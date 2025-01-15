## Meeting Recording

[YouTube link](https://youtu.be/N6pVo7sId6U?si=s-AC9rpXmB4k_9aS)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113811829636089188)

## NOTES:
Sarrah: open-ended project description.

Agent-hybrid models --> imporve environment.

* how agents react to chats, rewards.

* evaluate, adding features to environment.

* integrate actions around communication aspect.


Sarrah would be a recommender, additions to LLM itself. LLM agents, RL ideas.

* Neurofedora -- project description will be coming soon. 

* hypergraph -- a couple of things to contribute.

* Ludobot community -- courses, lectures, new content is online.


Evolutionary Robotics: evolutionary algorithms. 

* Computational Psychiatry --> seeing everything in one place. Web repository, preprint.

* Nicole Rust --> do more SciComm.


January 21 --> textbook reading --> SF CogSci Reading Group.

* challenge anti-science bias.

* modeling -- readiness potential and in vitro signal for movement (intentional).

* connections between Ludobots and Dishbrain.

* POMDP --> how to make spontaneous activity --> goal-directed?

* FEP --> when does it become falsifiable? Inference, more than variational?


Ludobots --> Braitenberg connections.

* BVs --> Ludobots --> Sodaplay.

* textbook reading group, student (Computational Psychiatry).

* Ryan Smith tutorial. No one-stop place for a beginner. Terminology barrier.


Rise of RL in AI areas -- gameplay, robotic control, model-based RL and related areas.

* PyBullet vs. DART vs. ???

* Neuronal culture experiments (NeuroTech @ Berkeley + Braingeneers).

* Dishbrain 2.0 --> how would you use it? New experiments.

* spinning up RL --> educational materials and platform.


Simulation to control sensory input, RL to control agentive policies.

* dumb down ActInf, predict bias of a coin toss, losing some "Active" in the process.

* no longer (exploring environment), exploring statistical space.

## TRANSCRIPT: 
     
Transcript     
0:06     
hello where are people today     
0:14     
hi yeah yeah was a     
0:21     
with yeah it's     
0:26     
good all right and it looks like Morgan's here     
0:33     
Morgan so yeah welcome to the new year and uh so we took a break     
0:41     
uh did you know holiday things and now we're back yeah happy New Year so uh we     
0:48     
already actually started off the new year with some meetings uh this is the first Saturday morning narid meeting but     
0:54     
we had a diva wor meeting this past week on Monday the six and then we had a     
1:01     
cybernetics meeting on Thursday so let's go through our Diva     
1:08     
worm uh materials first so the first meeting is January 6th we had actually     
1:15     
uh in December the last meeting in December was Susan and she was talking     
1:21     
about her thesis materials so her thesis is uh now submitted we've been had been     
1:29     
talking about that thesis for over a year and she's she did a thesis um as     
1:36     
Master's thesis on biotensegrity for tissue morphogenesis so you know she built a     
1:43     
bunch of what we call biotensegrity models in a program called commo which     
1:49     
is a multiphysics program modeled different small models of tissue     
1:56     
morphogenesis and looked at how those motifs of cells those interactions     
2:02     
between cells is what they call Super stable or Ultra stable meaning that you     
2:08     
can uh load them with forces uh that would normally say bring     
2:14     
down uh some structure but they remain robust to those forces     
2:19     
especially um things like you know torsional forces so this is uh something     
2:27     
she's been working on for a while she put her thesis out she actually sent me the thesis to read so I'm actually going     
2:34     
through that so then this this uh returning to     
2:40     
2025 returning to our meeting schedule uh we had talked actually about     
2:46     
a paper that was related to that uh where they didn't talk about tensegrity     
2:51     
per se but they talked about epithelial cells and doing biophysical     
2:56     
modeling and then we were looking at another paper on Cell     
3:02     
asymmetry and uh protein expression particularly P protein     
3:08     
expression and how that sort of contributes to cell manages as cells     
3:14     
divide in an embryo and how that plays out at this sort of uh protein level     
3:22     
actually looking at the genes that encode the proteins and then at the cell level and looking at how that translates     
3:29     
into lineage tree so that study was done in C elans so uh yeah that's that's the     
3:36     
first meeting of the year uh I also over the holiday had uh produced a couple of     
3:41     
problem solving lectures so this is uh the first one here you know these are     
3:47     
short 15 to 20 minute sessions where I kind of draw things out on a whiteboard     
3:53     
they have to do with a lot of the concepts that we deal with in the DOR meetings so the first one is this     
4:00     
uh like it's sort of like a chalk talk where I like talk informally and sketch     
4:05     
things out on a whiteboard um the first one was about applying Game Theory to developmental     
4:12     
biology this is called game theoretic development the dorm group has published     
4:17     
a couple of papers on that in that direction so I kind of went over and summarized some of those     
4:23     
materials and then this other idea called generative Divergent integration which has to do with uh     
4:31     
embryo networks we're thinking about embryos as a network of cells that interact and how in development you get     
4:39     
this Divergence of function from say like you know stem cells or     
4:45     
developmental cells to differentiated cells that form differentiated tissues     
4:51     
that have Divergent functions but also maintain sort of a     
4:57     
common get maintained in a common system so that you know that those are some     
5:02     
pretty big ideas but I wanted to summarize those in about 20 minutes for people so those are on the dorm YouTube     
5:09     
channel as well so all this stuff can be found in the weekly meeting archive on GitHub the dorm     
5:15     
GitHub um organization so this is you know a lot of material here on our past     
5:22     
Diva meetings the link to the uh YouTube recording and then the usual create a     
5:30     
social media post for it as well okay so that's uh Diva Worm for     
5:37     
this week so we're getting a good start on that actually I wanted to also highlight that uh last year we had 44     
5:46     
meetings of Diva worm so every year you know I've kind of count the number of     
5:52     
meetings in this uh archive I think the year before in 2023 we had 43 meetings     
5:58     
so we have a lot of content there for DEA we we meet almost every week and so     
6:04     
it's I think it's worth going back and looking at some of the things that we've done in the past if you want to especially if you want to get an idea of     
6:11     
how to contribute to dorm I always get that question how do I contribute to D or I don't I contribute to open one for     
6:18     
that matter and my answer is you know maybe go back to those meetings and look and see what you     
6:25     
can find I also found this other tool and I'm not going to pull it up right now     
6:31     
but there's a tool that's out mozilla's produced a tool called orbit and it's uh basically a large     
6:39     
language model uh summarizer so what you can do is it I can't remember what large     
6:45     
language model it's built-on but you can plug it into a Firefox     
6:50     
browser and then you can uh go to say like a YouTube video and have it     
6:57     
summarize the video it summarized the video sort of in a well uh like a transcript a text     
7:07     
transcript so it basically takes the audio and summarizes it so we talked     
7:12     
about that in the past there are tools that do that that you pay for this is free and so you can just take that stub     
7:19     
and just summarize it and get a good sense of what's going on there it's not perfect and it doesn't work for every     
7:26     
piece of video and audio content on the web it just works for YouTube pretty well so I've been working kind of on     
7:34     
that as a side project thinking about how we can take some of these videos and make transcripts for them and you know     
7:41     
get at least some more information out of them uh sometimes it's hard to go through the uh you know the video and     
7:49     
kind of find what you want sometimes YouTube will uh create chapter sometimes     
7:54     
it won't so uh you know coming soon we'll have some transcripts these videos     
8:00     
so that you can read along and kind of mind those so that's     
8:07     
good and then of course we had our cybernetics meeting which was on Thursday it's the first of the     
8:13     
year uh you know we we talked about this understanding understanding book by Von     
8:20     
Forester we talked about the third chapter of that book so that was um on     
8:26     
memory because we've been talking in our cybernetics meeting about memory and memory encoding and memory     
8:33     
retrieval and it was um you know you have to wrap our heads around it a little bit but I think it was a pretty     
8:40     
interesting uh chapter so I think uh so we have our cybernetics     
8:46     
meetings every two weeks so I think in the next cybernetics meeting maybe we'll come to the you know some sort of next     
8:53     
step in that uh Direction so we might revisit that chapter 3 uh maybe talk     
8:59     
about some other chapters in that book and uh or you know kind of come uh bring     
9:05     
some other readings to the meeting and see uh you know we kind of approach the     
9:11     
cybernetics meeting sort of in a free flow way it's pretty Democratic if someone finds a good paper they want to     
9:17     
review We review that otherwise we kind of continue on a theme that we just kind     
9:23     
of follow it out to our satisfaction so uh but if you're interested in joining     
9:29     
that if you go to the orala research and education live YouTube channel you'll     
9:34     
find the cybernetics meetings or cybernetics reading group uh playlist     
9:40     
and you can go and look at some of the meetings we've had in the past we've reviewed books we've reviewed articles     
9:47     
we've talked about different topics so that's good okay     
9:56     
um so that is our meetings for this past week uh I'd also like to bring uh to our     
10:03     
attention two things we have uh I I've been kind of     
10:08     
putting together a submissions list for this new year and a list of Google     
10:14     
summer of code projects and I know we talked about Google summer of code projects and     
10:19     
how we might proceed on that for this year so we haven't met on this formally     
10:24     
um I think incf will be soliciting     
10:30     
projects soon I haven't gotten an email about it but they want to usually have them by the end of January where they     
10:36     
can post them so let's go over those so our     
10:42     
submissions list is pretty sparse right now but we're only like 11 days into the     
10:47     
new year so uh we have a number of venues that we want to Target the     
10:53     
deadline and then the event date so this first example is uh embodied     
10:59     
intelligence I just got an email about embodied intelligence 2025 this is a online conference where     
11:06     
they cover topics in embodied intelligence it's a little heavy on Soft Robotics but it's always a good venue to     
11:13     
present at some of the ideas of our agent based learning especially like the     
11:19     
things we're doing PR with vehicles or other types of things uh last year I     
11:25     
presented on developmental neuros simulation some of the work in that area     
11:30     
uh this year I'm trying to do maybe do the same thing uh the thing about this conference is it's um low cost but also     
11:38     
you know each person can submit their own submission and do a presentation so     
11:44     
we've had people do presentations in the past on various topics and embodiment     
11:50     
Jesse sometimes presents you know they're different they're they're pretty     
11:55     
Broad in terms of what they're looking for anything from like philosophy to     
12:02     
like I said Soft Robotics and anything in in cognitive     
12:08     
science you know is you with that has to do with embodiment is usually pretty accepted     
12:14     
so this is coming up uh the deadline submission deadline in March 1st for an     
12:19     
abstract and then the event is April 2nd through the 4th uh so we'll have to keep that on our     
12:26     
radar if you're interested in participating um you know kind of think for think     
12:31     
ahead and say what we need to have in place by what date uh another example is the New York     
12:40     
celebration of women in Computing this is Jess's uh Jesse's kind of driving this I don't think there's a virtual     
12:48     
component to this but Jesse always manages to do some sort of hybrid     
12:53     
component and we'll we'll see how that goes just contact Jesse if you're interested this is basically     
13:00     
um you know it's usually some sort of smorgus board of topics so I'm not really sure what he's got in mind for     
13:07     
this but uh if you're interested contact him the deadline is passed I think he's     
13:12     
already submitted a deadline or submitted a proposal for a session and     
13:18     
it's just a matter of fitting it into what he wants to do and then the event will be April 11 through     
13:25     
12th um and there's meta science 2025 this is along with the sips virtual     
13:33     
conference an opportunity to engage in like a metascience submission so I view     
13:39     
these two as linked somewhat because sips is interested in sort of     
13:45     
psychological reprodu you know for psychological experiments for reproducibility for uh you know     
13:52     
improving statistical analysis and things like that and metascience is a     
13:57     
very similar thing and the the nice thing this year is they're both sort of offering these virtual tracks where you     
14:05     
can submit work and present it virtually and that's a lowcost option to traveling     
14:10     
to the venue and presenting there uh so I was thinking of having     
14:16     
like a common submission here maybe one tailored more towards you know     
14:21     
experimental science psychological science and another one uh focused more     
14:27     
on sort of the pure meta science So Meta science topics again are things like you know uh experimental     
14:35     
reproducibility or statistical methods or you know some other type of thing     
14:40     
where you're studying the science of science so you know I don't know what we     
14:46     
want to do there I'm kind of thinking about it um the deadlines are coming up soon um in February so that means to     
14:53     
happen within the next month if we're going to do this and so let's think about that let's let's think about what     
14:59     
we want to do for that set of submissions ideally it would be something that we could pivot from one     
15:06     
to the other on so we don't have to like do a huge amount of work and um you know hopefully it works     
15:14     
out uh so that's and then the last thing here is the Google summer of code project descriptions this is a list of     
15:22     
project descriptions that I put together uh the ones I have are recycled     
15:27     
from last year but updated and so that is due soon I know that     
15:33     
um Morgan discussed you know maybe having uh a project uh focused on some     
15:42     
sort of open-source software development for I guess neurop Fedora or something     
15:48     
like that uh now that's you know that's something we should look into we all we need to do is and I'll show you how     
15:55     
these descriptions are written up prepare a description deson kind of think about what we want to have in the     
16:03     
description in terms of like you know what what's the work that needs to be done what's the problem needs to be     
16:08     
solved and then maybe some detail technical details so let's go to the list so this     
16:14     
is a list of projects this uh I think I have two on this list so yeah I have     
16:21     
daph and open source Community sustainability so these are two projects from I think these are the two projects     
16:28     
from last last year and I've updated them accordingly uh based on the work that was done last year um this first     
16:36     
one is dor graph and this is of course where we're trying to build these um you     
16:42     
know graph neural network type models and make them relevant to developmental biology so this is where     
16:51     
of course we did two things last year we built uh Pro this sort of neural     
16:57     
developmental program where you build this growing network of cells as the cells divide you get new     
17:05     
nodes in the network and they get connected based on their position but they can be connected by means of other     
17:12     
things we just need to train the neural developmental program uh you know we     
17:18     
need to train the model with data from our model system and then we can have these networks that grow and we can see     
17:24     
the Dynamics of the network and how they change their connec ity we can also     
17:30     
modify this to work on you know building connectomes versus the rest of the cells     
17:36     
in the embryo or some other growth process we might want to     
17:41     
replicate so that's one one option for people and then the other option is to     
17:47     
work with these hypergraph representations which mahul was working     
17:53     
on last year and uh we I've actually been working on updating the pre-print     
17:59     
on this over the break so we'll be having a new version of that out soon so     
18:05     
people can look at that new version and get a sense of what we're doing uh again     
18:10     
you know this is just kind of building models in different ways we have the materials in the repository I've listed     
18:19     
some of the repositories and websites they need to get started here we you     
18:24     
know have all sorts of training data for this project so that's something to point people to as as     
18:29     
well so we have this basic description here we have some background reading     
18:35     
here then we have like a skill level you know I would say this is an advanced skill level you need to have some     
18:42     
appreciation for mathematical modeling you need to understand how to work with data     
18:48     
Etc and then you know there's some required skills so usually we put in there what are the skills you really     
18:55     
need to have down you know to work on the proc project you don't want to have     
19:00     
people who don't know anything about programming obviously um I mean these     
19:06     
are pretty generic skills but still it's you know they're different skills and I     
19:12     
need to kind of go through here and make sure that I have the skills that I want     
19:17     
here usually that's that's part of it as well there's usually a time commitment     
19:23     
um there's a full-time project and a halftime project so there's like 175h hour time in 350 hour time and it's just     
19:31     
how much work does the project require I think for something like um uh neuro     
19:38     
Fedora would be like a full-time project this is a full-time project and you know     
19:43     
it just depends on what you want them to do if you want them to do some really     
19:48     
deep conceptual work along with the pro producing and programming artifact then     
19:55     
that's a full-time project if you just want people to like maintain code or to     
20:00     
produce some you know programming artifact then it's maybe halftime but it's really up to     
20:06     
you we need to have a lead Mentor maybe some backup mentors and I have I don't     
20:12     
have the project website here but that we have links up here so that's how we kind     
20:18     
of you know describe these projects to contributors to potential contributors     
20:23     
and get them in the front door so these will be posted on neurostars     
20:29     
people who might want a project will come and look at the description and ask     
20:34     
questions and this description should be good enough for them to get a decent idea of what's going     
20:40     
on and then the tech keywords are going to just kind of describe what kinds of     
20:46     
things are involved in the project so that people say oh yeah I have an interesting graph Theory or     
20:53     
computational biology I should check this project out so uh then there's open source Community     
21:00     
sustainability we know this project pretty well uh from last year this is     
21:06     
where we want to uh I need to update this even a little bit further     
21:11     
because I'm not exactly sure well I think I'm going to leave it open for people as to how they want to um really     
21:20     
approach this what I really kind of want is to take what we did last year the     
21:25     
reinforcement learning model and hybrid agent based large language model and keep working on that     
21:31     
developing pieces of that improving upon it applying it whatever so I I want     
21:39     
to I want to change this um I I really want to make this though something that     
21:47     
people can kind of make their own and put their own stamp on so the reinforcement learning models were a     
21:53     
good example of that where we had we've had like a three or four year Arc now of people doing reinforcement learning     
22:00     
models where they've kind of developed one part of it so we've had had like     
22:06     
know the basic reinforcement learning model we had the multi-agent reinforcement learning     
22:11     
model and then we've tried to expand the reinforcement learning model in different directions so that's what I'd     
22:18     
like to see kind of like improving upon or expanding one aspect of this     
22:24     
community sustainability approach and since we have the work in work in     
22:30     
repositories people can go back and add on to that repository so that's basically it I have     
22:38     
these two uh parts of our this is on the     
22:44     
uh orthogonal lab uh GitHub so we have these repository links here that guide     
22:51     
people right to the place where the code is and then um you know there's some     
22:58     
requirements here which I'm not quite sure I have all of the you know I don't     
23:03     
really have a programming language requirement here but I have basically you have to be able to integrate     
23:09     
multiple development environments extract model representations from complex systems so     
23:15     
how do I think about the problem how do I abstract it to some sort of     
23:21     
programming solution and then being able to think in an interdisciplinary Manner and that's     
23:27     
that those are basically the requirements and again the time commitment the mentors the project     
23:34     
website which we don't really have but we have the repositories and then the tech     
23:42     
keywords so that's uh the gck     
23:48     
descriptions for this year I I'm going to be updating these uh and keep working     
23:54     
on it and getting them uh ready to go and they should be     
24:00     
they'll probably ask me for them in the next two weeks so if we want to do something with neurop Fedora we can do     
24:06     
that if we want to do something else we can do that as well I'd like to build on     
24:12     
you know some of the things we've been doing with open source so in our open source meetings     
24:20     
you know we've talked about kind of developing these open source sustainability     
24:26     
models we've talked about different you know topics in open source uh we've     
24:34     
talked about research uh research software engineering we've talked about     
24:39     
some of the devor stuff I mentioned uh we've talked about other things so you know I kind of really want to build on     
24:46     
some of the things we've been doing there but maybe some of the things we've been doing later in the year with uh     
24:52     
like reprodu uh programming and and project reproducibility some of the environments     
24:59     
for that some of the tools for that and maybe even building a you know it would     
25:04     
be nice to have some sort of U interaction with other groups although we don't need to do that for     
25:12     
gon but things that facilit that SAR wants to say something yeah yeah yeah I     
25:20     
was saying uh even regarding the open sustainability projects like the one idea that you have is like keeping it     
25:25     
open-ended like it was for the past couple of years right and whatever ideas that the new people may have so they can     
25:32     
either work on the previous ones or add their new ones uh another thing that I     
25:37     
maybe wanted to add either in the same this or as a separate this was within the agent hybrid uh large language agent     
25:45     
hybrid model itself like maybe improving the environment of that itself like so     
25:52     
there were like when I worked on it there were certain things certain features that I added so maybe adding     
25:57     
like a new feature itself like one of the things that was even in my future Scope when I was doing the project was     
26:04     
trying to add like uh uh RG based approach a retrieval augmented     
26:11     
generation based approach for like how the agents would react to chats so maybe     
26:17     
if we have space either you can include that as an idea in the description of the open-ended project itself or like     
26:25     
like there is just something I want to put out like that is something that be done as an improvement on the on that     
26:31     
one so yeah what do you think about it like     
26:37     
yeah I didn't think about that uh part about the environment training environment I guess but     
26:43     
also kind of like evaluating the environment that the agents are     
26:48     
in yeah evaluating as well as like adding a completely new feature itself     
26:53     
to it like currently they work on the code part a lot right what I worked on like like we have interactions around     
27:00     
the coding of issues but then there were like there was plans to integrate     
27:06     
interactions around the communication aspect within the open source community     
27:12     
so like doing that using RG was one idea but then of course there can be other     
27:18     
ideas as well but then adding that uh whole uh like full feature to the     
27:25     
environment uh and of course yeah as you said like also evaluating the environment would also be a good one I     
27:31     
don't have any ideas right now as to how that would be possible but that would also be a good addition I guess yeah     
27:39     
yeah I think that would be good yeah so that that that's just kind of constraining people a little bit um     
27:47     
based on what we've been doing so yeah I think that's good um yeah the training     
27:52     
we've explored different ways of doing like U you know they have these AI gym environments where you train agents and     
28:00     
that's kind of a generic thing it's not like you know it's it's largely like kind of a reinforcement learning warning     
28:06     
thing but the things we were doing last summer with large language models are good too is kind of giving them     
28:12     
different scenarios or different you know places where they can acquire knowledge I mean you can train     
28:20     
them on like you know existing GitHub issues but it's like how do you get them     
28:26     
to kind of think or the agents to to kind of think in a way that's um based     
28:33     
on kind of more situational stimul yeah so that's that's     
28:38     
good um yeah I we have to think about that I guess just say you know we're kind of interested in going in the     
28:44     
direction of these kind of uh training environments or training     
28:50     
you know kind of thinking about training the agents     
28:59     
so like yeah yeah and I was also going to say like if you're interested I'll     
29:05     
also be interested in being like a mentor for that project itself for the open source Community sustainability one     
29:11     
all right that was possible yeah yeah what what what were you thinking about     
29:17     
uh uh so yeah so either if there is any addition to the uh to the large language     
29:23     
model itself like as I said like one of the things that like I think could be project on its own would be like adding     
29:30     
to that same framework uh or then also like extending on it like if anybody has ideas like I     
29:37     
when I joined I had the whole idea of the llm agents so I'm sure like there will be some new ideas this year as well     
29:45     
so even those on the entire open source Community sustainability part and then     
29:50     
of course because of the previous RL work there will be RL ideas as well um     
29:55     
I've not like exactly worked in in RL but I do have like a general idea of it     
30:01     
so even even those projects I think I could like Mentor as     
30:07     
well uh because like I have a general idea of the open source uh the the     
30:13     
environment that we supposed to be working in at least so and yeah I think if sham is     
30:20     
there from last year for the rl1 that would be even better but like if there     
30:26     
is like no one there right now then I could definitely like take up mentoring on that as well okay sounds good um yeah     
30:35     
I'm I'm looking yeah I'd be welcome I'd welcome your assistance and help on the     
30:41     
um in any way you have time for and you know I guess it'll come become clear once we get some people     
30:49     
applying and and and get a sense of where we're going with that project so     
30:55     
yeah yeah and like I've also been trying to do     
31:01     
some of my own work on it as well but like I'll I'll update you all once I actually get something done that's been     
31:06     
a bit difficult uh right now but yeah once I do have time to get something I'll hopefully give an update in one of     
31:13     
these meetings as well okay it sounds good thank     
31:19     
you so our timeline on this is you know kind of uh towards well the selections     
31:26     
are made in early May so that's usually when we start up our um open source meetings again now we'll     
31:33     
probably start them up a little bit earlier because we want to have interactions with people um before that and of course we     
31:42     
have other open source activities and Morgan and I've been talking about some     
31:47     
open source activities um outside of our traditional Google summer code stream     
31:54     
but so I mean you know we we'll start those meetings up when it makes sense but looks like Morgan has some things to     
32:04     
add I've got the FL oh     
32:16     
okay oh I haven't gotten got back to you     
32:22     
about that over the over the break it's okay yeah um yeah it's     
32:28     
uh you know the holidays were great but uh the problem with travel     
32:34     
is it's also time for us all you know some good     
32:40     
computational modeling of viral infections and things like that     
32:48     
yeah anyway just just wanted to say why I'm     
32:53     
being being quiet oh it's okay and yeah well well absolutely follow up with     
33:00     
you on these things but I'm here and I'll try and Chim in from time to time I just just     
33:09     
got the dog and fruit and we'll try and wake up a little bit     
33:15     
before the end here okay well I hope you're feeling better soon yeah I know     
33:20     
it's like this is the time of year right it is it is yeah yeah yeah um you know     
33:29     
hopefully hopefully I can be ready for next week right yeah yeah listen listening in     
33:37     
and uh I I did have a couple hypergraph um     
33:44     
uh updates or things things to contribute to but yeah just not quite     
33:50     
there yet this morning okay well let me know yeah okay okay something that kind     
33:58     
of C I guess it came up in the slack uh something that I I think I also     
34:03     
saw on social media but I wanted to go through it and kind of show what this     
34:10     
was it's very interesting um so it's this idea of what     
34:15     
they call ludab bots so I think Jesse posted on this in the um and the slack     
34:23     
and then I saw independently and it's this uh sort of     
34:28     
application of embodied intelligence embodied robotics     
34:35     
where there's sort of building the infrastructure so that people can design their own um embodied robots     
34:44     
embodied um systems where you know this agent has a body and you know you can     
34:51     
evolve it in different ways so this is an article from December 2013     
34:58     
it says beware scientists are creating machines that can evolve on their own or to put it a nicer way researchers have     
35:05     
found a way for robots to grow on there and so this whole work is about     
35:11     
basically uh using something like an evolutionary algorithm or an evolutionary program to evolve robot     
35:19     
bodies that match a certain environment that you can put them in a environment     
35:24     
where you can you know give different sort of Fitness functions depending on what     
35:31     
you're interested in and evolve the shapes of these robots and then you know     
35:36     
you might be able to 3D print the body or you might be able to you know run     
35:41     
this body in a 3D simulator and see how it behaves in a     
35:47     
simple physics environment so that's the idea and this is a project that spearheaded by Josh bongard those builds     
35:53     
upon Josh bongard work in embodied robotics in in what he calls     
35:58     
morphological computation so you can see the robot bodies here they have legs     
36:04     
they have these panels and then they're configured in different ways by say like a hinge or by some other     
36:12     
connector and that's really the key here is to develop these modules of body     
36:17     
parts and configure them in a certain way so that is to give the robot a     
36:23     
certain Fitness for its environment and you know that Fitness can be assessed in different ways but     
36:29     
basically it's uh more or less the physics of the environment but also it can be like something it's Performance     
36:36     
Based like you know how often it's able to acquire food or how fast it's able to     
36:43     
run so uh this is kind of this approach this Evo Divo Robo approach which is     
36:50     
evolutionary developmental robotics which applies principles of natural selection and biological     
36:56     
development to machine design um and then he's trying to design     
37:02     
these robots that go through growth Spirits like anxious teenagers they experience an awkward period of physical     
37:08     
development before they find their place in the world so in the simulations     
37:13     
you'll usually put it in say like a physics engine and then you'll try to try out different shapes try to change     
37:20     
the size of the phenotype the size of the different components and given a controller that     
37:27     
is I guess static you can evolve a a body and you have to kind of De it's     
37:33     
more of kind of developing the body but because you're using an evolutionary algorithm you're also evolving the body     
37:39     
hence evoo and then the robo is like because it's a robot okay so um basically you start     
37:48     
with this limbless wormlike machine with several body segments the body segments are these components of the phenotype     
37:55     
that change independently and then kind of in a coordinated fashion and then you     
38:00     
try to build this phenotype that can do something that has a fitness imperative     
38:06     
so in this case you have this lless warlike machine with several body     
38:11     
segments that's your starting condition then that starting condition has one goal so it has some sort of goal     
38:18     
directed Behavior which is to make progress across the flat surface towards     
38:23     
the light source so that that goal is fixed across the uh     
38:29     
generations of the uh evolutionary program and so you're able to evolve a     
38:36     
solution to that single task so it's it's a very sort of static Fitness     
38:43     
imperative it's a very static sort of environment so it doesn't fluctuate you     
38:49     
just want to be able to create a morphology that can complete the task of     
38:54     
moving towards this goal that's that's pretty much it but of course but instead of giving a     
39:00     
robot a complete set of instructions bongar generates a whole population of bots and let's Evolution     
39:06     
do the work so you basically have this population of robots that have different     
39:12     
um you know has some variation within the population you introduce mutation     
39:18     
recombination of the representation of that morphology so you introduce a     
39:24     
variation so you might have uh a a robot with three segments you have a     
39:30     
robot with five segments you might start to have robots with limbs you might have     
39:36     
one limb you might have eight limbs and the more mutation you     
39:41     
introduce the more Rec combination you introduce the more variation you introduce the more likely it is you'll     
39:49     
find some unique solution or maybe multiple unique solutions to this     
39:55     
Fitness imperative so you have a population of Agents it could be a 100     
40:01     
agents it could be a thousand agents those agents re produce and then those uh phenotypes are     
40:10     
evaluated and the ones that perform the best get preference in the Next Generation and you keep moving like that     
40:17     
until you converge upon the best Solutions and the advantage of doing     
40:22     
this with an evolutionary algorithm is that the end point is some somewhat unpredictable in other words you know     
40:29     
you might be able to predict say maybe the best you might be able to say do this in a prospective fashion and     
40:37     
say I could tell you what the best solution to this problem is like most Engineers you could just kind of     
40:42     
engineer a solution and say if I want to move towards a light source and a flat     
40:48     
surface this is the design that you need to have but the thing about evolutionary algorithms is you can actually find     
40:55     
unique solutions to this that don't look anything like the prospective or engineered     
41:01     
solution and that's good because sometimes those designs tend to be more     
41:08     
robust if you modify the fitness imperative some so if you say okay we no     
41:15     
longer want the robot to crawl across the flat surface towards the light source we want the robot to crawl along     
41:22     
an undulated surface or a hilly surface towards the light source maybe we tilt the flat surface     
41:28     
45° meaning that you need to have extra sort of uh you know the robot controller     
41:35     
needs to be able to grip the surface more tightly it needs to have stronger muscles or whatever and so that that may     
41:43     
result in a you know a solution that is maybe over optimized for a flat surface     
41:50     
but works perfectly well on this new in Incline surface or you might have you     
41:56     
know variation in the in the fitness imperative that's captured well in this     
42:02     
evolved solution so there you know this is this is why we use or want to use     
42:07     
evolutionary algorithms for this so this is kind of talking about uh     
42:14     
some of Banger's previous work he's found that he can evolve a contraption that walks upright in just a 100     
42:20     
Generations so you know there is a criticism of uh genetic algorithms or     
42:26     
evolutionary algorithms that is that it takes a very long time to evolve Solutions so why     
42:33     
don't you just do this prospective engineering and the answer is first of all it doesn't necessarily take a long     
42:39     
time to evolve good Solutions or good enough Solutions but also that like what I said     
42:47     
you know you might you can evolve solutions that you wouldn't get by just kind of prospective     
42:53     
engineering and so you know this is a nice uh approach it you know may take longer it     
43:00     
may not but it gives you a good answer so this is this is one of the advantages of doing this type of work so um bongard     
43:10     
has found that he can evolve a contraption that walks upright in just 100 Generations by contrast the     
43:15     
contraption that starts with legs already formed takes 250 Generations it     
43:21     
makes sense to stay close to the ground when you're young and only gradually grow legs and stand upright which makes     
43:26     
you more unstable so you can actually not only get this uh solution with respect to the fitness imperative but     
43:34     
you can also have this sort of Developmental trajectory that you can see you know as you kind of evolve the     
43:42     
task or as the solution evolves from the ground state that we talked about from     
43:47     
the sort of the common ancestry that we talked about and then you know you can     
43:52     
see these sort of solutions evolve across the generations you know you     
43:58     
might start with some you know legs that are short and then the legs as the     
44:04     
solution evolves grow longer and other parts of the body are modified so you can actually with this evolutionary     
44:11     
trajectory get a sense of what maybe you would see in a developmental trajectory     
44:17     
so there is a bit of like conflation here between development and evolution because you're evolving this thing     
44:23     
actively but basically that's there they're I think they're getting some really interesting insights in work like     
44:30     
this and this is why I'm kind of highlighting one reason why I'm highlighting this because I think it's     
44:37     
you know it's a nice method for looking at some of these problems in the development and evolution of behavior     
44:43     
but also in morphologies and the sort of embodied     
44:49     
cognition okay so um you can also 3D print these robots we saw that like they     
44:55     
have these morphologies that are um you know have have different     
45:01     
shapes that are configured in different ways you can 3D print these put a little     
45:07     
robotic controller Within These morphologies and have a nice robot that     
45:12     
has you know something that you couldn't necessarily engineer prospectively but     
45:18     
you get these designs and you can test them out in the real world though uh another Point here and this is     
45:24     
important for what I want to talk about later here um and this this story is from 2013 so     
45:30     
starting in 2013 he made these experiments available online he has this     
45:36     
platform he call ludot so the ludot platform is basically Ludo is the Latin     
45:41     
for play and the idea is that you can play with these designs you can play     
45:47     
with the parameters and an evolutionary algorithm and you can get your own designs that you can then use for     
45:53     
whatever you want so the idea is not so much to help people design things     
45:59     
prospectively but to let them play with the designs to see you know given this     
46:05     
framework what can we produce and because evolutionary uh programs are     
46:12     
generative if you play around with the parameters you can get a a variety of different solutions and then evaluate     
46:18     
those maybe in the real world or in a simulation so there's a u a Reddit     
46:27     
Channel or sub Channel called lud rudots and this is this uh I guess this     
46:35     
is a subchannel uh diff design or diff Lut Bots differential design of robots     
46:41     
and so this is some documentation for the lud Bots approach and this is where     
46:47     
you know they kind of go through the different components of your lobot you     
46:52     
have objects you have Springs Motors control optimization than in final     
46:59     
project design so there are these different tutorials you can follow along if they have listed uh the tutorials are     
47:05     
all available in um you know interactive notebooks so you can Fork those and you     
47:12     
you know play around with the parameters play around with the outputs and see what happens um this is     
47:21     
part of a course that Josh created called education and evolutionary robotics so this is is you know part of     
47:27     
an educational imperative as well it's not just about design and about teaching     
47:33     
people how maybe you know how to evolve a phenotype and then teaching people about     
47:40     
the interaction of physics and evolutionary representations this is     
47:46     
about like you know sort of doing this on your own so there's this strong     
47:52     
educational component the strong sort of DIY component     
47:57     
so Jesse actually I think has four guto Bots um on his GitHub so you know he has     
48:04     
this kind of uh marked and um you know I kind of     
48:11     
wanted him to be here could maybe talk about it a little bit but um that's okay I think we could I know now that he's     
48:17     
interested in this so we might actually pursue this later as sort of a side     
48:22     
project or something that fits into our educational Mission because I think the the materials are already there we     
48:29     
can much more easily do things with it this is uh the diff bespoke Morpho     
48:38     
repository so this is where you have this repository where we have a a mass     
48:45     
body or mass spring body model and we have an interactive notebook that allows us to run through this uh sort of uh     
48:54     
model and build like a mass what they call Mass spring model so there's this     
49:00     
history of mass spring models being animated online so um there was a     
49:05     
project about 20 25 years ago called soda play and this used to be a Java uh     
49:13     
Java applet that you could run in your browser you could you know design these little Mass spring models which means     
49:19     
that you have these little uh masses that you would put on you know put in     
49:25     
space and then you connect them with spring Springs so you have these little like skeletal structures and then you     
49:32     
know youd build you know you could build as complex as you wanted and then you turn on a physics engine where these     
49:38     
massing models would exist in a physics engine you could play with the perimeters of the physics engine and you     
49:43     
know you maybe move it you pick it up and you drop it on the ground in the physics simulator and then the thing     
49:51     
would move around and it would have different Dynamics sometimes you could get them to walk     
49:57     
sometimes you could get them to just kind of bounce around and you know it's just really     
50:02     
fascinating stuff um a lot of that work goes back even     
50:08     
further to passive Dynamic walker uh research and that started was     
50:15     
started by Tad mcgear who's a mechanical engineer and they actually were able to build these robots that could sort of if     
50:22     
you put some input energy in they could prod reproduce bipedal motion by petal     
50:28     
walking and so you know you can take mechanical systems without a brain you     
50:34     
can put some initial energy into them and they can move in a way that is looks like it's controlled by a nervous system     
50:42     
but it's actually not controlled by a nervous system it's just controlled by the interactions between the form the     
50:48     
geometry of the form and the physics so this this uh this repo has     
50:56     
some Mass spring body simulations in it and some of the things that you need to run     
51:03     
those um this is actually the     
51:08     
uh the collab notebook now you can run this notebook and produce a movie which     
51:13     
I'll show you in a minute I'm not crazy about it like it's it seems like you're     
51:19     
putting a lot of these passing a lot of these things in and out of a black box because what you're doing is you're     
51:24     
cloning this be spoke morph over atory and you're putting in you know     
51:29     
some parameter values and I can't really follow from     
51:35     
this code exactly what's happening with the mass spring     
51:40     
simulation but you can basically set it up so that you can export this is the     
51:45     
reason this uh notebook exists is because this is part of just building a bot and putting a video together to show     
51:53     
you the outcome so this is more of an educational thing so that is like passing parameter values into a black     
51:59     
box and there's probably some lower level code that we can visit revisit I'm not going to do that here but what you     
52:07     
end up with from this notebook is this video so basically outputs this     
52:13     
video where you have these Mass spring models you see the masses here the     
52:18     
Springs linking them and it's in this physics simulator where this is the floor here this black     
52:25     
bar and it's kind of bouncing up against the wall so it's you know you're moving it     
52:32     
it's kind of reacting to barriers reacting to the physics if you make the     
52:38     
gravity really strong you can get these things to collapse if you make the gravity really light you can get these     
52:44     
things to float and but you can see that they kind of they're reactive in a lot of ways so     
52:51     
they have this motion that looks like it's controlled Maybe by a nervous system but there's no nervous system     
52:57     
it's just Springs and masses and so the idea is that you know     
53:02     
everyone can kind of produce their own I guess they're um you know this is just     
53:08     
kind of a demo to show what these look like and you know everyone can kind of     
53:13     
produce their own version of this and um you know it's it's     
53:20     
educational at the very least uh this is uh from the     
53:25     
communication the ACM this is this article by Josh bongard evolutionary robotics where he kind of     
53:32     
talks advocates for this approach and so he talks about um how to     
53:38     
design construct and deploy autonomous and adaptive machines and so people have been trying     
53:45     
to approach this for years and using this prospective engineering approach sorry could what's what's the art he's     
53:51     
got many articles which this is from ACM yes this is from ACM uh uh     
53:57     
from uh August of 2013 so this is all kind of from oh okay a 10 years ago yeah     
54:04     
um but this is you know can he's been doing this for quite a while so yeah and then we have uh     
54:13     
industrial robots are an example of autonomous at non-adaptive machines they     
54:19     
execute the same sequence of actions repeatedly conversely unmanned drones     
54:24     
are an example of adaptive yet non autonomous machines they exhibit the Adaptive capabilities of their remote     
54:30     
human operators but they're not autonomous so they have they're controlled by another     
54:36     
agent that is you know can adapt to different conditions but you know you     
54:42     
can't you have to have a human in the loop to date the only Force known to be capable of producing fully autonomous as     
54:50     
well as adaptive machines as biological evolution then we talk about like how we     
54:57     
can use these population-based metah eristics evolutionary algorithms to optimize sumar all aspects of an     
55:03     
autonomous robot use of metah heuristic sets the subfield of Robotics apart in the     
55:09     
mainstream of Robotics research in which machine learning algorithms are used to optimize the control policy which is     
55:16     
defined as some function that transforms a robot sensor signal the command sent to its Motors so the idea that you know     
55:24     
you want to be able to optimize how how it's um moving you know how it's taking     
55:30     
the sensor signals and creating a set of motor commands and that is uh you know     
55:37     
kind of the the goal of this um as another branches of computer science the     
55:43     
use of a metah heuristic algorithm is a cost and a benefit the cost is it's not possible to guarantee if or when an     
55:49     
optimal control policy will be found for a given robot the benefit is that few     
55:55     
assumptions must be made about the problem evolutionary algorithms can prove both the parameters     
56:02     
and the architecture of the robots control policy and even the shape of the robot itself so we're talking about sort     
56:10     
of uh the goal that we want to achieve in the control policy that control     
56:15     
policy could be in the form of a say a gural network or some controller but     
56:21     
it's also in the form of this morphology so the morph ology can     
56:27     
constrain the behavior generated by the controller or it can benefit that     
56:34     
behavior of the controller depending on how adapted it is to its environment so     
56:40     
that's basically and so they're approaching this from a fundamentally different way than traditional sort of     
56:48     
artificial intelligence ruen robotics which means that they're considering explicitly the design or the sort of the     
56:55     
form of the phenotype that is involved in Behaving so if you need to move towards a light     
57:02     
source you have to consider the types of locomotion you may need to use to do     
57:07     
that some types of locomotion are better than others conversely you can't just plug a controller into any generic     
57:15     
morphology you have to use a specific morphology that is kind of coupled to     
57:21     
this control policy that you're using for the behavior so there may be solutions that     
57:26     
are very unique in terms of the phenotype uh or the shape of the robot     
57:32     
that have a correspondingly really interesting and maybe nonoptimized for     
57:38     
anything else behavioral modsy so that's kind of where we're going with this so to illustrate the     
57:45     
distinction between mainstream and evolutionary robotics consider two experiments drawn from two Fields so you     
57:52     
have leg Locomotion which is optimizing control policy that allows for a two or a six     
57:59     
leg robot to move over ruged terrain this is a popular area of study of     
58:04     
Robotics so this is where we want to sort of contr you have a a sort of a     
58:10     
fixed or a fixed set of phenotypes and then optimize the control policy for     
58:15     
those phenotypes uh in mainstream robotics machine learning algorithms can now     
58:21     
optimize walking behavior for a physical two-legged robot in a matter of minute so this this is not a this is a trivial     
58:27     
problem if you have sort of a fixed uh morphology but of course it also     
58:35     
requires uh very little variation in the environment so if you're you know     
58:41     
wanting your two-legged robot to move over a Terrain you can do that you can program a     
58:47     
controller if there's some variation in that task for some reason um if you     
58:53     
switch to a smooth terrain or an incline or something else then it's a little bit     
58:58     
harder to for that program to work correctly but anyways that's that's the approach use a mainstream     
59:05     
robotics alternatively a recent investigation in simulation has shown if     
59:10     
robots are evolved to move over a rough terrain robots will eventually evolve from amorphous shapes into robots     
59:18     
exhibiting the rudiments of appendages so this is where they're simulating these robots in in this in     
59:26     
environment that these environments that um Josh bongard has been working on if     
59:32     
you have robots that are evolved to move over R terrain if they have these adaptations these specializations for     
59:39     
this type of environment robots will eventually evolve from amorphous shapes into robots exhibiting the rudiments of     
59:46     
appendages so the appendages are sort of uh giving it this extra Fitness so not     
59:55     
just having things like blobs or sets of boxes but to have appendages that can     
1:00:02     
actually sort of dig into the terrain and you know move independently semi-independently of the body so this     
1:00:10     
is um you know this is kind of showing the power of doing these kind of uh     
1:00:17     
experiments and so you know this is a figure that shows a sampling of Representative work in evolutionary     
1:00:24     
robotics so this is where you have different ways of approaching evolutionary robotics this article is     
1:00:31     
intended to be like a review of evolutionary robotics really laying out the practical imperative of the field     
1:00:40     
so that what I talked about was the sort of the practical imperative this is sort     
1:00:46     
of the ways in which people have approached this and build and you notice that these models are     
1:00:52     
pretty um pretty simplistic they robots     
1:00:57     
they don't look too much like animals say I mean this soft robot kind of does     
1:01:02     
it looks like some sort of worm but other otherwise you know they're very     
1:01:08     
much they look like robots so but in any case you this is I guess a good starting     
1:01:14     
point but there are different ways that you can generate you know robotic morphologies and tie those to control     
1:01:20     
strategies and so forth so evolutionary robotics often involves optimizing in     
1:01:26     
not only the controller of a robot but also its body plan formal grammars uh     
1:01:32     
this is this a example from Hornby and Pollock and algorithms that simulate     
1:01:37     
development which is this B from urbach and vard have been used to optimize robots     
1:01:43     
and simulation so this is where we have a like a formal grammar that we use to     
1:01:50     
construct a robot so robot morphology is a product of a     
1:01:56     
grammar and sort of composing that grammar in different ways so each part     
1:02:03     
each part of the morphology is attached to sort of a set of grammatical rules and you build it that     
1:02:10     
way um or you can use a a sort of a developmental approach which I described     
1:02:15     
earlier where you know it's a different type of way of approaching the problem     
1:02:21     
you still have this sort of compositional aspect but it's fundamentally different way to do approach the     
1:02:27     
problem you can both use both of these however to optimize robots and     
1:02:33     
simulation additive manufacturing has been employed to build physical versions of evolve simulated robots semi     
1:02:40     
automatically and that's examples from C and D these are these two examples this     
1:02:45     
is the Golem project this is by Lipson and poock and showing how they've done     
1:02:50     
this so they basically did this additive manufacturing and and uh yeah once     
1:02:57     
deployed as physical machines evolutionary algorithms have been used to allow damaged robots to recover from     
1:03:03     
injury that's the example in E so basically you can use evolutionary     
1:03:10     
algorithms to fix a damaged robot or to sort of infer the way to repair it uh     
1:03:17     
that's that was from this uh bongard at all article here um as well as ease the     
1:03:24     
transfer all newly evolved controllers from simulation to the physical robot that say F here so you can do all sorts     
1:03:32     
you can do test transference or functional transference you can do a repair you can do all these things that     
1:03:39     
you know we think of may be associate with natural intelligence or life and     
1:03:46     
you know again the the metaphor is stretched here but that's where they're kind of going with this and then of     
1:03:52     
course you know in the case of a robot you have very practic imperatives for these things you want to be able to fix     
1:03:58     
things in real time you want to be able to uh trans you know tat do transfer of     
1:04:03     
learning test transfer across contexts and so all these things are very important to the Practical concerns of     
1:04:12     
Robotics in addition to Locomotion researchers have evolved more cognitively demanding behaviors such as     
1:04:19     
discriminating between differently shaped objects objects by manipulating them which is shown in G where they have     
1:04:26     
this hand that's controlling the basketball or physically demanding tasks like aerial swarming which is     
1:04:33     
H uh behaviors have also been involved for robots with non-traditional body plans such as T segr robots this is a     
1:04:41     
tense secrity structure this is going back to the stuff that Susan uh is doing in Diva worm where she's thinking about     
1:04:49     
these kind of tensegrity structures which is these Ultra stable structures     
1:04:54     
and you can use them now you use them for wide variety of things actually tensegrity originated     
1:05:00     
in architecture and you can use them to design robots that are Ultra stable so     
1:05:07     
you if you load one end with forces or you load a number of ends of forces this     
1:05:13     
structure exists in Dynamic tension so it can experience a wider range of forces than uh some other structure that     
1:05:21     
isn't a tensity structure so U without getting into the tech techical details     
1:05:26     
of this suffice it to say that you know these are really desirable for building robots we can also use it to explain     
1:05:34     
like large scale structures in in cell biology and development so that's why     
1:05:40     
this is a really interesting sort of Direction and it's interesting that we can evolve these kind of tensegrity     
1:05:47     
structures um in in particular tensity robots so these 10 segurity robots     
1:05:53     
actually have behaviors associated with them so the structure is behaving in the world it's not just experiencing loads     
1:06:01     
it's actually moving and doing things which is really interesting from     
1:06:06     
the standpoint of how're doing things in you know in biology how we build these     
1:06:12     
Tegrity structures that are maybe kind of static and then thinking about how say cells migrate together and and     
1:06:20     
maintain these tens secrity structures um so 10 segurity robots soft     
1:06:28     
robots which is J so uh John rifle has built these soft robots that are you     
1:06:34     
know programmable uh really interesting area of research these look more like     
1:06:40     
animals like I said so maybe one of the goals of evolutionary robotics is to get close to replicating some simple animal     
1:06:49     
orology but simple animal behaviors uh modular robots and robot     
1:06:55     
swarm so modular robots are these here where you have just different components that are sort of coordinated and then     
1:07:02     
robot swms here where you have different robots that are     
1:07:07     
coord so that's kind of the imperative of um of evolutionary     
1:07:15     
robotics uh a couple I think there's another set of words here in t segurity     
1:07:20     
structures so um advances in Material Science however have made nonr traditional robot body plans possible as     
1:07:28     
one example the evolution of behaviors for 10 segurity robots was reported in     
1:07:33     
Paul and that's reference 26 tensegrity structures are collections of rigid and     
1:07:39     
elastic links attached in particular way that provides several advantages over     
1:07:44     
traditional robots such as the ability to automatically revert to their default form if perturbed so they can     
1:07:52     
recover from these uh per ation that might be very     
1:07:59     
um disastrous otherwise so um yeah a lot     
1:08:04     
to think about there in that area um     
1:08:10     
so yeah and then there are a lot of things going on here with respect to morphological computation information     
1:08:18     
Theory and dynamical systems theory so     
1:08:23     
this kind of lends us to some of the topics in um embodied cognition and     
1:08:30     
embodied intelligence as as usual there usual     
1:08:36     
challenges here um and this statement here one goal in     
1:08:42     
evolutionary robotics in particular and in the field of evolutionary computation more generally is to create increasingly     
1:08:49     
evolvable algorithms and by evolvable it just simply means how many     
1:08:55     
how much variety can you produce from these you know from a single algorithm how expressive is that algorithm with     
1:09:02     
respect to the range of phenotypes that you can achieve so if you can if you     
1:09:08     
build a evolutionary algorithm that has very little Express     
1:09:13     
expressivity um that means that you're not really going to be able to take advantage of the generative nature of     
1:09:19     
evolutionary algorithms or the combinatorial nature of the algorithms so you know putting them in different     
1:09:27     
environments uh evolving them for many generations doesn't really get you anym so you have to make sure that you can     
1:09:34     
have these evolvable algorithms and create increasingly evolvable algorithms to help you to kind of come up with     
1:09:40     
these unique solutions that you want um yeah so this is uh this is another     
1:09:48     
Point here one goal in evolutionary robotics in particular in the field of evolutionary computation in general is     
1:09:55     
to create increasingly evolvable algorithms rather than independently optimizing the individual parameters of     
1:10:02     
a candidate solution such algorithm should rapidly discover useful aggregate     
1:10:07     
patterns in canidate Solutions and subsequently elaborate them it has been     
1:10:13     
shown for example the Gen genomes that encode formal grammars produce robots of     
1:10:18     
regular structure and that such genomes are more evolvable than genomes that do     
1:10:23     
not produce regular structure so that means that if you have a     
1:10:28     
representation of the problem and in genetic algorithms we usually incode this in terms of binary strings and     
1:10:36     
those binary strings are combined together in a genome if we structure those     
1:10:42     
representations in a certain way which have this sort of grammatical     
1:10:48     
structure you know we're able to sort of make our algorithm maybe more     
1:10:55     
expressive or more evolable than if we didn't do that so you know there's a     
1:11:00     
problem of representing things in this uh form of a artificial genome or     
1:11:06     
artificial chromosome but also the problem of structuring this representation in a way that can then be     
1:11:13     
expressed formal grammars are sort of the way to go there so there are a lot of different ways we can improve our     
1:11:22     
representation improve how you know we're Fitness function improves some of     
1:11:27     
the aspects of this approach um so yeah there are a lot of interesting references     
1:11:34     
here um and a lot of them have to do with sort of this so this one here 26     
1:11:42     
designing control Tegrity robots for Locomotion that's G an interesting     
1:11:47     
article here's this book uh Fifer and bongard which we've talked about before how the body shapes the way we     
1:11:53     
think um there are a number of other articles     
1:11:59     
on information Theory and software robots as     
1:12:05     
well love the community that he's got there yeah I've watched it over the     
1:12:11     
years yeah it's a it's great     
1:12:20     
yeah the ACM article you were sharing that was the diff FL the what s yeah     
1:12:27     
yeah oh which one is that the oh no no you had an ACM article oh I don't think     
1:12:34     
I have the link for that but that's that article is um let me see if I can get     
1:12:40     
the information yeah so that's the uh in     
1:12:46     
the uh August 2013 issue ACM I wasn't yeah I mean like you said     
1:12:54     
it's it's it's already you know I mean it's very much he he has all his     
1:13:00     
evolutionary robotics course um courses and you know lectures     
1:13:05     
and materials online you know like uh you can tell when he starts a new     
1:13:11     
semester because he's like it's online immediately yeah and uh um it's it's absolutely     
1:13:20     
ready to go educationally you know yeah um     
1:13:27     
uh anyway SC stuff     
1:13:33     
yeah all right go ahead yeah like when you were explaining about the evolutionary     
1:13:39     
robotics on it reminded me a lot of like how genetic algorithms also work yeah     
1:13:44     
and like I I think like genetic algorithms are like a subass of evolutionary algorithms itself yeah so     
1:13:53     
yeah that was interesting so I looking to like read up on that so I think I'll just what was the name that Morgan     
1:13:59     
mentioned who works on it oh this is uh Josh bongard and of course there other     
1:14:06     
people who do things on this yeah yeah but but but Josh has like     
1:14:13     
uh all his cours like like his lectures come out almost immediately on YouTube     
1:14:21     
when he starts a new semester um which is which is     
1:14:26     
awesome yeah God yeah thank you you're     
1:14:33     
welcome yeah so that's great uh we uh yeah speaking of     
1:14:39     
our sort of putting things on YouTube uh you know Morgan's put a lot of things     
1:14:46     
from YouTube in our slack channels and so if you're interested in looking at different lectures and things like that     
1:14:54     
um you know we always always have stuff kind of in our slack channels that are um you know kind of things that from     
1:15:02     
different conferences there's a lot of content on YouTube if you're interested     
1:15:07     
in any topic uh from an academic standpoint we can always find some real interesting stuff conferences are always     
1:15:14     
putting things on YouTube now we of course with slack we've got this limitation of like the thre Monon window     
1:15:22     
where things get kind of disappear on us I've been trying to make backups of that     
1:15:27     
and I've been also offloading things to our different um Discord     
1:15:33     
servers so I'm going to try to make more of a point in the new year to review those things and make sure that we have     
1:15:40     
you know we we know kind of where these things are so they don't get lost um so     
1:15:45     
that's um and then of course you know synthesizing a lot of that stuff so like     
1:15:51     
at the last meeting of the year last Saturday morning neuros Sim I talked a     
1:15:56     
little bit about computational Psychiatry and kind of developing a     
1:16:02     
overview of what we've been putting in the channels so that I I still want to     
1:16:07     
move that forward this year and I don't know what what we might do with that if we might do like a review article or     
1:16:14     
like you know I don't know maybe it's better served as like a interactive survey where you can say these are the     
1:16:21     
topics that are interesting in Evolution or in um computational     
1:16:28     
Psychiatry here are some links you know having this in a more formal setting uh like a like a web repository     
1:16:36     
or something maybe having a short paper accompanying it like a preprint I I     
1:16:41     
don't know how we would do that but that's something we should try to do because it's like you know we have these     
1:16:48     
interesting conversations about this stuff and I want to see if we can maybe make it into like an more of an     
1:16:54     
educational community oh that's that's great yeah I mean I I     
1:16:59     
just uh just had a conversation like a week ago with a you know upcoming     
1:17:05     
student and you know covered a lot of this conversational psychi psychiatric     
1:17:11     
like material and you know and he felt that it was all very new all very you     
1:17:17     
know like like seeing it all together in one place was was really helpful and um     
1:17:25     
makes me think that that maybe there is kind of a a place for that you know some some     
1:17:34     
additional kind of popularization of computational     
1:17:40     
Psychiatry the U what was it n Nicole     
1:17:45     
rust um as a as a New Year's resolution     
1:17:51     
you know the University of Pennsylvania Professor has new New Year's resolution for all scientists do more scom this     
1:17:59     
year oh yeah she she she felt that that was that     
1:18:07     
was good to to challenge uh any any incoming anti-science bias that uh was     
1:18:17     
you know yeah yeah so that that sounds like a great uh great new New Year's     
1:18:22     
resolution for the lab yeah yeah I think so so yeah     
1:18:28     
um but yeah there's a lot of you know and then again with a lot of these newer     
1:18:33     
Fields there's always this sort of mass of stuff that comes out and there's     
1:18:38     
always this need to sort through it like you know you have people doing a lot of work thank you     
1:18:45     
Sirah um and then you have people doing all this     
1:18:51     
great work but there's really no synthesis that you know we need synthesis really I     
1:18:57     
think to to make sense of what's going on so it's a very important step in the     
1:19:03     
thing but it's I don't know if it's science communication some of it is but some of it is you know even like Theory     
1:19:11     
building other things like that so I think there's always a rule for like you     
1:19:16     
know what we're doing is is really interesting and I think it's not like it's serving a need and we need to kind     
1:19:22     
of figure out what that what that Niche is more directly I think     
1:19:28     
because I mean we've been kind of populating that Niche somewhat but not enough and you know we can't compete     
1:19:35     
with other groups that are doing like you know state-of-the-art uh     
1:19:41     
science and it's you know not for every group some groups you know they're better at kind of you know addressing     
1:19:49     
the open questions that result from The Cutting Edge science maybe more so than     
1:19:54     
doing cutting a signs so yeah I have these two readings and I     
1:20:02     
think they're really interesting and I'm not sure how they fit together uh topic is called spontaneous activity and     
1:20:08     
intentional Behavior Uh one paper is on what they call the accumulator model and we'll     
1:20:15     
figure out what that is we go through the article and the other article was on active inference and intentional     
1:20:22     
Behavior so let's get into this uh topic this is the first paper um this is by Aaron shurer jakobo     
1:20:32     
stit and Stanis L Dean this is from     
1:20:37     
pnas uh I think it was from 2012 so it's been a while since this has been out but     
1:20:43     
this paper is called an accumulator model for spontaneous neuroactivity prior to self-initiated     
1:20:52     
movement so if you're familiar with with the Readiness potential which precedes voluntary     
1:20:59     
self-initiated movements that's what they're referring to so that you know usually when you like move your arm to a     
1:21:05     
Target location your uh premotor cortex     
1:21:12     
generates this Readiness potential which is you know preate you know pre sort of     
1:21:18     
dates the movement itself before the movement is initiated in the body it's initiated in the brain and then that     
1:21:25     
signal was initiated somehow so it's basically spontaneous     
1:21:30     
neuro activity but it translates into the self-initiated movement that's basically the problem and so this if you     
1:21:38     
are familiar with the libbe experiment or you know they use this     
1:21:43     
experiment to sort of talk about free will uh it's this idea that you can have     
1:21:48     
you have this motor planning phase before you actually have the motor execution and and so then people say     
1:21:55     
well does that mean that we don't have free will because we have these things in the brain that happened before the     
1:22:02     
actual movement and you could make that argument but it's you know ignoring of     
1:22:08     
course that your brain is not you know that your brain isn't this sort of autonomous thing that your brain is     
1:22:14     
linked to what the body is doing and it's linked to things that have happened for all this other stuff so this is an     
1:22:23     
interesting topic what they're going to talk about here is this sort of buildup and understanding     
1:22:29     
what's going on here so this is of course uh neuroactivity and we usually measure it with some sort of     
1:22:36     
EG and we're going to talk about like you know what this model is     
1:22:42     
computationally and you know what we can understand about it and then we'll move into the other     
1:22:48     
paper so let's start with the abstract um so we start out by saying ual buildup     
1:22:55     
of neuronal activity known as the Readiness potential which is going to be this signal in in brain activity it's     
1:23:03     
going to be like something you can measure electrophysiologically reliably precedes     
1:23:08     
voluntary self-initiated movements and the average time lock to movement     
1:23:14     
onset so this is where you know this happens before movement it triggers     
1:23:20     
movement and it's a buildup of the signal so this neural activity this     
1:23:25     
buildup IS presumed to reflect the final stages of planning and preparation for movement so again there's this planning     
1:23:33     
and preparation that happens and you don't think about it consciously it's a subconscious type of planning obviously     
1:23:40     
if you say for example see something on a table you want and you want to move your arm you have that sort of from     
1:23:49     
another part of your brain where you see something there's a motivation and then you want to make a movement but you     
1:23:55     
don't just make the movement there has to be some planning on making the movement on moving things and so you     
1:24:03     
know this this is something that happens very quickly but there is this planning and preparation and then the signal that     
1:24:10     
it's generated here we present a different interpretation of the premovement buildup we use a leaky stochastic     
1:24:18     
accumulator to model the neural decision of when to move in a task where there is     
1:24:23     
no specific ific temporal Q so in this case what we're doing is we don't see     
1:24:28     
anything sort of in the environment there's just kind of this neural     
1:24:34     
decision that's made through this model of a leaky stochastic accumulator basically where you get the signal it's     
1:24:41     
accumulating and it's leaky with respect to how much is stored and then there's a     
1:24:46     
stochastic component which means that the accumulation is     
1:24:51     
stochastic um so this is just kind of maybe generating the signal     
1:24:58     
spontaneously um but only a general imperative to produce a movement after an unspecified delay in the order of     
1:25:04     
several seconds so the idea isn't that you're motivated by the the model isn't motivated by any specific thing in the     
1:25:11     
environment sort of like this autonomous thing that's that's activating so it's     
1:25:16     
like there's there's a need to make a movement you don't know what it's in response to it's just making this signal     
1:25:22     
it's just hitting above threshold basically according to our model when     
1:25:27     
the imperative to produce a movement is weak so this is where you know it's not     
1:25:32     
again not Q driven but it's like there's an imperative to produce a movement in     
1:25:37     
other words we could say like you must move so many or you must produce a     
1:25:43     
movement signal so many times in a minute or you know it might be so many     
1:25:48     
times in an hour the imperative changes as the need to produce a movement changes     
1:25:55     
and again this isn't in response to any sort of stimulus it's just like an autonomous uh model that's just     
1:26:02     
generating movement so in this model when the imperative to produce a movement is weak     
1:26:08     
the precise moment at which the decision threshold is crossed leading to movement is largely determined by spontaneous sub     
1:26:15     
threshold fluctuations in neuronal activity so that means is     
1:26:22     
that uh basically movement is determined by the sort of these subth threshold     
1:26:30     
fluctuations and so the movement is spontaneous the movement signal is     
1:26:35     
spontaneous it's generating spontaneous movements um so that's that's the the     
1:26:43     
part here time locking to movement onset ensures that these fluctuations appear in the average is a gradual exponential     
1:26:50     
looking increase in neuronal activity so this this is where it's it's     
1:26:55     
linked to movement on set um our model accounts for the behavioral and electrography data recorded from Human     
1:27:03     
subjects performing the task and also makes a specific prediction that we confirmed in a second electrography     
1:27:11     
experiments this is EEG uh fast responses to temporarily unpredictable     
1:27:16     
interruptions should be preceded by a slow negative going voltage deflection     
1:27:21     
beginning well before the interruption itself even when the subject was not preparing to move at that particular     
1:27:29     
moment so this is again where they're introducing interruptions um they have these fast     
1:27:36     
responses and those can um so this this has an effect on     
1:27:44     
how movement preparations are executed so this Readiness potential is something     
1:27:50     
that has a German name of course um it's interesting um so let's     
1:27:56     
see uh let's let's go to this uh part of the paper here where they talk about the initiation of spontaneous uncued     
1:28:04     
movements this raises some unique questions if there is no external signal     
1:28:09     
to trigger the movement then what is in the brain is responsible for triggering the movement and how in in is the     
1:28:16     
precise time of onset determin so this is the question they're trying to ask with some of the things that they're     
1:28:23     
doing with their model so again you know you can have like a sort of a naturalistic setting where you move in     
1:28:30     
response to stimula in the environment but what if there's no external signal to trigger the     
1:28:36     
movement then the brain has to autonomously trigger the movement so you     
1:28:42     
know you might think like you instead of having a stimulus in the environment you     
1:28:47     
might think gee maybe I should uh like if you're in a dark room and you can't really see anything and you think yeah maybe I     
1:28:54     
should put my hand out and feel where I'm going because I can't see anything I mean that's one example of what they're     
1:29:01     
talking about this would be a mental sort of trigger but still where you know you could have a spontaneous trigger may     
1:29:08     
be a reflexive trigger where you're not seeing anything so you reach out and you try to feel walls around you to see if     
1:29:15     
there are any barriers or obstacles in your way so these are the kinds of things but the brain still has to     
1:29:20     
trigger these and it's going to be a different mechanism so you have this has to be timed properly because if it's     
1:29:28     
something that is like say a reflexive response or something then you know it     
1:29:34     
can't just be kind of uncoordinated in terms of time so these questions have been raised     
1:29:40     
in the past that the possible role of ongoing spontaneous neuro activity is not been     
1:29:46     
considered um and then they talk about the Readiness potential here um so they     
1:29:51     
talk about how you get you can record this from the EG discovered in 1969 1965 by corn Huber     
1:30:00     
and de the RP appears in the average over many data aexs time lock to movement     
1:30:07     
onset and may begin its negative deflection one full second or more before movement onset depending on     
1:30:15     
different aspects of the task and methods measure measurings and so     
1:30:21     
forth Readiness potential is taken to be the a physiological sign of planning     
1:30:26     
preparation and initiation of tional Acts echoing the widely held assumption     
1:30:32     
that gradual increases in firing rate and electrical potential to precede spontaneous movements does in fact     
1:30:39     
reflect the gold directed operations that cause those movements so one thing     
1:30:45     
we you know kind of take RP Tob Readiness potential is this sort of expression of     
1:30:53     
this great ual increase in firing rate that preced spontaneous movements and that that is sort of something that's     
1:31:00     
linked to co directed movements so uh surprisingly more than 40 years     
1:31:07     
after the discovery of the Readiness potential this assumption has only recently been     
1:31:13     
questioned and so this is where uh the premovement buildup of neuronal activity     
1:31:19     
apparent in the Readiness potential and the Assumption of causality invested in it become a Cornerstone in the study of     
1:31:26     
volition so in you know original way people thought okay this is uh a     
1:31:32     
movement this is you know this precedes movement this is sort of gold directed     
1:31:39     
exclusively um and you know we we don't really think too much about the causality or cases in which maybe it's     
1:31:46     
not involved in Gold directed mov so Benjamin Le Bay of course did these     
1:31:52     
experiments where you tried to measure the temporal relationship between the onset of Readiness potential and the     
1:31:59     
feeling of an urge to move and this is of course a pretty hard thing to measure I mean you can say you know you can kind     
1:32:06     
of link intentionality to the Readiness potential but it's hard to kind of get the sense of what constitutes uh     
1:32:14     
motivation here uh but in any case uh you know decoupling this is a very     
1:32:21     
important step in really understanding what the Readiness potential does and how it     
1:32:26     
operates the result of Le Bay at all's experiments suggested that the objective neural events of the brain cause     
1:32:32     
movement that cause movement preced the urge to move by 300 milliseconds or     
1:32:37     
more so there's a report of an urge to move or there's an urge to move which I     
1:32:43     
guess is the production of the movement and then the Readiness potential which precedes it so from a causality     
1:32:50     
standpoint this presents somewhat of a problem a recent experiment uses using     
1:32:55     
leb's Paradigm confirms the same pre- buildup at the single neuron level so before you get this urge you     
1:33:03     
get this buildup of signal uh such demonstrations have had an unrivaled influence on the prevailing     
1:33:10     
view that movement is initiated preconsciously and the feeling of intending to move is grafted on after     
1:33:16     
the fact so this is interesting that there's this decoupling between the two     
1:33:23     
between the the uh the premovement signal and the urge to move for the     
1:33:28     
movement itself and you know understanding that causality while important is not at all clear     
1:33:36     
necessarily in fact a gradual increase in neuroactivity preceding spontaneous movements appears to be a very general     
1:33:42     
phenomenon common to both vertebrates and invertebrates why do humans and crayfish     
1:33:48     
in this citation 18 exhibit the same 1 to two second buildup of neural activity     
1:33:54     
an advance of self-initiated movements so you know you see this not only in humans and in motor cortex of     
1:34:02     
humans but in cray fishes don't have the same neural structure as humans but     
1:34:08     
nevertheless have the same buildup of neural activity where it's being generated in crayfish so we have this     
1:34:16     
same phenomenon corn corn Hub anda's interpretation of the Readiness     
1:34:22     
potential is a sign of planning and preparation for movement fails to explain what specific neural operations     
1:34:28     
underly the spontaneous self-initiation of movement and why these operations are reflected in the specific exponential     
1:34:35     
shape of the Readiness potential so the shape of this signal is actually important as well here we present a very     
1:34:44     
different interpretation of the mounting neural activity receding spontaneous movements made in the context of a     
1:34:51     
spontaneous movement production task their model that they they use this     
1:34:56     
spontaneous signal shows that a decision threshold applied to autocorrelated noise in this case the output of a leaky     
1:35:04     
stochastic accumulator so this is where you have this autocorrelated     
1:35:09     
noise um in this form of a a formal generator can account for the specific     
1:35:16     
shape of the Readiness potential as well as the distribution of waiting times from subjects performing Reay     
1:35:22     
spontaneous move test we replicated the libay experiment uh behavioral and EG     
1:35:29     
results and validated our model by fitting the shape of the Readiness potential using parameters chosen by     
1:35:35     
fitting the behavioral data in addition our model also directed us to a specific     
1:35:41     
prediction that we tested with the second EG experiment so they kind of talk about     
1:35:48     
these two paradigms there's the coranda Paradigm and there's the LA paradig     
1:35:54     
these two paradigms are different in important ways although both reveal a Readiness potential when the data are     
1:35:59     
time locked to movement onset or onset of EMG activity so EMG activity being     
1:36:05     
muscles and how that signal moves to the muscles which of course is consistent     
1:36:12     
with the limb movement um and so in movement onset as     
1:36:18     
well so in the corn Inda Paradigm or K&D Paradigm subject s produce self-paced     
1:36:24     
movements at IR regular intervals for periods of a few minutes at a time     
1:36:29     
subjects are explicitly asked to avoid making rhythmic movements and to vary the intervals between movements so these     
1:36:35     
are just kind of random movements they want to randomize the movements and kind of make sure that they're not part of     
1:36:41     
you know that there isn't this sort of movement Arc or this sort     
1:36:47     
of they want to basically decouple sort of movements from their preparations and     
1:36:53     
studies that have used the candy Paradigm subjects are typically told to keep the intervals within certain     
1:36:59     
limits um for example you might have someone pause at least 15 seconds     
1:37:04     
between movements but not more than about 25 seconds um and so there's this interval     
1:37:12     
that we need to keep that you know again you have to ask subjects to do something to control their behavior and time     
1:37:18     
themselves and that's that can be you know that can be problematic but anyways     
1:37:25     
um the candy Paradigm often includes a time interval approximation task and     
1:37:31     
therefore processes of time estimation may be confounded with those specifically involved in self Initiation     
1:37:37     
Movement so you have this you know a lot of this is sort of self-report based or     
1:37:42     
self-regulation based and it kind of it's hard to measure is the bottom     
1:37:48     
one um and so both motor timing and time estimation test have been associated     
1:37:54     
with activation and some of the various same regions that are associated with self initiated or self-paced movement     
1:38:01     
notably the supplementary motor cortex or SMA and the dorsal lateral prefrontal     
1:38:07     
cortex or D dpfc so these are     
1:38:12     
um yeah so this is where you get this sort of these time estimation tasks and     
1:38:19     
the motor tasks are in the same place so you know it's kind of again it may be a     
1:38:26     
confound maybe a confoundment some of these experiments and just goes to show you     
1:38:32     
that this isn't a very thing easy thing to interpret um in the leet task which we     
1:38:38     
adopted here subjects do not repeatedly perform a movement at a regular intervals as in the K&D task instead     
1:38:46     
there are discrete trials with exactly one movement per trial once the trial     
1:38:51     
begins there is a minimum waiting interval 3 seconds and then the subject may make the instructed movement     
1:38:57     
spontaneously at any time subjects are specifically instructed to not Target a     
1:39:02     
particular time interval or pre-plan the time of their movement in any way after     
1:39:08     
the movement is made the subject recalls the approximate position of the clock dial which is shown to show the waiting     
1:39:15     
time um at at the moment here she first was aware of the urge to move so this is     
1:39:20     
kind of like you you kind of look at a clock then you can make a spontaneous     
1:39:27     
movement and then that's your urge to move again the urge to move being I     
1:39:32     
don't know how you measure that exactly um but that's basically the thing that you're     
1:39:37     
reporting so again it's hard to measure it's hard to get a handle on this     
1:39:42     
directly but um so basically they have this stochastic decision model and     
1:39:49     
thenal decision to move um human subjects are able to complain with the instruction to produce     
1:39:54     
spontaneous movements at seemingly random times when asked to do so we     
1:39:59     
propose that the brain uses the same machinery for decision making in the sort of task as it would in any decision     
1:40:06     
making task a threshold applied to the output of a neural accumul this     
1:40:11     
possibility is supported by a recent study pointing to a common neural mechanism for voluntary and stimulus     
1:40:17     
driven actions um decision- making tests are typically modeled in terms of     
1:40:23     
accumulation of evidence and so they're applying that to this sort of neural accumulator model where you're     
1:40:31     
accumulating evidence in this case it's the form of some neural     
1:40:36     
signal okay so that's that's basically what you're doing here um and so this is     
1:40:42     
some examples here of what's going on um this is the stochastic decision model     
1:40:48     
this reproduces the distribution of waiting times as well as the characteristic chap and time course of     
1:40:54     
the Readiness potential so in a we have this visual depiction of the model so     
1:41:00     
you have the signal um you have samples um after an stochastic     
1:41:08     
exponential transition period which is in here I think determined by the ratio     
1:41:13     
of urgency and leak parameters The Leaky accumulator generates noisy trajectories     
1:41:18     
which are these here where where whose threshold Crossings determine movement     
1:41:24     
times uh so it has to cross a certain threshold it moves closer to the threshold then it hits this threshold up     
1:41:31     
here and it hits it at different times so you can see the noise kind of drives it away from the threshold and then back     
1:41:37     
towards the threshold and this kind of you know there's this waiting time where     
1:41:43     
you see this distributed across um samples and so okay so that's a     
1:41:53     
and the waiting time is the time from The Trial ons set to threshold Crossing     
1:41:58     
and the Readiness potential is the average over all the simulated epics     
1:42:05     
time locked at the threshold acoss it so the reading is potential somewhere in the middle so it's like you generate a     
1:42:11     
bunch of signals and you find the average of that signal and that's the time that's the actual writing is     
1:42:18     
potential basically so the idea is that this is not like a deterministic process this     
1:42:25     
relies on um you know sort of spontaneous neuroactivity and as such we have to     
1:42:31     
model this as a series of stochastic signals that are sort of averaged     
1:42:37     
together and that's how you end up with this Readiness potential um then B is the mean waiting     
1:42:43     
time distribution and we can look at this in terms of the model we can also look at     
1:42:48     
the empirical data and we have this sort of over the number of Trials over time you see this     
1:42:57     
here um and measure the mean waiting time distribution um and then C is the mean     
1:43:05     
empirical uh Readiness Potential from the classic Le task and the mean sign     
1:43:11     
reversed output of the simulation get to the time range here so again we have our model we have the empirical data and so     
1:43:21     
that is so this is the empir empircal data from the glob a task this Gray Line     
1:43:26     
the black line is the model and if it's the model fairly     
1:43:33     
CL okay so that's um that's basically the     
1:43:43     
experiment I'm going to go down to the discussion here see if we     
1:43:49     
can all right so um the origin of selfin iated movement is a multifaceted     
1:43:54     
question and there are numerous different contexts in which spontaneous self-initiated movements may     
1:44:00     
arise initiation of foraging or grooming behaviors adjusting one's position after     
1:44:05     
having been seated for a while or even musical proposition um so there are a lot of     
1:44:13     
contexts for different types of movement our study concerns events in the brain near the end of the causal chain leading     
1:44:19     
to self-initiated movement in the last one or two section before movement onset     
1:44:25     
in a context where single specific movements where a movement is to be made spontaneously at an arbitrary     
1:44:31     
unspecified time our model was intended to account for the shape of the premovement buildup     
1:44:37     
and Rel activity is known to pred spontaneous self-initiated movements and then two the distribution     
1:44:44     
of waiting times observed in this context so um there's a lot of sort of     
1:44:53     
work that's spanned more than 40 years examining the properties of the Readiness potential its temporal     
1:45:01     
profile its Topography of different latencies variability in different task     
1:45:07     
contexts and disease States potential cortical generators given its relevance     
1:45:12     
to free will however we still lack a precise mechanistic account of what the Readiness potential reflects Beyond     
1:45:19     
descriptive phrases such as planning and preparation for movement so they     
1:45:24     
basically you know this is a term that people use but it's not clear what it     
1:45:29     
actually means especially at the neural level so you know you can say it's planning and preparation but what does     
1:45:36     
that actually result in in terms of the neural substrate so what they've done here is     
1:45:42     
offered an account for what this actually means in terms of ongoing spontanous fluctuations and neuro     
1:45:48     
activity this neural accumulator and threshold it's both plaus ible and     
1:45:54     
parsimonious uh our account departs from the prevailing assumptions about the nature of the Readiness potential and     
1:46:01     
thus suggests that some very basic questions be Revisited from a different     
1:46:08     
perspective so you know I think a lot of what they've done here is kind of     
1:46:14     
confirm the lebay experimental model but also provided um you know some pretty     
1:46:21     
interesting mechanisms for how this occurs and then you know just to be kind of clear about     
1:46:29     
this this is both a cross species phenomena so you can use this model in a     
1:46:34     
wide variety of Animal contexts from humans to crayfish so you know the     
1:46:41     
substrate the neural substrate can differ but the signal is basically generated in the same way or similar way     
1:46:48     
and then we can actually um you know look in terms of brain computer     
1:46:54     
interfaces and how they make the point here our model might also help explain     
1:47:00     
why the Readiness potential is not proved to be a particularly robust predictor in the development of     
1:47:06     
asynchronous Rin computer interfaces so we can look at brain     
1:47:11     
computer interfaces to see an example of how this is not necessarily A predictive     
1:47:16     
phenomena or as predictive as we'd like to think we assume that spontaneous     
1:47:21     
fluctuations are Ong goinging even when the subject is not preparing to move and that these can often approach the     
1:47:27     
threshold without Crossing it so you can get a lot of noise in you know if you're     
1:47:33     
looking at bcis and a lot of bcis try to use this Readiness potential as a proxy     
1:47:39     
for movement so if you're building a BCI for someone who is um not able to move     
1:47:46     
their arms and you want to use it as a control signal then you have to you know if you     
1:47:53     
make the assumption that it is a control signal you know needs to actually have some efficacy I mean you don't want to     
1:48:00     
have the BCI trigger a movement or a movement signal when no movement signal     
1:48:05     
is intended so this is maybe kind of a problem in in some of the design of bcis     
1:48:11     
and understanding this process better actually help us build um you know I     
1:48:19     
guess in terms of asynchronous bcis I guess synchronous BCI that's not so much a problem but in any     
1:48:25     
case um you know it can help help us get us a little bit     
1:48:31     
better so synchronous BCI applications use a priority knowledge at the time of     
1:48:37     
the event by queuing the subject of form an intention so there's an actual CU     
1:48:42     
involved asynchronous bcis don't have a queue and they're just recording from the neur activity so this is you know     
1:48:50     
this kind of uncovers what we're doing doing here what we're doing okay so this is an interesting     
1:48:57     
paper and it kind of gets into this whole sort of morass of literature     
1:49:04     
on per preparing to move and intentionality and you know gold     
1:49:09     
directed movements and things like that now I want to get into this other     
1:49:14     
paper and I don't know how connected this is going to be but we'll talk about this uh paper in terms of you know what     
1:49:23     
it how maybe how it links to the other paper but really standing on its own this is active inference and intentional     
1:49:29     
Behavior this is a preprint that was released in late 2023 so I don't know if this has been     
1:49:37     
published anywhere um else but I'll just go over the preprints is Earl friston is     
1:49:42     
the main author we have some active inference people here Thomas Parr uh     
1:49:48     
Christopher Buckley Maxwell ramstead so     
1:49:53     
this is um you know kind of talking about intentional behavior and     
1:49:59     
activties so the abstract reads recent advances in theoretical biology suggests     
1:50:05     
that basil cognition and sentient Behavior are emergent properties in vitro cell cultures and nor Ms so we're     
1:50:12     
going to be talking about basil cognition but mainly in the context of     
1:50:18     
like I guess things like dish brain and that type thing which we've talked about     
1:50:24     
before um such neuronal Network spontaneously learn structured behaviors     
1:50:30     
in the absence of reward and reinforcement so again we have this not it's not the Readiness potential but it     
1:50:37     
is this phenomena where you have the spontaneous learning of structured behaviors there's no reward or     
1:50:45     
reinforcement in the example before you know movements can be reinforced by     
1:50:50     
Behavior so the intention to move can be reinforced by the you know previous     
1:50:55     
Behavior or it can be reinforced by cues but you know you also have situations     
1:51:01     
where movements are generated spontaneously and so in this case what we see is we have these Ral networks     
1:51:09     
generating SP structured behaviors and the absence of a reward of     
1:51:14     
reinforcement so then these are inv vitro cell cultures so you know they're not connected to other sort of sources     
1:51:22     
of information basically in this paper we characterize this kind of self-organization through the lens of     
1:51:28     
the free energy principle and which is as self- evidencing uh we do this by first     
1:51:35     
discussing the definitions of reactive incentient Behavior and the setting of active inference which describes the     
1:51:42     
behavior of agents that model the consequences of their actions we then introduce a formal account of     
1:51:48     
intentional behavior that describes agents as driven by a preferred endpoint point or go on late in estate     
1:51:55     
spaces we then investigate these forms of reactive sentin and intentional Behavior using     
1:52:02     
simulations so the first thing they're do going to do is simulate the AFF forementioned in vitro     
1:52:09     
experiments in which neuronal culture spontaneously learn to play Pong this is the dish brain work by implementing     
1:52:16     
nested free energy minimizing processes the simulations are then used     
1:52:21     
to deconstruct the in Su predicted Behavior leading to the distinction between merely reactive sentient and     
1:52:28     
intentional Behavior but the latter formalized in terms of inductive plan this distinction     
1:52:35     
is further studied using simple machine learning benchmarks so they do some other types of uh modeling such as     
1:52:43     
navigating in Grid world in the tower ofo problem which is stacking discs on a     
1:52:49     
on a a pole and making sure that they're certain order that show how quickly and effect     
1:52:56     
efficiently adapted Behavior emerges under an inductive form of active     
1:53:03     
influence so they kind of referenced dish brain at the beginning in 2022 a     
1:53:08     
paper was published that claimed to demonstrate sentient behavior in a neuronal culture grown in a dish this is     
1:53:14     
the invitro Neal Network that they're talking about the behavior in question was the spontaneous emergence of control     
1:53:22     
movements of a paddle to hit a ball so you have this movement you know U needs     
1:53:28     
to play Pong you know they used to have this dial and it would move back and     
1:53:33     
forth they called it a paddle and you would turn it back and forth to move the uh the sort of paddle     
1:53:42     
that they had on the screen and it would you'd have to match the ball's position in space so you'd move the padal right     
1:53:49     
right left and right and you would try to match the position of the ball when it came down to the P where the paddle     
1:53:56     
should be so you you know it's a matter of predicting sort of where a ball should be it's basically this this     
1:54:02     
intentional movement on one dimension where you're trying to match some     
1:54:08     
stimulus but not just match the stimulus where it is predict where that stimulus     
1:54:13     
will be when your movement is executed so it's you know it's actually a little     
1:54:19     
bit more uh complex then what we were talking about the Readiness potential     
1:54:25     
because there's a secondary component which is the predictive component predicting a     
1:54:31     
trajectory this study has several sources of inspiration that speak to the notion of Basil cognition and related     
1:54:38     
work we talked about basil cognition in terms of Mike Levan's work and and some of the related work on that it's     
1:54:46     
basically where you have very simple cognition or the term basil being like     
1:54:52     
you know the common ancestor of all different forms of cognition so you should expect certain types of behaviors     
1:54:59     
and that should transcend like humans and crayfish as we saw in the last per okay so um in particular the     
1:55:08     
hypothesis that adaptive and predictive Behavior would emerge spontaneously was based on earlier work     
1:55:15     
showing that in vitro Neal cultures could be described as minimizing variational free energy     
1:55:27     
and thereby Evin the active inference of learning this application of the free     
1:55:32     
energy principle toal neuronal cultures was subsequently validated empirically     
1:55:38     
in the sense that changes in neuronal activity and synaptic efficacy this underwrites learning could     
1:55:45     
be predicted quantitatively as a variational free energy minimizing process so where are these findings     
1:55:52     
remarkable or were they predictable so then they consider in one sense they were entirely predictable     
1:55:59     
they were predictable from the free energy principle which states that any two networks that are coupled in a     
1:56:04     
certain sparse fashion will come to manifest a generalized synchron so     
1:56:10     
basically two networks will match each other when they are under the     
1:56:16     
constraints of the fre energy principle if they're coupled so they have to be coupled in some way     
1:56:23     
more formally the Fe states that if the probability density that underwrites the     
1:56:28     
Dynamics of coupled random dynamical systems contains a Markoff blanket which     
1:56:34     
Shields internal States from external States so it serves as sort of this boundary between ex internal and     
1:56:40     
external States it Shields internal States from the activities of external States given the blanket States or     
1:56:47     
sensory active States then internal States will look as if they track the statistics of external States or more     
1:56:55     
precisely as if they encode the parameters of a variational density uh external States beyond that     
1:57:02     
blanket so basically you know this is talking about like if we think about like the brain and     
1:57:08     
cognition we have these internal States and then we have the external stim we have the external     
1:57:14     
States and it depends on where the markof blanket what what it covers that determines more cons synct     
1:57:23     
here um so empirically the synchronization was observed when the neuronal culture s     
1:57:30     
the play Pong however the Fe goes further and says that the internal and active States     
1:57:36     
or autonomous States at vther Network can be described as minimizing a variational free energy     
1:57:42     
function um on this reading one can interpret the autonomous states of a network article or person as minimizing     
1:57:51     
variational free energy or surprise which is self-information or equivalently     
1:57:56     
maximizing basy and model evidence the marginal likelihood of sensory     
1:58:02     
States um this leads to an implicit thology in the sense that one can describe     
1:58:07     
self-organization in terms of self- evidencing that entails active inference and learning planning purpose intentions     
1:58:15     
and perhaps sentience the underlying free energy principle minimizing processes their two     
1:58:21     
way of logic iCal interpretation is is the focus for this paper so a lot of     
1:58:26     
words there um and you know it's it's fine but it's like basically if you are     
1:58:33     
very familiar with this process maybe you can into it this     
1:58:39     
better um but basically you know you have to think about what kinds of things are     
1:58:45     
involved in minimizing so they're basically reinterpreting what we were talking     
1:58:51     
about respect to the Readiness potential in the brain is having this common     
1:58:57     
framework of minimizing free energy and so if you think about like     
1:59:03     
whether I have a stimulus or not to prepare for a movement there's a minimization of free energy that sort of     
1:59:10     
biases a stochastic process to produce a movement at certain times over     
1:59:17     
others and so that kind of preference I guess it's an energetic preference then     
1:59:25     
translates into this sort of tiic imperative or this this goal     
1:59:31     
directed imperor the goal at one level being energy minimization at another     
1:59:37     
level it's producing you know movements that are efficient and they're all kind     
1:59:42     
of linked together in that U framework and then of course you can also you know     
1:59:48     
uh look at basy and model evidence the likelihood of sensory States and those     
1:59:54     
things kind of fit together in a certain way so um you know this is just kind of     
2:00:02     
extending in a way what we saw in the last paper to this model of dish brain     
2:00:07     
and sort of an interpretation in terms of free energy and variational free     
2:00:13     
energy um the results reported in one work which is this I guess the dish     
2:00:19     
brain paper were considered by some to be unre remarkable for a different reason learning to play Atari games like     
2:00:25     
pong was something that had been accomplished with machine Learning Systems years earlier using neural     
2:00:30     
networks and reinforcement so what is remarkable about a neural network reproducing the     
2:00:36     
same kind of behavior it is remarkable because one cannot use the reinforcement learning     
2:00:41     
Paradigm to explain the emergence of self- evidencing behavior seen in Metro     
2:00:47     
and by self- evidencing Behavior I guess they mean like this sort of adapt     
2:00:53     
Behavior basically you can't necessarily explain this reinforcement learning or     
2:00:59     
well is their point this follows from the fact that one cannot reward a neuronal network     
2:01:05     
because no one in neuronal network meaning the in vitro network not necessarily a neural     
2:01:11     
network um you can't reward a neuronal network because no one knows what any no     
2:01:17     
one knows what any given inv vitro neuronal Network finds rewarded so so at the level of a network you can't like     
2:01:24     
provide a reward to it to improve its performance that's not the currency of that Network for a neural network an     
2:01:31     
artificial neural network you can reward that network if you know kind of the uh     
2:01:37     
sort of the maybe the training data or you know in a reinforcement learning     
2:01:43     
model of course you can reward Things based on the reward structure you know     
2:01:48     
those things are sort of descriptive but in the case of a uh network of neurons in a     
2:01:54     
dish you can't necessarily reward it because you don't know the currency and so but in the case of free     
2:02:02     
energy we kind of know what a network finds aversive which is surprising     
2:02:08     
unpredictability so we can use that as sort of a way sort of an     
2:02:15     
anti-reward and so this was the rationale for delivering unpredictable noise to the sensory electrodes     
2:02:22     
of the cell culture or we starting the game up Hong in an unpredictable way     
2:02:27     
whenever the neurona that would fail to hit the ball so this is sort of a way that we     
2:02:33     
could um you know sort of address this issue of reward and sort of recapitulate     
2:02:41     
this in the noral network     
2:02:47     
um some found that the results reported in one remarkable but not in a good way     
2:02:52     
and I like that because sometimes things are remarkable but you don't know what the remarks are sometimes they're bad     
2:02:58     
remarks so uh but in this case yes this was this was a bunch of bad remarks they     
2:03:05     
disagreed with the claim that the behavior could be described is sentient so again you know we talked about dish     
2:03:11     
brain and I talked about sentience and this concept of sentience what they're doing here is unpacking sentients a     
2:03:17     
little bit in terms of the uh free energy principle so here we hope to make sense of the     
2:03:24     
notion of sentient behavior in terms of basy and belief updating where sentient     
2:03:29     
Behavior denotes the capacity to generate appropriate responses to sensory perturbation as opposed to     
2:03:36     
merely reactive Behavior so the goal here and the definition that they're     
2:03:41     
working with in terms of sentience is taking something that is you know maybe like uh in inv vitra     
2:03:49     
network that generates these sort stochastic responses to     
2:03:54     
things and seeing how much they can generate appropriate responses to     
2:04:00     
sensory perturbations it's not just about um optimization it's about responding to     
2:04:06     
perations and the idea is that it shouldn't necessarily be reactive it should be a little bit more     
2:04:15     
complicated um and so you know pong plane Behavior guess it's considered sentient as opposed to     
2:04:24     
reactive we consider a bright line between actions based upon the predictions of a generative model that     
2:04:29     
does does not entail the consequences of action so it's the consequences of     
2:04:34     
action and then having these three different types of behavior reactive sentient and intentional sentient     
2:04:40     
following between reactive behaviors and intentional behaviors so this is where     
2:04:46     
you know kind of they go into a little bit about how uh you know people have used model     
2:04:53     
for reinforcement learning um as an alternative to active     
2:05:00     
inference and kind of going through that this form of sentient Behavior described     
2:05:05     
in terms of basy and mechanics can be augmented with intended endpoints or goals this leads to a novel kind of     
2:05:12     
sentient behavior that not only predicts the consequences of its actions but is also able to select them to reach a goal     
2:05:19     
state that may be many steps in the future this is actually intentional Behavior which requires some of     
2:05:25     
backwards induction and you know kind of this sort of thing that we talked about within you     
2:05:33     
know Readiness potentials it are regenerating stochastic Behavior or intentional     
2:05:38     
Behavior to generate movements and what what is the substrate of     
2:05:44     
that so definitely an interesting paper there's a lot of jargon in here that's     
2:05:50     
uh related to the free energy principle into active inference so I'm not going     
2:05:56     
to dive deeply into that but I do want to point out that this is really um you know kind of thinking     
2:06:04     
about these different generated behaviors in different ways um so if we want to look at the     
2:06:11     
definitions of reactive senent and intentional Behavior you know reactive behavior is     
2:06:17     
really characterized as the sensory motor reflex arcs and the mere realization of set points     
2:06:24     
and trajectories so this is where we have very simple homeostasis in sentian Behavior we     
2:06:31     
have sort of this uh influence of perception on action is mediated by the results of planning with a distribution     
2:06:39     
of our policies derived from a model and de with counterfactual depth or a belief     
2:06:44     
about this future sensory consequences of actions then intentional Behavior not     
2:06:51     
simply driven by a generic imperative to minimize sensory productive error but     
2:06:57     
towards the attainment of a particular feature and point bate so this might be considered more     
2:07:04     
complex homeostasis um so this is these are the     
2:07:10     
ways that they Define these behaviors and then they think about active inference and so we introduced     
2:07:17     
the generative model used for the following sections which can be seen as a gen generalization of a partially     
2:07:23     
observed Markov decision process or PDP so this is something model that we can     
2:07:29     
use for uh looking at these kinds of     
2:07:35     
behaviors so this is the figure here and they kind of model reactive sentient and     
2:07:41     
intentional behaviors under these different types of reactive Behavior you can model this     
2:07:47     
with q- learning and they show this controls inference and this is equivalent to     
2:07:54     
active inference for mdps the markup decision processes sentient behaviors you have     
2:08:01     
action selection based on the inferred consequences of action intentional behaviors action selection constrained     
2:08:08     
by intended endpoints or goals you have functions for each of these and they vary by we have the q- learning     
2:08:15     
component reactive Behavior we have some variation on the uh on on     
2:08:23     
the noise signal here or the variation signal here senting Behavior Uh G and     
2:08:31     
then for intentional Behavior we have G and H on the same signal and so we     
2:08:36     
should have this expected free energy for partially observed markof decision processes here where we have two     
2:08:43     
components risk and ambiguity so that's uh kind of how they     
2:08:49     
formulate that so those are those two papers I don't     
2:08:54     
exactly know how much more they connect um I think you know with some of     
2:09:01     
the things we talked about with um the first paper I think they mapped some of     
2:09:06     
the things in the second paper especially since in the first paper they're trying to do these behavioral     
2:09:12     
experiments where it's hard to Define kind of the parameters of the experiment     
2:09:17     
you're dealing with human self reports you're dealing with different paradigms of figuring out what this Readiness this     
2:09:23     
potential is doing and then how that relates to you know intended movement so     
2:09:28     
you have this aspect of intentionality and then the second paper they model this with this dish brain     
2:09:34     
Paradigm where they look at in in vitro Network so they're just taking the measurements of uh     
2:09:42     
electrophysiology and they're modeling it with you know the active inference     
2:09:48     
Paradigm and looking at the variational fre energy so I don't know if people have     
2:09:54     
looked at the Readiness potential of creational free energy or not but I think there's an important parallel     
2:10:03     
there okay um Morgan did you have anything to     
2:10:09     
[Music] add yeah I'm not sure about the I mean I I I love     
2:10:18     
the the connection I mean there is there is a connection     
2:10:26     
um in terms of Readiness potential I'm I'm not sure sorry now that I'm talking     
2:10:32     
my dogs decided to jump on me     
2:10:38     
um and uh it's it's interesting that     
2:10:45     
they in the second paper that they're using Dish brain um or talking talking     
2:10:50     
about dish brain I mean this this sounds like a a great     
2:10:56     
thing to bring to an experimental setup like that um I mean I     
2:11:05     
I I was actually thinking more or some some about the connections between the     
2:11:12     
um the lud Bots and and the second paper     
2:11:18     
oh yeah or you know just in terms of um these uh these     
2:11:25     
paradigms being     
2:11:32     
um very easy yeah me so that that they brought it to a partially observed     
2:11:38     
Markoff decision process um you know versus you know     
2:11:44     
comparing that to some of the things that um that they're doing with ludot I I     
2:11:53     
don't know may maybe it's learn missing some of the neural stuff but     
2:12:00     
certainly easy to yeah I'm not sure sure yeah yeah there's a lot to my bra's not     
2:12:08     
fully online yet but anyway the um love love that love thinking about     
2:12:18     
um uh you know I I've I've I've been trying to take to heart some some     
2:12:25     
criticism of of free energy Principle as a     
2:12:31     
um you know to well basically when does it become a kind of     
2:12:41     
falsifiable uh you know comparable     
2:12:46     
mechanism um in a in a you know and and what would you be comparing it     
2:12:53     
against um and and when is it you know when is it more than just     
2:13:02     
variational you know I mean I I I'm trying to get ready for um January 20 21     
2:13:12     
we're gonna do um a a a textbook reading so the the     
2:13:21     
active inference textbook okay and um and that's part of the San Francisco     
2:13:28     
cognitive science reading group which is the one that did last project was     
2:13:35     
brenberg Vehicles okay Vehicles yeah     
2:13:41     
um so so it was a great discussion or you     
2:13:47     
know and um and um     
2:13:52     
it was hard not to think of that I mean when you were describing ludab Bots I I     
2:13:59     
was getting flashes of vehicles yeah yeah particular sections of vehicles     
2:14:05     
because I was just like oh this is just like you know I forget like you know     
2:14:10     
chapter five or whatever like uh I forget exactly but you know     
2:14:16     
what I mean like I was just getting flashes of that like this is exactly this is exactly brenberg thought     
2:14:23     
experiment of doing this with the robots yeah and and you know just how one you     
2:14:30     
know like yeah and and well just how much bongard is is you know is conceptu     
2:14:37     
you know computationally realizing braver Vehicles yeah and     
2:14:44     
um uh anyway so so that that that was the group and then like looking to the     
2:14:53     
active inference Institute and some things Daniel freedman's put out recently getting together     
2:15:02     
um materials etc for the next um the next cohort textbook reading     
2:15:10     
group so you know they and they read it over over multiple wops right     
2:15:16     
right um but it it anyway in preparation and also talking     
2:15:24     
with this um this student who's interested in both brain Imaging and     
2:15:29     
conversational Psychiatry um discovering some of the um Ryan     
2:15:38     
Smith uh stepbystep     
2:15:43     
tutorial which which is both a great you know paper that he explicitly     
2:15:51     
made for those trying to break     
2:15:57     
into both like computational Psychiatry well it trying to break into the active     
2:16:03     
inference research area and and feeling like there there     
2:16:10     
was no there was no um there was no good one stop place for you know a     
2:16:19     
beginner um and how he puts it in context     
2:16:26     
of um existing modelbased RL research and     
2:16:33     
and kind of terminology and so that that's that's     
2:16:38     
also interesting just because you know when you look at a lot of of um robotics     
2:16:46     
modeling and and you know again like kind of the rise of RL in in so many you     
2:16:54     
know of quote AI areas right where it's like it's either game playay or     
2:17:01     
it's robotic control and     
2:17:07     
um it's very much been around model modelbased RL or     
2:17:15     
or are related areas right     
2:17:21     
and um looking at the Luda Bots and see I mean it'd be really interesting to see     
2:17:27     
like what um you know I I see he's using pine bullet like what does what does say     
2:17:35     
Dart what what additional Frameworks or     
2:17:40     
um uh liaries would Dart bring in which is another package that's like an extra     
2:17:48     
layer on top of pie Bo I think I don't want to say necessarily     
2:17:53     
codeveloped but but but um but from kind of Robotics groups of Georgia Tech and     
2:18:00     
and and related institutions     
2:18:06     
um I think it'd be really interesting to to look at both kind of     
2:18:12     
like neuronal culture experiments which obviously you know I I'll be this is     
2:18:19     
really interesting because uh I'd love to bring something to uh we got a lot of new possibilities     
2:18:26     
with with um the Berkley neurot at Berkeley students who who really want to     
2:18:33     
do something dish brain cortical Labs as a new paper together with the brain Jers     
2:18:41     
at UCSC yeah and they're definitely trying to do something that is like you     
2:18:49     
know you use our API you know use us     
2:18:55     
remotely um I mean I I'm sure that they're also try to build out their own API just in terms of how to use one of     
2:19:02     
their boxes right but um uh anyway it's this     
2:19:10     
is um yeah just giving me some things to think about in terms of you know what if     
2:19:17     
you were going to do dish brain again you know     
2:19:23     
how would you use it you know and and um     
2:19:28     
and in and kind of in a sense like what's the research     
2:19:35     
topic when you're doing     
2:19:40     
um is brain experiments yeah and I you know it's um     
2:19:48     
and there's a couple ways to look at that and so yeah I I     
2:19:57     
I any those are my those are my thoughts yeah I think there's start somewhat     
2:20:03     
rambling because of my my cold here it's okay yeah I think there's a lot to think     
2:20:08     
about there especially a dish Brin it's like yeah it's kind of like a black box right     
2:20:14     
now and figure out how to interpret what's going on there yeah I mean you know I I just I I     
2:20:22     
think of it a lot like I mean again like um open AI back back when they were a     
2:20:29     
research Company the researcheducational company yeah you know all all the way     
2:20:36     
back in like what 2017 um uh they had a um they had a     
2:20:43     
thing called like spinning up the spinning up an RL or something like that     
2:20:49     
oh yeah anyway it was their educational materials platform and you     
2:20:57     
know and but just part of it being like like having a game engine to control the     
2:21:03     
simul to control the the um the sensory     
2:21:09     
input and to have RL to control the agents based you know agents actions and     
2:21:16     
policies you know yeah and and you know just looking at some of the     
2:21:24     
active inference yeah I mean one of the things Ryan Smith talk about like is     
2:21:30     
that you know you can you can kind of dumb down active inference and put it in this kind of variational let's just     
2:21:37     
predict a um let's predict a coin toss     
2:21:42     
kind of or you know let's predict the the bias of a coin from from coin     
2:21:48     
tosses um but you're losing some of the     
2:21:54     
active there in the sense that you know that     
2:21:59     
that this isn't an agent exploring an environment yeah this is this is you     
2:22:06     
know this is the you've abstracted so much away that that it's somewhat     
2:22:12     
collapsed down to just um traditional probalistic basing inference right right     
2:22:22     
and and that maybe you you know if you really want to have um exploration     
2:22:29     
exploitation kind of tradeoffs that you need to put an agent into an     
2:22:35     
environment um a more more complex environment like     
2:22:42     
that anyway it's just um     
2:22:50     
yeah yeah all right yeah well thanks for attending yeah     
2:22:58     
that's fine um yeah so thanks for attending and yeah there's a lot of food     
2:23:03     
for thought here I think it's a good start to the new year so let's continue to think about some of these outstanding     
2:23:09     
issues about you know gck and about submissions and about do things     
2:23:16     
so all right yeah yeah yeah yeah okay all right take care brother take care     
2:23:21     
see you next week thanks     
