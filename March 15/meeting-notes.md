## Meeting Recording

[YouTube link](https://youtu.be/pm-ZNpUke74)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114168104525374042)

## NOTES
Shyam: interested in this year'a GSoC. SWARM/LLM --> 

Qs: scope --> swarm, multiple agents.

* from a few to many. Management systems --> state of system stored.

* majority-swarm, SWARMS Python package.

* coordinate different student chapters. 


Work on education material -- support NeuroTzechX software initiatives (most starred -- MOABB).

* getting students involved, knowledge is only things that grows --> shared.

* arXiv paper -- EEG Benchmark -- MOABB paper.

* coding and data munging projects. Different expertise levels. 

* organoid news. 


NCAs and Cellular Automata --> how do biological simulations work?

* essay on "Unreasonable Ineffectiveness (intractability) of Mathematical Biology" (https://en.wikipedia.org/wiki/Unreasonable_ineffectiveness_of_mathematics)

* models in developmental biology --> what features do we want to extract short of a finite element model --> capture 
the flow. 

* model flow --> how much is cell adhesion changing, no one cell is "in charge" (adjacency-driven).

* how can we use CGS systems and Lagrangian Coherent Sturctures to model flows (cultural and biological systems).

* models of life --> what we think "life" is (flows, autonomy, emergence, discrete/continuous)?

* models don't capture vertical aspect --> only interesting end points. Multiscale.


Figure 1. Attenpt to capture "fuzzy database" aspect of LLMs.

* probabilistic ML --> textbook. Sequential prediction.

* how do we test this? Sample models that require reasoning (how we reason, chain together better).

* reasoning tests -- approaches (training, RL optimization, decoding). Not seeking out how model is insufficient.

* optimize for reasoning models (fine-tuning). No Free Lunch --> forgetting with fine tuning (continual learning 
approach).

* Chollet, Karpathy --> work models to arena performance (benchmarks).

* empathic AI --> loop a model back on itself (no good arena performance, no strange loop).


"Artificially Clever" -- Penrose. PNAS paper --> Rumelhart. "What is a Number?" --> what do model do to ensure right mathematical answers?

* people + LLMs. Dehaene, Tenenbaum --> work with infants.

* a lot of well-worn paths, lots of work. None are developed to solve particular problems (in-house benchmarks).

* only as good as your benchmarks. Distinct from human logical inference (assume agency?)


Benner-Marcus benchmark --> check for what is being lost in post-training, fine-tuning.

* large concept models -- https://arxiv.org/abs/2412.08821, https://ai.meta.com/research/publications/large-concept-models-language-modeling-in-a-sentence-representation-space/

* DLCA --> Differentiable Ligic Cellular Automata.

* David Ha --> submitted Ai-generated paper to ICLR.

* neuropilot.chat -- generate BRIAN2 spiking NN models.

## TRANSCRIPT   
0:00     
hello good morning morning hello uh shyen yeah hi Hi how are you hello I'm     
0:09     
fine uh this is my first time joining uh or El's meetings okay yeah uh I've     
0:18     
already introduced myself on slack uh and I think I've uh sent a direct message towards your direction I'm     
0:23     
interested in the sales Chaw uh and yeah I'm currently drafting up the proposal I'm 70% there I joined     
0:30     
this meeting and I think uh I have a couple questions regarding the project     
0:36     
and some and the scope of it and all uh I was hoping I could get some answers here     
0:42     
okay all right yeah what were your questions uh okay so I think the first     
0:51     
one is um about the scope of the uh of the project I was hope uh I wanted to     
0:57     
ask if we are trying to move away from uh two three agents to something like uh     
1:05     
more uh uh somewhat of a multi-agent system which has a lot of Agents a swarm     
1:11     
type thing where we have multiple contributors coming and then looking at the uh say the repository that we're     
1:19     
modeling or the open source community that we're modeling and then we have multiple maintainers uh voting on uh     
1:25     
each contributor's tasks and then their method method methods of approaching     
1:31     
that problem and then uh uh and then we also have somewhat of a state management     
1:37     
system where we're keeping track of the uh open source system that we're modeling over multiple different time     
1:43     
steps I was thinking to do that we could have a database sort of thing so that we don't have to start our system again     
1:50     
every single time we on the simulation so that we can have the growth that happens in the system stored over multiple time steps and then when we     
1:57     
come back and run the simulation again we could just our previous St from the database and then keep keep uh building     
2:03     
on top of that yeah so yeah I don't know I I guess     
2:10     
we you mean like over multiple sessions yes yes yeah so yeah I don't     
2:15     
think we have that capability built in um I'm not really sure how it's yeah but     
2:22     
yeah we have where well last year we did um of course the large language models     
2:27     
and agent based models hybrid we also did some work on or we've been doing     
2:33     
work over the past several years on multi-agent reinforcement yeah and so that can be     
2:40     
you know that's that's sort of the multi-agent approach now it' be interesting to integrate swarm type     
2:46     
models or swarm intelligence type models into that or to treat it more as kind of like a collective Behavior type model     
2:54     
I'm not sure what the literature looks like in that area but um it'd be interesting to see     
3:00     
but yeah there is a whole bunch when know we've been kind of working in a certain direction on the M multi-agent     
3:07     
reinforcement so there's a repository there to build on um so yeah I mean that     
3:13     
that would be another thing to do um I think it' be interesting okay there was     
3:19     
also some work that was done last year and it I don't think it got very far on     
3:25     
integrating multi-agent reinforcement learning with like the large language models so larg models would generate     
3:33     
like um a project and some tasks and then the multi- uh agent system would     
3:39     
interact with that and use those tasks so I don't know how far we got on that I     
3:45     
don't think very refer yeah yeah uh from what I've seen on the core base uh it looks pretty uh     
3:52     
there's only a couple agents and the doing a pretty basic tasks uh so there's a calculator model which uh the     
3:58     
contributor and the maintenance is not trying to build over so I was thinking uh the in my proposal uh for what I'm     
4:04     
going to submit this year I was thinking maybe I could build on what's already here uh and then uh try to make a uh you     
4:11     
know a swarm type of thing where I have more llm based agents working together and then uh U we could have a majority     
4:19     
voting based uh type of swarm model uh there are a lot of swarm models that I've looked at uh there is this one     
4:25     
specific python Library called SWS uh through Ai and things like like that uh these are agent orchestration tools I     
4:32     
was thinking maybe I could uh try to uh you know build my proposal around that     
4:39     
direction it sounds good it sounds good okay yeah okay definitely you know     
4:46     
I don't yeah I guess if you had a package in mind that would that would be useful because I don't know how like     
4:53     
when you get to the memory management aspect of it how many agents you can actually put in the environment so if     
4:59     
there's a pack you know it'll it'll be able to handle that those CS of     
5:04     
computations yeah exactly so are there any other ideas     
5:10     
that you specifically want me to focus on in my proposal uh no I think that's     
5:16     
that would be good you know if you could hit on those points and like I think the key is to say i' integrated into the     
5:22     
existing code base right right yeah     
5:27     
right okay sounds good thank you so much you're welcome you're     
5:33     
welcome so yeah um so yeah in terms of     
5:38     
meetings this week we had our Diva meeting last     
5:45     
Monday um and we haven't had still haven't had our cybernetics or cognition     
5:51     
Futures meeting so welcome Morgan uh good I I I keep having meetings before     
5:58     
this meeting yeah which is which is already already in early um so I'm going     
6:05     
to I still haven't had breakfast oh yeah anyway um good     
6:12     
lot uh lot happening this week     
6:18     
um but um Mo mostly mostly narch meetings and and uh yeah     
6:27     
Recruitment and just discussing future future     
6:35     
projects so good good stuff but a lot of a lot of generating um like a lot     
6:41     
of saying people are if we can work on educational     
6:48     
material not yeah so like educational material     
6:57     
for around supporting some of nx's projects and and     
7:04     
you know in particular software projects so um you know I     
7:11     
still yeah so our most you     
7:19     
know GitHub starred project is the mother of all BCI     
7:24     
benchmarks and it's still a great you know it's like     
7:30     
besides its you know unique application area um     
7:36     
it's a great uh it's a great     
7:42     
sorry something's something's ringing on     
7:47     
me okay um it's a great     
7:53     
um it's a great intro project for um students     
7:59     
to get familiar with psychic learn for instance you know and     
8:07     
and yeah I I I like that in terms of you know a lot     
8:14     
of Neuroscience cogy students are you know always asking about how to break     
8:20     
into neurotech and it's like there's not a lot of neurotech jobs yeah um you know     
8:26     
and um uh so it's like yeah what what's the     
8:33     
best thing we can do to prepare them for for the larger larger job     
8:40     
market but it was really nice we met I met with the the students organizing the     
8:46     
California neurot technology conference which is a great student run conference     
8:54     
um of the neurotech chapters from the various UC schools and other     
8:59     
other California institutions so that was um it's great to see     
9:07     
and theyve got some great speakers     
9:12     
um uh yeah so that's that's another another reason to work on our kind of     
9:19     
marketing and educational materials like I'd love to go down and and use as an     
9:25     
opportunity to you know get get more get more students involved in the     
9:30     
project yeah yeah because it's also one of those projects where it's just like     
9:37     
um what's the the I forget who who said this or you     
9:43     
know knowledge knowledge is the only thing that grows when shared oh     
9:49     
yeah anyway but you know that this is this is a wonderful project where it's     
9:54     
like it actually it actually gets better by having more people and and you know     
10:01     
it gets better by people adding more data and adding more     
10:07     
implementations um and yeah so I'm I'm also pushing it as     
10:17     
a you know a good a good project to have the different student chapters     
10:24     
uh coordinate together you know like it's a project that they can all work on and benefit from but and that kind of     
10:32     
coordination like could actually push it into um to a level that um we could get     
10:41     
a paper you know yeah because it's all it's already got yeah anyway like like the the French     
10:50     
team that develop it it's a you know kind of it's a cool GE you know geometric     
11:01     
um geometric methods for for machine learning classification     
11:07     
um they they've already got a good archive paper you know around its most     
11:13     
recent you know it's like the forget the title but it's like the largest EG you     
11:18     
know benchmark yeah um     
11:26     
and yeah it's got and it's got projects that are that fit in a in a kind of like     
11:31     
a number of different kind of um like experience or you know like     
11:40     
there there are projects which are coding and then there are projects that are kind of like data munging you know     
11:46     
right and and you know the like see seeking you know almost like literature you like finding finding data sets you     
11:55     
know getting them into that form and then um and then updating yeah so lots lots of     
12:02     
different expertise levels uh can can     
12:12     
participate and I'm trying to trying to think of any organoids organoid news     
12:21     
um but any we can update on that later all right sounds good thank you for that     
12:30     
update yeah all right so the first thing I wanted to talk about today was uh we of     
12:37     
course have our slack so if you're not in the slack please you know explore the     
12:43     
slack I know that like people are coming in uh from you know outside and so they     
12:50     
probably aren't familiar with it we have a general Channel which is where you kind of end up when you join and you     
12:57     
know I think shyam and BD have introduced themselves so that's key and     
13:04     
then we have our sub channels so we have all sorts of channels uh we have data science uh     
13:12     
bioevolution a gsar channel it's useful uh virtual reality Channel and     
13:17     
some other channels and then we also have some Discord servers that uh serve is kind of     
13:24     
a backup to those channels um that we don't use as often but are still sort of available for     
13:31     
people to go to those Discord channels and the slack team are all linked off of     
13:38     
the main Lab website which is um orthogonal research.     
13:45     
weed.com so go there and you can find the links um this is one of the things from     
13:52     
the slack here I think this is something that Morgan posted this is an article from Google research     
13:59     
on differential differentiable logic cellular autom so in the dorm group     
14:06     
we've been exploring the uh neural cellular autometa we did some work on     
14:12     
this a couple years ago actually um and then beyond that we haven't really done a lot with it but uh people have been     
14:19     
picking this up um in the last few years and trying to build pattern generators     
14:26     
out of so it's very interesting work um and so you know if you go back to the     
14:33     
original cellular autom those are very old computational systems uh they go back to Le Von noyman     
14:41     
and the idea of a cellular autometa of course is you have a central uh cell     
14:47     
with neighboring cells and the neighboring cells depending on their state govern the uh the sort of the     
14:55     
focal cells state so let me draw this out on a whiteboard [Music] um so in a cellular autometa you might     
15:04     
have a neighborhood of cells and usually you know     
15:10     
it's there's the vanon noan neighborhood and there's the more neighborhood so they can look you know     
15:16     
different ways so I'm just going to draw a unit of     
15:22     
analysis here so in this kind of a neighborhood     
15:27     
configuration you have the FAL cell which is here and then this kind of configuration     
15:32     
you have the focal cell which is here and then you have neighboring cells the     
15:38     
neighboring cells were always one cell away from the focal cell and so you can think of this in terms of XY     
15:46     
coordinates this is negative 1 negative 1 they all have a position this is z negative     
15:51     
one this is one Z yeah this is actually not this is     
16:00     
one this is this     
16:05     
is 1 Z I'm trying to remember my coordinates here     
16:12     
um it's something like that anyways if you label this Rd you end up with these     
16:18     
Neighbors in specific positions relative to the focal cell and in this case you     
16:23     
have the same sort of coordinate system now the interesting thing about these focal cells is they're affected by the     
16:31     
neighboring cells States so for example if we have this type of     
16:43     
neighborhood and our focal cell is here if a majority of these cells are     
16:51     
shaded let's say the initial state is that they're all sort of off and then when I this squiggly line     
16:59     
here which is kind of shading it in is going to be where the cell is turned on     
17:04     
these cells are all turned on and it's a majority of the neighbors that are turn     
17:10     
and so we might have a rule that says if a majority of the neighbors are     
17:15     
turned     
17:21     
on then on which means that if a majority of the     
17:27     
neighbors are on then the focal cell is on so then the next state which     
17:35     
is and our t t+ one so this is T and then this is t+     
17:44     
one the focal State okay so that means that we've     
17:51     
turned on our fcal     
17:56     
cell these are all and the same holds true for this type of     
18:03     
neighborhood as well where it's you know a majority rule where the neighbors     
18:09     
are if they're on     
18:19     
then then the focal C and you know you can use that majority     
18:25     
rule the same way to go turn it off as well so the majority cell is on than     
18:32     
the fcal cell will be so this is you know one type of rule we can have other     
18:39     
rules we can have rules where you know we basically if one cell is activated     
18:46     
then the focal cell is activated we can have rules where um all the cells have     
18:52     
to be activated for the focal cell to be activated it depends on our sensitivity and all that now you have to remember     
18:59     
that these neighborhoods are all kind of nested together in the sense that they're they're operating in parallel so     
19:06     
if we take the square neighborhood like this and we     
19:13     
imagine that we have this implemented in parallel that means that this is the     
19:20     
focal cell for this neighborhood and then this neighborhood then extends out     
19:31     
so this is neighborhood a this is neighborhood B this neighborhood B will     
19:36     
have a focal cell here so this is focal cell a focal cell b and you can see you     
19:42     
can create neighborhoods all the way across a larger Matrix of cells so this     
19:48     
might be out a space here but you get my     
19:53     
point uh neighborhood C where you have     
20:00     
focal cell which is here and this keeps going all the way     
20:05     
across the grid so you have these focal cells affected by the neighboring cells and you have this um these computations     
20:14     
that Ur in parallel so you can have effects where things either form     
20:20     
patterns stable patterns transient patterns sometimes you have Cascades     
20:25     
that Cascade across the larger grid sometimes you know in what they call the     
20:30     
game of life you have things like gliders and other types of structures that move across the grid as cells are     
20:37     
activated and those rules are activated and they turn on um sometimes you have     
20:43     
things that just kind of jam up where everything is activated and then it's     
20:48     
saturated and you just end up going from where everything is off to where everything is on sometimes you get     
20:54     
coherent pattern formation though and that's what we're going to be talking about in the differential rule logic     
21:00     
cellular automa paper so this is the subtitle of this is from Game of Life to     
21:06     
pattern generation with learned recurrent     
21:13     
circuits so the basic idea of a cellular automa of course is based on these     
21:18     
neighborhoods and how you can Implement these rules to activate um you know these cells     
21:25     
collectively in a a neural cellular autom we use different types of tools we use     
21:32     
um different types of machine learning techniques neural networks and things like that and so that's where they're     
21:39     
they're kind of drawing from here this is why there's been a rebirth of cellular automa um you know people have used     
21:47     
cellular automa to look at complexity to look at the implementation of different     
21:53     
types of pattern formation they've used different types of rule sets so for example if you have     
22:00     
different types of rule sets you can generate different patterns so wol has     
22:06     
described you know you'll have something like he uses     
22:12     
triangles and you get these triangular neighborhoods where these     
22:18     
triangular grids where they get activated across kind of like     
22:25     
this and you know they're different patterns so you get things that look like seashells you get things that have like     
22:33     
stable periodic patterns and those have different numbers attached to them so     
22:39     
you know there's like rule 120 rule 60 rule 30 and they just are implemented uh     
22:45     
in different ways using different rules and so you know those kind of     
22:51     
models are great for pattern formation but there isn't a lot of     
22:56     
control there and and it's just kind of a curiosity so this is why we're     
23:01     
interested in implementing more machine learning techniques here so let's go through the paper here and see what they     
23:08     
have to say this is a paper you know kind of a big money approach to this     
23:13     
this is like the you know a Google research team called the paradigms of intelligence team so that's where     
23:20     
they're coming from Randazzo uh is named you know they published a lot of things     
23:27     
on uh I think some of the other neural cellular automet work that we've talked     
23:33     
about in B okay so imagine trying to reverse engineer the complex often unexpected     
23:40     
patterns and behaviors that emerge from Simple Rules so this statement is     
23:45     
basically that one of the things about pattern formation and what we might call a mergent phenomena which is where you     
23:52     
get these patterns that come from these interactions is that a lot of times they're not reverse engineerable in     
23:58     
other words you can forward engineer them by generating uh a cellular automet     
24:05     
and running it for a number of generations and getting these patterns and you know you can same thing with     
24:11     
swarm intelligence where you run a bunch of agents in a simulation and you can get them to form patterns and that's you     
24:19     
know we talked about emergence weak emergence strong emergence but the thing     
24:24     
about emergence is that it's usually not reverse engineer in other words you can't there's no inverse way to evaluate     
24:32     
this so this is kind of what they're getting at here where you know you try     
24:38     
to reverse the or reverse engineer these complex patterns and in fact in a lot of     
24:44     
cases you can't do it because what happens in an emerging system is that there are many different ways to get to     
24:50     
that pattern so it's not so much that you can isolate it to specific     
24:56     
interactions it's that those patterns emerge from many different possible     
25:02     
configurations of the system so if you think about an ant colony where you have ants uh crawling along um and and     
25:12     
forming Pathways that they can uh Traverse and then you look at a say like     
25:18     
an ant colony optimization over which we talked about last week and you see this     
25:23     
pattern form they can form that pattern by using many different um uh routes and     
25:29     
Route following strategies it isn't just you can't isolate any single pattern to     
25:34     
any set of specific interactions so that's that's where we are with this and so they say this     
25:42     
challenge is a inspired researchers and enthusiasts to work with cellular autometer for decades so you know people     
25:50     
have been working on this kind of approach that goes bottom up so in the     
25:56     
cellular autometa you start with these neighborhoods you start with these     
26:01     
interactions these focal cells are changing their state these focal cells are also organized in parallel and you     
26:09     
get these emerging patterns that come from the bottom which are these     
26:14     
neighborhoods up to the entire grid so you end up with these kind of uh     
26:19     
triangles with uh periodic patterns and that's what they mean by     
26:26     
bottom up we choose rules then investigate the resulting emerging patterns but what if we could create     
26:34     
systems that given some complex desired pattern can in a fully differentiable     
26:40     
fashion learn the local rules that generated while preserving the inherent discrete nature of cellular automa so     
26:48     
again these are discrete models we have these cells it's a discrete model in time as well so these uh neighborhoods     
26:56     
change their state with time so we go from T to T1 to T plus2 to t+3 and in     
27:03     
each state these focal cells change and so when you get like something like a glider that moves across this grid     
27:10     
that's the product of time Evolution it's also the product of discret State Evolution as     
27:16     
well so that's what they're going to talk about here so they they're interest     
27:22     
is in building these learned circuits and then what they want to do here from this learned circuit is they want to     
27:27     
build is G it's Google G you know they could have built anything but they decided on the corporate logo so but     
27:35     
anyways in any case you see how this pattern is forming from these interactions and but what what's     
27:41     
interesting is that you can do this through implementing rules and just watching the simulation go or you can     
27:47     
build these circuits that you can then go back and Trace the evolution of this so you know what part of the circuit has     
27:54     
been activated when and you can trace back that that that P the formation of that     
28:02     
pattern so that's and then that's what they mean by differentiable that allows us to have a differentiable system as     
28:09     
opposed to something that's merely emerging prior work is explored learning     
28:14     
transition rules using non-differentiable techniques demonstrating the feasibility of     
28:20     
revolving local rules for specific computation and this this citation is     
28:25     
from uh physic a in 199 before Melanie Mitchell uh Jim Crutchfield and craer     
28:33     
evolving cellular autometer to perform computations so this this is work that goes way back this is this original type     
28:40     
of work that um people were doing with emerging patterns in     
28:47     
cellular likewise prior exploration of making one-dimensional cellular autom differentiable exist so there's this     
28:55     
paper from 2017 by Martin on the archive or differentiable cellular autometal so     
29:02     
people have been exploring this sort of approach for a while and this again is     
29:07     
an approach to making emergent phenomena understandable at the level of like     
29:15     
specific interactions we propose a no novel fully ended endtoend differentiable approach     
29:22     
combining two interesting Concepts in the world of artificial intelligence so the first is neural cellular automa     
29:30     
which I mentioned this is a thing we've been looking at in Diva one we worked on it for a little bit this is a an article     
29:38     
from Mike Levan Razo and colleagues this is in the still which is the machine     
29:45     
learning journal and this is of course the paper growing neural cell wheer autom I think we've covered this in D.A     
29:52     
meetings in the past this is where you know they're basically building some the aoma     
29:59     
with a neural network architecture and then they're trying to grow these pattern for up they're trying to     
30:05     
implement pattern formation uh growing phenotypes things like that it's very interesting work and     
30:13     
it actually in the uh Google summer of code devor project this year uh we're     
30:19     
doing things with these uh neural developmental programs which have the     
30:24     
roots in neural cellular Alon the second con so neurocellular     
30:29     
autom is the first concept the second concept are differentiable logic gate networks so these uh cited works here     
30:37     
are this paper deep differentiable logic gate networks uh that's a nups paper     
30:43     
from 2022 and then convolutional differential logic gate networks that's also an     
30:49     
Europe's paper from 2024 so this is an emerging idea as well where you have     
30:55     
these logic gate networks that describe sort of these interactions on     
31:01     
this grid so every one of these rules and in these neighborhoods is basically     
31:06     
a logic gate you have to satisfy the condition and then the logic gate is     
31:12     
activated otherwise it's not you know that that corresponds to whether this uh     
31:18     
this focal cell is activated so that's the idea and then for each neighborhood at each point in time there's a circuit     
31:24     
that's turned on or off and you can build differentiable rules     
31:30     
from or you can use it as a differentiable system NCA ex NCA exhibits the ability     
31:36     
to learn arbitrary patterns and behaviors however they do not inherently     
31:41     
operate within a discrete State space so NCA uh models these neural cellular     
31:47     
automet models are not dis don't operate in a discrete State space so it's hard     
31:53     
for uh people to interpret the output so you know if you think that regular     
32:00     
cellular automet are hard to interpret or their interpretability is low NCA I     
32:05     
guess are even worse because they don't necessarily operate within this bace that a traditional CA     
32:12     
operates um H so their interoperability is made more challenging and leaves them     
32:17     
stuck in a regime where current Hardware must perform costly Matrix multiplications to gradually update     
32:24     
their continuous internal States differentiable iic gate networks meanwhile have been used to discover     
32:31     
combinatorial logic circuits blending discrete states with differentiable training     
32:36     
signals but they haven't yet been shown to work in recurrent settings NCA as it     
32:42     
were are recurrent in both space and time sounds intriguing right so they're talking about using     
32:51     
these two different methods and then they're talking about the integration of these two methods differential logic     
32:59     
gates a cellular autometa as a potential step towards programmable matter and     
33:05     
they use the word computronium which is this paper from 1991 it's kind of a     
33:11     
Visionary paper um from     
33:16     
science and it's speculating in Precious computronium so this is like kind of an     
33:23     
idea of having this programmable matter um as as something that we can at     
33:29     
least understand computationally uh Mike Levan does a lot of stuff with programmable matter as     
33:35     
well and other people who do this a theoretical physical substance capable     
33:40     
of Performing arbitary computation fi and margalus pioner this     
33:45     
dream with Cam 8 a cellular autometa based Computing architecture so this is uh toi of T gate     
33:54     
Fame and then margalus who published this paper on cam8 which is a cellular     
34:02     
aom based computer architecture this is from 1995 so this is a long time ago     
34:07     
this is where they were um trying to figure out how to build a computer with Sol autom kind of going back to Von     
34:16     
neyman's original Vision not the Von noyman architecture but Von noyman did     
34:21     
other work um on self reproducing machines that kind of is uh in that area     
34:29     
and then programable matter Concepts and realization in physic D in     
34:36     
1991 So in theory uh you know these kind of models are     
34:42     
capable of immense horizontally scalable computation however they face the     
34:47     
fundamental challenge then they're talking about T foi and marvelous uh actually crafting the local rules needed     
34:54     
to achieve a desired macroscopic computation uh with a motto at all noting that other     
35:00     
researchers still worry about the difficulty of finding local rules that corresponding to real natural systems so     
35:07     
this is another thing about cellular automa is that they look kind of lifik     
35:13     
and in fact that's kind of one of the arguments that a lot of people make that the patterns that they form are like     
35:19     
things like sea shells and other types of pattern formation and they kind of     
35:25     
mimic biological processes in that they form patterns that look biological look     
35:30     
lifel but there is no evidence that life actually produces things in     
35:36     
this way this is a fairly computational model that produces lifelike patterns     
35:43     
and so it's hard to find local rules for this right I mean you can find the local rules for the computational side but     
35:50     
finding the local rules saying biology and then saying well this is what what the model is doing above and beyond sort     
35:56     
of satisfying the conditions of the logic gate um that's that's sort of an elusive point and that's what they're     
36:03     
making here um so what if we could directly learn these local rules and create models that combine binary Logic     
36:10     
the flexibility of neural networks and the local processing of cellular we believe our prototypes offer     
36:17     
a glimpse into the future of computing which they Define as learnable local and     
36:24     
discreet so again local having these neighborhoods discreet being these     
36:30     
discreet States and then learnable which brings in the uh neural network     
36:38     
aspect this article will walk you through implementing cellular automat using differentiable logic gates and     
36:44     
demonstrating some key results so they had a couple of fundamental questions     
36:49     
can differenti logic CA learn at all and so they actually use Conway's Game of     
36:55     
Life which is a nice uh cellular automa model where you know     
37:01     
they have the cellular automa that runs and they're able to produce different types of patterns not only static     
37:08     
patterns but things like gliders that moved across the grid and other types of patterns um and this is something where     
37:16     
you know I guess they're using Conway's Game of Life to see if that those things     
37:21     
can be learned this kind of an interesting Benchmark for that the second question     
37:27     
question is can we're recurrent in space and recurrent in time circuits so these     
37:33     
rules and these grids are managed by sort of a recurrent process um and so     
37:41     
there's this spatial and temporal aspect it evolves over time it interacts over     
37:46     
space and you have the so you have recurrent recurrence in space recurrence     
37:52     
and time and so can that sort of a system learn complex pth patterns     
37:58     
similar to those generated by traditional neural cellular autom so the neural cellular automa really     
38:04     
interesting produce good results but they're not discreet and they don't allow for this differential aspect this     
38:11     
is what they're getting at this is what they want to do and they want it to they want to be able to trace back to     
38:18     
specific um sort of forward uh rules and outcomes so while     
38:25     
both differentiable logic gate networks a neurocellular autometa or ncas have     
38:31     
demonstrated trainability effectively training circuits that exhibit both temporal and spatial recurrence of NCA     
38:39     
within the framework of differential logic remains unexplored so they do these     
38:45     
experiments they talk about a 2d grid of intelligent cells which is how they     
38:50     
describe the cell autom they use three channels of color they have an alpha     
38:57     
Channel which is where if the alpha value is greater than 0.1 the cell is     
39:03     
considered alive as in Conway's Game of Life The Hidden channels which are n     
39:09     
minus 4 channels allow the cells to communicate more complex information about their environment so the examples     
39:16     
I gave you here were sort of as binary on or off now you can change those rules     
39:22     
to say something is activated to a certain degree you know it can up to a     
39:28     
threshold it can be maybe just kind of just alive at zero a value of 0.1 and     
39:35     
then vital or some sort of Vitality like 0.7 you know you can have different     
39:41     
states of being along so that's they're kind of getting at here um and then they     
39:48     
have this two-stage update mechanism the perception stage in the update stage so     
39:53     
this uh basically this focal cell is a cell that senses the world around it     
39:58     
which are these neighboring cells and um they so in their case they     
40:05     
use soble filters which are these tools that allow you to approximate uh spatial     
40:12     
gradients numerically so basically the solo filter when implemented changes across its     
40:20     
surroundings the filters are applied channelwise and the result is turned a perception Vector which combines the     
40:26     
cell's current state with the information it gathers about its environment so this is kind of like in     
40:32     
biology where we use chemical gradients or we see chemical gradients being perceived by biological cells to align     
40:40     
themselves with their surroundings and this is something that we see in um in     
40:46     
chemical morphogenesis so the type of Turing morphogenesis that we're familiar with     
40:52     
um that's basically the idea is that you have these gradients these chemical gradients and pattern formation follows     
40:59     
these gradients and their sort of their intersection so then there's the update     
41:06     
stage where the neur they put a neural network in the mix where each cell uses     
41:12     
its perception Vector which was described up here as an input to the neural network which performs identical     
41:19     
operations on every cell in the grid using around 8,000 parameters the neural network determines how each cell should     
41:25     
change based on the information SC it's here that the system evolves with the cells adapting and responding to     
41:32     
environmental changes so this is a figure that shows the NCA from that they're trying to do     
41:40     
is evolve this I think this lizard phenotype and they're showing how     
41:45     
they're using um soble filters and this perception vector and then plugging it     
41:52     
into AAL Network to produce this update and so this is a actually from a     
41:58     
growing NCA so they use a similar process in the growing NCA paper this is     
42:04     
this paper from the the distill journal and so you know what they want to do is     
42:10     
they like all this they just want to reverse engineering so that's and then so they use gradient descent to you know     
42:17     
to sort of find these uh these specific steps so this is a good paper um I I     
42:26     
like their approaching what they're doing put some things in the chat here     
42:31     
so VD thank you for posting some things here this is a post on unveiling     
42:37     
differentiable logic cellular aoma New Frontier neural Computing another blog     
42:43     
that I found on the same topic has a good pictorial explanation so yeah oh and then uh     
42:49     
didn't realize but the blog and paper of the same diagram yeah so this is kind of     
42:55     
um talking about this work is a blog post yeah and this yeah this     
43:01     
uh I think this is actually this figure is from this NCA paper so this is back     
43:07     
from 2021 and still but that's what they're trying to do they're trying to     
43:12     
build this sort of uh pipeline where they have the soo filter which is sort of uh sort of     
43:21     
determining or detecting spatial gradients build this perception Vector for each focal cell they're building     
43:28     
this your own network and then they're updating their so all very good stuff um any     
43:35     
other questions I see Morgan said     
43:40     
nice Morgan had anything to say about     
43:45     
it no I I I hadn't uh had a chance to actually work with it or play with it um     
43:54     
you know but uh yeah it it it does take me back to that um um what year was that     
44:02     
the first NCA oh I think 202 well uh I don't know when the first     
44:09     
paper I know some of the work was in 20 20221 but I think it goes back a little     
44:15     
further than that though yeah I mean I don't know yeah yeah and it's it's scary to me that     
44:24     
that was uh almost five years ago     
44:29     
yeah yeah seems like it was yeah I think there's oh go     
44:36     
ahead no it's it's you know I I we had     
44:42     
somebody come by the lab the bib asking about these kind of     
44:49     
computational you know like what how H how do biological simulations work     
44:58     
or you know yeah and and um who's who's     
45:05     
got a blog post [Music] or somebody's somebody just wrote like a an     
45:13     
essay on the you know it's it's it's a takeoff on the the old essay but it's     
45:20     
like the um you know the the the unreasonable     
45:27     
ineffectiveness of mathematics and biology or something like that yeah like it's like the opposite of     
45:34     
the who did the first um uh wigner Eugene wigner wigner W yeah yeah yeah     
45:39     
thank you um anyway so it's just like you know talking talking about you know     
45:46     
the difficulty of or the yeah intractability or yeah the     
45:57     
why why mathematical biology is so hard yeah um     
46:03     
and yeah so was was trying to talk about you know the models models of in     
46:12     
developmental biology and you know who who who who's doing such things and     
46:21     
um uh and how     
46:27     
you know kind of like what what features from them do you want to try and extract     
46:32     
you know without without creating a kind of finite element physics     
46:38     
model um when there's there's you know like yeah so     
46:47     
it's I thought it was really interesting to see these these new very     
46:53     
wide um wide images microscopy images of     
46:59     
embryos and um you know to to Really Capt you know like like people who are     
47:06     
working to capture all the flow oh yeah you know     
47:13     
and and then when you think about you know like like trying to model that flow     
47:19     
and trying to model it um you know trying to model     
47:25     
it with you know like like what     
47:31     
what yeah which those features do you want to capture you know so I mean there's kind     
47:37     
of like the the how much is sell adhesion     
47:44     
changing uh you know how much of the genetic control is     
47:50     
important again always always and is always being good to go over the fact     
47:55     
that you know no cell is in charge of this yeah yeah right so so to some     
48:03     
degree it's you know it's driven by this cell     
48:09     
adjacency um and anyway so the these     
48:15     
these mathematical abstractions are still Absolut you know still really     
48:20     
relevant for this um yeah yeah even though they're they're     
48:28     
obviously abstractions you know yeah but     
48:33     
valuable valuable yeah I think that's the modeling flow is     
48:40     
interesting people I I think I there's a paper maybe in     
48:47     
2020 where they used lran coherent structur so this is a model where you     
48:54     
use a lran to track like Flows In liquids so if you have like a Dy that     
49:00     
you have disperse in a liquid and the liquid is turbulent in some way you can     
49:06     
track those flows using this tool where basically you look at like uh it's not a     
49:11     
discrete model in the conventional sense it's just you take two particles and you track their distance or their difference     
49:18     
so you have this differentiable model but you also have this description of these flows because you get these     
49:23     
structures that show sort of form as and and so someone was using that to look at     
49:29     
like uh cell migration in embryos really interesting paper so that that kind of     
49:35     
model is kind of interesting in light of you know the type of typical     
49:40     
developmental biology models we doing things like you know looking at cell physics we're looking at uh cell you     
49:48     
know cell cell interactions having in considering the autonomy of specific cells or specific tissues so yeah I just     
49:57     
think that you know the sort of the the and this is more maybe a diva worm conversation but how those different     
50:04     
models kind of interact with these type of uh you know modeling     
50:09     
exercises try to approximate uh what we think life is I guess what's important     
50:15     
right right and then and then to throw on the the important you know kind     
50:20     
of leev contribution to this is is how is the the bio electric     
50:29     
field changing if if at all I mean you know you can certainly imagine times     
50:35     
where you you've got flow you got physical flow but but the Field     
50:41     
properties aren't necessarily changing yeah or or or are you know like like     
50:47     
again like another another um yeah he's he's brought brought     
50:55     
electricity back into as as another another level on which     
51:01     
um there's there's both well that there's some sort of     
51:10     
control right but again that that and then the     
51:18     
interesting thing being that of course again that that that control is of course Collective     
51:25     
yeah so the other thing to mention about this is there are a lot of interesting ties between the C autometal work and     
51:32     
the complexity Theory which I think one of the papers in the uh was mentioned     
51:38     
was sort of out of Santa Fe Santa Fe Institute so you know there they've explored these kind of ideas quite a bit     
51:45     
especially with with respect to emergence um and sort of the how you     
51:51     
have different types of emergence strong emergence weak emergence how you know one of the things about     
51:58     
emergence is that you can't really reverse engineer emergence and how that kind of you know     
52:05     
how that could be a model of life so have any model of life really if you're     
52:10     
thinking about like these different vertical levels of how life is organized any model of life is usually a higher     
52:19     
level model and so it inails emergence from say like a genotype to a phenotype     
52:25     
or from single organiz to like a community of organisms and so you have this sort of     
52:31     
uh you know vertical nature of Life which you know I don't know if our     
52:38     
computational models can capture that necessarily I mean cellular automat seem to do that but then you know having like     
52:46     
the specificity that we have in life at these different levels of organization     
52:51     
don't necessarily get captured by the cellular time it's just kind of a a replication of it of the process oh get     
52:59     
these patterns great it looks like life let's call it life the game of life is     
53:05     
like you see a glider moving oh looks like a like something swimming and it's it's just something that's moving in in     
53:12     
pixel space it's not necessarily yeah     
53:18     
so I you know it it's it's the you know all all models are wrong     
53:26     
some are useful yeah I mean you know the the yeah I mean again it's it's     
53:36     
interesting what you can explain with simple cell     
53:42     
adjacency you know cell cell interactions in that in a kind of you     
53:47     
know flocking behavior in Birds kind of right that it can have all this um can     
53:53     
have all this flow and structure uh um you know if you will um of of the     
54:02     
group you know um but it's it's all off of very simple local     
54:09     
interactions and and it doesn't you know I I don't think that it explains everything but it's it's it's still you     
54:17     
it's still remarkable when you see that multiscale game yeah     
54:23     
yeah all right yeah all right so any other comments answer questions before I move on we've had this Arc of talking     
54:30     
about large language models and reasoning and this was also posted in the slack I think this is also Morgan     
54:37     
where it's this diagram from a paper it's figure one from a     
54:43     
paper um this is just kind of talking about large language models post     
54:48     
trainining and some of the things we do Post training so could you want to talk about this figure it is just an attempt     
54:55     
to um to capture you know like there's so     
55:01     
much work going on yeah right so many different groups and um this is by um or     
55:10     
you know this is one of the people that I that I follow on this is um he's a     
55:17     
French researcher um I forget where he works but but he's he's always run a     
55:23     
group of sharing papers and you know this is the guy that um we did the we     
55:31     
did a a read through of of um we we've done     
55:37     
textbooks we've you know covers covers he covers     
55:42     
articles um I'm sure I probably posted     
55:48     
the the LinkedIn on this did I um     
55:56     
uh oh yeah okay here it is here it is let me let me just     
56:02     
quickly yeah and it     
56:08     
includes this one second     
56:15     
second so put this in the     
56:23     
chat um     
56:32     
and and     
56:39     
here's okay so that's just the the the archive and the     
56:47     
um uh associated associated GitHub     
56:54     
um again it's you know the the the IM do you mind blowing that up or you know     
57:01     
yeah my problem is my class yeah so you know and again there's     
57:09     
this plethora of I     
57:14     
mean you know why why are we doing all of this is     
57:20     
because you know again large language models are an interest     
57:28     
was it fuzzy database of of all     
57:33     
our yeah training across all accident     
57:39     
words and that can be found on the internet and and so all of these techniques are     
57:47     
are trying to you know when when trained with such     
57:55     
a simple um you know sequential prediction um     
58:08     
model now now there's all these attempts to to get these um these sequences to     
58:17     
to well I mean to use one technique's name to chain together     
58:23     
better to to approximate something that is is again our our idea of of what it     
58:33     
is we how how we reason um and and a lot of that is based     
58:42     
on um having you know so one thing is super important is that all of these depend on how we test them right so it's     
58:50     
it's all it's all down to what do we consider to be example problems that     
58:58     
that um require reasoning um so you know we've got uh     
59:06     
We've now got a plethora of benchmarks um that feature heavily with     
59:13     
math problems and and other kind of reasoning um reasoning     
59:20     
tests um and yeah this is this is just a a nice     
59:27     
overview of of where they are um and the different     
59:34     
approaches um but I I I think you know I think it's one again because I'll just     
59:42     
do this until until somebody shows me that I'm wrong but you know bring up uh     
59:49     
the Emily bender and yes you know just     
59:54     
uh we're doing all all of these things because this is this is really not a     
1:00:00     
good approach and and you know we we we train on all these benchmarks but we     
1:00:09     
don't look you know we don't see     
1:00:15     
what's we're not seeking out um how the model is now     
1:00:24     
insufficient when when kind of this this post training is     
1:00:33     
done to optimize it for these reasoning benchmarks so you know again when large     
1:00:41     
language models kind of started you know she and Gary Marcus got together a bunch     
1:00:47     
of linguists that that it was really interesting to     
1:00:53     
see the kinds of mistakes that large language models would     
1:00:59     
make that that Ling linguists could find and could     
1:01:05     
see um but you you wouldn't capture from kind of natural language     
1:01:13     
conversation or or you might you might gloss over them in the same way as like     
1:01:20     
when a friend you know makes a mistake while while speaking to you and you just     
1:01:26     
assume that you know they got confused about something or they were thinking two thoughts and and like a mashup     
1:01:33     
happened or something something like that yeah and you know I I I think and I I     
1:01:42     
haven't got the the reference right now but you know I I saw paper perhaps     
1:01:48     
there's another so that that guy is Raymond um there's another woman Cecilia     
1:01:56     
uh I I also posted I think a link to her group that she meets online and um I think she's the one who     
1:02:04     
posted paper that was like there's some significant     
1:02:11     
forgetting that's happening in these these reasoning models or these     
1:02:17     
post post training certainly fine-tuning um which again gets us back     
1:02:23     
to you know kind of like the continu AI people yeah in terms of you know like     
1:02:31     
like that would be your expectation you should expect the fine tuning     
1:02:39     
to you know I mean to to to to to use the old expression there's no such thing     
1:02:45     
as a free lunch right right and and so     
1:02:51     
you know like like yeah so if if you're making a tradeoff     
1:03:00     
for improvements on reasoning     
1:03:05     
benchmarks like like you you should expect there to     
1:03:12     
be an issue somewhere you know yeah     
1:03:18     
um and yeah like like you know I I I     
1:03:25     
have no time whatsoever for AI     
1:03:44     
dorismar kind of work yeah and and you know and and and I     
1:03:50     
think a big part of it is that you know this isn't just research this is this is     
1:03:57     
money right right so this is this is you know you know you can't can't swing a     
1:04:05     
cat without hitting an AI you know AI startup founder in San     
1:04:11     
Francisco sorry to all cats yeah but uh yeah so yeah this basically     
1:04:21     
the this Inner Circle is a large language model post training then     
1:04:27     
they're talking about scale reinforce and tuning those I assume are sort of     
1:04:33     
the post trining alignment strategy we have training RL optimization and     
1:04:40     
decoding so you're doing these kinds of different benchmarks here Chain of     
1:04:46     
Thought tree of thoughts consistency decoding or for scale and     
1:04:53     
decoding I'd say those are the yeah they calling those the algorithms oh the algorithms yeah yeah and or the     
1:05:02     
policies like you know her lhf and uh reinforce for reinforcement     
1:05:09     
learning and then end to end prompt knowledge distillation for tuning and     
1:05:14     
then you have these models which I guess are the ones where you have this post     
1:05:19     
training or maybe they're more suited to this I don't know     
1:05:27     
what this this outer ring is well those are those are what you end up with so     
1:05:33     
it's like it's trying to it's trying to categorize you know so again it's just like it's crazy that there are you know     
1:05:42     
I mean in just this one example you've got you know alphago llama claws you know Gemini is kind of from     
1:05:50     
the same company as Alpha go yeah but deep SE quen M you know so th those are     
1:05:57     
those are all separate companies models okay yeah     
1:06:03     
that that you know and again it also reflects the fact that like like even     
1:06:09     
within a company they've got multiple teams pursuing you know multiple     
1:06:18     
Avenues right yeah um because again there's this trillion dollar pot at the     
1:06:24     
end of the rainbow that they all think that you know     
1:06:29     
they're in race for yeah um and so no amount of you know no     
1:06:36     
amount of funding is too crazy yeah uh     
1:06:43     
uh but yeah so it's it's a nice um you know it's a nice     
1:06:49     
landscape picture yeah of that that gives you a little a little organization     
1:06:57     
um but you you you can also see some of these are represented in multiple     
1:07:04     
avenues like I see deep seek     
1:07:10     
on in the two two outer areas oh yeah deep seek is actually in two of the     
1:07:16     
categories so yeah yeah and and and which which again you know that that was     
1:07:23     
also the other interesting thing about the deep seek um um release on Spring     
1:07:29     
Festival was that um it uh it was one of the only kind of big well it was one of     
1:07:38     
the only super well-funded groups even though they were small um uh     
1:07:47     
uh that told you about everything that they did and and you know and released     
1:07:52     
everything that they did and so you got to see see how you know like again like     
1:07:59     
these are these are very complex multiple you know um multiple training     
1:08:09     
regimes and optimizations and and things that um yeah yeah but again all all on     
1:08:18     
you know ever ever increasing sets of benchmarks and um yeah so at I forget I     
1:08:26     
think it was well Fran Chalet is obviously a good person to to follow on     
1:08:33     
this because um he he's uh you know he no longer works Google so he can he can     
1:08:40     
say what whatever he damn well pleases barring some you know I guess it's NDA     
1:08:47     
period yeah uh uh well I don't know if you saw there's a a a book that's coming out     
1:08:56     
about an Insider at meta and the book has been blocked by     
1:09:03     
Zuckerberg so so it's supposed to be very um not not flattering picture of inside     
1:09:11     
Facebook and they're they're So Meta is blocking it based on for forcing the the     
1:09:18     
author who used to work at meta into private arbitration oh which is a     
1:09:23     
technique that some of these companies and yeah yeah uh um FR um I think was the person talking     
1:09:33     
about or maybe KY but you know that that     
1:09:39     
um you know some of these benchmarks are even starting to get you know people are     
1:09:45     
working their models to just get good you know chat Arena performance and yeah     
1:09:52     
and again there's there's not enough broad testing of the of the     
1:09:58     
models um and yeah so     
1:10:06     
um I like that expression Arena performance yeah yeah yeah it's     
1:10:14     
a you know again the the the arena was a good idea at the     
1:10:20     
time and it it does give you I mean you know again it's it's it's important to     
1:10:27     
know what um what are the important questions and you know I think it's     
1:10:33     
really interesting to go back to Tim Hansen's presentation on empathic     
1:10:41     
AI that um you know we     
1:10:46     
know yeah I think I think it's interesting when you start looping a     
1:10:51     
model back on itself right and and um which you could potentially     
1:10:59     
say is a way for it to to teach itself but but nobody actually does this in     
1:11:05     
practice because it doesn't doesn't lead to better models you know right or like     
1:11:13     
like that that looping itself is is is still problematic and     
1:11:21     
um um and yeah so we we not achieved to     
1:11:26     
this strange Loop right to to     
1:11:32     
yeah use use Tim's Tim sock yeah so this is this paper what is a number that a     
1:11:39     
large language model may know uh so this is from the archive this is new um this     
1:11:45     
is uh basically where oh I guess where they're trying to introduce a concept of a number instead of just recalling     
1:11:53     
numbers or things like that uh so this is uh let's read the abstract     
1:12:00     
numbers are a basic part of how humans represent and describe the world around them as a consequence learning effective     
1:12:06     
representations of numbers is critical for the success of large language models is it become more integrated in everyday     
1:12:13     
decision so basically it's like describing the category of numbers     
1:12:19     
instead of kind of reciting numbers or giving a definition of numbers from a     
1:12:25     
dictionary so you know like it's like well mathematical skill of describing     
1:12:30     
all things in a set or all sets in a you a domain or whatever you know and then     
1:12:37     
like that definition will change so it's like really it how large language models     
1:12:43     
deal with Theory and Theory building which is I guess the Practical     
1:12:49     
consequence uh so these are effective representations that you can are     
1:12:54     
expandable as as you need to uh however these models face a challenge depending on     
1:13:00     
context the same sequence of Digit tokens for example 9911 or 911 can be     
1:13:06     
treated as a number or as a string so this you know 911 might be     
1:13:12     
like a phrase that people use for an emergency number or 911 might be just     
1:13:18     
three numbers you know in a you know numeric sequence or it could be a string     
1:13:24     
which is actually part of like a sentence a word in a sentence so what     
1:13:30     
kinds of representations arise from this Duality and what are its Downstream implications so you have the model has     
1:13:37     
to be able to recognize the difference between the two and has to be able to do that it has to be a recognized context     
1:13:44     
and these larger uh you know these higher level     
1:13:49     
sorts of categories what kinds of representations Aras Duality using a     
1:13:54     
similarity based prompting technique from cognitive science we show that     
1:13:59     
large language models own representational spaces that blend string likee and numeric     
1:14:06     
representations in particular we show that elicited similarity judgments from these models over integer pairs can be     
1:14:14     
captured by a combination of lein edit distance and numerical log linear     
1:14:19     
distance suggesting that an entangled representation so lein edit distance is     
1:14:25     
like looking at like two words they could be you know strings with different     
1:14:32     
characters in it and then looking at the difference in terms of characters     
1:14:38     
character so if you're you know you're comparing two words like there and there     
1:14:44     
t h e re and t h r the Le steam edit distance actually is     
1:14:52     
um I think it's like two or three because you change some of the letters or characters in those two strings and     
1:14:59     
of course there and there on those two spellings mean different things so you     
1:15:04     
know this so let's back to the Whiteboard we can draw this out to show     
1:15:10     
so we might have there and     
1:15:18     
there and so your um your edit distance I think is two because you're changing     
1:15:24     
this these two positions and you're changing this the characters within the     
1:15:31     
string if you have uh you know if you were to compare a string of     
1:15:39     
three with a string of four characters the edit distance would be     
1:15:46     
one because you lose a character so there these that's lein distance and     
1:15:52     
it's used in computational linguistics quite a bit and you can use it to     
1:15:57     
understand sort of the edit distance between two words but it doesn't necessarily give you the     
1:16:02     
context and it doesn't necessarily give you the context uh numerical log linear distance     
1:16:10     
of course is where you get this actual distance um in different way so this is     
1:16:16     
an entangled representation where you get these two aspects of the words and     
1:16:24     
you know the you to build this sort of uh these meta categories in this context     
1:16:32     
in a series of experiments we show how this entanglement is reflected in the weight and embeddings how it can be     
1:16:38     
reduced but not entirely eliminated by context and how it can propagate into a     
1:16:43     
realistic decision scenario these results shed light on a representational tension and Transformer models that must     
1:16:50     
learn what a number is from text input so again this is quote from Warren     
1:16:56     
McCulla 1961 I think he was wearing a shirt at the time that's good um and     
1:17:03     
this is inside joke or never mind um     
1:17:10     
so what is a number that a man may know it and a man he may know a number so     
1:17:17     
this is like basically uh what is a number so I can recognize a number if I see 1961 I know     
1:17:25     
are numbers but then also how do you know a number what do you know how do     
1:17:30     
you know that 1961 is a date in history or that 1961 is like a measurement of     
1:17:37     
weight be 1,961 grams you know there different     
1:17:43     
meanings of this combination of     
1:17:48     
numbers so yeah that's that's the and so they're using these representations to try to make those distinctions     
1:17:55     
and uh yeah yeah it it it yeah reminded me a little bit of the that PN paper     
1:18:03     
with um rumel hard or no oh no the other     
1:18:14     
one um or the other paper okay yeah     
1:18:21     
um yeah it it's like a biblical passage     
1:18:26     
isn't it this what is a number oh I don't know     
1:18:32     
it's I think yeah anyway the um the Malla paper is kind of     
1:18:40     
interesting um yeah it's uh     
1:18:48     
um you know again it's these these funny these funny things I mean just     
1:18:55     
just not necessarily what this paper is about but just again like you know the     
1:19:02     
the early problems that large language models had just doing arithmetic you     
1:19:07     
know and just getting at the point that like again these this is these are not     
1:19:14     
artificially intelligent systems but um um what was the     
1:19:23     
uh artificially clever I think was the was that     
1:19:29     
penrose's term I forget he had a different you know it's     
1:19:35     
fake you know it's it's like like again it's a large language model is not doing     
1:19:40     
math yeah it's not right it's not not done not learned its Tim taes or     
1:19:47     
anything like that right yeah and so it's just like if you ask you know like     
1:19:54     
again like I I I you know it would be interesting to     
1:20:00     
know behind the scenes what the companies the various companies are doing so that it can do arithmetic right     
1:20:08     
you know is it get you know feeding at tables of like if ask this you know this     
1:20:15     
is interesting it just reminded me of the the P paper where they were asking     
1:20:22     
people kind of um questions about complex sentences but     
1:20:28     
they were asking people and llms you know and and     
1:20:38     
um this just focus on the llms but um but I think it might have come out with     
1:20:45     
it might have come from doing like like I saw     
1:20:51     
um um oh that one     
1:20:58     
developmental developmental psychologist     
1:21:04     
um anyway I liked it okay yeah sorry okay I'm trying to     
1:21:13     
find the um so yeah so it's they were talking     
1:21:21     
about the the you know that this came from some of like     
1:21:26     
Stan's work oh right so he he he'd done he'd done this kind of work with infants     
1:21:33     
and stuff like that oh     
1:21:40     
okay that's one person that's not the person I'm thinking of Tenon bomb ten bombs     
1:21:46     
who yeah yeah so I mean you know like I like people like T bomb who and and     
1:21:53     
Donan who actually work with kids yeah     
1:22:00     
yeah so let's go to this paper um this is the one that relative to the it's     
1:22:07     
relevant to that um that figure we were looking at earlier uh this is large     
1:22:14     
language model post trainining a deep dive into reasoning large language models is from the archive this is uh     
1:22:21     
these are the authors on this paper uh large language models have transformed the natural language processing     
1:22:27     
landscape and brought to like diverse applications retraining on a vast web     
1:22:32     
scale data uh has laid the foundation for these models yes yet the research     
1:22:37     
Community is now interested in increasingly shifting Focus for post training techniques to achieve further     
1:22:44     
breakthroughs so this is where they now they're doing this post training that's where we got that zoo of models and zoo     
1:22:51     
of techniques and all that um um well pre-training provides a broad linguistic     
1:22:57     
foundation so there's the pre-training phase and that's the foundation of the model like you know what it what it can     
1:23:05     
retrieve um posttraining methods enable LGE language models to refine their knowledge improve reasoning enhance     
1:23:13     
factual accuracy and align more effectively these your intense and ethical considerations so fine-tuning     
1:23:21     
reinforcement learning and test time scaling those were the three categories uh so if we go back to the     
1:23:29     
figure that L you these two category three categories here scale reinforce     
1:23:34     
and tuning um and these have emerged as     
1:23:40     
critical strategies for optimizing large language model performance ensuring robustness and improving adaptability     
1:23:47     
across various real world tasks this survey provides a systematic exploration     
1:23:52     
of post training methodologies analyzing their role ref finding LGE language models Beyond pre-training     
1:24:00     
addressing key challenges such as catastrophic forgetting which we talked about at least in terms of forgetting uh     
1:24:07     
reward hacking in inference time trade-offs we highlight emerging     
1:24:13     
emerging directions and mod alignment scalable adaptation and inference time reasoning outline future research     
1:24:20     
directions so they have a link to their public repository which is     
1:24:25     
here and that's this uh awesome large language model post training     
1:24:30     
repository at this uh this GitHub account here um and so this is the read     
1:24:38     
me here large language model post training a deep dive into reasoning langage language models we have the     
1:24:44     
archive paper link and then we have the corresponding authors here this is the figure we just went over and then the     
1:24:52     
contents here uh actually it's an interesting table     
1:24:57     
because they give you I think a good uh Mini review of some of this um you know     
1:25:05     
these different papers I guess these are links down to the bottom here yeah so this is this is the table of contents to     
1:25:12     
these different things in the review uh reward learning policy     
1:25:17     
optimization exploration generalization and the different methods that they go over in this document so     
1:25:25     
um yeah so like multi-agent reinforcement learning you have emergent     
1:25:31     
communication coordination social reinforcement learning exploration and     
1:25:36     
generalization is zero shot reinforcement learning generalization reinforcement learning and     
1:25:42     
self-supervised reinforcement learning and then um you know they have some of these other methods policy     
1:25:49     
optimization offline reinforcement learning imitation learning hierarchical re enforcement learning there's reward     
1:25:56     
learning and some others this is large language models     
1:26:01     
reasoning and decision making causal reasoning planning and Common Sense     
1:26:06     
reinforcement so they also have this survey of papers where they kind of     
1:26:12     
highlight different papers that are relevant here and then these categories with     
1:26:17     
papers associate with that so this is a very useful resource a large uh review     
1:26:24     
here about these different and then these These are uh reinforcement learning and     
1:26:29     
large language model fine tuning repositories so these are places where people have already implemented this so     
1:26:35     
you have things like llama gy which simplifies fine-tuning LGE language model agents with online reinforcement     
1:26:43     
learning uh instruct llama implements pre-training supervised fireing tuning     
1:26:50     
or sft and reinforcement learning from Human feedback rhf to train and fine tun Mama     
1:26:59     
2 um train transformer language models of reinforcement learning or TRL that's     
1:27:07     
a state-of-the-art library for post-training foundation models using methods like supervised fine-tuning     
1:27:13     
proximal policy optimization uh grpo and direct performance     
1:27:19     
optimization this is a very nice resource here thank you Moran     
1:27:24     
digging all that up getting that     
1:27:30     
out yeah they've got some they got some really nice tables here or you know they've really cated a lot     
1:27:41     
of a lot of papers yeah now there no shortage of methods     
1:27:47     
that they propos here for some of this stuff like there's a there a lot it looks like people have done a lot of     
1:27:52     
work in the area at least thinking about it trying things out but     
1:27:57     
I well yeah I mean I yeah you     
1:28:05     
you yeah there's a lot of people yeah so     
1:28:11     
like like if if anything I think it's it is somewhat you know like there's still     
1:28:17     
a lot of well-worn paths that a lot of people are are rra spring the same the     
1:28:25     
same material and and kind of like variance of the same of similar     
1:28:31     
approaches yeah um but again it's just like you know yeah but of course there's     
1:28:38     
no like accounting for which ones are I mean I guess you could say depends on     
1:28:44     
your application domain which one is best well and again like so few of the     
1:28:49     
you know like none of these are being developed to solve a particular Pro you know right like like you know in inh     
1:28:57     
house I mean there's all the public benchmarks and then I assume a bunch of     
1:29:03     
In-House benchmarks or things and maybe they've got some some of their own     
1:29:10     
in-house issues that they they trying to connect to these but but again it's just     
1:29:17     
like you know oh yeah um you know all of is just     
1:29:26     
U yeah yeah well deep SE yeah um all these come down to you know     
1:29:34     
I mean it was the the modal the Berkeley modal AI guy who was     
1:29:40     
just like you know you you're only as good as your benchmarks yeah right because that's the only way     
1:29:47     
we can um um we can test it and um     
1:29:58     
uh yeah but I I I liked the beginning of this just in terms of it's you know     
1:30:07     
like you know there remain you know prone prone     
1:30:14     
to critical shortcomings you know     
1:30:21     
and um this is     
1:30:28     
U their their reasoning is well again it's there's no reasoning there no real     
1:30:36     
like like or well certainly their reasoning is fundamentally distinct from     
1:30:42     
human like logical inference yeah I I I guess you know     
1:30:49     
um it's it's difficult to it's difficult to discuss Muslim without the language     
1:30:57     
uh assuming agency yeah which which again is the     
1:31:05     
yeah it's just a just a a bit of a problem of of using our language for for     
1:31:11     
basically metal language but yeah     
1:31:16     
um yeah and again like like I don't know     
1:31:22     
who has this but you know you know there should be there should be a you know     
1:31:28     
Bender Marcus Benchmark that checks for you     
1:31:34     
know um it's     
1:31:41     
yeah what what is being what is what is in fact being lost     
1:31:47     
or um in in some of these post trainining approaches     
1:31:54     
yeah or you know like subtle subtle ER subtle problems that will arise from     
1:32:00     
post training fine tuning I'll see if I can find that that fine tuning     
1:32:07     
yeah but so yeah I wonder if there's like you know I mean I wonder if there     
1:32:14     
are problems introduced through fine tuning are you know I mean it's not     
1:32:20     
included in the model like if you think about like natural intelligence the     
1:32:25     
reasoning kind of comes with the output uh maybe maybe not always but um     
1:32:33     
you know it's not we don't fine-tune our output I get well maybe we sort of do in     
1:32:38     
a social way but yeah I mean it's it's kind of     
1:32:44     
interesting comparison there's     
1:32:50     
yeah there's definitely um     
1:32:55     
yeah little little bit but it it and it it's it's being it's it's definitely     
1:33:01     
being called you know catastrophic     
1:33:08     
forgetting so it this is this is just yeah I I haven't checked in with the     
1:33:13     
continual AI people or you know I've probably missed their their monthly     
1:33:19     
seminar okay okay well their their last their     
1:33:25     
last meeting was focused on efficient fine-tuning     
1:33:30     
techniques all right yeah so let's let we move on looks like Sara is     
1:33:39     
here yeah hi you good     
1:33:46     
good oh yeah I've been like missing the past few weeks for like a bit of oh yeah     
1:33:53     
yeah no problem welcome back what's up yeah thanks yeah I'm G to     
1:34:01     
go to a series of papers I kind of close out the meeting uh this     
1:34:06     
category intelligence and biological systems um just a series of papers that     
1:34:13     
one's a theory paper one's a kind of a review paper and then the other is I guess another theory paper um I guess     
1:34:22     
I'll start with this one here which is the review nature reviews Neuroscience paper so this is uh let me zoom in here     
1:34:31     
a little bit this is uh Daniel barabasi who is at um Harvard and he's     
1:34:40     
the son of uh barbas from Network science F so oh     
1:34:47     
okay like the okay yeah his dad's at nor     
1:34:53     
Eastern yes and he's he's like the famous Network Science Guy this guy is a     
1:34:58     
developmental biologist computational developmental biologist he works with Florine ingert who's a seigan person and     
1:35:07     
then Andre ferera cro who's the author on this so this is uh this paper is     
1:35:15     
three systems of circuit formation assembly updating and tuning this is     
1:35:21     
from nature reviews Neuroscience which always has good reviews of things in Neuroscience     
1:35:27     
so um they've done some really interesting work on innate behaviors in     
1:35:33     
zebra fish and then also some things in in SE elegans that you're interested okay so the abstract on this     
1:35:41     
paper understanding the relationship between genotype and neuronal circuit     
1:35:46     
phenotype necessitates an integrated view of genetics development plasticity     
1:35:53     
and learnings so now we're no longer talking about a large language models and how it does like forgetting and     
1:35:59     
learning and things like that and of course we're thinking more about development uh we're not explicitly     
1:36:05     
talking about an emergent model but we are talking about this sort of genotype     
1:36:10     
to phenotype mapping so we have genotype that informs the circuit phenotype or     
1:36:17     
the connectone and so this is you know this is a kind of a different view than the     
1:36:23     
typical computational view but um challenging the prevailing notion that emphasizes     
1:36:29     
learning and plasticity as primary driv of circuit assembly in this perspective     
1:36:35     
we delineate a tripartite framework to clarify the respective rules that     
1:36:41     
learning impy might have in this process so these are the tripartite vi this is     
1:36:46     
the tripartate view assembly updating and T um okay so in the first part of this     
1:36:54     
framework which we term system one neural circuits are established purely through genetically driven algorithms in     
1:37:02     
which spike timing dependent plasticity serves no instructive Ro so you have this they're they're kind of drawing     
1:37:08     
from the system one system two where you have like system one which is sort of     
1:37:15     
Basil Behavior system two being reasoning which is actually you know way that you might think of kind of the way     
1:37:22     
they're approaching Lar language model reasoning you have the training phase and then you have this posttraining     
1:37:28     
phase so you have this system one and system two Behavior it's not exactly the same thing but you     
1:37:34     
get um so this is they have in this case they have three systems so they have     
1:37:41     
this three system framework system one of course is where you just have this     
1:37:46     
genetically driven you know circuit so we have genes that produce uh a circuit     
1:37:54     
so you know if you go to say sea alans or CRA fish you can observe neural circuits that are basically the same     
1:38:01     
across the organisms so they're driven by like environmental challenges or     
1:38:07     
plasticity or anything else it's just kind of like they're put into place in development uh in and they're basically     
1:38:15     
the same um so that's system one Spike timing dependent plasticity of course is     
1:38:23     
where you have learning but you don't have that in the system we propose that these circuits equip the animal with     
1:38:29     
sufficient skill and knowledge to successfully engage the world so this is where you have these kind of fixed     
1:38:35     
behaviors and they're invariant with respect to the environment it's just     
1:38:40     
kind of producing an outut next system two is governed by a rare but critical singleshot learning     
1:38:47     
event so this is where you have um this is maybe kind of like fear learning     
1:38:53     
where you have if you've ever been scared like once uh you usually retain that you know     
1:39:01     
if you have an aversion to something like you don't like to go into a dark room it could be because you were scared     
1:39:08     
One Time by being in a dark room and it you have an aversion to it um you know     
1:39:14     
you might have an aversion to certain foods because maybe you got food poisoning from that food once so you     
1:39:20     
never eat it again and it it works against like plastic it because you     
1:39:25     
retain that memory in in you know uh even in the face of conflicting evidence     
1:39:32     
so this is the system one which is where you have this sort of uh or I'm sorry     
1:39:37     
system two where you have the single shot learning where you gain knowledge in a single shot but then it maybe isn't     
1:39:46     
adaptive so this is uh which occur in response to survival situations impr     
1:39:51     
prompt rapid synaptic conf configuration so this is where you learn something you     
1:39:56     
still don't have this sort of uh plasticity that will allow you to     
1:40:03     
reorganize your synaptic um synaptic connections due to any sort of new information it's just     
1:40:09     
encoded in a single shot such events serve as crucial updates to the existing     
1:40:14     
Hardware knowledge based of an organism but does in the well for this flexibility that we see in system 3     
1:40:21     
which is this character which is characterized by a per Perpetual state of synaptic     
1:40:27     
recalibration involving continual plasticity or circuit stabilization and fine tuning so this is where you have     
1:40:34     
this kind of continual learning or continual plasticity you're always     
1:40:39     
learning based on new information and it's not single shot anymore it's sort of just calibrating itself depending on     
1:40:47     
what the environment is doing and so by outlining the definition and roles     
1:40:53     
of these three core systems our framework aims to resolve existing ambiguities related to and enrich our     
1:41:00     
understanding of neural circuit formation so assembly updating and     
1:41:05     
tuning are these three steps assembly being system one updating being system     
1:41:11     
two and the tuning being system three so um I don't know they probably     
1:41:18     
get into how system 2 and system 3 are related because the single shot learning is is what we often talk about in or     
1:41:25     
sometime we talk about zero shot learning um machine learning in in large     
1:41:31     
language models and it's sort of like this single shot learning where you're learning one you're learning in one shot     
1:41:37     
and it's very efficient in the sense of being able to acquire information but     
1:41:43     
then this fine-tuning is in biological systems a different step and of course     
1:41:48     
the system two can be in this case can be now adaptive because you can acquire something in a single shot that's maybe     
1:41:56     
doesn't match the environment later so you need to have the system three to sort of recalibrate that single shot     
1:42:02     
learning so you might learn something is bad but then you don't necessarily give     
1:42:08     
the Nuance as to why it's bad and so you respond to something it's bad just with a a general Behavior that's aversive and     
1:42:16     
then system three and it brings that uh brings a little bit more context to that     
1:42:22     
uh so you can or different situational applications and rice and as that it     
1:42:28     
actually reminds me a lot of what brenberg vehicles are doing so s brainburg vehicles have a system one     
1:42:34     
where they have this sort of wiring and like in brainburg vehicles you have different vehicles that have different     
1:42:39     
wirings and the wirings are fixed from vehicle to vehicle type and then system     
1:42:46     
two is where it might acquire a behavior and again that behavior is fixed for the     
1:42:52     
Phoenix type so you have this certain wiring you have this Behavior it might     
1:42:58     
be aversive and you know you're kind of collapsing system one and system two     
1:43:04     
here but in my example what I'm saying is that brenberg vehicles have the system one and system to they exhibit     
1:43:10     
this sort of single shot learning so you know if you put it in in a say if it's     
1:43:16     
has a native behavior that might make it uh attracted to White and you put it     
1:43:22     
in Environ with no light it won't be attracted to anything it'll just kind of move around according to Brownie and     
1:43:30     
motion and then if you put it in an environment with light it'll exhibit the system to Behavior where it moves     
1:43:36     
towards a Target like a light source and then it still doesn't exhibit the system     
1:43:41     
three of course which is where you need fine-tuning and then that's where you     
1:43:47     
need to have sort of maybe a more complex circuitry or something that can     
1:43:52     
be so you know this is you can apply this to artificial systems as well it would     
1:43:59     
be quite interesting to see how this is applied to these different systems now     
1:44:05     
they take an interesting approach even more interesting approach to this and that they put it in the context of     
1:44:11     
development so you system one is sort of analogous to developmental maturation so     
1:44:17     
we think of like uh a fixed circuit if it's fixed through genetics as being     
1:44:22     
fixed and you know actually that's not entirely true there's this developmental     
1:44:28     
maturation so as this hardwired system gets put into place and I think we     
1:44:35     
talked about this last week uh with Jesse we had this conversation about     
1:44:40     
plasticity and systems that are put into place Behavioral Systems that are put into place at different stages of     
1:44:48     
development this system one is actually put into place at different stages of development so you can have these sort     
1:44:54     
of life history phases of this circuit being turned     
1:44:59     
on so there are all sorts of uh skills that kind of are acquired in newborns so     
1:45:06     
newborns can do certain things uh you know that don't need to be learned     
1:45:12     
sometimes they have aversions that are hardwired so um there're you know     
1:45:18     
different things they give an example spider brains and newborn marine iguanas     
1:45:25     
being able to detect and Escape snakes um cuckoo birds murdering their     
1:45:32     
step siblings so there can be quite complex behaviors that get put into place at     
1:45:38     
different stages um and then of course you need to have so they make the point here aade     
1:45:44     
and hardwired does not mean inflexible and stereotypical so you can have these innate circuits that are you know     
1:45:52     
flexible in some ways but um you know they're they don't have the system one     
1:45:58     
and system two aspect of acquisition so they kind of give this it     
1:46:04     
sort of links together morphogenesis and learning which is really interesting     
1:46:10     
here um yeah so this is a nice paper um it kind of makes these     
1:46:17     
points uh very generally and they're trying to build this Theory here where     
1:46:22     
they show these performance curves over trials is how people in this case are     
1:46:28     
acquiring the skill of playing tennis so actually they have the point here in system two you have these eure     
1:46:36     
moments uh which are you know I talked about fear learning where you have this one shot learning but you also have     
1:46:43     
these Eureka moments where you you start to acquire skill like in in tennis or     
1:46:51     
any kind of sport and you kind of build that expertise and then all of a sudden you have some sort     
1:46:58     
of moment where the skill level jumps and reaches a plateau and this often     
1:47:04     
happens in training where you work with something for a while and as you acquire     
1:47:09     
the skill you kind of improve and then you hit this Plateau or even improve to a certain point uh and it's a very quick     
1:47:17     
consolidation of the memory sometimes you know in Discovery we have this I think we I don't know if     
1:47:23     
we talked about the aha moment but that's in the literature uh where you have this you     
1:47:30     
know discover you you kind of read things you read all these papers we finally put something together in a very     
1:47:37     
quick eure moment so system two could be positive as well as negative but it's     
1:47:43     
this oneshot learning that has not as much Nuance of system 3 where you keep     
1:47:49     
practicing and in skill acquisition you actually acquire skills through practice     
1:47:55     
you hit these plateus where you acquire different skill levels and then you keep practicing and you can make it to you     
1:48:02     
know higher and higher plateaus of performance so this is kind of what they're getting at here and then there's     
1:48:09     
a biological basis for this which they talk about here with synapses and innate     
1:48:14     
knowledge and all of that okay so that's a nice paper um the     
1:48:21     
next paper here I want to talk talk about is so it's called a theory of     
1:48:26     
intelligences this is by Michael hulberg so this is a theory of     
1:48:33     
intelligences and the abstract reads intelligence is a human construct to     
1:48:38     
represent the ability to achieve goals given this wide birth intelligence has     
1:48:44     
been defined countless times studied a variety of ways and represented using     
1:48:49     
numerous measures understanding intelligence ultimately requires Theory and     
1:48:54     
quantification both of which have been proved elusive I develop a framework called the     
1:48:59     
theory of intelligences or TI that applies across all systems from     
1:49:05     
physics to biology humans and AI so this is like kind of we talked about     
1:49:11     
intelligence as being this poorly defined concept especially for like     
1:49:18     
artificial intelligence because we kind of use analogies from Human intelligence and in     
1:49:24     
human in the human case intelligence is likewise pretty poorly defined and so     
1:49:31     
but this actually goes across all these different domains it's kind of like the     
1:49:37     
mic 11 cognition as everywhere approach which goes back to what's his     
1:49:45     
name philosopher what's his name well anyways um so this kind of it     
1:49:53     
it's kind of like the Mikael 11 intelligence everyware approach but it also kind of gives you this kind of     
1:50:01     
connection between natural and artificial intelligence     
1:50:09     
so TI lakens intelligence to a calculus differentiating horal lighting and     
1:50:16     
integrating information so this is where you have this differentiable model of     
1:50:21     
intelligence um but also o sort of mathematical model which you can easily apply to artificial     
1:50:28     
intelligences intelligence operates at many levels and scales and TI distills these into a parsimonious macroscopic     
1:50:35     
framework centered on solving planning and the air optimization will accomplish     
1:50:40     
goals so this again is this sort of uh competency of goals aspect notably     
1:50:47     
intelligence can be expressed in informational units or in units relative to goal difficult     
1:50:53     
so this is of course like bit like kind of measure of intelligence latter     
1:50:58     
defined is gold complexity relative to system ability which can be individual uh complexity or benchmarked     
1:51:06     
complexity so you can have a benchmark or you can have like an individual     
1:51:11     
assessment I present General equations for intelligence and its components and a simple expression for the evolution of     
1:51:18     
intelligence traits measures developed here could be the basis for further refinements to Gage different facets of     
1:51:25     
intelligence or any stepwise transformation of information I argue that proxies such an     
1:51:32     
environment technology and society and collectives so proxies being these     
1:51:38     
environmental technological society and Collective aspects are essential to a     
1:51:44     
general theory of intelligence the possible evolutionary Transitions and intelligence particularly in humans so     
1:51:52     
this is a quite a ambitious Theory kind of thinking about uh information Theory     
1:51:59     
and how it can be applied to intelligence uh talking about going back to Claude Shannon and what he his quote     
1:52:07     
information is the resolution of uncertainty um so basically the     
1:52:14     
potential of information is as an unresolved order that can be perceived filtered deciphered and transformed     
1:52:22     
Shannon had previously equated information with the term intelligence uh through his observation     
1:52:29     
is but one essential part of intelligence the other being goal attainment so there's this kind of old     
1:52:35     
view of Shannon and he's thinking about information Theory and he you know kind     
1:52:42     
of understands that information is about resolving uncertainty so if there's you     
1:52:48     
know uncertainty you can't say that you have information information is only useful     
1:52:55     
when it's certain and so then you also of course have goal attainment and maybe     
1:53:00     
some other Concepts as well this is just kind of what we building towards in this uh by associating these Concepts     
1:53:08     
one arrives at a simple General description of intelligence that is the resolution of uncertainty producing a     
1:53:15     
result be it reactive or an intentional goal so if you have a a system or     
1:53:23     
process that resolves uncertainty it can be you know that's     
1:53:29     
intelligence so if we have a genetic system that builds a a circuit in a     
1:53:34     
cran that is you know resolving uncertainty if you have like     
1:53:40     
say a motor circuit that motor circuit resolves uncertainty you don't have to     
1:53:45     
have a s you know a system of neurons that can have to come do this sort of uh     
1:53:52     
sort of behavior on its own and so if you had that kind of system say you had a bunch of neurons that kind of had     
1:53:59     
connections between them and you just had those generated in development and     
1:54:06     
the idea was that you know every generation every individual has to solve     
1:54:11     
the problem of uh moving on its own like moving around its environment well that     
1:54:18     
would result in like basically this random walk that you would do forever and ever and only some organisms would     
1:54:25     
figure out how to move maybe towards a goal or move in a coherent manner how to coordinate their limbs and everything     
1:54:32     
else having that kind of circuit hardwired into the genes and and     
1:54:38     
expressed in development in a very systematic way resolves uncertainty and so it provides the     
1:54:46     
organism of intelligence now it could be reactive or it could be towards an intentional goal     
1:54:53     
so you could have a reactive form of intelligence which is building a circuit that maybe just does a random walk or a     
1:55:00     
levy flight or something like that and that would be fine but then you also have intelligence as that can sort of     
1:55:07     
have an intentional go like move forward or move backward and in C elegans for example they have different parts of the     
1:55:14     
movement circuit that do that and so those are all sort of this in the parlance of the last paper this stage     
1:55:21     
one uh Behavior so this is kind of     
1:55:27     
consistent with that last paper uh so the objective of this paper     
1:55:32     
is to unpack the statement of his definition of intelligence and to use     
1:55:37     
this to propose a series of increasingly complete Frameworks in a theory of intelligence so um yeah I don't know if     
1:55:45     
they're mathematical models we want to follow up with here so basically this is um the key Concepts figure figure one um     
1:55:54     
this is where you have this sort of uh this Information Gain over time and then     
1:56:02     
this uh planning versus solving that so     
1:56:07     
let's see let's see if we can figure this out     
1:56:13     
okay um so time versus in so first of all planning versus     
1:56:19     
solving you have these different planning solving U so okay solving is     
1:56:26     
the ability to resolve uncertainty planning is the ability to trace a future sequence of manageable challenges     
1:56:32     
for its gold resolution the Clines which are these lines here across the graph refer to the     
1:56:40     
progressive intelligence milestones and abilities that deal with complexity so you have these these uh ISO bars here uh     
1:56:49     
in this graph these solid lines they show kind of these I guess stable States     
1:56:56     
or um Milestones that you make as you move forward so you have one two     
1:57:03     
trajectories one two and three that's the dotted lines trajectory one is is     
1:57:08     
gains an intelligence mostly due to solving so you see it kind of parallels the Y AIS which is solve and it crosses     
1:57:16     
these different Milestones so you have these Milestones that come across here     
1:57:21     
uh it reaches this uh fifth Milestone sooner than trajectory 2 which is where     
1:57:30     
it's dominated by planning so solving is on the y- axis planning is on the x-     
1:57:36     
axis so when it when uh when your gains     
1:57:41     
in intelligence are dominated by planning you reach a lower Milestone     
1:57:47     
than if you do it by solv and then three is this trajectory three which initially     
1:57:53     
favors solving the gradually favors planning is the most efficient of the three examples so you actually get to     
1:58:00     
the fifth Milestone sooner and so what that's adjust as that     
1:58:05     
planning and solving are both part of intelligence then this section B which     
1:58:10     
is time versus Information Gain this again has um these uh two so     
1:58:19     
there's a mod u i which is one here is this monotonic decrease in path node     
1:58:25     
changes leading to an intermediate resolution that's efficiency number two which is this     
1:58:33     
polinomial here is complex trajectory and path node     
1:58:38     
change the transient information loss subsequent discovery of a more accurate path and a consequential delay in     
1:58:45     
resolution and then three which is here which is a straight line up but with a     
1:58:51     
high level Information Gain is the sufficient path corresponding will rapid resolution so     
1:58:58     
you see lays out these scenarios for his theory of intelligence and how it     
1:59:04     
resolves in     
1:59:09     
okay so that's that paper and you know again he lays out this mathematical framework he kind of also lays out this     
1:59:16     
idea of an intelligence Niche so this is uh these are representations borrowed from the     
1:59:22     
archaological and evolutionary Sciences whereby the fundamental niche of a system or a species is the set of     
1:59:29     
possible conditions for which the population can persist so this actually goes beyond human intelligence in terms     
1:59:36     
of natural intelligence and gives us this sort of uh philogenetic view of     
1:59:43     
intelligence so we have this fundamental Niche which are traits generalization and     
1:59:49     
flexibility you have this proxy realiz Niche and this realized Niche a realiz     
1:59:55     
niche being a subset of the fundamental Niche which is context and environment so we basically have say a fundamental     
2:00:01     
Niche would be like a neural circuit and you know that neural circuit can be flexible and then the realized Niche is     
2:00:08     
where we have context and something that responds to the environment so in the parlance of the last paper the     
2:00:14     
fundamental Niche are these systems one and two the realiz Nisha system three     
2:00:20     
and then proxy realiz n is where you have this augmentation so it can be another form of the ne realized Niche     
2:00:28     
and then you have this Niche extension which is selection learning experience it's also that sort of level     
2:00:35     
three then the proxy novel Niche which is where you extend and     
2:00:41     
invert uh intelligence and that's separate from this fundamental Niche so     
2:00:46     
just thinking about this in terms of sort of different niches is that um an     
2:00:54     
organism can occupy um specializations that they can     
2:00:59     
exhibit so uh basically you have this fundamental     
2:01:04     
Niche it can be augmented it can be refined through context and then new     
2:01:10     
niches uh emerges a system Innovation so like something like language or     
2:01:15     
cognition so if you have an organism that acquires high level cognition or     
2:01:21     
acquires a language that's the proxy novel     
2:01:27     
okay so the third paper is this paper     
2:01:33     
here um this is the natural history of     
2:01:38     
intelligence systems towards understanding major Transitions and cognitive Evolution so it draws from     
2:01:44     
that sort of f genetic view of intelligence and in this case intelligence systems one reason why this     
2:01:51     
is interesting Adam saffron is an author on this so it looks     
2:01:56     
like Victoria clage and Adam saffron the a so that looks like this will be     
2:02:02     
probably a pretty interesting Pap um actually there are three papers in the     
2:02:08     
series but this is the one paper I want to highlight right now     
2:02:14     
um uh I think this is like a preprint and two other papers that are also     
2:02:20     
preprints so in the first set of Explorations meditations of three so this is paper     
2:02:26     
two and paper three we examine major transitions in cognitive Evolution and     
2:02:31     
provide a framework for understanding different types of intelligence in naturally evolved systems so they're     
2:02:37     
looking at this sort of fenetic view they want to understand different types of intelligence these evolved systems um     
2:02:44     
so it's not artificial intelligence it's natural intelligence and it forms you     
2:02:49     
know they they they're have a common answer Cry of course but they also have their own sort of adaptations and unique     
2:02:58     
aspects drawing in synthetic perspectives from multiple theorists we review several key taxonomies on     
2:03:05     
cognitive sophistication including dennett's hierarchy of creatures so     
2:03:10     
dennet was actually the original person who proposed sort of the cognition all     
2:03:16     
the way down idea uh darwinian scaran paparian and gorian so this is denet     
2:03:23     
hierarchy of creatures um this is I'm not going to get into this concept but this is where     
2:03:30     
it comes from Pearl's ladder of causation of course Judea Pearl has worked on causation and has this sort of     
2:03:37     
model of causation where you start with Association you move on to Intervention     
2:03:43     
which can allow you to diagnose a cause and then counterfactuals which allow you to look at things that are contrasting     
2:03:51     
and cons consider what if questions um and then Thomas's evolution     
2:03:56     
of agency uh Michael thomaso propos this evolution of agency as being gold     
2:04:02     
directed intentional rational and social en     
2:04:07     
normative so these are kind of drawing from these different taxonomies of     
2:04:12     
cognition and as much as they're kind of you know necessarily think of a     
2:04:19     
biogenetic view of intelligence as a ladder because that would be incorrect but they do have these     
2:04:25     
hierarchies and so you know you know there are things that can form to different hierarchical levels of     
2:04:32     
complexity I guess you could put it so this is kind of where they're going with this we place particular emphasis on     
2:04:38     
Thomas's account which traces the development of increasingly sophisticated forms of agency from early     
2:04:45     
vertebr to modern humans so Thomas C's model is actually probably the most FAL     
2:04:50     
genetic of three um taxonomies that we have here so this is why they're kind of you know looking     
2:04:57     
at this sort of how agency kind of evolves uh the paper also examines how     
2:05:03     
unlimited associative learning and this is something that actually comes uh from     
2:05:11     
uh this is a concept that's uh an earlier concept not in this paper uh but     
2:05:17     
it was proposed as a method of sort of thinking about about uh tonomy things     
2:05:25     
like that uh so unlimited associative learning mmark critical Transitions and cognitive     
2:05:31     
Evolution uh this review provides groundwork for two subsequent papers exploring social intelligence human     
2:05:38     
uniqueness and artificial intelligence we suggest that understanding these natural histories of intelligence may be     
2:05:45     
crucial for developing artificial systems that can robustly engage in     
2:05:50     
causal reasoning and social interaction this theoretical synthesis     
2:05:56     
offers insights into both the evolution of natural intelligence and potential     
2:06:01     
Pathways for developing artificial agents with sophisticated cognitive     
2:06:06     
capabilities so they're very much thinking about artificial intelligence but they're also taking this     
2:06:12     
philogenetic View and saying this is also important and especially in terms     
2:06:17     
of understanding natural intelligence you can't just think about human analoges to     
2:06:23     
intelligence so there this is the paper here uh number one so this is the first     
2:06:29     
paper uh the natural history of intelligence systems this paper     
2:06:38     
two this is the second paper in this series same authors in search of the     
2:06:44     
socio effective and cognitive origins of humanity what if anything is unique     
2:06:50     
about human Minds so this actually kind of is the second set of these     
2:06:55     
Explorations thinking about um sort of comparing human cognitive uniqueness     
2:07:03     
with non-human primates focusing primarily on the theory of Mind analogical reasoning and social learning     
2:07:10     
capabilities so this is something that is very much uh sort of Michael cell     
2:07:16     
oriented and this kind of goes into some Developmental and comparative psychology     
2:07:21     
ology how capabilities May emerge through the interplay of innate predispositions and social learning so     
2:07:28     
this is relevant to the thing you talked about in the first paper on sort of the     
2:07:35     
systems one two and three uh and and so they kind of get into these differences in uh primate     
2:07:44     
cognition and how human cognition is unique in that     
2:07:49     
sense uh paper three is this paper on towards artificial gen general     
2:07:58     
intelligence by reverse engineering the human heart mind and I don't know why     
2:08:03     
they put heart mind I guess it's because they're looking     
2:08:09     
at okay so in the abstract reads in this final set of Explorations meditations this is     
2:08:16     
the third paper we examine the requirements for developing artificial general intelligence or AGI near the     
2:08:23     
lens of human cognitive architecture with particular emphasis on the role of narrative selfhood and social cognition     
2:08:31     
drawing on perspectives from cognitive science philosophy of mind and artificial intelligence research     
2:08:38     
critically evaluate current claims about the capabilities of large language models here we go particularly regarding     
2:08:45     
their purported achievements of theory of mind and selfawareness we argue that genuinely human like artificial     
2:08:51     
intelligence you require more than sophisticated pattern recognition and language     
2:08:58     
modeling so this is re relevant to what we were talking about before where we build this model of sort of a training     
2:09:04     
stage and then a post-training stage and then we add in our reasoning in the posttraining     
2:09:10     
stage um so this is what we're talking about here they argue that you need     
2:09:15     
something more than that potentially necessitating the development of coherent narrative self model     
2:09:22     
and Rich causal understanding special forms of ritually embodied and socially embedded     
2:09:28     
development to achieve robust and reliable functionality we conclude by     
2:09:33     
proposing at the path to artificial general intelligence may require recapitulating aspects of human     
2:09:40     
cognitive development particularly regarding the construction and narrative identity and social moral moral     
2:09:47     
reasoning capabilities this analysis is implications for both techn teal development of AI systems and the     
2:09:54     
ethical Frameworks through which we evaluate artificial     
2:10:00     
moments okay so that's those papers uh I know this these last three papers I     
2:10:07     
suspect that they will be submitted to the special issue that we've been we're     
2:10:12     
we're trying to contribute to and I think they're very much in line with that but the third paper in particular     
2:10:18     
is interesting in terms of this uh this large language model     
2:10:23     
reasoning uh Quest and so yeah so that's     
2:10:29     
all I have for that uh Sara asked a question in the chat also attended a talk this week which mentioned large     
2:10:35     
concept models and how they might be a huge step towards AGI so this is these     
2:10:40     
are different than large only with large concept it's not large only yeah we were kind of talking about     
2:10:46     
that earlier but um yeah I had not heard of these before I I haven't done much research on this yet apart from the news     
2:10:53     
about meta's LCM models being released okay would people here be interested in     
2:10:58     
exploring this yes I could try to collect some papers and speak about the next meeting yeah please do um we just     
2:11:05     
got done talking about um large language models and reasoning kind of how they're     
2:11:10     
doing this and uh it's a zoo of ideas and benchmarks and tools so yeah I'd     
2:11:17     
like to hear about concept models and how that's done     
2:11:22     
yeah sure I I'll try that as well even I was like looking to read up about it so     
2:11:27     
it would be a good way to do that as well okay yeah great thank you do we have any thoughts about the     
2:11:42     
papers yeah um I     
2:11:48     
mean as as usual it's l material yeah um     
2:11:56     
so I mean I always drop the drop the links for us     
2:12:03     
um um I'm not sure what dlca     
2:12:09     
is if you want to put that put it in the chat what that is     
2:12:16     
um just just to say um     
2:12:23     
yeah hoping to meet with Adam next week um he's uh he said he's got a big     
2:12:32     
meeting Wednesday but we'll be freed up after that oh yeah yeah yeah yeah yeah     
2:12:38     
yeah of course um um the     
2:12:45     
reversing uh reverse engineering um     
2:12:53     
yeah it's um I'll get the I'll get the links Sarah     
2:13:01     
we'll get we'll get all those yeah yeah no no idea yeah yeah yeah yeah I I I was     
2:13:08     
first finding them on Research gate but they're actually all on S archive freeprints they're all on     
2:13:16     
OSF instead of search searching on Adam saffron OSF um but just to say that uh     
2:13:24     
you know this is this is great to see because I'd really like to um know you     
2:13:32     
know more details like what he presented at the foresight meeting     
2:13:38     
um you know what is potentially like a year ago is it that long um anyway but but     
2:13:47     
you know so the human heart mind is the you know it's     
2:13:55     
it's he's going for empathic AI yeah oh     
2:14:02     
okay I I believe yeah yeah no the u i I got you     
2:14:09     
now yeah yeah yeah     
2:14:16     
um you know I I yeah what what projects exist Bradley that um that are perhaps     
2:14:25     
using you know neural cellular automa uh I think I people have largely     
2:14:32     
just been exploring the algorithms so like you know just kind of doing benchmarks and and proof of concept I'm     
2:14:40     
not sure I know that what we've been doing with the NCA is trying to grow an     
2:14:46     
embryo Network which is something we've done in D.O wor we take the cell centroids and we kind of look at their     
2:14:53     
proximity or their signaling potential and we build networks and we kind of     
2:14:58     
grow a growing Network so like as an embryo as the cells divide an embryo you     
2:15:04     
get these expanding networks and the same thing holds true when you get like a connect them that's where cells are     
2:15:10     
differentiating in the neurons and connect to one another so you get these growing networks in development and you     
2:15:17     
can use an NCA to as part so we have a repository in this where we're using it     
2:15:24     
to kind of grow a network and show how as the network grows you know it changes     
2:15:30     
its connectivity it gets more dense and all     
2:15:36     
that uh oh um so yeah we we started     
2:15:44     
um we moved to Daylight savings yeah uh     
2:15:49     
last North America yeah last weekend last weekend so that's that's why you're     
2:15:55     
maybe an hour off um like we should post in what is it     
2:16:01     
UTC time or you that wouldn't help actually but yeah it would that wouldn't     
2:16:10     
help this is this is the problem of finding a reference time frame yeah     
2:16:16     
yeah yeah cuz I used to remember it used to be like 12:00 p.m. but then I don't know I I have a     
2:16:24     
reminder that yeah we we sprung forward yeah so     
2:16:30     
so in the states we moved one hour one hour ahead yeah okay so so what is like the     
2:16:39     
just actual time with times okay 7:30 I oh okay so I've been okay thank okay     
2:16:46     
that helps me absolutely and the Europeans will do it in like end     
2:16:55     
of the month I think anyway so it's like like for a couple weeks the Europeans     
2:17:03     
stay normal time and then they'll switch yeah     
2:17:09     
yeah okay yeah yeah because I remember 8:30 and yeah okay I'll change my     
2:17:16     
reminders yeah thanks thanks thanks yeah thank you all right so I guess that's it for today     
2:17:24     
um wanted wanted to mention one more thing okay um which is that uh     
2:17:32     
um David H submitted uh a paper to an AI     
2:17:39     
generated paper to iclr oh yeah so the um anyway I I hadn't uh I     
2:17:48     
hadn't really seen this but um uh I I think I saw some tweet or     
2:17:54     
something about it and um you know he's just saying like like he did this with     
2:18:00     
permission from iclr yeah and uh you know um I for I forget     
2:18:10     
who who was Laing it but you know like oh this is a great step forward or     
2:18:17     
something like that but again yeah I I um have to read it first well it's not     
2:18:25     
just that but yeah like like again this is you know going going through going     
2:18:31     
through peer review is still just artificial cleverness right yeah you know and and not um yeah but but it     
2:18:41     
would be it would be interesting to to look at it and again     
2:18:48     
um uh wanted to mention so somebody just sent me a link um to this on slack     
2:18:59     
um sorry my slack just quit so     
2:19:11     
um one second     
2:19:17     
sorry so neuro neurop pilot chat um is     
2:19:23     
is trying to make a chat agent that generates uh Brian 2 you know spiking     
2:19:30     
neural network models oh wow okay and you know so it's just like I I     
2:19:37     
I I mention it just because I don't want to be I don't want to be the uh the old man telling kids to get off my lawn yeah     
2:19:45     
uh about large language models like like they can do some you know like this this could still be useful um and um I I'm     
2:19:56     
just curious if if if anybody's got a like like who who might be interested in     
2:20:02     
trying this um who's the Brian 2 guy     
2:20:08     
French oh I don't developer yeah     
2:20:14     
say actually I want to say I want to say maybe like English-speaking person who just happens to live in France maybe     
2:20:20     
yeah but anyway uh um not not sure if anybody's interested in playing with     
2:20:26     
that but but I thought that would be um yeah it might be nice like like brain     
2:20:32     
GPT I think is the yeah yeah Bradley love Yeah like like are are there some     
2:20:40     
you know generating a paper doesn't actually seem like that     
2:20:47     
much of a stretch for H you you know getting it to you know like like again     
2:20:53     
useful code generation or or getting it to um yeah to really really be a good     
2:21:03     
assistant for literature searches or hypothesis generation which     
2:21:12     
would be kind of cool yeah anyway all right     
2:21:17     
thanks next week take care bye     
2:21:23     
thank you bye bye bye
