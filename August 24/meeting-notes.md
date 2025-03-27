## Meeting Recording

[YouTube link](https://youtu.be/CMKgMSoKawc)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113032188525201946)

## NOTES
Medium post on Sarrah's project, final post.

* code changes -- pull requests, docs, posts, and code repo.

* LLAMOSC --> descriptions. Contributor, maintainer, agents.

Trevor: proposal on sonogenetics for mental illness.

* pre-clinical models are the standard.

* meet the program manager (Boston, SF). Logan, Jesse are in Boston.

Jesse: Experiential learning, project infrastructure.

* focused research organization. Twirlybirds, writing process, vantage points discussion.

* world models paper -- work on this in CybRG and CogFutures.


Calls for internship, projects. Gamedev concentration, PlotTwisters.


Allostasis Machines -- papers, what defines a project?

* computational psychiatry and cognitive architectures.

* SOAR, Ron Sun's model. Groups with software projects. Organically-inspired.

* Brain Inspired podcast -- imaging --> brain structure --> computational representation --> behavior (Carbon Copies).


Different architectures can give the same behavioral output.

* collect measurements, test developmental systems.

* efficiency of developmental systems.

* out-of-distribution experiences. 

* deep reinforcment learning --> efficiency.


Innate biases, continual learning. Multi-agent learning --> Game of Life (super-embodiment vs. super-abstract).


Brainfuck programming language -- makes everything more complicated, on purpose.

* Google DeepMind --> flip bits on strings randomly (Sebastian Risi's work).

* programs with desire to keep going.

* NeuralMMO guy -- live coding. Agents goals, desires --> how many different architectures can drive this? 

* many different metrics. Model a system as a spring, then optimize.


Model equivalence: coupled spring systems, substituted for other models --> cable equations, coupled oscillators.

* dynamic causal models -- specify # nodes you want to model, connectivity.

* von Neumann -- playing with coupled oscillators. https://pubs.aip.org/aip/apr/article/7/1/011302/997386/Coupled-oscillators-for-computing-A-review-and

* limitations of vN architecture, KAM networks -- simulation + interpretability.

* model-free example. Indigenous examples -- redescription --> incorporate things.

* put representations to work. Successor representations. Putting people into situations.


What is the underlying cognitive architecture? Development -- common theme. Representations are not yet stable.

* successor representation. Representational efficiency vs. flexibility.

* redescription (Clark and Karmilov-Smith) -- Piegetian update.


U-shaped performance curve --> goes down before it goes up (with growth).

* multiple systems engaged in performance (collection of subsystems --> meta-brain connections).

* questions for Sutton's metacognitive understanding of RL.

## TRANSCRIPT     
0:01     
Hi how are you we goce Hi how are     
0:10     
you so I had yeah I created the final     
0:15     
blog for my submission I'll just put the link link to that in the chat box all     
0:23     
right um so yeah one thing I wanted to ask was     
0:29     
uh like it's if I put this link for my final evaluation right since it's hosted     
0:35     
on my own github.io page so yeah that should be fine as long as     
0:42     
it's a permanent um and it should be permanent yeah yeah it's a permanent     
0:47     
domain it's l to my GitHub account so till I have my GitHub account I have     
0:53     
domain as well okay yeah that's great um yeah let's     
0:58     
take a look at it yeah I can just present it you don't mind okay yeah go     
1:10     
ahead um yeah so uh this is the project     
1:15     
report uh so in the important links for the project have included uh the the     
1:20     
code change the code changes have included the link to all the full     
1:26     
requests that are authored by me and closed Within the duration of this     
1:32     
project um then next for the documentation and blogs I've uh included     
1:38     
a link to our medium page uh where the blogs have been cross     
1:45     
posted and uh next to the code for the code reest oh yeah I just yes I've     
1:53     
included the link to the medium page where all the blogs have been cross posted and uh then for the code     
2:00     
repository I have included the link to my folder within the g code repository     
2:06     
where I have um submitted all the     
2:12     
code and so yeah these are the main links that I've included right at the top of the blog so that anybody can go     
2:20     
to them and then I've just basically explained a bit about my project uh the     
2:26     
bir eye overview of um why I was doing this project and the fact that it was     
2:31     
worked on earlier as well uh in G 22 and 23 and I've kind of taken a different     
2:37     
approach leveraging large language models um and then I have explained the     
2:42     
need for the project um why I decided to take the llm route and what were the     
2:50     
benefits and after that I've just kind of uh explained in detail about the     
2:56     
actual lamos framework that I've created uh so this is just most of this is the     
3:01     
same as the read me and here I've included this diagram of the initial preliminary design that I had     
3:08     
created and then from it everything that I've implemented so far so most of the     
3:14     
things that I envisioned year have been implemented apart from subtask 2 and     
3:19     
subtask 3 which I have included in the future SC um but the main framework and     
3:25     
sub have been so this is just a bit more about     
3:30     
how all of the what are the different variables and the different components within the     
3:35     
framework uh then I've explained about Auto Rover about the automated request     
3:40     
life cycle uh powered by Auto Rover uh the two decision making algorithms that     
3:47     
we have created and the metrics the different metrics such as experience code quality motivation     
3:53     
levels and uh this is just a list of the various accomplishments throughout uh     
4:00     
ending with the screenshots of the graphical user interface that have     
4:05     
created and uh then in future improvements have included the issues that I created so each of these have a     
4:13     
links if there is anybody else in the future also comes across this and wants to improve on the project uh this would     
4:20     
be netive and then it's just acknowledgements uh so yeah I was hoping     
4:26     
this would be sufficient for the final valuation     
4:31     
yeah that's exactly what they want and usually people put it in a read me but this is better I     
4:39     
think so I'll be completing my evaluation mostly today or tomorrow okay     
4:44     
and uh could you push this to the uh uh our our medium yeah uh yeah sure sure I     
4:53     
that okay thank you yeah thank you yeah     
4:58     
thank you Jesse wanted to say something about it     
5:04     
oh no just saying um great I'm glad you're going to share that     
5:11     
with the link to the blog yeah yeah in the chat right yeah yeah yeah I'm I'm     
5:18     
sorry I didn't came through I was just saying that's that was good yeah oh do I just put it back or can you access the     
5:25     
link oh no it's fine and I was encourage Shing to Medi     
5:32     
no all right well thank you for the updates s yes we're concluding gck for     
5:37     
the year um we're moving to fall term and some of the things that we're doing     
5:43     
there um so we'll be doing uh you know hopefully some internships or you know     
5:49     
we'll be changing a little bit about you know like our open source meetings we talked about yesterday shifting Focus or     
5:57     
you know not doing not focusing ing on that so much in the fall and then you know trying to revive uh cybernetics and     
6:05     
cognition Futures and once I think this like the academic year gets started we can kind of focus on that     
6:12     
more um we had a diva worm meeting last week so that was uh basically all about     
6:21     
hypergraphs and networks and connectivity and networks and you know     
6:26     
it wasn't particular well it was a little bit biological but it was more most ly about the mathematics of network     
6:33     
connectivity and this followed up from uh Mah rora's project on     
6:39     
hypergraphs so this is you know kind of going over how do you build     
6:45     
representations of biological systems at the phenotypic level so you know we're     
6:51     
interested in celegans were interested in the cells but also things below the     
6:57     
level of cells but also things above the level of cells cells so we have cells um you know sometimes those cells     
7:04     
divide in in embryonic development sometimes those cells change their fate     
7:09     
they change their position so we want to capture all that information but we also have processes within those cells that     
7:17     
we want that are sometimes connected to what's going on in other cells sometimes not so we want to represent that as well     
7:24     
so that's why we're working on this hyper Network approach to um embryonic     
7:31     
networks and this is something in in the DOR group we've published on so this is     
7:36     
uh if you check that out on the evil Worm YouTube channel you'll see more um     
7:42     
on that meeting so it's just kind of an overview of methods um and so yeah um so I guess we     
7:51     
can continue with updates uh I don't know Jesse do you have an update     
8:00     
hey um I said most of my things yesterday     
8:08     
but briefly I'll say     
8:15     
um uh I believe we're gonna start properly     
8:22     
next week hopefully both commition Futures and uh the cybernetics reading group     
8:30     
again I know we'll be doing some things with the world models     
8:36     
paper um there's been a lot of previous movement on joepro stuff which is really good I'm     
8:43     
happy about that a lot um I as for other     
8:51     
updates um I guess the biggest not really news yet but things     
8:58     
in the works as um I have reached out to uh my home University or my previous     
9:08     
University um at Albany and I'll be meeting with them next week for one of     
9:14     
the Departments about uh like experiential learning uh I'll be meeting with the     
9:22     
main Center for that in two weeks and     
9:27     
then hopefully later in September I'll be me with some similar groups in San     
9:32     
Diego um there's also like the I think Morgan mentioned yesterday the data science     
9:38     
Alliance which is a really cool group that I didn't realize a lot of the people that     
9:43     
I'm a lot of cool people at San Diego who I already have mentioned are doing     
9:48     
things in that in that space so hopefully more with them too um just a     
9:54     
short version it's mostly just like administrative stuff right now     
10:00     
um I am continuing to organize some of the project     
10:05     
infrastructure for Joe Pro working groups um there's been a few things     
10:12     
Avery's Avery's had a few like potential projects that are upcoming and uh Jen     
10:22     
has done a lot already in the mental health working group um I     
10:29     
I may say more about that next time but um it's been nice to see those things     
10:34     
come along so uh that's that's my general updates for right     
10:41     
now that's good um yeah I know it's like you're kind of getting ready for fall and things are kind of Shifting um so     
10:49     
I'm glad to hear that you're kind of reestablishing the ties of Albany I know     
10:55     
that we've done this in the past like two years ago we had a nice crop of interns and we did a lot of good stuff     
11:01     
there um hopefully you know we can yeah exploit that pipeline a little bit more     
11:07     
or yeah one of the things that I think we     
11:12     
like could discuss more not necessarily right     
11:18     
now is I know we talked you and I talked about this a little bit but like specific calls for like different internships of     
11:25     
projects um they're sort of at least how it used to be with Al she had to make a very very general post like what is your     
11:32     
lab what could you do there so it wasn't it wouldn't be like be an intern for this project it' be be an intern for the     
11:38     
lab yeah which I suspect is kind of the same thing but um what's nice is meeting     
11:44     
with my department specifically my former Department um I think we might     
11:49     
have a little more Nuance there and I do stuff with like game design too like I'm actually curious about     
11:56     
um I met someone some someone joined Nick wick on the coner chair     
12:02     
level uh this year as like a co-organizer and um they're like a Game Dev I don't     
12:09     
know if it's a major or like a concentration within their that     
12:15     
department and that's the CEST thing in general but also like um there be some dub tals into like     
12:25     
you know plot Twisters um which is you know we're not Super Active right now but I     
12:33     
think towards the end of the year the next year there may be some overlap there too so I'm going to inquire a     
12:38     
little bit about that so um but also we do a lot of things here     
12:44     
too uh but but specifically like what will we want you know what would we want to like try to solicit or get more help     
12:50     
on because I can mention all the I can mention Futures that I mention Society ethics Tech is kind of coming back     
12:56     
online this semester and everything like that um and I'm really excited about that but if there's anything kind of     
13:03     
like I mentioned a while ago on the slack like if people want to if they want any help reaching out to     
13:10     
either an organization or a university or an institution let me know because I     
13:15     
can I'll have some experience with that now we have a good pretty good track record of like positive things coming     
13:21     
out from that so if you want uh any help of that or you're     
13:29     
curious like oh yeah I'm with this group and I do stuff but you know how can we try to do more um reach out to to us or     
13:37     
to me specifically maybe we can talk about that     
13:42     
okay yeah we'll have to get on that I guess we're getting pretty close this just still always hard at the beginning     
13:48     
of the semester to straighten all this out but we'll get there yeah we should     
13:54     
revisit I know I think last meeting we talked about the cards that we had so     
13:59     
uh when to revisit those I haven't had really a chance to do anything with them I got to do that but I've been busy with     
14:06     
other things so PS and have it okay um that's great uh Trevor how     
14:14     
are you I'm doing well I um uh yeah I took     
14:20     
your feedback um my Lo proposal and uh you know I figure it has such a low     
14:26     
likelihood of being funded you know I changed it and then um I submitted it earlier this week and so um yeah put and     
14:34     
taken a a class with you so we'll see if um if if anything comes of it like said     
14:40     
I'm not holding my breath but uh fingers crossed I appreciate your feedback um yeah about at nothing else     
14:49     
super exciting my world yeah so yeah we uh yeah I enjoyed the     
14:56     
reading the proposal I think it's an interesting approach um I'm not really     
15:02     
familiar witho I guess it's one of these newer approaches that kind of just uh people are trying to figure out how to     
15:08     
use because I means it's like this like a lot of these nextg sequencing techniques and imaging techniques it's     
15:15     
like you know Finding exactly The Right Use case where it it's a benefit over some other method so you know I think     
15:23     
that actually it seems kind of like that's pretty clear what that might be um you know definitely can allow you     
15:30     
to look at um you know genetic effects but the thing you know you have to     
15:35     
remember is that you're you have to be mindful of your effect size so like if you're looking at Behavior you have an     
15:42     
effect size of like genetics but also like when you design the experiment the behavioral experiment it's got to be you     
15:49     
know pretty tight or at least you know has to be um pretty pretty specific to what you     
15:56     
want to look at to to augment that effect so that's that's I mean that's always a     
16:01     
thing I guess everyone struggles with is how do you find you know how do you     
16:06     
maximize the effect size in the experiment absolutely yeah I I spent     
16:13     
some time uh really delving into trying to find comparable any things that     
16:21     
because you know obviously you know nobody has access to this Tech like     
16:26     
Inhumans so you are at the mercy of of all the preclinical models and so um I     
16:33     
was yeah I found a couple of things and and then I was trying to yeah actually I     
16:39     
was able to find a different Tech that is used in humans and then trying to like Stitch it all together and so it um     
16:47     
yeah no I really appreciate it though it was um yeah you were dead on with the     
16:52     
advice so I appreciate it yeah yeah the other thing I would say is     
16:57     
like yeah a lot of these things you you submit a grant and it's like you know maybe it's a little likelihood of being     
17:03     
funded but you know it's something once you build a proposal or something it's easy to kind of recycle it you say okay     
17:11     
I have these parts here I have a good introduction a good uh you know kind of     
17:16     
what we want to do or what and then like you know the the impacts so once you     
17:21     
have that all worked out you know it's easier to do it for the next round or the next thing you want to submit it to     
17:29     
absolutely yeah it's comforting to feel that it may not all be totally uh non     
17:36     
recyclable well yeah a lot of things aren't but like you can take the parts like you basically don't have to do the     
17:43     
I mean you probably want to keep up on the literature review obviously like if new papers come out U you know kind of     
17:50     
make them you know have like a citation editor put them in make sure that they're going to be there the next time     
17:57     
you do it because like in a field like that it moves pretty fast you get new papers you get new new versions of what     
18:04     
they're doing and so it's it's always good to have but if you have that basic you know kind of how it the basic     
18:12     
framework you know you've done they've done animal models they've done     
18:17     
validation of a tech then you know that's that doesn't change that much I     
18:22     
mean it changes a little bit but you can attach those new papers onto it and then     
18:28     
you know that like the aims are always I think the biggest problem when you recycle a grant you have to kind of be     
18:34     
mindful of your audience so like if it's like a grant where you know they're     
18:39     
looking like call them Innovation grants where people they want to Foster     
18:45     
Innovation versus like an NIH Grant or an NSF Grant which is more     
18:51     
specific andless you know usually less worried about Innovations but that's you know that's     
18:58     
just we we talked about this a couple weeks ago with respect to Grants um     
19:03     
where you know you have different places where they have different calls and you have to be specific and follow the     
19:10     
directions but basically you can use the same template and once it's there you     
19:15     
can you know you have something to work from you don't have to reinvent the de every     
19:22     
time absolutely do you have much experience like applying for DARPA grants or anything like that not really     
19:29     
I mean I think we tried it once but it didn't work I mean not not this group but another group I was in but that yeah     
19:35     
those are kind of tricky because you have to be invited more or     
19:41     
less yeah so you have to like I mean the better thing to do there is look at like what's coming out of the DARPA     
19:48     
grants sure interesting um I think I put it in     
19:56     
the chat that there's um they're doing like a a meet program manager thing     
20:02     
Boston San Francisco and I know there there's people I think seem to be in that area I think Jesse sounds like you     
20:09     
might be in Boston or something so I don't know if that's up your alley but check     
20:20     
something yeah Jesse's in Boston of course yeah I'm sorry I didn't quite     
20:26     
hear the Boston reference specifically but I'm heing no worries I I was just I I put a thing     
20:32     
in the chat I was talking to I think Logan um there's a a thing where you can meet     
20:40     
with um program managers sta program managers like next month or something so I don't know if that's oh yeah there's     
20:46     
some really cool like oh that reminds me I have to fill out um there's like     
20:52     
a focused research organization or something meeting too um that I'm going to try to go to like like like like like     
21:00     
alternate sort of ways of doing research um so yeah that's all really are are you     
21:05     
you're not in Boston are you tripping or like are you I'm in Bloomington Indiana yeah okay     
21:13     
yeah so no Boston trips my future but I've got um I think the I don't sure if     
21:19     
you're talking about the speculative Technologies thing but that be yeah okay yeah I spill out the little form I don't     
21:27     
know if they'll let me to the workshop but uh we'll see cool isn't it yeah     
21:33     
yeah let me know let me know     
21:40     
out yeah absolutely be good to hang out     
21:46     
yeah yeah it's great that's updates I don't know if Morgan when Morgan comes maybe he has     
21:53     
some he had some nice updates last yesterday's meeting in open source that     
21:58     
was a good meeting we had uh of course Sara presented her final presentation on     
22:03     
our project that's the uh large language models for open source     
22:08     
sustainability which actually came out did she did a really nice job on like     
22:14     
building a model and you know kind of building large language models as     
22:19     
deployed around some of these problems that we were talking about so we were talking about modeling a community of     
22:25     
Open Source contributors you know we have uh you know what she's done is like     
22:31     
created this set of tasks we're almost like generating an open source project     
22:37     
generating a very simple project that you know is something that     
22:43     
uh another agent contributor can address issues in create issues work on them     
22:50     
have a certain competency level and then you know all of that is basically a     
22:56     
simulation so you have all you know we talked about doing using agent based models or multi uh     
23:04     
multi-agent reinforcement learning models and you know that's this is an A     
23:09     
variation on that instead of having like each agent be like a reinforced learn reinforcement learning     
23:16     
agent or some sort of set of rules on a grid this is these are like a bunch of     
23:21     
large language models and Jesse said generative project Sims basically that's what it is it's     
23:28     
like you have a generative project generative agents working on the project     
23:33     
and then you get a sense of like what if you can see what the outputs are you can see what the issues are and then you can     
23:40     
see how they behave which you know um yeah I guess it's better than running     
23:46     
like just kind of Designing this hardcoding this stuff and then giving it to the agents because you don't know     
23:52     
what the agents are actually um you know picking up on or how they're performing with respect     
23:59     
which your hard coating so if at least if you wet these things you know if you use a generative approach to all of it     
24:05     
it's actually quite good um and so yeah and then um Cham is working they didn't     
24:14     
present yesterday but they'll present later but this is the multi-agent     
24:20     
reinforcement learning model but like kind of developed further along so uh     
24:25     
hansu chogle uh and and rvy Roger gopalan did     
24:30     
a lot of the work on the reinforcement learning agents the past two     
24:36     
years and shom has picked up on that and is kind of incorporating some of the stuff that uh Sara uh developed in terms     
24:45     
of generating issues and things like that so but that's going to be like a multi-agent reinforcement     
24:52     
learning uh you know based model so it's going to be different from Mar language models but you know it should give us     
25:00     
another set of tools to look at that problem so that's great that's that's a     
25:05     
lot of progress made on that and then of course yesterday we talked with I talked with uh Morgan about his involvement in     
25:13     
neuro Fedora and the Fedora distro of clinics and some interesting things I     
25:20     
think we've got some interesting things came up in that discussion um just in terms of how do     
25:26     
you manage soft software releases you know if you're doing like software engineering for scientific Pursuits or     
25:34     
you know something like that and that's not something that in a lot of science labs they think about they don't think about software engineering too much     
25:40     
unless you're in a software engineering lab or if you're in like a computer science     
25:46     
group you know that that skill isn't really isn't really developed at its     
25:51     
highest form so you know we talked about you know what do you do if you want to     
25:57     
sort of Leverage a lot of you know if you want to build software for people doing scientific computation they want     
26:04     
to you know take this Dro and use it out of the box how do you manage all the dependencies of all the free software     
26:11     
that is it's built upon how do you make it so that you know that Labs don't have     
26:17     
to pay thousands and thousands of dollars for good tools that sort of     
26:22     
stuff so it's really interesting conversation and that's on the orthoga lab uh YouTube     
26:30     
[Music] Chan yeah I like that I really like     
26:36     
we've had so many we've had so many good discussions in the open source meetings     
26:42     
yeah I feel like I almost want to like there there could be an intern who     
26:50     
just like basic segments things you and I thought about doing that just     
26:57     
techology um to to be continued the tle birds are ever Floy yeah sometimes they'll be     
27:04     
collected sometimes they that's I should we should probably write     
27:09     
something about I don't do we ever like mention like we've written about it in post but they make a post like the Twirly Birds um as as like bits of     
27:17     
information or discussion that kind of go through the air I I feel like this should be something the sort of like     
27:22     
it's a the lore of orthogonal lab it's sort of been this like not really in     
27:28     
side joke but just a specific terminology but even more so than that like I think I think um I don't know I     
27:35     
look forward to some of those uh there's a lot of a lot of things to     
27:41     
be written so and I seem to remember maybe something to that effect I don't think     
27:48     
it was like a full blog post it's like I remember getting pictures of T Birds I     
27:54     
remember that yeah I remember in yeah I think I mentioned it like I think I mentioned it in somewhere even in the     
28:00     
medium it's been mentioned there maybe but but it's not like not a like oh tly     
28:08     
birds and you know the challenge of you solidifying information you know segments of a blow     
28:15     
in the bra of discussion like you could you could you could do that anyway yeah um that's good     
28:22     
and I'm I have a whole bunch of things in my mind about writing about     
28:28     
the process like I still I I have to finish the like the     
28:35     
uh the Vantage points like it's it's finished as it the Vantage points     
28:42     
discussion that I showed I think a while ago and like other other top like I     
28:47     
think there's a really cool place to talk about those things so I'm happy     
28:53     
um I think I'm done yeah we can move on time oh it's fine     
28:59     
uh Trevor said N I don't know what that means sorry I'm I'm on my mobile phone     
29:06     
and I'm having just some technical issues that that not intentional sorry that's fine yeah     
29:14     
yeah uh you know sometimes you get cryptic things that mean something sometimes they don't it's like and Jesse     
29:20     
knows this especi especially when I say weird stuff yeah     
29:30     
okay all right so um well one of the things I did in the last two weeks well     
29:37     
we didn't have a meeting last week so one of the things I did during that time uh I was traveling we did the dvoor     
29:45     
meeting but I did do uh I attended Bika     
29:51     
2024 so we you know every year we contribute something to baika which is     
29:57     
the biological inspired cognitive architectur Workshop or conference uh the last three years     
30:03     
they've had a full conference um where they hosted it in a place so I think the     
30:09     
first year we participated they hosted it in Japan but it was largely online     
30:14     
because of covid uh the second year we participated it was in Mexico in     
30:21     
guadalahara but it was also uh virtual last year they had it in Ningbo     
30:27     
China so it was um put on by a Chinese group sponsored by them but it was also on     
30:34     
zoom and then this year they I don't know their sponsorship fell through so     
30:41     
they had to do something to to continue the U to continue the you know year     
30:48     
annual thing so they decided to hch their wagon to AGI     
30:54     
2024 which is the artificial general intelligence conference that's held in Seattle that had a lot of good speakers     
31:01     
in of itself and I didn't get to attend that but I did attend the Bea conference     
31:07     
and actually hosted a session uh on Zoom so let me open up the I'm gonna bring up     
31:16     
the EA schedule here so this is uh     
31:21     
biologically inspired cognitive architectures for AI this is always been a really nice mix     
31:28     
of people it's very much I guess you could say the anti-     
31:33     
nurs because it's you know not flashy like NS it's not necessarily even trendy     
31:40     
but it does have a lot of interesting there a lot of interesting talks you know people exploring topics that have     
31:47     
kind of gone maybe forgotten uh very International so you get people from all sorts of different     
31:55     
countries and doing things you know they're not like in even in I mean you know when we think of AI now we think of     
32:02     
like nurs large language models machine learning deep learning it's pretty much     
32:07     
it you know there's some other conferences but they're all very much like     
32:13     
the um you know they're driven by like intense competition of big Labs corpor     
32:21     
corporate people and so forth this is not that this is very um     
32:27     
very much you know and of course because it's not really AI it's it's cognitive architectures it's interesting that this     
32:35     
topic biologically inspired cognitive architectures I remember back in the Au like about 2006 2007 this was actually a     
32:44     
theme that that DARPA was working so this doesn't have a direct     
32:49     
connection to the DARPA project but like I said you know you watch the outputs of the DARPA projects and they kind of pick     
32:58     
up on very nent themes and try to develop them so if you know you have this theme     
33:05     
that people are talking about they might try to throw some money at it and see where they can take it so this is the     
33:13     
you know this is AA AI 2024 uh I don't know if they have I     
33:19     
guess this is yeah the whole conference I don't know if it's uneasy chair I know there was like a part     
33:25     
uneasy chair but they don't I don't know if we have let's see if I can     
33:35     
find okay this is this is these are the virtual posters um and so this is okay this is     
33:43     
the presentation schedule posters and everything so this is again you know uh     
33:48     
there were a bunch of presentations and posters there's going to be a collection of papers coming out of it and I did a     
33:57     
submission on my own but there you know other submissions here so there were a     
34:03     
lot of interesting things this one is Howard Schneider grounding artificial general intelligence with robotics The     
34:10     
petic Cat Project so there was like some stuff an embodiment on grounding the     
34:16     
grounding problem which is basically how do you ground cognition you know you     
34:21     
have to ground it maybe in symbols or you could ground it in embodiment and so     
34:26     
that's that's what that is and so you know this is very different of course from nurs because nups they're     
34:32     
not really worried about body too much they're worried about the number of layers you have in your     
34:38     
model uh Francisco Gomez development of a bioinspired computational framework     
34:44     
for the integration of attentional networks there is a lot of stuff on bioinspired models the discussion of     
34:51     
cognitive models of course as cognition like attentional networks that's     
34:56     
definitely qualif is cognition but you also have this bio inspired aspect where     
35:02     
you know we're worried about not just like a neural network a connectionist network but we have you know or like a     
35:09     
symbolic Network we have things uh like we're looking like two weeks ago we     
35:14     
talked about models of the hippocampus and things like that so you're actually using the existing     
35:21     
biological networks as inspiration for what you're doing so that could mean you know synaptic Computing then     
35:28     
Computing uh you know different like focusing on different circuits and kind of replicating     
35:35     
those um yeah some of you know there was some stuff on deep reinforcement     
35:40     
learning multi-agent simulations so it's not like they're ignoring that work it's     
35:45     
just that it's being Incorporated in different ways um there was some stuff on     
35:51     
cognition itself so it's not just all kind of like geared towards you know artificial intelligence     
35:59     
it's actually there's also there was a lot of good stuff on cognition on how you know uh you can use     
36:07     
cognitive models to address um you know uh disorders other     
36:14     
things um cognitive performance things like that so that was a you know so it's     
36:22     
pretty diverse in that way too this is an Adaptive dynamical System model for     
36:27     
development of schizophrenia epigenetics and false memories cognitive biases and     
36:33     
natural language automatically detecting differentiating and measuring bias in     
36:38     
text so U that was the first session then the second session I hosted this     
36:44     
one there a number of good talks in this section um the one I submitted uh was Al     
36:50     
estasis machines as continuous cognitive modeling so we worked on a uh about     
36:57     
three years ago was Jesse myself Avery and     
37:05     
um and uh no it's um I can't remember her     
37:11     
name now but anyways uh we worked on a paper     
37:16     
Onis Dana yeah yeah wow yeah uh yeah so     
37:21     
we worked on this paper on Al estasis machines and it was for the sigai conference was a workshop at the S Kai     
37:29     
conference and that Focus was on laying out this idea of an Al estasis machine     
37:35     
talking about Al estasis and cognition and linking it to     
37:40     
um to autopolis which of course is a theory of complexity a theory of that     
37:46     
merges cognition with biologically inspired stuff and so forth this is a     
37:52     
different take on Al estasis machines this was actually quite technical when it talked about how you would model     
37:59     
continuous cognition using anal estasis machine's approach briefly this is where     
38:05     
you have uh like a a cognitive architecture or a black box some process     
38:12     
inside of it it could be even like the simple as an oscillator or it could be like a cognitive model you know full on     
38:18     
cognitive model and then you have an output which is a trajectory and that     
38:24     
trajectory then is it's not important what the actual values are as the output     
38:30     
but the idea is that it gets perturbed by certain environmental factors and you get this ability to     
38:37     
recover to its original state so if I perturb the trajectory it either     
38:43     
recovers to its original state or it ex exhibits hysteresis which means it doesn't recover to its initial State and     
38:51     
it drifts off to a new state or it drifts off into something that's unstable and so you know I kind of     
38:57     
walked through that process talking about like cognition talking about the     
39:03     
sort of the dynamic dynamical systems aspects of that and then mapping that to sort of this continuous cognition idea     
39:11     
so that was an interesting talk it's on the YouTube channel it has a lot of views it has like almost a thousand     
39:16     
views already I posted it like three weeks ago and so people are interested in it uh the paper on this is coming out     
39:24     
soon so let's keep an eye and I I actually am going to do a larger video     
39:30     
on our involvement in V coming up you know maybe in the next two weeks uh I I     
39:36     
we have our um our openhouse Channel that I I put I     
39:42     
put a bunch of stuff in so like this is something I started in 2022 and I've been adding to it and I'm     
39:48     
going to add a video on our involvement in V uh to that so keep an eye out for     
39:54     
that as well Olga churn of skaya she did a nice talk     
40:00     
on the dynamic theory of information a lot of this was actually stuff we've     
40:05     
talked about in our cybernetics group and in our cognition Futures group uh a     
40:11     
nice approach of to Consciousness uh talking about like uh epistemic closure     
40:17     
and other things so this kind of an interesting approach it was very it was     
40:23     
more philosophical than a lot of the other talks but it was interesting um David Kelly uh he's like a perennial     
40:31     
presenter at this conference uh he did this uh he has this     
40:37     
like platform that he's working on where he's really focused on symbolic     
40:42     
computation and a lot of this so it's it's kind of it seems old school but it's actually quite interesting how you     
40:50     
know you can drive forward on some of the old school stuff and make progress and he's applying a lot of this not to     
40:57     
like robots or you know some sort of conscious AI but like stuff like project     
41:03     
management and stuff in it management so that's really     
41:09     
interesting um max tanov actually did a nice talk on the future neural networks     
41:15     
and energy consumption so this is something that uh of course is bi has to     
41:20     
be biologically inspired because you know you're drawing the neural network     
41:25     
uh Paradigm that we have of course is completely artificial it's abstracted     
41:31     
away from what the brain does and it performs you know fairly well but the energy requirements are very high and so     
41:39     
if you look at biological brains biological brains actually maybe outperform a lot of real     
41:45     
networks but their energy consumption is very low so the question is what can we     
41:51     
learn from biological brains how it does the types of cognition that say are     
41:57     
connectionist models try to approximate but with a very low level of     
42:03     
energy consumption and so he went through some things there uh in the discussion in that     
42:09     
session uh Peter karov also did a talk and heavy in spatial encoders with adaptive Sparks     
42:16     
connectivity basically talking about um the synaptic uh aspect of you know     
42:23     
cognitive models how that might work and Max and Peter got a conversation about     
42:29     
sort of the biologically inspired aspects of cognitive models it was really interesting then Carlos trov rounded out     
42:36     
the session uh computational model for Effective processing based on cognitive Sciences this is another uh approach     
42:44     
that is you know kind of focused on heterogeneity and cognitive models and     
42:50     
some of the things that uh you know kind of linking this to Performance human     
42:55     
performance in the a Ive realm which is the emotional realm and so you know     
43:00     
emotion has an effect on cognitive processing and so kind of bring those things together you know in a     
43:07     
computational model so yeah it was good and then there was a virtual poster     
43:12     
session I'm not sure that I have the poster list here but um yeah it was it     
43:19     
was good um and so actually they have some historical background here so uh be the     
43:27     
conference series was preceded by the triple AI fall symposia on Bika held in     
43:32     
2008 2009 so this is in the same period where they were a little bit later than     
43:38     
the DARPA project but they were thinking about this back in the As and you know kind of grew out of a lot of the earlier     
43:45     
AI uh you know some of the AI Winters where people realized that they needed     
43:50     
to sort of ground their models more in biologically inspired stuff in cognitive     
43:57     
you know there were cognitive architectures back in the 90s um but you know bringing those     
44:04     
forward um originally participants were mostly the members of the DARPA Bika program of 20052 2006 so actually was a     
44:11     
little earlier if I remember but so yeah this was like the the DARPA Bea program     
44:17     
you know ran this they DARPA will basically select their participants and they'll say you know can you do this     
44:25     
stuff can you solve this problem and then you're left to your own devices to do it largely but of course they can     
44:32     
pull the funding at any time if they think it's too uh it's not going the way     
44:38     
they like so there's a there's a tradeoff there with EA programs is that there's a lot of flexibility but it's     
44:45     
also you know they're just trying to see what people can do and if it's serving the needs of     
44:51     
unfortunately uh you know the military that's something I     
44:57     
ethical concerns about but anyways um yeah so this kind of grew out of this     
45:03     
20052 2006 era then people started getting attracted to it as a result in     
45:08     
2010 the Bea conference series was initiated as a separate venue managed by     
45:14     
a newly formed nonprofit the beika society so they've been organizing conferences around the world for 13     
45:21     
years and you know they go to a number of different countries demonstrating impressive of     
45:27     
success at growing progression the conference was complemented by schools in     
45:32     
symposia in total making 15 separate events Pika Society membership has     
45:38     
reached many hundreds and you know it's basically actually included a nice     
45:45     
virtual component which is this hybrid format which is what we're doing what we     
45:51     
usually participate in okay so that was DEA and have you     
45:58     
know there there there's a video of that talk I'm going to do another video of our involvement in Bea thinking about     
46:05     
like all the things that we've kind of not just presented at beika but a lot of the talks on those themes so there are     
46:12     
four themes that we've addressed in four years uh we've done Al estasis     
46:19     
machines uh we've done um trying to remember what they all were     
46:27     
um so yeah we've done the four themes and I'll put a video out on that soon     
46:32     
and kind of thinking about like some of the other things that we've done on those themes so not when we talk about     
46:38     
those themes at Bika we've talked about them at other conferences we have other papers and it's uh you know has like you     
46:46     
know it's basically allowing us to develop some of these ideas and draw them out and get     
46:53     
feedback so uh any questions or comments about that um no questions but I I I really I did     
47:00     
see like a video or some other videos that were like posted up and I I definitely look forward to going to that     
47:06     
and seeing both um the thing you have forthcoming but     
47:12     
um yeah I think I think that's something to to I don't know um H stasis machines     
47:20     
are that maybe that's something that deserves a product description of its own so yeah so     
47:27     
yeah yeah that's the thing about projects is that like you know there's a lot of stuff that gets done and then it     
47:35     
has we kind of revisit it from time to time you know we'll do maybe a couple papers and and then that's like kind of     
47:42     
maybe a standup project on its own so it's kind of hard to know kind of where those and you know drawing out a lineage     
47:48     
of the of the development of it so you say well okay this is from this project it's a new project or a new set of     
47:55     
things that come out of this idea so like you know we had I think we've     
48:00     
talked about developmental AI as a in-house code word for this stuff and then there's all this stuff that that     
48:06     
gets done in thinking about that and then those that's like a group of papers     
48:12     
and there's another group of papers in another area like if sonian information and so on and so forth so it kind of you     
48:19     
know if you have a couple papers in that area then you start to think okay well what is the you know maybe this is     
48:25     
something we need to get you know maybe an internship or you know some other     
48:32     
research opportunities built around because it seems to be something that they're thinking a lot about so it's     
48:38     
it's just showing this sort of evolution of projects why it's so hard to define a     
48:46     
project um was that the um biological     
48:52     
division stuff that is the biologically inspired cognitive architectures     
48:58     
conference okay right sure sure sure     
49:04     
um no not not off the top of my head um     
49:10     
sorry I um it's okay yeah Still Still Still rousing     
49:16     
myself this is pre coffee     
49:24     
yeah yeah and I I made the uh mistake of     
49:29     
also opening slack at the same time and then falling down a rabbit hole     
49:36     
of yeah it's they should just call it Rabbit     
49:41     
Hole yeah yeah yeah yeah anyway how's everybody doing this morning good good     
49:48     
yeah were really H we're kind of taking stock of our new you know kind of     
49:54     
transitioning the fall so thinking about that what was what were some of the um     
50:00     
sorry you probably spent like an hour going but but what was the big beika I I     
50:07     
I remember there was a there was a a good Bea example where     
50:13     
certainly um did they have like a headline     
50:19     
project um I'm not sure uh well they had the the uh DARPA project back in the     
50:27     
odds and that was uh you know where they would build uh you know cognitive     
50:32     
architectures were kind of in in Vogue in the 90s like Bron built this     
50:39     
cognitive architecture and there other people and you know it's kind of like they wanted to see where that would go     
50:46     
if you could put some biological inspiration into it so there were a number of examples of that and it the     
50:54     
conference is really like kind of diverged since then from like kind of strictly these cognitive     
51:01     
architectures another example of a cognitive architecture be like Sor which is the oh yeah yeah yeah okay okay which     
51:09     
they use a lot for game design and like programming agents and things like that     
51:14     
but you know they they kind of the idea is that you know you want to build an like a simulation of intelligence that     
51:22     
is based on cognition based on what we know about cognition least of course the cognitive science view we maybe want to     
51:29     
make that biologically inspired because of course you know and then uh and then     
51:35     
you know whatever that means like there were some talks on like you know looking at uh mental health and other things     
51:44     
like that using bi using cognitive architectures for that and so you know     
51:49     
that's another area where you could use those you could just simulate cognition and see where it     
51:55     
fails how you know but but these are all things that you have to kind of have the     
52:00     
right conception of cognition to do so yeah yeah yeah if I if I remember     
52:08     
right it's not not exactly you know not what I would call computational     
52:14     
Psychiatry um but definitely um yeah makes     
52:20     
me just just reminds me to look up the um there's a cool annual school or you     
52:29     
know some somewhat annual school it's like the cognitive modeling winter School in     
52:37     
India okay and they they get people from all the kind of different you know from     
52:43     
the like the sore group um there's a there's a group in     
52:50     
um like like UC Davis um     
52:57     
yeah they gathered together kind of like all the different I I would say let's     
53:02     
say like groups that actually have software software projects yeah you know     
53:09     
like like yeah um it's a great it's a     
53:14     
great meeting I I we we interviewed like maybe two two of the grad students     
53:22     
involved I think um anyway that was nice you know     
53:27     
and this was this was like during the you know like 20     
53:33     
2020s yeah yeah like like yeah um oh so     
53:38     
there was a beika 2021 yeah that's the first one we attended that was     
53:45     
okay sorry for being late guys I think Jesse like stumbled upon     
53:51     
like the involvement like call for involvement just kind of been     
53:57     
yeah no no that's that's cool last two years I've kind of done it on my own like you know there we we always have     
54:04     
opportunities to do that so yeah the     
54:11     
um it's it's hard to find the groups that that do this kind of stuff I mean     
54:16     
you know it's like like kind of stumble across them like um I think the first     
54:23     
time I I heard from some was um the brain inspired     
54:29     
podcast like like um yeah like then see yeah then i' find     
54:37     
find some GitHub page and they've been working on it for decades you know it's it's um it's it's interesting it's it's     
54:46     
I don't know if I would say biologically inspired yeah yeah cognitive science inspired or     
54:56     
Yeah well yeah it depends on what you mean by biology like right right yeah I     
55:03     
think that it's the large B like it's like you know if it's like something you     
55:09     
find in a real brain it's biological well yeah no yeah sure sure the um um     
55:17     
you know I know Logan I mean I I've invited Logan before     
55:23     
to to join us but I I know he's got a meeting same time um     
55:29     
but you know if if there's a biologically inspired I think of yeah     
55:35     
organically inspired the um you know it it might be a little like like their     
55:40     
whole brain emulation I mean in the sense that like like actually trying to     
55:46     
use you know trying to use Imaging to capture brain structure and then and     
55:54     
then imbue that would function computationally     
56:01     
and you know and get Behavior right right like like this is their um the the     
56:10     
work that he presented in um     
56:15     
um with a Dutch guy it carbon copies is     
56:20     
the organization I think okay yeah that um um     
56:30     
um and I forget what what I forget what model organism they     
56:36     
were they were targeting at this point in terms of their kind of like high     
56:41     
resolution x-ray you know connectomic Imaging I     
56:49     
forget that um any yeah gotcha     
56:56     
yeah I do I do I'm seeing some of this now it's     
57:01     
reminding me yeah um so they still but     
57:06     
looks like it looks like it kind of Peters out at 2022 uh what oh the work     
57:15     
for. oh no they have a whole series of uh talks like they have a website um     
57:25     
where they have the talk posted so it's like it last year was in China um but     
57:31     
yeah then this year it was like associated with AGI because they didn't have a a sponsor someone willing to host     
57:38     
it but AGI was actually an interesting conference I didn't attend     
57:44     
that but I know Gary Marcus gave talks there and couple other people yeah it's     
57:49     
just like basically the artificial general intelligence uh you know like it     
57:55     
it's not again you know it's not NPS it's uh but but     
58:00     
it's like more of the classical uh AI stuff     
58:07     
so I I got you I got you I got you sure     
58:13     
yeah certainly certainly SAR is is of that is of that type yeah the classical     
58:24     
yeah so yeah that's that's uh what I did that uh as I was traveling so I actually     
58:32     
hosted a session is all right um so yeah     
58:37     
uh why don't I get back to some of the updates that I've been I wanted to bring something else to     
58:43     
our attention and uh so I also worked on new     
58:49     
book review so there's this new book and I know people are um interested ining we     
58:55     
have a whole Channel and brenberg vehicles in the slack so this is the book here this is a new book by uh Scott     
59:03     
hoton and Jeff yosimi Scott hoton is a u     
59:08     
mathematician does a lot of stuff with topology and um other areas of     
59:15     
mathematics Jeff Yoshimi is actually a philosopher of cognitive science does a     
59:21     
lot of stuff with cognitive science and brenberg vehicles and they published     
59:27     
this book through MIT press the open dynamics of brenberg vehicles uh it's a really interesting book because they     
59:34     
look at brenberg vehicles from the perspective of dynamical systems so you     
59:40     
know you have your brenberg vehicles as brenberg to find them but what they're doing in this book is they're modeling     
59:45     
sort of these diads of brenberg vehicles in these geometric spaces so you know     
59:51     
they're kind of interacting it's not social interaction but it's like interacting based on these topologies     
59:59     
and one of the things one of the reasons why this is really interesting is because if you know anything about     
1:00:04     
brenberg Vehicles you know that brenberg talked about sort of two things in the book um     
1:00:12     
well three things the first of course is like assuming that you have to have an     
1:00:17     
embodied structure this is why they use Vehicles these vehicles have wheels they     
1:00:23     
have sensors they have a body with something with a some s connection set     
1:00:28     
of connections inside but there's the spatiality of the vehicle so the sensors     
1:00:34     
are at the front this the maybe there's a light source in front of the vehicle     
1:00:39     
or to the left or to the right of the vehicle and that mediates how the vehicle Moves In Space so there's     
1:00:46     
embodiment is an essential aspect the second aspect is that you have this     
1:00:51     
connection machine inside or this connectivity so so you know he focuses a     
1:00:57     
lot in the book on these cross connections where you have a sensor on the left side and it affects and     
1:01:03     
effector on the right side and sometimes those uh connections have cross talk so     
1:01:09     
the effects of like the left sensor might affect the left wheel somewhat but it usually maps to the right wheel so     
1:01:16     
you have these mappings this cross talk and you can have these simple wiring diagrams within the agent but they can     
1:01:23     
have like some sort of uh maybe an emergent effect on the output     
1:01:29     
Behavior the third thing he talked about was like he tried to map the behaviors of these vehicles to emotional states     
1:01:37     
and that was maybe a little bit controversial but the idea that you know you can look at like vehicles moving     
1:01:43     
around in a circle very fast and say that's like an affinity or like love     
1:01:48     
it's you know it's kind of like almost pseudoscientific in a way but like basically kind trying to map these if     
1:01:56     
you were doing like ethology and you were looking at insects you know you might try to interpret like what ants     
1:02:03     
are doing or what these are doing and and kind of give it a that behavior a name that's you know um kind     
1:02:11     
of you know something that's anthropomorphic so that that's what we're doing it with vehicles so those     
1:02:18     
are the three things that brenberg came up with but what they're interested in is you know this connection these     
1:02:24     
connections inside and then if you constrain the vehicles on say some sort     
1:02:30     
of uh topology so if you constrain the vehicle to making like circles or if you     
1:02:36     
constrain the vehicle in different ways you could actually constrain it I guess morphologically by like being very     
1:02:43     
explicit about where you put the the affectors the wheels the sensors the these little antenna on this vehicle you     
1:02:50     
can then you know uh get some behaviors that look like they're intelligent but they're really just artifacts or     
1:02:57     
products of the interaction between this connection these connections or this mapping and the the topology that this     
1:03:05     
vehicle is behaving on so if you have this troid structure here on the surface     
1:03:11     
of the book that vehicle would follow the toid structure and it would you know or you would have another vehicle that's     
1:03:17     
kind of locked to the behavior of another vehicle and they're both kind of     
1:03:23     
moving around this teral structure it'll generate complex looking behaviors but     
1:03:29     
it's largely an artifact of the geometry and you know that's maybe     
1:03:34     
something that even humans exhibit we might actually do a lot of things that are artifacts of our own geometry we     
1:03:41     
don't think about it that way but anyways that's what they're getting at in this book they lay out a bunch of stuff on     
1:03:47     
dynamical systems in here so this is actually also a very good primer on how     
1:03:52     
to talk about a couple dynamical systems cognitive science anyways I really     
1:03:58     
thought it was a good book I was like looking forward to reading it and then I got contacted by artificial life journal     
1:04:04     
and they wanted me to write a a book review of it so I did and this is the     
1:04:12     
result so I you know it's thinkk you it's three pages so you know I think it     
1:04:18     
goes through a lot of good stuff um kind of talking about sort of the book laying     
1:04:24     
it out they're interested in what they call minimal embodiment so this is where     
1:04:30     
we have this these pairwise vehicle interactions we have this topology     
1:04:36     
they're acting on and there's this minimal embodiment aspect in other words if you have an agent can you take and     
1:04:42     
you embody it but can you strip the embodiment down to a minimal sort of     
1:04:47     
effect so we can actually look at it in terms of what are the effects of having a brain in a body instead of in effect     
1:04:55     
at so this is kind of where they're going with this and yeah there's a lot of stuff on dynamical systems and     
1:05:03     
cognition and then there's there are a lot of connections to both classical     
1:05:08     
themes in artificial life as well as classical themes in cognitive     
1:05:13     
science so um this this is a point that I made here a point for further study     
1:05:20     
involves determining the best approach for studying cognitive phenomena so there's traditional been this rivalry     
1:05:26     
between dynamical systems connectionist models symbolic representations and     
1:05:32     
hybrid approaches so we've had dynamical systems you know uh going back many     
1:05:39     
decades where people have said you know we need to look at cognition is this dynamical system something that unfolds     
1:05:46     
in a phase space we have these stable uh States uh and you know that's that's the     
1:05:51     
way to analyze cognition other people have had advocated that we use connectionist models to produce     
1:05:58     
generative behaviors and then that's just something that is somehow you know     
1:06:04     
exhibits intelligence there also you know a lot of people think we need to focus on     
1:06:09     
symbolism and symbolic representations having these you know ranging from lookup tables of inputs to     
1:06:17     
symbols to behaviors or just kind of like the emergence of symbols uh from uh     
1:06:25     
non symbols or whatever and then of course hybrid approaches which combine these and so this was covered in a     
1:06:31     
review by Randy beer in the year 200 so this is something that's you know been this is a dynamical purchase of     
1:06:38     
cognitive science that was in Trends in cognitive science this kind of lays the the groundwork for a lot of these kind     
1:06:45     
of interpreting a lot of what's going on in cognitive science so that was a good     
1:06:50     
uh reference to kind of bring to the four here and in this book um I think     
1:06:55     
they really kind of advocate for a hybrid approach and that's something I think most people would say is is you     
1:07:03     
know you need to have maybe these dynamical representations over time of continuous Behavior but also you     
1:07:11     
know models of nervous systems that are connectionist we can't necessarily specify every component in every     
1:07:18     
interaction we just need to let these things emerge and we also need to have some     
1:07:23     
symbolic aspect the behaviors so yeah I think they yeah they really do in this     
1:07:29     
book they talk about all these different approaches and how you can model this using brenberg Vehicles so this is     
1:07:36     
really I mean you know brenberg vehicles are an Al sort of an antidote almost to     
1:07:41     
deep learning techniques Because deep learning techniques um you know are you know     
1:07:47     
everyone says well they're they're conscious or they're sentient but you know they're not embodied and moreover     
1:07:54     
uh you know we don't really you know we think of deep learning as sort of an analogy of the brain but we don't think     
1:08:01     
well maybe it's not a very good analogy so what else do we have out there that we can use to kind of compare and     
1:08:08     
contrast to see you know and and I and I'm not saying the brain Bo vehicles are     
1:08:13     
exhibiting the kinds of uh I don't know uncanny valley     
1:08:18     
behaviors that deep learning approaches have approached or large language models     
1:08:24     
but you know you can think about brenberg Vehicles as maybe being a little bit closer to     
1:08:31     
cognition and then you know maybe if we spend a lot of time and a lot of money     
1:08:37     
on brenberg vehicles we could maybe come up with some things that are alternatives to deep learning models     
1:08:45     
that people you know I don't want people to say that brenberg vehicles are exhibiting sentients but you could see     
1:08:51     
from renberg's work that he kind of was going in that direction maybe     
1:08:56     
erroneously but I think that's you know that's something that you know it's it's     
1:09:03     
kind of shoved down in the current hype we don't have these models that are     
1:09:09     
alternatives to deep     
1:09:14     
learning okay uh do you have any questions or comments about that yeah it reminds me of like a super     
1:09:22     
sophisticated version of Conway's Game of Life yeah     
1:09:28     
yeah you also forgive me um I I'm     
1:09:33     
still um having a little bit of difficulty drawing the um the like the     
1:09:43     
the differences between deep learning and this because couldn't the one of these vehicles be like     
1:09:49     
conceptualized in a deep Learning System whether you know had some sort of     
1:09:55     
state-based thing that you were mentioning earlier but and it had all like the the embodiment of of what you     
1:10:03     
were describing couldn't you like create some sort of agent or something that would basically replicate this type of     
1:10:09     
vehicle uh yeah I mean yeah so you could have that you could have a vehicle where you had uh a deep learning model inside     
1:10:18     
a very simple model uh but there are a couple things that differentiate like brenberg vehicles from that for one     
1:10:25     
thing deep learning models are not embodied in the sense that you you know     
1:10:30     
when you when you put things in a deep learning model there these hidden layers that kind of kind of sort through the     
1:10:36     
data and they don't I mean they can you can attach labels that say this is from     
1:10:41     
this location this is from this location but there's no inherent spatiality in the de now people to be fair have worked     
1:10:49     
on like you know modular models where you have like you know different parts     
1:10:54     
that kind of streams that kind of go to different places but you know that that's not     
1:11:01     
typically the way deep learning models work they kind of take in data they have labels you have to tell it what the     
1:11:06     
label is and then it'll give you categories of things behaviors and you     
1:11:11     
could do that I guess dynamically um but the thing about brenberg Vehicles is you can     
1:11:17     
theoretically use like it can just explore its environment and you're getting information and it's mapping     
1:11:24     
from like this what it's encountering to Its Behavior so it's kind of like this um I     
1:11:32     
guess input output machine more more explicitly than a deep learning model and you know the thing about that is of     
1:11:38     
course the very simple example is the cross talk where you go from left sensor     
1:11:44     
to right affector vice versa there might be some cross talk in there if you add     
1:11:49     
in nodes within the vehicle we've done this in some of our work um you can     
1:11:54     
actually get get you know it's not deep learning in the sense that you have hidden layers it's almost like in the     
1:12:02     
seans connectone sense where you have inner neurons where you have like     
1:12:07     
something coming in the affector you have this inter neuron that's sort of     
1:12:12     
processing information you might have a bunch of inputs coming into an inter neuron it might then have a number of     
1:12:21     
outputs to affectors or you might have a direct M from a a sensor to an affector so you     
1:12:28     
can actually you know have connectomes that are or you know     
1:12:34     
connection uh connections within a vehicle that are highly explicitly     
1:12:40     
spatial and that helps it behave in a spatial environment where you have like chemical gradients that you want to     
1:12:46     
follow or you have light gradients you wanted to follow or even just like f finding like a path through a maze where     
1:12:55     
has to make decisions about you know where where which which path should     
1:13:01     
I take and you know I mean you can do those things with deep learning but it's a different Paradigm and it's it's similar it's sort     
1:13:09     
of born out of the same connectionist ideas of cognitive science and and you     
1:13:15     
know but they're they're going to be I think practically quite different you     
1:13:20     
know are there differences in like the active learning like online learning um     
1:13:27     
capability is there implications yeah I guess the the promise there would be that brenberg Vehicles would be better     
1:13:32     
at Active Learning where you know uh deep learning model you would because a lot of deep learning models of course if     
1:13:40     
you train them well they can do they're you know they can generalize but typically you have to train it on these     
1:13:46     
out of distribution examples so if you have uh you know if it encounters     
1:13:52     
something that's very common in the environment fine if it encounters something that's very rare or you know uh unusual in the     
1:14:01     
environment then it can collapse or fall down and you know it has to really have     
1:14:07     
that experience built into the model the braber vehicle you can do Active Learning so it doesn't you know you just     
1:14:14     
kind of deal with it as you encounter but again this is something that no one's really explored so I don't     
1:14:20     
know if it would actually be better or worse at this um     
1:14:27     
it's fascinating I've never heard of it I appreciate you talking us about it reviewing the book oh no problem yeah     
1:14:33     
it's great I think it's food for thought because it's like you know this is all     
1:14:38     
kind of stuff that uh you know it's it's like stuff we're we've been interested in for a while but     
1:14:44     
it's kind of like we like we've done a lot of the stuff with developmental brain Vehicles which fits into this     
1:14:51     
what's what's next there what what can we think about like how would we you know how do we want to test these kind     
1:14:58     
of agents and that's that's maybe what you're asking is how do you put those in an environment maybe compare it with     
1:15:04     
deep learning and active learning and things like that I mean that's certainly one of     
1:15:10     
the the big um one of the big issues right is that     
1:15:17     
like especially with with punitive cognitive architectures     
1:15:24     
it's like like there are many architectures that can replicate Behavior or you know that     
1:15:30     
that you different architectures could give you the same behavior right right     
1:15:36     
right so that that's that's that's one you know that's one thing     
1:15:43     
um like uh yeah so how much of you know experimental psychology and and     
1:15:49     
cognitive science is trying to design experiments or trying to collect measurements that will allow you to to     
1:15:58     
distinguish those different architectures right yeah but certainly     
1:16:03     
another another big part of that or certain why why we're so interested in development is that um that again to to     
1:16:13     
steal from Bea um you know like like developmental systems can can learn very     
1:16:22     
quickly you know with with few observations like there's like a there's a real     
1:16:28     
efficiency in developing developing systems that we see or you know like     
1:16:34     
like I'm just thinking about like like a lot of like um Josh T bombs kind of work yeah you     
1:16:41     
know like language and and other kind of developing systems like you can     
1:16:49     
definitely do you know I mean if anything I think some of the reinforcement learning came in because     
1:16:56     
of it you know deep reinforcement learning came in because of its     
1:17:01     
efficiency um but I still like like there's still a     
1:17:07     
certain dissatisfaction with     
1:17:12     
its um yeah just a certain still remaining     
1:17:20     
dissatisfaction and and I think still you know yeah by iCal evidence or or you     
1:17:26     
know use of innate um biases that that allow for you know     
1:17:35     
rapid rapid learning or rapid adaptation or continual learning you know just a     
1:17:42     
bunch of things that that suggest like like there's there's     
1:17:47     
something there we need something else right but I I think you're totally right     
1:17:53     
J in terms of that you know like like yeah you know this is just m you     
1:18:00     
know this is like multi-age learning yeah right like like you like Conway     
1:18:06     
game game of life is just you know you can think of it as as yeah a     
1:18:14     
bunch watching a bunch of Agents I mean there's there's a certain     
1:18:20     
you know total bottom up with Conway or like like not not     
1:18:25     
there's a certain like super abstraction with with Game of Life yeah uh I     
1:18:33     
funniest do we already talk about this Sean Carroll interviewing     
1:18:40     
um uh I'm not gonna get his name right     
1:18:46     
um uh like like I'm guessing Spanish     
1:18:51     
or Brazilian name uh so he's the he's the guy who did um he did a re     
1:19:00     
reimplementation if you will of game of life but and this is the funniest thing     
1:19:06     
being Sean Carol's podcast but he he did it in the programming language brain what he did so you know there's     
1:19:14     
this programming language called brain there is okay that was the thing that was and it's got a long history I     
1:19:21     
mean like the way I know it is that yeah yeah I know this is really     
1:19:27     
funny right so so the way I know it is that that it was designed to be a     
1:19:35     
programming language that um that just messed with your heads like like it it     
1:19:40     
was to make everything more complicated it was like how do I make a language you     
1:19:46     
know how do I make a high level language that's more like assembly     
1:19:52     
okay and and what he points out is that like like     
1:19:58     
in fact this is this is it is like that in the sense that like it's only got     
1:20:03     
seven operations so from a theoretical computer science perspective it's got some interesting properties and he's     
1:20:09     
using that and you remember this paper he's a Google Deep Mind guy     
1:20:16     
um he uh I think maybe this paper came out     
1:20:21     
like last year maybe um where he showed like like it was kind of this     
1:20:29     
random programs like I'm just gonna flip bits on strings and and then try and run     
1:20:36     
them and and eventually these programs develop the ability to     
1:20:43     
replicate yeah yeah like you remember this paper yeah I think that's Sebastian Reese's     
1:20:51     
worker maybe yeah something similar yeah yeah I I'll find I'll find it I'll find     
1:20:57     
it but the other thing that was funny was that Sean Carol had to start the the     
1:21:03     
podcast going like I I'm going to use some some language right now that I just     
1:21:10     
want to prepare everybody for but this is this is actually and then the guy the guy who     
1:21:18     
work it was said that U he had to check with the the MIT University press     
1:21:24     
whether it was POS like like he's writing written a book about it they censored it yeah he's like am I am I     
1:21:32     
allowed to publish this in MIT I just thought that was I thought     
1:21:39     
that was a humorous you know I didn't expect to start my morning with Sean Carol     
1:21:45     
swearing yeah that was that was that was fun but but oh yeah please Trev yeah I     
1:21:53     
was trying to do a thumbs up sorry I'm like like an old man over here     
1:21:59     
but but yeah it was it was pretty funny anyway the um uh but it was still very     
1:22:06     
Game of Life right like like he's not trying to you know uh I mean well     
1:22:12     
certainly replication that was really interesting and if if we you if we were     
1:22:17     
kind of viewing that we would be like oh these programs are starting to gain some sort of desire to to keep going or     
1:22:25     
something like that yeah but it's much more interesting when you're seeing like like the the neural     
1:22:31     
MMO there's a neural MMO guy live coding every     
1:22:37     
day like like yeah he's just he's putting in the hours um but you can you     
1:22:44     
know really nice you know massive     
1:22:50     
multiplayer uh game where you know it would be very common for you to be     
1:22:55     
watching the agents and and making you know making assumptions about the the     
1:23:01     
the agents goals or Desires in terms of how they're how they're either     
1:23:08     
cooperating or how they're interacting right yeah uh um and and just how many     
1:23:15     
different how many different architectures can drive that you know and how many different ways in which you     
1:23:23     
can um how many different metrics by which you can you can     
1:23:31     
potentially um um you know judge the architectures     
1:23:37     
right so in terms of in terms of you know how compute     
1:23:44     
training yeah Cycles right or yeah other     
1:23:49     
measures of efficiency measures of Simplicity um um measures of     
1:23:56     
generalization you know like you said like now now put them into you know uh     
1:24:03     
situations they didn't didn't U get trained with um or you know other other     
1:24:09     
kinds of things yeah yeah this also brings up the analogy to animal brains     
1:24:15     
and so you know like one of the things you find from animal brains or like     
1:24:20     
things like uh Numa actually is artificial version of sort of these     
1:24:26     
cortical columns that mammals have and so you know you have these structures     
1:24:31     
and this is known from like you know uh comparative Anatomy computational     
1:24:37     
Neuroscience that you know some architectures like C uh neocortex or     
1:24:43     
cortical columns are more general purpose architectures that is you can find vertical columns doing interesting     
1:24:51     
things and a wide range of uh mammals you have an expanded neocortex and     
1:24:57     
mammals to different extents and that has to do with this general purpose computation so you can take a cortical     
1:25:04     
column and Numa has actually modeled this in silico and you can solve a     
1:25:09     
number of problems with it it's just the architecture enables this sort of basic processing where you have some sensory     
1:25:16     
input coming up in through the columns and then there you know inputs and outputs that sort of refine that that s     
1:25:24     
sensory input and then of course if you put them in uh parallel that's where the power comes in and so you have this     
1:25:30     
general purpose column it's done in parallel and it can solve a lot of different types of     
1:25:36     
problems you can also see this in insects where they don't have a neocortex they don't have cortical     
1:25:43     
columns but they do have as or mushroom bodies that do a lot of the same things as neocortex and so you could use a     
1:25:50     
mushroom body connector to perhaps do a lot of the same things and no one's done     
1:25:55     
this with in in silico but that's you know you have this convergent evolution     
1:26:01     
where basically insects don't have neocortex they don't have the the stuff     
1:26:06     
they don't have the three low brains like um vertebrates but what they do have are these mushroom bodies that have     
1:26:13     
evolved to do things like sens integration and other types of cognition     
1:26:18     
and so that's well known as well now that's those are two very different architectures and even with mammals your     
1:26:25     
cortical columns are very different in terms because you know in um it's six     
1:26:31     
layer cortex but you know in different species you have different amounts of it     
1:26:36     
and so forth and the and sometimes you get these uh ge ey because it's     
1:26:42     
basically a sheet that expands and so when it expands to a certain size you get these folds and gear ey that allow     
1:26:49     
it to have this complex topological structure so there's all that so you can     
1:26:55     
have this sort of general purpose computation but if you contrast that     
1:27:00     
with some of the uh more specific areas of the frame where we've built models of     
1:27:06     
this um you have areas that are maybe more specific to certain types of     
1:27:12     
cognition so in hippocampus which we talked about last time you have these uh     
1:27:18     
Fields these receptive Fields these areas where spatial cogn is done so     
1:27:25     
there's this very specific type of processing in ca1 and ca3 in hippocampus     
1:27:31     
in mammals where you have this these spatial representations and people have     
1:27:36     
talked about play cells red cells all these other types of cell types where you're representing space you're able to     
1:27:43     
do you know very complex uh uh you know spatial cognition and that's of course     
1:27:50     
you know what we were talking about with brenberg vehicles but with Vehicles don't have a lot of those     
1:27:57     
complexities it could you could build that in but um suffice it to say you     
1:28:03     
can't do anything you can do some memory with hippoc cample Fields but you know doing     
1:28:09     
something like uh procedural learning I don't you know I don't know I don't     
1:28:15     
think that's really kind of you couldn't if you did if you built a model of hippocampus in Silo you might not be     
1:28:21     
able to do that although we had that P paper last time that suggested that hippocampus or spatial memory in general     
1:28:28     
is actually sequential information that is like kind of large language model in     
1:28:34     
nature which is just an interesting Theory out don't the other area that's     
1:28:40     
very specific is the uh cerebellum so the cerebellum has like the structure     
1:28:46     
it's highly sort of specialized for timing and so you have movement timing     
1:28:53     
you hit involved in langu linguistic timing all this other stuff it's basically a series of cells and     
1:28:59     
connections that act as a comparator so this is very commonly uh cited in     
1:29:05     
computational Neuroscience where you want to build a comparator and not every     
1:29:11     
you know in mammals you have a cerebellum but you have this in insects too where they have timing they have to     
1:29:18     
operate on timing information they don't have a cerebellum but you know they can still do that sort of so you have these     
1:29:25     
architectures that are very specific architectures that are very general but then you Al also have almost like a     
1:29:33     
domain Independence in other words you can have something that's uh you know     
1:29:38     
undergone this sort of parallel Evolution you can have these structures that are do similar things but don't     
1:29:45     
look anything good and so I mean I just wanted to make     
1:29:51     
that point because I think it's important to think about     
1:29:56     
I did have a question what you were saying a couple of questions so with the     
1:30:01     
whole musroom neuron like um uh you talk     
1:30:06     
about like convergent evolution but is there any evidence that like these alternative um neuronal types in other     
1:30:14     
species like share the same scalability properties um as you'd see in in like     
1:30:21     
humans um I don't know I I don't know about like I don't know if there are any studies that look across mushroom bodies     
1:30:29     
um part of that problem is of course we think of C like cortical neocortical     
1:30:34     
scaling as like we always like tie it to Greater intelligence um so like you know in in     
1:30:41     
uh in primates for example you know you have proi which have a very small     
1:30:47     
neocortex and then as you get into monkeys and then great apes you get bigger and then in homo it just explodes     
1:30:54     
in terms of size so you have this you know um you can make these comparisons     
1:31:00     
in insects it's it's quite a bit different and I don't know if anyone's I'm sure there's probably a paper     
1:31:05     
thinking about this where they think about the scalability of mushroom bodies I know that like in some insects that     
1:31:11     
don't do much like dung beetles they don't have much of a mushroom body or     
1:31:17     
you know where they don't interact with their environment as much as sell like bees or ants and that so you know you     
1:31:23     
have us I don't know what the the details of that are but I mean basically what I mean by convergent evolution is     
1:31:29     
that you if you have a problem you need to solve which is doing things like     
1:31:35     
multisensory integration memory learning you would evolve like you don't evolve     
1:31:41     
the same structure you evolve a different structure and it may not be like scalable in the same way like you     
1:31:48     
don't see this huge explosion in like the size of the mushroom body is that that mean it's more     
1:31:54     
efficient I don't know but no I appreciate it     
1:32:01     
thanks thing you know I'm so ignorant about um modeling in Neuroscience I was     
1:32:06     
just curious I I don't even know if I'm I'm a little hesitant to even bring this up because I I'm such a novice and don't     
1:32:12     
know the language but I've um there's these like ways of um modeling systems     
1:32:20     
as Springs and then when you optimize it it's it's like the it's a little bit of     
1:32:25     
the role of the dice typ thing you don't always get the same answer and so are     
1:32:30     
there is that very common um in these Neuroscience models to have something     
1:32:36     
like this yeah I just just a curiosity of what you were talking     
1:32:41     
about uh did you want to say something about that excuse me yeah I've certainly seen     
1:32:50     
uh I've seen that there's model equivalence right so     
1:32:55     
so they um um if you look at coupled     
1:33:01     
yeah coupled spring systems um can be can be substituted for     
1:33:09     
for you know a large class of of other models um of a more conventional     
1:33:18     
um U I mean are you talking about like kind of     
1:33:25     
additional ways of seeing like cable equations alternative     
1:33:33     
yeah that's a step above me yeah I don't even know what cable equations     
1:33:38     
mean terms of like computational Neuroscience Ms     
1:33:44     
oh I mean use the word that I was thinking of it and I couldn't remember the phrase the couple of oscillators     
1:33:52     
yeah yeah like like those those have a yeah those those can those can     
1:33:59     
represent a a whole yeah large class of of     
1:34:06     
models that might have a different you know physical     
1:34:12     
interpretation so are those like are those common to use like in the literature is there packages yeah yeah     
1:34:21     
well so I'm gonna I can only really speak about Neuro Imaging but like like     
1:34:28     
yes those are the um I think those are now widely used in Neuro     
1:34:37     
Imaging with a particular class of models called Dynamic caal models     
1:34:45     
um the um the the the requirement in those particular     
1:34:52     
models um and these are implemented in kind of one of the most popular software     
1:34:58     
packages that that one of the toolboxes that's you know been used since the beginning of Nur Imaging going back to     
1:35:05     
the pet days um but uh you have to specify how     
1:35:11     
many nodes in the brain you're going to model and then so th those nodes then     
1:35:18     
have a have and then you set up the connectivity of that not     
1:35:24     
and then and then you can basically have a set a couple differential equations     
1:35:29     
that that model the system and you do model comparison     
1:35:35     
between models where you change some of the connectivity and and then you do um you     
1:35:43     
look at model evidence across those models to to you know give you kind of     
1:35:50     
Base factors that then say like okay this particular model that you know has     
1:35:58     
inhibitory connections or doesn't have inhibitory self connections or something like that like like of the three to five     
1:36:07     
models that I've looked at um this one has the the most model     
1:36:14     
evidence and and yeah that that would be an example I I think of of you know     
1:36:20     
these models being applied in their iming that if that El that's great thank you sorry for the     
1:36:26     
deviation I was just I mean it's a it's it's a cool class that you know only started     
1:36:33     
in I mean I think like the first Theory paper was like 2006 but I don't think it really kind of took off in terms of     
1:36:40     
actually getting applied outside of the lab it started until like you know 2013     
1:36:46     
2015 kind of you may be aware of it but um you     
1:36:54     
know Von noyman he had um uh as the     
1:36:59     
successor to the Von noyman architecture he was playing around with these couple of oscillators and it like I think like     
1:37:05     
right before he died it was like his last thing that threw out there     
1:37:10     
so is it's a Computing thing um yeah I guess as an alternative     
1:37:17     
um for um to V architecture because he I think he saw a lot of limitations with     
1:37:22     
it so solve wider repertoire of     
1:37:31     
problems     
1:37:39     
yeah okay and that's kind of like you know this biologically inspired aspect     
1:37:45     
right so like oscillators of course are the things that we think of when we think of modeling neural excitation use     
1:37:54     
like possibly throw an oscillator Model A couple oscillators to you know and     
1:37:59     
then of course that that would be you know of course if you want to build a computational architecture you can't     
1:38:04     
just throw like a neurom model at it you have to I mean as a uh Quantum Computing     
1:38:11     
demonstrates it's not just as simple as reproducing the Paradigm you have to really kind of work on the how to     
1:38:19     
compute something with it how to solve a set of benchmarks and then you know kind     
1:38:24     
of up that performance somehow so yeah it's why the Von noyman architecture has     
1:38:30     
not really been replaced as of yet well I was thinking about that you     
1:38:36     
know these um karf Arnold networks in terms of just     
1:38:43     
you know it's it's one thing to have a computational model that     
1:38:51     
can you know can reprodu educe the the the phenomena you know that the     
1:38:57     
importance of simulation but also the importance of interpretability what what am I trying     
1:39:02     
to say not efficiency but Simplicity or and basically the big problem of of     
1:39:09     
estimating you know model dimensionality so I think that's good let's go move on we were talking about     
1:39:16     
like we get a deep dive in hippocampus and all that and I had some readings     
1:39:22     
that kind of followed up on that and one of the things we talked about in that discussion was successor     
1:39:28     
representations so I'm going to uh present a couple of papers that kind of follow up from that discussion two weeks     
1:39:35     
ago um talking about representations uh different reference     
1:39:41     
frames in this platonic representation hypothesis so this is uh you know we're     
1:39:47     
talking about biologically inspired Computing and how we want it you know     
1:39:52     
sort of take inspiration from biology but of course Jesse said maybe a better word is organic Computing or organically     
1:40:00     
inspired Computing now part of that of course is not just the architecture in     
1:40:06     
terms of neurons and synapses and dendroid but also these representations     
1:40:11     
that may or may not be a thing in the brain so let's let's start with this     
1:40:17     
paper successor representations this is a paper from Sam gersman     
1:40:23     
who is a neuroscientist from Harvard this is from the journal on     
1:40:30     
Neuroscience the successor representation it's computational logic and neural     
1:40:35     
substrates so you know again when we do this we have to think about computation     
1:40:41     
if it's plausible but also if you know not just that it's naps to a neural substrate that we've seen in nature but     
1:40:48     
whether it's also has it's plausible in terms of the computation right so the abstract reads     
1:40:56     
reinforcement learning is the process by which an agent learns to prodict long-term future reward so this is the     
1:41:04     
the sort of the Crux of reinforcement learning you have an agent that learns     
1:41:09     
like different policies lens of rewards associated with those policies and then is can kind of figure out the reward     
1:41:16     
structure and then figure out the best policy some of that of course is this long-term aspect and you know if you     
1:41:24     
think about like in uh machine learning we know we kind of think or in deep     
1:41:29     
learning we kind of think about a memory so we get okay uh to learn something you need to     
1:41:35     
have like data you need to have training data but you also need to have some sort of pattern matching and then some sort     
1:41:42     
of memory and so in reinforcement learning you're really doing pattern     
1:41:48     
matching with in terms of the uh policies but then you also have this memory this long-term Outlook so that's     
1:41:55     
really the key is to figure out like if you see if you can predict how this     
1:42:01     
reward will Faire over time that's really the thing we want we don't want just like kind of these immediate     
1:42:08     
rewards and agent shifts back and forth between policies that's not really useful I mean there's a     
1:42:15     
biological area you know reinforcement learning started in biological psychology so people are understanding     
1:42:22     
things like dopamine in terms of reinforcement learning but uh you know we also have computational models so     
1:42:29     
just so that you know we know that like this isn't just something that we've made up in a computer that there's this     
1:42:35     
it maps to the biology of the brain uh we Now understand a great deal     
1:42:41     
about the brain's reinforcement learning algorithms but we know considerably less about the representation of states and     
1:42:49     
actions over which these algorithms operate so if we go and think about a     
1:42:54     
reinforcement learning model you know we're looking at these set of policies     
1:42:59     
or these set of actions and we think about the reward associated with them so     
1:43:04     
it's like if you have like you know if you had a bunch of food sources if you were an animal like a rodent and you had     
1:43:11     
a bunch of food sources and some of them were poisoned and some of them had High Core content some of them less High cor     
1:43:18     
content the idea would be learn those basic properties in make the decision to     
1:43:25     
exploit those based on what was available and you know that would be learning     
1:43:31     
reinforcement uh at the neurochemical level of course there's dopamine there's also other aspects people use to model     
1:43:38     
uh how that process gets sort of encoded now you know you have so you have memory     
1:43:44     
but you also have these representational states and actions so again you know people have     
1:43:51     
very uh you know intense arguments about representation in the brain but for the     
1:43:57     
purposes of this it's you know representing those States and actions how do you represent that information as     
1:44:03     
a whole as a as a model in the brain and not just like a set of things that you     
1:44:08     
just act on in a shifting manner a useful starting point is asking     
1:44:14     
what kinds of representations we would want the brain to have so not just like what the brain actually has but like     
1:44:20     
what do you think is most posative you know what do you think is like a     
1:44:25     
sort of a a way forward you know and then maybe we can see what uh the brain     
1:44:31     
actually has so given the constraints of a computational architecture we look at the brain we say what is possible what     
1:44:38     
is plausible and then what kinds of representations maybe make sense and     
1:44:44     
then test those um on on you know what we have in terms of an     
1:44:50     
architecture following this logic leads to the idea of successor representation so this is uh where we have this     
1:44:59     
specific type of representation the specific representation encodes states of the     
1:45:04     
environment in terms of their predictive relationship with other states so it's     
1:45:10     
like you know we have these policies or these uh states of you know and then we     
1:45:16     
want to be able to have this predictive aspect so we want to have states that     
1:45:22     
predict other states or have some relation to other states that is predicted um so a little bit of sort of     
1:45:30     
predictive processing issue going on here thinking about like how you know     
1:45:36     
our cognition is really about prediction and that processing is about you know     
1:45:42     
predicting the next State uh recent behavioral and neural Studies have provided evidence for the     
1:45:49     
successor representation and computational studies have explored ways to extend the original idea so this is     
1:45:56     
something that you know we've been able to kind of get a sense of with behavioral and neural studies uh this     
1:46:02     
paper reviews progress on these fronts organizing them within a broader framework of understanding how the brand     
1:46:08     
negotiates tradeoffs tradeoffs between efficiency and flexibility for     
1:46:15     
reinforcement so what they mean is that or what he means is that the brain is basically doing this trade-off between     
1:46:22     
efficiency and flexibility so like you know you need to conserve energy in the brain you need to conserve cognitive     
1:46:28     
resources perhaps but you also need to be flexible in terms of your predictions so you need to make predictions that     
1:46:35     
allow you to sort of maybe maximize your energy with respect to food sources but you also need to explore different food     
1:46:42     
sources to make sure that you know like if you're like a rodent and you're     
1:46:47     
exploring different food sources and you find that one food source that's really rich in nutrients and you just stick     
1:46:55     
with that um that's fine until that resource runs out then you don't know     
1:47:01     
what to do other than that you might have like a set of things that you might explore you know things with a little     
1:47:07     
bit less nutrient content but think about that process that you know you're exploring things you don't have things     
1:47:14     
like kind of arranged in front of you from like best to worst you have to go     
1:47:19     
out in the environment and explore the environment and evaluate each food source and say this has high nutritional     
1:47:25     
content this says less so this is poison if you don't explore if you're not     
1:47:30     
flexible with respect to what you explore then you can't really get a full map of that space if you're highly     
1:47:38     
efficient in finding the most you know nutritious food stuff that's great you can probably find it but if the     
1:47:46     
environment changes then you're uh screwed basically and flexibility allows     
1:47:51     
you to do that but too much Flex F ability then you know you might end up eating some poison for dying so that's     
1:47:58     
not good either so there's this trade-off between efficiency and flexibility and reinforcement learning     
1:48:04     
and talks about this in the paper here uh kind of this idea of     
1:48:09     
reinforcement learning mean the problem of predicting and maximizing future reward it's a hard problem because the     
1:48:17     
number of possible Futures is enormous too big to search through exhaustively so you you can't consider all career     
1:48:24     
paths as a prospective student you can pick some that you're familiar with you can pick some that you see in front of     
1:48:30     
you but not every possible option now if you did go through every possible option     
1:48:36     
it may be good but it might not be plausible it might take too long it's just like an algorithm trying to find an     
1:48:43     
optim solution you can't go through every option you can go through some good options but you don't know if     
1:48:50     
that's the best option so it's a problem and this is this trade-off in     
1:48:55     
practice um you know so yet another another approach is to again imagine the     
1:49:01     
goal state but instead of planning a path to the goal only consider how often the goal is achieved from a particular     
1:49:07     
starting point so if you start from a certain point what are your options in front of you and this makes this problem     
1:49:14     
a little bit more tractable makes this trade-off less sharp or less     
1:49:20     
severe so one of the problems of or one of the successes of reinforcement     
1:49:25     
learning or in the algorithms not just in the brain and is crucially on the representation of the environment so if     
1:49:33     
we have good representations of our environment we can do reinforcement learning a lot better and this is     
1:49:39     
something again the successor representation idea kind of focuses on     
1:49:44     
so a very flexible representation such as knowing how often each state transitions to every other state this is     
1:49:51     
basically knowing parameters of a markof model uh can be highly accurate but it's     
1:49:57     
computationally cumbersome so as you can imagine putting a a a Markov model in a     
1:50:06     
you know in a robot you you know that like you can characterize the Markov model you can hardcode it but what we're     
1:50:13     
doing is we're building a Markov model from sort of uh first principles from     
1:50:18     
empirical observations only so you have the states that you observe sometimes they're hidden states that you don't     
1:50:25     
observe you have these transitions between the states and you have to figure out what the probability is so     
1:50:31     
with like something like flipping a coin that's pretty easy you know kind of intuitively that this is random more or     
1:50:37     
less but of course there are variations in that that we've talked about in a previous meeting the Summer where that's     
1:50:44     
actually not the case so you know there are a lot of variations in the environment that you have to learn you     
1:50:50     
have to have these flexible representations in really get that down and if you think about this in terms of     
1:50:56     
a Markoff model uh this this helps because we know computationally how     
1:51:01     
burdensome a Markov model can be how hard it would be to learn a Markov model from scratch so that's what we're     
1:51:08     
doing so you know this is where reinforcement learning can help different representations clearly     
1:51:15     
have different strengths and weaknesses so computational models can help us understand these tradeoffs in terms of     
1:51:21     
General princip Les and we can ask another question which is what makes a representation     
1:51:28     
useful for reinforcement so in doing reinforcement and trying to learn the     
1:51:33     
parameters of the environment and trying to figure out the best path forward the best way to transition between states     
1:51:41     
how those States may be vary in nature and how to take advantage of that that's     
1:51:46     
the kind of thing we want but we need a representation to know how to navigate that we can't just do that from kind of     
1:51:53     
u a memory or pattern recognition we need a representation something a     
1:51:58     
framework to understand this stuff so this is where you know he kind of talks about these uh types of maybe     
1:52:06     
representations with respect to reinforcement learning so one lesson from these discoveries is that     
1:52:12     
reinforcement learning is not one thing but rather multiple things as set semi     
1:52:17     
dissociable systems that each can solve the reinforcement learning problem independent there's some citations here     
1:52:25     
from the literature these systems make different trade-offs between computational     
1:52:31     
efficiency and flexibility as elaborated in the next section by formalizing his     
1:52:36     
trade-off space we can clarify what makes a good representation for a given computational architecture so this is     
1:52:43     
like what we're talking about with computational architectures sometimes they're very general and you can put a number of     
1:52:50     
representations on them basically them up with different representations and that's fine so like neocortex you can     
1:52:57     
have all sorts of different representations and you know that might work with that architecture with the     
1:53:04     
hippocampus or especially with the cerebellum that may not be the case you might have to have a very specific     
1:53:11     
representation there or that there's that representation and you can't say     
1:53:16     
represent um different types of memory like episodic memory in the cere you can     
1:53:23     
only represent procedural me the cereb that sort of thing and again I'm just saying this as     
1:53:29     
an example I don't we know the details of you know how that might work but I     
1:53:36     
think the point is is that we want to identify good representations for different     
1:53:41     
computational architectures and ultimately representations that can learn from the environment sufficiently     
1:53:48     
to enable optimal Behavior so so this is where you     
1:53:54     
introduces successor representations so this is where we're balancing computational     
1:54:01     
representation uh the basic idea is to build a predictive map so this is very much like predictive processing in that     
1:54:08     
that Spirit of that we're building a predictive map of the environment so we're building like map of the     
1:54:14     
environment environmental States or cognitive States and we're saying how     
1:54:19     
you know how can how often does this occur or or often are these two states related and so we're building this     
1:54:26     
predictive map this representation it summarizes the long range predictive relationships between states we will     
1:54:32     
show how this predictive map when used as the representation for reinforcement learning so they're applying it     
1:54:38     
specifically to this problem is optimal for a particular computational architecture and then in this case it's     
1:54:45     
a linear function approximation so they're not worried about the brain at all they're just testing this on this     
1:54:51     
mathematical function approximation so you know it's basically approximating a     
1:54:56     
linear function linear regression or something like that recent experiments     
1:55:02     
have begun to suggest that Sr May constitute a part of a separate system the reinforcement learning so the     
1:55:08     
successor representation might be one of these separate uh sort of uh subsystems for     
1:55:16     
reinforcement learning with implications for how we understand the functions of the hippocampus and dopamine we talked     
1:55:22     
about that where you have functions in these their architectures like dopamine     
1:55:28     
function or you know in the hippocampus these receptive fields and so forth so     
1:55:33     
we have we have these semi dissociable systems and then we can map that to     
1:55:39     
specific problems of predicting the environment and then we can actually think about like how do those operate in     
1:55:47     
a specific neural um architecture     
1:55:53     
so looks like Trevor had to leave okay that's okay uh we we'll have the video     
1:55:59     
okay so that's the one and it you know it kind of reminds me the semi dissociable systems of the metab brains     
1:56:05     
work that we've been publishing on you know we have these metab brains where you have these different layers of     
1:56:12     
representational layers so you might have like a bottom layer which is very much um you know non there's no sort of     
1:56:20     
representation in it it's just kind of like a connection machine like a connectionist model or what you might     
1:56:26     
find in a uh R bird vehicle very simple     
1:56:31     
then you might have another layer where you have this sort of Markov model running which is where you kind of     
1:56:37     
associate or you're learning from the data from the environment you're associating States we're kind of developing this model of probabilities     
1:56:45     
of States how they're related and what maybe hidden states are and then this     
1:56:50     
final layer where you're doing prediction on that where you have okay now we have this Markoff model we're     
1:56:57     
learning from the environment now if we summarize this over maybe weeks to months to years we can make predictions     
1:57:04     
and encode those predictions as being probable plausible or not     
1:57:10     
plausible so I mean you know we we did a paper on this sort of thing uh for um an     
1:57:16     
artificial life uh Workshop back in 2020 is like     
1:57:22     
basically taking bre vehicles and taking that little you know that that     
1:57:27     
non-representational architecture and adding on layers which are more and more     
1:57:33     
representational and so it's a metab brain so you have these layers stacked within a RG vehicle where you have like     
1:57:39     
this very basic connection connectionism and then you have the um a higher level     
1:57:47     
model of states and of you know probabilities of between transitioning     
1:57:52     
between states and then something predictive so prediction is a different thing it's basically saying it's     
1:57:58     
summarizing all that information saying How likely is this to happen How likely is a queen flip to happen I can model     
1:58:05     
you know uh I can model a Brit vehicle observing Co flips it'll observe them bring it into     
1:58:12     
this Markov model it'll sort of tally the probabilities and you could say it's     
1:58:18     
50/50 but actually we know that that's not always the case that there are certain runs over time that deviate from     
1:58:24     
50/50 and to make those predictions maybe those are like spurious     
1:58:29     
predictions which maybe requires another model to evaluate that evidence to say     
1:58:34     
is a prediction we make spous or is it like something that's real or it can be     
1:58:42     
causal so you know there it can go keep going up it's almost like reverse Turtles all the way down Turtles all the     
1:58:47     
way up but uh anyways uh so that that's successor representations and I just     
1:58:54     
wanted to make that last point because I think it's relevant to our work this     
1:58:59     
second paper is the platonic representation hypothesis so this paper can be summed     
1:59:05     
up in like two sentences here one sentence and this is from the archive so     
1:59:11     
this has probably been submitted to one of the machine learning conferences um so basically neural     
1:59:18     
networks trained with different objectives on different data ities are converging to a shared statistical model     
1:59:25     
of reality in their representation spaces so this is the representation     
1:59:31     
space this is a figure that kind of summarizes the platonic representation     
1:59:37     
hypothesis so and imagine you have this uh set of data that's coming into your     
1:59:43     
model you have X which is images so you have these images that are projected     
1:59:49     
into the model you have the text which is y here so this is the the image this text     
1:59:57     
describes the image so you're linking the text with the image and as a model does you want to     
2:00:05     
take both of those things and use it as the to model the underlying reality Z so     
2:00:11     
that is where you have the image but it's annotated now the program knows     
2:00:16     
that this is a blue cone this is a red sphere and that they're next to one there's approxim     
2:00:23     
so we have this relationship here so we have the F image F text those are two     
2:00:28     
functions and we want to bring those together and map them to a shared reality and so this is where these two     
2:00:36     
things converge that's what they're talking about with this so why do they call it platonic uh so let's read the     
2:00:42     
abstract um so we argue that representations in AI models particularly deep networks are     
2:00:49     
converging first we survey many examp examp of convergence in the literature so you know this is where we     
2:00:56     
have these different representations and AI models that we're using uh different ways to represent data and you know kind     
2:01:03     
of build these outcomes uh but you know these are converging because people are as they     
2:01:11     
use a variety of models they're kind of finding these sort of underlying     
2:01:17     
principles it's almost like complexity Theory where you have the underlying principle and you know we're trying to     
2:01:23     
discover them across many different types of systems first we survey many examples of     
2:01:30     
conversion through literature over time and across multiple domains the ways by     
2:01:35     
which different neural networks represent data are becoming more Al so if we run you know data into a neural     
2:01:41     
network they have all sorts of different types of visual data or text Data they get represented in the same way which     
2:01:47     
makes sense uh it's the same tool it's the same type of model     
2:01:52     
but you know this is something that as we work with them we figure out how those align across     
2:01:58     
models um next we demonstrate convergence across data modalities so as     
2:02:03     
Vision models and language models get larger so as these types of models get larger where you have more input in     
2:02:11     
terms of more data they measure distance between data points in a more and more alike way so the idea is that the more     
2:02:17     
data you add basically um the more sort of information you have and that cuts down     
2:02:26     
on sort of the technical variation between uh data sets so if we use two     
2:02:32     
Benchmark data sets to Imaging you know two image data sets uh maybe like the iris data set and     
2:02:40     
the U the mnus data set we can actually get those representations to become     
2:02:47     
similar with the more data so the more observations we have of the data the more they pick up on sort of the     
2:02:53     
fundamental features of each data set that has share commonalities so the     
2:02:59     
representation is really kind of getting at the more fundamental aspects of the data set instead of just simply     
2:03:06     
describing a feature space very unique to the data and that has implications     
2:03:11     
for like generalizing um a model because you can train it on like you know     
2:03:18     
mnist and the iris data set and actually do something like biological uh Imaging analysis so um I     
2:03:29     
mean people have done that before but it doesn't worked out very well the accuracy is not very good so okay so we     
2:03:36     
hypothesize that this convergence is driving towards a shared statistical model of reality kind the Plato's     
2:03:42     
concept of an ideal reality so this goes to philosophy talking about platonic uh     
2:03:48     
ideals and how you have these like sort of IDE in nature like these ideal models     
2:03:55     
and you know that they're these like I guess platonic types in nature and so     
2:04:02     
that that's what they're getting at um we term such a representation the platonic representation so if we want to     
2:04:09     
represent a red sphere in a blue cone we have to find the thing that describes the ideal representation of a red sphere     
2:04:16     
and a blue cone or the ideal representation of all geometric objects that's basically it     
2:04:22     
we term such a representation the platonic representation and discuss several possible selective pressures     
2:04:28     
towards it finally we discuss the implications of these Trends their limitations and counter examples to our     
2:04:35     
analysis so they have their project page here on GitHub IO and the code here so     
2:04:41     
they're doing this sort of theoretical investigation I guess of this     
2:04:47     
convergence of uh representations um     
2:04:52     
and they uh they Define this thing called representational alignment so they're looking the way they evaluate     
2:04:59     
different representations is through representational alignment which is a measure of the similarity of the simil     
2:05:05     
of the similarity structures induced by two representations so you're looking at a     
2:05:11     
similarity metric over different kernels that in contain these representations so they're interested in     
2:05:18     
the representation of a function which is a mapping uh from the     
2:05:25     
uh that assigns a feature Vector to each input in some data on domain X then we     
2:05:31     
have a kernel which is of course how a representation measures distance similarity so X byx on this space r and     
2:05:41     
we want to look at the similarity between data points so that gives us our kernal representation maps from X to R     
2:05:49     
and then this interaction maps to R the kernel then there's this kernel line metric which is uh this kernel comparing     
2:05:59     
interactions between kernels on this space are which measures the similarity between two kernels how similar is the     
2:06:06     
distance measure induced by one representation to the distance measured induced by another and so the idea would     
2:06:11     
be that they would should be identical or near identical if these representations are convergent and they     
2:06:18     
should be nonidentical or highly nonidentical if these representations diverge and so that would be evidence     
2:06:25     
against the platonic representation whereas if they're very close the aligned then that's evidence for     
2:06:32     
platonic representation um so this kind of goes     
2:06:37     
through actually they talk here about different models with different architectures and objectives can have     
2:06:43     
aligned representation so this is what we're talking about with biologically inspired models you can have different     
2:06:50     
architectures comp computational or anatomical and yet they can do things     
2:06:56     
that are very similar so that maybe implies that they have aligned representations so you can have this     
2:07:01     
sort of convergent evolution of different structures do similar things and maybe what's going on is you have     
2:07:07     
aligned representations that do similar things and why I don't know I don't     
2:07:13     
think anyone knows but I think thinking just starting to think about it like this is is     
2:07:19     
useful okay so you know getting at kind of how they     
2:07:26     
think about this this is the capacity hypothesis if an optimal representation     
2:07:32     
exists in function space larger hypothesis spaces are more likely to cover it so this is where we have this     
2:07:38     
hypothesis space and the hypothesis space as you scale up the     
2:07:44     
architectures they overlap so these are two different representations here hypothesis space and and hypothesis     
2:07:51     
space too basically um you know they're exploring the same space they're the     
2:07:58     
representations are different hypothesis of what you know what the     
2:08:03     
environment is like so it's like with the reinforcement learning model We have     
2:08:08     
basically this model of the environment how closely can we get to     
2:08:14     
you know the true environment well we're only sampling a Subspace of this environment but if we use different     
2:08:20     
representation we see that we explore different parts of the space so they're the Divergent representations but     
2:08:27     
they're exploring the same space now they don't overlap here so we have different models and we still have     
2:08:33     
different interpretations and it's hard to know like which one is correct because we have just different     
2:08:41     
representations but as we said before if you add more data you can improve that     
2:08:46     
uh this Quest towards a platonic representation because you're General izing better and you're doing other     
2:08:52     
things better as well so as you scale up this architecture you end up with a hypothesis space for each representation     
2:09:00     
being you know improved or enlarged and ultimately that results in even if     
2:09:06     
they're exploring different parts of this space uh then the hypothesis     
2:09:12     
Subspace they tend to overlap and so as they grow in size as they get bigger     
2:09:17     
with scaled of architectures they overlap in this space r and you end up     
2:09:23     
in this metric space r and you end up with this region which is the overlap between space one and space to and here     
2:09:31     
is where I guess they you know sort of uh propose that this is part of this     
2:09:37     
platonic architecture so two small models might not cover the optimum which is well     
2:09:44     
which is this star I guess here of this uh Circle uh and then and then thus find     
2:09:50     
different solutions so the solutions are these open stars and you can see that they're     
2:09:57     
Divergent so this hypothesis space is just kind of the hypo the space of     
2:10:02     
different hypothetical Solutions these open stairs are the Optimal Solutions and the in the optimal Global solution     
2:10:09     
or the global Optimum is in the middle of this interior Circle you can see in     
2:10:15     
the the uh fill star here so we don't hit that space we don't hit that point     
2:10:21     
with either of the two smaller models smaller representations but if we scale up the architectures then we find that     
2:10:28     
there's not only overlap between the two hypothesis spaces but that we can find that optimal point because both     
2:10:34     
hypothesis spaces cover that again you know we can think about     
2:10:40     
this in terms of solving tasks our task gradient here this is the multitask scaling hypothesis where the models that     
2:10:48     
are trained with an increasing number of tasks are subject to pressure to learn a representation that can solve all tasks     
2:10:55     
so as the task gradient uh increases here we get this     
2:11:00     
uh you know these different tasks that overlap and we end up with this space that is multitask     
2:11:09     
optimized so I think I'm going to leave that um aside that paper I think that's     
2:11:14     
good paper the final one I want to talk about today is this paper um this is     
2:11:20     
from 2020 and I think we covered this a long time ago one of our meetings it's it's food for thought because it's you     
2:11:27     
know kind of thinking about reference frames not as these computational things     
2:11:32     
but like these things that humans use in terms of understanding space and     
2:11:38     
language and I think we covered actually I don't think we covered this paper it is a paper on um indigenous people in     
2:11:45     
New Guinea and how they think about space when they think about space they don't think about space like like in     
2:11:51     
terms of North Southeast and West often times they talk about something being     
2:11:56     
either uphill or downhill and so it's like kind of an interesting set of uh     
2:12:02     
spatial reference and so you know the idea is like if people conceptualize space differently do they use like a     
2:12:11     
sort of a platonic representation or do they use culturally specific representations that maybe have some of     
2:12:17     
the same features like directionality but then vary quite a bit in terms of     
2:12:23     
the actual thing that the the representation they're using the framework that they're using so that's     
2:12:28     
where this is coming from so this is actually on uh different reference frames and different axis in indigenous     
2:12:35     
amazonians so again this is an indigenous culture where they haven't been exposed to Western culture and so     
2:12:41     
often times if you're doing cultural uh studies you can use crosscultural     
2:12:46     
studies you can use indigenous uh societies as sort of a model for kind of     
2:12:52     
an alternate way of interpreting the world alternate representations so that's why they they     
2:12:59     
focus on indigenous people and you know that's maybe a a false uh assumption     
2:13:06     
because indigenous people of course interact with you know other cultures     
2:13:11     
the Western World all the time so it's not like it's kind of hard to kind of make that sort of a     
2:13:17     
laboratory assumption uh but yeah so this I'll just go through the     
2:13:24     
abstract of this and then we'll wrap up um spatial cognition is Central to human     
2:13:30     
behavior as well as other animals as we've seen you know in in all sorts of mammals insects and horse they use     
2:13:37     
different uh substrates different architectures to use spatial cognition     
2:13:42     
we focused on Hippocampus but you can just as easily as something maybe like a     
2:13:48     
mushroom body or something in an insect so you know this is something that uh     
2:13:54     
but but we're focused on the representations here in humans and so we know that like there     
2:14:00     
are a lot of different types of representations of cultural representations of Concepts     
2:14:07     
very question is is like you know is there like maybe a platonic component     
2:14:12     
and a culturally specific component how culturally specific are these     
2:14:18     
representations so the way people conceptualize very space varies within and across groups for unknown reasons we     
2:14:24     
don't know why cultural uh that that these representations are culturally     
2:14:30     
distinct it may be this sort of trade-off between flexibility and um you know efficiency     
2:14:39     
so if you have like platonic aspects of a representation it makes it efficient     
2:14:46     
you have like some framework but then there's this variation that's introduced because you need to have this     
2:14:53     
flexibility depending on what you're doing your environment so forth so here we found that adults from     
2:14:59     
an indigenous Bolivian group use systematically different reference spatial reference rings on different     
2:15:05     
axes so this is where they're looking at different axes and they're using different spatial reference     
2:15:12     
frames and this according to known differences and their discriminability so uh in both verbal and non-verbal     
2:15:20     
tests participants preferred allocentric which are environment-based space spatial representations so     
2:15:27     
allocentric is outside the body environment based egocentric is with respect to the body so this is where you     
2:15:34     
get this embodiment aspect um participants prefer allocentric space on     
2:15:40     
the left right Axis so looking from left to right so just looking at the environment left to right is outside of     
2:15:47     
the context of a body where spatial discrimination like B versus D are     
2:15:53     
notoriously difficult so you know thinking of things on the axis of left to right is good but then you can't make     
2:16:00     
these kind of spatial discriminations easily but the same participants     
2:16:06     
preferred egocentric or body based space on the front back axis so that's looking     
2:16:11     
forward versus Looking Backward so now you're involving the body and your location in space so it's more of a     
2:16:18     
relative to your body type of representation and in this case spatial discrimination     
2:16:24     
is relatively easy so you know if you're thinking about like how and I'm sure     
2:16:29     
that like people in the west I mean can relate to this um you know if you're     
2:16:35     
thinking about like a number line which of course can vary in different cultures     
2:16:40     
but like just think about the standard number line where you go from left to right where the standard set of     
2:16:47     
political opinions and the Spectrum from left to right those are all kind of like this sort of you know representation and     
2:16:54     
egocentric space maybe there's some aspect of the body in it it's just really depends on how you think of that     
2:17:01     
representation but then this there's a different set of representations from front to back you know thinking about     
2:17:08     
like what's in front of you versus what's in back of you and having a diff having it more related to the body the     
2:17:13     
position of the body so this is this is actually in terms of spatial discrimination this is     
2:17:20     
um there's a difference the results of this paper     
2:17:25     
there are three main takeaways the first is that it establishes a relationship between spontaneous spatial language and     
2:17:33     
memory across axes within a single culture so they've establish this kind of relationship this kind of     
2:17:39     
representation that's very different from maybe how westerners think of it so you can understand the variation and how     
2:17:45     
that you know how that varies two a challenges the claim that each language group is a dominant     
2:17:51     
spatial reference frame at a given scale so there's this claim I guess that uh     
2:17:58     
spatial cognition and language are connected that there's like one representation for each language group     
2:18:04     
and of course we see that that's probably not true that there are multiple ways that this representation     
2:18:10     
interprets what's going on in the environment both with respect the body and just with respect to the environment     
2:18:17     
itself and then three it suggests that spatial thinking and language may be both shaped by spatial discrimination     
2:18:24     
abilities as they vary across cultures and context so spatial thinking and even     
2:18:29     
like descriptive language we talked about this in that example from indigenous New Guinea where they thought     
2:18:36     
about like um up and down and front to back a sort of synonymous because you're     
2:18:41     
either going uphill or downhill so that's and that shapes the language the descriptions that you're using and     
2:18:47     
ultimately spatial cognition in language you're interacting because you have to     
2:18:52     
describe that space that you're representing so this is an interesting this Steven pad DOI was an author on     
2:19:00     
this isn't he the person on the um llms yes team like like challenge     
2:19:07     
chomsky's model paper yes that's that's one of his papers as well yeah yeah yeah     
2:19:14     
I I you know that came out recently and I think that's why I think he's birthday     
2:19:21     
okay well you're right um makes me want to check Ling buz though in terms     
2:19:27     
of um yeah yeah always interesting to see if if that particular paper is still     
2:19:34     
at the top of Ling buuz yeah it's it's number two still oh wow     
2:19:41     
right well if anything has to with Shamsky it's like okay it's up at number one two yeah yeah anyway go ahead oh     
2:19:49     
yeah so yeah and then talks about these other uh studies in the in the     
2:19:54     
introduction so um although these egocentric or perspective dependent descriptions may seem natural to some it     
2:20:02     
is far from Universal so in uh uh in Mex in indigenous Mexicans and in OS     
2:20:09     
speakers a POA New Guinea a ball might be said to be uphill or downhill of a chair so this is like where I was     
2:20:16     
talking about with these examples where you have the ball e to the front or the     
2:20:21     
back or to the right or the left of the chair it's thought of as uphill and downhill that's the language that's used     
2:20:27     
the descriptor so the spatial representation is based on this hill and you know if you're on one side of it     
2:20:33     
you're uphill on the other side you're downhill and how that relates to a metric space is basically that it has     
2:20:39     
something to do with the radiant of a hill and so you know we have to you know     
2:20:44     
this is very far from what we're doing in uh you know in Ai and in um     
2:20:51     
computation representations thinking about it at this level you can see that there's quite a bit of variation and     
2:20:57     
it's a lot more link to language so this is um you know a nice paper also to look     
2:21:05     
at um so yeah let's let's uh have a couple minutes of commentary and wrap it     
2:21:11     
up my face got squished uh um yeah so     
2:21:21     
you know really interesting like like obviously you know what you'd want to     
2:21:27     
see um with these um these indigenous     
2:21:33     
tribes um is the kind of cognitive science experiments in terms of um let's let's     
2:21:43     
put these representations to work you know yeah and and and get some get some     
2:21:50     
data I mean you know I again I thought the the earlier papers you were     
2:21:56     
discussing the successor representation you know     
2:22:01     
was was it was about like putting putting     
2:22:06     
people into situations with those you know and and so you know again like like     
2:22:14     
we were saying earlier you know you you cognitive scientists and experimental     
2:22:19     
psychologies about designing experiments to help you     
2:22:26     
reveal what's the underlying cognitive architecture yeah or you know like like     
2:22:31     
what is the underlying uh rep what are the underlying representations and and     
2:22:37     
how kind of flexible or yeah you know what are what are their limitations     
2:22:43     
right yeah and um uh but the the thing back of my Mind     
2:22:50     
through all these papers was um again development yeah and and you know that     
2:22:57     
this is all this is all focused on you know     
2:23:04     
essentially adult Behavior after you know you know adult Behavior where     
2:23:12     
representations are now stable or something like that     
2:23:17     
right and uh um but but again this is all this is     
2:23:25     
all somewhat conditioned by the the my early     
2:23:31     
exposure to Annette carel of Smith um and her you know work on     
2:23:36     
representational redescription right so it's just like like she she's trying to     
2:23:43     
make yeah you know I mean her her work with Andy Clark in the 90s was focused     
2:23:50     
on on bringing yeah bringing a more modern     
2:23:56     
cognitive science to to pedan developmental stages right yeah and     
2:24:03     
and and I think it would like like is it gersan is that the the first author oh     
2:24:10     
gersman yeah gersman gersman sorry sorry gersman you know     
2:24:16     
um yeah like like better successor represent     
2:24:21     
presentation you know is is either more accurate or more flexible right yeah and     
2:24:28     
and what what carof Smith was showing with with you know language     
2:24:37     
examples was that was exactly that like like you you you you know very much in     
2:24:45     
the in the kind of um uh     
2:24:52     
wrote model free example you have a past     
2:24:57     
tense L verb learning um that that gets goods and and     
2:25:03     
is works except for Irregulars you know so so it's like the child successful in     
2:25:11     
language um um but is getting some things wrong and and then you have a rep     
2:25:19     
represent ational redescription that now     
2:25:25     
incorporates into that represent you know the the representations now include irregular     
2:25:31     
vers and and you know now you have this weird u-shaped behavioral growth where     
2:25:39     
performance actually goes down before it goes up yeah and and now it goes up to a     
2:25:46     
higher level you know which which was again one of the one of the modeling or     
2:25:55     
you know one of the kind of data realities that that carel Smith was     
2:26:00     
trying to um trying to understand yeah right like why why why would performance     
2:26:06     
get worse with     
2:26:12     
growth you know and and at least you know this is this is the narrative that     
2:26:17     
she sold she sold me in the 90s yeah uh but I I thought the the paper the the     
2:26:25     
gersman paper was was interesting you know the details the examples and     
2:26:33     
especially the um Ida mad um work um you     
2:26:38     
know trying to set up examples where she could distinguish these things you know     
2:26:43     
and yeah again it like goes back and forth with this like I think I think you     
2:26:49     
mentioned this too too like there were perhaps multiple systems are actually     
2:26:55     
engaged in this in the performance yeah and and you're not it's not actually one     
2:27:02     
model or you know it's not not necessarily one system that's that's doing the work here um and that again     
2:27:12     
that paper seemed to be getting into a like like it's it's a trade-off     
2:27:17     
between competing systems right you know um um which which again you know is is     
2:27:27     
another just adds to the the kind of you know experimental     
2:27:33     
complexity necessary to get it like what's what's actually going on you know     
2:27:40     
in the platonic sense right right if we could know the truth yeah     
2:27:46     
yeah um anyway really interesting and and again like also getting at some of     
2:27:53     
the the questions that um uh I think you know would be in line     
2:28:00     
with kind of Sutton's um program for for you know future     
2:28:09     
program for a future you     
2:28:15     
know metacognitive understanding of reinforcement learning     
2:28:20     
I was trying trying to make it I was trying to make it more conent     
2:28:28     
title promina to a to a future     
2:28:34     
understanding of reinforcement learning yeah yeah that's great um yeah so let     
2:28:40     
don't we put a pin in that and um think more about it I don't know what we'll do next week maybe we'll follow up on this  
2:28:47     
uh I I have some ideas but I'm not gonna I'll I'll pull together some     
2:28:53     
papers yeah yeah sounds good all right and um yeah we'll talk about every good     
2:29:02     
regulator yeah I mean we should we should definitely make time for that yeah we find find a time that we can     
2:29:09     
make instead of like always going to that same time on Thursday or something     
2:29:14     
yeah we'll make it at some points thanks have good week take care     
2:29:22     
bye
