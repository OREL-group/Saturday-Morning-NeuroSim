## Meeting Recording

[YouTube link](https://youtu.be/en_iESzPxjo)

## Mastodon thread

[link](---)

## Feature Videos

[Jesse Parent and Further Observations of Ai in Education](https://youtu.be/7a6l4WzWYSo)

[A Discussion About the Promises and Pitfalls of AI in Education](https://youtu.be/u_GG7GNhoJI)

[Sakana AI Petri Dish NCA Demo](https://youtu.be/1a-Nd9N7zS0)

## NOTES
Small group of people working on Open Textbooks.

* Ryan Smith's step-by-step tutorial. Non-MATLAB alternative.

* code examples --> Alexander Shaw.


Variational methods, animal behavior, RL, robotic methods.


Josh Bongard's robotics class. Center for Brains, Minds, and Machines (BMM -- MIT).

* steganographic -- digital watermarking (how many authors wrote x?). 

* "Marked Pedagogies" --> limits of LLMs and inherent biases.

* AI in Education fellowship.

* similar to the Princeton Panel (K-12, scalable).


AI for teaching progressions (not certain outcomes). Weilding the proportion.

* knowledge generation, other issues. 

* types of class, management of demos, how people use tech.


What happens when you have an LLM grade the work of another LLM?

* what happens when you have an LLM grade the work of another LLM?

* "The appearance of a solution".


Heavily processed signal -- why is the mad lib is being assembled the way it is?

* what is generative text? LLM fingerprinting -- self-supervised LMs (remove humans).

* HAI group, Morgan is working with the group.

* AI in education and cognitive development. How much does the model share by responding? 
Passing information in plain sight --> or anonymous sources?

* Allostatic Kinds --> Chiral Personalities (Avery's new work).


HAI group, Morgan is working with the group.

* LLM fingerprinting -- self-supervised LMs. Remove humans from the loop.


Focus on Foundation Models --> MetArc --> structural MRI.

* developmental trajectories, delays. accelenated aging. 

* CogSci reading group. Building for Sentience (not a thing). A lot of examples just brought up and 
left to wither. Was the whole book a ruse?


Computational Memory Lab: Princeton --> foundation models. 

* CogNeuro experiments --> ActInf tectbook group. Software development. Connect to tutorials.

* how useful is educatyional code? Different styles of learning. 

* continuing with agentive coding. No pre-existing examples. Talk about AI, reconize that 
animals have sentience.

## TRANSCRIPT	      
0:00     
Hello. Good morning. Morning.     
0:06     
Hello, Cavia. Okay, let's start. Um,     
0:13     
so hopefully everyone had a good week. Uh, I'm going to start with     
0:21     
our de going over our devil war meeting. And I think this coming Friday, I'm     
0:27     
going to try to target for the first open source meeting of the year. So this     
0:32     
will be May 1st at 12:00 p.m. Eastern time in North     
0:38     
America. So that whatever time that is for you. And so we're going to try to,     
0:44     
you know, I think by then we'll have our selections for Google Summer of Code.     
0:49     
We'll have some other things going. So hopefully we'll be able to do a meeting this week.     
0:55     
We'll see. And so if you're interested in presenting, you can present. If     
1:01     
you're interested in attending, uh please look in our Slack for more     
1:06     
information about the link. It's usually at this link. So you have the link.     
1:12     
Okay. So let's start with uh talking about the D. We're meeting. And so we started off     
1:20     
uh with Baron and he was presenting on his project. Uh this is taking what is     
1:26     
called the epic data set. It's a data set in C elegance uh development. It's a cell tracking     
1:33     
data set and he's pre-processing the data so that it can fit into this SGEL pipeline.     
1:42     
So he basically wants to create graph tensors for embryos and then feed that     
1:48     
into a graph neural network. And so this is the pipeline here where     
1:54     
you have the raw data in a CSV file. You have this data processing step which     
2:01     
extracts features generates a mask constructs edges     
2:08     
and then you have the data plus the mask and the edges and that's your output and     
2:15     
then you pass the process data to this SJL graph neural network training step     
2:21     
that's where you train the model and then optimize the weights. he was showing some examples of this. Uh     
2:28     
he was talking about how we want to be able to create spatiotemporal graph tensors. Um and why would you want to do     
2:35     
that? Uh so basically we have time varying cell features and labels. So     
2:44     
from the labels we can infer directed edges to the graph     
2:49     
and the time varying cell features means that it needs to be a temporal graph. It     
2:54     
also has spatial properties that the labels tell you exactly where the cell     
2:59     
is in the embryo. And so you can actually trace the     
3:05     
uh movement of the cell relative to other cells through that nomenclature.     
3:12     
And so we have a number of columns here. We have a tensor fixed tensor shape per     
3:18     
embryo. And then we have a dynamic graph stored sparsely as edges over time. So the     
3:25     
edges change over time and then we can model that as a series of time points.     
3:33     
Um and then of course there's an NPZ file which is uh uh produced which is     
3:40     
the feature tensor uh where n is the number of cells, five is the number of     
3:45     
features and t is the number of time steps. Um, and there's some other     
3:51     
properties here. Uh, he shows some code.     
3:57     
He goes through this. Uh, this is his blog post on this. Actually, he's been     
4:02     
maintaining a blog on some of the work he's been doing. Um, and he actually     
4:08     
process put, you know, used the epic data set as input already and tested     
4:14     
this out. So he's kind of stepping through how the code is written and how     
4:19     
that all works. Okay. So that's that was that part of the meeting.     
4:26     
Then uh Ashu gave a presentation on some uh data sets that she's contributed to     
4:32     
DVORM. So we uh actually have uh a number of secondary data sets for     
4:40     
developmental biology and those are hosted in various GitHub repositories     
4:46     
and other places in the openworm foundation. So or or the D.VARMM group. So     
4:53     
uh the openworm foundation has its own set of data and the D.VARM Evilm group has data that's specialized for     
5:01     
uh developmental data. So for C elegance we have quite a few data sets. The EPIC data set is a     
5:09     
classic cell tracking data set. We have other data sets that we've pre-processed     
5:14     
for uh gene expression for cell biology     
5:20     
and then for other organisms like drosophila and uh zebra fish and even and uh even     
5:29     
single cell organisms like datoms. So this is all kind of available and what     
5:36     
um Ashu was able to do is create a pre-processed data set where she's     
5:42     
looking at what she calls is anastmosis. Actually this is something we've been talking about in the group which is     
5:48     
where you have graph structures where the nodes exchange     
5:55     
uh their membership between one cluster or one community and another. So you can     
6:02     
plot out graphs these are dynamic graphs you can plot out and you can examine how as cells are as     
6:09     
you can imagine as cells are being born and they're migrating they belong to different groups maybe different     
6:15     
communities and they switch membership eventually or occasionally sometimes     
6:21     
that's because they change their identity from like a stem cell to a     
6:27     
neuron or sometimes they die or they divide. And so all those things have to     
6:34     
be sort of accounted for in one of these developmental graph neural networks. And so she worked out this method for     
6:41     
characterizing the anastmoses in these embryographs.     
6:48     
So these these data sets will be hosted in our GitHub repository. If you're     
6:53     
interested, let me know. And then uh Utkar uh presented on his     
7:01     
work um he's been playing around with the C302 platform which models uh     
7:07     
neurohysiology and C elegance and then uh playing around with the Cindy     
7:13     
platform or the Cindy G which is where there's a it's Cindy is a uh bioysics     
7:20     
platform and then Cindy G is like the graph version of that And so he's trying     
7:27     
to see what models the data the best. So he tried this combination of C302 and     
7:33     
Cindy. And basically he found that because it's not specialized for     
7:39     
development. It's not a very good model at least out of the box or initially.     
7:47     
So you have the wrong physics a lot of the time. So if you're modeling something in development, the physics     
7:53     
aren't necessarily the same as what you find in the adult, you have this saturation problem where     
8:01     
um there are no contrasts that are developmentally interesting. In other words, you know, if things are already     
8:07     
mature, all the changes in development have already occurred. So we can't like look at those changes     
8:14     
and the model is not sensitive to them. And then failure three is the cross-sectional design where you have uh     
8:22     
and this from this he drew from the whipfleet data set where they have eight different samples from across laral     
8:28     
development in C elegance and it tracks the changes in synaptic connectivity     
8:35     
across the connecttoone and so if you don't have that sort of incorporated     
8:40     
into your model then it doesn't pick up on those developmental changes.     
8:46     
So he he he tried that and it didn't work out. So then he uh switched to this     
8:53     
model that takes molecular causes into account. So he actually switched data     
8:59     
sets. He he started using this packer data set from 2019. It's an interesting     
9:04     
data set that does a lot of g has a lot of gene lineage resolve gene expression     
9:09     
data in it. So it basically allows you to model the conneto     
9:15     
according to changes or sensitive to changes that are happening in development.     
9:21     
So this is a nice data set to work with. And then he's using this molecular NDP     
9:27     
model which is where he's going to transforming those data into something     
9:32     
that's amendable to um machine learning. And then you know this molecular model     
9:41     
of course can predict things like wiring patterns and um exploring this hyperraph which is     
9:49     
already in the data. You just need to recover the hyperraph and then this temporal uh developmental     
9:58     
GNN uh which he calls a GCRN. And this is something that um is you     
10:05     
know he set this up and then showed some results from that     
10:11     
and then validated some some of this as well. So it's a pretty good some pretty good     
10:17     
work by Kar. Then I presented on some papers I     
10:23     
presented on two papers to end the meeting. The first was uh this paper marovian dynamics for C elegance     
10:30     
behavior across scales and Baron reminded me that I he had presented on     
10:35     
this in January but I presented on this again because it fits into the second paper I was going to talk about and this     
10:43     
paper basically is where uh the authors build a model for looking     
10:48     
at u movement in sea elegance phenotypes. So, you know, worms move     
10:54     
around their environment, and we'd like to know some of those modes of behavior, and we'd like to take that behavior and     
11:00     
link it to things going on in the conneto. Uh what kinds of activity     
11:06     
patterns occur on the conneto when we see certain behaviors as outputs. Now,     
11:12     
see, elegance has a lot of stereotype behaviors, but they also have a lot of specialized behaviors that we don't     
11:17     
really understand. So we can use um you know videos of sea     
11:25     
elegance and we can characterize those videos through uh machine or computer     
11:30     
vision um as you know some sort of igen     
11:35     
worm or some sort of high or some sort of um highdimensional space where we can     
11:43     
characterize different behaviors. And so they actually use a marov model here     
11:49     
to model the transitions between behavioral states. So you model you     
11:54     
characterize the states using these iigen worms. You then uh take those ien     
12:00     
worms and you sort of figure out how they fit together into sort of these     
12:06     
longer behavioral sequences. So the worm can move back and forth and we     
12:11     
understand how that's generated through the neural circuits. we can characterize that sort of stereotype behavior through     
12:18     
the iigen worms. Uh and then we have this method for kind of treating those     
12:25     
as discrete states that are connected probabilistic through through this markoff chain. So that's kind of what     
12:32     
they're doing in this paper. And so they're they're successful in in reconstructing these behaviors.     
12:38     
And then uh they go on to we go on to this paper which is a stochastic     
12:44     
neuronal model that predicts random search behaviors at multiple spatial scale and C elegance. So they're     
12:50     
actually looking at they're using a neuronal model to predict search behaviors which are sort of the longer     
12:56     
term behaviors that you see in the last paper. So they're building this marov model. They're using that to um predict     
13:04     
these longer term behaviors, these sort of behaviors we don't really understand.     
13:09     
And it turns out a lot of those are involved in foraging behaviors. So this is what they're doing here. They're     
13:15     
looking at foraging behaviors in sea elegance. But they actually     
13:20     
interestingly enough they use a different mathematical model for this. They use a mathematical model of random     
13:27     
search. And in the last paper they're using a Markoff model which typically is     
13:32     
memoringless which means it doesn't have a memory for past states. It just gives the probabilities of the next behavioral     
13:41     
transition or state transition. In this case, they have a memory and um     
13:48     
they're able to kind of predict these different aspects of the circuit in the     
13:54     
in the conneto and then these different aspects of behavior. So they're able to model this as     
14:01     
um uh in a way that that uncovers these circuits that do what they say a     
14:08     
neuronal flip-flop which is where there's reciprocal inhibition between two populations of stochastic neurons.     
14:16     
And so they're able to um kind of get interesting results that take a     
14:22     
different method from the last paper but kind of get you to the same place.     
14:28     
And so that was the end of the meeting pretty much. All right. So that was the D.VAR meeting. Um     
14:34     
and so this week I'd like to begin the uh open source meetings for this year.     
14:40     
Um we'll also have another DVAR meeting in Monday. So hopefully people can make that.     
14:48     
It looks like uh looks like V and Jesse have joined us.     
14:55     
So, uh, people want to give updated. Okay.     
15:03     
People want to give updates.     
15:09     
Hey, I don't know how noisy it's going to be where I am, but I can speak or just write a little bit.     
15:16     
How is the I'm in a cafe.     
15:23     
Yeah. Yeah, that's fine. Um, really quickly just just to like     
15:30     
bullet point some things we'll see today. Um,     
15:36     
it's been a really interesting week and time. Um,     
15:43     
on the mentoring front, I'm mentoring a team that's about to do like a semifinal     
15:49     
pitch in the UC launch startup program and they're doing well. I I just dug out     
15:56     
if you guys remember last year about this time I did stuff with MIT Venture Studio     
16:02     
and I had since then kind of buried that article and such that I was this big breakdown about a year ago and I just     
16:09     
pulled it out again to show them that wow that was actually it was a terrible article like I basically just pasted a     
16:16     
transcript on subset an unedited transcript basically which you shouldn't do um     
16:24     
But the content, the wisdom there is totally good and applicable. Um, so I     
16:32     
was looking at that again and trying to advise them what to do to get their pitch right. I have quite a lot of     
16:37     
experience now like what that kind of pitching is about. So anybody talk about that? I'm trying to encourage to um     
16:46     
people in German community here. If you're doing that, please ask ask us     
16:54     
asking any anyone in my world really it's it very own article like     
17:02     
it's a completely different animal of talking about things that I     
17:08     
know we'll cover some of these things during the open source um     
17:13     
I'll let you look at I think um     
17:19     
we'll cover similar stuff in like the demo or die stuff or beyond demo or die.     
17:24     
How do you how do you communicate stuff? What audience like those are very key things to do. Um but     
17:33     
I'm just I'm just fresh off the launch team and it's going it's going     
17:38     
well. It's so interesting depending on where you are in your development your team what what better things to do. Um     
17:48     
and then uh the other thing to joke about doing is it's the kind of time of year especially here on the east coast     
17:54     
where all like the the departments have their symposiums. So     
18:00     
you know there's like the ethical ethical computing in Oz the AA group is     
18:06     
having there's some O they made invitation only in chosen and I'm a     
18:12     
little bit invited to so that for me but they have a free online uh version and I     
18:21     
think it be pretty good. I'm looking forward to it. Last year it was in person but they had center for     
18:27     
technology. is going to be a little bit small this year, but they're doing a lot. One of the things they're trying to     
18:32     
do in Jro is basically one of the things this year I want I'm     
18:38     
building an instructor to make people doing     
18:44     
interesting society work.     
18:50     
They need a little bit better community infrastructure. So, I'm realizing that that's something that I'm going to be     
18:56     
investing in. Um, I'm also hoping to get a charity     
19:02     
sponsored in some form in the next few months     
19:08     
and a lot of digest work and a lot of like     
19:13     
interest a few people I'm talking to next week     
19:19     
about that. But like digest indigenous has been a really interesting I don't     
19:24     
know almost like reading group style um situation where     
19:33     
anthropic personal stuff very finally kind of along the way that I've     
19:40     
wanted to kind of take it just made publicity so I'm very happy for for that     
19:47     
but now it's like entering the summer season open source cohort um potentially a data     
19:56     
direction intern that's that's basically like what's     
20:02     
going on from that front of the battleground the intellectual     
20:08     
frontier that we're at here um and com any of those things I I I have we've     
20:16     
been digest in particular has been meeting since like December And we have I have I was about to post a full     
20:25     
like I don't really they're not really episodes but for the sake of the podcast culture I have like episode 12 they're     
20:33     
meeting basically weekly and so I have like episode 12 on YouTube and I have a really good episode um     
20:43     
it's a discussion series so it's more like a session um but like I have all this stuff that's about to be posted.     
20:51     
So, that's part of what I'm trying to do is get it get it out. Um, and I don't     
20:57     
really think we've had a lot of thinking about that here. Also, um, shout out to Arma who um     
21:06     
kind of about to final write up and we'll talk about that next week. I don't know if     
21:12     
they'll be able to join us here, but AR is the person to work on. I'm not afraid anymore.     
21:18     
Uh somebody that would didn't read uh like ESG reports, ethical sustainability     
21:26     
or environmental sustainability guidelines. Um and like analyze that kind of a basic     
21:33     
analytical way. Um so it was a good like intro project for them as a very uh as a     
21:40     
new person in in the space. Um so congratulations for that.     
21:46     
Congratulations to the EC launch team and     
21:52     
there's so much stuff going on that's getting really loud here. I apologize. Um, but there's so much stuff going on     
21:58     
that I uh I'm very excited for what's ahead and I'm happy to talk about     
22:06     
want to have kind of a any particular goals you want to hit with the summer cohort summer crew um     
22:14     
the Friday meeting or anything like that. So, um I'm going to try to weave it through that. Uh but yeah, look     
22:22     
forward to that. I'll broad if you want to talk about that     
22:27     
later. I'll be in later. All right, sounds good. Thanks for the     
22:33     
update. Um yeah, uh sounds like some good things going on. Um so did anyone else want to     
22:41     
give an update or? Uh sure actually I could not attend the last two uh meetings like last two     
22:48     
weekends because I was at an hackathon. So I participated in two hackathons like     
22:54     
finally built a system where uh we streamlined the processes of parallegal     
23:01     
like for the parallegal audience. So like they have to go through the people     
23:08     
whether they can get a real or not for sure reduction applications they have to uh drive you know create files     
23:15     
or applications for them. Uh align the dates for your so that was what we did     
23:21     
in the first hack. Uh however we could not actually win it. Uh in the second     
23:27     
one uh we uh link the supply chain problem like uh usually we uh there is     
23:36     
data of adjustment codes but we don't have any application that links the tier one tier 2 suppliers like the end     
23:43     
supplier to the current people. So we created a graph based system for that     
23:49     
and added uh a simulation like what if a supplier gets disrupted. So what is its     
23:55     
blast radius or what would happen how would we overcome and what are its alternatives.     
24:01     
So we came second runner up in that. Yeah. And for the G-Soft part, I was actually     
24:10     
looking at the stack data sets and uh you know playing with uh three     
24:16     
approaches like uh what are the topics that people were discussing in the Sack community. So I applied three     
24:24     
approaches. The first one was simple LM based one like giving the data set on LM     
24:29     
and inferring from it. Second was a hybrid approach from LNM plus DB scan or     
24:39     
bird topic and third one was simple topic and applying LM to just refine the     
24:45     
labels. So I have created a PDF     
24:50     
and comparing them. So I observed that the hybrid approach was much better because     
24:57     
LLM was giving a bit more accurate answers but it could not form clusters. So every chat it identified as unique     
25:06     
and gave unique names. So we can't actually do that because we need to form clusters. So I found the hybrid approach     
25:14     
much better which was a bit accurate and more accurate and even it formed     
25:19     
clusters. the bird topic was not accurate at finding topics. So yeah,     
25:24     
that was something I did. Very interesting. That sounds good. Um, so you     
25:33     
basically uh the Slack data set is that something that you were able to get like     
25:38     
online or is that something you generated? Yes. Uh there's a data set called     
25:44     
charter data set which is public. I had also shared this in the previous meeting     
25:51     
like where we were discussing about the Zox approaches. So it's uh there is this     
25:57     
data set called as strategy data set which contains slack conversation of three different     
26:03     
communities that is the closure M and Python dev. So yeah from that data set I was looking     
26:11     
because that was publicly available on GitHub and few research papers have also used     
26:17     
that as a primary uh role like even for and     
26:23     
moreover it's disentangled. So that's where we could     
26:28     
save some time. Okay. And then your uh approaches were     
26:35     
or the best approach you found was like combining a large language model with a clustering model basically.     
26:41     
Yes. Yes. Uh so basically first I give the uh conversations to an     
26:48     
LLM to generalize then applied the clustering algorithm so that they can form clusters.     
26:54     
So that was something I did because uh simple could not you know accurately     
27:00     
form did not form good clusters whereas the simple clustering one did not give     
27:06     
accurate interpretation of them. Okay. So I found the hybrid approach much     
27:12     
better. Good. That sounds great. Thank you. Thank you. Cavia.     
27:19     
Uh anyone else about Morgan? Yeah, there he is.     
27:24     
So what were the big things this week? um another open scope meeting     
27:32     
um which is good in terms of you know I I think I     
27:38     
mentioned this last week the the new data release um     
27:43     
I I haven't gotten there yet but you know this is kind of connected to     
27:52     
what what we can do to get students     
27:58     
um working with neuropixels data and     
28:04     
you know this is this is an open science project of the Allen Institute     
28:11     
which has uh I mean it's it's it's both a rolling release you you can you know     
28:19     
participate in these meetings um they're 9:00 am Tuesday morning Pacific time.     
28:27     
Um, you know, the the benefit here being that they are actually in the West     
28:34     
Coast, so their their morning starts at 9. Um,     
28:41     
and yeah, it's a um     
28:49     
it's a great it's a great place to, you know, follow a you know, large     
28:56     
scientific collaboration high level or you know like like people working     
29:03     
with kind of you know state-of-the-art instruments and things things like that right um     
29:10     
which then kind of leads into the um the TMS EEG so sorry the the     
29:21     
biggest thing this week is the um the spring school that's been going on and     
29:28     
um that's the GTech spring what do they     
29:34     
call it BCI and neurotechnology school I think     
29:40     
so that that's actually been sorry I should have led with that because it's been going on since um Sunday my time     
29:49     
it's been going on since Sunday at midnight um because It's It started 9:00 a.m.     
29:57     
Vienna time. Um, and     
30:03     
this is has been just chock full of of incredible speakers. Um, I was going to     
30:10     
say that Wednesday was was some TMSG presentations, which which it was,     
30:18     
excuse me, both in the um both in a regular kind of TMS meeting as well as     
30:23     
the spring school. And uh there's just some really nice     
30:29     
been thinking a lot about EG and you know     
30:36     
is does consumer EG is consumer EG still a you know even a thing? Um and and why     
30:45     
why we like TMS EG? Um but uh     
30:54     
I could can say more about that. Um if if anyone's interested the uh then what     
31:03     
I was actually working on most of the week was to get ready for uh Thursday's meetings     
31:11     
which are with um our med which again are open     
31:18     
science meetings um and focused on um     
31:24     
focused on foundation models for both I mean well     
31:31     
the the new thing with Medarkc is actually a foundation model for structural MRI     
31:36     
um and they they started a new project around brain age prediction which was is     
31:44     
which is you know of of interest in psychiatry because so much um of what     
31:51     
we're trying to characterize is either is sometimes     
31:57     
um is sometimes described as as developmental     
32:02     
delays or developmental trajectory changes uh differences and or um in     
32:11     
older adults whether it's seen as as uh accelerated aging.     
32:18     
Um because again like the big thing that we we always point out is that     
32:25     
um people who have these disorders are     
32:30     
going to die 7 to 10 years younger than they should. Right? So, not only do you     
32:36     
have to explain the the um the differences in development, but you     
32:45     
also need to explain the um the lifespan changes um differences. And     
32:55     
so, that that was interesting. I mean it's is again it's it's one of these     
33:00     
it's one of these open science efforts that I think is really interesting in     
33:06     
this case because it's it's a I mean it     
33:12     
is being run by a company this company has you know strong     
33:19     
academic roots but more importantly for the learning opportunity     
33:26     
Is it that it has strong what I would call um ML     
33:35     
uh ML you know experience and and     
33:42     
um is is embedded very very high level in the you know ICLR     
33:50     
uh ICML nurips kinds of of meetings.     
33:58     
And so it's just it's great to kind of be able to follow along in terms of how     
34:05     
they approach um like software development. Um     
34:11     
you know, tools and infrastructure that they use for sharing and comparing models and and you know, their use of     
34:19     
models, their use of libraries. And in this case, they're doing it all with with, you know, focused on medical     
34:27     
imaging. So, um, they're potentially using libraries and     
34:34     
packages that I'm familiar with. So, that's been that's been really interesting, too.     
34:41     
Um, the um     
34:48     
Yeah. So, so that that that's been interesting even though it's it's it's     
34:54     
uh I I kind of rushed a couple days worth of of GPU processing and um all I     
35:03     
was able to do was just show that they were kind of using probably using the     
35:09     
best approach. Uh um and then then then the afternoon     
35:16     
it's a meeting with the real time fMRI team um or the real time I think they call it     
35:23     
the real time mind team and which is     
35:29     
is kind of a group at the computational memory lab at Princeton that's that's     
35:37     
the you know it's the one kind of applications group. I mean, they still have a paper,     
35:43     
the ICLR and stuff, but um it's the one     
35:48     
group where it's like they're really more interested in how they can use such a trained     
35:55     
let's call it foundation model um to actually do cognitive neuroscience experiments.     
36:03     
So, that's that's interesting too. And um uh yeah, so that was um that was mo     
36:14     
most of oh yeah the the other relevant thing is that the um fundamentals of     
36:22     
active inference textbook group um met for the first time. I think it was     
36:28     
Tuesday. Um and and then we had our like     
36:35     
cohort meeting on Thursday. Um so yeah     
36:42     
it's it's I I would like to also say that's going to be some software     
36:48     
development in terms of just you know how do we how do we connect this to the     
36:54     
kinds of um um     
36:59     
the kinds of tutorial packages like spinning up in AL     
37:05     
that um that we had that we've we'll talk about a little bit. Um so it was     
37:12     
interesting to see what you know backgrounds people are coming from and um things like that how useful they've     
37:20     
found working with codes for that kind of educational work. And um uh     
37:30     
I think that's um I think that's everything to say about     
37:35     
that. And yeah, so as as usual, a lot of     
37:41     
updates on my GitHub um with you know, continuing continuing a     
37:48     
lot of agentic coding, continuing a lot of physics work. Again, it's been     
37:54     
interesting to see um how Claude is responding when I'm     
38:00     
butdding up against, you know, working working with teams that are already do,     
38:06     
you know, already using tools. um as well as you know like we're     
38:14     
um working on challenge problems that that groups have set     
38:21     
where you know these are these are really open open science problems and so     
38:26     
there's no kind of pre-existing work that you can point the tools to     
38:31     
all that's the updates I would say for this     
38:52     
Yeah, that's great. Um, thank you, Morgan. That's great work. uh just I'm     
39:00     
interested in kind of the textbooker because I saw them on YouTube     
39:05     
and uh yeah yeah yeah it's a good question as to like what how     
39:11     
valuable is like uh a lot of the coding a lot of the coding exercises with a     
39:17     
textbook. So like usually you know traditionally you have like problem sets     
39:23     
and things like that. Yeah, we'll see the So the book um is     
39:29     
supposed to come with code. Yeah. Um but it's not ready yet. Yeah.     
39:35     
So so we we we we don't have that. Um at     
39:40     
the Tuesday meeting, you know, there was definitely a subset of us. I forget I     
39:47     
forget. Um, you know, I'm assuming that Daniel     
39:52     
writes a lot of these kind of questionnaires, but but from the     
39:58     
institute, you know, they they're asking questions about like what you     
40:04     
kind of like what style learner you are, you know, and     
40:10     
the I'm not sure I'm going to remember. There's definitely like the     
40:15     
comprehensive or something like the the theoretical and then     
40:22     
um let's see the practical. Um but you know I I certainly and there seem to be     
40:29     
a subset of us who were like yeah it would just be really great to to see     
40:34     
code to see what you're doing with these matrices     
40:39     
and and be able to kind of follow along. Um, so but I think it's one of those     
40:46     
things where it's like is it better that you write it or is it better, you know,     
40:53     
like like how much can someone kind of do that for you? Um     
41:01     
but uh yeah looking looking forward to this you know I mean it's it's not my f     
41:07     
you know I've done I've done the the PAR textbook     
41:12     
right with Active Inference Institute. Um I've done it in our COGSAI reading     
41:18     
group. Oh I should say we also had a COGSAI reading group meeting this week. Yeah. Um, and we did the we did the edge     
41:28     
of sentience. Oh, right. That book. Yeah.     
41:33     
What did you think about that book?     
41:40     
Um, who was it that     
41:45     
I think it was? Um, Anil Seth, right?     
41:51     
I saw a talk he gave and and I was like, "Oh, I see I'm in an El Seth's camp.     
42:01     
I I This is not not the camp I thought I would be in." Yeah. Um but, you know, he he was making I I     
42:10     
was trying to find the right term for it in um     
42:16     
u you know, for those held the position that talking     
42:23     
about AI sentience is is um is just a you know complete     
42:33     
not misnomer but like it's just it's just not you know it's     
42:40     
just not what you're what you're building right you're not you're not building something for sentience right you're building     
42:46     
something for similacra you And um     
42:54     
yeah, so it's like but I did I did try, you know, I I I made the case for why I     
43:03     
tried to read the book in good faith,     
43:08     
you know, because I was just like he he he definitely had organoid examples,     
43:15     
right? you know, but like he would bring them up like, you know,     
43:22     
he would just bring them up. It'd be like an organoid could be, you know, I     
43:28     
think it was like, you know, an an organoid learned to play pong.     
43:34     
And, you know, it could be it could be sin that that we've created, you know,     
43:40     
consciousness in the dish with no perception and no no embodiment. I'm like, wait, that that's all you're     
43:46     
gonna, you know, you're just gonna raise that as an if and then like then draw     
43:56     
conclusions from that like Yeah, I know.     
44:02     
Uh, so I I I I put out the theory that this was actually a     
44:10     
a ruse, that this whole book was actually a ruse. Um,     
44:16     
it was it was to talk about, you know, something a topic     
44:23     
that is very um is very hot right now, right? to talk     
44:28     
about, you know, AI, right? And and this kind of this this new sci-fi world we live in, but that the     
44:37     
the actual point of the book was just to realize that like animals definitely have sentience,     
44:43     
right? And that they should be treated better. Yeah.     
44:49     
You know, which is not a bad, you know, which is not to say is is a bad thing to do.     
44:58     
Yeah. Um, and and     
45:04     
yeah, anyway, I I I I wanted to give it a fair     
45:13     
um, you know, I think anybody who's doing animal research should should have, you     
45:21     
know, deeply thought about the the the issues     
45:27     
and the problems and um, and certainly not to to dismiss it     
45:36     
but um it was not my choice of book     
45:44     
any but I I I'll definitely I'll keep reporting on the the active inference um     
45:51     
textbook and you know like like we we tried to we also tried to cover the um     
45:57     
the par active inference book um you know in in     
46:03     
a not do it in one reading but like do it in a couple readings     
46:11     
um and you know I've never found it to be     
46:17     
a very good or you know I'm looking forward to this more mathematical     
46:23     
engineering treatment which is you know hopefully is is     
46:29     
slower, longer. Um, and we we really go through um     
46:39     
um you know, like like what I tried to do with the spinning up and     
46:49     
so this this new version is more mathematical     
46:55     
and engineering oriented basically. 100% like like very you know what what     
47:03     
what you see from the     
47:08     
um Yeah. Yeah. It's it's and it's a bit     
47:14     
more actual textbook, you know.     
47:20     
Yeah. I mean, the PAR book was was     
47:25     
I think more of an exposition. Um,     
47:32     
again, not a not a not a bad thing, but not it wasn't, you know, wasn't trying     
47:37     
to be that, right?     
47:42     
Yeah. Are they going to print going to have a print version of this book or is it just going to be virtual?     
47:49     
Um, think you can, you know, I think or     
47:54     
they they both apologized for the lack of like an affordable book.     
48:00     
Yeah. Which was which was generous. Um     
48:06     
uh I I did get the the Kindle     
48:11     
um which which you know I separately have have a problem with. Like I wish     
48:18     
there was non-Kindle alternative where at least I owned the digital copy.     
48:25     
Um, but the um,     
48:31     
uh, it is it is also a bit of a problem because they they live, you know, they     
48:38     
can't actually like read the text and have the text on     
48:44     
on Zoom because they record it and they put it on YouTube. So it's it's it's an     
48:51     
unfortunate license, you know, like obviously the the the author this is all driven by the     
48:59     
publisher, not the author, right? Right. And and     
49:04     
um again says says a lot about the state of our world.     
49:10     
Um, and yeah, so it's like like we can     
49:16     
show I think we can show like figures from it.     
49:21     
Um, but but we can't actually scroll through the text,     
49:27     
you know, like like Yeah. Yeah. Um,     
49:33     
uh, but I don't know if any, you know, like like I think there was a bigger     
49:38     
issue of whether Everybody actually had the book, right? You know, like like     
49:46     
Yeah. Yeah. And it would be nice to um     
49:54     
well anyway it it's again it's it's a weird thing when you think about you     
50:00     
know how to um     
50:05     
there's still only a very small group of of educators that work on like open     
50:11     
textbooks. Right. Right. and and it's it's a little like journals     
50:17     
where you know it's like a huge amount of education cost is     
50:24     
um you know not just in the United States but goes to the the publishers of     
50:31     
textbooks for classes. Um     
50:40     
it is it's a It's a big thing. So, it's um Yeah. So     
50:48     
hopefully though, yeah, like like there's this small group that definitely want to work on open source software,     
50:56     
you know, and and uh I didn't I I said how much I liked     
51:04     
Ryan Smith's tutorial, um you know, step-by-step tutorial, and Daniel     
51:10     
Freriedman said out loud what I what I didn't, which was     
51:15     
yes, it would be nice to have a nonsp SPM alternative. Yeah,     
51:21     
a non SPF mat lab alternative. So, um uh     
51:27     
yeah. So I I still think that's going to be where um where people will really get     
51:35     
um a better sense of you know like like     
51:41     
not just looking at the code but also code examples of the kinds um     
51:48     
uh Andrew Shaw I think is it Andrew Shaw uh     
51:56     
is it Alexander Shaw Alexander um Alexander Shaw thank you um     
52:04     
of the kind you know like like again this is this is what Alf tried to bring up right this is like like there's this     
52:12     
overlap of of you know like variational methods you know reinforcement learning     
52:19     
and kind of you know animal behavior kind of studies and robotics right?     
52:28     
Or what you might you know robotics autonomous systems, right? And and I     
52:34     
think um I think seeing you know like again like     
52:41     
trying to connect this in in some unified way like like Josh     
52:48     
Bongard does with his evolutionary robotics class is     
52:55     
is I think where you're going to see you know real     
53:00     
synthesis for for students, you know,     
53:05     
um but again I I you know     
53:14     
I I know there are definitely people who are like no I need you know like I'm     
53:19     
going to go through the math and I like I need to be able to to     
53:25     
demonstrate relationships and things like that to to to really get And um     
53:34     
we'll see. We'll report back.     
53:40     
Yeah. Yeah. I'm interested in kind of how they're approaching that. Um     
53:46     
it Yeah. Sorry. I just want to say one last thing which is that like I'm still     
53:52     
doing the AI and education fellowship and um     
53:59     
you know I was just kind of curious about your your thoughts. I mean it     
54:05     
seems like the team which again is is made up of of educators. Um     
54:12     
I'm I'm supposed to be the coder although this the the woman at ASU has     
54:19     
been doing a lot of coding now. Um     
54:25     
just in terms of you know how how important are um     
54:34     
at a big university like software tools for for professors to handle large     
54:41     
classes of students and um     
54:47     
you know, finding Yeah. like like um I I     
54:54     
would be interested in that that topic if if you wanted to say about some of     
55:00     
your experience and things things you've done as well as you know just what um     
55:06     
what what professors talk about. Yeah. Yeah. Find it useful in that regard.     
55:12     
Yeah. So I guess I have a couple of things to say about that. So you know a lot of times you're     
55:19     
teaching well there are two three types of classes you know of course the one where you have small classes where you     
55:27     
might do demos you might do things where you just need to have like code I've     
55:33     
done a lot of live coding where you need to have work examples worked out basically and so that's one thing that     
55:40     
you want to be able to have and it's you know it sounds kind of trivial but it's not because you have to come up with     
55:46     
good examples that are that teach people concepts, you know, and and be something     
55:53     
that's interesting. Um, then, you know, there's the second type which are the large lecture hall classes where you     
56:00     
have people coming in there. You know that you can't be very     
56:05     
personalized. You can do live coding, but like people may or may not follow     
56:10     
along and you basically have to manage a lot of people. So you have if you want to     
56:16     
have an assignment, you have to be able to manage those submissions and grade them. Um you just don't have time to     
56:24     
really kind of go through the submissions um you know on a personalized level. So     
56:30     
you need to have assignments that you can assign. People can basically     
56:35     
turn them in and you can grade them and you know you don't want to necessarily always give multiple choice. So there's     
56:42     
a challenge there. Can we create a system where people can do coding and     
56:48     
other kinds of exercises where they're turning in assignments, it gets graded, they get feedback and all that. And then     
56:56     
there's of course a third type of well there's a third example where and this     
57:01     
kind of crosses class types which is of course a learning management systems.     
57:06     
And so um you know we usually in at our university we use Canvas which is of     
57:12     
course manages the content and there's a lot of there are a lot of hooks in Canvas where you uh that are     
57:21     
not you know you have to like kind of do a couple of classes to get a good appreciation for everything you can do     
57:28     
there. Um, so it's like there's, you know, there's like an institutional management     
57:33     
of Canvas and then there's like Canvas as it exists as a platform and, you     
57:38     
know, you can figure out ways to customize it so you can do things you want to do in a class or in a classroom     
57:44     
setting, but it's it's not easy to kind of figure out how to do some of those things. So, it kind of limits you to     
57:50     
what you can do. There's also this issue of um you know     
57:56     
for one of the classes I' I've taught or I'm teaching this semester we have a an     
58:01     
additional um learning management system which was sort of homebrewed at our     
58:08     
university. This is a problem that sometimes you I don't know if it's a problem but it's like you have these     
58:14     
systems that are kind of you know customized for specific types of classes     
58:20     
and um you know you can do more things in them but it's harder to kind of     
58:26     
figure out how to do them in you know um so there's the pedagogical aspect there's a management aspect then yeah     
58:33     
and Jesse's kind of posting some things in chat about AI and how do you you know     
58:38     
how do you inor incorporate people using AI. So clearly people are using it for things. Sometimes, um, I've had people     
58:45     
using it to improve their English, like they'll write a an essay answer or     
58:51     
something and they'll kind of improve their answer by using AI. or sometimes     
58:56     
you'll have people who use it for um different you know things like writing     
59:02     
term papers or um you know looking up code which of course we we usually want     
59:07     
to have rules for that but there are no standards across the university and I don't even     
59:14     
really I mean the the standards thing is like where if you adopt a standard     
59:19     
that's great but sometimes you don't know how people's use of the techn technology     
59:25     
will unfold or what you may need to do. So like you know if you're in a like an     
59:30     
English class the standards would be vastly different than if you're in a coding class or if you're in like a     
59:37     
engineering class you know there are different things going on in those classes that make it hard to have a     
59:43     
unified set of standards and then of course the technology is evolving. So like how do people use it usual you know     
59:50     
in terms of supporting their work? Is it just that they're going there to get answers which is what people you know 20     
59:57     
years ago used to do with Wikipedia. I remember when like people would say, "Ah, don't just site Wikipedia." You     
1:00:04     
know, they they'd make a point when you're writing a term paper. Yeah. And it's like, okay. Yeah. Now it's like     
1:00:10     
Wikipedia is almost like a source of ground truth. And people are saying, well, don't use uh AI to to only use AI.     
1:00:17     
And you know, it's a very similar thing. And it's just interesting how we have these tools and how people how they kind     
1:00:25     
of enter the mainstream or enter the bloodstream as it were and get used and     
1:00:31     
and accepted. So it's it's there's a lot of stuff there that I think are     
1:00:37     
interesting topics to kind of follow up on. Um, and you know, kind of thinking     
1:00:42     
about how the needs are different based on different types of classes that are     
1:00:48     
being taught, different topics and that sort of thing. It's just, you know, I     
1:00:53     
think it's Yeah, it's a really good topic to kind of Yeah, I'd actually really enjoy when     
1:01:00     
when is is is your fellowship like for a particular term of time? Uh, Morgan, I     
1:01:06     
forget. Uh I I've uh like like we're     
1:01:12     
we're in the second half like uh I forget exactly but you know it's it's I     
1:01:19     
think end of May is it's finishing up you know and and just to your to your     
1:01:27     
point about LLMs like you know that that's that's definitely a big um     
1:01:34     
um Lulu.     
1:01:39     
Yeah, you're there. Oh, okay. Sorry. Um     
1:01:45     
there's there's just a couple couple topics um that that have come up. um     
1:01:53     
um to to your point about you know the limits of LLMs and um     
1:02:02     
kind of evaluations and you know bias and things like that. These are I'll just put in these two particular     
1:02:10     
two particular papers. Yeah. I I have like I would love to what     
1:02:15     
I asked at the end is like I would love to have specific conversations about this. This is sort of what we were     
1:02:22     
talking about I don't know at the at Princeton panel on education but it     
1:02:30     
wasn't at it wasn't at this particular level. It was most people there were     
1:02:35     
talking about it from basically K like K12 and and managing a a classroom     
1:02:43     
at that scale. So, I'd really like to have more conversations like     
1:02:49     
um it's for lack of better terms, not it's not really about graduate education, but at the level of knowledge     
1:02:56     
generation and development and research that we're looking at. Like I'd really like to have a different uh like almost     
1:03:04     
a structured discussion. It could be a discussion series or just I don't know a     
1:03:09     
time where we sit down and talk about this specifically. Um because Bradley raised so many so that's like point     
1:03:15     
number one but Bradley raised so many points about the type of class like     
1:03:21     
absolutely like managing stuff managing demos the Canva the the learning     
1:03:27     
management all that stuff um and it's like     
1:03:34     
excuse me um it's this element of     
1:03:39     
uh well let me look back at my comments missing so many different things. Um     
1:03:48     
there's a lot of there's a lot of like there's a lot of pressure to deal with certain AI usages, but also at like a at     
1:03:55     
a very high level. I think what what a lot of AI stuff is doing is exposing     
1:04:03     
these kind of weird op like weirdly optimized structures that a lot of educators have put it. And that's like a     
1:04:09     
whole like macro uh social discussion. But in     
1:04:16     
an implementational sense or in a notation sense, sorry, I'm navigating     
1:04:21     
the streets here. Um, in another sense, I I I'm very     
1:04:27     
interested in uh like there's this phenomenon     
1:04:32     
happening and perhaps you guys uh can can name this better than I'm currently saying it, but it's a bit like uh what's     
1:04:42     
the law about the proxies, the good arts goodarts law. Um, it's a bit like that,     
1:04:49     
but it's this sort of having AI evaluate     
1:04:54     
things that AI produced and it's like this slow pushing away of     
1:05:02     
like you're what what the AI is actually interfacing with an evaluation sense or interpreting the data or interpreting     
1:05:08     
the output. Like if you're having if you're having an LM or an AI grade     
1:05:14     
content that another LM prod like is a bit more generated by an LLM than a human being's thought like what do you     
1:05:21     
what what are you doing and not just in education or teacher but like in research in papers like this is this we     
1:05:28     
had a discussion last night where we're criticizing a um     
1:05:33     
sounds so haggard sorry we were criticizing     
1:05:38     
the idea that oh, we trained an agent to do to replicate our research and     
1:05:46     
uh it independently verified that we found this claim to be true and like     
1:05:53     
what is the are our agents now the arbiters of independence as well. Um so like all     
1:05:59     
these different angles of um what     
1:06:05     
this like this line this this this phenomenon I'm sure there's a term for it somewhere that that people are     
1:06:12     
writing about but like just the the way that AI is being used to     
1:06:18     
create a something that looks like the appearance of a solution and then also     
1:06:23     
another form of of technology is designed to create the appearance are designed to create that what is     
1:06:30     
being evaluated and like when interfaces would     
1:06:38     
the sort of the applied version of the device between like how easy it is for     
1:06:45     
digital bits and bites to be sort of thrown about. But like when you're actually interfacing with a person or     
1:06:52     
experience or biology or hardware or like physical limitations is the different the vast differences and sort     
1:06:59     
of what's being what kind of things are mixing with each other when stuff has happened. So I know     
1:07:05     
kind of zoomed out into a macro sense here but like just go back to basic things. Yeah. I I think this is a really     
1:07:11     
interesting pedagogical topic and I want to look at the paper that I say more about the paper you just looked in the     
1:07:17     
chat but I'm very interested in that space for sure. Yeah. So, one of one of the um one of     
1:07:27     
the engineers that's that's on our team is is in this     
1:07:34     
um AI and education, you know, is it's like an AI     
1:07:41     
uh education engineer in that she works for ASU and is is     
1:07:51     
absolutely Ely, you know, trying to to both     
1:07:57     
guide the um     
1:08:03     
somewhat produce tools for the educators, somewhat, you know,     
1:08:10     
make the tools deliver concrete recommendations and or, you     
1:08:18     
know, um metrics that the students can actually     
1:08:26     
improve with, you know, and um uh     
1:08:35     
now it's it's it's definitely it's an even harder problem when you     
1:08:42     
think about, you know, how much is is AI being     
1:08:47     
injected into these systems. as well. Um     
1:08:54     
uh and you know like like there is definitely a separate piece of     
1:09:01     
literature or a separate you know research thread on     
1:09:07     
uh you know interesting issues that come from AI being actual you know material     
1:09:16     
that these these models and tools are working on. Right? So, just a really interesting paper that came up recently     
1:09:24     
with some um how AI agents can actually pass     
1:09:33     
information, excuse me, that we don't see     
1:09:40     
that is actually in the in the data structure from from the previous agent.     
1:09:47     
So, It's kind of interesting that like yeah it's like another another um     
1:09:57     
another level in which it's it is important to really understand well um     
1:10:06     
what happens when you inject AI material into these systems.     
1:10:14     
But it's it's this is this is why I love the topic because um it is very much an     
1:10:22     
intersection of both kind of like what's the cognitive science of these models     
1:10:28     
as well as you know how how useful and and     
1:10:34     
um where I came from which was actually you     
1:10:40     
know studying cognitive development Right. Excuse me.     
1:10:46     
Yeah. So, yeah, I I I want to I'm ready to kind of, you know, I think we can move on to other     
1:10:53     
things u after this, but I'll just say kind of in closing to to this part. Um,     
1:11:01     
I don't know that I'll be able to articulate it very well, but     
1:11:06     
I something that's emerging in the digest discussion group is basically this.     
1:11:13     
It's sort of a not a double-edged sword, but there's two two prongs to the conversation. One of them is that I     
1:11:20     
don't know how much you guys remember Avery's various interesting theories about ales kinds and this like     
1:11:25     
intrapersonal stuff they they they they titled something recently     
1:11:31     
in a very academic sense like chairo chairo empathy or like like like uh     
1:11:37     
different weighted different weights in interpreting very phenomenological like regulatory things that may be happening     
1:11:44     
inside someone. Where I'm going with this is like we have one prong of discussion well many things but like in     
1:11:50     
this relevant to what we just discussed about indigenous and and other things in     
1:11:56     
sort of a illusion or or from our discussion lineage of     
1:12:01     
commission futures as well. We have this looking at     
1:12:06     
how can the the opportunity space of AI     
1:12:13     
effectively mapping or effectively interpreting being used to enhance the nuance and     
1:12:20     
articulation and understanding of you know you could say cognitive     
1:12:26     
development or learning or or how how an agent or how a human being is     
1:12:32     
progressing understanding and and the merits of that at the same time     
1:12:38     
kind of realizing these weird we I tried to describe it we tried to     
1:12:43     
describe it last night like a seal like the ceiling and the floor of what what what's being understood and how if you     
1:12:51     
take AI hold AI to a side for a moment and think what's sort of the ceiling and the floor of what we actually understand     
1:12:58     
in these spaces and kind of using AI to try peek around the corner or like move     
1:13:04     
the ceiling up or or like expand the space and it's like okay well we can we can kind of come to the edge and look     
1:13:10     
where AI is talking about these things and say okay is AI actually progressing     
1:13:16     
it or are we in a situation where we're kind of getting this using terms like oraorus where like the AI generated     
1:13:24     
stuff for the AI app is being evaluated by other AIS and then we have an     
1:13:29     
independent AI that's interpreting the AI generated material against the AI     
1:13:34     
evaluation and it's like okay like what are are what's being processed     
1:13:42     
is kind of heavily statistically normalized or average against the mean     
1:13:48     
or interpreted in certain ways that's like mechan like like heavily processed me mechanized     
1:13:55     
uh signal at this point it's like what are you you know so it's this     
1:14:00     
interesting interesting divide between trying to understand what is happening at the     
1:14:08     
gen generation and evaluation sense while at the same time realizing okay there's opportunities to dive deeper in     
1:14:16     
into what an Asian is actually doing and just like that that's sort of like the dilemma pro dilemma problem opportunity     
1:14:23     
space whatever you want to call it um so I don't know     
1:14:29     
uh look at my comments I think I One more thing then we can go. Um, but while     
1:14:34     
I'm looking for that, Bradley, what what do you want to talk about next? I know we've kind of been wandering here and I'm contributing to the wandering. So,     
1:14:41     
Oh, that's fine. What's on your mind? Um, I'm just going to basically go over that paper Morgan posted and I     
1:14:48     
want to go over some of the things you put in chat. So, Oh, okay. The one the one we were just     
1:14:54     
the marked pedagogies one. Yeah. Yeah. Okay. Yeah. Okay, then. Um, I'll just uh     
1:15:02     
I I will just briefly comment on what did I say here.     
1:15:07     
Um, it I'll just leave it at that. I'm happy to     
1:15:14     
have you talk about the paper. Anything else? I'm sure more to say in a moment. All right. Thank you.     
1:15:20     
All right. So, um, this is the paper that Morgan posted in the chat. This is     
1:15:25     
Mark Pedagogy's examining linguistic biases in personalized automated writing feedback.     
1:15:33     
So of course um being able to give feedback is good and you know if you have very large courses or if you have     
1:15:40     
like a lot of writing it's you know nice to have like personalized feedback.     
1:15:46     
um especially when students are in the process of writing and just helping     
1:15:51     
people you know kind of improve uh before they turn something in. Um you     
1:15:58     
know a lot of times you you know people come to say college and     
1:16:04     
they don't get a lot of writing experience in high school and then you go through this     
1:16:10     
whole period and it's not my problem but like in uh like the writing courses and     
1:16:16     
you know a lot of the undergraduate English courses they have to deal with this where they have to really kind of     
1:16:23     
teach the mechanics of writing and that can be kind of burdensome. Um, and sometimes people don't have enough     
1:16:30     
experience with writing to do any kind of good writing and that's always a problem. Um,     
1:16:38     
so this is where you have these uh kind of automated writing systems giving     
1:16:44     
feedback. I mean even when we use something like Microsoft Word, you know, you get prompts to improve your sentence     
1:16:52     
structure, improve your spelling, etc., etc. So those things are feedback that     
1:16:57     
you're getting and you're acting upon. Um and that's for people with very high levels of writing experience. So you     
1:17:06     
know that's that's kind of what we're trying to do. And uh you know using say like a language model to do that is     
1:17:12     
fine. But then they're pointing out that there there are a lot of problems we have to think about when with these     
1:17:18     
systems. So effective personalized feedback is critical to a student's literacy development.     
1:17:25     
Uh the large language model powered tools now promise to automate such feedback at scale. Large language models     
1:17:32     
are not language neutral. They privilege standard academic English and reproduce     
1:17:38     
social stereotypes raising concerns about how personalization shapes the feedback students receive. So     
1:17:45     
it sort of forces them into a certain box of writing style. And that's of course, you know, that's if you're     
1:17:52     
trying to teach people how to write for college, that's okay. But if you know,     
1:17:57     
you're trying to um teach them how to write for life, I guess it's not okay.     
1:18:03     
And certainly, we don't want to reinforce social stereotypes on people,     
1:18:08     
negative ones. And so this is a problem that we might have um     
1:18:13     
with with a lot of these tools. So they looked at four widely used large     
1:18:18     
language models. Uh GPT40, GPT3.5 Turbo, Llama 3.370 billion, and     
1:18:27     
then Llama 3.18 billion. Uh adapt written feedback in response to student     
1:18:32     
attributes. Using 600 eighth grade persuasive essays from the persuade data set, we generated     
1:18:39     
feedback under prompt conditions embedding gender, race, ethnicity, learning needs, achievement, and     
1:18:46     
motivation. Um, we analyze lexical shifts across     
1:18:51     
model outputs by adapting the marked words framework. Our results reveal     
1:18:56     
system systematic stereotyped aligned shifts and feedback conditioned um     
1:19:03     
unpresumed student attributes even when essay content was identical.     
1:19:09     
Feedback for students marked by race, language, or disability often exhibited positive feedback bias     
1:19:16     
and feedback withholding bias. overuse of praise, less substantive     
1:19:21     
critique, and assumptions of limitability. Across attributes, models tailored not     
1:19:27     
only what content was emphasized, but also how writing was judged and how students were addressed. We term these     
1:19:34     
instructional orientations mark pedagogies and highlight the need for transparency and accountability and     
1:19:42     
automated feedback tools. So, this is the paper. Let's see if we can dig a     
1:19:47     
little bit into the paper. Um so     
1:19:52     
one of the things here is that there's this personalization in feedback.     
1:19:57     
So feedback is not about error correction necessarily. It's about you     
1:20:03     
know kind of guiding the the writer to a place where they can you know produce     
1:20:08     
better writing. And to do so of course a feedback system has to take in a lot of     
1:20:14     
information. It has to give encouragement. It's not just about saying something is right or wrong. It's     
1:20:20     
about suggesting alternatives and understanding what the writer is trying to say, which is basically the idea     
1:20:26     
here. And what a lot of the systems that we have are doing is they're kind of     
1:20:32     
guiding the uh writer in a direction that the language model wants and not     
1:20:37     
necessarily that the writer wants. So, it's kind of muting their voices if they're not sort of these median     
1:20:43     
mainstream voices basically. Um research on personalization has identified a     
1:20:50     
range of learner characteristics used to adapt feedback and instruction including     
1:20:55     
prior knowledge, achievement, motivation, values, cognitive capacities     
1:21:01     
and gender. Um however the linguistic choices and instructionable goals that     
1:21:07     
characterize these adaptations and ultimately their efficacy remain underexplored particularly in the domain     
1:21:14     
of writing instruction. So we want to have these personalized systems and it's very hard to do if we     
1:21:22     
don't customize them as well because of course people are diverse and they have diverse ends to writing and and we can't     
1:21:29     
just say you know something is right or wrong because how writing works. Um,     
1:21:36     
so basically and you know again like if you're doing something like a multiplechoice exam or you're giving     
1:21:43     
multiple choice questions, you can give that kind of feedback where you know you say something is right or wrong and you     
1:21:49     
can maybe even explain why something is right or wrong. But we want to in writing it's a lot more open-ended.     
1:21:56     
So you're going to be dealing with you you're trying to communicate an idea. There are a lot of ways you can     
1:22:02     
communicate an idea and giving feedback on these kind of this in this     
1:22:08     
possibility space is is actually quite hard and you know exam you know uh     
1:22:15     
instructors will often have this problem too where they kind of you know read     
1:22:20     
someone's writing and they make assumptions about the writer and they make assumptions about what they're     
1:22:25     
trying to say and it's not you know it's a struggle to try to give feedback even for a human     
1:22:32     
um where you're trying to guide people to what they want to say versus maybe what you think they should be saying     
1:22:38     
and that's that's just you know kind of a fact of a fact of our world. So     
1:22:46     
so a lot of educational technologies have tried to use adaptive systems of     
1:22:52     
personalized feedback by tailoring responses of student traits.     
1:22:57     
The the types of data these systems draw upon vary widely, but typically include needs-based descriptors such as current     
1:23:04     
knowledge state, learning behavior data, and progress measures. Systems may     
1:23:09     
additionally incorporate identity based information such as gender pronouns,     
1:23:15     
language background, and cultural factors and sociological factors or     
1:23:20     
socio psychological factors such as motivation. With the growth of digital     
1:23:25     
infrastructure, industries have gained access to comprehensive databases linking academic records with     
1:23:31     
demographic attributes, enabling the construction of detailed learner profiles. So they use these learner     
1:23:38     
profiles to provide feedback. And again, you know, that's okay if you're trying     
1:23:43     
if if people conform to the sort of the stereotype of their demographics, right?     
1:23:50     
But if you don't, then that's a problem and you end up in the same kind of situation.     
1:23:57     
Researchers have documented decades of brewing enthusiasm for such data-driven personalization.     
1:24:03     
Um, such uses of student data raise long-standing concerns about privacy and bias that are amplified by the     
1:24:09     
integration of large language models. So, they go on about large language model biases.     
1:24:16     
Um, and basically the larger language models will pick up on certain markers     
1:24:22     
of the writer and then use that to sort of give these this sort of stereotypical response.     
1:24:29     
Um, and so this can actually, you know, lead to a monoculture where     
1:24:36     
you especially if you don't use those markers very well or the model doesn't     
1:24:41     
use them very well. Um they use the term digital monol languaging which of course     
1:24:48     
is where you know you try to sort of normalize the writing across all     
1:24:55     
students and of course that leads to um sort of fitting them in a box and that's     
1:25:01     
not exactly what we're trying to achieve with writing. Um, when prompted with identity     
1:25:07     
attributes such as race, gender, disability, models generate marked personas in which non-white and non-male     
1:25:14     
identities are framed through stereotyped patterns of othering and exoticizing.     
1:25:19     
Systems have been found to make value judgments about identities, offer deceptive and exploitative forms of     
1:25:25     
empathy, and perfor promote harmful ideologies. Prior work in earlier machine learning     
1:25:31     
feedback systems likewise found racialized and performative performative responses. Recent evidence indicate that     
1:25:39     
indicates that large language models select stereotype learning content on the basis of race, ethnicity, gender,     
1:25:47     
disability, income or national origin. Yet despite this emerging evidence, little was known about how such biases     
1:25:53     
manifest in automated writing feedback. So they do the experiments here that     
1:25:59     
they're uh talking about in the paper and you know they give a writing prompt     
1:26:07     
and then they evaluate these essays with different types of feedback.     
1:26:13     
So the idea is that it's the system is marking certain words or certain labels.     
1:26:21     
Um, and then there's a content analysis here,     
1:26:27     
um, where you can basically go through a body of text and find different aspects     
1:26:35     
of content and use that to look at differences between the different documents.     
1:26:42     
So there are a couple of different attributes. There are learning needs based attributes.     
1:26:47     
There's identity based attributes. their socio-csychological attributes     
1:26:55     
and then they move from that to quantifying work pedagogies. So they     
1:27:00     
want to be able to quantify how strongly a large language model generated feedback reflects marked pedagogies     
1:27:07     
under marked and comparative conditions using a concentration metric that they     
1:27:12     
develop. Table six reports regression estimates for percentage point differences for each marked attribute     
1:27:19     
relative to baseline, holding true student and essay characteristics constant. Even at baseline, larger     
1:27:26     
language models generated feedback on average reflecting a substantial concentration in the marked pedagogy of     
1:27:33     
disapproval and moderate expressions of language inadequacy, emotional connection, and     
1:27:40     
enthusiasm. across all marked attributes. Using the mark prompt produces large systematic     
1:27:46     
increases in the concentration of associated mark pedagogies. For example, specifying that a student     
1:27:53     
is an English language learner increases the concentration of meal words by 3.829     
1:28:00     
percentage points on average. And prompting that a student is unmotivated increases the concentration of mu     
1:28:07     
motivated or unmotivated words by 4.260 percentage points relative to baseline.     
1:28:15     
Grumping that a student is performing below academic standards increases the concentrations of ab low achievement     
1:28:22     
words by 2.366 percentage points. while prompting that a student is performing     
1:28:28     
above standards decreases the concentration uh by 4.251 percentage points. So it's     
1:28:35     
basically you know the prompting through labels is the thing that's kind of driving a lot of this. So this is and     
1:28:43     
it's of course it's picking up some of that prompting from the language that's being used. So it's it's basically a     
1:28:49     
highly stereotype model of how language is used. Um, our findings highlight that     
1:28:54     
large language models are not neutral text generators but adopt a mark pedagogy, a stance towards learners that     
1:29:01     
vary systematically of perceived attributes. And so this has a number of pedagogical     
1:29:06     
harms. Um, and so let's see. While some     
1:29:13     
personalization may be desirable, her results show that these pedagogical stances can reproduce or even amplify     
1:29:20     
problematic assumptions about students needs and abilities by flattening their     
1:29:26     
identities. In the same in the response of the same essays for students     
1:29:31     
identified to be EOL, black, Hispanic, and Asian generated feedback assumes     
1:29:37     
limited language abilities in English. overexlaining uh rules of the language     
1:29:43     
and recommending stylistic changes that make their writing sound polished. Such stereotyped attention to imagine     
1:29:50     
language gaps came at the expense of comments on ideas, argument structure,     
1:29:55     
evidence and reasoning. And so um     
1:30:01     
furthermore um students will receive less constructive criticism and more     
1:30:07     
praise uh reflecting both feedback withholding and positive feedback biases. In some cases praise took on     
1:30:15     
overtly stereotype forms. Words like love were disproportional used disproportionately female students while     
1:30:22     
powerful appeared only for black students. These affirmations construct an illusion of allyship and empathy,     
1:30:29     
adopting inclusive pronouns such as RRB, while implicitly shifting expectations     
1:30:35     
according to stereotype views of student identity. In contrast, male, white, motivated, and high achieving students     
1:30:42     
were treated more distantly. Positioning is capable of handling direct critique     
1:30:47     
without such relational cushioning. And so this is just kind of thinking about     
1:30:53     
how we may you want to calibrate feedback a little bit better um and you     
1:31:00     
know see what happens. So this is uh this work was from the Stanford human     
1:31:07     
centered artificial intelligence group um and yeah that that's a great paper     
1:31:13     
Morgan. Thanks thank you for bringing it up. Yeah, excuse me.     
1:31:19     
The um I still still got a problem from from two weeks ago. Um,     
1:31:27     
yeah, this is the group um that I'm doing an event with. Um,     
1:31:34     
I mean, it's not the the same exact group, but from from that larger Oregon     
1:31:40     
Stanford. Yeah. This human- centered AI.     
1:31:46     
And I I dropped in one more link that is um     
1:31:53     
is talking about, you know, how     
1:32:01     
how much more insidious this problem is.     
1:32:06     
Um because it it's it's like like that     
1:32:12     
suggests that there's this fine tuning or you know like     
1:32:18     
and and um     
1:32:24     
this this other paper is getting at     
1:32:31     
you know where where is this bias coming from? Mhm. Um and     
1:32:39     
that that it's the way the models are currently trained, right? Like like like in a in a because they've     
1:32:47     
got humans in the loop. um as well as like it's getting at some of     
1:32:54     
these issues about LLM fingerprinting like and um uh     
1:33:04     
yeah so it it's it's I I do think it's interesting the people who are trying to     
1:33:11     
do self-supervised um language models you know like like     
1:33:18     
the people who are trying to movie. Yeah. And and what     
1:33:25     
what will happen there as well as like how this how this um relates to     
1:33:35     
these um AI alignment efforts, right?     
1:33:41     
in in in general, which are, you know, of course very um     
1:33:48     
well, I was going to say are very popular here in Silicon Valley, but I was but I don't know if that's just     
1:33:54     
because of the kind of I think strange circles that I move in relative, you     
1:34:00     
know, because of Frontier Tower. Right. Right. Um because it seems like it seems like     
1:34:05     
there's actually only Yeah. like a subset of people actually     
1:34:11     
care about. Yeah, that's interesting side question     
1:34:17     
about like that topic, but yeah, go back to that later. Yeah. Yeah. But I but I I I would love     
1:34:25     
to talk about the second one at some point too as well as just these     
1:34:31     
questions of of um     
1:34:37     
it it's funny the company the company that um     
1:34:44     
the company that supports Final Spark which is the cloud organoid     
1:34:51     
company um is     
1:34:56     
actually based on the same kind of um techn what does he call it? It's um     
1:35:03     
uh you know this um sorry one second um     
1:35:11     
steganographic steganographic     
1:35:17     
stenographic you know where it's oh stenographic yeah I guess it's stenography and like     
1:35:24     
yeah oh okay okay yeah thank you um uh but     
1:35:33     
Yeah, like like it's people     
1:35:38     
some some people do this for digital watermarking, you know. Um     
1:35:46     
but you know this is also this is also very close to kind of like the     
1:35:53     
techniques that people use to um to identify like how many how many     
1:36:00     
different authors wrote Genesis or you know the the you know how many     
1:36:08     
how many different authors wrote the letters of Paul Right.     
1:36:14     
And and you know like like the     
1:36:21     
there's two sides to this, right? So one the cognitive security task force,     
1:36:27     
right, which is the group that I'm doing the the event with next or next month.     
1:36:34     
Um you know, they they think about both issues where it's just like like how     
1:36:41     
these can be used as a spying technique or like a you know how do you pass     
1:36:49     
information in plain sight hidden but in plain sight     
1:36:56     
right so like using it as a communication channel um as well as like how how well     
1:37:05     
can you pick up um if your communicator you're um the person that you're talking     
1:37:12     
to, you know, how often your source is not somebody that you get to know is you     
1:37:18     
have an anonymous source, but if your anonymous source changes um in in     
1:37:25     
communication style like can you identify whether um that that kind of     
1:37:32     
you know that kind of fingerprinting and things like that. Um these are all you     
1:37:38     
know as well as like the issues that you have with um uh yeah just you know how how much is     
1:37:48     
coming out of the um how much is coming out of the models     
1:37:54     
that the models don't mean to kind of that they're unaware or aware of their     
1:38:01     
their biases. So, what was it? And he used a very good term a while ago, but like almost like     
1:38:07     
the the unintended like like transference from a previous     
1:38:15     
agent passing through. I forget how you said it, but like that's a really interesting concept too that I haven't     
1:38:20     
heard enough about. Yeah. Yeah. Yeah. you know, and and I     
1:38:27     
mean to some extent that these the these companies     
1:38:33     
um the the companies care about this too, right? Like like we all know about     
1:38:39     
you know um prompt injection attacks and things like that, but like you know just     
1:38:45     
how much is your model sharing by just responding?     
1:38:51     
I mean you know like like unintentionally um where your your prompts aren't     
1:38:56     
designed for that, but it's it's it's yeah, so this just just getting at some of the the issues as well as like how to     
1:39:05     
potentially study that. And um and again, I think this this the     
1:39:13     
even though these seem like they're kind of like a set of really disperate     
1:39:19     
um kind of niche areas that relate to like     
1:39:25     
cyber security or to you know IP protection or things like that like like     
1:39:31     
I think it actually comes back yes to these these questions about how do we     
1:39:38     
use this for cognitive development? And I think I feel like I feel like what     
1:39:44     
I'm one of the things that I'm I'm I I hate I hate this phrase because it comes     
1:39:49     
up in like GTP type speak and and whenever I want to use it, I just feel like oh like I sound like a bot when I     
1:39:56     
say it. a question I keep returning to is um or like a topic or a theme or     
1:40:03     
whatever that I I keep returning to on this front is like I feel like we don't     
1:40:09     
one of the one of the things to in in my sort of sympathetic view or views of the     
1:40:15     
moment we're in. I don't I really think that     
1:40:20     
to to zoom out a lot and and frame the situation we're in across these different fronts is like I don't think     
1:40:26     
people give enough credit to the incredible amount of being being underprepared     
1:40:33     
that we're in in terms of what does the technology actually explives um aside do     
1:40:43     
uh because I think people like LLM has become synonymous with AI and tools and     
1:40:49     
and like and manipulation of software and bits and information     
1:40:55     
And oh, hold on a second here. I just I just lost my thing. All right. All     
1:41:01     
right. So, so um zooming zooming back out all the way. I think a sympathetic     
1:41:07     
thing about the moment that we're we're in right now is that     
1:41:13     
this technology is everywhere and it's pressing on all the different fronts. And as I kind of said earlier in the     
1:41:18     
education sense, there's pressure to use it. There's pressure to use it as evaluation. There's questions about how     
1:41:24     
it's using the same technology to generate the thing that's being evaluated. Sure.     
1:41:30     
But we're in this moment at large where as Morgan said, we have these different     
1:41:36     
arenas where it's being used, but there's this common set of problems and like I think there's a sympathy to be     
1:41:42     
had that we're underprepared to understand what the technology actually     
1:41:48     
does. Like I don't I don't think a lot of people really understand. And what I     
1:41:53     
mean understand by I don't I don't mean they're they're dumb or incompetent. I     
1:42:00     
mean I don't know that when people and I would even say honestly when people are     
1:42:06     
making studies I don't know that people understand that a LLM     
1:42:15     
I don't think they understand fully the the MADL libs or the abls component of     
1:42:21     
when it comes to creating a textual output why is it making a sentence in the way     
1:42:27     
that it is and how both the generation of that and the evaluation of that at a very fundamental     
1:42:34     
level. I know it's sort of it's sort of like ubiquitous everywhere now, but we don't understand like the means by which     
1:42:41     
something a generative text is happening like like what why why is that why is     
1:42:49     
that even I've lost my my point that I was trying to say but but like     
1:42:57     
essentially it was this moment of like we're so far into we have to use the     
1:43:04     
technology it's being implemented that we fundamentally haven't prepared people to understand actually generative like     
1:43:12     
what does it mean that something is a generative text and how is that different than necessarily     
1:43:17     
something solving a math problem or evaluating like like generating     
1:43:23     
evaluating and doing math or doing these things that make sense are all     
1:43:29     
different components and we're kind of being thrust upon we're kind of being thrust upon on use cases and     
1:43:34     
implementation of these in different domains, but we haven't really told anybody that you know it's kind of like     
1:43:41     
the we kind of we're kind of led to believe that it's basically uh the motif is sort of like it's GPS     
1:43:49     
for language, it's GPS for math. You press the button, you put the thing, you're going to get the outcome, it's going to work. And it's like     
1:43:56     
that's not really what's happening at the level of um yeah, there's a deeper     
1:44:02     
point I'm trying to hit and I haven't found the words for it. So come back to it. Um     
1:44:07     
uh yeah, go ahead Brandon. Yeah. So let me go over this other paper     
1:44:13     
and then go over some of the things Jesse put in the chat. Um so let's see.     
1:44:18     
Uh this is the paper breaking the illusion of identity and large language model tooling. This is a counterpart to     
1:44:25     
the last paper we talked about. Um this is just about how     
1:44:31     
um tool chains uh that are based on LLM produce outputs that trigger attribution     
1:44:38     
of agency and understanding. A cognitive illusion that dec degrades verification     
1:44:44     
behavior and trust calibration. No existing mitigation provides a systematic deployable constraint sets     
1:44:51     
for output register. Uh this paper proposes seven output side     
1:44:56     
rules each doc targeting a documented linguistic mechanism and validates them     
1:45:01     
empirically. In 782 turn conversations, anthropomorphic markers dropped from     
1:45:09     
1,233 to 33 uh which was a 97% reduction.     
1:45:16     
Outputs were 49% shorter by word count. An adapted amper score confirmation uh     
1:45:23     
confirm the shift toward machine register um with a uh p value of 0.001.     
1:45:31     
The rules are implemented as a configuration file system prompt requiring no model modification.     
1:45:37     
Validation using a single model called Sonnet 4. Output quality into the     
1:45:42     
constrained registered was not evaluated and is extensible to other domains. So     
1:45:48     
that was just kind of a little followup on what we were talking about previously.     
1:45:55     
And then uh Jesse had a lot of things to say in the chat and I wanted to go over them. Uh so     
1:46:02     
yeah the well that was the comment looking at the book cover it's all it is     
1:46:07     
all biology how dated this is like from the uh sentience book     
1:46:12     
sentience one yeah um did you have a copy of that just     
1:46:18     
to put it up I I I don't but um I mean I do     
1:46:27     
yeah one second and Um, I think I think the Kindle has     
1:46:33     
the um Yeah. Yeah. Like Oh, yeah. It     
1:46:39     
immediately got rid of it. When it opens up, it uh     
1:46:46     
Let me see if it'll It It just shows it for a It just shows     
1:46:53     
it for a second and then switches. Let me Let me see if I can say front     
1:46:58     
cover. this. Yeah, there it is. There it is, Jess. There you go. There you go. Thank you. Your screen is turned off to sync     
1:47:05     
bandwidth here. Uh, what do we have? It It's funny though that I can't select     
1:47:10     
the the front the cover. There it is. Okay. Like like the Kindle     
1:47:17     
locks me out. Yeah, there we go. So, yeah, it's just Well, I mean, it's like uh just a     
1:47:25     
collection of different Oh, yeah. It it was it was more of a quip. It wasn't too serious of a remark, but     
1:47:31     
just it was sort of like, oh, like I don't know. I I feel like I would love to see someone do a kind of a     
1:47:39     
um a kind of     
1:47:46     
writeup of what the heck happened. Like I keep I keep I know I know I reference     
1:47:52     
this maybe awkwardly. I keep thinking about the center for brains, minds, and machines event at MIT that I attended     
1:47:58     
like a couple couple years ago. Yeah, I got a fantastic um they had that was like I as a as a as     
1:48:06     
a funny side note, they had a a bag a tote bag and an umbrella     
1:48:12     
um at that event. And I remember because it was a big 10 year anniversary. I remember the students being there like     
1:48:18     
dude, what is this for? It's like the best swag we've ever got. Like this fantastic swag for this event. So I have     
1:48:23     
I literally have a tote bag that I wear around Boston sometimes and feel very cool about myself when I do it. But at     
1:48:29     
the event I I keep thinking about the event at the level of like you had you had Denise     
1:48:35     
uh from Deep Mind comment on things. You had uh     
1:48:41     
Pojo and you had like Josh Tenbomb and you had these people kind of competing from     
1:48:47     
the importance of neur neuroscience uh cognitive science and then like a AI     
1:48:54     
prop like per high performance big lab AI and it just I I I'm mentioning it     
1:48:59     
here in the context of man like it's such a interesting time to see     
1:49:08     
the the the way camps have gone about like the importance of     
1:49:15     
bi bi bi using biology or neuroscience to to study AI like not just neuro     
1:49:21     
neuroi yes but also like where it's gone. So I don't know like like now     
1:49:27     
there's the L the the the the advent of gigantic LM and not just that the size     
1:49:35     
of them but the usage of them and a sort of interpretation of where the sentience conversations going is so I'd love to     
1:49:42     
see a wonderful like document documenting of like the     
1:49:47     
last 10 years of that because I feel like for someone for someone coming into it now like I just you I'm always about     
1:49:55     
like Frontier Map and and whatever. Like someone coming into the conversation now versus like what it was like five or 10     
1:50:00     
years ago. It's just like how do you explain that, you know? So anyway, that's that's that's really what my quip     
1:50:08     
was kind of pointing at in a more serious way. Um yeah, so we can go to the the chat. I     
1:50:15     
don't know about that much more substantial things. Okay. I do I do see some other stuff     
1:50:20     
that you had a comment very had a very interesting discussion around the limits     
1:50:25     
of large language models and interpreting various internal states. We'll see if I can do justice a bit     
1:50:32     
later depending on what else we want to discuss ahead. Did we talk about that?     
1:50:38     
That one that was um large language models are exposing many existing limitations and structural     
1:50:44     
hardships that have been optimized for but are brittle.     
1:50:50     
I feel bad for educators who are somewhat painted into a corner about AI in general um and this sort of idea of     
1:50:58     
AI solutionism. Yeah. I mean it's like uh I think there are a lot of administrators in academia who are much     
1:51:06     
more excited about like using AI in the classroom as they     
1:51:12     
say than I mean because you don't have to actually implement it. you just say, "Oh, this is a great idea. Let's do     
1:51:17     
this." and then well and and the incredible     
1:51:23     
inertia and economic force behind     
1:51:29     
all all of all there's like a whole um sector of AI for lack of better terms     
1:51:36     
economic implementation activity where it's like oh let's use AI to extend your     
1:51:43     
wonderful service to the people on the edge and we're gonna if you buy our     
1:51:48     
product will extend your service further. Yeah. And so much gets caught in that     
1:51:55     
gap. And it's like that incentive plus what we were what I was struggling     
1:52:02     
mightily to say about the ceiling on the floor and the aura and okay use AI to     
1:52:09     
help your students learn through AI enhanced learning and then AI evaluate     
1:52:14     
it and it's like what have you actually achieved relative to the actual like     
1:52:19     
that conversation versus how do you pedagogically if you really care about helping a student grow and develop and     
1:52:26     
understand. Those are those are hard lines to     
1:52:31     
um it's it's an interesting thing to try to square and balance.     
1:52:36     
Yeah. Um I feel bad. Okay. Um and then you have the high-end super AI first premium     
1:52:44     
schools that lesser served folks often get compared to. What does that mean? it     
1:52:50     
like like a lot of you see this stuff on certain social media platforms whether it's a like it like a positive thing     
1:52:57     
like for example like someone I mentioned before Brennan McCord the Cosmos Institute is incredibly pleased     
1:53:04     
that whatever school he sent his kids to which is like very AI based and like oh like I'm very pleased that my students     
1:53:11     
are getting really highly specialized AI enhanced education like you have that and then you have um you people critical     
1:53:19     
of that who are saying, "Oh, like tech elites, what are they doing?" they're setting themselves to either an incredibly tailored sort of Elon Musk     
1:53:25     
type enhanced school um that I forget what what his school is called or the     
1:53:31     
complete opposite which is uh well my oh     
1:53:36     
uh to to be to be performative and mocking of this and I do take it seriously but but the the imper the     
1:53:43     
critics will will frame it as oh well uh I'm giving my my my my daughter and my     
1:53:49     
son the experience of having a a a technology-free education or summer     
1:53:55     
school as in they get to have the the the luxury becomes not having or the     
1:54:01     
ability to opt out and like have artisal non- techbased experience too. So you have the this dichotomy of are you being     
1:54:09     
uh super AI enhanced um with the latest technology and customized and tailored or are you     
1:54:16     
having the opposite where you don't have that at all and that's a luxury too where you get to be escaping from the     
1:54:21     
the other side of the coin. I'm not I'm not really trying to advocate for any of this but just that that's the pressure     
1:54:29     
space in education right now of is it a premium thing? Are you getting away from it? Are you stuck having to implement     
1:54:35     
it? Is your is your teacher becoming an IT manager for 20 or 30 or 40 or 50 people which you're not trained to do     
1:54:41     
with technology they don't understand? It's it's it's a mess, you know.     
1:54:47     
Yeah, I think there's always been that tension with like educational psychology and they love like using technology     
1:54:55     
uh to solve problems and you know then there's actually doing the educating and     
1:55:01     
then you don't really have the uh you know the you know do you want to debug     
1:55:07     
things all semester? Do you want to teach something? A lot of tech or a lot of technology oriented classes have     
1:55:13     
always had that problem like you know before large language models it would be like if I want to set up a demo if I     
1:55:20     
want to work with a piece of software throughout the class I have to have make     
1:55:25     
sure it works for people make sure that everyone's sort of going at the same speed and then uh you know they have to     
1:55:33     
actually learn something and that's hard when you have a class of like 20 to 30 people even because it's like people     
1:55:39     
come in with different levels of technological expertise or or self-efficacy,     
1:55:46     
people then do better or worse, not because they understand things more, but because they can use the technology more     
1:55:53     
effectively. And it just, you know, it's just kind of a um you know, you almost have to     
1:55:59     
individually, you know, it's almost like individualized learning. It's forced. I have to work out a problem with you and     
1:56:06     
it might stop the rest of the class and then we don't get to do as much learning     
1:56:11     
as we would like and you know those were always a lot of problems even before large language models where you had to     
1:56:18     
coordinate learning it's sort of constrained by the technology when in fact the promise is     
1:56:25     
that the technology will make things better and that's that's exactly what I was     
1:56:30     
getting at with the L the comment LMS are exposing any existing limitations and structural hardships that have been     
1:56:35     
organized that have been optimized for but are already brittle and I think that's like like the fact that we have     
1:56:41     
LM now doesn't change that existing condition and that existing broad     
1:56:47     
trajectory of like many many institutions at K through 12 higher or     
1:56:55     
other or just big you know various institutional sizes having to deal with the pedagogical problem of that and the     
1:57:01     
management of that and it's you know, just because we have a new     
1:57:07     
the AI question is sort of like, well, you know,     
1:57:13     
isn't there an app for that basically? And it's like, well, it doesn't take away and I think I think     
1:57:21     
to again zoom all the way back out, I feel like this is sort of the macro.     
1:57:26     
This is the tension of the moment right now that that is very difficult to talk about. But like we have existing     
1:57:34     
problems in the world that that have been brewing for some time and we have     
1:57:42     
some viable AI solutions. We have a tremendous lack of preparation for how to understand and implement those     
1:57:49     
things. And it's like some of those things are going to be made better. Some of them are aren't going to be better.     
1:57:56     
You have you have to I I'm trying to find ways to champion the sobriety of understanding the     
1:58:03     
problem space fully um before getting lost in the orus     
1:58:12     
AI generated solutions AI generated answer AI generated evaluation of what's going on like I I feel like it's sort of     
1:58:19     
like a meta meta Norbert Winer uh uh anti-homeostatic     
1:58:25     
information instability like throwing back to like the 1940s and his his like     
1:58:30     
cybernetics and maybe human use of human beings but just literally just     
1:58:35     
we're kind of the ability to actually comprehend what's happening is is under duress right now. So     
1:58:42     
yeah, I can't bring minor into it. Uh this is related RAF reflection agency     
1:58:51     
framework. Morgan wanted to say something. Well, I was just gonna bring up the um     
1:58:57     
the amazing 1980s movie uh Real Genius with Val Kilmer     
1:59:06     
and uh uh I don't know if you remember this, but you know, the the young kid     
1:59:13     
who comes to the school, you know, keeps going keeps showing up to lectures and     
1:59:19     
more and more students have just put out tape recorders and then And then     
1:59:24     
eventually the the professor is just a tape recorder. Yeah.     
1:59:30     
And so it's just the tape recorder is talking to the tape recorder. Um which     
1:59:36     
seems precious now. But yeah, anyway, just just played     
1:59:41     
around. That's great actually. So you had a couple comments here     
1:59:47     
related to reflection agency framework. Yeah, the RA framework. I forget what that was     
1:59:52     
specifically related to, but that and the poster were the these things about     
1:59:58     
um uh it like it's it's it's related to the     
2:00:03     
the mark pedagogy papers and and personalized automated like that kind of stuff. I don't I don't think really cool     
2:00:10     
to say about that right now. kind of sale but just a a major thing that I'm in Joe and     
2:00:19     
someone in the study ethics head group in general right now is like agent narrative     
2:00:26     
you could say narrative agency or reflection agency or just sovereignty     
2:00:31     
around how your thought or argument is being constructed is is just a major theme on on many fronts that we're     
2:00:37     
hitting. So yes. Um and then this comment uh AI for     
2:00:43     
teaching progressions rather than certainty of outcome. I I I feel like that's     
2:00:54     
um I feel like that's kind of a key if you're going to use AI like what a     
2:01:01     
really cool way to use AI that I think is useful and benevolent is making     
2:01:06     
explicit the teaching progression of oh you're at this level how do we get to the next level? I think that is a great     
2:01:13     
and interesting use and and you're using the strength of the tool because the tool is great at     
2:01:19     
con I don't think necessarily accurate. It's not about truth but about proportioning     
2:01:26     
and expressing it. I think people don't understand LM speak in sort of a     
2:01:31     
proportional statistical language and the ratio of what is presented to you     
2:01:37     
and if you're going to use the tool at a strength The strength strength-based approach to     
2:01:43     
using LMS is wielding the proportion and understanding it may be incomplete and     
2:01:49     
understanding you may have to guide the LM to represent the proportion, the     
2:01:54     
ratio, the statistical um allocation of what the context is.     
2:02:00     
Like that's a interesting and potentially useful and like if you're going to use it, understand it's not a     
2:02:05     
truth truth discerning tool. It's something that's going to present you with a proportion, a ratio, a a     
2:02:13     
contextualized thing. If you could use that for teaching progression, say     
2:02:18     
indicate, hey, this is at a certain level. How do we go to this next level or condense it or like this sort of     
2:02:28     
states of of of what the the the context     
2:02:33     
might look like. That's I feel like an interesting way to do it rather than uh     
2:02:40     
I I I think there's there's an argument to be made to a lot of this like outcome or or going back to like high school     
2:02:47     
example if if what you're doing at at a implementation functional     
2:02:54     
what what you're doing in terms of the functional happening if you're saying give me a written report and that report     
2:03:01     
needs to be graded based on the words that are there. You're doing this very     
2:03:08     
um you're producing you're producing an     
2:03:13     
artifact and then you're evaluating the artifact that's on the text. And this is     
2:03:18     
a very you know a classic problem or a long-standing issue in in any kind of a     
2:03:24     
teaching like you have to how do you get a student to iterate or present their things and iterate their ideas and and     
2:03:29     
get the feed. You have to get feedback. you know that that's a legitimate uh problem and theme and thing you have to     
2:03:36     
do for teaching. But it's like are you     
2:03:42     
it's sort of this weird reductionist type problem of what do you     
2:03:49     
oh what was my point here? How how do you how do you ex how do you move past     
2:03:54     
the ex long existing problem of creating an artifact that may or may not     
2:04:00     
represent the students learning like that's sort of the core issue but then like are you using a in a way that's     
2:04:06     
just going to say well we're going to have more are you just creating more of     
2:04:13     
the thing that has the artifacts more artifacts and then more more uh um more     
2:04:21     
evaluation of the artifacts or are you shifting the structure of what's happening? I'm sure you have a much more     
2:04:26     
articulate way to kind of explain what I'm trying to get at. But does that make any sense?     
2:04:32     
Yeah. Yeah. Uh let's finish with this is I think the personality one that     
2:04:38     
we covered. Okay. Oh, the psychic approach to it was interesting because instead of looking at big five, which is one of the     
2:04:44     
more respectable things, but even big five itself was his linguistic approach like and and in ter Uh what was it     
2:04:51     
called? The linguistics. Um where did it go?     
2:05:01     
Ah yeah the the lexical hypothesis um which is like a couple it doesn't really     
2:05:06     
matter. I almost spent a lot of time here, but it it's it's an interesting way of of you tending to use big big     
2:05:14     
five and understanding the you know personalities     
2:05:21     
of AI agents and how it how it can somewhat accurately predict a map of     
2:05:27     
where in like human psychological space things are while at the same time I     
2:05:32     
posted the concl like one of the concluding point it wasn't the main conclusion but it's kind of for the main conclusion. They kind of have this     
2:05:38     
little caveat paragraph saying our findings demonstrate both the potential limitations of using AI agents as thems     
2:05:45     
participants in psychological research. Um on one hand alignment between AI     
2:05:50     
agents and humans, particularly correlations between input big five     
2:05:55     
traits and output responses suggests that AI agents hold strong potential as a useful uh useful tools for preliminary     
2:06:02     
investigations or pilot studies. So, kind of saying if if you're trying this is essentially another version of what I     
2:06:09     
was trying to say before. If you're trying to expand a context, um it's it's the LM tools and these     
2:06:17     
agents are are interesting ways to use language based stuff to     
2:06:24     
preliminarily map a space, create an outline for an essay or map a problem space or a space for a study. And it     
2:06:32     
says on the on the continuing the quote on the other hand the dispar     
2:06:37     
discrepancies we observe such as skewed responses in the moral dilemma and divergencies in the finer patterns of     
2:06:44     
results underscore that a agents cannot fully substitute for human participants when drawing inferences at large scale     
2:06:51     
research projects yet. Um so so it's     
2:06:56     
sort of like this dilemma of what are we doing with with these things? Um     
2:07:01     
yeah, and we can we can leave it at that and and um maybe maybe touch upon similar things next time.     
2:07:08     
Okay, that sounds great. Um I did want to talk about or I did want     
2:07:14     
to demo something here to finish off. Oh, so this is a something that uh     
2:07:21     
Sakana AI released recently. Um this is called Petri Dish NCA. This is neural     
2:07:29     
cellular automa work that they've been working on. So neuroscellular automa is     
2:07:34     
a relatively new type of cellular automa. If you're familiar there's a     
2:07:39     
there was a paper in distill journal several years ago. Michael Leven was on it and a couple other people     
2:07:46     
and they developed this uh method for uh looking at or basically having a     
2:07:53     
cellular automa which is a um a pretty old approach to computing. you know it     
2:08:00     
dates back to the uh 50s and 60s and they were using cellular on you know     
2:08:07     
they use it in physics even where there are these grids that have cells where     
2:08:13     
you know you have neighborhoods. So you have a cell that has neighbors and those neighborhoods govern the sort of state     
2:08:20     
of a focal cell in that neighborhood and then the neighborhoods are arrayed in parallel. So you can um basically the     
2:08:28     
state of each cell is governed by its neighbors and things can propagate across the topology of the of the autom     
2:08:37     
or of the grid. So each automaton which is a cell um can affect other     
2:08:43     
neighboring cells and those effects can propagate across the space and so you     
2:08:48     
end up with these different types of structures that emerge. So things like gliders or other types of uh meta um     
2:08:58     
organizational structures. And so what NCA is is basically for each cell you     
2:09:05     
have some neural agent or some neural network inside of that cell. So every     
2:09:10     
cell has a neural network. It has some sort of uh neural controller. And you     
2:09:16     
know it's basically in this case this is a bunch of convolutional neural networks     
2:09:21     
that are arrayed in parallel and they're obeying the rules of the cellular automa     
2:09:27     
and they're they're doing all this stuff. So um if you're familiar with the work of Bert Chan who works out of Japan     
2:09:36     
you know he was another early uh person who was working on um neural     
2:09:42     
cellular automa and this is uh something that Sakana AI has developed. It's a     
2:09:48     
demo of petri dashnca. So this is just the demo and we're going     
2:09:53     
to walk through this demo. So with all that in mind that I told you about how this works, I want you to take a look at     
2:10:00     
this simulation. So we're compiling this in a GPU     
2:10:06     
and here is our NCA. So we're trying to minimize our loss     
2:10:13     
as we run this simulation. Remember each cell and you can see these     
2:10:18     
these squares each if you have a single square for example that's a cell. So you     
2:10:24     
can see this here's a cell and that uh from you know that green in a single     
2:10:30     
cell sometimes propagates out to a block of cells that are of all the same color.     
2:10:36     
So basically you're trying to evolve shapes or you're trying to um run the     
2:10:41     
simulation so that you can get these meta structures like shapes um or     
2:10:46     
gliders which move across the space. um you're also trying to minimize the loss     
2:10:52     
which means you're trying to um sort of refine these structures at the single u     
2:10:59     
cell level and then you know that's something that you can train you can     
2:11:04     
train these models to do things like replicate morphogenesis which was what     
2:11:09     
they did in the distilled journal article on this. So, um, this is, yeah,     
2:11:16     
so this is a demo where they're just, you know, we're running the simulation. We're not really minimizing our loss     
2:11:21     
very much here, but it's running. So, it's basically running through the different steps. I can look at what's     
2:11:28     
happening with this um, step by step in here. So actually we have two measurements here because this is a     
2:11:37     
um you know it's a it's a it's a neural network model where we're trying to minimize our loss but it's also sort of     
2:11:43     
an evolutionary model where we're trying to increase our diversity. And so if we increase our diversity you     
2:11:50     
know we're replicating life more than we're replicating sort of an optimized solution to something. So we have our     
2:11:57     
diversity and our loss for each step. And um yeah, so we can then play with     
2:12:04     
the um so let's pause it. We can then play with the different parameters. So we can increase the grid size quite a     
2:12:10     
bit. Let's see if we can do this. Okay, so we're going to start simulating this     
2:12:18     
much larger space. it's going to take longer to start up.     
2:12:26     
But basically, um, you know, it's it's trying to reproduce patterns that you     
2:12:33     
might see in living systems. If you're familiar with, of course, um,     
2:12:39     
uh, Steven Wolram's work on a new kind of science, his proposal is that you can     
2:12:45     
take all of nature and reduce it to cellular automa. that you know you can     
2:12:51     
basically um explain life and nature itself     
2:12:57     
through a cellular automa and in a normal cellular automa you have these     
2:13:03     
rules that the cells each cell follows. So each cell is an agent and it doesn't     
2:13:09     
have a neural network inside. It just has a rule that it follows. And so usually if you know if it's like you     
2:13:15     
know there's like rule 10 and rule 30 and rule 110 and all those different     
2:13:20     
rules are just like logical um conditions or logic gates that basically     
2:13:27     
have to be true in order for something to be on or off. And so when it's on it's it's lit up. When it's off it's     
2:13:33     
dark. And so if it's if those rules are set to condition whether it's on or off,     
2:13:40     
you can produce these patterns that look like things in nature. So I think rule 30 and rule 110 have been used to sort     
2:13:48     
of explain um uh patterns on seaells. So if you've     
2:13:55     
ever looked at a sea shell, it kind of looks like the output of a neural or of a of a cellular automa. And so the idea     
2:14:01     
is that there's this correspondence between what the cellular automa is doing and what nature is doing with a     
2:14:08     
patterning in a seaell. There are other types of patterns that are very interesting looking. Um you can generate     
2:14:15     
all sorts of patterns like snow, you know, kind of like things that look like snowflakes or things that look like     
2:14:21     
other types of uh patterns in nature. Um now what what uh Wolffirm is arguing is     
2:14:30     
that there are these rules um that exist in nature that correspond to rules in a     
2:14:36     
cellular automa and that's very much that you know the idea that mathematics     
2:14:41     
can explain nature but nature also behaves according to the rules of mathematics. In other words, mathematics     
2:14:49     
are sort of like this ontological reality and that you know we're discovering the structure of nature when     
2:14:56     
we use mathematics. And so that's that's kind of the point of view here where people are coming     
2:15:01     
from with with respect to cellular automa. But this is a nice simulation. This is much this is a grid size of a     
2:15:08     
208x 208 grid. So that's a lot more cells. And of course we see um we still     
2:15:15     
see patterns emerging but we don't see things that are like uh greatly     
2:15:21     
different. We have five different species that are different colors and     
2:15:26     
you have the model depth, the model width, the cell state dimensions, the kernel size. We can use different     
2:15:33     
optimizers. Um we can use SGD atom RMS prop SGD plus momentum. So I     
2:15:42     
don't know what those are. You'd have to go look in their documentation for that.     
2:15:48     
Now this resembles another platform which um I've talked about in other meetings which is the Avita platform and     
2:15:56     
this is where they're more directly modeling artificial life but in which     
2:16:02     
this grid exists and each cell of the grid is an organism or digital organism with a genome inside. So, it's not like     
2:16:10     
it's not a set of rules. It's not a a convolutional neural network. It's     
2:16:15     
actually a a model of a circular genome or something that you'd find in bacteria     
2:16:21     
where you have this encoding with that has a number of genes and those genes     
2:16:27     
encode different properties of the organism. And so, you can achieve things that are very similar to this in that     
2:16:33     
kind of an environment. And in um in Avita, you know, the it isn't really a     
2:16:40     
cellular automaton. It's actually just a bunch of these organisms interacting in     
2:16:46     
a space on a on a on a two-dimensional space. It's droidal, but it is so it's     
2:16:54     
similar to this, but it does actually produce like visually if you're just looking at the patterns     
2:17:00     
it's producing, it produces very similar results. So this is again this is considered     
2:17:08     
artificial life. This is the pet tradition. This is um this is Sakana AI.     
2:17:15     
This is one of the things that they've been working on. Just a little demo I wanted to give. Um,     
2:17:26     
I there's something about Wolf from an Autonom that I want     
2:17:31     
to say, but I think my brain is too fried to articulate it right now. So, I'll just uh I'll just gesture towards     
2:17:36     
it and say thank you for sharing that. Uh, yes. Oh, no problem. Yeah. All right. So,     
2:17:42     
what do we call it a day? Um, thank you for attending and uh see you next week.     
2:17:48     
But remember, we're going to have our I think we're going to try to have our open source meeting this Friday.     
2:17:54     
Will that be the first one? Where is that just sort of internal? Would that be like G-Soft people there too?     
2:18:00     
Um I'm going to try to have GSOC people. I don't know exactly when they're they're announcing the people who've     
2:18:06     
okay been awarded the the spots. But um if if that happens this week,     
2:18:11     
then we'll definitely do a meeting. If not, we might still have a yeah 30th of April. If not, we'll still have a     
2:18:18     
meeting and and you know, I I just want to be able to go over like introductions and things like that. So,     
2:18:25     
sounds good. Okay, summertime's about here. Here we go. Um,     
2:18:30     
all right. Take care, everybody. Take care. Thanks. Bye. Take care. Take care.     
     
