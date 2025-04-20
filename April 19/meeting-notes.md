## Meeting Recording

[YouTube link](https://www.youtube.com/watch?v=4lg8OoMCnq0)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114368783498745538)

## NOTES
Pairwise --> limit problem (not a Markov Game).

"Learning to Learn" --> MARL, LLMs.


Logan Cross --> multi-agent RL. Using LLMs -- theory of mind to understand other agents.

* how best to cooperate, coordinate?

* Markov Games -- multi-agent RLs.

* expands on MDPs, ant behavior, Active Inference.

* software teams and interactions.

* continual learning <---> multi-agent work.


Lifelong learning group. ICLR -- coming up (this next week, April 24). Workshops, tutorials.

* learning representations. Post-2012 (pre-2012, feature engineering).

* University at Albany, UCSD, UIUC (where do we have relationships?)


Ideas for Summer 2025 cohort -- people who didn't get slots, what to do --> open-source meetings.


Data Science --> more applied space. Data + Direction --> get a few people from our connections.

* innovationstrategymentor.substack.com

* differences between academia and industry. Beyond quality checks.

* data nutrition (data labels, intermediary explanation.

* Summer cohort post -- what do we want to do?

* NeuroTech @ UIUC --> interested in more formal projects.

## TRANSCRIPT    
0:04     
hello how are you doing today     
0:14     
all right so let's see uh in terms of meetings     
0:19     
this week we had people worm and that was a discussion     
0:25     
on some proposed work on paper graphs and how that might apply to sea     
0:32     
elegance and biology in general uh going over some of the uh     
0:39     
different you know kind of meta aspects of that some of the ways which in which     
0:44     
you implement hyperrows and things like that um and     
0:50     
then we also talked about cential cells and C elegance and how to think about     
0:56     
the lineage tree cential cells are cells of multiple nuclei and a single cell body that's you     
1:05     
know connected through cytoplasm so there are a lot of instances of that in     
1:10     
C elegance phenotype but in other phenotypes as well um yeah so that's     
1:17     
that was divor and that the only other meeting we had this week once     
1:23     
again um as for our open source meeting not sure when we'll start that up again     
1:31     
maybe at the first of the month or in that week so whatever Friday that is     
1:37     
first Friday of May we might do that but we'll see     
1:45     
and around that same time of course we have the Google Summer code selections so we make we don't make     
1:53     
those public usually until the announcements are made by the program so     
1:58     
that's right around the first of May usually like the third or fourth so that's uh coming up and     
2:07     
hopefully we get the people we want sometimes we don't get every slot that     
2:13     
we want but that's okay we make do and     
2:19     
um so in years past we've had more it always happens we have more applicants     
2:25     
than we have spaces for we get a lot at a certain number of slots by program and     
2:31     
then we have to select uh the highest rated proposal and     
2:37     
sometimes it's what we want to do over you know um what what makes sense kind     
2:43     
of for us as opposed to you know any other kind of     
2:49     
direction and so that's that all goes into the decision so if people aren't     
2:56     
selected they're perfectly welcome to join us and uh try     
3:02     
to do that project as part of our open source group which we've done in the     
3:08     
past uh last year we had uh one person do that person who was working on     
3:15     
reinforcement learning um and so you know we we can always accommodate that     
3:20     
for people as well okay     
3:26     
so if you uh you know good luck to everyone who     
3:32     
applied and we'll see uh what the outcome is at the     
3:38     
beginning all right so last week we talked about this paper metal learning models of     
3:43     
cognition and this was a paper where we were introduced to this     
3:49     
uh model of metalarning and we went through all the basian uh rules and things like that and     
3:55     
thinking about how one can apply basian methodology to metalarning we also talked about some of     
4:03     
the other uh ideas they had for this so they had these uh four different     
4:10     
arguments for metalarning so they had the computational intractability     
4:18     
argument the inference problem the ability to manipulate a     
4:24     
learning algorithm's complexity and then they had these narrow scientific insights this was uh     
4:32     
where we left off roughly and we were talking about this rational     
4:38     
analysis of cognition so this isn't just useful for artificial intelligence this is     
4:44     
useful for uh understanding cognition and so they     
4:49     
were talking about rational analysis of cognition they were making connections     
4:55     
with reinforcement learning which will become important for today and they're talking about a number     
5:02     
of other types of qu interesting questions or directions     
5:09     
so they have this uh paragraph here they say we place an emphasis on the second     
5:16     
aspect in the present article and advocate for using fully converged metal learning algorithms as a replacements     
5:22     
for the corresponding basian models for rational analysis of cognition so     
5:28     
they're actually not using like a basian model per se they're     
5:34     
using an analog of the basian and they're building an algorithm that's based on the basian model and     
5:41     
then they're going to have those models you know let them run to convergence and     
5:46     
then make statements about publishing and about intelligence and all     
5:51     
that okay so that's where the rest of the paper goes however it is important to mention that     
5:57     
we believe that metal learning can also be a valuable tool to understand the process of learning to learn itself so     
6:05     
this idea of learning to learn is the key here so we talked about the basian     
6:13     
method as being this sort of uh you know y given x situation where it's     
6:21     
conditional probability so or conditional likelihood is more     
6:27     
what they're kind of getting at so you know if I have one thing that's true     
6:32     
what's the likelihood that this other thing will be true and you know you think about coin flips     
6:38     
where you flip a coin and in frequent test approach you have this flipping of     
6:44     
the coin and the probabilities that you get are all independent of one and it     
6:49     
assumes that there's an independence of that um process so every coin flip is     
6:56     
independent of every other coin flip and you get a probability of     
7:04     
0.5 and so that's uh the sort of frequentist view in the     
7:11     
basian view you might have some conditional probability or conditional     
7:16     
like that is that the outcome of a coin     
7:21     
flip is dependent on the outcome before so you know this is particularly handy     
7:28     
if you have a run of heads and then you know we can make a statement that says     
7:33     
the likelihood of heads coming up again is a certain amount given the past     
7:41     
outcomes and the likelihood becomes lower and lower as we get deep into the run of heads and then finally we get a     
7:49     
tail which is becomes more and more likely now things like that so we're     
7:55     
looking at patterns within our time series patterns within     
8:00     
our the structure of the system we're trying to predict and we're finding things that maybe you know that may be     
8:08     
uh conditional that it's less likely that we have an outcome happen 40 times in a row that we     
8:18     
we have a statement to to make to we can encapsulate that in a mathematical     
8:25     
statement okay so that's um a little bit about that in the next section we'll     
8:32     
outline several arguments that support this approach however it is important to mention that we believe that metalarning     
8:39     
may also be a valuable tool to understand the process of learning to     
8:45     
learn in this context several intriguing questions arise the first one is at what time does     
8:52     
meta at what time scale is metalarning take place in humans so we talked about     
8:59     
our time scales from last time where we have things happening at the millisecond     
9:04     
level we have things happening at the seconds level the minutes level at the     
9:10     
hours level and at the days level and maybe even at the years level so we have you know some sort of     
9:17     
cognitive event or some sort of stimulus and that gets processed rather quickly within maybe several hundred     
9:24     
milliseconds and we can measure that with uh EEG or some other     
9:29     
electrophysiological thing and then we have things that happen at seconds or     
9:36     
minutes which could be you know u reciting a poem or having a discussion     
9:43     
during a coffee break or you know     
9:48     
practicing riding a unicycle or something like that which we might be     
9:53     
into you know minutes to hours and then we have short-term memory     
10:00     
which of course is are things we hold in a short-term memory store and access as     
10:06     
we do those kinds of things and then we have long-term memory which encodes     
10:12     
things for long-term storage and then you know we have hours and and years then which are     
10:21     
sort of historical memory or reproduction or things like that     
10:26     
um we also have naturalistic cognition which is this uh continuous     
10:34     
stream of activity and those can take place in multiple time skills so where     
10:40     
does metal learning take place if you have metal learning you know if you have something like uh if     
10:47     
you learn how to say ride a unicycle or you have a conversation with someone and you learn some interesting fact and you     
10:53     
maybe put it in short-term memory and then that gets encoded into long-term     
10:59     
memory and then you maybe have this process of metalarning where maybe you learn several interesting facts during     
11:06     
that conversation and you remember all of them include them     
11:12     
uh is does metalarning take place then or does metalarning take place much     
11:18     
more in a much more expedient way in other words do you do sort of online     
11:24     
metalarning as you encounter facts in the world so if you see something new     
11:31     
you just kind of synthesize it with what you previously you recall some memories and then you make this new inference     
11:39     
it's basically uh y which is this new experience given x which is the previous     
11:45     
experience and that gives you this metalarning prior     
11:51     
basically okay so that's the first question the second question is how much     
11:56     
of it is due to test specific adaptations so is metalarning a sort of     
12:02     
a thing that we learn you know a thing that we adapt to so if we are in an environment of     
12:10     
learning do we have this sort of adaptation that is basically     
12:16     
metalarning so in other words is it uh if we do something     
12:22     
like learn how to use a computer um is that sort of do we use metalarning     
12:30     
as an adaptation to improve that process or if we learn how to play a     
12:36     
stringed instrument we use metal learning to improve performance that process     
12:43     
number three is how much of it is based on evolutionary or developmental processes     
12:48     
so you know do we have does this is this is metalarning sort of embedded in     
12:56     
development or evolution and again those time scales become     
13:01     
important because development is this you know sometimes years long     
13:07     
process evolution is many many years so you know it's     
13:13     
generational and so how does metal learning then compare     
13:19     
Um so that's that's another question and so those are three     
13:25     
questions that they bring up while we agree that these are important questions they're not the focus of this article     
13:32     
okay but that's those are good things I think to frame everything under and     
13:37     
understand kind of where the what the consequences or what the outcomes of metal     
13:44     
are okay so you have part two here why not basian     
13:50     
inference so again they they do a lot of introduction of basian modeling and they     
13:57     
use this sort of way to think about it um and and of course the sorts of     
14:02     
algorithms they want to use the sort of uh brain inspired models they want to use but the baze rule and uh basian     
14:11     
approach is important in how that's structured but why not just use you know     
14:18     
uh basian influence directly so we have just argued that is     
14:24     
possible to metal learn basal learning algorithms what are the implications of this     
14:29     
So uh basing inference has already established itself as a valuable tool     
14:35     
for building cognitive models we have a lot of cognitive models that rely on basian     
14:41     
inference in this section we provide four different arguments that highlight the advantages of metalarning for     
14:47     
building models of cognition so this is where again     
14:54     
uh we I don't know if they're conflating well they're not conflating basian models they're kind of zooming out and     
15:01     
saying uh you know we're really interested in     
15:07     
metal but we can use basian inference to best understand metal so     
15:14     
[Music] uh many of these arguments are novel and have not put in been put forward     
15:20     
before uh and so their arguments are as such the first is intractable inference     
15:27     
so this is the first argument metalarning can produce approximately optimal learning algorithms even if exact basian     
15:34     
inference is computationally intractable so we can have sort of     
15:41     
a we can use basian inference maybe not as a exact solution but as an     
15:48     
approximate solution and we can have this sort of metalarning as the     
15:55     
outcome so we can if we use a metalarning approach we can produce approximately optimal learning     
16:02     
algorithms so we don't have to have the exact basian solution we just need to     
16:09     
sort of have an inferential take an inferential approach and metalarning     
16:14     
will get us there here's an important point metalarn inference also never requires an explicit     
16:21     
calculation of the exact posterior or posterior predictive distribution so     
16:27     
when we talk about something that's metalarn learned from pri previous evidence synthesizing that we don't     
16:35     
really need to calculate out an exact posterior posterior predicted     
16:40     
distribution remember we're doing inference in the following way we have this this prior distribution we have     
16:48     
observations and then we have this posterior distribution which is     
16:54     
predictive and so what what does metal learn inference do it performs     
16:59     
approximately optimal inference via a single forward pass through the network     
17:05     
inference in this case is approximate because we have had to determine a functional form of the predicted     
17:11     
distribution the chosen form may deviate from the true form of the posterior predictive distribution which in turn     
17:18     
leads to approximation errors so basically they try to get it as close as     
17:24     
possible and then if they don't get it as close as possible you've got these approximation errors and then you try to     
17:31     
minimize that error so that's basically it then um the second     
17:38     
argument is that metalarning can produce optimal learning algorithms even if it     
17:45     
is not possible to phrase the corresponding inference problem in the first place     
17:50     
so in other words if we can't define the exact inference problem if we     
17:56     
can't state the problem in exact terms we can still get optimal learning     
18:01     
algorithms remember it's hard to pose the an exact problem which means in     
18:08     
basian inference terms you need to be able to specify a prior and a likelihood     
18:14     
so you need to be able to specify the prior distribution then take those     
18:21     
observations and produce a likelihood that is     
18:27     
reasonable so that's basically what we're doing so it's you know you have to have that well     
18:34     
defined in order to have a shot at getting some you know something decent     
18:39     
out of a basian influential approach if we turn to basine decision theory Savage     
18:45     
in 1972 made the distinction between small and large world problems a small world problem is one in     
18:52     
which all relevant alternatives their consequences and probabilities are low     
18:57     
so that's where we have something that's exactly defined but also is a rather small problem where we can get our hands     
19:05     
around the the probabilities and the consequences basically knowing all of     
19:10     
the outputs and so that's a small problem I guess and this is contrasted with a     
19:18     
large problem or a larger world problem in in which the prior or the likelihood     
19:24     
can or likelihood cannot both be identified so you can't necessarily get     
19:30     
a good prior distribution because there are a lot of observations in the past that we can't access     
19:38     
we also can't access the likelihoods because there are a lot of things we can't directly     
19:44     
observe so that's a large problem and it's very hard to define what the prior     
19:51     
looks like and what the corresponding lake would put so number three is     
19:57     
resource rationality and it's stated as metalarning makes it easy to manipulate     
20:03     
a learning algorithm's complexity and can therefore be used to construct resource rational models of learning     
20:11     
so this is where we have metalarning can manipulate the learning algorithms complexity     
20:18     
itself and so then we can construct resource rational models cover in 1999 put forward a     
20:27     
dichotomy that will be useful for our following discussion he refers to the algorithmic complexity of an algorithm     
20:34     
as the number of bits needed to implement by contrast he refused to refers to the     
20:40     
computational complexity of an algorithm as the space time or effort required to     
20:45     
execute it so it's implementation and execution it is possible to cast many     
20:51     
approximate inference schemes as resource rational algorithms so this is a specific type of     
20:58     
algorithm the resulting models typically consider some form of computational complexity     
21:05     
so in MCMC methods uh which is a specific type of method we     
21:11     
can use uh and basian learning and inference is important in MCLC     
21:18     
methods um computational complexity can be measured in terms of the number of drawn     
21:24     
samples drawing fewer samples leads to faster inference at the cost of introducing a     
21:31     
bias uh so this is where we have this sort of sampling     
21:37     
process we draw a certain number of samples and we get our prior     
21:42     
um and so we can do this uh quickly we can do this sort of you know for certain     
21:50     
problems where we might need a a fast answer or     
21:55     
there's just so much data that we can't reasonably sample all of it we can do     
22:01     
that we can get faster inference but we get a bias in the data we might sample     
22:06     
from a certain part of the distribution uneven in variational inference on the     
22:13     
other hand it is possible to introduce an additional parameter that allows us     
22:18     
to trade off performance against the computational complexity of transforming the prior into posterior distribution     
22:27     
and so uh other frameworks are building resource rational models such as rational meta reasoning can only also     
22:35     
only target computational complexity so I'm I'm not going to get     
22:42     
too much more into uh these type of models but just suffice     
22:49     
it to say that MCMC models fall into that category variational bay falls     
22:55     
under that category and so     
23:00     
forth uh this idea of computational complexity is interesting     
23:07     
um and algorithmic complexity by extension because a lot of times you     
23:13     
know we have problems that are of different varying complexities and it's you know worth I     
23:21     
think thinking about that i don't think people talk about that enough in a lot     
23:26     
of the especially the applied machine learning literature but especially just     
23:32     
thinking about different uh types of computational problems especially related to cognition uh then     
23:40     
argument four which is neuroscience that argument is metalarning allows us to integrate     
23:46     
neuroscientific insights into the rational analysis of cognition by incorporating these     
23:53     
insights into model architectures so now we're getting into getting     
23:59     
from sort of maian inference sort of the details of that     
24:06     
the computational complexity and now to sort of the architecture     
24:11     
itself which is it's biologically inspired in addition to providing a framework for understanding many aspects     
24:17     
of behavior metal learning offers a powerful lens through which to view the     
24:23     
brain structure and function that we're interested in uh for instance Wang     
24:29     
presented observations supporting the hypothesis of prefernal circuits may constitute metaw     
24:36     
reinforcement or a meta reinforcement learning system u this is where we're getting into     
24:43     
reinforcement learning because of course reinforcement learning happens in the brain as well as as a computational     
24:51     
process we have examples of reinforcement learning in neuroscience and I suspect that's kind     
24:57     
of where they're headed with the the reinforcement learning aspect that you can build these     
25:03     
circuits or these I guess architectures that mimic circuits that implement     
25:11     
reinforcement so you have these meta reinforcement learning systems um for a computational     
25:19     
perspective metalarning strives to learn a faster inner loop learning algorithm by an adjustment of neural     
25:26     
network weights in a slower outer loop learning process within the brain an analogous     
25:32     
process plausibly occurs when slow dopamine-driven synaptic change gives     
25:40     
rise to reinforcement learning processes that occur within the activity dynamics     
25:45     
of the peripheral network this allows for adaptation of much faster time     
25:51     
scales so we have two things here we have sort of     
25:57     
this circuit that we can use as inspiration for a system that basically has a     
26:05     
feedback a set of feedback loops in it so you can reinforce learning easily     
26:10     
with feedback loops you can actually enforce metal learning with feedback loops as     
26:16     
well because you have these prior experiences which allow you to build a     
26:22     
prior distribution and then you have reinforcement of that prior distribution     
26:27     
by observations by the current state of that circuit and then you have an ability to     
26:35     
build sort of representations that are well supported by     
26:40     
reinforcement versus representations that are not and then that gives you     
26:47     
metal so you have this faster inner loop learning and this slower outer     
26:53     
loop the faster interloop learning may be uh where you actually     
26:59     
reinforce the things that you maybe observe once of you observe them again     
27:04     
and again they become sort of inscrable or they become undeniably     
27:12     
true I guess or you might just see them a lot and then slower out recording     
27:19     
might allow you to build a model of metal that is what have I learned and how does it fit     
27:26     
together or what is it how do I distinguish between different alternatives that I've     
27:32     
learned so you know all of this sort of is to say that you have this     
27:38     
architecture that can be described in sort of this basian model and it can     
27:45     
also operate as this learning and metalarning     
27:51     
system within the brain and an analogous process plausibly occurs okay we     
28:00     
did all right so we we are able to have adaptation on     
28:06     
much faster time scales this perspective recontextualized the role dopamine     
28:11     
function in reward-based learning and was able to account for a range of previously puzzling neuroscientific     
28:18     
findings so this is where they talk a little bit about uh the neuroscience of     
28:23     
reinforcement learning and meta reinforcement learning so     
28:32     
forth importantly the direction of exchange can also work in the other direction with neuroscientific findings     
28:39     
constraining and inspiring new forms of metal architectures so for example in this resource uh the     
28:46     
lack at all 2018 showed that recurrent networks of spiking neurons are able to display     
28:54     
convincing learning to learn behavior including in the realm of reinforcement learning episodic meta     
29:02     
reinforcement learning which is your redder with all 2018 these type of architectures are     
29:08     
also heavily inspired by neuroscientific accounts of complimentary learning     
29:13     
systems in the brain which is covered by Mlen McN and O'Reilly 1995     
29:20     
both of these examples demonstrate that metalarning can be used to build more biologically plausible learning     
29:27     
algorithms and thereby highlight that it can act as a bridge between Mars     
29:34     
computational and implementational level so you if you remember Mars three levels     
29:40     
you know that two of those levels are computational and     
29:46     
implementational okay um finally the metalarning perspective not only allows us to connect machine learning and     
29:53     
neuroscience via architectural design choices but also uh via the kinds of     
29:59     
tasks that are of interest so uh functional specialization     
30:04     
in neural circuits which has been widely observed in biological brains arises     
30:10     
spontaneously as a consequence of task demands convolutional neural networks     
30:15     
trained on both face and object recognition depicted emergent segregation on the basis of these tasks     
30:23     
uh so we get this sort of emergent cognition from this metalarning system     
30:29     
and so they go through u some things about metalarn models they talk about them a little bit     
30:36     
more they talk about language as well conductive biases which are     
30:43     
important um model based reasoning exploration which is also     
30:49     
important cognitive control and then the question why why is     
30:56     
not everything metal so why don't we just use metal learning for     
31:01     
everything so um metalarning of course is a useful tool for constructing     
31:07     
cognitive models but it's important to note that we do not claim that metalarning is the ultimate solution to     
31:14     
every modeling problem instead it is essential to understand when metalarning is the right tool for     
31:21     
the job and when it is not so they give some examples of why it's not always the     
31:27     
best way to look or to implement a learning system the first is lack of     
31:33     
interpability so the most significant detriment is     
31:39     
that metalarning never provides us with analytical solutions that we can inspect     
31:44     
analyze and reason about so this is where you know we have     
31:50     
this distinction between basian exact basian models and     
31:56     
metal uh so take take as an example the data generating distribution we     
32:01     
encountered earlier for these assumptions a closed form expression of the posterior predictive distribution is     
32:08     
available by looking at this closed form expression researchers have generated new predictions and subsequently tested     
32:16     
them by performing the same kind of analysis with a metalarn model is not as     
32:21     
straightforward we do not have access to an underlying mathematical expression     
32:27     
which makes a structure exploration of theories much harder so I guess one of the differences     
32:33     
then between the metalarning and the sort of the approximate basian model is     
32:38     
that you're just really basing your answer your final sort of way that the     
32:44     
algorithm is implemented on sort of the structural similarity and not     
32:51     
necessarily following a mathematical model directly so in other words there's something like a prior     
32:59     
distribution there's something like observations there's something like a posterior distribution it's not even     
33:06     
that it's being estimated it's that you know it's being kind of implemented     
33:12     
uh in re you know in real terms so you know uh basian models are of course     
33:19     
highly theoretical in terms of their mathematical abstraction but implementing them in the     
33:25     
real world of course is a little bit different okay that being said there's     
33:31     
still ways to analyze a metal model's behavior um and so we can do this uh we     
33:38     
don't so we don't have full interperability we can't account for every component     
33:44     
like we couldn't say how metalarning arises directly we can't say that this is the likelihood that led to this     
33:53     
outcome but we can you know sort of analyze a mental model's     
33:59     
behavior uh but we can also you know take these     
34:04     
kind of blackbox models and use tools from cognitive psychology to analyze what's going on     
34:11     
so we can treat uh models as participants in a psychological experiment have them perform tasks and     
34:18     
then collect the data and analyze it according so that might be a way forward     
34:24     
is to just have our metalarning models produce output behave in the real world and then     
34:31     
measure what they're doing and see how that looks you might even get a number of model     
34:37     
implementations and then you know have them as like a a study where you have a     
34:42     
number of subjects where you're all training on the same uh     
34:49     
test we can only we okay so there's also intricate training processes so when     
34:56     
using the metalarning framework one also has to deal with the fact that training neural networks is complex and takes     
35:03     
time neural network models contain many moving parts like weight initializations     
35:08     
or the used optimizer that have to be chosen appropriately such that training can take off in the first     
35:15     
place training itself may take hours or days until it's finished so this is part     
35:20     
of this time scale issue when we want to modify assumptions     
35:25     
and data generating distribution we have to retrain the whole system from scratch al together thus although the processes     
35:32     
of iterating over different environmental assumptions is conceptually straightforward it may be     
35:38     
time consuming basian models can in comparison sometimes be more quickly     
35:43     
adapted changes in environmental assumptions okay so basically if let me assume I     
35:52     
wanted to explain human behavior through a metalarn model that was trained on the data generating distributions and these     
35:59     
equations but found that the resulting model does not fit observed data well so     
36:05     
a lot of times your model won't fit the observed data and so you know this is     
36:10     
something that you have to generate alternative hypothesis for     
36:17     
ultimately that can hurt you if you're just using a strictly basian interpretation     
36:23     
your prior your prior represents a hypothesis and if that hypothesis     
36:30     
doesn't fit the observations then your likelihoods aren't going to be very     
36:36     
accurate so this is where we have this difference between metalarning and sort     
36:42     
of a strict basian representation     
36:48     
uh there is furthermore no guarantee that a fully converged metalarning model actually implements a B optimal learning     
36:55     
algorithm while we are able to compare it to analytical solutions for simple cases like our insect length example     
37:02     
which we talked about last week where they measured the length of insect uh body parts and they try to predict     
37:10     
species and things like that um it is generally impossible to verify that a     
37:17     
metal learning algorithm is optimal indeed there are reported cases in which metal learning failed to find the B's     
37:23     
optimal solution we believe the issue can be somewhat mitigated by validating metalarn models in various different     
37:30     
ways but ultimately future work should come up with techniques to verify     
37:36     
metal so then in summary they have this question and this is the thing that's     
37:42     
been bothering me i think throughout the paper is they kind of swap out     
37:47     
metalarning and basian inference and they're not the same thing     
37:53     
we can base our metalarning on basian inference we can model it after basian inference but it's     
37:59     
not they're competing frameworks basically um and so you know this is     
38:06     
something that we can look at their different strengths and weaknesses we can use like     
38:13     
a strict basian form of basian inference we can use a metalarning model um and     
38:19     
but they argue that the metalarning framework does not and will not replace basian inference but instead will     
38:25     
complement it broadens our available toolkit and enables researchers to study questions that were previously out of     
38:32     
reach and then they basically kind of get turned just to metalarning and talk     
38:40     
about domain general models of human learning what does the future hold for metalarning the current generation of     
38:46     
metal learn models cognition this is almost exclusively trained on the data generating distribution of a specific     
38:54     
problem fail while this training process enables them to generalize new tasks inside the problem they are unlikely to     
39:02     
generalize to completely different domains we would for example not expect a metalorg algorithm for a challenging     
39:10     
maze navigation task if it was only trained to predict the lengths of insect     
39:16     
species and so this turns to sort of the basis for cognitive modeling in domain     
39:22     
specific modeling and they agree with new circa 1992 this     
39:28     
is uh some of the earliest work on the sor architecture     
39:34     
uh where they're actually were looking for not to build a cognitive     
39:40     
architecture but to build these unified theories of cognition and so this is one     
39:45     
of the point points here is that you know we build cognitive architectures we     
39:51     
build these things to learn about cognition not necessarily to simulate     
39:57     
things um you know we want to simulate things we want to build like an     
40:03     
artificial form of the of cognition and that's interesting but we also want to     
40:08     
build theories of cognition from those models so we agree with new that unified     
40:14     
theories of cognition are the only way to bring this wonderful increasing fund of knowledge and intellectual control     
40:22     
ideally such a unified theory should manifest itself in a domain general cognitive model that can not only solve     
40:30     
prediction tasks but also capable of humanlike decision making category     
40:35     
learning navigation problem solving and so on we consider the metalarning     
40:41     
framework the ideal tool for accomplishing this goal is it allows us to compile arbitrary assumptions about     
40:48     
an agent's beliefs of the world uh and its computational architecture and combine both of those     
40:55     
into a popular one okay so that's I think enough on that paper so that was uh this paper     
41:03     
here metawarn models of cognition and that so I wanted to go     
41:10     
over that the second part of that I thought that was important for kind of motivating the other things I want to     
41:16     
talk about today so yeah I think it's an interesting paper like I said I think     
41:22     
they I don't want to say they conflate manarning and basian inference they're     
41:27     
approaching it from the standpoint of looking at basian inference is something that we do uh in various     
41:34     
contexts um and you know we kind of understand how to do build algorithms     
41:40     
around that and then comparing that or contrasting that with things like     
41:45     
metalarn or learning delay when a structure is similar you can implement     
41:52     
uh basian inference in metalarning but at the end of the day     
41:58     
you know metalarning maybe different metalarning techniques whether or not they're basian whether or not they     
42:03     
actually implement basian inference is um in in the way it's defined     
42:10     
mathematically is u the question so I I wanted to move on another set of like I     
42:17     
have three other papers here in this group and this next paper then is I     
42:22     
think this was also in the slack i think VI also put this in the slack um I think     
42:28     
it was in the basis in the Benberg vehicles uh     
42:34     
channel yes okay and so this is um was a conference paper from     
42:43     
2023 and this is learning meta representations for agents and multi-     
42:48     
aent reinforcement so this is again kind of focusing on reinforcement learning     
42:55     
so like in the last paper we talked about basian inference we also talked     
43:00     
about reinforcement and so um metalarning     
43:05     
involves this sort of reinforcement this sort of um observing     
43:11     
prior things that happened in the past and then observing the world now     
43:17     
figuring out what's important then those get reinforced in a posterior     
43:23     
distribution And then that's kind of how you implement metal so that's basically     
43:30     
the approach that we saw in the last paper and you can follow that out and you can build an algorithm around     
43:37     
that this is where you're building meta representations for agents and so this is where they have to     
43:44     
learn those representations so the abstract reads in multi multi-     
43:50     
aent reinforcement learning the behaviors that agents learn in a single markov game which is     
43:57     
mg uh are typically confined to the given agent every single markov game induced     
44:03     
by varying the population may possess distinct optimal joint strategies and     
44:09     
game specific knowledge which are modeled independently in modern multi-agent reinforcement learning     
44:15     
algorithms in this work our focus is on creating agents that can generalize across     
44:21     
population varying mark games instead of learning a     
44:27     
unimodal policy which is of course there's a distribution there     
44:34     
uh each agent learns a policy set comprising effective strategies across a     
44:39     
variety of games so we propose meta representations for     
44:44     
agents or MRA that explicitly models the game common game specific strategic     
44:51     
knowledge so this is where you have uh different types of knowledge you have     
44:58     
game common knowledge and game specific knowledge or game specific strategic     
45:03     
knowledge by representing the policy sets of multimodal league policies     
45:09     
that gain common strategic knowledge in diverse strategic modes are discovered     
45:14     
through an iterative optimization procedure we prove that by approximately     
45:20     
maximizing the resulting constraint mutual information objective the policies can reach Nash     
45:28     
equilibrium in every evaluation markoff game the latent space is sufficiently     
45:33     
large when deploying uh meta representations for agents in practical     
45:39     
settings with limited latent space sizes best adaptation can be achieved by     
45:45     
leveraging the first order gradient information extensive experiments demonstrate the effectiveness of MRA for     
45:54     
matter representations for agents and improving training performance and generalization ability and challenging     
46:03     
evaluation so this is uh quite technical in the sense     
46:08     
that it's kind of hard to follow where they're going with this     
46:14     
um so a markov game if we can find out what that what that is     
46:30     
exactly okay uh so we start here the behavior of agents learn in the single     
46:36     
markoff game highly dependent on the environmental settings especially the     
46:41     
number of agents such as population many multi-agent reinforcement learning or moral     
46:48     
algorithms are developing games in a fixed population um and so sometimes we have     
46:56     
problems with generalization in in settings like this which is where the policies learned in a single markoff     
47:03     
game are brittle to the change of agent number recent works have experimentally     
47:09     
shown the benefit of knowledge transfer between markoff games of different populations     
47:15     
uh which is required to perform between successive games     
47:21     
um in this work we are concerned with learning multi- aent policies that generalize across Markoff     
47:28     
games and so let's see if we can find out what a markoff game is     
47:38     
okay for games induced by varying the population the distinct optimal policies     
47:43     
are determined by different strategic relationships between agents which we     
47:49     
characterize as game specific knowledge for example in a Pac-Man game that is     
47:55     
populationally dominated by ghost agents the game specific knowledge for Pac-Man     
48:01     
is to focus on the ghost agents positions for survival however as all Pac-Man agents ignore other Pac-Man     
48:08     
agents positions they are unaware of collaborating in their ability to collect food dots in evaluation games as     
48:16     
poor so one example they give is Pac-Man so a Markov game is essentially where     
48:22     
you have agents that use this sort of markoff model to model their behavior so     
48:30     
in Pac-Man the ghosts um have this sort of repertoire of     
48:37     
behaviors and they're implemented using a markoff chain and then the Pac-Man     
48:44     
agents of course could collaborate and have a coordinated strategy but they     
48:50     
don't so you know this is where this affects the knowledge of the game or     
48:56     
what you need to know to play the game so you have to know for example that the ghosts are going to behave sort of     
49:03     
randomly you also know that you're not going to be able to collaborate with your other fellow Pac-Man to get an     
49:11     
advantage of people so that conditions the     
49:17     
different strategies that are employed     
49:22     
one potential fix is to learn the representations which can serve as the gain common knowledge and generate a set     
49:29     
of policies that output the best effort actions and condition on different     
49:35     
suboptimal strategic relationships between agents so this may force Pac-Man to pay     
49:43     
more attention to other Pac-Man in spite of the game being less dominant although these policies can be     
49:51     
suboptimal in the training markoff game uh they have the potential to perform     
49:56     
well in the evaluation games in a zero shot manner this motivates us to learn     
50:01     
diverse strategies so that even if not all knowledge variations are covered during training the game common     
50:08     
knowledge can be learned so you you know you want to be able to train agents on     
50:14     
all the things that they might see and so this is where you get     
50:20     
um you know you you want to learn as many strategies as possible so you know you have this gain     
50:26     
common knowledge which is okay there's something like this that you might encounter and so you might not uh be     
50:34     
able to learn a specific variation of a rule but you know things are very     
50:40     
similar to that better generalization is thus achieved     
50:45     
since we only need to fit the best strategic relationship in the     
50:51     
evaluation so this is kind of the intuition that they're coming into this so they're formalizing this by proposing     
50:57     
meta representations for agents for MRA to discover the underlying strategic     
51:03     
structures so you basically want to learn how the game is played it's like     
51:10     
if I tell you the rules of a game you know that will tell me     
51:16     
how strategies will implement i mean strategies will be implemented within the framework of those rules if I learn     
51:23     
the rules of the game I can kind of figure out what the strate what you know what kind of strategy might be employed     
51:30     
i know basically what strategies will be employed and so I can from there I can     
51:37     
sort of build and but it's not just learning the rules of the game you're learning other things you're learning     
51:44     
potential solutions and you're learning other attributes of the environment     
51:52     
specifically by meta representing the policy sets with a multimodal latent policy suite they gain common knowledge     
51:59     
in diverse strategic modes are captured through the iterative diversity optimization we prove that by     
52:05     
approximately maximizing constrained mutual information objectives the laten policies can reach Nash     
52:12     
equilibrium in every evaluation gain if with a sufficiently large latent     
52:19     
space uh when deployed in limited size latent spaces fast adaptation is     
52:24     
achieved by leveraging the first order gradient information we further empirically     
52:30     
validate the benefits of MRA which is capable of boosting training performance     
52:36     
and extrapolating of a variety of validation so they give a mathematical definition     
52:42     
of a markoff game n agent Markoff game M is defined     
52:48     
by the state space S action sets A1 through A and observation sets O1     
52:54     
through O1 so we have observations we have actions and those are two sets     
53:02     
um that operate in a state space for any agent I included in one to N oi included     
53:11     
in OI is an observation of the global state S the state transition and reward     
53:17     
function for agent I are defined in this term um and they're defined as this interval     
53:25     
from 0 to one respectively where uh delta s denotes the set of discrete     
53:30     
probability distributions over us the joint strategy then is denoted as pi pi     
53:38     
1 to pi n where pi i is the strategy of agent i and pi negative i is the joint     
53:46     
strategy excluding it so you have uh this uh joint dis     
53:52     
strategy and then you have joint exclusion so you have like these overlapping you have basically this vin     
53:59     
diagram of the uh exclusionary area then diagram in the following sections we     
54:06     
study the markoff games with discrete states and action spaces so something like I guess like Pac-Man would be a     
54:13     
good example uh where you have an action space in discrete states and you define     
54:19     
it in terms of the strate joint strategies and disjoint     
54:27     
strategies in this work we consider the ro symmetric markoff games where     
54:32     
homogeneous agents are within with the same reward function and action space so     
54:37     
they're the same you know you can have I guess uh heterogeneous agents um where     
54:44     
they have different reward functions and different action spaces but in this case we're training them all in the same uh     
54:51     
in the same sort of world so we could roll asymmetric markoff games I guess     
54:57     
but they don't want to do that it's too complex uh the number of types of homogeneous agents is denoted as     
55:05     
H uh so for example an agent of value two and an n agent Pac-Man game     
55:12     
representing Pac-Man and the ghost agents so you have uh I guess you would     
55:18     
have uh two types of agent so you have Pac-Man and you have the     
55:24     
ghosts and they have different reward functions and action spaces homogeneous agents are symmetric in each     
55:31     
game changing the policy of an agent with another homogeneous agent will not     
55:36     
affect the output so if we swap out Pac-Man or ghosts they basically follow the same rules     
55:43     
population varying markoff games including training and evaluation markoff     
55:48     
games in other words varying N1 and N2     
55:53     
um where you have Pac-Man and ghosts uh are the same are with the same H and     
55:59     
states from states at S or described by different transition and joint space     
56:04     
observation action and reward functions     
56:10     
uh then we have this relational representation so this is an opponent modeling framework uh called relational     
56:18     
representation where citations are here this aims to capture the strategic     
56:23     
relationship between agents and output and embedding e for further policy and critic functional     
56:30     
so basically we're trying to get this set of relationships output and embedding and     
56:37     
then use that for further learning so maybe meta learning something like that     
56:42     
specifically consider the observation OI uh of agent I with entities of I uh     
56:50     
where um OIS is agent I's self-properties it's for example it     
56:56     
speed a YJ is agent I's observation of agent J so you can     
57:03     
have agent I can have self properties can measure its own speed we can observe     
57:09     
agent J and its behavior and then have the sort of uh observations of     
57:16     
environmental information such as landmark mark locations and all of those can be     
57:22     
concantenated into a single observation so that's the first part and     
57:28     
then with self attention generating the pair wise relation     
57:34     
uh GI J which is the J entity of agent I     
57:39     
with its egocentric relational graph G by the representation embedding EI for     
57:46     
agent I is formulated in this equation here where we follow the transformer     
57:52     
architecture and that represents our linear function the observation embedding with an AR number of agents     
57:59     
can be res represented with a fixed then they have Nash equilibrium     
58:06     
and they talked about that so every agent in the markoff game M acts according to joint strategy pi at state     
58:14     
S the value of agent I and the expectation of I's discount cumulative     
58:20     
reward so this is in Nash equilibrium uh a common metric to measure the     
58:27     
distance to a Nash equilibrium is Nashcon which represents how much each player or agent means by deviating from     
58:34     
its best response in total and it can be approximately calculated in small games     
58:40     
we denote Nashcom of Y in the Markoff game M is D pi defined this way     
58:48     
um and so with this definition the joint strategy pi reaches Nash equilibrium and     
58:55     
M if and only if DMI equals Z so that     
59:00     
that's basically what they're defining they're basically defining the markoff game mathematically this relational     
59:07     
representation which is some sort of uh I guess a meta representation     
59:13     
um that we can use for further evaluation and then defining things in     
59:19     
terms of Nash equilibrium okay so in a single markoff     
59:25     
game achieving Nash equilibrium gives reasonable solutions and is of great importance to enable generalization in     
59:32     
different markoff games the most straightforward way is the word joint strategy set that contains effective     
59:38     
joint strategies for each markoff game um we denote the set of all     
59:44     
training markoff games as M and the set of evaluation markoff games as M prime     
59:49     
and the goal is to learn an optimal joint strategy that satisfies certain     
59:55     
constraints um and they have the relational representations     
1:00:01     
so this is where this is sort of the implemented architecture of the MRA     
1:00:07     
algorithm where you have self attention you have the decentralized     
1:00:13     
actor the different strategies and then the centralized critic which is used to     
1:00:19     
reinforce the strategies so you see you have this actor critic warning where you     
1:00:24     
have the actors that are uh performing the strategies this meta representation     
1:00:31     
which is the critic that's reinforcing the strategies and then together that's     
1:00:36     
what that's used to produce this     
1:00:44     
output unfortunately although the above design fits well into the multitask moral setup where each test differs in     
1:00:51     
the number of agents there's no guarantee that the resulting agents can generalize in novel evaluation markups     
1:01:00     
so this is where we kind of uh then they present the insights and objectives of     
1:01:05     
our meta representation agents algorithm which is of course to follow up on this     
1:01:12     
model to make sure that you have something that works for um um meta     
1:01:19     
reinforcement or metagent reinforcement multi- aent reinforcement     
1:01:28     
uh then there's this part generalization by strategic knowledge discovery so we want to be able to     
1:01:33     
understand or discover the underlying strategic structures in the underlying games although the effective policies in     
1:01:41     
the evaluation games are never known during training agents can still learn the common strategic knowledge in     
1:01:47     
different behavioral modes solely in the training games in an unsupervised manner with the imposed suboptimal game     
1:01:54     
specific knowledge in particular for population varying games the agents are     
1:02:00     
assign assigned different strategic relationships in other words each agent pays additional attention to some agents     
1:02:08     
while ignoring others instead of learning only one optimal joint policy     
1:02:13     
which we did in the previous example training with multiple strategic relationships enables the unsupervised     
1:02:20     
discovery of behavior modes some of which offer appreciable returns and evaluation     
1:02:26     
markoffs thus when evaluating in novel games the desired policy behaviors can     
1:02:32     
be quickly generated by adaptation in the extreme cases that sufficiently many strategic loans are     
1:02:39     
captured with an extremely large weight in space the desired policy or     
1:02:44     
evaluation games can be directly funded so this is where they get     
1:02:50     
into mathematics of this and these mutual information between G and A condition     
1:02:58     
observation O uh the variable m denotes the basic information of gamem such as the numbers     
1:03:05     
of agents of each set of homogeneous agents so you have this large latent     
1:03:10     
space and diverse actions and you have this diversitydriven     
1:03:16     
objective that encourages high mutual information between G and A for behavior     
1:03:22     
diversity as well as between M and G to extract inspecific     
1:03:28     
knowledge okay     
1:03:41     
uh so they do these experiments here so they conduct experiments in three     
1:03:48     
environments built upon the particle world framework that cover both competitive and mixed games including     
1:03:54     
the treasure collection environment and uh resource occupation environment in a     
1:04:00     
Pac-Man like world so this is where they kind of go through the experimental     
1:04:05     
settings and we won't get into that but we will talk about some of these     
1:04:10     
results so there are benefits of gain common strategic knowledge you see that     
1:04:16     
in these figures here this is these are the figure two benefits of meta representations in     
1:04:23     
three environments so the first one on the left is the treasure collection game the     
1:04:30     
second one to the right is or the resource occupation game then the two on     
1:04:37     
the far right here involve the Pac-Man like world the graph on the left hand     
1:04:43     
side of that those graphs is the P the results for Pac-Man and on the right are     
1:04:48     
the results for the ghost so you see there's an agent performing treasure collection at left and then the next     
1:04:57     
uh graph over we have an agent engaged in resource occupation and then we have a Pac-Man     
1:05:03     
like world represent we we look at the representation of a Pac-Man and     
1:05:10     
then so we're looking at total executed episodes versus episode     
1:05:16     
reward and uh so let's see Um we conduct our first experiments to show the     
1:05:22     
benefits of the proposed method by demonstrating that when training in various markoff games but gained common     
1:05:29     
strategic knowledge can benefit individual training games so in figure two we compared     
1:05:36     
uh MRA and the following baseline methods so they have these different algorithms that they use uh the MADDPG     
1:05:44     
algorithm with relational representations of reptile     
1:05:50     
algorithm baseline with the same network architecture as MRA but agents and their     
1:05:55     
policies only in a single MG which is this baseline so this is baseline     
1:06:02     
reptile MADPG and MRA so you can see in treasure     
1:06:08     
collection MRA outperforms the others in resource occupation MRA also outperforms     
1:06:16     
the others and this happens after uh a number of total executed episodes but     
1:06:22     
early on the MAD BPG actually exceeds     
1:06:28     
performance of the others in terms of resource occupation uh in the Pac-Manlike world     
1:06:34     
we have a more uh heterogeneous result we have the MRA     
1:06:40     
uh outperforming the others in early on for ghost for Pac-Man and then we     
1:06:48     
have really it's hard to see if there's a clear benefit to any algorithm in terms     
1:06:56     
of performance later for the ghosts however we have this divergence of     
1:07:04     
performance for the different models the MR outperforms the other models and the     
1:07:11     
uh the MADPG model actually doesn't do very     
1:07:17     
well later so there are all these different you know kind of applying     
1:07:22     
these different models and comparing them which is interesting because we're     
1:07:27     
in different kind of game settings here so for MRI and reptile the size of     
1:07:33     
the training markup game set M for three environments is four four and three     
1:07:38     
respectively the settings of the training markout games in these three environments are as follows and we     
1:07:44     
talked about that we note that the actual executed episodes of MRA MRA and     
1:07:51     
one M and one markoff game are m times smaller than that for baseline of that     
1:07:56     
uh DPG which reveals the efficiency of the proposed meta representation     
1:08:03     
so the number of executed episodes if it's smaller or if you know they're     
1:08:10     
differences in the number of total executed episodes that can reveal the efficiency of the proposed meta     
1:08:17     
representation comparisons between MRA and reptile validate the effectiveness of MRA the meta represent effective     
1:08:24     
policies in various markoff games due to the existence of game specific knowledge     
1:08:31     
optimal policies in different games are distinct thus in reptile using a unimodal policy to represent them all     
1:08:39     
negatively affects their performance so we don't you know in some cases we     
1:08:45     
want to use um certain types of policies in some     
1:08:51     
games or in some um I guess methods we     
1:08:58     
don't by comparing MRA with baseline and MAD DPG the benefit of the gain common     
1:09:05     
strategic knowledge for individual games is revealed since the baseline agents are trained only in a single game they     
1:09:12     
cannot benefit from such common knowledge even with more episodes executed the common knowledge helps MRA     
1:09:19     
outperform MAD DPG we also evaluate MAD DPG with homogeneous agents sharing     
1:09:25     
parameters which works poorly although the Pac-Man like world is not a zero sum     
1:09:30     
game we still provide cross comparisons results for completeness and this is where we have     
1:09:37     
performance comparisons in multiple games so in this case we have uh these are the     
1:09:44     
training curves in figure three of markoff games constructed by varying minimum of agents from the underlying     
1:09:51     
environments so we have these different games um and we have different numbers of     
1:09:58     
agents so what we can see is as we increase the numbers of agents it changes our results so     
1:10:06     
different algorithms change their performance with by adding agents into     
1:10:12     
the environment so they give some other graphs here um they evaluate zeros     
1:10:18     
transfer and then they have some conclusions so the conclusions are as     
1:10:24     
follows in this paper we propose meta representations for agents that can     
1:10:29     
generalize in markoff games in populations with latent variable policies and relational     
1:10:37     
representations the diverse strategic votes are captured as an approximation to a theoretically justified objective     
1:10:44     
ma effectively discovers the underlying strategic structures in the games that facilitate generalizable knowledge     
1:10:52     
uh our work opens up several new problems theorem one requires the     
1:10:58     
computation as well as an extremely delight in space both of which are impractical although approximations that     
1:11:05     
MRA makes a reasonable obtaining optimal uh values will not always be guaranteed     
1:11:12     
possible future investigations include bounding by imposing restrictions on the     
1:11:17     
evaluation set or enlarging the laten space size with roymmetric game settings mra     
1:11:24     
has benefits in many research problems including deal dealing with population     
1:11:30     
complexity overcoming the multi-agent random exploration bottleneck and     
1:11:35     
adapting faster with the better represented agents a fruitful avenue for future work is to     
1:11:41     
augment MRA by adapting roles to apply other game settings besides achieving uh     
1:11:48     
any may not indicate global optimality in general and then more     
1:11:53     
games therefore we'd like to explore different metrics such as social optimum and correlated equilibrium as future     
1:12:00     
work um for population varying markoff games and we model game specific knowledge the     
1:12:07     
strategic relationship although it may lose the universal universality and broader     
1:12:13     
scopes very general meta learning reinforcement learning algorithms we hope the idea of explicit strategic     
1:12:20     
knowledge modeling and expire algorithms that adjust to the     
1:12:27     
task so that is this paper then there are two other papers     
1:12:33     
here this is the multi-agent learning for multi-root systems this is     
1:12:38     
multi-agent reinforcement learning and I'll just kind of go through the abstract of these and then we'll have     
1:12:45     
maybe a little discussion so this talks about multi- aent reinforcement learning multi-root     
1:12:53     
systems this is a challenging issue in both robotics and artificial intelligence     
1:12:59     
with the everinccreasing interest in theoretical re uh researches and practical     
1:13:04     
applications currently there have been a lot of efforts towards providing some solutions to this     
1:13:09     
challenge however there are still many difficulties in scaling up the multi-agent reinforcement learning     
1:13:17     
multi-root systems main objective of this paper is to provide a survey but not completely     
1:13:23     
on the multi- aent reinforcement learning in multi-root systems     
1:13:29     
after reviewing important advances in the field some challenging problems and promising research directions are     
1:13:35     
analyzed um so this is where they talk about multi-root systems where you you know you need     
1:13:42     
teams of robots instead of individuals um the performance of multi-root systems and redundancy and     
1:13:50     
cooperation contributes to test solutions with a more reliable faster     
1:13:56     
cheaper way so these are things like unmanned aerial     
1:14:01     
vehicles autonomous underwater vehicles drown mobile robots and other robot-     
1:14:07     
based applications in hazardous and unknown environments okay     
1:14:15     
um so the relevance to that here is that there's this emphasis on multi- aent     
1:14:21     
reinforcement learning in this field multi-agent reinforcement learning allows participating robots to learn     
1:14:28     
mapping from their states to their actions by rewards or payoffs obtained     
1:14:33     
through interacting with the environment um and so multi-root systems     
1:14:39     
can benefit from reinforcement learning in many aspects robots are expected to     
1:14:45     
coordinate their behaviors to achieve their goals the robots can either obtain cooperative     
1:14:51     
behaviors or accelerate their learning speed for learning among uh reinforcement learning     
1:14:58     
algorithms Q-learning has attracted a great deal of attention there's also this idea of uh cooperative     
1:15:06     
behaviors through an individual Q-learning algorithm improving learning efficiency     
1:15:11     
through co-learning and K cooperative robots learn faster than they could individual     
1:15:18     
using this uh basically when you're using these     
1:15:23     
kind of collective uh cooperative behavior approaches you're basically sharing     
1:15:29     
perception and learning experience and that can excel accelerate the learning process within the robot     
1:15:36     
group okay that's the the first paper and then the second paper is this     
1:15:46     
BIML which is this paper brain inspired metal reinforcement     
1:15:51     
learning and so this is this talks about um kind of their approach here so sample     
1:15:59     
efficiency has been a key issue in reinforcement So we talked about sampling as part of     
1:16:04     
the basian approach we can also we also use sampling and metalarning but sample efficiency of     
1:16:11     
course is important in getting a proper account of the world both in terms of     
1:16:17     
the priors and of the observations um an efficient agent must     
1:16:23     
be able to leverage its prior experiences to quickly adapt to similar but new tasks and     
1:16:29     
situations rather reinforcement learning is one attempt at formalizing and addressing this issue inspired by recent     
1:16:37     
progress in metalarning or meta reinforcement learning we introduced     
1:16:43     
BIML a novel multi-layer architecture along with a novel brain inspired memory     
1:16:49     
module that will help agents quickly adapt to new tasks within a few episodes     
1:16:55     
we also utilize this memory module to design a novel intrinsic reward that     
1:17:00     
will guide the agent's exploration our architecture is inspired by the findings in cognitive     
1:17:07     
neuroscience that are relevant and is compatible with the knowledge of connectivity and functionality of     
1:17:13     
different regions in the brain uh we empirically validate the effectiveness of our proposed method by     
1:17:20     
competing with or surpassing the performance of some strong baselines in multiple mini grid     
1:17:27     
environments so the what I found interesting about     
1:17:33     
this paper is they kind of use the same approach that we talked about in the previous papers but they have this memory module     
1:17:41     
that's really kind of interesting um so uh aside from this reward or they     
1:17:48     
they propose that there's a intrinsic reward to guide     
1:17:54     
exploration aside from this reward our memory module which consists of an episodic part that resets after each     
1:18:01     
episode and a heavy part which retains information across different episodes of     
1:18:07     
a particular task gives us a performance boost in memory based tasks while helping deal     
1:18:14     
with catastrophic forgetting that comes up in multiple task settings so they have this reinforcement     
1:18:20     
learning intrinsic reward part which is the reinforcement part and then they     
1:18:27     
have this memory module so the episodic part is basically where you get these     
1:18:32     
episodic experiences and you have this short-term episodic memory then you have this heavy     
1:18:39     
input which of course implements heavy inlay which is where you basically     
1:18:45     
retain information by sort of analog of synaptic     
1:18:52     
plasticity and this allows us to have this performance boost in memory based     
1:18:58     
tasks obviously the in heavy encoding and the experience of uh episodes can do     
1:19:06     
that it will allow you to sort of avoid catastrophic forget forgetting sometimes     
1:19:12     
when you switch between tasks you get this catastrophic forgetting of the first task when you go to the second     
1:19:18     
task and it's a common problem in a lot of u neural network systems a lot of     
1:19:25     
artificial intelligence systems so having a strategy for that is important     
1:19:31     
this is I guess part of task generalization where you have you switch     
1:19:36     
between tasks you have to retain that representation of the original task it's     
1:19:43     
good if you have a meta representation but if you don't you have a representation for each of the tasks and     
1:19:49     
the question then is do these representations interfere with one in other words you lose one representation     
1:19:57     
when you build a representation for all of your tests so that's that's kind of why     
1:20:02     
they're doing this so their contribution is summarized as follows they propose a multi-layer     
1:20:09     
architecture that bridges model based and model free approaches by utilizing predictive     
1:20:16     
information on state values so each layer of our architecture corresponds to a different part of the     
1:20:22     
prefrontal cortex which is known to be responsible for important cognitive     
1:20:27     
functionalities such as learning a world model planning and shaping exploratory     
1:20:34     
behaviors so they have resource they have references for this one of the     
1:20:40     
objectives in this architecture is derived from a newly proposed factorization of the log likelihood of     
1:20:46     
trajectories so this says uh this is a technical variation on uh palm dp uh which is     
1:20:55     
where you have this uh predictive of coding ability of the brain that's taken     
1:21:01     
into consideration the second contribution is introducing a     
1:21:08     
neuroinspired memory module compatible with discoveries in cognitive neuroscience     
1:21:13     
uh which will help which is the architecture I talked about before where     
1:21:19     
you have the heavy and episodic parts um this module will help in memory based     
1:21:25     
tasks and give the agent the ability to preserve information both within an episode and     
1:21:31     
across different episodes of some task the design of this memory module is     
1:21:36     
reminiscent of the hippocampus as the main region assigned episotic     
1:21:41     
memory so it's hippocampy inspired at least in terms of the way they describe it     
1:21:47     
then number three proposing a new intrinsic reward based on our memory module so the memory module is separate     
1:21:56     
from the intrinsic reward the intrinsic reward basically uh reinforces I guess the memory     
1:22:03     
module reward does not disappear over time is tag task agnostic and is very     
1:22:09     
effective in a multitask setting it will encourage exploratory behavior that leads to faster task identification     
1:22:18     
okay so that's uh and then they talk about meta reinforcement learning and this is kind of a review of how people     
1:22:25     
do this um you know they use uh gradient     
1:22:30     
and metricbased methods um and they they define it there okay so     
1:22:36     
those are the papers i know that was a long slog through the papers um did we     
1:22:42     
have any comments or questions if we want to start a discussion on it     
1:22:48     
excuse me it's an interesting area i you know don't know how much um kind of go     
1:22:56     
off on that um again it just reminds me that I'd     
1:23:04     
really like to have um Logan come talk about     
1:23:11     
his work on multi-agent multi- aent you know reinforcement     
1:23:20     
learning where they're using     
1:23:25     
LLM's I mean so it's it's LLM based but but they're developing a theory of     
1:23:34     
mind to understand the other agents right so     
1:23:41     
It's it's it's an interesting approach of     
1:23:47     
of trying to     
1:23:53     
to yeah like get getting at that how to how to cooperate how best to cooperate     
1:23:59     
or how best to kind of coordinate but uh     
1:24:09     
yeah would this be coming up in with regard to     
1:24:15     
the sustainable open source development i mean that that seems     
1:24:21     
like it was kind of Yeah yeah i mean like I I don't know V he     
1:24:27     
uh put two of these papers in the slack so I don't know what the thinking is     
1:24:33     
there i I I definitely it fits into that area um yeah you know and like having a     
1:24:39     
good model of you know taking these results and kind of putting them into this context     
1:24:46     
um you know I don't know how they fit exactly yeah yeah but I I like the paper where     
1:24:52     
they were talking about the different markoff games and thinking about that because I've had this long-standing     
1:24:58     
fascination with game theory and kind of like the things you could do with that in terms of learning and so forth so you     
1:25:07     
know that's that was a really interesting kind of approach yeah I had no just a context for putting     
1:25:14     
it up but yeah I just came to those papers and read them like I just them not very much in detail so I thought     
1:25:20     
I'll share them with black yeah and the part where the game Yeah i've come across     
1:25:28     
this before when I was actually learning learning from my previous project and applying it over there so that's what     
1:25:34     
you were doing that's Yeah i just felt like sharing it yeah yeah no I mean you know it's a real     
1:25:43     
it's a great area right i mean um expands on     
1:25:50     
MDPs like um I haven't seen Yeah so you know like uh at least     
1:25:59     
in in mo most recently the only time I see any discussion of MDPs is from the     
1:26:06     
active inference institute yeah um uh but     
1:26:11     
uh yeah so I'm I'm curious though now just to Yeah like maybe maybe if I've     
1:26:20     
seen more of Daniel's work in terms of modeling modeling ant behavior or     
1:26:27     
something like that like you know Yeah where where you've got where you've got     
1:26:33     
multiple agents but um no this is Yeah it's it's a it's a     
1:26:40     
great area yeah so it's interesting that uh if you     
1:26:46     
remember Brian Mccoral and his group a couple years ago     
1:26:51     
uh he built his summer of code project was applying POMDPS     
1:26:59     
uh partially observed micro decision processes to the uh open source     
1:27:06     
sustainability project and it was largely in this case it was like getting some code up and running to describe     
1:27:13     
you know applying it to groups so we could you know flush it out and put in parameters that were useful yeah as well     
1:27:20     
as using the Python version of um it was like um five pi Vista what's the Mesa     
1:27:29     
mesa Mesa thank you yeah yeah yeah yeah right right     
1:27:35     
yeah i remember that um yeah so that was uh but we never really we kind of went     
1:27:41     
further with the reinforcement learning that we did with the Q1 DP and the     
1:27:47     
different methods there from active influence so that yeah that was like you     
1:27:54     
know kind of going through the tools that they have and they have a lot of good tools actually for doing this sort     
1:28:00     
of modeling but you know I don't know what the connection is necessarily     
1:28:08     
um between like MDP PDP and     
1:28:14     
reinforcement I mean obviously in these papers they kind of talk about it but how would you do this for open source     
1:28:20     
sustain ability I guess is the question     
1:28:26     
yeah yeah well I mean again this is um let me just I'll just post his GitHub in     
1:28:33     
terms of um you know of course Logan's approach is going     
1:28:40     
to be very um it's going to be also using LLMs     
1:28:48     
um but This     
1:28:55     
is I mean this is this is I think it's most     
1:29:01     
recent and and you know like like it gets     
1:29:09     
that you know they they they're doing     
1:29:14     
tasks right um so you know I think     
1:29:22     
um yeah you you could you could definitely turn this into a software test and I don't know one theory of mind     
1:29:30     
is necessarily useful but but but again it could just be it could just be you     
1:29:40     
know that that kind of the framework for understanding the other agents like like     
1:29:48     
how how you're kind Yeah you know trying trying to     
1:29:55     
understand the other agents um in this in this kind of collective     
1:30:00     
action yeah yeah well there was a little bit of     
1:30:06     
um well they didn't call it theory of mind but they were basically modeling an agent like kind of a     
1:30:13     
relative agent here where it was like observing its own state then observing the state of its     
1:30:20     
neighbor and then integrating that so I mean it's not theory the theory of mind     
1:30:25     
implies that you have like a model of that mind directly     
1:30:30     
yeah i mean but that was that was Yeah but you know to some degree that was an     
1:30:35     
a ABM kind of approach right like like     
1:30:40     
this this this perhaps maps better to a kind of     
1:30:47     
you know software engineering team and and and its interactions you     
1:30:54     
know did did they have to work yeah so they they also limited the problem by by     
1:31:03     
doing things in a pairwise way right right so I mean to     
1:31:10     
understand they're they're not actually doing a Markoff game i mean even though in a kind of ABM way it's super     
1:31:18     
interesting kind of like the spatial and temporal dynamics that you can get from     
1:31:24     
that yeah yeah yeah all right yeah looks good     
1:31:30     
um definitely a lot of kind of interconnections here between different     
1:31:36     
methodologies and how to construct this sort of metalarning um and yeah it's not an easy     
1:31:44     
problem i guess like you know people are kind of proposing with different techniques obviously there are ways that     
1:31:50     
we kind of more more standard ways we approach things and then we have to kind of put the pieces together to achieve     
1:31:57     
this thing kind of elusive metalarning how do you     
1:32:02     
learn from learning how do you synthesize different things that you've learned how do you use observations from     
1:32:09     
different agents if you're in a team or a group and I guess metalarning is     
1:32:15     
valuable both you know kind of sometimes it's valuable for working with groups of agents so     
1:32:22     
like you know learning maybe what another agent is thinking or having this collective state     
1:32:28     
uh you know sometimes it's useful for uh having this meta representation where     
1:32:35     
if you switch between tasks you don't lose everything from previous representation integrate the     
1:32:41     
representation so in the markoff games the idea was that you had this sort of     
1:32:48     
meta representation of the type of game it wasn't like you were training it for     
1:32:55     
every specific scenario that you would call that scenario when it came up you     
1:33:01     
had sort of this that I give you the rules of the game you learn the rules you learn what's possible within the     
1:33:06     
rules and then form you what's plausible within the rules and then you act on that we     
1:33:13     
operate and then of course you know we have this third type of meta     
1:33:20     
representation which is sort of you know the sort of the statistical inference     
1:33:26     
aspect where you have the uh prior the observations     
1:33:32     
posterior and then you know that's kind of you have to have the right task structure or the right     
1:33:39     
problem structure for problem structure was an interesting thing that got going in there because we don't often think of     
1:33:46     
that as like the defining factor but if you think about like a markup game     
1:33:52     
that's a very specific problem structure you can characterize it statistically     
1:33:57     
but if you were in like an more open-ended game you had you know this heterogeneous aspect to it you have     
1:34:05     
different agents doing all sorts of different things you know then then what do you     
1:34:11     
how do you how how does your agent build a meta representation it's much harder     
1:34:30     
i haven't seen the continual learning community talking     
1:34:37     
about multi- aent work although I did see that that was that was one of those     
1:34:44     
papers was from lifelong     
1:34:51     
learning so that that uh that's a that's a continual learning     
1:34:57     
group right uh lifelong learning yeah I think so yeah     
1:35:05     
yeah so they they they were presenting at a continual kind of     
1:35:10     
approach conference yeah yeah     
1:35:18     
yeah i don't know you know you'd think it would be like that sort of thing i guess like you know the the continual     
1:35:24     
learning is hard but yeah I mean so you have the     
1:35:31     
multi- aent and multi-agent systems i mean if you think about it they kind of are they have to kind of be continual I     
1:35:38     
guess because they're the whole point of having a multi group of agents and have     
1:35:44     
them interact and sort of perform these tasks uh in you know in real time so like if     
1:35:51     
you had for example a swarm of uh drones     
1:35:56     
or robots that did something collectively you have to have a sort of     
1:36:02     
you know you can't train it on like a specific task and then you know get like     
1:36:07     
optimal performance on one task and then you know they have     
1:36:12     
to the task is really structured and everything and then you know if they run     
1:36:18     
into any contingency then the whole fails uh so you have to have this some     
1:36:23     
sort of continual element yeah I don't know the literature well but I you know     
1:36:28     
I'm not familiar with anyone so     
1:36:34     
yeah it's um ICLR is coming up right uh yeah I     
1:36:41     
think in the spring or summer I guess no I mean I was it okay     
1:36:50     
sure i I just started to seeing people     
1:36:58     
getting like acceptances and things like that oh is it not     
1:37:09     
till Yeah well it seems seems like people were advertising that they're you     
1:37:15     
know come come see us yeah yeah so it's next it's next week oh     
1:37:20     
okay yeah a April 24th um I you know it's just like     
1:37:28     
starting to see people saying like you know here's here's here's what our lab's     
1:37:35     
presenting at you know um anyway you know just     
1:37:42     
uh always always a good time to also just check what they've got in terms of     
1:37:49     
you know like what workshops are they doing you know tutorials     
1:37:59     
um yeah you know     
1:38:06     
what's the difference between ICLR and Europe like in terms of the types of     
1:38:12     
work and the culture of Yeah i mean I you know it's it's a good     
1:38:19     
question um uh I remember the you know     
1:38:24     
the French the French kind of communities that I was in like     
1:38:30     
like always emphasized ICLR yeah like and and I think it just I I don't know     
1:38:37     
if that reflects like like did Benio start this or something like you know     
1:38:44     
like I I'm I'm not     
1:38:49     
uh you know and and I liked I liked that during the pandemic they they kind of     
1:38:55     
they did the most to kind of like make their meeting online and like super cost     
1:39:02     
accessible yes um um but I I I feel like they've they've you know     
1:39:11     
like is any of this online     
1:39:16     
this year you know and it's in you know because it's like it's in Singapore     
1:39:23     
right you know like really nobody should be flying that     
1:39:31     
far um I mean yeah but     
1:39:39     
um but a lot of workshops um you know     
1:39:49     
yeah I'll have to go over that and look at that and see what Yeah but I I you     
1:39:55     
know how how do how do new conferences get started right like like what what     
1:40:01     
was missing from the previous from the this did start recently though right     
1:40:10     
okay i mean I     
1:40:16     
What is the And what does what does the top level domain CC mean     
1:40:21     
uh I'm not sure i think it's like okay international domain yeah it's     
1:40:27     
but I'm not sure what it means all right iclr     
1:40:34     
about Okay no there's nothing useful here okay     
1:40:46     
well anyways yes sounds sounds like every other every other machine learning conference     
1:40:53     
[Music] um based in Wisconsin oh their contact     
1:40:58     
email I mean their contact address is in Wisconsin     
1:41:04     
i guess just isn't it learning representations the LR part okay     
1:41:10     
maybe it's about like that aspect of it i don't know yeah but     
1:41:16     
I mean it's like like Yeah that that that's the bit that makes     
1:41:21     
me think that it's like kind of post 2012 maybe is that that that it's kind     
1:41:28     
of you know deep learningish     
1:41:36     
you know but like like this could have been previously it would have been like feature engineering or something okay     
1:41:43     
yeah     
1:41:51     
um okay now I'm not going to have closure until I find out who started this     
1:41:57     
meeting all right um yeah actually Jesse's here and uh I     
1:42:04     
was wondering if Jesse wanted to give a short update     
1:42:10     
hey um yes I'm here and I can speak uh I'll speak briefly i know it's kind of     
1:42:16     
late in the day um but been a lot going on and I     
1:42:22     
haven't really I haven't made the first parts of the meetings for a while i wasn't kind of listening so just stop in     
1:42:28     
and um give an update on some things so um     
1:42:36     
uh one update that's pleasant um I'm officially as as as of recognized by the     
1:42:43     
dean of the school I've completed my master's program I haven't graduated I     
1:42:50     
haven't walked yet but I'm done with courses so that's great     
1:42:56     
um but it's it's nice I'll be in San Diego in June for graduation So anybody     
1:43:02     
who's around there I will try to stay for a while maybe a week or so maybe a     
1:43:08     
little more depending on what else I I can find out or get into there uh so     
1:43:14     
that's fine are you not there now no I'm in Boston currently oh okay     
1:43:20     
next weekend is um the California Neurochnology Conference oh so it's the     
1:43:26     
student neurotch conference i'm gonna be down here yeah there's     
1:43:32     
there's so much [Music] um Yeah there's so much there's so much     
1:43:38     
more I want to do with um UC San Diego because I'm I I've got a     
1:43:45     
lot of interesting projects coming up and and I have as as we sort of may recall we've had a nice relationship     
1:43:51     
with like excuse me University of Albany and I really want to follow that up i     
1:43:57     
visited the I visited uh the campus gez was that last weekend     
1:44:03     
wow i can't I think it's I think it's true yeah Nick week was last weekend it     
1:44:10     
I don't know for everybody else for me it feels like it's like two months ago and it was seven days ago right now is     
1:44:17     
about when it ended um but I was able to I had     
1:44:23     
I it's a very difficult situation but I could not I could not attend a panel directly um and I spent hours and hours     
1:44:31     
and hours um coordinating it having people come in and come out um of of the     
1:44:39     
process i believe Sam Sam Corollo Samantha Corollo one of our interns     
1:44:44     
actually went to the panel as well she was local and could make it that was huge i'm going to be following up with     
1:44:49     
her and do like a kind of a um I don't know like kind of an interview with her and some other panelists too i wanted to     
1:44:56     
do more of that in person but I had a I had a situation where I could not attend     
1:45:01     
uh at the last minute and it was very uh it was tough but we had Kathy Parker uh     
1:45:07     
who was a longtime Nick like co-chair step in to to do the actual moderation     
1:45:13     
panel we had a lot of great great great feedback um and I really it's a very     
1:45:20     
meaningful panel um for me personally uh something I've     
1:45:25     
wanted to put on and I'm I'm very happy that it was useful i've had good feedback from the     
1:45:31     
panelists um and in general     
1:45:37     
um I'm I'm as I'm I'm as pleased as I can be about it um and and there's     
1:45:44     
there's more to come from that um I I was able to go to U Albany but I     
1:45:51     
wasn't able to um I didn't get to have all the conversations I wanted to have when I visited so uh there's a little     
1:45:59     
more I want to do in terms of the upcoming internships and summer stuff i have I don't know if you want to get in     
1:46:05     
this now broadly or not but like I have some ideas um for like some of the     
1:46:10     
summer cohort things or even just writing up a little discussion about what the summer cohort is because we all     
1:46:18     
know and we've written about it sporadically and it kind of exists but it it it could use a what is this thing     
1:46:24     
now and like it's an actual thing and it's a lot of really nice parts to it um for those who don't know it's Google     
1:46:31     
Summer code and also uh people who wanted to work on projects that didn't     
1:46:36     
get accept didn't have the funding because you know uh Google's funding a     
1:46:43     
number of slots is variable and you know that's a whole other     
1:46:50     
conversation Google s of code uh in the mentor in the mentor emails that they     
1:46:55     
they've said like hey uh people are asking you blah blah blah it's like well we release all the information at the     
1:47:02     
time we're reviewing stuff right now so if anybody's asking you're getting DMs i've gotten a few people like hey hey     
1:47:07     
what's what's going on and like is it look like a lot of people apply to this and say like you know our response our mandatory response     
1:47:15     
is we're reviewing all applications and get back to you right um so just to     
1:47:22     
clear that error but the the summer the summer cohort is sort of Google Summer of Code i I I think we finally settled     
1:47:28     
on their name last year or so or the year before but it's Google Summer code proper the people who didn't get funding     
1:47:34     
that still want to do products and be a part of our community and also sort of this uh professional development open     
1:47:41     
source our open source meetings um which which will start up again soon i don't know if we've set a date for that not     
1:47:48     
quite yet yeah but like in the next few weeks you know sooner sooner than you     
1:47:55     
think uh our Friday meetings will be in full force again the it's actually warm     
1:48:01     
out finally in Boston the warmest day of the year I think here so it's like it actually feels a bit more like summer     
1:48:07     
and and that summer routine is coming up um in addition to the professional     
1:48:13     
development stuff I might add a segment especially if I get a few interns on this front to sort of uh I don't know if     
1:48:22     
it's really a new project but it's a new face on a project which I'm calling     
1:48:27     
data and direction or data exit direction and it's I posted about a     
1:48:33     
little bit already but it it's sort of just you know data science data ethics and a little bit of focus on sort of the     
1:48:40     
tools a little bit focus on how they shape decision- making um basically kind of some of my favorite things from my     
1:48:47     
coursework uh um but then also like looking at papers and looking at things     
1:48:52     
that are in sort of the more applied space because I I' I found I found one     
1:48:58     
of the things I found through my whole process has been you know kind of the     
1:49:03     
intersection of data science decision- making um India like society ethics tech     
1:49:09     
I I I say it's kind of a sister it's a I don't know if it's a project if if data     
1:49:14     
and direction is a project of sorts it's sort of honor a general umbrella of like I don't know society ethics technology     
1:49:22     
our kind of group around that and then also we talk about like data science here all the time the data and channel     
1:49:29     
um but I'm hoping to get a few people either through Albany maybe through UCSD or um or here or just otherwise in     
1:49:38     
general like I I have I'm kind of first sorting things out with you Albany     
1:49:44     
currently right now but I'm I'm basically drafting up the final well I'm finalizing the internship posting and I'     
1:49:52     
I'd really like to have I think there's a nice dovetail to kind of include a little bit of that in the Friday     
1:49:57     
meetings or at least sort of um another project that I'm working on     
1:50:03     
is is um currently titled from here to there or strategy and mentorship for     
1:50:09     
innovators which is basically super related to the um um I     
1:50:17     
actually share my screen here really briefly um     
1:50:23     
whoops i might not be able to because maybe I can just a second     
1:50:35     
um okay let me try this now it's kind of     
1:50:40     
um a little I haven't used Jity on this computer for a little bit okay bear with me here     
1:50:48     
but basically just to really quickly show some of these things um [Music]     
1:50:55     
uh okay window this window so I think yeah     
1:51:02     
so a lot of the posts are here um starting to populate here on substack     
1:51:08     
and I have the a little brief in post on s what is success but then we have the     
1:51:14     
Google summary of code tips we have first timeline panel this is all related to the Nickwick     
1:51:21     
um Nickwick panel was kind of inspired that but I tried to distill some other things into it uh this is a general post     
1:51:29     
but there's only There's only four posts here right now but there's there's like soon to be 10 posts here like there's a     
1:51:36     
lot of here this is going to be a lot of things being distilled into that we've     
1:51:42     
talked about for years and years and years and years like "Oh I should write this down should I write this down i should do this." And so I'm doing a lot     
1:51:47     
in this space and currently a lot of these are for early career things but     
1:51:53     
then I'm going to say more about like uh kind of the I don't know middle manager     
1:51:58     
but um people leading projects like what is it like to deal with teams what is it like to deal with um the interpersonal     
1:52:06     
stuff relative to building achieving the the short-term goals and all all that     
1:52:12     
stuff so the sort of um people leading the teams in the field doing the stuff     
1:52:17     
and then also the like the the higher level uh vision setting and how do you     
1:52:22     
not be distracted we've had a lot of things about like how do you how do you how do you lead how do you at a very     
1:52:28     
high level lead lead teams towards specific outcome and how does that look like in different fields of you know     
1:52:35     
um in in a startup and I'm sure startup culture how is that different in like academia how is that different and you     
1:52:42     
know when you're working in in a very particular industry constraint again like the mountains monasteries um     
1:52:48     
metropolis kind of comes into play there too so those are like the higher level broad visionary things all of them I     
1:52:53     
want to be kind of in the same place then but we we've talked about here a lot so I'm very excited to sort of I     
1:53:00     
don't know I don't know if this is a a hard launch but somewhere between a soft launch and a hard launch of this and I'm     
1:53:06     
I'm starting to actually put this out i put a little I have a little awkward logo that I like the third version I'm     
1:53:12     
like finally okay with um and I have a lot more things from Nickwick to to share here too     
1:53:18     
um there's this whole sort of you know I'm trying to finish up all of that     
1:53:24     
stuff as much as I can before we move on to other things in in this in the space     
1:53:30     
um and then for for this one     
1:53:35     
um there's only one post for data and direction right now and the page looks     
1:53:41     
really awkward right now well uh but this is this is sort of a a really     
1:53:46     
simple take on the the data labeled and data nut nutrition project um there's there's many more posts to be coming     
1:53:52     
here too but this is sort of a nice hey what's a what's what's a tool and like you know data data labels are sort of     
1:53:59     
this um uh     
1:54:04     
intermediary explanation about what's going on or or trying to convey     
1:54:10     
something about the data set before you download or play around with it and there's implications for these other     
1:54:16     
things you know for for um transparency or reproducibility and all that kind of     
1:54:22     
stuff but there's there's um there's more coming here too and I'm going to be leaning into that a lot this summer so I     
1:54:28     
kind of have the the nitty-gritty data technical stuff here and then for the other for this other thing um this is     
1:54:34     
going to be higher level uh leadership management mentoring strategy kind of things those are those are two major     
1:54:41     
focuses folkai whatever for me this summer and     
1:54:48     
um there's I I'm fortunate because there's just there's time to to write     
1:54:54     
and time to make things and time to push all this stuff out so there'll be a lot of movement on these fronts um and also     
1:55:02     
like opportunities um I don't know like Bradley Bradley you     
1:55:07     
and I are like um close this for a second we we we've had so many     
1:55:15     
um discussions around this in the past so I know this is all kind of like oh I'm doing it now uh but like anything     
1:55:23     
you want to write about or like I'm kind of imagining some discussion series     
1:55:29     
around it all this kind of stuff that I want to do um like is there and I don't I don't     
1:55:36     
know what you we I'm kind of just jumping this now but we could talk about this in in Slack     
1:55:42     
or whatever else but like if there's anything that you want to cover or dovetail with some of your other I know you have like a bunch of project     
1:55:48     
management courses and things like that too so however these can sort of dovetail     
1:55:54     
uh existing efforts and further like I really I really want to finally put towards all     
1:56:00     
this that we've had so many wonderful discussions like on these Friday meetings that kind of um are useful to people and I'm I'm     
1:56:08     
hearing people ask oh what about this and I'm getting these questions what about this and what about that and I was like well okay like we've had we've had     
1:56:15     
discussions about it for such a long time it's like I'm I'm materializing it now So     
1:56:22     
um I don't know stay tuned for that and for those who want to be involved in writing around those things or doing     
1:56:29     
some of the posts or participating some of the discussions like you're welcome to do that much as you want to um so     
1:56:38     
yeah that's that's an initial update any any immediate questions or comments I can attempt to field     
1:56:46     
um well I mean yeah you know we have to start thinking about the content for our     
1:56:52     
open source meetings because the last couple years we've done them you know we've had of course the discussion about     
1:56:59     
GOC projects discussion about open source practice but then also some of these professional     
1:57:05     
development things that might be useful to bring some of that into the those     
1:57:11     
meetings oh yeah um yeah and I think yeah that looks great that like you have     
1:57:16     
this you're kind of taking a new dimension to some of the work that you've been doing with project     
1:57:23     
management and applying it to data science and Yeah and and Oh god sorry oh     
1:57:29     
no go ahead it's I mean I mean I'm I'm     
1:57:34     
I'm doing work in those spaces already and I realize I want to do even more     
1:57:40     
work in those spaces so there's there's a double incentive for that for me but also     
1:57:45     
like I the particularly the last year I have just had so little time to     
1:57:53     
distill and write and generate things um I know there's a discussion to be had     
1:57:59     
about like the Wednesday meetings of condition futures which I may still put a little bit on the back burner and center some of these other projects as a     
1:58:06     
as a as a lab discussion thing going forward um but like I feel so     
1:58:15     
uh relieved to not just be like vaguely talking about things but writing them     
1:58:22     
and and I also like I appreciate um you know all of our efforts here and I have     
1:58:27     
a few efforts of people that have been doing some some editing and and thinking about stuff with me and     
1:58:34     
uh again like the the feedback and response from from the panel and and and     
1:58:41     
some of the interviews that I'm doing about this have been really really uh promising so I appreciate everybody's     
1:58:46     
present and and past efforts that have led to these things happening now it's like finally I'm I'm done with the     
1:58:54     
coursework i'm doing this other stuff i'm I'm transitioning in this way and     
1:58:59     
then now it's like these things are starting to emerge that have been kind of just been sitting there for a long     
1:59:04     
time um so yeah let's let's let's have a maybe     
1:59:11     
um I don't know if you want to wait until next Friday or whenever but like sometime soon I think we could have     
1:59:16     
maybe the summer strategy meeting about open source to summer cohort like what do we want to say like I can draft I     
1:59:23     
already have mentally have drafted the summer cohort post and then we can just you know talk about that and say what do     
1:59:30     
we want to do we have in a couple months here and you know I have some things     
1:59:35     
that I'm going to be gonna be doing which some of it will dubtail really well into this some of it is separate     
1:59:41     
and then I know we'll you know we have our plans um and we have a lot of great     
1:59:46     
submissions too so um I'm excited about Google proper and then the summer co at     
1:59:52     
large so maybe we can talk about that specifically I don't know I know we've     
1:59:58     
kind of running out of time here today um but uh I'm I think it'd be good to do     
2:00:04     
that yeah all right yeah that would be     
2:00:09     
good all right so I think we'll wrap it up for this week um we had some good     
2:00:15     
discussions this week uh I'm looking forward to Jesse's work on     
2:00:20     
um the summer well the the data science stuff and all that and bringing that     
2:00:25     
into our open source meetings and uh you know we will next week we'll     
2:00:31     
continue the discussions that we've been having this week on uh I think metalarning and I did want to get into     
2:00:38     
world models and the uh relationship between metalarning and role models but I'm not going to do that this I'm not     
2:00:44     
going to get into that this week because it's you know quite a large discussion so we'll talk about that next week have     
2:00:51     
you heard anything from from like Adam by the way speaking of role models um no     
2:00:57     
I haven't heard anything recently i mean the paper was been submitted and they     
2:01:02     
like he he I guess he got sick for a while and then Yeah so yeah yeah i I     
2:01:09     
I've I've been talking with him um and and yeah he's he's been busy with things     
2:01:17     
um and yeah my last seven months is is getting     
2:01:24     
sick and things happening uh so I I totally understand i was just a Yeah um     
2:01:31     
but yeah like there's there's also like I know we maybe saw a recap about     
2:01:37     
um other other events that have recently happened i can even say more about maybe next week I'll say more about the panel     
2:01:43     
proper and what we're actually talking about um at at Nickwick but then also like other targets we want to hit this     
2:01:49     
summer there's a bunch of just applications still kind of coming through and some summer projects and programs but yeah um let's talk about     
2:01:57     
that in Slack I guess okay and thank you for Uh everything else has been going on     
2:02:03     
yeah sounds good all right i had a good good meeting with um Neurotch at UI U oh     
2:02:12     
yeah really yeah yeah yeah they they they were very um Yeah very interested     
2:02:21     
in in collaborating on some some projects and expanding expanding what their group     
2:02:28     
does oh okay uh I'm not familiar with that like is that a student group or is     
2:02:33     
that like a Yeah yeah yeah yeah these are all these are all Yeah our our student clubs um or you know under     
2:02:41     
undergrads um but um it was it was a good     
2:02:47     
conversation okay yeah it's a lot you know and like a mix of um mix     
2:02:53     
of cog you know cog and neuro kind of people but also um you know engineering     
2:03:01     
which you know strong strong tech school there yeah oh yeah     
2:03:08     
so anyway all right that was that was good great thanks all right take care     
2:03:15     
take care take care bye fight     
