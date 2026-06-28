## Meeting Recording

[YouTube link](https://youtu.be/oXmxB9DBmqk)

## Mastodon thread

[link](https://neuromatch.social/@OREL/116829214193127965)

## Feature Videos

[JoPro and Cognition Futures update](https://youtu.be/nyzJYTbuCLI)

[Moving Agents, Game Theory, and Applications to Multiagent Simulations](https://youtu.be/i6C9u2FgqeI)

[Horse kicks and the origin of Poisson process](https://youtu.be/EQa5H6K1bT8)

## NOTES
Kavya — next week, focus on Developmental AI.

DigiNest — lots of interesting opportunities for collaboration.

Epstein’s books on NetLogo — language is very 1970s. 

model insurgencies, segregation — how quickly do collaborative social behaviors turn?

bringing time-series to a lattice model. Poisson process: more sophisticated.

Center some points in “Structure of Goals and Experience”.

cohort meetings —> forming clusters.

policy (major Ai labs), 2) agent characteristics/internal — CogSci (Moral AI), 3) multi-agent communities (user encounter).

Intra-Inter-Agent domains. Frameworks —> anchor. Some general pathway of GSoC —> Data x Direction. 

Violet: CogSci background. 

DigiNest —> Avery, Jes, Molly. Less structured than a seminar series.

where do goals come from? Avery’s viewpoint. Ontology —> RL as a descriptive layout, reward structure.

what if it’s co-developed, hierarchical?

Telic States ~ Affordances. Environmental opportunity.

Yohan John — do not see differences, see with differences.

Objective/Goal — situating goal/end-state. Continually-informed.

Internal/Intrinsic —> volitional allotment (enactive).

juries that falsely convict — Poisson process.

origin of Poisson process. Common currency of navigation. Law of small numbers.


Autotelic agents — can set their own goals.

selection from alternatives. Goal —> perception of an alternative. Goal generation, affordances constrain.

Prisoner’s Dilemma (PD) — are all Prisoner’s the same? Power dynamics, nonuniformity is conceptionof the reward.

in concept of the reward.


Horse Kicks —> Geiger counter,

Stanford person —> Agent-based model as Ising model.

multiple chemical processes, more Sociological.

Levin paper —> using Ising models. Lean proofs, scaffolds. 

* “The Unreasonable Effectiveness of Statistical Mechanics”. Wht would Jaynes do? Maxent. dev-Neuro-AI. Growing olfactory neurons for bomb detection.


Poisson process: is attributed to Poisson. First used to quantify and predict the number of horse kick fatalities in the Prussian military.

## TRANSCRIPT
0:3030 secondsHello. Hi. How are you? Fine. I'm great.     
0:3838 secondsGood. Yeah, I enjoyed your uh paper yesterday that you had.     
0:4444 secondsOh, great. Actually, I could not get time to read that much the whole paper.     
0:5050 secondsYeah, I just went through the abstract and some of the overview of what it's trying to do like the other states.     
1:011 minute, 1 secondYeah.     
1:031 minute, 3 secondsWell, that's good. Yeah. Well, we should follow up on it. I don't know. Well, I'll look it over and see what they're     
1:101 minute, 10 secondsdoing. And actually, this week and the last week I was uh busy, so I could not focus on     
1:191 minute, 19 secondsthis much. Yeah. But yeah, I think till next next week I would try to focus on it and I mean get something done and somewhere.     
1:291 minute, 29 secondsAll right, it sounds good.     
1:331 minute, 33 secondsSo we had 40 meetings this week um for did we have four or three? I guess we had four or three.     
1:441 minute, 44 secondsOkay, so we had three meetings this week. Um the first one was on Monday. Um that was D.Aworm     
1:511 minute, 51 secondsand uh this is our group here and we started in uh Barian gave a little bit of an update on what he was     
1:591 minute, 59 secondsdoing. Um he issued some poll requests this week for his work. So he was uh doing what he call called a smoke test     
2:072 minutes, 7 secondswhich is something you do in software development life cycle to test to see if some something like a model will run if     
2:152 minutes, 15 secondsyou when you scale it up. and he was doing some of that and and pushing uh things associated with that. So he     
2:242 minutes, 24 secondstalked a little bit about that. Then I uh presented a paper here on um this was     
2:322 minutes, 32 secondson community detection in C elegance connetos.     
2:372 minutes, 37 secondsAnd so this was uh talking about using this uh method called community detection     
2:442 minutes, 44 secondswhich is a method where you look at a network and you try to find its communities.     
2:502 minutes, 50 secondsAnd communities in a network are parts of the network that are densely connected but uh sparsely connected with every other part of the network.     
3:003 minutesAnd so that might seem like it's kind of an easy task, but it's actually not because you have to search every con set     
3:083 minutes, 8 secondsof connections to see what the strength of that connection is and then say what     
3:143 minutes, 14 secondsgroup is sort of self-contained in that sense. And so this paper talks about     
3:213 minutes, 21 secondsthis in C elegance conneto for the laral worm. So the laral worm of course is after the embryo hatches and you have     
3:303 minutes, 30 secondsthis juvenile that goes through four different stages L1 through L4.     
3:373 minutes, 37 secondsAnd when it's in those stages, the conneto is actually quite plastic. So it's changing its its synaptic connectivity quite a bit.     
3:463 minutes, 46 secondsSo we look through this paper and um they kind of talk about how community detection works and how they used it in     
3:543 minutes, 54 secondsthis case. So they were using it to actually um manipulate different circuits. So they wanted to see what     
4:024 minutes, 2 secondshappens if you drop out certain connections from circuits, what they'll do. And so the reason they did that is     
4:104 minutes, 10 secondsbecause they looked across different lural stages and found that there were different um different circuit     
4:174 minutes, 17 secondsconfigurations for different stages of development. So for the adult we know what the circuit should look like. We know what the community should look     
4:264 minutes, 26 secondslike. We go back into the uh laral data and we see that there changes in that connectivity that are very interesting.     
4:364 minutes, 36 secondsSo they use this uh method called big clam which is a community detection algorithm uh tailored for weighted and     
4:434 minutes, 43 secondsdirected networks that explicitly capture overlapping modules. So they're looking at um you know circuits like the movement circuit or something like that.     
4:544 minutes, 54 secondsSo it's a series of neurons that are connected but they're also overlapping with other modules. And so when there     
5:005 minutesare changes in one module, they're going to be maybe corresponding changes in another module. So this is um this is     
5:105 minutes, 10 secondsthe paper presented on this um and they talk about their data set that     
5:175 minutes, 17 secondsthey use. They talk about how weak ties theory is important here because     
5:245 minutes, 24 secondsyou you have usually when you have a network that's sort of new, you have a network that's connected sort of     
5:325 minutes, 32 secondsrandomly. Maybe it has some uh sort of scale-free connectedness and then you start to get these weak ties.     
5:425 minutes, 42 secondsAnd the weak ties are important because they tie together two or more uh groups or modules. And so this is sort of the     
5:515 minutes, 51 secondsorigin of communities and networks is you look for these weak ties and you look for the strong ties and you see where the weak ties are joining together     
6:016 minutes, 1 secondgroups of strong ties and you denote that as your network boundary.     
6:066 minutes, 6 secondsUh weak ties goes back into social network theory. So Granavar in 1973     
6:126 minutes, 12 secondsdeveloped this uh this term to describe social networks in which you have people who are kind of connectors between two     
6:216 minutes, 21 secondsgroups. So if you have like um uh one you know you might be involved in this group and you might be involved in     
6:286 minutes, 28 secondsanother group outside of this lab and you are the weak connector there because you're connecting people from both     
6:356 minutes, 35 secondsgroups. So that's and then this this holds true for the conneto as well.     
6:436 minutes, 43 secondsAnd so there are some graphs in here where they show uh neural circuits in terms of how you have these modules and     
6:526 minutes, 52 secondsthey're basically connectivity matrices and you have overlapping connectivity matrices which represent these weak ties     
7:007 minutesand they can be of different constitutions um in terms of connectivity different regimes of connectivity.     
7:087 minutes, 8 secondsThen they get down to these circuits. So these are the circuits where I can't remember what circuit this is. Um     
7:177 minutes, 17 secondsthis is the circuit for uh the it's fngio regulation. So this is     
7:267 minutes, 26 secondsuh they have this thing called the ferinx that pumps and it regulates the     
7:327 minutes, 32 secondsintake of uh food. And so the fingial regulation is controlled by these     
7:397 minutes, 39 secondsneurons. And the take-home message here is that they change their connectivity over uh larval development. So you start     
7:487 minutes, 48 secondswith all of your all of your neurons sort of labeled here, but not all of them are directly connected to this uh network at first or this subnet network.     
8:008 minutesAnd so the connectivity sort of increases and changes across laral development culminating in an adult     
8:088 minutes, 8 secondsuh community which is here and you have stronger connections and weaker connections but they're all connected by     
8:168 minutes, 16 secondsthe time they become adults. And they made a point in the paper that they're different types of neurons that get     
8:228 minutes, 22 secondsconnected first and then later. So in the fangial pumping community you have sensory neurons and motor neurons     
8:318 minutes, 31 secondsconnected and then by L1 you start to get inter neurons connected into this     
8:398 minutes, 39 secondswhich then contributes to you know different behaviors that we see in laral development but also goes back to that     
8:488 minutes, 48 secondssynaptic data set from woodfleet that we've been working on in this group where basically Um, you know, there's a     
8:558 minutes, 55 secondslot of different types of synaptic plasticity in laral development. So,     
9:019 minutes, 1 secondgoing from transient plasticity to sort of pattern plasticity and what roles     
9:089 minutes, 8 secondsthose might play in behavior and they give a number of different circuits. So, this one is oxygen related     
9:179 minutes, 17 secondsegg laying and you see very different patterns here. So it's very interesting to see some of these networks     
9:249 minutes, 24 secondsum and you know how they kind of get played out in laral development. It's a very nice paper.     
9:359 minutes, 35 secondsIt's actually something I wish we had have written uh but we didn't. But we did have another paper that came out this week um and I talked about it in     
9:449 minutes, 44 secondsthe open source meeting and I'll get to that in a minute.     
9:489 minutes, 48 secondsSo this is a paper on um mapping okay mapping morphogenesis and mechanics and embryo models. So this is sort of a     
9:579 minutes, 57 secondsoverview paper of looking at morphogenesis and mechanics and some of the methods they use to look at that in     
10:0510 minutes, 5 secondsembryos and embryo models. And so they're talking about um embryos, but they're also talking about um organoids     
10:1310 minutes, 13 secondshere too. So they were kind of going in between and talking about some of the mechanisms that sort of contribute to     
10:2010 minutes, 20 secondspattern formation in these different types of systems. So they talk about gastroloids     
10:2810 minutes, 28 secondsand they talk about 2D gastroloids and 3D gastrloids and um they're talking about relating     
10:3510 minutes, 35 secondsflow and forces during embryogenesis uh like things like tissue flow. So tissues often times migrate or they     
10:4310 minutes, 43 secondsalways migrate in a structure like this and they conform to these flows and you can measure them using uh particle image velo.     
10:5410 minutes, 54 secondsSo you can use different methods to look at these migratory events and you can characterize them.     
11:0211 minutes, 2 secondsuh they also point out that uh tissues that form in these structures are like     
11:0911 minutes, 9 secondsan active fiscal elastic material which means that they have both fluid and solid-like properties and so you can characterize them with     
11:1811 minutes, 18 secondsparameters such as viscosity and elasticity.     
11:2111 minutes, 21 secondsSo this is kind of they're using tissue mechanics to model these systems     
11:2911 minutes, 29 secondsand then they talk about coarse grained approaches. So their modeling here involves coarse screening and fine     
11:3611 minutes, 36 secondsgraining and picking the appropriate type of modeling for the appropriate     
11:4111 minutes, 41 secondsproblem. So looking at larger structures is going to require a coarser     
11:4811 minutes, 48 secondsdescription and looking at smaller structures requires a more fine grained approach.     
11:5711 minutes, 57 secondsAnd then of course they're talking about some of these different types of embryoids and other types of organoid     
12:0412 minutes, 4 secondsstructures that you find in uh different developmental systems and how to     
12:1012 minutes, 10 secondscharacterize those. Okay. So then Susan of course is interested in the physics and mechanics of embryos and she had some things to say about that.     
12:2412 minutes, 24 secondsYeah. Back to the paper for a minute. Then we finally talked about this paper.     
12:3212 minutes, 32 secondsUm this is a paper could loving cells use phase transitions to process information.     
12:3812 minutes, 38 secondsAnd this is a paper that talks about um these kinds of we've talked about this     
12:4612 minutes, 46 secondsin the group before biomolecular condensets which a condenset is a a structure in a     
12:5312 minutes, 53 secondscell in the cytoplasm that's like kind of an aggregation of different biomolecules. They could be proteins,     
13:0013 minutesthey could be peptides, they could be uh RNA structures. And so, but these condensates seem to play a role in     
13:1013 minutes, 10 secondsdifferent things. And it's it's a hot field because people see them and they don't exactly know what they do. But the hypothesis raised in this paper is that     
13:1913 minutes, 19 secondsthe used to mediate phase transitions and to do information processing. And so this is kind of uh you know it's it's     
13:2813 minutes, 28 secondskind of speculative I guess but it's also you know pretty I think pretty good uh in terms of what they're     
13:3713 minutes, 37 secondsyou know expl so this whole idea of in uh cellular information processing is that uh cellular phase transitions solve     
13:4713 minutes, 47 secondsa range of problems. So you need a phase transition in the cell, a change in state to process information and they     
13:5513 minutes, 55 secondstalk about uh information processing in the cell as a matter of expressivity.     
14:0114 minutes, 1 secondSo if you have that mechanism of the phase transition, what range of things can it solve and     
14:0814 minutes, 8 secondswhat kinds of things can it learn or adapt to or solve? And so this is kind of an interesting way of approaching     
14:1514 minutes, 15 secondsthis. Um it's it's a very interdisciplinary approach involving molecular biophysics, soft matter and embodied computation.     
14:2614 minutes, 26 secondsAnd it's the embodied computation part we're going to come back to next week.     
14:3014 minutes, 30 secondsUm because it's, you know, this is something that is very different from the kinds of embodied cognition problems we've been talking about in this group.     
14:4114 minutes, 41 secondsOkay. So yeah, we're going to come back to this next week and we finished the meeting with some commentary.     
14:4814 minutes, 48 secondsUh we on Wednesday we had our cognition futures meeting and that's uh I'll let Jesse talk a little bit about that     
14:5514 minutes, 55 secondslater. It was interesting. We covered a a paper um from that special issue that     
15:0215 minutes, 2 secondsuh we published in from Royal Royal Society A and we you know again that's something we can follow up on here as well.     
15:1215 minutes, 12 secondsin this uh meeting. This was the open source meeting on Friday. Um we had some interesting conversations about open     
15:1915 minutes, 19 secondssource and about uh we've been on this topic of generative AI and open source which we     
15:2715 minutes, 27 secondsfollow up in in this meeting. Uh Baran again giving an update on his work. I I     
15:3415 minutes, 34 secondsshowed his poll request by Friday. he was able to make the pull request and it just involved some different files that     
15:4115 minutes, 41 secondswere created and you know modified. He did the smoke testing and all of that.     
15:5015 minutes, 50 secondsUh then I I actually uh showed off this paper. So Giadrath Gian who was a uh Gox     
15:5915 minutes, 59 secondsstudent in 2024 or 2025 I can't remember. Oh I think it was last year. um he did his project on     
16:0816 minutes, 8 secondssomething called temporal graphs. And so his project was called DVOG, developmental temporal graph networks.     
16:1716 minutes, 17 secondsAnd so this is his part of the DV DVO graph repository where he hosted his project. And so he was working on a     
16:2716 minutes, 27 secondspaper. Uh I try to encourage people to put out a paper on their projects.     
16:3316 minutes, 33 secondsand he was able to finish up that paper recently and get it posted on the archive. So this is the link to the     
16:4016 minutes, 40 secondspaper here and I'll show the paper in a minute. This is the paper from the archive dvotg temporal graph neural networks for     
16:4716 minutes, 47 secondsmodeling C elegance developmental contoics. So this is the paper uh where you know they were using he was using     
16:5516 minutes, 55 secondsthat whitle data set that the last paper used and he did it instead of looking at     
17:0217 minutes, 2 secondsuh c neural circuits he was just simply interested in changes in the network over time. So looking at how the network     
17:0917 minutes, 9 secondstopology changes and uh doing some other testing using area under the curve and     
17:1717 minutes, 17 secondssome other things. So he's looking at cell division events from cell lineage data um and plugging them into these     
17:2517 minutes, 25 secondsdiscrete time dynamic graphs and then looking at changes in the conneto.     
17:3017 minutes, 30 secondsSo that's uh this is what this paper was about. He also did some analyses which were interesting uh involving rich club     
17:4017 minutes, 40 secondsuh neurons which are these highly connected neurons and the sea elegance conneto and looking at their uh network properties.     
17:5017 minutes, 50 secondsSo congratulations to giadrotha on that.     
17:5417 minutes, 54 secondsOkay and then this uh topic that we talked about. So this is uh from     
18:0218 minutes, 2 secondsuh the sustainable software foundation or something. Um     
18:1018 minutes, 10 secondsthis is from the SFC. Um this is a uh organization the software freedom conservancy.     
18:1818 minutes, 18 secondsAnd so they they're interested in uh advocating for foss software or free and open source software.     
18:2518 minutes, 25 secondsAnd I I wanted to go through this arc of sort of thinking about the role of generative AI in open-source and     
18:3418 minutes, 34 secondsespecially in open-source contributions because uh it's an open question and they actually have dealt with this.     
18:4418 minutes, 44 secondsThey've they've grappled with this and they've come up with some recommendations.     
18:4818 minutes, 48 secondsSo I wanted to go over that sort of how they came to that sort of decision to do that. So back in 2022     
18:5718 minutes, 57 secondsum this article was published on their organization's blog if software is my co-pilot who     
19:0519 minutes, 5 secondsprogrammed my software and this is about how Microsoft bought GitHub and then     
19:1219 minutes, 12 secondsonce they bought GitHub they injected Copilo into GitHub and not only have they sort of encouraged people to use     
19:2119 minutes, 21 secondsCopilot to build things which includes open- source projects, but they've also used uh a lot of stuff from GitHub as     
19:3019 minutes, 30 secondstraining data. And this just struggles with sort of the implications of this.     
19:3519 minutes, 35 secondsFor one thing, you have a training set that may include copyright code. And in open source, our goal is to     
19:4519 minutes, 45 secondsalways strive for copy left code. So copy left is where intellectual property     
19:5319 minutes, 53 secondsis protected but the person who adopts the license gets to choose how restrictive or how unrestrictive     
20:0220 minutes, 2 secondsthat license is. Whereas copyright tends to just restrict everything by default.     
20:1020 minutes, 10 secondsAnd copy left is important for open source because copy left sort of controls and mediates this idea of uh remixing a recombination.     
20:2220 minutes, 22 secondsThat is when you have something that you say fork and you modify it. You're remixing that thing. Or when you have     
20:3020 minutes, 30 secondssome uh like some media that you take and you remix it, you take out clips of it and you use it for your own purposes.     
20:3820 minutes, 38 secondsThat's remixing. And so copy left is an important concept there because it allows you to sort of control that     
20:4620 minutes, 46 secondsremixing process and you know not always say it's just not allowed but to use it in a productive way.     
20:5520 minutes, 55 secondsSo this just goes through sort of how open source projects have to grapple with this. Not only in terms of     
21:0321 minutes, 3 secondsintellectual property, but then of course in terms of pull requests and the level of volume of pull requests, the     
21:1221 minutes, 12 secondslevel of quality in those pull requests and all of that. So this is a a issue for maintainers, but ultimately it's an issue for the quality of the projects.     
21:2421 minutes, 24 secondsSo they need they just and in 2022 they need to get their arms around all of this. So this just speculates on what might happen and what might happen if we     
21:3321 minutes, 33 secondsfail to sort of live up to the standards of free and open source software which of course is freedom to have access to     
21:4321 minutes, 43 secondssoftware, access to code, being able to build things in a way that's um you know enabling instead of sort of proprietary.     
21:5421 minutes, 54 secondsand we talked about that in the meeting.     
22:0022 minutesAnd so this is just kind of going through some of their philosophy and things like that. Um then there was this     
22:0722 minutes, 7 secondsother post that was published later. I think it was like last year or the year before and these are recommendations that they     
22:1522 minutes, 15 secondshad come to. So it back in 2022 they had this sort of um sort of post about you     
22:2322 minutes, 23 secondsknow thinking about this problem very broadly.     
22:2622 minutes, 26 secondsUm but now they're at this point they're ready to uh make some recommendations.     
22:3222 minutes, 32 secondsSo the recommendations are here. There are 14 of them ranked in order of importance     
22:4022 minutes, 40 secondsand it's really just talking about what the Foss community and what FOSS organizations should expect and what     
22:4722 minutes, 47 secondstheir moray should be about this. So they should both welcome people using     
22:5522 minutes, 55 secondsgenerative AI and be very mindful of you know what the contribution is. So this     
23:0323 minutes, 3 secondsjust kind tries to strike this balance um and you know it's really guidance for organizations.     
23:1023 minutes, 10 secondsUh so you know if you have a contributor comes to you and wants to contribute and they contribute something that was     
23:1623 minutes, 16 secondsobviously generated using generative AI um if it's of quality of course it's welcome but if it's not of quality then     
23:2523 minutes, 25 secondswhat do you do and and and of course even if it is of quality and it gets accepted you know where does that code     
23:3223 minutes, 32 secondsoriginate and you know there are a lot of things that we have to think about there and it actually goes back to you know     
23:4123 minutes, 41 secondssort of having quality control in open source projects but you know it also addresses some things that people really haven't     
23:4823 minutes, 48 secondsthought out very well that is you know what is the procedure for assessing quality of a contribution     
23:5623 minutes, 56 secondsI mean we've had a lot of cases where people have contributed things to open-source projects that were malicious     
24:0524 minutes, 5 secondsand you know unless you have a good quality control uh methodology, you miss those things. You might accept a pull     
24:1424 minutes, 14 secondsrequest that looks of of quality on the surface, but then is actually malicious.     
24:1924 minutes, 19 secondsAnd so these are things that we haven't really worked out, but you know, they're thinking about this in the context of Gen AI, but there other places where it applies.     
24:3024 minutes, 30 secondsAnd so they go through all these different things that you can do as an organization.     
24:3524 minutes, 35 secondsUm they talk about how uh generative AI can often be a copyright washing machine that     
24:4324 minutes, 43 secondsultimately ruins copy theft and this this is a legal issue more than an open-source issue but it does affect     
24:4924 minutes, 49 secondsopen source organizations and uh you know also just about like you     
24:5824 minutes, 58 secondsknow how does it how does it affect downstream licensing? So they're advocate they advocate for a copy left     
25:0625 minutes, 6 secondseverything or a copy left maximal approach. Meaning no matter what you always want to keep your organization in this copywft regime you always want to     
25:1525 minutes, 15 secondshave an open- source license. You don't want to have to be forced to make things proprietary.     
25:2225 minutes, 22 secondsAnd of course then this all relates to the acceleration where the maintain maintenance of an acceleration of     
25:2925 minutes, 29 secondsinnovation under something like FOS as opposed to something like a proprietary model.     
25:3725 minutes, 37 secondsOkay. So that's just kind of some of the points there. So we had a discussion about this. Jesse had a lot of things to     
25:4425 minutes, 44 secondssay because it fits a a lot into his um you know interests and the society ethics and tech group and all of that.     
25:5625 minutes, 56 secondsOkay. So I think that was it for that meeting.     
26:0026 minutesWell, well, Kavia had one thing to add, which was uh the stuff that he's doing on developmental AI, which we talked about before I started recapping the meetings.     
26:1226 minutes, 12 secondsAnd so, he actually did bring up a paper was this paper here,     
26:2026 minutes, 20 secondsOmar inspired framework for raising good robots. And this is Sarah Hamburg at all. and uh she does a lot of stuff with     
26:2826 minutes, 28 secondsactive inference and development. And so this is just kind of walking through Mars framework of the implementation     
26:3626 minutes, 36 secondslevel, algorithmic level and computation level in the context of this problem.     
26:4326 minutes, 43 secondsAnd so this is this is an interesting paper. Uh we'll have to revisit this paper later as I said.     
26:5026 minutes, 50 secondsSo that was that meeting.     
26:5426 minutes, 54 secondsOkay. So, that was what we had uh from this past week. I'm not going to recap the cognition futures meeting we had on Wednesday because     
27:0227 minutes, 2 secondsum I'll let Jesse do that. So, any questions about that?     
27:0727 minutes, 7 secondsI did want to point something. I think Morgan sent me this link on link. Oh, cavia. Um does the dower stage affect     
27:1427 minutes, 14 secondsthe graph part you showed? Um it can. I mean, they didn't look at that. They didn't look at the hour worms, but they that would give you differences in     
27:2327 minutes, 23 secondsconnectivity. Remember, they're looking at synaptic connectivity. So they have they basically count the number of synapses for a given connection.     
27:3227 minutes, 32 secondsAnd when you know they they weight the connection based on those number of connection number of synapses that they find. And so in dow worms you get a lot     
27:4127 minutes, 41 secondsof changes in synaptic connectivity. So yeah, we change those a bit. But you know this is kind of like they're     
27:4827 minutes, 48 secondsobserving worms and they're saying this is how they vary in connectivity across these different stages of development.     
27:5627 minutes, 56 secondsUm so it's you know they may be different if you look at different worms especially dower worms but even just     
28:0528 minutes, 5 secondsgeneral you know if you have like defined mutants say where you have a certain mutation that's     
28:1228 minutes, 12 secondsuh persistent in the in the lineage of that worm then you'll have uh maybe differences in connectivity there too.     
28:2028 minutes, 20 secondsSo there's a lot of variation to explore there.     
28:2328 minutes, 23 secondsOkay. Um, so yeah, like I said, Morgan uh posted this on LinkedIn or a link to     
28:3028 minutes, 30 secondsthis and it's this book called Embodied Intelligence, Multidisciplinary Perspective, a natural artificial and hybrid systems.     
28:4028 minutes, 40 secondsThis was something that was talked about at the embodied intelligence conferences here. we had um     
28:4828 minutes, 48 secondsuh you know we have our authors here who are regular contributors to that workshop and so uh they they were     
28:5728 minutes, 57 secondsworking on this book and they were they had a whole session on kind of going through this chapter by chapter so I'm glad to see that it's out and it's     
29:0629 minutes, 6 secondsavailable this is available um open access I believe yeah and so     
29:1229 minutes, 12 secondsthis is uh from MIT Press and it's uh a book on different types of embodied     
29:2029 minutes, 20 secondsintelligence and different types of systems. So, you know, they're very interested in robotic embodied cognition at this workshop. They're also     
29:2929 minutes, 29 secondsinterested in human embodied intelligence and everything in between.     
29:3329 minutes, 33 secondsSo, they're a lot of non-human animal uh models that you can use to look at embodiment. Um and so you know you can     
29:4229 minutes, 42 secondslook at embodiment in virtual reality and you know there was a lot of ways in which you can study this topic.     
29:5229 minutes, 52 secondsSo this is an exploration of embodied intelligence that moves beyond the traditional focus of brains and code to     
29:5929 minutes, 59 secondsthe role of embodiment across various disciplines. So it's not just focused studies. Um it's really kind of thinking     
30:0630 minutes, 6 secondsabout how embodiment persists across different um of different areas of of study.     
30:1630 minutes, 16 secondsSo um they have this introduction towards embodied intelligence.     
30:2130 minutes, 21 secondsUh they have the opening they have this chapter one convergences of human and artificial embodied perspectives. So     
30:2930 minutes, 29 secondssort of how we study it in humans versus how we study it in robots.     
30:3430 minutes, 34 secondsUh we have this article artificial selves robotment which is robot embodiment and narrative identity in robots.     
30:4330 minutes, 43 secondsThis third chapter the 30 years war on representations in the active inference west failia. This is by Axel constant     
30:5030 minutes, 50 secondsAndy Clark and Carl Fristen. It's very Andy Clark type of title where you know it's kind of thinking about active     
30:5730 minutes, 57 secondsinference and its role in representations or neural representations. So there's been this     
31:0431 minutes, 4 secondswhole and this came up in Wednesday's uh cognition futures meeting. There's been this whole debate about     
31:1231 minutes, 12 secondsrepresentations in the brain. So when we learn things we have maybe a representation of those things and you know if we learn things     
31:2131 minutes, 21 secondsin neural networks we also have a representation of of things there. The question is what does that representation look like? Is it is it     
31:3031 minutes, 30 secondspervasive or is it minimal or does it even exist? And a lot of the people in Seite the um radical embodied cognition     
31:4031 minutes, 40 secondscamp would argue that representations don't really exist in the brain. they're a product of the environment. And     
31:4731 minutes, 47 secondsthere's this whole debate about representations and whether they exist or not. Sometimes people take the view that well yeah they     
31:5531 minutes, 55 secondsexist but in a limited fashion and all of this and their point here is that there's been this debate but then active     
32:0332 minutes, 3 secondsinference is sort of the west failure or like this is the event that sort of settled the 30 years war ended it. So     
32:1232 minutes, 12 secondsactive inference sort of settles this debate.     
32:1632 minutes, 16 secondsUh it's an interesting article. Um but it's yeah it's definitely something that probably won't end the debate. Um this     
32:2532 minutes, 25 secondsnumber four is predictive processing from sensory motor skills to higher cognition. And again we have active inference people involved here. Giovanni Pizzulo, Thomas Park and Carl Fristen.     
32:3932 minutes, 39 secondsUm, so that's nice that there's this active inference thrust.     
32:4532 minutes, 45 secondsUh, then there's this part two embodied artificial intelligence.     
32:4932 minutes, 49 secondsThere's this uh article from Connor Hines and Mahala Albaras and Alex Kefir and these are active inference people as     
32:5732 minutes, 57 secondswell. They're associated with the active inference institute. This is advantages of ecological AI.     
33:0433 minutes, 4 secondsUm, that's interesting. Uh then there's number chapter six grounded embodied and situated intelligence in humans and artificial agents.     
33:1533 minutes, 15 secondsUh then there's chapter seven embodied cognition and strong AI.     
33:2033 minutes, 20 secondsUm and there's chapter eight embodied AI and machine learning isn't really embodied.     
33:2733 minutes, 27 secondsChapter nine, the embodied future of robotics.     
33:3133 minutes, 31 secondsAnd then that's that's part two. And then part three is adaptation, morphology and emergence.     
33:3733 minutes, 37 secondsSo chapter 10 is morphological pre-training. That's from Josh Bongard, adaptation from the inside out. That that looks interesting. We've talked     
33:4633 minutes, 46 secondsabout um some of this in uh the context of filtering     
33:5333 minutes, 53 secondsuh or or embodied filtering. And you know, this is obviously from a very Josh Bar Bongard point of view.     
34:0234 minutes, 2 secondsuh ex chapter 11 exploring cognition through a morphological information computational framework. So this is like     
34:1034 minutes, 10 secondsmorphological uh computation this area the book um chapter 12 this involves dober anyway     
34:1934 minutes, 19 secondsdov and Tom froze and that's embodied AI based on dynamic human computer interaction.     
34:2734 minutes, 27 secondsSo that's part three and then part four is emotion learning and embodied interaction.     
34:3334 minutes, 33 secondsChapter 13 emotion modeling and its embodiment and transition.     
34:3834 minutes, 38 secondsChapter 14 embodying emotions and autonomous and social robots homeostasis hormones and interaction and embodied AI.     
34:4834 minutes, 48 secondsUh that looks interesting. Um chapter 15 AI designer know thyself.     
34:5434 minutes, 54 secondswhat we learn about human intelligence through building artificial intelligence. Um, and that's that's chap or part four.     
35:0235 minutes, 2 secondsAnd then part five is embodied intelligence unifying principles. So this is where we're bringing everything together.     
35:1035 minutes, 10 secondsSo 16 is embodied intelligence enabling the next intelligence revolution.     
35:1635 minutes, 16 secondsAnd these are people from the embodied intelligence workshop kind of considering how this all fits together.     
35:2535 minutes, 25 secondsMike 11 as a chapter. Chapter 17, diverse intelligences, the space of possible minds.     
35:3235 minutes, 32 secondsThen chapter 18 is the conclusion.     
35:3635 minutes, 36 secondsAnd that's the book. And so this is um see if I can get a link to the book here. All right, there we are. There's     
35:4335 minutes, 43 secondsthe cover. It's nice cover. Um they have so it's 459 pages. So if you're uh     
35:5235 minutes, 52 secondsinterested in this book, it's available open access through MIT Press. Ah, looks like Vit's here. Hello, Vit.     
36:0136 minutes, 1 secondHi. How Yeah. Am I audible?     
36:1036 minutes, 10 secondsYeah.     
36:1336 minutes, 13 secondsYeah. Just asking how is everything. I couldn't join in last week either, so yeah, we've been doing pretty well.     
36:2036 minutes, 20 secondsHow about yourself? Are you busy this summer?     
36:2536 minutes, 25 secondsYeah, I am. I'm actually working somewhere else and then I'm just busy with that project. So, I go to office and that and then my summer internship     
36:3436 minutes, 34 secondsis just till 28th July. So, I'm just in the phase of wrapping up right now. Then I'll have my final presentation over there. So,     
36:4236 minutes, 42 secondsjust busy in that. So now it's still a bit lighter but like before that like till now I've just been busy with the project that they are doing and and     
36:5036 minutes, 50 secondssince a company is just not one project right it's like if they need any other small help or anything can I help over there like that     
37:0137 minutes, 1 secondyeah sounds good so yeah to hear that everything's going well     
37:0837 minutes, 8 secondsyeah everything's fine good Yeah, great.     
37:1537 minutes, 15 secondsActually, this was actually this was something that I had actually heard from um Ankit Grover in the Slack and he had     
37:2337 minutes, 23 secondsrun across a DVO TG uh paper and he was uh saying that he was pretty impressed by it. He's interested in learning more     
37:3237 minutes, 32 secondsabout it. Uh then he mentioned some tools we might use to follow up on it.     
37:3637 minutes, 36 secondsSo that's good. Um yeah so thank you Ankit for that vote of confidence on that paper.     
37:4437 minutes, 44 secondsOkay I'm going to talk about a paper um this is uh game theory game theoretical interactions of moving agents. This is     
37:5337 minutes, 53 secondswhen gion you and Durk Helbing Dirk Helping is a complexity person. He runs     
38:0038 minutescomplexity um like a a website where he does a lot of demos of complexity concepts.     
38:0938 minutes, 9 secondsUm so I think it's complexity explainables or complexity something like that and um so he's he's     
38:1638 minutes, 16 secondsgot some interesting uh usually he's engaged in some interesting work. He's at ETHZurich. So that's uh where the     
38:2538 minutes, 25 secondsauthors are located here. uh this is from the archive and it talks about game theory and some     
38:3338 minutes, 33 secondsof the things about agentive systems or multi- aent systems. So I thought it would be kind of interesting for     
38:4138 minutes, 41 secondsjust thinking of what they're doing here.     
38:4538 minutes, 45 secondsSo the abstract reads, "Game theory has been one of the most successful quantitative concepts to describe social interactions, their strategic aspects     
38:5438 minutes, 54 secondsand outcomes. Among the payoff matrix, quantifying the results of social interaction, the interaction conditions     
39:0139 minutes, 1 secondhave been varied such as the number of repeated interactions, the number of interaction partners, the possibility to     
39:0839 minutes, 8 secondspunish defective behavior, etc.     
39:1339 minutes, 13 secondsWhile an extension to spatial interactions has been considered early on, such as in the game of life, recent studies have focused on effects of the     
39:2139 minutes, 21 secondsstructure of social interaction networks.     
39:2439 minutes, 24 secondsHowever, the possibility of individuals to move and thereby evade areas with a high level of defection and to seek     
39:3239 minutes, 32 secondsareas with a high level of cooperation has not been fully explored so far. So what they're referring to here is     
39:4039 minutes, 40 secondsthey're referring to uh things like the prisoner's dilemma where in the prisoner's dilemma you have maybe like a     
39:5039 minutes, 50 secondsgroup of people could be two or three people who are engaged in some sort of activity maybe a conspiratorial activity. The idea is maybe they've committed a crime together.     
40:0240 minutes, 2 secondsAnd then when the police interview them, they interview them uh both, you know, one at a time. And they want to know     
40:0940 minutes, 9 secondswhat they each know. And they also want to see if any one person will defect and     
40:1740 minutes, 17 secondsuh flip and tell the police about the activities of the other people. So they want to see if they can get some sort of     
40:2340 minutes, 23 secondsdefection from the group which exists in in conflict with cooperation within the group. So the group can stick together     
40:3240 minutes, 32 secondsand no one individual can talk to the police and give them any information or one person can defect and usually you     
40:4040 minutes, 40 secondsknow they get some their sentence commuted or something. So, they get a benefit for themselves, but then the     
40:4740 minutes, 47 secondsgroup suffers because the other two people um get get outed or thrown under the bus, as they say. So, that's that's kind of where they're going with this.     
40:5740 minutes, 57 secondsThey're they're kind of using the prisoners example or the prisoners dilemma example without actually mentioning it by name.     
41:0741 minutes, 7 secondsSo the idea here is that they're extending this to individuals moving around a spatial array. And so you you     
41:1641 minutes, 16 secondshave different regions of the spatial array where there's a higher level of defection. And you can move to places where there's a high level of cooperation.     
41:2441 minutes, 24 secondsAnd when you move to places with a high level of cooperation, it selects for or it encourages     
41:3241 minutes, 32 secondsuh group cohesion. because obviously if you don't have cooperation, if everyone's in it for themselves, that's     
41:3941 minutes, 39 secondsnot good for uh collective behavior. And so this is where you have a bunch of agents on a grid or on some sort of uh     
41:4741 minutes, 47 secondsspatial surface and they're moving around and they're trying to find places that are sort of key for cooperation and     
41:5541 minutes, 55 secondsthey're trying to evade areas that are centers of defection. That's basically the idea. And so this contribution     
42:0442 minutes, 4 secondspresents a model combining game theoretical interactions with success driven motion in space and studies the     
42:1142 minutes, 11 secondsconsequences that this may have for the degree of cooperation and the spatiotemporal dynamics in the population. So again, this is a multi-     
42:2142 minutes, 21 secondsaent uh simulation where there's this imperative and you can look at uh the     
42:2842 minutes, 28 secondsstrategies employed by any one agent and you can look across agents and see that they tend towards the strategy of     
42:3742 minutes, 37 secondsencouraging cooperation and uh minimizing defection. But they all do this independently. So they all make independent judgments about this     
42:4642 minutes, 46 secondsand it's reflected in the movement patterns of the agents. So they're moving to places where these are these things are sort of highly rewarded. So     
42:5542 minutes, 55 secondsthere might be one region of the space where cooperation is rewarded. There might be other regions of the space where defection is rewarded. So whatever     
43:0343 minutes, 3 secondsthe payoffs are for those different strategies in different regions of the space determine how these agents move.     
43:1443 minutes, 14 secondsIt is demonstrated that the combination of game theoretic interactions with motion gives rise to many self-organized behavioral patterns on an aggregate     
43:2243 minutes, 22 secondslevel which can explain a variety of empirically observed social behaviors.     
43:2843 minutes, 28 secondsSo, you know, we're looking at how these uh behavioral patterns emerge in space.     
43:3443 minutes, 34 secondsSo, as the agents move, they move to these areas and they, you know, form groups. They form collectives.     
43:4143 minutes, 41 secondsAnd then we want to be able to analyze that at the end of our simulation and see what the outcome is.     
43:5043 minutes, 50 secondsSo getting into the paper, macroscopic outcomes in a social system resulting from interactions between individuals     
43:5843 minutes, 58 secondscan be quite different from anyone's intent. For instance, empirical investigations suggests that people prefer different     
44:0644 minutes, 6 secondstypes of neighborhoods based on their selfidentity. Uh so one could think that integrated neighborhoods should be widely observed but empirically this is     
44:1444 minutes, 14 secondsnot true. One find rather find segregated neighborhoods such as separate urban quarters which also applies to people with different social     
44:2244 minutes, 22 secondsand economic backgrounds. This is actually building off of showing segregation uh simulations that he ran in the 60s.     
44:3144 minutes, 31 secondsUm and so this is a old problem in uh urban sociology     
44:3844 minutes, 38 secondslooking at different uh people belonging to different social groups and whether they move into the same neighborhoods or     
44:4644 minutes, 46 secondsthey move into neighborhoods with people of different backgrounds. There's this urban ecological social distance tradition in sociology and the     
44:5444 minutes, 54 secondsindividual preference tradition in economics. So basically you're looking at this difference between the     
45:0145 minutes, 1 secondsociological lens and the economics lens. The main idea of social distance theory is that differences in culture     
45:0845 minutes, 8 secondsand interests between social groups are reflected by a separation of the residential areas. Um     
45:1645 minutes, 16 secondsand then so this is yet the role of social distance and individual preferences is questioned by the studies of the American urban housing market     
45:2445 minutes, 24 secondswhich suggests that racial discrimination and prejudices are the primary factor of residential segregation and concentration of     
45:3245 minutes, 32 secondspoverty. There are three stages in the housing market transaction which is where you know they kind of go through um you know the information     
45:4145 minutes, 41 secondsabout available housing units, terms and conditions of sales and financing assistance and then access to units     
45:4845 minutes, 48 secondsother than the advertised unit. In each stage the housing agent may behave in a discriminatory way, withhold information from customers and discourage them.     
45:5945 minutes, 59 secondsTherefore, the access of minority customers to housing is severely constrained. While the theory of preference-based dynamics assumes that     
46:0646 minutes, 6 secondspeople can relocate freely according to their own preferences, which fails to reflect the real relocation dynamics.     
46:1446 minutes, 14 secondsAnd so this just kind of goes through the relevance of this kind of study that they're going to do. So, um     
46:2346 minutes, 23 secondsthen we can look at this in game theoretic terms. We can look at migration, game theory, and cooperation.     
46:3146 minutes, 31 secondsSo in game theoretic terms, this movement to a more favorable neighborhood could be reflected by a higher payoff to presents who moved called migrants in the following way.     
46:4246 minutes, 42 secondsMigratory behavior aimed at higher payoffs is called success driven motion.     
46:4746 minutes, 47 secondsSo this is where you're moving to get a higher payoff. And this is what they call success driven motion. And there's     
46:5546 minutes, 55 secondssome citations to back this up. As we will show later in later sections, successor of motion can reproduce     
47:0347 minutes, 3 secondsresidential segregation and some other observed phenomena population dynamics as well like population succession     
47:1247 minutes, 12 secondswhich is an example of which is cycles of changing habitation. You see this in ecology with different species in ecosystems.     
47:2247 minutes, 22 secondsWe will also study how a change of the spatial population structure can affect the level and evolution of cooperation in a population.     
47:3247 minutes, 32 secondsIt could be thought that natural selection implying competition between individuals would result in selfish rather than cooperative behavior.     
47:4247 minutes, 42 secondsNevertheless, cooperation is widely observed also in competitive settings from bacteria     
47:4947 minutes, 49 secondsum and in animals as well. Game theory has been regarded as a powerful     
47:5647 minutes, 56 secondsframework to investigate this problem as it can be used to quantify the interactions between individuals.     
48:0548 minutes, 5 secondsAnd so there's a mathematical formal uh formalization to this. So the mathematical description of of selfish     
48:1348 minutes, 13 secondsbehavior tendencies is often based on the prisoners dilemma game in which the reward R represents the payoff for     
48:2148 minutes, 21 secondsmutual cooperation while the payoff for defection or cheating on both sides is reflected by the punishment P.     
48:3048 minutes, 30 secondsSo this is where you know the idea that if say if you have two prisoners who collaborate on a crime and they get     
48:3648 minutes, 36 secondsinterviewed individually by the police and they have to you know tell the police what they know and they get a     
48:4448 minutes, 44 secondsreduced sentence um and but that involves um you know identifying the other person and     
48:5148 minutes, 51 secondsbetraying the other person's trust and all of that. So the punishment is where the individual flips and gives the     
49:0049 minutespolice that information. Now the idea is is that's punishment because both prisoners would do this. Um whereas the     
49:0949 minutes, 9 secondsreward is when both prisoners keep their mouth shut and the police get no information.     
49:1549 minutes, 15 secondsSo that's the the way that that's structured in the prisoners dilemma. So you have reward, you have punishment,     
49:2249 minutes, 22 secondsand you have maybe some state where one prisoner flips and the other prisoner doesn't. So this is actually the um     
49:3249 minutes, 32 secondsanother optimal state where one prisoner gets sort of the reward and then the other prisoner gets the punishment. I mean it's optimal for the one prisoner     
49:4149 minutes, 41 secondsbut it doesn't uh encourage uh social behavior pro-social behavior.     
49:4849 minutes, 48 secondsUnilateral cooperation will occur in the so-called suckers payoff s where the defector gains t the temptation. This is     
49:5649 minutes, 56 secondswhat I was describing before. Um given that inequalities t is greater than r is greater than p is greater than     
50:0450 minutes, 4 secondss. Um so temptation is greater than reward is greater than uh punishment is     
50:1150 minutes, 11 secondsgreater than the sucker's payoff and 2 r is greater than t plus s. defection is tempting and cooperation is risky. So     
50:2150 minutes, 21 secondsyou you're tempted to defect and it's risky to cooperate because you don't know if the other person is also cooperating or if they're defecting.     
50:3050 minutes, 30 secondsSo that defection is expected to be dominating. Although mutual cooperation improves the average payoff.     
50:3750 minutes, 37 secondsSo the payoff is better when you cooperate, but there's no way to to to know that other people are cooperating.     
50:4550 minutes, 45 secondsSo you t typically will defect and there's a a limited reward there, but at least you know you'll get that reward.     
50:5250 minutes, 52 secondsThat's basically the way that the prisoners dilemma is structured. So that's what they're using as a way to model the spatial segregation problem.     
51:0351 minutes, 3 secondsIn a well-mixed population where an individual interacts with all the others, a defector's payoff is always higher than the average payoff which     
51:1151 minutes, 11 secondsleads to a prosperity of defectors. So defection of course pays off higher than     
51:1851 minutes, 18 secondsthe average. And so that actually dis uh discourages cooperation.     
51:2551 minutes, 25 secondsBut sometimes you can have and well mixed population is just basically where everyone's interacting with each other.     
51:3151 minutes, 31 secondsSo it's you know there's no like preferential individuals uh interacting with one     
51:3751 minutes, 37 secondsanother. Maybe they have a very uh varying amounts of trust in each other.     
51:4451 minutes, 44 secondsSo it's it's not you know that's that's all controlled for. This is uh of course not a spatial game.     
51:5351 minutes, 53 secondsIt's just kind of an irregular setting where you have this these interactions going on amongst agents.     
52:0152 minutes, 1 secondSo when we add the spatial dimension, we should expect that maybe the dynamics will look different in an evolutionary setting as it is     
52:0952 minutes, 9 secondsdescribed by the replicator dynamics and that's uh where we have replication of agents and their states. Only those     
52:1852 minutes, 18 secondsstrategies that generate above average payoffs have the chance to spread.     
52:2352 minutes, 23 secondsTherefore, from an evolutionary perspective, there will be no cooperators in the end, which contradicts the observed cooperation in reality.     
52:3252 minutes, 32 secondsSo, we expect uh defection to dominate and we expect no     
52:4052 minutes, 40 secondscooperation even though in reality we observe cooperation.     
52:4552 minutes, 45 secondsA variety of mechanisms have been proposed to explain the considerable level of cooperation observed under certain circumstances.     
52:5452 minutes, 54 secondsThese include kin selection, direct reciprocity, indirect reciprocity, group selection, and network reciprocity.     
53:0453 minutes, 4 secondsIn particular, it is interesting that the spatial population structure can significantly change the level of cooperation in a population.     
53:1353 minutes, 13 secondsWhile there could be a co-evolution of social structure and cooperation due to migratory behavior, this subject has not     
53:2153 minutes, 21 secondsbeen well studied in the past. So that's what they're going to do here.     
53:2553 minutes, 25 secondsSo they go through um some real world data from different urban areas. They're looking at the city of Chicago and the     
53:3453 minutes, 34 secondsmovement of immigrants in the early 20th century.     
53:3953 minutes, 39 secondsAnd they see that in that data set they have different types of succession processes of specific cultural groups     
53:4853 minutes, 48 secondswhere you have sort of uh an initial settlement, you have conflict, you have recession and reorganization.     
53:5653 minutes, 56 secondsSo you have groups that move into a certain area, other groups will kind of move into the same area, there will be conflict and then uh there will be     
54:0454 minutes, 4 secondsreegregation of those areas by that group.     
54:0854 minutes, 8 secondsSo uh the invasion is sort of when new groups move into an area and then the     
54:1554 minutes, 15 secondsdynamics change. So the invasion then can be initiated by a few pioneers who manage to enter a new area dominated     
54:2354 minutes, 23 secondsby older residents. For example, um you know, people will move to an area and then you know have social     
54:3254 minutes, 32 secondsconnections and that you know other people will move into the area and then there will be this succession. So that's     
54:4154 minutes, 41 secondsthe idea. Um and then of course this assumes that everyone in a certain group um you know that they have this affinity     
54:4954 minutes, 49 secondswith everyone in that group. So that's kind of the assumption being made here.     
54:5554 minutes, 55 secondsSo um following the initial invaders invasions can happen on a much larger scale in     
55:0255 minutes, 2 secondsparticular if housing prices go down. So it's like dependent on housing prices at least in this data set. Then previous     
55:1055 minutes, 10 secondsresidents who want to sell their houses at a good price are eventually replaced.     
55:1555 minutes, 15 secondsPeople may even move without reasons just following a trend of what others do which is a kind of collective hurting behavior. So this is an important point     
55:2455 minutes, 24 secondsis that sometimes these decisions are made sort of consciously and sometimes it's just kind of following some trend     
55:3255 minutes, 32 secondsthat you're observing because sometimes you know what the payoff is and sometimes you don't but you have this sort of signal that's um you know maybe     
55:4255 minutes, 42 secondspeople are cooperating, maybe people are defecting and you're trying to get the the best payoff accompanying this replacement process.     
55:5155 minutes, 51 secondsthe changing composition of the population may cause conflicts due to incompatible cultural values and prejudices. So it's again you know it's     
56:0156 minutes, 1 secondis it uh conscious or unconscious in terms of how the strategy is followed.     
56:0956 minutes, 9 secondsSo this just results in a turnover and you can see this sp these spatial dynamics play out.     
56:1656 minutes, 16 secondsSo this is again something we can model uh computationally.     
56:2156 minutes, 21 secondsUh spatial games based on lises would allow for one to study such effects. In conventional spatial games, individuals     
56:2956 minutes, 29 secondsare uniformly distributed in the simulation area and change or repeat their strategies following a certain updating rule. So an individual is     
56:3856 minutes, 38 secondsassumed to be unconditional or individual is assumed to unconditionally adopt the most successful strategy within that neighborhood. On the one     
56:4756 minutes, 47 secondshand, this creates typical spatiotemporal patterns. On the other hand, spatial structures play an important role in the maintenance of cooperation.     
56:5756 minutes, 57 secondsSo this is where you know you kind of have certain assumptions of the payoff matrix and that determines what the     
57:0557 minutes, 5 secondsspatiotemporal pattern looks like but also if you have a certain spatiotemporal pattern that exists it     
57:1357 minutes, 13 secondssort of uh sets the terms of the payoff uh structure. So it may be more likely     
57:2257 minutes, 22 secondsthat you cooperate or less likely that you cooperate depending on what the existing spatial structure is. So if you     
57:2957 minutes, 29 secondsalready have a segregated neighborhood then it's like uh probably um you know the cooperation the cooperative imperative there may be higher.     
57:4157 minutes, 41 secondsAnd so that's kind of the idea here. In the iterative prisoners dilemma, for example, clusters of cooperators are     
57:4857 minutes, 48 secondsbeneficial to cooperators. While the evolving spatial structure in the Snowdrift game, which is a variant of     
57:5557 minutes, 55 secondsPrisoners Dilemma, and that's a game where um the way this game works     
58:0158 minutes, 1 secondis that you have two snow plows and they are plowing a road from different ends.     
58:0858 minutes, 8 secondsThis is like in a a mountainous area and the snow plows come to a certain point where they meet and the idea is do they     
58:1658 minutes, 16 secondscooperate to move the rest of the snow out of the way or do they not cooperate?     
58:2358 minutes, 23 secondsAnd so this is kind of you can model you know sometimes these games are based on things like idiosyncrasies in the world     
58:3158 minutes, 31 secondsand they just people observe this thing and they kind of name a game after it.     
58:3658 minutes, 36 secondsSo, um, yeah, that's that's what the Snowdrift game is. It's just a variation on the prisoners dilemma, but it has very similar dynamics.     
58:4658 minutes, 46 secondsAnd so, um, you know, we can look at that game and, um, you know, it's a little bit different than the prisoners     
58:5458 minutes, 54 secondsdilemma because there's an explicit spatial structure in it. Um, and so this actually the snow drift game can inhibit     
59:0259 minutes, 2 secondscooperation. So when you get a different type of game or structure of a game, it can have different dynamics.     
59:1159 minutes, 11 secondsConventional spatial games however neglect the possibility of individuals to move or migrate. Although uh mobility     
59:1959 minutes, 19 secondsis a well-known fact of daily social interactions. we will see that the movement of individuals or what we might call population succession can change     
59:2859 minutes, 28 secondsthe spatial structure of a population significantly and influence the evolution of cooperation dramatically.     
59:3659 minutes, 36 secondsSo this is where we get into spatial games with mobility. So these are what we call mobility games. And so we have     
59:4459 minutes, 44 secondsdifferent ways to classify these. We have eight ways to classify them. Uh number one is that mobility may take     
59:5159 minutes, 51 secondsplace in a physical or geographic space with multiple dimensions or it can occur in an abstract space like something like     
59:5959 minutes, 59 secondsopinion space if we're looking at um sort of different types of epistemic models     
1:00:071 hour, 7 secondsrather than a grid. We might have uh a network structure like a friendship network and we can play the game there.     
1:00:161 hour, 16 secondsNumber two is that one may distinguish between games of continuous and discrete motion. So you know whether the movement     
1:00:231 hour, 23 secondsis sort of a trajectory or whether it's across a grid and has different numeric you know number of steps.     
1:00:331 hour, 33 secondsThe first ones may be considered as particular cases of differential games.     
1:00:381 hour, 38 secondsSo continuous games are sort of differential games where you can derive differentiable functions and do things     
1:00:461 hour, 46 secondslike calculus on them and those can be called motion games.     
1:00:511 hour, 51 secondsThe second ones will be named migration games and can be implemented for example in terms of cellular automa.     
1:00:581 hour, 58 secondsSo this is where we have the grid where we have movement across that grid that's uh more categorical in nature.     
1:01:091 hour, 1 minute, 9 secondsNumber three, the mobility game may be deterministic i.e. noisy, influenced by fluctuations     
1:01:161 hour, 1 minute, 16 secondsor having this sort of stochastic property.     
1:01:201 hour, 1 minute, 20 secondsSo it can be either deterministic or stochastic.     
1:01:241 hour, 1 minute, 24 secondsSuch noise can be introduced by stochastic update rules.     
1:01:291 hour, 1 minute, 29 secondsAnd you know there are different ways you can kind of think about setting up that aspect of the game.     
1:01:361 hour, 1 minute, 36 secondsNumber four, multiple occupation of a certain location may be possible allowing for the elomeration of individuals or may be prohibited. In the     
1:01:461 hour, 1 minute, 46 secondslatter case, spatial exclusion requires spatial capacity constraints andor the respect or protection of some private territory.     
1:01:551 hour, 1 minute, 55 secondsSo this is again the dynamics we saw earlier where we were talking about different types of invasions of space     
1:02:021 hour, 2 minutes, 2 secondsand you know kind of people's response to that behaviors you know you know whether they're they all kind of move in     
1:02:101 hour, 2 minutes, 10 secondsmass or they kind of move as sort of a signal that they see in the environment or they don't move at all.     
1:02:201 hour, 2 minutes, 20 secondsNumber five, in mobility games of spatial exclusion, empty sightes are needed. Therefore, the density of free locations is a relative model relevant     
1:02:291 hour, 2 minutes, 29 secondsmodel parameter. So, if you have a very dense grid where no one can move, of course, then you can't really have a     
1:02:361 hour, 2 minutes, 36 secondsmobility game. If you have a very sparse grid, then people can move or agents can move. And if you have a moderate grid,     
1:02:441 hour, 2 minutes, 44 secondsyou have sometimes you have spatial constraints. So it's like they might have you know it might be that there's an imperative to move or u you know     
1:02:531 hour, 2 minutes, 53 secondsthere might be a place where you can get a higher payoff but you can't move because that area is jammed. So you take the next best payoff.     
1:03:031 hour, 3 minutes, 3 secondsNumber six, the frequency rate or speed of mobility may be relevant as well and should be compared with other time     
1:03:101 hour, 3 minutes, 10 secondsscales such as the frequency of strategy changes or the average lifetime of a spatial cluster of individuals.     
1:03:171 hour, 3 minutes, 17 secondsDepending on the specification of the game after a transient time, one may find everything from chaotic patterns up     
1:03:241 hour, 3 minutes, 24 secondsto frozen patterns which can be expressed by a viscosity parameter. So in spatial arrays, we usually have this     
1:03:321 hour, 3 minutes, 32 secondsthing called a jamming phase transition where you have the movement of things through a space and then sometimes     
1:03:411 hour, 3 minutes, 41 secondsthey're dense enough so that at a critical parameter value they jam and that means that they go from this sort     
1:03:481 hour, 3 minutes, 48 secondsof uh you know motion to this frozen state and it's totally dependent on     
1:03:551 hour, 3 minutes, 55 secondsdensity. So if the density decreases, movement starts again. But there's usually this change in state based on     
1:04:041 hour, 4 minutes, 4 secondsthis critical parameter value of the ability to move. Uh mobility number seven, mobility may be random or     
1:04:121 hour, 4 minutes, 12 secondsdirected. So it may be success driven or it might be random. And so if it's random, then the agent isn't looking for the best payoff. They're just moving     
1:04:201 hour, 4 minutes, 20 secondsaround. If it's directed, then they're looking for a better payoff. And that's success driven. Although they may not be     
1:04:281 hour, 4 minutes, 28 secondsfinding success immediately, they're moving towards the higher level of payoff.     
1:04:351 hour, 4 minutes, 35 secondsDirected mobility may depend on the expected payoff in a certain time point iteration or it may depend on the cumulative payoff which is the     
1:04:431 hour, 4 minutes, 43 secondsaccumulation of payoffs over time over iterations.     
1:04:491 hour, 4 minutes, 49 secondsAnd then number eight, if age, birth, and death are considered, one speaks of demographic games. So you can actually     
1:04:561 hour, 4 minutes, 56 secondsplay these games with agents that are maximizing their payoff over time. Or you can have replicators where agents     
1:05:051 hour, 5 minutes, 5 secondsdie and new agents are born, which are descendants of the old agents, and they kind of accumulate this this payoff. And     
1:05:141 hour, 5 minutes, 14 secondsyou know the new agents can have different uh sets of epistemic conditions or values and they can change     
1:05:221 hour, 5 minutes, 22 secondstheir behavior accordingly and sometimes the payoffs change as well. So that's that would be a demographic game.     
1:05:311 hour, 5 minutes, 31 secondsSo they're focusing on games with success driven migration in two-dimensional geographic space.     
1:05:381 hour, 5 minutes, 38 secondsFurthermore, we will assume simple strategies such as all cooperate or all defect, no memory and no forecasting     
1:05:441 hour, 5 minutes, 44 secondsabilities. So that's so this is an example of a discrete game where you have this focal individual that's an     
1:05:531 hour, 5 minutes, 53 secondsempty circle. You have red individuals and black individuals or these red and black um pawns or agents     
1:06:011 hour, 6 minutes, 1 secondand you have an equal number of each. So you have eight ne eight neighbors of this focal individual in two different states.     
1:06:131 hour, 6 minutes, 13 secondsWe assume that all individuals prefer places that can provide a higher payoff.     
1:06:181 hour, 6 minutes, 18 secondsHowever, movements are restricted by mobility and the factors involved in implicated in mobility and the number of     
1:06:261 hour, 6 minutes, 26 secondsfree locations as one can only move to empty places and in a residential context that would be if they can afford to move to that place. So there may be     
1:06:351 hour, 6 minutes, 35 secondsplaces that have different um accessibility values and in a residential setting it would be how much     
1:06:431 hour, 6 minutes, 43 secondsdoes a place cost? Uh in this case it's just kind of like uh how accessible is that is that spot on the board.     
1:06:531 hour, 6 minutes, 53 secondsIn our model the mobility is reflected by the migration range M which can be a sim constant or as a function of cumulative payoffs. So you can move     
1:07:021 hour, 7 minutes, 2 secondsfarther if you have more of a payoff that you can either attain or have had in the past.     
1:07:111 hour, 7 minutes, 11 secondsSo movement may be specified proportionally to the distance moved and beta is a constant in this equation     
1:07:201 hour, 7 minutes, 20 secondshere. when the migration range M is restricted by the cumulative payoff, one may set migration fun the migration function here.     
1:07:311 hour, 7 minutes, 31 secondsSo this is the example here where you have a focal individual and they could have neighborhoods of different sizes.     
1:07:371 hour, 7 minutes, 37 secondsUm you have a more neighborhood of range one. A more neighborhood is every neighbor that's either adjacent well     
1:07:451 hour, 7 minutes, 45 secondsevery neighbor that's adjacent in one movement to the focal cell. It's either diagonal or cardinal direction. In a     
1:07:541 hour, 7 minutes, 54 secondsmore neighborhood of range two, you have two cells. So the neighborhood is two cells deep in all such neighbors.     
1:08:041 hour, 8 minutes, 4 secondsOkay. So that's kind of an example of what we're doing in a discrete game with a more neighborhood. And it's very similar to uh what we see in a cellular automter.     
1:08:151 hour, 8 minutes, 15 secondsAnd so the expected payoff for individual I applying strategy small I at a free location X prime within the     
1:08:221 hour, 8 minutes, 22 secondsmigration range be calculated with this function where you account for the strategies of the individuals located     
1:08:301 hour, 8 minutes, 30 secondswithin a neighborhood centered at location x prime. Here we assume that the individual can determine this value     
1:08:371 hour, 8 minutes, 37 secondsby testing a neighborhood np prime by means of some kind of fictitious play with its residents.     
1:08:451 hour, 8 minutes, 45 secondsSo in other words, you can figure out what the payoff is and what the value of doing something is by communicating with     
1:08:541 hour, 8 minutes, 54 secondspeople or you or agents or you can get us kind of a gist of what the other agents are doing by observation.     
1:09:031 hour, 9 minutes, 3 secondsSo that's the idea. You're just getting information from the surrounding environment.     
1:09:091 hour, 9 minutes, 9 secondsAll individuals are assumed to maximize the expected payoff by migrating to the place that promises the highest payoff.     
1:09:171 hour, 9 minutes, 17 secondsConsequently, the payoff at the new destination for I is expected to be this function here where we maximize for the     
1:09:241 hour, 9 minutes, 24 secondspayoff where a represents the area within the migration range M around Xi.     
1:09:311 hour, 9 minutes, 31 secondsIn our model, individuals decide to move if the expected payoff at the new position satisfies the short-term costbenefit condition here, where your payoff is greater than not moving.     
1:09:441 hour, 9 minutes, 44 secondsIf we assume that the cost of each movement is small and the new neighborhood yields a comparatively high cumulative payoff over the time period     
1:09:521 hour, 9 minutes, 52 secondsthe individual stays at that place, then the cost of movement can be neglected.     
1:09:561 hour, 9 minutes, 56 secondsBut usually there is a cost of movement that is something to account for.     
1:10:031 hour, 10 minutes, 3 secondsFinally, if two or more places promise the same maximum payoff, we assume that the individual will choose the closest one. If both the payoff and distance are     
1:10:121 hour, 10 minutes, 12 secondsthe same, then the individual will randomly choose one of the closest locations in our simulation. Since all the individuals     
1:10:201 hour, 10 minutes, 20 secondsall the other individuals also seek new places that can increase their payoffs.     
1:10:251 hour, 10 minutes, 25 secondsNeighborhoods may change quickly and the resulting payoff may fall below the expectations before the move during this     
1:10:321 hour, 10 minutes, 32 secondsfictitious play step. So sometimes you have this sort of random or you have this turnover and sometimes you don't.     
1:10:401 hour, 10 minutes, 40 secondsAnd then the question is why is that?     
1:10:421 hour, 10 minutes, 42 secondsAnd so sometimes it has to do with the payoff structure. Sometimes it has to do with where other people can go and there     
1:10:511 hour, 10 minutes, 51 secondsis this aspect of kind of figuring out what everyone else is doing, what payoff everyone else is getting. And then in     
1:11:001 hour, 11 minuteshuman dynamics like in the case of residential neighborhoods, you have this aspect of identity as well. Um and then     
1:11:091 hour, 11 minutes, 9 secondswe talk about learning. So learning allows individuals to adapt their behaviors in response to other people's behaviors in an interactive     
1:11:171 hour, 11 minutes, 17 secondsdecision-making setting. Basic learning mechanisms are for example unconditional imitation, best reply and reinforcement     
1:11:251 hour, 11 minutes, 25 secondslearning. So we want to include a learning step here. So we have this observation step or fictitious play.     
1:11:321 hour, 11 minutes, 32 secondsThen we want to learn from that. So we can use different types of kernels I guess for learning.     
1:11:391 hour, 11 minutes, 39 secondsum we might just have imitation where you just copy other people and that results in a very rudimentary type of     
1:11:461 hour, 11 minutes, 46 secondsset of dynamics. You have best reply which is okay out of these options what's my best option and then     
1:11:541 hour, 11 minutes, 54 secondsreinforcement learning where you select the best policy and there are other types of ways to do this as well. Um     
1:12:021 hour, 12 minutes, 2 secondsnow for our open- source um sustainability project we kind of have the sort of spatial structure in our     
1:12:101 hour, 12 minutes, 10 secondsagentbased models and there's no explicit spatial structure in open source uh communities except that you do     
1:12:181 hour, 12 minutes, 18 secondshave these sort of dynamics where you have um you have to kind of figure out what other people are doing and     
1:12:251 hour, 12 minutes, 25 secondscoordinate with that. Um so we use reinforcement learning. We also use active inference and there are other     
1:12:321 hour, 12 minutes, 32 secondsways you can do this as well um with personality models or with other types of models. So this is kind of one of these things for multi- aent systems.     
1:12:421 hour, 12 minutes, 42 secondsYou have to kind of figure out the best way to model it and what gives you the best set of conditions.     
1:12:491 hour, 12 minutes, 49 secondsSo they they go through unconditional imitation which is where you just copy the behaviors of others. it results in a     
1:12:571 hour, 12 minutes, 57 secondslot of hurt. You know, it overemphasizes hurting as a high payoff strategy.     
1:13:031 hour, 13 minutes, 3 secondsUh reinforcement learning is kind of a backwards looking learning behavior.     
1:13:081 hour, 13 minutes, 8 secondsI.e. people tend to take the actions that yielded the highest payoffs in the past. So if something has yielded a high payoff in the past, you replicate that     
1:13:171 hour, 13 minutes, 17 secondsin the present. This is one of the things about reinforcement learning that is maybe a problem for a problem like this and that is it doesn't allow for     
1:13:251 hour, 13 minutes, 25 secondsnew or novel solutions to occur. So if you kind of you know make the same mistakes in the past you replicate those mistakes you keep making them.     
1:13:381 hour, 13 minutes, 38 secondsIt's worth thinking that reinforcement learning was originally kind of a behaviorist model for behavior and and     
1:13:451 hour, 13 minutes, 45 secondsand they did a lot of the experiments in rodents. And so it was always about like can you remember where the food is     
1:13:531 hour, 13 minutes, 53 secondsbasically. And um so that's where reinforcement learning really kind of got uh refined. And then of course it     
1:14:011 hour, 14 minutes, 1 secondwas applied to artificial intelligence where it's very good at sort of building     
1:14:081 hour, 14 minutes, 8 secondssort of memories or building uh learned uh locations or learned things but it's     
1:14:151 hour, 14 minutes, 15 secondsnot very necessarily very good at incorporating new information. So this is kind of a point that we need to think about. Um and then of course there are     
1:14:241 hour, 14 minutes, 24 secondsother types of learning models we can use there. They talk about this best reply which is where you choose your strategy based on the expectation of     
1:14:321 hour, 14 minutes, 32 secondswhat others will do in a way that maximizes their payoff. So you're trying to kind of it's almost like a theory of     
1:14:391 hour, 14 minutes, 39 secondsmind type of thing where you're trying to figure out what other people are doing and how their payoff is working and then how your payoff should work. So     
1:14:491 hour, 14 minutes, 49 secondsyou're forecasting um other people's forecasts and then you have to have a belief about how other people behave. So you have to     
1:14:571 hour, 14 minutes, 57 secondshave sort of a theory of mind here. And so that's that's what best reply is.     
1:15:041 hour, 15 minutes, 4 secondsWe can think of other models as well for dealing with you know this this problem of an agent trying to figure out what other agents are going to do.     
1:15:151 hour, 15 minutes, 15 secondsSo in this model, players can only interact with the four nearest neighbors and adapt their strategies by unconditional imitation.     
1:15:251 hour, 15 minutes, 25 secondsAnd so this is where they run the simulation.     
1:15:291 hour, 15 minutes, 29 secondsUm, and here are some results. So in figure three, they have these 49x 49 grids.     
1:15:381 hour, 15 minutes, 38 secondsThey show the results for migration only, imitation only, and migration and imitation.     
1:15:451 hour, 15 minutes, 45 secondsSo, this is where um I guess migration is where they're actively seeking a higher payoff.     
1:15:521 hour, 15 minutes, 52 secondsImitation is where they're just imitating their neighbors. And then you have both. And when you have both, it looks like you're getting sort of the     
1:16:021 hour, 16 minutes, 2 secondsbest result. Um let's see. So let's see. They don't really mention in the legend.     
1:16:131 hour, 16 minutes, 13 secondsLet's go down to the bottom here. Um so yeah, the I guess the idea here is     
1:16:211 hour, 16 minutes, 21 secondsthat um the mix of those two things, imitation and migration are the best.     
1:16:271 hour, 16 minutes, 27 secondsHere we've examined how individual preferences can change the spatial population structure in a very simple social system considering migratory     
1:16:351 hour, 16 minutes, 35 secondsbehavior. The revealed social process can to some extent reflect the dynamics of population succession in urban areas.     
1:16:431 hour, 16 minutes, 43 secondsThis corresponds to case B in figure three.     
1:16:471 hour, 16 minutes, 47 secondsUh consider the payoff matrix for that figure and imagine that individual group one happens to be located in the neighborhood of group two. So when     
1:16:551 hour, 16 minutes, 55 secondsthey're talking about B, they're talking about this strip of results. So im     
1:17:021 hour, 17 minutes, 2 secondsmigration and imitation is here. It seems to give the best result. B actually models residential segregation     
1:17:111 hour, 17 minutes, 11 secondsin the data set that we talked about. So that's kind of what they're referring to here.     
1:17:191 hour, 17 minutes, 19 secondsUm so we can if we consider the payoff matrix that generated that figure 3B and imagine that an individual of group one     
1:17:271 hour, 17 minutes, 27 secondshappens to be located in that neighborhood of group two. For the previous residents, this may not change a lot. However, it attracts other     
1:17:351 hour, 17 minutes, 35 secondsmembers of group one who are not yet living in a neighborhood of group one individuals. This can trigger collective migration of other group one members.     
1:17:441 hour, 17 minutes, 44 secondsSince interactions between members of group one and two bring positive payoffs only from members of group one, group two will finally leave for new places.     
1:17:541 hour, 17 minutes, 54 secondsOf course, this process repeats just like the circle of population succession that we talked about earlier. One may     
1:18:021 hour, 18 minutes, 2 secondsnotice that here we do not differentiate the intention to migrate and the actual migratory behavior. So there's no intentionality that's separated from the payoff.     
1:18:131 hour, 18 minutes, 13 secondsUh in daily life, however, the movement of people is restricted by much many more factors such as wealth and time. So     
1:18:201 hour, 18 minutes, 20 secondspeople do not migrate often even if they are motivated to move. So sometimes you can't move because you're you don't have     
1:18:261 hour, 18 minutes, 26 secondsthe space on the grid. Sometimes there are other things you could model other um other factors in the mind of the     
1:18:351 hour, 18 minutes, 35 secondsagent that you could model but they don't do so here in our simulations as well migration activity after a few iterations is     
1:18:431 hour, 18 minutes, 43 secondssmall. So starting with a high migration rate due to the artificial choice of a random initial distribution the migration rate quickly drops to a low     
1:18:521 hour, 18 minutes, 52 secondslevel. Of course, other factors determining migration can be easily added to the above proposed framework of     
1:18:581 hour, 18 minutes, 58 secondsmigration games. And so then they link this back to the prisoners dilemma and the promotion of cooperation.     
1:19:071 hour, 19 minutes, 7 secondsSo this is where in figure four they show the migration only case with the imitationon case corresponding to m     
1:19:151 hour, 19 minutes, 15 secondsequals z and the combined imitation and migration case with m equals 5. In the imitation only case, the proportion of     
1:19:231 hour, 19 minutes, 23 secondscooperators is greatly reduced. So figure five is down here and it's a similar thing to what we saw for figure     
1:19:311 hour, 19 minutes, 31 secondsthree. This is migration only where m equals 5. Imitation only where m equals z. This is migration and then migration     
1:19:401 hour, 19 minutes, 40 secondsand imitation m equals 5. So you see that that's what they're referring to there.     
1:19:481 hour, 19 minutes, 48 secondsUm yeah. So in the imitation only case, a proportion of cooperators is greatly reduced because you don't know what you're cooperating with. You're just     
1:19:571 hour, 19 minutes, 57 secondsimitating other people. You don't really know what the payoff is. However, the combination of migration and imitation     
1:20:041 hour, 20 minutes, 4 secondsstrikingly promotes the level of cooperation.     
1:20:071 hour, 20 minutes, 7 secondsOur explanation is that when individuals have mobility, cooperative clusters are more likely to be promoted in the presence of invasion attempts of     
1:20:161 hour, 20 minutes, 16 secondsdefectors. We can see that in migration the migration only case cooperators manage to aggregate into form clusters.     
1:20:251 hour, 20 minutes, 25 secondsAlthough defectors attempt to enter cooperative clusters, they finally end up at the boundaries of cooperative clusters as cooperators split to evade     
1:20:331 hour, 20 minutes, 33 secondsdefectors and reagregate in new places where defectors are excluded. And so in the prisoner's dilemma, it is guaranteed     
1:20:411 hour, 20 minutes, 41 secondsthat 2R is greater than T plus S, which means that the attractive force between cooperators is mutual and strong. While     
1:20:491 hour, 20 minutes, 49 secondsthe interaction between a cooperator and a defector leads to a unilateral attractive force where T is greater than zero.     
1:20:581 hour, 20 minutes, 58 secondsWhen S is or when Z is greater than S, a cooperator replies to defectors even in a repulsive way. Therefore, defectors     
1:21:071 hour, 21 minutes, 7 secondsare less successful in joining or entering cooperative clusters than cooperators are. So, there's almost this     
1:21:141 hour, 21 minutes, 14 secondsuh attraction repulsion uh dynamic with respect to these different strategies. So when a strategy is uh     
1:21:241 hour, 21 minutes, 24 secondsstronger uh you have this attractive force. When the other factor is stronger or weaker a     
1:21:321 hour, 21 minutes, 32 secondscooperative force uh is is preferred and so they kind of get into how these dynamics work.     
1:21:441 hour, 21 minutes, 44 secondsAnd let me get to the um so let's get to the conclusions.     
1:21:491 hour, 21 minutes, 49 secondsWe have introduced the concept of migration games by considering success driven motion. Migration games can     
1:21:561 hour, 21 minutes, 56 secondseasily reproduce macroscopic style uh stylized facts at various social phenomena based on individual actions and interactions.     
1:22:061 hour, 22 minutes, 6 secondsTypical examples are population succession and residential segregation.     
1:22:111 hour, 22 minutes, 11 secondsUm, these aggregate outcomes emerge from interactions between individuals in a non-trivial way and a theoretical     
1:22:181 hour, 22 minutes, 18 secondsanalysis allows us to qualitatively understand the relation between microscopic interactions and the emergent macroscopic phenomena.     
1:22:271 hour, 22 minutes, 27 secondsFor the prisoners dilemma, we have shown that self-organized cooperative structures can promote the level of cooperation.     
1:22:351 hour, 22 minutes, 35 secondsMoreover, we have verified that any enhancement of cooperation by success driven motion is robust to different kinds of noise.     
1:22:431 hour, 22 minutes, 43 secondsWe even find that moderate noise levels can promote the cooperation level further. The underlying mechanism is mechanism is that in the migration game     
1:22:521 hour, 22 minutes, 52 secondssuccess driven motion will uh monotonously increase which means linearly the total payoff in the     
1:22:591 hour, 22 minutes, 59 secondsnoiseless system which however can lead the system into a locally optimal state.     
1:23:061 hour, 23 minutes, 6 secondsThe effect of noise can drive the system out of local optima towards the globally optimal state.     
1:23:121 hour, 23 minutes, 12 secondsAnd then they talk a little bit about the uh links to sociology and some of     
1:23:191 hour, 23 minutes, 19 secondsthe other things that um we originally talked about. It would be natural to extend migration gains in order to study     
1:23:271 hour, 23 minutes, 27 secondsthe co-evolutionary dynamics of population structure and urban growth.     
1:23:321 hour, 23 minutes, 32 secondsIn the long run, we hope this will contribute to a better understanding of planning and population dynamics in a city.     
1:23:391 hour, 23 minutes, 39 secondsSo yeah, I was kind of hoping that that would be relevant to uh multi- aent systems and how we model things and     
1:23:481 hour, 23 minutes, 48 secondssometimes we have this explicit explicit spatial component and sometimes we have this model where we want to have sort of     
1:23:551 hour, 23 minutes, 55 secondsspatial quai spatial component that allows us to model certain behaviors and then of course we have     
1:24:031 hour, 24 minutes, 3 secondsthis sort of model of I don't know if it's intelligence or decisionmaking where we might use reinforcement     
1:24:111 hour, 24 minutes, 11 secondslearning or we might replace that with other methods and to see which one works best there.     
1:24:191 hour, 24 minutes, 19 secondsOkay. Uh so that's that's all I have for that. Do we have any questions?     
1:24:251 hour, 24 minutes, 25 secondsI just um yeah it's uh it reminds me a lot of models that uh my mother is very     
1:24:331 hour, 24 minutes, 33 secondsfamiliar with from from this kind of sociological housing.     
1:24:411 hour, 24 minutes, 41 secondsUh yeah. Yeah.     
1:24:501 hour, 24 minutes, 50 secondsAny other questions or comments? I I feel very uh uncultured to do this but I     
1:24:571 hour, 24 minutes, 57 secondsI miss I miss so much of things and and the paper specifically that you just went through and I heard that I was like oh it's related to multi-ag blah blah     
1:25:061 hour, 25 minutes, 6 secondskind of words could you uh could you uh give like a brief one or two sentence     
1:25:141 hour, 25 minutes, 14 secondssummary so I can enjoy it for myself it's very selfish but yeah oh it's okay     
1:25:221 hour, 25 minutes, 22 secondsso they're doing is they're looking at these moving agents. So they're looking at agents that move around a space     
1:25:291 hour, 25 minutes, 29 secondsand they were making the analogy with socio sociological models of migration and segregation patterns. There's this     
1:25:381 hour, 25 minutes, 38 secondsfamous problem showing segregation model which shows that if you have agents of different types they tend to you know     
1:25:461 hour, 25 minutes, 46 secondshave different dynamics where they'll segregate into different areas of the board and it's supposed to be a sort of     
1:25:521 hour, 25 minutes, 52 secondsa metaphor for when we see residential segregation how does that happen and what they're doing here is they're     
1:26:001 hour, 26 minutesactually using the prisoners dilemma to model how agents make decisions and how they maximize their payoff. So the idea     
1:26:091 hour, 26 minutes, 9 secondsis that you have your agents, they're moving around this uh space and they're moving to places that maximize their cooperation and minimize their     
1:26:171 hour, 26 minutes, 17 secondsdefection. So if you're familiar with the prisoners dilemma, you can either cooperate or defect and turn in your     
1:26:251 hour, 26 minutes, 25 secondsco-conspirator. And we talked about that and I covered that. In any case, the idea is you can play these games out in     
1:26:321 hour, 26 minutes, 32 secondsspace and you can observe different dynamics and then this is linked to sort of this multi- aent problem by saying if     
1:26:411 hour, 26 minutes, 41 secondswe give the agent some set of behaviors, you know, what will they do? Will they maximize their payoff intentionally?     
1:26:481 hour, 26 minutes, 48 secondsWill they follow other people? Will they, you know, how does this affect kind of how they behave and how they coordinate their behavior?     
1:26:581 hour, 26 minutes, 58 secondsOkay. Yeah, the spatial component actually just adds this aspect of um you know you could observe those payoff     
1:27:061 hour, 27 minutes, 6 secondsmatrices in mathematics but this just shows how it you know how people sort of     
1:27:141 hour, 27 minutes, 14 secondsuh make decisions and and it gives them an impetus for displaying that behavior graphically. I guess     
1:27:251 hour, 27 minutes, 25 secondsI I I assume this was done somewhat in mind with all the mult the multi-adent stuff that I've mentioned before and the     
1:27:331 hour, 27 minutes, 33 secondssort of I I really feel like uh the way that things are going and I     
1:27:401 hour, 27 minutes, 40 secondsdon't I don't know I can I can segue this into some other things to talk about as I as I proceed but um excuse me     
1:27:481 hour, 27 minutes, 48 secondsUm I the things that are brewing right now     
1:27:561 hour, 27 minutes, 56 secondsand things that are brewing in data and direction and also really fantastic digest meeting last night um     
1:28:041 hour, 28 minutes, 4 secondsare there's just a lot there's a lot there and and uh maybe some of the folks it may be good to show them the paper that you just reviewed. We'll we'll see.     
1:28:131 hour, 28 minutes, 13 secondsOkay.     
1:28:151 hour, 28 minutes, 15 secondsSo yeah, I mean uh so yeah, why don't we get into an update?     
1:28:201 hour, 28 minutes, 20 secondsOkay. Um let me um I'll be able to say more in like 20     
1:28:291 hour, 28 minutes, 29 secondsseconds proper but um well sorry if I could just uh finish up there like these these are things that are in net logo right?     
1:28:421 hour, 28 minutes, 42 secondsYeah, I think they were I don't remember.     
1:28:451 hour, 28 minutes, 45 secondsIt seems like it would. Yeah, because it's it's like it's like um I just thinking about um Epstein's books like     
1:28:541 hour, 28 minutes, 54 secondshe's got like three books on um he's got three books on Net Logo.     
1:29:011 hour, 29 minutes, 1 secondUm and you know this is like uh I think they     
1:29:101 hour, 29 minutes, 10 secondsanyway it's like you can also model um you can also model insurgencies with this kind of     
1:29:181 hour, 29 minutes, 18 secondssame kind of migration uh you know and group group uh ID model.     
1:29:271 hour, 29 minutes, 27 secondsYeah. Um, yeah. Yeah. I think that's like some of the some of the examples that he covers.     
1:29:361 hour, 29 minutes, 36 secondsYeah.     
1:29:381 hour, 29 minutes, 38 secondsUh, I remember like we did this conference or this workshop a couple years ago where they had his work kind     
1:29:451 hour, 29 minutes, 45 secondsof prominently discussed. It was a agent based conference uh or workshop and yeah it's like that     
1:29:531 hour, 29 minutes, 53 secondsthis is the stuff where but they that's I think the impetus for agent based models was to look at like different types of problems like that     
1:30:011 hour, 30 minutes, 1 secondbut in the space have a spatial component to it. Exactly. Exactly. Yeah.     
1:30:061 hour, 30 minutes, 6 secondsYeah. It was it was it was super abstract, but like um it would be like     
1:30:141 hour, 30 minutes, 14 secondstelling you know it it was kind of getting at this point of like how quickly does a community turn,     
1:30:231 hour, 30 minutes, 23 secondsright? Um, and these kinds of these kind like like what were what were kind of     
1:30:301 hour, 30 minutes, 30 secondslike environmental or other factors that like encouraged that conversion or     
1:30:371 hour, 30 minutes, 37 secondsdiscouraged it um that they could throw in even even though it wasn't spatially you know necessarily accurate.     
1:30:471 hour, 30 minutes, 47 secondsYeah.     
1:30:481 hour, 30 minutes, 48 secondsWell, I think you Yeah. The other thing is you're modeling emergence, right? So you're modeling     
1:30:551 hour, 30 minutes, 55 secondswhat happens when a bunch of people do something. What are tipping point? Exactly. Yeah.     
1:31:011 hour, 31 minutes, 1 secondExactly. Exactly. Yeah. Yeah. Yeah. Uh I Yeah. I was It was just making me think     
1:31:081 hour, 31 minutes, 8 secondsabout how or like wondering how, you know, because those were like, you know,     
1:31:141 hour, 31 minutes, 14 secondskind of like 1970s understandings. I mean, if I if I     
1:31:221 hour, 31 minutes, 22 secondsremember right, like like I think the books were 90s, but like it was it was     
1:31:271 hour, 31 minutes, 27 secondslike very old data and and ideas. Um, I was just wondering like I wonder how     
1:31:351 hour, 31 minutes, 35 secondsthat's changed uh at least with insurgency models because like I I I     
1:31:421 hour, 31 minutes, 42 secondswanted to say that they felt like they were actually much better at predicting um     
1:31:491 hour, 31 minutes, 49 secondsI'll try and find this guy, but um he was absolutely doing mathematical modeling of um of insurgency patterns.     
1:32:021 hour, 32 minutes, 2 secondsand was getting invited to lots of conferences in like 20,     
1:32:091 hour, 32 minutes, 9 secondsyou know, like like the 2000 plus like Yeah.     
1:32:161 hour, 32 minutes, 16 secondsYeah. It is an old area like in sociology it was from like the 60s and 70s and then people use those references as kind of like the inspiration for the     
1:32:261 hour, 32 minutes, 26 secondsmore modern work. Um there are a lot of ways you can build these models that are like more sophisticated. I mean this is kind of an attempt to link this to game     
1:32:341 hour, 32 minutes, 34 secondstheory because it's not typic I mean the the lattice models don't automatically assume game theoretic structure. It's     
1:32:421 hour, 32 minutes, 42 secondsjust kind of like we run these agents and they have different rules that they use to make decisions and you can model     
1:32:491 hour, 32 minutes, 49 secondsthings that way. But in with linking game theory to this, you get this payoff structure that um     
1:32:561 hour, 32 minutes, 56 secondsyou know gives you an added dimension of doing things. And then of course you     
1:33:031 hour, 33 minutes, 3 secondsknow the spatial aspect is pretty abstract. I mean the agents are pretty abstract. The spatial aspect is also abstract because you know it's like     
1:33:121 hour, 33 minutes, 12 secondsassuming that they're sort of you know that you have a finite number of places to move or you know you have these um     
1:33:221 hour, 33 minutes, 22 secondsimperatives to move uh to different locations and you know it's not like you might find in the real world I guess.     
1:33:311 hour, 33 minutes, 31 secondsYeah. I'm gonna I'm gonna find this that I I feel like he he was bringing like time series or Yeah.     
1:33:391 hour, 33 minutes, 39 secondsUh some some distribute, you know, some some distribution in terms of frequency.     
1:33:441 hour, 33 minutes, 44 secondsUm and um yeah, anyway, I'll find it. Sorry, I dropped off there for a second. Like I'm just getting to the lab.     
1:33:541 hour, 33 minutes, 54 secondsOh, yeah. Yeah, no problem. Yeah. Yeah.     
1:33:571 hour, 33 minutes, 57 secondsAnd so you can have the sophisticated dynamics uh that are like real world dynamics. I mean you can just model kind of     
1:34:041 hour, 34 minutes, 4 secondsstochastic behavior or some sort of pattern behavior or like with a lot of real world dynamics there usually some     
1:34:121 hour, 34 minutes, 12 secondssort of uh plus process or something even more complex than that.     
1:34:191 hour, 34 minutes, 19 secondsYeah, it's you know I just um Yeah, but you know like a plus on process is so old.     
1:34:271 hour, 34 minutes, 27 secondsYeah. Yeah.     
1:34:281 hour, 34 minutes, 28 secondsLike like I I I um Yeah. Like like that would just be     
1:34:361 hour, 34 minutes, 36 secondssuch an obvious one like what did um what was the panel process um actually developed for? forgot.     
1:34:451 hour, 34 minutes, 45 secondsUh it was like um think about a ride and it wasn't     
1:34:531 hour, 34 minutes, 53 secondsuh Okay, I I'm almost I'm almost to the lab. I go I'll look this up. This is okay. Yeah,     
1:35:011 hour, 35 minutes, 1 secondwe'll have a trivia check later. I'll just ask. I I I also feel like it's it's uh just just this like my guess here     
1:35:101 hour, 35 minutes, 10 secondsthat it's also misattributed to plus but uh that's that's my bonus trivia point.     
1:35:191 hour, 35 minutes, 19 secondsUh looks like Jesse might be ready to give an update. I Yeah, I was wondering if you wanted to go over some of the stuff that we talked about in Cognition Futures.     
1:35:291 hour, 35 minutes, 29 secondsUh yeah. Um, and there's let me let me get to that cuz my mind that's like the bottom of the list right now.     
1:35:381 hour, 35 minutes, 38 secondsBut I do I am interested to talk about that and I do want to like I want to ask you about that because I want to center     
1:35:441 hour, 35 minutes, 44 secondssome points because I know I know you and I as we if you will have more to say     
1:35:521 hour, 35 minutes, 52 secondsabout that paper. So we it was a very interesting paper uh but I'll I'll I'll kind of work up to that um to my to go     
1:36:001 hour, 36 minutesthrough my week. We had Behorm. We had uh a number the the cohort the cohort     
1:36:081 hour, 36 minutes, 8 secondsmeetings are uh going very well and     
1:36:161 hour, 36 minutes, 16 secondsum they're kind of forming some clusters as well like like what people are working on in data and direction for example are     
1:36:251 hour, 36 minutes, 25 secondskind of establishing into three three major clusters. One of them is sort of the policy cluster. We're     
1:36:321 hour, 36 minutes, 32 secondsjust looking at what has happened at in at the big tech basically basically major AI labs and policy from the DoD     
1:36:411 hour, 36 minutes, 41 secondsstuff to um some of the internal policy disputes different people are looking at     
1:36:481 hour, 36 minutes, 48 secondsdifferent aspects of that. Um there is the agent agent characteristics     
1:36:551 hour, 36 minutes, 55 secondswhich kind of fits with a little bit of what we talked about today but just looking at very some specific parts. One of one of the interns Violet is looking     
1:37:041 hour, 37 minutes, 4 secondsat moral AI which is different than it's a very specific topic around um     
1:37:121 hour, 37 minutes, 12 secondsmoral operation performance and evaluation internal internal structure of the agent that way kind of very but like very cognitive science type lens.     
1:37:221 hour, 37 minutes, 22 secondsUh I think Violet has a background in positive science. That's why.     
1:37:261 hour, 37 minutes, 26 secondsAnd um another one one of the major impedances that I'll kind of just allude to and not get     
1:37:351 hour, 37 minutes, 35 secondsinto for the multi- aent um oh I want to get multi- aent meeting multi- media is     
1:37:411 hour, 37 minutes, 41 secondsAlicia's work on originally inspired by sort of community     
1:37:511 hour, 37 minutes, 51 secondsof agents or community of user human encounters     
1:37:581 hour, 37 minutes, 58 secondsum as a unique or as a particular lens on either regulation or or maintaining     
1:38:071 hour, 38 minutes, 7 secondsparticular um let's say bounds. Uh so so that's that's     
1:38:141 hour, 38 minutes, 14 secondsthat's creating sort of like this in in intra aagents and inter agent uh characteristics and and community     
1:38:211 hour, 38 minutes, 21 secondsstructures that that lead to some of the regular like what are the regulatory implications of specific things in the in those domain. So you have like policy     
1:38:291 hour, 38 minutes, 29 secondscluster, the the agent characteristic or community characteristic cluster and then also today I actually     
1:38:371 hour, 38 minutes, 37 secondsjust met with um the sort of middle ground which is a little bit in between. uh we have a cluster that is basically examining     
1:38:461 hour, 38 minutes, 46 secondsframeworks particularly at the design level but the RAF paper the reflection agency paper sort of the the anchor to     
1:38:541 hour, 38 minutes, 54 secondsthat again and the the individual was inspired by that. So we're basically looking at that and looking at other     
1:39:011 hour, 39 minutes, 1 secondthings and they have they have ongoing experience in another um role that they're in where they're using at     
1:39:091 hour, 39 minutes, 9 secondsenterprise level certain clusters of um tools. Um, and so it kind of is an     
1:39:181 hour, 39 minutes, 18 secondsinteresting hybrid opportunity of they're using it professionally in industry in certain cases and having to like teach and show other people how to     
1:39:251 hour, 39 minutes, 25 secondsuse some of them uh while doing sort of this research side uh with with us that is looking at um     
1:39:341 hour, 39 minutes, 34 secondsyou know frameworks for advising you know advising how to do designing for good uses or ethical uses     
1:39:421 hour, 39 minutes, 42 secondsor flourishing type things. So that's sort of an interesting cluster in the data and director space that's emerging.     
1:39:471 hour, 39 minutes, 47 secondsWe've had our second or third cohort meeting. We're kind of like we're a little bit behind where Google Summer code is, but we're     
1:39:541 hour, 39 minutes, 54 secondskind of the same the same general pathway of we're kind of into it now and and we're just sort of turning around the initial bend and like okay like     
1:40:031 hour, 40 minutes, 3 secondsthese things have kind of gotten legs now and they're moving and growing and and not being static anymore. Um so that's that's a very interesting thing     
1:40:111 hour, 40 minutes, 11 secondsand I'm very proud of that core. for doing that uh staying with us and getting to that that place. So that's     
1:40:171 hour, 40 minutes, 17 secondsdata and direction and um what's been interesting is the overlap between some things there and some     
1:40:261 hour, 40 minutes, 26 secondsthings here. Uh and by that I mean like the lab proper. Um by that I mean some     
1:40:331 hour, 40 minutes, 33 secondsof the multi- aent stuff. Uh Violet the Violet who's sort of the cognitive science background is um     
1:40:421 hour, 40 minutes, 42 secondsnot really is on a very short uh vacation for like you know graduation fun and stuff like that. Otherwise I     
1:40:491 hour, 40 minutes, 49 secondswould totally insert them into the cognition futures meetings proper which we can talk to soon. Uh Valer Violet's     
1:40:571 hour, 40 minutes, 57 secondssuper interested in um I I did a little preview of um cognition futures and what     
1:41:041 hour, 41 minutes, 4 secondswe've been looking at some Vela stuff from embodiment stuff some of the previous things we talked about and it was very in line with her interests um     
1:41:131 hour, 41 minutes, 13 secondsso that may be that may be um something ahead as well. Um what else do I have to say?     
1:41:231 hour, 41 minutes, 23 secondsUh I'm trying to go through the week and think about stuff. Wednesdays are very busy days for me. Um and but I'm very happy to have if we can all meet     
1:41:321 hour, 41 minutes, 32 secondsWednesday and do uh coaching future stuff then that's excellent. Um we kind of ran out of time for some things to     
1:41:391 hour, 41 minutes, 39 secondsget to the paper today, but we could talk about that a little bit soon. And the only only other thing I'll say is um digest was very nice last yesterday.     
1:41:511 hour, 41 minutes, 51 secondsUm, we had some more I don't know how to really call them. Basically, Digenous as the public facing version of Digeness as a discussion series is Avery, myself,     
1:42:001 hour, 42 minutesand Molly as these sort of co-hosts, and we talk about papers and related things.     
1:42:051 hour, 42 minutes, 5 secondsIt's it's a little bit less structured than a seminar series, but not as structured as like I don't want to call it a podcast.     
1:42:121 hour, 42 minutes, 12 secondsThat feels a little bit off to me. Uh, maybe that's just personal preference, but it's it's a it's a discussion series. the public face discussion     
1:42:211 hour, 42 minutes, 21 secondsseries. We had some new people join us uh over the last week or two uh as non-hosts, as sort of I don't want to say audience members, but something more     
1:42:301 hour, 42 minutes, 30 secondslike in-house uh people stopping by, which has been very good. What we actually we did a lot of like I think we had the most sort of     
1:42:381 hour, 42 minutes, 38 secondscoherent um what is Digi Nest? We spent a little bit of time introducing digest relative to what else is going on     
1:42:471 hour, 42 minutes, 47 secondsin the Joe Pro, the broader community at at orthogonal lab and all this other stuff. But we had a very nice time of like     
1:42:561 hour, 42 minutes, 56 secondsgoing through what it is and what we've been doing over the last six or seven months. So, and that was uh that should be recorded and recorded pretty well.     
1:43:031 hour, 43 minutes, 3 secondsSo, I'll be able to show many people who haven't been able to attend, hey, like what are we doing? What have we looked at? just some papers, but also project     
1:43:121 hour, 43 minutes, 12 secondsideas. How does this fit with everything else? Um, and I think it was a nice mutual exchange between Avery and myself. We wish Molly was there, but we     
1:43:201 hour, 43 minutes, 20 secondsmight see Molly in a few weeks when she comes to a Boston event um in July. But it was a very it's a very     
1:43:281 hour, 43 minutes, 28 secondsgood like I don't know a major sense of okay, a lot of things are taking shape more fully this week. So, uh, positive     
1:43:361 hour, 43 minutes, 36 secondsstuff to that end. I feel like there's one or two things I'm missing as well.     
1:43:401 hour, 43 minutes, 40 secondsand I can't quite remember what they are, so maybe they'll pop up, but otherwise we can jump into cognition futures and the paper for the     
1:43:481 hour, 43 minutes, 48 secondsreading group this week. Um, I don't know if you do you have things you want to just say or like I I know there was stuff you kind of wanted to say, but we ran out of time. We basically just     
1:43:571 hour, 43 minutes, 57 secondsloosely covered like the the not fun parts of the paper where they're setting up their argument and then next week we're going to kind of go into what     
1:44:041 hour, 44 minutes, 4 secondsthey're saying more. So, but uh anything you want to start with? Uh well I thought that was it was an interesting paper from the standpoint of they     
1:44:131 hour, 44 minutes, 13 secondsapproached um goals as sort of uh this I guess you could call it culturebound thing like     
1:44:221 hour, 44 minutes, 22 secondsthe idea was that goals has been approached kind of from a western perspective when we talk about goals for in cognitive science or goals in like     
1:44:311 hour, 44 minutes, 31 secondsagent systems or multi- aent systems that sort of thing and you know so if I have a goal or robot but has a goal to     
1:44:391 hour, 44 minutes, 39 secondsdo something. It's usually a you know a motivation and it has a certain type of sort of     
1:44:461 hour, 44 minutes, 46 secondsuh cach you know cultural cache in terms of how it's structured in the in the mind of the agent and so they were     
1:44:541 hour, 44 minutes, 54 secondstalking about where these tick states from um Buddhism and how they you know it's different from like what we think     
1:45:031 hour, 45 minutes, 3 secondsabout in in the west as a goal and so um that was interesting and I was thinking in terms of like reinforcement learning     
1:45:111 hour, 45 minutes, 11 secondsagain as I mentioned in the last paper reinforcement learning is kind of built from this idea of like a certain     
1:45:191 hour, 45 minutes, 19 secondsexperimental setting right and then it's been interpreted in a certain way so what happens if you know actually we     
1:45:261 hour, 45 minutes, 26 secondsextend our lens to like you know goals as being different types of things u and     
1:45:331 hour, 45 minutes, 33 secondsI think this paper kind of gets at it but it's there's a lot more I think that we're going to Yeah, like     
1:45:431 hour, 45 minutes, 43 secondsI feel I really like the paper in part because let's let's just     
1:45:491 hour, 45 minutes, 49 secondsuh put throw myself under the bus. I'm so obsessed with teiology purpose and behavior like as concepts in the 1943     
1:45:581 hour, 45 minutes, 58 secondspaper and just say oh like you know I'm I'm just so fixated on that. But what I really mean um more than that is I think     
1:46:071 hour, 46 minutes, 7 secondsit's a nice I'm curious to read where what the other folks have been doing.     
1:46:121 hour, 46 minutes, 12 secondsAvery was kind of fixated on oh where the goals come from and that's sort of like that's because that's Avery's like     
1:46:181 hour, 46 minutes, 18 secondsthing like like Avery's alistatic kinds different regulations non-uniformative interpersonal uh you know lopsidedness     
1:46:271 hour, 46 minutes, 27 secondsetc. and and that that kind of took over part of the conversation and thank you for being uh generous with that. But     
1:46:361 hour, 46 minutes, 36 secondsthere's um like some like a lot of there's a lot of things that I think are     
1:46:441 hour, 46 minutes, 44 secondsI I look forward to to next week's going through some of them more. Um and I kind of wish Amanda was there. I might try to like really seed seed the the document     
1:46:531 hour, 46 minutes, 53 secondsso that she can have some say on some things. But like yeah even even the broader sense of     
1:47:011 hour, 47 minutes, 1 secondthis sort of bringing awareness to let's say conventional reinforcement learning and it's sort of I don't I don't know if     
1:47:101 hour, 47 minutes, 10 secondsthe right word is epistemic here or ontological more so um I always get ontology always as a phrase I know what     
1:47:181 hour, 47 minutes, 18 secondsit is but like when I use it it it bothers me for some reason and so I never feel like I'm using the word ontology right but what I mean here is     
1:47:261 hour, 47 minutes, 26 secondswhen the paper pointed out um designing     
1:47:331 hour, 47 minutes, 33 secondsconceptually seeing as like reinforcement learning as you must have a descriptive layout first and then an     
1:47:401 hour, 47 minutes, 40 secondsevaluation on top of it as a as a like this is a structure to how to solve you you you create a domain you have a     
1:47:481 hour, 47 minutes, 48 secondsreward in a particular way and and you do it in this particular sequence and in     
1:47:551 hour, 47 minutes, 55 secondsa you know hierarchical sequence if you will and and it's sort of gesturing and I don't know that they did a perfect job     
1:48:021 hour, 48 minutes, 2 secondsof this but but this sort of gesturing of okay like how can we what what can we do by by having it be not as hierarchal     
1:48:101 hour, 48 minutes, 10 secondsnot as first this then that but maybe more co-developed and this idea of telkic states or you know I think there     
1:48:181 hour, 48 minutes, 18 secondswere some questions either by Avery or Amanda or you or all of us about well by telk states you basically just mean afford affordances or like what's the     
1:48:261 hour, 48 minutes, 26 secondsdifference between an afforded state or a state where you see an affordance and and a goal or a state where you see     
1:48:341 hour, 48 minutes, 34 secondsaffordances and and like is that basically itelic state like oh you've you've seen you've you perceived an aformance an opportunity in the     
1:48:421 hour, 48 minutes, 42 secondsenvironment so therefore you've entered state maybe and feel free to correct or comment on this but I think what I would     
1:48:491 hour, 48 minutes, 49 secondssay is like I just saying this now and walking around in my own city here. I'm I'm     
1:48:571 hour, 48 minutes, 57 secondsreminded of uh Johan John and sort of RIP not to him. I     
1:49:041 hour, 49 minutes, 4 secondsthink he's doing well. I think he's uh like married and has a kid and he's loving that great great life. Uh, but     
1:49:111 hour, 49 minutes, 11 secondslike RIP to Johan John's excellent like inspirational     
1:49:181 hour, 49 minutes, 18 secondsJohans John version of the conditioning group and his great lectures and the very accessible things he made about exploring some stuff um because in one     
1:49:271 hour, 49 minutes, 27 secondsof them I will always remember this sort of phrase kind of like my Nurber Weiner quotes this one I associate with Johan John and I don't know if it's he was quoting someone or said it himself but     
1:49:351 hour, 49 minutes, 35 secondsbasically uh it's not that we see differences it's we see with differences which is sort of     
1:49:431 hour, 49 minutes, 43 secondsalong the lines of um alter you know the Norbert weer alternatives quote and in this context of here like telk states as in the     
1:49:521 hour, 49 minutes, 52 secondsdifferent lenses that let like the goal the objective or the goal as     
1:50:011 hour, 50 minutes, 1 secondI think it to to very charitably get at what the paper is trying to do the goal as a means of non- hierarchically sit     
1:50:101 hour, 50 minutes, 10 secondsuating the environment and their reward or the goal or the the end state in a way that is a little more mutually     
1:50:181 hour, 50 minutes, 18 secondsinformed than you know kind of doing this broader questioning work of like what what what can classic reinforcement     
1:50:251 hour, 50 minutes, 25 secondslearning do in the way that is structured the way it's made explicit in the way that some of it's more I don't want to say information complete     
1:50:331 hour, 50 minutes, 33 secondsis maybe too strong but the way that things are a little bit more structured obviously in relation to each     
1:50:401 hour, 50 minutes, 40 secondsand what are things that are alternates to that that are more where that that doesn't hold as well and and that's what a state might specifically comment on.     
1:50:501 hour, 50 minutes, 50 secondsSo that's a lot of things and I'm curious if you have any followups to all that.     
1:50:551 hour, 50 minutes, 55 secondsYeah, I think the idea that well it goes back to what I was saying before that we basically construct goals, right? Like     
1:51:031 hour, 51 minutes, 3 secondsit isn't that a goal just is something in the in the world that's like beyond us. It's like we construct it. Even like     
1:51:101 hour, 51 minutes, 10 secondsif you're a rodent and you're trying to find food um and you you know you you try a bunch of options and you finally     
1:51:181 hour, 51 minutes, 18 secondslock onto a strategy that's always gets you food. That's a that's a policy that you select. But the goal of course is     
1:51:281 hour, 51 minutes, 28 secondsgetting food. And I mean the goal would be survival I guess. But it it's that specific goal of getting a piece of     
1:51:361 hour, 51 minutes, 36 secondscheese say is something you kind of figure out you say oh that's something that's positive I'm going to keep doing     
1:51:441 hour, 51 minutes, 44 secondsthat and you know you'll see this with like in studies of addiction where talk people talk about like you know the sort     
1:51:511 hour, 51 minutes, 51 secondsof reinforcement learning that happens there where you either like kind of keep going back to the drug or you stop doing     
1:51:581 hour, 51 minutes, 58 secondsit in there different rewards for you know that are the reward structures are involved in that. So the goal is like     
1:52:041 hour, 52 minutes, 4 secondsdriven by maybe something like dopamine signaling, but the actual thing that you're doing in the world is constructed     
1:52:121 hour, 52 minutes, 12 secondsfrom what's in the world. You know, it's a similar thing. And so that I think like in I think that was an insight from     
1:52:201 hour, 52 minutes, 20 secondsthe paper and I think that gets back to what Avery was talking about. What is a goal? A goal is something that you do in     
1:52:271 hour, 52 minutes, 27 secondsthe world. It might result from different types of drives that you have internally but externally it's going to always be based on the situation.     
1:52:391 hour, 52 minutes, 39 secondsSo right it's a bit of like top top down bottom up like externally speaking the goal and     
1:52:491 hour, 52 minutes, 49 secondsthis is this is why like imagining the al I'm superimposed in the alesthetic kind of diagram here not because I think it's the one true diagram but just what     
1:52:571 hour, 52 minutes, 57 secondsI think Avery was trying to get at even thinking about like that diagram is like you know three years old or so and even     
1:53:051 hour, 53 minutes, 5 secondsin in not that sense three years from ago and And and from more modern discussions,     
1:53:141 hour, 53 minutes, 14 secondsthere's there's a top-down element of provided a     
1:53:211 hour, 53 minutes, 21 secondsa for lack of better terms, a desire, an internal recognition that some     
1:53:281 hour, 53 minutes, 28 secondschange, something needs to be moved in in in let's say a basil effectivity type sense     
1:53:371 hour, 53 minutes, 37 secondsor like slightly above But in the maybe in the emotional sense as Fuches would say of direction setting something has to be     
1:53:451 hour, 53 minutes, 45 secondsthe internal s like uh maybe not signal but recognition if you will something     
1:53:521 hour, 53 minutes, 52 secondsinternally has has to move closer to more of or less less away from like more or less like move you know some kind of     
1:54:011 hour, 54 minutes, 1 seconda generic even scalar like uh just more or less of the thing like     
1:54:081 hour, 54 minutes, 8 secondsthere's something internally that is is seems to be a requirement in in in terms     
1:54:141 hour, 54 minutes, 14 secondsof the agents the valitional allocation right but from the top down perspective     
1:54:211 hour, 54 minutes, 21 secondsit's like the environment offers a finite uh buffet a finite     
1:54:291 hour, 54 minutes, 29 secondsarrangement of things so it's sort of like what to what end are you looking at it's like given a goal the environment     
1:54:371 hour, 54 minutes, 37 secondsoffer ings will have like a different lens or filter on it. But given, you know, it's a little bit of chicken or     
1:54:441 hour, 54 minutes, 44 secondsegg this way, I suppose. But also like I think I think to to be sympathetic to some of Avery's points is that like     
1:54:531 hour, 54 minutes, 53 secondsthe the source of the goal in terms of a gentle I like what I said about uh vocational     
1:55:021 hour, 55 minutes, 2 secondsaotment or allocation of relational valitional things in terms of like enacting a particular desire or moving     
1:55:111 hour, 55 minutes, 11 secondsrecognizing the more the basic more or less of it, Right. It it's sort of like that     
1:55:191 hour, 55 minutes, 19 secondsthere maybe is some kind of a primacy to that. Um but it depends like are you you know are     
1:55:261 hour, 55 minutes, 26 secondsyou looking at is the lens that we're trying to look at sort of the top down external here's an environment what can an agent do in it     
1:55:351 hour, 55 minutes, 35 secondsor the other I don't want to say I really don't like the word generative to use that word um um flippantly and and very     
1:55:441 hour, 55 minutes, 44 secondssort of trend trendy like right now like what is what is the you know what is the mesh between that so I don't I feel like     
1:55:521 hour, 55 minutes, 52 secondsI'm kind of stalling around a point that I want to make, but I'm not making it very well. Um, point being, I look forward to getting more deeper into the     
1:56:011 hour, 56 minutes, 1 secondwhat what they what the real meat of the paper because we spend most of the time setting up their framing of reinforcement learning. So, to be continued perhaps.     
1:56:101 hour, 56 minutes, 10 secondsOh, yeah. Yeah, no problem. Uh, yeah, I think I get what you're saying and it's uh we should follow up on that.     
1:56:181 hour, 56 minutes, 18 secondsGood stuff. Um, yeah, it's go ahead.     
1:56:231 hour, 56 minutes, 23 secondsI I think I think to to kind of ex pull it extra,     
1:56:301 hour, 56 minutes, 30 secondsnot the right word to pull this into some other to uh it's like it's like the feeling of um     
1:56:391 hour, 56 minutes, 39 secondslike a kid like a child that has food on their plate they don't want to eat and so they spread it out. That's that's really what I mean. they sp like, "Oh,     
1:56:471 hour, 56 minutes, 47 secondsyeah. I've eaten my food." And they try to just diffuse it even though it's it's not really going anywhere.     
1:56:531 hour, 56 minutes, 53 secondsum to to do to do a version of that.     
1:56:581 hour, 56 minutes, 58 secondsThere's even in terms of the um even in terms of what I was saying a few weeks     
1:57:061 hour, 57 minutes, 6 secondsmaybe months ago now about uh the common currency of navigation and navigating epistemic spaces and navigating     
1:57:141 hour, 57 minutes, 14 secondsum navigating some other stuff um in the common currencies dizzy diverse     
1:57:211 hour, 57 minutes, 21 secondsintelligence sense I think why why why the goal and telkic states     
1:57:291 hour, 57 minutes, 29 secondsand and autotellic agents like that's one of the glossery terms like autotellic agents are these things that can set their own goals and and like oh     
1:57:381 hour, 57 minutes, 38 secondsI I think some core things about all of this that I don't think the paper answers but are leading things I'm very interested are     
1:57:471 hour, 57 minutes, 47 secondsselection from alternatives and I think rather like I think like the merit of the goal like there's obviously     
1:57:551 hour, 57 minutes, 55 secondssome important things about goals goals like goals and purposes and I'm hitting the goal and and we mentioned like the     
1:58:021 hour, 58 minutes, 2 secondsthe Chan Chan Buddhist stuff and and how it's like this generative thing as opposed to this rig rig uh rigid     
1:58:101 hour, 58 minutes, 10 secondsstructure of like you have to implement this formula and by implementing the formula you're going to get the desired result stuff that's all has its place     
1:58:181 hour, 58 minutes, 18 secondsbut I think there's another lens of selection in and of itself and selection from     
1:58:271 hour, 58 minutes, 27 secondsalternatives. So like like the relationship between a gold and perception of an alternative um not just because of Norbert Weiner     
1:58:351 hour, 58 minutes, 35 secondsstuff, but like there's a fundamental and it maybe because I don't know the literature well enough, but I see     
1:58:441 hour, 58 minutes, 44 secondsthere's a fundamental like there's something about the perception of alternatives themselves, goals or     
1:58:511 hour, 58 minutes, 51 secondsnot. Like I think the difference between perceiving alternatives and you can maybe say well that's affordances but I don't know that it is in what I'm trying     
1:58:581 hour, 58 minutes, 58 secondsto say like the difference between alternatives afford like of of any kind like perception the nature of perceiving     
1:59:061 hour, 59 minutes, 6 secondsalternatives full stop affordances which are sort of environmentally tied and     
1:59:121 hour, 59 minutes, 12 secondsthen this sort of telic states or goal generation and goals as the lens by     
1:59:191 hour, 59 minutes, 19 secondswhich you're basically the uh I don't want to say generating but but the lens the the lens or the tagging     
1:59:261 hour, 59 minutes, 26 secondsthat affordances or things to do from the agent into the environment are I feel like I feel like thinking about     
1:59:341 hour, 59 minutes, 34 secondsthose three things um and differentiating them and and sorting out what I'm trying to get at     
1:59:411 hour, 59 minutes, 41 secondswith my alternative fixation is is something I'm excited to do and and I like I appreciate the paper in and of itself but I'm kind of hoping hoping it     
1:59:501 hour, 59 minutes, 50 secondswill continue some of my other aims in that end. So I I I will step away from the edge of all that and and move on to other things.     
2:00:002 hoursOkay. Yeah, it's a very good conversation. I think that's ties into the paper too. I was talking about some     
2:00:062 hours, 6 secondsof the aspects of um you know how agents are kind of determining a payoff for     
2:00:152 hours, 15 secondssomething, right? Like what is my payoff for this thing? And then that determines how I move or what my goal is. So if I     
2:00:222 hours, 22 secondsthink there's a higher payoff for something, I'm more likely to do it. Uh the drive there is to get the higher pay, highest payoff,     
2:00:302 hours, 30 secondsbut the strategy or the goal you use is different.     
2:00:332 hours, 33 secondsAnd sometimes it's wrong. So you miss your target. But yeah, and I I think to to be to be maybe     
2:00:432 hours, 43 secondsoverly charitable, if not somewhat charitable to Avery, I I' I've loved the term charitable and uncharitable because it lets me get away with a lot of things     
2:00:512 hours, 51 secondslately, and I'm enjoying that. to be overly charitable to Avery. There's an element of um     
2:01:012 hours, 1 minute, 1 secondI think some of Avery's cool work is like like when you look at things like prisoners dilemma like decision and sort of decision theory and things like that.     
2:01:112 hours, 1 minute, 11 secondsIt's it's it's I don't I'm sure there's some nuance here and I think this is unfair thing to say. So I'm being uncharitable to to     
2:01:192 hours, 1 minute, 19 secondsthat realm of stuff and overly charitable to a I feel like some of those things are     
2:01:282 hours, 1 minute, 28 secondsquite uniform like all prisoners are the same. All you know all all everybody is like it just depends on     
2:01:372 hours, 1 minute, 37 secondssort of like their relative uh you know power dynamics or like the relative structure of the situation as     
2:01:452 hours, 1 minute, 45 secondsas a sort of uh logic like the the variation is the logical positioning of the of the a of     
2:01:542 hours, 1 minute, 54 secondsthe agent relative to another agent. It is not about any internal particular qualities of the agent itself. And maybe that's I'm sure there's cases where     
2:02:022 hours, 2 minutes, 2 secondsthat's not true in some of the things, but I I feel for Avery in being being in being intentionally overly charitable to     
2:02:092 hours, 2 minutes, 9 secondsAvery. I think Avery's uh delight and exacerbation about some of this stuff is like, well, clearly     
2:02:182 hours, 2 minutes, 18 secondsthere's non-uniformity in the reward, like the the reward, the conception of the reward and the     
2:02:262 hours, 2 minutes, 26 secondsmotivation to do it. Like, so I don't know. I Let's Let's move on. I I I feel like it's going to be a a muddy pit that I don't want to get stuck in.     
2:02:382 hours, 2 minutes, 38 secondsThat's fine. Yeah, thank you for that.     
2:02:402 hours, 2 minutes, 40 secondsThank you for that update in the conversation. It was great.     
2:02:432 hours, 2 minutes, 43 secondsUh Morgan, you had something you wanted to point out about the hilarity of process.     
2:02:512 hours, 2 minutes, 51 secondsYeah. Yeah. Yeah. So, um so it's it is um It it does have its name from Pon,     
2:03:002 hours, 3 minutesnot that Pson was the first, was not the discover. Um, and Pon was modeling,     
2:03:072 hours, 3 minutes, 7 secondsinterestingly, um, uh, juries that are overruled, orur juries juries that falsely convict.     
2:03:202 hours, 3 minutes, 20 secondsUm so was was was looking it was like     
2:03:262 hours, 3 minutes, 26 secondsum looking at judicial judicial decisions in France was the was what the     
2:03:342 hours, 3 minutes, 34 secondsthe the natural phenomena that he was following. Interestingly though, the person who who actually discovered this     
2:03:432 hours, 3 minutes, 43 secondsis um is someone um I'm not going to get this name right.     
2:03:502 hours, 3 minutes, 50 secondsBortal bord.     
2:03:552 hours, 3 minutes, 55 secondsAnyway, and uh um this this particular     
2:04:012 hours, 4 minutes, 1 seconduh sounds Polish but maybe Prussian um uh was uh analyzing     
2:04:102 hours, 4 minutes, 10 secondsum the number of soldiers in the Prussian cavalry who were killed by accidental horse kicking.     
2:04:212 hours, 4 minutes, 21 secondsYeah, that's uh so so and he saw it as a real world tool     
2:04:292 hours, 4 minutes, 29 secondsfor analyzing small the the the law of small numbers. Okay. Yeah.     
2:04:352 hours, 4 minutes, 35 secondsWhich I I guess I'm I'm happy I'm happy that that's small numbers.     
2:04:402 hours, 4 minutes, 40 secondsYeah. Um, it's funny to think that like you'd have a you potentially have a nutrition rate that's like higher than     
2:04:482 hours, 4 minutes, 48 secondsyour suicide rate from like just from horse kicks. Yeah.     
2:04:552 hours, 4 minutes, 55 secondsLike like um uh Yeah. Yeah. But then also, you know, like like what people     
2:05:032 hours, 5 minutes, 3 secondsmight know this from is of course um geer and like a geer counter.     
2:05:092 hours, 5 minutes, 9 secondsUm uh which makes a lot of sense. Anyway, uh um but I did, you know, the the guy     
2:05:172 hours, 5 minutes, 17 secondsthat I was thinking about um was was at Stanford and um and of course what's     
2:05:242 hours, 5 minutes, 24 secondshe's what he's using and and this this you know he's very much like a modern a     
2:05:312 hours, 5 minutes, 31 secondsmodern um uh uh modern version of Epstein who who is it Epstein at Princeton? I forget.     
2:05:402 hours, 5 minutes, 40 secondsYeah, I think so. Yeah.     
2:05:412 hours, 5 minutes, 41 secondsYeah. Yeah. Yeah. Um uh is of course icing models, you know.     
2:05:482 hours, 5 minutes, 48 secondsOkay. like like like he's you know there is some there's some interesting things     
2:05:532 hours, 5 minutes, 53 secondsabout what um anyway uh I'll drop his um     
2:06:002 hours, 6 minutesit looks like he this is why I definitely saw him on like some podcast or some     
2:06:082 hours, 6 minutes, 8 secondsyou know news show because he's got a he's got a media page. Of course.     
2:06:142 hours, 6 minutes, 14 secondsYeah. So, like not not all mathematicians have a media page, but um reminds me of um or it seems like the     
2:06:242 hours, 6 minutes, 24 secondsthe um the the the chaotician in um Jurassic Park, you know, like like that kind of,     
2:06:332 hours, 6 minutes, 33 secondsyou know, yeah.     
2:06:382 hours, 6 minutes, 38 secondsUm anyway, just just it's I just bring it up just because like you know it's another one of these domains where     
2:06:472 hours, 6 minutes, 47 secondsobviously people really care. There there is there are some other uh um     
2:06:532 hours, 6 minutes, 53 secondsthere's some other differential equations that they already     
2:07:002 hours, 7 minutesthat they use for for war planning, you know, like or like like war simulations.     
2:07:062 hours, 7 minutes, 6 secondsSo, so it's it's like having multiple chemical processes,     
2:07:142 hours, 7 minutes, 14 secondsyou know, and and um uh happening and     
2:07:212 hours, 7 minutes, 21 secondshow to how to deal with that. Um that really only comes out of like chemical engineering. Um, I mean, in terms of     
2:07:302 hours, 7 minutes, 30 secondslike trying to handle that, uh, you know, it's like it's much more industrial. Yeah.     
2:07:372 hours, 7 minutes, 37 secondsWhich is probably a good way to describe war these days. Um uh but but but still relevant like like     
2:07:472 hours, 7 minutes, 47 secondsthere's still kind of like a uh a back and forth between that literature and     
2:07:542 hours, 7 minutes, 54 secondsand you know the kind of more sociological you know um     
2:08:022 hours, 8 minutes, 2 secondsyeah I think this is uh goes back to this discussion that we've had in different meetings on universality right     
2:08:092 hours, 8 minutes, 9 secondslike uh you you say there's process in sociology and you have this model that you can use. Then you can also use it     
2:08:162 hours, 8 minutes, 16 secondsfor other things like modeling chemical species or modeling other you know     
2:08:232 hours, 8 minutes, 23 secondsecology or and so you know the the assumption is is that they hold across     
2:08:302 hours, 8 minutes, 30 secondsthese different application domains. So I can model things in sociology, I can model things in chemistry and ecology and I can get similar relevant results.     
2:08:402 hours, 8 minutes, 40 secondsUh but of course you think about the agents and you're like well the agents are very vastly different in those systems. So it's like well why is it that we can get a result that's like at     
2:08:492 hours, 8 minutes, 49 secondsleast at the core screen level very similar and then that's where you're getting your whole body of complexity theory.     
2:08:582 hours, 8 minutes, 58 secondsUm, yeah. Yeah. Yeah. And and you know, as as a anyway, I I took the I don't know     
2:09:082 hours, 9 minutes, 8 secondsif I already had said this, but I took the Levan paper, the mathematical paper     
2:09:142 hours, 9 minutes, 14 secondsand and generated um empirical simulations     
2:09:212 hours, 9 minutes, 21 secondsusing using that same using icing models.     
2:09:262 hours, 9 minutes, 26 secondsOh wow. or like like using using uh um uh statistical mechanics models.     
2:09:332 hours, 9 minutes, 33 secondsYeah.     
2:09:342 hours, 9 minutes, 34 secondsTo generate empirical demonstrations of their theorems and propositions.     
2:09:412 hours, 9 minutes, 41 secondsUm and just as a as a you know um c can can     
2:09:502 hours, 9 minutes, 50 secondsagents do it. Um I also I also generated um uh lean proofs.     
2:10:002 hours, 10 minutesSo so generated a lean scaffold um and to to prove all their theorems     
2:10:082 hours, 10 minutes, 8 secondsum and to link a few things together that they hadn't done. I mean you you     
2:10:162 hours, 10 minutes, 16 secondsyou know by doing that you could actually find what you know like what you would need to get to the next step     
2:10:232 hours, 10 minutes, 23 secondsif you wanted to make it um if you wanted to satisfy the uh the theorem solver. Yeah.     
2:10:312 hours, 10 minutes, 31 secondsum as well as like what was missing to make the the leap to um um     
2:10:412 hours, 10 minutes, 41 secondsthe the the conjecture that they had about um large language moments. Yeah.     
2:10:492 hours, 10 minutes, 49 secondsSo there's just some interesting things.     
2:10:512 hours, 10 minutes, 51 secondsYou can find that in the um um my my quantum my quantum models you     
2:10:592 hours, 10 minutes, 59 secondsknow which which starts with you know starts talking about icing and moves to spin glass models and things like things things like that that um     
2:11:072 hours, 11 minutes, 7 secondsokay these are you know but it's like this universality where it's these these     
2:11:142 hours, 11 minutes, 14 secondsstatistical mechanics can represent lots of different concepts you     
2:11:212 hours, 11 minutes, 21 secondsYeah, it's almost like the paper the unreasonable effectiveness of mathematics. It should     
2:11:302 hours, 11 minutes, 30 secondsbe the unreasonable effectiveness of statmech.     
2:11:332 hours, 11 minutes, 33 secondsYeah. I mean like like you know somebody must have you know there's an archive paper that says that.     
2:11:422 hours, 11 minutes, 42 secondsYeah.     
2:11:442 hours, 11 minutes, 44 secondsLike that just seems like such an obvious Yeah. It seems like such an obvious I I'll I'll you know I have my     
2:11:512 hours, 11 minutes, 51 secondsrepos also produce an agent generated paper you know off the basis of their     
2:11:592 hours, 11 minutes, 59 secondsyou know like like what kind of work that they've done. Um so yeah I I I think that's what I should make the     
2:12:062 hours, 12 minutes, 6 secondstitle. I I actually did Did I Did I tell you I had the uh um     
2:12:132 hours, 12 minutes, 13 secondsSo, for the Weight Watchers stuff, um I have the title be um What would James do?     
2:12:242 hours, 12 minutes, 24 secondsYou know, who is James? Uh James the the physicist, you know.     
2:12:312 hours, 12 minutes, 31 secondsSo, it kind of started um maximum entropy, right? Right. Max and Yeah. negative interest.     
2:12:372 hours, 12 minutes, 37 secondsYeah. ET E et James. Um yeah, I think he's got the he's got the book on probability theory. Yeah.     
2:12:462 hours, 12 minutes, 46 secondsThat uh a lot of Max people Yeah.     
2:12:492 hours, 12 minutes, 49 secondsAnyway, I I I I of course was just trying to get the WWJD.     
2:12:552 hours, 12 minutes, 55 secondsUm Yeah. Yeah.     
2:12:572 hours, 12 minutes, 57 secondsBut but you know, but it would be what would a basian do is what it really is.     
2:13:062 hours, 13 minutes, 6 secondsthere. That's great.     
2:13:112 hours, 13 minutes, 11 secondsYeah. So, stay away from the back end of a horse. That's the That's the lesson here. Yeah.     
2:13:222 hours, 13 minutes, 22 secondsAll right. Uh well, thanks to everyone for contributing today and our great discussions. Uh Kavia had something     
2:13:292 hours, 13 minutes, 29 secondshere. Um yes, he had this I guess paper here. Uh I came across a startup     
2:13:372 hours, 13 minutes, 37 secondsrecently and since we sometimes discuss things related to EEG or neuroiming I thought it would be good to share here.     
2:13:442 hours, 13 minutes, 44 secondsIt tries to detect cancer and other diseases using old factory sense of dogs and BCI on them. I was just curious     
2:13:512 hours, 13 minutes, 51 secondswhether there's actually a need for this like are current methods expensive or less accurate. So speak to that.     
2:13:592 hours, 13 minutes, 59 secondsSo that guy's a member of the tower. Okay. Yeah. Yeah. Did Did the Who posted that?     
2:14:072 hours, 14 minutes, 7 secondsThat was Cavia. Yeah.     
2:14:092 hours, 14 minutes, 9 secondsOh, yeah. So, yeah, Cavia. Uh uh I I know that guy.     
2:14:152 hours, 14 minutes, 15 secondsI forget. I forget if he's a member. I forget. I mean, I think he's biotech guy. Um actually, I think this startup is based in Bangalore. Yeah.     
2:14:252 hours, 14 minutes, 25 secondsYeah. Yeah. Yeah. Yeah. So he goes he goes he goes back and forth to you know a lot of people come here to raise money     
2:14:342 hours, 14 minutes, 34 secondsyou know um but he he goes back and forth so he he was actually a member     
2:14:412 hours, 14 minutes, 41 secondsbefore um before we moved to Frontier Tower. So he he was he was you know biopunk before Frontier Tower.     
2:14:492 hours, 14 minutes, 49 secondsYeah.     
2:14:522 hours, 14 minutes, 52 secondsBut yeah, they're they're using it for cancer detection and you know, I mean, there there there are these anecdotal     
2:15:012 hours, 15 minutes, 1 secondstories and you know, and um uh about about odors,     
2:15:102 hours, 15 minutes, 10 secondsa person's odor changing with a variety of of ailments. So I think um I think     
2:15:162 hours, 15 minutes, 16 secondsParkinson's is also one where there can be a change and um     
2:15:232 hours, 15 minutes, 23 secondsum yeah but I I don't know much about like his his uh he he's definitely you know collecting data in India.     
2:15:352 hours, 15 minutes, 35 secondsYeah actually yeah there I think he has published some papers as well like showing some results. Yeah.     
2:15:452 hours, 15 minutes, 45 secondsAll right.     
2:15:462 hours, 15 minutes, 46 secondsI mean, this idea seemed pretty unique to me. So, I mean, I had not Yeah. seen     
2:15:532 hours, 15 minutes, 53 secondssomething like this happen before. So, yeah.     
2:15:562 hours, 15 minutes, 56 secondsWell, there there was another the the there was an organoid specific company called Kaku.     
2:16:052 hours, 16 minutes, 5 secondsSaid Kaku. Um, uh, I want to say Ku.     
2:16:132 hours, 16 minutes, 13 secondsYes. Um uh so this um I mean     
2:16:222 hours, 16 minutes, 22 secondsuh they they seem to have um uh I'll put this in um     
2:16:312 hours, 16 minutes, 31 secondsI'll put this in dev neuroai just because um this company has pivoted to     
2:16:372 hours, 16 minutes, 37 secondsbuilding um biomputers but their original um their original     
2:16:462 hours, 16 minutes, 46 secondsfocus was um was actually growing olfactory     
2:16:522 hours, 16 minutes, 52 secondsneurons or factory bulb to do super sensitive detection and they were trying     
2:17:002 hours, 17 minutesto sell this to airlines to do um bomb detection for sorry I shouldn't you know     
2:17:092 hours, 17 minutes, 9 secondsum you know it was just one of these things where we were like no no no no we we get the point but like what makes you think     
2:17:182 hours, 17 minutes, 18 secondsthat you can do that like like whereas like a dog a dog is very you know dog has got a it's got a great     
2:17:262 hours, 17 minutes, 26 secondssniffer right um but Kanuku was trying to do this in a dish and make a kind of biohybrid     
2:17:362 hours, 17 minutes, 36 secondsuh um system and and     
2:17:422 hours, 17 minutes, 42 secondsYeah. Anyway, and and now the the they they they Yeah. I don't know what happened because     
2:17:502 hours, 17 minutes, 50 secondslike like their entire building went up for auction like together with all the     
2:17:562 hours, 17 minutes, 56 secondslab equipment and and the auction required that you bought the whole thing. like you could only put one bid     
2:18:052 hours, 18 minutes, 5 secondson and it had to be like the whole building with everything in it     
2:18:112 hours, 18 minutes, 11 secondswhich was you know it was crazy. Um but     
2:18:182 hours, 18 minutes, 18 secondsthat's just the yeah funny stories of San Francisco tech. Yeah. Thanks.     
2:18:262 hours, 18 minutes, 26 secondsYeah. Yeah. Yeah. We, you know, it's like, it's funny because it's like it's easy, it's easy to get minus 80 fridges.     
2:18:352 hours, 18 minutes, 35 secondsYou know, these big these are really heavy. They're they consume a lot of power and they can be quite expensive,     
2:18:422 hours, 18 minutes, 42 secondsbut they're really easy to get as long as you come and pick it up. Yeah.     
2:18:502 hours, 18 minutes, 50 secondsLike because they're they've got to vacate the building and they they don't want to pay for a truck.     
2:19:012 hours, 19 minutes, 1 secondAll right. Yeah, thanks. That was a great discussion.     
2:19:042 hours, 19 minutes, 4 secondsOkay. So, yeah, thanks to everyone and um see you next week. You can see.
