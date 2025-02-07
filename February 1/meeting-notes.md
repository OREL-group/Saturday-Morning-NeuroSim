## Meeting Recording

[YouTube link](https://youtu.be/x2G9Qgo9uDg)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113932117938700954)

## NOTES:

Metascience — Project Management for Lablife (or LabOps).

modeling relational diagram, somatic anticipation.


Morgan — number of DeepSeek papers, related items.

PNAS paper that covers CogSci of humans and LLMs.

Mechanical Turk and LLMs.

Michael Levin @ Wolfram Institute.

Radical Gradualism — cognition is in a lot more places than you think.

GRNs have learning behaviors — six forms of learning.

are we defining “cognition” in a way that is too broad to be useful? Does the weather have cognition? You could test it.

* PNAS Nexus paper (McClellan).

covering reasoning in LLMs. Logic tasks, syllogisms, varying content (words).

will you see something as true? Cognitive development —> use nonsense words as grammatically correct.


Computer Engineering vs. Training Choices.

efficiency — directed RL training. 4-5 reasoning LLM models. 

test models — do they match reasoning abilities? Even humans fall into traps.

look @ how LLMs are being constructed for reasoning.

cognitive architecture theory, break problems down into smaller parts.

use as goals, deep algebra (Karpathy training on OpenMath textbooks).


Structures built on structures.

San Fran Data Science. Data science created by the tech industry.

NN optimization is a career. MLOps of LLMs. Computational Physics model. LabOps, ResearchOps, ModelOps.

working on reasoning problems. Support stratification, reasoning models are overkill.


ActInf textbook — Josh Bongard’s bots (toward BioBots). Simple Structures —> basic agent development, follow world models — rules for swarm robots.

World Model carved at its joints. How to get something that is an easier code, introduction to world models.

how to get something that is an easier code, introduction to world models.

“Inference as Planning” — connect Acting and reasoning behavior, sequential operations.

World Model — how far ahead can model think, plan.

Addius (2002) — Probabilistic Inference conference.


3 brown, 1 blue: transformers. Use RxInfer as replacement for SPM.

Lampinen et.al — CogSci and Tech —> thinking about evaluating outputs of LLMs.

understand model abilities, depth, expressivity.

more than transferring tasks from humans to LLMs.

designing evaluation — go beyond LLMs. Use math because you know what answers are. How do you check?


Charles Martin — Field Theory (Chicago), renormalization —> Weight Watchers —> Condensed Matter Physics (train absent of data). 

building inference tables. Open-endedness, building new relations.

Emerging Reasoning with Reinforce. Learning is both effective and efficient.

operationally, what does a world model mean? Link to inference as planning. Game examples —> leading in the wrong direction. Link to inference and planning.

Sequential planning has no evolutionary value in and of itself. 3D world vs. more abstract planning. 

Rosen — nothing to anticipate? Active — agent in a rich environment.


Models —> DeepMind-like —L shared models —> Quake 3.

SciCode paper. Github, integrated with inspect-ai (safety).

LORA, Transformer-squared. DeepSeek underpinning, relate to ActInf, RL.

deep multi-task and meta-learning.


Yann LeCun —> Hinton and LeCun —> AI is conscious vs. decade of robotics.

produce robotic behaviors (ROS, Sim2Real).

Chris R. Reid —> ActInf —> slime models and Philosophy.
MLOps of LLMs. Monetary value of what you are spinning up. Make a prediction about the next token.

* finding interesting areas in a super high-dimensional space, and ignore other areas —> distillation. AI safety framework —> cross-model evaluation.

## TRANSCRIPT

0:03     
hello how are you     
0:10     
today okay um well welcome     
0:15     
uh so this week we had we were supposed to have two meetings we only had one we     
0:21     
had the D.A War meeting and uh that went pretty     
0:26     
well and then we were going to have our cybernetics meeting but we cancelled for     
0:31     
this week again scheduling conflicts     
0:36     
so that's where we're at let me start with a few items here so the first thing     
0:42     
I'd like to point out is I think I did this about two weeks ago this is a post this is from the lad     
0:50     
medium this is a post on Diva worms video archive so evil worm has been active for     
1:00     
over 10 years now but we have a video archive that goes back to the beginning of     
1:06     
2020 that's when we really started recording the meetings and putting them out into um production like that so we     
1:13     
have you know four years of archives at least we also have the videos from the     
1:20     
uh Deva worm AI uh study group in 2019 so it kind of     
1:25     
goes back a little bit further but largely you know before that we were     
1:30     
just recording special lectures and things like that but now we record the     
1:35     
whole meeting for Better or For Worse I guess uh but the sort of the upshot of     
1:40     
that is that we have a lot of archives and you know we can transcribe     
1:46     
these videos and we can dive deeper into some of the topics that we've covered so I've     
1:53     
been creating uh transcripts for these videos uh so you know we have the that     
2:00     
information as well and I'm going to try to analyze that uh Archive of     
2:08     
transcripts you know at some point maybe we'll write a paper on it and see what     
2:13     
we have in terms of our different topics it's a very exciting uh format I think     
2:18     
we have people who are welcome to present on their own research we cover a     
2:24     
lot of cutting edge papers uh maybe do some technical demos     
2:29     
things like that so it's always you know always good stuff so just seeing what we     
2:36     
cover over time it would be very interesting because it's kind of hard to keep track of all     
2:43     
that the other thing is of course we have a lot of tie-ins between     
2:49     
dorm and something I'm calling computational developmental systems so     
2:54     
I'm kind of including the stuff we're doing at Diva worm some of the stuff we're doing with the computational     
3:02     
Psychiatry and some of the stuff on critical periods as well so you know we     
3:07     
have a lot of things that we haven't really kind of you know kickstarted that     
3:13     
hasn't been active and I'd like to see that happen under this Banner a lot of things that     
3:19     
we do in dorm that are sort of natural tians to what we're doing in this group or in in you know the context of the     
3:29     
computational agents or uh things like cognitive science or Neuroscience or     
3:35     
whatever and so I wanted to sort of Kickstart some of those connections more     
3:41     
explicitly though Diva worm started outside of our organization here and it     
3:47     
hasn't really been fully integrated into the organization so I've been trying to do that for several years actually you     
3:54     
know trying to get people to sort of pick up those connections as well as     
4:00     
myself uh we've been doing some of that but not as much as we could so I'd like to sort of foster     
4:06     
that so this this uh post is just kind of an introduction for people who are     
4:12     
not familiar with the diva worm meetings to interact with our video library and     
4:18     
this is on the uh dorm YouTube channel so this is a separate YouTube channel just for     
4:23     
dorm uh and it has all the meetings and it has other thing other content on that     
4:29     
channel too so we have small tutorials that I've done we've had tutorials that     
4:35     
uh Google summer of code students have done and you know things like     
4:42     
that okay so the next thing I want to talk about     
4:49     
is this is something I think uh Morgan posted in the slack this is a Robert Rosen um     
4:58     
repository I guess it's say estate this reminds me of the thing that     
5:03     
they did with WR Ashby's work um where the estate created     
5:09     
this it's a website I don't exactly know what the address is but they created an archive of Ashby's notes Ashby's well     
5:17     
known for have taken a lot of notes had a lot of like working papers and things     
5:22     
like that so they were able to publish that you know uh after his death and I     
5:28     
think the same is true for Robert Rose so Robert Rosen of course was um you     
5:34     
know he did a lot of theoretical biology he did a lot of things with     
5:39     
system science physics uh so is really     
5:44     
interesting uh work and of course he's well known for his work on relational     
5:50     
systems and relational biology so this is this is the     
5:56     
repository let's see uh let's explore the collection a little bit so this is just kind of set up so     
6:03     
you can search 233 papers I guess um and goes from 1950 to 1998 so pretty long     
6:12     
career um so this is kind of talking about some of his so he's done work on     
6:19     
structural stability he did work on uh bifurcation diagrams complexity     
6:27     
Theory um surface mod Ting assemblies uh field Theory and     
6:35     
thermodynamics a lot of stuff in applied math and then relational biologies that     
6:42     
was one of his big areas um some early computational     
6:48     
work um yeah so this is really interesting     
6:53     
category Theory even I think so yeah this is and I think he was at the University at Buffalo in New York or I     
7:01     
guess also the University of Chicago so he that's where he was in the world and     
7:07     
then of course he was engaged in all these different types of research uh so you know we we talked     
7:14     
about relational biology in the cybernetics group we've talked about it in the DOR group I don't know if we've     
7:21     
ever really kind of gone through something like a book that might be     
7:26     
interesting because just getting like some perspective on Network might be very interesting     
7:32     
especially I think we talked once about MR Systems uh it was again a cybernetics     
7:39     
meeting so there's a lot of interesting stuff here both in the cybernetics area     
7:45     
also in the theoretical biology area it might be worth going through this and     
7:51     
seeing what's you know because I i' had never seen all his work in one place     
7:57     
before okay so yeah this is this is great he lived from 1934 to     
8:02     
1998 and there he is as a child at his PhD in relational biology     
8:08     
at the University of Chicago I'm assuming that that was kind of his own     
8:16     
degree uh Nicholas rashevsky was his uh advisor I this is another person who's     
8:23     
interesting Nicholas rashevsky um he did a lot of early stuff on theoretical     
8:29     
biology too and so it might be interesting to look at like what was going on there theoretical biology     
8:36     
biophysics sort of that interface and so yeah that's kind of the     
8:41     
idea um so yeah and and you know again this     
8:47     
is stuff that we kind of cover in Diva worm kind of cover in our cybernetics     
8:54     
group yeah so they actually at Sunni Buffalo they called it at the time     
8:59     
Buffalo it's University at Buffalo um he they had a center for     
9:05     
theoretical biology I guess that's they still I don't know if it still exists but that's kind if you don't see that     
9:11     
very often so that's an interesting point here um and then he moved on to Santa     
9:17     
Barbara or this institute in Santa Barbara the study for Democratic     
9:22     
institutions where he began to develop the foundations of anticipatory systems theory so this is the thing that we've     
9:28     
been kind of focused on in terms of his work in the lab and kind of thought about this anticipatory aspect     
9:36     
of um organisms and biological     
9:41     
systems so this is you know again a lot of things having to do with the good regulator theorem having to do with uh     
9:49     
you know the predictive nature of you models within a biological     
9:56     
system being able to control your behavior and anticipate environmental     
10:03     
change so it's really really cool um so thank you Morgan for posting     
10:11     
that okay so then I also want to talk about this Workshop um so this is I I guess     
10:20     
from this year's NS and this was a workshop I was zor     
10:27     
Benjo and some other people deal rousi uh some other people in the field     
10:35     
and this is nuro AI using neuroscience and AI for intelligence Solutions so     
10:41     
this is kind of like a neuro AI uh you know it's it's basically you     
10:48     
know has some good neural AI stuff in here so uh the abstract of this Workshop     
10:56     
examining the fusion of Neuroscience and AI this Workshop aims to unlock brain inspired     
11:02     
algorithms while advancing both biological and artificial intelligence so their focus is on     
11:09     
algorithms and different types of intelligence and you know kind of fusing     
11:15     
neuroscience and a so let's see um there are some videos here uh this     
11:22     
looks like this is the whole session unlocked so this is eight hours of     
11:29     
you can see the video over on the side here different     
11:35     
talks kind of going through some reinforcement learning the causal cone     
11:41     
uh waves in the cortex different types of topological     
11:49     
spaces for looking at neural activity um equivariant expressed in     
11:56     
capsules in space so some good uh like their topics in computer science and     
12:04     
craft neural networks uh waves as     
12:09     
memory how to build abstractions which is interesting and this is in the context     
12:16     
of the brain not necessarily in computer science so you have this kind of     
12:24     
discussion of feature binding for Moto oscillators     
12:30     
uh competitive learning different types of learning and then uh information     
12:35     
bottlenecks and re normalization so different tools from computer science and physics different tools from     
12:43     
complexity Theory and applied math and then different views of learning where     
12:49     
you can you know you have to have sort of a policy where the system to     
12:55     
learn uh this one here adversarial robustness     
13:01     
and calibration some different approaches to systems looks like a panel     
13:06     
discussion with Carl friston uh yosua Benjo and adal     
13:11     
rousi uh kind of going through I guess some of the topics here a definition of     
13:17     
merrow AI and there was a Q&A which you know I     
13:23     
mean you probably check that out on your own so that's interesting stuff um     
13:30     
yeah so I'm not going to go through all of these talks but you know well let's talk a     
13:36     
little bit maybe look at the posters and see what people were doing here so you have all sorts of different interesting     
13:43     
topics here here's one need is all you need homeostatic neural networks adaptive concept     
13:50     
shift uh dietic learning and recurrent and feed forward     
13:55     
models this's one here brain in the dark design principles for neurom mtic inference under the free energy     
14:01     
principle so some free energy stuff uh this is a population     
14:06     
Transformer learning population level representations of inter cranial activity that kind of sounds     
14:13     
interesting uh multiple temporal credit assignment rules achieve comparable neural data     
14:20     
similarity the brains bitter lesson and of course we know the bitter lesson from     
14:26     
uh reinforcement learning in Rich Sutton scaling speech decoding with self-supervised     
14:33     
learning uh this one neuro asroy associative memory here's one on hierarchical     
14:41     
control which we talked about hierarchical temporal control last time and kind of how that sort of Paradigm     
14:49     
operates this is hierarchical control of reaching movements via compositional gain     
14:55     
modulation uh this is homeostasis of where direct Spike     
15:01     
encoding uh RNN replay leakage and under dampen     
15:09     
Dynamics this is one on prospective learning learning for a dynamic     
15:15     
future uh not so gritty internal representations of uh recurrent neural     
15:22     
networks path integrating more than one agent so this is on path integration which is a form of spa cognition glad to     
15:30     
see that because I worked with a colleague on a on some path integration     
15:36     
work a long time ago and I got familiar with the field and seeing what that     
15:42     
looked like and it's interesting because there's a field of spatial cognition which focuses on     
15:48     
Hippocampus and spatial memory and then there's path integration which focuses sort of on a     
15:54     
phog genetic approach and you know mechanisms that     
15:59     
are not necessarily in hippocampus so this is kind of an     
16:05     
interesting kind of approach yeah so this is liquid capacitance     
16:13     
networks um and I think that's about it I think there's a lot of really     
16:20     
interesting work going on a lot of sort of technical work that's really     
16:27     
Innovative it's nice to see um and say yeah I leave that to people     
16:33     
to explore in their     
16:39     
own all right so let's move on to uh this     
16:46     
document this is something that I prepared I think at the end of last year we've gone through it actually this is     
16:53     
something we prepared several years ago but I prepared the 2025 version of this     
16:59     
so this is a list of potential submissions and their destination and     
17:06     
their due dates so for example you know this Google summar code project descriptions     
17:12     
entry this has been taken care of I sent off the descriptions this week to incf     
17:19     
and they're going to publish them and see what kind of Interest we get and the two projects for this year are the deor     
17:28     
graph project which is a followup on the work that we're doing on graph neural networks and     
17:35     
um other types of graphs last year so we had two projects last year and we were     
17:42     
building infrastructure for that and we're going to continue on with that and     
17:49     
then of course the open source sustainability stuff so we're going to either continue down the road of     
17:54     
reinforcement learning or continue down the road of integrating agent-based models and large language     
18:01     
models so those are our two projects that are published now the deadline     
18:06     
internal deadline for that is January 15 that's for in cf's organizational     
18:12     
application and then later on will have uh the ability to kind of change the     
18:19     
wording of things and then you know the the application period opens in I think     
18:26     
early like mid-march or something that maybe early April I think we make the SE     
18:32     
have to make the selections by May 1st or something like that but basically that's our timeline so if people are     
18:38     
interested in working on a project they can uh I think I have them on     
18:46     
our uh GitHub repository Sil     
18:55     
me so we have a GitHub repository for G sock through the oral     
19:02     
group and I did update this for 2025 so our projects are up on the GitHub     
19:07     
repository github.com or L group gck The gck repository and we're going     
19:15     
to follow up on daph and follow up on open source Community     
19:20     
sustainability and so you know there we have some uh median posts if you're     
19:25     
interested in following up on this work I have the post the introduction     
19:31     
to uh the llms and open source sustainability and then developing     
19:37     
adaptive neural networks these were from two of our students here Pocky did the     
19:43     
Adaptive neural networks and of course Sara did the large language models open     
19:48     
source sustainability so if you want to know more you can click on those links we     
19:54     
also have a history and alumni page for gck students that's uh that should give you some idea     
20:01     
of what we've done in the past so a very very credible sort of group to work     
20:13     
with Okay so that's uh Google summmer of code this one here the Nick Wick uh     
20:19     
submission that has also been completed at least the version that was submitted     
20:24     
by Jesse uh so I think he's submitting for another one of the smartest boards     
20:30     
where you know he has a bunch of people talk on uh one or more     
20:35     
topics uh he's going to see if it works out so I don't know what the scheduling will look like on that but again we'll     
20:41     
be working on that further into the year as we go um we have two kind of two deadlines     
20:50     
or maybe more deadlines coming up so there's the deadline for meta science 2025 they have a virtual pre-conference     
20:57     
that they host online because I think the main conference is in Australia I'm     
21:03     
not sure where it is this year but there's a virtual pre-conference and I'd like to Target that for     
21:10     
submission um I'm not sure what it's going to be at I I I posted a an inquiry     
21:16     
in slack I just wanted to see who was interested and I had a few responses but I haven't we haven't any discussions     
21:23     
about this so this is something that's coming up um pretty Prett quickly uh we     
21:30     
have to have something in by February 7th so I might try to raate something up and see where it goes if it gets     
21:37     
accepted whatever and then the event is June 30th through July 2nd so it's     
21:44     
online um and it's metascience doino if you're interested in submitting     
21:51     
something to that you have to get it abstract in by the 7th and I think it's for just a talk I     
21:57     
don't think there's a paper so this is coming up pretty quickly and     
22:03     
then the uh sips which is the society for improvement of psychological science     
22:09     
they have a virtual component as well you have to submit your abstract by     
22:15     
February 14th and that event is May 21 through the 22nd so that's going to be and I think     
22:23     
what they're looking for there is like a workshop so I'm not sure if that's something we want to do uh that's going     
22:30     
to be a little bit more involved in the metascience submission and it might be like two aspects of the same submission     
22:37     
and I'm not really sure I got to figure this out pretty quickly I guess so I don't know if that'll happen but we'll     
22:44     
see and then there's this embodied intelligence Workshop of course which happens every year this one will be on     
22:52     
March 1st the deadline for this will be March 1st so I have some things that     
22:58     
will be submitted on on that front uh you know basically have to     
23:04     
figure out which thing that we're working on will be good for this uh write up an abstract for and put     
23:11     
it in and so that the deadline for that is March 1st the event date is April 2nd through 4th and that's also     
23:18     
online so uh you know with embodied intelligence if you register you you can     
23:25     
submit one abstract so if you're interested in cementing an abstract please do so and just make sure that you     
23:32     
show up and present because you know we've had some issues with that in the past where people can't make the time we     
23:40     
haven't you know we've had like presentations that were kind of recorded     
23:46     
and then forgotten about so it's like you know it's it's usually good do when     
23:52     
you put in an abstract to attend the actual meeting but anyways you know     
23:57     
that's we've been working on this very rich vein of Developmental neuros     
24:02     
simulation for several years now and going to this conference and presenting on it and putting out papers uh related     
24:10     
to that work so it's it's really been a a valuable     
24:16     
experience so we'll try to continue with that in 2025 and see where that     
24:23     
goes um yeah actually I think I should put out a blog post on that stuff so I don't     
24:30     
think we've gotten the sort of the benefit of like looking back on it seeing where we've     
24:37     
been all right so I'd also like to highlight Hussein's work on uh is that MIT reality hack we     
24:45     
talked about that last week um so he's was very excited about     
24:51     
his project so let's look at it so this is H the I think the headset     
24:59     
that they're working on here this is um this is screenshots it's not going to     
25:04     
show the video but I think it's just showing this this is a uh I guess it's     
25:10     
an EG headset over Quest 3 it's like the quest 3 is here then you have this     
25:18     
headset sort of skeleton and it's kind of sitting over     
25:23     
the top so this is the open Goa and this is a post from reality hack     
25:30     
Incorporated who's organizing MIT reality hack so this is team open     
25:37     
Goa and this is summary of the project this is something post to the slack this     
25:42     
is Hussein ather something he posted in the slack so says uh we made this cool     
25:51     
custom fully open source multimodal headset inspired by open BC eyes GAA     
25:58     
built from the ground up we wanted to merge real-time brain wave sensing with immersive arvr     
26:05     
experiences for a new level of ring computer interaction with eg EMG and advanced     
26:12     
machine learning models our project aimed at a code neural activity and     
26:17     
translated into meaningful interactions in arvr so of course EEG is the brain wave     
26:24     
activity EMG is the muscle activity and a people will record EMG to either get     
26:31     
some like corresponds with some muscle that's involved in some specific movement or they'll use it to cancel out     
26:39     
muscle artifact from the EG so there's a value to getting those multiple     
26:46     
measurements the core concept here is you have realtime interaction using EEG     
26:51     
data with the ability to detect and adapt to user States like relaxation and     
26:57     
focus uh that's the core concept so you're really trying to detect different user     
27:04     
mental States so sometimes if you can identify those States or the Edy cor out     
27:11     
of those States then you can sort of you know incorporate that into the content     
27:18     
or you can use that as an interaction uh mode of interaction so     
27:23     
you can use that as a way to sort of queue in on things in the environment or     
27:29     
you know use that as like sort of a way to select uh from a menu or something like     
27:37     
that uh the features here are Hardware prototype the headset combined with a     
27:42     
Unity based arvr set of interactions so it's this interface and then the headset     
27:48     
and then the recording um electrodes that you could see there was a framework for them on     
27:56     
top uh you had pop culture inspiration drawing on ideas from Pacific Rim X-Men     
28:03     
cerebro even elements of Neo Neon Genesis evangelon we imagin the future     
28:09     
where neuro adaptive arvr could enable incredible human machine     
28:14     
collaboration so they had a nice process here over three days we talked about     
28:20     
this last week that you know they have like this introductory session and then they work on a project for a couple days     
28:27     
and in different teams so in day one they finalized the idea for open GAA     
28:33     
drawing inspiration from open BCI tools but building her own unique     
28:40     
design they began 3D printing the headset components using Ultra cortex inspired designs balancing functionality     
28:48     
with Aesthetics then they set up the unity environment and integrated EG signal     
28:54     
processing Frameworks day two then focused on machine learning training models like EG     
29:00     
net and Inception time on the physionet EEG motor imagery data set to decode     
29:07     
focus and relaxation States so you have to have some sort of Benchmark for this this they we're trying to work on     
29:14     
here implemented multiplayer AR VR interaction and unity with real-time brain wave States influenced     
29:21     
environmental effects like flowers blooming or the growth of a virtual     
29:26     
garden and enountered some challenges of environmental variables tensorflow GPU     
29:32     
issues and data processing tackled them with persistence and quick thinking they had to improvise in some     
29:39     
of their activities um and of course here a lot of challenges in this because you have a     
29:46     
lot of moving Parts you have the machine learning algorithms you have the recordings you have the um sort of the     
29:53     
interface and the content Realm of the headset so it's all stuff that's you     
30:01     
know even like if you were to do this on a a desktop or a phone you would have     
30:07     
maybe a a little bit better characterized computational envirement     
30:13     
so all these things are challenges because you know I don't think there are     
30:19     
too many standards floating around for integrating these uh day three assembled the final     
30:26     
Hardware prototype and complet our VR AR demonstration so they did a demo made a     
30:33     
demo captured and edited the project video using OBS and mavi showcasing both     
30:39     
the technical details and immersive experience of open Goa basically they made a video of     
30:46     
this submitted our project along with thorough documentation code repositories     
30:52     
and an engaging narrative so they were able to achieve an accuracy of 86 to 88%     
30:59     
they overcame their technical roadblocks and developed an fully open source     
31:05     
platform um and so what they learned elaboration is key resilience pays off     
31:13     
respect the competition so there were a number of different uh related projects uh and     
31:20     
then celebrate progress okay yeah so this is great um     
31:26     
thank you Hussein for that summary detailed summary of what happened at your     
31:33     
hackathon at MIT and it looks like you learned a lot of things along the     
31:39     
way all right now I'd like to go back to our slack channels but instead of going     
31:44     
through single channels and going back to maybe three months in time I'd like     
31:51     
to highlight some things that have been posted recently in slack things that I found you know interesting but really     
31:58     
things from last week so this first one here we talked     
32:05     
about um the rosen's uh relational biology and pl his work on anticipatory     
32:13     
systems and this is from complexity digest which is a a     
32:19     
weekly U mailing list that where they put together links to different resources in complexity science     
32:29     
uh this it's actually hosted uh from the UNAM in Mexico City and it's Carlos     
32:36     
penson's group that puts this out so they're um this is actually I think an     
32:42     
event they're hosting at their institution so this is the International     
32:47     
Conference on anticipatory systems in rosenan complexity which I guess is     
32:54     
reference to rosen's work uh this is going to be in May 22nd and 23rd of     
33:01     
2025 this will be at un am in Mexico City um so this call reads a national     
33:10     
autonomous University of Mexico or UNAM by it's research group on philosophy of computing is proud to     
33:17     
invite you to participate in the International Conference on anticipatory systems in resan     
33:23     
complexity so inaugurated by Dr Robert Rosen     
33:29     
anticipatory systems theory deals with house systems with the ability to     
33:35     
anticipate model and act on future States this conference aims to address     
33:40     
anticipation and its many forms including its philosophical biological     
33:47     
cognitive and technological Dimensions this year 2025 will also Mark     
33:53     
the 40th anniversary of the original publication of rosen's anticipatory     
33:58     
systems philosophical mathematical and methodological foundations so this is uh     
34:04     
I guess this was published in 1985 uh this is the book on anticipatory     
34:10     
systems I think we may have kind of at least gone through this superficially at some point again Diva but we haven't     
34:18     
like I said we haven't done a chapter by chapter sort of review of of anything by     
34:24     
Rosen that's something maybe we should Target for this year since it's the 40th     
34:29     
anniversary of the book so I don't know uh this conference is focused on Robert rosen's IDE and Notions of Life     
34:37     
complexity modeling in mind word at anticipation. film.org and     
34:44     
if we go to the website we'll see that like this is the call for     
34:49     
involvement actually there was an International Conference organized by Dr Roberto FY in 2015 this is the 30th     
34:57     
anniv uh we welcome contributions in but not limited to the following areas     
35:03     
philosophy of science cognitive science theoretical     
35:09     
biology foundational mathematics and relational biology complex     
35:16     
systems medicine artificial     
35:21     
intelligence and climate crisis and kind of thinking about the     
35:28     
anticipatory systems theory in all those domains it's worth thinking about the     
35:33     
you know what's going on there and how you know we     
35:39     
might uh synergize with what's you know if if we kind of think about the topics     
35:45     
it might guide us in our explorations of the and then the welcome message from     
35:51     
Judith Rosen uh people often ask me what aspects of My Father Robert rosen's scientific work uh I think are most     
35:59     
important in one sense it's a tough question to answer each aspect is connected to every other so this is     
36:07     
basically some of the topics here Robert rosen's work uh connected to this topic     
36:13     
of complexity versus simplicity so when you disassemble a     
36:20     
system you know how does that relate to the complexity of the system this is kind of related to to uh     
36:29     
sort of reductionism and complexity two life is not caused by the     
36:36     
components but by the system organization so there are no building blocks of life the causal foundation for     
36:42     
life is the same as complexity system organization um three the type of     
36:49     
complex system organization that causes life waso incorporates the entailment embodied in my father's modeling     
36:56     
rotation diagram in an active form so there was this model or modeling     
37:02     
relation diagram not modeling rotation diagram uh so this is where he did     
37:07     
modeling of relational systems and that's I mean if you've ever     
37:13     
seen the diagrams in a couple of his papers he developed a diagramming system     
37:21     
for this uh     
37:28     
for the type of system organization that generates an anticipatory system and the modelbased model guided navigation     
37:35     
control strategies that characterize all life is what I refer to as somatic     
37:42     
anticipation so this is again the anticipatory     
37:48     
model where you know the idea is that there's some anticipation at different scales not     
37:55     
just like cognitive but organ isal cellular so     
38:02     
forth and so one of the things he focuses on is sort of the     
38:07     
self and the relation between the self and some of these systems so that's you     
38:14     
know leads up to this Mr type system which is the notation is M comma     
38:21     
R where m stands for metabolism and R stands for repair so this is a metab ISM     
38:27     
repair system where those two functions are coupled I've seen people do     
38:33     
variations of this where they do other types of coupled systems and I don't remember I think we     
38:41     
reviewed this type this whole sort of systems approach in a diva War meeting     
38:47     
and I can't remember which diva War meeting it was but I know that we discussed at least some of     
38:53     
this um so yeah this just something we'll come back to I think     
39:03     
the next uh paper and I think a lot of these are posted by Morgan so thank you Morgan for posting these this is uh a     
39:12     
distill article uh so to still was and I don't think they publish online anymore     
39:19     
but they used to publish these really nice interactive articles on machine     
39:24     
learning and this article is from 2021 so this is the distill article uh on a     
39:32     
gental introduction to graph neural networks uh so neural networks have been     
39:37     
adapted to leverage the structure and properties of graphs we explore the components needed for building graph     
39:44     
networks and motivate the design choices behind them so this is the interactive form of this article so these are the     
39:51     
diagrams here where it's showing you go from layer zero that project projects     
39:57     
and this is a single node in a graph at layer zero IT projects to two nodes in     
40:03     
layer one so this projects to this node here and this node     
40:10     
here actually it every time you hover over it IT projects to different neurons     
40:15     
but so let's see okay yeah now it's projecting to different neurons so you can see every every node     
40:23     
and layers are projecting to corresponding nodes and layer one then corresponding nodes in Layer Two then     
40:29     
corresponding nodes in layer three you can see that if I hover over     
40:35     
Layer Two it shows corresponding nodes in layer three and so on and so     
40:42     
forth so you see the the way it's structured here you have the different     
40:48     
uh you have the network in the different layers those nodes project to other     
40:54     
nodes and other layers and from that you get this structure that has both sort of layer     
41:02     
depth and then uh you know this topology of the static Network changes as you go     
41:09     
from layer to layer so there's another article     
41:16     
understanding convolutions on graphs that you might also check out this is uh     
41:21     
kind of convolutional neural networks put in a graph theoretic appro from a     
41:26     
graph thec perspective so they talk about graphs     
41:32     
and how you can build graphs from all sorts of things that are naturally connected so you know you don't want to     
41:38     
apply graph Theory to everything but there are a lot of things in the world that you can represent as graphs you can     
41:45     
understand the interactions between them model those interactions as edges     
41:50     
between nodes so the set of objects and the connections between them are natural AES     
41:55     
versus a graph researchers have developed neural networks that operate on graph data for over a decade uh     
42:03     
recent developments have increased their capabilities and expressive power and we're starting to see real world     
42:11     
applications so they in this article they divide their kind of review of modern graph Neal networks into four     
42:19     
parts the first is looking at what kind of data is most naturally phrased as a     
42:24     
graph second is to explore what makes a graph different from other types of     
42:30     
data uh then third we build a modern graph nural Network walking through each     
42:36     
of the parts of the model starting with historic modeling Innovations in the field moving from a barebones     
42:43     
implementation to a state-of-the-art GNN mod then fourth we provide a GNN     
42:48     
playground where you can play around with a real world task and data set so this helps us build a stronger intuition     
42:55     
about what those representations do for us so this is their uh sort of     
43:03     
interactive form of showing what a graph looks like um you     
43:09     
have vertices which are these nodes that's the technical term edges which are the connections between nodes and     
43:16     
then the global aspect of the graph which is the number of nodes are the longest path basically graph statistics     
43:24     
that you can calculate on these structures once they're fully fun and so you get a distribution of     
43:31     
these different uh of Vu so you get this triplet Vu and you can represent each of     
43:38     
those parameters with like a statistical     
43:44     
distribution and that describes the graph that describes the structure of the graph and the nature of the graph so     
43:50     
you're taking data from The Real World you're representing it as a graph you're building this triplet and then you're     
43:57     
visualizing it then you're getting the statistics and you can say something about the graph now you can make the     
44:03     
edges directional or undirectional and so that's that makes a difference in how     
44:09     
your graph statist what your graph statistics look like not every data set     
44:15     
or everything in the world is a graph obviously there things that aren't graphs but you can use graphs to     
44:22     
interpret a lot of things where you have a strong degree of interactivity you you can actually use     
44:28     
this to represent images and this is where they decompose an image with     
44:33     
different properties and they use like pixels in an image as the nodes and then     
44:39     
the relationships between the pixels as an edge so this is where you have two     
44:47     
pixels that are sort of diagonally connected actually you have pixels that     
44:52     
are fully connected with their neighbors so it's kind of like a a cellular automet type thing where you have a     
44:59     
neighborhood and that neighborhood are connected nodes then you look at their adjacency     
45:06     
Matrix so that's the strength of connections the strength of relation     
45:12     
between any two pixels and so you have this structure across the     
45:18     
image and you can see the adjacency Matrix on the in the middle and then the     
45:24     
corresponding graph on the right when you take the adjacency Matrix and you visualize it um so these the The     
45:30     
adjacency Matrix of these pairwise relationships and then they map to some     
45:36     
place in the graph so you can see that you're just taking the image the square     
45:43     
image made of pixels each pixel is is an is a node the edges connect the nodes     
45:50     
and so this is the structure of the graph it's basically just restating the image in terms of a Connect     
45:57     
model and so you can actually do this with text you can take like a sentence     
46:04     
break it up into tokens and then plot those the interactions between tokens so     
46:10     
the sentence graphs are all around us uh is represented in this Matrix down     
46:16     
here it says uh an adjacency Matrix and so we don't think of sentences being     
46:22     
networks but if you think about like if you were to sort of reorganize sentences into any     
46:29     
combination of words and any order so for example if you have the sentence graphs are all around us that sentence     
46:36     
makes sense because we we would put the words in that order and it makes sense to us there's a a syntax and a semantic     
46:45     
value to that Arrangement but if we were to uh     
46:50     
recombine the different words in their positions so if we said all around     
46:55     
graphs us our that doesn't make any sense at least to our ear and and so you know that's but     
47:04     
that's a possible set of connections between those words and so we have this     
47:09     
basically this sparse connectivity Matrix uh based on a a series of tokens     
47:16     
in a sequential uh list which is a sentence and it's represented in this     
47:22     
connectivity Matrix and we could also build a graph here where we just to have this directional connectivity in one     
47:31     
dimension so this you know this may be a little bit trivial in terms of the     
47:36     
Linguistics of it but it's act well not necessarily the Linguistics computational Linguistics it's not     
47:42     
trivial but uh it gives us the structure then that we can play with we can assign     
47:49     
statistical values to we can understand the sentence but uh so that's and then we have this     
47:57     
graph value data in the wild so we can look at a molecular structure so this is     
48:02     
where we have this 3D representation of a uh molecule and we plot this and we kind     
48:10     
of figure out the the structure we plot this as an adjacency Matrix and then we     
48:15     
can create a graph representation of this molecular structure we can do the same thing for     
48:22     
this caffeine molecule different molecule it has a different adjacent     
48:27     
Matrix and a different graph topology we can also build social     
48:33     
networks of course um this is the famous karate     
48:38     
Network this is a scene from the playoff fellow and it just shows like the     
48:45     
structure of who's interacting in those scenes and build you can build a network for     
48:52     
that uh and so they kind of get at this idea of what types of problems of graph     
48:58     
structure data we have graph level tasks which is where we take graphs as     
49:05     
input and then outputs are labels for each graph so we basically try to take     
49:12     
graphs once we visualize them and try to predict different typologies and what     
49:18     
they need so you know like if we saw a structure in nature we might be able to     
49:23     
predict that from the statistics with graph neural networks we're trying to do the same thing where     
49:29     
we have a graph and have different graphs and compare them and then try to     
49:35     
sort of categorize those graphs so we might say that like we might look at different motifs within     
49:41     
the graph like these Rings we might use that as a Criterion for sorting these graphs and saying that     
49:49     
can we find every graph topology with two rings so then we can actually uh you     
49:56     
know group those together as being like networks or graphs and these two graphs     
50:03     
are similar because they have a single R and so this is a lot like analyzing     
50:09     
motifs in complex Network Theory where you're trying to find different motifs     
50:14     
and and uh represent what those are okay so and then you have node level     
50:22     
tests which are uh where we want to predict the identity of each node or the     
50:27     
role of each node within a graph so here we have a graph with unlabeled     
50:33     
nodes and then here we have a graph of node labels that we predict so we're     
50:38     
trying to in this case we're trying to predict what the two hubs are and the identities of those two hubs so this is     
50:46     
where you have a social network with two people and those two people have a bunch     
50:52     
of people claim allegiance to them so they have they're highly connected and what you're trying to do is predict     
50:58     
these hubs from the structure of the graph so this is the karate club graph     
51:06     
where you have two hubs Mr high and John A and so you     
51:13     
can see that they're two we're predicting those locations from the     
51:24     
data and then the last prediction problem they present is Edge     
51:29     
prediction so this is where they're taking images and from the images they're     
51:35     
extracting information about interactions between people and the scene and and other objects in the scene     
51:43     
so you have this is a scene from a Karate Kid this is where you have Daniel     
51:49     
Johnny referee is watching these two are fighting they're standing on a mat and     
51:55     
you and the audience in the background so you're representing all these things in a     
52:01     
graph and so then you build this fully connected graph with unlabeled edges and     
52:07     
then the goal is to attach the sort of semantic information to graph where you     
52:13     
put labels on the edges and so it describes a scene it describes a relation between things and we can use     
52:22     
that as you know a way to sort of build     
52:27     
a model of interactions and maybe a model of prediction so this is a nice article it     
52:33     
goes over a lot of these different concepts and it has a lot of nice uh visualization aspects a lot of     
52:41     
connections between adjacency matrices and graph topologies and showing how     
52:46     
those are related so I like the way that they do the interactive aspect of     
52:51     
this um so this shows again how to represent Gra     
52:57     
as data structures showing the visualization and the relationship between the nodes edges     
53:04     
adjacency list and Global aspects of this so then they get into graph neural     
53:11     
networks they show kind of how this works taking things from graphs plugging     
53:17     
them into these algorithms and then you know you're doing things like predicting nodes     
53:23     
predicting edges predicting structure so this is U you know a lot of technical     
53:32     
aspects of graph networks talking about how we can use     
53:37     
message passing as a key uh part of understanding the Dynamics of graphs how     
53:44     
information is passed from one node to another and showing the distribution of     
53:49     
information the net message passing protocol so this shows aggregated     
53:54     
information from adjacent nodes this no here is taking in information or getting     
53:59     
messages passed from these other nodes upstream and so then you have this distribution of     
54:06     
information and you can actually use that that's that's how one way in which     
54:11     
refal networks are useful okay uh and then they have this     
54:18     
GNN playground here it is uh where they     
54:24     
have this I guess this is graph it's doing model prediction so if     
54:31     
we kind of have to select our inputs here we get a graph below on the left     
54:39     
and this I guess we're looking at a molecule um and they have the legend     
54:45     
down here and then this graph we're going to do some model prediction of     
54:50     
pungency versus non pungency so the structure of the graph will predict the properties of the molecule and then     
54:58     
you'll have this graph on the right which shows sort of the output of that     
55:05     
so let's see if I can run this um if I say size of     
55:12     
100 betting of 20 betting of 25 I don't really know     
55:17     
what these mean but I'm just going to play with it uh let's try different aggregation     
55:23     
functions so you can see that it's changing and the area under the curve is changing     
55:30     
model Au is changing and the depth four layers okay     
55:37     
so it's basically taking this graph topology it has different properties and it's going through     
55:45     
this uh basically uh going through the uh neural network and it's     
55:53     
analyzing the data and it's producing this output so we have this model of depth of     
56:00     
four layers A mean aggregation function and these parameters uh for the embedding and then we get this     
56:07     
help so you know this is something you can play with and get a sense of what     
56:13     
how this works okay and then this shows just kind     
56:18     
of a typical performance graph you know this is how you report the data so you     
56:24     
have the number of parameters versus uh the test area under the curve s for     
56:30     
pungency and then you're looking at sort of the performance metrics here and this     
56:36     
is what it looks like so this is all each of these this is a model     
56:42     
comparison you're getting different points have different uh values so just basically     
56:49     
running the simulation again and again and plotting out the results okay so     
56:54     
that's that paper um so this is really nice thank you Morgan     
56:59     
for that okay so this is another article I     
57:05     
think it was posted in one of the uh AI channels I think it was developmental AI     
57:11     
developmental murway I think we call it um and so this is from the journal     
57:17     
device which is a sell Press Journal and this is called magnetic     
57:22     
swarmm intelligence of mass produced programmable micro robot assembly versatile task     
57:29     
execution so the this is the graphical abstract where they're doing different     
57:35     
things these micro robot swarms such as lifting transporting and guiding so this     
57:43     
is where you have in lifting you have an high aspect ratio of the micro     
57:49     
robots you can bend them around different     
57:54     
dimensions you have then High packing density of different uh these micro robots where     
58:02     
they're packed together along two dimensions and then this High assembly     
58:08     
stiffness which is where you change the compliance of the micro robots that can     
58:14     
be used for guiding or full directed tests so I think it's interesting that     
58:20     
you can do these kinds of different things and result in different behaviors and activities so you have this     
58:26     
Collective behavior of these micro robots doing different tasks and you're doing things like     
58:34     
modifying the physical parameters to get these desired     
58:39     
results so this is the naan brief on the right here Yang it all present micro     
58:44     
robot worms that are mass produced through the Inu replica molding a magnetization on a single micro mode by     
58:53     
programming magnetization profiles a cub microbots microbots can be organized     
58:59     
into head to tail slip Co facial and face to face     
59:06     
assemblies micro robot swarms with distinct assembly features are deployed     
59:11     
to perform self-climbing self thrwing over an obstacle self-lifting on an     
59:17     
obstacle cargo Transportation wire connection and disconnection liquid     
59:22     
metal shape modification tube unclogging and organ     
59:27     
so these are different sort of tasks that they can do um so this is you know     
59:35     
I guess from these different types of assemblies they can get to these     
59:41     
ends so all they're using are these physical constraints they're able to get these different     
59:48     
behaviors and so this diagram actually is from a post on deep seek so this week     
59:54     
people have been talking about deep seek and sort of the how they're sort of a     
1:00:01     
lot better than what open AI is doing and so this is kind of showing the     
1:00:07     
architecture of deep seek this is an image that was posted in the slack um and so just kind of talks about     
1:00:15     
the architecture which has been sort of opaque to a lot of people so hello     
1:00:20     
Morgan uh how are you good thank you     
1:00:26     
um yeah sorry sorry for the delay here that's fine     
1:00:32     
um yeah I I I posted a number of kind of deep     
1:00:40     
seek um info papers     
1:00:47     
um and the University of San Francisco data Science Institute had a     
1:00:54     
um well there was there was a couple couple of events this this week that     
1:01:01     
were um llm related right so the     
1:01:08     
um buzz robot had an event with uh uh the lead author on this pnas paper     
1:01:18     
that that covered um you know cognitive science of     
1:01:26     
you know it's very much cognitive science of humans and llns yeah so uh I don't know if you saw     
1:01:33     
that yeah did you post that in the yeah it     
1:01:40     
um you know it doesn't fit well into categories so uh I forget where um I     
1:01:48     
think it might have gone into Data ml okay um just just because it seemed kind     
1:01:54     
of the llm related yeah I'm not not sure that's you know I I I don't think llms     
1:02:02     
and data science really have a lot to do with each other right well yeah but but     
1:02:08     
yeah yeah I guess yeah um     
1:02:13     
um interesting paper you know was very cogy or you know what what the guy was     
1:02:19     
presenting on was very coogy and and this is one of those     
1:02:25     
combined like um I'm going to um I'm     
1:02:30     
going to experiment with Mechanical Turk     
1:02:35     
people and and llms oh okay right so you     
1:02:42     
know and he made some points that I thought were J's putting up a thumb um he made     
1:02:49     
some points that [Music] were like also related to     
1:02:56     
uh Wolfram spoke at I mean wol Michael     
1:03:02     
Levan spoke at the wol from Institute I I I have not had coffee yet     
1:03:08     
yeah um and um one of the thing you know he was     
1:03:15     
talking about his U his ideas um you     
1:03:20     
know cognition or that that that I forget what the way     
1:03:26     
he put himself like a radical a radical gradualist I think is what he said right     
1:03:33     
that that that you know C cognition is in a lot more places     
1:03:40     
than you think and but the important thing was that if you don't if you don't     
1:03:46     
test things right um then you you just won't know right and he was making the extreme     
1:03:54     
case where he was just like he was just like well do I know you know he was     
1:04:00     
talking about Gene regulatory networks and he was just like you know you wouldn't expect that they were capable     
1:04:06     
of all these kind of learning behaviors but when when tested they     
1:04:13     
demonstrated all these you know six forms of learning something like that right and um then he made the extreme     
1:04:19     
case where it's just like you know people people then accuse me like of     
1:04:25     
saying you know does that mean that the the weather is thinking and you know and     
1:04:31     
his point is um I'm not saying that uh     
1:04:36     
what I am saying is that um you could you could test it right you know if you     
1:04:43     
had the tools on that kind of scale um you you you could test it and see right     
1:04:51     
and and this is um     
1:04:57     
leads into this this pnas paper um what was PN Nexus yeah just be     
1:05:05     
clear um uh uh but it was interesting mlen on this     
1:05:12     
paper okay you know um he's just it's not the last author     
1:05:18     
but he's he's at the back there yeah yeah and     
1:05:24     
um uh they but it's specifically covering     
1:05:30     
reasoning in all right yeah so giving     
1:05:36     
people you know like logic tasks     
1:05:45     
syllogisms and then something more complicated yeah and     
1:05:52     
and also and then another dimension of varying     
1:05:58     
um uh content the words the words you're using so so does does the content kind     
1:06:08     
of match your expectations or does it contradict     
1:06:16     
them and then he had a third condition which I didn't get to ask him about which was kind of nonsense right um and     
1:06:24     
I I was wondering if the so so part of it was like you know will     
1:06:29     
you see something as true when it it's like you know     
1:06:37     
um dolphins or doctors or something like that you know like like I'm not doing     
1:06:43     
this well on the fly but um but I was wondering if they added the     
1:06:51     
nonsense condition um for to to match something     
1:06:56     
you know you see this in child development or cogntive development right that if you use nonsense     
1:07:04     
words um kids will use will add will use     
1:07:12     
them grammatically correct okay right like like if you're obviously using this thing as a noun     
1:07:19     
then you will do noun things to it and if you're using it as a verb then you'll do verb things to it     
1:07:26     
right right um and I I didn't I didn't get to ask um I was gonna maybe try and     
1:07:34     
follow up with him on that um but     
1:07:40     
so they're testing humans and they're testing like four or five different     
1:07:47     
reasoning lln models right and um     
1:07:57     
one of and certainly again like to to loop back to Levan's point one of his     
1:08:02     
one of his things was that you know if if you're not careful about your you     
1:08:09     
know testing if a model does something right you you won't you know you you     
1:08:16     
shouldn't be dismissive of of its reasoning abilities um uh too too quickly and and     
1:08:25     
and the the humans are there because the     
1:08:30     
reasoning you know like even humans fall into these traps if you     
1:08:38     
will so um yeah so it was it was interesting to cover it uh the this work     
1:08:46     
had been done to you know it had just it got published like before the holidays     
1:08:52     
but um uh you know it was done probably like a     
1:08:58     
year plus ago right and so there was no deep seek yeah well uh but but it was     
1:09:06     
you know then I thought what was interesting was to then look at yeah how     
1:09:14     
llms are starting to be constructed for this particular kind of reasoning     
1:09:20     
purpose right yeah and um as well as like how that     
1:09:28     
matches uh um yeah like like cognitive architecture     
1:09:33     
Theory as as well as like cognitive Sciences ideas about how we break     
1:09:41     
problems down you know in into smaller parts right which is which is again one     
1:09:47     
of the one of the techniques that um uh that that that some of these     
1:09:54     
language models are are um at least some of the designers are using as as kind of     
1:10:02     
goals right yeah uh uh I mean goals for     
1:10:07     
their training and um and of course this     
1:10:14     
this all sort of comes back to something I don't know if you remember me talking about deep     
1:10:20     
algebra yeah yeah I think I remember right right so you know and and again to     
1:10:26     
um I forget the P data Warsaw guy who coined this thing but you know he he was     
1:10:33     
very much saying well like this was it was an extension of karthi's     
1:10:41     
2015 like kind of cursory work but but it was kar's work where he was training     
1:10:48     
on um open math textbooks I think okay yeah yeah something like that right     
1:10:57     
and and I think this came out in some of this llm train or some of the     
1:11:05     
reasoning model training has focused on math BEC because it it's this body of     
1:11:14     
logic work and and where you've     
1:11:20     
got um structures built on structures     
1:11:25     
know and yeah so I've you know there's there's some     
1:11:33     
like I don't know if you call it like there's some computer engineering to how     
1:11:40     
they've made this more efficient model and then there's     
1:11:48     
some you know then there's some kind of training choices yeah that that they've     
1:11:54     
made that that that I thought would be would be interesting to to look at um uh     
1:12:02     
but certainly you know the the the I think the big take-home is     
1:12:08     
the um the efficient use or and know again     
1:12:14     
like the efficiency of of adding some reinforcement learning some real     
1:12:20     
directed reinforcement one into into the training yeah     
1:12:28     
um uh yeah and then so so um buzzer     
1:12:35     
about that was th that was Thursday Friday was University of San Francisco and um University of San     
1:12:43     
Francisco's data Science Institute um is is an     
1:12:50     
interesting uh group you know the the fast AI     
1:12:55     
developers used to be professors there okay and     
1:13:03     
um the the data they were really leveraging you know the fact that they     
1:13:11     
were here in San Francisco right right and you know where to some degree you     
1:13:17     
could say kind of data science was created by the tech industry and um uh so they had um a guy     
1:13:29     
from modal which is just a you know it's a tech     
1:13:35     
company but it was very much you know it was a great example of you know a     
1:13:41     
Berkeley CS you know PhD who's who's     
1:13:46     
grown up in this era where neural network optimization is is     
1:13:54     
a a career yeah right you know it was a very young guy     
1:14:01     
very young guy but but absolutely speaking as like a tech industry leader     
1:14:09     
right you know right um and like like     
1:14:14     
talking giving us a lot of U really interesting insights in terms     
1:14:21     
of um I guess what you all like ml Ops of     
1:14:28     
of llms yeah and um yeah so interesting     
1:14:35     
interesting of course you know where     
1:14:41     
um this has become you know they're doing things that we would have built     
1:14:48     
DC's to do right I mean you know I I mean I like totally built a for     
1:14:55     
GPU workstation back at UCSF like you know what would that be like 10 10 years     
1:15:05     
ago or so now yeah um to to run of course     
1:15:12     
computational physics models right uh and his company is showing you     
1:15:19     
how to spin up and he was saying well like you don't you can't game on these     
1:15:25     
gpus you couldn't game on our gpus either right these were these are conversation only right yeah uh but you     
1:15:35     
know this this emphasis these days that everybody's just running llms right and and     
1:15:43     
um uh uh anyway I I I'm glad I went     
1:15:49     
because you know again like I I I feel a slightly I I feel     
1:15:58     
um you know I I don't use them right I don't     
1:16:03     
use them at all right yeah and and uh I mean I I I I still feel somewhat     
1:16:13     
good about that in terms of like I don't think that really needs to be your direction for artificial intelligence     
1:16:19     
but at the same time they are you know like like they     
1:16:25     
are the the the area um certainly younger me would have definitely     
1:16:31     
followed them because of the the the people and and you know um     
1:16:39     
research focus and money that's G gone into their development right     
1:16:47     
right so um so that's that that was that was definitely interesting and and again     
1:16:53     
he he had some things to to say about um some some practical things to     
1:16:59     
say about working with these especially on reasoning problems right so he was     
1:17:07     
you know he wanted to separate out just as the the PNA Nexus like     
1:17:13     
Stanford group um the the models that were focused on reasoning yeah you know     
1:17:20     
and and that if you're developing a chatbot for um to basically deal with you know     
1:17:31     
support stratification or you know um a     
1:17:36     
bot to do email labeling or you know these kind of things is like these these     
1:17:42     
these reasoning models total Overkill you know you don't don't need to     
1:17:47     
be and um yeah so I I I want     
1:17:56     
um so it's just sort of follow up from last week um in terms of the active     
1:18:01     
inference uh textbook oh yeah and you know the um I I really want to have     
1:18:12     
um uh you know so so I'm following Josh     
1:18:18     
bongards course which is nice just in relation to the last paper you covered     
1:18:23     
yeah um and um so two two more lectures     
1:18:28     
this week that were focused on basic neural network I mean I don't     
1:18:35     
even to call Basic neural like almost like basic logic truth table kind of stuff right and um and what was     
1:18:44     
the U but but again you know someone who's who tells you that     
1:18:50     
his course is going to be coding like you're gonna write more codes for     
1:18:57     
my course than anything that you've ever done yeah is is is like Josh bonard     
1:19:02     
talking about you know just I I WR of     
1:19:08     
um uh he's got these great he's got these you know pie bullet examples and     
1:19:15     
you know again like he's definitely trying to give you an experience of     
1:19:21     
building everything from the ground up so very simple robot like you wouldn't     
1:19:26     
even call these robots like they're they're um very simple     
1:19:34     
structures that that he's gonna apply kind of robot rules to which which is     
1:19:39     
actually kind of nice if if your end goal is biobots or something like     
1:19:45     
that um following up in the active you know so so again not a lot of people     
1:19:53     
came to that uh that particular reading group um and the psychiatrist who there     
1:19:59     
is like not quite sure he's ready to code but but I I'm gonna I'm following     
1:20:06     
up with the active inference Institute want more you know it's like even Ryan     
1:20:12     
Smith's stepbystep tutorial like you know you end up installing and using SPF     
1:20:20     
right is not not exactly what I would call like a     
1:20:27     
beginner you know this this is a far cry from karthi's uh LM from scratch right     
1:20:35     
yeah you know and     
1:20:41     
so yeah and and it would be nice um to     
1:20:47     
have you know like because pie bullet is a part of this you know thinking about     
1:20:54     
yeah some some basic agent um development     
1:21:01     
in kind of following um uh the the the world model papers     
1:21:09     
that um saffron recommended for the RFP yeah     
1:21:15     
there was um there was two or three papers from a particular     
1:21:21     
group uh and and I'm blanking on them right now I I'll I'll find them in a     
1:21:29     
minute but just thinking about um how     
1:21:35     
to yeah how to how to get something that is     
1:21:40     
um uh a kind of easier code     
1:21:46     
introduction um and     
1:21:52     
um you yeah it it's not so one again like I said this     
1:21:59     
last week but you know it's just awful to ask people to use matlb when it's it costs money oh yeah yeah you know and     
1:22:08     
you know they give you ways to run there's there's some way that you can run a compiled version of SPM but then     
1:22:16     
you don't get to really interact with the code in the same way yeah yeah it's     
1:22:22     
it's they just shouldn't or or they should test you know they     
1:22:27     
should test what they have with octave so that people can run OCT um but uh     
1:22:38     
uh yeah the the just thinking about the world models and and     
1:22:44     
um um inferences     
1:22:49     
planning is the um is kind of the connection     
1:22:56     
between um the the kind of active inference work and     
1:23:02     
um and the you know re reasoning Behavior or     
1:23:11     
you know certainly breaking breaking something down into kind of     
1:23:16     
sequential uh uh uh sequence of operations right and and that     
1:23:26     
that certainly in the the particular papers which I've got to find now so I     
1:23:32     
can really we weave them in properly here but um you know again so much of that the     
1:23:40     
world models papers was really just about how far ahead can can the model     
1:23:46     
think or plan right um and um it's     
1:23:52     
interesting the the reference in the in the textbook     
1:23:57     
um the um inferences     
1:24:02     
planning goes back to this guy um adius     
1:24:08     
um in like 2002 and um I'm super curious because     
1:24:13     
the the that particular that particular you know ml researcher I don't know what     
1:24:20     
you want to call them um actually worked with um Shri     
1:24:26     
nagarajan here at the Meg Center oh really like like they they had a     
1:24:31     
paper I don't know how sh met him um but well I think he was I think he was     
1:24:38     
basically brought into San Francisco to be a data     
1:24:44     
scientist anyway I I I I noticed that that that he has kind of like the     
1:24:49     
foundational paper you know and it's it's probably not even paper it's like it's like an abstract in a in a like     
1:24:57     
2002 probabilistic inference conference oh yeah you     
1:25:03     
know anyway sorry just again linking     
1:25:09     
linking together these things together with the active inference text and and     
1:25:15     
you know hopefully some actual practical practical     
1:25:21     
demos um yeah yeah oh that's great stuff thank     
1:25:28     
you uh so yeah you know as you're talking about live coding and how that's     
1:25:34     
like there's like a standard of karthy work and then like that is a skill I've     
1:25:40     
tried doing that and teaching and you know you have to kind of build that skill of live coding I've done that in     
1:25:45     
the group U years ago I used to do that more in the group meetings but I don't     
1:25:51     
as much anymore because it's very hard to do you know I mean I think karthy plans it     
1:25:59     
out oh yeah yeah you have to plan it out but I mean just getting it to be like effective like you know what do I want     
1:26:05     
to show people I want to show people like me hitting buttons on the yeah making mistakes or am I demonstrating     
1:26:12     
some thing that gives you a good visualization at the end um yeah or something you you know     
1:26:21     
works yeah yeah yeah yeah the uh     
1:26:26     
uh you know I've still I've thought well again you know I I haven't     
1:26:33     
um I don't use llms um you know I I I've seen the kind     
1:26:40     
of um what is it three blue one brown um is it three brown one blue um     
1:26:47     
videos on Transformers but you know doing something like Kar karthi's um L     
1:26:53     
from scratch would actually be a great way to um to solidify some of these things I I     
1:27:02     
just you know it's um I don't     
1:27:07     
know yeah you know I I I just don't know if I can do active inference without     
1:27:13     
doing coding you know if I'm gonna get if I'm gonna be able to     
1:27:20     
um yeah understand it the way that um I see you know par and Brian Smith and and     
1:27:28     
others talking about it right you know like it it's yeah super important so     
1:27:35     
yeah um yeah try trying to see whether it can use RX in for as as a a     
1:27:43     
replacement for kind of like the SPM stuff you know     
1:27:52     
yeah yeah that's great uh yeah and then you know World models you mentioned that     
1:27:59     
and it's just kind of interesting how I think we talked about world models last week in terms of how people have     
1:28:07     
different kind of perspectives on it I think we're getting fall maybe falling into the same trap we're with Foundation     
1:28:13     
models in some ways because that's like World models what does that mean well it's a representation of the world okay     
1:28:19     
what does that look like uh you know it's like okay it's just anything that isn't like the     
1:28:24     
trained you know uh whatever is the model is trained on so I don't know that     
1:28:30     
there might be something too I kind of thinking about world models as like you know what is the sort of what are the     
1:28:37     
cognitive science underpinnings of them yeah or what what do you mean when you mean world model is it     
1:28:44     
like well we talked about it a little bit in terms of ever good regulator theorem but like what does it mean in     
1:28:50     
terms of what what are the properties of a world model what would make it affect World model is it just a mapping from     
1:28:57     
the world to like a mental representation and I don't want to say     
1:29:02     
mental in a machine but like being able to recall something like a scene or     
1:29:10     
recall the basic structure of something or maybe encoding it as a graph and you know how much of that can you     
1:29:17     
recover different different things like that I mean really getting at like what     
1:29:22     
it what it is and you know yeah yeah I thought I thought it was it was a good     
1:29:31     
example this um sorry and I'll I'll post this um no I I posted the Nexus paper in     
1:29:38     
the slack um I just forget now what Underwood     
1:29:45     
uh what channel and and yeah so that second one     
1:29:52     
down no no no down down down yeah yeah so the second to last yeah yeah there     
1:29:57     
yeah yeah that that's that's the link to the paper and to to to your to your     
1:30:03     
point um both both of them made this this you     
1:30:10     
know so so you got this kind of Deep Mind researchers is thinking about the kind of theory and then you've got this     
1:30:18     
this you know San Francisco Tech guy who's thinking about how you use these     
1:30:23     
reasoning models and both are are really emphasizing that     
1:30:30     
you're um your eval your your evaluation is everything yeah like how how you're     
1:30:36     
evaluating output from these models is is really important and um and like you     
1:30:43     
said like if you're not asking the right question um you're not going to     
1:30:50     
necessarily understand the the model's kind of depth if you will yeah or you     
1:30:56     
know the the models abilities yeah and and I liked I liked     
1:31:03     
this particular paper just in terms of     
1:31:08     
um well you know you you you needed to be working with humans you still needed     
1:31:15     
to be doing cognitive science with humans yeah I liked that um and     
1:31:24     
uh yeah and you know this wasn't one of these it didn't have that feeling     
1:31:32     
like it was psychologists um um being lazy about     
1:31:40     
recruiting subjects and just testing an llm with like hey we give these tests to     
1:31:46     
humans let's just do to an L or you know like hey an llm you know     
1:31:53     
has decent results on a theory of Mind test it must be conscious or something     
1:31:59     
like that um so I I yeah I would love to see more     
1:32:08     
of these kinds of things as well as you know how to     
1:32:16     
um you know like like deep algebra was a focus because because math is so     
1:32:24     
important right but I think so many of these these     
1:32:29     
yeah one of um Chris oh I'm blanking on his name now     
1:32:35     
um one of the modal guys that that that talked at um the data Science Institute     
1:32:42     
you know he was saying that like designing your evaluation no like like no don't just use an llm to do your     
1:32:52     
evaluation and and and     
1:32:57     
um that you know that that I think his point was that like a lot of people are     
1:33:02     
using math because because they know what the answers are right and and that's I mean it is right     
1:33:13     
um but it's these aren't people who care about man right so it it gets to the point     
1:33:22     
that they don't have a whole bunch of pre you know te pre-tested um logic     
1:33:29     
problems or things like that for you know like how how do you check yeah that     
1:33:36     
your your system is is doing all these things right and um so anyway I I felt like     
1:33:47     
there was there was still a lot of Hope in this era where you know again this is     
1:33:53     
data science Institute at at University San Francisco so in San Francisco right     
1:33:58     
so You' got this this room of hundreds plus students you know     
1:34:05     
who when they got around to Q&A a lot of them were asking like am I still gonna     
1:34:11     
have a job yeah um and I I kind of wanted to say hey     
1:34:19     
look at this paper you know you should all maybe maybe being cognitive science just be a good     
1:34:26     
idea you know and yeah yeah it's it's um     
1:34:33     
it's funny how this is H yeah it requires it requires the skills I I     
1:34:39     
don't know if you saw this but on on YouTube there's this famous science     
1:34:46     
communicator but he got famous because he he went on Joe Rogan to argue with the Ancient Aliens guy so he's an     
1:34:52     
archaeologist but he's talking he's talking this week because Cardiff is is letting go half of     
1:35:01     
its Humanities oh my God staff yeah yeah and closing closing several schools and     
1:35:09     
um um you know they they they you know I I     
1:35:15     
bet I mean you can also almost imagine that that discussion of like what are     
1:35:20     
what are the degrees that are worth keeping right and and you yeah if if llms     
1:35:30     
continue to be the the dominant technology then maybe they're gonna need more humanties     
1:35:36     
people make sure that they're actually working yeah why don't we go back to the paper     
1:35:43     
uh we have the yeah so language models like humans show con 10 effects on     
1:35:48     
reasoning tasks uh James Mand is in the author list     
1:35:54     
um and you know we had all right so the abstract uh abstract reasoning is the     
1:36:00     
key ability for an intelligent system large language models achieve above     
1:36:05     
chance performance and abstract reasoning tasks but exhibit many     
1:36:10     
imperfections however human abstract reasoning is also imperfect human reasoning is affected by Real World     
1:36:17     
Knowledge and beliefs and show notable content effects humans reason more reliably when the semantic content of a     
1:36:23     
problem supports the correct logical inferences these content entangled reasoning patterns are Central to     
1:36:30     
debates about the fundamental nature of human intelligence so here we investigate whether language models     
1:36:37     
whose prior expectations capture some aspect of human knowledge similarly mix     
1:36:42     
content into their answers and logic problems we explore this question across three logical reasoning tasks so you     
1:36:49     
have natural language inference uh logical validity of syllogisms and the wayon selection task     
1:36:57     
uh which is psychological test um we evaluate the State ofth art language     
1:37:03     
models as well as humans to find that language models reflect many of the same qualitative human patterns on these     
1:37:09     
tasks like humans models answer more accurately when the semantic content of     
1:37:15     
a task supports the logic one influences these parallels are reflected     
1:37:20     
in accuracy patterns and in some lower lower level features like the relationship between language model     
1:37:27     
confidence or possible answers and human response times however in some cases the     
1:37:34     
humans and models behave differently particularly on the Wason task where     
1:37:39     
humans perform much worse than large models and exhibit a distinct error     
1:37:45     
pattern our findings have implications for understanding possible cont contributors these human cognitive     
1:37:52     
effects as well as the factors that influence language model performance so this is where they kind of talk about a     
1:37:59     
lot of the different tests that they're doing working from abstract reasoning     
1:38:04     
tests um and see this is what you were talking about figure one where you have     
1:38:12     
the sort of consistency violations of consistency and nonsense kind of going through that     
1:38:19     
they don't do any developmental uh eval valuations but that might be interesting given what you     
1:38:26     
were saying about you know syllogisms and nonsense and development um and then     
1:38:33     
this is the wayon selection task which is where participants are shown four     
1:38:38     
cards they told that each card is a letter on one side and a number on the other the participants are then told a     
1:38:45     
rules such as if a card is a d on one side then it has a three on the other     
1:38:50     
side so associating letters with numbers the four cards respectively show d f 3     
1:38:57     
and 7 the participants are then asked which cards they need to flip over to check if the rule is true or false so     
1:39:03     
you're evaluating the rule um as much as predicting the state of the flipped Cur     
1:39:11     
the correct answer is to flip over the curs showing D and seven however wayson showed that while     
1:39:17     
most participants Lon showed that while most     
1:39:22     
participants correct ly chose D they were much more likely to choose three than     
1:39:28     
seven that is the participant should check the Contra uh contrapositive of     
1:39:34     
the rule not three implies not D which is logically implied but instead they     
1:39:41     
confuse it with the converse three implies D which is not logically implied     
1:39:46     
so this is where you're looking at how you know the intelligence like gu     
1:39:53     
uses logical compositional rules to solve these problems and kind to come up     
1:39:58     
with the best solution so that's they're talking about     
1:40:03     
here uh yeah they they kind of evaluate language models and showing the     
1:40:10     
similarity across language models the sort of performance profile and then you know looking at     
1:40:18     
humans as well um yeah so that's the article in p     
1:40:24     
Nexus this is language models like humans show content effects on reasoning     
1:40:30     
tests if we go to the data science ml Channel then I think um Morgan has     
1:40:35     
posted a number of things here that are you know so we have some deep seek stuff     
1:40:41     
we have that paper so why don't we go over kind of where we start with deep     
1:40:47     
seek so there's a lot of deep seek stuff this week actually we start we can start     
1:40:52     
up here with this yeah go ahead yeah I was just gonna     
1:40:57     
say so Charles Martin just for and my apologies for the LinkedIn links but um     
1:41:04     
uh again these are these are original posts by these     
1:41:09     
people so I I have to link to something that's fine yeah and it's such a mind     
1:41:15     
field these days what to what to link too I'll find if they've got threads or     
1:41:22     
blue sky or something um uh but Charles Martin is the     
1:41:29     
physicist or he's coming from a theoretical physics background um doing     
1:41:35     
field Theory at University of Chicago he's used that kind of     
1:41:42     
background especially in like renormalization group Theory um     
1:41:48     
to design Weight Watchers and you find it weight     
1:41:54     
watchers. which is a um you know     
1:42:00     
using condensed matter physics theory to look at your training weights to analyze     
1:42:09     
your training weights um absent of data     
1:42:16     
right and um uh these are his breakdowns or you know     
1:42:24     
things that he's he's brought in that I think would be particularly interested     
1:42:29     
given his particular Focus so he he's very much the person who works in kind of um advising corporations that want to     
1:42:39     
apply this right want to apply these Technologies however he's coming from a     
1:42:44     
very good theoretical background in terms of how how he's especially looking     
1:42:51     
at um evaluating your kind of your training     
1:42:56     
efficacy and or um what's the right word     
1:43:04     
um whether you need to train more or like in he can find instabilities in     
1:43:11     
your training weights that would suggest you know that that can tell you     
1:43:18     
something about probable performance issues that you will have     
1:43:24     
just to just to give you a little background on that particular     
1:43:29     
um yeah yeah I'm looking at this looks interesting um that's this this article     
1:43:37     
here Charles Martin talking about evaluating I I'll put this in a     
1:43:43     
thread you know again I I I I do really love his posts in terms of     
1:43:51     
um um how he brings in good stuff to the discussion of of     
1:44:00     
training and weights yeah     
1:44:08     
that it is so hard to extract real links from these yeah     
1:44:15     
yeah and then he's he's got some examples of these but I I think that's     
1:44:21     
the that's the main um yeah I think we can get it through     
1:44:27     
we've talked about Weight Watcher before with the open source games this is the just yeah kind of understanding your     
1:44:34     
weight structure then this other paper implicit self-regularization in De networks this     
1:44:40     
is using um renormalization I guess techniques to look at this yeah and yeah     
1:44:48     
this is good stuff um it's it's it's really good stuff and and you know     
1:44:54     
it's um uh I I don't know if we've got you know it would be     
1:45:02     
interesting he's got previous posts on things like you know looking across say     
1:45:07     
all the same deep learning models I mean all the same llms that that say the Nexxus papers     
1:45:14     
looking at yeah right and and saying saying something about their weight structure and you know making     
1:45:22     
predictions on issues that the various models might have on the basis of     
1:45:29     
that that that's that's pretty interesting um     
1:45:34     
uh and sorry and then I I I dropped in a link to the     
1:45:40     
um just the um one of the world models     
1:45:47     
authors which one is that the last one yeah so that it's talked about in the     
1:45:55     
yeah so that that's his paper you know and then if you go to papers you can see that but you you can also see just like     
1:46:02     
the kind of world models um and and you know the kind of videos is that is he     
1:46:10     
doing with language well learning to model the world with language mastering diverse domains to World models so he's     
1:46:17     
actually doing like stuff with World models but kind of thinking about the achieving     
1:46:24     
he's he's he's referenced in the um he's referenced in ad the Adam afron     
1:46:31     
um RFP yeah yeah yeah and but that is interesting that like his     
1:46:38     
2024 icml I I assume what he means by this is     
1:46:44     
he's using llms     
1:46:51     
um maybe uh but but but again the main thing I     
1:46:57     
wanted to put him back in there for was was just um like you said like like     
1:47:06     
what operationally what does a world model really mean     
1:47:12     
right and and     
1:47:18     
um yeah yeah you know and I I I I want     
1:47:23     
to I want to try and Link it to this um inferences planning yeah yeah that would     
1:47:31     
be good yeah and kind of ab and kind of you know     
1:47:36     
not like like we see it in all of these kind of game     
1:47:43     
examples um     
1:47:49     
which which I think leads us in the wrong direction in terms     
1:47:56     
of what the world model means yeah so the game examples are are     
1:48:02     
kind of leading in the wrong direction that that that it's it's not     
1:48:07     
yeah that that we see we see this 3D world that the agent's operating in yeah     
1:48:12     
and we think that that's the world um whereas I think it's actually a     
1:48:18     
more abstract you know sequential learning or sequential     
1:48:25     
planning um yeah it's it's like it's not the actual kind of like one toone     
1:48:32     
correspondence it's actually this abstract yeah tree or yeah yeah but but     
1:48:39     
is interesting though right in that if agents aren't put into this kind     
1:48:46     
of world yeah right that the the sequential planning     
1:48:53     
isn't doesn't become a um like     
1:48:59     
like sort of doesn't have any evolutionary value right um you know again like I you     
1:49:08     
know the Bongo of course is taking over my my my brain space     
1:49:15     
um but but that's you know that that is     
1:49:21     
kind of that that kind of of Ryan Smith's Point too in the step-by-step tutorial of active inference is you     
1:49:28     
can't just you can't just you know act active inference doesn't become active     
1:49:35     
inference until you put an agent into um a kind of Rich environment     
1:49:41     
yeah I mean a comp a complex environment and     
1:49:46     
and yeah so they need to start they need to start think you know it like to come     
1:49:53     
back to the the the Rosen stuff you know it's it's um if there's nothing to     
1:50:02     
anticipate yeah then then you know you're not going to develop any of these     
1:50:08     
things um but uh     
1:50:14     
um yeah building building up this kind of these kind of inference tables of hey     
1:50:21     
if I see this then this or you know these other kinds of these other kinds     
1:50:27     
of things that you know funger talks about early models being kind of tree     
1:50:33     
tables yeah and then there's also the open-ended aspect so having like the     
1:50:39     
ability to kind of build new relations and things like that yeah yeah yeah and     
1:50:46     
certainly this is the the other part that     
1:50:51     
um uh uh that that all the kind of all the cool companies all the cool ml companies     
1:50:58     
now we're talking about is is continual learning and things like that right yeah um I I just you know I I I've     
1:51:08     
been looking around in terms of other you know who who's who's     
1:51:15     
doing um you know you you you check out open     
1:51:20     
ai's old um spinning up in RL right like like they haven't updated their     
1:51:26     
materials since 2017 or something right um you know went went to Rich Sutton's     
1:51:34     
you know Amy group there's there's no you know     
1:51:39     
there's coar um they they talk about like course     
1:51:45     
material and they are basically pointing you to um you can do their     
1:51:53     
corsera right you know which is cool um and maybe that's where they talk about     
1:52:00     
something that's you know akin to or like that would be on par with bongards     
1:52:08     
evolutionary robotics um in terms of leading you and building     
1:52:14     
something but I I haven't seen it anyway I'm looking for I'm looking for     
1:52:20     
that right like you know it it so many of the I mean models that     
1:52:27     
I used to play with um from Deep Mind you know like     
1:52:32     
again back when these companies were were big on sharing yeah um uh I think the the     
1:52:43     
they had this Quake three model that they used that I that I really liked because of course I could remember     
1:52:49     
playing quick three yeah and um I I can't even get it to run because     
1:52:55     
it's got like python 2 dependencies oh yeah it's I can I can install python 2     
1:53:02     
on Fedora um but like they've got this weird Google dependency on     
1:53:10     
basil and so you're kind of running it in a Java sandbox and like like basil 8     
1:53:18     
is like no I don't I don't I don't python 2 sorry     
1:53:26     
yeah yeah it's uh definitely so if we go back to the data science andl channel we     
1:53:33     
do have uh we go back up to let's see where be to start I wanted to start here     
1:53:39     
with this article from January 15th at Le Morgan posted it there this is     
1:53:46     
talking about the top out large language models are saturating many common evaluations so this is related to the     
1:53:53     
thing that we were talking about earlier where you have um this problem yeah let     
1:54:01     
me let me see if I can um extract out so this is Ben blazic at um at argon yeah     
1:54:10     
uh who is doing some really cool stuff     
1:54:17     
um again because he has real world applications and and you know if you     
1:54:24     
will they care um     
1:54:29     
about you know actionable results right right so let me I'll drop this     
1:54:37     
in the um channel the the the I'll drop it in a     
1:54:43     
thread on that on the um yeah so he's got     
1:54:49     
that so that's the paper SC code okay py code     
1:54:55     
yeah um which is     
1:55:00     
cool and     
1:55:08     
um     
1:55:14     
uh oh what oh shoot no sorry I think I put     
1:55:20     
this in the wrong thread oh now let     
1:55:26     
me sorry oh here we go sorry I just added     
1:55:33     
it to the there you go     
1:55:39     
okay this is the archive paper scod a research coding Benchmark curated by     
1:55:46     
scientists uh since language models now perform outperform average humans and     
1:55:52     
many challenging tasks it's become increasingly difficult to develop challenging high quality and realistic     
1:55:59     
evaluations and so this is where they're creating the scientist curated coding Benchmark     
1:56:04     
scode uh the problems in scode naturally factorize into multiple sub problems     
1:56:11     
each involving knowledge recall reasoning and code synthesis so this is basically like a benchmark for comparing     
1:56:19     
humans and language models and yeah so this is this is     
1:56:25     
good yeah I just wanted to add that um this seems to sorry go ahead no no go     
1:56:36     
ahead that I'm just done so I I also dropped the GitHub     
1:56:42     
link and um and just interesting off of that GitHub     
1:56:50     
link if you see um the news there so scode has been     
1:56:57     
integrated with inspect Ai and that's that's that next link all     
1:57:03     
right um and so this does seem to be an AI safety     
1:57:12     
Institute um I don't um you know it's one of those things     
1:57:19     
[Music] where um     
1:57:27     
again too many of the AI safety people that I'm introduced to um     
1:57:34     
are you know like their doomers and their     
1:57:39     
um whole brain emulation will save us yeah you know and I     
1:57:45     
I I I just have a problem with that um but uh     
1:57:52     
if this is at least a good framework for     
1:57:57     
improving like testing multiple you know looks like some good things here in     
1:58:02     
terms of um here's how you would set up and run the eval for a different a few     
1:58:09     
different model providers and they've got open AI anthropic Google Gro mistol     
1:58:14     
hugging face yeah that's kind of cool so if if open AI I mean sorry if AI     
1:58:23     
safety is going to do something for us hopefully it will be doing things like that g giving his code infrastructure     
1:58:30     
they they improving model evaluation     
1:58:36     
yeah so then we have the the highlight of Sakana AI which is this right model     
1:58:43     
this is David ha who runs Who's involved in this and this is just kind of a a     
1:58:48     
model like where they these self- adaptive models that modify their weights during     
1:58:54     
inference this is yeah kind of world model stuff kind of from the uh you know     
1:59:00     
well ha and Schmid Huber wrote the 2018 paper of world models so yeah they're     
1:59:06     
involved in that but also David H's also involved in artificial life approaches so interesting stuff there it it's     
1:59:15     
definitely um yeah like like um let me also just     
1:59:21     
put um uh an added     
1:59:28     
um you know here's here's their actual blog post on on this     
1:59:38     
okay kind Transformer squared okay self adapted larg language models yeah and     
1:59:47     
and you know apparently     
1:59:54     
um well again it's this is interesting in that it brings up and     
2:00:01     
contrasts itself with a number of other techniques like Laura um that are being     
2:00:08     
widely used because everybody's dropped everything that they're doing and and they're working on large language models     
2:00:14     
right right um so so that's kind of cool I I     
2:00:21     
you you know I always like something that starts with like the core you know the core ability of this thing is     
2:00:29     
achieved through the singular value decomposition and it's just like well if     
2:00:37     
it is yeah yeah then then you know     
2:00:42     
anyway I mean you know again this is why I love um the you know Gil Gillard     
2:00:49     
string and you know SVD is the root of of everything right     
2:00:55     
the root of everything so it it shouldn't shouldn't     
2:01:01     
surprise us yeah um but it does make it sound like you're just doing PCA on     
2:01:07     
something right yeah some internal variables I mean this blog post it reads     
2:01:13     
kind of like it's biologically inspired but it's really just kind of like you know it's not VI yeah yeah what what's     
2:01:22     
wrong with just saying it's algebraically inspired well that's not cool I mean not     
2:01:28     
cool well I mean I think it's cool I don't know but yeah it's so yeah I don't     
2:01:35     
know uh but I you know I I'm like like     
2:01:41     
they're they're great they still they still um you know they still uh submit papers     
2:01:49     
to aife and things like that so yeah aif isn't all biologically     
2:01:55     
inspired it's got true true and like like if I learned anything from from     
2:02:03     
gecko um it's it's how little evolutionary algorithms and modeling um     
2:02:12     
has to have any connection to biology well yeah lot of its optimization and     
2:02:19     
yeah yeah yeah yeah so me back to the channel I just want to go over really     
2:02:26     
quickly this stuff on um uh deep seek because I think that's really kind of     
2:02:32     
the timely stuff here so the Charles AG Martin uh post start to deep seek was     
2:02:38     
made by quats and so and then there's this deep seek r1's recipe to replicate uh 01 and     
2:02:46     
the future of reasoning LMS this is where you know they kind of     
2:02:52     
they have this uh performance chart deep seek R1 you know they've been releasing     
2:02:58     
models this week deep seek and kind of uh being compared with the stuff that     
2:03:05     
open AI is putting out um and so 01 being an open AI model so they're you     
2:03:11     
know kind of comparing deep seek model performance here and showing what it can do this is Charles H Martin again on     
2:03:19     
LinkedIn for those longing for a deep SE deep dive here is a very dense review     
2:03:25     
where it kind of goes into some of the this is distilled AI um this is just kind of an outline of     
2:03:32     
this deep dive the primer on deep sear one the architectural foundations     
2:03:39     
mixture of experts model multihead lat and attention fp8 Quant quantization     
2:03:46     
multi-token prediction then the training pipeline uh where you have supervis     
2:03:52     
fine-tuning and then reinforcement learning group relative policy optimization or     
2:03:58     
grpo and kind of going through that plus uh comparison to other types of policy     
2:04:05     
optimization models which is something I'm I'm not familiar with at all but um     
2:04:10     
you know that might be an interesting thing to look into um emergent reasoning     
2:04:18     
behaviors distillation reasoning and compact models uh open R1 with objectives of open R1     
2:04:25     
and impact on the community so there's a lot of very heavy emphasis on     
2:04:30     
reinforcement learning here absolutely you say absolutely right yeah and and um     
2:04:39     
yeah and I I added a link to the um to the to to the the article itself oh this     
2:04:46     
is the actual okay yeah yeah just just so you can you can drill down and and um     
2:04:53     
and uh wanted to just add     
2:04:59     
um that um I think it's in call for involvement     
2:05:05     
events um yeah SEC second to last there     
2:05:12     
um is the Deep multitask and metal learning course from Stanford okay um     
2:05:19     
and um yeah you know like like you said like     
2:05:27     
these this this kind of interest that everybody has in deep SE yeah it is just     
2:05:35     
a it's a it's a reminder that there has been     
2:05:41     
um a lot of work that that is useful to cover uh I I think you can relate it to     
2:05:52     
the active inference and you know like like I like the fact that it     
2:05:59     
it comes back to a lot of the     
2:06:04     
um discussions that you will have in an active inference     
2:06:09     
training agent kind of context yeah and um and again like I'm both looking     
2:06:19     
for easy way you know these are things that Josh bongard is going to talk about at some point     
2:06:26     
right because you know certainly when you look at how people     
2:06:32     
train robots yeah um that these are the the     
2:06:39     
these all all of those things that you saw in that distill um table are are you know things     
2:06:48     
that you will need to know right um especially and I dropped this um     
2:06:57     
into bronberg vehicles I think     
2:07:02     
um um the um I mean so one is is the the     
2:07:09     
the third thing back is Mech lab which is which is bongards lab um but um for     
2:07:16     
history on on Ross and kind of just you know training like like there's they     
2:07:23     
they had a talk from a willow Labs guy okay     
2:07:28     
yeah and and you know this is um um Yan     
2:07:35     
laon's talking about you know I I mean I I think it's interesting I had um Jeff     
2:07:44     
Hinton and Yan laon saying stuff on in my feed this week     
2:07:52     
um Jeff Hinton saying that um uh a AI is already conscious and it's going to kill     
2:07:59     
us um and Yan Lon is saying that this is the decade of     
2:08:06     
Robotics yeah it's kind of a Divergent view there yeah yeah yeah yeah yeah yeah     
2:08:12     
and and I'm uh you know again if if I have to pick a side yeah and again my my     
2:08:22     
side would still be the uh um with kind of like the Ross open- Source robotics     
2:08:30     
Foundation right yeah yeah um you know I'll still yeah go with robotics and and     
2:08:38     
you know how much we still have to do in terms of producing a robot     
2:08:44     
that can pick up a slippery object or you know and things like that like you     
2:08:50     
know how how how difficult Sim toore transfer is     
2:08:56     
still yeah and and um and I know it's getting late but um     
2:09:05     
uh sorry on that on that particular Point     
2:09:13     
um I was saving this to um Sim real transfer     
2:09:22     
um nope sorry I forgot now okay well this this Chris Reed uh this is Chris     
2:09:29     
Reed Chris R and this is a a lab web page where     
2:09:35     
these researcher uh doing uh things with emergent Behavior     
2:09:41     
complex systems he he came up because of an active inference uh Institute talk     
2:09:49     
from Matthew Sims yeah that was covering um slime molds and     
2:09:54     
philosophy oh okay that I saw that come up in in the feed there yeah I thought     
2:10:00     
it was interesting yeah I thought it was interesting um um I am still trying to think about     
2:10:07     
what I trying to say     
2:10:12     
before um see robotics um anyway you keep going okay     
2:10:20     
so yeah that was the Chris R readed uh website uh he's doing a lot of things     
2:10:26     
with Collective Behavior with ant learning uh ant optimization uh we talked about swarm     
2:10:33     
intelligence and ant uh swarm optimization uh slime molds of     
2:10:39     
course uh things on collective decision making etc etc so that's something to     
2:10:45     
check out um then I'm going to go back to the um where were we with the data     
2:10:54     
science ml just finishing up with uh the uh the stuff with deep seek and R1 zero     
2:11:01     
and R1 uh Morgan posted more on um the     
2:11:08     
well he posted on the language model reasoning so there more posts on that yeah that was just the the link to the     
2:11:14     
event yeah anybody wanted to join the zoom yeah know and then a link to the ark prize which is of course this uh     
2:11:22     
where we have r10 or an analysis of deep seeks r10 and R1 R1 Z is more important     
2:11:30     
than R1 and kind of getting this is where I got this diagram from that I showed to start things off and this was     
2:11:37     
uh the Deep seek R1 architecture by Sarah Chan this is kind of describing     
2:11:44     
the architecture and again like this is beyond what I you know we kind of talked a little bit more about it but this is     
2:11:50     
still kind of you know uh I guess the whole point of this architecture is to     
2:11:56     
say that it's shocked people how well it works compared to like some of the other     
2:12:01     
models and that it's open source and it doesn't take very much compute and all that so this is kind of why we're     
2:12:07     
interested in it and yeah kind of getting this figuring out the parts of this architecture it makes a tick so     
2:12:16     
this is kind of talking about some of the advantages of it and and how that     
2:12:22     
you know how kind of getting into the architecture thinking about some of the     
2:12:27     
shifts in the broader field of AI Mar language models yeah and that that that     
2:12:34     
was why it was nice to kind of cap off the week with um uh     
2:12:40     
um this this presentation from from     
2:12:46     
modal which was very much about you know kind of like the ml of of LMS yeah and     
2:12:55     
and and of course how much that has to do with money yeah right I mean in terms     
2:13:01     
of what are you spinning up and and what's what are your justifications for     
2:13:06     
doing that because again speaking to a room of of data science     
2:13:12     
students who are going to be you know not really doing this for for academic     
2:13:18     
research but but for for commercial interests right and and that's what's     
2:13:24     
these these these the the pricing and you know the the what what     
2:13:31     
they call what they're calling inference is when you're actually asking the model of question right yeah excuse me or you     
2:13:38     
know having it make a prediction about the next token and um yeah all about the     
2:13:45     
economics of it     
2:13:51     
um so you know um not not tremendously     
2:13:58     
interesting I I do you know I do think that     
2:14:04     
that there's you know I've seen some good market analysis of like what the hell's wrong with open a where they seem     
2:14:11     
to be coming out with a new model every every week before anybody's got to     
2:14:17     
understand what the the previous model that they released is is doing yeah anything like that     
2:14:24     
but but uh but I really like that distilled breakdown of kind of the the     
2:14:30     
the main um you know the the the the topics which     
2:14:37     
it would be good to be familiar in terms of understanding how they achieved um     
2:14:43     
how they achieved this um as well as like you know that that again I I feel     
2:14:50     
like um you know it's not active inference because I I don't think active inference     
2:14:56     
is is you know philosopher stone but     
2:15:03     
certainly you know so much of this stuff is about finding interesting areas in a     
2:15:10     
really super high dimensional space right yeah and and and being able to     
2:15:18     
reduce your um yeah to to ignore a bunch of     
2:15:25     
uninteresting areas in that yeah and and certainly and then     
2:15:31     
distillation which seems you know like again like I'm glad I don't have to     
2:15:37     
write business cases for these these llm companies but um just like I don't see     
2:15:45     
how you prevent a model from being distilled right like I know you can you     
2:15:50     
can say like please don't use this to distill a model that's going to be competitor right but at the same time     
2:15:57     
like how just I don't I don't see how you Watermark that you know yeah uh um     
2:16:04     
and and so anyway more importantly the the AI     
2:16:12     
you know to to come back to kind of like the AI safety um     
2:16:18     
framework obviously us researchers should be really interested in what we     
2:16:24     
can gain from looking across all of these models and and being able to use     
2:16:31     
them um um more ad depthly like that in     
2:16:37     
terms of um uh um being able to get all their     
2:16:44     
best bits yeah and but I I still you know other than like brain am I haven't     
2:16:51     
seen a good you know     
2:16:57     
um I don't know I mean other than like the kind of kogai that you saw in that     
2:17:02     
PN Nexus like I I haven't seen where an llm     
2:17:07     
is helping us as researchers yeah you know like like brain LM is a nice proposal in terms of hey     
2:17:17     
what if you had this kind of research assistant yeah that could tell you about     
2:17:23     
um the existing literature and suggest ideas right for you know like um but I     
2:17:30     
think it's something that we haven't actually thought about how would we you     
2:17:35     
know like what would be important evaluations for us right as as academic     
2:17:41     
researchers yeah all right well I think that's it for today uh thanks for uh the great     
2:17:48     
conversation about these different things and hopefully we you know we keep going I think this line of kind of     
2:17:54     
Robotics and and AI I think you're on a good uh track here so we'll see and you     
2:18:00     
know and what I want to bring in you know to it is is is basically     
2:18:07     
embryology yeah and you know and and I love the fact that     
2:18:13     
xenobots was was a manipulation of embryonic cells right and and removing     
2:18:19     
them from that context and yeah so and and as Josh bongard says     
2:18:25     
um you know the Czech the Czech um reference that gave us the word robots     
2:18:32     
was originally about biological robots yeah so so we you know the     
2:18:39     
biological roboticists are the real roboticist yeah all right take care all right take     
2:18:46     
care let see     
