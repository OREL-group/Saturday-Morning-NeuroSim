## Meeting Recording

[YouTube link](https://youtu.be/k8TEoQhB4Fc)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114329063824584427)

## TRANSCRIPT
     
Transcript     
0:01     
hello     
0:06     
Morning Morning All right Um let's get     
0:14     
started So uh uh we had a devil war meeting this week     
0:20     
We had uh we talked about some papers and projects that are being proposed for     
0:28     
Google Summer code So that's uh good Uh we didn't have any other     
0:35     
meetings but I got a message from Jesse saying that he's interested in restarting the both the cognition     
0:43     
futures meeting and the cybernetics meeting So we'll see how that goes So maybe starting that back up Then     
0:52     
additionally um I'd like to start the open source meetings back up I'm not     
0:58     
sure what our when we're going to start doing probably towards the end of this month because we're coming up on our     
1:05     
traditional start of the Google code program So     
1:11     
that's um I don't know what date that might be maybe in about two weeks or     
1:17     
so So stay tuned for that And in the summers we do our so the summers we do     
1:23     
our open source meetings It's usually every week on     
1:28     
Fridays Um and and I'll send out a note     
1:34     
to um set the final time It's usually in North America it's usually     
1:41     
you know morning to mid afternoon So so we'll do that Um we usually have     
1:48     
like reports on different projects uh some topic that we talk about and Uh     
1:56     
we have and on our YouTube channel we have playlist     
2:02     
for past years where we've done this enjoy the open source meeting is     
2:07     
seasonal goes from the beginning of May to probably September or October and we     
2:15     
just that's largely when we can have reports on summer projects     
2:21     
uh you know we'll go through a number of topics that I think are useful to a lot     
2:27     
of people and uh you know it's a good way for people in the lab and anyone     
2:32     
outside the lab to get involved in open source we also add an open science component into it from time to time and     
2:40     
it's it's quite a good experience so um I will be in touch in     
2:46     
terms of when that will start so let's start     
2:54     
Um actually I want to go through some stuff from the Slack So this is a paper     
3:01     
that VThe posted in I believe cognition futures So this looks interesting and     
3:08     
I'd like to cover it So this is an archive paper on     
3:13     
metalarn models of cognition Uh two weeks ago last time we met we     
3:18     
talked about um metalarning and metalarning models So this is metalarn     
3:24     
model of cognition that looks like it's a group from the max plunk institute and deep     
3:31     
mind Um and so I guess they're going to talk about metalarning and how that can     
3:38     
be used for learning and cognition So let's go over the abstract     
3:44     
first Uh the short abstract is that metalarning has established     
3:50     
itself as a promising tool for building models of human cognition in recent     
3:56     
years Yet a coherent research program on metal learn models of cognition is still     
4:02     
missing Uh the purpose of the present article is to develop such a research program We accomplished this by pointing     
4:08     
out that metalarning can be used to construct phase optimal learning algorithms allowing us to draw strong     
4:15     
connections to the rational analysis of cognition We then discuss several     
4:20     
advantages of metalarning the metalarning framework over traditional basian methods and reexamine prior work     
4:27     
in the context of these new insights So this is um sort of putting metalarning     
4:35     
in contrast of basian methods which I find are interesting I guess they're using basian methods but not in the same     
4:42     
way So if we're you know we're thinking about basian methods this is where we     
4:49     
have a set of conditional probabilities where we have an a priority distribution and then we have a set of     
4:56     
observations and then we look at how those a that a priority distribution matches the current observation and we     
5:04     
update our priors to reflect that new information and we converge upon a     
5:11     
solution So that's uh where they're going So the long     
5:17     
abstract is metalarning is a framework for learning al learning learning     
5:23     
algorithms through repeated interactions with an environment as opposed to designing them by hand So uh hand coding     
5:32     
In recent years this framework has established itself as a promising tool for building models of human cognition     
5:40     
uh yet a coherent research program around middleware models of cognition is still missing The purpose of this     
5:46     
article is to synthesize previous work in the field and establish such a research     
5:51     
program Uh so they rely on three key pillars The first is to point out that     
5:57     
metalarning can be used to construct basop optimal learning algorithms The result not only implies that any     
6:03     
behavioral phenomena that can be explained by a basia model can also be explained by a metalarn model but also     
6:10     
allows us to draw strong connections the rational analysis of cognition So you know we want to be able     
6:17     
to uh understand sort of behavioral phenomena     
6:24     
um but we also want to be able to have this rational analysis of cognition     
6:29     
Um so we want to be able to explain behavior by metalarning and have theoretical     
6:36     
framework as well We then discuss several advantages of metaarning framework over traditional basian     
6:43     
methods So raising basian methods but raising this specific class of basian method In particular we argue that     
6:50     
metalarning could be applied to situations where basian inference is impossible and that it enables us to     
6:57     
make rational models of cognition more realistic either by incorporating     
7:03     
limited computational resources or neuroscientific knowledge     
7:08     
So this is where we have u you know we go beyond sort of the the classic cases     
7:16     
of basian inference and we can make so rational models of     
7:22     
cognition typically you know sort of are divorced from reality     
7:29     
in some ways and so you know a lot of times people do things that are     
7:34     
irrational or they don't make the optimal solution And so you know with this kind of     
7:40     
metalarning framework you can actually kind of make up ground the ground between rational analysis of cognition     
7:48     
and the real world So again um how do you make this     
7:54     
more realistic you either incorporate limited computational resources or     
7:59     
neuroscientific knowledge So this is where we know things about decision     
8:05     
making that go beyond sort of a rational analysis of behavior or we build a computational     
8:14     
model Finally we reexamine prior studies from psychology and neuroscience that     
8:20     
have applied metalarning to put them in the context of these new insights In     
8:25     
summary our work highlights that metalarning considerably extends the scope of rational     
8:31     
analysis thereby of cognitive theories more general So this is a nice paper I     
8:36     
think I think it's kind of really presenting this area as sort of a     
8:43     
basian you know putting it squarely in the basian can but also kind of drawing     
8:49     
out how metalarning can contribute to uh theory So this talks about metalarn     
8:57     
models of cognition and how it's a sort of computational model So it's hard to     
9:03     
imagine cognitive psychology and neuroscience without computational models Uh traditionally such models have     
9:10     
been handdesigned by expert researchers and you know it's usually they people propose a computational     
9:17     
model of like memory or attention or something like that And so this leads us     
9:22     
to co has led us to cognitive architectures where we've provided fixed     
9:27     
set of structures and a definition of how these structures interact with each other So usually like a flow diagram or     
9:35     
some sort of model like basian model where you have um you know conditional     
9:42     
uh probabilities conditional variables things like that In basian models of cognition     
9:48     
researchers instead specify a prior and a likelihood function which in combination with baze rule will     
9:55     
determine the model's behavior So this is this reference Griffith's uh antenna bomb 2008 where they talk about basian     
10:05     
models of cognition the framework of metalarning um and this is these are the citations     
10:12     
here offers a radically different approach for constructing computational models by learning them through repeated     
10:18     
interactions with an environment instead of requiring an a priority specification     
10:23     
from a researcher So this is where you have you don't have these top down     
10:29     
models you have these bottom up models So you they basically are emergent or     
10:36     
they're generative in the sense that they produce sort of you know     
10:41     
different mechanisms and different interactions Um so this is a little bit     
10:48     
different approach than the traditional cognitive architecture approach So psychologists have started will apply     
10:55     
metalarning to the study of human learning Metalarning models can capture a wide range of empirically observed     
11:01     
phenomena that could not be explained otherwise So um they're able to reproduce human     
11:08     
biases and probabilistic reasoning discover heristic decision-making strategies used by     
11:15     
people and generalize compositionally on complex language tasks in a humanlike     
11:21     
manner So basically you have these types of things that are sort of uh kind of go     
11:28     
beyond the rational analysis of behavior where you don't     
11:33     
always assume that people take the you know sort of most um most optimal     
11:42     
choice You also introduce human biases So you want to be able to reproduce these things to successfully model     
11:49     
them The goal of the present article is to develop a research program along around metalarn models and cognition and     
11:57     
in doing so offer a synthesis of previous work Um so to establish such a research     
12:04     
program we will make use of a recent result from the machine learning community showing that metalarning can     
12:10     
be used to construct base optimal learning algorithms This correspondence is interesting from     
12:16     
a psychological perspective because it allows us to connect metalarning to     
12:22     
another already wellestablished framework which is a rational analysis of cognition So in a rational analysis     
12:29     
one has to first specify the goal of an agent along with a description of the environment of the agent interacts with     
12:36     
the base optimal solution for the task at hand Then derived based on these assumptions and tested against empirical     
12:44     
data If needed assumptions are modified and the whole process is repeated This     
12:50     
approach for constructing cognitive models has a tre tremendous impact on psychology because it explains well why     
12:58     
cognition works by viewing it as an approximation to ideal statistical     
13:04     
inference given the structure of natural tasks in the environment So we have you know ideal     
13:12     
statistical inference we can assume that things are optimal we can build a     
13:17     
statistical model or some sort of computational model and make predictions     
13:22     
But in in terms of what we're doing here we want to see if we can build     
13:28     
approximations So we don't want to build exactly that We want to come near nearby     
13:34     
The observation that metal models can implement basian inference implies that a metalarn model can be used as a     
13:41     
replacement for corresponding basian model in a rational analysis and thus     
13:46     
suggests that any behavioral phenomena can be captured by a basian model or any     
13:51     
phenomena that can be captured by a basian model can also be captured by a metal So there's this uh this     
13:59     
equivalence between the basian model and the metalarn model in terms of expressivity The question is which one     
14:06     
is better they're arguing is that the metalarn model being the class of basia model is actually better than a standard     
14:13     
basian model So they start with these four arguments So they sort of ask why     
14:20     
do we need to to go beyond the basian approach and so uh they have this     
14:26     
basically this figure figure one has the four arguments in it So the first     
14:31     
argument is that possible even if exact basian inference is computationally     
14:36     
intractable So this is a obviously this computer is struggling with the answer     
14:43     
Um so this is where you know we can sometimes model     
14:48     
things and frame and formulate them in terms of a mathematical computational     
14:54     
model but we can't actually get a good solution or run it to an exact solution     
15:00     
So you know sometimes there are problems that are computationally intractable where it takes way too long to get the     
15:06     
optimal solution and that may hold true maybe for the brain as well as a     
15:13     
computer but it's better to have these uh heruristics isn't this in fact that's     
15:18     
the argument kind of for cognitive heruristics is that we can't have     
15:23     
perfect information about the world so we have to generate these heruristic     
15:29     
uh uh solutions to problems to decision making problems and so those are good     
15:35     
enough to get us through the world and that's all that's what matters So that's that's you know the     
15:42     
kind of their point argument one argument two is that possible even if impossible to phrase or it's possible     
15:50     
even if it is impossible to phrase the corresponding influence problem So this is here uh metalarning     
15:59     
can produce approximately optimal learning algorithms even if it is not possible to phrase the corresponding     
16:05     
inference problem in the first place So we want to be able to get an     
16:11     
approximation this first argument and the second argument metalarning can do this for     
16:17     
us and you know even if it's really hard to sort of state what the problem is So     
16:24     
sometimes it's that we know what the problem is but we can't solve or find the exact solution In other cases it's     
16:32     
hard to even pose the problem correctly So um there's uh I think in     
16:41     
the past people have phrased different types of problems as illposed problems     
16:46     
So I think moving an arm to a target has been phrased as an opposed problem     
16:52     
because there are too many open parameters and you have to specify them And so the these are you know kind of     
16:59     
where you have things in the world that pose problems to say cognition or a cognitive     
17:06     
system has to solve them but it also has to understand what it's doing And a lot of times you have these open systems or     
17:14     
um you have uh sort of like an open adapt uh frame of adaptation where if I     
17:22     
perform one activity whatever I do in that activity is contingent upon the next activity and     
17:29     
so forth So you know this is the kind of thing for argument too It's not saying     
17:35     
that it can't find the solution It's saying that even the problem is     
17:43     
bullposed Okay So and then they Show this in terms of a probability distribution So if you have probability     
17:49     
of H what goes into the probability of H or the probability of D given H what     
17:56     
goes into that probability okay Argument three metalarning makes it     
18:03     
easy to manipulate a learning algorithm's complexity and can therefore be used to construct resource rational     
18:09     
models of learning So this is again this one argument three makes it easy to     
18:14     
manipulate a learning algorithm's complexity So this shows the um you have     
18:21     
neural net and you're pruning the neural net to find a solution or you're finding     
18:26     
the weights Metalarning can do this And then figure four metalarning     
18:32     
allows us to integrate neuroscientific insights into the rational analysis of     
18:37     
cognition by incorporating these insights into model     
18:42     
architectures So this is argument four integrates neuroscientific insights into rational analysis of     
18:49     
cognition This is where we have a model of something happening in the brain like we might describe the process of     
18:56     
short-term memory or spatial cognition And we have a number of places where     
19:03     
this happens and pathways and then we can basically say if these things happen given those     
19:10     
things then we have a probability of something else So probability of H given D is according to B rule this     
19:18     
conditional probability that one thing happens another thing will happen We know from the brain that the brain is     
19:24     
processing this So we kind of know what those probabilities might be     
19:32     
Okay so the first two points highlight situations in which metalarn models can be used for rational analysis where     
19:40     
traditional basian models come out So these two kind of     
19:45     
are more uh where metalarn models can be used for rational     
19:51     
analysis Um the latter two points provide examples of how metalarning enables us to make rational models of     
19:57     
cognition more realistic in these cases either by incorporating limited computational resources or     
20:04     
neuroscientific insights Okay Um so they kind of talk     
20:10     
about metalarned rationality what that is Um so the     
20:16     
prefix the prefix meta is generally used in a self-reerential sense So meta rules     
20:22     
or rules about rules Uh metaarning consequently refers to learning about learning We therefore     
20:29     
need to first establish a common definition of learning And so they use this definition from Mitchell circa     
20:36     
1997 So this is for a given task training experience and performance     
20:42     
measure An algorithm is said to learn from its performance if its performance that the task improves with experience     
20:50     
So any kind of well- definfined task sometimes it could be a illdefined task     
20:55     
someday you have to have some sort of measure of it and you have to have it presented as an experience So you have     
21:02     
to have the task presented over and over The algorithm is said to learn if     
21:07     
the performance of the task improves with experiments So you have to have some improvement which gives you a     
21:14     
learning rate which derives from the amount learned over the time that over     
21:19     
the repeated exposures and the repeated measurements That's what we mean by then     
21:26     
we can talk about the bas basian inference from rational analysis So in a rational analysis of cognition     
21:33     
researchers are trying to compare human behavior to that of an outdoor However it turns out that no     
21:40     
learning algorithm is better than any other inveraged overall possible problems And this is a finding that's     
21:47     
reported in the literature which means that we first have to make additional assumptions about the to be solved     
21:54     
problem to obtaining a well- definfined notion of optim Okay So for a running example one     
22:02     
may make the following somewhat realistic assumption And so they're giving an     
22:07     
example here of a problem in the uh so the first thing is each observed     
22:13     
insect length is sampled from a normal distribution with a mean and a standard     
22:20     
deviation So basically you you you're observing a bunch of things that are the same these you know you're measuring     
22:27     
insects you're measuring length So the measure is sort of a standardized thing     
22:34     
You make a bunch of observations on insects You then put that into make a normal distribution from that You assume     
22:41     
some normality with the mean and the standard Okay So that's the first that's     
22:47     
the obser set of observations Number two is that an insect species mean length mu cannot be     
22:54     
observed directly So we can't observe the mean directly We can measure all the insects we want but we'll never observe     
23:01     
the mean directly We only know that like there's a distribution there's a standard     
23:08     
deviation of 2 cm and if we do this if we build the statistical model we can find the mean     
23:15     
But the mean isn't something that's inherent in nature We only know the standard     
23:22     
deviation and then the mean derived from a model of the data of the observations     
23:27     
Number three is that mean lengths across all insect species are distributed according to a normal distribution with     
23:34     
a mean of 10 cm and a standard deviation of 3 cm So we know what this     
23:40     
distribution looks like when we get enough observations We know kind of what the standard deviation should be because     
23:47     
people have observed this before in different insects you know you model insects of a certain species you're not     
23:54     
always uh measuring the same ones You're just kind of you know measuring all     
24:00     
different instances and you derive that from previous observations and then your     
24:05     
current set of observations has properties that either come close to matching that or you know     
24:14     
don't Um so usually what we get is we get this mean that we derive from our     
24:20     
measurements We also have a mean that we've observed in the past We have a standard deviation that's been known in     
24:26     
the past And then we have the standard deviation So th those are the     
24:33     
assumptions An optimal way of making predictions about new observations under such assumptions is specified by bas     
24:41     
inference So we need to have a prior distribution P mu that defines an     
24:46     
agent's initial beliefs about possible parameter values before observing any     
24:51     
data and a likelihood P um X one overt     
24:57     
given you which captures the agent's knowledge about how data is generated for a given set of parameters So we know     
25:05     
like we know what the prior distribution is We also know you know that they're     
25:11     
going to be this set of observations and that there's a likelihood about this generative process     
25:19     
Uh in our running example the prior and the likelihood can be identified as follows right here Um and then uh where     
25:28     
x1 to t denotes a sequence of observed insect lengths and the product in     
25:33     
equation two which is up here arises uh due to the additional assumption that     
25:39     
observations are independent given the parameters You can see that this is a summation here of all of these     
25:49     
uh the distribution or the observations given the prior     
25:54     
distribution I guess it's the multiplication of the selection Okay So the outcome of basian     
26:01     
inference is a posterior predictive distribution which the agent can use to make probabilistic predictions about     
26:07     
hypothetical future observation To obtain this posterior predictive distribution the agent first     
26:14     
combines prior and likelihood into a posterior distribution That's here In the     
26:20     
subsequent step the agent then averages over all possible parameter values weighted by their posterior probability     
26:28     
to get the posterior predictive distribution is here So you can you know     
26:33     
build basian models that are pretty complex uh multiple arguments justify basian     
26:38     
inference as a normative procedure nearby its use for rational     
26:43     
analysis Uh this includes Dutchbook arguments or free energy minimization     
26:49     
and performance-based justifications They put free energy minimization in this class of rational     
26:56     
analyses Um and you know it's connected to basian inference For this article I'm     
27:03     
mainly interested in the latter class of performance-based justifications uh which is this last category     
27:11     
here Um as we will demonstrate metalarning algorithms can be derived to     
27:17     
learn approximations of basian influence Performance-based justifications are based on the notion of frequent     
27:24     
statistics Particularly relevant for this article is a theorem proved by Aches     
27:31     
It states that the posterior predictive distribution is the distribution from the set world distributions that     
27:37     
maximizes the log likelihood of hypothetical future observations when averaged over the     
27:43     
generating distribution So this log likelihood is the thing that you get out of a basian     
27:49     
distribution Um and that's you know what we're dealing with here Uh frequentist     
27:55     
statistics often deals in probabilities instead of likelihoods     
28:01     
uh that's the difference usually between the two Um so     
28:09     
uh this implies that it if an agent wants to make a prediction about the length of a still unobserved exemplar of     
28:16     
a particular insect species and measures it it performance using the log     
28:21     
likelihood then averaged across all possible species that can be encountered there's no better way of doing it than     
28:28     
than using the posterior predictive distribution So they give you they give a short proof and they get through some     
28:34     
of this the technical details here Um so they kind of get into the basian     
28:41     
argument They get into these kind of models uh these performance-based     
28:46     
justifications and they show that the basian approach is better this log likelihood uh approach is better than a     
28:54     
frequentist approach Okay Now we get into metalarning So that's a long kind of introduction into metalarning     
29:01     
uh thinking about sort of phase optimal learning and how that works So um now of     
29:09     
course when you're learning about learning you can see the kind of connection here You have a prior     
29:15     
distribution which is like learning and then you have some set of observations about learning So you have a conditional     
29:22     
probability which is learning about learning     
29:42     
So that's I think where they're going with this Um so formally speaking a metalarning algorithm is defined as any     
29:49     
algorithm that uses this experience to change certain aspects of a learning algorithm or the learning method itself     
29:57     
such as that the modified learner is better than the original learner at learning from additional experience     
30:04     
So you're basically modifying the learning process by learning about learning and it's improving your     
30:12     
performance So to accomplish this one first decides on an inner loop learning     
30:17     
algorithm and determines which of its aspects can be modified We also refer to these modifiable aspects as     
30:25     
metaparameters in an outer loop or metalarning process The system is then trained on a series of learning problems     
30:32     
such that the interloop learning algorithm gets better at solving the problems that it encounters Okay so this is basically     
30:39     
showing this process in figure two So you have learning of course we     
30:46     
talked about this measurement problem and this is a butterfly instead of a I     
30:51     
guess a metamorphized insect here Uh you're measuring parts of its phenotype     
30:57     
You're getting these measurements You're getting a distribution of measurements The base learner learns about these     
31:03     
measurements And then you have the mean of the measure So that's a performance     
31:09     
measure Um and so okay let's go over So that's in the learning uh rectangle And     
31:16     
then the metalarning rectangle is where these things get passed in and out of     
31:22     
the learning output So you're modifying learning by introducing new     
31:27     
instances new species of insect and so you have measurements for those So table     
31:35     
learn different types and instances and you know that's modifying it at at in terms of the     
31:42     
training You have metaparameters which affect the base learner So you have     
31:48     
parameters that affect uh how it's able to sample from that     
31:53     
original distribution or the basian rule it's using the structure of that rule     
31:59     
and then you have performance measures So the performance measures feed back to the metaparameters So if it's doing a     
32:06     
particularly good job of uh distilling the learning rule then it's rein those     
32:12     
metaparameters are reinforced If not they're changed So figure two says highle overview of the metalarning     
32:19     
process A base learner the green rectangle and this green rectangle here     
32:24     
receives data and performs some inertial computation internal computations that     
32:29     
approve its improve its predictions on future data points A metalarner in the blue     
32:35     
rectangle which is this outer rectangle encompasses a set of meta parameters that can be adapted to create an     
32:42     
improved learner This is accomplished by training a learner on a distribution of learning problems which are these things     
32:49     
here Okay So this talks about kind of kinds     
32:58     
of things that you can metalarn Uh you can metalarn hyperparameters for a base learning     
33:04     
algorithms such as learning rates batch sizes or training ethics     
33:10     
You can metalarn initial parameters of a neural network that is trained via stochastic gradient     
33:17     
descent You can uh metalarn prior distributions in a probabilistic     
33:23     
graphical model and then you can metalarn entire learning algorithms So they're making     
33:29     
some pretty good claims about what or metaarn I should     
33:35     
say So in terms of metalarn inference uh it may seem like a daunting goal to     
33:41     
learn an entire learning algorithm from scratch But the core idea behind the approach we discuss is the following and     
33:48     
the following is a surprisingly simple idea Instead of using basian inference to obtain the posterior predictive     
33:55     
distribution we teach a general purpose function approximator to do this inference The previous work is mostly     
34:02     
focused on using recurrent neural networks as a as function approximators     
34:07     
in this setting and thus we will without loss of generality focus our upcoming     
34:13     
exposition exposition on this class of models like the posterior predictive     
34:19     
distribution the recurrent neural network processes a sequence of observed length from a particular insect species     
34:27     
as we saw in the figure it produces a predictive distribution over the lengths of potential future observations of the     
34:33     
same species More concretely the metalarn predictive distribution takes a predetermined     
34:40     
functional form whose parameters are given by the network outputs So for example if we decided to use a normal     
34:47     
distribution as the functional form of the metalarn predictive distribution outputs of the network would correspond     
34:54     
to an expected length and its standard deviation So this is what we see in     
35:00     
figure three here So we have the metalarning setup where we have these     
35:05     
parameters we have forward and backward in this So we have x1 x2 and xt     
35:12     
So every time we kind of get an observation we make the     
35:19     
comparison and then we end up with this log like loop Then there's you know we can put     
35:26     
this into pseudo code uh basically see if the algorithm     
35:32     
converges by sampling the sample data and going forward and getting to a point     
35:39     
where that log likelihood is optimized Then we have metalarning loss     
35:44     
So we have we try to match a B optimal level of learning loss to go from a very     
35:51     
high loss over many iterations of the algorithm and it try we try to converge     
35:57     
upon the B's optimal uh loss and then the predictive     
36:03     
distribution show for insect length if we have our metalarned example and our     
36:09     
basian example over time over a number of iterations of the algorith we should     
36:15     
converge upon the baze optimal solution So here in the left we have the     
36:20     
probability density versus insect length this in this uh the basy a baze optimal     
36:28     
model predicts a mean insect length of about 9.5 and then the metalarned     
36:34     
uh model at about zero that's in t0 so this is when it's just observing it for     
36:40     
the first time if we keep running this algorithm over and over and we get     
36:45     
information from each observation and we keep optimizing the log likelihood and     
36:50     
reducing the loss we end up converging upon the mean so that we end up with     
36:56     
around the same mean as the B optimal uh condition So that's basically what it     
37:03     
does So it's learning an algorithm and then says how good is a metalarned algorithm and this is where they     
37:10     
evaluate their work Um so they basically um you know they try to do this sort of     
37:18     
um evaluation I mean they don't give any statistics here but they kind of uh     
37:25     
suggest that it can be done using our standard tools So uh we have previously shown     
37:32     
that the global optimum for equation seven which is up here is achieved by     
37:37     
the posterior predictive distribution Thus by maximizing this performance measure the network is actively     
37:44     
encouraged to implement an approximation to exact basian inference To perform an inference we     
37:51     
simply have to query the network's outputs after providing it with a particular sequence of     
37:57     
observations So this is basically where we're observing each observation We're     
38:02     
kind of uh adjusting the algorithm We want to use the fully optimized network     
38:07     
for rational analysis We have to ask ourselves how well does the resulting model approximate basian influence So we     
38:15     
have to consider two things First the network has to be sufficiently expressive to produce the exact     
38:22     
posterior predictive distribution for all input sequences That means that we have to have some sort of network     
38:29     
representation of this broad distribution And you know if we can't produce that     
38:36     
posterior predictive distribution we need to be able to adapt or evolve the network in a way that that     
38:42     
shapes that So that's why we go through all these different iterations of the log likelihood of this posterior     
38:49     
predictive distribution Neural networks of sufficient width are universal function     
38:55     
approximat meaning that they can approximate any continuous function to arbitrary precision So the aspect is not     
39:02     
too problematic for the optimality argument However in the second aspect we     
39:08     
can assume that the network is powerful enough to represent the global optimal of equation seven The employed     
39:15     
optimization procedure also has to find it So if we can represent the global     
39:20     
optimum we have to be able to find it So we have this aspect of     
39:25     
expressibility and then we have this aspect of finding something or finding the     
39:31     
optimum While we are not aware of any theorem that could provide such a guarantee in practice it has been     
39:37     
observed that metalarning procedures similar to the one discussed here often lead to networks that falsely     
39:43     
approximate basian influence     
39:51     
We provide a visualization demonstrating that the predictions of a metal model mostly resemble those of exact bas     
39:57     
inference for insight length example So um basically they're able to you know     
40:07     
they frame kind of these two aspects and so this has strengths and     
40:12     
weaknesses but we can do things like uh we can you know look at supervised     
40:18     
learning as we did here We can also extend it to the reinforcement learning case as well So in summary it is     
40:24     
possible to metalarn an approximately based optimal learning output If exact     
40:30     
basian inference is not tractable such models are a best option for for performing rational     
40:36     
analysis Yet many other methods for approximate inference such as     
40:41     
variational inference and MCMC methods which are Monte Carlo methods     
40:47     
maximum Monte Carlo methods also share this feature and thus and and will thus     
40:53     
ultimately be an empirical question which of these approximations provide a better description of     
40:59     
human So again this is where you know this is kind of I just went through argument one here Um and I think I spent     
41:06     
a lot maybe too much time on it because uh there are other aspects here So the     
41:11     
number two I'm just going to point out is these are these unspecified problems     
41:17     
where you really have sometimes these illos problems where you know you really     
41:23     
need to be able to specify a prior and a likelihood and sometimes you can't do that     
41:28     
So this is where you know again we have uh even in the world of basian decision     
41:34     
theory we have these small and large world problems A small world problem is one in which all relevant     
41:41     
alternatives their consequences and probabilities are known On the other hand the large world     
41:48     
problem is one in which the prior the likelihood where both cannot be identified So you have this distinction     
41:55     
between things where you can know all of these things and problems where you can't     
42:01     
identify any Savage's distinction between small and large worlds is relevant for the     
42:08     
rational analysis of human cognition as its critics have pointed out that basian inference only provides     
42:15     
a justification for optimal reasoning in small world problems that very few     
42:20     
problems of interest to the cognitive behavioral social sciences can be said to satisfy this condition So basically     
42:28     
most of your problems in cognitive science don't satisfy this condition So     
42:34     
we need to be able to make some assumptions and make them correctly So this is kind of saying that this is uh     
42:42     
metalarning is possible in theory but to become a good tool we need     
42:47     
to be able to make good estimates of different things in the world So and     
42:52     
this is of course um relevant to artificial intelligence where you know     
42:58     
or in in continual learning where you have this thing where you have to kind     
43:04     
of engage in the world in real time and you don't know what you're going to find     
43:10     
and sometimes you don't know the parameters of the problem that you're trying to solve     
43:16     
So that's u kind of getting at that     
43:22     
point Uh then they have argument three in terms they phrase that in terms of     
43:28     
resource rationality and then figure or argument four in terms of     
43:34     
neuroscience And so this kind of talks about how we have uh networks of spiking     
43:43     
neurons and the way that they are able to learn behavior And it kind of extends this to     
43:50     
reinforcement and learning at this point because that's kind of the natural connection between neural networks and     
43:59     
inference Okay So that's a very good paper It's very long and I'm not going to go over very much more of it because     
44:04     
I think we spend enough time on it Uh do we have any comments about     
44:17     
this um can you hear me okay Yeah I just     
44:22     
I got a I got a camera for my my Linux box So yeah I I I wanted to stop looking     
44:30     
at my iPad while anyway     
44:36     
Uh yeah Well we're going to see a lot more of     
44:42     
this is my is my comment Uh     
44:49     
and the um who's the Google deep mind guy david     
44:55     
Silver David Silver had a a a interview called talk     
45:04     
um a Saom interview with uh Hannah Fry     
45:10     
you know So so like Deep Mind hired Hannah Fry to be their science communicator Yeah I don't know if you've     
45:17     
seen this Yeah And um anyway he was talking yesterday or did they he was     
45:24     
talking this week about uh the the age of human     
45:32     
uh human knowledge AI is is coming to a     
45:38     
close and and what will power the the     
45:45     
next wave So basically this I mean or it's     
45:52     
basically kind of metalarning right allowing allowing the computer to form its own experiences and allow the     
45:59     
algorithms to their own experiences That's what it just made me think of right his discussion of this and     
46:12     
and this seems to be kind of trying to be an example of     
46:29     
that That is not much of a comment     
46:36     
Why do you think we'll be seeing a lot more of it well I mean his point is     
46:42     
is you know it's really just expanding expanding on his point     
46:48     
or summarizing his point that     
46:55     
that you know part of it is a slam on large language models right that that     
47:02     
Yes Okay You've trained on all accident text and and you've you've derived     
47:12     
this this um this artifact from     
47:17     
from what what can be contained in language structure as well as as well as     
47:23     
knowledge Right however reasoning and things like that     
47:29     
have become very secondary goal What you see with     
47:36     
you know Deep Seek and one and these you know the things things we've covered     
47:43     
recently right um and it's you     
47:49     
know perhaps people who decide trade wars on the basis of chat GPT and use     
47:55     
use algorithms that you know that the models really just don't understand Yeah     
48:01     
Like they don't they don't get what they're doing     
48:07     
Well he he he was trying to make the point that he humans really value the     
48:14     
the knowledge that they've put together in the sense of like they they think that this is valuable Yeah And and kind     
48:22     
of pinnacle Um but you know he he's trying to make the case that that the     
48:30     
problem with current levels of of AI is that they're they're not their own     
48:37     
learning systems They're not they're they're not learning how to learn Uh I     
48:43     
think is is is kind of his uh his case And and I if if we if we focused on     
48:52     
having them learn how to learn then they would be able to     
48:59     
generate their own kind of knowledge stores Uh uh through through these kinds     
49:07     
of interactions or you know through through interactions they would create these knowledge stores and and Yeah and they     
49:17     
would you know I think he was trying to say learn like babies Yeah Everyone says that now     
49:25     
He he's he's not um you know I've never seen in his work the same kind of     
49:32     
um the [Music]     
49:38     
same no not respect I'm trying to find not sure the word but     
49:43     
um uh emphasis that you see with like Josh Tannon you know on on     
49:52     
developmental you know ch childlike activities Yeah     
49:58     
But but I but I but I think he does have he has the um he has the Kenneth Stanley     
50:05     
kind of curiosity you know     
50:11     
uh respect Yeah     
50:16     
Yeah Yeah I don't know if VT or S had any thoughts on those Uh like current AI     
50:23     
systems are not thinking on their own I heard that that resonated with me a bit     
50:28     
because even I've read a lot of these things uh recently of how like the next     
50:35     
generation of AI or AGI is just supposed to be that like it's like because     
50:40     
everything that is now is just it's reproducing information in a way and we     
50:46     
are hoping that the next what we are able to do is actually able to create something but I don't I haven't seen you     
50:53     
know anything in the current state of the art where it has happened yet so     
50:59     
yeah I mean that that part I agree on right yeah that's     
51:06     
yeah I think in this paper they're showing that there's sort of this you know there's this supervised learning     
51:12     
where you have labels and things that you can measure You have an easily defined     
51:18     
problem and then you have this other algorithm that's kind of learning about that     
51:24     
process instead of from the data It's kind of optimizing that process And so     
51:31     
like you know it's kind of like if you learn something for the first time then     
51:37     
you reflect on it I mean that's I guess what they're trying to replicate And then when they do that they get you know     
51:44     
they get a better result It's a more refined result So if I think of like you know I can learn things I can observe     
51:51     
data I can use this sort of posterior log likelihood I mean I don't     
51:57     
do that like I don't state it but that's the idea in these computational models     
52:03     
is that I'm doing that calculation and then I'm learning how to optimize my learning process     
52:10     
Now the question of course is is that a realistic view of say like human learning You could have it for machine     
52:16     
learning and you know it it works to some extent but then you know the idea of it does learning actually work that     
52:23     
way because a lot of our machine learning models are drawn from human models and other animal models but     
52:30     
mainly human models And so the question is do we actually do that or do we do something     
52:36     
analogous to that in other words we use something as compact as a log likelihood     
52:41     
calculation and use that to sort of optimize our learning Do we even reflect     
52:46     
upon all of because we might reflect upon you know learning if we're like     
52:52     
reciting if we're learning the lyrics to a song reciting it But if you're learning something like how to ride a     
52:59     
bike or do something some sort of procedural learning uh you know that may not always be the     
53:06     
case You might have like this different type of you know make this     
53:11     
different type of calculation but I don't know it's a good question um so     
53:16     
that that's the criticism I think of a lot of or would be the criticism of any metal model is you know we I guess we     
53:26     
kind of agree that like we kind of reflect on what we learn what we're exposed to but is that really something     
53:33     
that benefits learning to the extent that the metal learning model suggests In other words like is it     
53:42     
important to reflect on something or is it just you know important to be able to     
53:48     
consolidate your over time which means you might uh sleep on it and then dream     
53:54     
about some procedure like if you're trying to trace a route out in your head     
53:59     
and you consolidate that knowledge Um so that's I mean is that reflection     
54:06     
is that metalarning or is that just like consolidating all the data that you've gathered building a     
54:14     
model you know it's it's hard to say exactly what metaphor is     
54:21     
best but but you'd agree that um it's the developmental psychologists that     
54:28     
think about this the most Okay Or well you know like like     
54:34     
I I mean not not maybe only right but     
54:40     
um you know again the differences between language learning in     
54:47     
infants you know learning to ride bike learning to you know like     
54:55     
like as a kind of like separate kind of skill you know um like what What     
55:03     
algorithms go into that     
55:08     
what yeah And and it's probably hybrid Yeah Yeah You know     
55:15     
like like it's probably mixtures of of systems right     
55:22     
yeah It's it's um Yeah And then tying it back to the neuroscience of course you know what     
55:29     
structures are being used in in learning and and depending what you're learning it's different systems but then what's     
55:36     
the metal learning for each system So like procedural learning uses a certain set of structures maybe like declarative     
55:45     
learning uses another set of structures and those metalarning processes would be different and you might want to merge     
55:51     
those two types of learning So that's maybe a third meta meta learning process     
55:58     
Yeah I mean I I think there's a there's a there's a hint in in at least Silver's     
56:06     
presentation that of course machines might     
56:13     
have like machines might do it differently Right Right Well yeah you know like like you know like like and     
56:22     
and So so in other words giving them an     
56:27     
algorithm that does metal learning is what they need Yeah I mean there there     
56:35     
is Yeah I mean I'm sure it's too simplistic     
56:43     
right but so the I'll try and find a link to that     
56:51     
just just so that you know Yeah Yeah Yeah     
56:57     
So yeah the other thing here of course then is continual learning and it's linked to that So continual learning is     
57:04     
where you're doing some naturalistic process or some naturalistic learning     
57:10     
which means you go through the world and you explore and you don't have these trial bytrial     
57:15     
presentations So if you're building a prior distribution it's from maybe like     
57:21     
isolated observations or it's sequences of observations that overlap and you're     
57:27     
getting these you might have multiple prior distributions depending where you     
57:32     
know what you're doing and where you are And so it's a lot harder to kind of     
57:37     
use that kind of metalarning model in this case because you're not only having     
57:43     
to take these naturalistic streams and segment them and figure     
57:48     
out you know what am I I'm learning about something by interacting with it     
57:53     
at different time scales different instances It seems like a lot richer     
57:59     
data but at the same time it's harder to sort of integrate into a model And then how do     
58:05     
you learn about that like how do you do that in real time because you have to do that in real time You don't you can't     
58:12     
take the learning experience offline and then learn about it     
58:17     
So I mean you know I guess they did show like that there's a sort of continuous structure at least to some extent in the     
58:26     
basian case where they have like each observation is updated and then getting     
58:32     
updated as it contributes to that prior distribution but uh you know that's and     
58:38     
that can lead to a lot of fluctuations in performance really if you kind of     
58:43     
observe only a couple of instances of something your performance is going to be really weird until you get down to     
58:50     
like some maybe an aggregating maybe a hundred or a thousand     
58:55     
observations as you saw in the lo in the um in the loss graphs you know you have     
59:01     
like the optimal days which is flat which is kind of your control and then     
59:06     
you have this metalarning uh system where it starts with a very     
59:12     
high loss and then it kind of converges But that takes a while to do And I was     
59:18     
thinking you know in the continuous case you're going to have this problem where you're observing things in the world     
59:24     
maybe for the first time You're trying to make sense of them And so that loss is very great for a while and then it     
59:30     
kind of settles down And I mean that might be expected I mean that's kind of maybe what we're doing in development     
59:36     
too is you know we have this I guess I don't want to call it a loss uh rate but     
59:42     
like um you know It's like an error rate maybe or like um a category error rate     
59:50     
and it goes down as we learn more and more about things But that category error though that error rate when it's     
59:55     
high it can provide opportunities for learning of itself because there are a     
1:00:01     
lot of things that you can put together from making errors uh you know a lot of     
1:00:08     
creativity So it's uh it's very interesting     
1:00:14     
how you know machine learning kind of does its own thing in a lot of ways like it has to because you're building things     
1:00:22     
that are doing things that are separate like very different from human cognition a lot of times     
1:00:30     
So so that was a great VD that was a good paper Um and yeah it's     
1:00:38     
definitely interesting area of research So this is YouTube video for what that's just the the David Silver Okay All right     
1:00:46     
So let's move on Um last time we talked about actually we were talking about     
1:00:51     
continual learning or continuous learning in humans and I was talking about this time     
1:00:58     
course that we use in like doing single trial observations So this is a a     
1:01:06     
network here It's a kind of a embodied neural network because it     
1:01:13     
deals with not just the brain but the spinal cord and the peripheral nervous system as well And so     
1:01:20     
this child is interacting with a video game console and this is showing the     
1:01:26     
different parts of the nervous system both central and peripheral and where things are     
1:01:34     
happening at what time scales So remember I said that there are these time scales We have like the millisecond     
1:01:39     
time scale and then we have the minute time scale and the hour time scale And so like this is one kind of slice or     
1:01:48     
snapshot of this child interacting with this console We're taking in a visual     
1:01:54     
image in 20 to 40 milliseconds That visual image is being     
1:01:59     
relayed to the retina It's going down to V1 at 60 to 90 milliseconds and then     
1:02:04     
it's going for back forward to the infrmporal uh cortex at 150 milliseconds It's going     
1:02:12     
to prefrontal cortex at 180 milliseconds So this is like a signal or the information that's being relayed and     
1:02:18     
these are kind of the estimates of when the information arrives in a certain     
1:02:24     
anatomical location Uh then you know prefrontal cortex at     
1:02:29     
180 milliseconds then medial cortex at 220     
1:02:35     
milliseconds and then of course it goes back down to the spinal cord and then it     
1:02:40     
goes to the fingers at 280 to 400 milliseconds where that information then     
1:02:46     
tells the fingers what to do So you go from like seeing something on a     
1:02:51     
screen processing what that is making a maybe a prediction about what to do next     
1:02:57     
and then sending a command signal through the spinal cord to the fingers     
1:03:03     
And then there's a but now you know this is of course we     
1:03:08     
could make a shortcut here with a brain machine interface we could record the     
1:03:14     
signal in um the MC and then have a a prosthetic that     
1:03:20     
does a button press for us so that if we can interpret that signal properly then     
1:03:27     
we can make that we maybe can shorten that a little bit or you know if you don't have fingers to use we can     
1:03:35     
correctly interpret that signal and produce an output So there's this closed loop between the screen and then the     
1:03:43     
controller and the human is in the loop basically And so that's kind of what     
1:03:49     
this is describing Now when I talked about last week is that you know you have this you can imagine this child     
1:03:56     
playing with this console for maybe 40 minutes And so at each point this is     
1:04:03     
just representing one instance which is like one kind of unit     
1:04:10     
of action where you see something in a screen you respond to it you use your     
1:04:16     
finger to respond to it And that's like one instance And of course this happens     
1:04:23     
many many times over the course of the game play which is like 40 minutes This     
1:04:29     
is you know and information is not only getting routed through these centers but     
1:04:34     
it's accumulating Furthermore you have this sort of refractory period and this adaptation in     
1:04:41     
these regions where if you know there's enough information that goes through there over time it starts to adapt to     
1:04:50     
that information It starts to make things more optimal in terms of the flow     
1:04:55     
of the information but it also starts to have these sort of collective effects that can have you     
1:05:03     
know that can change how that information is processed over time almost like these avalanches of effects     
1:05:12     
And so if you know you think about learning you know if you're playing the game and you're responding to things     
1:05:19     
kind of in in the im immediate now eventually that experience will build up     
1:05:26     
and you'll kind of maybe figure out how to do something make a shortcut in the     
1:05:31     
action of the game play and that changes how your fingers move That changes how you process the information We know from     
1:05:38     
learning that sometimes you know the processing of information speeds up with     
1:05:45     
learning Sometimes we have interference with learning You know there are these all these effects that we can describe     
1:05:51     
that happen at a higher time scale than what this is showing     
1:05:57     
So I just wanted to go back to this to kind of cover what we had talked about last week with that timeline and what that looks like with     
1:06:04     
the brain what that looks like with these closing action systems and so forth     
1:06:10     
Well and and just also adds you know trying to capture that Yeah     
1:06:20     
milliseconds you know millisecond by millisecond right is is you know a big     
1:06:25     
part of of why people still use EEG right yeah I mean you know like like     
1:06:33     
trying to capture that with fMRI is is you know you you end up     
1:06:40     
doing Yeah FO focusing on kind of one part of that or something like that so     
1:06:46     
that you can um deal with the the the kind of     
1:06:54     
temporal the temporal scale that you're collecting data Um but you you can     
1:07:00     
capture that millisecond by millisecond you know transfer and back and forth closed     
1:07:09     
loops and recurrence with with EEG     
1:07:17     
Yeah Uh yeah So I mean and that's of course the way that they do a lot of     
1:07:24     
brain computer interfaces They use some sort of electrophysiological measure Sometimes they'll use effne But     
1:07:30     
sometimes you're trying to get a signal like if this area is activated and you know that's that's     
1:07:36     
kind of so you can you know but the point here is that like that activity     
1:07:41     
will change over time you know you're measuring this sort of dynamic uh set of     
1:07:47     
signals and there's you know uh all sorts of effects that happen over one of     
1:07:53     
the time scales So but yeah you get the measurements of that kind of process     
1:07:58     
from electrophysiology EEG specifically So yeah that was this point     
1:08:05     
here But I'm I'm trying to make a broader point here which is that this is in the human brain And of course if we     
1:08:12     
think about primate brains it's a little bit different And then we go farther out and we start to get into different you     
1:08:19     
know brains with different features And so this process of interacting with the stimulus is much     
1:08:26     
different So this brings us to um this let's     
1:08:34     
see this brings us to this article here So this is from quantum     
1:08:39     
magazine and this is um says evol intelligence evolved at least twice in     
1:08:45     
vertebrate animals So this is talking about how     
1:08:50     
invertebrates which is anything from fishes to mammals birds and     
1:08:56     
amphibians you know in the mix and you know that includes a lot of different um     
1:09:04     
taxa a lot of different species We see at least twice that different forms of     
1:09:10     
intelligence involved So we see this in um we see one form of intelligence in     
1:09:17     
mammals and then we see another form of intelligence in birds And what we mean by a form of     
1:09:22     
intelligence is that it's based on different neural circuits or different sets of neural circuits     
1:09:30     
So if we go back to this figure you know this is implying that there's a neural circuitry to this action and that has a     
1:09:38     
certain time scale and the time scales based on connectivity between these     
1:09:43     
areas In mammals you know this varies by     
1:09:48     
species You get wildly different um you know body plans or body shapes you get     
1:09:57     
different appendages that are interacting with basically the same appendages but different configured in     
1:10:02     
different ways So if you go from uh primates to bats you know you have different ways that they interact with     
1:10:08     
their environment Um they go from bipeds to quadripeds and so on and so forth But     
1:10:16     
with birds you see this uh you know distinctly different set of     
1:10:21     
neural circuits that are involved in intelligence So     
1:10:27     
um and so okay let's start with this So um starts with humans tend to put our     
1:10:34     
own intelligence on a pedestal Our brains can do math employ logic explore     
1:10:40     
abstractions and think critically We can't claim a monopoly on thought So     
1:10:46     
there are all sorts of non-human species which have intelligent behavior Of course a lot of birds have very     
1:10:52     
intelligent behavior and they have a different neural circuitry for this     
1:10:58     
intelligent behavior So ravens plan for the future Crows count and use tools     
1:11:04     
Cockatus open and page booby trap garbage cans And chickies keep track of tens of thousands of seeds dashed across     
1:11:11     
the landscape So birds achieve such feats of brains that look completely different     
1:11:17     
from ours They're smaller and lack the highly organized structures that scientists associate with mamalian     
1:11:24     
intelligence And so this statement here a bird with a 10 g brain is doing pretty     
1:11:30     
much the same as a chimp with a 400 g Uh how is this possible so this an aside to     
1:11:38     
this is the work that primatologists     
1:11:44     
and biological anthropologists have done on the brain size growth So or cortical     
1:11:50     
growth And so one of the ideas about why humans are so smart is that in primates     
1:11:58     
you have this growth of the cortical sheet which when folded up forms the neoortex or the front of the mamalian     
1:12:05     
brain And so in in um in primates you see a growth of this     
1:12:12     
from monkeys to great apes to humans to homminids And so this grows by quite a     
1:12:19     
bit And the idea was that okay that the growth of the sheet is responsible the expansion of the sheet in terms of its     
1:12:26     
size is responsible for um you know increases in intelligence and so you know you can     
1:12:32     
make statements about the relative intelligence of different primates and     
1:12:38     
what they were able to do behaviorally But of course the problem with that is that it assumes a certain     
1:12:44     
uh neural architecture is responsible for this intelligence And so what they're showing here is that birds have     
1:12:51     
a different organization They actually have an expanded palium instead of an expanded     
1:12:58     
neoortex and they can do a lot of the same things at least in terms of     
1:13:03     
planning and maybe this sort of metacognition where they're actually reflecting on their own learning and     
1:13:10     
they're doing things uh acting So researchers have long debated     
1:13:16     
about the relationship between aven and mamalian intelligences One possibility is that intelligence invertebrates     
1:13:23     
animals with backbones including mammals and birds evolved once So there's this     
1:13:29     
idea that you have uh that mammals and birds have a common     
1:13:35     
ancestor that in that common ancestor you get the evolution of intelligence     
1:13:40     
and that that intelligence diversifies in birds and diversifies in mammals in different ways which is you know a     
1:13:48     
hypothesis right in this case both groups would have inherited a complex     
1:13:54     
set of neural pathways that support cognition from a common ancestor     
1:14:00     
Um and you know you should see actually homologies between these two So they     
1:14:05     
shouldn't look that radically different They should just maybe emphasize different things And of course we don't     
1:14:11     
necessarily see that It's hard to say what you know if these regions are     
1:14:17     
homologous I mean we don't think they're homologous people have done a lot of work on this But basically the the     
1:14:24     
question is whether or not this intelligence comes from a common ancestor Okay So the other possibility     
1:14:31     
though is that the kinds of neural circuits that support vertebrate intelligence and bird intelligence     
1:14:38     
evolved independently So bird intelligence has one set of mechanisms     
1:14:45     
Verte intelligence has another set of mechanisms Neither of those are particularly     
1:14:50     
homologous They are an example of parallel evolution where you get uh a     
1:14:56     
specific type of function from multiple sources So they may have had a common     
1:15:01     
ancestor but that common ancestor didn't have sort of the basis for intelligence     
1:15:08     
as things evolved independently It's hard to track down which path     
1:15:13     
evolution took given that any trace of the ancient ancestors actual brain vanished in a geologic link So yeah you     
1:15:21     
can do things like get endoccasts but it's hard to really make any sort of statement about what those     
1:15:27     
ancient brains looked like and especially how they behave how those     
1:15:32     
brains gave an behavior So you can only kind of make inferences from extent     
1:15:39     
species and the sort of the brain structure that you know you can get from endoccasts and it's it's kind of a tough     
1:15:47     
business and it's really not going to answer this basic question Okay So you can actually take     
1:15:55     
approaches such as comparing brain structures in adult and developing animals to piece together how this kind     
1:16:02     
of neurobiological complexity might have emerged So this article points to some studies     
1:16:08     
So there's this series of studies published in science uh in February that     
1:16:14     
provide the best evidence yet that birds and mammals did not inherit the neural pathways that generate intelligence from     
1:16:20     
a common ancestor but rather involved them independent So this study     
1:16:26     
here in particular or actually I think this is describing the studies this is constrain     
1:16:34     
roads to complex brains neural development and brain circuit evolution converged in birds and mammals and so     
1:16:41     
this talks about these articles where they're talking about this evidence for this uh convergent evolution     
1:16:50     
hypothesis So again we think that one of the drivers of intelligence or the     
1:16:56     
evolution of intelligence is this arms race for survival where you have     
1:17:02     
competition and you try to outs survive your competition So you grow     
1:17:07     
everinccreasing structures of everinccreasing size or structures of ever increasing complexity And so this     
1:17:15     
is one hypothesis for why you would see the evolutional intelligence You know you need it you     
1:17:22     
need to use it and you need to outwit the rest of the natural world And so um     
1:17:30     
that's what they refer to by arms race Uh they they say that highly     
1:17:35     
intelligent biological systems have emerged only a few times So this is of course excluding insects which we can     
1:17:43     
not get into here because it's you know that they also exhibit a lot of intelligent highly intelligent     
1:17:49     
behavior but that's of course that's known to be an independent     
1:17:55     
origin among vertebrates Mammals and birds can solve complex problems use     
1:18:00     
tools and engage in elaborate social behavior So this is their standard for highly intelligent um having tool use     
1:18:09     
social behaviors and being able to solve complex problems These sophisticated tasks     
1:18:15     
involve the palium the brain region most implicated in cognition which includes     
1:18:20     
the neoortex and mammals So this is the point I mentioned earlier that there's this region called the palium that is     
1:18:28     
in mam in mammals it's like underneath the neoortex and you have I guess some     
1:18:36     
neuroanatomists consider the palium and neoortex to be contiguous but in in mammals you have     
1:18:43     
the neoortex on top and it's expanded in birds you have the palium that's expanded and the neoortex that they have     
1:18:50     
is not expanded And so there's this difference in sort of the neural architecture There also differences in     
1:18:58     
centers that are kind of highlighted as the hallmarks of intelligence Um so     
1:19:04     
there's a difference at neuro anatom anatomical difference functional difference And so there is this kind of     
1:19:12     
you know evidence for parallel evolution We're using different structures The     
1:19:18     
structures have evolved in different ways However it is unclear whether complex     
1:19:24     
brains evolve multiple times through similar or different mechanisms We don't know if similar     
1:19:30     
mechanisms were uh responsible for this converg evolution or different mechanisms were responsible for this     
1:19:38     
converg Um so they t a couple of articles here is zerra at all hecker at     
1:19:45     
all rad at all respectively provide evidence for the convergent development     
1:19:50     
and evolution of neurons in their connection in the burden male paleia highlighting the need for     
1:19:57     
multiple perspectives in brain comparative studies So this is where again you have     
1:20:03     
these structures that are very similar They don't necessarily evolve intelligence and the common ancestor but     
1:20:10     
they have the same mechanisms that allow intelligence to evolve in different     
1:20:16     
parts of uh the fogyny of birds and mammals Okay So there's some related     
1:20:23     
research articles here uh the evolutionary convergence of sensory circuits in the palium of     
1:20:30     
amnotes Enhancer driven cell type comparisons reveal similarities between     
1:20:35     
mamalian and bird palium and then developmental origins and evolution of paleo cell types and structures and     
1:20:42     
birds So they're actually doing some developmental research here as well as evolutionary research     
1:20:50     
Um so this suggests that vertebrate intelligence rose not once but multiple     
1:20:57     
times Still their neural complexity didn't evolve in a wildly different directions Aven and mamalian brains     
1:21:03     
display surprisingly similar circuits Not identical but     
1:21:09     
similar It's a milestone in the quest to understand and to integrate the different ideas about the evolution of     
1:21:16     
vertebrate intelligence The findings emerge in a world     
1:21:22     
enraptured by artificial forms of intelligence They could teach us something about how complex circuits in     
1:21:27     
our own brains evolved And it might help us step away from the idea that we are     
1:21:33     
the best creatures in the world especially in terms of to model artificial intelligence We are not     
1:21:41     
the optimal solution of intelligence So birds have this other model of intelligence     
1:21:47     
In fact other ma other mammals have you know can be highly intelligent as well     
1:21:53     
And that's something that is you know I don't have the studying you know I'm not     
1:21:59     
going to get into that those distinctions but that's another discussion we could have as well But the     
1:22:06     
idea here that I kind of want to draw out is that artificial intelligence this is really based on kind of human     
1:22:13     
intelligence what humans do well and so forth And so any other sort of type of you     
1:22:20     
know other system where you have different things that are emphasized     
1:22:26     
different structures that are emphasized different behaviors are emphasized aren't really captured or     
1:22:33     
artificial So um so there was this bias against studying birds     
1:22:40     
uh they lacked anything resembling a neoortex and people simply thought that     
1:22:46     
they weren't that smart because of it Um and so for the longest time it was     
1:22:52     
thought that this is the center of cognition and you need this kind of anatomy to develop advanced cognitive     
1:22:58     
abilities and they're referring to the neoortex So you know uh intelligence     
1:23:03     
research for many years was very neoortex ccentric and so they didn't     
1:23:09     
really want to use birds as a model system Uh Harvey Carton was pictured     
1:23:14     
here He was one of the original he was one of the pioneers in looking at a     
1:23:20     
neural circuits and how those neural circuits actually produce quite intelligently     
1:23:27     
Um and so kind of getting into um you know bird aven anatomy or aven     
1:23:35     
circuits uh rather than neat layers birds have unspecified balls of neurons without     
1:23:41     
landmarks or distinctions These structures compelled neuroanatomists a century ago to suggest     
1:23:48     
that much of bird behavior is reflexive instead of um reflective I guess and not     
1:23:55     
driven by learning and decision This implies that what a mammal can learn easily a bird will never learn And so     
1:24:02     
that's obviously not the case as we've seen in subsequent years His     
1:24:08     
conventional thinking started to change in the 1960s when Harvey Carton Napton     
1:24:13     
compared brain circuits in mammals and pigeons and later in owls chickens and other birds What he found was a surprise     
1:24:21     
The brain regions thought to be involved only in reflexive movements were built from neural circuits networks of     
1:24:27     
interconnected neurons So they had this sort of assumption about what kinds of     
1:24:32     
behaviors were possible with a certain type of neural anatomy and Harvey     
1:24:38     
Curtain showed that you didn't you know that you could actually get from this different type of neural circuit uh     
1:24:45     
behaviors that weren't simply reflexive Um and so that's and they     
1:24:51     
actually because you have these network of interconnected neurons they resembled what you see in the mamalian     
1:24:58     
neoortex and those are the mechanisms maybe of intelligence rather than the     
1:25:03     
neural circuit itself This reason region in the birdb brain the dorsal ventricular ridge DVR     
1:25:12     
seems to be comparable to a neoortex It just didn't look like it So it didn't look like it but it shared sort of the     
1:25:18     
cellular components or similar cellular components similar synaptic components     
1:25:24     
and so forth In 1969 Carton wrote a very influential paper that completely     
1:25:30     
changed the discussion in the field His work was really revolutionary He     
1:25:36     
concluded that because aven and mamalian circuits were similar they were inherited from a common ancestor So this     
1:25:42     
is where we get this common ancestry hypothesis So this is the original paper     
1:25:49     
here Uh the organization of the alien tensilin and some speculations in the     
1:25:54     
fogyny of the amnotens This is where they're he's making this connection between the     
1:26:00     
structure called the telenphylin and the u you know between     
1:26:06     
aven mammals Now this this of course these new papers     
1:26:13     
are kind of working against the assumptions of     
1:26:18     
Harvey Carton at least the ones about the source of intelligence and evolution     
1:26:27     
Um so a few decades lateralis an anatomist at the University     
1:26:33     
of Mercy in Spain drew the opposite conclusion to carton by comparing embryos at various stages of development     
1:26:41     
He found that the mamalian neoortex and aven DVR So these are the two sort of     
1:26:48     
homologous structures uh or at least hypothesized to be     
1:26:53     
homologous developed from distinct areas of the embryos paleium So they're looking at     
1:26:59     
embryogenesis and they're looking at the source of these different uh so-called     
1:27:05     
homologous structures uh so but they developed from distinct areas of a number palium a brain region shared by     
1:27:13     
all vertebrates He concluded that the structures must have evolved independently So again looking at     
1:27:19     
different types of data can tell you some different things about     
1:27:25     
uh you know the the source of these things especially in terms of evolution     
1:27:31     
look at like anatomical data molecular data developmental data different     
1:27:37     
conclusions So Curtain and Pis uh were given completely different answers to     
1:27:43     
the big question The debate continued for decades During this time biologists     
1:27:48     
also began to appreciate bird intelligence starting with their studies of Alex and African great parrot     
1:27:55     
Um however neither group seemed to want to resolve the discrepancy between the two theories and how vertebrate peliums     
1:28:02     
evolved You know they kept working on their own method One can't continue to compare the circuitry in adult     
1:28:08     
vertebrate brains The other focused on embriionic development So this is where     
1:28:13     
you have these two different sources of evidence that are given conflicting answers And so in these new studies we     
1:28:20     
tried to put everything together Okay So that's great Um but     
1:28:26     
then we have molecular data So um two     
1:28:31     
new studies which were conducted by independent teams of researchers relying on the same powerful tool for     
1:28:37     
identifying cell types known as single cell RNA sequencing So using SCRNA seek     
1:28:45     
able to compare normal circuits as carton did not only in adult brains but all the way through embryionic     
1:28:51     
development In this way they could see where the cells started growing in the embryo and where they ended up in the     
1:28:57     
mature animal So this is where you have you can trace cells migration through     
1:29:03     
the developmental process their origin and how they ended up in different structures both in mammals and     
1:29:11     
in so you can uh get a sense of what's being expressed in the different cells     
1:29:19     
um and you know find source cells that kind of express the same things as as the ones at their     
1:29:26     
destination So for their study Garcia Moreno and his     
1:29:31     
team wanted to watch how brain circuitry develops using RNA sequencing and other     
1:29:37     
techniques They track cells in the palians of chickens mice and geckos at various stages to time sample when     
1:29:44     
different types of neurons were generated and where they mature Okay so they're able to use this     
1:29:52     
time stamp method They found that the mature circuits look remarkably alike across animals Just as carton and others     
1:30:00     
had noted they were built differently Uh the circuits that composed the male cortex and Aven DVR     
1:30:08     
developed at different times in different orders and in different regions So this is this figure here     
1:30:16     
Um this describes um this common neural pathway So in     
1:30:22     
birds and mammals the neural pathways that underly complex cognition are the same Both process sensory inputs and     
1:30:29     
output information to motor centers drive behavior So we saw with this figure here we have you know an input     
1:30:38     
sensory input gets processed um and then it goes down the spinal cord     
1:30:44     
and out into theectors So this is the kind of the mapping this     
1:30:51     
neural pathway We start with the phalamus which is a deep structure     
1:30:56     
underneath the paleium cortex that sends signals from sensory organs to the uh     
1:31:05     
the part where things get processed So you start with the phalamus you go to the input neurons you go to integrator     
1:31:13     
neurons and then to output neurons So you have these three layers of neurons Input neurons that take things in from     
1:31:19     
the phalamus places where that information gets integrated and then an output layer of neurons that then     
1:31:28     
uh sends connections to motor centers So down the spinal cord down to the uh like     
1:31:35     
the arms and the legs or you know you know different aector organs So uh this     
1:31:44     
is the basic neural pathway You see this in bird brains you see this in mammal     
1:31:49     
brains So however in each class these pathways are also located in different brain regions So in birds we have the     
1:31:56     
dorsal ventricular ridge or DVR and in mammals we have the neoortex So this is     
1:32:02     
the DVR in bird brains and this is the neoortex in the male So you can see that     
1:32:08     
there's this difference in chemical location Um and     
1:32:14     
then we see here as a closeup we have these input neurons here integrator     
1:32:21     
neurons and output neurons So coming from the phalamus one two three and then back up male brain we have neoortex     
1:32:29     
doing the same thing We have a similar set of of neuron types in this neural     
1:32:34     
pathway input integrator and output And then it goes back out down to the spinal     
1:32:40     
cord So that one is the spinal We have this loop where we have these three     
1:32:45     
different types of Okay So that's um and so this is the     
1:32:51     
paper here I think Um this is the yeah this is the Garcia Moreno paper     
1:32:59     
Um this is evolutionary convergence of sensory circuits and the paleium amniot     
1:33:06     
So this is the study here where they talk they do I guess the RNA seek and they use different techniques to give     
1:33:14     
um this this so they have um okay so let's see     
1:33:25     
um Elena at all integrated transcriptional analysis at single cell     
1:33:30     
resolution mathematical modeling to investigate the development of sensory circuits and chicken gecko and mouse is     
1:33:37     
a Remmber Edall which is a different paper generated a spatially resolved cell atlas and chicken palium and     
1:33:44     
compared it with mouse two lizards and a turtle to interrogate the conservation of cell states So they're adding in the     
1:33:51     
lizards and turtle because they want out groups So in modifi genetic analysis you     
1:33:58     
want the nearest set of taxa that are sort of um related to the common     
1:34:06     
ancestor by another common ancestor a deeper common ancestor And so you'll     
1:34:11     
you'll find these examples of lizards and amphibians which will give you a     
1:34:17     
sense of you know an open So this is uh     
1:34:23     
the reason this spatially resolved cell atlas to interrogate the conservation of cell states is to see if those cellular     
1:34:30     
states uh are you know common to the bird and mamalian common ancestor if     
1:34:39     
they exist deeper in the tree of life or if they are independently derived     
1:34:46     
Pecker at all developed deep learning models to identify shared and divergent regulatory signatures across to sephon     
1:34:53     
cell types in chicken human and mouse So this again is where we have comparing     
1:35:00     
different mammals with the aven and seeing if we have these regulatory     
1:35:06     
signatures How divergent are they how shared are so these studies together increase     
1:35:12     
our understanding of the evolution and development of the amnopra     
1:35:17     
Okay so amnotes are all um animals with an amniotic set So this     
1:35:25     
is the sort of the level and then within you have within that you have     
1:35:30     
um avens and mammals     
1:35:37     
Okay we're here Okay so that's the figure here I'm going to point that out     
1:35:44     
Um then they talk more about the RNA seek They talk about how these papers all taken     
1:35:52     
together provide the clearest evidence yet that birds and mammals independently evolved three regions for complex     
1:35:59     
cognition Um and that there's this independent evolution of these     
1:36:04     
structures and therefore there's some independent evolution of     
1:36:10     
intelligence or intelligent behavior Still it seems likely there was some inheritance from a common ancestor In     
1:36:18     
the third study that uses deep learning this is the deep learning technique that they applied that we talked about uh     
1:36:25     
Kempnik and his co-author Nikolai Hecker found that mice chickens and humans     
1:36:31     
share some stretches of DNA that influence the development of neoortex or DVR suggesting that similar genetic     
1:36:39     
tools are at work with both types of animals So they may not share the cell     
1:36:44     
signatures they may not share the same pathways but there are regulatory sequences that are common and so would     
1:36:52     
lead to these kind of pathways being similar pathways being formed similar     
1:36:57     
cell types being formed and thus similar types of uh     
1:37:04     
intelligence And as previous studies have suggested the research groups found that inhibitory neurons or those that     
1:37:11     
silence and modulate neural signals were conserved across birds and mammals So     
1:37:16     
again they have these inhibitory neurons And the important thing about inhibitory neurons is it sort of tunes or shapes     
1:37:23     
intelligent behavior So you talk about reflexive behavior That's where you have     
1:37:29     
a neural signal that kind of responds to some stimulus But it's not just as simple as     
1:37:35     
responding to a stimulus You need a lot of inhibitory neurons that control um     
1:37:41     
different neural signals So you can you know you can have things like smooth movements or you know things that     
1:37:49     
behaviors that aren't reflexive You can have metacognition basically and     
1:37:54     
inhibitory neurons play So these findings haven't completely     
1:38:00     
resolved the debate but we I think they were kind of saying that in these     
1:38:06     
studies the sort of the takeaway is that both of them are right none of them are     
1:38:11     
wrong which is you know kind of a weasly way to look at it maybe but     
1:38:18     
um so the next part is how to build     
1:38:23     
intelligence so intelligence doesn't come with an instruction it is hard to define There are no ideal     
1:38:30     
steps towards it and it doesn't have an optimal result Um you can have     
1:38:35     
innovations in evolution whether in terms of genetic regulation new neuron     
1:38:42     
types new circuits in the brain regions So this is kind of you know then we have     
1:38:48     
to connect that to behavior What kinds of behavior it generates     
1:38:54     
um one of the reasons I kind of like these papers is that really highlight a lot of differences It allows you to say     
1:39:00     
what are the different neural solutions that these organisms have come up with solve similar problems of living in a     
1:39:07     
complex world and being able to adapt in a rapidly changing trust     
1:39:12     
So this again is where you have these structures that lead to     
1:39:18     
different neural solutions that solve similar problems more or less and they respond     
1:39:25     
to the environment They're able to adapt So again we have other examples in     
1:39:33     
invertebrates We have octopuses and squids having structures that allow     
1:39:41     
for complex intelligent behavior We of course have social     
1:39:47     
insects We have birds bats and insects all kind of taking the skies on their     
1:39:53     
own Um so these are all things that we see many different places where     
1:39:59     
intelligent behavior evolves multiple times And again depending on how we describe intelligent     
1:40:05     
behavior you know we have all of these different types of solutions And what really counts here is that     
1:40:13     
um anatomy is basically putting solutions out there behaviors are being generated and then     
1:40:21     
those behaviors are sort of the basis maybe for metacognition maybe     
1:40:27     
for you know engaging in this arms race that increases the size and scope of the     
1:40:36     
anatomy So it's kind of an interesting way to look at     
1:40:43     
intelligence Um similarly there's limited degrees of freedom in which you can generate an intelligent brain at     
1:40:49     
least within vertebrates Drift outside the realm of vertebrates however and you can generate an intelligent brain in     
1:40:56     
much weirder ways So it's a wild west Octopuses for example evolved     
1:41:02     
intelligence in a way that's completely independent Their cognitive structures look nothing like ours except that     
1:41:08     
they're built from the same broad type of cell the neuron The octopuses have been caught performing incredible feats     
1:41:15     
such as escaping aquarium tanks solving puzzles unscrewing jar lids and carrying     
1:41:21     
shells as shields So how did octopuses evolve     
1:41:27     
intelligence using these divergent neural structures and if we could figure that out it might be possible to     
1:41:33     
pinpoint any absolute constraints and involving intelligence across all animal     
1:41:38     
species Um and so you know we could maybe ask     
1:41:43     
some questions about intelligence in different ways if we consider all the different types of intelligences And     
1:41:50     
we're talking about across animals so we're not getting into anything like plant cognition or any of these other uh     
1:41:58     
things that you might think of um or artificial intelligence Just think about     
1:42:04     
an animal intelligence So we need to kind of think about these shared features and they're not that it's not     
1:42:11     
that they're um not that they share a common ancestry although all animals do     
1:42:18     
share a common ancestry It's that these solutions keep cropping up in different     
1:42:23     
ways um again and again in the animal kingdom So they may share maybe a common     
1:42:29     
set of mechanisms that underly these solutions Um and so that's kind of what     
1:42:35     
maybe we want to look at So such findings could eventually reveal shared features and we can ask questions like     
1:42:42     
what are the building blocks of the brain that can think critically use tools or formats direct ideas of what     
1:42:49     
are the cells that need to be there what are the cellular relationships what are the uh genetic     
1:42:57     
regulatory networks that need to be in place within the cells and how how is     
1:43:02     
that all put together and they may be put together in different ways but those are the building blocks     
1:43:09     
um and we could also understand I think we could probably improve artificial intelligence they say it might help in     
1:43:16     
the search for extraterrestrial intelligence although it's hard to say why that would be relevant um for     
1:43:23     
example the way we currently think about using insights from evolution to improve AI is very     
1:43:29     
anthropocentric I would be really curious curious to see if we could build like artificial intelligence from a bird     
1:43:34     
perspective How does a bird think can we mimic that so that's uh that article I I like     
1:43:42     
it because it does give that alternate view of intelligence and it asks the     
1:43:47     
question or poses the question can we model intelligence you know we find sort of     
1:43:55     
the building blocks of intelligence We model that in different ways and generate different forms of intelligence     
1:44:02     
and then you know use that as sort of our model instead of kind of assuming rational decision-m model or     
1:44:09     
rational cognitive model or something else And of course our computational     
1:44:16     
models would look vastly different if we considered it from that perspective So you know if we said okay     
1:44:22     
we want to look at an octopus intelligence or bird intelligence how does that differ from a     
1:44:29     
human or mamalian intelligence and then what is the way     
1:44:34     
that that you know what kinds of models it's very different     
1:44:40     
Okay we have some things in the chat     
1:44:47     
Okay So are there any questions about that     
1:45:04     
sorry Bradley I'm I'm currently in the car Okay Um but uh no I was just uh yeah I mean I     
1:45:13     
I I saw this article too and um you know it it just makes me think of the the     
1:45:22     
new understanding and evolution that that you can have you know similar     
1:45:29     
structures kind of re     
1:45:34     
reemerge multiple times They don't have to be related     
1:45:40     
Yeah Anyway as well as like you know all the terrific work that's gone on with     
1:45:48     
with um bird learning Yeah     
1:45:54     
Yeah that's great Um and then of course the idea that you     
1:46:02     
know do we have like common building blocks across different     
1:46:08     
intelligence that's that's another interesting thing right right I mean like like yeah for     
1:46:15     
sure all the all the the leaven like arguments     
1:46:21     
yeah yeah so one of the things that we we were talking about a while back is     
1:46:26     
that you know going through these kind of definitions of intelligence where you know people have defined it kind of     
1:46:33     
largely from a behavioral standpoint Kind of thinking about what it is and how clear we define     
1:46:41     
it and we you know had gone through the literature a bit found that it's as     
1:46:47     
clear as mud really Um and the definitions are not very you know     
1:46:52     
they're always like many competing schools of thought They're kind of based on     
1:46:59     
um you know very limited aspects of behavior things like that     
1:47:04     
So I'm just thinking as I was reading through the article I was thinking about how you might define kind of     
1:47:12     
intelligence in terms of like these sorts of mechanisms that we     
1:47:18     
do intelligence or you know the actual behaviors themselves So I like in that     
1:47:24     
figure they showed the circuitry and they showed then birds and humans you have the same circuitry where you have     
1:47:32     
like three layers of neuronal types Then you also have these inhibitory     
1:47:37     
neurons So those are seem to be maybe key to producing certain types of     
1:47:42     
behavior So it's kind of an abstract definition on the one hand It wouldn't necessarily be useful for like a     
1:47:50     
psychologist but it would be useful for someone building an artificial     
1:47:55     
intelligence because then you could specify what kinds of parts you would need or say like     
1:48:03     
a could be a neural network it could be like some sort of uh reservoir network     
1:48:09     
or whatever And you could put those pieces together and say "Okay we have those parts." And in fact you know kind     
1:48:16     
of the way that neural networks work as much as they're not necessarily     
1:48:24     
a a model of the biology You see those same maybe sorts     
1:48:30     
of things happening there You have like a hidden layer and you have you know     
1:48:35     
your three layer networks You have multiple layers in some cases for deep learning you have many layers And so     
1:48:43     
maybe that's what's key to intelligence isn't really like the behavioral definition It's like these parts and     
1:48:50     
then when you get the parts in place and you can configure them in different ways the behaviors just kind of get     
1:48:57     
generated and it's you know then a matter of what environment that the     
1:49:02     
intelligence is in It's sort of its history of interacting with the world it     
1:49:09     
sort of history of of observing data and refining its answers from data and     
1:49:16     
things like that and then its ability to do that So if it can't uh select things from the     
1:49:25     
environment properly then it can't really it's not intelligent I mean if     
1:49:30     
you have like if you're just paritting back every answer that you generate then     
1:49:35     
that's not really intelligence it's kind of refining that     
1:49:45     
to and so yeah I don't know I don't know what the answer is but I think that's kind of interesting yeah definitions of     
1:49:51     
intelligence and we had a definition in the first paper that was     
1:49:57     
interesting but you know that's there a lot of definitions as I     
1:50:05     
said okay so that's it Uh oh go ahead Morgan     
1:50:11     
Uh no I was just gonna say you know yeah that that um it's really interesting to     
1:50:17     
look at the the people studying octopuses and and you know who have this these     
1:50:24     
same debates and the same same issues of how best to how best to measure it you     
1:50:30     
know or how best to to well what I like is um is to use the AI term how best to     
1:50:36     
benchmark Oh yeah Yeah     
1:50:41     
Yeah I think that's actually a good term for what we're talking about here because you have well you have a lot of     
1:50:48     
different uh the well you have a lot of different behaviors that have like some     
1:50:54     
similarities like if you were to say okay problem solving in mammals problem solving problem     
1:51:00     
solving go and then you you compare the solutions and it might be comparable but     
1:51:08     
you know it's best to sort of benchmark them in some way like if I have this     
1:51:13     
certain architecture here's the performance of these different tasks you     
1:51:18     
know they're they're not directly comparable you know some architectures are going to be better at some tasks     
1:51:24     
than others and you could make a table and you know then you could say okay well     
1:51:30     
my octopus like intelligence benchmarks well in these tests my mamalian like     
1:51:36     
intelligence is better in these tasks and so forth And you could say well do I want an octopus like intelligence or mamleon     
1:51:44     
like intelligence and for this task for this for     
1:51:51     
this you could open source the models and everything     
1:51:59     
So okay Well that's that's fun to think about     
1:52:04     
Um last thing I wanted to talk about today was to finish up with this paper here And this is kind of     
1:52:11     
an extension of what we've been talking about This is kind of getting     
1:52:17     
into and I don't have any papers right now on the octopus intelligence Maybe     
1:52:22     
I'll try to do that next week and follow up on this with the discussion But this     
1:52:28     
is um a paper on aven cognition or the     
1:52:34     
evolution of avian intelligence and it's a reviewed paper from 2006 called cognitive     
1:52:41     
ornithology So it's the study of bird cognition or aven     
1:52:47     
intelligence And so this is about comparative psychology So there's this     
1:52:52     
area of comparative psychology where you know psychologists will compare     
1:52:58     
different animal species with humans and get a sense of what that you know     
1:53:05     
they'll use that as sort of the way to gauge the evolution of intelligence     
1:53:11     
So a lot of comparative psychologists interested in the evolution of intelligence have focused their     
1:53:18     
attention on social primates Whereas birds tend to be used as models of associ which is interesting that they     
1:53:24     
have these different types of uh behaviors that they look at in     
1:53:30     
different species However corvids and parrots which have four brains relatively the same size as     
1:53:37     
apes live in complex social groups and have a long developmental period before     
1:53:43     
becoming independent So this is like in primates especially humans one of the     
1:53:49     
hallmarks of a bigger brain in primates is that you have this longer     
1:53:54     
developmental curve The thinking is is that you need these complex social groups to interact with     
1:54:01     
to become you know to fully mature And when you're mature you're much more     
1:54:06     
intelligent than um species with smaller     
1:54:12     
Okay So that's and then uh so there's this long developmental period complex     
1:54:18     
social groups um and these corvids and parrots have     
1:54:24     
demonstrated ape like intelligence as a result Um wherethologists have     
1:54:30     
documented thousands of hours observing birds in their natural habitat They focus their attention on     
1:54:37     
aven behavior ecology rather than intelligence So this review discusses recent studies     
1:54:43     
on aviant cognition contrasting two different approaches the anthropocentric approach which is where we view     
1:54:50     
intelligence from sort of a human perspective How different is human     
1:54:55     
cognition from that other birds and then the adaptive specialization approach     
1:55:01     
which is where you think about cognition as a series of adaptive     
1:55:06     
specializations and thus intelligence as a set of adaptive specializations It is argued that the     
1:55:12     
most productive method is to combine the two approaches This is discussed with respect to recent     
1:55:18     
investigations of two supposedly unique aspects of human cognition The first is     
1:55:24     
episodic memory The second is theory of mind And so this is where um you know     
1:55:30     
people throw this term theory of mind around a lot in AI But basically it's where you have an     
1:55:40     
intelligence that can think about what other intelligences are thinking This is     
1:55:45     
where you know you have a social group I'm an individual I can think about what     
1:55:50     
another individual in the group is thinking about and model that behavior So it's kind of like a     
1:55:56     
metacognition except it's in a different mind or a different brain     
1:56:01     
And so these are like supposed this is at one time people thought this was unique to humans and there's been some     
1:56:10     
kind of debate as to whether it's much more expansive across animals or not and     
1:56:16     
you know some of the tests of theory of mind and animals are kind of questionable So this is part of the     
1:56:22     
controversy but basically you know it's the ability     
1:56:28     
for an animal species to have individuals can think about what other individuals are thinking about And     
1:56:35     
that's and you know of course extending that to artificial intelligence it's even more questionable     
1:56:42     
as to how that's applied But anyways episodic memory of course is the memory of different episodes and being able to     
1:56:49     
recall them So those are usually thought of as unique aspects of     
1:56:55     
human Um in reviewing the evidence for aven intelligence however orids and     
1:57:01     
parrots appear to be cognitively superior to other birds and in many cases even apes This suggests that     
1:57:08     
complex cognition has evolved in species with very different brains or process of     
1:57:13     
convergent evolution rather than shared ancestry Although the notion that birds and mammals may may share a common     
1:57:20     
neural connectivity pattern is discussed So this is all stuff that we talked about in the last paper Um and so again     
1:57:29     
this is kind of moving us away from this anthropocentric view of intelligence and     
1:57:34     
towards a sort of view of intelligence where you have different intelligences that evolve in different uh plates of uh     
1:57:44     
the tree of life and you know they have maybe they have similar building blocks     
1:57:51     
but they're expressed in different ways They may be behavioral They're definitely different neuro     
1:57:59     
architectures Um so this is kind of talking about bird brains and how you     
1:58:07     
know a neoortex is uh basically the six layered structure where you have processing that goes from     
1:58:14     
the bottom to the top of the neoortex and each layer has some processing step     
1:58:21     
This is the basis of course for the cortical columns that they use um in in     
1:58:29     
Newa's uh computational models So this is something that is you this six layer     
1:58:35     
cortex is you find it in birds you find it in a lot of um vertebrates but it's     
1:58:43     
most highly expressed in mammals and especially in primates where it's     
1:58:49     
expanded quite a bit and you have this sort of processing power that is thought     
1:58:54     
to be sort of the seat of cognition or complex cognition So the idea that the     
1:59:00     
six layer neoortex of most mammals is the prerequisite for complex cognition     
1:59:05     
and this still pervades popular culture So the idea that you need this six layer neoortical structure is of course the     
1:59:13     
basis for NTA's model of intelligence but it's also sort of this idea that um     
1:59:21     
you know you're capturing basically intelligence with the structure and that you need to move towards a structure to     
1:59:28     
get the result Um let's see Um     
1:59:37     
so some you know a lot of comparative psychologists and neuroscientists also hold this sort of bias for six layer     
1:59:44     
cortex Um one reason for this long-held but     
1:59:49     
ultimately incorrect view is that confusing terminology used to name the different regions the alien     
1:59:56     
avi forbrain um is uh basically to confuse the     
2:00:03     
striatum which is part that's the aven cerebrum with sort of these parts of the     
2:00:09     
basil ganglia which are um involved in these more reflexive behaviors     
2:00:16     
So as the vertebrae basil ganglia is involved in species specific behaviors     
2:00:21     
such as maternal care sexual behavior and feeding bird brains were deemed incapable of producing flexible or     
2:00:28     
intelligent behavior It is now known that this nomenclature is based on a fallacy Large parts of a forebrain are     
2:00:36     
derived not from the striatam per se but from the palium So this is the part     
2:00:42     
that's enlarged and so they actually kind of thought that stratum was really     
2:00:49     
the part that was driving the intelligence of the pal in interesting     
2:00:55     
the male neoortex is also derived from the palium This places the aven forebrain into a     
2:01:02     
new light where bird brain bird behavior may now be explained as an adaptation to solving socioecological problems similar     
2:01:09     
to mammals possessing hardware that is different from mammals albe it evolve     
2:01:14     
from the same structure     
2:01:19     
Um so this is uh kind of what we look at when we look at     
2:01:25     
uh and sometimes when we look at animal intelligence or comparative cognition we     
2:01:31     
often look at the size of the structures generating the intelligence versus body     
2:01:37     
size So these scalings you'll find these for neoortex When you're looking at mammals     
2:01:43     
especially primates you'll have the volume of the neoortex versus body size So the larger     
2:01:51     
the neoortex is relative to body size the more intelligent the species     
2:01:57     
presumably So you'll see this plot in primates where monkeys are have a a     
2:02:03     
small neoortex volume relative to body size and homminids have a the largest     
2:02:11     
neoortical volume with respect to body size In birds you actually have a     
2:02:17     
similar relationship between the telenphylin which is the volume of telen     
2:02:23     
with body size So you have these smaller birds that have a smaller body size and     
2:02:30     
they have a smaller tel and sephflon and of course you'd expect that as the body     
2:02:35     
size grows the tel and sephiline volume will also grow So different species that are bigger they're going to have     
2:02:42     
corresponding anatomical parts that are also bigger but they should scale one to one     
2:02:48     
And when you have an expanded structure that means that that structure will scale nonlinearly or maybe two or 3 one     
2:02:57     
or whatever And so you see this in a couple of species You see in the brook     
2:03:02     
for example the toen felon volume is much larger than the body size gain So     
2:03:08     
as the body size grows the toe and supplement grows at a a nonlinear positively nonlinear rate     
2:03:18     
You have uh other species like the magpie which have a large cell relative     
2:03:24     
to body size um and the jack doll and     
2:03:29     
some other species as well So you see that there's the scaling that we use to     
2:03:35     
sort of look at the size of this enlarged structure relative to body size and where that structure is nonlinearly     
2:03:42     
positively enlarged relative to body size are the species that we're interested     
2:03:48     
in Okay Um and so just kind of thinking about intelligence from the sort of     
2:03:54     
evolutionary ecologic perspectives Um and this is why we use these kind of     
2:04:00     
scaling uh laws to sort of find uh you know where brains have     
2:04:08     
enlarged Um we can actually look at maybe some of the links between the forbrain size     
2:04:17     
and how that's large relative to body size and how that relates to behavior So     
2:04:23     
consistently there was a significant relationship between high innovation rate and large relative brain size for     
2:04:29     
corvids parrot parrots to a lesser extent non-cored song woodpeckers horn     
2:04:36     
bills owls and falcons these patterns were similar and when frequency tool use     
2:04:42     
was also correlated with the relative brain size So again you have these behaviors these intelligent behaviors     
2:04:48     
accordingly but the brain size the enlargement of the brains or what body size is that's kind of what's driving     
2:04:58     
this and then um birds have also adapted to solving     
2:05:03     
other types of soc ecological problems So for example living in large and     
2:05:08     
individualized societies where group members recognize one another have     
2:05:14     
long-term relationships and track other social relationships Therefore     
2:05:19     
specialized neural systems that process such types of     
2:05:24     
information And then of course concepts of categorization where birds like in     
2:05:31     
mammals especially primates are exceptionally skilled at discriminating between visual     
2:05:36     
images Such images can be categorized based on their perceptual similarities or may even be grouped together based on     
2:05:43     
a humanlike abstract concept such as same different So pigeons for example     
2:05:48     
can discriminate images of aerial photography or aerial photographs     
2:05:54     
pigeons trees in water chairs cars humans and flowers and even arbitrary     
2:05:59     
stimula such as letters of the alpha So they can do this kind of     
2:06:04     
discrimination Um they don't necessarily attach a symbolic meaning to it but they     
2:06:10     
do this sort of they can distinguish between different types of     
2:06:17     
stimul And then of course they can do other things transitive inference role versus wrote learning insight learning     
2:06:24     
and problem solving numerical concepts     
2:06:30     
objects So we have all these different aspects that bird brains can do just as     
2:06:35     
well or a comparable level to the male     
2:06:40     
particularly primate brains So I think that's all for today Thank you for attending See you next time
