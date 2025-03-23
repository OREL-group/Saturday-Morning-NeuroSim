## Meeting Recording

[YouTube link](https://youtu.be/XL_Y_Uravlw?si=ile0ZLKG1fUnZmjf)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114208823992285654)

## NOTES
Issue #xx: follow-up on Github issues and related work from last year. 

* Start-up in San Francisco: Neuro floor, Bio floor. Morgan is arguing for a Neurobio perspectyive.

* tissue-facing development. Paul Middlebrooks -- The Transmitter.

* "The Complex World" book overview. Krakauer --> focus on Lotka, 1952 paper.


Multimodal LLMs (MLLMs):

* distill research-level reasonings.

* Large Reasoning Models (LRMs): chain of thought approaches. Large Concept Models (LCMs -- akin to sentances being tokens). 
Large Behavior Models (LBMs -- very generalist policy for lots of embodiments).

* RLHF -- Reinforcement Leanring for the post-training step.

* Steve Piantodosi -- Language is for communication, not for thought. Utility of syllogism. Describing without engaging.


Language is built from need to describe knowledge. If you want to think, you need to shut up (keep embodiment busy, go for a walk 
to think).

* Continual AI --> not looking for counterfactual information.

* language is built from need to describe knowledge.

* if you want to think, you need to shut up (keep embodiment busy, go for a walk to think).


Gael Varoquaux: ask an LLM to play tic-tac-toe.

* Huggingface connections between models --> visualized. How do we even get at how much models are reasoning?

* MetArc --> online community, developed machine models for meta-imaging.

* Mind's Eye model --> natural scenes, movies, open-science collective.


Viktor Jirsa -- Virtual Brain Project. Hermann Haken --> synergistics.

* causality --> temporal aggregation, macro/micro constraints.

* two competing software packages: different approaches to multiscale modeling. 

* Hemodynamics (seconds), Electrophys (milliseconds).

* brain dynamics at different temporal scales.


Digital Twin Epilepsy (virtual brain projects).

* Hierarchical Bayesian Models vs. Physics versions. Bottom-up models.

* NeuroAI for Neuroscience. Settling on mechanisms.


FOOF -- full-spectrum EEG modeling (phenomenology of power spectrum).

* move to a generative model of the power spectrum.

* no spatial model, mixture of distributions: https://en.wikipedia.org/wiki/Mixture_distribution

* Gamma, Power Law behaviors. Leaves out a lot of information about cell sheet. 

* specifications of the spatial model. Trwaveling Wave, Seizures, how to characterize?

* bottom-up --> explain power spectrum (tradeoffs of physics modeling).

## TRANSCRIPT   
0:01     
hello good morning     
0:06     
morning morning before we start can I ask a few     
0:13     
doubts     
0:19     
okay I'm a yeah yes okay so uh for this is g to 202 back     
0:30     
project um I wanted to ask what exactly are we aiming like um like last year we     
0:37     
have already implemented some part of it and this year we are continuing the project so do we have to enhance last     
0:44     
year's p and make the conversation space and work on the issues that are     
0:49     
currently open on the repository or only the conversation space on the     
0:57     
issues CU I was documenting my proposal and having my research and like some     
1:03     
kind of experimentation that I was going on with but I just want to make sure I'm not going on the wrong     
1:10     
part um well I don't know uh we don't I don't think we have that many open issues in the     
1:16     
repository so like if you go to last year's what is     
1:21     
that there are five issues I'll just read them after you uh issue number six     
1:27     
years to add a conversation space which is to simulat St or like IC or something     
1:34     
um then we have issue number 61 which is adding engagement metric based on the     
1:40     
conation we have integrate within conation space and get     
1:45     
discussion um we also have you like we have to create a issue create agent to     
1:52     
allow Dynamic creation of new issues during simulation and we have uh collaboration     
2:00     
for multiple agents on a single issue all right well that's yeah those     
2:05     
are actually followup issues from last year's projects so you don't have to     
2:11     
address those you you could if you want to you can pick a specific set of issues     
2:17     
and address them in your application but you don't have to um it I think it would be use more     
2:23     
useful to kind of follow up on what was done last year it doesn't have to be on specific issues     
2:30     
but you we last year we did the large language model uh agent based model     
2:36     
hybrid uh model or project and then some work with     
2:41     
multi-agent reinforcement learning so one of those two or combining those or     
2:48     
whatever is um probably the way to go we have a repository I mean you know what     
2:54     
the issues are so you know where the repository is and that repository then     
3:00     
has um the work from last year so just try to I think probably the best way to     
3:06     
do that would to do your approach your um proposal is     
3:11     
to uh just follow up from last year's work and figure out a way forward and     
3:17     
the the issues in the issue um in in the issue list are merely followup things     
3:23     
from last year I usually make people do that because there are things that they didn't complete there always think you     
3:29     
don't complete and so to make those clear what those are and those might serve as technical challenges they might     
3:36     
just be things that are not necessarily relevant to what you want to do     
3:44     
so and any guidelines on what I should specifically include in     
3:50     
my um so I mean you know you need a timeline so going through from uh I     
3:57     
guess it's space it out to like a 12 week program or what however long the     
4:02     
normal period is um and then figure out for each week what your what unit of     
4:08     
work you're going to do or how much work you're going to do for each week and then figure out like you know if if I     
4:15     
run into problems how do I get around those problems do I do some other task     
4:21     
while I'm waiting for something to happen or what you know the there're so the the     
4:27     
the schedule or the timeline is very important and then having some description of what you're going to do     
4:34     
um is important as well okay and like regarding the project     
4:41     
specifically [Music] any uh what do you mean like well yeah     
4:47     
how you how what you want to do fits into the project I think it's a good way     
4:56     
to thank you you're welcome all right so it looks like we have Jesse     
5:02     
and Morgan and BT and shyam so     
5:10     
welcome um so anything anyone wanted to mention     
5:16     
before we get started it looks like Jesse's here and he had mentioned that he's just going to listen in for now     
5:23     
um how about Morgan     
5:31     
um super super busy week I'm just trying to think what um what news potentially came from     
5:40     
that um we're going to be moving did I say     
5:46     
last week that we're gonna be moving the lab to a new space so this this is     
5:52     
exciting um in terms of     
5:57     
having having dedic dedicated space um in terms of uh full full control over     
6:06     
this um like 4500 square     
6:12     
feet um and yeah I think I think in the first     
6:19     
couple months there'll be a good number of people coming through hopefully     
6:25     
interested in um funding the buildout that we would need for the you know since one to     
6:34     
reach the the BSL 2 um kind of facilities level where we     
6:41     
can do meleon cell culture work but but organoid work really     
6:48     
requires a whole new set of equipment that's all basically built inside an     
6:55     
incubator you know very very very specialized equipment it's built inside you know that that is all housed in     
7:03     
incubators so you can just keep everything going and maintained and fed     
7:10     
um all all in in you know temperature controlled and     
7:15     
um again to to also reduce you having to move things around so hopefully less     
7:23     
more more hands off so that's that's um     
7:30     
yeah I think that's our that's our big news these um these guys bought a a 16     
7:37     
Story Tower downtown San Francisco um and     
7:43     
uh so we get we get a we got a bof floor and a and a neuro floor oh wow but I've     
7:51     
been I've been pushing for the the neuro the neuro     
7:57     
floor to be you know neurobi right and and     
8:02     
and and the neuro Flo to be you know when     
8:09     
they when they talk about neurot tech I think they they don't understand that     
8:14     
most of the valuation in in neur attack is going to brain implant companies right right so     
8:23     
that that's one reason why it's just like like with with organoid culture you     
8:28     
can actually have have a kind of tissue facing     
8:34     
um technological development right and you can do all of this without     
8:41     
animals right and um which given     
8:47     
our position in the city is probably you know I mean it's doable but it it's you     
8:55     
know an animal facility is like a whole yeah larger you know it's infrastructure     
9:02     
it's it's you know people who are just working in the animal     
9:08     
colonies and and I kind of like the I kind of like the the funing story around     
9:14     
just um let's let's replace animal testing with     
9:20     
with organoid culture you know and um and look at Medtech uh in terms of kind     
9:28     
of broad um broader Technologies but it so it's     
9:35     
it's exciting definitely going to be a a a real work in progress for the first     
9:40     
couple months um it's a former wework building so the inside's really kind of     
9:46     
built out nicely okay um um you know but     
9:51     
uh yeah anyway there was definitely good um meetings well oh sorry then the     
10:01     
brain inspired so uh Paul Middlebrooks     
10:08     
yes the um yeah brain inspired host uh who's     
10:15     
now affiliated with the transmitter I believe the the Simons     
10:22     
Simons Foundation funded um neurom magazine neuro blog     
10:31     
yeah what do we call what is Quant yeah um there's no physical     
10:38     
magazine um they start he he uh started a uh and     
10:47     
I've got the here it started the     
10:54     
um complexity oh yeah the complex world     
11:00     
uh I forget what he called it complexity group right um so they're doing a a     
11:09     
regular Journal Club around the     
11:15     
craar um complexity papers yeah and they started with the the     
11:22     
lotka um 52 paper um okay I I     
11:31     
anyway I I I getting getting proposals in this week I I was not able to read     
11:37     
the paper but I jumped in on the I listened in and it was a you know was a     
11:44     
nice conversation a lot of people     
11:49     
um cool that you know people like Kevin Mitchell were there     
11:57     
um yeah discussing discussing the paper and um yeah looks like a really really     
12:04     
interesting group so they started their own it's it's got a it's new another     
12:11     
Discord can we can we please stop starting these um and     
12:19     
uh they'll be deciding you know how how often they meet soon you know um like I     
12:27     
think he was kind of pitching every two weeks um but we'll see see what people say but you know the four volume they     
12:35     
got plenty of papers to pick from oh yeah yeah yeah yeah um I think that was H any     
12:45     
I I'll try and think of other things as we as we go okay sounds great thank you     
12:52     
H shyan would like to speak so uh unmute and what would you like to talk about     
13:00     
uh it's it's related to uh the G project only uh I've texted uh both of the     
13:06     
mentors uh you Bradley and Jesse too uh uh told that uh started working on my     
13:11     
proposal and I want a review over it I sent it yesterday uh and I was wondering     
13:17     
if you've had time to go over it and maybe you could uh give me a couple pointers on what you'd like me to     
13:22     
elaborate more on or where you would like me to put some more effort on and uh if You' also like me to send over uh     
13:30     
the G so channel in the main slack I could do that too uh I did see the message so I'll look into it this     
13:36     
weekend and see okay okay sounds yeah so uh do I     
13:41     
send it over the G Channel too in case like Morgan no um I mean if if you want     
13:48     
to message him directly you can I don't know if he wants to uh oh okay okay do that but yeah I mean it's it's uh I have     
13:54     
it yeah so you don't need to put it in the gck CH okay yeah     
14:00     
okay sounds good sounds good yeah all right yeah so that's great thank you     
14:06     
sh okay so um let's see we'll start with um so     
14:12     
we'll start off with uh talking about some new YouTube content on our YouTube     
14:18     
channel so we have our orth Alon research and education liveb YouTube     
14:23     
channel this is a screenshot from my mobile YouTube app app and we have two     
14:29     
videos here um developmental neuros simulation and interference diffusion pattern     
14:37     
formation which is about a 30 minute talk that I kind of     
14:42     
developed uh from another talk that I put in the uh dorm channel so in the D.A     
14:49     
worm Channel there's a talk on interactive morphogenesis and so this is kind of a     
14:54     
followup to that but focusing more on some of the agent based stuff that we're doing in developmental neuros simulation     
15:03     
so it's one of these talks where kind of develop an idea uh I've been doing these for I did     
15:11     
one of these like uh about a year and 3 months ago where I talk you know it was     
15:17     
kind of the outcome of a lot of our stuff in cognition Futures and     
15:22     
cybernetics group so this is another one of those talks it's just kind of wide     
15:28     
ranging and covers a lot of ground but you know it's going to be kind of the basis for future work so there's that     
15:36     
video um and then there's this other video which is going to be the presentation at the embodied     
15:42     
intelligence Workshop in two weeks so uh I'll be presenting at the embodied     
15:49     
intelligence workshop on April 2nd and that will be on this uh this     
15:55     
talk phog genetic models of embodied agents so this is about a 10-minute talk     
16:01     
where I go through sort of the philogenetic view of cognition and uh I give a a phog genetic     
16:09     
analysis of brenberg vehicles and I talk a lot about our developmental neuros simulation     
16:17     
Paradigm and some aspects of embodiment having to do with uh sort of the uh I     
16:25     
guess I'm calling it The ecoo approach to embodiment and embodied agents so     
16:32     
this is a nice talk uh go through that if you're interested um you know lot of     
16:38     
interesting things there lot of developing work um so yeah so embodied intelligence     
16:46     
conference is coming up in two weeks and um you know then we have other     
16:52     
things going on the summer um yeah so that's um that update on that     
16:59     
also we had a diva worm meeting this week where I talked about uh sential     
17:05     
cells in the seaan lineage tree so I give a presentation on that basically     
17:10     
the idea is that you know if you have like if you you're familiar with muscle cells you know that muscle cells are     
17:17     
these large cells that are multinucleated and those multinucleated cells come from the CTI or this process     
17:24     
of forming a centium which is where you have all these nuclei a single cell body     
17:31     
and you see this in uh gropo development but you also see it in     
17:36     
cagans with celan's muscle but also in different structur such as the ferx and     
17:43     
the germline so you see this again and again in seans and then the question is     
17:49     
where does that fit into the lineage tree so I presented a couple papers that talk about the     
17:55     
biophysics of uh sential cells sort of the process of forming sential     
18:02     
cells and then this aspect of fitting it into the lineage tree so I don't know     
18:08     
where that's going in that's something that someone in the group was interested in and we kind of talked I I prepared     
18:14     
some materials for it so the meeting number 11 is on the dorm YouTube channel     
18:21     
it's a different YouTube channel but we have uh their weekly meetings and that's     
18:27     
weekly meeting 11 for 2025 okay so the next thing I'd like to     
18:33     
talk about is following up on our data science ml slack channel so if you're in     
18:40     
our slack you know that you know we have our slack channels we have different topical channels and the thing that's     
18:46     
been the most active in the last week or so has been the data science ml Channel where we've been following up from some     
18:52     
of the things uh our discussions on large language models and reasoning and so that's this uh     
18:59     
collection of things here so this is the first thing I think     
19:05     
this was posted in the channel um this is an archive paper um on it's called     
19:11     
learning to collaborate by grouping a consensus oriented strategy for multi-agent reinforcement learning so     
19:18     
this is all multi-agent reinforcement learning um so the abstract reads multi-agent systems require effective     
19:26     
coordination between groups and individuals to achieve common goals so this is relevant to the things that     
19:32     
we're going going to be doing in gso perhaps where we've been working on this multi-agent reinforcement learning model     
19:39     
of open- source communities so um you know multi-agent systems are usually     
19:45     
something like a uh system where you have a number of Agents maybe working collectively on     
19:52     
problems maybe competing maybe just kind of existing in the same uh so social group or you know in     
20:00     
maybe in a tissue in in a biological simulation so these multi-agent systems can be quite diverse and have a lot of     
20:08     
um you know aspects to them that are you know basically complexity so they require effective     
20:16     
coordination you have individuals coordinating on their own you have groups coordinating and they have to     
20:21     
achieve common goals however current multi-agent reinforcement learning or moral methods     
20:29     
primarily focus on improving individual policies and do not adequately address group level policies so this is where     
20:36     
you have these multi-agent reinforcement learning uh algorithms and the idea is     
20:42     
that you're focusing on cooperation uh from the individual level     
20:47     
so individual agents all have to sort of implement the same policy to coordinate     
20:53     
their activities uh but you know there is this aspect of group level policy that we can     
20:59     
exploit um and that's maybe more to the point in terms of fostering collab     
21:07     
effective collaborations so group level policies you know would be like how does you know     
21:14     
what are the sort of the Hallmarks of the group you know thinking about individuals in the group as opposed to     
21:20     
individuals pursuing common goals and then forming a group sort of uh ad hoc     
21:27     
so this is this focus on individual policies leads to weak cooperation as     
21:32     
you might expect because individuals always have different objectives and they can fall in and out of the group     
21:39     
and you know you can think of any strong group versus a group that's sort of ad hoc um and AD Haw gr just kind of has     
21:47     
members that come and go and there isn't a lot of you know strong cooperation there because there's no incentive     
21:53     
whereas a a very strong strongly you know reinforced group it's um you know     
22:00     
it reinforces its boundaries and people have a reason to stay in the group long term so you get     
22:07     
stronger cooperation there so there are different ways we can play with group level policies to get the sort of     
22:14     
stronger cooperation to address this issue we propose a novel consensus oriented     
22:21     
strategy or cosos that emphasizes group and individual policies simultaneously     
22:27     
so again we don't want want to throw out the individual policies but we also don't want to ignore the group policies     
22:34     
and so a good way to do this is to have sort of a emphasis on both     
22:39     
simultaneously so this is where we're getting this consensus oriented strategy um specifically cosos     
22:47     
compromises two main components or C cosos comp uh comprises     
22:53     
two main components a which is the vector quantitized group consensus module     
22:59     
which extracts discret lat and embeddings that represent the stable and discriminative group     
23:04     
consensus so you have this group consensus where you have a bunch of     
23:11     
agents that are kind of finding this uh set of     
23:16     
solutions and you know kind of figuring out what that is and then B the group     
23:21     
consensus oriented strategy which integrates the group policy using a hypernet and the individual policies     
23:29     
using the group consensus so you have this consensus oriented strategy which     
23:35     
basically takes that group policy and integrates it with individual policies     
23:40     
and then figures out with the group consensus so it's different ways of figuring out the group consensus and then both implementing     
23:47     
both of those strategies uh promotes coordination in both the group and individual levels so     
23:55     
there are a lot of kind of theories of you know group uh like you know behavior     
24:02     
in groups so if you look at the like we were talking about swarm intelligence a couple weeks ago you know you can think     
24:09     
about swarms as being the products of individual uh organisms or individual     
24:15     
agents that kind of you know cooperate in a very passive sense in other words     
24:22     
they all kind of pursue the same goals and they form these structures that are sort of weekly emerging     
24:29     
and but you know nevertheless there's still these groups that are stable but     
24:36     
you can also have these you know you can also think of swm intelligence as a group level phenomenon so if it's a     
24:43     
group level phenomenon the agents will do things uh to further the survival of     
24:50     
the Swarm so they're actually making their decisions directly in terms of how     
24:56     
to maintain and reinfor Force the Swarm so this is kind of another way to     
25:02     
think about this through empirical experiments on Cooperative navigation tasks with both     
25:10     
discrete and continuous spaces as well as Google research football we     
25:15     
demonstrate that cosos outperforms state-of-the-art moral algorithms and achieves better collaboration thus     
25:22     
providing a promising solution for achieving effective coordination in multi-agent systems     
25:29     
so they talk about where you can uh sort of uh use multi-agent systems as a means     
25:37     
to improve performance in applications such as multiplayer games traffic signal     
25:43     
control and sensor networks um and you can model these as multi-agent systems or a team of Agents     
25:49     
perform a shared task to reach a common goal so people have looked at multi-agent reinforcement learning as a     
25:56     
solution to this of course well use swarm intelligence as a solution to this     
26:01     
but you know neither of those necessarily address both the individual imperatives and the group     
26:09     
imperatives so you know there have been other methods that have been proposed for this uh uh approaches such as Roma     
26:18     
and road which are acronyms focus on task decomposition specialize the agent     
26:24     
associated with the role to resolve a certain subtask um ldsa learns Dynamic subtask     
26:30     
assignments which can dynamically group agents of similar abilities into the same     
26:36     
subtask so the problem there is that you have this sort of uh you have to kind of     
26:43     
rely on your understanding of the group or rather the agent's understanding of     
26:48     
the group to sort of understand or to to achieve this level of performance so you     
26:56     
have to understand the group as the this sort of structure with different you     
27:02     
know it has to be very tightly coordinated especially in terms of what's to be done to maintain it so you     
27:08     
have to have these tasks and subtasks and you really have to decompose different aspects of group     
27:15     
behavior and so that's sometimes that's not easy to to sort of     
27:20     
unpack uh you know especially if you have a newly formed group or you have a group that's not very well defined     
27:28     
having that kind of top- down approach isn't necessarily uh e easy or or viable in     
27:34     
some cases so uh on the one hand uh group     
27:40     
representations are not well constrained and vulnerable to Dynamic changes from the environment or policy training so     
27:47     
when the group changes its Dynamics you can't use that kind of policy or you can't really rely on those sorts of     
27:54     
group representations anymore on the other hand the above methods rarely consider extracting a     
28:00     
higher level policy guidance from the natural properties of groups which are these     
28:05     
subtasks so good teamwork often requires a good divisional labor forward looking     
28:10     
guidance to specialize in a certain subtask and rational individual decision making so if we think about like we're     
28:18     
talking about um ant colonies when we're talking about swarm     
28:23     
intelligence and in ant colonies we have a very strong divis division of labor     
28:29     
you have these Collective structures and there's a strong division of labor say like in ant colonies where they do     
28:36     
certain tasks and sometimes those are to the exclusion of doing any other tasks     
28:41     
so in a case like that it may be very easy to decompose yourp Behavior but if     
28:49     
you think about a bird flock it may not be so easy cuz the birds in in a bird flock are just using that flock as sort     
28:56     
of an expedient structure to to you know travel to achieve coordination and so     
29:04     
forth so if you think about this in terms of multi-agent reinforcement learning that group representation is     
29:11     
important and it if you go from different you know if you if you take into account different types of     
29:18     
groups your application of multi-agent reinforcement learning will be variable in terms of its efficacy so it may work     
29:26     
very well and something like an ant colony but not so well on a bird     
29:32     
flock so they propose their approach uh they use uh a couple of uh     
29:39     
pieces of sort of technical uh work here first we use the vector quantitized     
29:46     
variational autoencoder or vqv to extract the group consensus embedding which captures assured     
29:53     
objective that agents in the same group should pursue and is Essen for promoting     
29:59     
effective teamwork so they use this Auto encoder to build this representation in     
30:05     
Laden space then we perform the policy learning from two levels so they have     
30:11     
these two levels at the higher level we propose using a hyper Network architecture to transform group     
30:17     
consensus embeddings into a group level decision set of decisions from Global     
30:23     
long-term perspective so you think about what what the group The the imperatives of the group are not just as an     
30:30     
expedient structure but as this sort of longer term structure but also thinking     
30:35     
about how those things differ from the individual so that's at the higher level     
30:41     
and then at the lower level we utilize the group consensus embedding as the context prompt to augment the     
30:47     
observation to make the individual and refined policies so they use this group consensus to inform the individual     
30:54     
policies that are pursued for individual Aid agents the combination of these two     
31:01     
policies guarantees the foresight and precision of the decision making progress and so this is just kind of     
31:07     
talking about um their methodology some of the things they have representation     
31:12     
learning defined um so the representations for observations actions or underlying     
31:20     
messages are widely studied in moral so this is in multi-agent reinforcement learning some works and they gives an     
31:27     
example use B simulation metrics to extract the weight and embeddings from     
31:33     
observations these other two references attempt to learn action representations     
31:38     
to assist multi-agent policy learning these uh references to these two     
31:44     
references proposed represent uh underlying messages to conduct effective communication in in     
31:51     
Mas there are also some works that use the variational auto encoder to encode     
31:57     
the traj trory message to make representation more knowledgeable so they're using this vqv     
32:05     
approach this variational Auto encoder uh to maintain a quantized     
32:10     
hidden space to extractable space and distinguishable group consensus     
32:15     
embeddings to associate a more powerful strategy F this Vector quantize     
32:20     
variational Auto encoder is described here and it's there and the this is a figure     
32:28     
showing this schematic re of the V Vector quantize group     
32:33     
consensus you plug it into an auto encoder you have this group code book you have this history decoder and then     
32:40     
this group consensus embedding which leads us to the group consensus policy and the group guided     
32:48     
policy okay so I think that's enough on that paper that's uh that was one of the     
32:54     
papers in our Channel I think it has a lot of relevance to a lot of the things we've been talking about with     
33:00     
multi-agent reinforcement learning swarm intelligence Etc and it's interesting to     
33:05     
see what people are doing and trying to get at that individual group distinction that people have been trying to get at     
33:13     
uh in a number of different areas of uh Theory like from evolutionary     
33:19     
theory to psychological theory etc etc so it's kind of interesting to     
33:25     
see that this is another paper here this is     
33:33     
um from the art also from the archive this is called micro vqa a multimodal     
33:39     
reasoning Benchmark for microscopy based scientific research so we were talking a     
33:45     
little bit about um the um large language model     
33:51     
scientists uh or the AI scientists a couple weeks ago we were kind of talking     
33:58     
about how you know reasoning in large language models requires hypothesis     
34:03     
formation or hypothesis generation and then kind of dealing with that um as a     
34:11     
system so this is where they're using microscopy data as the input and they're     
34:17     
trying to build this workflow where you can you know have this sort of visual     
34:23     
understanding this hypothesis generation and then this experimental proposal proposal so you're trying to form ex     
34:30     
form uh sort of experiments based on hypotheses that     
34:37     
result from observations basically so this figure one is a     
34:44     
scientific experimentation workflow that drives Discovery researchers analyze     
34:49     
experiments develop hypotheses and design forther experiments to test their ideas we release micro vqa a visual     
34:58     
uh question answering or vqa Benchmark to test these three tasks     
35:03     
in the context of biological microscopy so each of these 1042 samples     
35:09     
is created by a biology expert and transformed into a multiple choice     
35:15     
question so this is basically the the pipe or the the     
35:21     
workflow um so the first part is expert visual understanding and so you want to     
35:27     
develop this sort of perception ability so the question is what is unusual about     
35:33     
the result so the system is presented with these microscopy images and the imperative is to find the     
35:41     
things that are unusual about the image so you know you can do like     
35:47     
feature selection which is one way to analyze images another way to analyze     
35:53     
images is to ask what's unusual about the result but to ask the in terms of     
35:58     
specific questions so this relies of course on labeled data you have to have labels on     
36:04     
this and one of the questions here is how is the cpin localized within the     
36:09     
endoplasmic reticulum so you have the endoplasmic reticulum and you're looking at the     
36:16     
sepin and you're looking at how it's localized and you're trying to answer that question and maybe     
36:23     
identify edge cases or anomalies the second question here is do     
36:29     
cells treated with baf A1 on this left hand side Express more p26 compared to     
36:35     
the control which is on the right hand side so a lot of times you know you'll have experiments that generate a control     
36:42     
versus a treatment so you want to find the difference between the treatment and the control so those are the kinds of     
36:49     
things that perception involves it involves finding anomalies or finding     
36:55     
unusual results with a guided question or has to be a specific question it can't just be find     
37:03     
anomalies because that does that generates a lot of false positives as you might imagine so definitely fits     
37:11     
into the sort of the philosophy of uh science that is you're answering very     
37:17     
guided questions you know they say like science is about the questions and so     
37:23     
this this is answering some of these questions at the level of perception the second is hypothesis     
37:30     
generation so instead of asking what is unusual about the result you might ask     
37:36     
why does this happen in my experiment and so this is assessment instead of     
37:41     
perception and so this also evolves around some or revolves around some     
37:47     
questions the first one is which mechanism might explain why aslv particles show signs of merging in a     
37:54     
cryoem image so this is where you see this you have this cryogam image you     
38:00     
know that it's a certain type of image and then you know that like there's this     
38:05     
phenomena in the image it's not an artifact so you might it might be artifactual it might be some biological     
38:12     
phenomenon so you have to think about the mechanisms that might explain this thing in the     
38:19     
image and again it could be it could be an artifact it could be just kind of     
38:25     
chance but it also could be something um that's mechanistic in the     
38:31     
biology the second question is which gleo cell is likely a responsible for this abnormal reticular fiber pattern so     
38:38     
you see this pattern here you get this from the perception stage you might ask     
38:44     
you know this seems kind of like it might be a question you ask under perception but you're actually asking a     
38:50     
question about the GU cells themselves not to explain the pattern but to ask     
38:56     
which things are responsible for this result so this is again where this image     
39:03     
is evaluated in terms of potential hypotheses so you generate     
39:09     
hypotheses and then finally you get to this experimental proposal so how do you test that     
39:14     
hypothesis and so then that goes from assessment to action so then that requires the system     
39:22     
to give a set of experiments to answer some of these questions questions so the first     
39:29     
question is what experiment could you perform to test if CC and B1 protein levels relate to cell cycle stages in     
39:37     
human a431 cells so again what experiments could you perform not um you know     
39:44     
mechanisms or you know what's unusual about a result so this is just kind of     
39:50     
breaking this down into these stages um that kind of lead to different     
39:57     
experiments that can be tested so that's kind of where we are with that and again it's you know this     
40:03     
is supposed to be a high throughput system where you have a lot of images coming in and then you're generating a     
40:09     
lot of hypotheses and you're generating a lot of experiments which might be done say with a robot in a wet lab and I can     
40:18     
do like in you know thousands of experiments and you end up with this sort of set of results that are then can     
40:26     
be evaluated by expert human so this is kind of goes     
40:31     
over um this multim you know they're kind of using these multimodel large     
40:37     
language models um and so despite recent advances     
40:42     
in the area of mlms for AI assisted research existing     
40:47     
multimodal reasoning benchmarks only target up to college level difficulty     
40:52     
while research level benchmarks emphasize lower level perception following short of the complex     
40:58     
multimodal reasoning needed for scientific discovery so to bridge this Gap we introduce micro vqa which is a     
41:07     
visual question and answering Benchmark designed to assess three reasoning capabilities vital in research workflows     
41:14     
expert image understanding hypothesis generation and experiment proposal so     
41:20     
those are the three that they identify here and so they go through this system     
41:25     
and kind of thinking about um benchmarking so benchmarking on state     
41:30     
of the mlms reveal a Peak Performance of     
41:35     
53% models of smaller large language models only slightly underperform top     
41:41     
models suggesting that language based reasoning is less challenging than multimodal     
41:46     
reasoning so this is interesting if you're doing language based reasoning it's actually less challenging than the     
41:53     
sort of multimodal reasoning and then tuning with sign scientific articles enhances     
41:59     
performance expert analysis of Chain of Thought responses show that shows that perception errors are the most frequent     
42:06     
followed by knowledge errors and then overgeneralization errors so again this is the sort of     
42:13     
Chain of Thought response where you have these perception errors like these false positives that are picked up by in the     
42:20     
perception stage and then knowledge errors which is like an error in kind of     
42:26     
in interpreting those uh that perception and then overgeneralization errors which     
42:33     
is where you're overgeneralizing in the second step and it affects the third     
42:39     
step these insights highlight the challenges of multimodal scientific reasoning showing micro vqa is a     
42:45     
valuable resource advancing AI driven bio biomedical research so they have     
42:52     
Micro vqa available on hugging face and then the project is also in a GitHub     
42:59     
repository so the GitHub repository is here this is the paper     
43:04     
with um code code is here in this     
43:10     
repository um and kind of you know I guess you can clone it and use it for     
43:16     
your own purposes okay I don't know if you wanted     
43:21     
to stop here and ask answer ask or answer some questions have a question     
43:26     
answering session     
43:35     
here I mean I love this or you know it's     
43:41     
um I don't know if this should be in the the data IML or     
43:48     
the you know whatever we want to call the the AI for science oh yeah kind of     
43:55     
you know um because again it's it's it's certainly trying to     
44:04     
distill um yeah you know like like they said like like they're trying to distill     
44:09     
research level you know kind of     
44:17     
reasonings right yeah um you know it's not it's not reasoning it's     
44:24     
reasonings um that that you know humans humans would have from     
44:31     
from these things um and um yeah anyway okay we     
44:39     
need more advanced benchmarks yeah yeah     
44:48     
okay this is a article by Melanie Mitchell in science this is I think from     
44:54     
this week uh or yeah is from this week so this is uh now we covered some of her     
45:01     
blog posts um in a prior meeting a couple weeks ago talking about reasoning     
45:07     
in in AI in large language models so this is where she's has this article in     
45:13     
science it's just kind of I guess a an opinion piece but it's you know kind of     
45:18     
following up on those blog posts this is called artificial intelligence learns to reason     
45:27     
so starts with this statement Julia has two sisters and one brother how many sisters does her     
45:34     
brother martin have okay so that's the puzzle now it may seem obvious but of     
45:41     
course the probably will not be since she posed the question solving this tiny puzzle     
45:48     
requires a bit of thinking you might mentally picture the family of three girls and one boy and then realize that     
45:54     
the boy has three sisters or he might figure out a more general rule any boy     
45:59     
in the family will have one more sister than any girl in other words the answer     
46:05     
to such a puzzle isn't something you immediately know like Paris is the     
46:10     
capital of France it requires reasoning a central feature of human intelligence and one     
46:17     
that larger language models like gp4 with for all their impressive Behavior struggle with I gave this     
46:24     
puzzle several times the most recent version of GP G4 which is 40 and it gave me the wrong answer each     
46:31     
time asserting that Martin had two sisters indeed several systematic Studies have shown that GPT for in     
46:38     
similar models lack abilities for robust reasoning limiting their usefulness in     
46:44     
many domains prompting tricks such as adding lets think step by step to the     
46:50     
end of a query to encourage better reasoning can improve lm's problem solving abilities in some cases     
46:57     
but such tricks haven't worked well enough to turn these systems into robust reasoners to remedy this many of the T     
47:04     
many of the top artificial intelligence companies have recently created new kinds of AI systems often called large     
47:11     
reasoning models I think we talked about that um that was Zara who had mentioned     
47:18     
that last week so that is uh a new tool she was     
47:24     
talking about the ones that Meadow was developing but I guess this is a more General uh Trend in the     
47:30     
area uh larger reasoning models are spec specially trained to perform certain types of     
47:36     
reasoning these include open AI 01 and 03 models anthropic clad anthropics     
47:43     
Claud with extended thinking mode Google's Gemini 2.0 flash thinking     
47:48     
experimental and that Chinese company deep seeks R1     
47:54     
model okay so those are examples of these kind of large reasoning models if     
48:00     
you give an lrm a puzzle like the one above it will generate a so-call Chain     
48:05     
of Thought natural language statements describing a plausible sounding reasoning process in a stepbystep     
48:11     
fashion so this Chain of Thought is the thing that it's generating instead of just an     
48:18     
answer um and so what is that better or is that you know at least it gives us     
48:24     
sort of this transparent um output so natural language statements     
48:31     
describing a plausible sounding reasoning process at a stepbystep fashion describes a sort of Chain of     
48:38     
Thought approach for example I gave the sisters puzzle to open AI 01 model     
48:45     
unlike gp24 the 01 model gives me its Chain of Thought to arrive at a correct     
48:50     
answer so it's Chain of Thought is as follows number one Julia has two sisters     
48:56     
that means there are three girls in total Julia plus two more Julia also has one brother named     
49:03     
Martin altogether there are four siblings three girls and one boy Martin     
49:09     
from Martin's perspective his sisters are all three girl of the girls Julia and her two sisters therefore Martin has     
49:16     
three sisters okay so that's five steps and it's kind of going through and it's trying to figure out the answer from all     
49:24     
the available information and sort of an inference as well this sounds very much like human     
49:31     
thinking out loud and indeed 01 and other lrms are trained on many examples     
49:36     
of human generated chains of thought being able to generate such reasoning steps has enabled lrms to reach new     
49:42     
performance Heights on difficult science math and coding benchmarks for example open AI reported     
49:49     
that it's a one model placed in the top 500 students in the US in a qualifier     
49:55     
for the US master Olympiad and exceeded the accurac accuracy of PhD scientists     
50:02     
on a benchmark of physics biology and chemistry problems other lrms have     
50:08     
attained similar Benchmark performances some companies are betting Big N lrms being the basis for AI     
50:15     
assistant that are commercially lucrative open AI for example has released its best lrms and it's     
50:22     
Associated deep research tool subscribers paying $200 per month and is     
50:28     
said to be considering charging up to $20,000 per month for reasoning models that can carry out PhD level research     
50:35     
whatever that is um is defined by these kind of reasoning models uh but some researchers are     
50:41     
questioning all the excitement over lrms and asking if these models as one handlight put it are really thinking and     
50:48     
reasoning or just pretending to that is does their Chain of Thought training enable them to reason in a     
50:55     
general and robust way or are they succeeding on certain narrowly defined benchmarks by merely mimicking the human     
51:01     
reasoning they were trained on I'll say more about these questions later but first I'll sketch out how     
51:08     
these models work and how they are trained so this is kind of and you know     
51:14     
this is just kind of a general model of how these things work so the different models of different ways that they     
51:20     
Implement them but uh so an lrm is built on top of a pre-trained base model     
51:27     
and large language model such as D gp40 in the case of deep seek the base     
51:33     
model was their own pre-trained large language model called B3 these base models have been trained     
51:39     
on huge amounts of human generated text where the training objective is to predict the next token in a text     
51:45     
sequence so like a typical large language model the base model was in post-t     
51:52     
trained that is further trained but with a different objective to spefic specifically generate chains of thoughts     
51:58     
such as ones that 01 generated for the Sisters puzzle so I think we had the     
52:03     
diagram I week of the different posttraining uh methodologies that are used in for     
52:10     
different models so it's basically where you train the model and then you post train it using a different objective to     
52:17     
generate these chains of thought after the special training when given a problem the lrm does not     
52:24     
generate tokens one at a time but generates entire chains of thought so it doesn't no longer generate single tokens     
52:32     
in sequence it's generating kind of these uh thoughts in sequence and then     
52:38     
putting them together as this s reasoning chain such change of thought can be     
52:43     
really long unlike say GPT 40 which generates a relatively small number of     
52:49     
tokens one at a time when given a problem to solve models like 01 can     
52:54     
generate hundreds of thousands of chain of thought steps sometimes settling hundreds of thousands of generated     
53:00     
tokens making up the Chain of Thought steps most of which are not refill to the user and because customers using     
53:07     
these models at a large scale or charged by the token this can get quite     
53:16     
expensive thus an lrm is substantially more computation than a larger language model to generate an answer so this     
53:25     
computation might involve generating many different possible chains of thought using another AI model to rate     
53:31     
each one and returning the one with the highest rating we're doing a more sophisticated kind of search through     
53:37     
possibilities akin to the look ahead search that chess or go plane programs do to figure out a good move so I like     
53:44     
this this is interesting that they're kind of comparing these chth thought models to these sort of the chess     
53:52     
playing models that we were doing with good oldfashioned AI or go     
53:57     
five where you would have these look ahead search tables you try to figure out every possible move going     
54:05     
forward uh when using a model such as A1 these computations happen to behind the     
54:10     
scenes the user sees only a summary of The Chain of Thought steps generated so     
54:16     
to accomplish all this the post trainining of uh lrms typically use two machine learning methods supervis     
54:24     
learning and reinforcement learning so this is where we were talking about last week we had this table where we had the     
54:31     
different models the different large language models and then we had this sort of emphasis on reinforcement     
54:37     
learning in the reasoning step or the post-training step and so this is why     
54:43     
they're using reinforcement learning because you have this supervised learning where you're kind of giving it     
54:48     
a you know some sort of supervision as to what the correct chain of thought     
54:54     
might be and then this reinforcement learn which reinforces the correct answers so supervised learning might     
55:01     
involve training the uh lrm on human generated reasoning steps created by     
55:07     
highly paid human experts as phds that they say you know it's PhD level reasoning it's because you're     
55:13     
using highly paid human experts to generate reasoning steps as the     
55:19     
supervision where on chains of thought generated by another AI model where each step is graded by humans and yet another     
55:26     
AI model then it's AI models all the way down and human experts all the way down     
55:31     
as well reinforcement learning by contrast an unsupervised method uh or     
55:38     
reinforcement learning is by contrast an unsupervised method in which the lrm     
55:44     
itself generates an entire set of reasoning steps leading to an answer and the model is rewarded only for getting     
55:50     
the right answer and for putting the reasoning steps in the right format for human readability such as numbering them     
55:57     
sequentially or putting them in some framework to interpret the power of     
56:02     
reinforcement learning over huge numbers of Trials is that the model can learn which kinds of steps work and which do     
56:08     
not even though it is not given any expensive supervised feedback about the quality of the     
56:14     
steps so the 2025 touring award was awarded to two researchers who have     
56:20     
helped develop the basic reinforcement learning methods that are now used to train lrms     
56:27     
so that's interesting um so there's been a substantial debate     
56:33     
in the AI community of whether lrms are genuinely reasoning or merely mimicking     
56:39     
the kinds of human reasoning that is in the pre-training or posttraining data so     
56:44     
one interest industry blog called 01 the first example of a model with true     
56:49     
General reasoning capabilities others were more skeptical philosopher Shannon Valor called lrm's     
56:57     
Chain of Thought processes a kind of metam mimicry that is these systems generate plausible sounding reasoning     
57:03     
traces that may make the human Thinking Out Loud sequences they have been trained on but don't necessarily perform     
57:09     
robust General problem solving so that's that's you know those are two perspectives there's you know     
57:17     
some people who think that these are true General reasoning capabilities there there people that say well it's     
57:23     
kind of this urat reasoning that resembl reasoning but it's not problem solving     
57:29     
in any sense but of course it's not clear what genu genuinely reasoning even means uh reasoning itself is an umbrella     
57:36     
term for many different types of cognitive problem solving processes humans use a multiplicity of     
57:42     
strategies including relying on memorized steps specific heuristics such as rules of thumb that     
57:49     
we use for kind of good enough Solutions analogies to P     
57:55     
Solutions and sometimes even genuine deductive logic so it's a grab bag of things that we use for reasoning it's     
58:01     
not just the sort of logic one type like logical deduction or it's not just     
58:07     
listing out a set of steps and walking through them as sort of the sort of you     
58:12     
know constraints set of constraints so you know there it's really kind of     
58:19     
reasoning if you give it a clear example or a very simple example it might do     
58:24     
very well but if you give it a a more convoluted example it might not because you need to bring other different types     
58:30     
of strategies to bear on it so in in the world of lrms the term     
58:38     
reasoning seems to be equated with generating plausible sounding natural language steps uh to solving a problem     
58:45     
and the extent to which this provides General interpretable problem solving abilities is still an open     
58:51     
question so this uh goes on a little bit more but basically basically that's the idea of this     
59:02     
article so yeah it's it's a you know it's a good summary of     
59:12     
her well I mean it's it's it's an overview um just just one thing um Sarah     
59:20     
was talking about uh large concept models oh okay she she     
59:27     
she she talked about doing a presentation on large concept models     
59:34     
okay that and that something akin     
59:42     
to sentences being tokens something like that okay like yeah um where this was     
59:53     
definitely focused on you know what what we've why there's been such a plation of     
59:59     
posts and data ml yeah which is this this you     
1:00:05     
know like um certainly kicked off by Deep     
1:00:11     
seek um not not that they kicked off this set of     
1:00:18     
models but but when they're when they're you     
1:00:23     
know much um smaller team produced     
1:00:29     
a um kind of like an 01 competitor right     
1:00:34     
U with with such modest resources and um and training training resources that um     
1:00:44     
yeah but you know as as usual melan keeps it um or at least     
1:00:52     
as you know as as like we've said or you know this is this     
1:00:59     
is my weekly like uh all these people talking about these models have a     
1:01:04     
trillion dooll reason to lie about them yeah you know and and     
1:01:12     
um or or you know if if if     
1:01:18     
scientists have certain incentives     
1:01:24     
to you know gloss over problems in papers um these guys again have Empires     
1:01:37     
build you know Empires are at stake for these people and you know um again it it     
1:01:46     
always you know just think about the Chris fry the modal AI guy just you know     
1:01:56     
at the end of the day this comes down to yeah that's like these are these are the the last experts we can pay to solve     
1:02:05     
problems and create training data sets for us right yeah it's like like you     
1:02:11     
know yeah phds we could we could try and just     
1:02:18     
makes me also think of the um um Steve pentad DOI who's the yeah P do     
1:02:28     
B Berkeley yeah yeah um you know that     
1:02:34     
U language is for communication Not For Thought     
1:02:39     
yeah right and and you know I I I     
1:02:44     
get you know I get syllogisms and their power or you know     
1:02:53     
like their utility um but yeah just seems seems very much like     
1:03:02     
our um our our Reliance on the tools that     
1:03:11     
we're actually using to try and explain our our reasoning to each other you know     
1:03:18     
yeah as opposed to it being H how how reasoning is done yeah desing something     
1:03:26     
but you're not actually engaging in it yeah yeah the the the um     
1:03:34     
the yeah yeah as well as like you know how I     
1:03:41     
mean there I mean old     
1:03:46     
um I don't know I believe it's a religious saying you know that he who     
1:03:52     
tastes knows but you know the funny thing that you have when you try to     
1:03:57     
explain a taste or explain a smell where you're just like like I don't I don't     
1:04:03     
have words for this yeah you know and and and it's     
1:04:09     
not yeah and it it kind of it somewhat gets     
1:04:14     
it like we're not     
1:04:20     
trying you know again it's not just that language is communication but like     
1:04:25     
language is is is built up for communication about those things that we     
1:04:32     
have reasons to communicate about right right because I can just be like oh you     
1:04:39     
don't get that smell here's the soup I'm I'm you know like smell this you know     
1:04:45     
like and and um anyway it it's uh and     
1:04:52     
just just one final thought on that is somebody um we had a a meeting event     
1:05:00     
last night at the bolab and somebody was asking about     
1:05:08     
um I forget [Music] exactly I forget exactly their example     
1:05:14     
but it was something like um why do people     
1:05:21     
recommend and you know including great great thinkers that you to you know     
1:05:26     
engage in some task when you want to you want to think about a problem like like     
1:05:33     
like um you know going out and and um     
1:05:39     
doing doing some sort of mindless task or going for a walk or you know one of     
1:05:44     
these things and and it kind of came back to that particular point which is     
1:05:51     
that um you know you you if you really want to think you kind of need to shut     
1:05:58     
up you know it's so giving giving your giving yourself something to do giving     
1:06:04     
yourself something to to um keep your keep     
1:06:10     
your embodiment busy right um is is yeah anyway but I I I I     
1:06:22     
um I posted I think in random     
1:06:30     
um I'm trying to think of the Gail Gail Vera so this is one of the psyit learn     
1:06:36     
core developers right and he I I think he was just responding     
1:06:42     
to Melanie's post or um was this like whenever I wanna whenever I want to     
1:06:49     
demonstrate how dumb a llm is uh uh I just uh ask it to play tic tac toe oh     
1:06:59     
yeah you know yeah anyway the these These are     
1:07:11     
um you know these are incredible um artifacts right you know I     
1:07:19     
mean it's it's like like when you think of the complexity taken to create this     
1:07:24     
this this Matrix if you will right it's got     
1:07:31     
incredible structure I I and the um people have been posting this week about     
1:07:37     
the U the hugging face     
1:07:44     
um connections between models     
1:07:50     
did did I not post this I'm not sure um so so just a really interesting a really     
1:07:57     
interesting visualization of the connections between these models but but     
1:08:02     
the which which is that you know which is to say like one of them is not just     
1:08:09     
an incredibly complex artifact but you know we've we've been making     
1:08:16     
these these many complex artifacts and an entire you know kind of an entire     
1:08:22     
industry around analyzing and and trying to understand what are these complex     
1:08:28     
artifacts that we've we've now made yeah um but how much are they actually     
1:08:34     
reasoning and and how do we even get at that is is you know a much more profound     
1:08:41     
question I mean other than doing you know Mechanical Turk for phds right yeah     
1:08:48     
so this is charting and navigating hugging face model Atlas so this is an analyzing hugging face I guess     
1:08:56     
yeah um yeah so this is stable diffusion versus     
1:09:01     
llama model Atlas visualizes models as nodes and graphs this is llama this is     
1:09:07     
stable diffusion and kind of looking at you know how they usually they do these maps     
1:09:13     
of literature um you know if you have a bunch of papers looking at where they     
1:09:20     
kind of fit into the literature so we have this um Atlas here     
1:09:25     
where we have llama models stable diffusion models and then these different categories adapter fine-tune     
1:09:33     
quantization merge unknown in root so you see that the root models are here     
1:09:40     
and then they have all these Forks which then have these different attributes     
1:09:46     
some are fine tunes some are adapters some are quantized     
1:09:52     
models some are unknown models so um the figure shows that the top 30     
1:09:59     
most downloaded models in the staple diffusion and llama regions node size reflects Chala of monthly downloads and     
1:10:06     
color denotes the transformation type relative to the parent model so this is     
1:10:11     
where the color coding comes in please zoom in to see the detailed model     
1:10:16     
trajectories we observe that the Lama region is more complex structure and her wider diversity of transformation     
1:10:23     
techniques compared to stable diffusion note that node position is optimized for clarity and does directly reflect     
1:10:30     
distance between model weights so I don't know if this model Atlas demo does anything here let's see     
1:10:36     
oh this is okay the interactive version so this is um yeah so you can click on some of     
1:10:45     
these Let's see we can zoom in on them um all right so this kind of Zooms in on     
1:10:52     
specific connections here uh uh yeah then just describes the name of the fork     
1:11:00     
here um this is uh okay that's fine     
1:11:05     
tuning this is an adapter model and then this is the uh this is an     
1:11:12     
unknown model let me Zoom back out to find the root model here it is this is     
1:11:18     
meta meta's llama model uh 38b and then you have these different     
1:11:25     
for fors and you have black forest Labs flux one which is a root model and you     
1:11:31     
have all these Forks here so this is really cool if you're looking for you know if you're     
1:11:37     
looking at a root model and you're looking for different versions of it it kind of guides you right to where that     
1:11:43     
is so yeah still a bit of an art project but it's absolutely still beautiful I     
1:11:50     
mean you know like our project in the sense of as they said like like the these are these these distances     
1:11:58     
distances aren't relevant right you know yeah yeah but but yeah but still you     
1:12:06     
know I mean again remarkable in terms of the amount of work and you know again I     
1:12:12     
I I would love to focus or you know more like the continual AI like how     
1:12:21     
much you know like we're not looking for kind of counteract actual information um you     
1:12:29     
know who's like what are the what are the deficits that are coming from     
1:12:35     
fine-tuning um better better characterization of the deficits that come from fine tuning and     
1:12:45     
um yeah well yeah yeah it's definitely in the spirit     
1:12:53     
of a lot of uh citation networks where you don't really have a strong set of quantitative     
1:13:01     
principles it's just kind of like visualizing things and so it's very much that art project aspect of     
1:13:08     
it pretty yeah yeah     
1:13:13     
yeah all right so this is uh something else that was posted in data science LL     
1:13:18     
this is Introduction to flow matching and diffusion models this is a MIT class     
1:13:24     
uh where they kind of go over this uh these different types of diffusion     
1:13:30     
models of flow matching and everything and this this was this was shared um I     
1:13:36     
mean I was just passing on what was shared by the um the guy who started     
1:13:44     
medark okay um which I forget exactly what medark um     
1:13:53     
technically represent um but it's the it's it's the online     
1:14:01     
community that develops particular machine     
1:14:06     
models for um um a lot of kind of I guess I guess     
1:14:14     
Medical Imaging just not sure what the the arc necessarily is an acronym for     
1:14:20     
yeah um but in particular what they're known for is the Mind's Eye um model     
1:14:30     
which is that that fmai of um I mean that kind of like f decoding     
1:14:38     
of is it natural scenes or movies um     
1:14:45     
anyway it certainly one of the groups that I look to just as a kind of like     
1:14:52     
open science Collective you know it's just it's just a group that formed online kind of under this     
1:14:59     
person um to to tackle things like that     
1:15:04     
yeah     
1:15:09     
um     
1:15:15     
and sorry I'm just just saying something but yeah thought thought it might be useful     
1:15:23     
yeah yeah so this is Ace course out outline uh they start with     
1:15:29     
flow and diffusion models talking about generative models stochastic and ordinary differential equations then     
1:15:36     
sampling from flowing diffusion models then they talk about constructing a training     
1:15:42     
Target uh training flow and diffusion models flow matching score matching     
1:15:48     
various approaches the diffusion models uh building an image generator they     
1:15:54     
actually have electure generative robotics which is really kind of interesting um large Behavior models     
1:16:01     
diffusion models for robotics I'm interested in the large Behavior models it's I don't know what     
1:16:08     
that is if are you familiar with that large behavior     
1:16:14     
model um do you think it's like um um sort of like robotics well yeah     
1:16:22     
it's in in a a robotics kind of thing but I don't know oh heard of     
1:16:27     
behavior just kind of reminds me of that um what did they call it like     
1:16:33     
um like XX something anyway but it's just     
1:16:40     
like like you know being being able to do very large you     
1:16:49     
know like like a very generalist policy for for like a lot of different embedding I mean a a lot of different     
1:16:55     
embodiments terms of Robotics I don't know let me look let me stop     
1:17:04     
guessing if if we can't figure it out from uh searching then we can something     
1:17:10     
yeah large Behavior models oh large Behavior     
1:17:23     
models yeah well according to Google it's the next evolution in     
1:17:30     
AI well you do get the ad you know the ad version that's from that's that's from     
1:17:37     
Forbes Yeah well yeah Toyota Research     
1:17:46     
Institute let me see who's got something     
1:17:52     
here um yeah     
1:17:58     
multimodal     
1:18:10     
yeah you know I mean they're also talking about     
1:18:15     
like I mean again you know these these robotic models have the the same kind of     
1:18:22     
you know flation and complexity is the the atlas we just looked at you know um     
1:18:29     
in the sense of um you know how much they can you know you can demonstrate a     
1:18:36     
behavior you know like like if you just film yourself doing some task how you     
1:18:44     
you know like like how the model can extract your can copy your behavior yeah     
1:18:53     
um you know which is which is kind of by definition already kind of     
1:19:00     
like one of these visual models you know it's like definitely including     
1:19:08     
visual but I I I I wonder how much of these are still based     
1:19:14     
on well they say try to extract the get get past the     
1:19:20     
marketing speak here you know because it's it's like like they they they so want to call this the you know an     
1:19:28     
absolute breakthrough and yet these are all from last year yeah so where is it     
1:19:33     
this year yeah it it just it seems like people trying to make it a thing but     
1:19:40     
it's not a thing try to make it a thing and it's the these are all they're all     
1:19:45     
from a very tightly grouped set of you know you you can also     
1:19:51     
imagine that this was kind of like one press release but then made it into like oh yeah 10 blog posts you know so     
1:19:58     
they're all like November 20th     
1:20:03     
2024 um as well as just how you know how just     
1:20:09     
bad Google start these days as well right     
1:20:15     
um wait why why am I using Google or am I using Google no I'm using Duck Duck Go     
1:20:21     
here oh wow um now let me let me let's see anyway uh I I'll I'll see if there's     
1:20:28     
anything that we can post about this um okay     
1:20:34     
yeah oh yeah let me go back here uh so yeah there's a lot of stuff here even     
1:20:39     
generative protein design so you know there's a lot of stuff with respect to     
1:20:45     
diffusion models and flow matching and all these things this is something that maybe we could get into a little bit     
1:20:51     
more in subsequent meetings I might try to to put together some stuff for next week on you know kind of understanding     
1:20:59     
uh diffusion models and understanding some aspects of those but anyways um so     
1:21:04     
then there's this last thing this is actually the um the class inward detail     
1:21:11     
in introduction to flow matching and diffusion models and it kind of talks about some of these um things uh so this     
1:21:19     
is the introduction talking about the course structure generative model is     
1:21:25     
sampling flow and diffusion models going over those more in detail and again I don't want to get     
1:21:31     
into this this week but um we can get into this later constructing the     
1:21:37     
training Target conditional marginal probability path conditional marginal     
1:21:42     
Vector fields and conditional marginal score functions then training the generative model through flow matching     
1:21:49     
score matching and then a guide to the diffusion model literature     
1:21:54     
uh building an image generator um and then a reminder on probability Theory and a proof of the     
1:22:01     
fuer plank equation so this is all kind of provided as this     
1:22:07     
resource um yeah so that's uh what's going on in our data science ml channel     
1:22:15     
so um so yeah any questions or comments about that anything from VD or shyam did     
1:22:23     
you have any thoughts about this or     
1:22:31     
questions not many questions actually it's fine um I'll try sending more     
1:22:37     
papers this week or something okay that's great yeah first time I'm hearing about     
1:22:44     
flow matching and diffusion model so I don't really have a lot to say either     
1:22:50     
yeah yeah no problem yeah all right um You I I'll I'll post about Med Arc     
1:23:00     
too yeah just it's a it's a good group to to learn from they've got a got a     
1:23:07     
pretty active Discord not not not that we need to be on more discords     
1:23:13     
ands yet another Discord yeah so I'm going to get into a set of     
1:23:19     
papers here um this is a category I'm calling intelligence and by     
1:23:25     
ological natural systems um so you know we've talked a little bit about     
1:23:30     
intelligence and kind of the definitional problems with intelligence and you know and then I want to get into     
1:23:38     
some things having to do with biological systems natural systems and kind of     
1:23:43     
thinking about that [Music] so okay okay so yeah that's a link     
1:23:49     
Morgan just posted a link to uh Metar     
1:23:55     
AI okay so let me go back to this so this     
1:24:01     
is a paper uh from Network Neuroscience uh this is called linking     
1:24:07     
fast and slow so there's this idea of thinking fast and slow I think it's Conan who proposed this and this is     
1:24:15     
linking fast and slow so this is the case for generative models Carl friston is on the author     
1:24:23     
list um Peter Peter zidan's now head of um SPM development okay so so he he's     
1:24:33     
you know as Carl's moved to run the theoretical neurobiology     
1:24:39     
group um I think I believe zidan's the the successor to the analysis group oh     
1:24:45     
okay yeah yeah I mean this is this is n Imaging stuff right     
1:24:50     
right so this is um kind of thinking about this idea of thinking fast and     
1:24:57     
slow as like in in terms of these neuronal networks that we can build from Neuro Imaging     
1:25:03     
data uh so let's let's go over the abstract um a pervasive challenge in     
1:25:08     
Neuroscience is testing whether neural connectivity changes over time due to specific causes such as stimuli events     
1:25:16     
or clinical interventions so this is something where you need to look at neural connectivity     
1:25:22     
and how it changes so you have to establish or some sort of causality as opposed to just observing changes and     
1:25:28     
interpreting them as something you know you have a certain likelihood that it     
1:25:34     
could be many things or one thing but you have to establish sort of causality to really say whether you know     
1:25:41     
it's due to some specific stimulus or some clinical     
1:25:48     
intervention recent Hardware Innovations and following data storage costs enable longer more natural itic neuronal     
1:25:56     
recordings and so again we're getting better recordings more recordings and so     
1:26:01     
this is this this imperative is is stronger than ever the implicit     
1:26:07     
opportunity for understanding the self-organized brain calls for new analysis methods that link temporal     
1:26:13     
scales so this is where we're getting these kind of continuous recordings we're getting longer recordings in these     
1:26:20     
naturalistic settings and it's no longer kind of like where you have you know you're testing things with a fixation     
1:26:26     
cross and then you're getting people to clear their minds or so you think and then you're getting a recording of a     
1:26:33     
discrete task that you're presenting over and over and you can average over those things instead you're getting this     
1:26:38     
kind of um naturalistic data where you need to think about multiple temporal     
1:26:44     
scales so there's an interesting uh parallel here with continuous learning     
1:26:49     
and how you're not evaluating things on like specific very focused task it's     
1:26:56     
actually where you're trying to analyze Behavior over you know maybe in in some     
1:27:03     
context over a range of tasks uh the implicit opportunity     
1:27:12     
okay um so these temporal scales range from an or from the order of     
1:27:18     
millisecs over which neuronal Dynamics evolve to the order of minutes days or     
1:27:23     
even years over which experimental observations unfold so you have these multiple time     
1:27:29     
scales you have you know seconds where you get or milliseconds where you get     
1:27:35     
the neurodynamics for say observing some stimulus you know we have erps that kind     
1:27:42     
of describe these different things in the brain that happen when you're exposed to a specific stimulus but then     
1:27:48     
putting that in the larger context of minutes days and years where you have things embedded in time so you have     
1:27:56     
these events that are embedded in time and you have these long-term um uh performance issues in     
1:28:02     
the brain so if I give you a stimulus and it's repeated over many minutes you     
1:28:09     
know if I just do this continually if I have like a a bell that Rings continuously over time you know can I     
1:28:16     
observe not only the sort of response to that stimulus can I also observe some     
1:28:22     
sort of memory mechanism memory coding or can I observe some sort of large     
1:28:27     
scale change in attentional capacity or whatever so there's a lot here that's really interesting in terms of     
1:28:34     
uncovering different mechanisms in the brain and of course that affects the connectivity of a Neal Network because     
1:28:42     
you have Network changes that accompany that this review article demonstrates     
1:28:47     
how hierarchical generative models and basy and inference help to characterize     
1:28:53     
neuronal activity across different time scales so again they they're good old     
1:28:58     
basian inference and then these hierarchical generative models and this is some you know tools that we're using     
1:29:04     
to sort of characterize as normal activity crucially these methods go beyond describing statistical     
1:29:11     
associations among observations and enable inference about underlying     
1:29:16     
mechanisms we offer an overview of fundamental concepts in States based modeling and suggest the taxonomy for     
1:29:23     
these methods additionally we introduce key mathematical principles that underscore     
1:29:28     
a separation of temporal scales such as the slaving principle and review basy     
1:29:34     
and methods that are being used to test hypotheses about the brain with multiscale data we hope that this review     
1:29:41     
will serve as a useful primer for experimental and computational neuroscientists on the state of the art     
1:29:49     
and current directions of travel and the complex systems modeling lature     
1:29:56     
so this is where they kind of give this call for thinking about these cortical     
1:30:02     
circuitries and different time scales um and so you know this we can look at     
1:30:07     
seizures in our understanding of seizures to see how this is real you     
1:30:13     
know immediately useful so seizures sort of evolve in different parts of the     
1:30:19     
brain and there these like Cascades of electrical activity and to understand     
1:30:25     
seizures and their onset you need this sort of continual continuous data and this understanding of continual     
1:30:31     
cognition so you know how does a seizure say spread versus you know how does it     
1:30:38     
remain localized and so the relativity remains localized it's not a seizure but     
1:30:44     
if it spreads out in the sort of avalanche model then it's of course a     
1:30:49     
seizure so you have this sort of itinerancy of cortical circuitary parameters over seconds to minutes and     
1:30:57     
there are a bunch of references here in naturalistic experiments researchers     
1:31:02     
study the Dynamics of freely behaving brain of the freely behaving brain and     
1:31:07     
exchange with its environment on the scale minutes to hours so this is in where naturalistic     
1:31:13     
experiments um you know allow us to look at some of this freely behaving um you know what what happens     
1:31:21     
in the brain when you're allowed to explore and not fix uh focus on a specific task     
1:31:28     
but focus on a number of tasks and not necessarily in a focused way so this is     
1:31:34     
you know where you're doing this and of course not only does your behavior evolve but your neurodynamics evolve as     
1:31:41     
well on a larger time scale studying the perion of Alzheimer's disease requires     
1:31:46     
accounting for processes evolving over months years or even decades in these examples a challenge is     
1:31:53     
to understand how slow and fast components interact in other words how slowly     
1:31:58     
changing variables shape the evolution of rapidly changing ones and how the     
1:32:03     
latter reciprocally influences the former this is the citation Ellis Noble and O Conor so uh this is this citation     
1:32:12     
here we'll get to that in a minute uh but basically you have these different types of components in this continual     
1:32:19     
Behavior Paradigm you have things that evolve fast or maybe repetitive and predictable and     
1:32:27     
then you have things that evolve more slowly and maybe are nonlinear in their response and so there are all sorts of     
1:32:34     
different things that we need to kind of think about all different sorts of Dynamics all different sorts of     
1:32:42     
U uh phenomena at different time scales so we need a statistical     
1:32:47     
framework to evaluate hypotheses when empirical observations span multiple     
1:32:53     
temporal scales when the hypotheses are framed on a different time scale from that of     
1:32:58     
observations so we might have a hypothesis that says you know we think that the neural Dynamics do this over     
1:33:06     
time and there's a you know okay we have to make an observation of that and we     
1:33:12     
have to kind of figure out what the signature is that can uh support or     
1:33:17     
falsify our hypothesis quantitatively comparing the evidence for hypotheses amounts theil     
1:33:23     
build generative models and comparing their ability to predict the data in     
1:33:28     
terms of model evidence such as marginal likelyhood modeling multiple temporal     
1:33:34     
scales affords the potential to better predict future observations so this is where we want to     
1:33:40     
generate different types of uh models to generate different     
1:33:47     
hypotheses and test those hypotheses so this is where generative modeling comes in     
1:33:54     
this review is based on the overarching idea that evaluating hypotheses with multiscale time series can be     
1:34:01     
systematically addressed by constructing hierarchical models where each level of     
1:34:06     
the hierarchy accounts for a different temporal scale so this is again where we     
1:34:11     
have like you know milliseconds minutes hours and and we     
1:34:17     
have like you know so many milliseconds in a minute in in a minute so many     
1:34:22     
milliseconds in in an hour and so we can look at things at the scale of milliseconds and then relate that to     
1:34:29     
what's happening on an hourly basis and this is the kind of hierarchical scale     
1:34:34     
you need because there are different processes happening at different temporal scales uh like for example you know if     
1:34:41     
you're exposed repeatedly exposed to a stimulus the response to that stimulus     
1:34:47     
from exposure to exposure is on onetime scale and then say a memory encoding     
1:34:52     
mechanism is present in another time scale     
1:34:58     
um and so they ask a question here how can hierarchical models be used to capture changes in neuroc connectivity     
1:35:06     
at different temporal scales and what is the mathematical justification for their     
1:35:11     
use how to evaluate the evidence for competing hierarchical models in order     
1:35:16     
to address neuroscientific hypothesis or make modeling decisions for example     
1:35:22     
which temporal skill should be modeled so we need to figure out kind of     
1:35:27     
what our hypotheses are and then what processes do we want     
1:35:32     
to model to sort of address those hypotheses and then you     
1:35:38     
know then build that into a model of neural     
1:35:44     
connectivity so you know they're kind of talking about so what they'll do in this     
1:35:49     
review is uh think about how we model the Dynamics of time ser series data at     
1:35:54     
a single time scale then separate time scales and mathematical models then introduce a     
1:36:01     
basy and statistical method for to evaluate the quality of multiscale     
1:36:06     
models and then conclude with this empirical example from epilepsy     
1:36:17     
research so they kind of get into some Concepts here so when we're talking about Dynamics you know we're talking     
1:36:23     
about different types of patterns that we want to see from you know get out of     
1:36:29     
these time series so when we get a Time series of course time series give us Dynamics they give us this sort of     
1:36:36     
dependent data over time with respect to time so each time point is dependent on     
1:36:43     
the prior time point so this is different than an experiment where you sort of average over     
1:36:49     
observations each observation is considered to be independent so you can do things like do     
1:36:55     
you know T tests or build models that are based on the sort of IID data or     
1:37:02     
independently distributed data in continual cognition or in     
1:37:09     
dynamical cognition we have this different set of Affairs which is that each prior time     
1:37:17     
point is you know each time point is dependent on its prior time point so you can build these kind of Dynamics iCal     
1:37:24     
models where you can look at different phenomena of sort of the evolution of a     
1:37:29     
Time series so we can look at these different things here we can look at these flows     
1:37:35     
and trajectories in a state space so the state space represents sort of all possible trajectories that result from a     
1:37:43     
series of observations you map the set by drawing this trajectory that kind of goes out     
1:37:48     
and this is X1 versus X2 so this is sort of where there     
1:37:53     
you can measure fluctuations you can measure uh repeated patterns and draw     
1:37:59     
them out like this um you can also look at trajectories in the time domain so     
1:38:05     
instead of comparing X1 and x2 in a b variat bace you can compare it to time     
1:38:11     
so X1 evolves over time X2 evolves over time and you can see that you know in     
1:38:17     
the in the state space you have this uh sort of ATT tractor Basin that forms you     
1:38:23     
can see that here and that's because you're getting this sort of repeated Behavior Uh When comparing X1 and X2 so     
1:38:31     
you get these sort of dynamics that are you know you get these uh periods where     
1:38:37     
there's a maximum and then a minimum and and so on and so forth they fluctuate over time and you're not capturing time     
1:38:44     
here but you're capturing the interaction between these two variables uh in the sort of IAD data     
1:38:52     
that we usually use in neuroscience science uh the interactions are bad but     
1:38:57     
in this case interactions are good they allow you to see these kind of evolutionary trajectories so again we     
1:39:03     
can do this we can plot this against two interacting variables we can plot this over time we get these uh oscillations     
1:39:11     
over time or what is more accurately described is sort of a flux over     
1:39:17     
time then you have bifurcations where you have trajectories that bifurcate due to some of event so you have maybe some     
1:39:26     
common trajectory that gets bifurcated by some historical event like a     
1:39:33     
perturbation if I'm exposed to some noise in the environment or if a seizure     
1:39:38     
an onset of a seizure occurs you can measure this out with these kind of tools looking at these     
1:39:45     
bifurcations and you know there's some sort of critical value that describes when a bifurcation is expected     
1:39:53     
to happen happen so these are all you know kind of there are a lot of predictive tools from complexity Theory     
1:39:59     
uh like the Hop F forcation which allows you to use parameters to predict or     
1:40:06     
model these sorts of phenomena in systems and then we have multistability which of course is where you can compare     
1:40:14     
two interacting variables in and instead of having one attractor Basin you have     
1:40:20     
multiple attractor basins or multiple points where the system is stable over time so you know again we have like a a     
1:40:28     
place where the system tends to settle we have maybe like one mean for that I     
1:40:35     
don't want to call it a mean but in general that's what it is it's a mean behavior and multistability of multiple     
1:40:41     
mean behaviors in different regions of the phase space and so you know the     
1:40:48     
trajectory might visit one of these stable points and then visit another stable point and then fluctuate back and     
1:40:55     
forth between these stable points with an intermediate of instability where     
1:41:00     
there's a potential for change large scale change to the     
1:41:05     
system so I want to look up this paper here um we' mentioned     
1:41:11     
before Ellis Noble and oconor     
1:41:24     
okay so there's this paper LS Noble and O Conor this is top- down causation an     
1:41:30     
integrating theme within and across the Sciences that's phrased as a question this is from interface focus in     
1:41:40     
2012 so this is the paper here top- down causation an integrating theme within     
1:41:46     
and across the Sciences so this is um by George Ellis Dennis Noble and Timothy OK     
1:41:52     
Conor um and then this abstract reads uh this is actually I think talking about the     
1:41:59     
special issue I'm not famili this is a special issue on top- down causation so     
1:42:04     
this there more papers to this but it kind of talks about the special issue uh this this issue of the journal     
1:42:11     
is focused on top down or downward causation the words in this title however already raise or beg many     
1:42:18     
questions causation can be of many kinds they affirm our ways of ordering our scientific understanding of the world     
1:42:25     
all the way from the reductive concept of cause as Elementary objects exerting forces on each     
1:42:33     
other through to the more holistic concept of attractors towards which whole systems move into adaptive     
1:42:40     
selection taking place in the context of an ecosystem as for top and down in the     
1:42:46     
present scientific context these are clearly metaphorical so top down just means like if you go to that top     
1:42:53     
hierarchical layer there's an effect that goes downward in the system so you     
1:42:58     
know if you think about um your body your body is like the top of a hierarchy     
1:43:04     
which includes you know um organs tissues cells and then you know with the     
1:43:12     
contents within a cell so anything I put my body through um if I you know if I'm     
1:43:20     
um if I experience a traumatic injury you know I can damage my tissues I can     
1:43:26     
damage my cells I can have blunt force trauma and they all happen at different hierarchical scales but that     
1:43:33     
perturbation is imposed from the top down you can also think about this in     
1:43:39     
terms of social organization where you have organizations where you have like a to a leader at the top of the hierarchy     
1:43:46     
and they impose rules that then the systems underneath them have to adhere     
1:43:51     
to and sometimes the mapping isn't very clear but that's what happens in these     
1:43:56     
kind of hierarchies is that top down things are sometimes inefficient sometimes they're you know     
1:44:04     
don't allow for uh certain types of complexity to evolve and so forth so     
1:44:10     
there's a metaphoric aspect to this but basically you know we think of top down as like this um imposition on a on a     
1:44:18     
system and so um in the present scientific context these are clearly     
1:44:24     
metaphorical is some of the articles in this issue of the journal made clear do we therefore know what we are talking     
1:44:30     
about uh so this is a set of papers by philosophers and scientists um and then they kind of talk     
1:44:39     
about this idea of of emergence and top down um you know     
1:44:46     
causation so this is this is really um I was kind of hoping for     
1:44:54     
uh more explicative paper but this is fine um they just talk about top- down     
1:45:00     
causation and so you know they actually ask if it's an integrating theme within     
1:45:05     
and across the Sciences um where you know you have different Sciences where they use this     
1:45:11     
concept but they have to map it to different things and this is good in terms of like uh thinking about neuronal     
1:45:20     
networks and intelligence because you have these things that happen at these large scales and kind of have to be sort     
1:45:29     
of imposed upon smaller scales and smaller processes so um then they say there's a     
1:45:38     
road map for future research which we won't talk about so much but is kind of relevant to this paper because I think     
1:45:44     
the idea here is that you're connecting this to emergence and emergent     
1:45:51     
complexity and if we go back to our paper a lot of our methods here sort of     
1:45:57     
implicitly involve emerging complexity because a lot of these trajectories over time will eventually     
1:46:05     
form these larger scale patterns which emerge from smaller skill interactions     
1:46:10     
so if you have interactions between like a stimulus and a brain response and     
1:46:17     
that's repeated over time you can get this large scale phenomenon of like adaptation or memory consolidation or     
1:46:25     
maybe a seizure if if you're in the right context but they actually do give some     
1:46:32     
interesting methodological um points here the first     
1:46:37     
is that they're evaluating hypotheses with hierarchical models a multiscale Time     
1:46:42     
series and so a mathematical model that they described earlier in the paper     
1:46:48     
specifies a hypothesis about how the measured data were generated arbitrating     
1:46:53     
between hypotheses entails us specifying a suitable set of models and having the     
1:46:59     
statistical Machinery in place to compare their evidence uh this selection sets out     
1:47:04     
recent developments in basy and statistical methods which are proving useful in neuroimaging and related     
1:47:10     
fields that deal with multi-kill time series data and dynamic models so they kind of go through this     
1:47:16     
they have this very basy and oriented approach where they talk about the     
1:47:21     
probability of one event affecting another event and of course that's what we're talking about with respect to     
1:47:29     
dependency with respect to time so you know it lends itself to this basan     
1:47:34     
approach where you can say what is the prior thing that happen and how does     
1:47:40     
that factor into the likelihood of something else happening so you can analyze these trajectories of basy and     
1:47:47     
techniques and basian descriptions um and then of course     
1:47:53     
talking more about hierarchical models and inverting     
1:47:58     
them so to recap each level of a hierarchical model has parameters that     
1:48:04     
are constrained by the level above for example with neuronal recordings a neurom mass model may be used at the     
1:48:11     
first level so at the lower level with parameters that encode synaptic connection strings so this is a specific     
1:48:18     
type of model people use to look at neuronal recordings and and you know the     
1:48:23     
parameters are specific to that context that application of the model of the     
1:48:31     
system slow changes in these synaptic parameters over a longer time period such as seconds or minutes are described     
1:48:37     
by the second level of the model with parameters that govern the slow Dynamics so you have two models here you have a     
1:48:44     
neurom mass model which encodes an aptic connection strengths but the strengths     
1:48:49     
change over time so you need a new set of parameters that describe those     
1:48:54     
dynamics of those connection strings changing so if you think about it in terms of like uh how those levels are     
1:49:03     
connected uh you know there's some top- down causation in terms of the changes     
1:49:09     
over time affecting the spe a specific instance of synaptic connection     
1:49:14     
strengths so if I give you a weight Matrix of synaptic connection strings that results from a snapshot in time of     
1:49:22     
this model of the lower model and then the model above it is     
1:49:28     
imposing um you know it's it's own that model is imposing uh itself upon those     
1:49:35     
Dynamics so it's determining those Dynamics okay so that's that's kind of     
1:49:41     
an example of that um and so yeah they get into a lot of good stuff in this     
1:49:47     
paper um but I think we'll stop there and go to the next one     
1:49:53     
so the next one is related to this and this is uh by Victor jerza and aidio     
1:49:59     
D'Angelo this is the Quest for multiscale brain modeling so this is related to what we were talking about in     
1:50:04     
the last paper this is where we're thinking about the brain at specific scales uh or specific levels uh     
1:50:12     
hierarchical levels and so we're thinking about things like synaptic     
1:50:17     
connections long-term synaptic changes uh you know brain re regions and     
1:50:24     
then things that affect the whole brain and so we have these different levels we have top- down causation but we also     
1:50:30     
sometimes a bottom up causation it's a bottomup causation is where you have things at lower levels that affect     
1:50:36     
things at higher levels and often times in complex systems we have a mix of both of them going out at the same time so we     
1:50:42     
have things coming from top down and also things coming from bottom up a lot     
1:50:48     
of times when we describe emergence for example we have this bottom up causation so we have have the actions of     
1:50:53     
individual agents that contribute to the formation of say like a flock or a swarm     
1:51:00     
or some collective some group and so you know those are but of course also that     
1:51:06     
group can affect the behavior of individuals can constrain the behavior of individuals it can determine how     
1:51:13     
they're organized what kinds of rules they follow and so forth so this top down and bottom up causation is a loop     
1:51:21     
and it's hard to sort of dis entangle that in complex systems which is why we need to do this sort of multiscale brain     
1:51:27     
modeling because analyzing the brain in anyone's scale of analysis is limiting     
1:51:34     
we can't necessarily make statements about causality if we don't have these different scales available to us so that's where     
1:51:42     
this review comes in uh the abstract talks about um sort of addressing the     
1:51:49     
multiscale organization of the brain so brain is inherently multiscale it's not just complex it has     
1:51:56     
many scales of organization and it's a challenge because we don't really understand fully     
1:52:04     
understand a lot of these scales and how they're related and when we say there's a scale we basically have to abstract that     
1:52:11     
out of what is basically the you know complex Dynamic organ so when we say     
1:52:19     
that like synaptic connections are a scale and we say the things that modulate synaptic connections are     
1:52:25     
another scale we're making a choice about what the scales are those aren't necessarily you know that mean there's     
1:52:31     
an inherent property of synaptic connections we can Define them and say     
1:52:37     
this is a set of synaptic connections and that is one scale of analysis and then the things that modulate those     
1:52:43     
synaptic connections are another scale of analysis but we don't necessarily know they're not necessarily separable     
1:52:50     
we don't necessarily know that that's another a higher scale or higher order and so we don't necessarily we can't     
1:52:58     
necessarily say a lot about top- down and bottom up causation in those     
1:53:04     
cases so uh in principle it should be possible to model neurons and its synapses in     
1:53:11     
detail and then connect them into large large neuronal assemblies to explain the     
1:53:17     
relationship between microscopic phenomena large scale brain networks and behavior     
1:53:24     
so it it should be possible to do this we should be able to get the detail and     
1:53:29     
then we should be able to uh kind of neatly separate these out kind of figure     
1:53:35     
out how they fit together and then uh explain this relationship pretty     
1:53:41     
easily however it is more difficult to infer neuronal functions from The Ensemble measurements such as those     
1:53:48     
currently obtained with brain activity recordings so our measurements in introduce another layer another     
1:53:54     
complication in this which is when we Define say like um a a scale we have     
1:54:02     
measurements that sort of Define that scale in other words if we have synaptic connections we have to measure those     
1:54:08     
synaptic connections using you know weight that weight then is what it's kind of describing what's happening at     
1:54:16     
that synaptic connection but then of course we don't know what that measure     
1:54:22     
you know if it's like the only measure available we might have multiple measures we might have Ensemble     
1:54:28     
measurements which are a collection of measurements and kind of how that fits     
1:54:34     
into function so you know this is kind of a harder problem so in this article     
1:54:39     
we consider theories and strategies for combining bottomup models generated from     
1:54:44     
principles of neuronal Bio physics with top- down models based on Ensemble     
1:54:50     
representations of network activity and unfunctional principles so what they're proposing is     
1:54:57     
that you have these networks and remember we're talking about a brain Network as our sort of goal as sort of     
1:55:05     
the top level and we have all these things that are contained in each node so every brain network is a series of     
1:55:12     
nodes and edges the nodes have properties sometimes they have     
1:55:18     
properties all the way down that is you can have a node that's like a neuron or a neuronal     
1:55:24     
connection and then there's like a biochemistry of that and you know there     
1:55:31     
and that's another layer of analysis so they're multiscale aspects of each node and then the uh edges which are the     
1:55:39     
edges of the network which could be described with multip in multiple ways and affects how we measure this network     
1:55:46     
and its connectivity so we have this bottomup sort of approach where we can take the     
1:55:52     
neuronal units and look at how they're connected together and then make inferences about the     
1:55:59     
network but of course if we get the measurement wrong down at the lower level then that you know that sort of     
1:56:05     
bottom up approach is flawed uh also with the top down     
1:56:10     
approach if we kind of infer a network from something like a a neuronal unit     
1:56:17     
and our measurement of the neuronal unit isn't exacting or you know good then     
1:56:23     
that can also play you that can also complicate our model so this is a pretty hard problem     
1:56:30     
um and so they describe a number of integ Integrative approaches that allow     
1:56:37     
us to build effective multiscale simulation in Virtual brains and neur robots or neuro robots and pave the way     
1:56:45     
to Future applications of medicine and information Technologies so in the highlights box     
1:56:52     
here they talk about multiscale brain modeling along with the availability of computational Technologies and     
1:56:58     
biomedical data this this is a grow rapidly growing field generating an     
1:57:04     
intricate set of strategies tools and applications data driven models using biological details at multiple scales to     
1:57:11     
simulate brain activity so we have data driven models we also have task driven     
1:57:17     
models which anticipate the functions needed to simulate Behavior so we     
1:57:22     
actually have two different types of models we can use for multiscale modeling we can have data driven models     
1:57:29     
which really focus on biological details getting uh biological data for these     
1:57:35     
different scales and then simulating what happens in the brain and then task driven models which kind of are Behavior     
1:57:42     
driven which are driven from specific tasks and looking at how those can be     
1:57:49     
used to simulate Behavior data driven models though can Pro     
1:57:54     
proceed an either bottom up or top down way so a data driven model if it's     
1:58:00     
bottom up it usually starts from neuronal and synaptic mechanisms and moves upward towards the brain Network     
1:58:08     
and top down is where we take the conomic data or the network data or     
1:58:13     
brain signal recordings from large regions and work downwards towards these neur one synaptic mechanisms and so we     
1:58:20     
can actually build go go in both directions at once but then integrating those as a     
1:58:26     
problem here we show how the different modeling strategies can be integrated to generate hybrid simulators allowing to     
1:58:33     
fill gaps and knowledge through principled rules to uncover hidden parameter values to generate testable     
1:58:39     
hypotheses guiding future research and to open New Perspectives for artificial intelligence towards personalized     
1:58:46     
medicine and bring digital twins so last part is always like marketing or you know kind of how this     
1:58:53     
is useful and you know but but this part kind of talks about the multiscale     
1:58:59     
aspect of brain modeling um so one interesting thing     
1:59:05     
here is where they talk about this multiscale problem which is of course how do we build accurate multiscale     
1:59:12     
models um that that integrate top down and bottom up causality in in a well-     
1:59:18     
defined way so facing the multiscale problem requires a well- defined strategy based on what are called direct     
1:59:25     
and inverse models so we have direct models and we have inverse models because they crucially determine     
1:59:32     
the way in which brain models are generated basically a direct model predicts the effects from knowledge of     
1:59:39     
the causes whereas an inverse model casts light on the causes given the     
1:59:45     
effects so we kind of know um sort of the causes I mean in a direct model we     
1:59:52     
try to predict the effect effects from knowledge of the causes so we try to     
1:59:57     
figure out what the causes are and then we predict the effects that we should see um so we have any sort of like set     
2:00:04     
of relationships between two things we can then predict the effects that should be there and that gives us our     
2:00:13     
model the inverse model by uh by contrast cast light on the causes given     
2:00:19     
the effects we look at the effects and then we try to inverse we predict the     
2:00:24     
causes so it just really depends sometimes on your system sometimes on     
2:00:29     
how much what kind of data you have and so forth more formally if one knows the     
2:00:35     
model FP as well as the parameters P one can directly predict the observable     
2:00:41     
signals which are the observed signals for a function of P inversely one can     
2:00:46     
determine P or its parameters based on observations uh of uh the inverse     
2:00:54     
observations in brain terms one needs to correlate the many neuronal activities that generate Ensemble Network     
2:01:00     
properties with the Ensemble signals measured through recording techniques such as MRI EEG meeg and pet the direct     
2:01:09     
problem is often referred to as the bottomup modeling strategy because it climbs the complexity scale from     
2:01:16     
elementary causes to Ensemble functions whereas the inverse problem relates to a     
2:01:21     
top- down modeling strategy because it tries to infer the hidden causes of The Ensemble     
2:01:28     
observations as discussed later modeling can go either way bottom up or top down     
2:01:33     
and the two strategies can intersect depending on the availability of data and the specific problem under     
2:01:41     
investigation so this is nice and and it kind of gives a little bit of a primer on how to implement these how to think     
2:01:48     
about them     
2:01:54     
yeah this is a summary of this so you have a direct problem versus an inverse problem you're going from elementary     
2:02:00     
causes which are say like single recordings or cell signals as they call     
2:02:06     
them and then you move maybe in from the direction of single cell signals to     
2:02:12     
Ensemble signals using the direct problem and the inverse problem is taking the Ensemble signals and moving     
2:02:18     
backwards to the Single Cell signals so single cell signal might be like a u recording     
2:02:26     
of uh direct like electrophysiological recording whereas an ensemble signal     
2:02:33     
might be something like an EEG trace or an fmri signal where you're measuring     
2:02:38     
from a number of cells simultaneously and getting a signal that sort of     
2:02:43     
summarizes that so what they're referring to is the model parameters that allow you to go from one type of     
2:02:50     
model to another so I think that's enough for that paper um any questions     
2:02:56     
comments and I'm going to talk about a a little bit different type of paper next so I know that Morgan has some opinions     
2:03:03     
about neuroimaging and well this is yeah this is my yeah     
2:03:10     
this is my area uh I I don't think multikill brain     
2:03:17     
modeling is used in Siri     
2:03:23     
yeah um uh but yeah Victor is the you know is one     
2:03:31     
of the three forces behind     
2:03:38     
um virtual brain project so this is um uh this is     
2:03:45     
the big um yeah it's it's his I mean     
2:03:52     
somewhat directed by him because he's the um he's the multiscale physicist     
2:03:58     
yeah you know like his his advisor was     
2:04:03     
um oh the lasers guy lasers guy I'm I'm blanking on them     
2:04:13     
yeah um synergistics oh haen Herman haaken     
2:04:21     
thank you thank you thank you yes yes yes yes yes and um anyway     
2:04:29     
um yeah so it's it's as well as as well as firstman you know I mean firstman and     
2:04:36     
zidan you know so it's like it's like you you     
2:04:41     
you you kind of have two competing software     
2:04:46     
projects right the London guys the London guys     
2:04:52     
are the kind of well for for certainly some decades have been the     
2:05:00     
the preeminent em analysis package and and thinking you know and     
2:05:07     
then expanding to EEG and you know so they were they were     
2:05:13     
dealing with these new time scales right and um and this also comes out from     
2:05:22     
you know the kind of examples that that the first and zyman paper are having     
2:05:28     
from from epilepsy where you've got you've got potentially grid electrodes in the brain itself right and and so you     
2:05:37     
could be doing recordings like that as well as as looking at     
2:05:42     
um uh other kinds of you know eai measures which which are     
2:05:49     
hemodynamic and therefore you know on whereas the the grids are on a mill     
2:05:57     
millisecond scale the the hemodynamics are on a a second scale right seconds     
2:06:04     
scale right and um and and certainly you know the the     
2:06:13     
hope is that you could potentially you could you know somehow     
2:06:19     
infer from the hemodynamic what what you should see if you were     
2:06:25     
recording from the electrod yeah um and and of course a big another yeah so this     
2:06:33     
is um this is certainly the reason that I've I've been very happy that     
2:06:41     
I you know crashed into EG at a young age from from no no you know no     
2:06:50     
direction of my own but um but just happened happened into a project that     
2:06:56     
that involved high density EEG and and so I got to see brain     
2:07:02     
Dynamics at at that different temporal scale right and and     
2:07:09     
um yeah so I I love these projects you know the the virtual brain project is     
2:07:16     
it's very different I mean he's it's funny though because I think one of your     
2:07:22     
versus big you know Perhaps Perhaps best funded I don't you know you never know     
2:07:29     
what which of these are passion projects or which you just happen to get funded but uh U his digital twin of epilepsy is     
2:07:38     
is is the virtual Brain Project you know I think it's the premier virtual brain     
2:07:45     
project um uh so they they they both can you know     
2:07:54     
they're both looking at it but from different perspective you know I think one reflects you know first you know     
2:08:01     
zman's the last author on that paper but that was very first in very first in     
2:08:07     
approach um I mean zon's a student of first and and so you know and it comes     
2:08:15     
out in certainly the um the active inference book you know     
2:08:23     
here is the the all the different the the hierarchical basian     
2:08:29     
models that they're talking about and     
2:08:37     
uh and your is giving you the physicist version of that you know right it's it's     
2:08:44     
it's you know but you to to some degree I mean but they     
2:08:50     
converge right right and so I think you know um it's uh yeah it it just kind of     
2:08:58     
speaks to their different different perspectives but um yeah yeah really really really um really important     
2:09:06     
somebody last night um you know this is this is a bio     
2:09:11     
meeting so this was a person who's coming from like computational chemistry but trying to     
2:09:19     
do uh trying to do modeling brain modeling     
2:09:26     
that included kind of like synaptic     
2:09:32     
release V vesical you know neurotransmitter release right as well     
2:09:39     
as like Global brain Dy Dynamics right and um and you know kind of kind of     
2:09:47     
Neuro Imaging I I think she's more coming from     
2:09:53     
um you know kind of pet     
2:09:58     
um which which is again like a a very different time scale but um     
2:10:06     
um it's U yeah it's it's the it's it's really the future brain     
2:10:14     
Imaging I mean in kind of like like the the world in which I was in um it's is     
2:10:21     
yeah being able to think more about those kinds of     
2:10:26     
multi-level Dynamics um inferences yeah great great you know     
2:10:34     
I I sent I sent one of those I actually sent the the years of paper to her okay     
2:10:39     
good the person I met last night was just like hey you should check I I'd said I'd said like you know she should     
2:10:46     
look at the virtual brain project and um yeah so that was a nice     
2:10:54     
uh article about it or you know about their philosophy yeah yeah so we have     
2:11:00     
these two different kind of ways of thinking about it but they're convergent largely the basian model being like by     
2:11:07     
large difference and uh you know there are different ways you can you know     
2:11:12     
charact these aren't the only two ways you can characterize this because we get out from neuroimaging we get to other     
2:11:18     
kinds of systems especially in biology like in ecology or like in um you know     
2:11:24     
other types of physiology where you're maybe thinking about different types of measurements or you're thinking about     
2:11:31     
different types of phenomena you know affecting uh it was it was intentionally vague about the different forms of     
2:11:38     
causality because you know these are theoretical Concepts and they kind of map to     
2:11:43     
different measurements different systems how they're defined how the levels of     
2:11:49     
complexity are defined so so it's really up to the like the system you're working     
2:11:55     
in and the conventions of measurement and the conventions of saying this     
2:12:00     
exists at this scale this exists at this scale yeah yeah yeah yeah for sure and     
2:12:07     
and yeah I mean sometimes it's like I mean I I think they might be using     
2:12:13     
causality but they kind of also just mean like temporal aggregation yeah like     
2:12:20     
like know but it the point being that you you have a microscale     
2:12:27     
model and it it and it has you     
2:12:32     
know you can you can you can determine the macro from the     
2:12:38     
micro right right um but it it that could be quite a simple yeah that could     
2:12:45     
be quite a simple averaging so to speak or yeah something like that yeah     
2:12:51     
so in some formulations of this you know the top down sort of serves as constraints and the bottom up serves as     
2:12:58     
sort of information so like if you have ner uh like if you have synaptic connections and they're going to the     
2:13:04     
next level to like a network level they're serving as information for that level whereas the network topology which     
2:13:12     
is the connectivity between cells or neurons that constrains your synaptic     
2:13:18     
connections and so you have that relationship and and that's like kind of more of     
2:13:24     
a uh you know more of a classic sort of complexity Theory approach where you     
2:13:30     
know it depends on your system what you're working and but you should be able to observe these things across     
2:13:36     
different types of systems there's an an assumption of universality there that basically this is how it works you just     
2:13:42     
have to find you know your system of interest and you'll find these kinds of Dynamics and principles at play right     
2:13:50     
right it it's it's I mean you can take the kind of like all you know all models are wrong     
2:13:58     
but some are useful yeah yeah you know but but I I I was thinking about that     
2:14:04     
when when you when you brought this up like I mean especially the first     
2:14:10     
and zidan one right which it it's I I     
2:14:15     
was just thinking about the kind of like the neuro AI for neuros science like     
2:14:22     
like they act they don't just want uh a lower     
2:14:29     
level dynamics that explains you know     
2:14:34     
that that explains the the kind of the data that they could collect at the     
2:14:40     
scale they can collect it right right they they want they want the mechanisms     
2:14:47     
underneath you know I mean they hope that they're settling     
2:14:54     
on something that's closer to the actual mechanistic bottomup models right I mean     
2:15:02     
let me give you an example and this this actually comes from a zyman like zyman talk     
2:15:08     
like a couple months ago um     
2:15:13     
where he he was talking about the SPM 25     
2:15:19     
and he he he brought up a tool from San Diego called f which is this kind of     
2:15:26     
like full spectrum EG modeling package that that Bradley voyex     
2:15:34     
group developed yeah and and voyex group is     
2:15:40     
doing is doing kind of like uh you know it's very much doing phenomenology of     
2:15:46     
the the power Spectrum yeah in the in the sense like it's not right so this is     
2:15:54     
this is your potentially um I mean even if you're not collapsing across channels     
2:15:59     
you you're getting you're getting this power spectrum and and zyman was talking     
2:16:04     
about how they want to move to a generative model of the of the EG power     
2:16:10     
spectrum and it's one of these it's     
2:16:16     
so so you could do that in a couple ways right you could do that where you in a     
2:16:21     
sense you don't have a spatial model right and and you know kind of a again     
2:16:32     
make it kind of like a a a mixture of     
2:16:37     
distributions that um that explain you know so it's just like you can look at that power spectrum and then not in like     
2:16:45     
a forier way but just in a probalistic distribution way you could see you could be like okay I've got like this     
2:16:51     
distribution that looks like a like a gamma that that has that kind of like     
2:16:56     
power law like like behavior and then I've got you know like kind of like a a     
2:17:04     
leoan at a at a at around Alpha and and like a smaller one around uh beta you     
2:17:14     
know that that explains the little blps that you usually see in these um     
2:17:22     
uh but that that doesn't you know like like that is leaving out a lot of     
2:17:30     
information that is probably actually really important just in terms of the cortical sheet connectivity of the     
2:17:37     
cortical sheet and and you know to bring up like wave club and and Earl Miller     
2:17:44     
like that traveling waves are are a thing yeah and     
2:17:53     
and that that a lot of this kind of dynamical     
2:18:00     
systems um you know like like yeah just just that and and and like early like     
2:18:09     
thinking about early um neurophysics models from all     
2:18:16     
from Australia which I I assume just reflects like one pi that had students     
2:18:21     
or something like that but you know that that they were doing a lot of these models where it was     
2:18:29     
assuming the cortex is just a flat sheet um like like doing a lot of     
2:18:51     
you could start to explain the the EG power Spectrum this would be like um JJ Wright and Dave ly and and     
2:19:03     
yeah and like a bunch of um New Zealand     
2:19:08     
anesthesiologists for some reason yeah and yeah I mean it's just again     
2:19:15     
it's one of these it's one of these tradeoffs I guess you have to make in in     
2:19:22     
you know kind of physics modeling where it's like yeah     
2:19:33     
um how how yeah like how well can you can you specify in     
2:19:41     
advance that spatial model yeah or or something like like yeah you know and     
2:19:47     
that's and that's the that's the all models are wrong so useful thing it's just like some somebody eventually come     
2:19:54     
along with a more useful model um um anyway I'm I'm not sure if that that     
2:20:02     
rant made was helpful but yeah it was yeah it's     
2:20:09     
it's just just thinking about yeah just thinking about something as kind of like     
2:20:15     
easy to derive but but also that is widely used like like we make go all     
2:20:21     
these we do all these derived measures off of the you know human EG power     
2:20:27     
Spectrum we have no idea what it really I mean you know lot lots of lots of     
2:20:33     
theories but you know no really good solid answers in terms of you know what     
2:20:39     
is Alpha even right which was the original hansburg uh uh you know discovery of of     
2:20:47     
EEG in the like late 20s yeah any um all     
2:20:53     
right good papers yeah yeah thanks okay so I think that's it for this week um     
2:20:58     
thanks for attending and uh see you next week take care take care by thanks bye
