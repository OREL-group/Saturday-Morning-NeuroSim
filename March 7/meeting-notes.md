## Meeting Recording

[YouTube link](https://youtu.be/qAIEPVQVrCk)

## Mastodon thread

[link](https://neuromatch.social/@OREL/116190100134116331)

## Feature Videos

[Improvements to LLAMAOSC (Open-source)](https://youtu.be/0aD0RPrIonI)

[How to Write a GSoC Proposal](https://youtu.be/vEUib6ZfCGM)

[Pull Request Contributions to LLAMAOSC (GSoC Repository, March 2026)](https://youtu.be/hEQ6yfg_2go)

[JoPro Organizational Update](https://youtu.be/FP--q4HEDgI)

[Developmental Feature Detectors, Sounds and Shapes (cross-species Bouba/Kiki)](https://youtu.be/ddziOmpB6y8)

## NOTES
Vidhi, Akshat:

1) OLLAMA embeddings #119 -- agent sends message to convo space.

* does not link chat and Git history.

* proposed RAG content structure: message --> PR/issue --> code lines. Current RAG setup.

2) memory system.

* link short and long-term memory (sliding window and vector DB).

* long-term is implemented.

3) current agent calling.

* Alice, Bob, Dave, Carol. Serial conversation passing.

* probabilistic agent, turn selection (no improvisation).

* turns are serial, some talk much more than others.

* motivation -- formula (total contributors, selected window size).


What is a real-like conversation style?

* simulate and data science. Pulls convos from Github, Slack.

* contributors for the conversation space.

* within the timeline of GSoC --> conversation space, Github history.


NYCWiC --> Albany -- post a link in the Slack.

* submission: spatial and epistemic intelligence.

* AHA --> Advancing Humans with AI. HardMode Hackathon.

* Breakout (Embodied Models from the 80s), Breakout (Navigational Affordances and Selection), Masterclass (Phylogenetically-mixed Architectures).

* what will be downstream of EI Conference? 

Kavya -- second-year CS (MESA contributor).

* planning session for EI Workshop?


pip install llamaosc

* move from being cloned and configured to being a version-controlled installer (.exe-like).

* "lowers friction for casual users, friction for power users". 

* pip packager (can make changes outside runtime, but run as well).

https://neutralino.js.org/ --> neutralino.js


FrontierMap --> worked into different versions.

1) metascience and organization (encourage more synthetic time).

2) demarcating the problem space.

Futures Center, Plot Twisters

Mona Hamdi --> games or prompts as interactions.

CogFutures --> first-person to shared (Becoming Aware).

Princeton Envision --> AI and Education (panel).


Vidhi Rohira
Vidhi Rohira says:
once you get the time* 
9:42


Vidhi Rohira says:
sorry messaged accidentally * 
9:42


Vidhi Rohira says:
ill joing back in sometime 
10:00



Jes
Jes says:
hi 
10:09


Jes says:
https://www.nycwic.org/
 
👍
10:22



Vidhi Rohira
Vidhi Rohira says:
I gotta go, got university exams
will join yall next week 
10:26



Jes
Jes says:
https://embodied-intelligence.org/
 
10:27


Jes says:
Summoning Yohan John to comment on Grossberg 
10:42


Jes says:
👍 
10:47

Jes says:
#DevAI 
11:02


Jes says:
'ever more selective response criteria" 

sec 6 

"how are criticial periods of dev regulated" 
11:05



Kavya Zala
Kavya Zala says:
since developmental stages are triggered by equilibrium from Short term and long term memory , what happens if equilibrium is disturbed by abnormal sensory input or chemical imbalance ? 
👍
11:10


Kavya Zala says:
that's interesting, thank you 


## TRANSCRIPT
0:01   
Hello. Hello. Hi. How are you?   
0:07   
I'm good. How are you? All right. BD.   
0:15   
Can you check the private chat on Slack? I've sent you something. Yeah, I saw that.   
0:22   
Okay. Yeah, it was that proposal. So, I'll look it over.   
0:29   
Okay. Is that something you wanted to present on today or   
0:34   
I'll give you some time? I'm not going to be presenting it today   
0:39   
because it's not yet ready. That's just my idea of it. I'm probably going to add more, but I wanted to know your thoughts   
0:45   
on it. Like, is it good? And I mean, yeah, I'll look it over. We'll   
0:51   
see. Okay. Okay. Okay. All right.   
0:59   
So, why don't we get started? Welcome. Uh, this week we had uh one meeting we   
1:06   
had D.VARM and uh we've been working on some things kind of behind the scenes. Um, and so   
1:14   
those will be coming out soon. Um, we're getting ready for Embodied   
1:20   
Intelligence Workshop that is on March 19th and 20th. So, I'm   
1:25   
going to send out a link in the uh Slack channel to let everyone know where to   
1:32   
find it if you'd like to attend or I think they'll be recording it. There'll be recordings afterwards.   
1:39   
Um I'm presenting some things uh from the web's work. Uh Jesse is I think also   
1:46   
presenting. He mentioned something in the Slack about a some presentation he   
1:51   
wanted to do and um you know it looks good. So, we'll see.   
1:56   
And um that that's great. That looks like it's going to be an interesting conference. Uh the way they're   
2:03   
organizing it this year is they're going going to have like three time zone tiers. Um they're going to have Asia,   
2:11   
which is for like Japan and China and Korea in centered on those time zones. uh   
2:18   
Europe, which is like the European time zones, and then uh the eastern time zone   
2:24   
of North America. So, all the time zones there. So, it's like people can pick the   
2:30   
one they're closest to and uh be kind of don't have to be awake at 3 in the morning because it's a virtual   
2:36   
conference. And so, um yeah, I will I I'm not I don't have   
2:43   
anything to present today on that, but that is coming up. Um then we have some   
2:48   
other things coming up, some other deadlines. Um and I will be communicating those internally as they   
2:55   
become uh we get closer to them. So one of those of course is uh Google   
3:02   
summar code and the deadline for proposals there is March 31st.   
3:08   
So if you are looking for to submit a proposal for Google Summer   
3:14   
code. So we have uh three projects. One is the dboorm project which is dbo   
3:20   
graph and that's the uh project where people are proposing various   
3:26   
techniques related to graph neural networks. So we've been focusing on graph neural networks but we have a   
3:32   
longer history in in divor of working with graph structures and networks   
3:39   
and so we have some people interested in that. We also have two projects in the   
3:47   
uh orthogonal web proper. One of those is well they're both   
3:52   
related to open source sustainability. One of those is open source sustainability with kind of a focus on   
4:00   
reinforcement learning and other methods like that. And then the second one is   
4:06   
focused on large language models. So, we actually have two projects to apply for.   
4:12   
Um, so I don't know how many slots we're going to get. Um, in years past, we've   
4:17   
gotten as few as two, as many as like seven, which is like unusual, but that   
4:23   
was one year we're right. We got everyone that applied, but that's not going to happen this   
4:29   
year, I'm pretty sure. And so that will be uh you know we'll be   
4:35   
uh getting those applications in by the 31st. That's a Google deadline. And then we   
4:41   
will make decisions from there. We'll evaluate the proposals. Um and so then   
4:48   
we I think we announce uh people in I think at the end of April or the   
4:56   
beginning of May. the timeline is a little shorter than it usually is because we um I don't know what the   
5:03   
problem or what their their procedure is this year, but it's different and so we   
5:09   
don't have as much time to to a little bit less time to to submit stuff. Um and   
5:15   
so yeah, if you're applying to the open source sustainability project, either   
5:20   
apply to the reinforcement learning one or the large language models learning   
5:25   
one. just just find the usually if you go to the uh uh usually there is a   
5:33   
discourse through INCF and they have the projects numbered and I don't know what   
5:39   
the numbers are this here for each one but it's two different descriptions so just be sure to note which one it is I   
5:47   
mean we can kind of figure it out because we just read the content and we'll put it in that bin but just to be   
5:54   
clear just just make sure you you're targeting the right project. Okay, Ash,   
5:59   
you had a question. Yeah, I had this question that uh GOC   
6:05   
allows three proposal forms to be submitted for one applicant, right? Yeah.   
6:10   
So, does INCF have an internal limit that one person can only have two forms   
6:18   
or something like that? Uh and I think probably two. Yeah, I I don't   
6:24   
remember what their rules are this year at least. Um I in the past I know people applied   
6:31   
to like two projects or multiple projects. Uh one of the issues with that of course   
6:37   
is that you have to sort of you know get the best proposal you can.   
6:43   
So I mean you know there are all sorts of ways that people have done that in the past. Uh I would yeah if but I I   
6:51   
think the limit is like two or three. I don't know. You'd have to check, be sure to check the rules. Um,   
6:56   
yeah, the rules didn't state anything. I tried reaching them by email, but they didn't respond.   
7:03   
Oh, okay. Well, I don't know. So, sometime ago, the rule was uh there is no internal limit as such. Uh there   
7:10   
used to be a form that you submit to INC when you are submitting your proposal   
7:16   
and in that form you would have to mention which other uh projects have also applied for even if they are with   
7:22   
and see if you specify and even if they're outside you specify but yeah I   
7:28   
don't think there is as far as I'm aware I don't think there's any limit as such you just have to uh declare in that form   
7:35   
which are the proposals you are because if it's within CF of course we don't want we want to be able to   
7:43   
allocate projects from so that okay okay thanks for clarifying it   
7:50   
appreciate it a Yeah. Yeah. So, in terms of the proposals, um, a   
7:58   
little bit of advice on how to write them. I've I've been doing I've been a mentor for probably wait I think nine   
8:05   
years. This is my ninth year as a mentor and uh for GOC and it's, you know, it's   
8:12   
been pretty good. We've had a lot of people come and go and they've they put a lot of uh really good code into our   
8:20   
organizations. So one of the things that successful people do is that they uh you know one   
8:29   
one of the things our organization does it's kind of different from a lot of other organizations is that they you   
8:35   
know you can address a problem in your own way more so than like a lot of organizations will kind of have a very   
8:43   
tightly defined project and then you contribute to that. And a lot of the things that we have our our our um   
8:52   
project calls are very broad and it says you know this is the problem figure out   
8:58   
some sort of solution to the problem. You know it could be a wide range of   
9:03   
solutions uh and you know that's something that you would then uh have the freedom to to   
9:09   
propose a solution to. Now one of the benefits of that is you can do exactly   
9:14   
what you want or at least within the project. Uh the downside is you have to know kind   
9:20   
of what works and what doesn't. And this is why we have like interactions before   
9:27   
the proposal period because then you can get feedback on things and try things   
9:32   
out and see if it works, see if it doesn't work, etc.   
9:37   
And so if we do that, we can get um you know a pretty welltuned project going   
9:43   
in. So when you write your proposal, you want to um summarize your approach sort   
9:51   
of in the uh introductory paragraph. Maybe say why you're interested in the   
9:56   
project, you know, what you hope to accomplish with the project. And then you proceed to talk about   
10:04   
your approach. What what does it involve? Does it involve uh different types of methodologies, different types   
10:12   
of data sets that you might need to get access to? Uh you know what is the   
10:18   
problem statement? How would you address it? What's the scope of the project? And   
10:24   
that's important because the scope of the project is going to determine whether you can get it done in in the   
10:29   
amount of time we have. So we have like 10 weeks where you have realistically   
10:35   
eight or nine to do something and get it, you know, enough so that you   
10:41   
get results and that you can submit it to Google. So uh you know I don't know   
10:48   
what that kind of scope looks like for everyone's project. Um I would just think about um a weekly kind of account   
10:57   
of what you would do. So you you'd want to start so there first couple weeks of   
11:02   
the uh program is the community period which is where we usually spend time   
11:09   
getting to know the community getting used to things um setting things   
11:15   
up like you know maybe setting up programming environments or things like that. Now we take the community period   
11:21   
somewhat seriously in our organization. We try to you know help people   
11:28   
make connections uh or just basically get to a better   
11:34   
understanding of what's going on. Uh our projects are research oriented so you   
11:40   
have to understand the research a little bit that sort of thing. So after that then you have your weekly account of I'm   
11:47   
going to hit the ground running with uh setting up my environment. I might test   
11:52   
two or three models and I can work from there and and try to get a result by the   
12:00   
end. And then the last week is usually like finishing up writing up your um   
12:07   
your proposal submission, uh doing documentation, things like   
12:12   
that. So that's that's kind of what how this is going to look. And then the last part   
12:18   
of the proposal is going to be the schedule. So they always want to have   
12:23   
and I think it's good to have sort of an enumerated schedule where you have an   
12:28   
account of every week. So you say week one, week two, week three, etc. And then   
12:33   
in that table after the week, you'd say what you would do or what you plan to do   
12:38   
for that week. And then you also want to have some account of what happens if you   
12:44   
can't do something. Do you have sec, you know, second or third priority things you could shift to while you kind of   
12:51   
figure out that bigger problem? So, if you hit a roadblock, how do you get around it?   
12:58   
Uh, you know, better yet, how would you say if you had a problem with your   
13:03   
project, implementing your project, how would you kind of recover from that and do something   
13:10   
different? How would you how would you change direction? How would you rescope   
13:16   
your project if the scope is a little bit big? Because the idea of Google Summer of Code is not to   
13:23   
have everything perfect and then just kind of blast through the project. The idea is that you struggle with   
13:29   
implementing the project and everything. And you don't want to like, you know,   
13:34   
have a proposal where you say, "Well, I'll figure everything out during the project period." But what you want to do   
13:40   
is you want to have a pretty good idea of how things will work. And then you need to work through the project. And   
13:45   
when you're working through the project, you're going to hit roadblocks. You're going to be challenged with things and   
13:51   
you're going to have to find a way around them and uh something that works.   
13:57   
And so that's that's what you need to do. Um sort of introduce your problem, talk about how you'll solve your problem   
14:04   
in a schedule. Okay. Um so that's a little bit about   
14:11   
GOC. Um and again those proposals are due March 31st   
14:16   
and try to you know communicate with us in the Slack or on GitHub.   
14:24   
And I've been really impressed with GitHub uh communication this year and and pull requests. We got a lot of pull   
14:30   
requests this year and I'm going to go through that in a minute. So yeah, thanks to everyone who's contributed on   
14:37   
GitHub. We've had a lot of not just pull requests but like people helping each   
14:43   
other out or talking through problems and uh a lot of that has been in in the   
14:48   
uh large in the larger language models open source sustainability or open source community uh part of the   
14:57   
repository. So we have the repository for um GOC and then within that we have our   
15:03   
different mostly that's like the open source sustainability project. So we have different versions of things like   
15:10   
reinforcement learning and large language models and active inference   
15:16   
and most of that has been in the large language models area but anyways thank you for your contributions there.   
15:24   
So this is our organizational GitHub and if you've been contributing to the   
15:31   
projects you see that there's this G-Soft repository. So this is for the   
15:37   
open-source sustainability projects. Um, if you're trying to contribute to DVO uh   
15:44   
graph, we have a separate DVLearn organization where there's a DVO graph repository   
15:50   
there and that's where you would uh do pull requests and look at the open issues. This is our uh repository. This   
16:00   
goes back to this project goes back to 2022. So in 2022, we did a a first   
16:06   
season of this where we had people working on reinforcement learning, active inference, and some uh other   
16:14   
types of simulation um sort of a survey of what we could do to   
16:22   
address this problem. Then in 2023 and 2024, we worked on um some of the   
16:29   
models. So we worked on reinforcement learning in 2023. Then we did some large language modeling   
16:35   
in 2024. Then back in 2025, DD was um the person working on u   
16:43   
reinforcement learning. But we've been working on creating um basically hybrid   
16:49   
models where there's a layer which is an agentbased model and a second layer   
16:55   
which is some model like a large language model or reinforcement learn.   
17:00   
So that's kind of what this is and then um so where this lives is here is open   
17:07   
source sustainability using large language models. This is the repository   
17:12   
where we've had a lot of our pull requests. We actually have two open pull requests. I thought I had gotten them   
17:18   
all, but we had uh so two open pull requests right now. I'll take care of those   
17:24   
later. Um but we have a lot of closed pull requests.   
17:30   
And this is, you know, like all sorts of stuff that are different types of   
17:35   
updates to things, um, different types of functionality that have been added   
17:42   
and all of that. So, this looks really good. And I had one or two conversations   
17:47   
I wanted to highlight. So, this is the list of uh, closed poll requests. And again, we've had a lot. We had a one   
17:55   
which was the auto clear calculator. Uh that was fixed. We added a safety check.   
18:02   
Uh there was a um routing and simulation   
18:07   
scripts. Uh dynamic issue creation. uh I think the conversation space for   
18:15   
Slack-like interactions, which is good because we were doing things with GitHub and modeling GitHub um issues and so   
18:23   
Slack interactions are a nice functionality there. Refactor issue reading logic, fix   
18:31   
contributor assignment, your syntax errors and import errors.   
18:36   
uh this was in reference to so issue 112 is in reference to issue 108 and 109. So   
18:43   
it's this uh issue creation in conversation space. So it's people   
18:49   
helping people. Uh then there's add engagement metric to conversation space. Uh correct type   
18:57   
initialization and there's some other open repo or open pull requests that I'll look at later.   
19:06   
This was issue 99. This is add requirements.ext for lump uh for a large   
19:12   
language model open-source community dependencies. And this is where there was a   
19:18   
requirements.txt file added uh where it makes installation straightforward.   
19:25   
Uh currently there is no requirements text in the repository. Um, and this is just kind of a a thing   
19:34   
that makes it easier to use and so it added a requirement.ext file and that   
19:40   
was uh to the front-end guey. Okay, so that's for both Mac OS and Linux. All right. So this is just uh   
19:48   
giving the detail on the pull requests and then there was this conversation where   
19:54   
um we had uh someone pointing out I think it was a shot that our   
20:01   
requirements text was that yeah it was me. Okay. Yeah. Uh you just zoom in a bit.   
20:10   
Yeah. Let's see.   
20:16   
So a requirements text already exists under open source sustainability. Instead of adding a second one, I think   
20:22   
we should update clean the existing file. Having true requirements.ext files might be confusing.   
20:29   
And this is updating the existing file. So this updated the PR to modify the   
20:34   
requirements text instead of adding a new file. And so this is just adding the packages in. And then um another thing   
20:43   
that was flagged separately and that was accepted. So that was um   
20:49   
and then I guess I'm not I haven't checked the issues but the issues of course there are issues that have been   
20:56   
added as well regarding that and some other pull requests. Um this is another   
21:02   
one here. This is uh where 112 was opened and that resolved the syntax and   
21:10   
import errors introduced by 108 and 109. So it's issues 108 and 109 or maybe pull   
21:15   
request 108 and 109. Yeah, the uh dynamic issue creation enablement was   
21:20   
was uh 108. So I guess it's issue 63 pull request number 108.   
21:27   
And then that's so that's this PR which is 112 fixes to uh the enabling dynamic   
21:34   
issue creation which was 108 and adding conversation space to simulate slack like interactions 109. So   
21:42   
these are the syntax and import errors respectively. Syntax error in run uh the   
21:47   
run file and then import error in the simulation file sim.p py.   
21:54   
So then this is just kind of showing how to test. And then um yeah, this was uh   
21:59   
thanks for catching this. This was Huffy's exexe.   
22:04   
Um and then this is just kind of like if you issue a pull request. Sometimes   
22:11   
uh you know different types of inconsistencies are catched by the continuous integration and sometimes   
22:18   
it's not. If you look through the code, you'll notice maybe something or if you notice at runtime, you download it and   
22:23   
do something at runtime, you'll notice that. So, it's nice that people are catching these and helping each other to   
22:31   
address the issues. Um, so thank you everyone who contributed to um the repository.   
22:39   
The other thing I'd like to talk about is the D.VARM meeting from this last week. So, this was meeting number nine   
22:45   
and of course we do these on Mondays. Um we had uh Baron uh Mandal he   
22:53   
presented on his project which was incorporating attention into DVOGraph.   
22:59   
So DVOGraph we've been working on uh an approach that's basically we segment   
23:06   
features out of microscopy data sets and other types of data sets.   
23:13   
Then we build graphs, graph representations using those um segmentations and maybe   
23:20   
using some other data where we create uh nodes which are maybe like centrids of   
23:26   
features or it could be like other types of data that are entities and then we   
23:32   
build these edges that are relations of those entities or features and we can build graphs   
23:38   
that um we build regular networks. We can build hyper graphs which are   
23:44   
networks that are embedded in other networks. We can build um other types of   
23:50   
descriptive graphs. We've been talking a lot about tensity for example in the meetings or we've been talking about   
23:57   
other types of tissue morphogenesis and so and then of course we have uh   
24:05   
spatiotemporal graphs which are where we of course the graphs as developmental   
24:11   
things are embedded in space but they're also embedded in time. So we want to look at the temporal graph learning that   
24:18   
happens in uh which which you would model in graph neural networks but is   
24:25   
actually something that we're interested in in terms of development.   
24:30   
So this is working with conto data which is like in in the C elegance nervous   
24:35   
system you have cells that are connected through uh different types of connections. We can characterize those   
24:42   
connections from existing data. We can characterize the cells but we want to   
24:47   
model thing aspects of the conneto related to behavior and related to other   
24:52   
sorts of activity. Um and so this is what Baron is is doing in this   
24:58   
presentation. He's using this uh explainable spatiotemporal graph learning evol or   
25:04   
learn graph evolution learning approach or SGEL. And this is where they're validating   
25:11   
this in a neuroiming data set and it's showing how in that data set uh brain   
25:18   
functional networks which are usually the networks that they look at using fMRI where they look at the activity of   
25:26   
um different pixels of brain tissue and they look at the hemodynamic response.   
25:32   
They can look at those networks as sort of proxies for what's happening in the conneto, the human conneto, but it's   
25:39   
also looking at that over time, how it changes when you engage in cognition or   
25:45   
you age or whatever. And so this is the neurodedevelopmental cohort. This is   
25:50   
where this method that he's proposing successfully modeled how brain function networks transition from dispersed to   
25:58   
convergent modular structures during development. So it's like this increase in organization.   
26:06   
So then there were a bunch of baseline tests. So he's he's kind of talking about SGEL   
26:12   
and um so this is like a method that people have used in like network brain   
26:20   
networks and things like that. And now he's kind of bringing this to the DVO   
26:25   
graph approach. Um and of course in graph neural networks that's a whole   
26:31   
different field if you're used to like large language models or you're used to um like reinforcement learning or just   
26:39   
regular machine learning. It's it's very very unique in a lot of the ways in which it deals with data and models   
26:45   
data. And so they don't necessarily have an attention mechanism built into that   
26:52   
those types of algorithms. Usually you have you know a a graph representation   
26:58   
and then you have maybe message passing which is like how you model things moving from node to node information or   
27:06   
flows and then you have other types of um symmetry processes and other types of   
27:14   
uh processes to enable you to to construct new graphs to find all um   
27:19   
optimal graphs etc. So it's very very different from typical   
27:25   
machine learning. So this is where he kind of wants to make this connection   
27:31   
um not just with um using brain something from the brain network   
27:36   
literature but also from the regular machine learning literature.   
27:41   
So this is talking about the dynamic relation learning module which uses a gating   
27:48   
mechanism if use historical and current network states ideally for modeling   
27:54   
embryos where past cell divisions influence future structure. So he's kind of going through like kind   
28:00   
of making this transition uh this dynamic relation learning where   
28:06   
it's capturing spatio temporal dependencies. Uh this is the proposed evo graph   
28:12   
integration workflow where he's saying that you have this these developmental   
28:18   
data on the left. You then have this dynamic graph construction from the   
28:23   
data. You have this uh graph decomposition step and then you have the   
28:29   
dynamic uh learning step. You have this readout and you get these two things   
28:35   
which are one is which is explainable dynamic graphs and then predictive   
28:41   
embeddings for sulfate and morph for genetic mapping. So and then he did this   
28:46   
visualization in npari which is a program that allows you to visualize   
28:52   
highdimensional data. This just shows like the lineage tree as it's moving,   
28:58   
you know, as it's bu it's it's being built. So that's interesting. Um also   
29:03   
what's this other thing the gaze graph it's here this is actually another thing   
29:09   
that he talked about which is really interesting um technical detail.   
29:17   
Okay. So then we had uh some discussion on this and then Ukar   
29:22   
uh Thiagi he presented on his work. He's been presenting on this work um that   
29:28   
he's been doing. It's been a lot of different things but I think it's focused   
29:34   
on um what is it?   
29:39   
I can't remember what the title of his little notebook is here, but he has this   
29:44   
notebook he's pulling out and it's so he's thinking about building this model   
29:49   
where you're incorporating chemical signaling physical properties of the   
29:54   
embryo um biohysical properties in particular   
30:00   
and and then modeling things like that. So he's showing this work that he's   
30:05   
doing here. Um he's we're this just follows up on some things that we were   
30:10   
talking about with respect to um you know what do we include in a model of bi   
30:16   
biological complexity. So we can't include everything but we don't want to   
30:21   
make them so sparse so that they don't represent biology and so that's always a   
30:26   
challenge. So we're talking about that and he was kind of addressing those points and then uh this is these are   
30:33   
diffusive spatial graphs. So this is a bottomup approach. Um and then this is   
30:39   
just kind of this general model type idea um using a formal sort of framework.   
30:47   
And again he goes through some more of the stuff. Um   
30:52   
then he uh goes on to this uh this is actually um   
31:00   
uh Shreas and he is talking about this u these   
31:06   
hyperbolic spaces for the conneto. So the idea is that the conneto is you know   
31:12   
you can model the conneto in a lot of different ways. Usually people model it as this sort of network that is just you   
31:20   
know it's a network. It's not really embedded in too uh intimately into the   
31:26   
um anatomy. Usually it's like okay these cells are in these locations but they   
31:32   
don't build like a representation of that space. And so this is where he's talking about building a conto and   
31:40   
embedding it in a hyperbolic space. And the reason you might want to do that   
31:45   
is because then it gives that graph some spatial relevance to the anatomy uh   
31:53   
beyond just simply like location. It also allows you to do u you know   
31:58   
implement ODS or neural ODS for applications to graphs and graph neural   
32:05   
networks. So this is where he kind of thinks about the u the the structure of   
32:11   
the conneto the uh hyperbolic embedding.   
32:16   
Um and he was talking about these punk array maps which are like representations of the space   
32:23   
um this sort of hyperbolic space. And so if you're given a discrete   
32:29   
conneto, snapshots of a discrete conneto in time, the goal is to learn a   
32:34   
continuous developmental model which is stated here. The constraints are it must be graph-   
32:40   
based. It must use hyperbolic space meaningfully. It must be biologically   
32:46   
grounded and it must interpolate between stages because usually our data is sampled in stages. You get like   
32:53   
measurements at specific times and you get these static connetos. And what we want is want something that is   
33:00   
continuous. To do that, you have to do some interpolation. And that's why we're doing the   
33:06   
interpolation, but also that interpolation benefits from the hyperbolic space.   
33:12   
And so this is just talking about why hyperbolic spaces. Hyperbolic geometry naturally includes   
33:19   
hierarchy and is similar to a geodeic. So if you're measuring a distance from uh neuron to neuron, you're thinking   
33:26   
about um like communication between neurons or you're thinking about like   
33:32   
axon finding between neurons or whatever. Usually you're not dealing with equity distances, you're doing   
33:39   
geodeics. So if you're measuring this two points on the surface of a sphere, you don't   
33:45   
draw a straight line or a like a plane won't fly in a straight line. it'll fly   
33:50   
according to a geodeic which is different and you have to deal with the math but it gives a better   
33:56   
representation. So then he talks about hyperbolicity   
34:01   
and then there's this punk array disc which is where the embedded the conneto and this actually it's the network where   
34:08   
you have a degree of connectivity. So you see the highly connected nodes are in the center less uh the more weakly   
34:16   
connected nodes are on the edge. So that looks like an interesting result.   
34:21   
Um, and then thinking about radial hierarchy,   
34:27   
which is what we're just looking at. And some more tests there is radial drift,   
34:37   
which is where you have radial change and why you have radial change.   
34:44   
And then some things that happen over development across stages. This is just showing the different stages. And then   
34:50   
the idea is that instead of having this kind of jagged function here, we have a   
34:56   
smooth continuous function and we interpoid the events in between.   
35:02   
That was good stuff. Um and then we want to add graph neural networks or graph networks into this where we can actually   
35:10   
then um capture some of the motifs and community effects   
35:16   
and so forth. Okay, so that was all I had on what we did in the last week. I   
35:22   
think that was pretty good. Uh and then of course talking about the G-S proposals and everything. Um so yeah,   
35:30   
get yours in as when you as soon as you can. Uh the deadline is the 31st.   
35:35   
A lot of interesting stuff this year. Uh another thing Jesse mentioned in the   
35:40   
Slack was there were some emails in the uh mentors uh thread or the mentors channel which   
35:48   
is like you get emails and a lot of emails sometimes but it's always fun to look at what they're talking about   
35:54   
across different orgs. One of the things this year was like people were using AI   
36:00   
a lot to make uh submissions and pull requests and it's like for some contri   
36:06   
or for some org heads for some mentors it's becoming a burden because there's so much content and uh I don't know   
36:14   
Jesse asked me how I felt about it and I was like well I don't know I guess it's not horrible if it's not junk you know   
36:22   
what I mean like if people use it responsibly or if people are actually   
36:27   
putting in the effort to make a good faith project. And so, yeah, it's it's   
36:32   
it's a controversy, let's just say, within that um that group of people.   
36:40   
So, that's just uh I might talk about that later in more detail. Yeah, maybe another meeting. Um so I   
36:48   
think Ashot wanted to present his things here um today   
36:54   
and Sara's here because Sara is the mentor for this project that we're going   
36:59   
to be uh looking at here. So um would you like to share your screen?   
37:06   
Okay. So I'd like to start with a brief introduction. I am Ax and I am an   
37:12   
electronics engineer like I'm meant to be an electronics engineer. However, I have drifted a bit into AI and CS stuff   
37:20   
because it honestly looks so interesting and so I was looking through GSOC and   
37:27   
found oral lab and this project looked really interesting. So I have been contributing for past week now.   
37:35   
So I'd like to uh this is not my proposal by the way. I'd like to just   
37:42   
talk about some issues that that can be tackled before the proposal period   
37:47   
actually starts. So the GOP part actually is more focused rather than   
37:53   
solving uh minor problems like these. So the current uh setup that was added   
38:02   
yesterday I think yeah it was uh added by Satya Kapari   
38:09   
and he basically added a fire vector database which was updated uh every message but   
38:17   
that was too efficient that was too inefficient it was taking very long so I pointed that uh it should   
38:25   
be done in batches of like 3 to five messages. That way the fires database   
38:32   
doesn't have to be updated after every single message because it is not actually updating. It is just deleting   
38:39   
the entire thing and then it is rewriting with that one extra message. So that system was very inefficient. So   
38:47   
I thought about this and I'd just like to talk a bit about the current setup.   
38:53   
We have one one contributor agent sends a message in the conversational space   
39:00   
then it will be registered as a message and that message will then wait until   
39:06   
the batch finishes off. I think it was three but until those three messages   
39:11   
don't come it just waits and then it is embedded into files and then it is   
39:17   
retrieved. So this had two major problems. First is   
39:22   
that it has it doesn't actually simulate a conversation which is the aim of the   
39:28   
project and second problem I think is the chat history and the git history   
39:33   
they are not connected we are basically making through two different environment   
39:39   
where there is only chatting occurring in one and get things occurring in   
39:45   
another. These two are not connected. Now that is not how real developments   
39:50   
work in Slack. We generally link like I have sent this PR I'm working on this   
39:56   
issue. So I thought that is not what we are simulating. We are not doing that   
40:03   
correctly. So here's my proposed context structure for   
40:09   
the project. We basically have a message base where we will have sender content   
40:18   
and whatever issues or PR it is trying to converse with that way we actually have context   
40:25   
so LLM knows what to answer how to answer what is being talked about   
40:31   
essentially and then we have a PR database which will have ID now ID will   
40:38   
act as the primary key to uniquely identify the PR or issue like we see in   
40:44   
Git we have issue number 108 we have issue number 68 PR this so that way we   
40:51   
can actually link G and messages then the PR will have content whatever it's   
40:57   
trying to convey and related lines of code and I didn't actually think this   
41:04   
hard enough but I'm thinking we can also write lines of code in another   
41:12   
part which basically has pointers that this is the file we are talking about. This is where the related code starts.   
41:21   
This is where the related code ends and like that. So that way we are able to   
41:27   
just send message then we can add some logic to also fetch the context provided   
41:32   
in the PR and issues and etc. That way AI is able to converse more efficiently.   
41:40   
Now anyone have any thoughts about this? Uh yeah. Hi. So when you said the   
41:48   
current scenario uh did you mean something introduced by one of the recent PRs? Yeah. Yeah. It was introduced just   
41:55   
yesterday this part. Yeah. Yeah. Right. Okay. So Okay. So were you the one that introduced this or   
42:02   
was it somebody else's PR? No. No, it was Yeah, I think I only   
42:08   
reviewed it. It was I just told one correction. He did most of the work.   
42:14   
Okay. Okay. Sure. Yeah. So, I get your point. So, the thing that you pointed   
42:19   
out, right, that we need to have a connection between uh   
42:25   
the conversation space and the code space. Yes. So, yeah. So, I like this idea as well.   
42:31   
uh what you can do is on the uh GitHub only on the PR you can uh suggest this   
42:38   
and then you can tell Satya whoever it is that you know started the PR that you   
42:44   
are working on this part so that you don't have code conflicts because if he's trying to open something else uh   
42:50   
that will be an issue so you can discuss with him and maybe he will also have some ideas so you can collaborate on the   
42:57   
PR and we'll keep reviewing Okay. The PR is already married. I think   
43:03   
I should open a new issue with this architecture. Sure. Yeah. Sure. Sure. Sure. You can do   
43:09   
that. And you can also just uh tag uh the original contributor as well.   
43:15   
Okay. And link the original PR. Yeah. Yeah. Okay.   
43:21   
So now I'm moving on to the second problem. The memory system.   
43:26   
See, I'm now thinking that we humans have basically two types of memory. Short-term memory and long-term memory.   
43:32   
Short-term memory is whatever occurred in 15 or so minutes ago. And long-term   
43:38   
memory is the memories we have ever since our childhood. So now for   
43:44   
short-term memory, what I'm thinking is we have a sliding window like algorithm.   
43:51   
This notes the last five messages we have sent and these are provided to the   
43:58   
agents whenever they try to take an action. Now through this we can actually   
44:05   
simulate a conversation. For example, let's assume message n minus one was I   
44:11   
am working on this issues. So then message n will be yeah and this issue   
44:17   
can be tackled like this. this has these shortcomings   
44:22   
and like that and for long-term memory this is mostly implemented right now I   
44:28   
think this this updates every X messages and is used for only semantic searches   
44:36   
so for example someone's working on issue 51 which was very related to a   
44:44   
previous issue 24 let's say so through long-term memory we can fetch the previous issue and whatever discussion   
44:52   
related to it through vector databases. So I will also be sending this to the   
45:00   
issues tab so people can start working on it. Okay. Now the second main shortcoming of   
45:08   
this project is the current agent calling. Now in this it is basically a   
45:14   
for loop. Alice talks then Bob talks then Carol Dave and so this is very a   
45:21   
robotic simulation of this for example let's say we are Bob so then we can only   
45:27   
respond after Alice says something and only Carol can response to what we are   
45:32   
saying so this is not a very good real simulation right   
45:39   
so why this fails basically if we graph the percentage of a messages sent by one   
45:47   
person it is basically 20 2020 20 now this is very robotic so I'm suggesting a   
45:55   
pro probabilistic selection here that the probability of a contributor acting is calculated by the   
46:03   
motivation of that contributor and we can divide it by the motivation of all   
46:10   
other contributors combined so that we can actually get some realistic   
46:17   
distribution of conversation. A person uh sorry an agent who is more   
46:22   
motivated will tend to talk more like Alice and Carol here and some agents who   
46:29   
are less motivated such as Eve they will tend to talk less. We can basically we   
46:36   
can have max this much responses per 10 contributor so that one agent doesn't   
46:44   
dominate the entire conversation and it will not become it will become a monologue that's not a conversation and   
46:51   
we can also add some limitations that no contributor shall speak by scenario because one agent will send something   
46:58   
then it will wait for someone else to response and motivation I think is   
47:03   
already implemented. We just have to use it to simulate this entire simulation.   
47:10   
So any thoughts on this approach? Um so to be clear, the way it's   
47:17   
implemented now is sort of a serial conversation. Yes. Yes. It's a loop basically.   
47:23   
Uh uh so Akit uh in the so I mean uh not   
47:28   
about the recent PRs. I don't know if there's been any changes uh but in the main like in some time ago there were   
47:36   
two uh methods right in which it used to take one was   
47:42   
authoritarian. Yes. Yeah. Yeah. So which one are you exactly uh talking about when you say it's   
47:48   
serial? Do you have any example of it? Have you tried it? Yes, I have screenshot. Uh   
47:56   
I I didn't prepare any screenshot but I think I should have some   
48:02   
enclosed PRs actually this was very recently I want   
48:08   
to correct one thing no worry I want yeah this is about the   
48:13   
conversation that was recently implemented the conversation not the earlier   
48:20   
conversation okay sure okay basically suggesting a weighted   
48:25   
Yes. Yes. Yes. Sure. So, yeah, the get the G one uses bidding   
48:32   
and something. Yeah. Yeah, that's what I was coming to that you can maybe also take inspiration   
48:37   
from those for. Mhm. So, as Yeah. Yeah. Sorry.   
48:43   
Yeah. The git one was is working very well. I agree with that approach. The bidding one, we use the experience to   
48:50   
wait the uh action probability. So we can we can also do the similar thing in this as   
48:57   
well but the conversation space is just like I told it is like not very this is not connected with the   
49:04   
git part it's thing we connected it yes yes   
49:10   
yes okay another thing that I can suggest for weight readers I believe vhi has also worked last year on using uh   
49:19   
weighted this in her project so you can also have a look at that and then you   
49:24   
can finalize a formula and you can try to implement it. Okay. So your formula looks good. I'm just   
49:30   
saying you can uh you know also do a little bit more research on how it uh has some real life uh impact.   
49:38   
So you can find some uh kind of research that suggests how people uh speak real   
49:45   
in the real life. So for example, you make a statement like we should introduce a limitation of no contributor   
49:50   
speaking twice in a row. But sometimes that does happen realistically, right? Yes. So I'm saying anything that you try to   
49:57   
introduce as a limitation or as a formula, try to have some real life research that is backing that up. So for   
50:04   
example, that is why I brought up the authorative and those models because they are based on models that we have   
50:11   
you know observed that people fall into. So you can try to do some similar research for this and then try to come   
50:17   
to the code and formula later. Okay. So as also said, yeah, it's more research   
50:23   
based. So make sure to have something backing up all your uh Okay. You know, if you try to introduce a new   
50:29   
formula. Okay. Yeah. I'll look into some researches. This was like very primitive   
50:36   
like I was just telling my idea. Yeah. So it's a great idea. I'm just saying you can before you start coding   
50:42   
try to look at it some more. Yeah. Yeah. I'll look into some research paper. I'd like to add a little bit   
50:48   
about that too is that you know sometimes this is what conversations look like   
50:54   
having seen a lot of like conversations and teams and that and sometimes they're people who are   
51:00   
speaking more and like if you do um for our Jity uh instance you know I'll often   
51:07   
look at like how much people have talked during the meeting and it's like usually a couple people have talked most of the   
51:13   
time and a few you know a lot of other people haven't really contributed. very much and that's a pattern that you get   
51:19   
and the question is is that some I mean it's a real pattern but is it desirable   
51:25   
and one of the things that we've tried to do through the history of this project is to simulate   
51:32   
you know uh teams open source teams and say um you know can we improve upon our   
51:39   
performance in teams can we model kind of realistic   
51:44   
uh you know scenarios But then can we improve upon that and how would that happen? So you know   
51:51   
having this distribution is nice because you can actually play with things in the code and modify how those conversations   
51:58   
happen and see what the results are. Yeah. Yeah. Another thing that not   
52:04   
specifically to you Axhat but uh advice in general uh so I can see a lot of uh   
52:10   
contributors trying to contribute for the conversation space. So uh one thing that I just wanted to uh put out there   
52:17   
was the whole so I mean I love these contributions uh as they are like you know small pull   
52:24   
requests uh as like kind of quick fixes. So we have a primitive idea of a   
52:29   
conversation space but when we actually start working in the project in the timeline of GOP uh the main idea behind   
52:37   
conversation space was similarly to how code space takes actual GitHub history.   
52:43   
The whole idea behind conversation space wanted to be that it takes from a   
52:49   
organization's existing conversation whether it is happening on slack or   
52:55   
whether it is happening on some other platform it pulls that actual   
53:00   
conversation it pulls the actual contributors who are talking about it the same way for git when we add the   
53:07   
GitHub link it takes that and then it goes through that it takes the existing pull requests and then it works on   
53:13   
making new ones. So the similar way for a accurate uh simulation what we want to   
53:20   
do is take the existing data take the existing contributors analyze their   
53:25   
behavior and then simulate how they would act in the future and so that is   
53:32   
what so this is a quite a complex it requires integrations and it requires a   
53:37   
lot of research so I just I obviously do not expect this in uh current PR But   
53:44   
this is something that I would really encourage anybody who's you know all the contributors who will even look at this   
53:49   
video I would encourage you to start thinking about it because apart from just your current PR the main thing that   
53:56   
you'll be working on in the coming few weeks is your proposal and in your proposal you would like to propose what   
54:03   
ideas you have for the entirety of the project duration. So yeah just a   
54:08   
suggestion on how to start thinking about it from now on. Yeah. Uh as I've I've also seen in   
54:17   
recent PRs as uh Mr. Bradley mentioned that LLMs are being used without   
54:23   
understanding the code. Yeah. I think our rep was also suffering a bit from that.   
54:29   
Yeah. So yeah I would I would I mean so the PRs are obviously it's an open   
54:34   
source repository. PR are accepted and then as you know as we also saw it   
54:39   
happen some PR introduce some bugs someone else points out those bugs so that's where the whole collaboration   
54:45   
aspect comes in so that's fine that's from an open source repository perspective that's completely fine but   
54:52   
from a g perspective you do need to think a bit into the future and plan out your whole project   
54:58   
yes we need to reduce the technical depth from every uh PR we commit to the   
55:05   
project so that let's maintain everything. Okay. Now uh this part will actually   
55:13   
will be going to my PR. I just wanted to discuss uh what is the current way what   
55:20   
is the best way to implement uh this entire model. Currently we have   
55:29   
a lot of steps get clone then we go into CD we install some things we install the   
55:36   
requirements we install Oola we get the docker running we make an image then we   
55:42   
have to run that every time we try to start the project so I'm now this is only some food for   
55:50   
thought that we can also have uh basically a py PI library pip install   
55:58   
llm with this uh project and we can run it like UV icon if someone has used it like   
56:05   
we just type one command and it sets up itself on its own. So   
56:13   
uh I'd like to write uh why should we use the tip?   
56:19   
Firstly, it gives a lot of accessibility. We do not need a lot of   
56:25   
setup and uh coding knowledge to start working or   
56:31   
inferring data from the framework. But this will also have some drawbacks   
56:39   
which I am telling in this slide. that the pip package will need a lot of work.   
56:44   
The current project we have is a lot closer to being a full-fledged   
56:50   
repository which is only targeting a niche amount of people who want to research how conversation works and how   
56:57   
we well we can simulate it. We can like bring it a bit to more accessibility.   
57:03   
However, this will need a lot of work. So we need to replace the ACR and   
57:08   
dockers with other alternatives which may be light or uh doesn't need   
57:15   
that much installation as we are doing currently in this project   
57:20   
and basically allowing the web installation will also   
57:28   
attract more contributors I think now I haven't been much active in the open source space but I believe uh Making it   
57:36   
more accessible will reduce the barrier for entry we have for contributors. They   
57:43   
don't won't need uh they won't need to do through such tedious steps and yeah   
57:51   
this way we can attract more contributors but the way I think is will be much harder than if we just let it   
57:58   
be. So yeah, that was Yeah. So any thoughts on um this   
58:05   
proposal? This part will be going into my proposal. I think it's a good idea.   
58:11   
Yeah, it's a it's definitely a great idea. It's definitely one of the things that we want to do to make it more   
58:17   
accessible and more like a software that people actually use. Not just contributors, but even people who want   
58:24   
to use it in their day-to-day actually start uh using it. Uh so that's one of   
58:29   
the steps forward for sure. Uh a pip library is also a very good idea. Uh one   
58:35   
of the things I would encourage you to start looking into is uh firstly uh uh   
58:40   
you are suggesting that we still install manually and then run the pip package   
58:46   
and so that's absolutely fine because need to be on your local system.   
58:51   
One thing that we need to look into is how will uh we have the configuration.   
58:56   
So if we make it a pip library apart from just making it once it's installed how will the user connect it to their   
59:03   
local how will they bind that uh second thing how they will choose the model like   
59:10   
choose the model how they will yeah how they will make sure the f package runs their local there'll be configuration   
59:16   
steps there so you can start looking into that and secondly uh you are I think suggesting   
59:22   
that we don't have a local docker image and we have something running on the cloud some alternative.   
59:28   
Yeah. Yeah. So you can so I'm sure there are docker cloud alternatives where we can have an image hosted sort of uh but   
59:35   
you should start looking into that if there are uh even also if you start looking into something hosted if there   
59:41   
are any costs associated. Uh so   
59:47   
you should find out that as well and we should try to make it easiest as well as   
59:53   
uh something that is the you know most cost effective way because it is open source at the end of the day.   
59:59   
Yes. So you can look into that and how all these configurations like whether it is possible and also if there are any   
1:00:05   
alternatives to making it a pip library that make it easier to run with docker and   
1:00:12   
so you can look into that. Yes. Yeah. And uh about the cloud part, I was   
1:00:17   
thinking that we can also have an option to run it locally, but we don't need as   
1:00:23   
much setups as we need here. Like we can have a Python script to set that all up.   
1:00:30   
Docker image. Yes. Yeah. So yeah, you can look into that as well. So you can just start mapping out   
1:00:36   
all your options and consolidating them. Okay. Yeah. Okay. Thanks a lot.   
1:00:48   
Sorry Bradley, I thought you wanted to say Oh, yeah. Yeah. So, I had a technical question about this. So, what why do   
1:00:54   
orgs use or why do packages use pip install over like install or what's the   
1:01:00   
advantage there? uh uh most of the   
1:01:08   
uh researchers and developers know Python the best I believe because it's an easily accessible language and the   
1:01:16   
current framework works entirely on Python. So that's why I wrote you can   
1:01:21   
talk but I I haven't actually mapped this up. I just wanted to collect thoughts that   
1:01:28   
should I work in this direction. Oh well, yeah. I mean I I guess you know it   
1:01:35   
might be advant advantageous like you said though there's a tradeoff between power users and   
1:01:42   
uh casual users. So that's um that's I what is so what is the is pip   
1:01:50   
for casual users more than for power users I believe so yeah pip is uh very much   
1:01:58   
more accessible than setting up all github and uh docker images and such all   
1:02:04   
that so pip does reduce it we can also map it   
1:02:10   
to an exe later on I think we just tap it and it works.   
1:02:15   
Yeah. But first we we will need to work in steps. So I believe making it into a pip   
1:02:22   
will be a huge step and making it to an exe will be much easier   
1:02:28   
I think because we can just directly convert the Python file into the .exe file.   
1:02:34   
Yeah. But this will require a lot of coding. So I'm a bit worried about on that track.   
1:02:40   
Yeah. Well, no. I think it's, you know, eventually we'd like to have like different options for doing installs and   
1:02:47   
things, but yeah. I mean, it's I'd have to do more. I I just because I'm just curious why   
1:02:54   
people use pipes. Yeah. Yeah. So, Bradley, what h what's the I mean the technical answer to your   
1:03:00   
question is uh the first way is what we use cloning the whole repository and running it. or to use when you have   
1:03:06   
intentions to contribute when you have intentions to change the code and see the changes on your own. Whereas pip is   
1:03:13   
a packager. So it's one of the most widely used packages for Python. So what it does is it has like the sort of   
1:03:20   
compiled code. You can't actually make changes to the code but you can run it very effectively because it's already   
1:03:26   
packaged. And there's of course other alternatives also. There's poetry, there's UV that works uh directly but   
1:03:33   
pip is uh so as again mentioned by ash what is because the whole project is already in python and pip is also python   
1:03:40   
based it would be a very easy transition to pip but yeah when when users would   
1:03:46   
use pip they would just have the software running would do not be able to change the code directly from the pip   
1:03:52   
package okay so that they would have to go clone the repository right yeah   
1:03:58   
That's, you know, that's something to think about. Um, yeah, but that's I think that's probably   
1:04:03   
like secondary to actually doing something with Yeah. Yeah. Yeah. The steps comes after we do   
1:04:11   
all these things. Yeah. I mean, yeah, we I don't we don't really have a huge active user base, so   
1:04:17   
I don't know how useful ultimately that would be. Yeah,   
1:04:22   
well eventually making it to PIP will expand the user base because it will   
1:04:27   
become more accessible as I told. So there will be more users I believe.   
1:04:35   
Either way this was my presentation. Thanks a lot for the opportunity to share my ideas.   
1:04:42   
Okay. and and uh I was also I wanted to warn about   
1:04:49   
one thing there's the uh opensource uh repository called neutralojs   
1:04:58   
I believe neutralinojs something like that it had a very u major security   
1:05:04   
breach I believe just yesterday or two days ago uh one GitHub user was hacked   
1:05:12   
and he wrote in some malicious code into the repository thereby infecting   
1:05:19   
very large base of the contributors. So I just wanted to give a heads up with   
1:05:25   
this situation. Yeah, thanks. Yeah, that's not unusual. Unfortunately,   
1:05:33   
there are a lot of cases where um sometimes if you get uh there was one case where a maintainer was paying   
1:05:40   
attention and someone had put the ZX incident. Yeah. Yeah. Malicious code into things   
1:05:46   
or so. Yeah, it happens unfortunately more than we'd like.   
1:05:52   
But either way, thanks a lot for letting me present. You're welcome. Yeah, thank you for that   
1:05:58   
um great um work. ideas, things like that. All right.   
1:06:06   
So, yeah, thank you. Um, Sara, did you have anything else to say   
1:06:12   
or? Um, yeah, just very happy and excited to   
1:06:18   
see all the recent uh activity on GitHub. I'm sorry I've been a bit busy the past week, so I could not uh check   
1:06:26   
go through everything. So, I'll be doing that over the weekend. And uh yeah to   
1:06:31   
also to all the contributors I think when we put this uh video up on YouTube   
1:06:36   
uh we can put it up uh in the GOP channel as well and encourage more of   
1:06:42   
our contributors to join these meetings. So because apart from the PRs and the code this is where we have the   
1:06:48   
discussions and this is these discussions is what will form the base of your proposals when you start writing   
1:06:55   
them which is quite an important part in the GOC journey. So yeah, looking forward to having more contributors   
1:07:01   
joining. Yeah, very good. Thank you. Yeah,   
1:07:08   
all right. Um, so yeah, I see that Morgan and Jesse are here.   
1:07:22   
Yeah. Hi, Jesse. Hi, Morgan. Uh I don't know if either of you wanted   
1:07:28   
to give an update or how you want to do that.   
1:07:33   
I I can you know speak basically. Um I would want I know I missed   
1:07:40   
um the earlier part of today's meeting basically. So I don't know I don't know what if it was just all Gox stuff until   
1:07:47   
now um what happened earlier today. Basically Gox stuff. Yeah.   
1:07:55   
Yeah. Um, a few folks have reached out to me, which I'll be getting back to. I'm in a   
1:08:00   
similar situation at SAR. Um, I'm just getting back from a lot of traveling and   
1:08:08   
various events and family stuff, so I'm kind of catching up on   
1:08:15   
uh emails and some messages about this and other other   
1:08:20   
projects. Um it's a really interesting time. Most of my updates aren't GOP related. Um but   
1:08:30   
just just just pushing some things forward and there's been a lot of   
1:08:36   
progress this year and I haven't really had a lot of time to talk about some of those things. um   
1:08:43   
kind of from uh from the   
1:08:49   
just as a very brief overview without going into depth on anything. Um,   
1:08:55   
in terms of like old old uh   
1:09:03   
the the old um I say old magic the in   
1:09:08   
terms of much much older older tires that go back years and years. um   
1:09:14   
Frontier Map is is being developed in into some like working papers and beyond   
1:09:21   
now and sort of demarcating the different versions of what Frontier Map is. Um, and it's it's nice because sort   
1:09:28   
of it's related to um   
1:09:33   
it's not it's not there hasn't really been a full release of let's say the the Job Pro Future Center,   
1:09:42   
but as I'm developing that a part of a suite of things that we're working on   
1:09:48   
are basically Frontier Map um and a lot of associated   
1:09:56   
projects around like comprehending. One of them is sort of uh organization like   
1:10:03   
almost meta science or meta meta science and organizations of like the landscape of of certain groups that are dealing   
1:10:10   
and sort of what their schools of thoughts are about um how fields are emerging. let's say um there's a project   
1:10:18   
around um um for a long time Bradley and I have had   
1:10:25   
conversations around um you know more how to encourage more   
1:10:32   
synthetic time either in convers uh academic conferences or events or   
1:10:37   
whatever this sort of time where not just people come and point their you know oh here's my idea here's what I'm   
1:10:43   
working on that's great answer the questions and go on, but something that's integrative for the community   
1:10:51   
um or and how how things are spoken about. So part of that um there's   
1:10:57   
there's a component to that that I'm working on that's sort of around um   
1:11:03   
something along the lines of demarcating the the problem space or demarcating the   
1:11:08   
domain of the discussion or of what was being said in terms of especially for   
1:11:14   
like relevant for inter interdisiplinary discussion. Um   
1:11:19   
I'm I'm being a little hesitant in how I word that because um   
1:11:25   
there's a working title for that. Uh so Frontier Map, the landscape, the problem   
1:11:30   
space project. Um those are those are in development. Um   
1:11:37   
there's one or two more that you know um have have ties there. Uh but   
1:11:48   
front frontier map is something all the way back from I think like 2019 or 2020 that's that's existed and hasn't   
1:11:56   
really been materialized but it it it's kind of forming I think part of   
1:12:03   
internally speaking myself as in I think part of what's been   
1:12:09   
what's helping it come out now is that there's sort of a uh a suite of   
1:12:16   
things uh emerging together that are that are sort of presenting almost like   
1:12:22   
a an ecosystem of of related tools or concepts um which which is you has has   
1:12:30   
some some interesting overlaps to uh longer term Google summer code projects   
1:12:36   
too but we'll get into that that some other time um other very very very very   
1:12:41   
quick things to to to try to mention um and go more in depth maybe we But just as a a very brief um update   
1:12:49   
from from my vantage point and for folks that don't know me, hi I'm sort of I'm Jess. I'm um sort of a research   
1:12:56   
coordinator here. I've been I came in many years ago through Google Summer of Code. Um,   
1:13:04   
I stayed with the program to develop some ideas and then I Bradley sort of let me um make things like cognition   
1:13:12   
futures which is sort of a working group that um has sort of crested a little bit   
1:13:17   
over time but it was it was opportunity to you know have this project and have some   
1:13:24   
project leadership and develop ideas and do u really interesting research. to have had like really nice um journal   
1:13:31   
clubs and meeting and meetings over time. So the opportunity to develop your   
1:13:36   
ideas and develop as as a researcher and develop as a a scholar or whatever you want to do um   
1:13:43   
uh that's been very good for me over the years and I've since made um other organizations and done things that are   
1:13:49   
spin-offs and and downstream of that. Um, so I'm someone who has a lot of that kind of history and um has come up   
1:13:56   
through some of orthogonal lab that way. Um, I'm currently doing things with a group   
1:14:04   
that I've basically I founded called Joe and another group that's doing some   
1:14:09   
business and consulting and strategic stuff as well. Um but for now I will be a another with SAR   
1:14:19   
and others uh a mentor for Google summar code and also if you have questions   
1:14:24   
about um some aspects of how orthogonal   
1:14:30   
has worked or some context over the years of of certain things or certain projects I might be able to um speak to   
1:14:37   
that u so when I'm talking about things like frontier map um almost no one in this room will really know what that's   
1:14:44   
about at at much level of depth and that's fine. You don't need to know that   
1:14:49   
uh that that's why I kind of brought it up a little bit um I don't know. um   
1:14:57   
with the caution or or sort of the way that I did. Um so that's sort of some   
1:15:03   
some some projects from that uh that an area that area of things sort of the the   
1:15:11   
I'm calling it future future center is sort of the um   
1:15:17   
home for most of those things. In a little bit more concrete terms, um some   
1:15:22   
updates from other related groups, uh plot twisters is still kicking um and   
1:15:28   
has done a lot over the last few months. Uh I was also attended a um a friend and   
1:15:37   
colleague of mine who's doing something kind of similar. If Plot versus is sort of designed at around sort of creating   
1:15:42   
an online game world um that has deal with sort of um   
1:15:49   
self self-awareness or sort of not not a therapy chatbot but sort of um   
1:15:58   
uh moving towards interactions and games and opportunities for a user to develop   
1:16:05   
certain like intrapersonal skills or maybe things emotional literacy adjacent   
1:16:11   
or so kind of a basic uh curriculum around certain   
1:16:16   
intrapersonal and interpersonal uh you know skills let's say   
1:16:23   
I attended someone uh someone's um thesis defense yesterday   
1:16:30   
um and they are doing her name is Mona and she's actually done a lot of things in in sort of the technology and ethics   
1:16:36   
space uh Mona Hamdi that she was presenting at um   
1:16:44   
SCAD uh for her master's work in   
1:16:50   
um not sure what to call it quite um   
1:16:56   
I can't pull up the link very easily but essentially she's she's working with uh much more applied things in terms of uh   
1:17:04   
you know actually it's about grieving or loss and and making similar kind of   
1:17:09   
component to dealing with that or having someone reflect on that and then also   
1:17:16   
building a lot of um building a lot of um agentic uh bu she   
1:17:24   
made her own card game of sorts which is part of something in plot twisters but then she's using a card game slash   
1:17:31   
an agentic operation for that to facilitate uh having some of that   
1:17:36   
experience of end of life pallet of care things that are um   
1:17:43   
help helping streamline that. So, it's very interesting to see a different application of both um   
1:17:50   
games or cards as as prompts to get kind of reflection or certain kind of interaction   
1:17:57   
um which originally for Mona and also for Plutters was an actual like physical card game and then taking that   
1:18:04   
interaction that's sort of iterative and somehow internally reflective   
1:18:09   
um and even also community oriented and and putting it into um a potential   
1:18:15   
technical application. So there's some interesting like back in the cognition futures days we talked about   
1:18:21   
phenomenology we talked about um kind of getting into that second person   
1:18:27   
or like not just first person subjective but the intermediary um   
1:18:33   
uh like one internal to external or internal to shared. So it's from that   
1:18:39   
perspective of like phenomenology cognition futures type stuff. Um it's very interesting to see these sort of   
1:18:48   
uh dip dips into that space. Um and I'll I'll leave it at that. uh   
1:18:54   
there's a lot of there's a lot of things that are hap happening and um   
1:19:00   
there's some substack posts that are sort of drafted or should be written from the pers plot twist's perspective   
1:19:06   
specifically. So um that will come   
1:19:12   
and then finally um uh   
1:19:17   
oh the Princeton Envision stuff too. Um I I am I will be posting a video from   
1:19:24   
that. I wasn't able to attend in person. Uh but I I will be posting a video on um   
1:19:30   
essentially the original panel that I was attending was uh AI and education and I'll have a   
1:19:37   
commentary on AI and education. The rest of the panelists were focus mostly focused on like K through2 education and   
1:19:44   
I have a little bit more experience in you know um this this area the the arena   
1:19:50   
of sort of undergraduate and and higher education type things um or you know   
1:19:56   
college and graduate school and professional or whatnot. Um   
1:20:01   
so that's cool that will come also. And then finally, uh, there's Nickwick, which will be in   
1:20:08   
Albany this year, New York Celebration Women in Computing. That's about to happen. That's almost already here. It's   
1:20:14   
hard to believe it's basically a month away now. Um, I'll post about that in Slack. Um,   
1:20:22   
I'll drop the link in the chat just so people can understand if they want to. This is this is this is stuff that most   
1:20:29   
people probably won't won't know about or be involved in, but I'm just mentioning that it's on the radar of things like based. And then finally, the   
1:20:36   
probably the most um uh   
1:20:41   
this is also condition futures related, which is sort of ironic because I wasn't um   
1:20:49   
uh going to do much with with that this year. But um   
1:20:55   
um very briefly, I'll just go through this. Um   
1:21:01   
embodied intelligence. Um, I wasn't even going I wasn't even sure if I was going to submit to this. Um, but I am. Um,   
1:21:11   
and I I don't know how much I dropped some of this on on you, Bradley, or not,   
1:21:17   
but essentially, let me see if I can pull up what I'm going for. Um, I came   
1:21:22   
about my submission totally through working on a bunch of other stuff. Um,   
1:21:28   
but I'm going to submit it probably today. And um where did it go?   
1:21:36   
Um that's so strange to me. Okay. All   
1:21:41   
right. That's that's the second one. Here we go. So my lofty title is going   
1:21:47   
to be navigation, affordance, perception, and the ethics of comprehension. Common currencies between   
1:21:54   
spatial and epistemic intelligence. Uh which is very very very lofty. But um   
1:22:01   
some of the some of the key things that they're asking for this year are the common currencies   
1:22:08   
and also ethics. And I thought why not try to take a swing at putting those   
1:22:14   
together somehow. And that's what my I'm going to you know it's a low barrier to   
1:22:20   
entry but it's a small talk here but I think I'll get some very interesting feedback from from from the group. So,   
1:22:27   
more about that in um in the class in in   
1:22:32   
Slack. Um I think this will be a very interesting um   
1:22:38   
their master class stuff this year actually looks really interesting. I don't know how to best interact with   
1:22:43   
that quite yet or or like to sign up for that specifically, but um good for the embodied   
1:22:49   
intelligence conference. Um the they kind of stepped it up a little bit from   
1:22:55   
the last few years and heard of what they seem to be offering. So that's cool. Um there's a few other things, but   
1:23:02   
I I'll I'll kind of pause there. I know more folks have joined and and um I'm   
1:23:07   
sure you have some things to say, Bradley, so any any questions or comments I can um speak to?   
1:23:17   
Um yeah, that's great. Uh thank you, Jesse. Um, actually we were just talking   
1:23:22   
about the embodied intelligence conference in the intro. So, uh, I don't know if you had the if you could bring   
1:23:29   
the agenda back up. It's kind of interesting. Yeah.   
1:23:34   
Let me try this again. Yeah. I think this works.   
1:23:41   
Yeah. So this is the and so they have these master classes   
1:23:46   
that are like I guess people can give five minute presentations during the master class   
1:23:52   
then they also have the master class itself. So the master classes if you go down you'll see that there are different   
1:23:58   
ones. Um there's one on reservoir computing   
1:24:04   
there's one on embodied robotics. Here's one. It's like a conversation   
1:24:10   
between Mike Leven and um uh the person who the main person who   
1:24:15   
runs this conference. So let's see if I can find them. Uh Fu uh Fuima   
1:24:24   
uh who's you know talking with um Michael Lean on   
1:24:29   
like I guess on embodiment and things like that. And they also have a number of plenary talks, panel talks.   
1:24:39   
Yeah, this is interesting. Trying to find the list of the master classes, but it's   
1:24:44   
okay. Thank you, Vy. See you later.   
1:24:52   
Yeah, this is Well, that's the registration. In any case, I don't Yeah, it's uh where   
1:25:00   
it is. But anyways, yeah, this is um if you could post this link in the chat for   
1:25:06   
this this uh program, people might want to take a look at it. Um yeah.   
1:25:14   
Yeah.   
1:25:21   
Um let's see. No, I don't like Are you Did you mention   
1:25:32   
that you're submitting to this properly? Yes. Or are you not? I thought so.   
1:25:37   
I'm submitting a breakout session in a in a master class session.   
1:25:42   
Okay. And are you are you for master class? Are is that where you're attending it yourself or is that   
1:25:50   
pres presentation as far as I'm aware? Okay. Yeah. Okay. Cool. Um I know I've   
1:25:57   
seen some things, but I haven't. Especially those last week and a half, I've not seen everything at all.   
1:26:03   
Yeah. Um so, uh let me know if I can   
1:26:10   
do anything with that. Yeah. But I I will uh I know I know it's   
1:26:17   
a very busy time for for everything else, but um I will attempt to send you   
1:26:22   
my uh my what I'm what I'm submitting just so you can see it there. I I I it's   
1:26:31   
really funny because I didn't I hadn't um I really wasn't going to   
1:26:38   
submit to this, but then something came up was like, okay, like this is Um   
1:26:46   
this is something that I want to try to because there's sort of a   
1:26:53   
you know um as as as folks may uh be aware of um   
1:27:02   
you know sometimes you have to start   
1:27:07   
Here we go. Uh yeah, sometimes you have to start   
1:27:13   
your idea out at a certain level even though you know where you want to go with it.   
1:27:20   
Right. So, um there we go. I I what what what I' what   
1:27:26   
what I'd like to do and there's something that I can't quite talk about yet um but I'm going to allude to is um   
1:27:36   
I the the the some of the meat of the   
1:27:42   
presentation is sort of uh or you know um   
1:27:49   
uh the some of the things what does the query really want to get That is sort of   
1:27:55   
these things and a key a key theme and topic for me and many friends is sort of you know   
1:28:02   
navigation and affordance and sort of the selection navigation affordance and   
1:28:08   
selecting alternatives or make being selection the selection process itself   
1:28:15   
um and and and like those you know I'm looking at that from the angle of common   
1:28:20   
currencies and in this case um you know the ethics because I find I   
1:28:26   
find this to be kind of a I'm really curious and I don't even know I don't even really even know what um what are   
1:28:33   
the ethical questions which arise from AI or from AI excuse me   
1:28:40   
um and and I I feel like that's such a I   
1:28:45   
know there are some things in that space perhaps but I feel like that's such a um   
1:28:52   
important, but also uh you could take that in so many   
1:28:58   
different ways in terms of of um   
1:29:03   
you know uh in so many different ways. And so I   
1:29:09   
I'm finding myself kind of like um Oh. Oh, yeah. I forgot this was a a   
1:29:17   
massive class proper. Yeah. Between those two as well. Um   
1:29:24   
uh but I think I think an interesting lens going forward and this this kind of   
1:29:30   
ties into um this ties into um   
1:29:38   
also a um apologies for some folks looking at the Jerro website uh which   
1:29:45   
which is it is still up and even I think Sara asked something about old JPro the   
1:29:50   
old um um uh   
1:29:56   
something uh and this is one of the latest   
1:30:01   
versions of Google Summer code things is actually still here in one of the old parts but the website's basically going   
1:30:08   
through a bit of an an update here and that's that's the job pro side as far as delete this site that's I'll deal with   
1:30:14   
that address that in Slack because I don't I don't I don't quite know the answer to the specific question but Um,   
1:30:21   
so put a pin in that for later. Um, part of where I'm going with the ethics   
1:30:26   
of it is, um, something we've been talking about in the digest group,   
1:30:33   
um, which is sort of about narrativity, emerging technologies, and   
1:30:39   
agency, let's say. Um, one of the things that we're kind of do,   
1:30:45   
well, I guess I can loosely say we're doing in the group is trying to attend a lot of a   
1:30:52   
lot of these advancing humans and a AHA advancing humans with AI group at MIT.   
1:30:58   
Um, they host very nicely bi-weekly lecture series. Um they've they r they   
1:31:04   
range from uh really interesting things to uh   
1:31:10   
you know uh like Google vendors selling and talking about how cool their AI   
1:31:17   
curriculum is. Um to some in-house like last week was basically an in-house one   
1:31:23   
of their in-house people just kind of saying all the stuff they're working on which is cool. There's quite a range of things, but I I really like I'm a big   
1:31:30   
fan of what they're doing because getting certain community development in the space is really important and and   
1:31:36   
having people uh the chats and the participants have grown in in the last few months and I'm I'm really trying to   
1:31:43   
encourage that to be you know the forum but doing a hard mode hackathon right now. They're doing a lot of really stuff   
1:31:50   
that I really support. Um so, you know, check out the AHA group there. Um but um   
1:31:58   
where I'm going with this all the way back back to the master classes and whatnot is um   
1:32:05   
um I guess the ethical component is I think there's a very particular interesting   
1:32:12   
where I'm going with all this about the ethics of and embodiment and whatnot is I think there's some very interesting   
1:32:19   
principles that are going to carry from sure um and ethical questions from I but   
1:32:26   
also relationship to um digital narratives and emerging story   
1:32:32   
technologies more so narratives and agency more so how is technology influencing   
1:32:40   
perhaps even our embodiment and ethical questions about being able to select or perceive choices um in in that light. So   
1:32:49   
I will I will um I will stop with that. I'm sure said plenty for now. Did you   
1:32:55   
want me to show any more about the conference, Bradley, or I think that's it for now. Um, just I'm   
1:33:02   
glad that you kind of brought that up though because um well, we'll talk more about it later.   
1:33:09   
And um there there's a couple opportunities, one in particular that I I'll reach out   
1:33:15   
to you about probably in the next week that are let's say downstream of um the   
1:33:23   
embodied intelligence conference that also fit kind of this broader um   
1:33:29   
embodied intelligence and then some of the things I've alluded to that I' I'd like your opinions on. So, I will   
1:33:34   
probably message you about that um in Slack. Yeah.   
1:33:41   
Yeah, it sounds good. Thank you. Yeah. All right. Um   
1:33:50   
so, thank you. Uh that was great. It looks like we have some people here. Uh some of our other repository   
1:33:57   
contributors. We have Retach and Ria and Kavia. So would you like to introduce   
1:34:03   
yourselves? You can unmute yourself and   
1:34:09   
um uh just in the meanwhile I'll also I realized I did not introduce myself so   
1:34:16   
I'll just give a short introduction. Uh I'm Sara Bastawala. I uh joined Orurel   
1:34:23   
when I started contributing to the uh sustainability project in 2024   
1:34:30   
and I mentored Vidhi uh when she took forward the sustainability project via   
1:34:38   
reinforcement learning last year and I am also a potential mentor for any   
1:34:44   
projects we have for the sustainability this year. So yeah, I I   
1:34:53   
Yeah. Uh all the new contri contributors as Bradley suggested, it would be great   
1:34:58   
if you can just unmute and give a short introduction. Yeah. Hi. Can you listen?   
1:35:04   
Yeah. Yeah. So I had actually attended the last meet as well on Saturday, but uh it   
1:35:14   
was an informal meeting. So I'll again reintroduce myself. So I'm Kav Zala. I'm   
1:35:21   
a second year computer science undergraduate from Viji India. So I have   
1:35:27   
actually gone through both the projects of war that is the depoor and   
1:35:33   
sustainability and I have also made contributions to both of them and   
1:35:40   
I have a background experience in Asian based modeling particularly in MESA   
1:35:45   
where I have uh contributed some examples particularly in the lead based   
1:35:51   
architecture and I was also researching about different uh other behavioral   
1:35:57   
architectures for me. I also have some other background   
1:36:03   
experiences and AI agents racks.   
1:36:09   
So yeah, thank you. Yeah. Um   
1:36:15   
okay, go ahead, Ria. Hi, my name is   
1:36:22   
from and I've been   
1:36:32   
and I'm   
1:36:40   
uh retach are you there? I'm finally a student of computer   
1:36:48   
science engineering. I was solving the issues by the oral group related to open source   
1:36:54   
sustainability using I had solved some issues like I and also created some PR   
1:37:02   
and uh my basically my experience is related to this was only happy to contribute.   
1:37:12   
Okay, thank you. Yeah. Hi, welcome Resh. Thank you. Uh   
1:37:18   
I've also added some code reviews for your PR. So, just go through this.   
1:37:23   
Thank you. Sure. Okay. I'm going to go through some readings now. I want to see um well,   
1:37:30   
we'll go through like two readings and we'll see what they uh foster. So, this   
1:37:36   
is a paper um and this is something that we've talked about in the group. um kind   
1:37:41   
of going way back to the things we were doing when well when we started doing   
1:37:48   
neuromatch and they you know had talks from different people and they had Steven   
1:37:54   
Gberg so Steven Gberg is known for adaptive resonance theory so what he's doing in   
1:38:00   
this paper here will be important in the formation of adaptive resonance theory   
1:38:06   
and as you can see this is an unsupervised learning model that consists of a comparison field and a   
1:38:12   
recognition field composed of neurons, a vigilance parameter, a threshold of rec   
1:38:18   
recognition and a reset module. So it is basically taking the biology of the   
1:38:23   
visual system and the attentional system and merging it into this sort of neural network type structure. So he's   
1:38:31   
computationalizing a lot of this in a connectionist structure, what we would   
1:38:36   
call connectionism, but would later figure prominently in the development of   
1:38:41   
neural networks. I always like to look back in time in terms of AI and see what   
1:38:47   
people were doing way back when because I think it's in informative and instructive for what can be what's   
1:38:54   
possible and kind of the roots of what we are doing now. So   
1:39:00   
this is uh Steven Gber from 1976.   
1:39:08   
Yeah. Yeah. Johan. Yeah. I remember Johan John talking about and that was his advisor at Boston   
1:39:15   
or Yes. And uh Johan for those   
1:39:21   
Johan John is somewhat one of my uh I guess I could say academic heroes. I really like what he's he did and uh   
1:39:28   
Johan has a kid now so he's a little bit more focused on that than hosting intellectually uh stimulating uh reading   
1:39:36   
groups and discussion groups around like material. Uh I think he does like neurologos versus his blog or I don't   
1:39:43   
know substack now but you have a lot of great com I'm reminiscing about the times when he   
1:39:50   
would host a lot of really good discussions and now that I'm in Boston here I feel legit like he's he's kind of   
1:39:57   
in a different stage of his life so I'm not we're not like hanging out and talking about this stuff but um it's   
1:40:03   
nice I'm imagining him time again   
1:40:09   
We can go through the paper. Yeah. So this is uh on the development of   
1:40:15   
feature detectors in the visual cortex with applications to learning and reaction diffusion systems. So it's   
1:40:22   
worth thinking about the history of AI where there are things that were going on very early that were   
1:40:30   
the attempt was to mimic biological intelligence however that is. So um if   
1:40:37   
you go back to McCulla and Pitts they were trying to build a biohysical model   
1:40:42   
of neurons and that's actually kind of what they proposed in their original papers and so that was something that   
1:40:49   
was the basis for the perceptron which came later and the perceptron is the   
1:40:55   
idea that you have this machine that does perception and it's it's always   
1:41:00   
this metaphor followed up by some abstraction of the of the biological system. And of course,   
1:41:07   
we lose uh in that in that abstraction, we lose detail and we lose the things   
1:41:13   
that you know maybe make that thing quote unquote biological. We lose the complexity   
1:41:19   
to do things that are computationally tractable. So we want to model say for   
1:41:24   
example uh a simple perceptual system or we want to model some neurons and their   
1:41:32   
connections or we want to model uh feature detection and um surround   
1:41:38   
inhibition uh things like that. we, you know, use   
1:41:44   
some sort of computational abstraction and we lose detail, but we   
1:41:49   
keep the metaphor and say this is learning because it actually does learn things. it has this sort of loose   
1:41:56   
connection with biology and it's worth thinking about because we do this again and again um in the   
1:42:02   
history of um in the history of AI and   
1:42:08   
not to give a preview of what I'm going to talk about at embodied intelligence but this is one thing that like we've   
1:42:14   
never really resolved from the early years of AI it's kind of like this thing that stuck   
1:42:20   
around with us and the question is will we ever kind get past that and maybe to   
1:42:27   
actual sort of biofysical machines and the answer is you know people proposed   
1:42:33   
that actually and it never really went anywhere. We might be able to get there with things like organoids like we've   
1:42:40   
talked about but still it's maybe far off and maybe will never happen. So   
1:42:47   
this is actually a paper that um is uh you know kind of the basis for a lot   
1:42:55   
of the stuff he would do with neural networks later. So that's just giving some context here. So the the abstract   
1:43:02   
reads developmental mechanisms for tuning of visual cortex. So his interest actually is in development not in neural   
1:43:10   
networks in biological development. and he's interested in the the development of the brain specifically.   
1:43:17   
Um and so this is where we have the tuning of visual cortex and this is of   
1:43:23   
course where in development um like if we're looking at the mamalian   
1:43:28   
brain we have a visual system that's starting to form. We have eyes that are   
1:43:33   
opening up to the world taking in light and it's wired to this uh you know set   
1:43:40   
of cortical structures that need to be shaped by those stimuli. And of course   
1:43:46   
we can look at the neuroscience literature to see what happens when you have uh blind mammals that are you know   
1:43:54   
we have blind mammals what they'll do is in an experiment they will nucleate the embryo they'll take out the eyes and   
1:44:01   
then they'll just kind of let it's like a rat or something um and then they'll let it live um and you know into   
1:44:08   
development and then look at the brain structures and they're very different from the brain structures of animals   
1:44:15   
that develop a a visual system and actually experience perception, visual   
1:44:21   
perception. So, you know, this is something that is interesting from a learning perspective   
1:44:28   
because it suggests that while there are some things that are innate, there's a lot of stuff that's acquired from the   
1:44:34   
environment, a lot of stuff that's shaped by learning. So you know we're he's talking about   
1:44:39   
this tuning of visual cortex where visual cortex the connectivity and the   
1:44:44   
sensitivity of the cells and the uh uh regions are tuned by uh environmental   
1:44:52   
mechanisms that are experienced in development. And so he's talking about this tuning   
1:44:59   
this adaptation and that it's actually derived from adult learning mechanisms.   
1:45:04   
So this is all defined as an adaptational property of shunting on   
1:45:09   
center off surround networks that prevents saturation of parallel processed patterns at a high input   
1:45:16   
intensities. a contrast enhancement in short-term memory mechanism and plastic synaptic   
1:45:23   
strengths that compute a time average of presinaptic signals and postsaptic   
1:45:29   
activities and multiplicatively gate signals. The mechanisms can generate fields of   
1:45:35   
feature detectors which are line or picture detectors. So if you're familiar with attention mechanisms, you know that   
1:45:42   
that people focus on this very thing where you have this feature detection and you focus on the features and you   
1:45:50   
ignore other things in the image. This is kind of where this comes from and   
1:45:55   
actually this is where biological attention comes from is this idea that you know you're doing early feature   
1:46:01   
detection in the visual system and that's sort of setting up your ability to attend to certain things in a scene   
1:46:08   
versus not attend to certain things in a scene. A developing hierarchy of such fields   
1:46:14   
can be synthesized in which successive critical developmental periods are triggered as a dynamic equilibrium.   
1:46:21   
as a dynamic equilibrium is established between short-term memory and long-term memory at each stage. So he gets into   
1:46:27   
this uh develop critical periods work this critical developmental periods work   
1:46:33   
and kind of it it kind of gives you this um sort of way of approaching   
1:46:39   
development and way of approaching developmental sensitivities and developmental tuning. So uh critical   
1:46:45   
periods are these short windows in development where a lot of the sort of   
1:46:50   
the most important things are acquired. So a lot of times in development we have structures that   
1:46:57   
start to form and they exhibit plasticity at a certain point in time like maybe a couple days of development   
1:47:04   
and if things don't happen during that couple of days of development they won't   
1:47:10   
ever happen. So you can have uh you know no ex no exposure to the   
1:47:16   
environment over those several days and it can result in long-term deficits to   
1:47:22   
the organism or you can have enhanced enriched uh experience during those few   
1:47:28   
days and it can result in a positive thing for the organism. And you can use   
1:47:33   
these uh these critical periods to sort of look at how   
1:47:40   
uh you know how contingent development is. In other words, if something happens   
1:47:45   
during the critical period, it's acquired. If it doesn't, it's not acquired and that sets up the sort of   
1:47:50   
the the the complexity of the brain afterwards. So it's a really interesting   
1:47:56   
uh tool to use to look at um you know artificial intelligence.   
1:48:03   
Uh then shunting adaptation can account for some data on spatial frequency adaptation. Shunting network properties   
1:48:10   
resemble properties of certain reaction diffusion systems that have been used to model developmental data in various   
1:48:16   
species such as hydra zenapus retina slime molds and others. So this is where   
1:48:23   
they're looking at these um they're really looking at reaction diffusion   
1:48:29   
systems in development and the where they're looking at reaction diffusion   
1:48:34   
systems and they're looking at how those operate for the dynamics and they're   
1:48:40   
using it to model developmental uh data in these different systems uh   
1:48:46   
where they're looking at um adaptation and perception. So reaction   
1:48:52   
diffusion systems are systems where you have maybe like a bunch of molecules in   
1:48:58   
a chamber and you're looking at how they respond like different chemicals respond   
1:49:05   
to pure diffusion processes. That means where they expand outward from a central   
1:49:11   
source. So a lot of times you'll have chemical systems where you have diffusion of a of a chemical signal or a   
1:49:18   
chemical set of molecules from a source. And if you have a bunch of these   
1:49:24   
operating in an environment, those sources will um sort of have this area   
1:49:31   
of influence or this gradient that expands outward and then those gradients   
1:49:36   
intersect and start to form boundaries. So this is actually a nice system for   
1:49:42   
looking at pattern recognition because you can model reaction diffusion as a system of patterns that form from   
1:49:50   
sort of randomness or from you know this sort of self-organizational property.   
1:49:55   
And of course back then the language wasn't quite the same as what we're using later. So this is we use reaction   
1:50:02   
diffusion now but like you know thinking about this sort of um these aspects of cognition and these aspects of   
1:50:09   
artificial intelligence weren't the terminology wasn't there yet. So   
1:50:15   
um so for example positional information due to regulation and reaction diffusion   
1:50:20   
systems is analogous to constancies due to network adaptation. firing of a   
1:50:26   
developmental gradient is analogous to contrast enhancement and maintenance of a pattern in morphagens is analogous to   
1:50:33   
short-term memory. So if you're not familiar with developmental biology,   
1:50:39   
this is a lot of jargon, but what it basically means is he's taking   
1:50:44   
components of developmental systems uh and he's using this as an analogy for   
1:50:52   
um cognition. So you have this pattern that is um a   
1:50:57   
pattern of these molecules that's analogous to a store in short-term memory. There's a developmental gradient   
1:51:04   
that it or the firing of a developmental gradient is analogous to contrast   
1:51:10   
enhancement in the visual system. And then um this positional information   
1:51:15   
which is where cells know kind of where they need to be in a on an anatomical axis in uh embryo embryogenesis when an   
1:51:24   
embryo is forming and this is also shows up in reaction diffusion systems is analogous to these   
1:51:33   
uh network adaptation mechanisms. So very interesting stuff and he uh he you   
1:51:40   
know he cites a lot of this uh early computational neuroscience literature. Um so he says two recent theoretical   
1:51:48   
papers and remember this is in 1975 so 1973 1974 era.   
1:51:55   
Two recent theoretical papers discuss the development of specificity in primate visual cortex. Both papers use   
1:52:02   
analogous mechanisms that drive their results. One of these mechanisms which is plasticity of crossorrelational synapses   
1:52:10   
has been mathematically proved capable of learning arbitrary acts in a wide variety of circumstances.   
1:52:16   
The second mechanism which is on center off surround anatomy is believed to   
1:52:22   
exist in the adult sensory processing areas such as retina and neoortex. This   
1:52:27   
is in mammals. Um a third mechanism   
1:52:33   
attenuation of small signals in a recurrent network has been shown to be necessary to prevent amplification of   
1:52:39   
noisy networks capable of short-term memory. Then a fourth mechanism   
1:52:45   
conservation of total synaptic strength at each cell can be replaced as an adaptational property of on center off   
1:52:52   
surround networks undergoing shunting interactions. So this paper argues that   
1:52:58   
the formal mechanisms which have been suggested for the development of specificity are also mechanisms that are needed for   
1:53:04   
efficient learning in the mature organism. So this is where you know you   
1:53:10   
have this analogy between what's going on in development. What's going on in   
1:53:15   
terms of how development, you know, takes us from this undifferentiated set   
1:53:21   
of cells to organs and to structures and   
1:53:26   
other types of things that are highly asymmetrical and highly specialized   
1:53:32   
specificity to sort of the same mechanisms that are used in learning and efficient learning.   
1:53:38   
And so you're you know learning of course is the encoding of information the acquisition and retention of   
1:53:44   
information and the recall of information as memory. And learning of course is important in neural networks.   
1:53:51   
He's not talking about that so much here but you know this is something that is going to become   
1:53:58   
relevant later on when he starts to work with neural networks and um these other   
1:54:05   
things that he's going to be doing later. So um and so this is uh where he   
1:54:12   
cites Weisel and Hume where they demonstrate that abnormal early visual experiences can induce abnormal   
1:54:19   
development of afrant connections of visual cortex. In other words, if you don't have that early visual experience,   
1:54:26   
you don't have the circuitry for later um visual performance, visual perception   
1:54:34   
and then affects the rest of the organism's life. So that early experience sets the gain for later on in   
1:54:41   
in development and in adulthood. And so this is kind of what we see with   
1:54:46   
learning. If you don't acquire things in training, you can't make good predictions. and so forth.   
1:54:54   
Um, and then they kind of talk about these other types of analogies between   
1:54:59   
development and learning and how those things are related and looking really at   
1:55:06   
the structure of these different types of systems in biology and then   
1:55:11   
abstracting that to computation. not quite at computation yet in this   
1:55:17   
paper, but he's starting to do some of the stuff where um he's just do drawing   
1:55:23   
diagrams. This is reminiscent of what Britenberg was doing in his biocybernetics where he was drawing   
1:55:29   
diagrams of circuits and then that would later become sort of computationalized   
1:55:36   
as this sort of uh you know as you as you could build an artificial system with them.   
1:55:42   
Um and then you know this kind of goes through um   
1:55:49   
some of this other work. Um he talks of he gives a review of developmental network models. Um and so this is just   
1:55:57   
kind of going over some of these models. This is looking at cortex and the   
1:56:03   
orientation of cells in cortex. So one of the things that happens in   
1:56:08   
development in the visual cortex is the cells become tuned to stimuli. And so   
1:56:14   
this is where they're kind of looking at the I think the neurohysiology here   
1:56:20   
where they're looking at the tuning of these cells to orienting it when the   
1:56:25   
organism is orienting itself to a visual signal. And this is where they're   
1:56:30   
teaching the visual system through experience how to you know   
1:56:36   
acquire this sort of tuning. So you can see here the view onto cortex after 100   
1:56:42   
steps of learning. It's figure three where you see these patterns of orientation that are sort of forming   
1:56:47   
order as opposed to being completely random. If you had an organism without eyes, you would uh try to do a hundred   
1:56:55   
steps of learning or if it didn't have eyes during its critical period, but then it had the ability to acquire   
1:57:03   
visual stimuli. This array after 100 steps of learning   
1:57:08   
would be totally random. That's the idea. So these developmental mechanisms kind   
1:57:15   
of map to learning and how things are learned because a development has in in   
1:57:22   
organisms development is sort of a precursor to learning. B, it uses   
1:57:28   
similar uh cellular molecular mechanisms which isn't cited here but this is   
1:57:34   
something that we find out later um in in the 80s and 90s especially and then C   
1:57:41   
um we can use this um metaphor for kind of neural networks and AI but you know   
1:57:48   
this is something where we had mastered the learning or or gotten really good at the learning but not necessarily at the   
1:57:55   
development. So we have machines that can learn, but then development is still   
1:58:00   
this thing that's like we're trying to do and it's hard to kind of   
1:58:06   
bootstrap learning from like, you know, nothing. It's it's kind of like easy to   
1:58:11   
build a machine that learns like a neural network that acquires information and encodes it in these memory   
1:58:18   
structures, but it's hard to sort of get something to form sort of self-organize   
1:58:23   
into a memory. Um, and then you know, do you have do you you do you rely heavily   
1:58:29   
on innate features or do you rely heavily on environmental features?   
1:58:34   
That's where I think the problem is with um the sort of developmental AI is that   
1:58:40   
we don't have that mix in a in a way that's u that can give us good results.   
1:58:48   
So this is just kind of going through some of the visual perception work and um you know he talks about recurrent   
1:58:55   
networks and um contrast enhancement short-term memory and looking at   
1:59:01   
recurrent onset or off surround interactions and um other things like that. Then he   
1:59:07   
talks about developmental hierarchies and critical periods here. So another important property of the model is it   
1:59:13   
can be used to generate a hierarchy of selectively tuned networks. This is like   
1:59:18   
in visual cortices 17, 18 and 19 where there exists cells exhibiting ever more   
1:59:25   
selective response criteria. So this is a hierarchical property that follows   
1:59:30   
from the fact that the cortex in our model also adapts to its total activity as section five describes. Hence the   
1:59:38   
cortex can be used as the retina for a second stage in the hierarchy. Its outputs will be the inputs in the next   
1:59:44   
cortical structure and its axons also possess crossorrelational synapses.   
1:59:51   
A central problem for such a model is how are the critical periods of developmental plasticity and successive   
1:59:57   
anatomical levels regulated so that the coded meaning of outputs from one stage   
2:00:02   
to the next does not change from moment to moment. So in other words, how do you keep this plasticity? How do you lock in   
2:00:10   
the adaptive results of this plasticity? You know, if you have a a plasticity mechanism, things could just drift   
2:00:17   
continually and end up at a place that's not optimized or not even something that's learned. So you could just keep   
2:00:23   
adapting, changing constantly and never like lock in on the solution. And so   
2:00:28   
that's what he's talking about here. Why is it that biological systems lock in on that solution? and um not just kind of   
2:00:36   
change until a certain point and then stop and then you end up with something that actually doesn't learn anything.   
2:00:43   
So that and it goes through this whole idea of critical periods and and other   
2:00:48   
types of things and and this is something that is interesting because this is something he's talking about in 1975   
2:00:55   
and he is he later goes on to do stuff with neural networks and all these other   
2:01:01   
things and cognitive science and as far as I know this has never really been   
2:01:07   
definitively solved. So this is kind of a thing that you know you bring up and   
2:01:12   
then it's like a challenge and it's hard to kind of define how to implement this   
2:01:18   
computationally or computationalize it and then eventually we end up with he   
2:01:24   
did a lot of great work in his career but it's like you know we still have things that are outstanding from this.   
2:01:30   
So, it's really kind of unlocking this huge problem space that we um are still   
2:01:36   
working on today.   
2:01:43   
Okay, so that was um the Gberg paper. Okay, so this is uh yeah, DevAI hashtag   
2:01:51   
ever more selective response criterion section six. How are critical periods of development regulated? Yeah,   
2:01:58   
yeah, those are I'll have to go back. Um, could you could you list the the or   
2:02:04   
mention the title of the paper again because I or I want to look at that for   
2:02:10   
other things. Yeah, this is on the development of feature   
2:02:15   
detectors in the visual cortex with applications to learning and reaction   
2:02:21   
diffusion systems. All right. Thank you. And if you're like   
2:02:26   
I don't know what your library access is, but this is something this is a deep cut as they say. Yeah, it's a very early   
2:02:32   
Steven Grossman paper. Uh the reason I'm looking at this is again I'm not going to preview the stuff I'm doing for   
2:02:39   
embodied intelligence, but this is one of the papers I was using. Cool.   
2:02:44   
No, I appreciate that. Um, I haven't, it's funny for me because I I'm like I   
2:02:52   
was alluding a little bit of context how how use this will be for people   
2:02:59   
here, but but in lab live cont um   
2:03:05   
around whatever the augmentation lab summit was last year, which I think sort   
2:03:11   
of summertime or end of summer or September or something. um for August. I I kind of   
2:03:20   
from from that point until the last few months, Commissioner   
2:03:26   
Futures in particular kind of um I don't it didn't it it was on it was   
2:03:32   
on a different kind of a back burner and now it's like but I kept saying to Bradley on the side like you know   
2:03:38   
there's stuff happening here like even some stuff   
2:03:44   
but you know like Addy and the Echelopa crew and and Elon   
2:03:50   
with his LM stuff and uh Will Han with his he's doing a lot with like music or   
2:03:58   
um the nature of information different way a lot of cool stuff there but I was like   
2:04:03   
oh you know it's like cognition futures like I was really high in that a couple years ago and now off but now it's like   
2:04:09   
there's this this nice other resurgence of um   
2:04:15   
a relending of things and mixing of things. So, it's very cool to see this and I think I don't know um I guess is   
2:04:23   
is is the actual event proper like when is when is   
2:04:29   
the Oh, the date the date. Yeah. The intelligence body intelligence   
2:04:35   
conference is 18 19th and 20th I think. Yeah. Yeah. Um uh so we'll have another   
2:04:43   
meeting. So maybe maybe something we could do for next time is obviously Google Summer   
2:04:49   
priority. Um but maybe we can have a a little planned   
2:04:55   
session next time that that's like embodied intelligence focus or something.   
2:05:00   
Yeah, that would be good. Yeah. And I you know, you're not going to spoil your your stuff, but we could maybe have   
2:05:06   
something I'll try to prepare something with that in mind for for next week. That's what you want to do.   
2:05:12   
Yeah, I think so. Have like and you know, we could like have a parallel thing for our lab like we used to do. Um   
2:05:19   
we used to do like these kind of run like when people were doing a lot of virtual conferences have these parallel   
2:05:25   
sessions. Um, and so yeah, and and again, if you want to publish your talk   
2:05:32   
on the lab YouTube channel, I can put that up. Yeah.   
2:05:37   
Yeah. Sounds good.   
2:05:42   
Oh, wait. Is do you know like I I haven't thought about this. Are they do you know if this   
2:05:49   
year the talks are going to be live or pre-recorded? Um, I think live.   
2:05:56   
I think they're live, but then I remember a couple times I did pre-record or something like that. Um,   
2:06:01   
yeah. Yeah, I don't I think they're live. Yeah, like you go into the Zoom room.   
2:06:09   
All right, I'll I'll say more about that for sure. Yeah. Well, I didn't want to get to one   
2:06:15   
more paper and I won't spend a lot of time on this, but I thought it was really interesting.   
2:06:23   
Okay, this is actually a question from Cavia. Um, since developmental stages   
2:06:29   
are triggered by equilibrium from short-term and long-term memory, what happens if equilibrium is disturbed   
2:06:36   
by abnormal sensory and photochemical imbalance? Ah, so this is where we get   
2:06:41   
into disrupting um critical periods and people have done there's been a lot of   
2:06:48   
work in molecular biology in disrupting critical periods. So you   
2:06:54   
can open the window longer or shorten it up. Or you can do experiments in in   
2:06:59   
neuroanatomy where you can take out the eyes of like an embryionic rat and you   
2:07:05   
can experience the world as as a blind rat and then look at the brain, look at the   
2:07:12   
c visual cortex and that's where your developmental stage is disrupted in some way. And that's actually where   
2:07:19   
um and and of course short-term and long-term memory are affected there   
2:07:25   
because you're affecting the sensory inputs, you're affecting the ability to learn and that sort of   
2:07:32   
thing. You know, you have more or less exposure. So that's when you get this disruption   
2:07:38   
and you get a lot of uh dysfunctions. you know, you get sometimes if you don't   
2:07:44   
get enough experience in the critical period, you end up with uh you know,   
2:07:49   
impairments or deficits in in blind organisms. Sometimes those areas of   
2:07:55   
cortex go unused. They don't get wired. They become smaller. They become   
2:08:00   
innervated with connections from other senses. So if you remove vision you end   
2:08:06   
up with um inputs from the uh proprioceptive   
2:08:13   
system and the auditory system. So you can actually enhance your auditory learning by having no visual system and   
2:08:21   
that can be you know recruited for consolidating memory auditory memory   
2:08:27   
instead of visual memory. So there are a lot of things that can happen if you disrupt that equilibrium.   
2:08:33   
Um and then in artificial systems you could use that to um do a lot of   
2:08:39   
interesting things. I don't know you could enhance performance, you could degrade performance, you could uh do   
2:08:46   
that with something interesting in multival models there.   
2:08:52   
That's good. Yeah, it's good insight. Um so let me go to this other paper. So we talked about this idea in cognition   
2:09:00   
futures a couple years ago. came up a lot and I know um Hussein is kind of   
2:09:06   
interested in this and this was also something that we talked about with Amanda and in the cognition futures   
2:09:14   
group. This is a paper um where there's this thing called the   
2:09:19   
BAiki effect and it's where you present different   
2:09:24   
shapes. You you have like a shape that doesn't really have a name like it's an abstract   
2:09:30   
shape. It's made up, but complex geometric structure no one's really been able to categorize because they've   
2:09:38   
created this madeup thing. It's like a spiky little ball or something, you know, and people will give names to   
2:09:48   
those objects based on their sort of shape and their visual properties. So   
2:09:55   
boua is like something that's rounded and soft. And then Kiki is something   
2:10:00   
that's spiked, spiky and sharp. And this is a crossodal association like   
2:10:07   
we're talking about. So that means that if you see some object that has a   
2:10:12   
certain look to it, you make a certain noise that describes it and it sounds   
2:10:18   
like what it looks like. You could also describe different sounds   
2:10:23   
by their sharpness or softness. In the same way, like we'll describe sounds in   
2:10:29   
ways we'll have like shortcuts to naming things that are kind of we've never   
2:10:34   
heard it before. We describe it. It sounds like a and then you might say it's a kiki sound or a bouba sound or   
2:10:39   
something like that. And those aren't like langu those aren't words that we've used in language. I mean, they're not   
2:10:47   
formal descriptions, but they're names that we ascribe to something that doesn't really have a name, and we just   
2:10:53   
kind of describe it as well, it's an interesting uh cognitive um art um kind   
2:11:00   
of curiosity. And so, what's interesting is that people thought that this was something   
2:11:05   
humans did because we had language uh spoken, you know, um spoken language and   
2:11:13   
that was hallmark of human cognition. In this paper, what they're saying is that   
2:11:18   
naive baby chicks, in other words, baby chicks, you know, under in in a developmental stage acquiring   
2:11:25   
information do something similar. So, yeah, this is uh matching sounds to   
2:11:31   
shapes evidence of the Baba Kiki effect in naive baby chicks. And so the   
2:11:36   
abstract here is if you hear the non-words Kiki and Boba, you may be more   
2:11:41   
likely to associate them with a spiky and round object respectively rather than the opposite. So Kiki is spiky,   
2:11:48   
Boba is round. And it's just like kind of using attaching a sound to what a   
2:11:54   
shape might look like. Boba being round, Kiki being spiky.   
2:12:00   
uh you might I don't know you might have like a waveform in your mind when you look at the object and you might use that waveform to to form the sound or   
2:12:07   
something. This is a case of sound symbolism known as the bulbiki effect.   
2:12:13   
Studies on formlength infants suggest that this effect might constitute a predisposed perceptual mechanism. So   
2:12:19   
this is in humans where they've looked at infants that do this and they have this. So the idea is that it's some sort   
2:12:26   
of innate effect that is innate to our perception as humans and that it's   
2:12:32   
something that we do early in development but it is something that is also gives us like a tool to deal with   
2:12:39   
information we've never seen before. Um and then so however these studies   
2:12:44   
suffered from the impossibility of ruling out a fast experience-driven origin of the effect resulting from   
2:12:51   
infant speed of learning, their sensitivity to environmental regularities and the large number of sound symbolic   
2:12:58   
associations to which they are precociously exposed to when interacting with adults. In other words, it's very   
2:13:04   
hard to do these developmental experiments. Are the the the babies uh simply just copying what adults are   
2:13:11   
doing and what the adults are doing have been learned from somewhere else or are   
2:13:16   
they just kind of integrating information from the larger world and   
2:13:21   
then kind of in you know uh inferencing from that? We don't really know. It's hard to do these kind of developmental   
2:13:28   
experiments where you isolate something to an innate effect.   
2:13:34   
Um so that mean so to better describe its anttogyny and fill in this gap and   
2:13:40   
anttogyny just means its developmental course. We tested the bubakiki effect in   
2:13:45   
domesticated chicks and gowas gallas. So these are chickens. Uh being a precocial   
2:13:53   
species chicks can be tested on the very early days of life allowing for virtually total control of the   
2:13:59   
experience before the test. So this is where you know that they haven't been exposed to anything in the world.   
2:14:05   
Everything that they're doing is going to be somewhat at least mostly uh innate. And that's, you know, kind of   
2:14:11   
the idea in these kinds of experiments. Um 3-day old chicks, 42 of them first   
2:14:18   
learned to circumn a panel to obtain a food reward. Then they were presented with two identical panels, one depicting   
2:14:25   
a spiky shape and one depicting a round shape. And then they hear the the sound   
2:14:31   
of BBA or Kiki. All right. So they they hear the sound, they see the shape,   
2:14:36   
integrating that those two modalities. We recorded which panel chicks chose   
2:14:42   
with either sound. So they peck at the thing that they've chosen in a total of 24 trials.   
2:14:48   
Chicks prefer the panel with a spiky shape when hearing the kiki sound and   
2:14:54   
that with the round shape when hearing the bubba sound. So, we can assume that they're making the same kind of judgment   
2:15:00   
or or using the same kind of mechanism that human infants do.   
2:15:07   
Results from naive baby chicks hinted a predisposed mechanism for matching the two dimensions of shape and sound that   
2:15:14   
may be widespread across species. We talked about this with um there are a   
2:15:21   
lot of multimodal models of artificial intelligence, a lot of multimodal models where you're   
2:15:28   
training a model with two different modalities. Um and you know this is important in   
2:15:33   
large language models because large language models we're using language. We're building models of language. We   
2:15:38   
also have images that we can attach to those those u linguistic   
2:15:45   
tokens. We can attach labels to images and we can use we can use that as kind   
2:15:51   
of a a multimodal um learning system. So   
2:15:57   
it's it's important to kind of think about what is possible, what's learned   
2:16:02   
and maybe what we can hardcode into these models and what we maybe need to hardcode that can't necessarily be   
2:16:08   
learned from data directly. Okay, so this is just kind of goes over   
2:16:14   
this um history. This goes back to 1947 where they they would invent these   
2:16:19   
non-words that were kind of descriptions of a shape. You might look at the shape and look at the waveform of the shape   
2:16:26   
and then look at the waveform of a sound and make that connection. So maybe in the brains of these uh chicks or these   
2:16:33   
humans, they're making this uh assessment of the waveform of both. And   
2:16:39   
if it's similar then there's a crossmodal fusion there. So there's a lot of work on crossmodal uh attention   
2:16:46   
crossodal perception where there's this idea that percepts fuse together a for   
2:16:52   
vision for auditory stimula and when they're not fused together when you don't have the visual information and   
2:16:59   
the auditory information say the percept is weaker. So in other words, it's it's   
2:17:05   
better that you have both modalities because there's a stronger response in   
2:17:10   
different areas of the brain that enhance learning that enhance memory and   
2:17:16   
that enhance sort of recognition later. So this is kind of the the what they   
2:17:22   
they go through on this. And um so basically   
2:17:29   
they have made this quite quite an interesting um finding and you know   
2:17:36   
people originally thought this was something limited to humans and we find that this isn't necessarily the case. Um   
2:17:44   
yeah, this it might be a controversial um experiment. You know, you might argue   
2:17:50   
with the with the methodology. You might argue that they're two different things   
2:17:55   
that maybe they're just kind of responding to two there maybe two different mechanisms involved.   
2:18:01   
Um but you know, this is something that again it's it's interesting. So the   
2:18:07   
discussion talks about the how the present study tested baby naive domestic   
2:18:13   
chickens for an example of sound symbolism namely the bubakiki effect and   
2:18:18   
they want to understand the anttogenetic origin of this effect. In fact even if this is a strong and well attested   
2:18:25   
effect in our species in both adults and infants   
2:18:31   
there is still an active debate on how it originates. We report a spontaneous tendency to   
2:18:37   
match a brown and spiky shape to the bouba and kiki sons respectively than 3D old chicks. Our results fit into the   
2:18:44   
current debate suggesting that sound symbolism belongs to a set of predisposed associations   
2:18:50   
built into different species. Our data well support the existence of an early   
2:18:55   
available mechanism as we hatched the eggs in the lab where we exerted   
2:19:00   
virtually full control of the chick's experience overcoming one of the biggest limitations from studies on human   
2:19:07   
infants. Um even though our subjects had never experienced a sound symbolic matching   
2:19:12   
prior to test they still spontaneously associated the two dimensions of shape and sound. This indicates that this   
2:19:20   
scubaiki effect may take place in the earliest stages of life without the need of subject directly experiencing the   
2:19:26   
crossodal matching. So they don't experience crossodal matching before this that just happens.   
2:19:33   
Similar results were obtained for other instances of crossodal associations in the species such as visual spatial   
2:19:40   
visual tactile and pointing towards a predisposed general mechanism for crossodal associations. So crossodal   
2:19:47   
associations are maybe thought to be innate that you can build in those   
2:19:52   
associations or that they're sort of come as a natural feature selection mechanism.   
2:20:00   
So this is really interesting. Um so yeah I think I'll stop there on that   
2:20:06   
paper. Um yeah I thought that was interesting in light of some of the stuff we t talked about a while back in   
2:20:13   
cognition futures.   
2:20:18   
Yes. Um, if I could if I could uh more accurately represent what I would talk a   
2:20:24   
little bit about Elon Barric Holtz's work and the LM language stuff, there's some par there's something to be said   
2:20:31   
there that might might um I still don't I don't I don't fully   
2:20:37   
grasp his work yet, but I think it would be an interesting thing to bring into   
2:20:43   
that um discussion. So maybe some other time or if there's ever an overlap. We   
2:20:48   
talked a little bit about an overlap between like hypoal type stuff in the future. That might happen this year. I don't know. Um but   
2:20:56   
absolutely in terms of the I don't know uh on what was it   
2:21:01   
ontogenetic? Yes. Um meaning and and things like that. That's   
2:21:06   
that's still a key thing to think about. and also like an approach of it gets you know   
2:21:16   
in the interest of time I'll just I'll just very quickly say like that   
2:21:21   
the anttogenetic development part and then my my current interest on the um   
2:21:28   
let's say ethics which which I don't I'm cur you know I'm I'm interested in how   
2:21:33   
I'm going to deal with the ethics component but I think I think   
2:21:39   
in an applied sense um sort of selection, choice, agency um and how   
2:21:46   
those things affect um development as well is a very   
2:21:51   
interesting space to look at. So maybe we can talk more about that next time, but thank you for the paper uh today.   
2:21:59   
All right. And thanks everyone for showing up. Yeah. Yeah. maybe your first time here, but we encourage you to continue to show up and   
2:22:05   
interact in Slack and ask us questions, too. Yeah. Yeah. Thank you. Thank you   
2:22:11   
everyone for your contributions and your uh activities over the week and um see   
2:22:18   
everyone next week. Take care everyone. Thank you. Take care. Bye. Bad.   
   

