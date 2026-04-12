## Meeting Recording

[YouTube link](https://youtu.be/1xcfcRznh2k)

## Mastodon thread

[link](https://neuromatch.social/@OREL/116389906845746498)

## Feature Videos

[Neuroecological Architectures](https://youtu.be/D2ISnIHrClI)

[The Latest Replication Study and its Meta-science](https://youtu.be/PfZif6BJevk)

## NOTES
Topic: Eeservoir Computing and things to benchmark against.

* organoid computing -- is a tissue doing computational work?

Cortical Labs: biological computer --> passing data to neurons, neurons passing them back.

* Phase transitions -- lots of physics, what is the computation?


GSoC mentors --> everyone has their own techniques.

LLM proposals -- 14 starred, 2 Greenfield.

Morgan: users of final spark. Organoids connected to bioelectrode array.

* applicaitons to reservoir computing. Something you can do with nonliving matter.


Quantum Computing person. Physical computation process (not neurommorphic).

* discussions around replicability has changed. 

* neuroimaging -- stats at scale. REplication crisis?

* what are the standards for simulated data? Generative coding?


ARC -- AGI project, competition. Understanding a limitation of the benchmarks we create.

* generating functyion must be good.

* rubric for proposals, how many proposals, rankings.

* Himanshu -- advise on RL stuff?

## TRANSCRIPT	
0:00	Okay, I think we're ready. So, welcome. Uh,	
0:077	who's uh I see Morgan said he's going to the hackathon today. He's going to the	
0:1414	uh tower for that. And then V says that sounds interesting.	
0:2121	So, this is the student hackathon here with the link in the chat.	
0:2828	Uh this is at Frontier Tower. This is a global neuroche hackathon.	
0:3535	Uh it's presented by Frontier Tower.	
0:3939	It's this uh 16th floor Nexus for Frontier Tower in San Francisco. Join us. Uh and then of course uh Morgan is	
0:4848	sort of the organizer there. He works for Neuroch. So he's working on that.	
0:5353	Next weekend, Neuroch is hosting the student led global neuroch hackathon with student teams from around the world	
1:001	coming together at Frontier Tower to build and collaborate together with a leaderboard.	
1:061	This hackathon is for student teams decided by their home institutions and not a public hackathon. So they're	
1:131	just recruiting people from the student clubs at McGill, Berkeley, John's Hopkins, Stanford, and Austin,	
1:221	and UC Davis. So it's uh it's like a really interesting event.	
1:281	Congratulations to Morgan for heading that up. Um hopefully they do some really interesting good work. Right. Did we have uh Di did you have any updates?	
1:371	college reading a few papers and yeah exams will start in a few weeks so like this is the lower karma phase so I'm	
1:461	just enjoying before I start studying a lot for that phase but yeah that's good looking forward to yeah Gog this summer	
1:561	it's going to be good yeah yeah so let's see um so the diva we're meeting this week uh this was I think	
2:042	meeting 12 or 13 in the year and on our uh YouTube channel for divorm	
2:122	for orthogonal web and this was uh we're going through I think some residual	
2:202	uh discussions about GOC and then we did some other things as well. So uh we had	
2:262	Shreas Baron Ashu K Morgan and myself to begin the meeting.	
2:332	Uh we went through Ashu had produced some data. She produced a new data set.	
2:392	Um it was based on something from worm base. So it was like a different way of like sussing out the u daughter cells of	
2:482	different cells. So when cells divide they divide in a binary fashion. They divide into two cells at least in C	
2:552	elegance and you get these daughter cells. And the daughter cells we can track all the cells and see elegance and we have the nomenclatures for them. So	
3:043	whenever a cell divides has two daughter cells and we know what those daughter	
3:103	cells are going to be and even more interestingly we know their relative position	
3:193	in the worm. So we know if it's going to divide in an anterior direction or a posterior direction or a left direction	
3:283	or a right direction. So we have these types of information available to us and it have it unfolds the same way in	
3:373	every worm. So this is a very fortunate part of this model organism and so this is just showing these	
3:463	different parts of this data set. So she built an identity map, she has a lookup	
3:523	table, some normalization rules, and um so that's all going to get pushed to the uh GitHub repository.	
4:024	Um then this is uh where we have some motifs from the conneto. So she was going through the developmental cells in	
4:094	this figure or in this table and then in this uh figure she ran in in a notebook	
4:164	she ran some network motifs and um displayed them here.	
4:254	And so a network motif if you're not familiar is a small connected set of nodes in a network. So a lot of times	
4:334	we'll look at motifs like triangles which you see here where you have a triangle where three cells are connected	
4:414	fully and you have this triangle and a lot of networks will have triangles in them or they'll have diamonds in them and those motifs are you know we we	
4:504	usually count up the number of motifs and it tells us something about how the network is connected and so this is a	
4:574	you know a method that people use in topological data analysis.	
5:025	They use it in community uh detection and they use it in other techniques as well.	
5:105	Okay. And then this is her uh sort of flowchart for what we were looking at.	
5:165	Um and uh this is all in service of this method hyper saggnagn	
5:235	and this is vertex convolution. And then she's going to work through this in her proposal. So this is um	
5:315	This is a nice contribution. We haven't gotten around to contributing data sets in a while. Like we've had some data	
5:395	sets in the past that we've committed to our GitHub repository. Um, and you know,	
5:455	they're usually built upon other shared data sets. So, we usually have data sets we'd like to extract for our own	
5:535	purposes. So, we have those in our GitHub repository. Um, and so that's that's something that is well	
6:016	secondappreciated I think and hopefully people will use it outside of this project.	
6:086	All right. So then talked about his proposal discovering developmental rules in the C elegance connect. This is using	
6:186	um the whip fleet connect data set and then using the C302 platform which is	
6:246	the platform that uh openworm uses for their um you know the open the openworm	
6:326	foundation sponsor the construction of C302 and it's basically uh where you're simulating the connectto of the uh C	
6:406	elegance which is 302 neurons and those 302 neurons of course each have their	
6:476	own uh bioysics, their own neurohysiology. So you're able to	
6:536	simulate that with C302 and then run whole simulations of the brain and and you know if you set the parameters in	
7:027	certain ways you can simulate different behaviors.	
7:067	uh then then he you know he wanted to use this in a developmental context which we talked about in the meeting and you know it's not the ideal tool because	
7:157	there different things h a little bit different things happening in development than the adult but and C302 is based on the adult segans but it's	
7:247	the best tool we might have for that so he tried that out and his result was you	
7:307	know it was it was acceptable it wasn't optimal you'd have to do some optimization of it. But you know, this	
7:377	is his diagram of this experiment where he took the Whitfleet conneto which is a	
7:437	conneto based on um different uh laral uh configurations of synapses	
7:527	and you know you have that for the different laral stages. Then you C302 simulation you plug that in. You then	
7:597	get neural activity from structure and then you apply this other tool called Cindy G which is a graph version of	
8:068	Cindy which is a platform for simulating neurohysiology and biohysics. So he's	
8:138	got that uh pipeline. So this is the first experiment which is the wet fleet conneto and C302 combined. This just	
8:228	shows like these different cells that were stimulated and um you end up with these voltage traces and calcium	
8:308	concentration traces and you can look at that. Um he had also mentioned that some of the the results he was getting out of	
8:388	his experiments were consistent with uh the u the rich club theory of C elegance	
8:468	contos which is that there um 302 cells in the connectto but only a subset of	
8:548	those are uh really active. they're really highly connected and they sort of coordinate	
9:019	secondthe entire conneto whereas most of the conneto is not highly connected and isn't active all the time like these the	
9:099	subset of rich club cells are and I can't remember what the rich club cells are. I believe that some of these are rich club cells but um we we just talked	
9:199	about that a little bit and I don't know what the answer is there but um that's something you could do with this platform.	
9:269	Uh so then we go on here um talking about structural versus functional development in C elegance.	
9:359	So structural development in C elegance is the uh physical wiring of the conneto. In other words, you know, if	
9:439	you have um cells and they have connections that are either electrical, which are the gap	
9:509	junctions, or they're uh synaptic, which means that there's a a connection that's	
9:579	established between two cells. They may have an immediate connection, but whether or not they're active in any one behavior	
10:0510	uh is immaterial here. What we're interested in is the structure of the connections between the cells. And so,	
10:1210	uh, in the Whitley data set or or at least in the data that they've presented in their papers, they have these	
10:1910	electroic electron microscopy snapshots of uh, C elegance, which means they're very high resolution images of C	
10:2910	elegance and from that you can see those connections. You can actually enumerate those connections. In fact, this is the way we usually sort of enumerate contos.	
10:3910	We look for different connections in microscopy images and we isolate them and then establish that two cells are	
10:4610	connected. So this is and then of course with electron microscopy you can make synapse counts. You can do um you know	
10:5510	you can actually see the synapses at the end of axons at the end of dendrites and you can actually count them up um and	
11:0411	then you know have a count for each one cell sort of communicating with another cell and you can uh look at changes in those in laral development.	
11:1511	The other type of connection connectivity is functional development or at least the other type of development is functional development.	
11:2211	This is where you actually base your conneto on activity.	
11:2711	And in neuroiming and say like humans we have that distinction between structure and functional networks. Structural	
11:3511	networks being the you know what cells are connected or in this case what um uh	
11:4211	voxels are connected and then functional development is which ones are active at any given time.	
11:4811	So that we have that in C elegance as well except we can isolate the cells that we know from calcium imaging data	
11:5511	which is where they inject a tracer and you can actually image calcium influx to	
12:0212	the cells and so you know kind of if a cell is active or not you can then make a distinction of what cells are	
12:1112	functional in what circuit at what point in a behavior. So um you know some of	
12:1712	this of course is captured when we do optogenetics. We can stimulate cells. We can also look at cells that are active	
12:2512	given that stimulation and we can get a better handle on actual activity of these networks. So functional uh	
12:3312	connections are sort of a subset of structural connections. So he's making that distinction. And so some of that is	
12:4112	where we're doing the CDG experiment. So this was on whitle. So this is where um he was able to do some other work with	
12:4912	um the neurohysiology um you know set up the simulation in Cindy G and then looked at it that way	
12:5812	and then he has these cubic spline fits which are based on the synapse count from Whitfleet and was able to simulate	
13:0713	this for different cells over time and so then he does this experiment with weak Cindy where he was able to discover	
13:1613	equations that described u the connection between two cells and or at least the activity of cells. Um	
13:2513	and this just kind of goes over that experiment. Um and that was that was a really interesting work. We had a a	
13:3313	larger discussion. I can't remember what this discussion was about but I guess it was about the experiments he was doing.	
13:4013	And then finally we have this paper um which is spatiotemporal segmentation of contraction waves in the extra	
13:4813	embriionic membranes of the red flower beetle. So this was a paper that we've been kind of sitting on but uh Susan	
13:5613	Crawford Young who's here uh she wanted she sent me this paper and wanted me to go over it. So the idea is that in the	
14:0414	embryo you have these calcium waves that go through the embryo. um early in development and it organizes	
14:1214	the um sort of cell differentiation meaning that it organizes and there are a whole bunch of waves like this in the	
14:2014	embryo. They organize how cells uh differentiate, the order in which they differentiate and oftent times uh	
14:2914	coordinate cells in groups so that they can form tissues or sometimes it coordinates them to migrate in a certain	
14:3814	direction or go to a certain place. So these uh contraction waves and ex you know these are things that they've	
14:4614	observed. uh there's a theory of differentiation waves that one of our collaborators and divorm has been	
14:5414	working on uh for a long time for decades and um this was interesting to that work as well. So that was that's a	
15:0215	theoretical uh sort of synthesis of a lot of these different waves that we see in embryionic development.	
15:1015	And so they're using this model organism, the red flower beetle, that uh you know where they're they they know	
15:1715	that these waves exist, but they're trying to characterize their function.	
15:2215	And so that's why this is an important paper. And they use this uh approach called particle image veloss	
15:3415	using cell tracking and then uh extrapolate out their velocity. So you can know how fast cells are moving and	
15:4215	what direction they're moving in a in a in in the embryo. And you can build little maps that show the arrows and you	
15:5115	know you can show basically the orientation and speed of every uh cell in the embryo if you're tracking it. And	
16:0016	sso you can build these maps where there are these you see actually that sometimes the movement is coordinated,	
16:0616	sometimes it's not. And a lot of times you get these shifts in direction and those shifts are thought to be the products of these waves.	
16:1516	So we can do this from different types of recordings two-dimensional and threedimensional plus time.	
16:2216	And this is this was a nice paper because it it really gave a lot of it really kind of broke this problem down	
16:2916	in a single model organism. They had these maps here where you see the uh the sort of the results of this PIV method	
16:3816	where you have arrows for you know that are sort of like these velocity fields and it just shows that the cells here	
16:4616	are moving in this direction and then up in this direction and this is leading to different morphagenetic events. So this	
16:5416	is leading to different things happening in those regions of the embryo setting up differentiation events and different	
17:0117	secondtype maybe like you know the formation the beginning of formation of tissues or other types of folds in the embryo.	
17:0917	And so this is just this is just going through a lot of these data. you can uh find a correspondence	
17:1717	between the speed of these velocity fields and the uh sort of time of developmental events or the onset of	
17:2617	developmental events. So here they're looking at the onset of a developmental event and then this uh function which is	
17:3417	a characterization of speed um of this in this velocity field. This is kind of showing this in detail.	
18:0418	So then you know we can do other things at the waves. We can look at wave segmentation. we can look at uh different sort of temporal aspects of differentiation.	
18:1418	It's really interesting some of the things he did here. It's very valuable data I think for thinking about these waves and seeing how you can like	
18:2318	decompose them in different ways. Um so yeah this is just really going over a lot of this work and uh this is you can	
18:3218	then map this to the embryo and see different regions you know different anatomical regions and and what's going on there at that point in development.	
18:4318	So very interesting work and then Susan had some words to say about it as well.	
18:4818	Okay so that was a divaorm meeting from this past week.	
18:5418	So yeah, um now at the beginning of next month, the beginning of May, we're going to try to start our uh open source meetings back up again.	
19:0419	So um this is going to be uh a about anong meeting on Fridays. Uh the time	
19:1319	is usually 12 noon Eastern time, which is in North America. So if you're in another part of the world, you just have	
19:2019	to figure out what what you know what the time difference is. Um if you are interested in joining, you know, we'll	
19:2919	be posting in the slack about when this is and um you know what what the topic will be. So basically it will be when we	
19:3819	select our GOC students um they will be presenting their projects during this time. We also welcome anyone to join us and they can work on their own projects.	
19:4819	Um if you're not successfully selected for GOC, you can work on a project there as well.	
19:5519	And um you know it's uh then we'll also have and this is usually something that the mentors do. Um I do this a lot.	
20:0620	Jesse does it sometimes. Sometimes Morgan joins in. Uh but anyone's welcome to talk about different topics in open	
20:1220	source. So we usually, you know, they're usually somewhat obscure topics that are, you know, something we'd like to	
20:1920	talk about and and kind of think about a little bit. We also talk about project management techniques. Um and, you know,	
20:2820	making sure that we can give people uh some professional development opportunities. So to think about some of the things you might encounter in the	
20:3620	workplace that are, you know, dilemmas or sometimes, you know, younger people	
20:4420	haven't thought about because they've never experienced it. So that's always good stuff. Um, and so we'll be starting that up around the beginning of May. Um,	
20:5520	and hopefully, you know, it'll be good a good time this year. Last year was pretty good. Um, I think we got a lot of,	
21:0321	uh, interaction and a lot of, uh, productive time out of that.	
21:0821	All right. Uh, looks like Morgan switched to his laptop.	
21:1321	Also, Sara's here. Welcome.	
21:1921	Thank you. I've been your I was listening to you.	
21:2721	Yeah. Good to hear. Good. Yeah. All right. Um,	
21:3421	did we want to share anything today? Uh,	
21:4021	um, not much. The past week I've just been focusing like I've been going through the proposals	
21:4821	also some interesting stuff on uh, are you all following the GOC mentors thread by any chance?	
21:5521	Uh, I have. Yeah. Uh there are a lot of things going on there. Yeah,	
22:0022	slot of things happening there. I just I wake up every morning and while I'm going to work, I just go through the emails there. But yeah, it seems like uh	
22:0822	I mean everything that's happening it's kind of relatable for every odd, right?	
22:1322	It's the same things are happening to everyone and uh there's like no one has	
22:2022	kind of a solution for it. Everybody just has their own techniques.	
22:2622	Um and yeah, but interesting to see everyone's kind of approaches to it as well.	
22:3422	Yeah.	
22:3422	And yeah, mostly just reviewing our proposals. There's quite a few this year.	
22:4122	So last week's just been that in work. Yeah.	
22:4722	So how many proposals did you get for the large language models?	
22:5322	Um I so I kind of starred every that uh was	
23:0023	sboth so seven and eight both have starred and kept so I mean the open source sustainability project has 14 proposals.	
23:1023	Um, out of that I think I'm not fully sure how many are for the project number	
23:1923	seven, the Greenfield project, and how many are for uh the LLM one. I think there's I know	
23:2623	two definitely that are for Greenfield so far. But yeah, I mean another thing that I think we should really do uh next	
23:3523	time for us is uh make sure that they all title their project name with the	
23:4123	exact uh project title from um from the GC ideas list with the number	
23:5023	with the project number because they everybody has kind of come up with like they've titled it innovatively but it's	
23:5723	a it's kind of a pain to filter it through and and find everything correctly.	
24:0324	So yeah, but yeah, but I would say 14 proposals for for the open source sustainability project.	
24:1024	Okay, good number.	
24:1324	I didn't count those, but I did count the green field. I think there were two for green field. Um I don't know why they have already	
24:2124	Yeah, I don't know why they said green field. Meanfield would be better actually, but whatever. Yeah, I was a little confused at first. I thought that	
24:3024	was a different orcs project and then I read and then I like what it's just named. I knew you were submitting two two projects this time. One for like if	
24:3924	you want to have any other approach and one specifically for the LA mask man,	
24:4224	but I didn't see what it was named and then I saw with all the proposals.	
24:4924	Yeah. Did you did Ara has that name or did you propose it? I have no idea where they got it from, but probably some AI too.	
25:0025	sYeah.	
25:0325	Well, yeah. Yeah. So is a large number. Yeah. Yeah.	
25:1025	Um Yeah, we had like I think 10 for G or for D.Vaorm. So, that's a lot as well.	
25:1725	So, uh compared to past years. Yeah.	
25:2025	Yeah. Well, I mean, every year like we get uh our projects usually get pretty good interest like and I don't know what	
25:2825	other projects are getting, but like usually we're in like you know I mean a few more like I think last year we had	
25:3625	like seven for D.VARM and like seven for um open source. Open source system. Yeah.	
25:4425	Yeah. Yeah.	
25:4725	Yeah. But then still I would say it's it's doubled this year, right? Yeah.	
25:5225	It's like a quick Yeah.	
25:5525	So did you find Yeah. Sorry. Go ahead.	
25:5925	Oh, did you find the rubric useful that I I sent out or? Yeah. Yeah, I did. I'm filling in that.	
26:0526	It's It's good to, you know, kind of break it all down into individual components. Yeah.	
26:1026	To be able to instead of just I did add a few more columns, but I'll share it with you.	
26:1626	Okay. Yeah. Oh, is Jess not coming? Yeah.	
26:2526	Um, I don't know. He, you know, he might come later.	
26:2926	Usually comes later, but hopefully he'll, you know, maybe he'll say something about like some of the other things he's been working on, but yeah.	
26:4026	All right. Thank you, Sara. Thank you.	
26:4626	So, I did want to talk about this. This was um a couple weeks ago, of course, we had the uh embodied intelligence workshop	
26:5526	and um there's a good time. I think there was a lot of interesting stuff at that workshop. um a lot of uh soft robotics, a lot of embodied robotics,	
27:0827	and then of course you had other talks um that focused on uh cognitive science	
27:1527	and uh like computation and things like that. Um and so this was one of the	
27:2327	things they had this year were these um uh master classes and they were basically experts in different areas who	
27:3327	would talk about their um different areas of expertise and they'd	
27:3927	put on the class kind of giving you an introduction to something and then it would be you know uh on that topic. So,	
27:4827	one of the master classes was on reservoir computing. And if you're not familiar with reservoir computing, um	
27:5627	it's a sort of a newer technique. It first was proposed in around the year 2000. And it was this idea that you can	
28:0428	do uh sort of uh maybe you know you could think of it as like an alternative	
28:1028	to uh uh different types of neural networks.	
28:1728	where you have a reservoir of nodes and you're putting together networks based on data that goes into node into this reservoir and then it comes out the	
28:2628	other end as sort of this uh uh basically this encoding or this this	
28:3328	representation. And so that's that's kind of the idea behind reservoir computing. And it actually started as um	
28:4128	something that was made for analyzing um problems that involved reservoirs, which	
28:4828	is interesting. But it's it soon evolved into this idea of reservoir computing um where you have um different	
28:5728	computational resources and you're using you know you're trying to optimize those resources.	
29:0429	Um and then of course they have reservoir networks which are network is something in network science that's	
29:1129	taken off where you use reservoir uh reservoir computing devices to build	
29:1829	networks from data. So you have your data which is your interaction matrix.	
29:2429	you put it into this reservoir which is a sort of a stochastic process and it puts together this network that you can	
29:3129	then use um to analyze things. So you have this representation that that comes out of it.	
29:3929	So it's a pretty nice little method. I know they were thinking about this in openworm at one time, how to use reservoir networks to characterize the	
29:4829	conneto of sea elegance, which would be a nice little project because it's it's a very small network that you're trying to reconstruct and um you know it's it's	
29:5829	a computational tool that doesn't have a huge amount of overhead. So it's you know plausible to build something like that.	
30:0630	So this uh was is something from the morphological computation blog. Um and	
30:1330	so this is um talking about this fresco competition which is the first international physical reservoir computing competition.	
30:2330	So um this is uh physical reservoir computing competition or fresco is the	
30:3130	world's first competition dedicated to exploring the frontiers of physical reservoir computing. We invite researchers, students, and	
30:3830	interdisciplinary teams to demonstrate how physical systems from soft materials to chemical systems to biological	
30:4730	tissues or any complex physical structures can be harnessed for computation, intelligence, and complex signal processing. So like I said,	
30:5930	reservoir computing started with actual reservoirs of liquids and you know they they were using that as sort of the the	
31:0731	metaphor. Well, people are also interested in this sort of physical computing which is where you have	
31:1431	physical systems that are you know basically the computation machine and you we talked about this with uh	
31:2331	different types of uh chemicals or you know you could maybe include organoids in that or slime molds which we've	
31:3131	talked about before. any of those are sort of ways that you can do these computations using this physical reservoir structure.	
31:4231	And so, uh, this is not just a contest.	
31:4531	It's a collaborative research initiative and completely free.	
31:5031	Uh, just so you're aware, it's not like a money-making scheme. In this emerging field, your input will help define what	
31:5731	counts as creativity, novelty, and significance. So they give a little bit about u physical reservoir computing here which is firc.	
32:0732	It's a modern machine learning approach that uses nonlinear physical dynamics.	
32:1232	So you know thinking about like a reservoir like water flow or laser dynamics or in even soft robotic bodies.	
32:2032	So you can use any kind of physical system as the reservoir and use those as computational resources. We are currently preparing a set of	
32:2932	introductory videos to explain the underlying principles and we're also preparing a few examples for inspiration.	
32:3732	So there they recommend reading this paper physical reservoir computing in robotics	
32:4532	which looks at how soft bodies and robots can be used. However, vizrc go or firec goes way beyond that. The first	
32:5432	ever physical reservoir computing uh work used a bucket of water. This is paper pattern recognition in a bucket.	
33:0233	Uh this was Chris Santa Fernando and Sam Sojaka.	
33:0733	Uh a good overview is the book reservoir computing theory physical implementations and applications	
33:1533	uh which provides a chapter on gener general reservoir computing but also some physical reservoir computing. Uh	
33:2333	finally a look at Susan Stephanie's physical reservoir computing a tutorial which is uh at this link. So these are	
33:2933	all like a life people um Susan Stephanie Croissant Fernando you know	
33:3633	work in a life or artificial life and you know this is uh consistent with this idea of sort of nonconventional computation.	
33:4733	Okay, so that's I mean this is just kind of going over this work.	
33:5333	Um and so then you know who should apply academic researchers exploring novel computational paradigms students	
34:0134	secondinterest in unconventional computation cross-disciplinary teams uh which in might include physicists	
34:0934	material scientists neuroscientists and engineers independent researchers and and enthusiasts with a passion for experimental systems.	
34:1934	Then everyone who is fascinated by physical reservoir computing. So this is just kind of you know trying to be inclusive to all sorts of different	
34:2834	fields as this would involve not just conventional computer science.	
34:3434	So this just goes through the the criterion for this.	
34:4034	Um this is a picture of I guess this is just showing an example of an acceptable implementation of reservoir computing.	
34:5034	So this is a very small example here. Um this is a crumpled piece of paper with	
34:5734	dots on it. So these are fedial markers for output extraction. Uh there's another dot that's in green. So the the	
35:0635	output extraction are in blue. There's a another marker in green for input. And so then you have the servo which serves as input actuation.	
35:1435	and then an Arduino for servo control I guess which uh does something with the uh input and	
35:2435	then it gives you outputs. So I'm not really sure the details here but this is basically a reservoir computer. Um and	
35:3235	you know this is like I guess an acceptable submission. So you have to kind of read the papers and figure out	
35:3935	how to build the computer that you want to build is that um there's a lot going on in	
35:4835	different types of computation beyond neural networks because we talk about like neural networks and large language models a lot in the group. We've we've	
35:5635	talked about a lot of other kinds of computing in the past, but just as a reminder that there are all these other paradigms out there.	
36:0736	Okay. So, I don't know if Morgan's there.	
36:2136	Yeah.	
36:2136	Yeah. I mean, you know, um I was just talking to	
36:2836	some some users of Final Spark, you know, the organoids intelligence cloud platform.	
36:3936	You know, basically they they run a bioreactor farm in Switzerland	
36:4936	that is, you know, um using organoids connected to microelectric arrays.	
36:5736	But the primary you know at the demo days or what I for	
37:0437	what they called it um user days um a lot of the applications were just	
37:1237	reservoir computing um approaches you know and that was the that was also	
37:2237	the the Um I I forget if it was I think it was	
37:3037	Indiana like like one of the first organoid um	
37:3737	machine learning examples was was also a reservoir computing you know	
37:4537	um and if if I would say you know not not not a full criticism but just like you know	
37:5437	this is something that you can do with non-living matter and and you know like like it it's an	
38:0438	interesting yeah so I think it speaks to	
38:1238	well leaving aside what it says about organized computing um it's still you know it's still an	
38:2038	interesting topic and and you know if that's one way to um perhaps you know	
38:2838	have a submission like uh yeah that's that's cool and I think I know some people who should at least look at it.	
38:3638	Yeah.	
38:3738	Um because they're definitely taking this this reservoir approach. I I just need to learn more about reservoir computing.	
38:4638	Yeah. you know, the um um you know, what's its lineage and and	
38:5538	what um Yeah. And and then like what what does	
39:0239	it make sense to compare and analyze the resourcing approaches with, right?	
39:1039	So that you can say more about what the Yeah. just so you can say more about what the system is doing. Um I don't explainable reservoir computing.	
39:2239	Yeah, I well I think the problem is is that it's not very interpretable.	
39:2639	Yeah. I mean as you can imagine because you have this big pot of hidden pot of nodes and you have hidden states in	
39:3439	there and you have to kind of extract things out of it. Um I've been doing as like I think I mentioned I I'm doing	
39:4039	this agentive coding paper that uh where I've actually taken reservoir computing	
39:4739	and then compared it with uh diffusion processes like forward and reverse diffusion. So you know that diffusion is	
39:5439	a hot topic and like machine learning and like there's this you can use those kind of as a comparison. So you have	
40:0240	this sort of physical So you have this physical or quai	
40:0840	physical process of some physical u randomization or you know so forward diffusion is where you're adding noise	
40:1740	into an image say and then uh putting you know doing reservoir network you might take an image and have it as input	
40:2440	to the reservoir and then it's trying to find the uh you ever heard of self-organized maps yeah so I I I I met Conan.	
40:3740	Okay. Oh, good. Yeah.	
40:4040	Um so that I mean it's kind of like that kind of process where you're taking a bunch of random nodes and you're kind of	
40:4740	finding the pattern from the map. And in the reservoir it's just like you have a reservoir with a finite number of nodes	
40:5540	and you're just kind of extracting the the features out from there. And then in in uh diffusion you're doing forward	
41:0241	diffusion where you're adding noise and then that's helping you to recover things because you're generalizing the model. So as you add noise into the images uh into that into that input,	
41:1441	you're sort of saying, okay, this input looks like this in an idealized way, but then if I add noise, I'm actually able	
41:2141	to see what it looks like partially oluded or with a partial mask. And then the reverse diffusion will recover	
41:2941	images from that noise. So you can recover a wider range of images if you're adding an an input into a	
41:3741	random network. um you're able to recover patterns uh based on sort of those you know that random network being	
41:4541	rewired into a feature space. And so that's kind of the way that the comparison works. You could compare uh	
41:5341	diffusion and reservoir networks and how those things yield um an analysis of	
42:0042	some sort of input data. But uh the difference of course there are a lot of differences. One of course is interpretability.	
42:0842	Um and I guess in the case of um uh uh diffusion it's higher and in	
42:1842	reservoir computing it's lower. There also some computational differences. I think reservoir computing requires more	
42:2542	computational resources. Uh I'll have to pull up that I I generated a table on this. Yeah. Just for my own curiosity. I want to know what the differences were.	
42:3542	Um it's it's interesting. Um but yeah,	
42:3842	you can that's I think the most direct comparison. Um interesting. Okay. I mean, you know,	
42:4642	like yeah, I would really love to to see that if you if you don't mind sharing because like you know, this is this is	
42:5542	such a widely used or it's practically the only technique used in organoid computing. Yeah.	
43:0143	secondThat that like you know I I I need to have more a better	
43:0943	understanding um in in order to kind of shift the conversation and and you know like uh	
43:1843	this group that's meeting this summer to you know somewhat more focused on I mean	
43:2643	potent focused on the whole range of of OI applications or kind of like issues.	
43:3243	So that's going to include actually growing them and you know things like that. Um but this is definitely one of	
43:4043	the topics that like needs to be a part of this this workshop which is you know which which it was nice to see that the	
43:4843	the organizer um is definitely coming from a you know um I mean he's definitely more of an	
43:5643	engineer but he's coming with enough uh ML background that you know he's he's	
44:0344	got some really um I think good questions about understanding what the what the reservoir computing approach is saying.	
44:1444	Um when you know the way they're using it, they want to say that the the tissue is you know we we want to say that the tissue is doing work.	
44:2444	Yeah.	
44:2544	And and that's the bit that is uh he's got some interesting ways to kind of probe that. So it' be great to put that	
44:3344	in the context of, you know, kind of some some language that I understand a little better. Yeah.	
44:4144	Or at least that's those comparisons.	
44:4344	That that's that sounds that sounds interesting.	
44:4644	Yeah. So the tissue is doing thermodynamic work. It's just the computational work is what you're saying.	
44:5544	Right. Right. Well, I mean, you know,	
44:5844	like like again, like when when um Cortical Labs, you know, which is it's	
45:0645	like this is kind of a I'm holding them to an unfair bar perhaps, but you know,	
45:1245	when Cortical Labs calling this a biological computer, um	
45:2045	it's suggesting that they're passing data to neurons neurons	
45:2745	and that's the neurons are processing them and you know and then they're passing	
45:3545	the data back or at least that would be a computer metaphor.	
45:4245	Yeah. Okay. Um, what you're describing is is,	
45:5045	you know, I would just say is, you know, is is it more is more accurate and is,	
45:5845	you know, as we know, can be done by non-living systems.	
46:0446	Yeah. Yeah. Um, yeah. There there's a metaphor there. Um and then there's this whole aspect of physi physical systems	
46:1346	compute which we did a whole bunch of work we did a whole series of like features on in this meeting about two years ago now remember the physical	
46:2246	computing thing uh that that is kind of thinking about that in a little bit different way so I mean the idea there we were talking	
46:2946	about like does the is the brain a computer is it like you know uh is there physical computing that's comparable to comp or	
46:3846	to sort of digital computing. With uh reservoir networks, you really do have like a physical computer where you have	
46:4646	things that maybe aren't bits like they don't originate as bits. You know, maybe there are things that are changes in state like in physical systems you have	
46:5646	phase transitions, right? And phase transitions are this rapid reorganization of the of the	
47:0247	of the sum of molecules in say like a liquid going from water to a solid or a	
47:0947	liquid to a solid. And so um in that case you know you have this mass reorganization of things. You can look	
47:1747	at that phase transition is say like um maybe hardness of state of the medium and you have this shift. It's kind of	
47:2547	like a sigmoidal where you go from like a liquid and then all of a sudden to a solid and it's very sharp. Um it's not a	
47:3347	step function but it's kind of like a segue or it could be a step function.	
47:3747	Now what we will do in a what we have to do to convert that to bits is to say everything in either side of the phase	
47:4447	transition is either a zero or a one. So if it goes from a zero, which is a liquid, to a one, which is a solid,	
47:5147	that's a a bit that's flipped. Or if we go the other way, it's a bit that's flipped. But that process is kind of	
48:0148	secondobscured. We can't I mean, we could I guess we could uh we could capture that with a a digital computer, but we'd	
48:0948	always have to state that in bits. We'd always have to convert that to like a binary state or maybe a turnary state.	
48:1648	if we're lucky. But that doesn't describe a lot of that process. So there's a lot of process that gets assued and you know um a physicist would	
48:2648	be horrified because it's like you know you're you're obscuring this whole process. It's interesting. Um the same	
48:3348	thing with organoids. You have this these uh you know graded signals and you have a bunch of stuff in parallel and	
48:4348	you have networks where you know the networks are these cells that are connected and then the cells are in a state right and the state is just really	
48:5148	kind of abstracted from a lot of complex interesting biopysics going on and	
48:5948	that's that's kind of maybe the problem here is that you have this you know you You say computational work, it's like well computation,	
49:0849	what level of computation? Um what do we mean by computation in the first place? Yeah.	
49:1449	Um there's yeah that whole literature on like unconventional computing.	
49:1949	I can't remember how they're dealing with those things. I mean it'd be kind of interesting to do a deep dive into that to see how they frame those kinds of questions.	
49:2849	Absolutely right. Absolutely. It reminds me the um	
49:3549	uh sorry I'm still on the way to the flower but like like there's a company	
49:4549	there's a company um based in LA.	
49:5049	It's funny because the CEO is like like a super fan of Carl Fristen.	
49:5649	Oh yeah. Um but he's uh uh and they they finally got	
50:0450	aired up, you know. Um, but uh uh I'm blanking on the name of the company,	
50:1150	but it's like it's EXO something and and I think I think part of it is coming	
50:2050	from I I I was just going to say like is the this is like a former quantum computing	
50:2850	person who um who uh has started this compute company,	
50:3750	not quantum, but it's got some sort of thermodynamic	
50:4550	um it's like it's like exo something.	
50:5450	Yeah. And and I I wonder if it's like somehow trying to use a similar, you know,	
51:0851	e extra physical process, physical computation process.	
51:1351	Um it's is he's is building it as like a super efficient, you know, not not neuromorphic,	
51:2251	but um um yeah, I I'll find it when I get to the tower.	
51:2851	All right. Yeah, that's fine. Uh yeah.	
51:3251	So yeah, there are like even if you go back to Fineman, he talked about a little bit about like physical computing	
51:3951	and how you compute physics and this is a classical physics not necessarily quantum physics because quantum computing of course is its own paradigm.	
51:4951	Um we don't want to borrow from that for classical processes. So you know it's kind of like what do we how do we characterize	
51:5751	uh you know physical computing in that way. Um so yeah I don't know I'm going to have to look into that uh more in	
52:0552	more detail and you know it' be an interesting set of things. I think I actually mentioned	
52:1252	uh some of Fineman's work on it uh back when we did that uh physical computation series of features like two years ago.	
52:2352	We have a post on our medium about it um if people are interested in going back and reviewing that. Um but yeah, just a	
52:3252	series of discussions we had on different papers, different things. It ranged from philosophy to physics to	
52:3852	computer science to neuroscience. And it's just kind of thinking through all these uh questions that were interesting	
52:4552	to our group, our group, but also uh more inclusive to different debates in the scientific literature.	
52:5652	Okay, thank you Morgan for that uh discussion.	
53:0053	sSo this is something else. I think Morgan posted this in the slack	
53:0653	and um this is a paper from the u there's this uh	
53:1453	it's on scientific replicability lead author on this paper is Brian Nosk and so um this uh article is titled	
53:2353	investigating the replicability of the social and behavioral sciences. is very ambitious because there's a lot of social and behavioral science out there.	
53:3353	Um but basically they're doing a metaanalysis on the field and they have this uh interest in replication and	
53:4253	replicability. And so when we say replicability what are we referring to?	
53:4853	Um so basically in science one of the things that we try to do when we do	
53:5553	experiments is we would like to first of all have a controlled experiment where we have a	
54:0354	hypothesis and then we set our experiment up so that we can test the hypothesis without too many confounds. So the idea	
54:1254	being is that when we have a hypothesis about like say um if I move my mouse	
54:1854	across the screen um you know I'm doing something with my hand there's a	
54:2654	motor control involved and if I perturb that motor control in different ways for example if I have a distractor light in	
54:3354	the uh peripheral periphery of my visual system it will slow down my ability to move the cursor across across the screen	
54:4154	because I'm distracted visually by that thing and it disrupts my sensory motor integration and so it's my movement is	
54:5054	slower and you could you know have a control where people aren't distracted by the light uh a experimental condition	
54:5954	where people are distracted by the light and then have different levels of distraction so that one is obviously	
55:0655	going to have an effect and maybe one is has a minimal effect and you you predict all this in advance. You design the	
55:1455	experiments so that you can test the the relationship very in a very isolated way	
55:2155	and you try to eliminate confounds which are things that will maybe could be other potential causal mechanisms or or	
55:3055	um effects and you try to um minimize the interactions of different variables. So	
55:3855	you just want to have the two variables or you know uh that that you're testing.	
55:4355	So you have a very clean if you have a very clean experimental design first of all your effect will pop out and you'll be able to see the effect.	
55:5355	You can use statistical testing to um confirm that effect and then of course you have an effect size which depends on	
56:0256	the number of people who are in your experiment.	
56:0556	And then of course you have this idea of replication. So if I design a good experiment and I have this result,	
56:1356	I can you know do all sorts of different uh statistical tests. I can even do causal modeling and say this is you know	
56:2256	the effect and it's real. Another way to know that it's real is to to replicate that result. To do like 10 experiments	
56:3256	and have them all basically point in the same direction or have 10 different groups do the same experiment. And why do you want to use different groups?	
56:4256	Because different groups will do the implement this slightly differently.	
56:4756	They might use different variations on the light. they might use different variations on uh the the cursor speed	
56:5456	and and so forth. So you have if if the effect holds up across these different	
57:0157	secondum variations then you know that the result is robust. So that's the idea behind replication. We'd like to see	
57:1057	replication also because if we're trying to apply our findings to um you know	
57:1757	applications like if we want to build this into a computing paradigm like a user interface we want this to be something that is robust. So if we say,	
57:2857	you know, we want to build this result into a guey, we want to make sure that this isn't just some result that's not	
57:3557	um very well supported and is maybe the case only about a quarter of the time because that would be, you know, it would result in a a bad product.	
57:4557	So replication has a lot of uses in um you know in the behavioral sciences but also in other areas where we do	
57:5357	experiments and you know the thinking is of course is that physical systems or physics you can replicate things very easily or	
58:0258	maybe in chemistry because those are physical systems and we have a very high degree of characterization of those	
58:1058	systems and quite frankly they're not as complex as social systems at le or so the thinking goes. So, a lot of people	
58:1858	who do biological experiments and social science experiments will say that um you know I you know I you know I can use	
58:2758	experimental techniques but they're not going to be as replicable as those in physics and chemistry simply because	
58:3458	it's harder for me to isolate the different um variables involved, not get	
58:4358	interactions and not get confounds because you know In biology and in social science, you have a lot of	
58:5058	sometimes you have uncharacterized variables, sometimes you have a lot of uh things that are interacting.	
58:5858	Um, and it's it's just really hard to isolate those things and then also make that um that experiment useful for	
59:0759	understanding the system as a whole. So we can do experiments in biology and social science that are very contrived.	
59:1559	They have very low what we call ecological validity or the ability to transfer those results to	
59:2559	um to reality. You know what does that mean in reality? What does that mean in like a real social setting or real	
59:3259	psychological setting or a real biological setting?	
59:3759	And a lot of times our experiments are just that. they're they're sort of uh artifacts of	
59:4459	you know that that don't have a lot of application outside of their own domain.	
59:4959	So this is kind of where we we sit with this. So the idea is is that replication	
59:5859	um we kind of assume that replication is gold standard in the social sciences because of the factors that I mentioned	
1:00:051,	it's hard to get experiments to replicate. So this has led to something that they call the replication crisis which is that you can do all these	
1:00:131	experiments and get these results and um if you go back to the literature to try to reproduce a lot of experiments	
1:00:221	sometimes a lot of famous experiments you can't replicate them and you know this is a this is a thing that is sort	
1:00:301	of the basis for this science reform movement that you might see Brian Nosk of course is very interested in this.	
1:00:391	There are other people as well which is that we need to improve science by finding better ways to do science,	
1:00:451	finding better ways of standardized science. Uh because we want to have more replicable social science, more replicable biological science.	
1:00:551	Basically, where we can't replicate something, we should try to rethink how we do experiments, how we do data	
1:01:021,	,	analysis so that we can make things more replicable.	
1:01:061,	And of course then there's this other school that says well we really can't do that. We just have to go with what we have and you know that's just kind of	
1:01:141,	our heristic and and you know that's the best we can do and I wouldn't worry about it too much. So um you know there	
1:01:221,	there it is a debate. So when they present this stuff it's interesting and it's I think useful for understanding	
1:01:311,	where we stand in the science in the social and biological sciences. But it's also very much um you know maybe we	
1:01:401,	can't expect to use experimental methods and really expect to have highly replicable results. Maybe uh the best we	
1:01:491,	can do is like quai experimental methods that gave us give us indicators of what things are you know effects in social	
1:01:591,	science. if we have a intervention for example there's certain effects that we should expect and it's not going to be very easy to replicate those across	
1:02:081,	different labs or different contexts. So that's kind of where we wrote this. Um so let's go over the abstract of this	
1:02:161,	and then a little bit into the paper. So as as uh as meta-cience what they're doing is they're taking a bunch of	
1:02:241,	different results from different papers that have been published and they're re-evaluating those and they want to	
1:02:311,	 understand kind of as a whole where we sit, how replicable are claims that get published. And sometimes they're very	
1:02:391,	famous results. And sometimes we base a lot of our theories on them or a lot of	
1:02:451,	like um uh popular sort of science popular ideas about how the brain works for example on them. So you know there	
1:02:541,	have been a lot of examples in psychology where um you've had famous results that have everyone has kind of	
1:03:011,	secondhung their hat on and then they turned out not to be replicable. And so this is a little bit of a a ding on um some of	
1:03:091,	the co cognitive science techniques that have uh come out of the cognitive revolution. So in any case, let's get into the abstract.	
1:03:191,	Pursuing replicability or independent evidence for previous claims. So you do an experiment and you	
1:03:261,	publish your results and you observe the effects there and then some other group tries to do the experiment again and	
1:03:351,	they either get an effect and maybe it's of a different size because sometimes you don't get the same number of	
1:03:431,	subjects. Sometimes those subjects exhibit variability. Sometimes your environment is a little bit variable and so you can't expect them the uh results	
1:03:521,	to always be exactly the same but you should get them in the same direction.	
1:03:561,	You know if they get a positive result you should also get a positive result and you should be able to do this uh in	
1:04:031,	any kind of setting. So like again if I want to confirm some finding I just simply run the experiment for myself and	
1:04:121,	I get that result. And as we know we can do that actually we have a version of this in computer science where you run if you run things in a container.	
1:04:211,	The whole concept of that is that I will write a program execute it on my machine and then if you execute the program on	
1:04:291,	your machine you might get a different result because your machine is is different parameters has a different uh process or whatever but if I put it in a	
1:04:381,	container I can always run the the the program exactly the same way and get the same results.	
1:04:461,	So there is a version of this in computer science. Um, unfortunately we can't containerize social and behavioral science experiments or biological experiments.	
1:04:561,	So that's that's that's something to keep in mind.	
1:05:001,	sSo this allows us to have generalizability which you know in machine learning we worry about with	
1:05:071,	training models but in a lot of these experiments we want to make experiments.	
1:05:131,	We want to design experiments so that the results are generalizable to you know any kind of replication and eventually even to application domains.	
1:05:251,	So here we attempted replications of 274 claims of positive results from 164	
1:05:321,	quantitative papers published from 2009 to 2018 in 54 journals in the social and	
1:05:391,	behavioral sciences. So a wide range of different findings uh published recently. So this is well 2009 to 2018	
1:05:481,	is well within this sort of science reform era. So this is like you know if you go back to like the 80s and 90s or	
1:05:561,	in the 70s um you can go back there and find a lot of experiments where people were totally not thinking about this.	
1:06:031	 You know they were very um not thinking about replication too much. Sometimes they were, but a lot of times they	
1:06:091	 weren't. And you know, you might you might say, I'll take some experiments that were published back then and and reinvestigate them, and lo and behold,	
1:06:181	they don't replicate the way I expect.	
1:06:211	Well, you know, that's maybe unfortunate, but it's not something that where people are actively engaged in	
1:06:281	this conversation. But with from 2009 to 2018, this conversation was going on. So, you know, you might say, well,	
1:06:361	people were, you know, just trying to run their experiments and live their lives, but the idea being is that, you know, people were aware of this problem and it still persists. So,	
1:06:471	and I will say that the uh no group and and some of these other groups, you know, they have a specific sort of agenda for this. It's not like they're	
1:06:561	picking on people, but they do have this idea that, you know, uh science needs to be done a certain way. So um this this	
1:07:041,	is and they want to sort of advance their own research in um science reform.	
1:07:091,	So there is that aspect of it. So you know I'm not saying that like people are just being intentionally dense about	
1:07:191,	science reform. It's just that that's the the that's where we are in in this in this uh debate.	
1:07:251,	Um so they they had a pretty good sample of different studies to look at.	
1:07:321,	Replications were high powered on average to detect the original effect size uh with a median of 99.6%	
1:07:401,	used original materials when relevant and available and were peer-reviewed in advance through a standardized internal protocol.	
1:07:491,	Replication showed statistically significant results in the original pattern for 154 of 274 claims which is around 55.1% of studies surveyed.	
1:08:031,	Uh so this is you know maybe not great.	
1:08:061,	Um it's it's over half but it's only about a little over half. Uh so this means that you know if you have	
1:08:141,	experiments that you take out of literature at random uh only a little bit more than half of them replicate. And that's you know	
1:08:221,	again this is using sort of the you know as close as we can get to the original experimental design.	
1:08:331,	So um you know that is kind of disappointing maybe	
1:08:401,	and for 80.8% of 164 papers which I don't know how they get to 80.8 eight of	
1:08:461,	a p you know point eight of a paper. Um but I think this is just a waiting scheme uh weighted from replicating	
1:08:541,	multiple claims per paper. So this is where you know they make more than one claim from or maybe more than one	
1:09:021,	experiment in a paper and you're kind of looking at this in its totality. So um we're really kind of at and when we do	
1:09:111,	that we actually get a little bit below 50%.	
1:09:141,	So actually if you think about this as an at chance endeavor like if we had like if we ran a thousand experiments	
1:09:221,	and we got 50% of them that replicated that's kind of at chance it's not but you know that's one way to think about	
1:09:291,	it. Um there probably reasons why this exists. Um I don't think people are doing a poor job of experimental design	
1:09:381,	but um they never really kind of get into that in these papers. they always kind of just show that there's this lack	
1:09:441,	of replication. Um, and you know, it the implication is always that there's a	
1:09:511,	problem in science in in science. I think probably a lot of this is going to be like psychology or something	
1:09:591,	psychology adjacent. Um but maybe it's just again the complexity and the nature	
1:10:071, 10	of social and behavioral sciences that it's very complex and it's hard to kind of	
1:10:141, 10	isolate phenomena in a way that sort of like physics.	
1:10:191, 10	Okay. So um we observed modest variation in replication rates across disciplines and you know depending on the discipline it ranged from 42.5%	
1:10:301, 10	to 63.1%.	
1:10:321, 10	So you know depend you know maybe some disciplines it's really hard to replicate in others it's maybe easier to replicate but really you don't get	
1:10:411, 10	anywhere near 100% and you don't necessarily get anything near 0% either.	
1:10:461, 10	So um and then some estimates though had a high uncertainty. So you know again we're making an estimate about this um	
1:10:561, 10	based on just this sample of things and it's I guess a representative sample um but you know we're we're hovering around 50%. Kind of around that area.	
1:11:071 	The median Pearson's R effect size was 0.25 for original studies and 0.10 one zero for replication studies.	
1:11:171 	Uh which is of course you know there are replications in the literature and of course we expect replications maybe from	
1:11:251 	what we're saying here to not be as robust as the original studies. So again, you know, we're finding this,	
1:11:321 	we're kind of confirming this idea that um the original studies are not uh great in terms of replication, but the	
1:11:411 	replications aren't great either for obvious reasons.	
1:11:461 	Um 13 methods for evaluating replication success provided estimates ranging from 28.6%	
1:11:531 	to 74.8% which is a median of 49.3%.	
1:11:591 	uh some decline in effect size and significance is expected based on power to detect original effects and	
1:12:061 	regression to the mean because we replicated only positive results. So you might be able to replicate a negative result, but that's not that hard to do.	
1:12:151 	I mean you do a poor job of like uh setting up the experiment and oh I got a	
1:12:211 	I got a negative result too you know you have to run the experiment to get a negative result. I guess technically but	
1:12:291 	um so you know having the positive result that's sort of the thing that requires you to have	
1:12:371 	good experimental design. A negative result doesn't necessarily require that.	
1:12:421 	We observe that challenges for replicability extend across social and behavioral sciences illustrating the importance of identifying conditions that promote or inhibit replicability.	
1:12:531 	And again, this is assuming that you can do this in the same way that we kind of have a mental model for.	
1:13:021	 So, you know, again, why do we care about replication? Well, one of the aims of science is to discover regularities,	
1:13:111	statistical regularities and sort of structural regularities.	
1:13:151	And one way to do that is to say if I run an experiment and I get a positive result, if I rerun that experiment, I	
1:13:231	should get a similar result and I should always get that result if this is a phenomena that's true or that's that's	
1:13:301	real. If it's not real, I might get a positive result once and then a negative result again and maybe I keep getting a	
1:13:391	negative result then maybe I get another positive result. And this is not trivial because basically when we do a statistic	
1:13:471	when we assess statistical significance that's essentially what we're doing. If we had say 20 experiments,	
1:13:561	uh we should expect if we have say like um a 95%	
1:14:021 	percentile um criterion um that we should expect 19 of those	
1:14:091 	experiments to be uh positive to be successful to show the effect and one experiment that does not. So depending	
1:14:181 	on our significance criterion, we should expect out of those 20 experiments a certain proportion of those to	
1:14:251 	replicate. I mean that's essentially what we're saying when we do like uh statistical significance. We should say for 20 observations	
1:14:341 	a vast majority of them should be in this direction and there may be some in the other direction. But the reason why	
1:14:421 	we have the uh significance criterion is because we want to say that like for the most part this is true. There are always exceptions.	
1:14:531 	So you know people have talked about um statistical significance before. So there's this whole side debate about	
1:14:591 	like the um the value of the looking at statistical significance and you know	
1:15:071 	how people do things like P hacking to try to like uh make something statistically significant that otherwise	
1:15:151 	wouldn't be. So there are all sorts of problems there as well. But the idea is that we want to discover these regularities.	
1:15:231 	So we want to be able to replicate our results so that every time we do an investigation we can get similar results and it should	
1:15:321 	be reliable and if we especially if we have something that that is um an application we want to make sure that it hap that it's a a repeatable result.	
1:15:441 	And so then you know they they talk about this replication crisis and how a lot of published work will claim well it	
1:15:521 	doesn't claim replication it's just that they're published as positive results and a lot of times people don't question that and they kind of run with the	
1:16:011 	secondresult and so this is a problem that we have um especially in in things like cancer biology where the stakes are	
1:16:081 	pretty high right we need to be if we have a clinical trial there it's actually pretty important that we can replicate it and a lot of times we can't	
1:16:171 	and and I have thoughts about that um where you know it's it's like we're	
1:16:251 	dealing with very complex systems and a very in fact with cancer it's very um	
1:16:321 	u it's highly variable in terms of how you observe these things and so there are a lot of things there that kind of	
1:16:391 	work against really good experimental results but anyways is um so they get into this. Popular	
1:16:471 	explanations for the low observed replication success rates include under reporting of negative or inconclusive evidence for claims,	
1:16:561 	high sampling error from small samples,	
1:16:581 	a measurement error due to unreliable measures coupled with a statistical threshold that serves as a publication	
1:17:061 	filter. So there's this idea that like sometimes when we uh to get things published we need to achieve a certain	
1:17:151 	statistical threshold of a p value. And so if we can't get to that sometimes	
1:17:221 	people will try to get to that using um you know less than rigorous methods to	
1:17:281 	get there. Um and this this is something that is maybe a problem because a lot of	
1:17:351 	publications won't publish negative results and if they don't publish negative results of course some people don't get published and there's a whole	
1:17:431 	incentive structure that is immobile in this case. So you know this is where you	
1:17:501 	have to publish positive results you can't publish negative results. So there's pressure to get positive results even if it means sacrificing replic	
1:18:001 	sreplicability or you know just simply doing something more nefarious like excluding samples that don't meet the	
1:18:091 	you know that don't meet the statistical threshold.	
1:18:121 	So that's kind of one of the points there. Low rigor and quality control and research design and measurement.	
1:18:201 	So if your experimental design is poor or you don't, you know, control for all of your compounds and questionable	
1:18:281 	research practices that inflate the likelihood of obtaining positive outcomes.	
1:18:331 	These factors are compounded by a research culture that rewards novel and interesting findings and discourages error correction. Again, these are just	
1:18:411 	these incentives that are misaligned with the ideals that we would like.	
1:18:471 	Replication failures are not necessarily due to the original findings having low credibility. Low replication rates can also be due to false negatives or early	
1:18:561 	design replications, selecting only positive results for replication and differences between original and replication studies that are initially perceived as unimportant.	
1:19:071 	More broadly, there are conceptual challenges in deciding what a replication of a previous finding is and how to assess whether replication	
1:19:161 	attempt succeeded. So we sometimes, you know, even just using like meta-cience.	
1:19:221 	Um, you know, maybe meta-cience the problem is meta-cience. Maybe the problem isn't in the literature. Um, but	
1:19:291 	I, you know, that's something that is a little bit more that that's maybe requires a meta science. Um but I think	
1:19:391 	really um you this is just kind of an interesting kind of way to think about our results that we read. Whenever we	
1:19:481 	read a result you know is this something that is um you know can we we trust this result	
1:19:551 	as replicable or is this a one-off result that is interesting but it's not going to we really have to think through this problem somewhere. Um,	
1:20:051 	interestingly I know there are a lot of people who uh critique benchmarking in computer science. So benchmarking kind	
1:20:131 	of suffer from the similar kind of problems we see here where you have two programs and you benchmark their performance and a lot of times people	
1:20:221 	are trying to optimize performance down to like a couple decimal places and you know how how um effective is that	
1:20:321 	really? I mean, you can game those kind of statistics pretty easily. Um, and so,	
1:20:381 	you know, sometimes people will,	
1:20:421 	you know, um, want to show that their model is better performing than another model. So, there's a temptation there to sort of gain the system for your model.	
1:20:521 	Um, there are a lot of there are a lot of challenges in in benchmarking as well. And um I haven't gone and found a	
1:21:011 	secondcritique a good critique of this but um maybe I'll do that next time.	
1:21:071 	So they go through this study here. This is uh table one papers and claims selected by replication attempts by discipline.	
1:21:171 	So they cover business, economics, education, political science, psychology, sociology,	
1:21:251 	uh and then the total at the end. So we have um claims selected and replications attempted. So they've selected a number	
1:21:341 	of papers with claims um and then they have that number there.	
1:21:391 	So they're sampling. I think in psychology they have 950 in education they have 445 and there's a	
1:21:461 	range of uh number between that papers eligible for replication uh means you know which papers can we	
1:21:551 	actually replicate the claims with so that's a subset of those papers with multiple claims they're a smaller number	
1:22:031	 with that have multiple claims in them or testing multiple hypotheses and then papers with a single claim volume which	
1:22:111	is the balance. So the so the papers eligible for replication those are the ones that will be the replications that they attempt.	
1:22:211	So not all of the claims can be replicated or they don't think they can or they won't. So they do a subset of	
1:22:281	these and I don't know what the criterion for deciding that was. Um but that's you know that that is up to the	
1:22:351	uh the team that that did the paper. So um they had papers with replication	
1:22:421	started papers with replication attempts completed total replication attempts of claims. So that's a smaller subset still	
1:22:501	and then unique claims of replication attempts. So this is how they kind of divided this out. They took a bunch of papers from different fields. They examined their claims.	
1:23:011	secondThey then took each claim.	
1:23:041	actually they took each paper and they then looked at the claims and they did they figured out which ones they could replicate and then they did the	
1:23:131	replications um and they ended up with a much smaller subset of of um replication of times completed.	
1:23:241	So this is, you know, again where we have a bunch of things in the literature, we kind of winnow it down to things that	
1:23:321	are sort of lowhanging fruit or easy to actually do in an environment. So we're getting like the kind of the simplest	
1:23:381	experiments or the the most maybe the most important experiments. And so there is this selection bias here uh to be	
1:23:481	aware of that is we're not testing every claim. We're testing a subset of claims.	
1:23:531	And um yeah, so I mean, you know, there there might be something to say about that where um you're kind of testing the	
1:24:021	things maybe that are the least replicable or maybe they're the most replicable. It's not really clear. Um so	
1:24:101	that's basically what we have here. So you're making um and if you look at the numbers actually um I don't think	
1:24:191	there's a huge sort of bias towards any one discipline. I think you know the I	
1:24:261	think psychology that's a little bit more replicable or maybe you you had more attempts in	
1:24:331	psychology than in other areas. So you had papers with replication attempts completed 58 in psychology you had	
1:24:421	started with 950 papers with claims in education you have 13	
1:24:491	versus 58 and for education you had 445 papers so there's a little bias I think	
1:24:561	for psychology and because the team is I mean Brian Nosk's a psychologist and the team probably knows psychology better this is probably why you have this bias.	
1:25:081	So again, you know, this is not like the experiments are behavioral experiments.	
1:25:151	So they're not going to be widely wildly different from the typical psychology experiment. So that's kind of what why	
1:25:241	um you know just just something to be aware of here. Okay. Um so for table one	
1:25:321	uh representativeness across disciplines was maintained during identification and extraction of claims because we use	
1:25:391	random sampling strategies. Most of the change in representativeness occurred owing to the non-random process of	
1:25:461	selecting and starting a replication study. So education and political science decreased in relative proportion of the sample and psychology increased.	
1:25:561	Okay, that's again what I just talked about. Compared with the original sample of papers, the proportion of completed	
1:26:031	attempts of unique claims was within 3.5% for economics, education, political science, and sociology. And more notable	
1:26:121	variation was observed for business and psychology.	
1:26:151	Representativeness of replication attempts was relatively steady by year compared with the sample papers.	
1:26:221	Um we selected papers and attempted replications in two phases with 139 of the completed replications occurring	
1:26:301	from papers selected during the first phase and 25 from papers selected during the second phase. Replication success	
1:26:381	rates were similar between the first and the second phase.	
1:26:431	Okay. U this then is figure one which is the replication success rates across 13 binary assessments for papers.	
1:26:531	So what is this? Um this is where we have binary success measures um and for different things and then	
1:27:021	proportion successfully replicated according to measure percent.	
1:27:071	So these are the different sort of ways in which uh I guess things are assessed.	
1:27:161	Um so you have this measure of success.	
1:27:201	You have metaanalysis at the top which is where you know I guess there are these different types of mechanisms or	
1:27:281	or or different types of measures that they're binning things into when they're looking at how replicable those measures are. So meta analysis comes out on top.	
1:27:381	Then you get small telescopes, basian metaanalysis,	
1:27:441	replication effect and prediction interval, subjective interpretation, replication base factor.	
1:27:521	Then skeptical p value is down the list. Sum of p values is down the list.	
1:27:561	Correspondence test is right with the p values. Uh b factor is down below. and then the original fact and replication	
1:28:051	 confidence intervals. So the confidence intervals are at the bottom along with base factor. So I'm not quite familiar	
1:28:131	with these success measurements, but it's interesting that um sometimes baze	
1:28:201	and basian stuff comes out on top or near the top and baze factor comes out low. confidence interval comes out low	
1:28:291	and then correspondence tests which are usually um pretty weak statistical um	
1:28:361	relationships come out with p value measurements. So I'm I you know I'm not an expert at these in these different	
1:28:451	measurement techniques but it's kind of interesting how those are distributed.	
1:28:511	Okay, so they talk about this a little bit more. Um, this problem highlights a challenging problem or this project highlights a challenging problem.	
1:29:001	sReplication success metrics can be applied only to methods that meet their assumptions. So again, sometimes people	
1:29:061	use metrics where the assumptions aren't met by the data. So this is something that again is maybe a problem in	
1:29:151	replication is that people use different metrics or these metrics incorrectly and that can always because metrics always	
1:29:231	have assumptions built in. So this is a problem which you know you would think be corrected in peer review but oftent	
1:29:301	times is not. People will give justifications for using a metric that maybe they shouldn't be doing. Okay. Um	
1:29:401	and so um in figure one we present 13 replication success metrics. Some are necessarily binary assessments of	
1:29:471	replication success or failure. Others are simplified to provide a binary assessment for comparison.	
1:29:551	Okay. Uh across metrics replication success rates ranged from 28.6% to 74.8%	
1:30:031	with a median of 49.3%. of that number and 49.3%.	
1:30:081	The observed variation highlights the impact of different assumptions underlying each approach. For example, the highest estimate of 74.8%	
1:30:181	for the metaanalytic combination of the original and replication evidence provides strong evidence of success	
1:30:251	because it includes original studies that provided evidence of success and these tests are not independent of the original evidence.	
1:30:331	Variation in the observed replication rates are affected by both the assumptions of the binary assessment and the subsample for which the metric could be used.	
1:30:431	Figure two presents correlations between each pair of binary assessments or replication outcomes which both methods can be applied. So that's this	
1:30:521	figure here. Um and then this is where we have these different metrics kind of compared to one another and then we have	
1:31:011	secondthis distribution of all 144 correlations.	
1:31:051	So this is just kind of thinking about these correlations between different metrics and how these are distributed.	
1:31:121	So um you know uh let's see correlation values are to the right of the diagonal	
1:31:201	over here. Um and so what does he say about that? Uh figure two presents correlations. Spearmman	
1:31:291	correlations were positive and relatively high with some exceptions.	
1:31:341	For example, analysts almost always interpreted success on the basis of statistical significance as reflected by a correlation of 0.90.	
1:31:441	Whereas measures that use confidence or prediction interval show relatively strong correlations with each other. And so this is where again we have this	
1:31:531	different types of measurements having um you know uh sometimes they're they	
1:32:001	slead to high replication, sometimes low replication, sometimes specific types of measures um are interchangeable	
1:32:101	but also if you're using other measure other types of measurements they don't aren't as consistent. So sometimes you know you'll have a replication where you	
1:32:191	use say like a confidence interval and another one where you use a basian method and you're going to have a different result.	
1:32:281	Is that due to the experimental design? Maybe not.	
1:32:321	Should we do that kind of test? Perhaps because sometimes it can tell us about how robust a result is.	
1:32:421	And so again this discrepancy in different methods using different methods for the uh different studies is	
1:32:511	uh partly because they are treated because they treated replication outcomes both smaller and larger than the original outcomes as failures to	
1:32:591	replicate. So there is this aspect of statistical testing um in their effect on replication.	
1:33:091	Okay. So the discussion here is about half the findings from a sample of social behavioral science papers	
1:33:171	published between 2009 and 2018 replicated successful with variation and success estimates across 13 binary assessments and effect size comparisons.	
1:33:291	variation in replicability across disciplines was modest with replication rates between 42.5 and 49%	
1:33:381	um on for fields that had more than 20 replications. These findings are consistent with the cumulative evidence	
1:33:451	across systematic replications um and they illustrate that there is substantial uncertainty in estimating replicability.	
1:33:551	Okay, so there's some conceptual,	
1:33:571	methodological, and inferential challenges to assessing replicability.	
1:34:031	Uh, conceptually, it can be challenging to attempt a replication. Strictly speaking, there's no such thing as an exact replication. Of course, we want to	
1:34:121	get it as close as possible, but we can't always replicate the exact conditions under which the data were collected.	
1:34:201	Um there's different there always differences in units, treatments,	
1:34:251	observations, and settings. Researchers must make decisions about how to conduct a good faith replication on an original claim.	
1:34:351	Um, so for example, should a present-	
1:34:371	day replication of a 2009 US study of political behavior that use President Obama as a stimulus, use Obama again or	
1:34:461	the current US president or use the leader of the participants nation? So if you study people in another country, are	
1:34:541	they going to respond the same way as the people within the country where the the leader is from? So this again is	
1:35:011	secondlike something that you do a study and it's interesting for what you want to find but then it might be very highly	
1:35:091	contextual and replicating that study may not hold. So you know but this is interesting because a lot of times we	
1:35:181	will take a study like this and extrapolate out the effect. So you you you might say something of you know does	
1:35:261	this result say something about the context of the United States and President Obama or does it say something	
1:35:341	about more generally uh you know electorates around the world and their respective leaders? It may be very	
1:35:431	constrained to the US context. It may not.	
1:35:471	So this is a problem that you have with studies when they're set up and studies when they're replicated.	
1:35:541	Um another thing we have to worry about is is to whether or not the theoretical commitments are correct.	
1:36:021	So sometimes we have a theory and you know this is something that um the theoretical commitment might be	
1:36:101	wrong where you have sort of uh you interpret your result in a certain theory and of course it's the wrong theory to interpret it with.	
1:36:201	Um yeah so then methodologically it can be challenging to determine how to measure	
1:36:271	replication success. So again we have these these measures of these metrics that they use but again um you can't use	
1:36:351	a single metric universally and a lot of times it depends on the measurements that the original studies used and	
1:36:441	that's that's there are a lot of problems there.	
1:36:481	Then inferentially it can be challenging to determine whether original and replication studies produced the same outcomes. Each of the replication	
1:36:571	assessment criteria strengths and weaknesses and may be based on different assumptions.	
1:37:021	 For example, metrics combine original replication evidence that are not independent tests and have relatively low sampling error.	
1:37:111	Uh these tended to suggest the highest success rates. So again um tests that	
1:37:181	are not um okay uh these tended to have suggest the highest success rates they might be	
1:37:261	useful only when it is safe to assume no selection or publication bias and the emphasis is on cumulative evidence. So	
1:37:341	again um different types of studies may be more amendable to replication	
1:37:421	um and different types of ways to study replication are only useful in certain	
1:37:501	contexts. So you don't want to assume that studies were free of selection or publication bias when they were and you	
1:37:581	don't want to select a study that has selection or publication bias.	
1:38:041	Okay. In summary, the question did it replicate can be difficult to answer.	
1:38:081	Fortunately, the answer for any given study does not matter much in the long run. Research is conducted on a study bystudy basis. Replicability is	
1:38:161	established by a cumulative body of evidence. So sometimes when we have a hypothesis or a theory, it's not so much	
1:38:261	that it's whether it's replicable or not. It's that if you know there are hundred studies in a certain area	
1:38:341	and they all yield different results, we can kind of figure out what the right answer is by looking at the accumulation of results. In other words,	
1:38:441	if a study is um published and it turns out that it's not true, that the result	
1:38:501	is maybe a one-off, it doesn't really hold to true theoretically,	
1:38:561	then we should be able to detect that by looking at a hundred different studies and looking at the direction in which they point. If another if a stud is	
1:39:031	pointing in the other direction, then maybe we just are skeptical of it and we don't need to worry about replication	
1:39:111	because we can kind of figure out the correct direction of what these findings suggest.	
1:39:201	Okay, I think that's enough on that paper. Um I don't know if Morgan had anything to say about that since he posted it in the	
1:39:271	chat. Um interesting to hear his feedback on it. Well, yeah. I mean, obviously, you know,	
1:39:361	it's um it's super important to to talk about these issues. you know, um Brian	
1:39:441	and the the the center there has definitely been a big part of, you know,	
1:39:521	I'd say helping move that conversation forward in productive ways and um	
1:40:001	syeah, so it's uh	
1:40:061	uh I'm still I like uh greetings greeting students and things right Yeah.	
1:40:131	But um uh yeah, like uh	
1:40:201	no no no major um	
1:40:291	comments on it, but you know, just like so valuable and so um	
1:40:371	um just nice to see how the I forget They um I don't know if you've ever seen a podcast of decoding the gurus.	
1:40:481	No, I've not seen it.	
1:40:491	Uh I highly recommend I mean you know it's like some people who um	
1:40:591	you know it's like two like I think one's an anthropologist and one's a psychologist but like like a methods psychologist you know.	
1:41:091	Yeah.	
1:41:101	And um anyway, it's like they they just had a recent um	
1:41:191	yeah, they they're usually doing what they say, you know, decoding the gurus.	
1:41:241	So, it's kind of like taking apart people and make outlandish not outlandish claims, but like science	
1:41:321	claims, but they kind of take like those things apart. But they recently had a	
1:41:401	researcher who was very much just talking about how discussions around rep replicability	
1:41:491	have changed since like you know over just 10 years and like you know in a good way and	
1:42:031	yeah I remember that like when people started talking about this it was like people were very defensive about I mean, as you might imagine, um, you know,	
1:42:111	people were defending their turf. They thought that they, you know, done their due diligence and then there these people who say, "Well, look, we have this crisis."	
1:42:191	And so, yeah, but I think there's been more acceptance more recently about like the need to be sort of rigorous in this area.	
1:42:311	Yeah. Yeah. Yeah. Yeah. For for sure,	
1:42:351	for sure. Um and uh uh you know there's like kind of a second you know	
1:42:441	conversation of you know neuro imaging people who are doing kind of like more	
1:42:521	statistics at scale which but it's but it's still still very similar. to like like a lot of overlapping	
1:43:001	sconcerns and issues even though like the conversation's a bit more sometimes is a bit more technical,	
1:43:091	right?	
1:43:111	Yeah. Uh yeah. I mean like there are a lot of areas of science you could say	
1:43:171	that yeah there's a I mean the term replication crisis always implies like kind of oral crusade or something. So	
1:43:261	maybe it's not a crisis, but definitely it's like we don't have good community standards for these things. We I mean we	
1:43:341	we are beginning to have those and that's one of the the impeti uh behind um different types of toolboxes and you	
1:43:431	know virtual machines and things like that that we've talked about with um replication neuroscience where you're	
1:43:501	building tools for people to more easily standardize their results. So you're not just kind of home brewing a solution every time you need to do something.	
1:43:591	You can make sure that you have good control over those things. And um I think that that improves the the the the	
1:44:091	results because it just like you know you you go through this pipeline, you're verifying everything and it's not a huge cost to the labs doing the work.	
1:44:221	Yeah. Yeah. Yeah.	
1:44:251	All right. Like I said, the whole another kettle of fish are benchmarks in computer science. So that's	
1:44:331	and I know that like we think that benchmarks are sort of a lot easier than like we say you know well social science	
1:44:421	is pretty hard and it's got a lot of interaction but like in computer science surely we can just kind of get these	
1:44:491	benchmarks and they should be you know pretty easy to to understand and calculate. But again, you know, you have	
1:44:561	these problems where you kind of make up your own methods or you um maybe want to see something. There's a there's a sort	
1:45:041	of confirmation bias that if something is true, you want that to be true. So that's what happens.	
1:45:111	Um but again, you know, like um I think it is like really about well, it's about community standards,	
1:45:201	but a lot of times it's also about cost to the researcher. So sometimes these replication to ensure replicability it's	
1:45:281	expensive. It's like you have to spend the time you have to spend sometimes the money to do these things and not everyone can not every group has the the	
1:45:361	resources. So it just makes it if you make it easier for them to comply it's not that hard to do you know.	
1:45:461	Yeah.	
1:45:481	I would say, you know, I think I think ARC is is an example, you know, the AGI	
1:45:561	ARC um is an example where	
1:46:031	 like our our kind of own understanding is is also a limitation of the benchmarks that we create.	
1:46:131	Yeah.	
1:46:151	like like um you know	
1:46:221	we we can't um we can't define good intelligence tests for these models	
1:46:301	um when we have trouble creating them for ourselves or like right	
1:46:381	creating creating uh unbiased benchmarks there like you know what I mean?	
1:46:461	Yeah. Yeah. And it's like if we don't understand intelligence very well, we can't make good benchmarks.	
1:46:531	Yeah. Yeah. Yeah. I mean Yeah. I mean I I see it I see it in doing all this	
1:47:001	sagentic coding where you know like the I see it in the issues of of testing on synthetic data.	
1:47:101	Oh yeah.	
1:47:121	because you know it's like like it can look complex. It can it can look um	
1:47:211	you know to the eye or you know these other things but like it's really just as good as your you know generating	
1:47:291	function right and you know like you know so if you give it some real data and suddenly	
1:47:371	everything's off it's like you've obviously not got something in your synthetic uh generator	
1:47:451	Um right yeah that's that's a great conversation	
1:47:531	to kind of continue. Um so um we have time for one more thing.	
1:47:591	Um so I I did want to go over a paper really quickly that um is of interest maybe to ecological psychology types and	
1:48:091	probably I think probably Jesse would enjoy this. Um this is a paper that's now published in um this book	
1:48:171	neurocognitive foundations of mind. This is a neuro ecological architecture situating situated cognizing systems.	
1:48:271	This is Luis Favlla who we've talked about before in cognition futures and some other contexts. Um	
1:48:351	let me go over the abstract and then we'll go into the paper. Um so uh the ab	
1:48:421	so this is a p uh this is a chapter in this book. Um and so the abstract read	
1:48:491	situated approaches to cognizing which is defined as distributed embodied and extended cognition or you know different	
1:48:581	ways of doing cognition basically have exerted an immense influence on the cognitive and psychological sciences.	
1:49:071	So distributed cognition is often thought of as different agents doing cognition and then kind of coming	
1:49:151	together in groups. Uh embodied cognition of course is doing cognition with reference to a body. So the the	
1:49:241	brain or the agent is in a body and that body conditions how that cognition is expressed. Then extended cognition is	
1:49:331	extending cognition into the world through artifacts or through the environment.	
1:49:381	Um so this is you know these are things of course that are situated in a context um that are hard to separate from their	
1:49:461	context. So and you know when we talk about experimental replicability if we want to make an experiment like	
1:49:531	this replicable we don't need to just um replicate the the sort of the highly contrived experimental conditions but we	
1:50:011	secondneed to put people in a similar environment. So this is the whole sort of debate between very controlled	
1:50:081	experiments in the lab and these more naturalistic experiments where it may not be as highly controlled but you're	
1:50:151	in the right uh in the right environment in the right context and so that's maybe what matters more	
1:50:221	since such accounts typically do not prioritize neurobiology their impact is felt far less in neuroscience. So, uh, when we talk about	
1:50:311	extended and embodied and and distributed cognition, usually we're not thinking about this in terms of neuroscience. We're thinking about this	
1:50:381	in terms of like behavior. And in cognitive science, it's usually like some behavioral observation where you	
1:50:481	put people on a in a airplane cockpit and you look at how they uh make choices on on a a control panel and then you	
1:50:571	record their responses. and there's no neuroscience necessarily involved in it.	
1:51:021	So this is where we want to sort of unify um ecological psychology with neuroscience and have this neuroecological architecture.	
1:51:131	The influence in ecological psychology which stresses the role of ecological information which is of course things	
1:51:201	like uh flowing visual cues and other types of dynamical systems type inputs	
1:51:271	or things that lead to dynamical systems from the environment. We have this role of ecological information that	
1:51:351	dynamically unfolds at the scale of organism environment systems.	
1:51:401	that's critical for cognizing and this is something that is um you know something we need. A substantial	
1:51:481	criticism of this approach concerns the apparent absence of the brain's contribution to cognition in so far as other situated approaches	
1:51:561	remain influenced by ecological psychology. Such criticisms undermine other approaches as well. The primary	
1:52:041	aim of this work is to present a framework for integrating neuroscience with situated approaches namely the	
1:52:111	neuroecological nexus theory or next. So this is the theory he's proposing here.	
1:52:171	To be successful uh next must both maintain the core principles of ecological psychology and provide	
1:52:251	testable hypotheses concerning the neurobiological contributions to intelligent organism environment events.	
1:52:331	The latter is proved provided by contemporary neuroscience work on the neural manifold hypothesis	
1:52:401	uh in hypothesizing that situated cognition can be explained by interactions among environmental or	
1:52:481	ecological information and classes of neuronal manifolds. Next provides a step towards a more complete understanding of	
1:52:561	mind. One that spans the cognitive and psychological sciences as well as the neurosciences.	
1:53:031	So this is something that unifies two different areas.	
1:53:071	This is the preprint. Um and so it gets into a little bit of history here. Uh situated approaches to	
1:53:151	cognition generally adhere to the view that intelligence systems are always embodied and embedded. So this is	
1:53:221	something that you know again when we talk about situated cognition which is usually a sort of a shorthand for these	
1:53:301	sort of naturalistic experiments or a theory that we use to interpret naturalistic experiments. We're usually	
1:53:381	dealing with intelligence systems. It could mean the, you know, a human operator or um, you know, an animal in a	
1:53:461	in a naturalistic environment or it could mean an AI system or an automated system in a body in a naturalistic	
1:53:551	environment or something like that. So it could be like a a robot in a naturalistic environment or an AI in a	
1:54:021	naturalistic environment like an autonomous vehicle or something like that.	
1:54:081	And so we have to start thinking about these theoretical constructs like embodiment, embeddedness, example.	
1:54:171	Uh though there is variety and controversy in how the term is used as a starting point embodied refers to the idea that cognition	
1:54:251	requires a body to occur. So embodied means you need a body whatever a body is. And so a body could be like you know	
1:54:341	our bodies where we have relations between the different parts of our bodies. It could be like a vehicle. So a	
1:54:431	vehicle has specific movements. It has specific control imperatives. And so you know those you have to operate within	
1:54:511	that that um context. So you have a vehicle let's say moving around an environment. It can get to different	
1:55:001	spoints by, you know, selecting different control mechanisms like steering or acceleration	
1:55:071	or reversals and they create different out behavioral outputs. And so these	
1:55:151	behavioral outputs then	
1:55:441	So these different behavioral output sort of determine what the intelligent behavior looks like. So if you only have	
1:55:511	a subset of control me control imperatives available to you, your you know it doesn't matter what your	
1:55:581	intelligent behavior is sort of deducing from the environment. The outputs are the important part and so the outputs	
1:56:061	 might limit significantly what you can actually express as a behavior.	
1:56:121	So this is embodiment and this is of course important there whole conference as an embodiment in say like robots and	
1:56:201	automated systems but it's easier said than done. There are a lot of open questions and embodiment and how to characterize that visav these intelligent controllers.	
1:56:311	In a more specific sense, this means that there tends to not be a sharp distinction between cognition and non-cognition in the body and related	
1:56:401	the sensory motor processes are important for cognition. So, um we need to really kind of we can't just think of	
1:56:471	the body as kind of a conduit for intelligence or for cognition. The body actually interacts with intelligence. So	
1:56:561	like you acquire information through your eyes or through your hands and you don't require information	
1:57:041	um you know through your stomach you know it's it's not the conduit and but there's an interaction there. So	
1:57:111	sometimes your visual acuity is controlled by your central nervous system and you know there connections	
1:57:201	between the body and mind that need to occur here and this is true of any kind of a controller with any kind of u body.	
1:57:281	So it could be like a autonomous vehicle controller. It has to have interactions with the vehicle. And in fact, we have	
1:57:371	that in in autonomous vehicles with sensor systems across the vehicle.	
1:57:431	In a more specific sense, this means there tends not to be a sharp distinction between cognition and non-cognition.	
1:57:511	And related, the sensory motor processes are important for cognition.	
1:57:561	There is a spectrum and how weak or strong these positions are. At the weaker end of the spectrum, cognition is primarily a brain event. But the brain	
1:58:041	areas associated with the body's sensory motor processes play important roles in causing and enabling even higher forms	
1:58:111	of cognition such as abstract reasoning and language. At the stronger end of the spectrum,	
1:58:171	cognition is not primarily a brain event with the body's non-neural structures and processes causing and con	
1:58:251	constituting even those previously mentioned higher forms of cognition. So this is like where we talk about weak	
1:58:321	and strong embodiment. Uh weak embodiment is where we kind of think of the brain as being within a body. Yes.	
1:58:421	But the brain is doing most of the work and the body is just there as sort of an instrument of the brain. In strong	
1:58:491	embodiment, the body is actually doing most of the computation or it's balancing out with the brain or the	
1:58:561	controller. So you know this is like a debate within embodiment that's important here because you know you have	
1:59:041	to deal with that you know the role of the body basically.	
1:59:081	So this is where we think about embodiment and it's important to kind of ve be very specific what we mean by embodiment.	
1:59:171	Okay. So um and then we have to go back when we think about ecological psychology we need to go back to	
1:59:241	behaviorism and think about sort of our route out of behaviorism.	
1:59:301	So when we kind of came from behaviorism and moved into the cognitive revolution,	
1:59:371	we were kind of left with some intellectual baggage. Some of that is	
1:59:441	where even from the earliest days of psychology and behaviorism there was some form of functionalism	
1:59:531	which is means that like the way we thought of all mental processes was primarily functional meaning that	
2:00:002	something did something else. So when we think about these interactions between body and brain or body and controller we're always thinking in terms of	
2:00:082	functionalism. So it's like what is you know or why does this behavior exist? It must	
2:00:162	exist for a reason. It's probably to adapt to its envir, you know, uh to allow the organism to adapt to its	
2:00:232	environment. And so this is of course both good and bad in a lot of ways because sometimes functionalism can	
2:00:312	constrain us and sometimes it serves as a useful explanatory device.	
2:00:362	So this kind of uh found its way through behaviorism and then it found its way sort of into the cognitive revolution as	
2:00:442	well. Um and so um but in behaviorism specifically it had three main	
2:00:512	commitments. The first is that psychology is the science of behavior and that the sources of behavior are	
2:01:002	basically external which is means that they're in the environment.	
2:01:042	,	um and that when you talk about mental concepts, you shouldn't and rather you should talk about behavioral concepts.	
2:01:142	And um this actually is one of the differences between cognition or the cognitive what would become cognitive	
2:01:222	 science and ecological psychology is that ecological psychology sort of retained this aspect of the source of	
2:01:312	behavior which is that it's external in the environment instead of internal to the mind. And so this is kind of	
2:01:382	describing this distinction between uh weak and strong embodiment.	
2:01:442	Um and so then you know we kind of talk a little bit about the cognitive revolution going through this history	
2:01:512	and then of course the position of Gibsonian ecological psychology within that. And of course uh Gibbs sort of	
2:02:002	sGibsonian ecological psychology bridges this gap between perception and action and sort of behavior or or some of the	
2:02:092	 things we think about in cognition and behaviorism and some of features of behaviorism.	
2:02:152	And there's been there have been a lot of applications of ectoological psychology um to development to human machine interaction to virtual reality and etc.	
2:02:272	And so then again, you know, in ecological psychology, we think of perception as being direct, meaning that	
2:02:362	um you know, we're really kind of drawing from ecological information and we're building uh our models based on	
2:02:432	that the information is out in the environment and not necessarily originating in in the brain or in the	
2:02:502	mind. Um and so you know we we have different ways of you know dealing with	
2:02:562	perception that's you know or we treat perception is direct. It doesn't rely on any sort of intermediate representation.	
2:03:052	 Um and then uh so you know again	
2:03:152	okay then second perception and action are continuous. So again, this is where you know in a lot of psychology	
2:03:222	experiments, we present these discrete trials and we repeat stimulus presentation over and over again. In an	
2:03:302	ecological uh setting, perception and action are actually continuous. They flow and the order of those stimuli are	
2:03:402	very important in terms of acquiring that information. So you can't just present things in these discrete	
2:03:482	uh discontinuous trials. They have to be in this order in this continuous flow.	
2:03:542	And so this is actually quite a big challenge to a lot of experimental designs because if we have like say a um	
2:04:042	 a naturalistic design, we might put an agent out into the environment and let them interact with the environment. We	
2:04:112	get this ecological information, this continuous information. We get this perception action loop that forms. But	
2:04:182	that action is quite unique to that set of interactions.	
2:04:222	So as you can see, this is very hard to square away with replication because every time you run the experiment, the	
2:04:302	flow of information from the environment will be somewhat different. I mean, even if you have the same environment, a highly controlled environment, it will be somewhat different.	
2:04:402	But this is necessary to understand the true nature of a perception action loop.	
2:04:462	And it kind of speaks to how maybe you know the way we think about doing experiments does not square away with	
2:04:542	the needs to understand how the mind works or how behavior works.	
2:05:022	 And then third we talk about affordances. And so as a consequence of perception being direct and the continuity of perception and action, it	
2:05:112	follows that detected ecological information can specify meaningful opportunities for action, namely affordances.	
2:05:182	In short, affordances are perceivable opportunities for behavior. So they're just features within an environment or	
2:05:262	um you know somewhere where you where you kind of latch on to them. So they're kind of like intuitive points where you	
2:05:342	can kind of pick up. So if you have like for example a door, if you see a handle to the door, you learn that that handle	
2:05:422	is good for either pushing or pulling the door on a hinge. So you learn this in development. You interact with the	
2:05:502	door and once you interact with the door, you get an intuition for how it operates. And so any door that you encounter, you try to to push or pull it	
2:05:592	with the handle. Now if a door maybe slides along the the track a track and you try to do that, then you have	
2:06:072	 problems generalizing. But if a door always behaves the same way, then you just simply use that intuition to guide	
2:06:142	the action and you can successfully generalize an information. So Gibson talked a lot about affordances.	
2:06:232	They're both objective and subjective properties of an object. And this this is, you know, it's sort of a unique way	
2:06:312	to look at generalization in in training and intelligence. So if you have an agent that needs to generalize	
2:06:402	something, you know, or some pattern in the environment, if it's an action type of pattern, like um if you're if a robot	
2:06:492	is trying to move a door or throw a ball or do something with something, um it needs to actually go through the action,	
2:06:582	try out different things and and have build this intuition of what this sort of thing does and then it and um apply	
2:07:072	 that more broadly to other classes of similar thing and that's how it actually would learn. It's not going to learn	
2:07:142	from presenting all possible options as to how this thing is used because first of all um it can't necessarily select	
2:07:222	from those options and secondly um you know you can't um	
2:07:312	you can't really test those out in the environment that you're in. It's very going to be very hard to do that. So this is um why a lot of robots have	
2:07:412	problems with tasks that seem effortless to us because we've sort of automated	
2:07:472	we have these sort of automated or um procedural behaviors um that we don't think about how we	
2:07:552	execute it. We just kind of learn the the um sort of the procedure and we internalize that.	
2:08:032	 Okay. So uh fourth psychology is about the organism environment system. So we have to have the system of both the organism and the environment. This is	
2:08:122	this extended cognition where things are offloaded to the environment where things are you know we extend our	
2:08:192	cognition into the environment and we use the environment and our mental models interchangeably.	
2:08:272	Okay. So this just kind of goes through this history and talks about sort of situatedness and then it sets up his neuro neuroecological cognitive	
2:08:362	architecture. So this is the neuroecological nexus theory. Um and so next is appropriate for the	
2:08:432	investigation of cognizing organism environment systems that have nervous systems. Since cognitive systems are	
2:08:502	always situated, next is committed to the position that such systems necessarily include organisms	
2:08:582	which are embodied of course that are tightly coupled with or constituent by their ecologies. That's embeddedness. So	
2:09:062	 that you know you have organisms that have a body but they're tightly embedded in these ecologies or these	
2:09:122	environments. The nexus part refers to both the framework as a point of convergence for ecological psychology and neuroscience	
2:09:212	and as a nexus that constitutes the primary causal and or constitutive links or junctions that connect the various elements of a cognizing organism environment system.	
2:09:322	So next is defined by five hypotheses.	
2:09:362	Hypothesis one is that the organism environment system is the privilege spatiotemporal scale to understand	
2:09:432	cognition. So we don't care about like the uh details of the brain, we care about	
2:09:502	the organism and the environment but we also care about this multiscale nature of the problem. So sometimes we	
2:09:582	want to drill down to neuronal activity and we want to have this information but	
2:10:052	we want to link ecological psychology in the environment with neuronal activity in the brain. And so we need to	
2:10:142	establish this sort of organism environment system but then have the access to these uh more detailed scales in the brain.	
2:10:252	Hypothesis two is that neural population dynamics generate the relevant states for cognizing. So this is where we have	
2:10:322	these population dynamics that are at a lower level of um organization.	
2:10:392	Um and so we instead of sort of thinking about cells as just neurons, we need to	
2:10:462	think about neural populations. And so a lot of times in cognition neural populations are the things the scale of	
2:10:542	interest where where neurons work together to produce representations and their activity will you know tune those	
2:11:012	secondrepresentations accordingly. Um so there's a lot of uh theory and experiment behind that a neuropul	
2:11:112	group that has been selected for over species development time scales. So you have specific populations of cells in	
2:11:182	the visual cortex that are tuned to visual to extract things like columns	
2:11:242	uh stripes blobs and then that feeds into higher level representations of images. You also have populations in	
2:11:332	sensory motor cortex that are tuned to different limb movements, directions of limb movements, things like that.	
2:11:422	Um, hypothesis three is that cognizing is based on lowdimensional neural dynamics. So, this is where this	
2:11:482	manifold comes in and and manifolds are sort of the current theory of how uh	
2:11:562	neuronal signals are organized. Um, you know, the thinking is that there's this topology or this this representation	
2:12:042	that forms a topology. Um so you have these highdimensional structures and	
2:12:122	lowdimensional manifolds. And so um there's a mapping between the two that's what we call homeomorphic	
2:12:202	which means that they share the same structure even though they look very different. So that's kind of the a tool	
2:12:282	we can use to understand representations of you know large conceptual spaces in	
2:12:352	lowdimensional um structures.	
2:12:412	All right. And then of course it get it gets into a lot of things about the neurommanifold hypothesis and how things	
2:12:492	that say this rat is interacting with the environment moving around the environment are represented in the brain	
2:12:572	as these neural manifolds and then this was represented by um a topological	
2:13:032	structure like a Taurus. And so you would have like this these movements and these interactions encoded as the shape	
2:13:132	and then you explore that area of the shape through neuronal activity and you know everything kind of maps to this	
2:13:222	Taurus which is the representation of the environment.	
2:13:262	Um yeah so then this is again this is a hypothesis four is that the body organizes into lowdimensional synergies.	
2:13:352	So this is uh going back to synergetics from Kelso which is where you have limbs that sort of are controlled together	
2:13:442	into groups, muscles that are controlled together into these synergetic groups and these groups then act as sort of you know outputs for the neural manifolds.	
2:13:562	So a lot of times um you can take a space and decompose it into a manifold itself. So there's this	
2:14:042	uncontrolled or unconstrained manifold hypothesis that uh you know basically breaks the	
2:14:122	environment down into a configuration space. If you have like say a workspace in front of you like a desk,	
2:14:192	how do you have to move your limbs to reach every part of that space? And there actually are quite a few options	
2:14:272	if you were to consider every um possible movement as an individual degree of freedom. But of course, our	
2:14:362	limbs don't operate like that. Our limbs operate as sort of these grouped muscle synergies, these grouped um limb	
2:14:442	synergies. And so our limbs move in certain directions and we have access to maybe a subset of	
2:14:542	movements to reach every part of that space. So when we move our arm, we don't, you know, bend our wrist and bend our arm the other direction or elbow the	
2:15:032	other direction. We actually kind of everything moves in a coordinated way so we can reach different parts of that	
2:15:102	space. And so there are a lot of different uh mathematical tools that allow us to decompose these spaces and	
2:15:192	suggest optimal placement of objects and things like that. And of course this holds true for most things in the environment where you know the brain	
2:15:292	actually computes sort of the most efficient path to a target. And it's it's a really interesting um dynamical	
2:15:382	systems theory underlying this. And then hypothesis five is that cognizing fundamentally emerges at lowdimensional states of the organism.	
2:15:492	And so next claims that cognizing is a multiscale phenomena that emerges from system systematic relationships among	
2:15:552	brain, body and the world. So each spatiotemporal scale is highdimensional but the principal structure of each is low dimensional.	
2:16:042	Okay, so this is something where um you know we're working from these uh neural populations. We're working from these	
2:16:132	uncontrolled manifolds that uh describe body synergies acting in the world. And	
2:16:202	then we can from there build a model of action in the world from neural populations.	
2:16:282	And so this is um an example here of a little rodent in a burrow and it's	
2:16:362	trying to navigate its way out of the burrow and it's building this representation of the environment and it's then acting upon it and it's	
2:16:452	producing these uh muscle synergies that allow it to reach different points in the environment. and it has this model	
2:16:532	of an unconstrained manifold or an uncontrolled manifold that tell it kind of the best places to go for things.	
2:17:012	secondIt's a nice paper because it it stitches together a lot of ideas into what is essentially a cognitive architecture. Um	
2:17:092	there isn't a formal architecture program that he's producing here, but I think you can see the logic in a lot of this.	
2:17:182	Okay, so that's that paper.	
2:17:222	All right. Um, so I think that's all for today. Um, thank you for attending. Thank you for hosting this meeting.	
2:17:302	Yeah.	
