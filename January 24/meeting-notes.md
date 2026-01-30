## Meeting Recording

NONE

## Mastodon thread

NONE

## Feature Videos

["Building a Better Science" AI assistant](https://youtu.be/txKPz8HoGS8)

["Ask a Cyberneticist" RAG Encodings](https://youtu.be/L1GHPCrCUNo)

[JoPro Year in Review 2025](https://youtu.be/VUIzpBjnswg)



## NOTES
Not answering a particular question --> simulating different changes in tissue composition.

* infer tissue structure from MRI --> at each voxel, what is the best model?

* statistical comparisons of model features. Brain tumor data --> heterogeneity of a tumor.

* people who have a lot of text associated with them.


Hitchens, Levin bot --> the more source material, the more idiosyncratic.

* what goals -- can you use something like this for good?

* BrainGPT -- Brad Love project. Trained on Neuro papers. 

* experimental design -- what will you find?


Finding something potentially problematic with experimental design.

* NeuroTechX -- RAG model. Put together a review paper easier? What is the use case?

* Keyword search --> PubMed vs. RAG embedding. "Finding a deeper similarity".

* JoPro letter --> institutional capacity -- setting directions, early-stage project.


Development Cycle --> unit tests, building a framework --> synthetic data, real-world data.

* fast development -- without optimization, cuts ties to tool creation.

* Morgan --> reading group paper --> human data, metacognition --> improve ill-sturctured task performnce.

* placeholder --> agents created something not specified --> use JULES as a path across development.

"Better Code, Better Education". 


Stack (do subagents share context in some way):

1) Gemini-Antigravity IDE from Google.

2) Reasoning Model.

3) IDE with Multiagent Feature (creates subagents).


Practical Diffusion, microstructural imaging in Python.

* where is H20 free to move and where is it restricted? Inter-axon H20 free, extracts implementation, soma.


Big Picture Reasoning:

* need more guidance -- NVIDIA containers vs. PIP Install, setting rules for all agents.

* agents create docs --> other agents use them.

* 



Gas Town: Claude code multi-agent.

* big-picture reasoning. Need more guidance (NVIDIA containers vs. PIP install). Agents create docs, other agents use them. Setting rules for all agents.


Cognitive Foundations for Reasoning, Manifestation in LLMs.

* complex tasks, but can't add two numbers, hard to get at internals of reasoning. What's the best approach?

* use 28 reasoning categories, better at restrategizing?

* if you help a model, helps performance (Algorithms We Live By)

* can we do CogSci without LLMs?

* PyTorch, CUDA, OpenCL --> set up programming environments --> agent wraps work.


Not answering a particular question --> simulating different changes in tissue composition.

* infer tissue structure from MRI --> at each voxel, what is the best model?

* statistical comparisons of model features. Brain Tumor data.


People who have a lot of text associated with them. Hitchens Bot, Levin Bot --> the more source material, the more idiosyncratic.

* Ask a Cybernetician --> Ashby bot, Weiner bot.


Mental Health paradigms and perspectives --> iterated on it. For a couple of weeks. Things will change a lot. 

* theories of "what they are doing". Individual experience around using theories --> "what is it like"?

* social work curriculum --> very interdisicplinary.

* Media Lab-style project. Futures Center -- Jopro flagship. Institute for Progress. Futurist-style websites.

