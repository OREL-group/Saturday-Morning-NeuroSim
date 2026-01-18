## Meeting Recording

[YouTube link](https://youtu.be/J8lXB9rU6Tc)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115914399020270871)

## Feature Videos

[Recent posts to the Brain Organoids Slack channel](https://youtu.be/irTT_8kuYto)

[What is the Sakana AI Research Agenda?](https://youtu.be/2vr6JIisRgE)

[Whats New in the SF Tech Scene?](https://youtu.be/dV5-AE3ERtk)

## NOTES
AI Economist -- governing framework of agents.

* tax cheating -- optimization becomes degenerative (RL on the governing framework).

* sustainable governing framework. Robustness, longetivity.

* work put into project, long life if code is maintained.


Conversation to get to the point where agents code.

* Better Code, Better Education. Stallman --> software artifacts are different from things that have come before. Github contributors: Russ Poldrack, Steffan Bollman (Neurodesk), Yarrick (NeuroDebian), Claude (Agent).

* DataLad. Diffusion Methods --> most of Morgan's papers are on this.

* Refactored an existing Rhea project. 

* rough path theory: https://en.wikipedia.org/wiki/Rough_path

* open-source (people's own goals and considerations -- forks and hard forks, when to diverge and how to manage).

* software projects -- BrainGPT prompt. Fine-tuned LLAMA model.


UNIX philosophy of pipes: https://thelinuxcode.com/piping-in-unix-or-linux/#google_vignette


Ken Stanley is involved in Sakana AI (Evolutionary Methods/LLMs).

* artifacts: text objects --> LLM short-term memory.

* see how big commercial teams can optimize workflows.

* break up tasks, subtasks.


UV -- use instead of Conda. Written in Rust.

* immediate virtual environment for system. GUI in a sandbox.

* adding physics -- changes problem in a bunch of ways.


Our curricula assume "WEIRD" prerequisites. Set up a server in Germany, helps African students.

* African data --> old scanner, hallucinate models to approimate 7T scanner.


fNIR demo --> Kernel, provides 1cm deep images.

* photons that go deep into skull, less likely to come back out. 

* Jax refactoring -- microstructural MRI problem-solving.

JPM Healthcare Conference --> invote-only, lots of satellite events:

* Midwest Neurotech Conference -- something the UIUC NeuroTech group is trying to organize.

* big student group, trying to help new student groups get started.


AI-assisted coding. Event in the tower. Anti-Gravity (not vibe coding).

* Google Antigravity: https://antigravity.google/

* Jax -- drop-in replacement for NumPy. slow CPU implementation.


1) vision for Open Source Sustainability --> not coding agent, but simulation.

2) simulation of how humans behave.

Steve Yegge, Gastown, multi-agent LLMs.


Ben Blaiszik -- Argonne, MatSci, discovery. Physical Science rules: https://www.anl.gov/profile/benjamin-j-blaiszik

* automation pares down complexity, find the insight --> open-ended models.

* give mean experimental design, what will the result be? DEEPMIND math --> Terrence Tao's center. Lean (foundation model favorite). Creativity/hallucinations.

* theorem-provers: math and academic productivity are benchmarks --> is this capturing the full range of human behavior?

* how has human go changed since AlphaGo? Centaur Go?


Lieber Center @ Johns Hopkins --> Carlo runs a seminar series.

* what do we need to make mechanistic models of neural development?

* Russ Poldrack-like. Variation across species (stem-cell development).

* David Reddish -- Zebrafish, Mouse, Human, Primate. Embryology and disorders data insights.


See complexity, take it apart. Self-supervised techniques (end-to-end training of eyes for tissue).

* Normative Viability -- what are variables that matter?

* immense variability -- exposes complexity of roles, factors (developmental) effects of schizophrenia (phenotype), took a lot more work.

* Biological scale of the internet --> histological work --> go in with a single theory, lack of automation and computer vision (less insight).

* open-ended geometric representation, how to get CV to take in whole visual input --> Gestalt.

* growth in representation space, conceptual distance. 


Patrick Kidjer; like Chollet, he is defining the stack.

* Neural Differential Equations (NDEs): physics approach.

## TRANSCRIPT
0:01     
Hello.     
0:06     
Hello. Yeah, I got a bit of a sore throat. Oh, yeah.     
0:11     
It's that season. Yeah,     
0:18     
my daughter's been home for two days. Oh,     
0:26     
yeah. So, what's going on with you?     
0:32     
Um, maybe I need some more light. Yeah,     
0:42     
there we go.     
0:47     
More presentable here. Um, yeah, I uh     
0:53     
this week, let's see. Well, it's it was um JPM healthcare this week um which is     
1:01     
a a huge industry conference. Um     
1:07     
the joke is that no one you know has ever attended JPM healthcare because     
1:16     
JPM Healthcare is a invite only meeting     
1:22     
that is for big wigs and     
1:28     
uh people with, you know, real money. Yeah. Um     
1:33     
um so there's a bunch of euphemisms for     
1:40     
the conference ecosystem that is not actually JPM,     
1:48     
but a bunch of people do events at the same time as JPM.     
1:57     
Um and those were great. Good. So it it was it was you know we     
2:02     
did um we did uh demo day with kernel     
2:08     
which is this near infrared uh imaging helmet.     
2:14     
Um although they make dev kit so you can     
2:20     
you don't actually have to use the helmet. Um but that's their yeah really interesting     
2:28     
device to track blood oxygenation. Um so you can use it as kind of a a     
2:38     
less demanding MRI system. Uh it only sees about a centimeter deep     
2:46     
into the into the skull. So you can only kind of capture what's happening on the     
2:53     
top of the head. Yeah. And and so so the two two two things.     
2:58     
One, because of the helmet itself, it's like where the sensors are, you're     
3:04     
really capturing only the top of the head. And then two, you're you're depth is limited by the     
3:12     
the um uh photon transport. and and you know     
3:19     
how many of the very very few photons go into the head     
3:24     
and then come back out but those are the ones that you detect.     
3:30     
Yeah. Uh so deeper is is much much less likely that     
3:38     
the photons that go deep will come back out or certainly come back out to where     
3:44     
where your sensors are. Um, so you know it it has some it has some     
3:53     
limitations in Africa. Um,     
3:58     
but you don't have to have a two-tonon     
4:03     
super cools magnet system. So it is kind of portable.     
4:09     
Yeah. Um and then just another nice nice     
4:14     
meeting on uh Thursday with with companies talking um uh to two startup     
4:24     
founders. one one was a PhD from Stanford from the lab that uh one of the     
4:32     
co-founders from Nurling and the the other a PhD from Oxford who     
4:40     
went through the same lab that I did with Tim Barren doing doing     
4:46     
animal electrophysiology although now she's doing a very consumerf facing company um anyway that was great to     
4:55     
really nice. Um, we now have there's a bunch of UIU     
5:03     
students here. Oh, yeah. Yeah. No. Um, so, uh, I'll meet up with     
5:11     
them today. Um, so they're all with Neurotch at UIU.     
5:19     
Okay. Um, uh, one is the kind of like partnerships     
5:26     
manager. Okay. Excuse me. I think he's I think he's a senior. And, um,     
5:33     
uh, I'll find out. He he he got he was definitely in early.     
5:41     
I was supposed to meet him last night, but my my daughter was sick and my wife had something. So, um,     
5:47     
uh, I haven't seen him yet. But then there's two two I think freshman     
5:53     
um who are coming to because Photonix West started which is a big trade show     
5:58     
for optical um technology right and um then there's a sub meeting     
6:07     
called BIOS which is focused on biomedical optics right yeah     
6:14     
or it's you know biomedical imaging optics societ or something like that. I don't     
6:20     
know. B I L. Um and uh     
6:27     
so that that I I'll I'll meet with them later today.     
6:33     
We'll we'll kind of walk the trade show and see as well as like they'll come by Frontier Tower and look at it as as a as     
6:42     
like feel it out for the hackathon in April. Um     
6:48     
but uh really really excited because the UIC     
6:53     
has such a big neurotex society or you know student group.     
6:59     
um they're helping     
7:04     
coordinate a lot of the other student groups as well as like I'm really     
7:10     
encouraging them to encouraging all the student groups that are are established     
7:19     
to to have an eye towards how to help the new groups get started,     
7:28     
right? Like um uh yeah, like it would it be it'd be great     
7:36     
to at least devote a bit of time to helping helping the new groups. Um     
7:45     
I love that the mid that the that UIU is leading the way to have a a Midwest     
7:51     
neurochnology conference stu student run student run. um you know, but they're     
7:57     
they've, you know, reaching out to like Purdue, Indiana, um u     
8:05     
UIC, uh New Chicago, Northwestern,     
8:11     
uh Wisconsin, um Michigan. I think it's close to     
8:18     
Michigan. Yeah. Yeah, I should know this. Yeah. Um uh     
8:26     
yeah and um let's see what else. Um     
8:35     
well you know just just pointing out the other     
8:41     
issues that students issues that students in other countries     
8:47     
have that we don't have to deal with here. is um meeting with the students in     
8:53     
Africa this morning and um     
8:59     
they're they're in a blackout. Oh, okay. And and     
9:06     
unfortunately it is much more common than     
9:11     
um you know it's not just a power outage. It's like one of a regular like that     
9:20     
that's something that regularly happens and um     
9:26     
uh I'm not not sure not sure everything about it but um     
9:32     
it comes comes back to this issue of like um how best to you know we we we teach this     
9:41     
boot camp of MRI processing thing.     
9:46     
Um, but still a lot of the curriculum is is assuming a kind of um     
9:57     
I I I don't know if this is perfect example, but like you know that we're assuming a lot of weird prerequisites.     
10:05     
Weird weird being this acronym about right     
10:11     
the kinds of Yeah. It's I I don't know if it's that's     
10:18     
exactly the acronym I'm trying to get out. Yeah. The weird weird uh populations in psychology.     
10:23     
Yeah. You know that that Yeah. We we're we're we're certainly not the majority of the planet,     
10:29     
right? And and you know, it's it's like I I think I     
10:37     
said last week, you know, setting up a setting up a VNC server in Germany     
10:43     
might actually be the single most useful thing that we could do for these students     
10:50     
um because of of connectivity issues,     
10:55     
you know. Um although you know I     
11:02     
and then I I'll I'll finish so you can get started. But um the uh     
11:10     
had an incredibly productive week following better code, better science.     
11:18     
Okay. Uh uh I I I I think it's um it says a lot about the     
11:27     
project that the um     
11:34     
do you so so this is not just a Russ Bulldrack     
11:40     
project right? Yeah. So obviously he he's writing the     
11:46     
text. Um but he's doing it in an open-source     
11:52     
manner, right? Um I I was looking at the GitHub repo and I was looking a little     
11:58     
closer and I see two other contributors     
12:04     
and and so one is Stefan Bowman. Okay. the nerd desk guy     
12:11     
and um and the other is is Yerk Halenko who is the Nerd Debian guy.     
12:19     
Okay. And I and I like the fact that these are the two people that we've previously     
12:26     
reached out to for the Active Inference Institute to speak about open source.     
12:31     
Yeah. So I I I like that those are the two those are the two names associated with     
12:38     
better code better science GitHub repo. And then like and then I think it's like     
12:46     
um let me just check this but um and then I think it's like you know like     
12:53     
I I think Claude is another     
12:59     
you know um which again makes makes sense in this for this particular     
13:08     
Claude being the agent or the Yeah. Okay. Yeah. Yeah. Yeah. It's so so     
13:18     
looks like um Well, it's funny because it's like I see     
13:23     
um yeah because I think he's talking about data lad.     
13:30     
So, it certainly makes sense that um     
13:36     
here we go. Sorry, I'm just     
13:43     
um Okay. Well, I I'll find it. But like     
13:51     
yeah like like that makes sense that that they also have a coding agent be one of the um you know     
13:59     
contributors. Yeah. And I and I told you his his postoc is     
14:04     
is like a senior person at anthropic. So     
14:09     
I think that explains his um uh his choice. Um I I've been using uh Google's     
14:18     
tools. Right. So Gemini um and     
14:25     
uh yeah had a had a really productive     
14:30     
um week coding with Gemini.     
14:36     
Um I mean I I chose a project it like like know I'm tech I'm supposed to be on     
14:42     
the microructural MRI team at um camera     
14:48     
and yeah most most of my academic papers are on kind of diffusion processing or     
14:53     
diffusion data. Okay. Um so I I you know it's it's not uh     
15:01     
it's it's not out of my um my area. Um     
15:06     
but for the project direction I took     
15:14     
um it's actually a really great I mean I I I refactored an existing in RIA     
15:23     
project because I knew you know Jax was designed as a numpy     
15:32     
replacement. Right. Um,     
15:38     
and you know, it it's like Jax was very much designed as a a drop in replacement     
15:45     
for numpy, right? to to     
15:51     
and so I I I chose something that I knew     
15:58     
was built on NumPy um but was currently a slow CPU kind of     
16:06     
ex you know implementation. Yeah. and um     
16:13     
uh refactoring it and then following     
16:19     
um a particular there was there was a student back in Oxford who was one of these like     
16:28     
you could tell that this was the brightest person in the room you know kind of person yeah you know     
16:33     
and and he did his PhD with Terry Lions who's the like famous math competition     
16:42     
specifically on neural um differential equations.     
16:47     
Okay. Like like like you using neural networks to solve.     
16:54     
Yeah. I don't know if it would be right. I I forget what his thesis title is, but     
17:01     
something like something like neural differential physics or something like that. Right. Okay.     
17:08     
Yeah. Yeah. Yeah. and and     
17:13     
you know he's he's one of those people where     
17:21     
you you know almost like Freswell Chalet where     
17:26     
you you can see this is someone who's kind of like defining the software stack     
17:34     
you know for an area anyway it it's like it's like it started     
17:41     
as a Jack's refactoring of this microsructural MRI project. Um but I     
17:48     
found that like by by actually following everything that     
17:53     
Patrick kid um I think um     
18:01     
has the the choices that he's made. It's like, "Oh, now you see why he's done all     
18:08     
these things." Um, and and     
18:15     
it just turns out that his scientific software stack is actually very well     
18:20     
designed for solving the problems in microsructural MRI. Um, which is which is really cool. So, I     
18:28     
I I've I've got um excuse me, I've got a lot done on it. It     
18:34     
it's it's again it's a al but it's also a great example of just what Russ is     
18:41     
getting at in ter excuse me in terms of just you know like like my benefit here     
18:46     
is that I do know the area and so it's just like okay at a certain point I can     
18:53     
take a a kind of known data set that lots of researchers have used I could     
19:00     
process it and I kind of know what I should at     
19:06     
because other tools have processed this data before. You know, maybe tools that are slow, but     
19:15     
tools that that have been well vetted and so you get these answers out     
19:23     
um that tell you something about this particular data set. Now I can do it,     
19:30     
but it takes 4 seconds on, you know, a laptop,     
19:35     
right? Yeah. Because I'm just, you know, everything is is um super massively paralyzed and     
19:45     
um Yeah. So it's it's it's very cool. Um, I think I'll have like a nice little     
19:52     
virtual MRI scanner out of it     
19:57     
and and it's it's nice work that actually     
20:03     
when fully developed is will be really interesting especially in the um     
20:11     
connection with like super high field MRI microscopy and and histo ology and     
20:20     
the kind of work that people are doing there. So sometimes they're taking um uh     
20:26     
post-mortem brains, they leave them in the scanner for 24 hours.     
20:32     
So, and they just, you know, they they, you know, you you get these like     
20:39     
absolute incredible data sets that you can then     
20:44     
use to test out techniques.     
20:50     
um as well as like it being super interesting to apply to very noisy data     
20:55     
sets and and the kind of data sets that that they're collecting in Africa where     
21:02     
they're maybe collecting with with what we would consider an old scanner. Um,     
21:09     
but now we can basically ask the system to hallucinate,     
21:16     
tell me what this would look like if we collected it at seven Tesla on a research scale.     
21:22     
Yeah. So, it's um I think it's going to be an     
21:28     
interesting interesting project and I'm I'm     
21:34     
getting getting to the point where thinking about, you know, reaching out to some of the some of the um MR physics     
21:43     
people I know, seeing what would be what would be a good, you know, um     
21:50     
kind of real real world pass that would uh that would make them go wow.     
21:58     
Yeah. So yeah. Sorry I took for a long time.     
22:03     
Oh that's fine. Yeah that's great stuff. Looks like there's a lot of stuff going on and     
22:08     
often times you know just don't get to touch base with uh all that's going on.     
22:15     
So yeah this better code burner science. This is a GitHub repo.     
22:20     
Oh yeah yeah yeah. Okay. I mean, you know, you know, Russ, he he he does every, you     
22:27     
know, he he loves to do things in the open, right? Yeah.     
22:32     
Um, and like like he he's um     
22:40     
you know, if if I if I had the     
22:46     
um um if if I didn't have the the the     
22:51     
social anxiety, you know, I'm sure I could have reached out to him as soon as he published it. Yeah. as soon as he said and and you     
22:59     
know perhaps gotten involved like it's the kind of thing where he he's he's always hoping more people get involved.     
23:08     
I'm going to I'm going to go to um the     
23:13     
I'm going to go to a meeting that's in the tower but on     
23:20     
uh AI assisted coding and at least talk about this. I I'm I I don't want to, you     
23:28     
know, forget what we talked about last week. Um     
23:34     
but that that some     
23:39     
like like I still don't think I'm using anti-gravity     
23:44     
with which is which is Google's IDE     
23:50     
as as well as I could, you know, like Again,     
23:56     
to to Russ's point, most scientists are self-trained programmers, right?     
24:01     
You know, and and so I you know, and like like I maybe had more     
24:08     
training than most because like essentially my first job out of college     
24:14     
was was eventually taking over software engineering team     
24:20     
being a manager. these guys knew. I mean, but my programmers were like 20-year veterans     
24:28     
in coding with idees and C++ application     
24:33     
frameworks. They they they knew their tools. Yeah. Right.     
24:38     
I didn't I just knew the problem area. Right. Right. Um, uh,     
24:47     
so, so I'm still missing things. I just talking to a professor up in Toronto     
24:53     
and he was just like, "Yeah, I've been I've been using anti-gravity     
24:59     
and it's it's like having a team of grad students working for me." Um, and I I     
25:06     
said, "Well, you know, I'm just using I'm using Gemini. I'm using jewels." and he he didn't know what those were.     
25:14     
But, you know, when I started using anti-gravity, I could see like like it's essentially     
25:20     
a gooey for jewels, right? Right. At the same time,     
25:26     
there's definitely like wildcard um characters. There's there's     
25:32     
characters that you can use in your prompts     
25:38     
that have special meaning and I still don't know what those are. Yeah.     
25:43     
Like like you know, so I I don't know what a slash is for workflows. I don't     
25:49     
know what a mention is. I I don't. So, I'm gonna go to this AI assisted coding     
25:55     
where it's a bunch of basically like, you know, web front end people,     
26:01     
right? Um uh and I'm going to see if I can get a better sense of     
26:11     
um what are these? You know,     
26:17     
a better professional sense of the tools. Um because I'm sure     
26:23     
I'm still using them in a very crude self-taught way.     
26:29     
Yeah. Um um but the other thing being that as it relates to the open source sustainability project     
26:35     
like like there's some claw code projects um like uh     
26:44     
um like Gas Town. I don't know if I'm going to be able to find it.     
26:49     
Um     
26:54     
uh let me see.     
27:01     
Yeah. So so let me just Okay. Um share this. You know     
27:10     
coming coming back to again what we were talking about. um     
27:20     
you know so so I I had um I mean we have a     
27:26     
a constant stream of visitors at the tower right because it's like     
27:32     
you know we we've got over 500 members in the tower and then like     
27:38     
there's plenty of space so people are always coming by and uh this was     
27:45     
this was, you know, someone who's using,     
27:51     
you know, who's using AI assistant. I'm going to call it AI assistant. Never use the term vibe coded. I'm still not sure.     
27:58     
Yeah. Yeah. Um, you know, but he he was just like wanted     
28:04     
to know if I was using it, but seemed to think that like     
28:11     
I would benefit from uh having it do the data analysis for me     
28:20     
or like like you could teach it how to use your the tools you use and I was like     
28:28     
what tools like like     
28:35     
and you know I still yeah but but he showed me Gast Town which reminded me a     
28:42     
lot of Um I think Sarah's project     
28:48     
um in terms of being you know a multi- aent LLM     
28:54     
um software software development team     
29:02     
where everybody's got roles and things and um     
29:09     
again I don't know how how um     
29:16     
I mean I I always come back to two things like one what's what's your real vision for the     
29:24     
open source sustainability in terms of like like you're not trying to make a coding     
29:32     
agent. No. Right. you know, so what h how again do     
29:39     
you define the the goals of the project? Um     
29:47     
it it in a way that distinguishes it when so     
29:54     
many of the implementations could be seen as like     
30:00     
this is a software development project. Right. Right.     
30:08     
Sorry, that was more of a question, right? Oh, like what the vision is in terms of     
30:14     
Yeah. Yeah. Yeah. Yeah. So, I guess I guess the difference, you know, you're not developing a tool for doing the     
30:22     
actual like helping people in projects. It's more like simulating     
30:28     
a project itself and then looking at the sort of the possibility space of what     
30:34     
could happen in that project. So I mean you could simulate a a functional project, you could simulate a     
30:41     
dysfunctional project, you could try different scenarios where um you know so I know that the work that     
30:49     
Sara did uh you know a year and a half ago now um it was just generating some     
30:57     
sort of you know showing a proof of principle that this could be put together and put together in a you know     
31:04     
not in a large tech company sense like you know where it's very polished and     
31:11     
it's for purposes of like you know enterprise use. It's just kind of like     
31:16     
building a simulation so that we can simulate you know uh like contributors     
31:22     
and then how they put together issues and how they do these things. I mean that being said of course you know you     
31:29     
know how accurate is say like a large language model generated     
31:35     
uh system like that uh in terms of replicating what people would do that's     
31:41     
not necessarily you know a onetoone thing you know you're going to have sort of a that's     
31:48     
why I'm you know I'm thinking well maybe we need to be a little bit messier in the in the sense of having human uh     
31:55     
types of issues or human types of things. Maybe you know the a large language     
32:01     
model for example would generate very tightly defined issues and they're very     
32:08     
you know self-contained whereas like a contri human contributor might have a very open-ended issue and     
32:17     
you know it kind of gets worked on as it gets worked on and and it evolves into new things and and that sort of thing.     
32:24     
So we don't have the same sort of efficiency imperative. You're just interested in seeing what those that     
32:30     
structure of the project looks like trying to move forward from there and simulate some of those scenarios.     
32:38     
Um I mean my experience with open source at least has been like it's it's much     
32:44     
more open-ended than like what you might see in a typical uh you know where you     
32:49     
generate a bunch of issues and you solve them efficiently. And that's in that's interesting and that shows that you can     
32:55     
actually do that. But then beyond that, what are we actually trying to figure out? I mean, we're not using it to     
33:02     
improve performance necessarily. We're using it to simulate how these things     
33:07     
actually work. Um. Yeah. Yeah.     
33:14     
No, that that's that's good. Um     
33:20     
certainly yeah I see you know again I I've got an     
33:27     
interesting perspective on it as a Fedora packager because     
33:34     
you know it's one thing to I've been a software junior manager and I've also seen Fedorac. Yeah.     
33:41     
And and and at least perfectly on a lot of open source scientific software projects     
33:48     
and you know a company has a very clear vision     
33:57     
you know it might change but it's just like we want these features. We we we we want this thing to do this stuff so that     
34:05     
we can charge money. Well, yeah. Yeah. And and at open source projects, you     
34:12     
know, people are coming along all the time with kind of their own goals and     
34:18     
considerations and and um and some some of them are potentially even at cross     
34:25     
purposes, right? So this is why you get forks where     
34:31     
um you know I mean even even you know well     
34:38     
well-intended hard forks where it's just like hey to implement this thing I have to actually     
34:45     
really modify the tool right so I I can't I can't actually let     
34:52     
this be a kind of parallel process this is um this is a twig, you     
34:59     
know, off the um and you know, like uh I've certainly     
35:06     
seen that too. Um I've got well     
35:13     
um I mean I you know you know me um I'm always going back to the AI economist     
35:21     
that particular project in terms of just how     
35:31     
you know, as as a a tool in which they had agents,     
35:36     
but they were they were actually more interested in     
35:42     
um the the um the governing     
35:50     
framework um that the agents exist. existed in     
35:57     
and so in this case, you know, it was it was like taxation, right? Um     
36:07     
or at least in the one one of AI economist examples, it's the taxation     
36:13     
program and and you know, it was predicting basically how many people     
36:19     
would cheat. Um but but it was an interesting     
36:26     
simulation where you show that like you show the tradeoffs on that and that     
36:33     
like that at at at the end of the day a certain amount of of tax cheating is is     
36:40     
allowed because um the the the framework would     
36:46     
actually become degenerate if you tried to maximize     
36:51     
you know you tried to maximize zero crime.     
36:58     
Um that that you make it tolerable so that most people pay.     
37:04     
Yeah. And and that you don't need to spend so     
37:09     
much on oversight or enforcement. I mean it's that it's that kind of you know and     
37:16     
they they were doing RL on the governing framework.     
37:21     
Yeah. even though you know it was a hierarchical RL problem where the agents were RL     
37:29     
agents too. Um, yeah. Um,     
37:35     
but you you you you think you're you're interested in the     
37:44     
um yeah, the the     
37:50     
the potential messiness of the problem. I mean in the sense of like like     
37:58     
you you want human like agents, right? Well, humanike in the best and     
38:04     
worst sense. Yes. Uh but but and then and then what is the     
38:10     
sustainable um what is the sustainable governing     
38:15     
framework? Right. Right. Yeah. Or what what is what is the framework     
38:22     
that is the most encouraging sustainability or um robustness     
38:31     
um maybe longevity um I mean you know like I know that the     
38:37     
software sustainability institutees work is not exactly the same thing but it's a     
38:43     
it's a certainly a very It's an understandable goal that like     
38:50     
the work put into a particular software project um     
38:56     
it it has it has the potential for a life a very long life and and a very um     
39:05     
fruitful one you know if if the code is     
39:10     
um maintained and and you know cultivated     
39:17     
Right. Uh, you know, this goes back to kind of     
39:22     
like, you know, like the original Richard Stallman arguments about how     
39:28     
what how software art artifacts are different than um     
39:37     
than the kind of artifacts that that society has produced before. Yeah. Right. Like there's zero, you know,     
39:44     
there's zero cost to copying them, right? I mean,     
39:49     
essentially zero cost to copying them, right? So, so you could make a, you know, you can make a bazillion of them     
39:56     
as easily as as you know that making that first one is the hard part,     
40:03     
right? Copy zero is more expensive than copy one and copy two.     
40:09     
Yeah. And then and then you know but then     
40:14     
it is this now at least in an open source fashion it is     
40:20     
now a template um um     
40:25     
both for for understanding a particular problem as well as like you know a     
40:30     
building block to something even bigger perhaps. I mean the kind of Unix philosophy of of     
40:38     
pipes where you can now, you know, string 10 tools together     
40:44     
and actually create something new.     
40:50     
I'm sure you got some uh some papers and some     
40:57     
Yeah. Yeah. Let me items. Yeah. Let me get some things up here. Um     
41:03     
the some of the things you mentioned uh do you have links for     
41:08     
the better code better science GitHub? Oh yeah, absolutely. Yeah. And uh     
41:14     
uh I like the um I like the mist book that they did.     
41:22     
I think that's the new     
41:30     
uh Yeah, this is the this is the current rendering of the     
41:38     
book     
41:44     
is there. So, let's Yeah, let me pull up this one.     
41:50     
So this one is the Yeah, this is Gas Town. So Gas Town is     
41:58     
Yeah, that that's that's that's again just getting at um     
42:04     
clawed agents like like multi- aent um code development.     
42:10     
Okay. Yeah. you know, and just how just an example of using one of these     
42:18     
commercial systems in a in a kind of sorrow way.     
42:25     
Yeah. Yeah. Yeah, it just like, you know, just it's fascinating to me that it's like it's so     
42:34     
but but at the same time there's a bunch of reasons why it's     
42:40     
actually really useful for LLMs in their current form to to adopt this, you know.     
42:49     
So, so actually I I believe Gemini I believe the Google team actually refers     
42:57     
to artifacts as um text objects that LLMs create     
43:05     
to give themselves short-term memory. Okay. Wow. Yeah.     
43:11     
So they um they're     
43:18     
you know I mean and again what we're trying what I'm trying     
43:24     
to do is to see how     
43:29     
these big commercial teams right who are dealing with     
43:36     
you know the the the frontier models Right.     
43:44     
How are their engineers trying to, you know, deal with the     
43:50     
limitations as well as like extend their functionality, right?     
43:56     
Yeah. So, it's just like like imagine you had all the resources in the world because     
44:01     
that's basically what these teams have. Uh um you know this is this is what     
44:10     
Google Deep Mind's doing, right? It's like like they're they're trying to get     
44:15     
their agents their thinking models. They're trying to get them to break up tasks     
44:22     
as they go. They they they want them to um stop,     
44:30     
plan, write the plan, then restart     
44:37     
taking, you know, item one, you know, now break up into subtasks,     
44:46     
right? start doing those subtasks like know when you've completed those     
44:52     
subtasks, right? So it there's there's a lot of there's a     
44:59     
lot of breaking up a task and there's a lot of of again like let me let me make     
45:09     
I think the Google term is an artifact and some of that is like what if I get     
45:16     
cut off at this point you know what if yeah what if the system I'm on crashes     
45:23     
which which certainly happened to me um developing yesterday. Um     
45:30     
uh starting agents on on a DGX Spark is interesting because you've got 128 gigs     
45:36     
of RAM essentially. And so the system basically the systems agents kept on seeing my     
45:43     
Blackwell processor and thinking that they had so much RAM that they were each     
45:49     
grabbing 90 gigs and then it crashed. Then then then the     
45:56     
OS started having to kill things because it didn't have enough frame. Yeah. Um but but just uh     
46:05     
the a you know so they're they're trying to move to multi- aent but they     
46:12     
they need something some intermediary output to to so that they can share with each     
46:20     
other. Hey     
46:25     
Um um I'm just just talking about some of my AI assisted coding.     
46:34     
Yeah. Um     
46:39     
yeah. So, so Gaston was what one of the one of the programmers um who said that     
46:47     
he he like, you know, everything he does these days is is a AI. He's agent driven     
46:56     
and and he he he suggested I look at co gas. My my problem is that I I'm kind of     
47:04     
committed to, you know, like I don't have unlimited resources, right?     
47:09     
And uh I feel like I'm already paying Google enough. Yeah. Um um but I'm super curious     
47:19     
uh because there there's definitely a lot of buzz and excitement around cloud code.     
47:27     
Yeah, I'm I'm I'm definitely trying to push having a tighter loop. I mean, it seems     
47:35     
like some of the some of like why you don't have agents     
47:41     
at the terminal is is actually AI safety     
47:48     
is somewhat AI safety driven. Yeah. And and by that I don't mean like you     
47:55     
know Ghost in the Shell. I mean like so that that an agent doesn't like erase     
48:01     
your drive, right? Yeah.     
48:08     
It's not just to keep the genie in the bottle, right? It's Yeah. You don't send your     
48:17     
Yeah. You don't send your life work to DevNull. Um     
48:23     
uh yeah, but then the the second link is the is the Paul Dre book. the um     
48:32     
and this well this is the book is there where is the GitHub repository? Oh yeah sure sure. So the the GitHub     
48:44     
if they have a link on that now yeah one sec. All right     
48:50     
but yeah this is the book. Yeah. So, this is the sort of the back end or the front end of it.     
48:55     
And then um Oh, like I see some more people holding     
49:01     
down the bottom. Yeah, he he he just moved the repo     
49:09     
to Okay, here it is. This is the read only one.     
49:15     
I I I got it. I got it. So, so he he in the new year he moved it to um     
49:25     
he moved it to be become its own organization. Oh, okay. Yeah.     
49:30     
Instead of, you know, so his his like his GitHub username is Coldre.     
49:37     
Yeah. But um uh so it used to be a personal repo and then he made it into an or     
49:43     
Right. Right. That's always a good always a good strategy. Although you always have like stuff that's     
49:48     
uncoordinated across the different uh     
49:53     
Yeah. So, looks like we have Yeah. five contributors. Stefan Bowman,     
50:00     
Claude, uh Oslav, and uh yeah, and and Georgio, I guess.     
50:08     
Yeah, Georgio. Giorgio was the one I didn't I I I don't know him. Okay. Yeah. I I I I'm assuming 100%     
50:18     
uh or you know I I'd put money on that uh that's a um a ner imager.     
50:28     
Yeah. Okay. Yeah. I'm gonna see. I could I could be wrong.     
50:34     
Yeah. And then pull of course. Um yeah. So     
50:39     
that then this is the book. I guess this is just kind of the back end of the book.     
50:45     
And uh yeah, so that's the front end. What is Claude doing to for this repo? I     
50:52     
mean, what is the is it just like to uh     
50:58     
specifically how is Claude committing to this repo? Do you know or     
51:03     
No, I mean um you know it's it's I don't     
51:09     
think the book is is you know primarily uh like trying to be I think I think     
51:19     
he's just I think he's just trying to acknowledge     
51:24     
that that Claude is absolutely a part of his workflow,     
51:29     
right? and and you know I I mean at this c     
51:36     
certainly for my um u diffusion     
51:42     
microructural it's a it's a crappy acronym but diffusion microructural imaging in     
51:48     
Python. So, DMI. Yeah. DMI P.     
51:54     
Yeah. Yeah. Yeah. Yeah. Yeah. I I I absolutely hate it because I can't make     
51:59     
it into a word. A cool word. Yeah. Yeah. I I in my head I just call it     
52:06     
dimpy. Yeah. But but that's that's a flipping around.     
52:11     
I don't know how to justify that. Um uh     
52:18     
you know like like so much of the     
52:23     
it's not just the coding right but it's the convers you know it's like you have     
52:28     
a conversation to get to the point of having agents     
52:35     
code right so so     
52:40     
I mean I I absolutely feel like, you know, I have to acknowledge this this um     
52:49     
uh the this model and like, you know, it's a co-author.     
52:55     
Yeah. Like like it's a co-author. Um     
53:01     
and uh Yeah. Yeah. And this is it's been     
53:08     
interesting. I I think last week I talked about the kind of you know kind of low-level     
53:14     
GPU programming work that I'd done and and     
53:20     
you know how how incredibly useful it was for it to     
53:26     
be this expert in you know in the kind of the low-level     
53:32     
details of memory systems. um     
53:37     
uh yeah architectural differences cond     
53:44     
limitations right so like by the way I mean if if anybody hasn't already like I     
53:51     
I've switched to UV for for everything Python like     
53:57     
um I noticed I noticed that the soften team     
54:03     
so that's this is the mind's by um the Minds Eye 2     
54:10     
team, you know, the the former stability AI guys that now have their own startup.     
54:16     
Yeah. Um, so that was where I first noticed that they were pushing     
54:23     
um their MedArk open science group was was like first you install UV     
54:33     
and and it it's pretty amazing. But again, it's the kind of thing where it's just like,     
54:40     
you know, um I'm I was working and     
54:46     
um Nvidia was pushing and I think that's partly because Honda's got like, you know, it's got a     
54:53     
big team too, right? So, it's just like Nvidia wanted to be like Anacondas on our DGX.     
55:03     
Yeah. The problem being that you you you have an ARM dependency, right? It's not an     
55:10     
x86 platform. Um, so there's stuff that doesn't work.     
55:15     
And so when the DJX came out, there was the the the first thing they were saying     
55:21     
was just like, you know, Anaconda saying like, "Hey,     
55:27     
we're we're working hard to get the rest of our stuff ported, you know, and so it     
55:34     
was like it was kind of a good thing, but it was also like, hey, by the way, this isn't this isn't ready as a     
55:41     
development system." Um, uh,     
55:46     
Gemini, you know, I I was already using UV and they were point, you know, Gemini     
55:52     
pointed out that like, oh, that UV will solve all your problems on AR.     
55:57     
Okay. And it and it totally happened and it's faster     
56:03     
like like in every way, shape, and form it's better. Um     
56:09     
you know like like in terms of you know basically like these     
56:15     
automates you know what would be three commands is is kind of essentially one     
56:21     
with UP just immediate virtual environments for for your systems. Um     
56:28     
and and I've seen this more too where um applications now Python applications     
56:35     
are you know it. So it's like I can UVX     
56:42     
something that would be a pip install and basically run like it it it both     
56:49     
creates a virtual environment pip installs that the tool     
56:55     
and executes right. Yeah. So, so what you see with like UVX     
57:01     
Nifty app is you see a guey appear that's ready for work.     
57:07     
Yeah. Right. But it's actually doing that in a in a sandbox,     
57:13     
you know, with with like the Python you need and the the requirements that that     
57:19     
that tool's going to meet. Anyway,     
57:24     
I'm getting very software engineering today,     
57:30     
but I but I I I've loved it. I mean, it's the it's made me actually, you     
57:37     
know, consider like at first I was just like, okay, we can just keep this box on     
57:42     
the network and people can load load jobs on it. Like like with     
57:48     
with UV like I think it could actually be your workstation. Like it could be your PC.     
57:54     
Yeah, for sure. And you should be doing everything in Jacks.     
58:00     
Okay. Yeah. Yeah. Yeah.     
58:05     
Let me let me I I think I shared this with before, but let me if not this is     
58:13     
the guy at Oxbridge whose tools Um     
58:20     
uh I mean he he was an archer. I thought, you know, it's funny because I think this guy is now in San Francisco.     
58:26     
Okay. Like like you know like everybody um     
58:32     
uh Okay. Kid Yeah. And if you go to software,     
58:41     
right? Yeah. um     
58:49     
if you see these these particular tools, right? And and I definitely want to say     
58:56     
um that you know down to     
59:02     
senpai to jacks. These are all um     
59:11     
uh like like best of breed implementations,     
59:17     
right? Yeah. I mean it it it's     
59:23     
so it's like yeah the closest thing to kind of like following you know core     
59:31     
Julia people you know like and and let     
59:37     
me just also find his um uh     
59:46     
yeah this is The is doctoral. Yes. Have you seen     
59:54     
publications? Yeah. Neural differential equations and machine learning thesis.     
1:00:01     
Yeah. On on neural differential equations. Um but he he was the um     
1:00:09     
he's the student of um Terry Lions who's the uh     
1:00:17     
guy developed rough path theory. Okay.     
1:00:24     
Um like like really great     
1:00:30     
software implementations to to follow. Um     
1:00:36     
and and I tell you I've talked before about um you know Crunch Lab. Um     
1:00:45     
um so this is the     
1:00:53     
the Crunch Crunch group at um at Brown.     
1:01:00     
Um     
1:01:06     
um but like like in particular     
1:01:14     
the times in which you know adding adding physics changes     
1:01:23     
the um changes the problem in a in a variety of     
1:01:29     
ways. Right? There's there's a bunch of ways that which physics informed neural networks can can be applied and um     
1:01:39     
and in diffusion MRI in focused ultrasound um     
1:01:47     
these are these are super valuable. Yeah.     
1:01:52     
Um, so I I I I wanna I want to make the, you     
1:01:59     
know, like the I don't know if it's like the add-on book, but um     
1:02:06     
um the the the response to Volra should be um um better code, better education.     
1:02:15     
Yeah. Yeah. That's Yeah.     
1:02:21     
I it is it's I I get I get why he has     
1:02:27     
the ordering he has right. Yeah. Um but I'm I'm looking at it partly I     
1:02:36     
mean I was saying this to V before uh we we talked just after New Year's     
1:02:42     
and um you know in working with student groups     
1:02:48     
right like like So, one, it was crazy that I had never     
1:02:53     
used an LLM, right? Like, like, you know, I almost finished 2025. I've never     
1:02:59     
used an LM um     
1:03:07     
to, you know, somebody like Russ comes along like, you know, and and he's been     
1:03:15     
teaching, you know, he he's such an educator, right? um and coding in particular, right? And     
1:03:25     
he's talking about it, right? Um     
1:03:31     
but how about going the other way? Like like how can we use this to actually     
1:03:37     
help students learn these concepts,     
1:03:43     
you know, and anyway, so that's that's that's what I would like to see.     
1:03:49     
Yeah. Well, this is all great stuff. Um, yeah. What why don't we move I have actually I     
1:03:57     
want to talk about Sakana actually. So, we'll move on to that. Um, I have some     
1:04:03     
things that I want to present on it but then we can talk about it after. So, um     
1:04:10     
this is u an organization Sakana. Um it's run by David Ha and and some other     
1:04:16     
people. This is one of their graphics um from social media. So if you know as you     
1:04:22     
know in Japan they're very fish oriented. Their cuisine has a lot of     
1:04:27     
fish in it. And like the emperor at one time was an eichthologist.     
1:04:33     
So it's like it's very fish oriented culture. So, they have the fish theme here of Fish working on Fish Warrior and     
1:04:41     
they're coding AI agents and they're in an arcade where they're playing Core War. And if you're familiar with Core     
1:04:48     
War, this is a a simple game that was developed back in the early60s. It has     
1:04:55     
this deep history in computer science. And core war is a game where you pit     
1:05:03     
little programming agents against one another and they compete for computational resources and they do     
1:05:10     
interest they have interesting behaviors when you do that when you build this kind of a uh setting. And so the core     
1:05:18     
war is a war over coding resources or core you know memory resources. So the     
1:05:23     
agents will fight over memory and getting the memory they need to execute their program. And this is you know uh     
1:05:31     
this has been um instantiated in a lot of different ways. A lot of different     
1:05:36     
groups worked on core war from the '60s forward. Um     
1:05:42     
uh you know in the 80s they codified some of the rules for core war and of     
1:05:47     
course the Avida platform the artificial life platform is based on this basic idea of agents competing for uh     
1:05:55     
resources and core memory. The movie Tron of course was based on     
1:06:02     
this idea that you you know there's a CPU and that there's a sort of almost     
1:06:07     
social hierarchy built around the CPU. So, it's a real interesting kind of history here um in a lot of ways. And     
1:06:15     
so, Sakana apparently is Japan's answer to open AI. Japan wants to be     
1:06:22     
competitive in a I mean, Japan has a very rich history in robotics. Um, but     
1:06:27     
they want to have like their own open AI. So, this is their website, Sakana     
1:06:32     
AI. This is uh so they're in Tokyo and they want to democratize AI in Japan.     
1:06:39     
So, I don't know if that's necessarily being just like OpenAI, but um that's their goal. So, they have a blog. Um     
1:06:47     
their blog has a number of interesting things on it. This is the digital red     
1:06:52     
queen adversarial program evolution and core war with large language models. This is actually a new post. Um that's     
1:07:00     
an interesting title. Um but basically, they're playing core war. They're using large language models and they're     
1:07:07     
basically evolving programs by getting the different large language models to compete with one another and have these     
1:07:13     
battles. And so you can see that they um have this fitness function that they're using to evaluate the programs. And the     
1:07:21     
fitness function is increasing with time as they play the game. So they're     
1:07:26     
they're different rounds of this game and they're increasing their fitness for     
1:07:31     
the most part as you can see. um the is the digital red queen     
1:07:38     
algorithm. So the red queen is a uh old concept in evolutionary biology which is     
1:07:44     
where you have basically uh sexual selection     
1:07:50     
uh where you're evolving um you know sort of these better and     
1:07:56     
better solutions to a problem. Um and so this is but they're using this in a     
1:08:01     
computational context. So they're using a lot of concepts from coralore, a lot of concepts from ev um uh evolutionary     
1:08:08     
programming to kind of get at some of these problems. And then they're using agents uh AI agents as well. So Sakana     
1:08:18     
AI agent wins a coder heristic contest. Uh first AI to place first. This is     
1:08:24     
Fisheline is their fishen is their u handle here. This is Sakana AI. Um yeah,     
1:08:31     
there's our graphic. Um and uh yeah, so they have a lot of interesting stuff     
1:08:36     
going on here. They've gotten funding of course as a startup. Um let's see.     
1:08:47     
So this is their AI scientists. They they've done some work on AI scientists towards fully automated open-ended     
1:08:53     
scientific discovery. Um this is I think I don't know if this is like just one     
1:09:00     
group that's doing AI scientists but um their approach is here. So at Sakana AI     
1:09:09     
we have pioneered the use of nature inspired methods to advance cutting edge foundation models. Earlier this year we     
1:09:16     
developed methods to automatically merge the knowledge of multiple large language models. So they have these methods for     
1:09:24     
um sort of having this evolutionary model merge. So it's this post here,     
1:09:29     
evolving new foundation models, unleashing the power of automating model development. So this is um we're pleased     
1:09:37     
to announce that our paper evolutionary optimization of model merging recipes has been accepted at nature machine     
1:09:44     
intelligence. So this is the link to the publication. Um, back in March 2024, Sakana AI     
1:09:51     
released evolutionary model merge, which generated some attention in the AI community.     
1:09:57     
Um, it's since been implemented in well-known open-source frameworks like MergeKit and Optuna Hub, enabling     
1:10:04     
diverse users to create and publish many unique models. Multiple internal and external teams     
1:10:12     
have been pursuing follow-up research. One example is cycle QD which is accepted to ICLR.     
1:10:20     
Uh so they're they're using evolutionary model merge as sort of one of their core     
1:10:25     
um uh methodologies. Um so this this nature machine     
1:10:30     
intelligence paper is evolutionary optimization of model merging recipes     
1:10:36     
and this has um David H on this paper with some co-authors     
1:10:42     
and this is basically where they're merging these large language models     
1:10:47     
together. Large language models have become increasingly capable but their development often requires substantial     
1:10:54     
computational resources. Although model merging has emerged as a cost-effective promising approach for     
1:11:01     
creating new models by combining existing models, a current rule relies on human intuition and domain knowledge,     
1:11:08     
limiting its potential. Here we propose an evolutionary approach that overcomes this limitation by automatically     
1:11:15     
discovering effective combinations of diverse open-source models, harnessing     
1:11:20     
their collective intelligence without requiring extensive additional training or compute. Our approach operates in     
1:11:28     
both parameter space and data flow space allowing optimization just beyond the     
1:11:33     
weights of individual models. This approach even facilitates cross-domain merging generating models such as a     
1:11:40     
Japanese large language model with math reasoning capabilities. So, the Japanese math large language     
1:11:47     
model achieves state-of-the-art performance on a variety of established Japanese large language model     
1:11:53     
benchmarks, even surpassing models of substantially more parameters despite not being     
1:12:00     
explicitly trained for such tasks. Um, furthermore, our culturally aware     
1:12:05     
Japanese vision language model generated through our approach demonstrates its effectiveness in describing Japanese     
1:12:12     
culture specific content, outperforming previous Japanese vision language models. This work not only contributes     
1:12:19     
new state-of-the-art models back to the open source community, but also introduces a new paradigm for automated     
1:12:25     
model composition. This is it's interesting because we don't think of large language models     
1:12:31     
oftent times outside of English because a lot of the large     
1:12:38     
language models foundation models that we talk about all the time are English-based and so you know having     
1:12:44     
this here is is pretty good um and it just kind of opens a window into that     
1:12:51     
kind of uh research. So this is interesting. Uh let's go back to     
1:13:00     
the AI scientist. And if we go back to the II scientist,     
1:13:05     
uh we find that uh so they do this work on merging the knowledge of multiple large language models. They've harnessed     
1:13:12     
large language models to discover new objective functions or tuning other large language models. So they're doing     
1:13:18     
this sort of uh parameter discovery or this um discovering different equations     
1:13:24     
or discovering different functions uh given data. So that's that's also     
1:13:29     
interesting. Um so in our report we propose     
1:13:35     
a fully or okay in our report we propose and run a fully AIdriven system for     
1:13:41     
automated scientific discovery applied to machine learning research. The AI     
1:13:47     
scientist automates the entire research life cycle from generating novel ideas,     
1:13:52     
writing any necessary code, and executing experiments to summarizing     
1:13:57     
experimental results, visualizing them, and presenting its findings in a full scientific manuscript.     
1:14:04     
We also introduced an automated peerreview process to evaluate generated papers, write feedback, and further     
1:14:11     
improve results. It is capable of evaluating generated papers with near human accuracy.     
1:14:18     
The automated scientific discovery process is repeated to iteratively develop ideas in an open-ended fashion     
1:14:25     
and add them to a growing archive of knowledge. This imitating human scientific community. Um in this first     
1:14:32     
demonstration, the AI scientist conducts research in diverse sub fields of machine learn within machine learning     
1:14:38     
research discovering novel contributions in popular areas such as diffusion     
1:14:44     
models, transformers and groing which are is you know different areas. Um and     
1:14:52     
then the AI scientist is designed to be compute efficient. Um, each idea is     
1:14:57     
implemented and developed into a full paper at a cost of approximately $15 per     
1:15:02     
paper. So, you know, this isn't without flaws, but it it's a good first step in     
1:15:08     
this area. So, this is uh uh this is an example paper adaptive dual skill     
1:15:15     
denoising generated by the AI scientist. So, um     
1:15:21     
this is the PDF here. dual scale diffusion adaptive feature balancing for lowdimensional generative models. And     
1:15:28     
then this is kind of going through this paper uh talking about diffusion models and um     
1:15:36     
some of the things that um applying this to lowdimensional spaces     
1:15:43     
and then they propose an adaptive dual scale denoising approach for low dimen     
1:15:48     
dimension fusion models. uh they evaluate their approach on four diverse 2D data sets circle dinosaur     
1:15:56     
line and moons. Our experiments demonstrate significant improvements in sample quality with reductions in kale     
1:16:03     
divergence of up to 12.8. So they have all this these main     
1:16:08     
contributions. Um uh it's a novel adaptive dual scale     
1:16:14     
denoising architecture. It has a learnable timestep condition waiting mechanism.     
1:16:21     
It's a comprehensive empirical evaluation on various 2D data sets and then this gives insight into the     
1:16:27     
dynamics of the denoising process and lowdimensional spaces. So that's the paper. Um and then I want     
1:16:35     
to get to um some of the other papers that they've done. So this is of course the AI     
1:16:42     
scientist post that we talked about um and     
1:16:49     
There's this other paper on unlocking groing. So this is a comparative study on weight     
1:16:56     
initialization strategies and transformer models. So this is um     
1:17:04     
the abstract here. Um this paper investigates the impact of weight initialization strategies on the groing     
1:17:11     
phenomenon transformer models addressing the challenge of understanding and optimizing neural network learning     
1:17:17     
dynamics. Grocking where models suddenly generalize after prolonged training     
1:17:23     
remains poorly understood hindering the development of fishing training strategies. We systematically compare     
1:17:30     
five initialization methods. So these pietorch Xavier key orthogonal and king normal     
1:17:38     
across four arith arithmetic methods or tasks in finite fields using a     
1:17:44     
controlled experimental setup with a small transformer architecture. Our approach combines rigorous empirical     
1:17:50     
analysis with statistical validation to quantify the effects of initialization     
1:17:56     
on crocking. Results reveal significant differences in convergence speed and generalization     
1:18:02     
capabilities across initialization strategies. Xavier's initialization     
1:18:07     
consistently outperformed others, reducing steps to 99% validation accuracy by up to 63% compared to the     
1:18:15     
baseline. Orthogonal initialization showed test dependent performance, excelling in some     
1:18:21     
operations while struggling in others. These findings provide insights into the mechanisms underlying groing and offer     
1:18:28     
practical guidelines for initialization in similar learning scenarios.     
1:18:34     
Our work contributes to the broader understanding of deep learning optimization and paves the way for developing more efficient training     
1:18:40     
strategies in complex learning tasks. So yeah, they talk a little bit about     
1:18:47     
groing as a concept. Um, rocking refers to a sudden     
1:18:52     
improvement in generalization performance after prolonged training, often occurring long after the training     
1:18:58     
loss has plateaued. This phenomena challenges our understanding of how neural networks learn and generalize,     
1:19:05     
particularly in the context of small algorithmic data sets. Um and then of     
1:19:11     
course we have this aspect of Wayne initialization strategies and their     
1:19:16     
impact on grocking and transformer models. While transformers have become the de facto architecture for many     
1:19:22     
natural language processing tasks, their behavior on arithmetic tasks provide a     
1:19:28     
controlled environment to study fundamental learning dynamics. Um     
1:19:37     
so then this relationship between weight initialization and groing presents several challenges. So one is that     
1:19:44     
groing itself is a complex phenomena that is not fully understood. So we it's hard to really kind of know what to     
1:19:50     
expect in terms of results. The highdimensional nature of neural network parameter spaces complicates the     
1:19:57     
analysis of how initial weights influence learning trajectories.     
1:20:03     
Third, the interplay between initialization, model architecture, and task complexity adds another layer of     
1:20:09     
intricacy. And so those to address these challenges, they conducted their     
1:20:15     
systematic comparison of methods. Uh our main contributions are that we     
1:20:21     
provide a comprehensive study of the effects of weight initialization strategies.     
1:20:27     
Uh we demonstrate the different initialization methods can significantly influence groing behavior. We offer     
1:20:33     
insights into which initialization strategies are most effective for difficult arithmetic tasks and we     
1:20:40     
analyze the learning dynamics associated with each initialization method.     
1:20:46     
So that is the AI uh scientist and grocking and then the multi uh     
1:20:53     
multi-style generation or style fusion paper.     
1:20:58     
This is uh a little bit different area now. Um this paper introduces the     
1:21:03     
multi-style adapter, a novel approach to enhance style awareness and consistency     
1:21:10     
and character level language models. As language models advance, the ability to generate text in diverse and consistent     
1:21:17     
styles becomes crucial for applications ranging from creative writing assistance     
1:21:22     
to personalized content generation. However, maintaining style consistency while preserving language generation     
1:21:29     
capabilities presents a significant challenge. Our multi-style adapter addresses this by introducing Lunable     
1:21:36     
style embeddings and a style classification head working in tandem with a style adapter module to modulate     
1:21:43     
the hidden states of a transformerbased language model. We implement this approach by modifying the GPT     
1:21:49     
architecture incorporating style adaptation ever after every transformer layer to create     
1:21:56     
stronger styles specific representations. Through extensive experiments on     
1:22:01     
multiple data sets including Shakespeare's works and wiki 8 and text     
1:22:07     
8, we demonstrate that our approach achieves high style consistency while maintaining competitive language     
1:22:13     
modeling performance. Our results show that improved validation losses compared     
1:22:18     
to the baseline with the best performances in N onWiki and text 8. Uh     
1:22:25     
notably we achieved nearperfect style consistency scores across all all data sets for Shakespeare and Anwiki and text     
1:22:33     
8. The multi-style adapter effectively balances style adaptation and language model capabilities as evidenced by the     
1:22:41     
improved validation losses and high style consistency across generated samples. However, this comes at a cost     
1:22:48     
of increased computational complexity resulting in slower inference speeds     
1:22:53     
approximately 400 tokens per second compared to 670 in the baseline. This     
1:22:59     
work opens up new possibilities for fine grain stylistic control and language generation tasks and paves the way for     
1:23:06     
more sophisticated style aware language models. So um     
1:23:14     
this is you know thinking about this this problem um so this is a problem     
1:23:21     
that is um you know stated in the literature the ability to generate text     
1:23:27     
and diverse and consistent styles is crucial for a wide range of applications from creative writing assistance to     
1:23:34     
personalized content generation styleware language models that can adapt different writing styles tones and     
1:23:41     
genres are more versatile and userfriendly. However, implementing style awareness in     
1:23:46     
language models presents several challenges. So, capturing and representing diverse styles within a single model     
1:23:52     
architecture, maintaining style consistency while preserving the model's language     
1:23:58     
generation capabilities. and then ensuring the model can generalize generalize to unseen styles and adapt to     
1:24:05     
new contexts without compromising its core language modeling abilities.     
1:24:10     
And so um on multi-style adapter, our multi-style adapter addresses these challenges by introducing learnable     
1:24:17     
style embeddings that capture diverse writing styles, a style classification head for dynamic style inference, and     
1:24:25     
then a style adapter module that modulates the hidden states of a transformer based language model.     
1:24:31     
So that's paper and I think that's a good representative     
1:24:36     
sample of what Sakana AI is doing. Uh, I remember what was the what group put out     
1:24:43     
that paper that we reviewed um late last year. It was like they were doing     
1:24:48     
evolutionary large language models or something like that. Was it Google? I     
1:24:54     
think Morgan knows this, but could have been one of the Google AI teams.     
1:25:00     
Um     
1:25:06     
um I mean I I certainly know what you're talking about, but I'm trying to I mean     
1:25:12     
before I before I leave out my crutch and actually search um     
1:25:23     
I mean I Yeah. Yeah. I I I kind of want to say it     
1:25:30     
was um the what is intelligence guy, but it could be. Yeah, I think it was     
1:25:36     
actually. Um let's let's Yeah, you got to check. But     
1:25:44     
well, while you check, I'll mention that. Uh so I mean, you know, this is just kind of another way that we can use     
1:25:49     
evolutionary methods to do these solve these kind of problems. Uh and and the     
1:25:55     
the history of this goes back quite deep into computer science. It goes back to core war as we've seen. And so um in     
1:26:02     
core war we have these very simple programs that evolve to solve sort of to     
1:26:09     
compete for resources in the CPU. So you you know you start off with programs     
1:26:14     
that are maybe two different styles. You have like an A type and a B type and     
1:26:20     
they kind of run through and they they compete for memory. they repro self-reroduce.     
1:26:26     
They might have a mutation operator which means they can change their instructions or they can lose     
1:26:32     
instructions or gain new instructions and then they use that kind of method to     
1:26:38     
um evolve strategies to gain more resources. So you almost get like this     
1:26:44     
digital ecosystem of different programs. Sometimes programs will uh find a niche     
1:26:51     
which isn't like you know dominating every other program but it's getting it the resources that it needs. Sometimes     
1:26:58     
you get programs that try to dominate the ecosystem. Sometimes you get programs that go     
1:27:03     
extinct. You know you get a whole host of interesting behaviors. And the idea is     
1:27:09     
you can harness a lot of that to build agents that you know um can do things.     
1:27:15     
And so that's that's kind of where that's coming from. And then they're applying of course all of this to large     
1:27:21     
language models and some of these pro uh project domains that we talked about.     
1:27:26     
And the AI scientist is particularly interesting because uh that that gives     
1:27:32     
you a domain for like reasoning and building like you know models and then     
1:27:39     
you know basically leaning on a lot of the strengths of large language models but doing something that we can     
1:27:46     
understand. A lot of um things in science use science as the benchmarks.     
1:27:53     
You'll see this again and again and it's not just in AI research you know you'll use say for example     
1:28:00     
uh science you know social scientists will use other social scientists as     
1:28:05     
indicators of certain behaviors. So like in in network theory they'll use like     
1:28:11     
publishing behaviors of scientists as a way to build networks. And that's, you     
1:28:16     
know, maybe that's good, maybe that that that's an accessible benchmark, but maybe it's also bad because it's a very     
1:28:22     
small subset of human behaviors. So that's uh my my two cents on all of     
1:28:28     
that. Um, but they're doing a lot of interesting work to see.     
1:28:35     
I I I'm I'm not finding an easy I'm not finding a paper where I'm like, "Oh,     
1:28:41     
yeah, that's the one." Well, that's okay. that I mean it exists     
1:28:47     
and and certainly one person that uh that will be no surprise is um Kenneth     
1:28:53     
Stanley working on this. Oh, okay. Yeah. Um uh um     
1:28:58     
you know then then there were several Chinese teams     
1:29:04     
um as well as some interesting like like I think it got proposed as a workshop     
1:29:10     
topic for Gecko 2025. Um, apparently there's a upcoming     
1:29:17     
workshop in 2026 um referred to as Evo Star.     
1:29:24     
Oh yeah. Yeah. Um Um     
1:29:30     
Yeah. Uh I I dropped links to, you know, the the Future House team.     
1:29:38     
Um, I'm not I'm not sure they're worth, you     
1:29:46     
know, like like it's just one of those like billionaire funded     
1:29:52     
teams where, you know, what what if we give what if     
1:29:58     
we give a a bunch of people who've got, you     
1:30:04     
know, great backgrounds um a lot of money and time to focus on this     
1:30:10     
and then they spin off a forprofit company. Yeah.     
1:30:16     
Like I like can we wait to see what the output is first? Yeah. Well, we do     
1:30:23     
pivot already, you know, like like before you even showed anything, you need to start charging money.     
1:30:30     
We did make it advance. We started a company. So, Right. Right. Well, yeah. Yeah. Yeah.     
1:30:35     
Yeah. Yeah. Um, uh,     
1:30:41     
yeah. Anyway, it's it's the I I wanted     
1:30:48     
one of the one of the software projects that that I want to do that seems pretty easy and     
1:30:56     
now with with a coding assistant, um, I think I should be able to pull off     
1:31:03     
is the the brain GPT. um um project which is like a fine-tuned     
1:31:12     
LMA model that has been trained on a bunch of     
1:31:18     
neuroscience cogno papers and I'm really interested to see     
1:31:27     
uh uh what what it might be able to say     
1:31:33     
about some particular like what it's supposed to be doing is generating     
1:31:38     
it. It's supposed to be telling you like if if you give me an experimental     
1:31:43     
design, I will predict what the result will be.     
1:31:50     
And you know, I think I think there's some there's some uh     
1:31:57     
some some easy examples we can try on this. Um     
1:32:02     
uh the the I I think it's interesting what     
1:32:09     
the latest kind of like deep mind math     
1:32:15     
work and the AlphaFold team and well and     
1:32:21     
like teams that have gone beyond AlphaFold have been finding or kind of like how     
1:32:30     
their approaches are different now. But so so on the one hand just the the math     
1:32:36     
work and it's awesome that Terrence Tao is like you know fully embraced I think     
1:32:42     
he's got a new center that's actually focused on AI scientists really like work.     
1:32:48     
Yeah. um uh he he you know he he was he's been     
1:32:57     
very bullish on AI coding assistance and     
1:33:02     
formal math theory provers and um yeah     
1:33:08     
the kind of you know developing the kind of Kevin Buzz buzzard um     
1:33:15     
uh like work and um Uh and obviously     
1:33:23     
all the foundational language model teams have have like fully started embracing um uh     
1:33:34     
lean for for for that like you know like     
1:33:39     
like can can we use c can can we can we     
1:33:47     
back um back prove.     
1:33:54     
You know, we we we know we we want hallucinations and then we want to     
1:34:00     
backfill a reasoning like we we want to validate them     
1:34:09     
and you know so like again like creativity has has hallucinations,     
1:34:14     
right? Yeah. Um um but then you know to to your point in     
1:34:22     
terms of just like you know everybody's been leaning on a couple     
1:34:28     
areas, right? And and so like math obviously is one.     
1:34:36     
Um but then you know Alphafold is like one of the first examples where it     
1:34:42     
seemed like you know deep learning made this major you know again it it blew     
1:34:48     
away a benchmark that had existed for like 30 years     
1:34:56     
and and it was like it wasn't just like 10% better. it it you know it was just     
1:35:05     
destroyed the benchmark right um um so that that's also been     
1:35:12     
interesting because you know of what the teams that have tried to follow it have found right so     
1:35:20     
again like just keep on harping on this like you know like how has go how has     
1:35:27     
human go changed since Alph Oh yeah. Right. Right. Because it it hasn't died.     
1:35:36     
Right. Right. Right. And and um     
1:35:44     
Yeah. I I I think you know as as like     
1:35:50     
coming back to kind of better code, better education. Yeah. Right. like you know um     
1:35:56     
uh it's interesting you know I I was uh I was on chess team     
1:36:04     
as like you know a little kid right like I can't imagine     
1:36:14     
yeah like like the the chess programs could be so much more adaptable     
1:36:22     
to the player and to like now talking     
1:36:27     
talking the student through     
1:36:32     
what's going on in the game, right? Like like again like I'm I'm so old I     
1:36:38     
can remember when they were just using magnets underneath a big board to actually drag a piece,     
1:36:47     
you know, like like you had physical pieces. Yeah. Right.     
1:36:54     
Um as if that was smart, you know. Um but like like how those strategies, you     
1:37:02     
know, like how alpha I mean how it goes change and then you know in the alpha     
1:37:07     
case like like the the the data then again becomes a     
1:37:16     
problem, right? that like like AlphaGo kind of made its its     
1:37:22     
breakthrough because there was all this data that was kind of like     
1:37:29     
being underutilized and and so there there have been some     
1:37:36     
really interesting um extensions beyond AlphaFold now and and it is interesting     
1:37:43     
the innovative approaches that have been taken Um but at the same time like like you     
1:37:52     
know so many of the Google Deep Mind you know AI science um discoveries     
1:38:02     
have have have been absolutely useless. Yeah. Um,     
1:38:08     
and and you know, like like I I'm picking on them because I'm using     
1:38:15     
their tools and so like I'm I'm not biased or you know using them, right?     
1:38:21     
Like it it's it's it's uh you know so they've they've had AI     
1:38:29     
science papers where they've said that we've discovered 100,000 new materials, right? And and it the problem is that it     
1:38:37     
actually takes humans, you know, like 10 years to actually go through those     
1:38:42     
100,000 results and be like, "This is all crap." Right. Right. Yeah.     
1:38:49     
Human written papers in some ways, too. But Yeah. Yeah. Yeah. Yeah. Yeah. Yeah. Yeah. Nobody remembers that.     
1:38:55     
Yeah. you know like um but I think that's really important and and     
1:39:02     
you know that in in which domains are you actually     
1:39:08     
seeing any consider I mean that that's that's my that's my beef with with     
1:39:15     
future house is just like like show me this is show me this is worth 200 a     
1:39:21     
month before Yeah. Yeah. like like you you you you've probably got one I mean I I     
1:39:30     
I I would love to know what what they base this on in terms of just     
1:39:36     
I think Google was pushing an idea that um     
1:39:42     
that they their AI had discovered a new cancer treatment. You remember this?     
1:39:50     
No. last year. Anyway,     
1:39:56     
yeah, I I I think you could count on one hand the number of high-profile stories     
1:40:04     
and each one of them has a     
1:40:10     
a lot of controversy. Yeah. Or or or a lot of complexity like like     
1:40:15     
Alpha comes with a lot of complexity. Um the the the math is the is certainly you     
1:40:21     
know the area where there's there is a lot of excitement from from top mathematicians.     
1:40:28     
Right. Right. Well, I think people see the potential, but it's like, you know, what is the practice going to look like     
1:40:36     
as well as like, you know, you know, I mean, I'm I'm being hyperbolic, but um     
1:40:44     
um but uh but they know math isn't real, you know,     
1:40:50     
you know, I mean like sure it's good here.     
1:40:57     
Um, so you know like like I I always     
1:41:02     
pointing it towards Ben Blazic as the guy in Argon who you know is like the     
1:41:09     
person to follow for material science. Um I forget what his group is called.     
1:41:16     
It's like the material science data     
1:41:21     
discovery center. Yeah. the material science discovery center     
1:41:28     
something something like that. Yeah. You know where it's just like like you     
1:41:34     
need data you know and and the national labs have a lot of it. Um you need rules     
1:41:42     
right? So it's just like like chemistry at least has a whole bunch of of     
1:41:50     
existing rules that they understand that they can they can you know you need constraints on the system right um     
1:42:01     
yeah it's like like     
1:42:06     
you know when they start when they start generating you know     
1:42:13     
you know, when we start running around with like this the suits from Black Panther that can absorb energy, you     
1:42:20     
know, and turn it into something else because of the material properties. Like, okay, you know, maybe maybe this     
1:42:26     
is working. Well, that's good. All right. Well, why     
1:42:31     
don't we move on? So, I just wanted to sample Sakana AI. I wanted to talk about some of the stuff, see where we are in     
1:42:38     
that area. like we're doing some interesting kind of reflections on this and hopefully,     
1:42:44     
you know, maybe we can put something together for later in the year.     
1:42:51     
So, I know that uh Morgan posted a few things in the brain organoids channel. Maybe we can go through those things and     
1:42:57     
look at them. Um I put some things um from last week on     
1:43:03     
the conversational psychiatry. Okay. Yeah. I don't I don't Well, we we     
1:43:09     
can talk about that separately. Organites. Organites. Yeah. 100%. So, this is uh yeah, this is Thomas     
1:43:15     
Verbuchin U. And this is next generation stem cell models for studying brain     
1:43:21     
development and disease. So, he's using this organoid model for looking at this     
1:43:27     
uh a few screenshots. What is this from? What what talk series?     
1:43:32     
Oh, okay. This is um so yeah, so this this particular group     
1:43:39     
um I should say is um what I love about     
1:43:44     
this group is sorry I got the video started here.     
1:43:52     
So, um, Carlo runs a, um,     
1:44:00     
I think he's associated with the Liber Institute at Johns Hopkins. Okay. And, um, or certainly that's that's the     
1:44:08     
that's the group that's kind of like the closest to my heart, you know, super     
1:44:14     
focused on developmental disorders like schizophrenia.     
1:44:20     
um uh really, you know, seeing it as a neurodedevelopmental disorder, trying to     
1:44:27     
understand mechanism. Um Carlo runs a seminar series     
1:44:35     
that um is is     
1:44:41     
covers all these topics, right? Yeah. Uh he he he in particular     
1:44:48     
let me just get his um the the particular website. Right. So     
1:44:56     
yeah. So let me see if I can pronounce his last name right. Colon     
1:45:03     
Tonyi. Okay. All right. Um so uh     
1:45:11     
Carlo Carlo um     
1:45:17     
works on methods and and bringing data. So coming back to this AI scientist     
1:45:25     
issue, right? like like what do what do we need to be able to make     
1:45:35     
mechanistic models of of neuro development, right?     
1:45:41     
Um having large multihomic spatial multiomic data     
1:45:50     
sets um uh is is so vital. So, um, let me let     
1:45:58     
me get his, um, let me get his website because it's like he's, you know, to     
1:46:06     
some degree trying to do what um,     
1:46:14     
you might say like Russ Pauldra does for neuroiming data. Okay.     
1:46:19     
with open neuro. Um I haven't quite found it yet, but but     
1:46:27     
the the data um the he's got a platform that's called like Nemo     
1:46:35     
uh see if I can find it. But but you see on his his website here, you know, he's     
1:46:42     
he's particularly interested in these human, you know, cellular variation maps     
1:46:49     
like like how they relate. I mean, but it's it's so it's not just stem cell     
1:46:54     
variation and embryionic development, but it's like across species and and     
1:47:01     
so so one it's like it's a tool for     
1:47:07     
understanding right so the the particular talk that you saw there right     
1:47:12     
is like you know focused on mouse models.     
1:47:19     
Yeah. Right. But right because that's the one we can     
1:47:24     
manipulate at least with our current ethics. That's the one we can we can manipulate. Um uh     
1:47:34     
but then connecting these two humans, right? So there's another guy um whose     
1:47:42     
talks I've been watching recently. It's um uh     
1:47:48     
let me see. It's um David a I don't want     
1:47:53     
want to say reddish um     
1:48:01     
yeah right um     
1:48:06     
yeah so you know cross species translation through computational analysis at David Rich I I'll find the     
1:48:14     
link but like like this is this is the the the point of like trying to     
1:48:22     
um to some degree do the data wrangling. So that you've got mouse, you know,     
1:48:29     
you've got you've got um you got zebra fish, you got mice, you got say nonhuman     
1:48:38     
primates, and you've got human data sets, right?     
1:48:45     
and um how to how to link those as well as like in each one of these how     
1:48:52     
do they speak to to embryology and and um and its disorders,     
1:49:00     
you know. Um and he's he you know in particular his     
1:49:09     
um uh his research focus is on um     
1:49:17     
uh some of the     
1:49:24     
tools for um data insights.     
1:49:31     
in these large multiomic data sets. Mhm. So, um     
1:49:37     
I mean just just as an example, um     
1:49:43     
so sorry, I'm just finishing up with giving you a link to David Reddish     
1:49:53     
as as someone to you can find like a a rich YouTube history, rich publication     
1:49:59     
history on some of these topics. But but going back to Carlo um you know like     
1:50:04     
like um um other other kind of PCA     
1:50:11     
techniques to you know because when when you've got multiomics     
1:50:18     
spatially and so you know you're looking at multiple cell types right like like how     
1:50:25     
to how how to try and understand these multiomic data sets and get and get     
1:50:31     
insights from them in terms of you know gene expression     
1:50:36     
uh relationships um multisellular relationships     
1:50:42     
multisellular interactions etc. That's that's the um     
1:50:50     
and and he runs a regular series on this. Okay. And Yeah. Yeah. And then um just for     
1:51:02     
um yeah it's the Liber Institute for Brain     
1:51:09     
Development. Yeah, John's H. Yeah, this is the I I forget, you know,     
1:51:15     
with some of these some of these institutes like     
1:51:21     
not not 100% sure if like like is it at Hopkins or is there like work? Yeah, it     
1:51:27     
it's near Hopkins and like Hopkins professors like have, you know, like     
1:51:32     
work there but have appointments at Hopkins, you know. I think they might be private, you know, but but the but the     
1:51:39     
point being that like it's had a long history of like it has the largest postmortm brain collection is     
1:51:44     
schizophrenia. Okay. Yeah. and and they've they've certainly     
1:51:51     
you know like like it's come up before in terms of the um conversational psych     
1:51:57     
I mean the um brain organoid work that that that     
1:52:03     
interests me in terms of um approaches to to try and try and address     
1:52:09     
questions around schizophrenia. Yeah. So one of the things he talked about in     
1:52:16     
this talk was this polygenicity of neurological disorders. So this is where     
1:52:23     
this is uh where where the they have this G-W was data and they're looking at     
1:52:30     
the contributing alals to or loi to the different um thing that they're assaying     
1:52:37     
here. So this is from this paper truthcoy at all in nature which I don't     
1:52:42     
have up but like basically this is the idea he's trying to communicate that this was you know this is schizophrenia     
1:52:50     
and you have this gwas and you have all these different contributing factors.     
1:52:55     
This is not you know this is above and beyond or this is sort of just the     
1:53:00     
genetic contributions. This is not the um other contributions yet. So this is     
1:53:07     
uh you know this is just kind of the genetic underpinnings of development     
1:53:12     
and then brain development is comp dynamic and     
1:53:17     
complex. This is of course is a slide showing kind of the uh cortical     
1:53:23     
structure of a one-month-old versus maybe the cortical structure of an adult. you have this developmental time     
1:53:29     
course from progenitor amplification to deep layer neurogenesis     
1:53:36     
to upper layer neurogenesis and then to glyogenesis. So you have these stages of     
1:53:42     
human cortical development going from E10.5 to birth. And then you can look at     
1:53:48     
this in mouse and it would be a little bit different and you know any kind of vertebrate and you'd have differences in     
1:53:55     
how these things proceed in terms of the timing. Um so this is but this this is     
1:54:02     
communicating the point that the G-W was that we saw on the last slide gets sort of put into place and development     
1:54:08     
through this process. And then of course if we can understand the process and     
1:54:14     
some of the things that go into brain development at these different stages and then the GW we have the G-W was     
1:54:21     
information. we can then perhaps understand maybe you know how     
1:54:27     
schizophrenia develops and we can understand more about those sorts of disorders. That's kind of what they're     
1:54:34     
getting at here. And then this and then this slide which I found     
1:54:40     
interesting um where he lays out and I think uh Morgan posted this slide in the     
1:54:46     
slack uh where this is kind of a longitudinal study for embryionic     
1:54:52     
development. So you're looking at pur potent stem cells here not an invivo case but like you it's a cell culture     
1:54:58     
thing where we're looking at these uh pur potent stem cells and looking at embryionic development. So you go from     
1:55:06     
this genotype space which is represented by the G-W was. You have these polygenic contributions.     
1:55:12     
You have the phenotypic space which is how that those things are manifest in the phenotype. And then in the middle     
1:55:18     
you have this development space which you can see is kind of represented by these layered surfaces. And so like you     
1:55:26     
go from the genotype space and they get those genes or those alals or loi get     
1:55:32     
expressed in development in different ways uh and then those different ways     
1:55:38     
that they get expressed contribute to the phenotype and I guess this means adult phenotype. It wasn't I found this     
1:55:45     
slide intriguing because you know for one thing it's kind of like showing that     
1:55:50     
you're it's a generative process from the genotype to this developmental     
1:55:56     
uh representation this phenotypic representation. On the other hand, it's not quite     
1:56:02     
accurate in in the sense that development is sort of a phenotype     
1:56:08     
and development sets up the adult phenotype and you have to distinguish between sort of the developmental     
1:56:15     
phenotype and the adult phenotype. On the other hand, you can't really pull those apart too much because the     
1:56:21     
developmental phenotype sort of influences the adult phenotype in different ways. It's really, you know,     
1:56:27     
this is an intriguing representation, but I'm not, you know, I don't know. I     
1:56:33     
mean, I get the the point, but like it's it's a little bit more the representation maybe is a little bit     
1:56:39     
more complex than this. Um, what was interesting about this is that in our     
1:56:46     
divor meetings, we've talked a lot about um epigenetic landscapes.     
1:56:52     
And epigenetic landscapes were a method or technique kind of proposed by uh     
1:56:58     
Wington. And Wington when he did this he he just drew these sort of pictures and     
1:57:04     
used this metaphor of a landscape with with um with valleys and those valleys     
1:57:11     
were called channels or or uh this process of canalization. So you had this     
1:57:16     
landscape where you had these channels that were driven by developmental trajectories. And so you'd start at the     
1:57:23     
top and he used this ball as the metaphor of unfolding development. And     
1:57:28     
then development would unfold along these trajectories with these branching points. So you would have, you know, and     
1:57:34     
then the ball would represent like a phenotype and then the ball would move down the channel to a branching point     
1:57:42     
and then the ball would either go down one trajectory or another and it would keep doing that until it gets to the     
1:57:48     
bottom of the landscape which is supposedly the adult phenotype. And the idea is you could draw out these     
1:57:54     
trajectories through this developmental space and define these different phenotypic     
1:58:00     
possibilities at the end. So wherever that ball moves through these channels, that's sort of the     
1:58:06     
developmental trajectory that leads to the adult phenotype. And one of the things about that landscape was that it     
1:58:12     
was highly metaphoric. So it didn't really have a lot of detail. Uh but actually he did propose that of course     
1:58:19     
this is all underlied by genetic interactions. So if you go back to the G-W was map, you see that there are a     
1:58:25     
lot of contributing lossi there, you know, they contribute at different     
1:58:31     
amounts. So some are genes of large effect, some are genes of, you know, uh     
1:58:37     
trivial effect and then of course de depending on your developmental state or     
1:58:43     
your developmental period or phase, you know, those those genes contribute more or less. So this is kind     
1:58:50     
of and then he You know, again, he was very ky well ky maybe he didn't have the     
1:58:57     
detail in terms of the genetic map. So he just had these um kind of these     
1:59:03     
little squares and lines coming up and it was um you know the idea was     
1:59:09     
basically that that that was a standin for these genetic interactions. And so     
1:59:14     
since that time people have tried to quantify the map or quantify the the epigenetic landscape. And so I think     
1:59:21     
that would kind of be interesting in in the context here which you know proposes that there's of course a genotype that's     
1:59:27     
being expressed. It's expressed into this developmental map and then that developmental map leads to the     
1:59:33     
phenotype. But it it it's basically generative in the sense that     
1:59:38     
development sets up the adult phenotype. You can't just have like a developmental process that leads to a phenotype and     
1:59:46     
you know there's like one combination of things that leads to that phenotype. Um     
1:59:51     
there are all sorts of things like you know things like phenocopies     
1:59:56     
and you have uh buffered phenotypes. You also have uh pleotropy. So you get     
2:00:03     
different types of phenotypes from essentially the same genes but the interactions are different. So they lead     
2:00:09     
to different phenotypes. So there are different ways in which this phenotypic space looks that are totally dependent     
2:00:15     
on the development or interactions. So it's again an interesting uh concept     
2:00:21     
set of concepts to play with. Now this paper this other paper that uh Morgan     
2:00:27     
posted was also interesting and so yeah that that talk is in that     
2:00:34     
talk series that that Morgan mentioned. Um this is a perspectives paper that is     
2:00:41     
primary cyia as architects of the neoortex. So this again is a lot to do with brain     
2:00:47     
development and microephille in this case instead of schizophrenia. Um so uh     
2:00:54     
primary silia architects of the neoortex roles in brain development function and microphily.     
2:01:01     
So this is um a group out of Denmark and France.     
2:01:06     
um and they're looking at primary hereditary microephille or MCPH     
2:01:12     
a condition closely linked to neoccortical development. So initially MCPH genes were thought to regulate a     
2:01:18     
limited set of cellular processes but recent studies reveal that many uh encode multifunctional proteins often     
2:01:26     
converging on primary psyia organels that orchestrate the development of the most vertebrate tissues and organs.     
2:01:34     
And so these are these mechanisms um     
2:01:39     
these organels that really kind of put together the brain um in development. In     
2:01:47     
this perspective article, we examine the role primary psyia and brain development and explore how disruptions in MCPH and     
2:01:55     
microphily associated proteins compromise siliary dynamics and function. So these psyia are building     
2:02:03     
sort of the the tissue, you know, the cells are are um being put together into     
2:02:09     
this tissue in a certain order and the psyia are working to sort of build that     
2:02:16     
structure and then the siliary dynamics are affected by these     
2:02:22     
uh genetic states. So the idea is that there's some disruption maybe in the     
2:02:27     
genetics uh genetic interactions or the genetic states in development and disrupts the way that the brain is     
2:02:34     
developed into this adult phenotype. So they also want to explore how disruptions in MCPH and microphily     
2:02:43     
associated proteins compromise cereody dynamics and function. We highlight additional psy uh psyio     
2:02:50     
related proteins with potential influence on neuro development by elucidating the connections between     
2:02:56     
primary psyia and neuro development. We aim to provide insights into mechanisms of neuro regeneration.     
2:03:03     
So it's also has an important role in neuro regeneration and they can understand that as well.     
2:03:10     
Ultimately advancing our understanding of primary psyia may help develop therapeutic strategies to restore     
2:03:16     
neuronal function and improve outcomes for individuals with neurodedevelopmental disorders.     
2:03:22     
So this is uh focusing on microphille which is something that is it's a brain     
2:03:29     
disorder defined by reduced brain size while maintaining an overall normal architecture. So it affects the growth     
2:03:37     
of neoortex in terms of brain size. Uh so micro is small and sephily is is head     
2:03:45     
or brain. And then uh so the phenotype     
2:03:50     
is manifest by an occipital frontal head circumference smaller than at least two     
2:03:56     
or three standard deviations below the mean for age, gender and ethnicity. The     
2:04:01     
diagnosis of microphilles is usually performed antennally during routine ultrasonic examin     
2:04:07     
ultra sonographic examination or postpartum during the neuro neonatal     
2:04:13     
physical examination. Microphily can be caused by a number of genetic and environmental factors     
2:04:20     
including but not limited to inutroviral infections, tetra uh ter uh     
2:04:28     
teratogen exposure which things like fetto alcohol syndrome and metabolic     
2:04:34     
conditions of the type listed here. Genetically conditioned primary     
2:04:40     
microphille is ter microphily primary hereditary or MCPH. It's a specific type     
2:04:46     
of microphille that we're interested in here which is typically inherited in an autotosomal recessive manner and     
2:04:53     
primarily affects the development of the neoortex. Cortic corticogenesis the process of     
2:04:59     
neoortical development unfolds at the emergence of early neural stem cells     
2:05:04     
which expand in a number of in the ventricular zone of the cortex. So you get uh stem cells that expand in this     
2:05:12     
ventricular zone. they migrate up and they form belt cells or differentiated     
2:05:17     
cells and so you get a limited pool of those neural stem cells and you have     
2:05:23     
less uh growth of the neoortex. You have a smaller growth of the neoortex but you     
2:05:30     
have the same architecture. It's just fewer cells. So you have neural stem cells which give     
2:05:37     
rise to intermediate progenitor cells that init initially differentiate into neurons and then later gal cells.     
2:05:44     
Subsequently these neurons embark on radial migrational and gal fibers reaching the cortical plate to establish     
2:05:51     
dendrites and external connections and culminating in the formation of the six layered cyto architecture.     
2:05:58     
And so the proliferation of neural stem cells influences the neuron count which     
2:06:03     
in turn shapes the size and function of the neoortex. So this is why you have smaller brain size overall.     
2:06:12     
MCPH is gen genetically heterogeneous with at least 30 genes listed so far in     
2:06:17     
the online mandelian inheritance in man or OMI database encoding proteins that     
2:06:24     
orchestrate one or more of the patterning processes of the neoortex. Uh in MCPH gene variants affect primary     
2:06:33     
psyia which function as cellular antenna that orchestrate developmental processes in most vertebrate cell types. psyia     
2:06:40     
uh yeah they they serve as these antenna in the cell they kind of protrude from the cell and they have this this role of     
2:06:47     
monitoring sort of the developmental process for the cell so it you know kind of knows     
2:06:54     
where to go and things like that. Um so this is you know a way to orchestrate     
2:07:01     
developmental processes like neural stem cell pool expansion, axon guidance and     
2:07:07     
neural migration during corticogenesis. So monitors sort of where the cell is in     
2:07:12     
the in the brain where the axon should go you know these are all chemical     
2:07:17     
signals. uh and then pool expansion I guess to make sure that there are enough     
2:07:24     
neural stem cells in in the neural stem cell pool you know to know when to stop     
2:07:29     
dividing and um you know having that sort of a self-regulating uh um     
2:07:35     
capability. These findings have contributed marketkedly to our understanding of brain development and celia and     
2:07:41     
neurodedevelopmental disorders. So in this perspective article we present an integrated overview of     
2:07:48     
corticoenesis and the molecular genetics of this disorder with a focus on how     
2:07:53     
selected microinsphily associated genes function at the level of primary psyllium.     
2:07:59     
We examine the multifunctional roles of MCPH genes within a siliary framework     
2:08:05     
highlighting those most likely to act directly at the psyllium. And then they explore silary mechanisms that influence     
2:08:11     
both developmental and regenerative processes emphasizing the emerging role of primary     
2:08:17     
psyia and neural restoration. So they want to advance their     
2:08:23     
understanding of how MCPH related pathways shape brain development and may be harnessed to promote neural repair.     
2:08:30     
So they're interested in this disorder, but they also want to know how some of     
2:08:35     
these uh psyia play other roles in the brain. Um how these pathways also allow     
2:08:43     
for plasticity and so on and so forth. So there are a lot of aims in this paper     
2:08:48     
and they kind of go over uh what what is known in the area. So this is a figure     
2:08:54     
here u this this is worth going over. I think this this shows neoccortical     
2:08:59     
development. So again you have this time course of uh of cortical development in     
2:09:04     
the human and then in the mouse. So when you see E, it's the mouse. Um, E8, E10,     
2:09:11     
E15, P1 through three, and then P2 through 4. And then that corresponds with human     
2:09:18     
stages WPC3, WPC5, 10, 22, and 25. So you know, they have     
2:09:24     
these basically they've worked out these developmental stages in each organism. Um, and then they, you know, there's an     
2:09:32     
there's an analogous stage in another organism. So since human and mice are     
2:09:37     
both mammals, you have these uh stages that are conserved between the two     
2:09:44     
species and you know their timing is you know basically the same but it's you     
2:09:50     
know there's a different nomenclature involved. Um I mean there's variation in the in the     
2:09:57     
stages in terms of their timing but it's they're all basically analogous.     
2:10:02     
So this just shows the different types of cell. You have the psyia on the sort of the edge of the cell. You can see in     
2:10:09     
this epidmal cell we have motiles at the bottom. Sometimes psyia or you know     
2:10:15     
sensory organs. Sometimes they help the cell move. There are different uh roles for different types of psyia. You have a     
2:10:21     
primary psyllium here coming out of the edge of the cell. Here you can see you have different types of uh styles     
2:10:28     
neuroprogentor cells neurons and inter neurons. So you see the neural progenitor cell sort of you know     
2:10:35     
precursor to a number of different cell types and it differentiates accordingly and of course the psyia differentiate     
2:10:42     
accordingly as well. You also have aststerytes igodendrite precursors and     
2:10:48     
oligodendrites. So you have neurop precursors which can become neurons. They can also become astrittes and uh     
2:10:55     
other types of cells. You also have these other things like oligo dendrite precursors that have a more restricted     
2:11:03     
set of fates. Um this is a radio migrating neuron and a tangentially migrating neurons. So you     
2:11:10     
have different types of cells emerging at different stages of development. So in this case we have these NECs that     
2:11:17     
emerge very early and then you have this uh ARGC which emerges a little bit     
2:11:23     
later. There's a pool expansion of these cells. So these are progenitor progenitor cells that uh form and then     
2:11:32     
they expand their pool size. So as you know undifferentiated cells or precursor     
2:11:38     
cells uh divide and then provide um sort of constituents for uh neurons     
2:11:47     
and other types of cells later. So we have this pool expansion of the precursor cells. We have then this     
2:11:55     
differentiation process. We also get migration involving the psyia. So the     
2:12:01     
psyia are basically picking up chemical signals within these different parts of     
2:12:06     
the developing brain telling the cell where to go telling the cell where to project its axons and so forth. And it's     
2:12:13     
moving through the ventricular zone the subventricular zone and then into the different layers of cortex.     
2:12:20     
Later on you get this neuron neuronal organization and you get tangential migration so that     
2:12:27     
different cells know how to connect to other differentiated cells. And you see the psyia are marked here to show that     
2:12:34     
they're an integral part of this process. They're sensing their environment and they're coordinating     
2:12:40     
these kinds of migration migratory movements and um organization into     
2:12:47     
layers and things like that. All right. So that's that's basically development. This is shows the dynamics     
2:12:55     
of primary psyllium ARGC pool expansion. Um this just shows this primary     
2:13:02     
psyllium. It retracts a little bit here. Um it's basically being resorbed and it's also     
2:13:10     
uh then during cell division it's uh you know being resorbed. the cell divides     
2:13:17     
and then you get these new celia coming out. So you have silioenesis which occurs in this part of the cell     
2:13:24     
cycle. So you have a G1 to G0 or G1 G0 which is this where you have the primary     
2:13:31     
psyllium you have the Sphase where this this there is this resorption you have the G2 phase where the uh cellia     
2:13:39     
disappears then you get cell div primary cell division or mitosis and then you of     
2:13:45     
course you get this uh silioenesis as G1 G0 proceeds. So the psyia are     
2:13:53     
retract and expand as part of the cell cycle. And so that's a kind of an important point when you're looking at     
2:13:59     
these pools of progenitor cells. And these uh psyia are important for     
2:14:05     
regulating the size of that pool. So if the psyia there's a defect in the silia or a defect in how they are resorbed and     
2:14:13     
generate then you have reductions in the pool size or um you could also have     
2:14:18     
expansions of the pool size and that could be a different disorder. So this is kind of just showing how these and     
2:14:25     
these are uh genetically controlled genetically mediated. So it's not like     
2:14:31     
um you know we have these I wouldn't say repeatable results but we have this sort     
2:14:37     
of tendency towards these things. Um then then we have in C sensory primary     
2:14:43     
psyllium radial migration of neurons. So this is the role of psyllium in migrating neurons instead of regulating     
2:14:49     
say pool size of progenitors. This is when they're moving to their positions and cortex and interacting with each     
2:14:55     
other. So they're actually picking up signals from neighboring cells. They're     
2:15:01     
guiding their axons. They're guiding their position in the cortex and they're finding a place to     
2:15:08     
settle basically and how to interact with their neighboring cells. And so     
2:15:14     
this is uh whereium are playing an important role in organi organizing that     
2:15:19     
architecture. So interestingly when you have defects in the psyllium you have defects in the pool size of the     
2:15:26     
progenitors but the architecture remains largely intact. So it's just a smaller     
2:15:32     
cort uh cortical layer with essentially the same architecture. So you know I     
2:15:39     
don't know I didn't you know I haven't we haven't read the whole paper but um     
2:15:45     
the sili the silial dis uh the cilia disorders have maybe a     
2:15:51     
lesser effect on the organization of the architecture than they do on the on pool     
2:15:56     
expansion dynamics. Um, but yeah, that's that's basically what they're getting at     
2:16:02     
here in the paper and they go through a lot more detail in terms of specific lossi and u different mutations and     
2:16:10     
things like that and then um just talking about how signaling pathways are     
2:16:16     
coordinated by the psyia and how dysfunction can have profound consequences     
2:16:21     
and so this this is a list of MCPH genes and their cellular function. So you know     
2:16:27     
we know that they're involved these um these loi are involved in different     
2:16:33     
cellular processes and so if we see that there's a mutation in one or more we     
2:16:38     
know that there's maybe some you know maybe they have a function in common and we can isolate those mutations to those     
2:16:45     
specific functions. Okay, so that's that's a good paper. Um,     
2:16:51     
you know, it's just kind of thinking about um some of the things that are going on in the brain and some of these     
2:16:59     
disorders. Um, and it links back to that talk that Morgan posted before about um     
2:17:06     
a general more general model of this stuff. Sorry, I didn't realize my camera's on.     
2:17:13     
Okay. Um, uh, yeah. Yeah. the, you know, really really     
2:17:21     
fascinating one, right? Because um I mean it gets I I I love I love the     
2:17:31     
infographics on those. I I I try to     
2:17:36     
point out to people that like, you know, when when I started     
2:17:44     
um grad school, you know, it was     
2:17:51     
mostly histologology work around schizophrenia. Yeah. Right. and and it was like post-mortem     
2:18:00     
um slices and and things like that. And     
2:18:09     
you you know it was it was and it was very     
2:18:15     
I don't know the best way to say it. It was very pre- internet in that like um     
2:18:23     
there wasn't a lot of digitization. There wasn't a lot of um     
2:18:34     
they weren't thinking about biological scale the way that to some degree I     
2:18:41     
think we've benefited from the internet scale. Yeah. is that that     
2:18:50     
you know we're obviously talking about the one of the most complex artifacts of the     
2:18:57     
universe and and you know so often in this     
2:19:04     
hisystological work they would go in they'd be like they would go in with a     
2:19:10     
theory which I could sort of get why but there'd be some something like you     
2:19:18     
cell body size or um connections or something like that.     
2:19:25     
And this is this is again getting back to this like lack of automation, lack of     
2:19:32     
computer vision slashcomputer intelligence.     
2:19:37     
Yeah. Um this hisystological work was done     
2:19:44     
manually. Right. So you know these these poor grad     
2:19:51     
students posttos that had to do this work you know like like     
2:20:00     
understanding that this is painstaking skilled labor.     
2:20:07     
Yeah. Right. Um so to come away with     
2:20:14     
histological analysis that shows that cell bodies of a particular cell type     
2:20:21     
are smaller in schizophrenia versus controls. Um you know was like potentially     
2:20:29     
somebody's like dissertation work you know. Yeah.     
2:20:34     
Right. And and yet at the same time Right.     
2:20:43     
So, so, so that would seem remarkable and it would seem significant.     
2:20:49     
The problem being that what time has shown is that basically anything you     
2:20:56     
choose to go in and look at, there's differences, right? Yeah. There are always     
2:21:03     
differences. It's just what do they mean? You have to interpret them, you know? So, one you don't understand     
2:21:10     
the the normative variability, right? And two, it's just like, yeah, there are     
2:21:17     
all these differences, but unless you actually looking for like 500,000     
2:21:24     
different metrics of connectivity, receptor type, receptor density,     
2:21:31     
um, cell body size, you know, like like every cell has like a thousand     
2:21:39     
features. Yeah. And and there are 3,000 cell     
2:21:45     
types, you know, and in and in any particular area of     
2:21:50     
tissue like, you know, like there's some variable number of those cell types that     
2:21:56     
are potentially ordered or disordered or connected together or not connected, you     
2:22:03     
know, like like so you got this incredible variability across     
2:22:09     
heterogeneity. in terms of you know the cider architecture.     
2:22:14     
Yeah. And and you know so when you see something like that like it's it's I     
2:22:22     
mean that paper it's such a great testament to the just like     
2:22:31     
you know and on the one hand they're kind of focused in on something because they're talking about primary school.     
2:22:37     
Right. Right. you know, and and but what what I love about it is that it     
2:22:44     
kind of it exposes the kind of the complexity in which     
2:22:51     
that that feature can be, you know, like like the many roles it plays like what     
2:22:58     
where it's coming from, what doesn't influence all the other     
2:23:03     
factors that come in in development, you know, and and     
2:23:10     
um and it's like just the kind of thing where it's just like     
2:23:15     
uh we need so much more data at such a     
2:23:21     
such a finer kind of resolution and like all of it needs like you know     
2:23:29     
massive supercaled uh automation because like like humans     
2:23:35     
can't take in all this you know. Yeah. And so it's it's the kind of thing where it's just like, you know, this is why I     
2:23:44     
think I I love that the soften team has gone     
2:23:49     
from real time f I mean well part of part of their commercialization is     
2:23:55     
yes you know us from real time fMRI which is sexy but kind of useless. Um     
2:24:03     
uh but we're we we've got a startup, we've     
2:24:10     
raised money and we're doing medical reasoning training     
2:24:17     
and and I think their clinical product will be medic medical reasoning and     
2:24:28     
pathology. Right. Right. have pathology as as     
2:24:35     
self-supervised computational hisystologology. Right.     
2:24:40     
Right. And and what I'm trying to get at there is like to to link it back is just like     
2:24:50     
how do you make computer vision not just measuring cell size     
2:24:59     
but like literally taking in the whole visual input,     
2:25:05     
right? and and you know so like on one hand you     
2:25:11     
want a David Maher you know     
2:25:17     
computational building blocks of like you you know you find you find the the     
2:25:24     
simplest geometries for everything. you know, you build up     
2:25:31     
um uh something. But like again, like these self-supervised     
2:25:38     
techniques like their internals are not that, right?     
2:25:44     
Yeah. You know, and but but what you are training you're training them on tissue     
2:25:50     
slices, right? So,     
2:25:56     
um, but that that that that being like, you know, we want we want eyes     
2:26:02     
we're we're fine-tuning or we're we're doing end to end training     
2:26:08     
of eyes for tissue. Yeah. Right. like like they look at tissue and     
2:26:16     
they see they they can measure anything and they can you know they can both see the     
2:26:22     
complexity as well as take it apart. Yeah. And and like like Yeah. like that will     
2:26:31     
be um yeah that that that that's that's what I     
2:26:37     
want to learn from from the soften team is like how how to do that,     
2:26:46     
you know, and I kind of I kind of like the fact that they're not 100% they're     
2:26:53     
not real they're certainly not brain scientists, right? you know, it's just like like no, no,     
2:27:01     
no, no. Like let's not, you know, like like our our inclination     
2:27:08     
is going to be like to have fully interpretable models at     
2:27:13     
this point. Yeah. and and like like I think you gain     
2:27:18     
from actually following the kind of     
2:27:23     
tech path of make the end to end models     
2:27:29     
do something. Yeah. And see see what they've learned.     
2:27:35     
Yeah. what you know like like you'll get some achievements and then like like there'll     
2:27:41     
be interesting things in the weights. Yeah. Well, that's good stuff. So, um I     
2:27:48     
wanted to go over before we go a couple things from the chat. I know Jesse had an update, but like he didn't couldn't     
2:27:55     
speak on the Yeah. Uh so, let's see. Sorry, I was in and out for a while. My only major update is     
2:28:02     
a lot of job pro work continuing indigenous in the year ahead. Also data     
2:28:07     
direction and data plus times direction and SCT which is society tech and ethics     
2:28:14     
and technology discussion series in the works as well. Have a lot that needs to be published or put on YouTube. Yes,     
2:28:20     
let's please get a um let's let's get uh some progress on that. So, right. Yeah,     
2:28:26     
thank you Morgan for the insights and uh you know, maybe we'll follow up on some of this stuff. Uh     
2:28:32     
again, we have the um you know, the transcript available on this uh meeting,     
2:28:39     
so we'll go through and look at that. For sure. For sure. And and yeah, I I I     
2:28:47     
haven't forgotten about things in conversational psychiatry. Yeah. Yeah, that would be like interesting to to     
2:28:55     
talk about. Next week we're doing the um um     
2:29:01     
we're doing the new Tom Griffith paper for reading group um     
2:29:09     
in next week. Okay. Um I I I I don't     
2:29:16     
um I I'll I'll post it in the um     
2:29:26     
anyway he's the computational cog lab. Yeah. Yeah. At Princeton and and I think it would be     
2:29:34     
um you know interesting to look at that as well as the the papers that uh for for     
2:29:44     
comps like com psychiatry that I talk about.     
2:29:49     
All right. All right. Thanks. Okay. See you later. Take care. Take care. Bye.     
2:29:55     
See you. Bye.     
