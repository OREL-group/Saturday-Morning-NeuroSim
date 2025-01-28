## Meeting Recording

[YouTube link](https://youtu.be/UnKx0mpzyiY)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113891017992412012)

## NOTES:

Morgan: Josh Bongard's course -- Evolutionary Robotics.

* reading group: ActInf book (Tuesday meeting, 3 people showed up), Vehicles (later in week, much better attended).

* step-by-step tutorials, White and Smith discussions.


3D Slicer -- Hackathon (developer day).

* issues building on Fedora. Downgrade system to make system builds.


Brainhack -- data build. A lot of dependencies --> CMAKE allows for VTK across multiple platforms.

* Superbuilds -- not system builds, but building locally (long build time, lots of redundancies).

* turn off tools -- superbuilds.

* OpenBCI -- Galea (EEG/XR). Transformers are not good for time-series, sequential (not token-oriented).


DDEs for Neuroscience. Patrick Minneault -- Enigma project (single-unit foundation). Quell hype around
foundation models.

* Carbon Copies -- brain emulation challenge workshop. Strong wishful thinking element.

* white paper -- Logan Collins, Patrick Minneault.

* improve our ability to capture connectomics. Phillip Shiu -- Drosophila connectomics.

* for connectomes, are we oversampling certain areas? Results in the connectome we work with and understand.


Diagram for organoids, assembloids, disease models (Knofler, Pascu).

* summaries of organoid research --> Frontiers paper image (whole-brain organoid).

* cerebral organoids first reported in 2013, or 2008?

* provenance of innovation, first papers.


Human cell organoids, who started connecting organoids together (assembloid).

* brainorganogenesis.org

* starting a Synthetic Biological Intelligence Lab from scratch.

* equipment, synthetic biological intelligence.

* people from different parts of synthetic biology (organoids +).

* trying to build a community for this type of research.


Empowering Remote Labs --> NeuroTechX --> remote groups --> access to Braingeneers.

* "Goal-directed learning in cortical organoids". -- Active Inference and Intentional Behavior.

* merging of simulagtions of neuronal culture with cognitive tasks --> stimulation (closed-loop behavior).

* AI-designed robots --> Josh Bongard video --> around the 45:00 mark. Simulations, policies for random bodies.

* simulations of Xenobots. Manipulate embryonic cells, sheets -- fabricated structures of diverse types.

* Sim2Real transfers --> difficulty in soft body robots. Cell sturctures and behavioral predictions.


Connectomics <--> Active Inference <--> Bongard : 3-D structures have goal-directedness.

* signal a given brain structure configuration.

* Sergiu Pasca, Ron Weiss (Programmable organoids).

* microfluidics problem -- manipulating organoids. Organ on a chip.

* nutrients, forces, etc.

* LLMs --> new creative ways to say they are "hit or miss".

* PhysiBOSS --> agent-based modeling (organoid simulation project).


Reading Group -- Markov blankets. Free energy --> cell division.

* Bongard --> fancy embryo manipulation. Ravshevsky --> biophysics.

* The Niche --> blog that covers stem cell biology.

* MEA -- last proprietary piece of Braingeneers. Get into open analysis pipeline. Cell types rather than a spectrum.


Organoid cell gene expression is unusual. Artificial environment with environmental signals.

* tissue/network behavior, from cells grown in isolation. Artificial vs. realistic.

* cortical column as the unit of information processing. What's different about the Thousand Brains project?

* NeuroNav project --> Reinforcement Learning (model-free). Neurally plausible!

* do you care about the behavior or the architecture or the neurobiology?

* list of neuro-inspired stuff in white paper (cortical message passing methods).


ActInf secret sauce -- Continual Learning, key components.

* we have a bunch of cell types because of historical contingency.

* model-free RL -- comparative anatomy -- make inferences in light of Bongard's work. What does structure tell us (vs. function)?

## TRANSCRIPT:

Transcript     
0:01     
hello how are you morning morning all     
0:08     
right welcome so yeah um Jesse is taking a     
0:15     
leave of absence from the lab he's busy with things in his     
0:24     
life so finishing up as being a student oh yeah     
0:30     
uh so yeah that's good um and we were going to have a cybernetics meeting last     
0:36     
week but we postponed it for the week after and we've been I think we had our     
0:44     
third Diva one meeting last week and we covered two     
0:51     
papers um and so one on benchmarking Sean's data sets which was     
0:57     
really interesting so so if people are interested in that uh for like machine     
1:04     
learning or whatever they have uh some benchmarks in there we went through their GitHub repository from the paper     
1:12     
and looked at the different benchmarks that they have I think there were some behavioral benchmarks some cell biology     
1:19     
benchmarks and things like that um so it's interesting     
1:26     
um another thing that happened was I got the project descriptions for Google     
1:33     
sumar code to Inc after kind of taking a first pass at it so I sent in some of our     
1:41     
ideas and hopefully we'll hear back in a couple weeks about the status     
1:53     
EV so did you have any updates you wanted to share Morgan uh I've got two dogs here I need     
2:01     
to deal with but um the been doing     
2:11     
um Josh Bard's Court well I didn't I've     
2:18     
been sending all the lectures for The evolutionary robotics     
2:24     
class yeah um and that's that's been interesting i'     
2:30     
like to follow up on that the did the um this dog wants to go out     
2:39     
um we did a um rating group on the active inference     
2:48     
textbook oh yeah yeah and um so so three three people showed up oh     
2:58     
wow 10 10 people were signed up and you know the vehicles vehicles one was much     
3:06     
much better attended um you know I just don't know if you can just     
3:13     
give people the entire 300 Page book as a yeah even with kind of two months     
3:21     
notice yeah I think that's kind of a like here's a book you got to go chapter chapter I know you     
3:28     
know any right and but by three people I mean I was one of the three so there was     
3:34     
two other yeah um     
3:40     
um yeah so I I I definitely shared that     
3:46     
you know there were other ways to do this and that the active     
3:54     
Institute is the you know is the master of this um uh     
4:00     
as well as sharing the step-by-step tutorial um and the fact that like you     
4:08     
know they've got almost eight hours of of video     
4:15     
talking with you know Ryan Smith and Christopher white about the step-by-step     
4:20     
tutorial you know     
4:25     
um so that uh     
4:32     
yeah I can say more about the robotics in in a minute okay um and the     
4:39     
uh Ed the 3D slicer you know it's not     
4:45     
they called it a hackathon but it was you know work     
4:50     
on work on a projects you know it was like developer     
4:57     
day you know like like yeah so that was cool and I was I I was     
5:05     
just kind of focused on what we' discussed     
5:10     
um like said two weeks ago now a week ago     
5:15     
um uh just about you know the issues building on Fedora and     
5:25     
um yeah so you know interesting stuff where     
5:31     
it's like I I actually did make progress um and but it was it was silly things     
5:38     
like you know oh hey I've got to use I've got to use an older version of GCC     
5:45     
because like too many too many what would be warnings on GCC you know like     
5:51     
they're building on a bunch of and a bun like three versions behind the door     
6:00     
in terms of GCC yeah and U anyway so you     
6:06     
know just it's it's funny when when you realize that it's not it's not version     
6:14     
issues it's I mean it's not like code issues or anything like that it's just that yeah you've got to downgrade your     
6:26     
system that the builds will yeah will complete     
6:34     
um um but but that was good and it was it was nice to you know connect with     
6:40     
those guys and um uh yeah like like the     
6:45     
their kind of opensource community manager was was there helping people I     
6:52     
mean they were doing an inperson event in um um in the     
6:59     
North Carolina okay and um oh and U     
7:04     
right now is brain hack Gainer buil which we could     
7:13     
actually could check the the talks online yeah all right so there are a few     
7:20     
things I wanted to go over um I think some of the Morgan had mentioned and     
7:26     
then I think one was uh where Hussein is involved so the first one is the slicer     
7:34     
hackathon so this is uh hosted by kitware this is this page in the 3D     
7:41     
slicer community so we've talked about 3D slicer both in this group and in Diva     
7:46     
worm where you know people are doing 3D modeling of image     
7:53     
visualization uh analysis and you know there's a wide variety of people in that community in     
7:59     
3D printing people paleontologists astronomers surgical people medical     
8:06     
imagers etc etc this is the they were doing this     
8:11     
inperson event at the kitware North Carolina office um and they also I think had a     
8:17     
Google meet instance where people could join virtually so this is an nice example of     
8:25     
an event that you know people host online sort of in this case uh hybrid and you know they're able to     
8:33     
kind of organize this on their discourse instance um it's like you know this is a     
8:41     
typical hackathon where they want you to review the issues set up your     
8:46     
environment before you get there um and then you know get into     
8:52     
these discussions about different topics so their good first issues are here on     
8:57     
their GitHub repository you know these are just basically very simple     
9:03     
issues uh I mean simple if you're in that Community um if you're a you know a     
9:10     
very early beginner probably not uh you know you have things like     
9:15     
improving the developers guide uh document th slab reconstruction     
9:22     
UI documentation of cmake variables     
9:27     
um improve slice execution model documentation these are things you might     
9:33     
expect from first good first issues and very simple issues to sort of solve     
9:38     
during hackathon you don't want to have huge issues during hackathon you want to start small maybe if you decide to build     
9:46     
something you know you kind of figure out what the issues are and attack the low hanging fruit then after the     
9:53     
hackathon is the time where you really kind of move up to the more complex issues yeah so that looks really nice     
9:59     
that they they had this event looks like they're their Community is well     
10:06     
structured and yeah that's great got a pretty sizable group     
10:12     
there sorry I'm trying to find some     
10:17     
lights there in North     
10:25     
Carolina sorry there we go and     
10:31     
and yeah I'll I'll figure out how to kind of give them a report or     
10:38     
you um it's a it's a big project you know     
10:45     
like like they they have a lot of dependencies um and     
10:52     
uh you know like cake cmake the build tool start     
11:00     
started because kitware yeah it was developed I mean in a     
11:07     
perfect kind of hack away where the developers needed to scratch their own     
11:12     
itch in that they needed to build vtk across multiple platforms right so so     
11:19     
there it's like like we we need to sport Windows which is always the big problem     
11:26     
yeah uh and Unix and um     
11:34     
and yeah and then the fact that like all these platforms have different um um     
11:41     
different tool chains you know um so     
11:47     
anyway so so I saw a lot of those issues but but also just like that     
11:52     
you're building I mean one of the things that Fedora dislikes um but is very common     
11:59     
especially with scientific software these super builds where you know instead of using the     
12:07     
system dependencies instead of using the system builds of of various common     
12:16     
commonly used tools um you build locally     
12:21     
every single dependency you have um which makes for just really long     
12:27     
buil times as well as like a lot of redundancy in terms of just     
12:35     
um yeah everybody's everybody's building their own itk everybody's building their     
12:40     
own ptk instead of trying to figure out how     
12:46     
to how to um use the system version or something like that for instance yeah     
12:54     
but but that was exactly what I knew was going to happen and and and you know so     
12:59     
I I got to I got to learn a little bit about how to yeah better better adapt     
13:07     
the system I mean I was still using the super build um but but I was turning off     
13:13     
tools that were that that you know that I had obviously as system system     
13:21     
dependencies as well as like figuring out that I need to use GCC 13 instead of     
13:27     
14 which you know again these These are the kind of things where it's just like hey for some reason     
13:33     
GCC now throws a haris instead of exceptions I mean     
13:38     
warnings for exactly the same code and yeah     
13:47     
so that was good good yeah yeah you're gonna talk about the other hack on yeah     
13:54     
so it looks like uh uh uh Hussein went     
13:59     
to the MIT reality hackathon we talked about this last year it's in     
14:05     
2025 it's for 2025 and uh I don't know if there like they're different things     
14:11     
going on here it's basically the same structure but uh so yeah they had 2024     
14:18     
tracks and prizes and um let me see if they have anything in     
14:25     
the yeah experiential 2025     
14:30     
um and I don't know if they tell you much about okay here it is the program     
14:37     
structure so this is uh the technology theme is deep spatial the next generation of extended reality and they     
14:44     
have extending reality and all these application domains designing Prosperity learning     
14:51     
Innovation Advanced Computing integrating in embedded systems hack to Market which I assume is     
14:59     
like just creating like rapid prototypes of things engineering sustainability multi-     
15:06     
sensory interaction digital embodiment aerospatial applications not sure what     
15:12     
that is and then artificial intelligence so this is just kind of like     
15:18     
the uh tentacles of extending reality uh so there three categories     
15:25     
technology methodology and action uh so technology is experiential now and     
15:34     
soon so that is what technologies are experiential now and in the near term     
15:41     
what are they and what potential implications do they have for creating new kinds of Technology enabled     
15:48     
Human Experience how is this technology currently being enabled by other     
15:53     
institutions for World development so I guess it's just putting     
15:58     
the technology into practice um and how they sort of     
16:04     
enable Human Experience uh methodology category two     
16:11     
how to Foster Innovation uh so this is just kind of how do you     
16:17     
make uh things uh one core hypothesis behind the reality hack mission that     
16:24     
forms of technology development leave gaps in what problems are solved and who is serving by new     
16:30     
technologies what relevant methods and mechanisms have previously been proven successful for sheering     
16:37     
Innovation from enabling would be innovators with skills selfefficacy and     
16:43     
a support network of people and resources to deploying commercially successful solutions that solve problems     
16:51     
and make the world a better place uh is that a question I don't know     
16:57     
uh what new mechanisms might be conceived and implemented so this is where you're     
17:04     
enabling people giving them the support to create things and put them out into     
17:09     
the world and then also making sure that those things are useful you know or or     
17:16     
enrich people's lives and so you know this is always something that people are looking to do is to figure out how to     
17:24     
Foster Innovation um and then three is action this is     
17:30     
let's reality hacks this is just kind of like doing the things you do at a hackathon you know creating your project     
17:39     
doing you know collaborating with other people doing things in person in a short     
17:45     
period of time and then producing some long-term uh project so this is pretty     
17:52     
nice uh you know uh Hussein's really excited about it he's always excited     
17:58     
about it it's it's a nice event it's I think at MIT and the salon at MIT Green Building     
18:05     
MIT Museum um so yeah it's it's     
18:11     
nice see if they have any more information about what's going on so     
18:16     
looks like they have Salon one opening kickoff state of the     
18:22     
industry um little hands big worlds XR for kids at the Yale Center     
18:29     
for immersive Technologies and Pediatrics uh this     
18:36     
is the 1035 startup talk haptic Coast product launch I guess this is a haptic     
18:43     
device then I I suspect that the rest of the session is like you know kind of getting into the     
18:51     
hackathon yeah I know open BCI is there because they've got that um Galia     
18:57     
headset which is you know a VR EEG all right um integrated device I     
19:06     
mean I think it's got some additional features as well um it's a very spendy     
19:14     
device yeah I know 20 25k 30k oh wow     
19:23     
um yeah yeah I mean that's that that     
19:28     
just tells you how much excuse me that that tells you what     
19:33     
their development costs would be I mean you know like the hardware doesn't cost that I mean you know the the bill of     
19:39     
materials is not that expensive right right right but the the the need to     
19:46     
recoup the the the engineer time basically you know that you've got on     
19:53     
that was apparently significant but yeah that that uh um i' I've seen open GCI     
20:01     
posting stuff from the from the event they were talking about it before     
20:08     
too and of course yeah say's very I mean he Ed last year too     
20:16     
yeah so that was the MIT hackathon then something posted by     
20:22     
Morgan I think in it was it one of the I think it was Z there rberg vehicles or     
20:29     
devner o AI was the main conference playlist yeah this is the videos that     
20:36     
they have 27 videos so looks like they had uh opening     
20:42     
remarks aligning representations across individual models and naturalistic imaging she's she's um she's a staple of     
20:50     
the the open source um you know brain     
20:56     
hack and uh other other um     
21:01     
communities Elizabeth Duke PR yeah yeah yeah uh yeah Arena's obviously a     
21:10     
professor there at um in Montreal yeah and well I guess obviously we all know     
21:20     
J I think I think Elizabeth is um she Stanford now I forget     
21:29     
y this this Arena R talk rethinking intelligence from dynamical systems     
21:35     
perspective it's interesting yeah yeah I mean you know Terry sinowski is OB you     
21:43     
know is the one who you know every time I think I find     
21:49     
some interesting new math physics thing it's     
21:55     
like I'll do a search and Terry snowski just described it 10 years ago yeah yeah     
22:01     
he's he's been doing a lot of this for a very long time     
22:07     
so I I I wonder what kind of overlap there is there but but um uh yeah     
22:16     
and um I guess I guess eventually some he he needed to talk about Transformers     
22:25     
yeah um but I I just uh I just saw a talk on     
22:31     
um you know just how how crap Transformers are for time series     
22:37     
prediction oh yeah yeah any kind of sequential data I guess is the     
22:43     
problem yeah the the the yeah yeah just treating treating     
22:49     
time series as a token prediction is just not yeah but you know he he's he's the the     
22:57     
master of you know I think um I think it was these delay differential     
23:03     
equations that um that I started seeing like last year and you know he's got a     
23:10     
paper in 2013 about them oh yeah yeah they've been around room for a while oh     
23:15     
yeah I mean they have but but applied to near sence okay     
23:22     
yeah yeah it's yeah I don't know what yeah it' be interesting to see what he has to say about some of this uh     
23:29     
then the panel discussion does better AI mean more humanlike     
23:35     
AI uh this one here are two New Perspectives on the structure function relationship in real     
23:41     
networks Paul CAC who we've talked about some Neuroscience foundations for     
23:48     
AI the second keynote is Louise pooa the entangled brain integrating perception     
23:55     
cognition and emotion uh then there were some lightning     
24:01     
talks uh oh okay entangled brain Guang yeah     
24:07     
yeah yeah oh this yes     
24:14     
sangled yeah I take it that they're getting like a lot of this is at the level of here's my work how does that     
24:20     
fit into the greater Vision uh which we might talk about in the panel yeah     
24:30     
uh experimentation on in silic neural responses from encoding models and continual reinforcement     
24:37     
learning doing a prec coup um then the next panel emergence of     
24:44     
reasoning in grein and machines um you know some other talks here um I     
24:54     
guess visual representations visual sensation     
24:59     
perception visual processing uh on the relationship     
25:05     
between single units and distributed representations interesting you know     
25:11     
typical sort of like visual representation stuff uh another round of lightning     
25:20     
talks uh Foundation models for Neuroscience yeah he's he's now paid by     
25:26     
the amarath Foundation oh and and they're     
25:32     
doing the Enigma um the unfortunately second     
25:39     
project to be called Enigma yeah um and and     
25:47     
um uh well there's also the big psychiatric one you know yeah yeah yeah     
25:53     
the the um kind of like a single     
25:59     
unit you know it's like a foundation model from the ground     
26:05     
up like using yeah big new data collections I     
26:12     
think is the is the idea     
26:18     
yeah excuse so idea being that like you know     
26:25     
or I don't know if this is how they they Justified the the funding for it but you     
26:31     
know the the the brain project the brain initiative is is being     
26:37     
defunded somebody needs to do this right yeah     
26:42     
yeah always 10 years later do it right you know you do a project oh we got to     
26:48     
do it right maybe maybe I I mean together with this this you know this hype about     
26:56     
Foundation models oh yeah yeah I I wonder if they're dealing with     
27:03     
that any better than anyone else like it seems like everyone has a foundation model for something yeah you know I mean     
27:12     
I I I love him um like he's always been attached to     
27:21     
really cool you know good you know I mean he was CTO for neurom match he was     
27:29     
um yeah that's it's good Neuroscience MAA kind of     
27:36     
projects um but uh you know there's just some of that um     
27:44     
is is that's foresight Institute meetings yeah you know and there there     
27:51     
there's just this this this whole brain emulation as we     
27:57     
should say we should um did I put this in carbon copies is doing     
28:05     
U something big February 22nd did I drop that in     
28:12     
um call call for participation     
28:19     
um sorry let me yeah carbon copies foundation on     
28:26     
LinkedIn rain ulation challenge Workshop yeah okay     
28:32     
yeah um and you     
28:38     
know again there's I think I've said before that     
28:45     
there's some discussion around whole brain emulation that I just find     
28:52     
um I don't know what the right word is like     
28:58     
it's not it's not just that it's optimistic it's like it's     
29:07     
um wishful thinking yeah wish wishful thinking around     
29:13     
this that that doesn't seem to um bch reality or doesn't seem to be well     
29:19     
grounded you know um yeah yeah it reminds me of The Far     
29:26     
Side cartoon where there's a lot of equ and then there's there's like and then a     
29:31     
miracle occurs yeah um     
29:37     
anyway well I mean it's certainly like an open set of open problems that like     
29:43     
you know if you think okay well we have this vision for something and we have     
29:48     
the state of the field and then there are like five big open problems we need to solve to get to what we want to do     
29:56     
and it's great if we could solve those problems but we're not there yet so let's just kind of look around     
30:04     
them yeah yeah yeah the the anyway it it's     
30:10     
um uh you know sorry I was just gonna say something about the car compies where     
30:16     
you know there's there's a lot of really good technical     
30:24     
um you know he and and Logan um Collins have uh a really nice white     
30:33     
paper discussing the technical     
30:40     
innovations that would be that are that are within reach and     
30:48     
and practical and what they would do to     
30:55     
improve the um yeah just the our our our ability to     
31:03     
capture connectomics or and cell cell structure     
31:10     
yeah that's really interesting you know and and     
31:16     
um uh yeah anyway and I I I saw I just     
31:21     
saw that Philip Shu who is the first author of The Big drop     
31:29     
connectomics gives us Behavior paper I don't know if you remember this from     
31:36     
um uh Kristen somebody's lab in Berkeley sorry     
31:43     
but I I can find Philip she I can find the reference the link but it was it was     
31:48     
you know an interesting like hey connectomic gives us something akin     
31:55     
to um sorry connectomics plus computational     
32:01     
Neuroscience simulation gives us something that looks     
32:06     
like calcium Imaging oh really you know     
32:11     
of of this of the same stuff you     
32:17     
know um like this is just like a standard simulation and then the conomics data top connectomics data and     
32:25     
and you know again like devils are in the details in you know devils in the details in terms of just like okay you     
32:33     
know like does it um you know I I I think that     
32:41     
like I think it's one of those things [Music] where     
32:47     
um you know so it was like it was     
32:52     
like you know this simulation gives us something that looks     
32:59     
like all Factory uh um     
33:04     
um you know old factory response or something like that but you know sorry     
33:12     
talking last night with my daughter about 23 to me results okay it's just like hey you know you know she's saying     
33:20     
something like like what's my ancestry you know it's like her her mom's Irish     
33:25     
and and I'm prettyy much English and so say well you know according to 23 me I     
33:32     
come from London but here's the thing right was trying to explain to her that you know     
33:37     
these kind of DNA analysis it's not like they go in and they like like oh you have London yeah you have London in your     
33:45     
DNA right like like it's on the basis of who signed up where they located and and     
33:54     
so you have this problem that in the UK of course like most people live in London right and certainly people with     
34:02     
disposable income to to waste it on a 23 and meek kid also live in London right     
34:08     
right so it's just like do I come from London or is the only all all the     
34:13     
samples just from London right right well it's you know does it     
34:21     
connectomics did the connectomics results give you an all Factory response on the basis of conomics yeah     
34:29     
or is that just like is is Al Factory kind of like the main the main sense you     
34:36     
know is that like the visual system for for drop right in sense like like you     
34:42     
know you you stimulate somewhere you're gonna get the biggest response in all Factory areas or something like that you     
34:49     
know what I mean right well that's an inter yeah that's     
34:54     
an interesting question is that like an issue of sampling then or is it     
35:00     
like you know I I I I I don't want to you know I I yeah I mean it would be     
35:07     
great to have somebody like Philip Shu address that right um I I will point out     
35:14     
that one um he was totally not interested in organoid     
35:22     
intelligence and maybe I'm still feeling hurt about that uh and two he's     
35:27     
currently working at uh I forget what they're called maybe     
35:35     
it's like it's like emulate bio anyway he's he's working at a startup     
35:41     
downtown that is doing a whole brain ulation okay yeah you know like which     
35:49     
which to me means that they're doing histology and F highr     
35:58     
you know I mean they're they're basically they're doing AST yeah but but it's probably easier to     
36:06     
raise money with whole brain English but yeah it's sexier is yeah yeah     
36:12     
yeah again I I I still want to know how they how they think that     
36:17     
the yeah what's the secret sauce yeah     
36:24     
yeah so yeah that so that was the Patrick Minal Foundation models for     
36:31     
Neuroscience there's another talk here a common neural basis for Behavior across individuals and species which is     
36:38     
interesting in light of all the model organisms we use but also uh in terms of     
36:44     
the philogenetic approach to neuroscience and how we can sort of     
36:49     
extract key principles across different model     
36:55     
systems Blake Richards at a brain like learning with exponentiated     
37:00     
gradients talking about some of the problems with gradient descent and getting at those kind of     
37:07     
issues uh then this keynote here number five or our Driscoll fast and slow     
37:14     
learning and artificial and biological networks uh the panel discussion for day     
37:22     
three our foundation models for Neuroscience the next big thing obviously     
37:27     
you know that's a contentious thing um then the last few talks here     
37:35     
multi-agent cooperation through learning aware policy gradients we stuff on     
37:41     
gradients uh credit assignment in neural networks without     
37:46     
plasticity uh and then large pre scale pre-training on neural data allows for transfer across     
37:53     
individuals she she the one is she an Emory uh Eva dire     
38:01     
yeah okay then there was a great meeting yeah closing address here and yeah a     
38:06     
great meeting and you know check out some of these talks it's on the main conference YouTube playlist yeah I mean     
38:15     
you know it's like how long they've been going now six years or something I mean'     
38:21     
been going a long time you know it's great great meeting one of the only ones     
38:28     
that really centers itself around Naro AI     
38:33     
yeah so yeah we might get into brain organoids I I I don't think we've talked about brain organoids in a while kind of     
38:40     
some of the things from I think November to now so let's start with the first thing     
38:47     
here uh this is uh this LinkedIn link about     
38:53     
assembl loids this was uh Sergio pasca on     
38:59     
LinkedIn asids and they showing this diagram here     
39:04     
where we have neural organoids different types of neural organoids different you know strial     
39:11     
organoids spinal cord organoids muscle organoids gasta     
39:16     
organoids combining those into neural symbl loids um you know which are these hybrid     
39:23     
things here in the middle and they inate each other and then disease models which are the     
39:31     
migration of sybl loids creating different tissues or sort     
39:36     
of you know you can have like mutations or you can have different disease States so for example     
39:44     
gasta cortical suids can be used for cancer Invasion models for tumor cell     
39:51     
metastasis or or um the way uh Open Water was using on     
39:58     
for um de demonstration of of your ability     
40:06     
to destroy destroy Glo blastoma and leave     
40:11     
um healthy cells yeah pretty remarkable yeah yeah so they     
40:18     
have the well they have two different types of neural assembl migration of Sids and projection of Sids and they     
40:25     
involve different combinations of organ NOS so like somewhere where the cells     
40:30     
migrate from one to the other uh you know they have you have two organoids     
40:36     
put together the cells will migrate across and then projection assembl we going to send projections across and     
40:44     
that's that's the dominant form of integration and so then that that allows     
40:49     
you to study other types of connectivity defects as opposed to migration defects where you're looking at things     
40:56     
like neur degeneration reduce Network synchronization and abnormal neural     
41:02     
activity okay that's a great diagram I think we saw this before in another meeting but I wanted to bring it up it's     
41:08     
nice yeah he he he he keeps on he keeps on this is this is one of P's particular     
41:16     
you know um you know Hammers If you will yeah is     
41:23     
is is is SIDS you know I I still probably credit     
41:31     
um um is it noler I'm trying to think of     
41:38     
the guy in Vienna who was meline Lancaster's adviser you know she's she's     
41:44     
the first author interesting you know there's a guy um on LinkedIn who's been     
41:51     
trying to do summaries of of organoid re research and     
41:59     
um and he he obviously put forward um     
42:07     
a you know some Frontiers paper image that that had a table like this     
42:14     
but but had like kind of an obvious mistake in it because it was talking     
42:20     
about a whole brain organoid yeah and um anyway but it was     
42:27     
interesting because people like um     
42:34     
um Alison MRI down in San Diego chimed     
42:40     
in about you know both mistakes in the figure as well as like papers that they     
42:46     
felt were I think because he was saying     
42:52     
something like cerebral organoids were first     
42:59     
um you know first reported in 2013 or     
43:05     
20 2012 2013 something like that and it was kind of it was     
43:11     
interesting to have people like mry and Pasa jumping in on this saying like no     
43:19     
no no it's like 2008 um and uh     
43:28     
yeah so interesting um yeah anyway the the the assembl loids     
43:37     
you know fell down a little rabbit hole in terms of just what what really     
43:43     
constituted the first you know I guess the other question was like human     
43:49     
cell uh um organoids and and then you     
43:55     
know then the next question would be who who started the assembly kind of crace     
44:01     
yeah or you know like like yeah connecting connecting different     
44:07     
organites together but but Pas and pasco's of     
44:13     
course doing the class that is or doing the workshop um     
44:20     
that a lot of a lot of his posts relate to um the upcoming Workshop in May April     
44:28     
May um so that's his brain organ of genesis. org     
44:33     
um and um still still really hoping he'll make all those training materials     
44:40     
available yeah so I definitely want to um talk     
44:49     
about this paper from um one second     
45:02     
uh I don't think I put this in     
45:07     
slack but let me just drop this     
45:14     
in so yeah there you go okay yeah so     
45:20     
this paper here this is an archiv paper yeah oh this one yeah starting a     
45:25     
synthetic biological intellig L from scratch yeah I saw this uh was put up on     
45:32     
the archive over Christmas break or holiday break right     
45:37     
right yes and you got a combo of people from both     
45:43     
brainers right yeah as well as well as um cortical Labs okay you know so that     
45:51     
was that was nice and then I hadn't seen people from RPI before     
45:57     
um but you know more more the marrier and     
46:02     
um uh um yeah that that was that was cool and if you if if you go through a     
46:10     
little bit um especially to the um the supplementary     
46:17     
information it really does you know detail like what what you need     
46:27     
oh yes yeah yeah so um this is     
46:36     
uh yeah again it's just hard to get     
46:43     
overviews of of what what equipment do you need what yeah like if you really     
46:52     
just want to focus on growing neurons doing recording     
46:58     
and and you know and potentially interacting in this kind of organoid     
47:04     
intelligence um way I I kind of kind of prefer this synthetic bio bio     
47:10     
intelligence yeah term but um anyway really nice really nice     
47:20     
um yeah so they're they're an organoid lab     
47:25     
I mean well you got sorry go back up to the top     
47:31     
yeah so you've got um M Raji um he's he's like you know I I     
47:40     
forget his um his exact role but I you know he's he's     
47:48     
definitely a senior Pi at The genomics Institute right and and um of of the     
47:58     
brainers in particular at that you know because that's like brainers are like a     
48:03     
suborganization of genomics Institute right um uh I was surprised that David Hustler is     
48:12     
not on that um anyway but but that doesn't     
48:18     
surprise me that Muhammad is because he's the yeah he's he's on all the the     
48:25     
kind of the real organoid papers um and then Brent Kagan yeah is obviously the     
48:31     
cor collapse guy so I I don't recognize anybody else um but um I will see what I can     
48:43     
learn about what's going on I I thought it was just interesting as well that kind of the do you see the     
48:50     
um um The Design Lab at renier oh yeah you know and the center for     
48:57     
biotechnology and interdisciplinary studies yeah which I thought was interesting     
49:03     
too anyway so I I I'm hoping that that just     
49:09     
means you know we've got this um organoid intelligence slack and um you     
49:17     
know try trying to build a community of the groups that are that are doing this     
49:23     
right right um and so maybe maybe RPI is     
49:29     
is a new Once once you know as as a lab that     
49:35     
um is interested so I guess that g gay Wang I don't know how you say     
49:42     
G good wayang yeah um let me see     
49:48     
if let see what I get through um and there this new you know     
49:56     
this is the um sorry I'll drop this to     
50:01     
like you said like there were a bunch of papers that um that were dropped     
50:09     
um uh over the holidays yeah yeah and this is the one where you know like     
50:19     
like kind of updates some of some of these you know     
50:26     
somewhat previous reports from the same group but again just touting their cloud     
50:35     
enabled um organoid lab as as to as     
50:40     
being a um uh yeah kind of an     
50:47     
empowering um remote lab right yeah that     
50:52     
that you could work with this um um     
50:58     
yeah yeah and and and this is this is so this just nice to see this is what we're     
51:03     
trying to in terms of you know anything we build would be basically for others     
51:10     
to use right um and yeah so I thought I thought a     
51:17     
nice report on that that's and again with neurotek X we've got some groups that are remote that um that we're Hing     
51:27     
that um they can get access to the the braingineers work     
51:34     
yeah um want to bring that up and     
51:39     
um oh yeah and then the the last the only Reas I'm bringing it up is the um     
51:46     
the connection with um um let me just see     
51:55     
go um     
52:06     
let me just see if I get this with yeah and then the last I I want to just     
52:13     
bring up because um it comes back     
52:21     
around to um uh     
52:31     
to active inference okay um or it could it could come around too bad     
52:40     
but it it's um it's uh just doing     
52:45     
something that is dish brain you know this is the first kind of dish brain     
52:51     
like paper that I've seen from the brain Jers and you can see Karina's some     
52:56     
middle author there and then then you've certainly got the usual suspects in     
53:01     
terms of the um the bra engineers piis at the end there so Muhammad David and     
53:12     
Mercia yeah um and that that's that is is is     
53:21     
brought to mind um just uh one     
53:27     
got too many papers here um but a     
53:36     
um a [Music] paper from     
53:41     
um friston plus     
53:46     
um some other co-authors on active inference and intentional     
53:54     
Behavior and the the last author is um Maxwell     
54:01     
ramstead okay um anyway I     
54:07     
I there's there's some you know these these two two areas are kind of     
54:15     
coming um um starting to starting to     
54:21     
merge right right that's that's great so this is uh where they're kind of using     
54:28     
cortical organoids to look at intentional or go directed     
54:34     
learning uh then they have this part here although sensory input is vital to     
54:39     
neurod development in Vivo few Studies have explored the effective meaningful input to in vitro neuroc cultures over     
54:46     
time so this is where they're outside the brain and you know giving input to     
54:53     
developing organoids I guess organoid cultur yeah uh this is the demonstration of the     
54:59     
first example of a gold directed learning uh observation and BR organoids     
55:05     
they have this Clos Loop elector physiological framework to body Mouse cortical organoids into a simulated     
55:12     
dynamical task which is the the pull balancing cart pull task and then     
55:18     
evaluate learning through high frequency training signals yeah and and now now if you just     
55:27     
check the slack again okay and and yeah check there so you see in their in their     
55:36     
formal account of intentional behavior um uh we simulate in vitro experiments     
55:44     
in which neuronal culture is spontaneously learning to play PM right right so there they're Absolut you know     
55:52     
it's it's it's this merging of the     
55:57     
um simulations of neuronal culture and actual organoid you know organoid     
56:04     
intelligence yeah and and um and     
56:12     
it's sorry the third um leg of this which I thought was     
56:19     
super super interesting um actually comes from Josh bungard     
56:26     
um and he has um he did a talk not as     
56:33     
part of his lecture series for Texas     
56:40     
Tech um and in this he is let me I'll just     
56:48     
I'll drop it into brain organiz because again it sort of relates but um     
56:57     
uh sorry where is it so it's at     
57:02     
like 40 yeah it's about 45 minutes     
57:09     
in um uh he is sorry I lost you he's     
57:16     
talking about the um you know so here here's a class about     
57:24     
evolutionary robotics where you're making simulations and you're designing     
57:30     
you know policies for     
57:35     
these almost random bodies right yeah um     
57:41     
uh and yeah and like they're they're     
57:46     
mostly I mean it's mostly moved to soft body robotics at this point right yeah     
57:52     
but um but yeah the the very very crude what I mean     
57:59     
by that is like these are very crude structures right that don't certainly look like robots but it's interesting     
58:07     
because as soon as he gets to kind of his xenobots um he's talking about how they     
58:16     
develop these with basically micromanipulation of the embryos to get     
58:21     
these these kinds of behaviors but then um     
58:27     
and interestingly talks about the fact that the word robot comes from this     
58:32     
Czech uh work from the 20s I think and in the story these were biological     
58:40     
robots oh so he's just like in many ways these     
58:46     
are robots and the mechanical ones are the ones that are you know are are kind of     
58:53     
fake version of them yeah but but he starts to do     
59:01     
simulations of xenobots okay and and or you know Sim     
59:09     
simulations of um what if I do     
59:17     
micromanipulation of you know embryonic cells to create sheets of     
59:27     
uh um you know skin cells I think I think he was mostly playing with again     
59:34     
it's the work of somebody um Patrick I forget Patrick     
59:42     
um making     
59:48     
fabricating cell structures um of particular cell type     
59:56     
cardiac and and skin where his simulations start to make     
1:00:05     
good Sim tooreal transfers okay that which which was cool     
1:00:13     
right so so again you know one of the things that he talks about in his in his     
1:00:20     
class is the the difficulty of sim to     
1:00:25     
real transfer when they're just talking about the kind of um soft body robots that they're they     
1:00:34     
they've been the kind of things that he's been working on for 20 years yeah     
1:00:40     
uh um but what was really interesting was hey we're doing simulations of     
1:00:47     
xenobots and it's make and it's it's     
1:00:54     
actually making useful predictions about what kind of cell structures we can put     
1:01:00     
together and what their behavior will be     
1:01:07     
yeah um so it doesn't doesn't quite come um fully back to the you know the the     
1:01:17     
ramstead active inference modeling of neuronal structures and the the um the     
1:01:25     
gold directed learning of of the the branch years but but I'm I'm feeling     
1:01:32     
really good about that those three coming together     
1:01:37     
where sell um yeah where those those simulations can can get much more     
1:01:45     
biological and and the the reason for that right is that that geometry and and     
1:01:52     
kind of connectomics you know again like one of the things that haven't been been     
1:01:57     
able to do in organoid intelligence is well there's there's a great deal of of     
1:02:04     
trouble generating 3D structures that have purpose yeah you know or or or     
1:02:15     
certainly just being able to control that in a in a um again a kind of you     
1:02:21     
know experiment or goal directed right uh way like I I want I want to have this     
1:02:30     
kind of brain structure how do I how do I signal that     
1:02:37     
right right and and I thought it was interesting that you know bongard is not quite there but he's he's predicting     
1:02:45     
Mobility off of these these     
1:02:51     
artificial yeah off of these biological robots     
1:02:57     
yeah so so really really interesting kind     
1:03:05     
of Confluence yeah yeah I like this you     
1:03:10     
know I feel like it should use some some fancy words     
1:03:16     
UNS no what's the what's the U     
1:03:22     
um it's a sociobiology guy um uh IO Wilson yeah yeah consilience     
1:03:29     
consilience you know he's got that book on consilience     
1:03:36     
yeah well that's great yeah thanks for that overview things yeah yeah sorry not     
1:03:43     
not um there's some good stuff there too in terms of um     
1:03:52     
um um High throughput um culture     
1:03:57     
work um and you know there's there's I I I got some links to     
1:04:04     
some um yeah what I would call kind of technical organized     
1:04:10     
culture papers right um our messages are going to be     
1:04:17     
deleted January 28th uh it looks like the older ones I mean the ones that you     
1:04:23     
know has they disappear I'm backing up these different channels in the     
1:04:30     
uh uh in the Discord so we have the links preserved somewhere and I've also     
1:04:35     
backed up some of the channels okay so it's yeah it's not going into the ether uh okay but yeah let's it would be it     
1:04:42     
would be sad yeah I know why don't we move through some of these other links and then we'll yeah so like this     
1:04:50     
is uh this is a tissue talk I guess that happened yeah     
1:04:56     
programmable organoids guiding sulate with synthetic biology in neomorphic     
1:05:01     
circuits yeah and then he he's he's you know he's one of those people who's been     
1:05:09     
doing it forever yeah yeah sergy Pusa well the the     
1:05:16     
the Ron whis okay yeah okay the programmable Orin sorry that was another     
1:05:23     
that was a different um that was tissue talk yeah old tissue     
1:05:29     
talk and then we also have uh this paper here and this kind of     
1:05:35     
fits into what you were just talking about uh assembl oid models to study     
1:05:41     
Loop circuits of the human nervous system so this is where we     
1:05:47     
have uh neural circuits that kind of loop around from the the basil ganglia     
1:05:53     
the cerebral cortex the thalamus these are motifs that you'll see in the human connectome and often times those are you     
1:06:00     
know important for function between like you know things coming up from the brain     
1:06:05     
stem to the neocortex and then back around looping uh so this is basically you know     
1:06:15     
the inspiration for the fundamental networks for sensory motor processing and their dysfunction so you     
1:06:21     
can study neuros psychiatric disorders these cursive Loop circuits have been investigated in animal models     
1:06:28     
and by clinical neuroimaging however direct functional access to developing human neurons     
1:06:34     
forming these networks has been limited so you know we can use animal models in in in mammals to look at these     
1:06:44     
circuits uh here we use human plur poent stem cells to reconstruct an invitro cortical strial thalamic vertical     
1:06:51     
circuit which is this Loop between the thalamus the strium and the uh     
1:06:57     
neocortex uh by creating a four-part Lo bmid so that's the four part     
1:07:03     
loem y uh more specifically we generate regionalized neural organoids that     
1:07:10     
resemble the key elements of the cortical strial Thea cortical circuit and functionally integrate them into     
1:07:16     
lupus symbl loids using custom 3D printed biocompatible Wells yeah yeah I     
1:07:23     
thought that was interesting too so what are they they do are they doing like uh     
1:07:28     
just how are they building these circuits I'm not quite sure well it     
1:07:34     
so you know manipulation just just manipulation of     
1:07:42     
of organoids is kind of a microfluidics problem yeah right and and you know I I     
1:07:51     
think this is where you see the     
1:07:57     
um yeah yeah the this this again um interaction of of the     
1:08:08     
the a lot of organ on a chip kind of work making custom Hardware to allow you     
1:08:17     
know to kind of because we don't know how to tell     
1:08:22     
cells what to do yeah we we we kind of have to put them in an environment where     
1:08:30     
they they just do that thing that we want them to do yeah and and so it's a     
1:08:36     
combination of you know yeah where where nutrients are     
1:08:43     
where where are the forces um you know whether you're generating those     
1:08:50     
forces with centrifuges or you're generating those forces with microfluidics     
1:08:57     
um this is you know again you you'd see from the the the papers figures that um     
1:09:06     
you know it's quite it's quite complicated um equipment     
1:09:13     
generation you know qu and and very very specialized right yeah um and and yeah     
1:09:22     
and you see this with the uh um you see this in the you know even the     
1:09:31     
kind of low cost equipment that the brain Engineers uh     
1:09:37     
um publish about for quality control of     
1:09:43     
of single organic right so this is this is much more complicated I I think I think this     
1:09:51     
might be the largest number of assembly our largest     
1:09:57     
assembl like I'm pretty sure Vienna's still doing three     
1:10:02     
anyway um yeah but really interesting and again     
1:10:09     
they're they're combining this with you know all sorts of kind     
1:10:14     
of specialized neuronal techniques as well right so tracing and calcium     
1:10:22     
Imaging and you know it's it's um it's     
1:10:28     
yeah this is this is the kind of stuff where it's just like okay we're not going to be able to recreate     
1:10:34     
this low cost yeah this is pretty advanc there's a lot of     
1:10:40     
skills certainly you know you you need a team for this because you need you need     
1:10:46     
lots of different Specialists right yeah it looks     
1:10:53     
like yeah so it looks like they're doing a lot of this stuff with to in to try to     
1:10:59     
sort of recapitulate early human development and then disease conditions yeah so that's good     
1:11:07     
um yeah and then uh this is a LinkedIn post here this is a link to a     
1:11:15     
paper New Perspective in cell where they discuss the concept of AI     
1:11:21     
scientists oh right right and and um     
1:11:27     
yeah um why do I biomedical Discovery I guess yeah I     
1:11:34     
think this was just this was more in there because um yeah just there's there's so     
1:11:42     
much there's so much you need to know in biomedical research you know and the the     
1:11:51     
utility of these agents um uh     
1:11:57     
yeah yeah I think that's you know it's a of course we always talk about     
1:12:03     
bioinformatics and trying to put together knowledge looks like they're really kind of moving towards some of     
1:12:10     
the trund Year topics of continual learning AB absolutely right I mean it's     
1:12:17     
it's um you know I I was you know in in looking at some of     
1:12:23     
the soft where behind evolutionary robotics yeah um and things that that I     
1:12:31     
could you know adds to the kind of basic bongards pie bullet     
1:12:39     
stuff um made me check out Ida um mad's     
1:12:46     
work because I was thinking about her nurv um project and and it was just interesting     
1:12:54     
because it was just like I is now like all large language M     
1:13:00     
yeah you know this is so you know someone I mean     
1:13:07     
it's you know good for Richard Sutton he's stuck he he's studying RL and he's     
1:13:15     
sticking with it so     
1:13:21     
any I I you know it's it's again there's so much I mean     
1:13:28     
it's really interesting to me finding listening to people talking     
1:13:35     
about large language models coming up with new ways create new creative ways     
1:13:41     
to say um sometimes large language models work     
1:13:47     
and sometimes they don't and we can't tell the difference but it's like it     
1:13:52     
keep coming up with new you know what did     
1:13:58     
um uh somebody was describing it as like     
1:14:03     
fractal I don't know they were they were trying to give it a new fractal name just like one you're talking about     
1:14:09     
hallucination yeah like like this new term adds nothing to the discussion maybe I had     
1:14:17     
seen that somewhere in it but it sounds weird yeah it sounds like something we want to avoid I guess yeah well anyways     
1:14:24     
uh yeah fractal nonsense I right you know I think he's a forcer     
1:14:32     
good but I think Sean Carol started it with saying that he's a a fractal professor at San oh yeah     
1:14:39     
well at least there it makes a little bit of sense because stud pral so yeah     
1:14:46     
uh this is the Weiss lab I just I dropped that in in terms of a link to the to the the tissue Talk run     
1:14:55     
wice yeah uh this is more from Sergio pasca     
1:15:01     
organoids like I said he just keeps he keeps banging on these things so this is     
1:15:07     
an image of the last paper we talked about right is this the these are the the so you have the uh Pur poent cells     
1:15:17     
building these diphallic organoids doing single Cellar in a seek     
1:15:22     
and then growing them for 100 100 days and seeing the characterization of the     
1:15:27     
different cells there and this is a umap plot of the cells and their markers and     
1:15:33     
then this shows this is this is another umap showing the different cells in the     
1:15:41     
organoid yeah this is really interesting and then you have spatial mapping here     
1:15:46     
so it corresponds to e15.5 Mouse yeah it's interesting yep no it's     
1:15:54     
great stuff and yeah um that is coming off of     
1:16:04     
um I think off of a um James     
1:16:12     
glazure um uh well anyway but but certainly of the     
1:16:20     
kind of compell 3D kind of um     
1:16:26     
simulations yeah this looks like agent based modeling fiz AOSS this is     
1:16:31     
multiscale models uh is there a paper associated with this hit the don't hit the the     
1:16:40     
paper I mean don't hit the image hit the the LinkedIn link oh uh I don't I don't     
1:16:47     
like to get in the LinkedIn in the oh okay could you put a base the paper you     
1:16:52     
I will try sorry about that that's okay you know I mean these days it's just like I just don't like to use Twitter     
1:16:58     
yeah I know I know avoiding that like the plane let me uh let me find     
1:17:09     
that you know it it's so yeah it's so hard to find     
1:17:17     
H you know why can't we all just use web links yeah I know it's     
1:17:23     
like uh okay oh okay there's there's quite a lot     
1:17:31     
of stuff here yeah yeah here we go um let me see what he's got yes fizzy     
1:17:37     
boss tutorial here it is I mean you know the other thing that     
1:17:43     
I feel bad about is is the um you know is to go in extract the     
1:17:53     
paper right right yeah and then and then like kind of bypass this person's post     
1:18:01     
you know what I mean yeah I know like like Anyway there there you go there you go that's a yeah uh so this     
1:18:09     
is so this is building multiscale models of fiz boss and agent based modeling tool briefings and     
1:18:15     
bioinformatics yeah yeah this is the kind of stuff where I'm really     
1:18:22     
hoping you know like again like like there's this third leg to um the kind     
1:18:33     
of I don't know if I want to call it organoid intelligence project or kind of     
1:18:38     
um Oran organoid simulation project     
1:18:44     
but you know how to bring um um much     
1:18:49     
more sophisticated biological simulations to     
1:18:55     
play that that you know like again like the the really nice thing about the     
1:19:00     
bongard paper is is that he did it and got Sim to real yeah you know in that     
1:19:08     
like okay now if I make that does it does it behave the way I I     
1:19:14     
my simulation um said it would and um so     
1:19:20     
yeah I thought that was really you know I'm always looking for things that     
1:19:25     
are in the kind of comp cell 3D Morpheus space or or tissue Forge space yeah yeah     
1:19:35     
this of course is just kind of in that Spirit uh so this article introduces     
1:19:41     
three examples of multiscale models which relay on the framework Foss and     
1:19:46     
add on a fysic cell or physicell which includes the intercellular descriptions     
1:19:52     
as continuous time Boolean models to the agent based approach uh the article     
1:19:58     
demonstrates how to construct these models more easily relying on physic cell Studio the physic Al graphical user     
1:20:06     
interface and then they give a stepbystep tutorial in their GitHub in their GitHub repo here so this     
1:20:13     
has uh really kind of working from a Boolean model and building these uh     
1:20:21     
these agent based models okay and and yeah and I think like tnf models     
1:20:30     
would be cool yeah yeah all right so that's great um why     
1:20:37     
don't we move on in the interest of time here uh we     
1:20:43     
were here so the next paper is the systematizing cellular complexity hell     
1:20:50     
bartin approach to biological problems this is uh in plusa complex     
1:20:57     
systems which is uh a newer pla Journal     
1:21:02     
so this is Nima inani and this is sort of this idea of I     
1:21:11     
guess yeah I mean you know certainly trying to I mean a kind of a theory     
1:21:16     
paper right yeah yeah um that's hearkening hearkening back to Hilbert's     
1:21:24     
was it 1900 problems in mathematics yeah yeah     
1:21:31     
so this kind of goes through uh you know talking about how you know you can can     
1:21:39     
you can examine individual components of Cellular Systems and you can find molecular     
1:21:45     
reactions and interactions basically more of a sort of a reductionist approach to uh getting information out a     
1:21:53     
cell however the challenge lies in integrating these components into a comprehensive comprehensive system Scale     
1:22:00     
map and so this is just making this system Scale map better and more useful     
1:22:07     
this difficulty arises due to factors such as missing links unknown variables Overlook nonlinearities in high     
1:22:14     
dimensional parameter space downplay natural noisiness and     
1:22:20     
stochasticity and a lack of focus on causal influence and temporal Dynamics     
1:22:26     
and then you know what is so what is it that is the essence of complexity in the cell     
1:22:32     
basically uh so this is of course important in constructing a meta theory     
1:22:37     
of biology uh and is addressing fundamental     
1:22:43     
aspects of cellular regulation adaptability and noise management is     
1:22:48     
vital for understanding the robustness and functionality of biological systems     
1:22:54     
so this is all about you know not only the full description or a better     
1:23:00     
description but about some of these other things robustness functionality     
1:23:06     
adaptability etc etc so this is really kind of uh he has three problems here one is     
1:23:14     
where the control switches two is how to manage the need to     
1:23:19     
reconfigure and three is how to harness noise rather than to succumb to it so     
1:23:25     
the first part here is this control switches which is of course actually     
1:23:31     
sites here Ashby uh where you have the concept of trial and error Carl popper     
1:23:38     
highlighted the role trial and error is a fundamental process the knowledge acquisition with an evolutionary     
1:23:44     
epistemology so you know a lot of people propose molecular switches in the cell     
1:23:50     
that switch the cell maybe from one state to another or switch from one metabolic mode to another so you know     
1:23:57     
what does that mean is it uh is it something that gets learned is it something that's programmed is it     
1:24:04     
something that's you know a Boolean or binary uh phenomena or is it you know     
1:24:10     
what what how do we characterize it um and it has you know it relates to     
1:24:17     
adaptation how can the cell adapt to things there's been a lot of work on switches and say like uh coli where you     
1:24:25     
know you have a very simple relatively simple set of switches that can switch the phenotype from one type to another     
1:24:32     
that's an sort of an Adaptive form so like if you're in one set of environmental conditions you can switch     
1:24:40     
to a certain metabolism and then if you're in another set of environmental conditions you can switch to that     
1:24:46     
metabolism so you know it gets into that problem two how to manage the need to     
1:24:52     
reconfigure this speaks to ostatic response and feedback control and     
1:24:57     
thinking about adaptive reconfiguration in cells so like from switches to this     
1:25:03     
idea of reconfiguring the meot type the metab you know the metabolic networks     
1:25:09     
and all that uh kind of going through that and then problem three is how to harness     
1:25:15     
noise rather than to S comeb to it uh now you know there's this idea of     
1:25:20     
cellular noise that's been very popular in the last maybe 20 years     
1:25:25     
the idea that there's intrinsic as well as extrinsic noise so you have intrinsic     
1:25:31     
noise that operates at the level sort of maybe like you know you can think of gene expression as having intrinsic     
1:25:38     
noise having this noise and like stochiometry of the molecules that are     
1:25:45     
involved in triggering gene expression and having transcript production that     
1:25:52     
fluctuates over time in in different contexts and you know how a biological     
1:25:59     
system can handle that noise so if you had like deterministic gene expression     
1:26:05     
it would be easy for the organism to know what to do but when you have this fluctuation especially over time the     
1:26:12     
cell has to sort of integrate all that information and say you this is the sort     
1:26:17     
of the signal that's being sent extracting the signal from noise and all that and then there's of course extern     
1:26:23     
sign noise which is from the environment where you're getting signals that are     
1:26:29     
noisy from the environment and the cell has to figure out what the actual signal     
1:26:34     
is and separate that from the noise so to speak so this is kind of going     
1:26:39     
through this sort of um you know talking about noise and how noise is actually     
1:26:46     
good in the organism or in the in the cell so you know we think of noises     
1:26:52     
being negative or bad and the signal being separate from the noise but sometimes noise is important for     
1:26:59     
biological systems especially because it provides variety it provides a means for     
1:27:06     
adaptation and change it provides information to the cell or the organism     
1:27:11     
that they can use then to understand its environment or understand     
1:27:17     
um you know kind of understand what's going on in the say in the cell or you     
1:27:22     
know in in the biochemical Network so that's getting into that then just     
1:27:28     
kind of finishing up integrating all of these three things into sort of a meta     
1:27:34     
heretical approach okay uh yeah that's good any     
1:27:41     
you want to comment on that or well just got I you know this is all making me you know I'm     
1:27:49     
coming off the back of this reading group so there's just um um     
1:27:55     
thinking a lot about Markoff blankets oh yeah and and it's I I posted this in the     
1:28:04     
math Channel but um the Newton Institute has been hosting a history of     
1:28:12     
mathematics um weeklong Workshop or something     
1:28:18     
conference and um the     
1:28:25     
um is it R reevesy rev veski you know the the kind of very     
1:28:31     
famous biophysicist mathematical biophysicists in University of Chicago in like the 30s     
1:28:39     
you know I'm talking about I think so um anyway it's somebody was     
1:28:48     
covering his work and you know because he was such an influential figure     
1:28:54     
in biophysics um and was kind of you     
1:29:01     
know perhaps too zealous in his insistence on the mathematical nature of     
1:29:09     
everything um but that they were they were covering the fact that he's got this free     
1:29:15     
energy explanation for cell division yeah I don't know if you seen     
1:29:21     
that um um     
1:29:28     
yeah I I've I've got his I mean I think they're in a box now but I've got his     
1:29:34     
like TW volume biophysics text yeah from yeah some some I don't know if     
1:29:43     
it's like a do publication or something I haven't I haven't gone into     
1:29:48     
it to see whether there's some some interesting free energy principle kind     
1:29:53     
of you know precursor there oh yeah precursor yeah well there are a lot of     
1:30:00     
people doing things with like energetics and uh but I mean you know I don't know like I I I get the sense that like my     
1:30:07     
understanding of free energy principle is basically that it's kind of a rehash in the way of like a lot of the energetics     
1:30:15     
work like you know you have uh prene and other people who proposed a lot of     
1:30:21     
things having to do with like energetics and minimizing energetics and so I mean     
1:30:26     
you know there's that aspect of it so it has a lot of precursors and early complexity Theory and you know now we're     
1:30:34     
talking about like going to active inference and things like that so yeah     
1:30:41     
yeah again I'm coming off of that book and and you know I     
1:30:47     
gotta I don't yeah yeah yeah so I don't know whether     
1:30:54     
this the book is trying to cover too much     
1:31:00     
um but yeah anyway I I I want to revisit that or I I wanna I want to do the the     
1:31:09     
the class with the act or you know the the the the multi-week reading     
1:31:19     
yeah so yeah we have uh this is a list of regenerative medicine and stem cell     
1:31:26     
journals from the N oh yeah so that that yeah so Nosler you know maybe I was     
1:31:32     
thinking of his name instead of the guy in VI but um this he's     
1:31:40     
Professor Davis um that that does the niche as a a Blog yeah and like weekly     
1:31:47     
report yeah seem's very he's very good yeah um this is uh and he he actually     
1:31:56     
covers regenerative medicine yeah yeah like like he's the one who covers all     
1:32:02     
those the stem cell clinics and you know and goes through     
1:32:08     
the the the the not necessarily valued work of of     
1:32:17     
seeing which ones these are just charlatans and things oh right yeah     
1:32:25     
uh so then this uh this is a bio archive or this is a LinkedIn post to a     
1:32:32     
bioarchive paper pointing to a bioarchive paper an uh an integrative     
1:32:37     
layer resolved atlas of the human adult human menes right     
1:32:45     
right uh this is uh Lether LinkedIn post pointing to the cell reports methods     
1:32:52     
paper on 3D brain organoid Ral network analysis     
1:32:57     
strategies report so this is actually uh mea nap which is micro     
1:33:06     
electrode recording related so this is a flexible network analysis pipeline for     
1:33:12     
neural 2 and 3D organoid microelectr fors yeah yeah so I wanted wanted to     
1:33:18     
throw that in you know the the one piece remaining the one proprietary piece     
1:33:25     
remaining in the um bra Engineers kind of uh protocol or certainly lab     
1:33:32     
automation is is the um the mea okay um     
1:33:38     
and that might be that might be the case for a while um but so I was just looking     
1:33:46     
for yeah who who Who's dealing with the you know getting that data out and into     
1:33:55     
a an open analysis pipeline     
1:34:01     
right and um yeah just to have that as     
1:34:06     
as on the radar and you know and what would     
1:34:14     
be more important of course for the organized intelligence right is like you     
1:34:20     
want to to stimulate as well right right     
1:34:25     
right all right yeah that's important uh this is another post uh to     
1:34:34     
a paper an integrated transcriptomic s atlas of new human     
1:34:39     
organoid neural organoids it's from nature and this is the diagram here show     
1:34:48     
yeah yeah good stuff and um sorry I'll just link through to see who the     
1:35:00     
um uh so Sergio Pasa     
1:35:08     
again um here we go     
1:35:15     
R um and I'll just put as I'll put in the     
1:35:22     
thread there a link to the paper there we     
1:35:33     
go so this is the paper and integrated transcriptomic was a human organoids     
1:35:40     
this is yes this is human neural     
1:35:46     
organoids uh it's unclear which parts of the human brain are covered by existing protocols and this has been difficult to     
1:35:53     
Quant qu atively assess organoid variation and Fidelity so these 36 single cell     
1:35:59     
transcriptomic data sets spanning 26 protocols and the one     
1:36:04     
integrated human neural war8 cell Atlas twiddling more than 1.7 million cells     
1:36:10     
they've cited 26 papers here um I mean that's that's still that's     
1:36:18     
awesome right I mean it's it's it's a drop in bucket     
1:36:25     
yeah but um but it's great to see or you know it's a great start and it's it's     
1:36:34     
also just you know um I think something that is also really important is this     
1:36:41     
um this idea of how clear it is what cells are yeah     
1:36:50     
you know so there is this reference at that that Allen     
1:36:55     
Institute um for instance yeah but     
1:37:03     
um uh it's also just interesting in terms of you know the kind of criticisms     
1:37:11     
that have been made about how normal these cells are right     
1:37:19     
um put that together with this issue of     
1:37:25     
um there are cells that it's not clear what they are in the brain in in in in a     
1:37:34     
normal human right like right like um     
1:37:39     
and and you know again back to this idea that like there's a cell type as opposed     
1:37:48     
to it being kind of a spectrum right you know and and so     
1:37:54     
um yeah and yeah so just just it it     
1:38:00     
definitely looking forward to tracking that in terms of how many organoid cell     
1:38:08     
types have been kind of cataloged and and     
1:38:13     
yeah yeah so they say here mapping developing human brain references shows     
1:38:19     
primary cell types and states that have been generated in vitro estimates transcriptomic similarity between     
1:38:26     
primary and organoid counterparts across protocol so they have these exemplars from the developing     
1:38:33     
human brain um I guess from the human adult I don't know what their data sets look     
1:38:39     
like but basically they have this ability to map this to things you see in the brain and you can     
1:38:46     
characterize and that's that's basically what the goal is     
1:38:51     
here so you know it's I guess the the whole aspect of discrete cell States it's sometimes     
1:38:58     
it's kind of hard to know you know what a specific cell type is and get a lot of     
1:39:04     
variation in terms of what they look like what they express so it's nice to     
1:39:09     
have an atlas where you at least have some comparison you know in vitro setting     
1:39:15     
because in the in vitro or invivo setting because in the invitro settings you often you know get things that are     
1:39:23     
not you know seen in nature basically     
1:39:29     
so okay that's great thank you for that uh this is the causal bench     
1:39:37     
challenge a machine learning contest for Gene Network inference single cell preservation     
1:39:44     
data y uh this is five questions with     
1:39:49     
Professor Glu Harvard bioengineer and AI in machine     
1:39:54     
interfaces using technology to treat disease oh this is the the synthetic     
1:40:01     
biology intelligence lab paper here yeah right right before the holidays yeah     
1:40:08     
yeah uh this is endogenous Gene tagging with FN cast 9 to track and sort real     
1:40:15     
lineages from 34 orades yeah that's interesting uh     
1:40:21     
sure deciphering brain organ oid heterogeneity by identifying key quality     
1:40:26     
determinants that's like cell culture sort of yeah yeah and then that's that's     
1:40:34     
and then today's papers that we talked about earlier so any of these other ones that we we kind of highlighted would you     
1:40:41     
like to get into or um I I mean do the the last one the     
1:40:49     
quality the um this one here yeah yeah yeah so I mean you know again just     
1:41:00     
super um super important uh to you know there     
1:41:08     
there's this real issue of quality control right and     
1:41:15     
and you know together with     
1:41:22     
um well yeah what do we mean by quality control     
1:41:27     
right and and what's important for biological     
1:41:32     
systems like like you know     
1:41:38     
so yeah and and being able to understand the difference you know     
1:41:47     
um so uh I I'm I'm always on the lookout     
1:41:52     
for for papers discussing it um as well as yeah just     
1:42:00     
how which of these techniques would be kind     
1:42:07     
of reachable with with a a smaller budget yeah     
1:42:13     
yeah and so yeah this just just bringing up um some of the U     
1:42:23     
um easy to assess things yeah so this is where use faret diameter and then shown     
1:42:30     
in this figure uh and then this is emerged as a reliable single parameter the     
1:42:37     
characterizes brain or quality so you start with like measuring some morphological characteristic and then     
1:42:43     
you go to the expression profile and you see yeah what that looks like so yeah     
1:42:49     
that's that's interesting yeah and you know again yeah it's it's you know     
1:42:58     
want to think about I mean that the the     
1:43:04     
biological intelligence um paper or you     
1:43:11     
know from scratch you know setting up a biological intelligence lab from scratch     
1:43:18     
paper covers a lot of the kind of the infrast structure you need you know the     
1:43:25     
reagents you need um but it's not it's not getting at the     
1:43:33     
kind of the protocols and and um again what what mateline     
1:43:42     
Lancaster identifies as a big problem which is the inability for different     
1:43:50     
research labs to reproduce each other's work yeah um     
1:43:56     
and uh yeah so it it's it's needing to     
1:44:02     
think about this in in you know like we're we're not tracking something     
1:44:10     
important yeah is is the uh we we don't we don't     
1:44:16     
know what we're doing you know and and um     
1:44:24     
yeah just just how crude things are at this point and how to how     
1:44:30     
to move to something that's at scale right um so that that yeah that you're     
1:44:39     
not kind of hand hand rearing each each org     
1:44:45     
um yeah and and just hoping to get     
1:44:51     
lucky um but but and then obviously also dealing with you know some of the issues     
1:45:00     
that I think I think UCSF was one of the first to kind of try to characterize     
1:45:08     
well mainly to criticize the work from San     
1:45:13     
Diego but you know that that gene expression in or of     
1:45:20     
organized cells it is     
1:45:25     
unusual yeah yeah and and you know so that they described it as as     
1:45:34     
um the cells seem stressed um or distressed or yeah well     
1:45:42     
they are they're in a weird environment and they're being pushed and it's an artificial environment with with again     
1:45:49     
artificial signals and and you know and this is where I I think it's going to     
1:45:55     
link you know back to the kind of bongard Lev xenobot kind of work is     
1:46:02     
you're you're you're grow you're     
1:46:07     
you're you're asking for tissue or network     
1:46:14     
like you you want to make predictions about Network behavior from cells that     
1:46:22     
are are in a sense grown in a weird isolation     
1:46:28     
yeah C certainly from their T their     
1:46:34     
expected tissue context yeah right and and so you're     
1:46:40     
giving it you're giving it growth signals and other kind of     
1:46:46     
expression signal artificial growth and expression signals right     
1:46:53     
um yeah anyway you know I I and it's it     
1:46:58     
was interesting the bongard tech Texas Tech talk that I     
1:47:04     
dropped in there yeah um you know you see     
1:47:12     
more about how you know it's really just kind of a     
1:47:19     
fancy embryo manipulation that they're doing yeah     
1:47:24     
right so they haven't they they they haven't gotten into the synthetic     
1:47:29     
biology too much yeah um uh but I think at a certain point I     
1:47:38     
mean like like there's something to be said for that just physical manipulation cell manipulation yeah     
1:47:49     
um in terms of just what what happened happens when we don't use any     
1:47:56     
any but that is of course also     
1:48:01     
super um artificial right right and and     
1:48:07     
like obviously you're gonna you know to build more sophisticated     
1:48:12     
robots biological robots uh um you'll start to be     
1:48:18     
interested in cells signaling and things like that yeah     
1:48:23     
then yeah okay that sounds great uh thank you     
1:48:32     
why don't we move on to some papers now I mean' been talking more Pap but like     
1:48:37     
in another set of topics so we have this uh let's     
1:48:46     
see okay so I actually did want to talk about one more thing before we get to that uh     
1:48:54     
I noticed that the Thousand brain Community thousand brains Community is     
1:49:00     
pretty active and they're doing a lot of interesting things oh yeah so this is     
1:49:05     
their YouTube channel uh a thousand brains project and they've been posting     
1:49:10     
a number of videos on they've been having these brainstorming sessions and     
1:49:15     
posting some videos on this uh so this is one aspect of their Community where     
1:49:21     
they're trying to work out problems in uh you know in video kind of     
1:49:26     
like what we do uh this is a video what is the Thousand Marines project all about that     
1:49:32     
was actually quite useful because it kind of talks about what they're doing um they seem to be kind of yeah uh     
1:49:39     
they're trying to emulate a neocortex they're emulating sort of the the layers     
1:49:45     
of neocortex and using those information processing steps or stages but they     
1:49:51     
notice also that there very standoffish in terms of are we really simulating the brain I mean maybe we shouldn't be     
1:49:57     
surprised by that because you don't want to oversell what you're doing but they're you know they're very much in     
1:50:03     
this area of using the neocortex as a model system or building a an     
1:50:11     
intelligent agent basically and so that they they have a lot of good content on     
1:50:17     
this YouTube channel you gonna say something yeah well I was just gonna say you know     
1:50:25     
I think what you mean by that is that they have they are utilizing a cortical     
1:50:31     
column model right cortical column as being the kind     
1:50:38     
of the the unit of the Neo cortex right     
1:50:44     
and and um     
1:50:51     
uh yeah anyway it's     
1:50:56     
it's you know I think it had a lot to do with their old software project you know     
1:51:04     
the like what was what I thought of is the new menta um open- Source work from     
1:51:12     
you know like 10 years ago yeah um um     
1:51:18     
but you know I I think he is I mean he's certain you know he's aware that there's a lot     
1:51:25     
of other structures in the bra oh yeah yeah and and you know but I I I yeah     
1:51:34     
that's interesting what what's the what's the community I mean is it more than than um is it more than     
1:51:43     
them are they reaching out to other yeah from what I understand it's them they     
1:51:48     
have uh a couple key people in the organization and then they want to get people they want to recruit people to     
1:51:55     
use their their approach so yeah they're using the cortical columns as sort of     
1:52:00     
like the fundamental units of cortical processing and you with the idea is you     
1:52:05     
array these columns like they they are in the neocortex just kind of in parallel you're able to build you know     
1:52:13     
these these basically parallel Computing devices so they have a YouTube channel     
1:52:19     
they also have a website here where they have their Community tag so they have like you know they're doing     
1:52:25     
things like building issues on GitHub they have like uh issues for building on     
1:52:30     
the Monty we talked about Monty before yeah um yeah and so there are people     
1:52:35     
doing like uh doing for request comments and things like that on this um okay     
1:52:43     
yeah so the community is just basically a bunch of people who uh want to build these biologically     
1:52:49     
inspired intelligent systems based on a thousand GR Theory so it's kind of like the theoretical side of like Monty and     
1:52:57     
Numa and all of that because they've been developing these tools for a     
1:53:02     
while uh yeah so that's this is their website with the community Tab and then     
1:53:08     
they actually I have recently I think over the holidays again put out this     
1:53:14     
technical paper and it kind of highlights what they're trying to do with thousand     
1:53:19     
brains so this is Vivian clay who's working at newa she's a key person in     
1:53:26     
this community Jeff Hopkins of course at newa he's another first one of the key     
1:53:32     
people at mementa and then Niles lead Hol who's also at mementa so this is     
1:53:39     
their new paradigm for sensory motor intelligence uh basically they're kind     
1:53:46     
of uh they talking about deep learning how this has driven a lot of progress in     
1:53:51     
artificial intelligence uh despite these advances the creation of intelligent systems that can operate     
1:53:57     
effic effectively in diverse real world environments remains a significant     
1:54:03     
challenge in this white paper we outline the Thousand brains project and ongoing research effort to develop an     
1:54:10     
alternative complimentary form of AI derived from the operating principles     
1:54:15     
of the Neo quartex we present an early version of thousand brains or the     
1:54:21     
Thousand brain system a sensory motor agent that is uniquely suited to quickly learn a wide range of tasks and     
1:54:28     
eventually Implement any capabilities the human neocortex has cord to its design as the use of a repeating     
1:54:35     
computational unit the learning module which are these cortical columns where you have different layers in a column     
1:54:42     
and then you put these columns into the parallel and you're able to use that as the repeating unit of computation and     
1:54:50     
you might argue that that's not really realistic a realistic characterization of what     
1:54:56     
neocortex actually does because it's there's diversity across neocortex as much as those units repeat you get     
1:55:03     
different sensory cortices you get integration cortices multisensory     
1:55:08     
cortices and they're you know the way that processing you know what's being processed of course is different they're     
1:55:14     
trying to make a generic version of these these columns so that you know they're not like beholding any One S     
1:55:22     
sensory system nevertheless in neocortex we see these segregated regions of you     
1:55:28     
know devoted to different sensory systems visual cortex motor cortex sensory motor cortex auditory cortex Etc     
1:55:37     
so it you know it asks it begs the question then are they really being used in the     
1:55:43     
same way or is this is this something that's very highly generalizable in the     
1:55:48     
way that they're proposing but anyways um it's you know it's a learning     
1:55:53     
module that allows you to use qu this sort of columnar     
1:56:00     
organization uh each learning module operates as a semi-independent unit that     
1:56:06     
can model entire objects represent information through spatially structured reference frame or spatially structured     
1:56:12     
reference frames in both estimates uh it's and is able to affect     
1:56:18     
movement on the in the world so it's basically taking and sensor information     
1:56:24     
outputting some sort of motor response or sort of response to the world uh     
1:56:30     
learning is a quick associative process similar to heavy and learning in the brain and leverages inductive biases     
1:56:37     
around the spatial structure to the world to enable rapid and continual learning multiple learning modules can     
1:56:43     
interact with one another both hierarchically and non-hierarchically by the quarle     
1:56:48     
messaging protocol which is something they've used in menta uh creating more abstract     
1:56:55     
representations and supporting multimodal integration so they're really combining uh cornical columns and then     
1:57:02     
this messaging protocol which is of course important for the computational aspect we outline the key principle     
1:57:10     
principles motivating the design of thousand green systems and provide details about the implementation of     
1:57:16     
Monti or first instantiation of such a system this is the code here on GitHub     
1:57:22     
and then detailed documentation on their thousand brings project uh Wiki I guess or what a readme     
1:57:31     
um site so this just kind of goes through the details this is actually     
1:57:37     
they talk here about the need to develop World models so this allows the system to     
1:57:43     
quickly learn the structure of the world and how to manipulate objects to achieve a variety of goals which is sometimes     
1:57:50     
referred to as a world model so I find interesting they're going to World models here as well as a lot of     
1:57:57     
other people uh yeah so they they argue that the     
1:58:03     
Thousand brain system is built with embodied sensor motor learning at its core um yeah I mean this is again kind     
1:58:12     
of the the claims um and and and you know again like not     
1:58:20     
taking anything sorry my is     
1:58:25     
um um is trying     
1:58:31     
to trying to send voicemails for me um     
1:58:36     
but uh this is very like their um you know I feel like this is a     
1:58:43     
rebranding of of what they were doing I forget what     
1:58:49     
the their old project was called um well they had numenta and then they     
1:58:57     
the they didn't really couch it as thousand brains they couched it as kind of like     
1:59:03     
the right right well then he's he he had a book oh yeah yeah I mean and that that     
1:59:11     
was you know I mean again this isn't to take a you know like like at both the     
1:59:16     
Redwood Institute and and then what he was doing together with um     
1:59:30     
sorry the I'm trying to think of the the guy     
1:59:35     
um who ran their open source um project yeah I remember him     
1:59:42     
yeah I can see him but I can't remember his name anyway um that was PR pandemic     
1:59:50     
and he died like right yeah so they I guess they're trying to revitalize the community and Rebrand it     
1:59:57     
a bit trying to get people to use it yeah yeah I mean again this isn't to     
2:00:02     
take anything away from it but like you know this is I do feel like this is very similar     
2:00:11     
in kind of a concept and approach to what what um what they had been     
2:00:17     
doing um and I I think in     
2:00:24     
the you know like the two months ago presentation that they did yeah     
2:00:32     
um I think he brought up because it was     
2:00:37     
like temporal hierarchical oh temporal hierarchical learning yes right right     
2:00:43     
you know like like like that was kind of you know he was definitely trying to say     
2:00:50     
like we're doing something more General and flexible yeah well I think that's     
2:00:56     
yeah that's kind of the generic version of what they or the technical version of what they're doing yeah and then this is     
2:01:03     
kind of like you know we wanna because he did write a book on Thousand brains yeah I remember what it was called but     
2:01:09     
that was a second book so I guess maybe this is more of a more accessible way to     
2:01:15     
kind of approach it but yeah I mean this is a fascinating work I think you know they're really can of uh working out I     
2:01:23     
don't know what the difference is between the two uh really I mean you know they they     
2:01:28     
have some things here where they talk about the building blocks of what they're doing     
2:01:34     
um basically but I think it gets it gets back to this this issue     
2:01:40     
of you know because because Ida     
2:01:47     
mad's nuron naav project is is     
2:01:52     
kind of this um intersection of I'm doing reinforcement learning     
2:02:02     
or yeah like a model free reinforcement learning for for a simulated     
2:02:09     
agent but I want something that's nurly plausible right right     
2:02:17     
right and and it it it's a it's a     
2:02:23     
strange um tension because to some     
2:02:30     
degree the the neurally plausible doesn't matter yeah I know it's what does that mean like is it like it could     
2:02:38     
happen in Sun universe or right is it like really Hue directly to the brain     
2:02:43     
what does that mean and and you know it's just like like do you care about     
2:02:50     
the behavior or well yeah just just just that that that     
2:02:56     
tension yeah yeah and you     
2:03:01     
know and it comes up a lot [Music] in I mean especially you know if you     
2:03:08     
want to try and um make it do you know make it into     
2:03:14     
engineering right like like neuromorphic Computing where it's just like do do I     
2:03:21     
want you know how much do I want the neuro and how much do I want the     
2:03:28     
Computing yeah I think that's you can see that in there like kind of the highlights of like if you look at the     
2:03:36     
list here you have sensory motor learning an inference of course that's something that is behavioral but you     
2:03:43     
know we you know you're generating motor commands could you use that in like     
2:03:48     
something like uh xenobot or could you use it in something like uh embodied robot versus like just     
2:03:54     
generating some motor commands that are yeah you know and then you have modular structure of course you know a lot of     
2:04:01     
things are structured in a modular way not just the brain but that's uh cortical messaging protocol which is a     
2:04:07     
computational abstraction which you know I don't know how closely that is aligned     
2:04:12     
to the biology of the brain but we have computational Neuroscience which     
2:04:18     
predicts that you know there are different types of computational things that the brain does there is voting     
2:04:24     
which of course is something where neurons and different units are     
2:04:30     
participating in Collective Behavior Uh reference frames which of course we know from bio or from     
2:04:37     
neurobiology is something that we see in the brain and and and basically has a     
2:04:42     
behavioral consequence uh rapid continual learning where learning and inference are closely     
2:04:50     
intertwined so this is again like where yeah you're characterizing the learning     
2:04:56     
process yeah yeah yeah and then model free model based policy right I mean     
2:05:02     
it's it's you know um it     
2:05:09     
is it's comprehensive right like like those are all the those are all the     
2:05:14     
things that I want to follow yeah yeah I mean and I I would I almost want to say     
2:05:21     
that the cortical message passing yeah is kind of like the active inference     
2:05:28     
Secret Sauce yeah yeah okay right right where you know because a lot of the basian     
2:05:35     
mechanics Arguments     
2:05:41     
for the the a lot of the arguments about like     
2:05:49     
like this allows us to put everything in one framework is the argument for the     
2:05:56     
cortical message passing right right that like like there is this langua     
2:06:02     
franka of of of multiple systems but that they     
2:06:10     
can then eventually come together um I forget what what what     
2:06:16     
section of the book that is but you know where it's just like like this this is a     
2:06:22     
way I I think thousand brains and active inference people both want some sort of     
2:06:28     
cross modality integration right right so yeah I think that's uh you know     
2:06:35     
an interesting exercise in what we might look towards towards some sort of Bio     
2:06:41     
inspired platform at least uh and you know again they're they're doing this sort of dynamic continual learning which     
2:06:49     
is is you know it's nice goal and it matches everything with uh you know     
2:06:55     
with embodiment and that but uh yeah I mean I think this is where thinking about more um especially getting in into     
2:07:03     
the the software and working out some examples I don't know if people have an interest in doing that but if we do then     
2:07:09     
we should follow up on it I mean it's it's it would be good to check in yeah     
2:07:14     
yeah you know like like again I I love that list right yeah like like you know     
2:07:22     
yeah continual learning's got to be in there you know and understanding yeah it's it's     
2:07:33     
it's trying to bring in anatomy or you know it's trying to bring in the     
2:07:38     
different different brain structures it's trying to bring it you know the the     
2:07:43     
the heart the hard things for for robots to do is still you know picking up a     
2:07:50     
phone you know yeah     
2:07:57     
anyway yeah we'll see okay so the other thing I want to talk about is this paper     
2:08:04     
uh this is a new paper uh this is plus computational     
2:08:09     
biology um Dan Goodman yeah Dan Goodman and     
2:08:15     
colleagues uh this is adapting to time why nature may have evolved a diverse set of neurons     
2:08:21     
so when we were talking about the organoid cultures and things like that     
2:08:27     
we talked about cell types and like you know validating organoid cell types with     
2:08:33     
uh what we see in in in Vivo brains and then you know this is where they're     
2:08:39     
considering why we have different types of neurons we're a diverse set of neurons in a neur neural network if you     
2:08:45     
look to the uh you know the cortical networks that we were talking about earlier as well     
2:08:52     
you know where you have different structures the C the neocortex the strum and the thalamus they're all kind of     
2:08:58     
connected in the Maman brain why do you need that kind of a circuit why can't you just take say take vertical columns     
2:09:06     
and put them together uh directly from the brain stem I mean why do you need all these intermediate structures and     
2:09:12     
these Loops so that's kind of maybe what they're answering in this paper so the abstract reads brains have     
2:09:19     
evolved diverse neurons with varying morphologies and dynamics that impact     
2:09:25     
temporal information processing so their focuses on temporal information     
2:09:30     
processing or in another put in another way it's continual learning because     
2:09:35     
you're learning about time but you're also learning overtime and that in you know processing     
2:09:42     
that temporal component is important um in contrast most neural     
2:09:47     
network models use uh mous unit That Vary only in spatial parameters     
2:09:54     
such as weights and biases so if you have something like a connectionist model you have these units units are all     
2:10:01     
basically the same they don't they aren't differentiated except for their weights and maybe they're bi so they're     
2:10:08     
like purely computational biases and and variation it's not uh you know in terms     
2:10:15     
of what the cells are so you know you can have there's no differentiation say between inter neurons or you know     
2:10:23     
paramal neurons or anything else that you know any classification we can think of that has some functional um     
2:10:30     
differentiation so this functional aspect is uh you know I guess an important thing to kind to figure out     
2:10:36     
why it exists um to explore the importance of temporal parameters we train spiking     
2:10:42     
neural networks on tasks with varying temporal complexity holding different parameter subsets     
2:10:49     
constant we found that adapting conduction delays is crucial for solving     
2:10:54     
all test conditions under tight resource constraints so it's this conduction delay aspect which is important and of     
2:11:01     
course you know there's this whole aspect of the brain being sort of a temporal difference or at least the uh     
2:11:08     
cerebellum doing that but in in the cerebellum you have this uh you know     
2:11:14     
relatively complex circuit that allows the you know uh this sort of temporal     
2:11:19     
differencing but you see this in in individual neurons with in in terms of     
2:11:25     
the biophysics so basically it's this ability to sort     
2:11:32     
of uh gain this temporal information remarkably these tasks can     
2:11:37     
be solved using only temporal parameters such as Del ways and time constants so there are your delay differential     
2:11:44     
equations more than they come in use here uh in terms of modeling temporal     
2:11:50     
delays um and so you you can solve these tasks     
2:11:55     
that they presented to this network using only temporal parameters such as delays and time constraints with     
2:12:01     
constant weights so you're keeping the weights constant the connections between the units what you're doing is you're     
2:12:07     
changing the delays and the and the different time constants so you have you know One Network that has one time     
2:12:14     
constant another network is another time constant and then you might delay within that different connections and so     
2:12:21     
instead of the weights you basically have um you know like a matrix of delays     
2:12:27     
and that can also be very useful for information processing oh go ahead what's what's the     
2:12:37     
the is it like course or conference that Dan Goodman     
2:12:44     
um uh it's uh s sufa or something it's     
2:12:51     
like um like spiking neural sping neural networks conference yeah right right     
2:12:58     
right yeah something like that yeah yeah yeah so yeah that's a whole different world they do a lot of stuff modeling     
2:13:03     
the biophysics of you know uh and then building it into neural network so that's that's what they're doing and     
2:13:10     
then some really interesting results in that Community it's not like I don't know if it's in the mainstream of what     
2:13:16     
we think of what we think of neural network Theory and and well     
2:13:21     
it's definitely because it's it's focused on the spiking but but um     
2:13:28     
um yeah but I I can see it being key to this as well as like you know again it's     
2:13:36     
it's um what it certainly has is the narly pla yes yes that that this is this     
2:13:44     
is you know again like studying these simulations really does give you     
2:13:52     
a better sense of of of how neural tissues probably working     
2:14:01     
yeah in more complex spatio temporal tasks an adaptable bursting parameter     
2:14:07     
was essential so again we had this bursting parameter so this is interesting because this bursting     
2:14:13     
parameter there's a whole literature and complexity Theory and burstiness which     
2:14:18     
is where you get these events that are like non uh non-normal nonlinear events     
2:14:24     
that you know so you get these bursts of activity you don't get this constant activity so when you're doing the     
2:14:30     
spiking of course you have this network with um you know Action potentials and     
2:14:36     
then you have this bursting aspect to it which leads itself to you know lends     
2:14:43     
itself to this sort of complexity the interpretation so it makes sense at that     
2:14:48     
level at least in my mind uh overall allowing adaptation of     
2:14:54     
temporal and spatial parameters enhances Network robustness to noise again we're     
2:14:59     
talking about biological noise and how you have robustness to this noise uh a     
2:15:05     
vital feature for biological brains and neuromorphic Computing systems so this     
2:15:10     
is again a a bio inspired thing that is also very engineering     
2:15:16     
friendly uh so it's you know it's good our findings suggests that rich and adapt ible Dynamics may be the key for     
2:15:22     
solving temporarily structured tests efficiently in evolving organisms which     
2:15:28     
would help explain the diverse physiological properties of biological neurons so the answer that they give to     
2:15:36     
um why we have different types of neurons why we've evolved different diverse sets of neurons is because we     
2:15:43     
need diverse physiological properties we need to be able to create these U these     
2:15:49     
bursty these bursty Networks systems that can sort of     
2:15:54     
distinguish you know time delays and things like that maybe produce different     
2:16:00     
types of time delays so you might have one type of cell that has one type of time delay another type of cell has     
2:16:05     
another time delay and when you network those together then that is it's not so     
2:16:11     
much the sort of the heavy in learning it's sort of something else that's based     
2:16:17     
on these time delays and how they are able to synchronize so this is and then they say in lie of     
2:16:24     
these you know in lie of connection weights you can have a matrix of     
2:16:31     
delays which basically serve a sar function so that's and let's see if we     
2:16:38     
have any figures in here this kind of shows what they're do the schork     
2:16:43     
schematic of the framework for the study so we have this input encoding which are Spike trains remember these are spiking     
2:16:50     
Neal networks output en coding pair options these your Spike counts so you get these Spike trains and you have the     
2:16:57     
spike counts or output and coding pair options Spike trains so you can actually     
2:17:02     
count the spike trains or the spike counts as the output so you have the spiking neural network you have Spike     
2:17:09     
trains as the input you have Spike counts and Spike trains as the output um and then you have this sematic     
2:17:17     
potential which is where you have the Soma of the cell these inputs that you know this s the     
2:17:24     
multiple inputs that come in there's a synaptic kernel which you know brings in the     
2:17:31     
input and there's this delay between the input and the synaptic kernel many of     
2:17:36     
this dendritic filtering which is where you sum sum these synaptic kernels     
2:17:42     
together as then put into the Soma so the voma is the V1 plus V2 plus V3 it's     
2:17:48     
this additive contribution so that's what they're doing in their     
2:17:53     
spiking Ral Network they're taking in inputs and they're have they have a     
2:17:59     
basically an integration rule um and then they have this evolutionary algorithm that they're     
2:18:05     
using which is where they have these initial solutions they evaluate them they sort     
2:18:13     
them by loss function and then they pick the best uh or the elite loss leaders or     
2:18:21     
most loss or something and so the elites are solutions of best performance lowest     
2:18:26     
loss you pick the elites out of this uh selection of of solutions then you have     
2:18:33     
you basically use an evolutionary Al algorithmic approach you generate     
2:18:39     
children from the elites you reproduce those Elite Solutions and then you have     
2:18:45     
this um where you vary this uh in the children where you have random fact     
2:18:51     
you have five children and you keep doing this to get uh different solutions     
2:18:57     
so you're basically improving the solutions from random and you know that's how they're     
2:19:03     
doing this okay so I think that's it for that paper did you have anything else to say about that     
2:19:09     
Morgan no bring bring up the title again yeah I mean I think it's really     
2:19:16     
interesting and and you know especially interested in that the um evolutionary algorithm part of     
2:19:26     
that just because that's a big part of um uh     
2:19:32     
um you know Josh Bard's work um     
2:19:38     
and it's you     
2:19:45     
know yeah we have a lot of cell types because of evolution     
2:19:52     
right like like like it's it's one thing to say like that that's actually useful     
2:19:58     
but it's also it's a bunch of History right right right it's historically yeah but sorry the the I     
2:20:07     
noticed two weird uh references on the uh on the paper just it just if if you     
2:20:15     
bring up the title there's there's um there's so one if you look at kum's um     
2:20:24     
uh institution it says University of Bristol Bristol Southwest England yeah     
2:20:31     
that's that's that's out of [Laughter] place like like is it is     
2:20:40     
it yes like Bristol is in the southwest not a place but then go down a     
2:20:48     
little bit and see the the editor the who it was um yeah so editor University     
2:20:56     
of Edinburgh United Kingdom of Great Britain and Northern Ireland like again like like you know it just seems like     
2:21:06     
there's some weird algorithm that's desd this like as opposed to it being real in     
2:21:12     
the sense that like nobody writes their address is University of Edinburgh and then that weird you know I mean that is     
2:21:18     
the proper name for you kingom yeah but like why was it used there     
2:21:27     
sorry not not totally relevant to the evolutionary algorithm stuff I I think     
2:21:33     
is interesting um just in how people construct those     
2:21:39     
algorithms right you know which is like like basically all of Gecko and things     
2:21:44     
like that right um um yeah just you know it's it's     
2:21:52     
interesting the games you have to play to get something that is akin to to Evolution right and and and how the     
2:22:02     
games are usually very crude right well     
2:22:07     
I think there's a difference between like using an evolutionary algorithm sort of solve an optimization problem     
2:22:13     
and like actually doing like well seeing this is these are evolutionary scenarios which we're going to test because I mean     
2:22:20     
that's really the the maybe the qu better question I said you know okay one     
2:22:26     
one option is that these networks evolved because they needed this sort of diverse time information and then     
2:22:32     
another option might be that it's just historical contingency that you have like different cell types like we have     
2:22:39     
with the organoids that sort of they evolved and then they integrated into     
2:22:44     
networks and then that's what we have so I mean you know you could test those hypotheses using an evolutionary     
2:22:51     
algorithm by the way but also it's a more direct test of like the evolutionary imper yeah yeah I mean this     
2:22:58     
kind of goes back to the the cisc stuffff and the the     
2:23:07     
um what was that that reading group that they were doing in terms of comparative vertebra oh yeah the comparative Anatomy     
2:23:14     
yeah yeah you know     
2:23:21     
well we'll follow up I I wanted you know again thinking about like neuron     
2:23:28     
relative to to just doing model-free reinforcement learning     
2:23:35     
yeah um it made me think that like how much     
2:23:41     
yeah how much do we have in terms of non-human     
2:23:47     
primate comparative Imaging um that we could actually look at some of     
2:23:55     
these things and and make yeah inferences or you know get any insights     
2:24:04     
um and that that like that would be interesting stuff to pull together again thinking about kind     
2:24:11     
of bongard you know kind of work     
2:24:17     
um well as well as like the whole brain emulation kind of work right where it's     
2:24:23     
just like hey we can get all this structure how much does it really tell us and and how much is it telling us     
2:24:30     
that you know how much is is it telling us that is relevant if we're missing the     
2:24:36     
kind of The evolutionary context in which it it developed     
2:24:42     
right specifically in terms of its functionality or you know like like how     
2:24:49     
it's being repurposed over these years and like     
2:24:55     
what what limitations are there on that repurposing there we can     
2:25:02     
um we can follow up I gotta all     
2:25:07     
right good all right good good discussions um let's follow up on slack     
2:25:14     
and see you next week sure all right take care take care bye bye     
