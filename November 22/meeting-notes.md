## Meeting Recording

[YouTube link](https://youtu.be/FDJeVwqNr1Y)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115597386685843169)

## Feature Videos

[A Neuro-inspired Computational Framework for AGI (using an ActInf approach)](https://youtu.be/1E6eUnhLh5o)

[A Discussion of the Recent AlphaEvolve Paper](https://youtu.be/LTjshWCEvWY)

## NOTES
Computationally-intelligent symbiosis.

all the rich funders interested in a model of the virtual cell. Cell models, agency, drug response.

deal with multiple objectives, mutation operators based on world knowledge versus hand-coded operators.

math as a training ground, but also a toy problem.


Autocomplete, transformer. Prediction, temporal sequences.

post-transformers — are ActInf models the way forward?


Foresight — Neurotech weekend videos. They are missing the Levin part.

transformer model — with good mechanistic models.

connect to Levin regulatory network machine (GRNs).

analog computing, computation being fundamental to growth, complexity (extend 2-D Pong).


Add to ALife simulations with a slightly more CS approach.

focus on virtual cells — stay DevoWorm relevant. 

bioengineered intelligence.


DevoWorm, November 17.

epithelium CAS models, cell-cell junctions.

“What is Intelligence” book —> collect a lot of different threads.

automatic learning —> performing an action that will have a specific impact.

“Biological Underpinnings of Lifelong Learning” —> Active Inference.

improve upon fragilities of DL, compositionally problems of RL.


Pong example. Goal-oriented behavior in brain tissue.

adaptive tissue response. 


Symbiogenesis — computational life/intelligence.

Levin, single cell model of environment, loop tightens to form anticipation.

2) other like agents, anticipatory system. Cambrian explosion.

Cross-species examples —> oddity in Octopuses — have ToM, but not social. 

Soft Body Control as a mechanism of embodiment.

does soft body control = behavioral affordances.
 

Model Agents —> prepares you for war, prepares you for cooperation.

KL divergence — demonstrate what this looks like (dimensionless form of dynamics of comparison over time).

FTDE — Finite-time Discrete Exponents. KL vs. FTDE.


Reflective Agency — MIT Media Lab. Ground things in philosophy and phenomenology.

useful phenomenology, beyond “here’s the conclusion” of LLM output.

Blaise paper on computational life.


Active Inference of Emergent, Collective Behaviors.

## TRANSCRIPT
0:00   
Hello. Morning.   
0:07   
I'm just finishing up the um uh connection meeting.   
0:13   
Oh, okay. Yeah, it's good.   
0:19   
Yeah, it's great. So, I'll I'll start with an update here on my own.   
0:27   
So uh this week we had the diva worm meeting   
0:32   
and that was uh where we talked about epithelial sheets. Um first of all we talked about   
0:39   
cell junctions. We talked about how you can model junctions and all the   
0:45   
components of that in a sheet. And then we talked about thinking of   
0:52   
epithelial sheets as a complex adaptive system. That is you have these uh forces   
0:59   
that arise from each cell that keep the sheet stable but then you have these   
1:04   
larger scale structures of positional information and tissue   
1:10   
uh integrity. And that's what we talked about in the first paper was how that tissue integrity is maintained and   
1:17   
that's what kind of constrains things from the top down. You have these bottom up forces from each cell. It could be   
1:24   
molecular mechanisms. They could be uh activi you know actions of the cell   
1:29   
itself and then you have things from that higher level of organization   
1:35   
constraining uh function. So that was um nice. You   
1:41   
can go see that on the YouTube channel. And um you know, we still have I guess   
1:47   
some postmortem from the active inference um symposium. Um you know, I don't we didn't do   
1:54   
anything this week with it, but um you know, that's still kind of to digest and   
2:00   
to think about. Yeah. So we had a couple things uh sort   
2:05   
of following up from the active inference symposium and then uh something that was put in the slack. So   
2:13   
this um is the first thing I want to talk about. So this is uh this is active   
2:20   
inference related. This is Alexander Shaw, who I don't think was at the symposium, but does a lot of stuff that   
2:27   
we've talked about with active inference and this computational psychiatry   
2:33   
approach. And and yeah, I I can talk about some   
2:39   
other some other papers that that he's been publishing just like this month.   
2:44   
Oh, yeah. Yeah. That Yeah. relevant to the um what is intelligence   
2:52   
um reading group that we just did this week too. Sorry to keep keep going.   
2:58   
Oh that's fine. Yeah. So this is a neuro inpired computational   
3:04   
framework for AGI predictive coding active inference and   
3:10   
free energy minimization. So this is this is a recent uh preprint.   
3:16   
Uh the abstract this paper proposes that foundational principles from theoretical   
3:22   
neuroscience/predictive coding, the free energy principle and variational inference   
3:30   
offer a biologically grounded framework for artificial general intelligence.   
3:36   
These approaches characterize the brain as a hierarchical inference system. A   
3:41   
continuous updates beliefs and select actions to minimize uncertainty and   
3:46   
surprise. In contrast to conventional AI systems which typically rely on static   
3:52   
architectures and offline training, biological agents engage in active   
3:58   
generative inference within dynamic uncertain environments.   
4:03   
We argue that is the inference-based architecture not just its behavioral outputs that underpins the adaptability,   
4:11   
generalization and resilience of natural intelligence. So it's this uh ability to do inference   
4:19   
rather than just having this standard behavioral output that they they kind of isolate as the   
4:27   
key. We outlined a neuroinspired computational framework built on   
4:32   
hierarchical generative models, scalable variational inference like variational   
4:38   
applause and active inference. Finally, we contrast this approach with dominant   
4:43   
deep learning paradigms and discuss its implications for building interparable   
4:48   
adaptive and autonomous machine intelligence.   
4:54   
So um so they basically go over predictive   
5:00   
coding and the free energy principle. Uh these theories propose that perception, action and learning arise from the   
5:07   
hierarchical minimization of prediction error via approximate basian inference.   
5:13   
In this view, the brain is a generative model. It continuously predicts sensory inputs, updates internal beliefs in   
5:20   
response to mismatches and selects actions that minimize expected future surprise. So we have prediction,   
5:29   
uh response to mismatches and minimizing surprise. Those are like   
5:35   
the three basic components of uh active inference. And so this forms a   
5:42   
predictive loop. This is a feedback loop that supports both epistemic behavior,   
5:48   
reducing uncertainty through exploration and instrumental behavior, pursuing   
5:54   
preferred outcomes uh achieved by internally simulating possible futures and evaluating them   
6:01   
according to expect free energy. The underlying dynamics are governed by a variational principle. This is also   
6:08   
important in u active inference. And when they say variational, they mean   
6:13   
that the brain minimizes a quantity called variational free energy abound on   
6:18   
model evidence providing unified explanation for learning adaptation   
6:24   
action selection under uncertainty. So variational free energy is defined by this term here   
6:32   
which is where qz is the approximate posterior   
6:37   
pz given x is the true posterior and then px uh is the model evidence. So you   
6:44   
have basically the posterior given model evidence and then the approximate   
6:51   
posterior given the true posterior given model evidence and then you subtract uh   
6:57   
log uh model evidence and then you have your KL divergence and that's your   
7:03   
function that you're uh basically minimizing which is your uh variational free energy   
7:12   
minimizing this bound approximates basian inference in a tractable way. So this is the bottom of the document.   
7:20   
Meanwhile, artificial intelligence has made rapid progress in areas such as transformerbased large language models,   
7:26   
diffusion based generative models and reinforcement. So these are all kind of relevant   
7:32   
things. Uh interestingly in the opensource uh the the presentation I   
7:38   
gave on open source sustainability uh I I focused a lot on the uh   
7:43   
reinforcement learning models that we we've been doing and kind of relating that to um active inference and some of   
7:52   
the things and we we've done some active inference in the past but there's some interesting sort of mathematical   
7:59   
relationships in the models that we've been using with uh active inference. And   
8:05   
so that's something I think we should follow up on especially given kind of what we're trying to do in terms of   
8:12   
solve a collective behavioral problem and how to best approach that.   
8:17   
U this also is very interesting in terms of the post transformer uh model landscape that we were talking   
8:24   
about uh for the last two weeks where you know we're thinking about how to   
8:29   
move beyond transformers or how to improve upon transformers as that step in a large language model or some other   
8:37   
way to kind of you know overcome the limitations of those models. So, you   
8:42   
know, this is uh where I think that's what they're maybe kind of posing   
8:48   
for active inference that it's sort of better than a transformerbased uh   
8:53   
approach, but you know, that's that's something I guess that they're going to get into later in the paper.   
9:01   
So, you know, then they kind of point out the limitations of modern models   
9:06   
that are currently used. So that's like transformerbased models also diffusion models forcement learning agents. These   
9:13   
systems often struggle to generalize beyond their training distribution adapt online or robustly handle insert.   
9:21   
And so one of the problems of course is that they typically lack explicit generative models of the environment and   
9:29   
rely on static architectures trained by a supervised or reinforcement learning. So reinforcement learning say for   
9:37   
example is good for learning kind of immediate uh sorts of rewards and   
9:43   
policies but it's not good at like that sort of world model approach where you need to model the world. So you don't   
9:50   
have to have been trained on everything to get the gist of the context. So um   
9:56   
this is kind of a long-standing uh question in cognitive science which   
10:04   
is you know how do we put things into a framework? You know how do you have a   
10:11   
general idea of where things fit into the world despite maybe not having experience with a specific thing? Where   
10:18   
do you fit that into the world? We can do that pretty easily as sort of you know when we're in a   
10:25   
context we have this sort of intuitive sense of you know where something goes and that's   
10:31   
not something you see in machine intelligence. So this is kind of an interesting thing. It's not something   
10:37   
you can get with diffusion models. It's not something you get reinforcement models and not transformer models. Um   
10:46   
so yeah and then we talked actually you know in in our paper on the ever good   
10:52   
regulator theorem we talked about diffusionbased models and sort of how you can maybe use the ever good   
11:00   
regulator as a means to get to a world model based on these kind of problems   
11:05   
where you have like a diffusion based u approach and then you can generalize   
11:12   
from that. So that's something that is maybe, you know, an interesting area.   
11:18   
But what they're arguing here is that you need to have an explicit generative model. And of course, they're going to   
11:24   
put in uh they're going to plug in basically variational free energy as that generative model.   
11:32   
This paper explores the emerging hypothesis that the computational principles underlying brain function,   
11:39   
predictive coding, dynamical systems modeling, and active inference may   
11:44   
provide a biologically ground blueprint or constructing general purpose agents.   
11:49   
We argue that such agents should not merely reproduce intelligent behavior, but embody the same self-organizing   
11:56   
inference-based principles that underly human cognition. To develop this argument, we proceed as   
12:03   
follows. First, we examine the brain as an inference engine showing a hierarchical predictive coding and   
12:09   
active inference give rise to perception, action, and learn. Next, we   
12:15   
contrast this with prevailing AI paradigms, particularly transformer and diffusionbased models, highlighting   
12:22   
their strengths and limitations. We then present the free energy principle and variational lelass which is going to be   
12:29   
a variation on variational free energy as scalable engines for neuro inpired AI   
12:36   
and then they propose a road map for AGI uh based on this on this way of doing things.   
12:43   
So there's this model of general intelligence. Um and this is where you   
12:49   
we view perception, cognition and action as the outcomes of approximate basian   
12:54   
inference embedded in a dynamical system. And so this allows us to have a   
13:00   
model where we uh you know are able to approximate the world, anticipate it and   
13:06   
select actions that reduce uncertainty.   
13:13   
So we want to have this hierarchical generative model. Um so you know there's   
13:20   
this they kind of argue the brain is a hierarchical architecture that can uh you know basically have each   
13:28   
level generate predictions about the activity of the level below.   
13:34   
sensory signals are explained away by these top- down predictions and only residual errors are propagated upward.   
13:43   
So they approach this as a message passing architecture which supports basine inference over   
13:49   
latent variable Z given sensory observations X under a joint generative   
13:54   
model here and this is just this statement here. uh because exact basian   
14:01   
inference is intractable in realistic settings the brain is assumed to represent a variational posterior qz   
14:08   
that approximates the true posterior pz given x so this is where you have this   
14:15   
uh posterior that approximates the true posterior um and that's your variational form   
14:23   
inference then proceeds by minimizing a variational free energy functional which is here this is basic basically what we   
14:30   
were looking at with your um your variational uh free energy and then minimizing free   
14:37   
energy ensures that internal beliefs are both accurate and parsimmonious   
14:43   
which remains close to prior expectations. This provides a trade-off between flexibility and generalization   
14:50   
which is essential for adaptive intelligence. or are you gonna say something, Morgan? Or   
14:55   
um I I really do like uh Shaw's work and   
15:01   
and Yeah, glad glad we're covering it. U   
15:06   
you know, this is this is still very broad strokes though, right? Yeah. Yeah. Well, yeah, we'll get a   
15:12   
little bit into maybe like how they're applying it uh more generally, but it's   
15:17   
very much a I think a position piece. They're not really uh saying this is an   
15:22   
example of it in a robot or something. It's just kind of like this is an alternative to   
15:29   
I mean he's he's he's definitely um in the active inference camp.   
15:34   
Oh yeah. Yeah. Definitely. It's standard active in like active inference has has something   
15:41   
to contribute to AGI. Yeah. Yeah. Uh and and you know I I like I like his   
15:49   
work too. I mean um he he publishes or you know I shouldn't say   
15:56   
publishes he posts a lot of just tutorial links and like like uh uh   
16:04   
computational examples. Yeah. Yeah. So like like Yeah. And   
16:12   
Yeah. Uh so okay this is an example of predictive coding and visual perception.   
16:18   
So predictive coding is sort of um you know related to active inference in that   
16:25   
we're uh we have this feedback loop and we have we're sort of estimating   
16:31   
uh you know things and minimizing error. So this is an example of predictive   
16:38   
coding. Consider a simple visual scene in which a person views a cup on a table. Higher level visual areas or   
16:45   
inferno temporal cortex which is the anatomical uh localization generate abstract   
16:52   
predictions such as object with a handle or familiar graspable shape. These   
16:57   
predictions are sent down the hierarchy shaping expectations for the patterns of activity in lower level areas. So these   
17:05   
would be like orientation edges in V1. So you have this network where there's   
17:11   
processing in the visual system. The early parts of the visual system are   
17:17   
represented by V1 and then later parts of the visual system are represented by inferotal cortex. So V1 is lower in this   
17:25   
case and inferotal is higher and so they have this relationship where one is kind   
17:31   
of sending information forward and then the other is kind of giving this information back as feedback.   
17:38   
uh it in in the if the incoming sensory input matches these expectations   
17:44   
prediction error remains low. So if the parts different processing in different   
17:49   
parts of the visual stream or visual network are basically similar or no   
17:56   
surprises like when you refine some of the shapes uh that there's this thing   
18:02   
that pops out uh then prediction error remains low. However, if the object is   
18:07   
partially oluded or appears unusual, say if it's a broken cup or an unexpected   
18:13   
angle prediction. So, it's like if you you know if the visual system gets sort   
18:19   
of the gist of what it is, but then it has some exception to it that uh is a   
18:25   
problem because it might not be a cup if it's a broken cup or it could be a cup. you know, the the visual system has to   
18:32   
sort of um you know, and then there are other parts of the brain that that participate in this. Maybe that's a   
18:37   
critical aspect of this um you know, different types of other information   
18:42   
that you can use. But in general, you know, as you resolve the uh the image,   
18:49   
the main, you know, the the overall image, you get these exceptions that then can need to be resolved basically.   
18:58   
So this is where we get this these errors that arise maybe in early visual   
19:03   
areas and are sent upward. These errors are crucial. They signal a   
19:09   
mismatch and prompt higher level areas to update their beliefs until the model settles on the most likely explanation   
19:15   
which is damaged cup. So you have s you know lower level   
19:20   
systems that identify the shape of a cup and then it's most likely a cup and then   
19:27   
you get these exceptions that give it you know provide different like subsets   
19:34   
of information. So you have these refined categories like damaged cup and that's most likely.   
19:42   
So it doesn't it isn't necessarily always going to be damaged cup. It might look like a damaged cook, but it might   
19:47   
actually be something else. Which is maybe one of the problems here is it's just this approach is just simply   
19:54   
assuming that the visual system is making this classification on its own   
20:00   
which you know this is something of course that may require other information.   
20:06   
Um you know that's that's sort of you know they talk about a priority and they talk about posterior predictions and   
20:13   
things like that. U but that that of course requires you know some sort of   
20:19   
categorization and so that's going to involve higher levels of the brain uh maybe early on if   
20:28   
we're doing this sort of uh category assessment even some in something like   
20:33   
B1 in this way perception operates not as passive registration but as the brain's   
20:40   
best guess about the hidden cause of ambiguous noisy input allowing for rapid adaptation to new or   
20:46   
unexpected situations. So this is, you know, kind of reminiscent of the ambiguous figures   
20:52   
paradigm, right? So in ambiguous figures, you know, you have some uh sort of   
21:00   
abstract shape or some uh shape that you can't identify right away. And you know,   
21:06   
if you look at it in certain ways, it looks like maybe a duck or a pair of rabbit ears. and you kind of your visual   
21:13   
system has to resolve it. That's you know kind of just the orientation of things and how that gets interpreted and   
21:20   
all that. So they're arguing that you know you have you start off with these very ambiguous shapes or these ambiguous   
21:26   
objects and they get resolved as the visual system gains more information but   
21:32   
critically the visual system has to make predictions about what that thing is and then it goes down this path of   
21:39   
minimizing that error. So it could be the wrong thing. It could be the wrong category. But as long as the error is   
21:45   
minimized, it's going in that direction and it resolves it. So the the idea   
21:50   
isn't that it necessarily gets things correct. The idea is it's minimizing   
21:56   
error which is sort of this free energy model minimizing energy. And then you   
22:03   
know you have um you know I don't know I guess it's supposed to be right. Always correct. I   
22:10   
don't know what the error rates would be, but just keep that in mind. Um, you know, so   
22:16   
so the idea is that this is sort of the the way that this works. And of course,   
22:21   
this is how visual the visual system processes information, right? It starts with very simple patterns like stripes   
22:28   
and blobs and then it works its way up to details and kind of attaching semantic labels to them, which is, you   
22:36   
know, not talked about here so much. It's just kind of minimizing things. Then they talk about act active   
22:42   
inference. Notably, predictive coding is not restricted to perception. In the   
22:47   
framework of active inference, action selection is cast as an inferential process driven by the same imperative   
22:53   
that governs perception, which is the minimization of expected free energy. In this view, agents do not   
23:00   
passively infer the causes of their observations. They actively select policies that make future observations   
23:07   
more predictable and less surprising. So again the surprise is   
23:12   
you know if you think about this in terms of uh regularization or   
23:17   
normalization things should become more sort of towards the mean over time more   
23:23   
predictable. you should have less surprise. And you know this is again where if you   
23:29   
think about this in terms of a world model things should always kind of fit into this world model. And you know   
23:36   
acquiring that sort of predictability is the job of like a basian uh statement   
23:43   
where we're using conditional probabilities using a prior distribution. We're then taking the   
23:48   
current observations, we're fitting it into a prior and we're sort of normalizing.   
23:54   
So nothing ultimately nothing should be surprising although that kind of you know the the basian approach kind of   
24:02   
assumes that we have perfect information right we we have to have a prior that   
24:10   
incorporates everything in the world. You can't have a prior that incorporates   
24:16   
sort of, you know, a sort of a a very tight distribution   
24:22   
around the mean and then have a bunch of out of distribution observations because   
24:27   
those out of distribution observations won't be able to fit into that model necessarily.   
24:34   
So the expected free energy which is uh gpi under a policy pi can be decomposed   
24:41   
into epistemic and instrumental components capturing both uncertainty reduction which is exploration and goal   
24:48   
directed behavior which is exploitation. So they're putting this in a sort of a reinforcement learning cast as   
24:55   
you might guess. Um, one common formulation expresses this as in this   
25:01   
term, which is we've seen this term before, but now we're adding in this   
25:07   
expected free energy. Um, and so this form reflects the expected divergence.   
25:14   
So this is like the we saw with the uh KL divergence or or the uh the log   
25:21   
probabilities expressed or log likelihoods expressed as KL divergence. But now Now we're talking about free   
25:27   
energy. Um, this is the expected divergence between posterior and   
25:32   
likelihood minimizing. It encourages the agent to seek actions that simultaneously reduce uncertainty about   
25:39   
hidden states and achieve preferred outcomes. In effect, perception and action are unified under a single   
25:46   
inferential scheme. brain continually continually infers not only what is   
25:51   
happening but what it should do to bring about the desired predictable state of affairs. So this is important because   
25:57   
really what the what the point of this is isn't to just classify things passively but to uh provide an impetus   
26:06   
for actions that will rectify the situation. So, you know, if you see an   
26:12   
ambiguous figure, if you're familiar with the paradigm, you know, if I if I   
26:18   
see like two things, you know, if there are two options in my ambiguous   
26:24   
perception, if I'm supposed to either see like a rabbit or a duck, and I'm   
26:30   
talking to my person next to me and I say, I think I see a rabbit, they say, I   
26:36   
think I see a duck. And you're like, okay, well, let me look and see if it's a duck. until you refocus your eyes. Now   
26:41   
you see a duck because you know you you're expecting that based on the   
26:46   
communication with your neighbor. So you're doing active things in the world   
26:54   
to sort of make a certain outcome happen. You're using this information that you're getting from this model and   
27:00   
you're actually acting upon it and maybe normalizing your behavior. Maybe you're   
27:06   
just kind of uh it's helping you sort of get to the the thing that you're supposed to do or get to things that   
27:13   
make sense or whatever. But there's an active component here that is not   
27:20   
something you see in in your transformer models or in your diffusion models or   
27:25   
any of that. So their approach to a world model is almost sort of like we   
27:30   
have to uh have this action component to it. And I know we talked about how   
27:36   
people are wanting to do action models and and collecting data on action   
27:41   
models, but there is this school of thought of course where you just have to have behavior do things like it's not a   
27:49   
data set that you need. It's experience in the world. The agent has to have experience. it has to just kind of roam   
27:56   
around the world and and collect enough sort of experience to do something. I   
28:02   
actually hit upon this in the uh spatial intelligence talk uh if you watch   
28:08   
towards the end where you know part of spatial cognition isn't really building   
28:13   
a model of the world that's perfect. It's about exploring enough of the world   
28:18   
so that makes conditions or godic or that you can sort of have a a   
28:24   
representation of every possible thing in the world or as many possible things   
28:29   
as you can in the world so that they just become part of this this uh   
28:34   
experience and then this world model that that is you know it's it's sort of after the after the experience. So it's   
28:42   
and and it's maybe you say well you could just collect that but it's actually more than that because the   
28:47   
agent actually has to have experience being in that space or being you know in   
28:53   
that situation. So you know it's worth thinking about and then this is not a new idea of   
28:58   
course people have you know talked about experience and of course in embodiment we talk about experience and all this   
29:06   
where you have to you know it's not just about data you know data points it's   
29:11   
about having that connection between using your body to do something and then   
29:16   
having that information and sort of almost like a unique set of data points   
29:21   
that you can then use to uh gain that knowledge. European model. So again they   
29:28   
c cast this against reinforcement learning. So unlike traditional reinforcement learning which relies on   
29:34   
externally defined reward signals, the policy optimization, active inference derives behavior from an internal   
29:41   
generative model and an imperative to minimize variational free energy. So   
29:46   
goals and preferences. So goals and preferences are encoded as   
29:51   
prior beliefs about preferred states and behavior emerges from the drive to release these states while realizing   
29:59   
these states while reducing uncertainty. This makes active inference naturally   
30:05   
suited to continual adaptive control. So this is continual learning and the sort of thing in uncertain environments   
30:11   
offering a biologically broader alternative to model free or value based methods. So this is where they decompose   
30:19   
expected free energy. So the expected free energy gi which captures both   
30:24   
uncertainty reduction which is the epistemic value and goal fulfillment which is the instrumental value and then   
30:31   
the decomposition of this equation is where you have gpi which equals two parts. the epistemic value which is here   
30:39   
which has these conditional uh likelihoods under kale divergence and looking at   
30:45   
that and then that's additive with instrumental value which is this log   
30:50   
probability and uh this this conditional Q so this is basically where you have a   
30:59   
preference you want to reduce your uncertainty so you want to make sure that your beliefs align with what's   
31:05   
going on in the environment And then those are the things you're acting on.   
31:10   
So it's almost like in reinforcement learning, we have a policy and we try to find our uh preferred policy. So, you   
31:17   
know, that's kind of like uh I wouldn't say mushing these together, but like   
31:23   
it's basically like leaning on the idea of instrumental value and then just   
31:28   
optimizing that instead of having this component of epistemic value where you   
31:34   
have this uncertainty and you're just reducing that. So it's like you know with epistemic uh value you know if I   
31:41   
believe something or if I have a set of beliefs those are epistemic things like if I believe things about the world if I   
31:48   
believe that if I go far enough along the surface of the earth I fall off the edge instead of coming around on my   
31:55   
original point because we're on a sphere instead of on a flat surface. And so I have to go out and test that. and I have   
32:01   
to go travel and I you know I can believe either either thing but my   
32:06   
uncertainty is not um eliminated until I actually experience that thing. I have   
32:12   
to go out and test it. I have to go out and and experience that travel and then I know for sure and that reduces my   
32:19   
uncertainty about things. And you know you can do that with agents. You know, if the agent sees the edge of a grid,   
32:25   
does the agent know that there's the grid is tooidal or that the that's the edge of the grid and they need to not go   
32:32   
uh to the edge because they might get trapped. You know, this is just thinking about a grid where you have a two   
32:37   
dimensional grid where you have agents exploring. Uh let's see, we had a question from   
32:44   
Jesse here. Um, yeah. So, I'm thinking about how this relates to comments like   
32:49   
affordance and computation to what I just said about needing a body to get the data in the world uh in in in   
32:58   
interactions, not just abstract about data points. Yeah, I think that's a good   
33:03   
point. You know, that that is a different fundamentally different thing. I guess that's the whole argument of   
33:09   
embodiment, right? is that the that experience in the body you know uh I   
33:15   
think it was like Adam Saffron and colleagues who said it's like this uh there's this filtering mechanism that   
33:22   
happens with things you know with using your body if you have like a something   
33:27   
like proprioception or interosception there's this filtering that happens you   
33:32   
only get from having that sensory experience so you have a bunch of sensors are collecting data but that   
33:39   
information is being put together in a way that is not just kind of like data   
33:44   
points that you you can explore or or feed forward. Uh then that's that's a   
33:49   
good point. Then the second comment there's a very interesting discussion happening with Ilan at Echolapto at FAU   
33:57   
where he's trying to sort sort of get at a large language model as a means of showing language how language is sort of   
34:04   
its own thing relative to the mind body problem. Mind language problem. Yeah. So   
34:10   
I mean that's Yeah. And then of course you know there is this role of language in like motor learning and in embodiment   
34:17   
that that we haven't really talked a lot about but Jesse would like to speak. So go ahead Jesse.   
34:24   
Hey. Um can you hear me? Yes. Okay.   
34:30   
Um yeah I'm trying to think of a way to really get at what I wanted to say. I   
34:35   
appreciate what you're doing. the LM thing I mentioned not because I'm   
34:41   
such a a proponent of the view but more like I think it's a nice view in terms   
34:47   
of identifying I don't know if I believe it but I I see   
34:55   
what Elon speaking up with his work there sort of this   
35:00   
there's a structure of the language that is is potentially disembodied   
35:06   
and like an internal logic to it which is I'm not trying to   
35:12   
say separate but like is its own thing like that's that's fine and it's like   
35:17   
but again I missed a little bit of things I like to think but but   
35:23   
I'm seeing that as like a justosition to the things that you require   
35:29   
um I I don't really like the words   
35:35   
computation here but that which requires you to through your   
35:43   
physical embodiment get indication. It's it's like it's like having markers or   
35:48   
like like kind of like printed bills that you're tracking the the thing   
35:53   
through it by going through the medium interaction. You get you get a specific   
36:00   
kind of information and maybe a specific kind of uncertainty reduction. And the   
36:06   
last point I wanted to make was like what was very interesting and just now and all this is like we've   
36:12   
talked we've talked before about like riding a bicycle and readying a hand and how like your mind you know you can   
36:18   
transfer your sense of self to like okay I'm now riding a bicycle I'm listening but if you think about that um I will   
36:25   
sort of be in it and then okay as soon as I okay now I'm not no I'm not bicycle anymore I have to prepare it stop it get   
36:32   
out take repair the tire whatever that kind of discuss which I'm very very roughly referencing here in our previous   
36:38   
phenomenological talk right and it's sort of like I think and I don't I   
36:44   
assume this maybe is a core of phenomenological um discourse in general but then I was   
36:50   
like okay well everything is a version everything you experience   
36:57   
is sort of this version of riding the bicycle it's always the body itself is like the first   
37:04   
bicycle But it doesn't mean you stop it or whatever or that's less important. But it's like it's like understanding that   
37:13   
writing through a pen on a paper will have a specific   
37:18   
impact or or like the mean is more than just the medium. It's the way that the   
37:24   
information or the decision structures put through the interface of mediums or   
37:30   
mediums pearl and it's like there's a signature by nature of it. I don't think I'm doing a great job getting what I'm   
37:36   
at but I'm curious you any thoughts or comments on that. Yeah, this last thing you mentioned that   
37:44   
you perform an action, you have an impact and we just talked about feedback actually in that respect. That's why you   
37:50   
have this part of the model where you do something in the world and you see what   
37:56   
it does and then you do something else. You have this action part of uh like   
38:01   
entropy minimization or surprisal minimization which is where to minimize   
38:07   
your uncertainty you have to do things like you have to do experiments or you have   
38:13   
to explore the world or something. So that's the action part and you know a   
38:18   
lot of like yeah a lot of uh like procedural learning is about   
38:24   
experience. If I want to ride a bike I can describe you how to ride a bike but really to ride a bike I need to ride the   
38:31   
bike and then I can do it automatically after that because I encode that those motions and things like that and it's   
38:38   
not something I can verbally tell you how to do and then you just do it once   
38:43   
and you're done. have to have the experience. And so that's, you know, kind of where   
38:48   
this is. Um so let's let's move on. Let's see. So this is um kind of this   
38:54   
decomposition of free expected free energy. Um and so the interpretation of   
39:01   
this equation, the the G pi function is that the first term, which is the   
39:06   
epistemic value, encourages the agent to take actions that will be informative.   
39:13   
actions that reduce uncertainty about hidden states. So we have hidden states, we have observed states. We don't know   
39:20   
all of our hidden states. And that's why we have to reduce our uncertainty. We have to resolve not just the the   
39:26   
observed states, but the hidden states as well. So, you know, there may be states that we're kind of we don't   
39:32   
really understand what they are, but we know that they're kind of these things in our model that exist, but you know,   
39:39   
we don't know exactly how to interpret. So uh and then the second term pushes   
39:44   
the agent towards outcomes that are consistent with prior preferences desired or rewarding outcomes   
39:51   
and then so together these components drive exploration and exploitation without requiring explicit reward   
39:58   
signal. So this is again where you know we in well BD knows this quite well that   
40:03   
in reinforcement learning we have these exploration and exploitation models. We   
40:09   
also have them in other areas. Um you know we have these ar uh unarmed bandits   
40:14   
actually came up in the active inference uh symposium that people were using   
40:21   
you know unarmed bandits to model exploration and exploitation. In this case we're using this to not require an   
40:29   
explicit reward signal in the model. So that's how they're doing this. So a lot   
40:36   
of connections with uh reinforcement learning. The this the argument here is   
40:43   
that improves upon reinforcement learning by having this action state.   
40:49   
And so then they talk about cognition is dynamical inference and state space. And   
40:54   
so thinking about this as a a dynamical system.   
41:01   
And so then they talk about you know different neural dynamics. So you have these recurrent neural dynamics   
41:07   
and this is kind of how the brain is dealing with these the production of   
41:12   
this these kinds of predictions and the production of integrating evidence and all that.   
41:19   
U so they say such recurrent neural dynamics whether whether oscillatory   
41:25   
chaotic or metastable be formalized as solutions of differential equations that   
41:30   
govern the temporal evolution of beliefs. So these are like where we're describing our beliefs about the world   
41:36   
as these in these form these differential equations that are going to become these dynamical trajectories and   
41:43   
then we want to understand how those evolve. So if we think about this in   
41:48   
continuous time, we get this differential equation here or we have this gradient term and then we're   
41:55   
subtracting that from this function mu and then you know so we have like this   
42:01   
first term here um and this is a triplet function   
42:06   
describes how beliefs will evolve over time based on prior expectations of natural dynamics. So I guess this is the   
42:15   
um uh the mean the mean behavior the sum   
42:21   
behavior and then x which is your uh sort of your obs current observation   
42:28   
and then this is over this gradient uh which is this f which I believe fits   
42:34   
into let's see it anyways that's and so the first term this function part this   
42:41   
first part of this equation describes how beliefs would evolve over time based on prior expectations or   
42:48   
natural dynamics or how the brain expects things to change even without new sensory input. So say you like know   
42:56   
things and then you stop observing the world, you put on a blindfold, you put   
43:01   
your fingers in your ears and then you know you kind of just think about the world or you go learn anything new. So   
43:09   
this is where you maybe come up with a new solution but but not based on   
43:14   
experience just based on this kind of processing of what's there. Um the   
43:20   
second term acts as a corrective force. This is this term here adjusting beliefs   
43:26   
to reduce prediction errors and improve the fit between the brain's model and the actual sensory input. So there's   
43:32   
this gradient term where you have this correction. It's basically minim going   
43:37   
down. and it's minimizing along this gradient and it's saying, "Okay, your beliefs need to be adjusted to get rid   
43:44   
of these prediction errors because there's some things that don't make sense. So maybe we need to take our fingers out of our ears, take off our   
43:51   
blindfold, and go explore the world." And that exploration will get us down the gradient to the minimal point to the   
43:57   
minimization point. So this is just thinking about these neural dynamics in a similar way, right?   
44:05   
So we have this basic paradigm of how we have like you know we're predicting from   
44:11   
priors or producing a posterior that posterior then is being minimized with   
44:16   
respect to maybe experience or action. And so this is again you know um   
44:24   
so this is this is great. We're formalizing this mathematically and then we're putting this in terms of like a   
44:31   
neural me set of neural mechanisms and then we're looking at the dynamical systems output. So we can see that this   
44:37   
is very easy to implement in like an agent where you have to produce a   
44:42   
behavior of some type or coherent behavior. So that's what we have here.   
44:48   
So the implication is profound. General intelligence and biological agents do not arise from learning specific input   
44:55   
output mappings or storing specific task solutions. Instead, it emerges from a capacity for   
45:02   
continual structured inference dynamically estimating latent causes,   
45:07   
updating beliefs over time, and selecting actions to minimize future uncertainty.   
45:13   
So from this perspective, we're not looking for a fixed algorithm, but a dynamical system for approximate   
45:19   
inference in deep uncertain non-stationary environments. So basically those environments where uh   
45:25   
some people say you need a world model for in the case of our transformer, a transformer would have problems with   
45:32   
what we call out of dis out of distribution data. Um but this is of   
45:37   
course maybe a solution to this because we don't need to worry about um thinking   
45:42   
about those things as outliers or as as as hard problems. It's just a problem of   
45:49   
experience. We put an agent in the room. Let it explore and kind of construct its   
45:55   
own minim minimize solutions to things and then find the uh optimal solution to   
46:03   
it. So that's kind of what we're getting at here. So crucially, predictive coding and active inference provide more than a   
46:11   
descriptive theory of neural computation. They offer a mechanistic template for constructing artificial   
46:16   
systems that can reason, plan, and adapt in the same situated embodied manner as   
46:22   
human agents. So this is kind of where they get into the limits of deep   
46:27   
learning and predictive coding. So um this is actually maybe relevant to our   
46:33   
idea about post uh transformer architectures   
46:38   
uh thinking about how you know we've had a lot of success with like   
46:44   
large language models and convolutional neural networks. Um but deep learning of   
46:49   
course is constrained in several respects. um and they cite these here. They   
46:55   
generalize poorly beyond their training distribution. They struggle to represent uncertainty   
47:01   
in a principled way and they lack the capacity for continual online adaptation.   
47:07   
They're also reactive rather than proactive. They don't infer hidden causes, construct internal models in the   
47:14   
environment, or select actions based on long-term expectations. So this is where they kind of talk about   
47:21   
this uh the core operating principles of these types of models and contrast them   
47:27   
with the kind of model they're proposing here. So one of their points is that whereas   
47:33   
conventional deep learning systems rely on static feed forward mappings   
47:38   
optimized via back propagation, predictive coding systems perform ongoing hierarchical inference over   
47:45   
latent causes with uncertainty estimation and a action selection embedded in the same inferential loop.   
47:54   
not just minimizing uncertainty but we're selecting from actions and we're doing all that in one shot.   
48:02   
So um there there have been some developments such as recurrent architectures   
48:08   
uncertainty aware models and online fine-tuning that have begun to chip away at this deficit of sort of the   
48:16   
traditional deep learning approach and its drawbacks. Nevertheless, predictive   
48:22   
coding and active inference provide a unified biologically grounded framework in which inference, learning, and   
48:28   
behavior emerge from a single underlying principle which is the minimization of variational free energy. And so that's   
48:36   
kind of what their uh their argument is. Um actually this is a nice table. Uh   
48:45   
this is contrasting deep learning systems with predictive coding and active inference architectures.   
48:51   
So this is kind of getting at the different aspects of these systems and then kind of how they do this   
48:57   
differently. So uh the first aspect is core principle in deep learning   
49:03   
approaches you have pattern recognition from data. In predictive coding active   
49:09   
inference we have inferences of relent causes. So that's a difference in terms   
49:14   
of how data is dealt with. um which is important and this doesn't necessarily   
49:20   
mean you need experience. What this is arguing is that you have these latent sort of causes you have these things   
49:26   
that are possible but we have to go out and explore and see if those things are actually we cause or not. So I could say   
49:34   
another if I see the sunrise in the in the east in the morning, I could have a   
49:40   
number of hypotheses for why that happens, but I can't know for sure until I test all in the in the deep learning   
49:47   
paradigm. I would only be able to verify things based on observed data. So I'd   
49:54   
have to go out and have data about the curvature of the Earth and then, you know, like how the Earth turns on its   
50:01   
axis and all that. If I don't have that, then you know um those sorts of things aren't plausible. Whereas if I   
50:08   
experience it, I can go out and do natural experiments and I can experience my world and and kind of come to a   
50:14   
conclusion about that. And then of course that's you know transferable. It's not just something   
50:20   
that is you know you have enough training data and you can triangulate that one thing and then that doesn't   
50:26   
generalize to anything else. Okay. Okay, then there's the architecture which of course in deep   
50:31   
learning is where we have feed forward static layers and in predictive coding we have hierarchical recurrent and   
50:38   
dynamic architectures. So we have a wider range of architectures uh learning mechanisms. In deep learning   
50:46   
we have gradient descent on loss functions. We use things like cross entropy to look at the the measure that   
50:52   
and then in predictive coding we have minimization of variational free energy. So we still have a gradient but the   
50:59   
gradient is you know not um   
51:04   
it's basically like uh minimizing the available options until we get to like   
51:10   
the only thing left. Whereas in uh deep learning, we're basically minimizing the   
51:17   
uh training error and you know we don't necessarily know if our you know what   
51:26   
our training data represents. So we just all we know is that there's this um loss   
51:33   
and we're trying to minimize it. Uh uncertainty handling deep learning it's   
51:38   
often implicit or approximate. So we use something like dropout uh in predictive   
51:44   
coding we use explicit it's explicit via precision weighted errors and variational posterior. So it's just   
51:50   
fancier fancier approach to uncertainty handling and of course this is again   
51:56   
part of this uh conditional probability right we have a a prior the prior will   
52:03   
represent you know kind of like the same thing as um sort of a training data set   
52:10   
in in deep learning but then we refine that through observations   
52:16   
and then we have these posteriors which you know represent maybe represent   
52:21   
beliefs about the world and then we we kind of refine all of that over time in   
52:27   
a way that's not like optimis optimizing it's just kind of through experience   
52:33   
adaptivity in the case of deep learning we have retraining or fine-tuning that's required in uh active inference we have   
52:41   
online inference over fixed model structure adaptation without retrain   
52:47   
action selection ction in deep learning models is typically via separate reinforcement learning modules. So kind   
52:53   
of another model has to deal with that and then action selection is often done   
52:58   
the reinforcement learning in active inference. Action selection is usually   
53:03   
unified with perception by expected free energy. The expected free energy term is   
53:09   
the thing that does action selection and it's integrated with that model in the sense that it's all taken into account   
53:15   
kind of as part of that experience world models. Uh in deep learning we   
53:22   
have discriminative input to output mappings. In   
53:28   
uh active inference we have generative world models which simulates the causes and consequences.   
53:35   
Um I and I don't know I don't know if that's necessarily true for deep learning where you have just simply the   
53:42   
input to output mappings. I don't know if it would be the world model. You know maybe it's kind of like the well I guess   
53:49   
it would be the world model but I think when people talk about world models in machine learning they're kind of talking   
53:56   
about this thing here this ladder thing and then this is kind of the thing that   
54:01   
results. So you know you have like your training data and the uh then the network   
54:08   
represents something which is this input to output mapping. So it's like okay   
54:14   
this is the space you know if you have these inputs you get these outputs and then there's this thing on top that   
54:20   
people want to build called the world model which is kind of generative. So like the things that we were doing in   
54:25   
our special issue um that's what they were getting at is that you know if you look at the Han Schmidt Huber paper on   
54:32   
world models they talk about how they have a race car that they they teach to   
54:37   
kind of understand its universe of of scenes in in the simulation and that's   
54:44   
their world model. It's generative but it also you know is kind of like also   
54:49   
mapping things to an outcome. So it's it's it's a kind of a little bit different way of thinking. But anyways,   
54:57   
they make this distinction because in active inference, you're actually   
55:03   
actively doing like exploration. You're simulating what the consequences of something are and you're able to give a   
55:09   
bound on that. Uh generalization in deep learning, it's often bit brittle   
55:17   
under distribution or yeah, often brittle under distribution shift. So you   
55:22   
know you can only generalize what you have a prior distribution for in deep work. So if you have data and   
55:30   
the data kind of uh match uh some other task   
55:36   
um then you have you can make a generalization. If it doesn't, if there has to be some inference made, it's   
55:42   
often pretty brittle, but it doesn't make that generalization very um and then in in active inference,   
55:49   
generalization is potentially more robust by a structured inference and uncertainty model. So this is where we   
55:56   
have this uh the claim is that generalization is improved with this uh   
56:02   
sort of integrated model with experience with exploration given a prior distribution of beliefs that sort of   
56:10   
thing. Um I don't know if I buy it. I mean I'd have to see some sort of test.   
56:15   
Um but yeah and then biologic plausibility. Uh in deep learning it's loosely   
56:21   
inspired. So if you use a convolutional hierarchy that's supposedly biologically   
56:26   
plausible but in active inference uh we explicitly map things to cortical   
56:32   
microcircuits and neurom modulation. Okay so that and so I don't really want   
56:40   
to spend too much more time on this. Um let's see if I can get down to   
56:46   
maybe some of the latter parts here. So they just basically talk about some of the variational models and they kind of   
56:52   
get into dynamic causal modeling here uh which is something that they draw from   
56:58   
for their variational LLAS. They talk about learning and adaptation   
57:04   
under the free energy principle. They talk about uh active inference and 2D   
57:09   
pong which actually is a good I think test case because it shows exactly how   
57:16   
you can uh take active inference agents and put them into the world. Although that's a pretty basic example. So they   
57:24   
implemented a minimal active inference agent to control a paddle in a 2D pong   
57:29   
environment. This is where you have a paddle that moves up and down and you have to bounce the ball off the paddle   
57:35   
and you know that's kind of a task. And so this is again something that reinforcement learning can do quite   
57:41   
well. uh especially with something like Dishbrain where you have uh your dish   
57:47   
brain which is a cell culture and then it's using um these feedback signals to   
57:54   
predict where the ball is in the paddle. And so they're using an active inference   
58:00   
agent for this. Here at each time step, the agent receives visual observation of   
58:05   
the current ball and paddle positions and uses variational loss to infer the most likely hidden states of the   
58:11   
environment. So those hidden states are things like the ball's velocity um at   
58:17   
any given time or you know uh maybe how the ball will uh refract off of the uh   
58:25   
the your opponent's paddle and make that prediction. So this is a generative   
58:31   
model that was handsp specified and includes simplified physical dynamics that govern how the ball and pedal   
58:38   
evolve over time. So you need a basically you need to have a set of observation of physical dynamics. You   
58:45   
need to have prior dist a prior distribution of physical dynamics. In physics that's easy but of course you   
58:52   
have to have that and you have to have information about all possible um you   
58:59   
know hidden states. So if the ball bounces in a weird way it has to be you know you have to be able to predict that   
59:05   
interaction from and and you can do this if you have enough prior you know data   
59:11   
in your prior distribution or if you have that experience but if you don't have that experience you simply can't do   
59:16   
it. And this is again you know kind of contrasting this with training data sets. So I mean you know if you're   
59:23   
talking about prior distributions and experience you know how does that improve over a training set? Well I mean   
59:30   
it I guess it does if you have a really good prior and really good experience   
59:36   
but if you don't then it's it's a little bit of a problem. So this just kind of goes through uh   
59:43   
comparing this with reinforcement learning approaches which typically learn policies from external reward   
59:49   
signals via trial and error. And so that's where you know you're just like you have an agent that's learning things   
59:55   
through trying different things. If it's getting an error, try something else.   
1:00:01   
This agent uses a modelbased inference driven strategy. It behavior emerges from the minimization of variational   
1:00:07   
expected free energy enabling online adaptation of uncertainty aware decision making of that task specific supervision   
1:00:15   
over. So this is the perception action loop in this uh table two. There's an   
1:00:22   
observation model which is this equation here. It's additive um state inference which is allows you   
1:00:30   
to this is variational lelass which allows you to in for different states of   
1:00:35   
of being this uh then there's action selection which has this minimization   
1:00:41   
function and then your state transition model which is how do you move from   
1:00:46   
state to state and that's what you need for that. Okay, so that's kind of com   
1:00:52   
contrasting that with uh reinforcement learning. You know, I kind of glossed over the difference between   
1:00:58   
reinforcement learning, doing trial and error and the sort of the I wouldn't say it's trial and error of the active   
1:01:04   
inference model, but we talked about the mathematical things already. So you get a sense of how that differs and then of   
1:01:12   
course we're going towards narrow inpired AGI architectures uh where you know we have these uh key   
1:01:19   
design principles we have generative models which maintain internal probabilistic models that generate   
1:01:26   
sensory inputs uh from latent states. So we have this joint function px zed z x   
1:01:33   
is latent states zed is supporting or x are the sensory inputs zed is the latent   
1:01:40   
states and these support simulation counterfactactional reasoning and belief up. Then we have this hierarchical   
1:01:47   
structure. So we have our internal representation which is layered where   
1:01:52   
the high level beliefs generate top down predictions and lowle sensory data propagate bottom up prediction   
1:02:00   
like a complex adaptive system. Um online variational inference which is   
1:02:06   
where we use real time algorithms such as variational lelass to continually update beliefs in UT about hidden causes   
1:02:15   
in response to new sensory data. uh precision waiting. Then we have this   
1:02:21   
active inference loop which select actions a minimize expected free energy   
1:02:27   
or G pi unifying exploration which is the epistemic value and the goal pursuit   
1:02:33   
which is the instrumental value in a principled way which I don't know   
1:02:38   
if that's really true but yeah however planning via expected free energy minimization remains computationally   
1:02:45   
demanding and then this is the problem where we find out that yeah, this is   
1:02:50   
really hard to do in a in a in an agent's computational   
1:02:56   
abilities. I mean, you don't want to have something that really takes a long time to run um in a in a real-time   
1:03:03   
setting. Then there's continual learning and plasticity where we adapt the parameters   
1:03:09   
theta of the generative model over time to minimize long-term free energy. Unlike leaf updating, this form of   
1:03:16   
structural learning is not trivial. It remains an active research front.   
1:03:21   
So they give an example their pawn game. Here you have an observation at time t of the ball. You have your variational   
1:03:28   
applause to infer a hidden state. You select an action based on the current belief. You roll out a predicted next   
1:03:36   
state under action at then you move the pedal accordingly in the middle. And   
1:03:41   
that's your sort of your procedure.   
1:03:49   
Okay. So that's that's that any well I know Morgan has some comments   
1:03:54   
here. Well, it's it's you know, it's a   
1:04:03   
it's a great summary of the active inference approach to the problems laid   
1:04:09   
out in the biological underpinnings of lifelong learning systems   
1:04:17   
paper. Um, you know, it's uh   
1:04:27   
It's it's covering the same you know it's covering the same   
1:04:34   
fragilityities brittleleness of of   
1:04:39   
you know conventional deep learning approaches. Yeah. Um and uh   
1:04:48   
trying trying you know as as you see in that kind of table of deep learning   
1:04:53   
versus active inference like this this is a   
1:05:01   
um to some degree this is a bio first approach.   
1:05:06   
Yeah. you know, like like like trying trying to be a biologically   
1:05:14   
realistic agent and and so, you know, u   
1:05:24   
it's it's kind of covered several times, you know, where   
1:05:29   
this is um this doesn't need to be adapted to   
1:05:37   
continual learning or or you know   
1:05:44   
you don't reinforcement modules don't need to be added for for action selection and things like that. Right.   
1:05:51   
Because it's it's already got all this. Right. Right. And um so yeah   
1:06:00   
um and yeah and and of course you know   
1:06:08   
final bit like it's got it's got some some decent basic example with 2D pawn.   
1:06:17   
Oh yeah. You know, and and like you said, this is   
1:06:22   
this is what Dishbrain this is what the the braineers together with Brett Kagan have   
1:06:30   
have been doing in terms of goal orient goal they call it yeah I think it's goal oriented um   
1:06:38   
uh behavior in in brain tissue right so   
1:06:44   
not even not even a an animal Um, it's it's just that that   
1:06:51   
kind of adaptive adaptive tissue response.   
1:06:57   
Um, so yeah, I mean, as I said, I I I really   
1:07:04   
like him. I've been um finding a number of examples where his his group comes up   
1:07:12   
or his posts come up um most most recently. So, so we did the um   
1:07:20   
uh what is intelligence book for our reading group. This is the blaze   
1:07:28   
uh I always forget his name Agera Arcus I think is   
1:07:35   
um so this is the team team leader paradigms of intelligence a team at   
1:07:40   
Google. This is the this is the team that Blake Richards just joined.   
1:07:48   
And um uh there's there's a lot in it you know   
1:07:54   
it's got a very wide scope and the first chapter he spun off as as a separate   
1:08:01   
book which is called what is life where it summarizes the kind of computational   
1:08:08   
life uh his computational life paper from   
1:08:13   
2020 to 23. Um, I've got it here somewhere.   
1:08:20   
But, uh, if if you remember, you know, he likes he likes talking about this   
1:08:27   
because he gets to say green Yeah.   
1:08:32   
And the, you know, which is which is particularly   
1:08:40   
funny because it's like, you know, if you know the story of Brain it's like It's like like a grad student's   
1:08:48   
attempt to to mess with you. Yeah. um uh   
1:08:56   
as a as a as a cruel joke, but um you   
1:09:01   
know, it's an interesting I mean, I I think it would be great to do a deep   
1:09:06   
dive on that particular paper because it's it's super key to his   
1:09:14   
uh his push to see symbiogenesis   
1:09:20   
as a key mechanism. for his um   
1:09:27   
computational life, computational intelligence   
1:09:33   
uh as as somewhat being synonymous. I mean, life life and intelligence,   
1:09:40   
you know, in a kind of, you know, leavenish way. Um   
1:09:46   
uh the the the the life part just needing that self-relication,   
1:09:52   
right? And and um anyway, I'm not Oh, yeah. Yeah. Yeah. This, you know, um but   
1:10:01   
the reason I I bring it up in terms of um   
1:10:07   
uh of this context is that um uh two   
1:10:12   
things. So one um he we got talking   
1:10:17   
about this like he he wanted to say you know I mean the other way I was   
1:10:25   
summarizing this book was saying like this is the longest introduction to active inference that you can imagine   
1:10:32   
because it's it's someone who's who's saying that uh   
1:10:41   
once you He he's got a very like, you know, leaven   
1:10:48   
single cells need to model their environment and that becomes a a loop   
1:10:54   
that you kind of tighten to to reach anticipation.   
1:11:01   
But that that once you realize that your environment has agents that are like you   
1:11:09   
that are modeling their environment and and potentially you you know that this   
1:11:15   
sparks a an arms race of of   
1:11:21   
anticipatory systems that that he wants to credit with a lot   
1:11:29   
of of you know growth. in intelligence and, you know, likes to to put this in a   
1:11:35   
Cambrian um um what do they call it? The Cambrian   
1:11:41   
explosion. No. Yeah. Yeah. Is it? Yeah. But you know that you know what I'm talking about like   
1:11:47   
Yeah. And that this this particular   
1:11:52   
um this this this   
1:11:59   
modeling of agents in your environment he wants to say it has as a second   
1:12:08   
repercussion. Um so so one it's it prepares you for war. Two, it prepares you for um   
1:12:21   
social groupings or uh   
1:12:26   
uh cooperation. Let's let's call it coop cooperation, persuasion,   
1:12:33   
right? U or or you know   
1:12:38   
coercion, you know, like like   
1:12:44   
and this this   
1:12:49   
the one point we got we we're doing it as two-parter. So this is this is only   
1:12:56   
getting halfway through the book, but um he talks about uh octopuses   
1:13:04   
because the problem with this theory and I I you know I was thinking a lot about your um   
1:13:11   
cross species uh examples from from your talk Bradley   
1:13:17   
and you know how how useful that can be um and kind of what what would you think   
1:13:25   
of this particular uh uh oddity which is of course that octopuses   
1:13:32   
you you you you know they're smart, you know, they can model uh other agents. Um   
1:13:39   
but they're not social, right? And and so um you know, I'm I'm going   
1:13:49   
back and forth on um what to think about that, how to put   
1:13:55   
that in context, you know. Um, but it's funny because uh what while I was   
1:14:01   
reading that, Alexander Shaw like talked about a paper that he's writing on um uh   
1:14:11   
soft body soft body mechanics, soft body control in octopuses and active   
1:14:18   
inference and you know so it got it got that that   
1:14:27   
which apparently hasn't hit archive yet. Yeah. Or or I would share a link like all all   
1:14:34   
I can find is the his his LinkedIn post on this. Um but then the   
1:14:42   
but that I think that is interesting. There's there's also a lab at Berkeley. I think it's the Dole Dole Lab. Um   
1:14:50   
spelled the Turkish way. So the there's some weird mark over the U. Um, and the   
1:14:59   
they they've got one species of octopus that's kind of social.   
1:15:07   
Uh, and we think we should study them and   
1:15:14   
and so I'm curious what you think on that. The the other the other funny aside on the doll lab is that   
1:15:22   
um that they've been giving psychedelics to these   
1:15:29   
and and you know there's this long history of of giving psychedelics to   
1:15:35   
animals you know so like I don't know if you remember the the um   
1:15:44   
scientific American had this Um, I mean this this was obviously a paper first, right? But like like giving giving   
1:15:52   
spiders LSD, which just, you know, I mean, it's like   
1:15:58   
it's like I mean, I guess I get why this gets through IRB, but how do you really   
1:16:04   
justify this? There was a point in the 50s and 60s where they just gave every LSD to   
1:16:10   
everything. Exactly. It was it was in the water so to speak. Yeah. And and um   
1:16:19   
well you know and of course the funny result is that um it is it is tough. It is tough. Um yeah,   
1:16:28   
so as an undergrad I um I built   
1:16:35   
as an undergrad I built uh operant chambers for crabs and crayfish and of   
1:16:44   
course they're underwater. So this is this makes it really hard   
1:16:50   
because you can't just drop a pellet in there and and be like you know There you   
1:16:56   
go. Um, if if it's in water, it potentially floats away. Yeah. You know,   
1:17:03   
like like so, um, yeah, we had to we had to come up with some things. Yeah. I   
1:17:10   
give VG some time here. But the um interesting topics that that that   
1:17:18   
relevant I mean you know like what is intelligence uh paper or book is definitely trying to   
1:17:26   
collect um uh is trying to marshall a lot of   
1:17:33   
different threads but but that really come together in   
1:17:40   
you know Again, it's like um is it is it correct to say precedence bias where   
1:17:46   
it's just like like because I was I was introduced to active inference first.   
1:17:51   
It's like all all I see in what is intelligence is like building up to this kind of active inference story.   
1:17:57   
Yeah. and and and um uh   
1:18:03   
yeah anyway the the the u   
1:18:09   
you know it was also nice that that like the paper we did before this was the the   
1:18:14   
biological underpinnings of lifelong learning system because that that was like that's like a perfect precursor   
1:18:22   
paper or um preceding paper to this this as well and   
1:18:30   
this is a nice this is really nice overview of all that of kind of this   
1:18:36   
this material. So yeah to V's point she said but I wonder   
1:18:41   
how we can study animals underwater like ant colonies particle swarms etc. All   
1:18:46   
these algorithms have been studied because they are on land. Yeah, this is interesting because the kind of the the   
1:18:53   
way we like use these like we'll have like computational models like swarm intelligence algorithms and things like   
1:19:01   
that and that's really based on the idealized behavior. So you know that is like kind of we observe them in certain   
1:19:08   
ways in the lab. We characterize the behavior and then we say this is the algorithm that they use and then of   
1:19:15   
course you know we're looking at idealized behavior. So it could be in different environments they use   
1:19:20   
variations on this or you know I mean like with ant colonies you're using this   
1:19:27   
principle where you have ants they lay down their pheromone ants follow the pheromone and then they build these   
1:19:33   
networks and we assume that they're optimal or you know there's some optimality criterion which is why we're   
1:19:40   
interested in it but it could you know there are cases where they just build   
1:19:45   
structures and those structures have some sort of complexity. Um, in divorm a   
1:19:51   
couple weeks ago, I did a paper on, um, this isn't the recording, uh, not in the   
1:19:58   
main meeting, but it was a paper on building these, um, wasp nests or wasp,   
1:20:04   
uh, colonies where they have these chambers that have like levels and then   
1:20:11   
ramps. And they have to figure out how to do that amongst the individuals. And like it turns out that like the the   
1:20:18   
nests aren't all the same, there's some a lot of variation, but because they're   
1:20:24   
interacting that those interactions are basically constraining the architectures   
1:20:30   
that can be used. So they have the same architecture, but there's a lot of variation in the architecture. And so   
1:20:36   
and then of course if you have different types of materials available to the wasps, they build different types. they   
1:20:43   
may or may not be able to build that ar you know use that same architecture. And the model that they used in this was   
1:20:50   
well they they observed like some extent wasp uh nests and then they built a   
1:20:57   
computational model that involved resource availability and then environment like the physical   
1:21:04   
environment and then the behavior and that constrained the behavior. So if you constrained it by, you know, putting it   
1:21:10   
in a moist environment where the the mud was like really moist versus really hard   
1:21:15   
packed, you get different architectures there. But, you know, that's the kind of what we're looking at there is almost   
1:21:22   
kind of like the emergent properties. That's what people are interested in, not the kind of the exact behavior which   
1:21:29   
is interesting because that you know in in the world of algorithms we're kind of interested in the exact behaviors but   
1:21:36   
you know uh you know we're also estimating a lot too.   
1:21:42   
What would you like? I was just gonna say that that just to finish that one thing that   
1:21:48   
they're giving Gold Dolan's lab is giving um   
1:21:54   
psychedelics to these octopuses to improve their sociology   
1:21:59   
or their Yeah. At least that's the theory.   
1:22:05   
Yeah. Yeah.   
1:22:11   
Okay. So, VI uh right. Hi, how are you? How are you? So, it's not very formal   
1:22:18   
presentation. I just have a report even that's not formatted well and yeah so   
1:22:23   
our problem was the Amazon post that recommendation and like we know that there are a lot of   
1:22:29   
first time users and Amazon suggestion things they have their own algorithm of   
1:22:35   
course but um we have chosen the Amazon data set like the Amazon reviews data set that's how the term Amazon cold   
1:22:42   
start came in and this whole problem is called as cold start so that's what we   
1:22:48   
try to do like we try to create a model that could recommend that like not exactly but it was a model that could   
1:22:55   
tell us how accurate uh predictions can be we have used fast light GCN for this   
1:23:01   
and fast GCN and GCN is basically nothing but graph convolutional networks   
1:23:08   
so yeah I've just explained like we made this report because it was a good project and   
1:23:15   
like we made this report and we tried to explain pretty That's what our problem was. So the whole motivation of it is to   
1:23:22   
recommend systems that are crucial for e-commerce platforms like Amazon etc. And I mentioned as I mentioned   
1:23:29   
previously we named it Amazon because our data set is Amazon. I can show you the data set   
1:23:36   
right. So I'll just quickly run through it. We thought that um even cold start has   
1:23:43   
multiple different types of pard like a strict pard long long tail coat or   
1:23:48   
sparse data set. What we did is we thought that if a user has had like   
1:23:55   
interactions equal to two we can like interactions less than or equal to two. So even that user is actually new   
1:24:02   
because they have just ordered one product. So if there's a homepage then what should be suggested to that user?   
1:24:09   
So we took K as the interactions and we specifically kept it as less than or   
1:24:15   
equal to two and we divided this whole thing into two phases. The first phase   
1:24:20   
was uh the general recommendation system using the graph neural networks and the   
1:24:27   
second one was to focus on the users with less than or equal to two interactions. So as I mentioned earlier   
1:24:34   
we have this far side GCN model and before we started anything we created a   
1:24:40   
graph which is a bipartite graph system and there were user nodes and item   
1:24:46   
nodes. So user notes were for the customers item nodes were for the products. So these are the two graphs   
1:24:52   
that we made and then both of them were connected by using the mapping which user has ordered which products. We   
1:24:58   
mapped them and these edges were created between the nodes bas based on the   
1:25:06   
rating that was there. So I think I should just show you the data set.   
1:25:16   
The data set is here like it's pretty big but mostly we have used   
1:25:22   
the user ID, product ID and profile and helpfulness did not help us much. We use   
1:25:28   
the score to make the edges of the graph and the text reviews to help us a bit   
1:25:34   
more. So all right, I'll just quickly run through   
1:25:40   
it. So we chose light GCN over other models because it has those feature   
1:25:45   
transformations and nonlinear activations. Also, it was faster and simpler and we did not have much time to   
1:25:51   
implement this. So we chose a very smaller like an or easier model that could do a lot in less time and the main   
1:25:59   
thing is that it it has a graph and it does not involve weight. So it can just learn from the nearby nodes.   
1:26:06   
So we showed that and yeah so why we chose fast light GCN is because in   
1:26:13   
normal standard like GCN we have only one positive item and one negative item and it uses the BPR loss. Whereas the   
1:26:21   
fast GCN we can actually have one positive and three negative items. So we   
1:26:26   
have this is the fast GCN like the approach that we use and yeah so the   
1:26:32   
contrastive loss is nothing but uh one positive and many negatives together and   
1:26:37   
also the main thing of what contrastive loss means is that it can group the similar items together and it also   
1:26:44   
groups the unsimilar items together. So when we create this model and the user is suggesting something like when the   
1:26:51   
when something is suggested to the user we also know what is to not get supposeded we also know what is not   
1:26:59   
supposed to get recommended to the user. So even if there's something random happening we can avoid the negatives in   
1:27:05   
that and then we use the coign and even learning rate. So it's as simple as   
1:27:10   
understanding how vector products work that if we have if we multiply two   
1:27:16   
vectors like the product ID and the user ID and if we get some cos theta for example if it's zero that means they're   
1:27:22   
in the same direction and since they're in the same direction that means they are alike the angle is 90° if they're   
1:27:28   
perpendicular that means they're not very alike but it's not negative and if it's like completely opposite 180° then   
1:27:36   
it's opposite right like two opposite directions that's not supposed to be suggested. And then we had yeah just a   
1:27:44   
few more equations and then we changed it for 200 epochs. So our graph had three layers because   
1:27:52   
that was the optimal thing that we found in other papers   
1:27:58   
and yeah this is just explaining about how the layers are like layer one is the the layer zero is the initial layer and   
1:28:05   
then the three layers and how it works. So before we tried light GCM, we also   
1:28:11   
thought that we can use a simple model like logistic regression but like we we   
1:28:17   
were wrong over there because logistic regression failed and logistic regression is usually for like binary   
1:28:24   
things like no should this be suggested should this not be suggested but our problem was more complex and we wanted   
1:28:31   
to suggest better things to the users. So yeah, this is just the math part of   
1:28:36   
it of what we used and this is the node degrees to popular nodes so that they   
1:28:42   
don't dominate and yeah I guess I'll go a bit faster.   
1:28:48   
So we had 120 epochs as I said and in each of those epochs we had like 4096 random   
1:28:56   
batches or like a batch of 4096 interactions of pairs of user and the   
1:29:01   
positive item and yeah the peak three times is because of the three layers and   
1:29:07   
again the cosine and that we used. So we had that and then of course before   
1:29:12   
everything we we had to work with the data to understand what it is. So there were total of uh like 256,000   
1:29:22   
users and these many items 94,000 items and these were the total interactions   
1:29:27   
between them. That means like roughly most of them had had around two interactions and then this is what the   
1:29:34   
graph talks about that if these are the number of interactions per user and these are the users then the K that we   
1:29:40   
chose as two is quite optimal because K equal to two will come somewhere around   
1:29:45   
this red line. And yeah, most of the users have had around two interactions. So this data set is good for a cold   
1:29:53   
start problem basically and it's a long data distribution.   
1:29:59   
So yeah, this is just about this graph and the cold start cut off which we kept   
1:30:04   
as two later on like we focused it only to two users. And then this is the   
1:30:10   
processing pipeline again that originally there were these many interactions that means these many users   
1:30:16   
and these many items. So again it talks about the same thing and after filtering we had 35% reduction in the interactions   
1:30:23   
because K is equal to two. So now we have focused everything to two and then we had the implementation. So these are   
1:30:31   
nothing but the model parameters. The embedded dimensions are 128. That means   
1:30:36   
of 128 traits. For example, a user has bought a book. So now based on that book, we can have 128 trades like okay,   
1:30:42   
this book is maybe in scientific contest. So it's more technological   
1:30:48   
something or maybe the user likes buying only books. So like that we had those embedded dimensions than layers and the   
1:30:55   
learning 120 box. And yeah, dropout is most important to ensure that there's no   
1:31:00   
overfitting happening. Otherwise if the model is overfitting then there's no   
1:31:06   
point of it. So again this was how we did our prediction   
1:31:12   
and then yeah so to evaluate our model we kept the hit ratio and hit rate and   
1:31:18   
hit rate is nothing but how many times the proportion of the users for whom at   
1:31:23   
least one relevant item appears in the top key recommendations. So here K is not the interactions but K is the number   
1:31:31   
of users with at least one hit point like K is the number of items that are displayed like first five items or first   
1:31:38   
10 items and then we had the NDCG as well which is not very important because   
1:31:43   
we work mainly with the hit ratio to know how many times the correct thing is being recommended in the top K product   
1:31:52   
and then yeah this was the evaluation then our results Of course the loss was   
1:31:58   
reducing over the epox and we had 120 epox and yeah this is what we got. HR at k is   
1:32:06   
equal to 5 is 51%. That means when there are five products   
1:32:13   
the recommendation is correct by 51% and if there are 10 products and the recommendation is   
1:32:18   
correct by 53%. So as K increases that that means the number of items that are   
1:32:24   
being recommended even the hit ratio is increasing.   
1:32:29   
So yeah that's the graph of hit ratio that the hit ratio keeps increasing and   
1:32:34   
it goes to 59% which is almost 60%. So that's a good rate   
1:32:41   
and these are the items embedding visualization. So since we cannot have 128 dimensions that we can show in a   
1:32:48   
graph, we had only dim one and dim two by the 128 embeddings are divided not   
1:32:53   
equally but in some mathematical way. And then this graph is actually these   
1:32:59   
all these nodes are the items and the ones that are very close clustered are the ones that are related to each other.   
1:33:06   
The ones that are far like the distance is based on how related the items are to   
1:33:11   
each other. So that was about that and yeah we just created a model and had the   
1:33:19   
hit ratio definition for it so that Z can talk about what is the what is the   
1:33:26   
accuracy of the model. We didn't have much time so we couldn't implement the actual part where we could have some   
1:33:33   
recommendations going on because you would need another data set for that. But uh this is how our model works and   
1:33:40   
yeah these are some of the outputs. I think I showed this as well this   
1:33:48   
these are again just the outputs. So we had some design   
1:33:54   
challenges. Uh we haven't included the part where we   
1:33:59   
tested it on logistic regression and it didn't work out. We just included the standard light GCN and the PPR loss. So   
1:34:06   
BPR is actually Bashian probability and even though it is based on a preference   
1:34:12   
like how the Bian law works it didn't work well because over here this like a   
1:34:18   
very low model like it has lesser capacity and it has it has a very weak training thing happening. So with one   
1:34:25   
positive it can take only one negative. That's why it was also overfitting because it knew that it knew that only   
1:34:32   
this pair exists. But then the contrastive laws that we used could actually map one positive with three   
1:34:39   
negative. So that helped us a lot. And yeah we can just see again the training over the box. Then we had another hybrid   
1:34:47   
content GCN GNN graph neural network where we only included where we only   
1:34:54   
included the positive interactions. That's why what happened is that we got the hit ratio as one which is 100%. And   
1:35:01   
that's why the model was overfitting. So we have explained why we chose those   
1:35:07   
hyperparameters where we chose three layers as it worked out to give the best balance between HRB   
1:35:15   
and DCG and yeah that's it as I think   
1:35:23   
all right well that's great so this was part of a class or a pro a program   
1:35:29   
project or what was this? Uh so it's like we have a course machine   
1:35:34   
learning that's a theory course and then our faculty actually wanted us to   
1:35:41   
implement something like she was like just learning algorithms is not a good thing. We should probably try to think   
1:35:47   
of a model or use something that is already existing or not already existing but we should   
1:35:54   
try to explore something and try to implement it so that our learning can improve. So that's how we thought of   
1:36:01   
using this. Yeah, that's great. That looks good.   
1:36:07   
Any questions for V?   
1:36:12   
Yeah, it was great work. Yeah, go Jesse.   
1:36:17   
Yeah. All right. Well, thank you, Vie. Congratulations on that.   
1:36:23   
All that good work. Yeah. All right. Uh, Jesse, did you want to   
1:36:30   
give an update? Um, I'll say a few things.   
1:36:35   
Okay.   
1:36:42   
Uh, I forgot what I said last week about plot twisters and in depth, but um their   
1:36:49   
play testing session has gone well and they're continuing to do more of that. this week um they postponed one of their   
1:36:57   
sessions uh to reorient it to get a bit more one-to-one feedback. So, it's sort   
1:37:03   
of interesting when you're trying to do a play testing session, but you you you make a group of people operate as if   
1:37:10   
they're one person in a in a going like going through a procedure. Kind of   
1:37:17   
wrapping some things up with data and direction folks and general pro like we're kind of getting to   
1:37:24   
you know, a stopping point for the semester. And I think that's good. Like   
1:37:29   
many of the people have been working kind of continuously on it. And it's like, okay, we need to,   
1:37:34   
you know, you get to the part of the year where it's like, you know, both people are going to if you don't do something very   
1:37:40   
intentionally, then it's just going to drift away. I'm very aware of that and I'm I'm attempting to facilitate   
1:37:48   
that happening and at the same time like building up some momentum for other   
1:37:54   
things I want to do in the year ahead. It's very it's very   
1:38:00   
you know it's very hard in the sense that it's   
1:38:06   
already it's already basically Thanksgiving and Thanksgiving is already basically the end of the year. So, it's   
1:38:12   
like you I always find this to be a challenging time of the year when when   
1:38:18   
arranging everybody else's stuff because it's it's it's just such a it goes so   
1:38:26   
fast and there so it's like being on a slide like you don't have a lot of lapal movement. It's all just going.   
1:38:33   
So, that's kind of you know high level stuff. um   
1:38:39   
next week. I don't know if I can easily pull this up. Let me let me try   
1:38:46   
um me try to to get something   
1:38:54   
next week. I might want to take a deeper dive into a specific paper and I don't know if I can easily pull it off. Um   
1:39:01   
okay, let me try this. I I might just loosely preview the paper, but it's a   
1:39:06   
very interesting paper on a number of fronts um because   
1:39:12   
it deals with many subjects of   
1:39:19   
u interest. Yeah, I've got the paper here now and I I'll only spend a couple minutes   
1:39:26   
on this just to tease it. Um   
1:39:32   
yeah it's called reflective   
1:39:38   
agency ethical and empirical framework for ad AI mediated self-reflection systems and   
1:39:45   
this is out of um MIT media lab Rosen Vicard Patty May so this Mel Kim the   
1:39:52   
lead author is in fluid interfaces um I believe And what's interesting   
1:39:59   
about this paper is that it it's sort of a it offers it   
1:40:06   
creates a framework. It offers a little bit of a investigatory case study of   
1:40:11   
among existing AI journal chatbot type things   
1:40:16   
and then also has a sort of a a user a small user study too. And what they look   
1:40:23   
at is I don't I don't have my highlights on this version, but that's okay. But   
1:40:28   
what's quite interesting and what we can talk more about next time is um they ground their analysis in   
1:40:37   
philosophy and phenomenology. So they talk about um   
1:40:43   
you know they get it as Arisilian virtue ethics a similar philosophical grounding but phenomenology in terms of um Eday   
1:40:51   
and Haidiger. Am I saying that right? Eiday I don't know um   
1:40:59   
but Haidiger and and some other stuff that we've kind of got gotten around to.   
1:41:05   
And um I appreciate the sort of   
1:41:11   
phenomenologically grounded take on human computer interaction, but also   
1:41:17   
like what how how um   
1:41:22   
how things are designed to constrain or maintain space for uh   
1:41:33   
reflexive reflective agency or or curiosity or um   
1:41:39   
you know things like what how you're designing something as a   
1:41:44   
means by which you're you're putting tipping the scales on um comprehension   
1:41:50   
or determination of you know narrative or or what things mean and I think I   
1:41:58   
think it's a it's a very interesting blend of like actual useful phenomenology and and the AI stuff and   
1:42:04   
then you know language and comprehension subcondition futures type things. It's very it it and and also like the last   
1:42:11   
thing I'll say is like the paper also you know it it kind of it kind of um   
1:42:21   
suggests like you should have an important amount of friction to slow things down as opposed to just a   
1:42:28   
conclusion and then how you should feel about that conclusion or how you should feel about your from a particular   
1:42:33   
experience or perspective is just automated and kind of you know well   
1:42:38   
here's the answer you know and that very sort of classic GTP like well here's the conclusion and and kind of you know   
1:42:45   
maybe alluding to some nuance but not really participating fully in the creation of   
1:42:52   
it at best versus you know passively or steering or indoctrinating you to a very   
1:42:58   
nice viewpoint or or or or a a uh a   
1:43:03   
cadence of interaction that is beneficial to people who want you to use the app as opposed to you know um   
1:43:11   
actually exploring what what your your situation might be. So   
1:43:17   
I will conclude by saying the paper in one sense I think is is a complete justification for why plot twisters   
1:43:23   
exist because in essence plot twisters is you know our our existing use of AI   
1:43:30   
is I don't even know how to say or comment   
1:43:35   
on it but but let's say it's it is not yet um   
1:43:42   
we are investigating possibilities and do not reach a full conclusion yet. I think it's is fair to say about what   
1:43:49   
kind and how to use AI and modern AI um within plot twisters. I can say that   
1:43:56   
much. But in spite of that or regardless or like   
1:44:03   
unrelated to that specifically um plot twisters is inherently formed around the   
1:44:09   
idea of what they're calling reflective agency or being able to be aware of and   
1:44:14   
have a sense of your own narrative and what does that look like and how do you how do you how is that modeled for   
1:44:19   
people to engage in in the game world. So, I'll leave it at that, but I think   
1:44:24   
it's a very interesting paper in terms of both like some research like I really I think I might reach out to the the   
1:44:30   
lead author um and and kind of have them talk to me or maybe talk to plot twisters or do something that's open to   
1:44:36   
like our our general community because a lot of people in the a lot of people in our community and I by that I mean like   
1:44:42   
orthogonal andro and maybe flat twisters and maybe echalopto and maybe some other   
1:44:48   
you know people in this in this space both at larger too like um in terms of   
1:44:54   
game development around this stuff. Um Amanda Curtis is is like doing a lot with that and part of you know leading   
1:45:00   
up the metagub stuff and play testing and also just Boston like like this is a   
1:45:06   
very Bostonbased thing like that that that these groups are looking at. So I look forward to following up   
1:45:12   
with that. Um and maybe we can do a deeper dive next time or I can do a better summary next time because I'm   
1:45:18   
writing up some things about it too. I think it'd be a nice um a nice bridge uh   
1:45:24   
in a way that I'd like to see more of. Uh so yeah, that's that's what that paper is. And then um   
1:45:33   
um I'll leave it at that. There's a few other things, but we can say more next time if I think we're meeting next week   
1:45:39   
or we or is that the week of Thanksgiving? We're not going to meet then. I forget.   
1:45:44   
Thank you for that presentation. Yeah. Okay. Yeah. Yeah. Okay. Let me   
1:45:51   
know. But even I'll I'll I'll make a recorder write something about it either way. I think it's it's one of those um   
1:46:00   
it's something that I'll be I'll be citing a lot of. I think I think the frame of development will be relevant to a lot of things and plot questions and   
1:46:08   
then maybe some other things too. Okay. Good. Thank you.   
1:46:13   
Yeah. Uh yeah. Morgan, did you have something to say or   
1:46:19   
No, certain certain children have of have a   
1:46:25   
Okay. And um yeah, are making No, it's it's good. Um but I   
1:46:34   
I did kind of miss the last bit there. Um although I I think I'm down for   
1:46:42   
meeting on Saturday, next Saturday, too. I'm I'm certainly hoping to connect with   
1:46:50   
some uh Hopkins people. Okay. Um I'll be in Baltimore.   
1:47:00   
That's that's where we do that's where we do holidays. Yeah.   
1:47:07   
Because we can fit fit, you know, 20 25 people   
1:47:12   
in one place. Yeah.   
1:47:17   
Okay. Sounds good. Thank you. So, I think I   
1:47:22   
want to go over two other papers to finish off. And these are kind of like just I'm not going to get deeply into   
1:47:28   
each of these, but um these are things that were brought up in the Slack or   
1:47:34   
before. So, I wanted to kind of go over them and you know address them. So this is the uh   
1:47:42   
this is a Google deep mind paper. This is alpha evolve. Um so I can't   
1:47:50   
remember where this came up. Maybe one of our discussions or in the slack. So   
1:47:56   
this is alpha evolve coding agent for scientific and algorithmic discovery. So   
1:48:01   
they're doing this sort of AI scientist type of thing. Uh this is their white   
1:48:08   
paper. So in this white paper, we present Alpha Evolve, an evolutionary coding agent   
1:48:15   
that substantially enhances capabilities of state-of-the-art large language models on highly challenging tasks such   
1:48:22   
as tackling open scientific problems for optimizing critical pieces of computational infrastructure.   
1:48:30   
Uh, Alpha Evolve orchestrates an autonomous pipeline of large language models whose task is to improve an   
1:48:36   
algorithm by making direct changes to the code using an evolutionary approach.   
1:48:41   
Continuously receiving feedback from one or more evaluators. Alpha Evolve iteratively improves the algorithm   
1:48:48   
potentially leading to new scientific and practical discoveries. We demonstrate the broad applicability of   
1:48:55   
this approach by applying it to a number of important computational problems.   
1:49:00   
When applied to optimizing critical components of large-scale computational stacks at Google, Alpha Evolve developed   
1:49:07   
more efficient scheduling algorithm for data centers on a functionally equivalent simplification in the circuit   
1:49:14   
design of hardware accelerators and accelerated the training of large language models underpinning Alpha   
1:49:20   
Evolve itself. Furthermore, alpha evolved discovered novel, provably correct algorithms that   
1:49:28   
surpass state-of-the-art solutions on a spectrum of problems in mathematics and computer science, significantly   
1:49:35   
expanding the scope of prior automated discovery methods. And this is a citation here. Romero paredal 2023.   
1:49:45   
uh notably alpha evolve developed a search algorithm that found a procedure to multiply two 4x4 complex value   
1:49:53   
matrices using 48 scaler multiplications offering the first improvement after 56   
1:50:00   
years over stress and algorithm in the setting. We believe alpha evolve in   
1:50:05   
coding agents like it can have a significant impact in improving solutions to problems across many areas   
1:50:12   
of science and computation. So this paradus at all paper.   
1:50:18   
So this is the nature paper mathematical discoveries from program search of large language models. Um and this is their   
1:50:27   
kind of approach to this. Uh large language models have demonstrated tremendous capabilities in solving   
1:50:34   
complex tasks from quantitative reasoning to understanding natural language. However, large language models   
1:50:41   
sometimes suffers from confabulations or hallucinations which can result in them   
1:50:47   
making plausible but incorrect statements. This hinders the use of current language or current large models   
1:50:53   
in scientific discovery. Here we introduce fun search for searching the   
1:50:59   
function space not that they're actually fun. Um, and this is an evolutionary procedure based on pairing a pre-trained   
1:51:06   
large language model with a systematic evaluator. We demonstrate the effectiveness of this   
1:51:12   
approach to surpass the best known results in important problems pushing the boundary of existing large language   
1:51:18   
model based approaches. Applying fund search to a central problem and external   
1:51:24   
external combinatorics capset problem we discover new constructions of large caps   
1:51:30   
going to be the best known ones both in finite dimensional and asintoic cases.   
1:51:37   
Uh this shows that it is possible to make discoveries for established open problems using large language models. We   
1:51:44   
showcase the generality of fund search by applying it to an algorithmic problem online bin packing finding new heristics   
1:51:51   
that improve upon web's baselines. In contrast to most computer search   
1:51:57   
approaches, fun searches for programs that describe how to solve a problem rather than what the solution is. Beyond   
1:52:04   
being an effective and scalable strategy, discovered programs tend to be more interpretable law solutions,   
1:52:11   
enabling feedback loops between domain experts and the fund search agent and then deploying such programs in world   
1:52:18   
applications. So this is the paper here. Um   
1:52:24   
this just kind of describes the fund search agent and how they did this. So back to this paper here.   
1:52:31   
So they actually compare fund search and alpha evolve in table one. Uh this is   
1:52:36   
the fund search is their previous agent. Alpha evolve is their new agent. Um so   
1:52:42   
fund search does something and then al involve so I guess improves upon it in   
1:52:49   
some way. So fun search evolves single functions. Alpha evolve evolves entire   
1:52:55   
code files. Fun search evolves up to 10 to 20 lines of code. Alpha Evolve   
1:53:01   
evolves up to hundreds of lines of code. Fun search evolves code in Python. Alpha   
1:53:07   
code evolves any language. Fun search needs fast evaluation around   
1:53:12   
less than 20 minutes on one CPU. Alpha Evolve can evaluate for hours in   
1:53:18   
parallel on accelerated GPUs. uh fund search allows for millions of   
1:53:25   
large language model samples to be used and in alpha evolve only thousands of   
1:53:30   
large language model samples can surface. One search uh uses small large language   
1:53:37   
models there's no benefit from the larger models alpha evolve benefits from   
1:53:43   
the state-of-the-art large language models. Fun search uh uses minimal context which   
1:53:51   
draws from only previous solutions. Alpha evolve draws from rich context and   
1:53:56   
feedback and prompts. And then finally fun search optimizes single metrics   
1:54:01   
whereas alpha evolve can simultaneously optimize multiple metrics.   
1:54:07   
Okay. So that's uh and then this is the highle review of   
1:54:12   
alpha evolve. So remember alpha evolve is is sort of an improvement upon the   
1:54:18   
previous their previous attempt at this.   
1:54:23   
In this case what we're doing here is we have this feedback between humans and   
1:54:28   
the agent humans define what the human set evaluation criterion provides in   
1:54:35   
initial solutions and optimal back optional background knowledge.   
1:54:41   
uh they provide a problem definition to the agent alpha evolve which figures out how   
1:54:47   
and then there's so there's this uh prompt sampler   
1:54:52   
and the prompt sampler gives rich content containing past trials and ideas   
1:54:57   
to a large language model ensemble that ensemble is a proposal of improved   
1:55:03   
programs that goes to the evaluators pool and then that ens programs with   
1:55:10   
quality scores and other feedback which goes to the program database and then   
1:55:16   
that those are programs that approve and act as inspiration and that goes then   
1:55:21   
back to the prompt sampler which then provides an approved solution to the   
1:55:26   
human. So this is interesting. We use an   
1:55:33   
evolutionary algorithm in this orchestrating procedure and that   
1:55:38   
evolutionary algorithm gradually develops programs and improves the score on the automated evaluation metrics   
1:55:44   
associated with the task. Actually why don't we go through creative generation.   
1:55:50   
So uh they use this creative generation. So to drive the evolutionary procedure   
1:55:55   
alpha evolve leverages the capabilities of soda uh state-of-the-art large language models. principal role is to   
1:56:03   
digest information about previously developed solutions and to propose new and diverse ways of improving solutions.   
1:56:10   
Although alpha alpha evolve is model agnostic in ablations we observe that   
1:56:16   
alpha evolve performs increasingly better as the underlying model improves.   
1:56:21   
So this is uh kind of their code here. Um   
1:56:28   
this is just showing um kind of the blocks here that they're   
1:56:33   
using. Um and just kind of thinking about this   
1:56:40   
and how this is implemented. Okay, so this figure three is an illustrative example of applying alpha   
1:56:46   
evolve to evolving a supervised learning pipeline. All snippets of code are abbreviated   
1:56:52   
with ellipses um which you can see here on the uh so   
1:56:58   
these are just the different code snippets that they're demonstrating indicating skip lines the user pro uh   
1:57:06   
provided file with blocks marked for evolution and a special evaluate function that can be evoked to score the   
1:57:12   
current version of the code. Example of an assembled prompt can be provided to the large language model. example output   
1:57:19   
generated by the large language model and c. So this is so this is a here this   
1:57:26   
is uh what is provided by the user. So this code here is provided by the user.   
1:57:34   
This code in b is an example of the assembled prompt which will be provided   
1:57:40   
the large language model. So you have the prompt here. So it looks like what we're doing here is we're sort of   
1:57:46   
annotating this and providing more detail. And then C is where you have an output   
1:57:54   
generated by the large language. So the models um that they use Alpha   
1:58:00   
Evolve employs an ensemble of large language models. Specifically, we use a combination of Gen Gemini 2.0 Flash and   
1:58:08   
Gemini 2.0 Pro. This ensemble approach allows us to balance computational   
1:58:14   
throughput with the quality of generated solutions. Uh G Gemini 2.0 flash that's   
1:58:20   
lower latency enables a higher rate of candidate generation increasing the number of ideas explored per unit time.   
1:58:27   
Uh Gemini 2.0 Pro possessing greater capabilities provides occasional higher   
1:58:33   
quality suggestions that can significantly advance the evolutionary search and potentially lead to   
1:58:39   
breakthroughs. The strategy mix optimizes the overall discovery process by maximizing the value volume of   
1:58:46   
evaluated ideas but retaining the potential for substantial improvements by the more powerful model.   
1:58:54   
Okay. So they they actually get into their evolutionary methods here. Alpha Evolve extends a long tradition of   
1:59:00   
research on evolutionary and genetic programming where run repeatedly uses a set of mutation and crossover operators   
1:59:07   
to evolve a pool of programs. In particular, classical evolutionary techniques have succeeded in symbolic   
1:59:14   
regression applications, automated scientific or algorithmic discovery and   
1:59:19   
scheduling problems. Now the challenge with evolutionary methods is the use of   
1:59:24   
handwritten evolution operators which can be hard to design and may fa may fail to cap capture important properties   
1:59:31   
of the domain. In contrast, alpha evolve uses large language models to automate the construction of these operators. It   
1:59:39   
leverages the large language models world knowledge and mutate programs without the need to predefine a set of   
1:59:45   
allowed mutation operators. So it actually mutates things using world knowledge of the web language model and   
1:59:52   
it doesn't use mutation operators as usually would in an evolutionary.   
1:59:58   
Um so this is uh so the fund search system uh is ex so   
2:00:09   
so fund search which was the precursor to this model um they they focused on   
2:00:16   
basian optimization and in alpha evolve they're using this sort of evolutionary approach   
2:00:24   
the second paper I wanted to talk about so the second paper I wanted to talk about here. Um, so did you have   
2:00:32   
something you wanted to comment on? Uh just just the the the   
2:00:39   
tradition that this is coming from, you know, like   
2:00:44   
kind of kind of goes back to   
2:00:50   
wanting to dive into Blaz's paper on computational life, you   
2:00:56   
know, because it's like like these are I mean these are kind of old ideas, you   
2:01:02   
know. Uh uh I I noticed that John Baptist M uh was the like wrote the um   
2:01:11   
the summary article to the alpha evolve. Okay. And and like like this is this is you   
2:01:19   
know this is an old you know a veteran of of gecko and and those kinds of you   
2:01:28   
know those kinds of uh conferences. Yeah. Um   
2:01:34   
uh uh I'm I'm blanking on his particular his particular technique, but like you   
2:01:41   
know it it I was thinking about it again with with regard to   
2:01:48   
what is intelligence because he he he makes the claim in the   
2:01:56   
um end of book four. He's trying to talk about like um   
2:02:03   
like a computational intelligence symbio like like and and I think what he's what   
2:02:11   
he's trying to get at or certainly part of this is that like um   
2:02:17   
how do you optimize like how do you deal with multiple objectives   
2:02:22   
and you know and again this is this is much more real   
2:02:28   
Yeah. And and and you know again like has this kind of   
2:02:33   
tradition at Gecko for like how do we make the most abstract   
2:02:41   
Yeah. multiobjective uh uh you know problem and   
2:02:49   
do Yeah. So just you know just just noticing like or you know it's lovely to   
2:02:55   
see this but it's also like interesting that it's like such an old   
2:03:02   
an extension of of old ideas. Um   
2:03:09   
and and like you know I I I love I love math as a training ground but like math   
2:03:16   
is also you know in a sense is like like the his bad is the toy problem.   
2:03:23   
Right. Right. Yeah. And it's this very specific um   
2:03:31   
problem set. Yeah. Super specific like super Yeah. It's   
2:03:38   
it's it's a um it's very easy to extract   
2:03:45   
or you know like focus on kind of one dimension at a time.   
2:03:51   
Yeah. You know like like if you know what I mean like um Yeah. But it's cool.   
2:04:00   
It's cool to see. Okay. Yeah. All right. Well, Jesse had to   
2:04:06   
leave, but I I'll finish up here with this last paper I want to talk about and I think we talked about this maybe in a   
2:04:13   
previous uh discussion or or it came up in the   
2:04:19   
slack. This is actually I see when Bernie is on this paper. Uh this is learning the natural history of human   
2:04:26   
disease of generative transformers. So this is very much sort of a a bioinformatics type thing where they're   
2:04:33   
using transformers to look at human disease discovery basically. Um and of   
2:04:41   
course we talked about the post transformer model possibilities. Now you   
2:04:47   
know this is a nice summary of sort of how you can use transformers in this uh   
2:04:54   
bioinformatic domain. And so you know that's another place where we can use transformers to look at how how well we   
2:05:02   
can do and then think about other types of models that we might use to get similar results or better results.   
2:05:09   
Uh so this I'll just go through the abstract here. So decision making in healthcare relies on understanding   
2:05:16   
patients past and current health states to predict and ultimately change their   
2:05:21   
future course. Artificial intelligence methods promises to aid this task by   
2:05:26   
learning patterns of disease progression from large amounts of data. However,   
2:05:32   
their potential have not been fully investigated at scale. So they modify um   
2:05:38   
what they call generative pre-trained transformer and they abbreviate that GPT. So it's a kind of confusing uh   
2:05:46   
architecture to model the progression and competing nature of human diseases.   
2:05:52   
We train this model deli2m on data from um 400,000 UK biioank   
2:05:59   
participants and validate it using external data from 1.9 million Danish   
2:06:05   
individuals with no change in parameters. Delta 2M predicts the rates of more than   
2:06:11   
a thousand diseases conditional in each individual's past disease history with   
2:06:16   
accuracy comparable to that of existing single disease models. Deli2M's   
2:06:22   
generative nature also enables sampling of synthetic future health trajectories providing meaningful estimates of   
2:06:28   
potential disease burden for up to 20 years and enabling the training of AI models that have never seen actual   
2:06:34   
death. uh explainable AI methods provides insights into deli's 2M stems   
2:06:42   
predictions revealing clusters of coorbidities within and across disease chapters and their time dependent   
2:06:48   
consequence on future health but also highlight biases learned from training data. In summary, transformer-based   
2:06:56   
models appear to be well suited for predictive and generative health related   
2:07:01   
tasks are applicable to population scale data sets and provide insights into   
2:07:08   
temporal dependencies between disease events potentially improving the understanding   
2:07:14   
of personalized health risks and informing precision medicine approaches.   
2:07:19   
So, a couple words on this. First of all, we talked about   
2:07:24   
looking at what presumably are transformers versus uh active inference methods. And   
2:07:32   
we see here that transformer models at least in this context can do this kind of predictive and generative work on   
2:07:40   
looking at a data set and predicting things in the data set. Uh but the you   
2:07:45   
know the the context here is healthcare data. So you know it is what it is. It's   
2:07:51   
not a like a a task like you know exploring a world where you have a lot   
2:07:57   
of unknown aspects to it. Um but the other thing I wanted to point out was   
2:08:04   
that in this case we're using a transformer to provide insights into   
2:08:12   
temporal dependencies between disease events. So we're looking at this these   
2:08:17   
sequences. Of course, in large language models, they have sequences of of tokens and putting those tokens   
2:08:24   
together in a meaningful way. In this case, what the transformer is doing is   
2:08:29   
is pulling together these temporal dependencies in a predictable way that   
2:08:34   
allows us to determine states. So, we have these disease events. we don't know   
2:08:40   
necessarily which ones uh you know cause other things or which ones go together   
2:08:47   
and we can do that with uh transforming. So we can highlight these temporal   
2:08:53   
dependencies um in these sequences. So this is kind of an interesting you know way to do   
2:09:01   
this. Um and it kind of frames this idea of the post   
2:09:07   
um transformer landscape because what is it that transformers do well? Um in this   
2:09:14   
case we see that they can um you know give us these predictive models. They do   
2:09:20   
have these sort of generative properties. They have can deal with temporal data well. together sequences   
2:09:28   
of events or sequences of things. And then of course we might compare that with something like uh uh active   
2:09:36   
inference model where you're requiring some sort of exploration of an environment. And then on top of that we   
2:09:43   
have these world models that we can employ. If we employ a world model to something like this then what is the the   
2:09:50   
added uh added value to that? And then maybe what is the added value to using   
2:09:56   
an active inference model in this case? Yeah, the you know it's it's interesting. Um   
2:10:07   
I you know I'm not too familiar with the kind of data set that that would be you   
2:10:14   
know um but another another big part of   
2:10:20   
um what his intelligence is him saying that   
2:10:26   
um you know he he he   
2:10:32   
was basically coming from developing you know, uh, autocomplete,   
2:10:40   
you know, and and so, uh,   
2:10:45   
you know, certainly someone who sees great power in the transformer model. um   
2:10:52   
or finding finding prediction as a as a fundamental   
2:11:00   
um fundamental feature of of agency, you   
2:11:07   
know. Yeah. and um now how that how that perhaps applies in   
2:11:14   
this case and I'm I'm open open to see   
2:11:20   
still not quite sure what what goes into those u the the one thing I wanted to   
2:11:26   
mention though was that um what we're hoping to start at the tower um together   
2:11:34   
with some some UCSF people Um well they had a great meeting uh actually the   
2:11:42   
wetware meeting. Sorry one second.   
2:11:50   
Sorry somebody decided to start practicing violin. Ah um uh u   
2:11:59   
the it's this model from the arc institute   
2:12:04   
called state and um this is this is also   
2:12:10   
a prediction model you know so so   
2:12:17   
I like it I mean you know one you know we're we're in a bolab Um, virtual cells   
2:12:25   
are all the rage right now. You know, all the uh all the the billionaires with   
2:12:33   
with intellectual aspirations are building virtual cell models   
2:12:40   
and or funding virtual cell models. And so uh   
2:12:46   
we're going to be doing a deep dive on that on that particular model and as as well as   
2:12:53   
you know hopefully make this into a um   
2:12:59   
ongoing project in the sense that like you know um new data sets new new   
2:13:07   
perturbation data sets uh are being released all the time and kind of   
2:13:14   
covering what's what's going into them to be able to make these um uh   
2:13:23   
partly these you know general agency kind of models cell cellular models   
2:13:30   
partly these drug response models right and of course you know that's that's   
2:13:36   
where I expect that there will be kind of like you know this is one of reasons   
2:13:42   
why like there will be plenty of money to collect data sets for this. Yeah. is that you know drug development   
2:13:50   
still uh is it's you know is a massive driver of of the the research and development   
2:13:58   
in these areas and um as we see with um   
2:14:03   
uh yeah sorry okay um   
2:14:10   
anyway we can we can follow up on that and you know but I think it would be really I think it's really interesting   
2:14:16   
to to deep dive on a transformer model that's   
2:14:24   
being applied to data that we better understand or kind of like I   
2:14:31   
don't want to say better I mean like um   
2:14:37   
I've got better mechanistic models of what's going on and what I what I really want to connect this to um is the uh 11   
2:14:48   
um um regulator what's he call it regulatory   
2:14:55   
um regulatory network machine.   
2:15:01   
Okay. Yeah. Uh I think I think is Yeah. So harness   
2:15:08   
Yeah. So, so he he's talking about it with with regard to, you know, this kind   
2:15:15   
of analog computing, you know, but I think it I think this actually gets at   
2:15:22   
um this gets at kind of Blaz's point about computation being   
2:15:30   
um uh being fundamental.   
2:15:36   
is that that you actually see this in um   
2:15:42   
yeah this this is this is a part of single cell genetic regulatory networks.   
2:15:48   
Yeah. and and you that it's it's quite easy to   
2:15:54   
see. Um I I I yeah just just I I think I think we can   
2:16:01   
connect it or I I like what he was doing in terms of   
2:16:07   
somewhat trying to add to artificial life simulations with with a slightly   
2:16:15   
more CS approach which he had there. Um but I   
2:16:23   
think we you know like like   
2:16:29   
yeah it it would be great to to find a domain in which there's um you know sort   
2:16:37   
of like that paper you just covered where it's just like you know global health data like that's a that's an   
2:16:43   
awesome topic to kind of look at that's kind of far from from where I'm at in   
2:16:49   
terms of of um data sets and you know I think I think if we focus on these   
2:16:56   
virtual cells I think there's there's a lot that we could cover that will stay   
2:17:01   
stay very you know um um   
2:17:08   
you know kind of divaorm relevant. Yeah. so to speak. I mean, you know,   
2:17:13   
diva worm and then what I want to call like um or like what Brett Kagan calls   
2:17:18   
bio-engineered uh um bio-engineered intelligence, you   
2:17:24   
know, right? Because because that's the that's the   
2:17:29   
that's the the um area where I'm trying to, you know, find   
2:17:38   
new ways to um extend these like uh   
2:17:45   
you know like the the the 2D pong like like can we can we do better than   
2:17:51   
that? But like you know by that I mean around around growing the neuronal tissue as well as   
2:17:59   
uh the complex yeah the complexity of those structures and networks and things like   
2:18:07   
that. All right, that sounds great. Uh, yeah,   
2:18:12   
let's follow up on that. Definitely, you know, in the next in the new year, you   
2:18:18   
know, we're always trying to sort of put thematic, you know, build thematic themes to get research out in DVO work.   
2:18:25   
So, that that that's probably going to be one of our themes. Yeah. Yeah. I mean, I'm I'm curious as   
2:18:32   
well. Um, just sorry, one last thing. um   
2:18:37   
uh foresight institute yeah released videos   
2:18:43   
that I can I can share you know like it's the from their um neurotch   
2:18:50   
and it's got um more details um from   
2:18:55   
Conrad Gording's Conrad Gording Ed Boon's oh yeah   
2:19:02   
uh um worm project for lack of a better I   
2:19:07   
forget maybe they gave it a name I forget but you know what I'm talking like   
2:19:13   
you know like super relevant um   
2:19:19   
uh although you know like what they're missing is the leaven part right which   
2:19:25   
is the development well yeah and just one last thing like like no   
2:19:33   
surprise to me at that Blaze is publishing papers with Michael Le.   
2:19:38   
Oh, yeah. Yeah, probably. Yeah. Yeah. But I I think those would be   
2:19:44   
interesting to cover too. Yeah. Yeah. That's great.   
2:19:50   
All right, let's call it a day and uh thanks for attending all the discussion.   
2:19:56   
See you next week. Sounds good. Take care. Take care. Bye. All right.   
