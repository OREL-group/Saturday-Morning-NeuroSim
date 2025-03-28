## Meeting Recording

[YouTube link](https://youtu.be/epSPCnKghR4?si=Waz8nI4YFPi6g9gQ)

## Mastodon thread

[link](https://neuromatch.social/@OREL/112425524247441924)

## NOTES
Sarrah — resources (on ABMs-LLMs).

Jesse — open-source infrastructure.

Jen — onboarding materials.


Resources on Notion (for DevoWorm and OREL).

* 5-minute video from the open house collection (start guide).

Open House 2022. GSoC contributors — GSoC open-source scholar. Open-source development scholar. GSoC development team.

* scholars program — NYCWiC — startup experience (Jen’s help). Jen Jiang (project management, Psychiatry).

Inclusive gaming — how to start a career in AAA+?

* intentional discussions — Deploy or Die?


How to document conference (connection you can draw upon later). Different strands, different people.

* outcome Paola is looking for. Labels are metadata, card would generate data itself (Markup — XML). 

* passed by language model. Moving towards LLM queries — facilitate NeuroGPT.

* don’t separate model from text programming. Model cards — to model write-up. Literate programming style.


LaTex —> generates raw HTML, link to model cards as XML. Easiest way to generate this automatically.

* sociotechnical not just a technical analysis.


Military recognized this in software engineering best practices.

* GSoC documentation. Reading Neuro paper does not give access to model and data.

* computer has access too full stack. Automated lab driving.


Neuroscience data is a mess. How well can human brains learn from a very small number of samples (Organoid Intelligence) vs. how many games of Go do you need to search to beat humans.

Big Brain Dataset (estimates of brain samples). Multiple datasets need to be linked.

Meeting in 2017-18: NeuralStorm (https://neuroengineering.ucdavis.edu/nsf-training-program-neuralstorm).

Blue Brain project — software contributions. Active Learning — tries to get at organoid intelligence.


Python script for analysis, model cards.

* pie charts with percentages — subcluster ID and content. Hierarchical Clustering.

* click on supercluster to ID (from business intelligence). Power BI software. Data tree, mind map (visualization).

* superclusters have a name and integer value.


Model Cards — set of slots, denote values used by AI.


Read, tells you what is in the model.

* Huggingface —> model cards collections (Example: https://huggingface.co/lisali126/hf-hub-modelcards-pr-test). 

* don’t need to write things out in XML.


Structure has to be reflected in the model card.

* Lennarsson lab, clustering (UMAP). Nonlinear projection.


Improve via in silico techniques. SynBioBeta — pipelines are not incredibly productive.


Hussain Ather
Hussain Ather says:
Hi 
9:01

Sarrah Bastawala
Sarrah Bastawala says:
Hello ! 
9:01

Himanshu
Himanshu says:
Yeah! 
Himanshu says:
Me and Hussain, yes 
9:07

Shubham Soni
Shubham Soni says:
Is the cohort going to work parallel to gsoc? 
9:09

Hussain Ather
Hussain Ather says:
Absolutely 
Hussain Ather says:
Thanks jesse 
9:22

Himanshu
Himanshu says:
Great opportunity! 
9:22

Jes (OREL)
Jes (OREL) says:
For later: I found an old draft on "beyond demo/deploy or die"  - about a culture of open communication 
9:25

Paola Di Maio
Paola Di Maio says:
hi 
9:35

Jes (OREL)
Jes (OREL) says:
Google Summer of Code is a fairly structured program which had its project selection much earlier this year. So it wont' be a part of "this years" GSoC per se, but, it could be an open source project that the lab looks to develop outside of GSoC 
10:02

Paola Di Maio
Paola Di Maio says:
thanks 
10:02

Jes (OREL)
Jes (OREL) says:
That said, I think it woudl be great to see basically a "call for involvement" or a project proposal written up (or a video going through things sort of like here) , and that way it could be mentioned or help recruited for it when available. 
Jes (OREL) says:
Morgan I'd be curious to see what (oxford?) models and latex you're referencing 
10:09

Morgan Hough
Morgan Hough says:
Sweave 
10:12

Jes (OREL)
Jes (OREL) says:
like this? 
https://stat.ethz.ch/R-manual/R-devel/library/utils/doc/Sweave.pdf
 
10:13

Paola Di Maio
Paola Di Maio says:
thanks 
10:16

Jes (OREL)
Jes (OREL) says:
(documentation is important for GSoC too 😉 ) 
10:21

Paola Di Maio
Paola Di Maio says:
yes, if you can access the paper please share it I could only access the preprint 
Paola Di Maio says:
thanks 
Paola Di Maio says:
thanks I have just signed up to this complexity digest 
10:51

Jes (OREL)
Jes (OREL) says:
👍 

## TRANSCRIPT
0:01     
h no good morning     
0:10     
morning Morgan and     
0:16     
Hussein and Sara     
0:21     
hello hi looks like yeah hello     
0:30     
looks like we're uh we can start and other people will probably join     
0:36     
us in a little bit so welcome to the meeting this     
0:41     
week um hope everyone is doing well this is the first week of G so hope     
0:48     
everyone's been doing well with their Community bonding like I said it's just a period where you get to know your or     
0:55     
you have some resources to go through I talked about some resources last week     
1:01     
and you know we're also doing things with getting projects up and running so all of that is kind know going on should     
1:09     
be going on and you know we'll try to help you out if you need     
1:14     
resources but um you know that's that's something that you should be reaching     
1:20     
out to people on the orb you should be getting a sense of what the orb is doing in the area of your interest and how you     
1:27     
can leverage the orb to help you so if you have any questions let myself     
1:32     
or Jesse know also if you U are in the dorm group hamu can help as     
1:41     
well okay uh so we didn't really have any meetings this week we didn't have a diva     
1:48     
War meeting we didn't have a cognition Futures meeting we didn't have a     
1:53     
cybernetics meeting and that was partially because I I was busy this week with things I didn't time for any of     
2:01     
those so uh Diva worm will be continue this coming week we'll have a meeting we     
2:08     
cover some topics um I'm going to cover the thing I was doing last week in that meeting uh I     
2:14     
also want to go over some Community uh period stuff for the DOR people and then     
2:21     
our uh cognition Futures and our cybernetics group probably do the     
2:26     
cognition Futures group this week and maybe the cybernetic scle movie to this week     
2:33     
so and then oh of course Friday we'll start our open source meetings so this     
2:39     
is something we've been waiting on yeah uh so yeah this is yeah Jesse     
2:48     
just I think made an announcement in the slack uh the open source meetings so     
2:53     
they're at noon eastern time in North America and you know we we do like     
2:58     
usually once a week so this coming week you know it'll be a community bonding     
3:04     
period uh you know I guess you don't really have if you're Sara uh you don't     
3:11     
have to give an update um this week but you have to kind of think about the     
3:17     
community maybe questions you've had from the community perod and then two     
3:25     
yeah and then two other people that we have uh ad dama and shom are also kind     
3:32     
of doing open- Source development and they'll be try well hopefully they'll join us as well and we can talk about     
3:38     
some things to get started there too so oh go ahead yeah I just this week     
3:48     
uh so I was just I mean I I know you said I don't have to give an update I start I update you little bit so uh most     
3:54     
for most of this week I just I was so there were the last time when I gave my presentation     
4:00     
uh there were a few resources that were dropped in the chat links to a few paps     
4:06     
and most of them were based on the prior approaches uh especially RL based approaches so I this week I just tried     
4:13     
to read through them to kind of like since I don't have an arel background kind of understand what has been done     
4:20     
before and hopefully next week like as you said maybe even talking with Adama     
4:26     
and Sham uh like can start focusing more in new     
4:34     
approach yeah yeah that would be good um yeah I don't know if you like uh on     
4:42     
Friday if you want to kind of go quickly over some of the things you've been reading through for the rest of us just     
4:47     
so we can see I'm gonna try to do some yeah yeah next     
4:55     
next I'm going to try to go over some material like some introductory open source materials we do it every year but     
5:03     
it's always useful to people to see um some things about open source     
5:08     
development and that so and yeah hansu as well join us and     
5:14     
Jesse on the open source meeting this Friday so and you know I I I think Jesse     
5:20     
mentioned it once in the channel we'll reup the announcement closer to the meeting     
5:26     
yeah I know he's he's been in them before cuz was in I think uh the year before last or something like     
5:33     
that and so we'll do the diva worm stuff separately from this like during the D     
5:39     
meetings we'll talk about open their uh project updates and you know it'll be     
5:45     
separate yeah and so you know the reason I want to do that is because uh D.A worm     
5:51     
is a different community and they're you know getting insights from different people and it's you know it's a     
5:58     
different kind of uh it's more tailored to their project so but if you're um if you are in evoor     
6:07     
and you want to attend the meeting you're welcome to do so it's not     
6:12     
closed okay so thank you for the update s um I don't know Jesse did you want to     
6:18     
talk a little bit about the open source stuff as I know you had to we had had some questions floting around about     
6:27     
it um let me see if I can show anything about it basically there's we're doing     
6:32     
we're doing some work Jen Jen has been helping with some like on boarding materials and I basically want to make     
6:41     
a like can be a website but it basically be a notion page um that's just public     
6:47     
and it will sort of be like the go like like the actual Center like I can should     
6:53     
be show a slight preview of it now um isn't this isn't the final version of it     
6:59     
but um just to just to tease it     
7:05     
um here here it is um but basically this I think is it is it coming through now     
7:11     
yes yes um but basically kind of like a you know     
7:18     
a thing that's going to have a lot of stuff on it like announcements and some of the facts we're going through here     
7:23     
just putting questions here um and also like these resources like I actually I went through some of the YouTube     
7:30     
um both the diva worm Channel which now is Diva worm Channel which um uh and and     
7:37     
the um aagal Channel and there's a lot of good stuff there I put I believe I put     
7:43     
in the chat um uh well in in the in the let me show     
7:50     
this here um     
7:55     
yeah I put in the the Google Su code um CH slack     
8:03     
channel uh with just something from like like I think this is like a five minute     
8:08     
video that Bradley made for the open house but just sort of like a very broad gck for Education advocacy and community     
8:16     
building it was a sort of nice we have a lot of nice old content in there that is like worth looking at so I might I have     
8:24     
like a start just like a like a checklist or a start guide to go through that I'm working on and I want I'll get     
8:29     
Bradley's feedback on it maybe we can have it ready for like next next Friday just so everybody's like okay I have all the things I you know I'm in slack and     
8:37     
I'm here and so on and so forth I'm just to kind of go through all that stuff     
8:42     
um and there's also like a lot of like I don't think any of read like I don't think we're going to make mandatory     
8:48     
reading any like looking at any of these old videos but there's just a lot of like really nice context from from what     
8:54     
what what's been happening in the past too that is like some of it's not not buried at all but some of it is is like     
8:59     
very deep um in the archives of like YouTube videos and stuff so um I'm really glad it feels like we just did     
9:06     
the open house to 2022 like yesterday but it's it's almost like a year and a half two years ago right right and you     
9:14     
know some things are obviously different since then but but a lot of it still carries over um I saw something is the     
9:22     
cohort going to work parallel to to G yes um I I thought at least I I'll theer     
9:29     
to in the final safe for all these things but like uh some of this week has been figuring out what to call     
9:34     
everything and I think I think I think because because we've been doing this for a while but I feel like we haven't had the best names for it so we have     
9:40     
like the g-o contributors who are like the people who got very few slots     
9:46     
available um and I think we're going to settle on basically the open source Dev     
9:52     
team uh and sort of the name because that's what we have like what are what are what what are like the orthogonal     
9:58     
people who have been doing this for a while and and you not everybody has had the funding but we from Google directly     
10:04     
but they've been part of this thing so the dev team itself is like uh just our     
10:10     
open source Dev development practices so I think we might use the term open source like Dev Dev team or open source     
10:18     
Dev team scholar to just sort of just just just to differentiate you know is basically did     
10:24     
you were you was there enough slots to give you or not basically was I would     
10:29     
rly clarify that but for me it's like you know if we had enough slots from incf and from Google we just give them     
10:36     
everybody um but the whole thing itself is the cohort and everybody's in the same cohort together so yes it's all     
10:42     
parallel uh you know the requirements may be different for reporting for if you're have to report to Google or not     
10:49     
but like you can come to the meetings you can look in the project you can talk we encourage you to talk to people the     
10:54     
past people in the projects the current people in the projects the mentors we have a really nice community of mentors     
10:59     
like himan is herein has had a lot of experience in some of the project spaces     
11:05     
um and obviously Brad's been here from the beginning and and I'm I've been here     
11:11     
for a while and and you know I think I think Morgan even comes open source meeting sometimes and Morgan like just     
11:17     
you know lot of stuff so like this this is a great community and I think calling it     
11:22     
The cohort is sort of this inclusive everything that's actually happening and that's sort of the language that I'm     
11:28     
going to start trying to um and start implementing like even like     
11:33     
I'm doing a bit more on LinkedIn too and and one of I guess one of the other things I wanted to say is like I we     
11:40     
we've been doing like professional well first I want to mention professional development stuff but then I'm Bradly I said a bunch of stuff and you should you     
11:47     
know confirm or deny that that sound to oh yeah as for that yeah that's pretty much the case which we've been talking     
11:54     
about so you know we're thinking of this as a team effort on one level we have     
12:00     
you know part of the experience of someone of code of course is learning how to run a project manage project     
12:08     
manage a project and have something tangible at the other end then there's this open source aspect which is you     
12:15     
know what are the practices and wores of Open Source how do you get something out     
12:20     
into the world and license it and all this and then the third part is this uh     
12:26     
aspect of teamwork or working on a team because practically speaking you'll always be doing something with a team     
12:34     
even if it's just managing Forks if you had your own project you just did it yourself you still have people who Fork     
12:41     
it you still have a community of people who use it so you have to manage a team in some way and that's kind of the     
12:48     
meetings that we'll do on Fridays is we'll talk about different aspects of that you know we'll     
12:53     
have I I'll do features every week about different things like you know they     
12:58     
there you know different practical things that we needed to keep in mind um     
13:04     
there are other types of career opportunities Jess's done a lot of really nice discussions on kind of     
13:11     
topics that he's encountered in his career where you know he's trying to work with a team or you know there's     
13:17     
some problem with um you know human relations or management or     
13:24     
something that you wouldn't think of sort of coming in you know it's just     
13:29     
like these things that crop up and things that seem to happen on teams and no one has a really good answer to so     
13:36     
those are all things that we we going to do so you know if you're uh have you     
13:41     
have been selected by Google you know your title is something like Google summer code scholar or something like     
13:48     
that and then if you're not been selected by Google but you applied uh to the to the program to the     
13:56     
projects then you are like an open source development scholar so there's a scholarship aspect of it and you know     
14:03     
it's just you know you get the official sort of Google summer code stamp but     
14:09     
you're you're basically doing similar things you're in the org as a scholar so     
14:15     
you're working on open source sort of the project but you're also thinking about the larger world of Open     
14:23     
Source that's that's what we're trying to get at their experiential part of     
14:28     
this yeah um I I think it's actually been the last last two     
14:35     
years um I really like where it's it's     
14:41     
gone because I think it's been a little bit more of a holistic take on on everything and I     
14:49     
I've like I have way more experience now um I don't I don't have like a     
14:54     
tremendous amount of software development experience in terms of making software products but I have a     
15:01     
tremendous amount of experience now working with people who are making the software and also working people doing     
15:08     
the hardware and getting those products to Market like that's part of what I do um and and constantly meetings about in     
15:15     
my day job um and and looking at Technologies and how to like get Technologies to talk     
15:21     
to each other and stuff like that so that's that's been really cool for me to see but also like one of the biggest     
15:27     
things and I I this is kind of why I keep mentioning like Nick Wick and New York celebration of women Computing in     
15:32     
that conference is that conference is geared towards     
15:39     
um uh early career folks who are having their first conference or having their     
15:45     
first um academic or speaking experience or how do you communicate in this firm how     
15:51     
do you communicate what you're doing to people in all idea what you're talking about kind of stuff um or or well I mean     
15:57     
that's one thing but in the conference a bit more you are talking to a select group of like uh computer science type     
16:04     
people um but but from that experience to I think and and or El's our history     
16:12     
with that event we've been with that event I think for almost five years now um in different forms we didn't present     
16:19     
this year but I was involved and and so between that and then this     
16:25     
summer uh the summer cohort um we've really gotten to a place where I think     
16:31     
we're having really meaningful uh meetings that have both project updates     
16:37     
and we'll talk about your technical stuff and where you are in the project where you Rel to your goal what you want to do but then also we'll slip in these     
16:43     
things about um profession development commun like how do you communicate one one of the topics last year was like     
16:50     
giving and receiving feedback at work you know or like addressing um like how how to sort of     
16:56     
differentiate you know expectations and and what do and and you know how to you     
17:01     
tell if you're kind of being maybe asked for too much or um like like different     
17:06     
startup like different startup kind of experiences and just being able to talk about that in an open way I think it's been really useful so the I think that     
17:15     
that's pretty much what I wanted to say and one more thing to the end is like I think this year with with Jen's help uh     
17:22     
for some of the onboarding and communicating stuff and then largest experience with Bradley and everybody     
17:28     
else like a lot of people who are here today right now and people who will be showing up in Fridays um I think there's     
17:35     
also a one thing I I would like to push a little bit more forward this summer is     
17:41     
sort of very like even more     
17:48     
um not exactly portfolio building but getting like getting to the next level     
17:56     
of how to communicate or share your work like what I've ended up unintentionally     
18:02     
doing a whole bunch of stuff on LinkedIn recently for various groups um and including our group like including athal     
18:09     
group and I'm not I'm not saying everybody has to be LinkedIn doing a bunch of Social Media stuff I don't particularly I'm agnostic about that but     
18:19     
um like both I think there's a little bit more I want to focus on in terms of     
18:24     
communicating to others and then like finding jobs     
18:30     
in the 2020s like this year like how you do that and how you show up in spaces     
18:38     
that are relevant to actually finding jobs and and people in Job searches in     
18:44     
my life I have people who are want to be looking for jobs I have I just went through the     
18:50     
um uh if I can show this quickly yeah uh I just had I just had a     
18:57     
great talk I know here's in in going to be in uh gaming and gaming is kind of     
19:02     
its own thing but um uh I just was at this this event     
19:08     
inclusive gaming conference at Oxford and um this person     
19:15     
uh lieta uh is just gave like a fresh     
19:21     
Insight of like what is it like to try to get into gaming which is tough to get into right now but her insights are like     
19:26     
how you find jobs and our jobs posted or not had a network um really mirror a lot     
19:32     
of what I've been experiencing from um like I've been to a bunch of events     
19:38     
here in Boston lately too that are like you know this is this is big you know this is Health tech and and clinical Ai     
19:44     
and all this other stuff so it's just like I feel like okay um there's a lot     
19:49     
there that I want to talk about and for those who don't know I'm like I have a small organization I'm developing that     
19:56     
does like early career mentor as part of its like a main focus so I'm kind of dub     
20:02     
tailing from that too and I think there's just a lot of to kind of pull it back to this um I think I think there's     
20:08     
a lot of like skills um that are really tangible that aren't going to be covered in um like     
20:16     
the the main Google summer code curriculum but that we at orthogonal lab     
20:22     
um have been thinking about for a very very long time uh like one of our main banners was like education Banner like     
20:28     
how we're teaching in pedology and so not just teaching in how we're teaching     
20:33     
like technical material or academic material but now I'll kind of really bring it     
20:39     
into um you know the professional development stuff like stuff you're     
20:44     
actually going to be using um to navigate your your work experiences so I look forward to that and um if anybody     
20:52     
wants to like like Hussein I know like Hussein has a whole bunch of experience in in dealing with a lot of these things     
20:59     
um and hum has been around the block on on these topics too like if people want to like contribute or want to like have     
21:06     
a talk or present something of that nature at these meetings too like I really encourage that because I know     
21:12     
there's a lot of um solid experience here so I'll let it be for now but looking     
21:21     
forward to that yeah sure yeah that's great Jesse um     
21:31     
yeah so yeah that's that's yeah it's a great thing we'll we'll we'll start     
21:37     
doing that this Friday like I said that'll be a good opportunity to     
21:43     
you know pick up what we left up last year because last year you know we did this uh I think the year before we did     
21:50     
this too but like we we really kind of get our stad last year having different features and things like that and really     
21:56     
putting some value into it you know yeah and and like what we didn't what I didn't get to do last year     
22:02     
was like not as say make a blog post for each of the topics but like demarcate okay we're talking about expectations     
22:08     
we're talking about uh how to give and take feedback we're talking about you know so I think I want to try a little     
22:14     
bit I think I'll have a little more help to do that this year and that way even getting like maybe more intentional     
22:20     
discussions or just just you know um opportunities to talk about that constructively too I one a similar thing     
22:28     
like I don't think this year Google Google summer code is requiring there's     
22:33     
sort like that Weekly blog post thing for a while I don't think there's anything like that this year um there's     
22:38     
like reports but not like the updates and I I I guess um I want to reemphasize     
22:47     
that like we do I think we do encourage like a beginning and an ending presentation specifically yeah but also     
22:54     
like if you are looking for and this is like hint hint should be but if you are     
23:00     
looking for opportunities to like write a small blog post about what's happening     
23:06     
or to write some something I don't really blog post is sort of a catch-all term for this but if you're looking for     
23:12     
experience on how to write about what you're doing you can do that here and also like ask us for help to do it     
23:20     
because we are open to that and like that's a communicating what you're doing not going to go full demo or die     
23:28     
right now um or deploy our di which is something we've talked a lot about in the past and     
23:33     
I have I'll say one more thing about that later too but but just like getting used     
23:40     
to communicating what's happening um is something I think will be a great asset     
23:46     
to you so yeah that's it all right yeah     
23:51     
thank you Jesse um so are there any other updates before we move on other     
23:57     
things     
24:04     
okay uh so I wanted to actually highlight something here this is Jesse you know he prepared     
24:13     
this we talked about this last week so this is his uh this is the     
24:20     
medium for the lab so if you're interested in posting a blog post on your updates on your project I think     
24:27     
everyone is presenting their projects in the meetings more or less so you know if     
24:32     
you want to present on it um you can but uh you know we can also write a blog     
24:38     
post on your experience or on some of your plans and so we can publish it here     
24:43     
this is medium.com Aral group so we publish I think I showed this last week     
24:49     
we publish on this uh sporadically we don't really have a schedule when things     
24:54     
go up but you know we've been trying to keep it up every month or so a new post     
25:00     
so this is Jesse's summary of the MIT experience uh MIT times MGB which is     
25:07     
Massachusetts General Brigham AI curers we talked about this I think two weeks     
25:12     
ago and this is just you know his summary of this conference where he talks about some of the aspects of this     
25:19     
conference um you know the sponsors uh what kinds of takeaways he     
25:25     
got so you know we we don't usually we attend meetings or conferences and it's     
25:32     
pretty overwhelming a lot of times you get a lot of information you experience     
25:38     
new things but if you don't sit down and reflect on it then you know it kind of gets lost so I encourage people who go     
25:44     
to events like that to do something like this it's always useful uh so he you know he gave some     
25:51     
quotes in here things that people talked about that stuck with him and then his     
25:57     
takeaways from the event which are one there will be no slowing down Health AI two is first mover bias which is     
26:05     
basically if you're a firm you take the first move you can shape the market     
26:10     
three priorities Theory and choices uh this is kind of linking into     
26:16     
Data fairness and ethics for synthetic data and generative     
26:21     
visualizations five sensors and automated data so you can see that he's kind of putting his takeaways down and     
26:27     
then the rest of and read about it and think about it as well as other people in the world so if     
26:33     
you're interested in doing that thank you Jesse for putting this together but if you're interested in doing something     
26:39     
like that or you know an update on your project you're welcome to do so I think     
26:45     
it's a good experience or or if you attend event if there's a local thing even at your University like oh I was at     
26:51     
you know um some you know tech tech event or a topical event it's it's     
26:57     
pretty wide ranging like that that my commentary there was pretty General but     
27:02     
I did it mostly to have make an artifact that I can reference later and I realized that's that's a key thing to do     
27:09     
also I can't figure out medium isn't letting me like I tried resizing my image a bunch of times and medium is     
27:15     
only doing like fullsize images for me yeah and I'm tried to figure out how to weigh around that but it's just it's a     
27:21     
little looks a little hokey for me but hopefully that'll change     
27:29     
um but yeah like doing that and there's actually I I I really think it's a great     
27:36     
idea to try to document conference because it's really hard to do in a way that feels right at least at least for     
27:42     
me like I don't that was an easier one because it was simple and I only engaged the material of the conference at a     
27:48     
certain level and it was it wasn't I wasn't diving into like the deaths of clinical Ai and and and some of the like     
27:56     
a lot of Imaging stuff that was happening there I just spoke you know very specifically about it um but I had     
28:03     
one for some other events in April April's been a huge just event stream     
28:09     
and then May 1 was the inclusive gaming conference which has been huge huge huge     
28:15     
huge in many fronts and I'm writing a very long piece about that um and I'll     
28:20     
put that on the medium too eventually but also like sometimes it's great to just     
28:25     
make like the particularly the the inclusive gaming conference piece is going to have a lot of     
28:31     
Concepts and a lot of things that we did for plot fishes but also just these sort     
28:37     
of connections that you can draw upon later like H the compared to the     
28:44     
clinical AI one that I that we just saw that's a bit more General I'm like okay     
28:50     
here's a there's not a lot of in it like admittedly there's not like a lot of like amazing things in that but it's     
28:56     
okay to do that and just get you to writing about that your ideas that way too the inclusive gaming one though will     
29:03     
definitely be something that weaves together many many many strands of     
29:08     
interest in different people and I feel like that's its own art form too so     
29:16     
um yeah we definitely encourage you to submit things to it or if you want even if it's like geez I I don't have a lot     
29:23     
of experience writing for like public kind of things and I'm working on this project where I found this thing     
29:28     
interesting um can you help me set up a medium post yeah we can we can do that     
29:35     
you can ask about that too yeah and this is one way that we kind of new people     
29:40     
coming into the group or sometimes people kind of getting their foot in the     
29:46     
door on a new topic is encourage people to write a blog post and then maybe do     
29:51     
it order do a presentation and then maybe do something more substantial later maybe devel Vel an artifact or     
29:59     
publish a paper or something so it's part of that that pipeline it's sort of     
30:05     
the front door of that pipeline where you kind of get your feet wet you say I'm just going to get some ideas     
30:11     
straight uh out of my head into something that people can access and     
30:16     
give feedback on because you know if it's all in your head it's hard to for people to give you feedback you know     
30:23     
being able to clarify your thoughts or you know things like where you're at a conference and you have some insights     
30:30     
you know it's sometimes if you wait too long or if you just kind of don't make any uh create any     
30:38     
artifacts you know can be lost and it's hard to really recall what the insights     
30:43     
were what the takeways it yeah that's great thank you um yeah     
30:52     
I'm just looking through the chat here I think we've answered everything in the chat     
31:00     
so uh another thing that we've got here is um I didn't want to talk about data     
31:06     
and open data a little bit so for our projects um we     
31:12     
have some opportunities you know to work with data and our group doesn't     
31:18     
generally generate our own data but we do use a lot of open data and secondary data sets and there's a lot of stuff     
31:25     
available on the web so you know uh like for example if you attend neurom match     
31:31     
this summer they have data sets that have been validated and if you're     
31:36     
interested in doing stuff with neurom match they have these data sets that are pre-prepared and and something you can     
31:43     
just pick up and start working with through a a Jupiter notebook or collab     
31:50     
notebook so you can just like you know the the data set is there it's been processed you just send some commands     
31:56     
you do some analysis you can get some insights um we also do things with     
32:02     
collecting secondary data sets so there are a lot of uh repositories of secondary data in the biological     
32:10     
sciences and the social sciences and in other areas and that's a little trickier because you have to assess the quality     
32:17     
of the data set then you have to put them together so you might take like three data sets kind of merge the data     
32:25     
together and make sure that it's you know it it's it's uh everything that     
32:30     
you're making comparisons with are valid and then you can produce uh an analysis     
32:36     
so we can do that we can do different types of secondary data analysis we can also train machine learning models so we     
32:43     
have especially in the DOR group we have a lot of data sets that we reference     
32:48     
either they're microscopy data sets or they are you know some sort of data that     
32:54     
is uh numeric that you can train a model with and so that's you know something that I     
33:00     
know Sara with a large language models might have to fine-tune the model also the models kind of you know sometimes     
33:07     
they're pre-trained and you have to be aware of some of the ways in which they're pre-trained so we have we have     
33:13     
to think about data a lot and we have you know access to different data sets     
33:19     
so if we're doing any projects and we need data you know we can get data we also of course have the neuroimaging     
33:26     
data that's available one Morgan is really good at like picking that out and     
33:31     
he's worked with a lot of neuroimaging data sets so that's another resource we have so you know that's so we have these     
33:39     
three buckets the sort of the machine learning aspect sort of the secondary data aspect and then some of the other     
33:47     
uh things where we would like to integrate the data together so uh in keeping with that uh     
33:55     
Powell has been discussing in the slack about this data set that she's found     
34:00     
from the Allen Institute and she wants to work on in terms of getting some visualizations out of the data so I'm     
34:08     
going to show some uh examples here from the data or from the slack so I'm going     
34:13     
to go to the general Channel and I'm going to show a couple of examples here so she's putting these     
34:21     
transcripts in the uh slack channel so she had this discussion here uh hello     
34:29     
I'm a bit early for today's meeting I'm a little bit tired uh so there's this visualization     
34:36     
collaboration there's a data set I have it open in um in a in a tab that I'm going to go to in a     
34:43     
minute uh but we're going to discuss it and walk through the data set it's basically this uh she's created a     
34:51     
channel called data which stands for data visualization and posted the brief there like I said we'll go through the     
34:56     
data um and then what she wants to do basically is work on the data set as     
35:05     
like you know go through take the data create a hierarchical model or     
35:11     
hierarchical representation then create a visualization um so the this these are     
35:17     
data that have been generated by The Ellen Institute so these are neuroscientific data and then the idea     
35:23     
is that you would take that and visualize it and um you know you can do this in different ways once     
35:29     
you have the data you know you have to figure out sort of the data structures that you can like then use to analyze it     
35:37     
so there're different algorithms you can apply there different analyses you can apply but they all have their own     
35:42     
assumptions so you can't just throw a method at data and make it happen you     
35:48     
have to be able to understand what the structure of your data is and then what     
35:53     
the assumptions of the model are and then you know put putting those two together what can kinds of interesting     
36:00     
things can I do the idea is that there's this data set created by this group by this institute that has you know a good     
36:07     
reputation of creating quality data that's important they provide some tools     
36:12     
for visualizing data but you need to have it's a pretty high bar of Entry so     
36:17     
you need to have a good sense of what you know what you're doing you need to know how the tools work so it's hard to     
36:25     
know the different things about you know how to use it um and so you know this     
36:31     
this is just something that maybe a professional neuroscientist would use um     
36:36     
but she wants to actually just see the data itself she wants to be able to get     
36:42     
uh some data you know basically generate a clustering algorithm hierarchical clustering algorithm I'm assuming you     
36:49     
know some sort of hierarchical uh clustering like where you have a clustering algorithm but it     
36:56     
produces a tree uh I do have a puzzle like the cluster at the moment doesn't have much in there     
37:03     
it's got some integers and I haven't figured out what those integers stand for and so you know there they're     
37:09     
different aspects of the data that we have that we can use to analyze     
37:14     
things it could be that I have to bother the author could be their codes so sometimes you have to consult with the     
37:20     
author sometimes the people generating the data have information that they can put into the um um you know that they     
37:30     
put into documentation sometimes you have to kind of correspond with the     
37:35     
author of the data set Tim you know um ideally it should be that everything is     
37:40     
in documentation form so ideally if you're doing a data analysis if it's a primary     
37:46     
analysis uh you know you want to be clear about what things mean what the variable names mean what how the     
37:52     
variables were collected you know and then what the measures are if they're continuous or if they're binary or     
37:59     
whatever and what those mean so uh you know I I think that's a good     
38:06     
uh starting point I think she's got a good data set to work with now there are     
38:11     
some questions about visualization so basically what she's trying to do is     
38:17     
create a visualization and then apply this to this model card's idea that she has um that you know she's working on so     
38:25     
it's like taking the data extracting some insights using some technique     
38:31     
hierarchical clustering or whatever similar to that and then um you know     
38:36     
applying it to these model cards and so uh what I'm using them for is to provide a natural language description where you     
38:44     
can yeah and then uh sir we have a data model which is the silent data set and I     
38:50     
would like to see in the middle part and I'm going to do them all parts after I get it um and it's yeah so this     
38:58     
is uh yeah I think this is it then there's     
39:03     
you know you can use Python to parse the data set and to build the visualizations and everything else so uh     
39:11     
there's you know maybe there's a mind map that you can create as well I don't really know we'll have to talk about     
39:16     
this in a minute but so I think that's good kind of a good starting point um I'm going to go into the data I'm going     
39:23     
to show the data in a minute but I wanted to ask Paula if she had any anything to add or if I got that right     
39:29     
or what what what her thoughts are thank you thank you so much yes you Illustrated very well I'm sorry the in     
39:36     
the narrative in the I recorded the messages because it's easier and I think     
39:42     
I got yes you got you got the summary right so basically actually the one     
39:48     
thing I didn't post which I said I would do which I'm gonna try to do now it's not as do dat there is um on diub I     
39:56     
found a script python script that says that you can easily visualize viory from     
40:03     
using Python and I have tried but I didn't manage so I'm going to try to suggest that that is method is tried     
40:10     
first but please just go ahead and and and show the data I mean as long as nobody do anybody have any question is     
40:17     
the pro problem statement clear first of all and if it is we just go into the     
40:23     
data if not ask me any questions yeah I okay so I'll get into into the data so     
40:29     
this is the data here um right from the Allen brain Institute what they've done is they've got these variable super     
40:37     
cluster uh they've got labels they've got classes     
40:44     
neurotransmitters neuropeptides so basically how you organize a data set is you have like a case which is you know a     
40:52     
row in that case as a number and you know these are these might be you know     
40:59     
sometimes they're ordered sometimes they're not I don't think these are ordered but what you'll end up doing is     
41:04     
you'll have of course columns that are linked to that ID and you'll have different uh information in there so you     
41:12     
know you'll have multiple variables you might have a neurotransmitter a     
41:17     
neuropeptide it's part of what they call region of Interest which is a regional     
41:23     
uh description um you know there are all sorts of things here here now the thing     
41:28     
you want to do when you do a data analysis is you want to keep your cases intact so every case has a bunch of     
41:36     
stuff in it and that's like that observation and you know if you're doing data science you know sometimes you'll     
41:43     
want to sort your observations by one of the variables and this is very important     
41:49     
when you do when you generate a script or if you sort it in some way that those     
41:54     
cases remain intact and this is one one of those lessons of kind of like introductory data science programming is     
42:01     
that you know when you do a sort you want to keep everything together you don't want to Jumble you don't want to     
42:07     
just sort one column and get everything out of sync and and delink the label     
42:12     
from the different things because all of these things are this is you know highly     
42:19     
uh multi-dimensional set of data so all these columns are different variables     
42:25     
potentially and so we can we can add them together and we can maybe get     
42:30     
reduce them by doing data reduction or or dimensionality reduction we can take     
42:36     
single variables and plot maybe one variable versus another we can transform     
42:42     
them into binary values or we can transform them into you know some scale     
42:48     
but what we don't want to do is decouple our uh cases you know data from uh one     
42:55     
variable from another variable in the same case we want to make sure that the cases remain     
43:00     
intact okay okay that's the that's the correct one ABC so we have three columns ABC sub     
43:08     
cluster cluster super cluster so far if you look at if you scroll down and you     
43:14     
look at chart uh over there it's an additional sheet at the very Bott very bottom     
43:22     
or yeah it says chart okay so this is the visual ation of the super     
43:28     
clusters which is simple at meat and it shows there are 30 something super     
43:34     
cluster plus a bunch [Music] of mixed ones and we can see from this     
43:41     
visualization that the biggest the cluster is the what spatter so let's     
43:47     
start from there it's the biggest chunk and if you hover over that pie you     
43:55     
should be able to see a little number popping up somewhere and my assumption is that the number that if you hover     
44:02     
over the pi um slice the purple     
44:07     
one you see a little number showing what I think is what inside that cluster uh     
44:14     
super classer uh which is uh supposedly the sub classers and then the uh inside     
44:23     
each subcluster there is what no sorry there is a yeah there is a     
44:30     
cluster so there is a hierarchy there of ABC and uh and and what I think I would     
44:36     
like to do before I can do any further how do you say     
44:42     
analysis uh which eventually I'm not going to get involved at the moment and I would not recommend anyone at this at     
44:49     
this stage to get into the details of what each um of what you know all the all the     
44:56     
columns because there's a lot and I think Alan Institute with tools do a very good job     
45:03     
doing that but what it doesn't do and what I think should do is to have a mind map which shows a data tree whereby for     
45:10     
each of these super classers you can click on it and expand     
45:15     
it and see how many clusters and clusters are uh belong to this super CL     
45:22     
and just speak to have a clear idea of how the data is organized uh and I would     
45:28     
have thought this is very trivial you know it's very easy thing to do but I I'm not very good with tools and I been     
45:35     
wasting a lot of time and you know checking out then somebody came up with this H     
45:42     
powerbi uh they fed the the table to the sheet to power VI and uh if you can go     
45:51     
uh Bradly to the to the slack Channel     
45:57     
uh database I have uploaded together with the chart I have     
46:03     
uploaded um screenshot of when I sh WhatsApp WhatsApp image     
46:11     
yeah okay this is more or less what I'm after     
46:17     
um okay you can see this shows a bunch of things hanging     
46:24     
from splatter and then if you standand splatter you     
46:30     
see all the subclusters that hang down there okay and it should be easy enough     
46:35     
but I don't have powerbi and the person who did this demo demo this for me said they couldn't give it to me they     
46:41     
couldn't give me the code for this um realization and so I I was left thinking     
46:46     
how can I reproduce it and that's a little bit where I got stuck so at the moment although the data set is very     
46:52     
interesting and in merits being understood and studied further I would say uh let's crack this very simple     
46:59     
visualization problem and I'm sure in this lab there are very good people who can do it and I have this guy who has     
47:06     
come up you may have seen his answer in SL saying yeah I can do it so I I don't     
47:12     
know if anyone else would like to offer a solution for how to achieve this um     
47:18     
and anyone else has any questions or comments on on this what I'm trying to do it's called     
47:25     
powerbi Power okay and this is like freeware or is this like a     
47:32     
powerbi no it's a micros business intelligence stand for business     
47:38     
intelligence is a license store and the person who did this has the license from the work and they were not comfortable     
47:46     
uh using it because there is a license number attached to every download they said you it's my work place I don't want     
47:53     
to put this out Etc so but it's it looks like it can be done very easily with the     
47:58     
right tool right I don't know if anybody has any intelligence there so like what     
48:04     
is this this analysis or this visualization type is there a name for it     
48:12     
or it's called it's a data tree or a I I would call it a mind m a mind map uh     
48:19     
more or less would would has the same structure whereby you have a the first     
48:25     
node which is the higher the highest element in the hierarchy super clal and     
48:32     
then the nodes that hang from which Super and then so on in a in a hierarchy     
48:40     
structure so I I think the correct name is data tree and the mind map is a type     
48:46     
of visualization diagram that you can use to visualize data     
48:52     
treats yeah that that looks good um yeah and so you just it would be     
48:59     
useful because then you can take a look and you say I want to see what's in that super class what is in that class you     
49:06     
just click on it and it shows and from there uh I can probably think of what     
49:14     
would be the best next step now as you can see the sub classers have a name okay     
49:21     
M uh it's like splatter and the other that you can see easily from the     
49:28     
pie chart looked at before the cluster and subclusters actually are     
49:36     
numbers that's when I refer to integers you can see that     
49:45     
um and and so these are a little bit but I'm going to work out what these numbers stand for and I think they're     
49:52     
just you know numbers that would correspond to some kind of description of what that what's that number stand so     
49:59     
at the moment if I could just get that visualization then it would allow me to work with the data set without having to     
50:06     
go into I don't know much is going to be much easier to to look at the DAT set to figure out what it is and how how it's     
50:15     
struct yeah so this and then so where do the model cards come in you said that     
50:20     
you wanted to ultimately use this to inform the model cards     
50:27     
I didn't get the word the model what the model     
50:33     
curs model currents yeah I mean how do those relate to this visualization cards     
50:40     
he said cards oh cards oh sorry cards cards so basically the idea is um so you     
50:49     
understand what I mean by model card right yeah yeah well why don't you me why don't you     
50:55     
describe it for people yeah okay so the best description so the     
51:02     
mod cards are well described in Bunch papers starting starting from the Google     
51:09     
team um uh in 2018 they mentioned that how could a     
51:16     
model card basically it's a What in in in in AI corresponds to     
51:23     
what are train so it's a it's a set of slots where you things in it and you say     
51:32     
what the things are to denote some values that are then used by the     
51:37     
AI and uh in in machine learning the data is uh not easily readable like we     
51:46     
now if you look at the table and then you look at this map at this visualization you can see how the     
51:51     
visualization shows um at a glance what's in the table okay so the model     
51:57     
card does the same thing the model card you you look at the model card and uh     
52:02     
you read it as as a text and it tells you what's in the model so the best     
52:07     
characterization of a model card I you seen it on hugging face which I think you got to     
52:15     
already and if you search um for uh     
52:20     
having Face model Parts there is a lot of matal now there wasn't when I first joined but there is now if you search     
52:28     
for H based Ms there is a whole section where they give a very profound accurate     
52:35     
thorough description of mards in all this aspects far too detailed even     
52:40     
sometimes I said oh my gosh you know they're going one it's not necessary to describe them in that sense but it's good good work so describes model cards     
52:49     
very neatly and what I have done so far is that I've taken model cards are     
52:55     
described in a in uh in an interface which is HTML and I don't know if I've already     
53:02     
explained this in some some short talks or somewhere um I have a hugging face uh     
53:10     
mother car template that I'm trying so I extracted the uh XML from     
53:17     
the from the HTML I sprayed and and the idea is to create a     
53:23     
model card generator so I'm not a programmer either Jaz but     
53:29     
you know I'm really sometimes if I have some time to waste I try to do things like that so I thought can we generate     
53:36     
can we create an interface where people just fill in the slots like they would     
53:41     
they would do fill out like a Google form okay you create a Google form and you can decide what you want in your     
53:48     
form like you decide how many questions what type of questions and so I thought could we have a mod card generator and     
53:55     
this is actually should be definitely a Google summer of code project if if I     
54:01     
suspect someone may have already done it I would be surprise so when I put a question out there saying has anyone     
54:07     
made a generator for for xmf um so um     
54:14     
the idea is to have uh model cards uh you you fill out the form when you said     
54:21     
I want the model card like this once the model card generator is uh live anyone     
54:27     
can just fill out the slots and XML would automatically be uh regenerate     
54:35     
without having to write the actual XML for each card by hand it's a very clever little trick and a guy came up to me     
54:42     
saying I have an ontology generator so I know that there are bits of work done but so that is the idea and I think it     
54:48     
would be nice somebody to do it or I I don't interface with Google summer code     
54:53     
and I was going to ask you guys I didn't understand how far are you into the     
54:59     
Google summer code project I didn't understand have you is orthogonal lab going to be already     
55:06     
um uh has already been accepted your proposal I don't know how it works but I think this would be nice if not you can     
55:12     
just do it here H so is is it clear Bradley what I'm trying to do with Mod cards have I answered your question yeah     
55:20     
yeah I think so and I think I just wanted everyone to get a sense of where you're were going with this yeah we     
55:26     
unfortunately this year you know we've already Bally the idea is once we have once we know how the structure is     
55:34     
whenever this structure will have to be reflected into the model card and rather     
55:39     
than doing each model card by hand I think should we not have a mod generator that uh can be structured according to     
55:47     
uh based on the the structure of this B that's the     
55:54     
idea all right yeah and then uh so un oh what was     
56:01     
that yeah yeah could be useful yeah yeah definitely     
56:09     
yeah yeah so these are this is um this is uh yeah a lot of outputs um     
56:19     
will generate the kind of data files that you're that I think you're you're     
56:25     
looking to to to to generate here     
56:31     
um you know I I I can think of particular examples where you know like bids and things where you're you're     
56:39     
producing um yeah you kind of have a file format     
56:45     
that that specifies a markup um metadata     
56:50     
file you know and um uh so what what I was was trying to     
56:57     
look for and not not necessarily finding it this this second but and follow up     
57:03     
later is um is how the um what's the lab     
57:10     
Larson the LaRon lab um did the uh did     
57:17     
the clustering I'm I'm assuming it's some sort of umap is that have you     
57:23     
looked at this Bradley I have not looked into it deeply now I mean you know you     
57:29     
know it's not not to not to criticize these folks but like pretty much guaranteed     
57:37     
that they did some sort of nonlinear projection to get the Clusters that they got right     
57:44     
yeah you know and uh but     
57:51     
anyway what I mean is that like the data that I think Po's looking for     
57:56     
is is in that is you know like if we if we knew what they used to generate that     
58:05     
uh a clustering then it would be really easy to get in there and to generate the     
58:11     
metadata that you're looking for which would be you know in fact just um I mean     
58:18     
as far as I can tell would be you know certain aspects of the the model um uh     
58:26     
certain aspects of the model that you used and and yeah were yeah just just     
58:32     
that um uh actually I'm not just thinking     
58:39     
metadata so for example the the the column the column     
58:46     
heads in uh in the spreadsheet they are what I consider metadata so they are the     
58:53     
names of the data it says this data is whatever neurotransmitter is that is the     
59:01     
metadata but the actual card would generate the data     
59:06     
itself um expressed instead of being an     
59:11     
in CSV or XLS or HTML it would be in     
59:17     
XML and that I think in that I think the value the     
59:24     
value would be that it can be then pared by the language model that's the     
59:31     
ultimate goal the ultimate goal is that when you want because and I should speak to the to the brain gbt Guy Mr love I     
59:40     
have to go and try see if they understand what I'm talking about so basically once you ask a language model     
59:48     
using natural language interface like your chat gbt would hey what's the neurotransmitter for this uh     
59:57     
okay it would automatically be able to give you a sentence it says the neur transmit for the sell is because because     
1:00:04     
he can read the it can read the data at the moment it can't so at the moment if     
1:00:10     
you want to get a check the brain to give you answer you cannot query you can     
1:00:18     
query the data using I think the people are still using SQL I see I don't if     
1:00:26     
there is I mean that's the last thing I need I don't know if you want to ask uh     
1:00:31     
if you want to query a data set like such a large spreadsh like this you would have to ask you have     
1:00:38     
to which is not natural lenic it's a structured you you need to learn SQL     
1:00:44     
first but because we are moving towards language model where people ask     
1:00:50     
questions Theory data sets via a natural language interface like GP ch     
1:00:57     
then I think this would facilitate the any     
1:01:02     
CH chat GPT gini or whatever any natural language interface to be able to clear     
1:01:09     
the data and provide exact answers based on the data set at the moment I don't     
1:01:15     
think that functionality exists um yeah you know again like the     
1:01:24     
the model cards as as I understand the the M cards in huging     
1:01:30     
face you know it it's um it's kind of     
1:01:35     
bringing um it's kind of bringing a literate programming     
1:01:40     
to um to to model right     
1:01:48     
up I you know I'm trying to use yeah S I don't know if those     
1:01:54     
references one is for the human one is for the human for the human to be able to read the data without any other but     
1:02:02     
one is I think I think it would be for the for the natural language interfaces to use it I suspect you know I would be     
1:02:10     
useful for that purpose right right well so that's kind of the point is that that     
1:02:17     
that by using a literate programming style right where where you're um this     
1:02:25     
is this is an old was I think it was newth who started literate programming     
1:02:30     
is that right Bradley I think so you know but it's     
1:02:35     
it's you you you have your you have     
1:02:42     
um you you're not separating your model your modeling from your     
1:02:49     
text and and that that's um that actually gives you a a very tight     
1:02:57     
alignment between kind of your definitions and and parameters too right so that like that     
1:03:05     
then it becomes much clearer um to to a certain extent     
1:03:12     
like you can use human well you your your all your variables and and you know     
1:03:19     
things that are in the text so again like brain GPT you know it's doing a lot     
1:03:26     
of different things but one of the things it's definitely doing is basically you know they're feeding in     
1:03:31     
papers they're feeding in Neuroscience papers to to f tuna F tuna llm right and     
1:03:39     
and you know if if more papers used a     
1:03:45     
literate um writing framework or Paradigm then there     
1:03:51     
would be much tighter alignment in terms of of it wouldn't just be like I can     
1:03:57     
reference figure three figure three is is actually in the text like like I mean     
1:04:05     
I I I used to do this because you know I like to use oord's got some some big     
1:04:11     
names in R anyway you can put your R models um that are generating your     
1:04:17     
figures in your latch and and you know the nice thing     
1:04:22     
there is that if you started feeding that add into uh uh if you start feeding     
1:04:29     
the raw latch as opposed to the PDF     
1:04:35     
right into which which again this is all available on archive in the sense that     
1:04:41     
like like archive has the raw has the raw latch um and and then generates     
1:04:48     
postcript and then generates the PDF and now generates the HTML uh um but if you if you did this     
1:04:57     
then you know your your data and your modeling codes are all     
1:05:02     
embedded in the text right and and that gives that gives like very tight     
1:05:09     
alignment between the the um you know what what you see in the figure in terms     
1:05:16     
of you know in super cluster AG then you can you can it can actually see the link     
1:05:23     
to you know we're calling this you know Medela or something you know like like     
1:05:29     
all all those the human labels and then the references to that in the text are     
1:05:36     
are actually you know directly linked to both a model and and it's its     
1:05:44     
data I I can I can drop some links in the the data V Channel yeah that that     
1:05:51     
relate to this and how you you generate the the     
1:05:58     
um how how I would imagine you generate long cards from this that that seems     
1:06:04     
Seems like that would be a great approach thank you thank you I think     
1:06:10     
you've seen probably further than I do uh I didn't I was just thinking you know     
1:06:16     
uh I want to see the data I want to be able to model the data using model cards     
1:06:21     
and then I would like to have model cards uh produced generated as XML I     
1:06:27     
don't know why is this because that's my what I've been doing like and then because XML is very flexible and it can     
1:06:33     
be linked and as you say you mentioned and it can be manipulated in certain way     
1:06:40     
and qued in certain way so that's very and actually bradle mentioned it before     
1:06:45     
I think if we have it in that way it can be integrated different data sets could     
1:06:51     
be integrated easy without having to because there would be like um a natural     
1:06:59     
langage integration you know that's I thought but what you're seeing more it's     
1:07:05     
probably an application of this which could be useful so thank you and I can see that jazz suggested that I write     
1:07:12     
this up I have already written up the first step jazz in the call for     
1:07:17     
involvement and then to because I didn't want to clock the channel I described     
1:07:22     
the first task of visualization in the Channel called B data Bas     
1:07:31     
database let's get this three columns uh and I uploaded the three     
1:07:38     
columns only as a csb uh show up like this screenshot     
1:07:45     
which is the whats file shows example and there are millions of way that this can be done very economically for those     
1:07:51     
who know how to do and once we have that we could think the model Parts uh but I     
1:07:58     
understand what you're asking um jazz is write up this the entire scope of the     
1:08:05     
project as I described it here and I can do that let me just work on it I think it could be useful because it could     
1:08:12     
become a big project and I'm not expecting uh that orthogonal lab soles     
1:08:17     
it but if is of interest and if you guys have resources you need any of your     
1:08:24     
brilliant um folks say oh yeah I could do it easy     
1:08:29     
then know let's work on it if not we just leave it on the Shelf have something     
1:08:35     
um possibly that I you know no worries I mean under no pressure it's my own thing     
1:08:41     
it's my own ambition and and I even tried to hire programers on google.com and things like     
1:08:48     
that but it's you know and I said okay I pay someone couple of hours to to do it     
1:08:54     
but or a few hours or whatever but I haven't found anyone reliable and I'm spending too too much time on this uh we     
1:09:02     
this is not my primary talk this is something that I would like to do and because you have a fantastic resource     
1:09:07     
here I decided to share it and I really appreciate the time to illustrate it and     
1:09:15     
I will write it up or or narrate it and more completely than I already have     
1:09:22     
the DAT this channel so that people understand why want to do the visualization as a first step and and     
1:09:29     
then hopefully you never know maybe you know maybe some students looking for some project and interested in exploring     
1:09:36     
this so thank you so much for the space to discuss it yeah sure and and you can     
1:09:43     
move on unless yeah J Jesse shared a link for     
1:09:52     
for swe sweave so you know I mean I I'm I'm so old I learned     
1:10:00     
S I learned s first r r is Theo version of s     
1:10:06     
oh and yeah yeah yeah so um and um     
1:10:13     
anyway as a um I've got this somewhere archived uh I've got a Nur Imaging study     
1:10:22     
written up as latch with our our figures yeah and it it it's it's     
1:10:32     
it is a nice it's a nice way to think about how to generate machine     
1:10:38     
readable um you know again like text you     
1:10:43     
know you know like the humans got the text the the computers got your your     
1:10:50     
figures with the with the code that generates those figures and and the DAT     
1:10:56     
you know it's got every you know it has to have the data the modeling code and the text so that there's there's     
1:11:02     
alignment in terms of you know these human terms relate to these figures and     
1:11:08     
and you know these clusters Etc that you're seeing in this kind of Allen Institute data um I I wanted to point     
1:11:16     
out I think I dropped a link in this to um call for involvement but anyway that     
1:11:23     
that Arizona State just did like two weeks ago I think did     
1:11:29     
a um the math department did a like a     
1:11:34     
special Saturday all day event of just going through Allen Institute     
1:11:40     
data and if they might not have done this     
1:11:45     
particular um uh Larson data set but um     
1:11:52     
but again like I I the the easiest way way to generate this uh um     
1:11:59     
automatically you know would be again to like have the code that they use to     
1:12:04     
generate those clusters and then just just have it     
1:12:09     
um what I would say called is have it with verbos     
1:12:17     
output you know which is usually a flag and and then okay I'm look for it if it     
1:12:23     
exists give it though want give it they will give the     
1:12:29     
data I don't know if they give it they maybe will     
1:12:34     
so I believe it's now yeah I believe it's now a reporting     
1:12:40     
requirement you know like like again like they're they don't not necessarily     
1:12:46     
do look up I didn't I didn't even think how they generated it I I I could have     
1:12:52     
but it could also be that it's written in the paper     
1:12:57     
information I have so let let me follow up on that and and I understand the     
1:13:04     
suggestion that the swe swe is great yeah let's see let's you see     
1:13:11     
because these other approaches tend to be very technical I'm more like a socio     
1:13:17     
technical I am interested in grabbing the looking at the data understanding what is it in it using you see if I wear     
1:13:25     
a mathematician or a computer write write a program or write the script for     
1:13:31     
for figuring that this is what Al do does but to some extent but the way they     
1:13:38     
the output they give me is not the outut I need so I thought what would be the quick way so but iate that um maybe     
1:13:46     
there are other ways of of of achieving that result and I would look into Suite uh it looks maybe more complic I think     
1:13:53     
it can be simpli greatly uh by following the approach and and I understand that is not always the     
1:14:00     
simplest thing that to scientist um and this is why I'm a little bit an odd one out but let me     
1:14:08     
look at the if I can get the coding in from him and if anyone if anyone feels     
1:14:15     
inclined to follow me on this I think this would be a very simple simple     
1:14:21     
simple non technical way of achieving that result um I mean least it's least     
1:14:27     
technical possible if it is a and if not let's just not waste time in it and     
1:14:33     
unless work on something else you but thank you thank you for the opportunity to share this     
1:14:39     
problem yeah and uh to help me find a direction for for the solution all right     
1:14:47     
yeah that's no problem and by the way Morgan if you have any links the Ariz people if you have I     
1:14:55     
could I could even reach out to them and saying I'm trying to do this maybe they already the results so let me know if     
1:15:01     
you have some I'll follow up with you no problem     
1:15:07     
yeah uh yeah so Jesse had mentioned yeah Jesse had mentioned about Google summer     
1:15:12     
of code so yeah unfortunately this year we've already selected our candidates and everything but we're doing uh you     
1:15:20     
know we usually do uh projects in maybe January so we write up a proposal in     
1:15:26     
January and then we uh get solicit people for the project and then we end     
1:15:33     
up selecting people and then you know there's no guarantee you'll get people on it but it would be kind of an     
1:15:39     
interesting project uh especially with respect to some of the stuff that we've we like this sweave user manual I     
1:15:46     
actually teach something like this in project management to how to integrate different uh you know pieces of code and     
1:15:53     
markup to build documents because documentation is very important in managing projects and things like that     
1:16:01     
um so that's that's nice thank you for the documentation you know again my my um I     
1:16:07     
was thrown in the Deep ends of software engineering in terms of medical device     
1:16:12     
development so so where you know like everything needs to be you know     
1:16:18     
documentation comes first you before you before you write     
1:16:23     
codes anyway yeah yeah so lots of lots of good practices there yeah but but in     
1:16:30     
particular I've really been thinking about how yeah but you know why right you know why I can I can I can provide     
1:16:36     
an explanation to that because you know simply because this uh par law it says     
1:16:43     
you know you should start writing codes without having a clear design of what you're doing First You're Gonna spend a lot of time doing it and doing it     
1:16:49     
debugging it was if you have a plan and your documentation could be as simple as     
1:16:55     
diagram for the system then you would uh you know it would be easier so and also     
1:17:01     
for communicating the the work among the team members so this is why the documentation comes first so sorry yes I     
1:17:09     
subscrib that yeah well the the the and the the military realized this very     
1:17:15     
early um in the production of aircraft that required a number of suppliers and     
1:17:22     
a number of different designers that that that their models needed to come together um so it was interesting that     
1:17:29     
you know we were all doing software engineering but we were kind of picking up these best practices that had come     
1:17:36     
from from aircraft manufacturing like 50 years     
1:17:42     
before anyway but just wanted to say that you know as     
1:17:49     
ironically is you know I don't want to mention but something is going on the     
1:17:54     
that is not nobody can explain so somewhere along the line This has happen     
1:18:01     
particular yes I they they started ignoring those best practices from from     
1:18:07     
75 years ago yeah uh uh the um just as     
1:18:13     
as it relates to how best to to feed you know again like reading reading     
1:18:19     
Neuroscience papers doesn't give um people doesn't give the computer access     
1:18:27     
to the modeling and the data in a in a constructive fashion right and so you     
1:18:34     
see with with various projects that have that have popped up in the you know     
1:18:39     
neuroimaging Community which my example is going to come from but where you know they've     
1:18:45     
they've gone through in the figures to try and find you know the the cluster coordinates and     
1:18:54     
things like that to feed into a database because they don't have access     
1:19:00     
to the data and they don't have access to the modeling code and you know with something like     
1:19:07     
sweave you can you can actually write uh     
1:19:12     
such that the the the computer would have access to the full stack you know     
1:19:18     
and that's that's what's really you know interesting and Powerful about thinking about that as as inputs to brain GPT I think     
1:19:26     
would be you know really remarkable yeah yes yes yes that's     
1:19:33     
that's where I come from and thank you so much for for understanding it when I look there is a lot of this is where how     
1:19:38     
I got into into the Neuroscience in the first so one day I decided see let's     
1:19:44     
look at the brain data out there and I saw mess and unspeak bless that unless     
1:19:51     
you had studied uh brain science and unless you were really trained as a     
1:19:57     
informatician in brain data you wouldn't be able to make sense and I think we're     
1:20:03     
getting to the point where we everybody needs to understand at least to some extent some of this data because it's     
1:20:08     
becoming very relevant to a number of other number one machine learning and AI     
1:20:14     
so we need to get this we need to have an understanding of the data without that learning gr and I think that's     
1:20:21     
where hopefully uh this work will contribute to but is more like generally     
1:20:26     
the sense of direction where I think I'm I'm heavy and this is the kind of work     
1:20:31     
I'm interested in doing so thank you for appreciating the     
1:20:37     
challenge yeah no problem uh yeah so again you know we can do the project     
1:20:42     
through GAC which would require us to sort of come up with a proposal in January but also we can have you know     
1:20:51     
people can work on it if we can find someone who wants to do do something in the lab you know a lot of times we have     
1:20:57     
people who we get as interns and through other streams and they may want to do     
1:21:03     
something I know in the fall we're going to have people who are interested in doing uh model building and I haven't     
1:21:09     
worked out the details on that yet but we will have like opportunities and that might be something for them to work on     
1:21:16     
as well because um that sounds like something that would tie into like a lot     
1:21:22     
of different aspects of data like not just analysis but like you said the     
1:21:27     
Neuroscience data sets that exist maybe not like well I think a lot of them uh     
1:21:34     
are kind of a mess with respect to people outside of Neuroscience like how do you take a data set like that and     
1:21:41     
work with it um if you're well versed in Neuroscience you can do it but if you're     
1:21:46     
not then it's a little bit harder especially like if you're trying to build like a yeah just read it even just     
1:21:54     
look at yeah yeah so we yeah we spend a lot of money and time on building tools to     
1:22:01     
parse things to integrate these things and it's going to be one you know um     
1:22:07     
it's still no better I guess is the point um and so this is this is an opportunity I think to get a bit more of     
1:22:14     
a handle on the data there in that area um and yes I would like to     
1:22:21     
underline I already said it but let me mention it again the model card have been developed to uh support uh machine     
1:22:30     
learning models okay which are ultimately I don't want to get into this     
1:22:35     
to much but ultimately machine learning like a neural network and stuff like they     
1:22:40     
processes so what they're doing is they're creating a a model card to     
1:22:46     
explain what is the process behind the algorith okay it's just to show what the     
1:22:53     
algorithm about algorithm is a process okay whatever     
1:22:58     
algori what I think I'm doing which is relatively new comma not rocket science     
1:23:04     
but Innovative I think is that I'm trying to use the model card     
1:23:09     
to uh represent a data model which is not a process like the     
1:23:16     
data sheet that we're looking at the spreadsheet that you're looking at is a is a data model it's not a process yes     
1:23:23     
okay so and I think that's new so I think new I I think it's new I mean it's     
1:23:28     
new like nothing too big but I felt that when I looked at it and I said I'm using a mod card to to to make explicit using     
1:23:37     
the words what is in in that data set what normally cards are used to make     
1:23:43     
explicit using words what the algorithm does and in that sense I think it's a     
1:23:49     
it's a it's a application somehow I wanted to underline     
1:23:57     
yeah okay yeah so there's another there's a paper associated with this uh     
1:24:03     
I don't know this is I guess the Larson data set so this is the paper that is associated with this data set this is     
1:24:10     
transcript toic diversity of cell types across the adult human brain uh so this     
1:24:16     
is again the the source and again yeah so you know if it's in science you know     
1:24:21     
it's kind of a closed access paper but you would have to go through the paper and find things in the     
1:24:29     
traditional way that they do this which is to go through the rep uh the     
1:24:34     
materials and methods and kind of dig things out um so you know this is     
1:24:39     
basically destion oh okay well yeah and which is     
1:24:45     
good and up until very recently we haven't had pre-prints to to draw from     
1:24:50     
so this again is an improvement so uh the structured abstract reads the     
1:24:55     
mamalian brain comprises billions of neurons and glea capable of executing     
1:25:00     
highly complex behaviors these cells are organized into several major functional regions with distinct developmental     
1:25:08     
Origins although the cerebral cortex is the most well studied because of its role in cognition the other regions are     
1:25:15     
near less essential so this is where they're what they're trying to do with their data set in the past several years     
1:25:21     
single cell genomic methods have revolutionized their understanding of the brain cellular diversity revealing     
1:25:27     
hundreds of transcriptomic cell types across the mouse bra so this is what they're trying to do they're trying to     
1:25:32     
get this information out of these cell types they're trying to get transcriptomic data which is gene     
1:25:38     
expression data and they're doing this across the mouse braing so this is this data set is sort of a survey of this and     
1:25:45     
you know where you can have two different types of data sets I guess one is to answer very specific questions     
1:25:52     
which is if I do an experiment I'll you know do the experiment I'll     
1:25:57     
have some very specific data for that experiment and then I might maybe do uh     
1:26:04     
a thousand replicates of that experiment so that data can be used to understand     
1:26:09     
that experiment but it can't be used to understand other things U it's hard to     
1:26:15     
like use those data to inform something else now something like this we have     
1:26:20     
data from a a wide variety of like we might survey a bunch of neurons in the     
1:26:26     
brain so that's this kind of data you have that sort of a descriptive aspect     
1:26:31     
to it but you don't necessarily have like specific interventions that you're making so you know that's another thing     
1:26:37     
to think about when you're using data is that you have this aspect of um you know     
1:26:44     
almost like intervention type you know so you have like things where you make an intervention and then you have things     
1:26:50     
where you're surveying the um the system system and you're getting some     
1:26:56     
descriptive parameters and so uh this is where they're trying to distinguish     
1:27:03     
diversity in looking at transcriptomics which is hard because it's a problem     
1:27:08     
where you know we don't know how to really describe it fully we can say that there differences between cell types but     
1:27:15     
you know defining those cell types in terms of specific differences that's kind of what we're doing with the     
1:27:22     
analysis we're using some sort of structured model to sort of take things     
1:27:29     
with a common signature and put them into different groups and so that's why     
1:27:34     
you know it's kind of um you know when you when you start it out I mean it's kind of hard to say um we're going to     
1:27:42     
create these groups because we don't have labels for them we have putative labels but there are a lot of sub     
1:27:49     
classes and things like that so yeah uh I well I yeah I can share the     
1:27:55     
science paper I can share the preprint you can do that after the yeah um yeah     
1:28:01     
so with basically what they do in a study like this is they they profile cells they get RNA sequencing they take     
1:28:08     
a sampling of locations in the brain and then they take a sampling of cells so     
1:28:13     
they have a final data set which is more than 3 million cells including 2 million     
1:28:19     
neurons which we clustered iteratively into 31 superclusters 461 clusters and     
1:28:27     
3,313 subclusters this tap- down approach enabled us to examine and compare heterogenity within and across     
1:28:34     
cell classes and regions and so that's what they're doing here they're trying to find neuronal subtypes and again this     
1:28:41     
is something that's um you know we have labels for groups but sometimes     
1:28:48     
especially when you're looking at the data in a new way those labels are going to be inappropriate we need to come up     
1:28:54     
with new labels so it's always good to think in that way that it's it's you     
1:29:00     
know that we have labels but there's also this exploratory aspect of it and so this is a     
1:29:06     
a visual sort of representation what they're doing here this is a human brain     
1:29:13     
you have these you know regions of interest that you have that we know from     
1:29:18     
kind of studies of the brain that you know we can take those regions of Interest     
1:29:24     
we have names for them so we can take a sample from that region of Interest we can give that a name those regions of     
1:29:32     
Interest then yield super clusters then those have clusters within the super clusters and then there's     
1:29:38     
subclusters within the Clusters so you can see that hierarchical relationship in the brain we have these partitions     
1:29:46     
which are Super clusters because they contain clusters of cell types and then     
1:29:51     
those clusters contain subclusters of cell cell types so if you think about this in terms of like uh say like the     
1:29:59     
hippocampus you know you have maybe it's a bad example but the hippocampus has multiple neuronal types many different     
1:30:07     
types of gal cell Ayes we can then take those cluster you know find clusters     
1:30:15     
within there that might be like a couple of cell types that have a similar signature and then subclusters which     
1:30:21     
might be functional differences by transcription which means that they're basically functionally distinct     
1:30:29     
but maybe they have the same morphology where that they're have the same morphology but they're functionally     
1:30:34     
different so you know there are a lot of ways you can look at the yeah I because you have the paper in     
1:30:42     
yeah can you find I I I don't know I can can you understand my understanding is     
1:30:49     
that these clusters and subclusters in the table in the spreadsheet are not are not     
1:30:55     
named like the super cluster have a name or each super cluster each super cluster     
1:31:00     
has a name yeah but but the some clusters and cluster have numbers     
1:31:06     
okay and um and so can you find anywhere in the paper what these numbers I mean     
1:31:12     
is there a description of what every cluster is and in particular the sub     
1:31:18     
clust I my understanding is that they represent what the they call cell types     
1:31:25     
right so if you have the chance to figure out uh because that's what actually     
1:31:32     
motivated the whole thing my question was uh three five years ago to someone     
1:31:38     
at Allan Institute the director do we know how many cell types are there in     
1:31:44     
the brain and I think is this data set should be able to answer the question at     
1:31:50     
the moment what I have is a list of numbers 0 to 3,000 this is yeah we have     
1:31:57     
identified 3,000 subclusters which I think is what they refer to as cell type     
1:32:02     
if when you have the chance to look at the paper if you could have me answer that question make sure that my     
1:32:08     
understanding is correct and then don't they have names that I don't know I haven't figured that out yeah that that's     
1:32:15     
something it'll be in the the methods but yeah and like you know this is a     
1:32:20     
problem that we've talked about in Diva worm where you say how many types of cell or in the brain or in the     
1:32:26     
human body or any system and the answer is never clear because you do have this     
1:32:34     
aspect of like I can observe the phenotype of the cell and I can give it a label and people have done this in the     
1:32:40     
history of Neuroscience they've used like kology they've used uh you know microscopy they've drawn out cells they     
1:32:47     
they kind of have different characteristics of the cell the region of the brain but you know     
1:32:54     
transcriptomics gives us a different tool and that is to have like specific signatures of     
1:33:00     
transcription and that's a different aspect of it but in any case you know     
1:33:06     
asking that question just really depends on how you classify the cells if you use     
1:33:11     
some Criterion that involves maybe like different aspects of a phenotype or     
1:33:16     
transcription or some combination yeah you get a different answer it's basically just somewhat     
1:33:24     
noisy labels def now there is a paper there is a paper by the director     
1:33:31     
of Alan Institute who she wrote five years ago or more saying exactly the     
1:33:38     
problem the challenges in classification of brain cells so that's a big open     
1:33:43     
question at the moment probably that's why they've got numbers so when I looked at it we know neurons we know Gia Gia     
1:33:51     
how you pronounce it Gia and so there are a bunch which are already identified     
1:33:57     
and and understood but so when this data set came out and says there are 3,000 I that's I thought this is what we     
1:34:04     
need to study you think and then I got stuck in the visualization and I never     
1:34:09     
got so that's my next step obviously will be to understand what this what characterizes and and distinguishes this     
1:34:16     
different type of because I think that's where the juice is yeah of this and     
1:34:24     
there are other data sets too right you you you want to look at you know the big     
1:34:29     
brain data set for instance so you know big big brain is a different different way of     
1:34:37     
doing it where you know they're they're they've they've built all this very     
1:34:43     
specialized Hardware to to     
1:34:49     
um you know freeze a human brain slice it in incredibly thin     
1:34:57     
slices and then do all sorts of Imaging and microscopy on each     
1:35:04     
slice you know not only the the and and then being able to do microscopy with     
1:35:11     
that right but but where you now have actual visualizations of the the     
1:35:18     
different cells and and with um uh     
1:35:24     
IM imun Immunology based stating uh you     
1:35:30     
have the ability to distinguish um on the basis of     
1:35:37     
of um molecular signatures the more of the variety you know of of     
1:35:45     
cell types from a from a different perspective the the the transcriptomics     
1:35:50     
is is you know it's seen that yeah I mean you     
1:35:56     
know reference I haven't looked into yeah yeah definitely def so so so     
1:36:04     
how can we make it for example if we had way of modeling these data sets in a way     
1:36:10     
that doesn't break our brains then it could be easier to compare them for example to see how do we compare this     
1:36:16     
data set from that is you know how this classification this is a big job and this is the kind of thing I'm interested     
1:36:22     
in understanding and and I cannot even look at what's in the table so that's thank you for     
1:36:29     
pointing me out it would be nice to to start making a compiling um a list if     
1:36:35     
it's not there already of all these Pap sets there there yeah there is so so um     
1:36:43     
so I was in a meeting like 20 2017 um 2018 the um     
1:36:54     
I think it was like Nur storm or something I forget what the it was a weird     
1:37:00     
storm name meeting anyway at NBL and um     
1:37:06     
uh you want to look at Josh no it wasn't I don't think it was     
1:37:12     
called brainstorm you know like like anyway I can find it but the main thing     
1:37:18     
being that it had a bunch of had a bunch of Jania far people people and a bunch of Applied Physics     
1:37:25     
lab people from you know John's Hopkins are you know related and um and they     
1:37:32     
have a big you know they're so you know Allen Institute Jan Farm     
1:37:39     
people know that there there's actually multiple data sets need to be     
1:37:44     
linked and and I I want to say that Joshua V is the kind of Point person     
1:37:53     
and I believe his lab's name is neurodata um or I I I know it's his     
1:38:00     
Twitter handle or really something anyway yeah I have come across yeah     
1:38:08     
that's very useful thank you thank you because I have lost Str and also I think     
1:38:13     
things have changed incredibly in the last five years the the blue Brain     
1:38:18     
Project fell fell apart there been a lot of changes so I think it would be a good     
1:38:24     
time to update that list and thank you will you share any any point wherever     
1:38:30     
you think is suitable yeah absolutely no problem uh uh blueb Brain Project still     
1:38:37     
you know that's still ongoing it's just that they're no longer running the human brain     
1:38:44     
projects oh is it but but like yeah they've got a very active they've got a     
1:38:49     
Super Active team in L and Geneva you know and they're yeah so they they     
1:38:57     
still they're still building on top of the software you know like biggest     
1:39:04     
output of their their particular contributions to to the human brain     
1:39:10     
project were software and um uh but and then you know it's C cat     
1:39:18     
n's who's you know taken the Helm of of human brain project now called e brains     
1:39:25     
um but she runs the the ulic um the ulic     
1:39:31     
group now um that that zillis has passed um that's doing all the microscopy for     
1:39:37     
Big Brain um anyway like like you said like there's a whole bunch and we've     
1:39:44     
talked about that there's a whole bunch of of different data sets that each each Project's quite good     
1:39:50     
about kind of making some version or you know some something publicly available     
1:39:57     
but at the same time what really needs to be done and and and this meeting was one of of many to to look at that and     
1:40:06     
and um I think the most recent big brain meeting was in Iceland last year um but     
1:40:13     
is is I think the best meeting I mean other than you know like going to human     
1:40:19     
brain uh human brain mapping uh which is Ed June in Soul this year um to see you     
1:40:27     
know who who's who's doing the kind of um yeah wiring all these data sets     
1:40:36     
together yeah yeah so that's great um yeah so why don't we move on thank you     
1:40:43     
that was a good a good discussion of the data and different data sets and how we can integrate those some of the     
1:40:51     
issues um yeah I'll I'll that science paper I'll put it up in in slack and     
1:40:58     
it's worth mentioning that actually uh Paul talked with Zur here Zur of course     
1:41:05     
is um uh Zur uh is kadzi um he's you     
1:41:13     
know sometimes in the group but yeah he's interested in this so that's good um so why don't we move on to     
1:41:20     
another thing here uh this is something that I that I think     
1:41:26     
came out this week I'm not really sure how long this has been around but this is something that actually was uh if you     
1:41:32     
get complexity digest which is a an email or sometimes you can see it on social media they have this thing that     
1:41:39     
was just published this was published by the they adverti this thing that was published by the um Santa Fe Institute     
1:41:47     
and this is uh on a website foundational papers and complexity science so this is     
1:41:53     
kind of like an accounting of the history of complexity science and some of the major papers and going over those     
1:42:01     
so the project is where they want to sort of get a sense of where the field     
1:42:07     
of complexity science has been where it's going what are the major issues in the     
1:42:13     
field so uh this is foundational papers in complexity science is a project to     
1:42:20     
discern the unity of an evolving inquiry after pulling members of the extended     
1:42:25     
network of Santa Fe Institute complexity researchers so that's like people at the Santa Fe Institute and all the people     
1:42:32     
who are affiliated with it we selected 88 papers spanning just under a century     
1:42:37     
that chart the formation of the field so this is complexity science is in a lot of ways new but the roots of complexity     
1:42:45     
science are old I mean they go back maybe about a century and you know they     
1:42:51     
they were of course in different fields at the time but they kind of come together that coest into complexity     
1:42:56     
science so you've had people in physics in sociology and economics in um you know in biology and     
1:43:06     
Mathematics and they kind of streams of inquiry all kind of met in this     
1:43:11     
area uh these papers some Classics other cult others cultish and you know you'll     
1:43:17     
look at the papers and you'll see why they they say that in a minute collectively investigate the principles     
1:43:23     
of governing open out of equilibrium systems that are self-organizing or     
1:43:28     
selected in the natural or cultural world so this is the kind of uh you know     
1:43:33     
game that the santaan 2 plays they're interested in analyzing these type of     
1:43:39     
systems and the reason why we need a complexity science in the first place is because our traditional methods are much     
1:43:47     
less amenable to giving us an answer so if we use something like a a linear a general linear model     
1:43:53     
we can't get good answers to systems like this from that type of model if we     
1:44:00     
had a linear model if we had very simple experiment with a single intervention     
1:44:06     
with main effects that were strong and robust we wouldn't have to worry about those but the world isn't like that     
1:44:13     
that's the world of sort of a general linear model and what that does Best But now when we have systems that are more     
1:44:20     
like the real world that are open a of equilibrium systems that have features     
1:44:26     
of self-organization or natural and cultural selection then we need to have     
1:44:31     
this complexity methodology and so you know they they give this is a nice sort of curation of     
1:44:37     
papers that kind of go through a lot of the history but also sort of how these     
1:44:43     
techniques evolved so you know like with network theory for example you have     
1:44:48     
Network Theory coming out of graph Theory you have Network Theory coming out of a theory of interactions you have     
1:44:55     
Network Theory coming out of other places uh mathematics uh and other places where     
1:45:01     
you're dealing with matrices to to describe interactions and then     
1:45:07     
visualizations as well so there are a lot of things that kind of came together and people putting them together in a     
1:45:14     
way um and so uh the year 2000 is established as to cut off year     
1:45:19     
foundational papers so anything past the year 2000 is not considered a foundational paper that's interesting     
1:45:26     
because again with network science a lot of the landmark papers in that field are     
1:45:31     
just before the year 2000 so you or actually a little bit after the year 2000 so a lot of those papers are kind     
1:45:39     
of like right at that cut off here so you know it's interesting to say that like complexity science is somewhat old     
1:45:46     
but sometimes in some of these fields you know the foundational papers are maybe not as old as you think     
1:45:53     
so um let's get into the oh this is the home link here let's go back to the this     
1:46:02     
these volumes so these are kind of the description of some of these papers so     
1:46:09     
um you know I think here you have people introducing the paper uh and the paper     
1:46:14     
is here so the concept is here and then the paper is here so this first one is     
1:46:20     
maximum power as a physical principle Evolution and the paper that they chose     
1:46:27     
for this was by AJ lka if you're familiar with lka Tera or you know     
1:46:33     
co-evolution that's the same lodka and this is from 1922 contributions to the     
1:46:39     
energetics of evolution so this is where we're looking at evolutionary systems     
1:46:45     
and the energetics of evolutionary systems this concept of maximum power some of these are going to be pretty     
1:46:52     
obscure but they have their role in forming things that came leater again so     
1:46:59     
uh this is uh Suzanne still to work is to think that's the theme and then the paper that she chose was zard so if     
1:47:07     
you've heard of the zylar engine which is um it's a thermodynamic system that's     
1:47:13     
open and Exhibits sort of properties of the Maxwell's demon which we've talked about in the cybernetics group uh this     
1:47:21     
is the same lard and this paper is on the decrease of entropy in the     
1:47:27     
thermodynamic system by the intervention of intelligent beings in 1929 again the     
1:47:33     
title of some of these papers you couldn't get away with this today without some scrutiny because they     
1:47:38     
thought a little bit differently about the problems back then but this is basically you know leading to sort of     
1:47:44     
some of these ideas of information and energetic entropy and     
1:47:49     
things like that uh Sergey gaval uh this theme is navigating the     
1:47:56     
landscape of complexity Su WR seminal contributions and their far-reaching impact and of course for that the pixel     
1:48:03     
writes plasic paper from 1932 the roles of mutation in breeding     
1:48:09     
prospering and selection and evolution in which s WR introduces the idea of a     
1:48:14     
fitness landscape uh then Walter Fontana who's a     
1:48:19     
evolutionary biologist has this theme the shadow of a mechanism and for that     
1:48:25     
is uh waddington's paper canalization of development in the inheritance of     
1:48:30     
acquired characteristics that's from 1942 uh Bruno well shaen and Christopher     
1:48:36     
Hiller were neuroscientists the Genesis of modern Computing and Ai and they picked Mulla     
1:48:42     
and Pit's classic paper from 1943 The Logical calculus of the ideas eminent in nervous     
1:48:49     
activity Andrew Pickering the birth of cybernetic and they pick the Rosen gluth leaner and Bigalow paper Behavior     
1:48:57     
purpose and heliology from 1943 so as we go through these we can see that there are these papers that are     
1:49:04     
foundational to other fields as well as to complexity science and they just kind     
1:49:09     
of pick things that are very important that have these themes complexity themes     
1:49:14     
but like Mullen pits that paper is important in the Genesis of AI Rosen     
1:49:20     
gluth and Bigalow paper is important in the the Genesis of cybernetics and soil rights paper is     
1:49:26     
important in the Genesis of the uh neosynthesis and evolution so you can     
1:49:31     
see that there are these different um you know papers that kind of are foundational to other fields as well     
1:49:39     
um and I'm trying to see if we have any more interesting papers there other     
1:49:45     
volumes three other volumes here so you know we have uh Dwayne farmer gives the     
1:49:52     
Revolutionary discovery of chaos and picks a paper from Loren which is this     
1:49:58     
deterministic non-periodic flow paper from 1963 in which the Loren attractor was     
1:50:04     
proposed and this is again you know a lot of things with strange attractors and Chaos Theory and you know sort of     
1:50:11     
the foundations of them so this is a nice reference where you can look at some of these um you know very early     
1:50:21     
foundational papers and get a sense of the sort of the papers to go to to start     
1:50:26     
off your literature review and then you can you can do something like the forward search in Google Scholar to pick     
1:50:33     
up all the citations of that paper and you know kind of move forward through the literature that     
1:50:40     
way um I'm looking at some of these papers yeah this is H James Crutchfield     
1:50:46     
has this uh theme requisite complexity contemporary view of cybernetic control and communication and this is the knet     
1:50:53     
nashby a good regulator theorem paper so it's interesting that you know we're     
1:50:58     
picking up a lot of cybernetics but also a lot of things from other fields     
1:51:03     
physics but also Evolution um you know the Von noyman     
1:51:10     
paper theory of self reproducing automa you know other papers like this     
1:51:15     
one this is recurs moros space is the possible and the actual this is R     
1:51:22     
geometric analysis of shell coiling General problems so some of these are you know very specific to maybe problems     
1:51:30     
some of these are foundational the different fields but they all have this aspect of complexity in them um Duncan     
1:51:39     
Watts who of course wrote a paper with stroat in 1998 on small worlds in     
1:51:46     
networks and small world networks he has this the weak ties and the origins of     
1:51:51     
network science so like I said a lot of the foundational papers in network science were sort of around the year     
1:51:58     
2000 but the idea of network Theory goes back to graph Theory but it also goes     
1:52:04     
back to Sociology in the 60s and 70s uh so you had uh mgram doing mgrm     
1:52:13     
experiments uh not the psychological experiments but the ones where he sent a letter out in the mail or he sent a     
1:52:18     
bunch of letters out in the mail and wanted to see how many postmarks they would accumulate before they came back     
1:52:24     
to him so he used basically the model of a of a chain letter and he wanted to see     
1:52:30     
how many hops that would take across the network and so from that he was able to derive some of the first principles of     
1:52:38     
um small world networks they weren't really observed fully until we got to Watson strats but then gaver in 1973     
1:52:47     
talked about weak ties which was this idea that you have weak ties between different parts of a a social network     
1:52:54     
and that they serve to integrate The Social Network so there are a lot of things about Network the that kind of     
1:53:01     
have been around for a long time but they haven't really been integrated until maybe about 25 years ago and so     
1:53:07     
this is where we're getting a lot of this uh we're get the concepts and then the mathematical models and then the     
1:53:14     
applications and so this is a really good resource um I can make it available     
1:53:20     
to people but um yeah this is something that we should go through and and see     
1:53:27     
where if there are really interesting threads in this because it's a lot of uh it's a nice project a lot of     
1:53:37     
information yeah just the terrific collection though yeah right and and     
1:53:44     
yeah interesting to get to to get you know modern people to kind     
1:53:50     
of comment and introduce so really really interested to see that     
1:53:59     
yeah yeah so this is from the developmental systems blog this is I     
1:54:05     
think we've seen this before this is the flowers team at inria and France um they     
1:54:10     
work on a number of problems with respect this developmentally on cognitive systems theme or cognitive     
1:54:16     
Sciences so they're working on Pier Yoder does a lot of stuff with what you     
1:54:22     
might called developmental AI but they're also doing stuff with cognitive sciences and like this is an ecological     
1:54:29     
approach to artificial intelligence's post um so they've got a number of posts     
1:54:35     
here um one of the things I was interested in is this uh this stuff     
1:54:42     
about uh competencies of biological networks so this is a uh from the blog     
1:54:48     
here uh and this is kind of going through this is a tutorial about this     
1:54:53     
idea so Mike Levan is also involved in this and some other people as well um     
1:54:59     
and this is uh this tutorial is called Aid driven automated Discovery tools     
1:55:04     
reveal diverse behavioral competencies of biological networks so what they're     
1:55:09     
doing here is they're thinking about grns or uh genetic regulatory networks     
1:55:15     
and they're using these to sort of reveal different behavioral competencies so in um     
1:55:23     
in uh development we often have grns which are these uh genetic regulatory     
1:55:30     
networks and um we you know they do things they can regulate genes they can     
1:55:35     
regulate groups of genes and they produce different outputs and what they're saying here is     
1:55:41     
that they're different behavioral competencies of these networks and you know they're able to     
1:55:47     
navigate transcriptional space so you think of transcriptional bases any set     
1:55:53     
of outcomes that come from a specific Network so if we have a very simple     
1:55:58     
network uh we can have a number of different behavioral outputs so let me     
1:56:04     
show this in a in a in a board here so let's say we have a     
1:56:11     
regulatory network of three genes that go down stream here we go     
1:56:17     
from A to B to C and we might have a feedback from B to     
1:56:23     
a and we have an output so that output then you you might think this is very     
1:56:30     
simple a regulates b b regulates C this is positive this is negative and then     
1:56:38     
this feedback is positive and so if we can you know we have different limiters     
1:56:44     
on these different uh you know on the feedback so maybe we have feedback that's sporadic maybe we have feedback     
1:56:51     
that's constant it's going to of course give us a different output so if we just have like a up regulating B and B down     
1:56:58     
regulating C the behavior is you would think it would be simple but we know     
1:57:04     
from the world of uh complex systems that that's not necessarily true that if     
1:57:09     
this thing if you iterate over different initial conditions you can get different outputs but especially if you have a     
1:57:16     
feedback here which is a positive feedback where a is continually     
1:57:22     
changing its value and then that changes the value of B and then that changes the value of C or if you have a negative     
1:57:29     
feedback from the C to B that increases the complexity of the behavior of this     
1:57:34     
circuit even more so you can see from a circuit of a couple elements you can get a very diverse set of     
1:57:40     
outputs then those outputs are mapped to some sort of space so my set of outputs might be in     
1:57:46     
the space we might have a bunch of data points but the space is descriptive of     
1:57:53     
all possible data points so we want to have this combinatorial space where     
1:57:59     
we'll describe all different outputs and we get we can observe a subset of outputs if we W the model and then     
1:58:06     
that's what we get now we end up with these outputs that are a subset of the     
1:58:12     
space but you know it depends on what kind of things that you know we do with the network so if we have the network     
1:58:19     
set up with like certain different types of feedback different types of um you     
1:58:25     
know maybe thresholds for going from A to B or B to C or if a up regulates B     
1:58:31     
and B down regulates C we change those rules we change the sign on those then we can get different behavioral     
1:58:38     
outputs the thing here we're looking for different behavioral competencies so in     
1:58:44     
other words what is a network like this what can it do what can it output and if we replace these signs     
1:58:51     
with like logical functions so if we say     
1:58:57     
and so if the input to     
1:59:02     
a and the feedback are you know sufficient then b gets activated if not     
1:59:09     
B doesn't get activated the N effect what happens with C we can do the same thing at C we can say or you know we can     
1:59:16     
have an or logic gate here which is where you know either B is sufficient to activate     
1:59:23     
C or suppress C or the feedback is sufficient and then we can have     
1:59:29     
different outputs those outputs then can do different things they're in this space but they actually can drive     
1:59:35     
different behaviors on the outside in the outside world we can just classify them in this two-dimensional graph but     
1:59:42     
they can also do things in the world and so this is you know this is important in development because it's going to enable     
1:59:49     
certain structures to form Maybe certain behaviors to start and so forth so you     
1:59:56     
know this idea of Behavioral uh competencies comes from the idea that     
2:00:04     
Michael Levan has a cognition all the way down and that cognition from let's say like cells to uh brains is a     
2:00:13     
function of the competencies of that system so you know like bacterial cells     
2:00:19     
might have a very limited set of competencies relevant relative to the human brain but you can describe it in     
2:00:25     
terms of this set of cognitive things in this case what they're doing is they're describing it in terms of Gene     
2:00:32     
regulatory networks and so that's basically where we're going with this um     
2:00:38     
tutorial and then an Associated paper so this is a tutorial for this idea uh they     
2:00:45     
go through this tutorial in five parts uh part one is where we see how to     
2:00:50     
simulate biolog networks like I showed in the drawing that I did while applying     
2:00:56     
different kinds of interventions and orations this is where we introduce changes to the network changes to the     
2:01:02     
input and we get different outputs in part two we'll go over how existing approaches to perform automated     
2:01:09     
experimentation in these systems and discuss their limitations or purposes of constructing a behavioral catalog in     
2:01:17     
other words you can automate experiments you can go through all the different configuration ions and you can then be     
2:01:24     
assemble this behavioral catalog by seeing what the outputs do in part three we'll walk through the     
2:01:30     
implementation of curiosity driven approaches and show their usefulness for constructing such cataloges by mapping     
2:01:36     
the space of possible behaviors or what they consider to be steady States so     
2:01:42     
it's like all these points that you saw in the two-dimensional space are these steady state behaviors there may be     
2:01:48     
things that aren't steady state behaviors we're not really interested in those uh of the biological nwork so we we want     
2:01:56     
to know all possible behaviors but some of those are not stable some of those are not functional so they are not     
2:02:02     
really considered competencies and so we want to know in that space What are the     
2:02:07     
steady States in part four we'll walk through the design of an empirical set of empirical tests we've made to test the     
2:02:14     
robustness of the discovered behavioral abilities in part five we'll discuss some preliminary experiments showing how     
2:02:21     
the discovered behavioral catalog can be helpful to both a better understand the     
2:02:27     
latent functionalities and resilience abilities of study grn in other words     
2:02:32     
what you know we have this latent space in machine learning which is basically a similar thing where we have this network     
2:02:41     
and we have these you know different things at it up with these different categories and you know it's usually     
2:02:48     
like comparing a bunch of exemplars to a category and Laten space is just all possible     
2:02:55     
configurations of the things that's been trained of the outputs are generally a subset of that latent space and so this     
2:03:02     
this behavioral space is basically latent space where you have things in that Laten space embedded and then     
2:03:08     
that's your description and so that's what they're getting at with this late these latent functionalities there's     
2:03:15     
also this aspect of resilience and then two to develop therapeutic intervention so we want to     
2:03:20     
use this for therapeutic interventions to see what the outputs of a grn are in     
2:03:27     
terms of you know we were engineering a genetic circuit for a therapeutic intervention how would we do that how     
2:03:33     
would we enable some behavioral out outcome so basically how do we keep a     
2:03:39     
cell from going cancerous or how do we keep a cell um in a in a good operating     
2:03:46     
range so this this whole thing is just the tutorial kind of walks through the code gives you this uh this is uh let's     
2:03:54     
see so for this tutorial we will be studying the gene regulatory Network model that describes the influence of     
2:04:01     
rkip on the erk signaling pathway so this is uh described in this paper from     
2:04:07     
CH at all which is just basically uh mathematical modeling of the influence of R Kip or Kip on the irk     
2:04:15     
signaling pathway so this is just a paper that describes the system um this     
2:04:21     
this is a model system that you know we've identified and this is uh hosted on the     
2:04:28     
biomodels database so this is the reaction graph here as you can see there are a lot of feedbacks and uh other     
2:04:35     
types of things going on um and this is written in spml so you can take the spml     
2:04:40     
pars it and produce this bio model and then work with it in in Python and then you know do different     
2:04:48     
interventions get outputs so this is a conent ation of proteins in micromolar     
2:04:54     
this is a reaction time in seconds so you're running this network it's producing over time this output of     
2:05:00     
concentration of proteins in terms of micromolar concentration so you get this     
2:05:06     
for these different components of the network you're getting this different output so this is the way they do this     
2:05:12     
in here and then uh this is the simulation results for a default initial condition we have the trajectory nodes     
2:05:19     
of irk and of kkip RP is shown in transcriptional space so they show the     
2:05:25     
initial State and then the end point this is over time so it's increasing over time and then it kind of decreases     
2:05:31     
a bit this is in uh mic U uh micromolar concentration of arip and then this is     
2:05:39     
Earth which is also the micr concentration so you can see you can get these different outputs that are linked     
2:05:46     
to some sort of physical quantity and then you can compare them and the     
2:05:51     
competencies are basically you know what is the concentration output given the     
2:05:57     
path through the network what can it do and what can't it do can it produce an output that's deviates from these     
2:06:04     
functions probably not we need to characterize these functions and know what the competency of that part of the     
2:06:09     
network is so it's a little bit different way of thinking about we don't necessarily think about in terms of     
2:06:15     
cognition we think about in terms of information processing so this is this tutorial I'm not going to go through the     
2:06:22     
rest of it this is a different tutorial that's related to this Aid driven automated Discovery tools for synthetic     
2:06:29     
circuit engineering so what they're trying where they're going with this and maybe why Mike Len's involved as well is     
2:06:36     
to develop these automated Discovery tools for synthetic circuit engineering so when you're doing synthetic biology     
2:06:43     
you want to design circuits that allow you to produce controlled outputs so if     
2:06:48     
I'm you know working with a a bacteria colony and I'm designing a bacterial     
2:06:54     
circuit in a minimal cell that produces like some uh chemical at a certain     
2:07:01     
concentration in synthetic biology I can knock in the components to make that     
2:07:06     
happen I need to design a gene circuit that will allow me to regulate the production of that uh enzyme say in and     
2:07:14     
at a certain level I don't want to exceed the level I don't want to undershoot so I can do this in a way     
2:07:20     
that you know is basically by going through the network kind of knowing in simulation what the     
2:07:26     
competencies of that Network design is and then as you work it out in simuation     
2:07:32     
then you can take those components and engineer them in the circuit for the     
2:07:37     
that you're going to put into the bacterial cell and then you can get a population bacterial colonies and then     
2:07:43     
produce this more effectively so they go through a lot of stuff in this tutorial is kind of gives     
2:07:50     
you this uh so they you know they kind of go through some of the they always give references     
2:07:56     
to some of the things that they're talking about and then I want to go through real quickly some of these     
2:08:03     
papers uh so this is uh I think this is from the blog AI driven automatic     
2:08:09     
Discovery tools reveal diverse behavioral competencies for biological networks this kind of walks through this     
2:08:15     
is uh a description of this um this is the link to the interactive tutorials     
2:08:22     
but it kind of talks about some of the purposes of doing this many applications of biom medicine and synthetic bio     
2:08:29     
engineering depend on the ability to understand map predict and control the     
2:08:36     
complex context sensitive behavior of chemical and genetic networks the emerging field of diverse intelligence     
2:08:43     
is often Frameworks for which to investigate and explore exploit surprising problemsolving capacities of     
2:08:49     
unconventional agents so this is the diverse intelligences approach where we have these different competencies at     
2:08:56     
different layers of complexity so if you have bacterial cell it has a set of competencies that are different from say     
2:09:03     
like the human brain but those bacterial cells depending on the design of the circuit that you're working with can     
2:09:10     
give you a diverse enough set of outputs so that you can do interesting things     
2:09:15     
and you you know do this in a way that's uh applicable to systems that you're     
2:09:20     
engineering so these tools rely on two main contributions that we make in this paper     
2:09:26     
so the first thing is using curiosity driven exploration algorithms originating from the AI Community to     
2:09:33     
explore the range of Behavioral abilities of a given system so there's this tool called curiosity driven     
2:09:40     
exploration or curiosity driven search and this we've talked about this before     
2:09:46     
with respect to some of the stuff going on in aife where an open-ended system     
2:09:51     
where people have been looking at you know how do you guide an agent through     
2:09:57     
this sort of space this sort of possibility space or the search space     
2:10:02     
and one way is to use curiosity driven criteria so you're using curiosity     
2:10:07     
you're look you're investigating new things but you're you know not going doing a Brute Force search and you're     
2:10:14     
able to explore that space sufficiently without you know having to spend a huge     
2:10:19     
amount of time exploring every option so it's definitely a heris that we can     
2:10:24     
apply to these kinds of systems that we can adapt and leverage to automated discover the range of     
2:10:31     
reachable goal States at grn so we want to search that space look at the reachable goal States reachable meaning     
2:10:38     
things that can be reached in a certain amount of time or given the topology of that     
2:10:43     
Network and then two propose a battery of empirical tests inspired by     
2:10:48     
implementation agnostic Behavioral es to assess their navigation competencies so     
2:10:55     
this is again you know how do you navigate through this space our data reveal that models inferred from real     
2:11:01     
biological data can reach a surprisingly wide spectrum of steady States while showcasing various competencies that     
2:11:08     
living agents often exhibit and physiological Network dynamics that do     
2:11:13     
not require structural changes of network Properties or connectivity so this is again you know     
2:11:19     
uh we can reach a lot of states without like changing the network we just have this network we start with a starting     
2:11:27     
Network we start with an initial condition we let the the model run and we can get to these different behavioral     
2:11:33     
states without too much problem and you know we and we we we have a good method     
2:11:40     
here uh but furthermore we investigate the applicability of the discovered behavioral catalogs so these are the set     
2:11:46     
of assessible Behavioral States for comparing the evolved competencies across classes of evolved biological     
2:11:53     
networks as well as for the design of different types of drug intervention and Drug application networks or the design     
2:12:01     
of synthetic Gene uh Gene networks that we might use in BIO so this just kind of goes through     
2:12:08     
some of the references here this is the blog post and then this paper here I     
2:12:14     
think this is actually um a related paper which is     
2:12:19     
from Mike Lev but also Sebastian reesi Benedict harle Sebastian reesi of course     
2:12:25     
has worked on some things with respect to neural systems uh and neural cellular     
2:12:32     
autometa and some other systems like that really interesting but um so this is a paper     
2:12:40     
called The evolutionary implications of multiscale intelligence so this is where we're talking about using neuros solar     
2:12:46     
or automa in evolving sort of multiscale intellig these kind of     
2:12:53     
systems so I'll read through the abstract and then we'll end so I just want to give you a taste of this so in     
2:13:00     
recent years the scientific Community has increasingly recognized the complex multikill     
2:13:05     
competency architecture MCA of biology so this is kind of their trademark thing     
2:13:12     
where they have this multiscale complexity architecture you go from say a bacterial cell to a a eukaryotic cell     
2:13:20     
to to maybe like a a network of cells to an assemble Ed of cells to a brain you     
2:13:28     
know you can go up and you get these different competencies that arise from this so the MCA is comprised of nested     
2:13:35     
layers of active homeostatic agents each forming the self orchestrated substrate for the layer above and so it's a     
2:13:43     
hierarchical system it's a hierarchical control system and in turn relying on     
2:13:48     
the structure and functional plasticity of the layers below so the layers below then have this plasticity that can     
2:13:55     
respond to changes and so this all gets put together not just in this Gene     
2:14:01     
regulatory network but in other types of networks as well the question of how     
2:14:06     
natural selection can give rise to the MCA has been the focus of intense research here we instead investigate the     
2:14:13     
effects of such decision-making competencies so anytime there's a change in the network or the network has to     
2:14:19     
make like a an evaluation it could be a a logical gate it could be just kind of     
2:14:25     
like a signal a sign you know it's positive or negative those are decision-making competencies and it     
2:14:32     
depends on the type of network of an mca's agential components     
2:14:38     
of the process of evolution itself using in silico neuro Evolution experiments so     
2:14:44     
this is something that you know the idea that you can evolve neural networks this     
2:14:49     
is basically neuro EV Evolution there are different ways that people do this but basically you're evolving a network     
2:14:55     
or you're evolving a population in networks to get uh to form a solution to     
2:15:01     
get an optimized Network so this is not using energy minimization or uh error     
2:15:07     
minimization it's using sort of a an evolutionary approach um so you're     
2:15:13     
they're using these in silicone neur Evolution experiments have simulated minimal developmental biology so they're     
2:15:19     
using this minimal asp ECT and to build this minimal model they're using neural cellular autometa which is modeling the     
2:15:27     
process of morphogenesis so cellular autom is a grid of cells that are each cell has a     
2:15:34     
neural component in it and utilizing an evolutionary algorithm to optimize the     
2:15:40     
corresponding model parameters with the objective of collectively self assembling a two-dimensional spatial     
2:15:46     
Target pattern which could be like you know a square or it could be a diamond     
2:15:51     
or could be like the shape of a rabbit I think in this case they're using a lot of different basic patterns like rabbit     
2:15:59     
you know like a cartoon rabbit an outline of that or you know a snake you could use that and so they're able to do     
2:16:06     
this in in a cellular autometa which means that the cells in a grid light up     
2:16:12     
in that shape it's basically what happens where they get turned on and so uh there's the spatial Target     
2:16:20     
pattern which is uh considered reliable moreal Genesis uh Mike Levan and     
2:16:25     
Sebastian reesi have published on this number of papers in the past uh were on     
2:16:32     
the distill log which is still alive but they've done a lot of Dem like demos of     
2:16:38     
this so if you're interested you can go to distill blog and look up like neuros     
2:16:43     
or automa and there's a lot of work on or at least two papers on it that I know of furthermore we systematically vary     
2:16:50     
the ACC accy of which an nca's un unicellular agents can regulate their     
2:16:55     
cell State So within each cell they're regulating the cell State and they're usually doing this through um you know     
2:17:03     
regulating noise or the effects of noise buffering and things like that so again     
2:17:08     
our cellular automa is this grid that has each each grid has bunch     
2:17:15     
of cells and those cells individual cells     
2:17:22     
are have a neighborhood around them so this cell here has a neighborhood of     
2:17:29     
might look like this or might include the corner cells and that neighborhood     
2:17:34     
determines a state of focal cell but each cell in this uh grid has     
2:17:42     
its own state has its own autonomous process and it has some Network like     
2:17:48     
this that tells it what to do and it gets inputs from the neighboring cells which come into a and then the output is     
2:17:55     
the state of the cell and then that can inform the state of neighboring cells     
2:18:01     
and so the idea is that each cell is making an autonomous decision process it's being influenced by neighbors but     
2:18:07     
it's also doing things internally and it's producing a state and that state changes over time and so that's what     
2:18:15     
we're getting and we're getting from that a pattern that might be like you know some sort of wavy pattern or some     
2:18:22     
sort of shape that we can in these papers they often use a Target it's kind     
2:18:28     
of like the use a mask as a Target and they target certain patterns and then     
2:18:34     
they try to reproduce them so if you're looking at a wavy line like     
2:18:39     
this hard to simulate here but basically the wave would be something like this     
2:18:45     
you could do you could replicate that that mask through the behavior of the cell the evolution of this of of this     
2:18:53     
grid so that's you know kind of where we're going with this and so we demonstrate that an evolutionary process     
2:18:59     
proceeds much more rapidly when evolving the functional parameters of an MCA compared to evolving the target pattern     
2:19:06     
directly uh so again you know we want to use the MCA in this Evolution wherever     
2:19:12     
the evolved MCA is generalized well towards system parameter changes and even modified objective functions of the     
2:19:18     
evolutionary process thus the the Adaptive problem solving competencies of     
2:19:23     
the agential parts of our NCA based incal morphogenesis model which is that cellular autometa strongly affect the     
2:19:31     
evolutionary process suggesting significant functional applications of the near ubiquit is competency SE living     
2:19:39     
matter so that's quite a bit but that's what we     
2:19:45     
have okay so looks like Jesse had the link and Paul had to leave uh post all     
2:19:51     
this on the uh well with the video but also in the     
2:19:58     
SL y yeah it's great great stuff I     
2:20:03     
I think we talked about developing system.org before but um but this paper     
2:20:12     
is is really interesting to see this week     
2:20:17     
um well as you can tell I got a cold uh um     
2:20:23     
but this week was sinbi beta yeah and um     
2:20:28     
so this is a big synthetic biology meeting that um yeah brings in a lot of     
2:20:37     
um it's not like so much a science meeting they can see it's it's I mean     
2:20:44     
it's got a lot of Industry people as well as Finance     
2:20:49     
people looking for for startups in a kind of JPM Healthcare kind of meeting     
2:20:55     
way but um but it it was really     
2:21:00     
interesting hearing about the um the challenges that synthetic bio has in     
2:21:09     
terms of you know especially trying to to uh to do the kinds of things that you     
2:21:18     
you know you might think oh well we been able to do you know drop in plasms and     
2:21:24     
get them expressed and you know whatever you want um uh these     
2:21:32     
these pipelines if you will aren't still incredibly     
2:21:38     
productive and and being able to and the tools I can see now the tools     
2:21:46     
aren't there to do kind of good in silico you     
2:21:54     
know U simulations for how to improve them and and that's you know like like     
2:22:01     
you're really really hitting up against you know like just where computational     
2:22:07     
systems biology is right now you know and and so it was interesting to to     
2:22:18     
um to see is interesting to see this and just be reminded you know again like     
2:22:24     
like I can I can talk a lot about the particular software tools like they     
2:22:29     
they're using spml and and bringing things into Jacks but     
2:22:37     
um uh um that that's not you know like like     
2:22:42     
that's not the the the kind of how you're GNA do yeah the Curiosity driven part of     
2:22:51     
that is the really interesting part yeah you know and and I I I thought some of     
2:22:57     
the most interesting work um again kind of related to things that maybe only     
2:23:04     
like gko can do at scale but is kind of this this automated automated     
2:23:12     
um it's like automated lab driving and and what they mean by that     
2:23:17     
is is you know computers are directing um different experiments you     
2:23:25     
know and as exper as experimental results are coming in then then the     
2:23:31     
model is adapting those to like okay now we're going to do a set of experiments     
2:23:37     
that we're going to be changing this or we're going to be you know looking at the the the um yeah just the parametric     
2:23:45     
results of of this and um     
2:23:50     
and that you know it's such a such a large such a high dimensional space yeah     
2:23:57     
that that they need they you know they need to be efficient but they and and     
2:24:03     
and like um yeah have to have a much better idea of where they where they     
2:24:10     
should be looking next yeah yeah and that's that's really interesting and and it's     
2:24:16     
really it's interesting well so just the last thing I wanted to say is that there's going to be a a lab uh there's     
2:24:23     
gonna be a journal club today 3M Pacific time um with the the     
2:24:30     
cortical Labs Discord group is is um is running a journal Club this afternoon     
2:24:37     
they're gonna focus on the organoid intelligence paper oh okay which is this the the big one from kind of M it's you     
2:24:44     
know it's a real multi U multilab paper right right     
2:24:51     
and one of the things that they're talking about is just how well human brains do exactly what we're talking     
2:24:57     
about in terms of uh with with a small number of samples they seem to know     
2:25:05     
where to go uh uh how to yeah how to how to learn     
2:25:10     
from a very small number of samples right and and to navigate a a very high     
2:25:16     
dimensional space and comparison to you know how many games of     
2:25:23     
go um Alpha go needs to play to to to beat human players for instance yeah you     
2:25:30     
know um as as just one example this is this is this is really     
2:25:36     
interesting um and uh I think well just     
2:25:41     
wanted to one last thing would would love to cover and maybe could get us     
2:25:47     
someone to to speak on this if we don't have something but Active Learning and and     
2:25:55     
you know because that that's the most recent um kind of proposal or     
2:26:03     
uh topic name that I've heard that that tries to you know computationally get at     
2:26:12     
that that aspect of of human cognition that that they're talking about in the     
2:26:18     
organized intelligence paper this this ability to learn from very small     
2:26:24     
samples uh um and yeah yeah and you know     
2:26:29     
and may you know with with the luxury of time we can go through the foundations     
2:26:35     
of complexity SCI yeah yeah and maybe maybe get more ideas uh um but um but     
2:26:43     
would love to cover um well just just yeah this is uh but and let's not forget     
2:26:50     
that Sebastian reesi I think is also the author of the um the work that Sarah     
2:26:58     
presented in terms of um llms I believe right like AG agent based model Yeah     
2:27:05     
well yeah there they they do a lot of stuff with that like uh right yeah right     
2:27:11     
right anyway really really interesting yeah thanks yeah all right so that's it     
2:27:16     
for today and let's keep going on slack and some these other topics and see you     
2:27:22     
next week thank you take care take care bye     
