## Meeting Recording

[YouTube link](https://youtu.be/x_XHuhXyk-Y?si=KiIutWKRH9vcEluD)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113297475044418213)

## NOTES:
Jesse: updates -- workshop planning. Blogpost on teleology paper (will submit to Medium).

* areas to edit, review. Cybernetical references.

* behavior relative to functionalism. Functionalism philosophy paper.

* Levin's motivations. TAME -- relation between agent and environment.

* Krakauer -- teleonommic matter. 


Machines designed with purpose (signal from the goal, selection of a goal).

* not all machines are selecting (toaster vs. robot).

* is a clock constantly interating over states? Probably not.

* prediction --> time, space coordinates.


Emergent --> BVs are not teleonomic, but phototaxis are?

* function due to structure, teleonomic --> selection of actions (control theory).

* Krakauer's complexity science -- Fuchs as well.

* good stuff in the #cyb-rg and #cognition-futures channels. Good papers here.


"New Biology" set of texts (what do they look like?).


MATLAB package from the 1990s. Contributions have moved on, Octave is both open and transient.

* center of Open Neuroscience (.org). 

* Levin speaks to collective intelligence view. New way to look @ synthetic biology.

* James Glazier --> "Systems Biology from a Network Perspective". ODE version of this paper.


Multiscale modeling course (EMBRIO). Genetic circuits from Caltech.

* Immunology --> agential material --> multicellular.

* Glazier's weekly seminar series (12 Noon PST). GLIMPRINT.org --> prediction and intervention.

* weirdness of immunology. "Do microbes have immune systems?". Brains in single-cell organisms.


Redundancy -- one factor, many effects, compensatory.

* need to engage with UAlbany more. Upcoming research event.

* what is mechanism? 10 people interviewed.

* emergent complexity --> "More is Different" (Anderson, 1972).


Frontier Maps -- essence of connecting people to these challenges.

* reason why easy stuff was done first.

* follow up from 1943 paper. 


Morgan's philosophy is "neural". 

* Celsius --> get into protein design.

* Alphafold --> decades-long protein-folding efforts.

* people have moved the goalposts --> maybe protein prediction wasn't a huge barrier after all.

* possible from data sorted from othe groups.


Language models were first break through because of ubiquity of data.

* Daphne Koller -- start a biology company. Not just trying to do a foundation model. 

* UK Biobank, but it is only one dataset (data is sparse and expense).

* biology needs an internet scale of UK Biobanks.

Mechanism of Life >> Syntax of Language (MoL is more complex than SoL).

Next set of problems --> docking, protein shape is probabilistic (what's computationally/conformationally stable).

* "Attention is all you Need" --> Aidan Gomez et.al --> 


Peer Review is a deeper social problem --> managing differences in expectations that comes from peer review.

* also not appropriate to treat as fraud detection, should be collaborative.

## TRANSCRIPT
     
Transcript     
0:02     
hello good morning morning how are you getting started still need my coffee     
0:11     
okay so welcome um so this week we had     
0:16     
uh of course our Eva worm meeting and in that meeting we talked     
0:22     
about actually the Nobel Prize that was awarded for physiology and medicine and it was given out for micro     
0:30     
rnas and it was two SE elegans people who won it and then they worked on SE elegans in the context of winning their     
0:37     
prize so that was interesting and then that was Monday and     
0:44     
then Tuesday and Wednesday we had two AI related Nobel prizes so that was     
0:53     
interesting it's pretty I guess it was pretty controversial we'll talk about that     
0:58     
today um and then Friday we had an organizational meeting on uh the ACT imp uh Symposium that's     
1:08     
coming up so specifically this is for open source and open     
1:14     
science so you know we're trying to do this uh session in conjunction with the active     
1:21     
inference institutes upcoming Symposium this is the one on November     
1:27     
13th or 16th and we are getting uh ready for     
1:32     
that so I sent out a document I think to Jesse and Morgan um primarily although     
1:40     
anyone's welcome to join in we're organizing speakers we're organizing     
1:46     
events uh we're just trying to make this useful to people who maybe aren't as     
1:52     
exposed to the stuff as we are because our group has a dedicated uh you know     
1:59     
meeting space for that we have programs and you know we we have we talk     
2:05     
about time and in not every you know people don't talk about this in every group it's just kind of     
2:13     
a a topic that you know we we've talked about how some groups have tried to approach it and but it's it's um well     
2:22     
we'll talk about that also today about like how people think about open     
2:27     
science and you know really it's about practice and it's about sort of the the ideas or maybe     
2:36     
even I don't know if there's any Theory but it's basically you know a lot of     
2:41     
practice and so that's part of a big part of it and so I don't know if we're     
2:47     
going to do any tutorials or if people are interested in that but that might be useful although     
2:54     
on the other hand you could make the case that it's not useful and we should just kind of give people the information     
3:01     
and they can because it's not like you know you it's particularly hard to use some of the tools that are out there but     
3:09     
anyways so that's uh what we had this week um terms of     
3:16     
meetings um so I guess any I guess Jesse do you have any     
3:22     
updates excuse me good morning um nothing like amazing um I didn't get     
3:31     
to go to the Friday meeting and um I am curious about that and     
3:36     
everything else so uh I I kind of missed a little bit of your recap now too but I saw the work     
3:44     
the work work sheet you put together and I'm excited to talk more about that and think more about that     
3:51     
um on the whole this week it was uh I was basically traveling a lot this week     
3:58     
to take care of and things and uh I have returned to my     
4:05     
normal um that is really the first day of     
4:11     
being in my normal routine again so I'm looking forward to kind of being able to     
4:17     
sit down and push forward on certain things um on a side     
4:22     
note I'm very close to submitting uh     
4:27     
a I don't really know what to call it I guess it's will be a blog post on the     
4:33     
chology paper and when I do I would I wouldn't mind if you look it over     
4:41     
to there's some there's there's some areas you could just um like edit or review and then     
4:48     
also um I'm I've kind     
4:55     
of I'm sorting out what to do next and I think this is something that I'm going to continue to     
5:01     
follow um by happen stance um a colleague of mine is also     
5:09     
referencing some cybernetical things recently and we had a somewhat     
5:15     
serendipitous talk about them and I really want to show them the final product uh so I'm I'm almost there and     
5:22     
it's not I don't think they I don't think it's going to be super relevant to what what they want but more like um     
5:30     
uh I know this paper is something     
5:37     
that has just a lot of Pious and different things um that that that have     
5:43     
you know it's a really interest the more that I read about it look at the history     
5:48     
of it like it's a really interesting paper in terms of implications     
5:53     
for all the stuff we looked at in the verel quest line and embodiment     
6:00     
because the way they're situating um     
6:05     
chology and what they call Behavior relative to functionalism is really is really um     
6:13     
this this thing that one yes it it it challenges this longstanding you know     
6:22     
um sort of the sort of uh purpose theological Divine mystical you know     
6:29     
that that's a big a big longstanding you know Arc of the the the previous     
6:37     
billennium is that's like huge huge thing um but but more specifically um     
6:44     
the the mechanization focus and the fun the functionalism of and what causality was and and and and the there there's     
6:52     
very small um the more I read the paper the more I see like the more I understand some of Len's     
6:59     
like act motivations in in that whole branch of like biology or developmental or     
7:05     
whatever theoretical uh takes on biology and where he's going with his ideas but     
7:11     
then also just the relation between an agent and its environment and essentially like going through to     
7:19     
um what we call what what I guess David krackow you know his view of complexity     
7:26     
science and his kind of shift as taking complexity signs to mean um teleonomic     
7:33     
matter right and like why like I've been like this week I've been thinking a lot about okay like they're very clear that     
7:41     
you know I've looked at I've been thinking about the commentary on they explicitly say you know some people say     
7:48     
that all machines are are full you know full of purpose are designed with a purpose it's like well let's let's let's     
7:56     
let's take that sentiment rela to what they're getting at and they're really getting at the nature of purpose as     
8:02     
being a selection of a goal by an Indy and having to get feedback from that     
8:09     
goal like if I like and I'm really curious because there's some critiques of the paper that I want to explore and I wonder if they get into this but like     
8:16     
what do they mean by signal from the goal and it's it's kind of interesting     
8:23     
because it it the way they frame things intentionally or not is this very interesting     
8:31     
um it's a very interesting way of designating their like their scope the domain of what they're concerned about     
8:37     
relative to um you know     
8:43     
uh all all machines they said you know all maches on purpose because all machines aren't selecting you know     
8:48     
they're aren't having to make this choice they they they they they they I have a nice way of referencing even like     
8:55     
a clock and and and there's some things that I was thinking about in terms of the paper terms of like discreet versus     
9:00     
continuous and end States versus not having end states are you simply reiterating a process are you are you     
9:07     
going forward and at what level like like is there is there a way you know     
9:12     
it's fun to explore that space of okay well is the clock you know     
9:18     
yes could could you argue that a clock is just constantly doing iterating okay     
9:23     
next date next date next date next date or not and I think there's reasons why like that that doesn't work and why     
9:29     
there are arent does hold but it's really interesting to consider that relative to the way they talk about     
9:34     
prediction and prediction requiring uh multiple coordinates one a Time coordinate one has to be a spatial     
9:41     
coordinate and how like the variation like there there what they're doing in     
9:46     
terms of associating the selection and the selection of a goal     
9:51     
not just not just a movement but the selection um and how the selection is     
9:57     
tied to things in the world that are perhaps one would say     
10:02     
in modern day complexity science emergent um but but you know it's before     
10:08     
that so it it's just been really fun to like really really really continue to like there's so much juice to squeeze     
10:16     
from the fruit on the paper um for me anyway I don't I don't necessarily think that everybody loves the paper the way     
10:23     
that I'm I'm I'm going into it but like it's been really fun it's been really rewarding to like situate     
10:31     
um a lot of the things we've already done with the paper and what I'm writing so far isn't doing that I'm just have I     
10:37     
have a couple like at the end I'm going to have a little bit I might even mention the renb vehicles just because     
10:42     
it's not Bren Vehicles aren't uh tonic at least in in the way that     
10:50     
they're being described here they mentioned photo like they exclusivly mentioned photo taxis and brenberg you     
10:56     
know wrote this stuff like 40 years later but but you know the the Merit of     
11:04     
the vehicles being like really simple structures with slight changes can do these really complicated looking     
11:10     
behaviors and so it's interesting justos from like functionality and and how things are the     
11:16     
structure and how things are arranged versus all the toonomic all the purpose     
11:22     
what is purp what is purposeful Behavior voluntary you know the importance of voluntary selection in the behavior um     
11:29     
and what does that mean you know so it's kind of a nice check there and obviously L which is like like you can when you     
11:36     
read the paper a few times you could just see like oh here's like this is L like just taking out     
11:43     
these paragraphs and making a big paper about it it's like okay cool it's like     
11:48     
well I do that I could do things like that too you know it's like it's like it's like seeing some of the the the     
11:56     
the uh what I don't know it's like it's     
12:04     
like seeing different kinds of work being done in     
12:09     
papers um is is is very it's an appealing part of this and then     
12:14     
obviously so fukes um there I was going     
12:19     
to say 11 and 11 in Bard paper but a lot of 11 F always for this thing and I I     
12:25     
get I get why like I understand and even even though like even the way that the     
12:31     
authors Rosen Bluth and Co SE like did things to separate out     
12:37     
for what like The more I've read the paper The more I've understood why like     
12:43     
why did they separate out to get to prediction and higher orders of prediction because at first past it was     
12:49     
a little bit obscured to me like why but now it's like I'm getting more and more and more as why they're doing that and     
12:56     
it it fits really well with like a lot of Le what he's to separate out for two in certain ways like I get I get that     
13:02     
part of it so you have that you have I mentioned David KRA hour a few times and     
13:08     
and his like I don't know I don't yet know what to make of his stuff I haven't gotten further into anything from him     
13:14     
that's on the docket um but I'm curious where he's going with what he calls quote unquote complexity     
13:21     
science um and the T anomic matter and then then I'll um I also put you know     
13:29     
ukes who's like very much um you know he spent a lot of his time railing against     
13:35     
reductionism and and has his particular take on it from ecology of the brain book so it's interesting to kind of see     
13:42     
all those things kind of related to this paper to me um and and I'm not at the     
13:49     
end of what I'm writing which I'll I'll send it to you soon um it's not like I'm     
13:56     
going in depth um it just like a couple senses for those other authors but     
14:02     
like as I'm finishing the things up and like putting stuff out     
14:07     
into this paper it's like I'm I'm quite curious where where     
14:13     
to go next and I think I'm really looking forward to our meetings next week and I'm dis I'm I'm I'm not     
14:20     
disappointed but like I I had really wanted to attend all all the ones this week myself but it just wasn't going to     
14:26     
happen because there's so much stuff on my mind about it and um I I think that'll be the best place     
14:35     
to discuss it but I'm I'm I want to continue on the path from here both sort     
14:40     
of like uh even even maybe just kind of doing I think maybe for either Wednesday     
14:48     
or Thursday whichever one we meet at I might try to just go over this paper or this blog post that I'm writing but then     
14:55     
specifically kind of Trace out like almost do like expand a little bit on     
15:01     
what I just said Con to the other authors and stuff because I I'm curious about that and there's     
15:08     
been a lot of there's been some good links posted in in in both the cybernetics channel the the reading     
15:15     
group Channel and and conition Futures that I really haven't gotten a follow up on and I     
15:21     
know um there was the one about like mechanism I don't know if you're going     
15:26     
to talk about that today later linkoln stuff but um I'm looking forward to that too so that's that's basically the     
15:34     
update um also shout out I know I think it's a little bit older but um shout out     
15:40     
to um well was it last     
15:46     
week yeah well I think it was it was last Su shout out to Sara uh for presenting at at Google I had to say     
15:53     
that earlier and I I read I reposted that on LinkedIn but I'll make like that's be really nice to celebrate um I     
16:01     
don't know if she's going to write a post I she's done a bunch of posts on medium but like um congrats to her and     
16:06     
everybody else too um for Google summer code stuff so I wanted to say that um on     
16:14     
a on a slight on a slightly different admin note um I I was supposed to have a um I     
16:21     
haven't been able to engage you Aly as much as I wanted to over the last week so um I've had had a lot of things come     
16:28     
up so kind of unfortunate about that but there's there's another event um like a     
16:33     
research event happening at the end of this month that might try to get us involved in some my um so I need I'll be     
16:40     
following up with that too but um that said um my Outlook is I'm enthused     
16:46     
because I think I've I've cleared up a lot of things uh I'm you know I mean my     
16:51     
courses have begun but I'm taking uh a lighter course load much lighter than last semester term uh which is nice but     
17:00     
still there's some stuff to do uh but I think I think the end of this year I'm really going to have a lot of zeal to     
17:08     
push forward on some things and I feel good about that so that's my um that's     
17:13     
my update good thank you all right so I have a couple of announcements uh     
17:20     
regarding our medium and our YouTube channel so Jesse had mentioned that Sara     
17:26     
presented at the Google summer of code contribut compers uh conference uh and she     
17:33     
presented on like a short lightning talk on her project     
17:39     
so it's on our YouTube channel we have uh this video the agent based world of     
17:45     
Open Source Community sustainability um and this is I guess     
17:50     
about three and a half minutes so it's a lightning talk and you know check that     
17:56     
out if you're interested in going over her her project and seeing what she did     
18:01     
especially in the context of what we were doing with open source sustainability or what we've been doing with it I I think it's a good one um     
18:09     
then she also has this demo this was a couple weeks ago this is the large language model powered agent based model     
18:16     
for open- Source Community sustainability this says 92 views this     
18:21     
has just kind of been posted so but these two videos go together if you're     
18:27     
interested in looking at over that project and then of course uh sar's also     
18:33     
posted a number of posts on the medium so this is their medium uh she     
18:39     
posted a project report on August 24 and a couple of posts like the project     
18:45     
midpoint Milestones the building blocks uh looking at the beginning of     
18:52     
her coding period so she has like three posts from the Summer where she goes through the process of G     
18:59     
and then this final presentation or project report so if you're interested     
19:04     
in the project if you're interested in large language models and how you can apply them to social simulations if     
19:11     
you're interested in open source and open source sustainability that that sort of thing is     
19:16     
good okay that's needless to say that's going to be part of what we present to     
19:22     
uh uh active inference but anyways okay so this is the next thing I     
19:29     
wanted to talk about so Jesse uh saw this in the cognition     
19:34     
Futures Channel and I I posted it in there and he said will you present on     
19:40     
Saturday or can we talk about on Saturday and I said yes so this is again from the     
19:45     
transmitter which is a nice um I guess it's a Blog of Neuroscience content so     
19:52     
we talked about a transmitter article last week and this is uh another good     
19:57     
transmitter article so they're kind of like the nature of blogosphere or     
20:03     
something like that anyways um what are mechanisms unpacking the term is key to     
20:10     
progress in Neuroscience this is by Danny Basset and Lauren Ross and this is um you know talking     
20:18     
about mechanism something we've talked about in our uh cognition Futures group     
20:24     
a lot we've also talked about it in our cybernetics group a bit     
20:29     
but mechanism of course is something that we always talk about in Neuroscience if we want to know like how     
20:36     
something works we call it a mechanism um you know if you want to get a grant from the NIH you better better     
20:43     
talk about mechanism even if you don't know what mechanism is you better talk about it so mechanism of course has this     
20:50     
machine metaphor aspect to it which it means that you know a machine is a mechanism like a door has a     
20:57     
wch uh you know a door handle has you know a lock has like tumblers in it     
21:03     
things like that so the mechanism in the brain would be how does memory work and     
21:08     
then we would look for specific cells that are involved in in coding memory     
21:14     
and retrieving memory or networks that retrieve memory we might look inside those cells to look at the U Action     
21:21     
potentials being generated by them or the molecular contents and so you can     
21:26     
see that in a in a sense mechanism is the sort of reductionist exercise where you're always trying to drill down to     
21:33     
the the fundamental mechanism which is whatever it is that you know maybe it's like flipping a switch or it's like some     
21:41     
simple thing that we can grasp and we could isolate and do experiments with to     
21:48     
show this specific thing trigger say a memory so there's been a lot of work     
21:53     
with uh in mice on uh reversing memories     
21:59     
or reversing the encoding of memories and people have done this with different proteins and neurons where they've uh     
22:07     
basically knocked out the protein or they've silenced the protein and they've been able to uh you know basically     
22:15     
reverse memories now that's a good example of a mechanism there other     
22:20     
examples of mechanism like in motor control with different parts of the     
22:25     
brain um and we'll talk later in the meeting about cerebellum and how you know they're     
22:32     
different cells responsible for different things they different fibers responsible for     
22:38     
timing and those are all maybe seen as mechanisms so uh this article they asked     
22:45     
nine scientists to weigh in on what mechanism means so this is one these uh     
22:50     
articles where they try to get a consensus if possible to figure out what mechanism actually means and you'd think     
22:57     
like we' know but we don't and that's kind of kind of a problem I think um so     
23:05     
you know the way these they put this mechanisms are often viewed as causal systems which helps explain their     
23:12     
Central role in Neuroscience causes are factors that control predict and explain their     
23:18     
effects giving us an understanding why things happen and a way to Target future     
23:24     
outcomes identifying causal relationships and systems is necessary to understand the natural world and the     
23:32     
brain is no exception and why we're interested mechanism of course is Undercover     
23:37     
uncovering the causal structure of the brain so now just to throw in another     
23:43     
word that sometimes people misunderstand we have the word causal and of course     
23:49     
causal you know when we look for relationships in Neuroscience we look for you know relationships between     
23:55     
things you know we can have things like associations we can have things that are     
24:01     
correlative we can have things that are sort of you know maybe Loosely related     
24:07     
but not tightly related in other words they might be in association but they're not you know if     
24:14     
you manipulate one or if you manipulate the other then that relationship falls     
24:19     
apart now in the case of causality you have you know there are all sorts of     
24:25     
different ways that people have tried to figure out what cause out is one big uh     
24:31     
feature of causality is this idea of intervention where you're intervene to     
24:36     
sort of test you know the causal relationship to test it under you know     
24:42     
certain conditions you do controlled experiments and you manipulate uh the variables and you     
24:48     
intervene and you see if those when those relationships hold and when they don't we often repeat our experiments to     
24:55     
show that that causal mechanism is consistent over a large number of Trials     
25:01     
and so that's where we get uh stat statistical significance     
25:06     
from and we also have uh red like sort of uh counterfactuals so we can create a     
25:14     
situation where something occurs and then we create a situation where it's not there and so we have these     
25:20     
counterfactuals that we can use to uh sort of strengthen the case for something being     
25:26     
causal so you know we we have mechanism we have causality causal mechanism and     
25:32     
that's sort of the gold standard of things in the brain apparently so a mechanism isn't just a     
25:40     
CO common causal Concept in Neuroscience it is often viewed as the causal concept     
25:45     
required to understand the brain that end funding agencies including the National Science Foundation National     
25:52     
Institutes of Health and top science journals often refer to mechanism or     
25:57     
mechanistic findings to determine what research they should fund and publish it's clearly a status     
26:03     
term of Neuroscience of course and so but we don't know exactly what they mean     
26:08     
so first of all let's think about maybe how you know causality     
26:15     
is sort of referred to in terms of the bringing proper so you know standard examples of     
26:23     
mechanisms are neuronal firing gene expression and antibody production all     
26:28     
of which fall at the molecular and cellular so this is where we're going drilling down into like these levels of     
26:37     
organization as opposed to looking at say like a brain Network or something more closely tied to behavior and we're     
26:44     
using this as sort of the mechanism so the mechanism is that some Gene is upregulated a protein is produced that     
26:52     
has an effect on a neuron that has an effect on a network in fact and then it     
26:57     
has an effect on Behavior and you can do that but you know we know from like the studies a lot of the the     
27:04     
studies of uh you know different diseases we know from     
27:11     
Psychiatry that we can have a lot of canidate genes or some like depression     
27:16     
or some other uh you know thing that the brain does and it really makes it no     
27:24     
clear as to what the actual mechanism is or what how much those genes contribute     
27:30     
to the overall thing so just because you go to you you use reductionism you try     
27:35     
to find those mechanisms does not mean you understand the phenomenon and then for other     
27:41     
neuroscientists mechanism also refers to macroscale causal systems such as causal     
27:47     
circuits topologies and networks so some people just say we want to get things that are at the systems level and you     
27:54     
know find mechanisms there those mechanisms are may be more relevant to     
28:00     
behavior say so we're interested in Behavior everything below the the sort of systems level washes out or maybe     
28:08     
isn't as important as the causal mechanisms at the systems and so the systems level picture     
28:17     
mechanism includes higher level causal structures which are more abstract and have spatially distant causes so we     
28:24     
think about like a network we have you know maybe different parts of the network you intervene in different parts     
28:30     
of the network you knock down like you know uh function you silence parietal     
28:38     
areas or frontal areas and it has an effect on the rest of the network and     
28:43     
you know you can intervene there and you can establish sort of the causal mechanism of shutting down that area and     
28:49     
its effect on the network and the Behavior Uh but it's more abstract in     
28:55     
the sense that we don't know all the sort of underlying components and in     
29:01     
fact those may be very different every time we do it not very different but you     
29:07     
know such macroscale systems include Network and neuronal connectivity explanations of efficient signal     
29:14     
transmission circuit Motif Explorations facilitory and other complex     
29:20     
behaviors simulated lesion analysis and brain connectivity explanations of     
29:25     
disorders and diseases and so what is the problem with different uses to the mechanism concept     
29:32     
you know maybe it's just two ways to get at the same thing but this is a problem     
29:37     
because making progress in Neuroscience becomes significantly harder when the term mechanism lacks a clear consistent     
29:45     
meaning so you know they offer some suggestions on how to clarify all     
29:51     
this in its current usage mechanism resembles a suitcase like word phrase     
29:57     
Mar Marvin Minsky coin to describe terms that house a multitude of diverse entities Minsky claimed this was the     
30:04     
case with words such as emotion love and intelligence Each of which is a catch     
30:10     
all expression for a variety of things so you know a suitcase word means     
30:17     
nothing by itself but it holds a bunch of things inside that you have to unpack     
30:22     
and it's often used to conceal the complexity of a very large range of different things whose Rel relationships     
30:28     
we don't yet comprehend and so um as the way Daniel     
30:35     
Dennett stated there is no such thing as philosophy three science there is only science whose philosop philosophical     
30:42     
baggage is taken on board without examination so this is a a quote that     
30:47     
kind of applies here because we don't necessarily think about the philosophy of causality and yet we use the term and     
30:54     
you know it always has different meanings or meanings are CLE so that's kind of     
31:00     
the the the take of the authors now they have different people here that they've     
31:06     
interviewed um so this is Amy erston and the question was how was the     
31:13     
notion of mechanism used in valued your subfield and talking about you know this     
31:19     
is a lab where they study the molecular uh bases of cognitive Neuroscience learning how molecular     
31:26     
events influence the connectiv ity of higher orical circuits that generate cognitive     
31:32     
operations and so kind of talking about that sort of unique challenge is the meaning of the term     
31:39     
mechanism used differently in these two different cultures the dictionary definition to mechanisms is identifying     
31:46     
causal relationships um and you know from where we stand this fundamental meaning is     
31:51     
retain in the molecular and cognitive subfields uh we see mechanisms all the     
31:57     
way down down that's analogous to this ideaa of turtles all the way down which means that you keep going down to     
32:03     
different levels of organization and you keep finding you know you may find a mechanism but you may find some smaller     
32:10     
component or you may find things that are sort of unclear so you need to go down to a lower level still we talked     
32:18     
about this with the um Grandville paper on black boxes so if you remember the Granville     
32:26     
paper where we Ted talked about how every black box or every uh white box     
32:31     
has two black boxes inside of it where you know we have we start with a black box and we understand what's in the     
32:38     
black box so we have a white box it's a transparent box but even when we     
32:43     
understand that mechanism and what's inside of it we still have parts that are black boxes so we still have     
32:50     
components that we may understand how the components fit together how they     
32:55     
kind of operate together but then we still have those black boxes that we have to drill down and explore some more     
33:01     
so it's just kind of like this endless sort of exploration of black     
33:07     
boxes uh the expansion and Divergence of the molecular versus cognitive subfields has weakened our ability to understand     
33:14     
the details of these mechanistic relationships so uh you know without     
33:20     
this knowledge research is often dismissed by reviewers and editors is not     
33:25     
mechanistic so basically what they're looking at is how mechanisms in     
33:32     
Neuroscience are often about alterations and connectivity at all different levels     
33:37     
altered cognition caused by changes in the connectivity of circuits such as correlations and functional MRI old     
33:44     
signals altered circuit connectivity caused by changes in molecular connectivity such as the opening of     
33:51     
potassium channels or a synapse weakening its effects and the alterations and ion channels open state     
33:57     
caus by changes in the connectivity of atoms such as a phosphate group con connecting to an ion Channel rather than     
34:03     
to an ATP so that's kind one take on this     
34:08     
Andre Fenton from New York University how is the notion of mechanism used and     
34:14     
valued in your subfield um this person Works across subfields and kind of thinks about the     
34:21     
way different ways in the in the domain of memory science or learning in memory     
34:27     
uh how these terms are used across these subfields so they for example combine     
34:34     
experiments with molecular mechanisms of memory persistence and neuronal network     
34:40     
mechanisms of spatial information processing so mechanism in this case     
34:45     
refers to how it works and if you figure out how it works it constitutes mechanistic     
34:52     
evidence but those two things are very different at distinct levels of biological organization     
34:59     
so you know you have say for example uh the ability to pinpoint     
35:05     
structur and enzymatic changes that are crucial for initiating and maintaining long-term     
35:11     
potentiation uh elucidating these distinct molecular mechanisms of initiation and maintenance relied on     
35:17     
causal manipulations incling pharmacology pharmacogenetics optogenetics and     
35:23     
genetic manipulations so you have to use different interven ions to get at that     
35:28     
causal mechanism it may be pharmacological it may be optogenetic it may be some sort     
35:36     
of genetic manipulation and so all those things may give you different answers or     
35:41     
they probe the mechanism in different ways and so this is you know but this is at this level now if you look at the     
35:47     
network level you may use different manipulations you have different     
35:53     
insights and so unfortunately how well causal manipulation work depends on the     
35:59     
nature of the system not merely the Ingenuity of the experiment uh causal manipulations may     
36:05     
be an ineffective approach to elucidating network mechanisms in large part because biological neuronal     
36:11     
networks are complex systems with layers of redundancy and feedback so this is interesting that you know we're bringing     
36:18     
in this these ideas uh from almost you know I guess they're consistent with cybernetics we have redundancy and     
36:25     
feedback we have these complex systems and you know we haven't talked about that yet we've talked about     
36:31     
interventions we've talked about really you know drilling down and finding fundamental relationships we' talked     
36:37     
about networks but we've talked about it in a way that's been kind of you know     
36:42     
trying to see you know what a mechanism is instead     
36:47     
of saying well you know these are complex systems with different layers of redundancy and feedback and of course     
36:55     
saying something is complex on its own is isn't really an answer to anything but if you understand some of those me     
37:01     
you know redundancy and feedback mechanisms they look different than say like a mechanism that or like a a     
37:08     
fundamental mechanism that we might recognize in modern Neuroscience so if you look at Gamma     
37:15     
oscillations in memory you can see that activity in the medial inter rinal cortex promotes slow gamma over     
37:22     
mid-frequency gamma oscillations part of the hippocampus and that this activity     
37:27     
triggers recollection although the electrophysiological phenomena are part     
37:33     
of how recollection Works recollection mechanisms are likely redundant so when     
37:39     
you try to manipulate slow gamma oscillations the network almost certainly compensates in an attempt to     
37:45     
prevent a complete collapse of the biophysical origins of gamma oscillations and Gamma oscillations     
37:52     
contribute in fact to more than just one recollection or more than just recollection itself so all these me all     
38:00     
these things that we're trying to understand maybe have multiple roles     
38:05     
in the system and so when we try to intervene maybe shut one Mech or one     
38:10     
factor down other things come to compensate for it so we can't really establish a     
38:17     
mechanism it's a really nice Insight um and so oh John crock hour not the     
38:25     
crock hour from Santa Fe but he's actually one of the people who did the     
38:30     
uh the uh Cafe uh CA Neuroscience Cafe on YouTube that we've talked about     
38:37     
brother yeah yeah oh and is that aren't they Brothers I don't know     
38:44     
maybe it's possible Oh I thought I I I always assumed that they were oh uh uh maybe     
38:52     
not I'll check we can be this guy has a very thick British accent and I don't know about     
38:58     
The Croc hour from Santa Fe but gotta yeah gotta     
39:04     
um well anyways uh John Croc he works on um motor contr or sensory motor behavior     
39:11     
and things like that um so basically saying that you know     
39:19     
neuroscientists really don't care about the philosophical literature but are nevertheless convinced that proper explanations of     
39:25     
behaviors generated by the nervous system must be mechanistic they must show how physical     
39:30     
parts in space and time interact to generate the whole Behavior this cogs and springs in a     
39:37     
clock view is also expected to be causal the clock will cease to work in predictable ways if either cogx or     
39:45     
spring Y is messed with so you know it's this kind of like this watch maker analogy     
39:51     
which of course goes back to sort of uh the Middle Ages and the enlightenment     
39:56     
where people thought that you know the world was this sort of intricately placed set of entities or     
40:04     
intricately designed set of entities that are all in balance and of course that was blown away by subsequent you     
40:12     
know subsequent science uh but the Clockwork view you know maybe it kind of     
40:17     
still persists in this idea of mechanism um and so you know the idea of     
40:24     
course in a in a watch or in a clock is that if you remove certain parts that     
40:30     
you don't have you know that it basically stops working in a way so you know we think about like if we do a a     
40:37     
molecular study and we knock down some molecular Factor the protein or a gene     
40:43     
and we can see that like this affects the phenotype you know they're very     
40:49     
simple experiments you can say can do in celegans where this is the case or in bacteria you can change the expression     
40:55     
of some gene or you can not down the gene uh and it will knock out the     
41:00     
function and you can show evidence of that so this is the mechanism for this now of course we talked about in the     
41:06     
last uh in in Andre Fenton's answer that     
41:12     
sometimes systems compensate these things so then this Clockwork model     
41:17     
doesn't really work well right so this is what uh kind of the Assumption I     
41:23     
guess we're using uh when we talk about mechanism um     
41:28     
and so that's I guess that's what John Crocker was getting at the favorite way to mess with this this set of intricate     
41:34     
Springs and cogs of neural circuits these days is optogenetics so this is I apologize for     
41:40     
the one Simplicity but this is The Stance of mainstream Neuroscience so he's making this statement that     
41:46     
basically mainstream Neuroscience is stuck in this Clockwork world or you     
41:52     
know the the watchmaker world so this is where again you know um it's everything     
41:58     
is kind of there and you either can remove a part and it doesn't work or you remove a part and it works and we can     
42:04     
tell if it's mechanism or not um the idea that there can be legitimate     
42:10     
causal explanations that are not about physical things that act upon each other locally which would be circuits or     
42:18     
distantly which would be networks is not really taken that seriously in mainstream Neuroscience so you know if     
42:24     
we're talking about complex systems where we're talking about you know     
42:29     
things that are you know things that involve a lot of feedback then you know it's not really something we talk about     
42:35     
a lot in Neuroscience there are some people do but like that's not the mainstream and it's certainly not the     
42:41     
funding agency imperative okay um so let's see     
42:49     
psychology and cognitive Neuroscience in contrast and play uh componential functional explanations which critically     
42:57     
can also be causal in an example from Daniel Dennett which I think I either read or heard     
43:03     
you're walking towards a box and I say to you doo when he clothes her it has poisonous snakes in and you come to an     
43:09     
abrupt stop the meaning of my utterance is Maj your muscles contract this is obviously a causal story but not one     
43:17     
composed of a neural account of how sounds in your auditory pathway went through subsequent intermediate     
43:22     
processing steps in your brain culminating a motor commands uh so this is like where I tell you to     
43:30     
do you know there's another person there I tell you that this is a danger you     
43:36     
stop and stopping doesn't have I mean it has to do with what your brain is doing     
43:42     
but it also has to do with the Lang you know I'm hearing words and I understand     
43:48     
those words as being something that maybe wores made to stuff so it's it's a different kind of set of things going on     
43:55     
than what we may find in individual brains people are generating words and listening to words and that's all in the     
44:02     
brain but uh you know this this interaction between you know using language and executing actions in the     
44:10     
world is a different kind of layer of things and so what is the causal mechanism here is it the someone telling     
44:17     
you to stop because there's danger or is it something within the brain that is     
44:23     
forcing you to stop I mean it could be both but you know it's it's a it's a good     
44:30     
question because ultimately you know you could have a study where uh you know you have people     
44:37     
saying things uh that are both instructional and just kind of just     
44:43     
random and people would just generally stop maybe because there's danger maybe     
44:48     
because they're confused and you wouldn't know if you looked at the neural mechanisms you know that they're     
44:54     
all the same right they basically when you hear something something you stop and but the meaning is very different     
45:00     
and the reason you stop is very different and that is a different layer of different level of explanation and     
45:08     
it's certainly not the same thing okay so uh to move forward there will     
45:16     
need to be a broader familiarity with the Mor's different framework of complexity science so here's another     
45:22     
advocate for complexity science and this more is different paper something we have gone over but this is sort of a     
45:29     
foundational paper for the Santa Fe Institute so this is a paper from like     
45:36     
1972 where they talk about um different levels of explanation and how you know     
45:44     
it it you can find like different granularities of explanation different     
45:50     
levels of explanation so for example you know you have the behavioral explan     
45:55     
explanation which is a of a certain granularity you have the neural explanation and maybe even like the     
46:02     
molecular explanation those are all different granularities but they all kind of fit     
46:08     
into the effective theory of why you stopped at this time and so you know     
46:16     
this is uh it's actually also a foundational paper for the idea of uh     
46:22     
emergent complexity so this is um you know the idea that you have things that     
46:28     
happen at one level and they kind of cascade upwards to um you know levels     
46:34     
where you can see the effects and of course you don't know where those effects     
46:40     
originated sometimes that's not really important at lower levels where they originated but they manifest themselves     
46:46     
at higher levels and so this is um it talks about how this article     
46:53     
promotes the pl pluralistic idea of level dependent effective theories and so one might say that     
47:00     
Neuroscience is the field among those interested in the relationship between brain and behavior that is in fact     
47:06     
defined by its requirement for mechanistic causal explanations using structural facts about     
47:12     
neurons so you know we we Neuroscience is well suited for things like looking at reflexes Locomotion and eye     
47:20     
movements but this can't be a suitable solution for all behaviors     
47:27     
and so this is something we have to keep in mind so he doesn't think that you can     
47:32     
say collapse psychology into Neuroscience or vice     
47:38     
versa so I'm going to you know leave this up to oh actually Louis pooa has a     
47:44     
is a big uh name in in sort of embodiment and and activism what don't     
47:50     
we look at what he's said here a he also advocates for complexity     
47:57     
and kind of this idea that there's this Newtonian billiard ball approach to     
48:04     
neuroscience and causal explanation that is not suitable for what we're trying to do in the     
48:10     
brain and so he goes again he kind of takes the same view as crck hour where     
48:16     
talks about different mechanisms like safe or fear processing where you might     
48:22     
look at a traditional view might Focus solely on the Amiga and that's molecular     
48:27     
Cascades uh but this misses out on all the other things that contribute to fear     
48:33     
processing so you know the amdal interacts with different parts of the brain those interactions are modulated     
48:40     
by neurotransmitters and then the large scale Network Dynamics shift around during different Fierce States so the     
48:48     
network centered on the Amiga creates this fear sort of state and then that     
48:54     
state evolves over time so that's quite a different view than like say a single     
49:00     
mechanism where you can manipulate something take it away or uh give more     
49:05     
of it and have an effect uh and so you know this he kind of goes over     
49:12     
here some nice views here so I'll leave this up to you to finish reading um I'll     
49:18     
post the article and we can have a uh I don't know if we Jesse had anything to     
49:23     
say about it or Morgan Jesse says great great article will have to really absorb     
49:28     
this deep sorry you just caught me uh feeding     
49:35     
the dogs here one second all right about Jesse you have anything to     
49:41     
say yeah um so was was it     
49:48     
only okay so how many     
49:54     
people okay okay okay looking at the I kind of got like so there's all these different people there's like 10 people     
50:01     
commenting on it yeah okay we didn't go through all of them just now do we no I just went through a few and I didn't     
50:06     
want to uh I mean I don't want to give anyone the short shrift but like I     
50:11     
just I assume some of them are um it's very interesting kind of     
50:18     
like I get why they set up the article this way but it's sort of it's sort of annoying to click them     
50:25     
open it's like I I I was one of my previous jobs I was in a situation where     
50:30     
everybody was obsessed that was it was basically web design and everybody at the time was just obsessed with gee we     
50:36     
got a lot of content on the page why don't we put it in an accordion and just like and then like everybody across the     
50:43     
whole organization just was obsessed with it and I just had the biggest flashback to that and it's like okay     
50:49     
like it kind of makes sense but that it's really annoying to navigate     
50:54     
um were any of the people we looked at like it seemed like a lot of people in this article were very like yeah     
51:00     
complexity science and and and so on and I would say Danny's very like Danny's     
51:06     
with the Santa Institute were there people who were like staunchly against it in any way that we saw or well I     
51:13     
don't think so but uh I didn't look through all of them yeah I don't think I'm in a staunch way against it it's     
51:19     
just that like they one of the people we talked about didn't mention it but I think I think you know it's it's it's     
51:26     
kind of one of these things where you're trying to reconstruct or reassess causality and so it's kind of     
51:33     
like the way it's written is that it's you know uh well what about causality     
51:38     
let's let's think of different ways to deal with that and so yeah people are going to turn to complexity science     
51:45     
because it's obviously the one one good alternative to the sort of the view mechanism it's     
51:53     
it's it's really fascinating like I know I'm kind of I'm I'm in     
52:02     
a I don't know perhaps artificially elated space     
52:07     
but just to to Really to to go back to to to to see this inter of the 1943 paper that that that we read weeks ago     
52:16     
and I'm still writing about um it's just interesting to see like I feel like I     
52:21     
feel like what I want to do um     
52:29     
uh and maybe it's because I wasn't you know I don't I don't know I I never I don't I'm not a trained     
52:35     
neuroscientist um so maybe I I'm speaking out of turn     
52:41     
here but but like I always feel like a lot of to me this is sort of the core like     
52:49     
this is these are like real big issues in like the nature     
52:55     
of how science is done at large and so much of the training like     
53:01     
doesn't it feels like it's something that has to be carefully Unearthed and then is is is you know so I feel like I     
53:08     
feel like the task of um like essentially front     
53:14     
like I I never really published Frontier map I suppose which I should I should do     
53:20     
but froner map and and the essence of that is like getting at at how to connect people to these     
53:29     
these challenges um and so I feel like I feel like it in terms of     
53:37     
um I think this be quite exciting if if you want to go there if you want to be optimistic which is always important     
53:44     
to like have caveat about if you if you're up for optimism today about where     
53:51     
things can go uh event like I think there's sort of I     
53:58     
for I can see a certain I'm not saying it is happening     
54:04     
but I can see the nature of what inflection point would look like where people realize okay we have we have to     
54:10     
do XYZ and it's going to require a different approach or it's going to     
54:17     
require addressing the spaces that haven't been not just interdisiplinary things fell to the Gap but more like why     
54:26     
at a large scale the processes will not account for the things that have been     
54:31     
missed and and and attention between that and realizing hey it's really hard     
54:37     
like there's a reason why the easy stuff happened first I I think that's so important to say too and not just     
54:43     
demonize reductionism or demonize the mechanism like there's you know I I I'm against it and     
54:52     
I guess having my quotes up but also like why like it's important to     
54:58     
understand why you know this was this was what became established so I mean     
55:04     
that that's really higher like higher broad level stuff um to to come back to     
55:10     
it it's it's fun I'm going to go through the article and maybe it'll say more about it but I feel like     
55:16     
um I think it's a great um followup from the 40 1943 paper I     
55:23     
think it's um     
55:29     
yeah I my mind is is is still lost in in thinking like I my mind is basically     
55:36     
still in the mode of finishing the article that the essay that I'm writing whatever it is and     
55:42     
looking at the current these current works like now like that could easily be put that could easily be put into the     
55:48     
same space of the article that I'm writing but then it's like okay what what what to do next in the space and I don't I don't we don't to     
55:55     
discuss that here now but it's sort of like where there's so many ways to to     
56:00     
continue to work on these topics and I'm I it's like there's so much stuff on     
56:06     
the table it's like okay what do I pick up first so but that's that's where my mind is and um beyond that I very much     
56:14     
appreciate it's a good find and a good share when was it was this how long ago was this article this was     
56:20     
recently that was was last week yeah last week yeah it's not um     
56:26     
fair enough then um that's     
56:35     
uh doesn't really affect anything that I was going to say but um I don't know there's a lot lot there's a lot to     
56:42     
follow up on and I just I see a lot of um yeah I'll leave it at that thank you     
56:49     
for sharing the article and more more ahead more next week on on these topics for sure no problem     
56:57     
um yeah Morgan are you in a position to Yes     
57:05     
um well I I no I I I appreciate the discussion     
57:11     
um no no big insights here     
57:17     
um but um you know     
57:24     
I'm somebody was asking me um what my what My Philosophy was and um     
57:33     
and I would say that it's neural so     
57:41     
um you know yeah and and that that that's where     
57:47     
I'm looking for my mechanisms right or at least you know um as well as why I'm     
57:54     
always just a little little Beed with     
58:00     
um some of the kind of hammer off Quantum explan you know yeah Quantum     
58:08     
explanations for for Consciousness is just like I thought we were talking     
58:13     
about neurons yeah all right now let me go back uh now     
58:19     
so we're again like I said last week or this past week on Monday the no Nobel     
58:26     
Prize was given for physiology of medicine and that was a c Elegance related thing and I talked about that um     
58:34     
in evil worm and then Tuesday and Wednesday there was a there were nobels     
58:39     
given on AI or AI related things and you know one was in physics which was um you     
58:48     
know one one prize and then the other was in chemistry for protein like for Alpha fold so so we start with this     
58:56     
article uh in studying Nobel when AI researchers hopefield and Hinton take     
59:02     
2024 physics prize and so uh this is of course for foundational work hopefield     
59:10     
of course developed hopefield networks which were you know these learning machines that were based on spin glasses     
59:17     
and physics so there is the strong physics connection there and then Hinton of course develop deep learning although     
59:25     
I think um yesterday Morgan said I wonder what Schmid heer's take is on this Snowbell     
59:32     
Schmid heer is of course famous for like saying I invented deep learning 30 years     
59:38     
ago um instead of 10 and so and so Hinton     
59:43     
actually uh quit Google in 2023 to warn of the dangers of AI and he was     
59:50     
flabbergasted at the news so this is um you know this is the physics prize was     
59:56     
given on Tuesday this is for the foundational work uh you know we have a lot of     
1:00:02     
foundational work of course we've talked about the history of that where you have     
1:00:07     
these uh networks actually if you look at the uh Nobel right up they go back to     
1:00:14     
um Mulla and pits which is of course the classic paper looking at sort of the     
1:00:19     
neurophysiological logic of neurons and you know that was sort of the basis for     
1:00:25     
uh some of the early neural networks and then of course you know that was sort of     
1:00:30     
the inspiration for connectionism and cognitive science but also hopefield networks which were these spin glasses     
1:00:38     
or V variations on spin glasses which is model in physics uh that you know     
1:00:43     
allowed us to learn from networks and and so this is you know all sort of in     
1:00:50     
the sort of the roots of uh what we might call um you know old old AI or good     
1:00:58     
oldfashioned AI but it really isn't good old fashioned AI because it is more kind of connected to the modern sort of data     
1:01:05     
driven AI that we use today uh well we still use like symbolic     
1:01:11     
AI but this is you know the thing that everyone's hyping     
1:01:16     
so uh Hinton said I'm flabergasted I had no idea this would happen I'm very     
1:01:23     
surprised and of course this was probably I mean I don't know if it's very controversial in physics I think     
1:01:29     
the chemistry award was probably more surprising at least in terms of being of     
1:01:34     
a method and a computational method at that as usually we think of like you     
1:01:40     
know I remember like back when I was in graduate school people would complain about like how you know there was no     
1:01:48     
Nobel for computer science apparently now there is so it's every other Nobel     
1:01:53     
you know uh maybe not the Peace Prize but like or literature but every other     
1:01:59     
Nobel we were getting um computer science in um so hopefield and hinton's     
1:02:06     
research which dates back to the early 1980s applied principles from physics to develop methods and underpin modern     
1:02:13     
machine learning techniques their work has enabled computers to perform tasks such as image recognition and pattern     
1:02:21     
completion uh this wi is perhaps more ey catching because Hinton who was often     
1:02:26     
called one of the Godfathers of AI resigned from Google in 23 so he could     
1:02:31     
speak freely about the potential risks from AI systems so as I understand it like his     
1:02:38     
Nobel speech was about like the dangers of AI you know some might or I guess the     
1:02:44     
you know threat of AI and so some might say that there's sort of this pre-programmed Noble idus which is where     
1:02:51     
you know Nobel Prize winners kind of go on these tangents um so well you know that's     
1:02:58     
that's something that we can talk about later we'll see how that plays out um     
1:03:03     
but basically why they won the physics prize is because these techniques are drawn from physics so why are computer     
1:03:11     
scientists or I guess uh you know people in that millu getting a physics     
1:03:17     
Nobel um and yes Hassen Felder said and the new 2024 Nobel Prize in physics does     
1:03:25     
not go to physics which of course is not necessarily true because we're using     
1:03:31     
sort of an applied physics point of view so the Noel committee awarded this     
1:03:38     
because the two men draw from statistical models used in physics and partly because the     
1:03:45     
advancements and physics research come from using the men's noal Network techniques as research     
1:03:50     
tools uh artificial neural networks have been used to advance research across physics topics as diverse as particle     
1:03:56     
physics Material Science and astrophysics so we're not only drawing from physics theory but we're also     
1:04:04     
enabling physics with these methods uh so hopefield is still alive a     
1:04:10     
91 year old theoretical biologist the physics background um and so the hopefield     
1:04:17     
networks are networks that describe connections between nodes as physical forces this is of course the Hope field     
1:04:24     
Network and this of course is based on spin glasses uh in particular it stores     
1:04:31     
patterns as low energy states allowing the system to recreate images when prompted with similar patterns this     
1:04:37     
approach mimic Associated memory resuming how the brain recalls words or concepts and this is their figure kind     
1:04:44     
of showing the relationship between natural and artificial neurons     
1:04:50     
um so this is uh Hinton of course is 76     
1:04:55     
and built on Hope Fields research in the early 80s by developing a layered version of the hopefield network that     
1:05:01     
incorporated probabilities so you know this is where we're getting weights so this is actually hinton's work in the     
1:05:07     
80s not for the Deep learning stuff that he would do in the 2010s but you know um     
1:05:14     
so you have the hopefield network that's based on spin glasses and physics theory     
1:05:19     
you then have intens work which takes the hopefield network and incorporates     
1:05:24     
weights and so now you know uh hint Ander parallels to physics studies of     
1:05:30     
large systems of similar elements like gas molecules instead of tracking individual molecules physicists examine     
1:05:38     
Collective properties like pressure or temperature so now we have this tie into complexity Theory because you know we     
1:05:45     
were talking about mechanism earlier specifically mechanism in the brain we can see that if we take that natural     
1:05:52     
artificial sort of analogy we see that you know like in in Neuroscience we can     
1:05:57     
have Collective structures emerging structures so can we in artificial neurs     
1:06:04     
and those are actually very important so we don't want to necessarily track individual molecules we can examine     
1:06:10     
Collective properties with these kind of tools and the sort of link between you know these artificial neurons and what     
1:06:18     
we're doing in physics is is kind of important I I don't know if that's something people really kind of explored     
1:06:25     
philosoph IC Ally or theoretically to its whole extent but it's just something     
1:06:31     
to kind of put a in the boltzman equation from the 19th century physics calculates the     
1:06:37     
probability of different states in such systems Hinton applied this concept to neural networks naming his 1985 method     
1:06:44     
the boltman machine so this is another model that Hinton developed the boltzman     
1:06:49     
machine you're maybe familiar with it this is where we have this connection     
1:06:54     
between machine learning and statistical physics which has been a fruitful area for many years people are doing things     
1:07:02     
with diffusion now and it's a similar kind of connection of people a boltzman machine is capable of     
1:07:09     
recognizing classifying images and generating new examples based on its     
1:07:14     
training uh the techniques P pioneered by hfield and Hinton vastly simp simplify and approximate processes     
1:07:22     
suspected to occur inside biological neural networks like those fund inside animal grains uh neural networks have     
1:07:29     
brought automation techniques to machines that must deal with approximations and fuzzy fuzzy edge     
1:07:35     
cases they must also learn from unstructured data and so you know this just kind of talks about and of course     
1:07:42     
it's very idealized because we know that you know neural networks it really depends on the training and the     
1:07:48     
algorithm and everything how well they do on these kind of edge cases and     
1:07:53     
unstructured data sets but that's not what this article is about so yeah so     
1:07:59     
then of course you know when you give a Nobel Prize you award it to certain     
1:08:04     
people you have a rationale there are a lot of people that kind of get the short shrift in a sense um so that's something     
1:08:12     
that you know we saw with the physiology and Medicine uh prize two cgans     
1:08:18     
researchers got it uh but there was a lot of concurrent work in plant biology     
1:08:24     
on micro rnas where it it wasn't mentioned in the prize so that's something uh you know where they just     
1:08:30     
kind of have you know they have a kind of a theme and they get people and you know some people get the short shrip     
1:08:38     
so um hinton's involvement and artificial intelligence dates back to     
1:08:44     
1972 and his achievements have significantly shaped modern generative AI in 1987 Hinton rart and Williams help     
1:08:53     
bring attention to back propagation which is of course something we also are familiar with a key method for training     
1:08:59     
neural networks that is fundamental to today's generative AI mons um and then     
1:09:05     
of course in 2012 Hinton collaborated with ksky and SSG to develop     
1:09:11     
alexnet a pivotal innovation in computer vision and deep learning widely credited     
1:09:16     
with launching the current error of generative AI so Hinton has received the Turing award which is the Nobel Prize at     
1:09:24     
Computing this is what people were complaining about that you have the Turing award which isn't good enough you'd like to have a Nobel and now you     
1:09:31     
have the Nobel as well and so this is the other prize on     
1:09:36     
Wednesday this was for uh alpha alpha fold and so if you're not familiar with     
1:09:41     
Alpha fold this is where we're using computational methods solve problems in     
1:09:47     
protein folding and protein uh structure and so this is of course the     
1:09:53     
computational tool and the same sort of argument might be made that maybe we     
1:09:59     
shouldn't be giving words in chemistry uh for methods or for things that are     
1:10:05     
tangentially related to chemistry of course you could also argue that this is very fundamental to Modern     
1:10:12     
Chemistry because you can use things like um Alpha to predict proteins and to     
1:10:18     
develop materials and things like that so this is something that is again a method but it's used     
1:10:26     
you know it's going to be used quite widely and it has a wide impact so this this prize was given to Dennis C and     
1:10:33     
John jumper and of course David Baker and these are all people on this Alpha     
1:10:38     
full team they didn't give it to the whole team because that's not the way the bill bber like I said but you know     
1:10:44     
these are uh John jumper has uh degrees in physics and chemistry and then Demis     
1:10:51     
has I guess a computer science background you know I the physics background term as well so you know you     
1:10:57     
have people of course people float between Fields all the time as I know and so this is you know this is     
1:11:03     
something that again it maybe has maybe has some controversy to it but I think it's a good uh I think it was inevitable     
1:11:10     
that they gave this award uh to Alpha fold at some point because alphafold     
1:11:16     
really has improved upon the state-ofthe-art in that area so you know this is about     
1:11:23     
computational protein design and using this method to create sort of more efficient     
1:11:29     
vaccines speed up research on cures for cancer or lead to completely new     
1:11:35     
materials so of course Alpha fold you know we're familiar with how that's kind of come onto the scene and in     
1:11:42     
2020 this is sort of uh you know kind of took the World by storm in terms of or     
1:11:48     
at least the world of uh uh protein prediction by storm and protein folding     
1:11:54     
and so this is uh of course uh you know they now got Al or     
1:12:00     
Alpha fold 3 where we can predict the structures of DNA RNA and molecules like     
1:12:07     
lians and this is of course essential for drug Discovery so this is something that you know of course has a wide     
1:12:15     
impact in chemistry um and of course you know esus     
1:12:20     
and I think uh joh John jumper was like only like seven or eight years out from his PhD after winning this so it's kind     
1:12:28     
of interesting how people can win Nobel prizes like when they're 91 and people     
1:12:33     
can win them relatively early in their career so um and then of course you know     
1:12:40     
uh Baker was it works more generally on protein prediction so um baker has     
1:12:48     
created several AI tools for Designing and predicting the structure of proteins such as a family of programs called     
1:12:54     
Rosetta in 2022 his lab created an open source AI tool called protein mpnn which     
1:13:01     
is able to help researchers pre discover previously unknown proteins and design     
1:13:07     
entirely new ones so it's actually maybe more for class of tools that are being     
1:13:13     
developed Chief among the alpha F so this is the other prize and so if     
1:13:20     
we go here this is the nobelprize.org site where they kind of show kind of the     
1:13:25     
profile of the people they always have the the serious drawing here and then they kind of describe why they won the     
1:13:32     
prize and then have some like a press release and some other scientific background and then this is the prize in     
1:13:39     
chemistry for 2024 and uh you know press release and     
1:13:45     
scientific background as well so that's uh what that's all about     
1:13:51     
now I mentioned that like why is it that we're giving a a Nobel Prize to a method     
1:13:58     
you know both of these are kind of method oriented so you know there's some fundamental physics here there's     
1:14:04     
actually some fundamental chemistry here why would you give a a a Nobel to a     
1:14:09     
method and so people have asked that question and all you have to do is go back about 31 years so in     
1:14:17     
1993 Jurassic Park came out in the theaters in the summer and then the fall     
1:14:23     
we get The Nobel Prize or PCR or polymer chain reaction and so     
1:14:29     
this was one by Carrie mullus and Michael Smith this is definitely chemistry but it's a method it's not     
1:14:35     
like for some fundamental Discovery it is a method but the method is wide ranging     
1:14:41     
impact and you know you can do a lot of things with PCR as much as you probably will be able to do with Alpha for and so     
1:14:48     
this is um this was the Nobel Prize in chemist uh chemistry for 1993     
1:14:55     
awarded for contributions to the developments of methods within DNA based chemistry uh or you know awarded to     
1:15:03     
Carrie Mullis and Michael Smith Carrie Mullis did the sort of invention of PCR     
1:15:10     
or at least uh kind of perfected it so it worked and it so PCR in in brief you     
1:15:18     
know you have a template of DNA and you can put it into the set of chemical reactions and it's this uh what they     
1:15:24     
call thermal uh sequencing so like you have this you know template of of DNA     
1:15:32     
and you basically subject it to these Heating and Cooling cycles and you can amplify that DNA through these Cycles so     
1:15:41     
you program a machine to go from like 95 degrees down to about 10° Cel you get     
1:15:49     
the cycle and it it allows you to replicate DNA or RNA sometimes     
1:15:55     
in you know in your sample so this has been very useful for you know all sorts     
1:16:01     
of sequencing tests that sort of forms the core of nextg sequencing and a lot     
1:16:06     
of you know techniques for um um analyzing DNA and     
1:16:12     
RNA so this is you know important for uh genetic engineering it's important for     
1:16:18     
genetic analysis all that um and then of course Michael Smith was able to do     
1:16:25     
something called sight directed mutagenesis which was of course um you know a technique to uh do these targeted     
1:16:33     
studies um where you have like you can Target certain illegal nucleotides and have effects in the     
1:16:41     
organism so these these kind of went together in this prize and then there is this article I found     
1:16:48     
um so there was this article I found uh it was kind of like I guess tongue and cheek but it had it does sort of     
1:16:56     
continue from this sort of alpha fold and PCR tradition which is when we'll     
1:17:02     
blast get its Nobel Prize and so blast of course is a tool for a bioinformatics     
1:17:07     
tool for searching uh for Gene and protein sequences given a template you     
1:17:13     
do this computationally and you find the the best matches in a database to the     
1:17:18     
sequence that you're quering so this is actually kind of tongue and cheek but uh     
1:17:26     
basically uh you know people have complained about how you're awarding Nobel prizes the methods this person     
1:17:33     
says I think the creator of blast should get a Nobel Prize the effect uh that BL     
1:17:39     
the impact that blast is had on the field of biology not just on bioinformatics has been huge these     
1:17:46     
people created a verb What modern biologist does not know what blasting a sequence means blast paper is one of the     
1:17:53     
most highly cited papers in history its impact on physiology is     
1:17:58     
undeniable Litman and Jean Myers who are the people who developed um blast stand out for their     
1:18:05     
contributions to the computational processing of biological sequences that's the Nobel sort of description of     
1:18:13     
blast uh I know that blast was built on previous work like Fast day but one so     
1:18:19     
is everything and two fast day is also Whitman's work so he can claim credit for that the other counter argument I've     
1:18:26     
heard is that blast is mostly a method so and so but so is gfp which is green     
1:18:31     
fluorescent protein uh and one may argue and of     
1:18:36     
course this is one uh I don't know if this one an nobell I think it did um one     
1:18:42     
may argue that it was very cool that one could have a protein that Flores by itself but the prize was awarded for the     
1:18:48     
impact in the lab does anyone believe that just the 1962 discovery of jellyfish protein would have sufficed     
1:18:55     
for an elel so this is where um let's see yeah this shows in 2008 this was the     
1:19:04     
word for glowing proteins so green fluorescent protein is a subset of all the kinds of colored fluorescent     
1:19:11     
proteins that we have and we use these ubiquitously in biology to tag things     
1:19:17     
that we use like some sort of uh we use it as a tag to you know attach itself to     
1:19:22     
some molecular Target and then we use it to report on whether that's present or     
1:19:27     
absent in the samples so this is a very useful tool but it actually comes from a     
1:19:32     
jellyfish protein and it was isolated by a Japanese researcher and then they were able to uh you know purify it and make     
1:19:42     
give some value so Marty chaly who's a seans person was able to use gfp as a     
1:19:49     
genetic tag for different biological phenomena and then Robert Cen is a big     
1:19:54     
uh biochemist name in Biochemistry um was able to help us     
1:20:01     
understand how gfp for uses so that's what they're referring to there and so     
1:20:07     
you know you could argue that you could give blast the Nobel Prize but you know this is tongue and cheek but still then     
1:20:14     
finally this uh article from John hfield in October 2018 this is uh after I think     
1:20:21     
winning some prize um and then you know not the Nobel but uh basically asking     
1:20:27     
now what so uh you know this uh hopefield of course is 91 now so kind of     
1:20:36     
just you know basically retiring from his position winning the 2019 Franklin metal     
1:20:43     
and physics and kind of going over some Reflections on what physics is so to me     
1:20:51     
growing up with a father and mother both of whom are physicists physics was not just subject matter um all things in the world are     
1:20:59     
incidentally the subject matter the central idea was that the world is understandable that you should be able     
1:21:05     
to take anything apart understand the relationships between its constituents do experiments and on that basis be able     
1:21:12     
to develop qu a quantitative understanding of Its Behavior physics is the point of view that the world around     
1:21:18     
us with effort Ingenuity and adequate resources understandable and predictive     
1:21:23     
and reasonbly quantity ative fashion being a physicist is a dedication to a quest for this kind of understanding and     
1:21:31     
so kind of reflecting on his life and some of these things um and so this is     
1:21:37     
kind of an interesting article if you're interested in um you know some life of a     
1:21:42     
scientist who ends up winning a Nobel Prize so that that's kind of what all     
1:21:48     
that was about this week um any comments or questions on that yeah I mean it's     
1:21:56     
if if AI begins to deliver what uh what it's promised we should see more of     
1:22:03     
this or you know like like more more more will come     
1:22:11     
of software and and software innov or you know computational Innovations right     
1:22:20     
I wasn't uh I'm hoping that we do something at Celsius that that's around     
1:22:26     
conversational protein design just in terms of some some appreciation of     
1:22:33     
the of that of that work yeah and maybe alha too I mean certainly     
1:22:41     
you know the the big thing that that the alpha fold team could     
1:22:47     
could you know objectively scaned behind     
1:22:52     
was the the decades long protein um structure competition right     
1:23:00     
right that that you know they certainly had their alexn     
1:23:07     
moment in terms of just smashing you know smashing all previous     
1:23:14     
records in you know in their first you know     
1:23:19     
release right and and and even I believe you know improving     
1:23:27     
significantly on the the the next two     
1:23:33     
um so there was there was a lot of just     
1:23:39     
wow what have they done you know um the     
1:23:44     
the U the the     
1:23:50     
the you know the thing we're not talking about is the fact that like     
1:23:56     
now you know I don't want to say people have moved the goalpost but it's just     
1:24:03     
like maybe maybe protein structure wasn't the right the Great Wall holding back     
1:24:11     
biological Innovation yeah and and     
1:24:16     
um and yeah and I don't know if you     
1:24:22     
mentioned um Ben boy is's comments     
1:24:28     
about you know this is this is possible     
1:24:34     
because um this is possible because of lots     
1:24:40     
of data that has been stored in databases you know like like like you     
1:24:46     
said like um I think you posted something after Ben's thing where it was     
1:24:53     
just like when when will the protein database get its Noel oh yeah yeah that was the thing I talked about yeah and     
1:25:01     
just just something you know again something to be said for you know that     
1:25:09     
that I mean it it always seems kind of obvious that language models would be     
1:25:15     
the the first you know in quotes breakthrough right just because of the     
1:25:22     
data right and and you've seen you've seen     
1:25:28     
what the companies have done you know like from from like trying to pay people     
1:25:34     
to generate more text to you know Finding finding weird text     
1:25:42     
stores that they could they could buy access to um but you know at a at a     
1:25:50     
certain level there's there's been a plateau in performance because it's like     
1:25:56     
we've we've finished all the data great um and and in biology I mean I I I     
1:26:07     
should have posted this too but I posted the UK biobank um     
1:26:14     
scientific conference videos that dropped this week okay I think from last     
1:26:20     
year you know like not they're not super recent but they only just made it to     
1:26:26     
YouTube um and it was interesting to see Daphne     
1:26:33     
ker who's a famous Stanford machine learning     
1:26:38     
Professor who believe is now I don't think she's     
1:26:45     
Capt her Stanford you know she's she's joined like a lot of Stanford machine     
1:26:50     
learning professors you know she's she's gone into industry and um and got you know a huge     
1:27:01     
amount of VC money to start a biology company yeah and it was interesting     
1:27:09     
because I I just posted something from of her speaking I think     
1:27:17     
at the world's what's that never understood what that     
1:27:22     
conference is it's like the world science scientific form or something like that maybe seems very seems very     
1:27:28     
splashy but it doesn't seem like it's a scientific conference um     
1:27:35     
anyway and she was speaking in kind of big generalizations what was interesting to see her presenting at the UK biobank     
1:27:43     
conference because there it was just like oh you know she's not just one of these like I'm trying to do a DNA     
1:27:51     
Foundation model you know she she's discussing like the the     
1:27:59     
histopathology and multimodal data that's associated with the the     
1:28:06     
um um It's associated with the UK bio Bank you know and     
1:28:15     
and the the the future of Bio you know the     
1:28:20     
one UK biobank like data sets don't really exist anywhere else     
1:28:26     
yeah it is it is an amazing resource um and     
1:28:32     
to as amazing as that is how it's still you know it is still just one data     
1:28:40     
set um and and you know you are kind of     
1:28:45     
limited to the to the tests that that those people did and it would be hard to     
1:28:52     
add to them right like like it's pH physically hard it would be physically     
1:28:58     
hard to say like oh I want to just track down that same you know one million UK     
1:29:04     
people and do this thing to them right um like like this isn't     
1:29:12     
software and and like each one of those data points is potentially expensive and     
1:29:19     
and or hard to do in the sense that like doing the measurements requires     
1:29:25     
potentially a you know a skilled technician yeah     
1:29:32     
yeah um and and that that biology perhaps     
1:29:38     
needs like you know it needs like internet scale more     
1:29:43     
of UK bio Banks right yeah that that that that um you know yeah just because     
1:29:53     
again you know the biology of the     
1:29:59     
the the mechanisms to tie it back to yeah the mechanisms of Life are a lot     
1:30:06     
more complex than the syntax of language um and and look at and look at     
1:30:13     
the and look at the you know the the ratio that we had in terms of data to     
1:30:22     
to algorithm yeah you know quote quote     
1:30:28     
mechanism in terms of deep learn you know in terms of training training net     
1:30:33     
to do to do to be chat GPT right     
1:30:40     
right it's it's um anyway yeah interesting stuff we'll see     
1:30:48     
how in the future if uh we get more nobels on     
1:30:55     
AI certainly going have a lot of applications though and that's kind of but that's been going on and it should     
1:31:01     
be said that the uh prizing chemistry you know we talk about Alpha fold sort     
1:31:06     
of an isolation but really it's based on what people been doing chemistry for years and you know is it like you know     
1:31:14     
sort of a continuation of that so it's like is you're getting more computer power you can solve these problems more     
1:31:20     
I like your point about how maybe protein folding wasn't the barrier than we thought it was just simple you get     
1:31:26     
enough computational power and you write the right program and it's not that hard     
1:31:31     
because you have the you know it's like any other set of problems like where we     
1:31:37     
thought it was really hard and that's when we get enough computational power it's not as hard as we thought not as     
1:31:42     
intractable as we thought so and and it it kind of it does set our sights on the the the     
1:31:50     
next problem but in this case it's actually problems right in the sense     
1:31:56     
that it's not just it's not just docking but it's it's also um yeah that that     
1:32:05     
there are actual there are plenty of     
1:32:10     
um yeah that that protein shape is actually you know somewhat probabilistic     
1:32:19     
right you know you're you're kind of you're potentially multiple shapes right     
1:32:25     
just anything is confirmation stable it's like yeah yeah yeah and and so do     
1:32:31     
docking has has a number of interesting problems to it and and all the other     
1:32:37     
protein interactions     
1:32:43     
um is is hdden on the     
1:32:49     
um all you need is attention paper I'm not not sure I don't think so     
1:32:55     
I don't think so right I don't know I mean you know it's again just it's kind     
1:33:01     
of funny that we're all you know or at least right now in this particular hype     
1:33:07     
cycle it's it's     
1:33:15     
the I I posted a thing on the um or one     
1:33:20     
of those um kiler papers is um sorry     
1:33:25     
it's attention is all you need     
1:33:31     
yeah where are the offers on don't know uh it's a bunch of Google people I don't     
1:33:38     
recognize I think it's it's all Google people wa no no it's got It's got a     
1:33:43     
university Toronto yeah Aiden Gomez I think is one of the like like these are     
1:33:51     
the people who went on to I bet you and these are all people at     
1:33:56     
startups right now yeah you know and when I say startups I mean you know that     
1:34:02     
that have more than like a hundred million not startup startups yeah you     
1:34:10     
know um but Google brain Google research and University of Toronto and then last     
1:34:17     
author Ilia Pol shukin okay but I I     
1:34:22     
posted a link to the video on um like R rnn's all we really needed or     
1:34:30     
something like that yeah yeah that was a kind of a um     
1:34:39     
presumptuous title as it turns out well it certainly been Rift on from     
1:34:47     
from that on yeah everybody substituted there yeah     
1:34:54     
so yeah I I'm actually a member of the ASAP bio slack so ASAP bio is an or that     
1:35:01     
does a lot of stuff with open science mainly with well with preprints but other things uh the ad basically an     
1:35:09     
advocacy group and they've been doing a lot of interesting stuff with um     
1:35:16     
different types of events so I actually uh I was when I was part of ASP     
1:35:22     
bio as one of their coach cohorts we hosted this talk on the past present and future preprints we put together this     
1:35:30     
talk where we had a bunch of guest speakers talking about their experience with     
1:35:35     
preprints and um how they use them in their Labs so this is a very good uh     
1:35:41     
presentation I actually live tweeted this at the time so it's very much um     
1:35:47     
yes during the pandemic so it was very much um you know something that we had     
1:35:52     
to do um virtually but it was a it was a good experience anyways uh this is what     
1:35:59     
they're doing that's what they kind of advocate for and so every year they kind of come up with these uh sort of focal     
1:36:07     
areas of their efforts so I thought this was good because it kind of gives you an idea of the way of the landscape in uh     
1:36:15     
open science and what people are thinking about in terms of maybe the types of things that people want to do     
1:36:23     
uh or you know kind of the quest open questions so this is um it's the     
1:36:29     
community manager Johnny coats uh 2025 is rapidly approaching and     
1:36:35     
we're now planning our community calls for next year so they do these Community calls where they work on these projects and kind of work on something having to     
1:36:43     
do with these questions so as of last year I wanted to give you all an opportunity to vote on     
1:36:49     
which calls are held so that we're delivering things you want to hear about so these are things that they kind of     
1:36:55     
identified as major themes in the in the in the world of open science kind of     
1:37:01     
open questions but also things you can do a pre uh you know project on so like     
1:37:08     
the first one is has to do with preprints and Publications predatory publishing paper     
1:37:15     
mills and they're unpacked on scientific publication and preprints so this is where people try to uh gain the system     
1:37:23     
or they they you know write papers with generative AI or they kind of write derivative papers and you know there's     
1:37:31     
this this sort of uh predatory aspect of publishing or the slight sort of mass     
1:37:37     
production of published papers that's kind of um a problem yet a lot of uh you     
1:37:44     
know not only in journals but in uh preprints as well so that's that's one and that's     
1:37:52     
something that's you know kind of not directly related to open science but it is an issue that you can have an open     
1:37:59     
science angle the second is institutional recognition of preprints so in open     
1:38:06     
science there's this issue of practice you know where you want to impart the practices to people so they can do     
1:38:12     
better science and the assumption is is that if you do open science and you know that that the     
1:38:19     
assumption is that's better but it costs people time you know you have to implement     
1:38:26     
those practices but moreover your home institution has to recognize the value     
1:38:31     
of preprints so if you publish something as a preprint does it get viewed as a     
1:38:37     
publication or to people just dismiss it if people release pre-prints early     
1:38:43     
did they get you know recognition for it or you know what what is the role how do     
1:38:49     
people view preprints some institutions view them favorably some un favorably     
1:38:54     
some are you know sort of neutral and so this has a role sometimes in tenure and     
1:39:00     
promotions this has a role in sort of you know as we know like in in the world of AI preprints or ubiquitous you     
1:39:08     
everyone posts to work on archive but in some Fields like in biology you know     
1:39:14     
it's it's a mixed bag and so that's kind of what they're getting at     
1:39:19     
there uh there's also publishing experiments we have Arcadia which is a company um that was founded     
1:39:27     
to do like exploratory science but also built on different new publishing models     
1:39:33     
so they're doing like replications they're doing other types of working with different types of model organisms     
1:39:39     
and then pushing the work out in these Innovative types of Publications uh there are other     
1:39:45     
platforms like Pub Pub and other types of like uh pre-print aggregators and     
1:39:51     
it's you know this there're all sorts of experiment going on in the publishing sphere you know that's something that we     
1:39:58     
I just got uh an inquiry from the active uh active inference Institute about     
1:40:05     
setting up a overlay Journal an overlay Journal is of course are where you you     
1:40:10     
host your some papers uh you might have like a thematic type of um Journal     
1:40:17     
atmosphere you know you have an interface that basically presents papers as like being part of a Journal you have     
1:40:24     
editors but you host your papers on say something like open science framework so     
1:40:30     
you can actually build a journal from you know uh from you know make it very     
1:40:35     
easy to build a journal and sustain it so this is uh something we're looking     
1:40:41     
into uh so that's that and then social media and science communication of course you know having that Outreach     
1:40:48     
aspect but also having the communication aspect so rapidly reporting was results     
1:40:54     
as sort of blog posts or you know social media posts instead of like you know I     
1:41:01     
mean you might write the paper or the preprint but then you have to get it get the word out and this is where social     
1:41:07     
media and science communication kind of come together also you know we have science     
1:41:12     
communication on social media we want to uh sort of interpret studies for people     
1:41:17     
make sure that they don't fall prey to misinformation or you know there aren't     
1:41:23     
like sort of uh misinterpretations of of an article you know I'm sure you've seen     
1:41:29     
things where they're very Sensational headlines about something but of course those Sensational headlines have to be     
1:41:35     
countered because they can be very damaging to really understanding what was done in this     
1:41:41     
stud um journalists and preprints responsible reporting this is kind of what I was talking about where you know     
1:41:48     
someone who doesn't have the domain expertise picks up a preprint says that this says something that it doesn't and     
1:41:54     
then you know that's that that kind of persists in the minds of people who are     
1:42:00     
kind of casual you know have a casual knowledge or maybe no knowledge at all of a     
1:42:06     
certain area so you know when you know this was particularly important during the pandemic when you had a lot of uh     
1:42:14     
preprints that were you know not um shall we say not about this necessarily     
1:42:21     
about the science anyway this is uh a constant problem especially     
1:42:28     
when universities release press releases on on articles and they're not they don't necessarily match what the actual     
1:42:35     
work was that was done you know it doesn't match that so this is something that you know it's an interesting topic     
1:42:42     
and then of course there's this topic Roots routes to open where to preprint with in other away away initiatives so     
1:42:49     
how do you get to an open science practice or how do you get to open science practice you might do this     
1:42:55     
through preprints you might do this through science communication you might do this through sharing data you might     
1:43:02     
use all three as a strategy you might have like videos like you know our lab     
1:43:08     
we do a lot of videos we do a lot of uh papers blog posts we have a very uh     
1:43:15     
varied set of channels that we use and some you know some people are just satisfied with maybe a releasing prequin     
1:43:22     
or uh releasing open data and so you know they're interested mainly in preprints but it's kind of interesting     
1:43:29     
how those kind of strategies intersect this is actually the next one is a really     
1:43:35     
interesting um question and that's has Open Access failed so you know maybe you     
1:43:41     
know we can ask the question how widely adopted is open access uh opens you know     
1:43:47     
sort of open science practices but of course journals have this imperative of     
1:43:52     
open access where you know instead of having things locked behind hand to paywall you have access to them and so     
1:43:59     
if you go to something like Plus or eif you know they have a model where the     
1:44:07     
author pays money to have the article be freely open sometimes those fees are     
1:44:14     
extremely high and it's hard for researchers who don't have a lot of     
1:44:20     
grant money or a lot of institutional support to pay that fee to make the article     
1:44:26     
open there are different types of access there's green Open Access Diamond Open     
1:44:31     
Access gold Open Access and they're basically just variations on how to make something Open     
1:44:37     
Access but there's this issue of you know kind of where     
1:44:42     
companies you know the big publishing companies like Springer and Wy have kind     
1:44:48     
of unscrupulously taken the model and used it to kind of make a profit so they're     
1:44:53     
squeezing PE authors for money and they're also squeezing libraries academic libraries for     
1:45:01     
subscriptions and so you know it has Open Access really kind of facilitated     
1:45:06     
access to articles facilitated access to open science or is it just another     
1:45:12     
money-making scheme and that's an interesting question I feel like kind of     
1:45:17     
it's been co-opted in a lot of ways unfortunately um but it's something that     
1:45:22     
we have to think about and of course with overlay journals we can get around some of the costs associated with     
1:45:29     
running a journal so the whole reason why you know we're reliant on big journals well because there's a Prestige     
1:45:36     
aspect but there's also an aspect of it's hard to put together a journal with     
1:45:41     
with editors and with reviewers and then with uh the infrastructure to uh publish     
1:45:49     
something but now with pre-print servers we don't necessarily have that problem we can take a preprint server we have     
1:45:56     
other tools that sort of enable post um post preprint review or you know     
1:46:03     
something like that and we can put together a system that approximates a journal we can also do this with overlay     
1:46:09     
journals where we have we can host the Articles uh with a sort of a persistent     
1:46:15     
identifier and then we can have an interface where we can allow for reviewing comments displaying all of the     
1:46:23     
supplemental data and everything else then finally this uh this is a sort of     
1:46:29     
a uh Evergreen topic which is Miss and disinformation and preprints so like     
1:46:34     
when people kind of misinterpret their data or there's like basically a a bad     
1:46:42     
faith preprint that comes out arguing for something like you know uh some drug     
1:46:48     
being used um to cure Co or something like that     
1:46:53     
um those are things that you know we want to sort of identify and and deal with as a problem in the community so     
1:47:01     
those are kind of their open questions I would probably come up with a different list but this is what they're interested     
1:47:09     
in um so I have a couple of Articles     
1:47:14     
here um this is the first article this is     
1:47:20     
um an interesting article from frontiers of neuroinformatics um this is open is not     
1:47:27     
enough let's take the next step an integrated community-driven Computing platform for Neuroscience so this is a     
1:47:34     
paper that we I think we talked about this yesterday and this is those are the neur de developers yeah this is the     
1:47:41     
neurod Deb so um some of these are going to be about like our conversation     
1:47:46     
yesterday and U so this is a paper that kind of describes sort of this neurod     
1:47:52     
Debian platform which argues that you know we have this sort of standard of     
1:47:58     
open and you know just making things open isn't enough you just don't throw your data out on the Internet or put out     
1:48:05     
preprints and you know really have no um you know it can be sort of     
1:48:11     
divorced from the community and that you're just putting things out in the world without any sort of community     
1:48:17     
feedback or Community involvement or not letting the community learn the practice     
1:48:23     
and use them easily so this is where they're talking about here um and this     
1:48:29     
you know has connections the incf so you know they're trying to kind     
1:48:35     
of get a handle on a lot of the uh Neuroscience software projects that     
1:48:41     
exist so in scientific software we have two problems we have sort of this model     
1:48:49     
of sort of home brewing everything which is like where you create create your own software for you know doing something     
1:48:56     
and then you make it open but of course making that open doesn't really solve anything because you're not going to     
1:49:02     
maintain the software and you're not going to you know make it easy for people to use so making it open doesn't     
1:49:10     
really make much sense uh so there's been this movement to have like research     
1:49:15     
uh software Engineers um where Labs would hire a research software engineer who would make things very much like a     
1:49:24     
more professional software project but that of course costs money like most uh open science initiative so this is a     
1:49:32     
problem um and of course making this sustainable you know that's another     
1:49:38     
issue so um you know we know that software research software projects that     
1:49:44     
whole culture is broken in efficient and opaque procedures combined with a scarce developer Workforce results in tools of     
1:49:51     
insufficient quality and robustness so we need things to conduct the research but we don't have those tools even if     
1:49:58     
they're open because we can't use them uh and people you know of course leave their positions and when they     
1:50:06     
leave their positions usually the software dies with so we need to bring our tools into     
1:50:12     
the open we need community-driven platforms so the entire Community can contribute to these different tools so     
1:50:19     
this is where we talk about n Debian neurod Debian applies proven principles     
1:50:25     
and procedures from free and open source software or fos and uh allows us to sort     
1:50:32     
of develop a strategy so neurod Dean strategies to work with scientists and developers helping them to directly     
1:50:39     
integrate their software with the Debian operating system so using this you know     
1:50:45     
Linux distribution we can integrate the software into that and then people can use that and it's all open and you know     
1:50:53     
it doesn't cost the labs very much to implement uh so they they kind of     
1:50:59     
they're trying to sell neurod Debi in here and Debian in particular um there's     
1:51:05     
of course neurop Fedora which is a different platform and of course Morgan is very familiar with that um and I mean     
1:51:12     
I I started it because of these guys oh okay yeah so yeah they talk about having uh     
1:51:19     
strict Open Standards so the other problem of course in scientific like     
1:51:25     
software development is that you know we don't have good standards and this is true for like open data as well that we     
1:51:32     
need to have standards of people adhere to if we're going to throw things out into the world you can make things like     
1:51:38     
kind of just throw them out there and if they don't follow standards if you don't have good practices that are you know a     
1:51:46     
lawful replication then the things that you put in the world aren't useful you     
1:51:51     
know particularly useful so you know this is where they have Open Standards     
1:51:56     
where they want a maximum interoperability of all components without sacrificing robustness or     
1:52:04     
creating unnecessary burdens so this is uh they kind of go through all of this     
1:52:10     
they talk about how widely used neurod Debian is around the world and it's of course most of the industrialized world     
1:52:17     
with some you know uh well it's pretty worldwide I think d distribution wise um     
1:52:24     
and so it's pretty representative of the world um and you know we have these uh     
1:52:32     
you so not only is it built for widespread use and replication and um sort of this     
1:52:40     
professional standard of software development but it's used all around the world     
1:52:45     
so this is one paper where they kind of advocate for certain Open Standards in     
1:52:51     
science and then this is an article more on um     
1:52:56     
reimagining peer review so this is a different issue in open science this is where we need to kind of rethink peer     
1:53:03     
review because you can have usually the way peer review works is you might have     
1:53:09     
two or three reviewers on a paper those reviewers might have different abilities     
1:53:15     
to sort of scrutinize your paper um and so you make it through those hurdles and you get published of     
1:53:22     
course as we know from a lot of the studies that have been retracted you know sometimes you can commit out andout     
1:53:27     
fraud by manufacturing data or manufacturing figures and you can get     
1:53:33     
through those hurs pretty easily and still get your paper published sometimes in really reputable journals and so the     
1:53:39     
whole idea of peer review is that you're kind of trying to be held accountable by     
1:53:46     
peers but the problem of course is because you only use a a very small number of peers     
1:53:53     
that you know that that can be sometimes it can be a barrier where your peers don't want something     
1:53:59     
published or where they have a beef about some you know Theory or something     
1:54:05     
so it can be a problem there but also that you know you only have like three eyes on it and they usually don't like     
1:54:11     
say scrutinize the data the numeric data where they don't think too much about the figures and so this can be a problem     
1:54:18     
where you actually don't get the desired result so they people want to reimagine peer     
1:54:25     
review there's been like crowd sourcing there's been other types of peer review open comments on papers um but when we     
1:54:33     
do this we also need institutional buyin so this article is reimagining PE review     
1:54:39     
needs Publishers and institutions that collaborate so the abstract of this     
1:54:44     
paper reads collaboration between academic institutions and Publishers is     
1:54:49     
essential for advancing ongoing peer review reform despite being an important process in     
1:54:55     
scientific publishing the flaws of the current models of peer review used most by Publishers which are usually the     
1:55:01     
model where you have an editor and you have a couple of reviewers and the editor will send it out to reviewers the     
1:55:07     
reviewers will give their reports back the editor then makes a decision and     
1:55:12     
then you know it's either kind of driven by the editor or driven by the reviewers but in both cases you have people who     
1:55:20     
maybe don't understand the paper fully or maybe have a bias or maybe don't um     
1:55:27     
you know don't scrutinize the paper at the level that maybe it's scrutinized that later uh so like the numeric data     
1:55:35     
or you know details of the figures and there are things that you know it's just it's human error it's Collective error     
1:55:43     
it's that you're not sampling enough from your peers or something like that so this is there are a lot of flaws     
1:55:50     
actually in peer review but um the flaws of the current peer current models of peer review used by most     
1:55:58     
Publishers are increasingly recognized and include inefficiency inconsistency bias and a lack of     
1:56:05     
transparency so these are the kind of the things that they've identified fortuitously numerous journals and     
1:56:12     
related organizations have leveraged the transformative potential of preference to already initiate positive changes uh     
1:56:20     
our over active support for academ institutions or active support from     
1:56:25     
academic institutions influential in shaping researchers careers and cultures     
1:56:30     
is crucial too this potential collaboration would offer mutual benefits Foster more responsible     
1:56:36     
research assessment help we imagine peer review and ultimately promote a healthier research culture so in this     
1:56:43     
case we're talking about institutional buyin from people doing open science     
1:56:50     
just not you know not only the the science scientists and the peers were reviewing it but the institutions as     
1:57:05     
well um any comments or     
1:57:13     
questions yeah peer     
1:57:20     
reviews it's like one it's it's almost like a deeper     
1:57:30     
social not problem but     
1:57:35     
um it's also managing me like like we I think we talked about Friday it's like managing the expectations of what comes     
1:57:42     
from peer review yeah you know and     
1:57:49     
and managing the difference in expectations that comes from     
1:57:54     
here because different people have different ideas right you know then     
1:58:00     
there's there's there's you know and the many the many the many     
1:58:08     
things the many different problems that lie behind reviewer two oh     
1:58:15     
yeah or reviewer three yeah or yeah yeah yeah yeah yeah um     
1:58:27     
yeah yeah I mean you know also don't want to make it a free-for-all so that people can be you don't you know it's     
1:58:36     
it's but like like we said like you know it's not it's not exactly it's not     
1:58:42     
designed um nor perhaps even appropriate to treat it as a you know fraud     
1:58:48     
detection right you know right it's um it's a um yeah it's a it's a review but     
1:58:57     
it's hope you know in in a hopefully collaborative kind of way right right     
1:59:04     
you know it's it is hard for us to not treat it     
1:59:10     
like it's your grading papers yeah you     
1:59:18     
know it may be because we're asking academics to multitask so much and     
1:59:23     
grading papers is big part of     
1:59:32     
things yeah humans are other than computers it's hard to switch off     
1:59:37     
certain things that you're spending a lot of your time doing     
1:59:43     
yeah but uh yeah um just U sort of to     
1:59:50     
follow up I think I posted this but I don't know if you saw it but um Gom the     
1:59:57     
previous lead developer of SPM which is the kind     
2:00:04     
of certainly one of the Premier Tools in in functional your     
2:00:10     
Imaging um you know and a mat lb package that goes back to the 90s and and is is     
2:00:17     
basically Carl friston's You Know Carl Carl friston started it and and it is     
2:00:23     
the repository for his many many uh     
2:00:30     
computational contributions to to statistical parametric mapping right     
2:00:35     
which is the name of the tool itself right um he's moved on     
2:00:42     
yeah like like I I I see that you know like last year for like it's only been     
2:00:48     
like a year he's he's moved I I did ask him if he's     
2:00:55     
uh I asked if he's still working on octave at all as as you know an open     
2:01:02     
source developer and if he's um you know still still interested in giving a talk     
2:01:08     
in that kind of um speaking to that kind of work um but     
2:01:14     
but he might be lost to Industry     
2:01:20     
yeah um and then just thinking about     
2:01:36     
um I'm just just trying to remember what his um okay it is the center for open     
2:01:43     
Neuroscience okay yeah yeah so I kept on thinking Center for Science which of     
2:01:50     
course is the Virginia think but it's yeah Center for     
2:01:56     
open Neuroscience do org so he he would be a good speaker     
2:02:05     
yeah you know and and he definitely has he definitely has talks on the subject     
2:02:13     
yeah as you can see like I I I knew or you know I I had email contact     
2:02:23     
with him when he was still a grad student in Ruckers and     
2:02:29     
um and his his advisor was that um Nur     
2:02:35     
imager that was quite involved in kind of early neural network work I'm blanking on his name     
2:02:42     
right now but Ste Steve something     
2:02:48     
um but like like good early yeah early     
2:02:54     
90s neural network work you     
2:02:59     
know did you have more papers um let's see so this yeah this one here we'll     
2:03:06     
talk about this um this is a paper that uh ricar and Michael leer own um this is     
2:03:14     
called open problems and synthetic multicellularity and kind kind of talks     
2:03:20     
about some of the things you were talking about with ECT to Neuroscience um this is a concept paper     
2:03:26     
that they put out online recently so yeah this is open problems in synthetic     
2:03:31     
multicellularity so the abstract of this U is multicellularity is one of the     
2:03:38     
major evolutionary transitions so you know we think about evolutionary transitions what kind of is has led to a     
2:03:46     
lot of the bio complexity we see in the world today one of those is single cells living you know alone and then single     
2:03:54     
cells living in colonies and then single cells living in these multicellular communities where you know     
2:04:01     
they resemble tissues which are functionally interdependent and you know so you can     
2:04:08     
have single cells kind of living their lives in the world you can have these     
2:04:13     
single cell collectives where you have like you know different colonies and then you have     
2:04:19     
this multicellularity which is where cells become interdependent and tissue or something like that just this Evolution     
2:04:26     
or a transition you see those intermediate steps cell around in like organisms like yeast but this idea that     
2:04:34     
you have this evolutionary transition where you go from cells being self uh sort of self-reliant to cells being in     
2:04:42     
this community um so the rise of multicellularity provided the     
2:04:47     
ingredients for the emergence of a biosphere inhabited by complex organisms over the last decades the potential for     
2:04:54     
bioengineering multicellular systems has been instrumental in interrogating nature in exploring novel paths to     
2:05:01     
Regeneration and disease as well as cognition and behavior so this is kind     
2:05:07     
of where they're talking about these sort of you know this is much like what Mike 11 does with you know um cell uh s     
2:05:17     
synthetic systems and then also some of his work on tamame because what they're     
2:05:23     
going to be doing is um engineering cell collectives that have certain     
2:05:30     
competencies cognitive competencies and then of course recurs is interested in sort of the     
2:05:38     
complexity of that and how you know we got there through Evolution and um how that complexity is     
2:05:46     
managed so this is kind of you know they kind of go over a list of open problems     
2:05:51     
s ongoing in future challenges in the field and conceptual approaches that may facilitate progress     
2:05:59     
so this is kind of a sort of a taxonomy of natural and synthetic     
2:06:05     
multicellularity so you have natural C multicellularity you have this governed     
2:06:11     
by a number of different mechanisms so again the word mechanisms uh you have     
2:06:16     
hierarchical mechanisms and that's something you see in the embryo in this case this is a     
2:06:24     
roph embryo where you get uh striping you get different pattern formation this     
2:06:30     
is governed by hierarchical gene expression and you know we have this kind of you know where the cells sort of     
2:06:38     
uh work collectively to form these patterns in the Embry you also have emergent mechanisms so this is an embryo     
2:06:46     
of a vertebrate um where you have this uh emergent mechanisms where the tissues     
2:06:53     
are formed through sort of these through this emerging complexity and then you have evolved complexity so this is I     
2:07:01     
guess a group of multicellular cells um this is evolve cell assemblies     
2:07:08     
emerging under synthetic selection mechanisms so this is where we can do sort of uh artificial Evolution or or     
2:07:16     
simulated Evolution experiments where you get these ability to form these     
2:07:21     
multi cellular complexes so those are natural examples then we have synthetic     
2:07:27     
examples where we have uh again the hierarchical mechanisms the emerging     
2:07:34     
mechanisms and the evolved complexity so in B we have a synthetic band pass filter using engineered     
2:07:43     
eoli C is um let's     
2:07:49     
see I don't know oh okay I think they labeled B twice uh but I think this is C     
2:07:55     
the generation of multiple coexisting sulfates in this diagram you can see the     
2:08:00     
different colors D is programmable symmetry breaking and do structure formation so     
2:08:07     
this is where we have basically structures coming from uh where you can     
2:08:12     
program symmetry breaking between cells they form different tissues and you get this differentiation within this Mass     
2:08:21     
um and then morphogenetic processes are spatially organized your multiscale     
2:08:27     
feedback loops shaping embryos and this is where we talked about f g and H so these are the     
2:08:34     
emerging mechanism examples f is a kidney organoid development example here     
2:08:40     
you can see the organoid it's not you know it's basically a bunch of kidney     
2:08:46     
cells kidney like cells in this organoid um G is turning like branching     
2:08:52     
morphogenesis of bacteria so you can see in the culture here and you see this     
2:08:58     
branching coming out from a central core this is a bacterial Colony it's showing     
2:09:03     
the sort of Turing reaction diffusion um pattern formation mechanism     
2:09:10     
then H is the development of anthropods so this is uh one of like a xenobot but     
2:09:16     
I guess it's an anobot I don't know what the difference is uh maybe they're using human cells for this instead of zenopus     
2:09:24     
cells but basically this is one of their yeah one of their examples epithelial     
2:09:32     
C so this is where you're creating this hybrid uh robot but with cells from a     
2:09:39     
cell culture um then evolved complexity is J K and L uh J is     
2:09:48     
um um yeah they didn't label their figures as     
2:09:56     
well as I could have here um I guess this is     
2:10:03     
basically of so evolve cell assemble these emerge under synthetic sele     
2:10:08     
selection mechanisms including cell cell adhesion to escape from predators so J     
2:10:14     
is the cell cell inhesion example K is adapted from this reference     
2:10:20     
eight and then xenobots are here so this is a xenobot so you have these different     
2:10:26     
versions of sort of mechanisms and ways to get to this     
2:10:32     
complexity then you have examples from the natural world then a lot of examples from the synthetic now when they say     
2:10:39     
synthetic they mean like under controlled conditions so like a bacterial colony is not really synthetic     
2:10:45     
in the sense I guess you can program The genome but like you know some of these     
2:10:50     
are computation some of these are sort of hybrids some of these are organoids and some of them are cell culture but     
2:10:57     
basically it gives you I think a good overview of what we can do biologically     
2:11:02     
and what occurs in nature um so this is uh you know the     
2:11:10     
current landscape of synthetic multicellular systems can be roughly decomposed into three partially     
2:11:16     
overlapping classes so this is where they get into sort of the structure of the field and the challenges that we     
2:11:22     
have uh to sort of deal with so the first is synthetic multicellular     
2:11:29     
circuits and so this class involves cellular circuits that have been modified or introduced through genetic     
2:11:35     
engineering with living cells typically used as a chassis so this is like your xenobots or your anthr robots um and     
2:11:43     
then many designs within this domain rely on a modular approach to Circuit complexity based on standard     
2:11:50     
combinatorial circuit design cellular consortia have been used as a multicellular implementation of all     
2:11:57     
kinds of simple responses from comining combining Boo and gates to pattern     
2:12:03     
formation these designs involve strains interacting through chemical signals propagating in a liquid medium or     
2:12:10     
diffusing over short distances on a nagar plate so you can build these synthetic multi cellular circuits which     
2:12:16     
are Gene circuits that do certain things Express certain um products     
2:12:22     
or you know they actually can fit together to give you this great circuit     
2:12:28     
complexity that can perform things like computational functions like Goole and Gates or involve pattern     
2:12:36     
formation and that's you know something you can design so like a lot of your     
2:12:41     
bacterial um you know example P bacterial pattern formation that we saw there was this sort of thing uh we also     
2:12:50     
have programmable Sy IC assemblies the next step towards engineering multicellular system exploit the     
2:12:56     
predictable properties displayed by adhesion driven spatial Mora Dynamics so     
2:13:02     
this is where we had these ad you know these cells that were joined by adhesion     
2:13:07     
and we have they're distributed in space and we can sculpt those kinds of     
2:13:12     
assemblies in a in a very profound way given you know our interventions again this bottom up     
2:13:19     
engineering law is predicting or programming the outcome of the final spatial structure it was easily     
2:13:25     
understood that cell sorting be with different adhesion energy or cell     
2:13:30     
sorting diff due to different adhesion energies could easily explain self-organized aggregation of a set of     
2:13:36     
randomic cells so you know when we did early cell uh culture     
2:13:42     
experiments with cells in you know that kind of Clump together people understood     
2:13:49     
the role of adhesion they understood sort of later we get these adhesion proteins that would uh you know be     
2:13:57     
responsible for this and so you can actually understand this in terms of     
2:14:04     
adhesion energies and differential adhesion energies across space and this describes sort of how these get     
2:14:11     
aggregated into specific patterns and or you know randomly mixed     
2:14:16     
cells and there's like reference 48 and 49 here I don't know what those     
2:14:23     
despite the self-organized nature of these processes it is possible to make some predictions concerning the spatial     
2:14:29     
Arrangements at a steady state so these are where you're programming Assemblies of cells um you're dealing with the     
2:14:36     
adhesion of these cells and you're sculpting the multicellular U milu and finally     
2:14:44     
synthetic morphology and gential materials so one way of moving beyond the cell level engineering involves     
2:14:51     
considering cell collectives as a gential materials and this is what Jesse's been talking about earlier in     
2:14:56     
the meeting these systems exhibit emergent properties at the system level that cannot be understood in terms of     
2:15:03     
the properties of the constituents so these are genes and cells so this is where we're looking at mechanism but at     
2:15:09     
a higher level than genes or cells we're looking at it at the material Level or     
2:15:14     
at the morphological level so cells the collective of cells are the the material     
2:15:21     
the material then has the level of agency not the cells or the genes and     
2:15:27     
this is what they're getting at with um agential materials and so you know this     
2:15:32     
would be important if you're trying to develop say a smart material or some new     
2:15:37     
material that you wanted to program the shape of or the the U the other physical     
2:15:46     
properties uh like hardness or you know other things so this this is something     
2:15:51     
that we definitely you know uh it kind of relates this idea of     
2:15:57     
mechanism um this approach takes advantage of higher order properties of embodied living matter such as memory     
2:16:04     
context sensitive navigation of problem spaces and homeostasis perform computations and     
2:16:11     
design morphologies beyond the bottomup principles of synthetic biology so this     
2:16:16     
is where we're doing this bottom up stuff in synthetic biology and and we're programming assemblies we're building     
2:16:23     
circuits but then we have this agential material that you know concept that is     
2:16:29     
sort of the top down aspect of this so in a lot of complex emerging systems you     
2:16:36     
have the bottom up components that are sort of the uh you know the effects of     
2:16:42     
lower levels like genes or cells and they're contributing to sort of the     
2:16:47     
shape of the collector and then this sort of aspect of the material layer or     
2:16:55     
the morphological layer constrains what that those things do so     
2:17:00     
you know this is where you get the sort of constraint on these things that are coming through the bottom up so this is     
2:17:08     
kind of you know speaking to complexity Theory but also speaking to some of the things they're doing in multiple layers     
2:17:14     
to engineer these materials and morphologies these this approach takes     
2:17:20     
advantage of high order properties of embodied living matter uh to perform computations and     
2:17:26     
design morphologies beyond the bottom of principles of synthetic biology this class includes organoids and     
2:17:32     
biobots and other multicellular assemblies capable of collective responses in space and time and novel     
2:17:40     
forms of behavior so if we look at some of these     
2:17:46     
references um so 35 is     
2:17:53     
so you can go back to 35 that is of course uh this paper rewiring zels     
2:18:00     
synthetic biology is a tool to interrogate the organizational principles of living systems this is     
2:18:06     
back from 2010 this is annual annual review of biophysics     
2:18:19     
um um so that's yeah if we look at the references here then we can see that there are a lot of     
2:18:24     
different references uh in general we have uh different as you know     
2:18:32     
different references of multicellularity and evolution uh this paper here synthetic     
2:18:38     
symmetry breaking and programmable multicellular struction formation this is from 2023 in cell     
2:18:45     
systems uh we have papers like this paper the origin of metazoa     
2:18:51     
a unicellular perspective this is where we're looking at the origin of animals uh as individual cells and kind of     
2:18:58     
coming together so yeast actually provide a really good example of this um     
2:19:04     
where yeast are medaillons but they're single cells sometimes they live in these multicellular Aggregates and then     
2:19:11     
of course the common ancestor of yeast with us you know those are obviously     
2:19:19     
multicellular um and so multicellularity has come to sort of a     
2:19:24     
refined uh you know existence with metazoa so some of these things you know where     
2:19:31     
we have the physiochem uh physiog gentic determinants in the evolution of     
2:19:37     
development this is from Newman in science 2012 dynamical patterning modules a     
2:19:43     
pattern language for development and evolution of multicellular form this is a developmental biology paper some other     
2:19:51     
papers from bongard and Len uh scalable pipeline for Designing reconfigurable     
2:19:56     
organisms this is a pnas paper from 2020 this is blackest bongard L and     
2:20:03     
krigman biological robots perspectives on an emerging interdisciplinary field     
2:20:08     
this is from Soft Robotics in 2023 and     
2:20:14     
uh let's see there's a paper on synthetic symmetry breaking in programmable multicellular restructure     
2:20:21     
formation this is cell systems in 2023 this is wford at all so you can see that     
2:20:27     
there's a lot of uh pre prior work that this was based on kind of going through     
2:20:33     
the world of sort of synthetic biology the evolution of     
2:20:38     
multicellularity and some of these papers on you know developmental biology     
2:20:44     
and uh developmental pattern formation and then linking that to uh soft     
2:20:55     
robots so that's uh just kind of a cursory overview of that paper I think     
2:21:00     
it lays out sort of the a you know what what's involved in that field what people are looking at and sort of     
2:21:06     
unifying sort of multicell origins of multicellularity with some of these synthetic biology approaches and really     
2:21:13     
kind of getting at the question from a different angle than what a lot of people are interested in you know which     
2:21:19     
is kind of like the finding what multicellularity is and then looking at saying that you know it's kind of maybe     
2:21:26     
inevitable and you you see with synthetic biology you have a lot of variants that maybe aren't obvious uh     
2:21:33     
examples we see in evolution so um I think it's a good paper um you know I didn't want to get through     
2:21:41     
all the details in it but basically that's the take from message I think     
2:21:48     
yeah yeah well I mean it it certainly is the kind of the kind of     
2:21:54     
thing we expect from Le at this point yeah where it's like he will have a     
2:22:00     
different take yeah or you know it's not it's not he will have a different take he he will bring you to see everything     
2:22:07     
in a different way yeah um and     
2:22:15     
and yeah um I mean it's a it's a it's a great paper     
2:22:21     
you speak speaks to that that uh     
2:22:26     
um collective intelligence view of things right right that that     
2:22:34     
that really is so profound and     
2:22:40     
and um yeah just per permits so many     
2:22:47     
different yeah kinds of behaviors and and     
2:22:53     
um needed you know kind of new fields to handle all the different ways     
2:23:02     
but yeah yeah um so I I I mean this is     
2:23:07     
this is great I I've been um trying to watch more of James glazers     
2:23:17     
talks okay you know yeah and you know and trying to think     
2:23:26     
about I mean like his I forget what he calls his class but it's something like     
2:23:34     
introduction     
2:23:40     
to it's like system biology a network perspective I think or something like     
2:23:46     
that right um and just how you know     
2:23:54     
is there's there's already so much there and that's really just kind of like it's     
2:24:01     
that's mostly just like the OD version of this yeah right that that like it's     
2:24:08     
not it's not really trying to get at some of this this much more complicated     
2:24:13     
stuff well I want to say to get it's still not even at this     
2:24:19     
perspective right you know um uh     
2:24:24     
although compy cell 3D certainly has has models that that start to get at this     
2:24:32     
but I was just wondering about how     
2:24:40     
um like like one trying to think about what's the     
2:24:45     
new biology kind of set of texts and classes yeah and and certainly James     
2:24:53     
glazier's like like a start maybe this is more of systems biology yeah set of set of classes     
2:25:03     
um there's there's a I I I posted this     
2:25:09     
that that he one of his posts is producing a kind of multiscale course     
2:25:14     
okay and I posted a link to it I think they're calling it like like     
2:25:21     
embryo like e MB r i o right right right     
2:25:27     
what channel is that I think I might have put done     
2:25:34     
D because um it seems kind of in line with     
2:25:39     
some of the yeah yeah this is things you cover there embryo multi scale modeling     
2:25:45     
course yeah yeah yeah you know and and again there's good stuff there um     
2:25:52     
there's another kind of like biological     
2:25:58     
or genetic circuits from Caltech     
2:26:03     
anyway the main thing being these are these are all interesting but     
2:26:10     
um the the the other thing that I don't know if they talk about and I'm I'm     
2:26:17     
curious when L will get to because you know he will yeah uh um is     
2:26:24     
like Immunology okay right like like how how does Immunology     
2:26:30     
differ in this you know um because when they're talking about a     
2:26:37     
gental material they are kind of talking about multicellular yeah yeah you know and     
2:26:44     
like and it's super interesting anyway I I was just thinking about um     
2:26:51     
James Glazer does a weekly course well no sorry weekly seminar     
2:26:58     
series Thursdays it's noon Pacific time because I can't make it because I     
2:27:06     
got another meeting yeah and um there's     
2:27:11     
like three meetings that same that same hour um     
2:27:18     
and you can glim glim print I don't know what the     
2:27:25     
acronym is anyway that that's their     
2:27:33     
um Glen pr.org     
2:27:38     
yeah Global a Global Alliance for immune prediction and     
2:27:44     
intervention glint anyway it's just really interest you     
2:27:50     
know there's there's a lot of their work in terms of like digital twins with you     
2:27:56     
know with Immunology right right and just just the kind of the weirdness of     
2:28:02     
Immunology yeah you know it's     
2:28:07     
and you know as if biology needed more complexity     
2:28:13     
yeah but but     
2:28:18     
um wanted to mention it because he's he was saying as well that he's actually     
2:28:24     
looking for help on things like just the website and stuff like that I was gonna     
2:28:30     
kind of nose around a bit okay but just also you know like like as as as     
2:28:40     
interesting as this is it doesn't always get in the kind of the interesting things that the immune system does and     
2:28:47     
there was another interesting talk on um and I forget where this is from but um     
2:28:53     
um do microbes have immune systems oh okay and and which made me think a     
2:29:00     
little bit about the um the the the the French paper on you know the the you     
2:29:09     
know kind of brains in single cell organisms right you know it's a similar     
2:29:16     
thing right it's just like like can can a single cell creature have an immune system just like can a can a single cell     
2:29:24     
creature have a brain which which strikes you as a kind of multi future     
2:29:30     
yeah all right yeah that's great well thanks for the feedback and and that was     
2:29:35     
a good good paper uh so yeah uh next week yeah we'll we'll keep up the     
2:29:42     
conversation in slack and um see you next week take care take care bye
