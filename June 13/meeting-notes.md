## Meeting Recording

[YouTube link](https://youtu.be/tc-P9TKcivY)

## Mastodon thread

[link](https://neuromatch.social/@OREL/116756297291812425)

## Feature Videos

[Population Level Biomedical Foundation Models](https://youtu.be/FbIXxRpRHvA)

[How Does Intelligence Develop?](https://youtu.be/qTJXh_C7BgU)

[Fallacy of the CogSci Hexagon](https://youtu.be/YQO2OvNUY48)

## NOTES
High accuracy under subject-disjoint cross-validation.

Foundation Model (FM) scope, frozen representation. Representations vs. subject-specific results. FMs build from 100s of subjects.

* novel classification pipeline -- need a set of datasets -- open-source, classical ML pipelines.

* PyTorch geometry-friendly.


Not a "scaled" effort in tech nor the medical imaging sense. 300K datasets for a foundation model. Better application of a general linear model.

* fine-tune to individuals, but not to over-focus on individuals (confounds within a dataset).

* Alljoined --> Enigma Foundation Model --> use case for neuroimaging.

Development a behavior of Intelligent Agents:

1) add juvenile stage (weak priors) vs. adult (strong priors).

2) "Beyond the Adult Mind" paper --> predictive processing (incremental updates). Babies need to construct from scratch. "Active and Epistemic Value".


Benchmarks and Foundation Models scope. Identity trap --> physically-grounded shortcut learning.

* Ethan Mollick -- cutting edge commentary.

* Randall Beer -- Dynamical Cognitive Science paper. Language of dynamical computation, language of CogSci --> can we reconcile.

* Boden's cognitive science demarcations --> 2007 pre-ML/DL.

* find old papers on developmental freedom and capacity.

* unified principles of agents --> world models, developmental freedom, developmental capacity.


Sybnthesis videos. CogSci beyond LLMs --> do some more interdisciplinary contextualizing work.

* multi-instant, multi-agent systems.

* Stochastic Parrots. Preprint offering a critique of impacts of models. Revisit the original paper (challenge to the community).

* DAIR --> what insights of n years hance are offered? Martiny critique of embodied cognition.

* Yann LeCun first-person approach.

* FDA timeline --> rate of change in world vs. what our institutions can support.

## TRANSCRIPT
0:06     
church.     
0:31     
Hello. How is everyone today?     
0:37     
Morning. Just um yeah, just heading into the lab. Doing good. Yeah.     
0:45     
Is that Cavia? Hello. Hi. Hi. How are you?     
0:52     
Great. Good. All right. So, why don't we get started?     
1:01     
So, this week we had actually three meetings uh that we did. Uh the first was uh DVO     
1:08     
worm that was on Monday. Then we did um our cog cognition futures meeting that     
1:14     
was on Wednesday and then we did a uh open source meeting on Friday.     
1:22     
So, it was a very busy week for meetings. Uh, we're also talking about,     
1:28     
uh, doing a lot of revamping of different resources. So, Jesse's working     
1:34     
on his website revamp for Joe and, you know, we're in the process.     
1:40     
We're kind of revisiting a lot of things. So, on Monday, we started with the DAWR     
1:46     
meeting. Um, Ashi Rajput and myself were there to begin. And then we got Baron     
1:52     
Mandal online and we started talking a little bit     
1:58     
about uh Baron's pull request to DVO graph. So this is where he added his     
2:06     
epic pre-processing and data set script. So this is the work he did for his weekly I think it was week two of the     
2:12     
coding period. So he has a number of different CSV files and a data loader     
2:18     
that he was working on. So he uploaded all of that and uh issued a poll request     
2:25     
and it was accepted. We reviewed that. Uh then we talked a     
2:31     
little bit about Barshine's post on uh his experience for coding period the     
2:37     
second coding period week of GOC. And he's keeping a blog where he's     
2:43     
keeping a weekly sort of report of his experiences. And then he's going to post to the lab     
2:50     
medium. Um, a couple of posts. Uh, he posts an introductory post. Uh, he's     
2:57     
going to post a midterm post and then a final report. So, that's all kind of     
3:04     
uh forthcoming. All right. So, yeah. And then he uh presented on all this and then I got     
3:13     
into this. I got actually into two papers uh for the rest of the meeting. The first paper was this uh ambitions     
3:20     
for theory in the physics of life. This is by William Bialik uh who's a a very     
3:27     
uh famous and accomplished uh or theoretical biologist, a biophysicist.     
3:35     
So he's doing a lot of things with biohysics and theory in biology. And so     
3:42     
um he this was from a summer school uh where he delivered a talk on     
3:49     
the role of theory in biology where you know in in a summer school you're typically you it's an intensive uh maybe     
3:58     
two or three week period where people get to do things in a wet lab and then they have to reflect on those things by     
4:06     
reading papers and of course this also had kind of a theoretical component. So,     
4:11     
how do you build theory from the experiments you're doing? And so, that's what this was about. And he really kind     
4:18     
of focused, reason I like this article is because he focused in on the complexity     
4:23     
of uh biology and that being the sort of the basis for theory. So, when you     
4:29     
observe something in the lab, you can develop a theory for it. You have to think about the complexity of that     
4:35     
thing. Uh and what is the what is the right level to pitch a theory. I mean     
4:41     
what what does it need to include? How inclusive does it need to be etc.     
4:48     
So we went through this article and spent a lot of time talking about different things in the article. um     
4:56     
talking about going from say an experiment to uh a conceptual model to maybe a set of     
5:03     
equations and then thinking about how your theory generalizes. So you might     
5:08     
develop a theory of morphogenesis that largely focuses on drosophila or you     
5:14     
might develop a theory of development that focuses on all different types of organisms and it's going to be     
5:22     
different. So this is uh one example where we have two components that we've     
5:29     
boiled our our experimental system down to and the question is does your theory include enough detail to be predictive.     
5:36     
Sometimes you don't know enough about your system to develop a predictive theory. Other times you have enough and     
5:44     
your theory is elegant. You know, you want your theory to be simple, but you don't want it to be too simple and you     
5:51     
want to capture complexity without really kind of getting lost in that complexity. Yeah. So, this is uh like an     
5:59     
example from gap genes in Drosophila and you know he gives an example of how you take things from a graph. So you have     
6:06     
experimental data, you take things from a graph and you build a a conceptual model and then you refine that model and     
6:14     
then that's the thing that predicts something and so you can build a predictive model out of that. Uh I think     
6:21     
there was also an interesting correspondence here between     
6:27     
the role of parameters in complexity theory and the role of parameters in     
6:33     
neural networks. And we talked about this a little bit, but something that     
6:38     
was interesting from this because you know we think about     
6:43     
sort of in machine learning and in deep learning especially that we use a large number of parameters to describe a     
6:49     
network. We can tune those parameters and get a predictive model. So what are we doing there? Well, we're kind of     
6:56     
building a theory. We're building a theory of of data or of the data that     
7:03     
we're analyzing. And so as we tune those parameters, we we describe it with a     
7:08     
large number of parameters. So in a sense, our theory is maybe, you know, is it overfitting or underfitting what     
7:15     
we're trying to understand. And so we can run into cases where our model     
7:21     
overfits the phenomena or a model underfits the phenomenon.     
7:26     
And the same holds true for theories. We could have theories that sort of overfit what we're trying to explain and some     
7:32     
that underf what we're trying to explain. So this is this is kind of a     
7:39     
I guess maybe the best way to put it is it's a correspondence between the two domains, but we don't really know why     
7:47     
you know what the actual connection is. So he also gives these different axioms     
7:54     
for reacting to complexity. So the first is give up life is really really is that complicated.     
8:01     
The second is we should study theories that remind us of the real thing not try for quantitative comparisons of theory     
8:08     
with experiments. Uh then three is the only real theory is     
8:15     
how things are related to one another. Three is we are interested in relatively     
8:20     
macroscopic behaviors which are usually more universal than microscopic mechanisms. And he brings up the     
8:28     
renormalization group. Number four is the fact that living systems function often quite well and     
8:35     
can be promoted to a principle that sex selects parameters or behaviors     
8:40     
circumventing details. This is sort of the tiein to deep learning.     
8:46     
Okay. Yeah. There was I think there was a little Okay, I stopped there. That was basically it. So he gave these six     
8:54     
points and we reflected on it a little bit. Okay. Then the next paper was this paper hyper agents. And this was kind of     
9:00     
uh sort of it was interesting that it was     
9:06     
uh you know was sort of tangential to the last paper but it actually did fit in somewhat with what we were talking     
9:12     
about because hyper agents are this sort of model of self-improvement of a     
9:19     
software agents and there's this link to what's going on in intelligent system living systems and     
9:27     
so it was interesting read this after the other paper because it kind of tied things together in a unique way. So, um,     
9:38     
basically what they're interested in is are these self-improving AI systems which aim to reduce reliance on human     
9:44     
engineering by learning to improve their own learning and problem solving processes.     
9:50     
So, this is what we call continual self-improvement. And uh we talked about     
9:56     
Sakana AI in this group last time and you know they're doing this sort of     
10:01     
thing where they're doing continual self-improvement and so this that is related to this     
10:08     
because I think some of the people were kind of you know sort of in collaboration with     
10:15     
Sakana AI. Not sure any of the people are actually from Sakana AI but there's     
10:20     
definitely that connection. And so one of the things we're interested in here is we're interested     
10:27     
in these metal level mechanisms that sort of limit or sort of put a cap on     
10:34     
how much systems can improve and their accuracy. So we don't want to     
10:39     
self-improve things too much and then not be accurate about them. Um and so we     
10:45     
but we also don't want to have to handcraft these metal level mechanisms.     
10:50     
And a lot of times when we, you know, say we want to build a metal alerting system, we'll often just handcode it and     
10:58     
that'll be that. But we actually want to have a system that's sort of self-organizing     
11:04     
and can evolve on its own, but also do so in a way that's accurate.     
11:10     
So uh to preface hyper agents they come up     
11:16     
with they mention the Darwin bodal machine which is uh this paper from 2025     
11:23     
was I think from the same author that demonstrates open-ended self-improvement which is achievable in coding. So     
11:31     
starting from a single coding agent, the Darwin gloal machine repeatedly generates and evaluates self-modified     
11:38     
varants forming a growing archive of stepping stones for future improvement.     
11:43     
Because both evaluation and self-modification are coding tasks, gains in coding ability can translate     
11:50     
into gains in self-improvement ability. So they use this coding task um     
11:57     
benchmark in the Darwin gold machine and then in this paper they introduce this     
12:03     
idea of hyper agents because they want to go beyond the coding domain to look     
12:08     
at transfer task transfer and other things.     
12:14     
So they find in with the hyper agents example that these agents are self-referential     
12:21     
integrated task agent and a meta agent. So they have two agents that are doing     
12:26     
things and this means they don't have to hardcode uh a meta a meta solution. They     
12:34     
also don't have to supervise it necessarily because it's a separate but related agent.     
12:40     
So this means that the meta level modification procedure is editable itself enabling metacognitive selfm     
12:48     
modification improving not only task solving behavior but also the mechanism that generates     
12:54     
future improvements and so they extend the Darwin gloal     
13:00     
machine method to create this Darwin gold machine hyper agents approach     
13:05     
and so this is where they're able to eliminate the assumption of domain specific specific alignment between task     
13:11     
performance and self-modification skill that could potentially support     
13:16     
self-acelerating progress on any computable task. And so they they actually go across     
13:24     
different uh skill domains. So they go beyond coding to go to paper review, robotics     
13:30     
reward design and math solution grading and look at performance there. So this     
13:37     
is an improvement on performance of other types of agents showing that you     
13:42     
know this approach is fruitful and so we went through the paper a     
13:49     
little bit and then that was the meeting. So we did have a little bit of metalarning in there in in vivo but I     
13:57     
think it does tie into theory building because you know for two reasons. One     
14:02     
one is that metacognition is really about building theories in in some cases     
14:08     
a theory of mind in other cases a theory of the world. And so you know this is     
14:13     
kind of a route to world models of course but you know it's it's interesting from the standpoint of     
14:20     
building theories of things. And then the other way is that it it kind of also     
14:27     
talks about that parameter problem. And so what are we actually how do we model     
14:33     
very large amounts of data? How do we do that effectively?     
14:38     
Okay. So then we had our open source meeting. So we did have our cogn uh cognition futures meeting Wednesday and     
14:45     
Jesse can talk a little bit about that um if you would like. Uh but I want to     
14:51     
talk go through the open source meeting which Jesse also pointed to in the slack. We had a very good discussion at     
14:57     
the end of that meeting that Jesse led that was really interesting. U but we'll     
15:02     
talk about that in a little bit. So the open source meeting was on Friday. Uh we     
15:08     
started by getting into the Hool's or I'm sorry Baran's update. Um and so he     
15:16     
talked a little bit about buzz work for this week, week three. Uh he talked about his uh you know last week he     
15:24     
issued a poll request that was a data loader and some files. This time he's     
15:29     
working on this attention model that he's trying to implement and some of the     
15:36     
components of that. So he work he's working on this attention uh edge     
15:41     
attention aggregation model uh where he's looking at incorporating attention     
15:48     
into a network itself. And then he has these two methods called dynamic     
15:53     
relation learning and dynamic node learning where this selects the nodes     
15:59     
that need to be updated for future graph topologies. And so he's working on     
16:05     
getting all this together and and running. He's going to issue a pull     
16:10     
request I think this weekend sometime. And so this is basically     
16:16     
uh his work for the week and it's very impressive. I think he did a lot of work uh in a very short period of time. So we     
16:23     
discussed a little bit about some of the things he had in his slides. Um gave a     
16:29     
you know had some questions. I gave a little bit of a critique of some of the things and it was pretty good. Then     
16:37     
Morgan had uh reported from where he was in in the city and he was running     
16:44     
errands and he had a little update there. Um     
16:49     
and then I I actually presented on um something that is sort of personally     
16:57     
relevant to our organization but also more relevant to developing open source     
17:03     
projects and that is the maintenance and evolution of uh repositories.     
17:10     
So if and I think we mentioned this in the meeting here, our organizational     
17:16     
repository was deleted through a malicious attack several weeks ago     
17:21     
and GitHub was able to restore it and to this day we don't really know what happened and uh but this just     
17:29     
underscores the need to to have like a really good plan for backing up     
17:36     
repositories in their state in their current state and in past states. And so     
17:42     
we talked about how you know you can fork things and you can have those forks out there so that work is sort of     
17:49     
somewhere else but still you know it you have to make sure the forks are updated.     
17:55     
A lot of times collaborators will fork things and not sync synchronize them. So     
18:01     
you know they're out of sync. Sometimes that's not such a big deal. Sometimes it's bad because you know you lose     
18:09     
things, you lose commits, all sorts of things, but you know also you have this problem     
18:16     
of backing up your actual repositories. I you know we kind of tend to think of     
18:21     
GitHub as sort of a ground truth or at least the home repositories being a ground truth and um     
18:30     
you know that's obviously cannot be true. You can have things that go away     
18:36     
and sometimes you're not aware of when they're going to go away. They just happen to go away. And so this is uh     
18:43     
speaks to the need to back things up on a regular basis and have a a resilience     
18:49     
plan because you know we have our resources and this doesn't this applies     
18:54     
to any kind of set of resources um that you have like drives and emails and     
19:00     
things like that where if something isn't working and you need to access how do you access that information you know     
19:07     
are there more is there more than one way to do that so that was something I I pointed out uh and then I talked about     
19:14     
some papers some articles that I had uh found on thinking about your repository     
19:22     
architecture strategy. So this was a nice blog post on this from Stefan Hiller uh and he talks about this     
19:29     
difference between a monolithic repository or a monor repo and a     
19:35     
multiple repository poly repo. And so you know the decision here is     
19:41     
like when you start an organization and you scale up or sometimes when you start     
19:46     
an organization you're developing a culture how do you manage your teams how do they interact with GitHub and how in     
19:55     
version control more generally sometimes it's about you know creating everything in one repo sometimes you use different     
20:02     
repos for different specialized tasks and so if you can do that then you you     
20:08     
have a strategy Y, but the problem is is that there pros and cons to each. And so that's what this article talks about.     
20:15     
Um, and so having a consistent strategy is good, but also having a strategy that fits your team is just as good too and     
20:22     
sometimes better. So, uh, we talked a little bit about monor repos and and     
20:27     
poly repos. And then we talked about the strategies, the advantages and disadvantages     
20:33     
across these. So there are advantages to the monor repo strategy there disadvantages and then the polyure repo     
20:41     
strategy there also advantages and disadvantages. Okay so that's and then of course um a     
20:48     
lot of this has to do with your institutional culture how you approach     
20:54     
key design decisions and things like that. Okay. And then there was this article um on this tool called Git     
21:02     
Evolve where they predict the evolution of GitHub repositories. So we we just went over the abstract on     
21:08     
this but basically talked about um the system that will predict the evolution     
21:13     
of GitHub repositories or how they evolve as organizations change and scale     
21:19     
up. And so you know this is again another thing where if you start a     
21:24     
repository you know and you start with a certain goal in mind and then as you work on it     
21:31     
because open source is very collaborative it can go in different directions     
21:37     
um it changes and sometimes you have to restructure the repo. Sometimes you have     
21:42     
to change the name of the organization or the repository.     
21:47     
Sometimes you move things in new repositories as they become as they become more or less relevant and so on     
21:54     
and so forth. So this is um this is what they were trying to do here. predict the evolution     
22:01     
of GitHub repositories. And uh yeah, I think this this is an     
22:07     
interesting paper, an interesting approach they propose, but I think it underscores this challenge of sort of,     
22:16     
you know, working through your uh sort of presence in version control and     
22:23     
constantly re-evaluating and revising that. So we have an example here where     
22:28     
you know we used to have our open source sustainability things and a repo called     
22:33     
GSOC and it was just parts of that repo that we had uh commits to and we had     
22:40     
everything in there. We had a bunch of other things, but that's where open- source sustainability lived. And then uh     
22:47     
recently in the within the last month and a half, I created an open-source     
22:52     
sustainability repo that is more better organized, better descriptive, and really focused     
23:00     
on the things that we're actually actively doing. So, that's one example     
23:07     
of how you can do that. And it's really just a matter of cloning the old repository,     
23:14     
creating a new repository with just the files you want to save, thinking about     
23:19     
the structure, and then putting it into practice. That's that's pretty much how I     
23:25     
approached it. Um, so that's how you do that. So then that was good. Then then     
23:31     
Jesse had a conversation here. Um, and it was about strategies for kind of     
23:38     
thinking about, you know, how you're valued in an organization. And we had this quote from     
23:44     
Ethan Mullik. He's a a AI person on LinkedIn.     
23:51     
Um, and he said, I said it a few months back and I think it is more important now than ever. If you're considering     
23:57     
taking a job offer, you will want to ask what your token budget will be. And that     
24:03     
sounds like, you know, that's that's a pretty practical thing to ask if you're like say getting an AI job. But more     
24:10     
generally, it's something that you should ask if you're, you know, what is     
24:15     
my role in the organization or how am I viewed in the organization or am I going     
24:22     
to be supported in the organization? And so that's just kind of a, you know,     
24:27     
thing. Sometimes a job looks really good, but you don't get support if the culture isn't there or the resources     
24:33     
aren't there. So, yeah. And Jesse says, "This is a great     
24:40     
question because it'll give you some insight into what their AI strategy is again." Yeah. Just how they approach     
24:47     
this larger enterprise that you're being hired for and how you fit into that.     
24:53     
So, that was something that uh sparked a lot of interest and uh yeah, and then     
25:00     
I'll leave it up Jesse to kind of flush that out if you would like. I I I really recommend following Ethan     
25:06     
Mollik. He's based in the Wharton Business School and writes he writes     
25:12     
well and writes often and he's sort of like if he wants someone who is very     
25:18     
cutting edge and pretty aware and pretty sober about     
25:23     
trying to just evaluate what different models and whatnot are doing. I think he's one of the better people to follow     
25:29     
at at that point of uh that at that vantage point. um and     
25:36     
he'll he'll kind of he's fairly generous in like hey this is a good question to     
25:42     
ask in this particular situation or whatever and in this case of the     
25:48     
conversation that we had and and wanted to recap it here the conversation that we had basically about um it was you     
25:55     
know the question was hey ask about tokens or whatnot but it led into a very nice discussion of how do you get at as     
26:01     
you said like some of the strategy of understanding what's going on in um an     
26:06     
in organization. It also split into areas about um related to conversations     
26:12     
I've had with various um interns or just just just     
26:18     
I mean not just young people but also people who are just graduating from Ivy     
26:23     
League schools uh people who are graduating from excellent schools or     
26:28     
coming off of different um career opportunities all having the same     
26:33     
question about what are we doing with a degree like should I pursue another degree what the cost and benefits of that in terms of resources and money and     
26:42     
time and and like direct direct benefits, indirect benefits. So, it's a very nice um very nice I'm going to go     
26:48     
back and try to uh like flip it out or repurpose it or or or even like just     
26:54     
say, okay, we had this and let's expand upon it here because I think it was one of the the     
27:00     
a very nice collection of what right now contemporarily     
27:06     
uh in a contemporary sense what what is going on like what are the questions     
27:11     
actually being asked right now and and I think we had a nice range of you know conversations about     
27:19     
uh perspectives on that conversation. So, um I can leave it at that for the     
27:25     
moment, but I'm happy if any if anybody here uh or or watched that or or has     
27:32     
heard it now and has additional questions, please ask them in the chat or please ask them in Slack or uh even     
27:38     
some people have specific things they don't, you know, in a DM or or you can     
27:43     
also say, "Hey, Jess or Bradley or Morgan or who or whoever talk it's great that uh     
27:51     
I'll hear, oh, I reached out I reached out to a past Google s venture. I reached out to someone else in the lab.     
27:57     
And I I really try to encourage that because I think that's something uh     
28:03     
an incredible skill to get used to doing and and the benefits are great. But please, you know, reach out to us um in     
28:12     
in whatever form is best for you. Get used to doing.     
28:20     
Let's see here. I'm gonna put these down. Sorry.     
28:27     
There we go. Yeah. Thank you, Jesse. Um, yeah. So,     
28:33     
uh, why don't you talk a little bit about the, um, the Cognition Futures     
28:39     
meeting from All right, great. Can you still hear me?     
28:44     
Yeah. All right. This should be a little bit better now. Um,     
28:52     
yeah, actually I'm I'm attempting to edit and and and     
28:58     
do some editing that on that right now. Um, and and I'm experimenting. It's so     
29:03     
interesting right now as as a as a meta commentary and everything. this I think     
29:09     
we spoke about this in the context of one of the meetings recently but just     
29:16     
the means by which you're like the AI handoff component of everything where you're you're kind of interacting with     
29:22     
these tools and when it gets interpreted or stopped it comes back to it um I'm     
29:27     
you know I'm attempting to sort out some of that myself even in terms of like editing the video posting the video like     
29:34     
how are we doing you know this different stuff with it so Um     
29:40     
it was it was it was a a nice meeting. Uh we basically covered     
29:47     
the beer paper and I'm amazing what the title of it was. Oh his take on the     
29:53     
dynamical cognitive science fun. He was basically having a response to was it Van Gelder? Uh like this paper from     
30:00     
1991. I'm sure you uh I don't have anything super easily to     
30:06     
show for it, but it was a very nice it was a nice uh meeting. We explored parts of it. I know Amanda kind of went     
30:12     
through it and mentioned sort of five of the the five points or the five claims     
30:18     
or five aspects of of the approach that uh beer was getting at.     
30:25     
It it basically at its core was kind of about um     
30:31     
he was the original paper 30 or so years ago or three decades of you know since     
30:38     
that it was part of that the beer's paper was part of an article series I think the Raha paper was part of the     
30:44     
same one from last week before uh but this article series around     
30:49     
you know 30 years on dynamical cognitive science or three decades of it um and     
30:55     
what's kind of happened since then or not. And that the paper in the past was was     
31:01     
uh Van Gelder kind of he was like, "Hey, you know, I'm going to I'm going to try     
31:06     
to arbitrarily reduce the space that we're talking about somewhat just so we can     
31:14     
have our disagreements and move on." Like he was making a very particular gesture so that it would lead to further     
31:20     
discussion and development. Um and Beer's paper essentially is a critique     
31:26     
of of some of that saying well you know maybe it's more like uh     
31:35     
dynamical dynamical a dynamical a language of dynamical systems and a     
31:41     
language of computation are two languages that you can use to describe what's what's happening. and he kind of     
31:48     
goes into well what about like behavior or mechanisms that are producing certain behavior. He he offers certain um     
31:54     
alternatives uh but he he he sort of is critiquing Van Gelder's original approach uh by     
32:02     
saying well maybe you maybe you're you're doing too much with this in some form and it's it's an interesting thing     
32:07     
to both look at the merits of the critique and     
32:14     
the whole the whole set of discussions on on a personal this isn't this isn't exactly what we talked about but thinking about it since then um on a     
32:21     
personal like on a personal note about things. Um there's this element of I     
32:27     
feel like I have even more sympathy for Van Gelder originally um in the sense that     
32:35     
I think it's a wonderful and beautiful and awkward lesson in in this space     
32:40     
where sometimes you have to at the level of a new     
32:48     
bridge or theory taking place you have to kind     
32:54     
framed something in a way where you're going to very obviously be wrong for a long time even like like there and     
33:01     
there's a use to doing that and not just and there's like sort of the Carl Paer uh     
33:08     
the point of science progresses through like saying the theory doesn't work kind of a     
33:14     
thing like that like like like like this continually challenging like yes like there's something to that approach and     
33:20     
like philosophy of history, science kind of a thing. I think that's power, right?     
33:25     
Um but not not just not just that approach like     
33:32     
I think in in many fields right now and it's a conversation that I have all all the time and in many you know um     
33:43     
spaces that we're in here and elsewhere is     
33:48     
how do you how do you demarcate Like I think I     
33:55     
think this is perhaps a stretch to say because     
34:00     
I don't quite know um but the history of Van Gelder's     
34:06     
assertion for dynamical cognitive science and and what he what he wanted to do there leading to     
34:13     
like three decades of pretty well doumented critique and discussion. I think people don't realize like     
34:22     
that's not that that's a nice thing to have for for     
34:29     
a domain space and that it hasn't always been that way. Um and certainly there's     
34:36     
been many um certainly there's been many     
34:43     
arenas where there's been contentious and rigorous debate on theory and     
34:48     
practices and like like that's that's not an unusual thing. It's just I keep I I always have a permanent reference     
34:55     
point in my mind is something that I mention for like um I'm mentioning when I'm introducing     
35:01     
people to a lot of things that that are coming on board is like Margaret Bowden and the 20 the 2007     
35:10     
demarcation and and how in in like her massive I think it was like mind and bot     
35:15     
mind mind is machine or something or her large compendium series she was like saying like that was sort     
35:21     
At that point like it's it became somewhat untenable for someone in     
35:27     
cognitive science to know all the diversity of branches and thoughts that were happening. And     
35:36     
I I I think it's an interesting reference point because that was both before you know before     
35:42     
deep learning before LM and before all this other stuff. So to put a bow to put a bow on on my part     
35:49     
of this and I'm happy to hear from Bradley or Morgan or anybody else. Um we     
35:54     
had a we had a nice discussion about the paper it and I forgot what we decided we     
35:59     
want to do next time. Um I think oh yes I remember now we're going to go to one     
36:05     
of the other papers in uh the world models special issue rural society a     
36:11     
that that we were also published and uh Avery and Amanda kind of found one they     
36:16     
wanted to do there. So we're going to go back to that space and look at I think it was like topological     
36:22     
implications of some some things there. the topologic paper I think le with Levven as one of the senior or later     
36:29     
authors on on that that should be good and kind of just you know     
36:36     
more more more at large that we're kind of just getting the band back together about some things uh so it's good to see     
36:43     
uh Amanda kind of doing Amanda's stuff and Amanda takes and Avery oh I should     
36:48     
also mention Avery presented a little bit on alistatic kinds which is sort of their     
36:55     
longstanding project and ideas that they've, you know, made and then presented a little bit, developed, put     
37:01     
on the shelf, come back now with some new things and new takes on it. Uh and     
37:06     
there you know Alysa cards is sort of a an approach to regulation, regulatory     
37:11     
weights and imbalances or biases or preferences um that individual agents have and how     
37:18     
that might um uh     
37:25     
it is also commentary on the agent in an environment uh as well. It's it's a     
37:31     
it's not quite vertical horizontal causality if you will in the fuch sense but but there's some interesting     
37:39     
overlaps between that that they're fleshing out doing some archetypes around those kind of uh processes     
37:45     
information men seem interesting in or interested in that as well so we'll probably hear from those updates head to     
37:53     
uh finally the last thing I'll say about this it did not come up in the I     
37:59     
mentioned this in chat though or in Slack. Uh I I would like to find the old papers on uh it was like developmental     
38:07     
freedom and developmental like capacity. I don't know probably three or four years ago now. Um because I am one of     
38:17     
the things that Gerro is doing is sort of incorporating this is my own personal     
38:23     
I should say I'm doing this and and Jerro is supporting me in looking at this. It's not necessarily a JPro     
38:30     
sanctioned and and or oral lab sanctioned um     
38:39     
uh project yet, but I have a vision of     
38:48     
somewhat in line with the 1943 papers and and Leven's sort of repeated     
38:53     
attempts at uh trying to better categorize both agents     
39:00     
or artificial and and biological agents. A more unified principles that would cut     
39:06     
across both substrates or or or embodiment, embodiment types of of agents, if you     
39:12     
will, diverse intelligence, allow diverse intelligences. I have a project that I'm working on um that     
39:22     
would look at things like developmental freedom maybe a little bit of metabrains some of the mental health work uh     
39:29     
condition future stuff in general world models something that's a bit syn synthetic and and perhaps ambitious     
39:36     
perhaps aspirational but I'm trying to not quite assemble the the infinity     
39:42     
stones I think that's quite it's more like some loosely polished pebbles     
39:49     
uh that I'm trying to assemble maybe into a kind of you know a rudimentary     
39:55     
uh uh a crude a crude mosaic like thing uh     
40:03     
that that's where I'm that's but I I if you ask me what's what's happening in     
40:09     
the in coation futures besides besides you know we're reading some papers Amanda that's kind of Maybe continuing     
40:15     
from some of her old fiction future stuff, embody nerve phenomenology. Aver's got Avery's sort of ales kinds     
40:23     
and taxonomy of of affordance's work going on. Uh maybe Bradley and     
40:28     
orthogonal lab have and cyber the the spirit of the cybernetics reading group which I'm open. I'm I would like to kind     
40:35     
of find maybe a synthetic name or something. I don't I'm just calling it the Kish     
40:40     
reading group because that was like my originalist most original association. We can change it. So we have these sort     
40:47     
of nice themes of world models kinds Amanda's philosophical     
40:53     
cognitive inquiries into what is let's look at you know we we have important we     
40:58     
have important things to look at in in human human cognition that isn't all about AI. Like I really like that that     
41:04     
perspective is centered as as we're not going to have someone who's just going to willing like oh let's go and talking about AI stuff all the time too. I     
41:10     
actually really like that. And then me with whatever I'm not even going to try to categorize myself more than I already     
41:16     
have right now up my meeting and then broader cognition future space update and I'm happy to have uh Bradley say     
41:23     
more anyone else. Yeah, great overview and a lot of talking about a lot of the salient issues that were are coming     
41:30     
bubbling up from that meeting series. Um I do have some more information about     
41:36     
developmental freedom. I've been kind of using um Gemini and notebook to     
41:43     
summarize some of the from the papers and and slideshows and I'm kind of     
41:48     
working through kind of what it's kind of generous generating a kind of a synthetic     
41:54     
um description of what that is. So like you know going across the different papers I think we've talked about     
42:00     
developmental freedom and slightly different ways and I just wanted to get a handle on what that is you know like     
42:08     
from the different descriptions and you'll find this a lot of times if people write a series of papers on     
42:14     
something the description changes because you're always thinking about it in a new light so you want to bring     
42:20     
everything back together. I super clearly in my mind there's like     
42:26     
in I don't know the exact words obviously in my mind there's like one or two paragraphs within one of the papers     
42:33     
and it might have been just a preprint. I don't know if this was ever uh like submitted to a conference or not, but     
42:39     
there's like one or two paragraphs that I really want to find where one the concepts to find, but then also uh um     
42:47     
like it was a it was a particular snapshot of how we were thinking about at the time. I was like, "Oh, I got to I got to find that is so I I find which     
42:53     
one it is." So, um, I don't know if you're if you're going to make one of those synthesis videos or there's like a     
43:01     
rumage around through some of our past papers and I don't know, maybe it was on the the um the organization     
43:09     
uh I don't know what the PE page or the organization macro repo. There was stuff     
43:14     
there to look through, too. So, I'm going to try to rumage around to that, but anything you find I'm happy to     
43:22     
look at. Yeah. Yeah. I think that's um something that we can revisit and yeah, I might do     
43:28     
a video actually. Um yeah, you know, it' be nice to have that as a reference. I don't know if it would be,     
43:35     
but maybe it's better as a video or like some sort of hybrid where I make slides     
43:40     
or something. Yeah. Um e even like a very simple even like even     
43:49     
something maybe like a small it could be a very small video like just sort like here's paper one paper two paper three     
43:55     
or and maybe like here's a what kind of here's how we talk about it in paper one like a sub slide main slide sub slide     
44:04     
you know like like that kind of a that would be great I mean that no I don't     
44:09     
know how much work that would be but like I I'm going to have to do something like     
44:15     
that myself probably in some form. So, yeah.     
44:20     
Yeah, that's good. Um, do you have any other comments or questions on that?     
44:28     
I I have a few other updates that aren't related to this like data interaction update this week. uh digest we met last     
44:36     
night briefly but for Kishia futures um that's set and absolutely interested     
44:43     
in developmental freedom as as you assemble anything yeah     
44:50     
uh do you want to do the updates now for data yeah they won't they won't they won't be     
44:57     
long um okay uh if if anyone from that I I invited     
45:03     
them. Uh I I loosely I I think if people come I'll be more likely in the next     
45:09     
week or two than than this week um to to our Saturday meeting. Um     
45:16     
the first meeting was great. um the first cohort meeting. Basically what     
45:21     
we're trying to do that that we actually can do this time there's a space um on     
45:27     
Wednesdays uh where     
45:32     
pretty much everybody in the cohort can meet which is kind of amazing. we have     
45:37     
currently and and I'm I'm working to both it's it's a dilemma because it's     
45:42     
kind of like Google Home of Code like I only have finite time and I'm the main person for the you know if I had certain     
45:49     
other people or could combine some projects more easily it might be a little bit easier to do more but     
45:56     
currently there's four undergraduate students and one one one solid graduate student and one to two that maybe     
46:04     
will will be part of it indirectly Um and     
46:10     
they all were able to meet Wednesday on very on somewhat short notice um at kind     
46:16     
of as sort of our week zero preliminary meeting where we're just getting used to stuff. And then what we're doing and     
46:22     
ultimately is I'm having a just one-on- ones to get to know people and sort out their projects for the for the term is     
46:28     
basically a center bridged Google summer of code setup. It will basically be I don't know     
46:34     
roughly 10 weeks or so of of working on things in the summer. Um some folks want     
46:39     
to do something a bit more technical. Some folks are interested in one one individual who recently     
46:46     
graduated from a very good program uh was I said to them during interviews     
46:52     
like hey you may be like slightly overqualified for some of what we're going to be doing here but I'd love to     
46:57     
do this at a certain approach for you at a certain angle. And what I'm realizing is one um you know they were like oh     
47:05     
let's I do want to do some project stuff but I also want to talk about strategy and professional development and develop     
47:12     
my arguments and in terms of this more applied how do I communicate and get to know this space and I actually had     
47:19     
someone else not at all in the program uh find some of what I posted on the     
47:26     
internet on on the new website and and other things and basically     
47:32     
reach out and be like, hey, I I want I I want to both understand this and do some     
47:37     
more of the contextualizing work and get used to like being interlinary spaces as well. Um, that's maybe less of a data     
47:44     
injection, more of a jerk thing at large. But point being, I'm     
47:51     
more than I realized. Uh well I I've said this recently but     
47:57     
just the yes a lot of fantastic qual uh candidates and and very lucky for that     
48:03     
but also just the there is a real need that I'm trying to address. Am I am I     
48:10     
getting it perfectly and what I'm trying to offer people as they're coming to try to understand more about data and     
48:16     
direction or understand more about operating in a space that's like responsible ethics or responsible AI     
48:22     
data ethics uh human flourishing whatnot like getting building the sort of     
48:30     
on-ramps and pipelines so they can go do cool stuff in that space is is is     
48:37     
you know a work in progress for me and for for like every other, you know, it's a challenging space to be     
48:43     
in, but people are aware of that and willing to work with that overall. Um,     
48:48     
and and so the cohort that we have, like, you know, it's just starting out, but everybody in it, um,     
48:55     
I just I look forward to talking to them, you know, just talking to them over the summer, no less really cool     
49:01     
projects. Um I we get into what they are but but um     
49:06     
some of them we haven't had the discussion yet but one or two folks are     
49:11     
are are um finding some very specific things they want to do. Uh and one of them is     
49:19     
a very interesting take on um multi- aent or more so multi-instant     
49:28     
systems and let's say unconventional ways that might steer or guide uh     
49:36     
certain behaviors or ways of interacting. you have we had a discussion last night um in digest about     
49:43     
uh like um the the the foundational instructions     
49:48     
they give an LM right like here's your here's your your main things and how do you deviate from that we've talked a lot     
49:54     
about drift uh persona drift in in the in that sense from from assistant you     
50:00     
know archetypes or personalities or whatever but     
50:06     
looking at these different ways where there's multiple points of interaction in a a community or an environment or an     
50:13     
enterprise situation. uh with like the like the sort of one one to one to many     
50:20     
but that one is also several instances of the same agent or     
50:26     
or LM and and like how how is how does that environment or set of interactions     
50:32     
um can can what are some interesting     
50:37     
regulatory things in that space? I I'll leave it at that uh about about about that project. But it's been cool to see     
50:44     
people that um people are very interested in the spaces and people are like, "Okay, we want to go in here,     
50:50     
learn stuff, and and and try to make some things or figure some things out." And uh it's going it's going quite well.     
50:55     
I'm very I'm very I'm very pleased with that. And and have a little bit of the     
51:01     
uh here's my perfect vision for what I want to see here and and here's a     
51:06     
perfect presentation that I want to make. And it's like sometimes you just have to     
51:13     
go with it and make it as best you can even though you have all this preparation when it hits like oh you're     
51:18     
in it you know. So now it's just things are rolling rolling rolling rolling and it's exciting. Um and I'm very very     
51:24     
happy that everyone's um I really appreciate everyone in the program so far. And then um very quickly on Digest     
51:33     
uh we had a discussion about a it was a reply kind of you know there was that     
51:39     
three decades later from the Van Gelder and the Beer paper. This was more like five years later uh after um after um     
51:48     
the stochastic parrots paper which is sort of this landmark is an interesting critique paper from     
51:56     
Timru Margaret Schmitchell out of Google ethics and and others in in in the     
52:03     
Google ethics team at the time which became both this iconic reference point     
52:09     
for AI by criticism and a huge moment in     
52:16     
time for people realizing oh Google just like destroyed their a ethics board and     
52:21     
this big kfluffle this big controversial stuff and Google Google's motto used to     
52:26     
be do do no evil you know kind of stuff and so I was looking at that five years down     
52:32     
the road and the paper was essentially critiquing how     
52:39     
it was a pre-print paper that is offering a critique of people who are concerned with AI ethics shouldn't just     
52:45     
say like you basically challenging them to do more by saying don't just write off AI hype as oh you're just talking     
52:52     
like it's a stochcastic parrot but but do more than that in terms of look at the existing impacts right now about     
52:59     
things like how it's affecting different labor markets how it's affecting um you     
53:05     
know comprehension and they made a comparison to you know past revolutions,     
53:11     
the type type setters and and and you cultural moments of change and all. We     
53:16     
we had a very nice discussion. Uh Avery co-hosted the meeting. Um we had another     
53:22     
a new person join as well as kind of a audience member if you will. Um and it     
53:28     
was it was it was it was a good and fruitful was a good discussion around you know that trajectory of things.     
53:35     
Avery Avery never a Avery wanted to pre previous week we looked at the actual     
53:40     
original stocastic Paris paper and and kind of Avery wanted to kind of do a deeper dive on that. So we'll kind of on     
53:47     
on a little bit of arc of that as we return into um turn into some other to some other     
53:54     
things. But that's what that that meeting was about. It was it was a it was a nice it was a nice meeting.     
54:00     
I'll I'll post something about that soon. Um but that's it. That's that's     
54:06     
it. Summertime is like, okay, there's like a full load of Monday, Wednesday,     
54:12     
Wednesday, Friday, Friday, Saturday. Like that's like five things um in in in     
54:20     
the Jerro the JPro uh community that's     
54:26     
I mean like hosted in DVO learn posted an orthogonal lab some like these things. So, it's just like even bringing     
54:33     
people into the new system, it's like, "Hey, here's like this current roster of     
54:38     
meetings." There's a lot going on. So, it's fun time.     
54:45     
Yeah. Yeah. Thank you. Yeah. Yeah. It's uh my audio just cut.     
54:52     
Oh, yeah. Thank you. Yeah, it's great. Um so, yeah, revisiting the stochastic     
54:57     
parents paper. I think it's useful. I know they do the um     
55:03     
that group does a Twitch stream. Uh yeah, DARE. Yeah, it's led it's it's     
55:10     
for those who are new, uh Tim and Dewbase left Google AI and has did made     
55:16     
their the distributed AI research institute and they're um they have a     
55:22     
very you know their approach to things is interesting and quite different um     
55:29     
and and there's different elements of controversy and how they approach certain things and different members     
55:35     
talk about stuff. I'm not I'm not um fully endorsing anything     
55:41     
but I do think one of the things that came up in in the paper and in the discussion was also how it is     
55:49     
valuable or interesting to get the perspective of like the d the under un     
55:55     
under underserved if you will data workers the people on on who are kind of like you know uh looking at the stuff     
56:02     
the the unseen human impact of of big AI and model training and and all uh that     
56:10     
sort of thing. Uh yeah, so you you were saying sorry. Oh, no. I was I was just reminding us of     
56:20     
the their live stream. I don't know if you've like caught up with sort of their     
56:25     
current thinking and then that's usually kind of you know you write a paper and then you kind of reflect on it over time     
56:33     
and then other people will reflect on it too because It means something to the something different than it means of the     
56:39     
authors. So I I think I think for those in our in our deep orthogonal lab lore community,     
56:46     
there's a little bit of a semblance. We we just for some for some fun big intuition parallels. It's not quite     
56:54     
three decades later Van Gelder and Beer. It's maybe a little bit closer to the     
56:59     
spirit of if not the time uh the spirit of this the paper we read was based more     
57:05     
than the spirit of the martin critique of embody cognition which is very deep     
57:11     
co like one of the first things in the creatures red group we looked at Martinique was critiquing did cognition     
57:18     
futures kind of the same as as what happened to cognitive science from nun but Martin was saying hey like did we     
57:25     
really get embodiment right like are we confusing things like I wonder what Martini now would say about John Mun's     
57:31     
effort to get all this first person first person video and and and all the direct stuff because that's kind of uh     
57:37     
his critique like did we do we actually like do we do we really center embodiment enough are we not using video     
57:44     
as a means to deal with that kind of stuff. So I think this paper that we just read in Indigeness was a bit more     
57:53     
not quite not definitely not isometric or isomorphic uh onetoone comparisons but but kind of     
58:00     
more in that spirit of hey like don't don't get caught up by the hype     
58:07     
around using using don't use the phrase stochcastic parrots to to just like oh     
58:12     
yeah big AI like it was it was kind it was challenging the community to be a     
58:18     
bit more like okay like let's look at the real things that are happening right now um and not just not just sort of     
58:25     
like losing sight of that and um worrying about like     
58:32     
some broader implications of of of AI. It didn't say like I I I don't want to say like AI consciousness stuff     
58:39     
specifically but just what's happening right now. So yes, uh we can uh move on.     
58:46     
Yeah. Right. Yeah. Well, that's great. Yeah, we should continue to think about that. I guess more in that vein of uh     
58:53     
revisiting society, ethics, tech, and kind of the current state of what's     
58:58     
going on there. Yeah. I mean, because there's a lot of stuff going on there. You could just     
59:05     
grab something and say this is a concern. It might have if we     
59:11     
go back to sarcastic parents. This is a concern that you know they were     
59:16     
addressing five years ago. Things like that. And that's that's one of one of the one     
59:22     
of the analogies that's coming up a lot is like I I'm referencing sort of the FDA timeline a lot. And when I'm     
59:28     
interested with the um data and direction folks like I think it's important for people to understand one     
59:35     
everything's moving so fast and two a lot of our structural ways of dealing     
59:41     
with technological change or implementation at certain levels is just designed for a very different sequence     
59:48     
of events than what's happening right now. Like though I reference all the time to Sam Samman being like, "Yeah,     
59:54     
you know, um people are just going to get used to there being a lot of videos that are fake and videos about     
59:59     
themselves that are fake." And it's just like these like this is this is this is not the same as FDA clinical     
1:00:07     
trials for a medical device and that that that's okay but like we're in a world where that's     
1:00:14     
so so even in the context of stoastic parrots paper um like what was sort of an insight like even that that paper     
1:00:22     
starts by saying in the last three years which was at the time like 20 2018 2019     
1:00:28     
2020 and like the a three-year sentiment a three-year like aggregate sentiment on     
1:00:35     
the sh the direct the direction of like language processing and language models and and and how AI is interact inter     
1:00:42     
interacting with these these things versus the last three years like those are very     
1:00:49     
different threeear segments in terms of what's how much some things are in the face of of people even so anyway we can     
1:00:57     
I could I feel like I keep getting stuck to the whirlpool of that. So, I probably     
1:01:03     
move on talk about other things. All right. Thank you, Jesse. Yeah.     
1:01:09     
Oh, I I was I was trying to see I I was hope I was seeing if Avery     
1:01:16     
or some others might have joined, but I don't think they can right now. So, Okay.     
1:01:22     
Looks like Morgan is maybe wanting to give an update.     
1:01:28     
Uh, no. I was just trying to figure out my camera. All right.     
1:01:34     
I mean, um, yeah, give me give me a second because I'm just, uh, uh,     
1:01:42     
you know, it is it is nice. I mean, I gotta say that     
1:01:48     
I've never used OpenAI, but the the cloud remote control is the um is the     
1:01:54     
way you can you can uh you you never have to stop working,     
1:02:03     
right? Except except when uh um your remote     
1:02:10     
control systems need u sudo access or like you know they need you to run     
1:02:17     
certain certain operations. But um yeah got got something cool in     
1:02:25     
terms of um looking at uh again just like just     
1:02:31     
thinking a lot about benchmarks of foundation models. Um so I'll talk about     
1:02:36     
uh talk about this and um and a paper from um from UCSD uh um     
1:02:45     
on FM scope is the the name of the paper.     
1:02:51     
I'll just drop it in the chat. Is this foundation model scope?     
1:02:57     
Yeah. So here I I'll drop the paper in the chat. One sec.     
1:03:04     
Okay. Yeah. This is the identity trap and EEG foundation models.     
1:03:09     
Yeah. Yeah. So, so um Zepang Jung is the co-director     
1:03:16     
of the Schwarz Center for computational is it computational earth science I     
1:03:23     
think. Um but he does like like the center focuses     
1:03:29     
on EEG or you know this is this is Scott McKay is the the other co-director and     
1:03:37     
um sorry I don't know if you can hear that siren. Um     
1:03:43     
uh this is the this is the lab that develops EEG lab     
1:03:50     
which is you know is probably still one of the most widely     
1:03:56     
used EEG processing packages. Um but I do but I do think     
1:04:05     
that this is something that is relevant for for other modalities, right? Um     
1:04:13     
and you know what? Um     
1:04:18     
uh yeah, so just just thinking a lot about how to how to do     
1:04:28     
like like at least at this at this point this is more of like a BCI, right?     
1:04:33     
Right. But but you can do that you know like with the softened group the med arc is     
1:04:41     
the um the open science group um they are doing that with fMRI as well you     
1:04:48     
know so it's an interesting um     
1:04:55     
uh it's it's an interesting     
1:05:00     
some interesting issues that they bring up especially about um these kind of     
1:05:05     
small data sets and um I thought this     
1:05:11     
was particularly relevant because um we've got a um     
1:05:22     
um this package is the     
1:05:29     
you know I I still this is probably Neuroch X's most     
1:05:38     
most um it it's not our most starred project     
1:05:45     
but I would say that it's definitely the most um uh it's the most active starred project     
1:05:57     
and it's it's filled with data sets that are um     
1:06:07     
probably you know relevant to this this FM scope like like analysis of how much     
1:06:15     
are you kind of memorizing subjects and versus um versus finding the the     
1:06:24     
underlying representations and the Yeah. And and this is also super     
1:06:34     
relevant because you know talking about how we're in a     
1:06:39     
different we're in a different age. Um     
1:06:46     
Moab reminds me of a project from the kind of pre deep learning age.     
1:06:54     
It's definitely a precaling age, right? Where, you know, again, this     
1:07:02     
is this is where you could, you know, write a write a master's thesis or or     
1:07:09     
potentially even a PhD with, you know, a data set with like under a hundred     
1:07:15     
subjects. Um, you know, a and and and be and like and     
1:07:22     
that would be a lot of work. right? Like like like this is not to minimize in any     
1:07:29     
way, shape or form like how what a monumental effort that would be.     
1:07:36     
But you would, you know, I mean, I I I know this because I've like had grad     
1:07:42     
students come to me to talk about this project and say, you know, I can't believe I wish I'd known about this     
1:07:48     
project before I gotten started because um     
1:07:54     
yeah, they they were either the person collecting the data and again, you know,     
1:08:00     
if you're one person collecting data, like if you're going to get 50 subjects, you know, like That's a huge amount of     
1:08:07     
work, right? Um as well as like someone who's     
1:08:13     
potentially writing the analysis classification pipeline, right? So, you     
1:08:19     
know, you're developing some novel classification pipeline.     
1:08:25     
um you would have to be the person to write the new one and write the ones to     
1:08:33     
compare it to to show that it's better than these things, right?     
1:08:39     
And you know, it's it's nice to think that that     
1:08:44     
everything is available as open source, but you know, again, this was not the     
1:08:50     
case. And you know, this was one of the nice things about Moab, right, was that like it was a set of data sets and it     
1:08:58     
was a set of we're gonna to to use the current lingo, we'll just     
1:09:05     
talk about state-of-the-art algorithms, but it was it was basically classical ML     
1:09:14     
pipelines with with a cool particular     
1:09:19     
French uh twist u with this um Romanian     
1:09:24     
geometries for for classification which is cool stuff. I mean, you know,     
1:09:29     
it's it's nice stuff and um but it's certainly a big part of a     
1:09:37     
lot of deep learning methods now, especially if they're they're um coming     
1:09:44     
from the kind of like pietorch geometry     
1:09:49     
um world where they're they're considering manifolds and things like that.     
1:09:56     
Um so you know but but yeah so     
1:10:02     
grad students have to come saying um     
1:10:08     
you know this this project could have could have completely changed how they did their work if they if they'd known     
1:10:13     
about it in advance. Yeah. That said,     
1:10:18     
these this is um even when you combine all these data     
1:10:25     
sets together, it is it is still     
1:10:30     
um it's it's a great effort, but it's not     
1:10:37     
what we would call like a scaled effort. not, you know, certainly not in     
1:10:44     
the tech sense and not and um and not even in the medical imaging sense,     
1:10:53     
right? So the the current FOMO 26 challenge that we're doing with with     
1:10:59     
MedARC is doing um for for Miki, you know, is using a data set of 300,000     
1:11:08     
MRI scans, right? So this is this has got a much smaller     
1:11:15     
number of of you know some of these some of the data sets that are in here um uh     
1:11:22     
are very small and and so it's saying now three you know 300 I mean 3,500     
1:11:31     
subjects and um so I'm curious what that's going to include. One of those I     
1:11:38     
assume is a is a new data set that they've added that has like like a thousand plus you know like like some     
1:11:46     
somehow this is this has been bumped up with with like one particular addition.     
1:11:52     
Um but uh um yeah the     
1:12:00     
this is you know it's an important consideration that that I think we can     
1:12:07     
actually bring to other like topics of medical imaging and um uh so it's like     
1:12:18     
I've already taken this f scope analysis and I applied it to a large data set of     
1:12:26     
of MRI scans where we're not looking for for subjects     
1:12:32     
but it's the child mind institute healthy network data set which is actually collected across four different     
1:12:39     
locations. So um that's another thing that you can     
1:12:46     
um you can use this to to actually see again kind of like how much is the it's     
1:12:54     
kind of breaking apart what's you know trying to do um a kind of interpretable     
1:13:01     
AI approach um that that also kind of reminds me about like doing diagnostics     
1:13:10     
and and other um uh other techniques in     
1:13:15     
in statistics, you know, like like when you're looking at a general linear model     
1:13:23     
and you're trying to tease apart like the interactions you have, what happens when you control for this, what happens     
1:13:29     
if you control for that? And and trying to bring that to, you know, the the     
1:13:35     
foundation model um uh results that you get. So I think it's I think um     
1:13:44     
uh more general than just EEG.     
1:13:51     
Yeah. So yeah, let's see what these papers look like. So this is the identity trap     
1:13:58     
and EEG foundation models. So basically they talk about these FMs     
1:14:04     
or foundation models for EEG. They report strong accuracy on clinical     
1:14:09     
resting state EEG. Uh but high accuracy under subject disjoint cross validation remains     
1:14:16     
ambiguous. It can reflect genuine clinical marker or subject identity features likely with     
1:14:23     
label. That's what you're talking about with respect to like individual variation and versus like an actual     
1:14:31     
effect. Um we name this the identity trap and ask whether it can be diagnosed at the     
1:14:38     
representation level before fine-tuning. So this is where you trying to remove     
1:14:45     
uh basically artifacts of individual subjects.     
1:14:51     
Um and so that's that's what they're doing. So they propose FM scope which is     
1:14:57     
a frozen representation protocol packaging five diagnostics. We apply to three pre-trained foundation     
1:15:04     
models across four data sets and then uh they     
1:15:10     
find that the identity trap is universal. The dominance is a removing or this     
1:15:16     
dominance is a removable linear axis. erasing and improves label decoding     
1:15:22     
where where the label varies with within subject. Um and then aperiodic one fois is one     
1:15:30     
subject carrier removing it drops the subject probe. Um     
1:15:36     
and then fine-tuning amplifies label variance only in cells of the literature     
1:15:42     
established cross subject marker. Uh and so then the identity trap is a     
1:15:47     
physically grounded instance of shortcut learning. The preferred cube is a measurable physio phys physiological     
1:15:54     
component and subject disjoint splitting alone cannot rule it out. FM scope     
1:15:59     
separates gains reflecting a biological marker from those reflecting subject     
1:16:05     
identity. So that's very good. Um, yeah. I mean, you know, I'm glad that they     
1:16:10     
kind of dug into what a found, you know, what a foundation model is and maybe some of the caveats of     
1:16:17     
combining a lot of data and then thinking about things beyond mere     
1:16:23     
correlation and and kind of getting at some of these things, getting at maybe some of the things that can make a     
1:16:29     
foundation model not so predictive. Um, then Oh, go ahead. Yeah, I was just     
1:16:36     
going to say like this is this is interesting to just to to give you you     
1:16:43     
know like like something EEG that we are going to to be doing which is um     
1:16:53     
this uh uh this this company that is doing you know     
1:17:01     
showing pictures to people and then trying to predict what picture they're     
1:17:06     
seeing from just their EEG trace, right? Is is doing this kind of like we've     
1:17:13     
trained on this data, you know, we we've got this data set of say 10 or 20     
1:17:18     
subjects. We've trained now we're going to fine-tune it to the person that's now     
1:17:24     
sitting in this chair. Yeah. Um Oh, I lost picture. Sorry.     
1:17:33     
Um and um that's that's what uh     
1:17:40     
uh the this is going to be perfect for that, you know. um or like being you     
1:17:48     
know the the what we hopefully have is a very     
1:17:54     
we do have a demonstration um example where it's like like we should be able     
1:18:00     
to fine-tune better and more accurately fa faster and more accurately     
1:18:07     
um if if we can we can um remove this     
1:18:12     
compound and I guess what you'd call it's not it's Not pre-training, right?     
1:18:18     
But before fine-tuning. Yeah. Yeah. Yeah. Right. Pre-T or uh pre-confound removal or     
1:18:25     
something like that. Yeah. Yeah. Yeah. I'm I'm still learning my terminology. Anyway,     
1:18:30     
but I I I'll just I'll drop a link to this um because it's a I like this this     
1:18:37     
particular company in terms of what they are trying to do. So, if we go back to the GitHub repo um     
1:18:44     
Yeah. So this is the GitHub repo. Um we basically have a public an initial     
1:18:50     
public release. Um and yeah so it's a     
1:18:55     
diagnostic toolkit for auditing EEG foundation models. Um     
1:19:02     
and they have five diagnostics. Um they have a variance decomposition     
1:19:09     
subject access erasure aperiodic or foof ablation     
1:19:15     
and then layerwise probe and then direction consistency.     
1:19:21     
So these are you know one the first one is the subject identity dominate the     
1:19:26     
representation. The second is is that dominance confined to a linearly removable axis and does it     
1:19:34     
help to remove it? Then the aperiodic ablation which is is     
1:19:40     
the one overf spectral component of the carrier of identity. So there's always this 1 overf spectral component you can     
1:19:47     
remove or not remove. Four is at what depth does the label become linearly separable?     
1:19:54     
And then five is do subjects encode the task contrast along with a shared     
1:20:00     
direction. So these are all you know quite relevant to     
1:20:05     
data analysis. Um yeah and then I guess you can audit your     
1:20:11     
own data with this code. You can reproduce the paper that we just     
1:20:17     
saw and then you can bring your own data set or use some of their data sets here.     
1:20:26     
All right. Very good. Um, so yeah, thank you     
1:20:32     
Morgan. And that's hugging. Oh, the hugging face. Well, I'm just     
1:20:37     
I'm just sharing the they all joined. So, all all joined is this um this     
1:20:44     
company that's trying to do, you know, kind of like the EEG version of of um     
1:20:53     
uh Medarkc or, you know, the Mind Eye project.     
1:20:58     
Yeah. Um, so it's like like if you go hit the um the alljoined um.com     
1:21:07     
just because it's got a nice like like uh     
1:21:13     
Yeah, you can you can see their their headsets in action.     
1:21:18     
Yeah. Um so this is Enigma. Well, yeah, it it's it's a different     
1:21:24     
enigma. It's funny. Okay. Yeah. Yeah. So that's the CEO and the and actually one of the engineers. But the um uh I think     
1:21:32     
Enigma is what they're calling their calling their foundation model.     
1:21:37     
I forget. There's too many enigmas, you know. There's like the the the the enigma that's working on     
1:21:43     
like neural representations. There's the, you know, u Yeah. Anyway, I'll let     
1:21:50     
you get to the um let's get to the more presentations, but but um but I do want     
1:21:56     
to see what you can get from this in terms of improving     
1:22:01     
um uh uh the kind you know the the this     
1:22:07     
particular kind of use case of foundation models and and if it's um can     
1:22:13     
be a practical you know this is obviously super relevant for Neuro Techch. Um, and some things that I'm     
1:22:20     
trying to get started with the student projects, but Oh, that's great.     
1:22:27     
Yeah. Yeah. So, thank you. That was good uh good to to kind of visit that world and     
1:22:35     
see the state of the art there. So, it looks like uh Kabia would like to present Jess has been setting this up.     
1:22:42     
Uh yeah. So actually we were just discussing whether I can present the doc     
1:22:47     
which I had sent to both of you uh the idea list. Okay. Um so can I start?     
1:22:55     
Yes go ahead. Yeah. So I had actually listed down uh two to three ideas uh based on some     
1:23:02     
papers that I went through. So first idea was to add stage development to     
1:23:08     
active inference agents like u the I could not find a prior work where they     
1:23:15     
have used active inference and stage development like moving from juvenile to adults     
1:23:21     
and u I did found structural learning papers but not uh this type of papers     
1:23:27     
also this is just an enhance like we can add endogenous transitions uh rather Then     
1:23:36     
moving development through fixed time clocks and it seems to answer these two     
1:23:43     
question. The first idea whether does a phase structured prior schedule produce better generalization than a uniform     
1:23:50     
prior schedule and does the agent that decides its own transition timing outperform the one on a fixed clock. So     
1:23:59     
these were some of the papers that I went through like first one was the     
1:24:06     
foundation paper of active inference. So it talks about uniform updates but     
1:24:12     
there are no developmental stages within it. Second was beyond the adult mind     
1:24:18     
paper. It's mostly a theoretical paper where they have discussed that     
1:24:24     
predictive processing is a little bit ine inefficient to account for cognitive development in infants like um just to     
1:24:32     
explain they have not told that it's not correct but uh in order to explain we     
1:24:38     
need a complete theory of cognition like um we need an agent that starts from     
1:24:44     
nothing to a fully developed model like how a newborn who starts with no model builds up sophisticated models. The     
1:24:52     
challenge PP mostly describes incremental updating of an existing model but babies need something far more     
1:24:58     
radical. They need to construct entirely new structures from scratch. So this was     
1:25:03     
the challenge that this paper discusses. uh the gap was to introduce a flexible     
1:25:09     
starting point and a structured learning toolkit that uh this paper addresses     
1:25:16     
active inference for learning and development in important neomorphic agents. So it's a paper that discusses     
1:25:24     
that in order to show a true intelligence, we need three things. A     
1:25:29     
body learning through physical interaction with the environment, a neuromorphic hardware, a brain inspired     
1:25:35     
computing that process information the way neurons do, and a developmental approach like learning that progresses     
1:25:42     
from simple to complex. The fourth paper was emergence of goal     
1:25:48     
directed behaviors for active inference with self prior. So this paper proposes     
1:25:54     
how goal directed behavior emerges in early developmental stages     
1:26:00     
like uh they modeled the child with a sticker on one hand another. So without     
1:26:05     
any rewards the child removed the sticker due to mismatch between the     
1:26:11     
internal environment and the external. So the experiment also proved that     
1:26:16     
infants aren't stubbornly fixed forever. If a change persist long enough the infant's brain will eventually update     
1:26:22     
its baseline. So another addition to the first idea would be to add hetrochrony     
1:26:29     
like to extend and see how different developmental windows affect like in uh     
1:26:35     
different stages of life. What if one stage of life is given more amount of time than the other like something that     
1:26:42     
happens in C elegance as well. I think like in lar stages if one window is much     
1:26:49     
more open it mutates. So     
1:26:54     
again the I could find some papers on critical periods but mostly on neural network and not on active inference     
1:27:02     
part. So that gap still remains open. And the third idea would be to extend     
1:27:07     
this paper of goal based NCA. Um they have shown that the neural cell neural     
1:27:14     
automator is somewhat robust to loss of data like if there is a 40% loss of data     
1:27:20     
it can still somewhat get to the end goal but it     
1:27:25     
there's a gap that what if the data is damaged like can the NCA recover from partial information rather than loss of     
1:27:32     
data what if the data is damaged yeah so these were the three ideas that     
1:27:40     
I just shortlisted them. I just wanted to know whether which idea should I go     
1:27:46     
forward with or are there anything that you suggest?     
1:27:51     
H yeah, this looks pretty interesting. Could you scroll up again? Uh     
1:27:57     
yes. So yeah, I mean definitely um     
1:28:03     
you know thinking about all these different mechanisms that you could sort of incorporate into the the work. So you     
1:28:10     
know you have of course the reason why we want to pursue development.     
1:28:16     
Well there actually two reasons two main reasons. One is that it's not like     
1:28:21     
adulthood. So you usually have like the origins of an adult network or an adult     
1:28:30     
model or something like that. So you know like you say add a development phase like juvenile brain is     
1:28:37     
more plastic and we assume that the developmental stage is weak prior versus     
1:28:42     
adults who have strong priors. And then we could add in something like     
1:28:48     
a phase transition or some sort of clock mechanism that would like kind of time out that     
1:28:56     
transition from development to adulthood. So I mean that's kind of one reason we do it. Another reason of     
1:29:03     
course we do development is because we're interested in this nature versus nurture question which is that you know     
1:29:12     
if we have sort of nothing uh as the origin of your prior how do     
1:29:19     
you gain a prior or a strong prior and the you know answer to that of course is     
1:29:25     
you collect data or you acquire information from the environment     
1:29:31     
but then there's that process of development. So that's kind of what's interesting there. Um, and then you can     
1:29:37     
of course add uh innate features which are things that are sort of hardcoded     
1:29:42     
but they're not deterministic long term like you know they're there to give uh     
1:29:48     
the sort of maybe the set of priors that's um you know just some something is like     
1:29:56     
almost like a set of training wheels uh where you have things that you inherit that you start with the     
1:30:04     
tendencies that you move towards and then plasticity might move you away from them as you learn that sort of thing. So     
1:30:12     
that that's all kind of why we do development. So I think like you know some of these approaches like you're     
1:30:18     
kind of going into the active inference direction which is where they're interested in     
1:30:24     
kind of uh you know this sort of gradual improvement using basian methods like     
1:30:31     
prior. they're interested in epistemic uh aspects of of uh that model where it's     
1:30:39     
like you know what does the knowledge look like? Um and then of course you     
1:30:44     
have um predictive processing which is kind of part of active inference where     
1:30:50     
you have some sort of neural model that can do prediction of things and     
1:30:56     
processing is a predictive act. So neuroprocessing is about predicting things in the     
1:31:02     
environment. Uh if you encounter things you know if you if you get information     
1:31:08     
from the environment and you acquire it then you know if you see something that     
1:31:14     
you've seen before then you use that to predict maybe the source of food or     
1:31:20     
maybe some other connection that you can exploit. So that's predictive processing. And then you know this is     
1:31:27     
something that um of course we can't necessarily use in development because     
1:31:32     
it's inadequately defined as as the theory is defined today. I mean like     
1:31:38     
this area like of predictive processing is like h hotly debated in the cognitive     
1:31:45     
science literature. So like if you were to go in that direction, you'd have to     
1:31:50     
engage with those critiques and the you know especially in terms of development     
1:31:57     
like you know you you have to really kind of dig into the literature a bit for that um to make sure that we're     
1:32:05     
answering a question that people care about. But this I think is a nice question though you know that you have     
1:32:11     
these things in development uh or you don't have these things in development that you acquire through     
1:32:16     
development. So like predictive processing you don't necessarily see it maybe in early development because you     
1:32:23     
don't have any priors or very unique priors but as you move along as you gain     
1:32:28     
experience then you gain uh predict the ability to do predictive processing     
1:32:34     
basically. So I mean you know this is um and I have     
1:32:39     
to say though a lot of times people talk about babies and newborns and it's like um you know this is very     
1:32:48     
human centric. So there are a lot of other types of developmental systems where um you know we could draw from as     
1:32:56     
a biologically inspired model to kind of bolster the arguments     
1:33:02     
or or getting gain inspiration for different approaches to this problem.     
1:33:08     
Like for example, there are a lot of organisms that have a lot of priors that they come with or I'm sorry, a lot of     
1:33:13     
innates that they come with and it's a matter of going from sort of innateness     
1:33:21     
to, you know, plasticity coming online. And so that's that's kind of maybe one     
1:33:28     
another way to do this as well. Uh move down a little bit in the     
1:33:33     
document. So yeah, we have embodiment of course.     
1:33:40     
We have neuromorphic hardware. Um neuromorphic hardware, you know, that's     
1:33:45     
something that is we can also look at like spiking neural networks and things like that as the software equivalent of     
1:33:52     
that where you basically are drawing from sort of the hardware of the brain as it     
1:33:59     
were. I don't like to say it like that, but like um it does draw more from this.     
1:34:05     
It has this inspiration of implementing something in hardware rather than just     
1:34:10     
simulating like behavior or simulating a very broad     
1:34:16     
representation of what's going on in the brain. Um yeah, I think maybe you know     
1:34:22     
that's maybe not as sort of central to what we're doing here or it would be a     
1:34:27     
little bit harder to implement that. Um but embodiment is a very important part     
1:34:32     
of development of course. Um you know we have of course we would like to evolve     
1:34:39     
our agents phenotype along with the behavior. So if we're talking about acquiring priors in development you're     
1:34:46     
acquiring priors from the environment but you're also acquiring it from the     
1:34:51     
phenotype as it's as it's shaping you know. So as you gain length in your arms     
1:34:56     
or you gain, you know, the ability to coordinate your arms or you gain the     
1:35:02     
ability to coordinate your legs, you can start to walk basically. So you know,     
1:35:08     
babies learn how to walk, it's because they have this prior motor circuit that allows them to walk, but they have to     
1:35:15     
coordinate it through learning and plasticity. And so that's what they do. And so that's you know the whole process     
1:35:23     
of learning you learn that prior through um some innates and some experience     
1:35:31     
with the body as well as with the environment. So that's you know that's kind of how     
1:35:36     
embodiment fits into that. Um then you have goal- directed behaviors and active     
1:35:43     
inference. So again goal directed behaviors are um     
1:35:49     
You know, I guess you have to sort of start from a non- goal directed state in your infancy and then you move towards     
1:35:56     
goal- directed states because you learn what those goals are or you learn kind     
1:36:02     
of how events kind of move towards an end at least in cognition. And so that's     
1:36:09     
kind of what this is, right? You know, I I think yeah, negative feedback. And so Jesse's interested in     
1:36:17     
this area. I mean, he's written some blog posts on that. We've talked about this cybernetics paper where they lay     
1:36:25     
out this this taxonomy of different behaviors which we can talk about. Um,     
1:36:33     
but I think yeah, I mean like I think the one of the key things here is just     
1:36:38     
kind of saying, you know, what is development? What does it mean to develop versus be an adult? What does it     
1:36:46     
mean to ha have a body that or to kind of grow into a an embodiment or to grow     
1:36:53     
an embodiment from basically nothing and you know that sort of thing. So     
1:36:59     
those are all important things. Can you move down a little bit?     
1:37:06     
Yeah. And then of so of course you know we want to implement this in some agent     
1:37:12     
we have you know we've worked a lot with brainberg vehicles um we can embody it     
1:37:17     
in a generic agent I mean we don't have to embody it in any specific agent then     
1:37:22     
there's the NCA which is the neural cellular automa I I think that's     
1:37:28     
interest neuroscellular automter interesting but you know that's kind of something     
1:37:33     
that is I don't know how well integrated it is with um some of the other questions. I     
1:37:42     
know that like they have sensory motor Lennia which is a software package.     
1:37:48     
Lennia is an approach um that was developed by Bert Chan I     
1:37:53     
believe at Google and it was a set of approaches where they have these continuous cellular automa and I think     
1:38:01     
NCA is actually kind of part of that whole area of inquiry where they're     
1:38:08     
developing cellular automa that kind of fit in with embodied models. um you know there there have been some     
1:38:15     
attempts to model development with MCAs but it's largely like kind of seeing if     
1:38:20     
you can match a template and so I don't know if there's uh if you can do     
1:38:27     
really effective developmental modeling of aging behaviors using like NCAs or a     
1:38:34     
sensory motor line it's well I know the sensory motor line they've tried to do     
1:38:39     
development that was actually the um Pierre Odor and his group in Paris.     
1:38:46     
Um but that you know that's something that you know maybe we try a more     
1:38:51     
conventional model first. Um but I think yeah I think maybe focusing on the active inference     
1:38:58     
components would be good. Um and then you know thinking about the difference     
1:39:04     
between development and adulthood and then getting into some of these other questions. I I see you have     
1:39:10     
heterocchronone on the list which is of course the timing of development. Um and     
1:39:15     
that's of course important for how things are required and how long you're exposed to them and how long the phen     
1:39:23     
the embodiment uh grows as opposed you know in direct     
1:39:28     
correlation with the exposure of something. Yeah. And we've talked about critical     
1:39:35     
periods as well. Um but the first thing I would do here is to get down this distinction between development and     
1:39:41     
adulthood and then think about like you know what is it that we're interested in um     
1:39:46     
looking at are we interested in looking at how some maybe some task is acquired     
1:39:53     
and this is like in in how they've used development and AI I think in the past     
1:39:59     
has largely been as a mechanism for improving uh training of models     
1:40:07     
So you're training models uh by having them acquire data and then you want them     
1:40:12     
to generalize, you want them to learn associations, you want them to do all these things,     
1:40:19     
but a lot of times acquiring data is a hard task for a lot of agents or for a     
1:40:26     
lot of algorithms or models. And so it's very hard to train something and get it     
1:40:32     
to work. um you know and and have this world model     
1:40:37     
sort of there available to us. So the developmental schemes have all been kind of how do we do this more efficiently.     
1:40:44     
Um but in in like computational agents then we have this additional layer of     
1:40:50     
like if you were using a robot you know how do you get the robot to learn tasks like sensory motor coordination because     
1:40:58     
it's not just as easy as giving it instructions because it has to work     
1:41:05     
within an embodiment and and coordinate everything and you know giving instructions is very hard. it has to be     
1:41:13     
able to explore different options and then implement a solution. So I think that's you know I     
1:41:20     
think I would start with that distinction between development and adulthood and then move into some of these other mechanisms maybe like     
1:41:26     
critical periods and heterocchrony we might also talk about like priors as     
1:41:32     
a general principle for you know how we make     
1:41:39     
how an agent will sort of formula formulate a way of doing things. So, you     
1:41:46     
know, if you don't have experience with anything, you can't really have strong priors. But once you get experience with things,     
1:41:52     
then you can have strong priors and it allows you to be more predictive. So, those those things I think all fit     
1:41:59     
together in a very interesting way. Um, I I know that like in terms of     
1:42:05     
finding something novel to do, you know, that the active inference space I think is quite fruitful because I don't think     
1:42:11     
anyone's really kind of gotten into uh thinking about     
1:42:17     
active inference and development and what that means for sort of acquiring     
1:42:24     
knowledge or acquiring priors and really working that out. So I think that's     
1:42:29     
actually a very good place to to focus on. Um     
1:42:34     
and you know active influence is a really hot field I guess or has a real     
1:42:40     
strong interest for by a lot of people. So um yeah I think that's that's a good     
1:42:45     
way to go. Jess     
1:42:52     
you go first. Yeah. No, I was just saying that um I also found some recent work where people     
1:42:59     
were combining active inference with LMS and trying out different things.     
1:43:06     
Yeah, there's a lot of combination of things like you know people are     
1:43:11     
you know you active inference is kind of a framework for understanding. So it's like a theory but it's not really a     
1:43:18     
theory. uh that's that's uh there's this whole debate of what a theory is but um     
1:43:24     
so it's a framework I guess that's predictive um and people will use this     
1:43:30     
in different settings so if you go to the active inference institute symposium you have people applying it to all     
1:43:36     
different areas like large language models um biology     
1:43:41     
um medicine uh you know all sorts of things and so     
1:43:46     
it's just a matter of figuring out how that fits fits into what you're interested in. Um yeah.     
1:43:54     
Yeah. Um to to that end, I would say uh     
1:44:01     
I guess it's the free energy principle, but but sort of principle versus theory stuff and the principle is like     
1:44:07     
principles not being able to be disproven, but does it fit the principle or not kind of a thing like that? That     
1:44:13     
was maybe a useful way to think about some of it. But um more so I wanted to jump in and say um what I'm have deep     
1:44:22     
longstanding and whatn not interest in     
1:44:27     
uh related to what Cub has been discussing is     
1:44:34     
um anything that kind of lends to highlighting because what you basically     
1:44:41     
doubling down a bit on what Bradley said about the difference between development and adulthood or how     
1:44:51     
uh I I mean I think one of the most especially on in a human sense and this     
1:44:58     
is part of mental health paradigms perspective that Joe pro is part of it's     
1:45:03     
it's inherent part of cognition futures but not not necess not cognition futures     
1:45:08     
is a bit more broad um than like specific applications of like We're not     
1:45:15     
talking about the DSM there very much, which is like the manual for, you know, mental health evaluations and whatnot.     
1:45:21     
Um, and where I'm going with this is like I am very interested in things that     
1:45:29     
try to look at and demarcate well the ways that     
1:45:38     
different stages of development are let's say nonuniform in their capacities     
1:45:46     
and like we kept talking about I asked oh what about developmental freedom developmental freedom Um, it's sort of     
1:45:52     
this concept we developed that addresses some of this or at least tries to offer     
1:45:57     
a a lens of the trade-offs between where     
1:46:02     
the progression in someone's developmental process and certain     
1:46:08     
certain things are more flexible, certain things are less flexible. um you know and and and kind kind of like uh     
1:46:15     
kind of like the idea of um you know when when when a small when a a     
1:46:22     
small animal or a mouse is one of the things I did in an old neuroscience lab a long time ago like what when     
1:46:30     
the reason that a baby mouse or for example cannot     
1:46:37     
entrain itself and develop a circadian in rhythm in the way that an adult mouse     
1:46:42     
can is because the the hard little of the hardware isn't there yet. Like the hardware has to mature over a couple     
1:46:50     
days so that there can be something that seems like a broader circadian rhythm taking hold in the whole body. Right? So     
1:46:57     
it's like there's these different components of when things come online and what kind of regulatory systems     
1:47:03     
actually begin operating at what level and so on and so forth and what's before after those states, right? what sort of     
1:47:10     
the sun setting of those states, right? And I guess like I'm very interested in     
1:47:19     
things that help to demarcate what those things what those states or you know if     
1:47:25     
Avery was here um macro not just all kinds but but the alostatic the     
1:47:31     
alistatic points of these systems as as the different regulatory components come in and out of operation across     
1:47:38     
developmental periods. And then yes in the Bradley sense of difference between maturation and and development and     
1:47:47     
adulthood um as as a particular like you know a lot of the things that we talk about all the time we use language of oh     
1:47:55     
in in in in precise biological language like oh in the adults in the adult human     
1:48:01     
being or the in the adult field mice or in the adult you know insert organism     
1:48:08     
but in in in many spaces in in a lot of common especially human side of things.     
1:48:13     
We don't we don't always have much uh     
1:48:20     
a lot of our models and perspectives are are quite short-handed to very long-standing issues that all     
1:48:28     
people and brain everything you know everything's everything is referenced is referred to of a very particular model     
1:48:34     
of what a person's experience is. So things that bring nuance to what that is     
1:48:39     
and and yes I'll go I'll go I don't like going here in a critical or critical theory or ethics component but yes the     
1:48:47     
many models are basically built off of the middle-aged white man as as the the     
1:48:54     
point of reference for many many models or health or normativity or standards.     
1:49:00     
So that's like one one branch of it. But even beyond that like sociological component just bringing the nuance into     
1:49:09     
the developmental states I think is something that uh I'm very interested in at large. So I'm glad that you were     
1:49:15     
putting this together. Like I I don't know what next steps you have in mind. Kabia u Bradley's pointed out some     
1:49:20     
things there. There's there's a fairly rich history in the lab of stuff that you can point out or that we can point     
1:49:26     
to. Um, and I'm definitely excited to see where you go with this. I think,     
1:49:32     
um, I kind of wish Ashley was here cuz I know Ashley was talking about this and I don't think she was at the last meeting     
1:49:38     
either. Um, so I wonder if she will be interested in that as well. And they might might have some other folks from     
1:49:44     
across the lab or um in Jerro that are um     
1:49:52     
there may be more interest here than it seems because you're the only person bringing up in the meeting right now,     
1:49:57     
but I would say like you could find a     
1:50:02     
uh you could find some folks that are interested in this if you want to continue to develop it out. And not saying they have to work with you or be     
1:50:09     
teammates or or whatever, but people who are willing to talk to you about this. Um they are they are here even if     
1:50:15     
they're not in this meeting right now. So that's my two cents.     
1:50:21     
Yeah, thank you Kavia. That was very good. We'll keep working on this and working through it. Let me know like     
1:50:27     
what your thoughts are like offline about this. Um yeah, I think it's     
1:50:33     
definitely like, you know, there's something there we can focus on and maybe there's more than one thing to     
1:50:38     
focus on, but um I think probably like I said there's a there's a there's a     
1:50:45     
kernel that we can start with and just focusing it down to like some     
1:50:51     
implementation. Yeah. Yeah. So uh just uh one thing I wanted     
1:50:58     
to ask. So uh should I just start with this first area like uh like you     
1:51:04     
mentioned that uh development maturation and referencing that out and just     
1:51:11     
starting with some implementation of it. Yeah. Yeah. So get a get a good idea conceptually of how that what you want     
1:51:18     
how you want to approach that and then you can implement it in Python if you want just a demo and then we can review     
1:51:25     
the demo and see how it works see what the performance looks like and then refine it because you can't really start     
1:51:32     
unless you have a good base. Yes. Yes.     
1:51:38     
All right. Yeah. Thank you. Thank you so much. Yeah.     
1:51:44     
So, I'm going to present on a P. This is, of course, we had this discussion earlier. Jesse     
1:51:51     
uh brought up uh some of the things about uh cognitive science and and and     
1:51:57     
some of the discussions we've had in the cognitive science reading group. This is     
1:52:02     
a um a a a paper um I think it's from a book,     
1:52:11     
not quite sure. This is the challenge of cognitive science and um it kind of     
1:52:17     
talks about cognitive science as an interdisciplinary endeavor. The contrast between psychology and neuroscience and     
1:52:25     
then the challenge of cognitive science. So we've read a number of papers in which cognitive science is defined     
1:52:34     
and then the history of cognitive science is defined as sort of the quest towards that definition. Um, one of the     
1:52:41     
problems of cognitive science is because it uses so many different tools and techniques. It stretches over so many     
1:52:47     
discip input disciplines is that it's hard to really kind of get it uh get a     
1:52:54     
good sort of distilled sense of what cognitive science is. So, it's an area of inquiry, but there's so much going on     
1:53:01     
that's so diverse that it's hard to can it if you were to boil it down to a couple of important studies, you know,     
1:53:09     
how are those studies connected? It's very hard to see the sort of the pattern     
1:53:14     
there. Um and then furthermore like we've said over time there's been this     
1:53:21     
sort of evolution in cognitive science from like you know uh basic decision     
1:53:27     
making to uh you know psychopysics to uh AI and     
1:53:34     
large language models and things like that. So there is this space of cognitive science but how much is any     
1:53:41     
one approach uh providing in any given time. So um of course we start with the     
1:53:48     
hexagonal diagram and this was something that came from a 1978 report on the     
1:53:54     
state-of-the-art and cognitive science that was commissioned by the Sloan Foundation. So that's where we reference     
1:54:00     
this cognitive science hexagon and it's just a shape that describes sort of the     
1:54:06     
space in between six input disciplines     
1:54:11     
and you'll see different disciplines actually if you look up the cognitive     
1:54:17     
science pyramid on um you know if you Google it or something and you look up     
1:54:22     
the different references they sometimes have different names for the disciplines     
1:54:28     
that are contributing which is you know it's kind of slippery in that sense. So     
1:54:33     
it's it's kind of hard to define this triangle or this hexagon or even any triangle within the hexagon     
1:54:40     
um properly because if you're not using the precise terms     
1:54:45     
then it's the different field. So uh we have philosophy which is a huge     
1:54:50     
territory of things. Um I think largely in it the philosophy that's contributing     
1:54:57     
to cognitive science is largely philosophy of mind although there are other parts of philosophy that can     
1:55:03     
contribute as well. There's linguistics. So our focus on large language models     
1:55:08     
isn't just kind of without precedent. you know people there have always been linguists in the cognitive science     
1:55:15     
enterprise and this LLMs are the latest imple or in um sort of version of that     
1:55:22     
there's anthropology which you know in in some ways contributes to cognitive     
1:55:27     
science a lot of the like cognition in the wild work and a lot of the situated     
1:55:32     
cognition work is based in at least in part in anthropology     
1:55:37     
um there's also you know human thinking about human evolution and the evolution of cognition as well.     
1:55:45     
There's neuroscience of course again these are all very large fields. So you know some parts contribute and you know     
1:55:52     
it but it's I guess the spirit of the field that's really what they're when they came up with this hexagon is what     
1:56:00     
they were thinking. So there's neuroscience which of course is you know     
1:56:06     
um where we're thinking about neural circuits but and comparative cognition     
1:56:12     
but also sort of these broader questions of function. Then there's artificial intelligence.     
1:56:18     
Sometimes you'll see computer science as this this point in the hexagon. um     
1:56:25     
artificial intelligence being the classical symbol of manipulation, artificial intelligence. Um but I think     
1:56:33     
that still kind of fits in there as a area. And uh then psychology, cognitive     
1:56:39     
psychology, which a lot of times people will conflate cognitive psychology with     
1:56:45     
cog uh cognitive science. And of course they're not the same thing.     
1:56:50     
Now within this hexagon, you have these triangles. So you have like a triangle between psychology, linguistics and     
1:56:56     
anthropology or psychology, linguistics and neuroscience, artificial intelligence, philosophy and     
1:57:03     
anthropology. So you can recombine these in different ways depending on the question you're asking.     
1:57:10     
So this is very interdicciplinary field. Um, and it's when they came up with the     
1:57:18     
hexagon, they describe cognitive science as an amalgamation of all these fields.     
1:57:23     
And I don't really think the amalgamation aspect is quite correct. It's more like maybe it's inspired by     
1:57:30     
different fields. So depending on the question you're a asking, you're maybe     
1:57:36     
drawing from those different fields, knowledge and tools and things like that. So that's kind of where I think     
1:57:42     
we're um kind of you know going with respect to cognitive science. Now you     
1:57:49     
can imagine that when you have so many influences that sometimes the field is incoherent     
1:57:54     
and that led to papers like whatever happened to cognitive science we've talked about a lot um and just kind of     
1:58:02     
people wondering what the state of the field is. So uh this is just kind of     
1:58:08     
thinking about this um in different you know in this way. Um     
1:58:13     
some of the connections identified in the the uh cognitive science hexagons     
1:58:18     
were judged stronger than others. So this we have dotted lines and solid     
1:58:25     
lines. The solid lines are the more solid connections. The dotted lines are the more ephemeral connections. But     
1:58:32     
nevertheless, you know, these are all connections to be made. So it kind of, you know, gives     
1:58:38     
you an idea of where the where the bulk of the work is and where maybe lesser     
1:58:44     
work is happening. Um, this is kind of an interesting     
1:58:49     
point. Um, you know, some of the connections that were judged weak in     
1:58:54     
1978 has now become a thriving subdiscipline in its own right. Some philosophers impressed by the potential     
1:59:01     
for fruitful dialogue between philosophy and neuroscience have taken to calling themselves     
1:59:07     
neurosophers. So this there Patricia Church's work in 1986     
1:59:13     
and has moved forward and a lot of the stuff that people have done on uh the     
1:59:18     
philosophy of mind. So there's been a lot of work on     
1:59:24     
um well what was the book that uh it's reality     
1:59:31     
plus that was a philosophical take on virtual reality     
1:59:38     
and sort of a lot of the cognitive science issues in that I think is that the one that Hussein did     
1:59:44     
a review of a long time. Yeah Hussein did a review on this like by Chalmer's I think or something. Yeah. Yeah.     
1:59:50     
So it you know again this is if you have a cognitive science talk series you will     
1:59:57     
get talks like that and then you'll get talks on uh you know using fMRI for human     
2:00:06     
categorization and then you might get a talk on comparative cognition between humans and     
2:00:13     
you know like other mammals or other animals.     
2:00:19     
and you know so it's a very diverse area and the idea is that you should be able to extract sort of the commonalities     
2:00:26     
between all these approaches. Um and so okay this is a nice anecdotal     
2:00:33     
story uh Miller's account of how the Sloan report was written is both disarming and telling committee met once     
2:00:41     
in Kansas City. It quickly became apparent that everyone knew his own field and has heard a two or three     
2:00:48     
interesting findings in other fields. After hours of discussion, experts in discipline X were unwilling to make any     
2:00:55     
judgments about discipline Y and so forth. In the end, they did what they were competent to do. Each summarized     
2:01:02     
his or her own field and the editors of the volume uh patched together a report.     
2:01:10     
This may be how reports get written, but it's not a very good model for an interdisciplinary enterprise such as     
2:01:16     
cognitive science. So what he's saying is that they came up with this hexagon quite simply by asking people, what is     
2:01:23     
your field? How do you think that they connect? And then kind of putting that all together. Um I I would have thought     
2:01:31     
it maybe would have been validated by a literature uh you know mining exercise, but     
2:01:38     
apparently not. So, it's it's kind of funny how much like     
2:01:44     
this is like the major thesis of like a lot of the stuff like why am I making     
2:01:49     
I'm I'm sorry to to just tangent this so much but like what's motivating me so     
2:01:55     
much in many of the things that I'm doing right now is is like that's thank you for the paper Bradley or the book     
2:02:01     
Patrick because this is exactly in the service of like     
2:02:08     
uh so many things that are the way they are right now are kind of exist in the     
2:02:16     
context of um like like I I'm I'm going to very I'm     
2:02:22     
going to very briefly share this but like this this this this is a broader     
2:02:29     
concept of this is 20th century dreams or whatever and this is a bit of a     
2:02:34     
social commentary on it but the same's true for um like the DSM like how these     
2:02:43     
things like all these things why I'm doing what I'm calling like person studies or agentic studies or I'm trying     
2:02:49     
to come up with a new term for this cross whatever you know cross cross um     
2:02:56     
domain looking at some aspects of cog science what we call cognitive science cognition phenomenology whatnot is like     
2:03:02     
where does it come from well a lot of the or like the bedrock foundations on demar ations of things are literally     
2:03:08     
just well, hey, here's like an arrangement of some     
2:03:13     
stuff that that's how what when we first made it, we put we put the structural logic of     
2:03:21     
the thing together in this particular configuration and we just built on it because it's something to do. And I I     
2:03:27     
don't begrudge it as as this is like my it's a very common soap box for me. I     
2:03:33     
don't begrudge that it happened. That's like when you're building something, when you're building new ground, just     
2:03:39     
like we said about the Van Gelder paper earlier, I said the sympathy of Van Gelder making a somewhat contrived     
2:03:46     
argument that he knew would be corrected upon later. Like that's a great thing to     
2:03:52     
do and a difficult thing to do, especially when you know you could be perfect. You have to start somewhere. So     
2:03:57     
immense sympathy for that. Like I don't I'm not even I'm not trying to shame oh how stupid the people were who made     
2:04:04     
color decides. So you have to start there. But the thing is like I feel like we're in this era right now     
2:04:11     
where it's so vital that we really     
2:04:18     
investigate the configur like the the original     
2:04:23     
structural configuration of the field and everything else versus     
2:04:29     
not having to behold into the legacy configuration forever. And I think there's so much tension there and and     
2:04:36     
there's new things emerging, but it's also like, you know, where's the path dependency of it all     
2:04:43     
taking place? So, we can go back to this, but like I I appreciate you bringing it up and I've had my little uh     
2:04:50     
my tantrum about it, but I I I think articulating these a lot of the work I'm     
2:04:55     
trying to do in the future center in many ways um is articulate ways of     
2:05:01     
looking philosophy, history of science, meta science, sure where these domains developed and why they did or didn't go     
2:05:07     
in a direction. I know we have that in co futures. I know it's a major part of reimagining cybernetics or     
2:05:13     
reconstructing cybernetics as sort of our in-house Orel initiative, but     
2:05:19     
there's just so much there and and I I think this will be a good uh another     
2:05:26     
another um tally on that board.     
2:05:31     
Yeah. So in light of what you're saying then the next part of this paper is in fact     
2:05:38     
the hexagon as a whole is not a very good model for cognitive science. So     
2:05:44     
this is kind of the the take-home here is that you know we have this model that everyone cites and then they wonder what     
2:05:50     
happened to cognitive science but in fact it maybe isn't a descript good descriptive model after all. Um, even if     
2:05:57     
we take seriously the m lines that mark connections between the disciplines of cognitive science, the hexagon gives no     
2:06:04     
sense of unified intellectual enterprise. It gives no sense that is of something     
2:06:10     
that is more of a composite of traditional disciplines such as philosophy and psychology.     
2:06:16     
There are many different schools of philosophy, many different specializations within psychology, but     
2:06:22     
there are certain things that bind together philosophers as a group. and psychologists as a group irrespective of     
2:06:29     
their school and specialization. Um, and so one of the main claims of     
2:06:35     
this textbook is that cognitive science is indeed a unified enterprise and it has its own distinctive problems,     
2:06:42     
techniques and explanatory frameworks. Um and so what we need isn't necessarily     
2:06:48     
a hexagon but to figure out what's going in inside this hexagon irrespective of the different contributing fields. So     
2:06:56     
there are a lot of contributing fact like fields in cognitive science. I     
2:07:01     
mean, if you think about like the earliest artificial intelligence research, you had people who were     
2:07:08     
interested in psychology but also interested in computer science, which actually at the time wasn't really a     
2:07:15     
unified field. It was just like a department at a university that grew out of the math department where they did     
2:07:22     
things on computers and they were developing sort of their own methodologies. you'd use those then to     
2:07:29     
move to some, you know, work in trying to program machines that burned     
2:07:37     
like you might see in a in a psychology experiment. Um there's a story about how     
2:07:44     
um so there was a um a department at the     
2:07:50     
University of Michigan uh that was founded by John Holland and it was the     
2:07:55     
precursor to the modern complexity um uh program at U of M. And there's a     
2:08:03     
story about how John Holland had was kind of in this space. He was like     
2:08:10     
interested in psychology, interested in computer science and wanted to bring them together into a program that people     
2:08:16     
could, you know, learn how to do things. And it was kind of like an adaptive     
2:08:22     
computing adaptive behavior type idea, but it was very fluid. And so it had     
2:08:28     
influences and it would have eventually its own questions but it was like you know how do we sort of set this apart     
2:08:35     
from all the other things going on at the university and that's true of a lot of department or a lot of uh things that     
2:08:42     
are kind of emerging and how programs form and how they have to justify themselves within the university. As     
2:08:48     
Jesse said, there's this inertial aspect where you have to report to institutions     
2:08:55     
want to keep doing things a certain way, but also want to see kind of how things     
2:09:01     
fit into their prior framework for doing things. And so this is kind of     
2:09:08     
uh you know the kind of the problem with cognitive science, right? Um what is defining cognitive science? Um and so     
2:09:17     
this is where they kind of get into some of the things about cog that make cognitive science unique. There's of     
2:09:24     
course the levels of explanation. So uh the levels of explanation in     
2:09:30     
cognitive science are different than neuroscience but actually different than psychology as well because most     
2:09:37     
cognitive scientists will place the study of the brain firmly at the heart of cognitive science but it's not at the     
2:09:45     
level of neuroscience. Cognitive scientists by and large don't care about say molecular mechanisms in     
2:09:52     
the brain. They don't think in terms of circuits so much. They do think in terms of what     
2:09:57     
happens in the brain then linking that to the cog sort of these cognitive mechanisms or behaviors whereas     
2:10:05     
psychology doesn't necessarily think about mechanisms although depending on     
2:10:11     
where you are in psych in a psychology department you think about that more or less. So, you know, again, part of this     
2:10:20     
is in that cognitive science has its own unique take on, you know, what you're     
2:10:27     
investigating. But then again, you know, you go to a psychology department and     
2:10:32     
you can find someone who's very much aligned with the cognitive science program and not really be a cognitive     
2:10:39     
scientist or more of a cognitive psychologist. So it's very much uh that's one of the problems is that it's     
2:10:46     
very much like it's so broad that it's kind of bringing in things that sometimes do belong to other fields     
2:10:53     
or that are concurrent with other fields. So this just shows the levels of     
2:10:58     
explanation where you have you know people are interested in what happens     
2:11:04     
from neurons to pathways to cognition.     
2:11:10     
Uh and then this is a nice This is um I think I've shown this figure before.     
2:11:16     
This shows different modes of investigation for     
2:11:21     
the temporal length of some phenomena of the brain versus the size of its     
2:11:28     
phenomena. So like if you're looking at a syninnapse versus the whole brain,     
2:11:33     
that's a difference in terms of size in millimeters. Or if you're looking at something that happens in a millisecond     
2:11:39     
versus a day, there's this difference in time in terms of seconds. And all these     
2:11:46     
this is just a list of these different methods that are used to measure those     
2:11:52     
time scales and those length scales. So like patch clamp is something you use on a neuron to measure electrical activity     
2:12:00     
and that happens at a certain time scale. that's very different from say like lesion studies or fMRI and then you     
2:12:09     
could make this kind of graph in fact for a lot of things um not just for     
2:12:14     
methods for measuring activity but also for behaviors and I think we have in one     
2:12:20     
of our papers a map where we have like a time a time scale     
2:12:26     
for different aspects of cognition. Yeah, that's what I was thinking of when I saw this and I was I was I couldn't remember     
2:12:32     
which one it was. So I was also going to say like definitely if you can put this paper in in this     
2:12:40     
chapter in in a slack I would I I definitely want to because this is a nice introduction for a lot of like some     
2:12:46     
other folks that are kind of coming into some of the cognition future stuff like this like this is it's a nice like I'm     
2:12:53     
glad we're getting like the method like this is sort of the methodology of the you know cognition futures method     
2:12:58     
project stuff. So yeah. Yeah. And then of course you know there's this challenge of cognitive     
2:13:05     
science. Um there the three dimensions of variation.     
2:13:11     
Um so one dimension of variation is illustrated by the sub fields of neuroscience.     
2:13:16     
Neuroscience studies the brain at many different levels. And in neuroscience they adopt the vertical     
2:13:23     
uh hierarchy of biology. So you go from neurons to brains to societies and you     
2:13:31     
can look at all those things in neuroscience. Um and of course you have so that's something that cognitive science kind of     
2:13:38     
adopts to some extent. Um then the second dimension of variation comes from     
2:13:44     
the different techniques and tools which we saw in that figure that are used at different time and length scales. And of     
2:13:53     
course the third dimension of variation is exemplified by the different sub fields of psychology.     
2:14:00     
So we might want to go out and explore, map and describe and explain the     
2:14:05     
cognitive abilities making it possible the myriad things that human beings do and say. So you know you have in     
2:14:13     
psychology you have different sub fields like developmental clinical     
2:14:18     
um cognitive um psychiatry you know all these different areas of psychology and people     
2:14:26     
are just interested in largely in the same thing. They're just interested in different ways of looking at it. So     
2:14:33     
that's and then that of course is something all all things that we can adopt into cognitive science. And then     
2:14:40     
they have this figure here which is the space of cognitive science. This graph is not as informative as I would have     
2:14:46     
liked it to be but basically it kind of shows these different modes of inquiry     
2:14:52     
vision memory language problem solving and then these other things that are not     
2:14:58     
specified and then uh that's so that's the x- axis the y ais is are the     
2:15:05     
different methods for getting at these things. So like fMRI, behavioral data     
2:15:11     
and some uh neurohysiological recordings down here. And then of course you have     
2:15:17     
the levels of organization, molecules, synapses, neurons, networks,     
2:15:24     
the central nervous system on the Z-axis. So it's this three-dimensional plot um investigative technique, levels     
2:15:31     
of organization in domains of cognition. And then the idea is you could plot out     
2:15:37     
your study or your area of interest as a space or as a dot in this space and that     
2:15:45     
that defines your interest in cognitive science I guess. So it's just kind of     
2:15:50     
breaking ourselves out of that um hexagon and thinking in different ways about how to define cognitive science.     
2:15:58     
This is good stuff. Um, and then this is just is the preface to a book and this     
2:16:03     
goes through and I I think this stops here at the prehistory of cognitive     
2:16:09     
science which is another story for another day. It so what was the is it a history of     
2:16:16     
landmarks? What was what what was like that was one of the title     
2:16:21     
uh history of landmarks like scroll up. It was like that historical. So this is just where     
2:16:26     
they're going to go through the history of cognitive science. Okay. Then there's this prehistory which is     
2:16:32     
like going back to behaviorism and psychology and the reaction against that     
2:16:39     
and then the rise of computationalism. And so those two things kind of came together     
2:16:46     
and that's like it's so interesting one of like it's very interesting to see     
2:16:55     
what part of the rant and also hi Erin glad you're here with us     
2:17:02     
um said some comments about black holes and whatnot and in the chat     
2:17:08     
um part of my um continuous ranting about all of this stuff is is it's so     
2:17:16     
interesting now and I I feel like     
2:17:25     
I know I know I've kind of happened into a space where I regularly am in contact     
2:17:31     
with clinical social workers, clinical psychologists, people that are wielding     
2:17:36     
kind of the fruits of what we're supposed to be examining in the implied sense people purely in a theoretical     
2:17:42     
sense philosophers and and I I I guess I feel like     
2:17:49     
it's a little bit bizarre to me that I don't I don't think I should be such an     
2:17:55     
out like I know that many people are interdisiplinary and do things in in multi-disiplinary     
2:18:01     
ways. I'm not I'm not special about that. But it it sort of     
2:18:09     
is is a bit baffling to me on many fronts that there's not really a little     
2:18:15     
more concerted effort even even even I would even say     
2:18:22     
at a like a popular phrasing now is like epistemic honesty or like ontological     
2:18:30     
uh an epist ep epistemological humilities about things like yeah Yeah,     
2:18:35     
but I just I don't I think I think     
2:18:41     
um there's there's so much integrative work to be done, let's say. Um and and I'm     
2:18:48     
just going to kind of gesture towards what all that what all that means and everything else I've been ranting on about to kind of come back to to what we     
2:18:54     
were saying. Yes. Um I I this is a nice introduction like very textbook uh and     
2:19:01     
getting at things in a nice way. Um, so we can look at that and something to bring about into, you know, cogn     
2:19:09     
cognition futures and some of the new folks in the program. Last thing I'll say about this, and I don't know how much time more time we have, oh, not     
2:19:14     
much, I'm sure. Um, I think I forget if you brought this up, Bradley, or this is something that's come from     
2:19:22     
some of the other things, but just how uh there's a conversation a few weeks     
2:19:27     
ago, it might have been one that I initiated or not, um, on sort of cognitive science 1.0, Oh, the hex     
2:19:34     
hexagon and also the sort of at the time the bracketing of we're really going to     
2:19:40     
center computation. we're really going to center um     
2:19:45     
computational modeling the idea of computation computation it's hexagonal but I feel like the real the real the     
2:19:51     
real there should be something in the middle that's not there in hexagonal classic cognitive science which is like     
2:19:57     
computation like like it is computation was supposed to be uh not necessarily     
2:20:03     
the golden ring of it all but but the one ring of it all but like it was     
2:20:08     
supposed to be you was supposed to be the chosen one. like you were supposed to be this thing that was going to um     
2:20:18     
you know do all this do all this stuff and and not that it did or didn't in a particular way but just     
2:20:24     
it kind of it kind of became a you know a gesturing to or a reference point and     
2:20:30     
then the two two quick things I want to say is it was really informative one time when I went to ironically in in     
2:20:38     
when I was considering doing a PhD in cognitive science science. I went to the     
2:20:43     
UC San Diego which is the first I think one of the first ever like very large     
2:20:50     
broad interdisiplinary cognitive science programs as as a as as a institution     
2:20:56     
like like they they they made it very much on purpose at the time which and and I think the university itself was     
2:21:02     
you know 1960 or so. So it was kind of in the right moment for a lot of these     
2:21:07     
things. Fantastic people there doing fantastic things. Um, but it was so     
2:21:12     
interesting to go to this open house and to see the cognitive science people or     
2:21:18     
like the the the I think it was it might have been a psychology open house and not a     
2:21:24     
cognitive science open house. I forget which. Uh, but just seeing the cognitive scientist and their mechanistic approach     
2:21:30     
and then social or uh uh developmental and like oh like oh it it was very it     
2:21:37     
was very interesting and informed at that level to see it at the time. And then the last thing I'll say is uh     
2:21:44     
the bracketing component I'm going to kind of step back the bracketing component and and and uh computation     
2:21:51     
relative to the 1943 paper and that step ladder that step that that diagram of     
2:21:58     
trying to taxonomy diagram of breaking down the things and how there's sort of a a movement towards okay well we're     
2:22:06     
going to use computation to kind of you So we're going to center it here and use     
2:22:12     
computation to explore these human domains of it. And a lot of I think Leven's work and work that we're might     
2:22:17     
be concerned about interested in is sort of maybe bringing it back out again where we're looking at not uh where     
2:22:24     
things are a bit more level and trying to do the original aim of the 43 paper which was     
2:22:30     
principles that would apply across substrates or embodiment natural     
2:22:35     
artificial. Um, so I think that sort of points to where we can go with some of the things, but I'll leave it at that.     
2:22:41     
We're way over time. Um, I don't know if you want to look on anything there or     
2:22:47     
Erin's comments, but I know we have to go. Welcome, Erin. Did some pretty good uh     
2:22:53     
made some pretty good comments in the chat. So, you brought up a paper on neuroplasticity     
2:22:58     
and uh Yeah. And then, uh, yeah. Yeah. Erin says, "I don't think our     
2:23:05     
visual representation for modeling this should be a static polygon anyways." Yeah, it's well, it's like that's that     
2:23:11     
was kind of the way that they conceptualized it. Of course, we mentioned that it wasn't really a very     
2:23:18     
good model. Um, and this is uh neuroplasticity     
2:23:23     
century old idea championed by Adolf Meer and Susan Lamb. And then Jess said     
2:23:29     
Meyer in occupational therapy which was who Adolf Meyer was. Um and then uh     
2:23:37     
where is this? Oh yeah. Okay. Um and then uh a pioneer 21st century American     
2:23:45     
psychiatry. He was the psychiatrist and chief of John's Hopkins Hospital and is best known for developing psychobiology.     
2:23:53     
Yeah. yet another field and then that's just kind of like is that part of     
2:23:58     
cognitive science or psychology or what right and and like also like to be very     
2:24:04     
pmic for another moment I know occupational therapists and clinical psychologists and whatever and it's like     
2:24:11     
those like put them in the same room and talk about like I feel like I always     
2:24:17     
feel like I want like return of the Macy's conferences for these kind of things and it's like I don't know let     
2:24:22     
I'll leave it at Um but yes. Yeah. Yeah. The language, you know, a lot of times it's just adopting your own     
2:24:28     
language. That's the distinction. And it could work better if people use common     
2:24:33     
language like we talked about with the random beer paper. Exactly. I was going to mention like the     
2:24:40     
like languages as lenses and letting it be. It's okay to have the language, but     
2:24:46     
you also need to, you know, do translations at times. Um     
2:24:53     
I'll I'll I'll I'll follow up to to Kavia at at the end, but if you can go     
2:24:58     
through I think we're pretty much done, but yeah. Yeah. And then Erin had here I     
2:25:03     
Googled visual representation of accretion and then black holes and then yeah, black holes and rotating black     
2:25:10     
holes please uh please me a bit better as a working model and then yeah about     
2:25:16     
appent horizons and yeah and then yeah so that's that's good. And then uh Cavia     
2:25:23     
had this comment. I just wanted to say that as Jesse mentioned earlier, some people might be interested. I'd be happy     
2:25:29     
to connect and learn. So yeah, Cavia definitely if you found something Kavia was presenting uninteresting, you know,     
2:25:36     
jump into that conversation and give your feedback on his document.     
2:25:41     
So what? Yeah. And to do that in 30 seconds, we'll try to clip this     
2:25:47     
presentation and we can make a little like paragraph or card like some kind of a here's what I'm looking at and and we     
2:25:55     
can talk about it here and in the Slack and in Jar Pro as well. I'm I'm creating sort of a a project development task     
2:26:01     
board or like join up and help out call for involvement type things. So yeah, we can make something there and and     
2:26:08     
there's people in that group and in this group that are looking for that to do. So we'll follow up in Slack about that.     
2:26:15     
Um but yeah, this is a good broad meeting today and thanks for taking the     
2:26:21     
extra time to go through the stuff, Bradley. I'm sure you did that with my rants in mind. So thank you.     
2:26:27     
Yeah. All right. All right. Thank you. Have a good week, everybody.     
2:26:33     
Take care. Thank you.
