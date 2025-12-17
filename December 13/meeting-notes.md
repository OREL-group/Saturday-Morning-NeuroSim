## Meeting Recording

[YouTube link](https://youtu.be/jB-OfM_hs2s)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115735691677674210)

## Feature Videos

[Tiny Neural Networks in Behavioral Science and Machine Learning](https://neuromatch.social/@OREL/115735691677674210)

## TRANSCRIPT
0:01   
All right, welcome to today's meeting. Um, I'm going to go over a few things.   
0:06   
Uh, hopefully you're finishing up your year in a good fashion. Um, we're going   
0:12   
to talk about our latest Slack posts. We're going to talk about the world of tiny neural networks. These are very   
0:19   
small neural networks that people are using to look at experimental data. And   
0:24   
in fact, there's a separate area of machine learning where they're using   
0:30   
very small network. They're trying to figure out the smallest network they can use to efficiently encode information   
0:38   
and this is of course for reasons where you know you want to use as few computational resources as possible and   
0:46   
then uh we have new active inference papers. So let's get to it.   
0:53   
So the first thing this is from Morgan. This is talking about the connected minds conference. This happened in   
0:59   
October uh this October 6th through the 8th at York University in Toronto. Uh   
1:06   
this is exploring the intersection of brains, machines and society.   
1:11   
Um you know it's very much like a wei robot type thing where it's uh cross-   
1:17   
hosted by Queens University in Ontario. Uh they have uh all sorts of things   
1:24   
going on at this. I don't know if this was ever on YouTube or whatever, but uh they had a number of interesting   
1:30   
sessions here. uh social robotics and health, mobility and accessibility,   
1:37   
applications and risks of large language models, ring computer interfaces in society, technologies for remote health   
1:44   
and embodiment, indigenous data sovereignty in the technosocial age and   
1:50   
social media, AI, mental health. So very good stuff at that event.   
1:56   
The second feature was uh posted by Hussein and this was uh this uh popular   
2:03   
article and then there's a paper attached to it. So this is called from crushed sugar cubes to exploded   
2:09   
ceramics. This universal law predicts how most objects will shatter. So it's   
2:14   
thinking about the physics of shattering and what they call shattering laws.   
2:19   
And so um the subtitle here is a new equation calculates how many fragments   
2:25   
of each size will be produced when an object breaks. The principle could help people prepare for rockfalls or other   
2:33   
real world scenarios. And so this is shattering of course this   
2:38   
uh lamp. And so a French physicist developed an equation to predict how things will shatter.   
2:45   
And I was surprised that we hadn't had that but I guess not. So, um, when a delicate object crashes   
2:52   
onto the floor, most people expect it to shatter into several pieces. What they might not know, however, is that the   
2:59   
size of these fragments, whether from a broken plate, mirror, or sugar cube seem   
3:04   
to follow a universal rule. So these are the shards and the shards actually follow a distribution which of course we   
3:12   
know from like power laws is a very um popular and if you're a critic of it   
3:17   
pernicious uh feature in physics and in complexity theory but uh this is you   
3:24   
know thinking about the physics of a whole thing that's breaking apart. So it's kind of like the opposite or   
3:29   
inverse of emergence. Researchers have long known that a   
3:36   
dropped or smashed object will break into a consistent ratio of fragment sizes. In other words, if you group the   
3:42   
splintered pieces by size and graph their distribution, most broken objects   
3:47   
would yield the same graph shape. Um now Emanuel uh Vermo a physicist at   
3:54   
IM Marseilles University in France uh has come up with an equation to describe this consistent pattern of fragmentation   
4:02   
which works across many materials. His study was published on November 26 in   
4:07   
the journal physical review letters which we'll get to in a moment. The simplicity and success of this   
4:14   
approach are striking, wrote Faren a physicist at the University of Deinine   
4:19   
in Hungary, who is not involved in the study in a physics magazine commentary about the new work. When studying   
4:26   
fragmentation, researchers usually look at either fine-cale mechanisms such as how cracks take shape or a broader   
4:34   
general principle. Miller M took the latter approach. They examine the most likely fragmenting   
4:40   
outcomes in situations with few physical constraints or a principle of maximal   
4:45   
randomness. Simply put, the most likely shattering pattern that will take place when an   
4:51   
object breaks is the one that maximizes disorder, resulting in the messiest,   
4:56   
most irregular sized pieces. The armo suggests in the study, but even maximal   
5:02   
randomness has some limits. It obeys the previously mentioned rule about the ratio of shattered pieces always   
5:10   
following the same pattern which Vermont and his colleagues reported in a 2015 study in the journal proceedings of the   
5:17   
Royal Societya A. Combining these two elements allowed Vietnam to figure out   
5:23   
an equation to predict how many fragments of each size will come from an object cracking open. He then tested how   
5:29   
the equation held up against data from previous shattering studies, including those with glass rods, dry spaghetti,   
5:38   
exploding ceramic tubes, liquid drops, and waves breaking in turbulent seas. He   
5:43   
also sized up the equation with data he previously collected and how individual sugar cubes splintered when dropping   
5:50   
objects on them from a different heights. That was a summer project of my   
5:56   
daughters. I did this a long time ago when my children were still young and then came back to the data because they   
6:02   
were illustrating my point. Well, that was a quote from this uh scientist.   
6:08   
The objects fragmented in accordance with the new equation. U the new work shows that statistical   
6:14   
regularities of fragmentation can emerge from a combination of maximum randomness   
6:20   
and kinematic constraints without reference to any microscopic mechanism. So it is a lot like emergence in that   
6:27   
sense. But again, it's the reverse of emergence. It's how things break apart rather than how things come together.   
6:36   
Still, the math doesn't work in all circumstances. In materials that are both springy and flowy, like silly putty, the cracks may   
6:43   
heal and close, preventing some pieces from forming. And in a jet of liquid breaking up into   
6:50   
droplets, the fragmentation process is too regular for the equation to be applied.   
6:56   
The universal law of shattering might be relevant for more than just predicting messes from human clumsiness. For   
7:02   
instance, uh tells the new scientist better understanding of objects break apart could help determine   
7:08   
energy costs of mining for ore which involves smashing rocks or aid in   
7:13   
preparing for rockfalls. So that is that um popular article.   
7:20   
This is the physical review letters paper fragmentations principle versus   
7:25   
mechanisms. So this is uh Emanuel Vermo   
7:32   
and uh this is the abstract. When it comes to understanding how a cohesive   
7:38   
object breaks up, there are two types of temptations. Either seek detailed mechanisms. So you   
7:45   
could have capillary instabilities for liquids, cracks, propagation and brittle   
7:50   
solids or rely on a general principle to infer the multiplicity of fragment   
7:57   
sizes. Here we show that an original conservation law coupled with a maximal   
8:02   
randomness principle provides new unifying predictions. We explain when this principle is likely   
8:09   
to apply and why the fragment size distribution is a power law. So this is   
8:14   
uh describing this as a power law uh which is equivalent to exponential   
8:21   
distribution in that case with exponent of beta which   
8:26   
is defined like this a function of the dimensionality of the breaking object D.   
8:31   
So this just describe this this exponent which is the exponential   
8:37   
part of the power law is uh a function of the dimensionality of the breaking   
8:42   
object. Examples including crushed and and   
8:48   
grinded brittle materials like solids, bars, plates, and shells   
8:54   
or cubes and spheroids, but also liquid drops and bubbles, exploding liquid   
8:59   
shells, plastic debris in the ocean, and remnants from the caveman industry,   
9:04   
which and some of the shrapnel from the stone tools that used to be. Uh discuss   
9:11   
the discussion is implemented by an original experiment. So this is uh   
9:20   
this is the article. Uh despite being of a trivial common   
9:26   
experience, the origin of the multiplicity of fragment sizes uh produced by a glass of accidentally   
9:33   
dropped on the floor and its many variations remains a fundamentally unanswered question. It concerns a vast   
9:40   
landscape of applications all involving the break up of cohesive objects ranging   
9:45   
from crushed or impacted solid bars, plates, rings, and shells or spheroids,   
9:53   
liquid fragments from impacted drops and exploding liquid shells to the formation   
9:59   
of bubbles under breaking waves and even the remnants from the caveman industry. In all cases, the fragments are broadly   
10:06   
distributed in size according to a decaying power law with an exponent beta, a notable function of the aspect   
10:12   
ratio or dimensionality d of the initial object. We invoke here a maximal randomness   
10:19   
principle the analog of Boltzman's kinetic theory of gases to describe the distribution of   
10:26   
fragment sizes which when applied to the appropriate function and coupled with an original conservation law provides new   
10:33   
unifying results. So we're going back to uh the theory of gases and Boltzman's   
10:40   
work on that. We call n dd the number of fragments in the size range in this   
10:46   
interval here form from an object of size r dismantled under maximal randomness conditions subject to some   
10:53   
constraints. So we have an object size of r. We're taking it apart and this is   
10:59   
maximally random and then it's subject to some constraints. So the random process then is constrained and you end   
11:07   
up with this structure because there are many microscopic factors influencing the formation of a   
11:14   
given fragment in an environment which in itself varies contaminantly with the   
11:20   
break of process. A deterministic description of n is out of reach. So we   
11:26   
can't like with emergence we can't describe like say if we're thinking about a self   
11:32   
assembly process of that sphere we can't think of that in a deterministic way   
11:38   
that is we can't think of every single step and have a deterministic model that   
11:43   
will predict every single step how large that step is and when that step will   
11:48   
occur. We can only use a stochastic model which is not going to give you a   
11:54   
prediction um in terms of something that's going to give you a microscopic   
11:59   
characterization. We have to rely on the macroscopic characterization of the system and you   
12:06   
know we just basically observe it until we either get the sphere assembled or in   
12:11   
this case break the sphere apart into its fragments. But precisely because of that   
12:17   
microscopic random nature, the size partition n is in a given experiment is likely   
12:23   
all among all those that are possible to be one with maximal probability. In systems where there are many degrees   
12:30   
of freedom and very few microscopic constraints at play and this is the case in gases or   
12:36   
turbulence. The statistics is readily obtained by computing the number of occurrences of a given micro state which   
12:43   
amounts to maximizing an entropy. So this is uh going back to statmech.   
12:50   
This is of course the sort of configurational space and then thinking about the mic the possible microates and   
12:59   
computing those occurrences. So we use n factorial arrangements per size class to   
13:05   
characterize this which means we're thinking about all permutations of something per size class. And so this   
13:13   
is this the statement here. Our principle amounts to maximizing this term here which is the integral of n log   
13:22   
n minus n plus constraints and then this dd term at the end. So this is s this is   
13:30   
our mic number of micro states here. We need now to make the constraints explicit. So this part is just   
13:37   
constraints which isn't helpful. We need to know what the constraints are and how they act upon the system. A conservation   
13:45   
law for fragmenting objects first discovered in this reference 12   
13:51   
is the key to the present discussion. So there is a conservation law for fragmenting objects which describes the   
13:58   
energetics. Um let a d-dimensional object of volume rd dismantle into a collection of   
14:04   
fragments with size uh dxt at position x at time t. So you have this uh set of   
14:11   
fragments that have a position in space and then this time uh this describes a process when it is   
14:19   
over fragment sizes d are independent of t. So we can have these fragment sizes happening at any given time. We just end   
14:26   
up with the fragments of certain certain size distributions at the end of the process.   
14:32   
These are distributed according to n. We may define a density in the breaking object extensive to the local fragment   
14:40   
volume. And this equation here describes this fragment volume a globally conserved   
14:47   
field moving at velocity uxt as the fragments separate.   
14:53   
This density obeys the conservation equation singling out the field divergence   
14:59   
naval u. This diver that divergence of order R over R is usually small since   
15:05   
cracks in a macroscopic solid material propagate at the velocity of sound and   
15:11   
involve minute microscopic displacements so that fragments are formed before they   
15:16   
separate appreciably. And then we have this term here. These different parts of   
15:21   
the term are summed over the whole volume of the breaking object and is conserved during the internal   
15:27   
arrangements leading to its fragmentation. Conversely, among the many routes a branching cracks may take, those   
15:34   
permitted by this conservation law must leave this uh original term unchanged.   
15:41   
We first consider the consequences of this constraint only with a beta with beta lrange multiplier. We thus maximize   
15:49   
s in equation one implying that n uh the similarity to d   
15:56   
to the power law that we have d exponent b beta a power law reflecting the   
16:01   
empirical observations reported above. So basically we're summarizing the   
16:07   
description of this process with a function and then we're looking at the   
16:12   
power law of that. uh we choose a rigid representation involving the initial   
16:18   
size of the object R to formulate the conservation of mass more precisely the   
16:24   
conservation of volume accounting for the empirical observation that fragments tend to   
16:30   
the volume of the sphere of diameter D is d over 2D   
16:36   
um in dimension D. So that this term we yield this term which solves for beta in   
16:43   
a closed form. The formula above which solely comes from the kinematic constraint on equa in   
16:50   
equation two which is up here   
16:56   
agrees well in trend and order magnitude with the measured ones for solid bars 1D   
17:03   
plates and shells 2D or cubes spheroids but also for liquid drops and bubbles in   
17:09   
3D. This is all shown in figure one. Some original data in this figure are   
17:14   
given in mass and or cumulative distributions. Uh   
17:21   
we have beta of approximately 1.3 for one-dimensional brittle glass bars or   
17:27   
spaghetti um either dropped on a rigid floor or impacted longitudinally by a heavy mass.   
17:35   
The beta value of around 2.4 is a good average for dropped 2D brittle plates   
17:41   
and exploded ceramic tubes as well as for plastic fragments   
17:46   
collected in the ocean. Most of these come from the degradation of thin packaging. So things like bottles and   
17:52   
envelopes and therefore pertain to the two-dimensional paradigm. Flakes from stone tools used as hammers   
17:59   
by chimpanzees and possibly early hominins are produced via 2D expansion   
18:05   
process as the tool impacts and falls into this two-dimensional category.   
18:11   
Rocks progressively breaking into dense granular flows under a sustained shear and a gap of first display in a   
18:17   
two-dimensional signature and finally a three-dimensional exponent when introparticle stresses such as grinding   
18:24   
have become isotropic. As for fragmentation in liquids, we much   
18:29   
must mention plunging breaking waves which enter air pockets below the ocean surface breaking up in the transient   
18:36   
turbio agitation of the water. The size distribution of the resulting bubbles   
18:42   
have have been interpreted along several different lines, notably one invoking a kalurov type of turbulence below the   
18:49   
wave leading to uh beta values uh uh equaling 10 over3 a value not   
18:56   
incompatible with recent data. The 3D present paradigm suggests that beta of   
19:01   
around 3.5 which is not incompatible either um but has an essentially different   
19:08   
origin assuming randomness not necessarily turbulence. Likewise a good fit with beta of around   
19:15   
3.5 is obtained for the fragments of a liquid drop in trainment into a pool of   
19:20   
admissible liquid as it impacts the surface of the pool at large Weber numbers.   
19:27   
A standard sugar cube made of compacted dried saccharos crystals shattered into   
19:32   
pieces and crushed on the rigid floor by a heavy mass falling by its own weight.   
19:38   
And this offers an ideal illustration of 3D fragmentation. As figure two shows, fragments issuing   
19:44   
from a single cube are more numerous and smaller for a larger impact velocity,   
19:50   
but their size distribution is always well fitted by a power law, which we saw in equation two, with a beta value of   
19:57   
around 3.5. The interest in this experiment lies not   
20:04   
so much in the fact that it's confirming known things but because it invites one to consider another principle the one of   
20:10   
energy conservation. The energy of the impactor is finite. Um and as such we uh   
20:22   
the application of this principle is delicate in fragmentation since we know that equating the available mechanical   
20:28   
energy with the amount of created surface energy may lead to notorious mistakes of which we have several   
20:35   
examples of with liquids. Um the reason that there are so many forms of energy such as kinetic, sound,   
20:42   
light, heat and others and many sources of energy dissipation and fragmentation,   
20:48   
friction uh by viscosity or plastic deformations   
20:54   
um are kind of playing against this universal rule. Nothing guarantees in   
20:59   
general that the energy input will be exclusively converted into surface creation although most of it actually   
21:05   
does so in brittle materials. So material type and how energy is converted. So why don't we go over the   
21:12   
figures? So this is figure one. This is of course our power laws described here.   
21:17   
We have our beta exponents here. So we go from one to four and the beta   
21:24   
exponents beta from fragment size partition. uh this is the power law measured by   
21:30   
several authors and of the fragmentation of both solid and fluid objects of dimension D which is here. So we have   
21:36   
our one-dimensional cases here at one our two-dimensional cases here in red   
21:42   
and our threedimensional cases in black. So the onedimensional cases in blue they have this uh beta value of around 1 to   
21:50   
1.4. Um then you go to your two-dimensional cases where the beta value is around   
21:57   
1.8. 8 to 2.4 and then you have your threedimensional cases where the betas are 2.8 to almost   
22:05   
four. So you can see that there are these you know these are variable by the type of material by other factors that   
22:13   
we just talked about. Figure two is the fragment size distribution. So this   
22:19   
graph shows sort of uh this function PD and then D   
22:24   
over R. And so this is the size distribution and the uh size roughly. So this is just   
22:33   
showing in the inset the pattern of fragmentation. So you have some large   
22:39   
fragments and a lot of smaller fragments. And from that you can get a uh size distribution. So the size   
22:46   
distribution of course you have very few very large fragments. you have uh a   
22:52   
number of smaller fragments and a lot of other fragments that are smaller still.   
22:58   
So you have this distribution of their size and so that's what they're trying to characterize here. Uh they have this   
23:05   
for three different fragmentation patterns as you can see. Uh this first one has very large fragments, a couple   
23:12   
very large fragments and a lot of smaller fragments. the next one over in the middle that has   
23:19   
a a larger number of bigger fragments and a larger number of smaller fragments. And so you can see the   
23:27   
distribution is a little bit different there. And then the third one you have mostly smaller fragments uh with a much   
23:34   
less stark difference between the bigger fragments and the smaller fragments.   
23:40   
So this is fragment size distribution PD which is on the X- axis from the   
23:45   
shattering of a single sugar cube of size R. So this is a single sugar cube   
23:51   
shattered three times and you can see the distribution of these things. Um, this was a sugar cube lying on a rigid   
23:57   
floor crushed by a heavy mass, which is on the left, falling by its own weight   
24:03   
from a height h, crushed by a heavy mass of 0.4 kg, which   
24:11   
is m, and then falling by its own weight from a height h. So, this is like   
24:16   
something falling off a table under a sugar cube. The image width and the inserts is 15 cm. So this is a small   
24:24   
field debris field. Um left h equ= 10 cm. So the one on the left uh the height   
24:31   
is 10 cm. The image on the center is 50 cm and on the right is 150 cm. So he's   
24:38   
dropping this this mass from different heights. And so obviously this is going   
24:43   
to have a different impact energetically on the uh sugar cube and it's going to   
24:49   
affect how things shatter. So you see as you drop it from a higher and higher um   
24:58   
as you drop it from increasingly uh higher heights you get this uh more   
25:04   
sort of complete shattering I guess you could say. Uh you don't get as many large pieces. the number of large pieces   
25:12   
um it doesn't decrease the size of the largest fragments decreases but you do   
25:19   
get uh more sort of maybe a complete pulverization   
25:25   
by the time you get it uh the the uh dropping height at about 150 cm   
25:32   
in each case all fragments are larger than 0.04R 04R that's equal to 1 millm and deposited on   
25:39   
a dark support for analysis. So these are all sort of have a lower size limit   
25:45   
but not an upper size limit.   
26:08   
So let's talk about this paragraph here. Um but precisely are general principles   
26:14   
alone enough to describe fragmentation in all cases independently of any specific mechanism? Certainly not. As an   
26:21   
example of is the examples above suggest there are several others. For example,   
26:27   
the break up of a smooth liquid thread produces droplets from the uniform size   
26:32   
proportional to the jet diameter by a deterministic capillary instability.   
26:37   
Even violently expanded liquid shells bursting by the random nucleiation of holes followed by ligament breakup are   
26:45   
too regular to give rise to a power law distribution as an equation eight which   
26:50   
we didn't we went over that one. This is equation eight here,   
27:12   
but are instead well described by a bell-shaped distribution representative of a noisy capillary instability.   
27:19   
In that situation, the microscopic rearrangements within the ligaments constrain deterministically the variance   
27:26   
of the fragments diameters to be proportional to their mean squared. A feature found similarly in the radio   
27:32   
expansion of a necklace of magnetic beads. Uh the fragments are then gamma distributed with an order   
27:40   
like gamma distributed. A distribution also interpable in terms of maximal   
27:45   
entropy. But now with beta no more given by   
27:51   
but now with beta no more given by the space dimension. D is in equation 8 but by beta equals 1. Since   
28:03   
incidentally the minimum fragment size can actually be zero in the in that case   
28:09   
small sizes okay randomness which sets the form of the distribution and microscopic mechanisms   
28:17   
setting the distribution parameters D and V cooperate in their overall statistics N.   
28:24   
Similarly in solids patterns and fragments are well unders   
28:30   
Similarly in solids patterns and fragments are well understood from deterministic mechanisms and some simple   
28:36   
geometries both in quai static or dynamic fraction. However, even in   
28:42   
situations where randomness prevails, microscopic interactions between the fragments influence the distribution   
28:49   
shape. The observations in 18   
29:06   
So to conclude, we have shown that for brittle materials or fragmentation and turbulent flows, a kinematic constraint   
29:13   
applies to a maximal randomness principle, inferring both the power loss shape of the fragment size distribution   
29:20   
and the value of its dimensionality dependent expon. Considering several counter examples, we have also   
29:27   
delimitated delimitated the domain of validity of   
29:33   
this description which assumes molecular chaos in the sense of Boltzman and holds   
29:38   
in the absence of microscopic constraints between the fragments. Although these can be accommodated   
29:44   
subject to the appropriate mechanism, the description in some cases present   
29:50   
contribution also intends to make more precise the area where maximum entropy approaches can either be useful or not.   
29:59   
So this idea of molecular chaos uh this goes back to the kinetic theory of gases, the work of Paul and Tatiana   
30:06   
Erinfest, James Clark Maxwell and of course Boltzman.   
30:12   
So this is the molecular chaos hypothesis and it has this long German   
30:18   
name u is the assumption that the velocities of colliding particles are uncorrelated and independent of   
30:24   
position. So this is where you have this sort of randomized distribution of gas   
30:30   
particles. This is a standard assumption of statistical mechanics that you don't have this internal correlation of of   
30:38   
molecular positions in this a random system. Uh this means that the probab   
30:44   
the probability that a pair of particles with given velocities will collide can be calculated by considering each   
30:50   
particle separately and ignoring any correlation between the probability for finding one particle velocity v and a   
30:58   
probability for finding another velocity v prime in a small region. Uh James   
31:03   
clerk Maxwell introduced this approximation in 1867 but it's been a standard part of kinetic   
31:10   
theory. uh the assumption of molecular chaos is the key ingredient that involves proceeding from the BBG KY   
31:17   
hierarchy to Boltzman's equation by reducing the two particle distribution function showing up in collision terms   
31:25   
to a product of one particle distributions. This in turn leads to Boltzman's H   
31:30   
theorem of 1872 which attempted to use kinetic theory to show that the entropy of a gas prepared   
31:37   
in a state of less than complete disorder must invariably increase as the   
31:43   
gas molecules were allowed to collide. So this notion of of molecular chaos   
31:49   
sort of opens the door to entropy. And so this idea that entropy must increase   
31:56   
over time. This drew the objection from Lashmitt   
32:02   
that it should not be possible to deduce an irreversible process from time symmetric dynamics and time symmetric   
32:09   
formalism. And so this was Lashmitt's paradox.   
32:14   
The resolution of this in 1895 is that two velocities of two particles after a   
32:20   
collision are no longer truly correlated. So this is where we're getting this collision aspect in   
32:26   
bringing this into play that two particles might be correlated before their collision but after collision they   
32:32   
go off in different directions and it's it's pretty much a stochastic process.   
32:37   
And so since uh you know if you have like a container of of uh   
32:44   
of gas particles then they're always bouncing around in that space especially as you add heat and so the chances of   
32:50   
them colliding are very high and so that's actually what we're capturing is the postcolision trajectories   
32:58   
by asserting that it was acceptable to ignore ignore these correlations in the population at times after the initial   
33:04   
time. Boltzman then introduced an element of time asymmetry through the formalism of his calculation. So this   
33:11   
also has relevance to the erotic hypothesis. And so in physics and thermodynamics of   
33:18   
course the erotic hypothesis says that over long periods of time the time spent   
33:24   
by a system in some region of the phase space of microates with the same energy   
33:29   
is proportional to the volume of the region. So if you spend enough time   
33:34   
exploring um you know a representative region of   
33:39   
phase space you have enough information to understand all of the ent the entire phase space. So this is of course the   
33:48   
idea that all accessible microates are equa probable over long periods of time   
33:55   
and thus you know a predictable thing. So this is um sort of where we start in   
34:02   
statistical mechanics that um um are microates or erotic and then we work   
34:10   
from that to find the structure. So thank you to Morgan and Hussein for   
34:16   
those items. Okay. Now I'm going to go through a series of readings on uh tiny   
34:21   
neural networks. And I'm going to preface this by saying that tiny neural networks, some of the work on this, some   
34:29   
of the work is on applying like things like perceptrons to data. Uh   
34:38   
other things are uh applying recursive neural networks to data. And then there's this other area in machine   
34:44   
learning research that is kind of separate and they're trying to find the smallest network that gives us the best   
34:52   
result. So, it's it's kind of a smattering of work, and I'm going to go over it and talk about some of these   
34:57   
aspects of finding these very small neural networks that are still capable of pattern   
35:03   
recognition and how that's useful.   
35:08   
So, this is actually um from Reddit um and this is just a an observation here.   
35:16   
They point to a paper in a GitHub repository which we'll talk about later.   
35:21   
But this is uh the title of this thread is tiny neural networks are way more powerful than you think and I tested it.   
35:29   
So this is an R machine learning on Reddit. I just finished a project in a paper and   
35:36   
I wanted to share it with you all because it challenges some assumptions about neural networks. You know how   
35:42   
everyone's obsessed with giant models? I went the opposite direction and asked what's the smallest possible network   
35:49   
that can still solve a problem. Well, so here's what I did. The first is that I   
35:54   
created difficulty levels for emnest like pairing digits. Uh so zero and one   
36:01   
or zero versus one is easy. Distinguishing between zero and one distinguishing between four and nine is   
36:08   
classified as hard. So these are just different types of problems.   
36:14   
and how you know if you have a neural network of a certain size how well it can solve that problem.   
36:21   
Number two is training tiny fully connected networks some as small as two neurons to see how capacity affects   
36:29   
learning. So this is again where you have these units they're fully connected meaning that every unit is connected to   
36:35   
every other unit and then you know growing that set. So we go from two   
36:41   
neurons up upward to see how the capacity affects learning. So the larger   
36:47   
small networks um are going to have a larger capacity than the smaller ones   
36:53   
going down to a minimum of two. The third is that we pruned up to 99% of   
36:59   
the weights. And this is, you know, something that you can do if you start with a somewhat   
37:08   
large neural network. So you have a bunch of units. They have connections are fully connected and you expect there   
37:16   
to be some redundancy in those connections. So you can prune them and it should have no immediate effect on   
37:23   
the network. it does have an effect on the robustness of the network. But then you can also prune them down quite a bit   
37:30   
as it turns out. And what they did in this case is they pruned up to 99% of the weight. So that's almost all of the   
37:37   
weights. And in this case, what they're saying is that even in 95%   
37:43   
rate of of pruning where it's it's an extremely sparse network, this keeps working. Um, again, not necessarily in a   
37:51   
robust way, but it does keep you know giving a result that keeps that learned   
37:56   
information. Then number four is that they poked it with noise and occlusions to see if over   
38:02   
parame parameterization helps robustness and it turns out that that does help   
38:08   
robustness when you uh provide noise and occlusions to the data. So that's not   
38:13   
surprising that you train um a a network with objects with different types of   
38:20   
noise, different types of occlusions basically of different types of variation in the input and it can   
38:27   
recognize things outside of its immediate class. Okay, so that's interesting. And then so the craziest   
38:33   
findings here, a four neuron network can perfectly classify zeros and ones, but   
38:38   
it needs 24 neurons for tricky pairs like four versus nine. So for the easy class it it you know you only need about   
38:46   
a four neuron network which is I guess 16 uh weights if it's fully connected.   
38:52   
Uh then for 24 neurons which is a lot more weights um you need to have that   
38:57   
for these harder problems like four versus nine. So there's quite a gap in   
39:03   
between the minimal size networks for each of these uh tasks.   
39:09   
After pruning, the remaining 5% of weights aren't random. They're still focusing on human interpable features   
39:16   
and they're using this tool called saliency maps uh which are these heat maps that people use to look at um the   
39:25   
uh outputs of these networks uh in the weight structure. Uh so that's uh you   
39:32   
know basically observing that you're basically pruning it down to the sort of   
39:37   
the essential or the minimal connections and this is you know something that we   
39:42   
know from complex networks where not all connections are equal. Some are you know   
39:48   
sort of uh some some connections are redundant. So   
39:55   
sometimes nodes have more than one connection to another node either directly or indirectly.   
40:01   
But also and more importantly there are these critical connections. Sometimes they're weak connectors. Sometimes   
40:08   
they're connections. Maybe there's only one connection between two nodes either directly or indirectly and those need to   
40:15   
be preserved in order to have sort of this topological preservation and in this case this is a functional thing.   
40:23   
Uh this the third uh finding bigger networks aren't smarter just more robust   
40:29   
to noisy inputs like occlusion or gaussian noise. So big bigger networks   
40:35   
when when people think about building the biggest network as possible what they're doing is adding robustness. But   
40:42   
what this uh result suggests is that the smaller networks   
40:47   
um just maintaining a large high degree of connectivity is actually as robust as   
40:53   
maybe bigger networks. So that tradeoff of you know more no more units uh could   
41:01   
just be more connections and more complete connectivity.   
41:06   
So why does this matter? Um, if you're deploying models on edge devices, sparity is your friend. So, you   
41:12   
obviously want to have a very small representation if you're deploying things in the wild, especially on things   
41:18   
like edge devices. Um, but again, you know, sparity is your friend, but uh   
41:25   
redundancy is also your friend a lot of on a lot of cases. U overparameterization might be less about   
41:32   
generalization and more about noise resilience. So, this is what we're talking about. It's not necessarily that   
41:39   
you want to introduce say like noise uh or or   
41:44   
occlusions to generalize although that can help you generalize but it's also   
41:49   
about noise resilience which means that if you add noise into a like a zero or a   
41:55   
one and and provide different per permutations on that it's easier to   
42:01   
identify a zero or one in its different forms and especially if there's a noisier degradated signal, you can   
42:09   
identify that more quickly. Um, and then tiny networks can be   
42:14   
surprisingly interpretable. And so they um talk about this paper on the archive   
42:20   
and they highlight figure 8 where there are these paper misclassifications   
42:28   
that they talk about here. There these mclassifications that they   
42:34   
talk about in that context.   
42:40   
So this is uh this is the paper this is a paper from nature reviews neuroscience. Um this is tiny recurrent   
42:47   
neural networks for discovering cognitive strategies. This is Liji an he's the author and this was actually   
42:54   
published in uh nature reviews neuroscience. So this is about experimental   
43:01   
design in neuroscience and how we can use tiny recurrent neural networks to   
43:06   
uncover different what they call cognitive strategies. So one of the   
43:11   
things you find in neuroscience is you want to understand how um animals learn   
43:17   
from experience to make decisions. And so a lot of times we'll use normative modeling frameworks. So normative   
43:24   
modeling frameworks are uh models where we look at the sort of the rules of   
43:29   
decision making where we operate from like an epistemic position where we're interested in knowing you know in   
43:36   
knowledge and how that knowledge is operated on. So we use models like basian inference or reinforcement   
43:43   
learning. So we know that say for example reinforcement learning the purpose there is to find the optimal   
43:49   
strategy or the optimal um policy for uh   
43:55   
doing something and we reinforce different policies but this is at a level that isn't really like descriptive   
44:02   
of any neur neurological process. This is a a sort of a normative idea and so   
44:10   
this is where you know we can interpret how experience shapes adaptive decision   
44:15   
making. But these kind of models are of course too simple to account for the finer details of biological decision   
44:22   
making. So if we want to know something about how neurons   
44:27   
um help us make a decision or how brain regions help us make a decision, we can't really get there from some of   
44:34   
these normative models. And these of course as well as vary across individuals. So it's hard to   
44:40   
understand individual variation. By contrast, large artificial neural   
44:46   
networks are flexible enough to model intricate details of decision making.   
44:51   
However, owing to their complexity, they often act as black boxes that cannot be   
44:56   
easily understood in terms of cognitive mechanism. So, this trade-off between interpability and flexibility has   
45:04   
limited the field's ability itself to understand the cognitive strategies behind biological decision-m.   
45:11   
So, this trade-off can be resolved by using these tiny recurrent neural networks to discover cognitive   
45:17   
algorithms that govern biological decision making. This approach involves fitting a very   
45:23   
small tiny RNN to the behavior of a participant and a reward learning task.   
45:29   
We explored tasks with varying structures, lengths and learning stages.   
45:34   
These tiny uh RNNs comprise only one to four units. So these are very small. Again, these are the smallest ones that   
45:41   
we saw in the Reddit post that they were experimenting with.   
45:47   
And so this is very different from the uh hundreds of units models that we have   
45:53   
usually in a typical artificial neural network. So you might ask well why how   
45:59   
you know what of what use are these very small models. Uh the they seem almost to be toy models which don't have the same   
46:06   
predictive power as the hundreds of units models. Um but despite but despite   
46:11   
their small size, tiny RNNs and many adjustable parameters from their input and recurrent weights, allowing them   
46:19   
sufficient flexibility to capture a wide range of behaviors while remaining simple enough to interpret.   
46:26   
Tiny RNN's take as input the participants recent task experience such as previous choices and rewards. the   
46:33   
input through a set of weights learned from the data from each individual updates the unit activities which are   
46:40   
the dynamical variables that summarize what the individuals learned from past inputs.   
46:46   
So this is different from traditional modeling frameworks which use inputs to   
46:51   
d update dynamical variables which are values or beliefs much more rigidly   
46:56   
often relying on normative assumptions and handcrafted rules. So this is where you know we make assumptions about the   
47:03   
behaviors. We kind of don't we kind of assume the rules in advance. We set   
47:09   
those rules in advance. And what we're doing in these small networks is we're trying to let the rules emerge from the   
47:14   
data and the rules might be different for individual in in the subject pool. So this is much   
47:22   
more useful in that sense. Tiny recurrent neural networks excel   
47:27   
when abundant data are available. So this would be thousands of trials per participant. But many human data sets   
47:34   
contain only a few hundred trials per participant. So this is where you know we need to   
47:40   
have another step here to make these tools a little bit more uh amendable to   
47:47   
a wider range of experiments. Um we developed to this end we developed   
47:53   
a knowledge dist distillation procedure in which a larger teacher RNN which it   
47:58   
which is consists of tens of hundreds of units was trained on pulled data from all participants and student tiny RNNs   
48:07   
were trained to reproduce the teacher's predictions for each individual ensuring reliable modeling with limited data. So   
48:14   
we have this sort of um this interesting relationship between a   
48:20   
larger neural network and these tiny neural networks. So it's the larger neural network is being trained on the   
48:27   
data um and then it's uh basically trying to uh the tiny networks are   
48:34   
trying to match the teacher's predictions. So it's a a sort of a a tutor model   
48:41   
where you have smaller student you know the tiny models are the students the   
48:46   
larger model is a teacher and there's this effect of learning things from the teacher. So that's interesting.   
48:55   
Um the dynamics of these trained RNNs can be visualized using tools from dynamical systems theory which describes   
49:02   
how their internal states or dynamical variables evolve in response to inputs.   
49:07   
So for example, the RNN's internal state captures an animal's choice preference   
49:12   
which can be expressed as the logic or log odds of choosing one action over another and interpreted as a position in   
49:19   
the RNN's lowdimensional state space. uh triabil changes in this correspond to   
49:26   
a velocity and reward inputs act as an external set of forces that drive the evolution of the internal state within   
49:33   
this space. Plotting these positions and velocities for different task conditions produces   
49:40   
phase portraits that visualize how current states and external forces together shape the state trajectories   
49:47   
revealing hidden decision-making strategies encoded in the models.   
49:53   
So tiny RNN's uh provide a balance in that they're flexible enough to capture   
49:59   
complex patterns yet they're simple enough to be interpretable and broadly applicable across species and data sets.   
50:07   
So this is and then they tested the tiny models on uh six wellstudied reward   
50:13   
learning tasks including experiments with monkeys, rats, mice and humans.   
50:19   
Tiny RNNs in each case have performed traditional normative models in predicting participants   
50:26   
choices often matching the performance of larger RNNs. So this is interesting   
50:31   
that these smaller models did a pretty good job of matching the performance of other larger models. Um   
50:41   
beyond predictive accuracy, our approach has provided insights into decision-making strategies using   
50:47   
dynamical systems interpretations. So for example, the analysis of dynamics   
50:52   
of tiny RNNs revealed reward induced indifference effects and new forms of   
50:57   
preservation and choice bias that would have been difficult to find with traditional models. In addition,   
51:04   
applying these the same interpretive tools to artificial agents um which in this case are RNN models   
51:10   
trained to optimize reward learning test performance. These uncovered strategies that resemble basian inference.   
51:18   
So, not only was their performance uh comparable to normative models, but it   
51:24   
actually did things that were comparable similar to normative models themselves.   
51:31   
Tiny RNN's provide a powerful framework for understanding decision making um and then finding new cognitive   
51:38   
strategies while remaining predictive accuracy maintaining predictive accuracy. So that   
51:46   
is um really interesting work. Um   
51:52   
this is number three. It's it's another article. This is from the same author but it's a different article in nature.   
52:00   
And this is discovering cognitive strategies with tiny recurrent neural networks. So this is a more detailed   
52:07   
paper of that article in nature reviews neuroscience. Uh and so it's really kind of going over   
52:14   
the same sorts of things. Um the in intro here is interesting to give a little bit more background. Um from   
52:22   
early symbolic models to connectionist approaches, researchers have long sought   
52:28   
computational models that capture the adaptive nature of animal behavior.   
52:33   
Normative frameworks such as basian inference and reinforcement learning have been particularly influential given   
52:39   
their ability to formalize how agents accumulate knowledge from environmental interactions to make decisions processes   
52:47   
supported by prefrontal and stridal neural circuits. A key advantage of these models is their   
52:54   
simplicity is they typically have few parameters and can be easily augmented with additional assumptions such as   
53:01   
forgetting choice biases and preservation. Yet despite their simplicity and   
53:06   
extensibility, they often lead to incorrect or incomplete characterizations of behavior due to   
53:13   
bias and researcher subjectivity. So if you uh are following if you apply   
53:20   
these normative models what you get is exactly the type of assumptions you put   
53:26   
into them. So you know if you're thinking about neurodeiverse populations   
53:32   
or neuroatypical individuals those people won't be covered under the   
53:38   
normative framework because the they violate the assumptions of the normative framework. So we need to have a system   
53:46   
you know that allows us to have to let rules emerge or to let sort of   
53:51   
these assumptions emerge from the data instead of imposing them on top the data.   
53:57   
Uh this is another article. This is uh getting a little bit away from human subjects but this is also computational   
54:04   
psychiatry. Um so this is from the journal computational psychiatry and the   
54:10   
name of this article is using drift diffusion and reinforcement learning models to disentangle effects of   
54:16   
depression on decision making versus learning in the probabilistic reward task.   
54:24   
So let's go over the abstract. So the probabilistic reward task is   
54:30   
widely used to investigate the impact of major depressive disorder or MDD on   
54:36   
reinforcement learning and this is biological reinforcement learning and   
54:41   
recent studies have used it to provide insight into decisionmaking mechanisms affected by MDD.   
54:48   
The current project uses probabilistic reward task data from unmedicated treatment seeking adults uh with major   
54:56   
depressive disorder to extend these efforts in three ways.   
55:02   
Number one is providing a more detailed analysis of standard probabilistic reward task metrics, response bias and   
55:09   
discriminability to better understand how the task is performed. Number two is   
55:15   
analyzing the data with two computational models and providing psychometric analyses of both. And then   
55:22   
three, determining whether response bias, discriminability or model parameters predicted responses to   
55:28   
treatment with placebo or the atypical anti-depressant appropri   
55:35   
uh analysis of standard metrics replicated recent work by demonstrating a   
55:41   
dependency between response bias and response time and ensuring that rewards   
55:46   
totals in the PRT are governed by discriminability. behavior was well captured by the   
55:53   
hierarchal drift diffusion model which models decision-making processes. The   
55:58   
HDDM showed excellent internal consistency and acceptable retest reliability.   
56:04   
A separate belief model and reproduced the evolutionary response bias over time   
56:10   
better than the HDDM but its psychometric properties were weaker. Finally, the predictive utility of the   
56:17   
PRT was limited by small samples. Nevertheless, depressed adults who responded to bupropriion   
56:23   
uh showed larger pre-treatment starting point biases in the HDDM than non-responders,   
56:29   
indicating greater sensitivity to PRT's asymmetric reinforcement contingencies.   
56:35   
Together, these findings enhance our understanding of reward decision-making mechanisms that are implicated in MDD   
56:42   
and probed by the PRT. So this this uh section talks a little   
56:48   
bit about behavioral complexility or this section talks a little bit about behavioral complexity and how that plays   
56:55   
a role in determining bias. So behavioral and reinforcement learning   
57:01   
tasks can be surprisingly complex. In the PRT which is rooted in the signal   
57:07   
detection framework, participants must distinguish between two stimuli and   
57:12   
these are schematic mouths of similar length and you can see this in this   
57:17   
figure here where there's this mouth that they have to determine on a face and then they have to do make identify   
57:25   
the correct one. Um and so uh these are the schematic mouths and correct   
57:32   
identifications of one rich stimulus are rewarded three times more often than the correct identifications of the other   
57:39   
lean stimulus which means these stick figure faces. Um   
57:44   
consequently participants typically developed a response bias. They respond rich more than they respond rich more   
57:51   
than lean. um and weak response bias may be a   
57:56   
marker of uh anhidonia and may and many data are consistent with this proposal. Wherever researches   
58:04   
probe neural mechanisms that's support response biases this body of work is sufficiently extensive that the PRT   
58:11   
appears in the NIHDOC matrix as a validated test of reward learning.   
58:17   
Nonetheless, in a recent study comparing unmedicated adults with major depressive disorder to healthy controls, we   
58:24   
identify two aspects of PRT performance that were previously unrecognized.   
58:29   
So they use this drift model to determine the sort of uh response   
58:37   
uh to to like a reward stimulus. And so you have this decision threshold that   
58:43   
differs and the the drift diffusion is where you have the response that kind of   
58:49   
drifts towards these different biases over time. So you start here where the   
58:55   
responses are basically random and then they drift towards one response or   
59:01   
another response over time.   
59:06   
And so the response bias effects were not uniform. It was strong when response times were fast but weaker when response   
59:13   
times were slow. That indicates that the mechanisms underlying response bias likely involve preparation of fast motor   
59:20   
actions rather than for example sustained stimulus evaluation.   
59:26   
So like I said, this is getting away a little bit from the small neural networks, but it gives you this idea of   
59:31   
how normative models u perhaps don't capture the types of things we're interested in when we deal with um you   
59:39   
know experimental human behavior other types of experimental systems. So this fourth   
59:46   
article is how tiny neural networks represent basic functions. Uh this is sort of an introduction to mechanistic   
59:53   
interperability through simple algorithmic examples. Um this shows how small artificial   
1:00:00   
neural networks can represent basic functions. The goal is to provide fundamental intuitions about how neural   
1:00:06   
networks work and as well as give us insights into mechanistic interperability and this is a field that   
1:00:12   
seeks to reverse engineer neural networks. Uh so he presents three examples of   
1:00:18   
elementary functions, describes each using a simple algorithm and shows how algorithms can be coded into the weights   
1:00:25   
of a neural network and then the author explores if the network can learn the algorithm using   
1:00:31   
back propagation. So um this article attempts to break   
1:00:37   
neural networks into discrete operations and describe them as algorithms. An   
1:00:42   
alternative approach however perhaps more common and natural is to look at the continuous topological   
1:00:48   
interpretations of the linear transformations in different layers.   
1:00:54   
And so this for to understand topological intuition you can use TensorFlow playground which is a simple   
1:01:00   
tool for building basic intuition and classification tasks. ConfetJS uh demo   
1:01:08   
which is a more sophisticated tool for visualizing neural networks for classification tasks and neural networks   
1:01:14   
manifolds and topology a great article for building topological intuition into   
1:01:19   
how neural networks work. So um this is sort of the three   
1:01:25   
elementary functions of a neural network. Um so this is these are your inputs.   
1:01:31   
This is your bias. This is your nonlinear rectifier and then this is your output   
1:01:38   
y. So we have three components here. The inner product with the inner vector uh   
1:01:44   
where we add a bias term and then where we run a nonlinear activation function. So we have sort of this input that we   
1:01:51   
have to kind of figure out the input vector. We then have bias and then we have this nonlinear activation function   
1:01:58   
which activates the uh parts of the network that have   
1:02:04   
the weights that we want to pay attention to. So this is there's a collab notebook   
1:02:10   
that goes along with this if you'd like more information on this. And he starts   
1:02:15   
going through the different operators. So this is where we have our activation   
1:02:21   
function and our learning function at the end or output. Um we have to ask the   
1:02:27   
question you know how many neurons are response do we need to learn a certain   
1:02:33   
piece of information. It's like what we talked about in the um Reddit post which   
1:02:39   
is you know we have to have a minimal number of units to learn a minimal num   
1:02:45   
number of things or some sort of thing that we want to learn. So in this case we have this operator here. This is the   
1:02:53   
um less than operator. How many neurons are required to learn the function of x   
1:03:00   
being less than 10? And so write a neural network that returns one where the input is smaller than 10 and   
1:03:07   
otherwise zero otherwise. So this is our input x where it's smaller than 10 in   
1:03:13   
every case. So we have our solution here. Let's start by creating a sample data set that follows a pattern we want   
1:03:20   
to learn. So we start with an x and a y variable and then we get this function here which   
1:03:28   
is the ground truth where we have the step function at 10.   
1:03:33   
So everything on this side of the step function is one. Everything on this side of the step function is zero.   
1:03:40   
So this is a simple classification task. If x is less than 10, it is one. If x is   
1:03:48   
greater than 10, it's zero. This classification task can be solved using logistic regression and a sigmoid   
1:03:55   
as the output activation. Using a single neuron, we can write the function of sigmoid ax plus b, b being the bias term   
1:04:06   
and can be thought of as the neuron's threshold. Intuitively can set b to 10 and a to 1 and get f= sigmoid 10 - x. So   
1:04:16   
let's implement and run f using pietorrch. We set this up in PyTorch   
1:04:22   
and we get this ground truth which is in blue which is what we started out with and then the prediction which is the   
1:04:27   
sigmoid. So the step function of course is a straight line at 10. The sigmoid is   
1:04:34   
uh mostly correct except because it's uh you know has that sigmoid shape or that   
1:04:40   
S shape it's going to have it's going to predict results that are either side of   
1:04:46   
10 just a little bit. Okay. Okay, so that looks pretty good in terms of like   
1:04:51   
the ground truth. So it looks like the right pattern, but can we make a tighter approximation? So we don't want to have   
1:04:58   
anything over 10 at all. And we'd prefer that all of this would be closer to uh   
1:05:04   
an a perfect accuracy. So for the sigmoid function as the in   
1:05:10   
inputs approach uh negative to positive infinity and outputs approach 0 to one   
1:05:16   
the outputs approach 0 to one respectively. Therefore we need to make our 10 - x function return large numbers   
1:05:23   
which can be done by multiplying it by a larger number say 100 to get f sigmoid   
1:05:28   
100 by 10 - x. So now we'll get f9.5 and   
1:05:34   
that's equivalent to one roughly. So it gives us this tighter sigmoid tighter to the ground truth this narrower sigmoid.   
1:05:42   
Indeed when our training network with one neuron it converges to f sigmoid m   
1:05:47   
10 minus x where m is a scaler that keeps growing during training to make the approximation tighter. So through   
1:05:54   
training this sigmoid gets tighter and tighter and closer to the ground truth step function.   
1:06:02   
To clarify, our single neuron model is only an approximation of the uh less than 10 function. We will never be able   
1:06:08   
to reach a loss of zero because the neuron is a continuous function while less than 10 is not a continuous   
1:06:14   
function. Our second one is minab.   
1:06:19   
So write a neural network that takes two numbers and returns the minimum between them. So this is uh where   
1:06:27   
uh we're trying to figure out the minimal distance between two numbers.   
1:06:32   
So like before let's start by creating a test data set and visualizing it. So this is setting this test data set up   
1:06:39   
and then this is the sort of the plot of it. So this is visualizing the training   
1:06:44   
set. In this case we can use relu activation because it is essentially a maximum   
1:06:51   
function. Indeed using rel can write the min function as follows. This is the min   
1:06:58   
function here in terms of value. And so now we want to   
1:07:04   
uh build a small network that is capable of learning equation one and try to train it using gradient descent. So this   
1:07:11   
is our uh model. We're instantiating a class and we're uh writing our function here   
1:07:19   
that uses real to evaluate this. This is uh a visualization of the minmodel   
1:07:25   
computation graph. Um so this is the input tensor depth, the linear depth,   
1:07:32   
the rel depth, the category depth and then the output tensor depth.   
1:07:38   
So we train this model for 300 epics and that's enough to converge the model. So   
1:07:44   
let's look at the model's parameters. So this is sort of the way it's set up here. We have our weights, our bias and   
1:07:51   
our output layer weights and bias. So many weights are zeroing out. We are left with a nicely looking model here.   
1:07:59   
And but this is not the solution we expected. But nevertheless, it's a valid solution and even cleaner than what we   
1:08:06   
see in equation one. By looking at the network, we learned a new nicely looking   
1:08:11   
formula. So the proof of this formula here is is this proof here. And that so   
1:08:18   
that works out. And then our third uh example is is   
1:08:23   
even. So now we want to create a neural network that takes an integer x as an input and returns x modulus 2. That is   
1:08:32   
zero if x is even one if x is odd. So this is basically an even odd classifier. Um this one looks quite   
1:08:40   
simple but surprisingly it is impossible to create a finite size network. This one looks quite simple but surprisingly   
1:08:46   
it is impossible to create a finite size network that correctly classifies its integer. Um and this is you know even   
1:08:54   
true using a non periodic activation function such as relu.   
1:09:01   
So a network of relu activations requires at least n neurons to correctly classify each of two to the power of n   
1:09:08   
consecutive natural numbers as even or odd. And so this is a proof using induction   
1:09:15   
and that and then there are different cases to consider there.   
1:09:23   
This is the implementation. This is the ground truth here where we try to implement this algorithm using a neural   
1:09:30   
network over a small domain. We again start again by defining the data and   
1:09:35   
this is our ground truth. And then because the domain contains two to the fourth integers, we need to use   
1:09:42   
six neurons. Five for each of these uh plus one output neuron. Let's build the   
1:09:48   
network and hardware the weights. This is the code here um using this um model.   
1:09:55   
As expected, we can see that this model makes a perfect prediction. So this is the X Y prediction versus ground truth.   
1:10:04   
And as expected, it doesn't generalize to new data points.   
1:10:11   
We saw that we can hardwire the model, but would the model converge to the same solution using gradient descent? And so   
1:10:16   
now we add gradient descent into the mix. And of course, the answer is not so easily. Instead, it just stuck at a   
1:10:23   
local minimum predicting the mean. So this is again where the prediction is   
1:10:29   
around the mean and it's not really picking up things uh very far away from   
1:10:34   
the mean. It's stuck in this local minimum and it doesn't generalize. Well,   
1:10:39   
this is a known phenomenon where gradient descent can get stuck at a local minimum. It is especially   
1:10:45   
prevalent for non smooth error surfaces of highly nonlinear functions such as is   
1:10:51   
even more details are beyond the scope of the article but to get more intuition one can look at the many works that   
1:10:58   
investigated the classic exor problem. Even for such a simple problem we can see that gradient descent can struggle   
1:11:04   
to find a solution. In particular, I recommend Richard Bland's short book, Learning Exor, Exploring the Space of a   
1:11:12   
Classic Problem, a rigorous analysis of the error surface of the exor problem.   
1:11:18   
Um, and then so some final words. I hope this article has helped you understand the basic structure of small neural   
1:11:24   
networks. Analyzing large language models is much more complex, but it's an area of research that is advancing   
1:11:31   
rapidly and full of intriguing challenges. Number six is this um article from MIT   
1:11:38   
technology review by Karen How and this is tiny 4-bit computers and now all you   
1:11:44   
need to train AI. So this is again focusing on these tiny four-bit computers and this is an area of machine   
1:11:52   
learning where they're trying to figure out the minimal size network for learning effective things or what if we   
1:11:59   
want to learn something in a model what's the smallest model we can use. So this is a you know an exercise in um   
1:12:07   
efficiency because it works faster and it uses less energy but it's also of   
1:12:13   
course you know and and for small devices if we're using like tiny devices   
1:12:18   
but also you know it has insights into what we can do with these small networks for other things.   
1:12:26   
So again this the problem here is that deep learning uses a lot of energy and a   
1:12:32   
lot of computational resources and so you know maybe again like we said in   
1:12:37   
some of the earlier articles maybe we don't need to have these massive networks like we said massive networks   
1:12:45   
really provide robustness or at least that's the argument. Um and so you know   
1:12:50   
we we like robustness and we like to have like you know that aspect of the   
1:12:56   
networks but to learn things efficiently we don't necessarily need that robustness especially if they're   
1:13:03   
problems that don't require a lot of generalization or robustness. So this is uh and then we can also achieve   
1:13:09   
robustness in other ways as well. We don't necessarily just need to use larger and larger networks and scale   
1:13:15   
everything up. Um the idea about scaling laws is that you know if we just get big   
1:13:20   
enough networks we can learn like you know we have the super performance and   
1:13:25   
we don't have to worry about um you know um how well the model can generalize. We   
1:13:34   
just you know we can power our way through it. And so that's that's what we're kind of talking about here. Um   
1:13:43   
so basically uh the idea here is that you have this four-bit deep learning. So   
1:13:49   
there's this part of the article how bits work. You've probably heard before that computers store things in ones and   
1:13:55   
zeros. These fundamental units of information are known as bits. When a bit is on it corresponds with a one.   
1:14:02   
When it's off it turns into a zero. Each bit in other words can only store two pieces of information. But once you   
1:14:09   
string them together, the amount of information you can encode grows exponentially. Two bits represents four pieces of   
1:14:16   
information because there are two to the second combinations which will give you four. Four bits can represent two to the   
1:14:22   
4th or 16 pieces of information. Eight bits can represent two to the eth and so   
1:14:28   
on. So this these are these fully connected networks. If we have say um   
1:14:33   
two uh two units, we actually have four different combinations in those four   
1:14:40   
weights. If we have four units, we can have 16 pieces of information or 16   
1:14:45   
weights. And so we can have, you know, as we increase the number of units, we   
1:14:51   
have the scaling of an increase in the number of weights that we have. And so we can do a lot with relatively small   
1:14:57   
networks. We have a lot of potential weights we can use. And of course, like we said, we can prune a lot of them and   
1:15:03   
still get good results. So we can do a lot with small networks.   
1:15:10   
Well, but going to this 4-bit deep learning. So what does 4-bit training mean? Well, to start, we have a 4-bit   
1:15:16   
computer and that's four bits of complexity. One way to think about this, every single number we use during the   
1:15:23   
training process has to be one of 16 whole numbers betweengative8 and seven   
1:15:29   
because those are the only numbers our computer can represent. This goes for the data points we feed into the neural   
1:15:35   
network, the numbers we use to represent the neural network and the intermediate numbers we need to store during   
1:15:41   
training. So how do we do this? Let's first think about the training data.   
1:15:46   
Imagine it's a whole bunch of black and white images. Step one, we need to convert those images into numbers so the   
1:15:52   
computer can understand them. We do this by representing each pixel in terms of its grayscale value. Zero for black, one   
1:16:00   
for white, and then decimals between for the shades of gray. Our image is now a   
1:16:05   
list of numbers ranging from 0 to one. But in 4bit land, we need to range from8   
1:16:11   
to 7. The trick here is to linearly scale our list of numbers so that 0   
1:16:17   
becomes8 and one becomes negative or one becomes positive 7 and the decimals map   
1:16:23   
to the integers in the middle. So we get this number line like this   
1:16:29   
where we're stretching out our 0 to one and we're building a map between our   
1:16:35   
values between 0 and one, our interval which is now8 to 7. The process isn't   
1:16:41   
perfect. So if you started with the number 0.3, you would end up with a scaled number of -3.5. We'd end up   
1:16:47   
somewhere up in this part of the number scale here. But our four bits can only   
1:16:52   
represent whole numbers. So you have to round -3.5 to four. You end up losing   
1:16:58   
some of the gray shades or so called precision in your image. You can see what that looks like in the image below.   
1:17:04   
So you end up with this sort of grayscale uh grayscaling effect where   
1:17:09   
the fewer bits you have to encode the less detail you have. So you have this nice photographic detail in an 8bit   
1:17:16   
model. But in a one bit model you have this very um light and dark   
1:17:23   
representation. You lose any of the information about the skin. You lose any   
1:17:28   
of the information about the hair. You just have to kind of, you know, assume that you know kind of what those things   
1:17:34   
are from the original image. If I just gave you a one bit image, all you would see is the black and the white and you   
1:17:41   
would have no distinction between say like the eyeball and the um and the eyebrow and and parts of the shadows of   
1:17:48   
the face. It would be indistinguishable. Although in the two bit model, you would have some uh more grayscale values you   
1:17:56   
could use to sketch out some of the details there. And then when you get to the 8 bit value, you can essentially   
1:18:01   
reproduce some low res version of this image. So, you know, if you're if you've ever   
1:18:08   
worked with computer graphics or you remember um say like the old AmIGGa   
1:18:14   
computers, you know, kind of this problem pretty well where you have these, you know, you're working with a a   
1:18:21   
small amount of memory and you have to encode features in this small space, in   
1:18:26   
this small graphical space. So, you know, you have to be able to make uh uh   
1:18:32   
use your grayscale values very efficiently. Uh so this is kind of a an old problem.   
1:18:39   
We don't worry about it as much when we have a lot of computational power. But one of the things you know you learn   
1:18:44   
from studying old computer science or at least the computer science of that era   
1:18:51   
is that you know you can use these small networks in in very creative ways that   
1:18:57   
you can use them to represent things and it forces you to do that. Um so it's interesting. So as you lose precision,   
1:19:04   
you have to figure out ways to represent these problems in different um you know   
1:19:09   
differently. So this trick isn't too shabby for the training data. But when we apply it   
1:19:15   
again to the neural network itself, things get a bit more complicated. So this is where we often see neural   
1:19:21   
networks drawn as something with nodes and connections like the image above. But for a computer turns it into   
1:19:28   
numbers. Each node has an activation value and a connection weight. And we   
1:19:34   
know that from some of our other articles. And then we're making this map between our values in our um in our   
1:19:43   
channelgative8 to 7 and then we're mapping our decimals to that.   
1:19:51   
So linearly scaling numbers that span several orders of magnitude loses all the granularity at the tiny end of the   
1:19:57   
scale. As you can see in this example, any number smaller than 100 would be scaled fromgative8 org -7. This lack of   
1:20:05   
precision would hurt the final performance of the AI model. So after two years of research, the researchers   
1:20:12   
finally cracked a puzzle. Uh this puzzle of representational um you know detail   
1:20:18   
at these small these small models. Borrowing an existing idea from others,   
1:20:23   
they scaled the intermediate numbers logarithmically. to see what I mean. Below is a logarithmic scale. You might recognize   
1:20:30   
the so-called base of 10 using only four bits of complexity. The researchers   
1:20:35   
instead use a base of four because trial and error shows this work best. You can see how it lets you encode both tiny and   
1:20:41   
large numbers bit constraints. So you can't really see it in this copy that I have here, but basically it's this log   
1:20:49   
putting things on a logarithmic scale and using that as a means to make this mapping.   
1:20:56   
With all the pieces in place, this latest paper shows how they come together. Uh they ran several   
1:21:01   
experiments where they simulate for a bit training for a variety of deep learning models in computer vision,   
1:21:07   
speech, and natural language processing. The results show limited loss of accuracy in the model's overall   
1:21:13   
performance compared with 16 bit deep learning. The process is also more than   
1:21:18   
seven times faster and seven times more energy efficient.   
1:21:23   
And so uh for a bit deep learning uh you know it really needs more work. The   
1:21:30   
paper only simulates the results of this kind of training. Doing it in the real world would require new 4-bit hardware.   
1:21:37   
So we really need to have a different type of hardware to really kind of   
1:21:42   
capture a lot of the potential of this method. Um this advancement opens the door for   
1:21:49   
training in resource constrained environments. wouldn't necessarily make new applications possible, but it would   
1:21:55   
make existing ones faster and less battery draining by a good margin. So, um   
1:22:01   
that is that article. Article seven is this um article and I'm   
1:22:07   
not going to go through the whole thing. I'm just going to talk about the abstract. This is understanding generalization, robustness, interpacity   
1:22:16   
neural networks. So our abstract here um although modern   
1:22:22   
deep learning often relies on massive overparameterized models the fundamental interplay between capacity sparity and   
1:22:29   
robustness and low capacity networks remains a vital area of study. We introduce a controlled framework to   
1:22:36   
investigate these properties by creating a suite of binary classification tasks from the emnest data set with increasing   
1:22:43   
visual difficulty. So this is the example we saw in the Reddit post that   
1:22:48   
the paper that they pointed to where they're comparing they have these easy tasks by comparing zero and one and   
1:22:56   
these harder tasks like comparing four and nine. Our experiments reveal three core findings. So first the minimum   
1:23:03   
model capacity required for successful generalization scales directly with task   
1:23:09   
complexity. So this is again um we have this minimum   
1:23:15   
model and has a capacity and we need to you know based on the task complexity we   
1:23:20   
need to maybe a larger model. So if we have a a task of small complexity we can   
1:23:25   
use the smallest model possible. If the task complexity is a little bit harder then we need to use a larger model. And   
1:23:32   
by task complexity just means what the feature space looks like. So differentiating between a zero and one   
1:23:38   
is is easier than a four and a nine because it has a maybe a larger feature space.   
1:23:44   
Second, these train networks are robust to extreme magnitude pruning up to 95% sparity. Again, what was talked about in   
1:23:51   
the uh Reddit article uh where they reveal the existence of sparse high   
1:23:57   
performing subn networks. So this is actually interesting in terms of like uh   
1:24:02   
community uh discovery in complex networks and one of the things that   
1:24:08   
people think about in complex networks in terms of connectivity um you have these sub networks sometimes   
1:24:15   
that are sparssely connected to other networks um and but they do actually play an important role in the overall   
1:24:21   
topology of the network. Um and so in this case what they're doing is they're   
1:24:27   
really just kind of getting not only you know finding the smallest model in terms   
1:24:32   
of the number of units but finding the smallest number of connections because remember those weights are kind of the   
1:24:40   
uh the resource constraint of the network because as you grow the number   
1:24:45   
of nodes in your network number of connections the number of weights and so   
1:24:51   
forth uh grow at an um I can't remember what the scaling is. Um it's somewhere   
1:24:58   
between um exponential and super exponential. So it's it's definitely a a   
1:25:06   
memory constraint. Um third we show that overparameterized   
1:25:11   
uh overparameterization provides a significant advantage and robustness against input corruption. So again we   
1:25:19   
want this robustness. We have this we can have this overparameterization which   
1:25:24   
comes at the cost of a larger network but we do want some overparameterization   
1:25:30   
and we you know we can get it maybe through u you know having more   
1:25:36   
connectedness but really uh we just need to kind of figure out ways to introduce   
1:25:41   
over parameterization without too much um without the models   
1:25:46   
being too big. And the reason we do this is to have robustness. So really if we   
1:25:52   
can do if we can achieve robustness without massively scaling up the network, that's what we want.   
1:25:58   
Interperability analysis via saliency maps further confirms that these identified sparse subnet networks   
1:26:05   
preserve the core reasoning process of the original dense models. So overall this work provides a clear clear   
1:26:12   
empirical demonstration of foundational tradeoffs governing simple neural networks.   
1:26:19   
So really this is you know uh given our discussions about post transformer   
1:26:25   
topologies and networks this is really interesting because we you know we said   
1:26:32   
why do you want to move on from transformers and it turns out that transformers are very large models that   
1:26:39   
if we could find smaller models we could improve the the performance per well we could definitely improve the efficiency   
1:26:46   
of the models We might even be able to perform prod u improve the performance of models if we can figure out ways to   
1:26:53   
at least maybe match say the robustness of a transformer with a smaller model overall.   
1:27:00   
So massive models like transformers and deep convolutional networks have pushed the boundaries of performance across   
1:27:06   
many challenging tasks. This progress often comes at the cost of heavy computational resources   
1:27:12   
and all of that and they often operate as black boxes. So if we had smaller networks, we could say make that process   
1:27:20   
interpretable. We could have smaller networks that use less energy, use less memory, and figure   
1:27:27   
out ways to make them more robust. Their lack of transparency makes them less suitable for scenarios where   
1:27:33   
resources are limited and understanding the model's reasoning is critical.   
1:27:39   
So they say smaller networks can serve as an effective and efficient alternative.   
1:27:44   
And then so they basically talk about a lot of the same things we've already talked about in some of the other other   
1:27:51   
articles. And then finally, this article here is the GitHub repository for   
1:27:57   
lowcapacity neural networks. So this was the GitHub repository linked to in the   
1:28:02   
original Reddit post where you know this is where they're kind of looking at uh   
1:28:09   
lowcapacity neural networks and how small they can go. So tiny neural   
1:28:15   
networks can solve emnest binary tasks even after 95% weight pruning and   
1:28:21   
overparameterization boosts robustness not just accuracy. And then so some of the things that are   
1:28:27   
interesting about this is that u you can do this what they call brain surgery for   
1:28:32   
neural networks. You can pro 95% of the weights and still have a functional   
1:28:37   
network. You have this task complexity scaling where a four neuron net handles   
1:28:44   
a task an easy task like zero versus one but you need a 24 neuron uh network to   
1:28:51   
handle pairs like four versus nine. We can have these saliency maps that prove   
1:28:57   
that pro prune nets use sort of a humanlike reasoning. So they they focus   
1:29:04   
on the same types of features as our uh perceptual systems focus on which I   
1:29:09   
don't know if that qualifies as humanlike reasoning. Then finally overparameterization does not equal   
1:29:14   
overkill. That bigger nets aren't smarter just because they're more robust to noise.   
1:29:22   
Bigger nets aren't smarter. They're not just, you know, being able to generalize better. They're just more robust to   
1:29:28   
noise. So that's uh that feature on tiny neural networks. Hopefully that was useful in   
1:29:35   
terms of understanding what tiny neural networks are, why they're useful, and where we can use them both in like human   
1:29:43   
subjects or animal studies and in computer science.   
1:29:49   
Finally, I wanted to talk about two new active or I guess they're not new active inference papers. They're papers on   
1:29:54   
active inference that I found recently. Um very interesting papers.   
1:30:00   
The first article is in IEL transactions on cognitive and developmental systems   
1:30:07   
and this is called ama inspired framework for raising good robots. Um so this is kind of merging developmental   
1:30:15   
stuff into this sort of um more inspired framework.   
1:30:21   
So uh the abstract reads our current computer and AI systems are built on neuroscience principles from a century   
1:30:28   
ago. Recent advances in our understanding of biological computation have not crossed into computer science   
1:30:36   
to catalyze advancements. We outline a multi-dimensional blueprint for a form of bio inpired agent   
1:30:42   
leveraging modern neuroscience principles uh including the collocicalization of   
1:30:49   
memory and compute plasticity embodiment active inference and   
1:30:55   
neurodedevelopmental principles. We discuss how combining these core features could theoretically lead to   
1:31:01   
cognitive agents that are aligned to our pro-social values transparent,   
1:31:07   
explainable, and energy efficient. So this is what they mean by good robots.   
1:31:12   
In particularly we leverage Mars triille framework an advocate for an   
1:31:18   
implementation level consisting of embody neuromorphic hardware   
1:31:23   
an algorithmic level consisting of active inference and a computational level consisting of pro-social goals   
1:31:31   
supported by evidence of pro-sociality catalyzing the development of our own complex cognitive abilities. So we have   
1:31:37   
this implementation level which is this embodied neuromorphic hardware. So it's   
1:31:42   
like the brain but also the body and this is all neuromorphic the algorithmic level which is active   
1:31:49   
inference which is the the sort of the normative decision making part of this and then the computational level which   
1:31:56   
is pro-social goals which also introduces development of the agent. A   
1:32:02   
developmental process scaffolds different pro-social computations over time. Supporting our perspective, we include   
1:32:09   
simulation data demonstrating the transfer of priors between two different pro-social behaviors by active   
1:32:16   
inference. Supported by an embodied process, agent behavior is transparent and   
1:32:22   
explainable throughout. We advocate for this blueprint as a guide in creating capable, ethical, and sustainable   
1:32:28   
machine intelligence. So this is where they kind of talk about the limitations   
1:32:34   
of current AI where we need extensive training, computation, memory and   
1:32:40   
energy. We also have difficulties coping with and exploiting noise, variability   
1:32:45   
and uncertainty. Difficulties generalizing across tasks and environments.   
1:32:51   
Poor performance on tasks requiring embodied intelligence such as adaptation to external conditions. And then   
1:32:58   
finally, inadequate transparency, interpretability, and explanability. So these are all sort of viewed as like   
1:33:05   
limitations of current AI systems. And then the idea is that we need maybe more   
1:33:10   
neuroscience or more up-to-date neuroscience as well as maybe an updated version of   
1:33:16   
computation since we're operating on the vanoyman computational architecture. So   
1:33:22   
this is where the neuromorphic stuff comes in.   
1:33:30   
And so this is what they mean by a good robot. Um definitely applying Mars trile   
1:33:35   
level hypothesis here is really interesting. Um and so that that's kind   
1:33:40   
of part you know this is where   
1:33:48   
so active inference comes in at the algorithmic level. So Mars algorithmic level relates to processes employed in   
1:33:55   
transforming inputs into outputs. Applied to robotics, this would encompass the models used to process   
1:34:01   
information and perform actions. So an overview of the active inference   
1:34:06   
framework originating from neuroscience. The active inference framework offers a   
1:34:12   
biologically plausible and unified explanation for how the brain processes information, earns, and generates   
1:34:19   
behavior. This includes solving the hard exploration problems and accounting for   
1:34:24   
mechanisms of natural agency and behavior. We am here to provide a high level overview of Aif or or active   
1:34:32   
inference framework relevant to embody neurodedevelopmental systems.   
1:34:38   
Um within AIF the brain models the world as a set of probabilities which it uses to   
1:34:45   
make inferences and predictions about the world. The brain actively works to minimize surprise by aligning   
1:34:52   
predictions and observations as closely as possible. So surprises is uncertainty   
1:34:57   
about the world given the data and it's you know this idea of prediction error   
1:35:04   
free energy. So it's basically the entropy of the system and you want to minimize it over time as you as you   
1:35:11   
learn free energy and hence surprise minimization is achieved by number one   
1:35:18   
adjusting models or altering perception or two selecting actions that maximize   
1:35:24   
information gain and minimizes prediction errors. So if you turn your head towards an unknown noise that's uh   
1:35:31   
minimizing prediction error um and you know if you're uh adjusting your model   
1:35:37   
you're altering your perception uh to also minimize prediction error. So Aif   
1:35:44   
is said to provide a dual account of both perception and action. And so as such it involves a continual   
1:35:50   
loop of prediction, perception and action over short time scales. Perception optimizes beliefs about the   
1:35:57   
world, but over longer time scales, learning optimizes beliefs about the relationships between variables that   
1:36:04   
constitute the world. So this is a superior approach to reinforcement learning. We talked about   
1:36:11   
the connection between reinforcement learning and active inference in our talks. uh but also more generally I   
1:36:18   
think in the active inference institute symposium that was in November we talked   
1:36:24   
about this distinction and how you know how active inference compares to   
1:36:29   
reinforcement learning. It's definitely a um an interesting kind of comparison.   
1:36:34   
And I don't necessarily know if um active inference is better than reinforcement learning, but it's   
1:36:40   
definitely complimentary and it does a lot of the you know it's trying to get at a lot of the same things.   
1:36:46   
So they kind of go through what uh active inference is useful for in this type of model. Um and you know going   
1:36:54   
through its sort of applications to robotics and you know going through figure two   
1:37:01   
here it goes through how you have the implementation level the algorithmic   
1:37:07   
level and the computational level over time and how they interact. So you have   
1:37:12   
things from the implementation level moving to the algorithmic level updating   
1:37:17   
that at the next time point and then updating that algorithmic level updating the computational level at the next time   
1:37:24   
point. So you almost have like these uh these go boards   
1:37:31   
which you know where you have things happening at the implementation level at time two moving to the algorithmic level   
1:37:38   
at time three and then that can update both the implementation level at time four and the computational level at time   
1:37:45   
four. So it can actually go backwards as well. So your your synapses and physical   
1:37:50   
body configurations update models. Models can update the synapses and   
1:37:56   
physical body configurations as well as the skills. And then the skills can update the models appropriately.   
1:38:14   
So this other paper is active inference for learning and   
1:38:19   
development and embodied neuromorphic agents. This is from the journal entropy. I think it's the same author, same first   
1:38:26   
author. Um, and so the abstract here is taking inspiration from humans can help   
1:38:32   
catalyzing embodied AI solutions for important real world applications.   
1:38:38   
Uh, current human inspired tools include neuromorphic systems and the developmental approach to learning.   
1:38:44   
However, this developmental neurobotics approach is currently lacking important frameworks for humanlike computation and   
1:38:51   
learning. We propose that humanlike computation is inherently embodied with its interface to the world being   
1:38:57   
neuromorphic and its learning process operating across different time scales. These constraints necessitate a unified   
1:39:04   
framework active inference which is underpinned by the free energy principle. Here end we describe   
1:39:11   
theoretical and empirical support for leveraging this framework and embody neuromorphic agents of autonomous mental   
1:39:18   
development. We additionally outline the current implementation approaches including toolboxes and challenges we   
1:39:26   
and we provide suggestions for next steps to catalyze this important field. So this is kind of like a less um   
1:39:34   
ambitious paper doesn't talk about Mars levels. It does talk about this aspect of um using um active inference to look   
1:39:43   
at developmental neurobotics quite specifically. So they they talk a little   
1:39:49   
bit about embodied agents and so how embodiment is important and   
1:39:55   
how this is a key component of any robotic system.   
1:40:03   
And they talk a little bit about how in robots Even in embodied robots, you have   
1:40:09   
this energy limitation that is that a lot of the computations require this sort of energy expenditure   
1:40:16   
and we want to minimize it as much as possible. So we want to be able to use something like synapses and we want to   
1:40:23   
capture the sort of energy efficiencies of biological structures. So inspired by   
1:40:29   
the brain, neuromorphic computing aims to create powerful energy efficient cognitive systems and has been described   
1:40:35   
as a key enabling technology that the development of a unique generation of autonomous agents. Neuromorphic systems   
1:40:43   
include plastic synapses and these are spiked dependent timing plasticity uh   
1:40:49   
connections and dynamic and eventbased computing paradigms. efficiency in this   
1:40:55   
context is relative to the particular energy constraints imposed by the environment and the body itself. So they   
1:41:02   
kind of go over some of these components and how they allow for continual   
1:41:07   
learning. So basically what we want to do is we want to build these more biological structures   
1:41:13   
and we want to use them in ways that are you know allow us to be more energy   
1:41:19   
efficient. Um and then they kind of go through a lot of like developmental analogies. So   
1:41:27   
looking at developmental sciences and how skills are acquired. So you know we   
1:41:33   
have a number of different types of skills that are acquired not just in development not just kind of in learning   
1:41:42   
like training things with data but through these embodied experiences. So   
1:41:47   
this is where the body has to interact with the world. You have to have these experiences to learn properly in   
1:41:53   
development. And then that developmental learning scaffolds future learning. So it's not just a matter of throwing as   
1:42:00   
much data at the system as possible. It's about crafting these experiences with the body and then building upon   
1:42:07   
that. Um emulating these embodied learning mechanisms and artificial agents may therefore promote the   
1:42:13   
acquisition of humanlike abilities. This developmental approach aligns with the 1950 hypothesis by Alan Turring. Instead   
1:42:21   
of trying to produce a program to simulate the adult mind, why not rather try to produce one that simulates the   
1:42:27   
child's then subject to an appropriate course of education, one would obtain the adult   
1:42:33   
brain. So which is you know this is again this developmental perspective goes way back to Alan Turing at least in   
1:42:40   
in computing. But you know the idea of kind of meeting this with um you know   
1:42:47   
some sort of formal approach that works really well has been quite elusive and we've talked many times about how this   
1:42:53   
might be done how people are trying to do this in different ways. It's a really interesting um kind of you know way to   
1:43:00   
think about it because for one thing development has a lot of aspects to it. You can look at morphagenesis. You can   
1:43:07   
look at learning. You can look at um you know different types of organisms you   
1:43:15   
know and they all have different types of developmental periods. So they're all you know but I think it's worth   
1:43:22   
mentioning that you know the basic difference between something like Mars levels and a developmental approach is   
1:43:29   
that you know you basically Mars levels have to come from somewhere right? I mean we have to have at some point these   
1:43:37   
things are sort of they have to originate somewhere and then they build into the adult form. So this is um   
1:43:45   
definitely and then there's plasticity that kind of fits into all of this. So definitely a lot to think about here and   
1:43:53   
what they're getting at here is they're getting at the development of learning but I don't know if they get into the   
1:43:59   
development of uh different types of embodiment as well. That would be also another thing. This is something that   
1:44:06   
we've been doing work in our group on about talking about how morphogenesis can be modeled in terms of this uh   
1:44:13   
learning developmental learning process. But this paper just really kind of   
1:44:19   
compares traditional ML with these developmental imperatives.   
1:44:25   
So that's all for today. Thank you for paying attention. If you've made it this far, thank you. Um, and so we trying we   
1:44:33   
may have one more meeting this year, but otherwise we're wrapping up for the   
1:44:38   
year. So please, um, if you have ideas for what to do in the next year, let us   
1:44:45   
know. Um, and, um, see you next week or next year. Thank you.   
   
   
