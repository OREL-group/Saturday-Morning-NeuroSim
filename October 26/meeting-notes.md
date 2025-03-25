## Meeting Recording

[YouTube link](https://youtu.be/GJepE9vBMak)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113375875313857627)

## NOTES
Montreal NeuroAI conference (MAIN).

* workshops -- Friday (tutorials day. Scikit-Learn).

* workshop that might be (NIH, November 12-13, NeuroAI).

* does Neuro inform AI, and does ML inform neural data?


More computational Neuro -- conference -- EEGx (virtual/online).

* are foundation models enough now or anymore (overhyped terminology)?

* trend is not fully-enough absorbed (goes away).

* hype is consuming itself. Influencer/Academic stuff.

* how many things do I know of through social media?


Question: clinical AI event, preprints. Not first-mover bias, but a conformity bias.

* pressure to have a social media component. 


ROSCon -- discourse.ros.org -- Robot Operating System. Discourse for community.

* software that touches a lot of research.

* manipulation, path planning, hand-held mapping, Sim2Real transfer, agent planning.

* Finite Element Models -- robotics becomes more biomimetic.

* COLLAs (conference on lifelong learning). Spelke -- keynote @ NeurIPS. Cognitive development -- AI conferences.

* no dev, cog, embodiment in NeuroAI.

Materials spread across three conferences (robotics, MAIN, COLLAs) --> put all together --> BioAI.

* continual, Neuro data, embodied. Foundational domains --> everything gets mapped to that.

* Jesse: meeting (Thurs) -- Robin's take on Bergson (where is memory stored?) -- go to Page 16-18 (about halfway).

* debate -- dovetails into consciousness. Memory is distributed, how do you put back together (humpty dumpty with brain damage). 

* perception as memory (perceived stuff is already memorized).

* Hutto and Myin -- incoming causal chains discarded in making a pattern.

* incoming sensation --> x --> pattern formation. Gibsonian Information ties?

* LearnMem conference 2018 --> 5-year cycle. Physical memory aspect. Problematic evidence for easily stateable theory.


"Language and the Brain" -- gathers edge cases that doesn't map to established theories and metaphors.

* distributed nature of memory (engram). Primbram -- surgical populations, Neurosurgery --> to get into brain, need to cause damage.

* SOLMS -- theories derived from brain damaged cases (H.M.). How does function return -- localization of function vs. redundancy.

* Dynamic Memory Lab @ Davis (LearnMem 2023).

* Disrupting circuitry vs. discovering function (only get data from places you've collected it from).

* cerebellar work (statistical analysis). Statistical network -- distributed architecture. Resting networks --> dynamical systems.

* statistical networks -- distributed architecture. Resting networks --> dynamical systems.

* BICA stiff --> Morphofunctional models. Realism. many systems, subsystems @ play.

* need to fix as much variability as possible.

* mundane actions --> interplay more formal computational models --> Winter School of Cognitive Modeling --> dynamical models.

* anatomical modeling -- examples of hierarchical control, neural compositional strategies.

* layer-specificity. Cocomac --> tract tracingdataset. Non-human primate work. 

* Carbon Copies talk -- Drosophila brain model (Logan and Randal).


Many scales at which people currently collect data. Database @ different scales.

* origin of brain -- what bridges MRI to single-cell work?

* white paper on whole-brain emulation. Get function from structure (Morgan does not agree, AI safety-alignment).

* synthetic program (Makram), complete idea of CryoEM across organisms.


Big Brain detail, in a reasonable time. "Comparative Prospects" paper. Focus on Carbon Copies JClub.

* connectome-constrained networks --> DNM of fruit fly system.

* Shiu paper. Simulations using Drosophila. Flywire data, used to SNN model (in a reduced fashion).

* get olfactory behaviors out of the system. Super computationally efficient (full cable model vs. Shiu's model).

* motivated by good neural network theory.

Can't push any computational work to biology at this point.

## TRANSCRIPT
     
Transcript     
0:05     
hello morning morning     
0:11     
right right let's get started um so this week we had uh we had a diva     
0:20     
worm meeting and we had I think there was a cybernetics meeting that I didn't     
0:26     
attend because I didn't otherwise it was happening so     
0:32     
and we also had an admin meeting yesterday where we talked about our     
0:37     
continuing work on getting things submitted to the active inference conference this year so that's     
0:46     
coming up uh in November so that's what we did this     
0:53     
week um any updates     
1:04     
mention thei Neuroscience conference that was     
1:12     
this week oh in person yeah yeah yeah     
1:23     
unfortunately okay yeah that main conference yeah yeah I I mean I still     
1:29     
hope that they'll put videos up later of everybody yeah or at least all the the     
1:37     
main talks um um uh     
1:44     
[Music] the I I thought it was interesting what they had as workshops for the     
1:54     
um I think Friday was like um two tutorials day or or something but     
2:04     
um anyway it it looked like a bunch of psychic learn tutorials which I thought     
2:12     
was uh sorry I was um adjusting my setup so I didn't really     
2:20     
hear what was or ask or not oh I just asked him for the link for the main     
2:26     
conference which he has now okay     
2:32     
all right so I see them the link here main 24 uh so this is the main 2024     
2:38     
conference uh this is a robot eating a donut so that's topology um so yeah the     
2:47     
seventh edition and that's the poster and venue     
2:52     
it was in person keynote speakers Terry sanowski Luis pooa     
3:00     
uh Carlos Pon Donia precup Eva d l     
3:05     
Risco uh and then the day byday program is here course the speakers are here you have the usual speakers I guess from     
3:13     
Montreal the Montreal area um Ellen Institute     
3:20     
Etc so yeah looks pretty interesting um let's see if let's look at the uh     
3:27     
program here so this was the     
3:32     
Tuesday uh ear talking about alignment uh dynamical     
3:39     
systems uh I guess this is how to how we can teach humility to AI to make it     
3:47     
safe uh States based Dynamics and cortex and Transformers     
3:53     
um panel discussion and the evening uh a CAC was     
4:01     
some Neuroscience foundations for AI this talk here two New Perspectives on the structure function relationship     
4:07     
and neural networks Louise piso on the entangled brain and let's see Wednesday we had     
4:17     
scaling up speech bcis the emergence of abstraction in minds and     
4:23     
machines then doing a precup on continual reinforcement     
4:28     
learning uh uh comparative analysis of visual sensation and     
4:34     
perception visual representations in the human brain predicted by large language models there a really good stuff here uh     
4:41     
Thursday Foundation models for Neuroscience as Patrick manal uh a common B neural basis for     
4:49     
Behavior across individuals and species that looks interesting uh Blake Richards or the     
4:55     
brain-like learning with EXP exponentiated gradients     
5:00     
uh fast and slow learning and artificial and biological networks     
5:06     
um and then the evening multi-agent cooperation through learning aware     
5:11     
policy gradients Illuminating synaptic learning rules produ assignment neural networks     
5:17     
without plasticity and then they had a neuro AI     
5:22     
party so this is the party here um looks like that that was the program I didn't     
5:29     
see tutorials although it's probably in a different uh part of the     
5:36     
website um no is my bad they called it um educational oh uh um check the main     
5:45     
page yeah here it is yeah yeah yeah yeah I remember yeah I remember they did this     
5:51     
before where they had like education totally tot yeah so this was yeah the     
5:56     
main educational which I guess is uh before right after after the main     
6:03     
conference it said the 25th right yeah yeah yeah um where's the link to the     
6:12     
um did did did they show you the things that they are doing oh uh let's see     
6:19     
somehow I got to another page the schedule here okay okay I guess this is it yeah     
6:26     
yeah you see yeah like     
6:31     
yeah that what I expected I mean like psyit learn is awesome like let me not     
6:39     
uh I just thought for a thought everybody was focused on nuro     
6:46     
AI well pyit learn I mean that's kind of the melts and bolts of the methods I     
6:52     
mean I don't know how many neuro quote unquote neuro AI methods are sort of you     
6:58     
know have their own toolbox basically I mean I'm sure they do but it's not as     
7:05     
accessible so yeah I just I thought it would be more like CNS oh     
7:11     
well you know and trying to do some sort     
7:17     
of yeah I think they've got this optimized down to like some you know     
7:22     
lessons that you can learn and and you know I I know that     
7:28     
they've got a group of um researchers who like certainly know it well and you     
7:37     
know so yeah uh this was yesterday that's you know again that's it's great     
7:43     
and and um um yeah yeah so this was yesterday     
7:50     
and so in the morning they had the neuro AI primers which were these uh you know introduction to machine learning where     
7:56     
they had these different activities here introduction to supervised learning     
8:01     
using pyit learn model selection and validation using pyit learn then there     
8:07     
was ml interfaces for neuroimaging uh this one is machine learning and functional MRI and using     
8:13     
narn and then m& which is training machine learning models on Meg data     
8:18     
using & Python and pytorch so that was the morning there     
8:23     
were two tracks there you could like take kind of the machine learning or the sort of neuro track it wasn't you know I     
8:30     
guess they didn't integrate in the morning and then in the afternoon you had the neuro AI models this is where     
8:37     
you're kind of getting the Keynotes we have a keynote here experimentation on     
8:42     
in silicone neur neural responses that's here where in this     
8:49     
session you will use a pre-trained encoding model from the neural encoding data set which is Ned to generate     
8:56     
insilico functional magnetic resonance imaging reference from and in s phography EEG responses to images we     
9:04     
will then Leverage The generated in silicone neural responses for experimentation specifically using     
9:11     
relational neural control or RNC you will explore en silico fmri responses     
9:17     
for tens of thousands of naturalistic images to find controlling images at a     
9:22     
line or disentangle responses or different areas AC cross visual cortex     
9:27     
but us isolating the shared unique representational content so this is this neural encoding     
9:34     
data set which is on GitHub here this is actually the Ned     
9:40     
toolbox uh we have so the data set comes with pre-generated in silico fmri and Ed     
9:49     
responses or 150,000 naturalistic images coming from various sources here uh     
9:57     
which you can use for research purposes so this is an interesting or data     
10:04     
set that does sound I mean it does sound interesting it it's it it also sounds     
10:12     
very um I mean again I I'm just surprised     
10:18     
that that was the that was the topic why were you surprised by it I don't know     
10:27     
I I so one thing that I'm looking for is a um a workshop that I think might     
10:37     
be well I I'll I'll see if I can find the link but like like you know um     
10:45     
certainly NIH like November 12 13 oh yeah is doing like a neuro AI right     
10:55     
workshop and I I just thought it was going to be more like that     
11:01     
okay again I don't I don't know if my expectations um should be yeah     
11:09     
entertained what's the content of that Workshop well I think it's definitely     
11:15     
GNA be like again more of this kind of like does     
11:23     
nuro well I don't know let me let me let me see if I can find a program but the     
11:31     
um you know I think we kind of covered this in terms of talking about our own     
11:37     
kind of neuro AI Channel you know are we talking about Neuroscience informing AI     
11:44     
or are we talking about you know machine learning of neural data which is seems     
11:53     
to be the seems to be kind of what what you know certainly the main educational     
12:00     
um day focused on yeah yeah I think there's yeah definitely it's you know     
12:06     
people are kind of like they they think of it in terms of like the nuro and then the AI and they kind of bring them     
12:12     
together in some way and I you know I would think well okay it would be something like a neuro inspired     
12:18     
architecture or um you know some sort of thing like that but like a lot of times     
12:24     
just kind of there seems to be this like okay it's logical to bring together their data sets and build data Journal     
12:31     
models and then see where that goes I guess that's maybe one of the things we're kind of     
12:39     
conceptually you know maybe it's a little bit of a distinction there     
12:45     
but so yeah yeah no again I I I don't know if my expectations should be     
12:51     
entertained here like yeah yeah yeah it's not like     
12:57     
I've got good neuro AI theories well I think it's just one of     
13:03     
these fields where like we don't know where it's going yet so it's like you know people kind know do what they know     
13:09     
they bring it to the table and that's it I mean we have a lot of people trained across those domains it's just kind of     
13:16     
like you notice with the talks you had like neuroscientists you had machine learning people and kind of some     
13:22     
crossover but it wasn't like you know fundamentally     
13:27     
integrated when anyways uh this is Ali gford or allisandro     
13:33     
gford uh and you know they have the materials here so you can actually just kind of go walk through these tutorials     
13:40     
so you have the collab notebook and the GitHub repository oh here's the RNC GitHub     
13:46     
repository so this is the uh the relational neural contr control     
13:51     
GitHub repository it basically is this method for using deep neural networks to     
13:58     
analyze data uh so you have this is the paper here in     
14:03     
C cisc Discovery representational relationships across visual cortex uh theoretical     
14:11     
motivation uh they talk about relational neural control RNC generates and explores in silic functional magnetic     
14:19     
resonance imaging responses for large amounts of images it almost seems like what you're doing is you're kind of     
14:26     
maybe generating um or yeah you're generating and     
14:31     
exploring different responses for images funding controlling images that align or     
14:37     
disentangle responses across regions of interest and uh you know so it kind of     
14:45     
is sort of an AI approach to dealing with finding b function in neural data     
14:53     
it's interesting um okay so let me go back to this     
15:00     
uh there's also understanding representational similarity analysis this is Hamza     
15:07     
abdil and uh this is where they do this representational similarity     
15:13     
analysis where you're trying to link disparate types of data based on shared structures and their similarity or     
15:19     
distance matrices it is a powerful method for comparing and understanding NE representations across different     
15:26     
conditions modalities or species and so again this is another     
15:32     
tutorial and then there's brain decoding where you're doing you're applying     
15:37     
decoding models to fmri data and this is p herholtz and p bar     
15:45     
barbaron um again the tutorials are here uh and you can follow along towards     
15:54     
modeling high level movement melan sagato and this is where     
15:59     
they have this I guess this is actually um this Workshop introduces affordable     
16:07     
efficient strategies using video and pre-train vision Transformers as tools     
16:12     
to gather contextually Rich data sets and movement Foundation models is a way to combine them into joint insights so     
16:19     
I'm not familiar with the movement Foundation models are using but that'd be interesting to look into well the     
16:27     
workshop will focus on human mve movement the concepts will be broadly applicable across domains and species so     
16:34     
this is actually the GitHub repository where they have uh advancing     
16:40     
movement Neuroscience of foundation models so this is where we     
16:45     
have uh I don't know exactly again what they mean by Foundation model I guess um     
16:52     
this is where you're bringing together video and pre-trained vision Transformers to gather contextually Rich     
17:00     
data sets and then movement Foundation models will combine them into joint     
17:05     
insights we don't know how exactly so I don't see that there's a paper in     
17:12     
here uh yeah so that's okay but that's that's good that's basically the     
17:18     
education the idea there is to you know give people some educational background     
17:24     
into their Ai and I know um Morgan is kind of     
17:29     
satisfied with things but yeah you know I didn't know I was going to be taking that position or you know like like     
17:37     
yeah again I I I don't know what I thought I was gonna     
17:43     
see I guess I I like I said like it was GNA be more like CNS oh yeah well like     
17:48     
it was gonna be more computational neuroscience and     
17:54     
um yeah but this is good and um uh let     
18:01     
me I hate Lo losing things in the this this     
18:06     
chat um but there's G to be um a     
18:12     
conference that's coming up um so cutting     
18:19     
egx I mean Maine seems to have more eai yeah but um the good thing well     
18:29     
can I just say I'm I'm disappointed in Maine that it didn't have     
18:35     
virtual yeah yeah I am too I think that would have been useful for I mean you know did we not learn anything from the     
18:42     
pandemic yeah I know um I I don't understand these     
18:50     
researchers who are like I'm so glad we're getting back to the you know     
18:55     
in-person meetings that's the you know like like is would it kill you to turn on a     
19:05     
camera I don't understand like I'm not I'm not trying to take their inperson     
19:11     
experience away from them yeah um just just want to be a fly on the wall yeah     
19:18     
um uh cutting egx is is virtual is     
19:23     
online okay and um anyway I I will     
19:32     
um I will check out the     
19:37     
um I'll check out more of the educational um like like you know as     
19:44     
Jesse said like do are are Foundation models even enough anymore     
19:50     
yeah haven't we we moved on to Frontier models yeah Jesse there you go there's     
19:57     
your there's your Mar Mar H yeah yeah I like it that was trying to figure     
20:06     
out who said that I think it might have been timage F that I was quoting but yeah yeah but you could you have the     
20:11     
frontier map so but it's it is it's kind of just     
20:18     
funny that like the name even just the naming of it     
20:24     
is so like I I someone asking was it was it     
20:30     
here or was it somewhere else someone was like someone was a very legitimate question asking like well what is a     
20:36     
foundational model and that was like a year or two ago oh yeah already pass that like it it was like a very big like     
20:43     
what does it mean to be a foundational model and then there's like all the institutes like Stanford is like all     
20:50     
about foundational models and now you know Hai     
20:55     
was this this this came up because I I dropped the the new     
21:01     
Michigan foundational models Workshop or something like that right and and it was funny because like     
21:10     
I just just last night um it's like a Stanford biomedical     
21:17     
Imaging um Medical Imaging U talk it's     
21:23     
like Foundation models for 3D Medical Imaging and he starts out by like saying like I guess I'm gonna have to start     
21:31     
with um you know what is even what is even a foundational model and you know     
21:37     
has has the term lost its lost its meaning these days because everybody uses     
21:43     
it what was the original term so no one knows but yeah yeah yeah yeah yeah I I I     
21:50     
and you know as much as um well so then I I followed up because I was just like     
21:57     
so somebody using the term Frontier Model and he just like that's what Nvidia     
22:04     
used oh well we're a trillion dollar company so we're we're even bigger     
22:13     
yeah in in a way that I don't really want to get into right now kind of raises an interesting point because I'm     
22:18     
trying to I'm looking to do some things that sort of a um metascience type space but it's     
22:24     
almost like it's not just like     
22:29     
um like two two things one not just pre     
22:35     
paradigmatic but like pre-trend like like the trend doesn't even take off fully the trend doesn't     
22:42     
get fully enough to absorbed and then for there to be momentum about the de development of a term and then it's sort     
22:50     
of going away but then also like is are we     
22:56     
like in in a sort of handwavy way like is this sort     
23:02     
of indication that what what     
23:09     
what you know what the Clearing House that makes a     
23:16     
term popular is almost like how much of an influencer it is like is it is it     
23:22     
just really popular right now full stop and is that make it the defao term like     
23:27     
it like it doesn't content doesn't matter just make sure you use the language that's getting at     
23:33     
this thing that's current right now otherwise people won't understand it like like I don't know that I'm not saying it very well but almost like the     
23:39     
development of the concept is either completely detached from it or     
23:47     
just um like you     
23:53     
know it's it's sort of like hype hype hype consuming itself at the expense of     
23:59     
his that you know more than the concept yeah which is you know nitpicky     
24:05     
but scientists aren to mean to memes yeah they just don't want to admit     
24:11     
it like you would well you would put up a meme in a talk but like meing is     
24:17     
right well that that that that Foundation like like the word has become     
24:24     
yeah um some something that you have to use     
24:30     
right right yeah even if you're not actually doing that and that's that's actually something I was thinking about     
24:35     
literally this morning when I woke up which is really unpleasant I don't this is not the things I want these is not     
24:41     
the things I want to think about when I wake up it literally this it was that some there was an event um that I was     
24:48     
invited to that I'm I'm likely not going to go to for other reasons there's an event that I was invited to and there's     
24:53     
a very big name speaker at the end of it and I was like I was thinking about this topic like oh     
25:02     
um I like the speaker work you know I like what they're doing and thought the     
25:08     
only reason that I know about them at all is because of social media and I was thinking     
25:15     
like I kind of jokingly said it in the past even like a year or two or three or     
25:20     
four ago um here you know this this     
25:25     
tension of not not I don't know how to explain it     
25:32     
because it's sort of like of course as if you're if you're doing the Academia stuff especially if you're trying to do     
25:37     
uh like like a 10e track or really like you like your goal is to gain academic clout then there's yes there's sort of     
25:44     
obvious overlaps to social media related work and like making things that are consumable for social media basic to be     
25:52     
influencer you're an influencer but you're doing the academic stuff and it's sort of like     
25:58     
it's so interesting to see that conversation have changed because for for a while there was such a strong push     
26:04     
back of oh like what do you do on Instagram you should be in the lab you know and now it's sort of like whatever     
26:12     
platform you care about it's almost I think it's kind of been flipped entirely     
26:17     
to some extent that you know you should there's a there's at least some kind of     
26:23     
a pressure to put stuff in that in that space and I guess what I was thinking     
26:30     
about this morning is sort of like how many things do I only know now     
26:40     
through what to to zoom out a bit further like what is how should one     
26:45     
approach it even even in thinking about like the open source the research the research management stuff that we talked about recently I'm thinking about I'm     
26:52     
not GNA I'm not going to talk about this there for the event I don't want to I don't I don't I don't really even     
26:59     
want to be talking about it right now but I feel like it's sort of on my mind and something to kind of sort through     
27:05     
but um you know it's like what do you do what do you do with that part of it um     
27:11     
and there's many many many many many commentators on it which I don't to get into right now but it's still the     
27:16     
question of like I don't know I'm I'm still kind of absorbing the thing I keep mentioning     
27:23     
from the like first or second month of this year where it's like you know the     
27:28     
the at a clinical AI event and just talking about you know like we're     
27:33     
dependent on preprints right now and there there's sort of this the speed of     
27:40     
of things makes it even more like well you better you better shift your pitch and     
27:48     
your proposal and anything public facing to have that termin it otherwise you might be behind and so     
27:55     
it's it's it's not just like a first mover bias it's the first it's a it's an     
28:01     
I'm I'm I'm cool I mean I know the cool words bias too Mak sense yeah what what     
28:08     
what term was that referring to I mean I was talking about them at as     
28:14     
at large as a class like it could be foundational models could be anything at the time in the first event this year it     
28:20     
was I don't know basically about llms you know as part of the llm hype bubble     
28:26     
and and and and from the conference from that event that was talking about like [Music]     
28:32     
um from the same event there was a very interesting conversation that was like     
28:37     
oh we're doing this we're doing this for you know to save lives aren't we like     
28:43     
look ultimate out the return on investment here is saving more lives and well no the return on investment here     
28:49     
is is making money too saving lives get out of the way yeah so yeah I mean I'm     
28:56     
I'm kind of ring over the place but but but just sort of like I was thinking this morning and     
29:02     
maybe I'm maybe I'm I'm self-fulfilling prophecy bringing up here again but just like the weight of there is there is now     
29:09     
an aspect of I don't even know I don't even I don't I don't even think it's science communication I think it's it's     
29:16     
something Beyond communicating science to a public audience it's it's this     
29:23     
pressure like this immense and I think honestly I think it's specifically for younger generations to that they feel an     
29:30     
immense pressure to have a social media     
29:36     
component to what they're doing um     
29:44     
even I don't know I don't know I'll leave it at that we can move on to other things now I don't want to think I'm     
29:49     
talking too long about this thing yeah oh that I think that was a f aside I think that was an interesting we should     
29:54     
put a pin in that conversation because it is does speak a lot to like how people use language and how we get like     
30:03     
things to study or why we study certain things and I think with narrow AI you kind of see where you know there's a     
30:11     
bias towards like coming at it the way that you know how to come at a problem     
30:16     
instead of kind of thinking about the broader synthesis so I mean you know that's that's something um so let me share my     
30:24     
screen again uh so we were talking about this cutting EEG conference this is going to     
30:31     
be online I guess uh this coming week uh a lot of stuff     
30:38     
here uh different types of neuromodeling uh EG from the     
30:45     
ear oscillations are they real brain wave yeah brain     
30:52     
waves do we lose Y what are we we lose what     
30:59     
Jesse is he Jessie I'm sorry was     
31:05     
that are you still there yeah obviously oh yeah okay look like     
31:14     
Morgan lost his connection oh yeah dual connection sorry I lost you     
31:23     
okay uh yeah uh then there's what's it like to be a signal     
31:28     
um 50 shads of a PhD which is just a career session what Neuroscience in the     
31:35     
anthropos era um a queer look at science fiction     
31:40     
look at Neuroscience a queer and science fiction look at Neuroscience AI guided data analysis     
31:46     
hyper hope ewi accelerating scientific discovery this is     
31:52     
Publications We Trust Publications that we cannot reproduce this is all you know I I like     
31:58     
that they have a lot of different types of um sessions you know Society     
32:06     
Publications computational tools goals uh careers and and different like     
32:13     
topics so that's good some some some pretty rocking people there um johany     
32:20     
King is is now at meta okay there at the beginning     
32:28     
um yeah it's it's pretty awesome to have Stephan deer doing mobile brain     
32:33     
Imaging um and um yeah Andre M yeah and you got like     
32:42     
eif and a brain life um oh an open source Neuroscience     
32:50     
software I wonder who that's go down here cycling on the     
33:00     
yeah very yeah very catchy titles in in     
33:05     
this yeah yeah yeah anyway they the um you know but um     
33:16     
this Benedict anger you know I think these are these are nice complement to     
33:23     
kind of what was covered in this educational um session yeah educational     
33:29     
session program yeah yeah so that's uh cutting     
33:35     
egx then you had put another Link in here on uh Ros yeah R roscon roscon     
33:43     
happens so um you know it     
33:50     
um I should have checked that we could catch all the talks from that um I     
33:58     
certain my uh hope so um we're lucky here in San Francisco     
34:06     
um you know the b b basically the Gazebo team um     
34:14     
operate out of out of Bay Area and um uh     
34:21     
Kristen oh I'm blanking on her last name um anyway I think she's the Community     
34:28     
manager for for gazebo she does she also does events at     
34:35     
at noise Bridge which is the hacker space here so like you highly recommend     
34:41     
um their discourse. discourse. ross.org or     
34:48     
something like that okay anyway her her updates um Ross's um the the kind of     
34:58     
Ross Community discourse are great and um you know for not only covering what's     
35:07     
you know like features and kind of typical Community manager stuff covering a software     
35:14     
project but that you know obviously this software touches a lot of     
35:22     
research touches a lot of research Labs right so you also kind of indirectly get     
35:29     
a lot of updates about um about people working on other things and     
35:34     
um or you know applications of that software and um so it's uh still great     
35:43     
to cover and then um in brenberg vehicles um or um what do we call that     
35:51     
channel uh I guess BR yeah just um okay you know Russ     
36:00     
Salah salahov um if you don't know um he's     
36:08     
Apple's um Chief scient or chief ml AI     
36:15     
scientist even though he's uh he's Professor car Millan yeah um and     
36:23     
um yeah so it's it's good stuff to um     
36:29     
good stuff to see I I thought that the Apple paper um that got     
36:37     
it the lack of reasoning in llms was really interesting oh yeah you know they     
36:43     
they dropped that in I dropped that in math um because I think they used math     
36:48     
reasoning as their their example oh yeah yeah yeah yeah um anyway just just you     
36:57     
know like that was another one of the big big conferences that was happening kind of this past week that     
37:04     
um yeah yeah roscon is what is Ross what does Ross stand for oh a Robot Operating     
37:13     
System oh okay all right so that's good right so this is this is the probably     
37:19     
the most widely used middleware for robotics     
37:24     
yeah and you know um yeah yeah you and     
37:34     
is again a part of a lot of them here's another here's another     
37:40     
buzzword don't want to trigger anybody uh um for digital twin stuff oh yeah the     
37:49     
um you know certainly human brain projects started started this with using     
37:56     
you know Ross robots real life Ross robots but in simulations in gazebo     
38:03     
right yeah so so that you could you know     
38:08     
like this was their attempt well not just their attempt but like it was a     
38:14     
practical way of um having the kind of best sin toore     
38:20     
transfer right right so you know that you were you were actually using the     
38:27     
same software that you were going to use in um in your real life     
38:32     
robots um yeah and then this this     
38:38     
other this other talk is was was interesting or sorry you're still     
38:44     
looking at R um uh um yeah so I I haven't I haven't gone     
38:52     
through you know there's only certain aspects I mean you know it's like it's robotics right so there's there's a lot     
38:57     
of you know kind of um very robotic     
39:04     
specific topics here you know um but I I think there's also just a lot of overlap     
39:12     
in terms of agent planning and agent you know right so it's like you know in fact     
39:21     
there's there's there's a lot of overlap between say roscom and um like the     
39:28     
Alberta plan for I forget what they call it very     
39:33     
Alberta plan for AI or whatever they you know I feel like that should say that     
39:40     
the acronym should be Amy or something like that but I'm not getting it anyway but you know what I'm talking     
39:47     
about right like um yeah um and then the     
39:53     
yeah one one of the last videos that I dropped was about was someone talking     
39:58     
about finite allet modeling for for software bugs which is where it starts to get a     
40:05     
little yeah so I guess YouTube if if the person's actually speaking it doesn't     
40:12     
pass on the live     
40:18     
yeah but but you know I like I mean one I've just been covering a lot of fine     
40:25     
and element stuff or related stuff currently um but uh this is where     
40:32     
robotics becomes more biological are you know biologically relevant right because     
40:39     
this is you know it's once you once you can deal with soft body     
40:46     
simulations you know it now gets very kind of biomic right     
40:58     
yeah yeah definitely Soft Robotics yeah opens up a lot of     
41:03     
doors yeah yeah and then then you have that that like real overlap with kind of     
41:09     
you know yeah animal animal movement kind of     
41:14     
work and things like that right yeah yeah yeah uh back roscon yeah it's a lot of     
41:23     
robotic stuff um like just stuff various things uh you     
41:29     
know the tutorials talking about control handheld mobile mapping systems tool path     
41:37     
planning manipulation uh I guess U manual     
41:43     
manipulation in robots birds of a feather networking sessions and building robots with open     
41:50     
source software that's that's her name that's Katherine Scott there introduction to Ross and building robots     
41:56     
Okay intrinsic yeah yeah yeah sorry I I think I said Kristen it's cther Scott     
42:04     
Scott okay yeah yeah that's good um that's that'll     
42:10     
be uh it's it's interesting um yeah so yeah I had another thing I want     
42:18     
another conference I wanted to talk about too so it's like all these conferences happening uh but they're all     
42:24     
very good uh have a lot of interesting topics and a lot of things to kind of follow up     
42:30     
on um so this one is uh colas and so this is the conference here     
42:37     
this is the third conference on lifelong learning agents that was actually I think in maybe was either brenberg     
42:44     
vehicles or in like Dev AI somewhere like that yeah brenberg okay brenberg     
42:51     
okay so this is this was a in Italy this was where they kind of at a lot of stuff     
42:57     
on lifelong learning and continual learning so you know uh this is where     
43:03     
you have uh you know this field that includes like meta learning multitask     
43:09     
learning transfer learning curriculum learning domain adaptation VI shot     
43:15     
learning out of distribution generalization online and active learning and open end of Lear so it's     
43:22     
like this whole collection of things and people are trying to put these things     
43:29     
into practice so they had a couple of tracks here conference workshop and journal     
43:34     
tracks look at the conference track all sorts of     
43:39     
there's uh accepted papers here oral presentations you had memory head for     
43:46     
pre-trained backbones and continual learning Subspace configurable     
43:52     
networks diffusion augmented agents um     
43:57     
categories the classifiers name only continual learning for by exploring the     
44:03     
web um chunking continual learning is not just about distribution     
44:09     
shift uh subal distillation then we had some     
44:14     
posters uh priors for object Centric learning mased Auto encoders or     
44:20     
efficient continual Federated Learners so there's a lot of jargon in here but there you know just know that like in     
44:28     
continual learning there are a lot of things that sort of play into this     
44:33     
aspect of learning like across domains or learning as the agent behaves freely     
44:41     
or as it it kind of goes across that's lifespan you know just kind of doing this sort of naturalistic     
44:49     
Behavior Uh learning to learn without forgetting using attention uh on the limitation experience Replay for GNN in     
44:57     
continual learning so this is uh replay of I guess experience and     
45:03     
then graph Minal networks uh let's see prototype based     
45:09     
novel glass Discovery and detection maintaining plasticity and continual learning by regenerative     
45:17     
regularization continual learning of diffusion models that generative     
45:23     
distillation um state update of regression     
45:29     
trees let see yeah all sorts of different topics     
45:36     
your rehearsal policies and rehearsal free continual learning with pre-train models so there     
45:43     
are all sorts of ways that people kind of approach these different problems um I also     
45:54     
have so yeah if you go here I have a couple screenshots that I     
46:01     
took of the YouTube pres so poas is on YouTube and um they have their own     
46:07     
channel and there are a couple of main talks keynote talks this one was from J     
46:15     
mcleland uh this was efficient cumulative and continual learning in natural and artificial systems this is     
46:22     
where again where you have this cumulative learning cross contexts in continual learning and efficient     
46:28     
learning and this kind of talks also about natural systems of making that     
46:34     
connection um this one was uh this was the theoretical advances and continual     
46:41     
learning video from the YouTube channel and this is phenomenology of catastrophic forgetting so this is uh     
46:49     
again you know test similarity task recurrence and overparameterization it     
46:55     
says chapter two which I'm assuming is maybe part of some way that they organize the     
47:03     
conference um but yeah it looks kind of interesting given what we're interested in     
47:10     
here um this is the YouTube channel here where they they have uh all sorts of you     
47:17     
know talks from the this year's conference a deep dive in in context     
47:23     
learning had a heterogenity analysis for out of distri distribution     
47:28     
generalization um how to make machines at adapt quickly reinforcement learning at the hypers scale so there's a lot of     
47:36     
a lot of stuff here that goes kind of beyond the just the term continual     
47:42     
learning so I think lifelong learning agents it's it's a pretty good conference um again it's in person in     
47:51     
Italy but it's they have things on YouTube here um and again yeah uh     
47:58     
doia precup towards a general blueprint for continual reinforcement learning and     
48:04     
how to make machines at adap quickly so that's kind of where they are with that and it's very much you know     
48:11     
has this sort of AI flavor involves a lot of reinforcement learning a lot of     
48:16     
inovative reinforcement learning and a lot of other topics that are really important for     
48:23     
this um yeah go ahead well just gonna say yeah hopefully Maine     
48:31     
will drop videos in a couple days okay is that promise or is that just I don't     
48:38     
know if not then they mean to be ashamed yeah because again like like honestly     
48:46     
you know if if you're putting together a conference that size like you should be     
48:51     
able to turn on a camera yeah     
48:58     
yeah just turn the camera on you know and and you know they they did it for     
49:04     
the lifelong learning right yeah big big names there     
49:11     
yeah all right so I think there's a lot of interesting stuff on uh these different     
49:17     
conferences um and you know I think there's a lot to follow up on especially     
49:23     
with respect to some of the stuff we're doing um you know we have our sort of     
49:29     
our approach to nuro AI it's not really been I mean we've kind of described it     
49:34     
in terms of Developmental Ai and some of these things but I think definitely you     
49:40     
know we could uh learn some things from the videos here     
49:45     
and I'd like to see well maybe we'll talk more about that in coming     
49:50     
meetings yeah I I saw um is it spelly     
49:58     
uh yeah I think so refering to yeah like she's one of the Keynotes at um     
50:06     
neurops okay like you know I I just I'm     
50:12     
always glad or you know and like yeah like that that cognitive     
50:20     
development is being considered in all of these you know AI conferences     
50:30     
yeah but I I didn't I didn't see so much of that in the the     
50:37     
cola no I didn't really see it     
50:45     
um uh what we didn't see well we did see EMB bodyman I can't remember but not     
50:51     
really I mean I guess it depends on what you mean by embodiment but she has some sort of spal cognition     
50:58     
stuff uh a lot of stuff talking about like out of distribution stuff but not     
51:03     
in an embodied context which would be you know I don't know like shifting     
51:08     
bodies or shifting relations to the environment or whatever be interesting yeah yeah yeah I mean this is where it     
51:18     
like I do feel like you know you're seeing material this is a nice example of     
51:24     
seeing material um kind of um spread across     
51:30     
three serious conferences yeah you know but that kind of actually needs to be be     
51:37     
put together right yeah it's you know because you got the the robotics people     
51:42     
who are you know the ones actually building stuff right     
51:48     
yeah but you know the the yeah so like like you put put all of     
51:55     
those three together and then you maybe get something that's more like bio     
52:06     
AI yeah I think so and so like uh you know that would be like continual     
52:12     
learning with the sort of connection of Neuroscience data with the connection of     
52:18     
Robotics yeah yeah but like fully embodied yeah you and and again like you     
52:26     
know know in kind of the in some people's kind of neural theories like where movement and things     
52:34     
like that were like a let's not say Foundation models but     
52:43     
foundational domains where the nervous system learned to do things and then     
52:50     
other things got mapped to that or you know like like again like how how cample     
52:57     
cognitive Maps become utilized for other purposes     
53:05     
yeah yeah I think that's that's an interesting uh way to think about     
53:12     
it yeah um yeah uh I don't know if Jesse had     
53:19     
anything to say about that or I mean i' I've brought updates that I     
53:25     
can say about this week and the meeting we did have yeah yeah so why don't we go move     
53:32     
to that then okay so go ahead sure     
53:41     
um I'll start with the meeting we were it was it was sort of one of those     
53:49     
um the is a Thursday meeting and it was following up on a     
53:56     
think Robins P robins take on B     
54:01     
bergson's um me like where is memory stored kind of stuff we I I actually     
54:08     
wasn't um apologies for you not being there I was in commute when it started     
54:15     
so I didn't get to record it I didn't even know I wasn't really sure who who was going to be there for a little bit     
54:22     
yeah um but we kind of very we got I think I don't know somewhere     
54:29     
around like page 18 16 but like I think halfway through some of the paper in     
54:34     
terms of it's like actual content we before the Alternatives part but basically was a nice discussion I a lot     
54:41     
of a lot of side questions about um contexture different people like I'm not super familiar with the debate uh     
54:50     
like well someone I guess I'll put it this way there's a lot of dob Tales into like consciousness and and other things     
54:57     
like that and I'm I guess I guess I guess the most professional and safest way for me to say it is like I'm pretty     
55:03     
agnostic about a lot of a lot of it and I don't have a lot of I don't have a lot of useful things to say so I'm mostly     
55:10     
trying to just listen and understand um in that space But I I do like the     
55:16     
approach of looking at it through the lens of memory and how memory works and I think that's why we're doing the paper     
55:21     
but also like I think that's probably one of my preferred lenses of like looking at those spaces so um I mean I     
55:31     
feel more can can can add in if you wants to say stuff I'll just say     
55:37     
um um yeah amand basically shared the     
55:42     
discussion and we one one of the more interesting points was sort of     
55:50     
um what memory is distributed you know kind of this hum analogy of putting being able to put things back together     
55:56     
again or not I think Mor get is something kind of funny like not just Humpty D being put back together but like having burn damage and other things     
56:03     
like that um um and then also the concept of memory as or perception as     
56:10     
memory and as as once something is perceived it's already in the state of     
56:17     
um being a memory and and what like what does that imply and how how is it done I     
56:23     
also mentioned which I I I didn't really know how to relate to when I got back I     
56:29     
remember this thing I saw I posted it I don't I think it's in futures um we     
56:35     
didn't we did not talk about this I just sort of awkwardly mentioned it but I'm curious if you have any connections to     
56:41     
it but in the cognition Futures bit Channel I posted something from Tom fros I think it was from     
56:46     
LinkedIn and it was basically looking at the huto and M's book and he said it's     
56:53     
fascinating indeed that the first step of sensing is to strip away the physical qualities of incoming causal change in     
56:58     
favor of making a pattern and I'm I'm trying to sort     
57:04     
out if there's any ties between that and um what we were just saying about memory     
57:10     
and perception and perception is memory and there were also a lot of discussion about like obviously GI gibon     
57:16     
information and you know like instead of direct and I said some     
57:22     
one of the discussions was like oh instead of direct perception is it is it is it Direct memory then and what what does that mean like like like stuff like     
57:30     
that we I don't think I don't think we got to like the complete substance of what the author's point was yet or     
57:39     
maybe I guess I don't know I don't know what the Alternatives if if it's the authors     
57:44     
presenting their own alternative or going to other Alternatives that it could be I don't I don't know yet we didn't really that's where we sto     
57:50     
basically so okay well yeah that's good uh graphical review yeah     
57:58     
yeah I saw that yeah yeah oh no yeah     
58:03     
just that um it was uh there's nice nice references in the     
58:11     
paper um so it was nice to follow up on those and and check the um I I think     
58:20     
they were drawing from this learning um learn meem     
58:27     
um conference 2018 and it looks like it's a I don't     
58:33     
know if it's one of those conferences that's scheduled when it's scheduled or if it's scheduled every five years but     
58:38     
there's a learn M 2023 that was interesting to to also     
58:45     
follow up on um and yeah like     
58:52     
like there'll be some other ones to there     
58:58     
I I I I gasped audibly I think you did     
59:03     
because You' I once again was reminded of a conference that I love     
59:09     
dearly that has not been regularly scheduled at least for this year and I'm hyping it up just for my     
59:16     
own you know fun it's we robot so I looked at we robot and I like oh V robot     
59:21     
2025 does it exist yet and it does so I'm extremely enthus is a completely     
59:27     
unrelated topic good that we robot will happen next     
59:35     
year um I think it's gonna be in Canada um yeah yeah so all right more     
59:43     
that later I'm sorry I was just I've been hoping for that for months so you     
59:49     
know rough for me anyway um yeah     
59:54     
um it's paper I'm looking forward to continue it there and I like I like the     
1:00:00     
sort of physical memory I don't mean to interrupt I think you were saying more things Moran I'm sorry no no no it's     
1:00:06     
it's you know um I I was distracted     
1:00:12     
during our meeting because I was taking my daughter to acrobatics um but     
1:00:19     
uh it was nice to kind of cover some of that memory literature and and you know     
1:00:26     
and see some some talks from um you know big names um that you know I I'd like     
1:00:34     
the presentations that they give because they bring up the kind of if you will     
1:00:41     
the kind of problematic evidence in terms of having     
1:00:47     
a nice having a theory that you can kind of state clearly you know that that you     
1:00:54     
can it's hard to have Theory that's that's easily statable that can     
1:01:00     
explain this this you know great great mass of     
1:01:08     
phenomena yeah and you know and just how important it is to get into the the kind     
1:01:16     
of the particular phenomena of learning in memory     
1:01:22     
um and and like I said at the meaning like that you know languages of the     
1:01:28     
brain which is Bri's book that is also referen you know he does a certain     
1:01:36     
amount of like you know I hope he likes the comparison um but like like Dennis     
1:01:42     
Noble that like like he gathers you know evidence that doesn't     
1:01:48     
fit well with with existing you know theories and metaphors     
1:01:55     
if you will and and you know it definitely has some     
1:02:01     
because again like this was this own the own kind     
1:02:07     
of you know wet lab his own experiments if you will um     
1:02:14     
that that speak to kind of the distributed nature of of     
1:02:20     
um the distributed nature of memory or you know engr stuff     
1:02:26     
and again it's it's just always fun when you get to meet somebody who's like yeah I was talking with     
1:02:37     
Lashley um yeah it's good it's good to     
1:02:42     
cover yeah yeah we'll have to talk more about that     
1:02:48     
um in future meetings I guess um but yeah I'm not I'm not like uh     
1:02:57     
like on The Cutting Edge of these sort of the problematic evidence so what's an     
1:03:02     
example of that um in learning and memory well again this this paper     
1:03:10     
doesn't doesn't cover that but um uh     
1:03:16     
um you know like this paper is very very high level you know like in its     
1:03:22     
descriptions and things like that um but um you know     
1:03:28     
certainly the um the kinds of things that that that um Carl you know was as a     
1:03:37     
brain surgeon um was dealing with again like     
1:03:43     
both people who had either they had accidents or they had     
1:03:51     
um tumors that needed to be removed and things like that right so and     
1:03:57     
and is just invariably you know to to get into the brain you have to cause     
1:04:04     
damage to the brain right yeah um     
1:04:12     
and so so we we also brought up Migel Christ and and     
1:04:20     
um I thought it was perhaps relevant Mark SS as well just as in terms of     
1:04:26     
people who um had a lot of theories about the brain     
1:04:33     
that I I would say were kind of derived from these brain damage     
1:04:40     
cases right so it was actually got to I think maybe Mark SS was recently on     
1:04:46     
machine learning Street talk I'm trying to think why I got to see him speak     
1:04:54     
recently but um he he got into research because his     
1:05:02     
brother had a fall as a kid and he was he wanted to understand     
1:05:10     
why the after that fall his brother was never the same     
1:05:16     
person yeah um and yeah so so there's there's some of     
1:05:24     
that but then there's some of the the you know how does how does function     
1:05:30     
return um you you you talk about localization of function and then you remove that     
1:05:40     
localized area right and then some other part of the brain starts being active while you     
1:05:48     
do that task right would be kind of one of one of Carl's examples     
1:05:56     
um now you know again it's it's     
1:06:01     
it's um yeah so I'm not doing great Justice and you know but was was     
1:06:09     
recommending um uh I forget his I want I     
1:06:15     
don't want to do too much damage to his name but     
1:06:22     
um uh     
1:06:29     
sorry yeah um Sharon ran     
1:06:34     
gath has the book so he runs the dynamic memory Lab at Davis and has a recent     
1:06:44     
book and is one of the speakers at 20 at     
1:06:49     
learn M 2023 um and again like     
1:06:56     
probably would have some some better some better examples as well as just yeah the D diving into some of those     
1:07:04     
those say Keynotes from learn man yeah     
1:07:10     
yeah so I think I get the idea it's like a lot of learning in memory was built on     
1:07:16     
like like hm or other clinical populations where you have brain damage     
1:07:21     
you get this localization of function deficit and then you study that and then     
1:07:26     
you know it's like sometimes you recover things because the brain can use other     
1:07:32     
places to do the same thing and it's kind of confusing things yeah yeah I     
1:07:39     
mean some of that right I mean hm would be maybe a better example of like like the circuitry involved in memory right     
1:07:46     
right and like disrupting that you know it like where he had this he had     
1:07:52     
shortterm but not longterm right yeah like very sure but but it was reset     
1:07:59     
yeah you know and but yeah you know like like there     
1:08:06     
are there there's a lot of different things I mean I I think about like the you know     
1:08:14     
the the Sarah Beller work that you covered um a couple weeks ago yeah right     
1:08:21     
just like like you know the the     
1:08:27     
there's you you only get data from the places that you're collecting it from right you know and and certainly you     
1:08:36     
know one of the things Carl would always say is just like what have you guys learned from FM that we didn't you know     
1:08:42     
that we didn't figure out as as brain surgeons in the 40s or     
1:08:48     
50s and and it's like well one you know we don't have to cut the skull open     
1:08:56     
right and two you know certainly with FM so it's like you have this benefit that     
1:09:02     
you can you you sort of can be at these virtual electrodes in in all all brain     
1:09:10     
areas right     
1:09:17     
um you know so so much of that cbella work was was um was e right yeah     
1:09:25     
again it's it it um you know this is why kind of like the statistical analysis of     
1:09:33     
that data has become its own you know I'm biased as being one of those     
1:09:39     
trainees but like you know that that that's why it became its own area     
1:09:44     
because trying to pull out those statistical networks became it became a a new way of     
1:09:53     
of doing yeah kind of brain brain science     
1:10:03     
right and and so you you're already seeing kind of like so much more of that     
1:10:09     
distributed architecture right yeah and and I think we'll see that more     
1:10:16     
and more in terms of you know the integration of kind of the the the rest     
1:10:24     
what what are called the resting networks but that are obviously very Dynamic right so it it's like there's     
1:10:32     
this this you know you you'll start to see things that are much more like     
1:10:37     
um Steve Brunton kind of analyses where dynamical     
1:10:42     
systems become an important component of your of your     
1:10:48     
statistical modeling all right yeah so I think I I get the idea here yeah it's     
1:10:54     
interesting so um definitely you know we kind of uh a lot of times we assume we know a     
1:11:01     
lot about things and it's just like kind of an artifact of what we've been able to collect we talked about that with     
1:11:08     
model organisms you have model organisms where you understand things but then it     
1:11:14     
doesn't necessarily generalize across life or you know we we have like medical     
1:11:20     
models you know sometimes very far removed like say for example using celegans to understand human health and     
1:11:28     
there's some analogies there but then you know sometimes they don't work very     
1:11:33     
well in Translation so it's just kind of an artifact of what we can study what     
1:11:39     
data we can collect and things like that so yeah very good set of conversations     
1:11:49     
um I would like to talk about um let's see yeah yeah I'll get     
1:11:55     
into this one um so this is a set of papers um     
1:12:01     
where talk about this idea of morof functionality and anatomy and so I'm     
1:12:08     
going to go through a couple papers here and we'll talk about them and see where they kind of fit into     
1:12:15     
things um this is a paper from uh artifici aif artificial life     
1:12:22     
journal and this is called emotion is morof     
1:12:28     
functionality uh Spanish authors um from the center for Automation and     
1:12:33     
Robotics at the univers uh Technical University of Madrid so     
1:12:40     
um well we'll go through the abstract we'll see what they're getting at when they say emotion is morphal     
1:12:47     
functionality the abstract reads we argue for a morphofunctional approach to emotion     
1:12:53     
modeling that can also Aid the design of adaptive embodied systems so they're     
1:12:59     
interested in Emotion modeling which is you know being able to replicate emotions or to identify them uh then     
1:13:06     
they argue for this moral functional approach by morphal functionality we     
1:13:12     
target the online change in both structure and function of a system so this is where this is this continual     
1:13:19     
change across like time you know in both structure and function     
1:13:25     
and related to the notion of physiology and emotion in animals apart from the biological     
1:13:31     
intuition that emotions serve the function of preparing the body so this is like you know where you     
1:13:38     
go through emotions to do things so it's like if you know like a fight ORF flight response for example would be an     
1:13:45     
emotional preparation or you know um anxiety would     
1:13:50     
be an emotional preparation or something like that we investigate control     
1:13:55     
requirements that any morphofunctional autonomous system must     
1:14:01     
face we argue that changes in morphology modifi the Dynamics of the system this     
1:14:06     
forming a variable structure system or VSS we introduce some of the techniques     
1:14:12     
of control theory to deal with VSS and derive a two-fold hypothesis so     
1:14:19     
this is where they're kind of using control theory to deal with this variable structure system and then they     
1:14:25     
have a twofold hypothesis so the first one is the loose coupling between two control systems in charge of action and     
1:14:32     
action Readiness so there's this control system for Action control system for     
1:14:38     
Action Readiness so you have to get ready for an action and then you have the execution of the action itself and     
1:14:44     
there's this loose coupling so Readiness means that you get the state of the system ready for the actual action so it     
1:14:51     
could be with thinking about how you know a homeost static system might     
1:14:56     
prepare for some Behavior it might you know sort of um Prime the system for the     
1:15:03     
behavior whereas if that those conditions aren't met if the system's out of uh homeostasis then that action     
1:15:11     
can't occur second the formation of pattern meta     
1:15:16     
control emotional phenomena can be seen as an emergent from this control setup     
1:15:21     
so this is again the formation of pattern meta control which the talk about in the     
1:15:28     
paper uh I think we had a comment in the [Music] chat it was unrelated sorry it was later     
1:15:37     
we'll talk about it after um okay so this article deals with two     
1:15:44     
research areas that have gained increasing relevance over the last decade morphological computation which     
1:15:50     
we've talked about is like you know when you have an embodied system and you it maybe moves or it changes its shape or     
1:15:58     
has a certain shape and it's doing something in Behavior you can uh characterize that as a computation and     
1:16:05     
emotional robotics which of course is where you know has links to aective Computing and uh you know robots     
1:16:13     
expressing emotions and so we just talked about how you know we can have emotional states     
1:16:20     
that set up other behaviors or prepare the body forther Behavior so this is     
1:16:27     
where this is kind of connecting both could be considered to belong to the wider Paradigm of embodied     
1:16:34     
robotics yet they seem to have very few themes in common and there has been practically no direct link between the     
1:16:40     
findings of the methods in the two areas embodiment has become a central issue in robotics morphological     
1:16:47     
computation refers to the information theoretical implications of embodiment okay so this is measuring these embodied     
1:16:56     
behaviors embodied aspects of behavior there is evidence that morphology structures information flows so this is     
1:17:03     
where they're making a statement about information flows being structured by     
1:17:09     
the morphology so if you have a a c a spherical body or a spherical morphology     
1:17:16     
that you're going to have a different type of informational flow available to you than if you have a square body or     
1:17:24     
some as symmetric body and so you know we could argue like why we have     
1:17:31     
asymmetric bodies I mean you know there's some organisms that are much more symmetrical than we are uh and     
1:17:37     
there are organisms that are less symmetrical than we are and what is the informational consequence of it and that     
1:17:44     
largely has to do with behavior so how is the organism acquiring information you could even look at cells     
1:17:51     
where you have this sort of they have different morphologies and a ask why do     
1:17:56     
they have different morphologies is it for you know purposes of movement of course there's um you     
1:18:04     
know sort of a mechanical aspect to that but there's also maybe an informational     
1:18:13     
aspect um as a consequence the morphology will allow us to reduce the     
1:18:19     
complex task of emulating nonlinear computation to the much simpler task to     
1:18:25     
adapt some linear parameters for an additional readout that's citation     
1:18:30     
18 uh which is I get to this     
1:18:41     
thing uh this is this uh Houser at all where it's a theoretical Foundation or     
1:18:46     
morphological computation with compliant bodies is in biological cybernetics     
1:18:57     
okay so they're kind of going into this idea of morphofunctional machines or     
1:19:03     
devices that can change their functionality not only by a changeing neural control but by modifying their     
1:19:08     
morphology so this is where we're not just you know observing changes within the nervous system but there's     
1:19:15     
morphological change as well so you know maybe stiffening your body or uh     
1:19:21     
relaxing your body those are things that can play a role in Behavior just as much     
1:19:27     
as neural control of course there's a connection between neural control and body modification or morphological     
1:19:33     
modification so this is you know uh but they're at different     
1:19:38     
levels uh morphofunctional designs May therefore be inspired by how emotion organizes adaptive responses and     
1:19:45     
biological agents uh in Emotion Theory there's this idea     
1:19:53     
that motion is about action Readiness you go through an emotion as largely to     
1:19:58     
experience a change in Readiness and do like patterns of physiological     
1:20:04     
activation uh as Freeman argues the behaviors that are directed through interactions with the world towards the     
1:20:10     
future state of an organism predictively require adaptations of the body to support the intentional motor     
1:20:17     
activity okay uh so a morphofunctional machine this needs to somehow predict     
1:20:22     
future engagements of the world and control morphofunctional preparation to     
1:20:28     
favor certain classes of behavior so this is where you get this emergent aspect uh where emotions emerge from the     
1:20:35     
control set um and so emotion research has     
1:20:42     
revolved around the tension between emotion and cognition often seen as two competing behavioral routes so this is     
1:20:49     
where you get this ra this rational set of cognitive processes and then you have     
1:20:54     
the these other emotional processes which are less than optimal Behavior     
1:20:59     
generation mechanisms this is kind of the classic idea in Emotion research we     
1:21:05     
challenge this View and suggest a control challenge between bodily disposition and activity performance so     
1:21:13     
act adaptive behavior is not just performing actions upon the environment it also involves tuning the body so it     
1:21:19     
is best prepared and so this these are forms of concurrent control     
1:21:25     
and when you integrate those and depending on the degree to which you integrate those it turns into the sort     
1:21:32     
of strategy for a cognitive agent so let's see if we can find some     
1:21:38     
figures in here um actually they have a good table here function effects     
1:21:43     
underlying the fight ORF flight response in animals so this is where you have different physiological effects they     
1:21:50     
have a functional role you biological examples of this phys ological effect and then you have analoges and robots so     
1:21:58     
every physiological effect uh has a functional role you know this is for the fight or     
1:22:04     
flight response biological examples and then robotic     
1:22:14     
analogs so this is like their dynamical systems approach um they make the point that     
1:22:22     
different morphological configurations make get rise to different phase diagrams so you have this phase diagram     
1:22:28     
on the left which is this um you know this kind of phase diagram here and then     
1:22:34     
the uh attractor diagram on the right so there are different types of bifurcations and attractor basins and     
1:22:42     
things that you can you know gain from these different morphological     
1:22:49     
configurations and uh you know and its interaction with cognition     
1:22:58     
so this is where you have this combined stat space set of stat space trajectories for a system with variable     
1:23:04     
structure for each operating region the Dynamics is defined by a different phase     
1:23:10     
portrait in this case that is EAS easily visualizable because of the existence of     
1:23:15     
a simple switching surface you get these uh sort of I guess this would be     
1:23:20     
considered the hybrid system where you have the emotions preparing the uh body     
1:23:27     
for action and so you have this sort of composite phas space where you have some     
1:23:35     
sort of wi forcation and you have this switching the switch surface where you     
1:23:42     
see the outcome um this so this shows the     
1:23:47     
transitions uh you have this transition between the bifurcation State and the     
1:23:52     
attractor and so you have this reversible transition between two different morphological configurations     
1:23:59     
one representing the bifurcation the other representing the uh uh attractor     
1:24:06     
Basin so this is based on a finite State automaton of two states that correspond     
1:24:11     
to two states of morphological configuration each one characterized by a different dynamical Behavior     
1:24:18     
transitions imply a morphal functional change and hence a behavioral change     
1:24:25     
so this is and then this is the this uh tasks involved in controlling a car so     
1:24:31     
they kind of use the vehicle um analogy they have driver control wheel directions motor     
1:24:38     
revolutions and brakes so the the driver controls these mechanical features of     
1:24:44     
the car that uh result in the behavior of the car changing uh this you know you have     
1:24:52     
driver control it goes to the different types of functional changes or the     
1:24:58     
mechanisms that cause functional changes but also you can have this feedback for Motor Performance you have things like     
1:25:06     
gear changes and then you have the current state which is the current GE and that feeds back to some of these     
1:25:13     
functional uh aspects so basically if the driver is controlling the car     
1:25:20     
they're changing gears they're in in one you know any one gear at any one time time then they're sending these commands     
1:25:27     
to sort of modify the behavior of the car but the behavior of the car is     
1:25:33     
dependent upon the current state of the gear and so gear changes are feedback     
1:25:39     
for Motor Performance and this entire sort of state of the car feeds back to     
1:25:45     
driver control so the driver can change things if they see things are not under     
1:25:51     
their control so this is kind of showing me control the link Control Systems here     
1:25:57     
you have a control system for sort of the morphology of the car and then the     
1:26:02     
brains of the car which is a driver that's going to make these     
1:26:08     
changes and so this is this figure five is a block diagram of a moral functional     
1:26:14     
robot controller the control device or CD which is this area in Gray in the middle operates in a robot using several     
1:26:22     
patterns of morphological configuration ation which is A1 through a n managed by     
1:26:28     
a homeostatic switching element hsse which is on the left and the morphal     
1:26:34     
functional controller MC which is down here so you have this uh control fun you     
1:26:40     
have this function you have this feedback function XT and then it goes into this uh control device where you     
1:26:48     
have the morphofunctional controller the homeostatic switching element and then you have these different morphological     
1:26:55     
configurations homeostatic switching element switches to a different configuration as     
1:27:03     
needed uh then this is the cognitive architecture representing the comp components required for the emergence of     
1:27:10     
a motion and their reciprocal causal connection so here you have a morphofunctional loop at the top which     
1:27:18     
can in includes morphal functional control you have this control system     
1:27:23     
below which is where you have cognitive control homeostatic control mediated by     
1:27:28     
arousal you have the body Dynamics you have sensing and action flows and you     
1:27:35     
have this relationship in the body Dynamics between morphological parameters cons system variables and     
1:27:42     
taken together the morphofunctional loop and the control State output it out a     
1:27:48     
control state that is for the the current time so basically you have this control M that feeds up into this     
1:27:55     
morphofunctional Loop that you know so you have this sort of the brains of the system interacting with the morphology     
1:28:03     
and there there are a number of feedback loops here and it outputs a current state of the     
1:28:09     
system so remember I said that there were these coupled Control Systems that's what they were getting at that     
1:28:16     
diagram so that in their conclusion uh they say by looking at the     
1:28:21     
phenomena of emotion we can grasp the chall challenge of controlling activity and controlling moral functionality     
1:28:28     
motor control produces different forms of movement towards executing goal oriented actions normally through a     
1:28:34     
sequencing of patterns that use some form of feedback mechanisms for control or for functional control a slower time     
1:28:42     
scale process that has consequences for Behavior over long periods of time like     
1:28:47     
minutes and biological systems provide this system with timely action readiness     
1:28:54     
so you have this motor control aspect where you know we can move our arms to     
1:28:59     
targets and it's usually something that operates on the scale of seconds and     
1:29:05     
then you have this morof functional control which is actually sort of uh     
1:29:10     
something that might occur at the scale of minutes so they break this down to two time scales like sort of seconds and     
1:29:17     
minutes so motor control is tightly regulated in terms of a closed feedback loop you have this imperative to match a     
1:29:24     
goal or to execute goal oriented actions which are immediate and result in     
1:29:31     
movements that are sometimes automatic and morha functional control is different it's a slower time scale     
1:29:39     
process it has this sort of these these sort of man mediates these hazes of     
1:29:45     
behavior and that's that's where we have this distinction uh control strategies for     
1:29:52     
variable structure systems support the hypothesis that emotions emerges pattern-based mechanisms of     
1:29:59     
system meta control that select from a finite evolutionarily selected set of control organizations so now we're     
1:30:06     
moving from this morphofunctional control to these control strategies that are these meta control aspects of the     
1:30:14     
motor control so there's this motor control which is you know at one level more for functional control and there's     
1:30:22     
a systematic control which is uh basically uh there there are     
1:30:28     
different control organizations available to you and you select from those and I guess they're     
1:30:33     
making the analogy between that and emotional states furthermore action generation and     
1:30:40     
preparation for Action appear as two Loosely coupled control tasks so you're     
1:30:45     
actually you know generating actions through motor control and you're     
1:30:50     
preparing for actions through this morphal functional control at least you're setting up the context for these     
1:30:56     
actions so that's where you're talking about the preparation so if I'm behaving     
1:31:02     
like if I'm driving in a very distracted state or I'm driving in a very angry     
1:31:07     
state or I'm driving in a neutral State those are you know those different emotional states will affect motor     
1:31:14     
control and the and the U the feedback loops in that set of actions during that     
1:31:21     
that emotional state when I change my my emotional state it changes my motor     
1:31:26     
control it changes the sort of the systems meta control strategy that I'm     
1:31:33     
using um and so that actually they cited citation 40 for that and this is this P     
1:31:39     
paper here a model of emotion is pattern met control this was actually a Bea 2011     
1:31:45     
so this is um kind of one I guess it's from their own work and their own sort     
1:31:52     
of uh their own kind of way of thinking about this so that's uh that paper I think     
1:31:59     
that was a good paper for looking at kind of this idea of having multiple     
1:32:04     
control systems that are sort of neural based sort of you know um thinking cross     
1:32:12     
Evolution and things like that this is another paper bringing anatomical information in neuronal     
1:32:19     
network models so this is um a number of authors     
1:32:24     
uh goulas H tag they've done a lot of things with um building connectomes that     
1:32:30     
are expand and things like that so uh basically they're interested in taking     
1:32:35     
neuron neuronal Network models bringing anatomical information into them and     
1:32:40     
then seeing what their utility is so a lot of European collaborators in this     
1:32:48     
paper um the abstract reads for constructing neuronal Network models     
1:32:53     
computational neuroscientists have access to wide- ranging anatomical data that nevertheless tend to cover only a     
1:33:00     
fraction of the parameters to be determined so you know we have all sorts of     
1:33:05     
connectomes um we have you know complete connectomes of cgans we have good almost complete     
1:33:12     
connect Downs of fruit flies we have you know uh neuroimaging deriv connect Els     
1:33:20     
and so forth and they give you anatomical data me meaning that they're not these     
1:33:25     
layered networks you know like we have with deep learning or these randomized     
1:33:32     
networks or you know like what we have in a reservoir Computing they're actually like there's a meaning to the     
1:33:39     
anatomy and there's a map from the anatomy to the     
1:33:45     
function so this you know so this is finding and interpreting the most     
1:33:50     
relevant data estimating missing values and combining the data and estimates     
1:33:55     
from various sources into a coherent go PO is a daunting task with this chapter     
1:34:02     
we aim to provide guidance to modelers by describing the main types of anatomical data that may be useful for     
1:34:08     
informing theal Network models we further discuss aspects of the underlying experimental     
1:34:15     
techniques relevant to the interpretation of the data L particularly comprehensive data sets and     
1:34:22     
describe methods for filling in and the gaps in the experimental data such methods of predictive connectomics     
1:34:28     
estimate connectivity where the data are lacking based on statistical relationships with known     
1:34:34     
quantities so what they're trying to do in this chapter is kind of give an idea of how to fill in the gaps in these     
1:34:41     
networks trying to figure out kind of where you know like maybe thinking about     
1:34:47     
function and thinking about what these networks should look like as sort of a uh that sort of systems of     
1:34:56     
other uh and so they they have this method of predictive conomics where you can take like a partial connecto and     
1:35:03     
predict the rest of it and this of course has consequences for understanding what a connectome actually     
1:35:09     
does and you know it sort of based on its anatomy and based on I guess some     
1:35:16     
some predicated on function as well um and so it is instructive and in case     
1:35:24     
it's necessary to use organizational principles that link the plethora of data within unifying framework where     
1:35:31     
regularities of brain structure can be exploited to inform computational models in addition we touch on the most     
1:35:39     
prominent features of brain organization that are likely to influence predicted enal Network Dynamics so now we're     
1:35:45     
getting into Dynamics not just structure with a focus on Maman cerebral cortex     
1:35:52     
given the still existing need for modelers to navigate a complex data landscape full of holes and stumbling     
1:35:58     
blocks it is vital that the field of neuro Anatomy is moving towards increasingly systematic data collection     
1:36:05     
representation and publication so this paper is about a sort of     
1:36:12     
enabling neuroanatomical uh Precision I guess um     
1:36:19     
at or you know making it better but this has a lot of implications for sort of     
1:36:25     
thinking about you know like connectomes and how they kind of are organized     
1:36:32     
anatomically their structure and then also their function what they do in Behavior so yeah that's that     
1:36:40     
paper um and so I don't know if we had any thoughts at this     
1:36:48     
point I I you know I really like the kind of the beas you     
1:36:54     
know or excuse me um I     
1:37:00     
I the the morphofunctional um models in     
1:37:08     
their you know their realism     
1:37:17     
of the many systems that are that are at Play yeah you know I mean it's     
1:37:27     
it's we know why scientists     
1:37:33     
needs you know to to fix     
1:37:38     
down as much variability as possible to to make you     
1:37:44     
know good causal inferences or you know     
1:37:50     
speak address questions of mechanism um but     
1:37:57     
uh yeah you know looking looking at some of their diagrams is just like like we     
1:38:03     
you know we know that so many of our like mundane everyday actions are     
1:38:09     
involving that kind of that kind of interplay yeah um my one uh     
1:38:20     
um you know with many of these the only thing I I wish would accompany these are     
1:38:27     
are computational models right you that that that yeah I I think they' be useful     
1:38:35     
I think they' be you know I didn't um I didn't check about     
1:38:40     
the winter School of cognitive modeling do you remember that this     
1:38:47     
Indian School oh yeah that does does like a week of like     
1:38:54     
actar and similar similar kind of models     
1:39:04     
um yeah like like I I wish we had you     
1:39:09     
know more of those to play with in terms of looking at you know just D Dynamic     
1:39:15     
models like that that that you could play with and and and see yeah patterns     
1:39:22     
patterns changing with with yeah give people a better     
1:39:30     
um intuitions about these things right I think yeah I think so and then I I     
1:39:37     
couldn't find that um uh hilag     
1:39:43     
paper which second one uh so the second one was uh this is from the archive uh I     
1:39:50     
think it's 2007 or no 2020 sorry way their GN en     
1:39:56     
clature here is weird but the yeah it's from 20 August 2020 so it's on the archive but I don't know it's bringing     
1:40:03     
anatomical models into neuronal Network models or anatomical information into     
1:40:09     
neuronal models and so this is just kind of like     
1:40:15     
again you know using Anatomy to infer uh well basically connect owns     
1:40:32     
so if we were to you know bring together like kind of anatomy at the scale like     
1:40:39     
okay yeah sorry I've got it now yeah yeah so if we were to bring Anatomy together at the scale of like you know     
1:40:47     
uh neuronal system so it would be like the central nervous system it' be the peripheral nervous system but then also     
1:40:54     
the embodied system or the morphological system um I think it's a really     
1:41:00     
interesting kind of way to view that as like you know uh complimentary or maybe dueling Control     
1:41:06     
Systems so you know if if I have a control system in in the connectone     
1:41:12     
that's driving some Behavior there's some circuit that like You' got inhibition and you know uh activation     
1:41:19     
and things like that going on and then the body is sort of primed for something else or the body is primed for the same     
1:41:27     
thing then you know we can actually represent that as two control systems that are kind of either integrated or     
1:41:33     
non integrated and that's it's kind of an interesting way to think about that     
1:41:38     
coupling between the brain and the body or maybe it isn't like that separate     
1:41:44     
maybe because you do have uh neuronal control of the body sometimes the body     
1:41:50     
it's just shape constraints things sometimes you have local processing at     
1:41:55     
the periphery so it's not really part of that same network so there're all these things that kind of come together I     
1:42:01     
think it's a fertile area like to think about agents like computational agents     
1:42:07     
robotic agents and to think about how to really kind of build like long-term States not     
1:42:14     
just the states that we can produce like if we were to take a seans movement circuit and produce like stereotypical     
1:42:21     
movements that's a like kind of a simple control problem because you know although we need the worm body there we     
1:42:28     
do actually don't need the worm body we can put that into a robot and kind of replicate that     
1:42:34     
movement but there's some you know longer term states that you might be     
1:42:39     
primed for that are important so you know they're different uh in in some I     
1:42:46     
guess in some insects and some invertebrates you have you know uh botly     
1:42:51     
states that kind of constrict the behavior of the organism and you know there's a     
1:42:57     
physiological connection with that that goes beyond sort of the neural network output or Neal Network     
1:43:04     
output so um     
1:43:09     
yeah yeah just I mean I see now that this this     
1:43:16     
this paper is more it's it's it's really going it's     
1:43:24     
real review of anatomical     
1:43:30     
modeling and then and then giving examples of     
1:43:37     
of like like high you multi-level hierarchical organization or yeah the     
1:43:45     
the relation to functional or functional constraints on     
1:43:50     
networks due to connectivity yeah let's see if there are any good figures in     
1:43:57     
here it's got It's got some yeah I mean it's [Music]     
1:44:03     
um and it's definitely an overview of a bunch of brain map you know brain brain     
1:44:10     
map data sets yeah um which is not surprising given the the majority ulic     
1:44:19     
um authorship uh you know it's aen and ulic you know being like     
1:44:27     
where e brains is now based I didn't see amance isn't on there but like you     
1:44:34     
said like you got some other Usual Suspects that kind of connect them early connect them stuff yeah     
1:44:42     
yeah so yeah there's a they do bring up cortical layers here layer specificity     
1:44:51     
and of course you know we have when we get in information in cortex that goes up and down these columns and there     
1:44:56     
different aspects of different columns like the different layers do different things in the     
1:45:02     
processing um you have this local variations in C of     
1:45:07     
architecture uh and they they refer to the Allen brain Atlas here uh     
1:45:14     
see yeah they got they got alen Atlas they got janelia they've got um you know     
1:45:22     
they've got all the all the big mapping centers yeah they referen the Coco Mac database     
1:45:29     
which is this uh I guess track tracing database or yeah yeah and that was cocac     
1:45:38     
was a really early one yeah you know like um and um of course with     
1:45:47     
um Ralph Ralph gutter who passed     
1:45:53     
too young um but I think I want to say conter did     
1:46:00     
that with h tag anyway but KAC was definitely an     
1:46:08     
early yeah it was definitely one of those early databases trying to take all this non-human primate work and and and     
1:46:16     
do do the kind of data collection or you know coalation     
1:46:23     
properly yeah that's actually interesting there's this track tra like track tracing is really fun because you     
1:46:30     
can see like sort of the the sort of the way that that I guess you could say     
1:46:36     
information moves in the in the brain although it's just basically activation but still you get these kind of     
1:46:42     
statements of connectivity so you can say Rin regen a a strongly connect area     
1:46:48     
B and then there are these anterior grade labeled cells found Mainland     
1:46:53     
layers 23 so you can actually you know kind of put in a tracer and it'll move     
1:47:00     
to the place where you know so you can actually put together different statements and you can these relational     
1:47:07     
statements so you know that's probably useful for understanding kind of you     
1:47:13     
know if we just had a correlational map it wouldn't be as kind of a strong of a statement as to what's going on in the     
1:47:19     
connecto if you have these kind of I don't want to say causal but they're directional or relational things yeah     
1:47:27     
yeah I I dropped a paper into Neuroscience networks um generating brainwide     
1:47:35     
connectum using synthetic heal morphologies okay now which which     
1:47:42     
channel was that this was Neuroscience networks all     
1:47:48     
right it's just October 23rd yeah yeah so this is the the uh brainwide     
1:47:54     
connectum using synthetic axonal morphologies oh yeah I saw this paper actually I was going to talk about this     
1:48:00     
next U okay yeah I will I will now definitely we're we're we're SS we're     
1:48:09     
sycs it was cool I mean let me also just say that I sent that     
1:48:16     
to um I sent that to Logan okay and uh     
1:48:22     
uh but kind of forgot what I was gonna ask I mean I was gonna ask Logan to come     
1:48:27     
talk oh yeah or like like and     
1:48:34     
um Randall con I think it Randle     
1:48:40     
something um and again I'll drop a link     
1:48:45     
uh he's got a video uh I think they recorded     
1:48:51     
their Journal Club that they did a couple weeks ago the carbon copies and     
1:48:57     
they went over the they went over the the new dri jopa brain or brain um model     
1:49:06     
yeah oh yeah yeah that would be great to hear about yeah I'll drop a link but but the     
1:49:12     
main thing being that Logan was super excited to see that paper and you know and I think it's very relevant to his     
1:49:19     
larger white paper with with Randall yeah     
1:49:25     
all right so we should we should still do that with Logan yeah yeah yeah that' be great actually um so yeah that's uh     
1:49:32     
let's go over this uh paper so this is Genera course this is this is got blue     
1:49:38     
brain yeah Henry Mar yeah yeah yeah Henry marro was blue brain uh and so     
1:49:46     
generating brain wide connecto using synthetic axonal morphologies uh this is uh from this     
1:49:53     
year so this is a brand new preprint on the bioarchive uh the abstract reads recent     
1:49:59     
experimental advances including electron microscopy reconstructions have produced     
1:50:05     
detailed connectivity data for local brain regions so this is just kind of talking about what we've been able to     
1:50:12     
collect types of data we've been able to collect on the other hand for intr regional connectivity large scale     
1:50:19     
Imaging techniques such as MRI are best suited to provide insights so we have     
1:50:24     
this sort of you know these two scale sort of local brain regions detailed connectivity data and then the int     
1:50:31     
Regional connectivity and these larger scale Imaging techniques now we have two     
1:50:36     
Imaging modalities and we have two different ways of looking at the brain so you know the idea I guess would be to     
1:50:44     
integrate these in some way so however understanding the relationship between     
1:50:50     
local and long range connectivity is essential uh leveraging a novel data set     
1:50:57     
of hold Rin AAL reconstruction so this is where we're looking at this detailed     
1:51:02     
connectivity data at the local re for local regions so we have the Exon     
1:51:08     
reconstructions but if we zoom out and we think about like these inter Regional     
1:51:14     
connectivity uh needs we need to have a whole brain axonal reconstruction data     
1:51:19     
set basically and we need to use that to look at these kind of local uh as you     
1:51:27     
know local and Regional relationships so this is where we uh     
1:51:35     
they leverage this data set they present a technique to predict whole brain connectivity at the Single Cell level by     
1:51:43     
generating detailed whole brain axonal morphologies from sparse experimental data so I guess they're doing this sort     
1:51:51     
of prediction step to extrapolate from the data and get to this uh desired     
1:51:57     
point the computationally generated axons accurately reproduce the local and     
1:52:02     
Global morphological properties of experimental reconstructions um and so this is where     
1:52:09     
you you create these axons and you generate them in a simulation or in a     
1:52:16     
predictive capacity uh furthermore the computationally synthesized axons gener     
1:52:22     
large scale inter Regional connectivity defining the projectome and the connecto of brain so the connecto     
1:52:30     
are the connections between cells at least nominally I mean we can define a     
1:52:35     
connecto in different ways we can Define it as the connections between regions     
1:52:41     
the connections between cells the connections between like populations of     
1:52:46     
cells and you you know depending on how you can collect the data it's basically     
1:52:51     
a correlational work and we talked about the track tracing database you could put     
1:52:57     
condition or um relational statements on that but then you also have to project them so like you know regionally where     
1:53:05     
are regions projecting to so like it again like with track tracing you have     
1:53:11     
this projection from one place to another and so you can build this projectone which is different than a     
1:53:17     
connectum which is where you have not like a correlational map but like these     
1:53:23     
relational Maps where you go from one place to another this involves acal     
1:53:29     
transmission from one place to another and so um what they're saying here is     
1:53:35     
that they have defined a projecto and a connectone and this allows for this     
1:53:41     
incal experimentation of large Brain regions so let me go to the full text     
1:53:50     
here so this is the introduction uh where they talk about     
1:53:56     
computational simulation and synthesis of the brain and this is essential for     
1:54:01     
studying the structure and functional complexity of the brain so we need to have these kind of simulation techniques     
1:54:06     
in addition to data sets of different types we need to have biophysically     
1:54:12     
accurate models to simulate neural growth by incorporating the molecular mechanisms of neural     
1:54:19     
development though their computational intensity offer often limit scalability we can also have     
1:54:26     
phenomenological models based on mathematical principles or statistical sampling for morphological data sets     
1:54:33     
these provide more computationally efficient Alternatives so we can have different types of models to sort of     
1:54:39     
model the brain and and kind of get these computational insights we can have     
1:54:45     
these biophysically accurate models which are very much uh you know dealing     
1:54:50     
with neurons and and neural growth and and like sort of these physiological     
1:54:57     
processes and getting them as accurate as possible but to do this for something     
1:55:02     
like a human brain or even like a Maman brain of any type it's it's     
1:55:08     
computationally untenable uh so you can only do very small patches of that uh for     
1:55:15     
phenomenological models like mathematical principles or statistical sampling from data sets where you have     
1:55:21     
like these connect backs that you know are basically correlational maps you can     
1:55:26     
do this but you and they're more computational efficient however those models frequently require manual     
1:55:33     
adjustments and struggle to generalize generalize across different data sets so     
1:55:38     
it's hard for me to like generalize from like a human connectone to aat     
1:55:43     
connectome to maybe like a a drop connecto um even though they're they're     
1:55:49     
all connectomes you know it's hard to say like with the sort of the the insights out of     
1:55:55     
there in 2022 they introduced the computationally efficient method for     
1:56:01     
synthesizing biologically realistic dendritic morphologies this is the citation 7 which is computational     
1:56:08     
synthesis of cortical dendritic morphologies based on the top     
1:56:13     
topological morphology descriptor in eight and nine so eight this is a     
1:56:18     
topological representation of branching ormal morphologies and nine     
1:56:24     
is objective morphological classification of neocortical paramal     
1:56:29     
cells so they were they've been working in this area where they're kind of     
1:56:34     
looking at these dendritic morphologies looking at this this     
1:56:40     
branching neuronal morphologies and then this this classification of paramal cells um I     
1:56:49     
guess they're all using the same kind of method and and trying to get at different uh granularities of of     
1:56:55     
dendritic morphologies so a similar approach was employed to synthesize astrocytes within     
1:57:02     
the complex neuro Leo vascular Network so this is where you have this uh     
1:57:08     
neurons and and glea and vascul are all kind of interacting and they're trying     
1:57:14     
to get uh they're trying to find the asites or synthesize astrocytes in those     
1:57:20     
models however the majority of models focus on dritic synthesis and do not     
1:57:25     
account for brain topology when generating morphologies so this is where you know you're just looking at dendritic     
1:57:31     
synthesis but not the larger topology of the network uh so they're trying to     
1:57:38     
synthesize axonal trees and there are a lot of limitations to this a lot of times it's just a very complex Network     
1:57:45     
and also you need to integrate these biophysical models with the sort of statistical models of kind of activity     
1:57:53     
so unlike dendrites uh which are generally restricted within a brain region axons     
1:57:59     
typically extend a specific brain region so axons or these axon uh trees are     
1:58:06     
going to be much larger than the dendritic trees so it's harder to model these uh     
1:58:13     
effectively uh and so this highlights a necessity of generating axons that are     
1:58:18     
spatially embedded within the brain and this is the paper here that they're referring to framework for efficient     
1:58:25     
synthesis of spatially embedded morphologies although there have been modeling efforts in areas such as axon     
1:58:31     
guidance trade-offs between material and conduction delay and fiber arrangement     
1:58:37     
to dat Only The Roots model has tackled the challenge of synthesizing detailed axonom morphologies so the roots model     
1:58:44     
is this paper Roots by Bing AAL an algorithm to generate biologically     
1:58:49     
realistic cortical axons and an applicational electroceutical model so     
1:58:55     
this is like you know uh sort of the attempt to do this so basically this     
1:59:00     
whole set of work is about modeling these kind of networks of connection like not like the statistical Maps but     
1:59:08     
just like the things that connect everything so you have dendritic model dendritic trees exal trees and then     
1:59:16     
getting this to be biological realistic basically taking what is a physiological     
1:59:21     
feature physiological process and scaling it up to the brain to Regional     
1:59:28     
parts of the brain so this is kind of where um you know can we do this for uh     
1:59:34     
uh some sort of mamalian connector uh however the axons generated     
1:59:39     
by this latter model which is the roots model um is restricted to the rat dentate gyus so it's a very small part     
1:59:46     
of the Rat brain and do not extend across brain regions limiting their broader applicability to long range     
1:59:54     
axons uh so they talked about like synthesizing these brainwide long range     
1:59:59     
axons it requires replicating the projection patterns and morphometric features of biological long range axons     
2:00:06     
also considering brain topology uh in addition biological data     
2:00:12     
on these structures was historically limited to just a few dozen morphologies uh until we've been able to     
2:00:19     
get some new types of Imaging and place and be you know which has allowed us to     
2:00:25     
reconstruct hundreds of different types of axons uh successfully synthesizing     
2:00:31     
brainwide axons allows for the creation of synthetic connections between cells across the brain thereby progressing     
2:00:37     
from the connectome encoding connections between individual neurons to the     
2:00:43     
projectome which is this paper anol model of the mouse hole neocortical micr     
2:00:48     
connectone which encodes connections between re once this connectivity is established it     
2:00:55     
becomes possible to expand local simulations to simulations of circuits involving multiple brain regions getting     
2:01:03     
closer to realistic full brain simulations so their whole goal originally was to build these whole     
2:01:10     
brain simulations and you know this has been like a long-term project for them so     
2:01:16     
they've really kind of worked on a lot of the components of this and so I think they're you know kind of this is a good     
2:01:22     
example of how they uh have been trying to approach this you know kind of going from biophysical models to these     
2:01:29     
connecto models to projecto models and then using the tools and and scaling     
2:01:35     
between them to come up with these uh Regional sort of models of     
2:01:43     
connection they're they're playing to their strengths     
2:01:49     
yeah I mean you know I feel like yeah     
2:01:54     
gonna spend the rest of his his career trying to justify the work he did in the     
2:02:00     
last you know as part of the human brain project yeah well I think you know that's that's good though yeah yeah it's     
2:02:08     
it's it's it's really good stuff you know like like and you see the the the     
2:02:14     
the H tag paper that you covered um you     
2:02:20     
see yeah just the many way the many scales at which people currently collect     
2:02:28     
data and and you know how much when you think of um you know that's a nice     
2:02:36     
overview because it's like you got to understand that there are like hundreds if not thousands of people working at     
2:02:42     
each of those scales yeah right and working to make to make a database at     
2:02:48     
that scale yeah you know or are on you know using that     
2:02:56     
particular you know technology yeah and and     
2:03:02     
um and yet it doesn't Bridge     
2:03:08     
the you know MRI to single cell     
2:03:15     
you work excuse me um um that's so     
2:03:22     
important and um anyway so yeah I I I     
2:03:28     
will follow up with Logan because I think his um their their white paper on     
2:03:38     
whole brain emulation     
2:03:43     
um you know like again like I've only got a problem with kind of like the end     
2:03:49     
goal of that um what's the end goal well the end goal is that somehow     
2:03:56     
you get you get function from structure okay you     
2:04:01     
know you know with with this with it being tied up in this     
2:04:10     
somewhat I don't know what the right quixotic     
2:04:16     
um goal of AI safety alignment     
2:04:22     
you know right like like yeah I don't know quick exotic is     
2:04:28     
the right word um right I think it's like a little bit     
2:04:36     
miss you know like like I I I don't even think we should be dreaming about     
2:04:43     
that like like yeah I'm not I I don't have     
2:04:49     
the good literature reference yeah for for you know but like     
2:04:55     
um anyway the main thing being that I would love to to talk more     
2:05:02     
about you know how computational synthetic a synthetic     
2:05:09     
program like ma rooms can can     
2:05:14     
potentially complement or or if not like complete the kinds of data collection     
2:05:21     
that that Logan's talking about using you know cryo at scale in Anger across     
2:05:30     
you know organisms yeah yeah you know where where     
2:05:38     
you know he's he's almost trying to capture all of you know he he wants to     
2:05:44     
capture kind of BR big brain detail you know again big brain as a project big     
2:05:50     
brain detail um you know in in a in an     
2:05:56     
organism in a in a reasonable time     
2:06:05     
yeah like yeah yeah and yeah that would be it' be a     
2:06:11     
good conversation to have I I'm I'm um trying to remember what     
2:06:19     
um let me just see if I can     
2:06:27     
um I'm curious about this relationship between structure and function and     
2:06:32     
specifically like if anyone's done any work on like kind of figuring out like     
2:06:38     
what are the like kind of the origins of a connectome so for example like if you     
2:06:43     
were to build a simple connectome and you could like build something kind of at random you can assemble like     
2:06:50     
connections what you know is that something that would yield simple     
2:06:55     
functions and then I mean we kind of know that like say like the connections in a brenberg vehicle can do things but     
2:07:03     
like could you like have a set of experiments where you could put together random connections and thus the random     
2:07:10     
structures and then it yields functions and then what are you know can we select     
2:07:16     
on those functions to produce things that are kind of diverse and have some     
2:07:22     
go directed aspect to them I'm just curious about that like I don't think     
2:07:27     
anyone's done that kind of set of experiments the the um the connection     
2:07:34     
sorry I'm just I'm just dropping in I I bet actually I'm gonna just check if     
2:07:40     
I've dropped this in before oh okay I hav     
2:07:46     
um um so I just dropped in a paper comparative prospects of Imaging methods     
2:07:51     
for whole brain Mamon connectomics into Neuroscience networks right okay and     
2:07:58     
that's his paper with um with Randall and uh Todd Huffman okay yeah this is     
2:08:06     
okay good I don't know who Todd is yeah I don't know but     
2:08:12     
um but should be should be interesting I'll     
2:08:18     
get more the um the one other thing I wanted     
2:08:23     
to say was that that that um is what was     
2:08:30     
kind of the focus of Randall con's um Journal     
2:08:38     
Club the carbon copies Journal club that they just did which was this um     
2:08:46     
dropa you know I I forget if they were was it the shoe paper here one second     
2:08:52     
I'll get the um     
2:08:57     
uh uh yeah so so here's the     
2:09:04     
video     
2:09:09     
um um which I will drop in as well okay so     
2:09:16     
constrained connect home constrained networks DNM of the fruit fly visual     
2:09:22     
system okay it's not the paper I'm thinking of     
2:09:28     
um so I was thinking of the shoe like shoe paper sh I I believe this one's um     
2:09:38     
and again just to make things easy in you know I'll just drop this in slack     
2:09:45     
that this is the paper that they're talking about okay okay this one here uh     
2:09:52     
right a study demonstrates how yeah yeah yeah yeah yeah this but     
2:09:57     
um there's a um anyway I I'm try and find another     
2:10:05     
paper I I'll find it later okay just in terms of simulations you know using     
2:10:10     
using dropa you know so again in my mind there's a Phil shoe paper maybe that's     
2:10:17     
what it is it's spelled um as sh     
2:10:24     
shiu um anyway he he's um got a cool     
2:10:30     
paper where you know he's using all this Flywire AI data that's being collected     
2:10:40     
but then he uses that in a much     
2:10:46     
more reduced fashion so     
2:10:52     
this is this is somewhat of a counter to say mm stuff right is his shoe over at     
2:11:01     
Berkeley with h i want to say Kristen something don't if I've got Kristen on     
2:11:07     
the brain I'm pretty sure it's the the last author is Kristen's own uh her lab     
2:11:15     
where they're one of these Labs that's collecting you know real you know     
2:11:21     
um single cell kind of data but he does this he does this like spiking neural     
2:11:26     
network model um abstracted from Flywire data to get     
2:11:37     
um I think it was like old factory or something     
2:11:44     
Behavior out of the system you know so you know and it was super     
2:11:51     
computationally efficient like like like he did this on his laptop okay you know     
2:11:57     
like like there had been this this Tokyo you know Japanese supercomputing Center     
2:12:04     
model University of Tokyo where they' done you know a full Cable model the you     
2:12:10     
know like they'd taken the connectomics data and they'd made this totally biologically realistic you know     
2:12:18     
model and they ran for you know     
2:12:23     
300 hours or like 6,000 processors right and and     
2:12:31     
he did the same thing on his laptop yeah for you know with this like really kind     
2:12:37     
of um very abstract you know kind of model     
2:12:43     
but but but motivated by kind of you     
2:12:48     
know good neural network Theory okay yeah and and I'll try find it ah yes yes     
2:12:58     
yes it's SP with you all right yeah and her name is Kristen Scott yes okay I     
2:13:04     
think that's yeah I'll drop I'll drop uh okay I I will Stave off dementia     
2:13:14     
for one more there we go one so this is yeah D comp computational brain model     
2:13:20     
Rev sensory motor processing Philip Shu and Kristen Scott yeah yeah okay that's     
2:13:28     
great but it's it it's you     
2:13:33     
know it's interesting a and when I met you at this foresight     
2:13:40     
meeting um and I follow I I you know again I was at this foresight meeting     
2:13:46     
saying like you know we need to stop you know like like forget about this whole brain     
2:13:53     
emulation work you know you can't if your goal is is this AI safety     
2:14:01     
your goal is like we need you know like like a biological     
2:14:08     
entity to be um to interface with the with the     
2:14:16     
computer um you know start with just organoid intellig like we can't even you     
2:14:23     
know we can't push any any kind of computing work to to biology at this     
2:14:29     
point yeah right and and so if you if your if your goal is to like upload     
2:14:35     
Consciousness like you need to start with you know an organoid in a dish     
2:14:43     
right like and and that that would be that would make sense you know     
2:14:49     
mechanistically right and but I I asked you if you'd be     
2:14:55     
interested in in in any anything like that and he was just like no no I     
2:15:02     
don't I I don't think that's that's a good use of my time yeah     
2:15:11     
well so yeah so okay well that's great     
2:15:17     
uh yeah thanks for that discussion and we had a lot of papers in there that we kind of yeah so     
2:15:25     
I'll I'll when I do the YouTube post I'll put them in there and the citations     
2:15:31     
please do yeah yes I I like I like yeah so I had one more thing here I think     
2:15:37     
Jesse had to leave he just a few other updates he's going to talk about we     
2:15:42     
robot 2025 we'll may talk about that next week and then there's a fellowship     
2:15:47     
for mental health working group and uh Society ethics and Tech progress so yeah     
2:15:53     
he had some things in the slack on that and congratulations on the mental health     
2:15:59     
working group looks like they're making some success and Headway and also you know we're looking     
2:16:06     
for sort of getting ready for uh New York celebration women Computing in     
2:16:12     
2025 but also we robot in 20125 so that more about that next     
2:16:18     
week yeah yeah yeah all right thanks next week bye take care brother     
