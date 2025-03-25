## Meeting Recording

[YouTube link](https://youtu.be/D_kdcz9d95Q)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113138347721391311)

## NOTES:
Morgan: tools (NeuroFedora).

* docs focused on Computational Neuroscience. PyMDP, other tools.

* bring it up with Ankur. How is Active inference used?


ActInf, RL agent policy. Ryan Smith's step-by-step tutorial.

* not everything in the world is Bayes Optimal (in Bayes, one thing is most optimal). RL optimal training.

* ActInf overlap with world models. Infer.JL.


Computational Psychiatry, ActInf. CompuCell3D example with pattern formation.

* software tools and morphogenesis --> ActInf, Levin et.al.

* computational psychiatry --> applied RL work.


Queen's Square -- a bunch of great institutions.

* Chris Bishop --> foundational variational Bayes. Bandit models.


POMDPs + RL = Active Inference.

Read Montague -- Peter Dayan collaborations.

* Computational Psychiatry (Zurich).

* Mathematics of Intelligence tutorial (IPAM). Application of RL models to neuroimaging data.

* Modeling gambling, stock trading (Econ tasks).


Parameters demonstrate strategy, risk averseness.

* Ryan Smith -- Step-by-step tutorial --> ActInf + policy training strategy.

* RL -- Fristonian approach.


Ida M. --> history, architecture RL, early 20th century behaviorism.

* produced relevant software tools.

* greater context of ActInf. Neurobench --> animal models, RL models.


JESSE: Combined undergrad/Masters' program.

* collaboration with Valeria, led to Society, Ethics, Technology.

* additional meeting with UAlbany. Foresight Institute grant.


NP (Neurophenomenology) methods group. Has a page on JoPro.

* Mental Health working group --> regular meeting time.

* won't be a standing hour-long meeting.

* exploration/exploitation tradeoff (early ActInf). All about action. Generalize across animals.

* energetic limitation optimal tradeoff.

* Fristonisms: "reduction of surprisal", "Contradictionism" (in opposition to?).

* Friston struggled with ambiguity, reason for exploring variational Bayes.


TREVOR: review commons (no experimental context).

* "Towards a NeuroAI" -- Kording, Zador. Does Neuro have anything to contribute?

* if ANNs are bio-inspired (questionable), then how useful are they how useful are they for Neuro?

* Pfau -- Neuro trying to be AI-relevant.

* what is the "why" of NeuroAI --> Darwinian?


Target Learning vs. Backprop -- use two different models to explain data. Model comparison techniques.

* fitting the data --> single model will fit the data.

* Dynamic Causal Modeling -- compare spatiotemporal models.

* Neuromorphic computing. Efficiencies of neural-biological NNs.


Organoid Intelligence --> overestimate power efficiency (cannot pass inputs in).

* superhuman performance -- in this case, human augmentation.

* Neuromorphic Computing -- more efficient chip architectures --> spiking NNs, or adaptive control. 

* system with power efficiency, expansion.

* series of talks (YT) related to Levin (multiscale issues, biological learning, TAME).

* Ricard Sole -- spiking NNs as non-neuronal processes.


Math of SNNs is so abstracted from neurons, represent NeuroAI.

* can we predict what happens at the next time step?

* Neuron C++ level simulation. Stochasticity in the brain (heterogeneity?)

* is that NeuroAI? How much detail do we need?


Useful from a physics of life perspective? Complexity boundary, how do we achieve criticality, dynamics?

* Diverse Intelligences -- evolution as a learning processes.

* Neuro is an outcome of evolution (Kanwisher's why questions).

* problem-solving all the way down.


Why did this neural structure develop, evolve? 

Ricard Sole is a neural system a means to develop interneurons. Sensory is a single-cell thing.

* movement, Romain Brette --> Paper QA2 system --> "How to solve it" --> LLMs as scientific discovery.

Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://www.frontiersin.org/journals/computational-neuroscience/articles/10.3389/fncom.2022.988977/full
 
Morgan Hough (he/him) says:
https://www.translationalneuromodeling.org/cpcourse/
 
Morgan Hough (he/him) says:
https://pubmed.ncbi.nlm.nih.gov/35340847/
 
Morgan Hough (he/him) says:
https://www.ipam.ucla.edu/programs/workshops/mathematics-of-intelligences-tutorials/?tab=schedule
 
9:41

Jesse Parent
Jesse Parent says:
It's funny as it has some strong parallels to the use of "AI" in other industries or products; "because we can mix it in!" is a major driver 
Jesse Parent says:
👍 
10:28

Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://youtube.com/@uclalifesci?si=vh4UZ741SCxqUf-Q
 
Morgan Hough (he/him) says:
https://github.com/Future-House/paper-qa
 
10:39

Jesse Parent
Jesse Parent says:
ty for discsussion! I have to depart for now. Let's follow up on the projects / grants talks in slack

## TRANSCRIPT
     
Transcript     
0:09     
hello are you hell     
0:15     
Jesse morning morning all right uh when don't we get     
0:22     
started um The Welcome to the meeting um yeah this week we did not have deaw     
0:30     
meeting uh we did have our cognition Futures meeting and     
0:37     
our cybernetics meeting and we have those what we did was we went over our     
0:45     
paper on the ever regulator theorem and it's applications to machine     
0:51     
learning and uh so the we we kind of went through it word for word I know     
0:56     
Jesse spent time saying the words word for word just so we could review     
1:02     
each part so in cognition Futures we did the abstract and the     
1:08     
introduction and went through that and then in the cybernetics reading group we went through sections two through I     
1:15     
think four which was the discussion and we finished up so we did the and then     
1:21     
next week we're going to try to do references and then you know the     
1:27     
supplemental materials so these two things are on YouTube our YouTube channel um you know we've got you know     
1:34     
uh so I know Morgan couldn't make it so this is available for him to look at and     
1:40     
comment on and there's it's kind of an open comment session here where we can make     
1:46     
comments uh and so that's that's we've got that going and that's been submitted     
1:51     
to uh the interface Focus special issue um so I haven't heard back on that I     
1:57     
know they have a Target date of October 1st for some things so maybe we'll hear back     
2:03     
then we didn't have any meeting yesterday we had uh an administrative     
2:09     
meeting last week this week nothing I wasn't have been and so that's our those     
2:15     
are weekly meetings so let me share a couple other things with you um the     
2:21     
first thing is that um Jessie pushed this post that he did on Valaria shaki's     
2:29     
um uh thesis on artificial intelligence and liability to our lab mediums this is     
2:34     
announcing her uh dissertation or thesis um on this topic it was submitted     
2:42     
to uh the University of Chu and you know it was on artificial     
2:49     
intelligence and the U legal responsibilities and so this I think was     
2:55     
uh you know case study in ch so this is a graduations to     
3:02     
Valaria um and she yeah graduated from University of CH School of Law uh she's a founding meth meth member     
3:10     
of society ethics and technology and um she you know she's     
3:16     
collaborated on a number of things that talk ethics and bias and AI which was     
3:22     
presented at New York celebration wom Computing in 2019 and then she spoke on Law and AI     
3:28     
priv privacy rights is part of key Concepts and Tech careers and Tech ethics in at the 2023 uh New York     
3:36     
celebration women and Computing and now she's published her dissertation so this     
3:41     
is the abstract in Spanish here and then in English so you can read it for yourself visit our medium and do     
3:51     
that uh the second yeah we'll talk about that in a minute I guess the second     
3:56     
announcement is that um there's this work Workshop coming up in November it's     
4:02     
the brain neur wayi Workshop this is hosted by the National Institutes of Health uh this has uh I guess they going     
4:10     
to be a lot of talks I have actually already submitted something under my name I don't know if people want to     
4:16     
submit things under their name but you know it should be an interesting time uh I don't know if they have their     
4:22     
speaker was set yet it looks like they're a number of uh speakers uh Patrick manol being Brunton     
4:30     
those are people we know from narrow match some other people as well from the     
4:36     
Allen Institute in Stanford and other places uh Lake Richards um uh Doris sa     
4:45     
uh Aina federenko these are people who been various papers that we've     
4:52     
read uh session three uhab Bahan he's done uh he does a lot of     
5:00     
Naro inspired stuff uh let's see Metra har Harman she     
5:07     
said Northwestern she does a lot of stuff on motor control um yeah so I mean we have a lot     
5:14     
of people here a lot of good uh research and it'll be interesting to     
5:20     
see uh so yeah register for that I think you can still submit abstracts I think up until uh Tuesday if you want to     
5:28     
submit something and um you know or otherwise just attend on your own you register for that and I     
5:35     
think it's free you can do this virtually and so that's that's a that might be a very fruitful     
5:43     
event the last thing I'll update us on is that coming up in November as well as     
5:49     
the applied active inference Symposium so this is uh it's something that I'm     
5:55     
actually involved with as a member of the uh scientific advisory committee and     
6:01     
you know we're kind of putting together an event on applied active inference so     
6:07     
this is where we're kind of doing you know uh soliciting talks at this point     
6:14     
uh soliciting U people being involved in this so this is U this is actually the     
6:21     
coda for uh active inference and you know they they have     
6:27     
this uh it's just kind of an embryonic stages now but we have had a couple a     
6:33     
number of talks in in the p in past years so in 2021 there was a Carl     
6:38     
friston series that has like three videos associated with it in 2022 there     
6:44     
was an event on robotics which covered you know that was actually really good featured a lot of     
6:50     
different applications of active influence to robotics of course then last year there was enacting ecosystems of shared     
6:58     
intelligence and then this year is the act of apply to active infos so this is you know you can     
7:05     
register for this or submit a talk I'm going to actually submit a talk for our work I'm not done with it yet but we'll     
7:12     
we'll see you know what that looks like when I'm anded ready to submit     
7:18     
it um and the other thing that they're looking for here is of course they're     
7:24     
looking for sponsoring institutions sponsoring organizations but also they're looking for some component open     
7:31     
science and open source and so we had a discussion in the     
7:36     
slack a short discussion about maybe role of perhaps neurop Fedora in you     
7:43     
know doing you know being like an open source sort of uh involve having some     
7:49     
open source involvement um you know there are also opportunities for making the event more     
7:56     
friendly to you know reuse having this Open Access component where you're     
8:01     
publishing the work automatically as it's being generated or some other ideas that they had so you know this is an     
8:08     
opportunity I think for some involvement and uh you know I think it'll be a really nice event so I don't know Morgan     
8:15     
that's something to say he's unmuted yeah well I just just um you     
8:21     
know I I I saw that and you know I think that would be that would be awesome um     
8:28     
certainly coner you know I would say in terms of     
8:34     
tools you know Nur fedora's got a more computational Neuroscience Focus well I     
8:40     
should say more of our documentation is focused on the the computational Neuroscience     
8:47     
tools and um which includes a couple examples of     
8:53     
things that you know you might say are kind of active in tools um you know like     
9:03     
um what would be like example I mean I I don't think RX and fur is in there yet     
9:10     
but um but like Pi mdp or um anyway I     
9:17     
think that' be cool and like would you know con certainly bring it up to Anker in terms of like you know yeah he he     
9:26     
he'd probably know more in terms of you know where where there's good overlap     
9:31     
there or certainly you know again like um I mean I was just kind of looking     
9:39     
at you know how is active inference used     
9:46     
um you know in software in terms of kind of what what areas     
9:54     
um and yeah and of was like     
9:59     
like RL policy um you know RL agent     
10:09     
policy obviously is the is the big one with like you certainly some     
10:17     
examples in robotics you know which is like absolutely related to it     
10:24     
yeah um yeah like would love to see Ryan     
10:30     
Smith's stuff like his step-by-step tutorial but but not using the the the     
10:41     
SPM mat lab scripts but using like Pi uh MGP     
10:50     
yeah like holy using that which which probably has its own examples anyway I I     
10:56     
I did start kind of digging in there you know and then I saw that that uh the the     
11:02     
act of inference had a new talk about from a machine learning researcher from     
11:08     
versus you know so this is the the you know AI company that     
11:14     
has Carl firston as their Scientific Advisor or chief     
11:21     
science officer I don't got him some some senior position     
11:28     
um and it it's just a nice example of it in terms of you     
11:35     
know I don't know if it's correct to say like it's Bay optimal but it's it's it's     
11:40     
about you know RL policy you know training and and     
11:50     
definitely certain efficiencies or um     
11:56     
optimizations and yeah yeah it's it's it's a nice overview it definitely     
12:03     
overlaps with you know with World models right yeah or certainly like     
12:10     
yeah very very related yeah I don't know if one of     
12:15     
their groups are submitting something to the world models issue but I was thinking yeah yes you I mean this is     
12:24     
this is just for the for the for the meeting but um     
12:29     
yeah I mean I was I was wondering if there was or you know like like or somebody     
12:36     
from RX iner you know JL     
12:41     
already doing a talk or doing something I don't know yeah interesting yeah a     
12:50     
handful of they've certainly done previous like active Institute talks or     
12:55     
like like um demos right     
13:01     
right yeah yeah I think that's yeah it's definitely I'm trying to think of what we could contribute that's sort of     
13:09     
applied I mean know applied meaning like I guess that it's not sort of     
13:15     
exclusively theoretical I don't really know what what the I don't think their Criterion for Applied is like really     
13:22     
strong so but you know we we don't I mean I guess we do we do a lot     
13:28     
of stuff with open Source it's just a matter of like how do you apply some of the stuff and then what what do we do     
13:34     
that's like intersects with act inflence active inflence so yeah yeah     
13:42     
yeah yeah I I I you know I was kind of looking for any     
13:48     
kind of potential you know some some examples in computational Psychiatry and     
13:56     
you know like honestly that's kind of that is Ryan Smith's area I mean that's that is kind of you     
14:03     
know certainly what what he was applying the data to or     
14:10     
um applying his tools to that kind of data     
14:15     
um and uh yeah would certainly love to see     
14:20     
some more examples in in a kind of um like compell     
14:27     
3D you know in terms of pattern formation morphogenesis I mean there's this you know Michael L paper of course     
14:35     
from uh couple years ago active inference morphogenesis computational     
14:42     
Psychiatry it's just you know that like that's literally like the title     
14:47     
yeah which one is that the there's so many 11 papers yeah yeah I I'll I'll     
14:53     
I'll drop a link okay yeah that'll be good yeah all right thank you yeah that's     
14:59     
great uh so I just wanted to get your thoughts on that and then um you know kind of it's something that I think we     
15:06     
should take advantage of uh as something to kind of boost the lab and boost our     
15:13     
what we're doing okay so that's the link that Morgan has yeah so as you see that's     
15:20     
literally the title it's like all my favorite topics     
15:25     
is just just as the title oh okay this is active morphogenesis and     
15:30     
computational Psychiatry okay and this is uh so this says like     
15:36     
they're approach computational Psychiatry and it's kind of like well they they kind of go     
15:43     
over um yeah yeah I mean it's good it's good for the references in in you know     
15:51     
he or you know his students collaborators do a good example of     
15:58     
covering the um uh as well as covering like the friston     
16:05     
literature itself you know like like you know c c because yeah because he's done     
16:12     
some things it looked like um like 2017 2018 papers that um Carl     
16:23     
did with um uh Stephan keable and um     
16:31     
and and a french guy but whose name I'm blanking on right now just a french guy just French I mean     
16:40     
these are these are all former students of his you know okay yeah like like you     
16:45     
know Stephan was a student of his like 2000 and this um so I I just haven't     
16:53     
gone through the actual you know checking those particular references I     
16:59     
mean I think or here's here's one where it's like knowing one's place a free energy approach to pattern regulation oh     
17:07     
okay just in terms of kind of the morphogenesis who's the author of that     
17:13     
that that's first and first author then yeah it's 2015 I mean we'll see we'll see I maybe     
17:20     
maybe yeah maybe maybe all the morphogenesis active inference morphogenesis biger are going to be left     
17:26     
literally yeah I know I think that's probably he's got the for safe safe bet yeah I'm     
17:35     
sure yeah so I don't yeah I don't know um it's interesting     
17:42     
so okay uh yeah yeah yeah no I I already see another one which is it's like it's     
17:51     
a different first author but it's it's love and and last author anyway that     
17:56     
that would be another interesting Direction Just terms of the software tools right like like you know again um     
18:05     
has has Le yeah any good computational examples     
18:11     
of that in morphogenesis you know that conversational Psychiatry kind of by     
18:17     
definition is is you know applied RL work right yeah so so I mean how do you     
18:24     
find their approach to computational psychiatry um like oh yeah I mean I I I think it's     
18:34     
um you know [Music] he you know you could certainly count     
18:42     
frisen as one of the it would be like students of friston who would have been     
18:49     
some of the first people doing this not it it's because they're the queen square     
18:56     
is this just interesting geograph rical area where you have the Institute of     
19:04     
um what's the uh there's a great I forget the exact     
19:11     
acronym but there's a great computational Neuroscience Institute it's right next     
19:16     
to the functional Imaging lab that's next door right so yeah like like it's     
19:22     
just down the street and it's like right next to the Institute of cognitive Neuroscience or you know like like     
19:29     
you know and neurosurgeries across the street and Institute of Neurology you     
19:34     
know it's like like all they're all there in Queens square right um I mean which is which is one of     
19:42     
those like little London Square Parks you know where yeah and and you     
19:51     
can almost yeah every day you can you can find John Asher outside smoking     
19:57     
cigarettes sorry he's a he's the the lead for SPF and software development oh     
20:03     
okay yeah um and yeah like I'm just trying to     
20:11     
remember some of the name you know so some of the kind of you know machine     
20:17     
learning papers that everybody knows um not not Chris Bishop anyway it's like     
20:25     
2,000 the kind of people who were doing you know foundational variational Bas papers and things like that were at     
20:33     
the computational Neuroscience Institute and you     
20:38     
know that that kind of cross-pollination in terms of people looking at behavioral data and     
20:46     
applying these same models with you know various various approaches although it     
20:53     
was it was primarily um looking at these     
21:00     
um applying these Bandit um Bandit models to yeah     
21:09     
kind of gambling tasks yeah that was some of     
21:15     
the yeah yeah so people people there then re     
21:23     
Reed monu had come over and was working as a um or like     
21:29     
not sabatical he had a cross appointment so he was he was Technic you know he's     
21:34     
he's both professor of Virginia Tech but he was also visiting Professor there and     
21:40     
you know I think we talked a couple weeks ago about his early papers with     
21:45     
like Peter Dian yeah you know from like the late 90s mid mid 90s ID 90s yeah     
21:56     
yeah so again like like it was     
22:02     
um pretty Central site there for for computational Psychiatry oh     
22:09     
yeah and this this past week has been the big computational Psychiatry um I     
22:17     
think forget if they call it Workshop or conference that takes place in Zurich which is is essentially hosted by     
22:25     
another student of conf Cl Stefan     
22:30     
um and and it has a lot like like I bet if we looked at the the list of speakers     
22:38     
it would be like Jean Deo Stefan keable like you know would wouldn't be     
22:45     
surprised if um uh Reed moniku is there     
22:50     
or you know yeah here I I'll pull that up okay yeah and and and one one last     
22:58     
thing um just uh     
23:05     
the mathematics of intelligence um at ipam this like Wednesday through Friday     
23:16     
um I I think I posted that in     
23:23     
um uh why am I already sorry I'm already     
23:29     
next year's conference maybe because it's is already over so this is     
23:36     
translational neurom modeling and well that's that's that's CL stefon's group is the translational     
23:44     
neuromodeling um unit yeah okay and um and then this     
23:51     
is computational Psychiatry yeah computational Psychiatry course 2024 yeah um and yep look at that     
24:00     
keynote speakers Rick Adams Jean Deno     
24:06     
uh you know Michael brav spear um I'm just seeing     
24:13     
people yeah all the some famous people I     
24:19     
mean what what kind of topics do they cover it's this it's that kind of stuff     
24:25     
it's it's you know the app application of     
24:31     
um reinforcement learning models to to behavioral     
24:37     
and neuroimaging data um where you know kind of the the     
24:44     
parameters of the the the modeling relate     
24:50     
[Music] to yeah kind of um     
24:58     
you know Co cognitive relate to cognitive um     
25:05     
um features yeah right so you know again     
25:10     
like stereotypical example like would be you know modeling modeling the you know     
25:20     
um gambling or or you know stock price     
25:25     
you know kind of like um stock trading data modeling or you know     
25:35     
um kind of you're you're you're engaging in some economic     
25:41     
task or or some gambling task and from the way you're playing and a RL model     
25:50     
applied to that you can show the parameters of the model relate to your     
25:55     
kind of risk div verness okay oh like yeah your your strategy     
26:01     
basically yeah yeah yeah it's like it's like the game game game     
26:08     
theoretic Parts you know again of of the model have this correspondence to a a     
26:16     
psychological feature yeah     
26:23     
right yeah and and yeah certainly that's the     
26:31     
it's the idea yeah that that that that's certainly you know one yeah I I and I think um and     
26:40     
again R Ryan Smith who's I see his his faculty there too um because his     
26:46     
stepbystep tutorial you know is is is     
26:51     
okay there we go very very you know that one's active inference but you know     
26:57     
again he's the one who showed me or you know his his tutorial you can     
27:04     
see kind of where active inference lives in a kind of Greater reinforcement     
27:11     
learning set of set of you know modeling issu modeling issues or you know     
27:22     
um it in a sense it represents a particular     
27:32     
um policy training strategy yeah right yeah I mean you know again     
27:41     
that's that kind of one particular perspective on it but but certainly any any perspective     
27:48     
you take on RL you can you can kind of translate that into an active inference     
27:55     
um TR tradeoff     
28:02     
yeah yeah it wasn't I believe quite so aware of like the connection between     
28:08     
reinforcement learning and active inference until you brought up this part so yeah I mean for me like like Ryan     
28:17     
Smith's uh active inference Institute talk where he just goes through his     
28:23     
paper yeah was was the the eye opening     
28:29     
that was when I was just like oh wait they're like oh that's it's a tradeoff     
28:34     
between these kind of competing uh um yeah these competing     
28:41     
perspectives and and you know and that also sounded you know just again like     
28:47     
knowing firsten from his neur Imaging work I was like oh that sounds remarkably forian too in the sense of     
28:54     
like of course it's some sort of kind of like optimal compromise between yeah     
29:03     
yeah um yeah so excuse me so let me     
29:10     
just say again that the um in slack     
29:16     
excuse me I'll go get a glass of water or something okay um but in slack here's     
29:23     
the um I'll just drop this into     
29:30     
CH but here's the ipam um you know Institute of pure and     
29:35     
implied math is doing the did this um well they did a three-day thing on     
29:43     
mathematics of intelligence tutorials for mathematics and intelligence yeah which had you know like three or four     
29:53     
great speakers um including either momenta Jad     
29:59     
who was a speaker plus I believe the host or the organizer yeah and     
30:08     
um so she she focused specifically on     
30:14     
the history of reinforcement learning well she focus on the history     
30:20     
plus kind of the overview and um she's the one who had     
30:26     
the I put this in the chat the great comment I don't I don't know why the the     
30:33     
the history of 20th century involves putting cats and boxes but but there we are yeah I have a     
30:42     
whole slideshow of like cats and Neuroscience and like you can go through papers and books and see these really     
30:48     
nice drawings of cats but they're in these like weird experimental settings yeah yeah so I I I thought that fit with     
30:55     
the with the political theme of this week you know yeah oh yeah cat you know     
31:01     
I thought that was nice nice overlap you know little synchronicity yeah um and uh     
31:09     
so yeah she she wasn't specifically talking about trer but but as we know     
31:15     
yes cats have been used for a lot of things yeah so she was doing a really nice history I think she was focused on     
31:22     
um Watson you know like early 20th century Watson     
31:28     
behaviorism oh okay yeah yeah and yeah she like like I really liked the I     
31:35     
really lik the overview and she she had you know again     
31:40     
like like two three other people pick to cover animal     
31:48     
cognition well anyway it's all it's all on that schedule um     
31:55     
so really nice overview that absolutely relates     
32:02     
to you know this is the greater context in which active inference     
32:07     
lives okay yeah yeah I was gonna say it looks like we also have some uh     
32:12     
evolutionary computation Josh bongard right right so I think he he     
32:19     
ends finishes it out right so I think that's like like I think he's the the     
32:26     
Capper maybe is somewhat also a standin for for     
32:31     
Micha 11an yeah if you will you know in the to like like future directions you     
32:40     
know yeah yeah yeah they also have Scott pagee diverse     
32:46     
intelligence is the problem solve yeah yeah um yeah they have yeah uh yeah I     
32:54     
mean yeah this is good stuff I this is really br yeah I you know again I've only listened     
33:02     
to Ida's stuff so far but um and you know like just let me     
33:09     
also you know she's she's one of the people who's definitely produced some     
33:15     
very relevant software tools that that it's it's what was her     
33:23     
Nur was like anyway I I'll I'll find it but it was     
33:29     
something like neuro bench or something like that where just like recreating you know kind     
33:36     
of animal behavior experiments to to then apply RL     
33:41     
models yeah     
33:47     
and yeah that sounds great um yeah I mean you know it's it's nice to have     
33:53     
like this sort of in context view of absolutely AC so there ultimately there     
34:01     
Roots back to like behaviorism yeah so it's interesting     
34:06     
yeah I know that like the connection between behaviorism and modern reinforcement computational     
34:12     
reinforcement is interesting but yeah yeah yeah and and you     
34:19     
know I know it was a long time ago now but that is it's that is exactly how I     
34:25     
started okay well yeah it's like I I was doing I got a Howard Hughes Medical     
34:31     
Institute Grant to do reinforcement learning in invertebrates okay where where I I was     
34:38     
TR you know I built operant Chambers for for invertebrates to see     
34:44     
yeah like how long how long an RL schedule could I get them on in terms of     
34:51     
how many how many lever presses could I get out of a out of a crab or     
34:56     
grayfish yeah yeah which you know good stuff     
35:04     
yeah well thank you Morgan for that overview and resources um I guess Jesse if you're     
35:12     
ready you can give an update yeah is my mic working     
35:21     
okay um not not really a whole lot outside of what what you already said     
35:27     
but but to review that um     
35:32     
uh for for Valeria things are a little bit different in Chile so it's I think     
35:38     
it's more like a combined undergraduate master's program     
35:44     
and but but like being able to practice law is a different pathway so um it's     
35:50     
not I'm not really sure what the equivalent would be it's not like someone writing an undergraduate thesis it's a little bit more than that but but     
35:57     
either way um it's been exciting for them and I just just a a     
36:04     
uh uh something not quite sentimental but also like I were like way way back     
36:11     
before before I really even joined the lab that the original collaboration was there and it was it was a nice thing um     
36:19     
to do and then it kind of led to both of us being uh doing things in in like     
36:26     
technology spaces more or Society ethics it would lead to society ethics back     
36:31     
then and um stuff like that and I think     
36:36     
that's the area she is specializing in ultimately too so that's cool um beyond     
36:42     
that um we had the meetings this week     
36:48     
for for futures and CTIC reading group as Bradley said um mostly just went over     
36:55     
the world models paper but also so um I'm continuing to push some structure     
37:01     
forward through joepro and the website um I did not get to     
37:06     
do anything um I still have to do some more meetings     
37:12     
with you Albany uh but but there's sort of a a lot of things pending in that     
37:19     
space uh that I'm I'm quite excited for     
37:25     
um yeah uh the there's there were some things on the     
37:30     
um like administrative side going on as well there's a few there's a few updates     
37:36     
about some grants that I'm looking to um applying for I'm I'm looking at     
37:43     
something with the foresight Institute I think I made it to like just the spring round for one of their of their     
37:50     
opportunities which is like nice but not doesn't really mean anything yet um     
37:59     
and uh oh um there's     
38:05     
uh uh I won't say so much here but um other sort of related good news is uh     
38:13     
Jen has started her um MSW program and has found some opportunities related to     
38:18     
that which might uh come into play for society ethics Tech     
38:25     
and the mental health working group too uh so could for that     
38:32     
too um that's that's pretty much it a lot of the work oh I guess one other     
38:39     
thing um about cognition Futures is     
38:46     
um I Unearthed a little bit of things I suppose about like embodied ner     
38:51     
phenomenology which is sort of Amanda's project from from the methods group and     
38:57     
and things there and it was it was I basically I put a page I should I'll link it somewhere eventually but     
39:05     
um it has a page now on joepro and it's just it's cool to just see the the the     
39:12     
presentation and some of the slides some of the commentary like putting all in one spot uh because it's a it's a it's a     
39:20     
nice project and it's something that's you know obviously related to the overall methods project which is     
39:26     
something I'm also uh sort of restructuring not restructuring but but getting a a front     
39:35     
page in order and then thinking okay what what can we what do we do with that     
39:40     
um where where is sort of the next steps on that so it's sort of it's nice because it feel like this week has been     
39:46     
a bit of a step actually into the I won't say high functioning but     
39:52     
maybe normal or more normal functioning of a lot of these sort of meetings and     
39:57     
processes and projects are coming a little bit more in rhythm again so uh it's been a good week for that and um     
40:06     
there's also some talk about establishing a regular scheduled meeting     
40:11     
time for the mental health paradigms and perspectives the working group that's kind of on in development I'm still     
40:21     
um um there are a few people that I I'm look to basically     
40:30     
be I don't know if advis is the right word but there's people in in in the field that we have some connections to     
40:37     
that um I don't know they're going to be able to make every meeting per se but but just like     
40:43     
uh there's some things in the works for that too but um I think we've talked     
40:49     
about maybe Fridays for the the actual meeting time     
40:55     
and uh it's kind of I think it mostly be similar actually more similar to sort of like um not the open Office hours     
41:03     
meetings on Friday not sort of as timing but more like I don't think it would be a regular standing hourong     
41:10     
meeting every week like it won't be like a reading group meeting or the cognition Futures meeting it'll be a little bit     
41:17     
more project oriented it could turn into a reading group but but but um you know     
41:23     
it will be a little smaller scale especially at first uh yeah and then     
41:32     
um yeah there's other administrative stuff but this just kind of boring things about getting used     
41:39     
to uh working with institutions that sponsor grants and and and waiting     
41:46     
deeper into that that you know chaotic space at times um so that's that's what     
41:54     
I've been up to that's that's basically all of my updates for now     
41:59     
yeah well that's good um thank you for that um you know it's good to see some     
42:06     
evolution of a lot of this administrative stuff pushes for getting     
42:12     
the meetings restarted for the year I I looked at the schedule for cognition     
42:17     
Futures I don't think we had had a meeting since April so it's like kind of yeah they've been there was like a     
42:24     
definite like summer hius there and we had like one or two and like we met that     
42:30     
time we haven't had an official one in a long time yeah which is you know I mean it's I     
42:37     
guess it's okay but it's like you know it's like I'm just surprised I thought we had had some more recently     
42:46     
but yeah they they I didn't and I didn't I kind of start there's a whole discussion to be     
42:52     
having like um I I'm     
42:58     
I'm not as inclined to to push certain things into notion as I have     
43:04     
been uh which is you know Dealers Choice if people want to use that they can but     
43:10     
like some of the C future stuff like there has there definitely hasn't been like     
43:18     
the there there isn't any like notes there but for this for like the meetings     
43:24     
that that did happen that like not everybody was at or just like discussion projects and stuff like that um I'm kind     
43:31     
of putting those files into the the document like the Google Document structure because I think     
43:38     
it's I know I know I'm I'm I don't like the the the zoo of of things and     
43:45     
strategies but I think I'm that's sort of a longer term thing I suppose but yeah um either way there was     
43:52     
there was this is probably the longest break of coition features that we've had in a while and in part     
44:00     
because um I mean it's the grad school finals and then summer and then a bunch of other stuff and everybody was sort of     
44:07     
there's a period in August that I think was just too soon to try to restart it because we we kept playing like musical     
44:14     
chairs about it um but it's good it's nice oh but it's     
44:20     
um uh I'm looking forward to continuing with that again yeah yeah it's great     
44:28     
so it sounds yeah it sounds like you we G to have a good fall for that yeah and I still need to     
44:36     
um we there are people that have expressed a little bit of interest uh I have to follow up on but more about that     
44:44     
later I was gonna ask you Morgan um the I'm afraid I might join a little bit     
44:50     
later something but you were talking about the tradeoff between active uh inference and re enforcement learning I     
44:57     
was wondering if you might be willing to say a few more words about on that so uh the     
45:08     
uh exploration exploitation tradeoff that you might see     
45:16     
in in kind of yeah RL train in in some     
45:22     
some environment where     
45:27     
that that would be you know I'm trying to think of the the particular RL terms     
45:34     
for it and um like a you know stock trading or     
45:42     
gambling task but but there's a there's a similar you know kind     
45:51     
of yeah I would need to look that up but but in in kind of ecology would be     
45:58     
the exploration exploitation or animal behavior what what field is     
46:06     
that from I think they use it across Fields yeah it's it's across Fields you know     
46:13     
but like what what what is that um would you call that specific you know     
46:20     
you say that's from animal behavior anyways but you know what I     
46:25     
mean you know I'm so ignorant of all things     
46:31     
neuroscience and so um I can understand what you're saying I I don't have great     
46:37     
domain yeah so again and and this comes     
46:43     
out when you read kind of like these first certainly early uh active     
46:51     
inference papers is that um you know this is very much about     
46:59     
action right okay like like and and yeah     
47:06     
um things that generalize across you know across animals yeah like like     
47:12     
attempts to to find things that extend across animals and     
47:20     
and where you know like energy energy is limited right     
47:27     
right yeah yeah so there's a couple things that that I should go through in     
47:33     
terms of like we're assuming this this and this yeah and and then you get then     
47:40     
you find active inference to be a you know I mean these the assumptions are very general and very you know very easy     
47:47     
to to to understand but then it's just like then active inference is kind of this optimal tradeoff between that or     
47:55     
certainly is a tradeoff that is is attempting to     
48:03     
maximize what's the way that first     
48:10     
like the reduction of surprise yeah yeah surpr     
48:16     
surprisal is is you know another another Frisian     
48:21     
thing is to make new words     
48:29     
or use use words that are yeah yeah so if if you don't if if you don't know his     
48:37     
papers like Nur Imaging papers what's the um there's a there's a a running     
48:44     
joke in his papers that he will always use Contra     
48:49     
distinction okay and and yeah what does that mean     
48:57     
sorry uh I I it's like you know is it     
49:03     
like in opposition too or like     
49:08     
like it makes sense from Context it's it's one of those words where it's just like yeah you could have     
49:15     
you could have used something else yeah quite easily     
49:20     
interesting yeah yeah you know so there is kind of a     
49:27     
um yeah there there it would be easy to to     
49:33     
train chat GPT to have to to write in a fian     
49:39     
manner because because he's got a     
49:45     
style interesting I wonder if there isn't a fren bot somewhere online there should     
49:51     
be I mean guar guaranteed that n imager has     
49:56     
done that like we have leot there's yeah if there's a Le bot there's got to be a     
50:02     
first     
50:07     
in yeah that's great you know there were people doing that before there was chat     
50:13     
GPT oh yeah yeah so just because uh you seem to be     
50:21     
the friston expert I I saw an interview with him once where he was talking about how [Music]     
50:28     
um kind I don't remember exactly what it was saying but I think he was saying that uh that one of the things that he     
50:34     
really struggled with was this idea of ambiguity and I think that might have been I suspect well might be reflected     
50:41     
in his modeling um in your opinion is do do you see that at     
50:47     
all well if if buy imy um like     
50:54     
uncertainty no uh more uh the idea where like because lot of     
51:00     
this bean stuff is like you select the one thing that is most optimal where um     
51:05     
there are contexts where that's not always the case where there like perhaps are two things that are multiple things     
51:13     
that have equal um uh priority or or different Pathways you     
51:21     
know um yeah I'm not not exactly sure I mean it' be     
51:27     
interesting to see where where he said that you know I'll dig it up he was talking to     
51:32     
Lex yeah oh he's talking to Lex bman um I mean he can certainly be very     
51:40     
philosophical um uh you know again like he     
51:46     
he's super super remarkable guy right I mean he's a     
51:52     
psychiatrist um by training uh but he but but he did his     
52:00     
undergraduate uh degree in maths at Cambridge so you know he's he's a pretty     
52:06     
you know he's obviously a pretty brilliant mathematician and then um the     
52:11     
reason the reason I'm familiar with him is that he wrote a package in the 90s     
52:16     
when he was still uh like Nur Imaging was just     
52:22     
starting uh and he was at the pet center and Hammersmith     
52:28     
hospital um and this was like early you know mat lab ruled the the computational     
52:37     
space back then and uh yeah he wrote the first scripts to do statistical     
52:43     
parametric mapping uh again of of pet data you know     
52:49     
but then that became that became uh well then everybody switched to doing urai     
52:55     
and and SPM was adapted to that and you know people started doing boxal based     
53:02     
morphometry and you know that became kind of like a widely used there was     
53:08     
like fmri and anatomical MRI became the you know the the go-to     
53:15     
tools for neur Imaging and um yeah but uh he's you know I think     
53:24     
it's only in like the last five years years that he's he's now I think he's officially said that he's he's a     
53:31     
philosopher now he's passed he passed off the     
53:37     
conversational stuff to to John Ash at the at the Phil every everybody     
53:43     
calls it the Phil but it's the the functional Imaging lab     
53:48     
fil sounds like I have much to learn thanks for thr me in it's yeah it's right there right there in Queen square     
53:54     
and as I was saying like Queen square is this really interesting uh um you know     
54:01     
very small little square just on the other side is Russell Square which is you know much larger right     
54:08     
like 20 times larger and and um but this     
54:14     
little tiny Square on the other just just on like the other side of one     
54:19     
building um has you know six or seven     
54:24     
different neurofocus institutes so Institute of cognitive     
54:29     
Neuroscience Institute of I forget what it's maybe it's I want to say it's like     
54:34     
Institute of computational Neuroscience but that doesn't sound right like it's it's got some other um and then yeah     
54:42     
neurosurgery Institute of Neurology because that's ion um and     
54:48     
uh and then just at the North like like there's another big Institute there     
54:54     
which has a lot of computation psychi is um um it's the MOX plun like like like     
55:03     
obviously MOX plun are these German institutes right but MOX plun has two I     
55:08     
think two institutes outside of Germany and one is in London which is     
55:14     
like Institute of computational Psychiatry it's like computational psychiatry in aging and then there's     
55:21     
another one in Florida oh the you know     
55:26     
which is like Institute of neural Dynamics or something like that yeah     
55:32     
something like that like anyway I made up the last word but like it's of neural something you know     
55:41     
and it looks like a it looks kind of like an like this is sound right like a     
55:47     
like an allen Institute but you know MOX plun Florida     
55:53     
yeah yeah wow I had no idea I'll look into this yeah     
56:02     
yeah right yeah that that's a great uh great conversation about     
56:09     
that so I don't know Trevor if you had any updates oh thank you um so I I submitted     
56:16     
a paper to to get peer reviewed through a service called review comments and they they told me you don't have any     
56:23     
experimental stuff so we don't like it or we won't look at it like so that's all right I'm going to go through uh     
56:30     
there's another peer review service called a peer community in perhaps youall are familiar with it um so I'm     
56:37     
gonna try doing that one see if they will look at my paper so     
56:42     
alas uh without experimental data one faces obstacles but it's okay     
56:49     
nothing's ins surmountable yeah that's all in my world so that     
56:56     
that's in reference to that paper that you showed last week that's right yeah     
57:02     
well it's you know that might be something where you it's like you might have to submit it as like some sort of     
57:09     
review or position paper sometimes the different journals have different categories for things that don't have     
57:16     
data you know sometimes they're hypothesis and theory papers they they have different terms     
57:22     
for them but basically you can get them published you know it's just depends on the journal     
57:29     
and depends on how they what they're looking for in terms of uh content     
57:35     
because some journals you know they have certain points of view or they don't include certain areas of inquiry so you     
57:43     
have to be careful you just have to do your kind of look through the journals you're interested in and see what     
57:49     
they're doing in terms of uh you know the different categories of papers the different types of content that they     
57:56     
publish and see if your paper is a good match to what was the the word that you used     
58:03     
at the beginning of like the article type like a review or something sometimes yeah like a literature review     
58:08     
or a review sometimes or sometimes they have hypothesis and theory I know Frontiers has that um they also have     
58:17     
like opinion or position paper they'll have weird names for them but basically     
58:22     
they're like papers that have that don't address a data analysis and so you know     
58:31     
yeah oh I appreciate yeah I will look more into these things okay yeah     
58:37     
yeah all right so that's that's great uh thanks for the updates I don't know shom     
58:42     
was here and then he left and probably network issues but um it's okay um     
58:49     
thanks for thinking of us sh okay so I'm going to share my screen I want to get into this discussion is     
58:57     
actually Conrad cording who uh posed the question and there's been a lot of talk     
59:03     
of neuro AI of course we did the the first Naro AI uh narom match course was     
59:09     
this summer and there's this upcoming conference on N Ai and so this is kind     
59:14     
of fitting this is a set of sort of questions he's soliciting from the     
59:20     
community so everyone is talking about narrow AI what do you see as the main     
59:26     
questions that go with the field make AI better through neuro is relatively easy     
59:31     
but which questions about brains does neuroi answered so basically um it's like neuro AI is the     
59:40     
intersection of Neuroscience and artificial intelligence or     
59:46     
AI you can use Neuroscience to inspire better Ai and of course you know a lot     
59:52     
of your standard models of AI are based on some Neuroscience     
59:57     
principle um a lot of the you know a lot of connectionist work uh a lot of the sort of the you     
1:00:05     
know the basis for you know the way we think about weights and things like that     
1:00:12     
and so you know that's that's easy I mean we we've done that but then the question is if you flip it around and     
1:00:18     
you say if neuro AI can answer questions about brains what are those     
1:00:24     
questions so that's or we use Neuroscience or we use artificial intelligence models to address questions     
1:00:31     
of Neuroscience and you think about this in terms of like well how do we do that     
1:00:36     
and the answer is of course that we can model the brain of course but then we can also compare Neuroscience models     
1:00:44     
with brains so you know there's been a lot of that sort of benchmarking uh     
1:00:51     
between uh artificial intelligence models and brains so people have done     
1:00:57     
experiments where they train a model on visual uh classification tasks and then     
1:01:02     
look at what's happening like in V1 or V2 and you know they can actually get uh     
1:01:08     
a comp there there's like there number of benchmarks and comparisons that you can do for that people have been     
1:01:15     
developing that um those sort of approaches but you know there are a lot of questions we can actually address     
1:01:22     
there a lot of you know Neuroscience is notorious for not really having a lot of Theory and I know we've just talked     
1:01:28     
about active inference which may seem a little strange but in general Neuroscience does not really Embrace     
1:01:34     
theory that much and so sometimes you have to really kind of pull teeth to ask     
1:01:40     
you know to sort of frame theoretical questions about the brain so then uh Conrad his next line is     
1:01:48     
something like and maybe why I'm asking I see a lot of paper posters that read a     
1:01:54     
bit like did this engineering thing with neural data and have relatively Widow on     
1:02:01     
this is how it matters for Neuroscience also there are people that really valiantly work on good questions     
1:02:09     
so you know people are actually asking good questions in Neuroscience they're not particularly theoretical questions     
1:02:16     
but they're questions that you have to address with experiments but you can also address with modeling and of course     
1:02:23     
with some sort of uh engineering approach maybe or some alternate     
1:02:29     
approach to get you know maybe take neural data and use it to answer that     
1:02:34     
question so that's uh where this is going this this     
1:02:40     
thread uh Jessie says it's funny as it has some strong parallels to the use of     
1:02:45     
AI and other Industries or products because we can mix it in as a major driver yeah there is a lot of hyper on     
1:02:52     
AI it's like it has J AI so buy our thing Thing by our Theory you know by     
1:02:59     
our uh exercise machine something uh but you know to not make     
1:03:05     
this just another sort of bland AI tie in you know they're really kind of trying to     
1:03:11     
ask um you know that he's I think he's trying to focus this discussion on you     
1:03:16     
know from neuroscientists we kind of theoretical questions would they ask so yeah I think that's a good point     
1:03:23     
Jesse so this is the part of this thread this was actually a long     
1:03:28     
thread uh one question is what are sparse neural network architectures that solve real world problems efficiently     
1:03:35     
and effectively and then of course so the the question is what are the sparse     
1:03:42     
Network architectures that solve problems efficiently and effectively so     
1:03:48     
in other words that the function is there and that it's efficient and so you     
1:03:53     
could ask about motor control learn in feature detection Etc so that's one     
1:03:59     
question and then Conrad responds there must be an infinite number of them no maybe we could find to the question a     
1:04:06     
bit okay so yeah that isn't like a very focused question then the more more focused question there is given the time     
1:04:13     
and resource consuming nature of finding them the network architectures denovo     
1:04:19     
using machine learning and of course you're looking at uh maybe like you know uh neural or or connectomes from say     
1:04:27     
like neuroimaging and you're looking at you're trying to find those the optimal     
1:04:33     
networks using machine learning and so there's this interaction between Ai and Neuroscience data what are concrete     
1:04:40     
known examples of sparse neural network architectures that solve problems     
1:04:45     
efficiently and effectively so this in this case then you may have a neural network     
1:04:51     
architecture that can actually produce those outcomes so if you know what that architecture as an advance you can sort     
1:04:58     
of pre-train your model and you know apply it to something like robotics or     
1:05:04     
apply it to something like a brain machine interface or whatever so that that's one one set of questions I think     
1:05:11     
it's an interesting set of questions around neural network architectures and     
1:05:16     
connectos there are a lot of connections there that you know are kind of left unsa but that's maybe one area     
1:05:24     
think uh Kevin Mitchell says uh efficiency has to be a big one so     
1:05:29     
efficiency of networks and efficiency of models especially with large models and data centers sucking up the energy of     
1:05:36     
small countries so this is where the brain can perform a lot of cognitive tasks very efficiently in terms of     
1:05:43     
energetics so our brains of course use relatively low amounts of energy to do a     
1:05:50     
lot of these cognitive tasks that it takes uh an AI model quite a bit more     
1:05:56     
energy to perform this has been a question actually if you look at a lot of this papers that compare artificial     
1:06:04     
neural networks and biological neural networks the question of Energy Efficiency always comes up or the     
1:06:10     
question of energetics always comes up so like you know neural networks use a     
1:06:15     
notoriously large amount of energy and you know to do things that are basic you know maybe maybe cognitive     
1:06:24     
you know and then you have a lot of really uh you know the human brain say     
1:06:30     
can do a lot of really Advanced cognitive tests with a fraction of the energy right so that's the idea and so     
1:06:38     
you know to make neural network models more efficient and then Conrad says on     
1:06:44     
on the why brains are efficient Direction where the can we steal efficiency ideas from brains and build     
1:06:50     
into Network's Direction so basically you could ask it both ways you could say     
1:06:55     
why are brains so energy efficient and you know the answer is probably because we just couldn't have     
1:07:02     
brains the size that they are and with the capacity they are of we had to eat all the time I mean we eat a lot anyways     
1:07:09     
but like we'd have to consume massive amounts of glucose if our brains were as     
1:07:14     
inefficient as neural network models so much so that we couldn't we'd be like uh     
1:07:20     
you know living in pods with just this glucose strip because we wouldn't be able to do anything else     
1:07:26     
so the brain necessarily have to be efficient but also that you know you could take the sort of the Energy     
1:07:33     
Efficiency of brains and sort of figure out why that is and build that into     
1:07:38     
networks using you know power from the power G or whatever so you could you     
1:07:45     
could answer the question both ways uh the third question here this is     
1:07:52     
from a computer scientist and their perspective I I think there are many many interesting cross-disciplinary     
1:07:58     
questions the term neuro AI sounds kind of unnecessary Neuroscience wasn't     
1:08:03     
inspiration of modern AI at least according to this person uh while some neuroscientists were the founders of the     
1:08:10     
discipline that we need a new term so yeah I mean I guess like you know     
1:08:16     
Neuroscience inspired modern AI as I mentioned you know we' we've gotten a lot of key Concepts from Neuroscience uh     
1:08:24     
of course modern AI founded by you know all sorts of people was kind of like cognitive science and it kind of you     
1:08:32     
know parallels with cognitive science so you know that's do we need a new term is     
1:08:37     
basically the idea that um you know maybe artificial intelligence isn't the     
1:08:43     
right term maybe it's artificial Neuroscience I don't know that's     
1:08:48     
interesting four is uh this is neuro dat lab how does biological learning work     
1:08:54     
which is a pretty broad question question but basically you know is     
1:08:59     
biological learning the same as artificial as we understand it today so if we we can learn something with a     
1:09:05     
neural network and it's it's efficient at least in terms of like performance and it's you know it works     
1:09:12     
does it work like biological learning or are we just assuming that we're you know are we just mimicking biological     
1:09:18     
learning and assuming that those results are are you know compliment I mean you     
1:09:23     
can compare they biologic or artificial models can learn the same things as biological models in some to some extent     
1:09:31     
but they maybe do so differently and they do so maybe independently of our     
1:09:36     
metaphor so that's that's kind of what they're asking about biological learning in this question but you know we so we     
1:09:43     
don't necessarily know biological W works just because we can simulate it with a     
1:09:49     
mod and then Tom Burns asks for me it's something like Are there natural     
1:09:54     
abstractions computational paradigms representations circuits Etc so are     
1:10:00     
there natural kinds of things like uh computational things in the brain or     
1:10:07     
representations that are common circuits that are common Etc uh so then you know you could ask     
1:10:14     
things like are there polysemantic neurons we know they're polysemantic     
1:10:19     
functions in the brain we know that you know brains even within our own brain we     
1:10:24     
can interpret symbols in different with different meanings we can assign multiple meanings of the same symbol of     
1:10:31     
course across brains that's true as well so are there polysemantic neurons then how does this develop     
1:10:37     
function and how can it go wrong how can we fix it so you know it leads from     
1:10:42     
these natural kinds to questions about different types of thing in the brain uh and then you know asking     
1:10:50     
functional and structural questions and developmental and evolutionary question questions and then of course also the     
1:10:58     
diagnosis of problems so that's good number five here is uh this is a kind of     
1:11:06     
a thread here where we have Zach danzinger uh talking about given the     
1:11:12     
current state of neuro AI work the only neuro questions they can address are one very conceptual so how could a circuit     
1:11:19     
of locally constrain elements compute something in general so this is something that's very much disconnected     
1:11:26     
from application so if you want to know like you know in a specific brain how     
1:11:32     
something works it's not really something you can answer right now you can get a a conceptual answer I guess um     
1:11:39     
but that's tough to work with or two methodological what can algorithms what     
1:11:46     
algorithms can explain an opaque network from sparse dat in other words if I only have a little bit of training data we've     
1:11:53     
talked about this with our developmental approach approaches where in development you have a far status set in the world     
1:12:01     
you know you focus on maybe one thing and explore intensely and then another     
1:12:06     
thing and explore it intensely and somehow you can start to generalize things you know and so we don't have     
1:12:13     
like infinite amounts of data in development but we somehow put together     
1:12:18     
uh different cognitive you know uh know we know things and we put together different cognitive functions now we     
1:12:25     
can't necessarily know everything that happens in a network so the network is     
1:12:31     
opaque and so we don't really know how relatively small amounts of data     
1:12:37     
translate into this you know what we have as adults so     
1:12:42     
that's that's kind of the question and you know they didn't really talk about developmental methods here but I think that's probably a key part of     
1:12:49     
it uh Miguel Nunes we know him from neurom match as well     
1:12:55     
what about also thinking in the questions Nur AI can help us formulate and only directly answer so you know the     
1:13:04     
idea here is that neuro AI can help inform some of the questions we ask so     
1:13:09     
if I have a neural network it can inspire me to think about the brain in different ways Elias Naro uh says     
1:13:16     
interpretability and control that's the what we can learn here what does it mean to understand a large neural system when     
1:13:24     
you have access to the activity of all the neurons all the time so this is     
1:13:29     
where you know we have of course inability we ask that question of neural     
1:13:34     
networks but we can also ask it of the brain because you know we want to know kind of what is responsible for the     
1:13:41     
outputed the network can we understand that in terms of specific connections or     
1:13:47     
specific neurons and of course the answer is not very clear it maybe it would never be clear because maybe the     
1:13:54     
you know there neuronal networks don't work like that um but we want to have at     
1:13:59     
least some ability to interpret what networks are doing we also want to be able to control those networks so yeah     
1:14:07     
it's but of course we have Technologies now in tendem with models that can give     
1:14:13     
us these more continuous measurements these more continuous monitoring techniques so that's another     
1:14:20     
thing that we can use number six is     
1:14:25     
um oh this is I think we talked about this question here the natural abstractions and then Lucas PUO Miller     
1:14:33     
says and at what cost in terms of energy consumption I hope the benefit cost ratio is being considered um if better     
1:14:42     
if by better AI we mean AI that is more aligned or similar to humans or animals     
1:14:48     
then I don't think it's a separate effort from using a to understand the brain it's the back and forth between     
1:14:53     
the two that makes it narrow AI so neuro AI is R this back and forth between uh     
1:14:59     
models Network or neural network models for example and the brain and and     
1:15:06     
looking at the brain so this is a back and forth It's Not Just In One Direction     
1:15:11     
you can't just say we interested in One Direction you have to consider     
1:15:16     
both uh I'm not sure we're fully at the stage to confident focus on which questions about brains does narrow AI     
1:15:23     
answer what more a prear paradigmatic stage focused on creating common ground     
1:15:29     
in theory and tools and in parallel seeking convergence of structure functional     
1:15:34     
relationships so this is where you know this pre paradigmatic stage is means     
1:15:39     
that you don't have a paradigm uh for Euro AI yet you're sort     
1:15:45     
of you know staking out the sort of idea of what tools are we using what theories     
1:15:51     
are we using and then what are the actual structure function relationships because you know in addition to our uh     
1:15:59     
non understanding of neural network models we also don't really understand the brain very well and vice versa so     
1:16:06     
this is a thing we still need to work out um so that's and then seven we have     
1:16:15     
uh this is the voice Vision BCI is a person who works on uh uh sensory     
1:16:22     
substitution Prosthetics uh I'd wish it would yield insights and     
1:16:28     
approaches that make humans smarter wiser rather than AI smarter but I'm not     
1:16:33     
hopeful uh this person says am may explain interindividual differences and     
1:16:39     
enable personalized brain measures okay that's interesting uh saxs 2019 in pnas     
1:16:46     
shows how artificial neural networks learn similar representations with different neural tuning xxb in 2011 in     
1:16:54     
journal neural shows how a similar principle explains inter individual differences in stimulation of O     
1:17:01     
responses so this is where you know you can actually look at individual differences using artificial neural     
1:17:08     
networks and looking at the representations uh based on you know individual tuning with different uh     
1:17:16     
networks so that's an interesting question um Elis in say hot take     
1:17:23     
computational neuroscience can address data sets harder than mist or deor filters meaning that you know we have a     
1:17:30     
lot of times in uh AI we have these idealized benchmarks and training sets     
1:17:36     
you know can we get away from that and can we get these harder data sets that     
1:17:42     
are less uh I mean one reason we use mnist of course is The Benchmark or algorithm so we use these     
1:17:50     
artificially you know uh easy data sets and of course we do the same thing with     
1:17:56     
uh behavioral experiments or like neuroimaging experiments we use very simple stimul because we want to isolate     
1:18:03     
mechanisms we want to like normalize the data set we don't want people think we want too many things when they look at a     
1:18:10     
bunch of images or do a task so that's that's one reason we do that but of course you know at the same     
1:18:18     
time you know our computational models sort of perform really well on these artificially     
1:18:25     
easy tasks but maybe not on hard tasks so it's like you know we think     
1:18:31     
about like things like continuous Behavior or naturalistic behavior can we do the same thing for     
1:18:37     
computational models uh another Michael scherner says     
1:18:44     
decode visual experiences and high resolution needs great decoder great neural data and experiencing brain that     
1:18:51     
can confirm via verbal report so this is where uh there's I think that people     
1:18:57     
have done some work with this in um like I you know where they look at V1     
1:19:03     
and they can decode the activity of V1 uh I remember seeing this paper where     
1:19:08     
they like played a movie and then they looked at V1 and they used some algorithm to decode the realtime     
1:19:15     
activity of V1 I think they were using like fmri and they were able to actually get some of the patterns of the images     
1:19:21     
of the movie extracted from V1 so that's that's kind of an interesting some     
1:19:27     
interesting work in that direction but the idea is that you can actually take his visual experiences and decode them     
1:19:33     
from the network activity um fana rudenko says we do not know well     
1:19:40     
enough interactions of Senses AI still cannot integrate multisensory processing     
1:19:46     
if at all relevant to machine what is substitution for senses okay so that's     
1:19:52     
uh yeah and then someone else say time so yeah there are a lot of things kind     
1:19:57     
of you know G very general ideas and then questions so uh this is someone I'm     
1:20:04     
just a lay person but this is the central open question I want answered regarding this so this question here uh     
1:20:11     
let us say you can measure the physical state of the brain to an exhaustive degree of precision and detail defining     
1:20:17     
membrane voltages so activity molecular composition Etc in terms of location at     
1:20:22     
a given snapshot and time you predict the next physical state of the brain and the lapse time step by an algorithm that     
1:20:29     
may be implemented on a turn machine which such a system achieving accuracy in predicting preceding physical states     
1:20:37     
of the reference system anywhere from 99% to asymptotic to 100% if not what's     
1:20:45     
the highest achievable accuracy uh it's you know it's kind of an interesting question because I don't     
1:20:52     
think you could do that but but also it's kind of a so they uh kind     
1:20:58     
of kind of make this point here below fnally at neat I heard that people at     
1:21:05     
certain famous lab doing both Ai and neuro don't think neuro has much to help AI with nowadays as for AI influencing     
1:21:12     
neuronormative modeling is useful in um yeah this first question I'm not     
1:21:18     
sure I mean it's it's it's kind of like the idea of emulation of the brain and     
1:21:23     
you know you could have opinions about that I'm kind of a skeptic of that I know that you know an open worm that's     
1:21:29     
kind of one of the well it's not really one of the goals per se I mean we' like to do that but I don't think that that's     
1:21:37     
really an achievable goal even in in se but but I think that's an interesting     
1:21:44     
kind of uh high stakes question um you know so that's that's eight and then     
1:21:51     
nine is says Blake Richards I recently said here that I think we need more     
1:21:57     
connections between Theory and data in Neuroscience we here are two recent papers and you give some links here     
1:22:03     
seeking to win theories of credit assignment to experimental data more like this please so this is where credit     
1:22:09     
assignment where you're trying to find the specific neurons in a network that are responsible for specific outputs and     
1:22:16     
credit assignment is kind of you know one of these questions that people I     
1:22:22     
think pursued for a while and it's kind of hard to know the you know it you know     
1:22:28     
we don't know if like the same neurons do the same thing every time network runs even if it's running the same     
1:22:34     
output so but there are you know people working on these ideas of credit assignment so those I have some papers     
1:22:42     
on this uh that I'll talk about next but basically this is one of the example you     
1:22:48     
know so there are two examples here he links to uh where they're looking at predals so that brings us to some of the     
1:22:55     
papers that people have had linked to in this thread uh the first one being this this     
1:23:03     
is one of the credit assignment papers the bioarchive link uh this is vectorized instructive signals and     
1:23:09     
cortical dend rights they on your brain computer interface task and so they're     
1:23:16     
talking here about back propagation of error which is one of the most widely used learning algorithms in artificial     
1:23:22     
World networks act profit propagation provides a solution to the     
1:23:27     
credit assignment Problem by vectorizing an error signal tailored to individual     
1:23:32     
neurons so again you can look at what different neurons are contributing to the network by vectorizing an error sign     
1:23:40     
and this is of course the credit assignment problem recent theoretical models have suggested that neural     
1:23:46     
circuits could Implement back propagation like learning by semi-independently processing feedforward and feedback information     
1:23:53     
streams in separate dendritic compartments this presents a compelling but untested hypothesis or how cortical     
1:24:01     
circuits Sol credit assignment in the bra so this is where they're using     
1:24:06     
combination of back propagation like learning and this sort of U vectorized     
1:24:13     
error signal um we designed a neuro feedback ECI task with an experiment to find     
1:24:20     
reward function to evaluate the key requirements for dendrites to Implement back propagation like learning     
1:24:27     
we train mice to modulate the activity of two spatially intermingling populations of four or five neurons each     
1:24:34     
so they're actually getting this uh signal from like a small group of     
1:24:39     
neurons and they train mice to modulate this activity uh of layer five per     
1:24:46     
paramal neurons in the Retros spinal cortex to rotate a visual grading towards a Target orientation over     
1:24:53     
recorded activity from Somas and corresponding distal apcal dendroides we     
1:24:59     
observe that the relative magnitudes somatic versus dendritic signals could be predicted using the activity of     
1:25:05     
surrounding Network and contained information about task related variables that conserv as instructive signals     
1:25:12     
including reward ER so they have this sort of almost uh it's not really a uh     
1:25:18     
reinforcement learning model but it's a similar type of thing where they're looking at these signals instructive     
1:25:25     
signals that looking at the contribution of different signals from the Som Soma     
1:25:31     
versus the dendrite and that sort of thing so they're able to like disentangle the signal signals in the     
1:25:37     
network the sign of these perative teaching signals both dependent on the causal role of individual neurons in the     
1:25:43     
task and predicted changes in overall activity over the course of learning these results provide the first     
1:25:49     
biological evidence of a back propagation like solution to the credit assignment     
1:25:55     
problem that's one approach you know where they're kind of combining what we're the lessons we're learning from     
1:26:01     
computational Neuroscience from Ai and then merging that with things in the brain and doing a set of experiments in     
1:26:08     
in a mouse brain and looking at it that way uh this other paper is this other     
1:26:16     
credit assignment paper so this is uh Target learning rather than back     
1:26:21     
propagation explains learning in the Mamon neocortex so in this case you know this is sort of the case against back     
1:26:28     
propagation in neocortex and in learning and talking about this in terms of Target learning which is what they'll     
1:26:35     
Define in the paper here so the abstract reads modern Neuroscience offers two competing     
1:26:42     
hypotheses to explain hierarchical learning in the neocortex so this is where you're learning through sort of     
1:26:49     
going through the layers of neocortex um and so the first one is     
1:26:56     
deep learning inspired approximations of the back propagation algorithm where neurons adjust synapses     
1:27:02     
to minimize the error so this is where you're getting being inspired from Deep learning and you're kind of using back     
1:27:11     
propagation as a way to explain what what you know uh what the brain is doing     
1:27:16     
or the ne cortex is doing layer by layer so this is sort of a hypothesis but     
1:27:21     
you'll notice that in neuroscience you know there's kind of a thin line between hypothesis and theory it's like the     
1:27:28     
hypotheses are informing the theory and people will say it's a theory but it's more kind of like a hypothesis it's kind     
1:27:35     
of a you know the the theory of course maybe as prepared dimatic as we mentioned     
1:27:41     
before so that's the first ideas is this back propagation that's inspired by     
1:27:47     
defa then the second one is Target learning algorithms so in Target learning algorithms we have neurons that     
1:27:53     
learn by reducing ing the feedback needed to achieve a desired activity so this is where you have feedback back     
1:28:00     
propagation isn't truly feedback but you have this feedback uh which is minimized     
1:28:07     
or reduced to achieve to desired activity so if you think about like you     
1:28:14     
know a lot of the inhibition that happens in the brain especially in Neo cortex that's kind of what they're     
1:28:19     
referring to you know you have to inhibit things selectively to get like a design Le activity and so you have to     
1:28:26     
know your Target or the target has to be clear because there has to be this level of control so that's the second and this     
1:28:34     
is sort of an algorithm that you can implement this is more sort of a computational neuroscience     
1:28:41     
thing uh we address this long-standing question by focusing on the relation between synaptic plasticity and somatic     
1:28:48     
activity of uh paramal neurons so this is where we're looking at anat synapses     
1:28:54     
and sematic activity again through single neuron modeling and inv vitro experiments     
1:29:01     
combined with deep learning theory so kind of doing things in modeling single     
1:29:07     
neurons and then doing experiments and then appealing to deep learning theory and this is Largo in terms of     
1:29:14     
back propagation but also some of the target learning stuff as well we predict     
1:29:19     
distinct neuronal Dynamics for each hypothesis so you know know for each of     
1:29:24     
these hypotheses Target learning and uh back propagation we have these different     
1:29:32     
Dynamics so if one is the case we should observe this set of Dynamics if the     
1:29:37     
other is the case we should observe these Dynamics we test these hypotheses on     
1:29:42     
invo data from the mouse visual cortex our findings reveal that cortical     
1:29:47     
learning is more consistent with Target learning highlighting a critical discrepancy between deep learning and     
1:29:53     
the cortical hierarchal learning so this is interesting because in this case what     
1:29:59     
we've done is we've kind of ruled out or severely question the utility of deep     
1:30:05     
learning theory in explaining what's going on in the grd so it's interesting you know we we we had bulaid plans to     
1:30:12     
sort of unify or maybe to to be inspired by Deep learning and turns out not to be     
1:30:18     
the case at least in this case I think that's interesting um so I mean you know     
1:30:24     
neur AI can go cut both ways I guess is the L um this paper is uh neep neural     
1:30:32     
network models of sensory systems Windows onto the ru of test constraints this is another example of sort of     
1:30:38     
neural AI where you're looking at sensory neuroscience and in sensory Neuroscience     
1:30:44     
we want to build models of predict neural responses and perceptual behaviors so we're not building theories     
1:30:50     
per se we're building models conceptual models of what's going on the sensus so     
1:30:56     
you know for decades artificial neural networks trained to perform perceptual tasks have attracted interest as     
1:31:02     
potential models of neural computation so are neural artificial neural networks     
1:31:07     
good models of this sort of sensory uh processing only recently however have     
1:31:14     
such te systems begun to perform at human levels on some real world tasks     
1:31:20     
the recent engineering successes of deep learning have led to renewed interests in Anns as models of the brain here we     
1:31:27     
review applications of deep learning to sensory Neuroscience discussing potential limitations in future     
1:31:33     
directions so they kind of deal with this sort of neuro AI Connection in this     
1:31:39     
in this review We highlight the potential uses of deep neural networks to reveal how Tas performance May     
1:31:46     
constrain neural systems and behavior in particular we consider how     
1:31:52     
task optimized networks and generate hypotheses about neural representations     
1:31:59     
and functional organization in ways that are analogous to traditional ideal Observer models so this is where we talk     
1:32:07     
about these ideal Observer models and this is where you know we control     
1:32:13     
everything and experiment and we see what we can find out so um you know they say here in the     
1:32:21     
paper behavioral predictions from ideal Observer model they also provide normative explanations     
1:32:27     
of otherwise puzzling perceptual phenomena for instance by showing how Illusions can be viewed as optimal     
1:32:33     
inferences given the statistics of the natural world so this is kind of a good     
1:32:39     
paper on how relevant uh artificial neural networks     
1:32:44     
and deep lurine are to sensory systems this is another paper this is by     
1:32:52     
Ken Wisher at all and this is using artificial neural networks to ask why     
1:32:57     
questions of minds and brains so now we're at not asking what but why and so     
1:33:03     
in this paper you know there's this kind of this is another one of these review articles where they're speculating about     
1:33:09     
how you know useful what's the utility of these kind of artificial neeral     
1:33:15     
networks so you know we're kind of in in the previous examples we're asking how     
1:33:21     
in this question we're asking why but the question why brains work the way they do is asked less often the new     
1:33:28     
ability to optimize artificial neural networks prefer for performance on human-like tasks now enables us to     
1:33:35     
approach these why questions by asking when the properties of networks optimize for a given task mirror the behavioral     
1:33:42     
and N neural characteristics of humans performing the same task here we highlight the recent successes of the     
1:33:49     
strategy and explaining why the visual and auditory systems work the way they do both of Behavioral and Ne levels so     
1:33:56     
there's this idea why but also being able to answer questions at different     
1:34:02     
levels of analysis behavioral levels and neural levels so you can look inside of a network and say how does the network     
1:34:09     
wired what is the sort of the credit assignment of different neurons of different synapses but you can also ask     
1:34:16     
questions of how is this information processed but then you can also look at the outputs and say this is the behavior     
1:34:23     
that we expect if we generate a behavior using an artificial moral network does it     
1:34:29     
match what we see in an animal model and so that's kind of where this paper goes it's just reviewing this the     
1:34:36     
different types of work that's going on in this area but I think the idea is that you know it's going to be able to     
1:34:43     
allow us to ask these y questions and of course among the next goals for research     
1:34:48     
in this area would be to discover the underlying principles that explain why each optim Iz artificial neural network     
1:34:55     
produces the particular humanlike phenomena it generates or the Y of Y so     
1:35:01     
it's like you can ask symatic questions eventually so this is an interesting     
1:35:07     
take on this this paper from nature is uh context dependent computation by     
1:35:13     
recurrent Dynamics and prefrontal cortex this again is kind of talking     
1:35:19     
about um you know these computational models and prontal     
1:35:24     
cortex and you know kind of understanding it so prefrontal cortex is thought to have a fundamental role in     
1:35:31     
flexible content dependent Behavior but the exact nature of the computations underlying this role remains largely     
1:35:37     
unknown in particular individual prefrontal neurons often generate remarkably complex responses that defy     
1:35:45     
deep understanding their contribution to behavior so they look at prefrontal cortex activity and maak monkeys trained     
1:35:53     
to flexibly selected integrate noisy sensory inputs it's a choice and then we find that the     
1:35:59     
observed complexity and functional rules of single neurons are readily understood in the framework of a dynamical process     
1:36:06     
unfolding at the bottom of a population these population Dynamics can be reproduced by training recurrent neural     
1:36:12     
networks so you can use recurrent neural networks to reproduce these population     
1:36:18     
dynamics of the of the neurons in in the cxs and so we can actually you know have     
1:36:24     
like this sort of these concurrent models of like a phenomenological model     
1:36:29     
what's going on inac cortex and in the recurrent neural     
1:36:35     
network we don't I mean we kind of care about the behavior but we can actually get the population Dynamics to replicate     
1:36:42     
which suggests a previously unknown mechanism for selection and integration of task R and inputs so we're actually     
1:36:50     
identifying mechanism at the network level this mechanism indicates it     
1:36:55     
selection and integration are two aspects of a single dynamical process     
1:37:00     
unfolding within the same prefrontal circuits potentially we provide a novel General framework for understanding     
1:37:07     
context dependent computations so that's an interesting PA it's chrishna shoi David Zio Valeria     
1:37:14     
Monte and William new so that's that's another example of narrow Ai and so     
1:37:20     
that's that's uh I think that was a good overview of sort of the questions in their oi some of examples of research in     
1:37:27     
their oi and how we might go forward with this     
1:37:42     
Enterprise certainly the the overheard in neat Labs or neat lab     
1:37:50     
you know like I've definitely heard before     
1:37:56     
and just thinking back to that Kur fuffle between Conrad cording and David     
1:38:04     
fall um on Twitter that was that was pretty brutal     
1:38:10     
but that's when they had     
1:38:15     
that position paper I think it would be the best way of putting     
1:38:21     
itous pseudo science or something no no no no like like the     
1:38:26     
towards towards a neuro AI oh okay you     
1:38:33     
know cording was definitely on     
1:38:39     
it um I it was like Tony Zer yes okay first     
1:38:47     
author but but like I don't know if they were just doing reverse alphabetical     
1:38:54     
like you know it it was a bunch of people right but it was it was getting at this this that     
1:39:01     
that yeah like does does neuro have have anything to contribute to to     
1:39:11     
to yeah I if if artificial neural networks are truly     
1:39:19     
neuro inspired which I think is question very very     
1:39:26     
questionable like you know     
1:39:32     
um then then should yeah modern     
1:39:39     
neuro have have something to and and I think David     
1:39:44     
FS I I don't know how you pronounce his name it's p PF Au how do you say     
1:39:51     
that far I guess I don't know fall I I yeah I I need to hear it but like you     
1:39:57     
know certainly the big thing being like     
1:40:02     
um you know he was just like oh come on you guys you know you're     
1:40:08     
neuroscientist you you know you're trying to be AI relevant right you know so you just     
1:40:17     
you're just slapping you're just slapping Neuroscience you know together     
1:40:22     
with AI and and and I forget what kind of rude thing     
1:40:29     
he said afterwards but was just like you know something like all the all the real work in AI is     
1:40:38     
is you know we're doing a deep mind oh     
1:40:44     
wow and I was just like you you mean reusing you know like like 70 80 year     
1:40:52     
old reinforcement learning     
1:40:57     
yeah don't think that's the argument you think it is yeah     
1:41:03     
uh you know but now it's deep you know deep RL     
1:41:09     
right um     
1:41:17     
and yeah I mean so like interesting like it would be you know I'd like to see     
1:41:24     
what like Nancy CER was was trying to get out with the why or the kind of yeah     
1:41:30     
the meta you know um the the problem being you know as as so many people have     
1:41:37     
shown that that like neural networks are you know another way of seeing them as     
1:41:42     
just as an optimization tool right right yeah it's you know a remark potentially     
1:41:50     
remarkably efficient one um     
1:41:59     
so yeah I mean I I I liked I liked     
1:42:05     
the the zurk I think it was zth zurk     
1:42:10     
um um but but the paper that was getting at I think     
1:42:17     
um Target um what do they call it Target learning T Target learning versus um     
1:42:24     
deep learning or back back back right yeah     
1:42:30     
back you know like like that there's an example where it's just like hey you     
1:42:37     
know I mean that that's what you want to see right is just like I I could use these two different models to explain     
1:42:44     
kind of neural cortical neural data and and you know using a a     
1:42:54     
using a model comparison technique you know or     
1:43:03     
or base factors or some something like that the the the evidence um is     
1:43:12     
is behind the um Target     
1:43:21     
Ley and and I yeah like like like the the problem I     
1:43:27     
have or you know the question I have for the caner paper is like there's not enough of that first example there's not     
1:43:34     
enough Target learning versus backr yeah yeah to to get at like     
1:43:41     
like what I would say we're trying to do at science in the sense that like we're     
1:43:46     
we're trying to find like what that the the kind of the principle of     
1:43:53     
those neural networks right yeah that that actually underly these     
1:43:59     
systems as opposed to just you know fit fitting the data yeah     
1:44:06     
which which you know like again it's like if you're only using one model then then it will fit the DAT you     
1:44:14     
know it will fit the data but yeah but that um yeah anyway and this again was     
1:44:22     
certainly what I love about Dynamic causal modeling in Nur Imaging you know the area I know better     
1:44:32     
um where you're you're actually doing comparisons between different basal     
1:44:39     
temporal models you know I I see it as this bigger framework where you're actually     
1:44:45     
think doing modelbased uh analysis and then comparison across models which you know     
1:44:53     
I guess partly partly it seems so revolutionary just because it's like before that we never did     
1:45:02     
yeah you know so that's why yeah I still say everybody should use SPM for     
1:45:09     
analysis of EEG meeg data because it has that functionality which just doesn't     
1:45:15     
exist anywhere yeah um so that that's pretty cool um     
1:45:24     
and yeah and then like certainly you know if you look in the neuromorphic     
1:45:30     
Computing and organoid intelligence papers all the I think like the first     
1:45:37     
topic you covered was the the efficiencies of     
1:45:44     
of the people who care about the the the efficiencies of     
1:45:50     
neural um biological neural networks     
1:45:56     
over you know gpus and and     
1:46:01     
how energy intensive all of our back propop algorithms are and     
1:46:11     
that yeah I mean this is this is definitely the the the Organo     
1:46:17     
intelligence papers if if if if we've got a problem with them it's that they     
1:46:22     
over emphasize the the the potential benefits in terms of power oh yeah they     
1:46:29     
do they do these these big you know these these tables of like look how much     
1:46:36     
more power efficient biology is and it's just like yes but we but we have zero ability to pass data     
1:46:45     
to these biological systems so it is like yeah it's a     
1:46:54     
aspirational yeah at best and you know certainly all     
1:47:02     
examples are like we do things slower and less     
1:47:10     
efficiently than computers yeah great computers I yeah I haven't really seen a     
1:47:16     
really good like energetics paper like where you actually ask the question like     
1:47:22     
so we do things maybe with less energy requirements I guess but like what are     
1:47:28     
we doing that's like slower what are we doing that's like why is there that disparity the questions yeah yeah yeah     
1:47:35     
then you can frame the question you do see it you do see I mean that's what I say like if you look in     
1:47:41     
the neuromorphic Computing world and and the     
1:47:49     
um kind of run a little Facebook group I shouldn't I I don't I don't even know     
1:47:55     
why we started it as a Facebook group but anyway post post all the     
1:48:00     
neuromorphic Computing stuff there I should you know like the good thing is it's got a history I just take that and     
1:48:05     
dump it but but um all the neuromorphic Computing people are the papers     
1:48:13     
currently you know are real examples of of more efficient actual chip     
1:48:20     
architectures right where where tables make sense right     
1:48:25     
right and and they're mostly using these spiking models spiking neural networks     
1:48:32     
as as yeah and algorithms tailored to spiking     
1:48:39     
neural network learning problems or or adaptive     
1:48:44     
Control Systems you know Etc right and and they they have a real um     
1:48:53     
they have an actual power efficiency that that you know like a and     
1:48:59     
a working one in the sense again like like these are not only you know big     
1:49:05     
science projects where they're these kind of compute clusters in in um     
1:49:12     
idleberg like heidleberg Manchester and and now the new ones down in Australia yeah um I     
1:49:20     
think Australia is like the biggest and it's the newest biggest right and     
1:49:28     
where you've got like all this Hardware dedicated for spiking girl Network     
1:49:33     
compute and um and it's it's you know it's definitely our     
1:49:40     
efficient um but it's like very limited in terms     
1:49:47     
of like like that's the expansion you know like like like     
1:49:54     
yeah and I bet I bet physicists well so I put a link um in the the the jitsy chat to     
1:50:05     
that um uh the series of talks that related     
1:50:12     
to I I would say were great uh I think you know the guy down at UCLA who put     
1:50:18     
this together but it was like a set of talks that was definitely covering kind of like Michael 11     
1:50:28     
multiscale oh team the issues as well as like like     
1:50:35     
some good biological learning some some really good biological learning stuff     
1:50:41     
too um uh let me     
1:50:46     
um let me just uh remember what that hey anyway I just     
1:50:55     
[Music]     
1:51:04     
I think you     
1:51:09     
just forget now what the sorry it it it's     
1:51:17     
um um     
1:51:29     
well you know it's got It's got some people that You' expect Like     
1:51:38     
Richard so and um and obviously Michael lean and     
1:51:43     
some some some new ones just in terms of you know like like talking about     
1:51:52     
yeah like tame kind of stuff or diverse intelligence     
1:51:59     
or and what what I wanted     
1:52:06     
to what I was kind of trying to um remember see if anything was relevant     
1:52:11     
was like is there another way to see spiking neural     
1:52:16     
networks as um you know as kind of a non neuronal     
1:52:23     
process in this you know like like is there another physical     
1:52:29     
metaphor for what spiking neural networks represent right yeah because     
1:52:35     
again like the math is so abstracted from from neurons right yeah     
1:52:41     
um that that yeah just how how much does this     
1:52:47     
actually um     
1:52:54     
represent um neuro AI so then sorry and I've been     
1:53:01     
talking for a long time the um the the the lay     
1:53:08     
person who who asked about you know like     
1:53:14     
can can we can we get a whole lot of biological detail and then predict what     
1:53:21     
happens at the next time step and it's just like like to a certain degree it's just like you know H how much is neuro     
1:53:30     
AI involve all the physical embodiment of     
1:53:36     
the neurons right like like you know like like neuron as the     
1:53:43     
the C++ package right with its cable     
1:53:48     
equations and and you know the um     
1:53:54     
that that's uh I forget the neuromorphology packet but you know like     
1:54:00     
like you know there's lots of people cataloging all the different cell     
1:54:05     
architectures and geometries so that you can actually make these physical models of all the kind of     
1:54:13     
brain cellular heterogen     
1:54:19     
yeah but to to to a certain extent like like you know is is that is is that     
1:54:27     
Nur yeah right like like is it yeah like you see what I mean     
1:54:35     
like how much do we need the the details of that biological embodiment um and and are we even you     
1:54:45     
know and are we actually capturing that with this kind of geometrical structure     
1:54:52     
you know this physical geometric structure or is it     
1:54:59     
something you know is it something else yeah yeah like I mentioned with respect     
1:55:05     
to open worm so I mean you know we can simulate every neuron you know do that but like the question is is there's a     
1:55:12     
lot of heterogenity there's a lot of stochasticity if even if we do simulate it and put those things take those     
1:55:18     
things into account how much how useful is that resulting Behavior I mean it may     
1:55:24     
match kind of like what you might see in a sea elegans but like you know is it     
1:55:29     
the same thing or you how you I guess it's useful to some extent it isn't     
1:55:35     
necessarily right yeah but it might be useful you know certainly like like this     
1:55:41     
is the this is the interesting thing in the in the kind of physics of     
1:55:47     
Life uh perspective right right where it's just like     
1:55:52     
is it [Music] interesting to the point or is it     
1:55:58     
interesting because of that systems ability to to reach a a kind of     
1:56:08     
complexity boundary that that allows for     
1:56:14     
um you know allows for criticality and and other you know     
1:56:22     
phase change emergence right um chaos Etc right     
1:56:31     
yeah like     
1:56:39     
yeah but yeah yeah I think that's good is is is     
1:56:46     
it coming yeah is it coming from that kind of network perspective science you know or     
1:56:54     
or or is it like like the weather where it's just like the there's actually input to the system     
1:57:02     
that we don't understand and aren't measuring properly right right right where I forget what they call it but you     
1:57:09     
know it's it's relates to kind of cloud solar interaction yeah that     
1:57:18     
that is this yeah yeah there's this concept     
1:57:24     
itinerant in okay complex systems theory it's basically where you have you know     
1:57:31     
depending on the initial condition things change so every time there's an input it changes the output and so it's     
1:57:38     
very kind of hard to predict in that way so the Dynamics are harder to predict than the actual mechanisms in     
1:57:44     
reproducing those but yeah I mean you know there yeah there so there are a lot of     
1:57:50     
questions I I you know maybe we should follow up on this I'd like to actually write some sort of nuro AI position     
1:57:56     
paper you know it's I don't want to be a bomb thrower but at the same time I'd like to be uh I think we should take this and     
1:58:04     
and kind of give our little point of view on that because I think we could have some really interesting things to     
1:58:10     
say about it well I mean I I gotta say at this point     
1:58:20     
I'm well no I'm not I was about to say I'm with foul or Foe or     
1:58:25     
whatever no because he was kind of rude but     
1:58:34     
um well yeah that it's Le Len's points or you know the the the the maybe the     
1:58:40     
references that Levan draws on about diverse intelligence where it's just and     
1:58:45     
and Richard Watson right right where where you see you see evolution is a     
1:58:52     
learning process right     
1:59:00     
and de deemphasize the neuro yeah right as as like the neuro is     
1:59:09     
a specific where you start to see that the     
1:59:14     
neuro is this specialized body that you know it's definitely has     
1:59:26     
um yeah just but that is that is built on on so many similar you     
1:59:33     
know um I mean like like what's what's you     
1:59:39     
know I'm always interested like in how Levan uses words because it's it's you     
1:59:46     
can you can think about them for a long time but you know the multiscale competency     
1:59:54     
right which just sounds I like you know it's just it's Pro problem it's problem     
2:00:01     
solving all the way down yeah you know like the turtles you know yeah yeah     
2:00:07     
Turtles all the way down yeah you know and     
2:00:13     
um and and that UCLA     
2:00:18     
life meting had a lot of that you know other non- neuronal     
2:00:27     
systems solving soling problems yeah so yeah     
2:00:35     
it's interesting that uh neuro is sort of an outcome of evolution and you go back to the can Wisher paper she like in     
2:00:42     
the introduction she talks about why being like maybe like an evolutionary     
2:00:48     
question so like you know it's like okay the how is like the mechanism the neural     
2:00:53     
mechanism of the why is you know why did it evolve or why did it why is it there     
2:00:59     
it's like the 10 virgins for questions why is something there in development why is something there in evolution so I     
2:01:06     
think that's kind of the link there that is you know maybe we're not there yet but we we can ask that of neural systems     
2:01:13     
of course yeah so I mean I you know I I think that's actually yeah yeah that's     
2:01:21     
that's a okay that that that     
2:01:27     
I now I kind of see it as as the why the the why question is like why why did     
2:01:36     
this neural structure which is built on all the same things     
2:01:43     
develop     
2:01:48     
um you know it certainly makes it of that Roman Brett paper     
2:01:57     
or yeah you know     
2:02:07     
is maybe some things that Richard sley talks about in a couple of his you know     
2:02:13     
evolving brains papers just in ter like like you     
2:02:19     
know is is neural system a way to kind of develop     
2:02:25     
interneurons oh yeah you know it's just like like we get we get sensory you know     
2:02:32     
and certainly like like you can see sensory as a single cell thing right     
2:02:41     
right um and we can get we we understand movement and we we can understand you     
2:02:49     
know again single cell things that are movement yeah and then like like brains are for     
2:02:55     
all for the interneurons yeah yeah I mean you know it's it's I I     
2:03:07     
I I dropped people off at the airport yesterday and and I was I for some     
2:03:14     
reason you know Richard Sol is um I think his is this CLA Life     
2:03:23     
Sciences talk was for some reason in my     
2:03:30     
feed so that that was in my head but yeah yeah good good set of talks though     
2:03:36     
I mean you know again they they disappear down the slack memory hole Yeah Yeah but like like that meeting you     
2:03:44     
know such a diverse set of of speakers but just but when you see them all     
2:03:51     
together you see you see all these connections between them you know right     
2:03:56     
so let's let's finish up with uh something that paa posted in in the     
2:04:02     
slack she's been missing all summer she's been doing some tasks and research     
2:04:07     
she's going to join us again soon but she wanted to send out some stuff that     
2:04:12     
she had she was thinking about so she uh sent out some resources on uh sick and     
2:04:19     
douglin at so dougl ad of course developed this uh sick platform which is     
2:04:26     
uh sort of a hypothesis generation Tool uh you know it's a a form of AI where     
2:04:32     
you're uh you know developing hypothesis and and so forth so this is a he I think     
2:04:39     
he passed recently so this was a a talk on online here Doug lanat sick and     
2:04:45     
future directions of reasoning and knowledge representation this was a talk from triple ai24     
2:04:51     
she also posted this paper on the nature of     
2:04:56     
hertica social intelligence journal in 1982 so this is a classic paper this is     
2:05:04     
Douglas Lanette um the nature of her istics so you know kind of this was sort     
2:05:10     
of early sick days so he developed this into the sick     
2:05:17     
platform um the abstract reads uh Builders of expert rule-based systems     
2:05:22     
attribute the impressive performance of their programs the Corpus of knowledge they embody so you know we're dealing     
2:05:29     
with rle based AI knowledge systems and so forth so it's very different from the     
2:05:35     
neural network um model that we were just talking about with nuro     
2:05:40     
AI uh so the you know the idea of expert rule systems is that there's a large     
2:05:46     
network of facts so you have all these facts that can you know you can find connections between between them to     
2:05:52     
provide breadth of scope and a large array of informal judgment rules or judgmental rules or heris sixs which     
2:05:59     
guide the system towards plausible paths to follow and away from implausible ones so you're using these rules that sort of     
2:06:06     
are decisions or decision making tools they're not you know going to give you     
2:06:13     
the absolutely best answer but they're sort of the good enough answer so heris are like good enough decisions you make     
2:06:21     
it you puristic judgment a lot of times in decision making where you just have     
2:06:26     
to make a good enough judgment and it should lead you in the right direction so this is the sort of the idea behind     
2:06:33     
what we're doing in sick um yeah what is the nature of her istics so there's a     
2:06:38     
whole literature and cognitive science on heris and heris decision making and     
2:06:43     
then they used theistic in a lot of the rule-based AI um and kind of giving this     
2:06:50     
good enough answer what is the nature of fistic what is the source of their power it's kind of an     
2:06:57     
odd question but how do they originate and evolve and I guess in this case you know how do they originate maybe in a     
2:07:04     
biological system or how do you develop a heris and how do they evolve as you     
2:07:09     
get more information so there's this kind of weird neuro AI question here     
2:07:14     
which is like if we assume that hero stics are a biological property of brains whether it be like in human     
2:07:21     
decision making or in like making as an animal making decisions about where to find food what are you know what are     
2:07:27     
these heris stics how do they originate how do they evolve how do you know this stuff some people would argue maybe in     
2:07:34     
animals it might be a Nate you know the abil the the uh urges to find food or     
2:07:40     
the the sort of the behaviors that you would use to do things like that are     
2:07:45     
innate and then how do they maybe evolve either like behaviorally or evolutionarily     
2:07:52     
that's an interesting set of questions anyways by examining two case studies the am and Uris programs we are led to     
2:08:00     
some tentative hypotheses and those hypotheses the first one is heuristics are compiled     
2:08:07     
hindsight and draw their power from the various kinds of regularity and continuity of the worldall so if You     
2:08:13     
observe regularity and continuity you assume that that sort of gives you that good enough answer so in other words     
2:08:20     
it's like the um explore exploit tradeoff so if you find like always find     
2:08:27     
food in a certain location you keep going back to that certain location and exploit and if you stop finding food     
2:08:35     
there then you have to go back and you have to explore for new sites of food so if you have this regularity and     
2:08:41     
continuity you have this heris of exploit and so that's one one way that     
2:08:47     
you might you know it's compiled hindsight it's experience they arise through specialization     
2:08:54     
generalization and surprisingly often analogy so again you know you have if     
2:08:59     
you specialize in something if you know a domain really well you develop a uh     
2:09:04     
sort of an intuition for your horis sixs generalization means that if you generalize from some examples you can     
2:09:11     
draw sort of Rules from that or heris sixs again they don't cover every case but they're good enough to get you you     
2:09:19     
know where you need to go and then analogy meaning that if you look at one thing you transfer that knowledge to     
2:09:26     
another thing and you use theistic of that they basically work the same so     
2:09:32     
that's those are the ideas of heuristics that you have these three ways that they arise but they also arise through     
2:09:37     
compiled hindsight and generally he's he's focused on the learning aspects of     
2:09:42     
heris but we could have heris that are innate we could have theistic that are     
2:09:48     
sort of taught and evolve both culturally and um their     
2:09:55     
experience 40 years ago POA who was known for Po's ear and statistics     
2:10:01     
sampling with replacement and leading us to consider a the field of Heretics the study of     
2:10:07     
informal judgmental rules of thumb which underly such     
2:10:12     
programs okay so then you know the htics asks what is the source of power of     
2:10:19     
heuristics so heris of course is this these good enough judgments tics asks     
2:10:26     
what is the source of power of htics so this means that you know sort     
2:10:32     
of how do new heris originate and how do we how do they come about so that's the     
2:10:38     
difference between heroics and heris and so this is a nice paper kind of goes through a lot of this and there maybe     
2:10:45     
some narrow AI um relationships here there's also a lot of theory building in     
2:10:51     
this and a lot of like considering sort of this idea of     
2:10:57     
heuristics in an interesting way I always remember wondering what the out     
2:11:03     
of Sol it book on my parents shelf was what what that was about oh I have that     
2:11:08     
book when I was a kid yeah yeah um     
2:11:16     
but yeah like whether whether Heretics is a     
2:11:22     
it own discipline is interesting interesting question oh     
2:11:31     
yeah yeah that's an old that's an old paper yeah yeah it's uh it's kind of a     
2:11:40     
classic going yeah I mean it's definitely going back to kind of like that that period of time expert systems     
2:11:48     
kind period of time but um it's funny though because it the     
2:11:55     
other thing I put in there is the um in the chat is the um this new future house     
2:12:03     
paper okay it's it's funny thinking about Heretics just     
2:12:09     
because um this is this is their attempt to make     
2:12:16     
a you know large language model into a scientific discovery     
2:12:22     
system oh right so anyway what what future house     
2:12:31     
is looking for is is is is you know making making a science out of tics yeah     
2:12:39     
okay you know right I mean what they need to do     
2:12:45     
is to to exploit tics that work right yeah     
2:12:52     
um like without like if if you knew the answer     
2:12:57     
then you would do the the best thing but since we don't yeah we need we need to     
2:13:04     
find yeah we need to find approximations that that get us get us     
2:13:09     
somewhere any so this is the Superhuman performance idea here this is certainly     
2:13:16     
you know like like I don't know how well they've achieved it I I I dropped a     
2:13:21     
you know a tweet into Data ml that that     
2:13:26     
certainly gives some of the future house person's you know little little     
2:13:35     
summary um you know I mean I'm I'm certainly interested like you know like um Demi um     
2:13:46     
ASB talks about like you know this is this is the dream right the that somehow     
2:13:52     
all of this will will create a system that augments us so     
2:13:58     
that we're all better at doing whatever it is we're doing     
2:14:03     
yeah and and the the the circle will     
2:14:09     
continue to tighten and and you know I'm not going     
2:14:15     
to say the singularity will be achieved but like we'll we'll we'll start accelerating towards better and better     
2:14:22     
you know progress and Discovery I like that thought     
2:14:32     
yeah all right well yeah thank you for uh all the good conversations and     
2:14:38     
attending today and uh see you next week than take care take care bye bye
