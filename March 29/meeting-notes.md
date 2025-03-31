## Meeting Recording

[YouTube link](https://youtu.be/o-A0p13RS2I?si=O8UPVDzUlUA2-aNw)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114248572526142260)

## NOTES
Diffusion Models and Neuroimaging. Helpful: diffusion models in brain imaging.

neuropilot.chat

Group statistics for large multi subject datasets. Gamma distribution for unaccounted for variation.

what do diffusion models give you? Goals to set, diffusion variant most appropriate  for task?

Synthetic Data Generation.

understanding of group differences (context of problems form the same domain).

still need a lot of data to find generalization —> address population.

“Bitter Lesson” article. Similar to the “Incredible difficulty of Biological Data” article.

brain is inherently biological. Spiking NNs —> capturing brain activity.

AI will not be a cognitive filter for complexity. AI x Bio (Foresight) —> CNS (Cognitive Neuroscience Society) —> COSYNE (streaming from Montreal).

 calendar of good meetings and talks.

organoid development — Neurofloor with Foresight.

Boyden’s talk —> “Computer Simulations of the Brain”.

SIMNEURO lab, Global Neurotech Summit.

temporal interference. 

* play with PyTorch —> Diffusion/Flow Matching —> Spatial Template —> image normalization for Neuroimaging (common space), but destroy individuality.


Use Stable Diffusion to make types of game characters.

* batch system clusters --> academic labs.

* Star City -- built on MIT projects.

* timescales --> neuronal activities. Organisms are different.


Jesse Parent
Jesse Parent says:
I'lll be listening-only for a little bit 
8:58
Jesse Parent says:
I'lll be listening-only for a little bit 
9:00
Jesse Parent says:
I'm ok, still recovering from illnesses 
9:00
Sarrah Bastawala
Sarrah Bastawala says:
Take care @jesse 
❤️
9:08
Sarrah Bastawala says:
also same for me had missed talking about lcms (large concept models ) last week as I wasn't able to attend 

Would love to talk about it today if we have time 
9:41
Vidhi Rohira
Vidhi Rohira says:
im facing some net issues
will fix them and be back in 5mins 
10:22
Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://synthneuro.org/
 
10:24
Sarrah Bastawala
Sarrah Bastawala says:
afk for 5 mins 
10:27
Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://www.youtube.com/live/qdbcVg2aNTs?si=RuIwsjBoFXv2lL5T
 
❤️
10:30
Sarrah Bastawala
Sarrah Bastawala says:
back 
10:32
Vidhi Rohira
Vidhi Rohira says:
currently i dont have a good access to GPU but im planning to buy a new laptop  soon 
any suggestions on which one i should buy 
10:48
Morgan Hough (he/him)
Morgan Hough (he/him) says:
Let me think 
10:48
Morgan Hough (he/him) says:
https://modal.com/
 
👍
10:49
Amirhossein Afkhami
Amirhossein Afkhami says:
Fortunately, I have access to 4090 
10:50
Sarrah Bastawala
Sarrah Bastawala says:
great @amirhossen! whats the gb? 
10:50
Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://www.stride.codes/
 
👍
10:50
Morgan Hough (he/him) says:
https://github.com/agencyenterprise/neurotechdevkit
 
👍
10:50
Sarrah Bastawala
Sarrah Bastawala says:
This is what we had ended up using @morgan and for image/diffusion based heavy models would definitely recommend over google cloud: 
https://www.runpod.io/
 
10:52



Amirhossein Afkhami
Amirhossein Afkhami says:
@Sarrah 40 gn 
😮
10:55
Amirhossein Afkhami says:
gb* 
10:55
Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://center17.ghost.io/go-star-city/
 
👍
10:56
Sarrah Bastawala
Sarrah Bastawala says:
Also, was thinking of applying to this : 
https://events.linuxfoundation.org/open-source-summit-india/program/cfp/#tracks-and-suggested-topics
 in the Open Source Project Leadership & Sustainability track, for maybe a lightning talk or a session presentation, and presenting the various approaches our lab has worked on in the open-source sustainibility project. Would be my first time applying to something like this so any advice on whether this is a good idea, whether I picked the right track, how to go about it and tips? To register I have to submit an abstract of what my session would be about, how it would go and what is my experience in the field. 
11:01
Morgan Hough (he/him)
Morgan Hough (he/him) says:
https://events.linuxfoundation.org/open-source-summit-india/program/cfp/#tracks-and-suggested-topics
 
11:05
Vidhi Rohira
Vidhi Rohira says:
yes i put it up 
11:07
Vidhi Rohira says:
yes conginition-features 
11:11
Vidhi Rohira says:
also, after this can we discuss about my proposal? 
11:18
Sarrah Bastawala
Sarrah Bastawala says:
will have to leave for dinner, good meet today 
11:24
Amirhossein Afkhami
Amirhossein Afkhami says:
thanks a lot 
11:27
Amirhossein Afkhami says:
have a godd weekend

## TRANSCRIPT
     
Transcript     
0:00     
well Jesse Morgan how are you well VT     
0:05     
all right let's get started then um welcome to the meeting uh this week     
0:10     
we have no devil war meeting we're getting ready for embodied intelligence     
0:16     
workshop and some other things as well kind of working on those     
0:21     
slowly uh so that's good a lot of things to talk about today um the first is     
0:28     
following and from last week we mentioned this chatbot uh     
0:34     
UI here this is neuropilot this is something I think that Morgan mentioned     
0:42     
when we were talking about uh post-training large language models     
0:48     
so what this is is a uh type of large language model that     
0:53     
allows you to describe your experiment and the neuropilot simulated so     
1:02     
um let me I'm going to try something here rad and virtual reality and it's     
1:09     
going to process my request it's going to select my models     
1:14     
it's going to run um run the I guess the model and then it's going to analyze the     
1:20     
results and generate the report so I don't know how long this will take we'll have to see but let me go back to some     
1:27     
screenshots of some things I already picked up here uh so I asked a question     
1:34     
what happens in the brain when a person interacts in virtual reality and it gives me a bunch of     
1:40     
models that I could use to look at different aspects of this problem so     
1:46     
this is a obviously a German group that's doing this because things are kind of mixed in German and in English     
1:54     
here but um basically it gives me the hutchkin     
2:00     
huxley model um the uh adaptive exponential integrate     
2:06     
and fire neuronal model 2003 which is of course the book on     
2:11     
computational neuroscience uh spike dependent spike timing     
2:16     
dependent plasticity and then a currentbased network so it gives me a number of     
2:24     
different models to work with and I can open those up and when this thing gets     
2:29     
done running we'll open it up and see what those what they give you and then     
2:35     
uh there's some other qu related questions what happens in the brain during a psychedelic trip and can a     
2:42     
neural network sustain activity without input so that's um just kind of a quick     
2:49     
demo of the u the interface and then going     
2:55     
into one of these topics so spike timing dependent plasticity may give you a     
3:03     
scenario neurons in the motor cortex receive feedback from VR interactions engaging in timing B     
3:11     
synaptic modifications and then these are some sample graphs     
3:16     
uh of an analysis here from a simulation that they're doing     
3:21     
um and that's that's for that diff that specific model and then this is the     
3:30     
2003 example so this is where neurons create a spatial map of a virtual     
3:36     
environment for complex firing patterns enabling navigation and     
3:41     
orientation and again this is a simulation that was run based on     
3:48     
the the uh models uh presented in this     
3:54     
book and it gives you that example     
4:04     
there all right so it's still processing it's analyzing the results it's going to take a while to do this um we can come     
4:12     
back to it if you have any questions so while we wait for this I'll go on to this paper from the transmitter this     
4:20     
article from the transmitter this is by Ava Dyer and Blake Richards um and they're going to talk     
4:28     
about accepting the bitter lesson and embracing the brain's complexity so this     
4:34     
is a narrow AI perspective so uh I think that the bit     
4:40     
better lesson here is that sort of reductionist experiments aren't going to get us to the point where we can     
4:47     
understand the brain enough to interface with it or simulate it in any meaningful     
4:54     
way so you know we need things like multimodal models brainwide models and     
5:01     
to mix those with very specific models of different brain regions and different     
5:06     
functions so um they have this illustration which I think is just kind     
5:12     
of like a piece of art but basically they     
5:17     
talk about multimodal models successful efforts must make sense of data sets     
5:23     
that makes electrophysiology imaging and behavior results so you need to have a lot of     
5:29     
different things that you're measuring simultaneously across the brain so to     
5:36     
gain insight into complex neural data we must move toward the datadriven regime training large models and vast amounts     
5:42     
of information we ask nine experts on computational neuroscience and neural     
5:48     
data analysis to weigh in so this is where they kind of get a you got to have a position and then     
5:56     
they kind of explore that position a little bit so we start with it is often said that the brain is the most complex     
6:03     
object in the universe whether this cliche is actually true or not it points to an undeniable reality that is neural     
6:11     
data is in incredibly complex and difficult to analyze neural activity is context     
6:17     
dependent and dynamic the result of a lifetime of multiensory interactions and     
6:22     
learning it is nonlinear and stochastic as well thanks to the nature of synaptic     
6:28     
transmission and neuritic processing it is highdimensional emerging from many neurons spanning different brain regions     
6:35     
and it is diverse being recorded from many different species circuits and experimental     
6:41     
tasks and so what that means is that we have these kind of you know we we     
6:48     
usually think of studying the brain as using specific highly controlled experimental settings where we record     
6:54     
data and we can say something about a specific function in the brain but the problem is is those are unlikely to     
7:02     
generalize both across brain regions and across subjects so if you're trying to     
7:09     
build say a neural interface for someone you know they they uh there's been this     
7:15     
persistent problem in brain computer interfaces where only a subset of the uh     
7:24     
subjects who uh are tested uh are they     
7:29     
actually match the expectation for neural activity so if you develop an     
7:36     
algorithm for decoding neural activity it maybe works on about 70 maybe 60 to     
7:43     
70% of your subjects and the rest of them it works in a different way so this     
7:48     
is a problem of course where we need to embrace the complexity instead of     
7:53     
getting rid of the complexity but that also requires us to take     
7:59     
different methods and and um interpret our findings a little bit     
8:04     
differently so when training on data from a dynamic nonlinear stochastic     
8:10     
highdimensional system such as the brain the chances for a failure and generalization multiply because it is     
8:18     
actually impossible to control all the potentially irrelevant variables in the context of controlled experimental     
8:24     
settings moreover as the field moves towards more naturalistic behaviors and stimuli we     
8:30     
effectively increase the dimensionality of the system we are     
8:37     
analy so how can we make progress uh how do we and I you know we obviously it's     
8:43     
going to be a problem to do these sort of reductionist localized experiments in     
8:49     
the brain and then bring them together into a unified model for the brain so we     
8:54     
have this series of disjointed models tied to specific experimental circumstances and we're asking those     
9:01     
studies to sort of generalize magically across the brain to describe     
9:07     
systems so it's kind of hard to do and this is sort of they're putting their marker down for the dynamical view of     
9:14     
cognition or the dynamical view of neuroscience and saying that this is     
9:20     
basically what we need for neuroi uh so as the field moves towards more     
9:25     
naturalistic behaviors and stimuli we effectively increase the dimensionality of the system we're analyzing so this     
9:32     
notion of uh system dimensionality is important as well that you know we talk     
9:38     
about dimensionality production but one of the things in that um in doing so is     
9:45     
that we have a method that successfully removes like everything     
9:51     
that's sort of redundant and gives us a signal that you know captures the     
9:57     
information from those higher dimensions so you know there's no evidence that in     
10:02     
doing a lot of these uh you know tightly controlled but disjointed experiments that we're     
10:08     
actually doing them so okay so then their position here     
10:16     
is how can we make progress then in developing a general model of neural computation rather than a series of     
10:23     
disjointed models we believe that the key is to embrace the complexity of neural data rather than attempting to     
10:29     
sidestep it to do this neural data needs to be analyzed by artificial intelligence well that's great so that's     
10:38     
our sort of insight here um AI has already demonstrated its immense utility     
10:45     
in analyzing and modeling complex nonlinear data so they talk about the     
10:50     
2024 Nobel Prize in chemistry that went to the team that     
10:55     
uh basically developed alpha fold and they were able to solve the problem of     
11:02     
predicting protein folding which is a complex task upon which traditional     
11:08     
modeling techniques had failed to make significant headway i'm not really sure that's true but like let's suppose it is     
11:15     
um AI has helped researchers make progress on many other devilishly complex analysis problems including     
11:22     
genomics climate science and epidemiology and so they're basically their argument is to throw     
11:30     
uh AI at it um but to effectively adopt AI for neural data analysis though we     
11:36     
must accept the bitter lesson an idea first articulated by AI researcher Rich     
11:42     
Sutton a pioneer of reinforcement in a 2019 blog post Sutton     
11:48     
observed that the most successful approaches in AI have been those that are sufficiently general such that they     
11:54     
continue to scale with increased computation uh in other words clever     
11:59     
bespoke solutions engineered to tackle specific problems tend to lose out to generalpurpose solutions that can be     
12:07     
deployed at a massive scale of internet sized data and brain sized artificial networks so you have trillions of data     
12:14     
points and trillions of model parameters or synaptic waves     
12:21     
so basically you know you know this is very much in the spirit of this data-driven     
12:27     
uh approach to AI that we've seen ascendant since probably the late as or     
12:34     
the early 2010s so you know we have these models we have a lot of data and     
12:41     
we just can power through it I guess um so I mean you know it's interesting     
12:47     
that they mention that we have these complex systems but then the solution is     
12:53     
really just to power through it with better algorithms and more data it's     
12:59     
kind of interesting that they take that tack um I thought they were going to actually go more in the direction of     
13:05     
using dynamical systems approaches but that's not actually where they're going with this as far as I can tell     
13:13     
uh Sutton suggested we need to recognize that the actual contents of minds are tremendously irredeemable complex we     
13:21     
should stop trying to find simple ways to think about the contents of minds such as simple ways to think about space     
13:27     
objects multiple agents or symmetries in other words embrace complexity which is     
13:34     
you know again uh I think there could be just as many problems     
13:39     
uh in embracing complexity but then just using AI because you're using AI or     
13:45     
using a data-driven approach and you're having to interpret the things that it     
13:50     
finds and you know with proteins with proteomics it's a pretty straightforward computational problem I think in at     
13:58     
least the way in which they're doing protein structure prediction and you     
14:03     
know that's maybe a little bit different than what we're dealing with in the brain so I don't know that that's just     
14:09     
kind of my take on that but um you know this is something     
14:15     
that it's not the sort of the mainstream position so as you can imagine this has     
14:20     
been pretty controversial in at least in the way that it's been approached here so uh we     
14:27     
believe that the bitter lesson surely applies to neural data analysis as well first there is no reason we can see to     
14:33     
think that neural data would somehow be an exception to the general trend observed across domains in AI so the     
14:41     
idea is that you could use uh AI to analyze narrow data just as you can use     
14:46     
AI to analyze any other type of data which is kind of maybe in terms of     
14:52     
generalization putting the curve before the horse but you know I don't know um     
14:59     
second neural data is a clear candidate for the benefits of scale precisely because it is so     
15:05     
complex if we were to embrace the complexity of neural data and to generalize to novel situations     
15:13     
then we must move towards a datadriven regime in which we employ large models strangling vast amounts of data indeed     
15:20     
there is an argument to be made that our inability to extract meaningful signals or complex neural data has held     
15:28     
back progress on practical applications of neuroscience research so yeah we don't have good methods for     
15:36     
dealing with large amounts of data or at least we don't haven't typically had large amounts of data in the past we've     
15:43     
typically been limited to single trial data when we've had large amounts of uh     
15:50     
neuroiming data we've had to use methods that weren't basically large scale in     
15:56     
nature so that's kind of what they're getting at there ai models trained at     
16:01     
scale on these data could potentially unlock numerous downstream applications we have not have not even     
16:08     
uh yet to even fully envision so how do we unlock full     
16:13     
complexity of brain data and scale up our understanding of the model first we need models that can make sense of     
16:19     
multimodal data sets that combine electrophysiology imaging and behavior across different individuals tasks and     
16:26     
species so that of course is where They're you know kind of getting at this idea of taking you know data from     
16:35     
different sources different modes of you know neuroiming different types of anatomical     
16:43     
data different types of behavioral data bringing it together across species     
16:48     
across tasks across individuals which of course is challenging to interpret as     
16:55     
much as it is to bring together and to synthesize size so I I mean I think you     
17:00     
need a theoretical component to this i also think you would need to kind of     
17:06     
maybe not do this sort of bulk analysis of things because if you're analyzing     
17:12     
across species as we know from some of the work we've done in evil     
17:18     
uh cross species analysis and comparative analysis you know sometimes you're     
17:24     
dealing with apples and oranges and AI isn't just going to magically kind of     
17:30     
work across those apples and oranges is seamlessly so it's an interesting point     
17:36     
but I think there's some caution there second we need infrastructure and computational resources to power this     
17:44     
transformation uh we need maybe high performance computing but also     
17:51     
infrastructure that can handle the training and fine-tuning of large generalist models finally scaling     
17:57     
demands data lots of it we need data sets uh and we need to capture brain     
18:05     
dynamics in natural uncontrolled environments to fully reflect the richness and variability of brain     
18:11     
function so we need models computing in that and they actually give a shout out     
18:17     
here to some of the initiatives that are ongoing so the international brain laboratory the Ellen     
18:23     
Institute the NIH's brain initiative and then Dandy which is the open uh data     
18:32     
repository and then so so they go through some more points here     
18:38     
um where they need we need robust global data archives largecale computing resources     
18:44     
dedicated to training AI models on neural data professional software     
18:50     
develop velopers and data scientists so this is the sort of thing where you know we have uh uh research software     
18:57     
engineers we have other types of open-source developers who know how to     
19:03     
manage open source projects because these would have to be ostensibly open source because you're dealing with a lot     
19:08     
of research labs and they can't afford to have things you know uh be     
19:14     
proprietary though we've talked about you know uh different ways to do that     
19:23     
and then of course having dedicated engineers and staff who can streamline data standardization and storage and     
19:30     
help build AI models at scale okay so they have responses here from different people conrad Cordon gave a response     
19:38     
louise PoA uh let's see Terry     
19:45     
Sajinowski so let's see let's let's go to some of the Let's go to Conrad's     
19:51     
response uh one of the most profound experiences of my life as a neuroscientist was following receptive     
19:57     
field mapping experiments in the basement of the Institute of Neuro Informatics in     
20:03     
Zur as he moved bright stripes in front of an animal's eyes I could hear the activity of a neuron it was active only     
20:09     
when the stripe was in the right place the neurons receptive field and so this gave us a model of how     
20:16     
the visual system works a set of neurons that extracts lines a subsequent set     
20:21     
that would extract curves and after a few steps a set of neurons that would recognize objects uh this I this idea of     
20:29     
the brain as a collection of simple specialized neurons grouped into brain areas was deeply influential for the     
20:36     
field and me as well giving rise to both leading theories in neuroscience and     
20:41     
then the development of AI as a discipline so over the years however we     
20:47     
found that rather the specialized neurons cleanly extracting human understandable features neurons are     
20:53     
entangled in the web of multi-purpose context dependent processing so this idea that there's     
21:00     
simplicity and normal coding died on the rocks of     
21:07     
reality so there is this complexity all right but of course like I said there's     
21:13     
this complexity in terms of interactions and you know AI is     
21:19     
surprisingly good at describing highdimensional heterogeneous neural data uh and so you know I guess he he's     
21:28     
kind of on board with the idea of AI but not as for as a framework for     
21:33     
understanding things so you know it's hard to find interpable structure um AI     
21:41     
is AI models have problems finding interpable structure and they don't     
21:46     
really offer very much conceptual clarity and that's maybe some of the problems that we run into with this kind     
21:54     
of approach luise Pizo we've talked about with respect to dynamical uh     
22:01     
approaches to neuroscience um you know he talks about     
22:06     
this embrace of complexity and he agrees with that uh we're dealing with non-stationary nonlinear stochastic     
22:13     
highdimensional biological systems but this raises critical considerations regarding their proposal     
22:20     
to leverage AI if we accept that the brain operates in a fundamentally context dependent manner perhaps even     
22:27     
radically so then capturing meaningful principles requires sampling from an     
22:33     
extraordinarily vast space of possible states and computations this presents both     
22:38     
conceptual and practical challenges for any large scale modeling approach     
22:45     
so uh and it says primary consideration is that current lab paradigms     
22:51     
inadequately capture the rich dynamics observed in naturalistic environments     
22:56     
though Dyer and Richards acknowledge this I would push further we need data from animals fairly engaging species     
23:03     
typical social interactions uh across multiple ecological contexts     
23:09     
uh the environments themselves must be sufficiently complex to allow meaningful birectional animal environment     
23:15     
interactions that mirror real world dynamics and then of course the other uh     
23:22     
consideration or the other critique here involves the interpretation of multiecies data sets so we should expect     
23:31     
significant species differences in both organization and function even if you're looking across a     
23:37     
primate brains or rodent brains you have these different scales where they're meaningful functional     
23:43     
differences uh this does not diminish the value of comparative work but rather demands we explicitly account for these     
23:50     
differences in our theoretical frameworks and modeling approaches     
23:57     
um so Terry Sjinowski uh considers this     
24:04     
um you know kind of from his perspective of working on you know he's he was uh     
24:13     
one of the chairs I think of some of the narrow AAI sessions in the last narrowi     
24:18     
workshop at the NIH um and this kind of gives he gives     
24:24     
this sort of proposes a generative model of the brain where you have time series     
24:30     
from fMRI you have virtual reality is the stimulus is the continuous     
24:36     
stimulus you have causal inference by uh causal cross mapping dimensionality     
24:43     
reduction after causal compression manifolds from attractor     
24:48     
reconstruction then a network of manifolds and then manifolds simulate     
24:53     
brain activity and generate behavior so you have all these different tools kind of stacked together these statistical     
25:00     
tools these analytical tools bring in time series data continuous behavioral     
25:07     
data and then the ability to reconstruct the behavior from those data from those     
25:13     
methods so this is actually from a preprint here powett experimentally     
25:20     
testable whole grain manifolds at recapitulate behavior this is from the archive in     
25:26     
2021 so um yeah this is this is a collaboration     
25:32     
that uh Terry Sichnowski did with Gerald Powell the Okanau Institute of Science     
25:38     
and Technology um yeah so that's um that's that article     
25:44     
um then let's return to our uh chatbot here and so Neuropilot I     
25:52     
asked Neurop Pilot about RAD and virtual reality very uh non-engineered     
25:58     
prompt and so it gives me a number of these different models again kind of     
26:04     
similar models to the last question I asked that was somewhat similar uh it     
26:09     
gives me 2003 and this of course is showing this     
26:16     
uh scenario simulating the firing patterns of neurons as a rat navigates     
26:21     
through various VR maze configurations here's the simulation or the graph that     
26:27     
shows the simulation these are neural dynamics um electrophysiological dynamics and     
26:34     
then it gives the parameters for the simulation so you plug this into an electrophysiological simulator and you     
26:41     
get these with these parameters and you get these results uh to give a structured response     
26:48     
here so summary of key simulation dynamics comparison to typical normal     
26:54     
behaviors uh hypothesis on underlying mechanisms so this is a large language model it's     
27:00     
doing this so like in the article you know they were talking about throwing     
27:06     
data at a model in this case we're throwing a prompt at a you know     
27:12     
basically I guess a database of uh information about uh     
27:20     
uh computational neuroscience uh neuro imaging things like that     
27:26     
so this uh kind of gives some some sort of structured response it also provides     
27:33     
this graph and it gives parameters for running the simulation um so yeah and then it just     
27:39     
says like for the hypothesis the observed patterns could be attributed to factors such as synaptic dynamics and     
27:46     
ion channel properties and so just giving these different scenarios here the varied firing could indicate     
27:52     
difference differing adaptations in excitatory and inhibitory populations     
27:58     
possibly driven by differential expression of ion channels like KV1 and then the model's inhibitory     
28:05     
weights negative.5 suggests a strong counterbalance by inhibitory neurons     
28:11     
critical for maintaining network stability despite high excitation uh this balance might mimic the real     
28:17     
cortical architectures where inhibition tightly regulates excitation and refine signal     
28:23     
processing during complex tasks such as spatial navigation uh so they just give like     
28:30     
plausible scenarios for things that you might a rat might do in VR and they try     
28:35     
to simulate those um the what the current base network is     
28:41     
simulating small network dynamics in response to virtual reality stimula     
28:47     
these are the parameters for this simulation and the image is loading here     
28:53     
there's a spike raster plot and a spike heat map so uh the analysis     
29:02     
uh they talk about the agreement and deviation um between the reference data from the     
29:09     
Cuba model with the simulation mechanistic explanations and     
29:15     
model assessment so this is the graphs really kind of slow and loading but basically     
29:20     
you can see we have this raster plot and heat map that it's generating so it's     
29:26     
just generating this sort of example of what the data should look     
29:31     
like and then uh I think this is     
29:38     
uh this is a I don't know what this model I'm not familiar with this model but it's analyzing a celatory activity     
29:45     
in neural circuits during virtual treadmill movements and it just showing the     
29:51     
membrane potential versus time in the initial phase and the adapted phase so     
29:57     
it's like during the virtual treadmill movement before they start using a     
30:04     
treadmill and then after and then here are the simulation parameters and then a summary of key     
30:11     
observations so for the initial phase the adapted phase and the characteristics of     
30:18     
different neurons the ABPD neurons the LP neurons and the PY neurons for each     
30:25     
and then the interpretation of network dynamics and the mechanistic hypothesis so the mechanistic hypotheses     
30:33     
are synaptic plasticity ion channel modulation neurom modulatory     
30:39     
effects and then the the research directions are functional implications     
30:46     
um and then research directions so it kind of gives you some you know kind of food for thought in terms of how to     
30:53     
design an experiment how it fits into the literature actually didn't really talk with the literature too much uh but     
31:00     
they they kind of give explanations they provide hypotheses to test and things like     
31:08     
that so that was an interesting um set of things thank you Morgan for     
31:15     
uh posting the neuropilot uh trying that out seeing what it was     
31:21     
like and then yeah that transmitter article was really interesting i thought it was a quite um interest an     
31:29     
interesting approach or an interesting kind of take on it and then seeing what other people thought uh I don't I'm not     
31:37     
quite sold on the idea of using AI as the way forward i think we need a lot     
31:42     
more thinking about sort of dynamical systems approaches and other types of     
31:49     
things and then you know I think that the maybe a ro for AI would be more suited to something like what we saw     
31:56     
with narrow pilot where you have you know maybe even higher level type     
32:02     
of model where you have these theoretical insights characterized and     
32:08     
then you can move forward and say oh yeah this sort of thing happens in these species or this sort of phenomena     
32:16     
happens in this set of individuals you and and be able to do these kinds of     
32:22     
things where you can more easily target uh populations or species or specific     
32:30     
pathways and I think that would work better not really sure what they're expecting you know by kind of dumping     
32:38     
everything into um what I'm assuming is some sort of discriminant model regenerative model     
32:46     
and then you know getting something out of it i guess it's like a cool insight     
32:51     
which might pro possibly be wrong it might possibly be right you have no way of knowing i guess you're supposed to     
32:57     
validated with experiments later but that's kind of expensive in a lot of ways     
33:04     
so did we have any questions in any or comments     
33:24     
a couple of comments in the chat okay yeah let's see     
33:33     
hi yeah i was saying I think I missed the intro of what Neuropil chat is     
33:40     
uh what is it yeah like is it like something developed by INCF or uh I'm not sure what group     
33:48     
put this out but this is basically it's a large language model where you uh you     
33:54     
know that you prompt it with something you prompt it with something     
34:01     
from the neuroscience literature um and then you know like you'll ask it a     
34:06     
question like what happens in the brain during a psychedelic trip or can a     
34:11     
neural network sustain activity without input and let me see if they have oh     
34:17     
that's they don't yeah they don't really have any information about the the group here but it's basically just a a way to     
34:26     
create and explore what they call neuro simulations which is essentially kind of     
34:32     
you ask it a question it gives you a bunch of models that uh it it tests or     
34:38     
it simulates uh based on your question so it has to find kind of the things     
34:43     
that are involved in the question you're asking and then it presents the data     
34:49     
like I guess it does some of the simulations um you know like in this example that we     
34:55     
were showing it does the spike dep uh timing dependent plasticity     
35:01     
simulation it you know gives you the plot so it shows you what the data should look like and then it gives you     
35:08     
some maybe some a little bit of interpretation That's basically what it is     
35:16     
yeah it's very good yeah okay all right so last week we     
35:24     
talked about a number of things we did talk about the brain networks and we     
35:29     
took two different approaches to that we talked about brain networks as sort of these uh sort of this active inference     
35:36     
approach to brain networks we can use basian models uh and then we also had     
35:42     
this other approach to brain networks um and so you know we were     
35:48     
contrasting and comparing those we also talked about large language models and     
35:53     
reasoning and we have a whole series of discussions on that going back to about the beginning of this year so uh last     
36:02     
several meetings we've talked about this topic we've been pulling up readings on     
36:07     
it and kind of going through how people are incorporating reasoning and concepts     
36:13     
into large language models so what we saw with um Neuropilot was kind of you     
36:20     
know just a general large language model i don't think there's a reasoning step in it but you can see     
36:26     
where you know reasoning can be very useful in a model um and so yeah this is     
36:34     
a developing area and uh we'll see where that goes but I did promise last week because I     
36:41     
did bring up in the course of talking about large language model reasoning     
36:47     
talking about diffusion models and flow matching and that sort of thing so that's what I'd like to talk about     
36:55     
now so I pulled together some readings there was a reading from last week where we they had a chapter on diffusion     
37:02     
models um but we're going to kind of talk about some other we're kind of     
37:08     
going to go over some other resources on this so some of these are kind of very     
37:14     
high level so I don't want to not try to get into too much of the research i'm     
37:20     
just going to get into some so a couple of these are you know kind of these things that are put out by startups so     
37:28     
they might be a little bit uh advertising oriented we'll see um this     
37:35     
is uh introduction to diffusion models for machine learning this is from assembly     
37:41     
AI so this talks about um you know the meteoric rise of     
37:47     
diffusion models as one of the biggest developments in machine learning in the past several years learn everything you     
37:53     
need to know about diffusion models and it's easy to follow guide this is Ryan O' Conor the senior developer developer     
38:00     
educator for um assembly AI so     
38:07     
uh diffusion models are generative models which have been gaining significant popularity in the past     
38:12     
several years and for good reason a handful of seminal papers released in the 2020s     
38:20     
alone have shown the world what diffusion models are capable of such as beating generative adversarial models or     
38:27     
GANs and image synthesis most recently practitioners will have seen diffusion     
38:33     
models used in Dell E2 Open AAI's image generation models released last month so     
38:40     
this is a little bit dated but basically this is the Dell E2 these are examples     
38:46     
of producing these generative images and it's using a diffusion model     
38:51     
to do this so given the recent wave of success by diffusion models uh many practitioners     
38:58     
are surely interested in their inner workings so in this article they examine theoretical foundations and then     
39:06     
demonstrate how to generate images with the diffusion model toolbox in PyTorch     
39:11     
so the introduction is that diffusion models are generative models meaning that they are used to generate data     
39:18     
similar to the data on which they are trained so they're taking training data and they're recovering it in some way or     
39:26     
some similar way fundamentally diffusion models work by destroying training data     
39:32     
with the successive addition of Gaussian noise and then learning to recover the data by reversing this noising process     
39:40     
so you can see here in this picture they use they have a training image of someone's face     
39:47     
they use Gaussian uh noise which is just like this sort of static that you see     
39:53     
here to obscure the image and the idea is you degrade the image     
39:59     
quality and you provide the algorithm with these successive successively     
40:05     
masked images so that the you know the model can learn what it looks like when     
40:11     
there's incomplete information so you randomly ablate the data points in the     
40:17     
image you randomly degrade the features and in doing so it can learn a wider     
40:23     
range of features it can learn how the feature sort of is decomposed I guess or     
40:29     
how it like can you know lose information so if you're looking at a partial image or something that's very     
40:37     
fuzzy the diffusion model would then be better suited to recover that because it's seen things like that before     
40:45     
so you noise the training data and then you dn noiseise that training data     
40:50     
through recovering the an image that looks similar so after training we can     
40:57     
use the diffusion model to generate data by simply passing randomly sampled noise     
41:02     
through the learning learn dising process so this is where we have the     
41:09     
example we get well we don't get it from static we get it from an image that's     
41:14     
been masked by um noise or static and then we have recover an image that looks     
41:21     
like the original more specifically a diffusion model is a latent variable model which     
41:27     
maps to the latent space using a fixed fixed markoff chain this chain gradually     
41:33     
adds noise to the data and then we'll obtain the solution so this is the markoff chain     
41:40     
here zoom in so our markoff chain starts at     
41:46     
X0 which is the training data the fully unnoised training data then we have XT     
41:53     
minus one we have uh then we have XT which is the noised     
42:00     
version and then XT which is the noise capital T and then we end up with so we     
42:08     
have this noise data we go from the training un unnoised training data to     
42:14     
this chain of aggressive noising and we end up with uh an image that's basically     
42:22     
totally obscured by noise so ultimately the image is     
42:27     
asmtoically transformed to pure Gaussian noise as we see in X capital T here the     
42:32     
goal of training a diffusion model is to learn the reverse process in other words you're training this equation here     
42:40     
you're training this process here you're training that into the model     
42:47     
by trans transversing backwards along this chain we can generate new data so     
42:52     
for Q we have Q here which is the function of     
42:58     
noising and then P here which is the function of D noising so you're     
43:03     
basically going backwards now from total noise X capital T and recovering the     
43:09     
image slowly extracting features out of the noise until you reach the recovered     
43:15     
image X0 which is similar to this X0 but it's been recovered so you're trying to     
43:22     
reverse this process of training by traversing backwards along this chain we can     
43:29     
generate new data okay so that's basically how it works you have this training data you're     
43:35     
noising it you're teaching the algorithm how to identify degraded images or     
43:43     
images that are asmtoically close to pure noise and then you're recovering that and generating some similar     
43:51     
image so there are number of benefits of these diffusion models so as mentioned     
43:56     
above research into diffusion models have exploded in recent years they're actually inspired by     
44:02     
non-equilibrium thermodynamics uh which is uh I'm not going to get into     
44:08     
the papers on that but this is something that we actually featured in our paper     
44:13     
on the ever regulator theorem working through some examples of diffusion models and the ever regulator theorem so     
44:20     
there is this link between the fusion models and physics and even     
44:26     
cybernetics diffusion models currently produce state-of-the-art image quality examples of which can be seen     
44:33     
below so these are the images generated by diffusion model beyond cutting edge image quality     
44:40     
diffusion models come with a host of other benefits including not requiring adversarial training so in GANs of     
44:48     
course we have adversarial training we need to teach the model both about the     
44:53     
training data set and then adversarial images so that it can distinguish     
44:59     
between the actual type of image and then you know counter examples or um     
45:06     
counterfactuals basically so it helps the model learn about reasoning a little     
45:12     
bit and causality in this case you don't have causality you have this sort of     
45:18     
noise-driven approach where you're teaching it about how a data how an image could look if it were you know     
45:26     
obscured with noise and so you're teaching it sort of counterfactuals in that sense it wouldn't really be     
45:31     
considered counterfactual in the same way but it's teaching it something about     
45:37     
some other properties of the training set it's not teaching that the training set is a sort of idealized set of     
45:43     
information okay and this is good because the     
45:50     
difficulties of adversarial training are well documented and in cases where     
45:55     
non-adversorial alternatives exist with comparable comp performance and training     
46:00     
efficiency it is usually best to utilize them uh on the topic of training     
46:06     
efficiency diffusion models also have the added benefit of scalability and     
46:12     
parallelizability so diffusion models scale up well and they can also be     
46:17     
parallelized on supercomputers so you can build like a parallel parallel     
46:23     
processing algorithm where you can split your job up into different parts and run     
46:30     
them uh while diffusion models almost seem to be producing results out of thin air there are a lot of careful and     
46:37     
interesting mathematical choices and details that provide the foundation for these results the best practices are     
46:44     
still evolving in the literature okay so then they're going to talk about the mathematical     
46:49     
theory so as mentioned a diffusion model consists of a forward process or     
46:55     
diffusion process so the training image is diffused in noise so it's just     
47:01     
diffusion means that you're uh moving away from order so you're diffusing um     
47:07     
and then which datadam generally an image is progressively noised so that's the forward process this diffusion     
47:14     
process and then there's a reverse process or reverse diffusion process in     
47:20     
which noise is transformed back into a sample into a sample from the target distribution so you're recovering that     
47:28     
image you're recovering that distribution of the original image so it's not the original image that you're     
47:34     
actually just kind of reconstructing uh you're reconstructing the target     
47:40     
distribution and you're generating an image from that so it's very similar but it's not exactly the same but it's good     
47:48     
enough for a lot of applications so you have this forward process and reverse process is diffusion     
47:55     
and then reverse diffusion the sampling chain transitions     
48:01     
which we saw with P and Q we saw those marovian transitions in the forward     
48:06     
process can be set to conditional Gaussians where the noise level is sufficiently low so we saw some     
48:13     
conditional probabilities in there in the Gaussian chain calculations so     
48:19     
that's what we're doing with these uh conditional Gaussians where we uh you     
48:24     
know can try different levels of noise so you know it's not enough just to say     
48:29     
we're going to add some noise you know there's a strategy here and you have to have like these steps where you're     
48:36     
introducing progressively more noise if the model can pick up on that transition     
48:43     
then it's more likely to work than if you just give it like an image an image     
48:48     
half obscured by noise and then noise you know it's not going to have enough     
48:53     
transitional information to kind of follow through so it can see that the     
48:58     
how the features are being obscured because it's random noise just generating it over v you know random     
49:06     
parts of the image so you're getting you know features that are obscured in     
49:11     
different ways and progressively so until you have features that are not     
49:17     
really recognizable and so if the model can see that in the training process in the     
49:22     
forward process it has a better chance of recovering it during the reverse process     
49:30     
uh combining this this fact that the markoff assumption leads to a simple parameterization of the forward     
49:37     
process okay so as mentioned previously the     
49:43     
magic of diffusion models comes in the reverse process during training the model learns to reverse this diffusion     
49:49     
process in order to generate new data starting with the pure Gaussian noise     
49:55     
the model learns the joint distribution and then you know where you     
50:00     
have two time dependent parameters uh of the Gaussian transitions are learned     
50:06     
note in particular that the markoff formulation asserts that a given reverse diffusion transition distribution     
50:13     
depends only on the previous time step or following time step so if you have uh     
50:19     
you know as you're recovering the image from noise you have     
50:24     
these different uh transition uh time steps so if you have a transition     
50:30     
distribution you're going from the previous time step to the next time step and you're doing this you're generating     
50:36     
transition distributions for each time step and it's changing as you go along     
50:42     
this is why again you need to have this uh you know you need to have this     
50:48     
significant transition period where you can go from uh point to point and you     
50:54     
know you can't expect to recover it in two steps or three steps it might have to be 20 or 30 steps the same goes for     
51:02     
the forward um the noising     
51:07     
process okay then they talk about training a diffusion model is trained by finding the reverse markoff     
51:16     
transitions and then they talk about KL divergence which of course is something     
51:21     
that we use in looking you know for looking at differences between things     
51:30     
um so you're trying to understand this through the kale divergence of a varying     
51:36     
distribution or reference distribution so the way you know that you've recovered the image is that you have     
51:43     
this initial distribution and a recovered distribution and you can calculate the kale divergence between     
51:49     
these two distributions um and so this is kind of what they're getting at uh so there's     
51:57     
this kale divergence of P from Q at any given moment and so actually the P and Q are     
52:05     
the uh transition distributions so as you're noising the image and denoising     
52:11     
the image you can see the difference between those and of course that's going to result in the uh of efficacy of the     
52:18     
forward and the backwards noising process okay so I think that's enough on     
52:26     
that article um this is another one here this is the     
52:33     
panoramic guide to diffusion models and machine learning zoom in a little bit and this is from     
52:41     
this is AI education um not sure exactly where this is from     
52:47     
but uh this is written by Oxanna Zadrric um and this talks a little bit     
52:55     
about diffusion models so again diffusion models are cutting into     
53:00     
cutting edge technologies uh that generate and transform data ways we once thought were exclusive     
53:08     
to human creativity so uh talking about diffusion models     
53:13     
being a type of generative model in physics diffusion is a natural process or particles spread out in a     
53:20     
medium from a region of higher concentration region of lower until a     
53:26     
kind of equilibrium is reached machine learning models use a similar process to create content imagine you have a photo     
53:34     
and you're gradually adding a kind of digital fog to it making it less and less clear until it's just random or     
53:41     
until it's just a random unrecognizable pattern in machine learning we call this fog noise so this is where this noising     
53:48     
process you're basically just adding some obfuscation to the image this is     
53:54     
diffusing across the entire image until the entire image is filled with the same     
54:00     
level of noise diffusion models uh for machine learning work in reverse they start with     
54:06     
this randomness and gradual and remove the noise called deoising step by step     
54:11     
following a specific set of rules to create something structured and coordinate like an image uh and so this     
54:18     
is basically talking about how you remove the noise and that's really the     
54:23     
key part of this uh let's see     
54:32     
so there are different types of diffusion models there's the improved denoising diffusion probabilistic     
54:38     
models and so uh this is based on the original     
54:43     
DDPM these improved models offer enhancements that often result in faster training times and improved quality of     
54:50     
generated samples guided diffusion models these models allow for more control over the generation process     
54:58     
users can guide the output towards desired characteristics or attributes conditional diffusion models     
55:05     
are particularly useful in applications where the output needs to be conditioned on certain     
55:10     
inputs uh this is good for uh tasks like text to image generation and then latent diffusion     
55:18     
models by operating in a weight and space rather than directly in the data space these models can offer     
55:24     
computational efficiencies that sometimes generate higher quality outputs for certain     
55:30     
applications so this is where you have these different types of diffusion models that uh deviate from the original     
55:37     
kind of model that we saw in the first order so this is what are stable     
55:43     
diffusion models and so you we're familiar with the stable diffusion platform um so stable diffusion models     
55:52     
are specific subsets of diffusion models they they share the foundational principles of diffusion models for     
55:58     
machine learning but are different in a number of ways so while diffusion models can be used for a variety of data types     
56:05     
stable diffusion models are specifically fine-tuned for image generation they     
56:11     
excel at creating detailed and contextually relevant images based on textual prompts offering a wide range of     
56:18     
creative possibilities the term stable suggests a focus on consistency and reliability of     
56:25     
the generated outputs uh these models are engineered to produce coherent and visually appealing     
56:32     
images that closely adhere to the input descriptions which I assume means that     
56:37     
there's some sort of diffusion process but then it's linked to labels and some     
56:43     
sort of semantic content so yeah this doesn't really give a lot of information     
56:49     
technical information as much as the last article so     
56:55     
um yeah and so they talk about midjourney is midjourney a diffusion model     
57:01     
um midjourney is an independent research lab is developed in the eye system known for generating images     
57:08     
uh while the specific technical details of midjourney's underlying model are not as publicly documented or transparent as     
57:16     
compared to other AI models like deli or stable diffusion which are diffusion models It probably involves techniques     
57:23     
like diffusion so again this is your diffusion model you have this image of a     
57:29     
cat and you have the cat being progressively noised to this random     
57:35     
static noise this dowsia noise and then you're dinoising going backwards     
57:41     
recovering the image to something that looks like the cat and this process has     
57:47     
a distribution or a series of distributions that you can calculate the     
57:52     
difference between the noising and denoising distributions with KL divergence and you have ways that you     
57:59     
can optimize this entire process to improve     
58:04     
performance so again we have forward diffusion reverse diffusion final output     
58:09     
and of course the training data is very important you need to have a good uh     
58:15     
generalizable data set you need maybe to have labels in your data set and you     
58:21     
need to pre-process your data set in a number of ways that will enable this because this process is dependent of     
58:28     
course on good quality images if you already have noisy images this noising process doesn't help     
58:35     
you very much it gives you a little bit maybe a little bit more well it doesn't     
58:41     
give you as much if you had a cat and images of a cat that were like low res     
58:47     
or maybe they had some noise they were masked with some noise already um it     
58:53     
would be very hard to use this process to improve upon probably uh decreventure     
59:00     
performance so you know that there are a number of caveats with diffusion     
59:06     
modeling and diffusion processes but it's a nice approach uh inspired by     
59:12     
statistical physics and uh thermody thermodynamic     
59:19     
methods so it looks like we lost Jesse but gained a miracle scene welcome to     
59:26     
Mira and Morgan has his camera on so I don't know morgan     
59:33     
good morning just Yeah listening along oh yeah i I     
59:41     
um you know partly because it's my my background but um you know I think it's     
59:47     
always helpful to look at look at some concrete examples of these diffusion     
59:54     
models you know and brain imaging um brain imaging is one of those great     
1:00:01     
domains where you've got a lot of people kind of working on the frontier on these with     
1:00:08     
these with these kind of data sets and so um yeah you get to see in practice     
1:00:13     
like what what that what these kind of different diffusion models give you in     
1:00:19     
terms of you know okay say yeah we've     
1:00:25     
got this very large data set of UK bioank MRI structural images you     
1:00:32     
know what what do we get out of that by by running diffusion models you know     
1:00:40     
like like like what what what goals would could you possibly set and then     
1:00:47     
which particular diffusion variant is most     
1:00:54     
appropriate you know and then then it it that can be really helpful     
1:01:00     
um so you know     
1:01:05     
um I think the way that Yeah yeah just just that so that's like     
1:01:13     
is it is it for synthetic data generation you know um or is it for Yeah     
1:01:20     
some some um particular understanding of of group     
1:01:28     
differences or something like that in our work again um well it can be it can be useful     
1:01:35     
to to see it see it in the context of one problem right right     
1:01:42     
or well or or a couple problems that are from the same domain right like like there's there's a number of different     
1:01:48     
Yeah kind of problems or or     
1:01:54     
um yeah tasks that you might want to accomplish with brain imaging data um so     
1:02:03     
it's you know is it that you've got a big pile of data and you're trying to understand you     
1:02:08     
know some structures in it or you've got one volume of data and you want to     
1:02:15     
understand you know where it lies in a in the greater distribution or you know     
1:02:23     
like and then these these these the the you know some of some of     
1:02:30     
these descriptions can can be it helps to concretize what these what these     
1:02:38     
different modeling techniques are doing or can can offer yeah right if that     
1:02:44     
makesense you know oh it does yeah yeah i think it's interesting to see i've not     
1:02:49     
seen a lot of uh I mean I've seen a lot of study or I haven't seen any studies     
1:02:54     
where people kind of look at like these methods in terms of you know what what     
1:03:00     
what kinds of input images do we want to use and maybe not so much performance     
1:03:05     
but like maybe like things where you simulate that     
1:03:10     
uh you know that noising and dnoising process and see how efficient it is     
1:03:16     
outside of the realm of like the uh the machine learning technique so a lot of     
1:03:22     
you know you can do a lot of experiments with like looking at noise and how you     
1:03:27     
know it obscures an image we were doing some work with that um in diva worm with     
1:03:33     
um pearl and noise we were obscuring biomedical image with noise and     
1:03:38     
recovering the information from that so it's like you can play around with all sorts of noise not just galsy noise but     
1:03:45     
nonlinear noise and other things that you know kind of y prov sometimes it     
1:03:52     
provides information but most of the time it degrades information and so what does that look like in terms of the     
1:03:58     
information that's there that's being obscured and that's being recovered     
1:04:04     
so yeah for sure for sure i you know like um I know for like my PhD     
1:04:14     
work I I found that the group group statistics in in images had an     
1:04:22     
interesting noise distribution that was um yeah that that we weren't accounting     
1:04:28     
for it was like like gamma distribution so it was kind of kind of you know     
1:04:36     
launch yeah yeah and um     
1:04:42     
yeah you know again one of these things where it was like it was only you     
1:04:48     
wouldn't see it in a single image but it was when when you're putting putting these large multi-ubject data sets     
1:04:55     
together and uh um yeah I I I haven't you know so I I     
1:05:03     
mentioned brain but I haven't been keeping up in terms of how those are     
1:05:08     
being applied um I I I just I     
1:05:15     
remember you know when stable diffusion was the was the hot you know     
1:05:22     
AI technique or you know for the week that it was Are they still are they still a company i actually I don't think     
1:05:29     
stable diffusion is but that was like a fork of another project and there are a bunch of forks of stable diffusion so I     
1:05:36     
don't think it's like gone stability stability stability AI was the one yeah     
1:05:42     
yeah yeah um that that certainly went through its     
1:05:48     
own iteration that had a lot of drama around it you're like like wasn't David Hod stability AI maybe yeah yeah i I     
1:05:56     
think he was I think he was for for a short time um anyway it it would be it     
1:06:03     
would be good to see you know um the I mean that the the nice thing is     
1:06:11     
that you know brain imaging does have this at least this one data set it's UK     
1:06:18     
bio bank where you kind of like you know because you still need a lot of data     
1:06:23     
right or to to yeah to hopefully find     
1:06:30     
generalizations that that become population     
1:06:37     
um um that could that could interest your your population you've got a lot of     
1:06:42     
data anyway it would be good to see what um um what what presentations are coming     
1:06:50     
up on this and to human brain mapping that'll be like in June yeah     
1:06:57     
um uh yeah but I I don't have any     
1:07:09     
um yeah don't don't have any diffusion modeling in     
1:07:15     
our any of our pipelines at this time yeah what did you think about the     
1:07:21     
article I I talked about the better lesson article well yeah i'm     
1:07:28     
good come on Bradley ai is gonna save us all oh okay     
1:07:35     
um yeah you know I mean I I I I certainly like     
1:07:46     
um you know I I who did the you know the recent     
1:07:54     
like the um it was like a play on the un you know the unreasonable effectiveness     
1:08:01     
but it was like the something about the you     
1:08:07     
know the incredible difficulty of biological data right yeah like you know     
1:08:14     
I mean I I I like the brain is biology right     
1:08:21     
so so you know that's that's the part where I'm     
1:08:28     
just like that is the that is something that should be     
1:08:35     
should be addressed you know right i mean especially to counter you know     
1:08:41     
again like when people say that neural network researchers are are working on     
1:08:46     
the brain it's just like no they're not right you     
1:08:51     
know you know they're they're they're doing glorified linear algebra     
1:08:59     
right i mean you know what I mean like like there     
1:09:04     
there is something there's something to that in terms of     
1:09:09     
um uh the this idea     
1:09:17     
that even say spiking neural networks are capturing brain activity right     
1:09:25     
um is is incredibly you know     
1:09:31     
um It's an incredible simplification and abstraction um     
1:09:39     
and so it it's it's nice when Yeah when     
1:09:44     
people are writing that because well again this is this is coming from someone who who cares a lot about     
1:09:51     
physiological psychiatry right and and     
1:09:57     
um yeah kind of embracing that complexity right um but uh but yeah whether whether     
1:10:07     
whether you know AI will quickly become a cognitive filter that we can use to     
1:10:15     
just you know suddenly see you know we you know you you do an AI filter pass     
1:10:21     
and suddenly all this all all is revealed     
1:10:27     
um well you we will see the the the foresight is doing a meeting in     
1:10:33     
um I think it's in May like AI AIX bio     
1:10:45     
um no you know this is     
1:10:50     
uh I mean Ben Ben Blazic I think you know we've talked about him before     
1:10:57     
I think he's at Argon National Lab kind of close close to you     
1:11:04     
um you know chemistry material science is going to have the the     
1:11:10     
the breakthroughs first right i mean if like like if it comes out it's     
1:11:17     
going to come out in something like chemistry first right and     
1:11:23     
and the the the unreasonable complexity of biology     
1:11:31     
will remain you know mysterious for a while     
1:11:37     
who who wrote that the transmitter oh uh that article was     
1:11:44     
uh Ava Dyer and Blake Richards so Blake Richards Oh okay okay probably those are good those are     
1:11:51     
good people or you know Yeah yeah that makes me um     
1:11:57     
Yeah i mean Yeah i think Blake Richards is known for taking controversial takes     
1:12:03     
so I don't know uh but yeah this is uh I mean you know I guess it's maybe like a     
1:12:09     
discussion like food for thought you know you have articles that are sometimes just like let's put something     
1:12:14     
out there and see what people think yeah generate controversy and or um you know Well it's     
1:12:24     
you know it's time that they're all together right now in Montreal oh yeah     
1:12:30     
yeah right for for cosign you know hopefully they're     
1:12:36     
they're talking about the the complexity um it's great you know I love     
1:12:43     
that meeting for you know this they're streaming everything okay this is     
1:12:49     
currently happening yeah yeah they think this started the 27 i mean I don't know     
1:12:56     
if it was just they might have just done the opening you know opening ceremony on the 27th but I     
1:13:04     
think it started yesterday oh wow that's uh something we should check out yeah     
1:13:10     
yeah it it I mean so co-signs right now and     
1:13:16     
um cognitive neuroscience society okay yeah     
1:13:23     
um which is you know which is still still a     
1:13:30     
biggie but I'm I'm trying to Yeah yeah and you know and again like I I I think     
1:13:39     
of cosign as the successor to nurips nurops right because     
1:13:48     
um yeah you know because it's been so taken over by these people who think that the brain is is     
1:13:55     
just you know a neural network right right right right     
1:14:00     
and and Yeah yeah so again I'm I'm so old I can't remember     
1:14:08     
when Nur was was you know kind of a a     
1:14:13     
brain meeting or at least had some had more co-signers kind of stuff     
1:14:20     
right anyway I I you know I met my adviser at up at Whistler     
1:14:31     
i saw that and then some somebody was just posting in a tech slack about about uh the BCI society meeting     
1:14:39     
which is going to be at B this year so I think that's every other every     
1:14:44     
other year but it was make making me think about these meetings that are in ski resorts     
1:14:51     
yeah you know and uh it's you know I would when I was in     
1:14:59     
radiology that like the continuing education for radiologist they would always have like you know continuing     
1:15:06     
continuing education radiology this year in Costa Rica     
1:15:12     
yeah like is that why it's there yeah hey     
1:15:20     
I think you guys are just justifying the trip but right     
1:15:27     
um the trying to think um things this week     
1:15:35     
um any good meetings lots of good     
1:15:40     
talks um um lots of good brain imaging talks i     
1:15:47     
got to I got to put together a calendar that just covers the Yeah     
1:15:53     
um the the the good meetings and you know especially the ones that that also     
1:16:00     
produce a produce the video file afterwards     
1:16:06     
um but uh I I've yeah I got to do that     
1:16:11     
um a lot of lot of good progress on um organoid development you know like     
1:16:19     
really really hoping this new you know um the biolabs going to get to move into     
1:16:28     
this you know 4,000 square foot floor i'm really really and and they've     
1:16:35     
asked me to to you know basically pitch a a neuro     
1:16:40     
floor um together with the foresight institute     
1:16:45     
oh wow so that that that that was really awesome um     
1:16:51     
so Tuesday we met with um yeah and Tuesday Vitalik Bdderin you know the     
1:16:58     
founder of Ethereum Yeah came by um     
1:17:04     
I have nothing to say about cryptocurrency or you know but all these     
1:17:12     
people seem to have um ideas [Music] about postmodern society i don't know     
1:17:21     
i'll try and keep my classical liberal arts education to myself yeah um well that that together with my my     
1:17:30     
mother you know is a sociologist and urban planner dealing with Yeah anyway     
1:17:37     
it's like okay I had too many too many     
1:17:43     
discussions growing up with her uh but you know like terrific to see     
1:17:50     
that kind of support in the sense that like um they they put me in touch with with     
1:17:58     
foresight institute and you know whose bioeakers I love you know um so     
1:18:06     
foresight institute's got Ed Bdon speaking April 1 um interestingly Bdon's     
1:18:13     
talk is titled Computer Simulations of the Brain oh wow which which you know I     
1:18:21     
I that is not what I think of of him as as being one to do um     
1:18:31     
uh yeah you can check out his you know for the the students here the the um I     
1:18:38     
think his blog his um is he synthetic synthetic biology     
1:18:45     
synthetic biology.org main yeah main well it could be the address of the lab i think it's     
1:18:56     
synthetic no trying to make it     
1:19:03     
into.com interestingly syntheticbiology.org switches to to     
1:19:10     
syntheticbiology.com oh     
1:19:18     
um interesting okay i don't know who's got that but     
1:19:24     
um anyway I'll I'll check the email um in terms of what that is but um     
1:19:37     
[Music]     
1:19:47     
Sorry yeah anyway I I'll I'll find that and put it in the chat sorry okay that's     
1:19:53     
fine yeah uh yeah why don't we return to the Now I have to talk about flow     
1:19:58     
matching i talked about diffusion models um and so I have some other resources     
1:20:04     
here on flow matching this is from the archive uh this is from December of     
1:20:13     
2024 and this is flow matching guiding code so this is um from a group working     
1:20:19     
on flow matching and kind of giving this uh creating this library this is I guess     
1:20:26     
associated with meta uh yeah Facebook research or meta research and then     
1:20:32     
they're doing this flow matching and they have this resource So um flow matching is a recent framework     
1:20:40     
for generative modeling that has achieved state-of-the-art performance across various domains including image     
1:20:47     
video audio speech and biological structures this multimodal data multimodal model this guide offers a     
1:20:54     
comprehensive and self-contained review of flow matching covering its mathematical     
1:21:00     
foundations design choices and extensions also providing a pietorch     
1:21:06     
package featuring relevant examples image and text generation examples this work aims to serve as a     
1:21:13     
resource for both novice and experienced researchers interested in understanding     
1:21:18     
applying and further developing flow matching so they have this flow matching library on GitHub and this kind of goes     
1:21:26     
over some of the code that you can use implement this so it isn't as prevalent     
1:21:32     
as diffusion modeling in terms of you know uh where we can find it in the you     
1:21:40     
know in the uh startup space or whatever but it's definitely uh also inspired by     
1:21:46     
physics actually it's inspired by different types of topological mathematics and things like     
1:21:53     
that so we have um flow models which are random vectors     
1:21:59     
conditional densities and expectations ifomorphisms and push forward maps using mathematical tools     
1:22:07     
and then modeling flows as generative models uh having these probability paths     
1:22:14     
instantaneous change of variables and then training flow models and then they     
1:22:20     
have so they have flow models and flow matching or you're building probability     
1:22:25     
paths deriving generated velocity fields um calculating flow matching loss     
1:22:33     
uh solving conditional generation with conditional flows optimal transport and     
1:22:39     
linear conditional flow aphine conditional flows and data couplings and then you have these     
1:22:45     
non-uclitian flow matching approaches um continuous time markoff chain models     
1:22:52     
discrete flow matching so for the discrete case and then the continuous time markoff process model case so you     
1:22:59     
have the continuous and discrete cases uh generator matching relation to diffusion and other     
1:23:06     
denoising models so there's this relationship diffusion models and denoising     
1:23:13     
uh and so and then additional proofs so I'm going to go to uh maybe a     
1:23:20     
more accessible um example in a minute but I wanted to go down to this uh     
1:23:26     
relation to diffusion and other denoising models so in this section we finally discuss the     
1:23:33     
relation to new noising diffusion models or DDMs and related models on non-uclitian spaces we mainly focus here     
1:23:41     
on the construction of diffusion models by then they give this reference song in all     
1:23:46     
2021 and explain how it can be placed within the FMGM family of models flow     
1:23:51     
matching um family of models at the end of this section we also discuss models and other     
1:23:58     
modalities that took inspiration from PDMs or denoising models and they be     
1:24:03     
framed as uh GM models so time conversion so the first simple     
1:24:09     
difference between dnoising diffusion models and flow matching is a difference how time is parameterized     
1:24:16     
so this is just a convention but is important to avoid confusion u diff as opposed to flow matching time     
1:24:25     
is inverted in diffusion models in ranges from zero to infinity to differentiate the two time     
1:24:32     
parameterizations let us use r for the time convention of diffusion models and t for the time convention of flow     
1:24:39     
matching so we have flow matching time is t noise is is equivalent to t equals     
1:24:46     
z data is equivalent to t = 1 so this is where you go from noise to data flow     
1:24:53     
matching and then diffusion time is r where noise is equivalent to r equals     
1:25:00     
plus infinity and data equals r or is equivalent to r equals one or zero so     
1:25:08     
you have uh data being um a value of zero noise being plus infinity because     
1:25:15     
you're adding noise to the data and then recovering it and then reparameterization is these terms here     
1:25:23     
so you can reparameterize the model um the underlying idea of denoising     
1:25:29     
diffusion is to construct a forward process that corrupts the data distribution um and so this corresponds     
1:25:36     
to a specific construction of a probability path as used in flow matching so in flow matching instead of     
1:25:43     
using this forward markoff process you're using this probability path in     
1:25:49     
flow matching so I guess what you're doing is you're working with flows you're working with the metaphor of flows and you're trying to find a path     
1:25:57     
uh from noise to the image um and so this is     
1:26:03     
uh this is the equation here where Q is the data distribution WR is a brownie in     
1:26:10     
motion and there's there's a velocity field also called drift in the context of SDES and then a diffusion     
1:26:18     
coefficient so um I guess these are stochastic differential equations they're working with um and then every     
1:26:26     
such SDE defines a conditional probability path and marginal probability path in these terms where in     
1:26:34     
the second line we parameterize time into the flow matching time parameterization so um this forward     
1:26:41     
process is constructed uh that for R greater than zero the     
1:26:47     
distribution of XR is approximately a Gaussian so basically they're working uh     
1:26:54     
it's very similar to uh denoising diffusion models you're     
1:27:00     
just following a path uh through a flow so that's kind of the relationship     
1:27:05     
between the two you're training a diffusion model um we now discuss how we     
1:27:12     
can recover the training algorithm of diffusion models is a special case of flow matching training in section 4.8 8     
1:27:19     
we discussed several options for how to parameterize and train a flow matching model with Gaussian probability paths so     
1:27:27     
you're using Gaussian probability paths instead of these uh forward chains or     
1:27:32     
forward uh noising these discrete noising u uh training sessions so you're     
1:27:40     
trying to work through this flow you have these browsy improbability paths um     
1:27:46     
and you can use a number of different methods for that um and then of course     
1:27:52     
you have sampling and just like in the diffusion model sampling is     
1:27:57     
important and you have OD and SD sampling so you have ordinary     
1:28:03     
differential equation sampling and then stochastic differential equation     
1:28:08     
sampling and that gives you this uh the different conditions uh then you     
1:28:16     
have the role of time reversal in the backwards process so diffision finish our discussion of diffusion models we     
1:28:23     
discussed the role of time reversal in the backward process in the context of diffusion models     
1:28:29     
given how central the idea of time reversal is for diffusion models it might seem surprising to some readers     
1:28:35     
that it is not needed for flow matching we explain this therefore here in more     
1:28:40     
detail specifically to generate data the diffusion model frame training is     
1:28:45     
learned as a backwards process going from zero to r is greater than zero such     
1:28:50     
that this equation uh once we found such a process we can     
1:28:55     
initialize with a gaussian to obtain a sample from the data distribution um and     
1:29:03     
so in other words we want the stochastic process xarr to generate the probability     
1:29:09     
path p r so we have the stochcastic process we have this probability path     
1:29:16     
that generate gets generated from that and we end up with this     
1:29:21     
um with with flow matching but this is exactly what we were trying to do in generator matching for general markoff     
1:29:28     
processes and in particularly flow matching with flows so we're the markoff     
1:29:34     
process in diffusion models is similar to these what we're doing with flow     
1:29:41     
matching and flows so that's uh kind of giving us and then we can use tools     
1:29:49     
like fauler plank equations to uh you know find because when you're dealing     
1:29:55     
with flows you have a number of tools available to you uh differential equations and other types of estimation     
1:30:02     
estimators so um that's the difference between those     
1:30:07     
two and let me go to this other article here this is archive paper     
1:30:16     
um from 2023 this is flow matching for generative modeling um and I think this     
1:30:23     
is uh maybe the same group uh from meta AI so this is the paper I think it may     
1:30:30     
be the an earlier version of this work but anyways uh we introduce a new paradigm for     
1:30:37     
generative modeling built on continuous normalizing flows or CNFS allowing us to     
1:30:42     
train CNFS at unprecedented scale specifically present the notion of flow     
1:30:48     
matching a simulationfree approach for training CNFS based on regressing vector     
1:30:54     
fields fixed conditional probability paths so you have these probability paths that you're following and that's     
1:31:02     
so flow matching is compar compatible with the general family of Gaussian probability paths for transforming     
1:31:09     
between noise and data samples which subsumes existing diffusion paths at as     
1:31:15     
specific instances interestingly we find that employing flow matching or uh with diffusion pads     
1:31:23     
results in a more robust and stable alternative for training diffusion models so this is a sort of another     
1:31:30     
alternative way to train diffusion models it's a more robust and stable     
1:31:36     
alternative to the u marov model approach that we use so they're using     
1:31:41     
more continuous methods like stochastic differential equations and other tools     
1:31:46     
from you know the study of fluid dynamics and flows furthermore flow matching opens     
1:31:54     
the door to training CNFS of other non-deusion probability paths an instance of particular interest is using     
1:32:00     
optimal transport displacement interpolation to define the conditional probability paths     
1:32:08     
these pads are more efficient than diffusion pads providing faster training and sampling and result in better     
1:32:14     
generalization so optimal transport so it's picking up on the structure of flows and it's using that information so     
1:32:22     
you know with the fusion you're just using a stochastic approach where you     
1:32:27     
know you're kind of recovering things from you're you're working with a lot of     
1:32:33     
uh you know basically noise random noise in this case you're able to actually     
1:32:39     
kind of use methods to your advantage uh training CNFS using flow matching and     
1:32:45     
image net leads to consistently better performance than alternative diffusionbased methods in terms of both     
1:32:52     
likelihood and sample quality and allows fast and reliable sample generation     
1:32:57     
using off-the-shelf numerical OD solvers so theoretically we should be     
1:33:03     
able to do this work with the tools that exist in um in some of these cognate     
1:33:11     
areas so deep generative models are a class of deep learning algorithms aimed at estimating and     
1:33:17     
sampling from an unknown data distribution so we're working with uh so     
1:33:24     
however the restriction to simple diffusion processes leads to a rather confined spaces sampling probability     
1:33:30     
paths resulting in a very long in very long training times and the need to adopt specialized methods for efficient     
1:33:38     
sampling so in this work we consider the general and deterministic framework of continuous normalizing flows cnfs are     
1:33:46     
capable of modeling arbitrary probability paths and are in particular known to encompass the probability paths     
1:33:52     
modeled by diffusion processes however aside from diffusion that can be trained efficiently so such     
1:34:00     
as the noising square matching no scalable CNF training algorithms are known indeed maximum likelihood of     
1:34:07     
training require expensive numerical OD simulations while existing simulation     
1:34:13     
free methods either involve intractable integrals or bias gradients the goal of     
1:34:19     
this work is to propose flow matching an efficient simulationfree approach to training CNF models so this is where the     
1:34:27     
motivation for this is coming from and how it's improving upon some of these other methods so basically using     
1:34:34     
continuous uh methods in diffusion models leads to these sort of problems with     
1:34:41     
tractability and so they're kind of introducing flow matching as a way around importantly flow matching breaks     
1:34:48     
the barriers for scalable CNF training beyond diffusion and sidesteps the need to reason about diffusion processes     
1:34:55     
direct directly work with probability paths so um basically they're using     
1:35:04     
image net 128 samples on a CNF trained using flow matching with optimal     
1:35:10     
transport probability paths so this is their data set they're able to recover these images with this technique uh let     
1:35:18     
me check the chat okay uh Morgan put a     
1:35:23     
YouTube link in what was the YouTube link oh that's just um that's cosign going on     
1:35:30     
right now okay that's like Yeah just Anyway this is you could It's live or they're they're live     
1:35:38     
now i think that's like a reinforcement learning talk okay we'll check that out yeah and and Surro     
1:35:47     
is the is Ed Bdon's lab okay simo i I     
1:35:53     
was thinking Sin Bio you know like our lab is S bio i mean you know Celsius is in bio     
1:36:01     
but Ed actually thinks about neurons right     
1:36:09     
that's which is good which is good yeah u but I don't think I've seen him do you     
1:36:14     
know I I I can't think of any computational projects that he's been     
1:36:20     
involved in you know and I mean and     
1:36:25     
um especially that include biology you     
1:36:31     
know like Michael Lean I can think of you know those Betsy projects     
1:36:38     
like bio electricity Um so very very curious     
1:36:45     
um and he he was another one of these these people like um like Elliot and     
1:36:52     
Celsius who was invited to um Honduras for this this you know these     
1:37:01     
um people with a lot of crypto um trying to trying to gather     
1:37:09     
scientists and Ed Bdon's there     
1:37:17     
but I couldn't think of you know you were trying to think of something that would be would be of     
1:37:24     
interest to do it but his his work is uh is so great i mean it's so     
1:37:31     
um you know such advanced kind of material science or you know just thinking of     
1:37:36     
like the expansion microscopy yeah um you know um did there was a great uh um     
1:37:44     
who did that presentation um     
1:37:53     
uh oh yeah it was um NV go I I'm have a look but there was     
1:38:01     
global neuroch summit uh Friday put on by the student clubs of     
1:38:08     
UPEN and UPEN and Imperial College     
1:38:15     
um although for some reason it seemed to have a lot of Yale students running it but um uh uh     
1:38:24     
the a nice presentation of transcranial     
1:38:30     
uh temporal interference electrical stimulation which is which is also a     
1:38:36     
Bden technique um it's like an original 2016 paper but I I it the the reason I     
1:38:45     
mention it is that it something that Flip Sabies had said who's     
1:38:51     
um got a new implant company so this is like a former Neurolink co-founder um     
1:38:58     
all the co-founders have their own companies now because they've all left     
1:39:07     
um you know that that it's not it's not a phase array     
1:39:14     
technique and um yeah that it's it's it's more     
1:39:26     
um and yeah I I want to try and get this talk in terms of better better     
1:39:32     
explaining the the Bdon um what they call TI     
1:39:39     
TES train temporal interference anyway but um uh sorry I I interrupted     
1:39:50     
it's okay um yeah did we have any other comments or questions about the     
1:39:56     
um the flow matching part of this i mean that you know again I think     
1:40:03     
that's cool you know that um I just you I would want to play with     
1:40:09     
the the pietorrch and see what we can see what we can get from it or you know like     
1:40:16     
again I I was just doing a quick a little quick search and kind of     
1:40:23     
UK bioank diffusion flow matching kinds of things and Um     
1:40:31     
um you know my my advisor is is kind of     
1:40:36     
leads the the brain imaging of UK bio bank so it's also good to see what they're     
1:40:42     
doing um so a lot of a lot of it's focused on making us a spatial template     
1:40:48     
as you can imagine for you know from all that population level data you know     
1:40:55     
because it's we've never had kind of 30,000 MRI scans all collected the same     
1:41:00     
way before you know um and     
1:41:07     
uh the the design of a spatial template is a super important um     
1:41:13     
Yeah super super important for imaging studies especially imaging studies that are actually going to be a low number of     
1:41:19     
subjects um and yeah bring bringing them into a common space is a is a really     
1:41:26     
interesting image normalization problem um spatial normalization problem     
1:41:34     
yeah and and with these nonlinear with these nonlinear techniques in particular it     
1:41:43     
becomes um a very interesting problem of you know you can you can make the images     
1:41:50     
match right you can bring them into exactly the same space but then you've     
1:41:57     
you've destroyed the the individuality of those of those     
1:42:03     
brains right right and and so that that is that is um yeah     
1:42:11     
that is the tension you have in spatial normalization does everybody have good access to um     
1:42:19     
GPUs currently it's not a good access i have the laptop     
1:42:25     
that I g project on it's a RTX it's a RTX 3090 Ti it's a good     
1:42:34     
enough GPU but the problem is it only has 4 GPU space so like I remember that     
1:42:41     
I could get like 7 billion 8 billion parameter models on it but anything more     
1:42:46     
than that would not fit because of the space     
1:42:51     
have have you worked much with um Google Cloud i uh not with cloud i've worked with     
1:42:59     
like collab and like the collab GPUs uh like on the pro plan but even they     
1:43:06     
were like we had to do a project in college where we needed like really good access to GPUs so we tried Google cloud     
1:43:13     
and it was not that because it used to get connect disconnected very quickly     
1:43:18     
and thing is when it gets disconnected you lose everything so you lose like all     
1:43:23     
the progress so far i think there is a way to go through Google cloud and TPU     
1:43:30     
as well but I'm not     
1:43:36     
it is like what happens is so like you have like data saved into your drive you can connect your drive to Google collab     
1:43:43     
and you can what you can keep doing is if you're training a model so you can keep periodically saving back the     
1:43:48     
weights to your drive so that will be saved but if you're running like even sometimes with very heavy models even if     
1:43:56     
you're running inference and in the middle of running inference if it stops then you can't like you have to start     
1:44:02     
again and it's like there there were like some problems with that but uh     
1:44:09     
there was so what we ended up doing for our project was we wanted to do something like we basically wanted to do     
1:44:14     
stable diffusion itself so we ended up using uh yeah we basically used table     
1:44:20     
diffusion to create sprites of uh we were working some in something related     
1:44:26     
to game development so we wanted to make sprites of uh like characters of game     
1:44:34     
characters so for that we used table diffusion and we used like a like a startup website     
1:44:41     
itself that like kind of gave us access to its cloud and basically like it had     
1:44:47     
the model hosted there itself and it had its own servers and you would kind of     
1:44:53     
you would pay like by the amount of like tokens you wanted to use so it wasn't     
1:44:59     
that expensive and we were able to like query and uh like use the models from     
1:45:05     
there so if you're looking for something like that I can guide you there     
1:45:13     
yeah yeah yeah i mean um uh um I'm     
1:45:18     
um I'm fighting with Google Cloud right now     
1:45:24     
[Music] yeah what's your exact use case though like     
1:45:30     
do you are you planning on pre-training or fine-tuning something or playing around it's the     
1:45:37     
um let me show you it's um this is     
1:45:50     
these two yeah they're they're using     
1:45:57     
underneath they're using um open     
1:46:04     
ACC and this package called the veto yeah if you scroll     
1:46:10     
down scroll down there you can see the yeah you know     
1:46:15     
just the kinds of um these are for simulations on on     
1:46:23     
ultrasounds you know so um both     
1:46:28     
um both ultrasound as a brain imaging technique and and focused ultrasound as     
1:46:34     
a um kind of additional technology especially for focal neurom     
1:46:41     
modulation but but the underneath it's using this devito package that's that's     
1:46:47     
open ACC so it's just like like trying to get     
1:46:52     
the GPU acceleration is super finicky and um anyway so I've been trying out     
1:46:59     
just like different GPU images you know like trying to use Nvidia's own images     
1:47:05     
to anyway but um in in general you know     
1:47:11     
if something if I lose my connectivity you know the jobs still still run on the     
1:47:16     
cloud um the problem is I I I still want to get um some of the visualizations so     
1:47:23     
I I just I haven't figured out how to tunnel um tunnel X over the SSH um on     
1:47:32     
these these instances anyway sorry Bradley I I was     
1:47:37     
just asking about everybody's GPU you know uh like like Yeah so yeah I've got     
1:47:45     
a I've got a workstation at the lab that I use to to kind of test things and     
1:47:53     
um yeah okay the software that I was saying that we ended up using so like     
1:48:00     
especially for diffusion it was and for all the models that they have uh there     
1:48:06     
itself it's quite okay that's cool yeah so but these are these are you     
1:48:14     
know specifically about language models uh I think language and image models as     
1:48:22     
well okay okay yeah yeah yeah yeah i you     
1:48:27     
know I I like like this this work or the work I'm doing with Neurocha Berkeley is     
1:48:33     
like it's just different enough that you have to do it yourself     
1:48:38     
oh okay it's like you don't have to use an existing model yeah there's no existing model you know it's     
1:48:45     
it's I mean this isn't even technically deep learning um Oh okay it's like you     
1:48:53     
can you can use it with PyTorch i I haven't tried it i mean I I see on their     
1:48:59     
on their their Slack I see some people doing that but um um this is kind of     
1:49:05     
just like typical like high performance computing computational physics kind of     
1:49:12     
stuff like it's you know a lot of these a lot of these are actually done just with MPI you know it's just just like     
1:49:21     
just add more nodes like slice slice slice up the problem into smaller parts parts and distributed     
1:49:28     
you know it's it it works really well on the kind of batch system clusters that     
1:49:34     
you have in academic labs and I just don't have anymore like like I I I'd have no     
1:49:42     
problem Yeah yeah yeah this is this is totally suited for like uh Yeah the the the     
1:49:50     
clusters i've I've I typically um I I actually I actually had a project you     
1:49:56     
can find this off my old blog but um I had a project called Star City and it     
1:50:02     
it's it's built on this MIT project because their their IT group's called Star and um and it ba it basically it     
1:50:11     
spins up like what looks like an academic cluster on AWS just just just so I can use the same     
1:50:19     
interface anyway sorry Bradley go back to regular     
1:50:26     
schedule programming oh it's fine yeah it's fine uh yeah so great no it's great     
1:50:32     
um so let's uh finish up with I think     
1:50:39     
probably we'll pick a paper here     
1:50:45     
some time i did want to talk about like this uh     
1:50:52     
thing this is from last week we were talking about uh continual cognition or continual     
1:51:00     
sampling of tasks and this and it goes back to the dynamical approach and so     
1:51:07     
this is kind of a diagram that we developed um for the continual AI stuff     
1:51:12     
that you know continual embodied AI stuff that we were working on uh so     
1:51:19     
there's uh this time scale it's kind of like you know if you think about     
1:51:24     
different things that are happening at different time scales in terms of an embodied     
1:51:30     
individual or an embodied system you have a bunch of things happening but     
1:51:36     
they're happening at different time scales so a lot of times we're interested when we do like     
1:51:43     
neurosimulation or you know when we talk about like uh different models of simulating the brain we're thinking     
1:51:49     
about neuronal activity or fast recognition of of     
1:51:55     
stimuli and that happens basically at the several millisecond scale so a lot     
1:52:02     
of times with a single trial of a stimulus we might look at an interval     
1:52:07     
from two to 300 milliseconds or maybe up to 500 milliseconds and then you know we report     
1:52:13     
that and it's like we just assume that this just kind of continues that you see     
1:52:18     
something and you respond and you see something and you respond and so forth but this this sort of time scale can be     
1:52:26     
expanded out in terms of the you know orders of magnitude so uh neuronal     
1:52:34     
activity and fast recognition happen within this 10 to the 10 to the zero with 10 the second order of     
1:52:41     
magnitude of milliseconds and then if you think about this further if you     
1:52:46     
think about naturalistic scenes or or doing things in the world you know you     
1:52:52     
have these sorts of activities that you can do the next stop of course in our     
1:52:57     
time scale was a short coffee break which is uh maybe 15 minutes that's 10     
1:53:03     
the 6 milliseconds so during a short coffee break you might talk to people     
1:53:08     
you might have a conversation you might um think about things like um you know     
1:53:14     
you might drink of course your coffee but you might think about things look at images do other things and there's a set     
1:53:21     
of interactions that is not only much longer in terms of time but then involves a number of cognitive processes     
1:53:28     
and in this continual engagement with the world we have consciousness we have     
1:53:34     
attention and all these things and then of course you move from a short coffee break to something like short-term     
1:53:40     
memory consolidation where you might kind of remember things from your coffee break that you discussed and consolidate them     
1:53:47     
into short-term memory you might hear a song that you can't get out of your mind     
1:53:52     
and you know there are a lot of things in memory consolidation that involve neural activity populations of neurons     
1:53:59     
but then also the stimulus and dealing with that over a longer time scale so 10     
1:54:04     
to the 8 milliseconds is about two hours and so that's about the time scale short-term memory     
1:54:10     
consolidation and then longer term memory consolidation is like a day so that's 10 to the 10th you might go to     
1:54:16     
sleep and then wake up the next day and that's when a lot of long-term longer term memory consolidation happens     
1:54:23     
meanings that you're you're consolidating these memories in a longer term storage and then of course if you     
1:54:30     
go to 10 the 12th milliseconds those are historical events of maybe 31 years so     
1:54:37     
you know you think about historical events living in the arc of history and     
1:54:42     
being able to recall things from that arc of history and so that's a different     
1:54:48     
time scale so this time scale is interesting because there's a lot of stuff happening you have neuro neuronal     
1:54:55     
activity happening all along here but you have this these you know these     
1:55:00     
processes are separated out enough so that you can see that they require uh     
1:55:05     
vastly different methods to interrogate vastly different types of nonlinear processes can happen and so     
1:55:13     
there are two quotes here that are of interest the first one is from Herbert     
1:55:18     
Simon which is that everything interesting in cognition acts above the     
1:55:24     
100 millisecond level so 100 milliseconds is probably like the you     
1:55:30     
know sort of the fast recognition that we think of maybe when we think of a visual recognizing maybe something in a     
1:55:37     
visual scene or you know we're thinking about neuronal activity in 100 milliseconds would be more than enough     
1:55:44     
to describe something like that but everything interesting in cognition     
1:55:49     
happens well above that 100 millisecond level so that we're dealing with things     
1:55:54     
like you know interesting things like interactions and you know longer term naturalistic behaviors and even     
1:56:02     
historical events or longer term memory consolidation and recalling those memories so that's one one quote and     
1:56:10     
then the other quote is as you come closer to a cloud you don't get something smooth but a regular at a     
1:56:18     
smaller scale and that was Ben Mandelro and Mandelro is interesting because he     
1:56:23     
came up with the idea of fractals and fractals are interesting here because     
1:56:28     
you have a lot of self similarity across this time scale like you have neuronal     
1:56:35     
activity happening at a time scale scale of 10 the second but that neuronal     
1:56:41     
activity happens all along this kind this log scale so that for historical     
1:56:47     
events you have many many many instances of neuronal activity it's all happening     
1:56:52     
in the same brain ostensively it's just happening you know you may have memories     
1:56:59     
encoded you have behaviors that that you're engaging in you have neural     
1:57:04     
processes sometimes they adapt to the conditions that you're living in and so     
1:57:10     
all those things are self- similar if you break this time scale down into all the instances of normal activity across     
1:57:18     
this entire time scale you get this these you know repeatable events but     
1:57:23     
they're not repeatable in terms of if you drill down to each event each event is self similar but it's different in     
1:57:30     
the way it operates so that's kind of my thing I wanted to bring up on that     
1:57:38     
um I don't know if we have any comments on that or questions     
1:57:45     
no you know as well as like um sorry     
1:57:50     
just thinking about Michael Evan you know like plenty of organisms are on     
1:57:55     
different time scales than us yeah and you know and how how important that is     
1:58:02     
to consider when you know when trying to judge their their cognit their cognition     
1:58:09     
right um but um yeah I I you know I I think I know     
1:58:18     
what Simon means but uh but I'm not sure that's totally true well yeah I think in     
1:58:25     
his case yeah But uh yeah yeah so um what was that um     
1:58:35     
what was that from oh this was uh something that was so we had a uh paper     
1:58:43     
on continued embody AI where we had a version of this time     
1:58:49     
this figure and then I added these quotes in so this is something that's kind of derivative of some of the work     
1:58:56     
that we've done in that but yeah I mean you know adding the embodied aspect to     
1:59:01     
this you know you have a brain but in a body and you know we don't talk about that a lot in like conventional AI or     
1:59:09     
machine learning but that's something that's very important of course for cognition or or if you want to sort of     
1:59:16     
simulate the brain you pretty much have to have this embodied aspect and this of course a lot of these naturalistic     
1:59:23     
behaviors are embodied i mean you're doing things in the world but you're doing them in a sort of a context or     
1:59:31     
sometimes in a body and you can't really represent them accurately unless you     
1:59:37     
have that body to work with so that was why that time scale is important also     
1:59:44     
because you're doing this continual process of cognition where you know     
1:59:49     
you're doing these naturalistic things and you have these different sort sets     
1:59:55     
of neuronal events and you know it's hard to really kind of separate them out     
2:00:00     
because if you're doing a behavior over three or four minutes you know even if you're doing a     
2:00:05     
rep a repetitive event you know you're doing things like mass practice you're     
2:00:10     
doing things like um learn you know adaptation and so those those kind of     
2:00:17     
responses are going to change over time and so you have a lot of interesting     
2:00:22     
dynamics there yeah uh yeah basically I was saying it's     
2:00:27     
like uh there's like various uh like various types of things I can submit     
2:00:33     
under so uh there's like a lightning talk or a session presentation like a     
2:00:39     
lightning talk would be 5 to 10 minutes and a session presentation would be 30     
2:00:44     
to 40 minutes so is there any like how do I decide which one I should go for or do I     
2:00:51     
try applying to both and seems uh well do you have 30 or 40 minutes of content     
2:00:57     
to deliver i mean it's a lot of stuff to I would probably go for the shorter one but     
2:01:06     
yeah even I was like inclined towards that itself because like I've already done like kind of a lightning talk in     
2:01:12     
the G-Soft lightning talks as well on the same topic so uh that would be good     
2:01:19     
okay and like another thing that I wanted to ask is like basically they have     
2:01:24     
um just a second let me pull it up there like three kind of things that you answer uh to like submit     
2:01:33     
uh like three kind of questions and uh it's like what kind of     
2:01:39     
like basically my thing was do I focus on like what I did last year in the     
2:01:45     
project or do I focus on like how alth lab has been uh like kind of doing the     
2:01:54     
uh project or over the years in general uh probably you know you could do focus     
2:02:01     
on your own work but you could motivate it with what the lab has been doing i mean you know that's usually the way     
2:02:08     
people do it they do like an overview and then drill down into that work i     
2:02:14     
think that would be good okay okay okay okay yeah and there's     
2:02:19     
basically like three questions which is like what are you hoping to get from your presentation what do you expect the     
2:02:26     
audience to gain from your presentation and how will it help better the ecosystem so like because I was just     
2:02:32     
wondering like the track is focusing on like the actual sustainability aspect so     
2:02:39     
like how technical do I do I focus on like the sustainability as well or do I     
2:02:45     
go into like the technical of how I made the project that will you know     
2:02:52     
better working in sustainability any tips or anything     
2:02:58     
um you know again you could do some I mean you probably should give us some background on sustainability part but I     
2:03:06     
think like working in the technical it sounds like it's a technical conference so they're probably Yeah the rest of the     
2:03:12     
tracks sound fairly technical yeah yeah they're probably interested in the technical advances at least you know but but you     
2:03:20     
could also mention broader idea and the scope of it because that is I guess     
2:03:25     
that's Linux right so they're interested in this topic it's just that they're also interested in how the technical     
2:03:32     
aspects to it right so like a B 50/50 balance of kind     
2:03:37     
of both I guess so like even in the how it would help the community would also     
2:03:43     
be like you know how sustainability would help in general and also how like     
2:03:48     
the simulation that we did would help right     
2:03:53     
okay okay yeah i'll I'll I'll make like a draft and I'll also send that as well     
2:03:58     
if anybody has time uh just look over but yeah thanks thanks a lot okay no     
2:04:05     
problem all right so let's talk about this paper     
2:04:11     
this is uh Diddy uh put this in the slack and I don't remember which channel     
2:04:16     
it was but uh this is uh from current opinions of behavioral sciences     
2:04:24     
reinforcement learning bringing together computation and cognition so this is um     
2:04:29     
kind of a review of reinforcement learning as like this cognitive aspect     
2:04:35     
and then this computational aspect so the abstract um a key aspect of human     
2:04:43     
intelligence is our ability to learn very quickly this ability is still lacking in artificial intelligence we've     
2:04:50     
talked about like zero shot and singleshot learning these are things that are um not particularly deep in     
2:04:59     
other words you know you could learn a single shot or a zero shot sort of thing     
2:05:06     
but it isn't really learning you know anything very complicated so this is something that we     
2:05:13     
really are kind of aiming towards but we haven't really achieved this article will highlight recent research showing     
2:05:20     
how bringing together the fields of artificial intelligence and cognitive science might benefit both ideas from     
2:05:27     
artificial intelligence have provided helpful formal theories to account for aspects of human learning in return     
2:05:34     
ideas from cognitive science and neuroscience and also informal artificial intelligence research with     
2:05:40     
directions that make algorithms more humanlike uh for example recent work     
2:05:45     
shows that human learning can only be understood in the context of multiple separate interacting memory     
2:05:53     
systems um and     
2:06:02     
uh um okay uh rather than as a single     
2:06:08     
complex learner this insight is starting to show promise in improving artificial agents learning efficiency     
2:06:16     
so this is a nice way to kind of bring together of the two fields and how you know it sounds like a nice uh review of     
2:06:23     
this and kind of thinking about uh how we can bring together the study of     
2:06:29     
machine and human intelligence um and so they start with     
2:06:34     
how AI supports cognitive research and talking about the field of reinforcement     
2:06:40     
learning in particular and the field of reinforcement learning is often highlighted as an archetype of     
2:06:47     
the success of theoretical approaches to cognitive science computational processes that     
2:06:53     
designed by mathematicians that theoretical guarantees are imported to model how animals modify their behavior     
2:07:00     
when experiencing rewarding orive outcomes it's reinforcement learnings     
2:07:07     
reinforcement learning algorithms have a narrow definition namely they attempt to maximize a specific cost function the     
2:07:14     
discounted sum of future expected reward so they use this kind of optimization     
2:07:20     
technique um and thinking about time so you know     
2:07:25     
the agent has to think about some future reward and what's expected and then they     
2:07:31     
observe rewards in the real world and they kind of align those two so     
2:07:36     
definitely thinking in terms of that uh timeline and um how we can link neural     
2:07:43     
activity with behavior and behavioral outcomes     
2:07:49     
um so such a function would clearly be important for animal survival and as     
2:07:55     
such researchers hypothesized that such RL algorithms might be implemented in the brain so indeed some simple RL was     
2:08:04     
found to be related to learning behaviors characterized as a law of effect and summarized mathematically     
2:08:11     
into a delta rule and early cognitive models of Pavlovian conditioning which     
2:08:16     
is referenced to where better than expected outcomes lead animals including humans to increase the strength of an     
2:08:23     
association between a predictor and an outcome a family of simple reinforcement     
2:08:29     
learning algorithms called model free RL such as Q-learning that's reference     
2:08:35     
three had been very successful at explaining learning in simpler stimulus action learning in humans and animals     
2:08:42     
and that's reference for so there are a number of foundational references there     
2:08:48     
uh reinforcement learning algorithms have been so successful in cognitive neuroscience because they not only     
2:08:54     
capture behavior but also provide a quantitative theory for the underlying processes indeed information carried by     
2:09:02     
the neurom modulator dopamine be modeled as a reward prediction error signal consistent with the RL framework of     
2:09:09     
temporal difference learning those are references one and five the stryatum     
2:09:15     
where dopamine modulates plasticity encodes the choice value or policy and     
2:09:20     
it has even been suggested that distinct parts of the strriatam may have distinct roles as proposed by an arl actor critic     
2:09:28     
model in short there is broad agreement that a stridal dopamineergic system     
2:09:33     
implements a form of model free reinforcement learning in the brain so this is an interesting u kind of     
2:09:41     
section here talking about how we have these models of reinforcement learning     
2:09:46     
and a lot of reinforcement learning is sort of you know it's based on sort of     
2:09:53     
what's going on with dopamineergic signaling in the stryatum and in the     
2:09:59     
cortex and so especially the stryum which you know has like we know kind of     
2:10:06     
what it does in terms of motivations in terms of behavior and we have this link     
2:10:12     
between neurochemicals uh brain anatomy and then behavior so we     
2:10:19     
can actually make that that explicit link using this theoretical model then     
2:10:24     
of course because it's reinforcement learner we can cast it into a computational framework and we can model     
2:10:31     
it in a computer and you know that that that gives us that avenue between sort of a     
2:10:39     
computational model and what's going on in the brain so you know this is     
2:10:44     
something that uh there there's a lot of kind of theory     
2:10:49     
in cognitive science about dopamineergic signaling and what that does uh some of     
2:10:56     
it is I think a little bit too ambitious and gets out ahead of what dopamine actually does and some of the dopam     
2:11:03     
dopamineergic dynamics so many people that claim that dopamine is this you know motivate you know it's it's uh you     
2:11:12     
know basically responsible for all addiction or all motivation and people throw the term around a lot without     
2:11:18     
thinking about the actual dynamics but in any case this is this serves as a nice model or at least getting a getting     
2:11:26     
your arms around what's going on in decision making or some forms of higher     
2:11:31     
level cognition so now we get to this meat of this which is how cognitive science can support AI     
2:11:39     
research so really focuses on reinforcement learning and so it just     
2:11:45     
kind of gives this sort of again like the article we talked about earlier and maybe unlike that article it really gets     
2:11:52     
into the details of how uh neuro research or cognitive research     
2:11:58     
can support a specific type of artificial intelligence and then vice     
2:12:04     
versa so you have different tools uh we have you know we have these     
2:12:12     
benchmarks that we want uh we have different types of analysis of patterns     
2:12:18     
of behavior rather than using aggregate measures uh we also need to be able to     
2:12:25     
dissect the behavior of simulated agents and all of those things kind of     
2:12:30     
rely on this interaction between cognitive science and and     
2:12:36     
reinforcement um and then of course I talk about in um cognitively inspired     
2:12:42     
algorithms using those in AI of course we can learn both about cognition or at least     
2:12:50     
frame our questions about cognition better and then also have this AI aspect     
2:12:56     
to it where we can build biologically inspired or cognitively inspired     
2:13:02     
algorithms um and then we can also look at multiple learning systems in parallel     
2:13:08     
so again we talked about that in the in the first article the bitter lesson article about how the brain is     
2:13:16     
inherently about multiple learning systems or multiple sensory systems so it's inherently multimodal inherently     
2:13:24     
multistream and so that's something that we need we can also bring reinforcement     
2:13:30     
learning to bear on so we have these deep reinforcement learning networks such as     
2:13:37     
DQN which can be successful at sort of these approximations of state     
2:13:44     
spaces and u giving us this in a larger space for representing these multiple     
2:13:50     
learning systems so when I say multiple learning systems I mean that we're doing when we behave     
2:13:57     
we do all sorts of things and we use say multiple memory systems more or less     
2:14:05     
simultaneously to encode information so we're always doing things     
2:14:10     
like we're doing sort of episodic memory encoding which means that we're always     
2:14:16     
exploring our environment we're looking around finding scenes and we're encoding those scenes and then encoding them into     
2:14:24     
memory and then retrieving those we also do procedural memory or     
2:14:29     
procedural learning where we learn maybe how to walk through a maze or we learn     
2:14:35     
some other procedure uh and then that gets encoded as well we can do both     
2:14:40     
episodatic and procedural memory at the same time as well as something like working memory where you hold things in     
2:14:48     
a in a working memory buffer in for shortterm recall so you     
2:14:54     
know if you're trying to remember um a set of words or you're trying to     
2:14:59     
keep your train of thought or you're trying to remember a set of numbers you keep that in working memory and that's     
2:15:05     
indeed a separate anatomical location and process from both procedural memory     
2:15:12     
and episodic memory so understanding all these different types of memory and then understanding     
2:15:19     
their neural bases are all kind of important to put together and then you     
2:15:25     
can also bring that together with reinforcement um and so this is these     
2:15:33     
you know understanding how these work can give us a better handle on how to model this in AI     
2:15:39     
agents um so that's that's the point here um we can also model things like     
2:15:47     
executive functions which is something that we often refer to in cognitive     
2:15:53     
science is happening in the prefrontal cortex and is the sort of learning to     
2:15:59     
learn aspect of cognition so you know executive functions are sort     
2:16:05     
of guiding all this coordinating different learning systems and it's all     
2:16:10     
kind of centered on an anatomical region and you know it's something that     
2:16:16     
we haven't really been able to simulate AI too well we do a lot of like sort of     
2:16:21     
general cognitive functions in AI but we don't model AI in a way similar to how     
2:16:27     
we know cognition is organized so you know there are a lot of things to     
2:16:34     
learn about that and to build models of as well um and then of course neuroscience can inform AI research in a     
2:16:41     
number of ways and has done so in the past and then of course there's this     
2:16:46     
hardware aspect where you know you can make parallels between the hardware of the brain and the hardware of an     
2:16:53     
artificial system uh so yeah this is a nice review it kind of goes over some of the points quite     
2:17:01     
differently than the bitter lesson article I would say and certainly is a lot more grounded in what AI can provide     
2:17:10     
um to cognitive science and neuroscience     
2:17:15     
and if you're interested in references we have a lot of good references in this paper um you know     
2:17:23     
uh references on you know theory and the development of Pvlo being conditioning     
2:17:30     
and reinforcement learning Q learning and other types of things this is an     
2:17:37     
article the framework for mealic dopamine system based on predictive heavy learning that's a classic paper so     
2:17:45     
there are a lot of good references in this paper okay yeah that that in particular is a     
2:17:52     
classic um Yeah who who shared this because this is an old paper uh I mean     
2:17:59     
like again like it's it's it's cool yeah vi put it in the     
2:18:05     
uh Slack and the off or I'm sorry yeah i don't know where they got it     
2:18:13     
i'm just realizing that that's not two authors that that's just one author yeah it's one author it's one author     
2:18:21     
so that is is better known as Ann Collins yeah yeah okay yeah yeah     
2:18:30     
yeah yeah computational cognitive neuroscience     
2:18:35     
lab um so just uh yeah it's a cool     
2:18:47     
um good group all right well I think that's it for     
2:18:53     
this week um let's uh we keep in mind that uh     
2:18:58     
Google Summer code project proposals are due soon oh yeah i just wanted to ask     
2:19:04     
whether you guys have seen my proposal and what your thoughts are and if I can     
2:19:10     
make any changes or anything that you would like me to do additionally     
2:19:16     
well I looked at it i think it looks pretty good so let's go i don't really have any changes i     
2:19:22     
mean you know I think you get over everything     
2:19:27     
okay because actually like even on the GitHub that I saw     
2:19:32     
[Music] um like this is the this not the first time an RL model is coming up right like     
2:19:40     
was like last year we had the LOS model but we keep having different RL models     
2:19:46     
right so I just wanted to like ask whe that's completely fine if I again have     
2:19:51     
an model like that won't hinder my acceptance rate or anything right yeah     
2:19:58     
that's fine yeah keep in mind that those are due soon so it's uh you know if you're if you're still working on it     
2:20:05     
yeah I think the deadline is like the 7th of April so it's next week I think     
2:20:13     
all right thanks see you next week thanks a lot bye see you next week okay take care bye
