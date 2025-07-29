## Meeting Recording

[YouTube link](https://youtu.be/dAtnBhDW_XU)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114923674830623170)

## TRANSCRIPT 
0:00    
Hello. Um, today I'm going to give a solo Saturday morning neurosim meeting    
0:05    
update. We're going to talk about a number of different features, but first I wanted to give an update on projects    
0:13    
and what's been happening in the lab in the last week. So on Monday, we had our D.Aworm meeting and a lot of interesting    
0:20    
things there. Jadratha went through the laral synaptogenesis data set and we    
0:27    
discussed sort of the details of the data set and some of the ways he could apply it to his project.    
0:34    
We also talked about simulations of early life and some of the ways you can simulate    
0:40    
sort of the formation of cells uh and the formation of what are called um    
0:48    
nucleotide like models minimal models of of nucleotides and things like that. And    
0:55    
then we talked about the possible shapes of life. So there were some someone did some experiments in the wolf from    
1:01    
evolution platform and we discussed those results. So that was a pretty good meeting and    
1:07    
that's on our evil worm YouTube channel. The second uh meeting of the week was    
1:13    
Friday and we had the open source meeting and we had project updates for Google Summer of Codes where Google    
1:19    
Summer of Code scholars are continuing to produce code and produce uh make    
1:25    
progress on their projects. And then I talked a little bit I followed a little bit up on the open    
1:30    
washing that we talked about last week talking about Meta's llama model. And    
1:36    
then Jesse gave an update on some of his activities. He's got some internships running through Joe and some other    
1:43    
things like that. Hello.    
1:51    
Hi. How are you? All right. uh why don't we dive into some readings    
1:59    
and things like that. Okay, so the first thing I'm going to talk about today is on this BI reading    
2:07    
group. So this is the biological intelligence complexity group    
2:13    
and uh this was uh something that Jesse posted in um the Slack. I I think it was in the    
2:20    
cybernetics channel because what they what they're doing in the BI complexity    
2:26    
group is they're trying to go over different keystone papers in the history    
2:32    
of like cybernetics and AI and brain science. It's just a wide range of    
2:39    
different areas. uh they talked about um although they I    
2:46    
don't know remember what the last paper we talked about was um but this paper was the it was by Warren Weaver. It was    
2:54    
from 1948 and we'll get into that paper a little bit in a minute but this is    
2:59    
sort of a screenshot of the Zoom group. So they were I don't know why they were face palming here. We had a discussion    
3:05    
about it in the slack. Uh but they were basically talking you know they'll read    
3:10    
the paper they'll invite people to sort of interpret the paper and then you'll    
3:17    
have the rest of the audience kind of ask questions. So this was the weaver paper from 1948    
3:24    
and I'm going to read from the chat on the right. So there was a quote to what extent a    
3:30    
property of the observer versus the system that was uh kind of you know if    
3:36    
you think about second order cybernetics where their focus isn't just on the    
3:42    
system but on the observer of the system and how the observer plays a role in the systems supervision and regulation.    
3:51    
So, uh, you know, they're they're kind of tying in this Weaver paper to some of    
3:56    
these topics in cybernetics. Um, Kevin Mitchell gives a observation    
4:03    
here. I think it's relative to the predictability of the effects of manipulations. That's kind of the    
4:10    
pragmatic payoff. uh Kran Razvan there's much remind so    
4:17    
much reminds of the simple book titled Flatland which is interesting because the book Flatland is this book that was    
4:25    
written in the 19th century and it was about these creatures that lived in a one-dimensional land and they would not    
4:32    
be able to see it was happening at two dimensions and then there's this two-dimensional land where the creatures    
4:39    
weren't able to conceive of anything in three dimensions. and so on and so forth. And so, um, it's    
4:46    
a nice exercise in thinking about how if you were living at a certain sort of    
4:53    
dimensionality, you would be unable to perceive things happening at higher dimensionalities.    
4:59    
And it seems kind of silly to think about it. um but it's very important for    
5:05    
things like visualizing uh data sets and phenomena of high    
5:11    
dimensionality. So like a lot of machine learning, one of the things that underpins a lot of    
5:16    
machine learning today is taking a lot of complex data,    
5:22    
taking up a very complex latent space and boiling it down to maybe three    
5:28    
dimensions that we can visualize. And so in doing so, we usually throw out a lot    
5:33    
of detail, a lot of information um that is inherent in those higher    
5:39    
dimensions. So it's it's it's kind of you know I don't think people talk about flat land enough really. Um and so and    
5:48    
then this is another comment. We are always living in a flat land as we see what we see not what is out there not    
5:55    
understanding it means we are missing a dimension. So you know the again like    
6:02    
there you know some theories of cosmology posit 11 dimensions of    
6:07    
spaceime and we live in three of those and you know that's basically what we    
6:14    
have to work with and so that's that's what that's referring to but it's also    
6:20    
referring to the whole machine learning aspect of dimensionality reduction.    
6:25    
Um and then there of course these issues of sort of the curse of dimensionality and other things like that.    
6:33    
Uh then someone says 100%. And then Richard Lang says don't rock    
6:39    
the gravy train either but why would any observer agree that it is complex or any    
6:45    
computationally constrained observer perhaps. on that. So that's Richard Lang and then    
6:51    
I think Jesse said the system will tell you if it's complex and then Kevin Mitchell's responds, yes,    
6:58    
I think the thing about complex systems is that they're not flat. So this is    
7:03    
again, you know, this this idea of flat land kind of came up in this commentary.    
7:10    
And then I like the great face palms theme. There's Pequard as a having doing a face palm. There's the great double    
7:18    
face palm of Pequard and Riker and then of course Darwin giving a face palm. So    
7:23    
it's a very common thing. This is the paper Weaver science and    
7:29    
complexity from 1948. This is um where it gives us typology of    
7:36    
different types of complexity organized simplicity organized    
7:41    
complexity and disorganized complexity. So organized simplicity is where you    
7:48    
have this sort of I guess um it focuses on regularity.    
7:54    
So in systems and behaviors and in relations you have these like arrays these ordered arrays of things. So it    
8:01    
could be like a checkerboard pattern or um a simple square matrix or some sort    
8:09    
of locally connected thing that has only local connections. And then the dynamics    
8:16    
of an organized simplicity or sine wave which is a periodic sine wave.    
8:23    
And then going to organized complexity you start to get these clumps or clusters of things. So in the systems    
8:29    
you get these clusters of things that are distinct yet you know they're they're uh individual subunits    
8:36    
the behavior of organized complexity are sort of these uh again clustered behaviors they begin    
8:45    
to become aperiodic. they they exhibit the sort of structure and then you get    
8:50    
the relations which you see in a network here. Instead of this locally connected    
8:55    
M uh uh uh lattice, you get this network that has modules in it and you get this    
9:03    
branching that you know leads to the modules and then the dynamics are    
9:09    
um you know you get uh shifts in the dynamics that represent these kind of    
9:15    
clusters and then disorganized complexity is where you have I guess    
9:21    
disorganization. So one of the things about this paper of course is that it becomes it comes right or well before    
9:30    
the era of chaos. And so there's this whole um field of chaos theory, but also    
9:36    
this idea of operating on the edge of chaos and where you have ordered systems    
9:43    
that become more disordered uh as they become more complex and then    
9:50    
but they still maintain some sort of general order. So they can sort of be    
9:55    
poised on the edge of chaos. They can be poised to undergo phase transitions at any    
10:02    
given time. They're more sort of excitable.    
10:07    
They can change their state more readily, but they still have this organizational aspect to it where    
10:14    
they're not completely random or completely out of control, I guess, is the way to put it.    
10:21    
And so this and again, so this is the language is different here, but it's kind of a similar concept. So for    
10:28    
disorganized complexity you have systems. The systems sort of are atomized.    
10:34    
Um the behaviors are sort of maybe on the edge of chaos. It looks like you    
10:39    
have um a cellular automa here where you get a lot of uh things that kind of    
10:45    
regenerate patches that are varying sizes and then the relations are this    
10:50    
complex network. Uh we're heading toward from um an organized complexity. we have    
10:56    
sort of this ordered network of modules, this this branching um and then you go    
11:03    
to this what is sort of approaching a hairball network is what they call a hairball network which is where you get    
11:10    
random connectivity but interspersed with ordered connectivity and then you have the dynamics which are stochastic    
11:18    
but also have components that are you know where the information lies. So in organized complexity, this trace has    
11:25    
information in it. Disorganized complexity, this trace also has information in it, but it's embedded in    
11:31    
a lot more noise. And so this is where you get to the edge of chaos.    
11:37    
So one aspect of this discussion that the BI complexity group was talking    
11:44    
about was that this comment by Cameron Rosvon, we are always living in a flat    
11:50    
land. We see what we see. And this of course goes back to the 19th century    
11:56    
book Flatland as I said. And so this is a teaser for some work that's coming up    
12:01    
for our work from our group for the Bea conference this year. So the Bika    
12:08    
conference is coming up next month and we're going to be presenting a paper. Um    
12:14    
this paper uh talks about super performers which is something we did a paper on in 2023.    
12:21    
and linking that to world models and uh intelligence augmentation. So this is an    
12:28    
area that we've been exploring in our phasic um research area and so if you're    
12:36    
interested um you know look up FASIC on our website and you'll uh find out more.    
12:42    
But in this paper we actually talk about flatland and how it you know world what we call a    
12:49    
world model for an agent actually can be influenced by thinking    
12:54    
about flat land and then thinking about how to break out of flat land. So there    
12:59    
was this mention of flat land in our paper for the conference here    
13:05    
and there's a citation which I'm going to talk about in a little bit. This is the flatland fallacy moving beyond    
13:11    
lowdimensional thinking. This is a paper from topics in cognitive science in 2018    
13:16    
and I'll talk about that paper in a minute. But I have a slide for the upcoming talk    
13:22    
for bea. So this lays out the flatland problem for world models. Um this is a    
13:29    
picture on the right of flatland. It's stylized after Edwin Abbott's 1884 book,    
13:35    
Flatland, a romance in many dimensions. And in that book, you know, he talks    
13:41    
about these beings that live in one dimension or two dimensions, and they're they're constrained to that world. So    
13:48    
beings that live in one dimension are on this basically like a number line. They    
13:54    
can't move past one another. They can only move in their space. They have no    
14:00    
access to two dimensions, so they can't eat anything. And they're just basically    
14:07    
line segments moving along a larger line segment constrained by their line segments.    
14:14    
If you go to a two world two dimensional world, you can have creatures of different shapes, but those shapes are    
14:20    
two dimensions and they can't access the third dimension,    
14:25    
which is depth. So again, they can live on a two-dimensional plane,    
14:32    
but that's about all they can do. If you think about video game, early video games where they had this    
14:37    
two-dimensional screen, it might have been a tooidal world where they just had access to the surface of the toid and    
14:44    
nothing more. So they could make movements along that plane, but there was no depth.    
14:51    
And then uh 3D space, of course, is where we live. You have three-dimensional space. You    
14:58    
have depth, but you also have width and height. And that's where we move. We move in    
15:03    
three dimensions. Some people use fourth time is a fourth dimension, but in terms of space, we    
15:10    
have three access to three dimensions. Now, we know from cosmology that they're higher dimensions, of course, but we    
15:18    
can't access those directly. And so this is an image where you see this    
15:24    
uh two-dimensional character sort of    
15:29    
uh rise above a plane or fall bel beneath a plane. And this two-dimensional object is able to see    
15:36    
the being only as it's crossing that plane and coming above it. So they can't see below. There's no depth.    
15:42    
And so this is again this is something that um    
15:51    
this is something Carl Sean talks about in his um in his cosmos series where he    
15:58    
has a video where he does this flat land sort of demonstration of creatures being in two dimensions and    
16:05    
creatures being in three dimensions. And then the implication is is that you could have something in higher    
16:10    
dimensions that we as humans couldn't perceive fully. So that was that's the    
16:16    
idea here. And so in for world models though there is this flatland problem    
16:22    
which is that the world always has a higher dimensionality than the model. So if we have a world model for agents,    
16:31    
that model has a certain dimensionality which you know might be an embedding,    
16:38    
it might be a a formal representation and you know we take things from the    
16:44    
world, we kind of abstract them away from the world and the world always has a higher dimensionality than the things    
16:50    
that we abstract away. So unless we have every single aspect of the world in our    
16:55    
latent space or on our representation then you know we our world is always    
17:02    
going to be more complex or at least have a higher dimensionality than the model of the world. So again this is    
17:08    
where the paper comes in toppings in cognitive science. Um and they talk about in that paper that there's this    
17:15    
dilemma of world of flatland the flatland problem in cognitive science.    
17:21    
Uh one part of this is that par the thing that we use to really kind of deal    
17:28    
with um making scientific hypotheses out of complexity. Something called parony    
17:35    
which is the easiest simple the simplest explanation which is often the best    
17:40    
explanation. But what we tend to do in making hypotheses is we tend to boil    
17:46    
things down to the simplest explanation. But in doing so we also lose dimensionality and in fact parsimmonious    
17:53    
explanations are inherently lowdimensional theories. They reflect reality of a much higher dimensional    
18:00    
problem. So you can have a parsimonious explanation that deals with    
18:07    
high much higher dimensional spaces but it may not fully describe those.    
18:14    
Similarly we can have simplified explanations of complex phenomena. We call that the flat land fallacy where we    
18:21    
assume that the simplest explanation is the best. But sometimes we're just fooling ourselves    
18:27    
as we inhabit this flat land. All right, the last thing I want to talk about here is this topics and cognitive    
18:33    
science paper. This is by Essen Jolly and Luke J. Chang. Um, and again they're    
18:40    
cognitive they're coming at this from a cognitive scientist science point of view. So we have this abstract that    
18:47    
reads psychology is a complicated science. It has no general axioms or mathematical proofs is rarely directly    
18:55    
observable and is the only discipline in which the subject matter is also the tool of investigation    
19:02    
like the flatlanders and Edwin Abbott's famous short story 1884. We may be led    
19:07    
to believe that the parsimony offered by our lowdimensional theories reflects the reality of a much higher dimensional    
19:14    
problem. Here we contend that this flatland fallacy leads us to seek out simplified    
19:20    
explanations of complex phenomena limiting our capacity as such to build    
19:26    
and communicate useful models of human psychology. We suggest this fallacy can be overcome    
19:33    
through a the use of quantitative models which forces us to formalize our theories and b improve quantitative    
19:41    
training which can build new norms for conducting psychological research. So their uh interest is in psychology very    
19:48    
specifically and they give some uh recommendations for overcoming this flat land problem. And so you know in the    
19:56    
they they talked about that in the discussion group that this is a problem that is sort of parallel to this idea of    
20:04    
simplicity versus complexity. And in dealing with complexity, we tend    
20:10    
to simplify things. But in simplifying things, we end up running into this flatland problem.    
20:17    
So again, this is the flatlander view of a sphere. It's a circle. It's 2D. The 2D    
20:24    
creature cannot perceive the 3D. And in reality, we have this sphere in    
20:29    
3D. Actually, in reality, we might have a higher dimensional structure, but we can't perceive that as such.    
20:37    
Um, so this is just kind of a basic idea about this problem.    
20:43    
Human psychology is rife with complexity. We're dealing with the brain. We're dealing with behavior.    
20:51    
And you know why does it happen? Why does the flatline fallacy happen? It's    
20:56    
because it's a bias and a limitation of human cognition. So we have a lot of uh sort of reasons    
21:06    
four main reasons why this fallacy occurs. The first is that biases in the fielding of understanding.    
21:13    
B is limitations of human cognition. C is over reliance on traditional    
21:18    
experimental design and analytical approaches. And D is limitations in our ability to communicate complex concepts.    
21:26    
So you may be saying, well, how does uh modern complexity theory fit into this? And I think it's it's worth noting that    
21:33    
this is something that's been talked about extensively in modern complexity theory, especially people interested in    
21:40    
uh social science and complexity theory where part of this is about experimental    
21:47    
design flaws or limitations. Part of this is about our own cognitive limitations and biases of our home field    
21:55    
or of making things easier. And so it's not as easy as you'd think to overcome    
22:00    
this. It's not just a matter of applying the techniques of complexity theory. For    
22:06    
one thing, those techniques are still lacking in terms of what they offer. But    
22:11    
moreover, it's hard to actually deal with these problems, deal with these issues effectively. So this is the paper    
22:20    
here. Um    
22:25    
so Warren Weaver as it turns out he wrote um if you know the mathematical theory of communication    
22:31    
he's a co-author on that book with Claude Shannon. Claude Shannon is was a    
22:38    
researcher um a theoretician and he worked at Bell Labs and he did a lot of things. Um, one    
22:46    
of those things was develop uh the theory of mathematical theory of information or the idea of information    
22:53    
entropy. And so you have this equation that sort of famous uh it's the h value    
23:01    
for information. And so if we we actually if we go to the board here I'll draw out the equation so    
23:07    
we can appreciate it. Um this is H equals and it's usually minus summation    
23:16    
and it's a probability of I and then there is this multiplier    
23:23    
log probability of information. It's usually the way it works. Sometimes you    
23:29    
can take this as log two. Sometimes you can take this as log 10. Sometimes you    
23:35    
can take this as natural log and the difference here is that you're    
23:41    
just it's just the way in which you're normalizing the the information. So if    
23:46    
you have like a base 10 usually gives you an index from 0 to one. If you're    
23:51    
doing it at base 2, it's usually means you're dealing with bits. So sometimes people like to take um different bits in    
23:58    
a string and calculate the information and that gives you that number. log 10    
24:04    
will give you or base 10 will give you an index between zero and one on a base    
24:09    
10 scale. So if we're looking at any sort of integer then that's what we get. And then log e is just you know sort of    
24:16    
a natural log a way to normalize it against um val a range of values. So the    
24:23    
idea is that you can calculate the information. You'll usually have some ensemble of things. So the ensemble will    
24:31    
be a number of units that you're looking at and they have a certain amount of information. So for example, we have a    
24:38    
bunch of circles here and these circles are lights that turn    
24:43    
on and off and we measure that over time. So over time    
24:51    
and we want to know, you know, how how we don't necessarily want to know,    
24:56    
you know, if they're all on or all off. What we want to know in this ensemble    
25:06    
is what is the pattern of on and off over time.    
25:12    
So let's say we measure away. So, we'll go for 100 time points.    
25:17    
And we'll say that it's uh 40 on and 60 off.    
25:27    
60 off. And what we want to know is not like if it's 100% on or 100% off. What    
25:32    
we want to know is what is the variation here. So if we have 50 on and 50 off,    
25:40    
that's the maximum amount of variation over that time interval. So it's on and off like basically at random. If we have    
25:48    
40 times on and 60 times off, that means that it's off more than it's on.    
25:55    
And that means that there's less variety in terms of it being switched. So that I    
26:00    
mean that's basically how this works. And then of course if you go from like if you're    
26:06    
100 is like zero on and and 100 off that means there's no variety at all. That    
26:12    
this is totally you know that we know the that there's absolutely no information in this in this light or in    
26:19    
this point because it's always on. So we can compress that information and ignore it. And what we want to know is    
26:26    
basically in this array, how many of these go on, how many of these go off in their frequency.    
26:33    
So if we go back to our equation, what we're going to do is we're going to plug in pi.    
26:56    
If we go back to our equation here, this frequency is going to plug into pi. So    
27:02    
we plug uh 40 and 60 into pi. And I guess it could be like 04 or 6 depending    
27:09    
on how we calculate it. I don't know maybe it's actually 08 because we have the divide 40 into 60 depending how we    
27:16    
calculate this uh probability. And then we take the log of that    
27:22    
probability. So we normalize it and then we multiply it by that same probability    
27:27    
to it's a normalization procedure. And then for all these lights we want to know the same information. So that's    
27:34    
where the summation comes in. Every light we do the same thing. And then we get our h value. And as it turns out we    
27:40    
need this negative to normalize things. So that's where we get this. And then of course we get our information. So our    
27:46    
information is here h and in Shannon's view you know h is sort    
27:53    
of he called h entropy.    
27:58    
All right. And so this is going to be problematic perhaps    
28:04    
because we're not, you know, if you think about like thermodynamic entropy, like if I have a cup of coffee on a    
28:10    
table and it's hot and then I leave it there for like 6 hours, it becomes cold    
28:16    
and it said that the the that heat is lost through this process of entropy. So    
28:23    
heat escapes and entropy happens and that's But that's not necessarily what    
28:29    
we're describing here. So why does he call it entropy? Uh well, there's a story behind that,    
28:36    
which is that he basically chose that name because it was catchy and he could    
28:43    
win debates using that name. It sounded impressive. But a better answer to that is that um    
28:50    
sort of the apocryphal story. The better answer is first of all you can because of this ensemble nature you can    
28:57    
calculate things like hm max h min you can actually get more    
29:02    
information out of this um ent this measure h and it gives you this sort of    
29:11    
property of calculating an ensemble of states or evaluating an ensemble of    
29:17    
states. Of course the other answer is is because there is actually an equation for    
29:24    
thermodynamic entropy and it is if I can remember    
29:32    
memory here. Oh wait a minute    
29:44    
something like this. If I translate it into something analogous to H, it's S. And    
29:51    
then you have this constant. And then you have the the natural transform and    
29:57    
then this probability. And what you're doing here is you're calculating this as an ensemble of microates.    
30:05    
So the idea is that in energetics, you have molecules. They're all in these    
30:10    
different microates. you're finding the probability of any one set of states. Um    
30:17    
so you know you have many any ensemble of molecules of the molecules themselves    
30:23    
can be in different states that evolve over time and you want to calculate those out and you get that and then you    
30:29    
have this energetic constant K which is um Boltzman's constant and then you have    
30:35    
S and so S and H actually are semi-related    
30:42    
right um I have a video on this on the YouTube channel where I go go over some    
30:47    
of these different equations. I go over um thermodynamic entropy. I go over um    
30:54    
Shannon entropy as some people call it and kind of how they're related. Now,    
30:59    
they're not related necessarily directly, but they have the same structure. They have the same sort of    
31:05    
properties and they're both dealing with these ensembles. So that was a long discussion on um    
31:13    
Claude Shannon and and how this is sort of he's relevant to to this area. And    
31:19    
then Warren Weaver was a co-author on that book and yeah I think he wrote the forward but Warren Weaver was a science    
31:25    
communicator at the time. So he did a lot of stuff with you know kind of protocomplexity theory. So like a and    
31:33    
you know he was interested in cybernetics and sort of how that serves as protocomplexity theory in a lot of    
31:40    
ways. So this paper is done by Warren Weaver who talks about science and    
31:45    
complexity and um so let's see let's get to some meaty things in this paper. The first    
31:53    
statement is how we can how can we get a view of the function that science should have in the developing future of man.    
32:00    
That's very 1940s. Um, how can we appreciate what science    
32:05    
really is and equally important what science is not? It is of course possible to discuss the nature of science in    
32:12    
general philosophical terms. Um, and let us as a very realistic    
32:20    
politician used to say let's look at let us look at the record neglecting the older history of science.    
32:26    
um we shall go back only three and a half centuries and take a broad view that tries to see the main features and    
32:32    
omits minor details. Let's begin with the physical sciences rather than the biological for the place of life    
32:39    
sciences in the descriptive scheme will gradually become evident.    
32:44    
So this is where we talk about he starts to talk about simplicity and um    
32:50    
reductionism and things like that. So uh in the 17th 18th and 19th    
32:56    
centuries the physical sciences learned variables which brought us the telephone    
33:02    
and the radio, the automobile and the airplane. Um the concurrent progress in    
33:07    
biology and medicine medicine were also impressive but that was of a different character.    
33:14    
The significant problems of living organisms are seldom those in which one can rigidly maintain constant all but    
33:20    
two variables. Living things are more likely to present situations in which half a dozen or even    
33:27    
several dozen quantities were all varying simultaneously and unsuttly in interconnected ways.    
33:34    
Often they present situations in which the essentially important quantities are either non-quantitative or have at any    
33:41    
rate eluded identification or measurement up to the moment. So what    
33:46    
he's getting at here is that I mean he's making this sort of distinction between    
33:52    
physics and biology. And physics the idea is that you can do these controlled    
33:58    
experiments where you can isolate variables. So you can have like the you can measure    
34:05    
a single variable and that single variable can tell you something about a system and sometimes that is lawike. So    
34:12    
it gives you this thing that you can just say okay this is an indicator of    
34:18    
this other thing and if I manipulate it in certain ways it can it almost you    
34:23    
know has this sort of causal linearity with the other thing. So, you    
34:29    
know, I can make create laws that apply universally. That's the idea. And so,    
34:37    
that allows us to develop technologies based on those manipulating single    
34:43    
variables or multiple variables. And we know causally what will happen. It's very easy to understand that in biology    
34:52    
and medicine. However, what he's saying is that there are a lot of different variables that interact. There are a lot    
34:59    
of different variables that have to be uh that get modified in different ways in some process. So like if you're    
35:06    
looking at a physiological process or some process of life, you know, you    
35:11    
can't just manipulate one variable and get a strong effect on the other end. And then that's something that you can    
35:18    
say is universal law. And so this is, you know, again, um,    
35:24    
just a broad stroke of the history of science. I don't think necessarily that, you know, that it applies in all cases,    
35:32    
but that's the the sort of a comparison he's making. And so    
35:39    
um he gets into this issue of how biology up to about 1900 was about what    
35:46    
people like to call stamp collecting which is where you do collection of data, description, classification    
35:54    
and observation of concurrent or correlated effects.    
35:59    
So you know in physics you can have like this and of course he's not talking    
36:04    
about quantum physics here so much or other types of uh nonlinear physics but    
36:10    
he is talking about sort of basic physics and how you can have the sort of    
36:17    
the causality comes more easily in these kinds of systems as opposed to in    
36:23    
biology and medicine. I'm not quite sure I agree with this. I think it's maybe    
36:28    
that you know we don't we didn't have the tools in biology and medicine    
36:35    
um and you know we had sort of physics evolve with mathematics more closely I I    
36:42    
don't know I mean like this is again something you would be able to discuss in the group here    
36:49    
so to sum up physical science before 1900 was largely concerned with two variable problems of simplicity whereas    
36:56    
life sciences which these problems of simplicity are often not so significant have not yet    
37:03    
become highly quantitative or analytical in character. Again, this this changed    
37:08    
over the last uh 70 years or so since this paper was    
37:14    
published, but this is the sort of the view that I think a lot of people have had up until very recently.    
37:22    
So, he gets into problems of disorganized complexity. So um he brings up Josiah Willard Gibbs    
37:29    
who talked also about thermodynamic entropy. Um there's also a quantitative    
37:34    
measure called Gibbs entropy as um you know as a way to kind of deal    
37:40    
with um you know this is sort of where we're going from like these    
37:47    
predictable quantities to sort of nonlinear physics because we're starting to deal with um dynamical systems and    
37:54    
we're starting to deal with sort of the foundations of dealing with the evolution of physical    
38:00    
systems. So, um, you know, that's that's kind of where we're getting into disorganized complexity. So, you    
38:07    
remember that typology I showed you before I got into the paper. We have these three different categories and you    
38:16    
know, this is where we're getting into those latter categories. Um    
38:23    
so if we look at sort of what physics has done    
38:29    
you know in in its history rather than study problems which involve two variables or most three or four some    
38:37    
imaginative minds went to the other extreme and said let us develop analytical methods which can deal with    
38:43    
two billion variables. So this sounds kind of familiar. This sounds like what we're doing in machine learning and deep    
38:51    
learning where we, you know, we could do uh data analysis on two or three    
38:56    
variables at once. But another way to go is to build like a generative model or a    
39:03    
discriminate model, a discriminative model that's of high dimensionality and    
39:09    
let's see if we can find patterns in that or you know find some sort of causality in that. So we go from like    
39:17    
the world of one and two maybe up to four variables and we go up to different    
39:22    
types of like you know very large or highdimensionality methods.    
39:29    
That is to say the physical scientists with the mathematicians often in the vanguard develop powerful techniques of    
39:36    
probability theory and of statistical mechanics to deal with what may be called problems of disorganized    
39:42    
complexity. So going back to our equation, this is sort of the foundation of statistical mechanics. This is    
39:48    
Boltzman entropy and the idea of statistical mechanics is to deal with    
39:54    
sort of these ensembles and look at their evolution over time. And the idea is that entropy is where you go from a    
40:01    
very high amount or high degree of variation and variety in that    
40:07    
thermodynamic ensemble to a very low level of variety. So things settle down,    
40:14    
you know, energy excites my cup of coffee and makes it hot. Uh when you lose energy, the the molecules settle    
40:20    
down into a a state of coolness. So this is where, you know, um we get this sort    
40:27    
of connection with the mathematics. And of course, that's just one small example of    
40:33    
the mathematics. we get all sorts of different ways we can calculate large systems with a large    
40:40    
number of variables. So that's you know we're using    
40:46    
statistical mechanics we're using probability theory to deal with things called disorganized complexity. And of    
40:51    
course, this was a 1948, so we would have to wait a couple more decades to    
40:56    
get sort of the dynamical systems treatment of disorganized complexity, which led us to chaos theory and sort of    
41:03    
this, you know, some of these other um categories of complexity that exist. So,    
41:11    
you know, this is again sort of setting the table for complexity theory.    
41:18    
Um and so the classical dynamics of the 19th century was well suited for    
41:24    
analyzing and predicting the notion or the motion of a single ivory ball as it    
41:29    
moves about on a billiard table. So this is the billiard's model of physics where    
41:34    
if I have, you know, a a Q ball, I can put it on the table and I can hit the Q    
41:41    
ball and it hits uh another ball in play and then, you know, might hit other    
41:46    
balls and those balls uh bounce off the edges of the pool table and might go    
41:51    
into a uh might go into a pocket. And then you can actually perhaps predict    
41:58    
the dynamics of that billiard table from the sort of the initial striking of the    
42:04    
Q ball to the motion of that Q ball, how it strikes the other balls and so forth.    
42:09    
So you could predict the dynamics of a pool table and it's you know classical    
42:14    
dynamics. Uh there's nothing uh really stochastic about it. Might there might    
42:21    
be you know imperfections in the surface of the pool table. There might be imperfections in the balls. There might    
42:28    
be, you know, differences in how different people hit the Q ball.    
42:33    
And that becomes important because, you know, in in the classical dynamics model, we don't care about those things.    
42:39    
We just care about sort of um the equations of motion and maybe entropy    
42:44    
and that's it. But then once we start adding in entropy, we start adding in these things that are sort of um    
42:52    
contribute to the net dynamics. Well, by that I mean like you know you have this perfect model of sort of the    
43:00    
equations of motion but then there are things that impact that and so you start    
43:05    
adding in things like entropy um uh things like uh individual    
43:12    
differences of the pool player uh things like the surface of the table things    
43:17    
like air pressure. And some of those things are play a very small role, but they're cumulative and they can add up.    
43:26    
So he brings up this idea of the billiards analogy where you can actually    
43:31    
make perfect predictions of a billiard billiard's play by looking at the    
43:37    
equations of motion. Um, one can but with a surprising increase in difficulty analyze the    
43:44    
motion of two or even three balls on a billiard table. There has been in fact considerable study of the mechanics of    
43:50    
the standard game of billiards. But as soon as one tries to analyze the motion of 10 or 15 balls on the table at    
43:57    
once as in pool, the problem becomes unmanageable. Not because there is any    
44:02    
theoretical difficulty, but just because the actual labor of dealing in specific    
44:07    
detail with so many variables turns out to be impractical. So this is interesting because this actually    
44:14    
suggests that not only do you have this issue of sort of the net dynamics but    
44:20    
you also have this issue of computation and that is like you know and again this is in 1948    
44:27    
but you don't have the computational power to necessarily analyze every ball    
44:33    
in the billiards table. You could only analyze two or three. And you have to analyze, of course, the equations of    
44:39    
motion for the entire game of billiards. So, you can't analyze every ball, at    
44:45    
least by the computational standards of 1948. Now this is where we get into the modern    
44:51    
sort of world of supercomputers. Uh the supercomputers we have today and even    
44:58    
like predictive machine learning models where we could feed a huge amount of data into the into the um the model not    
45:05    
just the equations of motion and maybe predict what those    
45:11    
trajectories would look like. So it's an interesting kind of point of computation    
45:17    
here where we have this uh this sort of limit that might not hold anyone.    
45:25    
So but he goes on imagine however a large billiard table with millions of balls rolling over its surface colliding    
45:32    
with one another and the side rails. The great surprise is that the problem now becomes easier for the methods of    
45:38    
statistical mechanics are applicable. So now we can use different techniques. We don't have to just use the equations of    
45:44    
motion. We can use statistical mechanics as a theoretical tool and we can say we    
45:50    
can model this as an ensemble instead of just tracking each ball to be sure the    
45:55    
detailed history of one special ball cannot be traced but certain important questions can be answered with useful    
46:01    
prediction. So some of those questions are on the average how many balls per second hit a    
46:08    
given stretch of rail or on the average how far does a ball    
46:14    
move before it's hit by some other ball or on the average how many impacts per    
46:21    
second does a ball experience? So again and notice that there are three words at    
46:26    
the beginning of each of those questions on the average. So what we do in in both information    
46:33    
entropy and in thermodynamic entropy is we're interested in this ensemble. We're    
46:39    
interested in this group of things and we're interested in either summing them    
46:45    
or you know calculating sort of the log transform of them and then you know    
46:50    
using a physical uh constant to look at the state overall state of these things.    
46:57    
So we're always using uh sort of an average of the ensemble or a summary of the ensemble to get an answer.    
47:06    
We're not interested in the individual behavior of these things although that can be important as well but we're    
47:11    
interested in the overall summary. So like if you wanted to measure say for example the state of a pool table the    
47:18    
state of a pool table would be where you have a pool table    
47:24    
and you have the pockets here. these pockets.    
47:34    
I'm just trying to kind of remember what a pool table looks like. And then you have your Q ball, of course, and you    
47:41    
have your other balls scattered about the table. And what you're interested in isn't like a single strike of this ball    
47:49    
and then there's a trajectory here or, you know, might hit this ball and this ball goes here. You're interested    
47:56    
in the state of all of these balls simultaneously. And then what is the mean behavior of    
48:02    
these balls? So the mean behavior of the balls is eventually they all end up in a pocket. And you can actually get the    
48:09    
mean behavior from the set of trajectories that happen every time you take your Q ball and you hit the other    
48:15    
balls and they end up in the pockets eventually. What is the mean behavior over time of that? And then that    
48:23    
actually can also give us information about that system about the you know    
48:28    
playing the game pool. So it's a different type of prediction different type of information.    
48:36    
Okay. But this is interesting because you're dealing with either individual cases and sometimes individual variation    
48:44    
versus averages of the variety. So you're doing maybe with individual like    
48:50    
distinct varieties of things versus this overall variety.    
48:56    
Okay. Earlier it was stated that the new statistical methods were applicable to the problems of disorganized complexity.    
49:03    
So how does the word disorganized apply to the large billiard table with the many balls?    
49:09    
So it applies because the methods of statistical mechanics are valid only when the balls are distributed and their    
49:16    
positions and motions in a helter skelter that is to say disorganized way.    
49:22    
So again if we go back to our pool table the pool table often you know we start off with our balls in sort of this    
49:29    
they're racked in this triangular shape and then the cq ball hits that and    
49:35    
distributes those balls all over the table. Eventually, you you keep hitting them until they get into the pockets of    
49:42    
the corners. But, you know, you so you go from this sort of ordered state where you have a    
49:50    
pool table and that pool table, you have the balls that are racked.    
49:57    
Let's put this up here. So, you rack the balls up here. They're all kind of in this.    
50:05    
And then you have the pull the the Q ball. You hit those. Those break up    
50:11    
break in different directions, right? You break the    
50:16    
the group of balls and then they go off into different directions and there's like a lot of heterogeneity in how they    
50:23    
kind of move and how they kind of distribute themselves and disperse and then they end up in their homes which is    
50:30    
minimal entropy because if they're in the pockets, we know exactly where they are. So we just need to find you know    
50:37    
how many balls are in each pocket and we can describe the entire system. So pool is this really interesting    
50:43    
system where we go from or you know order    
50:51    
total order to disorder or partial disorder    
51:00    
to order and the order of course is not total order. So this is like I guess    
51:07    
initial order and then we go to partial disorder    
51:13    
because it's not entirely disordered. I mean they're not you know spread out with    
51:20    
maximum sort of to maximum randomness and then we go to the final order or    
51:27    
maybe the entropic order which means that it's like they're in    
51:34    
the they're in their destination. There's you know limited var there's variation but there's limited variation    
51:41    
and it stays there. it's not going to pop back out of the pocket and you know so it's an interesting system    
51:48    
and so again this has uh parallels with complex with complexity theory with    
51:54    
chaos theory and so forth. So um    
52:00    
let's see uh for example the statistical methods would not apply if someone were    
52:06    
to arrange the balls in a row parallel to one side of the rail with a table and then start them all moving in precisely    
52:13    
parallel paths perpendicular to the row in which they stand. Then the balls    
52:18    
would never collide with each other or would with with two of the rails and one would not have a situation of    
52:24    
disorganized complexity. So, if you had a way to sort of move the    
52:30    
balls in a very ordered fashion to their pockets, if you like line you had the balls in    
52:36    
their rack and then you broke the rack and you had a way to like line them all up on the edges and then put them in the    
52:42    
pockets, that would be not uh disorganized complexity. That would be    
52:48    
order just kind of being rearranged. From this illustration, it is clear what    
52:54    
is meant by the problem of disorganized complexity. It is a problem in which the number of variables is very large and    
53:01    
one in which each of the many variables has a behavior which is individually erratic and perhaps totally unknown.    
53:10    
However, in spite of this unknown behavior of all the individual variables, the system as a whole possess    
53:18    
a certain orderly and analyzable average properties. So again, our trajectories    
53:24    
are in unique. They're individual. They're, you know, they have their own    
53:29    
sort of way of getting to the pocket. But if we describe this pool table as an average then we can see this pattern of    
53:37    
moving to the pockets it just that you know it's at maybe a certain average rate for the ensemble and then we could    
53:45    
analyze a pool game like that. We could analyze a pool game in two ways. We could have a pool game that's analyzed    
53:51    
by looking at the player hitting individual balls getting into the pocket    
53:56    
looking at you know how easily they they kind of do that. And then you think, well, there are all these variables that    
54:02    
are intervening and, you know, it's so it's hard to really average across the    
54:08    
balls because, you know, they're diff different distances to the pocket and    
54:13    
there's, you know, different things going on on the table. There are differences in the player and and it    
54:18    
just makes it unwieldy. The other way to predict it is by just taking the ensemble, taking its average    
54:25    
and then describing the average state of the game and saying, okay, if this player does this thing and they play on    
54:31    
this table, the the ensemble average uh varies by a certain amount. And then we    
54:37    
can say, okay, well, we don't really care about the individual trajectories. We care about the outcome of the game.    
54:44    
So we can become more efficient at our game of pool by maybe changing some uh    
54:49    
strategies that we use and you know overall it should help us be better but it not in every case.    
55:00    
So you know he's kind of getting into this disorganized complexity idea and how you're dealing with complex systems    
55:07    
as a manner of like uh statistical analysis. You can deal with individual    
55:14    
variables. You can deal with individual cases and then average those you know    
55:19    
across every case and you know take a mean and a standard deviation    
55:25    
and say some things about maybe statistical significance. Or you can use    
55:30    
this ensemble approach where you're just analyzing the entire system on its average on its mean level sort of mean    
55:37    
field model and then you're saying things about the average behavior and then if you know individuals deviate    
55:44    
from that average behavior then we at least we have a baseline for how they're supposed to behave.    
55:51    
So you know neither one is ideal but I think the uh ensemble approach maybe it    
55:57    
what he's saying is that it's better for a problem like analyzing pool.    
56:02    
Okay. Um a wide range of experience comes under the label of disorganized complexity. The method applies with    
56:09    
increasing precision when the number of variables increases. It applies with entirely useful    
56:15    
precision to the experience of a large telephone exchange and predicting the average frequency of calls, the    
56:22    
probability of overlapping calls of the same number, etc. It makes possible the financial    
56:29    
stability of a life insurance company. Although the company can have no knowledge whatsoever concerning the    
56:35    
approaching death of any one individual, has dependable knowledge on the average frequency with which deaths occur. So    
56:43    
when um an actuarial table was built, they kind of take the age and they    
56:49    
calculate out the um you know the average likelihood or average    
56:55    
probability of someone dying at that age. Now someone like say who's 80 years    
57:00    
old may be very energetic and healthy. They may be very unhealthy but the    
57:07    
average tells them what to sort of charge them. So in the aggregate they can I guess make money off of those    
57:15    
policies. So they're going to lose money on some 80 year olds are going to gain money on other 80-year-olds and it's    
57:22    
just a matter of like playing the odds on that. I know that doesn't sound very    
57:28    
sympathetic but it's that's the way that insurance and actuarial science works.    
57:33    
So um that's but they're again in that case they're using this ensemble    
57:39    
approach. Okay. So then there's this problems of organized    
57:46    
complexity. So um this problem of disorganized    
57:52    
complexity which is an advance over the earlier two variable methods leaves a    
57:58    
great field untouched. when it's tempted to oversimplify and say that scientific methodology went    
58:04    
from one extreme to the other from two variables to an astronomical number and    
58:09    
left untouched a great middle region. So again with ensemble averages we can go    
58:15    
to like very large numbers of things and and calculate their average.    
58:20    
But of course that's not you know the more we average the more we kind of    
58:26    
assume like this sort of median behavior and for the more you know if we do this    
58:32    
for more and more objects in our ensemble we obscure a lot of variation a lot of    
58:38    
variety and so that can be bad if there's heterogeneity in your system    
58:43    
what do you do I mean you can't just say the average works all the time because it doesn't there are a lot of things    
58:49    
that deviate from the average. And if you have these clumps or clusters like we saw with organized complexity,    
58:56    
those clumps and clusters are just you're just averaging over those and you have this mush of information. So you    
59:02    
don't have the proper amount of information. So when we apply H prime and we apply,    
59:11    
you know, we we do our sort of summation of our ensemble,    
59:17    
we're kind of selecting our group. So sometimes our ensemble is very large and    
59:23    
there's a lot of structure in that ensemble, but we're not capturing it with the average because we're, you    
59:29    
know, getting the information for something that's larger than that group and we're washing it out. So I guess    
59:35    
that's kind of the point there is that, you know, we can oversimplify things and end up with just in we're in the same    
59:42    
boat as we would be if we were just using the two variable method.    
59:48    
So um the problems in the middle region in fact will often involve a considerable    
59:54    
number of variables. The really important characteristic of the problems of this middle region which science is    
1:00:00    
as yet little explored or conquered lies in the fact that these problems as contrasted with the disorganized    
1:00:07    
situations with which statistics can cope show the essential feature of    
1:00:12    
organization. And in fact one can refer to this grow group of problems as as of organized    
1:00:17    
complexity. So this is again this is where he gets into um    
1:00:25    
maybe some of the things about cause and about you know again with the    
1:00:30    
cyberneticists they had this idea of causality and they kind of ascribed some    
1:00:37    
sort of purpose or some sort of intentionality to causality in a way    
1:00:42    
that's very unsatisfying looking back at it. Um, so he gets into    
1:00:48    
this section here where he talks about what makes an evening primrose open when it does. Why does salt water fail to    
1:00:54    
satisfy thirst? Why can one particular genetic strain of microorganism synthesize within its miniature body    
1:01:01    
certain organic compounds that another strain of the same organism cannot manufacture?    
1:01:08    
And it just goes through all these things. And maybe these aren't very good questions. um like how does comp how do    
1:01:15    
complex protein molecules know how to reduplicate their pattern and is this an essential clue to the problem of    
1:01:21    
reproduction of living creatures. So again, these are things that maybe we want to know how they happen, not just    
1:01:28    
why they happen. And so again, we need to use statistical methods.    
1:01:34    
They are not problems of disorganized complexity. They have they're problems which involve dealing simultaneously    
1:01:40    
with a sizable number of factors which are interrelated and to an organic whole. They are all in the language here    
1:01:47    
proposed problems of organized complexity.    
1:01:54    
These problems in a wide range of similar problems in the biological, medical, psychological, economic, and    
1:02:00    
political sciences are just too complicated to yield the old 19th century techniques    
1:02:06    
which were so dramatically successful on two three or fouryear variable problems    
1:02:11    
or two three or four variable problems of simplicity. These new problems    
1:02:16    
moreover cannot be handled with the statistical techniques so effective in describing average behavior and problems    
1:02:23    
of disorganized complexity. So these new problems in the future of    
1:02:29    
the world depends on many of them require science to make a third grade advance. Okay, so this is where he's    
1:02:36    
going over the next advance and again we're looking at this from 1948.    
1:02:42    
So this was you know kind of the point at which maybe people started thinking about complexity theory and by the you    
1:02:50    
know from like actually in the 1980s there was a great run of chaos theory    
1:02:56    
where it was like a very popular thing as fashionable to think about things in that way and then it kind of receded    
1:03:04    
but you know this is where it's coming from is this need to understand these    
1:03:10    
sorts of problems And so I mean, you know, it's interesting. I don't know if anyone's thought of writing a retrospective paper    
1:03:17    
on this. Um, but this is like very much sounds    
1:03:23    
like a Peter Holm type paper where you know Peter Holm is the person who's written a lot of blog posts on sort of    
1:03:31    
critiquing the history of complexity theory and what what it accomplished and what it    
1:03:36    
didn't. And you know, this is kind of the idea where we can look back and see    
1:03:42    
people calling for this thing that happened and then the thing happened and it had failures and it made advances and    
1:03:48    
we can actually get a good sense of what that advance looked like as it unfolded.    
1:03:56    
So that being said, I think you know uh complexity theory can solve some of these problems, but we've seen with    
1:04:04    
complexity theory, especially with like network theory and even with dynamical systems that    
1:04:10    
they can solve some of these problems that are open in this paper, but they can also not solve those problems. I    
1:04:17    
think with networks, one of the big stumbling blocks was always causality. You know, you can look at things that    
1:04:22    
interact. You can build huge maps that show structure. They show you can get these    
1:04:29    
average statistics of, you know, clustering or, you know, you can do community detection, things like that.    
1:04:37    
And but you're still left with this fundamental problem of causality.    
1:04:42    
What causes what? And maybe the the lesson there is maybe things aren't as    
1:04:47    
simple as they appear to be. maybe things aren't as strictly, you know,    
1:04:54    
cause and effect as as we like to think. So with networks, we we look at a lot of    
1:04:59    
interactions. We look at like Affecting B and B affecting A and you know CDE E    
1:05:05    
and F affecting B and all of that. And maybe that's just the state of affairs.    
1:05:11    
Maybe there isn't, you know, maybe it's just a matter of representing that and then coming back to that problem with    
1:05:18    
say like different statistical techniques that tell us maybe make estimates    
1:05:23    
of how much like A is contributing to B, but also C    
1:05:29    
through F. So, you know, I think there's a lot here    
1:05:35    
that I I didn't attend the the group, but you know, he does get into a lot of    
1:05:42    
this sort of stuff. And then he gets into the um philosophy of science more generally,    
1:05:48    
looking about what science is and what science isn't. never really interested in that so much. But I do think yeah    
1:05:54    
like if you're thinking about uh problems of statistics, problems of    
1:06:00    
machine learning, problems of system science very generally and broadly you know these    
1:06:06    
have a lot of practical applications. Um and you know thinking about the different types of complexity that exist    
1:06:15    
in the world and how we represent these in statistical models. Um, that's that's    
1:06:20    
very exciting stuff to me. Anyways, so I don't know if we had any comments    
1:06:26    
or questions on that. All right, so that's um I think that's    
1:06:32    
all for that. I think that was it. I you know that was just kind of my take on that as well. I don't have any maybe    
1:06:39    
next week I'll talk more about like the origins of chaos theory. I think that's really interesting as well.    
1:06:46    
So, another thing from our Slack, this was posted by Hussein, and I think uh    
1:06:52    
Morgan commented on this. This is actually following up from the    
1:06:57    
stuff that Morgan was talking about last week with the workshop.    
1:07:03    
If you go back to last week's meeting, he talks about this workshop at Pit or in Pittsburgh where they're doing things    
1:07:09    
like bioprinting and and cell culture and all this and kind of putting together those pieces.    
1:07:16    
And this is a paper that is kind of related to that. I mean, they're doing things that with uh soft materials    
1:07:24    
and uh development, although this is embionic development. I don't know if    
1:07:29    
you know um this isn't exactly organoids but it's similar and then doing this in    
1:07:36    
the brain. So this is like very much this mine in vitro approach. Um    
1:07:43    
so yeah this is brain implantation of soft bio electronics via embryionic    
1:07:48    
development. So this is where um they're using putting together all these pieces    
1:07:54    
to build things for the brain. So    
1:08:00    
uh developing bio electronics capable of stably tracking brainwide single cell    
1:08:06    
millisecond resolve neural activity in the developing brain is critical for    
1:08:12    
advancing neuroscience and understanding neurodedevelopmental disorders. During    
1:08:17    
development the three-dimensional structure of the vertebrate brain arises from a two-dimensional neural plate.    
1:08:24    
These large morphological changes have previously posed a challenge for implantable bio electronics to reliably    
1:08:32    
track neural activity through brain development. So again you know in development you    
1:08:38    
have these changes happening in the brain. So it's not just a matter of um measuring like extent neurons in you    
1:08:46    
know fixed in space but you have this sort of these change large scale changes    
1:08:52    
in the morphology. So this is really kind of if you implant bio electronics, you have to account for these changes.    
1:08:59    
So if you want to do something like track neural activity from say uh the    
1:09:05    
neural plate structure to like the neural tube and then onto different brain structures, you know, you're going    
1:09:12    
to have to account for these kind of morphological changes. Here we introduce a tissue level soft    
1:09:20    
submicrometer thick mesh microelerode array that integrates in the embryionic    
1:09:26    
neural plate by leveraging the tissu's natural two-dimensional to three-dimensional    
1:09:32    
reconfiguration. As organogenesis progresses the mesh    
1:09:38    
deforms, stretches it and distributes throughout the brain seamlessly integrating with neural tissue. Amino    
1:09:45    
stating gene expression analysis and behavioral testing confirm no adverse    
1:09:51    
effects on brain development or function which is good if you want to measure    
1:09:56    
brain function in sight to but you don't want it contaminated by um dysfunction.    
1:10:03    
This embedded electrode array enables long-term stable mapping of how single neuron activity and population dynamics    
1:10:10    
emerge and evolve during brain development. And then they use axelottle as their    
1:10:16    
model. So it not only records neuronal electrical activity during regeneration    
1:10:22    
but also modulates the process through electrical stimulation. So uh they're using an axel autoto model    
1:10:29    
of development which is a common model in developmental biology being able to    
1:10:35    
take uh these implants put them into uh embryionic axelottals and then tracking    
1:10:42    
brain activity through development.    
1:10:47    
So this is a picture of sort of their model. Uh this is uh uh panel A where    
1:10:55    
they start with stage 15 and they start with the neural plate    
1:11:02    
and they implant these ribbons into the embryo.    
1:11:07    
Then stage 24 it's they're they remain in there as you get shape changes. Stage 26 you start to    
1:11:15    
get the beginnings of the tadpole stage. Stage 40, this is the tadpole stage. You    
1:11:20    
still have the implants in there. And then stage 46, you're getting into the    
1:11:26    
um into the more mature form of axelottle and the implants remain in    
1:11:32    
there. And you can see that like as the morphology changes, the implants are still in sort of the same place. Uh we    
1:11:40    
get these different types of uh dimensional threedimensional changes as well as uh shape changes and it    
1:11:47    
persists. uh then we have so this is in B sort of this three-dimensional cartoon where we    
1:11:54    
can see the three-dimensional aspects of the brain as it's uh differentiating so you have the neural plate in one B1 you    
1:12:02    
have the implanted ribbons on the top of the neural plate you have the misoderm here and the noticord here so you have    
1:12:08    
misoderm on either side the notacord here and the neural plate on top and    
1:12:14    
then of course the neural crest is where this neural plate invaginates.    
1:12:20    
So that means that these implanted ribbons have to move down into this narrow groove. So you have the noticord    
1:12:28    
here and the misoderm up here. And so everything folds down downward.    
1:12:36    
And so then the neural tube uh as it's folded here, it's completely folded. The    
1:12:43    
implants are embedded in here. You get the somites on these sides, the spinal    
1:12:48    
ganglen. So the brain is building around the neural the folded neural tube. The neural tube is closed and then the    
1:12:55    
neural tube closes and expands. And you can see the implants are still there with the surrounding tissues.    
1:13:03    
And then three shows the three-dimensional distribution of bio electronics. So as far as I know, they    
1:13:09    
don't like distribute themselves outward. They're just there. where the ribbons are put down in the early neural    
1:13:16    
plate stage and then they get embedded by just the movement of the embryo and so you get this sort of embedding uh but    
1:13:24    
they maintain a position relative to the things you want to measure. So if you want to measure things, if you want to    
1:13:30    
have measurement accuracy, those implants need to correspond to brain tissues.    
1:13:37    
And so they seem to be sort of, you know, they they seem to be consistent    
1:13:42    
with what becomes the forebrain and then the midbrain and then a little bit of the hindbrain. So you can see this is    
1:13:49    
the embryo brain here where you have the three layer brain and the uh because you    
1:13:56    
put the implants on the neural plate they persist here but they persist into these different regions of the brain and    
1:14:03    
then you have so you actually have an IO connector that's remains outside of the    
1:14:08    
developing brain and this on the right here is the sort of the more mature the    
1:14:14    
tadpole brain where you have the uh this is the hindb brain here, the midbrain    
1:14:23    
and the forbrain. The electrons mostly are situated in the forebrain and you have the IO connector sticking out.    
1:14:31    
Um then you have some physics here. They    
1:14:36    
measure the elastic modulus versus the molecular weight. Um so that gives you    
1:14:42    
some performance information. Then you have uh stress. So you have cyclic    
1:14:48    
loading stress versus strain. And that's that. Um and they just show this    
1:14:56    
throughout the length of the ribbon. Um J is for neural plate versus    
1:15:04    
uh different stages of development. So during implantation and development    
1:15:09    
where you get this um you know these electrodes have certain force on the    
1:15:15    
neural plate. So they have you know they want to be able to make sure that it's not exerting too much force. It's not    
1:15:21    
manipulating the the way the neurop plate develops but it's also stable enough so that it doesn't um shift as as    
1:15:30    
these embryionic movements are happening. And then K is stress on neural plate    
1:15:37    
versus time as well. So you have this other function here. And that's that's    
1:15:42    
basically you know kind of the validation and kind of explaining how this works. And then this next figure    
1:15:50    
here figure two are the fabrication of tissue level soft mesh electronics.    
1:15:56    
So you know this again is a picture of the um the tadpole u    
1:16:04    
axelottle. So you have sort of showing the anchor and the IO pads and how this    
1:16:12    
kind of fits into the neural the folded neural plate. Um this shows the neural crest and then    
1:16:19    
the situation of these uh electrodes relative to the neural crest here the    
1:16:26    
implanted ribbons and just showing this cross-section.    
1:16:32    
Uh this is the fabrication of the of these ribbons. So you start with a    
1:16:38    
silicon oxide wafer. You have the sacrificial layer. You have the spacers.    
1:16:43    
you put these electrodes in, you have, you know, so they're building up how    
1:16:49    
they're um fabricating this thing, showing the different components.    
1:16:55    
Uh this just shows a cross-section of the different components. I think this is um    
1:17:03    
yeah it's a it's electron microscopy of this in I    
1:17:09    
guess it's implanted at this point u but basically it's showing the different    
1:17:16    
layers as they exist in the electrode and then M shows    
1:17:23    
um yeah this is a photograph of the free    
1:17:29    
floating mesh special electrode array during stretching, bending and twisting tests. So if you're    
1:17:35    
moving with the neural tissue or you're moving with the embryionic tissue, you have to have a lot of flexible    
1:17:41    
properties to the material. As you can see, it's it's a composite material.    
1:17:46    
It's, you know, not naturally. I mean, it's it's not it's made to be flexible,    
1:17:52    
but it's not as flexible as the tissue. So, it has to be able to bend and    
1:17:57    
withstand a lot of uh stresses and strains and things like that. So, you    
1:18:02    
have the electrode, it can stretch, it can bend, it can twist. And they did this testing before they did the implant    
1:18:08    
so that they knew that it wouldn't break apart as the embryo was making its    
1:18:13    
movements. So um and then of course they have this electrical impedance    
1:18:18    
resistance testing where you have um measures of resistance and impedance and    
1:18:26    
force for displacement and then for over space and over days over time.    
1:18:35    
Um yeah and then this just shows the neural    
1:18:41    
plate and the neural tube you know as we move through development and kind of    
1:18:47    
isolating that out and showing this process. You can see here that you have the    
1:18:55    
implant at different stages of embryionic development    
1:19:00    
and there are things you know you can do staining where you can see um sort of the cells that are it's    
1:19:08    
contacting and other things like that. So you're using uh this red stain, you're using Dappy    
1:19:14    
and you're using this green channel to look at the different cells that it's contacting.    
1:19:25    
Okay. So, there's a lot of good information in    
1:19:30    
this paper, a lot of detailed work, um, you know, including the trace that you    
1:19:36    
get out of these electrodes. So, you're getting a lot of good information out of the brain. Um, this is a proof of    
1:19:44    
concept paper, so I'm not aware that they're testing any specific hypothesis, but they're showing sort of how, you    
1:19:52    
know, the bas the system basically works. Not sure how easy or hard it is to implement.    
1:20:00    
In this figure, they do actually have some interesting um results from kind of    
1:20:06    
amputation studies. So this is where they have the implant    
1:20:11    
and then they amputate the tail in this group. In this group it's a sham.    
1:20:17    
So they basically measure uh the firing rate of these neurons. They look at the    
1:20:24    
embryos with tail amputation or without tail amputation.    
1:20:29    
And so with tail amputation you get this after tail amputation in that group. You    
1:20:35    
get a much higher firing rate than the embryos without tail amputation. Which is interesting given what we know about    
1:20:43    
neuro regeneration especially in embryionic development or in in TED    
1:20:50    
development. And then this shows like in in principal components analysis    
1:20:57    
uh what states these are in before and after amputation. So    
1:21:04    
before amputation you're kind of like I guess let's see state 1 2 3 4 5 6 7 the    
1:21:11    
darker circles are the uh the states after amputation the lighter circles of    
1:21:17    
before amputation. So I guess before amputation are here and after amputation are exploring more of this PC space.    
1:21:25    
Um and that's consistent with this figure here.    
1:21:35    
All right. So, yeah, the they they talk about this a little bit in the results. Um, we use the cyborg axelato model to    
1:21:43    
investigate neuronal activity changes following injury. So, the reason they're doing this a tail amputation is a sort    
1:21:50    
of simulate injury specifically tail amputation and subsequent regeneration.    
1:21:57    
At stage 30, cyborg axelato embryos underwent tail amputation whereas the    
1:22:03    
sham group remained uninjured. Continuous recordings showed that    
1:22:08    
following amputation neuron firing rates increased significantly compared with    
1:22:14    
preamputation levels whereas sham embryo showed stable activity as we saw in that    
1:22:19    
figure. Tail amputation also alters neural population dynamics.    
1:22:25    
Post amputation neurons show hierocorrelated activity and factor    
1:22:30    
analysis revealed shifts in neuronal states with initial divergence followed    
1:22:36    
by partially re partial reversion. To test whether neural activity changes    
1:22:42    
in changes influence regeneration, we applied continuous external electrical    
1:22:47    
stimulation through brain embedded electrodes mimicking post amputation neural    
1:22:53    
activity patterns. Stimulated embryos showed significantly accelerated    
1:22:59    
regeneration rates compared with non-stimulation controls. By day four    
1:23:05    
though, differences diminished as regenerationally completed. So this activity is sort of a    
1:23:13    
consequence of a regeneration process and we know that you know regeneration    
1:23:19    
often involves electrical signals in different cells or signaling and so it's    
1:23:26    
interesting that in the nervous system of course you're going to have this    
1:23:31    
activity. Um usually, you know, it's like this once    
1:23:37    
you have amputation, it's usually the site of injury that's active and it, you    
1:23:43    
know, there's some remodeling that goes on. There's some differentiation of cells that happen so that you can have    
1:23:50    
cells instead of being differentiated, they become stemlike and they migrate    
1:23:56    
out and fill in the gap and do things like that. Um but it's interesting that    
1:24:03    
you know they're also I guess cells in the central nervous system participating in that process.    
1:24:12    
So that's an interesting finding and again they didn't do like these really specific hypotheses. They just did this    
1:24:19    
sort of to show how the system can be useful.    
1:24:26    
Okay. So why don't we move on here? Um this is an article from the transmitter    
1:24:34    
and um we've been talking about neuroi I think probably for most of this year    
1:24:40    
last year and some of the things that are happening in that community    
1:24:46    
and you know we also talked about sort of neuroi and embodiment or generally    
1:24:53    
this is an article from the transmitter uh by Bing Bruntton and John Tutill    
1:25:01    
titled breaking the jar why neuro AI needs embodiment. So the idea of the jar    
1:25:06    
is like basically the the old philosophical idea of the brain in a vat. So like you know there's this    
1:25:14    
thought experiment that says you know assume we had a brain in a vat. a brain    
1:25:19    
was disembodied from your body or you know from its context in in the body put    
1:25:27    
in a jar and if we just put the brain in a jar could we just get could we have    
1:25:32    
thought you know what would happen and so this is breaking the jar so a lot of    
1:25:39    
models of artificial intelligence and even neuroi they might involve sort of    
1:25:45    
some sort of biological inspiration But they also exist in this jar. It's like    
1:25:51    
the brain in the vat problem. And so the idea is that embodiment breaks us out of that jar and gives us something that is    
1:26:00    
you know bodyike. So I mean the idea is basically that it's if it's neurallike    
1:26:06    
it has to involve some sort of body. And so you know then then the question    
1:26:12    
is is what does embodiment look like? But that's maybe a different question, but maybe leading up to what they're    
1:26:18    
talking about here. So brain function is inexorably linked    
1:26:24    
or shaped by the body. Embracing this fact will benefit computational models    
1:26:29    
of real brain function as well as the design of artificial neural networks.    
1:26:35    
Okay, so they kind of talked about the Teenage Mutant Ninja Turtles to start things off.    
1:26:41    
Um indeed coordinating body movement is the ultimate point of brain function. So    
1:26:48    
really brain function is about coordinating body movement.    
1:26:53    
Um and and you know you might say well I thought the brain generated language or    
1:26:59    
I thought the brain predicted things. That may be true but there are linkages    
1:27:04    
between say language and movement language in the body. There are    
1:27:10    
connections between language production and the body obviously    
1:27:16    
and there is connection between sensory information and moving through the    
1:27:22    
environment and using sensory information to shape movement. So movement is always at sort    
1:27:28    
of the the core of why we have a brain or why our brains do what they do.    
1:27:35    
predictive aspect is sort of part and parcel of moving.    
1:27:41    
So it's interesting that you know when you reduce it to that and sort of the coordination of that    
1:27:48    
movement moving through the environment it becomes clear that we have to have an    
1:27:54    
embodied model of brain function. The brain is not connected to the    
1:27:59    
external world except through the body. It receives no sensory inputs except those transduced through sensory organs    
1:28:06    
and it can enact no consequences except their muscles and other actuators.    
1:28:12    
Thus, the biomechanical feature and constraints of the body are built into the function of the brain. How animals    
1:28:19    
move also determines how the gathering of sensory information.    
1:28:24    
Um embodiment then is a concept that the function of the brain is inexorably    
1:28:30    
shaped by the body. Um embodiment the embodiment lens is often neglected when neuroscientists    
1:28:36    
study specific brain subsystems particularly higher order cognitive functions.    
1:28:43    
But in the field of growing the growing field of neuroi embodiment is now garnering greater    
1:28:49    
attention. So um Anthony Zador in 2023 proposed an    
1:28:55    
embodied touring test uh which is this paper here    
1:29:01    
catalyzing next generation artificial intelligence through neuro AI. This is where they talk about the    
1:29:08    
embodied turning test which challenges AI animal models to interact with the    
1:29:13    
sensory motor world at skill levels akin to their living counterparts. uh when they talk about a turn test    
1:29:21    
um it shifts the focus of these capabilities from those capabilities of game playing and language that are    
1:29:27    
especially well-developed or uniquely human to those capabilities inherited from over 500 million years of    
1:29:34    
evolution. Uh building models that can pass the embodied turn test will provide a road    
1:29:40    
map for the next generation of AI. So they still didn't mention what the actual touring test was.    
1:29:48    
Um but basically the idea is that instead of focusing on performing well on games    
1:29:57    
and performing well on these sort of combinatorial logic problems that there    
1:30:03    
is some connection to sort of motor performance and things like that.    
1:30:10    
Okay. So you know some of the features of it is that animals engage their    
1:30:15    
environments. They move around their environments. They explore their environments and then    
1:30:21    
animals behave flexibly. So if you have you know you you need to    
1:30:26    
have as many inputs as possible to sort of enable flexibility    
1:30:33    
and then animals compute efficiently. So there's this uh energy aspect of the    
1:30:39    
brain. So biological brains use relatively little energy to produce the    
1:30:45    
kinds of behaviors that they do. And so these are all things that need to be incorporated into    
1:30:52    
um an embodied turn test and allow these artificial agents to perform at levels    
1:31:00    
similar to their counterparts in nature.    
1:31:09    
Okay. So people have thought about this at least um and so here we discuss three    
1:31:15    
key features of embodied intelligence that are characteristic of animal brains. The first is feedback, the    
1:31:22    
second is biomechanics and the third is modularity. We argue that embracing    
1:31:27    
these three features will benefit computational models of real brain function as well as the design of    
1:31:32    
artificial neural networks that move beyond large scale word salad generation to efficiently accomplish real world    
1:31:39    
tasks. Okay. So they talk about feedback    
1:31:45    
being a ubiquitous characteristic of biological neural networks. Feed forward models in which information    
1:31:53    
flows in only one direction, such as from the retinance of the lateral genicular nucleus to the primary visual    
1:31:59    
cortex are popular because they're easy to interpret.    
1:32:04    
But that's not usually the way processing works. A lot of times it    
1:32:10    
involves constant and multiscale feedback where you have fluctuating physical    
1:32:16    
environments, recurrent connections, interlin organs    
1:32:22    
and cells that modify themselves through gene regulatory networks.    
1:32:28    
So these are all kinds of things we have to take into account. Again, you know, we don't really make a statement about    
1:32:34    
how much of the variation they contribute to, but they're in nature and so we should replicate those.    
1:32:42    
Second, biomechanical features of each specific body are essential to understand the function of the neural    
1:32:48    
system within it. Consider for instance this video of a trout body undulates in    
1:32:55    
the current and then surges upstream towards a small rock. This is uh what appears to be a dextrous    
1:33:02    
natural behavior is in fact executed by a recently dead fish. So this behavior    
1:33:08    
requires no neural activity and arises entirely from the interaction between    
1:33:13    
the vortices shredding shedding from the rock and the biomechanics of the fish body.    
1:33:20    
So this is where you can actually replicate or I should say the movement    
1:33:25    
of the body occurs with or without neural activity. So if you observe a    
1:33:30    
trout moving upstream, it's maybe driven by external forces as    
1:33:37    
much as sort of intentional internal forces. And so this is kind of an example of    
1:33:43    
that. Uh but this is also speaks to the sort of mechanical or physical intelligence    
1:33:50    
which is where the body actually has it you know sort of restricts the dynamics    
1:33:56    
that are available to it but also can be driven sort of by external forces.    
1:34:02    
Another good example of this of course is the a passive dynamic walker which    
1:34:07    
you if you're familiar with robotics you know what this is. It's a a physical model of a walker of a bipeedal walker    
1:34:15    
where you have this robot that's or this this sort of inverted pendulum that has    
1:34:21    
feet and then you just push it along. You you can push it externally and the    
1:34:26    
thing will walk like a bipeedal organism and it will eventually stop moving but    
1:34:33    
you can put enough input energy into it to get it to move and locomote. And it's    
1:34:38    
very similar to stay awake, a human walking. And so that's, you know, again another    
1:34:45    
example of this where you don't need neural activity to drive this behavior,    
1:34:50    
but nevertheless, you get this movement behavior out of a mechanical or physical system.    
1:34:57    
So that's another point. Um, and then third, our brains are highly modular.    
1:35:02    
Even as we advocate for an integrative approach, there is undeniable value in deeply characterizing specific parts of    
1:35:09    
the brain, muscoskeleletal systems in isolation. But of course, these modules need to be    
1:35:15    
stitched together in a way that's functional and gives us the sort of whole brain activity.    
1:35:23    
Um, but of course, modularity isn't just about dividing things into specific    
1:35:28    
modules and then putting them together. Once you get to the uh systems level,    
1:35:35    
modular modularity or modules can be a source of bottlenecks. So in the retina, retinal ganglen cells    
1:35:43    
are the only cells that send outputs to the rest of the image forming visual system and motor control circuits all    
1:35:49    
converge onto the final common output of motor neurons that synapse onto muscles.    
1:35:55    
Such bottlenecks define modules making it possible to develop computational models of each module that nevertheless    
1:36:03    
interface with one another and from which emerges the holistic behavior of virtual animal.    
1:36:10    
Importantly, models of different subsystems can be made at different resolutions and learn from different    
1:36:16    
data. And so these taken together form this    
1:36:21    
embodied perspective. But there is still a chasm between the aspiration of studying embodied brain    
1:36:28    
and how to implement it in practice.    
1:36:33    
So uh let's see what makes the emerging zoo    
1:36:39    
of virtual animals distinct from the previous generations of biomechanical models is in their compatibility with    
1:36:46    
models of the brain. We can think of brain models as controllers that plan and execute behavior or responding to    
1:36:53    
sensory stimuli from the environment. Of course, there's this model    
1:37:00    
or Moko, but we've talked about Mojo, which is a physics engine that simulates    
1:37:06    
the biomechanics of skeletons, muscles, and tendons. This is uh based on like kind of    
1:37:14    
simulating robotic systems, but you can also use this for AI.    
1:37:20    
A Jack's accelerated implementation called Mojoko MJX now makes training whole body virtual animals tractable for    
1:37:27    
researchers with access to GPUs. Um and so this so we need a good    
1:37:34    
physical simulated environment. Mjoko is a    
1:37:39    
a candidate, but there may be other ways to do this. The prospect of developing a fully    
1:37:45    
integrated neuromchanical model is perhaps closest to fruition for the adult fruit drosophila. The recent    
1:37:53    
completion of comprehensive synaptic wiring diagrams known as connecttos of the fly brain and vententral nerve cord    
1:38:00    
mean it is now tractable to hook up computational models of neural dynamics at the resolution of cells and synapses    
1:38:07    
to whole animal biomechanics. Such embodied models open the door to encilico experiments that are currently    
1:38:13    
not feasible in real animals complementing existing genetics and    
1:38:19    
behavioral tools. So consider the sensory control of robust walking. For more than a century    
1:38:26    
of intense study, we know that nerve cord circuits generate rhythmic motor patterns autonomously. Yet when the    
1:38:33    
walking animal encounters a perturbation, such as uneven terrain, it must integrate feedback from sensory    
1:38:40    
neurons with feed forward commandments to adjust, recover, and maintain walking.    
1:38:47    
In civil experiments, it ask how neural dynamics of recurrent circuits coupled with biomechanical consequences and a    
1:38:54    
virtual walking fly complete with interactions with an unpredictable physical environment will help us    
1:39:01    
untangle these dual functions. Then of course they get into foundation    
1:39:07    
models of animal brains and behaviors um and how those can be maybe useful    
1:39:16    
uh using the principles of embodiment to build these foundation models.    
1:39:24    
So again this is a nice article because it kind of lays out this vision for embodied neuro AI. I don't think it's    
1:39:31    
anything that um people haven't thought of before. It's just kind of putting it in one place.    
1:39:40    
Um I think that's all for today. Um did we have anything we wanted to talk    
1:39:45    
about before we go or um not really related to what uh this    
1:39:52    
meet is but I think like a few weeks ago I spoke about this whole project that we have in our college. So yeah that has    
1:39:59    
started and we we'll have our bi-weekly meet starting soon. Okay. So once they start, I think I can    
1:40:05    
put those up I can bring those updates. Yeah, that would be great. I'm looking    
1:40:11    
forward to it.    
1:40:18    
Thank you. Yeah, no problem.    
1:40:26    
All right, I think that's it for today. Um, see you next week. Thank you.    
1:40:33    
Bye. Thank you. Bye.    