* need to contextualize, what does this space offer? DAIR is doing virtual events, Possible futures (AI isn't inevitable).

* RAG embeddings: now, why would you use for research? Narrative Formation --> literature.

* surveillance to anti-veillance.


Molly --> automated decision-making, allostatic kinds -- what yields interactions?

* modernizing mental health. Cognition Futures --> links with Ekkolapto, new activities?

* Princeton Envision --> NYCWiC. Fallign asleep on a communication space.


Currently there is too much pressure to create a media brand, content domain, where do we "show up" --> JoPro socials.


## TRANSCRIPTS
Transcript for "Building a Better Science" AI assistant (Saturday Morning NeuroSim)
0:00     
You must be you must be talking about     
0:02     
the old XY um what no is the the um you     
0:09     
must be talking about the the old joke     
0:11     
in Python about anti-gravity and     
0:17     
I'm like I'm talking about the IDE from     
0:20     
the company that made you     
0:24     
and and um anyway it's a little funny     
0:29     
when when I finally said when I was     
0:31     
like, you know, trying to get it to to     
0:34     
understand that I was using anti-gravity     
0:36     
ID. Apparently, that is still considered     
0:39     
like a beta project at Google.     
0:43     
So, it is it is it is weird because I'll     
0:46     
talk to people about about how I'm doing     
0:49     
it and they're like, "Are you using     
0:50     
Gemini?" I'm like, "No, I'm using     
0:53     
anti-gravity." They're like, "Oh, you're     
0:55     
using VS Code." And I'm like like like     
0:58     
they've definitely     
1:00     
VS Code is open source like they've     
1:03     
definitely got a guey that they're using     
1:08     
but     
1:11     
the the multi- aent feature     
1:14     
um because I'm using three things. I'm     
1:17     
using Gemini which is obviously their     
1:19     
kind of chat GPT     
1:21     
and and I'm using their their reasoning     
1:25     
model right so it's like the three pro     
1:28     
right     
1:31     
then     
1:33     
but I'm actually doing most of the work     
1:35     
with the IDE which has this multi- aent     
1:37     
feature right so you can actually start     
1:40     
multiple conversations and the prompts     
1:44     
it's interesting how some of the prompts     
1:48     
create sub aents     
1:52     
and I'm trying to understand     
1:55     
how that differs     
1:58     
from me creating three agents, right? So     
2:01     
it's like if it has three sub agents     
2:05     
like so they share some context in some     
2:09     
way that's valuable and I'm I'm you know     
2:13     
again there's no way to look any of this     
2:15     
up like there's no     
2:18     
um there's no manual for this you know     
2:21     
there's like some YouTube videos from     
2:23     
the Google developers     
2:26     
um and     
2:30     
Uh, but then I'm also using Jules and it     
2:34     
seems like most people haven't heard of     
2:36     
Jewels,     
2:39     
but Jules is another Google project     
2:41     
where it's an asynchronous agent.     
2:45     
Um     
2:49     
the the the advice the advice that     
2:52     
Gemini is giving me     
2:55     
is that I should be using jewels repo     
2:59     
wide.     
3:00     
Okay. and and I should be using agents     
3:05     
and the multi- aent functionality for     
3:08     
developing features     
3:10     
and and obviously Gemini for kind of     
3:13     
like     
3:15     
big picture reasoning kind of things. Um     
3:19     
so so for instance like I tried setting     
3:24     
a um     
3:26     
uh some coding standards and and you     
3:31     
know basically code review, code audit,     
3:35     
doc string checking,     
3:39     
um     
3:41     
unit tests,     
3:43     
um the use of     
3:46     
the use of units     
3:48     
in all the um appropriate use of units     
3:52     
and unit checking     
3:55     
um uh since I'm doing physics right     
4:01     
uh as I said as a jewels task so it was     
4:05     
you know like again like I would love     
4:09     
I'd love some guidance uh in terms of     
4:12     
how to how to best you know structure     
4:16     
this     
4:18     
um I I I I think I come back to and I I     
4:22     
I sent you a there was a hacker news     
4:26     
story on Gast Town.     
4:29     
There was a couple hacker news stories     
4:30     
on Gast Town and so so apparently some     
4:34     
of the criticism Gas Town which is the     
4:36     
claude code multi- aents     
4:40     
it it it takes a it takes a whole town     
4:43     
to raise a child. um uh have been like,     
4:50     
"Wow, this is like an excessive use of,     
4:53     
you know, wow, we're going to burn the     
4:55     
planet a lot faster if if you create 40     
4:58     
agents to do this."     
5:00     
Um     
5:02     
at at the same time like like I can also     
5:06     
see     
5:08     
the you can also see the benefit of it     
5:12     
in terms of um having that kind of     
5:18     
you know communication having having     
5:20     
particular agents that are just there to     
5:23     
like um help with the communication     
5:27     
between agents or like like help with     
5:30     
the standardization like hey there's a     
5:32     
new there's a new function that you     
5:35     
should all be using and you know like     
5:38     
like it's it's hard to get across that     
5:41     
sometimes I'm like you know     
5:44     
if I mistakenly start a new agent it     
5:47     
will immediately start to try and pip     
5:49     
install stuff and it's just like no I've     
5:52     
I've tried to make a blanket rule like     
5:55     
anytime you want to install things or do     
5:57     
any Python work like use UV.     
6:02     
Um I I I'm still I'm still like how do I     
6:06     
set global rules for all my agents so     
6:09     
that like you know when when it sees a     
6:14     
PyTorch project I'm like don't pip     
6:18     
install PyTorch like on a DGX Spark you     
6:22     
need to use a Nvidia NGC container. like     
6:26     
how do I I want I you know there's like     
6:30     
there's like rules I want all the agents     
6:32     
to have. So I'm trying to figure out how     
6:35     
to use the agents.m MD file.     
6:42     
Uh again, it's like coming back to this     
6:45     
thing we definitely talked about last     
6:46     
week in terms of, you know, you have you     
6:51     
have your agents creating     
6:55     
documents,     
6:56     
you know, markdown files     
6:59     
that are they call artifacts that, you     
7:03     
know, other agents can find and read and     
7:06     
and learn from.     
7:09     
in terms of, you know, ongoing progress     
7:11     
or, you know, rules to live by or things     
7:14     
things like that. Yeah.     
7:18     
Um,     
7:20     
but I I do feel like I'm I'm, you know,     
7:24     
just throwing a lot at the at the wall     
7:28     
and seeing what sticks, you know? I mean     
7:31     
in the sense of like like I'm trying to     
7:34     
structure it but     
7:37     
um     
7:40     
I I feel after a certain amount of time     
7:42     
like I'm always like doing you know I'm     
7:46     
like trying to use jewels to then you     
7:50     
know do a pass across the the recent     
7:53     
development and make sure that it's     
7:55     
still     
7:58     
that it's actually complete right like     
8:01     
like how how how much do you check? Um     
8:06     
you know every every so often I'll find     
8:09     
in a walkth through that like there's no     
8:13     
there's no function that's just a     
8:14     
placeholder or something like that,     
8:17     
right? like like and and so what you're     
8:20     
looking at there is like like one of the     
8:23     
like agents created something but it     
8:27     
didn't actually end up getting used by     
8:30     
the output requirements that I had     
8:34     
either specified in the prompt or etc.     
8:37     
Right? So     
8:41     
it's it's it's again it's just like you     
8:44     
you you you     
8:46     
doing development so fast that things     
8:49     
can actually just get um set up. Um,     
8:55     
uh,     
8:57     
yeah. And and and the other the other     
9:01     
thing being funny is just like how many     
9:05     
temporary test files and things like     
9:07     
that. Like I keep I keep saving to     
9:09     
GitHub a lot of just uh     
9:13     
checks and     
9:16     
text text outputs that have been have     
9:18     
been generated. Um, but again, it's it's     
9:23     
it's remarkable how fast it can create     
9:28     
something that, you know, you could do     
9:30     
yourself, but would take you a lot of     
9:32     
time to look up stuff and to to, you     
9:36     
know, check what the syntax is on this.     
9:38     
And,     
9:39     
you know, it's it really is like having     
9:42     
a a     
9:46     
you know, an assistant with a just an     
9:49     
incredibly broad range of technical     
9:52     
skills.     
9:59     
But getting getting to the point where     
10:01     
it's just like     
10:05     
we'll, you know, be able to get in touch     
10:08     
with some some researchers and be like,     
10:11     
you know, hey, I've been testing this     
10:13     
tool. It it can do in seconds what, you     
10:16     
know, takes minutes or hours.     
10:21     
and it and it produces uncertainty     
10:23     
estimates and it     
10:27     
excuse     
10:30     
uh it's really interesting     
10:32     
but I'm also thinking about like like     
10:35     
how do I um I mean I I I don't know if     
10:39     
like reaching out to Russ or something     
10:40     
like that be like okay like you know     
10:43     
I've I've really used Google to to     
10:47     
create this this tool,     
10:50     
you know, I totally stand by the testing     
10:51     
and things like that, but like how do I     
10:54     
how do I talk about this development,     
11:00     
you know, or or is this is this super     
11:03     
common now?     
11:08     
Yeah, it's interesting. um just kind of     
11:13     
being able to take some of the harder     
11:16     
tasks and push them off to an assistant     
11:19     
and automate that. But then we have to     
11:21     
of course describe how it's being done     
11:24     
and you know like in the methods section     
11:26     
of a paper we usually describe     
11:30     
all of the steps that happened and how     
11:33     
has to be documented. I guess that's     
11:35     
kind of the uh point of better science.     
11:40     
is that it's more transparent but it's     
11:42     
also better science in the sense of you     
11:45     
know getting things done and getting     
11:48     
things to run. So there yeah there is     
11:51     
that sort of tension there     
11:55     
and um you know it's always nice to know     
11:57     
how something works but if you can like     
11:59     
implement it well it's kind of like a     
12:01     
container right you have something in a     
12:03     
container I can give you the container     
12:06     
theoretically you should be able to run     
12:07     
the whole thing in the container you     
12:09     
don't really have to tell me every step     
12:11     
of what the container what's being     
12:13     
executed in the container just as long     
12:15     
as I have that artifact     
12:19     
So I mean you know it's it's really     
12:20     
interesting.     
12:23     
Yeah. Yeah. And and     
12:26     
um     
12:28     
you know I mean I I still think that the     
12:31     
development cycle is very much like     
12:33     
working you know working regularly right     
12:37     
which is you know you build up a     
12:40     
framework and then     
12:43     
you know you potent potentially doing     
12:45     
some kind of like unit tests as as you     
12:48     
build things. But     
12:51     
but you finish that with a now let's try     
12:55     
this on some synthetic data     
12:59     
you know where I I know what I should be     
13:02     
seeing     
13:04     
um given given the set of operations and     
13:08     
then you know now let's try it on some     
13:10     
real world data where you know there's     
13:14     
realistic noise and and you know but I     
13:19     
go off of     
13:21     
uh you know this is this is a data set     
13:25     
with known problems or with you know     
13:28     
these are parts of the you know I I go     
13:30     
to particular parts of the brain where     
13:32     
you have very known kind of fiber     
13:35     
orientations and things like that like     
13:39     
etc you know     
13:42     
um     
13:47     
but it's still you know coming back to     
13:51     
that that you know um     
13:55     
better code better education     
13:57     
um uh uh     
14:02     
I I'm I'm absolutely learning to you     
14:05     
know like like again like this isn't     
14:07     
just like go go create a framework for     
14:11     
you know diffusion MRI modeling right     
14:15     
like like you're stepping through all of     
14:18     
this and um     
14:22     
uh     
14:24     
like like it's actually been really     
14:27     
interesting of how much I'm learning     
14:30     
along the way. Um     
14:34     
but yeah and these are on some topics     
14:37     
that like have been my     
14:41     
research area for a long time like you     
14:43     
know uh yeah and some of it is that like     
14:49     
I've never had the the ability to like     
14:53     
kind of wade through so much tactical     
14:56     
math     
14:59     
and and     
15:02     
examples     
15:05     
um so quickly but with with commentary     
15:11     
um that yeah I I I really think that     
15:14     
like this can be     
15:17     
um     
15:20     
practical for teaching purposes.     
15:22     
Yeah.     
15:26     
Yeah. I've been thinking about and and     
15:28     
I've been doing a number of different     
15:30     
things with different AI tools. Um in     
15:34     
the next couple weeks I'm going to maybe     
15:36     
give some demos of this and maybe it'd     
15:38     
be nice if you give a short demo on it     
15:40     
too at some point. Um, but to be able to     
15:44     
kind of do things that maybe were very     
15:47     
hard before, we couldn't do before that     
15:50     
are a lot easier and kind of walking     
15:53     
through some of the parts of that and     
15:55     
how that's implemented.     
15:57     
Yeah.     
15:58     
So, I mean, you know, this is some of     
15:59     
it's research, some of it's like, you     
16:02     
know, other other types of things you'd     
16:04     
like to do. Um but there yeah there     
16:08     
actually a lot of uh local tools like on     
16:11     
local machines that you can use that are     
16:13     
actually quite impressive. The problem     
16:16     
of course as you've mentioned is that     
16:19     
the documentation isn't always there. So     
16:22     
you have to kind of feel your way around     
16:24     
it and and kind of get a sense of how it     
16:26     
works and everything else. So the you     
16:29     
know there's this sort of rep you know     
16:33     
you want to be replicable in what you do     
16:36     
but then again you want to also try all     
16:39     
these different combinations of things     
16:41     
to get them to work. So you have to     
16:43     
figure out what you can get to work and     
16:46     
then how you make that you know into a a     
16:50     
repeatable pipeline that I can just say     
16:52     
here I'm going to hand this off. this is     
16:54     
the way this works and it'll basically     
16:57     
give you this result.     
16:59     
So, you know, it's it's it's     
17:02     
hard to do um because again, we we've     
17:05     
talked about this um the different     
17:07     
strategies for doing this. So, but yeah,     
17:11     
I I don't think I'm going to do that     
17:12     
this week, but maybe in in subsequent     
17:14     
weeks or maybe I'll do it as like a a     
17:17     
separate thing on the YouTube channel     
17:19     
where I kind of walk through some of     
17:20     
these tools.     
17:23     
So yeah, I mean that'd be interesting to     
17:25     
see maybe like some of the outcomes of     
17:27     
of some of the stuff you're doing too.     
17:29     
Just kind of like what is it simulating     
17:31     
and you know what kinds of interesting     
17:34     
things can you build with that? Can     
17:37     
um     
17:39     
I assume you're you know you're really     
17:41     
kind of working more on kind of research     
17:43     
questions.     
17:45     
Um     
17:46     
well it's it's um I took a project     
17:51     
called um uh     
17:56     
diffusion     
17:57     
what's what's it um     
18:00     
diffusion microructural imaging in     
18:02     
python     
18:05     
which     
18:07     
was was so this is a a tool for     
18:12     
um fitting tissue models to diffusion     
18:17     
data. Right? So, this is like when     
18:19     
you're looking at how water is moving,     
18:22     
you're testing how water's moving in in     
18:26     
64 directions.     
18:28     
And it allows you to get, you know, to     
18:31     
kind of make a     
18:35     
to to capture the ellipsoid, if you     
18:37     
will, of like where is where is water     
18:40     
free to move in this direction and where     
18:42     
is it restricted in this other     
18:44     
direction.     
18:47     
But then then as time's gone gone on,     
18:51     
people have got more sophisticated with     
18:53     
that and you know, they've recognized     
18:56     
that you actually are looking at     
19:01     
multiple water pools, right? So you have     
19:04     
inter axon water,     
19:08     
you have um     
19:10     
the extra axon water     
19:14     
and you have free water.     
19:16     
Um and and you you know there's there's     
19:21     
even techniques now where they're     
19:22     
they're talking about the soma s water.     
19:26     
Um, and     
19:29     
by, you know, again, not to get it too     
19:32     
into the the diffusion sequence itself     
19:35     
in terms of how they're they're doing     
19:37     
that, but they're they're making it     
19:41     
such that they can actually separate     
19:43     
those water pools potentially, right?     
19:47     
Um, so it it it I'm not as much     
19:52     
answering a particular question at this     
19:54     
point as as what I'm trying to do is     
19:57     
make a tool that     
20:00     
you know I I was in the analysis group     
20:03     
at FIM group. So we and like like you     
20:07     
know so my my advisor made you know     
20:09     
leads the the FSL team which is like the     
20:13     
software that's the most widely used for     
20:17     
MRI research MRI processing     
20:22     
and in my own my own work on in     
20:25     
psychiatric nerve imaging like certainly     
20:29     
you know people come up with things like     
20:32     
uh we expect you know in these patients     
20:36     
to see these changes in you know tissue     
20:41     
composition or something     
20:44     
and that's and that's what this allows     
20:45     
you to right? Or this is certainly     
20:48     
trying to get at like how to how to     
20:52     
infer tissue     
20:55     
um     
20:59     
tissue structure from the from MRI.     
21:04     
Um I'm I'm kind of focused on a     
21:06     
particular thing which is how to     
21:11     
um how to do that in a basian way that     
21:16     
allows for model comparison. So I can     
21:20     
say like like is I at each voxil     
21:26     
what is the best model for the tissue     
21:30     
there? Um and     
21:35     
yeah like trying to give it that you     
21:37     
know trying to give the tool a     
21:39     
computational physics tool a statistical     
21:42     
model comparison feature     
21:46     
it would be like like if you were     
21:49     
pinning me down on on     
21:54     
a go a goal with it. Um,     
22:01     
but that allows you to ask a lot of     
22:03     
questions,     
22:05     
you know, like uh     
22:08     
and they don't have to be psychiatric,     
22:10     
you know, like they could be I I I think     
22:13     
it would be really interesting to look     
22:15     
at, you know, um, brain tumor data like     
22:20     
like how useful is this in terms of     
22:24     
capturing the heterogeneity of the     
22:28     
tumor,     
22:29     
right?     
22:31     
Um because again that can be really     
22:33     
useful um for understanding the kind of     
22:38     
severity andor you know like u um     
22:44     
presurgical planning     
22:48     
might be one.     
22:55     
Yeah, that's that's interesting. Um,     
22:58     
yeah, so it's definitely worth     
23:00     
revisiting and or or you know, being a     
23:03     
little bit more like hands on in the     
23:06     
group here.     
23:08     
Yeah, I know. I'm I'm and I would love     
23:12     
to know. I mean, you know, like I this     
23:14     
could be one of those things where it's     
23:16     
just like if there's no manual and     
23:18     
there's no kind of instruction,     
23:21     
then, you know, perhaps like trying to     
23:25     
start some sort of group for it would be     
23:28     
the best the best way to actually find,     
23:31     
you know, f find community is to try and     
23:35     
create some



Transcript for "Ask a Cyberneticist" RAG Encodings (Saturday Morning NeuroSim)     
0:01     
Yeah, I was actually going to share some things I've been working on with um agents like training agents with some of     
0:09     
our readings and things like that and getting some answers out of it. Um     
0:16     
so you know reconstructing cybernetics we have a GitHub repository for that. um     
0:23     
we've been doing things like um you know uh defining terms and things like that.     
0:30     
So I decided you know I want I would like to train a model with some of the data from uh different sources and     
0:39     
almost kind of build a model that's like ask ask a cybernetician. So the idea is like I I train it on sort     
0:47     
of the personality or the uh outcomes like papers and and presentations of     
0:53     
different cyberneticians to see if if I ask them questions about those personalities,     
1:01     
what kinds of things would I get out of it? And so this is just very early days     
1:06     
on this. It's not like a a final project, but I've put some of these on the GitHub repository.     
1:13     
So, I've been using two models for this. Just kind of playing around with see which one is better or which one gives     
1:20     
me better answers. Um, I've run into some bottlenecks because um I'm not     
1:26     
paying for any of the agents. So, I'm I'm, you know, kind of trying it out     
1:31     
with the limitations therein. So, like you can't upload, you know, you can't     
1:38     
train it with documents that are over a certain size, which is a problem.     
1:43     
uh you can only you know train a certain number of documents but I've tried to actually found a collection of um     
1:51     
of letters and correspondences from different cyberneticians I found this through the library so I've been using     
1:58     
some of those materials I've also been using some of source some of the source papers from different people um so I     
2:06     
I've I've the idea is to create something that's either an amalgam of or     
2:13     
a um different personalities of WR Ashby     
2:18     
uh McCulla uh von Forester and um     
2:25     
why Robert Weiner. So we have four people uh four cyberneticians     
2:31     
who are sort of targets for this. Um, and then the idea would be like to     
2:36     
create maybe one for one agent for each or one model for each cybernetician or     
2:44     
combine them into a single model. I'm not really sure yet. I'm I'm still kind of playing around with it, but the     
2:51     
outcome are these. So, in Claude sonnet, um, I did it I I did a couple what I     
2:57     
would do is I would train it with these source materials. and I would uh ask it     
3:03     
would prompt it and it would give me answers for different prompts. So the first one here is um so this was     
3:09     
compiled in claude sonnet 4.5 um and this is uh you know I would     
3:15     
prompt it with a couple of prompts and I would get this answer and the answer of course is structured in the way that you     
3:21     
would get out of a large language model. Um so this is uh the first prompt was     
3:28     
how would WR Ashb define variety. So this is again you know if you have     
3:33     
trained the model on WR Ashby's work he mentions variety in the very specific     
3:40     
context that he mentions variety the agent also can go out onto the     
3:45     
internet and get information. So there is information there as well. So the     
3:52     
first one is how would WR ashb define variety and the answer is summarized as     
3:59     
WR Ashb would define variety as the number of distinguishable states or elements in a set which is of course the     
4:07     
model of variety that Ashb expounds in the Evergood regulator theorem     
4:13     
in his cybernetic framework. Variety is essentially a measure of complexity of the number of possible states a system     
4:19     
can exhibit. More specifically, Ashb uses variety as a quantitative concept.     
4:25     
If a system or set has n distinguishable elements, it has a variety of n. So it's     
4:32     
basically um how many elements do you have? That's the variety.     
4:37     
For example, a traffic light with three states red, yellow, and green has a variety of three.     
4:43     
The concept became central to his famous law of requisite variety which of course is key to the ever regulator theorem     
4:51     
which states that only variety can destroy variety. In practical terms, this means that for a regulator to     
4:58     
successfully control a system, the regulator must have at least must have     
5:03     
at least as much variety in terms of complexity or possible responses as the     
5:09     
system it's trying to regulate. A controller with insufficient variety cannot adequately manage a more complex     
5:16     
system. Ashb treated variety is a fundamental building block for understanding regulation, control and     
5:23     
adaptation in cybernetic systems whether biological, mechanical or social.     
5:30     
Okay, so that's the first one. Then the second prompt was how would WRB define a     
5:35     
closed loop ultrastable system? And then uh the answer to that prompt is     
5:43     
that WR Ashb would define a closed loop ultrastable system as a system with two     
5:48     
levels of feedback that can adapt to environmental disturbances by changing its internal organization.     
5:56     
And so this includes a couple of four key features. Um the first is that it     
6:02     
should have two feedback loops. So remember I asked it not how would WR     
6:07     
actually be define a closed loop system or closed loop feedback but a closed loop ultra stable system. So     
6:14     
ultrastability is a is a concept that is not like the one of the main ideas that     
6:21     
the uh cyber nutitions advanced but it is like this is something that if you go     
6:26     
deep into the readings you know you find this concept of ultra stability. So the     
6:32     
key one of the key features of course then is two feedback loops. So a primary feedback loop that operates continuously     
6:40     
to maintain stability under normal conditions and a secondary feedback loop     
6:45     
that activates when the primary loop fails to maintain essential variables     
6:50     
within their critical bounds. Uh number two is step functions. So when     
6:56     
critical variables exceed their acceptable limits, the secondary loop triggers discrete step-like changes to     
7:02     
the systems parameters or structure essentially reorganizing how the system     
7:08     
operates. Number three is self-organization. So this is uh self-organization in the     
7:15     
sense of the cyber daticians not you know necessarily the self-organization that say the people at Santa Fe     
7:21     
Institute talk about. So self-organization the system randomly or systematically     
7:27     
tries different configurations till it finds one that keeps essential variables stable. Once a stable     
7:35     
configuration is found, it persists until the environment changes enough to destabilize it again.     
7:42     
And then they have this homeostat analogy. Ashby's physical homeostat device exemplifies this. It had primary     
7:50     
servo mechanisms maintaining equilibrium or when disturbances were too great. Uni     
7:55     
selector switches would change the systems parameters until a new stable configuration emerged. The ultra stable     
8:03     
designation refers to this metal level of stability. The system is stable not     
8:08     
just through normal feedback but through its ability to restructure itself when necessary. It's essentially a learning     
8:15     
system that adapts to trial and error reorganization when faced with disturbances in its current     
8:21     
configuration cannot handle. So it gives you a lot of sort of details of this     
8:27     
concept and then the third prompt is how would Makulla and Ashby differ in their     
8:32     
definition of feedback. So, this is where I'm I'm going and I'm asking it     
8:37     
about WR Ashb, but I've also trained it on some of Makulla's um correspondences     
8:44     
as well. So, it has a comparator in there. And then, of course, you can go to the internet and find not necessarily     
8:52     
a paper directly on the comparison, but like their papers that McCull has     
8:57     
written on uh feedback and then Ashby's written on feedback. And so it's emphasizing that. So McCulla and Ashby     
9:05     
have fundamentally different conceptions of feedback rooted in their distinct intellectual traditions. Warren McCulla     
9:13     
the neuroysiologist and segmentatician viewed feedback through the lens of circular causality and neural networks     
9:20     
and goal- directed systems. He emphasized feedback as part of a closed loop system where outputs return to     
9:26     
influence inputs enabling purpose of home uh behavior and homeostasis.     
9:33     
His work with Walter Pitz on neural networks focused on circular patterns of activation to produce stable states and     
9:40     
computational functions. W. Ross Ashb, the psychiatrist and     
9:47     
cyberneticist, defined feedback more formally within the framework of regulatory systems in     
9:53     
the concept of variety. For Ashb, feedback was a mechanism for variety reduction, a way systems maintain     
10:00     
stability for counteracting disturbances. His law of requisite variety implied     
10:05     
that feedback mechanisms must be sufficiently complex to match environmental disturbances.     
10:11     
Ashby emphasized the regulatory error coding aspect of feedback and maintaining systems equilibrium.     
10:19     
And the key difference here is that Makoa tended towards a more neurological and computational perspective where     
10:25     
feedback enables complex behaviors and calculations. While Ashb focused on feedback as a     
10:32     
regulatory principle for stability and adaptation. McCulla explored what feedback makes     
10:38     
possible. Ashb formalized what feedback must do to maintain viability     
10:43     
both through central figures in early cybernetics but Ashby's approach was much more abstractly mathematical or     
10:50     
muller closer to biological implementation. So that's the Claude sonnet set of     
10:57     
summaries. I you know the idea here would be to build a workflow where you have some set of prompts     
11:05     
getting the answers to those prompts and then um having like you know revising     
11:10     
them and doing further synthesis. So the idea is, you know, we kind of come up     
11:16     
with prompts not just kind of at random, but kind of     
11:22     
uh almost like, you know, you would develop a pool of prompts and then you'd     
11:28     
kind of refine those prompts so that you get very specific almost like research     
11:33     
questions and then you put them into the um you you use them as a prompt and then     
11:40     
you get some answer out and then you uh basically analyze them and fact check     
11:46     
them to make sure that they're correct. Um and then then we have a nice     
11:53     
synthesis um around this. So this is, you know,     
11:58     
the idea here is to kind of come up with um maybe more pointed questions that people     
12:05     
wouldn't think to ask upon first glance or maybe questions that people would have that are sort of detailed in terms     
12:13     
of the literature. And I know Jesse at one time we we were talking I was talking with Jesse about building like     
12:21     
um uh different models trained on famous people and you know you could ask the     
12:29     
model a question and it would return the answer in the style of that famous     
12:35     
person. And so I I know a number of years ago now we talked about the     
12:40     
Michael Levenbot which is uh some tool that someone made. They trained it on a bunch of Michael Leven's papers and then     
12:47     
you you query the thing and it answers in the style of Michael Leven which is     
12:53     
interesting but it's not like um you know it's not in a research pipeline. So     
12:59     
it's just kind of like entertaining. I don't want to make it just entertaining. I want to actually answer research     
13:04     
questions here and get into the literature in ways that you know maybe we we can and maybe we can't easily do.     
13:13     
So this was the quad sonnet version and then there's the notebook LM version. Um     
13:18     
this is uh ashb and the mechanics of system variety. Um so     
13:26     
uh this has like numbers which are I guess citations. If you go back to the notebook it'll have the links. I didn't     
13:33     
put the links in here yet but um and I just wanted to put it in here so I could     
13:38     
um review it. Uh so WR Ashby describes the concept of     
13:43     
variety primarily as the number of distinct configurations or states a system can assume. He treats this     
13:50     
quantity as fundamentally equivalent to information using logarithmic units such as bits, binary digits to express it     
13:58     
precisely. So this is of course kind of similar to what how uh Claude Shannon     
14:05     
defined information. that's a little bit different maybe and it would be interesting to explore that more maybe     
14:11     
create new prompts based on that or something else. Um so the key aspects of     
14:17     
Ashby's description of variety include uh quantitative measurement. So Ashb     
14:22     
defines the amount of variety or information in a system is a logarithm to the base two of the number of     
14:29     
possible states available to that system. So with um Shannon entropy I     
14:36     
guess it's similar to Shannon entropy the way he thought about it um but he     
14:42     
explicit is explicit about using base 2 and if you you know you work with Shannon entropy sometimes people use     
14:49     
base 2 sometimes people use base 10 um and technically you should be using the     
14:55     
number of or a log to the number of states that you have which gives you an index from zero to on and that's cleaner     
15:04     
than just kind of reporting out a a dimensionless version of of entropy. But     
15:10     
in any case, that's that's, you know, he very he's very much in the same vein as Shannon, although I'm sure if we, you     
15:17     
know, prompt it in a way, it might uncover some subtle differences.     
15:24     
So basically Shannon and Ashby shared the same idea about information and     
15:31     
thinking about variety as as a component of it. Then exponential growth is also     
15:39     
important in variety. He demonstrates that variety of a systems possible organizations increases with extreme     
15:45     
rapidity as a number of its components grows. So that's uh components n for     
15:52     
example in a system of indistinguishable variables where each can be either active or inactive and can be connected     
15:59     
by various arrow patterns the total number of possible types of organization grows at a rate faster than 2n2 which is     
16:08     
of course n^2 to the power or 2 to the power of n^2.     
16:14     
Um and so that's interesting because you know that's something that um     
16:21     
you know is is part of this concept of variety. So then it highlights variety in     
16:28     
biological systems. Ashb applies his measures to biology calculating that the     
16:33     
human genetic inheritance of approximately 50,000 genes provides     
16:38     
50,000 bits of variety. fe each gene can independently assume one of two states.     
16:45     
However, he notes that the richness of a response is not only proportional to the input. Single bit of variety can trigger     
16:52     
a massive pre-established complex organization within a machine. So this is again um     
17:00     
you know drawing on this you know applying his idea of variety to a real     
17:07     
world system. Uh and I have some interesting comments on this. Um so this     
17:13     
is you know very much um thinking about how variety can explode in terms of its     
17:20     
complexity as you add components. So if you add a gene that's a bit if you add a     
17:27     
lot of bits that's a lot of complexity and a lot of particular outcomes of that     
17:32     
system. And then the question is is you know how you know what is a bit is it     
17:38     
the state of a gene is a gene can that be summarized in two states u probably     
17:45     
not there are a lot of states within that gene that you can represent. So this is kind of a thing where you know     
17:52     
it's nice to know how what the definitions are so you can work from them.     
17:57     
Then the variety of human action. So to provide a practical measure or to find a     
18:03     
practical measure for the variety of human behavior, Ashby suggests counting the number of verbs in a dictionary. He     
18:10     
estimates that a typical person has a repertoire of roughly 10,000 characteristic actions representing the     
18:17     
systems output variety. Uh conversation and destruction of     
18:23     
variety. So a central tenate of Ashb's theory is that an absolute system or a deterministic machine cannot generate     
18:30     
its own variety. The output of information from such a system is exactly equal to the input it receives     
18:37     
from its parameters. Over time, variety in an absolute system typically decreases as the line's     
18:44     
behavior converge towards a neutral point or cycle. These convergent     
18:49     
junctions act as sinks where information is destroyed. So it's bringing in a little bit about complex or dynamical     
18:56     
systems in here where you have um limit cycles and other types of attractor     
19:03     
basins. And that's kind of interesting. You could ask it again. You know what?     
19:09     
How does Ashby's concept of variety uh square away with square away is a     
19:16     
good prompt, but uh square away with dynamical systems theory, limit cycles,     
19:23     
attractors, things like that. Um then there's the requirement for     
19:29     
adaptation. So Ashb suggests that for an environment to be adaptable, it must not be total chaos of infinite variety. uh     
19:37     
instead the world must contain a large proportion of part functions which allow the environment to be functionally     
19:43     
divided into smaller manageable subsystems that an organism can adapt to     
19:48     
independently. Then ultimately Ashb views variety as the raw material of regulation for a     
19:54     
system to remain stable in a changing environment and must possess sufficient internal variety to counter the variety     
20:01     
of disturbances it faces. So that is on systems variety.     
20:08     
Then Ashb step functions. So this is um     
20:13     
I I guess I'm not really I can't really remember what the actual prompt was here     
20:19     
but um so this this continues on in the     
20:24     
cybernetic theories of W or ashb step functions often referred to as breaks     
20:30     
are the fundamental mechanism that allows a system to alter its own internal organization to achieve     
20:36     
adaptation in what Ashb calls a mix system variables are categorized into a     
20:42     
hierarchy. Null functions permanently constant step functions constant for     
20:48     
intervals but subject to sudden jumps. Part functions constant over finite ranges and full functions which are     
20:55     
continuously varying. Uh the specific rules of step functions in these systems are as follows. So     
21:03     
there are five here. Um and again we're talking about you know     
21:09     
systems and change and adaptation. This is sort of almost like we're describing     
21:15     
something very similar to like um a phase transition in     
21:22     
a biophysical or a physical system. So we're thinking about these discontinuities in and change over time.     
21:31     
So the first is parameters of organization. Step functions act as the parameters of organization for the     
21:38     
continuously varying variables or full functions of the system. While the full     
21:43     
functions represent the immediate behavior of the system, the step functions determine the set or field     
21:50     
uh the rules of interaction in other words under which these variables operate. A change in step function value     
21:57     
effectively transforms the system into a different machine with the new set of behaviors.     
22:03     
The second is the mechanisms for breaks and adaptation. Step functions are the     
22:08     
essential components of ultrastable and multi-stable systems. Uh triggering change when the systems     
22:15     
vital variables essential for survival exceed specific limits defined as     
22:20     
critical surfaces or break surfaces. A step function suddenly jumps to a constant value.     
22:28     
Trial and error. This breaks this break resets the organization of the system providing a new field for the variables     
22:35     
to explore. This continues in a trial and error fashion described by hash via     
22:40     
heads I win. Tails we toss again until the system strikes an organization where     
22:46     
the variables remain within the safe bounds and a stable equilibrium is reached. Uh number three is simplifying     
22:53     
the search for stability. In a mixed system, step functions contribute to the     
22:59     
efficiency of finding equilibrium. Because step functions are constant for finite intervals, they are considered to     
23:06     
be already in equilibrium by definition. It reduces the dimensionality of the     
23:11     
dejustment problem. The system only needs to adjust its continuous flow functions relative to the fixed values     
23:18     
of the step functions. Ashb noted that this significantly increases the probability of a system reaching a     
23:25     
stable state quickly. Uh number four is enabling localized adaptation or multi-stability.     
23:32     
In more complex multi-stable systems, step functions allow the system to adapt     
23:37     
in bits rather than all. Because step functions only affect certain parts of the system, a break or     
23:45     
change in one area can occur without necessarily disrupting previously established adaptations of other areas.     
23:52     
This is functionally similar to how genes operate in an organism. A mutation in one gene can alter a specific trait     
24:00     
without collapsing the entire biological structure. And then finally, social and biological     
24:06     
representation. Ashb applied the role of step functions to broader contexts. So in a social     
24:12     
system, the passing of a new law represents a step function change that occurs when a social variable exceeds a     
24:19     
critical threshold such as a crime rate. And so this is uh again thinking about     
24:27     
these broader systems and how Ashby's uh ideas apply to that.     
24:33     
Step functions are also the neurohysical neurohysiological equivalent of genes     
24:40     
provided that by the gene pattern to protect the organism's vital variables to inherited or learned adaptations.     
24:47     
So we have this sort of summary of uh systemic adaptation and thinking about     
24:54     
ashb's views on adaptation which I think was sort of the original prompt for this.     
25:01     
Then finally we have some a prompt on the dynamics of closed loop systems. So     
25:07     
this is where I actually asked bit about ashb's views on closed loop systems. Um     
25:12     
just that specific thing. And so then you know this kind of gives detail on     
25:18     
ashb's views on this first order closed feedback that we often think about as sort of a     
25:25     
central kernel of cybernetic regulation. So WR Ashby would describe closed loop     
25:31     
feedback primarily as a state of effective two-way interaction between components within a system. He defines     
25:39     
feedback as being present if we can find two variables that are dependent on the other.     
25:45     
This interaction forms a circuit where the behavior of one part is influenced by the other and this influence     
25:51     
eventually returns to the first part. Ashb identifies several key characteristics and insights regarding     
25:58     
closing feedback. The first is uh feedback as a closing link. So it it provides closure. Drawing     
26:07     
on the theory of servo mechanisms, he notes that a human operator can be considered part of a control system     
26:14     
acting as the closing link that takes account of the difference between actual output and desired output to alter the     
26:21     
input. Then we have necess the necessity of oscillation. So Ashb posits that if     
26:28     
variables of an absolute system undergo a recurring cycle of behavior, feedback must be present. He argues that     
26:35     
variables cannot be interconnected in a way that produces oscillation without forming a circuit.     
26:41     
Feedback and goal seeking. While many associate feedback with purpose of behavior, Ashb argues that goal seeking     
26:48     
behaviors do not necessarily imply feedback, simple systems without     
26:53     
feedback and still return to a central state when displaced. However, a powerful acting servo     
26:59     
mechanism utilizing feedback can act act uh can add a powerful stabilizing effect     
27:06     
making a machine more irresistible to opposition and ensuring it converges to     
27:11     
zero error more rapidly. Critique of negative feedback. Ashb     
27:17     
considers the concept of negative feedback to be too limited and simple to serve as a fundamental concept in     
27:22     
general systems. He demonstrates that it is algebraically possible for positive     
27:27     
feedback to result in stability and for negative feedback to result in instability depending on the values of     
27:34     
the coefficients within the systems matrix. Feedback is a selective change     
27:40     
mechanism. In his theory of the ultrastable system, feedback is the mechanism by which the system perceives     
27:46     
pain or a threat to its essential variables. This feedback loop informs     
27:51     
the system that it is that its current internal organization is failing to maintain stability there thereby     
27:59     
triggering a reset or change in step functions until a new state equilibrium is found. Uh feedback through the     
28:06     
environment. Ashb emphasizes that a complete dynamic system often includes the environment as a feedback link. For     
28:14     
instance, a person driving a car is part of a functional loop where their actions affect the environment which is the     
28:21     
car's position and the environmental feedback which are visual signals from     
28:26     
the road. This uh environmental feedback travels back through the driver's brain to     
28:32     
correct the initial movement. So ultimately Ashb views simple feedback     
28:37     
as a subset of more complex reacting circuits. you know that for part of the system to behave with more stability     
28:43     
than it possesses intrinsically feedback is a necessary condition.     
28:51     
So I'm keeping these in this model queries folder. I'm going to uh     
28:56     
elaborate at the read me. I'm going to elaborate a lot of the details about the models. I'm what what's interesting     
29:03     
about this is like I prompt it with something and it gives me this output and then I it's interesting that you     
29:10     
know you can find things that are really intriguing to you know maybe things we're talking     
29:16     
about in the group and then find that little thing and query that and keep building from there. Um, it also makes     
29:24     
me think that maybe I want to build a Claude Shannon bot as well or Claude Shannon um model where we have like, you     
29:31     
know, every time we kind of bring in a new person into the conversation, bring that in or build a customized uh model     
29:39     
for with like just Ashby and Shannon and just kind of like refine things like     
29:44     
that and see what we come up with because it's a, you know, it's a lot of stuff that like Ashby wrote.     
29:52     
a huge number of of things in his career and like just kind of you know all his     
29:58     
notebooks everything those are actually all online and they're available through     
30:04     
the University of Illinois library where you know he had his notebooks he had like all these concepts some of them he     
30:10     
followed up on in um in you know in papers that we can read     
30:18     
and some of them we can't so it's nice to have a tool that can extract some of that and kind of make connections in     
30:25     
ways that you might not be able to make at first glance and then kind of build from there. And then, you know, that     
30:31     
that builds upon something you can then research later in other ways and um kind     
30:38     
of verify a lot of it and um you know, just have a I guess have a richer uh     
30:45     
synthetic experience. You know, I I never tried Levvenbot,     
30:52     
you know. Oh, yeah. Yeah. It's     
30:57     
um I mean certainly um I mean, well, you     
31:03     
you got enough Levan video that you could actually make a     
31:09     
an AI AI video of him talking. Oh, you could. Yeah, definitely.     
31:15     
Uh but um yeah, I mean it is it is it's     
31:20     
interesting when you you with someone who's got a lot of a lot of     
31:27     
text. Um, you can make something that is um I mean I I've I've uh     
31:36     
um I forget what this channel is, but it's um somebody made an AI Christopher     
31:43     
Hitchens. Oh, yeah. And and on on YouTube and so they've got the     
31:52     
same, you know, they they've got his     
31:58     
diction um just     
32:03     
perfectly like like like it's talking like him.     
32:09     
It's it's got his his turns of phrases and and you know     
32:16     
um biting biting wit or like cutting     
32:22     
cutting uh attacks. Um um     
32:28     
and you know like like that is certainly something where they they go back uh I     
32:35     
mean it's crazy how long you know like you've got video of him going back to like     
32:41     
recordings of him going back to the 80s right so it's just like I think it's one of those things where     
32:47     
it's just like somebody who's been a talking head for as long as he has like you can actually capture quite Well,     
32:54     
oh yeah. And even though you've got him talking about, you know,     
32:59     
Venezuela or something like that, like something in the, you know, like like it     
33:04     
sounds exactly like it. Um     
33:10     
um so so that so that's interesting. Um and uh yeah, now like what     
33:21     
how can you you know, release that for good. I mean, in the     
33:28     
sense of like like what what goals, you know, so the Christopher     
33:35     
Hitchens thing, right? Like it's just like like yes, it's kind of nice to have someone     
33:41     
um cutting cutting down your enemies.     
33:49     
Yeah. But I but I'm not sure the the the productivity value of that.     
33:55     
Um you know like like what can we what can we learn from one of these one of     
34:02     
these um bots if you will.     
34:09     
Um I mean I I'm I'm really curious on the     
34:16     
um brain GPT, right? So, so this is the Brad Love     
34:22     
project that is um     
34:30     
uh that is uh um trained on neuroscience     
34:36     
papers to     
34:42     
make predictions about a new study. So it's like you give it you give it a an     
34:51     
experimental design plan and then it it's trained on all these     
34:58     
papers and it makes a prediction of what you'll     
35:04     
find. Okay. Yeah. for you know um and     
35:14     
I think the Brad Love idea here is that um     
35:21     
yeah that it would be you know a useful assistant.     
35:30     
I mean, you know, like like that it could potentially point out something     
35:35     
uh problematic with your design, right? You know,     
35:42     
um uh or or that, you know, you're missing a control condition or something like     
35:48     
that. Yeah. you know.     
35:53     
Um so um     
36:05     
it's at least one example of like somebody who's tried,     
36:11     
you know, been thinking about um somebody posted on Nate X's Slack about     
36:17     
a um an EEG rag. So, what's this?     
36:25     
Retrieval. Oh, right. What's the A and generalization or something like     
36:30     
that? Okay. Okay. Um,     
36:37     
so it seemed to be like suggesting papers or something and and I I was just like, okay, what's     
36:46     
I I still wasn't quite sure what it was doing. And then I said, um,     
36:54     
okay, so like one of the co-founders, Ner Techch X, had a paper about deep learning and EEG back in, um,     
37:03     
like 2018 or 2019 or something like that. I was like, would this, you know,     
37:10     
like is this something where um I I could, you know, like could I put     
37:17     
together a review paper of of on deep learning EEG     
37:25     
e easier or you know like like I I still wasn't quite sure     
37:34     
Um, you know what what a a bot trained on EG     
37:43     
papers would be able to um     
37:48     
do. Yeah. He he he would be able to do I mean he he said like it could suggest it could     
37:54     
suggest interesting papers or something like that. Like I mean you know I I honestly find I mean     
38:02     
I find Gemini's recommend you know like when I if I set a problem of like     
38:09     
you know who's who's working on um a variational inference appro or like     
38:17     
a simulationbased inference approach for tissue microructure.     
38:24     
um that you know has some other particular detail like like     
38:32     
I think I find it quite interesting how     
38:37     
close close a     
38:42     
find that Gemini can do that that wouldn't have come up with my     
38:50     
kind of keyword keyword search on PubMed, right?     
38:56     
Like like it it wouldn't have come up that way. Like like you almost needed     
39:05     
Yeah. You know, it's like     
39:12     
it definitely seems to be trained on the papers. Yeah. Yeah. So you can try and you can     
39:19     
like go to rag embedding from you know different sort of customized     
39:24     
sources and then use that as sort of a way to I mean in in one way it's self-referential because it's kind of     
39:31     
like this is what I'm training now this is kind of the world of uh what I want to know but like on the other hand it     
39:37     
does you know kind of cut through like it it it shortens your time to because     
39:43     
like in a keyword search you're often times constrained by your keywords, you know, getting ex them exactly right or,     
39:51     
you know, finding things that um, you know, you may it may be way down in     
39:56     
the list versus at the top of the list, things like that. So, you know, I I I don't I haven't really explored it that     
40:02     
much except to say that like that's like, you know, there are some uses that     
40:08     
obviously exceed keyword search. Yeah. you know, I I I I've I've really     
40:15     
liked it. I mean, I've I've I've found it to be quite spot-on     
40:24     
um in finding finding similarity,     
40:31     
finding a deeper similarity. Yeah. you know, and and that means but     
40:38     
potentially, you know, like the person's not necessarily working on the area that     
40:44     
I'm talking about, but but computationally they're using     
40:51     
an approach that I should learn from.     
40:56     
Yeah. Which is pretty cool. I mean in some of these cases that like like I said like     
41:02     
I've been using the agentic development     
41:07     
to do the wrapping you know so it's just like find me an approach     
41:13     
and that that comes with a an open source codebase right     
41:19     
and then and then I can wrap that and then use it as a test article or um etc.     
41:27     
Right. Um, and yeah,     
41:33     
again, it's it's it's been it's been um,     
41:40     
you know, I don't     
41:46     
I'm I'm ready to pay $200 a month.     
41:53     
Yeah. Yeah, for the the um the     
41:59     
awesome power of Well, I was gonna not not for the um the     
42:08     
chat service, but um so Ed Edison Discovery or what was I forget what the     
42:15     
company. So future house is this like Schmidt Futures     
42:20     
project to do     
42:26     
like like scientist     
42:32     
and so and the idea is that like you pay 200 a month and you get some amount of     
42:38     
credits that you can run and they're definitely training on papers, right?     
42:45     
Now, yeah, I I don't know whether I'm ready     
42:52     
to put down $200 just to satisfy my curiosity on what how that would be different.     
42:58     
You know, I I feel like these models are already trained on all the papers anyway.     
43:05     
Um Yeah. Yeah. But still still still on the     
43:14     
hunt for for finding some value here for using up all our water and     
43:21     
and energy resource. Um yeah, I mean and the thing is is like     
43:27     
you know you have very specific things you want to know. you you want to make sure I I don't know     
43:34     
what the training set is that it might go out on the internet and find things,     
43:39     
but I guess the having the local kind of training refines it down to, you know,     
43:46     
it gives it maybe more specific pointed information that may or may not be in the original training. So, so that's     
43:52     
that's kind of one of the advantages of using local training. But, um, yeah, I don't know. I don't     
44:00     
know what the the actual I mean like I said the first thing you would want to do in using in a research context is     
44:07     
figure out sort of the workflow for how you want to use it then you understand     
44:12     
kind of where its place is a little bit better. So you know things like you know finding     
44:19     
prompts much as you know it's not using it as like a search engine but it's a asking     
44:26     
it pointed questions getting structured answers and then refining those structured answers with additional     
44:32     
prompts finding the uh interesting connections um and then and then being able to go     
44:39     
from there. So yeah, I yeah, it's just, you know, so     
44:45     
this is just an experiment and and we're going to keep working on it and we'll see where it goes.     
44:50     
Um I think in it is in the spirit of cybernetics because you're building these feedback     
44:57     
models and you're using machines     
45:02     
uh intelligence augmentation to do     


Transcript for "JoPro Year in Review 2025"    
    
0:00     
All right. So, I'm going to review uh     
0:04     
Jesse's Joe work. Um he recently sent     
0:08     
out an email. This is actually a post on     
0:10     
a on the Job Pro Substack     
0:13     
and it's discussing sort of progress     
0:16     
made in 2025 reviewing some of the     
0:19     
things that have been sort of     
0:20     
foundational in 2025 and will hopefully     
0:24     
help build to subsequent years.     
0:27     
So, I'm going to go through this email     
0:29     
and I'm going to talk a little bit about     
0:31     
some of the things we discussed in the     
0:32     
last week. Um, a lot of things,     
0:36     
interesting things bubbling to the     
0:37     
surface with respect to JPro.     
0:41     
So, uh, this was, uh, a year-end review     
0:44     
post. Um, so this year, meaning 2025,     
0:48     
many of the people we worked with, these     
0:50     
include researchers, practitioners, and     
0:52     
builders across fields, share a similar     
0:55     
concern. They were learning quickly,     
0:57     
adopting new tools, and meeting the     
1:00     
expectations placed in front of them.     
1:02     
Yet, many felt uncertain about how their     
1:04     
work fit together, how to make decisions     
1:07     
with long-term consequences or how to     
1:09     
grow into roles that require more     
1:11     
execution, more than execution alone. So     
1:14     
this is something where you know we've     
1:16     
been exploring this uh topic in the     
1:19     
orthogonal web quite a bit where we're     
1:21     
thinking about synthesis and     
1:23     
synthesizing a lot of the ideas that we     
1:26     
kind of throw up in the air in our     
1:27     
meetings, our weekly meetings and in our     
1:30     
other kind of specialized meetings and     
1:33     
you know we put out a lot of papers but     
1:35     
we never go back and sort of integrate     
1:37     
those things. And in fact, from my     
1:41     
administrative work in the orthogonal     
1:43     
web, I can tell you that this is     
1:45     
something we're working harder on now     
1:47     
because we need to sort of reflect on     
1:50     
where we've been, especially when you do     
1:53     
a lot of work and then that kind of just     
1:55     
gets lost and you need to have insight     
1:58     
going forward, but you don't necessarily     
2:00     
have that insight     
2:02     
because the pressure is always go to is     
2:04     
always to go to the next big thing. What     
2:06     
stood out was not confusion, but a lack     
2:08     
of orientation, a sense that the systems     
2:11     
engulfing us offer brittle outputs and     
2:14     
legacy credentials with a pronounced     
2:16     
lack of guidance for becoming     
2:17     
responsible wayfinding actors within     
2:20     
complex evolving fields.     
2:23     
And so we actually do a lot of     
2:25     
interdisciplinary work in the orthogonal     
2:27     
web. And that resonates I think with a     
2:30     
lot of not just what's going on in the     
2:32     
orthogonal web but a lot of other um     
2:35     
groups research groups and um working     
2:39     
groups that we are interacting with. And     
2:42     
so it makes sense to build not just to     
2:44     
build tools for integration but to     
2:47     
engage in the practice of synthesis and     
2:49     
integration of ideas. the formation of     
2:52     
discernment, building coherence beyond     
2:54     
disciplinary silos and the ability to     
2:56     
navigate uncertainty     
2:58     
are increasingly treated as discrete,     
3:01     
private or even irrelevant problems. So     
3:04     
this first link is to the these notes on     
3:06     
community and leadership in the wake of     
3:08     
stability. This is something that Jesse     
3:10     
wrote in 2025 on June 11th.     
3:14     
uh this kind of talks a little bit about     
3:17     
thinking about problem spaces and how     
3:20     
you approach these. I think we've talked     
3:22     
about this in the Saturday morning     
3:24     
narosim meetings um enough so that we     
3:27     
don't have to spend too much time on it     
3:30     
but basically um you know having to sort     
3:33     
of work around     
3:36     
uh problems communicate vision properly     
3:39     
and the sort of the the consequences of     
3:42     
not doing that. Then he goes on to say     
3:44     
one here is a growing resignation. This     
3:47     
is out of our hands.     
3:49     
To better to look away or focus     
3:51     
elsewhere or else when that posture sits     
3:55     
uneasily besides the agentric rhetoric     
3:57     
of flourishing center technologists,     
4:00     
ethically courageous innovators were     
4:02     
indeed philosopher builders. The more     
4:05     
generative stance has often been quieter     
4:07     
and more demanding. That is nobody     
4:09     
taught us how to do what this moment     
4:11     
requires. So we are teaching ourselves.     
4:15     
This post refers to uh this event that     
4:18     
uh Jesse attended at the Cosmos     
4:20     
Institute where they uh had they sort of     
4:24     
styled themselves as an academy for for     
4:27     
they styled themselves as an academy for     
4:30     
philosopher builders.     
4:33     
And so this is something that he's     
4:35     
trying to replicate in Jopro. Speaking     
4:37     
of philosopher builders, as Brendan     
4:39     
McCord noted during the Cosmos     
4:41     
Institute's year end note, technology     
4:43     
that expands what is possible may narrow     
4:46     
who is possible, but it need not. I     
4:49     
would extend that observation beyond who     
4:51     
to where. When the range of who is     
4:53     
possible contracts, so too does the     
4:55     
range of futures we can chart along with     
4:58     
the institutional and epistemic pathways     
5:00     
that make those futures reachable. So     
5:03     
very much about inclusion but also uh     
5:07     
thinking about how the things that we     
5:09     
adopt in our organizations     
5:12     
enable or disable that sort of inclusion     
5:15     
and then harnessing the potential of     
5:17     
your organization to make change and do     
5:20     
great things. So again, and then he goes     
5:22     
over the moment we find ourselves in.     
5:24     
For much of the last century, our     
5:26     
institutions for learning, research, and     
5:28     
innovation were designed around narrower     
5:30     
assumptions. That is clearer     
5:32     
disciplinary boundaries, slower feedback     
5:35     
cycles, and more homogeneous pathways     
5:37     
into expertise and authority. So again,     
5:40     
consolidating things around a     
5:42     
hierarchical structure and having this     
5:45     
sort of limited amount of feedback as     
5:48     
opposed to the sort of fast iterative     
5:50     
feedback that we might have um that we     
5:54     
have maybe in in the modern day in     
5:57     
something like agile management or you     
5:59     
might find in small startups, technology     
6:02     
startups. You don't necessarily find     
6:04     
this in um in learning and research     
6:08     
institutions.     
6:10     
Even then, many forms of knowledge,     
6:12     
expertise, and responsibility were     
6:14     
marginalized or excluded. So again, this     
6:18     
sort of maybe unintentionally or maybe     
6:20     
sometimes intentionally excluded a lot     
6:23     
of viewpoints that may have been     
6:24     
valuable to formulating good     
6:28     
conclusions, uh making change and things     
6:31     
like that.     
6:33     
Today, as complexity accelerates and     
6:35     
domains collide, those limitations are     
6:38     
no longer merely unjust or inefficient,     
6:40     
they are structurally misaligned with     
6:42     
the kinds of problems people are now     
6:44     
being asked to work on.     
6:46     
The challenge is not that we've lost the     
6:47     
golden age of formation, but that we are     
6:50     
encountering at scale the consequences     
6:52     
of institutions that were never built to     
6:54     
support integrated comprehensions, cross     
6:57     
field coordination, or long horizon     
7:00     
responsibility in the first place.     
7:02     
Joe exists because those gaps keep     
7:05     
showing up in practice across fields,     
7:08     
institution, and career stages.     
7:11     
It shows up when interdisciplinary work     
7:13     
collapses under the way to mismatched     
7:15     
assumptions and timelines.     
7:18     
And it shows up when conversations about     
7:20     
ethics or responsibility are detached     
7:22     
from the lived realities of learning,     
7:24     
leadership, and decision-m.     
7:27     
Over time, it became clear that     
7:28     
addressing this gap could not be done by     
7:30     
focusing on any single pro program,     
7:33     
discipline or institution in isolation.     
7:37     
So this these challenges uh are not     
7:40     
failures of individual effort but of     
7:42     
surrounding ecosystems people are asked     
7:44     
to operate within.     
7:47     
And so this shaped how uh the vision for     
7:51     
Joe evolved over the year. Instead of     
7:54     
treating Joe Pro as a standalone     
7:55     
platform or pipeline, we increasingly     
7:58     
understood our work as part of a broader     
7:59     
landscape, one that depends on     
8:01     
relationships between groups, shared     
8:04     
language across domains and people     
8:06     
willing to take on the work of     
8:07     
translation and coordination.     
8:10     
In other words, the question became not     
8:12     
just what we build, but how the     
8:14     
conditions for building and becoming are     
8:16     
cultivated.     
8:18     
Um, so this is really kind of going over     
8:20     
some of the Joe Pro events this year     
8:22     
that took many forms. And this is a     
8:24     
figure showing some of the things that     
8:25     
were going on. So this is the Metagv     
8:28     
space makers project with plot twisters.     
8:32     
There's uh an attendance at fact which     
8:35     
is of course the uh technology ethics     
8:39     
section of the ACM.     
8:42     
There was participation in wei robot     
8:44     
2025 as well as participation in Google     
8:47     
summer of code.     
8:49     
There were these Joe Pro socials, so     
8:51     
online socials where you know these     
8:53     
topics were discussed,     
8:55     
the spring expo at UC San Diego for     
8:58     
educational innovation.     
9:01     
And then some part educational     
9:03     
participants here, things especially the     
9:06     
human augmentation summit which Jesse     
9:08     
attended and some images of that. So a     
9:12     
lot of participation this year.     
9:15     
So some of the highlights uh we continue     
9:17     
deep collaboration with orthogonal     
9:19     
research and education lab Joe per's     
9:21     
longtime partner particularly through     
9:24     
the science society ethics technology     
9:26     
working group together we explored     
9:28     
questions of project management     
9:30     
leadership and coordination and research     
9:32     
and innovation spaces topics that are     
9:35     
rarely treated as first order concerns     
9:37     
but which often determine whether good     
9:39     
ideas survive contact with reality.     
9:42     
They also uh stayed closely connected to     
9:45     
plot twisters, a Joe Pro sister group     
9:47     
building on the work supported by Open     
9:49     
Ido and the designing for digital     
9:52     
thriving grant and Metagv's governable     
9:55     
spacemaker fellowship.     
9:57     
Plot twisters exemplifies the kind of     
9:59     
experimental practiceoriented inquiry we     
10:02     
believe is essential for understanding     
10:04     
agency and narrative digital spaces and     
10:07     
individual and community sensem is     
10:10     
tractable design challenges rather than     
10:12     
abstract problems.     
10:14     
Uh so the events that Jerpo participated     
10:17     
in um of course there's this advancing     
10:21     
humans with AI community based out of     
10:23     
MIT where there's an emphasis on human-     
10:26     
centered AI which aligns closely with     
10:28     
our own concerns     
10:31     
and there's also participation in the     
10:34     
distributed AI research institute     
10:37     
particularly around the possible futures     
10:39     
workshop series.     
10:41     
Uh there's also engagement with the     
10:43     
Cosmos Institute and participation in     
10:46     
the Oxford AI times philosophy seminar.     
10:51     
A reminder of how valuable serious     
10:53     
philosophical engagement remains in     
10:55     
technical domains.     
10:58     
In more applied and embodied spaces,     
11:00     
JoeRo members attended events hosted by     
11:02     
groups like Augmentation Lab and we     
11:04     
exhibited at the AUG Lab Summit at the     
11:06     
MIT Media Lab. In addition to supporting     
11:10     
the summit, our colleagues at Echolapto     
11:13     
convene numerous salons and events     
11:15     
across crucial frontiers, creating space     
11:17     
for reflective engagement with questions     
11:20     
of technology,     
11:21     
cognition, futures, and human     
11:23     
experience. Together, these environments     
11:26     
challenged us to think more carefully     
11:27     
about how narratives, interfaces, and     
11:30     
systems shape human capability.     
11:33     
Um, we also engage with communities     
11:35     
focused on values, responsibility, and     
11:38     
career pathways, including the school     
11:40     
for moral ambition, whose work on     
11:43     
alternative and impactful career     
11:44     
trajectories resonates strongly with     
11:46     
many in our network. We reconnected with     
11:50     
collaborators at Princeton Envision as a     
11:52     
Revi Envision conference series with     
11:54     
renewed emphasis on data ethics and     
11:57     
responsible AI.     
12:00     
In terms of what was advanced this year,     
12:03     
um, across research, pedagogy, and     
12:05     
community work, we were asking a     
12:08     
consistent question. What does it look     
12:10     
like to design learning, inquiry, and     
12:12     
leadership structures that are actually     
12:14     
responsive to the conditions people are     
12:16     
navigating? Now,     
12:19     
so throughout the year, much of our work     
12:20     
focused on education and learning     
12:22     
ecosystems.     
12:24     
We formalized what we have been     
12:26     
developing implicitly for years into a     
12:28     
framework we call Joe and the new     
12:30     
learning ecosystem.     
12:33     
This work articulates an approach to     
12:35     
learning that is contextual,     
12:36     
developmental and trajectory aware     
12:39     
designed for interdicciplinary spaces     
12:41     
where people are often navigating     
12:43     
multiple identities, skill sets and time     
12:46     
horizons all in the same context.     
12:51     
We shared this framework in the spring     
12:53     
at the UC San Diego Education Innovation     
12:56     
Expo,     
12:58     
using it to demonstrate how pedagogy,     
13:00     
technology, and mentorship can be     
13:02     
designed together rather than treated as     
13:04     
separate layers. That same philosophy     
13:07     
guided our participation in Google's     
13:09     
summer of code through orthogonal     
13:11     
research and education lab sponsored by     
13:14     
the INCF     
13:16     
where Joe pro supporters supports     
13:19     
scholars contributing to open source and     
13:21     
research projects at the intersection of     
13:24     
computation biology and ethics. These     
13:27     
efforts reinforced a core belief.     
13:29     
Meaningful learning happens when people     
13:30     
are embedded in real problems with real     
13:33     
responsibility and adequate scaffolding.     
13:37     
Then as the year progressed into the     
13:39     
fall, Joe exhibited at the human     
13:42     
augmentation summit hosted at MIT Media     
13:44     
Lab, contributing to conversations about     
13:47     
human potential augmentation and the     
13:50     
social consequences of emerging     
13:52     
technologies.     
13:53     
Members of our community also engage     
13:55     
with global research communities through     
13:57     
conferences like ACM conference on     
13:59     
fairness, accountability, transparency     
14:03     
and that's the fact uh section of the     
14:05     
ACM     
14:07     
uh under the data times direction banner     
14:10     
exploring questions of fairness     
14:12     
accountability and participary     
14:14     
approaches to AI. So running alongside     
14:17     
this public work was a deeper strand of     
14:19     
research and sensemaking. Over the     
14:21     
course of the year, we developed     
14:23     
something in the way, an ethnography of     
14:25     
21st century directionless     
14:28     
directionlessness,     
14:30     
a project in the mental health paradigms     
14:32     
and perspectives working group, which is     
14:34     
a working group within Jobro aimed at     
14:37     
documenting what it feels like to be a     
14:38     
drift in contemporary life     
14:40     
professionally, cognitively, and     
14:42     
morally. Drawing from ethnography and     
14:45     
phenomenology rather than optimization     
14:47     
frameworks, this work shaped how we     
14:50     
think about mentorship, leadership, and     
14:52     
learning. Not as linear pipelines, but     
14:55     
as processes that must account for     
14:56     
uncertainty, fragmentation, and uneven     
14:59     
development. Later in the year, many of     
15:01     
these threads came together. In     
15:03     
December, we launched Digenest, which is     
15:06     
stands for digital narratives and     
15:08     
emerging story technologies, a new     
15:10     
rating group and discussion space     
15:13     
exploring narrativity, agency, and     
15:15     
emerging technologies.     
15:17     
Digeness sits at the intersection of     
15:19     
digital humanities, philosophy,     
15:21     
psychology, and design, and reflects     
15:24     
Joe's conviction that questions of     
15:26     
ethics and governance are inseparable     
15:29     
from questions of story, identity, and     
15:32     
meaning making. In many ways, Digenist     
15:36     
represents a synthesis of this year's     
15:38     
work, a space where research, pedagogy,     
15:40     
and community converge.     
15:43     
uh running through it all was a quieter     
15:45     
but essential effort which was field     
15:48     
based on field building and mentorship     
15:51     
projects such as from here to there and     
15:54     
data times direction both of which are     
15:57     
spin-offs from my capstone course work     
15:59     
at UC San Diego are not products in the     
16:02     
conventional sense rather are attempts     
16:04     
to offer language structure and guidance     
16:07     
for people navigating complex innovation     
16:09     
landscapes without clear maps data times     
16:13     
action in particular had a wonderful     
16:15     
initial internship cohort and serves as     
16:18     
a growing community within the broader     
16:19     
Joe umbrella.     
16:22     
These efforts reflect a belief that     
16:24     
leadership today is less about authority     
16:26     
and more about helping people orient     
16:28     
themselves intellectually, ethically,     
16:31     
and strategically over time. This year's     
16:34     
activities are the 2025 activities in     
16:37     
JPro, created shared reference points,     
16:41     
new vocabularies, prototypes for     
16:43     
learning, inquiry, and collaboration     
16:46     
that can continue to evolve. As an     
16:48     
organization, we continue to practice     
16:50     
incubation for projects and then growing     
16:53     
our capacity to cultivate context and     
16:56     
capacity. And so in the coming year, um,     
16:59     
a lot of these things will continue and     
17:01     
and grow and thrive hopefully. So I     
17:04     
think that's a good overview of what's     
17:06     
going on in Joe. Thank you for Jesse for     
17:09     
preparing this and putting it on his     
17:11     
Substack. Um I think you know he     
17:14     
mentioned to me that there's sort of     
17:17     
this immense pressure to create a media     
17:19     
brand and sometimes you know when we     
17:23     
produce content or what we might call     
17:25     
content in academia you know they call     
17:28     
it papers or presentations but     
17:30     
essentially it is content there remains     
17:33     
this sort of pressure to have a unified     
17:36     
brand or a unified theme that is you     
17:39     
know easy to sort of past people as so     
17:43     
you know the idea is you know I know     
17:45     
that person that's a that's a a certain     
17:47     
type of person they do a certain type of     
17:49     
thing and it sort of subsumes a lot of     
17:52     
the other things that they do or a lot     
17:55     
of the connections they make with other     
17:56     
things uh so if I say someone is a data     
17:59     
analyst or someone does cognitive     
18:03     
science or they're a certain area of     
18:05     
cognitive science that kind of shortells     
18:08     
what they actually can do and short     
18:10     
sells their potential     
18:12     
I think that's interesting uh from the     
18:15     
standpoint of interdisiplinarity.     
18:17     
Uh we also talked about the potential to     
18:19     
set up uh different types of uh content     
18:23     
which involve interviews with people     
18:26     
such as myself     
18:28     
as well as s sort of short uh     
18:31     
reflections on some of these issues. And     
18:34     
so look forward to that um in the next     
