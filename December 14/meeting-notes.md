## Meeting Recording

[YouTube link](https://youtu.be/nPsPL-NN_i0?si=Q_WaIPispLY1jHaB)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113653469061058947)

## NOTES:
Newsletters? What to do in the new year.


Blue Brain retrospective:

20th anniversary: lots of outputs, successes?

what role does NeurotechX have in terms of education/training?

video courses, other sets of funding of interactions.

extension of projects past original.


EBRAINS research infrastructure — new iteration, less emphasis on Neurorobotics, Neuromorphic computing (beyond brain imaging, modeling).


Informal STEM learning grant. INCF — community-building (platforms for people).

Neuropixels workshop (UCL).

comprehensive education from curated resources.

tools integrated into other people’s work.


Open-source software being more than “up on Github” —> getting regular adopters (collect metrics).


Incentives around publications and peer review. Infinite publishing space (now the constraint is attention).

quality control vs. gatekeeping.

when is publication evaluatable”?

what’s good for fostering multidisciplinary collaborators (get activation energy)?

Konrad Kording — moving into new areas. 


Tim Behrens — brain areas doled out to PIs.

finding, establishment in an area — papers you need to read.

attentional blinders needed, but also constraint.

dissemination —> gatekeeping, be in the right e-mail groups.


Same meeting —> same papers.

who is your real audience (lack of analytics)?

how do you serve them?


Neurostars —> how-to, debugging level of education.

digging into EBRAINS - Blue Brain.

main tutorials — SciKitLearn. Work in the real-world vs. SOTA —> getting to know your dataset (different set of tools vs, PyTorch).

where’s the on-ramp? #pedagogy —> DISCORD backup.

“Core Equation of Neuroscience”. alphaXiv —> narrow down on a small set of papers —> springboard for new research.


Embodiment in populations, embodiment, genomes, and functions (structures) in populations.

Bongard, Morphological Computation. Bongard and Beer.

not easy to do armchair philosophy about.

Embodied, multiscale simulations. Anthrobots —> brittle way of making things vs agential matter.


We like networks of neurons, not neurons per se, but all cells do this.

form collective phenotypes. Goals, reach goals.

Neurofedora — insight toolkit.

software kit for M=edical Engineering, Kitware.

National Library of Medicine, segmentation, C++ based, software engineering.

CMAKE, Automake. Built on Windows, Macintosh, Linux int toolkit. its, vtk.

## TRANSCRIPT
     
Transcript     
0:00     
hello morning morning how are you all right let's get started     
0:07     
um so welcome to the meeting today uh this is our last meeting of the year for     
0:15     
2024 so hopefully we can do you know go over some things tie up some loose ends     
0:22     
move into 2025 that should be good this week we     
0:28     
had the diva we meeting if I go to our uh meeting archive for     
0:34     
dorm which is right here uh you can see I've I've gotten     
0:39     
I've prepared a an archive on GitHub and so this actually goes back to the     
0:45     
beginning of 2020 so this is a long uh set of meetings weekly annotated     
0:53     
and has a link to the YouTube content and then some social media uh threads     
0:59     
and then every once in a while we take a break from dor and we go we have some meetings uh and those meetings are     
1:06     
listed just for people's edification to know kind of some of the other things that we're involved     
1:12     
with um aside from the meetings so we start with January     
1:20     
2020 and last couple weeks we've been doing some interesting things you notice     
1:25     
we cover a wide range of topics we General I have people presenting in the meeting but I usually     
1:32     
take the weeds so I'm usually listed as the weed for most of these but sometimes we get other     
1:37     
people um you know we we always get like good uh you know some good topics just     
1:44     
kind of like this meeting um I see in December we had two meetings uh last     
1:51     
week which was the 9th we talked about reverse engineering     
1:57     
celegans and some of the things involved with that I also after the main meeting     
2:03     
I usually do uh sort of an in depth Deep dive into some set of papers this time it was a     
2:10     
paper on Developmental and tissue networks which was very interesting because we've been talking sort of we     
2:16     
have this long-term Arc in the meetings this year on applying networks to     
2:22     
tissues and organoids and embryos and other types of biological systems at the     
2:30     
sort of the cellular level so that was last week the reverse engineering of     
2:35     
celegans was this paper from a group of people who are proposing to do this work     
2:43     
on characterizing every neuron in the SE elegance connecto and then doing     
2:48     
behavioral experiments to show sort of this full range of behavior that can be generated by that kind of connectone     
2:55     
it's a very interesting uh sort of topical area very nice Vision but it's     
3:01     
you know it's going to be hard to realize so this is something that I I've had     
3:07     
conversations with a few people in the group of the very large group of people who     
3:13     
had proposed this idea and you know kind of saying how open worm might be a good     
3:20     
fit for some of what they're doing uh so it does have some tie-ins to open wor but it's largely going to be their own     
3:28     
initiative um then meeting we also talk about input output functions which are these you know that's the way they     
3:35     
characterize the connecto relative to behavior so if you     
3:40     
have say a sensory input that's an input then you have this network and then you     
3:45     
have an output function which is the behavior could be uh sort of muscle movements or it could be some sort of     
3:53     
feeding Behavior reproductive behavior um so that's and then they characterize     
3:59     
that terms of uh linear equations differential equations and so     
4:05     
forth the week before that in December 2nd we uh sometimes we do some     
4:11     
troubleshooting in the group sometimes we do some more informal stuff Susan uh     
4:17     
Crawford young is doing this work with console which is a engineering tool it's     
4:22     
an engineering software package where she's trying to implement Biotin segries     
4:28     
and biotin segries are these Ultra stable structures um if you're familiar with     
4:33     
Buckminster Fuller's work on Bucky Balls or on geodesic domes that's kind of uh     
4:41     
you know those structures are tensegrity structures they're hyper stable     
4:47     
structures that you can load with stresses and they have you know these     
4:53     
opposing sort of uh these these opposing forces that keep     
4:59     
the thing Ultra stable so this is uh what she's trying to do it's very hard because they don't have a native set of     
5:07     
first of all it doesn't handle soft materials very well but it also doesn't     
5:12     
have a native set of uh physics or algorithms for handling those kind of     
5:18     
systems so it's you know we've been talking about how to do that we also     
5:23     
talked about this article on sort of the operating system of the cell which in     
5:29     
the article we covered was described as the ribosome and they talked about the     
5:35     
bacterial ribosomes you know of which there maybe 50,000 in a typical bacterial cell those     
5:42     
being sort of the operating system of the bacterial cell because if you don't have ribosomes you don't have proteins     
5:50     
ribosomes dock messenger rnas and they make proteins they make     
5:57     
they they translate things into amino acids and then those amino acid chains     
6:02     
make proteins so you know we kind of talked about and and they kind of propos that     
6:09     
if you do the back of the envelope calculations on all of the DNA and all     
6:15     
of the proteins that go into ribosomes that that description is     
6:20     
basically can fit on a thumb dve a typical thumb Dr so that's what they mean by ribosomal     
6:28     
OS then we also talked about a paper on Founder cells and early lineages and     
6:33     
celegans founder cells are those the sort of the precursors of different     
6:39     
sublineages in the lineage Tree in development so it might be Like An     
6:44     
Origin cell for making a lot of cells that become muscle cells or intestinal     
6:49     
cells or neurons or epithelial cells or some other type of cell differentiated     
6:57     
cell in the adult phenotype and so it it was a really interesting paper again on     
7:04     
these early lineage tree lineages and the founder cells and how they sort of     
7:12     
their sort of gene expression and their sort of metabolic Behavior so this is I I did a count on     
7:20     
the number of meetings we had in 2024 we had 43 I think we're going to have another one Monday so that'll be 44 so     
7:28     
we had 44 meetings of dor this year uh we had I think maybe 45 or 46 meetings     
7:34     
of Saturday morning neuros Sim so that's going to be you know and it says     
7:42     
interesting to count up how many meetings you've had over the year and to give a report now as I said last week     
7:48     
I'm going to be um doing an annual report I want to do it as close to the     
7:53     
new year as possible because I may be getting another uh publication go live before     
8:00     
then and I wanted to include that publication in in the final count but I'm getting the presentation     
8:08     
ready and you know kind of going through again doing this accounting it's always     
8:14     
really enlightening to see where you've been to see where you're going maybe and also to know how much work you've     
8:21     
actually done because you always underestimate because you forget things you say oh yeah what about this thing that we did back in     
8:27     
February and it slipped them so this is a good exercise for getting these things out okay so we have this document this     
8:35     
is something Jesse is kind of resuscitated and I've put some things on for     
8:42     
2025 these are these different uh sort of looking towards submissions for next     
8:48     
year so this is um the three that we     
8:54     
have so far we're always on the lookout there's a channel in the slack it's this     
9:00     
call for involvement and events deadlines Channel and we put all sorts of things in here and I'm just taking     
9:07     
things from this Channel and putting it into the spreadsheet so we have sort of a more permanent home for it uh and then     
9:15     
actually it's not the right this is the the channel and so     
9:20     
this is where you know if you have things that you want to post uh maybe     
9:25     
I'll put some of these special issues in although I don't know the people to Target them more specifically we     
9:31     
can uh but anyways those are in this uh Channel and I will try to put them in     
9:38     
this spreadsheet as much as possible so we have three so far we have     
9:43     
embodied intelligence and so this is of course our we do this annually we've done this     
9:49     
since 2021 so 2025 is coming up the deadline for submitting abstracts is     
9:55     
March 1st and you have to register and submit the abstract that the same time it's like one abstract per author so as     
10:03     
in years past we'll try to sort of you know coordinate this if people are     
10:08     
interested in doing multiple submissions if we don't want to do just one submission per for the lab that's fine     
10:14     
too I have a decent idea what we might do but I'm not sure yet um or at least     
10:21     
my submission that I'm going to put in uh so the event is April 2 through 4th     
10:26     
and then you know that's usually a pretty good it's a virtual event they usually have some pretty good     
10:32     
speakers uh it's worth checking out the New York celebration of women in     
10:39     
Computing now Jesse told me that this deadline has been extended so you know we'll we'll fix that when we get the new     
10:46     
deadline but I think Jesse's working on something for that uh it's some sort of     
10:51     
like uh you like he's done in years past to have this ethics Buffet where he's     
10:57     
focused on different topics in the area of AI ethics or Computing ethics or     
11:03     
something and then he's gotten people together to give presentations and so I've par     
11:09     
participated in that in the past virtually and it was pretty good uh you know it's always a nice kind of adds     
11:17     
value I think for the students because it's a lot of undergraduates and they're looking to     
11:23     
sort of get into a research area they're looking to get into     
11:28     
professional uh uh sort of professional development and so you know my actually     
11:35     
I've I guess the uh project management class that I've been teaching has been     
11:41     
influential to some people there we've Al I've also done a number of talks and that's been influential as well so it's     
11:47     
nice to have an impact in that way anyways we'll talk about that maybe     
11:53     
later and then the meta science 2025 conference so this is in uh the UK it's     
11:59     
a live it's a live live person conference but they will actually be having a virtual     
12:06     
pre-conference which is uh I guess right before the conference and I'm going to     
12:12     
look into that more maybe we'll submit something to this and the deadline for that is February 7th so it's it's     
12:20     
actually happening in June and July of the of the new year but the deadline for     
12:27     
submissions is what you're really okay so aside from that we have uh and     
12:33     
and this is coming up sort of at in the first part of the year is uh Google     
12:39     
summer of code projects so I know that Morgan had asked me about how we go     
12:45     
about submitting projects for Google summer of code so the details on that     
12:50     
are you know we need some sort of write up of the project by maybe about January     
12:57     
15 so you know I can put that on the list     
13:03     
too uh put this on here is different     
13:11     
categories and we get a multiple I just want to have a list of projects maybe that we can     
13:16     
pursue uh project     
13:26     
descriptions and I'll put a deadline of January 15th done that and we'll you know we'll kind of go     
13:32     
from there I think the deadline you know I usually have to send these to incf so the deadline is is     
13:40     
somewhat flexible but it's usually about the middle of February so we need to     
13:45     
have it probably by January 15th so we can think about which ones are the strongest ones going forward because if     
13:52     
you want to submit two or three different project ideas then we can work out what that project should look like     
13:57     
that would be good um because we do that a lot you know     
14:02     
every year we have I try to at least generate a couple you know and then I go     
14:08     
through and I find the strongest ones and put those in so I we'll probably be     
14:14     
continuing some of the stuff we've done last year we'll definitely that'll be a high on the list and then we'll have     
14:21     
maybe and I know Morgan wanted to do something with open source and maybe     
14:27     
some of the uh neurol Linux stuff that we've talked     
14:32     
about this year um so that's that's maybe something we can explore further I just need to have     
14:40     
some sort of project description by like January 15th and you know we want to meet over the holiday we can do that     
14:47     
privately kind of in a in more informal session than this so something you think     
14:54     
about yeah that would be great yeah     
15:01     
okay so let's started I had a couple things to talk about so this week was the uh they had uh NPS which is of     
15:10     
course ongoing and I've not been keeping up too much with nups I know they've had there workshops and we had the workshops     
15:18     
and the um tutorials that we went over last week and I haven't seen much uh     
15:24     
outcome from that but you know and then I know they've had a couple Keynotes already so uh let me go through maybe     
15:31     
some of the things online that we've seen so this is the nurbs 2024 site     
15:37     
again uh now they're into the into the conference um so it's going till through     
15:43     
Sunday so they've I think covered a lot of things already um let's see they have some blog entries     
15:51     
from this year a couple blog entries already uh the first one from December     
15:56     
11th was documentary film making at n uh there was this other thing results of     
16:02     
the nurbs 2024 experiment on the usefulness of large language models as     
16:08     
an author checklist assistant for scientific papers uh then then they had the     
16:14     
announcing the nurbs 2024 best paper Awards and then uh then they had the     
16:20     
nurs 2024 experiment on improving the paper review assignment that was     
16:26     
yesterday and of course so there are a lot of practical problems s in the field like how do you assign papers to     
16:33     
reviewers and you know some of these other things about using automating author     
16:39     
checklists and other things I want to get into the pest paper word because I think that's probably the most summarize     
16:47     
thing that I can show you um so every year per say best paper     
16:54     
Awards um so okay uh with that we are excited     
17:00     
to share the news of the best in runnerup paper Awards this year go to Five groundbreaking papers four main     
17:07     
track and one data sets in Benchmark track so they have the main tracks and then the specialized tracks that     
17:13     
highlight respectively new autor regressive models for vision new avenues for supervised     
17:20     
learning using higher order derivatives improved training of large language models and inference methods     
17:26     
for text image diffusion and a novel diverse Benchmark data set for large language module     
17:33     
alignment so yeah there are a lot of interesting Innovations going on here so     
17:39     
the best papers to the main track the first one here is visual Auto regressive modeling scalable image generation for     
17:47     
bya next scale prediction so this is where they're using visual autor regressive     
17:52     
models and these are models that iteratively predict the image At a next     
17:57     
higher resolution rather than a different patch in the image following an arbitrary     
18:05     
order so this is the novel visual Auto regressive model the V model shows     
18:13     
strong results in image generation while performing existing autor regressive models and efficiency and achieving     
18:20     
competitive results with diffusion based methods so we've talked a bit about diffusion based methods in recent     
18:26     
meetings but kind of you know how you um you know how do you implement that how     
18:32     
do you do this with some of the other methods so they're just comparing this with standard diffusion based methods     
18:39     
they're also comparing this with auto regressive models alone and then they're finding     
18:44     
that these uh this mod method is better than both of them at the core of the     
18:50     
this contribution lies an Innovative multiscale bqv     
18:55     
implementation uh which is I don't know what bqv stands for um I     
19:01     
guess something about um visual Auto     
19:07     
regression um so they're doing this at multiple scales of resolution     
19:13     
basically the overall quality of the paper presentation experimental validation and insights or scaling laws     
19:21     
gives compelling reasons to experiment with this model okay so that's the first one the     
19:26     
second one is stochastic tailored derivative estimator efficient demonetization for arbitrary     
19:32     
differential operators so this is a tractable approach to train neural networks using     
19:39     
supervision that incorporates high order derivatives so a lot of stuff that's like multiscale or doing     
19:46     
like uh higher order calculus or things like that interesting how where they're     
19:52     
kind of going with the field such problems arise when training physics and inform networks to fit     
19:59     
certain pdes so these are differential equations partial differential     
20:05     
equations uh so they're trying to use physics informed neural networks to fit     
20:10     
certain partial differential equation Solutions or at least models naive     
20:15     
application of automatic differentiation rules are both inefficient and intractable in practice for higher order     
20:22     
K and high Dimensions D so we have higher orders and higher dimensions and     
20:28     
so we need to kind of fit to those things and so using automatic     
20:33     
differentiation rules don't doesn't cut it so this is where they're kind of coming in with their new     
20:39     
method while these costs can be mitigated independently say for example for large K but for small D or for large     
20:47     
K but small D using subsampling this paper proposes a method     
20:53     
the stochastic tailor derivative estimator or stde that can address     
20:59     
both this work opens up possibilities in scientific applications of neural     
21:04     
networks and more generally in supervising training of neural networks using high order derivatives those are     
21:11     
the two sort of best papers and then they have Runners up for the main track     
21:17     
so they have not all tokens are what you need for pre-training which is where you     
21:24     
basically filter pre-training data when training large language models     
21:29     
the method Builds on the availability of a highquality reference data set on which a reference language model was     
21:35     
trained model was then used to assign a quality score for tokens that come from a larger pre-training Corpus tokens his     
21:42     
scores of the highest rank are then used to guide the final large language model training while the others are discarded     
21:49     
this ensures the final large language model is trained in a higher quality data set that is well aligned with the     
21:55     
reference data set the second paper is guiding a diffusion model with a bad version of     
22:01     
itself which is interesting um so this paper proposes an     
22:06     
alternative classifier for guidance which is CFG in the context of a text to     
22:12     
image model uh CFG is a guidance technique or a correction in diffusion     
22:18     
trajectories that's extensively used by practitioners to obtain better prompt alignment and higher quality images so     
22:25     
this goes in the details of diffusion models and how they're implemented and they're using this adversarial approach to sort of     
22:34     
train the model better to correct the diffusion trajectory um however because CFG uses     
22:41     
an unconditional term that is independent from the text prompt CFG has been empirically observed to reduce     
22:47     
diversity of image generation the paper proposes to replace CFG by autog Guidance which uses a noisy     
22:55     
or less well trained T2i diffusion model this change leads to notable improvements in diversity and image     
23:03     
quality okay that's those are the runners up and then we have the best paper for the data sets in Benchmark     
23:10     
track the prism alignment data set but participatory representative and     
23:16     
individualized human feedback reveals about the subjective Multicultural     
23:21     
alignment of large language models so this is interesting uh alignment of     
23:27     
large language models with human feedback is one of the most impactful research areas of today the key     
23:33     
challenges such as confounding by different preferences values or beliefs this paper introduces the prism data set     
23:41     
providing a unique perspective on human interactions with large language models     
23:46     
the authors collected data from 75 countries with diverse demographics and Source both subjective and Multicultural     
23:57     
perspectives okay so that we've got you know sort of this diversity we also have     
24:03     
um subjectivity and Multicultural perspective benchmarking over 20 current     
24:09     
state-of-the-art models the paper has high societal value and enables research on pluralism and     
24:16     
disagreements in human uh aided     
24:21     
reinforcement um so that's good um yeah so that's sort of the the papers     
24:31     
best paper wordss from nurs um and yeah so I I don't think there's much more to     
24:39     
say about that other than you know I think they're uh they were talking about being     
24:45     
on blue sky during the conference I haven't seen much on Blue Sky from them um but you know they're kind of going     
24:53     
through some of the uh main conference stuff so and I'm sure that those     
24:58     
websites for the tutorials and workshops will also maybe have some videos on them     
25:04     
so we might want to check out what's coming out from that over the next week or so another thing I want to talk about     
25:10     
is the computational Psychiatry conference and I think Morgan posted     
25:16     
this in one of the channels uh this is happening this coming year uh tub and     
25:23     
Jun Germany July 14th through 16th so this is the and the annual conference     
25:29     
this is the 2025 version um now I don't think there's anything we can do virtually we might submit something if     
25:37     
someone wants to go to Germany and present on it I don't know um but this     
25:42     
is basically the website for the upcoming Year's conference and so they     
25:48     
have the program is sort of already in place uh this is actually from 2024     
25:55     
below a 2025 conference will be added when it's available so they have the     
26:01     
2024 program here it's basically you know speakers they have a computational     
26:07     
tutorial on the first day they have a clinical tutorial on the first day and     
26:12     
they have Keynotes um a symposium here where they have a limited number of     
26:20     
speakers um they have the Symposium 2 so Symposium 2 from last year was     
26:25     
reinforcement learning models of physiological state and traits or States versus traits looking at longitudinal     
26:33     
and neural studies uh the Symposium two or     
26:39     
Symposium 3 was computational mechanisms of anxiety trans agnostic effects on     
26:45     
interoception planning and avoidance and I think Ryan we talk Ryan Smith doing this sort of active     
26:53     
inference flavor and he's at this session     
27:00     
uh and that looks like it I think Symposium one was improving task     
27:05     
reliability for computational Psychiatry research other thing I did this week was     
27:11     
I went through our slack Channel and actually the stuff that I've archived on     
27:18     
the Discord from the slack channel so this is over this represents over a year     
27:24     
and a half maybe 18 months or so of post the comput ational neuro neur or     
27:30     
computational Psychiatry and so I put together kind of a list of things here which are the     
27:38     
different topics I put them into three categories and the methods which I put into three categories and this is far     
27:44     
from complete this is just based on some of the things that were posted in the channels so computational Psychiatry of     
27:52     
course we have sort of our own flavor I know Morgan talked about this but basically     
27:58     
I've tried to group things into three categories for each topics and methods so in terms of topics uh for category     
28:07     
one we have a couple things and we have sort of a grouping that includes     
28:12     
epigenetic signatures of Developmental adversity and genetic dependent brain     
28:19     
signatures uh the category two is Network topologies connectum spectral     
28:27     
signatures morphometry continuous statistical Frameworks overlapping system sort of     
28:33     
nervous and immune system interactions and then neuro AI which is a lot bigger     
28:39     
than category one but I think category one would be kind of like genetics     
28:44     
epigenetics Category 2 would be kind of like networks and Spectra and sort of     
28:50     
continual measurement and then of course you have overlapping systems and the     
28:56     
narrow AI part that might actually should be a category 3 so let me put that in there now just     
29:03     
to make sure that I have that as a separate     
29:10     
thing so that yeah I took that off and then category four which would be this     
29:15     
one uh includes Brain Age predictions and deviations so this is where we're     
29:21     
thinking about traj Developmental trajectories and normative Developmental     
29:26     
trajectories and being able to yield information out of that so we have brain age and     
29:32     
predictions and deviations we have individual differences which would be summarized as     
29:40     
personalization we have this idea of the exposome which is the environment so you     
29:45     
know people have tried to quantify the environment and you can think of it as an exposome which is you know then     
29:51     
roughly equivalent to a genome or a proteome or whatever uh then we have genomic or     
29:58     
genetic road maps of the brain that kind of maybe goes into category     
30:03     
one uh but we might just put that over in category one and you know I'm trying     
30:09     
to get like trying to refine this as we go along uh computational neural     
30:16     
development which uh includes infants and changing environments so this is     
30:22     
where we look at like influences of the environment or changing environment on     
30:29     
development in a from a computational lens so all these things have sort of a computational aspect to them so I mean     
30:35     
people have studied people are studying these non-computational sometimes they're using computational methods but     
30:43     
all these things are sort of through a computational lens and then we'd like to bring them together in these     
30:48     
categories so you know the idea would be to kind of work out these different categories give them kind of a name and     
30:55     
then you know if that's something that we want to work in into a paper or into multiple papers or kind of think     
31:03     
about those categories inde dependently and they may be together that's     
31:08     
something we have we can do but I just wanted to get the ball rolling to put these different categories together so     
31:14     
we can kind of you know get things organized now that's topics and then     
31:21     
methods because topics are kind of these areas that you want to study and you're     
31:28     
looking for methods to study them sometimes you'll be doing the meth implementing methods sometimes the     
31:34     
methods are sort of their own thing your own topics and so you want to explore those and say oh yeah this is a method     
31:41     
that people are using so the methods are divided into three categories the first one is uh sort of a combination of     
31:50     
graphical and dynamical systems and Maps so we have graph representation learning     
31:57     
we have d dynamical systems which yield these Pathways which we talked about in say the normative trajectories of     
32:05     
development we have repetition Max of dsm5 symptoms there that was a method     
32:11     
that I saw in one of the posts uh predictive processing of course we     
32:17     
talked about active inference but you know that's kind of maybe that kind of goes in this     
32:23     
category so we might say active inference and predictive processing     
32:28     
uh basian modeling of behavior and what we call temporal depth and for that we     
32:34     
have this dissociation and the tame method in that     
32:42     
area so we have this area called temporal depth that's where we have dissociation and then this tame method     
32:50     
proposed by 11 and we've talked about that quite a bit but putting those     
32:55     
together into this sort of graphical dynamical systems mapping category maybe     
33:01     
with some active inference and predictive processing in fact that might actually be its own category I don't     
33:07     
know how well it fits into that area we might do a category     
33:12     
two that okay and then it's probably its own category anyways because it's quite     
33:19     
meaty uh so yeah then predictor processing being different from active inference but having them kind of work     
33:26     
in the same space category three is gamification and discovering with AI     
33:33     
agents then I have deconstruction here I'm not sure what that means but basically you know this idea that we can     
33:40     
do sort of learning and discovering game you know putting things into games of     
33:45     
agents and modeling things that way so we can have the potential for human     
33:50     
interaction and other things uh category four then is Evo Divo     
33:57     
neuro which is they like to use these kind of compound prefixes in Evo deep     
34:04     
that that kind of evolved from evoo so you have like evoo neuro evoo     
34:11     
neuro eego evoo all these things that are quite frankly confusing but they're     
34:18     
kind of catchy so evoo neuro is the evolution or development of nervous     
34:24     
systems or the development of neuro so this is you know kind of like where     
34:29     
you're combining a bunch of different things um evolutionary Neuroscience     
34:36     
developmental neuroscience and then the intersection of those uh then in that same category of     
34:42     
emotional regulation with neurodevelopmental disruptions or what what I guess was     
34:48     
summarized in some of the stuff was posted there's aberant parenting and then of course your     
34:54     
genetics methods which are gwos and NextGen sequence     
34:59     
so all those things you know they kind of fit in this category of looking at change over time regulation looking at     
35:06     
Evolution looking at the sort of disruptions in the trajectory of development and then looking at the     
35:13     
genetic basis for that so we have all these kind of things in the category for let's move on um so another thing     
35:22     
I'd like to share here is this actually this is kind of shifting from um talking about computational     
35:30     
Psychiatry do some of the preprint issues in neuroscience and some of the     
35:37     
topics so you know we've talked about open science in the last several weeks uh this is get this is from Andrew     
35:44     
pinski on Blue Sky and he's talking about the pre-print battle in     
35:50     
Neuroscience so maybe if if people want a review of this preprints were actually     
35:56     
highly AC accepted in physics and Mathematics for years and of course a lot of the papers     
36:03     
from nepes are also put on archive and that's kind of where they     
36:08     
live and that's where people site them and it's very much accepted to site archive papers in those fields in fields     
36:15     
like biology and Neuroscience however it's not really been the standard we usually get things behind pay walls     
36:22     
especially like abstracts from conferences and things like that and so     
36:27     
it's just the cultural aspect like you know we could have we could talk about in physics where the archive was founded     
36:34     
maybe 30 years ago when they were kind of ahead of the curve in a lot of ways in terms of uh not only accepting preprints but     
36:42     
people putting out preprints and being part of the culture in biology and Neuroscience     
36:48     
there's this sort of anticult of preprints that is that preprints are not     
36:55     
view they're viewed maybe suspiciously maybe people don't want to be scooped     
37:00     
maybe they don't want to get you know ahead of their skis in terms of what they're you know saying about their data     
37:08     
and so forth so it's not so much you know there may be some practical concerns but largely is a cultural issue     
37:15     
so this you know this uh this person is actually part of the uh motor lab or there's like a motor     
37:23     
super Lab at Western University in Ontario Canada and he's one of the investigators     
37:31     
there and they put out this nice uh uh weekly digested papers where they send     
37:37     
out some good uh Mo papers of motor control and sensory motor Behavior so     
37:43     
that's that's where he's coming from um and he's talking about the preprint battle in Neuroscience so according to     
37:50     
Andrew the preprint battle in Neuroscience has gradually been won I think the next step will be more     
37:56     
dramatic collapse and pure of your resources to service each paper so one     
38:01     
of the things about pre-prints of course is it provides open access it provides     
38:06     
Early Access to work it allows people to say take a preprint have people look at     
38:12     
it evaluate it and then have different versions of it where you can improve the     
38:17     
paper before reaching a terminal publication that's one advantage of pre-prints and you know may or may not     
38:24     
have a terminal publication but that's kind of the path that a lot of people Envision for this uh the other thing     
38:32     
though is this peerreview aspect so people have experimented with open peer review where you know you have a     
38:39     
preprint you put it out People review the preprint you get feedback you change     
38:44     
uh the paper accordingly and then eventually you end up issuing sort of a final version or a published version and     
38:52     
this is roughly how the eife model works the E model is where you submit a paper     
38:58     
to ewi they put it up as sort of a pre-print they have open reviews which are published then you have to satisfy     
39:06     
those open reviews then it becomes accepted and then it becomes part of sort of the published stream of papers     
39:13     
on ew now a lot of people frown upon that for various reasons and there's     
39:19     
been this contentious battle between people who think that that's not a good model and people who think it is but in     
39:26     
Neuroscience you know getting this pre-print aspect of the cultural change     
39:31     
out of the way and now we need to focus on the peer review aspect and peerreview     
39:36     
is also a cultural thing I mean we have this culture of peerreview where we review papers we think of it as like     
39:44     
this you know check on quality a check on um you know sort of the verification     
39:51     
of things and as we talked about last week sometimes that's not necessarily the case that you can have     
39:58     
People review a paper and it still be fraudulent because they don't say dig deeply into the data where it's maybe     
40:05     
three sets of eyes instead of 300 so that's that's where we are with this uh so continuing with this thread uh vast     
40:14     
majorities of papers good ones are incremental this is not disparaging expanding on established Concepts and     
40:20     
using standard methods so what he's saying here is that a lot of papers are you know when we develop a paper we     
40:28     
usually start with an outline kind of like what we did for computational Psychiatry there and then we fill in the     
40:35     
outlet we flesh it out if we're collecting data we collect our data and then we see where we are and we     
40:42     
keep working on the paper and a lot of times we we will uh submit the paper at     
40:48     
a certain point and then get peer review feedback and then improve the paper and     
40:54     
then put it out as a publication now if we're not pre printing at that processes uh it's opaque it's not     
41:01     
transparent it's private and maybe it you know at some stage it should be     
41:06     
private but at some point you know we want to get it into PE in front of people's eyes we want to get some     
41:12     
feedback and because of this incremental aspect of developing papers you know we     
41:18     
need to be able to do this uh maybe you know get it in front of enough people so     
41:24     
that we can you know it improves the overall flow and and tenor of the paper     
41:30     
so you're really kind of trying to develop Concepts develop ideas and     
41:35     
experiments and it's really hard to do without feedback we usually get this informal feedback where you know we we     
41:42     
pass it around with people in our lab and we say is this a good idea do you have better ideas but that's again is a     
41:48     
limited pool of people so this this is where pre prints and open pair review     
41:54     
can help as as a vast majority of papers are in Al which means that they just     
41:59     
kind of develop an idea and they don't start with gold you have to find that gold through sort of this iterative     
42:07     
process um it's worth keeping in mind that papers are read mostly by domain experts who whether they reviewed it or     
42:15     
not will still have their own views anyways these don't really need peer review um sometimes you know when you     
42:22     
have people giving an opinion piece maybe we don't want to PE review those     
42:28     
things uh maybe we do uh but you know if you have an opinion and a lot of people     
42:33     
have opinions and you know that's that's not something you need to necessarily peer review because it's something that     
42:38     
is not you know maybe you need to develop the idea more but that's you know just something that     
42:45     
happens with more normal feedback and discussion okay so that's you know we     
42:51     
have this this class of papers that are sort of incremental papers data papers Theory papers ERS we have this other     
42:58     
class of things that maybe are responses to that which are opinion pieces maybe     
43:04     
those don't need peer review as opposed to the other things that may be need peer review is developmental     
43:10     
pieces and then we have this these other types of papers that are making big     
43:16     
claims or whose claims prove to become influential these need much more serious     
43:21     
peer review than they are currently getting and the people doing peer review of these papers need much more credit     
43:27     
for their work so there are these papers that are sort of like Watershed papers     
43:32     
where that influence the field much more than other papers because they're dealing with maybe much more you know uh     
43:42     
sort of Concepts that are being clarified or introducing new Concepts or     
43:49     
maybe there are things that are going to be cited quite a bit sometimes you don't know what those are but sometimes you do and if you're     
43:56     
making big claims if you're making like a you know some novel Claim about human     
44:01     
evolution or you're making some sort of big Claim about uh you know given a uh     
44:07     
like you get access to a big data set and you make some claims I'm thinking of like encode from like 10 years ago or     
44:15     
you know something from a brand new instrument where you're really kind of getting data for the first time and     
44:20     
you're making some claims those need maybe more intensive peer review those are places where     
44:27     
instead of putting usual three people on it or three people that you can get at the time you know having a more formal     
44:35     
system for getting feedback and incorporating it so this is kind of the case for the so peer review especially     
44:42     
for these types of papers but you can also use open peer review for these incremental types of papers as well now     
44:49     
the reason I'm bringing up this thread in part is because there is this nature paper here and in nature human Behavior     
44:58     
the future of academic publishing this says a bunch of uh authors on it including iner     
45:05     
presensi uh Patrick Minal is on this um and some other people um and so this is     
45:14     
one maybe one of these opinion pieces um and it say academic publishing is the     
45:20     
backbone of science dissemination but is the current system fit for purpose we     
45:25     
asked the diverse group of scientists to commit on comment on the future of publishing they discuss systematic     
45:31     
issues challenges and opportunities and share their vision for the future so I don't have the paper kind of I don't     
45:39     
have access to it so we won't talk about that um in depth but just to let you     
45:45     
know that this paper exists and that this is what is referring to in this     
45:51     
post uh he actually has his contribution here which is his position which is a     
45:56     
eliminate peer review the preprint revolution is larg W than one Victory is secured fast and     
46:03     
free access to much of the scientific literature in many Labs including my own the preprint is what is generally     
46:09     
consumed and the eventual Journal version yields little more than a passing scan an update to the citation     
46:16     
manager this new reality puts into sharp relief the nature of traditional peer review an erratic and often perun     
46:23     
process that tends to improve papers that fundamentally alter aling them so this is where he's talking about this     
46:29     
sort of iterative improvement of papers um but what tends to happen is     
46:35     
people will post a preprint and they'll post updates and then kind of like the final version and a journal might have     
46:42     
some minor changes from those ideas that were posted in a preprint and so you know people will     
46:49     
just use the preprint because they can get access to it and because it's virtually indistinguishable from the     
46:55     
final paper so this this speaks to how people sort of treat pre-prints right     
47:00     
like you get things that are sort of late stage development and then you put it in in on     
47:07     
a pre-print server and then maybe you get feedback and then maybe you kind of     
47:12     
go for a formal publication so you know with a lot of these cases you know     
47:17     
people are kind of entering that stream late well what's interesting is you could say enter the stream early you     
47:25     
could put together like a very might call it weak paper but uh you     
47:32     
know it's something that you might want to get people's feedback on maybe it's a very important set of Concepts maybe     
47:39     
it's like our view on computational Psychiatry we don't want to put it all out there and say this is our view and     
47:47     
take it or leave it we want people to say oh yeah that's probably pretty interesting this has maybe been done     
47:53     
before this is kind of trivial Etc ET Etc getting that feedback early might be     
47:59     
actually quite useful for something like that but maybe not so much for a paper that just basically analyzes the     
48:07     
data okay so we should consider that idea the idea that most papers do not     
48:12     
need traditional peer review and in fact if you go back through the history of science you know maybe a 100 years ago     
48:19     
or maybe 200 years ago peer review was not what it is today it wasn't really viewed as a check on thing maybe it was     
48:26     
View as more of a check on quality than maybe like a set of     
48:32     
interactions or maybe they viewed it as a set of interactions without being this sort of you know check on quality or     
48:41     
something so it wasn't like they didn't have the kind of formal system we have today but it was also maybe more     
48:47     
realistic where you just had this um you     
48:52     
know people would give it a yes or no maybe it was driven by the editor and certainly nature is falls into that     
48:58     
category where you know they're basically the editor drives a lot of     
49:05     
decisions okay so you know maybe most papers don't need traditional peer     
49:10     
review maybe we've gotten to the point where we're just applying this peer review model to everything and it     
49:16     
doesn't necessarily mean okay so this kind of copies what he talked about in the thread not     
49:22     
subjecting most papers not subjecting most papers to traditional peer review would save substantial resources author     
49:30     
and reviewer time but also funder money the savings could be invested in more science but also more rigorous peer     
49:36     
validation of pre-prints it introduces new ideas and approaches or begin to Garner substantial     
49:43     
influence uh in practice peer validation would mean that reviewing the claims but also reanalyzing raw data scrutinizing     
49:50     
and rerunning the original code and perhaps even running confirmatory experiments so really we talk about peer     
49:57     
review we're talking about quality checks we're really talking about gatekeeping in the way it's currently     
50:03     
done as opposed to Pure validation which is where you actually go through and interact with the data in the paper at a     
50:11     
very basic level basically deconstructing the paper and reconstructing it and then saying yeah     
50:17     
I've done been able to construct this paper now they people who do things like     
50:23     
uh you there have been a lot of experiments with publishing models such is executable papers what that means is     
50:30     
that you can take a paper and you could execute it say in like an interactive notebook a Jupiter     
50:37     
notebook and you can actually reproduce the paper in that way so in this case     
50:42     
this would be kind of like more like peer validation or enabling this kind of peer validation where you get this um     
50:50     
you know basically I give you the tools and I give you everything you need and     
50:56     
you can walk through the paper and execute the paper as you go through the paper as reading the methods     
51:02     
understanding the methods and then understanding the results going to The Notebook going through the different     
51:08     
kernels of the notebook and executing everything and then everything makes sense and if it doesn't make sense then     
51:13     
you can ask questions or sometimes you see results and you don't know what it is you ask a question and then the     
51:19     
description in the paper might be updated so that it makes more sense to the reader because a lot of times what     
51:25     
we do is you know we make a statement or we     
51:31     
kind of present an idea and it's not necessarily very clear what that idea is     
51:37     
and so refining the idea refining the description unpacking things that need to be unpacked that's really where a lot     
51:45     
of the value of peer review lies sometimes it's detecting fraud and this method can of course unravel that if     
51:52     
you're deconstructing the paper you're interacting with the data certain level     
51:58     
um sometimes it doesn't of course and that's that's where we need to kind of focus our energies too but really kind     
52:04     
of you know making sure that peer review isn't just simply gatekeeping that it's     
52:10     
this sort of Enterprise that um gives us some     
52:16     
insight okay so funders and journals would have to incentivize pure validation because although rare the     
52:22     
effort would be substantial reprints would also need to adapt to include open data and code from the outset this     
52:29     
validation Could Happen years later so you know we could do validation years later if we've Revisited paper in 10     
52:36     
years and see how it looks compared to some new data that comes out or put new     
52:41     
data into the same model and run it and see if it's still valid or you know     
52:47     
whatever there a lot of fun things we could do there uh such a shift from Universal peer review to rare peer     
52:54     
validation fits of the growing desire to change how scientific productivity and impact or evaluated her validation would     
53:01     
be an achievement for authors showing that their work is robust and impactful your validation would itself become a     
53:07     
valued scientific contribution for reviewers this is where you know you get     
53:13     
credit for being a peer reviewer a lot of times in papers they'll list the peer reviewers on the front page like in in     
53:20     
the Frontiers journals sometimes you get like credit through um some of the     
53:27     
metrics but you know and sometimes people will write blog posts about it say I reviewed this paper here's my take     
53:34     
lot of times people will view peer review as confidential but sometimes you know people actually treat it as this     
53:41     
sort of interactive process that as long as it's not mean spirited can be very     
53:48     
enriching so yeah so this is just kind of rethinking this whole relationship     
53:53     
between peer reviewers sort of giving feedback and the authors     
53:59     
of papers and how papers are published so you know we really ideally     
54:04     
we need a shift in how papers are published and presented um so to some     
54:11     
degree the shift is starting with sub journals advertising the review process rather than the outcome by attaching     
54:17     
reviewer comments and author of buttles to the manuscripts they publish but again this is reliant on peer reviewers     
54:24     
really giving a deep throw investigation of the paper or kind of really good     
54:30     
comments and not like a superficial set of comments or mean spirited set of comments which happens     
54:37     
often um so yeah then it kind of talks about there's some discussion here from     
54:43     
people kind of thinking about this problem um yeah so I think the old model     
54:52     
of peer review is kind of unsustainable and you know know we need     
54:57     
to kind of think about a newer ma newer way to to sort of go over papers and     
55:03     
evaluate them so that's all I'm going to talk about for that now I want to get into     
55:10     
some papers this is a paper that I think we've gotten this came out in November     
55:17     
this is from the journal neuro informatics um this is on interdisciplinarity and collaborative     
55:23     
training in Neuroscience insights from the human brain project education program so this is highlighting the     
55:31     
human brain project and they have this educational arm that kind of grew out of     
55:37     
their main project so you know it's kind of like where you know a large funded     
55:43     
project might have some Outreach components they might have some educational components they might have     
55:49     
an open- Source Community these sorts of things so this is describing their training and education program that     
55:56     
they've kind of developed alongside the human brain project main focus which is     
56:03     
data and modeling so this is where you know we have a number of authors I'm not     
56:08     
familiar with any of these people but um they were involved in this effort so uh     
56:15     
the abstract reads Neuroscience education is challenged by rapidly evolving technology and the development     
56:21     
of interdisciplinary approaches for brain research the human brain project     
56:26     
HBP education program aimed to address the need for interdisciplinary expertise     
56:31     
and brain research by equipping a new generation of researchers with skills     
56:37     
across Neuroscience medicine and information technology so this is where you know we     
56:43     
have the human brain project it's producing this new type of data it's producing resources for     
56:50     
Neuroscience uh but we need to have this sort of EX inter disciplinary expertise     
56:56     
and I've seen this throughout my career where you have these projects that are ambitious they bring together     
57:02     
computation and biology and you know other areas and you     
57:08     
need to train people you know you bring together experts from different areas and sometimes they talk past one another     
57:15     
sometimes they kind of don't understand the big picture and so there's always this aspect of these kind of projects     
57:21     
where they try to get people you know they try to build training programs that     
57:27     
are inherently interdisciplinary so you can build not just expertise in one area     
57:32     
or another but build expertise to see this big picture and I think it's been a mixed     
57:39     
success I think sometimes people you know benefit more from some     
57:44     
of the siloed thinking some of the siloed expertise that's coming together so like you know if you're like a     
57:51     
neuroscientist you might find some Niche Neuroscience oriented Niche that is     
57:56     
improved by the interactions with computer scientists and vice versa so if you're a     
58:03     
computer scientist you might find an area that really benefits from interacting with neuroscientists and then other people     
58:10     
benefit from this interdisciplinary view which is to see the dialogue between the two fields and     
58:16     
sort of pick up on themes in that interaction so I don't think it's you     
58:21     
know I think there's this aspect of Education that's really valuable in a lot of these kind of projects where you     
58:28     
have this bigger conversation you have this synthesis that's going on you know between different fields I don't think     
58:36     
everyone really can you know build upon that I think it's certain you know     
58:41     
certain types of sort of synthetic thinkers maybe people who are more theoretically oriented but it does     
58:47     
benefit everyone and so this is kind of the uh sort of the goal of what they're trying to     
58:54     
do so you know really what they're trying to do in this educational program     
58:59     
is equip a new generation of researchers with skills across Neuroscience medicine     
59:04     
and information technology over its 10year duration the program engaged     
59:09     
over, 1300 experts and attracted more than 5500 participants from various scientific     
59:16     
disciplines in its Blended learning curriculum specialized schools and     
59:22     
workshops along with events fostering dialogue among early career researchers     
59:28     
so there are a lot of ways in which they approach their educational Mission they     
59:33     
have this Blended learning specialized schools and workshops events fostering dialogue among early career researchers     
59:40     
this is very typical of a lot of the approaches that other projects have used where they kind of host workshops     
59:47     
they'll have like these sessions where they kind of get people together kind of talk about the key issues how to address     
59:56     
D them forward you always focus on early career researchers because they're going to be putting their careers out there in     
1:00:01     
front of this initiative so the idea is that their whole career was influenced by this kind of uh     
1:00:09     
interdisciplinarity by this kind of you know in bold     
1:00:14     
initiative key principles of the program's approach included fostering interdisciplinarity adaptability to the     
1:00:21     
evolving research landscape and infrastructure and collaborative environment with the focus on empowering     
1:00:27     
early career researchers so this is a whole set of words here um the versus fostering     
1:00:35     
interdisciplinarity so again that can happen in a number of ways basically pulling disperate Fields together     
1:00:42     
sometimes siloed fields and kind of exploring the intersections between those it might be like having a course     
1:00:49     
on neuroinformatics which is of course combining informatics computer science     
1:00:54     
with neuroscience it could be you know some sort of interaction     
1:01:00     
between neuroscientists and computer scientists where you know you need to     
1:01:05     
learn if you're a neuroscientist you need to learn computational tools if you're a computational person you need     
1:01:11     
to learn neuroscience and that's of course the second part which is adaptability to the     
1:01:17     
evolving research landscape and infrastructure basically when we have these new technologies come out it could     
1:01:23     
be nextg sequencing it could be uh you know this sort of     
1:01:30     
omix any sort of omix it could be you know new computational tools it could be     
1:01:36     
new Neuroscience tools Etc that you are able to adapt to those     
1:01:42     
you can learn about these things you have a space to learn about them and so     
1:01:48     
forth and then a collaborative environment with a focus on empowering early career researchers so this again     
1:01:54     
you know where you have this open collaboration it's not siloed it allows early career researchers to take full     
1:02:02     
advantage so they kind of describe this whole setup of their uh educational     
1:02:07     
program and then you know eventually these programs end so you have to sort of close things down uh in in under the     
1:02:16     
perview of the program and you have to write a report to your funer but then you sometimes you keep some of these     
1:02:21     
things going so a lot of these projects will have like a uh educational arm     
1:02:27     
where they'll try different things during the course of the maybe a 10-year program they'll take the best things     
1:02:35     
that come out of that and they'll spin them off and so this is where you know you     
1:02:41     
can do some great experimentation and figure out what works and what doesn't and then spin off     
1:02:46     
the most successful stuff so they provide an analysis and     
1:02:52     
end up view across a diverse range of educational formats and events our results show that the educational     
1:02:58     
program achieved success in its wide Geographic reach the diversity of     
1:03:03     
participants and the establishment of transversal collaborations so this is where you know     
1:03:09     
we you get people from around the world a lot of times it's because you have you     
1:03:15     
know different collaboration sites sometimes you engage in a strategy of doing virtual education and virtual     
1:03:23     
Outreach you get people from different populations you get people from different perspectives and areas and     
1:03:30     
then the establishment of transversal collaborations where you get collaborations from different places in     
1:03:37     
science maybe people from the broader community and you get them working     
1:03:43     
together uh and a lot of that revolves around education because you can't really have successful collaboration     
1:03:50     
unless you have some educational aspect to it where people are learning from each other and there's some engagement     
1:03:57     
there building on these experiences and achievements we describe a leveraging digital tools and platforms provides     
1:04:04     
accessibility and highly specialized training which can enhance existing education programs for the next     
1:04:11     
generation of brain researchers working in decentralized European collaborative spaces finally we present the lessons     
1:04:18     
learned so that similar initiatives May improve upon our experience and incorporate our suggestions into their     
1:04:23     
own program so this is where they kind of go over this     
1:04:29     
um a couple words about interdisciplinarity here um in this     
1:04:35     
investigative Pursuit the fields of Neuroscience and Engineering these are the two fields that they've defined in     
1:04:41     
their project have integrated on many levels over the last decades resulting     
1:04:46     
in deeply interdisciplinary research Fields this Synergy has been fueled by rapidly evolving methods the collection     
1:04:53     
of methods and technologies that enable collection of large data setss analysis     
1:04:59     
on an unprecedented scale and large scale simulations which include high     
1:05:05     
resolution recording techniques and high performance Computing some of these methods were not new as such and were     
1:05:12     
widely used by other communities but not yet applied for Neuroscience research so     
1:05:18     
a number of fields have emerged from this sort of interaction from this Synergy these include neuroengineering     
1:05:26     
neuroinformatics and computational Neuroscience but these developments require educational and training efforts     
1:05:33     
that equip both emerging talent and established scientists with the skills and mindsets to remain competitive at     
1:05:40     
the Forefront of Discovery so this is where you know we have to approach this in different ways while some     
1:05:46     
universities and institutions offer courses combining computer science and Neuroscience there is a scarcity of     
1:05:54     
reports on integ in computational approaches in Neuroscience     
1:05:59     
curriculum and the traditional mathematic Ro requirements for Neuroscience majors are often lacking in     
1:06:05     
their ability to allow people to analyze big data sets and other things that are     
1:06:11     
needed so this is really kind of the idea here um you want to give people the     
1:06:18     
skills they need sometimes the skills aren't in the current curriculum so you need to expand the curriculum but we can     
1:06:24     
only learn some much we only have so so much time to achieve that curriculum you know so we can't we needed to learn if     
1:06:32     
we wanted to get people in a training program to learn everything they needed you know we'd be they'd be there 20     
1:06:38     
years and we don't want that we want them to learn things fairly quickly we want to get them through a degree     
1:06:45     
program quickly and get them out in practicing science instead of constantly     
1:06:50     
in like training so you have to figure out ways to do that and so they're     
1:06:55     
showing here is this figure that shows kind of the participant range which means that they have these events that     
1:07:02     
are both small and large and then the level of specialization which is where you have     
1:07:09     
different types of resources for learning so they have their sort of     
1:07:15     
their resources here so the the first thing here is this uh human brain project education e Library which     
1:07:22     
contains materials produced at education events and other lectures and learning material so this is where you have these     
1:07:29     
sort of archived materials things that can be accessed as um a     
1:07:36     
asynchronously and they have around 700 videos so this is a very large number of     
1:07:44     
potential training events that people can visit and interact with the second one is the human brain     
1:07:51     
project curriculum on interdisciplinary brain research this is where you have Blended learning     
1:07:57     
courses where you have like online courses with related workshops teaching     
1:08:03     
core research Concepts and complimentary subjects to non-sp Specialists and this     
1:08:08     
involves six courses and 17 workshops so again plenty of opportunities to     
1:08:13     
interact they had young researcher events which uh introduced early career researchers to this EB     
1:08:20     
brains uh focus and then focused on communities beyond the human brain     
1:08:25     
project and for that they had seven distinct events that were hosted they also had seven student     
1:08:33     
conferences which allowed early career researchers to collaborate and exchange ideas this human brain project school     
1:08:40     
which were a series of advanced lecture-based courses with additional training sessions for certain techniques and soft     
1:08:47     
skills that was eight events the ebrain workshop which was this ebrain     
1:08:52     
initiative multi-day workshops introduced to tools and services available via the ebrain research     
1:08:59     
infrastructure that was five events and then the E brains infrastructure training events which allowed us to get     
1:09:06     
access to This research infrastructure that's 35 events so you can see in a     
1:09:12     
sort of an initiative that you can structure things in a way that maximizes the number of sort of interactions and     
1:09:20     
sometimes these things are asynchronous and maybe like background and sometimes they're things that are more or suited     
1:09:25     
to these more intense interactions where you're engaging in like classroom     
1:09:31     
setting or conference setting or some sort of social setting I just wanted to go I thought that was an interesting     
1:09:37     
thing to talk about in light of some of the open research open science stuff     
1:09:42     
we've been talking about recently and how to structure sort of interdisciplinary training program     
1:09:50     
around those things yeah I mean     
1:09:55     
that's interesting too just uh thinking about it in terms     
1:10:01     
of um what role like Nur X has and what     
1:10:09     
resources are kind of there for for the people that NCH X is     
1:10:16     
bringing in yeah um that's     
1:10:21     
um that's kind of interesting yeah so so do they have like     
1:10:27     
like a YouTube channel or do they have like horses or do they have what are their resources     
1:10:32     
now in terms of EBR yeah yeah I mean all of those things     
1:10:39     
right I mean um uh you know I haven't I probably     
1:10:46     
haven't spent as much time on them as as I did when um it was you know human project     
1:10:56     
yeah um or when it when it had that branding um but you know I I believe     
1:11:04     
almost everything has been folded into that um so     
1:11:12     
um and there's still you know C and Ammons and     
1:11:18     
um and I mean she's she's certainly the the the face of e brains as the     
1:11:26     
director uh you know she's she's giving talks I I I think they still I mean you     
1:11:33     
know that proba are having webinars that are focusing on particular platforms     
1:11:39     
that they have um um but I mean you know there's     
1:11:47     
definitely I wonder how much in this new iteration there's been less of a     
1:11:55     
less emphasis on the I don't know what you want to call     
1:12:01     
it but like you know basically the the neuromorphic Computing the neurorobotic     
1:12:07     
extra activities or you know like I don't to say extra     
1:12:16     
um you know how how much have they gotten past kind of brain Imaging and     
1:12:22     
brain modeling right you know and and um     
1:12:28     
which was definitely yeah I I I wanted to say I mean as soon as you brought     
1:12:34     
this up I I wanted to point out that um uh Henry     
1:12:41     
marcam um is it Henry yeah um has a     
1:12:48     
um it's the 20th anniversary of blue Brain Project okay um     
1:12:56     
and you know and they're you know he's definitely doing a kind of you know     
1:13:02     
retrospective covering all of their obviously what he wants to to call     
1:13:09     
successes um we can certainly say there's been a lot of outputs you     
1:13:17     
know and um and yeah you know but but     
1:13:26     
right I mean and like a lot of you know certainly a lot of the kind     
1:13:33     
of computational Neuroscience that um was human brain     
1:13:39     
project was was very much blue brain yeah or or I I you know like you     
1:13:46     
said they talking about just the extension of projects past their past     
1:13:52     
perhaps their their you know original funding or something like that like you know blue Brain still cranking out     
1:13:59     
software packages and releases you know and I mean I'm sure he's brought in new     
1:14:05     
funding and things like that but oh yeah um they had a lot to they had a lot to     
1:14:11     
build on um uh but I I'm also just trying to     
1:14:17     
think I mean you know I I don't know if we're going to make this particular     
1:14:22     
um advancing inform stem learning Grant     
1:14:29     
um uh I think I think the biolab is going     
1:14:34     
to be involved in in something that's being submitted but but in terms of like narch X and things like um you know how     
1:14:45     
much you know I'm interested you know ICF does a lot right     
1:14:51     
to like like of I mean Beyond you know they they do some kind of     
1:14:58     
community building or certainly like trying to get roll out kind of platforms     
1:15:03     
for people um you know I'm just trying to think of     
1:15:11     
projects that have been successful in terms of not only getting an output but     
1:15:18     
also kind of creating um creating community     
1:15:25     
for for it and kind of like a I want to say ecosystem but like     
1:15:33     
um you know like real training program I I mean I for instance um or you know I I     
1:15:43     
I really love the neuropixels workshop from     
1:15:49     
UCL oh yeah um and you know it's like it's a recurring thing you know great     
1:15:55     
lineup of speakers to make all the talks available you know you can really give yourself a um you know a pretty     
1:16:05     
comprehensive education from from all the     
1:16:10     
um of the the resources that they you know help curate and and um and publish     
1:16:19     
for you you know what I mean yeah yeah like like I don't I don't     
1:16:27     
see I don't you know I think it's one of the things that like I'm kind of     
1:16:33     
disappointed that blue brain for instance doesn't do or you know     
1:16:40     
again I might not be aware of it but like you know there's there's there's     
1:16:47     
not as much emphasis on on the     
1:16:53     
um how to get the tools better integrated into other     
1:16:59     
people's you know work and and especially kind of what seemed to be the     
1:17:06     
focus of that paper was like you know for for getting early career     
1:17:13     
researchers you know um using using these tools or using     
1:17:19     
these Technologies right um again it's it's it's um I don't want     
1:17:27     
to say other people should be you know doing more it's yeah but but but you know I     
1:17:35     
mean just saying like in terms of thinking about like the effectiveness of of     
1:17:42     
um you know o Open Source software being more than just I I've got it up on     
1:17:50     
GitHub yeah and and and you know again     
1:17:55     
like I I think some of the criticism to     
1:18:00     
um to human brain project was you know     
1:18:06     
like you've got these platforms out you know but there's not     
1:18:13     
enough kind of ramping people up into getting getting more people than the     
1:18:19     
people that developed them using them yeah but I again this is you know I I've     
1:18:27     
I've perhaps got an Outsiders perspective and you know I know that they were certainly trying to collect     
1:18:34     
metrics and things like that     
1:18:39     
yeah yeah the metrics are you know kind of interesting because you you have these alt     
1:18:45     
metrics which allow you to measure things that are not like Publications necessarily so it's like you know how     
1:18:52     
many people are hitting our gith repos itory we put something up on like an     
1:18:57     
archive like dry uh dryad which is like open data how many people are hitting     
1:19:03     
our open data set you have these kind of rough measurements and it's like hard to know who's actually engaged in in these     
1:19:11     
sorts of things so if someone looks at your open data said how much are they engaging in it how much are they using     
1:19:17     
it what are they using same thing with the GitHub repository are they really they Fork are they really adopting it or     
1:19:24     
they just kind of using looking at it and you know and it's hard to to get like facilitate all that and get really     
1:19:31     
good not just data but like good a good sort of assessment of how successful you     
1:19:37     
are yeah yeah yeah it's it's it's a good point I mean and you know I I I hadn't     
1:19:45     
commented um on your earlier kind of section but you know again     
1:19:52     
like yeah what what what are the incentives around polici oh     
1:19:59     
yeah you know is is a is a a really interesting question and you know I I do     
1:20:06     
think that there's you know there's been just a kind of a backlash     
1:20:12     
to um you know like an earlier time when     
1:20:19     
kind of journals had a purpose right as a gatekeeper um like only so much could be     
1:20:26     
published and obviously that's just not true anymore um but that that there became     
1:20:33     
this you know that the incentives to get published became you know overriding say     
1:20:41     
the you know what what everybody found which was     
1:20:47     
reproducibility and and you know and again perhaps even you know the the directions and the     
1:20:55     
you know it it's it's um it kind of begged a certainly positive results and     
1:21:02     
and perhaps even a kind of um overly overly sophisticated um approaches     
1:21:10     
because again you you know you had to pass this Gauntlet     
1:21:15     
um but any it I'm I'm much more interested in     
1:21:21     
terms of the the the kind of incf questions like what's what's good for fostering     
1:21:28     
collaboration and fostering more well and     
1:21:35     
fostering you know multidisciplinary collaboration you know     
1:21:41     
yeah and you know how yeah what what gets what gets people over kind of the     
1:21:48     
activation energy that um um is required for that kind of you know that kind of     
1:21:57     
um you know what is B probably most appropriate is kind of multi-investigator um     
1:22:06     
collaboration yeah yeah it's always the key getting that like sustaining it not     
1:22:12     
just like that's interesting I learned something yeah     
1:22:18     
yeah no that's a interesting to see that paper yeah     
1:22:25     
yeah I think with with publishing too like you we can publish anything we can put things out like it's the barrier to     
1:22:32     
publishing is lower like you can get things formatted and stored like uh when     
1:22:37     
I was talking with the active inference Institute one thing they really interested in or that Peak their     
1:22:42     
interest was um overlay journals where you create like you have an archive of     
1:22:49     
papers and then you create a skin that kind of curates everything and you know     
1:22:54     
the journal at that point is largely a curation function so like you can app here review and you can add that to it     
1:23:00     
but the curation is the key how is it presented how do we get this into     
1:23:07     
people's hands so that they understand like what the significance speed paper is but they can find it and that brings     
1:23:14     
up the point that really the constraint Now isn't like it may been like 200 years ago where you would print things     
1:23:21     
and get them to people you know so you might have people need to get a copy state of     
1:23:27     
origin of the species and like in Germany you know origin of the species wasn't translated into German until     
1:23:33     
decades later and so then as a result you know that scientific Community you     
1:23:39     
know kind of had their own sort of Developmental trajectory with respect     
1:23:45     
to that work I mean and we had you know Publications like that up until very     
1:23:51     
recently where there's this gatekeeping function you know where you're seeing certain papers you're not seeing other     
1:23:57     
works but of course now we can digitally publish a lot of things and sometimes     
1:24:02     
those things aren't great but you know but the thing is attention you know that's the constraint now and I think     
1:24:09     
you know like from how people you know constantly complain that there's so many papers that they're     
1:24:16     
overwhelmed and you can use you know uh you can use like uh you know biblio     
1:24:24     
graic uh tools bibliometric tools to sort of sort through all the papers out there to see     
1:24:31     
the most relevant ones but it really is a matter of attention more than like     
1:24:37     
storage or transmission so that changes things because now you know it's like     
1:24:44     
how do I get people's attention is it going to be through some prestigious maybe more prestigious Outlet you know     
1:24:51     
maybe is it that people go to like nature.com and they see what the latest papers are and that's what they pay     
1:24:57     
attention to or is it like some tool for like preprints so like the archive of     
1:25:03     
course is notorious for having these dumps of papers in different categories and you have to sort through them and     
1:25:09     
figure out which ones are most significant or do you rely on some you     
1:25:15     
know set of our you know sort of set of archival     
1:25:21     
filtering expertise sort of uh ways of finding the best papers like I talked     
1:25:26     
about how the sensor motor super lab has their email list where they kind of     
1:25:32     
curate the papers and they say this is what we we're reading and you know     
1:25:37     
wouldn't it be great if you're reading it too uh but you know so those are the     
1:25:42     
I think that's the constraint and it's actually a little bit harder because that means that peer review is different     
1:25:49     
it's about you know kind of it's about quality control maybe it's not so much about gatekeeping but it's about getting     
1:25:56     
attention on things and that's diff that's a different set of things that we have to worry     
1:26:01     
about um we don't want things that are clickbait like that's basically how the     
1:26:06     
internet's handled attention and that's not what we want we want something more     
1:26:12     
productive yeah me I thought it was interesting talking     
1:26:20     
to um Conrad cording     
1:26:26     
um about why he was what why he was so interested in in     
1:26:35     
you know to some degree kind     
1:26:41     
of moving into a kind of new area for him you know and um and I think it's interesting     
1:26:50     
to think about how much you know there was this time Tim     
1:26:56     
Barons was kind of called out for the fact that his lab had had kind of     
1:27:04     
given each of the brain areas a um had been associated with a pi oh yeah     
1:27:12     
unless it's like this this Pi is the you know amydala person and this Pi is the     
1:27:19     
you know whatever part of the thalamus um     
1:27:27     
you know and leaving aside you know the reasons that he was called out for that the main     
1:27:34     
thing being that like at the same time there is a certain you know you you get you know     
1:27:42     
funding in an area you get started in an area um that that becomes the papers     
1:27:49     
that you kind of need to read right yeah and and it it it does you know when when     
1:27:57     
we talk about researchers becoming a little you     
1:28:02     
know I don't think siloed is the right term but you know     
1:28:10     
um needing kind of attentional blinders yeah you know you know in a in a you know     
1:28:18     
somewhat Justified way in that you know like this is     
1:28:24     
this is the report that they're going to need to write in three years or five years or one year right and and so you     
1:28:33     
know it's um um being able to open your searches     
1:28:39     
to the internet is is something you know um is is kind of a luxury that a lot of     
1:28:46     
people don't have yeah um so you know I I mean I I like what you're saying about     
1:28:52     
like you know like there is something about being a gatekeeper um when when Publications and     
1:28:59     
and certainly the kind of dissemination of them um you know involved     
1:29:06     
Logistics but but there is something certainly to be said for you     
1:29:12     
know you kind of have to be in the right email groups or you know I mean my     
1:29:20     
advisor would say all the time that like being an editor of Her     
1:29:25     
Image was was being a or you know like I     
1:29:32     
forget if he was like not editor but you know but being a person as part of a journal especially kind of a a premier     
1:29:41     
journal for a particular field that that was his way of knowing     
1:29:46     
what he should be reading you know yeah right and and you know so disc you know     
1:29:54     
finding finding reviewers for things um deciding you know what was what was good     
1:30:01     
what wasn't or you know um U what were     
1:30:07     
themes that they were going to to be suggesting and things like that was you know a a real way to you know Steer the     
1:30:17     
conversation in kind of a journalistic way right and um and yeah it it is kind of     
1:30:25     
it is you know I I certainly know the problem where you go to meetings and and     
1:30:31     
you know not everybody's read the same verse yeah and you know there's there's     
1:30:38     
there's something cool to that in the sense of like it's great to kind of spread the word but it's also like like     
1:30:46     
we have to meet again where you've read those papers and now we can actually have a a proper discussion yeah     
1:30:54     
you know and um yeah anyway I I I I I'm sure you got more stuff so I don't want     
1:31:00     
to bog down here but you these are really interesting you know these are     
1:31:05     
really you know um it's     
1:31:13     
it's u in trying to think about what role neurot X     
1:31:20     
has it's interesting in that you know I think one of the first things that I     
1:31:26     
have to address is like who is our real audience like who who who are we helping     
1:31:33     
in in you know I think our lack of analytics in terms of you know     
1:31:39     
um do do students engage more you know is it is it programmers is it you know     
1:31:47     
because you know I feel like we really need to tailor what we're we can only do     
1:31:52     
so much and we you know so we need to we need to um absolutely be kind of like     
1:32:01     
a kind of like a journal in the sense of you know we need to know what we're what     
1:32:06     
we should be curating yeah yeah that's a that's a common thing     
1:32:13     
we found in open worm I used to be on the Community Committee there and we we we thought about this problem and we     
1:32:18     
never really solved it of course but um so I mean you know one of the things there that you get people who are     
1:32:26     
interested in like well a lot of people who are like computational people might     
1:32:31     
be software Engineers or programmers or something and they come into this world where there's like this     
1:32:39     
aspect of biology aspect of Neuroscience aspect of computational stuff and they want to find a place you know and then     
1:32:46     
there are other people who are biologists who want to know more about the computational side so you get these     
1:32:52     
skill sets that people we're kind of entering in with and then it's kind of the job of that Community or people     
1:32:59     
running the initiative to sort of balance it out like say if you're you know you want to work     
1:33:05     
on a problem here's what you need to know you need to get up to speed on maybe some of the aspects of the biology     
1:33:11     
but you don't want to treat it like you're teaching them biology in a biology course because it's not they're     
1:33:18     
not you know it's not going to be the the same thing they're looking for because they there ultimately applying     
1:33:24     
it in a different way so you want to figure out kind of what what captures their attention and sometimes you don't     
1:33:31     
know what that is it's kind of like um you know what might capture a bi biology     
1:33:37     
students attention isn't the same thing that would capture an engineering students attention and vice versa and     
1:33:43     
there are things that they pick up cues that they pick up on that are sort of connected to what they've been doing     
1:33:49     
previously that resonate with them so that's that's one thing and then you know trying to collect data on this is     
1:33:56     
like we never really got beyond the questionnaire stage like you might ask     
1:34:01     
people what they're interested in but you only know they can only tell you what you ask them so it's like okay well     
1:34:09     
that's um that is something you need to work out more and it's It's Tricky it's not easy to do yeah yeah so I mean you     
1:34:17     
know it's really I think really thinking about this at multiple levels like what     
1:34:23     
kinds of resources can we make for you know different kinds of things that people maybe want to do in the     
1:34:30     
community do they want to uh you know learn maybe primarily be educated on on     
1:34:37     
certain things do they want to work on a project where they have very applied     
1:34:44     
interests they want to sort of just hang back and absorb the     
1:34:49     
community and that that's a that's a valid thing in it requires different sets of things to to present to them     
1:34:57     
like um maybe like Recaps of what people are talking about or bigger questions or     
1:35:03     
something like that yeah yeah yeah well it's it's you     
1:35:11     
know getting getting that feedback I I have I have new found respect for how hard it is to get that feedback yeah     
1:35:19     
yeah yeah um yeah it's kind of like kind of like getting students to to give you     
1:35:27     
giveing you meaningful evaluations at the end of the semester oh yeah not just     
1:35:33     
not just complaining that like yeah I'm gonna check that out and um     
1:35:39     
yeah it's it's um it's worth uh digging into e brains a little bit yeah     
1:35:47     
definitely you know I mean that the the other thing that I'm kind of looking for is is you know     
1:35:54     
how much you know I say like blue brain's not you know doing enough     
1:36:01     
yeah you know that's not true um but they're not doing enough of of this this     
1:36:07     
kind of work like is that is that a niche that would be worthwhile filling you     
1:36:14     
know or you know because I I've been I've been kind of uh I was     
1:36:21     
really I think I mentioned this when covered Montreal Ai and Neuroscience the     
1:36:26     
main meeting yeah you know you know I noticed that the the kind of tutorials     
1:36:33     
that they had or I forget the workshops associ I think it was tutorials you know     
1:36:39     
they had this pyit learn emphasis yeah you know and and     
1:36:45     
which I thought was interesting for you know for kind of like one of the Premier     
1:36:52     
neuro AI conferences right um uh you     
1:36:58     
know why why weren't they doing one of the fancy the Fancy Pants things you know um but but I I yeah I'm I'm really     
1:37:08     
interested to know you know because I I I still see that as you know if you were     
1:37:15     
gonna actually do some work in the real world right right like like that's kind     
1:37:21     
of like that's kind of like the frame you know the framework you should probably go to First yeah you know and     
1:37:28     
and um and you know get to know your data set like you know you don't get to     
1:37:34     
know your data set with pytorch right yeah you know you know you get to know your data set with stats and you know     
1:37:42     
visualizations and things like that right right and um and you know that that that     
1:37:51     
there was some good overlap between you know this ntic X Project Moab and and     
1:37:56     
what what Maine was doing right and that that you know if we if we've did a     
1:38:03     
little bit of work in terms of just uh you know trying to trying to adopt some     
1:38:08     
of their tutorials like that would be a really nice you know it'd be a nice kind of on-ramp into this     
1:38:14     
project yeah and just how many how many other kind of opportunities like that     
1:38:19     
are there um anyway I'm I'm not at anything for this point okay     
1:38:27     
well something to follow up on and I I I have I have I've been using I don't know     
1:38:33     
what you maybe created the channel for necessarily but the um edigi Channel it     
1:38:41     
it is like you know that's where we got that paper that's where I got that paper from yeah you posted it there November     
1:38:48     
no no that's good that's good I mean but you know it's like like I I am     
1:38:54     
I am I have been using that as a as a place to put you know when I see people     
1:39:01     
who are trying to do something in that regard well trying to do something new     
1:39:07     
or trying to think about something sorry I didn't maybe I missed that when you introduced the paper oh well yeah I     
1:39:13     
don't remember I don't think I said where I got it but yeah it was posted in that channel so um and then there's some     
1:39:20     
other things in here as well but yeah we'll have to kind of about some of these alternative models because I think     
1:39:26     
they're useful for like open source education how do you get people in the     
1:39:31     
on-ramp as you say projects and that sort of thing yeah yeah yeah I I I mean I've been thinking     
1:39:38     
about it you know like like I I you know I'm I'm kind of liking some of the things that are posted here like like     
1:39:45     
this artam cir and kov um you know he's now a researcher at     
1:39:52     
NYU right yeah like Center for non conversation you know and and you know     
1:39:58     
again like like okay that's that's awesome because you know his his videos     
1:40:04     
you know we don't need to kind of replicate his videos you know we just     
1:40:09     
needs to kind of curate them and and see     
1:40:14     
how we can support people with say some of the materials that he's already listed in his you know in his YouTube uh     
1:40:22     
um um descriptions you know yeah like like there's already this this this great     
1:40:29     
amount of material that just kind of needs to be um better organized for     
1:40:34     
people yeah and um um I forget what the     
1:40:41     
arc Alpha how would you say this Alpha C oh     
1:40:46     
yeah alpha kive or whatever kive thank you yeah this is uh     
1:40:53     
source that I've yeah I've been playing around with so yeah it's this tool Alpha     
1:40:59     
kive you can turn any pre-print an archive and a conversation using     
1:41:04     
elive a new SP project sponsored by archive Labs so this is yeah where     
1:41:10     
they're kind of doing this I guess peer review of the preprints or commenting on     
1:41:15     
the preprints it's kind of a nice tool um I mean I I I you know been a um     
1:41:25     
certainly a like early supporter of um for Mass library in terms of you know     
1:41:32     
what they were doing but like like like you said     
1:41:38     
like is that is that the way in which you can kind of get a a larger group to     
1:41:48     
narrow down on a small set of papers that they're going to read and and     
1:41:53     
really digests so that you know it can become food for discussion or you know     
1:42:03     
um springboards to you know new research initiatives yeah I mean like like yeah     
1:42:14     
anyway um I'm I'm I'm curious how to     
1:42:19     
well yeah I mean I I I I I know there's some you know there's things like Nur     
1:42:27     
Stars right yeah and but you know Nur starts seems     
1:42:33     
like it's more it's more text board you know yeah it's it's like how to sort of     
1:42:40     
which I mean which does seem like what it was intended right you know but it's     
1:42:46     
like I kind of feel yeah like you know I don't know if that Community     
1:42:54     
exists or you know because um I mean to some degree you know I learn a lot from     
1:43:01     
following like a couple mailing lists in my field yeah um but it's not it's not     
1:43:08     
where people post their papers or you know like unless their their paper comes     
1:43:15     
up in the context of some analysis question or something like that you know     
1:43:21     
yeah it's not so much like hey everybody you should read this you know um anyway     
1:43:27     
I think that might also just be you know not not being in a in a lab that's got a     
1:43:34     
particular kind of funding Focus where you know obviously again there's there's     
1:43:39     
a real need to stay um to to to be familiar with you know     
1:43:47     
the five to ten other labs that kind of are doing that work you know what I mean     
1:43:53     
yeah yeah yeah so um yeah we'll move on um     
1:44:01     
yeah but yeah interesting stuff so so yeah so the last thing I wanted to talk     
1:44:06     
about this year in our meetings is this collection of papers on embodied in     
1:44:12     
evolutionary approaches to morphology so we've talked about sort of morphology is     
1:44:17     
part of this embodied cognition so we have the um you know bodies of of agents     
1:44:26     
and we talk about the brains of the agents and we talked about morphological computation which is how that morphology     
1:44:34     
is organized to support cognition in the internal model of the agent so the the     
1:44:40     
brains of the agent and how it relates the environment so the three papers I'm     
1:44:46     
not going to go through them deeply but I'm going to talk about them kind of in sequence so the first paper is this new     
1:44:51     
preprint this is from Michael Levens group and Leo peel Lopez who's I think driving the     
1:44:59     
work um on anthro this a this particular aspect of anthr robots which is the     
1:45:06     
morphological Behavior behavioral and transcriptomic life cycle of anthr robots so if you're remember that you     
1:45:14     
know the xenobots which is like this it's this uh zenopus embryo that's sort     
1:45:20     
of a robot uh they're incorporating the cells into a robot and they're using     
1:45:26     
that as an autonomous agent uh this is what they call anthr robots where they're um using cultured     
1:45:34     
adult human Airway epithelial cells and these cells become self motile     
1:45:41     
and acquire neural repair capabilities without exogenous genetic     
1:45:46     
circuits or inorganic scaffolds so there're these uh Bots that     
1:45:51     
are basic based on kind of human type cell that's in culture and they're trying to engineer     
1:45:59     
the cell to sort of engage in this sort of you know motile Behavior the     
1:46:06     
self-repair and so forth so that's that's what they're going that's why they call anthr robot instead of     
1:46:12     
xenobot uh so fascinating aspects of morphogenetic and behavioral plasticity     
1:46:18     
of living material are revealed by novel constructs that self assemble from     
1:46:24     
genetically well type cells anthr robots in this case arise from cultured human     
1:46:30     
Airway adult human Airway epithelial cells developing becoming self motile     
1:46:36     
and acquiring neuro repair capabilities without exogenous genetic circuits or     
1:46:41     
inorganic scaffolds so they basically develop in     
1:46:47     
this Niche where there are these epithelial cells they become self motile     
1:46:53     
and then they become you know they they have the sort of plasticity where they can repair     
1:46:58     
themselves and they're no exogenous genetic circuits or scaffolds     
1:47:04     
needed so progress in bioengineering and regenerative medicine depends on developing predictive understanding of     
1:47:11     
collective cell Behavior novel circumstances so you know if we want to do bio engineering we want to do     
1:47:18     
regenerative medicine we want to guide cells to a Target or want to do bioengineer ing where cells have to be     
1:47:24     
sort of precise in where they go we don't want to sometimes we can have the luxury building scaffolds into things     
1:47:32     
but you know that's sometimes we want to have things incorporated into a scaffold we want to have better greater control     
1:47:39     
and bioengineering applications so we want to develop sort of this autonomous     
1:47:44     
behavior in cells we want to do this from actual living cells instead of kind of engineering a solution that's     
1:47:52     
inorganic um towards that end here we quantitatively characterize a number of     
1:47:58     
life cycle properties of anthr robots including their morphogenesis maturation and demise so they look at the life     
1:48:06     
cycle of these cells they look at the morphogenesis of the cells into this specialized cell type they look at the     
1:48:13     
maturation of the cell type and then the demise or the apotosis of the cell type     
1:48:19     
so you know this is a differentiated cell divide for a certain number of Divisions     
1:48:24     
and then the cells will go tic so there's this life cycle that we have to     
1:48:30     
be aware of we uncover a self-healing capacity and a remarkable reduction of     
1:48:36     
epigenetic age upon morphogenesis transcriptomic analysis revealed that assembling into anthr     
1:48:42     
robots drives a massive remodeling of gene expression relative to their cellular Source including several     
1:48:48     
embryonic patterning genes and a shift towards more evolutionarily ancient gene expression so these uh epithelial cells     
1:48:58     
sort of move around together in in this sort of colony and when cells are in a     
1:49:03     
colony they behave differently than when they're isolated and so we want to understand the you know where they like     
1:49:10     
if they come from a certain set of population of cells and they move to a new location and they integrate with     
1:49:17     
another set of cells how does it affect gene expression how does it affect     
1:49:23     
the further sort of morphology of the cell the maturation of the cell and so     
1:49:29     
forth so there's a lot of stuff that we need to know about these and this is this paper is basically characterizing     
1:49:36     
these anthropods these data reveal new aspects of engineered multicellular     
1:49:41     
configurations which wild type adult human cells self assemble into active living constructs with its own distinct     
1:49:48     
transcripton morphogenesis and life history so they talk about anthr robots     
1:49:54     
which are the first fully cellular human derived non-ionic biobots um they're self     
1:50:02     
constructing uh the they considered organoids uh actually I'm     
1:50:11     
Sor so the the origin of these cells are at     
1:50:16     
least what they're characterizing are these Airway organoids and these organoids are three-dimensional     
1:50:21     
structures of course that grow in vitro that mimic the architecture and function of the human Airway so there's these     
1:50:28     
human Airway epithelial cells that are grown in an organoid these organoids can     
1:50:33     
derive from multiple sources including stem cells normal human bronchial epithelial cells and human     
1:50:40     
donors uh Airway organoids are commonly characterized by their ability to     
1:50:46     
replicate the cellular diversity of the airway epithelium including ciliated     
1:50:51     
Cells Go blood cells and Bas basil cells so a number of cell types they exhibit     
1:50:57     
key functional properties of the airway such as mucus production C beating in response to internal external     
1:51:04     
stimula uh and so what they want here are the solated synthetic biological     
1:51:10     
constructs uh they want to understand those so they want to know how those cells integrate into that     
1:51:16     
structure the main difference between anthr robots and Airway organoid is that while the primary goal of the organoids     
1:51:23     
is to recapitulate the native tissue architecture and Physiology anthr robots and other biobots demonstrate New Living     
1:51:30     
forms and function that is not explored by Evolution but is useful for engineering     
1:51:35     
purposes they are used not only to make useful synthetic living machines but also to explore motility enabled     
1:51:41     
behavior that reveals plasticity and emerging features not apparent in organoid     
1:51:47     
assay so this is a little bit about the anthr     
1:51:53     
robots um this figure one the the caption is anthr robotss of different modes of     
1:51:59     
self-construction it may account for emergent morphotypes so they kind of show the different fates of the anthropo     
1:52:06     
progenitor cell which can be dormant what they call a merger expander     
1:52:12     
and then what they call a monoclonal expander so uh they kind of show in this     
1:52:19     
uh this is the PCA where they show these three different um these three different sort of fates     
1:52:26     
of the progenitor cell so the progenitor cell is here and then using a PCA they     
1:52:31     
can see that they have these three groups these three axes of variation um or the I'm sorry these     
1:52:39     
these three sort of groups uh on pc1 versus     
1:52:45     
PC2 and then here they have these different uh you know they have     
1:52:50     
basically the bot area the number of events detected and the variation and change of overall body     
1:52:57     
area so these Bots are collectives of cells that are in these different groups     
1:53:02     
and they're showing how that this bot grows over time um and so then they kind of talk     
1:53:11     
about a little bit about this they show some of the staining of these Bots and     
1:53:16     
how they sort of form uh then they say anthr robots exhibit a highly altered ancient     
1:53:23     
transcriptome including embryonic patterning genes and they show some     
1:53:29     
characterization here where they show that early stage anthr robots display onset markers of embryonic     
1:53:36     
development that the progenitor cells are located in this part of this pc1     
1:53:42     
versus PC2 space and then the day Zero Bots are down here so clearly the dzero     
1:53:48     
Bots are different than the progenitor cells which are shown in in this red here these red dots and then the day     
1:53:54     
Zero Bots are these assembl loids that kind of form from the from the cells and     
1:54:00     
so this is the morphology of the bot anthr robots display different     
1:54:06     
behaviors during the diversion process which is this sort of aversion which     
1:54:11     
brings the Cilia into an outward facing orientation so this is like kind of analogous to an embryonic movement like     
1:54:19     
you would see um like in in vagination and evagination so it's where it's     
1:54:24     
folding in and out ersion is where the Cilia become outward     
1:54:30     
facing so they kind of characterize this process here anthrotronix     
1:54:52     
maturity in embryonic development that is uh or you see uh anthr robots as the     
1:55:00     
age displaying markers of maturing embryonic development so this is where basically your aoid is mimicking     
1:55:07     
embryonic development in different ways anthr robots undergo a second massive     
1:55:13     
transcriptomic rearrangement during their maturation so the first trans     
1:55:18     
transcriptomic rearrangement is when they sort of form these an robots and the second rearrangement is when as they     
1:55:25     
mature so there are a bunch of key genes that we can look at that involve     
1:55:31     
mism involve ectoderm formation and involve sort of endoderm associated     
1:55:38     
genes so all three layers of the embryo uh are represented     
1:55:50     
here and so then in figure four they characterize late stage anthr robots and how they display markers of maturing     
1:55:57     
embryonic development they show uh key transcripts here and how they change     
1:56:03     
from your day Zero Bots to your day 10 bots so this is a 10day um sequence and     
1:56:09     
of course in a you can see that there's a colored representation of the anthr     
1:56:15     
robots at day Zero and day 10 and you can see that the stain that their differences here there's also this     
1:56:21     
change full uh full detection change in uh day     
1:56:28     
day 10 versus you know up up regulation down regulation in day 10 and then in     
1:56:33     
the PC Space pc1 versus PC2 the day Zero Bots are down here remember the     
1:56:39     
precursors are up here in the space day Zero Bots are here and day 10 Bots are out here so they change their position     
1:56:47     
uh especially on PC2 they sort of revert back to the this uh sort of the level of     
1:56:53     
the precursor cells with pc1 they move further to the     
1:56:59     
right so that's uh and so finally anthr robots display robust behavioral     
1:57:04     
longetivity and reversal of epigenetic age as they age we get this behavioral     
1:57:11     
tivity and we get this sort of these mature anthropods and so they start to uh you     
1:57:20     
know they start to change in terms of their population size uh anthr robots     
1:57:26     
approaching weeks 4 to eight in their life cycle experience visible structural degradation however the frequency of     
1:57:33     
motile Behavior among intact Bots at any given time remains steady indicating     
1:57:38     
Bots do not cease their movement as they age but only stop when they die we found no evidence of an increasing elderly     
1:57:45     
fully immobile phase of life so as the anthropods age cells die off they become     
1:57:50     
smaller they still move around though and they experience um just sort of a mature     
1:57:59     
phenotype so that's really interesting that's this anthropod approach to looking at     
1:58:04     
morphology and you know morphologies from cell collectives this second paper is um on     
1:58:12     
embodied computational Evolution a model for investigating Randomness and the evolution of morphological complexity so     
1:58:20     
this is by a pair of computer scientists and and there's some robotics research in here as     
1:58:26     
well um so this is kind of proposing this approach called embodied computational     
1:58:33     
Evolution so I'll read the abstract and and you know we can maybe go to the next     
1:58:38     
paper in the interests of time this was in the journal integrative organismal biology so this is uh you know kind of     
1:58:47     
focusing on biology instead of the but it's also bringing computer science into     
1:58:52     
the next here so the abstract reads for an integrated understanding of how     
1:58:57     
evolutionary Dynamics operate in parallel on multiple levels computational models can enable     
1:59:04     
investigations that would be otherwise infeasible or impossible we present one modeling     
1:59:09     
framework embodied computational Evolution or ECE and employed to     
1:59:15     
investigate how two types of Randomness genetic and developmental Drive the evolution of morphological complex so     
1:59:22     
you have this genetic component and a developmental component so this is kind of like what we were dealing with in the     
1:59:28     
first paper we have gene expression we have genetic Randomness we have developmental Randomness which they'll     
1:59:35     
describe in the paper but basically those two things together sort of the genetic aspect and then of course in the     
1:59:43     
uh assembl loids we have this developmental Randomness that occurred from these cells assembling into these     
1:59:49     
collectives uh with these two types of Randomness implemented as germline mutation and     
1:59:56     
transcription error in this case they're defining uh germine mutation and transcription errors these two sort     
2:00:02     
sources of Randomness with rates varied in 11 by 11 factorial experimental     
2:00:08     
design we tested two related hypotheses so hypothesis one was Randomness in the     
2:00:14     
gene expression process Alters the direct impact of selection on     
2:00:20     
populations and then hypoth is 2 is selection on locomotive performance     
2:00:25     
targets morphological complexity so this is where you're looking at Gene the gene     
2:00:31     
transcription process uh sort of altering selection     
2:00:38     
and then selection of locomotor performance targets morphological complexity so I guess they have these     
2:00:43     
agents that they're doing this with uh the experiment consists of 121 conditions in each condition nine     
2:00:50     
starting phenotypic population develop from differently randomly different randomly generated genomic     
2:00:57     
populations of 60 individuals each of the resulting 1,89 phenotypic     
2:01:03     
populations evolved over 100 generations with the autonomous self-propelled     
2:01:08     
individuals under directional selection for enhanced local Motor Performance as encoded by their genome     
2:01:15     
individuals at heritable morphological traits including the numbers of segments     
2:01:20     
sensors neurons and connections between sensors and motorized joints they that     
2:01:26     
they activated an individual's morphological complexity was measured by three different metrics derived from     
2:01:32     
accounts of the body parts in support of hypothesis one variations and the rate     
2:01:38     
of Randomness in the gene transcription process varied the Dynamics of selection     
2:01:44     
in support of hypothesis to the morphological complexity of populations evolved adaptively     
2:01:54     
so this is the ECE approach here where they show this process we have the     
2:02:00     
embodied process which is where we have it's kind of later process we'll start     
2:02:05     
with the genomic process where we have this deterministic aspect of selection     
2:02:11     
we have the parents we have mutation which is genetic error and we have     
2:02:17     
reproduction then we have development which is this mapping error mapping the genes to phenotype and then you have     
2:02:23     
Behavior which is part of this embodied process in Orange and then you get back     
2:02:29     
to this deterministic aspect of selection so EC is an agent based     
2:02:35     
modeling framework that incorporates the entire life cycle of each individual in a population of those individuals so you     
2:02:42     
have this population of agents that you're selecting on you're mutating their genome you're mapping the genotype     
2:02:49     
to phenotype or to behavior and there's a mapping eror error and development there's a genetic error and the mutation     
2:02:56     
process that then leads to this some variation in the population     
2:03:03     
that you can select upon uh so embodied processes include the development of the     
2:03:09     
individual and Its Behavior in an environment behavioral differences among the individuals in a population are used     
2:03:16     
deterministically to select parents in the population of reproduction genomic processes May include the mutation of     
2:03:22     
the genome that is used in reproduction the genome is expressed in the developmental process random errors can     
2:03:29     
principle be introduced at any place in this life cycle so we're kind of we have this     
2:03:37     
approach to embodiment in this paper we commonly call these individuals biorobots because     
2:03:44     
they are embodied models built to test biological hypotheses in the manner of web's biorobotic Paradigm this is web     
2:03:52     
01 and so that's basically what we're doing we're doing a very similar thing what we did with anthr robots on the     
2:03:58     
first paper um basically their agents uh have     
2:04:04     
genomes of genetic interactions development fixed and variable rules     
2:04:10     
physically embodied morphology with sensory motor circuits that drive self- propulsive body rate configurations and     
2:04:17     
behavior that is autonomously generated by the organism interacting with its     
2:04:22     
physical environment this third paper then is     
2:04:27     
evolutionary robotics as a modeling tool in evolutionary biology and again we have this robotics approach uh but this     
2:04:35     
time it's sort of as applied to evolutionary biology not biological     
2:04:40     
constructs or agents that are supposed to be biological constructs so this is     
2:04:47     
um yeah this is in from Frontiers in robotics and AI uh I'll just go through     
2:04:53     
the abstract and we'll finish up for today so the use of evolutionary robotic     
2:05:00     
systems to model aspects of evolutionary biology is well established this is sort     
2:05:06     
of a lot of this work on morphological computation comes from evolutionary robotics not organismal biology and as     
2:05:15     
such we can you know more easily quantify the phenotype of course but     
2:05:21     
their drawbacks to this as well such as you know how do we actually apply it to biological systems and this sort of uh     
2:05:28     
vertical organization that we see in biology so you know we've done this a     
2:05:34     
lot of things with looking at evolutionary biology using evolutionary robotic systems yet few Studies have     
2:05:41     
asked the question what kind of model is an evolutionary robotic system and so     
2:05:46     
this paper seeks to address that question in several ways first it is is addressed by applying a structured model     
2:05:53     
scripture developed for physical robot models and animal sensory motor     
2:05:59     
systems then by outlining the strengths and limitations of evolutionary robotics for modeling evolutionary     
2:06:05     
biology then finally by considering the deepest questions in evolution and which of them might feasibly be modeled by     
2:06:12     
evolutionary robotics so we're looking at structured     
2:06:18     
models which describes sort of physical robotic models of animal sensory motor     
2:06:25     
systems so we're interested in looking at animal sensory motor systems how they     
2:06:30     
perform we can do things with the robots that we couldn't do with animals we can look at their structure we can look at     
2:06:36     
their function we can also evolve them in a computer and see what you know how     
2:06:42     
that process would proceed then we outline the strengths and limitations of evolutionary robotics for modeling     
2:06:48     
evolutionary biology which we talked about for and then we consider the deepest questions in evolution which I     
2:06:56     
guess are you know how do these agents evolve what what are their common     
2:07:01     
ancestry points of common ancestry Etc what is their philogyny also you could     
2:07:07     
answer questions in evoo for the evolutionary development this paper concludes that     
2:07:14     
although evolutionary robotics faces serious limitations and exploring deeper questions in evolutionary biology is     
2:07:21     
when might expect because it's hard to to sort of get a handle on very deep philogyny and and some of the questions     
2:07:28     
related to that and other words we can model extent organisms and we can     
2:07:33     
understand that because we have we can build good representations of that but it's hard to build good representations     
2:07:40     
of things that we don't really have good extent models of um you know it's it's kind of     
2:07:47     
speculative at that point but it's it's it's you know something that we can use     
2:07:52     
as a tool it's particularly the bottomup approach to modeling populations of     
2:07:58     
evolving phenotypes and their embodied interactions so you know we want to     
2:08:04     
understand not just single uh sort of idealized agents in     
2:08:10     
their design but we want to understand this at a population level we want to know the kind of variation that might be     
2:08:16     
created in sensor motor systems or the variation that might be inherent     
2:08:22     
in a population of phenotypes that do things functional we can do this at the bottom     
2:08:29     
up approach we can start with the genotype work our way up to the phenotype and have populations that ex     
2:08:35     
exhibit mutation exhibit selection exhibit genetic drift exhibit uh     
2:08:42     
functional variation structural variation and the like we can have phenotypes that we can measure and we     
2:08:49     
can have phenotypes that evolve uh and this all involves a number of     
2:08:55     
embodied interactions and so you know if we want to test hypotheses about     
2:09:01     
embodiment we have to kind of give ourselves you know not just agents that     
2:09:07     
are idealized but agents that are sort of you know that have variation and we     
2:09:14     
want to understand how these phenotypes evolve because part of I think     
2:09:20     
embodiment is is knowing how a phenotype got there if embodiment if the     
2:09:26     
embodiment hypothesis is true it would it would suggest that function and structure kind of Co evolve     
2:09:34     
that you can't really have refined function without refined structure and vice versa you know the brain isn't just     
2:09:41     
in a vat and it doesn't like optimize itself and fit into any old phenotype the phenotype coevolves with the brain     
2:09:49     
with the controller and so you you'll see that but also you know there's a     
2:09:54     
population of different possibilities that could lead to some evolutionary     
2:10:01     
trajectory so that's that's something we have to keep in mind and then the developmental trajectory how do these     
2:10:07     
things kind of get coordinated in development how do they come online and then how does that affect the evolution     
2:10:12     
of these systems the phenotype and the genotype and the controller the     
2:10:19     
behavioral controller and how do those all fit together and how do they become     
2:10:24     
sort of optimized or what some people call a good fit and so that's where you     
2:10:32     
know we that's where we can use these kind of evolutionary robotics models that's where the power lies in     
2:10:38     
simulation and some of the analogies up raised from this     
2:10:45     
world okay so that's all for that set of papers uh we have comments or questions     
2:10:52     
on that well yeah I mean um you know I love this topic     
2:10:58     
yeah uh uh I I just saw     
2:11:04     
um um Dawkins talking about population     
2:11:09     
genetics and you know I felt like one of     
2:11:16     
the one of the problems kind of     
2:11:22     
understanding his nuances is it's like you know that you kind of need to be     
2:11:29     
familiar with the simulations yeah you know like like it seems like it's an     
2:11:36     
amenable you know discussion topic to you know it's an open area you can     
2:11:43     
just walk in and and get all the points but you know I I think um I mean I     
2:11:49     
really like this uh this the second paper um or you know I     
2:11:56     
got thinking about that uh and you know just that's a really interesting way of     
2:12:03     
of seeing I mean bongard papers too of course right I mean you know not not the     
2:12:11     
first one which is which which is whole other you know set of things you know     
2:12:19     
but like his his kind of what he's known for right or you know like he had one of     
2:12:25     
the first papers I think um you know I mean I think his Bard's like first     
2:12:31     
evolutionary robotics paper was 20 plus years ago yeah yeah yeah and um uh uh     
2:12:40     
you know I I didn't hear about it until it started hitting like pn or something yeah yeah and um anyway but but to to     
2:12:49     
your point right that that like these are these are not easy things to     
2:12:55     
just um kind of armchair think about um these These are these are uh it's it's     
2:13:03     
actually really important to see this these     
2:13:09     
um yeah embodied you know multiscale simulations for     
2:13:17     
for what insights they they give for you know again like um I mean I'm just it's     
2:13:27     
Fallen quick quickly fell down a rabbit hole of following up you know some     
2:13:32     
references and seeing that you know these are actually early Josh bongard papers     
2:13:38     
yeah bongard and somebody else Randle beard okayy beard yeah yeah you know     
2:13:45     
like as another another person yeah yeah and anyway so these are these are um     
2:13:52     
these are really interesting uh you know it's kind     
2:14:00     
of well but of course the anthopants     
2:14:07     
is another whole yeah another because like like     
2:14:16     
they there you see the difference between the robotics that we have right     
2:14:21     
which is like our crude way of making things our brittle way of making     
2:14:28     
things and and dealing with agential matter right right right because you     
2:14:34     
know I mean really the the you know I I I mean this is like completely colored     
2:14:41     
by seeing you know Michael L and and bongard to some degree but Mich L all     
2:14:48     
over you know all over the Internet um Talk talking about this work but like     
2:14:53     
you know that that nobody knew that this matter would     
2:15:00     
do this yeah you know like like it it it's it's if we release it     
2:15:08     
from the yeah the normal local environmental context you     
2:15:15     
know if we release it from its yeah it's its Collective     
2:15:23     
bonds you know like like will it like you said like undergo a kind of     
2:15:30     
embryonic like uh um     
2:15:36     
reconfiguration right that that that generates a machine that we've we've     
2:15:41     
never seen before um you know and what what what that     
2:15:49     
suggests and like I I don't know how much these papers could get in you know like again like you don't you're not     
2:15:56     
dealing with that with these mechanical robots because of course you know they     
2:16:01     
they they are very limited and totally passive materials right right you know     
2:16:09     
anyway it's it's super super interesting it's um so I'm G to meet in a half an hour     
2:16:17     
with nura Berkeley to talk about a second project that's that's very much     
2:16:24     
um dish you know dish brain and or     
2:16:30     
Beyond right and um but the an you know the     
2:16:37     
anthropo make me make me think about how you know some     
2:16:43     
of Levan's experiments are actually quite accessible right you know like     
2:16:49     
with with know like like this isn't Allen Institute required you know well of     
2:16:57     
course it's funny that he is of course the Allen Institute as well but um uh but this doesn't you know this doesn't     
2:17:04     
require big Capital costs to do these kind of experiments right yeah and     
2:17:10     
and I wonder um I I     
2:17:16     
I'm you know it's like you've got all the problems of of cell culture     
2:17:22     
mamillion cell culture right right with certainly kind of dish brain and Andor     
2:17:28     
you know anything that's going organoid as well as like there's this very     
2:17:34     
daytoday maintenance right so it's just like like if if you get it started and it's     
2:17:41     
working right then then it requires a very constant you know maintenance     
2:17:49     
regime and you know to to even get the things     
2:17:54     
that you're G to want to get right um um you know that that it's is just a     
2:18:01     
good reminder that there are other kind of biology experiments that I think are really interesting that speak you know     
2:18:09     
kind of to the collective um uh     
2:18:16     
um you know what what we like about neurons are not neurons but there's actually networks Nance right right yeah     
2:18:23     
right and and you know and I like that L's shown us that you know you don't     
2:18:32     
even need neurons right you know that there's a this is what this is what all     
2:18:38     
cells are doing right and we just we don't necessarily we aren't just thinking about it in the right way and     
2:18:46     
and you know and are there perhaps other yeah so just food for thought for this     
2:18:53     
discussion with like you know how much time do you guys have for what is     
2:19:00     
ostensibly an extracurricular activity yeah and you know and yeah like whether     
2:19:10     
we should put our kind of eggs in a in a basket that that require such kind of     
2:19:17     
consistent uh daily you know work or if     
2:19:22     
it should be something more more focused but um you know like um shorter period     
2:19:29     
but um but you know kind of of more interesting perhaps more interesting     
2:19:36     
demonstration or something like that anyway as usual L's work just continues     
2:19:43     
to inspire yeah for sure for sure and anyway so     
2:19:51     
this is it for the holidays yeah yeah that's it okay okay and if you'd like to     
2:19:56     
meet during the holidays sometime about any yeah I I I wanted to know if if um     
2:20:04     
if we could you know if it made sense and and perhaps with whose support it     
2:20:13     
would make sense to to do something um either Nur fidora or or     
2:20:22     
um you know I I would still really like to do something for nidor around the um     
2:20:29     
the Insight toolkit okay so this is the this is big National Library of     
2:20:36     
Medicine um you know registration segmentation     
2:20:41     
toolkit and it is it's a massive C++ project well     
2:20:48     
documented well um tested that is actually used by a lot of     
2:20:56     
other tools okay so this is this is kind of a software     
2:21:01     
engineering project and and I I was wondering whether to reach out to um a     
2:21:08     
group that focuses on like the software engineering for medical imaging yeah um     
2:21:14     
as well as like to reach out to somebody from kitware because I've I've definitely got some good kitware     
2:21:19     
contacts k kitware was the research was the kind of software development group     
2:21:24     
that was given the contract to develop this it's it's a public project in the     
2:21:30     
sense it was under National Library medicine but but kitware you know because kitware is already kind of known     
2:21:36     
for its big open- Source scientific libraries like BTK     
2:21:41     
okay and and and of course now we all I mean so many projects so many more     
2:21:50     
projects cake now than say you know automake or any of the other kind of old     
2:21:57     
old tools um cmake is a kitware project okay cmake was developed to build BTK     
2:22:05     
and itk and and to deal with you know very disperate platforms you know     
2:22:13     
so it's like make it so you can build on Windows you can build on Linux um build     
2:22:18     
on Mac and um     
2:22:25     
um yeah so I I I I can you know I would     
2:22:32     
I would suggest like you know interested in using these     
2:22:37     
tools using most recent versions of these tools and then these this is a project that that would be the first     
2:22:44     
goal like like let's let's build ant toolkit with this with these     
2:22:51     
um because like but that's already building right that's that's very simple it it you know it'll be like an easy     
2:22:58     
kind of win and it'll demonstrate something then like here's another toolkit that uses itk and BTK and and um     
2:23:09     
it's it's itk snap and you know it's um it's a you know limited gooey toolkit     
2:23:18     
but you know again it's got some really cool features and it would be a great     
2:23:23     
addition and and you know basically like working up in terms of complexity to 3D     
2:23:30     
slicer and and and kind of say you know it if if the person doesn't     
2:23:38     
hit you know if if you don't manage to get like all of 3D slicer working uh on Fedora like that's not a     
2:23:45     
failure but but but that there could be like um goals that we'd hope to get to     
2:23:52     
and that that would be kind of like the reach goal okay I I don't know I don't know how you you know kind of frame that     
2:24:00     
for for um mentees in terms of like it'd     
2:24:05     
be great you know it'd be great for you to do this I mean do you do you give them like     
2:24:11     
limited goals that you're pretty sure that they can hit or do you say like hey this is the goal but you know we it's     
2:24:20     
okay to it's okay to not reach that we'll just say you know after 10 weeks like these are the reason you know we we     
2:24:27     
learned this about yeah they have to develop a schedule or like a you know so they have     
2:24:33     
to like kind of hit I usually don't get I I usually have projects that are that     
2:24:39     
like sort of goal oriented like I usually have them develop something on     
2:24:45     
their own but then you know I have them do their schedule and say okay you're going to hit these goals     
2:24:51     
and if you don't hit them you have alternate like you can leave some room in the schedule so that you know you hit     
2:24:57     
these goals by these weeks but if you don't then you have these alternate goals and you could actually put it in     
2:25:02     
the description and say we would like to do these things but you know you can     
2:25:08     
also kind of uh you know uh you know SK you can build your schedule so that you     
2:25:14     
only reach the first goal and it really kind of gives them this and and it's up to the person reviewing the applications     
2:25:21     
and to say is this a reasonable way to reach this goal or you know not and you     
2:25:27     
know it's largely up to the person proposing their when they propose they     
2:25:32     
have to propose a solution to the problem and how they're going to achieve those goals in this amount of time so     
2:25:39     
we'd say like this is what we want to accomplish with this tool toolkit you know you're going to build this and get     
2:25:45     
to this point at I guess 12 to 14 weeks if you can't do that then this is     
2:25:51     
another this is a stretch goal this is a goal that we really want to hit and then     
2:25:56     
they they propose well they're going to do this you have to evaluate whether that's a reasonable solution whether     
2:26:03     
they can hit those goals and then it's up to them if they can do it and hopefully they can do it a lot of people     
2:26:09     
can because they're usually pretty motivated but you know that's that's also up to the mentor to say you know we     
2:26:16     
need to sort of find the best path to getting this done in this amount of time     
2:26:22     
it's a really tough skill to master because you know a lot of there are a lot of moving parts and you're they're     
2:26:27     
going to encounter you know blockers and other types of things and so it's really     
2:26:33     
kind of you know we have to kind of I guess give them a good basis for sort of     
2:26:39     
setting up that schedule that's really what we need to do in the applica in in the call for     
2:26:45     
involvement so I'm just I'm just trying to think about that like ways ways to     
2:26:50     
kind of inform that and like you know like maybe you know reaching out to some     
2:26:56     
of the like the 3D slicer community and saying like hey what have what have been the big stumbling blocks for people to     
2:27:03     
do this you know what what why why haven't you taken this on like or their     
2:27:09     
particular Stoppers and and then be able to say more about um     
2:27:17     
yeah yeah okay basically want to leave it somewhat open-ended but not too open-ended and because we don't want     
2:27:24     
them to get go down a blind alley and then not be able to do absolutely absolutely I mean that's that's why you     
2:27:31     
know and it would be like I mean I would definitely want to have you know I mean     
2:27:36     
again like I'm happy to pitch this just to to Kit wear and say you know are you     
2:27:42     
guys interested in kind of sponsoring this like you know um and and but okay     
2:27:50     
I'll see what I can um see what I can learn and I'm happy to talk over the holidays yeah yeah set up a time we do     
2:27:58     
that yeah yeah okay all right well yeah happy Christmas as they say in the UK     
2:28:06     
okay happy holidays to you too yeah yeah yeah all right hope to we'll talk later     
2:28:12     
all right talk later bye Che     
