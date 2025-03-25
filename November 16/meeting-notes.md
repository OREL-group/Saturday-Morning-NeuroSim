## Meeting Recording

[YouTube link](https://www.youtube.com/watch?v=AZiZQvMtk2s)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113494431585099435)

## NOTES
Jesse's talk -- overview of high-level concepts. Management and leadership for innovation (navigation).

* tailored for nuts and bolts. Navigating spaces: mountains, monasteries, and metropolis model. 

* Krakauer --> developing ideas in stages. Bring about newness: effective leadership -- ideas in stages. Keep in mind as you are a leader.

* 40 minutes, very dense. Many of these could be blog post-type things. Data ethics, impact statements. What are you modeling, demonstrating for success?

* how do you push a theory forward (science principles)?

* work things out into a talk --> how so we define? Then work out the details. Management towards a vision. Ways of thinking and operating (a day well-spent, not just doing research, being involved in community).

* VASO (captures volume). Structural resolution (sub-mm).


Beyond demo-or-die (certain amount of intentionality). Offer a series of frameworks. Idea generation -- process of putting into practices.

* taken from cardiac imaging --> balanced steady-state imaging. 


Technoplanar imaging is the standard. Target things for 2025. Notion vs. Excel.

* cart before horse, need a list of to-dos for next year.

* section about grants and funding (contrast to noise).

* innervations are important -- between organs (regulate each other).


Internships, conferences, etc. Theoretical/research movements.

* building package for a distro vs. containerization (Flathub package). Docker, Flathub.

* create package for dependencies (old way).

* intelligence: solve the same problem in different ways.

* expanding the cybernetic palette.

* ThoughtForge -- vehicle can assess its own damage, respond appropriately.


Karl Pribram: writing a message with a foot. Active Inference.jl -- team working parallel to RxInfer 
(ML group).

* reactive programming style and talking about reactive systems. Behvioral modeling group (#cog-futures). 

* cognitive futures --> cognitive architectures as part of behavioral analysis (working in Julia).


Ryan Smith: where Active Inference meets RL. Computational Psychiatry.

* talks from Karl, no emphasis on Ryan's relation of matrices to RL.

* Rich Sutton talk -- foundational work in RL. Connect to Ryan Smith tutorials. Place ActInf into a historical context. AMII (Alberta Institute).

* OpenMind -- dynamic Reinforcement Learning. Return to a continual learning approach.

* apply to be a fellow -- braing thread together. Yarrick --> SciOps, tap for another event, open-source sustainability.

## TRANSCRIPT

Transcript
0:00
all right when don't we get started then um so welcome
0:08
um and this week we didn't really do anything
0:13
except the active inference Symposium which was a lot of work uh on our
0:20
end uh we'll talk about that I also attended the narrow AI
0:25
Workshop so that was part of the week two uh we didn't have a diva worm
0:33
meeting and the other meetings we had to postpone because of the workshop and the
0:39
Symposium so why don't we get into that I'll
0:44
review what we I'll review the active inference Symposium this week and then
0:49
next week I'll talk about the nari workshop because as much as I've really enjoyed that um I haven't gotten the
0:57
notes together on so I've posted the links to the live
1:03
streams in the general channel so this is the active inference
1:08
Symposium uh and and so this is the way it's being presented to the world so we
1:14
have actually three live streams so what uh Daniel fredman uh does and Daniel
1:21
fredman is the person who kind of runs active inference Institute I mean he's
1:27
kind of the main person there other people people involved but he's like kind of the Visionary and the central
1:33
person and everything he he makes these live streams on YouTube and so they varying
1:40
lengths of time and this Symposium is basically three uh live streams two of
1:48
them being where all the talks are and then there's another one that's another type of uh kind of like a workshop or
1:55
something these are both 10 hour more than 10 hours a piece so I I put a
2:01
disclaimer here warning these are like 10 hours a piece you'll have to browse the streams to find the individual talks
2:08
so if you click through you'll go through and there'll be all these talks and you'll just have to kind of Zoom
2:13
through and find the one I think there's a plan to annotate the streams later but I'm not
2:19
sure you know when that's going to happen Okay so it was a good time um you
2:27
know we were planning on this and and I I we did some planning ahead of time we
2:33
had four talks from the group which is good it's a lot of work um and you know
2:40
the uh I had to get in touch with Stefan Bowman I had to schedule time to
2:46
pre-record which is fine it went well um and so we have that talk Jesse
2:52
contributed a talk which didn't make it into the live streams but we do have it on our YouTube
2:57
channel um I did one talk on open science and open source and another talk
3:04
on cybernetics the purpose purposefully mind nonstandard cybernetics talk and
3:10
that's basically recapping a lot of the stuff from our cybernetics group some of
3:15
the stuff from our cognition Futures group and then some additional things in
3:21
included let me go to the uh let's
3:27
see so I've got a bunch of screenshot here I'll just kind of walk through them so these are the live streams uh part
3:34
one and part two uh Daniel kind of did this uh courageous task of Hosting most
3:41
of both of them so it's like these huge long 12-hour Marathon sessions that were
3:49
you know he was mcing everything and it was great I mean you know I don't know I think he had a little bit of help from
3:55
other people but we got through it and everything uh we we contributed like three things
4:03
to these live streams but there's so much interesting content in the live streams that I'm going to go over and
4:09
I'm just going to kind of scratch the surface of what's there because there's just so much there you know there's Carl
4:16
friston and there are other people who are you know really kind of central to
4:23
some of the themes in The Institute over there so you know they're focusing on
4:28
active inference free energy principle um you know and then some
4:34
other a light topics there a lot of mathematical topics and software engineering topics like basically the
4:42
software that people use the model active inference and a lot of cybernetic stuff too I was
4:48
surprised um computational stuff and um
4:53
a little bit of educational stuff but not very much uh but anyways let's go through it so that's live
5:00
streams uh this is a shot from uh one of Carl friston's his he he started sort of
5:07
kicked off the first live stream with a discussion of the free energy principle
5:14
and active inference and he's going here he's talking about Maxwell's demon our
5:19
favorite demon where it's talking about active data selection so in this case I think he's talking about training a
5:26
model based on like selecting data in a certain direction so the idea is that
5:32
you select data in a certain direction and you can facilitate learning and so
5:38
this is what we call Active data selection does a sequence end in a reward yes admit the sequence for fast
5:45
structure learning no ignore the sequen fast structure learning furnishes a generative model of events that lead to
5:52
a reward and nothing else and so that's that's you know he goes through a lot of that um that's the
5:59
first talk in the first live stream uh then there was this uh talk I
6:05
can't remember oh this is in the first live stream as well Dynamic prior preference learning for scalable robust
6:12
deep active inference so this is another application to I guess it's
6:18
to no I don't know if it's deep learning or if it's something that's resembles deep learning but this is a good talk so
6:25
this lab here uh the neural adaptive Computing Lab at Rochester Institute of Technology that's run by
6:32
Alexander orobia I think we've talked about orobia in other um contexts and so
6:40
he runs this lab and we had a number of talks from that lab and a Robia is interested in
6:47
cybernetics interested in a lot of these type of topics around active
6:53
inference and so this yeah this person here uh they
7:00
presented on this um topic it's really interesting stuff really interesting
7:05
stuff okay um this is an image of this is from
7:10
another talk this is I'll get to the the ti I think I'll get to the title slide
7:16
in a little bit but this is uh a roboticist he works in Industry who
7:22
developed a robotic control system from the homeostat
7:27
from uh from uh WR asb's
7:32
homeostat and had a lot of really interesting insights into the good regulator theorem and what Ashby was
7:40
trying to do with the homeostat and how it connects to Modern Neal networks so
7:45
this is where you have this homeostat which is the picture up at the top it's
7:51
a set of nodes connections and weights and it tries to instead of
7:56
selecting for the optimal weights it selects for the most adaptive weights it selects for this Ultra stability and
8:04
homeostasis and then the nodes kind of coordinate themselves in different ways
8:10
so they've actually implemented a version of the homeostat for robotic control uh and you you couldn't get into
8:16
the a lot of the details because it's some of it's proprietary but suffice it to say
8:22
they're using the good regular theorem and and Ashby's homeostat to kind of
8:29
applying in a way that's interesting this is another slide from
8:35
the same talk this is uh talk in so he talks about the homeostat he talks about
8:43
this homeostatic Network and then talks about embodiment because they're they're applying it to Robotics and gives this
8:49
example of a network where you have this homeostatic Network that's taking
8:55
information in from sensors mapping it to motor so it's like a a brenberg
9:00
vehicle type model and so this is where you know this is a kind of a undirected
9:06
homeostatic Network where motor actions and sensory expectations become in
9:11
trained into the homeostatic self-maintenance process so again this is I was kind of
9:16
hoping we could find some papers on this but I don't think they're there at least not
9:22
yet okay um this one here is uh talk was actually in part
9:30
two and it's kind of towards the end of the session this is Andrew B
9:36
Pasa and the uh talk is active inference is a framework for social science agent
9:44
based modeling so this is uh stuff that the Institute is working on with bof
9:49
firms and so it's like this organizational approach that is influenced by active
9:57
inference and more generally by biological systems so this kind of goes through uh
10:04
some of the stuff that they're doing um you know this is It's a Long
10:11
kind of tutorial working on some problems so this is all in the live
10:20
stream uh this is actually a software called NGC learn and so this is
10:26
something that they've Al U I think think it's the uh the lab run by
10:32
Alexander arobi again and they did the stuff NGC learned uh where they they
10:37
kind of implement a lot of things with respect to um active
10:44
inference um so there was a whole tutorial on NGC learn in the in the
10:50
session I think it was in part two and this is of course the title
10:55
slide yeah it is from that lab uh this say William who's kind of maintaining
11:01
the software this is an introduction to NGC learn a computational neuroscience Library so this is actually for looking
11:09
at computational neuroscience and active inference and that's and he kind of goes
11:16
through a tutorial in there um this is actually something we
11:21
were talking about last time this is rx infer so they actually had in part two they had a overview of RX and for a
11:29
library for scalable probabilistic programming actually I think we talked about this last week in the
11:34
administrative meeting and so didn't make it to one of our main meetings but this is what they were talking about I
11:40
don't remember what we were talking about with respect to RX and for it was a lot of like isn't this software cool
11:48
uh does active inference it's you know but this is a set of libraries you can use for this kind of
11:55
approach so we have two uh pieces of software here uh njc learn and RX and
12:01
fur and so those are kind of interesting with respect to this de and Bulman talk
12:08
because he talked about uh neurodes but of course neurodes is the sort of
12:14
containerization strategy for software it's all I'll talk about that in a little bit keep that keep a pin in
12:23
that then uh okay so this is the the talk this is the person who
12:30
created these you know is creating robots inspired by Ashby and inspired by
12:35
the good regulator Theory so this is a company called thought Forge this is Matthew Brown so I think maybe we talked
12:42
about Matthew Brown um I think uh Morgan brought him
12:49
up this is real-time active inference for adaptive robotic control so this is
12:55
where we have the robotic control um yeah if when you are able to
13:01
speak um Morgan you know maybe you could tell me a little bit more about this and uh because I think we did talk about
13:09
him but that's that's the talk and that was in part two of the uh live
13:15
stream been in part one if we go back to part one we have these uh but they did
13:21
with the registration is interesting everyone who registered had to fill out some sort of a survey of what they were
13:28
working on with they were interested in and then um they they some of the
13:34
organizers created these word clouds so basically the way World Cloud works is
13:39
that if you have more mentions of something it's bigger fewer mentions of something it's smaller and this is from
13:47
across I don't know how many registrants maybe at least a hundred uh where you
13:52
have these different interests and so this is where this is like the personal background of the attendees so it's uh
13:59
AI is a big area research you know computational
14:05
psychology systems Neuroscience cognitive
14:11
um uh philosophy is a little smaller projects
14:17
multi-agent models and Linkedin made it in there somehow I don't know but um you know you
14:24
can see the sort of the areas people are interested in it's not surprising but it's it's nice to get
14:30
that sort of feedback about what people are thinking about why they're coming to a conference what they want to get out
14:37
of it perhaps so those are all not not surprising you know those are all
14:42
expected categories and so I'm surpris brain is so small but you know uh it's
14:49
an imperfect methodology because people will just put anything in but anyways um
14:54
that's that's for the personal background of the attendees
14:59
then this is how are you applying active inference so this is a different question it's basically not your own background but
15:06
how you're applying it which is maybe a subset of the first question but so again we have systems very large NN
15:14
which I assume is neural network smaller AI Theory which is interesting because
15:20
you know that's what we're interested in um you don't think of applying things to Theory but a lot of people in this group
15:26
do research of course Dynamics agents habits that's
15:34
interesting um multi-agent information uh research of course
15:42
model I'm which isn't informative and processing so again nothing really
15:48
unexpected there um it's really telling us that people are applying things as
15:56
systems as applications of course something having to do with Theory or
16:02
theoretical uh a lot of dynamical systems cognitive psychology habits and
16:08
then you know maybe research applications and um even governance is
16:14
in there so this is where kind of this is how serendipitous our contributions
16:20
were because you know we talked about open source and open science and I gave a talk on that and it
16:27
was really kind of fit in and I didn't even see this word I I think I may have seen it once after I did the recorded
16:34
the talk but it really fit into a number of areas like you know governance and systems and kind of
16:42
getting work out there and you know software research software tical development so it's very
16:49
serendipitous that we did this um and and some of the topics we covered so
16:59
okay moving on uh so okay in part two was when neuro the neurodes talk
17:04
happened and um what I like I said I had to pre-record it because the time zones
17:11
were you know too far off but that's okay because Stefan I think was very generous
17:17
for this time very amenable to doing the the re reccord you know it was got him
17:23
away from like the morning schedule and it was very well received I think did I
17:29
I pre-recorded it then we did the live stream then Daniel had asked me some really interesting questions I asked
17:36
Stefan first of all about some of the questions like you know he he presented
17:41
on neurodes which a lot of the work focused on neuroimaging which is great because there are neuroimaging people in
17:48
you didn't see it in the word cloud but there are a lot of people who were interested in neuroimaging uh Carl friston of course
17:54
made his uh career on neural Imaging but you know it's like okay I said well it's
18:01
a containerization strategy so how do you apply that to a larger audience like
18:07
how could I take active inference tools and put them in here and as it turns out
18:12
you can very easily do this you can very easily customize the narrow desk sort of
18:18
framework and you know that so that's very much applicable to what people are
18:23
doing in in the active inference Institute some of those software packages I mentioned
18:29
the other thing is that you know it brought up a lot of interesting questions about
18:34
replicability and you know open uh science where you know you you can just use something in the cloud or you know
18:41
have a tool that's you know gives you some capability as an organization so it
18:47
was really interesting stuff and I think uh Daniel was really turned on by it
18:53
terms of like you know how we can take lessons from it um and so that's good
18:59
and so yeah it was really good talk um it's on so we I I'll show you later but
19:05
we have a a playlist on our YouTube channel of all the videos as
19:11
well this is a a fun talk by John clippinger uh or a fun cartoon sure it
19:19
was a fun talk as well this is in part one so this is a cartoon by Leighton it's robots whipping humans
19:27
into submission making them do work and it says to think this all begin with
19:32
letting autocomplete finisher sentences which is like uh you know autocomplete is
19:39
usually like it's it's one it's a very old computer science problem where they
19:45
tried you know was very early language modeling with Markov chains and they basically tried to predict the next
19:51
state or the next thing in a sequence and so this is well before large language models and there I just did
19:58
this in project management I talked about um you know the history of uh like
20:04
automated code completions it's really interesting at this came up but this is
20:10
I talk Markov chains all the way and it talks about some Markov chain approaches
20:16
to active inference it's an interesting talk um if you're interested in mathematical modeling would be something
20:21
to look into so another word about this is that in the active inference
20:26
Institute we have also sorts of people who kind of join in so we have people
20:32
who are doing you know different projects sometimes it's software
20:38
engineering sometimes it's uh you know senior scientists doing like different topics that are relevant to the to the
20:45
topic at hand computational stuff so you can see that there's this very loose Association of people around the
20:52
Institute doing different things that are somewhat relevant to you know some of the main projects but still very very
21:00
fertile intellectual environment okay so now this is our talk
21:05
on purposefully non-standard cybernetics so this is where we have this was in
21:12
part one we towards the end of the stream and highlighting the cybernetic
21:18
interest group uh and it was really well received um you know they really I think
21:23
they really enjoyed it because I like I said there is this theme of cybernetics
21:29
in the group so there were some other talks where they where they talked about different aspects of cybernetics and
21:34
it's interesting I wouldn't have thought that I didn't realize that there was such a latent interest in cybernetics in
21:40
The Institute but here we are B hippolito was also there um she
21:47
did this talk dysfunctional markof blankets from stuck states to adaptation so this is talking about markof blankets
21:53
which is one of the ideas in active inference uh um you know markof blankets
22:00
basically serve as the boundary of a system or to Define dominate the system in some way and so this was a nice talk
22:07
this is at the end of part one if you go into the stream so yeah it was nice to
22:13
see this is our playlist for active inference Symposium so I put together
22:19
the four talks we have purposefully known standard cybernetics we have the overview of Open
22:25
Source and open science we have Jesse's uh presentation on management leadership
22:32
on navigation or research plus Innovation and then the neurodes uh talk reproducible
22:40
neuroimaging for everyone so those are all on the on the YouTube channel the orthogonal research and education lab
22:46
YouTube channel not the uh active inference YouTube channel and it's under
22:53
active Symposium that's the playlist name
22:59
okay so this is a paper from one of the talks actually this is one of the talks kind of like the the paper from for the
23:07
talk so this was in part one this is uh was Mark Miller who gave this talk and
23:13
this is uh you know the usual suspects in active inference uh and then the
23:19
paper is called resilience in active inference so it really kind of goes through some uh complex systems
23:26
discussions on resilience and other other sort of talks uh other
23:33
topics on adaptation and things like that so you know that's you know again
23:39
kind of uncovering some of those themes that we uh maybe the Casual Observer doesn't realize are part of active
23:45
influence a lot of stuff having to do with complexity and complexity related topics that are kind of latent and just
23:52
sitting underneath everything else but you know there there are things that many things to explore there
24:01
this was an interesting talk in part one this was uh Groove is the musical glue
24:06
for social bonding this is Leonardo Miler Rodriguez um this is this is a
24:13
neuroscientific and crosscultural perspective so this is kind of I guess applying active inference to music and
24:20
to music theory this talk is by Devin Bay um this
24:27
was in part two accounting for multiscalar and conscious psychobiological phenomena in the active
24:33
inference Paradigm so this is again like you know thinking about some of the
24:39
behaviors in you know uh some of the you know maybe not predictive
24:44
behaviors per se but just kind of like thinking about the different behaviors that you can have in you know if you're
24:52
applying active inference or something this is the active inference
24:57
Institute uh YouTube channel this has uh the live streams but also if you go here
25:04
and subscribe you'll get updated on their different streams so they do a lot of different streams of course uh they
25:10
do the uh topical live streams they do the uh they have they're writing a textbook and so there's a textbook group
25:18
that they're doing live streams of they're doing live streams of some of their decentralized governance stuff
25:25
that they're doing and you know they have other media in here that's really interesting
25:32
um you know again it's all kind of managed as a live stream so
25:38
it's you know it's not a not pre-recorded videos it's interesting how they can do that it's just a very
25:44
exciting kind of approach but I don't think I'd want to do that for our lab because just
25:51
because um but anyways it's it's a really good uh YouTube channel to subscribe to of course all the stuff
25:58
from the Symposium is there as well okay so this is what I was talking about about the purposefully nonstandard
26:04
cybernetics talk so this was a message I I think it was from Daniel uh it's just
26:10
kind of back to me um and this was just kind of unsolicited so it's nice um this
26:17
was I guess after it played and he says purposefully non-standard cybernetics is great I think it expands SL reconsiders
26:25
the cybernetic pallet and retex on pre- taxonomize this types of behavior
26:31
in important ways so that's interesting um I'm glad that they enjoyed that um I
26:38
putting that together you know with some of what Jesse was doing some of our conversations some of what I'm
26:43
interested in kind of pulling it together and that's what we ended up with and I'm kind of glad that you know
26:51
we were able to do that so you know if we don't remember we're kind of going
26:56
we're kind of starting off at the Rosen gluth that all
27:01
1942 or 43 paper on uh tileology behavior and purpose moving out towards
27:10
you know the view of like what is theology having some historical
27:15
information about these different themes and then moving out towards different
27:20
papers in the literature that kind of get at some of these issues of the
27:27
behavioral tax on they proposed back in 1943 so you know reorganizing it
27:32
thinking about it more critically Etc so they really enjoyed that that was
27:37
good um and I think you know the cybernetic pallet is interesting because
27:42
um you know this is again we have some approaches of cybernetics that you know this stuff
27:49
isn't static I know these classic papers exist but one of the reasons we're doing the cybernetics reading group is to
27:56
expand what was being being said there to update it to expand it to see where where it fits in the modern world and so
28:04
I think we did that very effectively um that's good this is the neurodes talk this is
28:10
Stefan Bulman uh there he is up in the corner uh I enjoyed this very much he
28:15
kind of went over a lot of interesting topics and you know discussed sort of uh
28:21
you know his their approach to open software um their sort of why they did
28:26
it you know why they uh spent the time to develop this containerization
28:31
strategy they did a lot of empirical tests to show that like you know containerization is superior to running
28:39
things on your own computer and distributing software and every using different software
28:45
Hardware um settings and um you know ending up with different results and so
28:51
I think it was a great uh great sort of demonstration of that and then we discussed how to create uh your own kind
28:59
of put your so own software into containers or you know there are ways that you can use what Nares has done and
29:06
instead of using it for Neuro Imaging use it for something else like an active inference piece of software and then in in the talk on open
29:14
science and open source I talked about uh some of the other Linux dros uh like
29:20
neurod Debian um where they you know allow you to put you know have these builds or can
29:28
put like specific maybe like active inference specific software package it
29:34
as part of the operating system so it's just kind of you know runs in that
29:40
environment so it was really I think it was really well received um and you know
29:45
it's Food For Thought for active inference Institute because like I said there are a lot of packages that they
29:51
use and so it's you know where you know is there an investment to be made there
29:59
this is the talk an overview of Open Source and open science this is something that Daniel also thought was
30:04
very Visionary and very good at a high level um and I I encourage people to
30:11
look through this talk I know we talked a little bit about it in the planning sessions where we said you know um this
30:19
is you know like the series of issues that are important in building uh sort
30:24
of a a strategy for open source and open science so you know we have uh a lot of people
30:31
talk about making things open source sometimes people just throw software up on the web and none of that is really
30:38
good for a number of reasons um you know saying that everyone should you know mandating that everyone
30:44
should uh you know be maximally open source or open science um can you know
30:51
pave over a lot of the differences between organizations sometimes they have time to invest in building like
30:58
infrastructure for you know uh annotating data sets preparing things
31:04
for uh being open so if I have a you know a set of research tools or data
31:10
that I want to put up I can put it up and share it but if people can't use it or understand what's going on then it's
31:16
not worth anything so you know having those strategies in place are good and
31:21
then it talks a little bit about infrastructure and some of the tools that we might use some of the
31:27
combinations of tools that might be sort of killer apps in the sense of uh making
31:32
you know enabling a lot more open source and open science are making it easier for people and then talked a little bit
31:39
about governance and that sort of thing also talked about some things like research engineering or research
31:45
software engineering and some other areas where you know where organizations need to invest to make some of these
31:53
things happen um and so it's very interesting I think Daniel was very impressed with sort of the breadth and
31:59
depth of the of the talk and this also advertises our open
32:04
source interest group so I actually talked a little bit about our open source sustainability models here where
32:11
I advertised some of that work being done and so and there was some work you know of course the stuff that Brian
32:17
mccorkel did on active inference but also the stuff that was done this summer on reinforcement learning and with LA
32:24
joang model so that is my overview act the act of inference for uh
32:31
Symposium I you know I mean there's so much more there I don't want to short shrift that stuff but um that's what I
32:38
those are the highlights I found
32:44
interesting yeah excuse me I've got a a bit of
32:51
aor bir but um uh I thought thought the I
32:58
thought the talks were great too you know and
33:05
um I think the one that
33:11
I I don't think you mentioned active inference JL okay you
33:18
know um that particular um that particular
33:26
team I mean the RX INF fur was great and
33:32
um and it is interesting the um the the
33:39
reactive I'm interested to know more about the the reactive programming
33:44
style yeah they they use they I mean that's that's part of the
33:50
RX um uh kind of that that particular group's
33:57
programming philosophy um and I think it's maybe a
34:03
double play on reactive in the sense that like um reactive is both a a
34:10
programming style as well as they're talking about
34:16
reactive systems you know yeah and
34:21
um but um yeah but I I just wanted to mention
34:27
active inference .jl because
34:33
um uh unlike the RX and fur team which is kind of like a machine learning
34:40
group um the uh I forget the lab's name it's
34:46
like like I ipab or something like that
34:52
um um they're a um
34:58
like behavioral modeling group you know yeah so it uh it somewhat relates to a
35:06
paper I dropped in uh cognition Futures on um fitting cognitive like yeah using
35:16
cognitive architectures as part of your cognitive modeling computational cognitive model okay um so kind of you
35:24
know act R and sore uh as as part of your kind of Behavioral
35:31
analysis um and that that's that seemed to be
35:37
their their particular um yeah like
35:45
like they were more cognitive people yeah or behavioral yeah modeling people
35:52
than than arver yeah and uh even though they're
35:57
both both working in Julia right yeah
36:02
um which is which is you know also also interesting but um and I they
36:11
um they were the ones that were maybe a bit
36:16
more uh at least running in up
36:23
to discussing the point that kind of Ry Smith
36:30
um had I think really emphasized and I don't know if he again like you know it
36:37
was hard to tune in for all you know all all 12 hours is a big
36:42
block like that um but
36:48
uh they got up to the point of kind of discussing where active inference kind
36:54
of meets reinforcement learn and and how it
37:01
um uh because because they were definitely talking about behavioral
37:07
modeling they were explicitly linking this to computational Psychiatry right
37:13
okay um which again you could just call you know
37:21
applied computational cognitive model and and um
37:29
uh yeah so it's it's um I don't know
37:34
whether you know I mean they had talks from Carl of course and um and I think maybe even a
37:43
few previous recorded kind of tutorial things um but I didn't see you know
37:52
didn't see the the the emphasis that um that Ryan
37:58
on you know how the active imprints like like you know directly relating matrices
38:06
that you know and the nomenclature that they use in the textbook to
38:11
reinforcement learning standard
38:19
terms you know again like I I still want to see uh I want to see
38:28
well I I I also dropped a link to um sorry let me see what the can't
38:36
remember now um so there there was a a talk from Richard Sutton yesterday well
38:44
no couple days ago but during the
38:50
um cognition fures no I think I put it in Frontier
38:58
projects yeah open mind research so
39:04
um anyway but it was it was Richard Sutton right who you know was at a
39:11
certain point was kind of like Deep Mind Alberta was basically created to
39:20
incorporate Rich son's group into mine right and um and the focus was
39:28
on just his his um kind of you know foundational
39:34
work in in reinforcement learning um I I'd love to
39:39
see um you know Amy or or Richard suton
39:46
in particular kind of connecting um the the kind of Ryan Smith
39:53
you know tutorials into the kind of you know just
39:59
just because Richard suon is like his textbook is like the reinforcement learning textbook you know like I I I
40:08
just wonder if he would have any any additional thoughts on kind of where
40:14
where you know placing active inference in
40:20
perhaps kind of historical context that making making some connections that haven't previously been discussed or
40:27
something like that and and this open see call again open mind
40:35
Institute sorry my phone is yeah open mind research so he he I I
40:43
like this um so he gave a talk just a couple days ago I think he called it
40:49
dynamic dynamic reinforcement learning and um and I I wasn't quite
40:56
sure where he going to go with that but you know it it it seems to be again
41:03
returning to this kind of continual learning um that that you know it's
41:12
crazy to think about training training tasks for one thing yeah when obviously
41:17
animals don't do that yeah and um or but yeah yeah and or like like and I think
41:24
we can say at this point that Sals don't do that and
41:29
um uh he I liked this U because he's brought
41:35
up Amy before but Amy seems to be just like his kind of post deep MIND
41:43
Institute um um that's that's Ami right
41:48
yeah but um uh but this is sounds like something
41:53
that he's developed for people who grad graduated they've they've you know
42:00
probably left Academia but um but still want to work
42:05
on you know what he would call the the Alberta plane and thinking about yeah um
42:14
foundational topics in reinforcement Mary and and you know again when he's
42:19
talking about it I think we're supposed to read um kind of continual learning in
42:26
that too yeah um and
42:31
yeah I think I I I think that would be a really
42:37
um you know if if I had one um so you know you can apply to be a
42:45
fellow at the open mind Institute yeah or open mind re open mind research right
42:52
um and um and
42:58
uh yeah I I think that would be a really interesting um uh start to to something with be you
43:09
know just bringing bringing some of those threads together and um and yeah I
43:16
I I just about the word cloud um I liked when they when Daniel was going over the
43:23
word clouds uh I forget who he was doing that with but he was kind of having a a
43:30
discussion about the word clouds okay um and and he was the I think the other
43:38
person was just like huh nobody's got llms
43:44
yeah yeah and I and I was like I was like good group good
43:51
group or you know I I I was just like yeah yeah you know no got L and that's
43:58
okay that's great yeah you know but but I mean they they yeah anyway
44:08
um you know they they come up enough right right like like we're not we're
44:14
not in any we're not in any llm winner yet right so
44:19
um uh but yeah so it was it was nice to see that and um
44:30
thought for I I I um I definitely caught that talk and
44:39
um um it was it was definitely you know
44:45
um interesting I can't I'm I'm blanking [Music] on the connections there um I did drop a
44:54
couple things in I think think
45:00
um great um yeah maybe braber vehicles
45:08
um there's a DARPA thing uh that I thought was interesting I think they
45:14
call it link um where the
45:20
vehicle it's something introspection I think is the ey in link and what this is is
45:29
is you know giving giving the robot the ability to to assess its own damage and
45:38
how to respond yeah um which I thought was a an
45:44
interesting you know um like additional additional layer yeah
45:52
um and it's it certainly reminded me of things
45:58
where you know um Carl PR would say something like you know why is it like
46:05
you've never been asked to like write with your foot before but if you if you
46:12
are told like you've got to write a message with your foot in the
46:18
pen you know you you would you would probably be able to create something that is you know messy but perhaps leg
46:28
right yeah and um and not not exactly
46:34
the same thing but but sort of right like like how to how to you know this
46:41
this this remarkable ability to adapt which I I guess is sort of also gets it
46:48
the um sort of gets it the the Levan likes to quote um William James right
46:57
intelligence is being able to to to solve solve the same problem in
47:03
different ways or something like that I forget how he phrases it um and uh yeah
47:11
so I I I couldn't think of anything in particular but you know I gotta say the
47:17
um robotics World U just has a bunch of interesting a bunch of interesting talks
47:25
um I forget which com conference was I don't know if the people are pre-recording for for noral PS
47:35
or um I know that there's there's other kind of robotic specific ones but
47:42
um um yeah great great Symposium and I I did not catch stens
47:49
unfortunately yeah I did did have things going on here um but uh but glad glad um
47:59
you know again like I was kind of joking to someone that um you know kind of a
48:06
tech tech person um that you know if anything I'm
48:12
I'm the old fuddy duddy who's you know cares about building packages for a
48:19
particular particular distro um and you know all the all the
48:25
kids are just containerizing and using whatever works
48:30
and you know one of the big controversies and in Fedora currently is
48:38
the the rise of allowing flathub
48:44
packages oh yeah yeah which is is kind of the same thing
48:50
you know um it's definitely kind of like a yeah so
48:57
it's it's suddenly the kind of the purity of the package in terms of you
49:03
know how how Fedora would would want you to would want your package to never
49:09
depend on internal libraries always use the system Libs and things like that
49:15
right so it's like if I wanted to package something and it depended on
49:20
three packages that didn't weren't already currently packaged in Fedora
49:26
like you know if you if you'd asked me 10 years ago it' be like well obviously I've gota I gotta create packages for
49:33
those dependencies first and then I can package the thing I actually want to
49:39
package and and these days it's just like you know one like in addition to a
49:48
package some you know the the the Upstream group would probably give me a
49:54
Docker option um but uh I see a lot of people just uh making flath Hub packages
50:01
out of these things anyway it it it's it's nice to see and um and it was nice
50:07
you know Yar did get in touch did get back in touch at least I did see that yeah you yeah yeah and so um I think you
50:17
know again like you can see from from yar's like project list and his in his
50:25
um I don't know if had to look at his Sops paper actually it did come up in the neuro neuro uh AI Workshop so okay
50:35
yeah yeah okay oh good good good um uh
50:40
but you know he he could be a really great you know
50:46
kind of um person to to tap further you know down the roads on on something like
50:53
open source sustainability or things like that um because you know this is
51:01
this is someone who's U yeah really been been doing it since he was you know he
51:08
was a student and um and you know he's he's a real he's
51:17
a a full-on Debian contributor you know which Debian has its own rules for how
51:24
you get that status and so it's it's pretty yeah yeah it's all good
51:31
um so yeah thanks Morgan for uh feedback and insights on that um yeah know that
51:38
was great yeah this is something we'll probably be revisiting for a while because there so much content there and
51:44
so many things to talk about and think about uh yeah so like I said I also did
51:51
the nuro AI Workshop uh I'm going to present on next week did the scub paper
51:57
it was interesting because that came up in the one of the sessions and then you sent that in the slack so I was like wow
52:05
is that the same the same paper so yeah and I'll cover that next
52:10
week the neuro neuroi Workshop is a little bit different it was almost it
52:15
was at the NIH but it was almost kind of a flavor of like DARPA you know because it was
52:21
like this topic that's out there you know it's like you had neuroscientists you had people had roboticist and it was
52:29
kind of like they were kind of trying to figure out where they all fit together um but but and then they had some good I
52:36
think they had some well phased questions that they kind of raised um kind of in advance so we'll come back to
52:43
that next week I got to prepare some things for that uh Jesse how are you
52:58
um all right it's been a a busy week for me but
53:05
um yeah um I've worked on a few different things I don't know what you
53:11
want to um discuss next but yeah um yeah I have a couple of articles but we can
53:17
we can discuss whatever you want if you'd like to discuss your the talk that you uh made for our YouTube channel
53:28
um it was it was okay it was um I wish I had a little bit more time to have it
53:36
the way I wanted it to be but it was a nice I think it's sort of an overview of
53:41
a lot of things a lot of like very high level Concepts that we've talked about it about uh you know M like man
53:50
management and and I don't know management and Leadership for Innovation and
53:57
uh like research doing really trying to think like it was a very wide ranging um
54:04
I use the term actually use the term navigation and I I think I I slipped in the start after the first slide
54:10
basically why navigation because it's not I don't want to do a talk about how to manage projects
54:15
specifically um that's something I think um I mentioning your project management
54:21
course and there's a lot of things that they doing details and and workshops and everything else
54:28
excuse me that are I think more tailored for nuts and bolts and and I think even
54:36
doing more detailed sort of writings ahead or discussions about that ahead or something that I'd like to do as we've talked about before but um in general
54:43
the talk was essentially about navigating the
54:50
different spaces and I use a little I basically kind of frame things in sort of the mountains monasteries in metrop
55:00
um sort of uh framework in attempts
55:09
of when to to kind of give a sense of
55:15
what arena or what what maybe more like not just Arena because I talked clearly
55:21
about um industry and Academia and and nonprofit or actually startup spaces I
55:29
talk about those Arenas specifically but also I think there's sort of a the mountains monasteries and in
55:37
Metropolis sort of lens is useful in that when you're trying to bring about
55:44
newness or new ideas or get to do new things so much of what
55:49
is I would I know a term like effective leadership or or good leadership is managing
55:56
the affordances of the space that you're in what kind of risk you can take and I talk a little bit about you know
56:03
different kinds of Institutions and what kind of risks they can take I talk a bit about
56:09
um the the ways of you know collecting
56:14
ideas as you're as you're processing um towards you know I mentioned tly Birds I
56:20
mentioned the idea of of collecting ideas I mention a lot of the different sort of higher level
56:27
um almost sort of a a I guess the word isest for but a lot
56:33
of just Concepts to keep in mind as you're going through as you're sort of a
56:39
leader in those spaces and a little bit as to what it's like to
56:45
be when you're not a leader too because I think I think I think part of it is not just you know the title of leader
56:51
but how do you work with a space that you're in either as as a a more Junior person who who has less Authority and
56:58
Direction and as a as a person who's offering Direction and offering space for people to do re Innovative things um
57:06
so it was it was a very very very broad almost it was really more like an overview talk um
57:13
about about that and I think um I'm like I'm all right with the talk I think
57:19
there's a few more details I could have slipped in there it was it was long it was 40 minutes and that's okay um
57:26
because it was it it felt quite um dense even though it was sort of high
57:34
level very high level everything was was like very broad Concepts and I think what I'd like to do in the future is um
57:42
really expand upon them like like many of the topics I were in there could
57:48
be um blog posts type things which I've set up a substack for to to make later
57:57
they could be like podcast episodes they there would be great discussions to really flesh out for people doing things
58:05
in those spaces particularly I would say and I've tried to weave this in a little bit I didn't do a tremendous I didn't do
58:12
too much of it I kept it I kept it as um I didn't make it an advocacy piece
58:19
um but but I could in the sense of um
58:26
I don't know um I one of the first things that I'm
58:32
writing for the I don't know blog series on this topic specifically is about um
58:38
defining success in terms of what you're doing
58:44
and I think that's the one thing I didn't put in in the main talk or really have time for or didn't want to get into
58:50
in that setting um was there's an implicit
58:57
deep um consideration for people I think everybody doing like really future
59:03
really trying to do like really Innovative work and and this is you could you could put into it like data
59:09
ethics or uh impact statements like whatever what you know there's different
59:14
components to it but but in a more advocacy sense I think there's there's a real
59:22
um a real sense of when you're when you're holding bu space or making space
59:27
or doing administrative efforts uh what is
59:33
it um what is it that you
59:39
are modeling or demonstrating or or building people towards in terms of what success looks like and is it success
59:47
defined by um you know what particular standards what particular Vision in the
59:53
future what particular because success in a very in one scope um and success on
59:58
another can look very different in terms of what it is that you're trying to both achieve whether it's like financially or
1:00:06
in terms of pure know what what you know what's considered scientific push pushing against scientific and idea
1:00:12
forward and a scientific way of pushing a theory forward um you know doing doing something rigorous that lets other
1:00:19
people test the merits of of an idea or a concept or a theory or a
1:00:24
principle you know like what what is it that you're trying to do and I think I think there's a discussion to be very
1:00:31
you know open about that in in in an ideal world you can be very open about that with a l with your lb with your
1:00:38
group with your organization and say what you're trying to do and I think I think um it's not often an ideal world
1:00:45
but I think that's something that is important to talk about particularly when when we're in a state of people
1:00:51
people I find a lot of people in you know um
1:00:57
a more Fuller thought about this sort of defining success and advocacy piece that I didn't that I didn't quite say is
1:01:03
essentially when you're training people to build the future and look at things what what are you
1:01:10
implicitly how as as you're doing the theory work how are you how are you
1:01:15
doing it in terms of both treating people but also like what to what
1:01:21
end and and what what what's happening in in terms of what you're creating and
1:01:27
how is it affecting how things are developing so that's the last sort of like two minutes two to three minutes of
1:01:33
My Talking where things I didn't say in the talk but things I'll kind of expand upon in in later writing about it which
1:01:39
is very much a little more think in a philosophical advocacy um normative
1:01:44
sense um but the talk centered a lot around our ideas to go back now the talk Center
1:01:52
lot around ideas basically things we talked about in the in the Friday meetings the go summer code meetings in
1:01:57
in terms of working in the different Arenas in terms of working with bureaucracy in terms of being a mentor
1:02:04
or a guide someone trying to be a mentor or a guide in various different Arenas and situations and things to keep in mind that's essentially what it was
1:02:10
about and I do think you know I think the talk could be refined and beenin off
1:02:16
in a bunch of other things but it was good to I know just make a sort of
1:02:22
artifact um to to discuss more so I hope to do that yeah yeah I think that's
1:02:30
great I haven't had a chance to look at it but I'll take a look I mean I've
1:02:35
looked a little bit at it but I haven't really bu into it I'll listen to it they could of uh give you some feedback but I
1:02:42
think that's great that you know at least getting an opportunity to get those ideas out into a coherent talk and
1:02:49
then you can take those parts of the talk and kind of explore those things is a lot like the other talks that we've
1:02:54
done where we're going to be going you know and using those as sort of a a way
1:03:00
forward for certain things like you know you can't really get to you can't get to the point of refining something you
1:03:06
can't Define it basically yeah and I I feel like I mean
1:03:14
this is this is much more of a I've been thinking about this topic at
1:03:23
large for a long time in the sense
1:03:31
of like like where does the topic fit like you there's plenty of books on
1:03:37
leadership and like like kind of your business business type books how to be successful and leading a team to some
1:03:44
end that vision and management towards the vision I like that's that's good and
1:03:51
important in its own way and there's like the far further end of sort
1:03:57
of I don't know advocacy stuff which is nice and important and I do of things I want to
1:04:03
say but that obviously but there's also the sort of um I think the more the middle ground
1:04:10
and what I talked like what I really really broadly out big big big just a
1:04:16
big high level outline on many terms is sort of
1:04:23
um as as you are either being guided or guiding
1:04:30
other people doing really Innovative stuff um what is that like because
1:04:37
that's it's not really a kind it's it's I think it's quite radically different than other kinds of I don't even want to
1:04:43
say work or employment which is true but um just like ways of thinking operating
1:04:50
like like ways of measuring your success ways of of thinking like oh I spent my time well
1:04:56
today yeah um I think it's different like I think I think it's it's very different space and so I think a lot of
1:05:03
people are in that space and a lot of our references for essentially okay well I put in nine hours today or I went to
1:05:09
the lab today or I got I did my experiment today like okay like like that's not none of that's bad um but
1:05:17
it's just I think I think there's a deeper conversation to be had about
1:05:24
like not not not just
1:05:29
doing research or science or whatever is you want to call it um
1:05:36
but being involved in
1:05:41
the well I spent a little bit of time in the talk talking about Community like I very I spent a few minutes on like demo
1:05:48
or die and going Beyond demo or die which is something that we' talked about I don't know three or four years ago
1:05:54
specifically but it's always been a theme Here of like like there's a reason for demo or die in terms of the very
1:05:59
broad concept demo or deploy or die of like having something to show people having some to say what to show people
1:06:07
but the broader comes of Beyond going Beyond Dem dies like that's really important to do but also like how are
1:06:13
you cultivating a lab environment where people can grow and share ideas and do this like do do the um I don't really
1:06:20
want to use the word softer stuff but I think that's a conventional way of talk about doing the sort of cult culating
1:06:26
things like you're not going to difference between sort of having a careful incubator or a garden with
1:06:31
seedlings developing very carefully because they're not ready to withstand you know
1:06:38
the in in the mountain Metropolis uh Monastery settings the
1:06:44
seedings are not ready to survive in the Metropolis yet um and KRA hour talks
1:06:50
about you know his kind of gu his role as this guide between people people developing their ideas and sort of this
1:06:56
mountains sort of more isolated more more um remote uh development process
1:07:04
and then you know the monastery is sort of a training ground where you have in-house discussions that are
1:07:10
cultivating but also challenging and the Metropolis is like okay out into the world and it's it's similar a similar
1:07:18
lens of like Beyond them or a die and what we talked about there is sort of um
1:07:25
that that cultivating this creating creating a administratively creating a
1:07:31
space for people to explore ideas and do work and how do you do that how do you
1:07:36
how do you do it knowing there's other things are going to en counter how do you do it knowing that like there's a
1:07:42
certain amount of intentionality that it requires um and there's a certain amount
1:07:49
of I don't know um
1:07:58
uh it doesn't it doesn't need to happen but it could it could so I don't know
1:08:04
there's there's many ways I could go I could talk about this for for a long time and like go different components of
1:08:11
it but I I do think it's it would be interesting to to flesh out a bit more and I think it's something that
1:08:17
um it's something I'm learning how to host discussions about because I'm able I'm able to we talk about it here and
1:08:22
it's coming up I had a really nice conversation essentially
1:08:27
um this week with um other people one person in particular is sort of about
1:08:33
like it's not just to to deal with so many of the problems the sort of intermediary problems that aren't just a
1:08:39
matter of you know pushing pushing a policy or research
1:08:46
forward it's also how do we you know um
1:08:56
enable and Elevate and Empower people along the way uh and and it it was it was nice
1:09:04
because the person I was talking to was a completely different very different field but it it was it was it was funny
1:09:12
how similar the the um I guess challenges were because to to deal with
1:09:19
lot of the deeper there sort of there sort of the the you know the problem at hand that
1:09:26
the the direct the direct surface on the face um face value goal of doing the
1:09:32
research of doing improving the policy improving the understanding of whatever
1:09:37
you know phenomenon whether it's you know um and I was raising a bit at the
1:09:44
complex world of like whether it's not complex and then more like able to be reductionist and a lot of symmetry and a
1:09:50
lot of you know more classical things or whether you're dealing with complex stuff whether you're dealing with like
1:09:56
uh equilibrium or or symmetry breaking things like like even in those spaces
1:10:03
sort of like you're still dealing with the World At Large and how do you like you're you
1:10:10
know science science doesn't happen on a vacuum and and neither does like the management and administration and
1:10:16
development of people in those careers or locations or the skills that's happened vacum either so that's that's
1:10:23
largely what it was you know um about and I look forward to to
1:10:30
developing um a lot of those things in in the next year really yeah yeah yeah
1:10:36
thanks for that uh so yeah it's interesting that mountains monasteries Metropolis model so that's something
1:10:42
that CRA hour developed uh and then they kind of adapting that to demo or do or something
1:10:50
like demo or correct yeah I I mean I I kind of just
1:10:56
I I offered a bunch of Frameworks it wasn't all like it wasn't everything through that lens it
1:11:03
was just I've been offered a bunch of a bunch of different lenses and I think I think it does fit I think there's a way
1:11:08
to think about under demo or die um but it's sort of a you know now monasteries
1:11:15
Metropolis is more of a broader level you know where are you in the idea generation process yeah um and it's it's
1:11:24
interesting to kind of um I don't know if KRA made it up or not but he certainly used it and he used
1:11:31
it a lot in talking about like ffi and what what the institute's doing and and
1:11:37
their you know their relative role is I talked a little bit about this in the talk too but like knowing what how what
1:11:43
kind of risk is your organization taking you know what is it is it monetary is it idea is it is it is it what what what
1:11:51
degree you know of each can they do and and why and like it's sort of relative to understanding what you can do in a
1:11:58
situation and what do you want to do um
1:12:03
what kind of risks are you open to taking at at the time that you're in as well
1:12:10
yeah yeah I think that's great and then you know this idea of demo or die it's interesting because in my project
1:12:17
management class I talk about the origins of demo or die so basically it comes out of the MIT media lab the idea
1:12:24
is to do this sort of practice where you put something into practice from an idea you build a
1:12:30
prototype or you show how something works and then to have that experiential learning where people can see the
1:12:37
details they can see how it works doesn't have to be something that's finished it can be just something it's like a prototype and then you keep doing
1:12:44
this over and over so the idea is that the demo becomes like this thing that
1:12:50
you can kind of work from so you do a demo you get feedback you do another Dem
1:12:55
you get feedback and then you kind of Polish everything out um I I did talk in
1:13:01
my graduate class now about um how sometimes you can create a demo just for
1:13:06
the sake of creating a demo like a lot of academic Labs will do this where
1:13:12
they'll have like two or three demos sometimes you'll see it a lot in like virtual reality or extended reality
1:13:18
where you know they'll like some company will build a demo and they'll say this
1:13:24
is a demo of how something works and they'll really get it polished and it's like this experiential thing and then
1:13:30
you know the demo though at that point just becomes like its own artifact it doesn't lead to any kind of uh progress
1:13:38
it's just kind of like I'm operating this thing under perfect conditions and
1:13:44
then you know it's it's sort of fragile to any sort of further development because you worked it out so well just
1:13:51
in that one area that you know might actually not be a very good say piece of
1:13:57
software but it works well just for the thing you're demoing and so what what what value is
1:14:03
that is that a experiential learning value is that like uh developing the
1:14:08
ideas value what is that and so you know kind of going over the different ways that you can do demo or die there's also
1:14:15
deployer die which is a little bit different um where you have to actually deploy something because the problem
1:14:21
with demos of course is that they can be you know uh selfcontained
1:14:26
and they don't really give you you know they don't really give you any sort you know they just show like this thing you want to show people it's almost like a
1:14:32
magic trick so yeah that's we should talk about that more I think definitely
1:14:38
and I think your your kind of approach of of kind connecting like Innovation with demo or die is really important
1:14:45
because that's why we do demos basically um we're doing it as part of a process
1:14:51
to develop things I mean we can do the the demos for demo sake but like you know that's
1:14:58
not necessarily as valuable so that's good um so why don't
1:15:04
we move on here and I think we had a good discussion about all this stuff and you
1:15:09
know this is like where I think we should revisit some of this I think the purposefully non-standard cybernetics we
1:15:15
need to kind of rethink like maybe how to get things out of that and maybe
1:15:21
create some papers out of it um or follow up on some things that were
1:15:26
mentioned and they weren't like you know really developed highly um but that's
1:15:32
what we do here um that's why we're doing this so I'm going to go over this article here this is
1:15:38
uh uh pet Holmes blog and of course he does a lot of good work uh with in terms
1:15:44
of complexity Theory and networks and all this and this article is uh it's
1:15:50
older well it's not older it's it's fairly new it's from October 24
1:15:55
um I was maybe think of one another article but so this is a fairly new article October of 24 surviving the
1:16:04
complexity winter I think that's a compelling title given some of the
1:16:09
discussions we've had about AI Summers and AI Winters and that historical
1:16:14
fluctuation so he's saying that I guess currently complexity and complexity
1:16:20
theory is in a winter and so I don't know you know how who wants to Define that but let's let's
1:16:27
find out so the top says complexity science in
1:16:32
2024 claiming to be what it's never been but gladly giving away its Nobel Prize
1:16:38
so the background here is that there was a Nobel Prize I think last year in physics uh that was related to some of
1:16:46
the foundational concepts of complexity and it's a physics it's a physics award but it's sort of for
1:16:54
complex it wasn't for complexity specifically but that's the way that at
1:16:59
least people were talking about it so this is interesting it sort of stresses
1:17:07
how complexity science is sort of at the Nexus of all these different areas and
1:17:13
so some of it is like you know that you when you get down to like the traditional disciplinary divides in
1:17:21
science and in Academia complexity science doesn't fit NE into any of them
1:17:26
so there might be some supporting materials you know people supporting ideas people
1:17:31
develop and in the world of evaluation people say well that's physics or you
1:17:37
know it could be that you know you develop a network technique for social networks and people say well that's
1:17:43
sociology but it's just as useful in maybe like uh biological networks or
1:17:49
physics as it is in sociology and just having that inner FL that flow that
1:17:54
inner change between Fields uh one of the problems with this of course is that
1:18:00
a lot of these things lose their coherent identity as a field so complexity science you know loses its
1:18:06
identity as a field when you have people in different fields kind of you know doing their
1:18:13
thing um so that's what he's talking about here and so this article is a
1:18:18
reflection where the science of complex systems stands today and where it should and could go next
1:18:25
so he says I'm as excited as everyone else at hopefield and Hinton got the Nobel Prize in physics so this is from
1:18:32
about this year's award um and and again this year's award was about machine learning neural
1:18:40
networks it you know but you think about the topics that are covered in hopefield and hinton's work it's like physics
1:18:47
cognitive science computer science and uh you know it's it's a physics a word
1:18:54
so you know that's kind of again subsuming some of those identities to physics
1:19:01
reducing it to physics the biological Foundation of computation has been part of many of the
1:19:06
holistic tribes and he uses the word holistic tribes and that is defined as the
1:19:13
disconnected scientific movements of the 20th century centered around systems
1:19:19
explaining systems by zooming out rather than zooming in so this is a this term
1:19:24
from holistic tribes he has a a blog post on that from February of 24 and
1:19:30
what that means is just like these groups that want to see things at the you know sort of the non-reductionist
1:19:37
scale thinking about how things are at the aggregate instead of in in terms of
1:19:44
the uh reduction so this is you know
1:19:49
kind of saying that it's not it doesn't really form a coherent field because it's just people adopting techniques
1:19:56
they could be in Neuroscience they could be in sociology could be in physics and you know they they there may be like a
1:20:03
complexity science but in terms of the questions that people are asking there
1:20:08
isn't really any coherence it's mostly in the methods so this is a problem in
1:20:13
science if you're asking questions you know that's kind of always
1:20:19
seen as like the core although sometimes in you know in like computer science and methods are pretty important but usually
1:20:25
the way that people Define field coherent Fields is in the questions they're asking so that's kind of what
1:20:32
he's getting here uh it would be entirely in order to uncork another bottle of Krug and party
1:20:37
W it's 2021 all over again this was the uh Nobel Prize where you know this was
1:20:45
awarded sort of for complex systems it was a physics Nobel and that was in 2021
1:20:51
so my mistake but that is a discussion of
1:20:56
that but oh no my complexity colleagues unanimously called this a prize to
1:21:02
Ai and join in the discussion of whether AI is physics or not so this is where
1:21:08
you know again uh is the hopefield and Hinton Nobel Prize is this like a prize
1:21:16
to AI where is it a prize to physics or is it even a prize to complexity I mean
1:21:22
it's just really depends on your perspective and he's talking about complexity theorist calling the
1:21:27
hopefield and Hinton prize a prize to AI instead of appreciating that it's a prize to a number of fields not just
1:21:36
physics the Nobel part of the story doesn't end there is the Nobel Foundation was kind enough to give AI
1:21:42
another round of Awards this time in chemistry so this is again the uh
1:21:48
the alpha fold award that was given we talked about that in the previous meeting and again this is another
1:21:54
example of How It's a chemistry award but there are all sorts of things involved in Alpha fold computer science
1:22:01
physics uh complexity Theory even and also chemistry so you have to give it in
1:22:06
some area and it's the point is is that it isn't just that area there are a
1:22:11
bunch of things that are being sort of brought to the FL and but people conceive of these things as different um
1:22:19
depending on who's looking at it and and giving the take on it this striking thing is that the
1:22:25
chemistry prize at least tabus and jumpers is a brilliant example of AI as not complexity science all prediction
1:22:32
all black box very cool and welld deserved but not complexity science per se so it has this aspect of complexity
1:22:40
but it's not complexity science as we Define it um currently and complexity
1:22:47
science then being driven by methods uh because you're talking about prediction
1:22:53
versus um other things blackbox versus defining the parts or defining the
1:22:59
phenomena so there there differences in the way it's approached um Ai and
1:23:05
complexity science overlap but one does not contain the other that's the important point so like you know some of
1:23:11
people were you know people were uninitiated in the methods of complexity science and maybe some of that is
1:23:18
because complexity science is really kind of a catch bag of questions and
1:23:24
methods mostly methods that are maybe similar to what you're trying to do in AI but
1:23:31
that's they're different you know different fields different things that you're trying to do
1:23:37
so it's interesting there I also caught the AI bug in many of my ongoing
1:23:43
projects try to find Nifty uses of large language models to ultimately learn about people I also have some admittedly
1:23:50
less interesting let's explore the capabilities of AI by letting them do something that we know uh how humans do
1:23:58
research so that's a long uh statement let's explore the capabilities of AI by
1:24:04
letting them do something that we know how humans do research so this is like kind of uh
1:24:11
basically we know what humans do in terms of behavior we get AI to replicate that behavior and then we look at the
1:24:17
capabilities of the AI to see what those involve but we don't actually make a
1:24:25
strong comparison with sort of the neural and cognitive capabilities of
1:24:30
humans when they do the same thing so and then of course even that is a an abstraction of what we think is going on
1:24:37
like you know we could use like um you know task learning in in like
1:24:44
psychological experiments versus a sort of naturalistic or continual learning that people usually engage in and the
1:24:50
same oldster for the AI that we compare it at sort of this artificial level of
1:24:55
capabilities and behaviors that's interesting um I would
1:25:01
never dream of calling that complexity science leaing through the abstracts of recent complex systems conferences I see
1:25:08
many such studies Co science but hardly complexity science so what he's saying is that basically complexity
1:25:14
science is being sort of um people are kind of moving in the
1:25:21
direction of kind of almost making it into AI research so like you know if
1:25:27
you're using methods you can use AI methods and apply them sort of nominally to sort of what
1:25:34
we might call complexity science but a lot of times it just kind of veers into just Ai and so it's kind
1:25:41
of keeping complexity science um you know away from its true
1:25:48
potential another sign of the times is that many of the core ideas of complexity science in the 1990s
1:25:55
have been absorbed back into the traditional academic disciplines so this is like you know Network Theory or some
1:26:01
of the statistical analyses uh you know used to be that like these were new
1:26:08
ideas oh I can analyze something using a network or oh I can analyze like a power
1:26:13
law on something or I can look at like dynamical systems isn't that interesting
1:26:19
and it's a different thing from what what's happening in a field so like a neuroscience you at the time there was
1:26:25
no real great I mean there was some discussion of but it no great pillar of
1:26:31
Neuroscience was you know dynamical systems theory and so people kind of
1:26:37
developed that on their own and it was considered complexity science or an instance of complexity science now as
1:26:43
it's become more accepted it's kind of going back in the direction of Neuroscience and people think of that work well that's Neuroscience not
1:26:51
complexity so it's sort of a you know kind of a classification problem but
1:26:57
also like who are you interacting with back then if you wanted to use dynamical
1:27:03
systems approaches you'd have to kind of go to a physics department or go to a
1:27:09
dynamical you know systems group or go to a complexity group and you wouldn't
1:27:14
talk to neuroscientists so much but then now as it's become more common it all
1:27:20
can all be subsumed in Neuroscience you can have conversations with other dynamical neuroscientists and it's part
1:27:26
of that field um I recently chatted with the
1:27:31
management scholar who pointed out how ideas from complexity science that is systems performing optimally at the edge
1:27:38
of chaos have been integrated textbook IED and gentrified to the point nobody
1:27:45
sees a need to look to complexity science for new ideas so it's basically these ideas have been Incorporated but
1:27:50
also in ways that are sort of maybe not as pure as we had them in the 90s in
1:27:57
complexity science so they've been kind of modified for their home field it
1:28:02
maybe sometimes to their detriment but it's not something that people are looking to complexity science for they
1:28:08
have the tools inhouse in their own discipline so why go outside the discipline to work with and of course
1:28:15
that's a problem because complexity science could be very fertile for a whole host of new approaches but people
1:28:22
aren't you know people are not necessarily looking always to complexity science for that Cutting
1:28:30
Edge further evidence of how systems related topics have partly fallen out of fashion and partly merged with other
1:28:37
fields of knowledge is their fading presence in the public political discourse
1:28:43
so we have want to find out about this we go back to sort of the mid-century the 20th century where we had you know
1:28:51
cybernetics and we had cybernetics applied to public policy and we had like
1:28:56
Herbert Simon and his sort of technocratic ideas applied to um public
1:29:02
policy and then you know we had system psychology we had things like limits to growth where we had system science and
1:29:10
government system science and policy and people were thinking about things in terms of systems so there was this whole
1:29:17
fat of like systemate type things like the institute for future studies and you know these other
1:29:25
institutions and topics that kind of fell by the wayside partially as people
1:29:31
started thinking about systems in their own Fields partially because maybe some of the shortcomings of systems
1:29:37
approaches and partially because it was kind of you know fattish in the sense that people always look for fads look
1:29:44
for new types of approaches and then when they don't deliver like you know everything they had hoped they kind of
1:29:51
abandon them and move on and which is unfort forunate because of course we know about the hype cycles and how
1:29:58
everything can reach a like a peak and then there these deflated expectations and then there's this plateau of
1:30:05
productivity so we're kind of at the plateau of productivity for the systems approaches so that's kind of the problem
1:30:12
that I I think uh complexity scien has paid the price for that this is not the end however just
1:30:19
like the famous AI winters of the past this complexity winter will give way to another spring the reason I'm fairly
1:30:25
sure of this is that the desire to understand a fundamental human trait which is nothing seems to be more
1:30:32
prominent about human life than it's wanting to understand all and put everything together and this is uh
1:30:39
attributed to Buckminster Fuller who articulated it in the book operating manual for spaceship
1:30:46
earth ultimately we can't do that without the most fundamental and radical of complexity science
1:30:52
ideas so this is basically the idea and this is from a better way of thinking
1:30:58
about emergence which we talked about in a previous meeting but this is the the
1:31:03
sort of the idea that causality is not the atom of scientific
1:31:09
explanation but rather we need explanation in the form of models systems diagrams systems thinking Etc
1:31:17
feedback loops included so we need to kind of not think
1:31:22
just about causality in the conventional sense we can't think about a causes B
1:31:28
causes C we need to think in terms of more sophisticated models and feedback
1:31:34
loops and retrocausality and uh loopiness like
1:31:40
loopy basy and approaches or you know any like there are a whole bunch actually in purposely non-standard
1:31:47
cybernetics we kind of get into some of that uh like retrocausality that results from having
1:31:53
a feedback loop so you have the present then you have the past and then you have the
1:31:58
future I can dve around that out just really quick because we do talk about it in the talk I want to maybe go over that
1:32:05
a little
1:32:13
bit okay so let me go over this a little bit so basically the idea is that you
1:32:19
have conventional causality which would be a to
1:32:24
b c and you know this is like causes you know so you know we have to do some more
1:32:32
formal tests for causality we have to do like interventions and things like that to test and and doing counterfactuals
1:32:39
and things like that basically that's the idea a causes B causes C now in a
1:32:45
feedback loop you don't have that necessarily you might have a to
1:32:51
B to B Prime and then down to C and then this
1:32:58
kind of goes like this so in this case you have something like the
1:33:04
present A to B there's a transfer you know in the present from A to B then you
1:33:10
have a feedback which is the past so it's self- referential or referential so B Prime is the past and then that could
1:33:17
it's combined here with a feed forward present just as we have made to be but
1:33:24
now you're adding in the past which then gives you both the present and the past but now it's as an
1:33:32
output it's the future because You' done something to the present to modify
1:33:38
it so this is something I we're developing in the talk uh where you have
1:33:44
these kind of past present future relations and you know rather you know it's not really a word salad because you
1:33:50
can actually do some really interesting things here um where you have like B Prime and then
1:33:58
you have another feedback which is like B prime prime and then you can go up
1:34:03
here and have like you know your information coming from maybe another
1:34:10
source which might be c and d and then that gives us an alternate future e and
1:34:16
then we might have another future out here uh
1:34:21
F where we have this Motif from here we end up with these alternate
1:34:28
Futures and the reason they're alternate Futures is because they involve
1:34:33
different levels of self- reference and different levels of referencing the past
1:34:39
so here we have the present here we have the past here we
1:34:44
have a deeper past and then we have another alternate
1:34:50
present and then we have now a future in a future so you can see that that's
1:34:56
how that would work so you can have these different types of uh you know
1:35:01
even with like basic causality and putting it into like a system like a cybernetic system you can get all sorts
1:35:08
of complex behaviors that you wouldn't otherwise have um and then of course there are
1:35:14
other things like in systems diagrams you have loops you have feedbacks you
1:35:19
have uh you know a lot of you know a lot of contributions to certain thing so
1:35:24
even if we do understand that you know basically a causes B you have other
1:35:30
inputs that don't AOW you to say make a definitive statement about what causes
1:35:35
what so again if we have um you know something
1:35:42
like go
1:35:48
here so if we have something like a c b
1:35:53
we might have another a a prime also causing b or a prime prime causing B so
1:36:01
each of these are kind of an alternate form of a and they're all acting on B so then we have to decide okay what is if a
1:36:09
is the main causal Factor then what is the role of these other factors so this might be secondary
1:36:16
causal this might be tertiary CA so it's not as easy now to say that
1:36:23
causes B because there are these other things pulling and that leads you to
1:36:29
C which indeed might have other things that kind of play on C like B Prime and
1:36:34
B prime prime and this is of course where you can use things like interventions to you
1:36:41
know determine whether which which causal factor is the strongest but you know it's like when you do something
1:36:46
like a PCA you have you know components that contribute a certain amount of the
1:36:52
variation to the problem you're looking at so even then when you have these causal chains you can have multiple
1:36:58
inputs that kind of Tamp down the predictability of the system so that's
1:37:05
kind of my thinking on that um so this is all stuff that we never really
1:37:11
resolved in the earlier sort of saturation of systems thinking we kind
1:37:17
of dealt with a lot of systems diagrams and building models of feedback and
1:37:23
models of sort of holistic representations but there are a lot of
1:37:29
questions that were never answered that we you know that we can kind of come back to and kind of figure out and and
1:37:36
get more deeply into and I think actually the markup link it's idea is interesting because in traditional
1:37:42
systems approaches the boundary of the system is very important but it was very hard to Define and so now markco blanket
1:37:49
kind of served that purpose but again we need more innovation in thinking about some of these old systems approaches
1:37:56
this says we need innovation in thinking about classic cybernetic St so for a moment we might be
1:38:03
infatuated by causal inference and blackbox prediction which is sort of the currency of M machine learning and you
1:38:11
know having like these black boxes that generate stuff and not really understanding the mechanisms but under
1:38:17
word the systems underlying them but just understanding the
1:38:22
output so we can do that all day but that Crush will not last forever and for
1:38:28
the record I'm not a prediction is not understanding me or almost the opposite which I should at least write a blog
1:38:34
post about so yeah some people say that prediction is not understanding which is true but I think you know sometimes it
1:38:40
is um but it's not deep understanding so you know I I I leave that to you
1:38:46
especially Jesse likes to think about things like this to end on a high note I just finished teaching complex systems
1:38:52
for the first time in 10 years and I can tell many students really like the material instead of following the
1:38:58
prototypical syllabus essentially a storyline and an accompanying skill set
1:39:03
that were already in place in Herman haken's 1981 synergetics so we've kind of covered the sort of the history of
1:39:14
um you know we I did a presentation in cognition Futures a long time
1:39:19
ago um on sort of complexity uh science in ecological
1:39:27
psychology and we talked about uh J kelo's work on um
1:39:35
synergetics in motor control and one of the things that he did was he went to visit Herman hen back
1:39:42
in the 80s and they had a long collaboration so Herman haken's ideas were physics and they explained a lot of
1:39:49
things in physics and then JS Kelo took those ideas and ported them
1:39:55
to uh perceptual science to ecological psychology and so now those ideas are
1:40:01
sort of part of the dynamical systems view Neuroscience but they started out in
1:40:07
physics so you know we have these kind of tools that kind of follow different trajectories throughout intellectual
1:40:14
history but they're kind of you know they're all part of complexity through um and then so you can have a class
1:40:21
where you kind of go through uh that history but in this
1:40:26
case uh uh pet F focused only on the zoo of ideas and Frameworks and there
1:40:33
different takes on the pillars of complexity science bism emergence
1:40:38
Etc so yeah there are all sorts of Frameworks out there maybe that's part of the problem is that there's so many
1:40:44
competing Frameworks there's synergetics there's you know dynamical systems there's
1:40:50
control theory there's you know there are a lot of different approaches that one can take and they're all different
1:40:56
they're all basically trying to do the same things more or less but they all have different tool boxes where they
1:41:02
might have slightly different tools uh and you know that's one of the problems maybe is that it's like a lot
1:41:10
of these complexity approaches have devolved into foms where it's about tool building and
1:41:16
about methological uh you know particularities rather than keeping to
1:41:24
the main ideas the main questions and not asking questions in specific Fields
1:41:29
but asking more fundamental questions about the world so it's interesting that
1:41:35
that's a good way to think about this um those ideas will never die or at least never not be reborn so this is another
1:41:42
Ln to the holistic tribes article uh the complexity science we have today could maybe die though by presenting itself as
1:41:50
something popular that isn't and then being swallowed by that twetter something which is I guess AI or ml or
1:42:03
whatever okay um any questions on that I know Jesse mentioned this in her admin
1:42:09
meeting uh last week and he asked about the submissions and aspirations document
1:42:15
that we had working on a long time ago and I actually got it out of the I found
1:42:20
it on the Google Drive for the lab and um it's it's interesting I don't know if
1:42:26
we want to start using any let me go back to it actually let me go to the
1:42:33
okay okay so let me share my screen and I'll go back to this so this is the old submissions and
1:42:41
aspirations document and we had 2021 we had a lot of stuff going on
1:42:47
there a lot of virtual conferences and things and as those dwindled you know we
1:42:54
kind of did a lot of stuff in 22 then 23 I kind of dwindled and then 24 we never
1:43:01
actually provided a stub for that so we have 21 22 23 then a programs and
1:43:07
training document that I don't know if Jesse is still aware of this is like
1:43:12
kind of talking about different doctoral programs I think this is a good resource
1:43:17
for interns and students uh maybe it comes out of here and goes into its own
1:43:25
document and then this is a PIV Associated pivot table so this is really I think based on Jess's Explorations but
1:43:33
people can use this if they want but my question is you know we should maybe create a 2024 version of
1:43:40
this and review it um we've gotten away from it for a while obviously but I
1:43:46
don't know if that's something that's of use um like I probably start with 2025
1:43:52
since 20 24 is almost over but I just wanted to revisit that
1:43:57
to make sure that we knew about it and were aware of
1:44:08
it sorry I didn't hear if there's a question at the end oh well I mean just I was showing what we have in terms of
1:44:14
that document is that something that might still be useful or should we rethink that document yeah I mean I
1:44:19
think we should think about like the end of the year like we should think about we're trying to Target for next year for
1:44:25
sure um I haven't prepared anything else yet
1:44:31
um but I think looking at you know opport like my ver my the version of it
1:44:37
that I'd like to see is sort of yes events things to submit to like the actual
1:44:43
calls and then perhaps um it could all be in
1:44:49
one sheet or one database it be notion would be very good for this I haven't
1:44:54
um I could put something there I have my own I've shifted my own stuff away other
1:45:00
spaces since a little bit I'm not in that space like that in
1:45:07
that database as much as I could be I suppose uh but it's sort of like I don't
1:45:13
know like
1:45:18
um it's it's a little bit of you know uh
1:45:24
chicken of the egg or cart before the horse about it like like I'm happy to do it I don't know if anybody really is
1:45:29
going to care about it Beyond me but like I'm happy to do it I'm happy to look like have a setion about grants and
1:45:36
funding and opportunities which I've been applying to a bit more lately and
1:45:41
like that so I mean I don't I don't really know what other people what other people would find Value in but I will be doing things in those spaces for sure I
1:45:48
think that set of resources you have on graduate stuff is good and you know but think maybe it comes into a different
1:45:54
set of like different place to to store it so we can access it um yeah I mean I'm
1:46:02
I'm like the list of programs I'm sure is I don't even know if that's really up to date anymore so it's I haven't
1:46:08
touched that in several years so people have done this with like neuro rumbler and things where they have like
1:46:15
up-to-date information and it's croud sourced and it's still out of date so but you know it's um I don't I don't
1:46:23
know I don't know if it's worth the time to invest in it that's what I'm saying but but still it's something for
1:46:29
students if they if they want to get a sense of you know what's out there um you know and then I don't know
1:46:36
what our opportunities are for 2025 we need to kind of go over those too like kind of make a list of things um but I
1:46:43
don't want to do that right now I want to do that offline um so we can move on but just as
1:46:51
a reminder
1:46:58
okay anything else Jesse before we move on no um I'm gonna have to leave in a
1:47:04
little bit also um but I some sometime
1:47:12
um I I I think I don't know if in slack would be best for this or somewhere else
1:47:19
but like actual um I think having some administrative
1:47:25
discussion about like actual targets I think I think it be good to talk a bit more about next year
1:47:31
soon uh because I have the opportunities to put out some intership things again
1:47:36
uh I have to follow up I have follow up the alany and San Diego and some other
1:47:44
um things here in Boston too so I'd like
1:47:49
to um and maybe that's maybe that's just something for me to spearhead I don't I
1:47:56
don't know if there's any other thoughts about it but like you know maybe a Friday yeah would be a good Friday
1:48:02
meeting for something like that talking basically about next year and like doing the
1:48:08
administrative you if my if my talk earlier was this more lofty uh discussion about you know organizing and
1:48:14
setting things up and and navigating through space this is the nuts and bolts gritty and just dates
1:48:24
and numbers and and charting charting the course for the road to be paved which is be less fun
1:48:32
but it equally is important so I'm I'm happy to do that yes this is where we throw all the high-minded theory out the
1:48:39
window and just kind of go with the practice okay so that's good yeah I'm
1:48:45
looking forward to that um thank you so let me get ready for this next segment
1:48:51
uh let's see
1:48:58
I'll do this one so
1:49:05
uh yeah so I think there's like you know some interesting stuff in the complexity
1:49:12
science article and in a lot of the active stuff that was discussed this
1:49:17
week it's you know it's very limited well it's not very limited but it's very much
1:49:23
part of that uh sort of in the surface of active influence especially applications of
1:49:29
active influence uh what we're going to do now is talk about some U Neuroscience related things um and this is a set of
1:49:38
things that are these projections inations and actions so we're talking about like action or
1:49:44
active stuff in the brain in the mind and we're talking about some of the
1:49:50
neuroanatomy and some of the systems that contribute to that so let me start here I think so this is
1:50:00
um you know this is going to be a collection of things that are kind of all over the place but you'll see the
1:50:05
connections as we go along so this is an article from uh
1:50:10
regenerative medicine it's a nature uh journal and it's a review article called
1:50:19
innov ination The Missing Link for biofar replicated tissues and
1:50:24
organs so this is where you know we talk about if we create tissues in organs say
1:50:31
in a uh an organoid or something like that or we create an artificial organ on
1:50:38
its own you know we can create this thing in a lab in a in a culture
1:50:43
environment but how do we integrate it with the body because that's ultimately
1:50:49
the goal for a lot of this stuff sometimes it's for like studying medical
1:50:54
research but sometimes it's for actually putting them in the body so and of course we have to think about
1:51:00
development so in development we have cells that differentiate they form tissues they form connections with other
1:51:07
parts of the body critically and then they operate so the the the
1:51:13
organizational scheme is very different than if you took something Brew it in a culture and then put it into the body
1:51:20
you know you have to have those connections there and that's one of the barriers actually of a lot of uh
1:51:25
bioengineering is that you know integrating things into the surrounding tissue integrating things into the
1:51:32
connectivity of the body connectivity of the nervous system sometimes is always a
1:51:37
problem and so people have tried various strategies to do this so what they're arguing is that for biofabricated
1:51:44
tissues and organs we need innervation and intervation is basically where the nervous system interat nerves into the
1:51:53
the organs so like if you have something like um you know like we talked about
1:51:59
the vagal nervous system there are all sorts of innovation or inovation going on there nerves innervating different
1:52:06
tissues like the gut and the digestive system and other places and those nerves
1:52:13
actually serve a critical role in sensing things inside the body and and
1:52:19
getting information to the brain for a h host of autonomic functions so that's
1:52:25
why it's important and yet at the same time you know you can't really have like
1:52:30
you can't put in a stomach without having it interated properly and so
1:52:36
that's a problem for these kind of explants or implants okay so uh the abstract reads
1:52:45
interation plays a pivotal role as a driver of tissue organ development as
1:52:50
well as a means for their functional control and mod ulation so again we need to have interation of the nervous system
1:52:58
to mod you know modulate these kind of autonomic behaviors that we
1:53:04
expect therefore intervation must be carefully considered throughout the process of biofabrication of engineered
1:53:10
tissues and organs unfortunately inovation has generally been overlooked
1:53:15
in most non neuronal tissue engineering applications so unless we're talking about something specific like the spinal
1:53:21
cord like if we want to reconnect the spinal cord where there might be an
1:53:26
injury you know you can usually build a little you know a a splint where you
1:53:34
have growth factors that allow for exogenesis and we understand maybe kind
1:53:39
of how to do that but that's really the extent of how we've done this um and so
1:53:48
uh in part due to the intrinsic complexity building organs can ining heterogen heterogeneous native cell
1:53:55
types and structures so a lot of times we'll build organs and they'll be very much like the main cell types and there
1:54:01
may be other cell types that occur maybe partially as a result of
1:54:07
interation sometimes as a consequence of innovation Innovation um and so this is something
1:54:14
we don't have as well to achieve proper inovation of engineered tissues and organs specific host axon populations
1:54:22
typically need to be precisely driven to appropriate locations within the construct often over long distances so
1:54:29
you need to facilitate the ax onog Genesis and that the ways in which you do it are going to depend you know you
1:54:36
have to design specifically for that as such neural tissue engineering
1:54:42
and or axon guidance strategies should be a necessary adjunct to most organogenesis Endeavors across multiple
1:54:49
tissue and organ systems to address this challenge our team is actively building
1:54:55
axon based living scaffolds that may physically wire in during organ development so this is you
1:55:01
know kind of what they're doing say in the uh spinal cord they have some scaffold where they have growth factors
1:55:09
they have the conditions for that encourage ex onog Genesis uh and maybe some guidance cues
1:55:16
uh you know so that they can don't you know connect to the wrong places so this
1:55:22
this is a you know really complex problem because we don't first of all we really have maybe a tenuous
1:55:30
understanding of how these wiring you know how this wiring works and what
1:55:35
constitutes the right connections but also just kind of building these scaffolds where you leave it up to the
1:55:41
axons to do their thing you know that's it's just kind of a hard thing to really
1:55:47
kind of get to work so we're able to do this maybe to physically WI
1:55:53
uh axonal Connections in organ development at bioreactors and Reserve as a substrate
1:55:59
to effectively dve targeted long-distance growth and integration of host axons after implantation so you
1:56:06
could do it both in culture and after implantation this article reviews the
1:56:13
neuroanatomy and the role of in inovation in the functional regulation of cardiac skeletal and smooth muscle
1:56:19
tissue and highlights potential strategy to promote inovation of biofabricated
1:56:25
engineered muscles as well as the use of living scaffolds in this endeavor for
1:56:30
both inv vitro and invivo applications we assert that inovation
1:56:35
should be included as a necessary component for tissue of organ biofabrication and that strategies to
1:56:42
orchestrate hostal integration or advantages to ensure proper function
1:56:48
tolerance assimilation and bioregulation within the recipient post implant so
1:56:54
this is a paper from 2020 so this is just a review of kind of the work that's been
1:57:00
done this is an example kind of what they're talking about you have an organ
1:57:06
on the left cardiac muscle different types of smooth muscle skeletal muscle
1:57:12
and then so they're just working with muscle and then they talk about the development and how those projections
1:57:19
occur on the development so in cardiac muscle you have timing of innervation
1:57:24
which regulates Ault heart size so the actual size of the heart is regulated by nervous system
1:57:30
inovation in smooth muscle you get innervation of bladder walls it starts early during
1:57:37
organogenesis and in gastrointestinal tracts common signaling Pathways regulating inter inic nervous system and
1:57:44
gut development so a lot of things are regulated by these connections and then
1:57:50
skeletal muscles we have neurotrophy that are needed for development we also get synaps
1:57:56
elimination so even when you you know you're talking about any type of muscle different types of muscle we have these
1:58:02
different types of connectivity that are essential for development but we have to recognize you know exactly what they are
1:58:10
then we have functional regulations so there are all sorts of Regulation uh in cardiac muscle these interations
1:58:16
regulate or modulate heart rate and contraction force and smooth muscle we
1:58:22
get regulation of Transit muscle contraction absorption secretion and immune function and then in uh Alpha
1:58:31
motor neurons they regulate the opening of things like the sphincter or sphincters in the uh gut system and then
1:58:39
bladder well contraction and relaxation uh and then of course in skeletal muscle we have muscle
1:58:45
contraction and neuromuscular Junction so a lot of functional aspects uh of
1:58:51
interplay with the central nervous system and the peripheral nervous system and in terms of tissue
1:58:57
engineering then we can see how we can build these different scaffolds we have injectable hydrogels uh different types
1:59:04
of scaffolds perfusion and mechanical stimulation we have um intestinal
1:59:10
organoids we have reconstruction of the bladder wall where we can use cellular
1:59:16
scaffolds um and then we have in the skeletal muscle we have injection of
1:59:21
motor neurons and surgical embedding with nerves so there are all sorts of techniques that we can use as well so this is a diagram
1:59:28
of sort of what we have we have the central nervous system here then we have the peripheral nervous system out here
1:59:34
we have different organs like the heart the gastro intestinal tract the bladder
1:59:40
and skeletal muscle we have the sympathetic chain along chains along the side which kind of go along the spinal
1:59:48
cord and there's communication between the sympathetic chain and the organs so the sympathetic
1:59:54
nervous system is you know communicating with this peripheral aspect of the nervous system going into the central
2:00:01
nervous system and getting processed there's local processing in the peripheral nervous system as well but
2:00:07
this all depends on how these organs are innervated and the connections that are made between organs and the nervous
2:00:15
system itself so you can see that the legend down here they're different connect different types of connections
2:00:22
preganglionic and postganglionic sympathetic preganglionic and postganglionic parasympathetic and
2:00:28
somatic motor neurons so that's the system and you know this is just kind of going over some of the approaches that
2:00:35
have been used and some of the trends in the future so the second paper is the
2:00:43
laminer pattern of propri acceptive activation in human primary motor cortex
2:00:48
and this is kind of talking about uh now propri ception and how this is activated
2:00:54
and this laminer pattern in primary motor cortex so this is a bioarchive
2:01:00
pre-print uh from last year but I don't know if it's been published yet but anyways um the abstract reads the
2:01:07
primary motor cortex or M1 has traditionally been viewed as a motor output generator however it's vital role
2:01:14
impropriate receptive catic sensation which means you're taking in signals from the body from the periphery from
2:01:20
the hands the feet the skin of different types and then even inter internal uh
2:01:26
systems to some extent we have this propr reception where we have this map of the body and how the nerves inate the
2:01:34
surface of the body and other things so we have like Maps uh if you've ever seen
2:01:39
the homunculus where you have like you know a very large face with big lips
2:01:45
it's like looks like a human but it's like scaled to the number of connections that um exist the dens of connections
2:01:52
that exist in different tissues so you have like huge lips a huge face and then
2:01:57
a a large head large hands large feet and then rest of the body is very small
2:02:03
and the genitalia are expanded as well and that's just a map of like you know how dense innervation is in those
2:02:10
different areas those different tissues and then that's all represented in the
2:02:16
M1 area in terms of a somata sensory map so you get this kind of input um and
2:02:24
it's processed and you get this interaction water cortex so yet our understanding appropri
2:02:31
recept of seata sensation in M1 at the laminer scale is limited largely due to
2:02:36
methodological challenges empirical findings in primates and rodents suggest
2:02:41
a pronounced role of superficial cortical layers so this is studies in both prates and rodents so this is a
2:02:48
Maman brain so we have these superficial Cor cortical layers but the involvement
2:02:53
of deep layers is yet to be examined in humans so The Superficial cortical layers are the ones on the top the Deep
2:03:00
layers are the ones on the bottom so this is different layers of processing in cortex where you have the six layers
2:03:06
and you have these relays that go down layer by layer and the different layers do different types of processing so
2:03:13
they're really kind of familiar with sort of The Superficial cortical layers and how those contribute to these seata
2:03:20
sensory maps and and how to integrate propri reception but the Deep layers are not as well
2:03:27
understood so they're using submillimeter resolution fmri for this study or at least they're talking about
2:03:34
the method uh Paving the way for the study of layer dependent activity in humans what they call laminer fmri so
2:03:41
fmri is sort of hampered by its resolution among other things but the
2:03:47
resolution doesn't necessarily allow you to because you get these oxal that are
2:03:53
you know a couple millimet cubed and so that doesn't allow you that allows you to look at different brain regions but
2:03:59
not the layers of Cortex so you need submillimeter resolution fmri for that to look at the layer by layer
2:04:06
interactions so this is what they're talking about when they talk about lamin or fmri in the present study lamin or fmri
2:04:13
was employed to investigate the laminer pattern appropriate receptive CA sensation on M1 deep layer activation
2:04:22
using passive finger movements as perceptive stimulation so this is where you have
2:04:27
this finger movement Paradigm looking at samata sensation looking at how it's
2:04:32
integrated in M1 then looking at these deep layers significant M1 deep layer
2:04:38
activation was observed in response to proprioceptive stimulation across 10 healthy subjects using vascular space
2:04:46
oceny or Vaso at seven Tesla for further validation two additional subjects were
2:04:53
scanned using a balanced steady state three procession sequence with ultra high in plane resolution so these are
2:04:59
all neuroimaging um technical points uh the point is here is that they did you
2:05:05
know some validation steps they used a high resolution scanner and they were able to observe this over 10 healthy
2:05:11
subjects which in fmri is you know a decent sample size um so these results
2:05:18
were interpreted in the white of previous laminer FM studies in the active inference account of motor
2:05:24
control so they're bringing in active inference here um we suggest that a considerable proportion of M1 deep layer
2:05:31
activation is due to propriate receptive influence that deep layers of M1
2:05:37
constitute a key component in propri receptive circuits so this is important U so we
2:05:43
get this intervation of of the this the body of the you know the skin and the
2:05:51
organ you know the the parts of the body that are exposed to the world we there are different degrees of interation
2:05:58
there that LE this density map that's in the upper layers of M1 then those
2:06:04
interations are uh further processed in terms of active in you know it's
2:06:10
consistent with active inference or the Deep layers of M1 okay let's go down to the
2:06:16
discussion so they talk about their study they talk about passive movements activated both superficial and deep
2:06:23
layers of M1 that's good um and then you know to our knowledge M1 activation and
2:06:29
response to proi receptive stimulation has not been studied at the human human laminer level previously but consistent
2:06:36
with our findings numerous Studies have established strong M1 involvement in relation to propri receptive perception
2:06:43
so for example propri receptive Sensations can be induced by tendon vibration which elicits an illusion that
2:06:49
the corresponding limb is moving so you can actually move tend vibrate
2:06:54
tendons and the limb which those tendons are on give you know there's this
2:06:59
illusion there there these proprioceptive illusions that you can elicit by doing things like tendon
2:07:05
vibration and so this means that you know there's a you know it's it's basically activating those inations
2:07:11
along the tendon and it's showing up in the brain uh M1 has been shown to be the
2:07:18
most strongly activated area during such illusions despite the fact subjects did not actually move the liim nor intend to
2:07:25
do so so this is an interesting point because there's a lot of literature on
2:07:30
um you know motor planning and motor preparation and you know you can measure
2:07:36
erps that kind of precede movement of Limbs what's interesting here is that
2:07:41
you can actually have activations that are decoupled from movement but also
2:07:47
intention to movement and that's interesting um because you know that's
2:07:52
something that we have a number of motor Illusions we think about visual Illusions all the time but there are number of motor illusions that actually
2:07:59
speak to this sort of you know what's going on when we move our bodies is it
2:08:05
intentional is it are there unintentional components is there like this you know map that is immutable can
2:08:14
we you know introduce illusions at different levels of the nervous system
2:08:19
you know we can do all these kind of interesting things activation was only found when the
2:08:25
tendon was vibrated at frequencies that did not elicit the illusion thereby excluding tactile inflence you can
2:08:32
actually exclude tactile inference so they they get down to this last statement um and they say thus deep
2:08:39
output layers may be actively involved in shaping propr receptive Sensations as
2:08:44
opposed to merely using it to guide output so this is where these deep output layers actually shape a lot of
2:08:51
these prop receptive Sensations from the inovation of the tissue and instead of
2:08:56
just guiding output so that's interesting in view of the increasing prominence of hierarchical basian
2:09:02
theories of brain function and their inherently link to lamin or circuitry we propose an alternative interpretation of
2:09:09
the observed deep layer signal this is based on the active inference framework which
2:09:15
friston which is particularly relevant to the sensory motor system according to the canonical micro
2:09:21
circuit underlying active inference proceptive stimulation should strongly
2:09:26
activate superficial layers of M1 which are the ones on the top since neuronal units at this depth are the targets of
2:09:33
driving feed forward per receptor prediction errors so when you have this
2:09:39
sort of your matching actual prop receptor prop reception with the model
2:09:44
that should be there you get these prediction errors and so you're getting
2:09:49
some sort of error correction eventually so that's where you're creating these errors or driving these feed forward
2:09:55
errors so these feed forward errors continuously update expectations about
2:10:00
the current propr receptive state so you're basically comparing your model with the state of the world and you're
2:10:08
kind of predicting errors which then are you know the system updates and fills in
2:10:13
the gaps the potent superficial to deep inter colomar pathway invad these
2:10:19
expectations on a deep layer ition units which is accompanied by feedback connections from premotor cortex so now
2:10:26
we're involving preo cortex into this and we're getting more information uh and we're correcting
2:10:32
those movements the Deep layer units integrate extensive synaptic input which
2:10:37
in itself may give rise to deep layer fmri signals furthermore on the basis of this input perceptive predictions are
2:10:45
generated and transmitted to S1 enamic zat sensory nuclei to inform prop
2:10:51
receptor perceptions so this is the perceptual influence component of active influence so basically what's happening
2:10:58
is we have our model in um S1 and then we have uh
2:11:04
feedbacks we have these uh different types of uh
2:11:09
signals that uh you know allow us to have these feedforward and feedback signals and those feedbacks actually we
2:11:17
start with okay so we start in M1 in The Superficial layers and there's some sort
2:11:23
of prediction there with error and we go to the Deep layers where that prediction is corrected in some way and then we
2:11:31
involve S1 enamic sematic sensory nuclei so there's a loop coming from other
2:11:36
parts of the brain parts of the brain that are taking in those interations before they reach
2:11:42
M1 and they're being integrated into these feedback loops which then allow us to do perceptual
2:11:49
inference so that's the way they kind of uh sell this within this framework portical spinal outputs uh constitutes
2:11:56
these same proppr receptive predictions directed to lower motor neurons in the spinal cord the distinction between
2:12:03
motor output and per reception thus becomes meaningless as motor output appropriate reception or two sides of or
2:12:09
motor output appropriate reception are two sides of the same Co so this is
2:12:15
really interesting um and going to talk more about the active inference
2:12:20
interpretation so let's move on to the last paper I want to get to that before we go this is
2:12:27
um I guess this is a preprint pending peer review this is uh I don't think
2:12:32
this is posted on the bioarchive but this is something I and I ran across well putting this
2:12:38
together this is visceral effort training and action the origins of agency and early cognitive development
2:12:45
this is Andrew Corker and and uh co-authors the abstract reads the feto
2:12:51
period constitutes a critical stage in the construction and organization of a malean nervous system so this is of
2:12:58
course we know this there's these critical stages of uh you know construction of these afferences
2:13:03
construction of these inovations and you know how the nervous system is constructed and how it gets
2:13:09
its information and adult in recent work we proposed that fetal brain development
2:13:14
is supported by bottomup or inter interceptive inputs from spontaneous physiological rhythms such as the
2:13:21
heartbeat so this is something where you have these um you know how do you kind
2:13:28
of connect these things in development and it turns out that brain development is actually supported in part by other
2:13:36
parts of the body so you get things like physiological rhythms in other parts of
2:13:41
the embryo like heartbeat and things like that and it kind of feeds back to the brain and it furthers development of
2:13:47
the brain so there are a lot of the shorthand erasa there's a lot of connectedness in uh later fetal
2:13:55
development and so this is where we get this um you know we can have these
2:14:00
connections we don't have these connections we may have problems so here we expand this visceral afer training
2:14:07
hypothesis to incorporate the development of top- down or alistic control over body States so they're
2:14:14
introducing allostasis here is this top down control over body States and this is this visceral afer training
2:14:20
hypothesis so this is where bodily states are controlled by these top- down
2:14:26
signals we propose that the brain's capacity to actively modify and regulate the AF feedback it receives through
2:14:33
inter receptive and other sensory channels is crucial for establishing basic forms of agentic control and
2:14:40
grounding the distinction between self and the other so this is really during the later part of fetal development the
2:14:47
really early part of like babies are born and they're kind of
2:14:52
doing this they're kind of figuring out uh the relationship between their s and
2:14:58
other things in the world so this is basic to the formulation of a gtic
2:15:03
control uh so we further suggest that individual differences in the way these training regimes are implemented or
2:15:09
disrupted might impact developmental trajectories in gestation and infancy including the potentiation of neural
2:15:16
behavioral impairment and disease risk later in life this analysis raises the
2:15:21
important question of whether the delarius effects a prenal adversity such as premature birth can be mitigated via
2:15:28
targeted visceral AFR training interventions so these visceral afference are really important for
2:15:34
regulating the entire fetus the entire baby as it's as it's developing the you
2:15:43
know there's this top down elatic control so we know about allostatic control and it just basically helps
2:15:50
these bodily States kind of form and become a thing so this is also I think
2:15:55
maybe important for developmental Ai and that you have these connections that are
2:16:01
not only kind of you we think of Connections in terms of a neural network is being weights but maybe they're more
2:16:07
than weights maybe they're kind of like you know permissive versus restrictive
2:16:12
and so if they're there versus not there we're in a certain configuration versus in a different configuration it can have
2:16:18
large scale effects on the outcome of development okay so yeah Jesse had to go
2:16:25
thank you Jesse and so that's all I have for that I don't know if Morgan had anything to say about it any comments um
2:16:32
yeah sorry what was the title of that again
2:16:39
the I just haven't seen balanced steady state
2:16:44
uh IM Imaging in a long a long time it takes me back yeah
2:16:51
um and uh yeah let me see sorry I'm just curious who's who's
2:16:59
um doing that that was
2:17:05
um oh is this the OSF it maybe yeah
2:17:13
um the you know this was a technique that was originally um
2:17:23
uh usually FM is is uh echoer Imaging
2:17:30
which is just says something about kind of like the nuts and bolts of the sequence balance steady
2:17:37
state is is a different way of doing it um originally taken from cardiac imaging
2:17:44
because it's super fast super fast read out so you can imagine trying to trying
2:17:50
to you know film The Heart right
2:17:55
right um that you need to be able to to you know capture a big 3D area really really
2:18:04
fast and um um this is Carla
2:18:10
Miller who was in John PA lab Stanford was the one like
2:18:19
this is going back to like when I started my PhD so 20 20 years ago yeah um was was
2:18:30
doing this um and I'm just curious in terms of
2:18:38
the um what else they have I mean you know
2:18:44
it would be an awesome technique if you could get it to work because because it's it's um
2:18:51
because of its super fast readout and um and so that and and
2:18:59
really yeah really high SNR and and
2:19:06
so you know she was doing some kind of
2:19:11
you know I think it was at the time like you know visual cortex kind of stuff um
2:19:18
but getting getting you know like sort of like structural
2:19:26
resolution kind of um
2:19:35
um millimeter cubic um
2:19:42
um yeah anyway I I'll I'll um I'm interested to see
2:19:51
who's who's actually doing that and how that's potentially connected to the Vaso
2:19:57
but you know but baso is the technique for for
2:20:03
actually capturing volume and you know so again like
2:20:10
echoer when when people talk about epai they usually say like Epi bold and so
2:20:15
they're talking about echoer Imaging and then this blood oxygen level
2:20:21
dependent signal um that is a muddy measure that's made
2:20:29
up of the oxygenation effect the
2:20:34
flow um change changes in the flow itself and then changes in the blood
2:20:40
volume and so the um the the people who
2:20:46
really care about you know getting these kind of really quantitative ative uh um
2:20:53
measures where you know the the you're only measuring one of those three yeah
2:21:02
right and and you know so sometimes they'll they'll combine like an
2:21:07
oxygenate you know a bold with a with an ASL technique to try and catch two of
2:21:12
those Bezos Bezos is another way to do anyway there's just a bunch of technical things that I saw that um that would be
2:21:19
really interesting but if you were doing that and and that would be the way to do
2:21:25
it at kind of like unheard of or you know again pre
2:21:33
previously unheard of kind of resolution and contrast to noise if you will in
2:21:39
terms of what really matters in terms of the fmri um that would be really remarkable and
2:21:47
um and then of course applying it to these particular domains it's it's would
2:21:53
be you know yeah super interesting yeah layer layer
2:21:58
FM you know as as like all the kind of research scanners like locations or you
2:22:06
know all the research Mr centers have moved to seven
2:22:11
Tesla the the ability to you know kind of using conventional
2:22:18
sequences with some tweaks you know they they've been getting this kind
2:22:24
of layer FM and some things that that they do um I've looked at some packages
2:22:31
for nidora in terms of just specifically getting kind of layer fmri
2:22:40
um but uh but that particular technique would be it's got a it's got a weird
2:22:48
spherical harmonic signal signal issue so it's like parts
2:22:57
of the parts of the the readout are are are good and parts
2:23:03
aren't and it has to do with this balance steady state effect that is kind
2:23:09
of it's super
2:23:19
[Music] you you know she she would be one of the first to jump on this if there was like
2:23:26
any kind of you know new insights into how to how to manage that uh that
2:23:33
gradient artifact um but um but cool fmri with you know a little active
2:23:40
inference uh yeah spin to it and um so I I'll
2:23:46
check the paper you know yeah I'll try to get the papers out two and slack
2:23:52
maybe that would be yeah sure sure they're all interesting guess yeah um yeah so that's good abut yeah thanks for
2:23:59
that discussion you know I just I think it's interesting set of things it kind
2:24:05
of discusses like you know sort of interation and how that's important in
2:24:10
of course it's embodied but also has this you know it's basically how our nervous system communicates and you
2:24:16
can't just say like I'm interested in what the brain's doing or I'm interested in what the body's doing it's this
2:24:22
interconnection especially in development which is interesting because we don't you know in like in
2:24:27
developmental AI that's one thing that people haven't really talked about is okay what happens if you don't have
2:24:33
these you have to have connections between parts and different ways yeah
2:24:38
yeah it's funny we had this this dinner last night with a bunch of
2:24:44
from a bunch of people it was you know host like a kind of VC company hosted
2:24:51
this neurotech dinner but it's people from all these different kind of companies right and um but this woman
2:24:58
from neuralink it was just interesting you know she's talking about the
2:25:05
the the progress that they've had with these particular patients that of course
2:25:10
have got these you know severe damage um and this is allowing them to move um but
2:25:19
I think one of the most interesting things we talked about was you know if if you
2:25:25
could capture that that in terms of development like have these kinds of
2:25:31
recordings during development yeah and just like like how how you know I mean
2:25:39
on one hand like how interesting that would be for you know brain Sciences
2:25:46
yeah U but also how challenging that would be you know it's one thing when
2:25:51
you have these adults but you know what do you do you know so one the brain's always
2:25:57
responding and is trying to generate kind of scar tissue around your implant and things like that yeah but you know
2:26:04
in the case of kids like you know their their skull is changing too right yeah
2:26:09
you anyway as she said there there there's they've got plenty of adults to
2:26:15
work with for a long time and but it should be um
2:26:20
yeah interesting so um yeah well I maybe
2:26:27
next Friday or you know at some point we could use Fridays to start thinking
2:26:32
about the the um the G Sox G to come yeah yeah let's do
2:26:39
that okay thank you have a good week all right take care take care bye
