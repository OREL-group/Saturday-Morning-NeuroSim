## Meeting Recording

[YouTube link](https://youtu.be/Pc_yv5ILNBk)

## Mastodon thread

[link](---)

## Feature Videos

[System 0-1-2-3 for Embodied Robotics](https://youtu.be/1n5brb0I2vI)

[Going on a Developmental Visual Diet](https://youtu.be/eP8tJ-PV2y4)

## NOTES


## TRANSCRIPT
0:06     
church.     
0:31     
Hello. How is everyone today?     
0:39     
Okay. In Paluma trying to find a coffee shop.     
0:46     
Uh Justin Baron, welcome. Morgan, welcome.     
0:52     
Okay. Yeah. All right. So, why don't we get started? Um,     
0:59     
so I'm going to talk about our meetings first and then I'm going to go over some things that Jesse and Morgan shared in     
1:06     
the chat and then we will um go from there.     
1:11     
So the first thing we talked about uh this week or the first meeting that we had this week was uh divorm     
1:19     
and that was on Monday and we had a little conversation um     
1:25     
before we got into the preview of the netai conference. So this is the netside     
1:32     
conference for 2026 being held in Boston sponsored by     
1:37     
entropy and complexities journals and um they're you know basically put     
1:44     
the moments from the meeting on blue sky. So I haven't gone back to the feed. I think     
1:51     
I uh post reposted a couple of things from the conference but I'll have to go     
1:57     
back and look and see if there was anything really of note. So there were     
2:02     
um a number of interesting keynotes. Uh uh uh Sturgats and Watts gave a talk uh     
2:11     
Barb and Elbert gave a talk. These are of course the authors of two seminal papers that came out in the late 90s on     
2:18     
network science. Um there's also a lot of uh workshops and and symposia that     
2:25     
were kind of adjacent to the conference which are also very interesting including network neuroscience     
2:32     
and uh other sort of biologically oriented network uh sessions.     
2:40     
So yeah lots and strogats were there. They gave a talk uh in lie of their     
2:46     
prize that they got at the conference. Uh these are of course two luminaries in     
2:52     
network science. They kind of developed this idea of small world networks working from social networks uh data and     
2:59     
and uh sort of existing theory that existed. Um, if you go back uh to     
3:06     
Stanley Mgrim, he did an experiment where he sent a bunch of people letters and he told them to go post them to     
3:13     
other people that they knew and then eventually they were supposed to post them back to him. And uh this, you know,     
3:20     
it sounds like chain mail, classic chain mail, except that he wanted to see how many hops it took people uh through     
3:27     
their their social connections network to get back to him. And it turns out     
3:32     
that it actually doesn't take as many hops as you might predict. And it's because you have these hubs in the     
3:38     
network that facilitate shortcuts through the network topology. So this is where the idea of small world networks     
3:44     
kind of comes from. And then they they kind of developed the mathematics     
3:50     
of this. So you know we had the intuition from experiments and then look we got the mathematics worked out.     
3:58     
Um then of course we had Albert uh Leslar and Reika Albert and they     
4:04     
developed the idea of scale free networks in 1999. So the uh Watson Sturgat's     
4:11     
paper was in 1998 this was in 1999 and they wrote a paper on scale-free     
4:17     
networks and proposing what those are. Those are basically exist in a regime     
4:22     
between random networks and um small world networks and also provide you know     
4:31     
sort of uh components of the topology that facilitate     
4:37     
sort of this um spontaneous order that we see in a lot of networks. And so this     
4:43     
is again they were getting I think they were getting a prize here as well. And so then we went over the schedule     
4:51     
and we went over some of the side sessions um workshops, satellites they call them     
4:59     
and you know it was really interesting stuff. So and uh Jesse noted that this was being     
5:06     
held in Boston. So that's where Jesse is. Uh we had a little discussion about     
5:12     
that. that we talked about two papers on muscularkeeletal um coordination and learning and in you     
5:21     
know biology we have muscularkeeletal systems they're part of a larger embodied sensory motor nervous system     
5:29     
and so we talked about you know how that works and then what they were doing in these papers is they were applying     
5:35     
reinforcement learning techniques to simulate that system especially uh sort     
5:40     
of the finetuning of that system and so that's what these papers were about. So this one was on using curriculum based     
5:48     
reinforcement learning to do these kind of muscularkeeletal tasks.     
5:53     
And you know they developed kind of a methodology for extracting the sort of the principles from the uh     
6:00     
muscularkeeletal system using these learn synergies boiling that down to neural dynamics and then putting that     
6:07     
into a set of policies that a neural network can learn from.     
6:14     
And so the curriculum learning is of course the key component there and we've     
6:19     
talked about curriculum learning before but you know you can use this of course in the absence of reinforcement learning     
6:25     
but it's I think a lot of the approaches use reinforcement learning as a way to sort of drive the sort of the curriculum     
6:33     
forward. Okay. And then we also talked about this other this is something else that Jesse     
6:41     
brought up. This is stuff that we've first talked about in the Saturday meetings from Avery Limb. Um and you     
6:48     
know we're talking about affordances I think in that context. And then we uh okay this is the next     
6:56     
paper here. This is on a model called Arnold. This is a generalist muscle     
7:01     
transformer policy. So they were using transformers here but they were also     
7:06     
using reinforcement learning as well and developing a model for the same thing.     
7:12     
And so they were going through this, we went through this paper. So they use a     
7:18     
different approach, but they're trying to do the same thing. And we basically compared and contrasted those two     
7:23     
things, those two models. They have briefly they have a muscular     
7:29     
skeletal policy where you do some sort of task and then their idea is they want     
7:34     
to be able to transfer those tasks across or transfer those skills across different tasks. So you have things like     
7:40     
finger reaches or manipulating balls in your hand or manipulating dice in your     
7:45     
hand. And those are tasks that require different muscle synergies or different muscle groups to be activated at     
7:52     
different times. Then of course you know you you can do that but you need an embodiment. So this     
7:59     
is the human embodiment where you have a hand that manipulates things with fingers. And so you could do this with a     
8:07     
different embodiment. But of course it would be a very different set of behaviors that would be executed.     
8:14     
Um then you have the pen reorient which is a different task altogether. The idea was to just kind of see how you can     
8:21     
transfer those skills from one task to another and they show their uh behavior     
8:27     
cloning uh reinforcement learning fine-tuning and refinement steps here.     
8:35     
So that was this paper and so that was pretty much the meeting. We um I don't     
8:41     
remember what we talked about at the very end but I think we reflected on the two papers and how they connect     
8:47     
together. And then we made this connection between motor learning,     
8:52     
sensory motor coordination and language learning and uh language production     
8:58     
which is of course they're they're connected things. When you're producing language, you're basically producing     
9:04     
motor control because you have to be able to say the words that you have in     
9:09     
your head and it requires an embodiment. Um, but also it does use a number of     
9:16     
parallel circuits. So, I'll get into our second meeting uh     
9:21     
uh that we had on Wednesday in a minute, but I wanted to go over this one um from     
9:26     
Friday, which was our open source meeting. So we have our open source meeting on     
9:32     
Fridays and Baran started us off with a blog post on his work for the week for     
9:38     
GSC. Um he was working on a data set loader. So he was getting the data into     
9:44     
his environment and you know he was working at the data set that of course has a formal structure but the data     
9:52     
that's available sometimes exists outside of that formal structure. So the idea is you need to build a data     
9:59     
structure for the data to be interperable and that's what he was doing here. Um and so he's using PyTorch     
10:07     
Geometric which of course is an existing toolbox in Python uh to do this and it     
10:14     
also helps you bring this into a machine learning context is visual. So it had some really interesting visualizations     
10:21     
uh with respect to the lineage tree of sea elegance and creating these point     
10:27     
clouds of different cell centrids that were you know would accumulate as the     
10:33     
cells divided and the embryo grows. So you see this uh you have a few uh points     
10:40     
here and then you fill in a a set of a cloud of points. It kind of looks like an embryo as it's developing. And I told     
10:49     
Barian that this is something that we've been doing for uh well we often do this for validation of data sets. So, you     
10:57     
want to see if it looks like what it's supposed to look like and you know you're successful in your uh in your     
11:05     
pre-processing efforts when you can replicate something like that. Um now we     
11:11     
also do other things with these point clouds and but it's so it's important to really have a point cloud to start with.     
11:18     
Um then he was talking about his plans for the future and this other interesting thing that he mentioned was     
11:26     
that you know he's kind of thinking post transformer he's uh he's reading this     
11:31     
paper where they talk about this model called Mamba 3 which is uh something     
11:36     
that goes beyond attention that's better than attention in terms of performance and um you know this is something we     
11:43     
talked about in this group where you know what do these post attention architectures look like or what are what     
11:50     
are the alternatives to attention? You know, so attention as we know it in     
11:55     
machine learning of course is this um mechanism that people have kind of for a     
12:02     
while they thought this was the thing that was going to give us uh you know great increases in performance. But when     
12:10     
we're dealing with something like uh biological machine learning or you know     
12:16     
something like that is attention really the best mechanism we can use.     
12:22     
Okay. So that yeah we had some more visualizations that was fun. And then uh     
12:28     
and then Ashu gave us an update on her work. She was writing out the um     
12:33     
documentation for her project. This is on functional hyper edges in uh     
12:39     
hyperraphs. So she's working on this and writing out the description, the docs and then um     
12:48     
this is her open source repository where she has her code and her uh     
12:54     
documentation and everything. So this is her work. Um so it looks good. uh we had     
13:00     
some comments on you know things to edit and then I we had a little discussion     
13:06     
about the role of documentation in your in your projects and how it's essential.     
13:14     
Okay. And so then I think Jesse had a discussion about     
13:19     
um what did I can't remember what we talked about yesterday. Uh well, we talked a little bit about what uh Cavia     
13:26     
was interested in, which is this agent-based um modeling and uh computational agents     
13:35     
and how those go together. Uh so yeah, Jesse had some words to say about that as well as how to sort of participate in     
13:42     
the group and how to sort of start your own open source project.     
13:48     
Uh then we talked about this uh repository on hugging face. So we uh     
13:54     
haven't talked about hugging face too much in this group this year but hugging face is actually has a lot of resources     
14:02     
that sometimes parallel GitHub. Sometimes they offer different things than GitHub and in this case there's a     
14:09     
society and ethics group hosted on hugging face. So they're doing a lot of things with auditability     
14:16     
and openness and other types of things that are     
14:21     
involved in like uh AI ethics. Uh so this is basically you know finding ways     
14:29     
to improve models to make sure that they're doing what we want them to do     
14:35     
and to make them uh conform to things like legal regimes and cultural     
14:40     
expectations. And so that's kind of what this is all about.     
14:46     
We of course had the society ethics and ethics and tech group in this lab for I     
14:52     
don't know six or seven years now. So, we've been doing work on this. Um, so yeah, we might get involved in this. Um,     
15:01     
but it also gives us kind of uh some feedback on where to go next maybe. Um,     
15:08     
so it's interesting. Um, then Morgan brought up this uh work on     
15:14     
terminal bench and Morgan is very interested in scientific     
15:19     
reproducibility. And so that's what terminal bench is. is it basically allows you to set up a     
15:25     
workflow with AI agents that allows you to do uh uh replicate or um replicable     
15:33     
science. And so, you know, this is where if you set up the workflow, you set up     
15:38     
the um you know, on any data set that you want to analyze, you can just run it     
15:44     
and you can be assured that it'll basically give you the same results every time. And so this is what this uh     
15:51     
terminal bench science is. It allows you to to control things using AI agents and     
15:58     
and um refined methods and things like that.     
16:03     
Uh yeah, we went through that paper. We also went through this resource harbor which is um an open source registry     
16:11     
uh that does kind of a similar thing. It's just a quality control measure. It     
16:17     
allows you it's sort of a it allows you to manage things like Kubernetes and Docker.     
16:25     
All right. And then uh yeah, Weight Watcher was of course another thing that Morgan brought up in this conversation.     
16:31     
We've talked about Weight Watcher is sort of this auditing tool for deep neural networks to be able to kind of     
16:39     
account for the weight matrices and and be able to sort of uh benchmark and     
16:45     
evaluate those Okay. Uh, yeah. And then we just had a     
16:51     
little bit of more discussion and then Jesse had a little preview of what he's going to talk about next week, which is     
16:56     
this idea about how to speak and tell a story when you're a researcher or when     
17:02     
you're trying to communicate an idea to people. So you know there's this uh sort     
17:08     
of method for presenting to people or multiple competing methods to how to     
17:14     
best present information to people. Um there's the substance first model and the hook first model which is either     
17:21     
where you grab attention or you earn attention with relevance or you grab attention with a device.     
17:27     
And it's sort of to the preference of the author as to which one they use. But the idea is you want to be able to grab     
17:35     
people's attention. And then of course uh there are these things that you can do within the talk     
17:42     
to optimize uh the talk for your audience and for your own benefit.     
17:48     
Um and then you know this is yeah we didn't quite get into it so I     
17:54     
did like the shortest preview possible. Um, yeah, but I I think it was quite     
18:01     
interesting. Uh, like this slide you're on is something very much worth focusing     
18:08     
on. And it's also basically directly what, uh, I call him my guy Larry, but     
18:13     
Larry Mckinary um, from the expert writing Chicago thing. Uh, like that was     
18:19     
basically his premise as well is that slide too. So to see it come up here repeated from sort of this old classic     
18:25     
is like I do think um like I I retitled just before the actual presentation the     
18:32     
slide the opening slide to say vintage advice and part of the the thing about the vintage or not was um like what's     
18:40     
still applicable today because things change and trends evolve. I think this is uh this is this is stood the test of     
18:48     
time if you will. Um, and I don't, it's not again an an implication that     
18:53     
people's ideas don't matter. It's just, um,     
18:59     
there's a particular skill set to making your ideas accessible to other people.     
19:05     
Yeah, that sounds good. Uh, yeah, I think it's all about accessibility of ideas. And so there's the skill of     
19:12     
having to sort of having the ability to speak well about your idea as well as     
19:18     
writing it. But you know, writing it, of course, I want to be able to see you     
19:23     
kind of explain it outside of the cons uh the structures of a paper. So paper     
19:29     
is usually pretty formal and they don't give you the freedom to kind of explore things, but also make them maybe     
19:36     
visually compelling, make connections that you might not doing a paper and so forth.     
19:44     
So yeah, and then uh yeah, these are the people who have kind of give     
19:50     
presentations on this and then that was basically what we uh     
19:56     
oh we also well Jesse has some tips in the slide deck about how you might apply     
20:02     
this to a demo of some type. So you know this is demo or die type stuff. So, this     
20:08     
is where, you know, you can be really efficient in your demo. Um, and you know, really in demo or die, you need to     
20:15     
be efficient. You need to be able to get right to the point of what you're demoing,     
20:20     
how it relates to something larger, what the demo is supposed to do. and     
20:27     
then you know just kind of have a couple one or two ideas to focus on as sort of     
20:34     
a you know maybe a big picture takeaway. So that's that's kind of interesting     
20:39     
too. Maybe we can focus on the demo or die aspect too next time because I think that's kind of for our group it's kind     
20:47     
of the most important thing I think. Yeah. I think I think what I'd like to     
20:52     
do um and the the last slide is just the recap slide. I think what I'd like to do     
20:59     
and it it's it's evolved since then. So I'll just I'll kind of uh carry on the     
21:06     
conversation is I think I'm kind of imagining three or four     
21:13     
parts in total. Um one I think is vintage advice which I think is really     
21:18     
good for young people to hear. because if you're talking to certain generations, that's what moves them. Um     
21:28     
like like the Connor the the second speaker who I kind of was like, "Oh, this isn't applicable." The the things     
21:34     
there are incredibly useful to know and it's even more useful to know when you shouldn't and when you should lean into     
21:41     
them. So that's sort of one thing at large. We get these questions about, oh,     
21:46     
how do you how do you blah blah blah to the audience or whatever? How do you know when it's a mixed audience? Those     
21:52     
things really come up. I think there's like uh also um specifically there's there's very     
21:59     
timeless things that you could be drilled down a bit more into like some of the expert writing stuff um and and     
22:05     
also what Bradley's saying about um     
22:11     
principles of demo or die flash talks that that that prepare the art of preparing you're basically your minimum     
22:17     
viable talk like the smallest talk you can give that really gets at what you're saying because I think that's sort of     
22:23     
the you can always add on and elaborate from there. But how do you get     
22:29     
sort of it's sort of like the smallest uh you know the the smallest model you     
22:35     
can make that is an excessive and learning how to do that in a talk form is is a sort of the bedrock skill. I I     
22:43     
I've been in my mind for over a year now. I'm trying to come up with this. It's a bit it's a bit sports analogy     
22:49     
heavy. Um but like what's what's what's the like in in football or American     
22:56     
football blocking and tackling is the sort of your fundamentals? Like we talk about oh go back to fundamentals. What's     
23:03     
what's the what are like fundamentals for interdiciplinary research or innovation in the way in the places     
23:09     
we're looking at it? And I don't I think I think essentially the the flash talk and the demo or die elements of that     
23:16     
kind of get at it. Um so that I'm I'm I'm     
23:21     
that's not a finished product yet. I know Bradley's does tons of things in um teaching open source and uh project     
23:27     
management and whatnot. So maybe a future thing to do there specifically.     
23:33     
But um the last thing I'll say before we move on to other things about the professional development topic is what     
23:39     
is who what is the latest like what is now like if not the 11 year old 11 uh     
23:49     
year old video on YouTube not not the oldtimers uh speaking their wisdom which     
23:55     
is a fine thing to do but like what is it now? And I I found     
24:00     
I I uh found a very good thing to     
24:06     
address what that is, especially in the     
24:12     
current moment where institutional clout uh bureaucracy and and sort of the the     
24:20     
resting on there's a tremendous shift away from     
24:25     
institutional I'm associate with institutions institutions so you should so you can     
24:31     
listen to me and very much focus on individual sort of like founders versus bureaucracy     
24:38     
but what does that what does that mean really in terms of communication in terms of writing certain things of of     
24:45     
styles and of connecting in particularly in I would say technical innovation spaces um and and there's there's some     
24:53     
folks that I've u been watching for a while there and and I think one of the next things I'm going to talk about in     
25:00     
in GOC but also frankly in the data and direction program that's about to basically start next week um I I really     
25:09     
think that's a nice a little bit of a classic just history part um key things     
25:17     
and then where we are where we're going it's very uh I feel really good I feel     
25:23     
like we we there's a there's a solid courage curriculum that's developing here and     
25:30     
it feels complete in a way that I wanted it to feel complete. So to be continued on that um next week.     
25:36     
Yeah, that's good. Thank you, Jesse. So that was all for this meeting. All right. And then our third thing I     
25:43     
wanted to talk about was Wednesday. This was where our Cognition Futures reading group got back together. So, if     
25:50     
you go to the JoePro or the Just Parent uh YouTube channel, you'll find this uh     
25:57     
Cognition Futures reading group session. Um this was just a recording of the     
26:03     
session with Jesse giving a little preamble at the beginning. So, Jesse also posted a um one of his Substack     
26:12     
posts on this. So, this just talks about how, you know, we're getting this group back together after a while. Um, we took     
26:20     
a hiatus at the end of 2024. You know, we had done like, um, so the     
26:26     
the web the lab has a kind of a long-standing interest in cybernetics     
26:32     
and we kind of worked on that for a while off and on and then we started     
26:39     
integrating that with cognition futures. We did this reading group where we started with uh Norbert Weiner's book,     
26:46     
the human use of human um what was it? The what was it?     
26:53     
Human use of human beings. Yeah, the human use of human beings where um you know we we went through     
26:59     
chapter by chapter every session was like a single chapter and we kind of reflected on the book at where things     
27:06     
are now basically. So that was a book that was written in the 1960s. uh Norbert Weiner's work was sort of     
27:12     
mature at that point. So he had a lot of things to kind of reflect on from his own work and then sort of apply those     
27:19     
lessons to the development of technology which might not seem relevant today but     
27:25     
it actually is quite relevant to today um in terms of kind of the themes that he's talking about and then kind of the     
27:32     
themes that technology critics are talking about today or people who are just interested in sort of AI ethics     
27:40     
more broadly. So this is um you know that was sort of the uh genesis for that     
27:47     
phase of the cybernetics project. Then we also reviewed a few papers and we had     
27:53     
this group that was active for about a year and a half just within cognition     
27:58     
futures on these cybernetic topics. And of course that culminated in the paper that we just published or just got     
28:05     
published last month on the ever good regulator theorem and um world models.     
28:13     
And so that's uh so that was a kind of a big gain for the lab I think to see that     
28:18     
through that arc from like you know reading group to paper. It's it didn't it is interesting because     
28:27     
I I was so focused on the     
28:34     
like history of hold on the history of um     
28:42     
where condition future stuff. It's so it's just weird to think of the     
28:49     
whole arc of um     
28:54     
like 20 I think the origins of the of the     
29:00     
reading group itself was like 2022ish     
29:06     
and I forget when our first recorded meeting was 2022 or 20223     
29:11     
and then it were like all the like Varela I'm becoming aware of pukes,     
29:17     
right? And then yes, it kind of at after that or towards the end of a certain run of     
29:23     
like the Velian lineage, we did this the the cybernetics element emerged     
29:31     
as like a center and I like it was interesting because we did we the the     
29:37     
unhumanist human being is kind of a you know it's a it's a society ethics and     
29:43     
technology book. Um and and you know things weren't quite so some things really carried well and some things were     
29:49     
like oh this is sort of you know a little uh strange way to talk     
29:56     
about it right and but then we went back into other parts of like cyberetics     
30:02     
theory and I think that's why if in in the video I don't know I don't know if     
30:07     
it shows up in the in the bridge version that I I clipped all the way we met for like an an hour a little bit a little     
30:13     
bit over that Um and and I reduced to like 20 minutes. So it was like very very very very rich.     
30:19     
But even in even in there you might see um like one of the last things in the old     
30:26     
distributions reading group um uh notes our notes are shared super     
30:32     
super lightweight notes was um Leaven citing the 1943 kind of uh not step     
30:39     
graph but that that organizational diagram of of you know predict types of     
30:44     
behaviors um in one of in one of Leven's own presentations So, it was yeah, interesting to kind of     
30:50     
just see to see that again. And it was really great to see everybody to come back     
30:56     
together. Um, I don't I don't I kind of just     
31:01     
I don't know what we'll call everything yet. Um, but I'm really happy to     
31:07     
have had the have had getting the band back together. So, I don't know if you or Morgan or anybody else wants to say     
31:14     
more, but I'm just happy that this happened and curious what will go next.     
31:21     
Um, yeah. So, I mean, I hadn't mentioned the Varela and the Fuches stuff, but that was actually more cog cognition     
31:28     
futures sort of slotted and then we said, "What are we going to do next after fuchs?" And then we did the human     
31:35     
use of human beings. So, that was nice. Um but yeah, I mean, you know, this is     
31:42     
again I like these reading groups because you can unpack things. Um you     
31:47     
know, you're not like we do that in this meeting. We do a lot of features. We do a lot of catching up for the week. Um     
31:54     
and in these meetings, it's a lot more focused, but also unfocused     
31:59     
um on what we can do. So you know, what do we want to do for this meeting? Let's just focus on chapter one, discuss     
32:06     
chapter one, etc. Um, yeah. Yeah. This this I'm I'm likening I'm     
32:14     
basically training in my mind and this is this is admin my admin hat. Um, I'm basically     
32:22     
realizing what I want to hand hand some new folks and pro maybe if we should have done um for Google Summer of Code,     
32:29     
but but for data and direction folks and other people coming in through Jos     
32:34     
um I basically want to hand them a like a a digital campus map because I feel     
32:40     
like in the in the like the working groups are almost like these sessions     
32:46     
that are happening in in specific classrooms or if you or like specific arenas like the Google Summer code like     
32:53     
the joint the open source cohort stuff you have worm you have data and     
32:59     
direction you have digest now you have the Wednesday meeting um and it's like what's what's going where this meeting     
33:05     
is is um it's like a big it's like a big jam     
33:12     
session in some ways and I I I've always appreciated the the openness of it and I     
33:19     
I think I I think the openness of it comes with I haven't maybe done it enough this this every season I I I     
33:26     
remember eventually or like try to emphasize and we want you guys to come in and say things too like come in and     
33:32     
have a presentation like like like add your thing to the uh what's it the stone     
33:38     
soup everybody brings stuff in the pot kind of a deal like like it doesn't have to be me talking or or Morgan or Bradley     
33:45     
like we really want to encourage folks to come and do that too Um     
33:51     
yes. Um I think I think there's a lot of     
33:57     
in-house or like neighbor directly adjacent to in-house     
34:04     
uh things going on and and it's nice that they can kind of flow well into     
34:10     
each other. A lot of good things come from there. Yeah. Yeah. I'd be interested in that     
34:16     
road map or the the whatever you're calling it the virtual campus     
34:21     
because well we do give like people in the onboarding materials we do give them     
34:26     
sort of a map of the meetings but it's kind of like here's a list or here's     
34:31     
like a YouTube channel which is useful for exploring but like it doesn't give you a sort of an overview     
34:40     
and yeah and like this is maybe we don't have to talk about this extensive right now, but in my     
34:46     
mega mega admin hat um and like program planning and and     
34:54     
by by program planning I specifically mean like the things you're doing especially if     
35:00     
there's a public facing component that's not just doing research and reading papers directly like hosting meetings,     
35:08     
hosting sessions, project development, working you know the the means by which     
35:13     
you can work on the project that isn't just at a regular standing meeting like all that kind of stuff. where where I'm     
35:19     
going with this is like I I've been starting to     
35:25     
it's it's I appreciate that Morgan's like I got to go find a coffee shop this morning because that's that's often me here in Boston too like and and that's     
35:32     
sort of what Boston has become to me is like this broad uh Boston campus even though I'm not     
35:40     
directly tied right now to one location I go like I go to coffee shops all the     
35:46     
time and I almost I almost I was really I I might mention this later, but um I was disappointed is I've been a little     
35:52     
bit um under the weather, if you will. I wanted to go to an MIT uh aha group had     
36:00     
been a seminar, a screening of of the AI doc, and a nice discussion about that.     
36:05     
Like a lot of cool stuff here locally, but there's a digital equivalent for that, too. you know, like all everybody     
36:11     
in in the core of like this group and and     
36:17     
and JPro are are like digital first, but it's like where even giving them like a     
36:22     
loose semblance of a map of like what's kind of where are things not just like     
36:28     
you know we've made those maps before of uh like oh where's neuromatl or where's     
36:34     
like divorm or where like those like you know that like thing with like three columns or something like that I that     
36:41     
was like a couple like two or three years ago now. As an aside, nothing is stranger than     
36:49     
being someone who is now fully trans transitioned from student who doesn't manage anything to     
36:59     
the the mental process of oh yeah, we started that group a couple years ago. It's like five or six years ago or seven     
37:05     
years now. I'm like, "Oh, that diagram from a little it's two or four years old." And not old in a bad way, just     
37:11     
like, "Oh, like it's so present in my mind, but it's you'd have to dig to find     
37:16     
it now, you know." Um, but anyway, I think making a     
37:24     
not just like a map that's like nice and visual, but like a nice explanatory thing. So, because a lot of folks in in     
37:31     
the like that I've been bringing in for data interaction are like, "Oh, this is great." And like what else? And I I'm     
37:36     
kind of mentioning to them, hey, you're welcome to come to like this meeting, the Friday meetings, um the digest     
37:44     
meetings if it's if it's spoken to them, but like what is that, you know, like what what is that sort of how do you     
37:49     
visually represent what's kind of happening in that space to to someone     
37:54     
who's brand new? So, um I I'm working on that and maybe that'll be a little     
38:00     
something I try to do this weekend and show off to some folks next week. Um but     
38:05     
you know, I'm happy to have feedback or input     
38:10     
particularly from Bradley about about how how what what should that even look     
38:16     
like? So, that can be we can talk about that elsewhere. I'm sure we have other things to say, but that's I'll probably     
38:23     
make something like that soon. Okay. So, yeah, let's let's see a little bit     
38:29     
about this uh this post on Substack. Um, so this is just kind of discussing what     
38:37     
why we're getting back together on this. Um, and so yeah, these cognition futures reading groups are have been very broad     
38:45     
historically. You know, we've talked about things like phenomenology, cybernetics, dynamical systems,     
38:52     
complexity, and the philosophy of mind. And then of course we had this cybernetics discussion offshoot that led     
38:59     
of course to the paper and um a lot of sort of     
39:04     
jumpstarting of our of our cybernetic interests in the lab and putting out some papers.     
39:10     
Um I did bring up like uh the paper I think last week in this meeting we     
39:16     
talked about the paper pyramid and how that you know that's kind of an overarching plan. I don't know if that's     
39:22     
relevant right now, but we can revisit that if if Jesse's mowing and you know     
39:28     
we we but this is something of course you should constantly re-evaluate anyways. In any case, we're kind of     
39:34     
pulling back into this arc and we're seeing what we can do and how it can go     
39:41     
forward. So, we had um and if you want anything     
39:46     
added or thrown in here additionally, you're welcome to do that. I'll probably also send this to Medium, too.     
39:52     
Yeah, I think this is good. And you can send this to Medium and we can just have this as the post. Um, you know, we can     
39:59     
Yeah. have future posts, I guess, as we get further into it. Th this was this is     
40:05     
basically more of a hyper bridged I almost want to say showcase uh because I     
40:12     
was like do I try to present all these like multitudinous strands and names. I     
40:20     
put a lot of the names in the YouTube video description just like kind of for like SEO type purpose, but also just     
40:26     
because almost as a reminder is like, hey, like we talked about like everybody     
40:33     
from beer to Raja and from beer to Raja     
40:38     
and back again, you know, like like that kind of a but in here I'm just like, well, I'm just going to like make it as     
40:46     
I'm going to intentionally leave out a lot of stuff and have this posted as almost a ceremonial.     
40:52     
Hey, we we had a first meeting. The band got back together again. I'm very happy that we did. And here's some related     
40:58     
things. Yeah. So, we had uh Jesse, myself,     
41:04     
Amanda Nelson, and Avery Lyn. So Amanda was um in a lot of the well she was uh     
41:13     
present in the cognition futures reading group uh back when we were doing it.     
41:19     
Avery was sort of um you know kind of interacting with this but not able to     
41:24     
make the reading group meetings. So then we got some perspective on things uh     
41:30     
where maybe we should go next. We talked a little about about Avery's work and um yeah it was a nice meeting.     
41:37     
So this again is like you know we would like to sort of drive this forward. Uh     
41:44     
we've been revisiting this uh discussion group from cogsai 2021     
41:49     
which of course we hosted um you know something called trajectories in cognitive science. So the cognitive     
41:56     
science conference hosts these discussion groups where you can discuss a topic and so we were talk we had like     
42:02     
a series of talks on different topics in cognitive science. I think Jesse um and     
42:09     
a few people did a talk on development developmental psychology.     
42:14     
uh I did a talk on trajectories as a computational concept and how you can     
42:19     
apply that to thinking about you know different uh cultural and cognitive trajectories     
42:27     
and then I think Avery presented something and we had some discussion around that we should do something like     
42:33     
that again if we can find the opportunity or even if we have to make our own opportunity     
42:39     
yeah um that's a dove tone was something I was going to mention I think I'll put it this way. Um     
42:49     
both for like completion of data and direction stuff and because we can I     
42:55     
think something at the end of summer like late summer     
43:01     
and when is when is your because you are probably doing stuff in a teaching     
43:07     
capacity or something. Um, as usual, it it I would like to we can pick the dates     
43:13     
later, but I think I the next opportunity for a larger scale event, I would love to have like a,     
43:21     
you know, in in East Coast time there's and in the west coast, but like East Coast, it's     
43:27     
before late April is like and and sometimes early May is is that time     
43:34     
where like all the all the schools here in Boston have their, you know, the     
43:40     
AHA symposium, the CIRC uh year end symposium where you have the     
43:46     
thing and you have your the informatics student showcase like the thing for your department to show off your big stuff at     
43:52     
the end of the year. I feel like there's a summer version of that that is a next version of a lot of things and and it     
43:58     
could be basically a big showcase for like what what's the ecosystem we have     
44:04     
doing. I think we could do it like digest this if this group comes up that     
44:09     
would be great. Um, and it could it could just be commission futures related, but I think there's enough to     
44:15     
make it you could have a small especially all especially     
44:21     
the most wanted suspects in this room easily.     
44:27     
If you give us if you give us if you give us each 20 minutes to talk about a particular set of projects something     
44:33     
like that um you know we we we'd have we'd have so much to say uh so I mean     
44:42     
you know that's a little bit flippant comment but um there's plenty there's a lot of opportunity for that so maybe     
44:48     
maybe maybe trying to plan an event uh at the end of summer would be fun if     
44:53     
that's a good time for people to do it. Yeah, I think that's a good plan. Um,     
45:00     
yeah, I you know, I know we've been trying to come up with an idea uh for a     
45:05     
while for some sort of presentation. So, I I'd like to try to see that through this year. Um,     
45:11     
yeah, like even right now, like one I had wanted to     
45:17     
and it this is big time admin with a little bit of a jerk parlene here. I talked last year of like I want to do     
45:27     
like there was um I think something that took place in this last year was the augmentation lab summit or the human     
45:32     
human augmentation lab summit at MIT which is fantastic. That's not going to happen this year because everybody was     
45:38     
in that base. They moved out of town. A lot of them went to San Francisco to be blunt. Um but there's other things going     
45:45     
on here that are great too. uh and I had knowing foreseeing some of     
45:50     
that and foreseeing I would say accurately that 2026 was going to be a very strange year on many     
45:57     
fronts for many people many things in the world. I'm like, "Okay, let's um     
46:02     
let's do something. Let's make a certain event." This basically might be a version of that event. Okay. And I at     
46:10     
this event, I would love to basically tease a launch of the actual joke feature center. I'd love to have Google     
46:18     
Summer of Code folks. They don't ne most Google Summer code probably done in a     
46:24     
way by them or something, but a way to kind of reference what happened. And by that I mean everybody in the open source     
46:31     
cohort. Um oh speaking of I had a few people interested like reach out about     
46:37     
some of the multi- aent whatever stuff. Talk about that later. But like Google serness     
46:43     
will have things to say futures might have things to say. The JRO future center might be a cool thing to say.     
46:49     
There's also potentially an opportunity to have a sort of semiartistic component     
46:54     
too. I'm still talking to like Echolapto, Addie, and um at least one     
47:00     
person who I think is local uh interested in doing sort of an art     
47:05     
basically I'm I'm keeping the theme of like art you hear me saying jam session a lot more recently but uh it's like     
47:12     
jazz jam session plus interdisiplinary research communication a lot of you know     
47:18     
there' be a way to talk about that so I'm kind of imagining the program like these are kind of programs and the     
47:23     
people in like this thrust that we have currently a couple free sessions and I     
47:29     
don't know um I think there's enough there to make it some kind of I don't know what to call     
47:35     
it but some big uh festival of     
47:41     
the the larger community and pro stuff um     
47:47     
I don't know but I think there's I think there's enough there to do something of that time and I'm happy to make it can be it could be an hour long thing. It     
47:56     
could easily be an 90 or 20 minutes and it could basically be it could easily be     
48:01     
like a half a whole half day like four hours. It could be it could probably be     
48:06     
like seven or eight hours of of stuff, but I don't know that any of you guys would want to do that much. Um, but like     
48:14     
I think this could be a solid chunk of, you know, multiple hours of activity     
48:20     
that would be substantial that we we haven't done anything like that. We didn't really we didn't really do anything that I don't think last year.     
48:26     
So, I mean, I'm not I'm not saying, oh, we could just repurpose last year stuff, but I think there's just a lot that     
48:33     
could happen there. Yeah. Yeah. I think we did the open house in like 22 23 in that time period. or maybe     
48:45     
for context for anybody who's not in this room as we all know. Um     
48:53     
I think the open house was a wonderful thing in part because Bradley did a thorough job and really got many     
49:01     
like bigger nexus or nodes in the lab space and the     
49:08     
community and also smaller ones. It was a very nice sort of     
49:13     
inventory. Um, and we've done some other like recap     
49:18     
type things since then, but not as thorough perhaps, right?     
49:24     
Yeah. I mean, that was like served a purpose that was different than this. But um I mean the idea of recapping the     
49:32     
space, you know, kind of how do you uh make the most of like the getting     
49:40     
things out of your head, making a description, fitting things together, discussing them. Um     
49:46     
I think it's it's pretty nice. Um, yeah, it's very a life in the sense that     
49:52     
they, you know, you want to have an artistic component and then the science component and then, you know, they're     
49:59     
different like it, it's bringing together a lot of different things. Um, which I like. Um     
50:06     
I'm I'm least sure about the artistic component, but just to make it more that     
50:11     
seems to be like the invogue thing to do like like um to invite an artist in. Yeah. Well, like     
50:20     
Oh, go ahead. Sorry. A life that you know they have like an artist like usually someone who does     
50:25     
applies a life principles to their work. In this case, it could be someone who's doing some sort of cognitive science     
50:33     
oriented art. you know, it's just kind of in the within the theme. Um, yeah,     
50:38     
people have done that pretty effectively, I think.     
50:46     
Yeah, let's talk about it. Um, I mean, let's talk about it outside of     
50:52     
the meeting. Yeah, I'm actually I can already put myself     
50:57     
the only thing that would I would have to work around would be some other like programs or or summer     
51:05     
things that I'd be doing. But I think end of I think August and the end of     
51:11     
August or whatever would be sometime in August or probably before September gets     
51:17     
up would be a great time to do it. I will pause myself because I'm gonna keep     
51:24     
planning it right now. Talk about other things. So the next thing I want to talk about     
51:29     
this is something Morgan posted in the Slack. This was in data science or data     
51:35     
science ML or data sc uh this is uh from Sakana AI. So we were     
51:43     
talking about benchmarks in the open source meeting and um he posted this     
51:48     
from Syakana AI which is where they have this recursive self-improvement lab or     
51:54     
RSI lab and you know uh Sakana AI is     
52:00     
doing things with like artificial life with uh genetic algorithms and applying     
52:06     
it to um AI research. So that's they're and they're based in Japan. So they're     
52:12     
kind of working um in that community as opposed to say like Silicon Valley. So     
52:19     
this is uh what they call the next paradigm of artificial intelligence. So as the world enters the era of AI,     
52:27     
Japan has a unique opportunity to reclaim its position at the frontier of global innovation.     
52:34     
However, to achieve global leadership in AI and scientific discovery, we cannot simply stick to the conventional     
52:40     
approach of brute force monolithic models. We must leapfrog the current paradigm.     
52:47     
History shows us how Japan's historical dominance and manufacturing was not achieved through abundant natural     
52:53     
resources, but by fundamentally redesigning the institution of the factory floor. through the philosophy of     
53:00     
continuous compounding self-improvement. Japan created systems that achieve more with less. So they they actually in um     
53:08     
you know this is one of the things that uh Japanese companies often did in the     
53:14     
like 80s and the 70s through the '9s was they had the Kaizen method which is u     
53:21     
basically stands for change improvement good where that's what it translates into in English and it's basically a     
53:28     
form early form of um agile and so you     
53:33     
know they were using those kind of techniques on the factory floor before people were using agile in the tech     
53:39     
industry. And so this is uh kind of where they're they're kind of thinking     
53:45     
about it in that in terms of that um but also applying it directly to an AI     
53:51     
pipeline say as opposed to managing a team developing AI.     
53:57     
So to achieve this at Sakana AI, we are building open-ended adaptive architectures that collectively     
54:04     
self-improve. Just as biological evolution innovates endlessly by building upon past     
54:10     
discoveries, our AI systems must transition from being static tools to autonomous researchers.     
54:17     
So they're using um they're using this recursive self-improvement technology and they're     
54:24     
applying it to foundation models. And so this is the research group that they're     
54:29     
announcing here. Um so they're kind of going through the history of the the     
54:35     
group. So the history of the group was that it was founded in Tokyo in like 2023.     
54:41     
In 2024 they published uh the first version of their AI scientist white     
54:47     
paper. They then worked on the released this uh large language model squared model which     
54:53     
was um I think something in collaboration with disco pop in the UK.     
55:00     
Then in 2025 they released AI scientist version two. They had the Darwin gold     
55:07     
machine paper with in collaboration with UBC in April of 2025.     
55:13     
They then published this white paper on the ally agent or ALE agent     
55:18     
in um collaboration with AI coder AHC058.     
55:25     
Uh then they had this uh AI scientist article in nature. So was published in     
55:30     
nature in March of 2026. Um then they also had these other     
55:36     
things. one in 20 August 2025 Shinka Evolve and then in February 2026 the     
55:42     
digital red queen. So they've been working on these different projects that are kind of connected into uh like the     
55:49     
evolutionary computation space, the artificial life space and applying it to AI. So this is uh kind of thinking about     
55:58     
what they're doing. I like this diagram by the way, Jesse, because this is kind of what we were talking about     
56:04     
with respect to how do we plot out our progress? How do we communicate that to people in the group? So, you know, you     
56:12     
could take this, we could have something similar to this for orthogonal web. We could link um different, you know,     
56:20     
milestones to papers or to blog posts or whatever.     
56:25     
Yes. Yeah. So then they have a bunch of different they're you know they describe these different research milestones     
56:32     
here. Um and then kind of thinking about the     
56:37     
uh evolutionary optimization loop is the universal sort of unit of uh what all     
56:44     
these things have in common. This is their sort of proprietary sauce here. Um     
56:50     
and so what unites this is an evolutionary optimization loop that has defined Sakana AI from inception.     
56:57     
Progress through ideas, not just compute. Um and so this is just kind of     
57:03     
talking about the advantage that that gives them in the shanka evolve paper.     
57:09     
It required only 150 samples to solve problems that brute force search treats as intractable.     
57:15     
So it gives you an advantage in terms of training data and in terms of performance.     
57:21     
LE agent outperformed 804 human heristic specialists by extracting structured     
57:27     
lessons from its own failures, not by burning more inference. The same     
57:32     
conviction will shape our pursuit of RSI. We are building not the most compute-hungry self-improvement engine,     
57:39     
but the most sample efficient one. And so this um this says relevance to     
57:46     
these uh type of foundation models. Um they want to develop agentic foundation     
57:52     
models. Uh and you know thinking about agent native models that power an AI     
57:59     
scientist and then how that AI scientist in turn can build better agent native     
58:04     
models. So basically you have agent models that are building uh or that that are     
58:10     
contributing to this AI scientist and then the AI scientist gets revised constantly.     
58:16     
So this is a graph that they're that they show for this uh you have cycles of     
58:22     
research and development and self-improvement. So you know this is like the prototyping cycle where you     
58:30     
keep building prototypes and you keep improving based on feedback. Um and that's kind of how they view this     
58:37     
uh but but in this broader context. Um and then scientific discovery     
58:42     
capabilities. So as you keep improving your     
58:48     
uh model, you keep improving your discovery capabilities and this is um     
58:54     
this is exponential apparently. So you have these agent native models which are based on a large language model and a     
59:01     
world model. You have the AI scientist which is involved in automated discovery and then     
59:07     
you see this recursive self-improvement where the AI optimizes AI code and then     
59:13     
this is democratized AI sovereign AI for all. It's very much one of these um     
59:20     
startup sort of blue sky type graphs where you show like the benefit of your     
59:27     
approach over sort of the status quo or over everyone else. You know, we don't     
59:32     
have the details of how this actually works, but this is sort of the vision.     
59:39     
So, that's the idea behind this. So, it's it's sort of this uh building off this idea of self-improvement     
59:46     
and applying it to the AI ecosystem.     
59:52     
Kind of like a view of things and yeah, I checked in with them for a     
1:00:00     
while, you know. Uh so was um     
1:00:07     
was just thinking about this summer's a life combined meeting     
1:00:14     
um seems to be happening in water. Yeah.     
1:00:21     
And uh uh yeah, you know, there's um     
1:00:32     
these these kinds of self loops. Um     
1:00:38     
you know, every everybody's talking about this right now because um you     
1:00:43     
know, anthropic are making planes     
1:00:50     
that make them money that uh that they've they've reached u     
1:00:59     
they've reached the point where their AI tools are self-improving their AI tools.     
1:01:07     
Yeah. Anyway, yeah, I I'll put some things in chat.     
1:01:12     
All right. Yeah. Well, thank you. Yeah, that was a good article. I I enjoyed taking a look at     
1:01:19     
that and uh in fact we've been following Sakon AI for a while and so yeah, I     
1:01:25     
think that's great. Uh definitely integrating a lot of this self-improvement into the actual     
1:01:32     
development of the you know AI system. So I mean this     
1:01:37     
is something that we do anyways in development but it's like you know thinking about how you're kind of     
1:01:43     
versioning your models too. Like, you know, we think about how you     
1:01:48     
want to release something that's like incredible and uh, you know, you have these big really big companies that are     
1:01:54     
releasing like these and and you see this in in big science     
1:02:00     
too where you have like bigname labs and they release these papers that are like these blockbuster papers and they have     
1:02:06     
mass amounts of data and it almost seems like they're trying to like overpower     
1:02:11     
everyone else, you know? So like the large AI companies will do this with their models and but at the end of the     
1:02:19     
day what we're interested in is like improving performance because of course that's what's happening. Uh so you know     
1:02:26     
having a model where that's built in I think is is good. Yeah I I hopefully you can hear this. Um     
1:02:33     
yes many times these companies are just presenting     
1:02:39     
with you know great grandeur and and hyperbole, you know,     
1:02:46     
they are making huge amounts of money from this, right? Yeah.     
1:02:52     
Um but uh you know, Sakana has always been a very a very reasonable research.     
1:03:00     
Yeah. you know like so it's interesting because you know at     
1:03:08     
the same time like their AI science work is not     
1:03:13     
I still haven't seen you know a breakthrough on that uh you know Gemini     
1:03:20     
the Gemini team pushing a new one current right     
1:03:25     
you know the big thing now is is to say that you have it But but if you get on a     
1:03:32     
wait list, right? You can evaluate it.     
1:03:39     
Yeah. So it's like you know you have of course you can have these major breakthroughs or you can just say you     
1:03:44     
have a continuous improvement of the model and which one is more honest. I guess     
1:03:51     
this is this is it right? Is that like you know that that this is the where the research worlds is has merged with the     
1:03:59     
business world. Yeah. Where it's just like like making outrageous claim is is actually very     
1:04:05     
helpful for your valuation. Oh yeah. Yeah. So like this is this is super     
1:04:13     
problematic where it's like you know deep mind has great teams but don't make     
1:04:20     
about tools that nobody could ch check or evaluate right like you know when you're ready. Uh uh     
1:04:29     
yeah, call it a business tool, but don't call it a science tool in both.     
1:04:35     
Yeah, I think that's a Well, thank you for the bringing that to our attention.     
1:04:43     
Okay. Um, so I don't Jesse, did you have a more extensive um discussion that you     
1:04:49     
wanted to do today or     
1:04:55     
um I think I think I'm actually going to say no for once if only because I think     
1:05:02     
my mind is is on both some of the the campus map digital     
1:05:10     
campus map that we mentioned for as well as um     
1:05:17     
that event that we talked about the in terms of things that I'll just note to     
1:05:24     
that are coming for the week ahead. One um data and direction should be     
1:05:31     
like starting like it is starting now. Um, and     
1:05:37     
um, I know that sound like the conventional     
1:05:43     
thing you're supposed to say, kind of the glad handing and oh, we have great     
1:05:48     
students and whatnot, but um, it's I think I think maybe more     
1:05:55     
authentic ways to address that is like it is genuinely humbling to see um,     
1:06:02     
folks want to do want to do um do stuff in this space. I'm very great     
1:06:09     
people apply and I'm looking forward to starting this year um with them.     
1:06:16     
Uh I'm very looking forward as well to the condition for group things with     
1:06:21     
Avery indigenous are emerging um as well.     
1:06:26     
I got to find out when because there's sort of an event in     
1:06:32     
in in Boston. I think it's in mid July. So, there may be a smaller Joe event in     
1:06:39     
person uh when Molly and some other folks are in town for that,     
1:06:46     
but I think the major event will be August type August. August somewhere in     
1:06:52     
August. That's that's where things are now. Um, I do want to follow up on the professional development like speaking     
1:07:00     
and demoing. Uh, speaking conventionally speaking in a more modern sense, demo or     
1:07:08     
die and some of the fundamentals. Um, I think those are things that will come up     
1:07:13     
over the summer for for many folks. Um, I have things in the docket for that.     
1:07:20     
And the only other thing on the radar is um the biggest wild card for the summer for     
1:07:26     
me is is if I get if I get into Dizzy the digital the diverse intelligence     
1:07:31     
summer institute proper or not. Um I don't expect it. Um I'm I'm I said hey     
1:07:39     
yeah I'll go in, you know, to it um if I get if I do get it or if there's     
1:07:44     
something that opens up. Um, it's interesting because it's in New York, upstate New York of all places and not     
1:07:52     
um Europe, St. Andrews, uh, United Kingdom     
1:07:57     
type type stuff. Uh, but outside of that, um,     
1:08:04     
I I will I don't I won't I won't drown on about anything else right now. So,     
1:08:10     
it's probably everybody. That's good. No, thank you.     
1:08:16     
Looks like Baron is here. Um, did Baron want to give an update about anything or     
1:08:21     
talk about anything? Let me go through the comments here. We     
1:08:27     
had some things in the chat. So, um, I think we started here with uh Jesse said     
1:08:34     
hashtag alternatives. Then he said it might be a good good to review hugging face overall. Maybe in     
1:08:40     
the GOG meeting ahead. Yeah, I should go over the D.VARM Worm hugging face cuz we     
1:08:45     
did put that together in like 2023 and it has actually all of the pieces of     
1:08:53     
software that are part of the D.Learn platform. So Barshan was asking about     
1:08:58     
that yesterday and he wasn't so familiar with D.Learn as opposed to DVO graph and     
1:09:04     
I want to go over that. Um, and then uh between Weight Watcher,     
1:09:10     
Arnold in the back uh to the 80s presentation. Oh, the Yeah, the one I     
1:09:16     
did for um embodied intelligence. Um, we might need to make another     
1:09:22     
throwback plus computation related topic. Yeah, we I mean, yeah, that's something     
1:09:29     
interesting, isn't it? at like kind of if you're exploring a certain topic     
1:09:35     
that's kind of modern, where does that come from or something like that? Um if     
1:09:42     
you're not familiar with the presentation I gave for uh embodied intelligence, it was basically um     
1:09:49     
isolating the um sort of the foundations of embodied intelligence models and     
1:09:57     
agent models and artificial life models that sort of percolated in the mid to     
1:10:04     
late 80s and early 90s. So there were a bunch of bunch of themes. Uh one of them     
1:10:10     
of course was Brightenberg's work that culminated in the Braenberg vehicles book 1984.     
1:10:16     
There was of course Boyds which was um Reynolds work. there was um other work     
1:10:25     
um around like swarm intelligence and passive dynamic walking and all those     
1:10:30     
things kind of came together at that time and then influenced later embodied intelligence. So that was like     
1:10:38     
wellreceived at the conference and it's on our YouTube channel. I think it's a     
1:10:44     
nice over historical sort of uh overview of that. But plus, you know, kind of     
1:10:50     
linking that to the modern era. Yeah, I think that might be good. Um     
1:10:55     
I'll have to think about what that looks like though. Um yeah, and like you know this is also     
1:11:02     
part of the cybernetics group too, right? Like cybernetics, our interest in cybernetics is twofold.     
1:11:09     
you know, one is technical, but the other is sort of this historical aspect.     
1:11:14     
So, what is it about cybernetics we can kind of bring into the present? What is     
1:11:19     
it about the history of cybernetics that's kind of relevant to what's going on today and getting that out there for     
1:11:26     
people? Um, yeah, so that's that's good. Um, yeah, and then uh Barian stumbled upon     
1:11:34     
this link here. So Barian stumbled across this uh work. This is from     
1:11:40     
ETHZurich. This is from the soft robotics lab there. And um it's called the Orca hand     
1:11:47     
open source dexterity at your fingertips. So this is following up from the stuff we were talking about in     
1:11:54     
D.VARM on Monday with uh muscularkeeletal groups and simulating     
1:11:59     
that using reinforcement learning. Um this is of course talking about robot     
1:12:05     
dexterity or you know you can use this also for sort of human prosthetics and     
1:12:12     
control mechanisms for that. So Orca is a reliable cost-effective robotic hand     
1:12:19     
that combines human level dexterity with open-source accessessibility with plug-andplay design tactile sensors     
1:12:27     
and zeroot learning support. Orca accelerates manipulation research for all. And manipulation research is where     
1:12:34     
they're designing hands that can manipulate different objects and of course, you know, engage in skill     
1:12:42     
transfer so that you don't have to retrain the hand for every single dexterity movement that you make. So,     
1:12:49     
you know, like we don't well, we kind of learn if we sort of use a pen versus     
1:12:54     
have some dice in our hand and shake them and throw them on the table or we use a a computer mouse. We do have to     
1:13:02     
learn how to use those things, but it's very minimal in terms of the training. I mean, you you we have all sorts of     
1:13:08     
different types of uh cognitive shortcuts. So, there are affordances in     
1:13:13     
the objects. There's just encoding which is where you basically interact with     
1:13:19     
something and you can kind of figure out how it works and that's based on previous experience and the like. So we     
1:13:26     
want to make this more humanlike in terms of learning and training.     
1:13:32     
So general purpose robot should possess humanlike dexterity and agility to     
1:13:37     
perform tasks with the same versatility as us. A humanlike form factor further     
1:13:43     
enables the use of vast data sets of human hand interactions. The primary bottleneck in is in dextter     
1:13:51     
dextrous manipulation lies not only in software but arguably even more in hardware. So the bottleneck     
1:13:59     
isn't really about the software so much. They're arguing the bottleneck is the hardware. So this is kind of, you know,     
1:14:06     
we were thinking about this on Monday where we have this aspect of the     
1:14:11     
software and kind of how that trans skill transfer has to work and how we     
1:14:16     
can design sort of a reinforcement learning paradigm or maybe a curriculum learning paradigm to help us uh enable     
1:14:25     
that. But also, you know, we didn't even talk about the hardware. You know, what is it about the hardware that enables     
1:14:31     
this kind of learning? And of course, you know, they just kind of talked about, you know, simulating muscle     
1:14:37     
groups, but building it in a robot, it's far different. You need to have the     
1:14:42     
proper feedback in the mechanism. You need to have compliant materials for the     
1:14:47     
muscle and the surface of the robot's skin and all that.     
1:14:53     
So if you go to the embodied intelligence conference, there's this whole, you know, focus on sort of soft     
1:15:01     
materials, soft active materials where they're basically considering what are     
1:15:06     
the best materials to make a robot body out of. And that's key to the cognitive     
1:15:12     
question. So, um, robotic hands that approach     
1:15:17     
human capabilities are often prohibitively expensive, bulky, or require enterprise level maintenance,     
1:15:24     
limiting their accessibility for broader research and practical applications.     
1:15:29     
So, what if the research community could get started with reliable dextrous hands within a day? And this is just kind of     
1:15:36     
making this easy and open source and everything for people to use in different settings.     
1:15:43     
We present the open- source Orca hand, a reliable and anthropomorphic 17 degree     
1:15:48     
of freedom tendon driven robotic hand with integrated tactile sensors, fully     
1:15:54     
assembled in less than 8 hours and built for a material cost below 2,000 Frank or     
1:16:00     
2,000 CHF. We showcase Orca's key design features     
1:16:05     
such as popping joints, autoc calibration, and tensioning systems that     
1:16:11     
significantly reduce complexity while increasing reliable re reliability, accuracy, and robustness.     
1:16:18     
And so they benchmark the orca hand across a variety of tasks ranging from     
1:16:24     
tea operation to imitation learning to zero shot to real reinforcement learning. So this is a picture of Orca     
1:16:31     
version one. This is where you have tactile sensors on the fingertips,     
1:16:38     
popping joints at the joints and uh you know this just these are     
1:16:43     
things that provide feedback and flexibility or compliance respectively.     
1:16:50     
And you have the silicone skin which is again for compliance. So you don't want     
1:16:56     
to have something that's harsh when you're trying to grip something. You want something that gives and then     
1:17:01     
provide but still provides that feedback. And then of course to have a wrist with     
1:17:07     
enough degrees of freedom to make movements that reach for different things. And you can you know when you're     
1:17:13     
manipulating something you move your wrist, you move your joints and that gives you a lot of degrees of freedom     
1:17:18     
for exploration. Then of course you have to build with an     
1:17:23     
artificial hand. you need to build the hardware uh the sort of the actuation     
1:17:29     
and then the cooling fans which are important in a mechanistic can as well.     
1:17:35     
So this is kind of showing their design     
1:17:40     
um and this is version one which is this is all sort of separate from the actual     
1:17:47     
computational algorithm. This is how they're designing the the system. they     
1:17:52     
don't have any sort of muscle mechanism in here other than the actuators. So     
1:17:57     
that's you know kind of what we were talking about in the uh papers on the muscularkeeletal systems. Um those kind     
1:18:05     
of are just thinking about the muscle groups first or the the muscular control first and they don't even consider the     
1:18:13     
um actual mechanism of the actuation. But in this case they're think about the     
1:18:19     
actuation and not thinking about sort of any analogy to muscle.     
1:18:26     
So they think when you start doing the sort of simulating muscle in physical form it gets becomes expensive to do at     
1:18:34     
least nowadays. Maybe in the future it'll be different, but     
1:18:39     
so this is mimicking the human hand and just kind of, you know, mimicking that     
1:18:45     
as as being the sort of the gold standard for manipulation of objects. Of     
1:18:51     
course, we talked about um which, you know, of course you can compare that to the octopus where they have a very     
1:18:58     
different system of of uh manipulation of objects in the environment. And so,     
1:19:04     
you know, you could look at that as well, but um in this case, they're just looking at the human hand. So, just just     
1:19:10     
food for thought. And then they're manipulating this Rubik's cube. And this     
1:19:15     
person is wearing a prosthetic device over their hand trying to, you know, I     
1:19:22     
guess do a pose estimation for the movement, the hand movements involved in     
1:19:27     
a Rubik's cube. And then grip. So they're closing their     
1:19:33     
fist. Oh, go ahead Bian. Oh yeah. So I just found it interesting     
1:19:40     
that uh was the first time I saw something in the hardware aspect or     
1:19:46     
domain is open. So yeah it it removes a lot of testing and stuff if in the     
1:19:54     
future they try to uh use that can be open and open source community     
1:20:00     
can be open in the hardware area. Yeah, it's you know there's a lot of     
1:20:06     
open hardware but the benefit of open hardware of course is similar to open     
1:20:12     
source software and that you can you know usually you try to make very simple for people to replicate it right you     
1:20:18     
give them the parts you might give them something they can 3D print or something very easy to get uh materials and then     
1:20:26     
you give them the plans and they can build their own thing but then the benefit of that is you can benchmark it     
1:20:31     
in all sorts of different environments ments or in all the different context use cases and then you you know ideally     
1:20:38     
you would have a way to get feedback from those groups like people will set up discussion boards and they'll say     
1:20:44     
okay you know if you use this open- source protocol or open hardware     
1:20:50     
protocol you know how what's your experience with it how can we improve it can we create issues that are     
1:20:56     
improvements upon the design and if you have a bunch of people using it in     
1:21:01     
different ways you You know, you can solicit a lot of potentially a lot of issues and address those and then     
1:21:10     
improve it a lot faster than if you had to do all that testing yourself and then release like the perfect version where     
1:21:18     
you had to actually go through and evaluate it and then come up with suggestions for the next version.     
1:21:26     
Those sorts of things. So, yeah, this is good. Um, thank you     
1:21:33     
Yeah, these are the kinds of projects that neuroch students work with. Yeah, definitely kind of a looks like a     
1:21:40     
research student project type thing where you could do like here's a here's     
1:21:45     
a piece of hardware. Can you replicate this? Can you build this and implement it?     
1:21:50     
Yeah, people are using EMG as as sort of the control. So, you send EMG signals     
1:21:56     
into the hand. You have to decode the EMG signals so you know which signals are kind of doing what and then you map     
1:22:05     
that to the device. We talked about this paper I think it was last time and we kind of went through this uh abstract     
1:22:12     
and I just wanted I know this is something Barshan was interested in so I wanted to talk about it a little bit     
1:22:18     
more. This is this paper on the developmental visual diet. So this is where they use the uh human visual     
1:22:26     
system development in the human visual system as an inspiration for guiding     
1:22:32     
curriculum learning and training of the model. So this is where they go through um and     
1:22:41     
talk about how we can use this sort of um approach to improve     
1:22:47     
uh machine learning models. So they talk about kind of the benefits     
1:22:53     
of how humans learn how to uh evaluate visual information and then how AI     
1:23:00     
currently does it and that there's this gap. So to close the gap, you can take     
1:23:07     
inspiration from human vision, how that develops from early infancy into     
1:23:12     
adulthood. And so they quantified visual maturation by synthesizing decades of research into     
1:23:20     
a novel developmental visual diet for AI vision. So we didn't really get into the figures     
1:23:26     
of this paper, but we can get into them now. Um so this is their figure one. Um     
1:23:33     
and so uh the text here     
1:23:39     
following the developmental trajectory of visual acuity, chromatic sensitivity and contrast sensitivity from newborn to     
1:23:47     
25 years old as an effective means of training robust AI vision systems. So     
1:23:53     
basically they're looking at two components of visual acuity, chromatic sensitivity and contrast sensitivity.     
1:24:00     
and they're evaluating this from newborns to 25 year olds and then using     
1:24:06     
that knowledge to build their model. So the first thing they have is they     
1:24:12     
have an image data set. They're using Eoset from ImageNet and they're using     
1:24:18     
that to they're pre-processing those data and looks like uh for a standard     
1:24:24     
artificial neural network processing the network that you're training is always     
1:24:29     
at a mature state. So all you're doing is you're deriving     
1:24:34     
uh weight matrices in the network but the network is always at the same level of maturity meaning it doesn't develop     
1:24:42     
in any way. It doesn't tune itself in in the developmental sense and what that     
1:24:48     
means in terms of an analogy is is you know kind of ky because that could mean     
1:24:53     
a lot of things. I mean we take weight matrices from the notion of     
1:24:59     
neuroplasticity basically where um synaptic connections get tuned to     
1:25:05     
certain stimuli to certain um information and that's basically how     
1:25:12     
weight matrices um emerge is through sort of getting experience with a data     
1:25:18     
set and then having it a statistical description of that data set embedded in     
1:25:24     
those weights. But of course that's not what happens in development. What happens in development     
1:25:29     
is you start from a state of very low maturity and you move to a state of high     
1:25:35     
maturity. And they're using the example of human development which is of course     
1:25:41     
uh where a lot of the maturation happens maybe before age 10. And then there's     
1:25:48     
this maybe contextual maturity as you age up to 25 years old. So it's very     
1:25:55     
much instead of a linear function which is flat and it's always mature, you get     
1:26:02     
this logarithmic function where there's a lot of maturity early on and then     
1:26:07     
refinement later. So that's for pre-processing. Then for artificial neural network training, they use a     
1:26:14     
number of different candidate network approaches um and models. And then for this robust     
1:26:21     
vision test, the battery involves looking at shape texture bias, abstract     
1:26:27     
shape recognition, degradation robustness, and adversarial robustness.     
1:26:33     
So, of course, they're looking at uh the ability to recognize shapes in different     
1:26:40     
backgrounds. Uh looking at the difference between shape and texture,     
1:26:46     
and then you know what happens when you degrade an image. Is the model robust     
1:26:51     
enough to recognize the object in the image despite it being     
1:26:57     
degradated or warped in some way? or if you have two examples that are very     
1:27:03     
similar or two identical images that have different labels, can the model     
1:27:10     
distinguish between them? So that's basically what they're doing here. And then they have uh figures B     
1:27:17     
through E. And those are where we have we're looking at the developmental     
1:27:22     
trajectories of the three aspects of vision modeled by DVD which are visual     
1:27:27     
acuity, contrast sensitivity, chromatic sensitivity and then those are     
1:27:34     
um B through uh E through D and then um this is as     
1:27:41     
synthesized through a multitude of psychophysical experiments across age groups. So this is just kind of     
1:27:48     
reviewing the uh figure B and C reviewing the literature. Uh the first     
1:27:54     
one is uh where we're looking at Snell and visual acuity. So it's a certain     
1:27:59     
measure of visual acuity and there's this parameter within that measure called the blurring sigma and that     
1:28:06     
blurring sigma increases um with sort of at a very early age like     
1:28:13     
within a few months it saturates down to zero. And so you have, you know, you     
1:28:20     
start off not being able to see very much and then by the, you know, age of like three or four months, you're able     
1:28:27     
to see at pretty good visual acuity and then it just drops almost to near uh     
1:28:34     
zero visual acuity, meaning you can detect very fine grained objects     
1:28:40     
at about maybe 25 to 30 months, maybe 40 months. So     
1:28:47     
this is all in infancy basically. Um and then you know as you get toddlers you     
1:28:53     
get up to the age of what a toddler is. And so the these are the different studies that have looked at this. So     
1:29:00     
most of the studies have focused on this period where you're gaining visual acuity and then they've been some     
1:29:06     
studies where that visual acuity is saturated. They just show the different references     
1:29:12     
here and there's this fitted developmental trajectory. So from all those studies, we can get a sense of     
1:29:18     
what this function should look like. For contrast sensitivity, there's this     
1:29:24     
frequency magnitude threshold. So we're looking at contrast instead of visual     
1:29:30     
acuity. And again, we have all these studies that show kind of what these     
1:29:35     
look like over a period of months in development from 0 to 300 months. And we     
1:29:42     
have all the studies here. we can derive this function which is sort of a a     
1:29:49     
S Sshaped curve. So it's a a logistic function and we can use that again for     
1:29:57     
our training regimen. And then we have chromatic sensitivity and the component     
1:30:04     
of color fidelity. And this is where sort of looking at     
1:30:09     
this one study, no block at all 2001. and they look at average chromatic     
1:30:14     
sensitivity as a function of the proton and triton axes. So this is just kind of     
1:30:22     
averaging that out and that's what they use for their model.     
1:30:28     
So E shows um kind of how this what these images look like. So if you     
1:30:34     
combine all these things, remember we said visual acuity is very um very weak     
1:30:40     
at one month but then gets refined as we get towards 300 months. So we have one     
1:30:48     
month which is where everything is really blurry and in our model     
1:30:54     
everything is really blurry as well. In four months it start things start to clear up. 16 months they clear up even     
1:31:01     
more. 64 months and then 256 months things are very sharp.     
1:31:09     
And so that is um how they kind of go through this. They you know kind of     
1:31:15     
model this refinement of ability to see very small feature sizes and this is how     
1:31:23     
this works. Um so to model the continuous development     
1:31:29     
of human vision we reviewed the existing psychophysical evidence and how human vision develops from newborns to 25     
1:31:36     
years of age and synthesized the developmental trajectories of three core dimensions of phys physical maturation.     
1:31:44     
So visual acuity chromatic sensitivity and contrast sensitivity. So this is all     
1:31:49     
in this pre-processing pipeline for AI vision. Across the series of experiments, we demonstrate that guiding     
1:31:56     
AI through this human developmental visual diet instead of the gold standard of high resolution AI vision training is     
1:32:04     
an effective means towards approaching humanlike robustness in visual inference. deep neural networks trained     
1:32:12     
with DVD exhibit shape bias beyond the state-of-the-art radio reliance on     
1:32:17     
spatial integration of visual features increased capability of abstract shape recognition and heightened resilience to     
1:32:24     
image degradations and adversarial attacks. So this actually this approach helps to     
1:32:32     
build on you know sort of the robustness and the uh performance of the model in     
1:32:40     
ways that the state-of-the-art pipeline does not. Importantly, the translation of human     
1:32:46     
psychophysical data into an efficient image prep-processing pipeline for AI     
1:32:52     
necessarily involves selecting a level of abstraction that balances replication detail with algorithmic considerations     
1:33:00     
that will enable e easy adoption in the field. Due to the many remaining differences with biological vision, DVD     
1:33:08     
is thus not to be considered a veritical mirror of the perceptual world of infants. So this is not you know kind of     
1:33:16     
a this is not actually what happens in development. This is like what we know     
1:33:22     
from the data and what we're kind of extracting from the data. So that means     
1:33:28     
it's it's kind of a rough model of what's actually happening in infants.     
1:33:33     
But we know that if we can take those broad principles and apply it to um this     
1:33:39     
developmental visual diet or DVD and use that as sort of a guide, we can get the     
1:33:46     
benefits of biological image processing in humans.     
1:33:53     
So they have a number of things here in this figure too. Um this is models trained with DVD close the gap to human     
1:34:01     
level shape bias. So these are the different types of stimula they tested the model on. They     
1:34:08     
have these Q conflicting stimula. So they have an airplane and an     
1:34:13     
elephant, a bear and a clock, a bicycle and elephant, a bird and a clock and     
1:34:19     
they're just these conflicting stimula and they train it on that. Then they     
1:34:25     
have the shape bias accuracy tradeoff. So they see that the shape bias accuracy     
1:34:31     
trade-off um increases with maturity.     
1:34:36     
So shape bias increases as you get exposure to more shapes, as you become familiar with more shapes. So when     
1:34:42     
you're four to six years old, you're not as locked into certain shapes being a certain thing. It could be a number of     
1:34:49     
different things. And then as you move to adulthood, you sort of gain this bias. You also gain accuracy in in in     
1:34:58     
encoding that shape. So that's kind of what these dotted lines are. Then you     
1:35:04     
have this dotted line which is the performance of the model. And they're testing this on mini eco set     
1:35:12     
accuracy versus shape bias. So as the shape bias decreases the accuracy     
1:35:19     
increases which is this kind of um you know so the baseline here and then this     
1:35:25     
is the DVD performance. Um in this case in this graph you have     
1:35:30     
eoset accuracy and versus shape bias and again you have these DVD models here as     
1:35:38     
the accuracy increases the shape bias decreases.     
1:35:43     
Then you have the shape bias benchmark which is uh for all these different models and they look at uh supervised     
1:35:53     
models, SSL models, multimodal models, the DVD models and then humans. So they     
1:36:01     
can look human performance versus all these different models and then of     
1:36:06     
course the DVD models uh for shape bias. And so we can see     
1:36:11     
that like in humans there's a high level of shape bias. In the DVD models you     
1:36:16     
have a high to moderate level of shape bias where the multimodal model models you have a little bit less shape bias.     
1:36:23     
And then for the supervised models and SSL models they have a low to moderate     
1:36:28     
amount of shape bias. So the shape bias is lesser in some of these supervised     
1:36:34     
models and greater in the multimodal models DVD models. And then of course     
1:36:39     
the human models which are of course uh in development you have four to six     
1:36:45     
years old, seven to nine years old, 10 to 12 years old, 13 to 15 years old and     
1:36:51     
then the adult and so the adult you have a lot less variation     
1:36:56     
and it's it's a high almost bias of 1.0. So you get like a tightening of the bias     
1:37:05     
over age with the DVD models. You also see this tightening over a jigus. The     
1:37:12     
ResNet 50, the ResNet 50 ECO set DVDP versus DVDP     
1:37:19     
and then ResNet 50 ECOS set DVDS. So DVDS has the highest level bias     
1:37:26     
amongst the DVD models. So but they're comparable more or less the multimodal models that they've     
1:37:33     
tested. So, it's interesting how the multimodal models and these developmental visual     
1:37:39     
diet models have a higher level bias and they're closer to what humans are doing than the supervised models. Um     
1:37:48     
and so their results are basically that you know you can um     
1:37:55     
successfully map from sort of human development to these kind of models and see a performance uh difference between     
1:38:03     
that and some of the other types of machine learning models.     
1:38:08     
Um EVD training promotes near human levels of shape bias. So a defining     
1:38:14     
feature of human visual perception is that when presented with object images     
1:38:19     
for which the texture and shape information are in conflict, observers reliably report perceiving the object     
1:38:26     
category in line with the shape information. So this is where you have this shape bias     
1:38:33     
that allows for people to sort of disambiguate objects. And so if you can     
1:38:39     
do that, you know, that's helpful because you have access to the label. It's also not helpful if it looks if     
1:38:46     
something is a certain shape, but it's actually not that thing. We make category errors like that all the time.     
1:38:52     
Um, but in general, this helps us to recognize things from incomplete     
1:38:58     
information or get the gist of what an object is and then just kind of     
1:39:04     
correctly categorize it. So there's a lot of flexibility in human cognition in that sense. But it also sometimes leads     
1:39:11     
to us mclassifying things. So this is you know I don't want to say a problem     
1:39:16     
in human cognition because quite frankly it's more robust than maybe an     
1:39:22     
artificial model. So that's kind of what you know what we see in humans     
1:39:29     
by and this you know this bias increases in development as we saw in the graphs.     
1:39:35     
uh in four year olds we have a shape bias of 0.9 in adults a shape bias of     
1:39:41     
0.96 by contrast DNN's irrespective of     
1:39:47     
network architecture it's deep neural networks irrespective of network architecture training set data set size     
1:39:55     
or training objective exhibit a strong tendency towards texture-based decisions.     
1:40:02     
So their shape bias scores typically fall within the 0.2 to 0.4 range. So     
1:40:07     
they're much lower level of bias. And so they're the way in which DNN's usually     
1:40:14     
work is they focus on texture-based decision making, texture-based features.     
1:40:20     
The texture preference and deep neural networks therefore constitute a signature difference to human vision. So     
1:40:27     
this is kind of the difference here. And what they're trying to do is exploit a different type of uh criterion for     
1:40:35     
uh feature recognition and feature selection. Okay. So we explored the effect of     
1:40:42     
developmental visual diets on the shape texture bias and artificial neural networks by performing a comprehensive     
1:40:48     
hyperparameter sweep of developmental visual diet based on the ResNet 50     
1:40:54     
model. So this is trained on smaller scale image data sets which was called mini     
1:41:00     
eco set which is 280,000 images um observing a trade-off between shape     
1:41:06     
selectivity and accuracy across hyperparameter settings representative model configuration for     
1:41:13     
chosen for a subsequent analysis. These are the DVDS which is shape bias favored.     
1:41:19     
Um DVDP which is increased shape bias from baseline     
1:41:26     
and then DVDB not DVDP but DVDB which is shape bias at a modest accuracy     
1:41:33     
loss of approximately 4.9% compared with gold standard training     
1:41:38     
with high resolution images. So DVDS stands for shape bias. DVDP     
1:41:46     
stands for recognition performance favored and then DVDB is where we have a     
1:41:52     
balance between the two. So DVDs is shape bias. P is performance favored and     
1:41:58     
then DVDB sits in the middle. Uh crucially when scaling these three     
1:42:04     
variants the full EOS set data set training. So they instead of using this subset of images of 280,000 images, they     
1:42:12     
used the entire set of 1.5 million images with 565 basic level categories.     
1:42:19     
The prior results were closely reproduced. So they were able to reproduce the results they got on um     
1:42:26     
this mini data set on the entire data set when but crucially when scaling these     
1:42:33     
three variants to full EOSET training the prior results were closely reproduced when the control while the     
1:42:40     
control model achieved a shape bias of 0.34 at 63% accuracy DVDs delivered a shape     
1:42:48     
bias of 0.9 that is within the human range and DVDP exhibited a shape bias of 0.7     
1:42:56     
alongside a slight accuracy increase compared from the baseline.     
1:43:01     
So 63% versus 65%. And DVDB delivered a shape bias of 0.8     
1:43:10     
close to the human range at a marginal 4.3% accuracy decline over baseline.     
1:43:17     
Thus this developmental visual diet training provided an increase in shape selectivity     
1:43:24     
and uh this is differs. DVDP was 106%     
1:43:30     
DVDB was 141% and DVDS was 165%.     
1:43:37     
Over our gold standard baseline with high resolution training. So a category specific depiction of     
1:43:44     
shape bias for DVDP. The resonant 50 baseline in human observers is provided as a supplement     
1:43:51     
which where they show I'm not getting into supplementary figures which you can look that up for yourself     
1:43:57     
where they show examples of shape texture behavior for DVD     
1:44:03     
and then compare that with ResNet 50 and then chat GPT4 4.     
1:44:10     
So, so importantly, the shape bias observed in our DVD trained ResNet 50     
1:44:15     
model not only outperforms the corresponding control models by a large margin. So, the control models are the     
1:44:21     
other models that they use um but by also all other contemporary ANN models     
1:44:28     
tested setting the state-of-the-art in shape selectivity and closing the gap to the human range of shape selectivity.     
1:44:35     
These included standard supervised convolutional neural networks or CNN's, vision transformers or VITs,     
1:44:43     
subsupervised models and multimodal vision language models or VLMs which we saw in that graph with the different     
1:44:50     
models and their performance. Note that these models include DNN's     
1:44:56     
trained on orders of magnitude more data as well as models operating on orders of     
1:45:01     
magnitude more model parameters highlighting the effectiveness of DVD training in shrinking down the amount     
1:45:07     
number of parameters we have to deal with as well as the data set size for training.     
1:45:13     
This is one of the things about like a lot of these developmental approaches is the promise is that we don't need to use     
1:45:20     
as much training data. we can just take a smaller training data set and somehow     
1:45:26     
extract enough information out of that to build good classifi u you know build     
1:45:33     
good recognition models. So in development we know that you know babies don't need that much information to make     
1:45:40     
proper classifications for example we want to be able to replicate that in our     
1:45:46     
models but model what computational models so far have required massive     
1:45:51     
amounts of data and then you know if you go back to this whole debate in cognitive science     
1:45:58     
between sort of the statistical uh models and the symbolic models you     
1:46:04     
know the argument for statistical models was that basically if you just train     
1:46:11     
your model with enough data, you can really build something akin to     
1:46:16     
artificial general intelligence. Whereas the symbolic people always argued that     
1:46:22     
you needed heavy symbol, you know, heavily symbolic systems to accomplish     
1:46:27     
that. And then of course we've had people the um neuros symbolic people who     
1:46:34     
have argued that we need a mix of these two things. And missing from that sort of     
1:46:40     
uh that classification scheme are developmental people who you might say     
1:46:47     
you know or might argue that you don't need that much data training data to achieve human level     
1:46:54     
performance given that you have a framework that mimics human development.     
1:47:02     
So their results and then they have some other figures in here where they show the evolving shape bias over     
1:47:09     
developmental time. So their DVD uh models will you know exhibit this     
1:47:15     
increase in accuracy over time as opposed to the baseline models. So the     
1:47:20     
baseline models don't change their accuracy remains constant but the developmental models start with a lower     
1:47:27     
level of accuracy and then jump up to a greater accuracy over time.     
1:47:32     
And then they have this uh this controlled rearing graph which is basically where they can control the     
1:47:38     
input data and the DVDB model performs better on shape bias than the baseline     
1:47:45     
or some of these you know they have an array of DVDB models here where they     
1:47:50     
show the different attributes. So in controlled rearing the the baseline     
1:47:56     
model DVDB model has the highest level of shape bias and then you look at     
1:48:02     
visual acuity plus contrast contrast only color plus contrast and then that     
1:48:08     
is a much higher shape bias than if we look at visual acuity plus color visual     
1:48:14     
acuity only or color only. So you need to have contrast cues in addition to     
1:48:20     
visual acuity or you need to have the model in its entirety to get that level     
1:48:25     
of shape bias. So color does not seem to be a component of shape bias or I mean     
1:48:31     
it it does contribute to shape bias but it doesn't contribute to shape bias on its own. Nor does visual acuity     
1:48:38     
contribute to it on its own. You need to have contrast in the model or all three factors in the model together.     
1:48:48     
Okay, I think I'm going to stop there. This is feature attribution, but I think a lot of the subsequent     
1:48:55     
figures just kind of support this basic idea.     
1:49:01     
We had a couple of comments in the chat here. Um, this is Jesse's comment.     
1:49:07     
Unrelated question from Morgan about Frontier Tower. Is there anything like that or any partnerships with the Boston     
1:49:14     
area um like MIT or any of those groups? Um I may reach out to Frontier Tower in     
1:49:21     
general around partnership opportunities. Curious if you have any thoughts on that can follow up     
1:49:26     
elsewhere. So I don't Well, first of all, if anyone     
1:49:32     
any questions about the paper, you know, go for it. Otherwise, if Morgan wants to     
1:49:38     
respond to that comment, he can.     
1:49:43     
He said, uh, not Frontier Tower, but Boss Lab in the Biopol.     
1:49:48     
Yeah, it's um, you know, Frontier Tower is kind of some somewhat unique. Um,     
1:49:57     
and, uh, I don't think they're looking for a a spot in Boston. Um, you know, at     
1:50:04     
at this time. Um but uh Boss Lab is is is the kind of equivalent that is the     
1:50:12     
community bolab in Boston. Um and you definitely do events with them.     
1:50:19     
the the um you know the these are the     
1:50:25     
there's a nice network of of labs associated with the MIT how to grow     
1:50:32     
almost anything in introduction to synthetic biology. Yeah. Um actually I'll drop a I'll drop     
1:50:40     
a link. Um David Kong gave a a really nice TED talk like     
1:50:46     
less than a year ago. Um, but uh that     
1:50:53     
I I you know I didn't really recognize how closely aligned their vision is with     
1:51:00     
with um you know biopunk and kind of distributed     
1:51:09     
know distributed arrays of labs. But yeah,     
1:51:15     
hope that's helpful. Yeah.     
1:51:21     
So, did we have any other comment Terry on the development of visual diet paper?     
1:51:30     
Well, sorry, I should have said, yeah, I mean, uh, you know,     
1:51:38     
I I was originally a cognitive development person. Yeah. Yeah. So, you know, I I I love this work. Um,     
1:51:46     
you know, super interesting. I like uh I like people, you know, attaching GoPros     
1:51:53     
to babies. Yeah. Um and uh you know um     
1:52:02     
uh so I was just thinking about the um     
1:52:09     
you know Amanda had suggested the wrangle beer paper like like what is     
1:52:14     
that like dynamical systems applied to     
1:52:20     
coside or something like that. Anyway just just makes me think of the the Indiana     
1:52:28     
um Linda Smith. Yeah. Group, you know, anyway, you know, like     
1:52:34     
like being applied to cognitive development as well, right? Yeah.     
1:52:40     
And so, yeah, really nice um     
1:52:48     
great great extensions of that kind of work. Yeah, I think um I think it's yeah, it's     
1:52:56     
pretty good. It's pretty uh rigorous work. I mean, they went to the literature, they found all the sort of     
1:53:02     
the data, they fit fit a curve to the data and they developed this uh     
1:53:07     
technique that is both consistent with how we train     
1:53:13     
uh you know models and how it might be you know mimic human development. So it     
1:53:19     
basically has these stages where you have sort of this acquisition and then you have the development of the feature     
1:53:25     
or development of the the trait that starts with kind of a general sort of     
1:53:31     
way to do it and then it refineses that ability over time. I got you.     
1:53:37     
Yeah. Yeah. the the the last reading group we did was the um     
1:53:45     
last month's was the distilled pub circuits um I think thread you know and     
1:53:54     
and it was very much you know it was very much digital system     
1:53:59     
uh comparisons with with neural network training you know um but but this is     
1:54:07     
this is the the much more realistic, you know, like how do those how do those     
1:54:14     
naturally develop? That's that, you know, is is awesome.     
1:54:21     
I did want to get a little bit into this paper. Um I think I can probably get through in 15 minutes. This is a recent     
1:54:28     
paper in artificial life. Um this is thinking about embodied collective     
1:54:33     
cognition systems. So again, these are like agents that are doing collective behaviors and they're embodied and uh     
1:54:41     
it's uh called system 0123 and some of the system one system two     
1:54:49     
types of cognition that's in the cognitive science literature. You kind of know what this means. Let's go     
1:54:55     
through this is from a Japanese group I think based at Kyoto University, University of Tokyo.     
1:55:02     
And uh yeah, so they're kind of uh taking again like Sikana, they're taking     
1:55:09     
a perspective that's a little bit different than sort of the Silicon Valley     
1:55:15     
MIT uh Stanford school of thinking about     
1:55:20     
this. So let's go through the abstract. Um so     
1:55:25     
the article introduces the system 0123 framework as an extension of dual     
1:55:31     
process theory employing a quad process model of cognition. So dual process     
1:55:37     
theory is where you have two types of thinking. So you have like the basic     
1:55:44     
type of thinking and then you have the reflective type of thinking that that sort of hierarchy. uh Ron Sun uh     
1:55:51     
developed dual process theory for cognitive architectures. So this is also     
1:55:57     
another place where this is coming from. Um so they're developing this system uh     
1:56:03     
for different levels of thinking in an agent. So they're employing this quad     
1:56:09     
process model of cognition meaning there four levels of thinking in terms of the     
1:56:14     
cognition. So expanding upon system one which is fast intuitive thinking and system two     
1:56:22     
which is slow deliberative thinking. So this is the system one and system two     
1:56:27     
distinction um made by conaman where you're doing you have the system that allows you to     
1:56:34     
make fast judgments. It's intuitive and then you have the slower system which is deliberate thinking or reflective     
1:56:40     
thinking. But they're also building two more levels onto that. So the first uh     
1:56:47     
additional level is where like it's a system zero which represents precognitive embodied processes. So it's     
1:56:55     
like what's happening with the body. Uh we know that like uh there's a lot     
1:57:01     
happening in the sensors in the skin sensors in the muscle that gets     
1:57:06     
processed up to the brain. That's all that's sort of system zero. So you have to have a body. The body is taking     
1:57:12     
information from different directions. It's being integrated in the peripheral nervous system before it goes to the     
1:57:18     
central nervous system. So that's system zero. Um there's also we know that     
1:57:24     
there's this prefiltering function within the peripheral nervous system. So not all information gets represented in     
1:57:31     
system one. Even it gets pre-filtered and gets presented to system one in a     
1:57:37     
certain way that then system one can operate on and then of course system two     
1:57:43     
will take that information as well. So we have system zero which is this     
1:57:49     
embodied specific level. We have system one which is this fast intuitive     
1:57:54     
thinking and then system two which is slow deliberative thinking and then system three which is of course     
1:58:02     
encompasses collective intelligence and symbol emergence. So it's this level above deliberative thinking reflective     
1:58:09     
thinking which is where agents are collectively doing things. So we've     
1:58:14     
talked about you know first of all I've talked about the emergence of collective behaviors which is not something that is     
1:58:22     
you know additive from individuals it's more of something that emerges from their interactions but also from this     
1:58:28     
concept of stigmore meeting which is where you have this uh     
1:58:37     
where you might have environmental cues that get deposited by individuals     
1:58:44     
They could be maps. They could be signs. They could be pherommones that guide the     
1:58:49     
rest of the people or the rest of the organisms in the collective to a certain     
1:58:55     
outcome. So this is the systems three thinking. Okay. So we have system zero, one, two,     
1:59:02     
and three. We contextualize this model with Bergson's philosophy by adopting     
1:59:07     
multiscale time theory to unify the diverse temporal dynamics of cognition.     
1:59:13     
System zero emphasizes a morphological computation and passive dynamics,     
1:59:19     
illustrating how physical embodiment enables adaptive behavior without explicit neural processing.     
1:59:26     
Systems one and two are explained from a constructive perspective incorporating neurodynamical and     
1:59:33     
artificial intelligence viewpoints. In system three, we introduce collective predictive coding to explain how     
1:59:39     
societal level adaptation and symbolic emergence operate over extended time     
1:59:44     
scales. This comprehensive framework ranges from rapid embodied reactions to     
1:59:50     
slow evolving collective intelligence. So this is not only a difference in sort     
1:59:56     
of level of processing but it's a temporal difference. So the lower levels are faster they happen at a more rapid     
2:00:04     
pace and then the higher levels build upon that and they can draw from a sort     
2:00:11     
of a long series of events. So system zero and one have a long series of     
2:00:16     
events that they're exposed to. systems two and three can sample from that and produce an outcome.     
2:00:24     
So systems one and two are explained. Okay.     
2:00:30     
Uh in system three we introduce Okay. In system three we introduce     
2:00:35     
collective predictive coding to explain how societal level adaptation in symbol     
2:00:40     
symbol emergence operated over extended time scales. This comprehensive framework ranges from rapid embodied     
2:00:47     
reactions to slow evolving collective intelligence offering unified     
2:00:53     
perspective on cognition across multiple time scales, levels of abstraction in forms of human     
2:00:59     
intelligence. The system 0123 model provides a novel theoretic     
2:01:05     
foundation for understanding the interplay between adaptive and cognitive processes thereby opening new avenues     
2:01:13     
for research in cognitive science AI robotics and collective intelligence.     
2:01:20     
So this is you know something it's kind of similar to what we're doing with metabrain models     
2:01:26     
and kind of similar to um this notion of sort of continual learning where you     
2:01:34     
have this you know we have this sort of uh learning is a time series or learning     
2:01:41     
from a time series and then building upon those events and sometimes that     
2:01:47     
sequence is not linear. So I mean you know you have sort of exposure to an     
2:01:53     
environment that's continuous and the some component of the agent is     
2:01:59     
sampling from that and then you know acting upon that but it's not necessarily linear. It's not necessarily     
2:02:06     
completely sampled and there's all sorts of interesting dynamics going on there.     
2:02:12     
So I think this gives us a framework for thinking about sort of the hierarchy of processing     
2:02:17     
but also thinking about continual learning. So um yeah they they talk about system     
2:02:25     
one and system two um they site conaman and Benjio talk     
2:02:31     
about this in human cognition and in AI respectively.     
2:02:37     
And so you know they talk about the system one and system two models which have sort of a limited application.     
2:02:46     
So why do we want to add levels? And it's because the system one system two     
2:02:52     
dichotomy focuses primarily on internal cognitive processes overlooking     
2:02:57     
embodiment and sensory motor interactions of the environment.     
2:03:02     
They do not account for collective intelligence in which language and symbol systems evolve dynamically within     
2:03:08     
human societies. They lack a broader temporal hierarchy failing to capture how cognitive     
2:03:14     
processes unfold across multiple time scales from rapid reflexive reactions to     
2:03:20     
the slow evolution of societal knowledge. And so then these limitations become     
2:03:27     
more pronounced as we try to interact more with the real world. So if we're     
2:03:33     
building embodied AI systems, we see the problems with this simple dichotomy. We     
2:03:38     
need to add more levels to get this sort of better integration with the world     
2:03:44     
better continual learning. So a lot of times uh robots fail to     
2:03:52     
adapt to real world behavior because their cognitive models often fail to integrate fast reactive motor control     
2:03:59     
with slow deliberative planning. Moreover, AI and robotics face challenges in modifying the languages     
2:04:05     
they use for communication and in contributing to the cultural and societal formation necessary for     
2:04:12     
collective survival. um their cognitive models often fail to     
2:04:17     
manage long-term collective semiodic dynamics that is symbol emergence     
2:04:22     
engineering their ability to flexibly adapt to language and symbolic systems     
2:04:28     
in the context of their environment. So they talk about the system 0123     
2:04:33     
framework. Uh this framework is inspired by Bergson's philosophy of time which     
2:04:40     
provides a theoretical foundation for understanding how cognition operates at multiple temporal scales from super fast     
2:04:48     
embodied reactions to super slow collective intelligence.     
2:04:53     
So I like how they frame sort of the embodied reactions to collective intelligence in terms of time. I think     
2:05:01     
that's good. um you know especially thinking about those time scales and the differences between them and how those     
2:05:07     
interactions have tend to happen. Um then they bring up the free energy     
2:05:14     
principle. So inside the brain we have the free energy principle and how this     
2:05:19     
gives us a model for how biological systems remain adaptive. Um however cognition is not limited to     
2:05:26     
processes within an individual brain. Um and so they they have very heavy     
2:05:33     
emphasis on semiodics here. Um so in semiodics it is widely recognized that     
2:05:39     
symbol systems have arbitrariness meaning that the relationship between the signifier and the signified is not     
2:05:46     
fixed and evolves across communities and time periods. We emphasize this arbitrariness to highlight the core     
2:05:53     
argument of this article. the existence of super slow dynamics in human or collective intelligence.     
2:06:01     
Human societies continually update shared simple systems that is systems of     
2:06:06     
signs in their relationship with phenomena over time through social interactions. This arbitrariness allows     
2:06:13     
adaptive flexibility and semiodic communication. Humans utilize a semiodic plasticity     
2:06:21     
analogous to neuroplasticity in the brain but not identical to it to engage in intelligent activities no single     
2:06:28     
individual can achieve alone. And this is what they refer to as system three.     
2:06:35     
So yeah, then they they kind of talk about how you have all sorts of different types of adaptive behaviors     
2:06:42     
without neural learning. They bring up passive dynamic walkers as an example of this. Uh these examples illustrate how     
2:06:50     
body environment interactions contribute to flexible, robust, and intelligent behavior generation.     
2:06:57     
Um and so this and then they kind of contrast what they're doing with foundation models and multimodal large     
2:07:04     
language models. Um and so rob robotics foundation models focus primarily on     
2:07:11     
computational data processing and neglect embodied interactions. So this is why they're proposing the system 0123     
2:07:18     
model as as sort of a a robotics foundation model.     
2:07:25     
And then they talk about richer hierarchical time scale or MTS understandings of cognitive systems. We     
2:07:33     
aim to establish a reciprocal dialogue between Bergson's theories of memory, the emergence of consciousness,     
2:07:40     
discussions of cognitive systems and intelligence. We attempt to extend Bergenson's MTS     
2:07:45     
framework, which is this richer hierarchical multi-time scale framework by examining both its similarities and     
2:07:52     
differences to contemporary cognitive models. So um and then of course their their     
2:07:59     
system three is rooted in the collective predictive coding hypothesis introduced by Tennaguchi in 2024.     
2:08:08     
And so that's how they developed their system 3. But they basically want to extend systems one/2     
2:08:16     
into this quad process model. Okay. Um yeah. So that's basically the     
2:08:24     
idea and it really kind of goes over a lot of this and reviews it thinking about fast and slow and neurodynamical     
2:08:30     
systems. So you know again we're dealing with fast systems 0 and one slower     
2:08:37     
systems two and three and then uh so their approaches were     
2:08:43     
inspired by the dynamical systems theory for autonomous agent behavior emphasizing the tight coupling between     
2:08:50     
the agents internal dynamics and the external dynamics of its environment. So this is where they quote Randall Beer uh     
2:08:58     
some of his earlier work from the 90s. This original dynamical systems approach     
2:09:03     
which may correspond to system zero and one explain an agent's lower level or     
2:09:08     
reflexive behavior in response to environmental changes with the concept of entrainment into attractors. So they     
2:09:16     
they talk about this tight coupling uh which is of course a a closed loop     
2:09:22     
feedback system and that that clos feedback system is tightly coupled. So     
2:09:27     
if we think about like sensory motor embodiment, we can think about like the     
2:09:33     
body as being tightly coupled to the environment relative to maybe like     
2:09:38     
symbol production or reflect reflexiveness in terms of like what am I     
2:09:44     
thinking? And so this tight coupling has you know     
2:09:50     
it has a very strong connection with this shorter time scale because if you     
2:09:55     
have a longer time scale you have too many things that can intervene in the tight coupling and that feedback loop     
2:10:01     
the or the efficacy of that feedback loop breaks down. So, we're all familiar     
2:10:06     
with the sort of the the tight sensory motor coupling that you see with say like an agent um that's interacting with     
2:10:14     
say its environment where maybe it's trying to walk or it's trying to move an object and it gets constant feedback     
2:10:21     
from the environment and it's basically trying to match what's in the environment.     
2:10:28     
So, that's system 0 and one. And so, it's very easy to model that. we     
2:10:33     
know how to do that. Um but then we also have of course this these levels two and     
2:10:39     
three or these systems two and three. So this is where we need to add in an an internal model to this. So we have the     
2:10:48     
internal dynamics and the external dynamics of the environment characterized by this uh tightly coupled     
2:10:54     
closed loop feedback system. But then we also have this internal model which is     
2:11:01     
where uh this is something as as classic in robotics. This was developed first by     
2:11:06     
Walpert in 1995 where they have a forward model and they have a reverse     
2:11:11     
model. So they have the forward model which is sort of the predictive model and the reverse model which is sort of     
2:11:18     
the model that produces the behavior. So um they go back to Walpert's work in     
2:11:25     
1995 on forward internal models which correspond with the so-called world     
2:11:30     
models used in recent modelbased reinforcement learning frameworks. So um we didn't in our paper and in fact     
2:11:39     
in that whole special issue they didn't talk anything about sort of internal     
2:11:45     
models or forward and reverse models that they use in robotics. I don't agree     
2:11:50     
that's necessarily the same as what people are talking about now as world models. So we have the Han Schmidt Huber     
2:11:57     
work and the Hafner work which is of course where people are talking about world models. This is kind of an earlier     
2:12:03     
iteration of this work. Basically, it's the idea that, you know, if you have a robot that's doing some sort of sensory     
2:12:10     
motor operation that it's not just a a tightly connected     
2:12:16     
or a tightly integrated clos loop feedback. It's actually where you have     
2:12:22     
resources like symbolic resources that you can draw from to generate behavior.     
2:12:29     
So this is u you know a little bit more advanced or a little bit higher level     
2:12:35     
than the closed loop feedback but I wouldn't say that it's kind of the same thing as world models. It's very similar     
2:12:42     
but not really. Um and so but early work on robotic navigation problems     
2:12:49     
demonstrated that the topological structure of the task space can be embedded as multiple attractors in an     
2:12:56     
RNN by learning sensory motor experiences. So that's a you know that's sort of the idea that you have this     
2:13:03     
dynamical system where you have clos feedback as a very immediate thing and     
2:13:08     
then you have this dynamical system that unfolds that the agent has access to     
2:13:14     
through these attractor basins. So it can interpret the sort of the outcomes     
2:13:19     
of these dynamical systems interactions as these attractors.     
2:13:25     
And so then they just talk about how continuous sensory motor experiences with minimal constraints     
2:13:32     
um can lead to higher order behaviors. Um, Tiny proposed hierarchical RNN     
2:13:40     
models such as RNNs of parametric bias and multiple time scale RNNs to     
2:13:46     
introduce a temporal hierarchy whereby the lower level exhibits a temp high     
2:13:52     
temporal resolution which may correspond to the system one and a high the higher     
2:13:57     
levels exhibit a lower temporal resolution which may correspond to a system two. So this all has this can all     
2:14:05     
be fit into a model of neural dynamics where different levels of different neural dynamics and then we can map     
2:14:12     
those two together. Uh the mutual interaction between the     
2:14:17     
top down predictive and bottomup recognition processes can be understood as the RNN implementation of predictive     
2:14:24     
coding. And here they site Rao and Ballard from 1999. So they they have     
2:14:30     
this uh predictive coding aspect to this. So I guess you're kind of matching     
2:14:36     
the two different time skills through predictive coding. Um and so people have     
2:14:43     
tried this with different things such as object manipulation, imitation, language     
2:14:48     
acquisition, and social interaction. And so there's there's this RNN PB which     
2:14:55     
is of course um this approach by Tani which is the RNN with parametric bias     
2:15:02     
and then there's this MTRNN which is uh the multiple time scale RNN     
2:15:09     
and there differences here between these two types of models. RNN PB     
2:15:14     
uh focuses on different frequencies of neural dynamics and its updates to the     
2:15:20     
system whereas the MTRNN incorporates multiple time scales by assigning     
2:15:25     
different time constraints to each network level. At a higher level, larger time constants     
2:15:31     
produce slower neural dynamics, whereas at a lower level, small time constants lead to faster dynamics.     
2:15:38     
And so this is just kind of thinking about these different levels and how they contribute to sort of an integrated     
2:15:44     
neural system that operates at different time scales that allow you to build these primitives. Say in sensory motor     
2:15:51     
control that would be like a bring obction,     
2:15:57     
a grasp function, a reach function and a release function. And then at the higher     
2:16:03     
level, you're combining those into sequences of movements. And so that's how this works. You start with the sort     
2:16:10     
of tightly controlled possive feedback. You build primitives from those and then you combine those together.     
2:16:18     
And they're all happening at different time scales. Okay. So that's enough on that paper. I     
2:16:24     
think uh that that's a nice paper where they're introducing a lot of uh uh     
2:16:30     
concepts and bringing them together and comparing this with world models. Although I think um it' be interesting.     
2:16:37     
They should have written a paper for the special issue because I think they're like kind of unpacking this in the context of the world models of Han     
2:16:45     
Schmidt Huber and Hafner would be quite interesting.     
2:16:50     
But yeah, this is you know again thinking about multi-cale cognition thinking about these time     
2:16:55     
scales of continuous learning.     
2:17:02     
All right. Did we have any comments or questions on that? No comments, but I appreciate going     
2:17:08     
through the paper. I was reminded of I think that was one of the final     
2:17:15     
group discussions like Bergson and time and physical memory and where is memory     
2:17:22     
located and how is it stored? like those are things um ye old reading groups of     
2:17:30     
past that um it's good to see here again today. I'll mention this to Amanda. I     
2:17:35     
don't I don't think Amanda's going to be able to come to these meetings, but yeah, what I might try to do is sort of     
2:17:42     
because we're doing one with YouTube and things are so much easier to clip now. I might try to just     
2:17:48     
uh I don't know, find a way so that if someone wants to follow some of the     
2:17:53     
conversation, they can they can do that. But you're doing a good job with clipping things yourself and whatnot.     
2:17:59     
But I feel like I'm I'm ever torn between um     
2:18:07     
trying to organize things and and realizing that that's, you know,     
2:18:14     
impossible. So, uh, we'll see. We'll see where it lands. But no, thank you for     
2:18:19     
going through that. And I I don't know if I mean maybe Wednesday we can     
2:18:26     
briefly mention that as well because I think that's there's enough there. We'll see. Yeah.     
2:18:31     
But that's all. Good. Thank you. All right. So, I think that's it for     
2:18:37     
today. Um, have a good week. Um, and see you next     
2:18:42     
week. Take care. Take care. Bye.
