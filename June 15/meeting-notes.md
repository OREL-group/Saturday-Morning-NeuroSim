## Meeting Recording

[YouTube link](https://youtu.be/hplkTym-vmI)

## TRANSCRIPT
     
Transcript     
0:00     
hello uh today I'm going to go over a number of items in a reading queue hope     
0:06     
you'll find these interesting as we're not going to have our normal Saturday meeting this week     
0:12     
and hopefully we return next week with a full meeting so the first thing I'd like to     
0:17     
talk about is in the world of complex networks and this paper in particular a     
0:24     
generative model for Community types and directed Networks     
0:30     
so this is where they're working with these hairball networks and they're trying to extract Community     
0:36     
types this is a picture of a hairball Network as you can see you have some     
0:42     
structure but a lot of it is just really kind of hard to understand and so one of     
0:48     
the things we try to do in complex networks when we build a very large topology and this is a topology of the     
0:54     
internet is to break apart the topology into different community ities or groups     
1:01     
of nodes that share commonalities that are either highly connected within themselves or some other Criterion that     
1:09     
we can Define as a community and so as you can imagine this is a intense     
1:14     
computational tasks def find these communities to find ones that are self-contained and robust uh as you can     
1:21     
imagine you can find many different overlapping communities but that's not necessarily     
1:26     
helpful and so in this paper one of the things they talk about is how connectivity in the growth of a network     
1:33     
results in different being able to Define different communities so let's go to the     
1:41     
abstract so the abstract reads a large complex networks we're often organized     
1:46     
into groups or communities and so you saw that big topology of the internet     
1:52     
and their subgroups within that that are groups or communities we can use     
1:57     
Community finding algorithms to find those groups and they usually have some     
2:02     
significance within the network it's the sort of the units of the greatest     
2:08     
interaction locally in this paper we introduce and investigate a generative model of     
2:16     
network Evolution so they're using a generative model they're basically creating a network they're generating it     
2:23     
from the sort of the principles that they want to generate it from and     
2:28     
crucially they're adding nodes to an existing structure and generating this     
2:34     
sort of large topology this hairbone so we look at Network     
2:39     
Evolution and this this type of technique for generating these hairball     
2:44     
networks reproduces all four pawise Community types that exist in directed     
2:50     
networks and so they go on to Define these pairwise Community types which are     
2:55     
essentially equivalent to structures that you see at the global scale or uh     
3:03     
connectivity rules that govern the addition of nodes so our four types are     
3:10     
assortative core periphery disassortative and what they call Source     
3:16     
Basin type and this is a newly introduced type so the value of this paper is in introducing this Source     
3:22     
Basin type we fix the number of nodes and the community membership of each     
3:27     
node allowing node con AC it to change through rewiring mechanisms that depend     
3:33     
on the community membership of the involved nodes so what this means is that you have sort of a limited size and     
3:42     
you have this membership Criterion so when we add a node or we rewire a node     
3:48     
we change the edge in terms of where that node is connecting we have this     
3:54     
sort of uh Criterion that is met so for example if I'm a showing up into a     
4:00     
network I wear to some other node based on some Criterion it's not just blindly     
4:07     
connecting and this is where we get a lot of these assortative and disassortative types of community uh     
4:13     
pawise Community types so this is uh basically you know there's this idea     
4:20     
that you can in reinforce Community membership by in community membership as a Criterion and they do this to sort of     
4:27     
bootstrap this process and ident identify these types of uh     
4:33     
communities we determine the dependence of the community relationship on the model parameters using a meanfield     
4:40     
solution so they use this mean field model to uh to determine this dependence     
4:47     
it reveals at a difference in the swap probabilities of the two communities and     
4:52     
this is just where you know there's a probability of a node changing communities during rewiring     
4:59     
is a necessary condition to obtain a core periphery relationship which is of     
5:04     
course this relationship where you have core of Highly connected nodes and a periphery of less connected nodes and so     
5:12     
you see this core periphery relationship uh in different uh     
5:17     
topologies uh where you have differences in connectivity it's usually maybe the     
5:23     
more popular nodes or the hubs that are core nodes and then peripheral nod     
5:30     
that play a lesser role in the network and that a difference in the average IND degree in communities is a     
5:38     
necessary condition for a source based in relationship so they'll talk about the source Bas in relationship more     
5:44     
specifically here uh more generally our analysis reveals multiple possible     
5:49     
scenarios with a transition between the different structure types and sheds light on the mechanisms underlying the     
5:56     
observation of the different types of communities and networked in so this kind of goes through uh the par     
6:04     
wise community structure this is the math here uh so the type of pawise community structure for two communities     
6:11     
R and S which are two communities uh is determined by the density WS on the edges between nodes     
6:19     
and these communities defined in this way so you have your uh WR wrs and then     
6:25     
that equals these this in within this stack these conditions if R does not     
6:30     
equal s then you have this rule if R equals s then you have this     
6:36     
Rule and so this you know they kind of go through this uh but they also want to     
6:42     
know something about some of these other methods so they want to know something about assorted of networks corpor free     
6:49     
networks and disassortative networks and so this shows the relationship between     
6:55     
ws and wsr which is like the cross connectivity so if you go in One Direction between R and     
7:01     
S versus in the other direction and so you you know they have these Criterion     
7:07     
uh for these four conditions and so again assortive connectivity is where you have this like     
7:17     
assorting with like core periphery is where nodes that are rewiring are ATT     
7:23     
attracted to core nodes this assertive is where nodes will     
7:28     
go outside of the their existing community and then Source Basin is this idea that there's a sort of gravity in     
7:37     
in connectivity so it'll grow to the community of closest gravity so it's     
7:42     
kind of a combination of core periphery and assorted     
7:48     
it and so this is an example here in figure one of sort of this type of     
7:54     
connectivity so again we have these bir directional connections where we have have zero and one and we can go from     
8:01     
zero to one or one to zero and then we have these so you know you have an     
8:07     
outbound and an inbound connectivity and so that's that's what these PA wise relationship looks like     
8:14     
but then you have you know assortative or periphery disassortative and Source Basin so assortive is where you have two     
8:22     
communities and you have connections between the communities that are sort of U you know select highly itive uh core     
8:31     
periphery is where you have a core of nodes and a periphery of nodes and so     
8:36     
they have this uh High highly uh evolv of     
8:43     
Highly this is high degree of organization amongst them dis assortive of course is where     
8:50     
you have two communities but they're not really interconnected very well so     
8:55     
they're classified as two groups but they're connected with you know uh     
9:00     
between each other more than within each other and then Source Basin is where you have the source and then you have a     
9:06     
basin here so you have these uh this this group that's highly connected and this other group that's connected to     
9:13     
that other group but they're in this separate group they're not really that well connected so it's almost like a     
9:19     
sort of disassortative connectivity but also kind of like assorted of connectivity in that you have one group     
9:27     
that's highly integrated so they provide this phase space and so     
9:32     
this is where we have uh like so in this case we have core periphery so we have     
9:39     
the peripheral nodes in red the core nodes in blue you see that there's this core of Highly connected nodes in this     
9:46     
periphery of lesser connected nodes you have a source Basin of course the source     
9:51     
being these red uh nodes here that serves roughly the roll of prery and     
9:57     
these Basin nodes that are roughly the uh Ro of the core uh you then have dis     
10:03     
assortive where the red nodes and the blue nodes are not really any sort of there's no organization between them     
10:10     
they just interconnect with one another uh core periphery of course is here     
10:16     
again and then assortative where you have this like assorting with like and     
10:23     
so with this phase bace we have um these two uh this B variant space where you     
10:31     
have core periphery at high values of pa1 uh you have cor periphery High     
10:40     
values of pa0 the disassortative connectivity for low values of pa0 and pa1 assortative     
10:48     
for high values of pa0 and pa1 and then Source Bas and kind of taking up the rest of the phase     
10:54     
space which is of course probably one reason why they wanted to discover this     
10:59     
new type of connectivity because there was this blank part of the face space so     
11:05     
that's the way they kind of think about this uh problem and I think it's an interesting approach to this sort of you     
11:14     
know rewiring problem or this connectivity problem where you have new nodes that are coming into a network and     
11:20     
then you decide where they're going to insert themselves or sometimes you have rewiring processes say in the brain or     
11:28     
in Social Network where you have to change your connectivity and you change     
11:33     
your connectivity sometimes based on the current activity of the network so as     
11:39     
the network is active and there are these active exchanges of information     
11:44     
between nodes they rewire in a way that's more amendable or more efficient     
11:50     
and so capturing this process of how this happens uh is important to understanding     
11:56     
these communities so now I want to get into a little a little bit into uh AI stuff and     
12:01     
we have some readings on okay so now I wanted to get a little     
12:07     
bit into artificial intelligence and I have two readings on that um one is in     
12:12     
this developmental AI area we've been working on and the other one is uh something from newa that's really     
12:19     
interesting so the first thing is from the Los Angeles Review of Books and this is a conversation between Alis and gnik     
12:27     
and Melanie Mitchell Alis and gnik is a developmental psychologist Melanie Mitchell is an AI person and they're     
12:34     
talking about how to raise your artificial intelligence so you know there's this developmental AI theme that     
12:41     
we're working on in the lab so you know one of the things that they're interested in a lot of people are     
12:46     
interested in developmental AI um and so you know we have models like large     
12:54     
language models they basically extract patterns and data     
12:59     
and then the question is whether they really understand it enough to give a reasonable output or whether they're     
13:05     
reliable enough to rely on for any sort of casual     
13:11     
use so uh Alis and gnik and no and Mitchell were skeptical of the     
13:17     
assumption that we will be able to feed large language models enough text and     
13:24     
become intelligent agents and so you know if you're taking a developmental perspective you know that just training     
13:29     
a model on data without any sort of structure or you know any sort of aspect     
13:36     
of development is probably not going to work and so that's what they're discussing     
13:43     
here so you know uh Allison gnik of course is interested in development but     
13:49     
Melanie Mitchell is also interested in a lot of things having to do with conceptual abstraction and analogy     
13:55     
making so more of the symbolic approach so this is another issue with large language models is there isn't the     
14:02     
symbolic layer to large language models so you know it's an another interesting     
14:08     
take on this is that they're kind of bringing these two perspectives together uh yes what today's llms can     
14:16     
achieve by consuming H swaps of text as impressive and has challenged some of our institutions about intell and has     
14:23     
challenged some of our intuitions about intelligence before we can attribute them to something like human     
14:28     
intelligence AI systems will need the ability to actively interact and engage with the     
14:33     
world creating their own mental models about how it works so this is going in the direction of creating these mental     
14:40     
models um so one of the questions here is let's start with the tension at the     
14:46     
heart of AI we understand to talk about AI systems as if they are both mere tools and intelligent actors that might     
14:53     
one day come alive Allison has argued that the current popular AI systems are     
14:58     
Jo anguage models are neither intelligent nor dumb that those are the wrong categories by which to understand     
15:04     
them rather we should think about them as cultural Technologies like the printing press or the internet why is a     
15:11     
cultural technology a better framework for understanding L language models and I think in the slack we've discussed the     
15:18     
idea of a cultural technology and so um this is you know     
15:23     
this type of thing like the printing press or the internet where you create this technological tool and people use     
15:29     
the tool and the imprint of the creators are sort of the thing that we get out of     
15:36     
the technology it's not the technology imposing itself upon the rest of us and     
15:42     
so I think that's a very important thing that we you know the Technologies themselves are rather passive and as     
15:48     
humans we use those and we're able to um you know derive great uh works of you     
15:55     
know creativity of or something else so Allison's response to this is a very     
16:01     
common Trope is to treat large language models as if they were intelligent agents going out in the world and doing     
16:08     
things that's just a category error a much better way of thinking about them is a technology that allows humans to     
16:14     
access information for many other humans and use that information to make decisions we have been doing this for as     
16:21     
long as we've been human language itself could think as be thought of as a means     
16:26     
to allow this so we are writing uh so we s writing in the     
16:33     
internet uh these are all ways we get information to other people similarly llms get us a very effective way of     
16:40     
accessing information from other humans rather than go out explore the world and draw conclusions as humans do llm     
16:48     
statistically summarize the information humans put on the web and so Melanie Mitchell of course then also mentions     
16:55     
that you know we use a lot of metaphors to talk about l language models uh things like autocomplete on     
17:02     
steroids and stochastic parrots or a blurry jpeg of the web or cultural     
17:09     
technology so these are all metaphors that sort of speak to the sort of limitations of large language models or     
17:15     
the sort of the need to make them passive instead of active um others use metaphors that have     
17:23     
more to do with agency and understanding I'm not sure we've come up with the right metaphor because in some s larger     
17:30     
language models are all these things maybe we have to say to what extent uh they are each of these things there's     
17:36     
such a big debate in the community about this and it's interesting that such smart people can so violently disagree     
17:42     
at how to think about these systems so you know because this is challenging our Notions of what     
17:48     
intelligence means it becomes very contentious uh back in the 1970s a lot     
17:54     
of people were saying if a computer could play Chess at a Grandmaster level that would require general humanlike     
18:01     
intelligence clearly it did not we thought the same thing about translation which is of course translating to     
18:07     
different languages and of course people try to do that now but this is not something that we've achieved since the     
18:14     
1970s now we're faced with systems that are conversationalists and are able to act like agents that understand     
18:21     
conversation is that require humanlike intelligence it doesn't seem so since we have these uh machines that can't seem     
18:29     
to do things that we say would be benchmarks of human intelligence but can     
18:35     
do other things that are quite complex so maybe those things don't sort of     
18:40     
aren't at that level of humanik intelligence and so to step back for a moment you know it's a very interesting     
18:47     
question and we've talked about this in meetings in the past where we tried to Define intelligence and talked about the     
18:53     
definitions of intelligence and it's very hard to have a get a good Gra grasp     
18:59     
on what intelligence actually is and so you know it's worth thinking about     
19:04     
how we sort of assign the term intelligence the things or you know we     
19:10     
assign humanlike intelligence to things that may not be humanik intelligence so Allison uh adds there is     
19:17     
an implicit intuitive model that everyday people including very smart people in the tech world have about how     
19:23     
intelligence works there's this mysterious substance called intelligence and as you have more of it you gain     
19:30     
power and authority so you know this idea that intelligence is this thing that you have it's something     
19:37     
that's almost like a substance or a fluid and then the more you have of it the better or the more Authority you     
19:44     
have or the more power but that's just not the picture coming out of cognitive science at all rather there's this very     
19:51     
wide array of different kinds of cognitive capacities many of which trade off against each other so being really     
19:58     
good at one thing actually makes you worse at something else uh to Echo melan one of the really     
20:04     
interesting things we're learning about large language models is that things like grammar which we might have thought     
20:09     
required an independent model building kind of intelligence you can get from extracting statistical patterns and data     
20:17     
large language models provide a test case for asking what can you learn just from transmission just from extracting     
20:23     
information from the people around you and so sometimes you know intelligence     
20:29     
um isn't intelligence the way we think of it it's this extracting uh information from data so     
20:37     
this next question is what do you think are the limits to what larger language models can a achieve just by being     
20:43     
trained in language alone and so you know they talk about this     
20:49     
question Allison says if you look at for instance videos of the very best robots     
20:54     
people are inventing you'll notice that there there's a little number in the corner that says 10x or 20x or something     
21:01     
like that what that means is that the video has been sped up 20 times to make it look like the robot is doing     
21:07     
something intelligent if you were actually watching the robot in Real Life it would just look like it was     
21:12     
incredibly painfully slow and awkward and making mistakes all the time this is     
21:17     
representative of what's called Mor ofx Paradox things that looked as if they were they would be really really hard     
21:24     
for AI they require a lot of intelligence like playing chess turned out to be relatively easy and things     
21:30     
that look like any 2-year-old can do them like picking up an object and putting it in a pot stirring it are     
21:36     
actually really hard larger language models have made that Paradox more Vivid     
21:41     
so this is you know something that again we have this model of intelligence that     
21:47     
may not be the best model to operate off of when we're thinking     
21:52     
about artificial intelligence but also we have this aspect of you know that     
21:59     
acquiring intelligence is actually not you know a a linear straightforward path     
22:06     
that you have to make a lot of mistakes and that you know people think well if you make a lot of mistakes you're not     
22:11     
very smart well that's not necessarily the case it's more about exploration we've talked about uh a lot of the stuff     
22:18     
that people are doing with GoPro cameras and capturing images of the environment     
22:25     
and training agents on those data so this is all very much of the same uh you     
22:32     
know topic or the same problem is how do we sort of think about intelligence how do we incorporate that into a machine     
22:40     
and it seems as if we're really don't really have that first part down how do     
22:46     
we get intelligence in the one machine or how do we get information in the war machine so that it actually Express as     
22:54     
intelligence um but going back to the contrast between different kinds of intelligences one type of intelligence     
23:01     
is about what I call transmission or how do I pass information to and extract     
23:07     
information from another person a different kind of intelligence is about truth I am in the world and the     
23:14     
world is changing and this is what they call a non-stationary environment so how     
23:20     
do I find the truth about something that we haven't seen before science is the most dramatic example of engaging in     
23:27     
this activity but even very young children are good of this and large     
23:32     
language models are of course not trained to do this and so we talk about how they hallucinate but hallucination     
23:38     
isn't really the right word to hallucinate you mean that you would recognize the difference between truth     
23:44     
and just a bunch of things that people have said large language models are not designed to make that distinction yeah I     
23:50     
think Hallucination is a poor term for what large language models actually do which is spit out terms sometimes that     
23:58     
are not have nothing to do with the prompt or nothing to do with the topic that they're talking about so you know     
24:05     
Hallucination is a is if you think about like how humans hallucinate hallucinations aren't just     
24:12     
you know random stuff it's you know sometimes you have very specific     
24:17     
hallucinations about say things that you know so you might have a hallucination about like big giant grapes in the     
24:24     
desert and how you're bouncing from grape to Grape along the landscape and that's that's a hallucination that is     
24:32     
based on a lot of you know it's putting things together in the sort of way that's sort of believable but it's not     
24:39     
something that you would think is a real experience that makes sense and this non-stationarity aspect     
24:46     
is interesting because this is something we're exploring in our paper uh on ever the ever regulator     
24:54     
theorem and Ai and so that's that's something that's coming out from the lab soon but this is again has to do with     
25:02     
this idea of non-stationarity of the data that's coming into the system so     
25:07     
when the data is uh normally distributed when it's in distribution when it's     
25:12     
stationary that's a totally different situation than when the world and the data associated with it is non-normal     
25:21     
out of distribution and non-stationary and so this is a problem that is really interesting I think     
25:27     
because it really affects the way that the AI acquires     
25:33     
information and ultimately how it operates on that information we might also have uh     
25:39     
another opportunity to do a paper in terms of thinking about non-stationarity and developmental Ai     
25:46     
and we haven't that paper isn't uh as far along yet that paper idea but that's     
25:52     
something that's maybe an opportunity for people to engage with so you know this this interview     
25:59     
goes on uh there's a question about how large language models rely on statistical associations rather than     
26:06     
Concepts and of course this is the aspect of you know symbolic AI versus     
26:12     
non-symbolic AI or neuros symbolic AI which combines the two and so of course     
26:18     
melan eventually answers this question in the following way a concept     
26:24     
is a mental model of some aspect of the world that has some grounding in truth     
26:30     
you might have a concept of something like a unicorn while it is not true in the real physical world it is actually     
26:36     
true in some different kind of fictional world I know it's fictional but I still have a concept of it and I can answer     
26:43     
questions about it I think these mental models of the way the world Works which involves things that cause other things     
26:49     
are Concepts and this is something I don't think that large language models have or maybe even can develop on the     
26:55     
scale that humans do and so again you know Allison dnik says makes the point     
27:04     
that you know uh mental models are different from statistical     
27:10     
patterns when you have a mental model you also have an idea that you can go out and test whether the model is right     
27:16     
or not I can actively go out into the world do an experiment and get the right kind of new data decide whether I'm     
27:23     
right or wrong so when you have a set of Concepts you can take that you can     
27:28     
evaluate it and you can go search for data that support that idea and maybe that's a bad thing in some cases but it     
27:36     
it's a different way of acquiring information than what you would have if you just kind of acquired information at     
27:43     
random and Incorporated it into what is essentially a very generic model not     
27:50     
necessarily a mental model with affordances and with specific Concepts     
27:58     
and so you know this kind of goes on uh for quite a while so I don't want to get through the entire interview but this is     
28:04     
something we can follow up on uh where you know they they talk about a number of really interesting     
28:11     
um uh questions and but it's all in the same day so this is a really interesting     
28:17     
interview um now I want to move on to what newa is doing and this is their thousand brains project so of course we     
28:25     
know about Jeff Hawkins and nenta and some of the efforts they've made to     
28:31     
understand neocortical columns and so you know their their whole basis of AI     
28:36     
is on these neocortical columns which are these multiple layers of brain tissue that are connected in a hierarchy     
28:45     
and it allows you to put those in parallel and do computations in a way fundamentally different than say like a     
28:52     
deep Learning Network where you have these generic units that are interconnected with hidden layers and     
28:58     
all of that so this is uh you know this Jeff Hawkins actually wrote this book a     
29:04     
thousand he wrote this book thousand brains theory of intelligence and so     
29:09     
thousand brains refer to these columns putting these columns in parallel and you actually being able to compute     
29:16     
with and so Numa has actually been working in building a community around their software their software is based     
29:22     
on this this principle and they've been trying to you know how do you how do you     
29:28     
take these insights about neocortex and apply them to artificial intelligence so     
29:34     
you know we're not they're not promising this sort of neuros symbolic Revolution     
29:39     
they're promising this different type of processing and the idea is that you know the brain to to be like successful at     
29:47     
artificial intelligence you need to model things more on the brain and     
29:52     
specifically the human neocortex or the Maman neocortex and you know you might     
29:58     
agree or disagree with that but that's what the way they're pursuing this and so uh to build the kind of efficient and     
30:05     
robust intelligence that we know humans are capable of we need to design a new type of artificial     
30:11     
intelligence um and so now they they're building this community uh they're releasing the short     
30:18     
technical document describing the core principles of the platforms they have very good documentation of their     
30:24     
approach this is something that their Community really has down they they've been working on these technical     
30:31     
documents for years and they're putting out sort of the core principles of the platform they have some uh code on     
30:38     
GitHub so this is something that can be pursued uh pretty easily um and so you know this kind of     
30:46     
gives you some information about how you can use uh new mena you can do things     
30:52     
like sensory motor learning work with reference frames so you can actually put in     
30:58     
uh spatial reference frames or conceptual reference frames I guess in this case they're showing an     
31:04     
observer you know in looking at some object and having these spatial points of reference of course you have sensory     
31:12     
motor integration here sensor motor feedback from objects you have then you     
31:18     
have modularity which is of course where you have these modules you know maybe if you have a     
31:24     
robot where you have these columns you can have some column colums devoted to sensory input some columns devoted to     
31:31     
learning inputs and learning processing and other things like so you can have     
31:36     
you know different components of your massively parallel system and so like in     
31:43     
human you cortex you have some areas devoted to visual inputs you have some     
31:49     
areas devoted to visual processing some devoted to sensory motor processing some     
31:54     
devoted to higher level Concepts in in the like and so this is sort of the     
32:01     
other principle of the Thousand brains which is that you can have these modules     
32:06     
but everything is in parallel and so this is a really powerful uh potentially     
32:12     
powerful way of doing this uh so they have an SDK that you can um use this     
32:18     
allows you to develop more easily especially some of these alternative architectures so once you get into the     
32:25     
uh world of Nea and you learn the the way it's supposed to work and you learn the vocabulary and the tools that they     
32:32     
have then you can play around with these kind of approaches where you have     
32:38     
multimodal modules uh a wider set of modules you have deep and wide uh     
32:44     
networks where you can have things that are sort of hierarchical and things that     
32:49     
are distributed so there are a lot of sort of architectural variants that you can play with and depending on the     
32:56     
problem you know some of these might might be quite useful some of the less useful and so this is uh their you know     
33:03     
kind of update on their system and their community so if you're interested in participating you know we we have some     
33:09     
interest in this in the lab some interest in BIO inspired stuff so you know please let me know if you're     
33:16     
thinking about something like this all right our next topic is on emergence and there have been a couple     
33:22     
good articles on emergence that have come out recently and I wanted to go over those and talk about their     
33:30     
significance so this is an article from Quantum magazine and this is on the new     
33:35     
math of how large scale order emerges so this is based on the idea     
33:41     
that you know we we know about emergence and we've known about emergence for a long time and the puzzle of emergence asks     
33:48     
how regularities emerge on macro scales out of uncountable constituent parts so     
33:55     
when you have a flow like this and this is a flow on the surface of Jupiter this is Jupiter's Great spot and the idea is     
34:03     
that you have all these components uh that come together to form these     
34:09     
patterns and so the the thing is is that the constituent Parts don't have a plan     
34:14     
for this structure they don't have the ability to sort of collectively     
34:21     
coordinate themselves to build these patterns so how do you get to this and     
34:26     
the answer of course is is emergence so things emerge out of just interactions     
34:32     
there's no plan but those interactions determine the sort of the scope and     
34:37     
scale of this pattern and so this is something of course that's diverges from     
34:43     
what we think of as artificial intelligence because you just need agents at the local level making     
34:49     
interactions sometimes the interactions are regular sometimes they're stochastic but they can produce these larger scale     
34:57     
patterns and it doesn't require sort of an intelligence it just requires interactions locally so there's some     
35:03     
maybe intelligence and the Agents if you were building an AI system but sometimes     
35:09     
they can be you know uh chemicals they can be uh you     
35:14     
know particles in a flow whatever and so those don't really have intelligence and     
35:20     
so emergence is conveniently it gives us the ability to sort of understand those     
35:26     
those sorts of things but there hasn't really been a very rigorous mathematical description of     
35:32     
emergence and one of the reasons why of course is because it's hard to describe a process that's essentially     
35:38     
stochastic so you have these things locally that are happening and they result in these patterns how do you     
35:44     
describe that in mathematical terms how do you use a symbolic system to describe     
35:50     
and that's really the problem that they're getting so this article is by Philip     
35:56     
ball um this talks about this this image is of course Jupiter's Great Red Spot     
36:03     
and this is a a pattern that's been sort of emerging over hundreds of years so     
36:08     
you can have uh emergent patterns at different scales at different time scales and different spatial     
36:15     
skills and so you know we see emergent phenomena everywhere in the world but     
36:21     
it's hard to know kind of you know if all these different types of patterns have the same set of principles behind     
36:27     
them or if they have different principles and so you know it's hard to know like we can kind of explain why     
36:33     
emergence happens but we don't have a really strongly predictive model of how     
36:39     
emergence happens and so uh Jim Crutchfield who's at Santa Fe says     
36:45     
confusion is red it's just a model we don't necessarily know you know if     
36:50     
something is truly emergent whether any one pattern follows the same rules as     
36:55     
any other pattern and so so forth NE Neil Seth who of course is a     
37:01     
neuroscientist says philosophers have long argued about emergence and going around in circles problem according to     
37:08     
Seth is that we haven't had the right tools not only the tools for analysis but the tools for thinking having     
37:14     
measures and theories of emergence would not only be something we can throw at data but would also be tools that can     
37:20     
help us think about systems in a richer way and so you know people have been     
37:27     
working on this problem and in recent years people have kind of come up with some novel ideas about this so Fernando     
37:34     
Rosas who's a complex system scientist at Sussex along with Anil Seth they     
37:40     
worked on this framework for understanding how emergence Rises and so this framework is in this     
37:46     
archive paper and this is called software in the natural world a computational approach to hierarchical     
37:54     
Origins and so this is of course paper here some other famous authors on it and     
38:01     
the abstract reads understanding the functional architecture of complex systems is crucial to illuminate their     
38:08     
inner workings and effectively or enable effective methods for their prediction     
38:13     
and control recent advances have introduced tools to characterize emergent macroscopic levels however     
38:21     
while these approaches are successful in identifying when emergence takes place so we can identify an     
38:28     
pattern when it's happened and you know this is a large way maybe from static     
38:33     
information or sometimes we can see something emerge if it's a chemical form of emergence if you see a pattern in a     
38:41     
coffee cup or in a chemical reaction or on the surface of a planet you know or     
38:47     
in a p puddle of water you can watch it kind of take shape or you know you can     
38:53     
watch an ant colony form um you know     
38:58     
it's it patterns of its behavior and you can see this but you know it's really     
39:04     
hard to know how it does this and so one of the problems of course is that it does it in different ways every time it     
39:10     
does it so you know there's this idea of initial conditions so if the initial     
39:16     
condition is different these structures are built in different ways and they can follow different types of interactions     
39:22     
you can't reverse engineer an emerging structure and get an exact solution to     
39:29     
it you just have like a number of ways that it can emerge and that's as much as     
39:35     
we know so people are limited in the extent that they can determine how an emergent pattern happens or comes to     
39:43     
be here we address this limitation by developing a computational approach to emergin which characterizes macroscopic     
39:51     
processes in terms of their computational capabilities concretely we've     
39:57     
articulative view of emergence based on how software Works which is rooted on a mathematical formalism that articulates     
40:04     
how macroscopic processes and express self-contained informational     
40:09     
Interventional and computational properties uh this framework establishes     
40:15     
a hierarchy of nested self-contained processes that determines what computations take place at what level     
40:23     
and which in turn delineates the functional architecture of a complex system this approach is Illustrated on     
40:29     
paradigmatic models from the statistical physics and the computational Neuroscience literature which are shown     
40:36     
to exhibit macroscopic proper processes that are akin to software in human     
40:41     
engineered systems so they're making this analogy between software and the structure of software and things that     
40:48     
are happening in statistical physics in computational Neuroscience overall this framework     
40:54     
enables a deeper understanding of the multi-level structure of complex systems revealing specific ways in which they     
41:01     
can be efficiently simulated predicted and controlled and so why don't we look at     
41:07     
the paper to see if there are any good figures because that's often a good way     
41:12     
to sort of summarize what's going on so the first figure is illustration     
41:19     
of causal States this is interesting from you know     
41:25     
the perspective of having this metaphor of a uh software architecture and having it you know     
41:31     
being generative and being able to produce these emerging States this paragraph here is     
41:38     
interesting arguments can be made based on evolutionary and thermodynamic considerations or why and to what degree     
41:46     
biological systems May display software like macroscopic levels that are causally     
41:52     
closed so this is interesting because we've been reading some work in I think it was this cybernetic spring group on     
42:00     
how emergence is really or biological emergence is really not something that's     
42:05     
programmatic it's not something that'll be captured using an algorithm and in this paper they soon making the opposite     
42:13     
case you can have uh causally closed systems that are you know you could see     
42:19     
them perhaps in biology that are basically program programmatic or I     
42:26     
guess you could say mic although we can play around with this idea and so you know the software alike     
42:33     
I think being the term of art that would be uh the point of contention so do     
42:39     
biological systems display the software like sort of uh organization and if so     
42:46     
then can we use that to make predictions about emergence because if we have biological emergence and it's structured     
42:53     
in the same way a program or a generative program might be structured a generative program can produce an     
42:59     
emerging output then maybe the biological system can as     
43:04     
well um living organisms perform actions for example interventions over their     
43:10     
environment and themselves in order to guarantee their survival however some interventions are     
43:16     
more feasible to implement than others so while it is almost impossible to intervene on the momentum of a     
43:22     
particular molecule in a glass of water so you know you have this thing that's     
43:28     
happening at the macroscopic scale it's hard to intervene upon that um which I     
43:33     
guess means you can't really um yeah you can't make an intervention     
43:40     
so there's this causal as consequence to it is much easier to increase its mean     
43:46     
temperature together with all the molecules in the glass so you can basically take a glass of water heat up     
43:54     
and ensure that all the molecules will heat and of course that has the emerging     
44:00     
phenomena of creating maybe a phase transition to a gas you know evaporation     
44:06     
water boiling water so you get right up to the phase transition but you know it's harder to     
44:12     
say it's easier to heat the glass with everything all the molecules being     
44:18     
heated than to intervene at the level of specific components of that emerging     
44:24     
system and modify them accordingly and of course sometimes we don't need to do that because you know heating a glass     
44:32     
of water is a meanfield thing in other words the molecules all sort of behave in the same way and they have a similar     
44:39     
response and so we don't really need to worry about making those interventions on the     
44:45     
individual uh scale at the at the microscopic scale we can observe a macroscopic effect by having this sort     
44:52     
of macroscopic intervention     
45:00     
caus closed systems are those for which macroscopic interventions are efficacious in controlling their     
45:06     
macroscopic scale so this is where this this is the causal e Clos system that we just talked     
45:13     
about with the glass of water hence one can say that systems are as if running software to the extent that they are     
45:19     
controllable at a particular scale at a reasonable thermodynamic cost so this is     
45:25     
an interesting statement so if you wherever you can control the     
45:30     
system if you can control the system say at the macroscopic scale then there's a you know it's easy     
45:38     
to predict what's going to happen macroscopic if you can intervene at the     
45:43     
microscopic scale to affect the macroscopic state and what they mean by     
45:48     
reasonable thermodynamic cost means that you know you're not trying     
45:54     
to um you you're doing something that was within sort of the bounds of the thermodynamics of the system or you're     
46:01     
doing something that is not like you know extremely costly and and this the     
46:07     
same kind of analogy we have with uh algorithms you know we don't run a Brute     
46:12     
Force search on things and wait around 150,000 years for an answer we have to     
46:18     
take sort of we have to create these her istics and so there are a lot of analogies between computer science and     
46:25     
natural systems that are really interesting here and so you know we're talking about like sort of issuing     
46:32     
commands and processing data and things like that but we're doing this in a way that interacts with physical systems and     
46:38     
biological systems building on similar arguments causal closure has often been regarded     
46:44     
by theoretical biologists as a necessary albeit not sufficient condition for the     
46:50     
subsistence of living systems so we've talked about causal closure before as well and this is of course you know     
46:58     
tying in with that literature so they draw heavily from computational     
47:04     
mechanics which is a framework for the study of stochastic dynamical processes from a computational     
47:11     
perspective and so it studies patterns and statistical regularities observed in Time series data and asks quantitative     
47:19     
questions such as how much historical information does the system store where is that information stored and how is it     
47:26     
process to generate future Behavior so this is something that you know if uh if     
47:32     
you're studying like a system where you have this cumulative output so in other     
47:38     
words you make interventions at the M microscopic level and an accumulation of     
47:45     
those have an effect at the macroscopic scale but this doesn't happen for a while then you know it's kind of hard to     
47:53     
understand that in terms of single interventions you have to take the sort of computational mechanics approach     
48:00     
understanding and I guess what they mean by computational mechanics is that you're looking at this this has it's     
48:05     
it's sort of like a uh statistical mechanics but you have this     
48:10     
computational cast over so you can create these types of     
48:16     
machines that they're talking about here uh Epsilon machines these are optimal complete     
48:23     
minimal representations of a computational engine that can generate the patterns observed in     
48:30     
data so you have these representational structures of the statistical mechanics     
48:36     
of this natural system such representations can be built     
48:41     
by grouping past trajectories according to the forecasted Futures into so-called causal States or precisely the causal     
48:48     
states of a Time series are the equivalence classes of past trajectories that are established by the equ     
48:55     
following equivalence relationship ship shown here and so this is where you the causal     
49:02     
states are given by a mapping Epsilon which course screens past trajectories     
49:07     
xit T thereby generating a new time series of clausal States this set e uh     
49:13     
formally the Epsilon machine of X is defined as a pair where Epsilon is the above mapping to clausal States and this     
49:20     
T term is a collection of transition probabilities in this form here     
49:27     
so this gets into their Epsilon machines where you know they kind of show     
49:33     
mechanisms and observations versus inputs and states in     
49:38     
this way so um     
49:45     
so the first one is this causal pH and this is a view of Epsilon machines as     
49:50     
the effective mechanism driving the system acting behind the scenes to generate observable data and that's an     
49:57     
A1 here where you have sort of this almost looks like a reservoir computer producing some patterned     
50:04     
output technically this corresponds to interpreting it as a hidden markof process where dynamics that take place     
50:10     
in variables e subt and a weight and state space while generating the observable data X of T then you have     
50:18     
this computational pH which is B this is an alternative view of Epsilon machine's discrete autometer so in this uh     
50:27     
in the state machine where the data corresponds to inputs given by a user driving the     
50:33     
system between different states technically this corresponds to seeing it as the discret autom with States e     
50:41     
subk which deter whose deterministic transitions are given by the input data     
50:47     
xot and so this is where you have these two different ways of doing this and     
50:53     
U causal States correspond to what kind of information bottleneck so you know     
50:59     
you have to engage in a number of activities like cor screening a past     
51:04     
trajectory so that you can have some sort of predictive power uh the causal States also have Markov Dynamics and by     
51:11     
Mark markiz the process this forces the effective states of the process to become     
51:18     
explicit so this looks like some of the stuff that we're arguing in terms of the ever good regulator theorem and how that     
51:24     
can be applied to this out of distribution data the sort of non-stationary data so a really     
51:31     
interesting approach it's a little tough to understand I think for someone who's     
51:36     
uh has a casual interest in analyzing an emergence system but I think it's I     
51:41     
think it's a real interesting approach okay now I'd like to move on to uh talking about     
51:48     
spreadsheets and using spreadsheets to do things like build a Transformer or a     
51:54     
large language model and so we talked about spreadsheets being used to build something like a urban simulation like     
52:01     
Sim City and so we talked about how spreadsheets can be used to sort of     
52:06     
manage those simulations and build the the sort of the nuts and bolts of the simulations and you know I had a     
52:12     
question about that that was basically like yeah it's obvious that you can use     
52:18     
spreadsheets and of course that's that wasn't kind of the point of what I was trying to get across there the point of     
52:23     
what I was trying to get across is that spreadsheets are represent a certain computational     
52:29     
tool and that it's it's you know it's sometimes viewed as sort of in a dismissive way that is a very simplistic     
52:36     
tool that doesn't really have a lot of use in sophisticated computation but we can actually use uh     
52:44     
spreadsheets as a as a way to sort of represent very difficult problems things     
52:49     
that might take a lot of computation but we can sort of get an intuitive understanding of it using a spreadsheet     
52:57     
and so that's where these uh readings come in so the first thing is this uh this term     
53:03     
spreadsheet is all you need which of course plays on the classic paper title attention is all you need and so     
53:10     
unfortunately attention isn't all you needed as we found out later but it's a good title um but this is uh dooen on     
53:19     
GitHub and this is the spreadsheet is all you need repository and this is a nanog GPT     
53:25     
pipeline act in a spreadsheet so this allows us to build a very small uh version of a large     
53:32     
language model and it's packed in the spreadsheet which is here Nano GPT EXL     
53:39     
XLS and so I'm not going to open it up because I don't have the program for it     
53:45     
uh available but we can actually you know open this up uh clone the     
53:51     
repository open it up and see what it looks like um but this is basically the read     
53:56     
me here this is where you can build this nanog GPT pipeline it's pretty fun to play with     
54:03     
especially when you're trying to figure out what exactly is going on inside of a transformer so there's this interpretability value to     
54:11     
it this helped me visualize the entire structure data flow all the mechanisms     
54:16     
calculations and matrices inside are fully active and configurable so basically what he's done is created     
54:23     
these tables in a spreadsheet and kind of walks through some of these Transformations that you need to make a     
54:30     
lot of Matrix algebra that you can do in a spreadsheet but it makes it kind of salient to people and understandable you     
54:37     
can view the data as a table or as a a matrix instead of just kind of like     
54:42     
thinking about the code and what it's going to look like you can actually have that in front of your face and you can     
54:49     
it makes it easier to understand I think and this is I think a missing piece of interpretability is this aspect of     
54:56     
seeing the data being processed or seeing what the data should look like in in front of your face not necessarily in     
55:03     
a plot but in the sort of raw you know Matrix of numbers and how it changes and     
55:10     
then you understand okay this is what's happening inside the Transformer this is     
55:15     
what's happening inside the model this is how we're getting our answer and so while reading about large     
55:22     
language models I realize that the internal mechanisms of a transformer are basically a range of matrices Matrix     
55:29     
calculations being connected in a certain order so basically you're taking these Matrix calculations you're putting     
55:34     
them in an order you can see that in the spreadsheet you know everything is sort of visualized for you and in a way that     
55:41     
isn't like just kind of like a diagram you can actually see the data change and you can actually Trace things back which     
55:48     
is crucial I think to understanding how the larger language model got its answer     
55:53     
arrived at its answer I started to wonder of the whole process can be represented in the spreadsheet since all     
55:59     
the calculations are fairly simple I'm a visual thinker I couldn't think of a     
56:04     
better way to do it and so this is kind of going on through you know this is not     
56:10     
python this is a spreadsheet the spreadsheet apparently is all un need and this is of course is the self     
56:17     
attention mechanism the core of the Transformer and again you open up the spreadsheet and this is what it shows it     
56:22     
shows these tables that transform to other things and you know it's easy to see what     
56:30     
components will you see so it contains all the Transformer components including an embedding a layer Norm self attention     
56:40     
projection u a maximum likelihood probability soft Max and logits and this     
56:48     
is based on Andre Caper's nanog GPT structure which is an 85,000 parameter     
56:54     
model say is something that you know is uh one of these very small     
57:00     
gpts uh it is very clearly a very small size but it's both complex enough for me to understand how it works but also not     
57:07     
too big to crash my computer which of course we talked about with the Raspberry Pi implementations of a large     
57:12     
language model and those small models are actually very important I think for understanding how the model works you     
57:20     
know it's it's the old Edge you have to learn to run before you can fly so I think that's a uh you know good sort of     
57:27     
use case for this but also you know you can do things and just kind of understand how to train something how     
57:35     
you know something is sort of implementable if something is implementable or not and you can of     
57:42     
course train it on very small data sets if you want so you can get very small data sets and very specialized     
57:47     
information and so yeah there there's a lot more in the in this uh read me     
57:53     
including some uh YouTube videos on what's Bill GPT the nanog GPT project     
58:00     
and 3D visualizations of transformers this is particularly interesting so you know there are     
58:08     
different types of visualizations people have used of transformers this is an interesting visualization this actually     
58:15     
uh is a visualization of nanog GPT not in uh a spread sheet but it's in this     
58:21     
sort of three-dimensional diagram here oops     
58:28     
and so if we zoom in and actually they have it for gpt3     
58:34     
gpt2 both extra large and small and so you can see these different components     
58:40     
here where they have the different matrices you can zoom in on the matrices     
58:46     
so you know we're zooming in on the different weight matrices the vectors     
58:52     
soft Max vectors soft Max matrices the projection     
58:57     
weights uh maximum likelihood weights Activation so forth so we have all these     
59:03     
different components and we can zoom through this 3D model I don't know what they're modeling this in but it's really     
59:10     
interesting and so now I have this article by Kevin luck this is his uh     
59:15     
approach to this building an ml Transformer in a spreadsheet so this is     
59:20     
actually the same one attention is all you need introduced Transformer models which have been wildly effective in     
59:26     
solving various machine learning problems um and so he actually did his     
59:32     
own version of this where created a transformer in a spreadsheet and made a video walking through it so this is a     
59:39     
YouTube video that talks about creating a transformer in a spreadsheet um at a     
59:44     
high level Transformers are effective because they convert the data in a way that can make it easier to find patterns     
59:50     
they build on ideas from convolutional neural networks and our current neural networks and and this has to do these     
59:57     
are analogies to focus and memory uh you know they use these terms uh from     
1:00:04     
cognitive science and they kind of bring them to neural network so the convolutional neural network is focusing     
1:00:10     
and the recurrent neural network is the memory component and this is combined into what they call Self     
1:00:18     
attention so implementing the Transformer really helped me understand all the components so another point for     
1:00:24     
that especially proud of my metaphor of scoring points for explaining self attention um and this these are some     
1:00:32     
other resources on the attention mechanism in Transformers so yeah he     
1:00:38     
gives it he gives his own take on using spreadsheets to build large language     
1:00:45     
model components particularly Transformers so our final feature of     
1:00:50     
today is to talk about uh Theory and Theory building and we have two articles     
1:00:57     
that have popped up in our slack channels so I'll go through those the first one is this article by Grace     
1:01:03     
Lindsay David Barack C o'd Donnell Stephanie     
1:01:08     
Palmer and this is a breakout room um I guess it's a perspective on a breakout     
1:01:14     
room some on something called the transmitter which I think is a neuroscience blog and this is U must the theory be     
1:01:22     
falsifiable to contribute to good science so this is sort of from the     
1:01:27     
perspective of Neuroscience and they're talking about Theory being falsifiable or must it be     
1:01:35     
falsified and so in Neuroscience they have their own approach in some Sciences falsifiability is important in other     
1:01:42     
Sciences lessen so keep that in mind falsifiability is considered by     
1:01:49     
some to be the Cornerstone of any scientifically sound Theory indeed certain schools of thought within the     
1:01:54     
philosophy of science that with theories is that are not falsifiable as pseudoscience but is the falsifiability     
1:02:02     
or testability of a theory actually crucial for good science or can a non-testable theory still help Drive     
1:02:09     
PRS so a theory that you can't say is you know an idea that you can't     
1:02:16     
falsify at least in principle because sometimes things actually are non     
1:02:21     
falsified and those are the the stronger uh hypotheses     
1:02:26     
theories uh that's you know that's you know if they're not falsifiable from the     
1:02:33     
start then they can't really be uh scrutinized so that's why they're called     
1:02:38     
pseudo signs but again like I said in some uh sciences and some forms of     
1:02:44     
science we can easily build falsifiable theories falsifiable hypotheses and     
1:02:49     
others we can't uh it's not easy to do so this is another you know this is a a     
1:02:55     
case where a philosophy of science gets ahead of the actual practice of science     
1:03:02     
and this is something you have to keep in mind when you philosophy of science is that it's an idealization and that it's not NE     
1:03:09     
necessarily something that people think a lot about when they're actually doing science but nevertheless It's always     
1:03:15     
important to keep it in mind at least in terms of you know where are we going because people tend to go in many     
1:03:20     
different directions and sometimes they run into problems with their ability to     
1:03:26     
sort of separate the wheat from the cha let's it say Neuroscience is a relatively young     
1:03:32     
scientific Endeavor so we may benefit from more unconstrained exploration of ideas and theories making room for     
1:03:39     
non-testable theories may help expand the space of ideas in neuroscience and provide footholds to Grapple with     
1:03:45     
increasingly large and complex data sets also given that non-testable theories     
1:03:51     
are already pepper the field of Neuroscience it is important to explore the role the airpl and how well suited     
1:03:57     
they are for it so Neuroscience has a lot of non-testable theories and part of     
1:04:03     
that is because we haven't traditionally have the tools to address those problems     
1:04:09     
or theories but also because we have a lot of sort of ideas that are very sort of     
1:04:17     
out there in terms of how to test so for you know we'll come up with the example     
1:04:23     
of Consciousness and so Consciousness is     
1:04:28     
notorious for having non-testable theor and so you know do we really want to     
1:04:35     
sort of have non- testable theories no but sometimes we have to and it's just     
1:04:42     
really kind of hard to get a handle on those non-testable theories we can State     
1:04:47     
something we think something is true we say how do we test it and we say well if     
1:04:53     
we had a way to measure the brain real time over 30 years we could do this and     
1:04:58     
of course we don't have that technique so it it's a moot point it's theoretically testable when we don't     
1:05:04     
have the ability to test it there have been a lot of things though where the technology has caught up with the     
1:05:11     
testability of the idea of a theory um I would also argue that     
1:05:16     
Neuroscience even though has a lot of quote unquote theories it's actually very devoid of theory and that seems     
1:05:23     
like a tautology but it's not because you know it isn't     
1:05:29     
driven by Theory it's driven a lot by data and isolated questions and then the     
1:05:34     
theories that do exist are somewhat non-testable so there's really a gap     
1:05:40     
between like things that are just kind of things people assert that you can't     
1:05:45     
test and then things that actually are drawn directly from like data and uh     
1:05:53     
investigation so you know we don't have like a theoretical Neuroscience way we have a theoretical physics the     
1:05:59     
theoretical physics also has this problem in some cases where you can't test things but in any case you know     
1:06:06     
that's where we are with Theory building so this this is part of a weeklong conversation with three     
1:06:14     
researchers uh Grace Lindsay of course is the moderator so she's asking these three researchers doing a back and forth     
1:06:21     
with them over slack to Define try to Define what qualifies as non-testable     
1:06:26     
and what trait such theories tend to have so you know to say something is non- testable can be like derogatory but     
1:06:35     
it also has certain properties so what does it mean to be     
1:06:40     
non-testable um and this is something that you know we want to be able to sort     
1:06:46     
of get our hand head around in terms of maybe what's thly pseudo science and     
1:06:53     
maybe what's maybe be just beyond the scope of our technological capabilities to measure but maybe things that are     
1:07:00     
actually testable so maybe there are things in ideas that we can test and     
1:07:05     
sometimes it isn't obvious how to test something and this is one thing when you're building you know hypotheses or     
1:07:11     
theories you ask a question you kind of construct a hypothesis maybe you build a     
1:07:16     
a theory and you say okay how could this be tested and you have no idea but     
1:07:22     
sometimes you have to kind of think through how to test it how to implement and it's not unlike in technology where     
1:07:28     
you have to think out a pipeline to say okay we're going to build this thing how do we do it what are the components what     
1:07:35     
is the sort of the workflow that we need to follow and it isn't exactly like that but it has some     
1:07:42     
similarities so this is an important point that you have to kind of think about if something is non-     
1:07:47     
testable maybe something is testable maybe something's clearly never able to be tested because it's just     
1:07:54     
something that you're asserting or it's something you can't observe but maybe something is you know if you could build     
1:08:01     
the right measurement device you could actually test these things so a lot of     
1:08:06     
the data we're getting from nextg sequencing a lot of the data we're getting from uh you know smaller probes     
1:08:14     
that we can put in the brain or we can get things at higher spatial resolution now as opposed to like 50 years ago we     
1:08:21     
can then you know maybe test some of the ideas that been floating around the literature for that long     
1:08:28     
we describe specific examples from Neuroscience with an emphasis on normative approaches we also discuss challenges in     
1:08:35     
accessing the quality of non-testable theories and the role they play in inspiring testable     
1:08:41     
predictions so sometimes we have non-testable theories that are sort of like out there because they guide us not     
1:08:48     
because they're predictions or they're they're highly predictive so you know we have ideas about things that are sort of     
1:08:57     
normative and then they lead to test predictions because people build off of     
1:09:02     
that so it's just like an idea that someone throws up off the brain you know     
1:09:08     
sometimes they're bad ideas like that sometimes they're good ideas like a bad idea would be the example of the Triune     
1:09:14     
brain where you know there's a lizard brain and then there's a more evolved     
1:09:20     
brain and this is all kind of pseudoscientific but the idea that it's normative that it kind of structures way     
1:09:27     
we think about the brain and then of course you might be able to build things up to test that     
1:09:32     
prediction you know that that's that's what we're talking about by the end we reconsider referring     
1:09:39     
to those these ideas as theories at all opting for Frameworks instead so there's a lot of back and forth about what a     
1:09:46     
theory is we could spend many many years having a conversation about actually     
1:09:52     
what a theory is believe it or not in so so Neuroscience I think there's somewhat     
1:09:59     
of an aversion to clear thinking about Theory at least in my opinion and even just using the name theory is kind of a     
1:10:06     
problem people will use framework because so much stuff is driven by data     
1:10:12     
and not like you know other types of ideas although you know when we get into the world of AI     
1:10:19     
too you know like I said about AI you know in AI they don't really have a     
1:10:24     
really good good handle on what intelligence is but then they build on that scaffold of a really loose poorly     
1:10:31     
defined idea and they say oh all of a sudden machines have intelligence well you know sometimes we     
1:10:38     
need Frameworks to underguard what we're doing so if we had a framework for intelligence and we're building an AI we     
1:10:43     
know kind of how we Define intelligence and then you can debate whether that's a good idea of how to define that and then     
1:10:50     
you build upon that to give yourself these uh you can actually have test testable theories and testable     
1:10:57     
hypotheses based off the framework so you know this is an interesting uh exchange here they have     
1:11:04     
this exchange kind of published um so this is a a slack     
1:11:09     
discussion um and it kind of goes through some interesting things here here's a quote     
1:11:15     
from Stephanie Palmer in Neuroscience we have a lot of ideas but your were theories is anything that's not testable     
1:11:22     
simply not a theory so you know there are all these sort of opinions and what theories are what's testable you know     
1:11:29     
all this stuff um Cen O'Donald uh says I have     
1:11:37     
tried to interrogate chat GPT for examples of a theory but 90% of its     
1:11:42     
suggestions are related to Consciousness so again like I said Consciousness is a sort of like land of un non-testable     
1:11:50     
theories you know or worse uh assuming we are staring clear that topic     
1:11:55     
partially because IIT has already been debunked as pseudoscience by Grace linday at all they wrote this paper on     
1:12:02     
this topic so not to get too controversial but that's what that's     
1:12:07     
about then the only potential interesting examples I could get of it were and so this is the list of theories     
1:12:13     
in Neuroscience that cat GPT has     
1:12:18     
generated uh cryptonia and hidden memories which is the theory that all     
1:12:24     
experiences are stored as memories in the brain even if we cannot consciously access them and they fall into a gray     
1:12:32     
area the extended mind Theory where the Mind extends beyond the brain and body     
1:12:37     
that include the external environment specific genetic determinance of complex Behavior the     
1:12:44     
idea that complex human behavior such as propensity for certain careers specific personality traits or detailed     
1:12:51     
preferences are uh directly and solely determined by specific genes that's     
1:12:57     
difficult to falsify um and then neuroplasticity     
1:13:02     
limits while it's established that the brain has a significant degree of neuroplasticity or the ability to     
1:13:08     
reorganize itself that prakes limits of this plasticity or hard to to find and test so these are all things that are     
1:13:15     
sort of theories in neuroscience and they're all very hard to falsify or detest or that sort of thing so this is     
1:13:23     
interesting that you know we had this uh this set of things that were generated by Chad GPT and it's really     
1:13:29     
just a summary of the literature and this other point he makes also why since     
1:13:34     
I recently ran a workshop on brain learning rules I was thinking about Blake Richards and Conrad cordings     
1:13:40     
proposal that the brain must be doing gradiant descend during learning it's an appealing idea but hard     
1:13:47     
for me to see how to test so this this point here brings up     
1:13:52     
something interesting and that is that you know sometimes we have theories but sometimes this theories underly are     
1:13:58     
underlain by this this sort of analogy building and this is I think important     
1:14:04     
for like Neuroscience because a lot of like theoretical Neuroscience is you     
1:14:09     
know some at least in in large part is based on like analogies with other things since you know we have we don't     
1:14:16     
have a very deep history of knowing what the brain is even doing there have been a lot of analogies for intelligence or     
1:14:23     
for what the brain does I guess in gradient descent during learning the brain is apparently optimizing things     
1:14:30     
during learning and so that's where the gradient the scent analogy comes in but     
1:14:35     
you know what does that mean is that the only thing that happens during the living what is the brain doing it's     
1:14:41     
obviously doing some sort of uh optimization or it's doing some sort of     
1:14:47     
like well we we know that like for example in machine learning there's radient descent and that leads to     
1:14:52     
Greater learning so the brain must be doing a similar thing but if we look at what's actually happening during morning     
1:14:59     
there are a lot of things happening there's acquisition there's optimization there's um you know a lo     
1:15:08     
you know a loss function I guess you could say uh there are things going on the molecular scale they things going on at     
1:15:15     
the anatomical scale and so so on and so forth so you     
1:15:21     
know it's it's really hard to kind of make a statement that's sort of has the Assumption of this     
1:15:28     
analogy and then build some sort of testal hypothesis off that and these other points you know     
1:15:35     
they have similar problems with them another aspect of this that's interesting is that you know     
1:15:41     
Neuroscience kind of comes out of psychology and psychology has you know a     
1:15:47     
history of having the sort of analogies uh for thought and so you know     
1:15:53     
this is kind of an interesting point uh some of these analogies don't have anything to do with the problem and they     
1:16:00     
were just kind of pulled into Neuroscience it's another um yeah so     
1:16:06     
this kind of goes through this uh conversation race Lindsay says I want to     
1:16:12     
know if we have two non-testable theories A and B how do we decide a priority which is more likely to inspire     
1:16:18     
those experiments that will lead to a good testable Theory so this is again     
1:16:24     
you know because we can't test things we have rival theories how do we know which one     
1:16:31     
is better maybe inspiring experiments we actually something that is     
1:16:37     
um you know has some testable aspect to     
1:16:45     
it and so this is a really good conversation again this is something that we can go through maybe more in     
1:16:52     
more depth later if people are interesting uh but this is you know this is something that could be debated for     
1:16:57     
years and probably there would be no good answer coming out of     
1:17:02     
it so our final paper or article for today is from the for graviton blog and     
1:17:11     
this is a a conversation between Yan laon and Elan musk I say conversation in     
1:17:16     
a very loose sense but the topic is about the science require     
1:17:22     
publication and so this is you know this idea that you know what do you what     
1:17:28     
qualifies as science so obviously we know we talked about Theory building hypothesis testing and those sorts of     
1:17:36     
things and some it makes maybe your science more or less rigorous but you know sometimes it's     
1:17:43     
about letting the world know what you're doing so if you do an experiment or if you even do find that like some idea     
1:17:49     
from Neuroscience can be tested and falsified or whatever um     
1:17:55     
if you don't let people know about it it's not really science because you just have it in your own head and you need to     
1:18:02     
get it out into the world so that other people know that at least you tried something and it maybe didn't work or it     
1:18:09     
did work and you need to let people know about that so the publication aspect is     
1:18:14     
important now I I put a caveat on this     
1:18:20     
in that there's this separate conversation in the uh open science community     
1:18:25     
about whether we actually need journals and I don't think we need journals     
1:18:31     
necessarily you can publish your work in various ways you can publish them as     
1:18:36     
documentation or in terms of lab notes or you can publish them in preprint form     
1:18:42     
and you know so publication can be very flexible but I think the idea I think the idea     
1:18:49     
stands what y Lon says in the first part of this uh thread     
1:18:55     
is that if it's not published it's definitely not science because if you don't put it out into the world if you     
1:19:00     
just keep it in your own head you know it doesn't mean anything it has to be a social activity has to be out in the     
1:19:07     
world so people can read about it people can understand what you did as well so     
1:19:12     
it's about it's about description it's about letting people know it's about communication and you know it's about     
1:19:20     
sort of replic you know replication allowing people to replicate at it properly so you don't want to just put     
1:19:27     
it out as a series of tweets you want to have like you know full details of how     
1:19:32     
something was done how something uh can be replicated so this is whole thread he's     
1:19:39     
responding to Ean musk who Yan Leon says well if it's not published it's     
1:19:44     
definitely not science Yan musk replies that is one of the dumbest things anyone has ever said     
1:19:50     
which I don't understand why that would be dumb but um and then Yan Lon follows up to qualify a science a piece of     
1:19:58     
research must be correct and reproducible be correct and reproducible must be described in sufficient detail     
1:20:05     
to be published or to receive a seal of approval the publication must be checked for correctness by reviewers to be     
1:20:11     
reproduced the publication must be widely available to the community and sufficiently interesting all these     
1:20:17     
points are kind of uh you know they they kind of conform to a certain model of science you don't     
1:20:24     
think all of these things are necessarily absolutely required um there are different ways we can do this but I     
1:20:31     
think you know things have to be sort of written they have to be you know published put out into the public eye     
1:20:39     
and yeah you need some oversight so you know I don't know about seal of approval I mean obviously there are a lot of     
1:20:46     
people publishing things that are like you know their papers that get retracted     
1:20:51     
you have people putting things out in the world that are you you know antivaxer or uh you know pseudo science     
1:20:58     
and so we want to be able to sort those out and say those are bad then this is good and so there has to be some sort of     
1:21:07     
value judgment there but I think the idea of being able you know being able to have a publication that people can     
1:21:13     
refer back to that standardizes things that tells people in the world what you found how you did something that's a     
1:21:21     
very important part of science that social aspect um if you do research and note publish     
1:21:27     
it it's not science without peer review and reproducibility chances are your methodology was flawed and you fueled     
1:21:34     
yourself into thinking you did something great one one will over hear about your work no one will over pick it up and     
1:21:40     
build on top of it no one will build new technology products with it your work     
1:21:45     
will have been in vain die bitter and forgotten I think that's a little over the top but the point here is that you     
1:21:51     
know uh there's this aspect of you know doing science and how we do science as     
1:21:58     
as a sort of a methodology and sometimes that can get sort of bogged down of this idea of what     
1:22:05     
cargo called right you just do the you check boxes off to get things done and     
1:22:12     
that's the way some people think about science there are other aspects of science too there is a creative aspect     
1:22:18     
there is of course the idea of reproducibility and making your science     
1:22:23     
kind of build upon on itself so if I publish a paper and IT addresses this problem can I build another paper from     
1:22:31     
that or can I follow up that paper with another paper that kind of explores the     
1:22:36     
topic and so you know there's there's this idea that a paper is sort of a minimal publishable unit in other words     
1:22:43     
it might be a single experiment it might be a set of experiments talking about you know with     
1:22:49     
a certain scope talking about a certain topic and so you know what con stitutes     
1:22:54     
a publication is you know you can question what constitutes a publication but basically it's a unit of publishable     
1:23:01     
work maybe a minimal unit of work and there's usually a series of those so in     
1:23:07     
the lab here we usually publish things you know we kind of follow up on a paper     
1:23:13     
with another paper and IT addresses a different question but in any case I think this is     
1:23:19     
an interesting conversation about what Publications are what they kind of accomplish     
1:23:25     
and so forth I don't think it's a very complete discussion because of course you know there's there are these other     
1:23:32     
aspects that are not talked about here this was just basically built off of this sort of Rift     
1:23:38     
between uh people on X so you know I just thought it might be interesting to     
1:23:44     
go over to understand a little bit about how people think about doing science and     
1:23:52     
practice so that's all for today uh thank you for paying attention and see you next week     
