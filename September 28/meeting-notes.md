## Meeting Recording

[YouTube link](https://youtu.be/rPrPLh6tueA)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113217637653956650)

## NOTES:
Big Brain Project/HIBALL conference.

* global EEG meeting. 


Meta: spending is bearing fruit.

* CTRL-Labs (pronounced control).

* Bergeron -- won a Kaggle BCI dataset performance.


CTRL Labs based in New York. MOABB paper, hired in person from group. NiLearn.

* SciKitLearn project -- reliability, accuracy from motor imagery.

* motor control in amputees -- still peripheral nerve-related EMG.

* gestural control -- deemphasizing movement. Hand can be still and you still get a usable signal.


Project Northstar people -- gestural computer vision. Stereo camera iPad attachment.

* photostitching a 3-D model. 

* 2019: Facebook had a brain imaging group.

* what was going on in company at that time. Ultimate UX/UI.


Demos that remain Demos -- a problem.

* PiEEG -- shield, attaches on top of a Pi. Open-source hardware.

* Brain Box initiative -- new Neuromodulation tech. Commercial arm makes tFAS systems (excitement in start-up world. SF, South Bay, LA).

* TMS systems and TES devices. 

* masterclass in Brain Imaging on YouTube.

* OHBM -- educational days. Eight presentations on cortical surface precision, imaging (whole-brain dynamics).


Receptor mapping. Big Brain started in brain slicing. Minimal Cell Workshop @ Ventner Institute (YouTube).

* 10um resolution, can see every cell. Traverse brain. Eulich -- German supercomputing.

* eBrains -- first generation of Big Brain good for computational Neuro people, now its Brain Imagers/fundamental researcher's turn.

* what is clinically relevant? Brain innovation. Global brain consortium (globalbrainconsortium.org).

* mind-brain clinic -- first 30 years of EEG.


Jesse: intrigued by Question Space, complexity theme --> complexity explorer.

* David Krakauer's work. Where is this relative to complexity in general?

* what is Bradly or Morgan's take on complexity? 

* teleonomic manner -- what is this? 


Vision: interesting. Sean Carroll, Mindscapes.

* teleology paper is very interesting. Different layers and tools. Developing theory and tools.

* what happened to Cybernetics? Cybernetics --> complexity pipeline, Cybernetics.

* computing science pipeline. NECSI, Complexity Hub.


Histograms are nice and neat. Tukey's Historical Data Exploration (1960s).

* new representations of the data (non-parametric, alternative to Pearson, Fisher).

* Tufte to UMAP --> what tests should you do to see if these models are appropriate.

* non-normality, homogeneity of variance.


Had to do averaging in 1960s, only thing that was algorithmically-computable.

* SVD-based approach, space-time-trails-subjects.

* visual system can bring out structure from plots.


ORAC --> organoid research and augmented computing (a.k.a. organoid intelligence). Where do biological models become relevant for computing?

* problems with ERPs --> beyond averaging -- single-time sturcture, joint time-frequency plots.

* event-related spectral perturbations. # of components for dimensionality reduction --> denoising, demixing.

* ability to get "work" done from biological systems is a far-off goal.

* which organisms are interesting to hijack for minimal cells?

## TRANSCRIPT

0:02     
hello good morning morning hello     
0:09     
Jesse all right so why don't we get started     
0:14     
um I ien like to go not quite ready but I'd like to go over the um the big brain     
0:22     
highball conference oh okay yeah that'll be good we we'll do that there's there's     
0:29     
another there's another one that was like like a     
0:37     
global I'm not remembering the name exactly but it was basically a big EEG     
0:43     
meeting that had a lot of really interesting stuff um let me just pull together     
0:51     
my some some slack things from Nar okay sounds good thank you so this week has been     
1:00     
interesting uh we've had uh our dvoor meeting where we finished up our summer     
1:06     
of code projects um we had the hyper Divo graph and we had the growing graph     
1:14     
neural networks and they both turned out they both got submitted uh Hussein updated us on some     
1:22     
of the stuff he's been doing with uh Medical Imaging he's been doing some pretty     
1:28     
nice uh you know medical physics and he's been doing there's a     
1:33     
channel in the slack breast cancer CT and that's the one he's been posting a     
1:38     
lot of updates to so you might join that if you're interested in that topic we also covered kind of an aspirational     
1:46     
paper on Cell modeling using AI which of course is uh you know it's a it's a sort     
1:53     
of a quest in computational biology to kind of find a way to model a cell and     
2:00     
so there were there was a large group of authors who proposed how we might do     
2:05     
that with AI uh interesting but aspirational paper in the cognition Futures meeting we     
2:12     
talked about behavior thology and purpose and this is a classic cybernetics paper by Rosen blue that all     
2:19     
where they kind of go through um sort of the hierarchy of uh feedback or how feedback is     
2:26     
relevant to say generating Behavior and we talk about Behavior could be     
2:32     
behavior of an agent could be behavior of a machine whatever some of that being thology some of that being sort of the     
2:39     
RO of higher order feedback and so forth and then of course uh we kind of linked     
2:45     
that to the paper we did earlier on uh 21st century machines living machines by     
2:52     
bongard and 11 and then we had our cybernetics meeting where we kind of     
2:57     
went through the references or our uh ever good regulator theorem paper so     
3:03     
definitely a good set of meetings this week let's see I can go through I know     
3:09     
Morgan's probably not ready yet I can go through some things from this week that I have so this week uh     
3:17     
was meta connect and this is an event where they go over their new     
3:23     
technologies they're kind of you know uh things that they want to preview that     
3:29     
are coming out soon or being released now so they had a number of consumer     
3:34     
products and then they highlighted this headset that they're working on this is     
3:40     
the Ryan AI glasses uh so this is something that they debuted at metac     
3:46     
connect that's not available to to buy yet but it's like this thing that they're kind of working on where you can     
3:53     
do augmented reality in a pair of glasses that you might wear and it would     
3:58     
be more or less a distinguish from a pair of glasses that you might wear um     
4:03     
you know walking down the street so they're using wave guide technology to to render the Holograms in front of your     
4:09     
eyes and everything is like it hosted in the uh in the arms of the glasses and     
4:16     
it's projected outward into your field of view and then there would be some Puck system that you would hold or put     
4:23     
on your belt clip to supply the battery and Supply the computation FS that's the     
4:30     
thing but the other thing they talked about was this wristband and this wristband is actually what they consider     
4:37     
to be a neural interface so um that's what we'll talk about a in a little bit more detail so     
4:43     
the neural interface picks up uh EMG signals at the rest and it translates it into just     
4:51     
basically gesture control uh signals so you're picking up the muscle activity at     
4:57     
the wrist you're producing gure signals that you know you can't necessarily do     
5:02     
with hand tracking or eye tracking or some controller and you're using it in that     
5:08     
environment so it's a very nice technology I'm not sure how well it works but one of the things that came     
5:14     
out of our discussion on this was that uh Morgan pointed out that um uh Ctrl     
5:22     
Labs was involved in this um in developing this neural wristband so this     
5:27     
is the neural wristband where you you have high performance EMG sensors on the     
5:33     
on the wrist you have this processor that integrates EMG signals to produce input events on device you have a haptic     
5:41     
engine that provides tactile feedback so it's you know there's this bir directional feedback at the at the     
5:49     
surface interesting that uh Morgan brought up Ctrl because I uh wanted to     
5:57     
do a little bit of a deep d into what they've been doing in their history with [Music]     
6:03     
meta so this is the uh an article from I think     
6:10     
2019 and so uh maybe Morgan can tell us a little bit about Ctrl labs and sort of     
6:16     
the background there but this is where Facebook acquired neuro interface startup Ctrl labs for its mind reading     
6:23     
wristband and so the deal is reportedly worth between 500 million And1 billion     
6:29     
dollar I remember at the time people were criticizing meta for buying all these     
6:34     
companies and you know spending all this money on um on VR and AR and so but it     
6:42     
looks like that is actually bearing fruit now you're getting this yeah we'll see still yeah um go     
6:51     
ahead it does it does go back to you know it goes back to     
6:57     
their I mean their VR right right so like you know this this time when they     
7:03     
were willing to spend I mean Lord it actually just took me a minute     
7:11     
to remember that um that they were calling it The metav oh right     
7:20     
yeah yeah yeah yeah and um I mean I     
7:26     
don't I don't know if that's my Dementia or just how unmemorable that technology     
7:32     
was but um um yeah     
7:38     
so control Labs is is what what people call it and     
7:45     
um and you know I don't actually remember who are the ones that started it but but our our connection with Nur X     
7:55     
is that um Alexander Bell who     
8:00     
um I I think got um some notoriety uh um I want to say like     
8:09     
2013 like like quite a long time ago now um for uh his performance on a     
8:16     
particular kaggle data set that was like um like a BCI kagle data     
8:25     
set and um associated with     
8:31     
that well separately from that actually um he was an EG     
8:39     
researcher um in I think in New York     
8:44     
that might explain it too because I think control Labs is based in New York okay     
8:51     
um uh anyway he he had started     
8:57     
um uh some some sideline projects um uh     
9:05     
a little like um a little like the pi um webcam like     
9:13     
ey tracking guy where he he started a a project where he was um writing     
9:20     
interfaces for kind of consumer EG devices so that you could collect data     
9:27     
from yourself it was basically doing like like how how you could do Erp     
9:33     
studies with with these consumer e devices that were only that cost only     
9:40     
like $200 and um uh     
9:48     
then uh but it was then like 2017 or something like that he also started um a     
9:56     
project called um Moab or the mother of all BCI benchmarks and um that was     
10:05     
um uh that was really like that was very much like a kind     
10:12     
of crowdsourced projects on neurot X or     
10:17     
certainly you know he used he used the community um to kind of gather data sets     
10:25     
and and pull together this this kind of psych learn related     
10:32     
um project where you were uh looking at     
10:39     
reliability and and you know accuracy of um     
10:45     
various mostly motor imagery um data sets but but looking     
10:52     
across multiple data sets and multiple algorithms which which algorithms were     
11:00     
were um yeah performed the best right so kind of dashboard of     
11:05     
those very again like very in line with kind of like a kaggle like thing but but     
11:13     
again this was like a kind of you know related to or very very um     
11:21     
modeled on Psychic learn as a project and part of that was that again like     
11:27     
because he was French and because the I could learn team of French that like he     
11:33     
there was a lot of overlap there and um and you know it definitely     
11:40     
got a little bit of of um kind of help and and inspiration from um narn or narn     
11:49     
whatever ni learn which was the the FM um machine learning package that um     
11:57     
from um oh um Olivier gel and     
12:02     
um uh I'm blanking on the I'm blanking on the big guy     
12:09     
um anyway it'll come to me yes that that's definitely age related and um     
12:18     
uh anyway so sorry just just to give you a little backstory in terms so so we     
12:24     
like like then the other thing is that you know he was hired the Moab paper came out I I think he was control L at     
12:32     
this point and he he hired in I think     
12:37     
maybe somebody else that had been involved with     
12:43     
Moab um I'll find these in a second but um um     
12:49     
but then we haven't heard from him since it's it's like he disappeared yeah and as well as you know they you see these     
12:57     
kind of control AB demos from like years and years ago     
13:03     
right yeah and then just nothing you know um uh anyway might might talk a     
13:10     
little bit to might talk a little bit later about Open Water Health but this is kind of     
13:15     
like the same thing like you get these demos and it sounds really promising but then we don't see anything yeah yeah     
13:23     
it's all like under security like under NDA or whatever you know supposedly they're     
13:30     
waiting like like there was one of the kind of     
13:38     
metaverse presentations or supposedly you know big announcements like you got     
13:45     
a you got a an EMG demo too um but yeah     
13:52     
anyway so super cool looks like there might be a product coming out it's not     
13:58     
dead yeah wow so yeah so one of the big things about this technology is of course the     
14:04     
movement artifact and and getting that calibrated so that it's useful as a     
14:10     
control signal so I mean you're you know is it that you're actually controlling     
14:15     
recording the EMG and its components or recording movement artifact and its components and it could be you know that     
14:22     
that's somewhat useful but right it's not it's interesting right and and it um     
14:31     
it also it kind of relates to um motor     
14:37     
control in um amp right you know like like you can you     
14:47     
can even when potentially you know the hand is     
14:53     
missing the the the there's still enough of the kind of     
15:00     
you know peripheral nerve or the yeah the EMG that's that is     
15:07     
still detectable yeah and um um they     
15:13     
definitely trying to get it um you know so     
15:19     
so another thing that's been very popular is of course the The Minority Report     
15:24     
interface um apparently that was the first movie to kind of popular this kind     
15:30     
of gestural control or something like that anyway I'm not sure why that movie got so     
15:35     
much gets gets to to be the name for this but um uh     
15:43     
um they definitely though like like I I'd heard that they were trying to     
15:49     
deemphasize like your movement like you should you should have to move as little     
15:55     
as possible but still be able to kind of control the you know to get the     
16:02     
UI kind of interactivity if you see what I mean     
16:08     
yeah yeah it's like like like your hand could almost be still and and um anyway     
16:15     
I I think they they they they hit perhaps some you     
16:22     
know what we academically interesting problems with the yeah yeah     
16:29     
with it as well you know yeah uh uh which which I I would say you     
16:36     
know I mean I've said this before which I would say is true with kind of all     
16:42     
VR you know I mean and that like like there's still a really good reason that     
16:47     
we're not all strapped in like some early kind of Facebook     
16:53     
metaverse you know announcement papers and stuff or you know demos and things     
16:58     
yeah yeah so Jesse said something about uh 100% are demos that remain     
17:05     
demos yeah it's like the problem with demos and demo or die is that it's like     
17:11     
the demo is not the end of everything but like sometimes people just kind of     
17:16     
get stuck in the demo and anyways um yeah so continue on um so     
17:24     
they bought uh control Labs back in 2019 they spent a lot of money on it they     
17:30     
people kind of disappeared um BOS who's the head of a and VR at Facebook Andre     
17:37     
Bosworth uh talked about kind of how this was going to be like part of the you know developing this technology at     
17:45     
scale and getting it into consumer products they actually in 2019 also     
17:50     
published a series of patents around the myo armband which is the demo that you     
17:56     
know I think uh Morgan was talking about uh and this was of course developed uh     
18:04     
by North formerly known as thalamic or thalmic Labs the myo armband measured     
18:09     
electromyography or e or they say EEG it's EMG to translate muscle activity     
18:15     
and dig gesture related software inputs but North moved on from the product and now makes a stylish pair of Air glasses     
18:21     
known as focals so this is you know kind of talking about how you might use a     
18:27     
wristband uh Bosworth says control Labs zband will be instrumental in developing new ways of interacting with machines     
18:35     
without needing traditional mouse and keyboard setups touch screens or any form of physical controller whatsoever     
18:41     
so this is kind of like why they're doing this and of course you know it's it's a nice um nice idea but you know     
18:48     
it's actually you know it's interesting that uh the Apple Vision Pro was     
18:53     
released uh with it tracking and isolating so you can use it tracking to     
18:59     
select objects in the environment and it does natur ship with controllers so     
19:04     
people have been trying to you know it it it it works to some extent and I     
19:09     
tracking of course is further along than this kind of Technology while people are trying to attach ey trackers to their     
19:16     
Vision Pro because it's not like the ideal inter the ideal     
19:21     
interaction uh you know medium so you know it really depends if you know I I     
19:28     
guess there two challeng is here one is to get this to work at you know at a good resolution so that it's controll     
19:34     
that's a seamless as say I could controller or keyboard or whatever which is not seamless but you know what I mean     
19:41     
the second is that um you know will people use this mode of interaction and     
19:47     
view it as like equivalent to some other mode of interaction in other words they     
19:52     
just pick it up put it on and be able to use it like you might use a mouse and you don't think about using a mouse too     
19:58     
much it's kind of natural to you because you you know we've had them around long enough and you know quite frankly     
20:05     
they're actually pretty good at like moving up and down the screen and and cl pointing and clicking we have that set     
20:12     
of interactions in like you know um in muscular neuromuscular control that we     
20:18     
have with the mouse that's going to be the challenge of course um so yeah this is definitely something     
20:25     
that you know they're kind of working on to get out into the world um so it's you     
20:31     
know I think farther along than it was but we'll see uh so this is another     
20:36     
article here where this is from 2019 this is a bold prediction uh C uh     
20:42     
control lab CEO will have neural interfaces in less than five years so this was Thomas Reen the CEO of control     
20:50     
labs in 2019 uh talking about you know how we're     
20:55     
going to have these kind of neural uh neuromuscular control devices in five     
21:02     
years now it's five years today right now so you know we uh don't really have     
21:08     
that yet but this is you know of course the predictions that one makes when     
21:13     
you're a tech person um or a tech CEO so uh this is basically the sort of the     
21:20     
outline of what um what a neurocontrol uh unit looks like so let     
21:26     
me zoom in people who need to know how this works so you have the uh you might     
21:33     
record from a single muscle or you know you you you're going to have something that's on the outside of the skin so you     
21:40     
know sometimes in uh like medical uh you know in experiments with animals or in     
21:47     
medical settings they'll insert an electrode near the under you know subcutaneously near the muscle or you     
21:54     
know something like that so they can isolate the muscle in uh surface EMG you     
22:00     
know you put a an electrode kind of on where the muscle is and you try to fix it to the skin so it doesn't fall off or     
22:08     
start recording from another muscle or get in between the muscle muscles and     
22:14     
record movement artifact and things like that so it's pretty hard to actually get the recording you know uh get the right     
22:20     
target place where you want to record from then you uh bring it     
22:26     
into um you know set of uh uh signal     
22:31     
processing devices um you have uh this preamp you have an encoder you have an     
22:39     
oscilloscope and then you have oscilloscope and camera and you can actually basically uh you know get this uh muscle     
22:48     
activity rectify the signal clean up the signal uh you know and then use it as     
22:55     
some control signal for um a device so this is you know a pretty big challenge     
23:02     
a lot of the signal processing is well known people know how to do that more     
23:07     
more or less but the real challenge is a understanding what the control aspect is     
23:14     
in other words what is the sort of threshold for moving your wrist in a     
23:19     
certain direction so you have to really kind of you know if you if you're either moving your wrist or not that might be a     
23:26     
easy problem but when you're making these you know movements that are kind of gradual you're making these subtle     
23:32     
movements in in especially in the hand muscles because they're not that big it's hard to know kind of you know     
23:39     
if you want to say recognize certain hand movements or hand gestures that's a lot harder problem and knowing what that     
23:45     
signal should look like and selecting that signal and segmenting it out of this time series out of the trace that's     
23:52     
the thing that you really have to work on and get to but also recording from the right site so having a device that     
23:59     
will fit and and you know conform to the hand and the wrist and things like that     
24:05     
so this is definitely you know again you know Big Challenge uh they have a lot of     
24:10     
good people working on it and it's you know really one of these interaction     
24:16     
modalities that is up and coming so we'll see how this works out and so this     
24:22     
is an article in 2021 so this is another research prototype human computer inter     
24:28     
action at the wrist so this is a meta press release where they talk about this     
24:33     
rist based interaction for the next Computing platform and so this is where they're kind of talking about     
24:40     
how uh you know why the wrist so there are many other input sources available     
24:46     
all of them useful voic is intuitive but not private enough for the public sphere or reliable enough due to background     
24:52     
noise a separate device you could store in your pocket like a phone or game controller adds a a friction between you     
25:00     
and your environment in other words you have to pick it up and use it um and you have to um you know if you're in like     
25:07     
say AR or VR you know you have to coordinate that device with the other device you're caring on your head so     
25:14     
it's you know it's hard to kind of remove all that friction VR in general     
25:20     
has a lot of friction because you're trying to coordinate kind of this headset and then you you're coordinating     
25:26     
devices and you're trying to align your body to the world and you're trying to bring up things in your field of view     
25:33     
and uh it there's a lot of friction in modern design especially like what meta has been doing in terms of their uh     
25:41     
platform there's just a lot of friction by nature in VR and so is something we     
25:47     
want to reduce as much as possible as we explored the possibilities placing an input device at     
25:53     
the wrist became the clear answer the wrist is a traditional pie place to wear a watch meaning it could reasonably fit     
25:59     
into everyday life and social contexts in other words you know people are used to well I don't know how much people     
26:05     
were uh watches anymore but you know people have that metaphor of wearing a     
26:12     
wrist watch checking their wrist having something on their wrist it's not like     
26:17     
something weird that you wouldn't know how to deal with because people know kind of how to deal with a     
26:22     
wristwatch um and you can use it in everyday life and social contexts you     
26:28     
know you don't have a sensor sticking out the right side of your head and uh     
26:34     
you know looking like a brain slug or something so it's it's you know not uh     
26:40     
jarring to people I guess I don't know anyways that the idea is that it's you know kind of like this social affordance     
26:47     
it's this physical affordance it's not obtrusive and it reduces the friction in     
26:53     
the environment and so uh risk-based wearable has the additional benefit     
26:58     
benefit of easily serving as a platform for compute battery and antennas while supporting a broad array of sensors the     
27:05     
missing piece was finding a clear input to clear path to Rich input and potentially the potentially ideal     
27:11     
solution was EMG which they talked about here the signals through the wrist are so clear that EMG can understand finger     
27:19     
motion of just a millimeter so if you move your fingers you notice that at your wrist there sometimes they're like     
27:26     
these it kind of moves there's some you can feel some movement at the wrist and that's because you have     
27:33     
tendons and muscle that are connected through the hand so you can actually pick up finger motions through the wrist     
27:39     
and so if you're recording from those muscles you can get that signal now that     
27:45     
doesn't mean that it's easy to get acquire it just means that you can do it     
27:50     
this means that input can be effortless ultimately it may be possible to sense just the intention to move a finger this     
27:57     
is of course coordinating this with some of the things we do in brain machine interfaces or recording Preparatory     
28:04     
signals in the premotor cortex and coordinating all of that so     
28:11     
basically you're recording the output of the peripheral nervous system specifically the nerves outside the     
28:16     
brain that animate your hand and finger muscles so that's basically and then     
28:21     
there's this whole mind reading thing that people get into um but yeah this is another EMG     
28:27     
demo this is controlling virtual objects so you can see that the hand is you know you're moving your hand there's this     
28:34     
device on your wrist and you can actually control things in a virtual environment you can reach out for things     
28:40     
grab them using that signal the virtual hand will contract as well and you have     
28:45     
this seamless hopefully seamless interaction uh then there's a typing demo where again you can type things on     
28:52     
a table and it can be interpreted as typing on a keyboard so you know the     
28:58     
fingers are moving to certain locations and you know the system can     
29:04     
reconstruct s of keyboard keyboard swipes or keyboard presses so that's     
29:10     
another demo they have so you know these are all kind of if you're interested in in this you would uh there there are a     
29:17     
number of demos they did back in 2021 so that's uh yeah so that's that's     
29:25     
stuff sorry sorry I I I was trying to remember the company     
29:31     
that had um you know it was basically a stereo     
29:37     
camera that that sits on the desk you s     
29:43     
sits um like where your keyboard would and     
29:49     
it's it's using computer vision not not I mean it wasn't quite     
29:56     
typing but but it was giving you the gestural um yeah recording the gestural     
30:03     
movements again this this this has to be age related     
30:08     
dementia um     
30:15     
um a lot of those people that company started project Northstar which     
30:23     
is like an open source BR yeah headset company anyway if you if you yeah if I     
30:31     
Google them get the name of that other company     
30:38     
and uh I think they     
30:44     
pivoted um I mean this is just you know like archaeology of of various San     
30:52     
Francisco startups I think they they pivoted to take their their sensor that that     
31:01     
previously sat on the desk yeah and attached it and and then it became a     
31:08     
stereo iPad attachment stereo camera iPad     
31:14     
attachment and and I do remember this then Robert     
31:20     
ELD at daers uh     
31:26     
um so robt new devel is the the like original developer and lead developer of     
31:33     
field trip which is a um pretty pretty widely used um EEG EG um mat lab     
31:43     
analysis package um he he had this uh he had a     
31:51     
demo of using an iPad and then you know basically walking around the subject     
31:58     
that's got you know EG on right and and doing like you know photo     
32:06     
stitching to to get the electrode POS you know basically he makes a by moving the cameras around he makes     
32:14     
a 3D head model and and gets the electrode positions on the head wow     
32:22     
okay and and um     
32:28     
yeah like we're we're like two companies three projects away from the original     
32:34     
thing but it just I was you know like like the EMG picking up the hands the     
32:43     
other others have have kind of tried to do that same you know I want to move my     
32:48     
fingers in the air but then like I'm gonna use computer vision or something to to figure out the the keyboard or or     
32:57     
project you know using light to project a keyboard onto um a surface and then     
33:03     
using that yeah um yeah H back back at     
33:09     
this time it's also good to remember Facebook had an image like a brain     
33:14     
Imaging group okay like like a fullon     
33:21     
high-end uh super fancy brain Imaging group that was doing um like whole brain     
33:29     
near infrared it was it was     
33:36     
doing I might go as far to say kind of weird     
33:43     
bra yeah and uh um again I need to Google     
33:50     
you you can see like like around that time maybe a bit later     
33:58     
um we would get these pictures of what their brain Imaging room looked like and     
34:06     
and because it was near infrared there were these cool like you     
34:12     
know Matrix style kind of you know imaginings where you know     
34:19     
you've got this thing coming down and it's got like you know like a hundred     
34:26     
fiber optic cables that are yeah coming to a helmet and like     
34:34     
like I think it just speaks to yeah yeah like like what was going on     
34:40     
in the company at that time in terms of just like all all this     
34:48     
work kind of with the focus of of     
34:53     
um like ultimate UI right yeah or or you know ultimate     
35:00     
ux yeah right right um extreme ux the     
35:07     
extreme extreme um yeah any so you know I I I     
35:17     
still wonder how much this is um you know maybe to Jesse's point in     
35:26     
the comments like how much this is just like we we've got we've got we've had     
35:32     
these these Technologies sitting or you know we've had these guys working in     
35:37     
these back rooms for for like 10 you know five plus years you know     
35:45     
um hey this you know we we should we should roll this out or you again like I     
35:52     
don't know will we ever see this device yeah you know or or will see like one     
35:59     
one you know consumer iteration of it and then it'll     
36:04     
yeah yeah yeah oh okay yeah so yeah would wouldn't     
36:11     
be the first wouldn't be the first uh you know tech tech fizzle the fizzle out     
36:18     
yeah yeah te yeah yeah there's some open science resources     
36:25     
I wanted to share um this is from ASAP bio this is uh introducing a prototype     
36:32     
directory of organizations and initiatives in open scholarly communication so this is uh ASP bio is     
36:41     
an organization that Champions open science practice largely in the form of     
36:46     
preprints but other types of uh open science activity that stresses     
36:52     
replication and uh you know other things um that you know disseminating     
36:58     
scientific information so this is uh basically this list that they have of     
37:05     
different organizations and initiatives uh you know one of the things they do of course is to sort of     
37:12     
create resources to help people navigate the space there's a lot there are a lot of weird terms if you're just coming     
37:18     
into the field a lot of organizations and you may not know what they are so     
37:23     
that you can get on board with the whole practice of of open science you don't have to spend a lot of time kind of     
37:30     
wondering what things are we have you know all sorts of different things uh     
37:36     
pre-print servers uh advocacy organizations uh open science     
37:43     
organizations infrastructure like curve note for example um uh different     
37:51     
companies uh different journals that are involved in open or or open science     
37:58     
oriented the knowledge Commons so yeah it's just like a a huge     
38:04     
list of organizations that do work in this space     
38:09     
you know this is something that if you're you know interested in knowing like if you're they're doing a certain     
38:15     
thing in your area of Interest like zoto or zenodo you can find out what those     
38:22     
um organizations are their contact information and so forth     
38:27     
so they've produced this list uh they also have this set of     
38:33     
definitions so for the purposes of determining what organizations and initiatives to include on the list we     
38:39     
Define open scholarly Communications is any organization or initiative that     
38:44     
focuses on improving openness and transparency in the scholarly Communications process this definition     
38:51     
encompasses open access to research but extends well beyond access to include issues such ASE preprinting     
38:58     
improvements to peer review curation Services open- Source infrastructure     
39:05     
research lify life cycle publishing and more so this is something that's useful     
39:11     
I think for a lot of different people coming into the area and I think Morgan is ready well     
39:20     
speaking a couple things that um that were talked about on the MCH X slack     
39:26     
here um so one is a new um Pi     
39:31     
EEG um which is like basically yeah what it sounds like where somebody's made     
39:38     
a a shield EG Shield you know so attaches     
39:45     
attaches on top of a pie um um that's that's     
39:54     
um interesting I mean I I don't want to say it's like a spin-off from University     
39:59     
of Edinburgh it seems like it's a a student at the University of Edinburgh who has a who has a side gig as as this     
40:08     
Open Source Hardware developer but but it's really you know it's nice um and um     
40:16     
uh so let let me let me use this as as an opportunity again     
40:24     
to suggest people join our techx to to to catch all this on slack okay     
40:31     
yeah and the nice you know one side benefit of nurx SL um we keep our     
40:38     
history you know like I'm not sure for how long but we still we still have our     
40:44     
history um uh yes     
40:52     
so um lots of things in terms of     
40:57     
and F news stuff and um apologies well the last     
41:06     
week and this this would have been right be before last Saturday's meeting I     
41:13     
think yeah um brainbox initiative is is another meeting that     
41:20     
um is that that finished up before before our last week meet and um     
41:28     
it's definitely one of the the kind of premere meetings where     
41:34     
um people working on new neurom modulation uh Technologies and and kind     
41:40     
of science G are gathered um so brain     
41:46     
box like like I'm not sure exactly they they're an organization but     
41:55     
I think they also have a commercial arm where they sell things and and     
42:00     
definitely one of those um I believe     
42:06     
they have or they are reselling a um tuss one of these trans cranial     
42:14     
focused ultrasound systems um but I I think they might resell you know TMS     
42:20     
systems so there's the magnetic coils that that people use to you know induce     
42:28     
uh activity in the brain um and other like Tes devices and are a     
42:38     
great source of webinars yeah um like pres presentations     
42:46     
again like uh I think to a certain extent     
42:51     
because they are a re you know it's their business but in terms of the people that     
42:59     
they get to do these presentations um brain bro is great you know like like they they get uh they     
43:06     
really do get like top people and um I I'm I know that the first time that I     
43:14     
saw a webinar or you know I saw a web presentation on focused ultrasounds it     
43:21     
was um Leonard uh PES     
43:29     
um the researcher at daers and um and     
43:35     
he's now the the head of science for this startup here in San Francisco     
43:41     
called nudge where you know there there seems to be a kind of     
43:50     
um yeah there there's a lot of excitement in the in the startup world     
43:56     
for for tuss so it seems like there's three     
44:03     
three companies not necessarily all based in San Francisco like well San     
44:09     
Francisco like down South Bay and then down in La um so really really interesting um     
44:19     
Technologies and and the nice thing about brainbox initiative and I can I'll     
44:24     
find links um I think they just made all their posters     
44:30     
available online and they definitely will you find all their videos on     
44:35     
YouTube from the the conference so BBI 24 brain     
44:42     
box um but uh um yeah     
44:53     
the just uh so the um yeah the eighth big brain Workshop     
45:00     
2024 uh happened in Padua Italy um     
45:06     
that's um I don't know why I immediately think of Shakespeare but um um     
45:14     
yeah and yeah so big this is um like it's got     
45:21     
a hard to remember website for the event but um Big Brain Project     
45:27     
is uh big brain project.org big brain projecten     
45:35     
word yeah yeah big brain project.org let me see if I can bring it up here     
45:44     
yeah um     
45:50     
yeah and so as this I mean certainly     
45:55     
this is how it starts is if you you know just on their their web page creating the next generation of highly detailed     
46:02     
human brain models by building on the big brain oh right     
46:09     
so I gotta say this is this is lazy naming     
46:14     
yeah um and um because I've had to work with this uh     
46:22     
this particular company's products and the company's name is brain products and     
46:29     
I just want to say that that's the crappiest uh search name     
46:35     
right like if I'm trying to Google stuff for brain products you know tech details     
46:43     
it's just like I get all sorts of brain     
46:49     
products um don't use brain in in yeah in the     
46:54     
name yeah um uh but I gotta say that this uh this     
47:01     
particular meeting um you know is all on YouTube um and let me just get     
47:15     
the yeah as as big brain project     
47:20     
um and it has been a a total master class in brain Imaging     
47:27     
like like you know I mean the three three sets of of     
47:35     
um like big conference uh uh video drops happened like this week um so ohbm which     
47:45     
is the biggest um human brain mapping conference the the O is for organization     
47:51     
of human brain um they dropped all their     
47:58     
educational uh educational days that are kind of     
48:04     
pre-conference um uh Workshop tutorials kind of thing if or you know you know     
48:10     
what I mean yeah yeah and um     
48:17     
uh I I thought those were good right so that was that was like you know again     
48:24     
they focused on like one topic was like you     
48:29     
know eight eight presentations on um um     
48:36     
surface surface cortical surface you know I forget what they called it     
48:43     
Precision Imaging or you know analysis or something like that like whole brain     
48:49     
whole brain modeling you know whole brain Dynamics um definitely something on kind     
48:55     
of EG and these are terrific because this is like this is big meeting for brain     
49:01     
imagers right so um so was really nice set of both     
49:08     
practical like like kind of overview of the of you know the technology or kind     
49:15     
of the state stateof the art um as well as kind of overviews of some of the big research     
49:23     
topics and and overviews of some of the software     
49:28     
uh and then big brain dropped and and you know again this kind     
49:34     
of started as an extension of um     
49:41     
uh Carl zillis is um like zillis was a neur anatomist at     
49:49     
at ulich um that was uh     
49:57     
I he was doing really fine hystology kind of work on     
50:03     
brains I I knew him as the guy who was the only person I knew that was doing     
50:09     
really good uh receptor mapping of brain     
50:15     
yeah again in this kind of um     
50:20     
uh histology histology SL pet kind of way     
50:26     
right um and he was always the one pushing it and     
50:32     
and in the kind of original brain Imaging books that came out in the I     
50:39     
don't want to say the 90s but like artha tooga zillis was in there um with his     
50:47     
with his his brain Maps which were you know slices usually right and and big     
50:53     
brain was like we're gonna we're gonna do it and we're going to do it like like     
50:59     
they gotten to the point where ulic was building its own     
51:05     
uh brain slicing technology right so it just kind of reminded me of     
51:13     
um because this the minimal cell Workshop was also     
51:19     
this week or you know videos dropped this week from Venter Institute and it just kind of reminded me of Venter     
51:25     
Venter building you know special Hardware to do sequencing right     
51:33     
right in his case to to kind of beat the right the big government effort but you     
51:40     
know um that that was the idea of big brain     
51:45     
and then then there was a conference it was like 2018 and it had     
51:53     
um it was got the weird I forget anyway it was it was like Woods Hole and     
52:00     
talking about this particular data set it was huge right so was like 10 Micron     
52:07     
resolution and you could see every cell and and it it was this like it was this     
52:13     
galaxy or you know this like Universe view of the brain right where     
52:21     
you just you could you could kind of endlessly Traverse the brain and in     
52:27     
terms of like every time you you you kept on going down in detail and you just find new worlds you know yeah um     
52:36     
and a big part of it was talking about issues of um H how to manage this much     
52:43     
data how to how to work with other groups when you definitely couldn't move     
52:49     
the data around so they were like building building web tools for it you     
52:55     
know vering the data um yeah     
53:00     
anyway but uh big brain now in this eth um meeting you can see you know there's     
53:10     
there's plenty of physiological modeling I mean th this is very much like a very     
53:20     
broadly it reminds me of like the full kind of set of of of topics that you'll     
53:26     
see at brain human brain mapping for instance right you know brain atlases improving     
53:33     
brain simulation um yeah simulation through integration with structure um white     
53:41     
matter mapping so diffusion you know um the     
53:47     
um uh an highball I think is relates to     
53:53     
is some acronym that relates to um like high resolution maybe again to together     
54:02     
with um I don't know if the the acronym is coming off of kind of a     
54:10     
particular name and defusion imaging uh um but dimensional     
54:17     
perspectives on multiscale cortical organization you know just I mean it     
54:23     
just goes on and on and on it's it's uh I'm just looking at the all     
54:29     
the different videos from Big Brain Project YouTube channel that that     
54:35     
dropped yesterday um uh you can give     
54:40     
yourself a you know a real kind of perspective on     
54:48     
all things brain Imaging all all topics brain Imaging     
54:53     
related um so I I I I know it's got a big ulic focus ulic is is is a number of     
55:04     
things um one it's the supercomputing center in Germany but it's uh two it's also the     
55:12     
current head of the um what what this     
55:18     
the second version of the human brain project um um the the leader is now cine     
55:25     
alance and and uh she worked she worked closely     
55:32     
with Carl zills and who who passed um I think     
55:38     
maybe decade ago yeah anyway while ago     
55:45     
um and maybe maybe five years ago but     
55:50     
anyway the um um she's now the head of     
55:56     
of the the what is now ebrain ebrain I think I     
56:05     
think it's what they call yeah so she she's on yeah but but this     
56:10     
is this is the second generation trying to learn from the mistakes of the first     
56:17     
in the sense that um uh people weren't necessarily happy     
56:23     
about how that billion euros were spent oh what they what they got for it yeah uh     
56:31     
and um and you know and to some degree     
56:36     
yeah it was like the brain imagers the brain imagers won I don't     
56:42     
know if that's one way of kind of seeing it is that like like the first generation was really good for the     
56:48     
computational neuroscientists yeah potentially um and and the the um     
56:59     
uh andc I I see a lot of initiatives in Europe in terms of trying to be     
57:08     
more translational or or certainly start to to walk back some of     
57:15     
that that original direction to to building out kind of fundamental     
57:22     
research in in areas that that hopefully are are more are closer to to topics that can     
57:31     
be um I I almost want to say commercialize yeah um but it's it's     
57:40     
there is this there is a European meeting where they I forget what they they call that particular meeting but um     
57:50     
um they would like to see something that they're not fun come out     
57:56     
of this that that could be you know even     
58:03     
better if it's if it's clinically relevant uh um brain Innovation yeah     
58:09     
like like I know it's a it's a crappy it's like brain Innovation days is the     
58:14     
is the European meeting there there is actually a company called brain Innovation that     
58:20     
that's been around for a long time that's um um     
58:26     
famous researcher in mosit runs that company um anyway I'm     
58:32     
blanking but um uh great great set of talks right and     
58:41     
um uh yeah can't can't can't say enough about it in terms of you know there's     
58:49     
there's deep learning examples um um all all sorts of things and and     
58:57     
you know like like again like I'm I'm I've got to try and make the time to go     
59:03     
over this because again it's it's a really nice it's     
59:08     
like yeah it's all right I I didn't finish that ulick is one big part of     
59:14     
this the other part of this is mcgillan okay and and um and I should say in     
59:21     
particular Alan Evans who's the kind of um     
59:27     
yeah just a a big reason why Miguel is the the     
59:33     
center that it is um in terms of of um     
59:38     
having a big you know big software group obviously having you know lots of big     
59:45     
data collaborations and um and then just having a bunch of top top researchers     
59:52     
but um uh okay yeah and there's there's even going to talk here um big brain the     
59:58     
Migel multimodal data ecosystem um     
1:00:05     
so right oh yeah look introduction yeah highball introduction by Katherine     
1:00:11     
almans and Allen Evans so     
1:00:19     
um a hell of a lot there I think I dropped a video on neuro AI special     
1:00:24     
lecture okay um you know because um I think re or     
1:00:30     
someone had said hey do we have a neuro AI interest group or something yeah that     
1:00:36     
was Rish BOS yes okay and and anyway that that     
1:00:42     
was there um so yeah a lot of a lot of good stuff um     
1:00:52     
and then um well don't don't let me if you've got things you know I can drop     
1:01:00     
links to this um I feel like I've talked for a long time but     
1:01:06     
um yeah well I mean I think we have a lot of this is a lot of stuff that you     
1:01:11     
know we can go through or people can go through yeah definitely drop the highball Link in the I don't know which     
1:01:20     
channel that could be I mean it could be brain organ neuroscience nwork works yeah     
1:01:27     
yeah I just wanted to to to the other the other one is the global brain     
1:01:33     
Consortium okay and um just just you know just     
1:01:40     
point it out it's globalrain consortium. org yeah at least they made the URL easy     
1:01:49     
and um the so celebrating 100 years of EG right     
1:01:58     
yeah and um uh you know hansberger there there's     
1:02:05     
some interesting videos that you can find at the mind brain clinics in in the Netherlands they did a bunch of History     
1:02:13     
you can you can check on Wikipedia too there's it is kind of     
1:02:18     
fascinating um kind of the first 30 years of the eing in terms of who was     
1:02:24     
doing what with what but um anyway a lot of a lot of big     
1:02:32     
names you know we talking about brain Imaging what I'm kind of emphasizing is     
1:02:37     
actually MRI and pet and you know those those kinds of things     
1:02:44     
electrophysiology um and if you will non-invasive electrophysiology so not doing brain     
1:02:51     
surgery um has this is this is kind of the focus     
1:02:56     
I think it's it's it's great the opening remarks are from Pedro Valdes Soso who's     
1:03:01     
the head of the CUA NeuroScience Center and for those who don't know Cuba um     
1:03:07     
because of its because of our embargo and technology and because of its     
1:03:13     
emphasis on on the medical sector and and producing lots of doctors um they     
1:03:20     
have one of the largest uh um corpuses of of EG data in the world worlds from     
1:03:27     
from all their from all their people and and um     
1:03:35     
uh that and the fact that um because Cuba was kind of pushed into the the     
1:03:41     
Soviet um realm um people of Pedro's     
1:03:47     
Generation Um are all Soviet trained mathematicians so they're all super     
1:03:54     
excellent in computational modeling but they they they figured out everything on     
1:04:00     
paper because they didn't have access to our kind of computers just finish with     
1:04:06     
that yeah yeah that's great yeah thanks for the discussion on that and I thinkig     
1:04:11     
brain conference looks interesting and highball and all right well let's uh     
1:04:17     
move on I don't know if Jesse had anything you want me to say or um I can     
1:04:24     
briefly this is more just like a pre teaser thing I miss some of what you     
1:04:29     
were recently saying I 10 to something um but there event sound you know     
1:04:35     
good um basically I'm     
1:04:41     
really currently intrigued     
1:04:46     
by a question space I     
1:04:52     
suppose okay um     
1:04:58     
and it's weird because we've talked we've talked about like complexity we     
1:05:03     
have like a complexity in something curriculum and we've mentioned the Santa two     
1:05:11     
countless times we've mentioned complexity Explorer we've mentioned all this     
1:05:17     
stuff and I don't know just because I'm very     
1:05:22     
naive and uninformed which I think is case um     
1:05:30     
but seeing David cra's war in recent     
1:05:36     
War um has been very interesting in a way that I think I need     
1:05:44     
to I don't know if I want to call it a project but there's a definite set of     
1:05:49     
questions that I want to investigate relative to his work relative to what     
1:05:56     
he's been doing at The Institute and where he's going and basically like it     
1:06:04     
like I don't really know if controversy is the right word because it sounded a little     
1:06:09     
more a little more dramatic than I intend but but     
1:06:17     
um it's sort of this the space between what is he doing with complexity     
1:06:24     
science or what he calls complexity versus The Institute and where is it     
1:06:30     
relative to sort of um what people are doing in complexity in general because I don't even I don't     
1:06:37     
even I don't really actually remember or at least I don't think I if you ask me what does Bradley's or     
1:06:43     
Morgan's take on complexity science I wouldn't be able to say very well like     
1:06:48     
it's it's like it's something that you talk about or care about in some ways like I don't have Nuance in that     
1:06:55     
discussion to say well I think complexity should be this or not this I think I think this is behavior of you     
1:07:03     
know where complexity science or Theory can work or not I don't know like I feel very I feel informed but like I I I     
1:07:11     
suddenly feel very superficial about my information and and depth     
1:07:20     
and there's certain things that I haven't heard before before and maybe     
1:07:26     
because I haven't been paying attention to them but there's certain things I haven't heard before about     
1:07:32     
what David KRA or is trying to     
1:07:37     
do um that feel to me very interesting but also I don't yet     
1:07:47     
know it's something that I have to much much much more deeply understand um     
1:07:52     
because some of the recent things that I've heard and this new book out which is I don't really know if it's a new     
1:07:59     
book so much as a collection of of older papers and stuff and and more streamlined a complex world is an     
1:08:04     
interesting thing but he's starting to develop this thing like chomic matter like what does that mean um and making     
1:08:12     
complexity sence about that to me and at first glance that's like okay that's     
1:08:18     
that's not what I originally was like that wasn't um     
1:08:24     
complexity science to me but I don't I don't know like I I I never really had a     
1:08:29     
great grasp of it at any rate but the angle that the vision that he seems to     
1:08:35     
be outlining seems very interesting to me even if it's something that I think is potentially maybe not could be     
1:08:42     
incomplete isn't the right word but more like it could be something I'm interested in in really pushing forward     
1:08:48     
but I don't know yet like I feel very very very um superficial so so I'm I'm trying     
1:08:56     
to find some of his stuff um and the conversations like there do conversation     
1:09:01     
with the one on mindscapes talking to Sean Carl my escapes podcaster guy I     
1:09:07     
think is also actually SFI and their conversation's great so far because son is coming from a bit     
1:09:14     
more of a um physicist classical physicist background and he's he's does     
1:09:20     
a lot in that space and he's very accomplished but is more as a convention     
1:09:27     
um you know that approach and him     
1:09:32     
probing David about where he's what is he doing with this stuff and even him     
1:09:38     
being at the Institute himself kind of seeing where it goes it a very interesting conversation while at this     
1:09:44     
too so between that's one thing I really want to dive in deeply um as we talked     
1:09:50     
about about last week I think uh barley went you know did did     
1:09:56     
a big overview of his presentation about complexity and and then it it dovetails     
1:10:02     
a lot into U you know the theology paper for me like going back and reading that     
1:10:08     
thology paper um has been very interesting even if     
1:10:14     
it's um it's a really interesting space for     
1:10:20     
me right now at least at least for my mind to to be work to looking at the 1943 paper in all of its like     
1:10:29     
profoundness and also like the Simplicity of things time too relative     
1:10:35     
to you know what like 80 years later     
1:10:40     
where like KRA is is seeing stuff um and and I'm I'm just that's     
1:10:47     
there's some I don't even know necessarily to say what I don't have greatly defined     
1:10:53     
questions but I know have some very specific questions that I may try to turn into I don't know if they'll be     
1:11:00     
like paper but I want to do do some writings about the space because I find this to be very you know um maybe useful     
1:11:08     
for some of my overall aims like things I want to see Chang or done or like the new we talked about like new kinds of     
1:11:14     
science both yes the wol from book but like doing science differently Stu for a long time um in this in this group and other     
1:11:21     
things that I'm interested in too so it's sort of like [Music]     
1:11:27     
where I'm theoretically like idea wise at a high level it's it's appealing like     
1:11:34     
in terms of actually developing like Theory and tools um I don't really     
1:11:43     
know like I don't know yet um and and it's it's interesting because it it's a     
1:11:50     
different layer of questions and Curiosity on somewhat     
1:11:57     
somewhat I would say familiar but like distantly familiar material that's come up like my feel like complexity is this     
1:12:03     
term that's just I actually referenced um somewhere when I was talking about this elsewhere it's like yeah a long     
1:12:09     
time ago I was like what happened to cybernetics and I actually feel a little bit better about that question now like I know I know where it went like I know     
1:12:17     
I know what happened to it because when I first came to it like I don't know almost 10 years ago and I just heard saw     
1:12:22     
this like kind of random YouTube video at the time from someone and I went down this long path and I don't really find     
1:12:28     
anything but then I've done so much stuff with it like I know I kind of I know about it but it's kind of a similar     
1:12:33     
spark of you know what is is there more within the     
1:12:42     
arena of people trying to do complexity stuff than I may be understood or like     
1:12:49     
discredited or did didn't didn't didn't appreciate fully as sort of the you know     
1:12:54     
High our way of saying it I suppose but um I don't know I'm just very curious     
1:13:00     
about that space and and I look forward to talking about that more I posted something in the slack about like one of     
1:13:06     
kar's papers about like machine learning stuff um but I'm really interested in sort of his toonomic matter approach and     
1:13:14     
what that entails for um potentially doing signs differently or having a different tool     
1:13:22     
set from from things that are not you know purpose related and and and it and     
1:13:27     
that's part of why like I I went through the paper in in in our discussion but also like I I'm writing I want to write     
1:13:34     
something specially about uh the paper the the 1943 paper     
1:13:40     
and I kind of did some big whiteboard thing about it that um I'm not going to show it right     
1:13:46     
now but like I I uh there's there's some stuff I'm doing already on that and I     
1:13:51     
want to just keep that going so um I don't know if if if either you have     
1:13:57     
anything you want to say about your take on the state of complexity science or some we don't to go into it deeply right     
1:14:03     
now right you know any like generic advices or things yeah we talked about     
1:14:09     
this or this conversation you're welcome do that otherwise we can we want other things too I I don't have like right any     
1:14:17     
questions outside of a vague vaguely stated interest at this time yeah i' be     
1:14:23     
very interested to see the way for and that it has on it like you know because I'm interested in the that that paper     
1:14:30     
was also very interesting to me in terms of like how do we approach um you know cybernetics but     
1:14:37     
also like how do we approach sort of behavior versus other things like     
1:14:42     
development and evolution and how does feedback really factor     
1:14:47     
into like what are the mech you know what does feedback lead to in terms of behavior and not just like human     
1:14:55     
Behavior animal behavior but like systems Behavior so yeah um but I guess     
1:15:00     
my other question for you is like what happened to cybernetics you said you had the     
1:15:10     
answer okay you oh I'm sorry was the last bit I what     
1:15:17     
happened to cybernetics you said you had the answer oh well you know it uh things     
1:15:23     
happen to it um but at the very least I     
1:15:28     
kind of see why it went the way that it did right you know it     
1:15:36     
it it's it's kind of actually interesting because maybe it's just because I'm more in it's so it's so     
1:15:43     
weird because it's like now that I know like I know Michael 11even and what he like that he     
1:15:50     
references the the theology paper yeah and then he's doing it like seeing     
1:15:55     
people conf people do the thing helps at least it it the personal the     
1:16:05     
the the effective you know sense of oh this is old as hell nobody really cares     
1:16:11     
about this like what happened this term that was really popular and like cybernetic organism terminated like like     
1:16:18     
all these weird us it's such a the thing about the thing I guess in similar ways but but     
1:16:24     
like culturally the cybernetic and cyber this and cyber that has its own kind of I use     
1:16:32     
a word Vibe it has its own like the word itself has so much     
1:16:38     
loaded into it complexity I guess does two similarly     
1:16:44     
but it it feels I don't know it feels     
1:16:49     
different somehow too um but yeah seeing see     
1:16:55     
like the 1940s reading enough nor Wier to see his take knowing those different     
1:17:00     
takes and seeing kind of I guess you could say natural development of other stuff that's been     
1:17:08     
nice to see like I I don't really know what to call that learning experience I guess is sort of the answer to the     
1:17:14     
question the long answer to the question of basically what the the questions     
1:17:20     
really like you know what did people trying to do     
1:17:26     
Computing and control and communication and information what do they     
1:17:33     
do in the last you know 80 years that's kind of what the question     
1:17:39     
really is um and then and then you got the wacky stuff so     
1:17:48     
yeah um but but     
1:17:53     
um definitely some things ahead regarding maybe even competing I might     
1:17:59     
do some if if it if it gets if a potential direct be trying to     
1:18:05     
do some actual comparative I don't know comparative analysis is too formal but     
1:18:10     
between you know Tak some complexity and and even seeing like like looking at some the complexity Hub recently about     
1:18:16     
like well we're trying to do problem specific groupings of of researchers instead of domain you know tended by     
1:18:23     
domain like okay school what does that really mean or or there's like the new Eng and complex sytems Institute which     
1:18:29     
I've heard a few things about and attempted to do their summer school for some winter School a long time ago and     
1:18:36     
and I've heard different things about what's going on there so we'll see it's a it's a it's a fun space right now but     
1:18:43     
that's all I got for it all right     
1:19:03     
you said something about a school of a thousand complexities or something like that what was that oh NE Eng and complex     
1:19:09     
systems oh right okay that that's what they're doing okay that I don't I don't     
1:19:15     
know what else I would have said oh complexity Hub too this okay comple I'm     
1:19:21     
notar with either of them well sort of but we'll see yeah there there are other     
1:19:26     
these other complexity like resources and places like you know Santa Fe is just one school of thought uh nexi is     
1:19:34     
another school of thought I mean they do a lot of stuff with networks and then complexity Hub I think     
1:19:40     
is like out of Europe or there people in Europe doing stuff and so like you know     
1:19:46     
there are all these different places where they have different schools of thought on what complexity is and what     
1:19:52     
is involved and so I mean you know it's a very I think very fertile ground to     
1:19:58     
kind of lay down your marker and this is what complexity is um I guess you know     
1:20:04     
anyone can have their own Theory but like uh you know there are always these different schools of thought where     
1:20:09     
people are bringing in different tools some people are more focused on networks some are on dynamical systems some are     
1:20:16     
on like these sort of postc cursors of     
1:20:22     
cybernetics you know so that's that's um you know that that's good that you're     
1:20:28     
thinking about that I think it's it would be great to kind of maybe turn that into something some     
1:20:36     
paper or presentation so more on that later thank     
1:20:41     
you Jesse for that okay let's get on with um I wanted     
1:20:46     
to present this article um so this is from the transmitter I think I mentioned     
1:20:53     
this last time is like a new new sort of place on the internet to find     
1:20:58     
Neuroscience takes and things like that um so this is Simon's Institute yeah     
1:21:03     
Simon's Institute yeah Simon's Foundation yeah yeah yeah um so they     
1:21:10     
they have this I guess that's a blog or a you know Magazine online so this is     
1:21:17     
Mark humer us is a neuroscientist um and they this is about     
1:21:22     
neural coding and the title of this article is averaging is a convenient fiction of     
1:21:28     
Neuroscience so you know we talk about averaging and mean field models and things like that and it's very easy to     
1:21:35     
work with those kind of things but in fact the brain is not like a mean field model it's not like an average system     
1:21:42     
you average things out sometimes you can you know filter out noise and get sort of a a good working answer sometimes     
1:21:51     
averaging actually hurts you however if you're dealing with these nonuniform     
1:21:56     
systems and you know you have this and this was a theme in cybernetics I think     
1:22:02     
as we talked about on Wednesday that you know there's this aspect of uh how     
1:22:08     
people will you know normalize things to averages or to uh normal distributions     
1:22:14     
and in the brain you can't necessarily assume that so this is the sort of the     
1:22:20     
theme of this article and the subtitle is but neurons don't take averages this ubiquitous practice hides from us how     
1:22:26     
the brain really works so again this is a nice take this oh Mark Humphrey is the     
1:22:32     
chair in computational Neuroscience University of ning here so     
1:22:38     
um so this is basically U something he's this is the diagram that kind of     
1:22:45     
explains this this is something he's calling mathematical masking so you see all these diverse signals coming into     
1:22:51     
this box and it comes down into this box and it like forms this nice neat sine     
1:22:57     
wave and then it leaves the boxes uh diverse as it came in so this     
1:23:05     
box here is just basically taking an average of everything and it's producing this nice sine wave but the problem is     
1:23:11     
of course is that that's just reducing perhaps all the information of those signals down to this one little signal     
1:23:20     
that we can measure so I mean you know we have signal processing techniques we have other types of techniques that     
1:23:27     
allow us to get uh you know information out of a signal uh but still you're you     
1:23:33     
know the Assumption of course is that individual neurons you're doing this sort of averaging especially when you're     
1:23:40     
averaging neural activity over trials or over neurons and you're losing a lot of     
1:23:46     
uh sort of information about what's happening in the brain or sometimes you're losing information about edge     
1:23:52     
cases or sometimes proc processes will have a long tail you know like a     
1:23:57     
exponential function where there's a lot of information in that tail and you're just basically chopping it out and     
1:24:04     
working with the average so this is one of the problems with you know some of these normalization techniques that may     
1:24:11     
make our job easier in the short term but then um in the long term it gives us     
1:24:17     
this um model that we could we would be better off not um doing     
1:24:25     
so this kind of starts off at any social Gathering of neuroscientists the     
1:24:30     
conversation can turn to what's holding back the field funders some Grumble lamenting the amount of money thrown at     
1:24:36     
microbiology instead journals others CH chip in browsing at the gatekeeping     
1:24:42     
editors the tyranny of Old-Timers some newly mined print Pi often mutters     
1:24:48     
cursing the difficulty of challenging entrenched ideas I say averaging and     
1:24:53     
everyone moves slightly farther away from me down the bar but really it is a problem averaging is ubiquitous and     
1:24:59     
Heights from as how the brain works so basically from his perspective you want     
1:25:05     
to understand the signals sent by neurons these are basically encoded in     
1:25:11     
spikes and this underpins the brain's functions um and so to understand say     
1:25:18     
how we make a decision many argue we need to understand the spikes that underly it how they convey information     
1:25:24     
about the options available how they convey the process of a decision between those options and how they convey that     
1:25:30     
decision into action averaging is everywhere in our attempts to understand the spiking of     
1:25:36     
neurons a good example is that fundamental work course of sensory Neuroscience the tuning curve imagine     
1:25:43     
that you want to know what frequency of a sound a neuron most prefers you play     
1:25:49     
that neuron tone you play that neuron tones in a range of frequencies and comp     
1:25:54     
the number of spikes it emits for each so you have this you know you're kind of     
1:25:59     
taking the spike you're segmenting out the spike and you're counting these in a     
1:26:05     
range of fre or you're counting the number of spikes for a range of frequencies you repeat that a bunch of     
1:26:11     
times average the number of spikes emitted for each frequency and you've built yourself a tuning curve from those     
1:26:18     
averages so this is a kind of plot that tells you the average number of spikes     
1:26:23     
the neuron sens for each frequency so you're basically taking each frequency band and you're getting an average of     
1:26:30     
number of spikes for that frequency which you know is you think that would be reasonable because you'd     
1:26:37     
have variation in terms of you know how many spikes are sent at each frequency     
1:26:42     
but you know this is something that again if it's normally distributed that's fine but maybe it's not normally     
1:26:48     
distributed within that frequency maybe there are things over time that are you know AB aberant from that average or you     
1:26:56     
know basically it's not a say a normal distribution within that within     
1:27:02     
different frequencies so for low frequencies it might be a normal distribution for higher frequencies it     
1:27:07     
might be an exponential distribution and it gives you this range of you know     
1:27:13     
range of properties that can't be measured easily with an average so it may well show you that the     
1:27:20     
neuron sends more spikes on average to 100 Hertz tones than the 10 or 1,000     
1:27:25     
Herz tones suggesting the neuron is tuned to that specific frequency of sound okay um the natural extension of     
1:27:33     
this idea is to look across time creating a peris stimulus time histogram so again this is another histogram type     
1:27:40     
model where you're looking at some average number of spikes and your RS and     
1:27:46     
just before and after some significant event so you want to know like Preparatory aspects of it and you want     
1:27:53     
to know the consequences of the event and so you want to see like so for if an     
1:27:59     
animal repeatedly gets a reward for example we look at how a neuron responds to that reward by seeing how many more     
1:28:06     
or fewer spikes it sends on average after a reward than before so neuroscientists use averaging     
1:28:15     
for good reasons because reduces the data that they're working with it gives you these convenient neat uh figures     
1:28:23     
that you can put into a paper that you can communicate the idea reliably so I     
1:28:29     
can understand it so you know if I have like a graph     
1:28:38     
um so if I have a graph again you know I might have I might want to     
1:28:47     
take my signals put them in these bins different frequency bands     
1:28:55     
and finding average value compare the average across these     
1:29:03     
different cases so this is my mean this these are my     
1:29:09     
frequency     
1:29:17     
bands and I can make this comparison right but let's say the underlying     
1:29:22     
distribution we want to kind of think about what that is so for a we might indeed have a normal distribution which     
1:29:29     
is sort of a bell curve like this this is the mean the central     
1:29:35     
tendency this is the standard deviation here and you've described most of the     
1:29:41     
cases that you're encountering in it so the average makes sense the average describes something significant about     
1:29:48     
the signal but let's say that in C which you know is Maybe a little the the average     
1:29:56     
is a little bit higher but the structure of the signal is very     
1:30:01     
different and see it might be a multimodal signal something like this maybe a long tail at this end so     
1:30:10     
taking an average you know might end up being here which then the standard deviation     
1:30:16     
would be like this and it doesn't really describe this underlying function at all because first     
1:30:23     
of all there are two essentially two means first of all that that are interesting so you can maybe report the     
1:30:31     
you know average of those means but that's there two distributions hidden in here and then there's this long tail     
1:30:37     
that we can't describe because we've kind of eliminated all those data so you     
1:30:43     
see that it describes a very well but C very poorly and yet the average looks like     
1:30:48     
it's about the same and even if we do like a T Test between a and C     
1:30:55     
you know we might get like something that's not significantly different but it actually is     
1:31:01     
significantly different in terms of the unno distribution and so this is kind of what     
1:31:07     
he's getting at which is that you know we use sort of mean values or average values as the sort of     
1:31:13     
summary of events and you can't always say that that's a good summary of     
1:31:20     
events sometimes it's not a good summary of events so averaging over time hides     
1:31:25     
what a neuron actually sees what it actually gets to compute with so it     
1:31:30     
might be Computing with this versus this and an average won't tell you the     
1:31:38     
difference in it hides it so you know we so you know we use     
1:31:46     
this as a matter of convenience uh neurons also typically emit different numbers of spikes to the     
1:31:52     
same event so only by averaging over many repeats of the same event can we seemingly extract the reliable signal     
1:31:59     
that the neuron uses to encode it so there's a lot of like uh you know     
1:32:04     
variation in terms of if I have some event like if I get a reward of juice     
1:32:11     
from a juice box every time I select a Target if I'm a a nice monkey and I do     
1:32:18     
my job in my experiment I get this reward and every time I take a sip from     
1:32:23     
the box and get that reward I'm getting a different number of spikes that are emitted so it's kind of hard to say you     
1:32:30     
know maybe like sum the number of spikes because it's going to be a different number every time for every event and     
1:32:37     
you might think that you know maybe these events are treated differently by the brain when in fact they're basically     
1:32:42     
the same response it's just there's some variation so we use the average to sort     
1:32:47     
of you know uh sort of gloss over a lot of that sort of variation or noise it     
1:32:54     
doesn't matter so much in terms of what the actual response is so on the other     
1:32:59     
hand you can have these kind of responses that are multimodal or these kind of responses that are qualitatively     
1:33:06     
or even quantitatively different and they can't be described with an average so averaging undoubtedly helps     
1:33:13     
us wrap our heads around the complexity of the brain's activity we even use the average response of neurons is the     
1:33:19     
starting point for some of our most sophisticated analyses of population activity such as the variance of     
1:33:26     
principal component analysis so this is a link to an eif     
1:33:31     
paper uh demixed principle component analysis of neurop population data and     
1:33:37     
this is of course a type of PCA that you know they use for um getting at neurop     
1:33:44     
population data so there are a lot of different types of analysis of variation that you can use to get signals out uh     
1:33:52     
and so this is actually one method such method so in this case you have uh you know     
1:34:00     
you're looking at the complexity of single neuron responses and those can obscure what     
1:34:06     
information these areas represent and how it is represented so they're using these dimensionality reduction     
1:34:13     
techniques um in this case uh demix principle component analysis decomposes     
1:34:20     
population activity into a few components um in addition to systematically capturing the majority of     
1:34:26     
the variance of the data vpca also exposes the dependence of the neural     
1:34:31     
representation on task parameters such as stimulate decisions or rewards so     
1:34:37     
this gives you this sort of model for dealing with different types of data so um you     
1:34:45     
know this kind of goes into the these kind of problems with using averages using different types of uh     
1:34:52     
dimensionality reduction because we're the basis of dimensionality reduction is that we're     
1:34:58     
finding these uh components that describe the varation so you know it's     
1:35:05     
maybe in some ways it's a similar problem     
1:35:11     
um so this kind of goes through uh some of the things that people have done in     
1:35:17     
the um field uh The Final Answer eludes this on     
1:35:22     
single trial some neuron spikes seem more step-like other neuron spikes seem     
1:35:28     
more ramp like so they're different types of spikes and if you just count spikes you're going to miss that     
1:35:34     
variation but irrespective of how many neurons increas increase their rates or how many stepped are ramped in a single     
1:35:41     
trial the problem of averaging is clear many single neurons do not look like the average ramping response and do not fit     
1:35:48     
Theory based on it so you know you might think that like counting spikes are averaging spikes will solve your problem     
1:35:56     
but even then not all spikes are equal so if there's an average ramp response     
1:36:01     
that we're looking for and we assume that every Spike does that there are other types of spikes that we're kind of     
1:36:08     
filtering out and those may actually be important in the uh you know at least in     
1:36:15     
terms of getting some interesting information out of the experiments it doesn't match our the our overall Theory     
1:36:22     
so sometimes when we do Theory building we kind of build theory on these archetypes or these averaged ideals of     
1:36:30     
what a system should look like so we might take a you know build a     
1:36:35     
theoretical model where we assume that all spikes are sort of similar and that you can do this method and you can get     
1:36:41     
down to um you know an answer that's very clean and neat and it fits into sort of     
1:36:48     
a theoretical statement and you know that sort of thing but that's actually maybe not the best way to approach     
1:36:56     
experimental data so uh whenever most of     
1:37:01     
us average neural activity over trials over neurons or both we're implicitly assuming that the resulting signal is     
1:37:08     
what the rest of the brain sees we're hoping that all the variation of individual neurons is distributed across     
1:37:14     
the whole population of neurons in a way that their aggregate moment to moment signal is approximately the same as the     
1:37:21     
signal we get by averaging the output of each neural it's weird that we don't know if this     
1:37:26     
assumption is true averaging is ubiquit is Central to our tools and part of the language but we know in our hearts that     
1:37:33     
as a matter of convenience an easier way to think about the brain indeed averaging spikes may just be an accident     
1:37:40     
of History rather than a rational approach to understanding the brain so you know again it's at the heart of kind     
1:37:47     
of What kinds of theories we use to do these kind of analyses it's part of the     
1:37:53     
it's a very simple language it's a clear language people can understand and yet it may be very wrong because it does cut     
1:38:00     
out a lot of the complexity that we need to know and so uh this is an interesting     
1:38:06     
point before computer generated Graphics existed a simple histogram of a neuron's average response was the simplest thing     
1:38:13     
to draw so that's very interesting that you know and that goes back even in into     
1:38:19     
the history of complexity theory that a lot of these analyses and complexity Theory weren't possible necessarily     
1:38:27     
before high-powered computers were available we couldn't explore fractals for example until we had these kind of     
1:38:36     
um you know high-powered computers that could simulate things and generate the analyses we need and so you know we we     
1:38:43     
you could do things on paper but it was hard to do it's hard to describe things are so this is uh you know interesting     
1:38:50     
that Computing actually is was serving traditionally as a barrier to a l this     
1:38:57     
and so um just just in a side there that might be useful and thinking about     
1:39:02     
Alternatives things we now have the tools we need to find out if averaging     
1:39:07     
is showing us something about the brain signals or is a isolating historical accident and so that's basically the     
1:39:14     
take-home message of this um now Morgan is going to say     
1:39:20     
something I was just gonna just add to that that     
1:39:26     
um I mean you talk talk about histograms and the     
1:39:32     
um the the text that is kind     
1:39:37     
of Nal um is tu's uh exploratory data     
1:39:43     
analysis yeah right like 1960s right like like anyway it was you     
1:39:53     
know he was at Bell Labs right yeah and     
1:40:03     
um you know that that one is the first     
1:40:09     
one the you know he has all these kind of like simple     
1:40:15     
prescriptions but forgetting these kinds of things where it's just like like rep     
1:40:20     
new representations of the data that that give me insights right     
1:40:27     
right as opposed to just the the kind of the parametric tools that that you know     
1:40:34     
Fisher Pearson     
1:40:40     
others had given us um and and it it was     
1:40:46     
profound it was it was profound even before computer Graphics yeah right and     
1:40:52     
then and the then you know     
1:40:57     
uh yeah and and like like the the end of that being kind of like you know     
1:41:05     
um like umap and stuff like that like right you but but but they really do     
1:41:13     
build on a bunch of kind of super basic I mean you know the kind of toughed     
1:41:18     
visualization of data right kind of stuff that that that there's yeah um I I     
1:41:26     
wanted to say I I dropped a link in open chat form on     
1:41:32     
slack that gets at um hre's     
1:41:37     
um uh yeah click click on that link from EEG lab okay yeah and scroll down a     
1:41:45     
little and they call these her images so there's there's you know in a sense the     
1:41:53     
this is this is what the data looks like you as as collected but then keep keep     
1:42:02     
going down right and you know     
1:42:09     
so the um there's this and then if you keep scrolling down then they sort they     
1:42:15     
sort the trials and then these kind of new new relationships are coming out     
1:42:22     
from the way that they're sorting them right is is yeah yeah and then     
1:42:31     
there you go there you know the the I don't know if you     
1:42:38     
know basically imagine an EG Trace is actually just one line of this plot     
1:42:44     
right right like turned on its side and then colorcoded instead of being a a     
1:42:50     
squiggly line right like like the squiggly line at the bottom is kind of     
1:42:55     
the grand average but but the each one of those is a squiggly line it's you     
1:43:01     
know in this case it's it's p z right or is that F I can't     
1:43:07     
see but um uh     
1:43:12     
um in in the like late 90s I mean you know again like when I     
1:43:18     
started an EG everybody was doing erps right     
1:43:24     
which is which is averaging yeah yeah and and and of     
1:43:31     
course um but I I was coming out of the I     
1:43:38     
refused to do stats in the psych Department I I wanted to do stats in the     
1:43:43     
math department right yeah so so I I had done stats you know with with     
1:43:51     
mathematicians and using R you know which is like the the actually I think I     
1:43:57     
originally used s which again is the is actual language that came out of bell     
1:44:02     
labs and was commercialized right and then R is the G version of     
1:44:09     
s um and you know a big part of of working     
1:44:16     
with the data certainly the first thing we learn is not to apply these models     
1:44:23     
but the first thing you see is what what tests should you do to see if these     
1:44:30     
models are appropriate yeah and of course you know and so you know getting looking for ways     
1:44:39     
to to um determine kind of the the     
1:44:44     
distribution underlying distributions and things like that non-normality measures     
1:44:51     
and uh um homogeneity variance measures and things like that right right and of     
1:45:00     
course as soon as you start applying any of those things to actual EG     
1:45:05     
data you know Erp data it's just like oh my Lord none of these assumptions hold     
1:45:11     
yeah like you know and and so it was it     
1:45:18     
you know again this is this is why it was such a such a pleasure to to have worked with     
1:45:25     
Carl pram um because um Carl was you know was     
1:45:31     
retired or you know a Meritus when I met him and um and just trying to get across     
1:45:39     
like how old he was you know and and you know he was a brain surgeon from the 30s     
1:45:47     
oh yeah you know he he knew he knew Walter     
1:45:53     
Freeman the one who who did lobotomies and things like that you know he was     
1:45:59     
totally against them was the Gast uh um     
1:46:06     
um but it went I would say to him you know so he can tell you everything about     
1:46:13     
the history of EG data analysis because you know he was like in Boston with the     
1:46:21     
first computer right like like     
1:46:26     
literally you know and and so you know he he was quite rightfully pointing out     
1:46:32     
that like they had to do averaging for for erps in the 60s because that was that     
1:46:42     
was all that was kind of algorithmically     
1:46:47     
computable because of memory requirements right and and you know that     
1:46:56     
that it's a great example of just a field getting into     
1:47:03     
a I mean I don't want to like a rut's not the right thing but you know it's     
1:47:09     
like like there was a reason to do that at the time that that     
1:47:16     
was a semi appropriate uh um transform or you know     
1:47:23     
Den noising right right and it's not like there     
1:47:29     
wasn't some results from that you know but     
1:47:36     
um but that but it became this this     
1:47:43     
um yeah it just it was like well we've got to keep using this Hammer yeah and     
1:47:50     
and you know the the experimental complexity or     
1:47:55     
the the the the ability that we had and the new amplifiers that we had and um     
1:48:03     
obviously high density EG also changed things right     
1:48:09     
because what you certainly my my first paper or my first     
1:48:14     
poster um on on anything was multi-weight Data     
1:48:20     
analysis of high density EG studies and and you know it was an SVD     
1:48:28     
based approach but it was it it was essentially a tensor     
1:48:35     
analysis of high density EEG data because I had space and     
1:48:42     
time right yeah and and I I had space I had time I had trials and I had     
1:48:50     
subjects and and um so so yeah it was um together with     
1:48:59     
Joe Dean Joe Dean was the was the last author and and that poster was presented     
1:49:06     
in the World Trade Center oh yeah yeah     
1:49:11     
yeah yeah is it was cognitive because I'm old it was a cognitive Neuroscience     
1:49:18     
Society 2001 oh okay yeah that was early     
1:49:24     
so it was the summer it was the summer before wow okay September 11th yeah yeah     
1:49:30     
yeah yeah and um uh but but you know so     
1:49:36     
I was just checking out this demixed principle component analysis and again it's     
1:49:43     
it's so I kind of came up in EEG as EEG lab um kind of came up too right because     
1:49:52     
it was actually in the 90s it was called IA lab yeah or no it was called IA     
1:49:57     
toolbox IA okay and and he had a bunch of he had a bunch of     
1:50:02     
features and um I can remember uh was it     
1:50:08     
Mike Warden I think it was Mike Warden I remember him coming up to my poster at     
1:50:14     
uh um CNS and saying like you know he was     
1:50:22     
check out you know my multi-way analysis but he was just like I see used I used my plot figure tool from from ICA     
1:50:30     
toolbox I was like oh yeah yeah     
1:50:36     
uh I forget who that was but anyway um but this the these her images were also     
1:50:43     
really interesting I mean it was it was actually like like at the time I was the software     
1:50:50     
engineering manager at electrical geodas right so like this high density EG     
1:50:56     
company these these her images I was actually also using a cross chanels so     
1:51:02     
there there was what we called a synoptic display and those are really     
1:51:08     
interesting too in terms of um you know the spatial the     
1:51:14     
spatial you know connecting them um in that way to kind of create those same     
1:51:20     
kind of plots that color plots but they represented space it it was also really     
1:51:28     
interesting how your visual system was very well suited to to bring out     
1:51:34     
structure from that oh yeah and and like like when you saw something in that like     
1:51:39     
it was real like like you know it wasn't necessarily easy as you see in the her     
1:51:46     
images you kind of have to take a a slice I mean you take a column     
1:51:53     
and and you see this in the Europe image you take a column and then you turn that     
1:51:58     
into a scout topography anyway it's it's um this     
1:52:04     
particular this this little transmitter article brought up a lot of memories for me yeah uh but     
1:52:13     
uh you know I I see I mean I think Mark humph     
1:52:18     
is like probably more used to kind of invasive recordings from animals yeah     
1:52:24     
but but the everything you see in EG lab her images is very similar it's very     
1:52:31     
similar um progression through uh Scott MC's like like problems with herbs right     
1:52:41     
uh uh event related potentials this this averaging and and trying to find new     
1:52:48     
ways to to to examine the the single trial     
1:52:54     
structure yeah and and then he did another version of this that's um uh so     
1:53:02     
you can obviously you can take the time and you can do you know a shorttime for     
1:53:08     
you or or wavelet transform EG lab did a wavelet transform and and create joint     
1:53:16     
time frequency plots right so so this is     
1:53:21     
again a way of making your data sets much B bigger yeah you know and and we     
1:53:26     
also you know again like gotta remember computers the 90s weren't exactly ready     
1:53:32     
for you know 256 Channel you know thousand samples per second like we     
1:53:38     
would we would hit you know problems with two gigabit file sizes on 32bit     
1:53:45     
computers um anyway uh um the     
1:53:52     
yeah so the joint time frequency was another kind of um in a sense pioneering     
1:53:59     
work that came out of EG lab in terms of what they called event related spectral perturbations which again was getting at     
1:54:06     
this um uh what what they were seeing in the The     
1:54:12     
Joint time frequency uh perhaps average but but but certainly they tried to get     
1:54:19     
it the single trial and again like like I a which is you know is similarly a     
1:54:27     
kind of you know fancy PCA right uh um and     
1:54:34     
you know the dimensionality reduction that you choose the number of components you     
1:54:40     
choose right you could you could um you could use this for D noising or you     
1:54:46     
could use it as they do in this demixing principal component analysis to to try     
1:54:53     
and get it um uh kind of Greater more complexities of the of     
1:55:01     
the underlying data right um and and and you know this this most certainly will     
1:55:08     
will eventually hit something like partial these squares where you're getting at um you're including the     
1:55:16     
design together you know the the in the in the the PCA     
1:55:23     
and you know it's it's another technique that is widely used to to kind of bring     
1:55:29     
out with with principal components to bring out the kind of     
1:55:34     
underlying um the latent structure that is most correlated with your design     
1:55:42     
matric yeah but super cool stuff yeah great     
1:55:48     
stuff all right so I'm going to go let's see share my screen     
1:55:55     
here um so yeah it was a good article um     
1:56:01     
they talked a little bit about um you know some of these problems with     
1:56:07     
averaging um this was a p about a paper here where they looked at this you know     
1:56:17     
response to moving dots in uh like I guess a MAAC     
1:56:23     
and they found that there was a great diversity of activity in cortical neurons that they behave in all     
1:56:29     
different ways um and there was an argument that raged back and forth about well how well     
1:56:36     
we can uh tell during a single trial if a single neuron steps rather than     
1:56:41     
gradually increases its spikes so this was I think the paper that they're     
1:56:47     
referring to here in science single trial Spike trains and parial cortex     
1:56:53     
reveal discrete steps during decision making so this is actually I think in humans this is actually I think they say     
1:57:00     
a better way to explain neuronal activity a brain region called the lateral entrop parietal area or lip is     
1:57:08     
involved in primate decision making the dominant model to explain neuronal firing in lip assumes that neurons     
1:57:14     
slowly accumulate sensory evidence in favor of one choice or another so you're linking it to sort of this Behavior     
1:57:22     
cognition that happens uh as a result of the spots laimer at all hypothesized     
1:57:28     
that neurons instead of rap exhibit rapid steps or jumps in their firing rate reflecting discreete changes in the     
1:57:35     
animal's decision State they recorded from lip neurons and maacs Performing     
1:57:41     
emotion discrimination task lip Spike trains and most cells involve discreet stepping Dynamics rather than slow     
1:57:48     
evidence integration Dynamics you can see that there is this sort of uh you know variation and     
1:57:55     
interpretability of these experiments based on the underlying Theory based on the underlying uh statistical methods     
1:58:02     
that are used so that's uh kind of finishing up on that paper or that     
1:58:10     
article uh one thing I guess I'll do one more thing before we end for today and     
1:58:16     
that is this uh set of Articles so this is on self self     
1:58:22     
replication and some neuromorphic Computing stuff so hopefully this kind of fits together um and we'll go kind of     
1:58:29     
go through it um so this is an article from I think it's from     
1:58:35     
1998 yes it's from artificial life journal it was like the fourth issue or     
1:58:41     
the fourth volume and this is by Moshe siipper who's a complexity theist um and     
1:58:48     
this is on 50 years of research on self-replication this is an overview of the type of     
1:58:54     
self-replication work that Von noyman was doing with cellular automa so he had     
1:59:00     
these self-replicating structures that were basically the cell cellular automa that would exhibit sort of a     
1:59:06     
developmental stage and then they would self-replicate and um so this is like thinking about this from the standpoint     
1:59:14     
of 1998 thinking back 50 years which was 1948 I guess um and thinking about Von     
1:59:21     
neyman's work Legacy so this is the abstract the study     
1:59:27     
of artificial self-replicating structures or machines has been taking place now for almost half a century this     
1:59:33     
is again 1998 my goal in this article is to present an overview of research carried     
1:59:40     
out in the domain of self-replication over the past 50 years starting from Von neyman's work in the late 40s and     
1:59:47     
continuing to the most recent research efforts of 1998 I shall concentrate on computational     
1:59:54     
models that is ones that have been studied from a computer science point of view so this these are not like you know     
2:00:01     
uh computational Neuroscience theoretical models these are really computer science oriented     
2:00:08     
models uh be it theoretical or experimental the systems are divided into four major classes according to the     
2:00:15     
model on which they are based and the four models or four classes are cellular     
2:00:20     
autometa computer programs strings or strands or an allog together different     
2:00:26     
approach so you have cellular ones that are based on cellular automa which are the standard uh ones that Von noyman     
2:00:33     
worked with you have computer programs that basically can rep self-replicate you know you have uh you     
2:00:40     
know an evolutionary algorithms or an evolutionary Computing you have strings that can be     
2:00:46     
you know recombined and replicated or other approaches like in I guess unconventional computer uh so he     
2:00:55     
kind of reviews those with the Advent of new materials such as synthetic molecules and nanom machines which we     
2:01:01     
found to that fourth class it is quite possible that we shall see the somewhat theoretical domain of studying study     
2:01:08     
producing practical real world applications so he kind of talks about     
2:01:13     
what Von noyman was doing in the 40s he was interested in the question of whether a machine can self-replicate     
2:01:20     
that has produced copies of itself so he wanted to investigate the logic necessary for replication not just the     
2:01:26     
active replication um he didn't really want to build a working machine at the     
2:01:32     
biochemical or genetic level so he didn't want to replicate biological reproduction he just wanted to replicate     
2:01:38     
the logic of reproduction and what you know what what a computational system needed to achieve to produce     
2:01:46     
replication so um the study of artificial self-replicating structures     
2:01:51     
are maches has been taking place now for almost half a century much of this work is motivated by the desire to understand     
2:01:58     
the fundamental information processing principles and algorithms involved in     
2:02:03     
self-replication independent of how they're realized physically so this is like kind of how you know you could have     
2:02:10     
a system that is totally divorced from reality and how that might want to replicate itself so you know if you had     
2:02:17     
a program and a computer how would it replicate itself and what would be the sort of conditions under which it would     
2:02:24     
replicate and you might think that's a weird question to ask but really you know it's like if you're talking about     
2:02:31     
like a learning machine or if you're talking about a machine that you know or a program that under goes Evolution     
2:02:39     
through an evolutionary algorithm then that's maybe an easier way to think about it and it maybe a much more     
2:02:44     
reasonable way to think about it because there's an imperative there to to do something uh that self-replicates     
2:02:53     
so it may Advance our knowledge of biological mechanisms of replication by     
2:02:59     
clarifying the conditions that any self-replicating system must satisfy in by providing alternate explanations for     
2:03:06     
empirically observed phenomena the fabric of artificial self-replicating machines can also have     
2:03:11     
diverse applications ringing from nanotechnology to space exploration so this kind of goes through     
2:03:19     
actually there's a nice map here of it's a lineage of works in the area of     
2:03:25     
self-replication so a solid line in this diagram represents a close relationship between two Works while the latter may     
2:03:32     
be an extension or an implementation of an early so we start with Von neyman's work in the 1940s we can see up at the     
2:03:40     
top and then we go down to the work of arbi of Smith of cod of chiny more     
2:03:49     
Jacobson more what's penr and P so RB is interesting because RB is of     
2:03:55     
course doing artificial intelligence work um in the 1960s I get I RB U has     
2:04:02     
done a lot of really interesting work in historically I think he's retired now     
2:04:07     
not no longer active as a researcher but having done a lot of really interesting work in in AI um in the 60s and 70s and     
2:04:16     
80s so uh of course the author of this paper is related to B's work um our B     
2:04:24     
had an influence on a number of different types of work um and and you know you can see     
2:04:31     
that this persisted down to the era of the 1990s and so you see in the legend     
2:04:37     
that these squares are cellular automet so RB pursued the cellular automa path     
2:04:43     
and they had like some descendants uh programs in circles here ratle amillo     
2:04:50     
1972 took inspiration from Von noyman to build out you have dud me uh Rey     
2:04:58     
developed Tiara and then uh John kosa who developed some things in evolutionary programming so that was uh     
2:05:06     
using programs so this was of course uh evolutionary type programs then of     
2:05:12     
course you had in the Triangle you had strings you had Lang you had uh Morris     
2:05:18     
and vetto so these were uh strings and I guess there were connections there with     
2:05:25     
um uh cognitive modeling and then other in the in the     
2:05:32     
um in this shape here the diamond you have uh freus     
2:05:39     
Jr uh NASA project rebec Jr and I guess these were more of like the     
2:05:45     
synthetic uh approaches to synthetic life so you know there's a lot of stuff     
2:05:51     
that kind of diverged from Bon nyman's early work um and took different     
2:05:58     
forms and so that's very interesting and and it kind of goes through all of these kind of areas of work from cellular     
2:06:06     
autometa to you know different sorts of universal Turing     
2:06:12     
machines um and and sort of the logic of replication so there are a lot of     
2:06:18     
aspects to this work that if you're interested in uh you know programs that     
2:06:24     
replicate or systems that have biological properties Learning Systems     
2:06:30     
especially this is something you might want to explore and think about and maybe follow up in some of these works     
2:06:38     
so that's um that's that paper and then this other paper here is from     
2:06:44     
2020 um this is from um a series of authors here Jang at all     
2:06:52     
and it's from uh nature and it's a system hierarchy for     
2:06:57     
brain inspired Computing so the connection here is that we're establishing these kind of models of     
2:07:04     
modeling neuro you know neuro inspired or biologically inspired Computing and     
2:07:10     
how do we kind of take these properties of neuro and biological systems and     
2:07:16     
build like kind of this framework for understanding these things both for artificial systems and for     
2:07:22     
systems um bi better understanding biological systems so this is where they develop a     
2:07:29     
systems hierarchy so uh the abstract here reads neuromorphic Computing draws     
2:07:35     
inspiration from the brain to provide Computing technology and architecture with the potential to drive next way of     
2:07:41     
Computer Engineering uh such brain inspired Computing also provides a promising platform for the development     
2:07:48     
of artificial general intelligence but unlike conven Computing systems which     
2:07:53     
have a wellestablished computer hierarchy built around the concept of Turing completeness and the vanman     
2:07:59     
architecture so we talked about that with respect to some of these models of     
2:08:06     
um uh some of these models of self-replication there is currently no     
2:08:12     
generalized system hierarchy for of understanding for of completeness for brain inspired Computing so we don't     
2:08:20     
understand how say TR completeness fits into brain inspired Computing nor we     
2:08:27     
have any analogies to the vment architecture it's in terms of like computational Theory or sort of kind of     
2:08:33     
Flying Blind and like the ter completeness aspect you know if you're going to develop a system that is sort     
2:08:41     
of mimics something like a biological system or mimics a comput you know a     
2:08:46     
complete computational system where you can perform any computation you need this aspect ofering completeness and so     
2:08:54     
we don't really have that in uh bioinspired uh Computing and neuromorphic architectures we just     
2:09:00     
simply have an architecture that we have to sort of ascribe these computational principles     
2:09:07     
to um this affects the compatibility between software and Hardware impairing     
2:09:12     
the programming flexibility and development of productivity brain inspired Computing okay so again brain     
2:09:19     
inspired Computing is great because we can Leverage The Power of the brain but     
2:09:25     
understanding as a computational paradigm we we're a long ways from doing that because we don't have these basic     
2:09:31     
concepts sort of mapped to the system itself so in this paper they try to     
2:09:37     
solve that they propose neuromorphic completeness which relaxes a requirement for hardware completeness and a     
2:09:44     
corresponding systems hierarchy which consists of a Trin complete software abstraction model and a versatile     
2:09:50     
abstract neur morphic architecture using this hierarchy various programs can be described as     
2:09:57     
uniform representations and transformed into the equivalent executable on any     
2:10:02     
neuromorphic complete Hardware so the neuromorphic hardware has to have these components you have this hard so you     
2:10:09     
have a hardware layer that's compatible with a software layer that can do can do     
2:10:15     
you know can perform different tasks or perform different computational functions and you know it's not like     
2:10:22     
restricted to C only certain functions you can do any set of functions you can think of um so this ensures programming     
2:10:30     
language portability hardware completeness and comp uh compilation feasibility we Implement tool chain     
2:10:37     
software to support the execution of different types of programs on various typical Hardware platforms demonstrating     
2:10:43     
the advantage of our system Hier including a new system design Dimension introduced by the neuromorphic     
2:10:49     
completeness we expect that our study will enable efficient and compatible progress in all aspects of bring     
2:10:56     
inspired Computing systems uh facilitating the development of various     
2:11:03     
applications so this is kind of their model here you have the software layer     
2:11:09     
the compiler layer and the hardware layer and all these kind have their own aspects neuromorphic chips as the     
2:11:16     
hardware you have these different U you know     
2:11:22     
configurations on the left you have the neuromorphic or the brain inspired Computing hierarchy on the right you     
2:11:28     
have the modern computer Computing Hier so you can see that on the left you have these neuromorphic chips on the right     
2:11:35     
you have general purpose chips such as CPUs and gpus and so what they're doing is they're mapping what we know from a     
2:11:41     
turning complete artificial computer to a neuromorphic computer and thinking     
2:11:48     
about this in terms of creating a neuromorphic a complete um system so you     
2:11:55     
have the hardware layer where you have the neuromorphic chips being mapped to memory in an inter connection network so     
2:12:02     
this is very much like the instruction set architecture of the Von Lyman architecture in art in artificial uh     
2:12:10     
computers and then you have this compiler level so you have these     
2:12:15     
analogies here and then you have the software layer where you have applications a neural Network framework     
2:12:21     
for the brain inspired Computing hierarchy applications and programming language is the mod modern Computing     
2:12:28     
hierarchy so it's a matter of mapping from the Von nyman architecture to a     
2:12:33     
brain inspired architecture all the well trying to make this sort of at the software level Trin complete but at the     
2:12:40     
compiler and Hardware level Nur morphic complete so this kind of goes through     
2:12:47     
some of the aspects of using synapses and dendrites and other things uh other functions in     
2:12:54     
neuromorphic Computing and thinking about this as you know kind of a model     
2:13:00     
for computation so you have all these components you put them together and you try to derive this turn complete     
2:13:09     
system um so yes this is a very good paper too um it kind of links back to     
2:13:16     
self-replication in that you know what you're trying to do is you're trying to build these or you're trying to map     
2:13:22     
between these biological functions and these computational functions and trying     
2:13:27     
to figure out how those things uh work at a functional level but also at a theoretical     
2:13:37     
level yeah it's interesting yeah I haven't seen that     
2:13:46     
kind of discussion around in in neuromorphic Computing um     
2:13:51     
again I want to digest that yeah if you've got a PDF oh well actually I     
2:13:58     
didn't check um so yeah yeah let just see if     
2:14:05     
that's that's see if that's available from the usual sources oh well I can put the PDFs     
2:14:11     
in the slack so okay okay cool cool cool     
2:14:17     
yeah yeah it's it's it's interesting I um     
2:14:25     
uh I forget now the exact context of the conversation     
2:14:32     
but you know we're still certainly as part of     
2:14:39     
Celsius like synthetic biology um     
2:14:46     
uh our ability to get work from biological systems yeah is is     
2:14:55     
still infancy doesn't doesn't seem to do it     
2:15:01     
justice it is it is a desired goal and certainly trying to get Computing work     
2:15:08     
from from biology is     
2:15:15     
um is you so it'd be interesting to see     
2:15:20     
where you know how much um how much that relates to kind     
2:15:28     
of yeah I I just haven't seen that in the context of like spiking real Network kind of modeling which see you know     
2:15:36     
seems to be the majority not not all but the majority of of neuromorphic     
2:15:42     
computing kind of work right yeah um but um but it definitely relates     
2:15:48     
to this this you know uh what I call orac which is the organoid     
2:15:55     
research and augmented Computing where you know like a hopefully you     
2:16:01     
know and what what Thomas Harding and and the Baltimore declaration people call     
2:16:08     
organoid intelligence yeah yeah right is is     
2:16:17     
um you know like like at what point do our biologic iCal models become kind of     
2:16:22     
relevant for computing yeah right um and     
2:16:28     
U and not not directly relevant but just certainly in terms     
2:16:36     
of um some some amazing biology work right     
2:16:41     
is that it was the ventner institute's um minimal cell     
2:16:48     
workshop and you can see their videos in terms of the kind of synthetic you know     
2:16:56     
synthetic cells and well they're not fully they're not fully synthetic     
2:17:01     
right yeah but just just the interface of of like the really interesting work     
2:17:09     
um that um is is in synthetic bio is is its own     
2:17:18     
direction right because like like he's very much     
2:17:23     
keeping parts of like like like a big part of that Workshop was which     
2:17:30     
organisms are are interesting in this minimal cell project     
2:17:37     
right um and you know and it seems to be which which are Goods     
2:17:45     
vessels for us to hijack yeah     
2:17:51     
um and and interesting interesting you know um natural organisms to to yeah     
2:17:59     
modify and work with so yeah anyway     
2:18:05     
hopefully you know potentially it will come around to helping helping us     
2:18:12     
understand how to better engineer biology yeah all right I think that's it for     
2:18:20     
today uh thanks for attending and see you next week take you take care BR take     
2:18:25     
care bye bye
