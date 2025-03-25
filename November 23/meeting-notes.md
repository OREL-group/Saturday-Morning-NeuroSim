## Meeting Recording

[YouTube link](https://youtu.be/nqomWNh_cb0)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113534195769582330)

## NOTES
Session 1: Q2. Embodiment Aspect of NeuroAI.

* DevOps -- before time, software development was chaotic.

ACT-R paper: bringing things to behavioral data.

* Activision --> have the best behavioral data on the planet.


From Introduction to "The Complex World" --> constructs for complexity.

* why do we have cell phones, "vantage points" paper, as opposed to other things?

* formalize a project description Krakauer's take on complexity science.

* teleomic vs. non-teleomic matter. Krakauer -- synthesis of complexity theory.


What's the next version of 4E? Information processing and cognition --> cultural criticism.

* structuralism vs. post-structuralism. Slice off half of CogSci hexagon. Align with "complexity" or methods.

* share folder of screenshots. SciOps. DevOps -- before time, software development was chaotic.

* oscillations -- lots of use in embodied systems, not so much in thinking systems?

* greater multiscale perspectives (sensu Levin)?


Web-scale projects --> multi-node maintainability.

* why do you need a messaging library? Data Lakes? Constant flow mentality.

* AWS added features because customers asked for them.

* human connectome project (laptop vs. cloud).


SciOps paper --> authors from Datajoint, Natuonal Labs, and various open-source people.

* Numenta --> anomaly -- non-DL, NNs. Detection company, open-source company, from a long time ago.


Deep Learning is very general. 

Universal Laws <-- Networks --> Structural
Post-structural, Chaos <-- Networks

* evolution-learning connection (old problems in PopGen).

* diffusion models, evolutionary algorithms, statistical mechanics.

* evolutionary algorithms behave the same way (very GECCO-y).

* dist2dist --> ML categorization.

* dist2dist --> stat mech, mutational distance, probabilistic approach.


Fit cognitive models to data --> neurophysiology models to data --> Dynamic Causal Model.

* implementation of data analysis --> cortical column model. Not brain, but pyramidial cells in contical columns.

* postdoc-level people @ Numenta live-streamed meetings. 

* CogSci reading group channel --> 

* SF CogSci reading group: Braitenberg Vehicle discussion --> by vehicle 5 or 6, complexity that you can understand/interpret.

* Richard Watson/Jeff Clune --> modularity, evolution brought in @ vehicle #6.

* IPAM -- Mathematics of Intelligence (some in Bioevolution). IPAM Workshop -- previous workshops. Multiscale, collective intelligence.

## TRANSCRIPT
     
Transcript     
0:01     
hello morning not bad super super wet     
0:07     
here and raining for like three days oh wow okay yeah four four days four     
0:15     
days it's got an atmospheric River oh okay I've heard yeah I heard     
0:24     
that oh good luck with that yeah like I think two more days or     
0:31     
something crazy     
0:39     
okay um so welcome uh when we get     
0:46     
started so yeah today we're going to talk about uh the nuro AI     
0:53     
workshop last week you know it's like the was very busy had the neuro AI workshop and then the active INF     
1:00     
Symposium one after the other and so um that was fun to kind of Juggle that but     
1:07     
the N wayi Workshop actually is on it's actually been recorded and you     
1:13     
can go to the we NIH has a website where they have recordings I don't have the link pulled up but I'll put it in the     
1:20     
slack sure yeah so I go like NIH cast     
1:27     
yeah yeah NIH cast uh so yeah I I I thought it was really     
1:33     
interesting there was a lot of good stuff a lot of question posing you know like a lot of the     
1:39     
NIH uh granting agency events you know they do it because they want to     
1:46     
clarify the terms of the thing that they're going to fund and so a lot of it was people from     
1:55     
you know I mean that there I don't think it was any more coherent than any other Nar AI Workshop or conference but they     
2:02     
did posst some questions and have you know so it's like we can actually Define     
2:08     
what we're going to fund and I've done that before I've been involved in those things they're pretty     
2:14     
pretty interesting I mean it's like hurting cats everyone has their own priorities and then you have to kind of     
2:19     
figure out where you fit in and then they they put them down on a list well we'll see what     
2:25     
that looks like it's fun anyways uh yeah so this week we had     
2:32     
uh Deva worm we had our Dil worm     
2:37     
meeting and we talked a lot about mechanical or mechanobiological networks     
2:44     
in the cell and we talked about how to sketch that out I talked actually I went over     
2:51     
the uh the devil worm report to openworm really quickly uh which I I I'll talk     
2:59     
about that in a minute uh the open room annual meeting but I went over those slides and it it's kind     
3:04     
of like reviewing some of the things that we've done in the last year and then that segwayed into this discussion     
3:11     
on me uh mechanobiological networks how to model that with respect     
3:17     
to what Susan is working on which is tensegrity which is this model of ultra stability in mechanical     
3:24     
networks and you know how you can model that using biological soft materials and     
3:33     
a lot of the software packages are you know kind of it's difficult to model a     
3:38     
tensegrity Model A biotensegrity model with soft materials in a software package because     
3:45     
usually they want to model hard materials because most people are interested in the application of TSR     
3:51     
that is like building houses or structures or things like that and so     
3:57     
that's we talked about how to build those kind of models and then we talked about like the     
4:03     
hypergraph stuff that we've been doing in D.A worm and how we could build like a     
4:09     
mechanobiological hypergraph basically so I've been thinking about that for a     
4:15     
week uh and so maybe we'll get back to that we also you know uh then Tuesday I     
4:25     
had the openworm annual meeting which was good that's every year we meet with     
4:31     
the board of directors at openworm and then we have people in openworm     
4:37     
who you know show their work so there were a couple people who had done a lot     
4:43     
of work uh you know dor included so Dil worm had a presentation there we talked     
4:50     
about things that we've done the last year in Dil worm and then uh Lucas who I     
4:55     
think presented in this meeting several months ago on his project on proteomic     
5:01     
or proteomic informatics or I guess you could call bioinformatic proteomics or     
5:09     
whatever he he he presented on I I recapitulated that presentation and and     
5:14     
gave a short report to the to the board and to all the people in open world so that was good they they were impressed     
5:21     
with all that work they were very happy with it and then um orig orig Leon who     
5:28     
we've talked about in the cont text of incf and uh some of the open science     
5:34     
initiatives that I guess it's neurod Debian that he works on or or proposed at some point where     
5:43     
there was a co-author on that paper he uh he's been really doing a lot     
5:48     
of work with open uh they they've been developing for example some connectome     
5:55     
tools and so they they've been developing it's it's kind of like taking all the connectone data data sets you     
6:03     
know we have the Gap Junction based data sets the synaptic data sets there's a     
6:09     
neuropeptide uh connecto and you know and there's also     
6:15     
like a hermaphrodite connectome and a male connectome and taking all those data and bring them together so that you     
6:21     
can actually use them together all that information in the same framework so     
6:26     
they have an web interface for that uh they call the connectome toolbox and you     
6:32     
can get there off of openworm dorg so if you go to openworm dogc connectome     
6:37     
toolbox you can get to that Tool uh he also has been developing with     
6:44     
another student a large language model that is uh open or C Elegance specific     
6:52     
what I mean by that is that you can they they basically took they've taken a a     
6:57     
larger language model one of these large language models where you get a training set and so you have a pre-trained     
7:04     
language model and then you can train it on Specialized literature so I think we     
7:10     
talked about this with the levven bot at one point where someone took Michael Levan's work and they trained a large     
7:16     
language model that was pre-trained with you know langu English language trained     
7:24     
material and they developed this bot that would like answer questions in the style of Michael 11 and based on his     
7:30     
papers and things like that so you can do that with openworm now too or at least with the     
7:36     
cigan uh literature so if you want to know for example you know what a precursor of a     
7:43     
certain neuron is in the connect D you can find that out and it brings up the     
7:49     
answer so I was playing with it a bit that was nice it was a nice tool so yeah por egg's been doing a lot of work he's     
7:55     
been getting funded through various agencies I think     
8:00     
uh he's got students working on different initiatives so he's really been making a lot of     
8:06     
progress on things uh and then vahed Gumi who joined     
8:11     
us in Eva worm back in the earlier part of     
8:17     
2024 he's been working on some things too and he had mentioned some things that he was working     
8:24     
so so that is where we are with uh open one so it's very still very active there     
8:31     
was a lot of discussion about how you know how to stay relevant because you know there's this     
8:39     
there are a lot of projects that are going on they're kind of nibbling at the edges of what openworm is doing where     
8:44     
they're kind of there's an interest in doing what open worm is doing and     
8:50     
getting people aware of those tools or even collaborated with people who are doing things that are complimentary I     
8:56     
think we've discussed this in dilor quite a bit so you go back to those meetings and you'll see that you know     
9:03     
there's this like this group out of China called meta worm I think we talked about their paper where they uh started to build     
9:11     
their own tools and then they kind of used some of open worm's tools and it's you know so you get groups that want to     
9:17     
do things and you know should we how at what level should we be collaborating     
9:23     
with it should they just be using the tools or should we be actively collaborating Etc ET Etc so that's all     
9:31     
fun um yeah so there's a lot going on there     
9:36     
so that was on Tuesday and then on Thursday we had our cybernetics meeting where we talked about this new paper     
9:43     
from Mike 11 on memory and uh you know memory as sort     
9:50     
of you know where as interesting because the paper he mentioned talked about     
9:56     
memory as the sort of flexible system he talked about memory with respect to     
10:02     
sort of the salience of things rather than it being this sort of camera and     
10:08     
then talked about how uh you know we talked about the     
10:13     
engram in this meeting and how there's been the search for the engram and how it's     
10:19     
been you know a varying levels of success and then he talked about the     
10:25     
engram as well in this paper and pointing out that the engram you know may not be a thing it may be a     
10:31     
distributed phenomenon in these networks of encoded     
10:37     
information and so forth so he talked about that and then talked about memory in the context of     
10:44     
metamorphosis where you go from a caterpillar to a butterfly and this is where the caterpillar mes into a cocoon     
10:51     
part of the morphology gets decellularized and     
10:57     
then you know the remain of the phenotype gets recellularized and then you want to put the     
11:03     
butterfly one of the interesting things about that process is that memories are retained across that process so there     
11:10     
are neural cells that get transformed presumably and some way but they retain     
11:16     
the memories of the caterpillar but there are some memories of course that the caterpillar doesn't need anymore so     
11:23     
do those get reclaimed or they're like uh you know precursor memories that     
11:30     
kind of flourish when the butterfly is a butterfly what's going on there so there     
11:36     
was a lot of that so that was a good discussion um that was led by Amanda     
11:41     
Nelson so that was our week in orthogonal uh so that's that's good and     
11:48     
then um so I wanted to talk about the NIH neuro AI conference so let me go get     
11:56     
that up okay so we're going to put this link to the video cast here we see it's     
12:01     
here this is the naroi workshop this is the Wednesday one there's a Tuesday one as well but you can basically see     
12:08     
actually NIH has video casts of all their meetings here so this is this is     
12:14     
The Advisory Board and from August 2023 so they have all these up so we'll start     
12:19     
here this is the uh website here where they talk about the brain initiative so     
12:25     
the nuro AI Workshop is kind of growing out of this brain initiative the NIH has     
12:31     
sponsored this this is 10 years of brain a decade of innovation this is a brain     
12:37     
research through advancing Innovative neurotechnologies initiative and the short hand for that is brain you know so     
12:45     
that's great uh you know it's one of those acronyms they have to kind of fit or shoehorn into the acronyms so um but     
12:54     
anyways that's what they're that's where they're going from so there are a lot of funding opportunities under grain     
12:59     
one of them being the snaro AI initiative so this is uh a post on Blue     
13:05     
Sky say Blake Richards who was a a presenter at this Workshop uh so I'm going to go through     
13:11     
this post a little bit and this is is kind of pointing to his presentation that he gave so uh he says I work in     
13:19     
neuro AI a growing field of research which many people have only the haziest     
13:24     
conception of it as way of introduction to This research approach I'll provide here a     
13:29     
very short thread outlining the definition of field I gave recently at our brain neuro AI workshop at the NIH     
13:37     
so yeah he was there he presented he had some really interesting insights some interesting nice looking slides so this     
13:44     
is one of the slides here uh the usual answer that people give is that it's research that creates a virtuous cycle     
13:51     
between neuroscience and AI so this is the sort of the view here where you have     
13:57     
Neuroscience machine learning or I machine learning influences Neuroscience by interpreting and     
14:03     
analyzing data Neuroscience influences machine learning by inspiring novel     
14:08     
Solutions and if you you know that's was kind of the tenor of this entire Workshop was that you had people who     
14:16     
wanted to use machine learning to analyze Neuroscience data you had     
14:22     
machine learning people wanted to use Neuroscience or in fact some computational neuroscientists who wanted to use     
14:29     
machine learning or they want to use Neuroscience to inspire novel machine learning Solutions and that's the usual     
14:36     
meaningless answer as Blake puts it so this is usual     
14:41     
answer research creates a virtuous cycle between Neuroscience in AI I've given this definition as well in the past but     
14:48     
if forced I would admit that it's fairly vacuous as a definition and I think     
14:54     
that's true because what's a virtuous cycle you know like we can and say that     
15:00     
if I you know um if I employ you and I pay you underpay you for your     
15:08     
labor but I pay you that's a virtuous cycle right it's not a virtuous cycle     
15:13     
but you could make that argument I guess um but so that's that's kind of     
15:19     
the vacuousness of it it's just some relationship and you know you say it's a     
15:24     
virtuous cycle it just means that they both benefit somehow but it's hard to see that like you know the it seems like     
15:31     
there's a a difference in scope in terms of these contributions so being sort of the data analysis     
15:40     
appendage of Neuroscience is much less beneficial     
15:46     
than being able to inspire novel solutions for architectures so um the more practical     
15:53     
answer is that it that it is researched that either one uses AR icial neural     
15:59     
networks and models at similar levels of abstraction to understand the brain     
16:05     
which we have from like you know our uh you know we have neuromorphic     
16:12     
Computing we have other types of models that just kind of abstract things from the brain and use those as sort of a     
16:19     
model of information processing or two uses Neuroscience ideas to try to     
16:25     
improve the artificial neural networks used in AI so that's still kind of the same thing     
16:32     
um but it's just more concrete as he points out um it hides the real     
16:38     
philosophy so he gives us practical answer research that either one uses     
16:44     
artificial neural networks to model the brain or two uses neuro neuro ideas to     
16:50     
improve a Anns for AI and so this is although this is kind of refining that     
16:56     
first vacuous definition it hides a much deeper disciplinary     
17:02     
turn so I think the proper definition is that narrow AI is the realization of the     
17:08     
original promise of cybernetics and connectionism so that's something that we've talked about in this group and     
17:14     
that's kind of our way of viewing ear I think that's actually an interesting     
17:19     
point um that you know you have these sort of we had cybernetics is sort of     
17:24     
this thing that was inspired by the brain it's not     
17:29     
AI but it gives us these models that we can then use maybe for AI or have it has     
17:36     
some computational value it has some theoretical value so you could turn     
17:42     
around and use it in neuroscience and it's its own own thing it stands on its own so you know within     
17:49     
neuroscience and machine learning we might insert a card in this diagram that is cybernetics and cybernetics might you     
17:57     
know be able to you know influence both machine learning and Neuroscience and then there's a feedback to     
18:05     
cybernetics so that's that's one and then connectionism of course is where we have these kind of networks that are     
18:12     
deep learning networks but they're connectionist networks and connectionist networks are a broader class of models     
18:19     
so we can use that sort of connectionist philosophy to build other types of     
18:25     
models that are influenced by the brain so like if we're talking about IC Computing I mean synaptic Computing are     
18:32     
kind of also connectionist models because you're connecting from say like     
18:38     
a you know a set of dendrites to the cell body you're     
18:43     
collecting them you're summing them you're doing you're performing operations on them you basically     
18:49     
generate a bunch of weights and rules that then you could use to say this is how this information is processed in a     
18:57     
single neuronal unit then you have other sets of Weights that follow from that so     
19:03     
this is interesting um so cybernetics and connectionism and     
19:08     
there connections between those two of course that we haven't talked about much     
19:13     
in the meetings but that this is sort of like our approach and just put into words and     
19:20     
it's a general science of intelligence focused on Parallel distributed systems control learning so this card actually     
19:27     
talks about that uh rather than continue the battle in cognitive science we have     
19:33     
dropped the endless philosophical debates and grandio ideas and focused on a progressive research program of     
19:39     
Science and Engineering because that is what's paid off for us in the end so     
19:44     
again a general science of intelligence founded on Parallel distributed systems control and     
19:51     
learning and then finally uh obviously disciplinary boundaries are blurry and I     
19:57     
don't want to gatekeep anyone for example telling people they're not allowed to color research n AI which of     
20:03     
course is often the case in disciplines but I personally like this definition     
20:09     
and think it provides the appropriate links to the wining engine philosophy of this new field so this is good um yeah so that's     
20:17     
uh Blake Richards and then uh yeah so     
20:23     
that's that's that then let's go to the uh some of the slides that were presented there um this is the website     
20:30     
for the brain neuro AI Workshop this is the agenda so it was uh split over two     
20:36     
days and they spent a lot of time on these guiding questions so you know they would have like discussion panels every     
20:44     
session morning and afternoon morning and afternoon and they would have these questions up on a slide where you could     
20:50     
see them and you know it would kind of lay out the agenda and of course there     
20:55     
were speakers who did a lot of different uh talk about a lot of different things let's start with on the path     
21:02     
forward so this is a summary of discussion from mpb this was a workshop on neuromorphic     
21:09     
principles in biomedicine and Hardware so this is a different conference and kind of leading into this one so this is     
21:16     
taking a neuromorphic approach uh the first is leveraging the algorithms size     
21:22     
weight and power benefits of neuromorphics but do not be overly prescriptive and they say     
21:29     
that means thinking physor in other words you know a lot of the issues of size and weight of power     
21:37     
of the processors and the hardware can be thought of as a physiological     
21:43     
system and so if you're thinking about neuromorphics which means you're using     
21:48     
uh the principles of the nervous system at the level not just of connections     
21:54     
between cells but also this deeper Hardware part like the physiology of the     
22:00     
brain uh then you should be able to model that as you know kind of like a physiological system rather than just     
22:07     
kind of copying what the brain does in terms of its     
22:14     
architecture the second one is focus on clear clinical needs rather than technology-driven     
22:20     
Solutions the third is that you know people are interested ultimately in building these implantable wearable     
22:25     
prosthetic devices that will benefit from new materials architectures and     
22:32     
neuromorphics uh develop better better infrastructure for sharing expertise     
22:37     
data technique and tools that's always a thing that people mention whether that happens or not is an open question we'll     
22:44     
talk about scops in a minute to kind of drive that home development of standard platforms     
22:51     
interfaces and software encourage more interaction between academic research industry and     
22:57     
clinicians develop better Frameworks to design and evaluate adaptive     
23:02     
systems develop and share multimodal data sets from from Real World situations and develop theoretical     
23:09     
analysis framework for neuromorphics and biom medicine and Healthcare again from this workshop on neuromorphic principles     
23:15     
in biom medicine and Healthcare on materials and integration challenges um make points uh there are     
23:24     
exciting and exotic materials and architectures being developed that ideally suited for neuromorphic     
23:30     
application there's this need for new electronic materials that are better matched to tissue so you have materials     
23:37     
that stretch and conform to their surrounding environment you have materials that are     
23:43     
biocompatible in other words you don't want to put metal or you know Plastics     
23:49     
of different types in embed them in the nervous system you want things that are     
23:55     
um biocompatible you want things that can self-heal you don't want to have to keep     
24:00     
fixing things and going in and making sure that they don't you know if they break that you go in and you fix it     
24:06     
manually you want them to heal themselves low immune response you don't want the implants to be rejected an     
24:14     
ability to interface directly with tissue so you want them to be able to actually stimulate tissue or do     
24:22     
something else record from tissue and not be invasive in any way then you need a     
24:29     
better need for better tools and standardized approaches for fabricating these materials into devices noting that     
24:35     
currently each lab must develop their own techniques from scratch uh this is on neuromorphic     
24:41     
principles uh cautioned against being too precious about strict biological     
24:47     
mimicry suggesting a broader physor framework so this is where you don't     
24:52     
necessarily want to copy the biological substring like you don't want to copy     
25:00     
neocortex uh at least in this in this case that's what they're suggesting you want to have a physor system that sort     
25:07     
of behaves like a nervous system but isn't modeled after any specific nervous system which makes sense because if we     
25:15     
don't know how the brain works we can't really replicate the brain and expect it to work so this is you know kind of     
25:21     
moving in a direction where we at least have a good appreciation for what we have and how we can     
25:29     
control term neuromorphic itself can be problematic in industry in clinical contexts because a perceived immaturity     
25:36     
risk yet AI is accepted so this is interesting that people have problems     
25:41     
with neuromorphic because they don't see it as a mature technology but AI is likewise a immature technology people     
25:48     
accept that much more freely I mean these are just things that they're pointing out they might be     
25:55     
barriers to adoption they might be things that are needed Etc neuromorphic principles of offer     
26:03     
valuable approaches needs un Focus uh needs to focus on concrete problem     
26:08     
solving so this is where you know we we can mimic things that are neuromorphic we can mimic like biological substrates     
26:16     
but we want to be able to solve problems with them not just replicate them uh talking about benchmarking this     
26:23     
stifles creativity and Discovery some people disagree obviously     
26:28     
benchmarking is needed to get a handle on performance but thinking always about benchmarking and how things perform at a     
26:35     
benchmark can also reduce your ability to make new novel things then key     
26:42     
technical advantages ofur a morphic approaches as opposed to AI standard AI     
26:48     
approaches are power efficiency which is important for say like implanted devices real-time     
26:54     
processing capability the ability to process data with low latency directly at the     
27:00     
sensor natural honor facing biological systems speaking the same language as neural tissue in resilience and     
27:08     
adaptability so how biologically inspired stochastic processing can     
27:13     
provide robustness it say speaks to sort of the The partially stochastic nature of     
27:20     
neural activity and being able to leverage that so this is session four     
27:26     
I'll just kind of work through these as I pulled these out but so session one was Tuesday Morning session four was     
27:32     
Wednesday afternoon this was the session that I just talked about so again you're     
27:37     
talking about neuromorphics robotics intelligent Computing um they had some goals and     
27:44     
guiding questions so the goals in this session were to discuss potential future neuro AI principles and Technologies     
27:52     
realtime personalized learning systems with appropriate metrics and their translation across agencies so you know     
27:59     
this is in the NIH so they have different initiatives like mental health     
28:05     
disease uh other types of things uh applied research so you know they want     
28:11     
to be able to leverage it across they what they're doing understand how other government     
28:16     
agencies or stakeholders could benefit from brain data sets and knowledge bases brain being the initiative I just     
28:23     
talked The Guiding questions are threefold so the first one is what Foundation advances in neuro AI are     
28:30     
needed to enable energy efficient neuromorphic Computing adaptive robotics     
28:35     
or intelligent neural interfaces with the potential to transer neuroscience and brain health what kinds of metrics     
28:42     
are needed to evaluate progress in both technical capabilities and translational     
28:47     
impa number two what infrastructure and platforms are needed to enablement of innovative scalable Healthcare     
28:54     
technologies that are affordable secure and user friendly how can brain initiative resources and     
29:01     
cross agency Partnerships accelerate this and then three how can neuroi     
29:06     
approaches the Technologies dve reciprocal advances between fundamental neuroscience and transformative Health     
29:12     
Technologies medicine Ai and orur Robotics while ensuring ethical use of     
29:18     
neural data and meaningful incorporation of clinician patient perspectives so let me pull up the the     
29:25     
goal and guiding questions for session two this is exploring the structure and functional convergence of deep neural     
29:31     
Nets and brains so uh this was Tuesday afternoon the goal of this was to     
29:37     
explore how large Brain data and computational tools may enable advances in eari Frameworks theories models and     
29:45     
metrics describing approaches for comparing natural intelligence and brain data with AI models so this is where     
29:53     
again we're kind of thinking about neuro Ai and we're thinking Beyond just kind of the Frameworks to a lot of these     
30:00     
different theories and models and ways you can put them into the world so the guiding questions are one how can we     
30:07     
develop and validate metrics for comparing biological and artificial systems that capture meaningful     
30:13     
computational principles while avoiding overfitting to specific comparison     
30:19     
methods or oversimplifying complex neurodynamics so this is where we need     
30:24     
to kind of make create metrics from from our nrow AI system and how can we make     
30:30     
those robust question two what Frameworks and approaches can help identify meaningful     
30:37     
comparisons between biological and artificial systems considering different levels of abstraction from algorithmic     
30:44     
principles physical implementation which computational principles in brain systems are more or     
30:51     
less difficult for nuro AI models to capture so this is where we have     
30:58     
uh you know we have to kind of first of all think about what are the computational principles of brain systems and then two can we capture them     
31:05     
in our models question three how can brain initiative data sets be effectively     
31:11     
leverage to evaluate and validate theories about shared computational principles while accounting for the     
31:18     
different requirements of hypothesis driven science and large scale projects that develop neuro AI models and     
31:26     
resources and then finally what infrastructure benchmarks and standardized platforms will be needed to     
31:32     
enable ethically and scientifically rigorous measurements comparing human or animal data to neuro AI models the     
31:40     
questions for session one uh this is defining neuro AI for brain which is     
31:46     
this brain initiative gaps challenges and opportunities this is this was on Tuesday morning first session so the     
31:54     
goal here is to establish a vision for neuro AI is a conver urgent framework where neuroscience and AI are reciprocal     
32:01     
advances through shared principles identify concrete opportunities for brain initiative resources which     
32:08     
biological and artificial systems The Guiding questions here how can brains     
32:13     
large skill data sets be structured and leveraged and develop neuro AI resources     
32:18     
such as neuro Foundation models or digital twins while balancing the need for both hypothesis driven science and     
32:26     
high entropy naturalistic data collection I guess what they mean by that is that you have a lot of I don't     
32:33     
know what they mean by high entropy but basically where you either a very     
32:39     
constrained sort of controlled experiment we testing a hypothesis where     
32:45     
you're just collecting data from the world I guess that's the thing question two how should we expand     
32:52     
our understanding of neural computation uh to incorporate broader biological system systems including glea     
32:59     
neurom modulation and development of evolutionary perspectives and ways that inform both theoretical advances and     
33:07     
practical neuro AI implementations so this is something I think that we're interested in quite a bit at least the     
33:14     
way we talk about things uh that's that's a a good question I think to kind of unpack maybe     
33:22     
in the future um I'm going to make a note of     
33:27     
that actually show all right uh question three how can     
33:34     
experimental platforms and Technologies support a discovery Loop that integrates theory development model validation     
33:41     
hypothesis generation and datadriven approaches while meaningfully incorporating physical embodiment and     
33:47     
real world Behavior then question four what infrastructure tools and coordination     
33:53     
mechanisms are needed to enable collection and Analysis of naturalistic neural and behavioral data at Scales     
34:01     
Beyond individual Laboratories while maintaining rigor and reproducibility so session three this     
34:08     
this is this was Wednesday morning advancing theory for brain through neuromorphic Computing embodiment     
34:14     
physical intelligence so you know this is sort of this embodiment aspect to     
34:20     
narrow AI which again this is something we're interested in but is not like     
34:25     
something that um you know is kind of at the four of a lot of the     
34:34     
discussions and I'm taking another note     
34:39     
here and so the goal here is to create new theories for Neuroscience through large scale neuromorphic Computing     
34:46     
neurod design principles and complimentary models and incorporate principles and embodiment in physical     
34:52     
intelligence so this is very uh sort of embodied a     
34:59     
Workshop question one how can neuromorphic approaches help us understand fundamental principles of     
35:04     
brain computation while also advaning more efficient artificial systems what     
35:10     
determines whether neuromorphic Computing serves primarily as a modeling and simulation platform versus providing     
35:17     
emulational biological processes to achieve deeper theoretical insights into     
35:23     
neural computation question two given the coal evolution of Hardware algorithms in both     
35:30     
technology and biology how do we ensure our choice of abstraction level an implementation approach reveals     
35:36     
fundamental principles rather than artifacts and available technology which biological mechanisms     
35:43     
are essential to implement versus those that can be simplified this is a question of looking at the co-evolution     
35:50     
or Hardware algorithms and how you abstract that neural system at both     
35:56     
levels question three how can different approaches to physical implementation from neuromorphic     
36:02     
Hardware to bioinspired Robotics and physical or ins cical model in the loop systems Advance their theoretical     
36:09     
understanding of neural computation what role should embodied approaches or physical interaction play     
36:15     
in this neuro AI Discovery so this is uh a slide where     
36:21     
they kind of get into brain's definition of neural AI for this Workshop so I talked about um Blake Richard's     
36:28     
definition of neuro Ai and the standard definition of neuro AI but what about the brain definition of neuro and so     
36:36     
that is where we have these uh Five Points so the first is neural wayi     
36:43     
leverages convergence between neuroscience and AI the drive reciprocal     
36:48     
advances and understanding natural intelligence and AI again this Loop this     
36:53     
discovery Loop this Workshop seeks to collect broad community input to identify potential future priorities and     
37:01     
opportunities for neuro AI Workshop participants are encouraged to broadly consider their disciplinary approaches     
37:08     
in neuro AI that extend to embodiment neural control of complex behavior and     
37:14     
evolutionary or comparative perspectives the fourth is brain the brain neuro AI Workshop seeks Insight     
37:21     
from diverse related and adjacent disciplines so it's embodied cognition     
37:26     
bio inspir robotics neuromorphic Computing and more then participants should consider what kinds of metrics     
37:33     
are needed to enable coordinated advances in a so this is focusing kind of on Energy     
37:41     
Efficiency uh some other types of things that kind of build on top of that and so     
37:48     
forth this is actually interesting I'll get into the scops paper later but uh     
37:54     
this is a slide from a talk on scops and I think talked about this in one of our     
37:59     
meetings already maybe last week where it was brought up I think Morgan brought it up where there's this idea of so it's     
38:07     
like based on the idea of devops devops being like software development and     
38:12     
operations management scops is like scientific uh you know scientific     
38:19     
management or scientific development scientific research and operations     
38:24     
management basically this sort of project management for a scientific large scientific projects so uh this     
38:33     
shows kind of the five levels of scops maturity so you know we have the initial     
38:38     
level which are ad hoc processes bespoke development level two     
38:43     
is managed processes or established processes these are repeatable Ro     
38:49     
specialization and quality control level three is Define sharable processes we     
38:55     
have open source ecosystems Fair data standards which is the     
39:01     
findable uh accessible interoperable and reproducible standards and fair     
39:08     
workflows level four is scalable automated workflows this is the scops     
39:14     
pipeline collaborative environments and team flow which just means like workf flows and teams and then level five is     
39:21     
optimizing you have Clos Loop Discovery where you have ai plus humans in the loop so this is where where you kind of     
39:28     
used that to bootstrap new discoveries this was another discussion on what they     
39:33     
call AI versus ni artificial intelligence versus n     
39:39     
natural intelligence so this is kind of the slide where they talk about the     
39:44     
differences here um they talk about machine learning models being with a     
39:49     
generic regular architecture that has a week prior so     
39:55     
you know this is where we start with a random Network it's fully connected or you know has no structure something     
40:01     
that's trained and shaped and the regular generic regular architecture is     
40:07     
this weak prior so doesn't predict things out of the box has to build predictions from the training and he     
40:14     
calls this The Blob which means that it's not shaping in any way of course in natural intelligence we know that you     
40:21     
know development can shape uh neuro architectures in various     
40:26     
ways there is there various aspects of innate abilities or innate structures     
40:32     
that are formed and so we start we have a starting point that's very     
40:38     
different uh then there's this other point hope to force differentiation emergently data intensive test specific     
40:45     
learning and that's called shallow adaptation which is what we have with AI     
40:51     
so we use a lot of data we kind of shove it down the model's throat we use test     
40:57     
specific learning and that's shallow adaptation because it doesn't necessarily generalize nor does it     
41:03     
provide any real insight it's just a lot of data so the problems with AI versus     
41:09     
natural intelligence number one the models are task domain specific the second is going from     
41:15     
scratch to complex functionality is hard and data compute intensive number three is no control     
41:21     
over the model that emerges we get weird models of things number four is risk of unnatural     
41:28     
and appro lat and failure modes again brittleness it's not robust and then ml     
41:35     
based views are unlikely to scale all to General complex general intelligence     
41:40     
these include well we have multimodo models but then the ones that are unlikely to scale well are model merging     
41:47     
convergent learning and the bitter lesson from the Su so interesting kind of summary of what those differences are     
41:54     
there was a talk on uh dendritic computing and dendrites so you know this is kind of like the perspective on what     
42:02     
dendrites contribute to Computing this is a paper pug Colo said all current     
42:08     
opinion in neurobiology in 2024 so that's sort of the reference and they     
42:14     
talk about dendrites being like this difference there being a difference between a point neuron and dendritic     
42:20     
neuron that the dend dendroides do a lot of highend processing that you don't get     
42:28     
with like a connectionist model of neurons or units and then you have this     
42:33     
sort of similar performance uh they talk about how dendritic artificial Neal     
42:38     
networks use a different learning strategy so dendritic Ann is mixed has     
42:44     
mixed selective nodes uh Vanns are class specific nodes     
42:50     
so these are differences in the learning strategies of these two different types of networks and then we have dendrites     
42:56     
in our artificial intelligence this just shows some of the things that endres can     
43:02     
sort of uh contribute to this area so you have a dendritic input versus a     
43:08     
somatic input it can do things like multiplexing credit assignment and error     
43:14     
back propagation so there are these uh different sort of things about what we     
43:20     
need so there are three slides and what we need uh to do I guess effective nrow     
43:26     
AI uh the first is accessible High Fidelity data so you know this this     
43:32     
speaks to open data and some of the standards and databases that we have such as Dandy neuro dat Without Borders     
43:39     
and bids are all tools that we have you know it's nice that we have these things     
43:44     
but it's kind of difficult still to use them in multiple contexts plus you know     
43:50     
people share their own data from their own labs and they fit them into these Frameworks um     
43:57     
so that's you know and then we have small scale data sets that do not differentiate between     
44:03     
models uh we need more data collected with models in mind and we need to     
44:08     
consider the signal to noise ratio of our data sets and then we have opportunities for     
44:15     
both bre to build both breadth and depth breadth being multi-stem and multi-domain depth being causal     
44:21     
manipulations and detailed neural activity so we can sample from a wide range of neural process cesses or look     
44:29     
deeply at one neuro process and get the causal aspects of it and the detailed     
44:35     
neural activity correct we need both of those really to do effective     
44:40     
neural what we need to is comparable model testing so we don't have to or     
44:46     
should not agree on how to build the next best models but we do need a clear measure of a model Delta which means the     
44:52     
difference between two models leads to robust improvements and so we need benchmarks for this this is where he     
44:58     
talks about brain score which is this competition where they tried to find     
45:04     
benchmarks for different uh you know looking at different models and how they     
45:10     
compare to I think it's neuroimaging data but basically they have this brain     
45:16     
score website that he was referencing and then what we need three are models of brain intricacies so we     
45:23     
need to have this sort of breadth and depth we need to breadth which is     
45:28     
complex cognition so we want to think about language we don't want to just think about the language centers we want     
45:34     
to think about knowledge and reasoning we in fact want to think about the entire language Network and we want to     
45:40     
think about things like emotions and social inferences and multimodal processing and all these other things     
45:46     
that go into say like language and so instead of just having like some sort of     
45:54     
Transformer to use in in a language model we want to have these neural systems that are very wide and then we     
46:01     
want to have depth or biological detail so we want to know where things happen in the brain What mechanisms are indeed     
46:10     
responsible for them we want to have models of embodiment and biophysics so     
46:15     
we want to have all this biological detail as well so one of our goals in neuro Ai and I thought this was     
46:21     
interesting is where we're trying to understand the emerging phenomena in biological brains so it means that you     
46:28     
know we have of course this emerging phenomena in brains we have things like population activity and plasticity rules     
46:35     
that kind of grow out of the representation we use for them and of course we know that different neurons     
46:41     
will you know contribute to these Collective representations that we can then use so our models     
46:48     
of current AI are based on sort of the computational principles of brains     
46:56     
representation but we know that that's you know kind of built from parts from neural activity so     
47:04     
there's this emergent aspect that we need to capture better and so you know     
47:10     
we have all these different modalities and tasks and different things happening at the neural level and somehow that     
47:15     
builds a representation that we then use in AI we just simply use that representation and     
47:21     
don't worry so much about the details but neur way I would want to understand     
47:26     
those Det details and perhaps that helps us to refine our representation so uh     
47:32     
there was a lot of talk about dendrites uh this is uh Haba Bahan who's     
47:38     
done a lot of neuromorphic computing work and he has this paper dend dendr     
47:44     
Centric learning for synthetic intelligence so this is a good paper where it talks a lot about uh sort of     
47:51     
the neuromorphic aspect of uh you know synthetic intelligence     
47:58     
how you can kind of work on both this aspect of being biologically relevant     
48:04     
biologically s but also working on problems like energy consumption and     
48:09     
things like that so there was some talk of you know using insect uh nervous     
48:14     
systems a sort of inspiration and one of the slides in that talk was a slide and neuro inspired     
48:22     
ingredients that are missing so you know we have a number of things things that we don't really have in our current     
48:29     
models of artificial uh intelligence artificial neural networks one of these is neurom     
48:36     
modulation so we might have a network topology that is you know something we     
48:42     
don't change we don't change the weights per se we don't change the topology but     
48:47     
what we do change is the function and so we might it might be that we need to have like a certain set of weights and a     
48:54     
secondary set of weights manage this neuromodulation of course we know that neuromodulation is controlled by     
49:02     
hormones other types of uh neurochemicals neuropeptides so we have     
49:08     
this model for doing that and we have the neuropeptidergic connectone for     
49:13     
celegans as just an example of this sort of thing where we can actually incorporate neuromodulation in our     
49:20     
models we also have uh things like rhythms and oscillations which are not     
49:27     
particularly useful for say like uh DNN or other types of neural     
49:32     
networks but are important for robotics because we're trying to model an output of movement often or some other Behavior     
49:40     
that's embodied and so that's an important part they also say there's a special role of     
49:46     
inhibition there's recurrence feedback there are different cell types that need to be modeled so you know not all cells     
49:54     
are generic cells they're they have different functions they have different morphologies Etc there's also non     
50:02     
synaptic signaling and dendritic computation so those are very there is a they stress those two things quite a bit     
50:09     
in the workshop this is the path forward intentional alignment of AI neuroscience     
50:15     
and cognitive science this is actually a nice diagram because it shows kind of how these things kind of overlap so it's     
50:23     
not just neuro AI now it's neurocog AI so you have Neuroscience where you have     
50:28     
neural data with the contribution you have structural priors     
50:33     
which come from cognitive science and then you have your DNN models which come from AI so you have this overlap that     
50:41     
where you have neural data in forming DNN models but then cognitive science provides your structural priors and     
50:48     
together you can build you know a nice set of models so I think that's interesting they includ a cognitive     
50:54     
science in here and and you know it's interesting that they think of this as a     
50:59     
sort of intentional alignment so this is Blake Richard's talk I talked about Blake Richard's take     
51:05     
on this before he talks about uh neuro AI as being this general science of     
51:11     
intelligence bonded on Parallel distributed systems control and learning and then it makes this other statement     
51:19     
rather than continue the battle on cognitive science we have dropped the endless philosophical debates and     
51:24     
grandio ideas focused on a progressive research program of Science and Engineering because that is what's paid     
51:31     
off for us in the end and he makes this other kind of appeal up you know kind of about     
51:38     
cybernetics and connectionism which we talked about he does mention that you know we     
51:44     
we have to think about it in terms of cybernetics and connectionism I think which are kind of the two main     
51:51     
insights uh we don't talk about very much in r on but then original form cybernetics     
51:58     
and connectionism oversold and underd delivered so this is where you know cybernetics wanted to be the sort of     
52:05     
catchall methodology for everything from Neuroscience to economics connectionism was kind of like     
52:12     
that too where they built these connections networks they wanted to solve every problem with them and so it was oversold and under     
52:19     
delivered so needless to say neither of these approaches did that or did the things that they promised it's that's     
52:26     
maybe a lesson for nari first of all but also that it's a lesson for you know     
52:33     
like what is the legacy of cybernetics and connectionism so in the face of these     
52:38     
Grand ideas the clear arguments made by people like Minsky Simon paper Shamsky     
52:45     
Etc were more convincing than the weak demonstrations provided by people like Rosen blet weer Mulla Etc this is     
52:53     
interesting he's making this point that sort of the GOI people or the good     
52:59     
oldfashioned AI people Minsky Simon paper Shamsky they actually were able to     
53:05     
sort of build things and put them out into the world and make Arguments for     
53:11     
intelligence that were much better than the weak demonstrations provided by Rosen blat leer Mulla which more in the     
53:18     
Neuroscience camp or in the perceptron camp which is headed in the Neuroscience     
53:24     
Camp the point is is that you have basically the connectionists the GOI     
53:29     
people versus the perceptron SL cybernetics people and he makes this     
53:37     
kind of differentiation by saying that the latter had weak demonstrations of their principles whereas there are clear     
53:44     
arguments in the first CA so maybe that's a bias of an AI researcher but     
53:50     
it's an interesting point to make why did cybernetics and connectionism not sort of serve as     
53:57     
um Foundation or how much of a foundation did it for um as we talked     
54:04     
about last week you know people are using say like the everan regulator     
54:09     
theorem in various ways so it's not useless it's not NE it was a weak     
54:14     
demonstration maybe at the time but maybe not now so anyways I think that's enough for this uh I think that's I mean     
54:20     
it's very interesting I think it frames a lot of things we've been talking about it has a lot of you know there's a lot     
54:26     
to follow up on but it was a very good workshop and uh I recommend watching it     
54:32     
on the NIH     
54:37     
cast yeah um I didn't I got to like only see little bit of the whole thing and     
54:44     
I'm glad this recap we picked several interesting things to share so I don't     
54:50     
know if um like I could look at the folder or     
54:56     
something but I'd be curious to see some of the other U screenshots and stuff oh yeah I     
55:01     
can share that because there's there's even in terms of like the data     
55:07     
management stuff and the scups things like something I want to look more into for all the the more project manery     
55:13     
stuff we're talking about and other in the Spectrum you know the cybernetics     
55:18     
nway stuff and um a lot of lot of interesting stuff     
55:24     
yeah thank you organ you want to say     
55:33     
something well I'm I'm wondering what what struck     
55:38     
you what struck you is new there in terms     
55:45     
of Nur um so I thought you know like it was     
55:51     
interesting because they had like kind of the neuro AI that maybe like Mila     
55:57     
which was represented by Blake Richards it talks about and then there's like the neuromorphic stuff that was kind of like     
56:03     
brought in so there is this kind of intersection there and it's not even kind of the     
56:08     
same thing they maybe not the same questions but it's interesting that those two things exist I thought that     
56:15     
the Blake Richard stuff on cybernetics was interesting I thought the embodiment aspect was interesting I thought that     
56:22     
you know like the dendri Computing stuff was interesting I think you know when we     
56:28     
talk about neuroi we're really talking about abstractions that are better or different from standard AI where we have     
56:36     
our connectionist model of our cells and we just try to optimize the weights when     
56:42     
in fact you know there's all sorts of stuff going on in the brain that we could use as     
56:49     
inspiration and you know they relate to things like a building kind of     
56:54     
physiology because in embodiment of course we need a physiology ideally we need to build in like things     
57:01     
that relate to like a morphology so yeah I think there's a lot there that I think that that sort of     
57:06     
aspect of it it's really interesting yeah     
57:13     
you no that's that's     
57:18     
um yeah I mean you know     
57:24     
neuromorphic I mean I say is that so I always like to point out you know     
57:31     
neomorphic Computing was was a part of the human brain projects originally you     
57:36     
know like yeah it     
57:42     
wasn't uh yeah but it is good to see it is good     
57:48     
to see there and um     
57:53     
uh and it does speak to that um you know do you do you have     
57:59     
implementations that actually do things yeah     
58:07     
uh it's yeah yeah I mean I I would     
58:12     
almost want there to have been more robotics yeah I don't know yeah I mean I     
58:20     
I liked what you said though about the about the oscillations like there's     
58:25     
not a lot of use of of you know especially as a kind of data     
58:33     
analyst of neuro data you know spend a lot of time thinking about     
58:39     
oscillations yeah but they don't they don't have     
58:45     
um they don't have a big role in     
58:50     
uh neuro AI um but they certainly they     
58:55     
certainly something you think about in terms of yeah     
59:01     
um like Central pattern generators for for robotics yeah and that that kind of     
59:08     
that that like like the the forces on the body in terms of s sof Robotics and     
59:15     
things like that like you know putting putting the fish in putting the fish in water and see you know     
59:24     
putting the dead fish in water it sweat yeah     
59:30     
yeah yeah it's it's it's it's interesting there there was     
59:37     
um Dennis Noble spoke at     
59:42     
um The Institute of Arts and ideas or something like that anyway but he he     
59:50     
was you know do do it his normal thing say that genetics is     
1:00:00     
wrong but uh yeah was was asked something about something about Ai and     
1:00:09     
why aren't why aren't any of these principles used in in AI or something     
1:00:15     
like that I I'm not goingon to do it justice but it it was funny because he was just like he's like you and I are     
1:00:23     
70% water yeah and AI is is like there's     
1:00:32     
nothing yeah anyway and and when when     
1:00:38     
when she said something like so you know so what if we had a water-based Ai and he was just like that's life you just     
1:00:45     
created     
1:00:51     
life but you know it just it's um I mean I I don't I don't know if there     
1:00:58     
was anybody there representing you know agential matter and and um kind of leev     
1:01:07     
you know uh kind of Greater multiscale     
1:01:15     
perspective like like L yeah terms of     
1:01:20     
um um I mean especially in terms of the     
1:01:26     
the kind of     
1:01:35     
the things things in addition to you know the micro multiscale and and things     
1:01:43     
like that but just like the introspection and the the some of the things we talked about like that Dar was     
1:01:49     
trying to build into robotics that again it's just like these all things are     
1:01:54     
these things all exist in kind systems built on the ental matter but to     
1:01:59     
to build a robot that can can assess its own damage and and and do something     
1:02:07     
about it you know these are these are all things that you have to hardcode in     
1:02:14     
yeah like like like Darkness Common Sense challenge which I still think is     
1:02:19     
hysterical that they've got the their their their mission icon is the the     
1:02:25     
robot sitting on a tree branch sawing off the [Laughter]     
1:02:33     
branch I still I still love that that's their actual symbol     
1:02:41     
yeah anyway but but very cool very cool yeah     
1:02:48     
and yeah actually do want to go back to the uh Sops paper someone presented on this     
1:02:55     
this this is the scops paper this is from the archive this is recent this is     
1:03:02     
uh achieving productivity and reliability and data intens and research uh and you're the     
1:03:10     
authors y lots of lots of good people and this is this is what Yar sent us     
1:03:16     
okay yeah oh okay yeah he did yeah and there is y on here yeah love there we go     
1:03:23     
yeah there we go all right so yeah this is and then their argument here in the     
1:03:29     
abstract scientists are increasing lever increasingly leveraging ad dances and     
1:03:34     
instruments Automation and collaborative tools to scale up their experiments and research goals leading to new births     
1:03:41     
have discovered various scientific disciplines including Neuroscience have     
1:03:46     
adopted key Technologies to enhance collaboration reproducibility and automation so they're drawing inspiring     
1:03:53     
inspiration from advancements in the software industry particularly scops or     
1:03:59     
devops uh which is of course develop uh software development and operations     
1:04:05     
research we present a road map to enhance the reliability and scalability of scientific operations for diverse     
1:04:12     
research teams tackling large and complex projects we introduce a five level capability maturity model which we     
1:04:19     
saw in that slide describing the principles of rigorous scientific operations in Project ranging from small     
1:04:26     
scale exploratory studies to large scale multidisciplinary research Endeavors     
1:04:32     
achieving high levels of operational maturity necessitates the adoption of new     
1:04:38     
technology enabled methodologies which we refer to as scops uh this concept is derived from     
1:04:45     
the devops methodologies that have revolutionized the software industry scops involves digital research     
1:04:52     
environments that seamlessly integrate computational Automation and AI driven efforts throughout the research cycle     
1:05:00     
from experimental design and data collection to analysis and dissemination     
1:05:05     
ultimately leading leading to Clos Loop Discovery so these are the discovery Loops that they were talking about in     
1:05:11     
the workshop this maturity models offers a framework for assessing and improving operational practices the     
1:05:18     
multi-disciplinary research teams guiding them towards greater efficiency and Effectiveness and scientific inquiry     
1:05:25     
so the keywords are all kind of scops devops data Ops which is another thing     
1:05:31     
in data science ml Ops in machine learning a capability maturity model     
1:05:38     
which is where you take the capabilities in your workflow and you assess their     
1:05:43     
maturity and you try to build in Greater maturity uh it's just a tool in project     
1:05:49     
management Neuroscience operations research open science closed loop experiment ments     
1:05:56     
digital twin Fair standards reproducible research automated workflows artificial     
1:06:03     
intelligence and AI driven Discovery so they talk about the need for elevating     
1:06:08     
operational maturity large scale science it's basically that you know a lot of     
1:06:13     
scientific research is um not as efficient as it could be and we can kind     
1:06:21     
of you know professionalize experimental workflows and Discovery workflows and so forth and     
1:06:29     
so that's kind of the idea here and then using Technologies to integrate into it     
1:06:34     
so they talk about a lot of different projects they talk about the brain initiative which has uh a couple of     
1:06:41     
components the cell consensus Network and the cell Atlas Network which are     
1:06:47     
building these atlases of brain cell types so there's this connection to the     
1:06:53     
US brain initiative and other initiatives such as the human brain project and the China Brain Project     
1:07:01     
human brain project being EU funded so yeah yeah you were gonna say     
1:07:08     
something oh U no I mean I I was just thinking about how     
1:07:16     
yeah like when when devops kind of     
1:07:22     
became a thing okay and you know what um uh     
1:07:30     
yeah you know be being one of those people that's old enough they could remember     
1:07:39     
before but but I I I distinctly remember you know I mean I I     
1:07:44     
remember I remember one of the things that I really liked about being with     
1:07:50     
neurotech x in San Francisco was that um     
1:07:55     
this was I was around a bunch of young people that were mostly software     
1:08:02     
Engineers right like they were mostly working as software software     
1:08:08     
engineers in San Francisco's taxine you     
1:08:13     
know and and for for many of them that meant working on     
1:08:22     
web scale projects right     
1:08:29     
so the just ideas that that I had as you     
1:08:37     
know a software engineer who like literally was on the first personal     
1:08:44     
computer right yeah like I think I     
1:08:50     
learned some things yeah and and yeah you know again like like them working on     
1:08:56     
on web scale projects that like they couldn't they     
1:09:01     
couldn't couldn't have my mindset right right you know and and like you     
1:09:09     
were already talking about maintaining maintaining kind of like multiple     
1:09:14     
[Music] nodes right and and so yeah distribution     
1:09:20     
and reliability and you know backup U     
1:09:26     
yeah backup servers take over um like these were all things that     
1:09:33     
that they you know you needed a plan for     
1:09:39     
right and um yeah so it was um yeah it     
1:09:45     
was interesting and as as well as yeah some of the     
1:09:51     
library you know and and and that that meant that I had to become familiar with     
1:09:57     
new libraries and new you know I was like why do I need to why do I need a messaging Library you know what would I     
1:10:04     
use this for yeah and um     
1:10:10     
and yeah starting to think about this kind of you know dat data lakes and and     
1:10:17     
you know data data data pipes and     
1:10:23     
um certainly certainly just this this idea that there was you know constant     
1:10:28     
flow of new new data coming in having to have servers ready for     
1:10:35     
it yeah and then and then a lot of the automation was was just to make     
1:10:42     
that to make that kind of continual process uh     
1:10:47     
operate you know so so it's like well obviously you needed to have things     
1:10:52     
checking on stuff and and you know     
1:10:58     
um yeah and you know you you'd see you'd     
1:11:03     
see these new Services appear on Amazon web services that that yeah like you could     
1:11:11     
you could start to think about why these why these were created why did these new why were a why was aw guys adding these     
1:11:18     
new features and and it was because their customers asked you know I mean     
1:11:24     
like so um yeah     
1:11:31     
and so I I I you know obviously I'm probably closest to human connecton     
1:11:37     
project um I I I don't know what     
1:11:43     
micron's um was really dealing with um     
1:11:48     
but it's kind of interesting because it's like to some degree human connect on     
1:11:54     
projects and as as great as it is um     
1:11:59     
again like I I was also quite taken with     
1:12:06     
um just just how little data I dealt with when you think about these internet     
1:12:13     
companies yeah yeah that that that     
1:12:19     
yeah um and it's both to the the need for cloud     
1:12:27     
it's just like obviously nobody processes stuff on their laptop yeah you know but you know you could with a     
1:12:34     
properly with a really big hard drive like you could do you could deal with a lot of you can connect to bring dat     
1:12:42     
right it's just yeah but I I I I haven't gone through     
1:12:47     
the the scops paper in detail I I recognize some of the people there in terms of like um dictor who's with     
1:12:56     
neurod dat Without Borders is he National Labs guy I think he's got a     
1:13:02     
company now to I forget what it's called um but I saw like data joint is one of     
1:13:08     
the one of the like one of the authors has a data joint email     
1:13:15     
address um so it's it's interesting it's an interesting mix of kind of like     
1:13:21     
National Lab people open source scientific software development people     
1:13:29     
you know that's kind of kind of private but kind of Open Source you know what I     
1:13:37     
mean yeah and and then uh I saw Petra there who's like a virtual brain virtual     
1:13:44     
Brain Project [Music] yeah yeah all     
1:13:52     
right uh Jesse says uh yeah that the     
1:13:58     
figure where we talked about the Cai neuro and AI it's half of the hexagon     
1:14:04     
kagai hexagon it's interesting yeah uh and then I did I did think it was funny     
1:14:11     
when he said or I think Blake     
1:14:16     
said we decided to put down you know to forget about all the philosophical debates and actually do something     
1:14:26     
yeah um speaking of Robotics I saw that the info for EI 2025 is now yeah so     
1:14:32     
that's good that'll be coming up I think in April right yeah so let me get on to some other things uh a lot of good     
1:14:39     
things happening these days uh with open source U so the first thing is this is     
1:14:46     
the Bren brain emulation Suite so this is uh Stefan uh     
1:14:53     
dorety and his project brain suite and he's actually adding to it I just saw     
1:14:58     
some this morning he hosts a lot of this stuff on uh the open science framework     
1:15:04     
so these are like some of the things that are going on uh looks like he's done a lot of uh well these are all the     
1:15:12     
presentations I think on brenberg vehicles and developmental brenberg     
1:15:17     
Vehicles so this is the incf presentation in 2019 he gave this is the     
1:15:23     
eii workshop in 201 21 this is uh an introductory     
1:15:29     
presentation extending dynamical systems theories models and body cognition and     
1:15:36     
then this is the a PDF of the EI Workshop so he's got all these materials     
1:15:41     
up here I'd kind of forgotten about this but he's reorganizing them uh yeah this is all this this is     
1:15:48     
good stuff thank you for posting this oh this is uh     
1:15:57     
so this is an OSF stub let me put it in the chat it's     
1:16:02     
just kind of something he's published um for that for that project R     
1:16:09     
and then there's a GitHub repository for Bren brain off of the oral group     
1:16:16     
GitHub so that's a different thing but this is like a lot of the documentation basically so yeah there also     
1:16:24     
Publications we have the the different uh main so this is the     
1:16:30     
Contin embodied learning paper which I'm actually trying to get out in the uh in     
1:16:38     
in the proceedings this is the neuros Sim manuscript from artificial life and     
1:16:44     
then this is the conference paper we did at artificial life back in 2020 so this is a nice set of references     
1:16:52     
for that broad project     
1:16:57     
okay uh then I wanted to to turn our attention to something that numenta is doing so numenta of course is the script     
1:17:05     
that they're doing uh what they call hierarchal temporal modeling which is where they're taking a column of     
1:17:12     
neocortex you know we know that neocortex is six layers and that it's organized in these columns and the     
1:17:19     
columns are repeated across neocortex so they're they're uh sort of     
1:17:25     
philosophy is to take these columns and use them as computational units and then     
1:17:30     
use them to program like things um so this is what they're trying to do and so     
1:17:38     
this is a press release from newa where they're talking about their thousand greens project so um if you're     
1:17:47     
not aware um U Jeff Hawkins who is one of the inventors of the Palm Pilot he     
1:17:55     
developed this framework a you maybe about 20 years ago maybe 15 years ago     
1:18:02     
where you know they're doing this comp computation on these cortical     
1:18:07     
columns and he he's written a couple of books on it um on intelligence which is     
1:18:12     
one book and then it talked about the Thousand reins and so the Thousand     
1:18:19     
Marines I think refers to these columns putting these things in parallel or yeah in parallel and so um so this talks     
1:18:27     
about numenta La launching their thousand Marines project providing open source sensory motor learning Frameworks     
1:18:33     
to power a fundamentally different approach to AI so basically what they're doing is they're open sourcing this     
1:18:39     
thousand brains project and they're bringing it to kind of the user     
1:18:45     
so this is uh Numa Incorporated is set to make a profound impact on the field     
1:18:51     
of artificial intelligence at the launch of the Thousand Marines project uh aimed at pioneering a new era     
1:18:57     
brain-based AI that addresses the limitations of deep learn uh so they've been working on this     
1:19:03     
internally and now they've released this as an open- Source model for sensory motor learning based on the principles     
1:19:10     
of the Neo cortex outlined in the Thousand Rings Theory this is the Thousand Rings theory of intelligence book that Jeff Hawkins has     
1:19:18     
published so the Thousand brain project is here this is again neuro AI     
1:19:25     
um and this is based on the thousand Marines theory of intelligence um since then we've been     
1:19:30     
thinking about how to apply our insights about the neocortex to artificial intelligence is described in the     
1:19:37     
Thousand brains Theory it is clear that the brain works on principles fundamentally different from current AI     
1:19:44     
systems to build the kind of efficient and robust intelligence that we know humans are capable of we need to design     
1:19:50     
a new type of artificial intelligence this is what the thousand R's project is     
1:19:56     
about so that's what they're trying to do here um and so they have this uh open     
1:20:03     
source framework on GitHub um and so yeah it's available and     
1:20:09     
there's like a discourse server that they have for you know they used to have an open nice open source community and     
1:20:17     
sadly their open source Community manager died suddenly and so U he used     
1:20:22     
to do a lot of like live live streams of this sort of stuff so yeah um they have     
1:20:28     
a lot of things on YouTube and discourse and they have a lot of good documentation this is something that you     
1:20:34     
know if people are interested in adopting this framework and working with it that's     
1:20:40     
available um yeah yeah the the woman who     
1:20:45     
ran nurx San Francisco originally was a     
1:20:51     
Sofer engineer at nement okay yeah so we I got to I mean     
1:21:00     
back then you know back then they were still     
1:21:05     
um they were still kind of like an anomaly detection company yeah yeah uh     
1:21:13     
um yeah yeah anyway but he's he's been     
1:21:20     
um I forget now which which year it was but he's given the Keynote at the human     
1:21:25     
brain project annual meetings and things like [Music]     
1:21:31     
that so that's interesting um I definitely will check out the event to     
1:21:39     
December 4th yeah yeah that's so there is this event uh December 4th it's a Meetup yeah     
1:21:49     
so that's and then it's a virtual event so it's easy to and then there's this     
1:21:55     
uh Community for the Thousand grain project so this is kind of the idea     
1:22:00     
behind the Thousand grain y so this is sort of the diagram     
1:22:07     
or the idea behind the Thousand greens um there's this object     
1:22:13     
model LM memory to learning module longterm memory sensor module motor     
1:22:19     
system to something called Monty which we'll talk about in a minute then you have a data loader the embodied     
1:22:25     
environment was for the Monty experiment so Monty is this implementation in     
1:22:31     
reference to Vernon Mount Castle who was a neuroscientist who proposed the column organization of the Mamon neocortex so     
1:22:39     
they work kind of built their platform on Mount Castle's work where he defined     
1:22:44     
sort of the layers of Cortex this colum their organization and then that's they     
1:22:49     
they you know kind of caught onto that and computational IED it it is he very famous in my hometown because he he went     
1:22:57     
to Runa College oh okay so I I'm I'm pretty sure that     
1:23:03     
um uh oh the the head of the brain Imaging     
1:23:09     
Center in Virginia Tech is the Vernon Mount Castle professor     
1:23:15     
of Neuroscience or something like that wow yeah so that's and then uh in the     
1:23:24     
future there be other implementations as part of the project so they're starting with like the sensory motor applications     
1:23:32     
and kind of building out from uh the ultimate aim is to enable developers to build AI applications that are more     
1:23:39     
intelligent more flexible more capable than those built using traditional deep learning methods Monty is are first step     
1:23:46     
towards this goal and represents an open source sensory motor learning framework so that's their and then they have their     
1:23:52     
Community their meetups discourse your documentation um this is the GitHub     
1:23:59     
repository of the Thousand brain project this is where we have the code available     
1:24:06     
so we have the Monty lab which is allows you to do these experiments the tbp     
1:24:12     
Monty which is the sensor mod learning framework uh and the CLA assistant which     
1:24:18     
is uh something that's kind of technical but basically the tbp Monty     
1:24:25     
is this here Monty repository um and you find the full documentation     
1:24:34     
here um so I guess you can do these kind of you basically have a set of sensory     
1:24:42     
motor tasks summarized in The Benchmark experiments and then you can build applications and Benchmark them against     
1:24:49     
those anytime a functional changes made to the code these experiments are rerun results are updated so you know it's     
1:24:57     
always benchmarking things there um yeah that's good um yeah so I don't know like     
1:25:07     
um I've not used it I don't know what the you know     
1:25:13     
it's I'm I'm curious you know so again like     
1:25:18     
newa had an open source project a long time ago     
1:25:26     
yeah and it was     
1:25:34     
um it was you know     
1:25:39     
a non-e learning neural network package right you know it was like a neuro     
1:25:48     
neural network package so I I'm I'm curious you know I     
1:25:57     
I posted in I don't if it was Frontier M     
1:26:04     
or or um Dev nuro but     
1:26:10     
um you know fitting I mean there's there are people who fit cognitive models to     
1:26:19     
data and then there are people who fit     
1:26:25     
Nur physiological models and and you know     
1:26:30     
you might think oh well doesn't don't don't lots of people do data analysis of     
1:26:35     
Neuroscience data yes but like like models that incorporate I I don't I     
1:26:43     
don't know what the best term is for models that incorporate a computational neuroscience     
1:26:48     
model internally right so again and the     
1:26:56     
SPM package in Neuro Imaging implements this Dynamic causal model     
1:27:02     
and what makes it special is um is     
1:27:08     
really that it's a it like Numa it's an     
1:27:16     
implementation of um a data analysis that includes an explicit cortical     
1:27:22     
column model um in this case yeah so all I've seen is     
1:27:29     
this particular flowchart but in the Jamon RIT model you know it's it's it's     
1:27:35     
an actual comp neuro model of the paramal     
1:27:41     
cells and the two cell types that are connected to the paramal cells right so     
1:27:47     
this is like if you've got electrophysiological data then it's these are the the     
1:27:55     
um suspected sources of those data you don't you don't listen to the brain you     
1:28:01     
listen to the paramal cells of the cortical Columns of the brain     
1:28:06     
right and and we can make inferences about the like interneurons and other     
1:28:13     
stellate I think cells that that are connected to the paramal     
1:28:19     
cells um be because they're they're     
1:28:25     
um yeah one one synapse away um uh     
1:28:32     
uh so I don't I don't know if it'll be that kind of model     
1:28:41     
um yeah so it's interesting but I I this is this is cool to see I mean it's it's     
1:28:46     
cool that they're doing a this is be a good a good chance to kind of refresh my     
1:28:54     
or update my my knowledge of what what they've been doing yeah you know they     
1:28:59     
they used to do they used to not only host U I can't remember the guy's name now who was their Community manager but     
1:29:07     
um uh but not only that but they used to live stream their their actual lab     
1:29:15     
meetings right yeah I remember that yeah you know and um and I'm trying to     
1:29:21     
remember um it's a South Asian guy who's the um like Chief scientist there okay I     
1:29:31     
I'm anyway I'll I'll I'll check but um yeah I wonder I wonder you like like     
1:29:39     
they were always doing very you know very like Mount Castle very single     
1:29:48     
subjects like cell you know cell modeling and and data     
1:29:53     
analys or you know like I don't even know how much data analysis they actually did it was he seemed to have a     
1:30:00     
lot of like postto level people working     
1:30:05     
as simulation modeling people yeah     
1:30:11     
yeah and um and again they it was never quite clear if they had a you know they     
1:30:18     
had a company or if it was just a kind of um     
1:30:27     
yeah yeah remember yeah remember the live streams they had like Jeff Hawkins     
1:30:33     
and some people it was very much like an academic lab meeting very right I mean     
1:30:39     
and and certainly for the posts it was you know or you know again like the     
1:30:44     
people who seemed like postto level people yeah they were they were like I'm     
1:30:49     
just you know this is the work I was doing it's you know NYU lab blah blah blah yeah like it was     
1:30:57     
it was straight up academic work yeah and I like it because they would go through like papers and they     
1:31:03     
would like kind of like ask a lot of questions so you wouldn't go through yeah the paper as like uh I'm gonna read     
1:31:10     
through it and you know it's kind of like let's work out some problems yeah yeah yeah yeah yeah yeah so we'll see     
1:31:18     
what the Yeah so December 4th n     
1:31:24     
uh there's like a whole bunch of things all happening that same time like What's     
1:31:31     
um there's something El coming up December well it's the foresight Vision weekend Oh okay that's one thing     
1:31:44     
um I think think got a Wednesday December 4th um     
1:31:54     
I see what that is I mean I okay oh no okay okay yeah that's six     
1:32:01     
in the E okay yeah yeah oh and they've got a second one in     
1:32:09     
San Juan Puerto Rico 21st to the     
1:32:16     
23rd that's that sounds much     
1:32:21     
nicer why would I     
1:32:26     
why would I go to that uh that awful City I read about of the     
1:32:32     
news San     
1:32:38     
Francisco there's something else though coming up like there's something else     
1:32:45     
that anyway I I'll I'll check all right you were talking about that P so what     
1:32:51     
channel was That in the thing you were talking about it was in     
1:32:56     
Dev uh um just um check Frontier map     
1:33:03     
project okay uh scroll up no     
1:33:09     
sorry um Let me let me sorry I'll pull my slack up just one second maybe it was     
1:33:15     
Dev AI it was the the paper that was focused on like     
1:33:20     
um there was an archive paper recently focused on     
1:33:26     
like fitting sore and actar models oh that might be in um in     
1:33:35     
brenberg vehicles may maybe definitely there was definitely     
1:33:42     
some cool um so this this week um we     
1:33:47     
actually had a meeting on bra brenberg Vehicles oh really yeah so the cognitive     
1:33:55     
science reading group or I forget what they're what do they um they build     
1:34:03     
themselves as anyway it was really nice um     
1:34:08     
we we had a seminar basically on on brenberg     
1:34:14     
vehicles and um you know that's a that's a really     
1:34:21     
nice um it's nice to read it again and just just     
1:34:28     
remember you know what um yeah San franisco cognitive science reading group     
1:34:33     
oh okay and speaking of cognitive science that was also why I was I was     
1:34:39     
laughing when I saw like that they added cognitive science     
1:34:45     
um the um yeah just what a great     
1:34:53     
thought experiment or you know certainly like like it's such a perfect it's such a     
1:35:01     
perfect um demonstration of something that you     
1:35:10     
can easily you know you can easily imagine you don't have to build this and     
1:35:16     
certainly by you know kind of like the middle of the the you know by like     
1:35:26     
five vehicle five or six you know like like it's the the loop that you've now     
1:35:34     
imagined is such that like you can't imagine the complex you like like the     
1:35:40     
complexity is such that you're don't you're not going to build any of these yeah yeah I know it's yeah it's like the     
1:35:48     
threshold for complexity you can understand or yeah yeah I mean certainly once the ads Evol U it's just like okay     
1:35:56     
you know like and now now imagine a billion years pass     
1:36:01     
yeah and you're you're replicating this and and I thought it was really you     
1:36:07     
know again I I thought that it was nice to reread and and just think about you     
1:36:14     
know some of the kind of machine learning work of Jeff cloons you know that like in terms     
1:36:23     
of you know bringing in evolutionary like     
1:36:28     
Robert I mean Richard Watson and and Jeff Clint in terms of like Evolution     
1:36:35     
and and machine learning or evolvability of neural networks and things like     
1:36:43     
modularity you know like which which he brings in in vehicle six you know with     
1:36:49     
the evolution um I thought was you know really key in terms of how you know you     
1:36:56     
you could upgrade a sensor from from taking from another animal another     
1:37:03     
vehicle and anyway but um it was nice     
1:37:08     
the sorry I was looking [Music] for um     
1:37:24     
was it braen bird um I I just I dropped some more     
1:37:31     
like World model papers in what channel in bra bird I     
1:37:38     
mean it wasn't it wasn't the ones I'm looking for this is Versa oh you know what it was cognition Futures sorry oh     
1:37:45     
okay let's go there yeah fit fitting evaluating and comparing cognitive architecture models ah here it is yeah     
1:37:52     
this one en actor yeah yeah and then the Conor Hines yeah oh     
1:37:58     
yeah IAM Iam's been on a a just a tear     
1:38:04     
these past couple weeks like like it's it's you know week after week it's all     
1:38:12     
mathematics of intelligence wow but but     
1:38:17     
um um some of them I might have put into bioevolution because they doing kind of     
1:38:24     
like collective intelligence of um now I'm not saying I say that then I     
1:38:32     
don't see any um anyway Conor Hines there you know     
1:38:40     
just speaking speaking about um applied active inference um you know Symposium     
1:38:47     
kind of kind related material but like if if you go to the YouTube video and     
1:38:53     
then you go to the description and then down at the bottom they have a link to the to the actual ipam Workshop okay and     
1:39:03     
and the the you know and then like once     
1:39:08     
you're there check like you know previous workshops because it's like the     
1:39:15     
last three weeks they've done you know     
1:39:21     
um uh um it's all mathematics of intelligence but it's like like like a multiscale     
1:39:29     
workshop uh like collective intelligence like a whole bunch of you know um um     
1:39:36     
social Collective Dynamics um you know people you know all     
1:39:43     
all kinds of ethologists and things um people working on traffic patterns     
1:39:51     
people are you know like like all really good stuff all really good stuff um like     
1:39:58     
like sorry just yesterday yeah I was Joshua bste okay from from from Hopkins um you     
1:40:06     
know and and definitely Tenon bomb you know like like like you know there's     
1:40:13     
just you know together with the Duro AI you wouldn't get anything done just be watching lectures you know but but all     
1:40:21     
really good anyway the the the actor you know I I I like this paper um just     
1:40:31     
because they seem to be thinking about     
1:40:37     
um you know actually bringing it yeah like bringing it to     
1:40:47     
um you know a lot of actar papers are are like like playing on the edges of     
1:40:55     
actar as opposed to you know     
1:41:00     
let's let's um let's look at applying this to to     
1:41:06     
behavioral data yeah yeah like like like let's look at like actually fitting this     
1:41:11     
you know yeah you think that would have been something that have been done before but I guess not not not enough     
1:41:18     
and I I like the fact that one of these people is at Activision oh     
1:41:25     
yeah that's great you know I I I've always I mean I guess you know I've     
1:41:31     
heard some horror stories about software engineering at at game companies yeah in terms of just you know like the worst     
1:41:37     
working conditions and things um but but I I've always wondered because it's just     
1:41:42     
like like why don't we see more research papers from like blizzard or Activision     
1:41:50     
yeah like like like they have the the best behavioral data on the     
1:41:57     
planet you know uh yeah yeah I I I I I mean I guess part     
1:42:06     
of it is that you know um as someone who     
1:42:12     
plays video games myself and and with my kids like U I I I think I know I think     
1:42:21     
they might know their customers and their customers don't care but but it's um anyway I just you     
1:42:31     
know it would seem like you know speaking of cognitive science like these     
1:42:36     
are data these are massive data sets that are relevant for cognitive     
1:42:42     
science you know I I I've I've always wanted to um have a you know take like     
1:42:50     
an open- Source game project and and run the server in some sort sort of project     
1:42:58     
where you know everybody who plays it gets access to you know the the logs of     
1:43:05     
the game data because like because this is the best behavioral     
1:43:12     
data but yeah I assume that Microsoft and Sony     
1:43:20     
are just sitting on this is big you know big data sets that they can U use for     
1:43:27     
for forther products right yeah learn from or you know have their AI     
1:43:33     
eventually digest or something like that yeah you know there's a lot of     
1:43:38     
interesting stuff in cognition feutures in brenberg vehicles in bioevolution I mean you know     
1:43:46     
there's just a lot of stuff yeah uh if I go back to cognition Futures you know uh     
1:43:54     
posted this thing here uh from the complex world the second world system     
1:44:00     
over the last century countless researchers have sought to capture the essence of complexity and ideas as wide     
1:44:06     
ranging as self-organizing systems voluntary activity cybernetic control     
1:44:13     
goal seeking self- reproducing representational schematic autopoetic     
1:44:19     
cognitive and information gathering and utilizing system so this is like kind of interesting that     
1:44:26     
this is these are like kind of vessels for complexity or constructs for complexity but then you know you see     
1:44:32     
that some of these intersect with some of the neuro AI stuff we've been talking about so like     
1:44:37     
representational cybernetic control goal seeking those are all kind of like descriptions of these kind of systems     
1:44:45     
and like it's interesting I think it's is interesting that we have these     
1:44:51     
constructs and just kind of interesting how you know we kind of first of all how     
1:44:57     
we kind of reinvent the wheel on things but secondly how those things intersect from complexity Theory into some of the     
1:45:04     
narrow AI stuff and some of the other types of things we're doing in cognitive science and Neuroscience and so     
1:45:13     
forth can I be selfish for a minute I had to step away for a little bit and we weren't I saw the screenshot and I don't     
1:45:19     
know what other discussion happened before that I was obviously curious about how we got to that just going to     
1:45:24     
the the slide oh I just saw it there and I thought it was interesting tie things together so I I I feel to be to be     
1:45:32     
totally Pat myself on the back I feel so Vindicated in a very specific way which     
1:45:38     
I may elaborate on another time I feel so Vindicated by like I I don't have the     
1:45:44     
book actually I do but his uh crack hours um it just     
1:45:51     
just because it it to me it's it it feels like what I said but he uses like     
1:45:58     
a different scale and in one of my writings the W is about Vantage points i' I've been using this long well     
1:46:05     
actually much longer than that I've been using this sort like cell phone an knowledge like why is it so much harder why do we have a cell phone you know     
1:46:12     
like like compared to I would say much more literacy     
1:46:18     
about internal you know em internal State     
1:46:23     
subjectivity and I in in the in that's that's something doing for a long time I never really formalized I suppose in the     
1:46:30     
Vantage points paper though I say like yeah there's a reason why it's easier for us to go build a spaceship and go to     
1:46:36     
the moon and do other things and so I'm I'm kind of coming at it from the almost a bigger scale but in the opening of the     
1:46:45     
book um which page is it on in in the first few pages in     
1:46:52     
introduction stuff within the first like 20 pages of the book     
1:46:57     
um he basically uses the scale analogy out another way he's like well we can     
1:47:02     
totally build stuff smaller than uh you know a covid-19 virus we can do stuff in     
1:47:07     
I don't know 20 30 whatever anomo range and he basically going the other direction saying well why is that why     
1:47:14     
it's not it's not not because we can't engineer something so small uh it's the co the co virus and other viruses is     
1:47:20     
operating in a different way much more complex so he kind of goes from this other angle of saying     
1:47:26     
well you know it's not just it's not just this or that but the     
1:47:31     
way the way he talks about it was quite interesting to me and it felt like     
1:47:37     
uh an a congruent argument with what I made in some of the Vantage points um     
1:47:43     
paper which which you know more about that later on     
1:47:49     
um but yeah I'm I I haven't I haven't had nearly as much time especially this week to go through the book but it is     
1:47:56     
interesting and I do think that's like I think there's something that I want to do regarding probably Levan because Levan's     
1:48:03     
sort of this a good foil but also of a similar     
1:48:09     
nature I don't know I don't remember if we talked earlier in this meeting about what we the paper Lev's memory paper     
1:48:14     
that we discussed Thursday night um or we're doing I I don't want to repeat     
1:48:20     
that we can summarized it yeah     
1:48:25     
okay um but Levan there's something I need to     
1:48:30     
do with Levan and and David cra's stuff and I think I think that's     
1:48:36     
gonna I I've been trying to actually formalize like a project description about what it is and and and that I want     
1:48:44     
to do there but yeah suffice to say there's something there and     
1:48:50     
um I don't know I I came in and you were talking about that specific part of the     
1:48:56     
book and you were I kind of got what you were saying but not really I'm sorry to make your retrace your steps here you're     
1:49:03     
talking about the quote or something oh yeah just that quote I was talking about how this is like you know we have these     
1:49:10     
uh constructs for complexity and how it intersects with some of the stuff we're doing in other     
1:49:15     
fields like n Ai and that sort of thing so you know you could have like you know     
1:49:21     
complexity theor is famous for having kind of new wine and old bottles like     
1:49:27     
you get like these different Frameworks that people kind of home brew and they kind of overlap with other like you know     
1:49:34     
you might have like synergetics which overlaps with you know different types     
1:49:40     
of dynamical systems which overlaps with Chaos Theory overlaps with catastrophism     
1:49:47     
which overlaps with other things just you could build like a map of that if you wanted to     
1:49:53     
where you just look at how these Concepts kind of intersect and like you know there are like insights in each     
1:50:00     
Viewpoint you know but they're all kind of constructs of the same types of things and so you know having that kind     
1:50:08     
of diversity is nice but it's also kind of hard to synthesize the field um     
1:50:15     
because you have these different things going on um and these different themes it's hard to really kind of then apply     
1:50:21     
it to anything where do you want to actually demonstrate the principles and I feel both     
1:50:30     
like in in a way of complete uh difference to both of you two like I     
1:50:36     
don't I really I'm far too naive to really understand     
1:50:42     
if what David KRA is saying in terms of his whole take ofon matter and his take on complexity     
1:50:49     
science is really like is     
1:50:57     
it a new take on it or is it just like a version of what Bradley just said so far     
1:51:04     
or we don't really know like I don't know like I think Bradley but I don't know I don't really know what your opinion on what he's trying to do there     
1:51:11     
yet um is and you don't have to you don't have an opinion right now that's fine I'm     
1:51:16     
just I feel I feel very mixed about what I'm supposed to feel about it     
1:51:23     
and I I at the same time like I I hope that's a separate question     
1:51:33     
from uh trying to say here well I don't know I guess maybe is     
1:51:41     
a similar question but but sort of like yes it's very weird because I think some     
1:51:47     
of the better parts of what I'm interpreting as modern or contemporary     
1:51:52     
for a version of complexity science is inherently going to be you know it's     
1:51:58     
this sort of age-old question of like what [Music] level are you working     
1:52:06     
at because certain like there's reasons why it's much like the more concrete you     
1:52:12     
are the more you can the more close you can connect the ODS between what it is you're you know supposing and and so on     
1:52:20     
um so I don't know like I don't I don't     
1:52:26     
have I'm not I'm not uh all in on David kow's stuff yet yeah or his like is I     
1:52:35     
don't even know if it's fair to call it his take or like his attempt to synthesize complexity science in a     
1:52:42     
certain way and say this actually I think one of the one of the key debates as far as like can understand so far is     
1:52:48     
actually no he's he doesn't want to call things that aren't basically I     
1:52:54     
don't know what to say decision Mak information process whatever things that aren't chomic in their     
1:53:03     
functioning out like he wants to separate that and I don't know what to make of that yet but I don't like gu     
1:53:10     
that seem like oh another just another remix or that seem particularly radical or that just like who knows     
1:53:17     
right yeah I think uh croca yeah he's trying to make a synthesis of some of     
1:53:24     
these ideas because again they're all over the place but they're very similar and then considering the sort of     
1:53:30     
the philosophical and historical aspects of that and you know it's just kind of like     
1:53:36     
that's not something that exists too much I that's why Santa Fe kind of exists in a way because facilitating a     
1:53:43     
lot of complexity Theory research but they're also kind of trying to figure out how     
1:53:48     
to synthesize it how you know what what is it about complexity Theory that's special or that     
1:53:55     
brings like we talked about last week where um you know there's this sort     
1:54:01     
of uh where it's kind of complexity theory is kind of useless it was the     
1:54:06     
petol blog post where complexity theory is kind of absorbed into other fields     
1:54:12     
and it's like what is it bringing to the table is it bringing any value so this     
1:54:17     
is bringing value to the table essentially we're reconsidering what we've learned     
1:54:23     
and say this is the value of complexity science at least as far as I can tell     
1:54:28     
because I think that in that small book you've got a lot of really cool kind of Reflections on history of complexity     
1:54:36     
Science History of cybernetics kind of bringing it all together bring that forward and you know there's others like     
1:54:42     
there's the T anomic discussion too which I'm not as IND as you are so I mean you're kind of the expert here on     
1:54:49     
this but um yeah I mean I think there that's what he's trying to do is really trying to add some Val like     
1:54:58     
say that there yeah there's complexity Theory it's the relevant you know the people adapted for their own Fields but     
1:55:04     
we have these other core questions and we need to advance well and and     
1:55:12     
like there's from my current Vantage Point hold onot of seconds it's going     
1:55:19     
to a buzzer is going to go give me like 10 seconds     
1:55:27     
all right hopefully     
1:55:33     
um from my from what I can currently I don't know sort out there's well not     
1:55:40     
sort out the I'll use the word Vantage Point very attentionally even though I say that all the time     
1:55:49     
um I I could see things going in a few different directions and I'm I'm curious     
1:55:58     
because part of me is you I think we can tell like I'm very hopeful about craar Vision in one sense and I'm skeptical on     
1:56:07     
others like I'm hopeful because I think there is     
1:56:14     
a I don't know almost almost in the same vein of what's what's what's what's next in     
1:56:20     
cognitive science or what's beyond 4 e or what's the next version of that     
1:56:26     
um I don't I don't feel like oh well David K's vision for for complexity     
1:56:31     
science he going to revolutionize everything and give us a clear path to go I I don't quite feel that but it's     
1:56:37     
more I think I think there may be something interesting in the way he's trying to     
1:56:42     
divide some of the lines of what is toomic or not but also     
1:56:48     
like I mean is it basically just saying is it trying to splice things in a     
1:56:54     
different way that's like basically like social science related stuff plus you know aspects of information     
1:57:01     
processing and like biological is too like like like there are ways you     
1:57:07     
could sort of minimize the novelty of what's going on     
1:57:12     
but um I I think I think there's some     
1:57:24     
there's a way that that that both in essentially in terms of     
1:57:30     
like straight philosophy and maybe like I guess I guess I call like the French you know critical crew of of I     
1:57:38     
mean you can I was actually as as a slight tangent I was looking at um P     
1:57:44     
wrote book on structuralism and then there's the post structuralists who kind of go into uh     
1:57:52     
like buo and I think like Dara and all all the L and all those people that have     
1:57:59     
different takes on like philosophy and History of Science and so on and there's something there but but but sort of     
1:58:07     
like I'm very sympathetic to what we saw in slides earlier about     
1:58:13     
you know we want you know we're gonna I don't know if this was intentional we're we're going to slice off half of the     
1:58:19     
hexagonal Cog sign and just do the the stuff that gets stuff done and and that that take too so it's sort of like I     
1:58:26     
don't know I'm not being the most coherent here ever     
1:58:31     
but um I I wonder I I guess my I guess I'll put it as a question I really     
1:58:38     
wonder what the lens that crover is doing can yield and and I think I think     
1:58:46     
I think it has a very high ceiling and and and a very low floor     
1:58:52     
um and I don't I feel I would in the next several months     
1:58:58     
I'd like to know more about that and report on that in it's kind of a project basically and I don't know what that     
1:59:04     
looks like and I don't know I'm not comfortable with a full proposal of it yet because it's     
1:59:11     
something to investigate but at the same time it could be as big as okay this is sort of a missing piece to a lot of     
1:59:17     
cognition fatures type work and the philosophy work around it or it could be well it's another Rican science that I     
1:59:23     
don't know yet so that's my longwinded way of saying I don't really know yet so     
1:59:29     
yeah well yeah you're always welcome to use this meeting as a sounding board if you want to present something on it more     
1:59:36     
formal I mean I think it would help clarify a lot of that um speaking of     
1:59:42     
structuralism I'm glad that you brought that up because I attended a network science seminar on Wednesday it was pet     
1:59:49     
Holm actually who was presenting and he presented sented on network so he's this is like Network science it's a special     
1:59:57     
interest group and he was talking about networks and how that's his area of research main     
2:00:04     
area of research and so how networks are have kind of taken two paths you know     
2:00:09     
we've had sort of this so Network science has been around for decades and     
2:00:15     
it really kind of got kicked into high gear around the year 2000 where there     
2:00:20     
were a number of papers released where people talked about the fundamental laws of networks like you know we talked     
2:00:27     
about small world networks we talked about uh different types modes of connectivity so there were these sort of     
2:00:35     
it was originally in physics where people talked about universal laws of networks so you could take like a social     
2:00:41     
network and a technical Network and other types of like biological networks     
2:00:47     
and they would all have these converge upon these laws of operation so small     
2:00:52     
world inness scale freeness um you know uh certain path length they're all sort of preferential     
2:01:00     
attachment there all these rules that you can find power laws in networks that describe you know     
2:01:07     
it could be a social network could be a biological Network any kind so that's like one type of approach to network     
2:01:13     
science then he talked about how structuralism is actually another way you can look at networks so you know     
2:01:20     
social networks you can actually measure structuralism the structuralism of some     
2:01:26     
of your Social scientists like Levy Strauss and some other people who you     
2:01:32     
know uh kind of advanced this idea of structuralism in in societies and culture and then you know they they     
2:01:39     
describe these structures you can describe them in social networks or you can describe them in other types of     
2:01:45     
networks as well so you can look at things like leaks and modules and other things and get a sense of you know the     
2:01:51     
structure and I I was thinking when I I heard this kind of he was talking about this     
2:01:56     
dichotomy between universal laws and structuralism I was thinking where does I wonder like things like post     
2:02:02     
structuralism where do they fit into this or other types of approaches to network Theory like you know we're     
2:02:08     
talking about chaos where does that fit into so I was just you know it this     
2:02:13     
really kind of food for thought it was a great talk but um yeah I might I might do present on that in in coming weeks     
2:02:21     
because I think important for some of this complexity debate and especially some of the things that we talk about     
2:02:27     
what you know what the frontiers of complexity Theory now that people have adopted a lot of these ideas into their     
2:02:33     
own fields and that sort of thing yeah um and     
2:02:41     
it's I look forward to that it's     
2:02:46     
it's I would like to get I would like a goal for myself is I'd like to get to a place where I have a a better sense of     
2:02:52     
how to how I want to align myself with basically like am I a complexity     
2:02:59     
scientist am I trying to push complexity science in a particular direction or is it sort of like saying well I'm I'm a     
2:03:06     
you know generic term well whether or not it broadly has     
2:03:13     
value is can I get to a place where I have a particular take or agenda I want to push in that space or not and I I to     
2:03:21     
be determined and U hopefully we can talk a about that more ahead so I'm sure you have uh oh     
2:03:27     
actually I don't realize what time it was we much further along um there anything else you wanted to say I I I     
2:03:33     
could ramp on about that for a long time so yeah I'm gonna get to this article yeah let's do that thank no     
2:03:42     
problem all right so this is an article that uh Morgan shared in I don't know     
2:03:48     
remember which channel in the slack it could have been data science um maybe bio Evolution bio Evolution     
2:03:55     
yeah it's it's relevant there too this is the Gonzo ml substack I guess uh and     
2:04:01     
this is Gregor sapunov who's I guess uh co-founder in CTO intento Google     
2:04:08     
developer expert in machine learning uh and so he's considering diffusion models which are a modern sort of machine     
2:04:16     
learning approach uh in the ever good regulator theorem paper that we just put out or is     
2:04:25     
you know we're kind of working on still uh we talk about defusion models extensively with respect to the ever     
2:04:32     
good regulator theorem and so this is you know diffusion models are where you     
2:04:38     
train a model on sort of like some diffusion process maybe noise uniform     
2:04:46     
noise and what you'll do is you know like what we'll take an example of image processing you have a bunch of images     
2:04:52     
that you train the model on but you don't train the model just on the images you train it on images that are     
2:04:59     
progressively masked by noise and then the idea is that this noise diffuses across the image and then you know you     
2:05:07     
have this ability for the system to recover different types so it basically     
2:05:15     
improves generalizability of the model by training it on Noise by masking the     
2:05:20     
image it learns sort of the feature you know variations and the features that     
2:05:26     
come with increasingly uh increasing amounts of noise being Ma you know     
2:05:32     
things being masked so it's an interesting way to approach generalizability and training of models     
2:05:39     
so this is um a this is titled diffusion models or evolutionary algorithms so     
2:05:45     
this means that diffusion models and there are a lot of interesting physical properties of diffusion models of course     
2:05:51     
we have diffusion models in physics we have like their you know stochastic models the you know we use diffusion     
2:05:58     
models for things like morphogenesis we use the fusion models for things like looking at Evolution because you have     
2:06:04     
like mutational processes that are more you know very similar to diffusion models so it's it's interesting making     
2:06:12     
that connection and I agree with this this is a very important connection so this is uh I guess this is     
2:06:20     
a paper by Micha 11even on it of course and it's actually the paper diffusion     
2:06:25     
models or evolutionary algorithms so this is the archive paper they're using     
2:06:31     
this diffusion Evolution method an evolutionary algorithm utilizing iterative Den noising as originally     
2:06:38     
introduced the context of diffusion models to heris refine solution and parameter spaces so they're using this     
2:06:45     
uh you know they're using this iterative noising and denoising of uh you know get     
2:06:51     
some data and they're using that to sort of corrupt the signal so that the the     
2:06:57     
system can learn about the signal in different ways you know in its corrupted form and then kind of better generalize     
2:07:05     
things so uh this in I'm going to read the top of the abstract in a convergence     
2:07:12     
of machine learning and biology feel that diffusion models are evolutionary algorithms by considering Evolution as a     
2:07:19     
denoising process and reverse Evolution as diffusion we mathematically demonstrate     
2:07:26     
that diffusion models inherently perform evolutionary algorithms naturally encompassing     
2:07:32     
selection mutation and reproductive isolation so these are the the kinds of     
2:07:37     
functions that you might have in an evolutionary algorithm you have a mutation operator that mutates the     
2:07:43     
signal so it's much like if you're introducing noise into the signal you're selecting for things so     
2:07:50     
you're selecting for features and you're you have populations     
2:07:55     
of programs that are mutated and if you isolate them you can     
2:08:00     
you know have this sort of genetic drift that allows you to find solutions that     
2:08:07     
maybe you you know you can select them sort of neutrally so diffusion does all     
2:08:13     
these things uh very similar models um and so diffusion Evolution efficiently     
2:08:20     
identifies multi Optimal Solutions and outperforms prominent mainstream evolutionary algorithms so this is     
2:08:26     
interesting that we can actually outperform evolutionary algorithms of diffusion furthermore leveraging     
2:08:32     
advanced concepts from diffusion models namely lat and space diffusion and accelerated sampling we introduce Laten     
2:08:40     
Spas diffusion Evolution which finds solutions for evolutionary tasks and high dimensional complex parameter space     
2:08:48     
while significantly reducing computational steps this parallel between diffusion and evolution not only     
2:08:54     
Bridges two different fields but also opens new avenues for Mutual enhancement raising questions about open-ended     
2:09:01     
Evolution potentially nonan or discrete diffusion models in the context of     
2:09:06     
diffusion Evolution so a lot of interesting stuff here uh there's also a GitHub repository     
2:09:14     
here which this is where they talk about this where they're kind of using noise     
2:09:20     
to enh these clusters you see that this noise is low     
2:09:26     
Fitness this these semi clusters and noise is low Fitness and you increase your     
2:09:31     
Fitness um yeah so they you can the code is here you can install it and run it um     
2:09:39     
yeah so that's uh the sort of the overview of the the sort of the paper     
2:09:46     
and the GitHub repository that they are talking about this post so this is uh     
2:09:53     
where kind of gives some more context an interesting paper from Michael Levan and Company this is the same Michael Lan who     
2:09:59     
has been working on bioelectricity artificial life and many other biology related topics he gave a fantastic talk     
2:10:06     
to what bodies think about bioelectric computation outside the nervous system at nurbs in 2018 this is the talk here     
2:10:15     
uh he also did an intriguing keynote robot cancer with the bioelectrics of embryogenesis and regener generation and     
2:10:22     
teach us about unconventional Computing cognition and the software of Life at aif 2020 I think we attended a life 2020     
2:10:30     
as a lab and I think I saw this talk there uh we he co-authored an excellent     
2:10:36     
work on cellular automa and differential morph Genesis this is this distill Pub the growing cellular autom this is we     
2:10:44     
talked about this paper before uh this paper claims that diffusion models are the paper that we     
2:10:50     
just saw the archive paper claims that diffusion models are evolutionary algorithms how so let's break it     
2:10:57     
down so he talks about in the biosphere at least two processes capable of     
2:11:02     
generalization and creating novelty Evolution a slow process of adaptation     
2:11:07     
to the environment across Generations through natural selection and learning a     
2:11:13     
fast process allowing individuals to acquire knowledge and generalize subjective experience during their     
2:11:19     
lifetime so there have been number of papers on the connection between evolution and learning from hinton's     
2:11:25     
classic how learning can guide Evolution to Van shuran wolf uh cats     
2:11:32     
Kats nilon and kunin towards the theory of evolution as multile learning and     
2:11:38     
then Watson and Leven we talked about Watson before and then Leven the collective intelligence of evolutionary     
2:11:44     
development 20123 the current work argues that is specific class of diffusion models or generative model     
2:11:50     
performance sequential stochastic de noising can be understood through an evolutionary process that performs     
2:11:56     
natural selection mutations and reproductive isolation and so this talks about     
2:12:03     
diffusion models here where they're doing the denoising the recovering an image from noise and there the image is     
2:12:10     
becoming increasingly harder Fitness um this is this is you know this     
2:12:16     
this process has been worked out um quite well and then we talk about     
2:12:22     
algorithms um as you can see both approaches involve iterative data updates and sampling new objects from     
2:12:29     
complex distributions both have a combination of directed updates and random curations     
2:12:35     
there are selected selection plus mutation or selection mutation models in Evolutions case random noise learn     
2:12:43     
noising and diffusions case so it's making the connection between selection mutation and evolution and random noise     
2:12:51     
learn noising diffusion that's interesting you know in the uh ever good regulator theorem paper     
2:13:00     
we actually have two examples one example of the sort of diffusion model and then the example of the learning     
2:13:06     
unlearning and relearning uh experimental Paradigm in     
2:13:12     
sensory motor neuros servs and I'm wondering you know and there's some connections made there I'm wondering if     
2:13:18     
this is a very similar thing they're hit we're hitting on the same thing this raises the question is the     
2:13:24     
mechanics of the two processes fundamentally connected and is there a deep mathematical Duality between     
2:13:30     
biological evolution and generative model or is it all just analogy and vanity of     
2:13:36     
vanities I think there is a deeper thing from my     
2:13:41     
perspective uh yeah so looking at species populations in the biosphere The     
2:13:48     
variational evolutionary process can be understood as a transformation of distributions will it be disc to disc     
2:13:54     
analogous to seek to seek distribution of genotypes and phenotypes mutation and     
2:14:00     
selection jointly change the shapes of these distributions many biologically inspired evolutionary algorithms can be     
2:14:06     
understood similarly they optimize an objective function by maintaining and iteratively changing the distribution of     
2:14:12     
a large population and the same concept transformation of distributions is     
2:14:18     
Central to many generative models vae Y and diffusion models learn to     
2:14:23     
transform simple distributions often standard Gans into more complex ones     
2:14:28     
where samples represent meaningful images sounds and texts so you can also view diffusion from an evolutionary     
2:14:35     
perspective during training data points are noised and the model wants to predict this added noise to reverse the     
2:14:42     
process uh in the sampling phase the model starts with points from a gy and distribution and incrementally updates     
2:14:48     
them through Den noising or noise-free samples the ideal so it takes the noise and it removes it through selection and     
2:14:56     
mutation and then you get this uh sort of evolutionary     
2:15:01     
process uh that aligns with interpreting The genome as a weight and space parameterization of a multikill gener     
2:15:08     
morphogenetic process rather than just a blueprint of an     
2:15:13     
organism and then there's this analogy to to statistical physics and energies     
2:15:19     
and probabilities so like we talked about statistical physics where you have the energy landscape and you're trying     
2:15:25     
to minimize the energy landscape and this is very similar to The evolutionary uh Fitness landscape so you have these     
2:15:33     
this sort of analogy between uh statistical physics and evolution you     
2:15:38     
have this analogy between diffusion models and evolution and so it goes through this math and some of the the     
2:15:46     
technical details and finally you know kind of getting to the end     
2:15:52     
where you know they consider how diffusion models work and how Evolution     
2:15:58     
might improve that and how this whole process is open-ended so that's great uh great     
2:16:06     
stuff uh any questions on that before we go no it's it's it's really interesting     
2:16:15     
um it's an interesting update for a bunch of ideas that again like I I kind     
2:16:22     
of caught quite curiously through my wife and um her work with Watson for you     
2:16:29     
know doing doing that kind of um that kind of program um it reminds me a lot I     
2:16:38     
mean you know looking at the paper um it reminds me a lot of gecko like     
2:16:46     
papers right I mean you know certainly in the in the the substack when mentioned CNA yes you know that's those     
2:16:54     
are the kinds of papers that I'm thinking about from like 10 years ago where like it's it's a lot of like     
2:17:02     
yeah optimiz functions optimization like if you go into the     
2:17:07     
details of the paper you know it's it's it's a yeah I I was really interested to     
2:17:14     
see like how did they bring in things like mutation into you know like like     
2:17:19     
you know and and I I think yeah I think it's it's it's     
2:17:27     
they're kind of they're kind of suggesting that it's there because     
2:17:32     
because these explicit kind of evolutionary algorithms behave the     
2:17:39     
same way yeah uh um on on these particular kinds of benchmarks that     
2:17:45     
again are like super common in in you know the um the top papers of gecko yeah     
2:17:54     
or maybe you know top papers of gecko like a couple years ago but but but     
2:17:59     
again like the connection there I mean I I really like the disc to disc because     
2:18:05     
you know I mean that's that's um yeah I     
2:18:11     
mean it's it's it's very easy to think about a lot of machine learning     
2:18:16     
categorization with with that kind of that kind of approach and um and it's     
2:18:23     
easy to you know energy like the connection statistical physics is just     
2:18:29     
where you know your your ex is just reflects energy but like if you think     
2:18:36     
about that very broadly like in in data terms you know it's     
2:18:44     
a you you get that kind of just straight probabilistic     
2:18:49     
approach or straight probabilistic interpretation and yeah like     
2:18:56     
um so it's um yeah the code is there to play with yeah yeah and and I'm     
2:19:06     
I'm yeah it was it was interesting I again     
2:19:11     
like I I would really you know I would just guess that gecko is     
2:19:19     
totally enamored with diffusion models you know     
2:19:24     
regardless of this paper like like like like the only thing I didn't check was     
2:19:29     
like how how new is this in sense of you     
2:19:34     
know is is kind of Levan team just riding on you know a bigger surge yeah     
2:19:42     
where you know again like we all saw this coming 10 years ago in the sense that like like these deep learning     
2:19:49     
approaches are are very general and you know and     
2:19:55     
obviously have this just massive smart minds and resources behind them um     
2:20:02     
they're going to swamp everything right it's and     
2:20:07     
um so but I like yeah just connecting you know I mean I think     
2:20:15     
I kind of extra you know shout out to Watson in the sense of like uh you know     
2:20:22     
I think he was definitely one of those people who was early on saying that like Evolution can be seen you know evolution     
2:20:30     
is a really um nice way to kind of Flip Flip machine     
2:20:37     
learning around yeah and and to to to learn from you know yeah like like     
2:20:46     
each side of that coin has something to offer and again like you know the really interesting thing about about diving     
2:20:54     
into kind of Watson machine learning is that there are all these kind of old     
2:21:00     
problems in population genetics yeah and evolution that yeah that like suddenly     
2:21:07     
suddenly have a a not like a new lease on life but you     
2:21:15     
know well you can reinterpret the models as you can reinterpret them and and it     
2:21:21     
it potentially you know suggest does it suggest new approaches you know could we     
2:21:27     
make some yeah some and and and again like as well as you know potentially     
2:21:35     
some of the issues through why you know again like machine learning     
2:21:42     
deep learning is not a it's not a magic wand but like like suggesting like why     
2:21:48     
there will always be difficulties with certain things because like again population geneticists have shown like     
2:21:55     
there are these issues in evolutionary you know yeah shifts and and things like     
2:22:03     
that or yeah yeah anyway okay all right cool all right let's wrap it up for     
2:22:09     
today I think there's a great T great set of topics that we talked about and I'll try to get the you know open up     
2:22:16     
these screenshots for Nur AI so you can look them over so so all right have a     
2:22:22     
good uh week thank you take care everyone thank you yeah take care oh yeah um nurs um has a neuro AI Workshop     
2:22:31     
okay wow right think think about yeah yeah yeah so like that's that's what we     
2:22:36     
should be covering in two weeks or something like that oh yeah yeah we should all     
2:22:42     
right bye
