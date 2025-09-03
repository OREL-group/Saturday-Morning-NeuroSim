## Meeting Recording

[YouTube link](https://youtu.be/9Hq7BvboOR4)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115121369636232162)

## Feature Videos
[Recap of the Augmentation Lab event @ MIT](https://youtu.be/aRXqXoKPzps)

[Markovinity (ActInf for Organoid Intelligence)](https://youtu.be/r2vNNic9x90)

## NOTES
Morgan -- metarc.ai (relaunch). Natural scenes dataset -- offline, real-time versions (RT-fMRI).

* Mind's Eye I and II. Run by former stability.ai employees, now sophont.ai.

* fmri.fm -- (real-time path fMRI). Neurofeedback.

* Q-EEG --> focuses on frequency band changes.

* change brain activity with learning paradigm.

Foundation = pre-trained model --> partial pipeline, real-time result.

* oncology datasets, post-mortem analysis of brain tissue.

* reasoning model --> medical purpose. Discord for project.


EEG challenge -- NeurIPS. Large psychiatric dataset.

* transfer learning --> Mind's Eye 2 --> EEG.

* UK Biobank access.


Revisit the SciOps arXiv paper.

* NIH --> ABCD (containerization in processing). Connection = training radiologists in Africa (Neurodesk).

* self-supervised approaches via stability.ai.

* BigBrain -- model training work, import to follow.

* multi-user cloud Kubernetes (orchestration tool).


Ops Engineer I2C2.org --> neurodesk.neutechx.org

ActInf 2025 meeting presentation: invite David Kennedy or Yarrick?

* BioViz Hackathon. MindInVitro. UIUC NeuroTechX group (https://uiucneurotech.wixsite.com/website).


Brett Kagan -- overview of two approaches to synthetic intelligence.

* Organoid Intelligence vs. Bioengineered Intelligence. Guide process to desired end targets.

* Recreate tissue targets of normal brains.

Adeel Razi -- getting classification from organoids.

* LLM complexity ~ organoid intelligence (lack of interpretability).

* ActInf, approaching the training, control, goal-directedness, and behavior.

* ActInf ~ control theory.


NeuroTech @ Berkeley.

Rest vs. training dynamics. Analyze training programs. Can you be a biological computing company?

* surprisal as feedback signal --> how do you break Pong down into stimulation?

* Low-D output vs. higher-D output -- what reveals false positives in terms of Hebbian learning?

* post-stimulation -- what kind of changhes are you expecting?

* "Your Brain on GPT" paper. 


Data x Direction e-mail. Philosopher-Builder concept (COSMOS institute -- Oxford, traditional vs. AugLab definitions -- MIT, non-traditional).

* Hiroshi Ishii -- augmentation, amputation.

* human-machine symbiosis. Cyborg Psych/Bodyfull/Bodyless.


Natalya Kosmyna (Embodiment) and Pat Pataranutaporn (AI vs. IA).

* Addy Cha (ekkolapto) --> moderated session with Wolfram.

* Karen Hao-tyoe of work. Designing a melting  -- what should people do ancd what should they know?

* "Theory of Everything" -- pinging around inside the Black Box.


ekkolapto --> Hormesis, interdisciplinary research talk -- JoPro.

* R and D for the future, building with a philosopher flavor. Responsible AI.

* Wolfram and the brain. 

* Virtual Tissue Groups. 

## TRANSCRIPT       
0:07    
Oh, hello. Good morning. How are you?    
0:12    
Good. It's a It's a very dark day. Okay.    
0:20    
Yeah, it's must be must be very gray and cloudy    
0:25    
out. got a kind got a few bits of news.    
0:30    
All right. All right.    
0:35    
Uh I don't know if Morgan had anything he wanted to update us on now or    
0:41    
Well, sure. Um just because uh well, yeah, this is uh this is an interesting    
0:48    
initiative. Um so Medarch    
0:54    
um I guess Medarch.ai if you want to find the the website uh    
1:00    
is relaunching. So this was a an open science effort to    
1:09    
um have a    
1:16    
not sure. Well, yeah, just an open science effort towards uh    
1:24    
which which focused on both real time and um and    
1:34    
and a normal don't know what the opposite is to to actually call it um but using the    
1:44    
natural scenes data set this is an fMRI data set of a large collection of images    
1:50    
shown to subject and scanner um and then the the the real time    
1:56    
version of it um as well as an offline I guess is would be the way it's    
2:03    
Um and the um the output of last round was um    
2:12    
popularized by its title Mind's Eye and I think Mind's Eye 2. Um    
2:21    
um so they have relaunched this was and if you remember this Bradley this was    
2:29    
employees I mean technically these were employees of stability AI.    
2:35    
Okay. Right. Yes. So so I I think part of part    
2:40    
of the relaunch is that um they left stability AI    
2:46    
Yeah. uh together with perhaps a lot of other people. Yeah.    
2:52    
Um or or stability AI pivoted    
2:59    
depending on who you ask, right? Um uh but they have a new company called Soft.    
3:09    
um s o p h o n t a i of course because if you want to get    
3:16    
funding these days you've got to use those two letters. Um and uh    
3:24    
there's three three initiatives so far and then a fourth one coming. So they    
3:30    
are relaunching um they're not calling it they're they're yeah perhaps for legal reasons    
3:38    
they're not using that name um but they're calling it uh um    
3:46    
foundation FM or something you know like no fmri FM that's sorry of course FMA    
3:52    
meaning the foundation and um uh and    
4:00    
real time or like like yeah it's the the the second project is real time FM    
4:10    
um and then the third is path FM which is pathology    
4:16    
so it's it's you know again there's there's some reason there's there is a    
4:23    
connection to this and and kind of psychiatric nerve imaging    
4:28    
Um, I I know several groups that have wanted to use    
4:35    
neuro feedback in a    
4:40    
well in the scanner basically, right? and and which gives you an interesting    
4:48    
way um to kind of confirm that your    
4:53    
protocol is actually making a brain change, you know, right? that that is is um    
5:03    
different than what has traditionally been done using um um you know    
5:10    
essentially what they call QEG which is um a kind of strange derivative of EG    
5:17    
but focuses on focuses on certain frequency bands uh changes in EG    
5:26    
and hasn't really been shown to be um    
5:32    
has a lot of controversy around it in terms of its reliability and its effectiveness and changing um it being    
5:39    
able to make affect change long term, right? So, so doing this in the scanner    
5:46    
is is a is one way of trying to see like    
5:51    
can you with a learning paradigm    
5:57    
change your brain activity, right? Um at least that that that would be the    
6:03    
the reason for engaging in this, right? whether whether that brain change is also    
6:09    
um you know effective in some sort of    
6:16    
um symptom management or you know etc is is a second question right so it's just    
6:23    
like make making that change and then having that change be uh uh on whatever    
6:30    
you know say depression metrics or other things like that is the second second    
6:37    
Um and then what they're doing with pathology isn't so interesting, you    
6:42    
know. So I I I attended all three meetings. um in terms of the presentations that    
6:49    
they had that they covered uh you know again there's there's there's a lot of    
6:55    
overlap with previous software efforts around real time fMRI that that were    
7:01    
interesting to me terms of of what approach they were going to take. I've been doing stuff in the scanner since    
7:08    
the late 90s which just means that I'm old. Um but uh uh because we were doing    
7:16    
EEG in the magnet. So this the issues that you have in terms of being able to    
7:23    
you know how to get real time data from the scanner, how to synchronize with the    
7:29    
timing of the scanner, how to deal with artifacts from the scanner. Artifacts    
7:35    
being a more EEG related thing than than real time frame.    
7:40    
But um some of those some of those are interesting and then you know the    
7:46    
application of foundation models which just means a pre-trained model.    
7:52    
Yeah. Um application of a pre-trained model is    
7:57    
is interesting as well because again a lot of the problems that you have um    
8:05    
relate to how to do you know analysis that is traditionally done offline    
8:12    
in in in in some expedited way meaning    
8:18    
that they usually change they don't do full pipeline they do um partial    
8:23    
pipeline to get a real-time result. Right? So these were these were all issues that    
8:29    
that um you know I was very familiar with was interested to see what what    
8:34    
approach they would take and also relate back to some some    
8:40    
um some work that I'm hoping to do back in my hometown which is is Virginia    
8:46    
which was one of the sites that actually pioneered real time uh fMRI especially    
8:53    
as it relates to computational psychiatry. So these are people doing doing uh uh gambling tasks and other    
9:02    
things like in the scanner or or even hypers scanning um but again in the    
9:08    
scanner um between two scanners one in Blackburg one in Renault    
9:15    
and like even back in 2014 they were doing GPU    
9:21    
um G using GPUs to do the real time uh processing to to    
9:29    
give you that that those analysis those typically offline analysis but so that    
9:35    
that was interesting the the the path uh FM project you know was is currently    
9:42    
being used on what I would call more kind of um oncology data sets in the    
9:48    
sense um but but I'm I'm again really interested because in psy psychiatry.    
9:55    
There's also there's also a sub field that focuses on post-mortem analysis of    
10:02    
of uh brain tissue and looking Yeah. So I'm interested to    
10:10    
see how much these what they're calling pathology models, you know, can can be    
10:19    
used again, how they these pre-trained models can be used to help us    
10:24    
distinguish or identify um tissue differences from post-mortem    
10:30    
brains. And you know the um    
10:35    
the the the Liber Institute for Brain Research is a um is a center at the    
10:44    
Hopkins that has the largest collection of postmortem schizophrenia brains. So I    
10:50    
think they've got like 4,000 or something like that. I mean a big big collection and the you    
10:57    
know again really interested to see you know um    
11:04    
how tissue models get trained and how they can potentially be used to to um    
11:10    
yeah a augment this kind of brain analysis. So there there's there's a fourth    
11:17    
project that they're starting that's called um well that that is that is definitely    
11:24    
medical reasoning. Uh I'm not sure what the the code name for it is. Um but uh    
11:32    
um yeah, I think I think that reflects that cell phone does have some sort of    
11:39    
business plan, you know. Um so I'm not sure exactly    
11:45    
what what that is, but I I assume it's like let's take some sort of, you know,    
11:51    
reasoning large reasoning model and and give it, you know, a medical    
11:57    
Yeah. purpose. But uh so I I I like this    
12:04    
project, you know, like well    
12:10    
two things. One, this project is a is a real open science effort, right? Like    
12:16    
this was this was one of those projects where they they they said like, "Hey, we're going to have a Discord, you know,    
12:22    
if you want to get involved, like join the Discord, come to the meetings, you    
12:28    
know, pick a task and and dive in and and you know, like this is open and it    
12:36    
was very much a a open project. So I think it was very um it was very    
12:44    
innovative that way or um it really did break break some molds, right?    
12:50    
Yeah. And two uh um because I'm I kind of want    
12:55    
to relate this to the EEG challenge that is is part of Nurabs.    
13:02    
Um, which which again, by the way, if I if I haven't talked about this before,    
13:07    
the the EEG challenge that nerves is is doing um    
13:13    
is using a large psychiatric data set. So, so I'm I'm, you know, this is my    
13:20    
favorite Child Mind Institute Healthy Brain Network data set. Uh, I've talked about it for a long time because I think    
13:26    
it's awesome and I'm glad that somebody Well, it's not just somebody. It's the guys. This is the PI who runs um Neuroch    
13:35    
X's um Moab project, the mother of all BCFI benchmarks is actually leading this    
13:41    
effort. So, it's like, yeah, we used this for a hackathon a couple years ago. It's great to see it's being used for    
13:47    
nerves. It's great to see that they got so much interest. they got um 450 groups    
13:55    
of that have already signed up that had overwhelmed their competition um infrastructure.    
14:01    
So they had to push back this the start to um Monday. Um    
14:09    
but the there is a part of metarch that    
14:14    
is using that um that has some people that I know that tried to do transfer    
14:22    
learning from mind's eye to to EEG you know um now this comes back    
14:32    
to some issues that I have but in terms of just like it's it's all fine and    
14:38    
dandy that we agree um sort of agree what foundation models    
14:44    
are. Um but but in general like the only the only data set that we have that's    
14:51    
kind of foundation model size is like taking all of the internet's text right    
15:00    
the question whether any there's any fMRI data set that comes close to that    
15:06    
um is is a big one and so this is also interesting and important in terms of    
15:13    
just um like what data sets are they they training to use um and and then how    
15:21    
are they testing this and you know so this is also pretty    
15:28    
so again I'm I'm interested in following this because um they have resources you    
15:34    
know like it's an open science group but it's an open science group that has resources that I find to be um beyond    
15:41    
most most groups and one of those is that they got access to the UK bio bank.    
15:48    
Now, getting access to the UK bio bank, you got to understand that there's been some serious controversy about this.    
15:56    
UK biioank um pulled everyone's access. Um I forget exactly when um    
16:06    
I don't know if it was earlier this year, even even before that. But basically UK bio bank said like hey    
16:13    
nobody can download the data anymore. You got to use our cloud to to process the data. But everybody was actually    
16:20    
really annoyed and and were saying that this actually restricted their ability to do even process the data the way they    
16:27    
wanted to. So again there's some really interesting things come that are    
16:33    
involved in this. Um, the next data set that they want to add is one that I've    
16:38    
not been able to get access to, which is which is the NIMH's ABCD    
16:46    
and and uh so on Monday, excuse me, the    
16:51    
reprom uh um training program begins    
16:59    
and and I would really like to be involved. It's it's interesting both to    
17:04    
to to see again the the additional containerization of    
17:11    
of all kind of um processing in terms of how that's done. uh we've talked about    
17:18    
some of these things are I think I think Stefan Bolman is one of the the best    
17:23    
people doing this kind of work and trying to kind of collect technologies    
17:30    
from you know scaled web services and things like that to apply to this    
17:38    
again it's really really important you know when you want to again like try    
17:44    
to do you know start to deal with data sets that like    
17:50    
there's no, you know, you you don't even think about trying to download this to your laptop kind of thing. Um, so    
17:58    
anyway, I just think that there's there's a whole lot of things interesting about this. um and you know    
18:05    
kind of want to think about or you know I'm following these projects because I    
18:11    
think there's a lot that we can learn in terms of of how to do science these days    
18:16    
in terms of the data set sizes that we need to to make real psychiatric    
18:24    
translational work possible. Um uh but    
18:29    
it's tied up with data access issues. It's tied up with compute issues, compute access issues,    
18:37    
and and how to how to really leverage all the machine learning that's been going on in terms of their their path    
18:44    
work is is is built on Dino 3.    
18:50    
So um and Mind's Eye is also taking you know again like like their work from    
18:57    
stability AI was not um they they've learned a lot at stability    
19:05    
in terms about scaling and in terms about selfsupervised approaches you know    
19:11    
so um uh yeah anyway I I don't I don't want to    
19:17    
go on too long about it But I just I thought that it's really interesting to follow. Um and you know would like to    
19:26    
make regular updates about it in terms of just tracking this progress    
19:32    
as as part of you know I'm really trying to connect this to what I'm going to what I've been calling computational    
19:39    
psychiatry. Um and uh um yeah and we'll be talking    
19:46    
more about trying to get access to the Liber Institutees data sets and see like    
19:53    
it's not Sant's interest but like like doing    
19:58    
that kind of post-mortem tissue analysis with these p pathology models I think is    
20:05    
is another interesting thing to talk about and it kind of relates to some work that um uh in a project called Big    
20:14    
Brain. So um again Big Big Brain being uh kind of a successor to the European    
20:22    
Brain Project.    
20:29    
Well, yeah, that's great stuff. Um yeah, I'm interested in following up on a    
20:35    
number of these things. Yeah, we never really did follow up on the containerization stuff. I mean, I    
20:41    
guess I don't know what more there is to say or what the next steps are there. I mean, we um    
20:50    
you have thoughts on that? Yeah, I mean, for sure. So, so,    
20:56    
so we um part of a group called connection that's doing um that's    
21:02    
training radiologists and neuro researchers in Africa. So it's    
21:08    
part of this kind of uh    
21:13    
it's it's also dealing with the you know compute and and bandwidth issues that in    
21:23    
that some countries have and so I was super glad to see that they    
21:30    
were using Narodesk both both from a training standpoint    
21:35    
from the you know the you Oxford does a a course on their software, right? They    
21:44    
insist that, you know, you show up to workstations that are like have all the    
21:51    
software pre-installed, right? Because like like you're going to do a fiveday course and they can't they can't have    
21:58    
everybody just bring their own laptops and then see if we can get it installed sort of thing. That that takes that    
22:04    
that'll take your five days, right? So, Neuroidesk is great in that regard, but    
22:10    
but then it's it's running it as a multi-user cloud Kubernetes    
22:19    
um uh project is is really where you can see Neuroidesk as a kind of you know    
22:28    
container or orchestration tool that that yeah is is when when coupled    
22:37    
with the right backend infrastructure um is is yeah just just what just what    
22:45    
your system admin would want you know um so so I'm kind of I'm kind    
22:52    
of working with an old friend of mine who's who's you know been a back-end data engineer for you know kind of a um    
23:01    
an ops engineer for big companies for a long    
23:07    
just in terms of of playing with that and and seeing you know how to get that    
23:12    
running on cloud infrastructure and and how to get that running in inexpensively    
23:18    
too. So um I2C2 uh I2C2.org or is is an org setup to run    
23:30    
um to run these kinds of things for nonprofits for instance. So it's like    
23:36    
I'm I'm trying to set up a kind of neuroesk.nuratechx.org.    
23:41    
Okay. So that that that I can you know because it's it's it's not only a problem for    
23:49    
teaching a course, it's a problem just in general, right? Yeah. Um, but I I was thinking about    
23:55    
this like like since I I got in touch with Stefan to ask him like because Google Cloud made a change that kind of    
24:02    
killed Nuresk on GCP. Oh, okay. and and you know so that that's fine in    
24:11    
the sense that like actually a lot of the IBM cloud Oracle clouds kind of    
24:17    
offer bigger bangs for your buck especially and those are actually    
24:22    
services that are more likely to give you cloud credits if you are a nonprofit or you you make a kind of science    
24:28    
request for them. Um um so so it's not so bad but um um I was    
24:38    
reaching out to him and then was thinking like hey have we started planning for the active    
24:44    
in you know the applied active inference meeting. Yeah. and and you know was there    
24:50    
something that you wanted to do for that in terms of you know maybe we could    
24:55    
reach out to Yaric again um if we if we get in touch with Jar earlier um because    
25:02    
again like his it's not just his work at Neurodebian it's his work at the center    
25:09    
for reproducible neuroscience and um I mean it's not I shouldn't say    
25:14    
it's just or you know reaching out to David Kennedy because I think he's the uh    
25:20    
he's the person behind that and and um yeah anyway it it's it's definitely a    
25:31    
yeah it's like like in terms of any cloud running things in the cloud these    
25:36    
days like it's an essential it's an essential technology right yeah yeah I don't well you know I'll    
25:44    
talk about the uh active inference Um I guess yeah it's all the questions I    
25:53    
had. I I think this is interesting the stability AI uh genealogy that's forming. So    
26:01    
So these people just ended up in different places and they're or there's a successor organization you said.    
26:08    
Yeah. Yeah. So, so the um the young kid    
26:14    
who who definitely started Medarkc um has had no problem I think raising    
26:24    
with with you know taking this kind like Medarch team and and raising for    
26:30    
softened um what what they call soften and and it's it's it's also you know I I I don't    
26:38    
mean to take this over is kind of a neuroch, you know, but um th this also    
26:44    
relates to a company that um that I visited over deep tech week here in San    
26:51    
Francisco called All Join. And so All Joined is an EEG version of Medartr.    
26:59    
Uh and um so yeah, I I I know that there's there's    
27:06    
some relationship in terms of of these are either all former stability people    
27:13    
or these are kind of like they've got a med art pedigree together or something like that. Um    
27:20    
but again it's um uh these are people who've been seeing    
27:27    
again like what pre-training and you know having the right metrics to see see    
27:36    
scaling behavior that leads them to believe that that certain things are    
27:41    
doable right and and that that's that's the bit that I'm trying to you know like    
27:47    
like again like there are for for as dystopian as as you know    
27:54    
Silicon Valley has become um I I don't want it to get lost that there are some    
27:59    
there are some technical um you know breakthroughs or um    
28:07    
there's some technical work going on that's really important to follow and to to understand right as as it relates to    
28:15    
model training and and things like that. Um    
28:21    
and and I would say that I think the paper    
28:26    
sorry coming coming back to kind of the containerization and things like that like like one of the reasons that I    
28:32    
think I put in touch with Yaric first for the for the um the institute's    
28:40    
conference was his archive paper called SCOPS    
28:46    
not spelled E S Y. No, but spelled S CI, which which I think is    
28:54    
interesting that it could be either. Yes. You know, I didn't until I said it out    
29:01    
loud. Yeah. When I was when I if I just read it, it's fine.    
29:07    
Uh uh but when I said it out loud, I thought that was pretty funny. And I'm sure that Eric knows that.    
29:13    
Yeah. um uh is it's a great or you know like it's    
29:18    
an interesting paper that absolutely relates to topics that we would want to cover.    
29:25    
Yeah. Yeah. Great. Well, that's a great update. So, you've been up to quite a    
29:31    
bit. Um yeah, a lot of things to follow up on. Yeah.    
29:37    
Yeah. That that that was that was good. Um just trying to think if there's any    
29:43    
um there's a we're doing a bio viz hackathon um in in terms of fabrication you know    
29:51    
the microelectctor arrays open eiz platform work yeah like uh    
30:00    
we'll we'll be doing some meetings next week to try and you know students are coming back I met with the UIU neuroch    
30:08    
uh group. Um they've got some they've got some questions about becoming a nonprofit.    
30:15    
Yeah. They they they they are finding it difficult. Um the university takes their    
30:21    
money. I mean, you know, when they get when they receive money, the university takes it and then they find it very    
30:26    
difficult to get back from the university. Right. Right. I I I didn't know whether to put you you    
30:33    
know like if you had any thoughts or guidance for them on that. Oh, it's typical university bureaucracy.    
30:40    
Yeah. Yeah. Yeah. Yeah. So, they they're very interested in in becoming    
30:45    
independent. Yeah. Um and and so that was a nice conversation just as it relates to Yeah.    
30:53    
like uh what what the Nerchek X board needs to consider about like again like    
31:00    
what's what h how to structure the organization to help the students,    
31:06    
right? So it's like if we could be a fiscal sponsor for for you know for    
31:12    
these orgs um in in some sort of responsible you    
31:17    
know not open ourselves up to    
31:23    
liability or anything but you know it's if if that's some way that we can    
31:29    
structure New York that would be useful I think that that would be really    
31:34    
valuable. Um u but but uh yeah want to    
31:39    
talk next week about mine in vitra with the students coming back and where we    
31:45    
are with that um uh and our our approach to you know the the have have you seen    
31:54    
this new paper from Brent Kagan? Um, sorry. Let me    
32:01    
um it's it's it's actually a great overview    
32:09    
of kind of two approaches to um to    
32:18    
what what you might call synthetic intelligence work. Okay. Actually, figure one and two. Yeah.    
32:27    
Yeah. This is two roads diverged pathways for harnessing intelligence in neural cell cultures. That's Brett Kagan    
32:34    
is the sole author and Yeah. Yeah. And he's the he's the chief scientist at um Cortical Labs.    
32:41    
Okay. So this is figure one. This is organoid intelligence and bioengineered    
32:48    
intelligence. Yeah. Yeah. Yeah. So they're making the distinction between like just kind of    
32:53    
normal bioengineered tissue and organoid. Right. Right. So so you know which is is    
33:05    
Yeah. So these these have a these a very different engineering choice. Right.    
33:12    
Right. where where one is is using, you know, these these developmental signals    
33:21    
um to both, you know, um induce the differentiation as well as to    
33:31    
to allow the cells to self assemble, right? I mean it's it's this this um yeah that    
33:39    
that that's the organoid culture which you can I mean again like a lot of the    
33:47    
organoid researchers focus on how to guide that process    
33:55    
to desired end targets. Right. Right. So, so a number of of, you know,    
34:06    
number of great groups that work on this um uh and they they want to kind of    
34:13    
recreate in in this organoid way particular    
34:19    
tissue targets of of you know normal brain. Right. Right.    
34:26    
And then the the bioengineered approach is is very different. And it    
34:33    
scroll down to figure two there. Um in terms of yeah that that uh these    
34:40    
these two pathways, right? So and that that I think is is really gets at like    
34:48    
what we've been trying to do with 3D bioprinting, right? in terms of of    
34:55    
linking um this this yeah perhaps more traditional    
35:04    
bio-engineering approach to structure you know to um yeah tissue engineering.    
35:11    
Yeah. Right. and and I think so it was it was it was nice to see this from from Kagan    
35:22    
in talking about this second path that because you know a lot of people I mean    
35:28    
as you know I I've been really interested in following organoid work um    
35:35    
uh we both we both had to make a choice in terms of can We do do we have the    
35:43    
infrastructure for organite work and do we have the funding for organite work?    
35:49    
Um um but but the main thing being that there's also a very wide or you know big    
35:57    
disconnect between our ability to to generate these organoids and our ability    
36:04    
to simulate what we will get. um or or you know like like the the    
36:12    
complexity that's there you know and and that's one of the    
36:18    
reasons to you know follow these like virtual tissue groups sort of like James Glazier in Indiana um that that second    
36:27    
path that a bioengineered intelligence um not not everybody involved in this    
36:34    
work is is super happy with that particular name. Yeah. But but again, I like that Kagan's made    
36:41    
the distinction, you know, and um because, you know, it does relate more    
36:47    
to the the the approach that we're hoping to do with with kind of like building up with the mind in vitro    
36:54    
because it started as a 2D neuron culture, right? Um, are there simpler ways that we can use,    
37:03    
you know, again, very inexpensive consumer hardware that's been repurposed? Uh, um, simple cell culture    
37:10    
work instead of, you know, kind of like the the reagents and and other things    
37:17    
needed for, um, uh, um, the organoid culture that allow us to do. Yeah. these    
37:27    
these engineered um these engineered cultures and you know so we're these are    
37:35    
more reliable you know kind of like we print this is you know what we want to    
37:40    
call this 4D biorinting right where we can we print in 3D but then we    
37:46    
get some growth but but we don't need to do this massive quality control where we    
37:52    
kind of go through all of our organoid cultures and decides, you know, which small    
37:58    
subset of those are actually like our our tissue targets, right? Um it is it    
38:06    
is it somewhat reminds me of um    
38:12    
of LLM complexity in the sense that like with LLM training, you get this thing    
38:18    
that's not really it's you don't really understand it and it's not fully under your control. Um but then you kind of    
38:27    
you you try all these um uh these all these fine tunings to to you know    
38:37    
sort of guard rail it into the the thing that you're you're testing for you know    
38:43    
right um and yeah so I just I thought this was a nice um a nice overview paper for you    
38:52    
know an alternative approach and and one that is is also appealing to us because    
39:00    
it's less less expensive, right? But I but you know again super important    
39:06    
in ter it's it's not just that it's less expensive. It's um although that does    
39:12    
make it more accessible um but that again we would love this to be a    
39:20    
undergraduate um uh accessible project you know.    
39:26    
Yeah. So I find this figure well 2B and 2C    
39:33    
interesting. So this is uh B is uh interperability    
39:39    
low and high versus site or physiological relevance low and high. So    
39:45    
I guess this is an organoid uh sort of the uh vascularized pattern neuroorgganoid    
39:52    
down at the bottom right which is low interpability and high physiological relevance.    
40:00    
And then you have something like single cell electrophysiology just high interperability low    
40:06    
physiological relevance. Then you have something like a 3D specified neural circuit high interperability    
40:14    
uh midphysiological relevance and then all these other types in between. It's    
40:20    
kind of like they're kind of putting this the organoid kind of down at this    
40:25    
end where it's more physiological relevant or physiologically relevant    
40:30    
than the 3D neural circuits or the the uh single cell recordings.    
40:37    
So I mean I guess that's because it's in some sort of context. It's vascularized. It's sort of in a tissue.    
40:45    
Yeah. Yeah. I mean, you know, like like again like um this this is this is very    
40:51    
much a an idealized figure, right? Yeah, I know. in the sense that like    
40:58    
surfacewide recordings of vascularized pattern neural organoids like is who's    
41:03    
doing that like like you know so you know I I try    
41:11    
to attend any talk that that covers the    
41:17    
vascularization of an organoid you know I mean and and by that meaning    
41:22    
you know like like I can't limit myself to to just the people working on neural    
41:29    
right neural tissue right um and you know and that's one of the things right so the    
41:36    
the other thing the other thing that's idealized about this picture is that all    
41:42    
this kind of micro patterning or 3D specified circuits and things like    
41:48    
that yeah like like you know u all the 3D bio fridging people are    
41:55    
working on like muscle, bones, skin, you know, ligaments, right? Like like like    
42:03    
you know, there's so few groups that are actually working on neural tissue. Um uh    
42:08    
but I do I do love this paper as well because it's like like when I was a    
42:14    
student um you know it's like kind of the best we you know I was a simple    
42:20    
systems neurobio guy so it was like get an invertebrate you know remove the nervous system and do the kind of single    
42:28    
cell electrophysiology right as as being that that was kind of    
42:33    
like like what you could hope to do as as a student. Um, and yeah, so in in    
42:42    
these two these two arms are kind of like the directions that I would love to    
42:47    
see us be able to to get to. Um, and you    
42:53    
know, and again, like the the MEA that like like how you do the recordings is    
42:59    
is definitely a part of this this technology there. Um, but yeah, I I I    
43:06    
love all these graphs. I think Yeah. Yeah. I mean, the the uh this uh figure 2B    
43:13    
kind of reminds me of the argument people make for embodiment, right? Embodiment is more relevant to    
43:22    
you physiology, but like the real world and then it's it's    
43:27    
probably higher interpretability, although I don't know how that graph would look like. Um and then figure 2C    
43:34    
this is technical challenge to assemble. So obviously the larger scale things are    
43:40    
higher and then difficult to elicit and control advanced neural function. So    
43:46    
it's easier actually to elicit and control function through 3D specified    
43:52    
neural circuits than something like a neural monollayer.    
43:57    
And and that's that I mean, you know, again, it's just like I don't know if I    
44:02    
should really be looking to Brett Kagan for for vindication, right? But like like, you know, that is    
44:11    
consistently been my point about why we should do that, you know, is that like    
44:19    
it is the it is the control um aspect that makes it really powerful.    
44:26    
Yeah. And and you know relating to that is like you know our ability to simulate it    
44:33    
relates to our ability to control it. Okay. So yeah this is the paper here.    
44:39    
Two roads diverged pathway towards harnessing intelligence and neural cell cultures.    
44:45    
Um and this is of course the comparison between organoid intelligence and bioengineered intelligence. Well both    
44:51    
broadly fall within the wider definition of synthetic biological intelligence. Why and BI diverge in their methods,    
44:59    
design goals and implications. Um the advantages and disadvantages    
45:05    
analyzed with respect to the existing challenges and future opportunities.    
45:11    
OI is a top- down approach that aims to recapitulate physiologically relevant brain structures these organoid    
45:18    
cultures. So they kind of go through and compare the two approaches.    
45:23    
Um, and you know, it's kind of one of these vision papers where, you know, that    
45:30    
they're kind of like there's a lot of promise that's or promises that are made    
45:35    
and they're kind of analyzing the promise of each method. So, I mean, you    
45:40    
know, I mean, there are probably a lot of things that are being taken into account, but uh, this one here in figure    
45:47    
one too, this uh, what is this? uh organoid intelligence and bio-engineered    
45:53    
intelligence and then they have like kind of like this mnest task and then they have these percentages.    
46:00    
So let's see if the full caption can tell us something about that. So um    
46:06    
yeah, OI and BI may intersect or diverge but could uh both could be considered as    
46:13    
stemming from general attempts to generate intelligent devices for some certain synthetic biology approaches.    
46:20    
In this way, the earlier term SBI acts as a useful catchall term for the field    
46:26    
while OI and BI would designate distinct approaches. Many experimental setups could be    
46:32    
applied to either OI or BI and there's some conceptual differences.    
46:38    
Uh here OI involves feeding in encoded signals which are here I guess and    
46:44    
allowing nonlinear transformations in activity to result in a collection of signals.    
46:50    
Um a classifier might work on the entire network and result in a confidence score    
46:55    
of key options. A similar approach might be adopted for BI. However, different    
47:01    
layers of the neural system may be utilized in pre-esigned distinct manners which could result in layers distal from    
47:08    
the signaling providing maximum accuracy. So, they didn't really explain the percentages. I find it's just    
47:14    
interesting how you know you're getting these different outputs from    
47:20    
some encoded signal that's put into the system and then you're getting things that come out. So I guess this is the    
47:26    
prediction or the confidence in the prediction something like that. What is this is a    
47:33    
seven or one? Yeah.    
47:39    
Yeah. Yeah. And I I I just dropped in a couple other um papers that that    
47:48    
you know Yeah. are are um together with the um    
47:57    
the you know everybody's got an AI company now um uh the the AI company    
48:04    
that um that pays Carl Fristen. So versus    
48:12    
um versus uh people have a paper with both Brett    
48:20    
Kagan and Adil Razi who's I I forget now. I think maybe Brett is actually the    
48:26    
CTO and Adil is the is the cso. I forget    
48:32    
how court collapse is structured but um but it gets at like like    
48:39    
these are these are additional papers in terms of just how their their approach    
48:44    
of getting work from from these organized or like getting    
48:50    
classification and yeah yeah um I was    
48:55    
going to call it machine you know I was going to call it ML but um but it's it's not ML if    
49:01    
If it's bio it's bio. Yeah.    
49:07    
Which is not actualological learning. Yeah. Yeah. Yeah. Yeah. Yeah. Yeah. So but it    
49:13    
it's it's interesting you know like again like this comes full circle back    
49:20    
to active inference you know in terms of of how you are uh um approaching the    
49:28    
yeah the the the training and the um    
49:35    
you know training control goal directed behavior.    
49:40    
Right. So the first paper here is the archive paper. This is a deal Razie Brett Kagan    
49:47    
and then this is uh simulating biological intelligence active inference with experimental or experiment informed    
49:55    
generative model. And so this is where they're actually doing active inference    
50:01    
uh with recent and rapid advancements in artificial intelligence. Understanding the foundation of    
50:07    
purposeful behavior and autonomous agents is crucial for developing safe and efficient systems. While artificial    
50:14    
neural networks have dominated the path to AI, recent studies are exploring potential biologically based systems    
50:21    
such as networks of living biological neuronal networks which are the organoids. Although there are other you    
50:29    
know if you're thinking about networks in the brain or networks in a a smaller    
50:34    
conneto then you know we're so talking about that as well    
50:40    
along with the promises of high power and data efficiency. Uh these systems may also inform more explainable and    
50:47    
biologically plausible models. In this work, we propose a framework rooted in active inference, a general theory of    
50:55    
behavior to model decision making and embodied agents. Uh so this is just kind    
51:00    
of this just applying active inference to this. Um we simulate decision making    
51:07    
processes in a simulated gameplay environment. So this is kind of like the dish frame approach but kind of like    
51:14    
extended to this active inference model. Our results demonstrate learning in these agents providing insights into the    
51:21    
role of memory based learning and predictive planning and intelligent decision making. This work contributes    
51:27    
to the growing field of explainable AI by offering a biological grounded scalable approach understanding    
51:35    
purposeful behavior in agents. So this is the I want to look at the paper a    
51:41    
little bit of 30 figures or so what they're doing here is they're basically um    
51:47    
yeah okay first of all they do mention dish brain so inspired by the dish brain    
51:53    
experiments and then they lay out the active inference method so they're building a    
52:00    
generative model based on pond dp which is the partially observed markoff decision process    
52:07    
Um and so they're uh doing that they're implementing that here. Uh pom dps offer    
52:15    
universal structure to model discrete state space environments where parameters can be expressed as tractable    
52:22    
categorical distributions. A pom db can be formally defined as a    
52:27    
tuple of finite sets. Soua so ss are the set of hidden states. O is    
52:34    
a set of observations. U is a set of actions. E encodes the    
52:39    
onestep transition dynamics. And this is the probability of transitioning to state s at time t given    
52:48    
the action of the last uh time point. And then uh a is encoding the likelihood    
52:56    
mapping for the partially observed setting. So that's basically the the model that    
53:01    
we use and they say in POM DP the hidden states generate observations through the    
53:08    
likelihood mapping in the form of some categorical distribution which is this    
53:13    
conditional probability and it's equivalent to this categorical distribution    
53:19    
here. So and so this is the cate sort of the uh    
53:25    
likelihood mapping of a state happening at any time. Okay. So um B is a collection of square    
53:33    
matrices uh where B sub U represents transition    
53:38    
dynamics. What determines the dynamics of S given agent agents actions U as    
53:44    
this um likelihood mapping um in A and B    
53:51    
the the state you know they'll take the likelihood mapping and the onestep transition dynamics of the state this is    
53:59    
represented as a one hot factor that is multiplied to regular matrix multiplication    
54:06    
okay then the marco vinity which is I think I've ever seen seen that before.    
54:12    
Yeah. The degree of Marovianness, I guess. Yes.    
54:18    
DP. Yeah. It means that state transitions are independent of history.    
54:24    
Uh and so this is the state. It only depends on the state action pair. So    
54:29    
this is interesting because they actually talked about that been kind of highlighting that in in some of the work    
54:35    
on um last year's active inference talk where there are these you know there's    
54:42    
this distinction between marovian and non-marovian models. Um and so that's    
54:47    
it's interesting there. Um yeah this is so the yeah um see yeah so from the    
54:55    
agent's perspective when encountering a stream of observations in time uh as a    
55:00    
consequence of performing a series of actions so the observations are all the actions are you the generative model    
55:07    
quantitatively couples and quantifies the causal relationship from action to observation    
55:14    
through some assumed hidden state of the environment. Okay, these are called hidden states    
55:21    
because the agent cannot directly observe the hidden state in the environment but it has to infer the state um from his previous actions.    
55:31    
Uh the agent maintains beliefs about S using the observations O    
55:37    
and so this is it's basically where you're observing the previous behavior.    
55:42    
You have a belief about what's supposed to come next. And so that's the um    
55:47    
that's the behavior that's emitted. Okay. So this uh shows this structure    
55:55    
and this is the the game that they play in dish brain where you have this ball    
56:00    
and it's moving around in this xy coordinate space and it's supposed to    
56:06    
predict the next position of that ball. So that's kind of the idea here. Um and    
56:13    
then they go through this um they have this classical formulation    
56:19    
of decision making. We talk about surprisal which is the measure of kind    
56:24    
of um I guess unique behaviors. So, you    
56:29    
know, when you have information entropy, you have a lot of things that are, you    
56:35    
know, kind of these different behavioral states and then a lot of that is called    
56:41    
surprisal because it's not sort of the same state over and over. Um and so recent experimental works    
56:50    
Kagan at all strong at all isomora at all use the concept of surprise in the    
56:55    
active inference literature to design feedback signals or embodied agents that    
57:00    
demonstrate improved learning with time. So this is again they're using this concept of surprisal as a feedback    
57:08    
signal in the system. So when you get a a unique feedback signal or uh like a    
57:14    
distinct feedback signal from a background sequence of the same behavior    
57:20    
then that acts as the feedback signal and it gives information to the agent and it allows it to learn things like    
57:27    
that. Um it should be noted that an agent is ignorant of the actual likelihood of any    
57:34    
observation and is not in full control of the environment. Um so the agent is not directly informed    
57:41    
of how probable an incoming observation is. So to estimate P 0 the agent must    
57:47    
internally encode and use a model to learn and predict the probability of incoming observations.    
57:53    
So this internal model is generative in the active influence over the tree. And    
57:58    
so um then this is of course the basis for minimizing variational free energy    
58:06    
uh of the observations one expects in the future. So then they start to get into policy space and some connections    
58:14    
to reinforcement learning.    
58:19    
And then of course they have this dynamic programming model to minimize    
58:25    
the variational free energy and then they get into counterfactual    
58:32    
learning. Um and then they get into the results    
58:37    
and uh yeah they just kind of demonstrate this. So that's this paper uh this archive paper    
58:44    
and then there's this other uh what is this journal here? I've never heard of    
58:50    
this cyborg and bionic systems. So this is I guess a newer journal but it's um    
58:57    
the paper here is called dynamic network plasticity and sample efficiency and    
59:02    
biological neural cultures a comparative study with deep reinforcement learning.    
59:08    
So now they're using deep reinforcement learning and this sort of approach to um    
59:15    
uh organoid intelligence to to see you know the differences are. So in this    
59:21    
study we investigate the complex network dynamics of in vitro neural systems using dish brain which integrates live    
59:29    
neural cultures with highdensity multi-electrical arrays in real time    
59:35    
closing. Uh by embedding spiking activity into    
59:40    
lower dimensional spaces, we distinguish patterns uh crucial for real-time monitoring and manipulation.    
59:47    
Our analysis highlights dynamic changes in connectivity during game play    
59:52    
underscoring the high samp highly sample efficient plasticity of these networks    
59:57    
in response to stimula. Um so they compare this uh efficiency    
1:00:05    
with biological biological systems as state-of-the-art deep learning deep reinforcement learning algorithms. So    
1:00:12    
they look at deep Q networks advantage actor critic network advantage actor    
1:00:17    
critic approaches and proximal policy optimization. They're doing this in the simplified    
1:00:23    
pong simulation. So in the last paper they showed the figure where yeah this    
1:00:28    
one here where where they demonstrate the pong game. They have this paddle and ball is    
1:00:35    
bouncing back and forth where it's bouncing against this surface and the pong paddle and it's trying to predict    
1:00:42    
the next position of this ball. So you can use like organoid intelligence    
1:00:51    
or you can use a reinforcement learning algorithm and kind of benchmark this to see which one is uh performing better.    
1:00:59    
Uh through this we introduce a meaningful comparison between these neural systems and DRL.    
1:01:06    
Uh we find that when samples are limited to a real world time course, even when these very simple biological uh cultures    
1:01:14    
outperform deep reinforcement learning algorithms across various game performance characteristics, this    
1:01:21    
implies a higher sample efficiency. So that's their takeway. So yeah, that's    
1:01:27    
uh these two papers. So this this paper they have their illustration of the the    
1:01:32    
dish brain and they have set up And they compare this with deep    
1:01:38    
reinforcement learning algorithms on the same benchmark. And they show some uh    
1:01:44    
visualizations through tne and ISO map of the performance here game play and    
1:01:50    
then following rest sessions and so they show the differences.    
1:01:56    
Yeah. Yeah. And and just just so you see that um in    
1:02:02    
the data availability on the right there. Okay. This is um yeah there's there's um    
1:02:12    
uh OSF um    
1:02:18    
and yeah be be really interesting to to see    
1:02:24    
how much is there. or is it not there yet? Uh let's see    
1:02:29    
this is it's maybe maybe not    
1:02:34    
maybe it's private maybe um I will I will follow up    
1:02:40    
in terms of yeah if you check check those I I I was assuming it was there    
1:02:47    
yeah I don't know what happened but there's a sub for definitely so okay okay okay    
1:02:53    
okay I I I will follow up I mean you know again like one of the reasons that    
1:02:59    
I think there's the that so little if you will work is going    
1:03:08    
on is that like you know having having access to this kind of still somewhat    
1:03:16    
complicated um um bioreactor    
1:03:22    
is is is not generally available. Um and so yeah, like like next week be    
1:03:32    
talking with Neuroch at Berkeley. They've got a wetwware um group of their    
1:03:39    
of their um their team or they've got a they've got a team that focuses on this.    
1:03:47    
um we're talking about how to yeah expand to to be able to do these kinds    
1:03:54    
of um these kinds of cultures um and    
1:04:00    
yeah like like we've got I've seen data sets from from the um Wolf group at    
1:04:09    
Munich where they're doing very similar things about you know again relating to this kind of like what the    
1:04:17    
lowdimensional space looks like if you start if you have data sets like these    
1:04:23    
um and you know what the what the um    
1:04:29    
what rest versus training um dynamics are and things like that. So um    
1:04:37    
hopefully we'll get to the point where you know data set access isn't the the issue and just like how to do you know    
1:04:45    
like again like how to simulate as well as like design training programs and    
1:04:51    
analyze those training programs like it's it's there's there's something there you know    
1:04:58    
uh um you know I I still I don't think biological you know again like this is a    
1:05:05    
company who's got kind of an interest to say that biological computing is a    
1:05:10    
thing. Yeah. Yeah. Um you know it's it's we we kind of have    
1:05:17    
been joking about you know how how quickly will it be before Cortical Labs    
1:05:23    
focuses on drug development. Yeah. because you know that's there's    
1:05:29    
there's a an industry to support that and you know whether you    
1:05:35    
can be a biological computing company when you know when cloud services exist    
1:05:44    
that you can program now and and so soft and stability and things    
1:05:52    
like that like are are absolutely functional companies uh that people can get work done you    
1:05:59    
know with now um so um yeah but just just you know it's    
1:06:08    
some additional work from Kagan in terms of just that um kind of vision paper on the kind of    
1:06:15    
two two paths of of organoids and bioengineering intelligence    
1:06:20    
yeah I like that that's that's a nice um set of papers that they're so they're putting out a lot of stuff on this.    
1:06:26    
They're kind of just going for Yeah. I mean, you know, a deal is is a student    
1:06:34    
of Fristan's. Yeah. Right. And like like some of the middle authors are basically engineers at    
1:06:42    
verses like like you got a lot of active inference people    
1:06:48    
involved there. Um and yeah, so    
1:06:54    
uh I will I will say that they're not the you know this has been um it's    
1:07:01    
something that the brain engineers are doing too, you know, and and some some of that is led by by Brett Kagan being    
1:07:10    
um publishing with them too. Um    
1:07:16    
but uh uh but I think you see this also    
1:07:21    
in terms of just you know how active inference uh relates to    
1:07:29    
control theory and and you know kind of other um    
1:07:37    
traditional topics in systems identification and and control right in    
1:07:43    
in engineering in general. Yeah. Because because like like the the the    
1:07:49    
Hopkins group um you know the Thomas Harding um Lenus MNOVA    
1:07:56    
uh group is is doing very similar kinds of things um together with the applied    
1:08:03    
physics lab they're you know algorithmically    
1:08:09    
there's a lot of overlap even though they don't use the um the the showy    
1:08:15    
marketing terms are like like you know the same Yeah. Yeah. Um    
1:08:22    
um so yeah. Yeah. I like the the way they lay out    
1:08:28    
their model in the archives paper. I think that's quite good to like kind of get a handle on what they're trying to    
1:08:34    
do. Yeah. And and you know like um Yeah. It's it's    
1:08:43    
I I still see like a bit of a hole in terms of or not like hole but like like    
1:08:50    
it would be nice to just um make a maybe a more interactive    
1:08:56    
simulation of of the pong as it relates to the the    
1:09:04    
as as it relates to some of these variables. um for for people to to understand how    
1:09:11    
they're they're kind of breaking Pong down. Yeah. And and and and then converting that    
1:09:18    
into the um again like like operationally what    
1:09:24    
does that mean in terms of the stimulation paradigm    
1:09:29    
or you know like like like how are you passing information to this biological    
1:09:35    
right? Yeah. Construct. Um, so you have to take the feedback. They    
1:09:43    
talk about surprising being like so some surprising event or different type    
1:09:49    
of event you stimulate the brain tissue and then somehow    
1:09:54    
helps it to learn that that's a maybe an advers stimulus or it should respond. But like    
1:10:02    
I mean like thinking back to some of the experiments and like ebian plasticity like what does that    
1:10:09    
look like? What what what kind of signal do you actually have to send and how efficacious is that signal?    
1:10:16    
Is it automatically you know supposed to work or is it just kind of like a generalized response of    
1:10:22    
the network or what is going on? Yeah. Yeah. And and then and you know    
1:10:29    
like like how are you and then how in the analysis of that post post    
1:10:35    
stimulation you know what what kind of changes are you expecting and you know    
1:10:41    
how does that in the the um to use you know Fristonian language    
1:10:50    
how how does that relate to your manifold right    
1:10:56    
Well, I'm just thinking about like if you had a change or if you had a, you know, you stim you stimulated something    
1:11:03    
in response to a stimulus, you know, in in the brain tissue and you got a response. Um, is that response always    
1:11:12    
um a positive like it's think in terms of reinforcement learning is that positive reinforcement or is it just a    
1:11:18    
signal that's gives a response and that response might be the same if    
1:11:23    
you have the signal or not. like it's it's basically like almost like a semi- stochastic response    
1:11:30    
that is maybe a false positive. So, you know, they you can play the game    
1:11:35    
pong effectively, but it's a pretty low dimensional game. Maybe in a higher dimensional setting,    
1:11:41    
you'd start to see these false positives crop up where it's actually making mistakes. Yeah.    
1:11:46    
Yeah. Yeah. Yeah. No, I I I Anyway, I I I was    
1:11:53    
I I was suckered in by the data availability. Oh, yeah. And and was was hoping that uh Yeah.    
1:12:02    
Anyway, I I really do like like like I I want to do a lit search that is is    
1:12:12    
like very with a wide net but that focuses actually on just one    
1:12:21    
particular output. Yeah. In all of these papers which is how many    
1:12:27    
of these papers actually have codes? how many newspapers I actually have data sets, you know, in terms of of things    
1:12:34    
that students could play with, right? You know, right now. Um um and yeah, and    
1:12:42    
then I've I've got to start a a a name and shame campaign or something, you    
1:12:49    
know, come on people, let's get some data sets out here. Uh so yeah.    
1:12:58    
Yeah, it would be but I would like to see that I would like to to play around you know like again like this should be this    
1:13:04    
should be an easy simulation and how how best to understand these these these    
1:13:09    
learn learning paradigms when when when the signal is so binary    
1:13:15    
right that yeah like like yeah um    
1:13:21    
anyway yeah okay that's great thank    
1:13:28    
Uh so yeah, that's uh that's great. Thank you for all the update on that and    
1:13:34    
and then getting into the papers. Those are pretty good papers. Um    
1:13:40    
so yeah, hello Jesse. I see you've made it. Um    
1:13:46    
of course, yeah, it's fine. Last week we uh Jesse was at the MIT    
1:13:53    
event and we did a a stream where he was going around on his phone and doing kind    
1:14:00    
of a live tour of the event and it was pretty good. Um, we have it    
1:14:05    
on the YouTube channel and uh I don't know Jesse if you wanted to report on    
1:14:10    
any followup from that. Yes, I do. Uh, give me give me like    
1:14:20    
one more moment to try to set things up here. All right.    
1:14:25    
Well, yeah, it's good because I have a couple more things to report on here. So, so the first thing is    
1:14:30    
congratulations Devit for posting this post on sustainhub kind of like the    
1:14:35    
summary of sustainhub and this is the uh it kind of goes over    
1:14:41    
the vision what's involved. So there was a lot of reinforcement learning. There    
1:14:47    
was a lot of um modeling using multi-arm bandits, agent-based modeling and um    
1:14:54    
development of a number of metrics. So during our open source meetings this um    
1:15:00    
this summer, you know, BD was able to go over a number of metrics she developed    
1:15:06    
to evaluate performance and uh they look like pretty good metrics. And so yeah,    
1:15:13    
then she lists the poll requests that were made here. Um, and yeah, that's    
1:15:19    
that's largely for the benefit of maybe future students or people who um, you    
1:15:26    
know, are interested in how you contribute things in open source. So um,    
1:15:32    
yeah, there are a number. So we had the SARSA implementation, multi-arm bandon implementation,    
1:15:39    
uh different metrics, the harmony index, the resilience quotient, the reassignment overhead and then of course    
1:15:46    
the graphical user interface and then the final readme    
1:15:52    
and then we had of course the core methods uh then this application reinforcement learning um this dual    
1:16:00    
level of reinforcement learning. So there's agent level reinforcement learning and community level    
1:16:05    
reinforcement learning and then of course our key metrics and then this is    
1:16:11    
the sustain hub model sort of models the    
1:16:18    
uh fairness and efficiency of task distribution in projects. So we can    
1:16:23    
understand sustainability in open-source projects from the way in which tasks are distributed and um you know this should    
1:16:32    
allow for consistent meaningful contributor participation. So then this is going through    
1:16:40    
you know the weekly timeline recap. So I believe that yeah she posted midterm    
1:16:46    
evaluation post which was just kind of like a midterm checkin and then this was    
1:16:52    
more conversational and so yeah if you want to understand her project go to these two posts here.    
1:16:59    
Um yeah, so congratulations to VD for completing GOC and hopefully everything    
1:17:05    
is um you know that you uh continue on    
1:17:10    
in your work and I don't know if you want to continue with this project but we now it's it's an open source project    
1:17:19    
on our um GitHub and um you know maybe next year's GOP    
1:17:25    
we build upon this um I'd like to actually turn to some of the active inference stuff too because this was    
1:17:32    
something that Brian Mccorpal did um several years ago. he did some active inference work on    
1:17:39    
um open source sustainability and kind of bring that up to date or um he    
1:17:46    
applied POM DP some models uh of collective behavior    
1:17:51    
and but then it's like you know we didn't have any no one else took up that mantle whereas we've been developing    
1:17:57    
reinforcement learning stuff for several years in a row so it' be interesting to kind of get that uh and then kind of get    
1:18:05    
the active inference stuff uh aligned with the reinforcement learning stuff.    
1:18:10    
So that's congratulations to BD for her uh completion of program.    
1:18:18    
Um I don't know if Jesse's ready now.    
1:18:25    
Um I can get started. It'll be a bit of a slow start. I'm having some issues with my other    
1:18:33    
um with my devices basically, but I think    
1:18:39    
you can hear me okay for the moment. Um, I would have loved to have finished my    
1:18:47    
um draft so far of what it is that I am    
1:18:56    
uh put together. Probably the easiest thing I can do is    
1:19:02    
slightly go over the email that I sent out. Actually, I realize that now. Maybe I'll just do that. uh because I sent her    
1:19:10    
a data and direction email and that's a pretty like fair capture of things. So I    
1:19:15    
mean yes it was uh there was a mentioning of Frontier Tower uh but    
1:19:21    
Morgan was wasn't there. We missed Morgan. Um I don't know um I don't know    
1:19:28    
there's anything we talked about earlier but um    
1:19:33    
here we go. Yeah. Um yeah I'll go through stuff. So I think I think this    
1:19:39    
is sharing now. Does that look normalish? Yes. Okay. So this is this is um a particular    
1:19:47    
um email    
1:19:53    
that I sent out to the directoring folks. But I'm just going to focus on the first part really which is all this    
1:19:58    
stuff. Um,    
1:20:04    
I don't know if I can do LinkedIn on this very well, but um, essentially    
1:20:09    
here's some nice pictures when I'm breaking it. It's so funny because I' I've written so much stuff since I've    
1:20:15    
made this email and it's like, oh yeah, and it's like I'm like, and this is where I go into this part. But    
1:20:21    
essentially, um, to recap the event as a whole, um, it was it was really good and    
1:20:27    
really impressive in a way that I didn't expect. Um, you can see my super brief um,    
1:20:33    
discussion here. Um, for those who don't know anything about the AUG lab, I didn't know about it. I didn't even get    
1:20:38    
what it really was. Um, but really what the AUG lab is is essentially a um,    
1:20:48    
it is essentially a two to three month summer program. It's and you kind of live in a hacker house and you make    
1:20:54    
stuff. And what the AGL lab summit was is this um    
1:21:02    
like their finale. Like they show off, they do their demo day. That's what it really is. Um and I didn't I didn't    
1:21:09    
quite understand all of that when I first um figured things out. I've done I've    
1:21:15    
done a few things with them or not, but I didn't I didn't fully go into the event knowing that that was the setup.    
1:21:22    
Um, and it made it made quite a bit of sense. If you can if you can.    
1:21:28    
Yeah, here's the agenda. Just to go through that quickly. You opening stuff. Echolapto who um I've done a bit with    
1:21:37    
recently. Augmentation lab, we've been I've been doing some things with them and gone to a few of their events. Pulse    
1:21:43    
uh I'm least familiar with, but these are sort of the main folks about it. The    
1:21:50    
first session was essentially someone from the media lab itself going through    
1:21:55    
what the media lab is and and how you can apply uh which was cool and then uh    
1:22:02    
some iconic professor uh Hiroshi Ishi um a lot of cool stuff he kind of just    
1:22:09    
laid a big big time overview mentioned his heroes and gurus. I don't have any    
1:22:14    
great pictures of that I can easily show you but that's I there were some photos from it and it was interesting to see    
1:22:20    
his take on things across time like there was like old school information theory cybernetics people um not like    
1:22:27    
Norbert Weiner per se but like people from this era of going going 40s 50s60s    
1:22:33    
up through um it so it was a nice historical take I think it was really cool and it's not like the    
1:22:43    
It's It's not um I'm sure a lot of folks would do it if they could, but the fact    
1:22:49    
that both Ishi and um Wolram were there.    
1:22:54    
Wolram was sort of the the finale person, but there was a really nice    
1:23:00    
element of older generations contextualizing things. And I don't know    
1:23:05    
how intentional that was or not. I'm sure it was somewhat intentional, but for a lot of    
1:23:12    
it's not it's one thing when you have, you know, nice big names and and people you can easily draw on that want to do    
1:23:19    
this stuff and that's sort of one of the major perks of being housed in Boston, you know, but    
1:23:26    
I I in in in an ultimate Jesse version at the conference, I would have even teased it a bit more or like tried to    
1:23:33    
have a session for like Wolf from and Ishi and maybe a few they're like really really senior folks explicitly    
1:23:42    
mention context um and devel and the development and how the moment that    
1:23:47    
we're in is different than the moment that they've the moments that they've been in before because I think I think    
1:23:54    
people I continue this is a this is a side Jesse sidebar comment I continue to    
1:24:00    
realize how much um one of the things I'm writing about in    
1:24:07    
in in the summary piece which is not just a summary piece but a collection of many of my thoughts is literally    
1:24:12    
narrativity is literally the the pressures of the current moment    
1:24:17    
on narrativity is a commentary on um    
1:24:25    
alienation and the lack of coherent stuff very much present shock very much future shock    
1:24:32    
into present shock into into all this stuff and I I think crossgenerational    
1:24:38    
perspectives um at the very least give this give this sort of uh core message that you too    
1:24:47    
like like things matter and you will be at a different developmental stage and you    
1:24:53    
will be able to speak to the the folks that are now in your shoes and and like sometimes it doesn't seem that obvious    
1:24:59    
until someone says it directly to you that you're part you are part of the continuity of a lot of pressure in the    
1:25:05    
world a lot of pressure in the world right now against it. So I think on that level it's very fascinating to see um a    
1:25:11    
lot of what was taking place here. Uh but back to literally the regular    
1:25:18    
schedule of the program. Uh the next section which I didn't really get to see because I kind of got this call like hey    
1:25:24    
go out and set up exhibitor stuff. Um so I didn't really see much of these. Uh, I    
1:25:30    
did see the first one though with Dogga, but these are basically the longevity suite of of stuff. Um, basically why you    
1:25:38    
should do it, care about longevity, here's um, you know,    
1:25:45    
a method that's going to be promising. And then Ellen's sort of a a celebrity    
1:25:51    
influencer person who was like, how do we popularize this? Um    
1:25:58    
and then kind of simultaneouslyish uh was was this exhibit space. Um there    
1:26:05    
was the the there was an the hall of exhibitors which is where my live e    
1:26:12    
excellent in quotes live stream video uh took place. It was not not the highest    
1:26:19    
quality but it was a nice behind thes scenes look. And then at the same time, which is a    
1:26:26    
little tough, but I mean it makes sense. Uh well, there interesting startups. Um I    
1:26:33    
knew some of them. Silven AI is the one with Dan Venzite um that    
1:26:40    
I mentioned sort of being state-of-the-art AI related and some other cool stuff there too. These are    
1:26:49    
external folks. Um, a lot of those are at Frontier Tower.    
1:26:54    
I'm sorry. A lot of these are at Frontier Tower. Oh, really? Oh,    
1:27:00    
so so you know, Muse Bio works on our floor. I mean, you know, because it's    
1:27:06    
biotech. Um, is on the 11th floor    
1:27:12    
and uh R3 is not directly working with us, but uh    
1:27:19    
actually Uh, I've got to credit R3 for donating so much stuff to Biopunk.    
1:27:26    
So, thank you, R3. And yeah, and I might know some more of    
1:27:34    
these, too. But this this also reflects the fact that um um Pedro and and Vic    
1:27:41    
who were organizing this um Yeah. obviously highlighted some people from    
1:27:48    
the tower. Yeah. Yeah. And there was a mention of front like maybe they talked    
1:27:53    
about it more here because I was I was like at this time I was completely not a room for like this stuff. So maybe the    
1:27:59    
intro mentioned them specifically. I don't I wouldn't have known. Um    
1:28:05    
but there was a mention of Frontier Tower during the intro. DA was talking here, Addie was talking here and um the    
1:28:12    
other gentleman was here. Um and they there was a little mention of your Tower somewhere there. Um    
1:28:21    
yeah. Um so that was this lunch lunch lunch this this time and somewhere    
1:28:27    
around here is when actually the video that I took was made uh lunch    
1:28:34    
then uh keynotes uh human machine symbiosis would and these two folks from    
1:28:40    
the media lab uh you may recall uh Natalia is the I don't think I listed    
1:28:48    
here yeah she's she's behind the your brain on GPT paper that's going around    
1:28:53    
everywhere. Um, it was very interesting because she    
1:28:58    
basically changed her presentation like the day before it happened and she did a    
1:29:04    
lot of I don't have any good pictures to show unfortunately but her presentation was essentially about bodyful bodyless    
1:29:12    
and sort of a very she basically most of her presentation    
1:29:17    
was essentially an axis on screen a four quadrant axis uh and and it was like    
1:29:24    
here's like really embodied, here's not embodied, here's like really invested in artificial intelligence, here's like    
1:29:30    
less invested and all these different versions of these dichotoies represented by popular films and and like    
1:29:36    
contemporary sci-fi. Um she does a lot with um but basically she does a lot of this sort of I've been I've been to some    
1:29:42    
of her events like at at a local like museum, a local expo where she's like here's let's look at you know like these    
1:29:49    
these sci-fi technologies and everything else. Um and and so there's this like very very tried to map certain thought    
1:29:56    
spaces and things like that. Um and she basically made her presentation a tour    
1:30:02    
of of all those different spaces with some axes. So I wonder if that's something that she's working on specifically uh not not repurposing the    
1:30:10    
video per se. She's already she's already done that in some of her work, but like I'm curious if it's what she'll    
1:30:16    
do next. And then uh Pat Pat um    
1:30:21    
is I put anything here for him. Uh Pat Pat for those who don't know he he's now    
1:30:28    
um a professor at the media lab. He's got his own he's got his own uh working    
1:30:35    
group now and it's it's the uh I think it's called psych cyborg    
1:30:41    
psychology proper but he was with Patty Maze at fluid interfaces. Um he    
1:30:47    
co-directs the advancing uh humans with AI. Um H AI H AA it's the AHA program uh    
1:30:56    
which I'm fan of. Yeah, I really enjoyed his talk. Um and I'm going to feature it    
1:31:04    
a lot of my write. I don't even put all the slides here but um    
1:31:13    
you know that's his his logo. There was a there was a very good    
1:31:18    
his his there was a it was a really really really really really rich talk. Um, and I think I think in terms of    
1:31:27    
conveying it to everything else that I want to do and am doing, it was my    
1:31:32    
favorite talk. Uh, because and I don't have the pictures in this particular,    
1:31:38    
you know, Twitter post. Um    
1:31:44    
he he went into things like new technology, old pedigogy.    
1:31:52    
And he has that sort of classic image of the um students sitting in a class like    
1:31:59    
kind of like a almost like comic or I say wood shop wood wood carving but like like that very old school uh    
1:32:07    
illustration of students in a classroom at a desk strapped to like some machine that that is like electrically connected    
1:32:15    
to a teacher professor like grinding books down and that image but then it    
1:32:20    
puts overlays it with like this is AI this is an LLM and this is what you know and it's sort of like getting really at    
1:32:26    
some of the systemic um stuff like a lot of this uh I wouldn't say the focus is    
1:32:33    
on changing systems per se but very much this um augmentation    
1:32:42    
meaningful augmentation as flourishing and flourishing as being what what he's    
1:32:48    
trying to center in in his in his working group. Um, so technology    
1:32:53    
supports human flourishing. And then he went into these different components during his his talk about wisdom,    
1:32:59    
wonder, and well-being. Um, he mentioned future view. He mentioned um a number of    
1:33:05    
projects that have happened. Um, and I think it's I think it's I think I'm I'm very excited. Honestly, I might even    
1:33:13    
I've been trying to think about what to do because I do want to do more education and I might I might even just apply to his program. um because because    
1:33:22    
I like it. Um although a little bit later I I might talk a bit about some of    
1:33:28    
my um future directions in that. Uh so yeah,    
1:33:34    
where are we? Uh this is great. I I I really think I really think just being able to pull these two keynotes from the    
1:33:41    
media lab. Um, granted like these are like you know DA's DA's in in in in the    
1:33:49    
fluid interfaces group and and so and other many other people in in the res in the um    
1:33:56    
augmentation lab have ties here. Yeah. But to go from this panel from this    
1:34:02    
these keynote section to this panel um was huge. My real favorite parts of    
1:34:10    
of the whole series were the panels. Um just because of    
1:34:17    
this was you the talks were cool but they were kind of    
1:34:24    
um you didn't get to dialogue about it. They were just sort of like idea it's    
1:34:30    
like condensed lectures or here's here's some key points that I want to share. the the the panels were fantastic and    
1:34:38    
changed what the event was to me. Um, so there's    
1:34:45    
this panel and then I'll get to one later that that was R&D for the future    
1:34:50    
um with Prospera, Harry Gandhi, um, and Sam Row from Athos, which is a local,    
1:34:57    
um, I don't know, startup incubator type group. Um, and then Addie from    
1:35:03    
Echolapto. Originally was supposed to be DA, but DA wasn't available for this basically. So Addy kind of stepped in    
1:35:09    
and was sort of a co-odderator and shared his own experiences and then also um moderated from Wolf    
1:35:17    
from later. So good job Addy. Addy stepped in. Addie is 23 years old and he's he's uh taking a lot on to to do    
1:35:24    
this stuff and he he he really he really makes uh things work and um    
1:35:31    
puts a lot on himself to do it and and I hope to support him ahead in a lot of things. Uh, but shout out to Addie for    
1:35:39    
um making a lot of stuff happen, including being in support of this event. But yeah, the panel I I could I    
1:35:45    
could spend a lot of time here in both of these panels, and I'm going to spend a lot of time in my write up dissecting    
1:35:54    
points u made in these two panels. Um, but to stay chronologically aligned at    
1:36:00    
the moment, and I don't know if I have any good pictures of this here, this is the panel proper. Uh I think it might be    
1:36:09    
Yeah, it's Yeah, I It's the same This is the same image. Um    
1:36:15    
but no, like this this was extremely    
1:36:20    
uh relevant and interesting because because    
1:36:25    
um I like this slightly better right now. Um    
1:36:30    
because um I I guess I guess the title I don't know if it says any more about it. Yeah.    
1:36:37    
The future work in meaning from an author who's also a lawyer. Uh Kendall    
1:36:42    
was a really interesting guy. Julius Gore um who really got the econ    
1:36:47    
perspective and Greg Epstein who's this chaplain uh at Harvard and MIT like he's he's a    
1:36:54    
religious I guess you know a scholar but also a    
1:36:59    
chaplain and it was sort of really it was really interesting and I didn't know    
1:37:04    
I didn't know like my excitement level for the event if I knew I mean I did know I was going    
1:37:12    
to be there but like I didn't know they were going to be kind of encouraged to talk about what they did and both panels    
1:37:18    
even. But even for this one in particular, um it was just it was just a    
1:37:23    
very nice mix of, you know, this is why why I mentioned earlier I mentioned narrativity, I mentioned present shock,    
1:37:29    
I mentioned meaning, I mentioned animation. And so for a bunch of tech folks talking like these these things    
1:37:36    
were on the table and I regret like I kind of wanted to get I didn't I didn't have time or I didn't I didn't I was in    
1:37:43    
the wrong mindset to think I should just go get a book signed by Kenloo and talk to him directly afterwards and like do    
1:37:50    
that more like I I should have done that. I didn't do that. I regret that. Uh but just for there to be essentially    
1:37:56    
a bunch of nerdy tech folks where you have this panel    
1:38:02    
um with both the the meaning making of it, how does it affect work? what do we    
1:38:08    
do? like it the contextualizing that was done here in this panel and even for the    
1:38:14    
R&D panel um is exactly what future technologists in in my view    
1:38:23    
need to be thinking about because the other side of the coin that wasn't said here although it was kind of hinted at    
1:38:29    
from from a number of folks like even even Natalia kind of commented on this    
1:38:34    
but there was no explicit commentary that's like hey like Karen like a Karen how commentary, Age of Empires    
1:38:40    
commentary. Nobody really said that outright. Not that they were avoiding it, but like the only only thing missing    
1:38:45    
from the contextualization process of this conference to me was Karen How of    
1:38:52    
Age of Empires. Empires of AI although it is age of empires like that. That's how I'm actually referring to it myself.    
1:38:58    
That's why I'm saying it like we are in an age of empires right now. Um so if    
1:39:04    
you take that aspect Karen how type work and then this meaning making and you    
1:39:09    
contextualize and say like pat okay like meaningful augmentation like let's like    
1:39:15    
how do we do that what is that what is flourish in that sense it's like like hell yeah like that's that's like the    
1:39:21    
challenge like that is it um and maybe maybe we robot if you threw in like like    
1:39:27    
a good dash of wei robot um you would have a really really wonderfully complete like as in like the policy    
1:39:34    
side, the horrific policy landscape that lawyers and good goodnatured and    
1:39:39    
well-meaning people are are uh hopelessly attempting to stem the tide    
1:39:45    
to be a little grim about it. Um but you know like like and I'm I'm kind of me saying this because I'm I'm saying this    
1:39:52    
out loud as I'm thinking like if I could design a conference next year what would I want it to look like? So I was like a    
1:39:58    
little Princeton Envision, a little Wii robot, a little Karen How, a lot of augmentation lab uh summit, a lot of    
1:40:06    
this panel, a lot of that panel, a lot of these keynotes like that's that's like what what what should folks know    
1:40:12    
and then what not framing it that completely what can you do with it? That's where my mind is yes going for    
1:40:18    
some things. Needless to say, I very much enjoyed the panels um including    
1:40:24    
this one. Um, there are a lot of great quotes. Uh, Greg did a wonderful job of    
1:40:29    
like re really calling out like, "Hey, I know you're all talking about, you know, technology, but uh, is this not like    
1:40:39    
messianic and apocalyptic? Like, are you not putting your faith in certain outcomes that let's just get to this end    
1:40:46    
state and then we're gonna be all great or going to be all bad?" like he he draw he did a great job of drawing out the    
1:40:52    
religious parallels that I think are unpleasant to look at for people that    
1:40:58    
maybe think they're very rational and and have absolutely no bearing to the    
1:41:03    
the faults and sins and wrongdoings of the past because because they're building a technology. It's like well    
1:41:09    
okay so that was cool. Um Ken had a lot of really really good perspective recontextualization    
1:41:15    
on you the human condition and Juliet brought in some you know her one of her    
1:41:21    
takeaways was you know the defense of the four four day work week or three-day work week and rain pilot program that    
1:41:27    
she's doing with that but also just at at its core sort of the defense of having time to do stuff like you could    
1:41:36    
say sovereignty autonomy the defense of you you as a human being you can have um    
1:41:44    
time to do what you want to do as opposed to present shock as opposed to    
1:41:49    
everything well just work more work more work more work more. She she kind of gave a little historical perspective of    
1:41:55    
um you know when when industrialization happened like you know    
1:42:02    
and and all these things happened where it's like okay well there's a new technology but okay everybody's work work more work work more we can have    
1:42:08    
everybody work more but then these movements coming in to say well maybe we should have you know child labor laws    
1:42:16    
maybe maybe we should have things called weekends um you know like like there's there's    
1:42:23    
there's sort of an the productivity goes up but then maybe isn't accounted for    
1:42:29    
and the adaptation and I think that's a fascinating nexus because the rapidity of the changes now versus society    
1:42:36    
catching up to them you know that is where we're in that's the exciting challenging crazy    
1:42:42    
uh time that's that's that's the moment that's the timeline we're in and that's something that I'm trying to try to    
1:42:48    
emphasize for many folks when I when I talk more and more about this. So yeah,    
1:42:53    
um Super Preview Alise uh was the moderator. She's doing some things with    
1:42:59    
Salone. Um she's a good moderator. She um    
1:43:04    
uh brought brought brought out a lot of the different segments. Well, um so    
1:43:11    
kudos to her. Um let's see where we at here. I'm not going to go through all    
1:43:16    
the residencies because there's a lot of them. Um, and you can you can look at them on the augmentation lab website.    
1:43:24    
Uh, but this is when I was like, oh, like this is what this is what the residency    
1:43:30    
what they've been doing for the last while. Um, I had a I had a I attended um    
1:43:39    
this is Ron and G or Parth and he I attended a echolapto workshop salon with    
1:43:44    
him a few weeks ago at Harvard. his interesting ideas about the future. So,    
1:43:49    
I'll just shout out that. Um, there's many, many, many interesting things here. Um, and also some past residency    
1:43:56    
projects that were really interesting, uh, like narrative tales or conceptual tales that fit a lot with plot twist,    
1:44:02    
what's going on there. Uh, so yeah, we had more exhibitions, book signing. The    
1:44:09    
hypnosis session also was super fascinating. Um, I could say a whole lot    
1:44:14    
about that. I don't think I have any easy pictures from this here. This was actually way cooler and more interesting    
1:44:19    
than I thought, especially when actually combined, which is kind of funny because you can see like the time a little weird    
1:44:26    
when actually combined with go um Andre's from QR. Um if if you got these    
1:44:34    
folks together and like spoiler, that's basically what happened the next day. is not on here, but um there was this this    
1:44:45    
is what happened the next day. Kurt was originally supposed to be at the Media    
1:44:50    
Lab event proper or the uh the summit and he he wasn't. So, basically, he he did a little recording with um Andre's    
1:44:58    
the next day. And where where we're going with this, and this is me being a big- time nerd, uh where we're going    
1:45:06    
with this is um if you combined    
1:45:13    
the QRI stuff with the hypnosis stuff, it was so interesting. And also I    
1:45:18    
mentioned somewhere in here um the QRI stuff    
1:45:24    
and the hypnosis stuff really had an interesting job of    
1:45:32    
kind of triangulating or like pinging like like like sonar detection inside    
1:45:38    
pinging around inside the black box to see what what's going on. And with with the the the    
1:45:44    
hypnosis was um it was cool to see people, you know,    
1:45:50    
whatever, but there was sort of like um oh now now how how would let's say    
1:45:55    
you're you're Grock or or ChatGP, how would you respond to this? Um and like    
1:46:01    
okay that's funny but but what it did there was a great there's a great um I'm not going to try to find it but Andre on    
1:46:08    
Twitter later said oh like you can clear like like jailbreaking some of the LM structure of of of mind stuff and of    
1:46:15    
course I think of Elon Baron Holtz who's doing a lot of work on that um particular topic regarding language as    
1:46:21    
LMS and stuff like that but you know basically people get into a suggestive state and then you can you can using    
1:46:27    
certain stimulus and and I thought it was very clever and very interesting how Albert one he asked one of the the the    
1:46:35    
attendees like, "Oh, are your friends here?" And they they're like, "Yeah, we know him." And and like, "Oh, does he    
1:46:41    
does he does he drink much?" And what he was trying to do was like, "Does this person does their internal storage know    
1:46:50    
what it's like to have a beer or two beers?" and he demonstrated    
1:46:57    
um one seeking the awareness of it but then also like he basically produced doubling effects of okay you've had one    
1:47:04    
two what about four what about and like like he was able to connect the internal    
1:47:10    
structure of the person no getting confirmation that because he he wouldn't he didn't want you know he he was    
1:47:15    
checking to see he didn't say this but I I deduced he would he didn't want to give the person commands that they had    
1:47:22    
no exposure to it was Well, pretend like you know you're high in a drug that you've never had    
1:47:28    
before. Like he didn't he didn't he he wanted to avoid that. And I was like, okay, yes, like that that makes a lot of sense. So the way that he crafted it was    
1:47:35    
interesting. And the way that between that and and what a lot of the QRI talk was about was essentially yes drugs but    
1:47:42    
but more like what are these select stimuli doing and how do they the QR and    
1:47:49    
and is very um uh phenomenologically interested. So, a lot of like I got to    
1:47:56    
ask a little bit about like okay like here's the Velian lineage of trying to bring rigor to uh this and I have a lot    
1:48:03    
of respect for like you know there's a little bit of overlap between like the interviewing where was it going with I'm becoming aware where was it going like    
1:48:09    
the second person stuff how do we get from first person to second person to third person ways to evaluate this and    
1:48:14    
make it more rigorous and it's like here's you know here's s here's like what the cure is sort of doing to this    
1:48:20    
so having that combined with Albert who again Albert was not presenting itself as a scientist, but he mentioned like    
1:48:26    
threat simulation. He mentioned um the going I forgot not catatonic but like    
1:48:33    
when you rub when you rub the shark's nose and it goes it just limps out and like stops moving like like all these    
1:48:40    
different actual like like somewhat rigorous um studies of like okay well    
1:48:46    
nobody nobody knows he's like nobody really knows what this particular state is or how to talk about this but like    
1:48:52    
here's what we can here's what we can do in this state. So, it was quite it was quite a compelling and not not at all a    
1:48:58    
sideshow, but actually quite compelling in the sense of especially for this crowd. I think it was a really nice    
1:49:03    
interesting choice. Um, and I know that Add's done a little bit with Albert before um, in like Toronto area or    
1:49:11    
whatever, but it was a very interesting component um, in a    
1:49:18    
here's here's an existing very clear augmentation    
1:49:23    
uh, within current bounds within no new technologies. This is this is just like this kind of like this is what you're    
1:49:30    
working with like this is part of the inherent system that can manipulate it in these ways.    
1:49:35    
Um, so it was an interesting combination between these two. Um,    
1:49:41    
I'm not even going to talk about Wolfrram because, uh, he's a cool guy. We all know him really well. Um, he's a    
1:49:47    
great great endeavor. I will say a little bit and I don't I don't know how much time I have rather like a minute or    
1:49:53    
two. Oh no, you have as much time as you want. Okay. Um,    
1:49:59    
do I have a good picture for this? I don't think I have a great picture easily here that I can share. Um,    
1:50:06    
suffice to say, this panel was also fantastic and I'm going to detail quite a bit more of it um ahead.    
1:50:16    
Um, let me really quickly look to see if I have Oh, the link LinkedIn.    
1:50:24    
How convenient of me. I forgot like I made this post. Yeah. Yeah. Great. Uh,    
1:50:29    
cool. pat myself on the back. Um, so here's    
1:50:35    
what the panel looked like. Um, and again, this is going to be done at the off lab here and done fluid interfaces    
1:50:41    
stuff here, but she um was unavailable for this. So, um,    
1:50:49    
I'm just going to read my post and then say more about it. There were so many great things about the Olette summit    
1:50:56    
this week. Uh, particular shout out to the folks on the panel. It was refreshing to see the way everyone spoke    
1:51:03    
about doing research and developing ideas as many R&D spaces and approaches    
1:51:08    
aren't that interested in actually changing or challenging systems at large. This week I've had great    
1:51:14    
conversations with our Jopra interns about the different areas innovators will find themselves in and how to    
1:51:21    
speak, understand, and navigate them as we push ideas and projects forward. Uh    
1:51:26    
both panels as I already said I like both of them uh this one and the future work meaning the first one really hit    
1:51:33    
home on the goal of centering the human condition building uh from within the act    
1:51:40    
well that should be the actual world we're in right now it's quite welcomed at a time as I kind    
1:51:48    
of said before where it's often more convenient to be abstracted and disconnected from our current moment the    
1:51:53    
current moment we have it as fragmented narratively disputed present shocked    
1:51:59    
digenial laden as it may be more on this later which is talk about the write up so kudos to the organizers and cheers to    
1:52:07    
folks that are doing all this stuff so that's my you know glowing take on things but what was really cool about it    
1:52:14    
uh I didn't know a whole lot about some of these folks and what they're doing but Harry Trey Joff is um    
1:52:23    
is oh it's not really is uh with Prospera and I'm not even    
1:52:29    
going to try to explain what's going on but Prospera is essentially trying to re rework some things about um    
1:52:37    
economics and laws and innovation and there's a special economic region in    
1:52:43    
Honduras and I don't know if Morgan or anybody else wants to say and step in    
1:52:49    
and comment on that you can. Uh but it was really interesting to see what he and Prosper are attempting to do as like    
1:52:57    
actually changing well not changing but like experimenting. I see this as an    
1:53:02    
experiment and and how do you get people and and countries and and and and    
1:53:08    
how do you how do you try to create these different environments? And this is like a very um hands-on approach, not    
1:53:15    
just sort of let's make a a lab like no, this is like let's make an economic    
1:53:20    
arena where you can do things in a certain way. Then I'm sure they're not without controversy. I'm not saying they're oh this is the true way forward,    
1:53:27    
but it's very interesting to get a take from that level. And it's also supremely interesting to see how everybody spoke.    
1:53:34    
Um, Trey is very much, you know, DC speak    
1:53:40    
and American politicians right now, I think, basically have to speak. There's    
1:53:45    
a very particular cadence about solutions and here's the problem and then here's a solution that will bring    
1:53:52    
you success. There's a very particular way of speaking that he embodied which I    
1:53:57    
found very interesting and and it was totally disharmonious in some ways. No. Well, that's not true. that's um there    
1:54:04    
wasn't any disharmony but to I guess would say a trained eye or a trained ear    
1:54:10    
and someone who is spending a lot of time and writing materials and educating others about talking different arenas    
1:54:18    
it comes across and like he's got his whole look you know he he looks like a DC lobbyist type you know someone who's    
1:54:25    
going to get get down in there and make make some deals and advocate you know and it was interesting to hear that    
1:54:31    
compared like Addie who's probably very far away from from that. Um and then you    
1:54:38    
have this Sam from Athos who is um    
1:54:44    
Sam and Harry both sort of these community oriented softer spoken more    
1:54:49    
del more aware uh more more presenting a certain space for for c for things um    
1:54:56    
and what what what they were doing and I say this not presenting Trey as some    
1:55:01    
hard cold person not at all like everybody was on the same page at sort of the spiritual level was happening.    
1:55:07    
But it was just so interesting to see to get to get the differences in the room. It's very society ethics tech spirit of    
1:55:14    
get the different people who are like in very different domains that care about the same stuff in the same room. So I I    
1:55:21    
I I might have presented this a bit awkwardly, but like I think it was fantastic to to see that like like it's great to    
1:55:28    
see g get get people who don't talk all the same way because if you're in a room    
1:55:33    
full of like educators, your room full of uh idealistic tech startup folks, if you're learn room full of billionaires    
1:55:40    
or want to be billionaires, like the the tone, the conversations are all uh that    
1:55:45    
can kind of wash away into nothingness and like oh yeah, like this is how this we all talk this way and we all see the    
1:55:54    
problems the same way. I find it to be sometimes it's great to do that but but I really appreciate when when in an    
1:56:00    
effective way when in an interesting or let's uh uh meaningfully ways of of    
1:56:08    
indicating the the differences that each of the domain spaces are tending to solve. uh one that can be shown um    
1:56:17    
usefully and and and with substance to a viewer who is not who to a lay viewer.    
1:56:24    
Uh I think I think that's a huge that's like like a very rare thing to do well and I think it came across really well    
1:56:31    
here. Um Harry Gandhi's a teal fellow uh    
1:56:36    
which I was like okay what's that about? I mean I know what it is but like I didn't know what his approach was going to be. Um, and I I wish I got to spend    
1:56:43    
more time with them Sunday because there was a lot of folks had this great opportunity to have lunch with Harry and I I I kept trying to go to it. my travel    
1:56:50    
plans got delayed, but uh I I really want to catch up with Harriet because the way he spoke about things um he was    
1:56:57    
super aware of like community um you know he had a really nice set of    
1:57:04    
commentaries on like what does it take at a at a how do you    
1:57:12    
do the future of R&D? How do you make communities different? And it was very much not uh get to market and get your    
1:57:19    
moat, you know, like your technological mode, your your strategic advantages like that. That's obviously un that's I    
1:57:26    
think understood for everybody here. But there was this very interesting um    
1:57:31    
emphasis of um    
1:57:36    
what you know you you need money, you need clout, you need you need respectability, you need legitimacy. Uh    
1:57:43    
but you need community. Um you need you need there was a very o open inquiry of like what is it that we need to do    
1:57:51    
um to create the environments    
1:57:58    
that maybe will lead to actual breakthroughs. and and there was sort of across the whole panel there was sort of    
1:58:04    
this open open sense of not being beholden to any particular    
1:58:10    
structures which I found very um structures or establishments but also    
1:58:17    
um it wasn't willingly blue skies thinking either. It was it was it was it was    
1:58:22    
really nicely grounded in let's do things intentionally with some difference that aren't just willy-nilly.    
1:58:30    
Oh, let's magically do whatever and aren't just um    
1:58:35    
you know uh the only innovation that matters is the innovation of you    
1:58:40    
delivering profit at a lower cost to the delivering more profit to yourself by    
1:58:48    
lowering the cost of delivering value to to consumers. Like that is innovation.    
1:58:53    
And that's sort of my my intense juxtaposition of like there's parts of the world where like that is the    
1:58:59    
innovation that matters. It's like lower the cost and get more money and deliver    
1:59:05    
the value. And it's like yes, but uh there's also other things to do in in an    
1:59:10    
innovation sense in how we do it. I think it was well modeled here. Um Addie did a very nice job of stepping in quite    
1:59:17    
last minute. Um he represented Echolapto well. uh echolapto is uh in development    
1:59:25    
on many of what it's aiming to do and who it's supporting and how things are happening. So I think it was a nice    
1:59:31    
perspective of you know you're you know you're you can be a young person you can    
1:59:36    
be you can be striving to do these interiplinary interdisiplinary spaces and shout out to my forthcoming talk on    
1:59:44    
uh I don't know if I can easily share this here or not. Um    
1:59:50    
I am going to I'm going to do this. Uh I don't think you can can you see what I'm    
1:59:55    
sharing? What do you see on your screen right now? out of curiosity. Uh the LinkedIn app.    
2:00:00    
Okay. Uh    
2:00:09    
I'm going to tease this uh because this is incomplete uh and I don't like the    
2:00:14    
title at all. Um but basically, so what do you mean by interiplinary research? And what it's really going to be is like    
2:00:21    
um interdisciplinary, undisiplinary,    
2:00:26    
transdisciplinary, like what is this? And then sort of in a job presence, where do I think all this stuff should go? Uh yes, contextualize    
2:00:34    
in that we're in a very unique moment um in in in civilizational history in in    
2:00:40    
that context. But to go back to this to this proper, um, you know, Add's Edd's    
2:00:47    
part of why I'm a fan of what Echolto is doing is like there's sort of a a no holds barred. Let's put stuff on the    
2:00:53    
table. There's definitely a sort of a bias and interest in certain    
2:00:59    
like cognitive, biological, hormesis    
2:01:04    
stuff. And that's Add's personal bias. But they do they do try to um get other    
2:01:10    
things going on too. Um and then like I said, Samro Samro was a proper moderator. Uh but he did a good job of    
2:01:17    
sort of feeding around he did a very good job of setting things up. Like I was kind of impressed by Athos and I've    
2:01:22    
talked to them before and I've been to some I've been to one of their events and they've been really    
2:01:28    
um inviting like I could see myself wanting to do something like what Athos is doing long term or joining them or    
2:01:34    
something like that. So, shout out to to Samro for I don't know this I I I uh    
2:01:42    
I was very impressed at how much this didn't fit some of the things that I thought would be here. And even this is    
2:01:48    
sort of a I don't want to say progressive because it's not really a a a a it was legitimately actually R&D for    
2:01:56    
the future and what do we need to do like it didn't it didn't really feel like    
2:02:02    
uh many other things felt I don't think it was like supremely unique or like uh irreplaceable    
2:02:09    
but between this as I said between this and the first panel there's definitely an appreciation for like I say I say    
2:02:17    
somewhere I think in my in my my my full write up I say the only reason    
2:02:24    
like because you could easily do this event right without either panel like    
2:02:29    
you could you could take away both panels and say hey here's our our residency summit we have a couple keynups from the media lab um    
2:02:37    
that's great also there's a wonderful uh yeah this this slide I I'll I'll hide    
2:02:43    
this slide yeah a cause near and dear to my heart this is actually at the start with Duna doing the intro here.    
2:02:48    
Um, but there was a legitimate    
2:02:55    
actual inquiry like how do we how do we how do we want to do this philosophical yearnings like it was it was evident    
2:03:01    
that the construction particularly of the panels I would say was we want to    
2:03:06    
have these voices in here that are going to actually bring ethics and vision and    
2:03:12    
society into the discussion in a way that's not just sort of handwaving or not some oh yeah and here's our our our    
2:03:18    
keynote speaker at the very end of the day is going to talk about responsible AI which is which many events in Boston    
2:03:26    
here uh do. So it's nice to see see things handled much much uh much    
2:03:34    
differently and much more like we value we value this and we're we're going to make space for this. So we're going to    
2:03:39    
have this be a real part of the event and not just um a little add-on. So that    
2:03:45    
was that was quite cool. That was pretty much the whole the whole deal. Um I think I already mentioned um this this    
2:03:53    
was a really fun this is a fun moment. It was on the fly. It was I got I one of    
2:03:58    
my probably my biggest claim to influence influencer and somewhat uh    
2:04:03    
whatever um renegade academic fame is that I got I    
2:04:11    
handd delivered a coffee black coffee no sweetener to    
2:04:18    
Andre's and I got Kurt a bottle of water for an    
2:04:24    
vending machine when we couldn't find any order anywhere. So I I I    
2:04:30    
was like, "Oh, now you sponsored the event. That's great." So I was like, "Yes." Um I I helped sponsor the summit    
2:04:36    
and this amazing Theory of Everything with Courage Dangle podcast. And um    
2:04:43    
yeah, so that was fun. It was a fun day. And we all had lunch afterwards. We went to a local place and sat down. We're big    
2:04:49    
time nerds for another hour or so. It was a good time. It was a very fun weekend. Um, I'll I'll stop sharing my    
2:04:56    
screen. Um, and you know, thank you for the the whirlwind uh tour of it and any    
2:05:04    
any questions or comments I can try to get. I talked for a long time. Wow. Sorry.    
2:05:10    
Well, I I yeah, I I think I have the philosopher builder thing down.    
2:05:16    
asked about that, but it seems like they want to inject philosophy into building    
2:05:22    
or engineering or something.    
2:05:27    
Go ahead. Yeah, I'll say. So, but but then I also I was just kind of curious what Stephen Wolf talked    
2:05:33    
about at in the Q&A. Like not everything, but just like one uh one or    
2:05:38    
two takeaways. I didn't stay the whole time for it um for myself, but like    
2:05:46    
I'll give you the first few things that he he spoke about. One of them was he gave an intro to himself    
2:05:54    
and he like went through all the things that he did and he said immediately like, "Man, this is a terrible introduction because it was so long-    
2:06:02    
winded and and also like, yeah, I did this for a while and then I decided to do this." and he tried to give like a    
2:06:08    
very brief overview of his stuff. He also told this story of um I think in    
2:06:14    
like 1984 when he like something from the 80s when he was also working here like in Boston    
2:06:21    
across the street and saying yeah I was here for an event and I I forget which    
2:06:26    
what what thing he just released but a reporter he's even stayed at a hotel the reporter called him and said like hey uh    
2:06:33    
called him like four in the morning like hey can you give me a one-word summary for this thing uh for like what who you are Well, give    
2:06:40    
me a one more sentence for who you are, like what you're doing or one one sentence summary and it's at 4 in the    
2:06:45    
morning and he and he just goes like no and hangs up the phone and then he's like I from that point forward I never    
2:06:52    
like he always tried to make sure people would just go like call his room and stuff like that. So again, it was sort of this nice like it was cool because    
2:06:59    
like it's just so casual for him to drop like this from the 80s, this from the 90s, this from you know the long-term    
2:07:05    
perspective that I said at the start of my uh little review of things.    
2:07:10    
Um and then he he there was this big long waving discussion about    
2:07:18    
like the brain um and the mind. I'm trying to remember    
2:07:24    
a specific detail about it in the sense of there was a point he was getting to    
2:07:29    
uh but he went through this just like this history of like how we've thought about the brain. Obviously he mentioned    
2:07:35    
a little bit of like why did he do a new kind of science? What was he going with all that kind of stuff? And he he went    
2:07:42    
into um just like how how the mind and the brain in his mind uh kind of came to    
2:07:50    
be where we are today with them. What what to do with them head and the structures with them and kind of typical    
2:07:56    
uh neuro stuff. Uh but then he there    
2:08:01    
were a bunch of questions uh oh what is augmentation? Where do we start with augmentation? How do we do this stuff?    
2:08:07    
And I don't have a lot of great cool things to say about it. Uh because I I did leave um I stepped away for a good    
2:08:13    
while at that point to handle some of the things. Uh but I'm sure it was great and I think I I do want to go back. I'm    
2:08:20    
think I think they'll be I think everything's going to be recorded and I'm quite curious to see uh to see what    
2:08:27    
happened with that. I'm I'm sure Addie did a great job of facilitating    
2:08:32    
uh what was certainly a bunch of uh a full house still waiting to talk to to    
2:08:39    
Oh yeah, philosopher builder stuff. I mean, to be honest with you, like    
2:08:46    
I kind of wish there was a little bit more about saying    
2:08:52    
what what that meant to them because I didn't I've as an outsider like my only    
2:08:59    
really exposure to the augmentation lab was um I did some things at their    
2:09:04    
I was at an echoloto salon at at their h their hacker house in Cambridge uh    
2:09:10    
Harvard Street Commons I is like the formal title for whatever it was and a few other like adjacent things there.    
2:09:19    
But I didn't it it's it's quite clear that there's a    
2:09:24    
legitimate focus on essentially philosopher builder type things. But as an outsider, I wasn't like I'm really    
2:09:31    
curious. I don't know they have like a a developed um philosophy of it or like    
2:09:39    
like as in here's our principles we're advancing. Um I do know that their discord has a like a tech ethics    
2:09:45    
channel. I do know that it's clear that they they care about it but also like I    
2:09:51    
don't think I think I even actually I asked Da at one point in Discord like oh    
2:09:57    
like are you guys doing anything specifically here? And I didn't I didn't quite realize like that there    
2:10:03    
what what what what a what UGL lab does um or I should say maybe has done. It's    
2:10:09    
just like these like summertime threemonth hustle periods and they they haven't like built out a framework which    
2:10:16    
is maybe some of them more actually what Jobro is doing and that's kind of why I might look into doing more of them next    
2:10:22    
year. However, as a little bit of a I don't know preview and maybe even    
2:10:28    
Morgan knows about this. I think a lot of the folks are basically going to San Francisco and so the future of    
2:10:35    
aug lab in Cambridge is a bit open from my current understanding of it. I'm sure    
2:10:40    
there's there's there's a lot of critical mass here as in Boston Cambridge but uh to be determined. So    
2:10:48    
where to go back to the philosopher part um I don't think that there's a a    
2:10:55    
crystallized sense of what what it means for them to do it. It's interesting because philosopher builders also the    
2:11:01    
term like cosmos institute which I I some I talk about now and then like that's their term like we are the    
2:11:06    
academy for philosopher builders and it's like well you seem to be like that but you    
2:11:12    
seem mostly be talking about a lot of um classical western philosophy and making    
2:11:18    
tools around it like for mostly democratic purposes which I think is    
2:11:23    
great but like I think a lot of what I want to do like I want to make an essay contest I want to make some other things    
2:11:29    
that are uh I want to encourage Cosmos Institute    
2:11:35    
to stay in that lane and I have a wonderful I have a lot of like I don't think we don't have like we're not like    
2:11:41    
buddy buddy high-fiving bros on Twitter but like things that Bernie McCord posts    
2:11:48    
are things that I legitimately think people should be thinking about and I want Cosmos Institute to do what they're    
2:11:53    
doing and then essentially with Joe and some other stuff I want to basically I want Cosmos to stay in its own lane    
2:12:00    
and do what it is doing at Oxford. Uh because I think we need a group that is    
2:12:07    
taking the Oxford old school western philosophy folks and giving them an    
2:12:13    
on-ramp to hey give a damn about feature and AI and bring your ethics and and do    
2:12:18    
this. I think I think I think there's a need for that, but I think that's one lane in a multi-lane highway of    
2:12:25    
philosophy and being a philosopher builder and I think a lot of what umation    
2:12:31    
lab did as their take on philosopher builders is quite important and I want to add something to the mix through    
2:12:37    
jumpro specifically as well um and a lot of what we've talked about in like society ethics tech stuff but also like    
2:12:43    
legitimately centering some some other um voices approaches and so on. So,    
2:12:50    
yeah, like it's not it's not like uh come be a philosopher builder was really    
2:12:56    
the rally and cry. Maybe it was uh but I didn't I didn't really know that was going to be a main theme of the event.    
2:13:03    
Um and maybe I'm just ignorant. I was like foolish and misinformed about it.    
2:13:08    
But I do think it really came across well like it could have like you could have phrased this you could have had    
2:13:14    
this exact same conference which is quite cool. I think if you presented this conference as    
2:13:21    
philosophy builder conference summit or philosophy builder summit it really could have held the only    
2:13:27    
difference would be the projects and some of the exhib exhibitors and some of the things might be like slightly less I    
2:13:35    
don't know conventional Boston kind of biotech biohacker like it was a little bit of    
2:13:42    
like like augmentation it was legit like the exhibitors thems were augment ation focused specifically and not philosophy    
2:13:48    
builder focused. But like if you just swap that out like you could you could    
2:13:53    
you could you could basically make this a much more overtly uh philosophy    
2:13:59    
builder focus which is quite cool I think. So good job to them for that and I'll leave it at that. Yeah.    
2:14:07    
Yeah. I I would definitely like to stay in    
2:14:12    
touch in terms of I mean one um I'm I'm gonna follow up with you this weekend    
2:14:20    
just the the overview that you have. Um I'd really like to put you in touch with    
2:14:26    
Pedro. Yeah. And and you know use use some of that    
2:14:32    
for their own um Yeah. kind of summary. I mean, it was    
2:14:38    
that was just an awesome coverage of the event. Um, and    
2:14:44    
and to my best, Steve Bow's advice. But wait, that's not all. I'm like, I I would love to finish I    
2:14:51    
want to finish um my post and I would love to share it. I    
2:14:56    
want to get feedback and share it. So, like, yes, thank you. Because I put I put effort into that specifically like    
2:15:01    
like I want to cover this well because it's sort of it's kind of the coolest thing since Princeton and Vision honestly. like in the things that I care    
2:15:08    
about like it it was it was a great summary of all that synthesis of all that stuff. So yeah, please keep me in    
2:15:13    
touch um for that. Yeah, absolutely. Absolutely. and and    
2:15:18    
you know it's it's um I mean one of one of the reasons why I wanted to drop    
2:15:25    
everything and come for such a you know short event    
2:15:31    
is that the the mission statement that I was given    
2:15:38    
at Frontier Tower um if you read the the Neurotech it's like I don't know so    
2:15:46    
actually My my floor is called neuroscience tech and BCI but but the    
2:15:53    
actual description of it is much more you know augmentation    
2:16:00    
um yeah it's much more cognitive augmentation focused and and so it was    
2:16:09    
I mean I I I loved the philosopher builder part just because you know I'm a    
2:16:14    
Johnny I mean I'm a St. John's college guy. So, it's just like like jerk    
2:16:22    
that's that's that's at best the only way we can describe ourselves as graduates of St. John's. Um uh uh    
2:16:31    
but the the the mission was very very aligned with these these    
2:16:36    
the with what I was given and and like I    
2:16:42    
said like um I'm familiar with so many of these orgs that that that I've only    
2:16:48    
learned about recently but but I would like you know I'd like to engage with more and and you    
2:16:58    
So e ecalapto's one um you know 517 just    
2:17:04    
just gave you know has has funded funded some some stuff here for us. I' I'd    
2:17:12    
really like to talk more about 517 and Harry uh because I there they were sort    
2:17:18    
of the missing I I had really really really I heard about the the dinner with or the lunch    
2:17:25    
breakfast with Harry or something Sunday and I really wanted to go to it. Um and it was like so many things kept    
2:17:33    
happening that I didn't get to. So like that's like that was like the biggest miss for me was that.    
2:17:39    
So more about that later for sure. And yeah, like anything else on these topics that we can we can talk about.    
2:17:45    
Yeah. Yeah. And I I do I do see even even not knowing as much about Frontier Tower as    
2:17:50    
I could um but like knowing you and other stuff like I see    
2:17:56    
the not the roots but like I see where things can go and I'm excited about them and I and I hope you get to do what you    
2:18:02    
want to do there. Yeah. Yeah. Yeah. For sure. I mean, you know, as well as like, you know, what    
2:18:09    
are the issues? So, so Elliott Roth, who leads biotech,    
2:18:15    
uh floor, you know, was brought down to Prospera to to potentially build a bolab there.    
2:18:23    
And and so I can tell you both, you know, like like good things like that as    
2:18:29    
well as like, you know, they they had money to fly people like Ed Bordon down and things like that. At the same time,    
2:18:36    
like unfortunately nothing was eventually built there and and like like they had a huge number    
2:18:43    
of problems. Um, and you know to to your point as well,    
2:18:50    
which is something, you know, I'm surrounded by a bunch of    
2:18:56    
people who I'm not necessarily politically aligned with. Um but when    
2:19:04    
when it comes to the arguments around um what the special economic zone is    
2:19:11    
trying to you know trying to change societal incentives,    
2:19:18    
right? Yes. Um and and you know like I want to say more than just economic    
2:19:24    
incentives because again it was a lot like at least the arguments that I hear a lot about regulation,    
2:19:31    
right? Yes. and and you know and again it's like    
2:19:37    
it's one of these times where I think I think what philosophy brings    
2:19:46    
is not the ethics um but is actually the appreciation    
2:19:55    
of complexity and um and uh um our interconnectedness    
2:20:06    
u you know against this this like    
2:20:12    
if if things are just cheaper if there are less rules that like yes magic will occur    
2:20:19    
right it doesn't and there's a sort of I actually think and part of what I'm    
2:20:25    
trying to write write more about in a very particular sense I think good philosophy in that sense particularly in    
2:20:32    
the context you just said. I think good philosophy, good ethics is actually being really sober like actually    
2:20:40    
connecting hey like you you said well like bringing real complexity as opposed    
2:20:46    
to geez here's some existing metrics that are empirically like we can    
2:20:51    
calculate that. Excuse me. We can calculate that. So let's do it    
2:20:56    
man. Like we like let's just optimize these talle variables. you got it. You know what I mean?    
2:21:01    
like we I think I think philosophy when it's done really well    
2:21:08    
um in in an applied context illuminates    
2:21:13    
the and I'm I'm borrowing language from something entirely else um that I not    
2:21:18    
related to this but um it will bring the latent the hidden the the nonobvious    
2:21:26    
things to the front and at its best when it's handled the right way will force force people to deal with the agency and    
2:21:35    
recognize the choice and the problem space. When you put pressure on the    
2:21:41    
choices and the problem space and articulating them and not just dry manning or or trickling it down into    
2:21:48    
well that's all great but here's this number that we need to care about. I    
2:21:53    
think that's a very um I agree with that very much. Yeah. Yeah. Yeah. So anyway, I just wanted to,    
2:22:01    
you know, say like like, yeah, thank you so much for the overview. You know, I    
2:22:08    
wish I wish I'd been there, but you you gave me a a great um um you know,    
2:22:13    
surrogate experience and and like    
2:22:20    
yeah, I I think there's there's a lot of of value. um    
2:22:29    
to to be found in in really engaging with these groups, you know. So um uh    
2:22:38    
like like Yeah. So I I I'm still love to strategize just about how best to do    
2:22:44    
that. Absolutely. Well, that's like that's becoming like an increasing focus    
2:22:49    
of of what I'm trying to do both like the practical and then I actually want to do really shortorthhand. I want to go    
2:22:58    
do a PhD in some of this. I don't think it really exists. I don't know that I want to make a PhD. I don't even want to    
2:23:04    
go through the process of finding a school institution interiplinary making but like there's rigor and development    
2:23:12    
of how does one like I want to get at the theory of how we do this stuff no less and that's important but like it's    
2:23:19    
just as important that the the the literally engaging like that's all nice    
2:23:25    
I want to do both I want to do the the the broader high level vision strategy because I think that's I think that's so    
2:23:30    
missing right now like like I didn't say this but like the The imaginary conference that I talked about has the    
2:23:37    
the other component is how do you synthetically decide synthes    
2:23:42    
synthesis that we talk about here and strategy like what do you what do you do    
2:23:48    
like where do you try to go at at like the actual broader level plus all the    
2:23:54    
all the nitty-gritty stuff that we're talking about here. Um, so more about that later, but like yeah, please let's    
2:23:59    
talk about this and and do stuff like there's stuff here like I feel like okay like you there's sort of the San    
2:24:05    
Francisco forever Silicon Valley stuff Bay Area and I I know what was so good    
2:24:12    
about this commerce for me is that it surfaced a lot of the contacts I'd really like to have here even if a lot    
2:24:18    
of them are going to San Francisco. it just like I got I got a little better foothold in the real a real a real value    
2:24:24    
a community of value to me here. So I'm happy to do more in those spaces. Yeah. Yeah. Well, and like I said, like    
2:24:31    
the good thing being that or sorry, the good thing being that they're coming here and and so    
2:24:40    
um yeah, let's let's let's try and um let's    
2:24:47    
try and use all that um energy and and excitement um to, you know, um find find    
2:24:56    
some projects or find some um are, you know, um, set set some topics    
2:25:03    
to be to be discussed and and, um, and fleshed out because, yeah,    
2:25:10    
the other thing that Frontier Tower has has given me experience with is really    
2:25:17    
opening up the number or, you know, getting to meet and greet with all the    
2:25:24    
the hacker houses, right? and and and you know kind of um associated    
2:25:31    
communities. Now you know some of these aren't as    
2:25:37    
some some are are connected to more established organizations like    
2:25:43    
Nucleate for instance, right? Which is which is a you know kind of um    
2:25:49    
I I see some overlap between Neurotch X and Nucleate except like Nucleate being for biotech you know.    
2:25:55    
Yeah. Um uh um    
2:26:00    
but again yeah it's like like would like to think and talk more about how best to    
2:26:07    
how best to engage with these groups and like it's it's yeah the kinds of things    
2:26:14    
that they would be interested in building projects around you know that    
2:26:19    
would be of interest. Absolutely. And I appreciate talk about that. I realize Bradley probably wants to go.    
2:26:25    
Yeah, definitely stuff. So, yeah. All right. Uh, so that's all for today.    
2:26:33    
Thanks for the discussion on on this stuff. Thanks, Jesse, for presenting and see you next week.    
2:26:40    
All right. Thank you everybody. The breast of ear.    
    
