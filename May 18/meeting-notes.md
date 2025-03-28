## Meeting Recording

[YouTube link](https://youtu.be/tKnRzEPl0SQ?si=V-T-HvWikXaf9P_S)

## Mastodon thread

[link](https://neuromatch.social/@OREL/112465020601051587)

## NOTES
Jes: CogFutures RG -- returns in mid-June. CybRG -- also on break.

DW -- cell-organismal modeling, different approaches.


JoPro -- reorganization, can dovetail with program, data analysis for project.

* Inclusive Gaming post -- forthcoming. Connections (WeRobot? VR people?).

* deep philosophical work. Epilepsy Fountation event.


EveOnline -- spreadsheets in space (https://www.eveonline.com/).

* lessons learned from VisiCalc. SimCity -- governments ignore good simulation work.

* winning strategies seem totalitarian.

* computational agents --> play video games. What is the superhuman strategy?


Centralized control master loop. Generate control from collective action. Allostatic discovery.

* Active Inference drone control software. Interface for agent-agent communication. 

* agent-environment interactions. "How to Grow Almost Anything" -- good gemonic manipulations (Benchling -- https://www.benchling.com/).

* basics for designing plasmids. TFAS -- transcranial-focused ultrasound.

* Chatbots and monetizing Psychiatry. Chatbots reinforce our biases, need to understand patient-therapist.

* too much anecdotal evidence -- where techniques is biased to do well. 

* Numbers, metrics. Interventions that do better than placebo, dealing with effect sizes, statistical noise.


Biobank --> see people before they are sick.

* foundation models for medicine --> Stability AI associated. Brain-inspired transformer models.

* longitudinal aspect of this --> who will develop a positive diagnosis.

* systems physiology -- is a lot more going on than we can track.


Emily Bender podcast -- automated lab platforms. 

* interpretability -- do humans need to be involved in matabolomic analysis.

* human oversight and interpretability. Database results (new tools) --> link them together.

* Neuromatch --> mentors and research collaborations. Research partnerships (neuromatch.io/partner/mentor).


Jes (OREL)
Jes (OREL) says:
I'll be in a commute to another event so I'll be a bit limited today 
9:01

Morgan Hough (he/him)
Morgan Hough (he/him) says:
I can update a bit later if thats ok 
9:10

Sarrah Bastawala
Sarrah Bastawala says:
No major updates from my side apart from the blog I had presented yesterday that can be found at 
https://sarrah-basta.github.io/blogs
, in doing some research for frameworks to use for my project I found this 
https://pettingzoo.farama.org/tutorials/langchain/langchain/
 tutorial that I found interesting as it is trying to use Pettingzoo environments via Langchain agents powered by LLMs... 
9:14

J
J says:
👍 
9:16

Sarrah Bastawala
Sarrah Bastawala says:
Welcome! Thanks a lot for presenting the blog 
9:26

Morgan Hough (he/him)
Morgan Hough (he/him) says:
I played it 😃 
9:30

Himanshu
Himanshu says:
I have played it too! 
9:30

Morgan Hough (he/him)
Morgan Hough (he/him) says:
My mum was an urban planner so I lived it 😃 
9:31

J
J says:
Also…. I found out brian eno knew cybernetics and conway game of life  . Edge article in slack 
9:34

Himanshu
Himanshu says:
A* agents are used a lot in evaluating playability in game env setting 
Himanshu says:
https://www.researchgate.net/publication/224177833_The_2009_Mario_AI_Competition
 
9:43

J
J says:
The fate of mant conpanies is still in “make a spreadsheet so we can see those numbers” smh 
J says:
Many 
J says:
SpreadsheetCity probably wasnt as fun to market 
9:53

Himanshu
Himanshu says:
Can you share link of this article? very interesting 
9:55

Sarrah Bastawala
Sarrah Bastawala says:
This article reminds me of a project I had seen in Octave from : 
https://octave.discourse.group/t/control-libreoffice-calc-from-gnu-octave/2025
. Octave, which is an ipen source equivalent of Matlab, is used heavily for mathematical and scientific computations and simulations. This project was an attempt to connect it to Libreoffice Calc (kind if the open source equivalent to Excel), and kind if bring together yhe tabular formatting of data with the visualization capabilities 
Sarrah Bastawala says:
Open source equivalent of Matlab* 
9:59

Himanshu
Himanshu says:
Robin Baumgarten's a* agent had won the mario AI compeition and is used in a lot of 2d game setting 
Himanshu says:
Sure! 
10:03

J
J says:
Curiosly it also raises questions about what the human unspoken rules are and why  . 
10:08

Sarrah Bastawala
Sarrah Bastawala says:
https://arxiv.org/abs/2306.03314
 discusses agent-agent vs agent-environment communication to quite a good degree 
10:17

Paola Di Maio
Paola Di Maio says:
hellow everyone a bit late and tired here, but I cannot find the neurotech channel on slack. am i just not seeing it? 
Paola Di Maio says:
or maybe it is the virtual-reality-neuroech channel I need to join 
10:19

Morgan Hough
Morgan Hough says:
No sorry. Its a different Slack 
Morgan Hough says:
NeuroTechX is a nonprofit I am a part of too 
10:19

Paola Di Maio
Paola Di Maio says:
ah thanks 
Paola Di Maio says:
ok, thanks 
Paola Di Maio says:
I was pointed there before but had not yet gotten to it, will do  now 
Paola Di Maio says:
Thanks @morgan I am looking at the page on neuromatch, lets see if it leads anywhere interesting 
10:47

Morgan Hough
Morgan Hough says:
https://skywritingspress.ca/2019/01/08/the-journey-begins/
 
10:50

Paola Di Maio
Paola Di Maio says:
awesome thanks 
Paola Di Maio says:
yes I sing up for that, thanks 

## TRANSCRIPT
0:01     
look like we've got usin and Morgan and Jess and     
0:07     
Sara so why don't we get started so welcome to the meeting this     
0:13     
is uh Saturday of course and this week we had uh two meetings we had the Dare     
0:21     
meeting and we had the open source meeting finally so we had our first open source meeting of the     
0:27     
year and uh so check those out on YouTube the Evo worm uh meeting is on     
0:35     
the EVO Worm YouTube and the open source meeting is on the live     
0:41     
YouTube okay and so we had a lot of good uh discussions there Sara presented on     
0:46     
her project um you know so what we're going to do in the open source meeting     
0:51     
is people will present their open source activities ideas whatever and then you     
0:59     
know we'll kind of work on debugging things keeping track of     
1:05     
progress um you know trying things out and other things like that and then we'll have features where we talk about     
1:11     
different um topical themes uh so yeah and then Hussein also     
1:18     
presented on some of the work that he's been doing so thanks to both Hussein and SAR     
1:24     
for uh you know contributing to that meeting uh and as for the dorm group uh     
1:32     
the dorm meeting I went over some information about um a workshop I     
1:38     
attended where they were building what they call the minimal cell so this is where we have uh just the components of     
1:47     
what the uh Craig Venture Institute calls the minimal bacterial cell so it's     
1:52     
like where they strip out all the genes that aren't necessary for survival and they get the uh genome down to a minimal     
2:00     
number of genes that can allow the thing to still be alive and then they model     
2:06     
all the different components so there are no organells in a bacterial cell you have DNA you have     
2:14     
uh different types of uh DNA related things like     
2:19     
proteins and ribosomes and things like that you have water and you have the     
2:24     
outer membrane of what they call vesicle and so modeling all that and it was very     
2:30     
different from the uh copy cell 3D stuff we've talked about very different from some of the other stuff that we've     
2:37     
talked about in terms of modeling like Gene regulatory networks and that interestingly though they were doing     
2:43     
some work with blender and uh Minecraft so doing the 3D modeling aspect of it     
2:50     
and you can get 3D modeling you know from microscopy images from uh     
2:56     
tomographic images from other types of data that allow you to actually reconstruct that in a 3D model so it's     
3:04     
it's kind of interesting stuff and then of course there's the open room stuff which is you know where you're modeling     
3:10     
cells in a body of a worm so you have uh     
3:15     
the wall of the the body wall you have muscle you have the cell bodies and     
3:21     
things like that so it's a very different type of modeling but I just wanted to get a good diversity of     
3:27     
different types of models that people try to do and you know there two different kind of     
3:32     
ways you can do this you can either model everything down to say like the atomic scale and people do that the     
3:40     
problem with that of course is that there's you know you spend a lot of computational time in building these     
3:46     
kind of models and every molecular interaction or Atomic interaction costs     
3:51     
you a certain amount of computation so if you want to model something like a cell you know that's     
3:56     
going to make it very hard to do and especially like over time because you     
4:03     
know biology happens over time so you have to sort of approach the sort of the     
4:09     
scale of the problem or Co or fine grain the problem appropriately so that you     
4:14     
can get the kind of simulation you want you can ignore the details that are may be     
4:20     
extraneous and you know be able to collect data that will allow you to um     
4:25     
build an informed model that does things that are sort of the things you would expect in nature to happen so you know     
4:33     
we don't want to build a model that doesn't do anything that an actual biological system does so uh you know so     
4:41     
we're approaching that in Diva worm and I hope maybe in the coming weeks we can maybe talk a little bit more about     
4:46     
compell 3D and you know kind of dig into what they do and how that can be use to     
4:54     
model um processes and systems     
5:00     
so um that's all about our weekly activities we had to sort of put aside     
5:07     
the uh cognition Futures and cybernetics reading group until like sort of the end     
5:12     
of this month which is fine um but we're you know we're still working on our     
5:18     
readings and some of the things there um so now I'd like to ask for     
5:24     
updates if people have them so I know Jess is traveling so yeah that you know     
5:31     
if you if you want to say something in the chat that's fine otherwise I open open the floor to anyone who wants to     
5:38     
give an     
5:45     
update um I'll just briefly you kind of mentioned some things yeah I'm uh     
5:51     
putting Futures the reading group on hold essentially until we get more into     
5:57     
June uh I'm just going to have way too much going on as I finish out sort of     
6:04     
the most intense term uh so I just think it's the right     
6:10     
thing to do for that definitely looking forward to continuing with that I just need to take a break to fin s all of     
6:15     
this stuff going on um and yeah I'm also looking forward toing the cybernetics group I think we     
6:24     
left off with the anticipatory system stuff yeah     
6:30     
so that that's that's good stuff too uh my general updates are a lot of     
6:35     
work has been happening um with joeo and related stuff uh J was     
6:43     
at the open source meeting or yeah and and     
6:49     
is sort of helping with Google summer code but also has kind of dovetail and things for the lab at     
6:54     
large um so that's it's nice to have that support     
7:00     
and you know it'll take a while but I think we'll have some useful things um for the lab and that     
7:08     
said uh joepro stuff I'm I'm really trying to reorganize a lot of things with joepro um and it's just taking time     
7:16     
but I'm I'm pretty happy with it the DSM project is still ongoing     
7:23     
too um and I'm not sure if I'm going to be able to dovetail um some things with stuff in     
7:32     
my program or not I may have some opportuni to do some     
7:39     
data kinds of analysis for a project but I don't I don't I think it might not     
7:44     
work out we'll see I'm trying to but um for sure um I did not I have it I have the     
7:52     
I've completed the draft of the post for the inclusive gaming conference and I'm just I'm kind of     
7:59     
reorganizing a bunch of my site things but I will eventually publish that too     
8:05     
and it's something I would I will definitely go over in in the lab as well     
8:11     
for C futures or just the DSM project whatever we want to do with it but um I     
8:16     
think that was that continues to be I've been thinking about that event quite a lot um both for what it was and for the     
8:25     
connections that were made there um there's a lot of     
8:31     
um a lot of connections were made along the lines of both sort of there's like     
8:38     
law students and the we robot camp we robot's one of the things that I oh I     
8:43     
actually update about we robot um now that I'm thinking about it unfortunately I don't think it's     
8:50     
happening quote unquote this year because it's been a fall event for the     
8:56     
last few years and we've done stuff with it I think it's in 2022 when it was in Seattle Washington I believe that's the     
9:03     
year it was out on the west coast I went to that and presented some stuff there and then I was at last year's event     
9:10     
too um here in Boston but I was looking into it because     
9:16     
I met a few colleagues or I guess a few connections at the connected life event     
9:22     
in Oxford and uh one of them would would be an amazing fit for we robot     
9:29     
but I was like hey you should check out this conference that has not happening but I've heard it just may be happening     
9:35     
in the springtime and I'm trying to find out who to talk to about it because I'm like     
9:41     
hey I would love to help her volunteer make happen or at least you know contribute positively to it so     
9:48     
unfortunately no we robot in the fall it's usually been like September or something uh but like I was saying     
9:56     
before that um there's been some interesting people a lot there I had an amazing conversation with people doing a     
10:02     
lot of virtual reality um not just making the like a     
10:09     
virtuality world but like trying to also create sort of a way to connect between     
10:15     
them um I mentioned that before I'll same up with that later and then a number of people just do like very deep     
10:21     
philosophical work I was I was so I don't know about you but like when I hear someone properly use affordance it     
10:29     
in a kind of conference that's not about like phenomenology directly or something     
10:35     
of that nature um it always makes me smile so like a few like two or three speakers     
10:41     
one of them is verying the philosophy the opening keynote uh Dr poppy wild I     
10:47     
believe like has this book about like post-human gaming and and     
10:53     
um really nice language about like the entanglement of identity and how like     
10:58     
when you have a Avatar it's um kind of in between spaces like is it is it us is it we is it me am I     
11:05     
playing the game am I you know is it my avatar like there's these things that happened here since of some one     
11:11     
depending on the nature of that a lot of other great points in a keynote um and just other other other     
11:21     
other people as well um that I I go into detail with some of     
11:27     
and and it's a longer blog post but I'm really for the the post not just because you know the writing is fine but also     
11:33     
just because I think some connections from the event will both affect     
11:39     
everything from society ethics Tech group to maybe some aspects of FIP Futures to definitely 100% plot Choice     
11:47     
CH which is the reason I was there um and another colleague or two was there     
11:53     
um from that group and it was just uh a lot sort of percolating in that     
12:01     
space the only other thing I guess on the radar right now is     
12:09     
um I guess there's a few things but I'll just say um oh what was it oh um I'm going to an     
12:18     
event today it's uh not super related to anything we're talking about directly but it will be essentially     
12:25     
Epilepsy Foundation event and it's a smaller event but I     
12:30     
think there'll be some good things there and I want to support some uh people in     
12:36     
that space and I'm really curious how     
12:43     
um I'm I'm pretty familiar with certain Regional events in New York but I'm I'm really curi this my first time seeing it     
12:49     
in like the Massachusetts area so we'll see how that goes I'll report back on that um dep on what we find but those     
12:56     
are my updates for now okay yeah thank you Jesse uh sounds like good stuff as usual um yeah good luck at     
13:06     
the event today and you always get uh some good information out of these events so keep up the good     
13:15     
work uh so yeah we have uh Morgan said I can update a bit later if that's okay     
13:21     
that's fine and then Sara says no major updates are my side she did present at     
13:27     
yesterday's meeting so we have her um update on her project and some of what     
13:33     
she's thinking now she did post uh a blog post uh this week and so you know for     
13:40     
the Google summer of code Community period we are doing a number of activities which we've covered last week     
13:48     
and then in Friday's meeting and so this is part of those activities is kind of     
13:54     
doing this sort of realtime Outreach where you're kind of keep keeping your notes together you're publishing a blog     
14:02     
post we used to do this every week but I don't know if it's required for the program but I would suggest that uh you     
14:10     
know people doing Google summer or code or any kind of research try to do a regular blog post like that so     
14:17     
congratulations to Sara so she published this blog post and doing some research for Frameworks to use for her project so     
14:25     
she's trying to jump start her project investigate the best approach to use and     
14:32     
so she's actually using or wants to use petting zoo which is this uh Lang chain     
14:37     
model from petting zoo so we've talked about petting zoo in the past in the group um so you know using this these     
14:45     
petting zoo environments which are like where you train a model in the environment so it's a training it's like     
14:51     
the AI gym basically where you're training the model in this environment     
14:56     
uh and then you're using Lang chain agents powered by large language models     
15:03     
so that that's an uh interesting step um so yeah you did actually push that post     
15:09     
to our medium so let me share my screen and show the medium post I just got it published before the meeting here um     
15:17     
this is uh the post multi-agent systems from reinforcement learning to language     
15:23     
models so this is a literature review uh that SAR conducted for the area so this     
15:30     
is nice to have because you know a lot of these areas the literature is very fast moving but that also means that     
15:37     
people don't really review it and you know a lot of people have different strategies for keeping up with the     
15:43     
machine learning literature keeping up with all of that but uh it's hard to really kind of get your hands around the     
15:49     
major themes so you know you might have like a like they have AR uh is it     
15:55     
archive sanity tools like that but those tools don't synthesize the literature so     
16:01     
I'm glad to see that you know we're getting some of that out of the uh as as part of the community     
16:08     
period so imagine a team of robots each with its own job they're like players on     
16:13     
a soccer field working together to score goals that none could achieve alone so this is this multi-agent systems sort of     
16:21     
multi-agent reinforcement learning approach that people have been experimenting with so you know     
16:27     
multi-agent reinforcement M learning is reinforcement learning with multiple agents multiple agents have policies and     
16:35     
they try to kind of synchronize their policies so that they can do these Collective behaviors and so people you     
16:43     
know of course have studied Collective behavior in different ways and this is one way you can implement it using uh     
16:49     
formalized um policies on agents um and then this talks about sort     
16:56     
of how this is all self organized and that it's you know I I don't know if you     
17:02     
would consider it to be leaderless but it's very distributed so like each agent     
17:08     
has its own sort of uh goals and then there's a sort of a social goal that     
17:15     
exists you know where the agents have to solve a problem and then they have to coordinate their behavior so that they     
17:21     
have you know they they maybe there's some divisional labor that emerges or there's some improvisation that emerges     
17:27     
but the point is is that you can't you know plan that out it has to sort of     
17:33     
synthesize um spontaneously and that's that's what you're trying to do in these kind of approaches so um you know if you     
17:41     
think about like swarming algorithms or other types of like Collective Behavior     
17:46     
algorithms that people use it's very similar to that so um they decide not     
17:52     
only what their next move will be but also who in the group will be the best partner for each task at hand like     
17:58     
choose how youd pass the ball during a crucial moment of the game this ability to adapt and coordinate smoothly is     
18:04     
vital to any world or are multiple agents interact and so um you know this     
18:10     
coordination is the key so you have to be able to sort of the agents don't only     
18:17     
have to match the the policies but they have to know kind of what they're sort     
18:22     
of how they're going to approach the policy without stepping on each other's toes so it's kind of like a social     
18:28     
insect Collective where you know they do have this divisional label and um you     
18:34     
know they do certain things and it's very efficient in terms of carrying out the larger task     
18:41     
so that's what we're trying to do here so she covers a couple of papers uh this     
18:48     
paper one uses sort of a probabilistic approach with reinforcement learning so there's this basy and inference aspect     
18:55     
to this sort of reinforcement learning problem uh and they use this approach called     
19:01     
basy and delegation uh an algorithm developed by them that helps artificial agents infer     
19:08     
the hidden hiddens of others by inverse planning so this is like we had a I     
19:13     
guess honu who was in the meeting uh last yesterday he had a question about     
19:20     
by turby algorithms and hidden Markov models with respect to this so I think that's an interesting     
19:26     
connection um and so you're dealing with these kind of hidden States or hidden     
19:31     
variables within other agents that you can predict and then act upon and coordinate with so that's you know     
19:38     
something that that's one way to do this is to sort of infer those hidden States     
19:44     
and then you know act accordingly or predict what those hidden States will be at any given time and then act     
19:50     
accordingly so this is an interesting approach um they're doing these multi-agent     
19:56     
mdps so uh so okay so there's this uh they're     
20:02     
evaluating multi-agent collaborations in a two-dimensional grid World which is this kitchen where agents or Chef which     
20:10     
are chefs work together to cook a recipe efficiently within a limited number of     
20:15     
time steps so they have to each have their own sort of they have to achieve this recipe and they have to figure out     
20:22     
what they're going to do so you know what are the agents what job are they going to do to uh achieve the large goal     
20:29     
of making this recipe and they have to do it within a certain time because you can't do it an infinite time obviously     
20:36     
so this models the problem is a multi-agent markof decision processor     
20:42     
mmdp where each state is defined by locations statuses and types and objects     
20:49     
of all objects and agents and then once you define those things you have a transition function which then models     
20:57     
the probability of moving from one state to another it's a very marvian approach     
21:03     
now it's interesting because the stuff that we did on active inference uh for the open source uh     
21:10     
sustainability project uh that used PDP so it's a it's a similar approach     
21:16     
where you're doing this uh maravian modeling and so we have this kind of a     
21:23     
model and people have done very various different variations on this so this is     
21:28     
definitely an approach that we've kind of somewhat explored but maybe not as     
21:34     
much as we would like and this might be you know one way to do this especially with respect to the open source     
21:41     
sustainability where you have a lot of people contributing and they have to figure out where they fit into a larger     
21:47     
project you know and there's this sort of time imperative you don't have infinite time to do things you can't do     
21:54     
things like two months later you know because there's this time Gap that occurs and so you have to coordinate in     
22:00     
time and in task space so this is a graph here I think     
22:06     
there was a question about this and you know you you're sampling from the different tasks so the agents are doing     
22:14     
things during these different phases so you know lettuce unchopped tomato     
22:19     
unchopped uh tomato chopped lettuce chopped uh and then you know add the     
22:26     
tomato and then you have plate tomato chop lettuce chop delivery you to put all those together um and they happen in     
22:34     
in time and they have to happen in a certain sequels uh so yeah that's and then the     
22:40     
second paper is enter large language models for their ability to code is these are communicative agents for     
22:46     
software development these are the large language models using chat Dev so you     
22:51     
know this is where your kind of uh training large language model uh in a     
22:57     
multi-agent uh environment and then this third one is     
23:03     
lln based agents to simulate human behaviors so this is again using large     
23:09     
language models for these generative agents and they're kind of having a     
23:14     
conversation and they're doing these interactions so this is all interesting stuff and I'm glad that uh Sara was able     
23:21     
to review all that for us like usara and it looks like sham is here     
23:30     
hello um soone hi so uh I just want to just uh     
23:37     
apologize not attending yesterday's meet uh I didn't know the timings but I'll be     
23:42     
joining from next week for sure okay yeah yeah we were just reviewing     
23:49     
our project so you know in the Friday meetings we're just going to like whoever I I would kind of hope that     
23:55     
everyone working on a project would kind of give a short update and then if you need to want to do a larger update you     
24:00     
can but you're not required to in any one week I'd like to have people do like short uh you know updates like kind of a     
24:09     
standup type thing and then you know every couple weeks you do a larger update on what you're doing so it's up     
24:15     
to you though um yeah so thank you shom welcome     
24:20     
um and and thank you welcome honu we just talking about you uh yeah so thank     
24:27     
you yeah SAR says thanks a lot for presenting the blog I don't know people had thoughts about the blog post     
24:35     
um any interesting things that I didn't bring     
24:44     
up okay um yeah I think it's it's good um definitely you know a lot of things     
24:50     
we've been talking about are uh in in the project and in some of the other projects especially with respect to     
24:57     
agents and agent Bas modeling and things like that so yeah and then you know we again     
25:04     
for the Google summer of code Community period uh we're still in that period so     
25:10     
we have maybe another 10 days or so in that period and my expectation there is     
25:15     
that you know people and even if you're not Google summer of code I think it's a good opportunity to sort     
25:21     
of look over what's going on in the in the community here kind of take stock of     
25:27     
what you could contri contribute to or what could help you uh achieve what you want to achieve so you know we have a     
25:34     
lot of content like I think we had talked about this yesterday we have a     
25:40     
lot of onboarding content we have a lot of different things going on in the lab     
25:45     
and it's kind of hard to keep track of everything because you know they different people doing different things     
25:52     
different streams different projects and it's very hard to be on top of all that     
25:58     
and myself included because I'm the one who's kind of uh helping this self-organize so um you know I I would     
26:06     
encourage people to go to the YouTube channel to the GitHub repository to the     
26:12     
website and explore those things and see if you find things that are interesting or parallel your own work or     
26:23     
whatever okay um so you know if we don't have any     
26:29     
more questions I'm going to get into something I want a feature I want to     
26:34     
talk about let me share my screen again and so um you know I've had this     
26:43     
long-standing interest in city simulations and Sim     
26:48     
City and I've been collecting some things that have been coming out uh across my feed across my uh you     
26:58     
know when I do research and I'm going to talk a little bit about some of those things now so I don't know how many     
27:04     
people played Sim City it's kind of a dated Endeavor the last version they had was like 10 years ago and it was kind of     
27:11     
a debacle around the release of that software so um it's you know it's     
27:16     
something that is a long-standing uh tradition in Computing uh the first     
27:22     
Sim City came out in the 1980s and it was yeah very good well Morgan's played it     
27:29     
and you know the whole idea was that they wanted to simulate a city because cities are actually good units of like     
27:35     
social organization self organization there are a lot of things going on in cities that are really interesting from     
27:43     
you know a computational standpoint because there are a lot of people doing urban planning there are a lot of people     
27:49     
who want to improve cities they want to be able to monitor what's going on and it's very hard to do you don't     
27:56     
understand the Dynamics so it's kind of like you know people who aren't necessarily interested in complex     
28:02     
systems are interested in you know they can understand like a city and how it's     
28:08     
self-organized and if you talk to them about self-organization using a city as an example they understand that very     
28:15     
well so but but anyways uh you know so one thing you can do of course is you     
28:21     
can simulate a city and a computer hopefully like I I just mentioned earlier oh okay Moran said my mom was an     
28:29     
herma planner so I loved it yeah um so you know I talked earlier about     
28:35     
kind of picking your sort of parameters picking your scale for your model if     
28:40     
you're building say like a virtual cell you want to have the right time scale you want to have the right spatial scale     
28:47     
and you know you want to know how many what kind of computational resources you have to fulfill that so if you have a     
28:54     
very limited system you can't just simulate everything and hope for the     
29:01     
best um in s City you know they had a certain way that they model the city and     
29:08     
then you know that would allowed you to build these simulations that could run for a long time you know many uh days     
29:16     
and nights as it was simulated in the machine and you know that's necessary in a city because you can't just simulate     
29:23     
like 5 seconds or 10 seconds you have to simulate long time periods and so if you     
29:28     
can do that then you can get some really interesting dynamics that emerge so you know in Sim City you'd have things like     
29:36     
uh you'd have riots that would spontaneously start because the people     
29:42     
who were uh the residents would not have water or not have police protection or     
29:48     
something if you didn't put it if you didn't specify it in the model there would be consequences for that so then     
29:54     
you'd have to specify it and everything else so the way the Sim City model would     
30:00     
work was that you'd have this um sort of this you know plane region and it would     
30:06     
be like a grid and you'd have all these things that you could put on the grid you could put roads housing you could     
30:13     
put police stations fire stations whatever schools and then you would just     
30:19     
let the simulation run and there would be residents that would move in and there would be activities that would H     
30:25     
unfold and this would go on on and it would kind of capture its own Dynamic so     
30:31     
you could put those things in place as initial conditions run the simulation and then if you walked away from the     
30:38     
computer for a while and came back you may not recognize what you came back to     
30:43     
because it's ins simulated so much that it has its own Dynamics and you'd have to respond to everything that's going on     
30:51     
so you know they they would give you alerts in the game and you would be able to do that now an interesting side note     
30:57     
about this is that we've talked about some of these things in cybernetics particularly like the work     
31:03     
of Gordon pasque uh and the work of some of the people doing working with cyber like     
31:10     
Stafford beer so those you know it's interesting that that actually if you     
31:16     
read about the history of Sim City it was in part inspired by the cyberneticist trying to do those things     
31:23     
they were trying to monitor very large systems that uh sometimes they were like     
31:28     
economies sometimes they were firms that were really big big corporations and     
31:33     
they're organizations that you can't necessarily get your hands around very     
31:38     
easily and they have their own dynamics that you know you get lost in if you try to like plan everything out by     
31:46     
hand um and so that that's where this came from and putting this into a computer and some people argue that you     
31:53     
can't do this effectively uh but you know this is a debate that's gone on where you know     
31:59     
maybe we build a model that you can do this in but it's not realistic enough because you have to sort of choose your     
32:07     
units of analysis and and the way you model the city that you know maybe     
32:12     
you're not realistic so Jay says uh Jess I guess also I found out Brian Eno knew     
32:19     
cybernetics in Conway's Game of Life yeah there's an edge article in the slack on that so that's yeah um ranin     
32:27     
know was a future he's a futurist I guess so that makes sense um Brian you     
32:34     
was a musician people so uh and then Sim City kind of     
32:41     
uh I guess imploded maybe 10 years ago they did a Sim City 5 where they had it     
32:47     
on a uh servers in the cloud and the cloud kept crashing and they couldn't     
32:52     
get the thing to update and so Sim City kind of ran its course     
32:58     
um then there were some other versions of urban simulations that came after that uh newer versions of things and     
33:06     
they did things differently than Sim City so what we're going to do in this feature is we're going to talk about Sim     
33:12     
City some of the things that are connected to that and then some of the data that you would use to train that     
33:18     
kind of a model so you know we're interested in machine learning training and reinforcement learning models where     
33:25     
you have data that you can put in the mix in this case what we have is we have     
33:30     
a a Bonafide simulation where we set the initial condition we run like a grid it     
33:37     
has like parameters that we specify we give it data that sort of tell it how     
33:42     
should run so it's kind of like an agent based model but we also maybe have stochastic processes that run like a     
33:49     
random number generator that run like different processes that could vary in in the real world and so we run these     
33:57     
simulations over a long periods of time and again like you know in in some in in     
34:03     
like machine learning simulations we're trying to optimize things we're trying to minimize the     
34:08     
loss but in these kind of simulations they run kind of open-ended so you run     
34:13     
them and they kind of do their thing sometimes they you know your city crashes and burns and you end up with a     
34:21     
city that doesn't do anything people ever moves out it it's destroyed whatever but but a lot of times it just     
34:28     
kind of develops its own Dynamics over time so the system changes and you have to respond to it if you can respond to     
34:36     
it and it's there isn't any imperative for optimization it's just every time     
34:42     
you know you have a set of initial conditions it continues it persists hopefully and you just have to respond     
34:50     
to it and it goes into new phases so it's a very like a very complex     
34:55     
system so that's that's a my very long-winded preface to this so this is     
35:01     
the first thing um I wanted to talk about so I mentioned that Sim City is on     
35:06     
this grid and so you know you'll have this area it looks like a a field with     
35:12     
grass but it's actually a grid underneath and so each of these like there there's a grid with different     
35:18     
squares and each square has a different value so you start out with nothing and you might put like a road through it and     
35:25     
then you put a road through it you might Zone some areas different types of things you know like housing or     
35:31     
industrial and then those things will kind of pop up in the grid but the interesting thing about this underlying     
35:36     
grid is that one cell affects the other cell so if you put something like an     
35:41     
industrial zoning here and some uh residential zoning here that residential     
35:48     
zoning will be impacted by its neighboring Grid or neighbor neighboring     
35:53     
grid cell and it will impact it maybe positively or negatively     
35:58     
and then the way to link these grid cells is to have these roads so you put down a road and then you want people to     
36:05     
have you know be able to get through um the P you know get through the city so     
36:10     
you have to kind of figure out like you know how to build an efficient City at     
36:15     
least from the standpoint of like you know getting around Logistics things like that and so you know usually those     
36:22     
things are achieved by a lot of urban planning here you just have someone any person who's playing the game just throw     
36:29     
down some roads and see what happens so it's a very different approach to urban planning because you're kind of just     
36:34     
testing hypotheses you're saying here's a road we'll put this down see if people     
36:39     
uh you know use utilize it if it's underutilized then maybe we made a mistake we could get rid of that road     
36:46     
build a new road they're different you know you can kind of destroy things and create things on the Fly too so it helps     
36:53     
you basically test a bunch of hypotheses about things so it's a very different approach to this kind of planning you     
37:01     
know hyper planning and so it it really does stand in contrast to some of the     
37:07     
urban planning stuff that happens but also maybe some of the cybernetic stuff     
37:12     
in that you know you have these cybernetic systems that are pretty open-ended and you can end up doing     
37:18     
things that are you know uh responding to unexpected events and things like     
37:23     
that so this is uh you know video not going to play the video about how Sim     
37:30     
City has the shortest Ruth paot path finding and they use something called     
37:35     
the AAR algorithm so the AAR algorithm is this algorithm that's used to Route     
37:41     
things across the grid and you know basically uses the AAR to evaluate the     
37:47     
value of each uh grid cell or parcel so you have these grid cells and Parcels     
37:54     
you kind of connect them with these roads you then evaluate you know if those things are accessible you know uh     
38:02     
how your citizens are getting around the city and then you can evaluate sort of     
38:08     
things like land values or congestion or well-being just by doing these kinds of     
38:15     
things so this just shows an example of traffic patterns using this AAR     
38:20     
algorithm but they use the AAR in Sim City for a lot of other purposes so it's     
38:25     
an interesting uh approach to the they basically have this grid they can put things on the grid they have this     
38:32     
algorithm that sort of gives you this they don't try to optimize a simulation per se but they're optimizing the     
38:39     
activity in the simulation and then they're evaluating it and you can do things about the city you can improve it     
38:46     
or you know you can change things based on that evaluation so this is so this is appears     
38:52     
to be an extremely simplistic a AAR pathfinding system with no no waiting     
38:57     
for Road density orur traffic congestion whatsoever so you throw in you have this     
39:03     
AAR algorithm that you use and then as you build the city you wait that     
39:09     
algorithm based on different conditions so if there's like traffic on these roads you would wait the uh pathf     
39:16     
finding algorithm by congestion or by desirability or things like that so it     
39:23     
helps evaluate your city it helps it grow and it helps the system kind of what things are happening and keep track     
39:30     
of the interactions and then show you the results of that if those interactions are positive or negative so     
39:37     
it's a very interesting way to do this and the implementation like I said this was done in the 1980s so it's not like     
39:43     
they used a lot of computational power to run these simulations they're you know pretty pretty easy to run I guess     
39:51     
relatively speaking compared to what you know considering what you're trying to do but they use these very simple tools     
39:57     
so there's the AAR algorithm which is the first thing and this is a GitHub     
40:02     
repository uh talking about AAR on grids so this is um you know kind of they have     
40:09     
software for this where they they implement the AAR algorithm they do this     
40:14     
on these grids this is just like in Sim City where you have this underlying grid     
40:19     
You're Building roads you're connecting different cells and you're evaluating those paths between cells and you're     
40:28     
acting upon you know whether that's positive or negative to your simulation and so this is the AAR uh     
40:36     
basically uh you know there different things like move costs you're using different uh her istics and and distance     
40:44     
metrics so they're different distance metrics if you're familiar with Manhattan distances or other types of     
40:51     
distances that allow you to calculate the cost of moving across the grid uh you know Connection by     
40:58     
connection that that allows you to evaluate some of these moves and some of the cost of some of these moves through     
41:05     
the city and depending on the structure of your city how efficient are things     
41:10     
how positively uh implemented are things how negatively implemented are things and     
41:15     
you can fix them accordingly or at least you can Target ways to improve them um     
41:22     
so that you know they're heris sixs to this algorithm they talk about some algorithmic detail     
41:27     
here uh and then some implementations so you know there are ways to implement the AAR algorithm and     
41:35     
do this in a way that's um not computationally prohibitive so this this talks a little     
41:42     
bit about AAR and implementing this on a grid this is uh this GitHub     
41:49     
repository doesn't really I don't think it's affiliated with any sort of project     
41:56     
um so the next also the next thing I want to talk about is this link to the     
42:01     
Steam Community and they have this uh article uh it's called practical engineering the     
42:08     
optimal Square grid and so um they're talking here about like building optimal     
42:15     
Square grid um this is uh I guess this is for Ci's skylines so this is not Sim City     
42:23     
but this is a sort of a thing that came after Sim City called City sky skines and so this is a newer version of city     
42:30     
simulations where they're doing things a little bit differently um in in the underlying     
42:36     
computation but they're still kind of simulating a city and so one of the things they're doing are building these     
42:43     
grids um and so they're kind of considering what the optimal size for a grid would be I have assumed that a     
42:49     
10x10 grid was best but it turns out it's not and so     
42:55     
um you know they figure they they have this you know you have this thing you go into the simulation when you kind of     
43:02     
construct it in your head that's like the best way to do things they these best practices and you know it's the     
43:08     
only thing you have because you know you you can only know if something is really good after you've tested it so you have     
43:15     
these it's kind of like in science where you have an idea and you might build a hypothesis and then the simulation     
43:21     
environment is for testing the hypothesis so it's like okay what is the best way to build this uh block uh or     
43:28     
this grid and so you say okay well maybe it needs to be a certain size and so you     
43:34     
test different sizes and you see what the outcome is so this is an interesting process of sort of evaluating these     
43:40     
things so um I'm not going to get into the details of how City skylines works     
43:46     
but basically they create this graph that shows for the 10x10 grid the     
43:52     
calculation is simple we get eight squared zable tiles and 10 Square Tile     
43:58     
area uh for a density of exactly 64% so you know this is an exercise and     
44:04     
figuring out how to build a grid that allows you to have maximal zonal tiles     
44:10     
in a certain area so that's what they're trying to optimize here so this is a graph here where they have these     
44:16     
different grid sizes uh Square so as you can see as you go up to uh 12 you get up     
44:25     
to 6 Maybe 5 and then it goes down from there so you can actually figure out the     
44:32     
optimal components to build these kind of simulations I think it's really interesting stuff and so you can go back     
44:39     
and you can do the you know some math on this to figure out the optimal type of thing so you're not trying to optimize     
44:45     
the simulation here you're just trying to optimize the components this holds true for the ASR algorithm and for some     
44:52     
of these components like tiles and other components that you need to build so I     
44:58     
really find this fascinating because you know uh in building simulations or even     
45:03     
going back to machine learning you know we think about how we optimize models and this is a very different way of     
45:10     
doing this but people have been doing this for many years so um it might be worth revisiting     
45:17     
it now we move on to this uh let's see okay so now we move on to this idea of     
45:23     
using spreadsheets and using data to build simulations and so you know now we kind     
45:30     
of got our model we have our initial conditions we can set up initialize our model with different features we can run     
45:37     
it and you know we can see what happens but how do we know like how to get even     
45:43     
where to start with that because it's just like you know when we build like a road or build a city we don't know what     
45:50     
the reasonable parameters are so you know one of the things we can do is collect data from The Real World we can     
45:57     
put in you know plug in values a range of values and see how they behave in this environment and so this also leads     
46:04     
us maybe to use this as a tool for urban planning where we can say I have this a good idea let's see if it works in the     
46:10     
real world and we can simulate it and if we have good if we calibrate it with good data we can get a good result so     
46:18     
this is uh Samuel arbisman uh substack called cabinet of Wonders he's got some     
46:24     
wonderful things on here from time to time but but this is a article that he put out recently called the spreadsheet     
46:31     
is a simulation machine and this is basically talking about um this spread the idea of a     
46:39     
spreadsheet and how you build these spreadsheets um you know there's a history of spreadsheet building in     
46:46     
Computing and people kind of maybe think that spreadsheets are p a but people use them have traditionally use them as ways     
46:54     
to sort of construct models and this is really interesting this is uh     
47:00     
visel this is an ad uh from uh I don't know if they still have visel but it was     
47:07     
an early spreadsheet this was before Excel because Excel came later uh where     
47:13     
they would build these tables basically and you know you'd have like different labels to the The Columns and the rows     
47:19     
would have cases so it's very data science oriented and so but you know     
47:24     
before spreadsheets or when spr sheets are being developed they had to develop data structures for this so it's like     
47:31     
how do you build a data structure that encapsulates rows and the columns and the cases but also in a way that I can     
47:38     
manipulate in real time so you know in a spreadsheet you would have like a bunch of     
47:43     
numbers but you also might have an equation that transforms those numbers somehow so I could take like the cost     
47:50     
and the profit and I could do some transformation of that and get a number and that number then could help me build     
47:56     
build a new variable that I could then use in in an analysis or feed it into a     
48:02     
simulation so this is interesting that we have this this tool and you know people will develop spreadsheets for     
48:08     
accounting and things like that and it's important for that but you can also do simulations in spreadsheets and so this     
48:15     
article is on how you're really simulating the world using a spreadsheet you can build like variables you know     
48:23     
and collect the data or you can generate a numberers a of numbers that are hypothetical you can put random numbers     
48:30     
in as a as a a row you can put in um or a column you can put in um you know     
48:38     
different values for something like from 10 to 100 like we saw in the last     
48:43     
example in this graph here where they they sort of had an optimization plot here where     
48:50     
they're trying to figure out the maximum so these are all things that are you know possible with spreadsheets so     
48:57     
spreadsheets are actually quite useful tools in of themselves and he's talking here about building simulations with     
49:04     
them we're using spreadsheets as a simulation machine     
49:09     
so uh this this article starts in 1984 a fusion the spreadsheet Revolution     
49:16     
the tech journalist Steven Levy wrote a long and fascinating article about this genre of software not only is the     
49:23     
article a time capsule of computing history it also gives one a sense for how people were thinking about     
49:29     
spreadsheets even then so this article is from wired a spreadsheet way of Knowledge from 2014 actually it was     
49:36     
posted in 2014 that's from 1984 uh and a quote from this article is     
49:44     
all this powerful scenario testing Machinery right there on the desktop induces some people to experiment with     
49:50     
elaborate models they talk of playing with the numbers massaging the model     
49:56     
computer hack haers lose themselves in the intricacies of programming spreadsheet hackers lose themselves in     
50:01     
the world of what if so you can you know like your big city simulation you can     
50:07     
use a spreadsheet to sort of ask these questions about what if test hypotheses     
50:12     
do these sorts of things so it's you know like Sim City is basically and I'm going to get to this is a big     
50:19     
spreadsheet essentially you have this grid you have the AAR algorithm you have     
50:24     
these other visualization features in the in the graphical user interface but at its heart it's really a     
50:31     
spreadsheet and what you're doing is basically doing operations on sort of a spatial spreadsheet where you have like     
50:38     
the spatial orientation of a grid but also that you're sort of plugging in     
50:43     
numbers over time so you have this grid that's you know X in an XY coordinate     
50:49     
system you're uh you know keeping track of what your neighboring variables are     
50:54     
doing and then your simul ating this over time so you're saying if I change this value what's the next value so you     
51:01     
can build some really interesting sort of dynamical systems out of out of these kind of scenarios but at its heart it's     
51:09     
a spreadsheet and you can Implement uh Sim City as a minimal sort of simulation     
51:16     
on a spreadsheet theoretically so this is really interesting that you know     
51:21     
thinking about it in this way and so you know spreadsheets allow us each of plus     
51:26     
to build Little Worlds and play with them seeing how small changes might make a big difference or even how big     
51:32     
differences might make none whatsoever because functions can be embedded within spreadsheet cells the words digital grid     
51:39     
essentially becomes a small constantly updating computer the embedded text elaborating an entire virtual Cosmos     
51:47     
working with both the functions and data within each cell and so uh during the ti     
51:52     
of the co pandemic I spent an inordinate amount of time playing with a spreadsheet developed by scientists at     
51:59     
the University of Colorado and this is the co estimator that focused on the aerosol     
52:04     
spread of virus particles by entering room dimensions so you can model the size of the room the number of people in     
52:11     
the room assumptions about Behavior mask usage and more I was able to better     
52:17     
understand the shape and Bounds of so many pronouncements that were swirling around so basically you can model this     
52:24     
space you have enough parameters you have enough real world data you can come up with really good hypotheses about um     
52:32     
some systems behavior and so you know it again it's not a city but it's you know the it's     
52:39     
the the philosophy of the thing um and so yeah when spreadsheets were invented     
52:45     
they kind of spread everywhere and there's a reason why they spread everywhere it's because they have this s useful     
52:51     
aspect um so yes and then of course and one of their key power is is that a     
52:57     
mechanism for thinking about the future according to computer scientist Alan Kay     
53:02     
and this is an article from computer software from Scientific American the creators of visel the first     
53:09     
spreadsheet were actually surprised that users were not just analyzing the past but trying to predict the future so this     
53:16     
is where you know you're trying to use your spreadsheet to predict the future using you know like these     
53:23     
Transformations putting a a an equation in place and asking these wh if     
53:28     
questions and allows you to predict the future and predict Dynamics and so     
53:33     
Dynamics Bridges invented by Daniel Brookland and Robert Frank Frankston as     
53:39     
a reaction to the frustration Brooklyn felt when he had to work with the old old ver paper versions in business     
53:46     
school so they used to have these pieces of paper that were like uh you know     
53:51     
ruled paper or grid paper where they would have to do things uh you know they     
53:57     
would visualize things by hand and so you could do these kind of visualizations but they weren't you know     
54:03     
in a computer so it was kind of hard to do these simulations over time and change the variables in real time they     
54:10     
were surprised by the success of the idea by the fact that most people who bought the first spreadsheet program Vis     
54:16     
aelk exploited it to forecast the future rather than to account for the past so     
54:22     
instead of using it as sort of an accounting tool people were doing these kind of forecasts activi so it's really     
54:27     
interesting how that is sort of in the nature of people using spreadsheets but     
54:33     
uh seeking to develop a smart editor they had created a simulation tool so     
54:39     
that's a really interesting point about simulation and very simple tools that we can Implement and then building these     
54:46     
large simulations Now find a couple final points about this if you want to look at     
54:51     
what uh say sim City's inputs were this is an example here where you have     
54:57     
basically these tables that you can collect from Real World data or you can     
55:03     
build like a table that's maybe a plausible data but the point is is that you need to have these uh you know you     
55:11     
need to account for the kinds of things that you would have in the real world so for example if you wanted to build a     
55:17     
structure of like energy and education in a certain region you would put in all     
55:22     
these variables um and you would you know kind of give them values you would have a range of values over a range of     
55:30     
conditions and then you could actually extrapolate from that so you could build like a starting cost where you have     
55:37     
different values for wind or solar or nuclear and then you could build these functions that would allow you to     
55:44     
interpolate values for different conditions so you can do all sorts of things with input data um and you can do     
55:51     
this in machine learning but the thing is is that you're not trying to train the model to predict you're actually     
55:57     
doing the prediction by query or by hand even um where the simulation just run     
56:04     
sweeps the parameter and just kind of samples ver values so you know it's a     
56:09     
little bit different approach to it this is the second example of uh you know     
56:14     
data so this is where you have not like continuous data but you just have sort     
56:20     
of discrete data where you have different raw materials Building Supplies this is very gamified     
56:26     
in where you have like these inventories of things materials Building     
56:32     
Supplies uh a different things like that so this is another example of the type     
56:38     
of data we might use in a kind of a simulation like this so you know again it's it's really built on data it's     
56:45     
about predicting from data you can build all this in a spreadsheet at least initially and then transform it to one     
56:51     
of these more complicated simulations and then build these really you know     
56:56     
complex uh dynamical systems from     
57:02     
them right so looks like we've got uh some things in the chat here um yeah so let's start up here um     
57:11     
so yeah we talked about Morgan's mom being an urban planner uh talked about     
57:16     
briano and hansu says that uh AAR agents are used in a lot of evaluating     
57:23     
playability and game environment settings yeah that's AAR is used quite a bit it's it's a pretty classic algorithm     
57:30     
it can be implemented in a number of ways and I should mention that AAR isn't your only option it's a popular     
57:36     
algorithm because it's pretty versatile but you can use other types of optimization algorithms or things that     
57:43     
are like aars so he posted something from research gate which is this Mario AI     
57:50     
competition article this is 2009 Mario AI competition this is from itle e     
57:57     
explorer this is uh where they did this Mario AI competition the focus was on     
58:03     
developing controllers that could play a version of Super Mario Brothers as well as possible so you're trying to build     
58:11     
like an I guess an artificial agent that plays Super Mario really well so it's kind of like the way that we do uh like     
58:17     
with h chess and go but with Super Mario and building these kind of uh ways to     
58:24     
control the play interesting um so thank you for that     
58:30     
hu um Jesse said the fatum uh the fate of many companies is still in make a     
58:37     
spreadsheet so we can see those numbers mode uh yeah it's definitely there's an     
58:42     
accounting per uh imperative for like spreadsheets in especially in     
58:48     
organizations but you know the simulation aspect is important too and yeah it does get lost it's like the     
58:54     
forest through the trees right um and so that's that's yeah it's     
58:59     
important spreadsheet City probably wasn't as fun to Market yeah there is no visualization     
59:05     
aspect and yeah that would be fun spreadsheet City that's what we should     
59:12     
do um then say I I I disagree uh uh Eve     
59:18     
online is a very popular game this this is what what is EVE     
59:24     
Online well sometimes it's it's called um you     
59:30     
know spreadsheets about space Oh okay like you're you're running you're     
59:35     
running yeah empires of spaceships     
59:41     
and oh yeah they've got their own money and they they have massive Wars and it's     
59:48     
it's really interesting I've got I've got some crowdsourced uh books on the     
59:54     
history of Eve online but anyway oh wow it basically run as a spread oh yeah     
1:00:01     
yeah yeah I think like you they games that run as a sprad it's kind of like like zor where it's a text based game     
1:00:08     
you know do things like that so yeah you if you're not not captivated by Graphics     
1:00:14     
but you're really interested in the mechanics that's that's that's for you I guess uh so yeah uh hantu says could you     
1:00:22     
share the link of this to this article very interesting yeah have the links I'll put them up on the I usually put     
1:00:28     
them in the YouTube stub so if you go to the YouTube video for the meeting they're in the stub I'll probably share     
1:00:34     
it in the uh in the general Channel as well with the     
1:00:39     
video um then Sara says this article reminds me of a project I've seen an octave from     
1:00:47     
this group here uh octave which is an open source equivalent of mat lab is     
1:00:53     
used heavily for mathematical and scientific Compu ations this project was an attempt to connect it to library     
1:00:59     
office Kelk which is an open- Source spreadsheet um and then bring this     
1:01:05     
together uh tabular formatting data with visualization capabilities yeah yeah     
1:01:11     
it's a a good way like to interface usual we interface things with the uh     
1:01:17     
tapto Limited Format CSV that's just a way to bring data into your system to     
1:01:23     
interact with it and to transform it different ways ways you need to have you know different tools for that so it's     
1:01:29     
you know it's interesting that spreadsheets are fundamentally different from CSV csvs are like bringing     
1:01:35     
something into a into a environment in a very efficient way so you don't have to     
1:01:41     
worry about the formatting you know you can bring it in as cases and variables     
1:01:47     
but then of course the spreadsheet allows you to do interactive things with it so it's kind of an interesting     
1:01:54     
approach there and then hu said Robin bomb Gardens a star agent that won the     
1:01:59     
Mario AI competition and has used a lot in 2D game settings yeah yeah I'm not     
1:02:06     
yeah I wasn't familiar with the Mario AI competition so that's an interesting find I don't know if yeah you want to     
1:02:13     
talk about it more or not     
1:02:19     
but so that's all I have on that um I I hope you found that interesting I've been kind of collecting those things I     
1:02:25     
wanted to go through it you know visal is is is famous or you     
1:02:31     
know yeah I I haven't seen that a long time yeah it's like every so often um if     
1:02:39     
you follow Dave Winer you know who who developed RSS and a number of other     
1:02:47     
things but you know kind of known for RSS and podcasting he'll talk about the lessons     
1:02:54     
learned from visit count you know from time to time he's such an old school Silicon Valley guy     
1:03:01     
yeah but yeah it's Sim City stuff's always     
1:03:07     
funny to me because I I kind of grew up with my mom talking about like arcgis     
1:03:12     
modeling and traffic simulations and you know how how governments ignore ignore     
1:03:20     
you know good simulation good shows if you build build more roads you know they     
1:03:25     
they're just Banks more cars right     
1:03:32     
yeah as well as the S City you know the the the winning strategy seemed to be     
1:03:38     
somewhat um totalitarian right you know like like     
1:03:43     
why was that yeah yeah yeah yeah the trouble the     
1:03:49     
trouble of getting a dominating with a democratic government was very     
1:03:57     
yeah this is an yeah it's an interesting point there are some CR critiques of Sim City that they're not it's not realistic     
1:04:04     
in that way that they kind of build it tilt it so that you can win it but it's     
1:04:10     
hard to like do so where it's not uh you're not rolling with an Aran fist I     
1:04:15     
guess um yeah so it's you know uh I don't know but but it you know and     
1:04:24     
it's one of those things like like like again like when you get these computational agents to play video games     
1:04:30     
right and then you find that they they they develop a strategy that's a winning     
1:04:37     
strategy but you're like but hey wait that that's cheating or you know like     
1:04:42     
but that's not the way to play it but but you know by by the actual     
1:04:48     
rules that's that is the winning strategy or you know that is the Superhuman strategy right and and you     
1:04:56     
yeah anyway the um uh it does make me     
1:05:02     
think again of um the the AI Economist as as the the     
1:05:08     
closest thing I've seen to you know good simulation of of actual     
1:05:14     
you know actual public policy right the the the way the way     
1:05:20     
you'd want it yeah yeah yeah you mentioned superhumans strategy so that     
1:05:26     
was something we've been talking about in the context of AI and it's interesting that you know our language     
1:05:32     
is kind of like this is the strategy for planning but like what well so what's     
1:05:39     
happening is the SI the simulation is running underneath right like everything is sort of running underneath and it's     
1:05:45     
not controlled by any one person unless you're talking about how people regulate it and so like you know when we interact     
1:05:52     
with something like a very complex system it's kind of like interacting with uh biological system if we're     
1:05:58     
building like maybe like an implant or even a medical intervention where we     
1:06:04     
have this system that is going and has its own dynamics that we kind of     
1:06:09     
understand but we you know we can control but it's hard to control without having some unintended consequence     
1:06:16     
somewhere else so we're just kind of you know trying to figure out how to intervene without um destroying the     
1:06:23     
system and you know doing our best there and it's it's it's kind of an interesting parallel because you know     
1:06:30     
it's like can we build a system that really regulates uh a very complex system like     
1:06:37     
that without you know maybe the reason why only the ironfist strategies work is     
1:06:43     
because it's basically that you have to do that to control all the variation that's happening and you know it's     
1:06:49     
probably not tenable yet either which is the other problem uh but yeah yeah you     
1:06:55     
know again I I I feel like it's     
1:07:01     
more for the programs that that it is easier to have     
1:07:07     
this kind of centralized control Master     
1:07:13     
Loop right than than to um to to know how     
1:07:22     
to you know uh generate control from Collective     
1:07:28     
action or you know generates generate a kind of     
1:07:35     
yeah complex homeostasis I don't know try try to find     
1:07:41     
the right word that's not control because like control like already kind of gives the game away right     
1:07:48     
right uh um did the um active inference     
1:07:53     
Institute talk yesterday was on     
1:07:59     
um was on extension they they did um an active inference drone Control software     
1:08:07     
okay so like trying to make trying to make a a drone more autonomous in the     
1:08:14     
like it's it's setting its own destinations kind yeah and then then this this week's talk on this from the     
1:08:22     
same group was was basically about the interface for for um agent agent     
1:08:28     
communication so like how how to get them now like not only to to be     
1:08:33     
autonomous but to also interact with other autonomous agents and you I I'm I'm     
1:08:41     
curious what the you I'm curious what the flocking behavior looks like oh yeah     
1:08:47     
for for instance yeah yeah yeah but just some interesting questions about how do how does agent     
1:08:54     
agent communication differ from agent environment understanding and if it     
1:09:00     
should differ at all yeah     
1:09:06     
yeah so yeah that's great U did we have any other questions uh about any of that     
1:09:14     
any other comments all right if not then I don't     
1:09:20     
know if Morgan wanted to give an update and know he he said he might do so later     
1:09:26     
yeah so we we started the how to grow almost anything synthetic bio course     
1:09:33     
here which has been interesting um I think we     
1:09:38     
could benefit from a a longer     
1:09:44     
um benchling focus so I I've dropped a link in the I'm I'm looking for     
1:09:52     
good yeah I I don't know what to call it it's not     
1:09:57     
I'm not looking for genomic tools but like for these kind of genomic manipulation um so again like for those     
1:10:04     
who who know benchling like what are what are tools that that are like benchling that we have more control over     
1:10:12     
aren't just a web interface uh and you know the this is um yeah kind     
1:10:22     
of the Bas basic things for designing um     
1:10:28     
um yeah designing plasmids designing you know designing experiments with     
1:10:34     
them um and so I dropped a link to the UCLA     
1:10:41     
bioinformatics what they call it but Co collaboratory     
1:10:46     
anyway that has that has like so far the nicest breakdown I've seen of kind     
1:10:53     
of um yeah many courses and kind of which courses depend on which other     
1:11:00     
courses so as you you know get get more experience to get to more advanced um     
1:11:07     
kind of Unix tools um let's see what else we've done     
1:11:15     
um I know we've done some more things well just uh just interesting meetings     
1:11:20     
on um tuss so probably talking about um     
1:11:27     
transrenal focused ultrasound as a neuromodulatory as a neuromodulatory     
1:11:34     
device so these are kind of things that have traditionally been done with um     
1:11:39     
with electricity using electrical stimulation     
1:11:45     
or or magnetic um TMS and this is um yeah I've um again I     
1:11:56     
I drop a I drop a lot of these links in the neurot X     
1:12:01     
slack um and um which which I do recommend if you are interested in in     
1:12:08     
this kind of Nur because there's um yeah there's interesting workshops that are     
1:12:14     
at least online if you're if you're interested um to see people present on     
1:12:20     
this but uh um yeah we doing some events here in     
1:12:26     
San Francisco on that are neurotech related um and um yeah Jess might be interested     
1:12:35     
in this rard do paper that I dropped into computational Psychiatry for and of     
1:12:41     
DSM or post post     
1:12:46     
DSM two two interesting papers one about the connection between you know historic     
1:12:52     
connections between neurology and Psychiatry well I should say historic     
1:12:57     
splits between between the two but how they should perhaps yeah benefit from from     
1:13:05     
new thinking in both both Fields um and I'll look around for some     
1:13:11     
other papers but yeah yeah that's great thank you     
1:13:17     
Morgan uh yeah that's always good stuff um you share that paper actually it     
1:13:24     
looks kind of interesting so this is the paper he's referring to this Bridging the Great Divide what can     
1:13:30     
neurology learned from Psychiatry so this is um you know kind of going over     
1:13:37     
the historical origins of both fields and then kind of how they rely on similar tools to study brain     
1:13:44     
disorders so you know one of the things we're trying to do I guess in computational Psychiatry figure out how     
1:13:50     
to use computational tools or sort of Psych Psychiatry how to improve     
1:13:56     
Psychiatry with different computational tools but also some of the physiological     
1:14:01     
tools that you know are up and cominging so uh that's that's if you go to the     
1:14:07     
channel that's you know kind of the theme of the channel so this kind of goes over this     
1:14:13     
history neurology and Psychiatry are kind of sharing these tools uh sharing common historical     
1:14:20     
Origins yet the Practical integration of medical and scientific approaches across     
1:14:25     
these clinical neurosciences have remained Elusive and so uh what while     
1:14:31     
much has been written about the need to incorporate emerging systems level cellular molecular and genetic     
1:14:37     
epigenetic advances into a science of mind for psychiatric disorders less     
1:14:43     
attention has been given to applying clinical Neuroscience principles to conceptualize neurologic conditions     
1:14:49     
using an integrated neurobo psychosocial approach this is like where they start     
1:14:55     
getting into these hyphenated terms basically situating this in different a couple of different     
1:15:01     
fields simultaneously so you have the neurobiology you have the psychology or     
1:15:07     
the psycho aspect and then the social aspect uh in this perspective article we     
1:15:12     
briefly outline the historically interwoven and complicated relationship between neurology and     
1:15:19     
Psychiatry and then how some traditional psychiatric conditions are being reconceptualized     
1:15:25     
is part of disorders of neurodevelopment and awareness so you know this is where you're taking what we've known from     
1:15:32     
Psychiatry and reconceptualizing it in this neuro biosocial psychosocial     
1:15:40     
approach um and then this divide between neurology and Psychiatry can be narrowed     
1:15:47     
by moving from lesion-based toward circuit based understandings of neuros psychiatric disorders from     
1:15:53     
unidirectional toward bidirectional models of brain Behavior it's usually you know in Psychiatry it's like the     
1:16:01     
brain creates the behavior and in fact it's this inner inner relationship it's kind of like uh     
1:16:08     
brain environment or you know Behavior environment type of relationship where their     
1:16:14     
interactions uh and then you know going from categorical diagnoses towards sort of trans     
1:16:21     
diagnostic dimensional perspectives and Silo based research toward     
1:16:26     
interdisciplinary approaches so it's a good paper I think for probably for our computational     
1:16:34     
Psychiatry Endeavor but also of course Jesse and and Jen Gian are working on the uh psych uh working on the DSM stuff     
1:16:43     
so that that might be interesting there as well okay um let me go to the chat uh so     
1:16:50     
Sara put this archive paper in the chat and she says this discusses agent agent     
1:16:56     
and agent environment communication to quite a good degree so this is this paper on multi-agent     
1:17:03     
collaboration harnessing the power of intelligent large language model agents     
1:17:08     
and so this kind of goes into some of these um talks about Auto GPT and baby     
1:17:14     
AGI models so that's interesting we've talked about of course developmental AGI     
1:17:19     
I didn't know there was a baby AGI category but um this is interesting     
1:17:25     
stuff so that's that's an interesting reading um Paula said hello everyone a     
1:17:31     
bit late and tired here I cannot find the naroch check channel on slack I may     
1:17:38     
have to be invited to that so it's it's usually this channel here uh virtual reality neurotech okay     
1:17:45     
yeah you joined it so good I I think I think she was I was     
1:17:51     
referring to the Nur X slack oh yeah yeah yeah and um yeah so if you go to     
1:17:57     
nurx.com and you you you know sign up     
1:18:03     
it's free it just it's just collecting your info and sending you a sending you     
1:18:08     
a slack invite yeah and then slack collects your data as well yeah now     
1:18:15     
slack is yeah slack is trading on trading out my 10 years of     
1:18:20     
nyic comment yeah well yeah okay so yeah the     
1:18:27     
slack issues not withstanding yeah it's in the neurotech ACT slack uh but yeah     
1:18:32     
that's that's great um yeah thanks um yeah so that that'll be an     
1:18:37     
interesting thing to look at uh some of these different tools and techniques we haven't looked at the computational     
1:18:44     
Psychiatry channel for a while we might do that actually I don't know how much has accumulated there but     
1:18:51     
um I think we got the exercise training uh I think that's something we covered     
1:18:57     
in I think two weeks ago um you know there's some interesting     
1:19:03     
videos in here um anything you'd like to highlight Morgan I me um yeah slack has also     
1:19:11     
gotten very slow yeah um I um well yeah     
1:19:19     
I I dropped in this this link about um about chat boot um that     
1:19:27     
uh again I I you know put in things like     
1:19:32     
that um I mean sorry you know you're passing things that now I'm like oh yeah     
1:19:37     
these are great sorry like we should all stop what we're doing it's very     
1:19:44     
tempting PA Thompson has to say uh but perhaps more General um just just about     
1:19:51     
chatbots again um in Psychiatry and and you know I think maybe it's also because     
1:19:58     
I'm here in San Francisco where everybody's you know trying to monetize     
1:20:03     
Psychiatry U chatbots are the you know     
1:20:09     
the people think of it as the low hanging fruit now because llms have you know ducked all the the oxygen out of AI     
1:20:17     
right yeah and um again I just think     
1:20:22     
it's it's good to you know just understand how how you     
1:20:29     
know completely um novel these are and and how you know like we don't we don't     
1:20:37     
understand therapist um patient Dynamics well yeah so so to to     
1:20:46     
start to start throwing throwing people at chatbots would be you know be way too     
1:20:53     
way too early um and you know again like I I appreciate what um hin had to     
1:21:03     
say about what we you know what we would want you know like where we want these     
1:21:10     
things to go but it's really important to understand like how they how they end     
1:21:16     
up getting used and and you know what um     
1:21:21     
yeah again like like yeah like more field research     
1:21:27     
essentially where we're not controlling you know and just seeing like what what     
1:21:33     
are the kind of natural dynamics that people fall into with chatbot as it is you know probably again     
1:21:41     
I I haven't done enough of this but I think it would be related just what are the Dynamics that people get into with     
1:21:48     
all the algorithms you know in the sense of you know people talk about you know     
1:21:53     
being being radicalized by YouTube being radicalized by Tik Tok being radicalized by you know     
1:22:00     
um Facebook right and and um yeah so this is you     
1:22:08     
know sometimes I I put these things in as because they they resonate as a you     
1:22:14     
know this this highlights an issue that we should think about more and and um uh     
1:22:22     
and and it's one of those things that it's like um I find the conversations around it to     
1:22:30     
sometimes be a lot like the conversations around micro doing which is you know another kind of popular     
1:22:38     
psychiatric Trend yeah um where it's just like you know too much anecdotal     
1:22:44     
evidence too much and too much you know um you know it's initial studies Focus     
1:22:53     
too much on on metrics in which you know the they     
1:23:00     
are biased to to do well on or you know     
1:23:06     
it's it's it's kind of normal at first for people to focus on things where     
1:23:11     
they're where they're kind of expecting effect as opposed to collecting you know     
1:23:19     
a wide range of data and then seeing you know learn learning more right and     
1:23:24     
especially learning about what they what they didn't expect and um and um you     
1:23:30     
know and and I think this is why we see again I'm also trying to understand the     
1:23:37     
the you know Common problem in Psychiatry where we have we have um     
1:23:43     
treatments and you know novel novel approaches that do you know have a kind     
1:23:50     
of initial period where it's it seems you know know promising and and studies     
1:23:56     
are positive and they pass you know 0.05 significance and and then you know five     
1:24:04     
years later they're they're not and meta reviews met meta analyses are showing     
1:24:09     
you know so it's like is it is it just you know numbers is it the the metrics     
1:24:16     
that we're using again how to how to explain these things and as well as like we still seem     
1:24:23     
to be going for um you know we seem to be going for interventions that are     
1:24:32     
are doing better than PBO right which     
1:24:37     
which which is already putting us in in some quite     
1:24:43     
High statistical noise yeah yeah there's the aspect of     
1:24:49     
using data like using more than anecdotal evidence and then there's the issue of you know effect size so what is     
1:24:57     
the effect size of something and and and you know again I     
1:25:05     
see I see UK biobank just hitting you know one like     
1:25:13     
major announcement after another in terms of you know absolutely     
1:25:20     
new science right you know big they've got 40 thou you know because they're     
1:25:26     
doing this just massive data collection and and where they're able to     
1:25:34     
you know see physiology of people before they're sick     
1:25:40     
right so big big announcement that that you know I think was this week you know     
1:25:46     
um something like 160 proteins that changed in you know 10% of     
1:25:55     
people who you know have been a part of this massive data collection and then     
1:26:01     
they developed cancer um years after so I think it was you know     
1:26:08     
maybe yeah like like a huge number like seven years before and then a smaller     
1:26:14     
number like three years before that's that's um that is I think is is part of     
1:26:21     
why I'm seeing this this big um this big push on kind of liquid biopsies and and     
1:26:28     
blood tests you know in the kind of startup     
1:26:34     
medical you know Medtech um and you know I um yeah just     
1:26:41     
just that like like we we need we need more of that oh oh sorry one One update     
1:26:47     
I I had a good meeting with Med Arc which is a community um U community group that's     
1:26:55     
focused on kind of foundation models for for medicine let's or     
1:27:02     
Medtech and the med Arc seems to be getting a lot of support from stability     
1:27:08     
AI which is the the company behind um stable diffusion right or you know it     
1:27:15     
got got a lot of this um curent Curt Buzz going um and the U the head have a     
1:27:24     
head of neur Imaging in AI Paul Scotty um who's who's part of a lot of     
1:27:32     
these um Discord groups um now the the the particular one     
1:27:37     
that I joined was um was focused on brain inspired Transformer models so     
1:27:42     
they were really kind of trying to do a a neuro AI um but but it was it was interesting     
1:27:50     
that um that uh the person leading that meeting was at     
1:27:57     
the the child MIND Institute and and so you know at first I     
1:28:04     
was like so well like oh you're at the child MIND Institute you know love the healthy brain network data set so where     
1:28:10     
they're they're doing this you know biobank like UK biobank     
1:28:17     
like study of collecting 10,000 you know data from 10,000 kid you so it's it's     
1:28:22     
you know it's sort of like ABCD as well which is Big N study and just you know     
1:28:29     
but but even better is the longitudinal aspect of it right so you know like like     
1:28:36     
how many of those how many of those fivey olds in the child you know how many how many of those say five to 10     
1:28:43     
year olds in the child MIND Institute data set are going to develop a a you know     
1:28:51     
major mental health diagnosis and you know adds adds 12 to 15 something like     
1:28:58     
that right and and you know how much we could     
1:29:03     
get if we actually had you know um blood and and other you know say um you know     
1:29:12     
proteomics again like you know really getting at physiology and and molecular     
1:29:19     
biology of those kids um pre     
1:29:25     
pre-diagnosis and and how how little of that is going on in Psychiatry which is     
1:29:31     
you know um which is not to say that this explains everything that we're we're discussing but you know at the     
1:29:39     
same time like you see with that with the computational um with the the paper     
1:29:45     
on exercise like like you know there's a lot there is a     
1:29:52     
lot more going on that and and and we can track all these things you know and     
1:29:58     
so I I think you know just to to come full circle to that history of Neurology and Psychiatry you know there     
1:30:08     
there you know there was an unfortunate shift away in the in the you know kind     
1:30:14     
of like 20s to the 50s 60s away from a a     
1:30:21     
wholly physiological you know molecular approach to     
1:30:27     
Psychiatry that that you know as the the I always push the the Mind fixers um uh     
1:30:36     
history of Psychiatry shows that like you know that I think we're still dealing with that Legacy yeah and you     
1:30:43     
know that the the more we take you know an oncology like     
1:30:48     
approach um I think the the better and um and     
1:30:54     
yeah then the the the the group that I see doing the most of that I mean the longevity groups I think are interesting     
1:31:01     
because of this this aging problem that you have in with with Pat Psychiatry     
1:31:07     
patients um dying so young uh but Indiana's the he of Psychiatry has a has     
1:31:15     
a very you know blood biomarker based approach to Psychiatry that's in again     
1:31:22     
is really interesting yeah yeah definitely it's uh you know we     
1:31:28     
saw from those or from a lot of the big data I guess you could call Big Data     
1:31:33     
approaches or multi measure approaches is that there's a lot first of all     
1:31:38     
there's a lot to put together so it's like understanding like and usually the way we do this of course is     
1:31:44     
dimensionality reduction we're kind of comparing different metrics so you know     
1:31:49     
for each metric if you have like metabolomics podium are going to have different signatures and then putting     
1:31:56     
those together figuring out how those go together and contribute to some sort of prediction down the line so you know you     
1:32:04     
have that approach and then you have the dimensionality reduction approach which is that things are going to share some     
1:32:11     
variant and we can reduce it down to those things that share enough variants that are     
1:32:16     
productive and of course this does work but there probably other ways to do this     
1:32:21     
as well and I thr you know I I don't know what the answer would be there but there's just you know again     
1:32:28     
it's it's a a matter of like you know our understanding of things and how much we can sort of abstract away from the     
1:32:34     
data and build a model of it and you know use that as a     
1:32:40     
tool yeah you know um Emily is it I think it's Emily Bender is it the     
1:32:47     
linguist yeah yeah yeah and and her awesomely named podcast um like mystery     
1:32:55     
AI hype Theater 3000 I think it's something like that     
1:33:03     
yeah she I forget the guest um that was     
1:33:08     
on but they were talking about these automated lab     
1:33:14     
platforms and you know and I understand what they were saying in terms of oh you     
1:33:21     
know like this is just what don't need you know like machines generating     
1:33:27     
papers that aren't even readable by by humans you know certainly there's plenty     
1:33:35     
to talk about in terms of you know the the massive GPT written papers that are     
1:33:41     
I'm sure flooding editor boxes um but at the same time when you look at something like you know that um     
1:33:50     
kind of molecular biology of exercise yeah you know like like there's there's     
1:33:55     
also a lot of stuff where it's like like humans don't need to necessarily be     
1:34:00     
involved in tracking the 3,000 metabolites and you know you see what I     
1:34:06     
mean like yeah yeah I know what you mean like I     
1:34:12     
I I would I would hope and I would expect that there's actually a middle ground there where there's there are     
1:34:20     
things that that we can um that that we can change about how     
1:34:26     
science is done and and yet you know we can also insist on the the science being     
1:34:34     
you know human um happen having human oversight and     
1:34:40     
human interpretability and human understanding right     
1:34:46     
yeah um and yeah and it's it's always that middle way that's the that's the     
1:34:53     
hardest um yeah uh yeah so it's like you know     
1:34:59     
again with a lot of these high put methods you know we're kind of like     
1:35:04     
getting these massive samples we're analyzing them and of course in a sort of like if you think about molecular     
1:35:10     
biology the way analysis works so you have you're putting in some things and you're doing some reactions and you're     
1:35:17     
getting some output and output then has to be normalized and like you know     
1:35:22     
debiased so you have these technical things that you have to do the measure and then you have a measure and you say     
1:35:29     
what does this mean and so then you know it's like okay I can compare it with maybe you know sometimes we do     
1:35:35     
comparisons like we'll do like a wild type versus a mutant we'll do like a a     
1:35:41     
resting state versus a active State we always try to create these conditions     
1:35:46     
where we may have some idealized condition and then whatever condition it is we're interested in and so again you     
1:35:52     
know it's like this intersection of like how we can devise a way to make these comparisons and how we generate the data     
1:36:00     
and how we map like what is it basically a technical output to something that we     
1:36:06     
can say this is a good measure of the thing that we're trying to get a handle on because the measure itself is like     
1:36:13     
arbitrary even though it's in numbers it's like we're creating this technical tool that gives us this stuff this     
1:36:20     
output you know how does that relate to some can we make like can we create a measure     
1:36:27     
or can we create a tool that allows you to have measures that have discret states that map to some     
1:36:34     
disorder and that's really that you know and there's a lot of work that goes into like perfecting tools like that too like     
1:36:41     
you know with PCR for example you know people optimize PCR so that you can get     
1:36:46     
uh good you know technical outputs that are repeatable right so people work on     
1:36:51     
it they don't just throw things in a re action and then just hope for the best um but you know that's that's the kind     
1:36:58     
of thing we're dealing with so it's not just a matter of like you know having an     
1:37:04     
interpretable method uh for for kind of you know doing an analysis it's also     
1:37:12     
kind of getting the data and getting the measure of     
1:37:18     
something and so you know we we've worked you know there there are all these things that we've developed in     
1:37:23     
science like standardized units which are like you know if you have a standardized unit of something the     
1:37:29     
reason we do that is because we want to be able to say from any one person to any other person taking a measurement     
1:37:36     
say of temperature that you can compare the two things so like I If I say it's 68 degrees Fahrenheit you say it's 68     
1:37:44     
degrees Fahrenheit we know it's there's some reliability in that observation otherwise it's kind of like     
1:37:52     
we don't have any way to validate the observations you know if I say it's 68° and you say it's 68° just by like you     
1:37:59     
know going outside and making an estimate you know there are a lot of things that go into that estimate that are     
1:38:05     
unreliable and so um it's definitely definitely you know so we have the tools     
1:38:11     
we have the techniques of like formalization and then we have the visualization techniques or the an     
1:38:17     
analytical techniques that are important see yeah I think there's yeah     
1:38:24     
there's a lot there um there a lot there of interest um yeah so the looks     
1:38:30     
like we lost a bunch of people um and uh I know it's late in a lot of places so     
1:38:37     
um yeah but yeah I mean going back to the computational Psychiatry Channel if     
1:38:43     
people want to check that out there there's a lot there uh this is actually     
1:38:49     
something Hussein posted on shout out to the developer Roblox this is uh oh they're using okay     
1:38:57     
so this is where the they're using neuro they're     
1:39:03     
developing something called neuro blocks a software platform developed uh that     
1:39:08     
will model brain circuits to treat brain disorders I'm interested in this neural     
1:39:13     
blocks uh so this is actually where they're taking inspiration from     
1:39:20     
Roblox uh they're doing modeling with so Roblox of course if people aren't aware     
1:39:25     
it's this virtual world where you build things of blocks and you can like stack them or build     
1:39:32     
structures uh and then you know this is something you can Implement on a headset or on a smartphone or     
1:39:39     
whatever uh right now there's a disconnect between the aims of clinical research and the computational tools we     
1:39:44     
have to exploit that uh so there's yeah people are doing a lot of stuff with uh Roblox which you     
1:39:53     
know uh it basically allows you to sort of visualize some of the stuff so you     
1:39:59     
can put things into a world where you can get insights and again you know underlying that those models there a lot     
1:40:06     
of numbers a lot of input data but you know we have to have some way to interpret it um it's     
1:40:13     
interesting uh yeah and then of course we did the exercise paper we did this     
1:40:19     
chat Bots there's a yeah there's a good one there on the genetic     
1:40:24     
atlas of embryo you know of the human embryo human brain yeah just that new     
1:40:32     
genetic Atlas yeah yeah okay but you know this is this is very     
1:40:38     
specific well this is another one but again you know there's just all this new data that's coming together you know and     
1:40:46     
and kind of going back to last week's um conversation with paa like like you know     
1:40:53     
these these great databases that have all this new you know all these new     
1:41:01     
results um but it would be great to link them to you know the the the the the     
1:41:09     
database that came out six months ago that had you know the weeks before that right yeah that that's that's being you     
1:41:16     
know put together by a different Consortium of of multi-site universities     
1:41:22     
right yeah um and um yeah yeah     
1:41:30     
um and I I I wanted to just also you know sorry just check     
1:41:37     
checking my LinkedIn there that Nur match has some new announcements um     
1:41:42     
calling for mentors but also um uh research     
1:41:49     
collaborations oh I hadn't seen that part they um yeah just uh sorry I'm just     
1:41:57     
my my internet seems very slow but um I'll I'll pull it up here um what did     
1:42:05     
they say um research Partnerships yeah exciting introducing our research     
1:42:11     
Partnerships program um if you are a researcher looking for help with software machine     
1:42:17     
learning pipelines or scaling your research to cloud services we can connect you with a suitable partner     
1:42:24     
yeah so Nur match. ipartner     
1:42:30     
okay and um I think also some other you know some     
1:42:38     
some other things that they've been doing in terms of um um yeah try trying trying to I mean I     
1:42:46     
think it's maybe slash Mentor but you know again trying to connect students     
1:42:52     
together together with with you know um people people to give them a early     
1:42:59     
career advice and things like that yeah I I will once again be     
1:43:05     
mentoring your neur match and like they they will have the neuro AI courses here     
1:43:10     
so they have the Deep learning course the computational neuroscience and now     
1:43:16     
the neuroi actually I think they may have changed the Deep learning course in the nuro AI course I'm not too sure but     
1:43:24     
uh we'll probably go through the narrow AI course uh this year so what we did in years past is we would go through the     
1:43:32     
they have the curriculum sort of as an open curriculum and the idea would be to try     
1:43:37     
to get the go through each week's curriculum and then just kind of like hit the highlights of that curriculum     
1:43:44     
you know for the group so we can talk about it uh Jesse has perpetually been     
1:43:49     
talking about doing this slow pod which is where you take the materials and you break it out into like multiple weeks     
1:43:56     
and kind of go through very slowly so you can get a sense of because they go through very fast and they kind of dump     
1:44:02     
it on you this would be like very a very slow kind of working through the     
1:44:07     
curriculum so that you know that's those are very interesting approaches to sort     
1:44:12     
of educ open education so we'll be doing more about that this     
1:44:17     
summer uh okay Paula has some things on the chat here um thanks Morgan I'm looking at the     
1:44:24     
page on neurom Match let's see if it leads anywhere     
1:44:30     
interesting um yeah so let's see uh let me go back     
1:44:36     
to sharing my screen uh let's     
1:44:43     
see okay so I did I didn't want to talk about this uh set of papers here um     
1:44:53     
so this is uh a topic of sort of modeling cultural Evolution using large     
1:44:59     
language models so we've talked about larg language models as sort of this way to implement or you know to connect it     
1:45:06     
with reinforcement learning and larger language models for therapeutic means and     
1:45:12     
Psychiatry this is a paper on cultural Evolution and populations a large     
1:45:17     
language model so we have of course biological evolution we have cultural evolution cultural evolution is     
1:45:24     
basically where you have cultural practices or cultural norms and you have     
1:45:30     
you can see evolution in that and in language it's you know really nice to see cultural Evolution because you'll     
1:45:36     
see like different terms change over time and different grammars change over     
1:45:41     
time so this is where you know this is where they're going with this they can model cultural evolution in a system     
1:45:48     
that has some relevance to like what we see in in humans which is kind of the     
1:45:53     
point of this so this is uh Pierre EOD deer who's at uh in the flowers team at     
1:46:00     
uh Ina which we talked about their stuff last week with respect to modeling uh     
1:46:05     
Gene regulatory networks and their competencies so we talked about that work last week they had a nice set of     
1:46:12     
demos open source demos a nice set of work that they're doing on that but they're also doing this work on cultural     
1:46:19     
Evolution and large language so let's go over the abstract and then maybe get into the some of the     
1:46:25     
paper and then I have some other things along side of that so um research in     
1:46:31     
cultural Evolution aims at providing causal explanations for the change of culture over time so basically in     
1:46:39     
cultural Evolution we're interested in building things like philogynes or     
1:46:44     
building like things like what they call seriation of of cultural artifacts over     
1:46:49     
time so like in um archaeology they'll often build like they'll take artifacts     
1:46:56     
from a site and they'll order it by its temporal in its temporal order so     
1:47:02     
they'll start at the most ancient thing and they'll go to the most recent thing and they try to figure out what those     
1:47:08     
are what those changes what the order of those changes are you can also use in     
1:47:13     
linguistics especially a philogyny which assumes that you have these sort of     
1:47:19     
common ancestral forms that Branch off and produce variance over     
1:47:24     
time so they're interested in the causal aspect of this over the past decades this field     
1:47:30     
has generated an important body of knowledge using experimental historical and computational methods while     
1:47:38     
computational models been very successful generating testable hypotheses about the effects of several     
1:47:43     
factors such as population structure or transmission biases so you know cultural     
1:47:50     
Evolution happens in populations you have you know a bunch of people that are     
1:47:56     
interacting they have this culture culture is conf Vision they can they can     
1:48:02     
break apart into two or more cultures over time and you know but you need to     
1:48:07     
have this population aspect and then transmission biases or when cultural     
1:48:12     
practices are transmitted from say like a tutor to a student or from a parent to     
1:48:17     
a child uh they may give every piece of     
1:48:22     
information or they may only give certain information or some cultural practices are preferred over others so     
1:48:29     
that transmit they're transmitted in a biased way and so you can model all these things and and that's what they're     
1:48:35     
going to do here uh so they're they're they have hypotheses about these effects     
1:48:42     
some phenomena have been uh so far been more complex to capture using agent based informal models so you know     
1:48:49     
they're trying to use these different types of model mod in tools like phogy and other types of categorical tools but     
1:48:56     
also you can use agent based models because you can have mod a population of     
1:49:01     
agents that pass things on to their descendants and then you have some uh     
1:49:07     
you know generative data that you can in mind to see what what the cultural Evolution looks like this in particular     
1:49:14     
is the case for effect the effective transformations of social information induced by evolved cognitive mechanisms     
1:49:22     
so this is what where we're interested in Social information and in populations     
1:49:27     
and we're interested in sort of these cognitive uh the intersection between     
1:49:33     
cognition and culture we here propose that leveraging the capacity of large language models to     
1:49:40     
memic human behavior may be fruitful to address this scap so they're going to use large language models they're going     
1:49:46     
to use the sort of the generative capacity of or language models and they're going to pass things on to     
1:49:53     
Offspring large language models I guess to model this sort of     
1:49:58     
process on top of being useful approximation of human cultural Dynamics     
1:50:03     
multi-agent models featuring generative agents are also important to study for their own sake so you know we can     
1:50:11     
actually approximate human cultural Dynamics using multi-agent models not always large language model but this is     
1:50:18     
actually very similar to what Sara was talking about in her review that people     
1:50:23     
are using multi-agent models uh for these Collective Behavior things and     
1:50:29     
cultural Dynamics are very much the sort of the embodiment of collective Behavior     
1:50:34     
you have these uh Collective goals that need to be achieved and you build these practices around that so you build in     
1:50:41     
this sort of set of practices that enable people to cooperate or enable them to do something um through some     
1:50:49     
sort of rituals or some set of like practices so it really does you know it does fit     
1:50:54     
into this multi-agent model framework quite well so you use a multi-agent     
1:51:00     
model featuring generative agents um indeed as artificial agents are bound to participate more and more     
1:51:07     
to the evolution of culture so these agents are you know bound to participate in the evolution of     
1:51:13     
culture it is crucial to better understand the Dynamics to machine generated cultural Evolution we have     
1:51:20     
presented a framework for simulating cultural re ution of populations of large language models allowing the     
1:51:26     
manipulation of variables known to be important in cultural Evolution and those are the following     
1:51:33     
Network structure so how the agents are interconnected how they interact some     
1:51:38     
agents will interact more than others if you're you know if you think about in culture if you're in the same research     
1:51:45     
group or you're you know you're uh alumni of the same school or you speak     
1:51:51     
the same language would you're more likely to interact than if not so there's this network structure     
1:51:57     
aspect there's the personality aspect which is where personality sort of primes the way you expresses cultural     
1:52:06     
practices uh and then the way social information is aggregated and     
1:52:11     
transformed so again you know there are different ways that this happens in different cultures the software we develop for     
1:52:18     
conducting these simulations is open source and features an intuitive user     
1:52:23     
interface and they want so they want to build this link between cultural Evolution and Generator generative AI so     
1:52:31     
they want to be able to model cultural Evolution with generative AI they want to be able to use that as a     
1:52:37     
tool so you know they kind of talk about like myths and stories and that's kind     
1:52:43     
of that you know a lot of people will think of cultural evolution in different ways there different ways to think about     
1:52:50     
it's very hard to Define culture in the first place so they're different definitions of culture but also that people will focus     
1:52:56     
on different aspects of it so in this case they're interested mythen stories and this is something of course that we     
1:53:03     
can uh deal this is something that's tractable using orang language models so     
1:53:09     
it's good so myths and stories are found in every human culture around the world     
1:53:14     
research using philogenetic methods which are these trees that we can build from a common     
1:53:20     
ancestry have revealed myths evolve in a way analogous to genes so there's this U     
1:53:27     
model that's been persistent in cultural Evolution that you know cultural you know culture basically     
1:53:34     
evolves like genes they've also have models of Gene cultural coevolution which means that culture can evolve with     
1:53:42     
genetic variation so there there's a rich history here of using phenetics in     
1:53:48     
modeling culture in different ways so in in especially in linguistics     
1:53:53     
too because language of course evolves with populations that evolve as you know     
1:54:00     
like genetic populations evolve as cultural populations and so forth um     
1:54:07     
so uh so using this biogenetic method it's revealed that myths evolve in a way     
1:54:13     
analogous to genes progressively changing as some elements are discarded and new elements are added as they're     
1:54:20     
pass through the generations so you know instead of having this model of mutation of DNA or something like that     
1:54:28     
you have this model of mutating uh a story or mutating a myth     
1:54:33     
so you know this is where you might train a model on extent stories that exist and then what happens over time is     
1:54:41     
that if those stories get told they get passed down they change they mutate and     
1:54:47     
you know we don't have like mutation isn't the same as how it is in     
1:54:53     
uh say like DNA where you have base pairs and they change in a certain order     
1:54:58     
it's just that you have you know you might take different elements of a story or of a corpus of of language and you     
1:55:04     
change the elements so you know you can think of like if I tell you a story and     
1:55:10     
you tell your friend a story and so on and so forth that story might significantly mutate across that path of     
1:55:17     
of transmission so that's what they're doing here they're looking at those mutational events in the story some of     
1:55:24     
these myths display a surprising stability being retained with minor modifications through generations so     
1:55:30     
some stories remain remarkably consistent over time some don't and so     
1:55:36     
we have to account for that variation as well and so you know maybe that's because they're very important to get     
1:55:42     
right maybe it's because they're written down versus being an oral tradition     
1:55:47     
whatever the point is is that we have this variation and we should incorporate     
1:55:52     
that into a model uh because that seems to be the way cultures work so um     
1:55:59     
moreover myths and distinct cultures seem to exhibit shared features possibly pointing to convergent evolution and so     
1:56:06     
this is the case in historic in the case of historical myths which may have been found to possess many similar elements     
1:56:13     
such as narratives featuring the collective challenges faced in the history of the group so get important to     
1:56:18     
get these kind of stories right sometimes it doesn't really matter so and so this is a thing that we could     
1:56:25     
model if that's something that we think is important and they do uh more generally providing causal     
1:56:32     
explanations to change the culture over time is a central aim of research and cultural evoltion so there are two schools of     
1:56:39     
thought here the first one is the Californian school which adopts the framework of Gene culture co-evolution     
1:56:46     
and this is uh I think this is the group out of Santa Barbara and Stanford and     
1:56:51     
they do this this stuff with Gene culture coevolution where they're looking at genes and culture and they say that you     
1:56:58     
know uh you know different populations will you know evolve and they'll break     
1:57:05     
apart and uh they may or may not transmit the same cultural values but     
1:57:10     
you can trace say again in this archaeological context sort of an ethnic     
1:57:16     
group and then a culture and sometimes the culture will track with the ethnic group sometimes it'll signific     
1:57:22     
change with respect to the ethnic group so there are different ways you can measure this Gene culture     
1:57:28     
coevolution further more you can have things like different adaptations that occur like the ability to process uh uh     
1:57:37     
lactase and so this is allows you to drink milk and so we've sometimes been able to associate changes in the genome     
1:57:46     
associated with that with cultural practices associated with certain ethnic groups and in different regions of the     
1:57:53     
world and so we can look at these kind of coevolutionary events and so this is     
1:57:59     
one approach to cultural revolution so the what they call the Californian School emphasizes how evolve     
1:58:06     
social learning mechanisms in transmission biases respectively contribute to the stability of culture     
1:58:13     
and the direction of its Evolution and so they use a very natural selection approach to this so they use very analog     
1:58:20     
everything in culture evolution is analogous to gen okay so that's the Californian school then there's a second     
1:58:27     
School referred to as the Parisian school and these people are from Paris so they're probably very familiar with     
1:58:33     
this uh so there there's the Californian school which is more about natural selection and cultural Evolution and     
1:58:41     
then there's a second school which is the Parisian school and they've adopted this framework of the cultural     
1:58:46     
attraction Theory or cat and so then this is there's a disagreement between the two schools in     
1:58:53     
terms of the central role attributed to selection so in the californ school     
1:58:59     
selection is very important in the cultural attraction theory of the Parisian School selection     
1:59:04     
is less important the The View that the Parisian view is that it emphasizes how non how     
1:59:11     
non-random transformations of cultural information during transmission events can explain how cultural trades     
1:59:18     
progressively evolve towards stable forms which are refer to as attractors so the Californian school is very much     
1:59:25     
driven by population genetics and natural selection the Parisian school is driven by sort of these dynamical     
1:59:32     
systems approaches where culture is being driven into attractor basins over     
1:59:38     
time and there's this trajectory that isn't really selected for it's just driven towards a stable state so this is     
1:59:46     
kind of their the they break this down because they want to get a sense of you     
1:59:52     
know how if you're going to model cultural Evolution with LMS what kind of approach are you going to use to sort of     
2:00:00     
instantiate that sort of evolutionary stuff so uh they're basically going to     
2:00:05     
use cultural attraction Theory and then do their study so this is a figure here     
2:00:10     
to show how these agents are organized so there's this network of Agents uh     
2:00:17     
where they have these stories that they pass between one another and then you know this is the Network so you can have     
2:00:23     
all sorts of biases and transmission you can have changes in the transmission where the story     
2:00:29     
mutates and then you know this is what you then then you can simulate this network for a while and figure out your     
2:00:36     
final State you can then Define the behavior of each agent so each agent has     
2:00:41     
an input prompt they generate a new story and that story has you know it     
2:00:47     
varies between the first generation and new generations so each a agent is going to be able to generate a new story uh     
2:00:55     
depending on its you know sort of its input prompt but also depending on its generation so you're and then of course     
2:01:02     
their neighboring stories that the larger language models might hear that they might get that information so     
2:01:09     
you're training the the model on some initial data set but also on stories that get passed between agents and then     
2:01:17     
of course the stories can vary based on how they've been mutated and then three is evolving stories     
2:01:23     
across gen several generations of Agents so this is a crucial part of this aside     
2:01:29     
from having a population of agents that those agents need to pass their stories     
2:01:34     
down to new generations of Agents so basically they're training the next generation of agent with their stories     
2:01:41     
both passing it down sort of maybe child parent uh in in a way like this or peer     
2:01:48     
toe where you know neighboring agent are able to train the next generation of     
2:01:54     
this black agent this red agent is influencing the black agent the black agent is influencing the red agent in     
2:02:00     
the Next Generation so there's this almost like this connectionist way of thinking about     
2:02:07     
transmission and then of course there's mutation and then you end up in the generation n which is the final     
2:02:13     
generation where you can observe this Cultural Revolution and how it's     
2:02:18     
uned and so they go through their study here they have this similarity Matrix     
2:02:24     
similarity graph and then they can build these kind of measures like this uh set     
2:02:30     
of word frequencies at each generation so it's interesting to see that like some words persist     
2:02:37     
across the Evol like the evolved this for 45 Generations or so and so some     
2:02:43     
words are used across all generations some words are used in early Generations     
2:02:50     
but not later generations generations and some words emerge later like after     
2:02:56     
25 or 30 Generations some words disappear and then reappear and if     
2:03:01     
you're familiar with uh some of the ways that they've measured culture Revolution and language like uh uh the stuff that     
2:03:10     
they've done with uh uh sort of engrams and modeling engram so Google has a     
2:03:18     
site uh where they kind of have these uh they they've kind of taken their     
2:03:24     
Corpus of books that they have digitized and they've broken it down into engrams     
2:03:30     
and then you can look at the frequency of words in that Corpus over time so it's like you know you have like the     
2:03:36     
word boat and you can look at how often it's been cited in literature over many     
2:03:42     
years and so that's what they're trying to do here they're trying to get a frequency of different words across     
2:03:48     
these corpuses that that are built from these large langu models and their     
2:03:53     
interactions um so it's very very interesting data here there's a lot of interesting stuff in this paper so this     
2:04:00     
is uh you know some of the stuff that they've done with culture evolution in     
2:04:05     
large language models this is this graph blown up so you have uh a lot of words     
2:04:11     
here where you know these are again you know these are built from engrams so engrams are where you take all the words     
2:04:17     
in a corpus and you break it up into like their syllables or different you know words or or fragments of different     
2:04:24     
length and then you know you kind of query those fragments as words and you     
2:04:30     
build a a frequency graph so you can do this with um you know uh actual words or     
2:04:37     
madeup words just to see what those you know because you don't necessarily know the context in which the words were used     
2:04:44     
you could use the word boat like in different contexts boat could be say for example an acronym it could be used as     
2:04:51     
like the thing we know is a boat or could be a sign term that has nothing to do with the meaning that we generally     
2:04:58     
use for it and those can have different frequencies depending on the cultural     
2:05:03     
context so this one of the drawbacks of this kind of approach is that you don't have the context here you just have the     
2:05:10     
frequency of use um this figure is the similarity graph between success of generations so     
2:05:18     
this shows that like if you have these connected agents that they're doing similar things in similar areas so you     
2:05:26     
can see not surprisingly the more connected you are to your neighbors the more similar you're to those neighbors     
2:05:32     
and they just kind of show this as a function of connectivity and again you     
2:05:38     
know you need to analyze the connectivity to understand this better but it just gives some interesting     
2:05:44     
detail as to how this transmission process works uh this is their interface so they     
2:05:51     
can actually again model this as an sort of you know by varying the parameters     
2:05:57     
you have the number of agents in your network time steps you give some seed     
2:06:02     
and then you have this initialization prompt this transformation prompt so     
2:06:07     
you're actually prompting the words uh at at initialization but you're also trans you're prompting a transformation     
2:06:15     
so it's interesting so you're you're saying that the initialization prompt is a Storyteller you add an item the     
2:06:21     
transformation prompt is where you say what kind of changes do you want to see minor changes major changes Etc the     
2:06:29     
network structure is way you visualize this graph and then you kind of give you     
2:06:34     
know this is Agent by agent breakdown of what's going on so you can actually give     
2:06:39     
the agents A personality so you can say if it's very creative not creative Etc     
2:06:45     
and so this actually allows this actually plays a role in how the mutational process works     
2:06:52     
because if you have a more creative agent they might mutate their story more than a non-creative agent and that you     
2:06:58     
know you can do this with other things like if they're very traditional versus very     
2:07:03     
non-traditional uh and so on and so forth so you can add a personality component to     
2:07:09     
this then finally there's this uh where they this is a paper where they talk     
2:07:14     
about hallucinations in multimodal large language models and the reason I bring     
2:07:20     
this up is because it in cultural Evolution you know you can have these hallucinations and you know maybe we can     
2:07:26     
understand hallucinations a little bit better in the context of cultural Evolution so I bring this paper up just     
2:07:33     
to give us some idea of what the state-of-the-art is with hallucinations with these kind of     
2:07:39     
effects where if you're mutating stories you know how often is it that you end up with     
2:07:45     
hallucinations and how often is it that you end up with stories that are basically consistent with the original     
2:07:52     
story so this is uh this survey presents a comprehensive analysis of the phenomena     
2:07:59     
of hallucination in multimodal large language models this is where they're incorporating uh visual information so     
2:08:07     
these are also known as L Vision language models so you not only have words that you're training it on or or     
2:08:14     
you know some Corpus of Lang linguistic data but you're also using Vision you know Vision like image data and things     
2:08:21     
like like that or you could also use auditory data as well so they use this     
2:08:27     
this class of model which has demonstrated significant advancements in remarkable abilities and multimodal     
2:08:33     
tasks despite these promising developments mlms often generate outputs     
2:08:39     
that are inconsistent with the visual content so as you mutate these stories     
2:08:44     
you know that's all well and good and you can track that and you can understand the sort of the cultural     
2:08:50     
significance of that but you also have these other modalities in cognition of course we not only have stories that are     
2:08:56     
told orally but we have Visual conps and so that often gives us the     
2:09:02     
context and so now we see that like often times uh large language models that are     
2:09:08     
multimodal they generate outputs that are inconsistent with that visual content so that's the way they Define     
2:09:15     
hallucination and it poses substantial obstacles to the Practical deployment of these models so so you know people are     
2:09:23     
trying to understand why this is the case it's prompting efforts to detect and mitigate such     
2:09:29     
inaccuracies so they review this field to kind of get a better understanding of how this is you know how we can     
2:09:35     
understand hallucinations and how these models behave so we review recent advances and identifying evaluating and     
2:09:43     
mitigating these hallucinations offering a detailed overview of their underlying causes     
2:09:49     
evaluation benchmarks metricks and strategies developed to address you know     
2:09:56     
hallucination um by drawing the granular classification and Landscapes of     
2:10:01     
hallucination causes evaluation benchmarks and mitigation methods this     
2:10:06     
survey aims to deepen the understanding of hallucinations in these kind of large language models and Inspire further     
2:10:13     
advancements in the field through our thorough and in-depth review we contribute to the ongoing     
2:10:20     
Dialogue on it enhancing the robustness reliability of mlms providing valuable insights and     
2:10:28     
resources researchers and practitioners alike so this is actually from their GitHub repository here where they they     
2:10:35     
call it awesome MLM hallucination so if you go here they     
2:10:41     
have this survey and this is their sort of uh I guess a     
2:10:47     
comprehensive uh categorization of different types of hallucination so you     
2:10:53     
have different types so you have hallucination causes hallucination metrics and benchmarks and hallucination     
2:11:01     
mitigation so causes being things like hallucination from data hallucination     
2:11:07     
from model hallucination from training and hallucination from inference or     
2:11:12     
prediction so this is really interesting how they break this down into different ways that you can have a model     
2:11:18     
hallucinate the different sources of error in that uh then there are these different     
2:11:24     
metrics and benchmarks so there are different types of metrics here uh depending on you     
2:11:31     
know like General metrics and then benchmarks of discriminative and generative     
2:11:36     
tasks and then we have m means to mitigate this so we can do things like     
2:11:42     
introduce negative data or counterfactual data or mitigate noises and errors in different ways we can uh     
2:11:50     
you know use Vision encoders or other types of modules to sort of mitigate     
2:11:55     
especially in multimodal models this mismatch between the Corpus of of text     
2:12:02     
and the image data uh we also have training related hallucinations which we     
2:12:09     
can mitigate with reinforcement learning auxiliary supervision of different me     
2:12:15     
methods uh and then mitigating inference related hallucinations we can do things     
2:12:20     
like inter do interventions or post talk Corrections so that's really interesting     
2:12:26     
stuff they have a uh this is a pretty good set of resources here um and then     
2:12:33     
finally uh this is this okay so this is the uh larger language models culture     
2:12:39     
repository this is actually from the first paper I believe and this kind of talks about uh you know some of the     
2:12:47     
things that they're doing in these in this first paper where they're building this population of agents and they're     
2:12:55     
introducing them to this Corpus and they're doing the mutation and all this stuff so this is uh Jeremy Perez     
2:13:03     
2m culture and you you know you can find that and and look through that     
2:13:14     
repository so yeah and then uh I think this is yeah so any comments or     
2:13:20     
questions on yes brly I was just write this in the     
2:13:26     
chat but it's quicker if I speak so how did you come across the cultural Evolution paper     
2:13:32     
because uh I was reading this paper not long ago and as I mentioned in the ethics um     
2:13:41     
channel in the slack I I've become extremely paranoid about things coming     
2:13:47     
up uh you know that I have working on elsewhere so I need to know how did you     
2:13:54     
come AC what is your path to reach that paper are you is is a machine spying on     
2:14:00     
meing data to each other is it is it by coincidence or tell me tell me any to     
2:14:07     
know oh I just probably found it on archive or like through the flowers     
2:14:13     
group blog or something like that I'm not sure you searching for I     
2:14:19     
mean you get more right isn't it difficult to know because I was specifically uh trying to write a paper     
2:14:26     
addressing cultural issues using ards which is I'm following on because     
2:14:33     
of the proposal that I'm going to write yeah and so I remember distinctively thinking I'm not interested in     
2:14:40     
hallucinations for the same reason that I'm not interested in in the pathology side of of medicine or AI but I remember     
2:14:49     
this paper very clearly and I you know I'm I'm very paranoid and so you're     
2:14:54     
you're confirming to me that there is a a matrix uh of knowledge which I am too     
2:15:02     
aware of but anyway thank you because I hadn't had the time to read it so at least you you help me looked at it now     
2:15:08     
thank you yeah so you know we' we've done we've been interested in cultural evolution in the group before we haven't     
2:15:14     
talked about it so much recently but we've done a lot of we you know participated in the cultural evolution     
2:15:21     
Society conference and so I mean this is something it's kind of a longstanding     
2:15:26     
interest in the group we've done some things like some cultural modeling and things like that so that that's actually     
2:15:31     
something we should talk about maybe more too um yeah I mean you know it's like uh     
2:15:38     
maybe I'll bring it up next week some of the work we've done on that so but yeah it's like an interest area     
2:15:45     
and I thought you know okay this be interest to the group kind of tied in with what we do and     
2:15:53     
yeah yeah I love that as well as how that kind of relates     
2:15:59     
to some of the the I mean I I think of it as the earlier agent-based modeling     
2:16:04     
work but certainly like the Joshua Epson oh yeah um like agent Z stuff where you     
2:16:11     
know yeah anyway like like um I think be     
2:16:17     
yeah Sarah's papers have been really interesting too you know things that she' been connecting that to I I I     
2:16:25     
dropped a link um to Steve Hansen um who     
2:16:30     
I think of as an old school uh um ai ai winter neural network guy who also just     
2:16:38     
happens to be a director of you know a neur Imaging Center okay um but um uh     
2:16:46     
they've got an upcoming Workshop um anyway it's called     
2:16:51     
U understanding lm's understanding oh yeah I I think I saw that online yeah     
2:16:58     
okay good good good it was on um Comp nuro List yeah yeah yeah and     
2:17:07     
um also it um yeah it looks really interesting like like I've certainly     
2:17:13     
loved his his work in the past and um well yeah now now his students are     
2:17:21     
doing cool things but uh um I also met with a um a     
2:17:28     
UI students about their neurotech club we should we should talk about that     
2:17:35     
because it was it was a good meeting and um I think he's a PhD student now uh um     
2:17:43     
but he he so he knows the club um is interested in doing more with     
2:17:49     
neurot X and and yeah just working on some cool stuff that we should talk about oh yeah definitely yeah that would     
2:17:57     
be be a bit more like Foundation models of of yeah um neuro     
2:18:04     
dat um related as oppos this llm but I I need to dig into so you'll you'll put     
2:18:10     
all these in in the the notes to the the the YouTube yeah yeah I usually put the     
2:18:16     
list of papers in there yeah I I I know I know yeah I'm gonna I'm gonna figure     
2:18:22     
out how to to scrape all this yeah yeah I wish they allowed you to do better     
2:18:28     
metadata management there but it's like yeah yeah anyway sorry I have realized     
2:18:34     
that uh that these notes are already shared and now I understand your process     
2:18:40     
Bry you take notes and you write them down and then you put them down the videos and this is why having understood     
2:18:48     
that I think maybe my docum be done I haven't seen them before although uh     
2:18:54     
there are CES that I captured that you may not have captured so it could be     
2:19:00     
scope for doing a bit more collaborative editing of this this but thank you so much for for sharing the resources     
2:19:07     
because so difficult to keep up with everything it's useful oh and again it's     
2:19:12     
past midnight and I I been thinking of logging off for Le an hour but then I     
2:19:18     
thought listen a few more minutes so thank you everybody and have a nice     
2:19:24     
weekend you too thanks for attending thank you take care bye bye     
