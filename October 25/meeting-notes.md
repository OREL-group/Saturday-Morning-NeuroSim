## Meeting Recording

[YouTube link](https://youtu.be/9I2bSfWc6nw?si=xRs2wU5-A-5mFn1t)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115436915878042975)

## NOTES
Review of NeuroAI — continuation of the Levin program.

GRNs —> Eichenbaum-Tolman machines. Turing machines to algorithm (Restricted Boltzmann Machine).

software engineering — part of a toolset.

Levin categories of learning without nervous system.


Is reservoir computing (should be “Physical Computing” and Ising models) Neuromorphic computing (a la Carver Mead).

* biology and physics are embedded in each other.

testing code should be separate Physical processes — biological processes.

inference testing. ML-like processes from physical systems. Tightening up language, manage processes.

focus on failure modes. What input is unexpected plasticity, growth, evolution, biology? Framework model.


Use models to create code for other models. Can coding agents help us?

Claude code anonymous — SF group.

code implements physics, ML.

vibe code CUDA algorithms? Good for an initial start — subscription models.


Multi-agent software development. Think much more macro than mechanism. Best practices — how many specialists do you need (at least three).

(x,y,z) vs. homeostasis. Critical steps in enshittification.

AI floor @ tower. AI economist is similar to open-source sustainability (very human problem with technology).

well-financed, well-connected groups.


San Francisco —> CogSci reading group —> DARPA L2M project. Lifelong Learning Machines (perspective article).

accumulation of learned tasks, catastrophic forgetting.

does Biology suggest new mechanisms in Ai research? Sleep-Wake cycle to NN training.

drowning in coverage of this, applying for science.

Neuro degree, molecular biology-oriented. Medical tech companies focused on the brain.

Shell scripting —> remix. Super NeuroAI — focused group @ Google (proactively modular).

Eric Raymond — UNIX philosophy of code (shell scripting is “good coding”.

keep software modular, not monolithic.


Neural Networks — neural understanding — what’s the next model?

continual learning. 

*”cure for cancer” — Ai Hype (mystery). 

NeuroTechX for GSoC 2026 (projects), AI agents for science meeting.

Sarrah should present here for a subgroup of Ai researchers.

aligned with what’s going on @ the tower.

role for technology in human flourishing.


Alexander Shaw — speaker for ActInf livestream.

Computational Psychiatry — efficient ways of doing variable selection.

* sustainability in silicon (good eco problem).


## TRANSCRIPT
Transcript   
   
   
Search in video   
0:00   
There you are. Great.   
0:06   
That's great. So, welcome. Um, so yeah, this week, uh, we had a divor   
0:14   
meeting. um Susan and myself and we talked or   
0:19   
went through the mathematics of tensegrity and then we had a couple more papers where we talked about uh bio like   
0:27   
bioysics of cells and linking that with molecular data. So   
0:33   
it was interesting you can go through the whole meeting on the YouTube channel. Um and then   
0:41   
uh we I I got a well in Slack Sara last night was highlighting her time at um   
0:49   
the deserter summit. So this is being held in Germany this year and you know   
0:55   
it's basically for people to go and talk about different projects. Sara was   
1:03   
uh tapped to talk about the open source sustainability project. Let me go over   
1:08   
that. So if you have access to the Slack, you can see this as well. Um so   
1:15   
this is the G-Sh. Uh this is sort of the administrator of the Gox Summit. Um and you know they're   
1:23   
on the blue shirts and they're kind of going through the agenda here. So they have a nice little get together. Um they   
1:31   
give talks, whatnot. This is a picture of a cake with the summer code logo on   
1:37   
it. And then this is the I guess they proposed to give talks on things and   
1:44   
Sara has her open source sustainability talk. Uh she wanted to talk about   
1:50   
metrics, human variables and more. So that uh I don't know how that went. I   
1:55   
guess that's going on this morning maybe. So we'll see. Um, but that's good, you know, that's good that we're   
2:02   
getting the word out about the project. I'm going to also talk about open source sustainability   
2:08   
at the uh active inference symposium in a couple weeks. Um, I'm preparing some   
2:14   
slides for that where uh talking about the different metrics, the different   
2:19   
approaches and then ultimately you know how that fits into the larger   
2:25   
problem. So this is the post here from the Slack.   
2:33   
All right. So um that's great. Um congratulations Assara for that and um   
2:41   
yeah it's great we can get the word out about the project. Uh Morgan, did you have any updates or   
2:48   
do you want to talk about your week? Well, yeah. Yeah, absolutely. Um, but   
2:56   
just just following up on that, um, I'd love to to actually give her a chance to   
3:04   
present that here to to   
3:09   
um, you know, it it kind of that project to me that project speaks to   
3:17   
a a very um, well, it speaks to a subgroup of of AI   
3:23   
researchers. that I think are are well represented at the tower.   
3:28   
Oh, okay. Because, you know, because that is very   
3:34   
it's very aligned with a bunch of um   
3:39   
it's very aligned with both values of the tower as well as um   
3:47   
kind of like their own goals with their work. I mean in terms of you know um   
3:57   
you know not that like conscious tech collective is the best uh example of   
4:02   
alignment with open source sustainability but but in that sense   
4:07   
like like you know is there a role for tech in   
4:14   
human flourishing or you know in in uh   
4:20   
no posit positive are positive contributions possible? Um   
4:27   
um and um you know again I I bring this up every   
4:34   
time we kind of talk about this project but you know again it seems somewhat like the um the Salesforce AI research   
4:43   
is AI economist project in the sense of like trying trying to   
4:48   
understand a a very   
4:55   
very human problem, right? But but but with technology,   
5:01   
right? In the sense that like um   
5:07   
yeah, s sustainability is is is already just an interesting thing for um   
5:17   
for a simulation, right? Yeah. Or like, you know, to me it's it's   
5:23   
it's like it's   
5:29   
Yeah. It's a good it's good ecological problem, right? Um   
5:35   
and um anyway, so like please help me help me   
5:41   
make that happen in the sense that like um uh because I would I mean I was thinking   
5:49   
so one of the things I was thinking about this week was also just um planning ahead to   
5:57   
uh you know like what potentially What   
6:03   
neuroche x projects would we be proposing for g next summer?   
6:09   
Yeah, you know and and um yeah. So, okay. Um so, this this week   
6:19   
had a couple um uh uh   
6:25   
couple things in particular. Um so   
6:32   
um there was a Stanford um did a AI   
6:38   
agents for science okay meeting and um   
6:45   
you know this is this is one of those areas where I think you know   
6:51   
I don't think we're lacking on kind of coverage of AI agents in the world. If   
6:58   
anything, we're kind of drowning in it. Yeah. Um um   
7:04   
you know, so I mean anyway, it it's it's   
7:09   
nice to see   
7:14   
what um it's nice to see occasionally that some   
7:21   
people are trying to apply these for science. Yeah. You know, because in general it's It's   
7:28   
again I don't know if this is like um just my   
7:34   
personal you know but you know we're surrounded by people   
7:39   
who like everybody's got an AI agent startup. Yeah.   
7:44   
Right. like like yeah. Um and uh I I had a I had a student um well   
7:54   
she she she just finished she was the president of the um the UCL neuroscience   
8:00   
society and um she moved to San Francisco to to join an accelerator   
8:08   
program. So like this is this is very very uh this is already a very San   
8:14   
Francisco story, right? And uh and she's   
8:20   
you know it's like she's got a she's got a master's in neuroscience   
8:25   
um from a very molecular program spent time in a regenerative medicine lab.   
8:30   
Right? So, so she comes to this accelerator program and she's like, "Okay, you know, this is my my skill   
8:38   
set. Um, you know, like accelerate me, right?" Like, you know,   
8:44   
and they're like, "What do you think about B2B insurance sales?"   
8:54   
And she's like, "I don't know.   
9:01   
So, um the the the you know and I did I mean we   
9:07   
did have a a good conversation about you know like   
9:13   
h how how large is the neuroch field right like like is there a neuroch field   
9:20   
or is there kind of like you know a small number of medtech companies that   
9:26   
are kind of focused on the brain right like like Anyway,   
9:31   
it was it was funny talking with her about, you know, the realities of of the   
9:37   
tech industry in terms of, you know, where   
9:43   
they want to see people getting to work. And um   
9:50   
uh anyway, I think you know some of these these stories though in terms of   
9:55   
the the AI agents for science because it's it's very related I think to some   
10:01   
one of the other meetings that was this week which was the um the Emily Bender   
10:07   
um you know AI hype uh   
10:12   
yeah um Mystery. I can't I can't remember their mystery   
10:19   
science theater. Excuse me. Sorry.   
10:24   
Um uh mystery AI hype theater or something   
10:30   
like that. Right. Yeah. Yeah. Um but the the story that like AI agents   
10:37   
have have come up with a cure for cancer. Right. Right.   
10:43   
And And it's one of these it's one of these things that unfortunately   
10:50   
yeah it fits a lot of um   
10:56   
the main critiques that she and um I forget the   
11:02   
director of research that that accompanies her on those um on those   
11:08   
live streams, right? But from from their their institute. Yeah. Yeah.   
11:14   
um D A I R but um uh   
11:22   
yeah and and it's one of these things where you know that comes up at like   
11:30   
if we do these foresight meetings which again the foresight meetings are great   
11:38   
our our ability to get something done in a in a weekend   
11:45   
in a kind of like hackathon format or something like that. Like super   
11:50   
dependent on your access to data and access to compute.   
11:56   
I in in terms of you know holding together something that um   
12:05   
that is a proof of concept that would be a good narrative for you. And this is   
12:13   
this is important to get funding, right? Because again like like so much of these   
12:20   
these stories are are really hyping, you know, yes, this is, you know, this is   
12:27   
going to create new new insights, new science, new, you   
12:34   
know, um uh anyway, I I I I've talked about this   
12:41   
too long. I think we know the critique, but but definitely good to to you know,   
12:47   
I think I've said this before, you know, we we should always give ourselves a good dose of of um mystery AI hype   
12:56   
theater. Oh, yeah. um inoculation and and um   
13:06   
this some somewhat relates to the the San Francisco Coxai reading group that   
13:11   
we had this week. And the paper was the um was the   
13:19   
perspective article that was somewhat a   
13:26   
it was basically a repurposed DARPA report from the lifelong learning   
13:32   
machines um you know L2M   
13:38   
uh DARPA project right so papers the biological underpinning   
13:44   
of lifelong learning machines and it was an you know it's an   
13:50   
interesting paper or it's an interesting   
13:57   
you know I think they call it a perspective because it's it's not it's not uh   
14:06   
comprehensive or in-depth enough to to call it a review right um but this is it's a It's a it's a   
14:14   
really nice um collection of both   
14:20   
biological mechanisms that uh are understood as   
14:29   
playing a role in continual learning, right? So the the the AI field of   
14:35   
continual learning um uh um you know what are what are the   
14:44   
you know what are the problems of continual learning like some something   
14:50   
like the um you know the problem of catastrophic forgetting right   
14:56   
and then what are the biological mechanisms by which   
15:02   
this kind of um this kind of problem is is mitigated or is um   
15:11   
um has a a you know puditive role in in   
15:18   
uh um stalving right so so let's say   
15:24   
catastrophic forgetting that you might you might put forward you know neresenesis   
15:30   
as at least one way to um to expand the   
15:36   
system um so that you've got this the storage capacity to to handle this this   
15:44   
accumulation of new of um of learned tasks, right? Anyway,   
15:53   
you know, and so they kind of go over some of the arguments around neuromorphic computing in terms of, you   
15:59   
know, certainly energy and and things like that. But um   
16:05   
but it's mostly focused on these kinds of um continual learning tasks u or you know   
16:14   
again the the wellestablished area of of AI research   
16:22   
that was around that but but again trying to take this you know does   
16:29   
biology have anything to suggest for um   
16:36   
um new mechanisms in AI research, right? So   
16:42   
it's like people who you know um uh people who've proposed things like you   
16:50   
know can we bring a sleepwake cycle to neural network training right and you   
16:59   
know obviously not in the literal sense or but you know can can can something   
17:08   
like a a sleepwake cycle um um allow for   
17:15   
you know um additional generalization, additional   
17:20   
um um you know that that would contribute to   
17:27   
some one one of these one of these um problems that you have in continual   
17:32   
learning, right? But a lot of the and and of course, you   
17:37   
know, one of the other reasons we were reading it is that Josh Bongard and Michael Leer on this, you know, as as um   
17:46   
uh in this case, I think it's it was I mean, they have they have both of them   
17:52   
and they you know, this is um an area though that was perhaps a bit more Josh   
17:58   
Bongard than Michael Leaven, although they still had anthrobots in there. Um, uh, I'm not not 100% sure that that   
18:09   
transition made it made sense, but but the the, you know, um,   
18:16   
uh, Josh Bongard's evolutionary robotics course covers,   
18:21   
you know, like like it's evolutionary robotics, so it's it's non-traditional   
18:27   
robotics, right? So um he does he does cover some of these problems in a kind   
18:34   
of um yeah I mean what what might be part of a continual learning um uh   
18:44   
sections of his of his course and um anyway good discussion around that.   
18:51   
Um, next next meeting we're going to be covering the um what is intelligence   
18:56   
book by um who's that Google d um   
19:01   
it's um blaze um I forget the guy's name um   
19:13   
oh yeah blazing arcus yeah agara yakus yeah Yeah. Yeah.   
19:20   
Um, so he he's definitely he's definitely on a tour. Um, because he's   
19:28   
he's doing a lot of podcasts, a lot of he he was just on machine learning   
19:33   
street talk. Um, and you know, I think I think it it'   
19:41   
come up that um, uh, you know, Blake Richards   
19:47   
like like a couple weeks ago, I saw a thing that Blake Richards is joining Google   
19:53   
and and it it's it's Blaz's team at   
19:58   
Google that that he's joining, right? So they're they're they're putting together   
20:03   
and he he talked about this a little bit with machine learning street talk um you know it's like it's a super   
20:12   
neuroai focused group you know u as you   
20:17   
could imagine with people like Blake Trait. So, I mean, that's that's kind of what I wanted to get around to talking   
20:24   
about, though, was just um was was neuroi and and you know, the   
20:31   
ho how much how much does does, you know, the actual um   
20:41   
you know, original metaphor of of neural networks actually depend   
20:47   
on, you know, a a neural all understanding and and you know um I I I I understand   
20:57   
the appeal I and and things but um   
21:02   
yeah that that there's this this hunger for you know what's the next new what's   
21:09   
the next model right so it's like we've been in the the decade of Transformers   
21:17   
um yeah like uh I think people are are   
21:22   
searching around. Um so that was that was the main um I'm still trying to   
21:31   
um still trying to get a um   
21:37   
you know can happy to talk about neuro imaging at some point. Um   
21:44   
and yeah, we've just got some we got some interesting um things going on at   
21:50   
Neuroch X and we'll be speaking to the students in November. Oh yeah. Um yeah,   
21:57   
just starting to think about society for neuroscience and um you know uh these   
22:04   
are things that are kind of in my backyard in the sense of like it's at least within the state of California.   
22:11   
Um there's there's um and and there's some big meetings before that too because   
22:18   
like everybody flies in for society for neuroscience, right? So so there's IE   
22:24   
EMs um has a um a neuroengineering   
22:30   
conference that's scheduled right before um SFN.   
22:36   
Um and yeah, just trying to think about some things trying to think about some   
22:42   
things that are um uh that would be good in terms of you know kind of growing the   
22:50   
um uh marketing for for Neurotech X. But um   
22:55   
you know and getting getting some visibility for for for the group as well   
23:01   
as like u you know by by getting some visibility I can connect more student   
23:08   
groups together you know anyway   
23:14   
I've I've got a few thoughts about or yeah I was wondering if you've talked to   
23:19   
um uh Alexander Shaw   
23:24   
uh It's exit   
23:30   
just just well just just uh um   
23:36   
thinking about the um active inference um   
23:42   
symposium or what are they calling it? Symposium. Yeah. Um, so, you know,   
23:52   
wanted to wanted to check in about about that. And, um, he he's he's someone who   
23:59   
I see posting. I mean, he he's definitely a computational psychiatry guy.   
24:05   
Excuse me. But, um, uh, been posting a lot of, uh,   
24:14   
active inference examples. um active inference comput computational   
24:20   
active inference examples, you know, in the sense of, you know, nice little toy   
24:26   
examples that demonstrate, you know, some some new or um   
24:34   
um you know, efficient way of doing variable selection or some something   
24:40   
like that. someone someone who who strikes me a lot like Ryan Smith um as as the a person   
24:50   
who kind of like focuses on pedagogy and and um you know computational tutorials   
25:00   
here I'll post it in the computational psychiatry Slack because he's um   
25:06   
you get his um as well as maybe his um   
25:11   
his GitHub Um anyway, but those those are the things.   
25:18   
Yeah, it's nice. I just see that the um the   
25:23   
person who um um so the president of   
25:32   
the UCL neuroscience um joined the joined the tower as a neurochlor person.   
25:39   
So she she she to end that story uh she decided to drop out of that accelerator program,   
25:47   
you know, and she she would prefer to do something other than what they were   
25:53   
suggesting. I I I think she's decided to choose um   
25:58   
slow slowing down and and doing things that feed her soul.   
26:04   
I mean, it it was it was nice coming off the back of the um   
26:09   
the kind of like the Brett Kagan, you know, go Wang. I'm still not sure how to   
26:15   
say his name, but you know, the like GE Wang paper that was the that was also   
26:22   
kind of like a review of NeuroAI. Um   
26:31   
Yeah. Yeah. Um there was definitely some interesting and and the the the the   
26:40   
area in which I wish we'd focused or um   
26:45   
seemed to me the the the best continuation of um   
26:54   
kind of like the the the Levan program if we can call it. um is the uh have you   
27:01   
seen his papers on um um it's like regulatory   
27:09   
something machines you know it's basically it's basically gene regulatory networks but he's trying to turn them   
27:16   
into like you know um   
27:24   
like what's the um like doesn't somebody do like an icon bomb Tolman machine   
27:31   
like you know what I mean? you know that like like that that that kind of um um I'm   
27:39   
gonna take I'm gonna take I'm gonna take this you know this concept from biology   
27:45   
and I'm going to turn it into a kind of touring machine you know I'm going to turn it into an algorithmic process um   
27:52   
more like a boltzman I think bolts m machine was the first right   
27:58   
um um wasn't wasn't that like a very early neural network bolts in the   
28:04   
machine or restricted restricted bolts in the machine. Um   
28:09   
um anyway that um uh I thought that in particular was one   
28:18   
where it was just like hey um   
28:24   
here's here's the system that is you know can demonstrate all these   
28:31   
learning effects. Um again in the kind of 11 sense um or   
28:38   
the you know the the the 11 categories of learning that you can find without nervous systems right   
28:47   
um and u anyway but but yeah wanted to   
28:55   
just say um I'll see if I can find this paper but somebody somebody wrote an   
29:01   
interesting paper that's totally relev relevant to organoid intelligence. Um   
29:06   
talking about um is is reservoir computing neuromorphic computing   
29:14   
that that I I you know I I had a lot of   
29:19   
um as you know I was kind of well aligned with already in terms of like this isn't   
29:25   
this isn't neuromorphic. I think I think I think she actually talks about both reservoir computing and   
29:34   
icing models as as you know like   
29:41   
like they can be you know like the fact that they can be implemented it's it's a   
29:47   
nice essay on like what did Carver me mean by neuromorphic computing you know   
29:53   
what examples do we have and and leading into this discussion of like is reserv   
30:00   
you know if if you get a biological uh uh if you get biology to do reservoir   
30:06   
computing are you you know is that is that biological at all right you know   
30:12   
and yeah um so sorry keep going   
30:21   
well well I mean well I mean I think the point of her paper was like   
30:27   
let let's call this what it's all what it's historically been called which is physical computing.   
30:34   
Yeah. I I I think that was her that was her point was that like like if you   
30:40   
could you know that's what reservoir and and icing models   
30:46   
have been historically used for. What what's interesting is that um   
30:55   
that they can behave like that you can get these MLike processes from physical   
31:02   
systems I think is is is what you know   
31:08   
um her correct um I mean you know again she's she's just like uh I think her biggest thing   
31:16   
was just like this isn't what Carver meant But I but I think it's I think it's   
31:22   
super applicable to this kind of larger art of of levan program which is um   
31:32   
thinking about the language that we use in general and like h how much is the language barrier. Yeah, I'm bummed. I'm   
31:40   
bummed I'm missing the um you know div do divor meeting is like right when I'm   
31:46   
getting my daughter ready for school. So, um, yeah. Yeah. But I I I we'll try   
31:54   
and listen to the this week's recording. Sounded like a great topic.   
32:01   
Yeah. It Well, it's it's another another   
32:09   
thought really interesting um I think it was perspective article, but but was   
32:14   
covering how how biology   
32:20   
you know, over over evolutionary time scales has learned to exploit um   
32:27   
bioysics or like physics, you know, and and and that we we should think we   
32:35   
should think of that as being, you know, much more relevant to their world to the   
32:42   
the cell's world. um you know as opposed to our   
32:49   
macro thing the processes at our scale right   
32:57   
um where we've got a tendency to focus on you know XYZ   
33:03   
and and navigating that um as opposed to manipulating you know   
33:11   
um relevant to both homeostasis is as well as like the scale at which the cells are   
33:17   
operating. Yeah. Anyway, so it sounds sounds like you're covering some cool   
33:23   
stuff there. One one of my great um um failures as a parent was making a   
33:31   
tensity um egg drop challenge device.   
33:38   
And my son my son was so confused. is just like I was like what what are this   
33:44   
is is this this is going to stop the egg from breaking. I was like yeah yeah don't worry like like   
33:52   
and they they threw it off the roof of the school and it was like   
33:57   
like the egg just totally Anyway, sorry that's why I was laughing when you're talking about the drop.   
34:06   
I was thinking of this egg drop that we did at the school where I tried to build a tanky   
34:12   
cushion. Sorry.   
34:27   
Yeah. Yeah. I'm not sure where where my engineering failure came from, but I did   
34:32   
not I did not pull it off. Yeah.   
34:47   
We got to talk last week.   
34:55   
I'm good. How are you? Good. She joined the meet last week, but I   
35:01   
guess the meet got cancelled or something. It wasn't there. So, I spoke to Morgan.   
35:08   
I was I was I was down in Santa Cruz.   
35:21   
Um nothing. I was talking to like that's why I was telling Morgan that I had a week off from college. We had a break   
35:28   
because of an Indian festival. And apart from that, nothing really. I had updated   
35:33   
about the thing where we held a meet like with our juniors where we introduced them to GCO and LFX and other   
35:41   
things. And I remember like one vlog ago I was talking about the whole uh junior   
35:47   
senior presentations thing that we have at college. So that final meet is over as well. Yeah. And I spoke to Sara.   
35:56   
She's gone to Germany and she has her mentor Google summer of code thing   
36:03   
happening over there. So she presented all three projects I guess like mine   
36:09   
that she mentored hers and I guess even Hman chose so that she could compare how   
36:14   
we have done this project over the years. Yeah. But it, you know, like again like   
36:20   
um um you know the the AI floor. Yeah, no   
36:26   
worries. Fiji. Um, uh, the AI floor has a lot of people   
36:34   
some people that I know from Noisebridge, you know, which is the the the old um the venerable um anarchists   
36:43   
hacker space in San Francisco that um was um certainly made, you know,   
36:50   
popularized by Aaron Schwarz. Um and you   
36:55   
know some of those noisebridge AI people are also involved with the gray area   
37:02   
which is a wonderful um you know tech art collective. I mean know like like   
37:12   
yeah create creative ways in which to use technology. Um, and you know, I I'd   
37:19   
been a part of the Conscious Tech Collective, which was a group from another community um, uh, center in San   
37:27   
Francisco called the SF Commons that, um, that again kind of   
37:34   
had a weekly meeting that was focused on, you know, ways in which technology   
37:39   
is could be used for wellness, mental   
37:44   
health, flourishing. you know it was a lot of   
37:50   
like you know um questions like can can technology   
37:56   
actually improve meditation which I I I think is an interesting question you know I mean to which my my almost you   
38:05   
know like my first reaction is going to be like I'm gonna say no and and the   
38:11   
burden is on you to show me why it's it would be the opposite   
38:18   
of um but yeah and and you know and so but I think   
38:26   
there's there's a there's a a larger group that is looking at things that are kind of of that um AI economists   
38:34   
style in terms of um people who are also you   
38:41   
know thinking about e economic modeling especially you know I still think,   
38:50   
you know, I'm again, I'm not one to to chase this kind of stuff in terms of, you know, post AGI   
38:57   
economic models that that make a lot of assumptions that I don't think are um   
39:05   
uh well grounded in history, right? Like like um you know that Yeah. Anyway, but   
39:15   
uh but I like the I like the simulation work around that or at least you know   
39:20   
like um if if again if the the simulation work stays stays well   
39:27   
grounded and stays um um reproducible   
39:32   
and open source then there's potentially some contribution there that that you   
39:37   
know others can build on to. So um I think uh yeah and I and I think the the   
39:46   
discussions I mean I still see interesting discussions around you know   
39:52   
how to manage how to manage um software teams and how to manage software   
39:57   
projects um that that you know are are o only   
40:05   
more relevant in this AGI world of where we're We're all writing software. I I I   
40:11   
I um I was very disappointed. I'll see if I can find this, but um what's that   
40:17   
guy's name? Is it Simon Will? It's like Williamson. I forget. There's something.   
40:26   
You know, you know what I'm talking about. He's like the guy who developed WordPress or something like that, right?   
40:32   
like um he he he had an interesting.   
40:37   
So so again not again not not strictly software sustainability but this this   
40:44   
you know how does how do coding agents um can can coding agents actually uh   
40:53   
help us with code? Right. Um   
40:59   
um he had a   
41:04   
he had a talk that he gave at um a group   
41:11   
called Yeah. Claude Code Anonymous. um is this uh   
41:20   
you know and and so this is a group that's also kind of franchised like like   
41:25   
they started in San Francisco but now they have chapters in in other in other cities and it's it's you know people   
41:32   
meeting together to be like like can you know what are the issues around the code   
41:38   
that is generated by agents um anyway I I'll try and find the the particular   
41:46   
talk. Um, but I I um yeah, and I don't   
41:52   
know if it's really of interest, but I I tried to uh vibe code something for the   
41:58   
first time and because I I I wanted to see I wanted to see, you know, like this   
42:03   
is literally the first time I've used an LLM   
42:08   
and and it for coding for coding and and you know and it's uh I mean It speaks to   
42:17   
my um um ignorance, right? That that I I I'm sure   
42:25   
I've got to do more on the prompt engineering. I mean, just in terms of my   
42:30   
own education, right, um but like like it it was definitely generating things   
42:38   
that looked very uh that looked ready. um but in details was was sometimes   
42:46   
causing more problems than a a and one of the things that it generated was um   
42:53   
so Claude was not only giving me code but was also telling me how to use it,   
42:59   
right? And and in this case it was actually   
43:04   
telling me the opposite of of the the   
43:09   
reality. Yes. Yeah. No, no, I will use it again. So,   
43:15   
so um this is the um this is what I'm trying to   
43:22   
this is the book by um uh Russ Pauldra.   
43:30   
So, um   
43:35   
so this is the the guy who's he's he's now the chair of psychology at Stanford.   
43:43   
and is somebody who I can remember when he was just a um you know early career   
43:49   
researcher u and he   
43:55   
one of his posttos is now a very senior person at anthropic um so he he's   
44:03   
definitely trying in this book to talk about um   
44:10   
how to to do this as well as um uh let   
44:16   
me see if I can remember Chris Rauus's. Anyway, the the the the   
44:24   
leads. Yeah. Okay.   
44:30   
Um Um Yeah. So, I I I I want I want to   
44:35   
actually start. I mean this was this was great because I saw that that CL claude   
44:40   
code anonymous exists that there is a group that's meeting in San Francisco   
44:46   
and I would love to to see you know like like focus on science   
44:52   
examples where um you know again the code is implementing   
44:59   
physics or you know   
45:04   
ML for you know very specific pipelines   
45:10   
right and um and there's um there's also another   
45:16   
senior guy at Nvidia who's um who's talked about and he he's a former   
45:23   
kitwear guy so this the people who develop VTK right um and   
45:31   
you know can we vibe code CUDA algorithms, right? And and I mean, you   
45:38   
know, it's just like like Yeah. And and I I think one of the   
45:44   
things is like yes, absolutely you could as long as you've got good test harnesses for like like these are my   
45:53   
input data sets. this is this is what I know I wanna you know what I need to get   
45:58   
and and um and like so as long as I've   
46:04   
got uh I've got a good place to test that CUDA code um and and I can be   
46:11   
iterating correctly in the right direction like this should work anyway   
46:16   
um the um I I'll post a couple links to some some articles in the in the chat   
46:24   
But I'd love to follow up on this because u yeah I I I think they should   
46:29   
be something that is helping us right I   
46:34   
mean in the sense that like autocorrect or you know things. Yeah. Go ahead. So   
46:40   
like oh yeah I feel like LLMs are actually good when you want to code like if you write a good enough prompt   
46:47   
actually you can use the LLM for the prompt itself and then give the same prompt to some other LLM and then   
46:53   
generate the code that you need but like it's good for the initial start but then if you are continuing a code base like   
47:00   
you're like not a code base but if you're continuing adding some code or something you're like you want to   
47:06   
improve something in a huge code base then it does not help because it does know anything about the code base and   
47:11   
you cannot give a lot of those files to a free version of any LLM and I mean I don't know we don't like I don't have   
47:18   
any subscriptions of any of the LLM. So if I use any of them that there just a free models. So I don't think the free   
47:25   
models allow you to uh put that much data in them. So if you like if you you   
47:30   
can put to some extent and then it's just like like free limit over and then   
47:36   
you can't use it more. So that's what like I feel lums are good to generate code for like the first few things and   
47:43   
then errors of course but then I feel yeah then you will get stuck eventually unless you are making everything using   
47:50   
that alism so like that's my perspective   
47:55   
no no for sure I mean I I love your perspective thank you because um yeah I   
48:02   
I am certainly you know again in my ignorance I am still using free models   
48:08   
because I I you know I'm not ready to commit. Um, but I I was talking about this AI   
48:15   
agents for science meeting that was this week and and it was just very obvious   
48:22   
that the groups that were doing or the groups that were able to to get projects   
48:30   
together were extremely well financed, extremely well connected like like have   
48:37   
unlimited compute a access to, you know, absolutely paid   
48:43   
model, you know, like like models I don't and and um but but also that experience   
48:51   
that you're talking about in terms of of you know Yeah. like should I be using   
48:57   
models to create my prompts for other models? Yeah. Yeah. Yeah. Anyway, that's that's   
49:03   
all. Yeah, I learned it from a friend like he was like he was like he just wrote like an   
49:10   
initial prompt. Okay, I want this, I want this. And then at the end of that prompt, he said, "Okay, generate a prompt for me that I would give you or   
49:17   
some other LLM to explain what I want." And then the LLM actually gave a very good prompt   
49:22   
specifying every single thing. Sometimes when we're like in a hurry, we just don't type a lot like so we can just   
49:27   
type the basic things, get a prompt and then copy paste that and give it to the same GPT or like some other model like   
49:33   
Lord Grock or something. Smart idea. Yeah. Yeah. Yeah. I mean I I was already or   
49:41   
certainly you know my my initial impression was that like I was getting something that was a lot better than me.   
49:51   
I would have been searching for the right programming terms, frame, you know, kind of like framework, model,   
49:59   
etc. and like like I could get going a lot faster,   
50:06   
but then you of course you always get into the like I've got to know the details and know how it all works   
50:12   
together and and you know so there there   
50:18   
yeah I I I'm I'm an you know I'm a newcomer. um if if there's um any good   
50:26   
resources you would suggest, I I would appreciate them and I would like to gather more. So, please tell me if if   
50:33   
you have a chance to look at um at Russ's book. Um I'd be curious to see   
50:39   
what what you think in terms of um like uh uh yeah, h how helpful is it for   
50:46   
for someone like yourself, more experienced? But I've got a Julia link of that book or something in the   
50:52   
chat. Yeah. Yeah. Okay. So, this is the book better code better science.   
50:57   
This is from Russ Puldra's group. And what's interesting about this book is that it is very much in the spirit of a   
51:04   
truly open-source book. So, they have uh first of all CCBYNC license. So, this is   
51:10   
Creative Commons attribution non-commercial. So, you're not able to sell the book to anyone. You also need   
51:17   
to attribute the book standard academic uh values. And then of course they have   
51:24   
a GitHub repository which is here. This GitHub repository is where people   
51:30   
can go and contribute to chapters, contribute content. It looks like there   
51:36   
are two contributors already. Uh Giorgio Arara and Yaroslav Henko.   
51:43   
So I don't know what the standards are. I don't know if you can contribute but this is the way that an open source book   
51:50   
should be um you know the authors provide the framework and then people can update it as they would like.   
52:00   
So this is the uh the book there's the introduction   
52:07   
which ten so if you'd like to contribute this book   
52:12   
is meant to be a living open source document with the source available online at podra pract better code better   
52:19   
science if you find any errors in the book or want to make a suggestion of how to improve it please open an issue on   
52:25   
the GitHub site even better submit a pull request with your suggested changes   
52:30   
So there's a contributor's guide and if you're interested you can go there. So the introduction talks about um a number   
52:38   
of principles that try to help us with you know developing good reproducible   
52:46   
scientific software. And so they get into this uh first part why poor   
52:52   
software engineering is a threat to science. So they talk very much about um   
52:57   
using software research software engineering techniques as sort of a standard for science and scientific   
53:06   
uh software development. Um you know there's an expectation now I   
53:12   
think that the code be more professional than what we usually do especially in small research groups where we are   
53:20   
producing software maybe for a very small number of people and then you know the production values are likewise   
53:29   
um it also points to the software engineering body of knowledge or sweed   
53:34   
in 2004 and this is similar to the project manager management uh body of   
53:39   
knowledge and where you have basic information about how to do software   
53:45   
engineering um in a in a book where you can look up things. Uh so there are a set of standards that are published   
53:52   
every so often. We're on version 4 right now and they're comparing here version three which was released in 2014 with   
53:59   
version 4 which was released in 2024. And so you can see that there are a lot   
54:04   
of like different topics, different standards, different specs that you can follow.   
54:11   
Um they've integrated agile and devops into this uh guide into version 4. And a   
54:19   
couple of you know they they what they do with this is they continually revise it. They add in newly relevant things   
54:26   
and they lose old older ideas. And so uh software engineering, operations and   
54:32   
software security are also sort of knowledge areas that are now newly   
54:37   
important as they've become mature. And so this gives like if you're a   
54:43   
practicing scientist or even if you are computational scientist, it gives you uh   
54:49   
guidelines for project management for software development. So this is a   
54:55   
social media post from Russ Pauldra. He asks, "For my colleagues who regularly write code in the course of their   
55:00   
scientific research, how much formal training, if any, have you had in software engineering practices?" And   
55:07   
twothirds of the people there say no, they had no training. Um another fourth   
55:14   
say that they had some training which consists of one to two classes and then 7% had extensive training which is not a   
55:22   
lot of people to sort of uh meet the expectations of the modern software   
55:27   
ecosystem. So another thing they highlight here is the error rate for people with training and people without   
55:34   
training. So they say if professional coders make errors at a rate of 1 to two errors per   
55:40   
100 lines seems very likely that the error rate of amateur coders writing software for their research would be   
55:47   
substantially higher. So in other words if you don't have training you not only   
55:52   
can't meet the expectations and standards of modern software production   
55:57   
but you also make more errors in terms of bugs or other things. So it's   
56:03   
important to get this kind of training or to have people who are professionally trained as programmers.   
56:10   
And so they they kind of go through this um how this applies to research and the   
56:16   
adolescent brain cognitive development study. And then they get into this issue about   
56:23   
vibe coding which of course is where you know we're talking about using vibe   
56:28   
coding to generate code research. And you know, of course, the the standard caveats apply. We did this paper two   
56:35   
weeks ago where we talked about applications to neuroscience. Um, they also talk a little bit about   
56:42   
automation in the coding process. And of course, as we know, you cannot overrely on automation. You have to have an act,   
56:49   
you have to be an active per uh participant in shaping that automation to your benefit.   
56:56   
So, this is really kind of the the introduction. They also talk about uh   
57:01   
beyond reproducibil reproducibility getting valid answers. And there's this   
57:06   
cartoon up here. It's a PhD comic. So uh this is professor Smith who's the   
57:12   
adviser and then the student. And the student says, "How do I know I didn't make a mistake in my computer for   
57:18   
Professor Smith?" And then Professor Smith says, "Did you double check it?" The student says, "Yes." Triple checked   
57:24   
it? Yes. Quadruple checked it? Yes. Then Dr. Smith says, "Did it confirm our   
57:30   
hypothesis?" And the student says, "Yes." And then Dr. Smith responds, "Then stop checking it."   
57:38   
You get this, you fall into this trap when you use uh when you write software for research,   
57:45   
sometimes when you use automation, that is you're trying to find the you know, you're trying to find software that will   
57:51   
give you the right answer, give you the answer you want. And what you should be doing is producing software that just   
57:57   
analyzes your data or whatever sets up your experiment in a way that is agnostic to   
58:06   
that is objective. And so you don't want to necessarily   
58:12   
um you know there is a tendency to sort of they they use a term for this that isn't   
58:18   
packing but bug hacking. Bug hacking is where you write code to kind of as a   
58:25   
means to an end. And that end is usually a successful confirmation of your   
58:30   
hypothesis or a successful confirmation that your data contains information that   
58:37   
you expect it to contain. This has been predominant in   
58:43   
experimental design for years where people will design experiments that confirm their hypothesis. Whereas you   
58:50   
should be designing an experiment that maybe addresses a specific mechanism but   
58:55   
is agnostic with respect to the hypothesis or even the theory.   
59:01   
So a lot of the things we know from experimental design and from scientific methods really kind of just can carry   
59:09   
over to coding. They have the essential tools and techniques section which is where they   
59:15   
hype they sort of hype Python as the tool to use for scientific coding. And I   
59:20   
agree with that because Python is a high level programming language that allows you that has a lot of toolboxes. You   
59:27   
don't have to uh learn a lot of uh you don't have to have a lot of deeprogramming knowledge to use Python,   
59:34   
but you have a lot of powerful tools at your disposal. Um I mean, nevertheless,   
59:39   
you do know how need know some of the data structures and and the best data   
59:44   
structures to use, but Python is generally easy to learn and then the toolboxes are easy to learn as well.   
59:53   
You also highlight version control. So using version control in lab notebooks in in GitHub and in other places I think   
1:00:01   
that's nice that they highlight version control virtual environments which of course if you're using virtual   
1:00:07   
environments you know that you you need to have a   
1:00:12   
uh virtual environment with good ecological validity meaning that it is   
1:00:18   
reproducible every time you open it up and use it. So if it's not reproducible then it's not a   
1:00:25   
ecologically valid environment and you're wasting your time because   
1:00:31   
you know you can't achieve the results that you want. Um you know I think they   
1:00:36   
talk a little bit here about um different types of programming environments as well. Also they talk   
1:00:43   
about um dependencies and different versions of Python and uh these are all   
1:00:50   
kind of you know there's all sorts of forwards and backwards compatibility issues that we need to deal with um that   
1:00:59   
will you know rear their head during programming. And these are the types of   
1:01:04   
things that you have to really kind of optimize and fiddle with. And this is   
1:01:09   
some this is a place where if you don't have formal training in this, you could lose track of what you're doing or lose   
1:01:15   
your sort of momentum. And that's bad because we want to be able to use the   
1:01:22   
best tools that we can. Um, and we want to have like the latest tools and we   
1:01:27   
don't want to have missing dependencies and all that. Um, so and then they advocate using cond   
1:01:34   
for your programming environment. uh this is where you know they they I guess   
1:01:39   
they you know we're talking about UV as a programming environment and they advocate using cond which is of course a   
1:01:46   
package you can install on your machine that has a lot of different tools it has R it has uh Jupyter notebooks it has   
1:01:54   
other tools that you can use for programming really handy tools in fact   
1:02:00   
that um you know all are kind of in this virtual machine that you on and it runs   
1:02:07   
the program the same every time. You don't have you go from machine to machine. You don't have to worry about   
1:02:12   
the different computational resources and the different ways in which the machine manages or the operating system.   
1:02:20   
They also talk about large language models which is good. They uh give a little bit of detail about how large   
1:02:27   
language models could be used um in research uh things like chat GPT and you   
1:02:34   
know really understanding what it's generating and why it's generating it. So they kind of go through how large   
1:02:40   
language models are built and trained talking about some of the open source language models. So the ones that you   
1:02:45   
can use sort of and customize for free in a lab setting.   
1:02:51   
um and you know about how do you do prompting and prompt engineering and   
1:02:57   
then some of the caveats such as randomness and large language models. So there are a lot of reproducibility   
1:03:02   
challenges here. Uh then we go into principles of software engineering. So this is where   
1:03:08   
we have to think about sort of the readability of our code, the modularity   
1:03:13   
of our code and you know different strategies for   
1:03:19   
programming. Um and so this is all really I think useful uh gets into agile development   
1:03:26   
processes a bit. So that's good. Um, I I I do have concerns with just kind of   
1:03:33   
blindly applying agile to research software engineering for the   
1:03:38   
simple reason that a lot of times agile is not well suited to research. It's   
1:03:44   
suited to software engineering just fine, but like the goals of research are not   
1:03:49   
I don't think agile quite captures those requirements. And so, you know, as someone who is a pro project management   
1:03:58   
instructor, you know, I'm saying that agile development processes may be a   
1:04:03   
good starting point for organizing your soft your programming project, but not necessarily extending that to a   
1:04:10   
scientific research group where you're doing a lot of research and you know, you have to sort of interface with that   
1:04:17   
those goals. And then finally, they get into coding with AI. So they go beyond   
1:04:22   
um you know vibe coding. They talk about workflows and how you might an agentive coder into   
1:04:29   
that workflow using your code efficiently and allowing for other people to use the   
1:04:35   
code and allowing for other people to interpret the code and know what the answer what what the output is and   
1:04:41   
interpret that output. And so all these things are very important to understand   
1:04:47   
and to you know kind of incorporate into your uh software engineering process   
1:04:53   
your research process and I think this book is a good start to this. This is a   
1:04:58   
nice resource for like applying a lot of AI stuff to science just because there   
1:05:04   
isn't a resource like this. I I I I think, you know, I think um I   
1:05:11   
mean, again, he he's a great person to be doing it because um because he's   
1:05:16   
always been a coder, you know, like like like you know, um   
1:05:24   
so you know, and a lot of a lot of like core Python tools were developed by fMRI   
1:05:31   
people, right? So, uh, uh, you know, like he's   
1:05:37   
also been around a bunch of a bunch of like, yeah, core Python team   
1:05:47   
people. Um, and you know, I think he saw that that hole, you know, like, okay,   
1:05:55   
yeah, what to your point about, you know, like like science coding is a bit   
1:06:00   
different. Um, and u, you know, I I I was just having   
1:06:06   
this conversation with a startup that is interested in funding some some science.   
1:06:13   
Um, and you know, I I I made the point   
1:06:19   
that I was just like, okay, so you know, if if you've got this hypothesis about   
1:06:27   
frontal activity, frontal lobe activity, like like you know the question I have   
1:06:35   
is like at at what point do we stop and say like hey this is this is just not   
1:06:42   
true you know like like you know if if you've got you know   
1:06:50   
because you're coming in with this financial interest in making this story you know like you should want even more   
1:06:59   
so you should want a clear like um when when to stop pushing this, when to   
1:07:07   
consider other other uh other explanations, right? Because and and and   
1:07:13   
like like that's science or you know like like obviously you want to take a   
1:07:20   
um you want to approach your hypothesis with the the best possible tools, best   
1:07:26   
poss pipeline um and etc. But um you know like yeah   
1:07:33   
that might just not be the that might not be happening. And u   
1:07:40   
um so I I I think it would be great to to cover that in a you know in a regular   
1:07:49   
regular meeting kind of way or and um see you know because again like I want   
1:07:56   
to be able to u   
1:08:01   
I want to be able to help especially you know again just thinking about this from a kind of nerchex standoint. point is   
1:08:08   
it's like like you know these tools are now a part of the the the tool set you   
1:08:17   
know and so um like giving people a proper background   
1:08:24   
um is going to be essential right   
1:08:31   
yeah like they they definitely have um you know again like I I like to put, you know,   
1:08:38   
like the the Chris Racus and and Simon Williamson   
1:08:44   
um articles back to back because um   
1:08:49   
um   
1:08:54   
it it's the two sides of these, you know, like like these are both people who are saying that large language   
1:09:00   
models,   
1:09:06   
But they're both they're both giving you kind of like diff different caveats in terms of of like like what you need to   
1:09:14   
be careful of and and how you need to use them to to get there.   
1:09:21   
Yeah. Yeah. I think and you know I I actually was teaching programming last   
1:09:26   
summer and like I covered it in the class because not least of which one of the students asked about it like having   
1:09:34   
to do vibe coding and you know it kind of covered the pros and cons of it. Of course we did this article uh two weeks   
1:09:41   
ago I guess on vibe coding and neuroscience. So, it's very interesting to compare like the Russ Pauldra book   
1:09:48   
with um this this uh article from the   
1:09:53   
this was from well I don't remember what journal it was in but was it was it transmitter?   
1:09:59   
Yeah, it was a transmitter so it wasn't really a journal but anyways uh   
1:10:06   
yeah I mean they're like immediate professional concerns I mean like when you're thinking about what you're doing   
1:10:12   
with it you're doing research. Okay, you're doing a research. What's the most practical way to use it? And then, you   
1:10:18   
know, there's the PDRA book which is more kind of general um you know, what are the implications   
1:10:24   
of vibe coding versus using another strategy for using large language models   
1:10:30   
or other, you know, how does it interface with software engineering all of this. So um yeah definitely we need   
1:10:39   
these guidelines and I'm glad people are thinking about them. Um   
1:10:45   
yeah and you know this is the thing about sustainability too. So this whole idea of open source sustainability, one   
1:10:52   
of the problems that we have of course is that we have like we generate code   
1:10:58   
for our uh team or for our group and you know we   
1:11:03   
want to be able to reuse it. We want to be able to have good code that scales a   
1:11:08   
different problem. So if we reuse it, if we're, you know, it only works on like our one data set, it doesn't really make   
1:11:15   
sense to invest in like uh maintaining it, you know. So we want to have got to   
1:11:24   
balance all those things out. And we don't also don't want to spend a large amount of time maintaining it. We don't   
1:11:31   
want to spend a large amount of time on it if it's, you know, not if it's only useful to like 30 people. And so that   
1:11:38   
that brings up the question of like who has the resources to do all this? So if   
1:11:44   
you're a small lab, you know, do you need to hire like a code maintainer but   
1:11:51   
also maybe a prompt engineer and then you know someone who can um   
1:11:56   
test the code, do all sorts of software engineering things. you need three people and you have to, you know, and   
1:12:04   
that's not viable for a lot of labs. Just have people just doing that   
1:12:11   
and there no real community resources for it yet. And I don't even know how you would Well, I guess you could build community resources by kind of sharing   
1:12:19   
people, you know, but that's, you know, that's not really people aren't thinking   
1:12:25   
about in that way. I mean, as opposed to like something like a PCR machine or   
1:12:30   
like a lab cell culture in a lab where you know kind of what you know you might   
1:12:36   
need a tech for that or someone who knows how to run the machine. You have service people offsite who can come in   
1:12:43   
and fix it. And so those are known quantities and those are known expenses   
1:12:48   
and accepted expenses. So, you know, having the software infrastructure isn't   
1:12:55   
just about the expertise. It's about like paying for it and getting like uh   
1:13:00   
people to accept it as a sort of a thing that we put into our scientific process,   
1:13:08   
you know, it so like you know uh if you write a grant or if you plan out   
1:13:13   
research and you say we need to pass this off to a prompt engineer for a while or we need to have their input,   
1:13:20   
that's a thing that people have to accept. And if you ever done research in a   
1:13:26   
group, you know what I mean. I I I   
1:13:32   
mean I I know it's not the open source software sustainability goal, but um   
1:13:42   
but I I I do think or you know like again like I I I   
1:13:49   
remember asking about how how much overlap is there with this project and   
1:13:56   
um not vibe coding but multi- aent software   
1:14:02   
developer, right? Because like like to to your point about   
1:14:10   
three people and and say some of the kind of like   
1:14:17   
best practices for software engineering, right? Because um you know my my first I   
1:14:26   
mean essentially my first real job out of high school of college was was   
1:14:33   
leading software development software engineering for a startup medical device   
1:14:38   
company right regulated software development falls   
1:14:45   
under ISO 9000 manufacturing and you have all these   
1:14:52   
roles for it in terms of you know what are the different roles people have   
1:15:00   
um you know like like stage of software   
1:15:05   
development is is um is documented because   
1:15:11   
because of the the systems overall complexity right   
1:15:18   
so the um and you know that then being   
1:15:23   
able to being able to say something about like I'm going to add this new feature um what systems are likely to   
1:15:32   
affect is something that is a is a quite a you know it's a complex question it's   
1:15:39   
a sophisticated question um and so you definitely need to know you know um   
1:15:48   
a lot about interdependencies and and you know who else is developing things.   
1:15:53   
Anyway, the point point being that it's it's a team effort, right? And that the   
1:15:58   
documentation and and controls on the system are are about maintaining   
1:16:06   
um team level knowledge, right?   
1:16:12   
And um anyway, you know, seeing software development as   
1:16:20   
a multi- aent process, I think is is the   
1:16:26   
the the the um the appropriate way to to think about it.   
1:16:31   
And um uh I I I think there's some some overlap   
1:16:38   
there with the open source project or the open source sustainability   
1:16:43   
And um yeah would would love to to see more about that like like even Vi was   
1:16:49   
just saying like you know people people are using language models to generate   
1:16:55   
the prompts for for language models.   
1:17:00   
Okay. Okay. So to follow up on one of your points, Morgan, yeah, I think the multi- aent software development is very interesting and as I was thinking about   
1:17:07   
this from the standpoint of sort of a formal academic software engineering or   
1:17:14   
software engineering developer um or software research engineering developer perspective. So you know we have to kind   
1:17:21   
of meet some sort of expectations especially for modern software. In the past, uh, academic software has been   
1:17:28   
like where people would produce something for a specific research   
1:17:33   
project and they wouldn't really put any effort into refining it and they would just maybe use it for their own research   
1:17:40   
or they would send it to people and they would use it in their own research group. In any case, the audience for   
1:17:46   
that was very small. The user base was probably in the order of like 50 to 100 people. So there's no need to have all   
1:17:54   
this extra infrastructure. Uh and so like what I was thinking   
1:17:59   
though is that if you really wanted to do good, you know, uh research grade   
1:18:05   
software engineering, you need at least three people. So you had to have like three lines available   
1:18:12   
to your lab. You need to have a software engineer or someone who knows something about software engineering. You need to   
1:18:18   
have some sort of maintainer to maintain the software. and then some sort of tester to test for bugs and to fix   
1:18:24   
things that are that go wrong with the software. Um that sort of thing. And so   
1:18:31   
it's interesting, not all labs can afford, of course, to have those three lines. Um you know, sometimes they can't   
1:18:39   
even afford to have one. Um, it kind of reminds me of like biioinformatics or   
1:18:44   
early biioinformatics where a lab might get a biioinformatician who was just someone   
1:18:50   
who could program and they would then task them with doing all the biioinformatics in the lab. Did they   
1:18:56   
have bio formal biioinformatics training? Maybe not, but they knew how to program and that's all that mattered.   
1:19:02   
Um, you know, so that that's that's kind of where we are with that. So the the infrastructure for multi-agent software   
1:19:10   
development in a lot of labs is maybe not feasible or infeasible. Um for larger labs maybe it's not too much of a   
1:19:17   
problem. So it's like using uh statistical software. You know we have   
1:19:22   
statistical software that's maintained outside of um academia. Uh but it started in   
1:19:30   
academia and it started for academic problems. Basically, you develop a software that will um you know, sort of   
1:19:37   
answer very arcane questions or allow you to do arcane types of analyses and   
1:19:43   
it it presents it in a way that you can interpret. Um and so, you know, if you ask a   
1:19:50   
statistician, of course, is this a valid way to do statistics? They'd say, no, you need to have a professional   
1:19:56   
statistician on staff to do this. But, of course, a lot of labs don't have access to that.   
1:20:02   
But but sometimes if you're in the academy, what they do do have is they have like a statistical research   
1:20:09   
institute or a statistical consulting group where you can go and pose questions to statistitians on staff.   
1:20:16   
from their posttocks or something and the university pays for it and you get that access to that expertise that you   
1:20:24   
know maybe those statisticians or applied mathematicians or applied statisticians where they can you know   
1:20:30   
engage with real research questions and so they have a little bit more grounding   
1:20:35   
in their sort of advice and then you can of course implement it in the software   
1:20:40   
or implement it with the software so I mean maybe that's what we need for multi- aent software development is we   
1:20:46   
need at least at the institutional level to have you know maybe several   
1:20:52   
specialties and spread that specialty out across different smaller research   
1:20:57   
groups and make sure that they can access that expertise with a lower barrier to entry.   
1:21:05   
Um it's interesting because you know when when uh if you think about open   
1:21:12   
access and open science especially the type of open science that Russ Pauldra   
1:21:18   
and company espouse it's usually about um you know how do we get institutions   
1:21:24   
to enforce open access standards or open science standards and one of the ways to   
1:21:30   
do that of course is to say well we need to force groups into compliance. So if you have a funding agency, they might   
1:21:37   
have uh requirements for uh data uh like some sort of data pipeline where you   
1:21:43   
have a data analysis that's open and then you archive your data and you might   
1:21:49   
have pre-registration where you register something before it's um you know before   
1:21:55   
you do the full study. And all of that of course costs time and money for which   
1:22:00   
a lot of small research groups don't have. And so that that's the problem with that kind of enforcing standards   
1:22:07   
upon research groups. Of course, we have the problem of, you know, having the expertise available, but then we also   
1:22:14   
have this issue of how do we enforce or enforce compliance and how do we do it in a way that keeps the barrier to entry   
1:22:21   
low? You know, it almost seems sometimes like the institutions are colluding with   
1:22:28   
large research labs to keep smaller entities out of the game simply because   
1:22:33   
the all the standards for like open science are founded, you know, are sort   
1:22:39   
of proposed by the large research groups or with the large research groups or RO1 institutions in mind. So, it's a very   
1:22:45   
interesting area to think about more.   
1:22:58   
Yeah. I I mean I I mean well what I'm what I'm curious about and and would   
1:23:05   
would love to know more is like how much of that   
1:23:12   
is already implemented in something like um Copilot or you know like like I'm   
1:23:21   
trying to think of um I I forget who owns Copilot but Um,   
1:23:28   
is that Microsoft? Oh, I guess they own GitHub too. Yeah. Okay. Um uh um   
1:23:36   
the you know like like so is is co-pilot already a multi- aent   
1:23:44   
system in you know in the in the back you know in the back end in the sense   
1:23:50   
that like you know like like because it would be crazy to be generating codes   
1:23:58   
and not thinking about how to test   
1:24:03   
You know and and and you know like to some extent those   
1:24:11   
should not those should be separate processes you know like like because you   
1:24:18   
know you don't you don't you don't want your coding agents   
1:24:24   
context if if I I don't if I'm using the right word here um   
1:24:33   
to to to influence your your testing, you know, to like like you know, your   
1:24:41   
your your tester should be, you know, shouldn't be in the weeds of the um how   
1:24:48   
the code was generated, but is more like what was   
1:24:55   
this generated to do and how best do I test it and how best do I probe this   
1:25:04   
code for for holes, you know, like like like again like we would do evaluations   
1:25:12   
where we would be focused on,   
1:25:17   
you know, failure modes, right? So it's just like like like   
1:25:23   
what you know I mean it's it's it's like like to a certain extent your your   
1:25:28   
software tester is kind of your red team right you know and like like I mean   
1:25:36   
again I don't know if my examples from from medical device development are are too specific but like like is there is   
1:25:44   
there input to this code that the codes not expecting that we'll   
1:25:51   
break it, right? You know, I mean, and and kind of like like Y2K being like a a   
1:25:57   
a stupid but simple example of like, you know, is there is there something   
1:26:04   
that the software just wasn't expecting as as input like and and like Yeah.   
1:26:13   
So, um, yeah, I just don't I you know, like like is co-pilot,   
1:26:20   
you know, is co-pilot still just essentially a single process LLM? Well,   
1:26:25   
I mean, but yeah, I mean, yeah, people were were pretty sure   
1:26:33   
that um that Microsoft was going to use their   
1:26:39   
ownership of GitHub and LinkedIn maliciously or like no like   
1:26:47   
exploitatively. I mean, again, like the the person doing the um the podcast   
1:26:53   
tours right now is Corey Doctoro talking about initification   
1:26:59   
and and Yeah. Yeah. I mean, but he he's he's   
1:27:05   
absolutely right. I mean, you know, like you see it everywhere, right? and and um   
1:27:14   
uh u I mean it's a I mean it's not exactly this the same problem as the   
1:27:19   
training problem but um but it just speaks to I mean you know again like he   
1:27:25   
he talks about these critical steps in in shitification where it's just like like you first need to get addicted you   
1:27:33   
you know you need to get the users addicted first and so you are providing   
1:27:39   
this absolutely public service that is of course a private service,   
1:27:47   
right? But you know, everybody's using it because it's free and it's useful,   
1:27:56   
right? and and you know and then somebody comes   
1:28:02   
along and it's it's like yeah why did   
1:28:08   
people think that this was actually different than 23 and me you know it's just like like of course a company could   
1:28:14   
come along by them and you know throw out the playbook in terms of what kind   
1:28:20   
of um privacy controls they've got you know Um   
1:28:27   
I mean and this this again somewhat speaks to the   
1:28:35   
and not suffer sustainability but but you know I I I think this discussion is   
1:28:42   
is very very much like the um   
1:28:49   
the Unix philosophy of of software development, right where   
1:28:56   
they they thought a lot about   
1:29:02   
the modularity of software and and you know I mean again it's   
1:29:11   
interesting when you consider that the time in which they're they're   
1:29:17   
having these discussions among themselves is that they are literally sharing a sh a central computer Right.   
1:29:24   
So, so you have you have access to other   
1:29:29   
people's code or like other people's programs. So, this this idea that like software   
1:29:36   
shouldn't be built up um into a monolithic um   
1:29:45   
uh you know, a monolithic system you control. But keeping it modular allows   
1:29:53   
people to um actually remix tools   
1:29:59   
um in a much more flexible way to do things that the original developers didn't even um or or like use cases that   
1:30:07   
the original developers didn't even consider.   
1:30:12   
So you know you see this in the discussions of like like you know standard IO   
1:30:19   
and and things like that so that the tools can all be you know into made into   
1:30:24   
pipelines and things like that made into pipes.   
1:30:30   
Um, yeah, I I can't think of a particular open source tool right now, but there's   
1:30:36   
definitely been I I can think of tools where it's like after a while the the   
1:30:42   
software project is broken up into a core and something else because people are like, "Yeah, this this has become so   
1:30:49   
so unusable from from, you know, too too much   
1:30:55   
feature accumulation.   
1:31:04   
Well,   
1:31:09   
yeah. Yeah. I mean, I I would definitely go back to the like, you know, again, like the the you   
1:31:17   
know, um I know not everybody's a fan of Eric Raymond, but like some some of his   
1:31:23   
writing about the Unix philosophy of code   
1:31:29   
and and you know um   
1:31:35   
you know, he he was probably more summarizing a lot of the   
1:31:41   
um uh Unix and open source developers at the time.   
1:31:47   
But but this is this is this was so key in their in their writing of like why the you know   
1:31:56   
um why Unix tools were written the way they   
1:32:02   
are was all all to defend against this these these kinds of problems.   
1:32:15   
pro proactively modular, you know, you like like like like you   
1:32:21   
make you make a tool that does one thing well and has a standard standard IO and   
1:32:29   
that allows you to um um and that's what shell scripting you   
1:32:36   
know shell scripting was was taking those tools and allowing you to to   
1:32:42   
flexibly remix, right? So, so it's like you're you're   
1:32:50   
kind of do, you know, Shell, I mean, it's funny. Um, who's the guy?   
1:32:56   
Uh, uh, John Sterhout, wasn't he the   
1:33:02   
um developer of Tickle? Uh, yeah. Yeah. Anyway, I'm I'm just   
1:33:09   
showing my age in the sense of like this is these are these are you know tools   
1:33:16   
that barely you know like like the students now they don't know any of   
1:33:21   
these these tool developers. These were a simple highlevel system programming   
1:33:26   
tools um back in the back in the day you know   
1:33:32   
and and actually Oxford's fMRI software actually uses tickle   
1:33:39   
excuse me but it was it was it was you know it was   
1:33:44   
like it was another kind of shell script   
1:33:49   
right and again it's like seeing shell scripting as systems programming,   
1:33:55   
but but it can be systems programming because you've got this you had these   
1:34:00   
decades of of the Unix philosophy of tools of tool development where you've you've   
1:34:06   
made these tools with with that kind of modularity and and and the standard IO   
1:34:12   
gives you compositionality. All right. So I'm going to talk a little bit now about this transmitter article   
1:34:18   
from this week in the computational neuroscience bin. This is wholeb brain bottomup neuroscience the time for it is   
1:34:25   
now. This is Edward Bdon and Conrad cording and they're doing some work in C   
1:34:30   
elegance where they're trying to put together this data driven model of bottom neuroscience. they're doing this   
1:34:37   
project where they're doing this mass experimental uh collection of data and then they want   
1:34:44   
to build a model of the sea elegance. So you know they want to sort of get the   
1:34:49   
data firsthand. Now open worm of course gets the data secondhand and then   
1:34:56   
applies it to uh you know models. In this case, they want to generate the data firsthand   
1:35:02   
using like optogenetics and approaches like that. Test like each   
1:35:07   
cell in the in the C elegance. You know, you can use optogenetics to get very   
1:35:14   
specific information about each cell, how it's active during behavior, and   
1:35:19   
then put all that data together into a model of C elegance as it's behaving as it's, you know, uh   
1:35:27   
doing what what it does. And so that's what they're trying to do here. And uh   
1:35:33   
they uh Conrad and Edward published this article in the transmitter whole brain   
1:35:39   
bottomup neuroscience. The time for it is now. So this is just kind of like expounding upon their vision and you   
1:35:46   
know I don't know I hope that they do well on this but this they're at the sort of stage where they're trying to   
1:35:52   
sell the idea community. So um they're they're also trying to fund   
1:35:58   
raise on well of course. Um Yeah. And so uh this is just kind of sowing   
1:36:04   
this idea the concept of ground truth of course which you know we are very   
1:36:10   
familiar with in like if you're the neuroscientists you would want ground   
1:36:15   
truth for everything but for a lot of you know people who are doing modeling   
1:36:21   
it's sometimes a little bit elusive to get the ground truth and you know some   
1:36:26   
people think that actually models are just as good as uh you know a ground truth and what they   
1:36:33   
mean by ground truth is like if you have a model result you test it with experiments not necessarily with data   
1:36:41   
but with actual manipulations. So like in an experiment we do an intervention and we can test different   
1:36:47   
ideas different hypotheses and you can do these massive experiments if you have   
1:36:53   
the high throughput platform where you can run a thousand thousands of experiments thousands of variations on a   
1:37:00   
specific idea and get a ground truth. Now you get that much data and you have   
1:37:06   
that many conditions it's hard to interpret that ground truth but you have it.   
1:37:12   
So we can design from the bottom up unleashing untold combinatorial possibilities. So if you have a   
1:37:19   
hypothesis about a certain gene involved in a certain mechanism or if you have   
1:37:24   
hypothesis about specific cells interacting then you can test that   
1:37:30   
hypothesis and you can test all the variations of that circuit or of the   
1:37:35   
genus expression or whatever and you can then you know build uh better models   
1:37:42   
because then you have that very specific data. Um in the mature sciences such as   
1:37:49   
physics we can start with the known properties of components electrons or steel beams for example to simulate and   
1:37:56   
predict the behaviors of systems made out of these components such as microchips and bridges. Discovery is   
1:38:02   
less about luck and more about design. Start from parts of known interactions then simulate and build. And then this   
1:38:10   
is simulate requires knowledge of parameters. So we, you know, we kind of go from individual logic gates to   
1:38:19   
circuits to architectures to maybe like a chip   
1:38:25   
that's at the top here. This is this artificial system in the brain. The analogy would be from a neuron to like I   
1:38:33   
guess this is a cortical column uh to a network of cells and then to the whole   
1:38:38   
brain. So we know kind of you know we have more parameters as we move to the   
1:38:43   
right we can simulate those parameters but we need to sort of ground truth   
1:38:49   
those parameters and it's harder to do as you move to the right because you have more and more parameters that you   
1:38:56   
really need to understand. And so with like a single neuron it's hard but with   
1:39:02   
the whole brain it's almost impossible unless maybe you have a high throughput platform to do that.   
1:39:08   
um and they they point out that neuroscience instead of this bottom up approach most still mostly works top   
1:39:15   
down. We observe an effect and then develop and test a hypothesis. So we may do an experiment where we do a   
1:39:23   
behavioral assay of the brain where we um you know have someone we give them a   
1:39:28   
list of words and we see which ones they remember and which ones they forget and then we kind of say okay that's the   
1:39:34   
behavior now how does it work in the brain? So you have to then go down into the brain and find the mechanism. And so   
1:39:43   
you know that's not necessarily maybe the way we want to do it. Maybe the way we want to do it is to work from the   
1:39:49   
bottom up where we look in in like at specific mechanisms in the brain and   
1:39:55   
then work our way up to the behavior. Uh we try to understand feelings,   
1:40:01   
decisions, sensations, movements and even consciousness through this process. Sometimes this works revealing a   
1:40:07   
mechanism. So you can look down and you can clearly see some mechanism that's repeatable.   
1:40:14   
But the hypothesis space is enormous. Hundreds of brain regions, thousands of cell types, perhaps millions of molecule   
1:40:21   
types. In such large spaces, almost all hypotheses are wrong.   
1:40:26   
So this is where you know you're you you're asking so many questions.   
1:40:32   
um you basically are shooting kind of blindly into a room and your chances of   
1:40:41   
getting the correct hypothesis are very low because if you have a million hypotheses, how many of those are right?   
1:40:48   
Only a handful at best. And so you're wasting a lot of time uh interrogating a   
1:40:54   
lot of hypotheses that are wrong. And you know that they're clearly wrong, but you don't know which ones.   
1:41:01   
Testing a hypothesis in isolation rarely leads to understanding how a system works in terms of its mechanisms. And if   
1:41:08   
it does, we only learn about a few. Early understanding how a brain process   
1:41:14   
occurs, curing a brain disease remains daunting. There are many hidden dimensions, many hidden variables for   
1:41:20   
that matter to confound us. So, we can't treat this like we're investigating a   
1:41:27   
microchip. They have this paper about uh or Conrad Cording and another person of   
1:41:34   
course has the classic paper on can a neuroscientist understand a microprocessor which is really a nice   
1:41:40   
thought experiment about how we do neuroscience and how if someone gave us a micro or   
1:41:48   
like someone took a personal computer that we have today back to like the   
1:41:53   
1700s you know could that invest investigator   
1:41:59   
figure out how that microprocessor worked or figure out how the the computer worked. Would they be able to   
1:42:06   
isolate the mechanisms that make that computer work given that they have no knowledge of the technology under?   
1:42:13   
That's kind of where we are with the top down view of neuroscience. We're looking at a brain. We're looking at behavior   
1:42:19   
and we're trying to find the mechanisms. Look down and find the mechanisms. And of course we need tools to do that. But   
1:42:26   
the tools don't really give us the insight or the even you know kind of   
1:42:31   
isolate the mechanisms for us. They merely give us like a picture into the   
1:42:36   
brain. Then we have to make that interpretation from analyzing data and   
1:42:42   
thinking about how you know how best to do that.   
1:42:47   
Can we take neuroscience to its microchipper? And so by that they mean like um you   
1:42:54   
know I'm not sure what that means actually. Um but I guess with microchips   
1:43:00   
you have a ground truth and you know you can use that to better   
1:43:05   
understand what it's doing. It is difficult to achieve ground truth for brains. Some scientists have succeeded   
1:43:11   
at bottomup neuroscience in small systems such as the squid giant axon or crab stematic stmatogastric ganglen   
1:43:20   
yielding transformative foundational principles about how brains work. So this is again also a C elegance you can   
1:43:26   
do this where you have the ability to go back to the genes you have well   
1:43:33   
annotated genomes you have well characterized gene expression patterns you have a small brain you have a small   
1:43:40   
finite you know like every you know you have well characterized   
1:43:47   
relatively small number of cells in the body so under a thousand and you can in   
1:43:53   
fact you could probably tractably analyze every cell and analyze you know   
1:43:59   
different pathways in every cell and it wouldn't be like you know something that would be take you a hundred years which   
1:44:06   
might be the case with the human brain. So this is kind of what they're thinking   
1:44:12   
about. They're thinking about these small systems but they're really their goal is to look at the human brain and   
1:44:18   
human systems and that's a you know trying to scale that up from say like Elegance is of course very hard but if   
1:44:25   
you can develop the right system for it you know then you can f kind of have a   
1:44:31   
founding technology for this bottomup neuroscience   
1:44:36   
which brings up the question if you can do bottomup neuroscience in these small systems that's great but could you can   
1:44:43   
you actually scale it up I I would argue maybe not because uh what happens   
1:44:51   
in human brains or say mamalian brains as opposed to sea elegance is you have a   
1:44:56   
lot of different types of mechanisms at play. So for example you know you have   
1:45:02   
segans is famously utellic which means it has the same number of cells from   
1:45:07   
worm to worm the developmental process produces a certain number of cells and that's it. The cells their fade is   
1:45:15   
deterministic so you know kind of what they're going to be. So you have and then their their physiology is of course   
1:45:22   
within this range that we can you know we we understand pretty well because it isn't there isn't a lot of plasticity   
1:45:30   
even in in you know laral plasticity and C elegance is limited to well-known   
1:45:36   
mechanisms. So it's easier to do bottom up neuroscience in a system like that. Can we do that in uh with with humans?   
1:45:44   
Well you know human brains are huge. They have a large number of neurons. They have a large the human body is a   
1:45:50   
large number of cells. We have to estimate how many cell types we have because we simply don't know. Um and you   
1:45:59   
know all of those things kind of play you know can that complexity be overcome   
1:46:04   
with this bottom up what they call bottom up approach but I suspect is going to end up being more of a brute   
1:46:10   
force approach in a lot of cases. And so that's the question and I don't think you necessarily can I think there's a   
1:46:18   
lot of plasticity and variation that is going to be serve serve a very strong   
1:46:25   
headwind. Anyways they get into sea elegance they get into some of the tools you can use   
1:46:32   
and that's really their focus is going to be this project. This is going to be this is just an image of the sea   
1:46:37   
elegance and it's showing the different um you know nervous system connections   
1:46:44   
here um for sensory motor integration. So you have   
1:46:51   
these stains where they're showing structural proteins and motor proteins and nuclear proteins the cells and   
1:46:57   
nerves of the of the body. So you know that looks that alone looks   
1:47:03   
pretty complex but as I said you know we can understand complexity if it's sort   
1:47:09   
of deterministic or if it's at a small scale but scaling up complexity to   
1:47:14   
something like you know um 100 million cells or a 100 billion connections   
1:47:21   
that's a little bit harder to do especially when things are not deterministic and you have more stochastic mechanisms out there.   
1:47:30   
Okay. So, yeah, this is a pretty good uh article and it's really kind of getting into like how do we estimate   
1:47:39   
uh variables and parameters in experiments?   
1:47:45   
How do we use data to how do we leverage data to understand sort of the parameters under which a   
1:47:51   
neuron operates? So, if we have enough data, I guess we can understand this.   
1:47:57   
may ask the question how much data do we need to estimate the parameters of ground truth of the neuron. So you need   
1:48:03   
to under you know you we don't know that in advance and you know oftentimes the   
1:48:08   
whole premise of big data or data science is that we can if we just have   
1:48:14   
enough data we can understand any problem that's the idea and same thing with sort of the Norvian view of AI   
1:48:24   
where you know the idea is you train your model with enough data you throw enough training model at your or   
1:48:29   
training data at your model and you end up with a model that can do anything or   
1:48:35   
it has these sort of the super intelligence. That's the idea. And so, you know, maybe that's not the right way   
1:48:42   
to look at this. I I would suspect maybe not. Maybe there's something here that's not going to give us the right answer   
1:48:49   
because you can get you can collect a lot of data. You can throw a lot of data at something, but that data had better   
1:48:55   
be realistic and representative of a wide range of conditions that say an   
1:49:00   
organism will experience that'll have a lot of out of distribution representation all of that. If we we   
1:49:09   
don't have that and again you could have uh you know uh terabytes of data but if   
1:49:16   
it doesn't represent those things then it's not going to be sufficient. In any case, they they kind of go   
1:49:22   
through this. They have some equations here. Um, and it's basically   
1:49:30   
the idea that the amount of data we need for a fixed error norm increases linearly with the number of parameters   
1:49:36   
P. So they focus on this idea of using the   
1:49:42   
inverse problem from statistics to characterize the   
1:49:47   
error the analytical error and then overcoming that analytical error through   
1:49:52   
more data. So that's the idea. And so um   
1:50:00   
uh the errorm increases as the data start differing from the inputs being an   
1:50:05   
isotropic gaussian and become correlated or more precisely small singular values   
1:50:11   
of correlation matrix become small as a conditioning factor explodes.   
1:50:17   
So um basically you start with an isotropic gaussian and   
1:50:23   
then you go to a correlated state because real real data tends to be very   
1:50:28   
correlated. Reporting from all neurons is probably insufficient to identify even linear weights of a realistic   
1:50:34   
system. This is, you know, kind of highlighting kind of the the problems here with with   
1:50:42   
getting the uh right amount of data for this exercise. But again, they're using   
1:50:49   
a lot of, you know, they're using an optogenetic test bed. They have tools like coldworm calcium imaging. So, there   
1:50:56   
are tools that we can use and we have more tools coming online all the time. And those things work great in like sea   
1:51:03   
elegance and maybe even zebra fish. Then when you start getting up to most brains and a million brains, will this this   
1:51:10   
China effort scale? Maybe. I don't know. Um, so this is that's a nice paper uh   
1:51:17   
that was in our Slack. Um, and so yeah, I don't know if Morgan   
1:51:22   
had any thoughts on that.   
1:51:28   
Not um   
1:51:33   
I mean not not thoughts obviously I was just passing it on as as you know a kind   
1:51:40   
of official um you know   
1:51:47   
we knew Ed Boy Bon and Conrad Cording were proposing this   
1:51:55   
ambitious data collection. Yeah. Yeah. Um and and you know and like like I was   
1:52:05   
you know attending these foresight meetings that where   
1:52:12   
Conrad specifically was was making this this this bold claim of like, you know,   
1:52:21   
we we we need we need this moonshot for   
1:52:28   
um the elegance to   
1:52:34   
you know that like like because it could become this this base   
1:52:40   
on which we met you know this this first rung right   
1:52:46   
um and so I I I mean it was more like I   
1:52:52   
wanted to see how they would frame that in a in a transmitter article.   
1:52:58   
Yeah. In a sense. So like like it was it was still, you know, it was like   
1:53:08   
it was still a bit like highlevel general, you know, like wouldn't life be better   
1:53:16   
if we had this, right? Yeah. And you know like like yes   
1:53:25   
like you know um   
1:53:32   
but was hoping to see more in terms of just um   
1:53:41   
yeah was was just hoping to see more details in terms of   
1:53:46   
data collection. data collection and like like so like   
1:53:54   
Yeah. And as well as like like   
1:54:03   
I mean maybe maybe more about the equipment. I   
1:54:08   
don't know if this is just coming off of conversations that I've had with him before.   
1:54:14   
Um but I I was I had asking like   
1:54:21   
why they weren't trying to put together kind of like a flywire AI   
1:54:26   
kind of consortion. Yeah. In a sense of like like   
1:54:33   
does does it have to be you know a centralized 20 to40 million fund? Um   
1:54:42   
well I think the idea here is they want to use uh Ed Biden's optogenetic tools   
1:54:47   
to like do one shot sort of imaging or multi-shot but all at the same facility   
1:54:53   
and there's a case to be made for that because it's like you can reproduce your work more easily if you have the same   
1:54:59   
group doing it right like you if you have a bunch of groups doing it you can   
1:55:04   
run the risk of them not really being coordinated or not have doing the thing   
1:55:09   
in the same way. So if it's a method like optogenetics where it's maybe highly variable in the hands of   
1:55:15   
different people doing these kind of high throughput experiments even um you   
1:55:20   
know maybe that's that's kind of the it's better off. I don't know.   
1:55:27   
Yeah it's it's um   
1:55:33   
yeah no for sure for sure. So it it was um   
1:55:39   
it was definitely a chance to see how they would present this and um you know um I'm still you   
1:55:50   
know it's the kind of thing where just like like would it be interesting to hear   
1:55:58   
from some Janelia or Alen Institute people in terms of just like why haven't they done it? Yeah, that's true. Because   
1:56:04   
they would be the one, you know, like like we have places that   
1:56:10   
could do this. Yeah. Well, like like they're already, you know,   
1:56:16   
well, I mean, yeah. Anyway, like like   
1:56:23   
so curious. would love to start getting some resources for um uh working with   
1:56:33   
worms. um both both C. Elegance and um   
1:56:40   
and Planeria in terms of just you know like again like intro undergrad kind of   
1:56:49   
things to be um yeah look looking for resources   
1:56:56   
around that. Um and you know would um obviously I've   
1:57:03   
got some things where We're hoping to do some, you know, can   
1:57:08   
we can we what's involved in replicating a   
1:57:15   
Michael Leia kick? Oh, yeah. Well, yeah, that's a tough one. I think   
1:57:21   
you need pleneria to start with. Yes. Um like a micro ablation laser   
1:57:29   
and and you know, so we have a startup that's actually doing   
1:57:36   
um optogenetics u cell culture work   
1:57:42   
um around bio electricity for non-neural cells   
1:57:48   
and and I am going to be you know so like again like I I'm I'm just um   
1:57:57   
I just want to follow up on something that um I forget which what this discuss   
1:58:03   
question came from, but just like like why we don't see more um   
1:58:10   
papers building off of Michael papers like why does why does Michael Le seem   
1:58:17   
to operate uh in his world? Yeah. Yeah.   
1:58:23   
and and uh   
1:58:30   
and I I don't think he falls into the category of like none of his students   
1:58:36   
continue on his work because like I'm I I think one of one of the   
1:58:42   
anthropots first authors I think is now a tough   
1:58:48   
professor. Um, and   
1:58:53   
I think anyway, but like like again like trying to trying to, you know, how how   
1:59:00   
to get people involved with like looking at these these um uh um   
1:59:09   
model systems and you know like like starting to think about you know um   
1:59:18   
quantifying your behavior and things like uh that that that we have like um   
1:59:24   
that aren't $20 million research. Right. Right. Right. Yeah. Um   
1:59:30   
but but um Yeah. And and again like like what does   
1:59:38   
it take to get into say doing optogenetics like like we've talked about at the lab. Um so so Elliot who   
1:59:46   
leads biotech before and is is you know kind of leads by the   
1:59:52   
punk society. Um uh he met with Ed before because Ed Bdon is   
2:00:02   
is the regular at foresight meetings and um he's he's gone down to the Honduran   
2:00:10   
Prosper um area. Do you know this this island   
2:00:15   
off the coast of Honduras? I know, but it sounds very Jurassic Parky. So,   
2:00:21   
it's super Jurassic. I mean, it's like Yeah, but it's like it's like a weirder,   
2:00:28   
darker, you know, um libertarian.   
2:00:35   
Oh, transhumanist, you know, um uh um Jurassic Park. Oh,   
2:00:44   
I mean in the sense of like like it's kind of um it's kind of a a crypto   
2:00:53   
network state, you know, like like hey if we don't you know like we can do   
2:01:00   
medical development faster because we don't have to follow   
2:01:06   
any rules seems to be the pitch you know and I always say like which   
2:01:12   
rules? Yeah. Like can you name   
2:01:18   
like can you name one of those rules? Yeah. Or do you just think that this is   
2:01:25   
how medical devices or you know medical research is is limited? Um but um   
2:01:34   
but but it's you know flown down. I mean, you know, like he's he's he's down   
2:01:41   
there, too. And I think they've talked about this before   
2:01:47   
in terms of um you know um his expansion microscopy seems to be   
2:01:55   
actually a very accessible financially. I mean like like it's it it   
2:02:01   
is actually a somewhat lowcost technique, right? Or you know like like It it doesn't.   
2:02:09   
Yeah. So like like what can we pull off at Bunk Lab   
2:02:16   
in terms of of Yeah. You basically have to explode your   
2:02:21   
samples and then imaging, right? So you can't do any kind of live imaging,   
2:02:27   
right? So So it's just like like Well, that's the that's the other thing, right? Because that like you know most   
2:02:34   
most um real neuroscience groups. And by that   
2:02:39   
I'm talking about kind of like molecular neuroscience, right? Like you've got a you've got a you got a lot of your   
2:02:46   
resources in your microscopy, right? And and you know, so you know that's   
2:02:52   
usually I mean again I think it's hysterical that our you know the we've   
2:02:57   
got this lowcost way of making you know sophisticated bio printers. Um but you   
2:03:04   
know the group that taught us like is using a $250 printer to make tissue   
2:03:11   
samples that they're imaging with, you know, basically a multi-million dollar microscope,   
2:03:16   
right? Yeah. Yeah. Well, and and cut cost where you can, right?   
2:03:22   
Yeah. Yeah. Yeah. I mean, you know, good. You know, and so it's like I get why there, you know, the students prefer   
2:03:28   
this than the the um you know, $100,000 bio printer. Um, but it's hard to   
2:03:36   
recreate that that microscopy functionality, right?   
2:03:42   
So we we we were just talking yesterday about like can we build our own confocal   
2:03:47   
microscope like like you know I mean this is after   
2:03:53   
this is after trying to pursue some some you know very expensive Nikon um and   
2:04:00   
other microscopes online on on auction sites right like like can we get a can   
2:04:07   
we get a you know4 million dollar microscope for20 $20,000 or something like that. But we've got to go we got to   
2:04:14   
drive it ourselves from like like somewhere in Pennsylvania. Yeah.   
2:04:20   
Um uh you know that um anyway but but   
2:04:25   
expansion microscopy is this is an interesting technique that that would   
2:04:30   
allow us to do more. Right. Um any uh   
2:04:37   
it's it's uh it's a great proposal or you know like I   
2:04:44   
would love to see them get the funding you know and um uh   
2:04:52   
you know again Conrad's on a lot of the papers that I like around neuroi   
2:05:00   
but like so many of them are are pretty much neuroscience, right? Yeah.   
2:05:06   
Like like like you know it just seems like one of those things where it's just like you know I'm talking about AI   
2:05:13   
because that's a good funding. Right. Right. There is that aspect of   
2:05:19   
it. Yes. You know AI what are you doing with AI? Well Right. Right. Right. How how is AI   
2:05:26   
helped us? You bought a subscription to cloud. Yeah.   
2:05:33   
Yeah, that's yeah. So, I mean um yeah, I think that's those are all good things   
2:05:39   
to think about. You know, oftentimes people will propose things and then, you   
2:05:45   
know, the reality maybe sets in. So, fortunately, they can get this off the   
2:05:51   
ground and get some good results. I do think, yeah, I think the Janellia piece is interesting because they've done a   
2:05:58   
lot of connetos. they've done zebra fish and of course the the flywware stuff and   
2:06:03   
then you know so you have expertise there and seeing that you know I   
2:06:09   
actually think you know it's is it really that we need optogenetic data or   
2:06:15   
is it that we can just leverage data that we have and then you know um   
2:06:21   
because there's just a lot of data out there and uh that's the whole premise of high throughput data is that you have   
2:06:29   
lots of data to work with and it seems like we just keep collecting more data and it's always the question is like why   
2:06:35   
can't we get achieve this breakthrough or we need more data. So we get more data and then we get all this data and   
2:06:42   
we don't know what to do with it. So we need more data to solve that problem. maybe some more software.   
2:06:48   
you know, I I I I don't know who's   
2:06:53   
who's best like articulated this, but um   
2:07:00   
you know, there's still something there's still something very   
2:07:07   
um like inefficient is not the the right   
2:07:12   
word, but it's just like like when we say we're collecting a lot of data   
2:07:21   
You know when when you're thinking about the complexity of the system under study   
2:07:31   
like it's a very um it's a it's a very sparse sample   
2:07:39   
of the of the process or you know of of the system. potentially a sparse sample of   
2:07:47   
the of even like the process under study, right? You know what I mean? Yeah. Like like like you know it's one of   
2:07:55   
these things where um again I I I feel like it's got to be   
2:08:01   
somebody who's who's done a better job of of   
2:08:09   
you know stating stating this problem. But like again like it's like it's like   
2:08:14   
it's not that we're collecting the wrong data. It's just like like we don't have the systems that are it's going back to   
2:08:21   
kind of like the original brain initiative, you know, vision, right? Like like h how how can we   
2:08:30   
collect data from all cells, right? Yeah. Like like all the cells all the time,   
2:08:38   
you know? But but but again like when you say collecting data from the cell like like what do you mean right? And   
2:08:45   
usually what we mean is like like a particular modality that's picking up a particular   
2:08:52   
uh particular part of a particular process. Yeah. You know   
2:08:57   
and and it's not the Yeah. the the   
2:09:04   
um it's not even close to like the system   
2:09:10   
of interest you know I mean like the system you know yeah I think it's it's basically a case   
2:09:16   
of model abstraction but applied to like variables that you're collecting so like   
2:09:22   
you know I could measure every possible source of data in a cell which would be   
2:09:27   
every gene being expressed a sequence of every gene physiological processes,   
2:09:33   
behavior, but only some of those are relevant really to what I want to know, which is like uh what is the neuron   
2:09:40   
doing and how does it connect to other neurons because some of this is noise, some of it is just kind of like   
2:09:46   
superolous to the greater process. So, we don't need that although maybe we do   
2:09:52   
need that if we want to look at the single cell. So we get this right and   
2:09:57   
you know but then it's also expensive to collect a lot of data like that. So the question is how do we get it to the most   
2:10:04   
relevant set of features and then collect those data. Right. Right. I mean it you know it's it's   
2:10:12   
almost like we're collecting more data to know what data we need to   
2:10:17   
and then collect more data. Not not not not to you know it's not like we need to   
2:10:24   
scale right. Yeah. It's like we're still we're more trying to to to to   
2:10:33   
get the highlevel view so that we know what to to actually hone in on, you   
2:10:40   
know. Yeah. Um um yeah. Anyway, the the I just want to   
2:10:47   
mention one um uh one person who at least tries to   
2:10:55   
I mean this is this was his talk when he came to the neuroson at the tower and   
2:11:00   
this is this is co-hosted with the foresight institute right   
2:11:06   
um so I think it's Max Cannon like spell with a K and um uh he's a student of   
2:11:14   
he's a PhD student of um um   
2:11:20   
uh is it go poly? Um do you know that guy   
2:11:25   
I'm talking about? He's like he's a condensed matter physicist who's now a neuroscientist.   
2:11:31   
Um, anyway, I I'll I'll find I'll find the the the right length, but but his talk   
2:11:39   
was basically about um idealized   
2:11:46   
BCI in the sense that like what if I had a   
2:11:51   
perfect information channel like like what what you know like if I had the   
2:11:56   
information that you're talking about of like like all cell activity that's   
2:12:02   
Um, it it reminded me a lot of the CMU professor um, whose whose name I'm not gonna um,   
2:12:11   
be able to get right at this time, but who talks a lot about like idealized um,   
2:12:18   
uh, idealized alignment in terms of um,   
2:12:24   
trying to to you know and like like in multi- aent systems that they need to   
2:12:30   
communicate like you need the the agents to communicate with each other so that they   
2:12:36   
are aligned. Yeah. And that like like what happens if you   
2:12:42   
start thinking about this just theoretically and some some interesting some interesting um interesting   
2:12:50   
conclusions that come from that in terms of like like is that scalable? And you   
2:12:57   
know like if you're getting you know exponential growth then you know this this is   
2:13:05   
perhaps like like you obviously need a different approach um because there's   
2:13:11   
just no way that um that alignment is informationally possible.   
2:13:17   
Yeah. Yeah. Like like and and Matt Cannon is trying to kind of like do the same thing   
2:13:22   
but like in terms of what if I had this kind of perfect   
2:13:27   
um BCI system, right? You know, like what what are some of the kind of scaling properties and problems   
2:13:35   
that would come you know, imagining this kind of thought experiment   
2:13:41   
that that I thought was useful and and like his his advisor is this Yeah. is   
2:13:46   
like a very physics of neuroscience researcher also someone pitching at   
2:13:54   
foresight alongside you know cording. Yeah.   
2:14:00   
So anyway, I'll try and find some I'll try and find some uh   
2:14:07   
some links on this in terms of thanks for the Slack. Yeah.   
2:14:14   
All right, that's great. Well, I think that's all for today. Um had pretty good conversation here about   
2:14:21   
all these issues. Um we'll have to kind of spool this out a little bit and   
2:14:26   
revisit some of these things. of course the open source sustainability stuff we're presenting on that this fall and   
2:14:34   
you know maybe we uh we also have this pre-print of course it needs to be updated and you know maybe another paper   
2:14:40   
we could write on it um maybe from this more kind of theoretical   
2:14:45   
perspective of like you know what we're actually dealing with um but yeah okay   
2:14:52   
yeah so maybe that's something to do for upcoming   
2:14:58   
meetings that that that would be that would be awesome. Um yeah, because I think   
2:15:04   
there's there's I I don't think there's anything formally written up about some of this.   
2:15:10   
Um and um yeah, and as well as just to   
2:15:15   
say um there's also some good meetings next week that that we can be talking   
2:15:22   
about. Um um I'm I'm blanking on them right now, but   
2:15:31   
we should check the golfer participation.   
2:15:38   
I I think Big Brain is coming up. Big Brain. Big Brain. I mean, that's in that's in Europe, but   
2:15:44   
hopefully they'll have everything online. Um the brain brain modes 2025.   
2:15:51   
I I don't know if you did you see the um the video list off of that?   
2:15:58   
I I didn't check it out. I did see it in the channel. Okay, good, good, good, good. Yeah. So,   
2:16:04   
and the cool thing being that John was one of the organizers. So, John Griffith is one of the incoming board members X.   
2:16:13   
Um, and uh I'll share another playlist where you have uh him and his band doing   
2:16:19   
some funk songs in the beginning too. Anyway, but but no, that that would be   
2:16:25   
great uh Bradley to to think about some of those things   
2:16:31   
theoretical theoretical or you know thought thought experiments   
2:16:38   
and what they what they teach us on some of these issues.   
2:16:43   
That sounds great. All right. Thanks. Have a good week.   
2:16:48   
Take care. Take care.   
