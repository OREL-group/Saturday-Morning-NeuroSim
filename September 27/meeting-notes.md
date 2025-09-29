## Meeting Recording

[YouTube link](https://www.youtube.com/watch?v=6aBJTryDBBw)

## TRANSCRIPT
0:00   
Hello and welcome to the Saturday morning ren update for September 27th.   
0:07   
A couple things to update us on today. Um the first thing is of course we had   
0:12   
our Eagle Worm meeting this week. So number 32 and that's on the Eagle   
0:19   
YouTube channel. And we covered two topics this week. The   
0:24   
first one was to go over a paper that utilized the Compyel 3D modeling   
0:30   
software. And in meeting 31, we did a paper that covered console, which is a   
0:38   
multifysics modeling tool. And in 32, we covered uh Compy Cell 3D as a comparison   
0:46   
to see how these things were. We also then dealt with uh kind of an   
0:52   
overview of the vectors artificial life platform which is kind of an interesting platform was brought to my attention by   
0:59   
Hussein put one of the slack some of the materials there. It's a has   
1:06   
a GitHub repository and they're doing some interesting things with life cycle   
1:13   
and with behavior. So it's something to check. So, I'd like to go over a few more   
1:19   
items. So, this is followup from last week's meeting. Jesse uh initiated a   
1:25   
conversation on this event here. And so, we talked about Michael Le and Josh   
1:31   
Bungard's work embodied robotics and a lot of the things they were doing at this foresight   
1:39   
virtual seminar group. And so, this was held on the 19th. So, this was uh last   
1:44   
Friday. and uh the title was embodied natural intelligence versus embodied   
1:50   
artificial intelligence. So, a few words on this. First of all, thank you Jesse for presenting. Um   
1:58   
but the other thing is is that it's interesting to see how they're kind of approaching some of this work. So of   
2:05   
course you know there's this interest in taking what we know about natural intelligence and embodiment and   
2:12   
replicating it as embodied artificial intelligence. So this is sort of the   
2:18   
description here. Uh and so you know let's see the abstract   
2:24   
reads the author Jacob uh Bernowski famously express the hand is the cutting   
2:30   
edge of the mind meaning things are translated into movements into the body   
2:37   
from the mind. So it's not just in the brain that's as activity in the world as   
2:43   
a major component. Natural systems including humans, advanced mammals and even avi species   
2:50   
have a core ability of treating tools as extensions of the body. A trait highlighting an evolutionary   
2:56   
advantage of generalizing motor skills. Natural systems can even operate devices   
3:01   
that have no ethological precedent. So we give the example of a monkey driving a car indicating a general purpose   
3:09   
learning machine for body control. Uh so these bold terms are things that they   
3:15   
kind of stressing in the discussion. Yet in the internet scale age of data modern   
3:20   
robotics remains surprisingly brittle in comparison to the above. So you know this general purpose learning machinery,   
3:28   
the ability of generalized motor skills, treat tools as extensions of the body,   
3:33   
coordinating tools with movements and then having this aspect of ethological   
3:40   
precedent or no sort of ethological precedent. Um and you know all those   
3:46   
things you know we haven't been able to master. Uh in this talk we will we ask what   
3:53   
exactly embodied intelligence is and unpack the reasons behind the persistently large gap in capability and   
3:59   
reliability between natural and artificial systems in the realm of physical interaction. So uh Josh Bongard   
4:08   
in particular is always involved in the embodied intelligence workshops. So he   
4:13   
has some really interesting work on uh morphological computing and robotics and   
4:18   
of course Morgan's been working with uh the platform uh that Josh Bongard is   
4:26   
open source for his class and uh you know I was thinking about this after   
4:33   
so I was thinking about that after last week's meeting and uh wondering how   
4:39   
you know you can approach sort of these embodied robotic builds as this sort of   
4:46   
evolved parts list. We've been doing some things with parts lists in a few publications also you know thinking   
4:53   
about this in contrast to some of the phoggenetic methods that we proposed. So   
4:58   
I I'm interested to see um you know what what kind of arises from that work since   
5:06   
uh the Bongard lab has this computational sort of uh toolbox that   
5:13   
you might be able to use. Second thing I wanted to bring up is this uh package called PI reason. This is something that   
5:19   
was also put in Slack I think by Morgan and this is a Python package where   
5:25   
they're doing neurosyolic computing. So, high reason is a powerful Python based   
5:30   
temporal first order logic, explainable AI system supporting multi-step   
5:36   
inference, uncertainty, open world reasoning, and graph-based syntax. And   
5:42   
so, this is uh the package here. So, you can download the paper which is an   
5:49   
archive. You can look at the inter blog post or you know you can download the pi   
5:56   
project or just load it in in a python. So this is uh nice stuff. Uh they   
6:04   
actually have some slides here as well and some videos. Um and this is   
6:09   
basically what they're doing. So uh they have this graph which has the initial   
6:14   
state. They have rules which are either learned or been specified.   
6:20   
And then you have this these outputs which are the explainable evolution of   
6:25   
the graph over time. So this graph changes according to the rules according to interactions and then you can explain   
6:32   
the output. So a lot of times if I run a network and I let it run for a long time   
6:39   
and then I plot a graph there's no way for me to interpret that. So this is an explainable   
6:46   
system and then you can uh compute things like rewards or other aggregates   
6:52   
uh which which is nice because you have this neuros symbolic tool that's also auditable and so this is this is all   
7:00   
looks like a very interesting uh um   
7:05   
package and they have some papers using py reason. This is out of the neurosy AI   
7:10   
lab at Arizona State. So they've used this in a number of papers. This one uh   
7:17   
is a geospatial trajectory generation via efficient abduction deployment for   
7:22   
independent testing. Of course abduction being a type of inference.   
7:28   
We have the precurren and this talk at ICLP.   
7:34   
Then the next one is scalable semantic nonarcodian simulation. proxy for   
7:39   
reinforcement learning. The next one is Pyrez is a sim for deep reinforcement learning.   
7:46   
And we have three papers. That's pretty good. Um yeah, this this looks   
7:51   
interesting. We should dig into this and talk about this a little bit more.   
8:01   
All right. So now I want to talk about the active inference institute and the symposium that's coming up. So we have   
8:09   
the symposium in November and I'm working on a couple of talks for this.   
8:14   
Um I'm working on a talk on spatial intelligence and spatial cognition which   
8:20   
kind of came out of the work that we're submitting to the special issue that   
8:26   
Adam Saffron is hosting in uh   
8:32   
in philosophical transactions. So that paper is coming along. Um but as   
8:40   
a as part of that we talk a little bit about spatial cognition and you know   
8:49   
some of the computational models one might use and so this is kind of where   
8:54   
this talk is going. So I'll I'll post the talk on YouTube closer to symposium   
8:59   
day. I'm also working on a talk on open source our open source sustainability   
9:05   
project. So we have a number of different um   
9:10   
you know projects that we've done over the past few summers and we have you know of course our focus on force   
9:18   
learning but also our focus on active inference. um and I kind of over give an overview   
9:24   
of those different efforts and then frame that in the larger context of open   
9:30   
source sustainability and uh how that project might move forward. So you know keep stay tuned for   
9:38   
those talks. They'll be on our YouTube channel. Uh but this is uh the active inference   
9:45   
website. So the active inference website uh I haven't really gone over this too much. usually interacting with the   
9:52   
institute on the back end. We don't spend enough time kind of going over their website.   
10:00   
So they have a lot of educational opportunities at the active inference institute. They have a textbook group   
10:06   
where they're working in this active influence textbook. They're just kind of working on chapter by chapter. It's a   
10:12   
participatory uh effort and the whole lab of course is participatory but the   
10:17   
textbook group is participatory. Uh they have courses   
10:23   
live streams of course in the symposium since the symposium. So live streams are   
10:28   
they're always very useful. Um I've participated in one or two of them and they have them almost every other week.   
10:35   
So you should be able to get uh some you know keep keeping uh keep tabs with some   
10:42   
of the things that they're doing. I'm really impressed by the breadth of live stream coverage that they have. Um then   
10:50   
of course research you have research overview but you have a number of software packages such as RX infur   
10:58   
active blocks the theoretical neuroscience group which is of course   
11:04   
owned by Carl Fristen and then of course they have the participate   
11:10   
participation link and some other things they're running this um this uh these   
11:19   
sort of research fellowships or research internships where people who are interested in doing work on active   
11:26   
influence can get supported by the institute. Um we also have a number of   
11:31   
different partnerships with different organizations. Um and you know we're we're of course   
11:37   
supporting the active influence institute in others. Um let's talk a   
11:44   
little bit about the symposium. This is the website for the symposium. So this goes back   
11:50   
this goes back to 2021 where they did a symposium which was basically Carl   
11:56   
Fristen with a set of lectures. Uh so that was the   
12:01   
first one and then the second one was in 2022 that was on robotics.   
12:06   
The third one was in 2023 that was enacting ecosystems of shared intelligence.   
12:12   
And these are all kind of I think they're on YouTube. I'm not really sure what the state of these first three are.   
12:20   
I know I remember catching some videos for the third annual uh symposium, but   
12:26   
the fourth annual symposium was this was the one from last year and this had a lot of deep coverage on YouTube and of   
12:33   
course we contributed to this. We contributed three things to them actually four. Uh Jesse gave a talk   
12:41   
uh I gave two talks on behalf of the lab. one for uh open source and open   
12:48   
access and then the other one cybernetics research group and then uh   
12:53   
we had an interview with Stephan Baldman who was doing a lot of things in   
12:59   
software reusability and computational neuroscience   
13:07   
of neuroscience data. So that was a nice talk that that we and   
13:13   
then in the fifth uh the fifth annual symposium is coming up November 12th   
13:18   
through 14th. So the registration is now open. So if you're interested register to attend or watch a YouTube live   
13:26   
stream. Um and you know it should be a great time.   
13:34   
I also wanted to highlight something Jesse is doing uh with Job Pro. So, this   
13:39   
is uh something that was listed on LinkedIn. I don't like to actually pull up   
13:48   
meeting because they have a lot of visual future. I'll charly call it visual future company the site. So,   
13:56   
we'll just do it like this. Uh so this is uh Jesse posting   
14:01   
this about this topic in Jopro. So of course he's trying to develop this JOP pro future center. Um and so he's in   
14:11   
this post he's covering this pessimistic optimism split. And so what that's   
14:16   
referring to is some uh demographic data about Gen Z.   
14:21   
So the data reveal that Gen Z feel significantly higher levels of pessimism about the current state of things   
14:28   
including their jobs, their financial system and the country which is the United States in this survey. 71%   
14:36   
expressed negative views about the country's state compared to 59% of older employees. This pessimistic outlook   
14:43   
begins with personal circumstances. Gen Z report much higher dissatisfaction   
14:49   
with their financial situations and work situations. But then if you look at sort   
14:55   
of the future or looking towards the future, Gen Z demonstrates consistently   
15:00   
lower pessimism of what's coming next than their older colleagues. While they   
15:05   
may be harsh critics of current conditions, younger workers are genuinely optimistic for what lies   
15:11   
ahead. And so these are the data in bar chart form.   
15:21   
And so, uh, Gen Z's optimism about future work situations, 20% more   
15:27   
optimistic than older employees, suggests they believe workplace conditions can improve through effort   
15:33   
and change. Their financial optimism, only 2% more optimistic, indicates   
15:39   
confidence in their ability to build economic security over time.   
15:44   
even about the state of the country largely outside individual control. Gen   
15:49   
Z shows greater future optimism. This suggests a fundamental belief in positive change possibilities and   
15:56   
ultimately greater change readiness and agility in the workplace. So this is uh one of the things that yes   
16:04   
he's trying to work out with his job for future idea. So yeah, he's I   
16:11   
think he's got some interesting things to say about that. Um   
16:16   
yeah, so that's great. Thank you. Uh congratulations Jesse. It's good.   
16:23   
So a few things that are out now from the lab at Research Gate. Um this first   
16:28   
one is phoggenetic models of embodied agents, an ecoebo approach. This is a   
16:34   
preprint that's been uh freshly released on Research Gate. What we like to do is   
16:40   
release things on Research Gate and get some interactions with it to see how   
16:46   
people respond and then maybe put some things on archive later or publish them   
16:52   
somewhere else. And so this is the first item I'm going to talk about here. This   
16:57   
is uh phoggenetic models of embodied agents. This was presented at the   
17:02   
embodied intelligence workshop this year. So usually we submit a paper in   
17:09   
conjunction with that talk and this is the paper for this year. This is just my   
17:15   
uh I'm the sole author on this and it kind of walks through um embodied agents   
17:21   
and how you can analyze embodied agents using phoggenetics. how you can build phoggenetic agents   
17:28   
from a parts list, but a parts list that has a phoggenetic sort of   
17:34   
set of relationships. So that means that you're going to have parts that have a common origin and that are elaborated on   
17:41   
through evolutionary processes or just simply through classification. And so   
17:46   
you know we uh in in one of the figures in the paper involves an analysis of   
17:53   
brainberg vehicles using the phoggenetic approach. And so this is but this frames   
17:59   
us in eco evo approach. So we bring in things from developmental brain   
18:04   
vehicles. We also bring things in from embodiment research quite explicitly in   
18:12   
this in this paper.   
18:32   
And so this is the other uh paper. This is from our cybernetics group. So this is the cybernetics group listed authors.   
18:41   
And this is called a brief history of cybernetic imperatives and behavior. So this paper follows up on the uh talk   
18:50   
that we gave last year at the active inference institute symposium. So if you   
18:55   
recall that talk that involved going back to Rosenth 1943   
19:01   
looking at their behavioral typology and reinterpreting that in different ways.   
19:08   
There are also some other uh gens in here with respect to cybernetic control   
19:13   
and behavior and thinking about behavior in terms of cybernetic imperatives which   
19:20   
are sort of reinterpreting the idea of goal directedness as purposeful and um   
19:27   
looking at the roots of behavior building up compositionally to more   
19:32   
complex behaviors.   
19:56   
So actually if we go back to the paper on phoggenetics this is the figure one which is actually it's a three-part   
20:04   
figure which goes over this phoggenetic analysis of braenber vehicles.   
20:10   
So you can see kind of they're very faint, but these are the Brightenberg   
20:15   
vehicles that are proposed in Braenberg's 1984 vehicles. So he   
20:21   
proposes three classes of vehicles, one, two, and three. For vehicle one, it's   
20:27   
very simple. It's 1A, which is a single wheel on a single axis. Kind of like a   
20:33   
unicycle with a sensor at the front. And so this is of course it produces forward   
20:39   
brownie in motion and this is kind of the simplest vehicle you can have. Then   
20:44   
there's class two which is elaborate on different connections between sensor and factor both pixelateral and contrateral.   
20:52   
So you have these uh you know analogies from the nervous system and they produce   
20:58   
all sorts of interesting behaviors that Renberg characterizes both as sort of   
21:04   
functional and effective which is you know maybe a leap on his part but that's   
21:11   
kind of the way he did that. Um and then C or uh so we have 2 A, 2 B and 2 C. And   
21:18   
then we have our class three which is A B and C. And these are vehicles that   
21:23   
have multiple connections between sensor and a factor and exhibit more complex   
21:29   
behaviors uh both affective and functional.   
21:35   
So this is kind of doing a phoggenetic analysis of the information that gave   
21:41   
about vehicles. it involved a lot of uh hard coding different character states and so this   
21:49   
is the these are the uh different phoggenetic arrangements that uh were   
21:56   
sort of the output of this analysis. So one A is typically considered in   
22:02   
biogenetic analysis to be out group and then two and three are their own plates.   
22:08   
Of course this is kind of uh a little bit different from a typical phogenetic   
22:13   
analysis and that we kind of know what the classification should be. So two and   
22:19   
three are going to group together but we don't know the internal structure of two and three. So we look at two two and   
22:26   
three. We have 2 B forming this sort of uh well two two A 2 B and 2 three form a   
22:34   
plate. 2 A and 2 C form a plate within that plate and they both think as sort   
22:40   
of cross talk with cowardous behavior. So the cross talk is the uh the cross   
22:47   
connections between sensory andector. And then 2B is this sort of uh lone   
22:55   
tax in this play where it has cross talk but aggression instead of   
23:01   
three uh 3 A 3B and 3C. We have 3 A and 3B.   
23:12   
So the second plate is 3 A, 3B and 3C. We have 3 A and 3B is this internal   
23:18   
plate where you have actually two different behaviors but the same architecture or very similar   
23:24   
architectures, love and exploration. Uh and then we have this other uh   
23:31   
architecture which is multiple connections from uh a group of sensors   
23:37   
to a group ofectors or to one aector and then that exhibits uh different types.   
23:44   
So there's cross talk in this one multiple forms of cross talk. This gives us a behavior called values.   
23:52   
The common ancestry between two and three is this goal directed motion as opposed to motion.   
24:00   
And so this is just the other parts of this figure just showing the uh examples   
24:06   
of say shared derived traits or homology. So we have homology here which is this vehicle state. Um we have go   
24:14   
directed motion which is up here and we have uh independently derived traits or   
24:21   
convergent evolution of cross talk. So you see cross talk in both two and three   
24:27   
and you can say those are evolved. So why do this analysis? Well, it's   
24:33   
interesting because of course we can classify vehicles in a different way.   
24:38   
You know, typically the classification is sort of top down, but we can also   
24:43   
understand how some of these traits might evolve. If we want to say create a substrate for the evolution of vehicles,   
24:51   
we see that like there's certain things that might independently evolve and some   
24:56   
things that um can be sort of shared derived traits. So we'll know what say   
25:02   
to hardcode into basic vehicle uh say genotypic representation if we're   
25:09   
using genetic algorithm or if we want to build   
25:15   
something that has you know the ability to evolve behaviors uh through   
25:20   
interactions with its environment selection then we should expect certain   
25:26   
traits certain phenotypes certain types of embodiment to occur again   
25:33   
but that's that's basically the value of this analysis and then this figure two talks about the   
25:40   
sort of parts list approach so this is where you know we look at fogyny of this   
25:46   
isn't vehicles but these are vehicles that from a parts list that we define   
25:53   
and the parts list is kind of you know reconfigured basically through   
26:00   
evolution and you can see that you know you can have these fogynies where you   
26:06   
have common ancestor variations on this on these or elaborations on these   
26:12   
different phenotypes. So this is uh of use of thinking you know what kinds of   
26:18   
vehicles can you get from a common ancestor meaning uh certain assembly   
26:24   
assemblage of parts and then you know what are the sort of the alternative forms that we might expect   
26:44   
So this is the brief history of cybernetics imperatives and behavior paper. A couple points about this paper.   
26:53   
First of all, this is our uh the current state of our   
26:59   
sort of timeline of teology. So this is this paper focuses on   
27:04   
teology. So this actually goes back to uh ancient   
27:12   
times and medieval times and how they kind of thought about progress in nature   
27:17   
and teology and then how that kind of became a naturalistic phenomena and then   
27:24   
how that was you know or changed or was otherwise incorporated into different   
27:31   
theories and more modern theories. So you know this influence about evolution   
27:37   
by natural selection, but it also influenced thinking about vitalism.   
27:42   
It actually has some influence on things like basian um   
27:48   
modeling and aprior knowledge and it even has connections to things like   
27:54   
behavior as habit and other types of things. So this there are three kind of uh streams here. one   
28:03   
leaning directly from ancient times. uh be leading from sort of the book of the   
28:09   
first uh behaviorists and psychologists and then like the sort of basian path   
28:17   
which leads to goal directed behavior and some variations.   
28:23   
So, it's kind of a nice timeline that goes through a lot of different,   
28:29   
you know, different milestones and different pieces of work that kind of lay out some of this   
28:36   
uh intellectual trait. Then, of course, we have the behavioral   
28:43   
uh classifications of behavioral typologies   
28:48   
that come from Rosenberg 1943. So this is a reproduction of that   
28:54   
behavioral typology. And so we as we recall we decompose behavior into things   
29:01   
like active behavior, purposeful behavior, teological uh behaviors like   
29:08   
feedback, extrapolative behaviors like prediction and then orders of prediction. Then everything else in in   
29:16   
each stage of this is is sort of a non-category or a nonclass. So like for   
29:22   
example you have active behavior and then you have passive behavior but passive behavior includes all non-active   
29:29   
behaviors. Anything that's non-active is in this category. The same for purposeful. If it's purposeful   
29:36   
uh it's in this sort of line of going leading up to order of prediction and if   
29:42   
it's nonpurposeful it's just it's not a category we're in. And so the terminology of course is   
29:48   
taken from Rosenberg. So maybe the terminology is suboptimal, but that's the way that the ship works. And so one   
29:56   
of the things about this behavioral typology that's nice is that we can play around with it. We can move things   
30:03   
around. We can add in different components. And so one of the ways in which   
30:10   
this was done   
30:29   
One of the ways in which this is done is to show some of these uh to play around   
30:34   
with some of these number classes and to say that they have different periods. So   
30:39   
this one is um a variation where the uh   
30:45   
non-purposeful non-category is replaced by a historical   
30:50   
sort of alternative to purposeful. And so this is just one example of how this can be done. Um, figure four shows a   
31:00   
little bit more ambitious change where we have instead of   
31:07   
purposeful as the path to the order of prediction, we have non-purposeful   
31:12   
random behaviors leading to the order of complexity.   
31:18   
And so, you know, we're kind of playing around with these categories. This next one is involves um looking instead of   
31:26   
the order of complexity the order of dynamics. So this is where we have active behaviors non-purposeful random   
31:34   
behaviors nonlinear or nonological behaviors uh dynamical behaviors   
31:40   
recurrence and then order which can be first second or third or higher. And so this is uh you know kind   
31:48   
of a useful tool for looking at some of these how behavior could be decomposed   
31:54   
and then of course composed if we go in the opposite direction. So if we want to   
31:59   
say understand behaviors from say like a general order of complexity or a general   
32:05   
order of dynamics we want to build a robotic system where we know what kind of dynamics we want. We just want to   
32:12   
build or compose a system of behaviors that meets that   
32:18   
requirement. Then we can use this typology to sort of build like kind of   
32:23   
backwards along this typology for the order of flexity or dynamics. Back tempo   
32:30   
dynamics or long prediction feedback or linear non-purposeful   
32:37   
active. So we know kind of what components need to be there. and how we need to add them together.   
32:54   
Another kind of valuable thing in this paper is this table of cybernetic imperatives. So this is where we have   
33:01   
these imperatives kind of listed here. this these processes that are associated   
33:07   
with these impairments and then the example of the behavior. So these some   
33:12   
of these are animal behaviors, some of these are behaviors of that we see in   
33:18   
humans, some of these are physical behaviors like symptom   
33:23   
motion. Some of these are are proc complex processes like avalanches   
33:29   
and so collective behaviors. So there are a lot of different types of   
33:34   
imperative existed different processes that drive them.   
33:40   
And then this is an example of sort of this progression in behavioral sort of   
33:45   
integrity or behavioral uh you know going from brownie in motion to pair order prediction. So this this   
33:54   
was handdrawn because I didn't really have a way to plot this out properly   
34:00   
using but in any case uh this so this proceeds from Brownian motion which is   
34:06   
like this random motion point to these sort of levy flights where you get this   
34:11   
random motion plate but you have these jumps these exploratory jumps. Then you   
34:17   
have ballistic movements which are straight line movements in a certain direction that then get corrected later   
34:25   
down the line through feedback and you get this sort of uh trajectory that   
34:30   
keeps missing about having to be corrected later. So you get this sort of   
34:36   
mystic sort of trajectory where you know it's very little uh   
34:42   
instantaneous control. That's more like delay. In four we have first order prediction   
34:48   
and dynamics where we have smooth smoother dynamics smoother prediction   
34:54   
but it's still you know rel this continuous feedback. And then   
35:00   
finally number five is higher order prediction and dynamics prove the smooth proof which is the product of continual   
35:07   
feedback and control. So, this is a first draft of this paper.   
35:15   
I think it's probably uh I don't know what we're going to do with it. Uh I just wanted to get it out   
35:22   
before the symposium so that we have something to advertise   
35:28   
um and then build up. Okay. Uh why don't we do a paper um   
35:36   
before we conclude for today. So this paper is called control across scales   
35:42   
signals information and adaptive biological mechanical function. This is from the archive   
35:49   
and it's uh uh from the nonlinear dynamics group at the department of   
35:55   
physics at UT Austin. So they're interested in sort of a   
36:01   
physics approach to control and thinking about many different types of systems   
36:06   
much as we have been talking about in the cybernetic imperatives.   
36:12   
So the abstract reads biological systems perform an astonishing array of   
36:17   
dynamical processes including development and repair, regulation,   
36:23   
behavior, and motor control. So there's this wide variety of behaviors that are   
36:29   
kind of incorporated into this um sensing and signaling and adaptation   
36:35   
among others. So a whole range of behaviors across different types of systems   
36:41   
powered by the transduction of stored energy resources. These behaviors enable biological systems to regulate   
36:48   
functions, achieve specific outcomes, and maintain stability far from   
36:54   
thermodynamic delivery. These behaviors span orders of magnitude in length and in time.   
37:01   
So from nanometer scale molecular motors driving morphagenesis to kilometer scale seasonal migrations   
37:09   
and from millisecond reflexes to millennia of evolutionary adaptations.   
37:14   
While physical laws govern the dynamics of biological systems, they alone are insufficient to explain how living   
37:21   
systems sense, decide, adapt, and ultimately control their dynamics. So   
37:27   
this is kind of where we're going with um some of these imperatives building   
37:32   
upon each other. So um in this case, you know, we're   
37:37   
talking about this gap between physical laws and how they sort of describe   
37:44   
um sort of dynam biological systems as dynamical systems, but it doesn't really   
37:51   
describe say the internal state or the internal components of such a behavior.   
37:56   
So behavior is generated in a diff far different way than we understand how to analyze it. In this article, we argue   
38:04   
that control theory provides a powerful unifying framework for understanding how biological systems regulate dynamics to   
38:13   
maintain stability across length and time scales far from equilibrium. So this is a physics approach to a similar   
38:21   
type of you know problem that we talk about in the cybernetic comparable.   
38:27   
And so um their focus is on biological mechanics although they can take   
38:34   
inspiration from a large number of systems. So they start off with talking   
38:41   
about the kinds of behaviors that physics can compactly describe. So for   
38:48   
example uh they talk about different types of behaviors of say like throwing   
38:54   
a baseball or the behavior of a commercial airplane as it takes flight   
39:00   
or how bicycles can roll and exhibit behaviors in that way. And so these   
39:06   
different types of behaviors are well described in the laws of physics. But there are all sorts of other um   
39:13   
motionbased behaviors that are maybe less uh des you know well described by   
39:20   
physics. And so um they point out here that biological mechanics is ultimately an   
39:26   
inherently a non-equilibrium process at the molecular scale. active   
39:32   
chemomechanical proc cheanical processes convert free energy reserves to   
39:37   
mechanical work. A major example is of course molecular motor behavior. So   
39:44   
meiosins, kines and vin which hydraize ATP to generate sliding   
39:50   
motion within the cytokeleton network of biological polymers.   
39:55   
Now, how do motors at around the 100 nanometer scale drive mechanics on the   
40:01   
cellular and organismal scales, which are usually around 10 microns to 1   
40:07   
meter? And so, we can turn to condensed matter physics to find those descriptions,   
40:15   
but you know, we we want to consider these as sort of part of a larger class   
40:21   
of behaviors. So on the left we have these different types of systems that produce motion   
40:28   
through animal cells and analogies of animal cells. Uh so we have this control   
40:34   
signal and then we have the system described by uh gxu. We have the control   
40:40   
signal u. So we have some examples here. We have a molecular motor which drives   
40:47   
motion in a cell. We have a motor neuron which drives motion in a human. soccer   
40:53   
player. We have a joystick which drives motion in a robot. And so this control   
40:59   
signal U is moving the system forward.   
41:04   
Then we have this second class where we have sensory systems and how they drive   
41:10   
controllers. So we have the sensory signal Y and the controller KYR. And so   
41:16   
here we have this gated ion channel that controls a network of interactions.   
41:23   
We have this uh   
41:32   
we have axonal conductance which controls dynamics in the brain. And then we have   
41:39   
this control signal or the sensory signal for an autonomous vehicle which   
41:44   
controls a microchip and a microcontroller. So this is these are just different instances of the sensory   
41:51   
signal being used to control the system. Then the third category we have fuel   
41:58   
which is uh delta G and an actuator which is w delta G. So we have this fuel   
42:04   
which uh exhibits a change in these different types of systems. So we have   
42:11   
this fuel which fuels this molecular mo motion that then contributes to both   
42:19   
plant and animal movement. Uh we then we have this electrical   
42:24   
um source which fuels an electrical motor. So we have these different   
42:30   
sources of fuel ATP and electricity and they fuel these different   
42:36   
uh you know movements in different systems through actuation.   
43:10   
So they actually do some things feedback and control here. So they have this um   
43:17   
these different time scales. They have the mechanism time scale, function time scale, the learning time scale and the   
43:23   
adaptation time scale. And this gives us some uh you know   
43:29   
additional sort of control systems and cybernetic uh motifs to work through. So the first   
43:36   
one is a mechanism time scale and that's characterized by feed forward control. So feed forward control occurs over the   
43:43   
time scales inherent to the physical mechanism which controls systems from the controller K influence the system G.   
43:52   
And then feedback control is where you have controller K uh influencing the   
43:58   
system G but then the system G influencing the system K through   
44:03   
feedback. So this is at the function time scale. So you think about the mechanism. The mechanism is something   
44:10   
that is sort of a driving force. So you might have a a chemical reaction where one   
44:17   
thing influences another. Feedback is where that thing that's influenced then in turn influences the thing   
44:22   
influencing. So it's kind of like a rate limiting or self-limiting process.   
44:29   
Of course we know the differences in terms of feed forward and feedback as in   
44:35   
this case it's you know building upon the complexity of that behavioral system.   
44:42   
Uh then we have adaptive control. So adaptive control is where we're at the learning time scale. So of course K   
44:48   
influences G and then G in turn influences K. But you have this integrator which then helps K learn. So   
44:56   
it's it's this uh purple circle that's an integrator and it integrates feedback   
45:02   
in different ways to give K different granularities of information about the   
45:09   
system G and then adaptation time scale which is where you have physical adaptation   
45:16   
rather than adaptive control. You have of course your adaptive control through   
45:22   
um we have uh like a gray circle which is   
45:28   
of course uh integrating um the feedback from G to K and that's   
45:36   
influencing K but then we have another integrator which actually influences G.   
45:42   
So this is uh G being influenced by the feedback that it's giving to K. So this   
45:48   
is the difference between learning and adaptation. Learning is where you have feedback that is sort of supervised and   
45:56   
then adaptation is where that supervised feedback is then influenced by changes   
46:02   
in G. So you can adapt to different conditions. Um   
46:08   
and so this is uh what they kind of consider   
46:13   
different larger time scales like evolutionary time scales or population   
46:18   
time scales. And so it's a it's it's an interesting way to represent these   
46:24   
different things because you know again you have like kind of this cybernetic system although they're thinking about   
46:30   
in terms of a control system and um how that those uh different levels of   
46:38   
acquisition behavior structured. Okay, so that's all for the updates for this   
46:43   
week. Thank you for paying attention and see you next week.   
   

