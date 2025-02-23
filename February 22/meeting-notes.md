## Meeting Recording

[YouTube link](youtu.be/h2cveq0UMZ4)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114049626908301818)

## NOTES

## TRANSCRIPT
0:00     
hello hello how are you I'm bad hell     
0:07     
Sarah so welcome so let's start with um we had a meeting this week uh dvo     
0:14     
worm uh and we had didn't have any other meetings let me go over the     
0:20     
dorm YouTube channel that's where all our meetings are posted um so we've been     
0:27     
going we'll be on our eighth meeting on Monday this year so we've been covering     
0:32     
a number of topics uh uh from early January we're     
0:38     
talking about epithelial tensegrity uh we talked about a paper     
0:44     
called the ba iorm approach which is the brain body environment uh a model of     
0:49     
celegans that takes all of that into account we've had a couple discussions on developmental hypergraphs this is     
0:57     
something that mahula worked on last year um and he's he's uh wanting to develop     
1:03     
it further this year uh we've been talking about conomics and computational methods for     
1:10     
conomics and celegans uh different types of     
1:16     
patterning codes in the lineage tree uh different topics in evolution     
1:21     
and in bioelectricity and you know so we've we've covered a number of topics in our     
1:28     
weekly meetings and those are on Mondays and then they're posted to     
1:33     
YouTube um then I did a lecture I think it was this squeak where you know I just     
1:41     
I've been working on these slides for a while and I just finally decided to do the lecture     
1:47     
on uh you know on I record the lecture and so this is called interactive     
1:53     
morphog Genesis source and dynamics of moer pattern formation so this is     
1:59     
something that uh involves using Moor interference patterns and other types of     
2:06     
layered morphogenesis and you know to to demonstrate pattern formation to     
2:14     
describe pattern formation and Sh examples from nature where that happens     
2:20     
so that's on our dorm YouTube channel check that     
2:25     
out the first thing is this i' I've had these uh this collection of things for a     
2:31     
while and I wanted to clarify this concept uh as we talk about large     
2:38     
language models but also as we talk about bio inspired models and think about uh what they call shot learning in     
2:47     
U in well in deep learning but in other types of learning models so this is the definition from     
2:54     
Wikipedia for zero shot learning so zero shot learning is a     
2:59     
problem set up in deep learning where at test time a learner observes samples     
3:05     
from classes which were not observed during training it needs to predict the class they belong to so this is where     
3:12     
you either have some sort of generalization or you have unsupervised     
3:17     
learning where you have not seen this or the model has not seen this before and you have to classifi     
3:25     
correctly classify so the learner observes samples from classes which were not observe during training and needs to     
3:31     
predict the class that they belong to the name is a play on words based on an earlier concept of onshot learning which     
3:38     
we'll talk about in a minute which classification can be learned from only one or a few     
3:44     
examples so zero shot methods generally work by associating observed and     
3:49     
non-observed classes through some form of auxiliary information which encodes     
3:55     
observable distinguishing properties of objects uh for example given a set of images of animals to be classified along     
4:03     
with auxiliary textural descriptions of what animals look like an artificial intelligence model which has been     
4:09     
trained to recognize horses but has never been given a zebra and still recognize a zebra and it also knows that     
4:17     
zebras look like striped horses so this is K both sounds like you can do some     
4:22     
sort of transfer learning but or generalization but also can get you into trouble if you don't if you think that     
4:29     
some something looks like something and it doesn't so if you have you you know you might fall prey to false positives     
4:35     
but as a shortcut to learning it's uh fairly effective so this is a problem     
4:41     
that we have you know it's an outstanding problem in computer vision natural language processing a machine     
4:47     
perception so I don't mean to like do an exhaustive review of it here but I     
4:52     
wanted to talk about this and so we can uh get it you talk about it get it clear     
4:57     
in our minds what this is the first paper on zero shot learning     
5:02     
and natural language processing appeared in 2008 at the tripa AI but the name     
5:09     
given to the learning Paradigm there was datalist classification uh the first paper on     
5:15     
zero shot learning in computer vision appeared at the same conference under the name zero data learning the term     
5:23     
zero shot learning itself first appeared in the literature in a 2009 paper from palatucci Hinton pommer and Mitchell at     
5:31     
nips 09 which is now NPS this terminology was repeated later in     
5:37     
another computer vision paper and the term zero shot learning caught on as a     
5:42     
takeoff on one shot learning that was introduced in computer vision years     
5:47     
earlier so in computer vision zero shot learning models learned parameters from     
5:52     
seeing classes or observed classes along with their class     
5:58     
representations and rely on representational similarity among class labels so that during inference     
6:05     
instances can be classified into new classes so you're observing a subset of things you're     
6:13     
exposed to a wider set of things and the model has to generalize say from horses     
6:20     
to horses with stripes which are now zebras so you can have this new category     
6:25     
and give it a new label the natural language processing the key     
6:32     
technical Direction developed Builds on the ability to understand the labels that is represent the labels in     
6:39     
the same semantic space as that of the documents to be classified so these     
6:45     
labels are in the semantic space and they're connected to one another this     
6:50     
supports the classification of a single example that observing any annotated data that feris form a zero shot     
6:57     
learning so this is where we don't have have any uh labels at all so that's the     
7:04     
Puris form of zero shot learning the original paper made use of     
7:09     
the explicit semantic analysis representation but later papers made use of other representations including dense     
7:17     
representations this approach was also extended to multilingual domains find Entity typing and other problems     
7:25     
moreover Beyond relying solely on representations the computational approach has been extended to depend on     
7:33     
transfer from other tasks such as textual entailment and question     
7:39     
answering okay so yes then um the original paper also points out that beyond the ability to classify a single     
7:48     
example when an collection of examples is given with the assumption that they come from the same distribution it is     
7:55     
possible to bootstrap the performance in a semi-supervised manner or what they     
8:00     
call transductive learning so this is where we have this     
8:07     
these three components we have the uh visual or the image     
8:14     
properties the features a feature space then we have our labels which is     
8:20     
embedded in a semantic space and then we have this distribution which is the distribution     
8:27     
of these examples and their likelihood or their probability so this is kind of     
8:34     
an interesting um kind of way to think about this this is where it comes from so that's zero shot     
8:46     
work now we talk about oneshot learning so this is oneshot learning and again     
8:51     
this is an object categorization problem and so whereas most machine learning based object categorization algorithms     
8:59     
require training in hundreds or thousands of examples and so again with zero shot learning one shot learning is     
9:05     
sort of a shortcut to learning and again it could result in a lot of false     
9:10     
positives but it can also help you in cases where you need to pick up uh you     
9:16     
know you need to figure out what something is one shot learning aims to classify objects from one are only a few     
9:22     
examples so this is where you're not doing unsupervised learning you're not doing Raw General ation where you're     
9:30     
just trying to you know find a new thing from no examples you actually have one     
9:36     
or maybe a few examples you have a very sparse set of data to learn from and     
9:41     
then you have to learn correctly and you know that's you know that's up to the     
9:47     
model that's up to the model's capabilities the term fuse shot learning is also used for these problems     
9:53     
especially when more than one example is needed so the ability to learn object     
10:00     
categories from a few examples at a rapid Pace has been demonstrated in humans and so this is something that we     
10:07     
see in development a child learns almost all the 10 to 30,000 object categories     
10:12     
in the world by age six so uh in development you acquire the semantic     
10:18     
space and you acquire these labels for things and as we talked about this in     
10:23     
the data sets that exist for children or that were acquired from children where     
10:29     
you have these natural scenes and then you also usually have some uh semantic     
10:34     
component or some complement of linguistic data that are attached to that so we have labels as well as uh     
10:42     
images and features this is due not only to the human's mind human mind's computational     
10:48     
power but also to its uh ability to synthesize and learn new object     
10:53     
categories from existing information about different previously learned categories     
11:00     
given two examples from two object categories one an unknown object composed of familiar shapes the second     
11:07     
and unknown amorphous shape it is much easier for humans to recognize the former than the latter so it's easier     
11:15     
for us I guess at least in development to uh recognize an unknown object     
11:22     
composed of familiar shapes and of course we know this from cognitive science where you give people these     
11:28     
different GE ometric Primitives and they can identify them and put them together     
11:33     
and you know give it a name and then the second is an unknown amorph shape so if it doesn't     
11:39     
contain these geometric Primitives they don't uh people can't necessarily get a     
11:46     
fix on what it is or what it might be and so again you have this potential for     
11:51     
false positives but it's also something that you know you can fit into these     
11:57     
broader categories into these Broad um schema that we have so it is much     
12:04     
easier for humans to recognize a former than the latter suggesting that humans make use of previously learned     
12:10     
categories when learning new ones so this is about category learning where     
12:15     
you have objects they have familiar attributes those features then can     
12:21     
generalize in terms of like knowing what features are combined in what way and     
12:26     
then expanding that semantic space or that category space to new things so     
12:33     
you know categories are necessarily linked you know so you're using a new you're using previously learned     
12:40     
categories to uh form new categories and they're linked in that way the key     
12:46     
motivation for solving oneshot learning is that systems like humans can use knowledge about object categories to     
12:53     
classify new objects so they're you know making this analogy from human     
12:58     
development from Human learning and so as with most     
13:03     
classification schemes one shot learning involves three main challenges so the first is representation how should     
13:11     
objects and categories be described then there's learning how should such descriptions be created and then there's     
13:18     
recognition how can a known object be filtered from enveloping clutter     
13:23     
irrespec of a reclusion Viewpoint and lighting so recognition is isolating the feature learning is uh sort of the the     
13:32     
sort of schema for creating new descriptions and then representation is how do you merge that     
13:38     
feature space in the category space uh on shot learning differs from     
13:44     
single object recognition and standard category recognition algorithms and it's emphasis on knowledge transfer or     
13:51     
transfer of learning which makes use of previously learned categories all right so again you know     
13:58     
there different things like model par thinking about the model parameters uh we want to reuse model     
14:05     
parameters there's a similarity between old and new categories categories are first learned on numerous training     
14:11     
examples then new categories are learned using transformations of model parameters those exist initial     
14:17     
categories we selecting relevant parameters for classifi then there's feature sharing     
14:24     
which allows us to share parts or features of objects across categories     
14:29     
and the concept of mutual information is important because those uh features uh     
14:36     
or you know those features are going to have some mutual information that Mutual information is going to make that     
14:42     
linkage between the old and the new category so if you have like for example     
14:47     
these geometric Primitives and they exist in this new category then that classification will     
14:54     
be based on sort of the the shared uh geometric Primitives so a dog     
15:02     
category for example may be learned in one shot from previous knowledge of     
15:08     
horse and cow categories because dog objects may contain similar distinguishing patches or these     
15:14     
geometric Primitives so you wouldn't classify a dog in the context of like a marine invertebrate you'd classify a dog     
15:23     
in the context of a quadrip a quadrupedal animal or horse or a cow and     
15:30     
so we have this uh you know there are different ways you can do this sort of     
15:36     
transfer but you know it's it's it's you know it's the way     
15:42     
it's usually done in um models the machine models then there's contextual     
15:49     
information and this appeals to Global Knowledge of the scene in which the object appears such Global Information     
15:56     
can be used as frequency distributions and it can random field framework to     
16:01     
recognize objects alternatively alternatively context can consider camera height and scene geometry     
16:08     
algorithms of this type have two advantages first they learn object categories that are relatively     
16:14     
dissimilar second they perform well in ad hoc situations where an image has not been hand cropped or     
16:21     
aign so this um has a lot to do with basian uh Theory and again with we have     
16:29     
this probabilistic or likelihood model so basy and oneshot learning algorithms     
16:35     
represent the foreground and background of images is parameterized by a mixture of constellation models during the     
16:41     
learning phase the parameters of these models are learned using a conjugate density parameter posterior and     
16:47     
variational basian expectation maximization or vbe in this stage the previously learned     
16:54     
object categories inform the choice of model parameters by a transfer by     
17:00     
contextual information for object recognition on new images the posterior     
17:05     
obtained during the wording phase is used in a basy and decision framework to estimate the ratio of object given test     
17:14     
or train so with prob the U likelihood of an object given test or training to     
17:21     
you know the ratio of that to the likelihood of background clutter given tester train so basically you're testing     
17:29     
background versus the object or the signal versus the noise given your training data set and your testing data     
17:36     
set p is the probability the outcome okay uh so this is basically     
17:44     
more about the basian framework and I'll skip that now I'll go to these last two     
17:49     
things that I wanted to talk about this is a medium post on fuse shot     
17:56     
learning and so we have zero shot learning which is learning from sort of     
18:03     
denovo we we're learning from other categories completely we're not observing anything we have one shot     
18:09     
learning or maybe a few shot learning where we kind of pick up uh from maybe a few examples a very sparse set of     
18:17     
examples and then we have endot learning which is you know where you have to add in examples and you keep adding in     
18:24     
variation in the observations of a thing so if we want to classify     
18:29     
um a specific breed of dog we need to have uh quite a few more examples than     
18:35     
just of a dog and so this is where we have this     
18:41     
distinction between sort of this unsupervised learning this you know sparse SE supervised learning and then     
18:49     
supervised learning where we have a rich set of examples and the idea is that the model     
18:55     
sensitivity to that is what people were always trying to optimize them so in the     
19:01     
field people are always advertising zero shot learning or one shot learning is really the standard     
19:07     
but it's interesting to think about some of these examples you know with biologically inspired models where you     
19:13     
have you know maybe the case where it's better to have unshot alert than to have     
19:20     
zero shot Le and so you know just something to think about any case this article in medium     
19:27     
this is few shot learning this is we em um and this is an article on F shot     
19:34     
learning specifically fot learning stands out as a revolutionary progression in the field of machine     
19:40     
learning allowing models to undergo training using a minimal number of labeled     
19:46     
examples in contrast to traditional supervised learning which relies heavily on abundantly labeled data few shot     
19:54     
learning addresses this challenge by Furnishing models with only a small set of label examples per class this     
20:01     
strategy involves utilizing a support set for training episodes enabling models to Excel on tasks where data     
20:07     
avity availability is restricted particularly in domains like clinical natural language processing or NLP     
20:16     
clinical NLP this exploration delves into the transformative potential of f shot learning in the context in NLP the     
20:25     
article covers various aspects including an overview of fuse shot learning um the mechanisms behind fuse     
20:33     
shot learning uh and fuse shot learning specifically relevant to     
20:39     
NLP in NLP we use few shot learning or zero shot learning and there's a     
20:44     
comparison there then there's narrow AI defining General AI which of course we     
20:51     
talked about General AI last week and sort of how that can be distinguished from narrow AI special ways of goal of     
21:00     
research um then insights into Data labeling and exploration of data labeling     
21:11     
tools um okay yeah let's talk about the     
21:18     
examples of f shot learning in NLP so these are meta learning approaches and the first example are     
21:25     
what they call Siamese networks so Coke all 2015 introduced     
21:31     
Siamese networks to determine the likelihood of two data examples belonging to the same class these     
21:37     
networks use identical multi-layer neural networks to process examples creating embeddings the distance between     
21:44     
these embeddings as computed and FedEd into a comparison Network for classification so in training pairs of     
21:51     
examples of randomly chosen or a broader set of training classes encouraging generalized learning in testing entirely     
21:59     
different classes are used aligning closely with the spirit of nway kshot tasks so this is where you have     
22:06     
multiple um ways that you can view the thing and then you have different shots     
22:12     
of tests so there different ways you can sample the data as well as being exposed     
22:19     
to the data um applied applications applied in NLP tests such as question answering and     
22:26     
text classification focusing on semantic similarity or dissimilarity between text     
22:32     
inputs the next example is prototypical networks so Snell 2017 introduced     
22:39     
prototypical networks addressing data imbalances by creating class prototypes     
22:44     
for embedding averaging classification is based on the similarity between prototypes and     
22:50     
inquery embedding calculated as negative multiple of ukian     
22:56     
distance so the application of this is used to address data and balances and applied to name entity recognition tasks     
23:03     
in a variation proposed by bin at all then we have matching networks so     
23:09     
vineel at all 2016 propos matching networks predicting one hot encoded     
23:15     
labels for our query set through a weighted sum of supports set labels weights are determined by similarity     
23:22     
computed through cosine similarity between embeddings generated from separate networks for supported     
23:29     
examples this is employed for nway kshot learning tasks predicting labels for the     
23:34     
query set based on the support set then the challenge is that it's     
23:40     
acceptable to data imbalance where where classes with more support examples May     
23:45     
dominate then you have non metal learning appr purches such as transfer learning     
23:52     
prompting and actually latent text embeddings     
24:00     
and that's all for that so that's some examples of how this     
24:09     
works and then finally I want to get to this paper here this is few shot     
24:15     
learning it's a survey of the field so this is a comprehensive survey     
24:21     
of few shot learning Evolution applications challenges and opportunities this is a is song Ting     
24:29     
Wang s Mond and giot sahu so this     
24:34     
is uh the abstract hot learning or FSL has emerged     
24:40     
as an effective learning method and shows great potential despite the recent creative works and tackling FSL tasks     
24:47     
learning valid information rapidly from just a few or even zero examples Still     
24:53     
Remains a serious challenge in this context we extensively investigated 200     
24:58     
more than 200 latest papers on FSL published in the past three years and we     
25:04     
to present a timely and comprehensive overview of the most recent advances in FSL along with impartial comparisons of     
25:11     
strengths and weaknesses of the existing works for the sake of avoiding     
25:17     
conceptual confusion we first elaborate and compare a set of similar Concepts     
25:22     
including F shot learning transfer learning and metal learning so metal learning and transfer learning learning     
25:28     
are distinct from F shot learning furthermore we propose a novel taxonomy to classify the existing work     
25:35     
according to the level of abstraction of knowledge in accordance with the challenges of FSF to enrich this survey in each     
25:43     
subsection we provide an in-depth analysis and insightful discussion taking computer vision as an example we     
25:50     
highlight the important application of ffsl covering various research hotspots     
25:56     
finally we conclude the survey with unique insights into the evolution of these     
26:02     
Technologies and kind of hope that that gives us guidance for the     
26:10     
future so let me see if we have let me see if I okay so this is     
26:16     
kind of getting into the concepts um talking about FSL which is fuse shot learning and so     
26:25     
they say what is fuse shot learning the concept of shot learning is inspired by the robust reasoning and analytical     
26:32     
capabilities of humans and is widely found in Edge Computing scenarios so F     
26:37     
shot learning is taken from humans but I think we could say that you can also find examples in other animals and other     
26:45     
learning organisms and you know maybe that's something that is done better in     
26:52     
other organisms other model organisms or we can take you know the look at the     
26:58     
variety of few shot running across organisms that would be kind of an interesting topic to follow up     
27:04     
on in 2020 Wang at all and that's reference five here give a detailed     
27:09     
definition of FSL through experience task and performance of machine learning which is one of the most recognized     
27:16     
definitions so far so that definition is a computer program is said to learn     
27:22     
from experience e with respect to some classes of task T and performance     
27:28     
measured P if its performance can improve with e on T measured by     
27:34     
P so is it's improved by experience on some task measured by the     
27:42     
performance measure okay it is worth mentioning here that e and FSL is very     
27:47     
small so experience is small the task is variable or maybe it's the same for your     
27:53     
specific measure of it but you know you it would vary across test     
27:59     
and then your performance measure would vary across tasks as well so your performance measure will vary by task     
28:06     
and if experience is variable then it varies by that as well um in recent years relevant     
28:14     
neuroscientific evidence in citations six and seven has shown that innate     
28:19     
human capabilities are related to various memory systems including parametric slow learning neocortical     
28:26     
systems and non-parametric fast hip aamp Learning Systems so they're talking     
28:32     
about slow learning in neocortex and fast hipic hippoc cample learning which     
28:38     
correspond to fsl's database slow learning and feature based fast learning so this is where you have this database     
28:46     
learning versus this feature based learning and F shot learning and then that corresponds with different parts of     
28:53     
I guess the human brain um to better understand FSL it is necessary to     
28:59     
introduce two concepts so we already talked about nway kshot which is a open     
29:05     
type of problem and then the other is cross domain fot learning so the nway     
29:10     
kshot problem is often used to describe the specific problems encountered by F     
29:16     
shot learning in this case the support set represents the small data set used     
29:21     
in the training phase which generates reference information for the second phase of testing the quer say is the     
29:28     
task on which the model actually needs to predict notice that the query class set classes never appear in the support     
29:35     
set so classic oneway kshot represents support set within categories and case     
29:41     
samples per category so you have categories with samples in each category then the whole task by way of     
29:48     
that as n times case samples as thus nway one shot learning     
29:55     
represents one shot learning and nway zero shot learning represents zero shot     
30:00     
learning so you would have in nway one shot learning you would say have 10 CL     
30:07     
uh categories one sample per category giving you 10 samples and then nway zero     
30:14     
shot learning would be 10 categories with zero samples in each giving you 10     
30:22     
samples of classes with nothing as a reference point and you would have to     
30:27     
generalize the concept of cross domain originates from transfer learning which refers to     
30:34     
the transfer of the knowledge from The Source domain to the Target domain there usually exist domain gaps between these     
30:40     
domains cross domain F shot learning integrates the features of cross domain and fuch shot learning it is a     
30:47     
challenging direction that has recently     
30:55     
emerged so this shows one of the knowledge graphs here for few shot learning uh one shot learning and zero     
31:02     
shot learning are keywords to relate the main advances and research directions uh     
31:07     
in the field of f shot learning recent in the recent last three years so this shows examples     
31:15     
of these things in the literature be clear this is one shot     
31:22     
learning this is zero shot learning and this is a literature graph we're looking     
31:27     
at different topics related to these different types of learning so of course     
31:32     
you have machine learning uh gesture recognition neural networks around one shot learning you     
31:39     
have computer vision in there you have zero shot classification you have sanese networks     
31:45     
which you talked about with online learning we have information     
31:52     
literacy we have supervised learning image recognition     
31:59     
uh yeah so this is just kind of a a literature search and then the number of     
32:04     
FSL related papers published in prestigious journals from 2010 to the     
32:10     
first half of 2021 so this looks like it's becoming a Hot Topic with I guess     
32:17     
probably hundreds of Publications at this point in 2011 there were less than 20 so gives them an idea of what people     
32:24     
are thinking about in the field     
32:34     
so what is meta learning and how is it different from F shot learning So Meta     
32:39     
learning is a general learning Paradigm that provides training on tasks and episodic training     
32:45     
mechanism um they talk about this in figure four meta learning focuses on     
32:50     
improving generalization for unseen tasks using prior knowledge if prior     
32:55     
knowledge is used to teach the model how to learn on specific tests metal learning can be regarded as a variant of     
33:01     
FSL it is emphasized that metal learning is not equivalent to FSL but FSL should     
33:07     
rather be seen as the ultimate goal so you might use metal learning to get to FSL um but it isn't equivalent to that     
33:15     
it aims to achieve robust generalizations without relying on a large scale of data sets and by dual     
33:21     
sampling of data and task space meta learning is enabled to construct a large number of auxiliary tasks     
33:28     
related to the Unseen task so this is where you can improve the model's performance by using metal learning     
33:36     
um and it involves a um a number so it involves three     
33:42     
steps stage one is where you find the learning algorithm and see if it can produce a     
33:50     
specific function so you have these tasks and they should produce a function and you can use this for you     
33:57     
know you can use learning rates initial parameters and net Network architectures to derive this function from the     
34:04     
tasks stage two is where you define a loss function using the tasks so you     
34:10     
have task one you have the prediction and you compute the difference so you     
34:15     
take performance versus a prediction observe versus predicted and you compute     
34:20     
the difference there and that's your loss function and again you this involves     
34:25     
Network architectures initial paramet in learning room and then stage three is where you     
34:32     
find the parameter that can minimize the loss function so you use some classifier that can minimize the loss function this     
34:39     
involves gradient descent and reinforcement so that's what meta learning or you know meta learning is     
34:45     
and there different variations on it like meta reinforcement learning meta video detection and so on so I think     
34:52     
that's enough on that topic I just wanted to go over that and and I wanted to think maybe more broadly about this     
34:58     
now that we have some of the fundamentals down on that um so for example you know we're thinking about     
35:04     
models you know we're thinking about how they learn but we're also thinking about     
35:10     
how we have to train them to get them to learn and so you know we talked about developmental data we' talked about how     
35:17     
develop we' talked previously about how development is different from say like adult learning that you know in adult     
35:23     
learning or at least in a in a model that we have that's analogous to learning we would use a number of     
35:30     
different um you know we just present examples say of images we might use an     
35:36     
image database with labels or without labels and we assume that the model can General is and then of course we've seen     
35:44     
these developmental data sets where you have these labels but you have to generate new labels and we usually use     
35:50     
this continuous scene data where you know it's very a very different form of     
35:56     
exploration than in the adult analogous data sets and then of course the whole     
36:02     
question of how do we synthesize categories and how to models and     
36:09     
organisms but also models recognize things that can be categorized and I     
36:15     
mean anything can be categorized but it seems like there's this bias towards things with a clear structure and     
36:21     
perhaps a structure that's familiar to the model or the ordinance so it's not that you have this amorphous that can     
36:28     
easily classified and you know that's uh just kind of a matter of decomposing the     
36:35     
object into different smaller pieces that are similar to other things that have been     
36:41     
learned but also having this sort of semantic space and this feature space that are linked and having that as a way     
36:49     
to as a reference point so okay so do we have any thoughts     
36:55     
on that I mean I I certainly think you know like language learning in in kids     
37:04     
is a good example I think it might be a good example of that there there's actually several Learning     
37:11     
Systems in a in a developing child yeah and and that they are sharing     
37:21     
some some you know larger     
37:29     
um context space     
37:35     
um what we know is that they seem to be quite good at     
37:43     
kind of one shot learning um or you     
37:49     
know um as well as like s super     
37:55     
rapid super rapid learning that reflects you     
38:02     
know where it's supposed that there's there's some inductive bias that's um     
38:11     
you know it it's probably biology and then     
38:17     
it becomes something it becomes something else that's     
38:23     
used or it something that becomes uh     
38:28     
more conceptual or you know again like you you got that mix of kind of     
38:34     
cognitive researchers who aren't kind of worried about the neural     
38:40     
representation and so they're they're just dealing with the the     
38:46     
behavior um they're they're impressed by the the     
38:53     
young child's yeah General ization and and     
38:59     
other other kinds of um you know behaviors when when put     
39:06     
in experimental scenarios     
39:12     
right I mean this is this is why cognitive development is so interesting or you know should should be of more     
39:18     
interest to all these um metal     
39:23     
learning groups and and     
39:31     
yeah you know it's like it's like continual learning is is     
39:37     
something that seems to become a field     
39:42     
because neural networks didn't work and and you know cognitive     
39:50     
development is the certainly developmental psychology is more the field of     
39:58     
like you know he here's here's here's a biological neural network that's doing     
40:05     
it that that is that is is always on     
40:12     
is learning multiple tasks and and you know and and relating them more     
40:20     
and more um uh not even necessarily when they     
40:26     
should be related you know and you know again it's always it's always     
40:34     
fascinating to uh as PJ did right um is     
40:40     
always fascinating to listen to kids um     
40:46     
playing and especially playing make believe yeah um you know because it's     
40:54     
uh yeah fast f ating window into how they connect things and how they think     
41:02     
things work um and yeah all all sorts of all sorts of     
41:10     
insights into um you know potentially how um how it's working behind the     
41:18     
scenes but of course you know it just needs more it's actually really difficult to     
41:23     
bring out experimentally right but but you can just tell that there's there's a     
41:29     
lot more going on than on our than our uh uh you     
41:36     
know yeah that are very abstract     
41:41     
maths right Al interested in kind of how this might be linked to a generalized     
41:48     
mechanism of associated associative learning or heavy in learning um and I     
41:54     
you know I don't know uh to think about that that a little bit as well um but     
41:59     
yeah there are a lot of connections here with different Learning Systems so like you know the Assumption here was we're     
42:06     
just talking about a single model and you know you might have multiple learning systems that are     
42:12     
engaged simultaneously so if you have a like a semantic space that's a language     
42:18     
circuit or a language model and then you have the you know the visual examples or     
42:23     
the computer vision examples which is a a learning a visual module then there     
42:29     
are other things as well um there other systems that are involved with that of course there is memory which is the     
42:35     
hippocampal circuit there's spatial cognition there's uh movement um so you know when we     
42:42     
incorporate embodiment into things so that there are a lot of systems that are engaged     
42:48     
simultaneously but I mean we're just talking about a single model here but     
42:53     
you know in a organism you'd have multiple models s     
42:59     
for sure for sure yeah so SAR asked based on     
43:04     
the same concept inshot prompting and oneshot prompting are heavily used in prompt engineering for larger language     
43:11     
models as well so yeah that's a that's a thing I didn't talk about the prompting there was a section I think in the     
43:17     
review on prompting so um I'll post the     
43:23     
link to the papers in the slack and then put it in the description the video as     
43:28     
well so you can you can read more on     
43:34     
that okay uh the next thing I wanted to talk about a series of posts by Melanie     
43:41     
Mitchell and I believe this is on her substack and this is on large language     
43:48     
models and World models we talked about this I think last time we've kind of been following up on this topic um over     
43:56     
a number number of weeks so we talking about large language models and reasoning so U this is on large language     
44:05     
models and real world models this is part one I'll talk about part two next     
44:10     
how do larger language models make sense of their quote unquote worlds so this is where you have um a model and then it's     
44:18     
embedded in the world and they have to make sense of the world through that uh     
44:24     
through some sort of world model we talked about World models could be kind of going back to good old fashion AI or     
44:33     
symbolic models and so in that sense it's not really anything new on the     
44:39     
other hand you can also have World models that are you know just kind of a a list of     
44:46     
things outside of the experience of that model so you know if you think about     
44:51     
generalization we just talked about zero shot or one shot or a few shot learning     
44:57     
World model can improve upon that performance on those kind of tasks because it gives you a framework     
45:04     
for inferring things in semantic space so this is uh kind of a reflection on     
45:12     
some of this some of these World models and how they might apply to larg language     
45:17     
models so she talks about AI brittleness in the before times so in the long ago     
45:23     
times before a large scale generative AI came out of the seen machine Learning Systems had some problems um the first     
45:31     
is often they didn't learn the general concepts we were trying to teach them but rather solve problems using     
45:37     
shortcuts or Surface her istics so one example of this is where some     
45:43     
researchers tried to train a deep neural network to classify skin lesions in photos this is an example um and they     
45:51     
tried to classify them into benign or malignant obviously we want to know the difference we use different features of     
45:58     
the images to get an answer and then match it with the real world     
46:04     
diagnosis while this network performed well on these kinds of photos it was trained on the researchers noticed a     
46:11     
problem so that problem was the algorithm appear more likely to interpret images with rulers so you see     
46:18     
that there's an image here and this is a clinical context where you put a ruler there to measure the size of the you     
46:24     
know they'll put that in the image so that the lishan can estimate the size of     
46:29     
luian um and the rulers were in the images um they were more likely to     
46:36     
interpret images of rulers as malignant why in our data set images     
46:41     
with rulers are more likely to be malignant thus the algorithm inadvertently learn the rule that rulers     
46:47     
are malignant so when you have a ruler here um and you know maybe they're     
46:52     
putting the ruler there because they want to measure because they notice that it's generally bigger than other lesions     
46:59     
and they want to measure it they put it in the image so this is an artifact of the image acquisition so you're     
47:05     
acquiring clinical images you have the ruler which is a relevant NE not necessarily relevant to the diagnosis     
47:12     
although it does have some correspondence of the diagnosis there is some correlation there simply because of     
47:18     
practice it's classifying everything with a r was malignant now of course the problem there is that it's not always     
47:25     
going to be malignant so you know again we're getting these false positives where we shouldn't be     
47:32     
because the model is taking some Shortcut and so that introduces a problem and that is     
47:40     
if you're acquiring data in the real world and you see something associated with something else you know it's it's     
47:46     
easy enough to say that well of course that's a a feature of a certain outcome     
47:52     
but it may not be that simple so you know basically the Network learned a useful heris but it wasn't that useful     
48:01     
in the end um the network didn't understand what Aion is or motivated the researchers to train it or why rulers     
48:08     
might be seen in particular images or anything else about the world so this is where you know we want to introduce this     
48:16     
world model theistic shortcuts are okay but they also have to be weighed against     
48:23     
realities of the world that that image is taken from     
48:28     
so such teristic shortcuts weren't limited to visual data in 2019 one group     
48:33     
reported on using a neural language model to determine whether one sentence logically implied another the model     
48:39     
performed very well in a data set designed toest this General ability but it turned out that the model's high     
48:45     
performance reli on superficial syntactic Properties or this uh this     
48:51     
syntax space uh on how on such as how the words in one sentence over AP those     
48:57     
into the second sentence when the network was given sentences for which it could not take advantage of this her     
49:02     
istic its performance decreased dramatically so this is where it picked     
49:08     
up on some feature of a sentence structure and it use that to to classify     
49:15     
things and of course it doesn't generalize because that that structural feature isn't     
49:24     
available in a language you could imagine train trting a model on on like some structure of poems and then     
49:32     
unleashing it on a corpus of text that doesn't involve poetry but instead involves like non-fiction or even     
49:39     
fiction literature so it's just a different style of writing and where where it's     
49:45     
trained in one case it can't distinguish between different styles of writing     
49:50     
basically another group wrote about similar brittleness in a deep reinforcement learning system that it's     
49:56     
success learned to play the Atari video game Breakout the system was trained by     
50:01     
being given video frames from the game and then choosing actions moving a     
50:06     
paddle horizontally to bat a ball in order to hit exploding bricks while train system seemed to be a highly     
50:12     
skilled at the version that's been trained on researchers showed that small changes in the game such as moving the     
50:19     
paddle vertical position by a few pixels CA Trad uh the measure performance to     
50:24     
plummet it seems like the original system had learn the abstract notion sorley there's     
50:30     
some there's something including the um the text on the yeah I know on the right     
50:36     
that's the way I captured it yeah oh okay I see I     
50:41     
see it seems that the original system were in the abstract Notions of paddle ball or     
50:47     
bricks uh and it was using the patterns of pixel configuration specific to the     
50:53     
original game to make those decisions so it's using these charistics to learn     
51:00     
to generalize and the problem with using charistics is it doesn't have the proper     
51:06     
context it doesn't have these World models and so now we're having these     
51:11     
debates about emerging World models um and you know there's some     
51:18     
debate as to whether models are able to learn World models on their own     
51:24     
so uh but there's a fiery debate in the eii community and how these systems     
51:29     
achieve their high performance and we're talking here about modern systems modern larage language models have they     
51:36     
basically memorized their training data and then retrieve it in some approximate way to solve new problems have they     
51:43     
learned much more numerous and detailed yet still brittle heuristic shortcuts or     
51:49     
do they have something like a more robust World model that humans seem to use to understand and act in the world     
51:55     
and so ilot has argued that these systems have learned robust Ro models but that's not     
52:03     
um that's not a consensus view so his case for this is that when     
52:09     
we train a large neural network to accurately predict the next word lots of different texts it's a learning it's     
52:15     
learning a world model this text is actually a projection of the world what the neural network is learning is more     
52:22     
and more aspects of the world of people of The Human Condition your hopes streams and motivations the     
52:29     
neural network learns a compressed abstract usable representation of that so this is uh you know some people would     
52:37     
agree with this other people disagree arguing that the success of larger language models is more attributable to     
52:45     
approximate retrieval from their best memorized storage of training     
52:50     
data so there are some examples U where we kind of are are stressing     
52:58     
the the retrieval abil capabilities of large language models over them actually     
53:04     
building a world so uh Yan laon and Jacob Browning     
53:11     
went further asserting that a system trained on language alone will never approximate human intelligence even if     
53:18     
trained from now until the he death of the universe well that's a pretty strong opinion but you can see the point is     
53:25     
that there either acquiring these World models or they're not and the world     
53:32     
model of course in as much as you can define a world model is something that     
53:38     
you know either emerges from the data or we're just simply retrieving data and so you know it's I guess that's     
53:46     
an interesting question because it looks like people are split almost 50/50 on     
53:51     
this question uh and and maybe we're being trolled here but but uh it seems like     
53:58     
everyone it's almost perfectly distributed between agree weekly agree weekly disagree and disagree with     
54:05     
disagree having slightly more being slightly more popular than the other     
54:11     
options but it seems like people uh either throwing darts at a dart board or     
54:16     
it's really contentious so yeah I mean the question is can large language models develop     
54:23     
emergent World models and what is the evidence for that so I mean the first     
54:29     
step is to step back and say what is a world model what does it mean to have a world model and how would it be useful     
54:36     
to have a world model so you know a world model obviously if you don't give     
54:42     
it the model something like an overarching context has to be acquired     
54:48     
from the data and you know maybe that's a strong sort of definition of world     
54:54     
model in terms of you know an autonomous model I mean if I give my model a context if I give it     
55:02     
some reference points in the world is that a world model I guess it is but I'm     
55:07     
giving it that information just as I'm training it on a feature space or a     
55:12     
semantic space so one can do a top down sort of     
55:19     
world model where one can have the model acquire a world model from the data and     
55:25     
the question is can the model do that through generalization through other sorts of     
55:31     
things through TR transfer learning Etc um but we can go back to the     
55:38     
definitions of world model and it turns out that they're not all the same     
55:43     
so one definition of a world model is internal representations that simulate     
55:49     
aspects of the external World another definition is representations which Preserve the     
55:56     
causal structure of the environment as far as is necessitated by the tasks an     
56:02     
agent needs to perform the third one is structure preserving behaviorally efficacious     
56:09     
representation of the entities relations and processes in the real world these     
56:15     
representations capture at an abstract level they counter Ro World processes     
56:22     
which typically involve causal relations in algorithmic efficient forms to     
56:28     
support re relevant behaviors so this number three is so these are getting longer and longer as you can see this     
56:34     
number three is interesting because it gives some very specific     
56:39     
predictions um that the representations are you know need to be there it needs     
56:45     
to be preser pres uh preserving of structure needs to have an effect on     
56:51     
behavior and it has to capture basic basically some counterpart real world     
56:59     
process and if we go back to the idea of the everard regulator theorem you know this is something that     
57:05     
comes up in in we have this paper on the ever regulator the world models     
57:12     
basically in the everhood regulator theorem the argument is that the model     
57:17     
has to be an isomorphic or isometric mapping to the real world and so what     
57:23     
does that mean that means that the model needs to represent the real world or the     
57:31     
World by having equivalent components so it doesn't have to be say like a hyper     
57:38     
realistic representation for every single thing is duplicated but it does have to preserve     
57:46     
the structure of the real world at a level that's mostly complete so if I say need to understand     
57:55     
things in the world of breakout as that video game where you have a paddle that     
58:00     
moves left and right you have this ball that bounces against the paddle smashes     
58:06     
into bricks and then bounces back down and you have to catch it with the paddle and bounce it back up and the object of     
58:13     
the game is to break through to the top of this structure and so the idea is     
58:20     
that the model not only needs to know how to make the next move but it needs to know the overall goal and needs to     
58:26     
know what you know what if you take one move what the consequences but if you     
58:32     
take multiple moves what the consequences for that so you need to have all of that encoded somehow in a     
58:39     
model and the question is can you learn that emergently from just kind of     
58:46     
interactions or does that need to be partially hardcoded or you know in the case of the     
58:52     
averted regulator theorem They Don't Really Define how this model comes to be it's often in     
58:59     
in cybernetics it was just often someone designing a model and implementing it in the Work     
59:06     
World they wer very specific on how this was done because they didn't really have any good examples back then you know     
59:13     
people were working on symbolic AI at best and so you might give it of the AI     
59:22     
a symbolic system and you know the symbolic AI systems had their own level     
59:27     
of performance they could do things like play chess but of course we moved away from those for reasons that they don't     
59:35     
they can't acquire data or they can't really reason from data in the same way     
59:40     
that our modern models can so this is all Food For Thought um I'd really like     
59:47     
to kind of think about this in terms of the ever good regulator theorem because I think there's a lot of     
59:52     
instructive um something very instructive about that     
59:57     
so this uh so these are all definitions um these in informal     
1:00:02     
definitions emphasize that the world models exist in an organism's brain or in say large language models neural     
1:00:08     
network that they capture something about the world that is causal and Abstract or compressed so it has to be     
1:00:16     
causal you have to have one thing affecting another see the consequences of actions know how things are related     
1:00:24     
caus and some sometimes avoid spous cause uh correlations or spous     
1:00:32     
causality and it has to be abstract or compressed in some way that doesn't     
1:00:37     
require you to reproduce every single instance in know in know in the real world or every single component of the     
1:00:44     
real world so we don't necessarily want to have this large set of statistical     
1:00:52     
associations we want this to be compact or exess we want this to be     
1:00:57     
algorithmically efficient so Melanie Mitchell is the     
1:01:03     
author of intellig artificial intelligence a guide for thinking humans uh in this book on page 236 she gives     
1:01:10     
the following photo as an example of how humans model the world including intuitive models of physics biology and     
1:01:17     
psychology which are these kind of models that we develop in development or we we have     
1:01:24     
kind of as these sort of default models of physics and biology and psychology     
1:01:30     
sometimes they call them folk physics or folk psychology so it's like if you learn nothing in school about physics or     
1:01:37     
psychology or biology you tend to default to these intuitive models and so     
1:01:42     
it's just like if You observe the world you can intu these things and you know     
1:01:47     
there might be some innate aspect to it but it's basically very different than     
1:01:53     
you know kind of formally testing things through hypothesis just kind of making these     
1:01:59     
quick judgments about the world based on intuition so this is where you know     
1:02:04     
these models enable us to very quickly make sense of complex situations and understand why certain     
1:02:12     
things happen certain behaviors happen and what causes these behaviors so this is the picture here this is a woman     
1:02:21     
walking uh walking a dog and pushing a stroller with a child in it     
1:02:27     
and she's talking on the phone she's doing like three different things at once and you know this is kind of why is     
1:02:35     
this all happening and a model would have to take this image plus there's a man walking on the     
1:02:43     
in the other direction behind it there's traffic it's a city scene now an algorithm would have to take this image     
1:02:50     
and figure out all the components of this what's going on what the causality     
1:02:55     
is is and what happens in the future if certain things     
1:03:02     
happen so this would be where we have to guess the relationships amongst the uh     
1:03:09     
things in the image we have to ask counterfactual questions like how would     
1:03:15     
the photo change if the dog belonged to the man or what would happen if a driver approaching crosswalk wildly honk the     
1:03:22     
horn or you know there are a number of scenarios we can test and think about the     
1:03:30     
outcomes it's important to note that our world models don't just exist for the real world they can also be formed and     
1:03:36     
used to reason about imaginary worlds such as those created in science fiction or fantasy literature so this is again     
1:03:43     
you know where we want to test different scenarios we have maybe like sparse data     
1:03:49     
um and we want to be able to reason about things in a way that you know     
1:03:55     
doesn't restrict us to those data sets and so     
1:04:01     
um MIT Professor Jacob Andreas wrote an insightful blog post proposing a     
1:04:06     
spectrum of different types of models that might count as World models so this is um a blog post which I won't talk     
1:04:13     
about but this is just sort of a classification of different types of world models so the first type of model     
1:04:21     
that could classify as a world model and this is the weakest type is is a static lookup table so we all you know we know     
1:04:29     
that like if you're training a model you can construct a lookup table from different     
1:04:35     
entries if you have that image that we saw if you have different components to     
1:04:40     
that image you can take those components look up what maybe the list of things     
1:04:47     
that they possibly mean are and then memorize you know take from that lookup table a possible answers and then evalu     
1:04:55     
those answers as to their likelihood maybe we have more data showing the outcomes or later you know     
1:05:04     
outcomes in in that scene so if we have that of course we     
1:05:09     
could you know that would be maybe sufficient as a very weak form of     
1:05:15     
prediction but it wouldn't give us a lot of counterfactuals it wouldn't be able to generalize in any way Beyond storic     
1:05:23     
data the next might be a map such as this two-dimensional map of the solar system where we see the planets in order     
1:05:31     
um and then we see the sun and we know that maybe that they orbit the Sun but     
1:05:37     
you know this is this two-dimensional map is useful for answering queries so     
1:05:43     
if we query this model we can get answers we can retrieve labels we can     
1:05:48     
retrieve basic information like which is the largest     
1:05:53     
planet or which planet is closest to the the Sun and this relies this offloads a lot     
1:06:01     
of the work of the world model to the user so the user has to give really good     
1:06:06     
queries and order to get a good answer it can't however help answer     
1:06:11     
questions like if Mercury and Earth are aligned at noon today what will the relative positions be at noon     
1:06:19     
tomorrow to help answer questions and involve Dynamics so we have the static     
1:06:24     
model we we have a lookup table which is even weaker and then the next step of     
1:06:29     
course forward is this Dynamics model so this is uh where you have the     
1:06:36     
planets around the Sun and you have like these mechanical arms it's called an A     
1:06:44     
so you can actually build a model like this where you have planets out a certain distance from the Sun you     
1:06:50     
represent their orbits by these rotating arms and you can actually clear the     
1:06:55     
model by moving the model in different positions moving the arms in different     
1:07:01     
positions and you can not only query things about the relationship between the Sun and the planets but then things     
1:07:08     
like their relative position in their orbits so we have a lookup table a     
1:07:15     
two-dimensional static map and a three-dimensional dynamic     
1:07:21     
dynamic so those are the three and then the final model in the Spectrum is the     
1:07:26     
simulator so if we have the solar system we can have a three-dimensional model of     
1:07:32     
Dynamics but that still doesn't help us with the counterfactuals we need to kind of     
1:07:37     
figure out the causal forces and which ones are truly causal and which ones are     
1:07:43     
spals so this allows us you know we know what simulators are I you know they're all sorts of uh programs that allow you     
1:07:50     
to simulate the solar system and its Dynamics and so in a simulation of     
1:07:56     
course you not only have that dynamical aspect but you have uh you know     
1:08:03     
different alternate scenarios different counterfactuals what happens when what happens     
1:08:11     
if so that's uh that's part one and then part two is here and so this kind of     
1:08:18     
gets into some specific examples this is evidence for world     
1:08:25     
models and large language models the case of aell which is a popular game um     
1:08:31     
this is a simple board game This was um reported in 2022 by Kenneth Lee and     
1:08:38     
others the authors trained at relatively small transformer Network to predict legal moves in the game and then analyze     
1:08:46     
the internal activations in that Network to see if the Transformer has learned a world model by virtue of its training on     
1:08:52     
token sequences representing games so um basically they train the trans     
1:09:00     
Transformer Network which they call the th GPT to input sequences of legal moves     
1:09:06     
and output a next legal move in the sequence so they train     
1:09:12     
this um they were able to generate 20 million sequences to be used as     
1:09:18     
training uh the input to a GPT is a sequence of tokens each representing a     
1:09:23     
legal move in the sequence the correct output would be a next legal move in the     
1:09:29     
sequence this is similar to how we use large language models for language there     
1:09:34     
are certain rules to language there are certain sequences that are more likely than others so it's very     
1:09:41     
similar and like typical large language model training the Transformer wasn't told about any about the meaning of the     
1:09:48     
input sequence it didn't know that it represented a game played on an 8 by8 board or that there were two players     
1:09:55     
with of different colors where the players took turns or anything else all that mattered in Transformers view was     
1:10:03     
the pattern have been put so     
1:10:08     
after training on this 20 million sequence data set a GPT was nearly     
1:10:13     
perfect on predicting a token representing a legal move given a sequence of previous     
1:10:19     
moves the question was what had the network actually learned in order to perform this task     
1:10:26     
so there was some speculation here that the Transformer had developed an emergent World model for this compressed     
1:10:33     
representation of the rules of the game and what the state of the game word would be after any sequence of input     
1:10:40     
TOS to test the speculation the author needed a way to look under the hood of the     
1:10:45     
Transformer to do this they used a technique called probing which can reveal whether the train Transformers     
1:10:51     
internal activations encoded the state of the game board so this probe is a simple classifier     
1:10:59     
that is trained on the Transformers internal activations to predict the state of the board at different points during a game     
1:11:06     
sequence uh so they created a training set for these probes they presented many     
1:11:11     
partial game sequences to AO GPT and for each input sequence they recorded the     
1:11:16     
Network's Vector of internal activations at each of its eight layers if aell GPT     
1:11:23     
had an implicit World model is activation should somehow encode what the contents of each board Square would     
1:11:29     
be given the sequence of moves represented in the input um as Illustrated below and     
1:11:36     
there's this figure here the authors created 64 different probes each probe     
1:11:41     
is a linear classifier so this is where you have the true board state after different     
1:11:48     
moves you have these moves being trained with this     
1:11:53     
model you have this sequence that moves as input to the Transformer and then you have these     
1:12:00     
activations from a given layer and this is the input to each probe so you had the A1 probe A2 probe C5 probe D3 probe     
1:12:09     
h8 probe meaning that it's basically sampling each position on the board and     
1:12:15     
seeing if there's a token on that or I guess in this case um an object in that space so     
1:12:25     
so A1 for example would be up here that's empty A2 is here it's also a     
1:12:31     
probe that's empty C5 actually has a black object in it so that's black D3 is     
1:12:40     
a white object so that's white h8 is here so that's empty so it's basically     
1:12:45     
sampling the entire board it's coming up with an answer of what object is there     
1:12:51     
whether it's black or white and it can do this for different uh move after different moves different board States     
1:12:59     
and it gets a sense of the entire space the idea is that since linear     
1:13:05     
classifiers are so simple if they can predict the correct board state from the Transformer activations those     
1:13:11     
activations must much encode that states in a very easy to decode way they     
1:13:16     
provide this representation that can easily be used to answer questions about the dynamic state of the AEL board so     
1:13:22     
remember we want don't want just a static representation we want a dynamic     
1:13:28     
representation however a snagger rose the winar probes trained by the authors didn't work very well for predicting     
1:13:34     
boord St this is interesting that we have these sort of uh static     
1:13:40     
representations we're trying to use that to derive a dynamic representation but those linear probes     
1:13:46     
didn't work in predicting the board State at any given time so the authors train tried training     
1:13:53     
more powerful nonlinear probes in particular neural networks with the hidden this much work worked much better     
1:14:00     
in predicting the board state so activations from Transformer 7 were     
1:14:05     
given as inputs when that happened the train probes were actually able to correctly predict the corresponding     
1:14:11     
board state with about 98% accuracy so this isn't really evidence     
1:14:17     
for the Transformer developing World model the problem is that the nonlinear     
1:14:23     
probes are too powerful at Learning pth patterns and so maybe it's just the     
1:14:28     
probits doing the predicting R and the Transformer     
1:14:34     
so you know this is some evidence for emergent World     
1:14:39     
laws and it's not really clear if that's good evidence or not um some people were     
1:14:48     
impressed some people weren't impressed I think we obviously saw that there's a split in this and a lot of them involved     
1:14:55     
sort of um you know preferences and bias um     
1:15:02     
so Crystal uh um on social media said I think the recent aolo paper was quite     
1:15:08     
striking clear evidence of a language model developing an internal World model and a said do large language     
1:15:17     
models really understand the world or just give the appearance of understanding evidence shows large     
1:15:22     
language models build models of how the world works which makes me comfortable saying they do understand so this is     
1:15:28     
about understanding and about Metal learning as well as about just building     
1:15:33     
a world model um so this is you know an ongoing debate whether or not this is an     
1:15:40     
emergent World model and um well impressive you know     
1:15:46     
it's hard to say whether this is really a world model so um I don't really think that we're     
1:15:53     
going to get to any consensus anytime soon on this but it's worth thinking     
1:15:59     
about world models is being an improvement on these bags of heris stics or these her istics this collection of     
1:16:05     
her istics that we would typically use to make these shortcuts and Lear so we     
1:16:11     
want to make these shortcuts and learning but we don't want to do it based on simple heris because the error     
1:16:17     
rate is too great and you come up with weird kind of associations and answers to things we want to be able to make     
1:16:24     
kind of her istic shortcuts but we want to do in an informed way that     
1:16:30     
understands the world and understands the consequences of actions so this is all kind of to say     
1:16:37     
that um there's a lot of interesting work with respect to large language     
1:16:43     
models and World models um but that I think can be generalized to other types of machine learning models as well I was     
1:16:52     
thinking um this week how how important it is     
1:16:59     
um to step back or or to to visit on a     
1:17:11     
daily um or at least weekly level     
1:17:17     
um the um the blog     
1:17:23     
um is it like it's some play on Mystery Science     
1:17:29     
Theater but for AI oh the the who's that blog by     
1:17:37     
sure um it's like Emily something oh Emily     
1:17:43     
Bender yes yes yes yes yes yes yes yes yeah     
1:17:48     
um as well as as something that um as well as something that     
1:17:58     
um uh who's the EF     
1:18:04     
um spokesperson um he's a writer Corey Corey do okay yeah yeah um you know that     
1:18:13     
um we receive an incredible amount of     
1:18:20     
um marketing hype     
1:18:26     
uh you know without seeking it out you know yeah um by companies who have to     
1:18:37     
justify why they are still in charge     
1:18:45     
Yeah by by yeah just just o o overhype you     
1:18:50     
know like like a bunch of great interviews this week you know so one um     
1:18:56     
I thought it was interesting that the CEO of Microsoft ostensibly just sit down and     
1:19:02     
talk about how they've come out with some sort of quantum processor which we can we can talk about the hype around     
1:19:08     
that but but you know his point and you     
1:19:14     
know their failed roll out of co-pilot yeah um his his point is like name me     
1:19:21     
one thing that AI has done you know yeah like like if this is     
1:19:31     
so if this is so Earth shattering you know I mean it's it's funny because     
1:19:37     
there was there's a theoretical physicist was kind of saying the same thing I mean she she was going off on     
1:19:43     
this whole like AI scientist thing yeah which which is you know if you will     
1:19:49     
an extension of that world model to you know a Imagining the the world that we     
1:19:57     
can't see right but but because because we've given them enough data um that     
1:20:03     
they can they can do these extrapolations if you will     
1:20:13     
um I I I think a daily dose of that is super super important yeah but you know     
1:20:22     
the first thing that popped into my mind which I was surprised she didn't say was Alpha fold right you know and and but it     
1:20:32     
is really specific right you know I mean it's like you tried you tried a key on a     
1:20:41     
billion locks and it opened one door you don't you don't you don't go ah     
1:20:49     
this is obviously the master key right you know     
1:20:55     
um uh so it     
1:21:00     
is U yeah so I mean this this speaks to     
1:21:05     
something that came from going through the the     
1:21:11     
references that Adam saffron put together was like     
1:21:18     
hey is this a world model or is this you know     
1:21:26     
a more a more fuzzy concept of planning right right you     
1:21:32     
know and and I what I love about all of this what I love about all of this is     
1:21:40     
that I can't you know it's like the last say     
1:21:47     
10 12 years of of AI hype um has been a     
1:21:53     
wonderful demonstration of everything that Douglas Adams had put into that one     
1:22:00     
story about deep thought which is which is you know give us the the answer to     
1:22:07     
life the universe and everything and you know it comes up with     
1:22:13     
an answer and it's just like did you actually know what your question     
1:22:18     
meant you know that that that all of this vagueness you know that like every     
1:22:25     
time we seem to be in a conundrum it it's really like do we actually know what we were talking about in the first     
1:22:31     
place yeah and so returning to the first the the     
1:22:40     
discussion around the zero shot learning as it relates to this     
1:22:46     
right when we're talking about cognitive development in children you know we have this um     
1:22:55     
like we we don't even have an internal representation you know like we put come     
1:23:05     
we we come online at like five years old right right you know I mean in terms of     
1:23:12     
like what even from our personal timeline     
1:23:19     
what are memories we can retrieve yeah and and that's like super vague that     
1:23:24     
like I lived in this city yeah you know like you know you can remember maybe     
1:23:31     
like I remember what my bedroom looked like you know like like and     
1:23:38     
um so you've got this this     
1:23:43     
absolute um uh you know I want to use like an     
1:23:50     
astronomical like dark matter Dark Energy kind of term like like this has     
1:23:56     
completely shaped your world like like you were absolutely a learning system     
1:24:02     
during all of this and a multimodal continual Learning System to to generate     
1:24:08     
these these these you know uh     
1:24:13     
uh this conceptual landscape High dimensional     
1:24:19     
conceptual landscape that you are using um     
1:24:25     
unbeknown to you right like like it's just the water     
1:24:31     
that you're you're breathing you know you're you're living in and     
1:24:37     
um um yeah so I I I really like I mean you     
1:24:46     
know Melanie Mitchell like Emily Bender is one of those people who who just     
1:24:53     
seems to come along every couple of months and be like any of you guys actually know what     
1:24:59     
you're talking about yeah you know like what's what's the     
1:25:05     
evidence for you saying that I mean other than like you know a press release from a company that has absolutely     
1:25:12     
everything at stake on you on you believing this it's it's you know uh uh     
1:25:19     
I mean again like it is insane to me     
1:25:26     
um who who did a talk on this um I forget if it I don't know I mean I     
1:25:33     
think the Simons foundation and the Council on Foreign Relations both did a talk on the effect     
1:25:42     
of deep seek on the AI landscape or or like like something like just to give     
1:25:48     
you a sense of just like like there was so much hype yeah     
1:25:55     
going on that you get these two extremes both     
1:26:00     
talking about just like ah there's there's been a t you know a tectonic     
1:26:07     
shift right and and at the same time when you you know you dig into the     
1:26:13     
papers it's just like this has all been just incremental uh     
1:26:18     
developments yeah um that that one particular team for a variety of kind of     
1:26:26     
like team leadership reasons together with you know poit     
1:26:32     
political um sanctions you know probably coales into     
1:26:39     
this particular form right yeah um but but yeah anyway so that that     
1:26:47     
all to say um uh uh     
1:26:54     
well the the you know I certainly like and and     
1:27:03     
again this is you know like what what do we get from from     
1:27:09     
humans Behavior but you know like like the map is not the territory right so so     
1:27:16     
I mean you know I I I wanted to just yeah talk about that     
1:27:22     
kind of efficiency and     
1:27:27     
and you know as well as like some of the kind of William     
1:27:37     
James um becoming becoming an expert on     
1:27:44     
things you know the like the speeds the speed at which you can answer in in a     
1:27:51     
sense out of distribution questions     
1:27:56     
um um you know just speaks to that kind of like you've got this model and and     
1:28:04     
again like I think we fall into a you know 3D video game kind of image     
1:28:14     
in our heads but but that's that it can actually be much more     
1:28:20     
conceptual um and um yeah anyway it's it's     
1:28:29     
um I I I think I mean so one I've been attending     
1:28:36     
the theoretical neurobiology group meetings that first     
1:28:42     
first and runs which are all open you can join on teams the only thing is um     
1:28:49     
on Mondays it overlaps with D.A worm oh yeah but it I I I think he has the same     
1:28:57     
structure that he used to have um at the film I mean what what which is where     
1:29:03     
he's doing it but he's still there but um the way you do his Neuro Imaging     
1:29:08     
meetings where it's like I think Mondays is kind of like like an     
1:29:15     
application and Tuesdays is     
1:29:20     
um is like Theory or you know is is more     
1:29:26     
the the Machinery yeah um uh and the active inference     
1:29:34     
Institute started a um a new textbook     
1:29:41     
cohort so I attended that that meeting but     
1:29:50     
I just the the     
1:29:56     
um the big different you know I think I think like being around active     
1:30:03     
inference Institute not so much but but like the machine learning Street Talk     
1:30:09     
active inference Discord or the Discord for machine learning Street talk and then our active inference     
1:30:17     
Channel um is is where you see the the     
1:30:24     
real disconnect between like here's the machinery and this is exactly what it     
1:30:29     
relates to in terms of policies in terms of math in terms of you know what its     
1:30:34     
extent is and here's the     
1:30:40     
um here's the vision of what people think that actually means which is much more philosophy and     
1:30:48     
and you know what your visualizations are as well as just bringing up you know     
1:30:54     
how alpha folds was     
1:31:00     
doing was considering things that were unintuitive and in a sense like world     
1:31:09     
breaking um and and and again I think     
1:31:14     
that's really interesting in that alha fold was is one of the     
1:31:22     
successes right you know um uh     
1:31:28     
um yeah and certainly like like Alpha fold's breakthrough was was is somewhat     
1:31:37     
credited to letting go of the hand um uh     
1:31:45     
kind of handmade you have human human made charistics yeah you know which again     
1:31:52     
like suggests that you know maybe our our in you know again like our internal     
1:32:00     
World model right is not actually how things work it's yeah yeah     
1:32:08     
yeah yeah yeah I think that's an interesting point and you know again     
1:32:13     
like in science we have well we have these sort of intuitive models like     
1:32:19     
intuitive physics and intuitive um like ology or folk physics folk psychology     
1:32:26     
and often times when you're teaching that say at a university level or often times fighting against a lot of the folk     
1:32:32     
or folk interpretations of these things so a lot of times you'll say you know this is the way something works you'll     
1:32:38     
demonstrate it through demonstration through an experiment and it sometimes agrees with that and sometimes it     
1:32:44     
doesn't and so you know if you're using like a if you're building a world model is     
1:32:50     
the world model I mean I guess the question is in in the case of what we're developing as     
1:32:57     
an intuitive model is that the same as sort of a world model that's informed or     
1:33:03     
is it a world model that we acquire just to navigate the world and so maybe the     
1:33:08     
question is is by in biological context you have different world models that     
1:33:14     
develop from different like contexts whether it's like someone with like a     
1:33:19     
PhD level education or someone in who's trying to navigate the world or you know     
1:33:26     
it's some organism that's embedded in a world in like you know in a aquatic environment versus an organism that's a     
1:33:35     
burrowing underground all these things you know you might have different world models which are just ways to relate     
1:33:41     
things um and you know that's going to have implications for how these are     
1:33:46     
implemented in artificial systems so you know we we talk about world models for     
1:33:52     
large language models but totally ignores like any sort of embodiment that actually be interesting     
1:33:59     
um and I haven't seen this in the embod intelligence workshops but someone     
1:34:04     
approaching the world models question from an embodiment standpoint um uh that's something that     
1:34:11     
might be uh I think we still have time to do a submission for that I don't know     
1:34:16     
but uh you know that's that's that's an interesting point um you know that maybe     
1:34:22     
we have multiple World models maybe a world model is just a way to kind of relate to the world and as our sort of     
1:34:28     
our information changes or conceptual World changes not just our actual world     
1:34:34     
then those World models also change or we have multiple World models depending on what we're doing and     
1:34:40     
there's sort of this intersection of world models and that gives us our     
1:34:46     
Behavior again you know I think that really comes down to the definition of what a world model is so we we had like     
1:34:53     
three definition there that no gave us and like you know they're they're all from the literature     
1:34:58     
but they're of different sizes so like you the one line definition and then the     
1:35:03     
big paragraph definition and maybe the on line definition is probably maybe better than     
1:35:09     
the paragraph definition but you know we have to Define what it is go ahead well it's just just I mean     
1:35:19     
just also thinking about that game right like     
1:35:26     
what what would a representation of the rules even look like or you know like     
1:35:34     
again and meet those criteria you know like like it's obviously just toy     
1:35:39     
problem right right but it's also very hard for me to     
1:35:45     
conceptualize what representation of the rules would     
1:35:51     
even look like you know and and it also just reminds me of how um how     
1:36:00     
interesting it is when you look in inside     
1:36:06     
um you get some insights inside of say um somewhat complex electrical     
1:36:14     
system and you     
1:36:20     
you you know you putting a probe on some particular     
1:36:26     
component and you get very surprised by like what you know what range it's     
1:36:33     
looking in and what and what kind of like the signal looks like at that for     
1:36:39     
that little component you know it's you know getting getting lost in all these     
1:36:45     
kind of Transformations and and um renormalizations and Etc scalings and     
1:36:53     
things like that like yeah and you know I I get that     
1:37:00     
somewhat from you know some of like distill Pub's you know tutorials on neural     
1:37:07     
networks and things like that it's like oh that's that's what the computer's thinking about you     
1:37:15     
know yeah yeah it's the you I don't know if you've ever seen the uh this video     
1:37:22     
it's where Bork the singer is describing what's going on inside of a television     
1:37:27     
and she's like talking about like how their little fairies in the television like make the image it's it's     
1:37:35     
interesting because like has this relevance to World modeling that if that's your world model of a television     
1:37:41     
I mean you could observe it but then you could also like kind of observe the output State without knowing necessarily     
1:37:47     
what's going on inside and you have to describe it and so you know and that goes back to like when we first World     
1:37:54     
model or we first to like interact with the world you know we're often kind of     
1:37:59     
not observing everything you know observing the full sort of reductionist     
1:38:05     
breakdown of something so we have to kind of make things make explanations often so there's this this aspect of     
1:38:12     
that that you know might be relevant to machine learning or machines or artificial     
1:38:19     
models well you know sorry that just Al made me think about you know um just a     
1:38:28     
platonic idea of of where our world models are are all you know at best or     
1:38:35     
our shadows playing on a cave right right like like we don't we we don't     
1:38:42     
even have access to um to reality uh we are we are you know     
1:38:54     
yeah that this isn't you know in a kind of um who's the uh who's the guy who     
1:39:00     
kind of epitomizes this um UC Irvine guy um the Hoffman     
1:39:07     
Donald Hoffman yeah yeah yeah yeah you know that like like you know th     
1:39:15     
this that we're so sure is real right yeah is is is absolutely just shatter is     
1:39:26     
and yeah uh you know Li limited     
1:39:31     
Spectrum you know you know yeah our it's     
1:39:37     
it's our own internal representation these things     
1:39:42     
yeah yeah anyway it's     
1:39:47     
uh it definitely this is all just good in     
1:39:53     
terms of keep circling back to     
1:39:59     
um uh uncovering our own fakeness about     
1:40:05     
these Concepts you know and     
1:40:11     
um and like the the engineering work is is so     
1:40:17     
useful at at helping us be yeah explo it or you know     
1:40:27     
yeah I also think it's kind of worth mentioning that if we do see these     
1:40:32     
emergent World models and machine systems that we should also expect to see something like a sort of a     
1:40:39     
developmental phase where like they're creating these World models that are very naive but like they attempts at     
1:40:46     
synthesis I mean the assumption that it's going to hit upon the right World model immediately is maybe evidence that     
1:40:52     
there is really that emerging process going on well I mean it's it's again     
1:40:59     
it's also you know I mean I I I don't you know I joke about it but I I I think     
1:41:05     
it's also very serious that a lot of these people have actual you know not     
1:41:12     
just commercial interests but are caught up in the idea like like this is the right path right you know and and there     
1:41:22     
was another machine learning Street Talk um well there was a machine learning Street Talk     
1:41:27     
interview uh I forget what his name was but um but     
1:41:35     
he he was the original um     
1:41:42     
uh is it long shortterm memory lstm yeah     
1:41:47     
yeah I always forget um     
1:41:53     
uh uh who who you know was the very definite you     
1:42:00     
know why would people think that you know you train on all this text that     
1:42:07     
you're you're going to get anything other than you know an approximate     
1:42:12     
text um um parot or you know I mean he was     
1:42:18     
calling it just database retrieval and um     
1:42:24     
uh there yeah and you know um I anyway     
1:42:31     
that's that's why I just like like I haven't checked Emily vendor's blog in a     
1:42:37     
while yeah and it's like Mystery Science AI hype     
1:42:43     
theater or something like that yeah yeah you know and you know I think Corey doctor     
1:42:50     
is maybe um has to has to focus too much on politics     
1:42:56     
these days to to be to be shaming shaming our AI overs yeah and shed     
1:43:03     
ification and so forth well you know and the fact that like we're probably not going to see any     
1:43:10     
any you know anti-monopoly anti-monopoly moves from the justice     
1:43:16     
department this this this term yeah but it is um yeah like like I think     
1:43:26     
you had the or Melanie had the Ilia quotes you know I mean he he just     
1:43:33     
you know this is someone literally raising bill you know like he's raising     
1:43:39     
money right like of course he's saying this is the     
1:43:44     
right like like these people are not yeah it's important to remember that     
1:43:50     
they're not academics and that like a lot of money on the line for you know     
1:43:56     
there's a big pot of gold saying this is this is the right way yeah and and     
1:44:03     
um um you know and I think it's it's really     
1:44:09     
yeah it's key to remember that um yeah I me I'm not even still     
1:44:15     
seeing the the programming you know I I like that Simon will Willam Williams     
1:44:23     
I forget his the the Django Creator oh     
1:44:29     
oh Simon Willison maybe wison yeah yeah Wilson yeah yeah but it was just like     
1:44:36     
like you know yeah we're     
1:44:44     
we're yeah like we we've got uh I I I     
1:44:49     
also like the king the moving goal posts on chat GPT oh yeah you know so it's like it's     
1:44:59     
like when Sam was same element was forced out was it just chat gbt 3 I     
1:45:05     
think so yeah it was just chat gbt 3 right and and like there was this mythical Q or this myth like Q star or     
1:45:14     
something like that oh yeah yeah like like like you     
1:45:19     
know that that they achieved AI I you know there was this this life form     
1:45:26     
lurking in open AI right and and the board was scared and you know etc etc and yet you     
1:45:36     
know we're at four you know five is Gonna Come Along     
1:45:42     
or you know then suddenly there's 01 03 you know all these     
1:45:49     
things um yeah anyway I I I I am very happy     
1:45:57     
to be yeah like trying to find this     
1:46:03     
great great movements um from the RX andur you know to to have more     
1:46:12     
examples in terms of um you know let's do more robot training     
1:46:18     
let's do more agent training um     
1:46:23     
and um and by you know in in implementations     
1:46:30     
we will we will start to chip away at all this vagueness yeah and um you     
1:46:39     
know I I don't think uh yeah I don't think we're gonna see anything in our lifetime     
1:46:47     
yeah you know uh but you know the the     
1:46:52     
other meeting that I attended was umh the Weight Watcher a yeah you know     
1:47:00     
in terms of     
1:47:06     
just that that's a condensed matter physicist looking at the     
1:47:16     
weights without data so it it's it's it's not I mean it's zero shottish in a     
1:47:25     
way yeah right um well no I mean it's trained um     
1:47:34     
but it's yeah it's another way of looking um it's     
1:47:43     
a new way of looking at the the um at the effects of     
1:47:50     
training yeah and like the effects of training yes thank you thank you and and     
1:47:56     
I'm I'm curious you know and I'm really trying to get something to the point     
1:48:02     
where we can see you know where we can have     
1:48:08     
an not a toy example that we can work with um I mean he's got some mnist kind     
1:48:15     
of examples that he talks about and he's got some Vision model um examples that he talks about     
1:48:24     
and um but we're the     
1:48:29     
the well she's a [Music] researcher rori I think is the city in     
1:48:38     
India yeah um IIT RI uh     
1:48:44     
who's her PhD is focused on EG speech     
1:48:51     
decoding right and um So Meta you     
1:48:57     
know meta like like again our Tech overlords are hiring up all our phds um     
1:49:04     
so like everybody who was working on like Meg in Paris now works for Meta     
1:49:10     
Meta AI right and they've got a new     
1:49:16     
they've got a new paper on speech decoding um and and but it was you know     
1:49:24     
it very interesting talking with her about it because she she she was her first question was like     
1:49:31     
why did they do you know they're doing speech decoding from the Meg signals but     
1:49:38     
they have the people typing and I'm like well yeah you know     
1:49:45     
like they they you know like why do you think they they had people typing like     
1:49:53     
I'm like you know they have people typing um because they needed to     
1:49:59     
know when you know like like that was giving them an     
1:50:04     
objective this is what I'm now thinking about this Bo you know yeah you know so     
1:50:11     
it's like every key stroke is giving you some insight into the the the     
1:50:20     
timing the neural data that you're seeing you know so this is this is hardly     
1:50:26     
silent speech or you know which which again and I I was also pointing out like     
1:50:34     
like let's let's not forget all the failed big teag projects that have tried     
1:50:40     
to do silent speech like like like there's there's big big company here     
1:50:45     
called whisper AI that just well they didn't go out of business but they've     
1:50:51     
pivoted oh okay yeah so so and there it's funny too because it's it's they're     
1:50:59     
they're based on this project that I still get asked about in nerx forms     
1:51:05     
slack or even like BCI Reddit yeah like hey I saw this MIT project where he's     
1:51:13     
he's decoding speech by attaching electrodes to the the vocal you know to your neck     
1:51:19     
right I forget what that project's called but this company is set up to do to do     
1:51:27     
that right and anyway they they uh they had     
1:51:34     
something that's supposedly working um one of the reasons that they pivoted     
1:51:40     
internally is uh uh that they couldn't get their own developers to use     
1:51:50     
it you know and you know I think that also yeah it's it's another good example     
1:51:58     
of I mean they raised a lot of money they had a lot of you know well-trained     
1:52:06     
people working on this and yeah this was not     
1:52:12     
a um this was not a practical breakthrough     
1:52:18     
yeah I mean just another example of like is is a you know is say I Chang door     
1:52:24     
yeah it's a good practical example that we can be looking at and um and we're     
1:52:29     
going to do a journal Club around it we're gonna build it into the the software project our our Moab     
1:52:38     
software project n techx which is the the mother of all BCI benchmarks right     
1:52:43     
so um you know I think it's' be cool for us to have a speech Moab it's like just     
1:52:50     
data sets what the f focus on this and um and it will also prevent companies I     
1:52:58     
mean you know like the amount of Buzz that you know meta says they can     
1:53:06     
decode speech right and and you know and people talking about hey did you see     
1:53:14     
this this breakthrough that meta just had in terms of decoding speech like     
1:53:19     
they'll be able to read our thoughts very soon and then you go you go and read the     
1:53:26     
paper it's just like like this isn't even speech you     
1:53:34     
know like they're decoding yeah you know and it's it's kind of impressive in     
1:53:40     
terms of just you know it's actually a very it's like 20 subjects you know getting people to sit     
1:53:48     
and type and and they needed the other thing is these are all trained     
1:53:56     
typists right super trained typists because they they cover the keyboard     
1:54:04     
yeah yeah they don't want them looking so these are all touch typists     
1:54:10     
yeah anyway it's like it's you not a lot of     
1:54:17     
this makes it into the press release oh yeah     
1:54:22     
okay but yeah I I wasn't     
1:54:28     
[Music] sure     
1:54:34     
um there's some there's some good links in um     
1:54:42     
bioevolution um     
1:54:47     
and Sakana has some new stuff okay or you know like s's uh     
1:54:56     
um been been releasing some things     
1:55:02     
um I think they Cuda Cuda     
1:55:07     
engineer     
1:55:13     
um yeah some stuff in Dev um Dev     
1:55:20     
AI Dev neuro AI     
1:55:30     
um yeah and and networks     
1:55:36     
okay yeah     
1:55:41     
yeah okay we'll try to do that maybe next week we get to that stuff sure sure     
1:55:47     
so this is uh new paper and behavior on brain science uh the the nice thing     
1:55:53     
about these papers is that they have an extensive uh discussion slash critique     
1:55:59     
that follows the main paper so there's a lot of um you know a lot of people will     
1:56:04     
submit their sort of responses in the article PDF so the main article here is     
1:56:12     
going to make this sort of statement and then people responding to it later we won't go through all the responses I     
1:56:19     
just wanted to go through this paper and then kind to talk about a little bit about the     
1:56:24     
responses and um it's really relevant I think to reinforcement     
1:56:30     
learning not only you know simulated reinforcement learning but the sort of     
1:56:37     
Behavioral aspect of motivation constructs so this is you know kind of     
1:56:43     
getting into the the psychology of it but also has relevance to other things     
1:56:48     
as well so this is by koi maryama and Haley Josh the title is a critique of     
1:56:56     
motivation constructs to explain higher order Behavior we should unpack the     
1:57:01     
black box so this is of course you know arguing that there's certain aspects of     
1:57:10     
motivations and U motivational psychology that are a black box and we     
1:57:16     
should understand sort of Behavioral reinforcement learning in more of a     
1:57:21     
cognitive way so let's start with the abstract um     
1:57:27     
so the abstract is the constructs of motivation or needs motives Etc to     
1:57:33     
explain higher order Behavior have burgeoned in Psychology in this article we critically     
1:57:38     
evaluate such high level motivation constructs that many researchers Define as causal determinance of behavior so we     
1:57:47     
usually you know argue that there needs motivations we'll give ascribe these     
1:57:53     
things the higher order behaviors and ways to interpret it but there's this sort of black box so a lot     
1:58:00     
of times when we describe motivations and other things like that or needs we don't really have a strict     
1:58:07     
cognitive mechanism to think about that um we identify a fundamental issue with     
1:58:13     
the predominant view of motivation which we call the Black Box problem so black boxes are usually things that we find in     
1:58:21     
science that don't have an explanation but have an output we try to ascribe something to that the black boxes simply     
1:58:28     
refers to this inability to like find a mechanism or maybe it's a uh you know     
1:58:34     
some sort of stochastic process but we don't really have a good fix on what the mechanism is and for black understanding     
1:58:42     
black boxes I refer you to uh the paper by Granville uh the cybernetics paper     
1:58:50     
where he talks about how we can take these black boxes break them down into     
1:58:55     
their parts thus having a like a clear box or a     
1:59:00     
a a transparent box but every time we break down a problem we often have black     
1:59:06     
boxes within that transparent box that we need to solve so we end up either you     
1:59:13     
know kind of drilling down to the sort of fundamental elements of things a very     
1:59:19     
reductionist approach or really of solving the blackbox is sort of this emerging process which is you know not     
1:59:27     
always a a way to sort of get a fix on what's actually going on so this is but     
1:59:34     
in this case we have this black box which is where we don't really have a good mechanism for understanding     
1:59:41     
motivations and so specifically highle motivation constructs have been considered is causally investigating a     
1:59:48     
wide range of higher order Behavior but this does not explain what they actually are how behavioral Tendencies are     
1:59:54     
generated so we don't know actually we could break this down into sort of its     
2:00:00     
cognitive psychology we could also break this down into his neurom mechanisms so we can drill down a number of     
2:00:07     
others and of course we'll still have black boxes once we drill down but you     
2:00:13     
know that's that's sort of uh you know uh for another paper the blackbox     
2:00:20     
problem inevitably makes the construct IL defined and jeopardizes its theoretical status so you know in in     
2:00:28     
theory building we often start with a black box and we try to explain the phenomena and we put in these parts and     
2:00:36     
we try to take these parts and provide like a mechanism or an explanation for     
2:00:42     
each part so you often maybe will have a theory where you have these boxes that     
2:00:48     
are maybe illd defined they have like some descriptor and it's just merely a linguistic     
2:00:55     
descriptor we don't really know what the mechanism is but that one thing causes another thing so the the whole point of     
2:01:03     
theory building is to sort of Define those things very broadly and then kind     
2:01:08     
of drill down on them and find something to fit within that box so you know we     
2:01:14     
usually use different mechanisms for doing that um and so that's what they're kind of arguing here to address the     
2:01:22     
problem we discussed the importance of mental computational processes underlying motivated Behavior so they     
2:01:29     
really are interested in this case in assigning some sort of computational     
2:01:35     
process to these black boxes and describing maybe you know like a     
2:01:40     
computational model cognitive computational model or a neurocomputational model to some of     
2:01:46     
these motivated behaviors critically from this perspective motivation is not     
2:01:51     
a use unary construct that causes a wide range of higher order Behavior it is an     
2:01:56     
emergent property that people construe through the regularities of subjective experience and behavior the proposed     
2:02:03     
perspective opens new avenues for future theoretical development that is the examination of how motivated behavior is     
2:02:11     
realized through mental computational processes so that's the abstract um and     
2:02:18     
so they talk about the history of this where the con Str a motivation mostly proposed for basic behaviors such as     
2:02:26     
eating which is like hunger drive or mating which is sex drive however later     
2:02:31     
years have seen increasingly use of motivational constructs to explain higher order     
2:02:37     
behavior um nowadays there is a plethora of high level motivation constructs in Psychology including but not limited to     
2:02:44     
the need for competence relatedness and autonomy the need to     
2:02:49     
belong self-affirmation motive desire for status self-enhancement motive     
2:02:56     
achievement motive and intrinsic extrinsic motivation so you see that     
2:03:02     
there are all these like I think especially interesting is something like autonomy we talk about that a lot in in     
2:03:09     
artificial intelligence we also talk about intrinsic extrinsic     
2:03:16     
motivation and that's of course relevant to reinforcement learning and you know     
2:03:21     
these are con conu so that means that they're not like based on a specific mechanism they're usually collections of     
2:03:27     
measures that we take when we observe say like a human system so we'll build a     
2:03:34     
a construct out of this collection of measures measures actually relate to     
2:03:40     
something that's like a behavioral output or could be a physiological measure but then we have to understand     
2:03:47     
what's what's generating these measures what's generating these outputs and     
2:03:53     
that's where they're arguing for these computational mods and so getting drilling down on     
2:03:58     
these constructs and saying this is what's causing you know this is what's responsible for these constructs instead     
2:04:04     
of just thinking of these constructs as a unitary thing that we can't really explain at a you know at a Le at the     
2:04:12     
level of of prediction or you know control uh I guess we can explain it in     
2:04:19     
terms of prediction not necessarily control so so this is what we want to get     
2:04:24     
to um so they talk in this in this opinion article we provide a critical analysis of these motivation constructs     
2:04:32     
to explain heror human behavior specifically we cast out on the theoretical status of high level     
2:04:38     
motivation in the sense of a construct that directly influences complex     
2:04:43     
Behavior rather we contend that such high level motivation is a subjective     
2:04:48     
construal or emergent property of underlying Al computational processes     
2:04:53     
which determine behavior from this psychological construction perspective     
2:04:59     
we clarify both strengths and weaknesses of high level motivational constructs and offer a new Avenue for research that     
2:05:06     
has attracted almost no attention in the past and that is theoretical analysis of     
2:05:12     
how motivation is realized through mental computational processes not just     
2:05:18     
measured as an output of behaviors but or a collection of measures but as this     
2:05:25     
sort of mental computational process which is active and being able to explain that     
2:05:31     
process so I want to go down to the open peer commentary because you know there's some interesting things here so you know     
2:05:38     
often times these commentaries can add a lot to the original article um this one is called endogenous     
2:05:46     
rewards a bridge between social cognitive and behavioral models of choice     
2:05:51     
which is where they talk about intrinsic reward at will or endogenous reward is a     
2:05:57     
fiat currency that is occasioned by steps towards any goals that are challenging and or common enough to     
2:06:04     
prevent its debasement by inflation a theory of mental computational processes should propose what properties that     
2:06:11     
goals grow from appetites or endogenous rewards which may be the universal     
2:06:16     
selective factor in all modifiable mental processes so this is one another one is     
2:06:23     
this resurrecting the Black Box conundrum the abstract here is in this     
2:06:29     
article maryama and Josh contribute that a me contend that a mental computational     
2:06:35     
model demonstrates that high level motivations are emergent properties from underlying cognitive processes rather     
2:06:42     
than instigators of behaviors despite points of agreement with the author's critiques of the motivation literature I     
2:06:49     
argue that their claim of dismantle between the black box of the human mind has been constructed on shaky shaky     
2:06:56     
grounds or shaking grounds uh basically that this is not the correct way to view     
2:07:03     
this um and so you know how do we dismantle this black box this is a     
2:07:08     
classic discussion in Psychology in particular particularly with respect     
2:07:15     
to um you know how accessible is what's inside the black box so can we access     
2:07:22     
the blackbox and you know using a computational set of computational processes may or may not get     
2:07:29     
a this one here is exploring novelty to impact the blackbox of     
2:07:35     
motivation and the abstract here as marama and Josh point out that we do not sufficiently understand the constructs     
2:07:42     
and mental computations underlying higher order motivational behaviors or     
2:07:47     
motivated behaviors although this may be generally true we would like to add and contribute to     
2:07:53     
the discussion by outlining how interdisciplinary research on novelty evoked     
2:07:59     
exploration has advanced the study of learning and     
2:08:05     
curiosity this one is motivation needs cognition but it's not just about     
2:08:11     
cognition the abstract here where Yama and Josh offer valuable suggestions for     
2:08:17     
how to integrate computational processes into motivation Theory but the processes     
2:08:22     
cannot do away with motivation altogether rewards are only rewarding because people want and like them that     
2:08:29     
is because of motivation for example sexual desire is not primarily a quest for rewarding information elucidating     
2:08:37     
the interface between motivation and cognition seems a promising Way Forward     
2:08:43     
so then this this one the unboxing is already begun one motivation construct at a time the abstract here reads Mar     
2:08:51     
and Josh argue that is not clearly specified how motivation constructs produce behavior and that this black box     
2:08:59     
should be unpacked we argue that the authors Overlook important classic Theory and highlight Recent research     
2:09:06     
programs that have already started unboxing we feel that without relying on the mechanisms that such programs     
2:09:12     
uncover the proposed computational approach will be fruitless this one is     
2:09:17     
it's bigger on the inside mapping the black box of motivation and this is uh many motivational contu     
2:09:24     
constructs are opaque black boxes and should be replaced by an explicit account of the underlying psychological     
2:09:31     
mechanisms the theory of motivational systems has begun to provide such an account I recently contributed to this     
2:09:37     
tradition with a general architecture of motivation which connects energization     
2:09:43     
and Direction with a goal setting activity of emotions and serves as an evolutionary grounded map of     
2:09:49     
motivational processes so this this is you know they they insert their sort of     
2:09:54     
theory in here uh where you have these different cognitive perceptional     
2:10:00     
intentional processes and you know these aspects of goals and mood and     
2:10:06     
motivational systems here emotional mechanisms action selection and so forth     
2:10:12     
this one is expectancy value theories contribution unpacking the black box of     
2:10:18     
motivation the abstract reads although in basic agreement with marama Josh's call for greater attention to the black     
2:10:25     
boxes underlying motivated Behavior we provide examples of our published suggestions regarding how subjective     
2:10:32     
task value and ability self-concepts get into people's knowledge structures we     
2:10:38     
suggest additional mental computational processes to investigate and call for a Developmental and situated individual     
2:10:45     
differences approach to this then the last one I'll do is needed     
2:10:52     
clear definition and hierarchical integration of motivation constructs in the abstract here reads     
2:10:58     
Marana and Josh offer a thoughtful and timely critique of motivation constructs     
2:11:04     
we largely concur with their basic premise but offer additional input and clarification regarding the importance     
2:11:11     
of carefully considering the energization and Direction components of motivation and fully attending to the     
2:11:17     
hierarchical aspect of motivation rather than prioritizing particular levels of     
2:11:25     
analysis so that's a nice overview of that and I didn't get into a lot of the     
2:11:31     
jargon um but there are a couple points here one is you know I covered some select uh responses and I think they     
2:11:39     
cover a lot of territory with respect to you know kind of there's their disagreements their agreements their     
2:11:45     
suggestions from the literature how to extend this and so forth um the second is you know you can     
2:11:52     
see how these kind of debates work going back and forth you know how you know you're introducing New Concepts and kind     
2:12:00     
of figure out the right level of um you know adjustment to existing     
2:12:07     
theories and then three you know this notion that we have these constructs for     
2:12:13     
something like motivation and how we can augment them with computational models with other     
2:12:21     
types of description and then conceptual advances that make that better and then how that     
2:12:28     
can maybe relate to artificial systems where we're building models of motivation say like in an artificial     
2:12:34     
system in a reinforcement learning system and how those models can be improved by what's going on in     
2:12:41     
Psychology and in sort of the psychological science and then bringing     
2:12:47     
that over into artificial systems well yeah I certainly wanted to bring up     
2:12:55     
because it seemed like there was you know quite rightfully some some um     
2:13:03     
supporting references from Child Development okay but     
2:13:10     
U but how nerd's generation is actually an     
2:13:16     
interesting um field as well in in kind of     
2:13:23     
elucidating the the mechanisms of     
2:13:28     
motivation when they fail yeah or when they when they they are themselves     
2:13:34     
degraded um and and yeah so um I I I I saw some     
2:13:43     
references to you know motivation versus cognition or the     
2:13:51     
like interplay of motivation and cognition and Child Development     
2:13:56     
um as as you know     
2:14:02     
certainly TR trying to unpack that the relationship and kind of the complexities but yeah that there's     
2:14:09     
there's some just interesting work in terms of again you know what what what     
2:14:16     
I'm calling computational Psychiatry but what I just mean by that     
2:14:21     
is you know these these TR trying     
2:14:27     
[Music] to model these Behavior     
2:14:33     
changes that happen you know whether it's a disease process whether it's um     
2:14:40     
age you know healthy aging or whether it's it's nerd     
2:14:45     
degeneration okay um what you see in     
2:14:51     
you know like um exploitation versus     
2:14:59     
exploration you know for instance right so     
2:15:05     
um older adults as as you might imagine stop     
2:15:11     
exploring yeah now you know and it's not necessarily that they know what to yeah     
2:15:18     
yeah just just yeah yeah it's a really interesting topic and and obviously you know something I've trying to say like     
2:15:27     
you know these artificial systems lack right you know yeah and and you     
2:15:35     
know again just I mean it doesn't even it almost doesn't bear repeating but     
2:15:40     
just like like these artificial systems are so far     
2:15:46     
from being alive right yeah you know like like you know the the the thing     
2:15:53     
I've got no more time for is like is a large language model conscious oh     
2:16:00     
yeah um but you know what it what it certainly lacks you know     
2:16:08     
again there's you know there's people talking about large language models     
2:16:14     
cheating right right and it's just like ah they're not cheating     
2:16:21     
like like again like like that word that word doesn't make any sense it doesn't yeah the context right like like you     
2:16:32     
know but but so it's a wonderful topic and and I saw     
2:16:37     
um that there was a reference in the original article to Y NIV um so I want     
2:16:45     
to check that she's got some 2006 Trends in cognitive science     
2:16:51     
that I'm sure would be an interesting read on     
2:16:56     
motivation yeah I'm not familiar with motivation as a whole so I'm not really     
2:17:02     
I don't know the literature that well and I didn't know some of the terms necessarily but I I I really what     
2:17:08     
interested me about this paper was kind of like how we have these different uh     
2:17:14     
constructs to explain behaviors and you know they're not like in COG in     
2:17:19     
cognition we usually do like you know we have like memory we have things laid out     
2:17:24     
in kind of a conceptual model or a theoretical model and then in attention we have the same thing and then we try     
2:17:30     
to attach measures to it and we try to do you know neuroimaging and like with     
2:17:35     
motivations it's kind of like this is something that's motivating people and there's a kind of a theory behind it but     
2:17:41     
it's kind of very Broad in terms of you know it's kind of cast as an overarching     
2:17:48     
explanation for you know and I know people have like different computational     
2:17:53     
models like based on dopamine and things like that but um yeah it's a little bit     
2:17:59     
different what they're talking about here yeah yeah I mean so one like that's     
2:18:05     
the big criticism of cognitive science right is what they actually mean is     
2:18:11     
adult cognitive science right yeah right like like adult uh abstract     
2:18:20     
like abstract thinking cognitive science right and and you know the developmental     
2:18:30     
psychologists are are like absolutely super familiar with motivation yes yeah     
2:18:38     
you know like like you know there there's they're coming at it from     
2:18:45     
a there's this Wellspring of activity you know what's driving it like     
2:18:53     
and you know we um yeah so it's um it's again I     
2:19:01     
I think there's no surprise I mean I I I just kind of saw some references but like like     
2:19:10     
there's a lot of cognitive development references yeah I think in     
2:19:16     
this because of that and and that um     
2:19:21     
um they're G to talk about a a split as in kind of older     
2:19:30     
children where cognition and motivation     
2:19:35     
actually um become more separated     
2:19:42     
um um you know and like like the cognitive scientists aren't incorrect     
2:19:51     
to have not thought as much about these motivations because because there's     
2:19:58     
actually this this split you know um uh yeah and then yeah there's     
2:20:08     
there's you know all these important in the kind of carof Smith     
2:20:13     
um you know post post bitian understandings of like we really     
2:20:20     
do have have these critical periods of cognitive development or you know we we     
2:20:27     
have these periods of cognitive development where there's like massive     
2:20:32     
reorganization of of um the underlying systems yeah or you     
2:20:40     
know and and that like unless you are studying kids you know I mean her her     
2:20:47     
big point was like you know looking at kids pre kind of seven right you know     
2:20:54     
which is which is also interesting because of     
2:21:00     
course this is what we know from nurse like where it's just like if you have massive cortical damage before     
2:21:09     
seven then your brain can shift you you've got massive     
2:21:16     
hemispheric damage that that you know your language function can can     
2:21:24     
return um for instance you know um but it's like after seven that won't happen     
2:21:31     
right right or you know like like again to to link it back to the kind of     
2:21:38     
neural under underpinnings like you said with dopamine and things like that like yeah like we know from     
2:21:45     
damage that that there's obviously um     
2:21:51     
something going on too right that that yeah anyway it's it's interesting I I I     
2:22:00     
um I got the PDF I'm check check that out yeah for     
2:22:05     
sure all right and sounds great okay well thanks for attending this week and     
2:22:11     
hopefully we continue on with the slack we'll try to review the slack next week sounds good all right see you thank you     
