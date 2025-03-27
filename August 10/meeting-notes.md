## Meeting Recording

[YouTube link](https://youtu.be/wn48fGpval0)

## Mastodon thread

[link](https://neuromatch.social/@OREL/112939996417239455)

## NOTES
Trevor —> idea turned out as a dead-end. Sonogenetics (https://www.nature.com/articles/ncomms9264), trigger neuronal modulation.

next month — organic collaborations. Infrastructure for wet lab.

braingeneers.ucsc.edu — BioE, developmental genomics, make lab automation.

make lab automation hardware, open-source.

UCSC innovation group — all open-source.


$5k grant for infrastructure.

Braingeneers — scalability in cultures, electrophysiology of organoids.

rat cells — UCSC, Muotri, UCSD — semi-automated protocol).

Madeline Lancaster — network dynamics —> change in oprganoids, multi-cellular dynamics.

Qs: change in information-theoretic complexity.


2018 paper — Muotri, Voytek.

2019 paper — Santa Barbara group


Electrophysiology— MEA — measure local activity. Also Ca+ imaging. Grow on top of MEAs.

Sarrah: small things for GSoC.

use an LLM to create more issues. What if it creates garbage, duplicates issues?

implement a template, step-by-step.

first LLM call, create a non-conflicting issue.

combined to create the final issue.


Don’t need to ad human-in-the-loop. Code quality rating — AutoCodeRover.

personalization part — basic storyline.

Jesse — good week, busy times.

general updates: things for JoPro.

brain organoids — how do we make a more concrete project description.


Admin work/functional Project Mgmt:

activities in Boston? Which will bear fruit?


NYCWiC — a few of the upstate cities are in the running.

mentoring projects — mental health working group.


Neuromatch — summer school, impact scholars (continuing projects).

progressive in how to make education accessible.

workshop — focused research organizations (in between industry and academia).

Related to Specula technologies. What can you do without a lot of funding. 

RFP (informal STEM learning).

celsius, well-aligned with Orthogonal (formalize to be a partner).

Project Mgmt stuff will happen Spring 2025. Model Builder stuff will be coming up in the Fall of 2024.

Neuroacademy UWE science institute.

Flock to Fedora event. More to do here.


Along the lines of Neurorobotics:

route-finding, 2-D maze, virtual rat, SNN model.

makes Neuroscience an Engineering field. Engineering things that seem so fundamental to us.
Dynamic Causal Modeling — relate to brain imaging — brain networks.

world models — secret sauce, tradeoffs in the RL machinery.

what does computational tractability mean in the context of the brain?

what was Sutton (RL) trying to accommodate with temporal differencing?


Alberta plan — DeepMind Alberta. 

fine-tuning, understand the issues better.

reformulation of the problem.

Ryan Smith — Active Inference (tradeoffs).

bottom-up neural models, higher-level task. In an RL context.


Build-a-Cell. Single-cell organism —> real-time behavior action.

Romain Brette — Paramecium, single-cell spatial cognition (navigation, taxis).

understanding HC without understanding evolutionary context.

bird migration (Jammer), hippocampus — part of a larger network.

complexity used for  other cognitive tasks.


History of Dopamine: attach paper on RL aspects of reward.

not replicating what the brain is intrinsically doing.


Read Montague paper from 1997 — relate a new model to Reinforcement Learning.





Hussain Ather
Hussain Ather says:
Hey all 
9:04

Sarrah Bastawala
Sarrah Bastawala says:
Hey everyone 
9:09

Jes2
Jes2 says:
If you want to bring a bit of structure to the organoids project, or make some description of its aims, im happy to do that; been doing a lot of that work lately 
9:11

Sarrah Bastawala
Sarrah Bastawala says:
have to leave, thanks for the advice and the meet ! 
9:43

Jes2
Jes2 says:
👍 
9:47

Trevor Tanner
Trevor Tanner says:
Very cool paper. Thanks for presenting 
10:30

Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://braingeneers.ucsc.edu/
 
Morgan Hough (he/him) says:
https://kvoitiuk.github.io/
 
Morgan Hough (he/him) says:
https://scholar.google.com/citations?user=j2zeZT4AAAAJ&hl=en
 
Morgan Hough (he/him) says:
https://www.nature.com/articles/s41596-024-00994-0
 
10:49

Trevor Tanner (desktop)
Trevor Tanner (desktop) says:
https://www.biorxiv.org/content/10.1101/2023.03.02.530856v1

## TRANSCRIPT
     
Transcript     
0:00     
hello morning morning for a few more people here there we go welcome Trevor     
0:07     
thank you morning     
0:13     
morning right so yeah we uh welcome     
0:18     
to meeting uh we didn't have     
0:24     
a open source meeting yesterday um but we did have a div one     
0:30     
meeting last week so D.A worm you know we covered a number of topics uh kind of     
0:37     
in celegans molecular biology uh talking about compy cell 3D     
0:43     
uh one of the people who attend the meeting regularly went to the com Pell 3D workshop and then we talked a little     
0:50     
bit more about modeling and so it was a really uh nice     
0:55     
set of discussions uh yeah so we didn't have     
1:01     
our uh cognition Futures nor our cybernetics meeting we'll have to pick     
1:07     
those up in a few weeks so we'll see how that     
1:12     
goes okay uh any     
1:22     
updates I'm not quite ready but I I've got some updates okay we'll come back to     
1:28     
that later uh Hussein or     
1:36     
Trevor um just yeah I I sent you that message I the idea I was thinking of um     
1:42     
unfortunately you I started delving into literature I actually spent few days and kind of turned out to a dead end um I've     
1:50     
got another idea I'm kind of playing around with um it's still gestating so I'm not quite sure if it's ready for um     
1:57     
public dissemination but that's me yeah well yeah that sounds you know it's sort     
2:03     
of that process of identifying a problem and seeing if it's viable and you don't want to spend time on it when it's not     
2:10     
viable so you know that's that's something that we can talk about um we don't have to do it within the next week     
2:17     
you know so sure I'm just gonna ask out of curiosity     
2:23     
do you um do you have um many like experimentalists collaborators that um     
2:31     
yeah just yeah I was just curious yeah uh we have in the past uh we don't it's     
2:38     
kind of hard to get uh you know a consistent collaboration there but that's something we could set up if     
2:44     
that's I mean certainly we have to find figure out how to do it     
2:50     
so yeah I was just curious there's um I kind of an idea in the realm of like Sono genetics I'm not sure if you're     
2:57     
familiar it's just you know using ultrasound um to like trigger neurom modulation and I think there are some     
3:03     
molecular opportunities for um maybe making better tools and so but anyways     
3:09     
yeah we can talk later this week um I don't know if that has if something like that would be of any interest to you     
3:16     
yeah that would that would be interesting definitely definitely that sounds interesting okay cool all right     
3:23     
that's positive I'm glad to hear that yeah yeah please you know it make sure     
3:30     
that you know we I don't want to like force you to like design a formal set of     
3:36     
experiments before we talk about it so you know if you're at a point where you think that it's worth kind of writing up     
3:43     
a one page or two page description then that would be great to look over talk     
3:49     
about awesome um okay the it yeah it's a     
3:55     
tricky thing because the of course the most tantalizing things require experiments so it's like the most that I     
4:02     
could do without experiments is just like a lit review but perhaps there's still value in something like that yeah     
4:09     
yeah well you have to decide what you want to do and what the questions are before you can get to the how to     
4:16     
implement it it's usually the case so you know there's some experiment we can     
4:21     
design but we have to know kind of what we're looking at and what kind of uh you know what we want to uh employ     
4:30     
to get the data that we     
4:35     
want if if I may ask you I know I I've heard like this talk of organoids going around what's all that about does     
4:42     
someone like work with organoids in here well uh Morgan is attempting to set up     
4:47     
an organoid collaboration so I've I've been interested in organoids for quite a     
4:52     
while and Morgan is actually working on doing some wet lab collaboration so Morgan did you want to say more yeah     
5:00     
that's that's one of the things that we're setting up here in San Francisco but yeah we're still in the     
5:07     
process of getting our wet lab space up and running um so hopeful hopefully by     
5:13     
next month that that will be the case um yeah we're we're supposed to have our open house I think the     
5:20     
20 I don't have a calendar but 22nd um coming     
5:28     
up yeah but you know it'll still be some time from that right     
5:34     
so um organoid culture when you look at like the kind of you know um through     
5:40     
organized culture that we're hoping to do um um still has some some infrastructure     
5:50     
requirements that that were are not quite at yet but um I should be um     
5:56     
visiting UCSC pretty soon um and uh there's a brain Engineers so     
6:04     
bra engineers. ucsc.edu um you can find uh the yeah the work of     
6:13     
um uh is it's like a I don't know how to describe it a subgroup in The Institute     
6:20     
of genomics um a special interest     
6:27     
group I'm not sure formally what the very Engineers are but um um but     
6:34     
definitely like a bioe component to as well as as it's like a bioe group     
6:40     
together with some you know more Developmental and genomic groups um and     
6:49     
the the nice thing about the brain Jers versus the some of the um some of the     
6:55     
other like UC see San Francisco or stford groups is that     
7:00     
they make all their um lab automation Hardware     
7:06     
U they're they're publishing that um plans and designs for all of that     
7:13     
Hardware as well in in an open source fashion so um that gives us with an eye     
7:22     
to you know as you see with lab automation with an eye to     
7:27     
scalability right um and with an additional eye to     
7:38     
um making cloud cloud enabled     
7:43     
research um because uh yeah which is which is really separate from the lab     
7:49     
alation but the one of the piis um uh     
7:55     
who his name I forget right now you know has a lot of um     
8:01     
is from uh Bolivia and so one of the     
8:07     
things that they've done is you know make all this Hardware     
8:13     
um very very automated uh but then they've also made it um     
8:21     
Cloud accessible so that students in Bolivia where they don't have access to     
8:27     
this kind of wet lab uh infrastructure are are able to um do     
8:34     
their own experiments so um and yeah uh     
8:39     
Bradley and I have uh had at least one um jitsy call with um with Karina vuk uh     
8:49     
who's the um is the first author I she's finishing up her her grad school and she     
8:58     
uh she's first off on this this kind of op Source Hardware infrastructure for     
9:04     
for organizes um um but uh yeah really interesting group and and at our last at     
9:12     
the last Celsius open house U I got to meet someone from The ucsc's Innovation     
9:19     
group so I think in general that's the the the group that's you know kind of     
9:26     
marketing the the University's IP in this case it's all open open source or     
9:32     
you know publicly available stuff but um but but still yeah they're they're very     
9:39     
keen to um yeah help help raise profile of of any of the universities work and     
9:48     
um so we're definitely um getting some you know Elliot Roth is our     
9:56     
um is another you know principle at at Celsius and so we just got a $55,000     
10:01     
grant for some of the infrastructure costs to um in addition you know that a     
10:07     
lot of it's 3D printable and um yeah so     
10:13     
I'll I'll I'll drop a link in the chat for you their TR thanks no I appreciate it is     
10:20     
um it sounds very impressive um is there a particular Focus um sorry I this     
10:27     
probably pretty so what are we yeah yeah so so     
10:32     
um when when when I think about what we're like     
10:39     
specifically targeting in terms of the science at this point um yeah brain BR     
10:45     
Engineers have covered a lot of what what we do want in terms of we want um a     
10:52     
lot more Automation and and a lot more scalability in terms of culture but but     
10:59     
the the real focus is on uh electrophysiology of of the organizes     
11:05     
and so in terms of a protocol um so one that that is a     
11:13     
protocol or at least you know they've they've done this for some um some rat     
11:21     
cells um at UCSC um uh but the the protocol we would     
11:30     
hopefully be able to reach is is from um uh San Diego's um Allison MRI and and     
11:40     
you know peripherally I mean in terms of electrophysiology um analysis of Bradley     
11:47     
voytech down in San Diego but but just this     
11:54     
spring um Alison you know winry lab uh     
11:59     
published I forget what the what did they call it a     
12:09     
semi blanking on the exact title but it's something it's something funny like     
12:15     
semi-automated protocol I forget yeah uh     
12:20     
it's something like semi-guided like I've never never heard semi     
12:26     
attached to this particular word but um uh uh there's a     
12:34     
um they have put together a kind of um publish a protocol in terms of electri     
12:40     
physiology and it one of the you know kind of not I don't want to say controversial     
12:47     
um one of the um surprising findings of     
12:53     
the um the early L voytech work uh     
12:59     
had to do with the the our spectrum of the     
13:04     
electrophysiology organoid after after um like 80     
13:12     
Days uh so you know close to three months yeah um and you know perhaps perhaps     
13:21     
even longer but um you know what what um mine Lancaster     
13:27     
has has pointed out one of the ways which you can     
13:33     
really um one of the ways that you could really     
13:41     
Mark you know a change in the organoids um is by its Network Dynamics um and and     
13:52     
as as she points out you know it it's it's when the organized starting to     
14:00     
behave or wait know when the when the multicellular Dynamics are starting to     
14:06     
behave in in you know real Network ways is is you know to her is the sign of of     
14:15     
what you know what you're really trying to achieve right so there's just a     
14:21     
number of a number of questions about you know changes in kind of um     
14:27     
information theoretic measur um yeah Network complexity Etc that come     
14:35     
that that that we can you know track with good automated um um     
14:42     
electrophysiological yeah recordings um     
14:48     
and you know it that's that's like our our very modest goals at this point and     
14:54     
just kind to some degree just replicating that work and then and the     
14:59     
work of some some other groups that are that are related to that um uh so then     
15:05     
there's like a 20 the the first paper was like 2018 paper with M voytech um     
15:14     
but then there was like a 2020 paper that um that came out of Santa Barbara     
15:22     
um and that had Shri Shri Katan nagaraj     
15:29     
director uh at UCSF in terms of the electrophysiological analysis anyway     
15:37     
just just broad stroks on that if I may ask when you say     
15:42     
electrophysiological analysis are you talking like patch clamp or are you talking like calcium     
15:48     
Imaging no no I mean that would be like so we we are     
15:55     
now uh uh I should say like this recent discussion I had with um with a group in     
16:02     
Bristol um but uh this is like um uh     
16:08     
meas you know um so just just mult yeah     
16:15     
just electric arrays um that uh and so     
16:21     
one of the one of the interesting or one of the questions we have in terms of     
16:27     
being able to do these kinds of long-term recordings is is you know do     
16:33     
do you grow do you grow on meas do you are you able to manipulate organoids to     
16:40     
to move them around in some sort of um you know good mechanical fashion um um     
16:49     
and yeah a number of things about doing those recordings that again it brought up in in Katarina's paper um that this     
16:58     
is buy your archive paper so this is this is the the yeah     
17:05     
currently currently unpublished but but on archive um and they're using um it's the     
17:14     
one one device that is still you know commercial um so there there it's     
17:23     
um Maxwell biosystems I think Nea     
17:31     
yeah thank you for describing that sounds interesting yeah yeah and and     
17:37     
they've got um they've got some plinary data or you know they' they've got some some example recordings um so again like     
17:46     
her you know it's been updated since then but it's like first hit archive     
17:52     
like March 17th but anyway I I'll drop some links in just a minute yeah yeah     
17:58     
thank you for the that update organ organoids we have a brain organoids Channel too in the slacks it's brain-     
18:05     
organoids and we've done put a lot of things in there a lot of things to re over um and so yeah that's like you know     
18:13     
we're really kind of trying to figure out how to do this and how to use this to answer some questions uh in the     
18:20     
meetings we've you know tried to look at different papers protocols but also you know we looked at the um one where they     
18:27     
were playing video games with a organoid I can't remember what they called that     
18:32     
well that yeah that was dish brain dish brain right so that was 2D culture yeah     
18:39     
2D culture so yeah there were a lot of things that one could do but it's just seeing what you know what's out there     
18:45     
and trying to find things that we can do uh given our resources and uh     
18:53     
yeah okay so uh looks like Hussein was here I don't know if he left     
18:59     
is gonna come back but hello hsein hello Sara and Jesse so yeah I don't know oh     
19:07     
hi I don't know if you want to give an update Sara um you're ready uh yeah yeah     
19:14     
sure uh yeah so basically like um I'll just share my screen     
19:22     
so uh yeah like I just thought today I'll kind of like I've been working on a few     
19:29     
small small things and I've submitted like two pull requests as well so like     
19:35     
this was the first pull request and this is kind of the graph that I     
19:41     
um have so far like uh two metrics that are being     
19:46     
draft uh for the project and uh so you can go through this full request anybody is interested     
19:54     
and then another request that I just submitted regarding the issue Creator agent     
19:59     
uh so I just thought I'll give a few like uh kind of demos on what I'm like     
20:06     
working with and how it kind of looks uh so the first thing that like I was doing     
20:12     
last week as well and then I completed this week uh was the issue Creator agent     
20:17     
in the open source sustainability project uh so basically like even last     
20:23     
time I think Bradley had this uh thought like uh basically I'm just trying to use     
20:29     
an llm to create more issues so that the more issues there are the longer uh the     
20:35     
more time steps we have in our simulation and the long with our uh simulation can run uh but then one     
20:42     
thought was that what if it just um kind of create some garbage and another thing     
20:48     
that I had nagging was what if it kind of just duplicates uh issues that I     
20:54     
already have uh because both of those would be bad it generating garbage would be bad because um it couldn't put any     
21:02     
good score to that and that would lead in like bad overall metrics and it if it uh     
21:12     
basically if it uh does something that existing issues already have uh that     
21:17     
would be bad because uh it would kind of conflict with u like the code would be     
21:25     
there already and then auto code R would not know what to do it would not be able to generate proper responses so both of     
21:32     
those things would be bad which is why I kind of uh made this issue Creator agent in the in the way that it generates     
21:39     
everything systematically like step by step so instead of just telling it to generate a whole issue uh the first     
21:46     
thing I do is pass the existing issues like whatever existing issues I have I     
21:51     
take them so for example like I had run this command with the with this command     
21:57     
line argument of for so I already had three issues because I already have three issues and I want run     
22:03     
the simulation with four issues the issue Creator agent tries to create the one remaining issue so the first thing     
22:10     
it does for that is it checks all the existing issues and it passes like the     
22:15     
basic title and description that these issues have uh like it takes the first few sentences of each of these files uh     
22:23     
and it stores that here um and     
22:29     
uh what this does is these existing issue titles are given to the first llm     
22:35     
call which is just to generate the issue title so it is just told that uh these     
22:40     
are the existing issues and you have to create something that does not conflict with these and it's also given the     
22:46     
existing code from the python file so based on that it comes up with an issue     
22:52     
title so the this is the issue title that it came up with which was to implement the modulus operator     
22:58     
functional in the calculator class uh once this issue title is done that is given to the next the title is given to     
23:04     
the next LM call and it is told to create a description for this uh so it makes this basic description then that     
23:11     
title and description are given to another llm call uh that generates some basic example code uh then that is given     
23:19     
to another LM call that uh checks like basic that says like what other     
23:26     
resources did it check and that is given to another LM call that uh generate some     
23:32     
System Info for where this was issue was checked Etc and then all of this is     
23:37     
combined and given to an LM call that creates the final um     
23:44     
issue so up here like and that everything is combined in like this way     
23:49     
I can like be sure that it's not generating Gage because it was given prompts for each and everything and I     
23:56     
can also be sure that it's not going to conflict with the existing exting issues uh the human in the loop can still be     
24:02     
added but like it is not a necessity for now like it's generating some pretty     
24:07     
good uh responses for now and then this is like just the rest of the simulation     
24:13     
with without the without ACR invoked uh so it's just like a without the actual     
24:20     
code solving happening a basic this there was also this code quality thing that I     
24:25     
added uh where it basically like rates the kind of gives a review to what the     
24:33     
code P request was and based on that it passes a code quality um and uh yeah there was another     
24:42     
demo that I had going on this is what happens like right now I ran this with again with issues four and I already had     
24:48     
four issues generated so this basically just ran uh on its own it didn't     
24:54     
generate any new issue it started solving these issues uh did the llm     
25:00     
bidding part and started the auto Cod Rover in the background which is     
25:05     
actually solving the code so this is everything from aut code Rover and like     
25:11     
this is still working um so this I wanted to like like I have another one with this completed     
25:18     
but the graph of it got lost so basically like even while this is generating the graph keeps on building     
25:24     
like once the first time step is done the metrics for the first time step will show up this CL so that is what I wanted     
25:30     
to show and like how it's like all coming together now and then another     
25:36     
thing that I'm working on right now is the personalization part uh basically     
25:41     
like for each uh agent whether it's a contributor agent or a maintainer agent     
25:46     
uh giving it like some basic storyline So currently I'm working on uh     
25:52     
like currently I've done where I've created a system message for that uh     
25:57     
agent uh basically uh the system message gives it like the system message is what     
26:05     
is given before any llm call is made to this particular llm so this is and it is     
26:11     
like appended to every llm call so basically the system message is going to     
26:17     
help that help it remember like what its experience is what why it is like why     
26:24     
this agent is there in this particular simulation and hopefully like I'll see better results in the metrics and even     
26:31     
in the um bidding part especially because of this personalization once it's completed and integrated uh so like     
26:38     
now I'm just going to focus on trying to get this personalization and some other stuff done and then focus on a bit of     
26:46     
the documentation like I have everything documented till now in the terms of like read me and blogs um but I'll try to     
26:54     
like get everything accumulated at one place now and all the P request links     
27:01     
and everything like that all right that's great uh thank you for the uh thank you for the update uh it was     
27:07     
great uh yeah I wanted to see where you were I I think I mentioned that you know as we come up to the end of gck uh which     
27:15     
is August 26 that's the deadline you know we need to kind of find a stopping     
27:20     
place so if we can find a stopping place where everything is you know we can wrap     
27:26     
things up and get something approximating a submission to Google     
27:32     
then that's what we want to do so you know you may have things you want to do sort of you know there a lot of things     
27:38     
you want to do to your project right uh I would like make find a stopping point where I kind of like stop what I'm     
27:45     
doing make sure it's working and then you know make sure that the documentation is sound and then make     
27:51     
your submission from that and then you know later on we can work on more     
27:56     
details so we they just want you to find like a stopping point for the project I     
28:02     
think I like a lot of the stuff you're doing I think you're making some progress on kind of you know you have     
28:07     
the framework and then you're kind of finding ways to make sure that you can verify what's going on so that's that's     
28:14     
good because of course if you just generate larger language model text you     
28:19     
know it might just be like you know you might get duplicates you might get garbage Etc so having that sort of uh     
28:27     
you you know those checks that can be implemented as good and you know we don't have to like     
28:34     
go we don't have to make like this huge elaborate solution it's just something that will kind of give us a way to do     
28:40     
that and we can maybe you know next year or after the end of the project we can     
28:46     
come up with better methods for it so I wouldn't worry about that too much just to have something that's     
28:53     
working right definitely so yeah in the next week I'll try to kind of do like as said get to a stopping point and just     
29:01     
integrate everything and then after that like I'll just stop actually and you     
29:06     
know just focus on the documentation because that's definitely there where like I always feel like there's     
29:11     
something I can add something I can add uh so yeah for now I'll just get to like     
29:17     
a good enough point and stop it yeah tempor till we can just like finish all     
29:25     
the documentation and get it all done and then come back yeah and you're welcome to continue     
29:31     
working on the project if you want to after the looks pretty good there's like a lot     
29:38     
of things that I had that I kind of you know wanted to add there was this R thing that I explored uh right in the     
29:45     
beginning it's kind of like now is not there's not enough time and not enough     
29:51     
scope to integrate that for like for the G period but that's definitely something I want to try to integrate even later     
29:59     
and even like other ways that LMS could be used like I remember you     
30:04     
mentioning brbg Vehicles like a very long time ago so I've not been able to look at that while I was working on this     
30:11     
but definitely later once the G period is over I would like to work     
30:17     
on yeah yeah that' be good and of course what you can do for those things is you     
30:23     
know kind of sketch out what the issues will be for that so you know you don't need that doesn't need your first     
30:28     
priority but to just make notes about what the issue should be and then you know we'll populate the project word     
30:34     
that we have been using for the open source meetings we can put those on there and you know then then you know     
30:40     
they can either you can either address them later or someone else can address them just so that we know what the open     
30:46     
issues are you know where we might want to improve definitely right that's very good yeah     
30:53     
I'll I'll that as well okay     
30:58     
right thank you Sarah thank you yeah so yeah we're coming along on G so we're     
31:04     
kind of coming to the end of that uh at the end of the month so and I actually for D.A worm my two students there I've     
31:11     
gotten an extension for a couple more weeks so they they're working on things as well their projects are a little not     
31:18     
as far along as Sara so I'm giving them an extension so but you know that's the     
31:24     
same process uh when you you know when you get to the end of your project you want to prioritize the things that are     
31:31     
you know doable maybe want to have maybe you know or are kind of reaches and you     
31:38     
know you do the ones that are the easiest you finish that up and then you make issues for the things that you'd     
31:44     
like to have or that are reach issues and those are typically you know things that someone you can do later or someone     
31:51     
else can do later as long as those things are codified in the in the project space     
31:58     
so we'll be coming to you know this will be fun I think they're all very good G     
32:03     
projects and I can't wait to see the sort of submissions and you know I think we've     
32:09     
had a lot of nice demos this summer different types of things that people have been doing hey can you hear me all     
32:16     
right yeah uh I'm good uh it's been     
32:22     
a a good week mostly busy busy times     
32:31     
um yeah uh I don't I know we I'm curious as to what else we wanted     
32:38     
to talk about today that might affect some things that I do or don't talk about um but for just very general     
32:44     
updates uh just a lot of things for joofo have     
32:49     
been coming along uh I'm just doing a major U like I don't know just call it     
32:56     
an infrastructure update um and like a byproduct of that is sort     
33:03     
of the website and I mentioned I mentioned in this chat here I said to     
33:10     
Morgan like if you want to talk about like getting I don't know if there is     
33:15     
anything written up like for what when we say brain organized GL like what does it mean just a slack Channel but like if     
33:22     
we want to I don't want to say formalize it might be a scary word at this point     
33:27     
but basically make like a project description about what is trying to be done and where it's at like that's     
33:33     
something that I'm interested in helping out with I mean I've been in the discussions for a while anyway but more     
33:40     
like I'm doing a whole lot of that uh recently and trying to kind of make     
33:46     
things a little more tenable to both you know it's it's this     
33:55     
fine line between like administrative work and functional project     
34:00     
management and general Clarity     
34:06     
of like what what is happening um so that's that's uh the last two weeks     
34:14     
maybe even three weeks I've really been uh focusing on that     
34:20     
stuff um and this this week um     
34:28     
has been exciting because uh I'm I'm really starting to     
34:34     
reach out again to many I guess uh I don't know     
34:40     
potential former and potential partnerhip     
34:46     
collaborators um we've done some things with you all but in the past and I'm I'm     
34:51     
kind of following up there again uh I have some plans to go to uh     
34:58     
UC San Diego where I'm currently a student but I'm not I'm basically     
35:04     
remote uh but this in September there's a few events I intend to be going to     
35:10     
there and I don't think we're going to get I don't think I'm gonna get any like     
35:16     
UCSD intern students this fall but I think a in the future and     
35:22     
ahead that is more of an option um     
35:28     
there's a lot of things happening in in the Boston area so     
35:34     
um what what what will bear fruit and what will the fruit look like you know we don't really know yet but     
35:43     
um but things are happening and it's cool um that's that's the shortest version of     
35:50     
my updates um there's uh herwick     
35:58     
uh which is the New York celebration of women Computing event uh the update on that     
36:06     
is uh we're pretty close to selecting a venue it's kind of     
36:12     
between a few of the bigger like not New York City but a few of the upstate     
36:17     
cities we're looking at and I'm excited because I think this is     
36:24     
the year that we have enough support as we all may know if you're if you're one     
36:31     
person trying to make a change at Institution for how things are working it's tough but if you get an ally or two     
36:38     
who are interested and able to make that change or or invest in doing it that     
36:44     
that that's a big ball game changer uh so I think this year will be     
36:50     
really good for like building a little more Community around Nick Wick and then also     
36:55     
specifically uh there's some mentoring projects that are I think fit well with what what we've done in the lab what     
37:01     
we're trying to do and what what I'm trying to do with Joe Pro so um that's     
37:07     
exciting uh we had some meetings with the mental health working group     
37:13     
today uh well yesterday and also today um and and some other like just     
37:20     
Joe Pro edmin stuff um had we're fortunate to have a kind of like a     
37:26     
formal fan not not formal an informal but fancy inperson meeting     
37:33     
um here in Boston and uh it went it went well so that's     
37:40     
that's the short version of it um there's also uh one other thing I'm really interested in trying to do uh     
37:46     
some of some of like opportunities I guess the things to keep in mind are um     
37:52     
for people who want to be um for those interested in neurom match     
37:57     
which is sort of the I guess former conference Series in current neurom     
38:02     
match Academy Summer School uh this is the first time they've done certain     
38:08     
courses they have a new neuro AI course that just wrapped up I was a professional     
38:14     
development Mentor I think I think Bradley was more full Mentor for the projects um but     
38:23     
that's has ended but there's this thing called uh impact Scholars uh     
38:30     
which uh is sort of a continuation it's the thing that everybody always wanted which was oh I love my project love neur     
38:37     
match can we do a longer more uh a longer more drawn out thing than just     
38:43     
two or three weeks crammed uh and that that is impact     
38:49     
Scholars for my understanding so there's if you if you were a student you kind of get the opportunity to continue your     
38:54     
project through I think March of next year but there's also a big call for mentors     
39:00     
again because mentors will meet I think somewhat regularly it's sort of like part-time job though so get a commitment     
39:07     
but they need mentors to help facilitate the projects and things like that grow uh so definitely look into that if     
39:14     
you're interested um I might I'm not sure I'm really qualified I am I am for like     
39:20     
everything that's not technical I'm not I don't think I would     
39:25     
be a good uh like you know what it's so funny     
39:31     
because one of this one when I was a when I was a project a project uh uh the the professional development     
39:38     
Mentor two one of my mentees was like this sort of 10e track assistant     
39:43     
professor um and I like well I'm not quite I'm not quite there yet honestly     
39:49     
in my my my computational Neuroscience capabilities     
39:54     
um but like in terms of other things and navigating spaces and just project     
40:00     
development and that I feel like okay I could do that but so sort of like it's a little bit     
40:06     
unclear I might ask them a bit more like are you basically looking specifically     
40:12     
for like the mentors for the projects to continue on and get paid for it or is it     
40:18     
like a little bit more inclusive of the professional development lens I don't know but either way neurom match like is     
40:25     
um something to check out and for those who don't know anything about them I'll just say they're very Progressive in     
40:32     
terms of how they're trying to make education accessible and they're just a fun     
40:37     
Innovative space to see uh what's going on and they do some cool stuff so check     
40:44     
that out um similarly or my last sort of General update is     
40:50     
um there's always you know kind of events of things popping up but um     
40:57     
one of them I'm particularly interested in is sort of a workshop I forget who hosts it so this might not be the most     
41:04     
decent there's upcoming potential workshop for I think they're calling it something     
41:12     
like it's not focused research organization but it's something along     
41:17     
the lines of a research organization that's in between Academia and Industry     
41:23     
and isn't necessar like like somewhere in between those conventional jokes and I'm hoping to attend that I don't know     
41:30     
if I'll get accepted to it but I think it would help because you know if you don't know by now uh now you     
41:38     
know but like you're we are in like this sort of interesting parah     
41:43     
alt uh academic space and there's a lot of things in     
41:48     
that space But sometimes having you know the structure about what those are how     
41:54     
do you do how do you do what what part or what development of the research path or like pushing an idea or Theory or the     
42:01     
Outreach of an idea or Theory whatever like where what do you do with that so     
42:07     
um I'm I've been looking a bit into these um I don't know things like that and     
42:14     
there happens to be a workshop around such that's happening both one's in     
42:19     
Boston one's in San Francisco one's going to be virtual and I can't remember the name at this time I think I think it     
42:26     
was a Rel to specula Technologies but I don't know if it's them directly uh but suffice to say there's     
42:34     
some interesting stuff happening in that space um which fits well with at least     
42:39     
some of what joepro is trying to do or facilitate joepro not only as a sort of mentoring Branch but also like the sort     
42:47     
of project coordination incubation and development uh aspect so um and and you     
42:54     
know our unique let's say take AKA uh what can you do without a lot of     
43:00     
funding currently that's still useful um so yeah that's that's a that's a very     
43:06     
broad SWAT of of things but I'll leave it at that for now right that's great uh     
43:13     
yeah there are a lot of things there um it's like you're investigating of these spaces um seeing     
43:19     
how we can Implement uh you know different mentorship programs and different you     
43:27     
know ways to sort of Kickstart projects so that's great sort of um if I could add to that     
43:35     
um you know something that uh that Jesse has uh has at least expressed some     
43:42     
interest in that it would be awesome to get his help with which is um this     
43:48     
upcoming NSF um RFP on uh informal stem     
43:55     
learning and um the you know very seems very very U you     
44:02     
know very well aligned with both you     
44:08     
know neurot X and Celsius which are the groups that I kind of     
44:13     
originally um was with in terms of considering that but um but you know is     
44:20     
actually super well aligned with orthogonal right and and you know uh uh     
44:28     
I would still you know not not to push it but it would still it'd be great to     
44:33     
to potentially you know formalize orthogonal so that it could     
44:40     
be partner on something like that because I just to think you know this is     
44:45     
kind of a unique opportunity in terms of kind of making a case for informal     
44:50     
steming yeah and and the kind of the institutions that support it yeah and one one of the things about     
44:58     
this particular Grant is that um they they ask they encourage groups     
45:07     
to to to be to do submissions with like with multiple     
45:13     
organizations you know so like if if we can find overlap between LA groups like     
45:19     
they would they were particularly encouraging of that kind of that kind of     
45:25     
overlap that kind of coordination in this particular proposal just just just to mention that     
45:32     
too yeah well that's great U yeah and maybe we'll look into that more in the     
45:38     
fall as well so yeah I think it was last week Bradley     
45:45     
and I met a little bit to talk about future plans and stuff like that but I don't know if you're I there anything     
45:50     
for you to say yet about either the like model building stuff or the uh project management of course but     
45:58     
like I'm curious about those I'm happy to do what I can with any of those things um I think the the project     
46:07     
management one is in Spring but um yeah uh     
46:13     
just just those on my head right now so I wanted to mention them yeah well I mean I'm still moving forward with them     
46:20     
I'm just trying to you know I'll probably work on next few weeks so     
46:27     
yeah and you know I need to get materials together probably kind of come together as I'm doing it so but yeah I'm     
46:35     
going to get things together in the next few weeks at least to start off with and then we'll go     
46:40     
through it'll be more interact the model building will be more interactive than the project management but what I mean     
46:48     
by interactive is just kind of having like you know uh it's going to kind of     
46:53     
be self-guided I guess but um     
46:58     
okay so yeah I don't know Jesse uh I don't know if you had more to say or     
47:05     
something I'm going to do a few things here and then we'll maybe come back to whatever you wanted to do yeah not not     
47:12     
really not if I something comes up I'll let you know but I'm you're in clear     
47:17     
okay this is something that um Morgan attended I guess uh this is cognitive     
47:23     
computational Neuroscience this was in I guess like is this in Boston     
47:29     
or it was in Boston unfortunately I did not make it yeah so I got I got sucked into some     
47:38     
work here but um but all the videos uh it made all the all the Keynotes all the     
47:45     
talks available online which is awesome oh yeah this looks great um so yeah there sorry you     
47:52     
couldn't make it I yeah I know it's kind of hard but if you have all the the talks and you     
47:59     
know uh it's really interesting stuff here so uh comparing artificial and     
48:05     
biological networks reconciling the dichotomy between sharing tonian and hope felian views on neuro     
48:14     
computations uh varieties of human-like AI um we had a couple of Keynotes the     
48:21     
Fireside Chats um they had some contribut     
48:27     
talks so that looks interesting um what makes representations     
48:32     
useful so a lot of the things we've been talking about in this group and you know we haven't attended this but um     
48:40     
interesting stuff do you want to make any comments     
48:45     
about it Morgan any other comments so yeah it's uh Wonder     
48:52     
wonderful Keynotes um uh and uh     
48:57     
you know the uh what did they call them gen     
49:03     
General General adversarial     
49:08     
collaborations is their is their kind of famous thing um so I haven't um so far I     
49:16     
just caught the rust keynote and um yeah just haven't haven't dived in     
49:24     
the um neuro Academy was also um overlapped with     
49:31     
this you know so that's the two we um you know be before Nur match there     
49:38     
was Nur Academy okay um so that that is also all online that's from the uh udah     
49:47     
V Science Institute um so just the total um you know     
49:58     
to too much content this past together together with u you know     
50:04     
something came up in terms of neurotech opportunity that I'm just     
50:10     
trying to try and try and make something of for for neur Tech X while the while it would be beneficial so I I     
50:20     
got distracted and um yeah didn't make it to the east coast so the the other thing that's going on right now is is     
50:26     
the is the Fedora flock of Fedora so okay yeah uh unfortunately I did not     
50:33     
meet with the with the nador folks um which is which is too bad because     
50:39     
they're you know they're distributed all over the world right so uh anyway but sorry almost home     
50:47     
will be able to sit down okay talk more all right yeah thanks thanks for the     
50:54     
update this is something that I think came up in the slack I'm not really sure what channel uh this is from I think from     
51:03     
science science advances uh and this is uh spaces of weight and sequence a     
51:10     
theory of the hippocampus so you know we have like U hippocampus is well known for kind of     
51:17     
you know the different types of representations that exist in the hippocampus people have probed the     
51:23     
hippocampus in terms of memory terms of spal cognition you have different types of     
51:30     
Amnesia that have been studied in hippocampus and the medial temporal loob more generally you have all these     
51:36     
different types of uh you know Place cells and grid cells and things that     
51:42     
represent space spatial landmarks and things like that and so this is an     
51:48     
interesting theoretical article that sort of proposes that space that spatial     
51:54     
relationships are lat and sequence and so what does that mean we talked about you know latent spaces in um machine     
52:02     
learning and we know that like that's where you store all of the possible outcomes of some data set so you just     
52:09     
sample the lat and sequence and you see if you can find the correct uh     
52:15     
representation um so this is uh Elite George is is on this paper he's a very     
52:21     
famous person in machine learning some other people on it as well     
52:27     
uh the abstract reads fascinating phenomena such as Landmark Vector cells     
52:33     
and splitter cells are frequently discovered in the hippocampus so these are you know     
52:39     
different types of cells that represent different aspects of space so you can     
52:45     
have Landmark cells Landmark Vector cells these splitter cells and I talked     
52:50     
about in the paper uh and so you know basically they proposed a bunch of different cell types     
52:57     
that represent different things in um you know in in this process of spatial     
53:03     
cognition uh without a unifying principle each experiment seemingly uncovers new anomalies or coding types     
53:11     
so in case you haven't kind of figured this out you know people have proposed a lot of different types of     
53:17     
representations or cell types that contribute to these repes representations but there isn't really a     
53:23     
unified theory of this um sort of thing so play cells were first proposed in     
53:29     
1978 and you know kind of people have there's been a Nobel Prize awarded in the last 15 years on uh on grid cells     
53:39     
and on some other types of aspects of spatial cognition and representation in     
53:44     
spatial cognition so this is a very uh people are very intrigued by this whole area and so this is giving us a theory     
53:52     
to guide us through this space um here we provide a unifying     
53:57     
principle that the mental representation of space which is with you know we have     
54:03     
these representations within our brains that allow us to represent things in the     
54:09     
world and in our brains and then operate on them so we have this mental representation that they argue that it's     
54:16     
an emergent property of latent higher order sequence learning so sequence     
54:21     
learning of course we know from uh you know language it's very important that language it's very important in     
54:28     
procedural learning because you're learning sequences you're learning procedures and in this case they're     
54:34     
talking about this being important for spatial cognition because you go from Landmark to Landmark or you go across     
54:40     
the space and you don't just you know navigate the whole thing at once you kind of navigate from point to point or     
54:48     
you kind of have to orient yourself and then navigate different you know according to different uh     
54:54     
orientations or you know of reference so becomes a sequence learning problem and     
55:00     
of course we have episodic memory in that has been will characterized in the hippocampus but we also have the     
55:07     
sequence learning that they're you know this is something that they're     
55:12     
proposing treating space as a sequence resolves numerous phenomena and suggests     
55:17     
that the place field mapping methodology that interprets sequential neuronal responses idian terms might itself be a     
55:26     
source of of anomalies um so I think we talked about like this a long time ago where they     
55:32     
have these different representations in hippocampus and you know it's not you know some people     
55:39     
proposed it's ukian of course I think we talked about ukian spaces um you know and in machine     
55:46     
learning and how we kind of assume ukian spaces and of course the world isn't     
55:51     
just Idan spaces it's maybe more higher dimensional than that and     
55:56     
so this is kind of where they're getting at um this whole idea of ukian spaces     
56:04     
are uket in terms being a problem for understanding the actual     
56:09     
representation so you know again like in machine learning Clan spaces are uh     
56:14     
limiting basically um our model clone structure causal graph so this is uh     
56:21     
cscg this is their model that they're introducing here employe higher order     
56:26     
graph scaffolding to learn latent representations by mapping aist egocentric sensory inputs to Unique     
56:35     
contexts so this is where we have this graph scaffolding where things are built on a graph you learn lat representations     
56:43     
you map uh egocentric means it's centered upon your body and then you're     
56:48     
looking outward um and so you're getting sensory inputs in an egocentric frame and you're     
56:55     
trying to apply those to unique contexts and you have you know you try to use     
57:01     
this sort of information to learn these late representations of the space and then I guess you sample from those     
57:08     
representations to guide you in your uh spatial learnings I guess uh so that's     
57:13     
basically what they're doing just you know there's a lot of jargon here but basically you're learning about the     
57:20     
spatial World by you know your sort of from your own point of view     
57:27     
and you have to like you know encounter different landmarks you have to build a representation of the space uh and you     
57:34     
know it's all kind of this thing that you build from your experience from your     
57:41     
egocentric experience um learning to compress sequential and episodic experiences so     
57:49     
remember I said episodic memory or kind of like you know different episodes in     
57:54     
space like if you see a certain object from a certain point of view that's an episodic     
58:00     
experience and the idea is you would put those together into a representation you have different episodic experiences and     
58:07     
you build a model from that you say okay this thing is here this thing is here     
58:12     
this thing is here and then you try to build a model around that saying okay how do how do these things related in     
58:20     
space um and then of course but you have to compress these because of course you know you learn many different spaces and     
58:27     
you only have so much hip a campus your EP campus doesn't mean okay that's not     
58:32     
true uh some people have uh there's this uh classic study about London taxi     
58:40     
drivers and that you know they're very expert at navigating their     
58:45     
environment and so the you know the evidence for this London taxi driver study was to look at the morphometrics     
58:53     
of the uh hippocampus and to show that it Row in in taxi drivers people who     
58:59     
experience you know episodic memories about the different streets in London all the time they drive down them they     
59:06     
know the shortcuts they figure out the how it's represented you know and so this is you know this is actually     
59:14     
leading to an enhanced sort of U growth in the tissue of the     
59:20     
hippocampus but still you know this isn't something that um you can do sort     
59:25     
of scale up based on the number of spaces that you have to learn so you have to compress this at some level so     
59:33     
um learning to compress sequential and episodic experiences using the Clone     
59:38     
structured CA and graph model yields allocentric cognitive Maps so allocentric cognitive maps are cognitive     
59:45     
maps that exist out in the environment not based on your own experience and so that's you know that's the kind of map     
59:52     
it's building that are suitable for planning introspection     
59:57     
consolidation and abstraction so all the things you would do with space you would plan you know how do I get from point A     
1:00:03     
to point B and it's not always the same way all the time you have to think about you know if there's traffic on this     
1:00:09     
street or that street where if there's like a detour that you have to make or if that space is even you know     
1:00:16     
continuous or discontinuous uh there's introspection so when you go and visit these places     
1:00:23     
what do you learn about it do you learn that like you know the representation is incomplete or what are you learning uh     
1:00:31     
consolidation of course meaning that you consolidate all this information as you learn it you consolidate it into a model     
1:00:38     
and then abstraction so being able to take space and kind of you know being     
1:00:45     
able to think about it in different ways so you know we have spatial representations of say our friendship     
1:00:52     
Network or spatial representations of um you know a place we've never visited     
1:00:59     
before there are a lot of ways we can abstract this out to other contexts so     
1:01:04     
while personal experience is important we can abstract it to other contexts and     
1:01:10     
you know we can do this kind of generalization by explicating the role     
1:01:15     
of idian play field mapping and demonstrating how lat and sequential representations unify Myriad observe     
1:01:22     
phenomena artwork positions the hip a campus and a sequence Center Centric Paradigm challenging the prevailing     
1:01:28     
space Centric view so they're saying that you know you have the space Centric view which is where you have all these     
1:01:35     
cells of code for different aspects of the space and you build these representations of the space what     
1:01:41     
they're saying is that you can actually have a sequence entric paradig where you take the sequence into account the     
1:01:47     
places you visit and you sample from a latent space to build those sequences so it's a different way of     
1:01:53     
thinking about what the hippocampus does and so you know this is of course you know this maybe I don't know how     
1:02:00     
controversial this is it might be quite controversial but um basically you know     
1:02:05     
a lot of the previous studies on the hippocampus we've sort of assigned a role in it for episodic memory so you     
1:02:13     
know building these kind of EP series of episodes in a in a spal     
1:02:18     
representation being able to do relational inference and fast learning um and so you know this is     
1:02:25     
important to understand stand uh our model suggests that place field maps need to be interpreted     
1:02:31     
carefully because they overlay sequential responses onto ukan Maps so     
1:02:37     
this is where um you know we we have a lot of things going on here I guess and     
1:02:45     
so uh you know we have to kind of think about it a little you know pretty carefully when we interpret the results     
1:02:52     
of any one place field now uh directly characterizing the play field maps in     
1:02:58     
terms of spatial and idity and Concepts could be a source of anomalies since the underlying phenomena are inherently     
1:03:03     
sequential and dynamic so again you know we have this aspect maybe a dynamical     
1:03:09     
systems where we're kind of building these spatial Maps but not thinking about how they evolve over time or how     
1:03:16     
information is acquired over time and integrated with them in in contrast uh cscg explicates     
1:03:24     
how the learning of sequential context gives rise to spatial representations that an agent can use to drive Behavior     
1:03:31     
without explicitly representing location coordinates so we don't want to have you know there's this kind of assumption in     
1:03:38     
a lot of spatial representations that exist um that you have to build location     
1:03:44     
coordinates for everything um you know certainly when we do robotic planning or robotic navigation you know you build     
1:03:51     
these models that are sort of geometric and they have these coordinates and you have to trans between the coordinates     
1:03:57     
for different contexts and you know there's no real evidence that we're building coordinates in our brains it's     
1:04:05     
just that that's kind of the Assumption because we have this model this cian model this this model that we know from     
1:04:12     
like you know geometry that can represent the space of coordinates but there's no evidence that we actually use     
1:04:19     
coordinates uh cscg predicts the conditions underl fields are expected to     
1:04:25     
change in response to visible or invisible environmental changes when they do not resolving a variety of     
1:04:31     
phenomena with a simple principle so this is an example here of     
1:04:37     
a rat uh learning a cognitive map from sequential experience so the rat is     
1:04:43     
going through this maze it's kind of exploring it's trying to find its way back to the origin point and so it's not     
1:04:49     
a perfect thing it's just kind of wandering around finding its way out to the original spot using these cues in     
1:04:56     
the environment these bricks and um you know kind of putting that together and     
1:05:02     
as it turns out this is a sequence of egocentric observations so as the rat     
1:05:07     
looks out on the maze you know it sees like this green block and     
1:05:13     
this fuchsia block and then it kind of moves it turns and sees the green block and the orange block with the yellow     
1:05:20     
block and it moves up until it sees another set of blocks so it's using these uh you know egocentric     
1:05:26     
observations and it's basically stringing those together to find this path so this is where we have the     
1:05:33     
sequence of egocentric observations and at each point you can have a sequence of egocentric actions so     
1:05:40     
you see things in the environment you see it a series of things in the environment you know kind of when you     
1:05:46     
give a a set of directions of someone that you often use this sort of approach     
1:05:52     
of a sequence of instructions on how to get from point A to point B so it might     
1:05:58     
be like make a turn at this highway or make a turn at the second mailbox doesn't really matter what the object is     
1:06:05     
it's just that you're observing the world in this sequence of of uh sort of     
1:06:10     
snapshots and you know you can think of this as episodic memory but then you can also think of this as a sequence of     
1:06:16     
events that get Str together encoded into this allocentric map which is a map     
1:06:22     
of the environment so you're taking these egocentric views of the envir you're stitching them together you're     
1:06:28     
building this allocentric map which is basically if I look down at the space what does it look like you know I'm no     
1:06:34     
longer in the space or like traveling in a straight line I'm looking down at the entire space and I'm saying what is my     
1:06:41     
path and I can recall that path so you know we can make an a egocentric action     
1:06:47     
at each point but when we get to our destination then we can encode this allocentric     
1:06:53     
m so that's basic what they're getting at with the sequential rning um you can have flexible splitting     
1:07:01     
and merging of States so this is where we have different sequential information that's put together in different ways     
1:07:08     
this is of course you know taking all the observed sequences building a latent space and then you know putting them     
1:07:15     
together in some order that makes sense and so not every order Mak sense some     
1:07:20     
orders will make sense some orders won't and so being able to build a weight in space sample from it allows us to build     
1:07:28     
this first order markof model then have this cloned model with appropriate merging and splitting of State D so you     
1:07:34     
can see that D is where you get a and b they converge upon D actually C goes     
1:07:40     
to D Prime and then goes to g d goes to E and F and so that's that's basically     
1:07:48     
what you're getting here you're sampling in different ways and so this is the Cs     
1:07:53     
CG graphical model this is where we have an action State we have the latent     
1:07:58     
variables here we have the discrete emissions of this latent variable so this is sort of a Markov model of the     
1:08:06     
whole process learning spatial information and then you have this observation a Time step in so you get     
1:08:13     
this action a latent variable a discrete emission from that latent variable and     
1:08:19     
then an observation clones and Emissions that are connected together in this way so     
1:08:25     
you know this is where you're rning an emission from this lat in space and it's you're testing it out you're making     
1:08:31     
observations after the fact and you're putting all this together okay so this is a 2d room with     
1:08:38     
uniform interior this is a set of mice that are kind of traveling around the     
1:08:43     
space you have the sequence of egocentric actions these egocentric observations so in spatial cognition     
1:08:50     
it's not only important just to have the sequence of egocentric observations but it's important that you can rotate them     
1:08:57     
in different ways so you can learn kind of okay if I'm here then what is over there and I can rotate my viewpoint I     
1:09:04     
can say okay if I'm headed in this direction and I'm headed you know this this thing is over on the left if I     
1:09:10     
rotate around this thing is on the right so be able to do these kind of rotations as well is     
1:09:16     
important um this these are heading dependent observations you're heading is you know the direction which you're     
1:09:23     
traveling and so they do this then they have this learn transition graph which describes all of the     
1:09:30     
different rotations all the different sequences of learning and then mapping     
1:09:35     
this to place Fields uh the firing rate Place Fields so they're able to take     
1:09:40     
this uh representation here in three and map it to place field so this is where     
1:09:46     
we have this learn transition graph among clones each clones cover color represents the observation it's attached     
1:09:53     
to um and then number four here is where clone activations as the agent navigates the     
1:10:00     
room used to compute their place fields which are reveal the spatial locations they represent so these networks then     
1:10:08     
can be maap to place fields and you know you can understand kind of where these     
1:10:13     
you know these networks are in space or what they're representing in     
1:10:19     
space uh so yeah they give a lot of methods here um this is you know they     
1:10:24     
they did a number of experiments for this uh where they they kind of did a review of the list of experiments that     
1:10:31     
observe phenomenon related Publications so basically this kind of goes over all     
1:10:36     
the you know diversity of the field and how people are thinking about these sorts of components of spatial W so you     
1:10:44     
know you have this uh source o'keef and Burgess uh where the experiment was     
1:10:51     
changes in the geometry and the phenomena observed was that Field Place Fields remap is     
1:10:58     
determined by geometry so that's one experiment then there was of course visual Q Rotation by Muller and kubby     
1:11:06     
this is where Place Fields rotate with qard barrier Edition also mull Muller     
1:11:11     
and Kuby Place field disruption near barrier so probing the place Fields     
1:11:16     
Landmark Vector cells Place field remaps with respect to a landmark this is     
1:11:21     
desmoke and kyum uh linear track this is where the     
1:11:27     
play field remaps with respect to start and end of track so you're taking the relative position of the start and the     
1:11:33     
end of the track and seeing how the place field remaps with respect to that and that was shean at all these numbers     
1:11:40     
are in the reference list so you know if you want to look it up later you     
1:11:46     
can we have Direction Place fields that was an noie from Burgess Laps on a track     
1:11:52     
this isn't Sun at all more connected rooms devel all two identical rooms f it     
1:11:59     
all Air pin maze uh durman at all and room size     
1:12:04     
expansion Tanny all so these last uh five are you know looking at how Place     
1:12:12     
fields are unaffected by certain features of the environment but sometimes also affected so you know we     
1:12:19     
have Direction specific repetition of play Fields play fields that expand or stretch based on the Loc with respect to     
1:12:26     
boundaries Place Fields being unaffected by closed doors an event specific rate     
1:12:32     
remapping and lavells so there's a lot of stuff that they're you know they they're tring trying to kind of     
1:12:38     
integrate here a lot of disperate findings a lot of interesting things but no Theory and no you know set of unified     
1:12:45     
models so this is actually an example of this cscg learning in a simulated 3D     
1:12:51     
environment so here's an agent and this is of course not with a wrap this is in a guess in in silico where they're doing     
1:12:58     
this uh this is an isometric view of a 3D environment so you have the agent here you have the egocentric field of     
1:13:05     
view so field of view moves the agent moves it takes in a part of this environment then you have this     
1:13:12     
egocentric observation here you have this discrete emission which is the vector quantizer you have another     
1:13:19     
observation from the egocentric point of view Vector quantizer so there these discrete emissions from this     
1:13:26     
from those you build this learn transition graph which is of course this you know you move from state to state in     
1:13:32     
this graph uh so that's that's you know being able to learn in this 3D environment     
1:13:39     
there's latent transitive learning which is where you have coverage of the 3D environment in an example episode so     
1:13:46     
your agent travels a certain amount of the uh environment explores that certain amount of the environment and then     
1:13:53     
learns from that so there's this coverage here it's not the entire     
1:13:58     
environment but it's you know pretty pretty uh pretty good coverage I guess     
1:14:04     
you end up with this learn transition graph that kind of maps out the space kind of     
1:14:10     
crudely uh so that's lat and transitive learning then you have late learning separate maps and disjoint environments     
1:14:16     
so you have the isometric view of individual 3D environments so you have different environments you can see that     
1:14:22     
the agent is in here and they have a point of view and as they move it changes Direction changes its     
1:14:28     
location and you know being able to learn separate maps in different environments leads to these different     
1:14:34     
learn transition graphs so you have different graphs for different spaces um we shortcut planning you have     
1:14:41     
this space where you know you have some shortcuts in there you have ramps you     
1:14:47     
have to go from like a source location to a goal location and you have to find these PL these um shortcuts so you have     
1:14:55     
platforms and ramps that allow you to do these shortcuts and the idea is the agent has to learn the ramp and the     
1:15:01     
platform their position between the source location and the go location um so they do this there's this     
1:15:09     
initial walk that gets decoded and then there's this execution of the inferred plan that the agent takes the ramp to     
1:15:15     
get on the platform to get to the destination so it takes the shortcut     
1:15:22     
successfully okay and so you know one of the things about     
1:15:27     
their model is that it reproduces several Place field remapping phenomenal so that table I showed you before gives     
1:15:34     
you like an idea of what kinds of phenomena people are looking at um and this of course this model of course     
1:15:41     
allows us to reproduce these and so these are the different studies that     
1:15:46     
they have o'keef and Burgess Miller and Kuby Mull and Kuby shean at all son at     
1:15:54     
all and dmuk and kyum 2013 so all these are these different studies and they've kind     
1:16:00     
of replicated them using this model so you know we're able to do this with the     
1:16:07     
model and so they kind of finish up here by saying you know making this statement     
1:16:14     
that sequence representation can help explain puzzling phenomena that Mak spatial and temporal effects so     
1:16:21     
sequential context naturally explain the direction sensitivity a place field REM mapping recorded in 27 which is this     
1:16:29     
paper here um and so I think that     
1:16:35     
is is that well is not important um     
1:16:44     
so okay so when the room is elongated someplace fields that were unimodal in     
1:16:49     
the original Rema to produce two peaks corresponding to two subcomponents the     
1:16:55     
elongated room it was observed that the Peaks were Direction sensitive the left sub component was active during the     
1:17:01     
rightward travel and vice versa we tested cscg for the same effects using     
1:17:07     
the same settings in figure as in figure 3A by plotting the fields conditioned on the direction of travel in the     
1:17:14     
horizontal rectangle room rightward and leftward trajectories of the agent strongly activated the left and right     
1:17:20     
peaks of the place field so remember these Place fields are representing a certain place there's a strength of     
1:17:26     
activation depending on where the agent is and so this is what they're kind of     
1:17:32     
hitting you know they're able to take these sequences encode them and then put them in these Place fields and place     
1:17:38     
field should be predictive of features in the environment so this is exactly what they're finding here and this is     
1:17:45     
because only one of the sequential contacts that activate a clone repr a directional one which is a natural     
1:17:51     
concept of representing locations using sequential context so this is a consequence here where we     
1:17:58     
want to use locations and represent them using a sequential context and so we you     
1:18:03     
know we have to kind of work around some of these uh issues with like directional walks and things like     
1:18:11     
that okay so um this other thing here is cscg can be predict what kinds of     
1:18:17     
environmental changes need to remapping so cscg shows that environmental connectivity changes need not lead to     
1:18:24     
place field mapping even when the agent's Behavior shows adaptation to the change a phenomena that the research     
1:18:31     
researchers found pu so in citation 31 rats arean in a for     
1:18:37     
room maze where the do is connecting the rooms could be selectively locked to change the connectivity of the Arena the     
1:18:44     
rat's Behavior reflected that it recognized the connectivity changes in the environment but the place fields did     
1:18:49     
not remap in response to these connectivity changes the authors found there a lack of REM mapping puzzling and     
1:18:55     
argued that play cells do not encode a topological map so this is a kind of a controversial statement in that you know     
1:19:02     
some people believe that the place cells actually are involved in a topological map and some people question that so     
1:19:09     
this is kind of an outstanding er uh uh issue in the area of spatial     
1:19:15     
cognition U so however uh cscg showed that place cells can encode a global     
1:19:20     
location in their activations Global topology in the cell the cell connectivity and still not show     
1:19:26     
remapping in response to the manipulations so they did this they     
1:19:32     
demonstrated this by training one of their models using a random walk and an environment comprising four scare rooms     
1:19:40     
that are connected by two-way doors similar to the experimental setting in this study 31 each room had visual cues     
1:19:47     
that distinguished it from the other rooms uh the model learned the global topology of the arena in the transition     
1:19:54     
Matrix the activation of clones corresponded to locations as in the previous experiments     
1:20:00     
and so then they tested this for two environmental modifications where one door was locked     
1:20:06     
uh both ways effectively creating a blockade and the second is all doors were locked in one way allowing only an     
1:20:13     
anticlockwise direction of travel so this is where you're kind of fixing in Direction so you're kind of either     
1:20:20     
saying you're trapped in one room trapped in one part of the space or you're trapped traveling in a certain     
1:20:25     
direction and you can't go back so this is uh so corresponding modifications were made in the ccg transition matrix     
1:20:33     
by modifying the connections appropriately and planning R in this modified cscg corresponded to the     
1:20:40     
reported successful navigation so the leason reason for the lack remapping can be understood by     
1:20:46     
realizing that the connectivity change block paths without any change in the visual cues the block path affected only     
1:20:53     
a few of the potential SE sequences that were responsible for that place field I change it is too small to be reflected     
1:21:00     
in aggregate sequential responses however the connectivity change can lead to large changes in     
1:21:06     
behavior for example and navigation between the two rooms so this is where this is kind of this idea of it being     
1:21:12     
emergent so you have these you know selected examples where they're blocked     
1:21:18     
paths and you know you you have this connectivity change in the network     
1:21:25     
and it's not consistent with the visual cues so you know but it it only affects     
1:21:30     
a few of the potential sequences so you won't see this in aggregated sequential responses uh but you also get the     
1:21:37     
potential for this um sort of uh emerging Behavior where you know they     
1:21:44     
can figure out a way to navigate between the two rooms that isn't necessarily obvious so this and then there's of     
1:21:51     
course some testable predictions we can make with this model and you know so     
1:21:57     
they've kind of listed out every time you build a theory you know it's important to have these testable predictions at the ready uh so in this     
1:22:05     
case you know one prediction is that what controls how Place Fields change is     
1:22:10     
not the V rate of visual change but the uniqueness of the visual context so this     
1:22:15     
is where you know when you look at these Place Fields how do they change is that the rate of visual change or is it the     
1:22:22     
uniqueness of the visual context so they actually tested this and you know they     
1:22:28     
did this with an experiment with square rooms they observed that the place fields in the checkerboard room were     
1:22:33     
more expanded this is because the same context repeats throughout the interior of the room making it difficult for the     
1:22:40     
learing to split into context for differents so there this this is a nice model they can test different hypotheses     
1:22:49     
they can look at different uh aspects of spatial learning which is a huge field that's kind of all over the place and     
1:22:55     
get some you know some sort of predictive Theory out of there so you know this is there's a lot of stuff here     
1:23:03     
um they mentioned Tolman ien bom machines or tems and that's in citation     
1:23:09     
51 this has many similarities of cscg and inspiration however unlike our model     
1:23:15     
here in the paper tems do not learn like graphs in Alias settings like ours so     
1:23:20     
people have kind of hit on this idea before but not entirely in a way that's     
1:23:26     
you know effective so that's I think I'm going to stop for now on that paper um did you     
1:23:32     
have any comments or questions no just you know I I find     
1:23:41     
um yeah I mean I I I love this work in in the     
1:23:48     
way it makes um it makes neuroscience     
1:23:55     
um it feels like it's revealing all the engineering behind Neuroscience yeah you     
1:24:02     
know this is this is this is hard stuff yeah you know and yet at the same time     
1:24:09     
it's explaining something that in to some degree is you know is     
1:24:15     
um seem so basic to us or you know is is something that a toddler is doing yeah     
1:24:21     
yeah right like like it's U     
1:24:27     
anyway very you know super interesting right yeah um um uh you know I     
1:24:36     
I um I didn't actually see how much is um is available to play with in terms of     
1:24:44     
um um models that they have for models that they make available oh yeah uh but     
1:24:52     
this Absolut you know well would of course be interesting is to see you know     
1:24:58     
like this is very along the lines of the kind of stuff that     
1:25:03     
um uh like like the neur robotics     
1:25:09     
platform from from the old human brain project was doing um with you know a kind of virtual     
1:25:18     
rat and then using um spiking neurl Network     
1:25:24     
yeah spiking their own network model to to do not necessarily some of their     
1:25:32     
particular examples but certainly just to do 2D maze or kind of     
1:25:39     
um you um route finding um you know and and like like     
1:25:50     
definitely simpler than these examples but but uh but again some something that was very     
1:25:57     
much a a combination of kind of like bottomup neural     
1:26:02     
models that that were helping explain a a kind of highlevel Behavioral task um     
1:26:11     
which you know even though we don't think of that as like a super cognitive task it it's     
1:26:18     
it's it's certainly something that you know all all animals are engag in you     
1:26:25     
know yeah at um uh not to not to distract from this     
1:26:33     
paper but there was a a great uh um what's the um     
1:26:42     
uh the the the build a cell seminar Series yeah yeah like like this this     
1:26:49     
week's Bild the cell um was really it was a really interesting Stanford     
1:26:55     
um I I don't know like biophysicist I mean definitely started out as a     
1:27:00     
physicist and you know like like there's he shows a picture of him at a meeting     
1:27:07     
with Fineman like in like 1980 or something like that but um but but it     
1:27:12     
gives a good example of of that very simple single cell organism that that     
1:27:19     
can do you know all sorts of kind of real time Behavior     
1:27:26     
action and you know like like we did with that um was     
1:27:32     
it like Roman Brett or maybe something we were reading around that time where     
1:27:38     
it was just like you know talking a little bit about you know that kind of     
1:27:43     
that kind of organism as well as just like silat in general um and you know     
1:27:49     
like like there's there's something cool about these kind     
1:27:56     
of hippoc cample specific hippoc cample models yeah but there's also something really cool about the like single cell     
1:28:03     
organisms seem to be doing something similar you know or well or or is it     
1:28:09     
well anyway it was a cool it was a cool build to sell semr this week okay let me     
1:28:15     
just let me just say that I'll I'll if I haven't I uh I think I shared it in     
1:28:22     
Celsius um uh because it he he also had a lot of he had a lot of um     
1:28:31     
micral Dynamics with regard to you know that     
1:28:36     
that single cell uh animal going out and and seeming to to you know um um feed     
1:28:46     
you know yeah and like like seem to know where seem to know where food was and or     
1:28:52     
other animals were and was was grabbing them anyway yeah yeah really really interesting um     
1:29:00     
really interesting paper yeah so you know that's another point you bring up is that like you can do spatial     
1:29:07     
cognition maybe you need a hippocampus in mammals but they their models of spatial cognition you have path     
1:29:13     
integration in insects and they don't have a hippocampus single cells can navigate you know these Taxas where they     
1:29:20     
move towards a resource they can navigate through their environment single cells within the human body can     
1:29:26     
do that as well you know based on just kind of coordinating different signals chemical signals so it's you know it's     
1:29:34     
interesting how that you know we need like a huge model of the hippocampus and     
1:29:39     
you know we need all these different cells to navigate spaces but other organisms do it with less I     
1:29:46     
guess and you know the question is is why yeah yeah well I mean I again I     
1:29:53     
think this is this is this is why you know uh I love orthogonal is that you     
1:29:59     
know that you're thinking about the the full evolutionary range yeah     
1:30:06     
right and because like like you know trying trying to     
1:30:12     
understand the hippocampus without understanding you know its evolutionary context is is probably you know     
1:30:19     
impossible right and and um uh um     
1:30:26     
yeah like like there are so many you mention mentioned insects I think I I     
1:30:31     
mentioned Edwin Jammer you know the Bristol Prof you know who had that paper     
1:30:37     
on bird migration and you know just had a simple     
1:30:44     
simple theory about bird migration that um had some cool computational stuff um     
1:30:50     
yeah big big big question but it it does seem like     
1:30:58     
like well yeah there there is all this complexity     
1:31:03     
into the hippocampus but then is that is that that complexity seem you know     
1:31:10     
potentially some people are saying like that complexity is then used for other     
1:31:15     
cognitive tasks right right outside of spatial and and um and you know and like     
1:31:25     
perhaps some of that some of its its complexity or it's it's     
1:31:31     
um you know something about its generalization as as then allowed you     
1:31:39     
know other parts of the brain to utilize it as well right yeah I don't know     
1:31:45     
but and that that we need to look back you know so-call down the tree even     
1:31:53     
though yeah maybe maybe trees not the best way to think of it well yeah I mean different     
1:31:58     
different taxa and how they're have a common ancestry and then like what how did they diverge like you know we have     
1:32:05     
of course you know fishes and birds and lizards and then mammals in in     
1:32:10     
vertebrates so how did they all use facial cognition it turns out they use kind of a     
1:32:16     
semiconserved uh mechanism you know they have like the different loes of the brain and they those have been refined     
1:32:23     
and they kind of use those but then when you go over to Insects they use a totally different set of mechanisms and single cells you know     
1:32:30     
they don't appear to have like uh neurons so yeah it even neurons     
1:32:36     
themselves don't have their own neurons so yeah yeah     
1:32:41     
yeah all right um all right so I guess that's     
1:32:51     
good um so I guess the follow follow up on this I I know I kind of talked about the hippocampus maybe we're hippoc     
1:32:58     
campused out but there's this other set of papers here uh reinforcement learning     
1:33:04     
never never reinforcement learning development in the hippoc campus and these were two different     
1:33:10     
papers so these are this one is on sort of the development of time compress     
1:33:16     
sequences we'll see what that what that's about and then linear reinforcement learning and planning     
1:33:22     
redfields in cogntive control so just kind of reinforcement learning approach so yeah this let's start with this one     
1:33:29     
do you mind for my my old eyes do you mind blowing that up a bit yeah thank     
1:33:35     
you there we go okay so this is I guess science advances again no this actually     
1:33:42     
in science so okay um this is by Faruk and droy emergence of preconfigured and     
1:33:50     
plastic time compressed sequences an early post Nal development so this is     
1:33:56     
where you know we're looking at hippoc hippocampal neuronal ensembles and where they kind of first     
1:34:03     
organize in development and can you know we want to know something about how this sort of     
1:34:10     
emerges in development so the abstract reads when and how hipocampal neuronal     
1:34:16     
ensembles first organized to support encoding and consolidation of memory     
1:34:21     
episodes so you know we we have these these neuronal ensembles that sort of form in the hippocampus networks and we     
1:34:29     
start to get this consolidation and memory episodes uh and we don't know when that     
1:34:34     
starts in in development um we recorded electrophysiological activity from large     
1:34:40     
ensembles of hippocampal neurons starting on the first day after eye opening so this is where we're in rats     
1:34:47     
we have this uh eye openening event and then they have to experience the world for the first time     
1:34:54     
um so these are naive rats and they have to navigate a winar environment and they     
1:35:00     
have to sleep to consolidate the memories they let them navigate these environments let them sleep and then     
1:35:05     
they wanted to see what kinds of things were learned from these ensembles that were existing at this point in     
1:35:12     
development so uh we found that a gradual age dependent navigational     
1:35:17     
experience inp experience Independent Assembly a preconfigured trajectory like     
1:35:23     
quences from persistent location depicting ensembles during postnatal week three so this is where we're     
1:35:31     
interested in this early part of development post NATO week three they found that there is this age     
1:35:37     
dependent experience adultlike compressed binding of adjacent locations into trajectories during navigation and     
1:35:45     
their navigational experience dependent replay during sleep emerged in concert     
1:35:50     
from spontaneous preconfigured sequences only during early postn week four so     
1:35:56     
we're getting different things coming online as we're going from postn week 3 to postn week four um and so we're     
1:36:03     
actually getting adultlike spatial navigation by early postn week four uh     
1:36:09     
so this is where it's kind of coming online and we're looking at you know as soon as they open their eyes they get to     
1:36:15     
experience the World visual world and then you know they have to kind of learn     
1:36:20     
how to do this sort of like an adult and so it doesn't take very long apparently um our findings reveal     
1:36:26     
ethologically relevant distinct phases in the development of hippocampal preconfigured and experience dependent     
1:36:33     
sequential patterns thought to be important for episonic memory formation so this is uh kind of goes     
1:36:41     
over um you know so the hippocampus is crucial for relational binding of     
1:36:47     
spatial locations and events into these spatial mental trajectories and memory     
1:36:52     
episodes so they're not talking about like the the previous paper where they were laying out this Theory they're just     
1:36:58     
talking about sort of the development of these abilities in uh ensembles that     
1:37:04     
exist in the hippocampus so we're not interested in theory we're just kind of interested in what those networks are     
1:37:10     
doing so the rapid encoding and consolidation of sequential spatial     
1:37:15     
experiences in the memory episodes are achieved by representation of such trajectories within time compressed     
1:37:22     
hipocampal neuronal sequences during sleep or rest proceeding and following     
1:37:27     
novel experiences so they're doing this test where they're looking at sleep the effects of sleep on or rest before and     
1:37:36     
after these novel experiences so this is where you know this just sort of the way     
1:37:42     
they've done the experimental technique they just want to see what the effects     
1:37:47     
of encoding or or of you know encoding a memory um hippocampus under goes a     
1:37:54     
developmental critical period and functionally matures around postnatal day 24 so postnatal day 24 is kind of     
1:38:02     
like between the third and the fourth week so this is where again they open their eyes at post and postnatal week     
1:38:08     
three kind of at the beginning which is about like I guess um day 21 day 19 and     
1:38:16     
then they experience this maturation of the um network but this this is also a     
1:38:22     
critical period so you know it has to be there you have to have if your eyes aren't open by then then you can't     
1:38:29     
acquire the information so this is where we have this intersection of like these     
1:38:34     
developmental events and then this critical period and you know everything has to kind of be in place in order to     
1:38:41     
get this result but anyways uh so there's this functional     
1:38:46     
maturation around day 24 however when and how the hipocampal neuron neuronal ensemble patterns of     
1:38:54     
activity across different brain States underlying the encoding consolidation of     
1:38:59     
episodic like memory develop so this is where you know we're looking at these neuronal Ensemble     
1:39:05     
patterns across different brain States and we're looking at the encoding and     
1:39:11     
consolidation of episodic like Memories we're looking at the dependence on intrinsic developmental programs or     
1:39:18     
prior structured experience and this intersection of things we don't really know how those all relate     
1:39:24     
to um so this is in part due to the difficulty of simultaneously reporting     
1:39:31     
electrophysiological activity from sufficient numbers of neurons and freely behaving developing animals so we need a     
1:39:37     
technique that allows us to look at all these neurons and how they're doing things in a freely behaving animal but     
1:39:46     
also in this developmental period this very specific period um we had a comment here okay     
1:39:54     
that's bring engine ears L BR engine ears sorry I was just I was just adding     
1:40:00     
some links I promise instead I drop it before Sor     
1:40:07     
f um so yeah so previous studies of sensory motor brain areas have mapped     
1:40:13     
how Neal activity before and after experience relates the developmental or     
1:40:19     
synaptic connectivity and plasticity of that uh of the hippoc     
1:40:25     
cample net so you know we're interested in sort of experience sort of this     
1:40:30     
threshold you once you have experience then there's this Flay of synaptic     
1:40:36     
connectivity and plasticity changes in this and then we end up with our     
1:40:41     
maturation and so during this critical period it's very important to have sort of be able to open your eyes and     
1:40:48     
experience the world and if you don't do that then you don't acquire this sort of adultlike     
1:40:54     
behavior however the hippocampus does not directly respond to external stimul of a single single sensory modality     
1:41:01     
instead it integrates multimodal sensory and locomotive information across different brain States during navigation     
1:41:08     
awake rest and sleep so it's doing a lot of sensory integration as well that's     
1:41:15     
something you know we didn't see necessarily in the last paper we saw where they tested this on sequences of     
1:41:21     
of views on you know uh egocentric views and building an allocentric map but     
1:41:29     
another part of spatial cognition which is important is this aspect of you know like uh footfall information when you     
1:41:36     
walk across a surface you know you're moving your body you're hitting the ground you're counting your steps and     
1:41:43     
that's all part of the spatial information as well you can also have auditory information that's important     
1:41:49     
it's more the localizing sounds and things like that so it isn't just about you know viewing scenes there's a lot of     
1:41:56     
information here that plays a role and locomoter information especially there's     
1:42:01     
a lot of stuff going on when you're moving that you know play into this sort of memory augment the memory give it     
1:42:09     
context so this is where you know furthermore episodic memory thought to depend on the maturation of the     
1:42:15     
hipocampal network develops after sensory motor systems appear sufficiently     
1:42:21     
operational so your sensory motor system needs to be in place before you can experience spatial Behavior or the     
1:42:27     
hipocampal networks start to mature finally structural maturation of     
1:42:33     
the hippocampal formation is controlled by intrinsic signals from the stade cells of the inter rinal cortex and this     
1:42:40     
is part of the uh you know the hippocampus is part of the ininal cortex     
1:42:45     
and so this is a you know there are all sorts of different things that communicate with the hippocampus proper     
1:42:52     
in inter cortex so you know this is where you have to have this     
1:42:58     
bidirectional communication between the hippocampus and you know other centers     
1:43:03     
in the brain especially sensory motor systems and we really need to understand the developmental stages of episodic     
1:43:09     
like memory formation within the hippocampus itself so you know they     
1:43:15     
recorded from the hippocampus from these different fields uh from 192 to 3 week     
1:43:20     
old freely behaving rats during 30 30 minutes of their first ever exploration     
1:43:25     
of a 1 meter linear track so this is where they have this day one run this is     
1:43:31     
their first experience then they recorded proceeding and following about 90 minute uh my 90 minute long sleep     
1:43:38     
sessions so you have the day one run you record pre-run and you record post-run     
1:43:44     
so you get this sort of effect where you look at the network before experience you give the Brad experience and then     
1:43:50     
you measure Post run and see the difference um you also have these awake     
1:43:57     
rest epics that are you know also measured 14 animals reexplored the onear     
1:44:03     
track on the same day so this is day one run two so they do another run on the following day all animals reexplored the     
1:44:10     
same linear track or day two run and this run session was flanked by Sleep sessions so again we're looking at the     
1:44:17     
first day looking at the second day we're looking at what happens before and after training and and then in some of     
1:44:23     
the rats they get a second bout this in day one so this is where they're kind of     
1:44:29     
going and setting up this uh almost like this     
1:44:34     
um uh you know this type of data set where you have um you know almost like a     
1:44:41     
not not quite a Time series but um so yeah so they find out you know they     
1:44:48     
kind of get through some of the methods this is the diagram here in a for the experimental     
1:44:54     
design um this is these are the data here they're recording from the neurons     
1:45:00     
the first time run um and they're kind of so for the first time around they get this set of     
1:45:07     
locations in meters these representations uh that form this is uh     
1:45:13     
p15 through 16 P1 17 through 18 p19 through 20 P 21 through 22 23 through 24     
1:45:22     
and then and finally the adult so what you notice about these graphs is that the activity sort of uh becomes less     
1:45:30     
there's less variation across these different recordings so you have this     
1:45:36     
representation that moves from location zero to location 1.5 in earlier um in earlier days or in     
1:45:45     
the first days of training uh or or in the earlier parts of development you get this sort of     
1:45:51     
significant noise across the different neurons and so it's hard for the uh for     
1:45:58     
the mouse to find its way to destination because it's it has all this noise in     
1:46:04     
the network and about day 19 or 20 just the noise starts to lesson this is     
1:46:10     
probably due to some sort of synaptic pruning and then you know friendly for the adult you get some noise but largely     
1:46:17     
this is allows the um the rat to have a map of space how to get from one     
1:46:23     
location to another uh there's this run and Shuffle condition so uh when they're shuffling     
1:46:30     
there's a lot more error in terms of centimeters per meter than in the running condition so this just shows     
1:46:37     
this over days of development for the adult and you see that in development you get this higher amount of median     
1:46:44     
error for the shuffle uh than you see in the adult but in the Run condition     
1:46:50     
things converge down to the adult by day 23 to 24 so it's     
1:46:55     
interesting um and then they look at Theta sequences during the first time     
1:47:01     
run where they're looking at uh past present and future and I'm not really     
1:47:06     
sure what these graphs means it's just overdevelopment comparing that with the adult but I guess these Theta sequences     
1:47:14     
are more organized starting around day23 and you see that that's very much consistent with the adult whereas before     
1:47:22     
it's very noisy especially in day 16 day 18 day 19 and I assume that like this is really kind of     
1:47:28     
before any learning is acquired so it's just kind of this line and then you get this noise and then you start to get     
1:47:35     
this pattern and then by day 23 it's refined enough to resemble the     
1:47:40     
adult um yeah so this is all kind of talking about this type uh you know     
1:47:47     
these developmental aspects of learning they propose a three-stage developmental timeline for experience dependent     
1:47:53     
trajectory replay um you know you have a stationary     
1:47:59     
location depicting on days 15 and 16 partial trajectory depicting on P days     
1:48:05     
17 and 18 and entire trajectory depicting on days 19 and 20 and so you     
1:48:12     
have these different stages of uh replay during sleep in these different     
1:48:18     
developmental uh periods which are just two-day periods this is graph of pre-run sleep     
1:48:24     
versus post-run sleep so you can see that like you really have this transition at about day 23 and it     
1:48:30     
resembles the adult so this is     
1:48:36     
um let's see uh here's uh some insight into what     
1:48:44     
they found so     
1:48:49     
um this suggests this this result up here this suggests that network preconfiguration does not emerge as a     
1:48:56     
result of un unaccounted sequential experience in the home cage before days     
1:49:02     
17 and 18 as an explicit sequential experience on a WI a track did not     
1:49:07     
result in bust data sequence and offline sequence plasticity until day 23 to     
1:49:13     
24 previous day navigational experience did not accelerate the developmental emergence of age and recent experience     
1:49:20     
dependent plasticity experience in day 21 and day 22 animals taken together these results     
1:49:27     
indicate that hipocampal ensembles exhibit reduced stimulus related plasticity during the critical period so     
1:49:34     
this is where we have reduced stimulus related plasticity during the critical period in hippoc compal ensembles     
1:49:42     
including their experience in the home cage and apparent contrast with height and plasticity observed in the     
1:49:48     
developing sensory cortex so this was I guess a hypothesis that they had     
1:49:53     
will we see changes in critical period changes in hippocampus that we see in     
1:49:58     
sensory cortex and if you're familiar of sensory cortex you know that sensory cortex really you know refines itself     
1:50:05     
over this critical period and when you have like the sensory input you if you remove the sensory input during the     
1:50:12     
critical period you can uh really kind of mess up the animal for life I guess     
1:50:17     
is the way to put it um but in this case you know we have this model of sort of     
1:50:23     
uh critical period plasticity in sensory cortex and we find that in in hippocampal ensembles we don't really     
1:50:31     
have this it's reduced compared to sensory cortex but we do have some uh     
1:50:38     
you know critical period plasticity so that's an interesting finding I'm not really sure how to interpret it any more     
1:50:44     
than that but I guess you know the idea is that there's maybe less of a dependence on this particular time     
1:50:51     
period as opposed to sensory cortex and um so this suggests that the age     
1:50:57     
dependent emergence of tight compressed trajectory sequences depends on intrinsic instructive signals likely     
1:51:05     
produced by the Upstream development developing stellate cell network of the interal cortex so there this suggests     
1:51:12     
that there's a sort of an innate aspect to training the hippocampal ensembles     
1:51:18     
you have this experience but you also have this innate aspect where this other network is developing and it's kind of     
1:51:25     
feeding information in and so it's you know maybe uh direct experience isn't     
1:51:32     
always necessary to have you know um spatial cogn the development of spatial     
1:51:38     
cognition but um I'd like to follow up more on that it's kind of interesting so they've identified     
1:51:45     
distinct CH uh stages and the development of sequential patterns and ronal ensembles and the rat which we     
1:51:51     
propose are important for the relational binding of events an episodic like memory     
1:51:56     
formation um in the first stage the hippocampal network represents discrete     
1:52:01     
locations explored in space lacks the ability to bind them into temporarily compressed trajectories so this occurs     
1:52:08     
at 15 to 16 which is why we see this sort of immaturity um this is when the rats are     
1:52:15     
confined to the nest so we don't expect a lot of direct experience the second     
1:52:21     
stage is characterized by the margin and gradual increase in the complexity of preconfigured sequential     
1:52:27     
motifs expressed during offline sleep and rest epics and an age dependent navigational experience in dependent     
1:52:33     
manner so this is where we have these uh you know these sleep episodes where     
1:52:39     
these things are being encoded as sequences where brat is kind of going over in their mind what they've learned     
1:52:46     
that day and trying to put it together into a coherent uh set of     
1:52:51     
sequences uh and then this stage begins around 177 to 18 days and continues to     
1:52:57     
21 to 22 days when Rats start exploring increasingly beyond their nest so this     
1:53:02     
is really dependent on when they leave their nest and get that experience but you know this isn't as     
1:53:10     
um I guess it isn't as uh sensory dependent or uh isn't as critical per     
1:53:16     
dependent is sensory cortex so this is kind of talking about a little bit more about plasticity     
1:53:23     
we propose that the coordinated development of time compressed sequences during encoding and consolidation of     
1:53:29     
sequential information by a stronger Replay in sleep at days 23 and 24 in the     
1:53:34     
rat represents a critical Network mechanism that could enable the emergence of episodic like memory     
1:53:41     
function so that's a good um good kind of summary of that quite a bit different     
1:53:48     
from the first paper because we're talking about development we're talking about kind of the sequence of things in     
1:53:53     
development we're kind of looking at the critical period versus maybe innate stuff that's going on um     
1:54:00     
and I don't know if like they cracked the nut there I don't know but it's it's     
1:54:05     
definitely all those things are coming into Blow no just just uh yeah absolutely     
1:54:11     
agreeing like really interesting as a different     
1:54:17     
take on the kind of developmental issues wor the the same     
1:54:24     
region so the second paper then is this linear reinforcement learning and this     
1:54:29     
is K and da so this is a nature     
1:54:34     
Communications and so this is where we're you know interested in spatial cognition cognitive control but also     
1:54:41     
this linear reinforcement learning aspect so the abstract reads it is thought that the brain's judicious reuse     
1:54:48     
of previous computation underlies our ability to plan flexibly um but that also that     
1:54:55     
inappropriate reuse gives rise to inflexibilities like habits and compulsion so and they mean reuse of     
1:55:03     
computation they mean like you know you're reusing the same mechanism over     
1:55:08     
and over to find things and I guess the idea is that you can benefit from that     
1:55:13     
but you can also your drawbacks to that as well so there are a lot of habits and compulsions that are kind of fixed uh     
1:55:20     
because the same computations are used over and over and they're context independent meaning that there isn't     
1:55:26     
this um you know distinction between computations for like bad habits and     
1:55:32     
computations for good habits um and this is just kind of a     
1:55:37     
general thing yet we lack a complete realistic account of either so they're what     
1:55:43     
they're doing here is they're building on control engineering and introducing a model for decision- making in the brain     
1:55:49     
that raises a temporally abstracted map of future events to enable biologically realistic flexible choice at the expect     
1:55:58     
of specific at the at the expense of specific quantifiable biases and so this     
1:56:04     
replaces the classic nonlinear model based optimization with a linear approximation it softly maximizes around     
1:56:12     
a default policy so in um in reinforcement learning we have these     
1:56:17     
policies that we try to you know use and we try to maximize the beh Behavior     
1:56:22     
towards these policies and the idea is these policies match the kind of behavior we expect from the system so um     
1:56:29     
you know this is this is of course you know we have computational reinforcement learning then we have the kind of     
1:56:35     
reinforcement learning we learn through experiments and so you know the whole     
1:56:40     
idea is that it's Loosely based on what you would see in behavioral Neuroscience but you know it's supposed     
1:56:46     
to give kind of a similar output it's supposed to allow for Learning and     
1:56:51     
condition and things like that um so it replaces the CL okay we     
1:56:58     
did that the solution demonstrates connections between seemingly disparate phenomena across behavioral Neuroscience     
1:57:06     
not notably flexible replanning with biases and cognitive control also     
1:57:11     
provides insight into how the brain can represent maps of longdistance contingency sta uh componenti I guess of     
1:57:21     
having components as an interal response fields and exploit them to guide Choice even under     
1:57:27     
changing rules so this is where you know we want to have these kind of instead of having these uh like linear sequences     
1:57:35     
instead of having these other types of um you know mechanisms and development     
1:57:40     
we're going to have these policies that kind of characterize learning and allow us to build these kind of uh flexibly     
1:57:48     
changing uh systems where we can change the policy uh in in policy optimization so that's     
1:57:56     
that's what they're trying to do here um so you know they talk about the brain     
1:58:02     
exhibiting a remarkable range of flexibility and inflexibility a key Insight from reinforcement learning     
1:58:07     
models is a human's ability to flexibly plan new actions and also our failure     
1:58:13     
sometimes to do so in a health in healthy habits and disorders of compulsion can be understood in terms of     
1:58:19     
the brain's ability to reuse previous computation and there five references there um exhaustive modelbased     
1:58:26     
computation of action values is time consuming thus it is deployed only     
1:58:32     
selectively such as early in learning task when possible to Brin instead basis     
1:58:38     
choices on previously learned decision variables this strategy saves     
1:58:43     
computation but gives rise to slips of acttion and cach values are onate so they give this strategy and it's     
1:58:50     
basically that you try to save time by um you know deploying different     
1:58:57     
computations selectively using this modelbased approach and then you know you try to kind of use that for all     
1:59:05     
different types of things now you know you can have it can save computation it     
1:59:10     
can save you know the ability for you to do computation so you might be able to do things faster where you don't have to     
1:59:17     
remember as much but it also gives rise to different types of you know a loss of     
1:59:23     
of different things like context or slips of action so that's what they're getting at     
1:59:29     
here uh so this is the basic concept of adaptive recomputation while it seems promising     
1:59:35     
this class of models even augmented with refinement such as prioritize replay partial evaluation and successive     
1:59:42     
representation which we haven't talked about but I have a paper in one of the reading cues there there's a paper in     
1:59:49     
successive representations uh that I'm not going to get into today but is something if     
1:59:55     
you're interested you should read more about um has so far failed to fully account either for the uh either for the     
2:00:02     
brain's flexibility or its inflexibility so you know we have these models of     
2:00:08     
computation and the problem here is that you know we can't say like you know if     
2:00:15     
something is selectively flexible we can't have a model of computation that is completely adaptive     
2:00:22     
you have flexibility that allows you to do a lot of things but maybe comes at the cost of encoding certain information     
2:00:29     
or an inflexibility which comes from the need to save computation but then     
2:00:35     
doesn't allow you to explore new Vistas so that's that's sort of tradeoff here and then you know there are     
2:00:41     
different types of mechanisms in these computational models that people have introduced to try to get this to work     
2:00:47     
but that's not you know it hasn't according to these authors has and     
2:00:53     
successful for flexibility we still lack a tractable and nurly plausible account     
2:00:58     
of how the brain accomplishes the behaviors associated with modelbased planning so we're interested in modelbased planning and in the     
2:01:05     
hippocampus of course we are using modelbased planning to some extent we have a model we learn according to that     
2:01:11     
model and then you know maybe if it's play cells red cells maybe it's     
2:01:17     
sequential uh information those models then will we to plan accordingly     
2:01:22     
um so this is what they're getting at with modelbased planning uh conversely the ReUse of completely formed action     
2:01:29     
preferences and explain extreme examples of habits such as a rat persistently working for food it does not want but     
2:01:37     
fails fully to explain how and when these Tendencies can be overridden and also many subtler graded or     
2:01:43     
probabilistic response Tendencies such as pavlovian biases or varying error     
2:01:48     
rates and cognitive control tests so this is something you know this is something for sort of     
2:01:53     
computational uh Psy Psychiatry and sort of thinking about it in that respect you     
2:01:59     
know how do you have these computations that overcome say um you know bad     
2:02:05     
Tendencies or other types of errors and learning um it's interesting I don't     
2:02:11     
know I don't know too much about this field so I'm not going to uh get into it too much but     
2:02:17     
um so uh they talk about this in particular we argue that this Central computational challenge in sequential     
2:02:24     
decision tasks is that the optimal decision at every time Point depends on the optimal decision at the next time     
2:02:30     
point and so on so if you were at a maze and you went from point to point in the Maze uh the value of going left or right     
2:02:39     
now depends on you know which turn you made at the subsequent Junction and similarly thereafter so you're being     
2:02:46     
locked into these possibilities with each move and the idea is you want to be     
2:02:51     
able to Escape say the tendency of going down a     
2:02:56     
blind alley every time you navigate The Maze it would be easy if you just had like a set of instructions and you just     
2:03:03     
follow those instructions and hope that you could make it through the maze but of course that's not the way mazes work     
2:03:09     
you know you have to discover you have to explore as you go along and then of course you know the idea is that you     
2:03:17     
want to be able to make an optimal decision at each time Point each turn in the maze     
2:03:22     
and so that's what you're trying to enable with these models um the inter dependence between     
2:03:28     
actions is a consequence of the objective of maximizing human one of expected reward in this setting and is     
2:03:34     
reflected in the Bellman equation for the optimal value so they're using the bman equation to do that however it also     
2:03:41     
greatly complicates planning replanning Tas transfer and temporal extraction in     
2:03:47     
both artificial intelligence and biological settings so this is this sort     
2:03:53     
of model where we want to be able to U you know get rid of these biases in     
2:03:58     
decision making um and you know we can use a lot of computation to do that but it greatly     
2:04:05     
complicates other aspects like replanning planning test transfer temporal extraction so there are a lot     
2:04:12     
of trade-offs here in some of these models so how then can the brain produce flexible behavior however we lack a     
2:04:19     
biologically realistic account of how this is implemented in the brain obviously you know we're not     
2:04:24     
implementing the Gman equation in our brains maybe we do something that looks similar but um it's it's not     
2:04:31     
biologically realistic so the other aspect of this is because of the     
2:04:36     
interdependence of optimal actions exhaus of search seems infeasible for     
2:04:42     
most real world tasks due to the exponentially growing number of future actions that must be optimized for so     
2:04:48     
when we go through a maze we're making decisions one of time and we're kind of optimizing for each step but if we think     
2:04:55     
about this in terms of all the options that we could make you know we have to kind of make an optimal decision for a     
2:05:01     
turn and there may be three options for that turn and then another turn that might be four options to consider and     
2:05:07     
you keep doing this over and over and you can see how much computational power     
2:05:13     
you need to kind of make that decision at every every uh every turn of the     
2:05:19     
Nam one such proposal which is perhaps the most promising step towards a neurally realistic planning algorithm is     
2:05:26     
the successor representation so this is in this paper citation 16 which by leveraging cach expectations     
2:05:34     
about which states will be visited in the future we can efficiently solve a subset of tasks traditionally associated     
2:05:40     
with modelbased planning so this is the successor representation and like I said I might     
2:05:48     
do a paper on it next week but we'll see so they're doing this uh with markof decision processes so let's see what we     
2:05:54     
have with the model here uh so the model kind of goes through uh so in Markov     
2:06:00     
decision tests like mazes or video games the agent visits a series of States s and at each they receive some B     
2:06:07     
punishment R and choose among a set of available actions a which affects which state they visit next so they have this     
2:06:14     
uh markof decision model uh which they mention up     
2:06:19     
here uh talk about that up here we I just highlighted um and then so you know we     
2:06:27     
have this uh optimal value V our some state has given the sum of future     
2:06:32     
rewards a series of nested expectations or equivalently in the recursive form of the Bellman     
2:06:39     
equation across all states this results in a set of interdependent optimization problems which can be     
2:06:46     
solved for instance by iterative search through the tree of future States computing the maximizing action in each     
2:06:53     
step over in realistic tasks with large State spaces this iterative nonlinear computation may be     
2:07:01     
intractable so you know this is the kind of thing that they're doing here they talk about model     
2:07:07     
performance um replanning uh here's the uh linear     
2:07:12     
reinforcement learning model in figure one we have this uh person Stick Figure     
2:07:18     
We Have A and B we have this coin here and this Square this this red X so um     
2:07:26     
for a the so for A and B the model optimizes the decision     
2:07:32     
policy by considering the reward and control cost which is defined as the KL Divergence between the decision policy     
2:07:39     
and a default policy so that's what we're doing here we have a value versus     
2:07:44     
probability of choosing a we have the expected reward and the control cost     
2:07:52     
uh then we have uh C and D which is the model accurately approximates the     
2:07:57     
optimal choice we compared its performance on a seven level decision tree task with random one-step costs at     
2:08:04     
each state to six pruned modelbased Aro algorithms which evaluate the test to     
2:08:09     
with certain depth of the tree so that's here where we have this decision Tree in C and then there's cost model in D which     
2:08:18     
we evaluate the cost of each model um and so that's uh what we have     
2:08:25     
here uh E1 is equivalent to the successor representation for the random walk policy so that's D1 here and uses     
2:08:33     
average values as the leaves linear reinforcement learning achievement your optimal average costs Y axis is     
2:08:40     
additionally cost relative to the optimum local costs of all states are randomly chosen in the range of 0     
2:08:45     
through 10 simulations are repeated a 100 times so I think I'm going to stop for     
2:08:52     
now I think we got the point of this paper kind of walking through this decision-making model and um you know     
2:08:59     
they're going to apply it to this um this set of Agents so we have any     
2:09:04     
questions or comments before we go so is it's a I hesitate to say a     
2:09:10     
simplification yeah but but it is the is the root of     
2:09:17     
this paper um a linearization and and kind of a variational     
2:09:25     
formulation of RL without you know again without     
2:09:31     
being um you know acknowledging that that still     
2:09:38     
leaves it very complicated yeah yeah I think I think you're yeah it's sort of a variational approach to reinforcement     
2:09:44     
right you know I mean the use of the KL between the     
2:09:49     
the you know the the model you know this is figure one a     
2:09:57     
b blurb the the text you know model optimizes the decision B SE by     
2:10:04     
considering the reward and control cost which is defined as the K Divergence between the decision policy and the     
2:10:10     
default policy yeah and and like before that there was there was     
2:10:16     
some some Talk of the we're linearizing this too like and um     
2:10:25     
uh these these you know typ typically when I've seen these     
2:10:31     
variational um re reformulations of problems like     
2:10:36     
the linearization is also an important part of the like I'm I'm I'm making what     
2:10:42     
was previously intractable problem trct yeah yeah     
2:10:47     
basically and again I still think that leaves it really complicated     
2:10:52     
but but but you know like that like that seemed to be their goal yeah yeah I     
2:10:59     
think so and for sure like you know like like you said at the beginning like you     
2:11:04     
know there's a lot of the lot of The Usual Suspects in computational Psychiatry and references from you know     
2:11:12     
one through five y NIV being being one of those in     
2:11:19     
the reference one yeah     
2:11:25     
yeah and so I I don't think danan is that did you say     
2:11:30     
Dian uh not sure d a y an how do you pronounce oh Dian Dian yeah yeah anyway     
2:11:37     
I mean dian's in there and and bought vck of course     
2:11:44     
umh and and I oh right yeah yeah um being you know     
2:11:52     
like all I mean I don't think they call themselves conversational Psychiatry people y really is but um I mean calls     
2:12:01     
herself that but they like like the methods are all     
2:12:06     
completely overlapping in terms of of what what they what they do yeah yeah     
2:12:13     
yeah so super interesting I I     
2:12:19     
um you know it's this kind of thing and and again um     
2:12:25     
it was the the presentations that that I found to be the     
2:12:31     
most you know edifying um is maybe uh Ryan     
2:12:38     
Smith uh so definitely a computational Psychiatry person in that he's in     
2:12:46     
Psychiatry like like uh um like he's in the Psychiatry Department think but but     
2:12:52     
uh um but he's a big active inference like     
2:12:58     
like like he he's he's the one who helps in some of his like     
2:13:04     
tutorials and some of his his is very like like explaining the differences between     
2:13:12     
a whole number of computational mods all in an RL context but then all as as     
2:13:21     
tradeoffs between like you like you think like exploration and um     
2:13:30     
um well I usually see it as exploration and exploitation but I'm not sure what the exploitation is in this this     
2:13:37     
context exp exploration and like fixed Behavior or like yeah     
2:13:43     
yeah and and um uh you know it was nice to     
2:13:51     
where yeah where where active inference it was it     
2:13:57     
was it was much clearer with his his uh I think active inference talk most     
2:14:04     
recently active inference Institute talk most recently that that     
2:14:09     
it it was it was the best explanation I'd seen in terms of what active     
2:14:15     
inference is as a tradeoff in in this kind of RL     
2:14:22     
context yeah um and who that again Ryan Smith okay     
2:14:35     
so um like like he was     
2:14:42     
definitely I want to say a postto of friston's U post talker visiting faculty     
2:14:49     
something something like that excuse me um and like like he did a tutorial like     
2:14:57     
a couple years ago like I think that the paper is called like a tutorial     
2:15:03     
on blah blah blah blah blah like shouldn't say blah uh     
2:15:10     
um was it Dynamic cos modeling I think I think it was he did a tutorial on     
2:15:15     
Dynamic CM modeling um which which is potentially more more brain Imaging work     
2:15:23     
but but the the the um you know the the interesting the     
2:15:30     
really interesting thing about Dynamic causal models as it does relate to brain Imaging is how you can bring the ex the     
2:15:37     
the the experiment and and particular brain particular brain Network um in in     
2:15:46     
this very clear modelbased way uh into analysis but but his most recent talk     
2:15:51     
it's Brian Smith he's at um the Lauren Institute of Marine     
2:16:00     
Sciences in um Tulsa okay uh     
2:16:07     
um because they they they obviously got a lot of money recent or you know like     
2:16:12     
somewhat recently and they they hired a whole bunch of great people     
2:16:19     
um um it's good good good to sit on all that oil money     
2:16:24     
yeah but yeah yeah I'll have a look for that talk     
2:16:31     
because it's um you know like we we there was there     
2:16:38     
was a a guy at Stanford there there's an RL group at Stanford that sensibly working you know     
2:16:46     
they're calling them World models yeah yeah you know but but it seems like the the secret sauce     
2:16:56     
is actually a lot of the same discussions that Ryan Smith's talking about in terms of of tradeoffs in this     
2:17:05     
in the you know um in the RL Machinery right because certainly some of this     
2:17:11     
some of the early parts of this paper related to the um     
2:17:16     
just basically what s like like what was Su trying to     
2:17:24     
accommodate with temporal difference RL sorry isn't that what he called it     
2:17:31     
yeah yeah what when they say TDL yeah yeah temporal differencing yeah     
2:17:37     
yeah and and you know it's it's always I mean you     
2:17:44     
know related related to this in general and of course they they mentioned     
2:17:49     
something of course um uh in in the references but     
2:17:55     
um uh uh what's it called Amy I think is the     
2:18:04     
Alberta or sorry am I'm trying to work out the     
2:18:09     
acronym but but you know the the Alberta plan right right right right right so so     
2:18:15     
Sutton's group you know the the now I don't want to say disbanded but now     
2:18:22     
defun Google sorry deep Minds Alberta um you know which is they've     
2:18:30     
been released and set free yeah     
2:18:35     
uh they're at that Alberta plan has has a whole bunch of like we're interested     
2:18:41     
in these things in in kind of RL and and     
2:18:46     
you know it's a lot of these same kind of sometimes it looks like it's fine-tuning     
2:18:52     
but like I think if I if I understood all the issues better it would I would     
2:18:59     
see for its you know its true depth yeah but but super it see seems really     
2:19:08     
you know related to this work in the sense that like it's related to you know it's it's almost like a kind     
2:19:16     
of reformulation of the problem but again it's like it's solving it's solving issues that I just don't     
2:19:23     
understand deeply enough to to see it's you know like like why it's so important     
2:19:29     
or um why why it's more than just computational tractability I think is is     
2:19:35     
what I'm trying to say yeah yeah I think that's true uh yeah I I would have to go back you know we should probably go back     
2:19:41     
to Sutton's work on this because you you know I mean yeah like     
2:19:49     
like the reason I always um for that same problem right it's just     
2:19:57     
like if I if I really understood it as deeply as he does then I would I'm sure     
2:20:03     
I would get why all those points are important yeah uh uh but until then I'm     
2:20:08     
just gonna keep reading that list and trying to make a little bit of     
2:20:15     
progress but but it would be good I mean again it would it be good to bring these you know     
2:20:22     
because it's like well you know how groups are they GNA get they they get a     
2:20:29     
little in a rut with their own vocabulary and things like that right but they're actually they're actually     
2:20:35     
talking about the same things you know yeah yeah and and so this is this is a     
2:20:41     
nice or at least you know sort of while you were talking I was I was checking the references as they were kind of     
2:20:47     
going past in the in the text you were reading yeah and and yeah like like     
2:20:53     
these are this is the you know the Confluence of of multiple um     
2:21:00     
research groups or you know like you're seeing multiple research group work kind of come together and be um uh well more     
2:21:09     
than merged but um you know built built upon right and and it would be great to     
2:21:17     
see um where again like World models and perhaps even     
2:21:24     
every every good um uh um every good     
2:21:30     
regulator yeah uh could play plays into this you know     
2:21:39     
um yeah great well that's great yeah we should follow up on this uh more but     
2:21:45     
yeah this is great been a great discussion Trevor did you have anything to say before we     
2:21:53     
you know you mention that you haven't uh you don't have too much um I guess     
2:21:59     
exposure to the these ideas of um model learning and uh reinforcement learning     
2:22:05     
what not only reason I unintentionally have stumbled     
2:22:11     
into this area in the past two days so there's a paper you you might find     
2:22:17     
interesting it's really more of an attack paper uh but it was just uh a lot     
2:22:23     
of the history of um of some of you know there's there's a     
2:22:31     
really uh deep focus on dopamine um oftentimes it wasn't emphasized too much     
2:22:38     
here but um often in one these reinforcement learning paradigms dopamine's like King and um anyways so     
2:22:46     
there was just interesting paper I came across where they they were challenging that and like in a lot of these um     
2:22:52     
paradigms where like int cranial stimulation is used um it's it turns out     
2:22:58     
that um when you're trying to use that in the context of learning or to incentivize behavior um it's not you're     
2:23:05     
not actually replicating what the brain is intrinsically doing it's um you are     
2:23:12     
creating a a super physiological stimulus that in of itself is what is um     
2:23:19     
guiding Behavior anyway so some this is you know the overlap is minimal but if     
2:23:24     
you have any interest I'd be happy but S I know it's not defin definitely drop a link I think     
2:23:31     
I know the paper you're talking about are certainly certainly one one that sounds like that um because uh I think     
2:23:40     
the the certainly the the original paper that we might be all thinking about is     
2:23:46     
like the um like 1997 um Reed monu and I'm trying to think     
2:23:55     
if H scanning or was different     
2:24:01     
um anyway it's it's it's um he was he     
2:24:06     
was um uh um definitely trying to relate you     
2:24:12     
know a a neural model to reinforcement learning okay and and um uh uh     
2:24:21     
you know and I I I say like like and I kind of follow Reed in particular     
2:24:27     
because he's the the head of brain Imaging and and um yeah I think like     
2:24:34     
human Neuroscience Lab at Virginia Tech in my my hometown okay um but uh but     
2:24:41     
what he's doing there so he's one of the only groups that that collaborates with Nur surgery     
2:24:48     
to do neurotrans level detection in in in awake humans     
2:24:56     
okay so and so they've made specific devices to track to track     
2:25:03     
neurotransmitters uh um potentially with a task you know while while I have the     
2:25:09     
skull open anyway but I I do I'll check the the paper super interesting TR yeah     
2:25:16     
because I'll check the paper in terms of like I seem to remember remember somebody recently having a paper on like     
2:25:24     
no it's not like the the monteu I can't remember who it was it was somebody big     
2:25:31     
in machine learning that was the senior author on that that 97 monu paper but     
2:25:38     
okay i' love to see that paper it sounds interesting yeah yeah okay um so let's     
2:25:44     
um let's drop links I mean I I I put links in the in the jitc     
2:25:50     
uh chat but let's drop links in in slack so that um that they don't go away when     
2:25:57     
we close this and um and yeah we'll follow up on the follow up on the put     
2:26:04     
them in computational Psychiatry yeah yeah and um I think that'd be really     
2:26:10     
interesting because uh you know again like     
2:26:15     
like it is it is really hard to to say what's going on in the     
2:26:22     
brain and and um you know read it's it's     
2:26:28     
cool that he does he supports kind of you know machine learning conversational     
2:26:34     
Psychiatry as well as does Nurse surgery and builds equipment to actually do the     
2:26:40     
measurements in humans in a way that is the most comparable with with works     
2:26:45     
that's done in non-human PRS yeah all right well yeah thanks for all     
2:26:51     
that um yeah we can continue the discussion in computational Psychiatry     
2:26:56     
look forward to seeing some of these links cool cool all right thanks so much talk to you soon to you     
2:27:02     
soon you bye bye     
