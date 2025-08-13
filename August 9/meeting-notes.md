## Meeting Recording

[YouTube link](https://www.youtube.com/watch?v=rzKwBMf4WY4&)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115003240689765644)

# NOTES
Computational Biologists: can we model natural systems? Abstraction that is computationally efficient.


Turing, 1950. Imitation Game is not relevant to modern work. Not a good definition of thought and consciousness.

thing in a box: thought or computer.

CogSci — NeuroSymbolic approaches, very significant advances such as DreamCoder (2021).

multi-layer perceptions paper that said we could never have a multi-layer model (once viewed as impossible.

LLMs pass the Turing Test — is this relevant for cognition computational neuroscience.


Don’t need the chemical, physical levels. Diverse forms of computation.

diverse forms of computation.

PINNs —> Physics-informed NNs.

biocomputation —> organoid intelligence.


Big discussion in computational psychiatry —> ability of LLMs and ability to engage in therapeutic applications.

degenerate behavior in LLMs.

BICA conference — wide-ranging, interesting conversations.

* biopunk Hackathon — a few projects proposed. 3D printers to bioprinters. “Fresh Bioprinting”.

Vidhi Rohira
Vidhi Rohira says:
yes 2mins 
9:13

Paul Mandal
Paul Mandal says:
Putting a reminder here to search the BICA conference. 
👍
9:15

Morgan Hough (he/him)
Morgan Hough (he/him) says:
Good morning 
9:17

Vidhi Rohira
Vidhi Rohira says:
Good Morning Morgan 
9:18

Paul Mandal
Paul Mandal says:
Is Bradly cutting out for everyone else or is that just me? 
9:46

Vidhi Rohira
Vidhi Rohira says:
yeah, me too.. ig his network bandwith is weak 
9:46

Vidhi Rohira says:
its fine now 
9:46

Paul Mandal
Paul Mandal says:
https://arxiv.org/html/2503.23674v1
 
❤️
10:16

Paul Mandal says:
Dream Coder Paper: 
https://dl.acm.org/doi/10.1145/3453483.3454080
 
❤️
10:18

Vidhi Rohira
Vidhi Rohira says:
BNY uses ELIZA right? 
10:21

Paul Mandal
Paul Mandal says:
Side none: Memristive circuits were one of the main approaches to neuromorphic computing (I'm not sure whether things have changed since I last was reading on that field). 
10:32

Paul Mandal says:
1. A Unifying Approach to Self-Organizing Systems Interacting via Conservation Laws: 
https://arxiv.org/pdf/2507.02575
 
10:37

Paul Mandal says:
2. Beyond dynamics: learning to discover conservation principles - 
https://iopscience.iop.org/article/10.1088/2632-2153/ad4a20/pdf
 
10:39

Paul Mandal says:
3. Hebbian Physics Networks: A Self-Organizing Computational Architecture Based on
Local Physical Laws - 
https://arxiv.org/pdf/2507.00641
 
10:49

Paul Mandal says:
Hopfield Networks were originally conceptualized as a robust way of storing information. Basically, a Hopfield Network has a set of nodes interconnected by edges. If a value of the node is accidentally erased, it can be reconstructed from the value of the edges.

Hopfield methods are trained by minimizing an energy function. There has to be an "unlearning" process so that the edges don't just converge to zero. There's something called the Crick Mitchison hypothesis that basically states that unlearning is related to the reason why we need sleep. 
10:54

Vidhi Rohira
Vidhi Rohira says:
afk 5mins 
11:09

Vidhi Rohira says:
back 
11:12

Vidhi Rohira says:
👍 

# TRANSCRIPT  
0:00    
Hello. Morning. Morning.    
0:08    
Hello VD.    
0:16    
Can't hear your audio. Yeah,    
0:22    
I don't know. Probably have to use the chat. Yeah, there we go. All right.    
0:28    
Yeah, I heard I heard something, but it definitely wasn't a voice. So,    
0:36    
all right. So, uh why don't we get started? So, usually what we do is we start with a updates or set of updates    
0:44    
for the lab. So, um on Monday we had the DBOR meeting was meeting number 26.    
0:53    
Uh we talked about a number of different things in the meeting. We talked about    
0:58    
sort of the evolution of intelligent brains and we had a conversation there.    
1:04    
We also talked about peptide modeling and uh we talked about    
1:10    
uh the origins of Evo DVO. If you go to the YouTube channel for Evoorm, you'll    
1:17    
see the full meeting there. Um and so that that's uh quite interesting.    
1:24    
Then on Wednesday started the uh bea conference and I put in cognition futures I put a    
1:33    
link to the uh YouTube archive and I'll talk about that in a little bit. So BEA    
1:39    
is uh biologically inspired cognitive architectures and it's this meeting that we've been    
1:45    
participating in since about 2021 and uh we have I think this is the so    
1:53    
this is going to be the fifth presentation that I've given there.    
2:00    
Uh we've done a number of different interesting covered a number of    
2:06    
interesting topics that we've been working on. Uh this year and in 2023 we    
2:12    
talked about super performance and then in 2021 and 2022    
2:19    
we did things with the Metabrain platform that we've done research on in the lab. And I can't remember what we    
2:26    
did in 2024. I was trying to remember this morning, but I couldn't come up with it. So,    
2:33    
we have a number of things I think to follow up on at this point. But anyways, I gave the talk    
2:39    
on um Super Performance. Um it was yesterday.    
2:46    
They have their talks on YouTube and it's still going on. It's    
2:51    
supposed to end today. Um and it's a really interesting conference. It's not it's it's kind of    
2:58    
like AI, but it's not the AI that you usually see at run the big corporations.    
3:04    
has a this sort of legacy component where you know it's kind of a mixture of    
3:11    
goi and neuros symbolic models and modern AI platforms like you know people    
3:19    
talk about large language models and transformers but it's these cognitive architectures    
3:25    
which try to approximate cognition um for robots and other things.    
3:31    
So, I'll talk about that in a minute a little bit more depth and and I'll try to put together um kind of a summary    
3:38    
later. I'm not going to do that today because it's it was a couple day, you know, we've been going through it and    
3:44    
digesting it. And then yesterday we had our open source meeting. So, that is where we did    
3:51    
our uh GOC updates. Um and then we also talked about putting    
3:57    
open source projects into production. So, what does it take to put an open source product into production? What are    
4:04    
the opportunities and pitfalls and all of that? So, that's what what we've done this    
4:10    
week. Um, looks like Morgan's here. Hello, Morgan.    
4:16    
So, I'm Vidi Bradley and Morgan already know me. I'm a Google Summer of Core    
4:21    
2025 scholar and I'm working on the sustain hub project right now. So, I'm    
4:26    
using reinforcement learning and getting about the project. Yeah. Okay, pleasure to meet you. I'm actually working on some stuff with uh    
4:34    
training the the C elegance conneto using reinforcement learning. So,    
4:39    
oh that's interesting. All right. So, uh now I want to talk a little bit about Bika 2025. I'm going to    
4:46    
just give a short overview here and then a longer update later. So, this is the website for Bika 2025. Beaai.org org and    
4:55    
then be aai-2025 is the URL. So it's uh they they had this    
5:05    
um actually this is incorrect in terms of the physical location but they had a    
5:11    
physical location and then they have a virtual component. I of course participated in the virtual component.    
5:18    
Okay. So this is the one here. It's it's physically in Porto Varta Mexico.    
5:24    
So they have uh you know people at that physical location most of the people and    
5:29    
then they have people participating online on Zoom and it's a mix of the two    
5:36    
talks uh types of talks um in person and virtual    
5:42    
and so um yeah there are some really interesting    
5:48    
talks. Uh this is Alexi Saminovich and he does a lot of things in what he    
5:57    
calls the Institute for Cyber Intelligence Systems. Um and also works at in the department    
6:04    
of bioengineering at George Mason University. Um and you know usually has some pretty    
6:11    
good talks. Um this one was how to teach beas speak    
6:16    
natural language and understand human mentality. So you know we kind of considered large    
6:23    
language models and how we maybe can you know we can use those but can we still    
6:29    
use symbolic AI and bea is considered an instance of symbolic AI    
6:35    
and it talks about how you can augment large language models with these    
6:41    
symbolic beas or symbolic AI type beas. And so this is um so he says beas are    
6:49    
unique in their potential ability to replicate higher human cognitive functions    
6:55    
personality social emotional intelligence goal reasoning but require intelligent    
7:01    
interfaces and symbol grounding to interact with the real life social environment. And so large language    
7:08    
models can pick up where beas leave off and then beas pick up where    
7:14    
large language models leave off. Uh this was Ricardo Goodwin.    
7:20    
Um he's from Brazil and uh his talk was on the pursuit of    
7:27    
understanding consciousness and cognitive architectures. This is another kind of talk where they considered large    
7:35    
language models and how beas can augment large language models. So this is again    
7:41    
where we have these cognitive architectures which are really you know very large box    
7:48    
and arrows models and you know they do different things that are more symbolic    
7:53    
and large language models and you can combine those.    
7:58    
This is Ron's son. Of course, we know his work. He's done worked in this area    
8:04    
of cognitive architectures for decades. And you know, he's a cognitive    
8:09    
scientist. So, he's approaching us not necessarily as an well, I guess he does do engineering, but also he approaches    
8:16    
it more from a cognitive science perspective. um and this is uh rethinking rationality    
8:23    
and intelligence and AI through cognitive architecture. So this talk examines the literature on    
8:30    
rationality and intelligence and AI systems and delves into a specific    
8:35    
approach the development of a neuros symbolic cognitive architecture. So    
8:40    
we've talked about neuros symbolic architectures before.    
8:45    
Um this is where you have like connectionist models or these neural    
8:51    
network models that have very limited representational capacity.    
8:57    
And then you have symbolic models which are sort of these gi models which model    
9:03    
concepts which have you know work from sort of tables of symbols and things    
9:08    
like that. and then merging those two approaches together. So you have sort of    
9:13    
the best of both worlds in that sense. So I think this one's happening today.    
9:20    
The discussion covers various forms of rationality, different ideas about intelligence, the nature of human    
9:26    
activities, the roles of motivation and so on. And this is all examined through    
9:32    
the lens of the cognitive architecture. So this talk also argues that recent    
9:37    
computational models are more sophisticated than often assumed    
9:42    
and they are well equipped to overcome many of the criticisms leveled against AI. So they improve upon the sort of AI    
9:51    
it's going on right now in ways that sort of address some of the criticisms    
9:57    
of AIS current sort of the contemporary state-of-the-art AIs.    
10:04    
Uh this is Shan Kougllay or Kugel    
10:10    
and um this is um his work focuses on    
10:15    
artificial intelligence, cognitive modeling and neurosyolic systems. The    
10:20    
goal of his research is to understand how natural minds such as human minds work and to implement biologically    
10:28    
inspired software systems based on the same principles. So this is definitely    
10:33    
sort of a maybe a more engineering oriented approach but it does deal with    
10:39    
this idea of mental imagery. So um his talk was beas for science mental imagery    
10:48    
consciousness and the nature of thought and so talking about software agents    
10:53    
based on these kind of beacas can serve as powerful tools for cognitive science.    
10:59    
They offer controllable, inspectable platforms for probing complex psychological questions and testing    
11:06    
alternative theoretical hypotheses. But while the synthetic approach to understanding minds holds tremendous    
11:13    
promise, it also introduces unique methodological challenges. In this talk, I will explore these    
11:19    
opportunities and challenges in the context of my recent attempts to use Aika to investigate mental imagery in    
11:28    
aphantasia. Um, and then just thinking about mental imagery, which is seeing with your    
11:34    
mind's eye or hearing your voice is something that is um    
11:41    
it's kind of hard to model. Actually, it's kind of hard to get at with experiments, but it's also hard to    
11:48    
model with computational models. So, this presents a modeling challenge. How    
11:53    
can we reconcile the differences in affantasics subjective experiences with their    
11:59    
unaffected task performance? And so, fully addressing this question requires modeling both conscious and unconscious    
12:06    
mental representations and processes. And the answer to this question is bearing on several long-standing debates    
12:14    
including the functional import of mental imagery, the nature of internal representations and processes and the    
12:21    
role of consciousness in producing overt behaviors. Um and then there were some other talk    
12:28    
this last talk this these were all the keynotes. So this last talk was by Vasilus    
12:34    
uh Cabarasos and this talk was human friendly    
12:39    
artificial intelligence enabled with a lattice computing paradigm.    
12:44    
And so this kind of talks about conventional deep learning architectures    
12:49    
and then this um alternative architecture    
12:54    
which is what he calls lattice computing. So that's pretty um mathematically    
13:01    
detailed. So, that was uh some of the keynotes. Like I said, I'll go over    
13:09    
some of the talks and things later,    
13:14    
but um    
13:19    
so this is the YouTube channel here. This is um what is it called? The    
13:26    
Senvestavo Facial. It's from the institute that's hosting because usually    
13:32    
it's hosted somewhere at some university. They often host it in Mexico. There's um    
13:40    
a group I guess in Guadalajara that does a lot of work on beas and they host they    
13:46    
hosted this in 2022 I believe as well. So, um they have a their channel. They    
13:51    
have the Beika uh uh sessions and then they have other    
13:57    
content on here which is kind of interesting, but it's in Spanish. So, if you don't understand Spanish, the Bea    
14:03    
sessions are mostly in English. Okay. So, Jesse's not here today, but this would be of interest to Jesse because he    
14:11    
posted a lot about this in the Cog uh Cognition Futures channel, the Slack. uh    
14:16    
I think he attended these meetings but this is another overview of one of these    
14:22    
BI complexity talks um thinking about like sort of following    
14:27    
up on some of the topics that they talked about in the session and kind of giving our own opinions about it.    
14:37    
So this is let's see um    
14:45    
so the BI complexity group is this discussion group they meet online uh I    
14:51    
think bi-weekly and they always cover a paper so they've covered papers from the history of cybernetics the history of    
14:58    
computing and what I understand they're kind of building this sort of body of    
15:05    
knowledge and trying to bring together people interested in these topics and trying to sort of bring insight out of    
15:13    
them from a modern perspective. So we've talked about the cybernetics    
15:18    
paper. We talked about the the Warren Weaver paper. It was last week or the    
15:23    
week before. This one is the uh a paper by Alan Turing and this is computing    
15:30    
machinery and intelligence. We're going to be talking about or they talked about this paper. We're going to be    
15:36    
referencing this paper and it's it's a paper that was published in the journal mind in 1950. So we have now 75 years of    
15:46    
insight into this work. So everything he talks about in this work is sort of 75    
15:53    
years old. And so we have answers to some of these things. We have perspective on these things. But can we    
15:59    
bring that to bear, you know, uh from what we know now? So,    
16:06    
um, this is one image that they talked about. This was actually from the    
16:12    
discussion group. Um, so Jesse posted a bunch of slides in the Slack and he    
16:19    
didn't really annotate them, but these are things that they talked about. So they, this is uh, I think science    
16:27    
post 1950. They've divided it into three things. There's nature which is N and that's    
16:36    
natural processes and phenomena. There's the simulant which is an    
16:42    
abstract formal symbolic model of physics properties of n or t subn and    
16:48    
this is materially computed. So for example nature something that happens in    
16:54    
the world you can simulate nature in a computer. you can use uh a a circuit or    
17:02    
an electrical circuit and that's kind of how we've approached    
17:08    
computation post 1950. So we can take a natural system we can simulate it on a    
17:15    
vonoyman architecture um you know we have other architectures but that's the one that we've kind of    
17:22    
developed the most over that period of time. So we can simulate nature but we    
17:28    
can also replicate nature. And so this is whereas a simuent is the or the    
17:33    
abstract formal symbolic model of physical properties. A replicant is an abstract material    
17:41    
model that retains the essential natural physics of n. So this is not computation    
17:48    
necessarily. This is where you can build a model a material model that simulates end. So    
17:55    
you can have um you know you could have of course a physical model like I could have a    
18:01    
physical model of a horse and it could have a flowing mane and the man could be    
18:08    
very lifelike and the horse could you know make noises and move. And so those    
18:15    
are all things that are replicants because they're not really uh the natural phenomenon but they try    
18:22    
to model it as closely as possible. And so there are these three divisions    
18:28    
of science. We use replicants simulants and we do that to study nature.    
18:37    
So this is the uh invitation. So this is they cover this turning paper from 1950.    
18:45    
Um that's their Zoom link. Um and so this is a comment from Kevin    
18:52    
Mitchell which was I guess in the chat and Jesse took a picture of it here. The    
18:59    
question is whether computational functionalism actually holds or not. It's an assumption that thought equals    
19:06    
computation. So what this refers to is this discussion we've been having over    
19:12    
probably several years now in the group which is that um when we talk about    
19:18    
computation you know is computation sort of analogous to something in    
19:24    
biology or is it analogous to thought or is it something else? And if we think    
19:31    
about simulating a natural process, can we use computation to model that    
19:37    
process? Do we capture the full process? And a more radical view of that is is    
19:44    
that natural process computation. So if we go to say like a forest fire or    
19:51    
a brain or you know something like that is that is there a computational    
19:57    
structure there that we could replicate say on a bonoyment architecture or some    
20:03    
other place and have a onetoone correspondence between the two.    
20:09    
And so this you know we we talked about things like natural computation    
20:15    
and then of course um Church Turing had something to say about that. Church    
20:21    
turning Deutsch which were two thesis advanced that kind of argue that you    
20:27    
know there is an equivalent computational system for any natural system    
20:33    
and so you know but this is still an open question. Is computational functionalism    
20:40    
suitable for every type of system in the world? And that has implications for when we study systems in nature. Can we    
20:49    
really kind of accurately simulate them? Can we simulate every possible state    
20:55    
that they're in or is this just kind of an exercise and approximation    
21:00    
and it's not really that um you know we should just take it with a    
21:06    
grain of salt. Okay, Paul,    
21:12    
sorry to interrupt you. Um the the church terrain hypothesis specifically    
21:18    
had to deal with uh computation on natur uh natural numbers as opposed to uh    
21:25    
natural simulations. And I just wanted to thank you.    
21:30    
This is like kind of leading from some of the stuff we've talked about in the past. But yeah,    
21:36    
I I think sometimes computational biologists can you guys sometimes really    
21:43    
focus on simulating everything. The question is well if we can simulate anything then then can we get a model of    
21:49    
of computation that or cognition that works and you know I believe the answer to that be yes but the difficulty often    
21:56    
comes from making a an abstraction that is that is adequate enough to to still    
22:03    
suit our purposes but is also computationally efficient. Yeah.    
22:10    
Yeah.    
22:17    
So yeah and um a lot of people in the sciences you know    
22:24    
they kind of also have this other view that uh you know we can't really build    
22:30    
computational systems that fully capture a lot of say like biology and that's    
22:36    
like another view that like um and I think it's it's fair because    
22:42    
you know, we kind of assume I think a lot of people assume that we can just    
22:47    
kind of make this easy correspondence and you know    
22:54    
okay so um all right that's that and then this is    
23:00    
so this is a timeline AI and complexity this is um sort of from 1950s so the    
23:09    
church turning thesis was back in the 30s uh GP computer was in the middle of the    
23:15    
40s and then from 1950 on this is the trying 1950 paper.    
23:21    
This is artificial intelligence GP computer and then natural complexity    
23:27    
physics gone which uh go from 1950. I'm not really sure what all this means. I    
23:33    
wasn't at the talk but that's their timeline. This is a general purpose of GP. It's a    
23:40    
general purpose computer um and just showing that kind of what    
23:47    
people are thinking about. So the speakers in this um session were    
23:54    
uh Dr. Colin Hills and Peter Kitner and they were talking about this they were    
24:02    
kind of over giving this overview of the touring paper at the meeting here.    
24:09    
And so this is this figure that we saw science pre-1950. Um and this kind of uh so this kind of    
24:18    
goes through a little bit more of this. So again we talked about nature simulant or emulant and then replicant and then    
24:26    
nature of course is occurs naturally without human intervention. And so in N    
24:32    
or nature this equ you know if we look at combustion it involves burning.    
24:39    
Um in in the simulant or emulant of course we're trying to build an abstract formal symbolic model of physics    
24:46    
properties. Um we have this t subn which is manually computed by a human computer and then t    
24:54    
subn is materially computed by a circuit or electrical model. And so    
25:02    
uh n is not art or we don't we don't have artificial nature.    
25:08    
Uh we then have abstract symbolic chemistry of combustion which is not burning. So we have this abstract    
25:14    
symbolic chemistry and therefore we don't have an artificial um aspect. We don't have this artificial    
25:22    
nature. We have something that approximates it. Um and then but then    
25:27    
the replicant we of course have a material model and then artificial N    
25:33    
would not occur were it not for human intervention. So we have burning but we also have this    
25:40    
artificial system that can simulate nature.    
25:46    
So this was the screenshot of the no face palms this week. Um this is the    
25:51    
screenshot of the session. Um and and so they let's look at what    
25:57    
what was going on in the chat when they were talking about this. Paul Middlebrooks who read weeds these talks    
26:02    
had some sort of figure. It looks interesting, but I can't zoom in enough to see what it is.    
26:09    
Let me see if I can get to it. Um yeah, I can't see what it is. But that's    
26:16    
um in any case um uh this person here    
26:22    
said what is natural complexity physics and then um this says okay so basically    
26:29    
getting past the fluff of biomplexity to algorithms symbolic computation based on    
26:35    
simple ingredients and see how far we go from there and then Jesse said she does so this    
26:44    
fits real Well, with cognitive science as a computationally centered medium to center all manner of what a mind is    
26:50    
doing. Okay, so that's um that's that slide. Um    
26:58    
this slide talks about distorted science the legacy of Turing 1950.    
27:05    
So this is again considering nature considering the simulant and then    
27:11    
considering the replicant and this is kind of talking this is uh    
27:17    
Colin's take on it Colin Hill's take on it. Uh so we have nature which is the brain. N equals the brain. The simulant    
27:26    
which is AI it's non artificial brain.    
27:31    
All N physics gone. So the physics of the brain are not in the simulant.    
27:36    
And then that means that there has never been a T subvent simulant that can become nature N.    
27:43    
And then there's the replicant which does not exist. We don't have an    
27:49    
artificial brain that compares with like say what we've done with simulating    
27:56    
uh brain-like processes and then the essential in physics are retained. So the replicant again is this    
28:04    
physical model where we could physically emulate say the brain or or replicate    
28:09    
the brain. It wouldn't necessarily have all the properties of the brain. It would be some sort of abstraction. it    
28:15    
would indeed be an artificial brain. Um, and they say replicant does not exist,    
28:20    
but we've been talking about organoids uh for a while and they're not really,    
28:26    
of course, replicants of the brain, but a lot of the um    
28:33    
a lot of the neural organoids, you know, they do replicate parts of the brain, they do replicate features of the brain.    
28:39    
So, organoids might be considered a replicant. And so you retain the essential physics    
28:45    
in um in a neuralorganoid. It's an artificial brain, but it isn't the brain    
28:51    
itself. It just has these properties. Has the physical properties of the brain. And it but it's not a simulant    
28:58    
where you're simulating things that are going on in the brain. But the simulation doesn't have physics. It's    
29:05    
not an artificial brain and it can't become nature itself. That's kind of the    
29:10    
idea. And then Colin notes there is a major category error in the use of material    
29:17    
simulants that has misled the science namely prediction of voltage by    
29:22    
neuromorphic electrical equivalent circuit models does not contact the    
29:27    
physics that creates the voltage and drains. EM fields do that. So    
29:33    
electromagnetic fields. So this is again, you know, kind of hashing out    
29:39    
these differences between say like taking the brain, simulating the brain    
29:44    
and then replicating the brain and how we might use that in scientific inquiry.    
29:52    
This is getting deep into like kind of philosophy of science and things like    
29:57    
that. And we'll get into the paper. It'll maybe kind of highlight some of these things that are going on there. Um    
30:06    
so they they had this in the comments here uh they were talking about material    
30:12    
replicants and some of the sort of philosophical    
30:17    
consequences of that and then um Mohammad Ansari here says is that what    
30:24    
Sirill was arguing with his Chinese room problem that we're not modeling the physics of intelligence but only    
30:30    
simulating its syntax with UTM. am. Then this is a picture of the I think of the    
30:37    
uh this is opening Turing's black box    
30:42    
and this is sort of a picture of the Chinese room and this is of course a thought experiment in cognitive science    
30:49    
where you take someone takes a slip of paper and they put it into a box. Maybe    
30:54    
the the slip of paper has a question or it has like a phrase on it and then    
31:00    
it gets slipped into the box and then they get an answer out of the box which is an answer to the question or maybe    
31:07    
it's a translation into another language. And the question is in this black box,    
31:13    
you know, does this process, you know, is there like say a little    
31:19    
person in there that's doing the translation or is it just done at random    
31:24    
and it happens to get the right answer? And so that's the the sort of the Chinese problem. You could update it for    
31:31    
sort of thinking more broadly about understanding and technological systems.    
31:37    
We had a thing in the chat here. Oh, yeah. I'm probably just Okay. I    
31:43    
don't know. Yeah, I might be cutting out a bit, but but okay.    
31:49    
Yeah, I might be having a little bit of a difficulty with the the instance here.    
31:57    
Yeah, I can I can hear you fine now. You're cutting in and out. All right.    
32:04    
And then this uh Sean Manion says, "Worth noting that 1950 to 1956    
32:11    
included several Macy meetings, ratio club meetings where Turing first presented this paper in December 1950    
32:19    
and the Shannon McCarthy edited automous studies among other lesserk known events    
32:25    
relating to these areas. So this was all part of at the same time they're talking    
32:30    
about general purpose computers and um simulants and replicants. They're    
32:37    
also talking about cybernetics and the legacy of cybernetics and how    
32:42    
cybernetics kind of thinks about the brain and thinks about modeling.    
32:48    
Okay. So that we talked about the Macy meetings, we talked about ratio club.    
32:54    
The ratio club of course is where they met. This is a I think a club in in    
32:59    
London where a lot of uh people met to talk about sort of the new era of    
33:05    
computing when they came up with cybernetics as a means to sort of view the world    
33:12    
through this computational lens or through this sort of mathematical lens.    
33:17    
And there were a lot of ideas in cybernetics that well some of them were    
33:23    
flushed out um not all of them were fleshed out. And so they ended up um you    
33:30    
know kind of being halfdeveloped and then people kind of forgot about cybernetics. And so we actually have a    
33:37    
group in the lab that we were kind of revisiting those issues and thinking about them in a modern way. Of course,    
33:45    
the Macy meetings were these more formal meetings where they thought about cybernetics and they brought people from    
33:51    
a wider set of disciplines to kind of consider how cybernetics could be    
33:57    
applied to their field. And again, this is another thing that never really    
34:02    
uh gelled into a robust field, but still has a lot of things to teach us about,    
34:08    
you know, how to think about these kinds of problems. Um okay so why don't we get into the    
34:15    
paper um actually let we talk about this first.    
34:21    
So this is um sort of the followup from this meeting this week. So um this week I got a uh an    
34:31    
email from the email list and it's in the last discussion how introduced his    
34:36    
thoughts and how touring led to a historically backwards way of trying to    
34:41    
understand slashexplain things. And so um what they're going to do this week is    
34:49    
talk about sort of a more detailed set of principles. And so that's kind of a a    
34:57    
thing for this coming week. So I don't know what they're going to talk about this week necessarily, but sometimes these discussions go off in different    
35:03    
directions. Um, so Jesse posted this in the Slack and I don't know what necessarily the    
35:10    
context of this was, but this kind of is something he found interesting. So    
35:18    
um, I incur and I hear you. This must have been some discussion in the in the    
35:23    
session. There's an uh there's an interesting set of meetings called the    
35:29    
Macy meetings that took place of the cyberneticists in the US. Warren McCulla    
35:35    
was kind of the chair of all of those. So this is for McCulla Pittz. Um and he    
35:41    
wrote a letter and I posted in the chat earlier like a list of that he wrote a    
35:46    
letter to everyone who's coming to the 10th and last one. So this is the 10th and last Mac meeting basically saying we    
35:54    
failed and saying and you know what it means in our own eyes we stand convicted    
36:01    
of gross ignorance and worse theoretical incompetence. This is of course um the    
36:07    
chair of the Macy meetings and this is referring to the LA the final Macy meeting. I don't know the year for that    
36:14    
though was the 10th Macy meeting so it was probably in the late 50s early 60s.    
36:19    
Um and so but basically when you have your meeting and they send out an email    
36:27    
or at the time I guess a letter um saying you failed and you don't know    
36:32    
understand what you're doing and we're pretty incompetent.    
36:37    
That's not a good sign. But I don't you know I don't know maybe that was just kind of built out of frustration.    
36:45    
Um, but anyways, that's kind of where these Macy meetings ended. And maybe    
36:50    
that's what it is. Maybe it is a lot of frustration. Maybe the problems were too hard and intractable. And of course,    
36:57    
remember, they were thinking about computation and they were thinking about modeling, but they didn't have the tools    
37:04    
of the modern era. So, it's like they were trying maybe they were ahead of their time.    
37:09    
And this is the last of probably one of the most innovative interdisciplinary meetings ever. So it was a pretty    
37:15    
interdisciplinary set of meetings. They talked about a lot of things but again they left a lot of things hanging out    
37:21    
there. And then of course you know Dartmouth narrowed the aperture to just engineering deliberately    
37:28    
because McCarthy hated the cybernetic stuff. McCarthy is John McCarthy who was    
37:34    
an AI researcher and um they basically um this is something that happened in    
37:41    
the sort of in the history of cybernetics. kind of the reason why maybe cybernetics got left in the dust    
37:48    
was is that you had there were a lot of times when you have interdicciplinary groups there's this initial interest in    
37:54    
being interdisciplinary but oftentimes people will or personalities    
38:00    
will prevail or intervene may have their own perspective on things and they take it in a certain direction and then when    
38:07    
you take a a multid-disciplinary group in a certain direction you fail because    
38:14    
you're sort of abandoning your your original goals. So, it's interesting    
38:21    
that they Dartmouth is was the host of a lot of these meetings and they just    
38:26    
basically turned this into an engineering only thing and this is where    
38:33    
you know again they had people from all over social sciences, natural sciences    
38:38    
etc. And this is where things kind of just collapse down into engineering.    
38:46    
And we've we've pursued that one way and computing power has made it possible to    
38:52    
do amazing things even though we went oh only symbolic works. So this is    
38:59    
interesting because at the time they maybe considered    
39:04    
some of the data driven approaches and because maybe the state of the technology    
39:09    
or something they they considered symbolic models to be superior or the    
39:15    
only thing that would work. And so that's interesting because today we don't think about just purely symbolic    
39:22    
models. We think about data driven models and we want to train our models with more and more data and you know we    
39:29    
kind of pay lip service to neurosymbolic models but the symbolic aspect maybe is    
39:35    
is viewed as a failure. uh and so this is maybe what they're    
39:41    
lamenting which is symbolic models are not the way to go and you know this of    
39:48    
course corresponds with the AI summers and winters. So of course we had these AI summers where there was a lot of um    
39:57    
extraordinary enthusiasm around a different AI models that came about. So    
40:03    
we had a AI somewhere around symbolic models. We had an AI somewhere around    
40:08    
parway connectionist models. And then as those models the shortcomings were were    
40:13    
sort of discovered. We had these AI winters which followed which was where    
40:18    
people overcorrected and abandoned those models and funding dried up and then    
40:24    
people would try something new later which would they do another summer and then another winter. And so we've talked    
40:30    
about AI summers and winters as this sort of um you know fluctuating    
40:38    
aspect of the field and so again this is where they kind of maybe overpromised in    
40:45    
terms of symbolic models and it wasn't delivered and then it says and then await only    
40:52    
connections stuff which means they also you know I guess what they're saying    
40:58    
here is that there maybe it was a camp of people that wanted to use symbolic    
41:03    
models and were arguing that those were the way to go and you can't necessarily    
41:08    
use any other way and there were also people who were early connectionists who    
41:13    
wanted to go in that direction. So it happens a lot of times in interdisciplinary groups where there's    
41:20    
two separate competing camps and it becomes untenable to satisfy them both    
41:28    
and indeed now no one wants to bring those two pieces together.    
41:33    
And so now you know there are people doing neuros symbolic work but then the question is what is the the good the    
41:40    
best balance of both of those types of models. So we've fractured the engineering into    
41:47    
connectionist and neurosymbolic. We've forgotten all the expert system stuff that was done in Japan before their    
41:53    
economy collapsed in the 1980s. This is I think Paul Middleworks talking about    
42:00    
the modern perspective. The Japanese were doing some excellent    
42:05    
work or I guess they still do on neurosyolic um and expert systems work. So they were    
42:12    
doing like neuro fuzzy and some other things back in the 80s. Um and this is    
42:19    
of course where they were doing these amazing things with robots back then as well. But like you know this is again    
42:28    
there all sorts of different um kind of research directions that pursued by um    
42:37    
you know and then kind of left on the floor. So these things haven't even been    
42:43    
integrated into the engineering much less the cognitive science integration much less the neuroscience integration    
42:50    
the psychology integration the mathematics and philosophy don't rely at all. So you know a lot of the things    
42:56    
like what the Japanese were doing with say like fuzzy systems and neuro fuzzy    
43:02    
and things like that that was purely an engineering kind of approach.    
43:08    
um they you know kind of use those in as applications but then thinking about the    
43:13    
cognitive science aspect the neuroscience aspect and these other fields this is where a lot of the work    
43:20    
that we've done with in fact a lot of the work that's been done with AI since the ratio club stopped or the you know    
43:27    
the u Macy conference has stopped is you know there's a lack this sort of    
43:34    
integration into other fields at least in a formal away.    
43:40    
We've broken into a thousand little pieces and we don't yet have a way to bring them all together. We need a    
43:47    
vendor style, you know, bring them together and put them in the glove. I think at some point, but I totally agree    
43:54    
with that. We've been looking at tiny little pieces all over the place, more and more minuscule over the last 75    
44:01    
years because we don't have any theoretical way of putting them together.    
44:06    
So this is sort of a lament about like kind of the state of how we think about    
44:12    
these technical problems and then how we bring them to other fields and there is    
44:18    
a symbiosis there which is missing when you're missing that big interdisciplinary cast of things. So    
44:26    
it's I guess it's um something that came up during the meeting. Um so let's go to    
44:33    
the paper then. This is um computing machinery and intelligence from 1950.    
44:40    
And um so this is the first part here. I guess he writes it in these parts. Um    
44:47    
the first is the imitation game. And so this is I propose to consider the    
44:52    
question can machines think? They should begin with definitions of the meaning of the terms machine and think. The    
45:01    
definitions might be framed so as to reflect so far as possible the normal use of the words, but this attitude is    
45:08    
dangerous. If the meaning of the words machine and think are to be found by examining how they are commonly used, it    
45:15    
is difficult to escape the conclusion that the meaning and the answer to the question, can machines think, is to be    
45:21    
sought in a statistical survey such as a Gallup poll. That this is absurd.    
45:27    
Instead of attempting such a definition, I shall replace the question by another    
45:32    
which is closely related. The new form of the problem can be described in terms of a game which we call the imitation    
45:40    
game. It is played with three people, a man A, a woman B, and an interrogator C.    
45:50    
Um, the interrogator stays in a room apart from the other two. Um the object    
45:57    
of the game for the interrogator is to determine which of the other two is the man and which is the woman. It's just    
46:03    
basically like asking questions of each trying to deduce their identity and then    
46:09    
you know not having that information in advance. So the interrogator knows them by labels    
46:16    
X and Y. And at the end of the game they say either X is A or Y is B. So you get    
46:23    
these two agents who don't know their true identity. You ask them questions    
46:28    
and then at the end of this game you try to ascribe the correct label. So this    
46:34    
sounds a lot like um maybe supervised learning that we would do today where we    
46:40    
have this information and then we try to sort of uh well I guess maybe    
46:46    
semi-supervised learning because you have this information and then you try to assign labels with some degree of    
46:53    
confidence. And so this kind of goes over the imitation game. And then number two is    
47:00    
critique of the new problem. So as well as asking what is the answer to this new form of the question one may    
47:08    
ask is this new question worthy when to investigate it. This latter question we    
47:14    
investigate without further ado thereby cutting short an infinite regress. Um    
47:19    
this new problem the new problem has the advantage of drawing a fairly sharp line between the physical and intellectual    
47:26    
capacities. No engineer or chemist claims to be able to produce a material which is    
47:32    
indistinguishable from human skin. So this is where they're getting into this um rep this replicant aspect. We talked    
47:40    
about the simulant and the replicant. So this is where they're kind of getting at this um this distinction. It is possible    
47:49    
that at some time this might be done. But even supposing the invention    
47:54    
were available, we should feel there's little point in trying to make a thinking machine more human by dressing    
47:59    
it up in such artificial flesh. So he's making this point that you could make    
48:06    
like if you wanted to simulate the brain, you could build a physical model of the brain. You could have the    
48:12    
physical properties of the brain but that doesn't make it any more of a thinking machine and you know so you    
48:20    
don't necessarily maybe need that the form in which we have set the    
48:26    
problem reflects the fact and the condition which prevents the interrogator from seeing or touching the    
48:32    
other competitors or hearing their voices. So basically we don't need uh    
48:38    
the replicant to make a correct determination of their label or their    
48:43    
identity. We just need the information and that's all that matters in. So we    
48:48    
can use a simulant to do the same thing. Some other advantages of the pro    
48:55    
craritarian may show up by specimen questions or answers. So again, you you give this do this question answering and    
49:03    
you're getting the information that you need and you can basically accomplish the task without building a physical    
49:10    
model. This may seem a little silly and trivial today, but if you think about,    
49:16    
you know, how people approached this before 1950, you know, they didn't have    
49:22    
the, you know, people didn't have the frame of reference of a digital computer like we do today. It was like people    
49:28    
would build automaton and they would, you know, have all sorts of different ways of kind of simulating living    
49:35    
systems. So what I mean by automaton are these little um physical models. you    
49:41    
know, you'd have little robots that would you wind them up and they'd walk and you know, they were physical    
49:47    
instantiations of something or you'd have like, you know, if you remember    
49:53    
from the movie Big Zar, which was this, you know, uh thing it was a model of    
50:00    
like um this uh person who would give out    
50:07    
answers to questions. It's a mechanical system. that would stamp out these answers to questions and it was um you    
50:15    
know so this was kind of the frame of reference people had before 1950.    
50:20    
So that was kind of I think that maybe kind of the context here. Um the question and answer method seems    
50:28    
to be suitable for introducing almost any one of the fields of human endeavor that we wish to include. We do not wish    
50:35    
to penalize the machine for its inability to shine a beauty competitions, nor to penalize a man for    
50:40    
losing in a race against an airplane. The conditions of our game make these disabilities irrelevant.    
50:48    
The witness can brag if they consider it advisable as much as they please about their charms, strength, or heroism. But    
50:55    
the interrogator cannot demand practical demonstrations. So all the interrogator    
51:00    
has to work with instead of some practical demonstration is just these questions and they have no    
51:07    
connection to any physical attributes like voice or    
51:12    
you know anything else. It's just kind of the answers to the questions    
51:18    
the game may perhaps be criticized on the grounds that the odds are way too heavily against the machine. So the    
51:24    
machine gets information but doesn't get all the nonverbal information that we usually get in a conversation. It gets    
51:31    
just the information as natural language. And of course you could also do this with    
51:39    
say binary or some other something else that would just give the    
51:44    
information. It would be compressed in a way that you know you could distinguish    
51:50    
between different answers to different questions and then make you know uh make    
51:55    
the proper label. Um    
52:01    
may not machines carry out something which ought to be described as thinking or which is very different from what a    
52:06    
man does. This objection is a very strong one. But at least we can say if nevertheless a machine can be    
52:13    
constructed to play the imitation game satisfactorily, we need not be troubled by this    
52:18    
objection. So that's uh kind of the    
52:23    
frame of what this imitation game what it means and then talking about the machines    
52:30    
concerned in the game. The question uh will not quite be definite until we have    
52:36    
specified what we mean by the word machine. It is natural that we should wish to    
52:41    
permit every kind of engineering technique to be used in our machines. We would also wish to allow the possibility    
52:48    
that an engineer or team of engineers may construct a machine which works but    
52:54    
it is manner of operation cannot be satisfactorily described by its constructors because they have applied a    
53:00    
method which is largely experimental. Finally, we wish to exclude from the    
53:06    
machines men born in the usual men. It is difficult to frame the definition so    
53:11    
as to satisfy these three conditions. So    
53:16    
we have uh let's see the three conditions are where we want to have every kind of    
53:22    
engineering technique to be used. uh we want to be able to construct a    
53:28    
machine where the manner of operation cannot be satisfactorily described by its constructors.    
53:35    
So we don't know how it was you know how it necessarily how it works. We want to    
53:41    
try every type of technique that we can and then we want to exclude from machines people. So we don't want people    
53:48    
behind the scenes. So if we go back to the Chinese room, we want a machine that    
53:54    
isn't aided by humans that works by a variety of mechanisms    
54:00    
and something that we can't necessarily interpret or it is not interpret.    
54:06    
It is difficult to frame the definition so as to satisfy these three conditions. So we can't really    
54:12    
do this in real life. One might for instance insist that the team of engineers should be all about sex but    
54:19    
this would not really be satisfactory or is probably possible.    
54:25    
Yeah, this is not um to do this. So it would be a feat of biological technique. Okay.    
54:32    
Um Okay. So let's see.    
54:42    
Okay. So that's a little bit about you know the machines that we're using how we can think about building these    
54:48    
machines. Um we want to construct a thinking machine but we need to cons sort of consider    
54:55    
these different ways of constructing the machine. Um,    
55:00    
we are the most ready to do so in view of the fact the present interest in thinking machines has been aroused by a    
55:06    
particular kind of machine usually called usually called an electronic computer or digital computer. Following    
55:13    
this suggestion, we only permit digital computers to take part in our game. So what he's saying here is that we have    
55:19    
these different constraints for building a machine for this game, but we're only    
55:25    
kind of using digital computers. We could use things beyond digital computers but this is not um you know we we can    
55:33    
think outside of this box. Um, and then he talks about gets into    
55:39    
digital computers and what those are, sort of the basic components that you have in a digital computer and how    
55:46    
information is processed and then walking through    
55:53    
um some more technical details and some objections to this approach.    
56:01    
So that's the paper. Um, so that was their meeting and and I guess they're going they went through the history of    
56:07    
it and they're going to talk a lot more this week, but I want to go through that because Jesse was very excited about it    
56:13    
in Slack and I don't know if he's not here today, but    
56:19    
yeah, so that's a historical note about thinking machines and about the    
56:25    
different types of computation and things like that.    
56:31    
any comments or questions? I uh unfortunately for you have a have a    
56:37    
ton of comments and I might incite your eye.    
56:42    
Okay. Um I'm going to start with the with the 1950 touring paper which I mean it's    
56:49    
probably one of his most popular papers. Yeah. Uh probably because it's the most    
56:55    
accessible to lay men. It was published in 1950 towards the end of of the career. It was uh it was uh published in    
57:03    
a uh I think in a philosophical or psychological journal or something along    
57:09    
those lines. Yeah. Um however, I I don't think that the the    
57:14    
imitation game that Alan Turing proposes is is quite relevant uh to uh our work.    
57:23    
So, so his his main argument was um we do not have a good definition    
57:32    
for for two things. One is one is thought uh the other is consciousness.    
57:39    
So he proposes this test and essentially the test is okay can can some outside    
57:45    
observer you know they they write things on a piece of paper they put it into a    
57:51    
box and uh the box spits out a um an    
57:56    
answer. Can they discern uh whether this the thing in the box is a is is a human    
58:02    
or a computer? Can they tell the difference? But the whole the the whole    
58:07    
thing about thought or or cognition having no set definition. These are    
58:16    
these are actually very important things to to what we are    
58:21    
trying to do in cognitive science. Turing as an engineer throws that out. And I have a lot of respect for Turing's    
58:28    
other work like the the Turing machine paper is great. This is probably my my    
58:33    
my least favorite one of his papers. Um, I want to jump from this to the Slack    
58:39    
message that Jesse wrote. It's very pessimistic. Uh, and I will admit that I    
58:45    
do not have the the best knowledge uh of the history of cybernetic um systems.    
58:52    
However, I can speak to neuro symbolic computing because it is something that I    
58:58    
follow. It is something that I've been doing uh research in although no no    
59:03    
publications uh on it yet but there have been very very significant um advances    
59:12    
in neurosyolic computing. One of them was uh was dream coder where essentially    
59:19    
the the initial challenge is to use um    
59:25    
is is to essentially create a program that can solve uh uh or create an AI    
59:31    
that can solve problems through generating programs. What dream coder is able to do is it's also able to uh dream    
59:39    
up problems and then create solutions to those problems. and that was published back in 2021. It was a pretty    
59:46    
significant uh paper in neurosyolic competing. So it's it's the natural    
59:53    
course of research for um certain fields to sort of be dropped to the wayside.    
1:00:00    
That was the case with AI. You mentioned the AI winters. uh one of the reasons why it was dropped to the wayside was    
1:00:06    
because there is this paper published and basically it said that we would    
1:00:11    
never be able to have uh multi-layered perceptrons which as the perceptron was    
1:00:17    
formulated that was that was true because uh the perceptron had like    
1:00:22    
literally a digital activation function. So there was no way to uh take a    
1:00:27    
derivative of that. Um but that paper saying that uh creating    
1:00:34    
a stacking perceptrons on top of each other was impossible effectively killed    
1:00:39    
AI research. And Jeffrey Hinton who won the Nobel Prize for physics for research    
1:00:44    
related to AI that's a whole separate discussion like should won the the Nobel    
1:00:50    
Prize in physics. Not going to get into that. But he actually had an argument with somebody I think in the in the 70s    
1:00:57    
or 80s and they were arguing that what he was trying to do was was impossible. Like by changing the activation function    
1:01:04    
we we like that essentially gave a rebirth to to machine learning and deep    
1:01:11    
learning in the 80s and 90s and here we are today. Um going back to the touring    
1:01:18    
paper, there is a there is an arch of paper that was uh posted    
1:01:23    
um uh on on March 2025. I'm going to uh put    
1:01:29    
that in the chat. Um and it deals with the touring paper and and the title is    
1:01:34    
literally large language models pass the touring test. um meaning that LLM and    
1:01:41    
and it shows basically I think chat GPT 4.5 or something and I've been 4 o mini    
1:01:47    
uh can can trick uh a user about 75% of the time in thinking that it's a human.    
1:01:54    
Um here's the question I have for the people in this group. Is that particular    
1:02:01    
particularly relevant for us? And I'm throwing myself in this category even    
1:02:07    
though I'm a I'm an AI researcher, not like a a computational neuroscientist,    
1:02:12    
but as a computational neuroscientist, is that particularly useful to us? Not    
1:02:19    
really, because it's investigating a a different problem than we are trying to solve. We're trying to create a    
1:02:26    
computational basis uh for cognition. Um, so I'm ve I I'm sorry for ranting so    
1:02:34    
long. which is something that uh I I'm I'm very passionate about. We don't necessarily have to    
1:02:41    
build like a a model from the ground up because the question is okay where do we start? We we don't necessarily have to    
1:02:48    
start at like the chemical level or the physical level or or even modeling you know quirks but we we are trying to    
1:02:57    
model cognition to to a certain point. So it is actually very important for us    
1:03:03    
to sort of define consciousness and define thought and and think about what what    
1:03:09    
our our objectives and and goals are. So I will I will end my rant there and    
1:03:15    
apologize deeply to the group. Oh no, this is great. Thank you.    
1:03:21    
Um yeah, I mean I agree with um a lot of like what you said in terms of    
1:03:29    
you know the I mean this uh the paper that they covered here was uh thank you    
1:03:35    
for the dream coder paper. Yeah. Um that yeah this wasn't Turing's most    
1:03:41    
insightful paper. Um, and you know, a lot of the aspects of the AI summers and    
1:03:48    
winters, I think part of that was because people kind of had    
1:03:54    
um I like to to kind of describe as like hype cycles in in business and    
1:03:59    
innovation where like people get their hands on something and they try things and there's a lot of sort of excitement    
1:04:06    
around it and then they can't figure out, you know, how like they they get    
1:04:12    
some of the technical details down and then they don't get all the technical details down and they consider something    
1:04:18    
to be a failure. So they kind of put it by the wayside and then of course as you said with multi-layer perceptrons that    
1:04:25    
actually was a solvable problem with later innovation with later research. So    
1:04:32    
it actually um but yeah this is uh and then in terms    
1:04:37    
of like thinking about um    
1:04:43    
uh like this is the paper large language models pass the touring test. This is an    
1:04:48    
interesting paper. So this is where value they evaluated four systems Eliza    
1:04:55    
GPT 4.0 or 40, llama 3.1 and GPT 4.5    
1:05:01    
and two randomized controlled and registered touring tests on independent populations.    
1:05:07    
Participants had five minute conversations simultaneously with another human participant in one of    
1:05:14    
those systems before judging which partner they thought was human. So they talked to a human, they talked to a    
1:05:21    
language model, and then they had to make that distinction. When prompted to adopt a human-like    
1:05:28    
persona, GPT4.5 was judged to be human 73% of the time, significantly more    
1:05:35    
often than interrogators selected the real human participant. So this is where    
1:05:41    
they, you know, there's this distinction to be made. And you know, it's interesting to note like how people were    
1:05:48    
making that distinction. I mean, it may have been not always in the same way,    
1:05:54    
but nevertheless, they were able, you know, they basically    
1:05:59    
couldn't make that proper judgment category. Um,    
1:06:05    
you know, uh, Llama 3.1 with the same prompt was judged to be human 56% of the    
1:06:11    
time. Um while baseline models of ISAN GPT40    
1:06:16    
achieved win rates significantly below chance 23 and 21% respectively. The    
1:06:22    
results constitute the first empirical evidence that any artificial system passes a standard three-party touring    
1:06:30    
test. The results of implications for debates about what kind of intelligence    
1:06:35    
is exhibited by large language models. And so that's kind of um that okay so we    
1:06:44    
had a comment in the oh uh VD asked BNY    
1:06:49    
uses a wiser right is this B bny is what    
1:06:56    
um like BNY is the bank of New York I think they have collaborated with open AI and they are using right now like to    
1:07:04    
the in the company. Yeah. Yeah.    
1:07:09    
Yeah. Yeah. So that's interesting. Yeah. That's kind of the imitation game in uh modern context, but in terms of thinking    
1:07:17    
about language models and human conversation. So um I'm not sure kind of where because    
1:07:26    
we've we've talked about some of the ways that um they've applied reasoning models and so like large language models    
1:07:32    
can produce linguistic output. But then there's this there are these reasoning models that we built on top of large    
1:07:39    
language models usually like reinforcement learning models where they try to refine the output and allow the    
1:07:46    
model uh large language models to reason and that's kind of you know I don't know what what level they were were they    
1:07:52    
having like an informal conversation or were they asking about specific types of    
1:07:57    
problems you know how do you solve this problem how do you solve that problem but it's interesting that the different    
1:08:03    
language models got different degrees of correctness where people got it's worth mentioning that that    
1:08:10    
reasoning process that isn't the RL portion uh which uh I'm blanking on the    
1:08:15    
name of that but generally that's due to chain of thought the RL portion is when    
1:08:20    
when chat prompts you which answer is better and there's a whole RL process that they use to uh to to fine-tune    
1:08:27    
their models which is actually very effective. Yeah.    
1:08:34    
Uh okay. And then what if we go to the other paper that you posted in here, the    
1:08:40    
dream coder. So this is dreamcoder. Um this is this    
1:08:46    
neuros symbolic paper um bootstrapping inductive program    
1:08:52    
synthesis of wake sleep library learning. So this is actually Josh Tenonbomb is on this paper. Um    
1:09:01    
so this is uh we present a system for inductive program synthesis to all dream    
1:09:07    
coders. So they're doing program synthesis which inputs a corpus of synthesis problems each specified by one    
1:09:14    
or a few examples automatically deres a library program    
1:09:20    
components and a neural search policy that can be used to effectively solve    
1:09:25    
other similar synthesis problems. The library and search policy bootstrap    
1:09:30    
each other iteratively through a variant of wake sleep approximate bas    
1:09:36    
approximate basian learning. So they have these wake sleep cycles that approximate basian learning. A new    
1:09:43    
refactoring algorithm based on egraphph matching identifies common subcomponents    
1:09:49    
across synthesized programs building a progressively deepening library of abstractions    
1:09:55    
capturing capturing the structure of the input domain. So they uh evaluate uh    
1:10:02    
classic program synthesis areas and AI tests such as planning, inverse graphics    
1:10:09    
and equation discovery. So uh jointly learning the library and neural research    
1:10:14    
policy leads to solving more problems and solving them more quickly. That's um    
1:10:22    
I don't know if Morgan uh because he's interested in program    
1:10:27    
synthesis and things like that. Um has anything to say about that?    
1:10:34    
I I do I'm just driving right now. Okay. But thank you. Yeah, try try do it in a    
1:10:42    
bit. All right. Yeah. Okay.    
1:10:47    
Um, yeah. So, I don't know if we want to talk about uh want to continue on with    
1:10:52    
this line of discussion or have anything else to say.    
1:11:02    
Okay. Well, yeah, that's interesting stuff. And we'll come back to Morgan later.    
1:11:09    
Actually,    
1:11:20    
I'm going to talk about this for a while. This is uh a set of papers where    
1:11:27    
they this is kind of moving away a little bit from the AI discussion and    
1:11:33    
talking about something called conservation laws and modeling physics.    
1:11:38    
So you know in physics we have conservation laws, we have    
1:11:43    
thermodynamics and so we can approach uh machine learning through incorporating physical    
1:11:51    
principles. we can learn conservation principles    
1:11:56    
using machine learning and then we can also um kind of think about conservation    
1:12:04    
laws as sort of a framework for understanding self-organizing systems.    
1:12:09    
So I'm going to go through these three papers and see what the state-of-the-art is in this area. It's kind of a broad    
1:12:15    
area and it involves a number of different sorts of approaches and things    
1:12:20    
like that. But you know, we will learn something more about physics modeling and things like that as we go along.    
1:12:29    
So this first paper is uh from the archive. It's from the condensed matter a soft matter uh part of the archive    
1:12:39    
and uh this is a unifying approach to self-organizing systems interacting via    
1:12:44    
conservation box. So uh the abstract reads    
1:12:50    
zoom in. We present a unified framework for    
1:12:56    
embedding and analyzing dynamical systems using generalized projection    
1:13:02    
operators rooted in local conservation modes. So in this paper what they want to do is they want to understand analyze    
1:13:09    
dynamical systems and want to embed dynamical systems using a certain type    
1:13:16    
of mathematical framework by representing physical biological and    
1:13:22    
engineered systems as graphs with incidents and cycle matrices. We drive    
1:13:28    
drill projection operators that decompose network fluxes and potentials.    
1:13:33    
So they're using this formalism to represent these kind of physical biological and engineered systems.    
1:13:41    
This formalism aligns with principles of non-equilibrium thermodynamics and captures a broad class of systems    
1:13:49    
governed by flux forcing relationships and local constraints. So what they're    
1:13:55    
doing is they're taking this mathematical model and they're capturing a lot of these aspects of physical    
1:14:00    
systems. We extend this approach to collective dynamics    
1:14:06    
through this thing called prreds which is projective embedding of dynamical systems.    
1:14:12    
And so this is an embedding of the of the dynamics of these kinds of systems    
1:14:19    
which lifts lowdimensional dynamics into highdimensional space    
1:14:25    
enabling both replication and recovery of the original dynamics. So what    
1:14:31    
they're doing is they're looking at these kinds of dynamical systems. They take lowdimensional dynamics.    
1:14:38    
They embed them in a highdimensional space or they lift them up. They enable    
1:14:44    
the recovery of the original dynamics which is important. When systems fall within the PRS class,    
1:14:51    
their collective behavior can be effectively approximated through projection onto a mean field space.    
1:14:59    
So this enables us to be able to approximate these kinds of the behavior of these kinds of dynamical systems.    
1:15:07    
We demonstrate the versatility of PRS across diverse domains including    
1:15:12    
resistive and mebrrist of circuits, adaptive flow networks such as slime    
1:15:17    
molds, elastic string networks and particle swarms. So these are    
1:15:24    
I guess these are you know you can think of these as computational systems. So what we're doing is we're trying to    
1:15:30    
approximate these dynamics in these different types of computational systems or these    
1:15:37    
information processing systems which are not vonoyman computers at all. They're    
1:15:43    
in fact physical or you know uh physiobiological systems. Um and so we    
1:15:51    
have you know particle swarms, memory step circuits, adaptive flow networks such as    
1:15:57    
slime molds of course there computing there is swarm particle optimization    
1:16:04    
there their elastic stream you can compute on networks and things like that.    
1:16:10    
Notably we establish a direct correspondence between creds and swarm dynamics.    
1:16:16    
So use swarm dynamics as a particular instance of this revealing new insights    
1:16:21    
into optimization and self-organization. Our results offer a general theoretical    
1:16:27    
foundation for analyzing complex network systems and for designing systems that    
1:16:33    
self-organize through local interactions.    
1:16:39    
Okay. So this is uh uh Paul sidenone memor    
1:16:46    
was that side none memorist of circuits were one    
1:16:51    
of the main approaches to neuromorphic computing. I'm not sure whether these things have changed since I was last    
1:16:56    
reading in that field. Yeah, this is one of the key technologies in neuromorphic    
1:17:02    
computing. I think it still holds. Um yeah, so you're you're doing a lot of    
1:17:07    
different types of unconventional computing. I mean unconventional being not uh typical    
1:17:14    
stuff. So yeah, so this is and then this is the they have their uh table of    
1:17:20    
contents here where they kind of go through and talk about um some of these    
1:17:26    
kind of physical and biological computational systems, dissipative networks, resistive and memoristive    
1:17:33    
circuits, adaptive flow networks and slime molds and elastic spring networks. So this variety of physical kind of    
1:17:40    
systems and being able to replicate dynamics on those Uh then they had the    
1:17:45    
PRS approach here which they lay out in part two. They're mapping PRS to a    
1:17:51    
particle swarm model and then they do these numerical systems simulations of particle swarms where they kind of show    
1:17:59    
this model in in action and then of course they talk about graph theory    
1:18:05    
network dynamics and then these different um so circuit based dynamics    
1:18:10    
and networks flow networks hookie networks and projection based adaptation    
1:18:17    
not sure what a hookie network is it be um something to do with cells    
1:18:23    
um and then particle swarms in particular where we have things specific    
1:18:30    
to that. So this is kind of talking about how to model conservation laws uh as part of    
1:18:38    
the dynamics of dynamical systems and then mapping them to these uh these non    
1:18:47    
non-traditional computing paradigms. And so I'm not going to go through the whole paper, but I just wanted to make    
1:18:54    
people aware of this kind of work um and how and there's a lot of technical    
1:18:59    
detail on the paper itself. But basically they're taking the dynamics of    
1:19:05    
a system, they're putting it into a higher dimensional space and then they're putting it into these frameworks    
1:19:12    
uh where you can actually um model the or I guess you can play the    
1:19:18    
physics and the dynamics out in these systems. Okay, so that's an interesting paper.    
1:19:24    
Um, and I'm not I'm not getting I don't have a handle on all the technical    
1:19:30    
details, they'd probably go over our heads, but that's you know the way a lot of the you know when when people were    
1:19:38    
kind of applying physics to computation typically what happens at least to me    
1:19:43    
anyways. Um this is a p second paper here which is from machine learning    
1:19:48    
science and technology. Now this is a different sort of thing. And this is uh beyond dynamics learning    
1:19:56    
to discover conservation principles. So this is where you're taking data from    
1:20:02    
maybe like a dynamical system and you're learning or discovering conservation    
1:20:07    
principles from them using a more standard machine learning approach.    
1:20:13    
So this is the abstract here. The discovery of conservation principles    
1:20:19    
is crucial for understanding the fundamental behavior of both classical and quantum physical systems across    
1:20:26    
numerous domains. This paper introduces an innovative method that merges representation    
1:20:33    
learning and topological analysis to explore the topology of conservation    
1:20:39    
law spaces. So this is where you know I guess you're learning things    
1:20:45    
like a network topology or sort of the configurational    
1:20:50    
entropy of some system and you're able to merge that with representation.    
1:20:58    
Um, notably the robustness of our approach to noise makes it suitable for complex experimental setups and its    
1:21:06    
aptitude extends the analysis of quantum systems as successfully demonstrated in    
1:21:11    
this paper. Okay. We exemplify our methods potential to unearth previously unknown    
1:21:18    
conservation principles and endorse interdisciplinary research through a    
1:21:23    
variety of physical simulations. Um, in conclusion, the work emphasizes    
1:21:29    
the significance of datadriven techniques in deepening our comprehension of the principles    
1:21:35    
governing classical and quantum physical systems. So this is where you know we don't    
1:21:40    
really understand fully the conservation laws involved in real world systems. So    
1:21:47    
if we collect data on them and uh you know analyze them using machine learning    
1:21:53    
we can maybe discover new principles. Um and so this kind of talks a little    
1:21:59    
bit about conservation laws and their importance to the physical world.    
1:22:04    
Um the discovery and application of these principles span various disciplines.    
1:22:10    
In recent years, datadriven techniques have emerged as powerful tools for uncovering previously unknown principles    
1:22:17    
and fostering innovative interdiciplinary research. So their novel method tackles the    
1:22:23    
challenge of revealing hidden conservation laws through the synergistic combination of representation learning and topological    
1:22:31    
analysis. Um and so um they organized their paper in    
1:22:38    
terms of first covering related work. So their previous approaches to the    
1:22:45    
discovery of conservation laws. Then there's a methods description which    
1:22:50    
details their data-driven algorithm. Um and then in section four they analyze    
1:22:57    
the implications limitations of future research of their approach. They do some    
1:23:03    
physical simulations and then they discuss the implications of that and then they highlight critical    
1:23:11    
insights and emphasize the potential of this technique and advancing our    
1:23:17    
understanding conservation models. So actually if we go down to section six    
1:23:24    
uh they talk about the limitations they talk about the comparison    
1:23:30    
um so why don't we talk about the comparison and then the limitations and    
1:23:36    
then some of the broader locations. So don't you know glossing over the    
1:23:41    
technical details to get to some of the sort of broader applications here. So in    
1:23:48    
terms of the comparison on the simple example of the coupled oscillator, so they give an example of a coupled    
1:23:54    
oscillator um in one of their experiments. Our approach showed the ability to discover    
1:24:00    
the underlying principles as good as the previous methods. However, we achieved    
1:24:06    
the new previously unmet results for the more complicated systems. More    
1:24:11    
specifically, in the experiment with the oscillating touring patterns, we showed that the ability of our algorithm to    
1:24:18    
uncover topologically non-trivial shape space. Well, while well while method for by Lou    
1:24:25    
2022 is only able to represent the same shape space in the higher dimension. So    
1:24:30    
they're able to they're doing things of oscillators and touring patterns which are you know different patterns of you    
1:24:39    
know different shapes that emerge from the sort of chemical morphogenesis    
1:24:44    
process. Uh and oscillators of course are things that produce oscillations.    
1:24:50    
Um those they're able to compare it with some of the existing methods and they're    
1:24:57    
able to do this I think more effectively is their point. Furthermore, our algorithm was able to discover the    
1:25:03    
number of conserved quantities in a quantum system which has not been done by the previous algorithms covered in    
1:25:10    
their review of the uh contemporary methods. We cannot compare our method to    
1:25:17    
the other approaches solving the same problem because it atall 2020 do not    
1:25:22    
have open code for their approach and the method of lu 2022 is hyperparameters    
1:25:28    
which we cannot tune. That's fun. It's always fun to have kind of limitations.    
1:25:33    
But the point is is that they do um you know pretty good job with respect to    
1:25:39    
previous work and they actually come up with some pretty novel results um in comparison.    
1:25:46    
Now their approach that they propose here has a few limitations. One comes from assumptions about the dynamical    
1:25:53    
system and the data collected from it. So uh the trajectories of the dynamical    
1:25:58    
system should be erotic. Um and even though most of the simpler    
1:26:04    
physical systems are erotic, non-argotic systems exist. In fact, most systems in    
1:26:09    
the real world are non-orgotic. Ergotic assumptions are usually um you know    
1:26:16    
idealized assumptions. So you know if you're doing the sort of data driven    
1:26:22    
approach um you need to be able to deal with narcotic systems which are    
1:26:27    
interesting for discovering but not available for discovery with our approach.    
1:26:32    
Another aspect of data collection is that all conserved quantities should vary. Moreover, variations of different    
1:26:39    
quantities should have approximately the same magnitude. Otherwise, the algorithm will not detect    
1:26:45    
directions in the shape space C with a small variance resulting in an underestimated number of conservation    
1:26:52    
laws. So there are some systems that don't have conservation laws and one example    
1:26:58    
of that is a pendulum with friction. So a pendulum is this uh weight, you know,    
1:27:04    
on a on a a rod or a string that moves back and forth and there's friction on    
1:27:10    
that pendulum. So this is a system without a conservation law.    
1:27:16    
And this can uh this okay so that sort of systems without conservation laws    
1:27:21    
also cannot be found by our algorithm since the minimal possible prediction about the number of conservation laws    
1:27:28    
for algorithms is one. So sometimes you can't model certain uh physical systems    
1:27:35    
that don't have conservation laws. In addition, trajectory should be sampled long enough to represent the respective    
1:27:42    
iso well. And so this is where we have this sort of abstraction from the    
1:27:48    
physical system to model some of the dynamics and we need to have    
1:27:54    
trajectories that can be sampled long enough to extract those dynamics. And so    
1:27:59    
again, you know, when you're uh obtaining data from physical systems, it's hard to know at what time scale the    
1:28:07    
dynamics emerge. You can have things like coupled oscillators where the    
1:28:12    
temporal dynamics are much longer than like say a simple oscillator or a single oscillator. And so those are things that    
1:28:19    
you need to understand before you try to extract conservation modes.    
1:28:26    
Another limitation comes in the number of trajectories. As we've shown in our examples, if the number of conservation    
1:28:32    
laws in a system is low, is it enough to sample 200 trajectories even for systems    
1:28:38    
of very complicated shape spaces? And then so the question is or I guess    
1:28:44    
it is enough to sample that penny. So your, you know, if you know the number of conservation laws that exist in your    
1:28:52    
system, it's, you know, sparse sampling is probably good enough. And so that's    
1:28:58    
that's kind of what they found here. However, we expect the required number of trajectories to grow exponentially    
1:29:05    
with respect to the number of conservation conserved quantities which makes it computationally more expensive    
1:29:11    
to evaluate our model on systems with high number of conserved quantities. So    
1:29:16    
that's kind of the limitation there is we don't necessarily know from any given    
1:29:22    
physical system what level of sort of complexity or conservation laws we    
1:29:29    
should expect. So it's you know kind of hard to do this exercise. We can maybe do this for well characterized systems    
1:29:35    
well but we need to characterize your physical system before we can extract laws from it.    
1:29:42    
Um and there's this whole literature on finding scientific laws as well. Like there people who have tried this with    
1:29:49    
different software platforms or they tried to extract like equations that describe different aspects of a physical    
1:29:56    
system. And you know this has been like a quest that's been ongoing for decades    
1:30:02    
where you know you'll have some algorithm that will extract all these potential equations and then you try to    
1:30:08    
like evaluate those equations and see which ones best describe the systems dynamics across all all manner of    
1:30:16    
different state uh configurations. So you make that erotic assumption about    
1:30:21    
the system and you search for the the laws or the equations that fit those    
1:30:26    
that assumption. And so that's kind of where we are. So they they really kind of think made a    
1:30:33    
nice exploration of this um uh and you know overall this work    
1:30:40    
emphasizes the potential of data-driven techniques to advance our understanding of conservation laws, the robustness to    
1:30:47    
noise. Okay, we believe this approach can drive innovations and interdisciplinary collaboration by    
1:30:54    
helping researchers elucidate the core principles that dictate system behavior across numerous domains. Further    
1:31:01    
refinements of this technique could enhance its applicability even more intricate systems. They don't really    
1:31:07    
give like good application domains, but that's kind of, you know, it's the way    
1:31:13    
these things go. Sometimes it's hard to know where to apply them. Um so this is the last paper here. This    
1:31:20    
talks about heavy and physics networks a self-organized in computational    
1:31:25    
architecture based on local physics laws. So um they they're thinking about this    
1:31:33    
more in terms of how to merge heavy learning with physics and learning uh    
1:31:40    
physics laws. So traditional machine learning approaches in physics rely on    
1:31:45    
global optimization, limiting interpability and enforcing physical constraints externally.    
1:31:53    
So this is kind of this approach to machine learning where you're doing    
1:31:58    
global optimization. So this they want to kind of break out of that paradigm. So they introduced the    
1:32:05    
Hebian physics network or HPN which is a self-organizing computational    
1:32:11    
framework in which learning emerges from local heavy and updates driven by    
1:32:17    
violations of conservation laws. So whenever conservation laws are violated,    
1:32:22    
it learns those violations and it tries to frame them. conservation discovery of    
1:32:27    
conservation laws in that context grounded in non-equilibrium thermodynamics and inspired by    
1:32:34    
priagene's theory of dissipative structures HPN's eliminate the need for global loss functions by encoding    
1:32:41    
physical laws directly into the systems local dynamics so it's kind of working from this    
1:32:48    
principle of distributive structures and non-equilibrian thermodynamics    
1:32:54    
uh which is more applicable to real world systems. By the way, um residual residuals, quantified    
1:33:01    
imbalances in continuity, momentum or energy serve as thermodynamic signals that    
1:33:08    
drive weight adaptation through generalized heavy plasticity. So the network is learning from these different    
1:33:15    
imbalances, different um heterogeneities of the dynamics and it's learning from    
1:33:23    
them. Um we demonstrate this approach on incompressible fluid flows and continuum    
1:33:29    
diffusion where physically consistent structures emerge from random initial conditions    
1:33:35    
without supervision. Uh HPN's reframe computation as a    
1:33:42    
residual driven thermodynamic process offering an interpable scalable and    
1:33:48    
physically grounded alternative for modeling complex dynamical systems.    
1:33:54    
So this kind of shows this graphic in figure one. This is a conceptual lineage    
1:33:59    
of Hebian physics networks. And so they they start with the hopefield network    
1:34:05    
which is where you start by trying to find the energy minima.    
1:34:10    
Then you have this Boltzman machine which is grounded in equilibrium thermodynamics.    
1:34:15    
And then it leads to the heavy and physics network which is grounded in nonequilibrium thermodynamics.    
1:34:21    
So it's like you transition between these three types of models. So the    
1:34:27    
hopefield network model convergence the deterministic energy minima Boltzman machines incorporate stochastic    
1:34:33    
equilibrium sampling and then HPN's generalize these approaches to non-equilibrium systems. So kind of like    
1:34:40    
one approach builds on the next approach meaning this heavy in physics network.    
1:34:47    
Um so traditional machine learning methods of physics often depend on    
1:34:53    
global optimization procedures such as back propagation. While these techniques    
1:34:58    
are effective they can be computationally expensive, difficult to interpret and detach from physical    
1:35:05    
principles. So you know we have different optimization procedures but are they really you know modeling    
1:35:13    
physics? Are they really close to the the dynamics or are they just kind of abstracting too much away?    
1:35:19    
We propose a fundamentally different approach which they call hebian physics networks and this is a classic    
1:35:26    
computational network of which nodes evolve through a local physically interpretable updates without requiring    
1:35:33    
any loss global loss function. So this is uh where we don't need a loss function. We just need to make these    
1:35:41    
local updates and we can build a good model of physics uh for different types    
1:35:47    
of dynamics. Previous frameworks including hopefield networks, Boltzman machines, energy    
1:35:54    
based models, spiking neural networks and the free energy principle which they throw in there have incorporated notions    
1:36:02    
of locality or thermodynamic routing. So these are all kind of these kind of physics inspired models that are also    
1:36:10    
have this neural component and they try to predict you can use them to predict    
1:36:16    
the physics of a system. Um however they remain fundamentally tied to equilibrium    
1:36:22    
paradigms or global supervision. So you have a lot of these systems that model    
1:36:28    
physics sort of modeling them with this equilibrium assumption. And of course a    
1:36:33    
lot of real world physics were interested in far from equilibrium or non-equilibrium    
1:36:38    
phenomena. HPN's depart from equilibrium based or globally optimized frameworks by    
1:36:45    
embedding principles of non-equilibrium thermodynamics directly into the network architecture.    
1:36:51    
Um, inspired by Priagene's theory of dissipative structures, each node    
1:36:57    
encodes a physical variable and evolves by penalizing connections and increase local residuals such as violations of    
1:37:05    
continuity, energy balance, or phase space conservation.    
1:37:10    
Synaptic weights are updated through a reinterpreted heavy rule. reinforces physically consistent interactions while    
1:37:17    
suppressing inconsistent ones with a biologically motivated decay term. And    
1:37:23    
so they kind of talk about these this class of conventional physics and for neural networks or pins. And these are    
1:37:30    
models that have been explored recently to sort of model these equilibrium    
1:37:36    
physics. Pins enforce physical laws externally    
1:37:42    
via loss functions. But in contrast, HPN's learn from within. The physics are not added to the    
1:37:49    
network, but rather drive it. The result is a self-organizing interpretable    
1:37:54    
framework capable of reproducing complex physical dynamics without global optimization or the explicit    
1:38:01    
discretization of uh partial differential equations. So that is the heavy in physics    
1:38:08    
networks. So these are three different approaches are very different in the way that they're approaching problem    
1:38:15    
different problem domains. Okay. So Paul uh yeah he put links to    
1:38:21    
the papers in the chat. Thank you very much for that. Um yeah so any comments or questions?    
1:38:33    
Okay. So Paul says,    
1:38:38    
"Hopefield networks were originally conceptualized as a robust way of storing information.    
1:38:44    
Basically a hopefield network as a set of nodes and are connected by edges.    
1:38:50    
If a value of the node is accidentally erased, it can be reconstructed from the value of the edges. And then um    
1:38:58    
helpfield methods are trained by minimizing an energy function. There has has to be an unlearning process so that    
1:39:05    
the edges don't just converge to zero. There's something called the kick    
1:39:10    
emitches hypothesis that basically states that unlearning is related to the    
1:39:16    
reason why we need sleep. Oh yes, this sleep where we consolidate memory by unlearning things and yeah it's good.    
1:39:25    
Yeah, there's this unlearning process in Hopefield networks and it's just kind of a way to keep the    
1:39:32    
network from converging. Yeah. Yeah. Hotfield networks are are no    
1:39:38    
longer taught in ML and I think that's kind of a a mistake like we should also cover, you know, restricted bolts    
1:39:45    
machines and hot. I think there's some interesting things there even if they're not.    
1:39:50    
Yeah. Yeah, I think so too. Um yeah there's a lot of interesting    
1:39:56    
stuff that uh we can learn from kind of    
1:40:01    
thinking about physical systems and then this goes back to this discussion of the    
1:40:06    
touring paper which you know I realize that there's the touring paper and then    
1:40:11    
there's this discussion they had in the BI group where they kind of talked about    
1:40:17    
sort of the implications and they talked about um you know different ways to    
1:40:22    
think about systems. So you have the simulant and the replicant. And what we're talking about here is maybe a    
1:40:29    
combination of the two where you have the simulant but also the replicant because you have physical systems but    
1:40:35    
you're also looking at the computational representation. Looks like Morgan is ready to go here.    
1:40:45    
Good morning. I I don't know about ready to go. um    
1:40:50    
having my first sip of coffee. So um    
1:40:56    
yeah, I mean whenever I see these, you know,    
1:41:05    
they're they're super interesting. Um    
1:41:14    
I'm not um well again I I think if I was more of a    
1:41:21    
computer engineer Yeah. as as opposed to a more um    
1:41:29    
um wannabe breaking scientists, you know. Yeah. I I might get more from these. Um    
1:41:37    
but you know it's it's it is fascinating in a kind of you know leanesque kind of    
1:41:44    
way to see the diverse forms of computation. Yeah    
1:41:50    
I guess and or Yeah. Yeah. um when I when I think about the the the kind of    
1:42:01    
physics laws or you know I still think    
1:42:08    
like physics informed neural networks might be more more interesting again for    
1:42:16    
the kinds of problems that I'm interested where you know you've got    
1:42:23    
neur imaging techniques that you could you could use some some    
1:42:31    
physics constraints and the mathematical modeling which is like    
1:42:38    
both computationally superefficient as well as is you know    
1:42:44    
potentially providing u superior resolution and and um    
1:42:53    
Yeah, but that's my that's my practical take.    
1:42:59    
I mean, you know, I I I love um uh    
1:43:04    
Yeah. I mean, of course, I always think of Adamsky, although I don't think he does any    
1:43:11    
physical computation kind of work. No, I think his work is largely like on    
1:43:18    
like things like slime looking at he's more in the unconventional,    
1:43:23    
right? Yeah. Yeah. Yeah. But um    
1:43:32    
uh I I still I mean I I do try to follow the neuromorphic computing    
1:43:37    
because it does I I think at some point it would maybe be more relevant for for    
1:43:45    
the designs of of like organoid intelligence or you know    
1:43:52    
again the biological computation right Um    
1:44:06    
the they the the not not turning like papers but the big    
1:44:14    
the big discussion in computational psychiatry right now is about the    
1:44:24    
um different language models and their    
1:44:30    
ability to engage in um    
1:44:37    
you know therapeutic conversations. Yeah. Um    
1:44:44    
and and what what goes wrong with language models when you ask them when you constrain them in a therapy patient    
1:44:52    
kind of relationship, right?    
1:44:58    
Basically how they become sociopathic. Oh, right. We talked about that. Yeah.    
1:45:03    
Which is it's an interesting it's an interesting problem.    
1:45:09    
Yeah. But I I just saw like Tom Insul and a    
1:45:15    
couple other people chime in on this most recently.    
1:45:20    
Yeah. You know, and you know, I think he's    
1:45:26    
definitely been in Silicon Valley too long. Oh, yeah. You know, now have GBT5 coming out. We    
1:45:34    
should have a serious conversation about the I think we could have had a conversation    
1:45:41    
about it before that. Yeah. Yeah. Um yeah, it's it's interesting u    
1:45:49    
some Yeah. the application.    
1:45:55    
Yeah. Yeah. So, you know, I'm I'm looking forward to some people, you    
1:46:02    
know, as opposed to the amount of um you know, fawning praise that I've heard    
1:46:09    
so far. I'm I'm waiting to hear some people starting to    
1:46:14    
find, you know, easy easy ways to break it. Yeah,    
1:46:20    
certainly certainly easy ways to um get    
1:46:27    
I don't know if you want to call it degenerate behavior, but like um    
1:46:35    
[Music] I I and and also just to be on the    
1:46:42    
engineering teams in terms of how they how they try to,    
1:46:47    
you know, fix the known problems in ways that you've got to imagine relate to    
1:46:53    
like either fine-tuning or other explicit constraints.    
1:47:00    
Yeah. I just just wondered, you know, because    
1:47:05    
again, you know, the the real problem for a lot of these teams is that like this isn't just a research project. This    
1:47:12    
is there is significant amounts of money on the line here. Oh, yeah.    
1:47:18    
Um, so    
1:47:25    
yeah, I noticed you've been you said that you were catching up on the BEu conference. What did you think about    
1:47:30    
some of the stuff going on there? Yeah, I mean, terrific stuff, right? I mean,    
1:47:37    
you know, super interesting. Uh, I I know you've you've attended before.    
1:47:43    
Oh, yeah. Right. Yeah. Right. And um uh    
1:47:48    
anyway, it's it's every every time I'm listening in, it's an interesting it's an interesting    
1:47:55    
conversation and it's and and quite wide ranging, you know. Um    
1:48:03    
so I I really enjoyed it's just been just been so busy here,    
1:48:12    
you know, building out the lab. So, we're we're kind of like on the last the    
1:48:18    
last like big changes that are needed in the lab space to to    
1:48:24    
really flesh out the subcultural facility. Just some some things where we've got to    
1:48:30    
like actually shut down the entire building.    
1:48:36    
It's just some of the water some of the plumbing work. We're just going to have to turn off the water for the entire    
1:48:42    
building to get it done. Okay. Um, but this this weekend, um, so I'm    
1:48:48    
gonna take off pretty soon. Um, this weekend we're doing a a biopunk    
1:48:54    
hackathon. Okay. And so we'll be doing all sorts of    
1:49:01    
uh I mean I think there's definitely a few projects that have been proposed with    
1:49:08    
bounties [Music] and um    
1:49:14    
but the big thing that we will be doing is James and I will be showing people if    
1:49:19    
they're interested how to convert a 3D printer into a 3D bio printer.    
1:49:26    
Okay. So, both uh hacking the firmware and    
1:49:32    
replacing the plastic extruder with a syringe, mechanically controlled syringe    
1:49:38    
and then you can do what they call fresh bio printing. So, you're printing into a    
1:49:43    
hydrogel. That's pretty cool. It is. It is very cool. it. We James,    
1:49:53    
you know, the the team that went to Pittsburgh to to learn this. Um, we were    
1:49:59    
all super impressed with with what they were doing. Um, so this was like a real    
1:50:05    
tissue engineering group at Cardi Melon that does this.    
1:50:12    
and um yeah like like the former student    
1:50:17    
of the PI who's now a professor at UKIT um is kind of the technical guy who has    
1:50:26    
like so many open source projects and it it's great because what you know    
1:50:33    
they're a tissue engineering group but they in addition to the the 3D vibrating    
1:50:41    
Um in addition they do basically they're doing soft robotics development to test    
1:50:47    
the tissues that they're fabricating.    
1:50:53    
So when it comes to the heart they're you know again making kind of mechanical    
1:51:00    
devices to um either to be controlled by the muscle    
1:51:05    
that they're they're making or um to to    
1:51:11    
use some sort of um test stretching or things like that to    
1:51:18    
the material. They do doing this all you know for    
1:51:24    
vessels for skin for etc. or making    
1:51:29    
bioreactors for say some sort of um liver like tissue that they've generated    
1:51:37    
that just needs to maintain culturally for a long time. So I got to say we were    
1:51:45    
we really lucked out in terms of finding this particular group and um and    
1:51:51    
being able to learn from them these skills is is awesome. So um trying to    
1:51:58    
bring that to the lab and and the real you know opening here is that basically    
1:52:04    
there's not a lot of groups that do this with neurons. So there's there's organoid groups. I    
1:52:11    
was trying to get this across to to we had a visitor had some journalists come through the tower and you know like    
1:52:19    
we're not trying to do the kind of brain science that say Alison is doing UCSD    
1:52:26    
um but you know we can do something that's still kind of research grade um    
1:52:34    
and just being learned in terms of how um neurons in these biological scaffolds    
1:52:41    
uh the connectivity that they they form and    
1:52:46    
the kind of complexity that you can find in terms of you know complexity in in    
1:52:54    
shorter time frames that that potentially could be could be grown um    
1:53:00    
would be would be kind of one of the metrics and in additional to kind of information theoretic metrics that are    
1:53:07    
kind of standard for the electric analysis Um    
1:53:12    
um I think that's yeah I mean that's that's our big thing this weekend. We've    
1:53:19    
got a lot of um yeah got a lot more to say about tissue    
1:53:25    
engineering but    
1:53:35    
well yeah good luck with all that. I know you've been working on that like kind of a longterm thing and it sounds    
1:53:40    
like it's coming together now. So, and then at the end of the month we've got Katarina coming to to present.    
1:53:48    
Oh, okay. Yeah. Yeah. So she's got this is sorry    
1:53:53    
she's a postoc at UC Santa Cruz and her    
1:53:59    
co-founder so they've got a startup that's again focused on some aspect of organoid    
1:54:06    
culture um it's called like open culture systems or something like that um    
1:54:14    
and yeah they're going to be coming to talk about um you know real real    
1:54:20    
organite culture. Yeah. Uh but their work has still primarily been,    
1:54:28    
you know, brain science work, right? So they're they're trying to grow a brain,    
1:54:34    
you know, they're trying to to culture a particular tissue target and and that    
1:54:41    
tissue target is like, you know, it's supposed to capture    
1:54:46    
that particular real brain area, right? and and then be able to understand    
1:54:52    
things about that mechanistically or you know relating to cell types and things    
1:54:58    
like that, right? Whereas organoid intelligence is like you can flip it and    
1:55:03    
you know use the engineering to just to generate the kinds of cell types    
1:55:09    
organization that you want and and you know that hopefully    
1:55:16    
are simulatable. um uh uh because then    
1:55:23    
then then perhaps they can be used in computation    
1:55:29    
in a more directed or you know controlled fashion. Um anyway, that's    
1:55:34    
the goal. Yeah, great. Well, thanks.    
1:55:39    
All right. Uh so I don't know did Paul or VD have anything they wanted to add    
1:55:45    
uh before we wrap it up for today? If not, I have uh I've got nothing. Uh at some    
1:55:53    
point, I'd like to know more about Morgan's background, but we don't have to do that during the meeting.    
1:55:59    
I'm just experimental psych and molecular biology. Okay. Are you are you a psychiatrist or    
1:56:06    
I see No, I do. Yeah. No, I do psychiatric research. I mean, but this is like I do psychiatric.    
1:56:14    
So I do I do computational modeling of of large MRI data sets.    
1:56:20    
Okay. We should we should definitely uh talk sometime because I'm planning on    
1:56:26    
doing an MD PhD and there's a good chance I'm gonna end up doing psychiatry. Either that or    
1:56:31    
neurology. Um no no psychiatry is the best. I I just brought that up just because there's    
1:56:37    
there's an interesting um there's an interesting program in Austin that at    
1:56:43    
the Dell um yeah Dell Medical Center. So    
1:56:50    
great stuff. And yeah, there's the other great thing is uh there's so many    
1:56:55    
publicly available neuroiming data sets that you can be working with now and and    
1:57:02    
learning from. Yeah, I have a few pups using those. So, okay, cool.    
1:57:07    
Good that they exist. Yeah. Yeah. Yeah. Yeah.    
1:57:13    
All right, that's great. All right, so I think that's it for today. Um, thanks for attending and um,    
1:57:20    
you know, if we're interested in doing any features or presenting any or talking about papers, uh, please let me    
1:57:27    
know. And um you know otherwise yeah see you next week.    
1:57:34    
Thanks. Bye guys. See you next week. I see you next week. Bye. Next.    
    

