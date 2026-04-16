## Meeting Recording

[YouTube link](https://youtu.be/1xcfcRznh2k)

## Mastodon thread

[link](https://neuromatch.social/@OREL/116389906845746498)

## Feature Videos

[The Latest Replication Study and its Meta-science](https://youtu.be/PfZif6BJevk)

[Neuroecological Architectures](https://youtu.be/D2ISnIHrClI)

## NOTES
Topic: Reservoir Computing and things to benchmark against.

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
0:00     
Okay, I think we're ready. So, welcome. Uh,     
0:07     
who's uh I see Morgan said he's going to the hackathon today. He's going to the     
0:14     
uh tower for that. And then V says that sounds interesting.     
0:21     
So, this is the student hackathon here with the link in the chat.     
0:28     
Uh this is at Frontier Tower. This is a global neuroche hackathon.     
0:35     
Uh it's presented by Frontier Tower. It's this uh 16th floor Nexus for     
0:42     
Frontier Tower in San Francisco. Join us. Uh and then of course uh Morgan is     
0:48     
sort of the organizer there. He works for Neuroch. So he's working on that. Next weekend, Neuroch is hosting the     
0:55     
student led global neuroch hackathon with student teams from around the world coming together at Frontier Tower     
1:03     
to build and collaborate together with a leaderboard. This hackathon is for student teams     
1:08     
decided by their home institutions and not a public hackathon. So they're     
1:13     
just recruiting people from the student clubs at McGill, Berkeley,     
1:19     
John's Hopkins, Stanford, and Austin, and UC Davis. So it's uh it's like a     
1:26     
really interesting event. Congratulations to Morgan for heading that up. Um hopefully they do some     
1:33     
really interesting good work. Right. Did we have uh Di did you have any updates? college reading a few papers and yeah     
1:41     
exams will start in a few weeks so like this is the lower karma phase so I'm     
1:46     
just enjoying before I start studying a lot for that phase but yeah that's good     
1:52     
looking forward to yeah Gog this summer it's going to be good yeah     
1:57     
yeah so let's see um so the diva we're meeting this week uh this was I think     
2:04     
meeting 12 or 13 in the year and on our uh YouTube channel for divorm     
2:12     
for orthogonal web and this was uh we're going through I     
2:18     
think some residual uh discussions about GOC and then we did some other things as well. So uh we had     
2:26     
Shreas Baron Ashu K Morgan and myself to begin the meeting.     
2:33     
Uh we went through Ashu had produced some data. She produced a new data set.     
2:39     
Um it was based on something from worm base. So it was like a different way of     
2:44     
like sussing out the u daughter cells of different cells. So when cells divide     
2:51     
they divide in a binary fashion. They divide into two cells at least in C elegance and you get these daughter     
2:58     
cells. And the daughter cells we can track all the cells and see elegance and we have the nomenclatures for them. So     
3:04     
whenever a cell divides has two daughter cells and we know what those daughter     
3:10     
cells are going to be and even more interestingly we know their relative     
3:17     
position in the worm. So we know if it's going to divide in an anterior direction or a     
3:24     
posterior direction or a left direction or a right direction. So we have these     
3:31     
types of information available to us and it have it unfolds the same way in     
3:37     
every worm. So this is a very fortunate part of this model organism     
3:43     
and so this is just showing these different parts of this data set. So she     
3:50     
built an identity map, she has a lookup table, some normalization rules, and um     
3:57     
so that's all going to get pushed to the uh GitHub repository.     
4:02     
Um then this is uh where we have some motifs from the conneto. So she was going through the developmental cells in     
4:09     
this figure or in this table and then in this uh figure she ran in in a notebook     
4:16     
she ran some network motifs and um     
4:22     
displayed them here. And so a network motif if you're not     
4:27     
familiar is a small connected set of nodes in a network. So a lot of times     
4:33     
we'll look at motifs like triangles which you see here where you have a triangle where three cells are connected     
4:41     
fully and you have this triangle and a lot of networks will have triangles in them or they'll have diamonds in them     
4:47     
and those motifs are you know we we usually count up the number of motifs and it tells us something about how the     
4:54     
network is connected and so this is a you know a method that people use in     
5:00     
topological data analysis. They use it in community uh detection     
5:05     
and they use it in other techniques as well.     
5:10     
Okay. And then this is her uh sort of flowchart for what we were looking at.     
5:16     
Um and uh this is all in service of this method hyper saggnagn     
5:23     
and this is vertex convolution. And then she's going to work through this in her     
5:29     
proposal. So this is um This is a nice contribution. We haven't     
5:34     
gotten around to contributing data sets in a while. Like we've had some data sets in the past that we've committed to     
5:41     
our GitHub repository. Um, and you know, they're usually built upon other shared     
5:47     
data sets. So, we usually have data sets we'd like to extract for our own     
5:53     
purposes. So, we have those in our GitHub repository. Um, and so that's     
5:59     
that's something that is well appreciated I think and hopefully people     
6:04     
will use it outside of this project. All right. So then talked about his     
6:11     
proposal discovering developmental rules in the C elegance connect. This is using     
6:18     
um the whip fleet connect data set and then using the C302 platform which is     
6:24     
the platform that uh openworm uses for their um you know the open the openworm     
6:32     
foundation sponsor the construction of C302 and it's basically uh where you're     
6:38     
simulating the connectto of the uh C elegance which is 302 neurons and those     
6:44     
302 neurons of course each have their own uh bioysics, their own     
6:51     
neurohysiology. So you're able to simulate that with C302 and then run     
6:57     
whole simulations of the brain and and you know if you set the parameters in certain ways you can simulate different     
7:04     
behaviors. uh then then he you know he wanted to use this in a developmental context     
7:10     
which we talked about in the meeting and you know it's not the ideal tool because     
7:15     
there different things h a little bit different things happening in development than the adult but and C302     
7:21     
is based on the adult segans but it's the best tool we might have for that so     
7:27     
he tried that out and his result was you know it was it was acceptable it wasn't     
7:33     
optimal you'd have to do some optimization of it. But you know, this is his diagram of this experiment where     
7:40     
he took the Whitfleet conneto which is a conneto based on um different uh laral     
7:49     
uh configurations of synapses and you know you have that for the different laral stages. Then you C302     
7:57     
simulation you plug that in. You then get neural activity from structure and then you apply this other tool called     
8:04     
Cindy G which is a graph version of Cindy which is a platform for simulating     
8:10     
neurohysiology and biohysics. So he's got that uh pipeline. So this is the     
8:16     
first experiment which is the wet fleet conneto and C302 combined. This just     
8:22     
shows like these different cells that were stimulated and um you end up with     
8:28     
these voltage traces and calcium concentration traces and you can look at that. Um he had also mentioned that some     
8:36     
of the the results he was getting out of his experiments were consistent with uh     
8:42     
the u the rich club theory of C elegance contos which is that there um 302 cells     
8:51     
in the connectto but only a subset of those are     
8:56     
uh really active. they're really highly connected and they sort of coordinate the entire conneto whereas most of the     
9:04     
conneto is not highly connected and isn't active all the time like these the     
9:09     
subset of rich club cells are and I can't remember what the rich club cells are. I believe that some of these are     
9:15     
rich club cells but um we we just talked about that a little bit and I don't know what the answer is there but um that's     
9:23     
something you could do with this platform. Uh so then we go on here um     
9:30     
talking about structural versus functional development in C elegance. So structural development in C elegance     
9:38     
is the uh physical wiring of the conneto. In other words, you know, if you have um     
9:45     
cells and they have connections that are either electrical, which are the gap junctions, or they're uh synaptic, which     
9:54     
means that there's a a connection that's established between two cells. They may     
10:00     
have an immediate connection, but whether or not they're active in any one behavior     
10:05     
uh is immaterial here. What we're interested in is the structure of the connections between the cells. And so,     
10:12     
uh, in the Whitley data set or or at least in the data that they've presented in their papers, they have these     
10:19     
electroic electron microscopy snapshots of uh, C elegance, which means they're     
10:25     
very high resolution images of C elegance and from that you can see those     
10:31     
connections. You can actually enumerate those connections. In fact, this is the way we usually sort of enumerate contos.     
10:39     
We look for different connections in microscopy images and we isolate them     
10:44     
and then establish that two cells are connected. So this is and then of course with electron microscopy you can make     
10:51     
synapse counts. You can do um you know you can actually see the synapses at the     
10:58     
end of axons at the end of dendrites and you can actually count them up um and     
11:04     
then you know have a count for each one cell sort of communicating with another cell and you can uh look at changes in     
11:12     
those in laral development. The other type of connection connectivity is functional development     
11:19     
or at least the other type of development is functional development. This is where you actually base your     
11:25     
conneto on activity. And in neuroiming and say like humans we     
11:31     
have that distinction between structure and functional networks. Structural networks being the you know what cells     
11:37     
are connected or in this case what um uh voxels are connected and then functional     
11:44     
development is which ones are active at any given time. So that we have that in C elegance as     
11:50     
well except we can isolate the cells that we know from calcium imaging data which is where they inject a tracer and     
11:58     
you can actually image calcium influx to the cells and so you know kind of if a     
12:04     
cell is active or not you can then make a distinction of what cells are     
12:11     
functional in what circuit at what point in a behavior. So um you know some of     
12:17     
this of course is captured when we do optogenetics. We can stimulate cells. We     
12:23     
can also look at cells that are active given that stimulation and we can get a better handle on actual activity of     
12:31     
these networks. So functional uh connections are sort of a subset of     
12:36     
structural connections. So he's making that distinction. And so some of that is where we're doing the CDG experiment. So     
12:43     
this was on whitle. So this is where um he was able to do some other work with     
12:49     
um the neurohysiology um you know set up the simulation in     
12:56     
Cindy G and then looked at it that way and then he has these cubic spline fits     
13:02     
which are based on the synapse count from Whitfleet and was able to simulate this for different cells over time     
13:11     
and so then he does this experiment with weak Cindy where he was able to discover     
13:16     
equations that described u the connection between two cells and     
13:21     
or at least the activity of cells. Um and this just kind of goes over that     
13:27     
experiment. Um and that was that was a really interesting work. We had a a     
13:33     
larger discussion. I can't remember what this discussion was about but I guess it was about the experiments he was doing.     
13:40     
And then finally we have this paper um which is spatiotemporal segmentation of     
13:46     
contraction waves in the extra embriionic membranes of the red flower beetle. So this was a paper that we've     
13:53     
been kind of sitting on but uh Susan Crawford Young who's here uh she wanted     
13:59     
she sent me this paper and wanted me to go over it. So the idea is that in the embryo you have these calcium waves that     
14:07     
go through the embryo. um early in development and it organizes the um sort of cell differentiation     
14:16     
meaning that it organizes and there are a whole bunch of waves like this in the embryo. They organize how cells uh     
14:24     
differentiate, the order in which they differentiate and oftent times uh coordinate cells in groups so that they     
14:32     
can form tissues or sometimes it coordinates them to migrate in a certain     
14:38     
direction or go to a certain place. So these uh contraction waves and ex you     
14:44     
know these are things that they've observed. uh there's a theory of differentiation waves that one of our     
14:51     
collaborators and divorm has been working on uh for a long time for decades and um this was interesting to     
15:00     
that work as well. So that was that's a theoretical uh sort of synthesis of a     
15:05     
lot of these different waves that we see in embryionic development.     
15:10     
And so they're using this model organism, the red flower beetle, that uh     
15:16     
you know where they're they they know that these waves exist, but they're trying to characterize their function.     
15:22     
And so that's why this is an important paper. And they use this uh approach called particle image veloss     
15:34     
using cell tracking and then uh extrapolate out their velocity. So you     
15:39     
can know how fast cells are moving and what direction they're moving in a in a     
15:46     
in in the embryo. And you can build little maps that show the arrows and you     
15:51     
know you can show basically the orientation and speed of every uh cell     
15:58     
in the embryo if you're tracking it. And so you can build these maps where there are these you see actually that     
16:04     
sometimes the movement is coordinated, sometimes it's not. And a lot of times you get these shifts in direction and     
16:11     
those shifts are thought to be the products of these waves. So we can do this from different types     
16:17     
of recordings two-dimensional and threedimensional plus time. And this is this was a nice paper     
16:24     
because it it really gave a lot of it really kind of broke this problem down in a single model organism. They had     
16:32     
these maps here where you see the uh the sort of the results of this PIV method     
16:38     
where you have arrows for you know that are sort of like these velocity fields     
16:44     
and it just shows that the cells here are moving in this direction and then up in this direction and this is leading to     
16:51     
different morphagenetic events. So this is leading to different things happening in those regions of the embryo setting     
16:58     
up differentiation events and different type maybe like you know the formation     
17:04     
the beginning of formation of tissues or other types of folds in the embryo.     
17:09     
And so this is just this is just going through a lot of these data. you can uh     
17:15     
find a correspondence between the speed of these velocity fields and the uh sort of time of     
17:24     
developmental events or the onset of developmental events. So here they're looking at the onset of a developmental     
17:30     
event and then this uh function which is a characterization of speed um of this     
17:38     
in this velocity field. This is kind of showing this in detail.     
18:04     
So then you know we can do other things at the waves. We can look at wave segmentation. we can look at uh     
18:10     
different sort of temporal aspects of differentiation. It's really interesting some of the     
18:16     
things he did here. It's very valuable data I think for thinking about these waves and seeing how you can like     
18:23     
decompose them in different ways. Um so yeah this is just really going over a     
18:29     
lot of this work and uh this is you can then map this to the embryo and see     
18:35     
different regions you know different anatomical regions and and what's going on there at that point in development.     
18:43     
So very interesting work and then Susan had some words to say about it as well. Okay so that was a divaorm meeting from     
18:50     
this past week. So yeah, um now at the beginning of next     
18:57     
month, the beginning of May, we're going to try to start our uh open source meetings back up again.     
19:04     
So um this is going to be uh a about an hourong meeting on Fridays. Uh the time     
19:13     
is usually 12 noon Eastern time, which is in North America. So if you're in     
19:19     
another part of the world, you just have to figure out what what you know what the time difference is. Um if you are     
19:27     
interested in joining, you know, we'll be posting in the slack about when this is and um you know what what the topic     
19:35     
will be. So basically it will be when we select our GOC students um they will be     
19:41     
presenting their projects during this time. We also welcome anyone to join us and they can work on their own projects.     
19:48     
Um if you're not successfully selected for GOC, you can work on a project there as well.     
19:55     
And um you know it's uh then we'll also have and this is usually something that     
20:03     
the mentors do. Um I do this a lot. Jesse does it sometimes. Sometimes     
20:08     
Morgan joins in. Uh but anyone's welcome to talk about different topics in open source. So we usually, you know, they're     
20:15     
usually somewhat obscure topics that are, you know, something we'd like to talk about and and kind of think about a     
20:22     
little bit. We also talk about project management techniques. Um and, you know,     
20:28     
making sure that we can give people uh some professional development opportunities. So to think about some of     
20:34     
the things you might encounter in the workplace that are, you know, dilemmas     
20:40     
or sometimes, you know, younger people haven't thought about because they've never experienced it. So that's always     
20:47     
good stuff. Um, and so we'll be starting that up around the beginning of May. Um,     
20:55     
and hopefully, you know, it'll be good a good time this year. Last year was pretty good. Um, I think we got a lot     
21:01     
of, uh, interaction and a lot of, uh, productive time out of that.     
21:08     
All right. Uh, looks like Morgan switched to his laptop.     
21:13     
Also, Sara's here. Welcome.     
21:19     
Thank you. I've been your I was listening to you.     
21:27     
Yeah. Good to hear. Good. Yeah. All right. Um,     
21:34     
did we want to share anything today? Uh,     
21:40     
um, not much. The past week I've just been focusing like I've been going     
21:46     
through the proposals also some interesting stuff on uh, are     
21:52     
you all following the GOC mentors thread by any chance? Uh, I have. Yeah. Uh there are a lot of     
21:58     
things going on there. Yeah, lot of things happening there. I just I wake up every morning and while I'm going to work, I just go through the     
22:05     
emails there. But yeah, it seems like uh I mean everything that's happening it's     
22:10     
kind of relatable for every odd, right? It's the same things are happening to     
22:16     
everyone and uh there's like no one has kind of a solution for it. Everybody     
22:23     
just has their own techniques. Um and yeah, but interesting to see     
22:29     
everyone's kind of approaches to it as well. Yeah.     
22:34     
And yeah, mostly just reviewing our proposals. There's quite a few this     
22:40     
year. So last week's just been that in work.     
22:46     
Yeah. So how many proposals did you get for the large language models?     
22:53     
Um I so I kind of starred every that uh was     
23:00     
both so seven and eight both have starred and kept so I mean the open     
23:06     
source sustainability project has 14 proposals. Um, out of that I think I'm not fully     
23:15     
sure how many are for the project number seven, the Greenfield project, and how     
23:21     
many are for uh the LLM one. I think there's I know     
23:26     
two definitely that are for Greenfield so far. But yeah, I mean another thing     
23:32     
that I think we should really do uh next time for us is uh make sure that they     
23:38     
all title their project name with the exact uh project title from     
23:45     
um from the GC ideas list with the number with the project number because they     
23:52     
everybody has kind of come up with like they've titled it innovatively but it's a it's kind of a pain to filter it     
23:59     
through and and find everything correctly. So yeah, but yeah, but I would say 14     
24:06     
proposals for for the open source sustainability project. Okay, good number.     
24:13     
I didn't count those, but I did count the green field. I think there were two for green field. Um I don't know why     
24:18     
they have already Yeah, I don't know why they said green     
24:23     
field. Meanfield would be better actually, but whatever. Yeah, I was a little confused at first. I thought that     
24:30     
was a different orcs project and then I read and then I like what it's just named. I knew you were submitting two     
24:36     
two projects this time. One for like if you want to have any other approach and one specifically for the LA mask man,     
24:42     
but I didn't see what it was named and then I saw with all the proposals.     
24:49     
Yeah. Did you did Ara has that name or did you propose it? I have no idea where they got it from, but     
24:58     
probably some AI too. Yeah. Well, yeah. Yeah. So, 14 is a large     
25:06     
number. Yeah. Yeah. Um Yeah, we had like I think 10 for G or     
25:13     
for D.Vaorm. So, that's a lot as well. So, uh     
25:18     
compared to past years. Yeah. Yeah. Well, I mean, every year like we get uh our projects usually get pretty     
25:25     
good interest like and I don't know what other projects are getting, but like     
25:30     
usually we're in like you know I mean a few more like I think last year we had     
25:36     
like seven for D.VARM and like seven for um open source.     
25:42     
Open source system. Yeah. Yeah. Yeah. Yeah. But then still I would say it's     
25:48     
it's doubled this year, right? Yeah. It's like a quick     
25:54     
Yeah. So did you find Yeah. Sorry. Go ahead. Oh, did you find the rubric useful that     
26:01     
I I sent out or? Yeah. Yeah, I did. I'm filling in that. It's It's good to, you know, kind of     
26:07     
break it all down into individual components. Yeah. To be able to instead of just I did add     
26:13     
a few more columns, but I'll share it with you. Okay. Yeah.     
26:23     
Oh, is Jess not coming? Yeah. Um, I don't know. He, you know, he might come later.     
26:29     
Usually comes later, but hopefully he'll, you know, maybe he'll say something about like some of the     
26:35     
other things he's been working on, but yeah.     
26:40     
All right. Thank you, Sara. Thank you.     
26:46     
So, I did want to talk about this. This was um a couple weeks ago, of course, we had     
26:52     
the uh embodied intelligence workshop and um there's a good time. I think     
26:57     
there was a lot of interesting stuff at that workshop. um a lot of uh soft     
27:06     
robotics, a lot of embodied robotics, and then of course you had other talks     
27:11     
um that focused on uh cognitive science and uh like computation and things like     
27:19     
that. Um and so this was one of the things they had this year were these um     
27:28     
uh master classes and they were basically experts in different areas who     
27:33     
would talk about their um different areas of expertise and they'd     
27:39     
put on the class kind of giving you an introduction to something and then it     
27:44     
would be you know uh on that topic. So, one of the master classes was on     
27:50     
reservoir computing. And if you're not familiar with reservoir computing, um     
27:56     
it's a sort of a newer technique. It first was proposed in around the year 2000. And it was this idea that you can     
28:04     
do uh sort of uh maybe you know you could think of it as like an alternative     
28:10     
to uh uh different types of neural networks.     
28:17     
where you have a reservoir of nodes and you're putting together networks based on data that goes into node into this     
28:24     
reservoir and then it comes out the other end as sort of this uh uh     
28:30     
basically this encoding or this this representation. And so that's that's kind of the idea behind reservoir     
28:37     
computing. And it actually started as um something that was made for analyzing um     
28:46     
problems that involved reservoirs, which is interesting. But it's it soon evolved into this idea of reservoir computing um     
28:54     
where you have um different computational resources and you're using     
29:01     
you know you're trying to optimize those resources. Um and then of course they have     
29:06     
reservoir networks which are network is something in network science that's     
29:11     
taken off where you use reservoir uh reservoir computing devices to build     
29:18     
networks from data. So you have your data which is your interaction matrix.     
29:24     
you put it into this reservoir which is a sort of a stochastic process and it     
29:29     
puts together this network that you can then use um to analyze things. So you     
29:35     
have this representation that that comes out of it. So it's a pretty nice little method. I     
29:42     
know they were thinking about this in openworm at one time, how to use reservoir networks to characterize the     
29:48     
conneto of sea elegance, which would be a nice little project because it's it's a very small network that you're trying     
29:54     
to reconstruct and um you know it's it's a computational tool that doesn't have a     
30:00     
huge amount of overhead. So it's you know plausible to build something like that.     
30:06     
So this uh was is something from the morphological computation blog. Um and     
30:13     
so this is um talking about this fresco competition     
30:18     
which is the first international physical reservoir computing competition.     
30:23     
So um this is uh physical reservoir     
30:28     
computing competition or fresco is the world's first competition dedicated to exploring the frontiers of physical     
30:35     
reservoir computing. We invite researchers, students, and interdisciplinary teams to demonstrate     
30:41     
how physical systems from soft materials to chemical systems to biological     
30:47     
tissues or any complex physical structures can be harnessed for computation, intelligence, and complex     
30:56     
signal processing. So like I said, reservoir computing started with actual     
31:01     
reservoirs of liquids and you know they they were using that as sort of the the     
31:07     
metaphor. Well, people are also interested in this sort of physical computing which is where you have     
31:14     
physical systems that are you know basically the computation machine and     
31:20     
you we talked about this with uh different types of uh chemicals or you     
31:27     
know you could maybe include organoids in that or slime molds which we've talked about before. any of those are     
31:34     
sort of ways that you can do these computations using this physical reservoir structure.     
31:42     
And so, uh, this is not just a contest. It's a collaborative research initiative     
31:47     
and completely free. Uh, just so you're aware, it's not like a money-making scheme. In this emerging     
31:55     
field, your input will help define what counts as creativity, novelty, and significance. So they give a little bit     
32:01     
about u physical reservoir computing here which is firc.     
32:07     
It's a modern machine learning approach that uses nonlinear physical dynamics. So you know thinking about like a     
32:14     
reservoir like water flow or laser dynamics or in even soft robotic bodies.     
32:20     
So you can use any kind of physical system as the reservoir and use those as computational resources. We are     
32:27     
currently preparing a set of introductory videos to explain the underlying principles and we're also     
32:33     
preparing a few examples for inspiration. So there they recommend reading this     
32:39     
paper physical reservoir computing in robotics     
32:45     
which looks at how soft bodies and robots can be used. However, vizrc go or     
32:50     
firec goes way beyond that. The first ever physical reservoir computing uh     
32:56     
work used a bucket of water. This is paper pattern recognition in a bucket.     
33:02     
Uh this was Chris Santa Fernando and Sam Sojaka.     
33:07     
Uh a good overview is the book reservoir computing theory physical implementations and applications     
33:15     
uh which provides a chapter on gener general reservoir computing but also some physical reservoir computing. Uh     
33:23     
finally a look at Susan Stephanie's physical reservoir computing a tutorial which is uh at this link. So these are     
33:29     
all like a life people um Susan Stephanie Croissant Fernando you know     
33:36     
work in a life or artificial life and you know this is uh consistent with this     
33:42     
idea of sort of nonconventional computation.     
33:47     
Okay, so that's I mean this is just kind of going over this work.     
33:53     
Um and so then you know who should apply academic researchers exploring novel     
33:59     
computational paradigms students interest in unconventional computation     
34:04     
cross-disciplinary teams uh which in might include physicists     
34:09     
material scientists neuroscientists and engineers independent researchers and and     
34:15     
enthusiasts with a passion for experimental systems. Then everyone who is fascinated by     
34:21     
physical reservoir computing. So this is just kind of you know trying to be inclusive to all sorts of different     
34:28     
fields as this would involve not just conventional computer science.     
34:34     
So this just goes through the the criterion for this.     
34:40     
Um this is a picture of I guess this is just showing an example of an acceptable     
34:47     
implementation of reservoir computing. So this is a very small example here. Um     
34:55     
this is a crumpled piece of paper with dots on it. So these are fedial markers     
35:00     
for output extraction. Uh there's another dot that's in green. So the the     
35:06     
output extraction are in blue. There's a another marker in green for input. And so then you have the servo which serves     
35:12     
as input actuation. and then an Arduino for servo control I     
35:18     
guess which uh does something with the uh input and     
35:24     
then it gives you outputs. So I'm not really sure the details here but this is basically a reservoir computer. Um and     
35:32     
you know this is like I guess an acceptable submission. So you have to kind of read the papers and figure out     
35:39     
how to build the computer that you want to build is that um there's a lot going on in     
35:48     
different types of computation beyond neural networks because we talk about like neural networks and large language     
35:54     
models a lot in the group. We've we've talked about a lot of other kinds of computing in the past, but just as a     
36:00     
reminder that there are all these other paradigms out there.     
36:07     
Okay. So, I don't know if Morgan's there.     
36:21     
Yeah. Yeah. I mean, you know, um I was just talking to     
36:28     
some some users of Final Spark, you know, the organoids intelligence     
36:37     
cloud platform. You know, basically they they run a     
36:44     
bioreactor farm in Switzerland that is, you know, um     
36:52     
using organoids connected to microelectric arrays. But the primary     
37:00     
you know at the demo days or what I for what they called it um     
37:07     
user days um a lot of the applications were just     
37:12     
reservoir computing um approaches you know and that was the that was also     
37:22     
the the Um     
37:27     
I I forget if it was I think it was Indiana like like one of the first     
37:32     
organoid um machine learning examples was was also a     
37:41     
reservoir computing you know um and     
37:48     
if if I would say you know not not not a full criticism but just like you know     
37:54     
this is something that you can do with non-living matter     
37:59     
and and you know like like it it's an interesting     
38:06     
yeah so I think it speaks to     
38:12     
well leaving aside what it says about organized computing um     
38:19     
it's still you know it's still an interesting topic and and you know if     
38:24     
that's one way to um perhaps you know have a submission like uh yeah that's     
38:31     
that's cool and I think I know some people who should at least look at it.     
38:36     
Yeah. Um because they're definitely taking this this reservoir approach. I I just     
38:42     
need to learn more about reservoir computing. Yeah. you know, the um     
38:51     
um you know, what's its lineage and and what um     
38:59     
Yeah. And and then like what what does it make sense to compare and analyze the     
39:06     
resourcing approaches with, right? So that you can say more about what the     
39:13     
Yeah. just so you can say more about what the system is doing. Um     
39:18     
I don't explainable reservoir computing. Yeah, I well I think the problem is is     
39:24     
that it's not very interpretable. Yeah. I mean as you can imagine because you have this big pot of hidden pot of     
39:31     
nodes and you have hidden states in there and you have to kind of extract things out of it. Um I've been doing as     
39:38     
like I think I mentioned I I'm doing this agentive coding paper that uh where     
39:44     
I've actually taken reservoir computing and then compared it with uh diffusion     
39:50     
processes like forward and reverse diffusion. So you know that diffusion is a hot topic and like machine learning     
39:57     
and like there's this you can use those kind of as a comparison. So you have this sort of physical     
40:06     
So you have this physical or quai physical process of some physical u     
40:12     
randomization or you know so forward diffusion is where you're adding noise into an image say and then uh putting     
40:20     
you know doing reservoir network you might take an image and have it as input to the reservoir     
40:26     
and then it's trying to find the uh you ever heard of self-organized maps     
40:33     
yeah so I I I I met Conan. Okay. Oh, good. Yeah.     
40:40     
Um so that I mean it's kind of like that kind of process where you're taking a     
40:45     
bunch of random nodes and you're kind of finding the pattern from the map. And in     
40:51     
the reservoir it's just like you have a reservoir with a finite number of nodes and you're just kind of extracting the     
40:57     
the features out from there. And then in in uh diffusion you're doing forward     
41:02     
diffusion where you're adding noise and then that's helping you to recover things because you're generalizing the     
41:08     
model. So as you add noise into the images uh into that into that input,     
41:14     
you're sort of saying, okay, this input looks like this in an idealized way, but then if I add noise, I'm actually able     
41:21     
to see what it looks like partially oluded or with a partial mask. And then     
41:26     
the reverse diffusion will recover images from that noise. So you can recover a wider range of images     
41:34     
if you're adding an an input into a random network. um you're able to     
41:39     
recover patterns uh based on sort of those you know that random network being     
41:45     
rewired into a feature space. And so that's kind of the way that the comparison works. You could compare uh     
41:53     
diffusion and reservoir networks and how those things yield um an analysis of     
42:00     
some sort of input data. But uh the difference of course there are a lot of differences. One of course is     
42:07     
interpretability. Um and I guess in the case of um     
42:14     
uh uh diffusion it's higher and in reservoir computing it's lower. There     
42:20     
also some computational differences. I think reservoir computing requires more computational resources. Uh I'll have to     
42:28     
pull up that I I generated a table on this. Yeah. Just for my own curiosity. I     
42:33     
want to know what the differences were. Um it's it's interesting. Um but yeah,     
42:38     
you can that's I think the most direct comparison. Um interesting. Okay. I mean, you know,     
42:46     
like yeah, I would really love to to see that if you if you don't mind sharing     
42:52     
because like you know, this is this is such a widely used or it's practically     
42:58     
the only technique used in organoid computing. Yeah. That that like you know I     
43:06     
I I need to have more a better understanding um in in order to kind of shift the     
43:14     
conversation and and you know like uh this group that's meeting this summer to     
43:22     
you know somewhat more focused on I mean potent focused on the whole range of of     
43:29     
OI applications or kind of like issues. So that's going to include actually     
43:34     
growing them and you know things like that. Um but this is definitely one of     
43:40     
the topics that like needs to be a part of this this workshop which is you know     
43:46     
which which it was nice to see that the the organizer um is definitely coming     
43:51     
from a you know um I mean he's definitely more of an engineer but he's coming with enough uh     
43:59     
ML background that you know he's he's got some really um I think good     
44:07     
questions about understanding what the what the     
44:12     
reservoir computing approach is saying. Um when you know the way they're using     
44:17     
it, they want to say that the the tissue is you know we we want to say that the     
44:22     
tissue is doing work. Yeah. And and that's the bit that is uh he's     
44:29     
got some interesting ways to kind of probe that. So it' be great to put that in the context of, you know, kind of     
44:38     
some some language that I understand a little better. Yeah. Or at least that's those comparisons.     
44:43     
That that's that sounds that sounds interesting. Yeah. So the tissue is doing     
44:49     
thermodynamic work. It's just the computational work is what you're saying.     
44:55     
Right. Right. Well, I mean, you know, like like again, like when when     
45:02     
um Cortical Labs, you know, which is it's like this is kind of a I'm holding them     
45:09     
to an unfair bar perhaps, but you know, when Cortical Labs calling this a biological computer, um     
45:20     
it's suggesting that they're passing data to     
45:25     
neurons neurons and that's the neurons are processing them     
45:33     
and you know and then they're passing the data back or at least that would be a computer     
45:41     
metaphor. Yeah. Okay. Um, what you're describing is is,     
45:50     
you know, I would just say is, you know, is is it more is more accurate and is,     
45:58     
you know, as we know, can be done by non-living systems.     
46:04     
Yeah. Yeah. Um, yeah. There there's a metaphor there. Um and then there's this     
46:10     
whole aspect of physi physical systems compute which we did a whole bunch of work we did a whole series of like     
46:17     
features on in this meeting about two years ago now remember the physical computing thing     
46:23     
uh that that is kind of thinking about that in a little bit different way so I mean the idea there we were talking     
46:29     
about like does the is the brain a computer is it like you know uh is there physical     
46:36     
computing that's comparable to comp or to sort of digital computing. With uh     
46:42     
reservoir networks, you really do have like a physical computer where you have things that maybe aren't bits like they     
46:48     
don't originate as bits. You know, maybe there are things that are changes in state like in physical systems you have     
46:56     
phase transitions, right? And phase transitions are this rapid reorganization of the of the     
47:02     
of the sum of molecules in say like a liquid going from water to a solid or a     
47:09     
liquid to a solid. And so um in that case you know you have this mass reorganization of things. You can look     
47:17     
at that phase transition is say like um maybe hardness of state of the medium     
47:23     
and you have this shift. It's kind of like a sigmoidal where you go from like     
47:28     
a liquid and then all of a sudden to a solid and it's very sharp. Um it's not a step function but it's kind of like a     
47:35     
segue or it could be a step function. Now what we will do in a what we have to do to convert that to bits is to say     
47:42     
everything in either side of the phase transition is either a zero or a one. So if it goes from a zero, which is a     
47:48     
liquid, to a one, which is a solid, that's a a bit that's flipped. Or if we     
47:56     
go the other way, it's a bit that's flipped. But that process is kind of obscured. We can't I mean, we could I     
48:03     
guess we could uh we could capture that with a a digital computer, but we'd     
48:09     
always have to state that in bits. We'd always have to convert that to like a binary state or maybe a turnary state.     
48:16     
if we're lucky. But that doesn't describe a lot of that process. So there's a lot of process that gets     
48:22     
assued and you know um a physicist would be horrified because it's like you know     
48:28     
you're you're obscuring this whole process. It's interesting. Um the same     
48:33     
thing with organoids. You have this these uh you know graded signals and you     
48:39     
have a bunch of stuff in parallel and you have networks where you know the     
48:45     
networks are these cells that are connected and then the cells are in a state right and the state is just really     
48:51     
kind of abstracted from a lot of complex interesting biopysics going on and     
48:59     
that's that's kind of maybe the problem here is that you have this you know you You say computational work, it's like     
49:06     
well computation, what level of computation? Um what do we     
49:11     
mean by computation in the first place? Yeah. Um there's yeah that whole literature on     
49:17     
like unconventional computing. I can't remember how they're dealing with those things. I mean it'd be kind     
49:22     
of interesting to do a deep dive into that to see how they frame those kinds of questions.     
49:28     
Absolutely right. Absolutely. It reminds me the um     
49:35     
uh sorry I'm still on the way to the flower     
49:41     
but like like there's a company there's a company um     
49:48     
based in LA. It's funny because the CEO is like like     
49:54     
a super fan of Carl Fristen. Oh yeah. Um     
49:59     
but he's uh uh and they they finally got aired up, you know. Um, but uh uh     
50:10     
I'm blanking on the name of the company, but it's like it's EXO something and and     
50:15     
I think I think part of it is coming from     
50:22     
I I I was just going to say like is the this is like a former quantum computing     
50:28     
person who um who uh has started this     
50:35     
compute company, not quantum, but it's got some sort of     
50:42     
thermodynamic um it's like     
50:50     
it's like exo something. Yeah. And and I I wonder if it's like     
50:58     
somehow trying to use a     
51:04     
similar, you know, e extra physical process, physical     
51:11     
computation process. Um it's is he's is building it as like a     
51:17     
super efficient, you know, not not neuromorphic, but um     
51:25     
um yeah, I I'll find it when I get to the tower. All right. Yeah, that's fine. Uh yeah.     
51:32     
So yeah, there are like even if you go back to Fineman, he talked about a little bit about like physical computing     
51:39     
and how you compute physics and this is a classical physics not necessarily     
51:44     
quantum physics because quantum computing of course is its own paradigm. Um we don't want to borrow from that for     
51:51     
classical processes. So you know it's kind of like what do we how do we characterize     
51:57     
uh you know physical computing in that way. Um so yeah I don't know I'm going     
52:02     
to have to look into that uh more in more detail and you know it' be an interesting set of things. I think I     
52:10     
actually mentioned uh some of Fineman's work on it uh back when we did that uh physical computation     
52:19     
series of features like two years ago. We have a post on our medium about it um     
52:26     
if people are interested in going back and reviewing that. Um but yeah, just a     
52:32     
series of discussions we had on different papers, different things. It ranged from philosophy to physics to     
52:38     
computer science to neuroscience. And it's just kind of thinking through all these uh questions that were interesting     
52:45     
to our group, our group, but also uh more inclusive to different debates in     
52:54     
the scientific literature. Okay, thank you Morgan for that uh discussion.     
53:00     
So this is something else. I think Morgan posted this in the slack     
53:06     
and um this is a paper from the u     
53:11     
there's this uh it's on scientific replicability     
53:16     
lead author on this paper is Brian Nosk and so um this uh article is titled     
53:23     
investigating the replicability of the social and behavioral sciences. is very     
53:28     
ambitious because there's a lot of social and behavioral science out there.     
53:33     
Um but basically they're doing a metaanalysis on the field and they have this uh     
53:40     
interest in replication and replicability. And so when we say replicability what are we referring to?     
53:48     
Um so basically in science one of the     
53:53     
things that we try to do when we do experiments is we would like to first of all have a     
54:00     
controlled experiment where we have a hypothesis and then we set our     
54:05     
experiment up so that we can test the hypothesis without too many confounds. So the idea     
54:12     
being is that when we have a hypothesis about like say um if I move my mouse     
54:18     
across the screen um you know I'm doing something with my hand there's a     
54:26     
motor control involved and if I perturb that motor control in different ways for example if I have a distractor light in     
54:33     
the uh peripheral periphery of my visual system it will slow down my ability to     
54:39     
move the cursor across across the screen because I'm distracted visually by that     
54:44     
thing and it disrupts my sensory motor integration and so it's my movement is     
54:50     
slower and you could you know have a control where people aren't distracted by the light uh a experimental condition     
54:59     
where people are distracted by the light and then have different levels of distraction so that one is obviously     
55:06     
going to have an effect and maybe one is has a minimal effect and you you predict     
55:12     
all this in advance. You design the experiments so that you can test the the     
55:18     
relationship very in a very isolated way and you try to eliminate confounds which     
55:24     
are things that will maybe could be other potential causal mechanisms or or     
55:30     
um effects and you try to um minimize the     
55:35     
interactions of different variables. So you just want to have the two variables or you know uh that that you're testing.     
55:43     
So you have a very clean if you have a very clean experimental design     
55:48     
first of all your effect will pop out and you'll be able to see the effect. You can use statistical testing to um     
55:57     
confirm that effect and then of course you have an effect size which depends on the number of people who are in your     
56:03     
experiment. And then of course you have this idea of replication. So if I design a good     
56:10     
experiment and I have this result, I can you know do all sorts of different     
56:16     
uh statistical tests. I can even do causal modeling and say this is you know     
56:22     
the effect and it's real. Another way to know that it's real is to to replicate that result. To do like 10 experiments     
56:32     
and have them all basically point in the same direction or have 10 different groups do the same experiment. And why     
56:40     
do you want to use different groups? Because different groups will do the implement this slightly differently.     
56:47     
They might use different variations on the light. they might use different variations on uh the the cursor speed     
56:54     
and and so forth. So you have if if the effect holds up across these different     
57:01     
um variations then you know that the result is robust. So that's the idea     
57:07     
behind replication. We'd like to see replication also because if we're trying to apply our findings to um you know     
57:17     
applications like if we want to build this into a computing paradigm like a user interface we want this to be     
57:24     
something that is robust. So if we say, you know, we want to build this result into a guey, we want to make sure that     
57:32     
this isn't just some result that's not um very well supported and is maybe the     
57:38     
case only about a quarter of the time because that would be, you know, it would result in a a bad product.     
57:45     
So replication has a lot of uses in um you know in the behavioral sciences but     
57:52     
also in other areas where we do experiments and you know the thinking is of course is that physical systems or physics you     
58:00     
can replicate things very easily or maybe in chemistry because those are physical systems and we have a very high     
58:08     
degree of characterization of those systems and quite frankly they're not as complex as social systems at le or so     
58:16     
the thinking goes. So, a lot of people who do biological experiments and social     
58:22     
science experiments will say that um you know I you know I you know I can use     
58:27     
experimental techniques but they're not going to be as replicable as those in physics and chemistry simply because     
58:34     
it's harder for me to isolate the different um variables involved, not get     
58:43     
interactions and not get confounds because you know In biology and in     
58:49     
social science, you have a lot of sometimes you have uncharacterized variables, sometimes you have a lot of     
58:56     
uh things that are interacting. Um, and it's it's just really hard to     
59:02     
isolate those things and then also make that um that experiment useful for     
59:07     
understanding the system as a whole. So we can do experiments in biology and social science that are very contrived.     
59:15     
They have very low what we call ecological validity or     
59:21     
the ability to transfer those results to um to reality. You know what does that     
59:28     
mean in reality? What does that mean in like a real social setting or real psychological setting or a real     
59:34     
biological setting? And a lot of times our experiments are just that. they're they're sort of uh     
59:41     
artifacts of you know that that don't have a lot of application outside of their own domain.     
59:49     
So this is kind of where we we sit with this. So the idea is is that replication     
59:58     
um we kind of assume that replication is gold standard in the social sciences because of the factors that I mentioned     
1:00:05     
it's hard to get experiments to replicate. So this has led to something that they call the replication crisis     
1:00:11     
which is that you can do all these experiments and get these results and um     
1:00:18     
if you go back to the literature to try to reproduce a lot of experiments sometimes a lot of famous experiments     
1:00:24     
you can't replicate them and you know this is a this is a thing that is sort     
1:00:30     
of the basis for this science reform movement that you might see Brian Nosk     
1:00:37     
of course is very interested in this. There are other people as well which is that we need to improve science by     
1:00:43     
finding better ways to do science, finding better ways of standardized science. Uh because we want to have more     
1:00:50     
replicable social science, more replicable biological science. Basically, where we can't replicate     
1:00:57     
something, we should try to rethink how we do experiments, how we do data     
1:01:02     
analysis so that we can make things more replicable. And of course then there's this other school that says well we really can't do     
1:01:09     
that. We just have to go with what we have and you know that's just kind of     
1:01:14     
our heristic and and you know that's the best we can do and I wouldn't worry about it too much. So um you know there     
1:01:22     
there it is a debate. So when they present this stuff it's interesting and     
1:01:27     
it's I think useful for understanding where we stand in the science in the     
1:01:33     
social and biological sciences. But it's also very much um you know maybe we     
1:01:40     
can't expect to use experimental methods and really expect to have highly     
1:01:46     
replicable results. Maybe uh the best we can do is like quai experimental methods     
1:01:52     
that gave us give us indicators of what things are you know effects in social     
1:01:59     
science. if we have a intervention for example there's certain effects that we should expect and it's not going to be     
1:02:05     
very easy to replicate those across different labs or different contexts. So     
1:02:11     
that's kind of where we wrote this. Um so let's go over the abstract of this and then a little bit into the paper. So     
1:02:18     
as as uh as meta-cience what they're doing is they're taking a bunch of     
1:02:24     
different results from different papers that have been published and they're re-evaluating those and they want to     
1:02:31     
understand kind of as a whole where we sit, how replicable are claims that get     
1:02:37     
published. And sometimes they're very famous results. And sometimes we base a lot of our theories on them or a lot of     
1:02:45     
like um uh popular sort of science popular ideas about how the brain works     
1:02:52     
for example on them. So you know there have been a lot of examples in psychology where um you've had famous     
1:02:58     
results that have everyone has kind of hung their hat on and then they turned out not to be replicable. And so this is     
1:03:06     
a little bit of a a ding on um some of the co cognitive science techniques that     
1:03:11     
have uh come out of the cognitive revolution. So in any case, let's get     
1:03:16     
into the abstract. Pursuing replicability or independent evidence for previous     
1:03:23     
claims. So you do an experiment and you publish your results and you observe the     
1:03:29     
effects there and then some other group tries to do the experiment again and     
1:03:35     
they either get an effect and maybe it's of a different size because sometimes     
1:03:41     
you don't get the same number of subjects. Sometimes those subjects exhibit variability. Sometimes your     
1:03:47     
environment is a little bit variable and so you can't expect them the uh results     
1:03:52     
to always be exactly the same but you should get them in the same direction. You know if they get a positive result     
1:03:58     
you should also get a positive result and you should be able to do this uh in any kind of setting. So like again if I     
1:04:06     
want to confirm some finding I just simply run the experiment for myself and     
1:04:12     
I get that result. And as we know we can do that actually we have a version of this in computer science where you run     
1:04:18     
if you run things in a container. The whole concept of that is that I will     
1:04:23     
write a program execute it on my machine and then if you execute the program on     
1:04:29     
your machine you might get a different result because your machine is is different parameters has a different uh     
1:04:35     
process or whatever but if I put it in a container I can always run the the the     
1:04:41     
program exactly the same way and get the same results. So there is a version of this in     
1:04:47     
computer science. Um, unfortunately we can't containerize     
1:04:52     
social and behavioral science experiments or biological experiments. So that's that's that's something to     
1:04:58     
keep in mind. So this allows us to have generalizability which you know in     
1:05:05     
machine learning we worry about with training models but in a lot of these experiments we want to make experiments.     
1:05:13     
We want to design experiments so that the results are generalizable to you know any kind of replication and     
1:05:20     
eventually even to application domains. So here we attempted replications of 274     
1:05:28     
claims of positive results from 164 quantitative papers published from 2009     
1:05:36     
to 2018 in 54 journals in the social and behavioral sciences. So a wide range of     
1:05:42     
different findings uh published recently. So this is well 2009 to 2018     
1:05:48     
is well within this sort of science reform era. So this is like you know if     
1:05:53     
you go back to like the 80s and 90s or in the 70s um you can go back there and     
1:05:59     
find a lot of experiments where people were totally not thinking about this. You know they were very um not thinking     
1:06:06     
about replication too much. Sometimes they were, but a lot of times they weren't. And you know, you might you     
1:06:12     
might say, I'll take some experiments that were published back then and and reinvestigate them, and lo and behold,     
1:06:18     
they don't replicate the way I expect. Well, you know, that's maybe unfortunate, but it's not something that     
1:06:26     
where people are actively engaged in this conversation. But with from 2009 to 2018, this conversation was going on.     
1:06:34     
So, you know, you might say, well, people were, you know, just trying to run their experiments and live their lives, but the idea being is that, you     
1:06:41     
know, people were aware of this problem and it still persists. So,     
1:06:47     
and I will say that the uh no group and and some of these other groups, you know, they have a specific sort of     
1:06:53     
agenda for this. It's not like they're picking on people, but they do have this idea that, you know, uh science needs to     
1:07:01     
be done a certain way. So um this this is and they want to sort of advance their own research in um science reform.     
1:07:09     
So there is that aspect of it. So you know I'm not saying that like people are     
1:07:15     
just being intentionally dense about science reform. It's just that that's     
1:07:20     
the the that's where we are in in this in this uh debate.     
1:07:25     
Um so they they had a pretty good sample of different studies to look at.     
1:07:32     
Replications were high powered on average to detect the original effect size uh with a median of 99.6%     
1:07:40     
used original materials when relevant and available and were peer-reviewed in advance through a standardized internal     
1:07:47     
protocol. Replication showed statistically significant results in the original     
1:07:53     
pattern for 154 of 274 claims which is     
1:07:58     
around 55.1% of studies surveyed. Uh so this is you know maybe not great.     
1:08:06     
Um it's it's over half but it's only about a little over half. Uh so this     
1:08:12     
means that you know if you have experiments that you take out of literature at random     
1:08:18     
uh only a little bit more than half of them replicate. And that's you know again this is using sort of the     
1:08:27     
you know as close as we can get to the original experimental design.     
1:08:33     
So um you know that is kind of disappointing maybe     
1:08:40     
and for 80.8% of 164 papers which I don't know how they get to 80.8 eight of     
1:08:46     
a p you know point eight of a paper. Um but I think this is just a waiting     
1:08:52     
scheme uh weighted from replicating multiple claims per paper. So this is     
1:08:58     
where you know they make more than one claim from or maybe more than one experiment in a paper and you're kind of     
1:09:04     
looking at this in its totality. So um we're really kind of at and when we do     
1:09:11     
that we actually get a little bit below 50%. So actually if you think about this as an at chance endeavor like if we had     
1:09:20     
like if we ran a thousand experiments and we got 50% of them that replicated that's kind of at chance it's not but     
1:09:28     
you know that's one way to think about it. Um there probably reasons why this     
1:09:33     
exists. Um I don't think people are doing a poor job of experimental design but um they never really kind of get     
1:09:40     
into that in these papers. they always kind of just show that there's this lack of replication. Um, and you know, it the     
1:09:48     
implication is always that there's a problem in science in in science. I     
1:09:55     
think probably a lot of this is going to be like psychology or something psychology adjacent. Um but maybe it's     
1:10:03     
just again the complexity and the nature of     
1:10:08     
social and behavioral sciences that it's very complex and it's hard to kind of     
1:10:14     
isolate phenomena in a way that sort of like physics.     
1:10:19     
Okay. So um we observed modest variation in replication rates across disciplines     
1:10:26     
and you know depending on the discipline it ranged from 42.5% to 63.1%.     
1:10:32     
So you know depend you know maybe some disciplines it's really hard to replicate in others it's maybe easier to     
1:10:38     
replicate but really you don't get anywhere near 100% and you don't     
1:10:44     
necessarily get anything near 0% either. So um and then some estimates though had     
1:10:50     
a high uncertainty. So you know again we're making an estimate about this um     
1:10:56     
based on just this sample of things and it's I guess a representative sample um     
1:11:01     
but you know we're we're hovering around 50%. Kind of around that area.     
1:11:07     
The median Pearson's R effect size was 0.25 for original studies and 0.10 one zero     
1:11:14     
for replication studies. Uh which is of course you know there are replications in the literature and of     
1:11:22     
course we expect replications maybe from what we're saying here to not be as     
1:11:28     
robust as the original studies. So again, you know, we're finding this, we're kind of confirming this idea that     
1:11:36     
um the original studies are not uh great in terms of replication, but the     
1:11:41     
replications aren't great either for obvious reasons.     
1:11:46     
Um 13 methods for evaluating replication success provided estimates ranging from 28.6%     
1:11:53     
to 74.8% which is a median of 49.3%.     
1:11:59     
uh some decline in effect size and significance is expected based on power to detect original effects and     
1:12:06     
regression to the mean because we replicated only positive results. So you might be able to replicate a negative     
1:12:12     
result, but that's not that hard to do. I mean you do a poor job of like uh     
1:12:18     
setting up the experiment and oh I got a I got a negative result too you know you     
1:12:25     
have to run the experiment to get a negative result. I guess technically but um so you know having the positive     
1:12:31     
result that's sort of the thing that requires you to have     
1:12:37     
good experimental design. A negative result doesn't necessarily require that.     
1:12:42     
We observe that challenges for replicability extend across social and behavioral sciences illustrating the     
1:12:49     
importance of identifying conditions that promote or inhibit replicability. And again, this is assuming that you can     
1:12:56     
do this in the same way that we kind of have a mental model for.     
1:13:02     
So, you know, again, why do we care about replication? Well, one of the aims     
1:13:07     
of science is to discover regularities, statistical regularities and sort of     
1:13:13     
structural regularities. And one way to do that is to say if I run an experiment and I get a positive     
1:13:20     
result, if I rerun that experiment, I should get a similar result and I should     
1:13:26     
always get that result if this is a phenomena that's true or that's that's real. If it's not real, I might get a     
1:13:33     
positive result once and then a negative result again and maybe I keep getting a     
1:13:39     
negative result then maybe I get another positive result. And this is not trivial because basically when we do a statistic     
1:13:47     
when we assess statistical significance that's essentially what we're doing.     
1:13:52     
If we had say 20 experiments, uh we should expect if we have say like     
1:13:59     
um a 95% percentile um criterion     
1:14:06     
um that we should expect 19 of those experiments to be uh positive to be     
1:14:12     
successful to show the effect and one experiment that does not. So depending     
1:14:18     
on our significance criterion, we should expect out of those 20 experiments a     
1:14:23     
certain proportion of those to replicate. I mean that's essentially what we're saying when we do like uh     
1:14:29     
statistical significance. We should say for 20 observations a vast majority of them should be in     
1:14:36     
this direction and there may be some in the other direction. But the reason why     
1:14:42     
we have the uh significance criterion is because we want to say that like for the     
1:14:48     
most part this is true. There are always exceptions. So you know people have talked about um     
1:14:56     
statistical significance before. So there's this whole side debate about like the um the value of the looking at     
1:15:04     
statistical significance and you know how people do things like P hacking to     
1:15:10     
try to like uh make something statistically significant that otherwise wouldn't be. So there are all sorts of     
1:15:17     
problems there as well. But the idea is that we want to discover these regularities.     
1:15:23     
So we want to be able to replicate our results so that every time we do an investigation     
1:15:29     
we can get similar results and it should be reliable and if we especially if we     
1:15:35     
have something that that is um an application we want to make sure that it     
1:15:40     
hap that it's a a repeatable result. And so then you know they they talk     
1:15:46     
about this replication crisis and how a lot of published work will claim well it     
1:15:52     
doesn't claim replication it's just that they're published as positive results and a lot of times people don't question     
1:15:58     
that and they kind of run with the result and so this is a problem that we     
1:16:04     
have um especially in in things like cancer biology where the stakes are pretty high right we need to be if we     
1:16:12     
have a clinical trial there it's actually pretty important that we can replicate it and a lot of times we can't     
1:16:17     
and and I have thoughts about that um where you know it's it's like we're     
1:16:25     
dealing with very complex systems and a very in fact with cancer it's very um     
1:16:32     
u it's highly variable in terms of how you observe these things and so there     
1:16:37     
are a lot of things there that kind of work against really good experimental     
1:16:42     
results but anyways is um so they get into this. Popular explanations for the low observed     
1:16:49     
replication success rates include under reporting of negative or inconclusive evidence for claims,     
1:16:56     
high sampling error from small samples, a measurement error due to unreliable measures coupled with a statistical     
1:17:03     
threshold that serves as a publication filter. So there's this idea that like     
1:17:09     
sometimes when we uh to get things published we need to achieve a certain     
1:17:15     
statistical threshold of a p value. And so if we can't get to that sometimes     
1:17:22     
people will try to get to that using um you know less than rigorous methods to     
1:17:28     
get there. Um and this this is something that is maybe a problem because a lot of     
1:17:35     
publications won't publish negative results and if they don't publish negative results of course some people     
1:17:41     
don't get published and there's a whole incentive structure that is immobile in     
1:17:46     
this case. So you know this is where you have to publish positive results you     
1:17:52     
can't publish negative results. So there's pressure to get positive results even if it means sacrificing replic     
1:18:00     
replicability or you know just simply doing something more nefarious like     
1:18:05     
excluding samples that don't meet the you know that don't meet the statistical     
1:18:11     
threshold. So that's kind of one of the points there. Low rigor and quality control and     
1:18:17     
research design and measurement. So if your experimental design is poor     
1:18:22     
or you don't, you know, control for all of your compounds and questionable     
1:18:28     
research practices that inflate the likelihood of obtaining positive outcomes.     
1:18:33     
These factors are compounded by a research culture that rewards novel and interesting findings and discourages     
1:18:39     
error correction. Again, these are just these incentives that are misaligned with the ideals that we would like.     
1:18:47     
Replication failures are not necessarily due to the original findings having low credibility. Low replication rates can     
1:18:54     
also be due to false negatives or early design replications, selecting only positive results for replication and     
1:19:01     
differences between original and replication studies that are initially perceived as unimportant.     
1:19:07     
More broadly, there are conceptual challenges in deciding what a replication of a previous finding is and     
1:19:14     
how to assess whether replication attempt succeeded. So we sometimes, you know, even just using like meta-cience.     
1:19:22     
Um, you know, maybe meta-cience the problem is meta-cience. Maybe the problem isn't in the literature. Um, but     
1:19:29     
I, you know, that's something that is a little bit more that that's maybe requires a meta science. Um but I think     
1:19:39     
really um you this is just kind of an interesting kind of way to think about     
1:19:45     
our results that we read. Whenever we read a result you know is this something that is     
1:19:52     
um you know can we we trust this result as replicable or is this a one-off     
1:19:57     
result that is interesting but it's not going to we really have to think through this problem somewhere. Um,     
1:20:05     
interestingly I know there are a lot of people who uh critique benchmarking in     
1:20:11     
computer science. So benchmarking kind of suffer from the similar kind of problems we see here where you have two     
1:20:18     
programs and you benchmark their performance and a lot of times people are trying to optimize performance down     
1:20:24     
to like a couple decimal places and you know how how um effective is that     
1:20:32     
really? I mean, you can game those kind of statistics pretty easily. Um, and so,     
1:20:38     
you know, sometimes people will, you know, um, want to show that their     
1:20:44     
model is better performing than another model. So, there's a temptation there to sort of gain the system for your model.     
1:20:52     
Um, there are a lot of there are a lot of challenges in in benchmarking as well. And um I haven't gone and found a     
1:21:01     
critique a good critique of this but um maybe I'll do that next time.     
1:21:07     
So they go through this study here. This is uh table one papers and claims     
1:21:13     
selected by replication attempts by discipline. So they cover business, economics,     
1:21:20     
education, political science, psychology, sociology,     
1:21:25     
uh and then the total at the end. So we have um claims selected and replications     
1:21:32     
attempted. So they've selected a number of papers with claims     
1:21:37     
um and then they have that number there. So they're sampling. I think in psychology they have 950     
1:21:43     
in education they have 445 and there's a range of uh number between that papers     
1:21:50     
eligible for replication uh means you know which papers can we actually replicate the claims with so     
1:21:57     
that's a subset of those papers with multiple claims they're a smaller number     
1:22:03     
with that have multiple claims in them or testing multiple hypotheses and then     
1:22:09     
papers with a single claim volume which is the balance. So the so the papers     
1:22:14     
eligible for replication those are the ones that will be the replications that they attempt.     
1:22:21     
So not all of the claims can be replicated or they don't think they can or they won't. So they do a subset of     
1:22:28     
these and I don't know what the criterion for deciding that was. Um but     
1:22:33     
that's you know that that is up to the uh the team that that did the paper. So     
1:22:40     
um they had papers with replication started papers with replication attempts completed total replication attempts of     
1:22:47     
claims. So that's a smaller subset still and then unique claims of replication attempts. So this is how they kind of     
1:22:54     
divided this out. They took a bunch of papers from different fields. They examined their claims.     
1:23:01     
They then took each claim. actually they took each paper and they     
1:23:07     
then looked at the claims and they did they figured out which ones they could replicate and then they did the     
1:23:13     
replications um and they ended up with a much smaller subset     
1:23:19     
of of um replication of times completed. So     
1:23:25     
this is, you know, again where we have a bunch of things in the literature, we kind of winnow it down to things that     
1:23:32     
are sort of lowhanging fruit or easy to actually do in an environment. So we're getting like the kind of the simplest     
1:23:38     
experiments or the the most maybe the most important experiments. And so there     
1:23:45     
is this selection bias here uh to be aware of that is we're not testing every     
1:23:50     
claim. We're testing a subset of claims. And um yeah, so I mean, you know, there     
1:23:56     
there might be something to say about that where um you're kind of testing the     
1:24:02     
things maybe that are the least replicable or maybe they're the most replicable. It's not really clear. Um so     
1:24:10     
that's basically what we have here. So you're making um and if you look at the     
1:24:16     
numbers actually um I don't think there's a huge sort of bias towards any     
1:24:22     
one discipline. I think you know the I think psychology that's a little bit     
1:24:28     
more replicable or maybe you you had more attempts in     
1:24:33     
psychology than in other areas. So you had papers with replication attempts     
1:24:39     
completed 58 in psychology you had started with 950 papers with claims in     
1:24:46     
education you have 13 versus 58 and for education you had 445     
1:24:53     
papers so there's a little bias I think for psychology and because the team is I     
1:24:59     
mean Brian Nosk's a psychologist and the team probably knows psychology better     
1:25:04     
this is probably why you have this bias. So     
1:25:10     
again, you know, this is not like the experiments are behavioral experiments.     
1:25:15     
So they're not going to be widely wildly different from the typical psychology experiment. So that's kind of what why     
1:25:24     
um you know just just something to be aware of here. Okay. Um so for table one     
1:25:32     
uh representativeness across disciplines was maintained during identification and extraction of claims because we use     
1:25:39     
random sampling strategies. Most of the change in representativeness occurred owing to the non-random process of     
1:25:46     
selecting and starting a replication study. So education and political science decreased in relative proportion     
1:25:53     
of the sample and psychology increased. Okay, that's again what I just talked     
1:25:58     
about. Compared with the original sample of papers, the proportion of completed attempts of unique claims was within     
1:26:05     
3.5% for economics, education, political science, and sociology. And more notable     
1:26:12     
variation was observed for business and psychology. Representativeness of replication     
1:26:17     
attempts was relatively steady by year compared with the sample papers.     
1:26:22     
Um we selected papers and attempted replications in two phases with 139 of     
1:26:28     
the completed replications occurring from papers selected during the first phase and 25 from papers selected during     
1:26:35     
the second phase. Replication success rates were similar between the first and     
1:26:41     
the second phase. Okay. U this then is figure one which is     
1:26:46     
the replication success rates across 13 binary assessments for papers.     
1:26:53     
So what is this? Um this is where we have binary success     
1:26:58     
measures um and for different things and then proportion successfully replicated     
1:27:04     
according to measure percent. So these are the different sort of ways     
1:27:10     
in which uh I guess things are assessed.     
1:27:16     
Um so you have this measure of success. You have metaanalysis at the top which     
1:27:23     
is where you know I guess there are these different types of mechanisms or or or different types of measures that     
1:27:30     
they're binning things into when they're looking at how replicable those measures     
1:27:36     
are. So meta analysis comes out on top. Then you get small telescopes,     
1:27:41     
basian metaanalysis, replication effect and prediction interval, subjective interpretation,     
1:27:49     
replication base factor. Then skeptical p value is down the list.     
1:27:54     
Sum of p values is down the list. Correspondence test is right with the p values. Uh b factor is down below. and     
1:28:03     
then the original fact and replication confidence intervals. So the confidence intervals are at the bottom along with     
1:28:09     
base factor. So I'm not quite familiar with these success measurements, but     
1:28:16     
it's interesting that um sometimes baze and basian stuff comes out on top or     
1:28:24     
near the top and baze factor comes out low. confidence interval comes out low     
1:28:29     
and then correspondence tests which are usually um pretty weak statistical um     
1:28:36     
relationships come out with p value measurements. So I'm I you know I'm not     
1:28:43     
an expert at these in these different measurement techniques but it's kind of interesting how those are distributed.     
1:28:51     
Okay, so they talk about this a little bit more. Um, this problem highlights a     
1:28:56     
challenging problem or this project highlights a challenging problem. Replication success metrics can be     
1:29:02     
applied only to methods that meet their assumptions. So again, sometimes people use metrics where the assumptions aren't     
1:29:10     
met by the data. So this is something that again is maybe a problem in     
1:29:15     
replication is that people use different metrics or these metrics incorrectly and     
1:29:21     
that can always because metrics always have assumptions built in. So this is a problem which you know you would think     
1:29:28     
be corrected in peer review but oftent times is not. People will give justifications for using a metric that     
1:29:36     
maybe they shouldn't be doing. Okay. Um and so um in figure one we present 13     
1:29:43     
replication success metrics. Some are necessarily binary assessments of replication success or failure. Others     
1:29:50     
are simplified to provide a binary assessment for comparison. Okay. Uh across metrics replication     
1:29:57     
success rates ranged from 28.6% to 74.8%     
1:30:03     
with a median of 49.3%. of that number and 49.3%.     
1:30:08     
The observed variation highlights the impact of different assumptions underlying each approach. For example,     
1:30:15     
the highest estimate of 74.8% for the metaanalytic combination of the     
1:30:20     
original and replication evidence provides strong evidence of success     
1:30:25     
because it includes original studies that provided evidence of success and these tests are not independent of the     
1:30:31     
original evidence. Variation in the observed replication rates are affected by both the     
1:30:36     
assumptions of the binary assessment and the subsample for which the metric could be used.     
1:30:43     
Figure two presents correlations between each pair of binary assessments or replication outcomes which both     
1:30:49     
methods can be applied. So that's this figure here. Um and then this is where     
1:30:55     
we have these different metrics kind of compared to one another and then we have     
1:31:01     
this distribution of all 144 correlations. So this is just kind of thinking about     
1:31:07     
these correlations between different metrics and how these are distributed.     
1:31:12     
So um you know uh let's see correlation     
1:31:18     
values are to the right of the diagonal over here. Um and so     
1:31:24     
what does he say about that? Uh figure two presents correlations. Spearmman correlations were positive and     
1:31:31     
relatively high with some exceptions. For example, analysts almost always     
1:31:36     
interpreted success on the basis of statistical significance as reflected by a correlation of 0.90.     
1:31:44     
Whereas measures that use confidence or prediction interval show relatively strong correlations with each other. And     
1:31:51     
so this is where again we have this different types of measurements having     
1:31:56     
um you know uh sometimes they're they lead to high replication, sometimes low     
1:32:02     
replication, sometimes specific types of measures um are interchangeable     
1:32:10     
but also if you're using other measure other types of measurements they don't aren't as consistent. So sometimes you     
1:32:17     
know you'll have a replication where you use say like a confidence interval and     
1:32:23     
another one where you use a basian method and you're going to have a different result.     
1:32:28     
Is that due to the experimental design? Maybe not. Should we do that kind of test? Perhaps     
1:32:35     
because sometimes it can tell us about how robust a result is.     
1:32:42     
And so again this discrepancy in different methods using different methods for the uh different studies is     
1:32:51     
uh partly because they are treated because they treated replication outcomes both smaller and larger than     
1:32:56     
the original outcomes as failures to replicate. So there is this aspect of     
1:33:02     
statistical testing um in their effect on replication.     
1:33:09     
Okay. So the discussion here is about half the findings from a sample of     
1:33:15     
social behavioral science papers published between 2009 and 2018     
1:33:20     
replicated successful with variation and success estimates across 13 binary     
1:33:26     
assessments and effect size comparisons. variation in replicability across     
1:33:31     
disciplines was modest with replication rates between 42.5 and 49%     
1:33:38     
um on for fields that had more than 20 replications. These findings are     
1:33:44     
consistent with the cumulative evidence across systematic replications um and they illustrate that there is     
1:33:51     
substantial uncertainty in estimating replicability. Okay, so there's some conceptual,     
1:33:57     
methodological, and inferential challenges to assessing replicability.     
1:34:03     
Uh, conceptually, it can be challenging to attempt a replication. Strictly speaking, there's no such thing as an     
1:34:09     
exact replication. Of course, we want to get it as close as possible, but we can't always replicate the exact     
1:34:16     
conditions under which the data were collected. Um there's different there always     
1:34:23     
differences in units, treatments, observations, and settings. Researchers     
1:34:28     
must make decisions about how to conduct a good faith replication on an original claim.     
1:34:35     
Um, so for example, should a present- day replication of a 2009 US study of     
1:34:40     
political behavior that use President Obama as a stimulus, use Obama again or     
1:34:46     
the current US president or use the leader of the participants nation? So if     
1:34:51     
you study people in another country, are they going to respond the same way as the people within the country where the     
1:34:58     
the leader is from? So this again is like something that you do a study and     
1:35:05     
it's interesting for what you want to find but then it might be very highly contextual and replicating that study     
1:35:13     
may not hold. So you know but this is interesting because a lot of times we will take a study like this and     
1:35:20     
extrapolate out the effect. So you you you might say something of you know does     
1:35:26     
this result say something about the context of the United States and     
1:35:31     
President Obama or does it say something about more generally uh you know     
1:35:38     
electorates around the world and their respective leaders? It may be very     
1:35:43     
constrained to the US context. It may not. So this is a problem that you have with     
1:35:49     
studies when they're set up and studies when they're replicated.     
1:35:54     
Um another thing we have to worry about is is to whether or not the theoretical commitments are correct.     
1:36:02     
So sometimes we have a theory and you know this is something that um     
1:36:08     
the theoretical commitment might be wrong where you have sort of uh you     
1:36:13     
interpret your result in a certain theory and of course it's the wrong theory to interpret it with.     
1:36:20     
Um yeah so then methodologically it can be     
1:36:25     
challenging to determine how to measure replication success. So again we have these these measures of these metrics     
1:36:32     
that they use but again um you can't use a single metric universally and a lot of     
1:36:39     
times it depends on the measurements that the original studies used and     
1:36:44     
that's that's there are a lot of problems there. Then inferentially it can be challenging     
1:36:50     
to determine whether original and replication studies produced the same outcomes. Each of the replication     
1:36:57     
assessment criteria strengths and weaknesses and may be based on different assumptions.     
1:37:02     
For example, metrics combine original replication evidence that are not independent tests     
1:37:08     
and have relatively low sampling error. Uh these tended to suggest the highest success rates. So again um tests that     
1:37:18     
are not um okay uh these tended to have suggest the     
1:37:24     
highest success rates they might be useful only when it is safe to assume no selection or publication bias and the     
1:37:31     
emphasis is on cumulative evidence. So again um different types of studies may     
1:37:37     
be more amendable to replication um     
1:37:43     
and different types of ways to study replication are only useful in certain     
1:37:50     
contexts. So you don't want to assume that studies were free of selection or     
1:37:55     
publication bias when they were and you don't want to select a study that has selection or publication bias.     
1:38:04     
Okay. In summary, the question did it replicate can be difficult to answer. Fortunately, the answer for any given     
1:38:10     
study does not matter much in the long run. Research is conducted on a study bystudy basis. Replicability is     
1:38:16     
established by a cumulative body of evidence. So sometimes when we have a     
1:38:23     
hypothesis or a theory, it's not so much that it's whether it's replicable or not. It's that if     
1:38:30     
you know there are hundred studies in a certain area and they all yield different results, we     
1:38:36     
can kind of figure out what the right answer is by looking at the accumulation of results. In other words,     
1:38:44     
if a study is um published and it turns out that it's not true, that the result     
1:38:50     
is maybe a one-off, it doesn't really hold to true theoretically,     
1:38:56     
then we should be able to detect that by looking at a hundred different studies and looking at the direction in which     
1:39:01     
they point. If another if a stud is pointing in the other direction, then maybe we just are skeptical of it and we     
1:39:09     
don't need to worry about replication because we can kind of figure out the correct direction of what these findings     
1:39:16     
suggest. Okay, I think that's enough on that     
1:39:22     
paper. Um I don't know if Morgan had anything to say about that since he posted it in the     
1:39:27     
chat. Um interesting to hear his feedback on it.     
1:39:33     
Well, yeah. I mean, obviously, you know, it's um it's super important to to talk     
1:39:41     
about these issues. you know, um Brian and the the the center there has     
1:39:49     
definitely been a big part of, you know, I'd say helping move that conversation     
1:39:55     
forward in productive ways and um     
1:40:00     
yeah, so it's uh     
1:40:06     
uh I'm still I like uh greetings greeting students and things right Yeah.     
1:40:13     
But um uh yeah, like uh     
1:40:20     
no no no major um     
1:40:29     
comments on it, but you know, just like so valuable and so um     
1:40:37     
um just nice to see how the I forget They um I don't know if you've ever seen     
1:40:44     
a podcast of decoding the gurus. No, I've not seen it. Uh I highly recommend I mean you know     
1:40:53     
it's like some people who um     
1:40:59     
you know it's like two like I think one's an anthropologist and one's a psychologist but like like a methods     
1:41:07     
psychologist you know. Yeah. And um     
1:41:13     
anyway, it's like they they just had a recent um     
1:41:19     
yeah, they they're usually doing what they say, you know, decoding the gurus. So, it's kind of like taking apart     
1:41:26     
people and make outlandish not outlandish claims, but like science     
1:41:32     
claims, but they kind of take like those things apart. But they recently had a     
1:41:40     
researcher who was very much just talking about how     
1:41:46     
discussions around rep replicability have changed since like you know over just 10 years     
1:41:54     
and like you know in a good way and     
1:42:03     
yeah I remember that like when people started talking about this it was like people were very defensive about I mean,     
1:42:08     
as you might imagine, um, you know, people were defending their turf. They thought that they, you know, done their     
1:42:15     
due diligence and then there these people who say, "Well, look, we have this crisis." And so, yeah, but I think there's been     
1:42:22     
more acceptance more recently about like the need to be sort of rigorous in this area.     
1:42:31     
Yeah. Yeah. Yeah. Yeah. For for sure, for sure. Um and uh uh you know there's     
1:42:41     
like kind of a second you know conversation of     
1:42:46     
you know neuro imaging people who are doing kind of like more     
1:42:52     
statistics at scale which but it's but it's still still very similar. to like like a lot     
1:42:58     
of overlapping concerns and issues even though like the conversation's a     
1:43:05     
bit more sometimes is a bit more technical, right?     
1:43:11     
Yeah. Uh yeah. I mean like there are a lot of areas of science you could say     
1:43:17     
that yeah there's a I mean the term replication crisis always implies like     
1:43:23     
kind of oral crusade or something. So maybe it's not a crisis, but definitely     
1:43:28     
it's like we don't have good community standards for these things. We I mean we     
1:43:34     
we are beginning to have those and that's one of the the impeti uh behind     
1:43:39     
um different types of toolboxes and you know virtual machines and things like     
1:43:45     
that that we've talked about with um replication neuroscience where you're     
1:43:50     
building tools for people to more easily standardize their results. So you're not     
1:43:56     
just kind of home brewing a solution every time you need to do something. You can make sure that you have good     
1:44:03     
control over those things. And um I think that that improves the the the the     
1:44:09     
results because it just like you know you you go through this pipeline, you're verifying everything and it's not a huge     
1:44:17     
cost to the labs doing the work.     
1:44:22     
Yeah. Yeah. Yeah. All right. Like I said, the whole     
1:44:27     
another kettle of fish are benchmarks in computer science. So that's     
1:44:33     
and I know that like we think that benchmarks are sort of a lot easier than     
1:44:40     
like we say you know well social science is pretty hard and it's got a lot of interaction but like in computer science     
1:44:47     
surely we can just kind of get these benchmarks and they should be you know pretty easy to to understand and     
1:44:54     
calculate. But again, you know, you have these problems where you kind of make up your own methods or you um maybe want to     
1:45:02     
see something. There's a there's a sort of confirmation bias that if something     
1:45:07     
is true, you want that to be true. So that's what happens. Um but again, you know, like um I think     
1:45:15     
it is like really about well, it's about community standards, but a lot of times it's also about cost     
1:45:22     
to the researcher. So sometimes these replication to ensure replicability it's     
1:45:28     
expensive. It's like you have to spend the time you have to spend sometimes the money to do these things and not     
1:45:33     
everyone can not every group has the the resources. So it just makes it if you     
1:45:39     
make it easier for them to comply it's not that hard to do you know.     
1:45:46     
Yeah. I would say, you know, I think I think ARC is is an example, you know, the AGI     
1:45:56     
ARC um is an example where     
1:46:03     
like our our kind of own understanding is is also a limitation of the     
1:46:10     
benchmarks that we create. Yeah. like like um     
1:46:20     
you know we we can't um we can't define     
1:46:27     
good intelligence tests for these models um when we have trouble creating them     
1:46:34     
for ourselves or like right creating creating     
1:46:40     
uh unbiased benchmarks there like you know what I mean?     
1:46:46     
Yeah. Yeah. And it's like if we don't understand intelligence very well, we can't make good benchmarks.     
1:46:53     
Yeah. Yeah. Yeah. I mean Yeah. I mean I I see it I see it in doing all this     
1:47:00     
agentic coding where you know like the I     
1:47:06     
see it in the issues of of testing on synthetic data. Oh yeah.     
1:47:12     
because you know it's like like it can look complex. It can it can look um     
1:47:21     
you know to the eye or you know these other things but like it's really just     
1:47:27     
as good as your you know generating function right and you know like you know so if you     
1:47:35     
give it some real data and suddenly everything's off it's like you've obviously not got something in your     
1:47:42     
synthetic uh generator Um     
1:47:47     
right yeah that's that's a great conversation     
1:47:53     
to kind of continue. Um so um we have time for one more thing.     
1:47:59     
Um so I I did want to go over a paper really quickly that um is of interest     
1:48:05     
maybe to ecological psychology types and probably I think probably Jesse would     
1:48:11     
enjoy this. Um this is a paper that's now published in um this book     
1:48:17     
neurocognitive foundations of mind. This is a neuro ecological architecture     
1:48:23     
situating situated cognizing systems. This is Luis Favlla who we've talked     
1:48:29     
about before in cognition futures and some other contexts. Um     
1:48:35     
let me go over the abstract and then we'll go into the paper. Um so uh the ab     
1:48:42     
so this is a p uh this is a chapter in this book. Um and so the abstract read     
1:48:49     
situated approaches to cognizing which is defined as distributed embodied and     
1:48:55     
extended cognition or you know different ways of doing cognition basically have     
1:49:02     
exerted an immense influence on the cognitive and psychological sciences.     
1:49:07     
So distributed cognition is often thought of as different agents doing     
1:49:13     
cognition and then kind of coming together in groups. Uh embodied     
1:49:18     
cognition of course is doing cognition with reference to a body. So the the     
1:49:24     
brain or the agent is in a body and that body conditions how that cognition is     
1:49:29     
expressed. Then extended cognition is extending cognition into the world     
1:49:35     
through artifacts or through the environment. Um so this is you know these are things     
1:49:41     
of course that are situated in a context um that are hard to separate from their     
1:49:46     
context. So and you know when we talk about experimental replicability if we want to make an experiment like     
1:49:53     
this replicable we don't need to just um replicate the the sort of the highly     
1:49:58     
contrived experimental conditions but we need to put people in a similar environment. So this is the whole sort     
1:50:05     
of debate between very controlled experiments in the lab and these more     
1:50:11     
naturalistic experiments where it may not be as highly controlled but you're in the right uh in the right environment     
1:50:18     
in the right context and so that's maybe what matters more since such accounts typically do not     
1:50:25     
prioritize neurobiology their impact is felt far less in neuroscience. So, uh, when we talk about     
1:50:31     
extended and embodied and and distributed cognition, usually we're not thinking about this in terms of     
1:50:37     
neuroscience. We're thinking about this in terms of like behavior. And in     
1:50:42     
cognitive science, it's usually like some behavioral observation where you     
1:50:48     
put people on a in a airplane cockpit and you look at how they uh make choices     
1:50:53     
on on a a control panel and then you record their responses. and there's no     
1:50:59     
neuroscience necessarily involved in it. So this is where we want to sort of unify um ecological psychology with     
1:51:08     
neuroscience and have this neuroecological architecture. The influence in ecological psychology     
1:51:16     
which stresses the role of ecological information which is of course things like uh flowing visual cues and other     
1:51:23     
types of dynamical systems type inputs or things that lead to dynamical systems     
1:51:30     
from the environment. We have this role of ecological information that dynamically unfolds at the scale of     
1:51:37     
organism environment systems. that's critical for cognizing     
1:51:42     
and this is something that is um you know something we need. A substantial     
1:51:48     
criticism of this approach concerns the apparent absence of the brain's contribution to cognition     
1:51:54     
in so far as other situated approaches remain influenced by ecological psychology. Such criticisms undermine     
1:52:01     
other approaches as well. The primary aim of this work is to present a framework for integrating neuroscience     
1:52:08     
with situated approaches namely the neuroecological nexus theory or next. So     
1:52:15     
this is the theory he's proposing here. To be successful uh next must both     
1:52:20     
maintain the core principles of ecological psychology and provide testable hypotheses concerning the     
1:52:27     
neurobiological contributions to intelligent organism environment events.     
1:52:33     
The latter is proved provided by contemporary neuroscience work on the neural manifold hypothesis     
1:52:40     
uh in hypothesizing that situated cognition can be explained by interactions among environmental or     
1:52:48     
ecological information and classes of neuronal manifolds. Next provides a step     
1:52:54     
towards a more complete understanding of mind. One that spans the cognitive and psychological sciences as well as the     
1:53:01     
neurosciences. So this is something that unifies two different areas.     
1:53:07     
This is the preprint. Um and so it gets into a little bit of history here. Uh situated approaches to     
1:53:15     
cognition generally adhere to the view that intelligence systems are always embodied and embedded. So this is     
1:53:22     
something that you know again when we talk about situated cognition which is     
1:53:27     
usually a sort of a shorthand for these sort of naturalistic experiments or a     
1:53:33     
theory that we use to interpret naturalistic experiments. We're usually dealing with intelligence systems. It     
1:53:41     
could mean the, you know, a human operator or um, you know, an animal in a     
1:53:46     
in a naturalistic environment or it could mean an AI system or an automated     
1:53:52     
system in a body in a naturalistic environment or something like that. So it could be like a a robot in a     
1:53:59     
naturalistic environment or an AI in a naturalistic environment like an     
1:54:05     
autonomous vehicle or something like that. And so we have to start thinking about     
1:54:10     
these theoretical constructs like embodiment, embeddedness,     
1:54:15     
example. Uh though there is variety and controversy in how the term is used as a     
1:54:21     
starting point embodied refers to the idea that cognition requires a body to occur. So embodied     
1:54:28     
means you need a body whatever a body is. And so a body could be like you know     
1:54:34     
our bodies where we have relations between the different parts of our bodies. It could be like a vehicle. So a     
1:54:43     
vehicle has specific movements. It has specific control imperatives. And so you     
1:54:49     
know those you have to operate within that that um context. So you have a     
1:54:55     
vehicle let's say moving around an environment. It can get to different points by, you know, selecting different     
1:55:02     
control mechanisms like steering or acceleration     
1:55:07     
or reversals and they create different out behavioral outputs. And so these     
1:55:15     
behavioral outputs then     
1:55:44     
So these different behavioral output sort of determine what the intelligent behavior looks like. So if you only have     
1:55:51     
a subset of control me control imperatives available to you, your you     
1:55:56     
know it doesn't matter what your intelligent behavior is sort of deducing     
1:56:02     
from the environment. The outputs are the important part and so the outputs might limit significantly what you can     
1:56:09     
actually express as a behavior. So this is embodiment and this is of     
1:56:14     
course important there whole conference as an embodiment in say like robots and     
1:56:20     
automated systems but it's easier said than done. There are a lot of open questions and embodiment and how to     
1:56:26     
characterize that visav these intelligent controllers. In a more specific sense, this means     
1:56:33     
that there tends to not be a sharp distinction between cognition and non-cognition in the body and related     
1:56:40     
the sensory motor processes are important for cognition. So, um we need to really kind of we can't just think of     
1:56:47     
the body as kind of a conduit for intelligence or for cognition. The body     
1:56:52     
actually interacts with intelligence. So like you acquire information through     
1:56:58     
your eyes or through your hands and you don't require information     
1:57:04     
um you know through your stomach you know it's it's not the conduit and but     
1:57:09     
there's an interaction there. So sometimes your visual acuity is controlled by your central nervous     
1:57:16     
system and you know there connections between the body and mind that need to     
1:57:22     
occur here and this is true of any kind of a controller with any kind of u body.     
1:57:28     
So it could be like a autonomous vehicle controller. It has to have interactions     
1:57:34     
with the vehicle. And in fact, we have that in in autonomous vehicles with sensor systems across the vehicle.     
1:57:43     
In a more specific sense, this means there tends not to be a sharp distinction between cognition and non-cognition.     
1:57:51     
And related, the sensory motor processes are important for cognition. There is a spectrum and how weak or     
1:57:57     
strong these positions are. At the weaker end of the spectrum, cognition is primarily a brain event. But the brain     
1:58:04     
areas associated with the body's sensory motor processes play important roles in causing and enabling even higher forms     
1:58:11     
of cognition such as abstract reasoning and language. At the stronger end of the spectrum,     
1:58:17     
cognition is not primarily a brain event with the body's non-neural structures     
1:58:23     
and processes causing and con constituting even those previously mentioned higher forms of cognition. So     
1:58:31     
this is like where we talk about weak and strong embodiment. Uh weak embodiment is where we kind of think of     
1:58:39     
the brain as being within a body. Yes. But the brain is doing most of the work     
1:58:44     
and the body is just there as sort of an instrument of the brain. In strong     
1:58:49     
embodiment, the body is actually doing most of the computation or it's     
1:58:54     
balancing out with the brain or the controller. So you know this is like a debate within embodiment that's     
1:59:01     
important here because you know you have to deal with that you know the role of the body basically.     
1:59:08     
So this is where we think about embodiment and it's important to kind of     
1:59:14     
ve be very specific what we mean by embodiment. Okay. So um and then we have to go back     
1:59:21     
when we think about ecological psychology we need to go back to behaviorism and think about sort of our     
1:59:27     
route out of behaviorism. So when we kind of came from behaviorism     
1:59:33     
and moved into the cognitive revolution, we were kind of left with some     
1:59:41     
intellectual baggage. Some of that is where even from the earliest days of     
1:59:47     
psychology and behaviorism there was some form of functionalism     
1:59:53     
which is means that like the way we thought of all mental processes was primarily functional meaning that     
2:00:00     
something did something else. So when we think about these interactions between body and brain or body and controller     
2:00:07     
we're always thinking in terms of functionalism. So it's like what is you know     
2:00:13     
or why does this behavior exist? It must exist for a reason. It's probably to     
2:00:19     
adapt to its envir, you know, uh to allow the organism to adapt to its environment. And so this is of course     
2:00:26     
both good and bad in a lot of ways because sometimes functionalism can constrain us and sometimes it serves as     
2:00:33     
a useful explanatory device. So this kind of uh found its way through     
2:00:39     
behaviorism and then it found its way sort of into the cognitive revolution as well. Um and so um but in behaviorism     
2:00:50     
specifically it had three main commitments. The first is that psychology is the science of behavior     
2:00:57     
and that the sources of behavior are basically external which is means that     
2:01:02     
they're in the environment. um and that when you talk about mental     
2:01:08     
concepts, you shouldn't and rather you should talk about behavioral concepts.     
2:01:14     
And um this actually is one of the differences between cognition or the     
2:01:20     
cognitive what would become cognitive science and ecological psychology is that ecological psychology sort of     
2:01:27     
retained this aspect of the source of behavior which is that it's external in     
2:01:33     
the environment instead of internal to the mind. And so this is kind of describing this distinction between uh     
2:01:42     
weak and strong embodiment. Um and so then you know we kind of talk a     
2:01:48     
little bit about the cognitive revolution going through this history and then of course the position of     
2:01:54     
Gibsonian ecological psychology within that. And of course uh Gibbs sort of     
2:02:00     
Gibsonian ecological psychology bridges this gap between perception and action     
2:02:07     
and sort of behavior or or some of the things we think about in cognition and behaviorism and some of features of     
2:02:13     
behaviorism. And there's been there have been a lot of applications of ectoological     
2:02:18     
psychology um to development to human machine interaction to virtual reality and etc.     
2:02:27     
And so then again, you know, in ecological psychology, we think of perception as being direct, meaning that     
2:02:36     
um you know, we're really kind of drawing from ecological information and we're building uh our models based on     
2:02:43     
that the information is out in the environment and not necessarily originating in in the brain or in the     
2:02:50     
mind. Um and so you know we we have different ways of you know dealing with     
2:02:56     
perception that's you know or we treat perception is direct. It doesn't rely on any sort of intermediate representation.     
2:03:05     
Um and then uh so you know again     
2:03:15     
okay then second perception and action are continuous. So again, this is where     
2:03:20     
you know in a lot of psychology experiments, we present these discrete trials and we repeat stimulus     
2:03:27     
presentation over and over again. In an ecological uh setting, perception and     
2:03:33     
action are actually continuous. They flow and the order of those stimuli are     
2:03:40     
very important in terms of acquiring that information. So you can't just present things in these discrete     
2:03:48     
uh discontinuous trials. They have to be in this order in this continuous flow.     
2:03:54     
And so this is actually quite a big challenge to a lot of experimental     
2:03:59     
designs because if we have like say a um a naturalistic design, we might put an     
2:04:07     
agent out into the environment and let them interact with the environment. We get this ecological information, this     
2:04:13     
continuous information. We get this perception action loop that forms. But     
2:04:18     
that action is quite unique to that set of interactions. So as you can see, this is very hard to     
2:04:25     
square away with replication because every time you run the experiment, the     
2:04:30     
flow of information from the environment will be somewhat different. I mean, even if you have the same environment, a     
2:04:36     
highly controlled environment, it will be somewhat different. But this is necessary to understand the     
2:04:43     
true nature of a perception action loop. And it kind of speaks to how maybe you know the way we think about doing     
2:04:51     
experiments does not square away with the needs to understand how the mind     
2:04:57     
works or how behavior works. And then third we talk about     
2:05:04     
affordances. And so as a consequence of perception being direct and the continuity of perception and action, it     
2:05:11     
follows that detected ecological information can specify meaningful opportunities for action, namely     
2:05:17     
affordances. In short, affordances are perceivable opportunities for behavior. So they're     
2:05:23     
just features within an environment or um you know somewhere where you where     
2:05:29     
you kind of latch on to them. So they're kind of like intuitive points where you can kind of pick up. So if you have like     
2:05:36     
for example a door, if you see a handle to the door, you learn that that handle     
2:05:42     
is good for either pushing or pulling the door on a hinge. So you learn this     
2:05:47     
in development. You interact with the door and once you interact with the door, you get an intuition for how it     
2:05:54     
operates. And so any door that you encounter, you try to to push or pull it     
2:05:59     
with the handle. Now if a door maybe slides along the the track a track and     
2:06:05     
you try to do that, then you have problems generalizing. But if a door always behaves the same way, then you     
2:06:11     
just simply use that intuition to guide the action and you can successfully     
2:06:17     
generalize an information. So Gibson talked a lot about affordances.     
2:06:23     
They're both objective and subjective properties of an object. And this this     
2:06:29     
is, you know, it's sort of a unique way to look at generalization in in training     
2:06:35     
and intelligence. So if you have an agent that needs to generalize     
2:06:40     
something, you know, or some pattern in the environment, if it's an action type of pattern, like um if you're if a robot     
2:06:49     
is trying to move a door or throw a ball or do something with something, um it     
2:06:55     
needs to actually go through the action, try out different things and and have     
2:07:01     
build this intuition of what this sort of thing does and then it and um apply     
2:07:07     
that more broadly to other classes of similar thing and that's how it actually would learn. It's not going to learn     
2:07:14     
from presenting all possible options as to how this thing is used because first     
2:07:19     
of all um it can't necessarily select from those options and secondly um     
2:07:27     
you know you can't um you can't really test those out in the     
2:07:34     
environment that you're in. It's very going to be very hard to do that. So this is um why a lot of robots have     
2:07:41     
problems with tasks that seem effortless to us because we've sort of automated     
2:07:47     
we have these sort of automated or um procedural behaviors     
2:07:53     
um that we don't think about how we execute it. We just kind of learn the the um sort of the procedure and we     
2:08:00     
internalize that. Okay. So uh fourth psychology is about     
2:08:06     
the organism environment system. So we have to have the system of both the organism and the environment. This is     
2:08:12     
this extended cognition where things are offloaded to the environment where things are you know we extend our     
2:08:19     
cognition into the environment and we use the environment and our mental models interchangeably.     
2:08:27     
Okay. So this just kind of goes through this history and talks about sort of situatedness and then it sets up his     
2:08:34     
neuro neuroecological cognitive architecture. So this is the neuroecological nexus theory. Um and so     
2:08:42     
next is appropriate for the investigation of cognizing organism environment systems that have nervous     
2:08:48     
systems. Since cognitive systems are always situated, next is committed to the position that such systems     
2:08:55     
necessarily include organisms which are embodied of course that are tightly coupled with or constituent by     
2:09:02     
their ecologies. That's embeddedness. So that you know you have organisms that     
2:09:08     
have a body but they're tightly embedded in these ecologies or these environments. The nexus part refers to     
2:09:15     
both the framework as a point of convergence for ecological psychology and neuroscience     
2:09:21     
and as a nexus that constitutes the primary causal and or constitutive links or junctions that connect the various     
2:09:28     
elements of a cognizing organism environment system. So next is defined by five hypotheses.     
2:09:36     
Hypothesis one is that the organism environment system is the privilege spatiotemporal scale to understand     
2:09:43     
cognition. So we don't care about like the     
2:09:48     
uh details of the brain, we care about the organism and the environment     
2:09:53     
but we also care about this multiscale nature of the problem. So sometimes we want to drill down to neuronal activity     
2:10:01     
and we want to have this information but we want to link ecological psychology in     
2:10:08     
the environment with neuronal activity in the brain. And so we need to     
2:10:14     
establish this sort of organism environment system but then have the     
2:10:20     
access to these uh more detailed scales in the brain.     
2:10:25     
Hypothesis two is that neural population dynamics generate the relevant states for cognizing. So this is where we have     
2:10:32     
these population dynamics that are at a lower level of um organization.     
2:10:39     
Um and so we instead of sort of thinking about cells as just neurons, we need to     
2:10:46     
think about neural populations. And so a lot of times in cognition neural populations are the things the scale of     
2:10:54     
interest where where neurons work together to produce representations and     
2:10:59     
their activity will you know tune those representations accordingly. Um so     
2:11:04     
there's a lot of uh theory and experiment behind that a neuropul     
2:11:11     
group that has been selected for over species development time scales. So you have specific populations of cells in     
2:11:18     
the visual cortex that are tuned to visual to extract things like columns     
2:11:24     
uh stripes blobs and then that feeds into higher level representations of     
2:11:30     
images. You also have populations in sensory motor cortex that are tuned to     
2:11:36     
different limb movements, directions of limb movements, things like that.     
2:11:42     
Um, hypothesis three is that cognizing is based on lowdimensional neural dynamics. So, this is where this     
2:11:48     
manifold comes in and and manifolds are sort of the current theory of how uh     
2:11:56     
neuronal signals are organized. Um, you know, the thinking is that there's this     
2:12:01     
topology or this this representation that forms a topology. Um so you have     
2:12:09     
these highdimensional structures and lowdimensional manifolds. And so um     
2:12:16     
there's a mapping between the two that's what we call homeomorphic which means that they share the same     
2:12:22     
structure even though they look very different. So that's kind of the a tool     
2:12:28     
we can use to understand representations of you know large conceptual spaces in     
2:12:35     
lowdimensional um structures.     
2:12:41     
All right. And then of course it get it gets into a lot of things about the neurommanifold hypothesis and how things     
2:12:49     
that say this rat is interacting with the environment moving around the environment are represented in the brain     
2:12:57     
as these neural manifolds and then this was represented by um a topological     
2:13:03     
structure like a Taurus. And so you would have like this these movements and     
2:13:09     
these interactions encoded as the shape and then you explore that area of the     
2:13:15     
shape through neuronal activity and you know everything kind of maps to this     
2:13:22     
Taurus which is the representation of the environment. Um yeah so then this is again this is a     
2:13:30     
hypothesis four is that the body organizes into lowdimensional synergies. So this is uh going back to synergetics     
2:13:38     
from Kelso which is where you have limbs that sort of are controlled together     
2:13:44     
into groups, muscles that are controlled together into these synergetic groups     
2:13:49     
and these groups then act as sort of you know outputs for the neural manifolds.     
2:13:56     
So a lot of times um you can take a space and decompose it     
2:14:01     
into a manifold itself. So there's this uncontrolled or unconstrained manifold     
2:14:07     
hypothesis that uh you know basically breaks the environment down into a configuration     
2:14:14     
space. If you have like say a workspace in front of you like a desk,     
2:14:19     
how do you have to move your limbs to reach every part of that space? And     
2:14:24     
there actually are quite a few options if you were to consider every     
2:14:31     
um possible movement as an individual degree of freedom. But of course, our limbs don't operate like that. Our limbs     
2:14:38     
operate as sort of these grouped muscle synergies, these grouped um limb     
2:14:44     
synergies. And so our limbs move in certain directions and we have access to maybe a subset of     
2:14:54     
movements to reach every part of that space. So when we move our arm, we don't, you know, bend our wrist and bend     
2:15:00     
our arm the other direction or elbow the other direction. We actually kind of     
2:15:06     
everything moves in a coordinated way so we can reach different parts of that space. And so there are a lot of     
2:15:13     
different uh mathematical tools that allow us to decompose these spaces and     
2:15:19     
suggest optimal placement of objects and things like that. And of course this holds true for most things in the     
2:15:26     
environment where you know the brain actually computes sort of the most     
2:15:31     
efficient path to a target. And it's it's a really interesting um dynamical     
2:15:38     
systems theory underlying this. And then hypothesis five is that cognizing     
2:15:44     
fundamentally emerges at lowdimensional states of the organism. And so next claims that cognizing is a     
2:15:51     
multiscale phenomena that emerges from system systematic relationships among brain, body and the world. So each     
2:15:58     
spatiotemporal scale is highdimensional but the principal structure of each is low dimensional.     
2:16:04     
Okay, so this is something where um you know we're working from these uh neural     
2:16:11     
populations. We're working from these uncontrolled manifolds that uh describe     
2:16:17     
body synergies acting in the world. And then we can from there build a model of     
2:16:23     
action in the world from neural populations. And so this is um an example here of a     
2:16:32     
little rodent in a burrow and it's trying to navigate its way out of the     
2:16:37     
burrow and it's building this representation of the environment and it's then acting upon it and it's     
2:16:45     
producing these uh muscle synergies that allow it to reach different points in     
2:16:50     
the environment. and it has this model of an unconstrained manifold or an uncontrolled manifold that tell it kind     
2:16:57     
of the best places to go for things. It's a nice paper because it it stitches     
2:17:04     
together a lot of ideas into what is essentially a cognitive architecture. Um     
2:17:09     
there isn't a formal architecture program that he's producing here, but I think you can see the logic in a lot of     
2:17:16     
this. Okay, so that's that paper.     
2:17:22     
All right. Um, so I think that's all for today. Um, thank you for attending.     
2:17:27     
Thank you for hosting this meeting. Yeah.     
Saturday Morning NeuroSim, 4-11
