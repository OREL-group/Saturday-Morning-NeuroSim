## Meeting Recording

[YouTube link](https://youtu.be/y8xTxVOtkts)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113097945436254645)

## NOTES
Jesse: fast but good week. Reading group, cybernetics. Brain organoids.

* #behind-the-scenes channel (JoPro Discord).

* Cognition Futures collaborators (same phenomenological space).

* event @ MIT? Diverse developmental intelligence.

* post-post-Hexagonal: CogSci (synesthaesia) --> evolutionary reasons.


UAlbany -- push different initiatives to that group. Aethos -- AI incubator (smaller, less defined 
groups).

* objective: let us help you do AI.

* different steps, technique that goes into organoids.


Bioprinting, Curvature/Life, History Problems, Profusion.

* 10 areas where equipment, materials come into play.

* scalability, quality control. Output --> complex electrophysiology.

* what you want comes from a very aged organoid.


Organoid intelligence: really pushes Biocomputational interface.

* biohybrid electrodes at the electrode-tissue interface.

* Nanofab aspects of this, getting more advanced.


Shubham -- RL in MESA --> ABM folder (pure agent-based model). 

* looking over agent.py. classIssue(mesa.Agent). Opening and closing times.

* which agent can take up space (individual cells)?

* if active-neighbors --> selected issues update if selected, solved.

* add contributors to the schedule. max_iter = 1000.


Reinforcement Learning -- RL agent, issue described solved attributes.

* action space has 4 degrees of freedom (N,E,S,W,NE,NW,SE,SW). Leads to observation space.

* grid_to_observation() -- both are using the same policy, rewarded differently.

* contributor vs. maintainer policies. Attributes won't get refreshed.

* OSS model -- MESA visualization. Shubham's work on Github repo.


GSoC lightening talk, Sarrah's work has been accepted (9/25 @ 4pm UTC).

* 3-4 slides --> calculator demo, other short demos.

Outline:

* 3 Summers of OSS --> open-source sustainability, Why use LLMs?, Demo (~90 sec). 

* Jopro projects development. NYCWiC meeting -- plans for venue.

* MH4H -- mental health initiative. Clinical work. CBTs -- cognitive enhancement.

* "Black Skin, White Masks" -- uniform template for all WGs.


What is a system's intended function? EGRT reference, intended cause and flow.

* #whiteboard channel. Bridge to finished concepts.

* project incubators, Harvard Innovation Lab. How to organize? 

* JoPro --> shopping mall for projects. Macro front-end.


Slime mold simulations -- novel means to create structure.

* Neuromorphic revolution workshop. Different compute architectures.

* Alt-computing: reservoir (stochastic networks) vs. neuromorphic (oscillator, spiking, slime molds).

* combinatorial solutions done by nature. Structural elements -- DevoWorm.


Build-a-cell seminar --> Gene Regulatory Networks. Single-cell computation.

* what is intracellular intelligence? Computation for lack of a better term....

* isotopes of lithium --> quantum effects in the brain. Molecular consequences of lithium action.

## TRANSCRIPT
     
Transcript     
0:04     
yeah uh regarding that um should we just wait for everyone to join I'm done with     
0:09     
my project oh yeah yeah so once everyone joins I can just take you through the     
0:15     
code and show okay that sounds good thanks morning     
0:24     
morning so how are you doing     
0:30     
okay I might um be in a slight welcome commute at some point today um maybe     
0:37     
very soon but uh a good overall it's been     
0:42     
a a fast week but a good     
0:47     
week um yeah could I been do General updates     
0:54     
I don't know if we're there yet um I     
1:01     
doing pretty well um yeah I guess shom wants to present on his project but     
1:07     
maybe you could do do your update first and then yeah I I don't have a lot to     
1:12     
say um I feel bad because I totally missed I think we're supposed to have the reading group this week for the     
1:17     
cybernetics I missed that entirely so apologize for that um and I don't think anybody if you     
1:25     
guys met without me that that's just fine and great um I don't I didn't get a sense that happened um so sorry about     
1:33     
that and we didn't really connect with Morgan either so Morgan's around today I try to talk about the brain organ and     
1:39     
stuff um just because I'm doing I'm doing a bit of work maybe later later um     
1:47     
I might I've been I've been doing some of the update from last week I've been doing some of the I don't know I don't     
1:55     
know if it's slab Manager work or just website website     
2:01     
toil of of trying to you know um make make things a bit more structured or put     
2:09     
them in Project form or move things around um I made a nice something nice for the     
2:16     
representational brins of phenotypes page that might filter well to the other stuff but um I can maybe show that a bit     
2:24     
later yeah oh yeah hey hey Morgan um I was just saying that um sorry I kind of     
2:31     
missed you Friday open to talking about stuff later for that later time I know you're     
2:38     
just getting in there um other updates for this week     
2:46     
um I tended to interesting event     
2:51     
and there's not a whole lot to say about it but it was um it was an event here that     
3:02     
may it's sort of the first time in the area that I've actually been to an event where someone was sort of interested in     
3:08     
it sort of the closest [Music] to I guess I would say um our     
3:16     
phenomenological interests in the cognition of     
3:22     
Futures and what I mean by that is that the main theme of the group like as as     
3:29     
some of us here know um maybe everybody but like in Boston there's a heavy heavy     
3:38     
heavy heavy um let's say biotech influence um     
3:45     
there's there's big farmer there's a lot of you know health related places to be     
3:51     
and do startups is is very big this is a an epicenter for that yeah worse so kind     
4:00     
of one of the themes for the event was you know longevity or cognitive     
4:05     
enhancements and I'm interested in some of those things to send memories but I was quite surprised because um at     
4:14     
least as far as I'm concerned one of the presenters who who was doing things with another lab uh is quite like they didn't     
4:23     
use the word importances but it was really close they didn't they didn't say     
4:29     
oh we need more phenomenological insights and understanding um but it was     
4:34     
close like they mentioned the word psyo Technologies uh which which feels a     
4:41     
little bit like things we we've talked a little bit about and like like like like getting it I forget the person who     
4:48     
coined that term but but sort of someone who's like oh yeah like writing and language effect you know how how how     
4:53     
your mind works and how you think like how live or whatever and and you know     
5:00     
um from what we've looked at we you know I'm I'm I'm maybe a little bit more     
5:06     
interested in sort of the the nature the way we've Tred to talk about some things in cognition     
5:12     
Futures and it wasn't quite that but it was very close to that and I think there actually might be some strong overlap     
5:18     
for doing things with um elements or parts of that group so I'm very curious     
5:25     
about that it was a very nice event overall um oh uh someone I didn't get to talk to them     
5:32     
and I don't know who they were and I it's somei like extended networking to follow list but someone from Michael     
5:39     
Lev's lab was there uh so that's sort of a potential in to to see more in that     
5:46     
way there were a few references of the tame or the um the framework that L     
5:54     
talked about not that many I probably would have liked more maybe in a discussion would have come up more um     
6:00     
but but there was a sense of the way way it came up was like     
6:06     
appealing in the sense of okay where you know cognitive life bones were sort of     
6:11     
mention and the ideas of of where you know what what sort of the upward or     
6:17     
downward pressures on you know like quote unquote cognition and and what     
6:23     
what you know the the sort of um I guess     
6:28     
you could say diversity intelligences or developmental maybe developmental intelligence is a little better lens     
6:34     
here but that's kind of where I want to go and I breached out to     
6:40     
um the speaker organizers about about that and some other things and I don't have anything really fun to say about it     
6:47     
yet other than that like oh it's feeling um but it was nice to see I'm always a     
6:53     
fan of people like actually trying to talk about what I consider I guess cognitive science but in the way that we     
6:59     
talk about it almost sort of like post post hexagonal cognitive science if you will um and I don't it's always it's     
7:07     
always so tough because the easiest things to reference are these sort of clunkier     
7:13     
um ways of talking about stuff and and I think there's a lot to     
7:19     
have been said in terms of um there there's a conversation that I     
7:26     
would have brought up there would within very long much long lines of someone was like oh like we talked about synesthesia     
7:32     
the mixing of bling of the tenses and whatnot somebody said oh well like the misfiring of the brain your neur neural     
7:38     
stour are misfiring and I think that would have been a great conversation in terms of like well um in sort of critical theory sense     
7:47     
like well what is it being compared to what are the Norms how did the Norms come about that you know what we're     
7:53     
saying blah blah blah as this standard view like standard cognition or normal cognition is blank and what one     
7:59     
development is it and so on and so forth that that's one branch go down but also um it was very interesting     
8:07     
to to see the perspective of of you know the sort of like conventional things     
8:13     
that you can say and like okay here's a here's a     
8:18     
cognitive enhancement like how can we how how is this evolutionarily beneficial to     
8:25     
um why why why would it be a good thing to have s why would be a good thing to mix some your numbers of colors and     
8:31     
letters and and other other like Century with experiences and stuff like that and it it was a it was a nice discussion and     
8:38     
I think it was a brave discussion because I find a lot of people at least at least in this area and the pressures     
8:44     
for how things are in in like what's cool to talk about or not I think there were some risks taken that I appreciate     
8:51     
in terms of trying to get deeper at like     
8:56     
um and issues that I think matter a lot and we talked about in a lab um even it     
9:01     
wasn't it wasn't touched upon directly but there was a little bit of like Observer dependency discussed and I was     
9:07     
like oh yeah like like in in the future like I will mention our defendant the talk that we've had work we done in that     
9:13     
space so um that was that was fun that was a fun unexpected thing     
9:19     
um unfortunately one of my friends is leaving the area soon but there's who related to this um     
9:30     
but um there may be some opportunities ahead uh to do things there um that's     
9:38     
that's my major update and and I'll say there wasn't there wasn't anything um     
9:44     
the way the way things work out this week I did not push too much forward with the U stuff that we talked about     
9:51     
last week but there will be more um this weekend and this week on that front so I     
9:58     
don't know if you ever want um like there's about a model builder     
10:04     
thing to talk about and and some other projects um that we can pitch to that     
10:11     
that group but um no no concrete things there but it's     
10:19     
it's certainly like on Deck as for things that are coming up that way I feel like     
10:25     
there's a few other things that happen this week but I don't they're not jumping out to right     
10:35     
now so where was that meeting is it an MIT or     
10:42     
um I mean it wasn't at a campus Building but     
10:48     
it was basically it was in Kendall Square which is like in Cambridge right     
10:53     
across from at MIT so uh it was at a a building um there but it I mean there     
11:01     
were many MIT students there of course but um it was a I think the the the     
11:09     
hosting organizations called Athos um and they do a lot of AI like     
11:16     
they're I think they're trying to be sort of like an AI incubator type     
11:22     
group and then there was a smaller group that was a little more um I don't know     
11:28     
if spin-off relation to the one they similar names like AOS and then another like kind of weird sounding name and it     
11:36     
was um they're they're a little more um I'll send a website later they're a little     
11:41     
more um     
11:47     
uh they're smaller and less defined right now but but I think it's sort of like a I think I think it's a a stretch     
11:55     
of an analogy to say Athos is sort of like     
12:00     
or orthogonal lab and and the other group is a bit like representational brins and phenotypes kind of like a     
12:05     
working group that's in development and I think has some kind of some funding     
12:12     
and some some structure that's in development with a couple folks that I know so I'm not quite sure how to     
12:18     
differentiate it but but basically that was the Ho group and there's ties     
12:23     
to they're established AOS is um     
12:30     
is is an established group that has a lot of like are you making AI why don't     
12:36     
you see we can help you do it kind of the thing um so a bit like incubator a bit development oriented um but from     
12:44     
much more from a I don't know uh from a particular     
12:51     
perspective I guess but it was a very     
12:56     
um I had a good feeling about um all of that yeah well that's good that sounds     
13:03     
good sounds interesting um yeah and you know just     
13:09     
kind of maybe you can make some connections there you know uh that sounds like a     
13:15     
good enough uh group there to and and so yeah I you know I don't     
13:21     
think too much about a lot of the startups that exist like just in the no     
13:26     
and crannies of different you know University communities like if you're near MIT or you're in San Francisco you     
13:35     
know there are a lot of people who kind of uh are kind of affiliated with universities they're kind of you know     
13:42     
not it's kind of hard to find them so that's great and then I I I was this     
13:47     
week I was uh of course we did the uh Morgan and I yesterday we did a meeting     
13:52     
on uh brain organoids or of an admin and I have I have notes from that     
14:00     
so I can actually pass them on to Jesse um you know it was like we had I     
14:05     
think we had a very tight set of sort of followup action item type things so you     
14:11     
know Morgan's been doing a lot of reconnaissance on brain organoid research like you know lab     
14:18     
work uh computational work education and they all these groups in you know the     
14:25     
Bay Area Santa Cruz places like that where doing a lot of really interesting     
14:31     
stuff and you know how do you kind of bring that to bear and and     
14:36     
do some research you know that's that's really the question and brain organoids     
14:42     
are tough because from what we were talking about I think it's tough for everyone who gets into it because     
14:48     
there's so much to deal with and it looks like Morgan wants to say something about it well just uh I was going to say like     
14:57     
I also put together other some notes or you know I can expand on what we discussed and um yeah you know Jess you     
15:07     
didn't miss too much I I was multitasking I I I get my son to to get     
15:15     
his driving test so um but but um uh I I     
15:20     
want to flesh out the um the kind the     
15:27     
various um the various Technologies     
15:35     
for the the different um different steps     
15:41     
and or kind of materials and or processes that go into the organized     
15:47     
culture and like each each one is developing you know um uh they just just     
15:59     
looking at a bioarchive paper right now that     
16:04     
is using bioprinted um hydrogel material     
16:11     
to yeah do kind of some some you know novel Innovation to increase     
16:20     
um one of the issues that we talking about is the with     
16:27     
significant growth or age um the the problems of of getting nutrients to all     
16:35     
the cells and you know like     
16:42     
a I want to say vascularization in the kind of biological sense     
16:49     
but you know increased profusion let's say via VIA the the yeah this kind of     
17:02     
um bioprinted scaffold and so yeah like like there's     
17:09     
at least you know kind of 10 steps or you know 10 10 areas where you know     
17:17     
either equipment comes into play or materials comes into play and certainly     
17:23     
you know one of the things theyve been tracking all along is um how to reduce     
17:29     
the cost of the the growth factors so there there's like a     
17:36     
synthetic bio projects that could be you know you could say is involved again I     
17:44     
if if part of what you're working towards is like increased     
17:50     
scalability so like like automation is is under that kind of scalability as is     
17:57     
you know quality control which includes computer vision which includes you know     
18:03     
um microscopy and yeah anyway I should     
18:08     
really get all of these in into into a dock and um just     
18:16     
be love love to contribute to those minutes right oh yeah yeah I I'll set it     
18:22     
I'll get mine together and put them up in the at lab admin channel in slack     
18:28     
Maybe can add to that um yeah so I think yeah I think Morgan's giving a good     
18:34     
example of the kinds of things we're talking about there just a lot of technical challenges but there also a     
18:40     
lot of questions that people uh can't you know need to answer I guess to get     
18:46     
like really good organoid work out because right now you know we're kind of in the exploratory stage a lot of papers     
18:52     
have been written on here's an organoid and we measure this and and you know of     
18:57     
course we have organoid intelligence but like you know there's a gap there in terms of getting you know high quality     
19:04     
reproducible stuff that's you know you could say this is like you know     
19:10     
something anyone can Implement in their own home lab it's usually like Labs with a lot of resources and their groups     
19:17     
doing uh that sort of thing but it's like a you know it's very challenging to do a     
19:24     
lot I mean certainly certainly the the the extra challenge     
19:32     
here is that you know if if your output from the     
19:41     
organ you know the super org um is is the kind of     
19:49     
complex uh electrophysiology yeah right so so as Nal Lancaster is     
19:57     
saying excuse me     
20:04     
um this this comes with in very aged     
20:10     
organ right so so and and again this is     
20:15     
this is what everybody also highlights as what becomes a quality control problem is     
20:22     
that um yeah just just as as you're as you're     
20:27     
keeping these to to get to the the you know older older age seems there     
20:36     
you know again we're just talking weeks here potentially right ideally a couple     
20:41     
months but yeah C culture age yeah yeah yeah yeah yeah uh um but that's that's     
20:49     
the kind of necrosis necrotic problems that that     
20:54     
will arise and you know combination of just in in the kind of you know sphere of     
21:02     
cells potentially or you know and again because you're     
21:08     
interested in electrophysiology um the electrodes organiz     
21:17     
interface and and the the you     
21:26     
knowell is one of those where you're really pushing that     
21:31     
organ's electrode inter yourface yeah because you that that's     
21:38     
that you know it is it is essentially a biohybrids computer yeah and um so some     
21:47     
of the work you know that there's this interesting subdomain um of     
21:56     
um of like startups and and you know commercial interest in in biohybrid     
22:05     
electrodes that is is of interest because of I mean they're all they're     
22:11     
trying to solve a problem in brain implants and that problem is the is     
22:19     
essentially the um electrodes tissue interface     
22:26     
yeah so it it's it's a it's a again another one of these interesting areas     
22:32     
to to track that it's got a whole lot of um you know     
22:40     
quite Capital intensive Technologies behind it yeah in terms of of you know     
22:48     
microelectronics and and you know essentially nanotech I mean the um the     
22:54     
3D the the the kind of um yeah the fa     
22:59     
nanofabrication of this is is like super interesting but it's getting it's     
23:05     
starting to get more like um it's like weird combination of kind     
23:13     
of yeah like a number of unique they're unique     
23:18     
Technologies but they are like chip design you know or they're like chip manfactured     
23:25     
yeah interesting yeah anyway I'll be hope hopefully be able to say     
23:32     
more about that soon but but that's that's actually one of the grants that's going in in the UK um     
23:41     
and um yeah yeah okay yeah so I mean it's good to     
23:48     
give an update on on some the challenges to getting because we've been trying to get this off the ground for quite a     
23:54     
while it's always you know just interesting to see what the challenges are and of course once again that uh     
24:00     
curved biology is the problem right like you know curvature is always the if     
24:06     
biology were Square cubes you could simulate it and work with it well it's     
24:11     
not unless it's a spherical cow then we don't want that either because that's like     
24:16     
oversimplification well yeah yeah although strangely in this case like     
24:22     
yeah this is this is the most spherical cow we get yeah yeah well it is you know     
24:28     
again it's just it's funny what Hopkins Hopkins mea is is essentially trying to     
24:37     
make um brain caps for organized in these these kind of yeah     
24:44     
they look like little you know hemispheres yeah all right great it sounds like a     
24:51     
yeah we had a meeting on that and and Jesse you know will'll get you the notes for that so uh you can catch up um other     
24:59     
than that this week we had D.A worm so I had a an update one of the update meetings for D.A worm where you know we     
25:07     
I kind of went over some things that we've been talking about recently in different meeting in our you know series     
25:13     
of meetings so I did actually did a Pap I reviewed a couple papers I talked     
25:18     
about some of the things that were uh kind of closing out gach in uh the graph     
25:24     
neural networks area so we talked a little bit about that I talked about uh     
25:29     
a paper on Gia and seans which was interesting uh it's another area you     
25:34     
know where seans is a model organism for uh disease and of course you have uh Gia     
25:42     
which you know is not a topic that people generally focus on so it was basically going on about how to compare     
25:50     
or how to look at glea and celegans it's an interesting system because there's specific FAL cells that we know of in     
25:58     
the connecto so we have you know every cell the elegans is characterized with a Gomen clature label     
26:06     
and we know the function pretty much some of those cells are G cells and so they fit into the connectome so when you     
26:12     
look at the connectome you're actually looking at you know neurons you're     
26:17     
looking at inner neurons you're looking at Sensory neurons you're also looking at things like Gia and so then you know     
26:23     
the paper talked about that it also talked about um you know how How Wheel     
26:29     
cells do things in a connectome that are related to maintenance and modulation of     
26:35     
signals and things like that and then connecting that to humans which of course is a huge step uh both in terms     
26:44     
of you know scaling up the connecto because not just scaling it up in terms of size but in terms of the way the G     
26:51     
cells work or what they do in in humans versus or what they called ma their     
26:56     
mammal category is as opposed to something like C elegance and just kind know making the     
27:02     
analogy between like if you study something in seans like     
27:08     
aging and something in mammals so it's it's you know they use celegans as a     
27:13     
model organism for things like aging and and U some neurodegenerative diseases     
27:18     
and things like that but it's always a tenuous link because you have like this vastly different system you're just     
27:25     
gaining maybe some of the uh lessons of the genetics of it or you know some of     
27:31     
the fundamental sort of neural transmission aspects but you know there's a huge gap     
27:37     
and it's It's always important to be aware of and then the final set of things I     
27:42     
talked about was about um like mechanical networks so we're talking about active myosin networks we've been     
27:50     
talking about that for a while especially in the context of tensegrity and so you know I reviewed a     
27:56     
bunch of things on acting myos networks how people model them uh so spoiler     
28:02     
alert they model them in different ways you go from the atomistic models which model what's going on inside a single     
28:08     
filament so it could be you know the molecular interactions the molecular Dynamics inside of a single filament and     
28:15     
then the action of the networks both in terms of their connectivity and in terms     
28:20     
of their sort of uh functional aspects so you have basically uh what we know is     
28:27     
a complex Network but instead of just having uh nodes and edges we have these     
28:32     
active edges that change dynamically and even the nodes change     
28:38     
their properties dynamically we can end up with things like hyper     
28:43     
hypergraphs and other types of you know networks with mechanical properties that     
28:49     
are sort of imbued in them so you know these are all things that you know I     
28:55     
think you know are kind of following up on some of the things we' talked about on DVA worm in the last maybe three     
29:01     
months um so that that was Diva worm and then we were going to have a meeting on     
29:06     
cybernetics but we didn't have that meeting uh I actually saw um Amanda for     
29:13     
the first time in a couple months so you know but we didn't have the meeting and but you we want to review     
29:20     
this paper this uh ever good regulator theorem paper uh so yeah we have two we have two     
29:28     
of those the one I did with Rob Stone and then the one we're doing collectively uh with reference     
29:35     
to uh modern you know uh World models so     
29:42     
that's that's something we're going to get to this fall hopefully there's just a lot in that paper to go over so it's     
29:48     
not going to be just one meeting so we hope to pick up the cybernetics meetings     
29:53     
soon and you know it's just hectic at a number of fronts get the cognition Futures meetings back     
30:00     
up if for according to Jesse's schedule and then our Friday times are we don't     
30:08     
uh we kind of completed our open source meetings for this year but we are you know I'm doing actually a thing on uh     
30:16     
the model builder series um it's basically a group of students doing     
30:21     
independent study on building models and um you mostly machine learning models in     
30:27     
their case but kind of getting this idea of models and model building so that's that's all     
30:33     
fun um but we may might also have administrative meetings at that 11 or at     
30:39     
that I guess noon Eastern slot so that's something to look out for as     
30:45     
well okay so um I I wanted to get back to shom who wants to present on his gck     
30:54     
stuff or his you know open source stuff and if he's there he had to go     
31:00     
somewhere but he's there okay so would you like to present so hereone uh I'll just share my     
31:08     
screen and uh I'll take everyone through the code once and then we can see the     
31:13     
output that's     
31:22     
um is my screen visible yes okay so this is uh the code base so     
31:30     
what I've done is um I have uh first I have created an ABM     
31:35     
folder that contains the pure agent based model and another folder where I     
31:40     
have implemented the reinforcement learning part on the same U ABM so over     
31:47     
here we can start with this agent. file I have three uh agents that will be uh     
31:53     
you know simulated in the grid one is an issue and the second one is the contributor agent third one is the     
31:59     
maintainer agent so issue agent has uh some attributes assigned to it unique ID     
32:06     
every agent has its unique ID so that we can you know find out the unique neighbors around it or whatever other     
32:14     
attributes that we want to access then we have its position uh the difficulty     
32:19     
uh difficulty part was actually already addressed in the previous models uh we have Earth short Moon short and Mars     
32:25     
short issues based on the incre difficulty I have added another attribute over here that is the priority     
32:32     
so the so that the max priority issues get addressed first then I have the     
32:38     
threshold threshold is basically um what sort of uh code efficiency is present     
32:46     
when the issue is solved right so uh and then I have initialized those attributes     
32:52     
with some values over here I have an opening time and a closing time so this means opening time basically means when     
32:58     
the issue agent was added to the simulation closing time means when the issue was you know solved completely     
33:05     
basically when the pr was raised and the pr was accepted into the final code     
33:11     
base uh the issue agent doesn't have any     
33:16     
um you know inference or basically thought process of its own it doesn't move around in the grid stays stationary     
33:22     
uh but still I have a uh function to update its neighbors basically uh every     
33:28     
step the um you know the GD is changing so we need to find the um cells around     
33:35     
it that are empty where the other maintainer or contributor agents can um you know take up that space or take up     
33:41     
that sell secondly I have contributor agent over here I have three attributes     
33:46     
for it one is the position that is pretty obvious Vision vision is basically how far the contributor agent     
33:53     
can see so uh the default value have set to seven so basically it can see uh     
34:01     
seven cells in all directions right so in those seven cells it will try to find     
34:08     
the um you know issue agents that are supposed to be addressed and then it can     
34:13     
be those can be addressed and uh so in those neighboring celles if it finds any     
34:19     
agent with the instance of issue and if the status of that agent is open so     
34:25     
basically it is an open issue uh it gets appended to a array called active neighbors and then if there are certain     
34:32     
active neighbors then it selects an issue uh from those multiple issues it     
34:39     
selects one particular issue and the status turns to solve right so after     
34:47     
that we have as I mentioned there was an attribute called code efficiency So     
34:53     
based on the uh skill of the uh contributor     
34:58     
the a random code quality is assigned to that particular issue and we move forward with updating the neighbors of     
35:05     
around the contributor agent uh similar logic with maintainer agent if it finds     
35:10     
uh any issue that is around in its neighboring cells which status has     
35:16     
solved uh It Go selects that particular issue and then if the code efficiency is     
35:22     
greater than 70 that that is threshold value then it uh the status is uh change     
35:28     
to close and closing time is basically when all of this process is completed     
35:33     
right if this code efficiency is not greater than 70 then the status has turned back to open and then again we     
35:40     
can move the agent around in the grid uh next I have the model. P so over here     
35:46     
I'm just initializing some values like you know what is the density of the issue agents contributed enties and     
35:52     
maintainer densities um then I have uh some data collect function over here uh     
35:59     
that collects the number of Earth issues that are solved then Moon then Mars and then the accepted PRS the average review     
36:06     
time and average code efficiency uh secondly I have some agent reporters that collect the position status and     
36:12     
other attributes of the agents um then over here we are initializing the agents into the grid we are assigning uh unique     
36:20     
IDs and um placing them in the um grid     
36:26     
and then over here we're adding them to the schedule right so then we have a     
36:31     
step function over here so step function what it does is um every every uh step     
36:37     
the agents follow their definitions basically whether to move around or to solve an issue or to review of PR and     
36:45     
the data is collected and the iteration is increased by one step so what I've     
36:50     
done here is I've had a maximum iterations that is thousand so once the this is done the schedule St the step     
36:59     
function stops because St running turns to false and the step function doesn't     
37:04     
execute anymore over here I have some functions to um you know the collect the     
37:10     
data U of the issue agents or the average efficiency of the code or the uh     
37:16     
review time and Etc uh then I have the server over here this is basically like     
37:24     
the you can call it a front end where you can you know uh uh deploy your model     
37:29     
and uh uh we have some sliders uh to change the values of issue entities or     
37:35     
contributed entities and other other uh attributes or variables     
37:42     
um this doesn't have a lot we have a server to launch and then you can launch it uh this is where the reinforcement     
37:49     
learning part gets uh you know um um what call it it gets implemented uh     
37:56     
right so over here I have imported the issue agents the previous Agents from the     
38:03     
agent. file in ABM directory uh as we     
38:08     
already as we have already seen issue doesn't have to need to have any step function but just to update its neighbor     
38:15     
I have mentioned the step function over here then I have the contributor RL agent basically it's the reinforcement     
38:22     
learning implemented agent so I have uh     
38:27     
um address another attribute over here that is the issue solved uh attribute so     
38:33     
once it solves an issue this turns to true and uh during our U reward     
38:39     
calculations we can use this particular attribute to reward the agent and same     
38:44     
goes with the maintainer agent I have addressed a new issue reviewed attribute     
38:50     
this same can be used in while calculating the rewards uh this     
38:56     
particular part is is the same as the agent Pi in the AVM um then this is the     
39:02     
model Pi so over here we are again addressing the um variables present in     
39:09     
the model the WID height and density and other things over here I have an     
39:14     
observation space so this observation space is like uh what an agent in in a     
39:20     
particular step can see so uh we have an array uh that contains 224 elements uh     
39:28     
whose maximum the elements can have a minimum value of zero and a maximum value of four we'll see this later what     
39:33     
zero and four actually are and then we have an action space it has eight     
39:38     
discrete values so eight discrete values meaning it can go north south east west     
39:45     
Northeast and also diagonal in the diagonal directions and then you have a step function uh so over here we call     
39:52     
all the functions to collect the data to um you know to um schedule the step and to um um just select the action what the     
40:02     
agent has to take then over here we have the calculate reward function this     
40:07     
basically calculates the reward so uh in the agents that are scheduled if the     
40:14     
instance is contributor basically the reinforcement learning implemented contributor agent as I mentioned the     
40:20     
attribute was going to be used for uh rewarding the agent uh so over     
40:25     
here if the issue solved is true it gets one point and if the issue solv is full it gets zero points and it moves     
40:32     
on ahead same goes with the maintainer RM then we have a reset function over here after every episode The Grid has to     
40:39     
go back to its original state so we are just um putting it back into its original state activating randomly then     
40:46     
a single grid um grid is used uh the initial agents are created again and     
40:52     
they are you know converted into an observation space and everything so     
40:58     
next I have a utility dop utility. Pi contains basically contains all the     
41:04     
functions that are again repeated again and again so create initial agents is used to observation is used around three     
41:11     
times uh to update the observation space at each step so what happens over here     
41:16     
is um if the instance um is is an issue RL agent and its     
41:24     
status is open the row appends to and um if it's solved the row appends one and     
41:31     
if it's closed it appends four if there is any other agent other than the issue say contributor or maintainer it appends     
41:37     
three and this is again sent back to uh our observation space that I talked     
41:42     
about as I told uh these zero and four have that um zero and four mean uh what     
41:49     
kind of agents are present around a particular agent and uh over here I have     
41:54     
a move function if the action action integer value is zero it stay it moves     
42:00     
to the right direction so the x value is increased by one if it wants to move to the left uh the x value is reduced by     
42:06     
one and everything then I have the server. pi over here so server. Pi     
42:12     
basically consists of again uh the sliders and all the values that can be     
42:17     
changed to manipulate the grid and everything uh that's it over here um     
42:23     
what this is the kind of the ray RL logic what is happening over here is uh     
42:29     
we have to um you know connect our environment and uh tell the uh grid     
42:38     
what sort of policy to use whether we have to use a contributor policy or we have to use the maintainer policy and     
42:45     
that is it what is going on over here uh over here if the agent ID starts with     
42:51     
contributor it has to use the contributor policy and it computes the actions over here uh and it return     
42:57     
returns it to the action space next we have a train config.py this has the     
43:03     
configurations of what to use whether how many gpus to use we have to use zero gpus and number of Learners number of     
43:10     
roll out fragment length is set to Auto so that um these um roll out fragment     
43:17     
length depends on number of learns Learners and number of event Runners so if you change the value this     
43:22     
automatically sets it to whatever will be the most appropriate then I have a     
43:27     
train. file over here that you know um get config is basically we call this     
43:33     
inside our train model uh to enter all these config information into the uh     
43:40     
this function and then this train model is called inside our example. that is     
43:46     
the final file that we we will be running and it is called over here with     
43:51     
all the configurations and everything and after the training is done uh it uh     
43:56     
stores the information in a direct called checkpoint in a file called results. EXT it pretty prints the     
44:04     
results into this file and then we can run our model uh on this particular code and it     
44:10     
opens the browser and everything so I'll just run the file and show just a     
44:20     
second here we go so over here we have the results and everything how many Learners how many steps and everything     
44:28     
and uh over here you can see so now one error that I'm facing over here is that     
44:34     
every step like after every step the attributes are getting refreshed for some reason but the code efficiency as     
44:41     
you can see it is maintaining a good 70 plus um an average of good 70 plus most     
44:47     
of the time but uh the thing is after every step the attributes are getting refreshed basically if the if a     
44:54     
particular um you know um issue was uh status was turned to solve in the next     
45:00     
step it goes back to open without even reviewing it so this is something I need to figure out and uh other than that     
45:07     
most the project is working fine so I could have a meet with himansu to maybe     
45:13     
figure this out or something uh how to run the train models uh so for now the     
45:18     
model is running pretty good we have sliders over here we can um you know play around with the issue densities how     
45:25     
many issues do we want and the contributed vision and everything uh over here I have a button that can toble     
45:32     
the movement of the agents so if I just turn it if I just turn it off the agents     
45:38     
don't move around and everything so this is pretty much the     
45:45     
project and uh yeah this is one last thing that I need to figure out     
45:51     
[Music] before why is the why are the attributes getting refreshed at step that is one     
45:58     
thing that I need to figure out so that's the grid that's where the agent based model plays out yeah for some     
46:04     
reason because yeah you can see over here the review time is constantly zero that means the PRS that are getting     
46:09     
accepted are not getting counted yeah is that is that a bug or is that intentional that that is supposed to be     
46:16     
a bug I think because I use some outdated ra documentation okay so maybe     
46:23     
because of that so I'll try to figure that out but that's not a very big issue I actually faced the bigger issues you     
46:29     
know creating this because um the observation space and the grid values     
46:35     
were not matching at all and um I had to you know keep take misa's G so project     
46:43     
as a reference to create this because I I started with creating I     
46:48     
started with petting zoo and um that that had too many variables to take care     
46:53     
of so that was not a very um you know viable option right last year Raj gopal     
47:00     
he he already told me actually that it is not a very good option but I still went for it and I realized it's not     
47:06     
going to work out so I just went ahead with the day reinforcement learning live video of     
47:13     
day so I'll try to figure this out maybe I can have a meet with himansu and he     
47:18     
can help me out with this other than that the project is working fine well that's great yeah I also I can also show     
47:25     
you the so once the training gets completed uh in the results for txt the     
47:31     
results get pretty printed uh basically of both the policy contributor and the     
47:38     
policy of maintainer oh yeah yeah so how many Learners were there what was the curl     
47:44     
coefficiency entropy and everything so pretty much we can pretty     
47:50     
much use it now uh the only thing that I need to fix is this why is it getting refreshed again yeah yeah so this is     
47:58     
great work uh so you did also I saw that you pushed some things to the GitHub     
48:03     
repository yeah so those are all kind of in there's a directory that has uh this     
48:10     
work in actually I'll have to make some changes with that because I didn't     
48:16     
create separate folders for agent based model and the ABM with our reinforcement learning part so I'll make those changes     
48:22     
and uh maybe by tonight or maximum tomorrow morning I'll make all the     
48:28     
changes and I'll update the read file as well okay that's that's good so this is     
48:33     
all on our gso uh repository on oral group on GitHub yeah and so that's where     
48:40     
sar's work is in a different directory this work as in so they're all kind of labeled by the name of the project so     
48:47     
yes yeah so that's great thank you shup do we have any questions for     
48:54     
chup so uh I mean I was just curious like you show the training process so do     
48:59     
you have like any trained model like you know some kind of that is that is     
49:05     
exactly what the problem is right now so um the training model we once we run     
49:12     
this uh example. file the model gets trained but I don't think the trained     
49:18     
model is running after the file gets executed it is again training the model and that is why uh the step function     
49:24     
every attribute is getting refreshed again and again if it runs a trained model the attributes won't get refreshed     
49:30     
so I think these are models that are not trained already it's training the model again while the grid is moving     
49:37     
around so that is something I need to figure     
49:42     
out okay sure yeah and so you you mentioned that     
49:49     
there are these contributor versus maintainer policies so these are just based on the category of the agent and     
49:56     
then they pursue a certain policy or no both are using the PPU policies but     
50:03     
because we are using different attributes and different action spaces to reward them so I just made two     
50:09     
separate um you know parts for both of them all     
50:17     
right looks good good to know um so yeah I look forward to playing with this and     
50:23     
you know um so again you know I extend the same invitation that I     
50:28     
extended to Sara which is if you'd like to continue working on this or if you'd like to work with the     
50:34     
organization um you know you're welcome to do so you know we talk about that     
50:40     
yeah yeah definitely I have some other ideas that I can maybe in future uh not     
50:46     
as frequently now but yes definitely I can make some changes uh in the coming yeah sounds great thank you thank     
50:55     
you so much yeah this this is good so actually one thing we need to talk about with respect     
51:01     
to the projects uh on open source sustainability is that we have this     
51:06     
preprint and the preprint has included the last two years of work um and I     
51:12     
didn't really update it much last year but I I would like to include SAR and shom's work because we've been working     
51:19     
on this long-term Arc of reinforcement learning so we've gotten three Summers now where we' worked on reinforcement     
51:26     
learning models and you know that needs to be kind of updated and talked about in     
51:32     
terms of that Arc maybe we need to reorganize the preprint probably um and then Sara's work on     
51:40     
using large language models so that would be like a separate section and     
51:45     
that might have connections to some of the active influence stuff that Brian did like I guess three years ago now so     
51:52     
you know we'll kind of think about that I'm G to kind of pull that out and we'll try to reorganize it and and update it     
51:59     
and I invite sham and Sara to be a part of that as well so you know we can as those things we get to that point     
52:08     
we'll talk about it more so yes definitely definitely yeah yeah right     
52:15     
thank you um another small update I wanted to     
52:20     
give from my side uh so um there is uh there are G lightning     
52:28     
talks I think someone from uh the or had participated last last year and had     
52:34     
given a talk as well uh so I have been selected like my project has been     
52:39     
selected for that talk as well this year uh so that is on the     
52:46     
26th from right yeah um     
52:56     
[Music] just yeah 25th September 25th at 400 p.m     
53:03     
UTC uh is when the so there are three different days this year that they're     
53:09     
having the talk so mine has been given this time so and uh in the talk we have     
53:14     
to present it's about 3 minutes and uh so I've given this talk once before as well when I did my     
53:21     
last so I think the it's some it's a three minute deadline and we need to     
53:27     
uh present slides so I believe it's three to four slides is the limit and uh     
53:34     
yeah maximum of three slides uh so the deadline to submit the     
53:40     
slides is September 16th uh so uh so yeah mostly by next     
53:46     
week's meet this time I'll have some idea I've not been able to do much yet     
53:52     
uh to put together the slides like I have um I have have the information     
53:57     
definitely I was trying to like I want to see if maybe there's a way I could include a demo     
54:04     
video so if that's possible because I was struggling with that during the presentation as well um so if I able to     
54:12     
figure it out by you know this time next week um I will definitely try to put     
54:18     
that into the slides and maybe host it on the YouTube channel okay I'll let you     
54:24     
all know how it comes along but if it doesn't happen in the worst case we definitely have screenshots of all the     
54:31     
different components that I could compose my slides of U but yeah I just wanted to inform everybody about that     
54:38     
yeah that sounds great congratulations thank you uh I mean I     
54:44     
think it's mostly love based so in terms of demos like you know     
54:50     
building a demo is kind of tricky because you know it's like what do you want to put in there you want to run the     
54:55     
program and show yeah um you know is that like is that what you're thinking     
55:01     
of and yeah definitely the first thing I want to do uh is like with the     
55:06     
calculator project kind of thing I had throughout the entire this I want to get     
55:12     
it working with the front end and the you know the whole AI models and the     
55:19     
auto Cod R running in the back end that's still something that I've not been able to get a full run yet because     
55:26     
of ram issues and other stuff I also have to give my laptop in for some repairs uh the next week so I'll see how     
55:33     
that happens uh but yeah that is one thing I want to do and then the second thing that I was once that works once     
55:39     
you know it works the another thing I was definitely thinking off was like the calculator project is a kind of simple     
55:45     
very simple demo repo so maybe there was something more     
55:51     
complex I could try that but then once again there's a thing of will it work     
55:57     
smoothly so I definitely don't want to try do it live because it won't fit in the 3 minute time SL     
56:03     
right but maybe shooting a video and speeding up all of the loading processes     
56:10     
might work so yeah if there are any ideas onto what could be a good demo     
56:16     
repository like I have a calculator project was the simplest thing I could think of that you know AI would     
56:22     
definitely get the code right for so that is what I've gone with now um so     
56:28     
yeah there any ideas uh for something else that might be more demo uh that would be very appreciated I     
56:36     
could work on it try uh I guess my word on that would be     
56:42     
like pick something that is like high visual payoff so like if you show people     
56:48     
just a bunch of code going by in the screen that doesn't really uh I don't know how you visualize     
56:54     
some of this like I I don't know if you could visual plan is to show the demo     
56:59     
the the front end that I created yeah so that is definitely the end plan so in     
57:05     
that there will be the metric graphs going about okay yeah uh and then there     
57:10     
will be the pull request that the you know the AI models come up with yeah and     
57:16     
there'll be the discussion that happens between these agents uh you know and they're trying to bid for a GitHub bid     
57:23     
for a p request so yeah that those are definitely the three     
57:28     
things that uh should work together which is the end goal of you know kind of the end of my project I would say was     
57:37     
uh yeah I think that was that your question or yeah I mean that was my     
57:43     
point kind of my point was that you know if you have like three minutes and you want to put a demo in there it's like     
57:48     
pick the things that are the most sort of visually s like if I show you the the     
57:53     
interface and there things going by that's interesting um it doesn't tell     
57:58     
you a lot but it's interesting and then you know if you have like a way to visualize the task but very quickly you     
58:06     
know you don't want to confuse people which can be happen if you put it together uh that that would be good too     
58:13     
and you know just remember that like you're going to spend a lot more time making the demo film it you know like     
58:21     
capturing the screen than to actually what you get out of it so like I'll do that when I give talks uh like for     
58:28     
conferences and record them I'll record them it takes like about two hours but it's like 10 minutes of content you just     
58:34     
have to like kind of keep practicing and and kind of fitting things in there and say What's the best way to present this     
58:43     
um and you know you just want to make sure that it's you know uh not like     
58:49     
people say why did you bother I am not trying to be mean but like it's just     
58:55     
like when you get have a demo and a talk people really want to get the payoff and     
59:01     
a lot of people have gimmicks too um you know like sometimes you'll have a     
59:06     
gimmick that maybe doesn't land well and that's you want to kind of avoid that     
59:12     
but it's just you know I think you could probably get something together for your project one     
59:19     
like yeah a rough sketch I had in my mind of like the whole I mean like the     
59:24     
three slides in three minutes so was thinking the first slide could be about like as you said right Orel has been     
59:30     
working on this project for like three Summers now yeah so maybe the first slide could just be a recap of the     
59:35     
different approaches we have tried um the second could that would be     
59:40     
like very short wouldn't want to spend more than like 30 seconds on it because not all of them are my project right and     
59:48     
then I was thinking the second slide could be like a some sort of a flow diagram of like with an introduction of     
59:55     
why I chose llms and then maybe you know for them to get an idea of how exactly     
1:00:01     
I'm using llms in it so you know introducing them to I have contributor agents and maintainer agents and I have     
1:00:07     
issues that these guys write and I'm using Auto Cod R so maybe try to present     
1:00:13     
all of that via diagram and then like once I kind of     
1:00:20     
tell them what I've done uh the demo would be like right at the end I     
1:00:26     
definitely think it'll take up like around one and a half to two minutes of the demo     
1:00:31     
itself uh the video I think I'm can try to squeeze it to one and a half uh but     
1:00:38     
yeah and then maybe you know there that could be like the pay of moment that you're talking about like how did I use     
1:00:44     
all these things that I talked about what is the result     
1:00:50     
yeah yeah yeah a rough flow I had if there are any inputs yeah I think that's     
1:00:56     
good yeah it kind of goes from the the big General to the specific and then um shom said in the chat maybe you     
1:01:04     
could have a to-do list which is good you want to have all your points kind of     
1:01:09     
like go through okay I want to have this this and this and then like get them distill them down to that 90 60 to 90     
1:01:17     
second window and     
1:01:22     
that's repit for the project     
1:01:29     
you meant like a to-do list maker kind of project or maybe you could already have a to list you know introduce some     
1:01:36     
issues into it and then your agents could the yeah the only thing is right     
1:01:41     
now the like what I'm trying to do I'm trying to keep the code as simple as possible without using external     
1:01:48     
libraries so like was usually definitely use some kind of like GUI Library which     
1:01:58     
yeah so getting an AI to understand a library would definitely be more     
1:02:04     
complex I try to avoid that for the demo that I wanted to go smoothly as much as     
1:02:10     
possible definitely something I could like explore calcor sounds really     
1:02:18     
good yeah I'll try to see if I can update the calculator to maybe include     
1:02:24     
like more the scientific functions and more things and then start introducing     
1:02:29     
the issues so I'll I'll play around with that and see if     
1:02:37     
that all right thank you Sarah thank you for that um Jesse is back I saw him come in and     
1:02:45     
out I was wondering Jesse could you share do you have access to your Discord the joepro Discord would you share your     
1:02:53     
screen on that uh yeah what what did you want to see I     
1:02:59     
wanted to see the behind the scenes uh Channel okay let me get my I'm just     
1:03:07     
opening up my laptop again give me a second here yeah so I I was noticing this channel     
1:03:16     
that Jesse has in in the joepro Discord I I almost want to call it like the     
1:03:21     
white boards Channel because I love white boards and I feel like that's     
1:03:27     
um a big part of my life well yeah yeah I noticed um but yeah let me okay I'm     
1:03:35     
almost there     
1:03:41     
okay I think I hope I'm at Cafe now but I um I think the noise is     
1:03:52     
okay all right um all right getting     
1:04:00     
there hopefully this is happening okay I think is it sharing uh     
1:04:09     
yes okay so here here's a general announcing stuff just everything we     
1:04:15     
already nothing new but the behind the scenes one is here um get rid of     
1:04:24     
this I close side um yeah uh what did you want to see     
1:04:30     
here just go through yeah go through some of the stuff here because I like the whiteboards you know you have some     
1:04:36     
things on whiteboards you have some things in here that are oh yeah I mean this is this is even     
1:04:43     
this first part I forgot I did this this is something I was trying to transfer over into giving like some of the     
1:04:50     
specific project stuff this is obviously from a while ago watch from last year um     
1:04:55     
um this is sort of where I'm going with it this is I think this is up now but a lot of this the design has changed and     
1:05:03     
it's still kind of a prototype for putting some of the projects up on the website so that's sort of like     
1:05:11     
old I guess this was only a month ago but to me this this this feels like it     
1:05:17     
was like last year um in terms of Designing the stuff and making like how     
1:05:23     
do you arrange the project uh so so this is in the work still U but looks very     
1:05:29     
different now um behind the scenes so what is the behind the scenes Channel     
1:05:35     
people don't know the server at all um it's sort of my current home base for     
1:05:41     
a lot of updates and things like that it's mostly really just announcements um and then I'm a little     
1:05:50     
I'm not even sure honestly with some of the working groups um having their own channels I might try to do threads or     
1:05:56     
something different like I still haven't figured out what I want to do there um and there's some old mentoring things     
1:06:02     
here that are not really active anymore and I might make a different thing for the mentoring in general but um so this     
1:06:10     
is quite influx and I haven't part of why I haven't mentioned it too much is because I'm once the structure is a bit     
1:06:16     
more set I will be overly overtly doing more things there but the behind the     
1:06:21     
scenes is sort of essentially behind the scenes look as all that is happening     
1:06:26     
um uh I'm quite curious about this we     
1:06:32     
actually had a a Nick week meeting today New York celebration women Computing but or this week I should say I didn't get     
1:06:39     
to attend uh directed because of the timing but um we are almost settled on a     
1:06:48     
venue which will it's sort of a prerequisite for doing like a call for     
1:06:53     
proposals or call for involement so that's good um this     
1:07:00     
whiteboard uh not a whole lot of fun things to say here but kind of for those     
1:07:07     
in involved in some of our reading groups you recognize the paper pyramids and this is this was sort of a a     
1:07:13     
reference for some of the mental health which I think even has a different like acronym NOW or whatever but this is sort     
1:07:19     
of an early um take on that we had discussion about     
1:07:24     
that about you know where where would some of the deliverables and outcomes go into that and and and it's     
1:07:33     
interesting because the mental health group is um like I know a lot of people doing     
1:07:39     
clinical work like clinical social work or or psychologist and and it's sort of like there's there's part of there's     
1:07:45     
sort of like theories and there's practice and one of the things to looking at is like how     
1:07:51     
how can there be Nuance to doing some of the actual of the work that level like     
1:07:57     
there's CVT but there's trauma or trauma focused CBT or culturally adapted CVT     
1:08:03     
there's variations on it and it's sort of interesting because that even came up yesterday um at at the earlier this week     
1:08:12     
at the meeting I mentioned earlier today uh because they're like oh     
1:08:17     
yeah enhanc don't like it um and I feel like     
1:08:23     
well there's a lot to say there but to move along     
1:08:31     
um I'll skip that for now um this is this is a big throwback to last year's     
1:08:38     
sck Wick um but this is this is a big cabor     
1:08:43     
of a lot of things with lar shaki who also um congratulations to I I meant to     
1:08:49     
push I haven't I didn't to push that to the main like medium but um she     
1:08:55     
published her thesis on um like liability and AI she's a law     
1:09:02     
student and she um but but before that you know Val     
1:09:07     
is like an OG original Society ethic Tech person uh who was way way before     
1:09:14     
even Way Way Back like four or five years ago uh she she was involved in     
1:09:19     
something so that's cool and then Jen is now part of what has become the mental     
1:09:25     
health group um and these are some old pictures from Avery and I we were in England     
1:09:30     
which was really fun times there and then one of the reading group pictures and Avery and I and Bradley were in     
1:09:36     
Chicago so that was very very fun time clasic Envision picture here uh so that     
1:09:42     
just I saw that again for a while I like oh that's great     
1:09:47     
um this book came um a blasting white     
1:09:52     
Mas is very much about um a very psychological take     
1:10:00     
on you could say uh history colonizer colon kinds of of things it's a very     
1:10:09     
poor description of it but I'm just going to keep moving to the channel for now     
1:10:14     
um this is about um adverse childood experiences and how they affect Health     
1:10:20     
uh so it's sort of a mental health thing but this came up in Jen's coursework um     
1:10:26     
what is this one oh this is the cognition Futures group     
1:10:32     
uh the updating the work I've had to bounce the the actual homepage for like     
1:10:38     
this fures around a lot and it's kind of set it's almost there um I'll show it     
1:10:46     
I can't I have to switch my screen in a little bit to show it um but like     
1:10:52     
getting an exra template for all the working groups to make uniform is     
1:10:57     
getting closer and closer and closer so I'm happy with that and then the the final     
1:11:03     
um the Whiteboard from this week U was really interesting because I bring in     
1:11:09     
like a classical clz uh quote which is like the people who are in Old School     
1:11:16     
like foreign policy international relations like security studies this     
1:11:21     
famous channel the 1700 or something thing and Wars politics through their     
1:11:27     
means but I was using it here in this interesting context of     
1:11:32     
um uh I think in this case this was I think this was gen stuff but um     
1:11:39     
discussing policy and how you know looking at it from a micro level of an     
1:11:44     
individual versus B A broader polish level of the system and and soort this there was a discussion about there was a     
1:11:52     
essentially a maladaptive practice of people getting into homeless shelters just to get Section A housing and we     
1:11:59     
looked at why is that happening as opposed to people like why can't people get housing they need in general     
1:12:05     
obviously housing an issue many sittings but just sort of like what is it that affects um people having these different     
1:12:12     
approaches to not being able to use the system as it's intended so yeah you probably can recognize the little the     
1:12:19     
egrt reference there and and uh like system and     
1:12:26     
War it's not picture but there's another discussion a little bit about like C regulations stuff there too um and you     
1:12:34     
know what happens when a system doesn't contain or afford all the means of resolving issues and regulation State     
1:12:41     
that's Can it can it be a good regulator but in in other states systems and human     
1:12:47     
systems are quite messy what happens and there's there's some examples here and     
1:12:53     
and some other pictures and stuff like that this is a super rire overview but I don't know if you have any any other     
1:12:59     
questions from this whiteboard or anywhere else in the channel to I can     
1:13:04     
address I think that's great I'm just I was just curious about you know what was going on there I think that's great to     
1:13:11     
have this sort of behind the scenes like Channel because it's like you know what's going on how does the sausage get     
1:13:19     
made you know um I think that's kind of an interesting I like when people people     
1:13:25     
give teasers for things they working on yeah and and I I I I'm like I said I'm     
1:13:31     
quite tempted to basically making the whole thing like I want like a white I would love to just have like the     
1:13:37     
Whiteboard Channel everybody like whatever you're working on just like take a picture of a whiteboard and talk about it because I find that that's     
1:13:44     
so I personally just enjoy it so much but I think it's quite useful too because we don't we don't those things     
1:13:50     
always uh there's so much information in     
1:13:56     
it's such a good like uh link or bridge to like some of the     
1:14:02     
the concepts that are harder to talk about um because I see the white oh yeah this like it's it's very it's a very     
1:14:09     
high retention for me and E to stuff but more so than that     
1:14:16     
um it's nice to see oh I forgot to say if people are interested in joining that I could put a link in it I haven't I     
1:14:24     
haven't been like promoting it because there just hasn't been like a bunch     
1:14:29     
of things for people to do yet um I'll put a link in the in the chat here     
1:14:35     
another place so I'm I'm still debating some of the     
1:14:41     
structure for like     
1:14:49     
um will will that server be a hub for communication about what's going on in     
1:14:54     
the working groups of the projects maybe and I'm not I'm not set on it yet but I     
1:15:01     
at least I'm set of like there is one channel for like news and links and stuff but I'm trying to also make it the     
1:15:08     
project the project channels are for project updates and I'm trying to make this a bit more project focused and get     
1:15:15     
people essentially incubate the projects off the ground and give people uh     
1:15:21     
especially people that are coming in or like in Jen's case Jen is like getting some project     
1:15:27     
experience with one of the projects in the health working grou like how do we get that up it's it's sort of     
1:15:35     
a it's it's a little bit more I guess project oriented um just because I I     
1:15:42     
think that's what's needed for for this right now um yeah it's in the works and     
1:15:49     
I'm happy to have like for like we kind of talked about rain rized stuff like     
1:15:54     
there could be I don't know if it's gonna be there could be a whole server to that so I don't know if I'm say oh     
1:15:59     
how's that the joer server not really be the best place for it but at least getting like a project description up on     
1:16:05     
there that I can reference and kind of put as a like almost like um like like a project on the media Labs     
1:16:12     
page for example that's sort of my my current reference point and it will at least be a     
1:16:18     
center uh or a central place hug to go to the other stuff that's happening in     
1:16:23     
space I think those are important that's that's that's the short and a long version of it right now yeah and     
1:16:30     
you were going to show the cognition Futures page yeah let me     
1:16:46     
um yeah it's it's getting there it's it's it's public but like it's not quite     
1:16:52     
how I want it to be it um so here's like uh a very familiar design for the     
1:17:01     
people doing this for I'm I'm I'm honoring by imitation some of the the     
1:17:08     
media lab but I have this set up here this fun stuff we scolls you know um and     
1:17:16     
then a lot of um uh things associated with it     
1:17:25     
like this is I might have to change how this filters out um like     
1:17:33     
the uh the Sorting of this it's mostly like it's these are all kind of     
1:17:40     
partially imported post but I got these I spent a lot of time trying to figure out how to do this the way that I like     
1:17:46     
it um with the tags and and everything else and the sort of in you know in     
1:17:53     
cognition futures for um this one is super this is this is     
1:18:00     
something that I'm just uh getting there but I think this would be a cool thing to have I basically just put     
1:18:09     
um I think this is from one of the this is from the website somewhere yeah uh     
1:18:14     
which is here oh oh it's not showing up     
1:18:23     
um yeah it's I a lot I pulled some stuff from here and basically took like the     
1:18:28     
Publications here yeah but for this I want to be like we don't to go to this now this is kind of a separate thing but     
1:18:34     
I'm curious what you want on this as like a project overview page from from like the phasic yeah well that's     
1:18:41     
something I'm gonna have to work on yeah it's something I I mean I haven't updated it in a while so maybe that's     
1:18:48     
something we can work yeah scrape some general stuff there um but to be you     
1:18:54     
know to be flushed out more yeah um but yeah this is this is kind of the     
1:18:59     
structure I'm going for for like a working a group I think it's it's okay it's getting there um any comments or     
1:19:09     
questions yeah I I like it I think it's great it looks like a very nice design     
1:19:15     
bringing all that stuff together like kind of in what you know like we have the the different websites and then     
1:19:21     
having this other front end where people can kind of get that information in the same place the reason     
1:19:29     
I do the uh you know the website separately is because they kind of have     
1:19:34     
their own flavor you know yeah and their own identity and then this would allow     
1:19:40     
us to have like a kind of a almost like a shopping mall for people who want to do a project they can see the parts yeah     
1:19:49     
yeah and that's that's what it's like on I'm not trying to I'm not fanboy the     
1:19:54     
media lab particularly it's just I've actually I looked at a bunch of um I don't know if I can show like     
1:20:03     
um like I've looked at a bunch like I've looked at like uh like Harvard Innovation lab not     
1:20:11     
because they're big name schools but just like what are people doing how are they like how are people organizing     
1:20:16     
their websites to cover this stuff and I like the media Labs the best so far     
1:20:22     
because they break it down into these different groups like this this to me is like     
1:20:27     
like like this just feels like it's like it's a nice website but I don't it kind of bothers     
1:20:34     
me like I can't really it's just like okay there's a bunch of stuff everywh and I'm not saying this is like     
1:20:42     
I'm not saying um you know this website is perfect yet     
1:20:47     
but I'm gonna get it to a place where um     
1:20:52     
it is sort of a a front a macro front end oops I'm sharing the wrong screen or     
1:20:57     
whatever um it's sort of like a macro front end and that way um people can get     
1:21:04     
to okay what what's what's at a high level here there's a bunch of things like Inda there things in or this thing     
1:21:11     
and some other like side groups and projects that are upcoming that I'm trying to do like the mental health working group is sort of its own thing     
1:21:19     
but like I'm happy to dub tail of that I may be getting like some advisors who are uh in the field like like people     
1:21:26     
doing social workers some like pychology people that would want to like serve as     
1:21:31     
Ser an advisor role to that space um and then other things like you know um stuff     
1:21:38     
with Twi and some other groups that are there and those are just the working groups too outside the mentoring stuff     
1:21:44     
that I want to do so it's sort of this um the website in and of itself is is     
1:21:51     
that sort of front like a macro landing page but then I I want to like help direct too oh what's what's phasic or     
1:21:58     
what's what's the you know what's I I haven't done it yet for like uh developmental brighten brick Vehicles     
1:22:04     
that' be a great thing to just put it in the spot and have it in the context of oh well that's part of oh I can I can I     
1:22:12     
can um I have one more thing I'll show um uh I just did I just did this one but     
1:22:22     
I think this looks pretty cool um uh     
1:22:28     
[Music] yeah is this showing everything     
1:22:33     
here I made representation right phenotypes too I think very fun to look     
1:22:38     
at yeah um     
1:22:44     
and I think I don't know where I pulled this from but this can be updated a     
1:22:49     
little bit I think uh but it ties to this it has the famous picture and then     
1:22:54     
it has a little bit of the alumni um a really basic applicant thing     
1:23:00     
um the group and the group website this is what I this is the thing I'm trying to get like I've got here you click on the group website it will go to the     
1:23:06     
actual page and that's like oh this like that's the goal I've trying to get can kind of see it in the context of all     
1:23:13     
these things here okay whatnot but um there's only there's only one thing here     
1:23:19     
that's this sort of incomplete thing there but it's it's you know that's     
1:23:25     
that's sort of a behind the scenes um things are in development in this way     
1:23:31     
so fine yeah that's great so yeah um     
1:23:38     
yeah well thank you Jesse for that overview of your behind the scenes in     
1:23:43     
Joe Pro and so let's move on uh Trevor are you there um     
1:23:50     
oh well bio archives I say thought I don't even know this will be my first     
1:23:56     
paper for PE revie so somewhat unrelated but that's it's a d Discovery thing and     
1:24:02     
so I'm not sure if anybody's interested but I can throw it up yeah do you have a     
1:24:07     
link or put it in the chat I'm sure yeah I'll throw in the chat it just got     
1:24:13     
approved this morning so it's pretty fresh okay yeah all right Z I'll put     
1:24:18     
that link in the chat then there's his bioarchive paper Trevor mentioned     
1:24:23     
something a couple weeks ago I'm going to uh kind of go into a little bit more     
1:24:29     
detail on he mentioned that Von noyman uh actually had a different type of sort     
1:24:35     
of vision for computation aside from the Von noyman architecture for modern computer     
1:24:42     
so there's some I I brought up some papers on Von neyman's couple of oscillators so you know we think about     
1:24:49     
the brain as like having you know be having Action potentials and having these and things like that and so you     
1:24:56     
can model neurons as oscillators and then of course you can model groups of     
1:25:01     
neurons as sort of these coupled oscillators there are different types of oscillator models in uh Neuroscience     
1:25:08     
that are used uh in like theoretical neuroscience and in computational     
1:25:14     
Neuroscience so you have these different oscillator models um but vanon noyman actually thought about this in a certain     
1:25:20     
way so that's what I want to talk about uh so this first paper is on coupled     
1:25:25     
oscillators for computing a review in perspective and so you know as opposed     
1:25:31     
to Something Like the connectionist Model you have these coupled oscillator models which are like     
1:25:38     
neurons represented by an oscillator and then those oscillators being coupled     
1:25:43     
into a network so that one effects one oscillator affects another oscillator and you can have these Cascades across     
1:25:50     
neurons Cascades across the network and it affects the phase of the osc     
1:25:55     
so if we're you know we're talking about an oscillator you know we have to kind of think about what it is and so an     
1:26:01     
oscillator is basically um something that oscillates according to a sine wave     
1:26:07     
so if we have like this graph here this is the zero     
1:26:12     
point and there's an oscillator you know we draw sine wave so a sine wave has two components     
1:26:21     
it has the positive component and the negative component on it and this is a one F uh one one Hertz of a sine wave     
1:26:32     
and the sine wave basically has a negative component positive component and it keeps fluctuating like this and     
1:26:38     
so that's what they mean by oscillation and so you know this is something you can use to model a neuron     
1:26:45     
an action potential but of course if you have a network of oscillators say if you have like you know a couple of     
1:26:53     
oscillators and a network if this network is oscillating     
1:26:59     
you know there's an oscillator here there's an oscillator     
1:27:04     
here and there's an oscillator here and the idea is that this     
1:27:10     
oscillator might impact this oscillator it might push its phase in a different     
1:27:16     
direction this oscillator might affect this oscillator by sort of changing its f     
1:27:24     
there are different ways you can affect oscillat so that's what we're talking about and of course if you had a network     
1:27:30     
like this and you changed the you know you pushed around these oscillators through the interactions you can end up     
1:27:37     
with some pretty interesting Dynamics so all this will be represented as a dynamical system where there's some sort     
1:27:44     
of uh you know face trajectory and it gives you a very different view of the     
1:27:50     
brain than something like um a connection model or a bon noyman     
1:27:56     
architecture where there's you know an input a linear input output or a set of     
1:28:02     
linear outs so this is couple of the oscillators for computing or reviewing     
1:28:07     
perspective this is under brain inspired Electronics this is like this area where     
1:28:12     
we're looking at brain you know uh you know neural inspired     
1:28:18     
architectures of brain inspired architectures and so you know I imagine that this was quite hard for Von noyman     
1:28:25     
to realize in his lifetime so we ended up with the Von noyman architecture which is very implementable at least     
1:28:32     
according to like 20th century rules of Technology but you know these kinds of     
1:28:38     
architectures are sort of up and coming neuromorphic devices brain inspired     
1:28:43     
Electronics nonvolatile memory Technologies um you know other types of     
1:28:50     
things and these really deal with building circuits and you know uh doing     
1:28:55     
things much like a neuron would do instead of like what we expect from a bonan architecture or connectionist     
1:29:02     
architecture so this is the coupled oscillators for computing paper um this     
1:29:09     
kind of goes over how what couple coupled oscillators are and their uh     
1:29:14     
significance so coupled oscillators are highly complex dynamical systems and it     
1:29:19     
is an intriguing concept to use these oscillator Dynamics for computation     
1:29:24     
the idea is not new but it is currently the subject of intense research as part of the Quest for Beyond more electronic     
1:29:32     
devices so one of the things that's beveled sort of the Devon noyman     
1:29:38     
architecture is Mo's law and so Mor's law is where you know as we build more     
1:29:45     
powerful computers we're shrinking down the S the feature size on of the uh transistors     
1:29:53     
and so as transistors get smaller they become more powerful but you you can     
1:29:59     
only shrink them down to a certain size before you start getting Quantum effects     
1:30:04     
and so we have you know people have kind of we've kind of reached more the limit of mors law today     
1:30:12     
uh people have kind of come up with very uh innovative ways around it around the     
1:30:19     
limit but you know this is something that we have to think about so there are people who are researching these     
1:30:25     
Alternatives as a way around mors law there are other like more practical ways around mors law more expedient ways     
1:30:32     
around but this is the sort of the driving force for some of these alternative computational     
1:30:38     
models uh to all large extent these efforts are motivated by biological observations neural systems and mamalian     
1:30:45     
brains which seem to operate on asator signals so they're looking at sort of a     
1:30:51     
Mamon based brain um and that's that's kind of where they're going with this in     
1:30:57     
this paper we give a survey of oscillator based Computing with a goal of understanding its promise and limitations for the next generation of     
1:31:04     
computing our Focus will be on the physics mostly nanoscale oscillatory systems and on the characteristics that     
1:31:10     
may enable Effective computing so they get into this uh they have a table of     
1:31:16     
contents here they talk about Von nyman's oscillatory computer they talk     
1:31:21     
about oscillators for these kind of computers the coupling of oscillators so this is     
1:31:26     
where I showed in the network where oscillators can affect one another they     
1:31:31     
can also be coupled and synchronized so you know they can all be synchronized as sort of at resonant     
1:31:39     
frequencies so that they actually produce a you know sort of a super additive output or you know consistent     
1:31:47     
output there are all sorts of different outputs that result from these kind of interactions     
1:31:54     
uh then you can do Computing with oscillator Dynamics so there's something called Collective State Computing uh     
1:32:02     
internet connections Define the network function you can actually build an oscillatory hope field Network which is     
1:32:08     
a type of uh Network spiking Network that they build and then models of for     
1:32:14     
aitor Collective State computer U and then they do these case studies where they do benchmarks on onedimensional     
1:32:21     
time sequences some image processing gate control and pattern generation and     
1:32:28     
then working with combinatorial and then they do some Quantum hard problems in a neural     
1:32:34     
network so this is interesting uh what I wanted to point out in this article is going down to you     
1:32:42     
know the ideas that on noyman had so historically the idea of OBC dates back     
1:32:48     
to Von neyman's 1954 patent which is here and his concept which is here is an     
1:32:55     
early and still very relevant example of OBC the scheme uses phase the phases of     
1:33:01     
oscillator signals to realiz Boolean digital computation Noosa serves as a perfect example on how one can translate     
1:33:08     
a level based Computing scheme with phase frequency based representation so you know you have     
1:33:15     
these oscillators and these oscillators are continuous signals and the idea is you want to take these continuous     
1:33:21     
signals and turn them into digital signals so a digital signal is where you     
1:33:26     
have a zero or one so basically your oscillation isn't a curve it's a square     
1:33:33     
thing that's like this and so you have to characterize this oscillation as a square and so the     
1:33:40     
idea being that this is a state of zero this is a state of one and that there are these you know it's basically a     
1:33:47     
binary system so the output is binary so when the phase is negative it's zero     
1:33:52     
when the phase is positive it's one and then you know these interactions are affected likewise the frequency the     
1:33:59     
width of the frequency band is going to depend on the the width of the frequency     
1:34:04     
band this oscillator so you can have you know quick transitions between Z     
1:34:12     
one kind of like this so it be Z one     
1:34:18     
z0 that sort of thing and so you have these you know lengths of time where the     
1:34:24     
state is in a where the system is in a certain State and you know it's variable     
1:34:29     
depending on the the the frequency here     
1:34:34     
um going back to this paper uh the so uh for this reason we     
1:34:42     
start by reviewing this concept in section two along with more recent proposals that resurrect the ID now the     
1:34:49     
attractiveness of this OBC this oscillator based computing largely hinges on finding a suitable oscillator     
1:34:56     
as a building block of the computer one may use electrical oscillators and even standard fabrication friendly seos Serv     
1:35:04     
transistor action however is not at all required to every oscillator type and so     
1:35:10     
the field is widely open for using emerging devices or possibly non-electric variables obcs reliz with     
1:35:18     
nanoscale highly efficient oscillators of the potential to yeld truly revolutionary devices     
1:35:24     
we argue that the physical realization of the oscillators is pivotal for their success and then they have a section on     
1:35:31     
the physics of emerging Nano oscillator devices so you can implement this in a     
1:35:36     
nano device you can imp you know so you can't necessarily use a vment circuit to     
1:35:42     
do it but you can use this do this with various types of uh physics and physical     
1:35:48     
systems that you can use in Li of that uh type of circuit so Computing in obcs     
1:35:55     
occur by oscillator interactions more specifically by oscillator synchronization so it's synchronizing     
1:36:02     
the oscillators at the same frequency which is the key to OBC and and having a     
1:36:09     
coherent output this is similar to what we see in the brain by the way so this is kind of the idea that Von noyman had     
1:36:15     
this was back in the 50s so you know he was kind of this is why of course we not realize this because it was kind of     
1:36:21     
ahead of its time uh one of the most promising applications for OBC is that they may be     
1:36:27     
used as Hardware accelerators and AI Hardware uh in algorithms a vast     
1:36:33     
majority of computing power is spent on performing simple repetitive calculations such as calculating dot     
1:36:39     
products convolutions applying nonlinearities and recognizing or matching simple patterns it is quite     
1:36:47     
possible that Boolean Coss based circuitry is suboptimal for doing these tasks so the kind of stuff that we do     
1:36:53     
with Boolean uh computation which is binary computation and Coss     
1:36:59     
circuitry uh is not necessarily the best way to do this so for this reason deep     
1:37:04     
learning algorithms and convolutional neural networks became major drivers for seeking out new possibly non Boolean     
1:37:12     
Hardware uh so this is just gives it this paper also gets into this and how     
1:37:18     
this might be done so this is a good paper for like kind of an overview of so     
1:37:23     
of recent progress in this area and kind of what but not necessarily what Von     
1:37:29     
neyman's Vision was um this paper is on coupled oscillator networks for Von     
1:37:35     
noyman and non-von noyman Computing so this talks about uh sort of Von noyman     
1:37:42     
Computing and non Von noyman Computing which includes Von nyman's coupled     
1:37:47     
oscillator model uh so the abstract of this paper reads the frenetic growth of     
1:37:53     
the need for computation performance and efficiency along with the intrinsic limitations of the current of the     
1:38:00     
current main Solutions is pushing the scientific Community towards unconventional and sometimes even exotic     
1:38:06     
alternatives to standard Computing architectures this is the same point made in the other paper where you have     
1:38:13     
mors La we reaching the sort of the limits of miniaturizing surfit and so we need to have a new type of computer that     
1:38:21     
has sort of a new regime of computing power something we can do maybe at the     
1:38:26     
quantum level or the Nano level Something exhibits uh Quantum     
1:38:32     
effects but also something at the you know the micro level micro scale and so     
1:38:38     
forth uh in this work we provide a panorama of the most Rec relevant Alternatives both according and not the     
1:38:46     
Von lman architecture um so this means that you know some of these options are     
1:38:52     
sort of based on the one now in architecture some are not highlighting which are the classical challenges such     
1:38:58     
as Energy Efficiency and or computational complexity they are trying to tackle so some of these kind of     
1:39:04     
computing paradigms are uh based you know on making things energy efficient     
1:39:11     
so if you have like say a computer for some nanotechnology device you know that     
1:39:18     
computer needs to be highly energy efficient and it also needs to account for qu effects so you need to have this     
1:39:25     
focus on Energy Efficiency you might have a processor that could be you know just something that is decoupled from an     
1:39:34     
energy source that also needs to be energy efficient sometimes if you're doing things for like AI applications     
1:39:40     
computational complexity might be your focus since then that might be something that you focus on so people have     
1:39:47     
developed a lot of Alternatives so they're talking here in this paper about     
1:39:52     
alter atives based on networks of weekly coupled oscillators and so this was introduced by uh goto and Von noyman in     
1:40:00     
the 1950s and is recently regaining interest with potential applications of both Von     
1:40:06     
noyman and non Von noyman types of computing again the vanon noyman type of computer is not the the oscillator model     
1:40:14     
presented here by Von noyman but the V noyman architecture uh in this contribution we     
1:40:21     
present a general framework based on the phase equation equ derived from the description of nonlinear weekly CED     
1:40:26     
oscillators especially useful for computing applications we then use this formalism to design improve the working     
1:40:33     
principle and stability assessment of Boolean Gates such as not and majority     
1:40:40     
that could be potentially employed as building blocks for both Von noan and nonv ares so they introduced some     
1:40:48     
interesting things here they talk about uh this framework by goto and Von noyman     
1:40:54     
they talk about how that might be used to build these computers that are very     
1:41:00     
different from the bond traditional bonoan architecture then they talk about some     
1:41:05     
of these new uh you know Boolean Gates that they've kind of discovered this is     
1:41:12     
something you see what in Quantum Computing where people are building so basically a logic gate is where you have     
1:41:18     
two inputs and then you have one output and you have to sum or you have to make it decision on those out uh outputs so     
1:41:26     
two in you know two inputs might be integrated we say like an and so if you     
1:41:33     
have two inputs and they're both of the same state then you get an output if not     
1:41:39     
you don't get out so it looks something like you know the traditional sort of and gate would be where you     
1:41:48     
have so the traditional and gate would be something like     
1:41:54     
where you have two inputs     
1:41:59     
this and they go into this bank bank is an and gate so it only lets     
1:42:06     
through things where both of these states are zero but both of these states     
1:42:11     
are one and so then the output is maybe one and if the if this these inputs are     
1:42:18     
mixed then the output is zero because it's not sa doesn't satisfy project so     
1:42:24     
this is the way to transform inputs into outputs using different rules and of     
1:42:30     
course you know some people have modeled neurons in this way where you know you have a bunch of neurons that kind     
1:42:37     
of synapse on on some uh location and you know they they kind of     
1:42:44     
have these sum summarization words so this is uh again another electrical     
1:42:50     
engineering paper uh they talk about the vanoyan architecture being kind of reached this     
1:42:58     
so we of course reached the vanoyan bottleneck uh which is that the system     
1:43:04     
throughput is limited by the data transfer between CPU and memory so in in a Von noyman architecture you have this     
1:43:14     
uh not only have this problem with moris law but you also have this vment bottel and this is where you have this limit of     
1:43:21     
data transfer between CP in memory uh we've kind of we've overcome     
1:43:28     
that in some ways with gpus and this is why gpus are used in in a lot of AI     
1:43:33     
because uh gpus are actually distributed architectures that have overcome this     
1:43:39     
limitation however you know having other ways to do this to deal with these kinds     
1:43:44     
of limitations of the vond architecture are important so they propose you know     
1:43:51     
that we have this sort of uh coupled oscillator model and kind of as a specialized     
1:43:59     
computational uh platform so yeah they kind of talk about     
1:44:04     
applications to artificial intelligence they talk about neuromorphic Computing     
1:44:09     
especially spiking neural networks so these are things that kind of give us a different sort of uh way to do     
1:44:18     
Computing uh they're actually these non-computing paranid or non touring     
1:44:23     
paradigms which actually are you know we've talked about this when we talked about physical computation last year we     
1:44:31     
have a medium post on the physical computation conversations like for Trevor that might     
1:44:37     
be very uh enlightening because we did Cover a lot of ground in those     
1:44:43     
discussions from like philosophy to you know uh Computing hardware and computer     
1:44:50     
science and and Neuroscience and between so we we did talk a lot about this um     
1:44:57     
and some of these things so this is actually interesting here they talk about mem Computing or memor Computing     
1:45:05     
this was introduced as a non-t paradigm represents the most idealized model of a computational me it can be realized in     
1:45:12     
analog or digital form its most effective realization is through FY and architecture is called self-organizing     
1:45:19     
Gates this is talking about what these logic gates and these these rules for logic gates such as the and     
1:45:27     
gate and so in this case you have these networks that self-organize these kind     
1:45:33     
of gates so the working principle of these Gates is as follows they are designed to reach an equilibrium such     
1:45:39     
that the terminal states are consistent with some prescribed relation for     
1:45:44     
example self-organized ising logic dates reach an equilibrium when their terminals satisfy a prescripted set of     
1:45:51     
BU relations uh they accept a superposition of input     
1:45:56     
and output signals at each terminal this allows to assemble self-organizing circuits by interconnecting     
1:46:02     
self-organizing gates with controllable properties of the Dynamics so this is     
1:46:07     
something that has been used to really or is really optimized in solving     
1:46:13     
problems that are combinatorial and dealing with computational complexity so these logic gates you know you have like     
1:46:20     
this and gate which is a very simple gate which you can also have Quantum Gates which have uh different properties     
1:46:27     
and you know the idea is that these Gates self-organize within the network so it's an interesting kind of approach     
1:46:36     
um so this is the part here where they talk about these coupled oscillator models of vono and I guess uh goon vono     
1:46:46     
so um the Quest for alternative non-conventional Computing Solutions     
1:46:51     
just recently revive the use of oscillators as building blocks for V both Von noyman and non Von noyman     
1:46:59     
architectures they were origin initially introduced independently by goto and Von noyman so this was actually something     
1:47:05     
that was not necessarily a collaboration I guess but it was like I don't know if     
1:47:11     
they talked to one another on this but uh we'll look at the papers in a minute but this is basically the goto and Von     
1:47:19     
no I want to be fair historically this was back in the     
1:47:24     
1950s the idea in this case is to encode information in the relative phase among     
1:47:30     
different oscillator so you're looking at the phase of each oscillator and then by means of a proper     
1:47:36     
coupling use them to perform basic operations such as the not or majority functions so these are in 54 to 57     
1:47:44     
actions so these different functions these different logic types of logic gates are actually from loto and Von     
1:47:51     
noan where they uh do these sort of this sort of collective processing of different     
1:47:58     
oscillators in the 1960s machines called uh parametr implementing the goto design     
1:48:05     
was built in Japan so this is actually in Japan they've been following up on this in the 1960s this is in 54 and     
1:48:13     
55 parameter uh parametr saw some success however they soon were eclipsed     
1:48:20     
by digital computers explaining the first gener eration of integrated semiconductors today their interest is     
1:48:26     
renewed not only because they are many other there are many other modern and more compact ways to integrate     
1:48:31     
oscillators ranging from ring oscillators to spin torque and Laser based structures and Beyond so you know     
1:48:39     
in the interim between the time that this was introduced in the 50s and there were some uh cursory experiments in     
1:48:47     
Japan with you know building machines using this principle we had a lot of movement in physics in terms of     
1:48:54     
understanding oscillators so you know of course there's the classic caroto oscillators which was also developed in     
1:49:00     
Japan but they also you know uh there in phys in physics there was a lot of work     
1:49:07     
on oscillators ring oscillators spin torqus laser based structures that     
1:49:12     
became sort of you know uh they were physical tools they were uh dynamical     
1:49:19     
systems tools but they also were able to uh perform computations so so I would     
1:49:26     
like to go down to these papers 54 through     
1:49:31     
57 and so this is uh okay so this is 54 here uh go to new parametr circuit     
1:49:40     
element using nonlinear reactants and this is a very obscure     
1:49:46     
venue uh in 1954 so this is one of the first papers this second paper is the     
1:49:54     
parametr a digital Computing element which utilizes parametric oscillation so     
1:50:00     
this is proceedings of the IR this might be available this was in 1959 so this     
1:50:06     
was in the 50s uh I'm assuming that maybe they didn't talk to one another maybe this     
1:50:12     
was happening in Japan independently I'm not sure of the uh History of Science     
1:50:17     
here but it'd be interesting to find out more uh this is Von neyman's work in the     
1:50:23     
same area uh nonlinear capacitance or or inductance switching amplifying in     
1:50:29     
memory organs this is a patent in 1954 and then this I guess this was     
1:50:37     
uh waggington A New Concept in Computing this is in proceedings of the IR this is     
1:50:43     
actually 1959 this is maybe covers vman's work maybe goto's work as well so     
1:50:50     
the summary here is that goto and V when were developing this in the 50s maybe in     
1:50:55     
the 60s they implemented some of this and then you know this was kind of lost     
1:51:01     
history during which time you know the sort of the Von noan architecture ruled     
1:51:07     
but physicists were doing work with uh oscillators a couple of oscillators and     
1:51:13     
then of course now there's this renewed interest with memoris offf Computing     
1:51:19     
with spiking uh neural networks and then now with this need for new models of     
1:51:26     
computation this uh vanon and bottleneck     
1:51:31     
which is the link between uh you know different parts of the architecture gpus kind of solve this     
1:51:39     
problem by uh Distributing the problem on Parallel cores but you you still have     
1:51:45     
a fundamental problem not only of this communication bottleneck but of the size     
1:51:52     
and performance bottle so that's all we have I have on Von nyman's coupled     
1:51:59     
oscillators and let's see if we have some things here so this Trevor's     
1:52:04     
preprint and then Jesse says I might have to go soon but I'm very interested in the different architectures I think     
1:52:10     
we might talk about that more in the cybernetics reading group yeah I think that would be a good thing to dive into     
1:52:16     
especially the history of science there in the cybernetics reading group see what that you know how that kind of     
1:52:23     
follows through to the present day and maybe some of the connections of cybernetics so I'm sure that like     
1:52:29     
especially Von Wayman had some interesting ideas about cybernetics but also some of these Concepts that were     
1:52:35     
floating around the time and got kind of lost to     
1:52:45     
history I was curious you you you mentioned that you have some recorded talks that talk about like philosophy     
1:52:52     
and things are those available online yeah so we have um a lab medium and that lab     
1:53:00     
medium has uh there's a post from about a year ago on physical     
1:53:07     
computation and we had a set of discussions in this meeting on physical computation uh ranging from sort of the     
1:53:15     
philosophy of it to the uh electrical engineering to the computer science and     
1:53:21     
we we so I have I can send you a link to that in the slack we you know that just     
1:53:27     
kind of goes over a lot of those discussions but then we also have worked uh separately on a series the     
1:53:33     
cybernetics reading group which actually is where we take some readings in classic cybernetics but also some     
1:53:39     
readings in the philosophical literature and the technical literature bring them together so um you might be interested     
1:53:48     
in those things um yeah they sound really cool um I was     
1:53:55     
also going to ask the for the first paper you mentioned um there were there was a section there about the comen     
1:54:01     
tutorial problems and I don't know if you had anything that you could expand on that I always curious what particular     
1:54:08     
types of problems people are proposing for these architectures um I don't know if that I'm not sure if any of the     
1:54:14     
papers talk about like well I guess the first one maybe it is let's see if we can go back to that um I'm not sure what     
1:54:21     
they were doing in this paper they well they had Quantum hard     
1:54:28     
problems they had uh yeah this is on page 14 so why don't we go to 14 to     
1:54:34     
[Music]     
1:54:40     
see case studies okay this one here so let's go into the zoom into     
1:54:48     
the oscillators for combinatorial problems so combinatorial problems can often be restated as energy minimization     
1:54:55     
or optimization problems so combinatorial problems are things you know like games where you have a lot of     
1:55:02     
uh strategies that you want to play in a in a set of options like chess you know     
1:55:08     
you have search problems which are combinatorial problems basically where you have a lot of possible outcomes for     
1:55:16     
something so that's that's and then you can restate those as minimization or optimization problem     
1:55:23     
so one of the points they make here is that hopefield type networks were successfully used to solve combinatorial     
1:55:29     
problems and that showed and hopefield networks are sort of these I don't know if you want to call them bi biologically     
1:55:36     
inspired uh networks I guess compared to like connectionist networks they are because they have some rules for like uh     
1:55:44     
Action potentials and things like that um in thresholds but these are you know     
1:55:51     
networks where you can solve one of the benchmarks of these combinatorial problems so you can actually take     
1:55:58     
combinatorial optimization problems then and reformulate them for oscillatory     
1:56:03     
devices so one of the things they point out here is the graph coloring problem so this is where you have a graph which     
1:56:10     
each part of the graph is a different color and you want to make sure that you know you don't have color the same color     
1:56:17     
adjacent one um and so that's that requires like a search of all possible coloring     
1:56:25     
sequences and getting one that does satisfies the criteria so to our     
1:56:30     
knowledge woo and woo at all are the first to propos oscillators for graph coloring problem so that's citation 136     
1:56:37     
and 137 in this paper um the basic idea here is to identify oscillator phases with     
1:56:44     
colors so you have the phases of the oscillator you associate with those with those with colors and to use the fact     
1:56:51     
that resistance coupling tends to pull phases or colors together and capacitive     
1:56:57     
coupling tends to push phases or colors away from each other so you have resistive and capacitive     
1:57:04     
coupling of these oscillators and this has the action of pushing or pulling     
1:57:09     
these phases together or away from each other that's how they describe it and I     
1:57:14     
don't know what that looks like I mean you know I'm not going to diagram it out but you know I guess you can get a sense     
1:57:21     
of what what they're talking talking about uh it is not hard to see then that the Dynamics of inphase and outof phase     
1:57:28     
synchronizing oscillators Maps the solution of a graph coloring problem where the oscillator interconnections     
1:57:35     
directly correspond to the graph edges a more General approach is shown in uh     
1:57:40     
reference 23 together an implementation using vadium oxide based relaxation     
1:57:46     
oscillator you're actually using an oscillator a physical oscillator and the     
1:57:52     
approach used in refs 23 and 82 which uh different references here     
1:57:58     
the graph coloring problem is first formulated to finding an ordering of the nodes on a phase Circle such as such     
1:58:06     
that the same colored nodes appear pair close together in the order but are not connected by a graph Edge so basically     
1:58:13     
you have a ring of nodes that colors appear close together in the in the sort     
1:58:19     
of ring but they aren't necessarily connected by an edge so it's it's basically you know sorting out nodes by     
1:58:27     
their color and then in contrast unlike color nodes so nodes of different colors may     
1:58:34     
share the same graph Edge but they are ordered to have different phases or     
1:58:39     
colored in this fashion a combinatorial problem may be reformulated into an     
1:58:44     
energy minimization or optimization task that can be implemented by a network of coupl oscillators so we have these     
1:58:52     
different ways of doing this kind of graph coloring problem and you know these are these combinatorial problems     
1:58:59     
tend to be NP hard or NP complete meaning that they really you can't get     
1:59:04     
an exact solution uh using you know in any reasonable amount of time or sometimes     
1:59:11     
if it's MP complete an exact solution doesn't even exist you just need to approximate the best possible solution     
1:59:18     
so you know efficient Solutions of these kind of problems usually aren't achievable with vman architecture     
1:59:27     
but you know with some of these non-conventional Computing architectures it may be that you can solve these kind     
1:59:33     
of NP hard or NP complete problems with those kind of architectures so you might     
1:59:38     
be able to solve a graph coloring problem exactly using an     
1:59:43     
oscillat or you may not but you may get a better actually get a better answer with the oscillated model that's at     
1:59:50     
least the hope so that's the kind of things you're talking about with amatorial problems     
1:59:56     
and there are other types of benchmarks as well where they're looking at um you     
2:00:01     
know different ways to implement that on an oscillator     
2:00:07     
computer thank you appreciate that yeah I don't know Morgan had anything to     
2:00:13     
say about it or usually     
2:00:20     
does yeah yeah wow I I've just been thinking about     
2:00:26     
these things and going over old um or you know latest Adam Adam mat SE papers     
2:00:34     
oh yeah but you know     
2:00:39     
um not so much you know kind of focused on     
2:00:46     
the yeah just the the slime molds and oh yeah there's there's a grad studor just     
2:00:53     
finished up at UC Santa Cruz that did simulation work of slime     
2:01:02     
molds yeah which I thought was interesting um kind of in a yeah     
2:01:10     
slightly different direction than it he was a little bit more interested in     
2:01:17     
um uh like novel means to create     
2:01:26     
structure um isn't it interesting Department there called computational     
2:01:32     
media oh yeah I've heard of this yeah yeah yeah and um anyway but um but yeah     
2:01:40     
I mean you know I I I find it fascinating you know certainly kind of more been looking     
2:01:48     
at the um     
2:01:54     
well like I posted recently and this this might have been on the our     
2:02:00     
neuromorphic Revolution Facebook group but um uh you know there's a a good     
2:02:08     
Reservoir Computing kind of Workshop that's coming up um I might be going on right     
2:02:16     
now um no I think it's next week um anyway but just the     
2:02:22     
you know those are different compute architectures yeah um but they're you     
2:02:30     
know tightly coupled to kind of computational Neuroscience models right     
2:02:37     
yeah although yeah well the sorry that that     
2:02:43     
would be the neuromorphic Computing in general right right and then Reservoir Computing is     
2:02:49     
interesting which I I think you kind of touched on at least a couple of     
2:02:54     
those alternative architectures because they get used in kind of physical     
2:03:00     
Computing systems right uh and of course that's the one that's     
2:03:07     
been used by organoid intelligence people right     
2:03:13     
right um but you know to to me that's a you know     
2:03:20     
it's almost a defeat I mean in the sense that like you     
2:03:26     
know if it can't be uniquely done by well I mean I don't     
2:03:33     
know yeah it it's it's certainly it's certainly not the um the     
2:03:39     
Breakthrough that we're hoping for right yeah but I but I think you know at the     
2:03:45     
same time I was about to say something silly like you know we're looking for things that can be kind of done uniquely     
2:03:53     
by computer by by biology or something like that and and that might be again     
2:04:00     
like you know if if Adam ad maty and has taught us     
2:04:06     
anything you know that there are you know there are alternative ways of doing     
2:04:13     
almost any of this stuff yeah the the question is whether it's you know that     
2:04:18     
doesn't mean that it's efficient or you know know it's not necessarily on the time scale that you want but but all     
2:04:26     
sorts of you know Goods you know good approaches to computational or uh     
2:04:33     
combinatorial problems can be accomplished by by all sorts of by all sorts of     
2:04:39     
systems yeah yeah and um yeah anyway     
2:04:45     
it's it's uh super super interesting yeah I was going to say that     
2:04:52     
like you know we think in terms of benchmarks often but nature doesn't     
2:04:57     
really think in ter I mean I guess you know there things that organisms need to do and problems that it needs to solve     
2:05:04     
but like it's not the same way we think in Computing about benchmarks and how to     
2:05:09     
implement those so it's really interesting and as some of these alternative systems of course Andre     
2:05:15     
adomat he does a lot of stuff with slim mold but with other kinds of organisms it's really interesting kind of     
2:05:22     
unconventional Computing that he does but yeah I mean that's that's great stuff um you know I     
2:05:30     
yeah yeah I was just gonna say that you know the again     
2:05:39     
like I mean sorry this this is something that kind of related back to when you     
2:05:44     
were talking about um uh structural elements I think in D.A     
2:05:52     
you know and I was wondering if you saw the that builda cell Talk from     
2:05:59     
University of Utah no I don't think so uh I think that     
2:06:05     
was the most recent build to build a cell CER and     
2:06:11     
um but but as it directly relates in Computing     
2:06:16     
the um just the the kind of computing that's happening in     
2:06:22     
Gene regulatory num and just just thinking about the kind of     
2:06:30     
intra you know this single cell computation all right yeah and and I     
2:06:38     
don't know if that's necessarily well I think that's kind     
2:06:43     
of part of um say Michael Len's you know     
2:06:49     
mind mind everywhere um but just how much I mean so I brought up     
2:06:56     
the acting or you know I thought of that because I saw another one of these silly     
2:07:01     
you know Quantum process or Quantum     
2:07:07     
Consciousness papers but like but like from molecular biology right like and     
2:07:14     
you know it's always interesting where he's just like okay what's the quote evidence of you know Quantum conscious     
2:07:21     
or something like that and and you know it was another of these like     
2:07:29     
well anesthesia seems to have some like     
2:07:34     
like somehow anesthesia is interacting with micr tual or something like that I     
2:07:40     
know what you mean yeah I think I've seen this graph where well it's a new one it's a new one right like like but     
2:07:48     
at the same time you know again it just it it's um you know when we're watching     
2:07:53     
that um that like single cell animal you     
2:07:59     
know reaching out in like you know kind of human real time and and getting stuff     
2:08:05     
right yeah it's just like like like we so still don't fully understand the     
2:08:13     
intracellular intelligence and and and you know non- neural processing that's     
2:08:20     
going on in the cell yeah and and you know that it's it's a big stretch to go     
2:08:28     
from like you know like an anesthesia anesthesia is is interacting with     
2:08:34     
microtubules which again if you see this build a cell thing just like they're being used for all these activities     
2:08:41     
right like you're you're talking about kind of like the highways you know in some ways like the highways of the cell     
2:08:48     
right and it's just like well of course they are like you know the jump to like therefore     
2:08:55     
Hammer off is right about or you know big     
2:09:01     
bigly molecular standpoint of of just how much how much you know like for yeah     
2:09:08     
I don't think there's a better word for but computation going on     
2:09:14     
so and um in in or intracellularly yeah yeah     
2:09:23     
and yeah yeah can I just add something to this yeah go     
2:09:28     
ahead um so there's there's another example because I know the hammer off anesthesia example you're talking about     
2:09:35     
there's another one involving um isotopes of lithium that I think is     
2:09:40     
often used as the justification for the um Quantum effects likely being in the     
2:09:46     
brain so I'll see if I can find that one and send it along just in terms of uh     
2:09:52     
like lithium action lithium neuronal action or or like like lithium action on     
2:10:00     
kind of humans um so I think the studies uh are     
2:10:06     
applicable to humans but the the justifications have been conducted out like in preclinical rodent models but um     
2:10:14     
the as it turns out the um behavioral effects of lithium are dependent on the     
2:10:19     
isotope and that that that is an unexpected result so oh that's     
2:10:25     
interesting um yeah yeah yeah please please um if if you find a if you find a     
2:10:32     
link for that drop it into competation of Psychiatry for sure I'd be interested I     
2:10:38     
I saw good I mean this is going back a ways     
2:10:44     
um go this could be like even five years ago now excuse me but a really interesting     
2:10:51     
paper on uh you know mole like molecular     
2:10:57     
consequences of lithium action that that was the first one where     
2:11:03     
I was just like oh wow this is a this is a really     
2:11:09     
um this is a lot more kind of mechanistic detail about drug     
2:11:17     
action than than we we usually see um and that was that was you know     
2:11:25     
because again like like I think lithium is one of those drugs where we're still not quite really really sure why it is     
2:11:32     
so helpful yeah I'd be curious to see what you're talking about to sounds yeah yeah     
2:11:39     
I'll see if I can dig that up um trying to think of where to whether     
2:11:46     
to just do a a new search on that or yeah I'll probably just do resarch but that it would be interesting yeah     
2:11:54     
especially if there's an isotope angle there too so this is uh our medium post on uh     
2:12:02     
physical Computing this is uh like a Saturday morning neural Sim discussion so this is actually a nice post you know     
2:12:09     
we had a discuss a set of discussions uh this is actually sort of     
2:12:14     
a quote from the ma conference and you know kind of talking about how they were     
2:12:19     
thinking about comp early Computing uh and sort of thinking of     
2:12:26     
digitality so like you know a lot of things in the real world are continuous but we wanted to make them digital for     
2:12:33     
convenience purposes of computing so this is kind of where the idea of you     
2:12:39     
know the Von noan architecture comes from this sort of you know this sort of     
2:12:44     
digital Computing Paradigm and so we talked a little bit about physical Computing because we were talking about     
2:12:51     
Computing in the brain and how you know there's this metaphor of the brain is a computer but you know the evidence that     
2:12:58     
the brain is actually say like a Von noyman computer is very tenuous it's it's a nice metaphor but you know it may     
2:13:06     
fall apart upon further scrutiny so we had this whole discussion thread on sort     
2:13:13     
of how to think about the brain as a computer or even if it is a computer and     
2:13:18     
that led us to this idea of physical computation and how people are approaching computation and cognitive     
2:13:24     
science and the neurosciences so it was a pretty wide ranging discussion you know we started     
2:13:30     
off with sort of uh some of the philosophical work of gualtier pikanini     
2:13:35     
and Cory mey Cory mey is interested in like uh sort of analog or continuous     
2:13:42     
Computing btio pikanini is interested in the physical computation and like     
2:13:48     
thinking about analogues to the brain uh we talked about computational     
2:13:53     
physical systems the post from the Stanford encyclopedia philosophy then there is this whole     
2:14:00     
conversation on the church Turing thesis and the church during deuts thesis which     
2:14:07     
you know this kind of frames how we think about like a active computation in     
2:14:13     
a Compu in a digital computer versus an active computation in the brain or in some biological system and so you know     
2:14:21     
Amanda of course was part of this conversation Amanda Nelson and she pointed out that it makes     
2:14:28     
sense to think of evolved biological systems such as brains as instances of analog computers instead of digital     
2:14:35     
computers and then distinguishing between vanon noyman architectures and Alternatives such as     
2:14:41     
physical or analog computation this is you know some of our discussions from these     
2:14:49     
sessions um then we talked in the second session about physical computation uh we pulled up uh fineman's     
2:14:57     
lectures on computation the work of Edward fredkin who did a lot of stuff with digital     
2:15:03     
physics and then uh we actually did discuss Andy adamatzky is work on unconventional     
2:15:09     
computation he's done a lot of work on things like reaction to fusion autometa and slime molds and things like     
2:15:16     
that excitable systems uh that can be modeled that fits aumo model which is actually another     
2:15:24     
oscillator based model of computation so this is you know kind of going over so     
2:15:30     
this is why I wanted to bring this up is because of course we've talked about we're talking about you know these kind     
2:15:36     
of oscillator networks and I think it it belongs in that context although I'm not     
2:15:41     
exactly sure how so then finally you know we we had another session we talked     
2:15:46     
about Steven wolfram's work toaso T's work tley of course developed the to     
2:15:52     
gate which is a gate I think in Quantum Computing and he actually wrote a paper     
2:15:57     
called action or the fungibility of computation which connects physical     
2:16:02     
entropy information action and the amount of computation performed by a     
2:16:07     
system and you know wfr adds to that conversation by kind of sketching out     
2:16:14     
some of the components of computation with a physical substrate so some of the things that physicists have been doing     
2:16:20     
on computation is also relevant to this discussion and so then you know this is     
2:16:26     
kind of a review of that and then I think we had a final session where we     
2:16:32     
talked about no Wolf's notion of universality and in computational models     
2:16:38     
that is you know if we have a computational model of some process you know is it something that we     
2:16:45     
should expect to apply to all sorts of systems or or just a subset of systems     
2:16:52     
so for example you know he has this obsession with cellular     
2:17:00     
autometa and in cellular autometa you can use certain rules to produce     
2:17:05     
different outputs and those outputs per you know uh resemble uh pattern formation in     
2:17:11     
biological systems so for example his rule 30 which is a certain set of     
2:17:17     
interaction rules within the uh in the uh cellular automa produce this type of     
2:17:24     
pattern formation that you often see in conus textile which is a species of     
2:17:31     
snail and so you know that's you know could you say take that model of     
2:17:36     
computation and apply it to Nature and say this is the explanation for the     
2:17:41     
system it's interesting that this type of model can also be used as a pseudo     
2:17:46     
random number generator so the question is is is biology really kind of uh     
2:17:53     
playing according to mathematical rules whereas biology its own thing and we're just like applying rules to explain     
2:18:00     
biology and saying that biology implements these rules but actually no and there are some arguments forign     
2:18:07     
against that which is of course it relates to this larger issue of pancomputationalism or whether computation can explain     
2:18:14     
everything in the universe or if computation is at something and maybe you can merely just draw parallels to     
2:18:21     
the rest of the world like you know biology or even physics and you know that's a question     
2:18:27     
that um I am I tend to be sort of a weak pan computationalist but that's just my     
2:18:35     
uh opinion um and this this has relations to complexity Theory too we've     
2:18:40     
talked about this in other uh meetings where you know complexity theory is     
2:18:45     
basically where we have this Theory say of networks or of pattern for     
2:18:51     
and we assume that you know we can apply say like Network Theory to any kind of system we want social systems biological     
2:18:59     
systems the same principles of organizational that may or may not be a fair assumption and this is again goes     
2:19:07     
back to this pan computational idea and so then you know this this kind of uh     
2:19:13     
kind of talk a little bit more about pan computation and then even poly     
2:19:19     
computation where you're actually implementing computational rules in a biological system which is     
2:19:26     
non-silicon which is the system of soft matter and this is kind of an interesting paper that we covered but     
2:19:33     
that's something you can read about more in the post so we had a lot of different discussions very wide ranging     
2:19:40     
discussions so you know I encourage um you know te Trevor or whoever else is     
2:19:46     
interested to look at this finally I did want to point out Trevor's page here he has a bioarchive     
2:19:52     
paper that he uh just put out so this is Trevor single um author paper in silico     
2:19:59     
Target identification reveals I il12b is a candidate for small molecule dor     
2:20:06     
development so is there anything you want to say about the paper Cher oh thanks um I spent way too long     
2:20:14     
on this this is a I probably did most of this work years ago actually and then     
2:20:19     
I've just kind of uh delayed publishing it so I finally     
2:20:25     
pulled it all together made all the figures okay yeah and uh and yeah so     
2:20:30     
it's uh yeah basically you know everything is all about risk minimization in these     
2:20:37     
days because I feel like we live in a very risk adverse Society so um you know     
2:20:43     
drug Discovery is especially expensive and so I basically did a bunch of stuff to um try to really minimize the risk     
2:20:51     
for if someone wanted to do a new drug Discovery campaign and so I found this     
2:20:56     
site that um that I I think there's like I I would argue a very good chance um of     
2:21:04     
you could have a successful campaign against if you were trying to make a small molecule and it it seems to have     
2:21:10     
some clinical advantages for trying to make um uh just like um safer drugs for     
2:21:18     
treating inflammatory bowel disease so yeah Z you CAU me off off the C I'm     
2:21:24     
happy talk about than I didn't know it's very nice for you to bring you     
2:21:29     
yeah yeah I didn't want to put you on the spot but I think yeah there's yeah     
2:21:34     
you're looking at the site right there oh no you're you're good yeah     
2:21:40     
yeah I'm happy to talk about it anytime but yeah it's very um not somewh orthogonal to neuro research     
2:21:48     
yeah that's fine yeah it's always good to see people's papers and getting things out and you know we we talk about     
2:21:55     
so many things here kind of bring everything together so nothing really I     
2:22:00     
guess is out of scope unless it's like extremely out of scope like I don't know but yeah that that's     
2:22:08     
nice congratulations Trevor on that and so I think that's it for today um I     
2:22:13     
think we have was a nice discussion thank you to uh chup for presenting on     
2:22:19     
their project all right see you next     
2:22:24     
week see yeah take care thanks so much thanks
