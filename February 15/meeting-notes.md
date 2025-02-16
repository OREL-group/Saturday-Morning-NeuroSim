## Meeting Recording

[YouTube link](https://youtu.be/6cR2Zg6vGyY)
## Mastodon thread

[link](https://youtu.be/6cR2Zg6vGyY)

## NOTES
Sampling Efficiency in BabyView paper: what is the difference between organisms and artificial systems?

what is sampling in the context of world models?

learning to walk —> continual learning emphasis.

vision and language models.


Robot learning —> robotics focus. Watch, then mimic.

language models — meet world models.

Chinese Room + LLMs. ML Street Talk episode.

“AI is a new way back to CogSci” paper.

NeuroTechX community — robotics stuff. Robotics clubs — well-funded, can be interdisciplinary.

robotics club is a way to show off. AI is a great way to learn about CogSci.

good Theory of Mind performance does not equal sentience.


Mentalism —> easy self-trap, related to LLM performance.

DeepSeek craze. What is your intelligence test assessment?

getting to DeepSeek —> creating new benchmarks.

Foundation Models — Automated Capability Discovery (ACD).

visualize AlphaFold progress, looks very different from previous work.

see the forest, not get caught up in the trees.

Stable Control Representations, edge-of-reach problem: Limited horizon rollouts from a fixed dataset leads to 'edge-of- reach' states: states which are used as targets for Bellman-based updates, but which are never themselves updated.


Logan Cross (met at NeuroMatch) — World Modeling: “animate agent world modeling benchmark”. Neuro/AI-focused.

counterfactual world modeling.

“more bio-realistic, less heavily supervised learning rules”. — NeuroAI lab (Yamins).

Paul Scotti — Stability AI, generative diffusion model companies —> Neuroimaging head, Discord group.

MedArc — Neuro people, LAION, OnNeuro.
Mind’s Eye — naturalistic dataset.  Restoring movies from fMRI data. Categorize papers — LLMentalist. Psychic’s con problem. 

softwarecrisis.dev (Book: Out of the Software Crisis).

SSL objective — representation and generalization in Neuro and AI.

NN architectures —> Yasmin’s and DiCarlo, 2016.

map architecture classes of CNN model to brain regions and/or pathways.


CogSci —> architecture class, task categorization, dataset.

William Hahn — artificial immune systems, developmental systems.

Glazier paper on in silica models of neural tube closure defects.

agent-based models —> brain development. GRNs, spatial expression in embryos.


Viral Epidemiology —> dynamical, ecological —> continuous dynamics, cybernetic vs. dynamical cognition —> lessons for NeuroAI?

reminder: what you’re looking at restricts your views of modeling.

cybernetics view vs. dynamical view. Continuous vs. discrete. 

motor, eye tracking are natural ways to approach this (moving and scanning environment).

data is temporally- and spatially-dependent. Nonlinear attractors vs linear trends.


Coordination Dynamics, Synchronization. Two similar complex systems.

Sapolsky — YouTube videos, father-offspring interviews. Why do no congenitally-blind people develop schizophrenia? Two rare things co-exist, but not at small sample sizes.

extend this to continuous data — easy to find thing, not always informative.

Hyperscanning —> very specific tasks, make results more interpretable.

error corrections in cognition and biology.

LLM engineering —> recommendations on multi-agent code developers.

error-corrections in cognition and biology. LLM engineering —> recommendations on multi-agent code developers.

Limiting to having a single code agent vs. a team.

dynamical model of code co-creation.

Simon Williston —> Django co-creator. LLMs can be a good code generator.
Cross, Spivey —> multi-agent —> ToM of other agents in open-source projects.

community — synchronizing and incorporating new agents.


Langchain —> how information flows, good for multi-agents.

emphasis on reasoning models —> MetaGPT —> deepwisdom.ai

LLM —> ABM —> reasoning models.


GLIMPRINT — continuous agent-based model —> bridges fundamentally different architectures. 

Default network in the brain —> connected to everything, does it mean anything?

AGI —> some agent has it, what taks would you give it to show this?

LeCun —> AI action summit in Paris.

LLMs not Royal Road here. Depends on benchmarks: nudges retrieval into reasoning.

* LSTM —> LLMs are just originator — a database — tex input to different models. Depends on benchmarks.



Sarrah Bastawala
Sarrah Bastawala says:
https://github.com/geekan/MetaGPT
 
11:07

Sarrah Bastawala says:
https://github.com/OpenBMB/AgentVerse
 
11:11

Sarrah Bastawala says:
https://docs.google.com/presentation/d/10Oe4Ep5H108I8Jm8CCxDXk6WOYQ_y8o5TK9W_x82IkA/edit?usp=sharing

This was also the original presentation (i.e one before doing the project) which should also help @morgan 
11:16

Morgan Hough
Morgan Hough says:
Global Alliance for Immune Prediction and Intervention 
11:19

Morgan Hough says:
https://www.youtube.com/live/-Rw7oKwms5s?si=90due2E6af2TXH_7
 
11:20

Sarrah Bastawala
Sarrah Bastawala says:
DeepLearning can always be trusted with the best resources for this, he mentions some frameworks in this as well : 
https://www.deeplearning.ai/the-batch/agentic-design-patterns-part-5-multi-agent-collaboration/

Also I've read both Chatdev and Metagpt from the mentioned papers in this and definitely both have really good results of the multi-agent framework as well as really good results.

Another (a bit extensive ) but good resource to find anything regarding llms that keeps getting updated as well is: 
https://github.com/AGI-Edgerunners/LLM-Agents-Papers?tab=readme-ov-file#multi-agent-system

## TRANSCRIPT
0:01   
all right so welcome um how are you doing   
0:09   
today just just got a little late start here   
0:16   
oh yeah all right yeah so we'll go over a   
0:23   
few things today uh we had our eour meeting this week which is always good um   
0:31   
and we didn't have any cybernetics meeting or cognition Futures and we're holding off on our   
0:38   
open source meetings until later in the year or at least later in the   
0:45   
spring all right um so let's go and do   
0:50   
uh let's let's start with some papers I   
0:57   
guess yeah actually no let's start with uh a couple of slack   
1:04   
items so I I put out a darwind day post um on the synthetic Daisy blog this is   
1:11   
something I'm going to cover in Dil one later um on Monday this is a review of   
1:17   
Caron carcinization from the biology to computational models so carcinization is   
1:24   
about how things keep turning into crabs in evolution so if you go to the Marine   
1:30   
invertebrate clades you get these uh crab phenotypes that are convergently   
1:35   
evolved in the tree in the in the ca of green invertebrates and so a lot of people   
1:43   
have hypothesized why that is and so kind of talk about the mechanisms behind   
1:49   
carcinization some of the systematics and then also kind of the computational models people have used   
1:57   
ranging from Network Theory people have used Network NS to other types of models   
2:03   
like um genetic regulatory networks and   
2:08   
uh genotype to phenotype Ming so that's something to check   
2:16   
out in cognition Futures we've had a fair amount of activity U   
2:24   
recently uh we had let's see   
2:30   
I reup this paper reclaiming AI as a theoretical tool for cognitive   
2:35   
science I think this is a specially useful for some of the things we've been talking about in terms of large language   
2:42   
models and some other forms of AI that you know need to be reassessed   
2:49   
using cognitive science also think it's you know kind of   
2:54   
always good to go and revisit that cognitive science hexagon   
3:00   
on and recall where we're at and so that's that's   
3:06   
there um this is something that Morgan posted brains and where else mapping   
3:12   
theories of Consciousness to unconventional embodiment   
3:18   
um oh this one here which is uh from Nicole rust on the transmitter this is from reductionism to   
3:26   
dynamical systems how tube looks influence my thinking across 30 years of   
3:32   
Neuroscience um this is a paper I found on dimensions and mechanisms of memory   
3:37   
organization we've been talking about memory in our cybernetics meetings um we   
3:43   
haven't uh turned our attention to that in a couple weeks but um you know we   
3:48   
talked about how the file drawer model of memory retrieval and memory   
3:56   
organization how that you know their alternate forms of that and how that may not be sufficient to really describe   
4:03   
what happens in memory um and then this paper this was   
4:08   
actually I had pinged Morgan on this this is a paper on the aha so this is where you have these   
4:17   
insights that occur and you all of the sudden make sense of something and then there's some   
4:24   
organizational aspect to this where it's nonlinear so it's not like you um kind   
4:31   
of have this Insight after a certain amount of reflection and that's and that's   
4:38   
cumulative like you don't come up with the parts and then you actually get the answer it's like you suddenly get the   
4:44   
answer from you know after struggling with something for a while and then just kind of pops into your head so that's   
4:51   
what this is and this is using an active inference approach let's go to some papers   
4:59   
actually so this is a really interesting paper this is something that I think it came   
5:06   
out last June but it's something I think Morgan found and put in the   
5:11   
slack this is the baby view data set I resolution egocentric videos of infants   
5:18   
and young children's everyday experiences so this is um I don't think   
5:23   
he actually put the paper in but he put like a link to the group and then this is one of their papers   
5:30   
um so this is like you remember we were talking uh in earlier meetings last year   
5:39   
about   
5:44   
um about Linda Smith's work on U developmental psychology and   
5:51   
developmental cognitive science and developmental Ai and and one of the   
5:56   
things they did was put a GoPro camera on babies and they filmed the you know   
6:02   
the interactions with the world and so you find when you do that that this sort   
6:07   
of naturalistic view that babies are engaging with the world in a much   
6:13   
different way than adults and so there are a bunch of ways in which that's true and so this kind of   
6:21   
has a different uh well it has a data set that sort of I think adds to that so   
6:26   
these are high resolution egocentric videos meaning taken from the uh baby's point of view and and looking out onto   
6:33   
the world and yeah babies and young children I guess um so let's read the   
6:40   
abstract here uh the abstract reads human children far exceed modern machine   
6:46   
learning algorithms and their sample efficiency achieving high performance in key domains with much less data than   
6:53   
current models this data Gap is a key challenge both for building intelligent   
6:59   
artificial systems and for understanding human development egocentric video capturing   
7:05   
children's experience their training data is a key ingredient for comparison   
7:10   
of humans and models and for the development of algorithmic Innovations to bridge this Gap yet there are few   
7:18   
such data sets available and the ones that do exist are at low resolution have limited metadata   
7:26   
and represent only a small set of children's experiences so what they've done is they've   
7:31   
assembled the baby view data set which is this high resolution camera capture with a large   
7:38   
vertical field of view and geoscope accelerator accelerometer   
7:44   
data so they're able to record like you know head movements and a larger field   
7:50   
of view and higher resolution interactions so this is a 493 hour data   
7:56   
set including entric videos from children spanning 6 months to 5 years of   
8:01   
age so it's that sort of from infants to small children and both longitudinal   
8:07   
atome contexts and in a preschool environment we provide gold standard   
8:13   
annotations for the evaluation of speech transcription speaker diarization and   
8:18   
human pose estimation and evaluate models in each of these domains so again   
8:23   
this is where you're getting interactions voice you're getting your vocalizations you're getting interaction   
8:29   
with objects you're getting points of view and then the pose of the person and   
8:36   
that's all kind of put together we train self-supervised language and vision models and evaluate   
8:42   
their transfer to outof distribution tasks including syntactic structure learning object recognition depth   
8:50   
estimation and image segmentation although performance in each skills a data set size overall   
8:57   
performance is relatively lower than when models are trained on curated data sets especially in the visual domain our   
9:05   
data set stands as an open challenge for robust humanlike AI systems how can such systems achieve   
9:12   
human levels of success on the same scale and distribution of training data as humans that's a   
9:19   
question basically can we bridge that I guess sampling gap or data   
9:26   
Gap so the sampling efficiency is the key where I guess what they're saying is   
9:33   
that humans and maybe other animals take they sample the   
9:39   
world and they get much more out of it or they sample it at maybe a lower rate   
9:45   
but get much more out of that sample and so you have this data Gap you can throw   
9:51   
a lot of data at a model and it only achieves a certain level of proficiency   
9:56   
whereas in uh biological brains you get this uh you know lowered sampling but   
10:05   
you get more out of it I guess is the thing it just really depends on how you define sample I suppose because you know   
10:11   
we could say like well you know we have a certain number of discrete images but that's that's neither here nor there I   
10:18   
guess that's a good open question is what is sampling efficiency and what's the difference between like say a   
10:25   
biological organism like a human or another animal and like artificial   
10:30   
systems where we're feeding a data in discrete um chunks even when we have   
10:37   
continuous videos of naturalistic uh scenes we're always   
10:42   
giving it these discrete chunks of information and you know we're we don't   
10:48   
well they didn't even mention World models in this but this is something that you know also is a problem where   
10:56   
you know you have a world model or some sort of model that the sample is then compared to or   
11:02   
the sample is assembled in sort of this aggregate form and then compared to a   
11:07   
world yeah I mean it seems like yeah I mean I I love this it's funny because i'   
11:13   
uh forgotten who the authors actually were on this I I you know I suppose it's a good   
11:21   
thing that I just assumed that Josh tone Oh yeah I mean I guess good for Josh or   
11:30   
um uh uh but you know as as a former cognitive   
11:39   
development or developmental psychologist uh U you know this is one   
11:44   
of the the this is a real you know this what I think of as a real data set yeah   
11:49   
you know like like all these tar games these you know that's uh that's   
11:57   
that's not uh that has no real World application you know um so I I I just uh yeah you know   
12:07   
and and so how you're able to take that data and   
12:15   
then uh and then be able to   
12:20   
do you know planning or the kinds the kinds of things that that we're talking   
12:26   
about that you would use uh a world model   
12:33   
for uh you know this is this is the closest that we know to how   
12:40   
how what what babies do yeah yeah or or seem seem to be doing and and I mean the   
12:47   
only thing I would add to that is the um that I that I really like is of   
12:55   
course um that there also like learning to walk   
13:00   
like robot robot train I mean you know   
13:06   
as an example of um you know embodiment and and again   
13:12   
this this perhaps like continual   
13:18   
learning um emphasis where it's just like you   
13:24   
know there's one thing is doing all these things right at the same time   
13:29   
right and and is probably you know and is and is utilizing that you know so it's it's U   
13:40   
yeah I mean I I just like some of the   
13:47   
um robotic kind of the the the people doing   
13:55   
robot learning with this kind of emphasis I I I'm I'm not sure I could   
14:02   
think of like exactly the same you know someone who's doing it with this   
14:08   
you know kind of um scope or yeah but I like   
14:18   
that yeah so why don't we go back to the paper yeah so this   
14:23   
is uh so they talk about data availability being a major to progress   
14:30   
in understanding of the Gap in learning efficiency between machines and humans   
14:35   
to make effective comparisons between human and machine Learners we need to be able to evaluate models on data   
14:42   
comparable to what children see and hear during everyday learning experiences so this is this   
14:48   
multimodal data egocentric video recordings taken from a child's perspective provide a key window into   
14:54   
what children both see and hear as they learn about the world around them from their social partner so there's a social   
15:01   
learning aspect as well like with the egocentric View and then developmental   
15:06   
psychology studies using these types of videos uh to have together revealed that   
15:12   
the infant view is dramatically different from that of the adult which is Citation 8 and varies as children   
15:18   
learn to locomote on their own and interact actively with their object places and people round them 11 and 12   
15:24   
so if we go to the eight so uh reference eight is actually   
15:31   
reference seven is Linda Smith at all contributions of head mounted cameras   
15:37   
that's the paper the GoPro camera paper from the Journal of cognition and development and then this other paper by   
15:44   
Yoshida and Smith what what's in view for toddlers using a head camera to study visual experience that's from   
15:51   
infancy and then there's this other set of papers here where uh this by cret   
16:00   
Fran Shack and adol crawling and walking infants see the world differently that's   
16:05   
from Child Development and then 12 is long Sanchez cruss AAL and Frank   
16:13   
automated detections reveal social information and the changing infant view so that that's you know there there   
16:20   
are a lot of methods papers in here a lot of papers where they kind of get   
16:26   
to this uh you know this Rel relationship between the egocentric   
16:32   
View and the world and how it's   
16:37   
explored so this is a a description of the data set uh we address gaps in data   
16:44   
availability by collecting and analyzing a new set of Developmental entric videos the baby view data set the current paper   
16:52   
describes the first release of the data set but data collection is still ongoing   
16:57   
recordings were obtained using a high resolution headmount of camera from 6 months to 5 years both at home and   
17:04   
prechill settings uh there's like a home View and a a preschool view portion of portions   
17:11   
of the data set so you have like two different social contexts and activity   
17:17   
contexts um and you can use this accelerometer geoscope data that can be used to   
17:24   
estimate children's head motion and then there's also this ego single child data set which is using a   
17:32   
different camera and yeah they describe it below   
17:37   
so yeah so that they have the baby view data set and the ego single child data   
17:42   
set so this is the setup uh where you have the camera it's the entric frame   
17:49   
100 degree uh 100 degrees of uh View and then you   
17:56   
have these views here you can see and then this is the cumulative hours of   
18:02   
videos versus age so this is in months so it's it it's largely concentrated down at about maybe   
18:12   
three or four to 20 months maybe 25 months so that's you know pretty early   
18:17   
in development other than other than Josh Den bom the the you know I'm glad   
18:23   
Linda Linda Smith is highly represented at least in the in the references yeah   
18:29   
yeah when you first when you first mentioned the bber that was I I had a flash with Linda Smith but oh yeah yeah   
18:37   
uh um I I I think that was the certainly imitation learning was one   
18:45   
of the things that I was thinking of in terms of um kind of where you see robotics people doing this more you know   
18:53   
big big big literature in robotics of like yeah watch me do this and and then   
19:01   
mimic it um that that is that is cool   
19:09   
yeah and and yeah any anybody with with a kids   
19:16   
knows that's how that they are doing that and then they will they will try   
19:22   
and kind of try and do the same thing you're doing even if it's you know um in   
19:30   
play uh yeah this is just really a description of the data set they don't   
19:35   
really show a lot of uh interesting results I mean other than like how the   
19:41   
uh data set is organized okay so actually that brings   
19:48   
to mind another thing that we talked about this week or that was posted this   
19:56   
week and so that's in the data science ml Channel actually there are number of things in here that are interesting um   
20:04   
there's of course this understanding reasoning large language models which we'll come back to later um and that's   
20:12   
basically from uh Sebastian rashka substack there's this other archive   
20:18   
paper and then there are these papers on well actually this one is language   
20:24   
models Meets World models and agent models and this is from this year NPS   
20:29   
and this is like a session would you like to say more no I was just going to say like   
20:36   
like I it's um it's confusing because this person publishes it under their   
20:44   
Channel you know I I like I like anyway it's got good content but unfortunately   
20:51   
the videos lose their their metadata to some some degree yeah   
20:58   
yeah so this video language models Meets World models this was something that I   
21:04   
was looking at I was looking over the video it seems almost like the way they   
21:09   
approach World models is going back to cognitive science or back to like almost   
21:14   
like the kind of models we were working with 20 or 30 years ago where you have these conceptual models of the world or   
21:22   
you know you have these uh uh I guess internal representations of the world then that's kind of the and   
21:29   
it's kind of like um well they rediscovered cognitive science in a way but it's it's also that like a lot   
21:36   
of times you'll look up things like I was looking up the Chinese room problem   
21:43   
and large language models and it was really sparse the number of references I could find on that specific thing so   
21:50   
really wasn't so that's I mean you know that's a thing to consider is that there is this obvious connection between a lot   
21:57   
of AI models in cognitive science and I don't know if really people have kind of   
22:03   
exploited that Niche yet I could be wrong in that I'm not hitting the right communities but you   
22:10   
know I I certainly I can't remember   
22:16   
the the actual interview but that sounds like something that's   
22:22   
come up in like a machine learning Street Talk interview you yeah yeah with with   
22:31   
someone um I forget I think it's Tim Tim   
22:37   
something is the host there anyway it it sounds like something he could he he   
22:43   
might bring up um but again like this is why I liked   
22:48   
your your uh the the paper I I actually sent that to   
22:54   
someone the you know AI is   
23:00   
I forget the title but like is a a new way back to cognitive science or a new way to study cognitive science   
23:08   
um I think this came up uh it wasn't directly the the   
23:18   
PNA it was a conversation on social media   
23:23   
about you know this kind of rediscovery of cognitive   
23:29   
science uh uh rules or you know   
23:36   
architectures um and it was a student   
23:42   
that i' talked to before she's she started a a kind of   
23:48   
Neuroscience group and it come into the neurotech X   
23:54   
Community but it was interesting because I think she was a   
23:59   
she was a roboticist at George Tech you know she was coming from from   
24:05   
that undergrad experience of being in the robotics club and so I was I I was super   
24:12   
interested in just in terms of how robotics clubs work in   
24:21   
general right like like they are somewhat well funded by the by   
24:29   
universities they um they push a kind of interdis you know like a lot of   
24:37   
different I mean obviously they kind of engineering   
24:44   
um dominated but but that they can you know   
24:50   
they do bring in a kind of interdisciplinary group or or multiple background group and um and   
24:59   
you know and again I I was particularly interested just because for a lot of you   
25:05   
know for a lot of students that's a way being in the robotics Club is a way to   
25:10   
show off yeah uh uh you know and   
25:16   
and I just thought it was funny that um you know like like physics Majors like a   
25:24   
lot of these people end up going to Quant Finance   
25:30   
yeah um but but again that's you know that's great right like people who know   
25:37   
how to use differential equations and anger sort of thing and uh   
25:44   
anyway she she'd been comment she was just like wow it seems like AI is   
25:50   
actually a great way to to talk about cognitive science or to learn about   
25:56   
cognitive science so I I'd sent i' sent the that that paper that you posted as   
26:03   
well as the that um that Stanford paper with   
26:10   
mlen the the the pnas Nexus paper yeah you remember that the H what were they   
26:17   
doing but they were doing like humans on a task um they did kind of like a   
26:24   
Mechanical Turk right uh um raiding   
26:30   
something anyway they they they were they were testing humans and they were testing   
26:36   
ANS on the same same tasks and and finding where where you know your your   
26:44   
cognitive kind of inductive biases LED you astray oh that's right they they   
26:50   
were they were changing they were changing the content of complex   
26:56   
sentences uh into like nonsense using nonsense words   
27:02   
versus yeah right   
27:07   
right and yeah it it it's it can be right I mean again it's   
27:15   
like as long as you're not um as long as you're not giving lm's   
27:23   
theory of Mind tests having them do well and then deciding   
27:28   
that they're   
27:35   
alive and so I I forget I I don't know what that archive paper was but I don't   
27:40   
think it was this but I did post um a paper or it was like a substack or   
27:48   
something um a post about just   
27:54   
lm's lm's used the or you know fall into the   
28:00   
same category as the um   
28:06   
uh what's the person who's like U The Mentalist tricks so so like like   
28:15   
like I I I can I can predict what you're thinking kind of   
28:23   
things it like you fall into the same traps right a person's trying to trick   
28:30   
you yeah yeah and and they were just trying to get at the point that that that it is an   
28:37   
easy it's kind of like an easy self trap when you're   
28:44   
uh interacting with the ls that I that I again is the is the only danger with   
28:52   
this you know using using them for for cognitive science right   
29:02   
yeah all right so yeah that uh that was the language models Meets World models   
29:09   
and so I think there's a lot to say about like World models and and like maybe language models or World models in   
29:15   
general and what exactly they are in that video they kind of have give it a very cognitive Science cast like   
29:22   
basically it's instead of just you know having all the these data and then   
29:27   
looking at like the sampling rate or sampling efficiency you have these   
29:33   
models that internal models to the agent that are used to sort of uh get these   
29:40   
out of distribution answers so it's not just the data coming in and you're not inferring from the data so much it's   
29:47   
that you have this model that you operate on and then the data has to fit   
29:52   
the model and of course you of course run the risk of just kind of get having a a bad model or an incomplete model   
30:00   
that sometimes if you get data that doesn't fit into the model then the agent is flx and the performance suffers   
30:07   
so you know I think there's like uh something to be said about world models being these internal models of cognition   
30:15   
these overarching models of like the world but then there's also this aspect   
30:20   
of you know how do you acquire something like this you can of course engineer   
30:27   
something uh top down but then you know what is it that maybe you you extract things from   
30:34   
or maybe the uh agent extract things from the world that isn't known to the   
30:40   
topown implementor of the model that is you know you might   
30:45   
have uh something in the world in some video that's captured That You Don't See   
30:52   
or there's a set of relationships that aren't apparent to the person creating the the representation and then putting   
30:58   
it in the agent you're talking about artificial systems so it's you know it's   
31:04   
one of these things where I think there's this out of distribution aspect to uh to World models in any case uh   
31:12   
then I think Morgan added a few more links here there's the how large language models conquered the ark   
31:19   
prize uh what was that oh that was the machine learning Street talk yeah I mean   
31:25   
you know as well as as this   
31:32   
this you know recent emphasis on um   
31:38   
smaller models can do better yeah you know and and so this this you   
31:46   
know deep seek craze if you will that that has set off a a bunch of of related   
31:56   
papers from different groups um that uh you know but yeah like   
32:03   
like Arc prise being a great example of you know in a sense cognitive science   
32:13   
becoming um greater emphasis or certainly   
32:19   
thinking about your what your intelligence test is   
32:26   
yeah is testing and and so yeah super   
32:31   
interesting super you know as well as what other   
32:38   
benchmarks that you know because like Arc prize was kind of unique at when   
32:46   
Chalet came out with it but I think you know deep   
32:52   
seek and getting getting to De seek has actually created a number of other you   
33:01   
know uh benchmarks that that are are you know growing that space or   
33:09   
being yeah yeah alth although interestingly or but   
33:15   
not surprisingly it's still super math focused oh yeah yeah   
33:24   
definitely yeah yeah so we have uh the paper here this archive paper which is   
33:30   
automated capability Discovery by Model S exploration that's a paper of Jeff   
33:35   
Clon on it and yeah you know it's still seems like the the same people are doing   
33:43   
all the heavy lifting yeah yeah but but you know but great great stuff you know   
33:50   
and and again like emphasizing this this   
33:59   
um I mean I I I I don't want to give them like deep seek all the credit here   
34:05   
because you know because I think um I've been rewatching a bunch of old like Deep   
34:12   
Mind videos um but you know just this this   
34:19   
this discovery if you will that we should we should stop trying to think we   
34:27   
know how this works yeah we should and we should let the models we should let   
34:33   
the models figure it out yeah with these with these you know   
34:39   
reinforcement learning um um self   
34:44   
self-learning um kind of strategies and and that you know it's it's   
34:53   
um uh I love the I I you know watching   
34:58   
too many videos but it's just like like uh I name it was I can't remember who it   
35:05   
was talking about this I think maybe it was David silver but um but they were   
35:12   
just saying he was saying that if you visualize Alpha   
35:20   
fold's kind of progress just how unnatural it is to the   
35:28   
people who were doing protein folding research before that yeah and   
35:36   
and um and yet in hindsight how   
35:41   
important they thought it was that it was doing all these   
35:47   
unnatural things yeah for for the   
35:54   
proteins overall stability at the end which is you know again it's one of   
36:01   
these things where it's just like somehow the models can see the   
36:06   
forest and not get caught up in the trees you   
36:12   
know yeah without seeing the forest yeah   
36:17   
you I don't know if the metaphor helps at all but it was interesting it was   
36:24   
interesting yeah so uh um and then I I dropped a couple   
36:31   
researchers profiles in who   
36:38   
um yeah so um uh kungl is let me just remember here okay   
36:47   
yeah so so he's he's Jeff Glenn's student but it's it's interesting to see   
36:54   
where he's coming from and what you know um you know like like look he was at um   
37:02   
he was at Sakana for instance yeah you   
37:08   
know again and you know it's like it's like where are the places that he's been   
37:16   
and what are the you know what are what are kind of   
37:22   
like the eye clear workshops that he's attending yeah yeah   
37:29   
um so so like like you know he's got some really interesting stuff um and uh   
37:37   
and obviously some some you know GitHub repos and papers and then Logan's the   
37:44   
next one uh yeah Logan so and what's cool is   
37:53   
that Logan's um Logan and I met as a part of neurom   
38:00   
match okay like like and it was Nur match in its pure neurom match   
38:09   
form in that like it it was just a like let's put eight random people in a   
38:19   
zoom okay and yeah and have them and have them introduce themselves yeah   
38:25   
yeah um but you know he was describing his work and I was just like I was like   
38:31   
oh you know that sounds like you're you know World modeling right and he was you know he   
38:39   
said yeah yeah exactly and and you know this was pre these top two   
38:47   
papers so um anyway I was I was you   
38:52   
know he would be someone I think I'd love to um have come come and talk you   
38:58   
know see like I don't believe there's any recordings of him talking about his work oh yeah that would be great   
39:06   
yeah you know but I really like this this agent agent World modeling Benchmark yeah you know obviously yeah   
39:14   
of course and and then you know that he might be doing theory of mind um without   
39:24   
um without talking about you know them being conscious   
39:34   
right but but a nice a nice   
39:40   
um a nice merger yeah yeah of kind of   
39:45   
cognitive science of of AI you know yeah yeah a lot of well yeah cognitive   
39:52   
science he has some good Neuroscience papers here too absolutely absolutely I I I think   
39:59   
he's coming from a um or certainly he he seems to be postto in a lab which is   
40:04   
very neuro AI Focus yeah so they're definitely thinking about yeah you know   
40:14   
Neuroscience um but but uh but I I was   
40:19   
particularly taken by the the kind of cognitive science of of his his AI work   
40:27   
yeah yeah definitely yeah that's great uh thanks   
40:32   
for that okay   
40:38   
um let's see yeah so that's data science ML and then we had some things in Dev   
40:44   
Miro AI that you know we had this is the post on where Morgan link to this neuro   
40:52   
AI Lab at Stanford and that's where they have the baby view data set paper um oh   
40:58   
is that the that is yeah I think that's what it is it's the sled here well   
41:06   
so because I think I mean that's that's that's super interesting but I think   
41:12   
this is n lab I think is Logan's current lab oh okay well that   
41:20   
great yeah I think it might be Dan   
41:29   
yeah I was I was just particularly like again like   
41:34   
um I looked at you know I was like okay so you know given his background you   
41:43   
know what's the what's the lab that he's moved to yeah and go to the research tab   
41:51   
there now you're right I see I see baby I see baby there yeah um but uh um you   
41:59   
know when I look at this when I look at these um kind of research goals yeah   
42:06   
they don't they don't actually they don't really make me think like this is   
42:12   
you know the these are interesting directions yeah I mean you know what I   
42:18   
mean like like these sounds like like Neuroscience goals right   
42:25   
right traditional Neuroscience goals um   
42:30   
uh Al although the last being you know where where it seems like   
42:36   
they're actually doing all the the real play yeah yeah but you know I think it   
42:43   
also speaks to just how many people are on that that baby beew paper and and you   
42:49   
know I forget I mean I want to say Michael Franken is   
42:57   
I I would bet that he's got a lot of appointments   
43:04   
yeah yeah yeah so yeah that's that's the then uh this   
43:11   
is so so this is the the guy at stability AI okay who was brought on as   
43:21   
like so you know stability AI one one of   
43:27   
the kind of pioneering um what do we want to call it diffusion   
43:33   
model generative model yeah yeah com companies right yeah where where it's   
43:40   
like like before chat GPT there was you know this this image generator I   
43:49   
guess is what they were known for yeah and um so the interesting thing was   
43:56   
that that this guy came onto stability as officially their head of neur Imaging   
44:05   
okay I I forget exactly what his title is but it was something   
44:11   
like something like that and um and he's got   
44:17   
he ran and I I guess still runs um a Discord   
44:23   
group um uh I know if I'm gonna be able to find it right   
44:30   
now um uh is   
44:38   
it um sorry I just I just checked Med Arc   
44:43   
and I just found um usin yeah um yeah yeah I think it's I think   
44:50   
it's medar um is the um um is the group and oh yeah   
45:01   
sorry it's right there right so um met AR's the third of these groups but it it   
45:09   
was it was there that they did a you know theyve got some papers   
45:16   
out um you know it's kind of like a self-organized community yeah of of um   
45:23   
of researchers and um neuroscientist   
45:28   
where um they came together to work on you know various uh simulations as well   
45:35   
as data analysis and one of those being I think it's called Mind's Eye okay   
45:41   
which was very much a um here's the data set of a person looking at pictures or   
45:48   
movies or something like that and and as you   
45:53   
know restoring what the the movie was from the brain activity oh yeah I've   
46:00   
heard of this yeah you know right um so I I actually posted this   
46:08   
across a number of of other groups too um just because   
46:17   
uh um well you know like Celsius and and NX   
46:25   
like I I would certainly hope we could achieve the same kinds of of   
46:35   
um have have a lot of same goals right and you know and again it's it's um he   
46:42   
he really did have a unique perspective on   
46:49   
um yeah working with open science communities okay yeah you know although   
46:56   
seems to have left stability   
47:02   
stability and and just you know like I don't think it needs to be I mean   
47:09   
stability had a whole bunch of issues oh yeah yeah that's what I understand yeah you know and and and you know unlike   
47:17   
open AI um you know it's uh I I I don't   
47:24   
know what its current status is but I I assume it's been Contracting yeah and   
47:29   
and I know that its founder um where did   
47:35   
he I mean he moved to   
47:42   
Microsoft some anyway I mean you know the the the   
47:49   
drama of of all of these these big you know so-called AI   
48:00   
um I don't I don't know what the right term is innovators that doesn't sound   
48:06   
right the these these you know corporate AI people like it's not really important   
48:13   
but um uh but it is interesting you know like like there's a bunch of   
48:22   
um there's a bunch of people a bunch of interesting people went through AI   
48:27   
because it had so much money and it was bringing in so many people right so the um David H was was   
48:35   
uh you know brought in as as a very important personal stability yeah for   
48:41   
instance yeah you know I I think he left within like a   
48:48   
year or something okay so yeah back to the dev   
48:55   
Maro AI Channel this is uh the software crisis yeah yeah so what is this uh this   
49:04   
is what I was talking about in terms of you know it's this is this is my my   
49:11   
issue with how to categorize these papers which is my own personal   
49:17   
slack issue yeah I know you know again   
49:23   
like all of these should really be in a dock with tags   
49:28   
so that they can be in multiple without it feeling like you're filling up a bunch of them anyway but this is this is   
49:35   
what I was talking about in terms of llms replicate the psychics   
49:40   
con okay you know and   
49:46   
and that that this is so often what people are falling into or you know that   
49:55   
um when they when they seem to be doing something you know quote surprising to   
50:01   
someone right it's it's as this author I think points out   
50:08   
you should you should think of this as a great teaching tool about how   
50:15   
psychics grift yeah yeah not not about how amazing alons are yeah so there's a   
50:23   
lesson to be learned here it's just not the lesson we want to learn like is yeah or you know U yeah and then uh this is   
50:32   
uh a post from LinkedIn on the test optimized brain and how Mouse and   
50:37   
primate visual cortex are unified by the same SSL objective I don't know what that means let me let me I'll try and   
50:45   
extract the uh okay   
50:51   
um um okay yeah yeah so this is this is a   
50:58   
lecture um that is on representation and   
51:03   
generation in Nur science and Ai and let   
51:11   
me I can give you I I'll just put it in the I'll put a   
51:17   
link to this box here so it's actually a PDF   
51:27   
um but it it did it did um   
51:35   
um it seemed like a nice you know a nice kind of review of of the   
51:46   
um um how kind of neural neural data and neural   
51:55   
processing um are kind of you see the same things in neural   
52:01   
networks and neural architectures okay neural network   
52:07   
architectures yeah so let's see if they   
52:12   
have this is a categorization performance versus it explained variance   
52:18   
is there an underlying principle this from yans and Hong in 2014   
52:24   
pnas this is showing kind of like these different networks uh model   
52:31   
architectures where the deeper networks sort of go out in this circle yeah yeah   
52:40   
and by the way this is again the same guy this is neuro AI   
52:47   
lab yeah yeah uh and then yeah so you formulate   
52:52   
comprehensive model classes choose challenging e eth locally valid tasks so   
52:58   
word recognition localization categorization are in this space so you have the cnns and and sort of the space   
53:07   
that they inhabit and then you have these different types of tasks within   
53:13   
that space and then Implement generic learning rules or radiate descent so   
53:19   
you're go you're converging upon different types of tasks or different types of tasks you converge Upon A Space   
53:25   
in this and so I guess that means that like there's certain models that are   
53:31   
optimized for these things like for different tasks or   
53:37   
yeah and and and this does you know and this is remarkably neuro right yeah like   
53:44   
like it's like so when you put it together with those other papers just   
53:49   
like oh yeah like this is exactly what I think you would have been working on yeah as opposed as opposed to these   
53:55   
other cool things that you're also doing too which is which is good yeah so yeah   
54:00   
this is exactly what you're saying where then these different models or these different parts of the space map to   
54:07   
different parts of the brain or different streams so this localization   
54:13   
it U uh sort of the convergence to localization in the space of   
54:18   
architecture classes maps to the ventral stream in the visual system so like these parts of the brain are specialized   
54:25   
for this thing and then that's like consistent with a model architecture that is convergent for the sort of   
54:32   
localization task so you can do localization you converge upon this type of model basically yeah yeah yeah okay   
54:41   
it's it's cool right yeah it is it is yeah it's definitely and a way of   
54:47   
thinking I I guess when they say architecture classes they mean like different configurations of an   
54:53   
architecture or different weights or what do they I guess maybe the well the networks get   
54:59   
deeper as you go out in the in the sphere or in the circle so like these architecture classes are sort of   
55:06   
categorized by their depth and it's certainly it's a   
55:12   
dimension yeah yeah right um   
55:18   
um yeah yeah it's it's I I I would want   
55:24   
to dig in more you know I I just thought it was uh it was you know again these are kind of just things I stumble across   
55:31   
yeah I know it's this is good and um you know it makes me want to   
55:36   
go and see what this whole lecture series is yeah like   
55:44   
like yeah yeah yeah this is definitely interesting yeah yeah it would be nice   
55:52   
you know again like neuro AI not well defined right you   
55:59   
know the Patrick Mano um paper   
56:05   
uh that covers you know that   
56:10   
covers nuro AI um although I think he says for AI safety or something like   
56:17   
that right um you know he he he shows you how many different things you could   
56:23   
actually be talking about oh yeah whereas whereas this seems like a really   
56:28   
you know well-rounded Neuroscience way of and that that I think is actually   
56:35   
really useful you know I mean in terms of of organizing and motivating   
56:41   
Neuroscience research you know yeah yeah I think this is and then if we   
56:47   
go down more you can actually get kind of these uh sort of you can   
56:53   
figure out the gradient descent rules for this and then uh L function the data set the   
57:01   
architecture class um and then yeah so that's   
57:07   
interesting as well as like I like it in terms of um you know kind of cognitive science   
57:14   
ideas too yeah right you know I mean you know thinking about yeah yeah just just   
57:20   
think thinking about categorization that way you know um is is certainly   
57:26   
um you know again like I could I could dig around and find some some   
57:33   
old cognitive science where it's looking very much like like they're using that   
57:39   
kind of metaphor yeah you know with with very different data you know basically   
57:46   
with behavioral data and and um yeah so I I love the   
57:53   
overlap with yeah just with the the cognitive science um Nur AI you know and   
58:00   
and Logan Logan seems to have like taken all of these threads and and made a   
58:08   
wonderful um you know video game agent that's embodying all of this oh   
58:14   
yeah that's that's cool yeah yeah that' be definitely be nice to hear from him   
58:20   
yeah yeah so so I I just thought you know like like if I get you know and if   
58:27   
I say like hey in March it would be great if you could come and and you know   
58:34   
give a talk that we could record yeah um would he be down for that right   
58:40   
that'd be good yeah yeah yeah let's let's uh figure the the logistics of   
58:45   
that out yeah yeah you know and again I I love the fact that the only reason I   
58:52   
know this person is because of n right   
58:57   
so yeah and then the just there's this other link Han AI oh um yeah remind me   
59:04   
what that um that is William Han PhD uh looks like yeah   
59:10   
[Music] so yeah I mean I I definitely love the   
59:16   
artificial immune systems yeah um I I I think you   
59:21   
know again I I think I kind of used Dev nuro AI   
59:27   
to as a as like a catchall for something   
59:32   
that's super multidisiplinary yeah and I just don't know what else to   
59:39   
do with it well I think we should uh think like   
59:44   
broadly about neuro AI or like what we're doing in our flavor of it so I I I   
59:50   
absolutely think you know like artificial immune systems kind of fit into that because we're just interested   
59:56   
did in all manner of like development and like how to build agents that are biologically inspired yeah yeah and and   
1:00:05   
um uh James Glazier speaking of you know   
1:00:13   
um exactly along these lines let me let me like actually just grab this because   
1:00:20   
it's it is so perfect um if I think   
1:00:27   
I re posted   
1:00:32   
it um uh yeah here it is so current   
1:00:40   
research in toxicology   
1:00:45   
um uh and I'm just gonna put this I'll put   
1:00:51   
it in their AI dead n AI again yeah   
1:00:58   
[Music] um um I'm not going to install box okay   
1:01:04   
sorry Slack's asking me I know I know well I   
1:01:11   
mean anyway there you go okay um just just a   
1:01:17   
cool um yeah it's it's I love that it's   
1:01:24   
coming I I love that it's in toxicology right you know um but they you know it's   
1:01:34   
a wonderful like um yeah multidisciplinary   
1:01:42   
work that is is what what you would expect from   
1:01:49   
development right and um   
1:01:57   
so I I I really want to pass this on to Thomas Harden because you know he's the   
1:02:03   
organoids intelligence guy right but yeah like that's totally not his field   
1:02:10   
in the sense that like he's a toxicologist and and you know if   
1:02:16   
anything he he he yeah so can can we link or organoids together with with   
1:02:24   
this kind of in silic modeling more yeah yeah so this is   
1:02:33   
something that models neural tube closure defects and so this is where they develop a dynamic system agent   
1:02:39   
based model of neural tube closure this is melean systems so they're using cell   
1:02:45   
signaling and biomechanics and we've talked about some of those type of models in D.A one um and how you know we   
1:02:52   
can use those we can look at the biomechanics the cell signaling and then you know other things   
1:02:59   
on top of that uh predict both the nature and probability of Def effects from genetic   
1:03:05   
perturbations the model of lines of biological phenotypes uh which we observe and   
1:03:11   
existing research and then there's this uh sort of assessment of Developmental   
1:03:17   
toxicity that's probably they had to put that in to get into the journal but it it's it's getting yeah   
1:03:25   
yeah oh this is is a better figure here okay so this is uh where they have this   
1:03:30   
sort of characterization of the embryo and they have this surface   
1:03:37   
ectoderm neuro Prest neuroectoderm so they Define the tissues down here they   
1:03:42   
have from t0 hours to 50 hours and they're looking at these different   
1:03:48   
things that are being expressed so um and they show kind of where these things are being expressed um um you see this   
1:03:56   
again here for well so this is for Sonic   
1:04:01   
Hedgehog etch GOI uh bmp4   
1:04:07   
EMP Noggin and Zi and then this is uh wi   
1:04:13   
uh ft fzd packs and snai so this is kind of   
1:04:19   
showing these different um things here yeah this is a nice paper   
1:04:25   
looks like they've characterize this and then this is their Gene regulatory Network for these uh gen   
1:04:32   
that they're looking at so um yeah so it's kind of hard to see   
1:04:38   
the kind of the elements but you basically have these different   
1:04:43   
components neural crest surface ectoderm and so forth um and then   
1:04:51   
in this yeah so they have more of that I'm looking for an output of the model   
1:04:57   
but I don't see it yeah then they have equations in here   
1:05:02   
that so yeah basically a gene regulatory Network um and then they they have some   
1:05:08   
outputs yeah yeah I mean it's it's it's you know it's exactly what you'd expect   
1:05:15   
from a kind of James Glazier yeah yeah great James Glazer Associated group and   
1:05:23   
um uh but I I love you know that it this   
1:05:28   
is one of the kind of the major milestones in embryo   
1:05:36   
development right so so it's got this um   
1:05:41   
yeah it's it's a it's a great start and   
1:05:47   
you know um there's not enough of   
1:05:52   
certainly agent based models that that are um yeah that that focused in kind of   
1:05:59   
brain Mel yeah I think that's nice that there's this uh agent based model that   
1:06:05   
has that fits into sort of a gene regulatory Network right right so um   
1:06:12   
anyway you know this this came up in the context of of artificial immune systems   
1:06:19   
right right and and I I I thought was a i misremembered   
1:06:28   
in my head that there was actually more of an immune story there okay yeah um   
1:06:34   
and and maybe there is in anyway but it it doesn't look like it   
1:06:40   
but but Hans Hans hans's work is interesting in that regard yeah   
1:06:46   
yeah and and you know James Glazier runs a what's it called   
1:06:56   
um it's like in IM grip or something it's like a   
1:07:02   
completely nonsense acronym um uh th Thursdays unfortunately I got a   
1:07:09   
meeting at the same time um I got two there's there's two meetings there's two   
1:07:15   
or three meetings all at noon on Thursday my time yeah and James   
1:07:22   
glazier's one of them and and the Focus um on immune system I I think I'm   
1:07:29   
Mis misremembering with with like his speaker this week for that who who   
1:07:35   
immune system focused yeah digital twin stuff oh okay but but but like immune   
1:07:45   
system I think I think immunity is the is the weekly meetings   
1:07:51   
theme you know yeah because I I think it started as a   
1:07:57   
pandemic um focus like like it might even be viral   
1:08:06   
epidemiology okay   
1:08:14   
yeah it looks like Sara is here   
1:08:20   
Sara um yeah so what don't we move on to another set of papers   
1:08:26   
here um I actually I wanted to talk about this one here been talking about   
1:08:31   
cognitive science and nuro AI this is actually um topic a topics and com   
1:08:38   
cognitive science paper on team cognition research and how that's transforming cognitive science this is   
1:08:45   
Michael Spidey from uh UC mered on this paper and uh this is a topics in   
1:08:52   
cognitive science paper this is part of this series on the dynamical hypothesis   
1:08:59   
and thinking about like the sort of the legacy of it so the dynamical hypothesis   
1:09:06   
is where we're thinking about the brain as a complex system and how that differs from some of the other ways in which   
1:09:12   
we've characterized the the brain uh you know as opposed to say something like a   
1:09:19   
computer and so Luis FLL and Vincente Raja are topic editors Vincente Raja of   
1:09:25   
course is we've talked about some of his work in I think it's either the cybernetics   
1:09:31   
group or the cognitive cognition Futures group then Lis favella has done a lot of work on dynamical cognition as   
1:09:39   
well uh this is Michael J Spidey um and so this is uh so there uh   
1:09:47   
Tim van gelder who was a connectionist uh who was also a philosopher so this is   
1:09:54   
connectionism this is back in the 1990s when he was publishing some of his Landmark works on   
1:10:00   
dynamical cognitive science um so he says Tim van gelder a connectionism   
1:10:07   
trained philosopher with the leeway to enjoy a 30,000 foot view of science was   
1:10:12   
perhaps in a special position to make his contribution of the dynamical hypothesis and cognitive science is   
1:10:18   
before the turn of the West Century and that's kind of a interesting way to put the 1990s but um this special issue   
1:10:26   
commemorates that Clarion col made almost 30 years ago his behavior on brain Sciences paper his journal   
1:10:32   
philosophy paper and has edit a volume with Robert Port so the port and Van gelder paper mind his motion but it's   
1:10:40   
actually an edited volume uh from 1995 were inspirational for many of us   
1:10:46   
uh together they've been cited more than a few thousand times for some that inspiration could manifest is simply   
1:10:52   
shifting away from digital computation a unique form of neural computation as   
1:10:58   
what constitutes cognition so this is where you know we think of the computer   
1:11:03   
or we think of the brain as a computer we think about digital computation and you know we we did a   
1:11:10   
whole series on this in 22 and 23 2022 and 2023 where we talked about   
1:11:18   
computation in the brain physical computation and some of the other aspects of that analogy and so people   
1:11:25   
have really kind of you know a lot of people in AI drilled down on this idea   
1:11:32   
of the brain being digital computation and of course there are other forms of computation such as physical   
1:11:38   
computation and indeed neural computation is Define in the neuroc   
1:11:43   
computation literature and so what they're arguing here is that there's   
1:11:49   
this uh sort of digital computation where you make that analogy explicit   
1:11:54   
with all the sort of the problems that it sort of brings with it or you think   
1:12:00   
of it as a form of computation that is unique to the brain and so this is of   
1:12:05   
course uh pikanini is one of the people who talks about this um we talked about   
1:12:11   
his work on physical computation um as well so this is uh one   
1:12:17   
one aspect for others it could trigger a transition to a dynamical systems approach that changes his nonlinear   
1:12:24   
trajectories and L istic State space so this is the Almond paper from 2009 so   
1:12:29   
again you know there are different ways you can think about the brain is like something that is computational but not   
1:12:35   
digitally computational you also have this aspect of dynamical systems where   
1:12:41   
you think about like these trajectories being produced and you know we could do this for Linguistics we could do this   
1:12:47   
for vision we could do this for other areas still for others it could transport one all the way to a complex   
1:12:53   
systems approach that I was multi organisms to engage in one shared cognition and that's   
1:12:59   
spy um this brief commentary focuses on the special issue articles   
1:13:05   
of molindo landfair amazine and amazine and   
1:13:10   
Van einhoven Wilshire helus G so this is   
1:13:16   
kind of talking about these the special issue and kind of talking about some of these aspects rather than comment on   
1:13:23   
them one at a time like a Serial process in sequential might do I will Instead try   
1:13:29   
to address the two articles in interlop fashion so these two articles already   
1:13:34   
dovetail each other uh the groundbreaking team cognition work of Jamie Gorman uh naturally figures   
1:13:42   
prominently in both uh and so talking about the performance of teams and the shared cognition that emerges among them   
1:13:49   
cannot be fully understood without embracing a dynamical systems perspective and placing a f focus on the   
1:13:55   
coordination Dynamics or multiple interconnected sub components of the system so coordination Dynamics refers   
1:14:03   
the sort of uh dynamical systems approach to uh coordinating different   
1:14:08   
parts of the brain or it could be coordinating different people with brains doing things and so it has a sort   
1:14:15   
of multiscale aspect to it uh in order to account for their observed phenomena these fields were   
1:14:22   
forced to take on dynamical systems accounts where the important phenomena can only be explained as resulting from   
1:14:28   
interdependent nonlinear interactions among multiple factors um there is a   
1:14:33   
lesson in there for cognitive scientists allow me to be a little more pointed with that observation it is possible   
1:14:40   
that we as cognitive scientists should be slightly embarrassed that our field has taken so long to catch up to those   
1:14:46   
dynamical systems insights so just kind of going through you know because   
1:14:51   
dynamical systems of course has been around for quite a while and still not really in the mainstream of cognitive   
1:14:58   
science or Neuroscience so thinking about like you know how that fits   
1:15:04   
into what people are doing the kinds of questions that are asked and so forth so   
1:15:10   
this kind of goes through some aspects of how sort of dynamical systems fits   
1:15:16   
into cognitive science it you know it's really interesting that some of this is   
1:15:21   
and this paper is kind of like almost like it it reads kind of like a stream of Consciousness sort of thing but um   
1:15:29   
and so it just talks about some of the ways people have applied uh dynamical systems   
1:15:36   
analysis um so I guess let's see if I can find a good example of what they're   
1:15:43   
talking about here so they talk about data analysis and data collection and   
1:15:48   
how one might use that as a way to you know or use dynamical systems analysis   
1:15:54   
to gain Insight from the data um so here's a a piece here together   
1:16:03   
gulan and einhoven these two papers that he's talking about in a special issue   
1:16:09   
are using these multiple densely sampled measures as part of how they call for a broader conception of what we refer to   
1:16:15   
as a cognitive agent crucially it need not be a single singular organism   
1:16:20   
bounded by its skin it could be two or more of them temporarily functioning as one cognitive agent for this allow me to   
1:16:27   
draw another analogy beer analyzes the statistical patterns of gliders in The Game of Life this is Randle beer he's   
1:16:35   
done a lot of things on artificial life uh looking at these gliders which are these sort of epip phenomenal agents in   
1:16:43   
The Game of Life and finds that while these Arrowhead shaped emergent patterns appear independent and selfmotivated as   
1:16:51   
they propagate across the lattice they are in fact ritually interdependent with their surroundings and the grid his   
1:16:58   
analysis shows that this complex interdependence makes it difficult to treat the glider as if it were a   
1:17:04   
singular autonomous cognitive agent all by itself is it possible to see mure of   
1:17:09   
people when they engage in team cognition so he's kind of considering Cog dynamical systems approaches to   
1:17:17   
cognition both in the context of how that kind of reinterprets cognitive science but also thinking about this in   
1:17:24   
terms of team ition and sort of the situatedness um that that you have um   
1:17:32   
that kind of emerges from this kind of analysis so this is uh talking about   
1:17:38   
ecological validity and you know kind of giving that is sort of this embeddedness   
1:17:44   
is sort of the psychological validity meaning that it makes your experiments or your analysis sort of more   
1:17:52   
ecologically sound that the sort of the setting of The Experiment or the setting of The observation is more embedded in   
1:17:59   
in sort of a real um environment and so this is kind   
1:18:05   
of this is interesting an interesting point for uh you know AI experiments   
1:18:11   
that we don't really have a good fix on what constitutes ecological validity   
1:18:16   
that is if we talk about intelligence you know is there an ecologically valid way to talk about you know artificial   
1:18:23   
intelligence or agent based intelligence   
1:18:28   
um so this part here by employing more ecologically valid shared tasks just   
1:18:34   
such as unscripted interactive conversation open-ended joint tasks and   
1:18:39   
coordination during game playay the field of cognitive science is better able to apply its findings to the real   
1:18:45   
world what is more some of the Bedrock findings and cognitive science melt away   
1:18:50   
when the test becomes more ecologically valid for example rather than treating language use as a discrete turn-taking   
1:18:57   
process where at each turn a message is delivered by a sender and acquired by a   
1:19:03   
receiver real world language is being better understood as a complex process involving interruptions overlapping   
1:19:10   
speech and ruled with errors misunderstandings and multiple methods of interactive repair so in this case   
1:19:17   
he's explicitly sort of taking on the information theoretic view of Shannon   
1:19:22   
and Weaver this idea that you have like you know the basically the the basis of   
1:19:28   
information Theory which is that you have this channel uh where there's a sender and a receiver and an information   
1:19:35   
channel that has discrete messages in it and you can make this characterization of the message so that's very much the   
1:19:43   
uh you know the basis for the cybernetic view of cognition where you have this uh   
1:19:49   
Communication channel that is open and you can analyze it and so he's arguing   
1:19:55   
is that in the sort of more ecologically valid approach you have this sort of   
1:20:01   
complex process where you have all these attributes of speech that are not you know kind of   
1:20:08   
idealized uh and he kind of talks about some of these and this is dingan and   
1:20:13   
Enfield 2023 so there's this view of you know these two competing views of uh   
1:20:20   
analyzing language you have the information theoretic view of language the cybernetic view of cognition and   
1:20:27   
then you have this other View and I guess this is supposed to be a dynamical view but that's you know that's just   
1:20:33   
kind of this foil uh comparison and I think it's interesting in the context of   
1:20:38   
you know how we analyze AI agents how we Analyze This difference between   
1:20:45   
biological agents and artificial agents and having these kind of distinctions of what you know how we actually analyze   
1:20:53   
these behaviors and and how we build our models so uh Brown Schmidt and tannan   
1:21:00   
house in 2008 found that this interactive co-creation of Common Ground developed over the course of natural and   
1:21:06   
scripted bidirectional conversation between two people was often sufficient   
1:21:11   
to eliminate some of the temp temporary ambigu ambiguity effects in word   
1:21:17   
recognition and syn tactive processing that have been observed in the scripted unidirectional language comprehension   
1:21:23   
circumstances so I guess all this means is that it's like it just resolves some   
1:21:28   
of the problems you know some of the LA things that are lacking from the information theoretic   
1:21:35   
view um so yeah in dynamical systems you kind of get away from these discrete   
1:21:41   
symbolic computational approaches and you kind of think about   
1:21:47   
uh you know more what's going on in the brain uh and yeah so you can in   
1:21:55   
biological cognitive agents you cannot instantly teleport from one representation to the next the way a   
1:22:01   
digital computer basically does their cognitive trajectories have to spend some time traveling through the   
1:22:07   
continuous State space in between these symbol like regions so this is again where you have instead of having these   
1:22:15   
discrete States in and discrete representations that you can switch back   
1:22:20   
and forth between you have to have the sort of trajectory that goes between representations so you have maybe   
1:22:28   
representation a and representation B and then you have this path between them so there's this transition between a and   
1:22:34   
b and it's continuous you know and of course you're analyzing um behavior in the brain in a   
1:22:41   
continuous way so that makes sense that you have this sort of and it's not you know a continual I guess it could be   
1:22:47   
looked a continual but this idea of you know these discrete measurements and these discrete models versus continuous   
1:22:54   
mod models in continuous measures so this is one thing that van   
1:23:01   
gelder has bestowed upon the field an emphasis on studying The Continuous temporal dynamics of cognition so this   
1:23:07   
is again uh just this idea of continuous uh   
1:23:13   
Dynamics and this is like you know the idea of like naturalistic   
1:23:18   
datasets and other types of things that aren't discreet and so that you know you   
1:23:23   
can really kind of contrast this with the cybernetics view and how they kind   
1:23:29   
of approach um intelligence and cognition and   
1:23:34   
communication um you know one interesting thing I haven't seen of course is is maybe you know kind of re   
1:23:42   
uniting explicitly cybernetic approaches and cybernetic views with this dynamical   
1:23:49   
systems view I mean you know this this paper kind of makes and a lot of papers   
1:23:54   
I think kind of make this distinction between dynamical systems approaches and   
1:24:00   
cybernetic approaches but I'm wondering if that distinction is more just kind of like drawn out because you know it's   
1:24:06   
this academic artifact of well there's this difference between the two things and we'd like to have our own field and   
1:24:13   
we you know don't really like the cybernetic View and you know this sort of that people will do this to make   
1:24:19   
their own sort of way in in academic space but like you know what are the   
1:24:25   
commonalities between cybernetic the cybernetic View and the dynamic view I'm just kind of interested in you know what   
1:24:32   
that would look like of course you know this is not something that was new to the 1990s and   
1:24:39   
Van Gilder didn't invent all this this is something that of course if we look at the uh intellectual background for   
1:24:47   
this and I I think I reviewed this in a uh cognition Futures meeting a long time   
1:24:53   
ago but a lot of the sort of the dynamical systems view of cognition   
1:24:58   
comes from ecological psychology and uh JJ Gibson's work in in   
1:25:04   
the 70s and earlier and then Michael tury's work a little bit later and you   
1:25:10   
know uh JS kelo's work theen and Smith's work in the 90s and then of course   
1:25:17   
Randle beer was doing a lot of this with robot robotic agents and so this is like   
1:25:23   
this has us a very very rich history in ecological psychology in this view that   
1:25:28   
you have to look at agents as these interacting continuously with the world   
1:25:34   
you can't just use these kind of discreet uh approaches and these kind of   
1:25:40   
you know uh experimental you know building your experiments on these   
1:25:45   
discreet approaches I guess is a better way to put it um and so the ecological   
1:25:51   
view opens up a lot of possibilities and of course the ecological psychologists are naturally attracted to dynamical   
1:25:59   
systems and so van gelder was really the person who sort of proposed the dynamical hypothesis but there are these   
1:26:07   
other intellectual precursors to this so I you know I know that paper was   
1:26:14   
a little bit like I didn't go through the paper maybe as intended The Way It Was Written but I think it brings up a   
1:26:21   
lot of important points um in that space of like uh cybernetic cognition versus   
1:26:28   
maybe dynamical cognition I mean you know lot of the   
1:26:33   
examples that that I think motivated it   
1:26:38   
really were early were   
1:26:44   
um we motor yeah yeah the easiest way I   
1:26:49   
think to study it actually and and you know and of course it's like well how   
1:26:56   
else could that be yeah right like like   
1:27:02   
um uh you know because I think   
1:27:11   
the as you know so it's like motor but also nonlinear analysis of motor yeah   
1:27:18   
you know it's like DET trended fluctuation analysis right um   
1:27:25   
I think rqa I want to say I want to say I know   
1:27:32   
what that is well I think the point is that you're collecting disc or you're collecting   
1:27:38   
continuous dat and you have to have some way to analyze it and there of course are different challenges to that kind of   
1:27:44   
Time series like you have to get rid of the noise you have to like figure out   
1:27:49   
how to make a statement about what's going on that's because we use discreet language to describe what epics or   
1:27:56   
things like that and so how do you extract that from the time series yeah yeah I mean it it's it's a it's   
1:28:04   
certainly a great um you   
1:28:11   
know um not not emphasis but like it's it's a reminder that uh   
1:28:21   
uh what you're looking at can can you know potentially severely   
1:28:29   
restrict yeah your your thinking about it and modeling right like like you know   
1:28:35   
how much how how much of cognitive science was built on decision processes before that   
1:28:42   
yeah and and um and how much you know   
1:28:48   
because this is this is something that Carl prum certainly talked about was like how much   
1:28:54   
changed when technology became available to start   
1:29:01   
recording continuous things you know yeah because I think he's he he   
1:29:09   
mentions EEG and ID yeah um and you know I I   
1:29:19   
I so so you know I want to kind of like separate out motion like like it   
1:29:27   
is you know eye tracking is is super interesting right because it's like you   
1:29:34   
can you can record the kind of the brain areas that   
1:29:40   
are controlling your eye movements um and it it's fascinating you   
1:29:49   
know like you don't you don't scan a painting like a   
1:29:55   
like a digitizer you know right so you know there are cluster   
1:30:02   
points on that you know and like like just you know face face processing and   
1:30:11   
and you know paintings painting uh evaluation like they were   
1:30:17   
discussing like two people discussing a painting and and you know how much is   
1:30:24   
how much is their eye movements coordinated because of the conversation   
1:30:29   
and how much is it coordinated because   
1:30:35   
people have these these you know nonlinear tractors   
1:30:41   
in painting yeah like some somehow the painting   
1:30:47   
creates these attractors you know for your eye   
1:30:52   
movements yeah um anyway it's a it's a fascinating area   
1:30:59   
um you know I'm I'm just reminded on how   
1:31:06   
difficult teamb based analysis is and   
1:31:12   
and how easy it is to find   
1:31:21   
coordination you know find synch ization right but but impute it to the   
1:31:33   
wrong Source or cause yeah you know and   
1:31:39   
and and like like you know I'm very I'm very um open to this kind of work but I   
1:31:48   
like I've seen a lot of hypers scanning yeah yeah   
1:31:54   
you know I I I love Gon duma's Work in Psychiatry   
1:32:00   
um uh he's up at University of Montreal   
1:32:09   
um doing you know do doing like high density recordings EG recordings to   
1:32:15   
people yeah um   
1:32:21   
um yeah like like how much of that is um   
1:32:27   
ecology how much of that is that you're dealing with   
1:32:32   
two two similar complex systems yeah like like yeah yeah it's it's um what   
1:32:42   
was the uh there was interesting discussion uh   
1:32:48   
who had this oh um Roberts psky okay   
1:32:54   
um he he does these he does these YouTube videos with his daughter I don't   
1:33:00   
know You' seen this but they're called they're called um father   
1:33:07   
Offspring interviews oh I think I've heard of it but I have   
1:33:12   
not watched it yeah yeah it's it's hysterical right so his daughter is just   
1:33:19   
asking him questions uh although I didn't get to see behind the curtain so   
1:33:24   
to speak because so so so this is their 50th one I I I really had assumes that   
1:33:32   
she just read him cold these questions from the internet and that he you know   
1:33:39   
being Robert spolsky could just talk about whatever at length yeah with   
1:33:45   
references right which which you you know which Carl fron can totally   
1:33:51   
do you know like like he does in his his meetings and   
1:33:58   
um anyway the question was um why do know congenitally blind people uh   
1:34:07   
develop skiz fre okay and um he had this this great   
1:34:16   
discussion about it which was of course getting at you know when two things are   
1:34:23   
rare How likely is it that they will   
1:34:28   
be together you know yeah uh um and so   
1:34:35   
he he he had this wonderful um example that that he talked about in   
1:34:42   
terms of you know they got like half a million people in Australia to   
1:34:49   
participate in this thing and it was just like like 11 th000 of them   
1:34:55   
developed schizophrenia and I think 60 some were congenitally blind and and   
1:35:04   
so the the answer you know it was funny because like um no congenitally blind   
1:35:12   
were found to develop schizophrenia and he said but the statistical likelihood   
1:35:17   
was six right people so he was just like zero or one   
1:35:26   
right but the main thing being you know yeah that sometime sometimes the   
1:35:33   
data is not even enough or you know like um that the the data gives you an   
1:35:42   
answer but you should actually wait because he he was giving the two   
1:35:48   
examples of of just like what if what if we' had one you know yeah   
1:35:57   
um it would say that that these are occurring more than they   
1:36:02   
should right so like given that it's a rare event you have this a rare you still have this   
1:36:08   
Association right so and what I wanted to do was like extend that   
1:36:15   
to dynamical systems or kind of Contin you know continuous data   
1:36:22   
yeah right the like it's it's it's potentially easy to find   
1:36:29   
things and also not necessarily informative   
1:36:36   
yeah but but um yeah just just that kind of work is   
1:36:44   
really you know at least at Virginia Tech the   
1:36:49   
people that are doing the hyperscanning what I I kind of like is   
1:36:57   
they are very specific about the tasks that they're giving them you know   
1:37:05   
so they're engaging in these kind of economic   
1:37:13   
tasks um and and I I think that's useful in   
1:37:19   
terms of trying to you know again like   
1:37:26   
make some of the results more kind of   
1:37:32   
interpretable um although you know I think I think the examples that they   
1:37:38   
have of real time you know real time continuous a conversation between two   
1:37:45   
people being to continuous tasks that   
1:37:51   
people are engaging and overlapping and things like it is much more real world   
1:37:56   
since and is how conversations actually happen and like like we are do we have   
1:38:03   
all these error correcting processes just like biology does right   
1:38:13   
right yeah that's actually an interesting set of observations   
1:38:20   
there just making some notes Here   
1:38:25   
yeah so um yeah why don't we check the chat I   
1:38:32   
think there were okay oh yeah okay uh yeah SAR are   
1:38:37   
you what's going on did you have an update for us or just seeing what's going on   
1:38:50   
here uh you're unmuted but we don't hear you hi   
1:38:57   
hi yeah so know mostly just dropped into see what's happening like I miss the   
1:39:02   
last couple of meetings I think I was on vacation I'm just back in town so just   
1:39:10   
OPP to see what yeah well good deal yeah nice to   
1:39:15   
have you yeah I I wanted to um you know I've   
1:39:21   
been diving into llm um   
1:39:27   
engineering uh to some and you know wanted to get uh any   
1:39:36   
any recommendations um that you had in terms of U   
1:39:44   
multi-agent uh you know multi-agent   
1:39:51   
coding yeah multi-agent code   
1:39:57   
developers and you know thinking to your to your   
1:40:04   
project um and yeah just if there were any any particular uh approaches or um   
1:40:14   
projects that you might recommend maybe you didn't get a chance to work with but   
1:40:19   
you thought would be interesting um just wondering where where there might be a you might have   
1:40:25   
some of those references yeah sure I did actually like I had I remember compiling like a list   
1:40:33   
of these so I'll go through them and I'll send it on the chat so I don't have   
1:40:39   
them like on this laptop right now sure sure that that would be that' be great   
1:40:46   
yeah so mostly in my experience when I was researching into that what I noticed was mostly you like try to have some   
1:40:54   
sort of open- source framework uh for the like especially for the part where the agents communicate   
1:41:00   
with each other like coding that from scratch can be very uh this so like uh   
1:41:06   
in in the project that I did here that is kind of what I did like I made it from scratch uh but then there are a lot   
1:41:13   
of uh Frameworks that allow you to do that part so you only focus on programming each agent individually and   
1:41:20   
then the communication part is quite easily done so I'll send over the list   
1:41:26   
of this please I I'd love to um yeah I'm   
1:41:32   
really really curious about the multi multi-agent uh um examples or you know   
1:41:40   
like like since we're coming off of a paper about   
1:41:45   
teams uh yeah you know how just wondering about how   
1:41:54   
potentially limiting it is to have a single code agent versus having a a team   
1:42:03   
if you will you know especially especially for   
1:42:09   
um especially for good code or you know like like like again I   
1:42:15   
I I I I dropped some links into Data s ml   
1:42:22   
from this guy Simon Williams it's not   
1:42:29   
Williams it's something will Willison willson anyway he's the co-creator of   
1:42:35   
Jango and was definitely seems to be doing the the the talk   
1:42:42   
circuit I was gonna say talk show circuit but no talk talk Circuit of of   
1:42:51   
um podcasts and and   
1:42:56   
conferences saying code agent you know llms can be a good code   
1:43:04   
generator okay yeah but but but I I like   
1:43:09   
I liked his emphasis on you know I liked his   
1:43:15   
pragmatism and his his realism yeah and   
1:43:20   
and I and I like I like that he's not I I I like that he's first and foremost a   
1:43:27   
guy who wants to support C creators and   
1:43:36   
um writers okay yeah you know like like like that that's his main goal that's   
1:43:43   
why he started D Jango he was he was like the the developer for some small   
1:43:49   
Kansas newspaper or something like that oh yeah and and you know and like like   
1:43:56   
he's made his he's made his fortune and now you know he's back just doing this this kind of thing and   
1:44:03   
um and it just seems like you know so much   
1:44:09   
of what you really want is is excuse me what comes from um you know   
1:44:17   
a build Sprint that's going well is one where you've got a bunch of team members   
1:44:23   
that are able to you know complimenting you know catch catch errors are things   
1:44:28   
that you're not thinking of um or build in you know build in um   
1:44:36   
needed hooks for something else that somebody else is gonna use it for later or you know all these kinds of   
1:44:43   
things that that would seem best coming from a um a multi-agent   
1:44:50   
uh coming with a multi-agent scenario but yeah um yeah that would definitely be an   
1:44:57   
interesting thing to look into especially with a lot of the work   
1:45:02   
that SED last summer with right and you know we have like a very controlled   
1:45:08   
system where we have open source project and then like   
1:45:13   
agents doing the open source project yeah one agent is creating project and then opening issues and closing issues   
1:45:20   
and you know so so like like like again like thinking about you know both this   
1:45:27   
SPC um uh uh as well as the the Logan cross   
1:45:33   
you know yeah just the the the multi   
1:45:40   
multi-agent being you know a great example of of where you kind of you have a theory   
1:45:48   
of mind yeah of what the other agents are doing or you know you you you would   
1:45:55   
probably be developing one right you know um and yeah so just a just a links   
1:46:03   
to a bunch of those things as well as being this you   
1:46:09   
know with our perhaps   
1:46:15   
um idealistic goal of you know at what point will LMS be   
1:46:23   
can can they even be something that actually AIDS scientific research or you   
1:46:30   
know yeah like like cod coding coding is not scientific research um but   
1:46:38   
um but coding and certainly coding in a in a much larger context you know again   
1:46:45   
like I've just been thinking about how to potentially do a a refactor of a of a   
1:46:51   
code base that I know I knew worked like 10 years ago like so to some degree it's like   
1:47:00   
it's self-consistent you know like I can't necessarily dump it on a new OS and run   
1:47:06   
it without its dependencies and things like that but um um how much is there for a a   
1:47:16   
software writing agent um to learn from that and and how much yeah just what   
1:47:26   
what are the limits of these these new software agents because you know it it   
1:47:31   
is obviously gonna be one of the first targets right yeah it's it's like we   
1:47:38   
could talk about all the jobs and all the hype about AI but obviously the first One's Gonna Be can the agent right   
1:47:45   
codes right right and do it effectively in a team and do it effectively and be   
1:47:52   
be uh you know what's what's the human agent interaction uh um and yeah how how to   
1:47:59   
manage that and all of those things um as well as you know all of the things   
1:48:06   
that went in you know that were um real factors for for Sarah's projects in   
1:48:13   
terms of software sustainability or you know um well yeah and and yeah and community   
1:48:23   
to the important thing community that I see in community building is of course   
1:48:29   
how to bring in new people get them up to speed um and and   
1:48:37   
you get them also contributing as opposed to um just   
1:48:44   
learning yeah so like these two that I dropped in   
1:48:50   
the chat like I've talked about both of those I think earlier as well but like at the that I had done my research I'm   
1:48:57   
sure like there are are much more now as well um but at the time that I've done   
1:49:02   
my research these two were the main uh like proper Frameworks uh that would like one they   
1:49:09   
both have papers in which they you know have a lot of this like supporting   
1:49:15   
research as well for like why these agents work good in teams and what is like uh like metrics as best as they   
1:49:22   
they could measure of how effective they are in teams versus when like the same   
1:49:27   
task is done with a single uh GPD agent or something and uh like they're both   
1:49:34   
same works that you know allow you to do like your own experiments like you   
1:49:39   
install the framework and everything and then you can just program each agent individually and kind of Do Your Own   
1:49:46   
Thing agent was I think I've personally tried meta GPD I haven't uh but I've   
1:49:51   
like read about it and in the videos and stuff yeah so so these   
1:49:59   
are both definitely there but like all of my research was I think like quite   
1:50:05   
like 6 eight months back so there may definitely be like you know better newer   
1:50:10   
Frameworks and stuff uh and like one thing that I personally wanted to use was L chain which also has this very   
1:50:17   
good uh like the whole thing is it has this chain of uh how the information   
1:50:23   
flows which makes it very easy to uh communicate between   
1:50:29   
agents so like a lot of people use l for multi-agent f development as well yeah   
1:50:37   
so this is where I think it's interesting you know because I I would say the big update since since last year   
1:50:47   
right it's been these the emphasis on reasoning models right yeah and   
1:50:55   
and you know and there's there's a lot of details about that but but again it's   
1:51:00   
this this everybody's trying to make a a Reasoner   
1:51:07   
um but to to your point about you know like Lang jang's older but but this is   
1:51:15   
this is multi-agent and and it certainly I I'm just you know I'm laughing at deep deep   
1:51:22   
wisdom is the meta gpts   
1:51:29   
company deep wisdom top AI you know it's   
1:51:36   
a it's you know I I I guess nobody's nobody's willing to take deep thought no   
1:51:43   
Deep Thoughts by Jack candy yes yeah well you know it's like it's like you   
1:51:48   
can't have a direct you know you can't have a direct Douglas Adams reference yeah   
1:51:55   
um but uh uh yeah yeah it but super interesting   
1:52:01   
like like I'd love to um yeah   
1:52:09   
and we've got your presentation on YouTube right yeah there her   
1:52:16   
presentation yeah yeah I I I should I should go back over that and um   
1:52:23   
um but uh it's certainly looking at deep   
1:52:28   
wisdom's web page you know I can see I can see that that's exactly what they're   
1:52:34   
going for in terms of the you know what I was thinking about multi-agent see that yeah you   
1:52:43   
know it's a fra yeah framework for basically what you're talking about although yeah yeah is it open source or   
1:52:51   
is it well it makes me think that like they they   
1:52:57   
open source you know they open source something yeah it's not all they got   
1:53:03   
then they got VC money right right exactly because I remember like the first time i' come across this I do not   
1:53:10   
remember seeing this rooming so no no no I'm sure I'm sure you know I mean yeah   
1:53:16   
so I'm sure of this is this is so this is so silicon   
1:53:22   
Val right you know it's like this all you know this   
1:53:27   
all happened like within a year yeah because the first time I'd seen this it looked like a group of like college   
1:53:34   
students got together in and now it's suddenly a company totally totally I   
1:53:40   
mean I mean you know this is the we have this big this big you know I   
1:53:47   
mean it's just a running joke right uh where we get people come by the the   
1:53:54   
community science lab and you know they're interested they're talking about   
1:53:59   
stuff and you know and then you say like hey what what you know what happened to   
1:54:04   
that guy they seemed really interested it's like oh well like yeah he and his   
1:54:09   
idea like they got 50 million to do just to drop everything and start an AI   
1:54:16   
company yeah yeah you know like like wasn't G to work   
1:54:22   
on some protein or something like yeah but you   
1:54:29   
know oh good deal this is the original presentation yeah that was the one   
1:54:35   
before and and then you talked about Lang chain and things yeah yeah this is the one which   
1:54:42   
like I talked about like water are you know some why like I want to do the open   
1:54:48   
source mod uh open source sustainability project with llm so it had like a lot of like proof of   
1:54:55   
concept of the M agent working and stuff gotcha gotcha and and and at the time   
1:55:02   
right because because previously it it had been just an agent-based model in a kind   
1:55:10   
of um right right right right right right in a in a net like a net logo kind   
1:55:16   
of way right right Bradley yeah yeah well there is a net logo compon OR uh   
1:55:23   
agent based component to it and we running it I think also   
1:55:28   
in Misa yeah and then but then you know that's kind of like underneath is the   
1:55:33   
Lang chain and then the other uh you know you have to generate what the agents are doing right like the behavior   
1:55:39   
that was the part that was like the llm and then agent based model were the interactions so it's like doing that   
1:55:46   
kind of a hybrid model or I guess you could use a reasoning model but you know it's um that's you know you could you   
1:55:52   
could play with it in different ways it it's let me um uh   
1:55:59   
um just just because you mentioned that and because   
1:56:09   
um sorry because um of the paper talking about the   
1:56:18   
um oh look I I didn't realize James Glazier is totally coming from   
1:56:23   
experimental condensed matter physics I mean you know that of course   
1:56:30   
makes sense right right um okay so glim   
1:56:38   
print is his um is his organization yeah   
1:56:43   
that meets on Thursdays so um but um the the the   
1:56:51   
previous um the previous glim print was focused   
1:56:58   
on combining continuous models with agent based models   
1:57:04   
okay and and that was super valuable it was like   
1:57:10   
extended colon filters um for for bridging for for   
1:57:16   
bridging these these worlds that I thought would be really um   
1:57:23   
really valuable I think they taking it   
1:57:28   
from it's also talking about bridging M you know multiscale but also these kind of like fundamentally different   
1:57:35   
architectures and how this had been taken from climate modeling or something   
1:57:42   
anyway I I'll I'll find a link or um uh I wonder if it's   
1:57:50   
already on YouTube but um yeah appreciate that   
1:57:55   
Sarah I um I want to look at that   
1:58:02   
again all right uh why don't we move on I had one more thing to talk about today   
1:58:07   
and that's following up on a discussion we had two weeks ago about the same   
1:58:12   
topic but I had some things   
1:58:18   
that I had some things to follow up on so this is the Deep seek in larger language models conversation we had two   
1:58:24   
weeks ago this was Morgan and myself and uh so this is uh one paper this was a   
1:58:33   
thing that was posted in the slack and it's it's a a long document but this is uh the it's focusing on reinforcement   
1:58:43   
learning from Human feedback and this is sort of a short introduction to rlf as   
1:58:49   
the field is known and post training focused on language models so they're actually this is sort of a hybrid model   
1:58:56   
between reinforcement learning from Human feedback and then linking that up   
1:59:03   
to to with large language models or language models in general and so this   
1:59:08   
is actually a book uh but so I'm not going to go through it but I'm just going to kind of highlight it here so   
1:59:15   
reinforcement learning from Human feedback or rhf has become an important Technical   
1:59:21   
and Storage ining tool to deploy the latest machine Learning Systems in this   
1:59:26   
book we hope to give a general introduction to the core methods for for people with some level of quantitative   
1:59:32   
background so this book starts at the origins of rlf both in recent literature and in a   
1:59:39   
convergence of disperate fields of science which include economics   
1:59:44   
philosophy and optimal control we should kind of highlight rlf and dive into that   
1:59:51   
in future meetings but for now you know this is just kind of talking about this   
1:59:58   
area uh and then we set then set the stage with definitions problem formulation data collection and other   
2:00:05   
common math used in the literature we detail the detail the popular algorithms   
2:00:12   
and future frontiers of rhf so this is about rlf but this is actually focused   
2:00:17   
on language models and post training so this is something the kind of uh think   
2:00:24   
about this is this um diagram uh this is actually where Schmid Huber strikes   
2:00:31   
again with deep seek and kind of like thinking about we I think we talked about how Schmitt Huber had mentioned   
2:00:39   
something about some connection to deep seek or you know like Schmid Huber always has this thing where he did it   
2:00:46   
first and then everyone else did it later and so this is an example   
2:00:52   
of uh Jurgen Schmid Heber 2018 reinforcement learning prompt engineer   
2:00:58   
and World model and Abstract planner collapsed into one big net so this is like everything in the world like this   
2:01:04   
is World models prompt engineering based on reinforcement learning and Abstract planning in this big net and so this is   
2:01:13   
kind of the diagram here where and Chris's initials are right here um and   
2:01:18   
then so you have this network it's a triangular uh Network you have a controller unit here model units and   
2:01:25   
input units so the input units are here uh you you have the model units in   
2:01:32   
in internally and then the controller units in Gray and so you have these sensory inputs reward inputs an input   
2:01:41   
that defines the goal or the current problem you have this humanoid robot or other type of agent out here you have   
2:01:48   
these outputs that predict future cumulative reward uh an encoding of History system history   
2:01:56   
predictions and then predicting the goal so that gives a t plus one to this goal   
2:02:02   
T and then that feeds back to a prediction of T A Time T and then this   
2:02:08   
output here that comes out to this this other agent so this is kind of this   
2:02:14   
multi-agent learning but also within the agent where you're doing this reinforcement learning and having this   
2:02:20   
world model uh you know it's it doesn't really make a lot of sense without context necessarily but this is just a   
2:02:28   
nice uh kind of follow up to that discussion we're having on   
2:02:34   
that this is uh an article um uh that says I don't know what oh   
2:02:41   
fundamental limits of large language models uh recent results show that large language models struggle with   
2:02:47   
compositional tests suggesting hard limit to their abilities so this is an article from I think it's Quantum   
2:02:54   
magazine and so multi-step logic problems can confound large language   
2:03:00   
models and this is kind of following up the reasoning discussion we had where you know they kind of talk about this   
2:03:06   
sort of these reasoning problems where you know you have to decompose a sentence and compose the sort of the   
2:03:13   
parts of the sentence to reason about what it means and so um they kind of   
2:03:19   
focus on Einstein's puzzle or RH uh the problem tests a certain kind of multi-step reasoning so you can actually   
2:03:26   
have these kind of types of problems that are specific to multi-step   
2:03:32   
reasoning uh uh new hairi a research scientist at the Allen Institute and her   
2:03:39   
colleagues recently set Transformer based large language models such as chat gbt to work on such tasks and largely   
2:03:46   
found them wanting they not might not be able to reason beyond what they have seen during the training data for hard   
2:03:53   
tasks or at least they do an approximation and that approximation can be wrong so using Einstein's riddle they   
2:04:00   
were able to probe these models and you know kind of come up with some fundamental limits for at least the   
2:04:07   
current models to solve compositional reasoning tests and these are again Transformer based larg language models   
2:04:13   
so you know other types of larg language models we don't know we just know from   
2:04:18   
the Transformer based types of models and so they you know they're kind of   
2:04:25   
figuring out what the limits at least of these Transformer based models are the work is really motivated to help the   
2:04:31   
community make this decision about whether Transformers are really the architecture we want to embrace for   
2:04:36   
Universal learning so it may be that Transformer based architectures are good at certain things but not this Universal   
2:04:43   
type of learning and composition so this just this article   
2:04:48   
goes through a lot of this reasoning and and some the things that they've been doing in that   
2:04:54   
area this other article this is from Nature Neuroscience um this is uh an   
2:05:02   
article not familiar with any of the authors um but this is the architecture   
2:05:07   
of the human default mode Network they explored through cyto architecture wiring and signal flow um this was not I   
2:05:15   
don't really remember it's got some some very classic people in Nur Imaging oh   
2:05:22   
okay Sophie yeah yeah so I mean you got you got Simon iov and Kat nans who you   
2:05:30   
know the C alment now runs the the human brain project you know European human   
2:05:36   
brain Pro I think it's e brains yeah uhh Alan Evans is the   
2:05:42   
the big guy at Montreal Neurological Institute and all the the big um big   
2:05:50   
brain Imaging studies okay and and um and Daniel   
2:05:55   
marulas um is the guy really brought in   
2:06:00   
um gradient based analysis U uh although Baris bernhard's you know amazing too   
2:06:07   
and yeah there's probably plenty of I mean so so Sophie vul too you know has   
2:06:13   
done um all this stuff so it's I I I think I posted this yeah yeah maybe well   
2:06:21   
and and it was it was just a a real CH   
2:06:26   
to force with some some I think there's another paper I might have also posted   
2:06:33   
recently but like like just bringing together all these these threads into   
2:06:39   
kind of one one paper yeah I'm trying to remember why like why I pulled this up   
2:06:47   
for the this discussion what were we were talking about neuroimaging that discussion so it may have been the   
2:06:54   
default mode Network that we were talking about yeah yeah I mean you know   
2:07:00   
it's it's um yeah let's scroll down a bit more in   
2:07:07   
terms of just I mean I I think I brought it you know was in Neuroscience networks   
2:07:13   
just because it was just like yeah yeah like like it was bringing together all   
2:07:19   
this stuff yeah it's like cool paper it's it yeah so this is about the   
2:07:25   
default mode Network and like how they're using histology and narrow Imaging to characterize the default mode   
2:07:31   
Network to better understand its role in information processing and tical communication so you know thinking about   
2:07:38   
the default mode Network it's cytoarchitecturally heterogeneous so you have different   
2:07:44   
types of memory related processing different types of modes of processing   
2:07:50   
you have um you know these inputs from sensory cortex and you have a core that's   
2:07:58   
relatively insulated from environmental input and then an analysis of signal flow with effective connectivity models   
2:08:05   
that show that this default network is unique amongst cortical networks and balancing its output across a level of   
2:08:12   
sensory hierarchy so we have this uh you know the default mode network is notorious for being misunderstood in   
2:08:19   
terms of its function I mean people use it as like a sort of a uh control for a   
2:08:26   
lot of narrow Imaging studies but like it's notorious for being kind of yeah it's it's always struck me you   
2:08:35   
know like like my advisor was very uh well and Christian Beckman who   
2:08:43   
is is is postdoc um was really you know early on defining   
2:08:53   
these these core networks right and this this   
2:08:58   
one being like such a dominant one and and it it just kind of reminds me   
2:09:05   
of you know EEG being discovered with Alpha activity   
2:09:13   
yeah you know and that like like you end up seeing it you know like more and more   
2:09:20   
you find it's connected to everything yeah you know and like you know you know   
2:09:29   
it's structured you know it's it you know it's like by Design so to speak   
2:09:37   
right yeah you know but at the same time it's like if it's connected to everything then like how much is it   
2:09:44   
adding you know right yeah well anys that's a cool paper   
2:09:50   
um and then finally we have this article here this is actually something that I found in   
2:09:56   
conjunction with what we're talking about uh more about like um thinking   
2:10:03   
about artificial intell or general intelligence and how that is sort of the   
2:10:08   
goal of a lot of what people are doing and maybe we shouldn't be thinking in that direction so this the number of   
2:10:15   
good authors here in this space kind of maybe critical of what's going on not a   
2:10:21   
modern AI research so this is where you know we think about this idea of   
2:10:26   
artificial general intelligence having a general intelligence and having that be the standard for artificial intelligence   
2:10:34   
and so uh this kind of rethinking of this in the history of AI and and kind   
2:10:41   
of the the Fran cholle work that uh he's been publishing recently uh   
2:10:47   
critiquing like this idea of general intelligence so the abstract is uh the   
2:10:52   
AI Community uh research Community plays a vital role in shaping the scientific   
2:10:58   
engineering societal goals of AI research in this position paper we argue that focusing on the highly contested   
2:11:04   
topic of artificial general intelligence undermines our ability to choose effective goals we identify six key   
2:11:12   
traps obstacles to productive goal setting that is aggravated by AGI   
2:11:17   
discourse and so those six key traps are illusion of consensus supercharging bad science presuming   
2:11:25   
value neutrality goal Lottery generality debt and normalized   
2:11:31   
exclusion so these are like I guess um you know ways in which we don't   
2:11:37   
understand the goal what research is doing um and then to avoid these traps   
2:11:43   
we argue that the AI research Community needs to one prioritize specificity in   
2:11:49   
engineering and societal goals so you know instead of just throwing a intelligence out to the world you know   
2:11:55   
use it kind of use it for specific purposes and reasons and you know then you'll be able to develop I guess a more   
2:12:03   
uh responsible controlled model two Center pluralism about multiple worthwhile approaches the multiple   
2:12:09   
valuable goals and three Foster Innovation through greater inclusion of disciplines and communities so that's   
2:12:16   
something we've course been championing in this meeting today uh you know using cognitive science methodologies and   
2:12:23   
other types of methodologies you know even uh uh dynamical systems   
2:12:29   
methodologies and team methodologies to sort of understand problem and you know   
2:12:35   
uh therefore the AGI research Community needs to stop treating AGI as the north   
2:12:40   
north star goal of AI research so you know this is very much criticizing this   
2:12:46   
approach of general intelligence you know something that may or may not be   
2:12:51   
able to Define well um yeah yeah for sure and and the well I I   
2:13:01   
love it as well as you know um just thinking about something that   
2:13:07   
came up in this um this great talk uh by this this young guy uh who's like head   
2:13:16   
of he's like CTO for modal AI um but he's you know recent   
2:13:25   
Berkeley AI Grant all like like PhD gr   
2:13:31   
and um um and it's all about benchmarks right   
2:13:38   
like like he's you know   
2:13:44   
so we can talk about AGI but as Chalet says do do you know what it is right   
2:13:52   
you know it's like like if you want to say somebody has it uh you know if you   
2:13:58   
want to say some agent has it like what do you mean by that like like what would   
2:14:04   
what would what test would you give it um and you know and like that's as   
2:14:12   
specific as you can be you know um   
2:14:19   
and anyway it's I I think it's good to bring up   
2:14:27   
um Yan laon's recent you know talk um you know   
2:14:33   
there's big AI um action Summit in   
2:14:39   
Paris you know where the non the non us   
2:14:45   
countries um uh had some you know collaboration   
2:14:52   
but you know some good statements um came out in terms of   
2:14:59   
uh you know just his his re-emphasis of of like llms you know aren't aren't the   
2:15:07   
Royal Roads to sorry there's yeah a lot of door slamming going on upstairs I   
2:15:13   
don't know what's going on um uh um and just how often   
2:15:22   
well yeah you know that that that llms aren't reasoning you know yeah like like   
2:15:29   
we're we're there was a great machine learning Street talk and um it was the   
2:15:36   
de original developer of lstm and   
2:15:42   
um it was really great because he's just like LMS are just database yeah like   
2:15:49   
we've we've given it all the text yeah you know like all the text we can find   
2:15:57   
and again like in data ml I I got a great uh talk by a CMU woman you   
2:16:06   
know talking about the different text inputs to the different models yeah that   
2:16:11   
is is also interesting because and she's just like hey you know what different   
2:16:17   
text inputs different models yeah you know uh but like his emphasis on these the   
2:16:25   
you know what we've distilled is this is it is kind of a   
2:16:31   
database of of the text that we started with right and   
2:16:37   
and um yeah and that that a lot of the fine   
2:16:44   
tuning is is just to nudge that   
2:16:51   
retrieval into patterns that we are more comfortable calling   
2:16:57   
reasoning you know on which again ultimately come down to   
2:17:03   
what are the benchmarks that we've assigned as as those you   
2:17:09   
know you know leaderboard metrics right   
2:17:15   
yeah yeah yeah so I wanted to end here Sara's uh Chat thing here uh so she said   
2:17:24   
deep learning can always be trusted with the best resources for this he mentioned some Frameworks in this as well and this   
2:17:30   
is deep learning batch gentic design patterns so this I guess is a chapter   
2:17:37   
where it's a thing here where kind of talks about prompting an LL to play   
2:17:43   
different roles for different parts of a complex tasks summons a team of AI agents that can do the job most   
2:17:49   
effectively so this is like um chat based on the chat Dev architecture I   
2:17:54   
think uh when I think uh uh Sara gave a talk in the Saturday   
2:18:02   
morning group like last summer and this was like in that this was a slide in   
2:18:08   
that talk I remember this and so this kind of talks about these different agentic design patterns for multi-agent   
2:18:16   
uh collaboration you have designing coding testing documenting that's that's in a waterfall model and then you have   
2:18:23   
so this is the waterfall project management model where you have these different phases of the of the uh   
2:18:30   
project and then you have these different agents doing this um and then you have these chat chains where these   
2:18:36   
different Agents from these different phases of the project kind of come together and uh have to communicate and   
2:18:43   
then contribute things to the project and so this is kind of like figuring out   
2:18:49   
this architecture and the cont to project management and collaboration um then also I've read   
2:18:56   
both chat Dev and metag GPT from the mentioned papers in this and definitely   
2:19:01   
have uh both have really good results of the multi-agent framework as well as really good results another a bit   
2:19:07   
extensive but good resource to find anything regarding large language models that keep getting updated as well is   
2:19:14   
this repository GitHub this is looks like uh   
2:19:21   
uh lar large language model agents papers so this is like a repository of   
2:19:27   
from aigi Edge Runners where they kind of have these paper lists um where they   
2:19:34   
get the paper and the code and and I guess it's uh by category survey   
2:19:40   
planning uh feedback and reflection so this is a good resource for like all   
2:19:45   
different areas um of This research uh research domain I like yeah it's very   
2:19:51   
long and it has a lot of good resources in it so check it out okay yeah that's awesome yeah well   
2:19:59   
thank you for that Sara thank you for the materials and thank you Morgan for   
2:20:05   
having a l a good conversation around this and following up on this absolutely no it's it's um yeah it's really   
2:20:12   
interesting uh it's you know like like like that one   
2:20:22   
that one review paper that we kind of started with you know talks about like there's there's a lot of overlap with   
2:20:28   
cognitive science here yeah and and as well as just model building in cognitive   
2:20:34   
science you know and and so um yeah and   
2:20:41   
you know I I love the the rise of these reasoning models yeah in terms of pushing us to think about these things   
2:20:49   
um and um and I think we've talked before about how you know   
2:20:56   
that um any future AGI like system is g to be a hybrid system yeah just just   
2:21:03   
just certainly like we are yeah yeah yeah but yeah great great uh   
2:21:10   
great papers to cover yeah right all right okay keep updated in your findings   
2:21:17   
is it yeah for sure for sure thanks yeah thank you all right thanks everyone   
2:21:23   
see you next week take care take care bye bye   
