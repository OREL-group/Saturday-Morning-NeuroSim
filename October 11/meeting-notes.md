## Meeting Recording

[YouTube link](https://youtu.be/W8kWfLyg8_8)

## Mastodon thread

[link](---)

## Feature Videos

[Definitions of NeuroAI and Biological Intelligence](https://youtu.be/QRiCK3SWa1s)

[Graph of the disciplinary and topical components that define NeuroAI](https://youtu.be/0egVd5VGw2U)

[Assembloids and Connectoids](https://youtu.be/oNH08jSl6AY)

[Differences between ANNs and BNNs](https://youtu.be/5o9qNDvUw2M)

## NOTES
CONNECTION program —> learn methods during program, process a proper data next.

BRAINMODES 2025 (Toronto). Fields Institute (YouTube). Mathematical modelers (John Griffiths).

combining white matter, modeling stroke damage. Effect: a change in resting state.


Interesting papers: Emily Sherman, DARPA. INSPIRE program. 

what other mechanisms for storing/processing information? 

30th anniversary of Biological Cybernetics paper by Terry Sejnowski (firing rate).


Two roads diverged: paper on cortical organoids.

Brett Kagan —  chief scientist for cortical labs. 

Figure —> organoid vs. 3D printing path.


No good textbook, overview of cell culture.

Computational Perspective on NeuroAI and Synthetic Intelligence.

gets into Neuromorphic aspects.


Ge Wang — Medical Imaging. Josh Bongard — ekkolapto talk.

group talk (Computational Philosophy group).

Polycomputational paper from 2023. Unconventional computing — mechanical processes.

metamaterials and BVs. Gates could be a BV-inspired metamaterial. Analogue computing examples.

Wave Club (Earl Miller) —> Bard Ermentrout. 

electrophysiological people — traveling waves. Broadband brain activity (different frequencies = polycomputation).

Reservoir Computing with non-living matter.


Emergent properties. Beggs —> criticality. MAIN, Minneault paper. Compare with Kagan paper.

RL vs. Active Inference. RL with exploration “bolted on”. Tutorial on Active Inference (IWAI — Ryan Smith, ActInf collapses to RL).


Assembloids (tissues pieced together), Connectoids (microfluidic-based).

what about HTM (Numenta)?

Dendritic computation: filtered inputs (logic gates, weighted sums via circuits).

Avery has been playing around with AI stuff.

Meta-brain, Allostatic Types. Neurochat — Computational Sim.


People are using cybernetics (revisiting, something is there). 

Futures Center — launching stage. Alternatives, on rams, destinations.

case study of “intentional synthesis time”.


Spurious reward in RL (inferring quality of reward from environment).

reward is internal and dependent on stimuli.

## TRANSCRIPT   
0:00   
Hello. Morning. How are you?   
0:07   
Not bad. Good. It's dark.   
0:12   
Yeah, I see that.   
0:21   
Good. the um   
0:28   
connection program finished. Oh, okay. Good. I mean, you know, it's um I should say   
0:36   
like the the training phase. Um and then we go on to um well if the   
0:46   
if the students want to continue then they go on to um flex periods where they   
0:52   
start processing like a proper data set you know. Yeah.   
0:57   
Doing something at scale that would be you know actual   
1:04   
you know research caliber size right? Yeah.   
1:13   
So this was through Neuroch. No, this is um this is camera.   
1:20   
Okay. So um I forgot what camera stands for, but um it's something like um   
1:29   
democratizing uh democratizing   
1:36   
MRI in Africa. All right. Um,   
1:48   
yes. Global magnetic resonance multi-disiplinary experts implementing disruptive approaches that are advancing   
1:56   
high value MRI access in Africa. Okay. Um, so that's the that's the org   
2:04   
and then connection is this this training program that they run that like   
2:11   
is you know pairing pairing us up with students across Africa and um I think as   
2:19   
I said a couple weeks ago my mine are all in Ghana or like my team   
2:26   
u yeah I I feel like we should be called team team Ghana.   
2:32   
Yeah. Um but they're they're not in the same they're like each is in a different   
2:38   
city. Right. Right. So So we Yeah. And there was definitely   
2:45   
some some issues with just internet access and and you know um   
2:53   
sometimes just even the the you know not video chat but just the u   
3:01   
group chat would be   
3:06   
an issue. Yeah. Uh but um yeah,   
3:12   
I'm hope hoping that they will sign up for the for the next for the flex part   
3:19   
and um yeah um other you know the the other big news   
3:27   
uh or the big thing this week was um   
3:34   
uh brain modes in Toronto. So,   
3:39   
so brain modes 2025 and um I see   
3:47   
that like if you go to um um   
3:53   
field what is it? Um one second. Okay.   
4:00   
Um is it fields institute?   
4:06   
I think it's the um   
4:18   
Yeah. Yep. So they've got this um   
4:27   
in terms of um   
4:32   
the they've already got the talks online which is awesome.   
4:37   
Yeah. But you know I know it's a a great   
4:42   
set of mathematical you know   
4:49   
mathematical modelers. Yeah. that um that presented   
4:54   
and um so that was um and yeah the John   
5:01   
Griff is the other um incoming Neurotech   
5:07   
uh um   
5:12   
board member. Yeah. That was was an organizer for that meeting.   
5:17   
Oh, okay. Yeah. Yeah. Yeah. Um   
5:23   
um and then in France was the um was this neuro2025   
5:30   
which was like like modeling   
5:35   
multimodal MRI, you know, not not not so much um pushing   
5:42   
the kind of like spatial temporal modeling uh as much as like you know combining   
5:49   
white matter and and functional activation maps   
5:55   
combining that analysis, okay, in interesting ways, especially as it   
6:01   
relates to um   
6:06   
modeling stroke damage. So um how how your   
6:15   
like resting state connect changes with   
6:20   
with stroke damage which   
6:25   
you know is is potentially insightful in terms of just how   
6:31   
how brains are put together, right? you know like um and then you   
6:37   
know in that kind of um lesion analysis kind of way you know   
6:44   
right yeah   
6:50   
trying to think you know busy here with SF tech week which is just a marketing   
6:58   
thing for Anderson and Harowitz   
7:04   
Um yeah, but lots of lots of people doing events this week, you know, so you know,   
7:12   
thousand literally thousands of people coming through the building. Wow. Okay.   
7:17   
Yeah. Yeah. Like like I I've got pictures of, you know, people people   
7:24   
lined up around the block, you know. Yeah. Um anyway, we'll see.   
7:32   
We'll see if that translates into people becoming members, right? But uh   
7:38   
yeah, excuse me for Yeah. Um yeah, I I think that's those there   
7:45   
those um my updates. um some some very   
7:51   
interesting papers um this week in terms of um   
7:59   
um well I had a had an interesting discussion um talked with Emily Sherman   
8:08   
she um she's the DARPA arc fellow who led the   
8:16   
inspire program. So, um, inspire is   
8:24   
a very, um,   
8:29   
forced acronym. Um,   
8:35   
I'm not going to remember it. Let me sorry. Let me just   
8:43   
It's investigating how neurological systems   
8:49   
process information in reality.   
8:54   
Yeah, that's um forest. Let's just say   
9:00   
you know that that seems that seems like that's a war crime. I'm not sure if forced is strong enough. Um uh um   
9:12   
the point being um   
9:20   
is it what other mechanisms? I mean, I I thought it was interesting,   
9:25   
right? Like like this um coincides with   
9:31   
um I forget what journal. Oh, no. I think   
9:36   
it's I think it's biological cybernetics. Okay. To stay to stay on theme for today's   
9:43   
meeting. Um uh   
9:50   
the um the they're doing the 30th and I I think   
9:57   
it's the 30th or 40th um anniversary of   
10:03   
um the Terry Sowski paper paper on firing   
10:12   
rate as um you know a a as a   
10:21   
neural information processing system. Yeah. Right. Which   
10:27   
was in fact the original conference name,   
10:33   
right? Yeah. Um um   
10:40   
and and inspire was was you know, trying to find other   
10:46   
alternative mechanisms or at least, you know,   
10:54   
um I mean, and there the inspire arc   
11:00   
opportunity soliciting ideas to explore the question, are there new ways   
11:05   
um to describe how functional neural systems store and process information that expand beyond the limits of digital   
11:13   
representations, right? And um   
11:20   
which I I assume is I mean well, you know, that's still   
11:28   
there that that's that um that was the   
11:34   
um RFP and and uh and it looks like it went out   
11:41   
to you know, certainly some of the usual suspects, but definitely some   
11:48   
uh like cortical labs, you know. Yeah. For instance. Um   
11:55   
and um uh yeah the the did did we cover um I   
12:04   
mean I know um   
12:11   
we talked about the two roads diverged pathways toward harnessing intelligence   
12:17   
and neural cell cultures that has these figures   
12:24   
There's another one from the same.   
12:30   
Did we talk about the um Hey, one sec.   
12:36   
All right. Uh yeah.   
12:43   
Did we talk about this archive paper? Um one second. Sorry.   
12:52   
So, you know, in in the Brett Kagan, Brett   
12:59   
Kagan's like chief scientist for um   
13:06   
for core collabs. Okay.   
13:13   
And um they um so I I think we covered this   
13:21   
this paper which is is just Brad Kagen by himself   
13:28   
um perspective paper where I mean the the big image   
13:35   
that's important is this uh   
13:44   
I don't know if it's going to come out in the video, but but this like distinguishing organoid culture from um   
13:52   
from what he's going to call bioengineered, it's just not coming through on the uh well I I remember that figure. I   
14:00   
don't Is it this paper or another paper? I think it's another No, no, it's a different paper. I mean,   
14:05   
I I I I think we talked about this one, which was just talking about these kind   
14:10   
of like I I was I loved it because it was going over kind of like the organoid   
14:17   
path versus something that could be seen as the 3D bioprinting path,   
14:23   
right? And um sorry   
14:40   
And um the but this this one is is with um   
14:50   
so he he had a paper um at the beginning of the year. I mean,   
14:59   
I think it was it was sitting in by archive maybe before that, but um he he   
15:05   
had a paper this year that was like, you know, how to set up your synthetic   
15:12   
intelligence lab. Yeah. And it was like a tutorial tutorial paper but like detailed, you   
15:21   
know, like 60 pages plus a supplementary section, you know, with with,   
15:29   
you know, the biological equipment that you'd need, the reagents that you'd need, the kind of cell culture work, the   
15:36   
kind of, you know, every every aspect, you know. Um and and you know again in   
15:45   
my opinion as someone been searching around for this kind of information it was a absolutely needed you know um   
15:57   
it was filling a hole. Right. Right. Where like nobody really had a textbook on this   
16:05   
and and you know cell culture work in general um is also lacking a lot of   
16:13   
that. I mean in the sense that like it's done it's taught via practicum, right? And you know,   
16:21   
but it it it it means that setting up your own space is   
16:28   
is still left as this kind of like, you know, um   
16:36   
it's transmitted from from one generation to the other oral tradition   
16:42   
or something like that. Um so so   
16:48   
that was nice paper. One of the things that was funny about that paper or the the oddity to me about it was that um he   
16:58   
it had the kind of people that you'd expect like Brett Kagan and um and a guy   
17:05   
on this paper um I'm blanking on his name right now but   
17:12   
like um Muhammad uh Muhammad Mustaja Raji or something   
17:18   
like Yeah. Yeah. Yeah. Yeah. Um who's who's an engineer, right? So he's a UCSC guy.   
17:26   
Not not Kate's PI, but um but somebody she's worked with   
17:33   
for sure. Um but then there's all these Rochester Institutees technology people,   
17:42   
right? So that that was on that that's on this original tutorial paper and   
17:48   
they're all on this one too. Okay. And and   
17:53   
um it's it's interesting because it's a neuroai paper.   
18:00   
Um I mean it's definitely like like trying to focus on that. Um,   
18:07   
and I mean I can't say I'm very happy with   
18:14   
the term neuro AI, right? It's, you know, kind of a buzz word. They continue   
18:20   
I mean they're doing what I would consider neuroi but nobody else does,   
18:26   
right? And so that just makes the term confusing. Um   
18:32   
um but it's it's it's interesting because it starts to get into kind of   
18:37   
like um some of the neuromorphic like   
18:44   
um you know that because they want to talk about how to   
18:54   
use biological neural networks, you know, in   
19:00   
ML. Um, they start to at least discuss, you   
19:07   
know, the history of neuromorphic computing and and things things like   
19:12   
that, which again is like obviously have a well, not obviously, but at least in   
19:19   
implementation have a digital form, right? Even if you're um Yeah. Just just   
19:27   
that. And um so   
19:33   
again, interesting like makes a little bit more sense that that Gi Wang's group   
19:40   
um would be involved in that because when I look him up, he's like a medical   
19:45   
imaging researcher. You know, he's like um I think he he's somehow famous in the   
19:53   
kind of CT world. Anyway, but I'm sure he has a lot of   
19:59   
computational people. Um, so somewhat relevant to Emily Sherman's   
20:08   
Inspire program as well as um somewhat uh um   
20:17   
interesting for um excuse me   
20:22   
uh somewhat relevant to Josh Bongard's. So he also had another   
20:30   
um talk um this week the computational philosophy group this echalapto group.   
20:38   
Okay. and and um you know so I mean this   
20:43   
is just on the heels of excuse me um   
20:53   
okay um   
20:58   
this is on the heels of um the um   
21:08   
foresight meeting with with Michael Leaven and Josh Bungard. Okay. But uh but this computational philosophy   
21:15   
group one was was very much um   
21:21   
centered around his poly computational paper from um   
21:29   
I think 2023. So this is the um   
21:34   
talking about Josh Bong. Oh yeah, Josh Bongard. Okay. Yeah. Yeah. Josh Ber, I mean, you know,   
21:41   
it's almost like like he he was definitely going to talk about anthrobots.   
21:46   
Um, but it's not really his thing. I mean,   
21:54   
you know, he seems certainly if you go through his course   
22:00   
like he's the guy's much more, you know, simulations of of Yeah. you know, soft   
22:08   
robotics kind of and and he can relate that to Androbots.   
22:14   
But but this uh um poly computation paper is is   
22:21   
very much in the well it's it's related to some of the papers you've presented   
22:28   
on um unconventional computing you know   
22:34   
especially around kind of um um mechanical processes.   
22:41   
Okay. Yeah. Um, I I can't think of any   
22:49   
actual titles right now, but but you've definitely talked about some of these.   
22:57   
Yeah. Yeah. Um, I I can't remember which ones   
23:02   
they are, but yeah, I remember the poly computation paper and that was where they were like programming almost like   
23:09   
programmable matter kind of in that direction. Yeah. Yeah. I mean, that's definitely one of   
23:17   
the ways he was going and and and you know, he had Yeah, I mean, so it's um   
23:24   
maybe if Jess joins later, he he can say more because um Jess uh   
23:31   
when Josh had already started, Jess was like, "Oh, this sounds like he's going the the bring vehicle route."   
23:41   
and and then he totally put up pictures of free vehicles and but but actually   
23:49   
came to overlay meta materials onto um Brainberg   
23:55   
vehicles where like like it it was that that was   
24:02   
kind of his contribution. Um and where   
24:09   
the the kind of gates that he was creating could be those um   
24:17   
you know um mechanisms of of those those early vehicles, right? Um anyway,   
24:28   
it was it was it was an interesting discussion. I was kind of um I think I said in the Slack, you know, I I was   
24:36   
kind of on a deadline for somebody's   
24:41   
uh um um letter. Um but um   
24:49   
what I was interested to see was was what you know what kind of analog computing   
24:56   
examples he would bring up and especially if any of those would be   
25:04   
relevant to um um   
25:14   
brain you know, brain modeling. I mean, almost of the sorts of brain   
25:21   
modes, right? like like although they didn't they   
25:30   
they're usually doing these kind of um decompositions as opposed to like um the   
25:38   
kind of um yeah I I really wanted him to try and connect some of his work to like   
25:44   
Earl Earl Miller's work and and you know the kind of people who present at the   
25:50   
wave club. Um, do you know that seminar series? No, I've never heard of it. It's   
25:57   
wave club. So, you're you're in luck next week. The   
26:04   
wave club from this week because it's it's the first.   
26:10   
So, traditionally, I think it's like the first Wednesday   
26:15   
of the month. Okay. Or something like that. What's the 14th? No, it's a first   
26:21   
Tuesday. Must be it must be the first Tuesday of the month. Okay. And um and it's um   
26:31   
Bard Urban Trout. Oh, okay. Right. Is like so you can already get a   
26:37   
sense of like, you know, what kind of stuff it's going to be. And   
26:44   
it's mostly or it definitely has um   
26:51   
uh I mean I don't know if this is what it's it's it's set up for but it's like it's mostly um   
27:03   
you know electrofizz people who are looking at traveling waves   
27:09   
okay in the in brain activity. So   
27:14   
it was like Earl Miller, although   
27:22   
I mean Earl Miller has definitely spoken there. Um I feel like the last time Earl   
27:28   
Miller spoke though it was um who's that guy at University of Maryland like Louis   
27:33   
Poa? How do you pronounce his name? Yeah, Luis Poa I think.   
27:39   
Luis Pesoa. Yeah, like the entangled mind, entangled brain or something,   
27:44   
right? So, so he he hosted Earl Miller most recently like like that's why it   
27:51   
was on my mind or you know that that and specifically it was like Earl Miller was   
27:57   
talking about you know by having by h   
28:05   
by having a complex uh um spectrum of of   
28:10   
frequencies active that you could be doing something that that that that   
28:15   
allowed you poly computation. Okay. And and you know, and it it was also   
28:24   
it was also how they're setting it up to to   
28:33   
expand. I mean,   
28:38   
I if if the neuromorphic people, right, are making kind of like   
28:44   
um you know, leaning on these these brain   
28:50   
metaphors or you know, inspiration. Yeah. Right. like like a lot of the um uh   
28:59   
analog computing is seems to be kind of like doing the same thing but drawing   
29:04   
from quantum computing that that like like that somehow this is   
29:12   
um this is a mechanism that will actually allow a lot more parallel   
29:18   
computation, right? which you know parallel poly I   
29:24   
mean you know and and um um but I I never get enough detail you   
29:32   
know but they never go into the kind of detail that neuromorphic computing people will go into in terms of actually   
29:39   
trying to make a a simulation or you know god forbid an actual practical   
29:46   
implementation right it's it's it's It's it's more these kind   
29:52   
of um these nods towards these ideas as   
29:58   
opposed to um actually like putting together examples of them. And and to   
30:05   
some degree the Bonguard work was the same thing, but like like   
30:10   
it was like the magic was the meta materials. Yeah. was like like and then meta   
30:16   
materials you know like that'll you know like okay I you know   
30:25   
do we have any examples you know any of these you know practical uh even at a   
30:31   
even at a kind of organoid intelligence level right like you know I mean reservoir computing   
30:38   
is a thing right like you can do it with non-living matter of   
30:46   
But um anyway, along aside, I mean, but but um you   
30:55   
know, re relevant to the Emily Sherman stuff   
31:00   
or like like that DARPA program. the the the sad thing is that she's she's   
31:07   
finishing up at like her time at DARPA   
31:12   
and um you can't blame anyone for not wanting to be a part of the federal government   
31:18   
right now. Yeah. Um uh so   
31:26   
she was probably the best advocate for somebody   
31:32   
to be doing organoid intelligence, you know, I mean she she was the art fellow   
31:39   
who, you know, was going to be the closest to that.   
31:47   
Um   
31:52   
but but the the Giwang or you know this this latest Brett Kagan paper   
31:58   
tries to be um yeah tries to kind of gather   
32:04   
a lot of the references relative to neuromorphic computing. Um you know   
32:11   
algorithms that have been used by by   
32:17   
biological intelligence, synthetic intelligence people. Um and um yeah, so   
32:25   
if if we hadn't covered it, I just thought that that would be good one to to mention as you know.   
32:32   
Yeah, it's Yeah, why don't we go over that paper? Um Sure, sure. Sure. Yeah. And it's got   
32:39   
some um it's got some good figures like the other one, too. you know, it it's   
32:45   
still archive paper, but they're they're obviously planning to to to get this out   
32:51   
with the same kind of um um the same kind of development as these   
32:58   
others that they've done, which have been great. I mean, that tutorial paper again is like, you know, absolutely the   
33:06   
best reference um on the subject. Yeah, this is the paper uh a computational   
33:13   
perspective on neuroai and synthetic biological intelligence.   
33:18   
Uh and the neuroi term of course is kind of a buzzword. I mean you know we're using that as a standin for anything   
33:26   
that isn't like neural networks I guess or you know something similar. Um this   
33:32   
is on the archive from I guess this week. Um, and the authors here, Brett   
33:38   
Kagan, Gi Wang, Mohamad Must Raji, and   
33:43   
you know, a couple other people here. Um, yeah. So then, um, zoom in here.   
33:51   
So, yeah, thank you. They're they're from Cortical Labs, RPI, Santa Cruz.   
33:58   
Yeah, that's where we're we're talking. Um, so most   
34:04   
Oh, yeah. So uh neuroai is an emerging field at the intersection of neuroscience and artificial intelligence   
34:11   
where insights from brain function guide the design of intelligent systems. A central area within this field is   
34:18   
synthetic biological intelligence or SBI. So this is the organoid stuff um   
34:24   
which combines the adaptive learning properties of biological neural networks with engineered hardware and software.   
34:30   
Um, SBI systems provide a platform for modeling neural computation, developing   
34:36   
biohybrid architectures, and enabling new forms of embodied intelligence. And   
34:41   
so this is a review where they organize the neuroi landscape into three interacting domains. Hardware, software,   
34:49   
and whatwware. So this is hardware being uh silicon hardware, software being um   
34:55   
you know some programming language or some machine language and then wetware being the like organoid work and   
35:04   
potentially like brain circuits. We outline computational frameworks and   
35:09   
highlight recent advances in organoid intelligence, neuromorphic computing and   
35:15   
neurosymbolic learning. These developments collectively point towards a new class of systems that compute   
35:22   
their interactions between living neural tissue and digital algorithms. So this   
35:27   
is um you know kind of a nice uh vision for things.   
35:33   
Um so let's go through the paper. This is kind of selling neuroi as a paradigm   
35:40   
shift and how this is just kind of the way that we need to go uh combining the   
35:46   
insights of the brain with artificial intelligence. Um you know what that means of course is up to the research   
35:54   
group that's doing it. So um you know this is a multid-disciplinary effort. requires   
36:00   
people to uh think you know both in terms of biology and in computation.   
36:08   
Uh then there are all sorts of applications they always have to highlight the medical applications you   
36:13   
know therapies and and other types of cognitive aids and things like that. Uh   
36:21   
and they kind of get into you know the history of tissue culture I guess. Uh,   
36:27   
and then kind of walking through that. Um, let's see.   
36:33   
But it's Yeah. I mean, it starts with tissue culture, but it's like I mean, it's specifically about neurons.   
36:39   
Yeah. They get into Lancaster papers here. Maline Lancaster. Yeah. Yeah. But like like neurons   
36:47   
and then meas and then kind of like how to build   
36:54   
you know how to start um I mean do stem cell work and then and then organoids.   
37:02   
Um okay um and then of course computational   
37:10   
science they go through kind of some of the history of that and kind of going   
37:17   
from the early years of computation to reinforcement learning to deep learning   
37:25   
and uh other types of neuroscientific theories like global workspace theory, integrated information theory,   
37:32   
predictive coding and active inference uh and how those can be useful um in in   
37:40   
this context. And then of course I talk about neuromorphic hardware driving this kind of spiking   
37:46   
event-driven architecture of biological neurons. Okay. So here we examine the emerging   
37:52   
field of SBI and neuroi with a focus on its computational foundations. We review   
37:58   
key technological conceptual advances, algorithms and architectures that   
38:03   
connect biological and artificial forms of intelligence. By highlighting these integrative efforts, we provide a   
38:10   
comprehensive framework for the understand for understanding the current state and future directions of this   
38:16   
rapidly evolving field. So they get into biological neural networks or BNNs and   
38:23   
this is the foundation of what they want to do. They talk about the complexity of   
38:28   
single biological neurons. So, ANN's are sometimes described as brain inspired,   
38:35   
but they're extremely simple in terms of their um you know uh function and   
38:40   
operation. It's basically a unit that gives out you know spits out weights. Um   
38:46   
and that's not how actual neurons work. How actual neurons work of course is   
38:52   
much more um analog and has a lot of different parameters that you can tune.   
38:59   
They get into dendritic trees and dendritic computing. So dendritic trees act not as single summing points but as   
39:06   
distributed filter banks as shown in figure one. Each branch approximates a   
39:12   
leaky RC cable with distinct membrane resistance, axial resistance and capacitance. Synaptic inputs undergo   
39:19   
location and time dependent attenuation with distance signals arriving more   
39:25   
weekly and slowly than proximal ones. So this is a tree here that they show um   
39:30   
and they show kind of the there's a circuit at each node where they have um   
39:37   
different the different electrical parameters uh membrane resistance, axial resistance   
39:43   
and capacitance. So you're modeling this physical system within each node. Um and   
39:49   
then you're summing those together but after they've been processed. So you you   
39:56   
know this is like a dendrite where you're getting sources from different places and it's being filtered into the   
40:03   
neuron. Okay. So this just shows a dendritic branches here. Um and it's   
40:09   
just underscoring that it's not at all like an artificial neural network. It has the structure that uh is not really   
40:18   
accounted for in our typical networks. Even in something like reinforcement   
40:23   
learning, you don't really have this kind of structure. Although in biological reinforcement learning, we   
40:28   
kind of assume the structure. Um actually biological reinforcement learning is a lot about dopamine   
40:35   
signaling. So you know that there's a whole different area there. But this is kind of like you know there's of course   
40:42   
the area of dendritic computing where people are doing a lot of you know kind   
40:47   
of pioneering work in that area. um and they're kind of using the dendrite as   
40:53   
the main unit of information processing. Okay. So then there's this key   
40:59   
differences between BNN's and ANN's biological and artificial neural networks. So they their focus here is on   
41:07   
the properties for each one. Uh they they focus on training data requirements. So in BNN's we have   
41:14   
evolutionary pre-training, innate threat detection and feature extraction. So that's the way they kind   
41:21   
of state that. Um so in other words like you have things that are innate or   
41:26   
encoded in uh you know for different animals like if you have a fight orflight response that's evolutionary   
41:33   
pre-training. uh innate threat detection and feature extraction are things also that are   
41:38   
innate that uh are kind of analogous to pre-training in an artificial neural   
41:45   
network. And then of course you have large data sets in artificial neural networks. One thing they didn't point to   
41:51   
here is that biological neural networks don't require a lot of quote unquote   
41:57   
training or the training rather is not you know you don't have to learn you   
42:02   
don't have to be exposed to the environment as much as possible to learn things. I mean you get exposed in   
42:08   
development to things. We've talked about that before where you uh you know   
42:14   
development is about being exposed to uh a lot of things but also like   
42:21   
uh being focused on different things and playing with them and seeing how they behave. So it's a very different type of   
42:27   
training than like what you get in artificial neural network that works. Um so there's there's that difference too   
42:33   
but I'll put that aside for now. The second property is energy   
42:38   
efficiency. So uh biological neural networks operate on a few watts of glucose   
42:45   
and artificial neural networks have high computational resource consumption. So this is like where we have our huge data   
42:53   
centers that require a lot of energy versus like a human brain that requires   
42:58   
uh basically food and water. Um and then you know that's that's enough uh energy   
43:05   
to produce uh you know what the brain does. Then the third point is intraet network   
43:12   
communication. So this is where we have um the focus on   
43:18   
synapses complex biochemical interactions at synapses. you get all sorts of signaling at synapses as   
43:25   
opposed to artificial neural networks where we have simple mathematical operations such as addition and   
43:31   
convolution. So you know in the biological brain you have these uh you   
43:38   
know biochemical signals you have um binding to receptors things like that in   
43:45   
Ann's the you know and then you can maybe characterize those with mathematical operations in artificial   
43:51   
neural networks they're basically you know the operations are the entire   
43:57   
sort of interaction between neurons so it's all some you know it's all kind of condensed sense to into in addition or   
44:04   
convolution or multiplication or something like that.   
44:09   
Uh the learning mechanisms um in biological neural networks we have self-organization,   
44:15   
synaptic plasticity and predictive coding. In artificial neural networks we have   
44:22   
gradientbased back propagation. So this is I mean that's one I mean they're pro well this is kind of the   
44:29   
example to use from artificial neural networks. The idea being is that artificial neural networks are   
44:36   
optimized. They follow a gradient uh to learn things. in biological neural   
44:43   
networks they you know basically learning is um I don't know if there's a   
44:48   
gradient um people often refer to learning gradients but they're kind of informal structures and really the focus   
44:55   
is on like synaptic plasticity um the predictive nature of um the brain   
45:03   
and then self-organization of networks. So it's a very different   
45:08   
sort of paradigm there. Um and so uh   
45:14   
then the next one is systems architecture. So that's biological neurons with integrated storage and   
45:19   
computation. And then in artificial neural networks we have siliconbased transistors,   
45:26   
bonoyman architectures which would separate memory and processing into two components. Whereas in biological   
45:33   
networks, you know, those things aren't necessarily separated or if they are,   
45:38   
they're in a network that interacts with each other. So, it's a very different architecture.   
45:44   
Emergent properties is the next property. And this is where we have uh in biological neural networks   
45:50   
spontaneous oscillations, criticality, wave propagation, and   
45:56   
homeostatic balance. uh and then in artificial neural networks hierarchical feature   
46:02   
representations and attractor dynamics. Okay. And then the last one is   
46:07   
resilience to damage which is in biological neural networks dynamic   
46:12   
rewiring and homeostatic plasticity allowing for partial recovery. So this is where if you have damage to the   
46:19   
system uh how does it get uh fixed or recovered? And of course this is   
46:24   
something that uh the brain is well known for in terms of plasticity but we   
46:30   
have this sort of uh we're interested in how the network rewires itself. So this   
46:35   
is a function a famous function of biological neural networks and then in artificial neural networks we have   
46:42   
static redundancy things like dropout and limited on the-fly recovery.   
46:48   
So yeah, I would also add in in terms of resilience to damage that there's also redundancy in the biological neural   
46:55   
network and you know that's that also plays a role in recovering information   
47:02   
but there you know and then there connections between these like uh emergent properties. This this area is   
47:08   
really interesting but it it speaks to a lot of the other areas as well. And so,   
47:15   
um, I like this table, but you know, I mean, you could probably keep revising it in terms of different properties and,   
47:24   
you know, uh, differences that you can think of. Uh, but I think the take-home message here is that biological neural   
47:30   
networks do things a lot differently than artificial neural networks. And you know we we can learn we can learn a lot   
47:38   
from biological neural networks in a way that kind of gives us different paradigms of artificial neural networks   
47:45   
at least in terms of that you know they're they're sort of you know even if we had something like a an organoid   
47:51   
culture or an organoid intelligence that it's artificial in the sense that it's   
47:57   
been sort of cultured and curated by human experimenters but it's still   
48:04   
artificial in the sense that it's doing some you know it's not like the actual biological system but it looks very   
48:09   
different from the artificial neural networks we use today.   
48:14   
I I liked that. Um or you know it's I'm just seeing that in an emergent   
48:22   
properties. Oh yeah. Begs um 2008   
48:27   
um 2022 and um this is the   
48:34   
um Indiana professor. Yeah. Yeah. Who replicated the mind in vitro. Right.   
48:44   
So the the UI open micro electrode array   
48:51   
project his postto is the one that like they end   
48:57   
the paper with like you know a postoc was able to build our system in 15 hours   
49:05   
and you know do you know get his own thing running in in Indiana and it's   
49:12   
It's um pegs. Um right. So it it Yeah. Yeah. Just like that.   
49:20   
Yeah. He's done this stuff with with uh like brain criticality for years like   
49:26   
you know thinking about how that happen. Yeah. Thinking about that happen. Absolutely. So yeah that and I would you know   
49:33   
emergent properties I might add like you know it's kind of the brain comp or neural complexity or brain complexity.   
49:40   
So you know you have all sorts of interesting properties of oscillations and coupled oscillators and things like   
49:46   
that. Uh and that that provides like these very complex dynamics that we   
49:52   
don't see in artificial neural networks at all. I mean you know sometimes the the uh dynamics are sort of the   
49:59   
information processing uh but you know it's like kind of yeah that's not going to be captured in an   
50:05   
artificial neural network. Um yeah so yeah.   
50:10   
Uh yeah. I mean we we'll we can come back to this table too. I mean I think we should collect all these figures and   
50:16   
tables and Yeah. Yeah. Yeah. Yeah. Okay. So   
50:22   
and I know exactly what talk what week that was that we talked about that other paper with the figure that you showed.   
50:28   
It was when we were talking about biorinting and Yeah. Yeah. So I'll go back to that.   
50:34   
Yeah. Yeah. He's gonna have a little bit on that too, but yeah. Okay.   
50:40   
Um, so yeah, then there the properties of functional biological neural networks. So, you know, we're thinking   
50:48   
about what are the key features that we need for functional learning capable biological neural networks. Thinking   
50:55   
back to like if we were going to um sort of extract some design principles out of   
51:01   
the brain, how do we do that? So the first is neuronal diversity and that is   
51:06   
brain function relies on the interplay between diverse neuron types including excitatory parameal cells and inhibitory   
51:14   
inter neurons which regulate network dynamics and plasticity. And so that's   
51:20   
um you know again where in artificial neural networks you have one unit type   
51:27   
and we usually don't have different types of neurons because we don't deal with like things like um you know   
51:33   
different types of ion channels being expressed in the neurons or different types of neuromorphologies.   
51:40   
We just have the unit and then the unit has you know connections with other units and then they're governed by   
51:46   
weights and that's it. So that's one design principle. The next   
51:53   
is modular and hierarchical organization. So uh you know there's this idea that   
51:59   
neural circuits are organized hierarchically to produce sensory motor information and execute complex   
52:06   
behaviors. Uh engineered biological neural networks do not fully replicate this   
52:11   
architecture. If you look at assemblid or conetoid approaches, they aim to capture key   
52:17   
aspects of modular connectivity, but they don't quite get to the level of uh a mature neural circuit or a material   
52:24   
maybe neural net neuronal network, which of course may be many circuits combined   
52:30   
into one functional unit. So you know if you're thinking about like a network for   
52:35   
learning and memory or a network for attention or a network for   
52:40   
um you know just doing something like addition or you know mathematical   
52:46   
computations um you may need to have different tissues or different brain regions that   
52:53   
are hierarchically connected. So you know in your typical assembly you have a bunch of cell types smooshed together   
53:00   
and then they form kind of this functional segregation but you know the organization of course is not going to   
53:07   
be the same as you see in a biological neural network or a mature one in any   
53:13   
case. Um so this is you know again end of a reach goal at this point but this   
53:19   
is like the one big difference between uh BNN's and ANNS.   
53:25   
Uh the next design principle is long range communication and critical dynamics. So that's where we have um   
53:32   
these oscillations like gamma, theta and beta. And this   
53:38   
these these oscill uh these these frequency bands support interreional coordination of memory, attention and   
53:44   
motor control. And then if you're thinking about the dynamics of them,   
53:49   
you're thinking about criticality in the brain, balancing, stability and   
53:54   
adaptability. So there are all these like meta uh meta features of the brain   
54:01   
you know different phenomena that are kind of uh beyond sort of the single   
54:07   
cell or even the population analysis. It's you know things in the dynamics   
54:12   
that we would like to capture for a network um such as what we're trying to   
54:17   
do with biological inspiration. Then our final uh design principle is   
54:26   
parallel distributed computation. And of course there's this uh sort of   
54:31   
area of ANN research that was big in the 80s 90s you know parallel distributed   
54:39   
processing and that's you know kind of discovering like parallelism and   
54:44   
computation and in in computational neuroscience and that but   
54:51   
this is actually kind of thinking about how the brain really takes advantage of   
54:56   
this design principle. So the brain's billions of neurons and trillions of synapses support massively parallel   
55:03   
processing. We're talking about at that scale, you know. So we're talking about a massive scale and being able to build   
55:10   
systems that operate at that scale, but also being able to control systems that operate at that scale. While modern   
55:18   
computer architecture such as graphical processing units or GPUs enable parallelization in artificial neural   
55:25   
networks, biological neural networks are still far exceed them in connectivity and energy efficiency. So there's this   
55:32   
connection between or at least this thinking that the parallel parallel   
55:38   
nature of biological neural networks the distributed nature of biological neural   
55:43   
networks allow them to achieve these gains that are so far elusive to   
55:48   
artificial neural networks. So you know energy efficiency being a primary example but also connectivity and sort   
55:56   
of you know we talk about these things it's sort of like magical. It's like how does the brain do so much with so little   
56:03   
energy or you know there must be some added stuff in the connectivity or   
56:08   
something and we're trying to find like what those things are so we can implement them in some sort of um you   
56:16   
model or device and so that's what they're getting at with these design principles   
56:21   
and again you know there probably other design principles but these are the ones they're identifying.   
56:28   
Um then they're mapping out this neuroai spectrum. Next um just thinking about   
56:33   
all the things going on in the field. Um you know this is an interdisciplinary   
56:38   
landscape. Um we have these three domains hardware   
56:43   
software and wetwware. And um you know hardware of course are things like   
56:49   
neuromorphic chips or spike based silicon systems. The software are computational models   
56:56   
inspired by brain function. Those could be neurosymbolic AI or reinforcement learning. And then wetwware are these   
57:03   
living biological neural systems like organoids, cultures or brain slices.   
57:09   
And so you combine these into this um these domains.   
57:15   
So um they also do this categorization of neuroi fields and they categorize uh   
57:23   
categorize SBI um or SBI related neuro AI into two   
57:29   
broad classes. Um the first is that fields do that do not involve living neuronal cells. These   
57:37   
are um sort of you know the sort of uh   
57:42   
hardware implementations of these kind of biologically inspired systems. So these areas leverage the   
57:49   
morphology physiology and computational principles of biological neural networks   
57:55   
to develop brain inspired hardware and algorithms. Okay. So this is uh actually   
58:02   
this this is actually figure two a graph representation of the different fields. We'll get into that in a minute but   
58:08   
let's continue with this point one. And so that the point one splits between   
58:15   
neuromorphic computing and neuroinspired learning. So neuromorphic computing is a   
58:20   
hardware implementation that moves us away from vonoyman architectures towards things that are   
58:26   
more um biological inspired. So vonoyman architecture of course separates out   
58:32   
memory and processing um for very practical reasons. Uh but that's not   
58:37   
really maybe the way we want to build devices that are inspired by the brain because that's not really the way the   
58:43   
brain works. And so you can build these neuromorphic devices that are much   
58:49   
different than the nonolment architecture. And then neuroinspired learning which is where we have   
58:56   
different types of algorithms and software that are inspired by the brain.   
59:02   
They're not at all like the kinds of algorithms that we have for vonoyman architectures. If you know anything   
59:09   
about how to you know the different types of algorithmic challenges we have for uh you know like parallel computing   
59:17   
and for quantum computing you know that like the algorithms for those paradigms   
59:23   
look very different than sort of the serial vonman architecture algorithms that we may   
59:30   
learn in like uh our computer science classes or something like that. So if we have like a you know we have a certain   
59:38   
algor a search algorithm that we build um for a serial vonoyman architecture if   
59:44   
we want to parallelize that it's going to look different and if we put that on a quantum computer it looks different   
59:50   
still so there are a lot of these neuro inpired uh algorithmic opportunities to   
59:57   
um you know build new algorithms build new sort of computational tools.   
1:00:04   
So the second part of this um categorization so there was fields that do not involve living neural cells and   
1:00:10   
then two are fields that involve living neural cells. So this is where we want   
1:00:16   
to kind of leverage the efficiency and adaptability of brain neural networks   
1:00:22   
um and integrate biological neurons with digital systems. So this of course is   
1:00:28   
organoid intelligence and bioengineered intelligence. And so this is where you   
1:00:33   
know you're using organoids or some sort of culture of uh cell culture to build   
1:00:39   
these systems that can process information and do this in a way that's similar to what you know uh uh in in   
1:00:47   
vivo neurov system does. So um you know sometimes people are using brain slices   
1:00:53   
for this u but other you know there times they're using neural cultures. uh these BNNs can be integrated with   
1:01:00   
computers to develop effective brain computer interface systems. So that   
1:01:05   
those are the distinctions there. Yeah. No, just just just this is my my   
1:01:12   
issue with BCI as a term. I mean you know um it is interesting   
1:01:19   
right that the the minded vitra group has has another section on you know I   
1:01:26   
mean they they first and foremost talk about culturing neurons   
1:01:34   
right and and again like okay so the   
1:01:39   
easiest thing to do is 2D um the organoids became this new   
1:01:46   
platform because the the neurons um would self assemble I mean with with   
1:01:54   
certain cues and um and that that   
1:02:01   
yeah that added this whole new layer of complexity um   
1:02:06   
slicing of I mean taking a brain slice uh um and you know trying to keep it   
1:02:14   
live um is definitely another alternative.   
1:02:20   
There there's a there's a longer discussion that relates to some yeah or   
1:02:26   
organoid intelligence and brain computer interfaces. Um,   
1:02:31   
you know, this this is not getting us any closer to putting um   
1:02:38   
either putting organoids into brains or um   
1:02:43   
um decoding, you know, it's it's this isn't   
1:02:50   
decoding a living brain either, right? But um these are these are my issues   
1:02:55   
that I need to work through. Yeah. But I I I love this graph. Yeah. So this is figure two. Yeah.   
1:03:04   
This this is this is cool. And you know I I've never thought about representing   
1:03:11   
it this way, but it really you know it it it captures well the the um   
1:03:21   
yeah the the the complex relationships. Yeah. So this is where we have synthetic   
1:03:27   
biology, cell and tissue engineering, neuroscience, computational biology and   
1:03:32   
so these are all the fields that kind of go into this enterprise. Then all the kind of the tools that we have here uh   
1:03:40   
neuro neural tissue culture, tissue culture, computational modeling,   
1:03:45   
cognitive and systems neuroscience, machine learning and then you know the next level are these kind of different   
1:03:53   
approaches, neuro tissue modeling, neuromorphic computing. Then you also have reservoir computing and feedback   
1:04:00   
driven learning. Um, and then synthetic biological intelligence and neuro digital twin model and then neuroi.   
1:04:07   
I've got there's a a lot of lot of acronyms to learn here. Yeah,   
1:04:14   
they're trying to define them for us, but as you go down, they start using   
1:04:21   
their new acronyms. Yeah. So, where did that come from?   
1:04:27   
Additional acronyms. Uh, okay. All right.   
1:04:33   
So, let's Yeah, let's kind of move down the paper. Um, yeah, they kind of talk about the   
1:04:39   
hardware. Oh, go ahead. Well, just just that like like again my   
1:04:46   
my only real issue with this paper is that this isn't what neuroi means to   
1:04:52   
most people. Yeah. It's it's very uh cultivated for their own It it it's it's very, you   
1:05:00   
know, I can see I can see why Brett Kagan thinks this is what Nuri.   
1:05:07   
Yeah. Um but when you see all the other Ner AI papers or like discussion or you know   
1:05:15   
the the what's the Montreal AI well that's that   
1:05:23   
is AI neuroscience. I don't know. You know, you look at the Patrick Manow   
1:05:29   
neuro AI for AI safety paper and honestly Patrick's probably the most   
1:05:34   
biological of them. But in general, they're they're more just brain inspired AI, you know, it's   
1:05:42   
like, you know, thinking about Transformers is the   
1:05:48   
hippocampus or something like that. Yeah. Yeah. Yeah, I think there's definitely they they kind of kind of cultivate this   
1:05:55   
for their own purposes here that Yeah. Yeah. Yeah. This is uh this is this is my issue. I'm jealous of   
1:06:03   
all this work. Oh yeah, it's great work. Yeah. This is an illustration of a neuromorphic architecture. So this just   
1:06:10   
kind of shows how this is organized without kind of it's very different underscoring how   
1:06:17   
it's very different from an endn that we use today. Um then they have you know   
1:06:22   
this idea of offchip and onchip learning. This is deep in the weeds of neuromorphic architectures.   
1:06:29   
Um then we have of course neuroinspired learning which are the software models. Um and then this is where we have   
1:06:35   
neurosymbolic AI and agentic AI. So this difference between sort of a neuros   
1:06:40   
symbolic approach where you take symbolic reasoning and combine it with sub symbolic learning which is what we   
1:06:47   
use in deep learning or other types of uh you know computer vision but then we   
1:06:53   
also add symbolic reasoning on top of that. Um and so the idea is you can   
1:06:58   
build structured knowledge and um you know it's basically combining the best   
1:07:04   
of both worlds in terms of like uh goi versus like the more recent uh norvigian   
1:07:11   
approach to uh AI which is data driven. Um and then you know kind of talking   
1:07:19   
about neuros symbolic AI and some of the ways people do that. Um, this just shows neurosymbolic AI as kind of a model. Um,   
1:07:29   
and then let's see they get into the let's see   
1:07:35   
um they were talking about Yeah, they were talking about agentic AI   
1:07:41   
and agentic AI they don't really talk about that a lot. They talk about it here kind of at the end. Neuros symbolic   
1:07:49   
agents can be made to autonomously interact with their environment, update their internal knowledge representations   
1:07:55   
and adapt rules through active learning mechanisms. And so this is where they bring up active inference as being kind   
1:08:02   
of the way in which agents behave and kind of don't talk about it very much.   
1:08:08   
Uh but then they get into reinforcement more. Yeah. Yeah. So then they get into reinforcement learning and active   
1:08:15   
inference where they kind of go through reinforcement learning and how that works. Um and then kind of contrasting   
1:08:23   
that with uh reinforcement learning and active inference as sort of two ways to   
1:08:29   
different ways to do this. Although you know there are sort of ways that you can combine them as well. It's just that   
1:08:37   
active inference is really about sort of it's um where you're using this measure   
1:08:43   
of surprise and you're using that to minimize, you know, you're basically minimizing   
1:08:49   
surprise and that gives you your kind of uh optimal sort of behavior or your   
1:08:55   
adaptive behavior. You were going to say something. Well, just just to that to that point,   
1:09:02   
right? like like they I mean one it should be said that Brett   
1:09:11   
Kagan has papers with Carl Fen. Oh yeah. And and so it's just like   
1:09:22   
they're trying to make it sound like, you know, active inference is really adding this   
1:09:29   
brand new thing. Um, and that that reinforcement learning   
1:09:35   
like needs to have this like exploration kind of shoehorned in or something like   
1:09:42   
like I forget the way they put it like um   
1:09:47   
bolted on or something something like that like you know um   
1:09:54   
uh I'm not I'm not seeing it exactly but Um   
1:10:02   
um it's this it's this paragraph right before acting. Anyway, but like you know   
1:10:12   
they Ryan Smith does the um   
1:10:19   
tutorial like like I forget what his paper is called but it's like tutorial on active inference, you I mean like   
1:10:27   
he's a total active inference guy, right? Yeah. Like and and um   
1:10:33   
uh next week there's the   
1:10:39   
what's it called? International active inference. Yeah. IWI   
1:10:45   
workshop. Yeah. Yeah, it's a workshop on like Ryan Smith is is like keynote, you   
1:10:52   
know, doing doing his tutorial thing and you know he's the one who's just like   
1:10:59   
you know active inference becomes reinforcement learning   
1:11:05   
right like you know in many cases that like it collapses to   
1:11:12   
reinforcement learning Yeah.   
1:11:19   
Yeah. I mean, again, Yeah. It's it's there are a lot of parallels. Yeah.   
1:11:25   
You get the Yeah. Yeah. And I love their um I love their figures.   
1:11:32   
Yeah. Or, you know, like like So, it's it's fine. I mean, you know, like like again,   
1:11:39   
like um they're definitely trying to get it like how the active inference model   
1:11:45   
as described here is is adding something right and it's   
1:11:53   
kind of I mean I wouldn't contrast them and I wouldn't necessarily say it's because reinforcement learning you're   
1:12:00   
trying to sort of you know it isn't just about like policies and selecting policies it's really about the sort of   
1:12:06   
adaptive behavior you're trying to find the optimal policy and active inference you're trying to minimize the surprise   
1:12:13   
and you have this uh you know you do have this sort of joint distribution that you're trying to uh you know   
1:12:22   
understand. Yeah. So that's that's but they're both kind of very similar and   
1:12:27   
the structure is very similar in that respect. Um I'm gonna when we do our presentations to um the   
1:12:36   
active inference symposium, you know, I've kind of been summarizing what we've been doing with open source   
1:12:42   
sustainability and that's one of the themes that we have is that we have this sort we've done a lot of work on   
1:12:47   
reinforcement learning. We've done some work in active inference. There's this kind of common theme there. emerging   
1:12:53   
which is that you're kind of using these models to get at some very deep kind of   
1:13:00   
uh social coordination problems and you know how do they kind of get at that in the same way or you know what is the   
1:13:08   
structure of these social coordination problems it's interesting I'll have we'll we'll we'll have to go over it   
1:13:14   
maybe next week or week after but yeah it's definitely   
1:13:20   
if you think about like what they're trying to achieve you're basically converging on the same thing.   
1:13:27   
Yeah. Yeah. It would be it'd be interesting to see   
1:13:34   
um   
1:13:39   
it'd be interesting to expand the the current projects with with a more active   
1:13:44   
inference model. Yeah. Well, uh, Brian Mccorco was doing that. Um, and he did like with it was   
1:13:52   
like social active inference. And you know, we think of active inference as being a brain, but you could do it   
1:13:57   
easily with a different agents, multi- aent kind of active inference, and that's kind of a whole another can of   
1:14:04   
worms. But yeah, we should develop that more. Um, I I'm not sure who it is at at   
1:14:11   
the active inference institute. I think that would probably be a good place to go for people. see people are interested   
1:14:16   
in working on problems like working that out more. Yeah.   
1:14:23   
Yeah. And and well the the other Yeah. Um as well as like putting something in   
1:14:29   
the um um I forget what Daniel Friedman has. Um   
1:14:39   
he has a particular name for it, but you can you can definitely advertise projects. Oh yeah. Yeah.   
1:14:47   
With with his Yeah. He just did that quarterly round table.   
1:14:53   
Oh yeah. Yeah. Where he he talked about a lot of the opportunities to get to to get involved   
1:15:00   
or propose things. Yeah. So definitely we should keep that in mind.   
1:15:07   
Um so yeah let's let's finish this paper up. So we have a diagram for   
1:15:12   
reinforcement learning. We have a diagram for active inference over two   
1:15:18   
time steps. Um and then you know we're kind of getting into   
1:15:24   
this table with the differences between reinforcement learning and active inference just like for different   
1:15:31   
aspects. um you know I don't I don't know if that's necessarily a key to   
1:15:36   
understanding the other part of the paper which is like we have all these different neuro   
1:15:43   
AI architectures because there are other options besides reinforcement learning and active inference like you know those   
1:15:50   
are two methods there may be other methods that you could employ here like or imply that you know that you could   
1:15:58   
apply that would be relevant as well. So this is kind of like   
1:16:03   
two I guess you could say that reinforcement learning and active inference are based on neural activity   
1:16:09   
but it's a little bit shady to say that but anyways yeah I I I mean I kind of   
1:16:15   
see why they're getting a uh they're taking this kind of route but um anyways   
1:16:22   
so this and then they get into open loop and closed loop learning which is like where you have uh this uh   
1:16:31   
contrast between reservoir computing and feedback based learning. So reservoir computing of course is where you have   
1:16:38   
this highdimensional dynamical system. You have these u these nodes in a   
1:16:44   
container and they kind of find their own wiring through um this sort of   
1:16:51   
different this readout layer that maps neural activity to desired outputs. So   
1:16:58   
basically trains the network in a different way than what we see in typical neural networks. Um and you know   
1:17:05   
reservoir computing is very hot right now. You know people are able to do different types of computational things   
1:17:12   
like pattern recognition, line source separation and time series predictions.   
1:17:18   
These are you know problems that are kind of interesting to um   
1:17:24   
uh you know as kind of benchmarks. um not necessarily for like uh being   
1:17:30   
like doing things like the brain does them, but that's you know uh reservoir   
1:17:35   
systems u are often assumed to have fixed weights. Biological neurons exhibit synaptic plasticity may   
1:17:43   
self-organized based on input driven plastic changes. So these are all kind of this is one approach reservoir   
1:17:49   
computing and then the other approach is feedback based learning which is where   
1:17:54   
you have closed loop systems that continuously adapt neural activity to real-time feedback. External stimulation   
1:18:02   
is used to reinforce or inhibit specific network patterns. So just having that contrast between reservoir competing   
1:18:09   
feedback based um and then of course the modular architectures getting into assemblids   
1:18:15   
and contoids. So the assemblids are where you have different types of   
1:18:22   
tissues kind of in the same culture. Uh contoids I imagine are things that like   
1:18:28   
uh building contos in a in culture.   
1:18:33   
They have so many terms for that. Um it's like you know they have so many terms for different types of organoid.   
1:18:40   
Um yeah so like they they they define here.   
1:18:45   
Go ahead. Sorry. Well, just like like   
1:18:55   
Yeah, it it it's it makes more sense   
1:19:03   
for you know, I get I get why the assemblid people are doing assemblies,   
1:19:09   
right? Because they they care about brain science. Yeah. Right.   
1:19:15   
um describing assemblids and conactoids as   
1:19:20   
if they're uh   
1:19:26   
what's what's the what's this term? Modular architectures.   
1:19:32   
Yeah. Like modular biological neural network architectures. Like   
1:19:37   
Yeah. It's not really the same thing. No. No. You know, it's like Yeah. And   
1:19:45   
and you know what what happened to what happened to like I mean again like I'm   
1:19:51   
not necessarily saying they should push this but like you know what about um   
1:20:00   
who's the pal Jeff Hawkins you know like um Oh brains yeah hierarchical temporal   
1:20:08   
modeling. Yeah. Yeah. you know, like like I mean   
1:20:15   
Yeah, I know. They they kind of ignore that in this whole   
1:20:22   
it's it's it's a review of of things. I mean, you know, like uh do they have a   
1:20:28   
beef or something? I don't know. Yeah. It's like that's but   
1:20:34   
but just in in terms of the um cortical column. Right. Right. That would be a logical   
1:20:40   
thing to organizational principle, right? Bring up a critical go once.   
1:20:50   
Yeah. Yeah. Yeah. I know. Doesn't that seem like a glaring emission? It does seem It does seem like they're   
1:20:56   
cherry picked for like kind of going in a certain direction. Totally. Totally.   
1:21:02   
Yeah. I mean and and and this idea of like like I mean as well as like this   
1:21:08   
isn't even cherrypicking like contoids versus assemblids and it it has to do   
1:21:13   
with with the the engineering you know like   
1:21:20   
like you know using what is it I mean one I've never seen the term   
1:21:27   
yeah that's a new one I I've seen assemblids that are using   
1:21:32   
microch links instead of fusing. Yeah. You know,   
1:21:38   
yeah. Yeah. Yeah. Well, let's see. They define assemblids as fused organoids. So, region specific   
1:21:45   
organoids are grown separately and then physically fused together. This is where you get these different   
1:21:51   
Yeah. Yeah. Yeah. I'm still not exactly sure that's how like Pasca's group or   
1:21:56   
No. Yeah. Yeah. The idea is that you have like you know these different   
1:22:03   
tissues that are going to form and then you have migration circuit formation and interreional signaling.   
1:22:09   
So you're just basically putting together a brain from like you know Frankenstein's monster brain or   
1:22:15   
something you know. Right. Right. Right. Um I mean it but you know when when Pasco   
1:22:20   
is doing it right or Nobles is doing it they're they're like   
1:22:26   
you know doing uh a   
1:22:32   
you know a subcortical organoid a cortical organoid you know a cortical   
1:22:37   
organoid that that represent I mean a subcortical organoid that represents this thing like that where now I've put   
1:22:44   
together you know this this limbic circuit because I want to do a   
1:22:51   
Parkinson's like model or something like that, right? Yeah. And um Yeah. Anyway, like again like I'm   
1:23:00   
not sure why I'm picking on this. Yeah, I know. Um but there is some there is some you know   
1:23:08   
like like like like it's an archive paper. It's obviously not done, you   
1:23:14   
know. Uh uh   
1:23:19   
but it does it does strike me as a little bit like the the uh because he   
1:23:26   
was on these papers too. The organoid intelligence paper that that had you know Thomas Harding   
1:23:33   
and Lena Smnova. Um, it kind of did the same kind of thing like it was like it   
1:23:41   
was it was trying really hard to like be defining a new field, right?   
1:23:48   
You know, you know, like like we we gota we gota we gota you   
1:23:55   
know define our terms. Yeah. So when they say contoids they   
1:24:00   
mean microch organoids. That means that the individual organoids are maintained   
1:24:05   
in separate micro micrfluidic chambers and then connected through microchs. So   
1:24:10   
they're not really physically together. They're in this in this uh uh flow set   
1:24:16   
of flow chambers where you know you have basically you can control the growth of each but they have access to one   
1:24:23   
another. Um, so it's really kind of uh a limited physiological relevance but   
1:24:30   
allows you to control the system more directly. So that's just kind of the difference. And again, you know, these   
1:24:36   
are like different, you know, I mean different methods basically and you'd   
1:24:42   
never see that in a real brain. So it's like I don't know if there's necessarily a point to this distinction.   
1:24:50   
All right. So I think that's enough for that paper, but that's a great paper. Thank you, Morgan, for bringing it up   
1:24:56   
and having a discussion around that. Yeah, they've got they've got great um   
1:25:03   
you know, I mean, I I think some of their figures are really   
1:25:08   
uh really helpful and   
1:25:14   
um yeah, you know, like like as much as I am picking on   
1:25:20   
some of their terminology, their their organization of   
1:25:28   
you know the kind of multid-disiplinary nature of the work is is is really yeah   
1:25:36   
helpful and and um I think um   
1:25:42   
informative. Yeah. I I   
1:25:49   
you know A and it's very much from a couple people that were are like   
1:25:55   
intimately involved in this. Right. Right. So,   
1:26:00   
um, we can we can dig around and find what   
1:26:05   
the the beef is with them and Hawkins,   
1:26:11   
but there is some more stuff that that just goes on that's like super relevant   
1:26:18   
for for the dish brain kind of work. Yeah. and and the um not I mean you know   
1:26:25   
the the the kind of the standard formats and stuff like that   
1:26:31   
that stuff that they've they've brought up before try to make it look more like a field. But um um   
1:26:40   
but there is a nice section on the the recent advances and application section   
1:26:46   
10 that's that's nice because they go over you know basically everybody that   
1:26:53   
we've talked about you know final spark you know brain engineers Indiana   
1:26:59   
um UIU mind in vitro um you know and and uh and a few others   
1:27:07   
that that um is cool to to be looking up, you know.   
1:27:13   
And then um yeah, and um and then some   
1:27:21   
like like just like their tutorial paper, they've got a great supplementary   
1:27:26   
section. So, I I'm I'm hoping that this will be, you know, like this will come out next year and it'll be like twice as   
1:27:33   
big and, you know, um really really being kind of like the defining,   
1:27:41   
you know, is like what I'll be pointing students at. Okay.   
1:27:46   
Yeah, it's cool. So, why don't we move on here? Uh so, yeah, Jesse, how are you?   
1:28:01   
Hi. Um, I'm okay. I've been I've been busy. I've   
1:28:07   
been sick. I've been dealing with stuff. So, apologies for being a little bit um   
1:28:12   
not here as usual. Um, but I'm all right. I'm I'm pushing   
1:28:17   
some things forward and I have some opportunities that I'm I'm waiting to   
1:28:24   
hear back from about certain things. Um   
1:28:29   
I kind of missed some of the stars today's meeting and I   
1:28:35   
know you I know you put some papers on research gate and stuff too or like updated some things. So um I I   
1:28:43   
appreciate that. I have to go back and I'm sure you talked about that. I think you said last week or something. So,   
1:28:49   
um I I've yet to fully get into that, but that's something I'm going to try to   
1:28:55   
do uh very soon. Uh, in terms of some general news and   
1:29:02   
things like that, uh, I guess it's quote unquote Boston   
1:29:09   
longevity week starts next week and I'll be doing some things with that.   
1:29:16   
uh including a hackathon of sorts where I will be a a   
1:29:24   
mentor judge type person   
1:29:29   
and it's cool because it's it's it's going to have um   
1:29:34   
it'll be based here in Boston uh at MIT   
1:29:39   
and it should have I don't know if Lean himself will be there but someone from   
1:29:45   
Leven's lab um and a number of other folks in kind of   
1:29:52   
the community at Picolapto stuff. You have   
1:29:58   
um Elon and uh will I don't know if they're going to   
1:30:04   
be directly part of it or not. Um but Andre is from the quality research   
1:30:09   
institute a sort of you know it it this this going to be a different kind of a   
1:30:14   
hackathon but they're very much trying to push they're trying to really um be   
1:30:20   
rigorous but also like you know kind of kind of address some of the the   
1:30:27   
different kind of spaces that they want to do and that's all interesting but I'm also   
1:30:33   
interested in it because of Um,   
1:30:39   
I think there's a little bit of some good emphasis on trying to do some synthetic time at the end of the   
1:30:46   
hackathon and that's what I wrote about in the Slack. sort of basically,   
1:30:51   
you know, I've talked for a long time about like doing research differently sort of hashtag banner of that and I'm   
1:30:59   
I'm thinking a lot about how to run events or conferences or academic   
1:31:05   
happenings to incorporate more of that. I've actually I've had a conversation yesterday specifically about um   
1:31:16   
the concept of a hackathon and and sort of what what alternatives or what   
1:31:25   
you know thinking a little bit about and this this is separate from the the event or even Boston which is like something   
1:31:31   
that's particularly in my mind yesterday into this into today is   
1:31:39   
hackathons are very good for doing very specific things. Um, and then you have sort of like the classic quote of, you   
1:31:47   
know, like I think it was Steve Jobs or somebody in the Apple camp saying like, "Oh, I hate consultants because you   
1:31:52   
don't stay with what you're developing for a longer period of time. You don't you just sort of do the thing and you   
1:31:58   
don't you don't stay with it or you you add a commentary and you're not attached to its results." And so I've been   
1:32:04   
thinking like what is this alternate or what are alternates and then that's a   
1:32:10   
whole other thing that that I've been doing with the future center but what what in terms of   
1:32:17   
a hackathon like what are strengths and weaknesses and what is what are his blind spots and what what are ways that   
1:32:23   
you could potentially create other events around around that   
1:32:31   
or or augment things so that you know the the inherent properties of   
1:32:37   
what you what what you're trying to do or build might be different. So that's sort of a a the last point is like the   
1:32:44   
most tangental of everything. But suffice to say um it's going to be a very busy um   
1:32:52   
you know two weeks ahead. It's been a very slow week or two for me otherwise. So I'm kind of gone before the storm   
1:33:00   
right now. But even that's fading away as things pick up. Um,   
1:33:07   
so that's that's a very light overview, but any um questions or comments so far?   
1:33:16   
Well, sounds good though. I mean, you know, got a lot of stuff going on. And   
1:33:22   
um, yeah, I did cover, you know, some things are kind of coming out now. So,   
1:33:28   
um the last um I gave an update I think week ago on the YouTube channel and you   
1:33:37   
can see more about some of those things on that in that report. So, um you know,   
1:33:43   
it's a couple things coming out on research gate as preprints that we've   
1:33:48   
been kind of sitting on. Um so, take a look at that. Um so, yeah.   
1:33:57   
And then we have of course our active inference symposium coming up in November that's going to have um some   
1:34:05   
materials coming out of that. Um and then you know we have kind of the end of   
1:34:11   
the year after that. Um and so I I don't know what people want to   
1:34:17   
you know kind of think about for um you know the upcoming year. I mean, I   
1:34:23   
know it's it's only October of 25, but you know, it's good to kind of think   
1:34:29   
about, you know, the next six months or the next year, what people want to do,   
1:34:34   
what people want to accomplish. So, yeah, for sure. Um,   
1:34:42   
there's some carry over like I'm I'm happy because some of the dating interaction stuff has basically carried   
1:34:48   
over from from the spring into fall. Um, and we'll see. We'll see just how much   
1:34:54   
it does. So, but that's been nice to to kind of see. And I should probably do it a more formal like where are we with   
1:35:01   
that. Um, but as far as like   
1:35:06   
orthogonal proper and things to do, um, I guess an interesting development is   
1:35:13   
that, uh, Avery has been doing some,   
1:35:18   
uh, playing around with some AI stuff is is a very generic way of saying it, but   
1:35:26   
I feel like there's a lot of things. I think one of the latent things I think   
1:35:32   
I say this I've said this before but I think one of the latent things that is sort of just waiting for us to do more   
1:35:40   
in in the lab in general is sort of this um   
1:35:46   
either uh   
1:35:54   
not really multi-actor that's sort of inherent to it but but things around   
1:35:59   
either Metabrain, personality, althetic kinds, the types um and this like simul   
1:36:08   
simulation and or like um   
1:36:15   
so things things in that space. um an interesting overlap   
1:36:20   
or kind of overlap and I'm still somewhat um   
1:36:27   
I just saw the full like kind of release it earlier today um but DA from the   
1:36:36   
augmentation lab and and MIT stuff is releasing her her work which she's been   
1:36:42   
working on which has been I guess neuro chat uh the world's first neuro adaptive   
1:36:48   
chatbot that is adapts and responses to your cognitive engagement. So I guess   
1:36:53   
it's looking at at things like attention, curiosity, focus and tailoring teachings to all of that.   
1:37:00   
Um, and I just saw this here and it was put it in another Discord thing, but like I   
1:37:07   
don't I don't I'm not really suggesting that is what we focus on. Um,   
1:37:14   
also also literally yesterday someone showed me um   
1:37:20   
a job posting from Google about mental health and and how Google wants a mental   
1:37:27   
health like specialist and and you know there's this there's a very   
1:37:35   
interesting space between all the sort of one um   
1:37:40   
how do you say the   
1:37:47   
nuts and bolts of how you're doing things and then sort of this commentary on well we're going to how how are you   
1:37:52   
doing it that if you want to say the ethics speech the responsible AI piece but even more so just just sort of I   
1:37:59   
don't know we were reviewing the pro the pro the job description we were a bit cynical   
1:38:05   
about like um you know Um,   
1:38:11   
to what end? and and is is it is sort of like   
1:38:17   
the the the ethics board of approach to Google where we want you to say certain   
1:38:24   
things and do certain things but you know it's kind of just um almost like a um   
1:38:33   
you know not quite plausible to my ability but plausible given your care enough to to   
1:38:43   
to well we have our mental health specialists that that what's interesting as as another slight   
1:38:48   
tangent is a bit like you know this is sort of an unabashed um   
1:38:55   
we're all making products for young impressionable people and we're going to do a good job of it. Um but we're we're   
1:39:03   
we're in the this is our business and um   
1:39:08   
seeing that stands emerge and change over time too. So, um I think   
1:39:15   
I I would I'm a very soft easy pitch right now and I don't I don't think we   
1:39:20   
should do this per se, but I think there's something in a space like you could have sort of   
1:39:28   
I'd be very content with just doing frankly a computational simulation focus   
1:39:33   
on on the topics that we're talking about. You could easily dubtail like a society ethics technology type component   
1:39:39   
onto it too. So I don't know like I don't know how much um   
1:39:47   
but that that's one thing that immediately comes to my mind and secondly um   
1:39:55   
having been a little bit more exposed to to some like Josh Bongard and the Michael Leven stuff and the living   
1:40:01   
things are not machines and of course like the behavior purpose theology cybernetic stuff and then obviously the   
1:40:07   
paper like one of the things that um Bradley sort of re re   
1:40:15   
I don't know released or or put put drawn attention to or put together again. Um   
1:40:22   
like I I think I think you know like two three four   
1:40:31   
years ago reimagining cybernetics kind of this oh yeah we might be returning to this stuff now. I think a lot of people   
1:40:37   
are doing that now. Like I think I think it's become a bit popular in certain circles but like like some of   
1:40:44   
the folks are are   
1:40:50   
using cybernetics in a less haha   
1:40:56   
you know like more intentionally trying to use things from like old school cybernetics.   
1:41:04   
Um, and again, it's certainly not everywhere, but I think it's I think there's something there. Um, and and   
1:41:11   
even, you know, from, yeah, for a old school ales kind work to metabrain   
1:41:17   
stuff. I think I think there's a lot of things in those spaces that would be ripe. Um, and and and could even draw   
1:41:23   
like meaningful projects and also some like meaningful um interests who want to work   
1:41:31   
on them. I could I'm pretty sure I could find um some folks who want to do things in   
1:41:37   
those spaces in general um and research assistants and all that stuff too. Um   
1:41:44   
those two immediately jump out at me. I'm not I know you already been asking for that, but like it just it kind of just   
1:41:51   
this those are very already on my mind topics and I'm curious what you think   
1:41:57   
about where like where do you want where would you want things to go next year?   
1:42:03   
Well, I mean there are a couple areas I think we can probably you know revisit or bolster. So   
1:42:12   
like you know obviously the cybernetic stuff there's some momentum there we should keep going with that.   
1:42:20   
Um I think with the agents, you know, thinking well the open source sustainability stuff like what I was   
1:42:27   
talking about with the different connections between reinforcement learning and active inference and you   
1:42:34   
know some of the things we've been talking about there not just thinking about in terms of like you know a highly   
1:42:39   
applied sort of approach but like what is the deep you know kind of theoretical   
1:42:45   
questions that kind of link together these different approaches.   
1:42:51   
And then of course we can use that insight for some of the agent stuff and   
1:42:57   
revisit some of that work because we've you know kind of if you look at what   
1:43:02   
we've been putting out in the uh embodied intelligence workshop proceedings we kind of put together a   
1:43:10   
couple years worth of different papers there and they kind of laid out this   
1:43:16   
story of like developmental regular vehicles And then of course um you know that the   
1:43:23   
what are what are the things that lead from that work? What are the things that lead from some of the other work with   
1:43:29   
metabrains? How can we pull that together more? Um and so there's I mean   
1:43:34   
there's a lot of stuff there ready to go. It's just a matter of kind of thinking about how to maybe write the   
1:43:41   
next not just write the next paper but what are the um what are the paths forward in terms   
1:43:49   
of you know interesting research interesting   
1:43:55   
approaches things like that. Yeah. And I find that to be   
1:44:03   
as as a Exactly. And and I find it to be where   
1:44:09   
um Yes. But I I won't I don't I don't I   
1:44:16   
don't think I I'm I'm avoiding dragging dragging us in a very particular direction because um I I do think that's   
1:44:23   
that's exactly the kind of things that are important right now on many fronts and And it would be good in this   
1:44:29   
specific instance. Yes. Um uh for what we're doing anything.   
1:44:36   
Um yeah. Um   
1:44:43   
there's there are things going on with the the future center that I'm slowly   
1:44:50   
I don't know I don't know what to call the stage that it's in. It's in a kind of a launching   
1:44:57   
um like there are things happening and they're like semi-public,   
1:45:02   
right? But but it's it's it's it's it feels like, you know, the ship has set sail   
1:45:09   
and it's just it's kind of just it's going slowly. Um but that's that's   
1:45:16   
that's just fine. Like it's not ready. It's not ready for anything else. I'll just say very briefly, I don't know if I   
1:45:23   
I put an email out soon. I' I've meant to send emails a few weeks ago and and things like that, but it didn't it was   
1:45:29   
it it's okay that it was this way. But in the email um was a very I I kind of I   
1:45:37   
tucked it in there and it was a very very loose um future center like preview   
1:45:43   
about what we're doing in alternatives um a video and it's   
1:45:50   
I'm okay with it mostly like I would give it a   
1:45:56   
B minus. Um, and that's okay. Like I'm I'm I'm   
1:46:02   
trying to do some of the iterative stuff between both doing writing more and then like presenting and presenting to people   
1:46:07   
that have no idea what it is that I'm talking about and trying to do. Um, but   
1:46:13   
but essentially there's movement on, you know, this framework about like we use   
1:46:19   
terms like alternatives or on-ramps or destinations or or directions or and and   
1:46:25   
and what what do these things mean? So I'm kind of developing some of the core fundamental terms and and particularly   
1:46:32   
in terms of think about alternatives as like a thing to pursue uh of more   
1:46:38   
rigorous literature view across like actual interdisiplinary research some meta science stuff um and and different   
1:46:46   
like domains in terms of like governance or or like the   
1:46:52   
structure like you know philosophy but also like like administratively or   
1:46:59   
structurally how you're to do some of these things. So that's partly why I'm excited about, you know, I've happened   
1:47:07   
into this opportunity where the event I talked about first that's happening this coming Friday will be an opportunity to   
1:47:15   
basically and I I just talked to the organizer and it basically made green light to make it like a case study of   
1:47:22   
okay like how can there be this intentional synthesis time at the   
1:47:29   
end of the event And I'm I'm trying to find I don't know if there's really a way to do much   
1:47:37   
quoteunquote rigor about making it a case study right now because the timing of everything you know it's a hackathon,   
1:47:43   
right? But but at least documenting it um and and working with the working with   
1:47:49   
people that sort of try you know here's here's what we're doing um in this space   
1:47:55   
and we're being intentional about it and we're going to you know try to basically make it a reasonable test run of that.   
1:48:00   
like that's that's very that's exciting to me and that's something that I' that's something that we've been talking about here for a long time and it's sort   
1:48:06   
of the first liveaction opportunity to to do it. So we don't to talk about that   
1:48:12   
today um but I I am I am very curious if you   
1:48:18   
all thoughts about that over the week um because I wouldn't mind like some   
1:48:24   
perspective on what to do in that situation. Um, so maybe in Slack we could talk   
1:48:30   
about that. But yeah, yeah, that's I'll leave it at that as sort of like some broad   
1:48:36   
slightly slightly indirect but broad updates about adjacent things that are going on here.   
1:48:43   
Yeah, I think that's great. Um, and so yeah, let's kind of keep on some of these things and   
1:48:50   
keep working on them and um, yeah, and and you know, as we go along, I think   
1:48:58   
Uh we're going to maybe start to get some more movement on some of these areas that have been quiet for a while   
1:49:04   
hopefully. Um yeah, so thank you Jesse for the update.   
1:49:11   
So I'm going to finish up here talking about actually something that I saw   
1:49:17   
online. This is a AI journal club.   
1:49:23   
This is kind of an interesting group here. This is the sensory motor AI journal club. This is being held at   
1:49:29   
Berkeley, but I think it's a good example of kind of what Jesse was talking about in terms of finishing up   
1:49:35   
an event with synthesis. Um, this is I mean this is a certain style of it,   
1:49:41   
right? So, this is the reinforcement learning debate series. And so, this is   
1:49:46   
how can we build and understand agents that learn through action. So what they have is basically uh five people uh all   
1:49:55   
taking very uh intentional adversarial approaches.   
1:50:00   
Um so first is Ellie Sesh who's going to argue abolish the value function and   
1:50:07   
reinforcement learning try active inference instead and you envisions the brain as a   
1:50:14   
probabilistic feedback controller and then that's on October 2nd and then October 23rd there's going to be uh   
1:50:22   
Neil's lead homem who says you have a thousand brains in your brain which is this actually the hierarchical temporal   
1:50:29   
eneral modeling approach um structured representations for the win the cortical   
1:50:36   
column is a sensor motor learning system okay so there like there's the sort of   
1:50:42   
the active inference approach the htm approach and then the third person on   
1:50:47   
November 6th is Adam Loitt I literally measured value in the brain so this is   
1:50:54   
uh pro- reinforcement learning and specifically in opposition position Ellie Sesh's   
1:51:00   
position which is long you know which is to abolishing the value function and   
1:51:06   
Adam's position is long live the value function and he would further argue that reward is enough so that's sort of an   
1:51:14   
the RL camp the reinforcement learning camp and then uh an Collins on November   
1:51:20   
13th is not everything is reinforcement learning so her argument is beyond   
1:51:27   
reward maximization and thinking about the brain as a symphony, not a single reinforcement   
1:51:33   
learning machine. So you have kind of four uh perspectives there. And then the fifth perspective on December 11th   
1:51:42   
is Thomas Ringstrom, no reward for you. That's his tagline. And then uh but yes   
1:51:49   
to empowerment and compositional policies. So you see these different perspectives.   
1:51:54   
Actually, we've been just talking about this in this meeting where you have these different kind of takes on how   
1:52:01   
the brain does things, computations, whatever you want   
1:52:07   
to call it, and how we can use formal models. And those models kind of sit in opposition sometimes. But what they're   
1:52:14   
going to do in this series after these five talks is then on January 22nd in   
1:52:20   
2026, they're going to have a final debate and synthesis. So they're going   
1:52:25   
to have this is kind of a debate approach. It's kind of, you know, each week you're going to have a different   
1:52:31   
perspective and then you're going to have this final debate where they're kind of all there and they're kind of   
1:52:36   
putting together things into a synthesis. So that's that's an interesting series.   
1:52:42   
Um I just think that was interesting because it's kind of combining uh a lot of perspectives into a very   
1:52:49   
interesting kind of way of doing you know way of of kind of reaching this synthe synthesis this theoretical   
1:52:56   
synthesis. Um so this is the RL debate series their   
1:53:02   
website sensor motorotai.github.io and this is their debates. Um and so you   
1:53:09   
know their kind of idea of course is to focus on sensory motor learning and they   
1:53:15   
ask the question why do we have brains and the answer is simple to survive and reproduce and neither is possible   
1:53:22   
without some action. And so therefore brains are for generating behavior.   
1:53:27   
And so then you know that means that to understand intelligence we have to   
1:53:32   
understand action. Okay. So how do we formalize active learning which is kind   
1:53:38   
of how action um is sustained and so then of course the mainstream approach is reinforcement   
1:53:45   
learning which posits that agents act to maximize rewards. This is the figure   
1:53:50   
from Sutton and Barto which summarizes reinforcement learning. You have the agent uh con you know uh conducting an   
1:54:00   
action in an environment. uh that action then has a state and a   
1:54:05   
results in a state and a reward. The state is returned to the agent. So if   
1:54:10   
the agent does something, there's a corresponding state. There's also a   
1:54:15   
corresponding reward or lack of reward. So if you know the agent um does   
1:54:22   
something, it generates a state. It also generates a reward and then that state   
1:54:28   
can either be reinforced or the agent finds a different state and so that's the idea and then you know the policies   
1:54:35   
are sort of how do you reach a certain state and what is the best way to do   
1:54:40   
that is the best way to act. Um so at each time step the agent produces action   
1:54:46   
at causing the environment state to evolve from state t to state t + one.   
1:54:53   
the environment in return provides the agent with a scalar reward RT plus one.   
1:54:59   
That's the standard textbook view. So I mean there are a lot of ways you could unpack this. There are a lot of ways to   
1:55:06   
think about this model. You know we then talked about embodiment at all which   
1:55:11   
would imply that the agent is embedded in the environment or that the agent is embedded in a body which interacts with   
1:55:18   
the environment. um you know so we're talking if we're talking about action we're talking about um the body we have   
1:55:25   
to talk about the body if we're talking about sensory motor learning so that isn't really in the diagram   
1:55:33   
and you know the state of course is kind of arbitrary because you know we   
1:55:39   
can have a lot of states and quite frankly when you have sensory motor   
1:55:45   
learning often times the state is undefined or cryptic and so it's hard don't know even what the state or the   
1:55:51   
reward is. So this is kind of leading to this idea that reinforcement learning faces   
1:55:58   
fundamental challenges. Uh so a few of these are that rewards are inferred not given. So sometimes   
1:56:04   
rewards are very clear but a lot of times they're not. So sometimes the reward is sort of divined from the   
1:56:11   
environment. So sometimes they're even things that are aausal. So, you know, if you're um   
1:56:18   
worshiping the sun and you think that the if you worship the sun enough that it will give you good crops, you know,   
1:56:25   
good crop yields, and you kind of think of that as a reward. So, you keep doing   
1:56:31   
that activity, but that, you know, that isn't really a reward. It's just that you're getting good crop yields   
1:56:37   
independent of your actions. And so, the reward isn't really there.   
1:56:42   
it's just kind of imagined or or divined from circumstance. Uh furthermore, the state, you know,   
1:56:49   
understanding the state. What is what does it mean to have like a good crop yield? Um what are the underlying   
1:56:56   
conditions of that? All sorts of things that kind of mess with this model. Um so   
1:57:02   
rewards are inferred not given. Sometimes the rewards are very clear, sometimes they're not. Number two is the   
1:57:08   
scalar reward is illdefined for complex behaviors. As we mentioned, sometimes the reward is very unclear depending on   
1:57:16   
the behavior. Um, and then three, not all active learning is reinforcement learning. So   
1:57:22   
that's why they come up with these different approaches like active inference and HTM.   
1:57:34   
So these issues motivate the need to upgrade or even replace reinforcement learning. So there's this whole, you   
1:57:40   
know, kind of thing where people like to argue that here's the dominant paradigm.   
1:57:45   
Does it need to be replaced or can you like, you know, um, you know, have like   
1:57:51   
variance of that theory? And it's it's a kind of a tactic that, um, oftent times   
1:57:58   
is sort of rhetorical. In other words, like   
1:58:03   
you know, we just kind of like do these thought experiments about what would happen if we replaced reinforcement   
1:58:09   
learning with active inference. Well, maybe reinforcement learning is pretty powerful in general, but maybe reinforce   
1:58:16   
or maybe active inference could inform reinforcement learning. Or we could just   
1:58:22   
get rid of reinforcement learning altogether, but then we would have to kind of get rid of all the benefits that   
1:58:27   
come with that theory. So um that's kind of the point here u is that they are   
1:58:33   
trying to kind of think about how reinforcement learning can be improved   
1:58:38   
but maybe also replaced and in the process kind of come up with this theoretical synthesis. So this is where   
1:58:46   
they have this RL debate series where people will defend or   
1:58:52   
um criticize their favorite theory. Um and then you know this just kind of   
1:58:58   
talks about some of the ways in which um you know these these conceptual   
1:59:04   
problems with reinforcement learning are manifest. So the first one is rewards must be inferred. They are ultimately   
1:59:10   
subjective. So um if you're a neuron in the nervous   
1:59:15   
system in the brain there's no such thing as the outside world. All that exists are spikes or action potentials   
1:59:23   
arriving at your synapsis from other neurons. Everything else is inferred. So   
1:59:28   
this is where you know we have this issue of phenomenology where we have things that are phenomenological and   
1:59:35   
things that are not. Color for example is not phenomenological in this case.   
1:59:40   
Photons are color is inferred from photons. It's constructed from by the   
1:59:45   
brain from incoming sensory data. Um, rewards are very similar to this.   
1:59:51   
Rewards are inferred from incoming sensory data. And so, you know, that   
1:59:57   
kind of decouples a bit uh, you know, causality in the environment from   
2:00:04   
perceived causality in the brain. So that they kind of point out that this is   
2:00:09   
the first major problem with the Sutton and Barto view. The environment doesn't dole out rewards. It actually just   
2:00:16   
provides sensory evidence and then you kind of interpret the reward from that meaning that the reward can sometimes be   
2:00:24   
you know um spurious or it can be um weak or or cryptic.   
2:00:31   
So they give this example of the burger versus salad. So consider an omnivore   
2:00:36   
and a vegetarian. Put a double cheeseburger with bacon and a salad in front of them. Is there an objective   
2:00:43   
observer independent scale or reward attached to each food? No. The omnivore   
2:00:49   
maybe prefers the burger and the vegetarian prefers a salad. It's just because of their internal preferences   
2:00:55   
that they make those choices. And then of course the reward is different for each of those agents.   
2:01:01   
Um and then so rewards are just kind of this thing that is an internal state   
2:01:07   
more than an external state. Um, and so then they point out that reinforcement learning typically works   
2:01:13   
in toy settings, meaning that it's not really it's not a real world scenario.   
2:01:18   
It's not a real world um case study. It's just kind of like we set up a   
2:01:25   
really obvious reward structure. It's very clear what the reward is and then we have the algorithm do and we   
2:01:32   
implement the algorithm and then we get the result that the agent responds to a   
2:01:38   
reward. Well, if the reward is clear, the reward signal is clear and the agent   
2:01:43   
is simple, then obviously it works. But that's not necessarily the way it works in the real world. So this brings us to   
2:01:51   
a deeper question. Is reward maximization really enough? If we do   
2:01:56   
like neuroscience experiments with rats, we often set up the experiment where the rat is put in an environment where   
2:02:04   
they're deprived of things in their environment that they would normally have and then we give them a juice box   
2:02:10   
or like a a lever which they can push to get juice. And so obviously   
2:02:17   
um when they're in that kind of setting, there's this very simple interaction that can be made. It's not, you know,   
2:02:25   
it's not like real life. It kind of tells us that they would like more juice if the juice is good, but that's beyond   
2:02:32   
that, that's not really giving us much more information. Um, so the sort of ecological validity   
2:02:40   
of a lot of reinforcement learning is low according to their argument. So that   
2:02:45   
means that you know you you can't say a lot about reinforcement learning as   
2:02:51   
something that we could model behavior on from like you know experiments with a   
2:02:57   
rat in a cage or this idealized model of reward.   
2:03:03   
And so uh and then this this other point not all active learning is reinforcement learning. And so this is a classic   
2:03:11   
experiment by Tolman uh where uh   
2:03:16   
yeah well they don't really go through well I guess they go through it down here. Um so they basically this   
2:03:23   
experiment Tolman and Hanzik 1930 trained three groups of rats in a maze.   
2:03:28   
You have the rewarded group which were seeing food at the end of every maze trial. uh no reward group which never   
2:03:35   
received a food reward and a delayed reward group which explored the maze without reward for 10 days and then   
2:03:41   
received food from day 11 onward. And so then they you know they talk about kind   
2:03:47   
of this how this set up this idea of latent learning and how the rats had built an internal   
2:03:53   
cognitive map of the maze without explicit rewards. So they kind of had some findings from this sort of study   
2:04:01   
where uh rats demonstrated active learning without any well- definfined reward from the environment.   
2:04:08   
Continuous external rewards actually inferred with this ability interfered with this ability. Um the delayed group   
2:04:15   
learned more efficiently once a reward appeared and the delayed group was exploring fe freely showing clear   
2:04:22   
evidence for active learning. But importantly, it wasn't reinforcement learning in the sento sense. So that   
2:04:28   
means that either motivations are intrinsic and not necessarily based on   
2:04:34   
external reward or that also that reward might not be enough. That reward is there but other   
2:04:41   
things are active. Um and um you know so we we are kind of getting an incomplete   
2:04:48   
picture and um you know it's important to remember that behaviorism was of course   
2:04:55   
a dominant approach in the early part of the 20th century but cognitivism came   
2:05:01   
about largely because behaviorism was in insufficient in explaining a lot of   
2:05:07   
decisionmaking behaviors. So, you know, we're dealing with a paradigm that was kind of supplanted in   
2:05:15   
neur in uh in psychology. Um, and so, you know, it we have to kind   
2:05:22   
of remember that because that gives us kind of a framework for maybe ways to   
2:05:28   
improve reinforcement learner, even supplant reinforcement learning. Um   
2:05:33   
so yeah the Sutton embarto paradigm is you know their idea is that it needs to   
2:05:39   
be improved or we need to think about it more critically and you know that's what   
2:05:44   
they're going to be doing in this series. Okay.   
2:05:51   
So we have any comments or questions   
2:05:57   
there. Okay. No. Um yeah that's really cool. is obviously part of Lisa Fil and   
2:06:02   
Bear's Lab. Um he's kind of put some discussions here and discussions outside of this this place too. So it's always   
2:06:10   
fun to see what he's up to. Um and I've   
2:06:15   
been looking at the website um and I look I really enjoy this. Like I I   
2:06:22   
uh this is a great example so timely. Um thank you for following this barely. Like this is I I   
2:06:31   
I I like I wish more debates were laid out in   
2:06:38   
advance like this. I think that's what we need to do. Like   
2:06:43   
that's uh as if we arranged it or was it was it   
2:06:49   
reward or was it just the divine insight of our conversations leading us to wherever we are here? But like no, like   
2:06:56   
that's a perfect that's a perfect it's exactly where I was kind of going with some of the stuff um that I wanted to   
2:07:03   
see more of. So this would be a nice example too. Um   
2:07:08   
what and and because it because it's so close um when this this is this is actually   
2:07:15   
quite interesting parallel to something that um Andre from the qual research   
2:07:22   
institute said when he was looking at like the state structure of like happiness or like discontent and how um   
2:07:30   
I don't even going to try to recapture the specifics of what he was getting at but he's looking at like the qualia   
2:07:36   
and and things he was looking at through um the research he's doing. But as a slight   
2:07:42   
tangent, um discontent or like massive disharmony   
2:07:48   
often is a similar structure to contentness with like one thing off or   
2:07:54   
like like a very small structure change. And so that's why like I feel a version   
2:08:00   
of that right now looking at this is like oh this is like this is great great great great great great stuff and it's   
2:08:06   
like I know especially and I realized seeing like the final debate setup is like oh yeah like I think it's quite   
2:08:12   
popular right now and have these like debate shows where you know you go around you debate the entire planet and   
2:08:18   
you have I I'm trying to stem a very particular   
2:08:24   
rant that I don't know that I want to get into But yes, so you have this debate and what the only thing that I'm   
2:08:30   
missing from this and and I'm happy because the website itself kind of gets at it like the website itself is   
2:08:37   
attempting to address address it um as   
2:08:44   
um like in the debate synthesis I was hoping like before I saw before I saw   
2:08:49   
what we went through I'm like oh like we need to talk about the problem space too even if there's disagreements about how   
2:08:55   
we see the problem space like You have to set it. You have to contextualize it and you have to, you know, I I like what   
2:09:02   
they did on the website and he went through it right now is very nice and very helpful and very useful. Like I want to normalize that. And I hope   
2:09:07   
during the debate at the end they kind of give some time to both that and then   
2:09:13   
also you know their own quote unquote state   
2:09:18   
change from from okay we started having this view here's where we've kind of   
2:09:23   
ended up with it. and even even with a way of like what I would like to do um   
2:09:29   
not necessarily in the GitHub version control sense but but map like the   
2:09:36   
all these words that come to mind GitHub or embryo like these are all buzzwords for for us and I don't I don't like what   
2:09:42   
comes to my mind but mapping with the the the stems you know like we talked about twi birds   
2:09:49   
and things of this not just like I just said passing out but like your your like you're going to the edge and you you   
2:09:56   
okay ideally maybe you you've you've collectively spent some time as I'm saying steelman the problem space like   
2:10:03   
you've made you've made articulations about the space as good as as good as you can be with hopefully high degree of   
2:10:11   
consensus but like at least identify the starting point coherently and care about   
2:10:17   
that and then maybe maybe you're have some kind of   
2:10:23   
code shorthand documentation structure. I don't know like like   
2:10:28   
the philosophical uh rigor of some kind about the changes   
2:10:36   
um to that problem space that you're advocating for or at the very least like   
2:10:43   
I was getting the word affordances also. I feel like I'm missing all I feel like all the buzzwords are just coming out of my mind from our like this this lab   
2:10:50   
we're talking about. But like are you are you   
2:10:56   
able to sort of articulate the the the the end the the edge   
2:11:04   
where where the debate expands into like oh well if this if this is so it it maybe   
2:11:13   
emphasizes this downstream set of things while taking away from the other. And I   
2:11:19   
feel like that just the articulation clearly of what that is relative to   
2:11:24   
who's winning the debate or how convict like like like   
2:11:31   
there's a certain kind of humor to the fact that we talk about all this all this stuff about you know um debates and   
2:11:39   
winning and um like applying this to like logic or   
2:11:45   
rightness or correct or something. And then yeah, it's like like part part one of one of the debate structure itself   
2:11:51   
was like well the reward's kind of just inside you anyways. And so it's like you know but like how   
2:11:57   
do you how do you you know how do you not not just the sense of winning but like   
2:12:02   
how do you articulate what what what's happening in a way that's not just oh   
2:12:09   
this resonates with this resonates this pangs around inside me in a way that's favorable and positive so I feel good   
2:12:15   
about that. I think that's win and I think I'm advancing something because it it feel it resonantly feels enjoyable to   
2:12:21   
me versus like you know and then winning but then like and I don't I don't I don't honestly suspect this is going to   
2:12:27   
become some ugly you know brutish debate uh of of the our reinforcement learning   
2:12:34   
philosophers or anything but you know like how do how do we how do we make it meaningful   
2:12:41   
in in ways that maybe can outlast the moment too right and and and and and keep the map   
2:12:48   
the map the map of the space that we've built afterwards like hey like is this a   
2:12:53   
map we can reuse later or is it just that was nice you know um so I I'm very   
2:13:03   
appreciative of of you sharing that and walking through it because it's it's a great real example about a real topic uh   
2:13:12   
with real people that are, you know, doing it. Like that's that's a   
2:13:18   
great that's one of the best examples I know right now found out 20 minutes ago of like what is   
2:13:25   
what is an example of some of this. So, thank you for that. All right, I think why don't we uh call   
2:13:31   
it a day. Um, thank you for attending and I think we had some good conversations today.   
2:13:38   
All right, take care everybody. Take care. Thanks. Bye.   
