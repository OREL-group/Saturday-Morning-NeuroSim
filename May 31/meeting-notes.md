## Meeting Recording

[YouTube link](https://youtu.be/v866RB8dUq8?si=TUIQmv9DdFCv3wIB)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114604819079949702)

## Notes
Background, not the paper. What happened to cybernetics — political forces, esoteric stuff.

Andrew Pickering —> “Cybernetic Brain” book, historical view.

our view (in #rg-cyb) is a lesser represented view. “Why are we talking about teleology?”

people had to wrap their brains around it.

why is it “negative feedback?” Distance from a goal —> a way to “scientific-size teleology”.


This week —> Fresight Neuro. more that just advanced connectomics. but not useful for understanding how the brain works.

collect data —> “whole brain emulation”. Article about complexity of biology. Do technology people think they will disrupt biology.

Complexity Discussion, Language Models.

Advanced connectomics. Comprehensive model of human metabolism. This is what brain emulation is like. 


Not at cell function, just at confirmation. Solving brain challenges along the way.


Explainability —> From Tokens to Thoughts (LeCun).

Computational Psychiatry (LLM paper).

Wiener’s lack of rigor —> still an issue. Is he a bit Buckminster Fuller-ish. 

Karl Pribram’s book, any good Wiener stories?


Wiener’s Alpha Wave and Mexican Hat wavelet (connection? Not really, but an indirect Fourier connection.

doesn’t make sense initially —> power-law behavior (amplifier-enhanced, no DSP back then). 

## TRANSCRIPT
     
Transcript     
0:00     
hello Hi How are you i'm good How are you     
0:09     
good Welcome So this past week we had uh a     
0:15     
keyboard meeting Leo was presented on some of his     
0:21     
work in that meeting Then Friday we had our open source meeting where Edy and Gia Grath     
0:30     
presented on their work and we also had a discussion about     
0:35     
demo or die which of course is this idea that you know you have to kind of demo     
0:42     
your ideas in order to show their worth to you know maybe your team your     
0:48     
working team or the larger world And sometimes it's good to do these demos to     
0:54     
work out problems and figure out what the scale is what the scope is of the     
1:00     
problem but as well as how to solve technical problems how to present them so that like other people can help you     
1:07     
solve them And sometimes in presenting them you help yourself because you get a     
1:12     
clear fix on what the problem is that you're having So this is all to lead into the coding     
1:19     
period for Google Summer of Code which is starting tomorrow and continuing I     
1:25     
think till late August early September     
1:31     
So that's good All right so let's get started I have a few kind of features I     
1:36     
want to share before we get into some main topics So the first thing I want to     
1:43     
talk about is this uh slashdown article I think this was posted in the slack     
1:50     
This thread is uh people should know about the beliefs LLM's forum about them     
1:55     
all Jonathan Elatrin is a law public policy CS professor at Harvard also     
2:01     
director of its Burkeman Klein Center for Internet and Society He's also a longtime slash readader This is the     
2:09     
slash ID of this person and writes in to share his new article in the Atlantic So     
2:15     
this is the article The article is inside the AI blackbox I think they've     
2:20     
been putting out a number of special art some sort of special topical issue of     
2:26     
the Atlantic on artificial intelligence and a bunch of different uh     
2:32     
articles on that So this one is what AI thinks it knows about you what happens     
2:38     
when people can see what assumptions a larger language model is making about it     
2:44     
And so I don't know if I have article or access to the full article but it kind     
2:49     
of talks about um larger language models and how people perceive those models     
2:57     
to perceive them basically So it's this sort of metaccognitive response to something     
3:05     
that is I guess quasi cognitive So large language models such as GPT     
3:12     
Llama Claude and Deep Seek can be so fluent that people feel it uh it as a U     
3:19     
So they kind of ascribe this article u to the chat GPT or the llama or the     
3:28     
deepseek as they interact with it and it answers encouragingly as an I So you     
3:35     
know it it acquires pronouns The models can write poetry in nearly any given     
3:40     
form read a set of political speeches and promptly sift out and share all the     
3:46     
jokes draw a chart code a website etc So this is you know the idea that you're     
3:51     
ascribing some sort of human aspect to the model How do they um how they do this uh     
3:59     
these and so many other things that were just recently the sole realm of humans     
4:04     
So you know these are things that humans can do but we you know we we couldn't     
4:10     
necessarily automate them easily and you know and so how do you     
4:15     
how do they do this practitioners are left explaining jaw-dropping conversations rabbit from a hat     
4:22     
extractions with armwaving that the models are just predicting one word at a time for an from an unthinkably large     
4:30     
training set scraped from every recorded written or spoken human utterance that can be found Uh fair enough Or the small     
4:38     
shruging cryptic utterance of fine-tuning and transformers So you know it's like     
4:44     
basically people are having trouble figuring out how this actually works We're going to talk about you know ways     
4:50     
that we can overcome this lack of understanding in a little bit But     
4:56     
basically the idea is that people don't exactly know how the model is doing this     
5:01     
These aren't very satisfying answers for how these models can converse so intelligently and how they sometimes air     
5:07     
so weirdly But they all we got even for model makers who can watch AI's gargantuan numbers of computational     
5:14     
neurons is they operate You can't just point to a couple of parameters among     
5:19     
500 billion interlinkages of nodes performing math within a model and say     
5:25     
that one represents a ham sandwich and the other one represents justice Um     
5:31     
there is an aspect of this which we call all of us in the field called a black box You know you don't fully understand     
5:39     
You can't quite tell why it said this or why we got it wrong We have some ideas     
5:44     
and our ability to understand this gets better over time But that's where the state-of-the-art is So this is just kind     
5:51     
of um the thinking of a lot of tech CEOs is basically that we don't you know it     
5:57     
is a black box and that you know there it's we probably need some sort of grand     
6:04     
challenge to actually figure out what's going on and to classify because even if     
6:09     
you have that circuit and you define it you don't necessarily know how the     
6:14     
circuit is doing what it's doing So this is a problem of interpretability     
6:22     
as we've talked about in past meetings and this is part of the thing about the     
6:28     
sort of the mystery of the agent to a human because when you     
6:33     
interact with something and of course that's true of brains as well We don't necessarily understand what specific     
6:41     
neurons produce a certain behavioral output I mean that's kind of the whole     
6:46     
premise of neuroscience and the whole premise of that article that they wrote several     
6:53     
years ago on can a neuroscientist understand a microprocessor That is to say if you     
6:59     
were to be if you were given a microprocessor without knowing what it did could you figure it out could you     
7:07     
reverse engineer it and figure out its function at the level of how we understand microprocessors today     
7:14     
you know this this is a this is a a question that's been a long time sort of coming for the answer So they have these     
7:21     
observability tools Uh this one is from Transluc This is the transluce model     
7:28     
investigator Uh this is uh on transluces model investigator I can help you     
7:34     
understand and debug language model behaviors Let me walk you through a tutorial of my interface together we'll     
7:42     
uh do three things The first is to observe a particular model     
7:48     
behavior or I'm sorry the first is to observe a peculiar model     
7:53     
behavior The second is to understand why it occurred and the third is to fix an     
8:00     
issue So the idea of this is you're tracing it through the network You're trying to get this     
8:06     
understanding of why something occurred Maybe a model hallucinates or maybe it     
8:12     
does something that you didn't expect it to So this is a tool that helps you do this Click on a demo to get started So     
8:19     
fix AI's inability to sort numbers Let's try that And so it opens up And I guess     
8:27     
let's see it says uh sure let me ask the model to sort some numbers And it says     
8:33     
something looks wrong 9.10 should be the smallest number Click the token you     
8:38     
think is wrong to surface neurons that influence the mistake So basically I can go to something I think is an error and     
8:45     
I can get Okay there we go Um so this actually I don't know what's going on     
8:50     
here Oh okay This is where it's sorting numbers like this Nine is down here So     
8:57     
if I click on a number it says I found some neurons that highly influence your     
9:04     
selection I group their behaviors into these clusters and so they have these clusters of neurons that you can look at     
9:11     
This is four neurons here with this chemical nomenclature and functional groups and this four neurons over here     
9:19     
at the request for restricted information feedback etc And so it says mouse over a cluster     
9:26     
to see which of its tokens which tokens its neurons fire on Click any cluster to     
9:31     
learn more So let's click on this left one It gives me a list of high influence     
9:37     
neurons And it has two modes activation mode and attribution mode So it almost     
9:44     
acts like a little annotation model for like you might find in     
9:50     
biioinformatics where it actually gives you like something like a in this case it's a neuron It has an ID and then it     
9:58     
has this explanation of what it's doing All right So then this is this token     
10:03     
here number eight which is nine This is out of order Um this is just showing for     
10:10     
the attribution mode the ID here So you have the ID in this list here Okay So we     
10:17     
have the activation mode here which is where we have a bunch of different     
10:22     
explanations for different I guess neuron IDs Then we have the attribution     
10:28     
mode which is here where you have the same IDs and you have explanations So     
10:35     
I'm having trouble kind of matching the two for some reason But that's okay because I just wanted to show you what     
10:41     
this looks like And again you know these are I guess supposed to be     
10:47     
explanations for kind of what each neuron is doing and it's you know maybe part of the task     
10:53     
or I'm not really sure how I don't know how this actually works but it's     
10:58     
interesting and I'd like to explore it a little bit in a little bit more detail but perhaps not this in this     
11:05     
setting So let's go back to the article Um actually let's go back to the slash     
11:12     
article since I think we got a sense of what they're trying to do in that article     
11:17     
So uh we have some feedback about this article     
11:23     
um uh and the way that Jonathan Zat train the author of the Atlantic article     
11:29     
describes it following anthropics bridge obsess bridge obsessed golden gate cloud     
11:36     
which is this uh I guess a model that they're uh highlighting colleagues at     
11:42     
Harvard's Insight Plus interaction lab would have produced a dashboard which I think we just saw that shows what     
11:48     
judgments llama appears to be forming about a user's age wealth education     
11:54     
level and gender during a conversation I wrote up how weird it is to see the dials turn while t talking to     
12:01     
it and what some of the policy issues might be Um and then uh this statement here     
12:08     
llama has open accessibility parameters So using it using an observability tool     
12:14     
which is the translucent tool that we just saw from the nonprofit research lab     
12:20     
transucers finally revealed what we might anthropomorphize is the model's belief     
12:26     
beliefs about its interculer which is the person who is querying the model Um and you know     
12:34     
basically prompting it with things Uh Zetrra's article notes If I prompt the     
12:40     
model for a gift suggestion to a baby shower it assumes that I am young and female and middle class It suggests     
12:47     
diapers and wipes or a gift certificate If I add that the gathering is on the     
12:52     
upper east side of Manhattan the dashboard shows that the large language model amending its gauge of my economic     
12:59     
status to upper class The model accordingly suggests that I purchase luxury baby products from high-end     
13:06     
brands like Aiden and Ni Gucci Baby and Car Cartier or     
13:11     
customized piece of art in a family heirloom that can be passed out If I then clarify that it's my boss's baby     
13:19     
then I'll need extra time to take the subway to Manhattan from the Queen's factory where I work The gauge carines     
13:25     
to working class and male and the model pivots the suggestion that I gift a practical item like a baby blanket or a     
13:33     
personalized thank you card And so the short of this is that large language     
13:38     
models not only contain relationships among words and concepts They contain     
13:43     
many stereotypes both helpful and harmful from the materials in which     
13:48     
they've been trained and they actively make use of it So basically what it's     
13:54     
saying is that if you give the model a training set it basically regurgitates a     
14:00     
training set by and large including a lot of the sort of the stereotypes that     
14:05     
exist in that training set And you know is that like what people do in some ways     
14:12     
yes But you know this is pointing out kind of how a large language model     
14:18     
arrives at its answers Anability for users or their proxies to see how models behave     
14:24     
differently depending on how the model stereotype them would place a helpful real-time spotlight on disparities that     
14:31     
would otherwise go unnoticed The trains article argues indeed the field has been     
14:36     
making progress enough to raise a a host of policy questions that were previously     
14:42     
not on the table If there's no way to know how these models work it makes accepting the full spectrum of their     
14:49     
behaviors at least after human efforts at fine-tuning them an all or nothing sort of     
14:55     
proposition But in the end it's not just the traditional information that advertisers try to collect With large     
15:02     
language models the information is being gathered even more directly from the user's unguarded conversations rather     
15:09     
than more mere search inquiries and still without any policy or practice     
15:14     
oversight So this is kind of just a kind of     
15:20     
thinking about how large language models sort of uh you know consolidate     
15:29     
the beliefs of people using So this is interesting stuff and of course people     
15:35     
have this idea of how they work and you know they have to sort of ascribe ways     
15:41     
of thinking about that but we have these tools like trans loose that can help us     
15:47     
analyze at sort of a neuron level how these answers are being put together so     
15:53     
we can audit these systems Another tool that we have uh and     
15:58     
I think this is also posted in the Slack is from anthropic and so this is a blog     
16:05     
post that they put out in their uh corporate uh research blog I guess uh on     
16:11     
interpretability and they have these open- source circuit tracing tools that they offer Um so this is um basically     
16:21     
taking a model looking at some uh answer to a prompt and then giving some     
16:29     
statistics about how it's arriving at that answer So in our recent     
16:35     
interpretability research we introduced a new method to trace the thoughts of a large language model So this is where uh     
16:43     
this article uh tracing the thoughts of a large language model and this is uh     
16:48     
there's a video here and it kind of talks about how     
16:53     
uh knowing models like how knowing how models like Claude think would allow us     
16:59     
to have a better understanding of their abilities as well as to help us ensure that what they're doing they're doing     
17:05     
what we intend as well as to help us ensure that they're doing what we intend to do what     
17:13     
we intend them to For example bod can speak dozens of languages What language if any is using     
17:21     
it is using in its head So is it using natural language in its head or is it is using something else is it translating     
17:28     
from one language to another cloud writes text one word at a     
17:33     
time Is it only focusing on predicting the next word or does it ever plan ahead     
17:40     
the third point here is quad can write out its reasoning step by step Does this explanation represent the actual steps     
17:47     
it took to get an answer or is it sometimes fabricating a plausible argument for a foregone     
17:53     
conclusion and so we take inspiration from the field of neuroscience which has     
17:58     
long studied the messy insides of thinking organisms and try to build the kind of AI microscope that will let us     
18:06     
identify patterns of activity and flows of information There are limits to what you can learn     
18:12     
just by talking to an AI model After all humans even neuroscientists don't know all the details of how our own brains     
18:19     
work So we look inside And so they share two new papers     
18:24     
in this article linked from this article to those papers um in developing this microscope the     
18:31     
application of it to see new AI biology is the term that they're using here So I     
18:37     
find this interesting because they call it AI biology but they do a very kind of tech industry characterization of     
18:43     
biology So in the first paper which is this um     
18:49     
paper on attribution graphs we extend our prior work locating interpretable concepts or features inside a model to     
18:58     
link those concepts together into computational circuits revealing parts of the pathway that transforms the words     
19:05     
that go into claw into the words that come out In the second article which is     
19:11     
also in attribution graphs we look inside claude 3.5 haiku performing deep     
19:17     
studies of simple tasks representative of 10 crucial model behaviors including     
19:23     
the three described above Our method sheds light on a part of what happens     
19:28     
when Claude responds to these prompts which is enough to see solid     
19:33     
evidence and that then they give these three points The first is Claude     
19:39     
sometimes thinks in a conceptual space that is shared between languages     
19:44     
suggesting that it has kind of a universal language of thought We show this by translating     
19:50     
simple sentences into multiple languages and tracing the overlap and how cloud processes We'll get to the back to this     
19:59     
tool in a minute But um that's one insight and I think that's interesting especially given that     
20:05     
discussion we had on languages and uh compositionality I     
20:10     
think it was last week So that's that's an interesting point There's been this debate in     
20:16     
linguistics about universality of language and language learning So this     
20:22     
actually supports that uh argument Number two is that claude will plan what     
20:29     
it will say many words ahead and write to get to that destination We show this     
20:34     
that in this realm of poetry where it thinks of possible rhyming words in advance and writes the next line to get     
20:42     
there This is powerful evidence that even though models are trained to output one word at a time they may think on     
20:49     
much longer horizons to do so So again this is where has the sort of     
20:55     
I guess you could say mental model of the words that it wants to produce or the tokens it wants to put     
21:02     
together Um you know this is I don't know if it's like poetry necessarily but it's definitely like the schema that it     
21:09     
forms And so um that's interesting I don't know if     
21:15     
their interpretation is correct on that But number three is that claude on occasion will give a plausible sounding     
21:21     
argument designed to agree with the user rather than to follow logical steps So     
21:28     
it's interesting that it kind of tries to agree with the user and all that We show this by asking it for help on a     
21:35     
hard math problem while giving it an incorrect hint we're able to catch it in the act as it makes up fake its fake     
21:43     
reasoning providing a proof of concept that our tools can be useful for flagging concerning mechanisms and     
21:51     
models So again we want to be able to find you know in cases where models     
21:57     
behave in in certain ways that are maybe interesting or troubling or not quite     
22:03     
what we we think should be the case um you know making errors things like     
22:10     
that We want to be able to find out and interrogate the model to see     
22:16     
why We were often surprised by what we saw in the model In the poetry case study we have set out to show that the     
22:23     
model didn't plan ahead and found that instead it did In a study of hallucinations we found the     
22:29     
counterintuitive result that Claude's default behavior is the decline to speculate when asked the question and it     
22:37     
only answers questions when something inhibits this default reluctance And in response to an example     
22:43     
jailbreak we found that the model recognized it had been asked for dangerous information well before it was     
22:50     
able to gracefully bring the conversation back around While the problems we study and     
22:56     
often have been analyzed with other methods the general build a microscope approach lets us learn many things we     
23:03     
wouldn't have guessed going in which will be increasingly important as models grow more sophisticated And so this is     
23:10     
scientifically interesting but it's also important for understanding systems and understanding how they     
23:17     
work Okay So then they they have this tour of AI biology where they talk about     
23:23     
um kind of the the evidence for what they're suggesting um and this is where you know Claude     
23:32     
speaks dozens of languages fluently from English and French Chinese and Tagalog     
23:38     
Uh how does this multi-ingual ability work is there a separate French claude     
23:43     
and Chinese claude running in parallel where there's some sort of cross-lingual core inside And so they show that     
23:51     
there's this sort of conceptual universality that exists in the     
23:56     
model Um and they they kind of link this back to linguistics Recent research on     
24:02     
smaller models has shown hints of shared grammatical mechanisms across languages     
24:07     
We investigate this by asking Claude for the opposite of small across different languages and find that the same core     
24:14     
features for the concepts of smallness and oppositeness activate and trigger     
24:19     
our concept of largeness which gets translated out of the uh out into the language of question     
24:27     
uh we find that the shared circuitry increases with model scale uh with quad 3.5 haiku sharing more than     
24:34     
twice the proportion of its features between languages as compared to a smaller     
24:40     
model So then they also talk about this poetry example where they find that     
24:46     
claude plans ahead before starting the second line it began thinking of potential on topic     
24:53     
words that would rhyme with grab it And so then with these plans in mind it     
24:58     
writes a line to end with the planned word So it basically has the way it approaches poetry is it hits the end of     
25:06     
this sentence here and then it has to kind of come up with a     
25:12     
rhyming verse here So it says a rhyming couplet Uh he saw a carrot and had to     
25:19     
grab it His hunger was like a starving rabbit So it's picking something that rhymes with rabbit at the end of that     
25:25     
sentence and it's putting that token at the end and then it's able to assemble     
25:30     
this rhyming puppet It can do this uh from grab it to     
25:37     
habit or it can also inject things Um if     
25:42     
we so in the injection case if we replace the concept with a different one     
25:48     
can again modify its approach to plan for the new intended outcome So we have the rabbit concept     
25:55     
here in these top two examples where we have this rhyming couplet and then we     
26:02     
have suppression uh and then we have injection And the injection is where you inject a green     
26:09     
concept at the end of the line grab it So instead of rhyming it produces green     
26:14     
at the end of this next sentence and injects the token at the     
26:19     
end So it's kind of interesting how it can do it can you know work around these     
26:26     
things and plan ahead to the next line So whether that's actually the way     
26:31     
poetry works we don't know necessarily because neuroscientists don't necessarily know     
26:37     
how that works Uh but we can uh sort of you know play around with the     
26:44     
internal state and modify it So that's you know their evidences that there's an internal state being formed aside from     
26:51     
just assembling tokens and they can manipulate that internal     
26:57     
state Uh then there's of course mental math and you know this is a classic well     
27:03     
we saw the example in the last demo and they show that there are these complex parallel pathways in Claude's thought     
27:10     
process when doing mental math we have these different ways of getting to a certain answer and they've kind of     
27:18     
traced these out and so uh yeah so that's     
27:25     
uh so that's kind of an aside side from this demo here which is this circuit     
27:31     
tracing tool here Um they have this neuronedia interface which     
27:37     
is this interface where they kind of show it's a circuit tracer for large language models So let's generate a new     
27:45     
graph It says enter the prompt to visualize and we could use any model we     
27:51     
want We can use we'll use uh Gemma 2.2b 2B and yeah there are some parameters     
27:57     
here We'll just go with the default parameters It's going to generate something in about 30 seconds There's a     
28:03     
graph underneath here So yeah Okay it generated the graph successfully There's     
28:08     
a test graph under here but let's see what this one looks like Open the graph and it's operating on my prompt What is     
28:14     
the history of Saturday morning neural sim and I guess we have this graph here     
28:21     
We have these white nodes So we're it kind of goes from left to     
28:27     
right and it goes through the prompt and this is what is a history of Saturday     
28:35     
morning neurosin And then this I guess is just kind of additional things that     
28:43     
have to do with the entire prompt Um so this kind of goes through and this     
28:49     
shows these I guess from L0 to L25 And I'm not really sure what it's     
28:56     
you know other than like looking at some of these statistics The statistics pop     
29:01     
up here So you have things like you know end of sentence punctuated punctuation     
29:08     
preceded by adjectives and conjunctions You have say read or     
29:15     
continue words related to question or inquiring law related terminology and     
29:21     
references to specific cases or legal entities question mark symbols and narrow by words like multiple and factor     
29:28     
So it's taking the features of the prompt It's not necessarily any sort of     
29:33     
meaning It's just the features uh of the of the words of the statement and you know those are being     
29:40     
activated but then you also have things very specific to the words in the prompt     
29:46     
So what is the word who the word part followed by prepositions or words     
29:53     
related to sections or components how what or whom questions     
29:58     
and any words associated with questions Layer three     
30:05     
Uh this one is words related to legal proceedings and permissions This is for     
30:10     
history So there are all sorts of things that get activated when you prompt It     
30:15     
might operate word by word but then it also has the features of the entire prompt And this just kind of breaks this     
30:22     
down So I'm not really sure how to interpret this graph other than to say it's producing a graph It's this you     
30:29     
know it's the way they're doing circuit tracing And I'm sure Morgan would have some things to say about this     
30:36     
Um so I don't know I don't know if he's you know I I I would love to Um I     
30:45     
am unfortunately in the car So So I want I want to be safe Yeah Yeah     
30:52     
But uh uh yeah we'll we'll be we'll be at the lab very very shortly All right     
30:58     
Yeah But but certainly found this very interesting Yeah     
31:05     
And um yeah I could say more later Yeah we can     
31:10     
circle back around Yeah that's fine Yeah All right So yeah that's and then so that's a     
31:15     
whole set of things about large language models and sort of auditing large     
31:22     
language models this concept of interpretability and then the tools that     
31:27     
we use and and they call them circuit tracing and they even have this term AI biology which is like looking under the     
31:34     
hood and seeing what it's doing BD says "But it's interesting how it     
31:41     
could create that graph." So would you like to say more about that or     
31:49     
No I just didn't expect like that Yeah     
31:56     
Yeah Yeah Yeah I don't know Yeah I don't know how     
32:02     
exactly you know it's able to produce a graph I guess just by quering what it's doing     
32:09     
but yeah how do we know it's accuracy like how do we know whether it's completely direct     
32:16     
or not yeah I don't yeah I don't know exactly how it's figuring out what node is doing     
32:23     
what I guess you can get a reading of the whole network when it's activated and you can uh you know you know kind of     
32:31     
what the weights are and you know kind of what is happening at each node So     
32:36     
yeah but I don't know how it's getting some of these phrases like like a math delimiter you know or     
32:43     
word issued I guess it just knows kind of uh maybe a history of what what's been     
32:50     
generated I don't know     
32:56     
Yeah this is this is interesting though I mean and definitely want to dig in     
33:02     
Yeah Yeah Well anyways yeah that's just a small kind of sampling of that     
33:10     
Um all right Uh well let me finish up with these other two things and then we'll actually we'll get into maybe more     
33:17     
stuff on that I don't know if we have I think we have another article on large language     
33:22     
forms but I'll see So this next feature is this natural philosophy forum and this happened at     
33:30     
John's Hopkins this past week actually I think it's ending today um this is natural philosophy     
33:38     
uh so this is a space for people interested in investigating the foundations of reality at the     
33:45     
intersection of science and philosophy they said that there's supposed to be a video archive there are     
33:52     
video archives from the past in 2022 There's Dan Dennett and Jeffrey West     
33:58     
giving talks So this is for this year natural philosophy symposium Uh this is     
34:04     
happening at the Baltimore Marriott waterfront Um and     
34:10     
they have a number of speakers Uh the first one is David Chalmer's We talked     
34:16     
about consciousness Ryan Smith is the commentator um assuming he's active influencer or     
34:23     
Smith Um there was Sandra Mitchell and evolution and complexity Uh Brandon Agunu is the     
34:30     
commentator Um so we had people doing fundamental physics social     
34:36     
organization Malcolm Macgyver doing things on sensing and planning Malcolm Macgyver is always good to uh you know     
34:44     
very good He has a background in philosophy but also in biology and engineering So he does a lot of stuff     
34:50     
with equally electric fish and looking at how they do a lot of their uh sensing     
34:56     
and planning and embodiment So it's interesting Uh Nick Wayne was uh speaking on the origin of     
35:04     
life and uh so yeah we had a bunch of people who had there were a lot of     
35:10     
interesting topics here Um now I'm not sure when they're going to put up the videos for this but I I assume soon So a     
35:18     
lot of people from like you know the complexity community a lot of people from diff various areas of science and     
35:26     
then of course people Melanie Mitchell who's talking about AI and I saw some of     
35:33     
the like screenshots on blue sky where they were talking about some of the talks looked really interesting So this     
35:41     
is uh definitely something to come back to and think about more     
35:48     
And finally I found this tool here It's called Desmos which is this um     
35:53     
nice mathematics visualization studio And so they have these graphing     
35:59     
calculators these interactive graphing calculators that you can work with Um     
36:05     
and you can create your own You can start by typing in some equations putting in some visual you     
36:11     
know creating some visualizations It works kind of like a graphing calculator Um but you can produce these nice     
36:18     
notebooks uh where you can produce things like this which is a uh dot patterns and you     
36:26     
you know you can set it up like an interactive notebook like a collab notebook where you can annotate it and     
36:32     
then have equations and plot those equations out You can have a slider that     
36:38     
allows you to simulate for different parameters and then you know work through the problem with that So you can     
36:44     
change the parameters of this visualized model and we'll change     
36:50     
it this Oh there we go Kind of moved it All     
36:56     
right So it's it's kind of moving this thing around Yeah See now it looks like     
37:02     
a bunch of potato chips that are morphing into circles back again So as     
37:07     
you change the parameters you can play around with it and experiment and do all these things So that's a nice tool again     
37:15     
uh something I just discovered um online So     
37:22     
uh yeah we have any questions on any of that I mean I know we've discussed the     
37:27     
large language models     
37:37     
thing Okay     
37:43     
Interesting Oh the yeah the tool here is Desmos So this is     
37:48     
desmos.com and you can you know create your own graph or your own notebook     
37:56     
Yeah I think that's something     
38:02     
Yeah we've just uh discussed Geogra before and it's definitely sort of a     
38:08     
similar tool We want to talk about this article This was also posted in the Slack This is beyond semantics     
38:15     
unreasonable effectiveness of reasonless intermediate tokens So this was um bunch of authors     
38:22     
from Arizona State They're from this SCI lab The abstract reads "Recent impressive results from large reasoning     
38:29     
models have been interpreted as a triumph of chain of thought or coot." So this is again going back to     
38:37     
kind of tracing out the outputs of a large language model and understanding     
38:43     
that as a set of thoughts being expressed So there's this triumph of     
38:50     
chain of thought which is just basically how well a large language model produce     
38:55     
serial outputs and especially the process of training on coots sampled     
39:01     
from baseline language models in order to help find new reasoning patterns In     
39:06     
this paper we critically examine the interpret that interpretation by investigating how the semantics of     
39:12     
intermediate tokens often anthropomorphized as thoughts or reasoning     
39:18     
traces in which are claimed to display behaviors like backtracking self-verification and     
39:25     
metacognition actually influence model performance So I remember I said before that there is a sort of metacognitive     
39:31     
aspect to interacting with a large language model and that is that you know     
39:37     
large language model produces outputs We see them and interpret this as thought     
39:42     
or you know kind of think about it as analogous to what humans are doing when     
39:48     
we create those things Then we can trace them out of course using these circuit     
39:54     
tracing tools But you know again there's this question of whether it's actually     
40:00     
producing things Well it's anything It's like kind of how we do neuroscience in a way We can map out a circuit and we can     
40:09     
observe behavior and then we make some inference about what that behav what you     
40:15     
know what's generating the behavior what it means etc And     
40:21     
so we we're left with the same problem now is that you know we still     
40:27     
anthropomorphize these things as thoughts And so if we see something that looks human and we can trace it back to     
40:34     
this complex circuit then we think okay we know exactly what happened and it's generating this humanlike behavior but     
40:41     
it's still an anthropomorphization of you know what's going on     
40:47     
So they critically examine this interpretation um thinking about the semantics of     
40:53     
intermediate tokens um which are claimed to display the behaviors like backtracking     
40:59     
self-verification and metacognition Those improve influence model performance We train transformer models     
41:06     
on formally verifiable reasoning traces and solutions constraining both     
41:11     
intermediate steps and final outputs to align with those of a formal solver     
41:18     
So they're doing this sort of alignment where they're taking uh reasoning traces     
41:25     
and solutions and they're modifying them to align them with a solver By constructing     
41:31     
a formal interpreter of the semantics of our problems and intended algorithm we     
41:37     
systematically evaluate not only solution accuracy but also the correctness of intermediate traces thus     
41:44     
allowing us to evaluate whether the latter causal causally influences the     
41:51     
former Our experiments involved training transformer models on traces and     
41:57     
solutions generated by AAR search We noticed that despite significant     
42:02     
differences and improvements on the solution only baseline models trained on entirely correct traces still produce     
42:09     
invalid reasoning traces when arriving at correct solutions To further show     
42:15     
that tracing accuracy is only loosely connected to solution accuracy we then     
42:21     
train models on noisy corrupted traces which have no relation with the specific problem each is paired with and find     
42:28     
that not only does performance remain largely consistent to models train on correct data but in some cases can     
42:35     
improve upon it and generalize more robustly than out of distribution tasks     
42:42     
So this is an interesting um part here They're talking about     
42:48     
um where you basically want to understand if trace accuracy can be     
42:55     
characterized Is it the same thing as solution accuracy or is it something     
43:01     
else what they're arguing is that trace accuracy is loosely connected to solution accuracy So you know it may be     
43:09     
that there are some in some cases traces going to correspond with solution accuracy but that's not always the case     
43:16     
And I think you maybe saw that from some of the tools that they were using there or that they developed where you     
43:23     
have these sort of vague relationships with the prompt and the answer So this     
43:30     
is not you know something that we can say oh this is going to be work 100% of the time and we can really understand     
43:37     
what's going on under the hood with these tools They're just kind of guides to what's going     
43:44     
on And so one way to do this of course is to produce noisy corrupted traces     
43:51     
that have no relation to the specific problem So you know oftent times in     
43:57     
large language models you're faced with ambiguity you're faced with o other types of things and so this is where you     
44:05     
know looking at that especially in terms of model distribution tasks is uh what     
44:11     
we need to do and so these results challenge the assumptions that intermediate tokens or chains of thought     
44:19     
reflect or induce predictable reasoning behaviors and caution against anti     
44:24     
such outputs or over interterpreting despite their mostly correct forms as evidence of humanlike     
44:31     
or algorithmic behaviors in large language models or in language models     
44:36     
more generally So um yeah they basically interrogate this     
44:44     
model of you know looking at a large language model using these circuit tracing tools     
44:53     
and then saying okay this is exactly how it's putting together the answer and then interpreting the     
45:00     
outputs h as having these sort of ascribed cognitive aspects to them So     
45:06     
you know there's some maybe some sort of metacognition going on but we shouldn't be too quick to say assign certain types     
45:14     
of function to these traces or to these to these different     
45:19     
um circuits that that form So     
45:26     
uh this I'll read a little bit of the introduction here Recent advances in     
45:31     
general planning and problem solving have been spearheaded by so-called long chain of thought models most notably     
45:38     
deepseeks R1 These transformerbased large language models are further post-trained using iterative fine-tuning     
45:46     
and reinforcement learning methods following the now standard teacher force pre-training instruction     
45:52     
fine-tuning and preference alignment stages So this is teacher force     
45:58     
pre-training instruction fine-tuning and preference alignment These are three stages that uh go into this sort of uh     
46:08     
long these long chain of thoughts Uh they undergo additional training and reasoning tests At each     
46:15     
step the model is presented with a question It generates a sequence of intermediate tokens colloquially or     
46:22     
perhaps fancifully called chain of thought or reasoning trace and it ends with a specially delimited answer     
46:29     
sequence After verification of this answer sequence by a formal system the     
46:34     
model's parameters are updated So it is more likely to output sequences that end     
46:39     
in correct answers and less likely to output those that end incorrect answers     
46:45     
So we talked about this several meetings ago We even had that graph was like that set of concentric circles where they put     
46:52     
these different models in these different spaces where they did this sort of post training or postc     
46:59     
calibration So they did the training um and they fine-tuned the output and     
47:06     
this is kind of what they're referring to here So this is sort of this reasoning step where they're fine-tuning     
47:12     
the model and they're able to do this sort of reasoning     
47:18     
trace operation And so     
47:25     
um while typically no optimization pressure is applied to the intermediate tokens empirically it's been observed     
47:32     
that language models perform better on many domains if they output such tokens first While the fact of the performance     
47:39     
increase is well known the reasons for it are less clear Previous work is often framed in anthropomorphic terms claiming     
47:47     
that these models are thinking before outputting their answers Simultaneously     
47:52     
the process of performing more auto reggressive forward passes before outputting the final answer has been     
48:00     
credited as an instance of interference time scaling That is these models are     
48:05     
assumed to be doing the problem adaptive computations that we     
48:11     
uh so problem it's assumed to be doing problem adaptive computation Famously Deep Seeks R1 paper     
48:19     
claimed that one of the most impress impressive observed behaviors of their trained models was the so-called aha     
48:25     
moment I think we talked about this before as maybe like the OSHA moment and     
48:32     
like this is uh actually something that's in the neuros I know in the cognitive neuroscience literature where     
48:38     
there's this aha moment you know so this is where in humans you'll work on a     
48:44     
problem and you'll learn you you'll be exposed to things and you acquire knowledge and then there's this aha     
48:50     
moment where you get an insight and um so this is something     
48:56     
people have studied in human cognition and this is uh so they're kind of making     
49:03     
this analogy to human neurog neuros human cognitive neuroscience where they identified the     
49:09     
aha moment uh both in terms of behavior and in terms of the neural imaging     
49:16     
um as part of the chain of thought that it was producing in order to answer some question that a model output token aha     
49:23     
seeming to indicate that it had come upon a sudden realization while a human may say aha to     
49:29     
indicate exactly a sudden internal state change This interpretation is     
49:34     
unwarranted for models which do not have any such internal state and which on the     
49:39     
next forward pass only differ from the pre- aha pass by the inclusion of that     
49:45     
single token in their context Interpreting this token as meaningful in this way requires making an additional     
49:52     
assumption that has thus far been brushed to the side in discussions of how long chain of thought models     
49:59     
function What they do that the derivational traces they produce are     
50:05     
semantically meaningful in the same way that traces that were trained that they were trained on or at least in the way     
50:12     
of a human might expect them to be So this is impossible to check for a     
50:18     
lot of large models The intermediate tokens of massive pre-trained and post reinforcement learning models produce     
50:25     
meander for dozens of pages and are written wholly and ambiguous and polymantic natural language and perhaps     
50:32     
much worse are the result of long opaque training processes on data that we have     
50:37     
no access to and cannot compare against So this is again for R1 you have this     
50:42     
reinforcement learning step at the end So a lot of the this sort of last step     
50:48     
this this u reasoning training is done through reinforcement learning and it's     
50:55     
you know if it's not this is where you get your this ability to sort of trace things and uh reinforce reasoning So     
51:04     
they they have another point up here which is interesting which is that we're oftent times inferring an internal state     
51:12     
to these uh to to large language models And so this is something that we do in     
51:18     
human cognition all the time We talk about internal states and the internal     
51:23     
states aren't necessarily related to a certain circuit It's it's sort of maybe     
51:28     
it can be related to a circuit but it's this um sort of assumption that there is     
51:34     
this internal state that's being generated that there's this behavior there's this activity and then there's     
51:41     
some internal model or internal state that's being regulated and then there's     
51:46     
you know it's basically the output So you see this a lot of times in emotion     
51:51     
you know where you have emotional states or you have cognitive states and we have     
51:58     
to sort of have a placeholder an assumption of this internal state So     
52:05     
that's kind of and then of course in large language models we have a similar     
52:10     
thing where there's some sort of internal state sort of the collective behavior of the circuit and its     
52:17     
activation So this is another thing that you know we do know better in uh     
52:24     
studying human cognition but it is something to think about     
52:29     
um as as sort of this thing that we're making an assumption about Okay I think that's all for that     
52:37     
paper Um so we we had these are all things that are in the Slack Thank you for the people who posted these in the     
52:43     
Slack I think it's like Morgan and Bey're posting these things All right So why don't we Yeah     
52:50     
why don't we come back to the this discussion i'll do one more thing So yeah I want to talk a little bit about     
52:57     
this I want to talk a little bit about this brain inspired meeting that happened this week So last week we     
53:03     
talked about the fact that there was going to be a brain inspired reading um     
53:08     
meet on this uh Rosen uh Rosen Bluth at all paper the one that Jesse wrote the     
53:14     
blog post on um and it was very good very indepth and so the discussion group     
53:23     
hadn't happened yet and so I I wasn't able to make the discussion group but Jesse was and I think Morgan as     
53:29     
well So this is Jesse's uh post on this     
53:35     
Um and so this is Paul Middleworks brain inspired complexity group hosting     
53:40     
Malcolm le Andrew Pickering Luis Pizoa uh Sean Manny Anna Ryell Kevin Mitchell     
53:48     
Der Puff and many others uh discussing the 1943 paper behavior purpose and     
53:54     
teology This is the paper that in question is part of David Crockar's Santa Fe     
54:01     
Institute foundational complexity paper series What an interesting discussion     
54:06     
about the history of cybernetics and how many of its associated descendant adjacent fields     
54:13     
developed developmental biology systems engineering cognitive science AI Puology     
54:21     
versus behaviorism in various historical contexts Uh the paper was a response to     
54:27     
the prevailing scholarly attitudes that dismissed teological explanations as     
54:32     
unscientific and obsolete By redefining purpose in terms of feedback Rosen Blues     
54:38     
Winer and Bigalow sought to rehabilitate the concept of teology striving towards     
54:44     
a rigorous framework that would account for goal directed behavior in both biological organisms and in     
54:50     
machines And so yeah he points to his uh discussion of the     
54:56     
paper And so I guess this I don't have the original post so this is going to be     
55:02     
kind of hard to read but this is a kind of a screenshot here at the     
55:09     
bottom Uh they talk I guess about the uh source material for cybernetics     
55:18     
um there's this juxtiposition of protocyetics and complexity and then this is a screenshot     
55:24     
of people discussing the paper So I had a I guess I had some discussions with     
55:32     
Jesse in the Slack about this Um and so     
55:37     
this is his message in the uh RG side uh     
55:42     
channel This is a cybernetics reading group channel Um and this is the link uh     
55:49     
this article I think it's from MIT press from new speak to cyerspeak     
55:54     
um he says also happening now brain inspire complexity discussion on the     
56:00     
1943 paper it's mostly about cybernetics right now and almost nothing about the     
56:05     
paper so far to be honest and I responded with a laugh cry because it's kind of funny that sometimes you have     
56:12     
these discussions about papers that go sideways And I don't mean sideways in a bad way I     
56:17     
just mean like they don't you know it's like people will talk about like the history     
56:24     
of cybernetics and get stuck there And you know it's just kind of funny how     
56:30     
uh that went And so then I said uh and then we talked about proto I I saw that post and     
56:38     
this term protocyetics and I had to ask how are they defining protocyetics     
56:44     
you mean protocomplexity So you know we talked about complexity theory and how it sort     
56:50     
of formed out of these concerns about reductionism and some of the methods     
56:55     
that we used to study interactions between things and emergence and things     
57:01     
like that And those kind of came together in complexity theory Of course David Crockower's book the one that     
57:08     
Jesse referenced uh has been referencing in in our lab Uh     
57:14     
that's a very good introduction to sort of the anticedants of complexity theory because it goes through these papers the     
57:21     
1943 paper being one of them that kind of contributed to complex modern complexity theory at least the Santa Fe     
57:28     
Lake So I I thought you know there was maybe     
57:33     
they were also going to talk about proto complexity and I you know I I was curious as to what they meant by     
57:41     
protocyics The you know there is this sort of history of like you know     
57:46     
analogies like the steersman analogy and the name cybernetics being sort of a     
57:52     
Greek root word So there's been this it kind of draws from the history of     
57:58     
thought the history of uh natural philosophy And     
58:04     
so I was just curious what they meant by protocynetics Um and so Jesse says just     
58:09     
in the sense that the paper was before cybernetics was coined And yeah cybernetics of course we know that there     
58:16     
were these Macy conferences in the in the maybe late 40s early 50s and this     
58:22     
came a little bit before that Uh but it's interesting I don't know uh if     
58:27     
people have kind of formally defined that as protocybernetics because you know there     
58:33     
is there is a lot of stuff that say Norbert Weiner was doing before cybernetics or some of these     
58:40     
other people were doing before cybernetics was coined or became a hot topic So yeah it's interesting and it     
58:48     
might be worth having a separate kind of discussion or you know set of     
58:53     
discussions on what kind of came before cybernetics or what kind of led into     
58:59     
cyber notes and then Jesse said maybe I will change it to that word The     
59:04     
discussion itself is basically 60% plus about history and takes in politics     
59:10     
around cybernetics which was actually interesting to me but I don't think it related to the complexity discussion     
59:17     
much and then I said actually some discussion on where cybernetics came from was quite interesting a lot of     
59:24     
cybernetics is born of describing a new world of the time which involved communication and computer technology so     
59:31     
if you think about information theory A lot of that came out of Claude Shannon's work on uh telegraph technology telefan     
59:41     
things like that which were you know a newish technology and you had to sort of     
59:48     
optimize communication channels for those devices and then from that we got     
59:53     
this theory of information which has been applied in many different contexts     
59:58     
So you know you have these things that are born out of sort of an immediate need of the time and then they became     
1:00:05     
this sort of almost with this universal or universalist sort of assumption that     
1:00:12     
those kinds of models as kind of theoretical models applied to the world at large So again that's an interesting     
1:00:19     
thing to kind of think about and explore And then of course there were these     
1:00:25     
older concepts that had to be merged with these newer technological realities     
1:00:30     
So as you had communication computer technology and you know systems that     
1:00:36     
required us to think differently not just in a purely reductionist way about     
1:00:42     
function and things like that We had you know we had to come up with a new theory but we also had tools that were     
1:00:50     
available to us that came from the past And so we can think of this as like ancient Greece the insights of ancient     
1:00:57     
Greece We also had to reconcile some of the religious thinking about things like     
1:01:04     
teology with sort of a modern conception of things that you know maybe look     
1:01:10     
teological or actually artological and kind of reconciled that     
1:01:15     
and then like think people like Claude Bernard who proposed homeostasis which was developed you know     
1:01:23     
in later by Walter Cannon and other people where you In Bernard's conception     
1:01:30     
there was this nilu French word meaning this um kind of     
1:01:35     
world where things were regulated and Bernard you know didn't offer a lot of     
1:01:41     
technical uh rigor to that um that came later So you had these concepts like     
1:01:48     
homeostasis that were kind of you know maybe early scientific and then they had to be updated So I just you know I just     
1:01:55     
thought that that was really interesting that whole um set of things that come together not only to inform cybernetics     
1:02:03     
but complexity as well And then I asked what are the politics of cybernetics by the     
1:02:08     
way So then finally Jesse responds to that question with uh this there was a     
1:02:16     
lot of discussion of basically cold war impacts on its real life implementations     
1:02:21     
for governance and other things And of course we know that you know we had a lot of cybernetics work went into     
1:02:29     
military applications Um we know that some of the a lot of the     
1:02:35     
work that was done at the University of Illinois You know there was this lab the     
1:02:41     
biological uh computer computing lab that was funded basically by uh military     
1:02:47     
funding And when that ended up uh getting pulled or uh no longer being     
1:02:54     
available the lab kind of went away And so there was a lot you know you     
1:02:59     
oftentimes that's the case in engineering where you're funded by something like a military grant or some     
1:03:06     
sort of grant and then you can have the freedom to explore other things But     
1:03:11     
there's always that kind of you know people kind of see the practical application as the military grant or the     
1:03:18     
corporate grant and it's really kind of a you know it's kind of a weird kind of     
1:03:23     
dual existence for things Um and then of course project cybersin which was um you     
1:03:31     
know also had political uh undertones Project Cybersson was mentioned lightly     
1:03:37     
but also other things regarding Russian cybernetics and we talked about Chinese     
1:03:42     
cybernetics and our cybernetics group at one point So there were different schools of cybernetics around the world     
1:03:49     
It wasn't just in the US and England there were you know I think Chinese     
1:03:56     
cybernetics we talked about some of the things they were doing kind of in parallel to the people in in the English     
1:04:03     
speaking world which actually is is true of a lot of the history of science     
1:04:10     
um you know there there were there's like German embryology and Russian embryology and all these like fields of     
1:04:17     
embry sub fields of embryology that were very prominent like     
1:04:22     
back in the 19th and early 20th century when people didn't translate articles as     
1:04:29     
much there wasn't the standard of English in the international scientific community and so you had these like you     
1:04:36     
know whole communities where everyone to communicate say in Chinese it would be in China and they would do their own     
1:04:43     
kind of work And I'm sure that's true to an extent today in different places in the world but it's not like it used to     
1:04:50     
be where you would just be isolated from other countries So like the German embryologists for example     
1:04:57     
uh were notoriously sort of resistant or um late to the party in terms of uh     
1:05:05     
reading the works of Charles Darwin So it's really interesting to look at like late 19th century embryology German     
1:05:12     
embryology in that respect Um so also interestingish talk     
1:05:20     
about teology and quote unquote God stuff And yeah I'm not sure everyone understood just how much the paper was     
1:05:27     
intentionally reclaiming teology as a term or like why it mattered or needed to be reclaimed     
1:05:34     
It would be interesting to review that discussion and compare it with some reading group cybernetics reading group     
1:05:40     
videos of the past which we have on our YouTube channel This is we have a a playlist for the cybernetics reading     
1:05:47     
group and we we've done a lot of interesting stuff in that reading group I've gone through a number of books and     
1:05:53     
papers and uh so that that's something that we should revisit if we're     
1:05:59     
interested in uh these sorts of things It was it was interesting I think the     
1:06:04     
videos are recorded Um but I think it's fair to say     
1:06:11     
at least half of it and I ask I think Morgan was there Um at least half of it was     
1:06:20     
really like just background and not really about the paper and kind of what is cybernetics It was sort of it was     
1:06:26     
sort of it was on a personal note I think Bradley you will know this more than uh most other     
1:06:35     
people It was basically the the discussion     
1:06:41     
was probably about 60 to 70% of what I really was looking for     
1:06:48     
when I started a long time ago on my original sort of project way before I     
1:06:54     
ever doing a lab of what happened to cybernetics Okay like all answering the     
1:06:59     
questions of these political forces and then a lot     
1:07:06     
of a lot of like cold war and esoteric stuff like like not not     
1:07:15     
just the 30s and 40s and 50s but kind of 60s and 70s which I didn't have a lot to     
1:07:21     
talk you know I didn't I probably least familiar with that because I don't know     
1:07:27     
I Guess that was earlier Who was the guy     
1:07:32     
who joined who had all this like personal     
1:07:38     
history stories andrew Pickering the old guy or the Okay     
1:07:43     
Okay Yeah Yeah Andrew Pickering I think was sort of the     
1:07:49     
guest guest person I mean he's obviously written like was he the cybernetic brain     
1:07:55     
book i forget Yeah Yeah I think that's Yeah And it was cool because we It was sort of nice to actually have     
1:08:02     
a multigenerational community like you had you had the I don't know high school     
1:08:10     
undergraduate kids who showed up asked a couple questions You had Andrew at the     
1:08:15     
other end of the spectrum and it was sort of like big intellectual family learning     
1:08:21     
and sharing time which was a nice it was quite wholesome in a way Uh which is ironic because a lot of the topic was     
1:08:28     
like what was the weird stuff going on during the cold war and how were cyber     
1:08:34     
Um but it but it was it was more than that too we did get into the paper but     
1:08:41     
um some of it was I don't know     
1:08:50     
um it was so interesting because I feel like what we covered and how we came to     
1:08:55     
the paper in our reading group was actually almost one of the lesser represented views on it And I don't I     
1:09:02     
guess view maybe isn't really the correct word but more the the     
1:09:09     
the our history and the deep dives that we took     
1:09:16     
Everything you said in the Slack I think would have been interesting and relevant Not that people didn't know it but more     
1:09:22     
it didn't um I don't     
1:09:29     
think it if I if I had more time to prepare and and I did mention this I did say     
1:09:36     
this in in the meeting briefly but I would have I would have loved to kind of     
1:09:41     
more thoroughly emphasize and explored directly or at least at least     
1:09:46     
offered some some com I don't want to say competing but come maybe Wow I sound     
1:09:51     
like a a um I sound a bit like     
1:09:58     
a late late night in infomercial when I'm saying this but not competing but     
1:10:04     
completing but but really sort of a completing narrative to it uh because I     
1:10:13     
think there was a little it kind of took a while for everybody to collectively wrap their heads around why are we talk     
1:10:20     
why is why are we talking about teology like what what like what what what was what what was the tabooness of it and is     
1:10:27     
it was it taboo at the time and in in the paper in the background     
1:10:32     
like it yes like it was a big deal to     
1:10:38     
weave into this you know structure     
1:10:45     
of well maybe even better way to say it is to extract from the structure of of     
1:10:55     
of Sorry I'm just adjusting my situation here     
1:11:02     
It it the the repurposing of it like it it     
1:11:07     
was it was it was it was a very intentional argument against well as an intentional move to     
1:11:15     
quote unquote reclaim teology or at least try to distance from     
1:11:21     
it so that it could be used to do this thing that would become predictive and     
1:11:29     
create these lenses of analysis based off of feedback at the time Like there were some questions about why is it     
1:11:36     
negative feedback and and I I kind of wanted to I I wish I wish I had more inter     
1:11:43     
ability to interject and kind of get into well it's negative in the construct     
1:11:49     
of what they're saying because negative feedback is related to distance     
1:11:56     
from a goal like it it again that's how they're spinning purpose and     
1:12:01     
teology and they're doing all of this to get away from the perceived woowoo taboo     
1:12:08     
god stuff and and and empiricism that that and and and the you     
1:12:15     
know I'm not even saying right or wrong about it I'm not I'm not really even trying to be anti- like reductionist or anti-reductionist or polymic about it     
1:12:22     
but just there was there was a very specific juiposition which I think maybe     
1:12:28     
to us from now 25 is almost relevant excuse me is almost irrelevant     
1:12:34     
seeming or like well everybody feels that way now but I I I think I think there was an     
1:12:43     
important context that could have been emphasized just a little bit more um that that were things that we centered a     
1:12:49     
lot in our previous discussions So that that's there's more to say than that I I'll kind of say that and then hear if you want to     
1:12:57     
say more Morgan wants to say more and carry on Well I just wanted to get your ideas     
1:13:03     
about it and yeah Morgan let's move on to you and I know you wanted to talk about the larger language models as well     
1:13:10     
So what are your thoughts about all this     
1:13:17     
[Music] um     
1:13:26     
sorry I've been I'm multitasking here Okay And uh um so in terms of the     
1:13:36     
um uh complexity discussion yeah I can     
1:13:43     
start there Yeah I mean um you know at some point Paul did say     
1:13:51     
like so does anybody want to talk about the paper     
1:13:56     
right and I was waiting for that too But I was like it was that's why the tension     
1:14:01     
for me was like I kind of want to talk about the paper But also like I I as I just said like I've had this like     
1:14:09     
one of my original reasons to ever to even come down the path that I'm down was literally what happened to     
1:14:14     
cybernetics I was like I didn't want to interrupt this like vast context that was circumstantial and not not at all     
1:14:21     
but the like the it was mostly like discussion 20 30 40 years after the paper was ready for like for like the     
1:14:27     
first half hour or so Okay Well I did want to know that but     
1:14:33     
Yeah we did get to the paper So I mean you know that that that was that was     
1:14:39     
funnyish Um um that so he had to say that     
1:14:46     
Um but uh you know I I I     
1:14:51     
certainly you know I I could understand why the discussion went the     
1:14:57     
way it did Um anyway the um language models     
1:15:04     
uh work um I' I'd like to get into but um would     
1:15:12     
like to be in front of a computer where I can see see what I'm talking about So Okay I     
1:15:20     
will need a bit more bit more time That's okay Yeah Um but but very     
1:15:28     
interested Um I I can throw in a just a few you     
1:15:35     
know thing things that happened this week Um okay that were certainly     
1:15:41     
interesting too Um you know the foresight had its neuro salon     
1:15:49     
um here here this week and um we had the founder of uh Eon     
1:15:59     
Systems talk and um yeah I was I was pleasantly surprised     
1:16:05     
to see that it it involved more than     
1:16:11     
just advanced connetoics um uh uh they're definitely trying to     
1:16:19     
capture capture living systems over time you know again with     
1:16:26     
with certain caveats and and certainly not doing developmental     
1:16:32     
neurobiology Um     
1:16:38     
uh and I and I thought it was funny that you know he was talking about all these     
1:16:44     
amazing things we could do but somehow like     
1:16:51     
solving understanding the brain wasn't one of them It was just like oh we're gonna be able to do this we're gonna do     
1:16:57     
that And then somebody was just like oh well so you know does this have any kind     
1:17:03     
of regenerative medicine applications or does this have any you know Eddie's like     
1:17:09     
oh we don't this is doesn't understand you know how the brain works I was just     
1:17:14     
like "Well wait a second How are you getting anything if     
1:17:20     
you're not capturing brain activity or you know like     
1:17:25     
uh starting to form some sort of um model of what the brain is doing     
1:17:34     
yeah So basically the idea there was they want to collect data but they don't     
1:17:39     
really they don't want to say anything about anything else Well they they they want to collect data for this     
1:17:46     
this you know for this whole brain emulation Right Right But but it it's     
1:17:55     
it's you know where where you suddenly see suddenly jumps to a conversation     
1:18:01     
that's that's you know reminiscent of altered carbon and     
1:18:08     
and you know but somehow like but we're not solving any     
1:18:13     
brain challenges here you know like we're not we're not doing brain science right and I'm kind I kind of feel like     
1:18:21     
well you should be it leads to that conclusion right yeah     
1:18:26     
and there was it's this this totally it doesn't totally relate but I I think it     
1:18:34     
does I mean you know like it's it's it's a it was an article     
1:18:39     
um oh crap please tell me I saved it um it was an article about the complexity     
1:18:45     
of biology um and and kind of like     
1:18:55     
like asking the question does do do the do the tech     
1:19:00     
people really think that they're just going to come in and disrupt biology     
1:19:05     
Um when uh let me just see Yes Okay Yes     
1:19:13     
Um and this uh Yeah Can tech founders really disrupt biology even when the top     
1:19:20     
scientists only understand tiny pieces of it um places like Stanford     
1:19:27     
EML Harvard entire departments of brilliant scientists Well yeah Okay It's     
1:19:32     
not their brilliance it's just the the the complexity of it right     
1:19:38     
um so and then they they've got a picture of of the most comprehensive     
1:19:44     
computational model of human metabolism which you know is this this massive of     
1:19:52     
you know massive wiring diagram Right Right Um and you know I I kind of feel     
1:20:00     
like that that kind of describes whole brain emulation Right It's just like you     
1:20:06     
know it's this tech story that that tech people have sold     
1:20:12     
themselves you know Um and you know I'm still still waiting     
1:20:21     
for you you know I mean I just think it's it's super important again to say     
1:20:29     
like you know Al Alpha Fold as as amazing as it was right is like is did     
1:20:39     
not well it's still going to be a long time and a lot more alpha folds will     
1:20:46     
need to happen before you even get into selfunction Right Right Like like we're     
1:20:52     
you're not at selfunction at alpha fold right you're just you're still at     
1:20:58     
confirmation right Um     
1:21:04     
and yeah Anyway so I I I just think um     
1:21:10     
somebody somebody doing brain emulation should should be a bit more     
1:21:16     
um should say that they will necessarily     
1:21:22     
be solving brain challenges on the way Um but I I don't know if that's again     
1:21:28     
just um uh yeah at the same time I'm jealous     
1:21:34     
these these these are people who are raising money right so maybe maybe they're on to something     
1:21:43     
yeah this goes back to like I think uh recently in our meetings we talked about     
1:21:49     
the main criticisms of the human or the human genome project you know 25 years     
1:21:55     
later the idea being that you know we produced a draft of the human genome we     
1:22:00     
have a good understanding sequence uh you know sequences in the genome but     
1:22:07     
we don't know exactly what the functions are we do have some knowledge of the functions we have annotations we have     
1:22:14     
you know some experiments we can attach to certain genes and we have you know u     
1:22:20     
uh you know uh genome studies where you know you can look at how much different     
1:22:26     
genes contribute to different traits and those are you know uh like G-W was and     
1:22:32     
things like that but other than that you know it's like what is the you know human genome project still hasn't really     
1:22:38     
given us a lot of functional insights and so you know that's something that of     
1:22:44     
course when they when they they understood that I think when they uh did the human genome project that it was     
1:22:51     
just a beginning step of kind of giving you the tools to get to those insights     
1:22:57     
But you know and and so in that sense that's not was that wasn't the original intent of the project On the other hand     
1:23:05     
you know there is this expectation by people that there's like naturally lends itself to insights and you know maybe     
1:23:12     
this is an expectation setting problem Maybe this is a problem more generally of our of the hardness of the problem of     
1:23:20     
like actually finding biological function or identifying it and knowing you know getting familiar with it as     
1:23:26     
opposed to like sequence data which is easier I guess and so um you know that's     
1:23:32     
that's maybe where we are with the brain as well where we have you know it's very hard to get to this step of     
1:23:38     
understanding it's easy to build like circuit diagrams or you know uh finding     
1:23:45     
sort of these uh identifiers is what I call them you know Um but but it's     
1:23:51     
harder to get the insight into behaviors and things like that     
1:23:59     
Yeah Yeah Absolutely I mean you you remember how upset I was with the     
1:24:05     
schizophrenia right research guy talking about the failures of the human genome     
1:24:11     
project um and it's uh I felt     
1:24:16     
like the failures of his science education Yeah But um but yeah     
1:24:24     
uh and well I I I'm I'm super you know I'm     
1:24:32     
interested to know more about what he's trying to capture with time I mean in     
1:24:38     
terms of like like he does actually want to image live samples Um     
1:24:45     
uh so some of the the larger more wellunded projects are definitely just     
1:24:51     
advanced connetoics with you know using expansion microscopy     
1:24:57     
and things like that Um it was an interesting discussion of expansion     
1:25:02     
microscopy you know somebody asking if it was if it was     
1:25:08     
destructive and everybody's funny funny response was that like the most is     
1:25:14     
destructive the most destructive method possible     
1:25:21     
really not like slightly slightly less than just     
1:25:28     
blowing the sample up And then you know so there was an     
1:25:36     
interesting discussion of kind of the the the     
1:25:42     
necessary reconstruction that is involved to expansion microscopy Yeah Yeah So for     
1:25:51     
those who don't know expansion microscopy is where they expand the tissue blow it up basically you like     
1:25:58     
swell the tissue so that they can see that they can get greater resolution then they do the     
1:26:05     
microscopy So if you have a very small feature you expand it out and then get to see     
1:26:12     
it I guess you correct like the shape and all that just right     
1:26:18     
Yeah Yeah you you you really got to you know kind of piece     
1:26:24     
piece you know it's it's a little like forensics     
1:26:29     
Yeah As you as you kind of piece things back together but you know at the same     
1:26:35     
time it's the you you know what what you've lost with the destructiveness you've gained     
1:26:42     
with the kind of interior visibility right if I don't know if you had more     
1:26:48     
like if you want to do more insights on the large language models later Which which which paper did you cover for what     
1:26:54     
the for the large language model discussion uh it was oh we had the paper     
1:27:00     
on um so we talked about this paper beyond semantics the unreasonable effectiveness of reasonless intermediate     
1:27:06     
tokens I think this was posted in one of the Slack channels     
1:27:13     
Um and it has that title again the unreasonable effectiveness of     
1:27:19     
mathematics play on like and so the idea is that there's     
1:27:24     
this like um there I guess the intermediate tokens are maybe not     
1:27:33     
uh you know cognitive in the sense that maybe we ascribe the function that we     
1:27:38     
ascribe to it And so yeah Yeah And then we talked     
1:27:45     
about some of the uh circuit tools Um we talked about neuronedia which is a tool     
1:27:53     
um from I think anthropic and then this other tool     
1:27:59     
transl from a research group the the the work that they've done is is     
1:28:06     
impressive in terms of of trying to bring out you know     
1:28:13     
explanability Um but I I don't I I haven't done I     
1:28:19     
haven't done the work to Well that's okay Yeah To to to really um     
1:28:27     
do it justice Um they're they're was some interesting     
1:28:34     
you know um the what's the the     
1:28:41     
um I forget I think I put it in dev     
1:28:47     
neuroi Russ Paulre had recommended the the um the Stanford you know     
1:28:56     
computational psychiatry LLM paper is as     
1:29:01     
you know very much showing you you should not be using this your     
1:29:08     
therapist and the the the funny comments to this was like did this really need to     
1:29:14     
be a paper Yeah It seems kind of obvious Yeah Yeah     
1:29:21     
Yeah That was the probably the most common     
1:29:27     
comment which is funny So let me pull up the tokens to thoughts paper that Morgan     
1:29:32     
discussed So this is uh on the archive It's uh from tokens of thoughts how     
1:29:39     
large language models in humans trade compression for meaning     
1:29:44     
Um and so the abstract reads human organiz humans organized knowledge into     
1:29:49     
compact categories through semantic compression by mapping diverse instances     
1:29:56     
to abstract representations while preserving meaning So for example Robin and Blue J are both     
1:30:05     
birds Therefore most birds can fly Or you know you can make that     
1:30:10     
inference You can make you can take birds You can take instances of birds     
1:30:15     
You can attribute functions to birds And you know that of course not all birds     
1:30:21     
can fly Um but you can generalize from the concept of birds You build upon your     
1:30:28     
concept and then you generalize to some behaviors and you have this model of     
1:30:34     
birds You have this model of robin and blue jay Uh basically you're mapping these     
1:30:42     
different instances of something to this representation and you're preserving the     
1:30:47     
meaning of the instance but also providing this context and this this     
1:30:54     
larger uh category So that's how you know we're     
1:30:59     
basically or humans use language to construct these mental models or these internal models     
1:31:07     
These concept these concepts reflect a trade-off between expressive fidelity     
1:31:12     
and representational simplicity So expressive fidelity is where you have     
1:31:18     
this you know ability to um you know have sort of a a good representation     
1:31:28     
that represents all the different instant categories for which something is true but also in cases where it's     
1:31:35     
false but also representational simplicity meaning that you don't want to specify every single thing and every     
1:31:43     
single exception to this representation So you want a s simple type of     
1:31:49     
representation of maybe a lowdimensional representation but you also want to have something that's accurate when expressed     
1:31:57     
in different ways Large language models demonstrate remarkable linguistic abilities Yet     
1:32:03     
whether their internal representations strike a humanlike trade-off between compression and semantic fidelity is     
1:32:10     
unclear So we don't know well we think this is what's happening in humans but     
1:32:16     
in large language models we're not quite sure whether these internal representations     
1:32:22     
uh have the same kind of tradeoff or this optimized tradeoff between these     
1:32:28     
two things We introduce a novel information the D theoretic framework drawing from rate     
1:32:33     
distortion theory and the information bottleneck principle to quantitatively compare these strategies Analyzing token     
1:32:41     
embeddings from a diverse suite of large language models against seminal human categorization benchmarks We uncover key     
1:32:49     
divergences The large language models uh form broad conceptual categories that     
1:32:57     
align with human judgment They struggle to capture the fine grain semantic distinctions crucial for human     
1:33:04     
understanding So again these where large language models excel is in forming these broad conceptual categories and     
1:33:11     
these largely align with how humans form broad conceptual categories But then of     
1:33:17     
course they struggle to make these semantic distinctions So you'll get these categories that look like they're     
1:33:24     
you know sort of human cognition but then they can make a lot of errors that     
1:33:30     
are untyp not typical of human cognition So that's you know kind of     
1:33:37     
just drawing out the distinction between large language models and human cognition in terms of representations     
1:33:44     
and in terms of this expressive fidelity and you know expressive is a     
1:33:50     
term that the use in computer science not so much in cognitive science So it's     
1:33:56     
worth noting that this is not something that necessarily have an analog for in     
1:34:01     
human cognition Um more fundamentally larger language     
1:34:06     
models demonstrate a strong bias towards aggressive statistical compression     
1:34:12     
whereas human conceptual systems appear to prioritize adaptive nuance and contextual richness even if this results     
1:34:20     
in lower compression efficiency by our measures So this is where you know in     
1:34:25     
large language models it's all about compression statistical compression and     
1:34:31     
how to you know encode those things um in that way and then in human     
1:34:38     
conceptual systems there is this emphasis on nuance and richness despite     
1:34:44     
you know the need for I guess there's less of a need for statistical compression and in fact human conceptual     
1:34:52     
systems work against this in a number of ways Um so it's more important in human     
1:34:57     
systems to have or at least human systems have this ability to find nuance     
1:35:04     
to deal with ambiguity in different ways and to go from context to context And this is exactly the thing that large     
1:35:11     
language models struggle with And some of that has to do with this sort of statistical compression regime under     
1:35:18     
which these models operate So you know is this a product of sort of the     
1:35:23     
technical limitations of large language models where you need to have you     
1:35:29     
know despite the large amounts of computational power     
1:35:35     
that they already require you still need to compress statistically the     
1:35:41     
representations or is it you know this is something that human conceptual systems are adapted for     
1:35:49     
um and so really do emphasize so you know the argument that large language     
1:35:55     
models are basically the same as human cognition is in this case at least false     
1:36:02     
Um and there's a very fundamental distinction here     
1:36:07     
Uh so yeah human conceptual systems have this lower compressional efficiency and     
1:36:14     
so that's you know some maybe that's a good thing and but you know in if you're     
1:36:20     
looking for compressional efficiency it's a bad thing These findings eliminate critical     
1:36:26     
differences between current AI and human cognitive architectures guiding pathways towards     
1:36:32     
large language models with more human aligned conceptual     
1:36:39     
representations So this is um you know maybe something that we can use to     
1:36:44     
illustrate how to make large language models more like human cognition Say okay this is what we need     
1:36:51     
to focus on Um but yeah and and so I don't know     
1:36:57     
let's look at paper itself So they kind of go through     
1:37:05     
um and they said they highlight this framework for comparing compression and     
1:37:11     
meaning So to understand how large language models in human cognition     
1:37:16     
grapple with the fundamental challenge of representing meaning we introduce an information theoretic framework This     
1:37:23     
framework is designed to analyze the critical trade-off or tension between compressing information into efficient     
1:37:31     
representations and preserving this rich semantic fidelity essential for true understanding So this is the the point     
1:37:38     
that we made in the abstract drawing upon core principles for rate distortion     
1:37:43     
theory which is something Faud Shannon uh introduced in 1948 and the information bottleneck     
1:37:50     
principle which was introduced by Tishb in 2000 Our approach provides a cohesive     
1:37:57     
lens for addressing all three of our research questions Uh so their research questions     
1:38:02     
are as follows The first one is probing representational compactness by categorical     
1:38:10     
length And so they want to know how information is condensed into     
1:38:15     
categorical structures How do you take information and put it into a categorical structure is this you know     
1:38:22     
it isn't just simply a matter of throwing things in bins there's this whole process by which you take     
1:38:28     
information and put it into categorical structure so that they have some     
1:38:34     
comparable amount of information Um both human categorization and large language     
1:38:39     
model derived clustering simplify diverse items X into structure group C     
1:38:46     
So we have all these different types of things that we want to put into categories You want to structure the     
1:38:52     
groups so that you don't have you know um things that are categories that are     
1:38:58     
sort of not useful Um but they also you want them to be broad enough so that they represent     
1:39:05     
uh the true sort of diversity that you see in the world Uh so they assess alignment     
1:39:12     
between model based clusters and human categories So it's C LLM and C human by     
1:39:18     
quantifying shared information So this is based on mutual information which is where you take two things and you look     
1:39:26     
at the overlap in the amount of information that they share And so you can use information     
1:39:31     
theory to get this uh number offering an initial view and how similarity     
1:39:37     
compactness is achieved This principles this principle of efficient input     
1:39:42     
representation here relates to the complexity aspect of our framework The second question is probing     
1:39:50     
semantic preservation with internal structure So they want to assess how well meaning is preserved within these     
1:39:57     
compressed representations So we have uh compressed representations for large     
1:40:03     
language models of humans and then we want to know how well semantics are     
1:40:08     
preserved within each type of model For research question two we     
1:40:14     
investigate this by correlating words language model internal measures of item centrality with human typicality     
1:40:20     
judgments So we're using two different sort of criterion but we're trying to sort of compare So in origin language     
1:40:29     
models we use item centrality which is a measure of sort of these clusters Then     
1:40:35     
in humans use these typicality judgments So you're basically trying to find the     
1:40:41     
mean thing in that category the mean object category And whether that helps     
1:40:46     
you with these out of distribution things is I don't really know the answer to because out of distribution objects     
1:40:53     
are by definition either the things that are atypical or things that have not been     
1:40:59     
seen before So it's hard to sort of calibrate that to these kind of mean uh     
1:41:05     
categorical exemplars In any case you have these two different kind of criterion or ways for     
1:41:12     
viewing this And so then we want to probe how faithfully fine grain semantic     
1:41:17     
information is represented So for example can large language models capture the internal structure of C     
1:41:25     
humans so can large language models capture what happens in human categories     
1:41:31     
or given that human categories are fundamentally different at least in     
1:41:36     
terms of how they're sort of formed can language models capture that directly     
1:41:43     
and so this relates to the distortion or the fidelity aspect of our framework And then research question three is     
1:41:50     
evaluating the integrated trade-off of total representational efficiency So having explored     
1:41:56     
compactness and preservation in the past two research questions we leverage our full framework Research question three     
1:42:03     
employs a unified objective function uh which is detailed below to quantitatively assess the total     
1:42:10     
efficiency with which larger language models of human systems navigate middle     
1:42:16     
trade-off So that's uh how they're approaching that problem Very information theoretic     
1:42:27     
driven Okay So um any questions on that     
1:42:38     
i just you know that that     
1:42:43     
um has deep parallels in     
1:42:49     
how people study language and humans     
1:42:54     
Yeah Yeah It's a hard thing because it's like you can't just make the assumption     
1:43:00     
that they acquire information in the same way or they do categorization the same way right     
1:43:06     
Yeah No no no For for sure for sure Um and again I mean you know it it's a it     
1:43:14     
gets back to this you know I'm not one saying that we     
1:43:22     
should you know use them as synthetic humans Um but but we should certainly     
1:43:28     
approach it in the same way that we do experimental psych in general Yeah     
1:43:34     
And uh yeah you got to got to figure out the     
1:43:39     
figure out the space and it's it's measure     
1:43:47     
So let's move on to our final thing for today This is um you know we've been talking about     
1:43:55     
cybernetics and how you know we you know sort of the antecedence of cybernetics     
1:44:01     
and how there's this legacy of cybernetics especially for artificial     
1:44:08     
intelligence and some other areas of science Uh Norbert Wiener of course was     
1:44:13     
a main figure in cybernetics and he had of course we we talked about his arc of     
1:44:20     
intellectual production and it's really fascinating He's not just the cybernetics person He did a lot of work     
1:44:28     
on information theory and some other areas of of uh science and engineering     
1:44:34     
as well This is a medium article This is     
1:44:39     
by the CEO of ASO AIO AG I not familiar     
1:44:45     
with that but it was a I think an interesting little article um Norbert     
1:44:51     
Weiner's understated legacy in the age of AI So this is of course generated by Dowi It's a picture of an old Norbert     
1:44:58     
Weiner I guess with chalkboards and so forth Um so the article talks about sort of     
1:45:07     
Norbert Weiner's influence on AI research which is not necessarily     
1:45:13     
apparent to people from kind of at first glance Um he did of course uh the book     
1:45:20     
the human use of human machines which we went through chapter by chapter in our cybernetics reading group He also did a     
1:45:27     
lot of things on information theory did a lot of things on cybernetics and feedback And so all those things are     
1:45:34     
kind of setting up sort of modern AI research but also sort of modern     
1:45:39     
cognitive science because modern cognitive science uses this sort of cybernetics view of things And so um     
1:45:47     
this is you know definitely a worldview that way we in you know sort of     
1:45:55     
was at the formative cusp of and so this is something that we would like to know     
1:46:01     
more about So Robert Weiner's work has a lasting influence on AI research but     
1:46:07     
unfortunately is less well known to the general public Robert Weiner was a mathematician and philosopher who made     
1:46:14     
several significant contributions to the development of artificial intelligence Uh we's most crucial     
1:46:20     
contribution artificial intelligence was the development of cybernetics which created some of the theoretical     
1:46:26     
foundations from modern artificial intelligence Cybernetics dealt with the     
1:46:31     
control and communication of machines and living organisms and was an interdisciplinary field that drew on     
1:46:38     
insights from mathematics engineering biology and psychology So you know we     
1:46:45     
actually we've talked about the the cognitive science hexagon which     
1:46:52     
has like it's a shape that has at each point at each sort of vertex a field of     
1:47:00     
study So you know cognitive science I don't remember all the six fields that     
1:47:05     
contribute to cognitive science It's like philosophy mathematics psychology anthropology computer science     
1:47:13     
and one more or linguistics I guess And so you know cybernetics has the same     
1:47:20     
structure where there's these different input domains these different input fields and they contribute to the     
1:47:27     
interdisciplinary So it's you know I don't know if you     
1:47:32     
want to like overlap cybernetics with cognitive science cybernetics cube or     
1:47:38     
square with the cognitive science hexagon you're welcome to do that It     
1:47:43     
would be interesting compared As we astutely observed we have     
1:47:49     
changed the world more than we have changed our way of thinking and the new way of thinking is still partly that of     
1:47:55     
the preceding stage This is actually an important point what we were talking about with respect to the reading group     
1:48:03     
the history of cybernetics and that is you know the purpose of that 1943 paper     
1:48:09     
was to sort of change the way of thinking So it's not enough to just kind     
1:48:15     
of introduce ideas into the bloodstream of the intellectual world or into a field     
1:48:24     
You know you have to kind of change the way of thinking Uh you know     
1:48:29     
you have to propose maybe how terms should be redefined or how like this     
1:48:36     
last paper we talked about to remind people that were you     
1:48:42     
know what the fundamental challenge actually is because sometimes people lose sight of this Sometimes a lot of     
1:48:49     
ideas get interpreted and you know there are a lot of sort of adivistic ideas     
1:48:54     
about say communication and control that persist and so you know sometimes you     
1:49:01     
need to write a paper to remind people that this is a fundamentally new thing that we're dealing with I'm talking     
1:49:07     
about 1943 not in today's but so we need to really kind of reframe     
1:49:14     
everything We need to reframe everything we've been thinking about before You know we can't just take our old ideas     
1:49:21     
and move them into the future We can't just take human analoges of thinking     
1:49:27     
or change over time and just kind of work with those We need to kind of fundamentally rethink those     
1:49:34     
So in this quote uh Weiner predicted the trajectory of technology in the human     
1:49:39     
propensity to underappreciate the frameworks that fundamentally reshape our     
1:49:45     
existence Winner's work on cybernetics was based on the idea that machines and living organisms can be viewed as     
1:49:52     
information processing systems that rely on feedback and control mechanisms to     
1:49:57     
remain stable and adapt to changing conditions So this is like where we talk about homeostasis and alostasis and     
1:50:06     
things like that much more than just that simple feedback in control     
1:50:11     
methods Uh Norbert Weiner's work on cybernetics and feedback laid some theoretical foundations for artificial     
1:50:18     
intelligence His insights into the similarities between biological and mechanical systems have significantly     
1:50:25     
influenced its development and his concepts of feedback and control have been fundamental in the development of     
1:50:31     
modern intelligent machines I think we would like this quote Artificial intelligence is highly     
1:50:39     
interdicciplinary Therefore let's approach it as a multidisiplinary holistic discipline     
1:50:46     
Um and so I'm paraphrasing that but it's still interesting Um and then there's this book     
1:50:53     
Cybernetics second edition or the controlling communication in the animal     
1:50:58     
machine Um so that's that's that article So it's interesting kind of a motivation     
1:51:05     
for this paper which I found This is paper from Steven Strogat's     
1:51:11     
um and this is Norbert Weiner's brain waves I thought that would be a nice way     
1:51:16     
to finish up the meeting Uh kind of stitching together some of Weiner's work     
1:51:22     
that's maybe inside of cybernetics and some that's outside of cybernetics since we did a lot of work on signal     
1:51:29     
processing as well And so um this is uh basically     
1:51:37     
discussing his work in the series So this is uh the introduction     
1:51:44     
can zoom in here In the late 1950s Robert Wer became     
1:51:52     
interested in the spectrum of human brain waves So he published some papers in the late 50s and early 60s Along with     
1:51:59     
his medical collaborators he made high resolution and sephilographic recordings     
1:52:04     
from subjects who were awake but resting with their eyes closed Under these conditions the     
1:52:10     
electronlogram showed conspicuous activity at frequencies around 10 hertz     
1:52:15     
or the so-called alpha rhythm Figure one which I'll show you in a minute show a winner sketch of the     
1:52:21     
magnified spectrum around 10 hertz He writes "It would have been quite conceivable that there would not     
1:52:27     
be a phenomena of that sort For example it might have been that all of our work on the fine structure of     
1:52:33     
the brain waves is wasted However once we find this effect we're under an     
1:52:39     
obligation to try and give it explanation There are two things that are striking here One is the very narrow     
1:52:45     
line at the center of the spectrum and the other is that this line arises from a dip So let's look at this figure one     
1:52:53     
So this actually looks like a wavelet um I think the Mexican hat wavelet     
1:52:59     
specifically but this is basically what he's discovering in human alpha waves So     
1:53:04     
this is the frequency This is the 10 hertz band here There's a maximum here     
1:53:10     
and then it it falls off around 10 hertz And then there's this dip on either side     
1:53:16     
of 10 hertz And then there's this increase in in going sort of up in     
1:53:22     
frequency and down in frequency There's a secondary the secondary peaks and then there's this fall     
1:53:28     
off after that So this is these are human alpha waves this is what they discover in their work Um this is the     
1:53:36     
schematic sketch So it's basically the idealized wave but this is basically what they're looking at And again it's     
1:53:43     
you know um it's interesting because you know why does it do this you     
1:53:50     
would think well there's some heat at a certain frequency and then falls off and that's it Um but this is something that     
1:53:58     
you know is not uh a normal distribution and you know you maybe you     
1:54:04     
shouldn't expect to find those in time series or you know um in in the frequency band but that's what we have     
1:54:12     
So to explain the spectrum weer hypothesized that there is a population of oscillators in the brain whose     
1:54:19     
intrinsic frequencies are close to 10 hertz that these oscillators constitute     
1:54:24     
a more accurate oscillator and mass than they do single Um so that means that you     
1:54:32     
have in this um this uh frequency portrait you have a bunch of things     
1:54:39     
underlying the signal So you're recording a signal from a site you have this 10 Hz band and because there are a     
1:54:47     
lot of things contributing to it you have this complex function Um and so it's actually you     
1:54:55     
know these oscillators are kind of operating at this frequency close to 10 hertz and if you average it out you get     
1:55:01     
to 10 hertz And it's a nice neat marker and it has like a lot of significance in     
1:55:08     
the brain I guess But the point is is that it's not produced by a signal signal single uh single signal It's     
1:55:16     
actually the product of a number of oscillators kind of operating maybe stochcastically but kind of collectively     
1:55:24     
giving you this signal The idea is that the oscillators interact by pulling on each other's     
1:55:30     
frequencies So they're interacting as well as producing independent     
1:55:37     
signals So if an oscillator is ahead of the group the group tends to slow it down So Steven Stroat has been     
1:55:45     
interested in synchronization his entire career He wrote this book sync about 20 years ago     
1:55:52     
where he was talking about a lot of the stuff that people do     
1:55:57     
when they study uh firefly synchronization So fireflies will synchronize their flashing activity and     
1:56:05     
they'll do it by communicating with each other and using the signal as a the     
1:56:13     
uh their si their uh viciferous signal as a way to synchronize each other's     
1:56:19     
flashes So this is something that we also see in uh like the kerodoto     
1:56:26     
oscillator which is a model of different neurons oscillating in a population and     
1:56:33     
each neuron is influencing other neurons in that     
1:56:38     
population So basically the oscillators are behaving in a way that's regulating     
1:56:45     
the entire average And so what you see in this trace is where this is kind of     
1:56:52     
you know this is an active process It's not something that happens automatically Um it happens kind of dynamically and     
1:56:59     
sometimes you never get to the actual average But you can see the average     
1:57:05     
behavior of the oscillators is at 10 hertz and then there's some variation around the edge So these dips represent     
1:57:12     
places where you know you have um less activity and it's just because they're     
1:57:20     
operating around this mean and there's this space where you know as they're correcting each other where they le are     
1:57:26     
less likely to inhabit So you're basically describing sort of     
1:57:32     
this complex system in the simple um     
1:57:38     
trace If it's going too slowly the group tends to speed it up In this way the population of oscillators can achieve a     
1:57:44     
collective enhancement of precision This is basically also the way that     
1:57:50     
um uh bird flock the movement of collective movement of bird flocks are described If you go back to some of the     
1:57:57     
models of collective behavior of bird flocks basically the pe way people     
1:58:04     
formalize this is that birds exist in this flock that individual birds will     
1:58:09     
kind of behave and then they'll monitor the behavior of their nearest neighbors     
1:58:15     
And so the way that bird flocks are sort of coherent and stable is that they just     
1:58:21     
basically slow down when the neighbors slow down and speed up when their neighbors speed up And so they correct     
1:58:28     
themselves to the average or the mean of the group And so this just propagates     
1:58:33     
across these you know individual birds communicating with their nearest neighbors and propagates throughout the     
1:58:40     
flock until you get this coordination of the flock And of course you'll see this mean behavior but you also see these     
1:58:47     
weird transitional states which actually allow the flock to recover to another     
1:58:53     
stable state So this this um this portrait here that we see you know you     
1:59:00     
could extrapolate this out to other types of synchronized behaviors as well Liner tried to support his notion     
1:59:09     
of frequency pulling with the experimental evidence available in those days For instance he mentions an amazing     
1:59:15     
experiment involving direct electrical driving of the brain A sheet of tin was     
1:59:21     
suspended from the ceiling and connected to one terminal of 400 volt 10 herz     
1:59:27     
generator He writes that this apparatus can produce electrostatic induction in     
1:59:32     
anything in the womb and that it can actually drive the brain causing a decidedly unpleasant sensation I bet it     
1:59:39     
will Um so this is an experimental kind of setup that he made for this Um it is     
1:59:47     
probably wise to take Weiner's experimental claims with a grain of salt He rarely shows or sites actual data     
1:59:54     
Figure 11 in Weiner 1961 is the lone exception and as far as I know no one     
1:59:59     
has ever replicated his results Weer 1958 also attempted to account for his     
2:00:04     
observations mathematically but his approach was awkward and let known     
2:00:10     
However he did leave an important legacy He was the first to propose studying the collective behavior of biological     
2:00:16     
oscillators So this again was sort of the basis for some of the     
2:00:21     
synchronization that came later So Wener's work was 1958     
2:00:27     
1961 And then this led to people like Art Winfrey who published in     
2:00:32     
1967 1980 1987 did a lot of things with um wrote this     
2:00:38     
book the geometry of biological time This did a lot of work with oscillators     
2:00:44     
Um you know these these oscillators range from chemical     
2:00:49     
oscillators to neuronal oscillators to u other types of     
2:00:55     
collective behavior Uh so examples include pacemaker cells in the heart     
2:01:01     
lcotic synchrony and yeast cell suspensions collective oscillations in pancreatic beta cells synchronously     
2:01:09     
flashing fireflies crickets that chirp in unison and women's menstrual cycles     
2:01:14     
become mutually synchronized So these are all examples of this sort of type of     
2:01:20     
mutual synchronization So where we are kind of couldn't land the fish um these other     
2:01:28     
groups had worked on very specific systems and actually have made quite a bit of progress in this topic and again     
2:01:36     
there's this assumption of universality where you have all these different types of systems and they are all driven by     
2:01:44     
this simp I guess we want to call it a simple mathematical law but the simple     
2:01:49     
principle of organization uh we review some of these examples in     
2:01:55     
section two and then in section three in this paper we consider the classic model of mutual     
2:02:01     
synchronization The analysis of this model over the past 25 years has drawn out a wonderful range of subjects of     
2:02:08     
course nonlinear dynamics but also statistical mechanics and even plasma     
2:02:13     
physics and as we'll see remember what we spectrum has almost been explained in     
2:02:18     
a mathematical sense but not quite So this this one this uh spectrum in figure     
2:02:24     
one that I showed you that was something that they've people have tried to figure out and explain in the mathematical     
2:02:30     
sense they give some biological examples uh ranging from pacemakers to per model     
2:02:37     
oscillators and we won't go through that but this is these are some of the afterthoughts and kind of thinking about     
2:02:44     
how maybe some of the mathematical explanations for this     
2:02:49     
um the intuitive leaps in Kuromoto's analysis deserve our admiration but they     
2:02:54     
have also provoked some vigorous headscratching and this is of course the Kuromoto oscillator of the accompanying     
2:03:00     
mathematical analysis for example what is one to make of kuramoto's assumption that r is     
2:03:06     
constant u the theorem must be something like this for most initial conditions for     
2:03:13     
most realizations and for large fractions of the time r over time stays within in a     
2:03:21     
certain degree of the constant Um it's an open problem to make     
2:03:26     
this precise So there's some precision issues with these models Um this issue     
2:03:32     
could be difficult as Nancy Copel pointed out may be connected to questions about the foundations of     
2:03:38     
statistical mechanics irreversibility conquer occurrence etc So these are all     
2:03:44     
kind of these issues in complexity theory that um you know have to do with     
2:03:51     
dynamics Um and so you know there are a lot of open questions in terms of uh     
2:03:58     
looking at oscillators that are coupled and uncoupled and so there's a lot of kind of fertile ground for this So after     
2:04:05     
three decades of research the study of mutual synchronization is prospering theoretically But like many branches of     
2:04:11     
mathematical biology it has wandered too far from its source There is no serious     
2:04:16     
confrontation between theory and experiment We need to follow the example of two related fields excitable media     
2:04:23     
and central pattern generators Um so the theory of excitable media is     
2:04:28     
developed alongside experimental work on spiral and scroll waves and the bellisop jacotinsky     
2:04:34     
reaction Similarly man trout and copel's theory of phase locking in chains of oscillators has been directly motivated     
2:04:42     
by experiments on the central pattern generator of lamprey and has led to some surprising     
2:04:48     
predictions that were recently verified by their experimental     
2:04:53     
collaborators But I suspect that mutual synchronization is going to be co-opted by physics where the oscillators are     
2:05:00     
closer to those imaginary theories There have already been some exciting applications to charge density     
2:05:06     
waves into arrays of microwave oscillators and superconducting Josephson junctions Uh on second thought     
2:05:15     
perhaps co-opted is not the right word mutual synchronization began in physics     
2:05:20     
with Hygen's discovery of phase locking between two pendula hung on the same     
2:05:26     
board And so um they talk about theory here and they talk about     
2:05:33     
uh sort of how one can use oscillator networks to compute learn to recognize patterns This subject should appeal to     
2:05:41     
people caught up in the current excitement about neural networks Abbott in 1990 has taken a first step in this     
2:05:49     
direction This is an oldish paper I didn't know how old it was Um the recent     
2:05:54     
observation of stimulus and new synchronization in the visual cortex has spawned several theories involving     
2:06:00     
oscillators though there's still uncertainty about the biological significance of the     
2:06:06     
experimental observations but in any case Norbert Reiner would be pleased to see that     
2:06:12     
we're thinking about oscillators in the brain again so that's that paper um and that's     
2:06:20     
that topic and I think there's this link between winner's work and in in his     
2:06:25     
career some of that was a cybernetics influence and some of it was more sort of a signal processing     
2:06:32     
aspect of his work but you know how these ideas can kind of transform themselves in entire fields of     
2:06:42     
study So if we have any followup or questions on     
2:06:52     
certainly interesting about the EEG Yeah that you     
2:06:58     
It did make me wonder I mean you know as well as some some the the additional comments that     
2:07:06     
they made about Wieners's work Yeah Um or kind of     
2:07:13     
lack of sighting or things like that It's     
2:07:18     
something that came up in the the complexity discussion was um uh I think it was talking     
2:07:27     
about [Music] the talking about     
2:07:34     
uh who was it i I I I forget the the other person but there was just like     
2:07:40     
like we coined you know we we wanted a different word than cybernetics because because we just     
2:07:48     
didn't want to invite we artificial intelligence itself I think right yeah     
2:07:54     
Yeah Yeah And it was they wanted to avoid wiener We wanted to avoid wiener     
2:08:00     
And I I just I wonder you know um     
2:08:07     
um yeah just just uh I'm starting to get this feeling like like he's u he's a     
2:08:15     
little Buckminister Fullerish you know like like     
2:08:22     
u you know he's he's got good idea you know like like he seemed to be everywhere He he     
2:08:30     
um was certainly influential Yeah Um but at the same time like like yeah     
2:08:41     
um yeah I I I I should u I should check if Carl's book Carl     
2:08:48     
Prim's book is uh is uh you know if there's an ebook now that     
2:08:54     
I can like search for terms and things like that like uh I wonder what I wonder     
2:09:00     
if he's got any good wiener stories that we can share Oh yeah because I he was certainly he was certainly invited to a     
2:09:07     
lot of those meetings and like definitely definitely got     
2:09:15     
to got to work with him or I would Yeah Anyway I I'll see if I can find some     
2:09:20     
stories Yeah that's great Yeah I thought you'd     
2:09:25     
be interested in the whole Marine Waves thing but Oh yeah Yeah I mean this is this is I I've got to figure out if that     
2:09:32     
was if that was something he was doing with Carl Yeah Yeah Yeah I don't I don't know I just     
2:09:41     
ran across this paper but I I it looks interesting because I wasn't aware I     
2:09:46     
know that we had done a lot of uh done a number of papers on signal processing and random processes and things like     
2:09:53     
that Um for sure Yeah     
2:09:58     
So I'm not sure about the that figure one I mean like I had mentioned it looks kind of like a wave and I don't know if     
2:10:04     
there if there's a connection between that and I can't see your screen though Oh well I didn't Let me bring it back     
2:10:10     
Okay     
2:10:16     
So uh figure     
2:10:23     
one So this is figure one here Oh yeah yeah yeah No search me Yeah So I mean     
2:10:30     
like I don't know if you think that looks familiar to you or what you had to say about that     
2:10:38     
Um um what's the Sorry I'm seeing this     
2:10:43     
on Oh Oh this is his um interesting I mean it's it's so hard     
2:10:50     
to know because like like certainly given the time like     
2:10:57     
I mean that doesn't make sense um initially right in that um you know     
2:11:06     
what what we think of um as full full spectrum these days you     
2:11:15     
know looks more like a a power law behavior you know So it's high high     
2:11:20     
power low frequency going off going down and then     
2:11:26     
then there's a little there's a little peak out of that at around 10 hertz and     
2:11:33     
then maybe like a smaller one at like 15 Um uh so but at the same time like given     
2:11:42     
the amplifiers and like maybe what you're using as your highp pass filter     
2:11:47     
right um     
2:11:53     
yeah Yeah I mean you know like like like again like that could be because of uh     
2:12:00     
you know like sort of um some artifacts of the     
2:12:06     
the signal analysis that they're doing But like like again like were they even     
2:12:12     
doing signal analysis well this is a schematic all going through electronic I mean like it would     
2:12:19     
have literally been analog circuitry right     
2:12:25     
I mean there's no DSP in this case what I'm saying     
2:12:30     
Uh but that I I'm just not good enough to     
2:12:35     
to know you know that that that um that error is electronics like if that's what     
2:12:42     
uh you know may maybe if that's what he was kind of focusing in on Yeah But it     
2:12:49     
it doesn't it doesn't look natural Okay Yeah So like uh I don't know there's a I     
2:12:57     
don't want to say scientific fraud but kind of thing you would say if like     
2:13:04     
it's like if you could draw your own results Yeah     
2:13:11     
Yeah let's let's give him the benefit of the doubt And he saw something around 10 hertz because like even Burger did in in     
2:13:18     
the you know the late 20s right so it certainly should have been possible     
2:13:25     
right well I think the point of figure one is it's a schematic like this is the typical thing that you would see and you     
2:13:32     
know then to to go on to make theoretical statements about it So it's not like uh it's like the typical thing     
2:13:40     
and of course there's probably a lot of variation there So um yeah I I like how     
2:13:47     
Strogats leads it to like a lot of the synchronization work So like basically that is leading you to this     
2:13:55     
these models of synchronization It's explaining some of the features of synchronization and of course in     
2:14:00     
synchronization work you won't just find like this archetype you'll find like a     
2:14:06     
lot of variation in the behavior and a lot of times in complexity theory we distill that down to like some like a     
2:14:14     
power line or something and we can describe it with that but there's but the actual plot is not you know it's     
2:14:21     
it's not idealized but we assume that that's the theoretical model because we can     
2:14:27     
describe it with a mathematical equation or something like that and so then we     
2:14:32     
also assume that that's universal that you go across different systems     
2:14:38     
Yeah for sure For sure Yeah All right Uh so yeah looks like     
2:14:44     
Jesse had to leave so I think that's all for this week Um thanks for attending     
2:14:49     
See you next week Thank you Thank you Yeah Talk to you See you Monday Yeah See you next week Bye     
