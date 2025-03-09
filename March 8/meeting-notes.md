## Meeting Recording

[YouTube link](https://youtu.be/ncyKtU0nUqY)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114130766685243514)


## NOTES
Analytic Solutions: Julia —> SciML —> data crunched to an exact solution.

control theory. Approximation solutions. Finding in exact solutions (ML — inconsistent with control theory).

Anesthesiology — EEG closed-loop feedback example: embeddings, find a lower-dimensional space in which problem is easier. 

simplify closed-loop feedback. 

SHRED —> Nathan Kurtz. Spatiotemporal dynamics: when do you see the dynamics change?

* 


You need a learning system and a memory system (separate systems). 

Subtle but complex structural difference —> at what level is it operating? 

psychiatric genetics, brain structure/physiology.

how responsible is genetic control over organogenesis?

ABCD dataset: why could these things be selected?

Pamela Sklar: datasets —> gene hunting. Schizophrenia. Bigger question of organogenesis: epigenesis factors for tissues and organ structure.

Running DOOM on everything: world model implications.

Carmack —> get so much from limited hardware.

read-only memories 2064 —> limit or constrain agents to hardware. Toasters and other machines.

Levin, Bongard paper. Limited operation video game ~ fully-level human sentience.


dynamicsai.org —> closed-loop systems and ML: analogies and loops on top of loops —> connections to AI methods and interaction.

Analog vs. digital —> how do things relate? What is too much capacity? Developmental Freedom, capacity? Developmental freedom —> beyond “sculpting a chunk of clay”. 

how much is too much plasticity? At what day of being alive does animal show behavior? Things needed to be in place first.

* maintenance stages, dynamic states of being.

attention, focus —> more trained in chess, more weight to valid moves?

less nuance in experts, more synthesis, automaticity.


English experts —> tune out invalid ways of pronouncing things. 

vantage points essay. Create environments to do the work. Stability.


Where could futurist medicine go? What can lead to enhancements, biohacking? Perturbance vs. agitation.

what provides useful changes? Push forward specific projects. Very interdisciplinary focus.


Setting things up fro pop-out effects —> transform data to the point of superperformance. 

OpenPI —> physical intelligence, physically-actuated devices. 

ALOHA —> bimanual manipulation with low-cost (novel action for chunking).


Developmental Cognition: long open-ended meeting, polymath medical group.

plasticity, hormesis (small change with recovery, over-compensation).

Superhuman performance —> above human performance on tasks, place this in terms of animal and augmented intelligences.

false coloration of medical images —> provide performance from a model that analyzes a eigenspace vs raw color space. 

Human —> IA, hybrid chess, superhuman.

cognitive models, computational neuroscience: what is input?

Hyperspectral —> frequency data. Why aren’t radiologists not out of business yet?

dimensionality reduction across frequencies.

good IA model, add information, schema.


RT-2-X: 55 billion parameters. Stacks and Piles dataset.

Open-X uses skill-specific datasets (pour, stacks, routes).

embodiments —> skills —> attributes, objects, spatial relations.

David Silver —> Towards Superhuman Intelligence. Recipe: super-scale RL.

Defining “superhuman” —> Atari performance? Chess? Human strategies have changed as a response to AI models.

Robot Learning course/meeting. Foundation models, scaling DeepRL.

* surgical robots (interesting set of constraints). Causality —> what does world model mean across LLMs, Robots (action-potential consequences), RL?

emphasis on multi-modal models (language doesn’t capture all of causality and consequences). Seek out interesting failure modes.

DreamerV3 —> RL world models. Deep RL course. Materials: Huggingface —> OpenAI —> Coursera —> LeRobot (former Tesla person).

Sim2Real transfer problem —> inferences about material properties in real world planning.

more bidirectional information, much more difficult terrain.

accessible robot arm —> Good RL policies for such an arm.

Imagined actions — world models. NNs with an understanding of dynamics.


Anthrobots —> soft mechanical policies (relevant to organoids). Towards Sim2Real models.

RL policy learning. Magnetic Swarm Intelligence. Representation as a control alternative.

PyMDP —> Markov Decision Processes (not as expressive as ActInf). Counterfactuals in swarm robotics.

* Multiagent RL —> Chris Reid: slime mold, ants. Ant Colony Optimization (ACO) —> Multiagent RL.

* SF CogSci reading group —> toy problems.

## TRANSCRIPT
Transcript
0:01
all right welcome um so let's get started
0:07
um we had one meeting this week we had the D.A War
0:17
meeting and I wanted to share a couple thing updates on the DOR group so this
0:24
is the YouTube channel for D.A worm and got a couple of videos in the
0:32
YouTube channel we have our weekly meeting so we have I think since our
0:38
last update we had number seven eight and N these are just the weekly meetings so
0:44
last week we talked about um this paper topon Nets which is from one of our former members or actually two of our
0:51
former members where they talk about structure and artificial neural networks how to
0:57
build topology and sort of this um heterogeneity into artificial Neal
1:05
networks uh the week before that we had the hyper graphs as renormalized graphs and cells as a Cascade of
1:13
biological machines those were two papers we reviewed there and then this video that I put out
1:21
uh two weeks ago an interactive morphal Genesis uh using moer pattern formations
1:28
to sort of as an alternative model M Genesis so a lot of stuff um always
1:37
coming out on that channel yeah and then as for the cybernetics
1:43
and cognition Futures group those are still we haven't had any new meetings on
1:50
those so those are still in a holding pattern and then our open source meetings will start up maybe in about a
1:57
month and a half I'm not really sure when we'll do but probably when we get a critical mass
2:03
of people to start that again we've had a lot of activity
2:08
in our slack um brenberg vehicle Morgan's been posting a lot of things
2:14
here I do post a lot of Robotics in bra bird Vehicles which is not necessarily
2:19
in the spirit of I mean it's it's only partially in the spirit of bra it's fine yeah but
2:27
yeah but not knowing not having another channel for it um yeah it's in there and
2:33
and you know uh I I feel bad because it's got a lot of reinforcement learning which again wasn't necessarily greaten B
2:41
well but yeah but there's a lot of a lot of policy work there
2:47
okay um but uh but it's good to see you know um David silver talking
2:56
and that's uh aner is in DAV Silver's lab okay who's doing the the neuroml gck
3:06
right right yeah for for gide project and
3:12
um uh as well as yeah interesting things
3:17
coming out for for Soft Robotics and and perhaps some
3:25
uh you know swarm or multi multi robot
3:30
control is is all in brain word let me go up to I start probably at
3:37
the beginning of the year here um yeah so we have a bunch of work
3:43
here this cell paper
3:48
on actually this is device journal and this is yeah magnetic swarm
3:54
intelligence and mass produce programmable microbot assemblies for versatile tax
4:00
execution and this is on Swarm robotics so that's a nice sort of uh
4:07
extension of brenberg vehicle work yeah yeah it's it's I I like this
4:14
and and I mean it's it's I some sometimes it's an extension of
4:20
kind of you know that robotic control especially for say like um like a kind
4:28
of like a neuroprosthesis um is is not as clearcut as um or the
4:35
representation and the way and control is is can allow for very complex action but
4:43
this is this is definitely more in the Swarm where there's kind of a collective
4:49
um Collective behavior um but um but these are yeah somewhat of an extension like
4:58
an emerging extension yeah of that of that um multi-root
5:05
control yeah
5:11
yeah uh the next one here is this uh this is Agent demo using pmdp so pmdp
5:20
of course is uh one of the things that they do in active inference um this is the python package
5:27
for um help me out yeah yeah the the
5:35
um this was posted I think on on active inference Institute or something like
5:41
that um but um you know the the Markoff
5:47
decision process as as a
5:53
um what's what's the right term for it it's like it's not as it's not as um
5:59
expressive a model as as active inference um but uh but this is this is
6:07
at the time where so we got we got another textbook um meeting for the San
6:14
Francisco cognitive science reading group on Tuesday and I'm I'm looking for more I'm
6:22
looking for the simple you know like toy toy problems that we can learn from
6:29
yeah and so this that's that that that's why that demo is there okay yeah and and
6:35
again these these relate or you know I really like the active inference
6:40
discussions that are um that set it in the context of of like
6:48
model free reinforcement learning yeah as as yeah
6:55
um so yeah anyway that that's
7:03
again I I could find a better way to organize links oh no it's fine that's
7:08
fine I think yeah I think need to go through them more often to see where we can put you know like you know it's like
7:15
kind of we get the stream and then we can Farm out everything into new into other kinds of papers and presentations
7:23
yeah yeah okay uh this one here is science robotics I believe
7:29
counterfactual rewards promote Collective transport using individually controlled swarm microbot so this is
7:35
swarm intelligence and like uh sort of count
7:40
reasoning things like that yeah yeah as well as it is somewhat relating to you
7:49
know again um following a lot of active inference Institute work um where Daniel
7:56
is always bringing up ant examples yeah yeah because he's an ant person
8:04
right yeah so this is uh this is I guess this is the paper or
8:10
is this like the summ well this is the editor summary so yeah sometimes they do
8:15
the summary articles no totally okay swarms of Agents working cooperatively
8:20
can perform tasks more efficiently than individual agents working independently microbot swarms have been
8:27
widely used for a range of applic ations however controlling individual robots within this one is
8:34
challenging youth at all present a control strategy for individual micro
8:40
robots in a swarm that relies on multi-agent reinforcement learning and the learning processor Awards individual
8:47
micro robots on the basis of their contribution to the collective performance the propulsion of the
8:53
individual micro robots is controlled by laser beams and the authors demonstrate
8:59
the potential of the Swarm to collectively transport cargo similarly to ants this is the ant sort of um uh
9:08
ant well they have um ant swarm optimization or ant
9:14
optimization as like a subset of swarm intelligence uh so that's it's
9:19
interesting that you know they're kind of drawing from that literature
9:25
specifically so it's yeah and it's creating policies for
9:30
reinforcement right multi- agent ones
9:36
yeah uh Mech lab is morphology yeah this is Josh Bard's lab
9:43
oh okay yeah so uh I I think this was maybe around the time when he restarted
9:49
his evolutionary robotics course yeah and um
9:56
he's uh I think on like 14 now okay uh I gotta say yeah neur
10:07
stuff has has caused me to fall somewhat behind in my my lecture viewing so I I
10:13
think I'm still on 10 yeah yeah but uh but he's still continuing his class you
10:20
know I love the fact that he puts everything online and um and like I
10:28
think we talked about about this time um you know it was actually in a talk that
10:36
he gave um to Texas
10:41
Tech he's doing uh so so one he's also
10:46
the anthropods xenobots guy yeah and and the the work that he's doing with Mike
10:55
Len he is simulating um he he's doing the same
11:03
biological robot work in simulation making predictions and then generating
11:11
those that that biology and in in his example of
11:17
the uh anobot is is is
11:23
getting reproducing the simulation or it's matching the simulation so he's
11:28
getting Sim to sim toore transfer uh from a biological simulation
11:35
so his his evolutionary course is mostly discussing or simulating mechanical
11:43
robots even if they're potentially soft um mechanisms but um
11:51
uh yeah I think it's awesome that he's doing biological simulations as well and
11:58
that's the most interesting for um the kind of organoid work or like again
12:05
there's so few groups that do the kind of biological simulations that he's
12:10
done um uh you know so it's the the groups we've
12:17
talked about like James Glazier in Indiana and Morpheus group in Dresden
12:24
and um tissue Forge which is which is kind
12:29
of a uh group group of Institutions anyway
12:36
great great lab to focus on lots of resources
12:43
yeah I think we talked about Chris Reeds lab Collective behavior for yeah yeah um
12:51
I forget what the context was though um
12:57
um how it how it came up did I see him give a talk uh maybe yeah could have
13:03
been anyway um who who who does he published
13:08
with uh let's take a look sorry I just to remember yeah it's like
13:15
uh lot of things with ants
13:21
uh yeah I serum work as well which is the Slime
13:27
mod oh yes yes I think
13:32
that's um I think that's what uh it was um it
13:39
was an active inference uh Institute talk uh it was a Cambridge guy talking
13:47
about um slim molds and philosophy oh right right yeah I
13:55
remember that yeah sorry just is just yeah just
14:01
helps you with the context thank you yeah actually I see a couple interesting
14:07
several interesting papers this one's interesting from an ant
14:13
perspective it says learning in Behavior ANS spine shortest paths using simple
14:18
local rules so we have of course this ant uh optimization Colony optimization
14:26
method and the idea is that ants will build these networks of trails based on
14:31
ferons and they'll use it to locate food or some other you know activity where
14:37
they're trying to navigate the space so this is I guess uh I don't know what
14:44
this is if this is like a response or like a summary of another paper this is
14:50
gar uh pnas in 20123 build simulation models to
14:56
understand how Turtle ants colle ly find efficient paths the branch networks
15:02
highlighting the importance of bidirectional traffic leakage of ants at Junctions and the ability to increase
15:09
flow as key components for efficiency their findings provide new biologically
15:15
realistic mechanisms that could improve applications in our own
15:20
engineerings so this is uh where some very specific points about these
15:27
networks these Branch Networks works you know thinking about like something like a highway system or a system of pipes or
15:34
a system of wires and these sorts of things that need to happen to kind of
15:40
make for efficient networks it's not just about finding the shortest path so
15:46
it's it's interesting um and then going into specific examples from uh The tral
15:53
Ant and talking about that and then he talks about an ant colony optimization
16:00
algorithms which are primarily designed to find efficient paths through complex
16:05
networks in the ant County optimization approach a swarm of virtual ants walks
16:11
randomly between nodes and the network the amount of pheromone each agent deposits is inversely proportional to
16:17
the length of the path that they traveled and shorter pads instantly receive a greater amount of feromon a
16:24
new cycle of exploration begins with the virtual ants favoring the strongest feromon Trail reinforcing it in turn and
16:32
the cycle continues until the shortest path is raled so this is you I didn't think about this before but like there
16:40
is a reinforcement learning aspect in ant colony optimization um and this would be of
16:46
course this multi-agent reinforcement learning type of
16:51
Paradigm did he also put something in the chat about um
16:58
and col Colony optimization and traveling salesman for own yeah so there
17:04
is also this book that has a good explanation of ant colony optimization and how it can be used to
17:10
solve the traveling sales and problem of name is Deek many or the author's name is deac manyi but thank you for that
17:18
link or the the suggestion yeah so this is this is uh
17:25
see yeah this is this from Chris Reed yeah and then the r is the Robot
17:32
Operating System yeah that's just somebody talking somebody a veteran of
17:38
um Willow um what was it called Willow garage
17:46
yeah uh this one here mastering diverse domains through World models this is a
17:54
yeah that's the most recent implementation of them the World model
17:59
that we were we were you know talking about that is kind of referenced in the
18:07
Adam saffron
18:12
RFP yeah so this is this is not like for large language models like I think we
18:18
were talking about that last week but this is for uh just general World model
18:24
for I guess a wide range of applications I mean it looks like a lot of visual
18:29
processing or you know building it for like video game models yeah
18:36
robotics so yeah they have a research paper here which is this mastering diverse
18:43
means the world models on the archive um and they show their uh
18:49
performance so this graph here actually is interesting Minecraft diamonds okay
18:55
because that's a complex or you you got to make lots of different
19:01
objects to get up to the diamonds
19:06
yeah yeah so I guess what they're doing here is they there's a control task
19:11
proprio control aari 100K B Suite visual
19:16
control ter 200m and crafter and they have the different I
19:22
guess uh I don't know what these different algorithms are I guess um yeah
19:28
all older older dreamers or yeah or some other yeah some other approaches all
19:35
right so those are basically the benchmarks and then this Minecraft diamond which is where it needs to learn
19:44
this uh task of mining diamonds in Minecraft and getting the I guess this
19:52
is I guess maximum performance is in black and then the mean performance is in Gray so they always highweight the
19:57
maximum performance uh and then applied out of the box
20:03
dreamer V3 also learns to obtain Diamonds the popular video game Minecraft from scratch given sparse
20:10
rewards long-standing Challenge and artificial intelligence for previous approaches required human data or domain
20:17
specific characteristics so again it's this world model where you build a model
20:23
of the world you know you want to try to build a model you know we talked about definitional problems with the idea of a
20:29
world model is being like you know what is a world model is it um you know sort
20:35
of a schema or conventional schema from artificial intelligence or is it something like a
20:43
you know maybe a set of rules or you know is it something that emerges from
20:50
interactions between agents and then they use that as sort of a guide uh you
20:55
know sort of a world model so we we talk talked about those in the context of large language models this is not large
21:02
language models this is a different sort of a reinforcement learning based um world model so this is
21:11
uh nice to have the contrast between the two so these are the visual domains this
21:16
is the control Suite where it looks like they're doing a lot of robotic simulation uh the atar game environments
21:24
where you have these um eight and 16 bit games where you know you're doing Simple tests
21:32
uh you know running towards a goal trying to hit a ball and you know shoot
21:38
at have first person shooters and things like or I guess third person shooters and things like that um so this is all
21:45
the Atari Suite then the DM lab where you're navigating spaces and then Minecraft which is this immersive
21:52
simulation I think a 3D simulation more accurately accurate to describe
21:59
so you have this transition from these two-dimensional environments in Atari to
22:04
these threedimensional environments in DML and Minecraft and so you know having this
22:11
sort of World Training down the sort of world you know going from a a 2d domain
22:16
to 3D domain you know it helps sometimes you need a 2d domain sometimes you need
22:21
a 3D domain you need that extra information and you know we don't get like true threedimensional information
22:28
from simulations I guess in Minecraft you navigate forward and
22:34
backward but you know it's like if you were to transfer that to a real world
22:39
test like a robot operating in the real world it may or may not transfer so but
22:44
anyways you know what is constructing this world model is the algorithm taking
22:50
like a a detail for detail account of that world whereas I just taking like
22:57
characteristics or features of of the world and using them as guideposts in general as
23:02
INF uh so you know you in these three-dimensional environments you need this sort of spatial and temporal
23:09
reasoning so you need to figure out if you need to go forward or backward if you're in a specific
23:16
situation you need to understand when things come first when things come later
23:22
and so that's that's what they mean by sort of world model is this having this
23:28
spal complexity is two-dimensional environments are spatially complex just not the same when threedimensional
23:33
spaces are you have I guess you could call them four dimensional spaces if
23:38
they include time and you have this Spa on temporal reasoning where you have things that go
23:45
forward and backward and uh you know our divers and SP or our heterogeneous in
23:53
terms of space so uh creating a general algorithm that LE Le the master new domains out of
23:59
the box without tuning would overcome the barrier of expert knowledge and open
24:05
up reinforcement learning wide range of practical applications so um they're really trying
24:12
to impart expert knowledge in these models and separate from a training uh
24:19
context so you know if we train the model on on some data it's separate from
24:25
this world model that it acquires uh you know cuz like if you think about uh when humans learn you
24:33
know we can learn new situations we can learn new contexts in fact we're always
24:38
learning new situations in context we have this world model that kind of uh
24:43
you know we kind of integrate a lot of that into uh the next uh thing so that was
24:50
and I think we've covered some of these things before maybe in a different yeah maybe so this is uh Mina
24:59
hang welcome to the Deep reinforcement learning course yeah so I think I think this was
25:05
uh this was just a an example at the beginning of the year um
25:11
when Josh Bard's course was starting as looking for some some
25:18
additional um yeah like what were the other freely available resources and um
25:26
and minha here had put together yeah the hugging face deep RL course um we've
25:33
we've talked about the open AI spinning up um resource that is now quite quite
25:41
old in in ourl terms yeah um and then um
25:48
of course the corsera of course from Alberta which is um which is based
25:55
around the rich Sutton um and um text I believe yeah yeah okay that's
26:04
good um so that's uh hugging face has a deep RL course and I didn't know they
26:10
ran educational stuff yeah yeah and you
26:16
know um so I I don't know if I've actually dropped this in here but um you
26:23
know I just C the or like I think it was last week or
26:29
maybe the week before but um hugging face has a guy who's former
26:38
Tesla excuse me um who's runs L
26:44
robot yeah um so this is like a project
26:50
inside hugging face now to produce a really accessible um robot
26:56
arm that you can use for tasks and you know as well as kind of
27:02
like yeah what's Goods RL policies for
27:07
for such an arm you know that that again um I love I love that you can do yeah
27:16
yeah the the overlap with Josh bogard's work is is cool and and again
27:25
trying to find something that um that we can then take to the next level which is
27:30
like you know imagine imagine moving the arm yeah and and you know decoding that
27:37
and then how to connect that that imagined action
27:42
together with the robot so that that that's a a second like interesting
27:48
problem and not necessarily as kind of linear as is you might imagine yeah so
27:53
imagined actions of course are not the same as World models they do kind of feed off of each other
28:00
because you have to have like a a model to imagine from I guess well it's it's
28:07
yeah I mean I think it's interesting um I
28:15
think that you get something like that though in that I think you'll start to
28:22
use um neural neural networks that have an
28:27
understanding of Dynam uh sorry in this that's in the neural
28:32
representation to coding so there's there's a really interesting paper from UCSF and um and I can I can drop links
28:40
um but of a guy controlling a robot arm you know but
28:47
with a with a invasive implant and and I think it's interesting to see what
28:55
um you know how how to open up kind of f f motor control um from that uh from
29:03
that
29:08
recording um so that's that's good this is an article from NASA demonstrates
29:14
software brains shared Pro satellite swarms so this is more
29:20
uh stuff on uh collective intelligence swarm intelligence yeah
29:28
this is uh uncertainty and contact with the world this is Aon Johnson this is a
29:33
r seminar at Cary melon uh where they're doing this uh I guess this is more World
29:41
model stuff yeah as well as that um well just
29:48
just you know the the kind of sim toore transfer problem that comes up because
29:55
your your world is is not so it's not so
30:00
clear so you know you you might have cameras that are looking down at the
30:05
ground and trying to make guesses about um you know contact strength and tensile
30:14
strength of materials that you're stepping on right but it's just some
30:19
interesting you know again real real world um problems for
30:27
these um these these models and and and how to
30:32
how to better um yeah how to better plan for them this
30:40
this also again comes up in terms of neuroprosthesis so the the people making
30:47
um like artificial legs you know find that the
30:52
more bidirectional uh information that they
30:58
can they can um enable in in these prosthetic uh legs
31:06
um allows for much more complicated much more difficult terrain to be managed or
31:13
or for a person to be able to walk faster so this this is um this is
31:21
actually really really important stuff in terms of making good
31:26
Prosthetics yeah that was the uh I think this was the paper where they talked about the Chris Reed paper ANS on the
31:34
shortest paths it talks about these different components in uh Turtle ant
31:41
colonies bidirectional traffic is one of them that's bir directional
31:47
information yeah and yeah so that's interesting um yeah but that's that's of
31:53
course another example World models definitely outside the realm of like simul models in the real
32:00
world um this one here is robot learning 2025 this is again deep reinforcement
32:07
learning and Robotics this is a playlist from YouTube I think yeah it was a in it
32:14
was a a meeting okay you know yeah yeah so so it's
32:20
um or sorry they say it was a course and and maybe maybe so but it was I thought
32:28
it was like maybe eight anyway but yeah but definitely
32:34
like Foundation models for for all of this
32:42
and and then yeah this is this is the Luma is is um somebody speaking from
32:52
um that built worked on the da Vinci robot surgical robot okay yeah yeah um
32:59
which has a lot of a lot of really interesting constraints on it obviously
33:05
you're you're doing surgery yeah so yeah so they've got some tolerances
33:14
as well as just like super fine motor action and you know these are these are
33:20
robots that are doing all this fine micro you know vascular work as well as
33:27
like they're sewing you up right yeah and you don't want to make
33:33
too many errors or have like a world model that's vague I guess well you
33:39
wouldn't really necessarily need a world model for a surgical robot because thinking would be that you could it
33:45
would be very highly specialized on the other hand you need to have for
33:50
exceptions you need to have them ability to kind of think outside of the task but yeah it it's it's I
34:00
mean I think it's interesting to think what what does World model mean or you
34:05
know yeah because it it's like like in the dreamer case you know I think they were defining the the world model
34:12
Network as the the model that given an action what
34:19
what would be the consequences yeah and and I think you
34:26
you kind of you need that you know it's like when the needle when the needle
34:32
goes in you know that there's going to be a larger scale deformation of the the
34:40
tissue kind of thing like like for instance I'm I'm not sure but again like
34:46
I I love these examples um for the the lessons that
34:51
they they had to learn from experience or you know from their particular domain
34:58
so it's like what what did the model not give them out of the box that they had
35:03
to they had to think about yeah yeah yeah so in large language models of
35:08
course we talked about world models as being a sort of causality or like taking a you know you in a large language model
35:15
you're constructing sequences of tokens and you're putting them together and they make sense or they don't and then
35:22
like you also want this causality so the model knows if something makes sense to
35:28
have one thing and then the next thing and having those kind of relationships where if you construct a sentence you
35:35
know you usually have some model of causality so if I want to describe something in the world that I've seen
35:43
with language then I have to put a a sequence of words or sentences together
35:48
that kind of where another person can follow the action so it's like you don't want to just kind of give instructions
35:55
in a jumbled way that don't make any sense to to another agent or another person and so there's that causality
36:02
that you need to master and that's above the sort of the learning that you get in uh putting tokens together or how to put
36:09
tokens together uh then you know of course in this case we have sort of
36:14
consequences which is of course causality we've talked about counterfactuals again which is a form of
36:21
causality so I think there's this causality aspect to World models that I
36:26
think maybe ties together together a number of these different cases you know if you're building them in larger
36:32
language models or reinforcement learning or you know robotics which sometimes is reinforcement learning
36:39
sometimes is an County optimization so you would have these World models you
36:45
know basically tying those together um yeah again it's super I mean you know so
36:53
one I think that also gets it why you know so many these groups are
36:58
emphasizing multimodal models now yeah you know and
37:04
and because it's like maybe yeah like language doesn't capture all of this
37:12
yeah yeah well yeah you know like despite all the texts that have ever been written yeah um um but I I just I
37:20
think of that example that somebody posted where kept on asking Chad GPT to
37:27
fill a glass of wine and show me a picture I don't know have you seen this example no
37:33
i't yeah anyway it's Ju Just back to to bender and Marcus's point you know is
37:41
that like like we focus or you know we're we use
37:48
leaderboards on the successes but you know there are clear failure modes and
37:56
what we what we should be seeking out are the the interesting failures yeah
38:01
and and the the revealing failures um to to to understand like
38:08
what's missing here um because there's there's still there's still something
38:13
significant missing yeah uh so that's uh we talked about
38:20
the AI driven robotics Club surgical robots openex embodiment robotic
38:27
learning dat us it's an RTX models that's a GitHub repository yeah okay this is yeah so
38:36
this is um it came out of somebody's talk um maybe it was David
38:44
silver um maybe I think it's somebody else's but but it was a big this is a big
38:53
conglomerate and um um putting putting all this stuff
38:58
together again try trying to you know trying to get it why it's still hard to
39:05
get a robot to pick up a ball and yet we can get them to you know write our
39:11
papers and pass medical exams yeah paper this is the
39:18
paper a paper is a blog post a code but but it's you see the open a embodiment
39:24
collaboration okay yeah so it's like this big yeah so yeah there's a data set and so
39:33
the abstract for this is large high-capacity models trained on diverse
39:38
data sets has shown remarkable successes on efficiently tackling Downstream
39:44
applications in domains from NLP to computer vision this has led to a consolidation of pre-trained models with
39:51
General pre-trained backbone serving as a starting point for many applications and they ask con such
39:57
consolidation happen in robotics so this is where you know we're thinking about non- robotics data sets non- robotics
40:05
context but then robotics where you're having to do things in the real world and manipulate things uh that's a
40:12
different sort of domain and that's why they're doing this
40:17
project conventionally robotic learning methods train a separate model for every
40:23
application every robot and even every environment so we have like C surgical robots or we have like some sort of uh
40:31
you know where robot has to run across the complex terrain or where they have
40:37
to spatially navigate those are all different sort of training regimens
40:43
different sort of methods for doing that and so you know if you were to build a robot that was a general purpose robot
40:50
or generally intelligent robot you would have to do a lot of work in integrating all these different worlds because is
40:57
robots are usually very domain specific can we instead trade generalist
41:03
ex robotic policy that can be adapted efficiently to new robots tasks and
41:09
environments so here they provide data sets and standardized data formats and
41:14
models to explore this possibility in the context of robotic manipulation alongside experimental
41:20
results that provide an example of effective X Robot policies we assemble a
41:25
data set from 22 different robots elected through a collaboration between 21 institutions demonstrating 527
41:34
skills and 100 over 160,000 tasks we
41:39
show that a high capacity model trained on this these data which we call RT DX
41:46
exhibits positive transfer and improves the capabilities of multiple robots by
41:51
leveraging experience from other platforms so I think that they have this
41:58
uh image if I can zoom in on the
42:06
image so this is uh I'm going to focus on this here so they have 22 embodiment
42:13
so the 22 different sort of shapes uh or phenotypes or a robot they call them
42:19
embodiment they have 527 skills so they have pouring stacking rout I think was
42:27
it last week we talked about the stacking and and uh so there's a data
42:32
set where they do stacking and then they do like piles and they have to pick from one of
42:38
those two and there's there's a whole subfield on like stacks and
42:45
piles and that that sort of thing so that that's that's you that's an interesting area to get into looking at
42:51
how they deal with how robots learn from their environment and the kind of data sets that they use
42:59
I I like I like this in particular because it it matches the the philosophy
43:04
behind um the Moab project ATX which is
43:10
the big mother of all BC benchmarks yeah and and it's the same thing where it's
43:17
just like it's like you if you train on kind of one data set you know you you
43:26
certainly in isolation you can start to just pick up a bunch of idiosyncrasies
43:31
from it um and you really want to train across a whole lot collect it in a whole
43:38
bunch of different ways and you know collect it with a bunch of different equipment yeah yeah you know and and
43:47
then you're you're yeah getting something that's that's Much More Much More General and
43:54
much more applicable to to new situations and then you have so then you
44:01
have see of embodiments ways in which you kind of have your phenotype or ways
44:07
in which you can manipulate the world you have your skills which are these different things pouring stacking route
44:14
following and then these data sets which have attributes objects and spatial
44:19
relations so these are just breaking down like I guess if you have like a skill like pouring or stacking there are
44:27
a lot of sort of tasks within pouring or within stacking and that's where you get
44:34
these uh different aspects of the environment attributes objects in spatial
44:39
relations so you know um I I like this kind of organization here where we have
44:47
you know we kind of this hierarchy of thinking about embod going from the
44:53
shape of the body or the shape of the phenotype to these different different skills which are you know a lot of them
44:59
are very different and so you have to kind of think about all these different of course you don't want to just think
45:05
about the skills that we Define as you know a kind of a top- Down definition
45:13
you might want to think about all the contexts in which a robot is so there may be skills that we don't recognize
45:19
for I mean you know all sorts of skills that like people have a lot of skills
45:24
for example that are hard way kind of put your finger on what they are and sometimes there are skills that
45:32
are very obscure sometimes there are skills that are very obvious
45:38
um but you know like playing a certain sport you know that's a skill is that
45:44
something it transfers to some other motor activity or some other strategic activity or you know is it something
45:51
that if we don't invent the sport for it you would never know you have the skill for so skills are kind of an interesting
45:57
category because we can Define skills from The Real World but there are many skills that you can have that kind of
46:04
lead from this world model that you might not you might need in some unseen
46:11
context that you can then apply but you know you have to have the model for that
46:17
and then you have the data sets which include all these tasks that you might do in coring or stacking so you might
46:23
stack flower pots or you might stack boxes or you might stack marshmallows or
46:30
you might stack uh dimes and they're all the kind of different variations on that
46:36
skill so that's the so this is open X embodiment data set uh they you kind of
46:42
break down their scenes their trajectories and um aspects of the data
46:49
set and then they kind of show what they're do is a robot is asked to route a cable pick an apple from a top door
46:56
place on the counter pick up the orange fruit so it's doing these you know kind
47:01
of fine motor tasks it's identifying objects and it's identifying like shapes
47:09
and colors and so it's using semantic labels so it is multimodal in that sense
47:16
that you have motor learning you have uh sequence learning procedural learning
47:22
you have semantic learning or language learning and then you have the
47:27
instructions you have the images you have this Transformer and then you have these
47:33
discrete actions and then that's where the actions are executed given the sort of the learning
47:41
of these things and the processing of the information all right moving on uh this
47:47
is the toward superhuman intelligence talk by David silver so this is we
47:52
talked about David silver earlier what did you want to say about that
48:01
sorry I wased um he uh you
48:08
know very well known as being the person who did
48:14
the the Deep Mind RL course right sure or certainly the the lecture series that
48:21
that Deep Mind released you know this is the um the
48:27
kind of expertise that he's coming from um at this particular conference um oh
48:34
yeah okay okay VI's used those too um
48:40
and uh so when when I saw this particular
48:48
talk um I I was curious where where he
48:53
fell um in in um
48:58
you know H how we're going to achieve this
49:04
um Mythic uh super intelligence or you I
49:10
mean you know so when people are using superhuman they're saying that like you know they're still saying that like
49:19
um we've achieve superhuman performance on Atari right I I I think it's it's
49:27
interesting that you know there hasn't been as much followup on how the game of
49:34
Go has changed since since alpago right but like humans humans have started to
49:40
play differently yeah and and I'm not saying that
49:45
necessarily means that they can take on a uh well perhaps they could or you know
49:53
certainly you see this um you
50:02
yeah there's there's a difference in play anyway it's it's I wanted to see how nuanced this this particular talk
50:10
would be or if it was you know if he if he's fallen into a certain uh um I'm a
50:17
I'm a marketing mouthpiece for my my Global
50:23
conglomerate local conglomerate again Bender and and not not just Bender you know Corey Do's
50:30
point that like like these companies have every reason to lie right like like
50:38
their stock price their their you know immense personal wealth all dependent on
50:46
you thinking that these are superum you know and that tech companies are capable
50:54
of you know waving magic wand right and and making you
51:01
know Making Science available you know from from your smartphone yeah right and
51:10
yeah anyway so superhuman is defined as
51:15
like above human performance on tasks you know and and it gets to this
51:21
um you know debate that like um what's
51:27
his name hon and and I made
51:33
yeah not that I'm putting myself in the same camp but but I I made the same mistake in the sense that like I was
51:40
just like oh God you know I I was amazed in 2012 before you
51:48
know image net working in Radiology about how Radiologists worked
51:55
you know and and um I I was super surprised that Radiologists don't use um
52:04
um pseudocolor Imaging for looking at
52:11
grayscale uh grayscale data for instance right so if you go to you know UCSF like
52:22
top top 10 kind of Hospital in the country um and you go to one of the
52:30
Radiology reading room suites you know these are these are dark rooms with very
52:37
expensive grayscale monitors very expensive screens
52:44
optimized for viewing these kinds of images
52:51
and I was just like well it doesn't matter what they on the
52:57
screen their eyes could only handle like a certain number of levels of gray like
53:04
what's the what's the screen matter you know um and and as someone
53:11
who's gone through the kind of training that satellite imagery people have you
53:17
know in in Colorado like like military satellite
53:24
analysts do not use do do not limit
53:29
themselves to the um
53:35
um the particular yeah the the particular data
53:41
that they were seeing or you know like like if if they've received
53:46
um um well just just just just that point
53:51
right I mean part of it is that they they moved you know they they do deal deal with what they call hyperspectral
53:58
Imaging so um frequency is is a much larger
54:05
dimension for them because they're collecting data from infrared through
54:10
right and um so they're actually typically looking
54:16
for ways to do some sort of dimensionality reduction across
54:22
frequency and and then to to match match like say the top three
54:29
principal components to red green blue so what you're looking at what
54:36
you're looking at is yeah is not is not color yeah right
54:44
you're you're looking in in Igan space or you know yeah you're looking at um
54:53
um IG components or well components matched to color because because sorry
55:02
this is the the final point because your eye is the is the perception you know
55:08
this is what you're trying to get it uh set up as as you know as as as an
55:19
input for because you know for this per receiver system um
55:26
and and you know it just seems like Radiology was right for a a better way
55:35
of doing it you know and so that was the famous hint in like 2015 I think like you know
55:44
Radiologists will be out of you know Radiologists will all be out
55:50
of business in five years or something like that I forget I forget what his time frame is right
55:56
but I I I I said definitely said the same thing to myself and said the same
56:02
thing in terms of just like why don't they you know why don't they add color
56:08
to these images in terms of of you know using algorithms to find to find
56:16
interesting to find interesting things and then to to add color to those things
56:23
for instance you know like again like it just make sense that you still had people reading them like they were
56:29
reading x-ray slides yeah but but we're here you know like
56:37
like I mean I I I keep seeing these examples but I'm sure like you you know
56:43
you might follow somebody like Eric toel um you know have they they've not
56:52
they've not taken on the medical Market even though you keep seeing these
56:57
examples where it's like they they outperform a radiologist on a very
57:03
limited um dermal cancer task or something like
57:10
that well I mean that's interesting from a cognitive model and computational
57:16
Neuroscience standpoint is like what what are what are we doing in terms of
57:21
like processing an image in terms of our brains and then what could computational
57:26
model do like a a artificial intelligence agent so like what are they
57:32
using are they using igen space are they using like cie values and then like what
57:38
how does that translate to Performance so there's some breakdown of the sensory
57:44
information there's some internal representation of that or internal sort
57:49
of transformation of that and then there's a performance out so if like a algorithm is using like a complex igen
57:57
Space versus like our eyes are using like you know some sort of differencing
58:03
of color or whatever we're not using Color at all then of course that might explain superhuman performance whereas
58:10
if you know maybe maybe uh the methods are sort of maybe the methods that we're
58:16
using are superior to what an AI is using and that goes of course to World models but also to this sort of sort of
58:24
gibsonian type model of processing yeah so yeah this you know I
58:32
mean that's that's I thought it was super interesting that the satellite imagers
58:37
were in a sense setting things up for pop out effects yeah right you know so
58:44
it's just like they they seem to know intuitively or or not that that you
58:53
you want to tr transform your data to the point that that humans get pop out
59:01
effects of the things that you want to pick out which made me like you know rocket launchers or you know whatever it
59:08
is yeah right and um yeah yeah so
59:17
yeah yeah I'm still thinking about this so we we'll come back to this later yeah
59:23
yeah yeah so I mean we we had something else in the chat this is a YouTube video here that was put in there yeah yeah
59:30
that that that's the playlist of the deep Minds RL David Silver's course okay
59:35
I it could be pretty old I mean like 2018 or anyway but like you know but
59:43
it's one of those that it might be in Mina's list of of good you know RL
59:51
resources yeah yeah yeah all right so then uh
59:57
yeah let's see we have building robots at home uh some other robotic seminar stuff
1:00:05
this is uh things from the maker Lab at Illinois Sig robotics at Illinois then
1:00:11
physical intelligence yes this is um this is a group and I um I I'm
1:00:22
assuming that there may be like former opening people or something um but but
1:00:29
physical intelligence is its own group um and open pie is their is their
1:00:38
model yeah um or yeah hit that is it is it a team at
1:00:45
open or is it their own company uh I think it's their own company I can't I
1:00:50
think it's their own company and it's probably you know again it's it's yeah
1:00:56
and it's like it's a whole bunch of VCS and and Jeff Bezos okay yeah anyway
1:01:06
um but this is this uh definitely comes
1:01:11
from the the really awesome Buzz robot um group in in terms of speakers so so B
1:01:19
Buzz robot gets great she like I I wish I knew how
1:01:24
she got so many great speakers but she she's the one who got the little robot guy just a couple weeks ago and
1:01:30
then this this was the talk like a month or like a couple weeks before the robot
1:01:36
okay yeah oh oh and and then Aloha there
1:01:42
right um so I think we talked about this but that um this is
1:01:48
what um I think his name is Remy from the low robot guy um this is the paper
1:01:55
that he said was the real uh um breakout for for
1:02:05
manipulation arm arm manipulation okay
1:02:11
yeah right so the novel novel action chunking so it
1:02:21
just you know again wonderful wonderful overlap of you know
1:02:26
cogy Robotics and and um machine learning
1:02:33
yeah all right uh and then finishing up yeah loha that's the link to the oh God
1:02:40
yeah yeah yeah all right yeah and looks like V joined uh the greenber vehicle
1:02:46
Channel I forget what L kiwi is but um I think Remy um has a a
1:02:56
like a a post since his talk about some L kiwi developments which assume is like
1:03:04
an added a more complex Little
1:03:11
Robot all right so that's good uh thanks for that that was a pretty good discussion on brenberg vehicles Channel
1:03:18
s of unpacking all the stuff in the channel I think you know we've talked
1:03:24
about world models but it's like there's a lot of stuff there there's like these kind of conceptual models there's like
1:03:31
you know World models for different types of types of artificial intelligence uh
1:03:38
different types of learning we have multimodal models of this so I think
1:03:44
yeah definitely getting down going down that road some more and and just for for v um if uh um
1:03:55
you might also check Dev neuro AI um because again sometimes I I don't
1:04:04
know where best to put some things but you
1:04:09
know related related topics could potentially Robotics and other things
1:04:16
that um that might be important for for that discussion yeah Dev yeah and it it
1:04:23
somewhat somewhat reflects the discussion that um that Jess uh or the
1:04:31
the meeting that Jess posted on developmental uh cognition I think was
1:04:36
the the group name that met in Boston this is yeah this is the one that
1:04:44
uh I think in general General yeah it was in general that was yeah the one
1:04:49
here that just posted the other day yeah so this is on YouTube this was a meeting
1:04:55
was yesterday it's on developmental I think psych like developmental
1:05:01
psychology developmental things so yeah yeah cognitive cognitive development yeah
1:05:07
cognitive development there's Jesse right there um and yeah so I don't know
1:05:12
if Jesse had anything to say about that I don't want to put him on the yeah I would love to I'd love to hear yes I may
1:05:18
be able to say well I can say a little bit no um
1:05:26
in short um I I've been around eapo for a while
1:05:35
but I haven't really done any they've they've hosted a number of
1:05:40
events like here in boss and other places too and they're kind of coming and I don't like Morgan knew more about
1:05:46
them or or or some of the the people there which is I know of them through my
1:05:52
experiences but not um that much and it was just nice
1:05:58
because it was sort of it it actually was sort of like one of our longer it like a long open-ended meeting on a
1:06:04
subject topic that we do and sometimes so it ended up being the first one I forget what was about um
1:06:12
entirely um I guess it was the poly math medical one and then there's one yesterday also about kind of
1:06:20
Developmental approach to cognition and a lot a lot about plasticity um but but also dub tail into
1:06:27
a nice conversation around sort of uh I was I was I was I'm saying the word
1:06:34
wrong but hom hesis hornis the one that's like a small change creates an
1:06:39
impact and you come back from it and then it has like over corrects or something like that hores I think yeah
1:06:47
yeah um and so a lot of um in instance the polyon
1:06:54
was kind of a warm warm for their events next week they have a number of very big events cool events Mikael 11 will be
1:07:02
frally attending to one of them U but but a lot of um things in Florida uh a lot of the
1:07:11
group is based out of Florida Atlantic and um there's an event there next week
1:07:20
I think two two different events um I'm not going to be there but the first one is going of a warm up for that and
1:07:28
um it was a nice well of discussion about you
1:07:35
know where where could um it was it was it was it was quite
1:07:41
Broad in some ways but but some of the the focus topics were on um you know like where
1:07:47
can what what a future future istic Hospital look like and and how how would it go from what a hospital is now to you
1:07:54
know um what what limitations may may change in in in time
1:08:03
um which is you know interesting in the context of the moment we're in in terms of healthcare right now but it was it
1:08:11
was good and it was it was um that was part of it and then yesterday was uh
1:08:18
interesting um Addie who's sort of the founder or or you know I don't I don't
1:08:24
know the right word to say but but the person leading these um salons and in a lot of the direction
1:08:33
of where things are going there for sure um has a very
1:08:38
interesting uh take on like sthesia and and kind of this interest
1:08:46
in um a different
1:08:53
sensory uh interactions either complement or
1:09:01
can lead to enhancements like there's a number of things that were talked about
1:09:07
that um you know kind of fit in the space of kind of essentially biohacking type
1:09:14
stuff but um I really enjoyed I enjoyed all of
1:09:19
them but I enjoyed the conversation yesterday too in the sense of um
1:09:26
yeah getting getting at a broad level of what what either in an agent or a system
1:09:34
you know what's what's sort of the line between perturbance and um you know
1:09:39
detriment or deterioration or like just enough agitation or stimulus to
1:09:45
provoke useful changes um and that that was sort of a
1:09:50
it was sort of a nice overlapping theme between the two I think there's also another one today like because there's a
1:09:55
series of like small the like salons or or or big big discussions they're having
1:10:01
and um you know what I can say here also is that there's a few like specific
1:10:09
projects that that that they're trying to push forward and and there's a
1:10:15
there's a little bit of overlap too I would almost say um
1:10:22
as a group um similar to us in that
1:10:29
they're very interdiciplinary focused
1:10:35
and um okay with exploring some of the niche spaces and and sort of you
1:10:43
know this you know um the challenge of doing that you know
1:10:51
the challenge of how much like even even me you know uh we kind of evolved too
1:10:59
this meeting is just a big a big you know Saturday meetings of this you know it could be anything and then we Branch
1:11:05
it off into these more focused discussion groups this is sort of what we've done to handle that but there's
1:11:11
still sorting out what they want to do in certain ways and what what what pillars do they want to focus on
1:11:18
and um oh you know they they are selecting for that
1:11:25
and have a lot of really really really interesting uh people who are doing
1:11:30
interesting projects and other things that I think we'll hear more of publicly sooner
1:11:37
um but I've really enjoyed their um events
1:11:44
and it's sort it's it's it is different in that
1:11:49
um they're trying to host and do events differently and in different set of structure different set of things here
1:11:57
but a lot of um the actual respect for trying to
1:12:02
pursue inquiry and not being afraid to throw as that says like wrenches into questions and and the sort of you know
1:12:10
open openness to uh like really trying to to get in
1:12:18
and out of um a topic and and really shake it up I
1:12:24
I is is interesting and nice um so I don't know there's a lot of
1:12:31
small things that that could be said um about specific topics and things like
1:12:38
that um one of them I um was very much
1:12:43
reminded of our um previous work on like I think it was something like developmental freedom and then
1:12:50
developmental whatnot one of the questions that came up with the plasticity one was essentially um
1:12:57
how you know how much is too much plasticity and why do we need plasticity and I think I I shared something and
1:13:02
took this you know I I a screenshot of one of my my quotes and we didn't really
1:13:08
go down this route uh but but I immediately thought of like a lot of our developmental work um you know kind of
1:13:18
operating in these bounded constraints of you know
1:13:23
when an organism is developed Ving yeah when an organism is developing
1:13:30
you have this I I go back I was I go back to one of my first like
1:13:39
Neuroscience actual experiences in a lab where I was trying to understand you know at whatev at what at what day of
1:13:47
being alive does in this case you know a mouse or a
1:13:53
lab Lab mous have start actually showing a circadian rhythm in
1:14:01
development and and all these questions about like well it's not right away you
1:14:06
know because certain certain structures have to emerge and develop before things can even synchronize to
1:14:13
it and and obviously many different spaces are different you know dials or
1:14:19
this or not different kind of rhythms but just sort of like um at at a bottom up level the the
1:14:25
the the necessity for things going on I I think I did a
1:14:32
quite a well and the other and the other the other end of the spectrum was or the other side of that is like the you know
1:14:38
the death um the inclination towards okay well you know in maybe in an
1:14:45
evolutionary sense well you're this you know you're no
1:14:50
longer very good at producing stuff and you just need to get out of the way so we're going to you know start showing
1:14:57
you the door in terms of your maintenance and there that's one way to
1:15:03
say it but but sort of this my main point which I I think I did
1:15:08
not articulate very well and probably won't do here but but it's something that we have talked about a lot in our
1:15:13
like Futures and memory and a lot of Developmental stuff is is sort of how
1:15:20
um there is just uh there isn't a
1:15:26
static um um things aren't static there there is
1:15:33
an estatic thing there's an estatic conition there's an estatic um state of being there there's this constant um
1:15:41
movement and constant you know very uh you know um what what are the qualities
1:15:48
of being alive you have you know you're you're taking things in you're letting them go you're changing and and it's
1:15:54
sort of like that's that's quite obvious in sumar but it's almost like a lot of the a lot of discussions around these
1:15:59
topics tend to be um I don't know
1:16:10
um very centered on speaking as if like the
1:16:17
mind or the brain even though we're talking about plasticity is like just the sort of uniform chunk of play that
1:16:23
everybody has the same you know model of and and and it was sort of fun to kind
1:16:30
of tease out um these different takes on on what's influencing that but um and
1:16:39
finally I'll I'll kind of say um it was it was interesting to
1:16:46
basically look at um and this is this is the one yesterday
1:16:51
I'm I'm kind of concluding about but you know the age-old question or or you know
1:16:58
how we it kind of reminded me of um similar to that like how we talk
1:17:04
about in this lab or have for the last few years uh
1:17:10
um analog versus digital kind of a thing like this just
1:17:16
gigantic um it's not a debate I don't really know
1:17:22
what to call it but just sort of how do the things relate or not and it kind of
1:17:28
felt a little bit similar to that it's obviously not the same topics but but the way of the question is like the
1:17:34
plasticity question and and in in in kind of a neural sense yes but also at
1:17:41
is very like what about like what about the body too what about um like muscle and and and there's other things that
1:17:47
basically would perturb in this case it was it was mostly biological focused here but something that perturb
1:17:55
a system and yes how much but also sort of
1:18:00
um what are the there was a nice there was a nice arch of the conversation that I I kind
1:18:07
of wish materialized a little bit more but basically about what is too much
1:18:12
plasticity or why do things need to be not plastic at times and that's kind of
1:18:18
where some of our de work on developmental Freedom versus developmental like I forget it was capacity or something else um made a lot
1:18:25
of sense to me because like you have to do that also last last particular point
1:18:30
of interest um there was a really interesting conversation the day before
1:18:35
which actually more so fit in in this one but came up in the wider ranging like poly mathematical one which is
1:18:42
about um I don't have great language for it
1:18:48
right now but um it was
1:18:53
essentially how it was sort of about you could say attention or Focus but how when you are
1:19:02
like like I think uh one of the people cited a bunch of experiments in chess and how the more trained in chess you
1:19:12
are the less actual like there's a there's a weight to your memory over
1:19:19
time and like you don't think of or remember invalid chess moves
1:19:25
as easily as valid ones so it's like you I I I I said oh so it's like you
1:19:33
have more Nuance you know and I and there was like oh actually it's less he
1:19:39
like no actually it's less Nuance because you have less overall Nuance but more uh I think the word was syn
1:19:46
synthesis and like a greater refinement of what you can do in the context of
1:19:51
things that are right or valid chest moves but you but the the mind kind of
1:19:57
cancels out the things that that don't don't um
1:20:03
aren't valid and that's sort of sign of an indication of like sort of how the
1:20:08
expertise of something like if like if you speak English all the time you kind of tune out invalid ways
1:20:17
of pronouncing things but if you go to another language or another language you can hear or speak differently um in in a
1:20:25
way that challenges that kind of going into um the more specified Nuance things
1:20:33
they're more no the more specified uh I would say detailed things and and the lack of a
1:20:39
broader um decontextualized Nuance I would say and so
1:20:46
um that was that was sort of an AR of conversation that I would imagine would
1:20:53
continue to the next event which I think is today and I may may not to go to it but point being
1:21:01
um it was it was a nice these these salons as they have been so far have been the sort of big
1:21:08
big broad ranging things and and I think I think they're kind of um adjacent to some we've talked about
1:21:16
and if people want to go to them and invite some of the topics that come up I can um see about that uh but I think
1:21:23
they're also they're going to have a these are it they don't just do salons they've done
1:21:29
like some hackathons and and some things here there's one here at the MIT media lab which I didn't get to go to but um
1:21:35
uh inadvertently met some people there and stuff through it so um they're doing
1:21:41
a lot of fun stuff and and we'll see where they go in the future so any questions I know I did a lot of
1:21:48
conceptual bounce around but no I think that's some good stuff to
1:21:54
follow up on um there was OB quite a bit more but I kind of selected for things
1:22:00
that we kind of especially some of the concepts that like you tied it into developmental freedom and and some of
1:22:05
these other things that we've done in in papers and that and and that might be more you know it might be interesting
1:22:11
just to do a paper on developmental freedom and kind of revisit that concept and kind of lay that out in terms of
1:22:18
artificial learning animal learning Etc um and you know well we'll have to come
1:22:25
back to that I think that's really great and this whole idea of like you know
1:22:31
learning an adaptation and kind of how those merge together with development and you know this is something that is
1:22:38
kind of always interested me but is is more generally kind of you know it's
1:22:43
it's it's like this huge topic that people kind of approach from different angles and it's kind of hard to get your
1:22:50
arms around what to call it because it's kind of like it you know you have you know adaptation you have development
1:22:57
you have learning you have uh plasticity and there just kind of all these things
1:23:03
operating and like kind as stitching together unified theory of all this is
1:23:08
hard to you know and in having these kind of Concepts where we can say oh
1:23:14
yeah that's something that applies to you know animal learning but also to
1:23:19
artificial models and kind of think more deeply about these these forms of learning
1:23:25
uh that's that's I think that's valuable but it's people haven't spent nearly as
1:23:30
much time on that as maybe we should right and I I kind of I mean they're
1:23:37
they're very familiar with with Michael Le is's you know going to be speaker at
1:23:43
event and and they had people from Lev's Lab at stuff that events so they know
1:23:49
about him but also um I I mentioned a little bit on diverse intelligence is
1:23:55
and um even dizzy the summer Institute uh and it's just like yeah like you know
1:24:02
no nobody I I think I even said as much like it once is like nobody really
1:24:09
cares like like people do care but but it's it's not it's
1:24:14
not um profitable or useful to enhance
1:24:20
things as they are right now you know so um
1:24:26
and that's that's that's a that's a harsh and a negative stance but yes like
1:24:31
that that it's um I always enjoy being able to talk with people that are kind
1:24:38
of aware of those here's a space you know that could
1:24:44
go in a certain direction and are willing to kind of try to we had a very
1:24:50
nice like sub conversation about like how do you
1:24:55
create environments for people to do the work that lets their um I don't know try to
1:25:05
make progress on these things it's hard to do like we've talked like even like our tally bir stuff and that whole thing
1:25:11
we said about like that conversation across time like like you kind of have to are you have to like create enough
1:25:18
stability and the conversation in the group over time to do the work to make
1:25:23
like my my my vantage points essay which I don't know if I ever it really shared here or not but like you have to do this
1:25:29
this work of just building out Vantage points and trying to you know connect them and so on and so forth so it was it
1:25:35
was sort of nice to talk um with another group in the
1:25:40
situation A of quite a different group in in terms of some of what they really want to focus on in the short term and
1:25:47
maybe other things but overall like um quite sympathetic to what you said in
1:25:53
those challenges and uh yeah I mean it's so funny because
1:25:58
I've known about them for a long time and as we all we know here I haven't
1:26:03
been around much and I've kind of I'm coming out of this winter of sorts um
1:26:10
metaphorically and and literally so it was kind of a nice set of warm-ups
1:26:16
and things to do and ways to talk about and we'll probably have things ahead maybe maybe in the future some kind of
1:26:23
an overlap of efforts between the groups but at the very least interest you know
1:26:28
very interesting people doing very interesting things and um in a lower
1:26:33
head there you know what the name of the group is yeah um echol opto so this is the
1:26:40
echol opto this is a I guess a group experimental inter disciplinary research
1:26:47
group focused on modeling and enhancing General cognitive systems so the website
1:26:53
is here science art stronger together and they
1:26:58
have yeah cool smells really smart people they have these I guess different
1:27:06
groups they have a cognitive hackathon a new salon I guess that's where they do the talks New Vision H
1:27:15
math yeah yeah this is really interesting stuff yeah and add like Addie's um
1:27:24
the person you saw in the video like he that yeah
1:27:31
um yeah you can see some of their events down there like they've done they've had things in like around Florida Atlantic
1:27:37
you can see the f um and they kind of H I think I think
1:27:45
they're in a period of like doing a bunch of these salons recently and then next week it's a bunch of events in
1:27:51
Florida and and they kind of you know they they kind of um there's not like I don't I don't know
1:27:59
I don't really know I don't I'm trying to speak like I know them very well because I don't but it's not quite the
1:28:05
same as like we have the standard meeting every weekend they they have sort of a a co
1:28:12
uh I don't really know if I could say cohort but a collection of people interested that have a lot of deep relationships about certain things and
1:28:19
um yeah meet regularly and put on events too which is pretty cool okay I I think
1:28:24
I know who these people this is Florida Atlantic Alon bar Holtz is yeah one of
1:28:29
the people here involved so yeah this is this is good um yeah it's interesting it looks like
1:28:36
it's very uh very new and exciting
1:28:42
stuff yeah um I I think a lot of good things will
1:28:48
come from them I'm happy to um I met them through
1:28:54
uh Dan Elon who is
1:28:59
um you know long time Dan and I grew up in the same
1:29:05
Hometown and then both went to Boston and then he left Boston and and den you
1:29:11
know did a lot in Ai and healthc Care spaces now and we kind of uh
1:29:18
um I don't know I kept I kept having all these misses with with echol opto um
1:29:24
in person like last fall and summer and I'm sure I'll be doing some
1:29:32
more things done ahe so good stuff and I very appreciate you know being invited
1:29:38
to um go to the events and share things and then have like um conversations I
1:29:43
found it on a personal level like I found um it's it's very important to to uh
1:29:54
stay in touch with people and talk about things that are interesting and things that do have meaning and can affect the
1:30:04
future it's sort of like my self-care is to intentionally do it and they're a great Community for that where people
1:30:10
like that care on our driving similar to we we're doing that here too and I I'm I'm very glad to be back here um with
1:30:16
this group more so and and appreciate our conversations as well I think it's a
1:30:21
maybe even a public good on some level but um good for me for sure so yeah so
1:30:30
uh Trevor Tanner who's he posted this paper on cell cell genomics paper on
1:30:37
effects of Gene dosage on cognitive ability function-based Association study
1:30:42
across brain and non-brain processes so this is yeah go ahead I know I know I
1:30:48
know David Glenn there okay yeah David Glenn okay so this is the graphical AB
1:30:54
you know Trevor is interested in behavioral genomics and and and cognition and things like that
1:31:01
so this is where they sampled
1:31:22
28,2928 people when you correlate it with things like cognitive assessment or
1:31:28
sometimes phenotype uh these use these uh Gene wide Association study uh type
1:31:35
approaches where you look at um the G
1:31:40
the CNG the copy number variation then they have this functional burden analysis which is where they have
1:31:47
a biologically defined set of genes where they look at whole body tissue genes brain region genes brain cell type
1:31:55
genes and uh they use go terms to sort of Define this so this is the annotations that typical annotations of
1:32:03
genes that you find then they have this so for this Gene Set uh they have an effect size which is based you know
1:32:10
roughly related to cognitive ability um they have this result where
1:32:16
they they look at um it looks like there are two classes here confers protect
1:32:22
protective effect or increases cognitive ability and then looks at then they look
1:32:28
at the effect of Gene set on cognition or the effect size of a gene set on cognition DM brief Freeds copy number
1:32:36
variants are major contributors to neurodevelopmental disorders and are
1:32:41
associated with lower cognition uh H had all identified a duplication increasing cognitive
1:32:48
ability they highlighted the gene that genes of many biological processes had unbal balance Gene dosage sensitivities
1:32:56
towards deletions or duplications for both brain and non-brain functions so
1:33:02
they're looking at this group of people this large group of people they're doing
1:33:07
a cognitive assessment they're doing a gene wide Association scan they're
1:33:12
looking for these copy number variants they look at the copy number variants in
1:33:17
terms of deletions and duplications so sometimes you can miss an a we or sometimes the wheels are deleted
1:33:24
sometimes they're duplicated and then you look at that those two classes you annotate those genes and then you uh
1:33:32
look for you know different reasons why they might be duplicated does it
1:33:37
increase cognitive ability does it confer protective effect and then you look at the effect size on this Gene set
1:33:43
on cognition so you look at what deletions and duplications give you and
1:33:48
this tag DS method which let's let's take a look at the abstract
1:33:54
to learn more maybe about that uh so yeah copy number variants
1:34:00
that increase the risk of neurodevelopmental disorders also affect cognitive ability so this is where we
1:34:07
have variations in copy number of wheals uh that increase the risk of
1:34:13
neurodevelopment of disord so sometimes you have things that are sort of you
1:34:19
know duplicated that affect cognitive ability but also set of neurodevelopmental disorders so you know
1:34:27
that's the kind of thing we're looking for we're interested in that however such uh cnvs remain challenging to study
1:34:33
due to their scarcity limiting our understanding of gen dose such sensitive biological processes linked to cognitive
1:34:41
ability so what we want to understand is how does Gene dosage or number of copies
1:34:47
of a of an a how does that uh link to
1:34:52
You Know It it's involved in these biological processes that are linked to cognitive
1:34:58
ability uh we performed a gene wide Association study or gwas in
1:35:10
28,2928 three associated with higher cognitive performance so they were able
1:35:16
to identify specific uh copy number variation associated with higher
1:35:22
cognitive performance we developed a functional burden analysis which tested
1:35:27
the association between cognition and copy number variation disrupting around
1:35:33
6,500 Gene sets biologically defined across tissues cell types and ontologies
1:35:39
that's where they were annotating the different genes and cell types and tissues among these 864 Gene sets were
1:35:47
associated with cognition and effect sizes of deletion and duplication or negatively correlated so this is where
1:35:54
they had the scale um the latter suggested that functions across all
1:36:00
biological processes or sensitive to either deletions so this is the
1:36:05
subcortical regions and post synaptic uh related genes or or
1:36:12
processes or duplications cerebral cortex pre synaptic processes so we have
1:36:20
delions and duplications being associated with different things going on in the brain associations between
1:36:27
non-brain tissues and cognition were driven partly by constrain genes which
1:36:32
may shed light in medical coral bidities and neurod development of disorders so it's a nice study goes over
1:36:39
a lot of uh technical stuff that I'm not going to get into but um this is yeah
1:36:46
this is an interesting link between uh genomics and
1:36:51
cognition and some of the things that are driving like the evolution of cognition and developmental
1:37:01
disorders so again I you know this is a little bit beyond what I want to get into here
1:37:06
but well I think I you know I think it would be good to
1:37:16
say that it's behind perhaps subtle but complex
1:37:26
structural differences yeah yeah you know you see what I'm trying to
1:37:33
H here like but as well as
1:37:41
like at what level at what level is is it
1:37:47
um is it operating um to to to
1:37:54
yeah yeah yeah this this was interesting so um
1:38:02
I've I've done work with David Glen okay on bipolar disorder
1:38:08
yeah and I mean in terms of brain Imaging yeah yeah right um and
1:38:16
and I don't think we did anything genetic
1:38:21
um um but so so this was interesting to see though I'm glad Trevor passed it
1:38:28
along because it it's it's an interesting um little rabbit hole
1:38:34
down psychiatric genetics yeah U but but again like like I'm more
1:38:41
and more lean towards psychiatric genetics as as
1:38:49
like brain brain structure uh uh structural composition and and
1:38:59
Physiology in know kind of Michael Le you know like I mean in the sense that
1:39:09
um how how responsible is genetic control over
1:39:16
organogenesis yeah and yeah and and Etc but um it's a
1:39:25
it's a um I'm just seeing some papers here
1:39:31
from you know looking at the the large ABCD data set which for some reason has
1:39:40
a registered Trademark Sign like why does it like ABCD is an N
1:39:50
imh thing with like it's got a well I think they yeah people just do
1:39:56
that things to that's that's frightening
1:40:02
anyway um I'll figure that out later yeah but
1:40:10
it so so you know but as it relates to cognition me as well as
1:40:15
this um as well as these points that um come
1:40:23
up up in psychiatric genetic or they're more likely to come up in psychiatric genetics when people are
1:40:29
trying to explain why these things um could be selected or like like
1:40:38
like evolutionarily how did we get here yeah and as opposed
1:40:44
to yeah just just um as opposed to
1:40:50
putting them in a in a I guess I like the context that leav has
1:40:57
where every everything's imperfect and everything has cognition yeah or like
1:41:04
like yeah everything has agency or you know anyway but
1:41:11
um yeah so nice thank you Trevor yeah
1:41:16
yeah and yeah if anybody wants to go down these rabbit holes like like again
1:41:22
like a uh uh that my my college doesn't have a
1:41:27
lot of scientists from it um and but I I had one it was Pamela
1:41:36
sclar and she her Focus was was psychiatric genetics so so she was my
1:41:43
hero because U she was the one putting together these larger and larger data
1:41:48
sets of that included schizophrenia and and in terms of trying to you know um
1:41:57
what Sam baries calls the je genan hunting right so you know in my youth we
1:42:05
we sought we sought the genes responsible for schizophrenia um and and what I you know
1:42:14
anyway she she passed super young um uh
1:42:20
so we don't get to see her um her conclusions on this but um you know I I
1:42:27
think we ran into the much bigger question of of
1:42:32
organogenesis and and kind of epigenetic epigenetic
1:42:40
factors that that that Levan has has highlighted that are so
1:42:48
important for um how we get complex
1:42:53
tissue and organ structure yeah yeah and especially one that that
1:43:01
is molded like yeah and then I loved all the discussion that Jess had around
1:43:09
plasticity you know and the kind of the tension that you have in plasticity
1:43:14
where it's like you you want a learning system but you want you want a learning
1:43:20
system and you want a memory system right okay okay that's good um yeah thank you again Trevor for that
1:43:27
contribution this is an
1:43:32
interesting everything yeah yeah so I think we talked about this in a previous
1:43:37
meeting uh where you know people are putting the video game Doom on very
1:43:43
small devices so this is an article from IG uh the weirdest devices that can play
1:43:50
Doom including a Lego brick and an ATM so this is something that we talked about in previous meetings where you
1:43:57
know people take the video game Doom and they can load it onto things like you know a refrigerator or an ATM things
1:44:04
that don't I mean they have a lot of memory compared to the original version of Doom back in 1993 but they um you
1:44:13
know it's like people are amazed that you can play them on these small devices so-called small devices so there's this
1:44:21
whole like kind of cottage industry of people I don't call it a cottage
1:44:26
industry it's just kind of a hobby uh will it run on Doom so this is a longstanding challenge where modders and
1:44:34
programmers attempt to get the game to run on any device imaginable when you ask the question will it run Doom the
1:44:41
answer is more often than not yes and we talked about this in a previous meeting that you know it's it's
1:44:47
a a fairly small program it's Turing complete and so there's an interest in
1:44:53
running doom on things because if you can run it on relatively low powered
1:44:58
Hardware you can do a lot of interesting things with simulating World models or
1:45:04
simulating other types of things you know and and so that's an that's a nice compact program that you can run um so
1:45:12
below you'll find a list of some of the wackiest devices that can run Doom with Visual and gameplay quality varying
1:45:19
greatly depending on the gadget so people are running it on things like Lego bricks
1:45:26
refrigerators um an ATM uh TI 84 plus calculator powered by
1:45:33
potatoes which is kind of a side it's the the calculator that's
1:45:39
interesting um and then of course these are all kind of you know not I wouldn't say low power devices but lower power
1:45:46
devices so if you think about like if I want to put something on um microbot or
1:45:53
know some other type of thing you know we've talked about running large language models on things like the
1:45:58
Raspberry Pi we did some demos a long time ago on that uh and that so that's
1:46:04
interesting from that standpoint that you can run these you know potentially
1:46:10
high-powered uh computational uh systems on these small
1:46:16
relatively small devices um yeah so and you can play Doom on a rotary phone apparently
1:46:23
on an Nord track treadmill so this is like a you know the treadmills now of course they have displays that's not a
1:46:30
surprise yeah it's not a surprise so much um and then you know you have a
1:46:36
digital camera uh um this is an iPod Nano again these aren't like super low
1:46:45
powered devices um they're just kind of uh you know things that you can do and
1:46:51
people have done this with like doing things in Excel spreadsheets and all sorts of things like that where you can
1:46:58
really kind of feel like the original Matari games for example where people were highly constrained by memory so
1:47:05
they had to program games in like this small very small buffer of RAM and so
1:47:10
they had to kind of get creative and that's kind of the idea behind these challenges is that you can get a very
1:47:18
you know have a very relatively small buffer and create these worlds within them so apparently someone also put doom
1:47:26
on a pregnancy test and again the pregnancy test has like a small display but it has a decent amount of
1:47:32
computational power especially compared to the the hardware we had in
1:47:37
1993 so yeah and you can play Doom on a PC running within
1:47:43
Minecraft and uh other things and and VR for rats even so that's um kind of that
1:47:53
this idea of running doom on everything I'm I'm you know I'm upset
1:48:01
that again we've we've lost our slack history and my my it runs Doom examples have
1:48:10
disappeared down the rabbit hole Yeah but I every time I see one I posted at
1:48:20
random and you know uh and
1:48:27
yeah I don't know why it became I mean I I don't know if it's just it reflects
1:48:32
the fact that like for so many of us of of at least that particular generation
1:48:39
doom and Quake were you know seminal games
1:48:49
um as well as you know like like C CarMax um superpower as a programmer was
1:48:58
to to get so much from limited Hardware
1:49:03
yeah and like um um you know a lot of his um a lot of
1:49:12
his engineering was around um yeah Tri tricks you could play
1:49:19
to get more to get more realistic uh activity from from limited uh
1:49:26
constrained systems but yeah yeah that's that's always funny Jesse had a comment this is almost
1:49:34
like a variant of read only memories 2016 yeah and I say that quite Loosely
1:49:40
but that game's come up a few times in different ways and those don't know anything about it it's it's
1:49:51
a I don't know um it's a cute game about the future and
1:49:58
about um kind of cyber Punky themes but in the game you you sort of get at one
1:50:06
point semi spoiler but not really you kind of get a point of like oh what are you going to Res to resolve a certain
1:50:11
crisis and you basically you basically you basically get to like
1:50:18
heavily limit what a lot of AI entities
1:50:23
that are of robots and and artificial intelligent agents you get to limit them
1:50:28
or you get to sort of almost like put a whole bunch of like you can make like a
1:50:33
toaster and all these things that aren't really fully sentient if you will it's
1:50:39
are of like arbitrarily you you get to choose if those things arbitrarily sentient or not
1:50:45
um and it's a very interesting it's a very interesting thought thought um game
1:50:51
and and in a similar way there are references in the game to kind of working just like L like quake and and
1:50:57
and do the references in the game people kind of gr kind of I think sled towards
1:51:02
like probably Millennials like those references baked into
1:51:07
um into it that are interesting in a similar way um so it's it's just it's
1:51:14
just a fun fun way to think about it obviously you know a limited operation
1:51:22
classic video game isn't the same as um or is it but it isn't necessarily the
1:51:28
same as um I don't know fully expressive sort of
1:51:33
human level sentience just dropping that into a toaster or a refrigerator but you
1:51:39
know it made me think about that and um there's there's also another segue I
1:51:44
don't know I think you're finished with that but something I will say in slack Moore that I'm looking into is um
1:51:52
um around the gaming topic but uh especially for those with certain um
1:51:59
disabilities so stay tuned for some discussion about that and the slack um
1:52:04
and kind of a you know if people are saying this or you're watching this you think oh yeah Jess is looking for games
1:52:10
about people with um different kind of like accessibility people with various
1:52:16
disabilities um reach out to me about that place more about that yeah
1:52:23
well I think I I want to make two more points about this first of all I remember I think it was back in the
1:52:28
cybernetics meetings we did a series of meetings on the leev and bongard paper
1:52:36
oh yeah living maches I mention that I mentioned that this week and other discussions so in that discussion we
1:52:43
kind of I I think I made a point about like what they were getting at was like
1:52:49
you know we have machines now that aren't like we have the machine Medical of the brain and but then we also have
1:52:55
machines that are kind of like artificial brains and they were trying to work out a taxonomy cords between
1:53:03
like machines cognition and then cognitive machines and it was
1:53:08
interesting um It's A Hard paper to write but I I think I made the comment
1:53:13
or I made the comparison there with like a sentient toaster or you know it was
1:53:19
like something like that and you mentioned toasters and it's like taking like some behavioral thing or in this
1:53:27
case maybe like a world model and putting it on a machine the question is how much Hardware do you need what's the
1:53:34
size of Hardware do you need to build like something like a world model something like a a sentient program or
1:53:40
whatever and can you put what how small can you make that you know how do
1:53:46
you how do you get the you know because there's also the issue of an animal brains uh where you know we have all
1:53:53
sorts of Hardware we have seans connectone we have worm or other types
1:53:58
of anoid connectomes that are even smaller what are they doing and what what level of a
1:54:05
connectome do you need to have like really complex behaviors you know World models or
1:54:12
whatever so I think think that's interesting too um this this
1:54:17
relationship between processing constraint or architecture
1:54:23
exercise and these kinds of pro self-contained programs that can do things interesting
1:54:31
things the other thing I did want to point out in my notes and I had my notes here so I asked a question or actually
1:54:40
it says I have these questions that are kind of phrased so I talked about that article and one of the questions asked
1:54:47
will it run Doom so like will something run Doom you can take any piece of
1:54:52
technology or maybe even a connectome and say will it run doom and from the article we know the answer is that for
1:54:59
fridges typescript ATMs uh older calculators rotary phones
1:55:07
iPod Nanos Nordic Track treadmill within Minecraft and instance within Minecraft
1:55:13
and digital cameras the answer is yes we could assemble a list of maybe Nos and
1:55:19
we could also include like animal connectives in this as well and then the second question is uh well
1:55:26
the second question is why does Doom run on everything and then asking co-pilot
1:55:33
and asking our gaming the the um the Reddit group and then you know I
1:55:40
can I can find out more about why does Doom run and everything so co-pilot's answer is Doom's engine is a medium
1:55:47
detail mode that triples the speed of the game on slower machines making it a
1:55:52
hugely accessible game this combined with its internal shareware release has
1:55:58
made Doom run on everything fans have gone to Great Lengths to rig and Tinker with us unusual devices such as digital
1:56:06
cameras and microwaves to make Doom run on them the sheer imagination and Engineering skills on display when it
1:56:13
comes to getting doomed to run on improbable platforms is impressive and keeps the game all today the are gaming
1:56:19
answers and these are people giving feedback back uh you can run a lot of other games
1:56:26
in many unconventional ways it just happens to be a mean to make Doom run on everything maybe because of a quote or
1:56:33
something of course not all variants of Doom you might have seen are the same source code simply because of size
1:56:39
limitations or graphic limitations so again source code size is important but
1:56:45
you know you can run other types of games as well that that have the complexity of Doom uh someone else said it a it's
1:56:52
literally just for the memes really old so insanely light code so small can run
1:56:57
on anything plus one of the most famous games of all time don't need to make much more of a Phenom don't need much
1:57:04
more to make it a phenomenon it's light now but the joke is back in the day it was hard to run in some cases I had to
1:57:10
do various weird things in my computer to get Doom working my mom was so mad that I screwed up my computer and one of
1:57:17
her friends reconfigured a bunch of stuff so Doom would run it was a Packard Bell 4 6 SX 33 with 4 megabytes of
1:57:25
Ram uh this other answer it was unique in the way it was made when it was made
1:57:31
it was a game that visualized 3D gaming before computers were ready for 3D games the reason it for it to be ported to
1:57:38
anything is a mix of the source code being public for modding and the fact that the game is a 2d game looking and
1:57:44
playing a 3D game the real reason Doom wasn't still is an awesome game and doom
1:57:49
is the grandfather of all Shooters today um yeah so then there's this article
1:57:57
here not can it run Doom but can Doom run it this is this article here buck
1:58:03
and Doom run it and there's another blog post on that how large is a turing machine if needed to run Doom so this is
1:58:11
a question about uh how large of a turning machine is needed to run Doom so this is a question about like if you
1:58:19
flip and say flip the question and say what kind of what size turing machine do
1:58:25
we need to run Doom so this is a Reddit post on this and so you know there are a
1:58:31
lot of interesting computational questions here a lot of interesting things that you know we to a lot of the
1:58:38
questions we talking about today yeah it I think it's important to
1:58:45
emphasize that it's some source code that is also why yeah everybody you know
1:58:52
source code at and and it's just so much damn fun
1:58:58
yeah uh yeah then Jess said it's like a slightly techy modern will it blend or
1:59:03
will it float okay so to finish up I'm
1:59:14
gonna I want to talk about this it's kind of an esoteric topic we kind of I
1:59:20
don't really have an answer to this but it's about Clos Loop feedback and machine learning so I've gotten a couple
1:59:28
of Articles and screenshots of things so this is like something I was interested in for the stuff that we've been working
1:59:35
on with respect to cybernetics and Clos Loop uh
1:59:41
constructs uh this is an article um I think it's some documentation I got
1:59:48
from uh Jeff Holton this is uh from
1:59:55
2019 uh this is machine learning Clos Loop intelligence is a design for
2:00:01
machine learning so this is an article U and so this is basically talking about
2:00:08
taking Clos Loop intell or Clos Loop systems closed loop motifs and using
2:00:13
them to design to use as a design pattern in machine learning so there are
2:00:19
many great articles on using machine learning to build models deploy them these articles are similar to ones that
2:00:24
teach programming techniques they get valuable course skills in great detail but to go beyond building toy examples
2:00:32
you need another set of skills in traditional system these skills are called things like software engineering
2:00:37
software architecture or design patterns which are approaches to organizing large
2:00:42
software systems and the teams of people building them to achieve your desired
2:00:48
impact this article includes some of the things you'll need to think about and adding machine learning to your
2:00:53
traditional software engineering process including connecting machine learning to users what it means to close the loop
2:01:00
between users and machine learning picking the right objective knowing what part of your system to address with
2:01:06
machine learning and how to evolve this over time implementing with machine
2:01:12
learning the systems you'll need to build a long support a long lived machine learning based solution that you
2:01:18
wouldn't need to build for a traditional system op operating machine Learning Systems what to expect when running a
2:01:25
machine learning based system over time of course the first question is determining when you need to use machine
2:01:32
one key factor in the decision is how often you'll think you'll need to update an application before you have it right
2:01:39
if the number is small for example five or 10 times then machine learning is probably not right but if that number is
2:01:46
large say every hour for as long as a system exists then you might need machine learning so it talks
2:01:53
about these different aspects of implementing machine learning and
2:01:58
whether it's right for you or not but this idea of Clos Loop feedback is kind
2:02:04
of talking about closing the loop in different contexts of uh applying
2:02:09
machine Le so closing the loop is about creating a virtuous cycle between the
2:02:15
intelligence of a system and the usage of a system as the intelligence gets
2:02:20
better users get more benefit from the system and presumably use it more and as
2:02:25
more users use the system they generate more data to make the intelligence better so you give the example of a
2:02:32
search engine and then uh but a successful closed loop doesn't happen by accident
2:02:38
in order to make one work you need to design a ux that shapes the interactions between your users and the intelligence
2:02:45
so that they produce useful training data good interaction is the following
2:02:50
properties the components of the interaction are clear and easy to connect the outcome should be implicit
2:02:57
and direct have no or very few biases and does not contain feedback loops so this
2:03:03
is interesting in the context of this just this Clos loop system which of course is where there's a connection
2:03:09
between a user and a machine and there aren't feedback loops within that so the
2:03:15
close loop can suffer from feedback that compounds mistakes for example if the
2:03:20
model makes mistakes stake that suppresses a popular action users will stop selecting the action because it's
2:03:27
suppressed and the model May learn that it was right to suppress the action because people stopped using so having
2:03:35
feedback loops within that closed loop is not optimal it's interesting because we think maybe of more feedback being
2:03:41
better but you can so to address feedback loops and experience should provide alternate ways to get suppressed
2:03:48
actions and consider a bit of randomization model in there are uh some of the basics
2:03:55
connecting machine learning to users uh machine learning will almost always be effective when the ux and machine
2:04:02
learning are designed to support one another doing this well can enable all sorts of systems that would be
2:04:08
prohibitively in expensive to build any other way and then this is a section on
2:04:15
intelligence orchestration which is kind of leveraging both users and chain
2:04:22
intelligence intelligence orchestration is a bit like car racing a whole team of
2:04:27
people builds a car it's all the way is technology into it it's every aerodynamic Wing Bast gear ratio and
2:04:34
intake valve set perfectly they make an awesome machine that can do things no other machine can do and then someone
2:04:41
needs to get behind the wheel take it on the track and win and then intelligence orchestrators are those drivers they
2:04:48
take control of the intelligence system and does what it takes to make the make the machine achieve its
2:04:55
objectives and so this is kind of reminiscent of Ashby's intelligence
2:05:00
amplifier idea where kind of goes through how people use machine learning
2:05:06
systems and optimize them through you know different behaviors so the uh
2:05:13
ashp's intelligence uh intelligence amplification stressed the idea of you
2:05:19
know maybe the machine has more intelligence in the human maybe the human is more intelligence than machine
2:05:25
but it's a symbiotic relationship and so you know it's like leveraging the Best of Both Worlds and
2:05:32
we've seen this implemented in something like hybrid chess where humans had been
2:05:39
beaten by artificial intelligence at chess so what uh chess players didn't
2:05:45
response to that was leverage some of these artificial intelligence systems to
2:05:50
hone and refine their strategies of playing chess using machines for things
2:05:56
like you know look ahead strategies and then using H what humans do best which
2:06:02
is implementing strategies and using that as a symbiotic system and you know
2:06:08
minimizing the amount of negative reinforcement and positive you know uh
2:06:13
maximizing the amount of positive reinforcement so this is an interesting
2:06:18
article here um there's some other screenshot I took of a quora discussion
2:06:24
on this so this is where they asked people and what ways to close in
2:06:29
feedback systems REM resemble machine learning techniques so this is not how do you implement closing feedback in
2:06:35
machine learning but it's a question of how do they resemble standard machine
2:06:42
learning techniques so some interesting uh comments
2:06:48
here this size okay uh this one is in a control context ml is not feedback
2:06:55
unless you consider recursion feedback ml is more recursive adoption to a
2:07:00
static or slowly moving model sequential e squares are common filtering or kernel
2:07:05
filtering all recursive so it's introducing this concept of recursive feedback so it's like in in machine
2:07:12
learning you have recursion in programming and programs in general you have recursion and that's sort of the
2:07:19
level of closing the feedback that we may consider uh control includes
2:07:26
among other things like robust control adaptation is Solly varying parameters
2:07:31
while controlling an external process with its own significant Dynamics this control comes in the two flavors feed
2:07:38
forward and feed back to modify the behavior of some external process which would be outside the computer so it kind
2:07:45
of talks about uh traditional control theory where we use a plant model
2:07:52
to manage the current state and you have this feedback that occurs with
2:07:59
disturbances and then there objectives like estimation and control so you have
2:08:05
a plant that determines the current state there's feedback on the current
2:08:10
state uh on the current state of the world you have some disturbance or non-disturbance and then the plant has
2:08:17
to estimate or control the current state from that information
2:08:22
and so that's a very typical uh standard way of thinking about control theory and
2:08:27
applying that to a machine learning context and implementing that through recursion in a
2:08:34
program um this uh answer
2:08:39
here it's also interesting is there any relation between consal systems and
2:08:44
machine learning so this is a little bit different way of phrasing it kind of leading up from Control Systems because
2:08:50
we've established that Control Systems can be programmed into a machine learning Al uh you bet there is I'll start with
2:08:57
the basic building block of modern machine learning Paradigm the perceptron this was a hardware structure built in
2:09:03
the 50s by Rosen blat to mimic the real world neural network in our brains it
2:09:09
arose out of control theory literature when people were trying to identify High complex and nonlinear dynamical systems
2:09:16
neural networks artificial neural networks were first used in a supervised line scenario in control theory Warick
2:09:24
if I remember correctly was the first to find that neural networks were Universal approximators you've heard about the
2:09:30
classic sigmoid nonlinear activation function used in machine learning deep
2:09:36
learning as a nonlinear squasher it came out of the control theory literature
2:09:41
without classical control theory you could say that there would be no back propagation which is a Ral heart and
2:09:47
Hinton Innovation uh which had inspiration or or its basis in control theory there
2:09:53
would be no back propagation through time uh which was uh 1990 paper by waros
2:10:01
back propagation Through Time what it entails and this is now used in recurrent neural networks by moner
2:10:07
Machine learning practitioners there would probably be not be an uh this
2:10:12
lstm method which was invented by hul ryer in
2:10:17
1996 which is used to model tap delay lines and me memory based neural networks these have found massive use in
2:10:25
speech recognition language models and time series sequences the conflict between
2:10:30
exploration and exploitation and reinforcement learning is known control engineering as the conflict between
2:10:38
identification or estimation and control so this was by Whitten in
2:10:43
1976 so this goes back not only in machine learning but in reinforcement
2:10:49
learning as well and of course we talk about sort of these behaviors in human
2:10:55
machine systems where you have this tension between human performance and
2:11:01
machine optimization and so uh this actually the reinforcement learning example here also
2:11:09
Ties That to control uh control theory and other things so that it's an
2:11:15
interesting I guess Andrew Ang's thesis featured this um this uh reinforcement
2:11:22
learning control theory slash uh NE you know uh Clos Loop feedback relationship
2:11:29
as well if you read The Works of modern machine learning theorists you'll find control jargon camouflaged a new diction
2:11:37
to make their ideas sound new or sexy so this is where you know we're kind of in putting new wine in Old bottles I think
2:11:44
there is some sort of disingenuity among these researchers by not acknowledging that
2:11:49
these algorithms arose out of a domain main they are not often willing to give credit to so when they call it back
2:11:55
propop it's nothing more than oldfashioned calculus based differential chain rules uh so yeah there is a lot of stuff
2:12:02
that um you know is kind of repackaged but comes from that traditional sort of
2:12:09
control theory background and maybe further more further back from uh
2:12:16
cybernetics and so is there any relation between control systems and machine learning this is the same question as
2:12:23
this person says kind of machine learning algorithms especially neural networks are used to approximate
2:12:29
functions that cannot be hardcoded uh the approximated functions map one set to another set H from
2:12:37
example the mapping function between cat images to the cat category is you know
2:12:42
the sort of uh approxim we want to approximate that function control theory
2:12:48
does research for similar types of functions meaning the mapping from one set to another set
2:12:54
but the sets are different between the machine learning and control theory examples in control theory the input set
2:13:01
is a set of signals or the series's transform for transform can be found and
2:13:07
the output is also a set of signals or just a signal signal so you know they're
2:13:12
talking about like if we had a set of images versus a set of signals major
2:13:18
differences between the control theory machine learning examples is that in control theory most of these functions
2:13:24
can be found analytically meaning that there is a direct way to find the desired function you solve a set of
2:13:30
equations you reach and you reach the function however in machine learning there isn't any analytical solution that
2:13:37
we know of you have to approximate it there are a few maybe but you can't use
2:13:42
them for most problems this is why machine learning problems are approached as an optimization problem where you
2:13:49
have to approximate the answer and you have to really spend time finding an approximated function you
2:13:56
have a lot of iterative Discovery you know going trying to find m a local and and Global
2:14:04
maximum on a landscape uh which consumes time and the function cannot be proven to resistant proven to be resistant to
2:14:12
adversarial inputs and control theory this means the closed control system
2:14:17
cannot be proven to be stable so the the methods that we use in machine learning
2:14:23
uh especially like gradiant descent those things are not you know those
2:14:28
things are different than what we do in control theory so it's an interesting relationship between the two and of
2:14:34
course in control theory that's a more like real world focused instance of Clos
2:14:40
Lo control so now of course these two areas intersect uh but this answer basically
2:14:48
argues that analytical Solutions are kind of key to understanding this
2:14:54
relationship so there are two Pap other additional papers I want to talk about here this first one is machine learning
2:15:01
deep learning inclusive devices this is in the domain of anesthesia delivery and
2:15:07
you know so this is an applied method for looking at closed loop systems
2:15:13
applying machine learning putting it in the loop and so um this has been going
2:15:19
on in anesthesiology since the 1950s and so this is where they're trying to to automate the delivery of
2:15:26
volatile an anesthesia based on um different types of data like
2:15:32
EEG and then of course you know people have been developing Clos Loop methods in this area for a while trying to find
2:15:39
ways to uh develop methods for delivering neuromuscular
2:15:45
blockades uh and other types of like you know physiology of course is the
2:15:51
dependent on realtime sort of delivery of anesthetics that work uh in that way
2:15:59
the classic open loop control system in anesthesiology Target controlled infusion devices which a hypothetical
2:16:06
plasma or effect site concentration is targeted based on estimations from a
2:16:12
population model of drug distribution and effect uh was kind of developed in the 1990s
2:16:20
and is now a mature technology so they yeah they kind of go through some of the innov Clos Loop
2:16:27
Innovations in anesthesiology and how AI can improve those and you know they kind
2:16:34
of get into a lot of about clu Loop systems and their definition
2:16:41
here uh where they Define clu Loop systems is acting to maintain a given
2:16:47
variable at a desired set point by three key elements a sensor or controller and
2:16:52
action so of course we you know we think about in cybernetics we think about this
2:16:58
more broadly and we don't make the distinction between like an automated system or an artificial system and if
2:17:06
you're interacting to something like a physiological system how those two things are related because in physiology
2:17:12
of course we have the concept of homeostasis and we have these
2:17:18
physiological systems which are in ostasis but we also have then this
2:17:23
closed loop between an artificial system and a physiological system which also
2:17:28
has to maintain this sort of uh homeostasis and so we have these these
2:17:37
Concepts sensor controller actuator and we have to apply it in different ways
2:17:43
that fit the system we're looking so that's this paper on anesthesia I think it's an interesting example of like you
2:17:50
know specific domain where you have sort of Regulation built on top of
2:17:57
Regulation um this last paper is uh from
2:18:02
uh cell reports physical science this is merging machine learning and bioelectronics for Clos Loop control of
2:18:09
biological systems in homeostasis so this is what I was talking about where you know people are thinking about these
2:18:16
bio Electronics or biomechatronic systems and build you know artificial
2:18:22
intelligence is inside of them but then build scaffolding them on top of biologic existing biological
2:18:29
systems which have this sort of also this physiological regulation and you know you have to sort
2:18:36
of it adds to the complexity of this closed loop you have kind of closed loops on top of closed loops and so this
2:18:44
kind of talks about how physiological processes rely on the state of
2:18:49
equilibrium called stasis which is achieved through this biological control Loop involving
2:18:55
sensors and actuators we have sensors and actuators in our physiological systems you know there it's sort of this
2:19:02
metaphor for different types of sensory organs and other types of you know
2:19:08
things that we use to act upon the world or act upon our internal state but
2:19:15
they're you know they kind of we can think about it in this General model however disease and aging disrupt these
2:19:21
control loops leading to imperor slower homeostatic mechanisms bioelectronic
2:19:27
devices offer the opportunity to interface artificial technology with these biological systems allowing people
2:19:33
who have diseases or have aging issues to retain that that function so if we
2:19:39
think about you know uh neuroprosthetics that's one example where you could
2:19:44
recover function homeostatic function that's seamless or you know attempts to
2:19:50
be seam L of the physiology so in this context we propose that machine learning
2:19:55
can significantly enhance the capabilities of Bio Electronics by facilitating real-time processing of
2:20:01
sensor and actuator data by utilizing machine learning of and bio Electronics
2:20:07
we can maintain and regulate biological systems responses more effectively compared to traditional approaches so
2:20:14
this advancement holds promising implications for bioelectric medicine and precision medicine
2:20:20
particularly in re uh repairing impaired homeostatic mechanisms so this is a
2:20:27
vision paper but it gets that what I was talking about with these feedback loops on top of feedback loops and of course
2:20:34
we have this whole issue of interacting with a machine Learning System so yeah uh V he uh had a comment
2:20:43
here as we're wrapping up this meeting I just wanted to say that even though I may not speak or contribute much I've
2:20:48
been learning a lot so thank you thank you for that um also I've been focusing
2:20:54
on project idea 5 and working on implementing the chat space du to my University exams that's fine that's fine
2:21:00
we're we're pretty far out from the deadline for gtoo so I'd appreciate any guidance on how to approach the preck
2:21:07
phase yeah so the preg gck phase you know we're trying out things we're not
2:21:13
quite at a proposal stage but please send things if you want feedback on them you can post them in the G channel in
2:21:21
the slack or communicate by a private dm with
2:21:26
myself um and yeah so that's okay um yeah thank you V for glad that you're
2:21:34
getting something out of the meetings uh any comments on the papers that I just
2:21:41
reviewed yeah interesting um so just going back to the um
2:21:51
the closed loop um kind of more General discussion
2:21:56
um and the Machine learning versus control
2:22:03
theory I think maybe uh discussion
2:22:09
um certainly one thing you know um the center that it's like Nathan CTS
2:22:18
and Steve I'm blanking on his name right now
2:22:26
um uh he does these um he does these videos
2:22:34
I think it's like Dynamics ai.org is that name
2:22:41
um anyway two things so you know like you said like or you know as the the
2:22:50
author said control theories usually got these analytic um formulations and so th this
2:22:59
is the this is the goal in something like um symbolic
2:23:05
regression or you know like and and so P
2:23:11
Sr and um and the the similar Julia
2:23:20
projects um lot of lot of cool math or a lot of
2:23:26
cool scl is focused on exactly that right like like I get data I I crunch it
2:23:36
and I get out a an analytic
2:23:41
equation right and and this is this has come up just super so so now then to to
2:23:51
you know the anesthesia examples like that's that's particularly cool and of
2:23:56
course you know super super relevant for me um one
2:24:02
it's interesting that there was in 1950s EEG um sensor
2:24:10
based control Clos Loop that's interesting you know as I've pointed out
2:24:17
to my anesthesiology friends um why don't you use the EG yeah that is that
2:24:24
is not something that is typically modern um which is which is fine um or you know
2:24:32
like like anesthesia is very successful and and you know relatively
2:24:41
low risk um but uh um
2:24:50
yeah it's it's uh the thing that came up that um is
2:24:59
actually an organoid paper from the Johns Hopkins group um like Hartung
2:25:05
and and Lena smirnova um together with Johns Hopkins
2:25:11
Applied Physics lab people and they are
2:25:17
using zebra okay so in my head I have to say zebra and then replace the Z with a
2:25:26
c okay that's how I remember so you could go to
2:25:31
zebra uh uhai for the the approach that they're
2:25:38
adapting and it's it's it's
2:25:44
um it's somewhat related together with this idea of embeddings that like you
2:25:50
can find a lower dimensional space um in
2:25:55
which um in which this problem is
2:26:03
easier and and regularized things like that right and
2:26:10
um uh uh so and I I bring it up in relation to
2:26:15
Dynamics AI because I looked at this paper that is just a pre print and sorry
2:26:22
I haven't been updating it on brain organoids because now there's just so
2:26:27
many so many slacks now and now we've added like like
2:26:34
found some people on a Discord channel that are Discord server that are interested
2:26:40
um shred shred from Nathan ctt's
2:26:48
uh um I want say Steve I keep keep it in my head I keep saying Steve Balmer and
2:26:54
it's just like like like he's in Washington he's you dub right it's it's um yeah anyway
2:27:04
but Kurt's uh has shreds which I forget what the acronym is but it it's it's very much a
2:27:15
um it's very similar and I'm I'm curious now um to try and talk to Hopkins about
2:27:23
you know would they give us you know are these data sets available so that we can
2:27:29
try try shred because I I was really um anyway but it it's it's a spatial
2:27:36
temporal uh um Spa of Temple representation that
2:27:43
that again gets ideally at the end you're going to get a kind of a Dynamics equation yeah
2:27:53
and and what they're using it for the organoids that reminds me of anesthesia is that they're looking for they're
2:28:01
looking as as organoids age when do you see the Dynamics
2:28:07
change yeah right because you know you do or like like the the
2:28:13
um the the experience people have is that at a certain age they mature
2:28:20
and they they start to have this these endogenous oscillations and and other
2:28:26
kind of new behavior um and and of course um this is
2:28:34
also super interesting or you know these these approaches are things that I would
2:28:40
also just like to try on you know high density EG recordings and things like
2:28:45
that you know so what what would that give us from from noninvasive elect
2:28:52
is which um has a really interesting history for you know not only resting
2:29:00
versus task behaviors but also drug action and anesthesia and and coma and
2:29:09
sleep all change the overall dynamics of the spatial temporal
2:29:16
electrophysiology and like how to how to understand that but great and then it relates to control
2:29:24
in terms of neurom modulation people want to say you know like if I TMS this
2:29:31
person's particular area I I can now instill a new Dynamics in there
2:29:38
yeah electrophysiology right that's fine that's great stuff um so yeah thanks for
2:29:45
the meeting today I think wrap it up um and again if you have any questions the
2:29:52
slack is open and see you next weekk you take care take care
