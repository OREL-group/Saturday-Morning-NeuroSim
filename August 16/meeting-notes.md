## Meeting Recording

[YouTube link](https://youtu.be/tDST1qz-lXM)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115040923932768903)

## NOTES
Blue Skies approach vs. focused in a context.

* Public AI workshop.

1-2h keynote, 1-2h workshop. Different type of event, how do you get the right balance?

* Hackathon vs. Summit. Work to build a community. First pass -- customized experiences good for each cohort.

* DATA x DIRECTION --> good stuff going on.

* AI inequality and education.

* FAccT conference overview -- send to Medium.

Decentralized nature of science -- no centralized board that makes decisions for everyone.

* Elizabeth Bik, retraction watch.

* incentives being wrong in journals, regardless of quality and impact (lab infrastructure).

* 4 week program for Neuroimaging (Neurodesk --> IBM cloud).

* crucial component -- 3D bioprinting workshop.

JESSE: Loosely promote public events -- MIT Media Lab (ekkolapto, start-ups).

* Hackathons --> discrete builds.  Making a synthetic outcome (innovations, wider-ranging).

* doing science differently, connect to larger Qs.


Princeton Envision. Hopeful, bring different voices into the room.

* middle of 2010s vs. Now. Different set of concerns.

* incorporate things we've talked about here.


## TRANSCRIPT 
0:02    
Hello. Hi. How are you?    
0:07    
All right. How are you? I'm good. Good. Right.    
0:14    
So, welcome to the meeting. Um again, had uh two meetings this week. We    
0:21    
had Diva Worm and we had our open source meeting. So um open    
0:30    
source meeting I talked a little bit about our activities at Vika which is the biologically inspired cognitive    
0:36    
architectures conference I talked about last week in this meeting. So I ended up    
0:42    
doing an overview of that of our activities of it. So if you want to and    
0:47    
actually I cut that part out of the video. So, one of the things I've been doing on our YouTube channel is I've    
0:55    
been taking out clips of different teachers from different meetings and    
1:01    
putting in smaller videos. So, you'll find that on the YouTube channel as well.    
1:07    
So, that's a recap from this week.    
1:12    
Why don't we get started? All right. It's our Slack. Uh I have a couple of articles that were put in the Slack from    
1:20    
this week I wanted to cover. Uh the first one is this one    
1:26    
and this is about games like chess or I guess chess in particular and machine    
1:33    
learning. And the reason I found this interesting well first of all because it's    
1:39    
an interesting topic with respect to what we talked about in this meeting. But the other is that Hussein Aether    
1:45    
who's one of the lab members who comes to these meetings and also to DVORM    
1:52    
made a comment in one of the DVO I think it was this last week where he said he    
1:57    
doesn't think chess is a good metric for intelligence that's his personal take    
2:02    
and so I think a lot of people have a similar take certainly chess was    
2:08    
important in the uh gi era of AI where they were building symbolic machines and    
2:14    
they're getting to play chess and and other games like that.    
2:20    
But this is also um you know just kind of his idea that you know we we kind of    
2:26    
associate chess with intelligence and he doesn't think it's it's a very    
2:32    
good metric. So this is kind of going over this article. he was he responded    
2:38    
with positive interest in the in our slack and so let's get into this paper    
2:44    
or this article. So this is all our games turn into Kelvin ball    
2:50    
why lessons from chess don't apply to machine learning. Okay. So,    
2:57    
this uh this is Ben Wrecked. Uh this person runs a blog    
3:03    
uh where this this uh source material was from.    
3:08    
Um, I want to pick first pick a    
3:14    
I want to first pick on some peculiarities of this essay and then turned away I think Sutton which is Rich    
3:20    
Sutton who is an expert in games but not pattern recognition    
3:26    
misunderstood the transformations that occurred in supervised learning in the 2010s.    
3:31    
And then in subsequent posts to this, the author turns to their own bitter    
3:36    
lessons from the 2010s. This was of course during the rise of deep learning.    
3:43    
So one thing that always bothered the author um about Sutton's examples is    
3:49    
that they conflated parlor games and pattern recognition. So uh Rich Sutton    
3:55    
wrote this article called the bitter lesson which we've talked about extensively in this group.    
4:01    
And um you know he goes through kind of what what the bitter lesson is and all    
4:06    
that. And Sutton of course is one of the    
4:12    
originators of reinforcement learning for as a source of artificial    
4:18    
intelligence a source of simulation. And um Sutton is reflecting on why we    
4:25    
can't achieve, you know, lifelike levels of AI, I guess. And so he kind of talks about    
4:33    
games and pattern recognition as sort of a similar problem type. And in this um    
4:40    
article, the author basically distinguishes between the two and says that they're very different problem    
4:46    
domains. Both game board games and pattern    
4:51    
recognition are fundamentally two completely different problems. Their computational solutions were also quite    
4:58    
different even though both use neural networks as part of the solution.    
5:03    
Chess and Go are both perfect information games. They have clear unambiguous rules and    
5:10    
clear definitions of what a win, loss, or a draw mean. So um    
5:17    
a little bit of background on this. Uh when they say perfect information,    
5:22    
this is a term from game theory that refers to how much information are you    
5:28    
assuming each player has in the game. So if I have perfect information,    
5:35    
I have or can acquire all the information I need to solve the problem. So if we think about chess, we have a    
5:42    
chess board, we have pieces, and you can play the game to its conclusion to see    
5:48    
if there's a winner or a loser or if there's a draw. And I can state that unambiguously in    
5:55    
steps. So there are a certain number of moves that I can make to get to one of    
6:01    
those outcomes. Furthermore, if I have enough information about subsequent moves or if    
6:07    
I can get enough information about predicting possible moves down the road of my    
6:13    
opponent, I can basically uh predict their game play and I can respond in    
6:20    
time. So, it's perfect information and that you have all the information you need to play against your adversary or    
6:28    
to build um you know a simulation that you can reverse engineer. You can describe all the moves that go into    
6:35    
this. And so that's true of chess but not necessarily true of pattern    
6:41    
recognition. So if I have a pattern that I recognize, you know, maybe I can't    
6:47    
describe all the steps um to that pattern, how how the    
6:53    
algorithms say arrived at that pattern and I certainly can't replicate it again    
6:58    
and again. Sometimes a sim uh a pattern will have different ways of getting. So    
7:06    
I think that's kind of an interesting point that that's a distinction between something like chess and something like    
7:12    
pattern recognition. And there are other things we can think of as well uh that    
7:17    
produce some sort of coherent output things like um building a swarm. We    
7:24    
talked about uh swarm collective behavior, swarm intelligence, things like that. And that's kind of a similar    
7:31    
thing. And maybe it's more on that on the side of pattern uh pattern recognition, but it's    
7:37    
actually probably a similar thing. So again, chess and go and their other    
7:45    
games in this category have clear unambiguous rules and clear definitions    
7:50    
of different end states. Now, John vonman and Oscar Morgan Stern    
7:56    
wrote a book on games and intelligence and this kind of the founding book of    
8:02    
game theory. Um, and I didn't pull that book, a digital book out for this, but    
8:08    
um, it's a it's an interesting of data to read. And uh so of course vanoyman    
8:14    
invented the vonomanyman architecture and you know from that kind of led to    
8:20    
this interest in games and then applying games to computers and that's kind of how we got our chess benchmark for    
8:27    
intelligence is through that sort of um interest and synergy.    
8:36    
Uh so in in their book, Vanoyman and Borgens went so far as to call chess    
8:42    
trivial because there's definitely a deterministic algorithm that solves the game. So you can use a deterministic    
8:50    
algorithm because you have perfect information in these games.    
8:56    
You could either write a code book to predict the optimal next move or you could enumerate a game tree down    
9:02    
to 40 moves and backtrack an optimal move. So in chess and other games you    
9:09    
can build a tree. That tree describes the entire game and as long as you have enough computational power to look ahead    
9:17    
uh you know maybe four or five steps or maybe six steps then you can actually    
9:23    
figure out how to outplay your opponent. So in that sense it's deterministic.    
9:29    
There is an undoubtedly an algorithm but one of unfathomable complexity that    
9:34    
solves chess. So as long as you have enough capacity to represent all this    
9:40    
complexity that you need, uh you can you can solve chess. Essentially    
9:47    
building a computer program to approximately solve chess is of course a daunting engineering challenge. Uh    
9:54    
Claude Shannon proposed an algorithm that would uh beat uh chess players in the 1950s    
10:00    
before we even had computers uh well personal computers I guess to attempt    
10:06    
approximations. Shannon proposed performing a truncated tree search with an reasonable function    
10:12    
at the uh at the node to evaluate the quality of a board position.    
10:18    
It would take decades for computers to be fast enough for Shannon's methods to play competitive chess. But of course,    
10:25    
eventually Deep Blue was able to beat Gary Casparov in 1997.    
10:32    
And Shannon's algorithm that he proposed back in 1950 would form the basis for the strategy    
10:38    
that Deep Blue used to be Gary Costa.    
10:44    
But however, the approach that Shannon proposed and was implemented in deep blue    
10:51    
is only a bitter lesson if you were committed to the new Simon program of using chess to understand human    
10:57    
expertise. So Newell and Simon of course wrote another book in 1970    
11:04    
where they kind of furthered this chess metaphor and started to apply it to    
11:11    
looking at expertise and looking at decision making and things like that. So    
11:17    
again we're using the chess metaphor. We're using the same model, the same deterministic model. And the idea is if    
11:24    
only you can build a say a decision tree in an organization or for an individual    
11:30    
and only if you had enough information about uh the number of moves you need to    
11:35    
look ahead, you can actually solve all sorts of problems. And that may or may    
11:41    
not be true. We know from uh subsequent research to when they were doing their    
11:46    
research that uh decision making is maybe not deterministic. Maybe that's    
11:52    
not a good way to describe it. We often use heristics and um yeah it's maybe not    
11:59    
the best way to represent what they were trying to do.    
12:07    
People do not play chess the way computers do. But the idea that a computer with enough power could beat a    
12:13    
human was known in the 1940s. While the algorithms were a bit more complicated and the computing hardware a    
12:20    
few generations later uh was much more powerful. The solution to go was not a    
12:28    
huge leap from this basic strategy of tree search and heristic board evaluation. So it's basically where you    
12:35    
can represent all possible strategies of the tree and then search the best uh the    
12:41    
best solution given your opponent's moves and you can use that in chess and    
12:47    
you can use that in go and you can use that in other games but when you get to something like    
12:52    
pattern recognition it's unsuitable. Pattern recognition on the other hand is    
12:59    
fundamentally a problem of induction. So this is where we're moving now to    
13:05    
pattern recognition. And again, we're trying to find patterns in data or patterns in some sort of    
13:15    
maybe some real world image and we're trying to figure out if these patterns    
13:22    
maybe mean anything. Uh we match them with maybe like a training set and look    
13:28    
and see what those patterns are. So sometimes we find patterns we weren't expecting. Sometimes we find spurious    
13:34    
patterns. Sometimes we find wells supported patterns. And so what is the    
13:40    
goal of pattern recognition? So if we ask the question like that, we    
13:45    
see that pattern recognition doesn't have the same goals as chess or as go or    
13:51    
any of these other games. I give you a sequence of examples and    
13:56    
ask you to infer a property of the next element of the sequence. So again, this    
14:01    
is like a large language model where we have a vocabulary and we have to infer    
14:07    
what element comes next in a sequence where if we have a pattern a visual    
14:14    
pattern recognition problem, we have to figure out what's the most likely    
14:19    
uh state for the next pixel. These are not the same as the kind of tree search    
14:25    
that you would use for a game like chess. It's a different type of representation.    
14:32    
There is not and cannot be a code book that mathematically provably solves this problem.    
14:38    
We have known this for 300 years. Unlike in chess, there cannot be a mathematical proof that a pattern recognition system    
14:44    
works. So we can't really build a proof to show    
14:50    
how a pattern recognition system works and and have it be mathematically provable    
14:56    
because for one thing we don't have perfect information about the pattern.    
15:02    
Like if we have a large language model, we have a vocabulary. We know what word is most likely to come next. But we    
15:09    
can't say that you know language in that sense isn't deterministic.    
15:14    
There are a lot of similar sentences or a lot of similar statements and putting    
15:20    
it together is not a matter of looking it up in a table or a code book. You    
15:25    
have to have the sort of probabilistic model and you have to have verification    
15:30    
from the real world and things like that. So I don't think it's I fully    
15:36    
appreciated the point until recently. So let me not pick on Sutton for not realizing it in 2019.    
15:44    
This is when he came up with the bitter lesson and it kicked off this whole round of discussions    
15:50    
about what can and can't be learned by machines. How pattern recognition differs from    
15:57    
perfect information gains helps illustrate why the current landscape of machine learning engineering design is    
16:04    
frustratingly convoluted. So that's kind of their the take here on    
16:10    
the difference between chess and pattern recognition. Um now if we go back to Sutton, Sutton    
16:18    
had some things to say about computer vision. And so the things he had to say about    
16:23    
computer vision. Uh so he says early methods conceived division as searching for edges    
16:31    
or generalized shapes or in terms of sft features. But today all this is    
16:38    
discarded. Modern deep learning neural networks use only the notions of convolution and certain kinds of    
16:44    
invariances and perform much better. So    
16:49    
you know uh methods of three deep learning methods of computer vision    
16:55    
involve trying to find these features in let's say an image where you have these    
17:02    
uh you know these these motifs and then you had to match them with templates    
17:08    
and you know worked to some extent. But of course, deep learning kind of got    
17:14    
around a lot of that by being, you know, being able to do this through sort of a    
17:19    
different uh strategy. So, SF was from 1999. I know this is    
17:28    
ancient history now, but I would not call early computer vision. Sift features were invented after    
17:34    
convolutional neural networks, and the two coexisted for different purposes in the computer vision community. Yan Lun,    
17:41    
no fan of shallow learning methods, would always sing the praises of SIFT, notably because SIFT had rejected had    
17:48    
been rejected three times by illustrious computer vision conferences. So what he's saying here is that the    
17:55    
things that Sutton was talking about with respect to computer vision was he was creating this artificial dichotomy    
18:03    
between sort of these methods that weren't deep learning and deep learning    
18:08    
and how that works much better. But of course there are methods that came post deep learning or came at about the same    
18:15    
time. So the components of deep learning or convolutional neural networks came    
18:20    
before things like SIFT. Having looked at SIFT features myself,    
18:26    
I'm not sure I'd say that they leverage human knowledge of the domain more than convolutional neural networks do.    
18:34    
As Yan Lun also liked to point out features are a convolutional neural network. This one where David Low    
18:41    
crudely handcoded the weights. So this is where you know you have basically a    
18:48    
convergence to the same type of method but using different ways of doing it.    
18:54    
You know it's not worth kind of making up this false dichotomy to sort of make    
18:59    
up a story about why something worked and why something didn't. If you look at the lowest layers of a    
19:05    
convolutional neural net, you'll always see simple sift like edge detectors.    
19:11    
So moreover, if you want to solve pattern recognition, it isn't sufficient to merely output SIF features. You have    
19:19    
to apply some sort of classification function to them, be it linear or nonlinear.    
19:24    
Nonlinear classification on SIF features leverages computational power in the    
19:30    
sense that if you have enough data, its error rates decrease. So this is an interesting point because    
19:36    
we said about um solving chess that chess is a deterministic game. You    
19:44    
have perfect information and you just need to have a tree of large enough size and if you can represent that in the    
19:50    
computer then you can quote unquote solve chess. Um now in the case of convolutional    
19:59    
networks and sift and all of this we want to do nonlinear classification    
20:05    
we basically have to have enough data to not necessarily solve the problem but to    
20:13    
decrease the error. So it's a sort of probabilistic    
20:18    
version of what is a deterministic problem in chess.    
20:23    
But of course you need to have both rely on a lot of having a lot of computational power available. But you    
20:30    
can clearly see that there's sort of this there's sort of the same trend that computational power gives you an edge in    
20:37    
both cases but it's a different type of thing that is happening.    
20:42    
So back to the article, however, convolutional neural networks undoubtedly outperformed sift based    
20:49    
methods in the 2012 imageet competition and p people immediately saw how to    
20:55    
scale Alexet where it was not clear how to move beyond the second place SIF based entry.    
21:02    
Now Sutton is vaguely alluding to SIFT uh as using more human knowledge than convolutional nets and that this    
21:09    
hindered progress. So we should learn a lesson. So let's try to apply it. A    
21:15    
multi-layer perceptron with one hidden layer, a convolutional neural network    
21:20    
and a transformer all leverage computation. We don't leverage their    
21:25    
human knowledge. Why do we use transformers instead of MLPS or compliments?    
21:33    
Okay, so that's kind of one part of this updated bitter lesson, I guess. Um, now    
21:40    
the original bitter lesson by Sutton has nothing to say, but the answer is clear.    
21:45    
It's because transformers seem to work better on evaluations people care about at the scale of data they care about.    
21:53    
Is that a fully rigorous statement? No. Are the rules of evaluation as cut and    
21:58    
dried as they are in parlor games? Also no. If pattern recognition is a game,    
22:04    
it's one of Kelvin ball. Kelvin ball is this game that if you remember the comic    
22:10    
strip Kelvin and Hobbs um Kelvin used to play this game where he constantly changed the rules and so    
22:17    
you could never win because the rules were always changing in Kelvin's favor and so this is kind of the idea that you    
22:24    
can shift the goalposts or shift the rules of the game and you know kind of come up with this story of    
22:31    
why things work. And so this is kind of    
22:36    
the thing about pattern recognition if you think about pattern recognition as a game.    
22:44    
Okay. Um but what unites parlor games and pattern recognition is evaluation by    
22:50    
competitive testing. Uh whatever seems to work best today in a particular leaderboard is what people run with    
22:56    
tomorrow. It is undeniable that comp competitive testing has been the primary driver of the academic and industrial    
23:04    
branches of machine learning which has consumed the rest of artificial intelligence.    
23:09    
That said, I worry we have lost something in the embrace of pure scaling through this sort of Kelvin ball. This    
23:16    
design pattern can't tell us what to do after we hit the inevitable wall of diminishing returns.    
23:22    
Okay. Um yeah, so this is great. And then um so    
23:30    
that's this article and I thought it was really interesting because we did have this discussion about chess, you know,    
23:36    
intelligence and then of course there's this issue of chess being a sort of a    
23:42    
thing that defines uh artificial intelligence pre-dearning.    
23:49    
But now with deep learning and post deep learning, we don't really go have the    
23:54    
go-to of chess anymore as a metaphor. We really kind of lean on pattern recognition. It's important to realize    
24:01    
that these are two separate uh types of things.    
24:08    
Okay. The next uh article I want to go through here, this is from diagram    
24:14    
monkey blog. Um, and again, I just ran across this uh blog. It's uh I don't    
24:20    
remember who the author is, but this is where this is from. And this is an    
24:26    
article on meta meta-cience or open science. And there's been this um sort    
24:33    
of argument in meta-cience about sort of the utility of    
24:40    
significance testing and how to reform science. So the idea is that a lot of scientific results have    
24:49    
been based on significance testing and a lot of people think that    
24:54    
significance testing is flawed and that can sometimes call a lot of    
25:01    
scientific results into question. There is also this issue in parallel to    
25:06    
that of the change of practice in science. So, you know, how do you best    
25:13    
approach changing practice? You can ashame people into changing practice. You incentivize people into    
25:20    
changing practice or do you try to come up with good alternatives to convince    
25:26    
people to change their practice? And so, uh, this this blog post hits on a lot of    
25:33    
these issues. So, the title of this is Metathugs. And    
25:38    
I know this is pretty, uh, in your face. Um but that when they say metathogs    
25:44    
they're referring to meta-cience and some sort of the maybe unsavory    
25:49    
practices within that field. Okay.    
25:54    
And this is independent of like science reform by the way. This is actually getting to science reform. So just so    
26:01    
we're clear what meta-cience is. It's the science of science or it's the uh    
26:06    
science of studying scientific methodology. So, um, there's this two-part series in    
26:15    
how to science a science with science, which is like some reflections of meta    
26:21    
science. Metathogs is one. There's another one I'm not going to talk about. Um,    
26:26    
and so, yeah, so I knew things had definitely gone wrong when science invited us to    
26:33    
meet the data thus. So this was an article that was published in science journal and it was about um sort of how    
26:42    
people go and they look at data sets that have been published or look at papers that have been published and try    
26:48    
to interrogate the data to make sure that there you know there's no fraud or there's no you know sort of mistakes in    
26:55    
the data or things like that. There's a whole cottage industry of people who    
27:00    
investigate papers that have already been published and you know if they suspect that there's some malfeasants or    
27:08    
there's some you know uh degree of error in the results they will go through and    
27:14    
reanalyze the data and see if they can replicate paper or find any errors in the paper. And you know maybe this is    
27:22    
people's shock or maybe to no one's surprise you know there are a lot of papers that    
27:27    
are maybe missing the mark that sometimes they have to be retracted and    
27:33    
sometimes it's just a matter of you know that these things weren't caught in peer review and we we've talked about this    
27:40    
before. Um, so this is uh it was an article on science in science journal and it's    
27:48    
called meet the data thugs and it's kind of a provocative title for an article was basically about    
27:55    
um these meta scientists. Not only were they thugs but they were enforcers, watchd dogs, whistlebls,    
28:03    
etc. So basically these negative connotations to an activity that is um    
28:09    
you know probably necessary and you know a lot of you know one could say that if    
28:16    
you're a large high stakes journal you maybe don't want people poking around in    
28:21    
some of the things that you've accepted because it can hurt your reputation. But in any case, and and again, if you're    
28:29    
like a scientist, you might feel threatened by people poking around your work and and you know, making the    
28:36    
assumption that it needs to be investigated with a critical eye. I    
28:41    
mean, that just happens as a matter of, you know, protecting our territory.    
28:47    
So, of course, thug is not a positive word, and I was surprised that someone would choose to describe themselves in    
28:53    
that way. Nevertheless, the article is positive in general and supportive of thuggishness. In this sense,    
29:01    
what the thugs were doing was investigating published papers, checking the math, demanding data, proddding    
29:07    
suspect analyses, cutting, which is kind of uh, you know, being self-righteous,    
29:15    
that kind of thing. The title of the piece had them out to expose shoddy and    
29:21    
questionable research. Okay. So, it's like, you know, some of this is self-escription, some of this    
29:27    
sort of the um a lot of times in the glamour journals, you get this sort of    
29:32    
salesmanship of something. You have to like you frame it in a controversial way and you get discussion.    
29:39    
Um, so that's kind of where we are with that. Um, and so    
29:45    
I suppose that this is a good thing. So, you know, it's not a bad thing to    
29:50    
uh try to do this and to try to hold people accountable, but there is this aspect of    
29:57    
kind of almost well kind of a revenge driven thing, but and overall this is a    
30:04    
good thing. This is a thing we need to have. We need to have these checks in the scientific    
30:10    
community. We were dealing with scientists after all and they were operating the error    
30:17    
correcting mechanism that is supposedly one of science's greatest strengths. So of course this is something that happens    
30:24    
in peer review. It's supposed to happen in peer review. There's supposed to be this sort of deconstruction of the work    
30:29    
this crit this critical eye cast on the work and sometimes it makes it in peer    
30:34    
review and sometimes peer review fails at that. And so, you know, having an extra sort of post peerreview error    
30:41    
correction mechanism is not a bad thing necessarily. And certainly we do have post peerreview or post publication    
30:50    
peerreview um journals or models that we can turn to. But again, even in those    
30:57    
cases, we have a subset of eyes that are looking at this paper. Maybe three,    
31:02    
maybe five, maybe six. And we if we have many more especially    
31:08    
when you know the paper goes out into the world people try to replicate it or    
31:14    
they turn to it as sort some source of authority. It's good to have a way to sort of make sure that we're not kind of    
31:21    
relying on something that's errorridden. Science is so big now, so varied in the    
31:28    
forms it takes, so exquisitly differentiated in its roles that there's no reason why one of its specialized    
31:34    
functions shouldn't be dedicated purely to correction. And yet, this whole article bothered the author of this    
31:42    
post. Um, and of course, you know, you can see why because it's like on the one hand, it's this necessary function. On    
31:49    
the other hand, it's framing it in this sort of u sort of moralistic and    
31:55    
um    
32:02    
in this sort of moralistic and controversial way.    
32:08    
The botheredness started much earlier. So I was very slow in the uptake. So this goes back to a paper that was    
32:14    
published in 2005 which was published by a person named John Ionatis.    
32:22    
And so this is where kind of like the roots of a lot of the meta science comes from. So it comes from this era where    
32:29    
people in well there are people who started in social psychology    
32:34    
but also people in medical research who started to like question P values and    
32:40    
why those were important. And there are people sometimes basian and sometimes not. The question whether p values are    
32:48    
the right way to dis determine statistical significance. And the    
32:54    
problem with that of course is that a lot of papers in the literature use p values and they rely on p values for    
33:01    
saying whether something is significant or not and pointing us to things you    
33:06    
know results that are significant and real versus spurious and things we don't    
33:14    
need to worry about. And so this is a you know this is a problem because there are a lot of    
33:19    
papers with this kind of test that's maybe not rigorous enough to really give    
33:25    
us uh a true answer as to what is not spurious    
33:30    
then maybe there are a lot of spurious uh results in the literature    
33:36    
and so John Ionatus published this paper in 2005 why most published research findings are    
33:42    
false so it kind of builds on this idea that like if the p value is uh lacking    
33:50    
but maybe it's a a bad methodology ology and maybe a lot of the science that uses    
33:55    
that is also wrong which is of course in my opinion is that's just probably not    
34:01    
true. You have a lot of results. You know the p value actually does help you    
34:06    
distinguish between spurious things uh spurious sort of    
34:12    
results and non-spurious results. Um    
34:18    
so you know this is not you know this is kind of I think a uh bridge too far in terms of like    
34:25    
making a judgment about most scientific findings. Nevertheless, you do get this phenomena called P hacking where people    
34:32    
will try to get to a posit or to get to a significant p value. And so they might    
34:38    
do things like exclude things from their samples or add subjects to their samples    
34:43    
or design their experiment in such a way that sort of makes their ecological    
34:49    
validity less valid. And so they do things that make the experiment    
34:56    
uh you know make the p value significant that don't reflect the real world or    
35:01    
don't reflect good practice. So this was a pretty um pretty    
35:08    
controversial paper I guess at the time. Um and so you know this is something    
35:14    
that like it catches the eye. It says oh yeah this is a really interesting question. But the problem is is maybe it    
35:20    
isn't a question. Maybe it's a question that's made under false pretenses.    
35:25    
So something to think about. Even as a brand newish scientist, it seemed fishy,    
35:31    
which I've always thought it was kind of like questionable. And as an aside, and I'm    
35:37    
not making any casting any versions here, but John and I and Addis also signed the Great Barington Declaration,    
35:43    
so I don't know if that has, you know, there's this connection between the two, but whatever. Um I was reading a lot of    
35:52    
papers about methodology but this one stood out. In my notebook I wrote this    
35:57    
paper is another methodological study which is modestly summarized by its title. Unfortunately I don't think this    
36:05    
conclusion necessarily follows from the analysis. So the idea is that there's this sort of    
36:12    
you know you go to the literature you see what uh you know a paper you're    
36:18    
papers are using p values and there was this whole analysis in the paper and    
36:23    
then it led to this conclusion and of course a lot of people found that maybe this was kind of a reach uh for what    
36:30    
you're trying to do. What set it then he's talking about this    
36:36    
paper why most published research findings are false. What set it aside was the sweeping nature of its claim.    
36:42    
One of the subheadings is most research findings are false for most research designs and for most fields. So that's a    
36:50    
pretty uh sweeping generalization.    
36:55    
But in any case uh and and then of course the uh consequence of this is    
37:02    
that you can't really hedge from something like that. Maybe you can hedge from the title but not from the    
37:08    
subtitle, shutting out any possibility that it didn't mean exactly what they said. But for all this, there was very    
37:15    
little theoretical input and almost no data to back it up. So they didn't really do this hugely rigorous analysis.    
37:22    
So we're just showing in the literature you know that the p value is prevalent and if the p value of problems and maybe    
37:29    
the entire scientific interpret problems and of course that's a pretty large leap    
37:34    
because different fields are different practices with respect to the p value and you know so in some fields you might    
37:41    
get prevalent p hacking in some fields you might not    
37:47    
just as one example there were lots of papers in that approximate area but the majority were    
37:53    
vastly more measured and importantly brought data to the argument. So there    
37:58    
is this set of papers and there's been this set of papers that have continued to be published on P hacking and on    
38:06    
scientific reliability and on the design of experiments a lot of things in meta    
38:11    
science and so you know there wasn't this sort of controversy around it or    
38:18    
maybe this generated controversy. So um    
38:24    
continuing on with this paper, the author or this blog post, the author    
38:30    
kept a summary of some conclusions that went something like this. This is a long list of conclusions. Um    
38:38    
so the first one is that the peer reviews process doesn't work. Obviously, if there's a problem with p values and    
38:45    
people are reviewing papers and accepting papers that use the p value,    
38:50    
then peer review is kind of useless. Of course, this also holds true. Maybe you    
38:56    
could make that claim from the original example that we gave where we had people    
39:02    
who went and sleuth into data sets into results from published papers. And if    
39:09    
you find errors, uh, then that means that the peer reviewers didn't do their job. So there's this implication that    
39:15    
peer review doesn't work. There's also this implication that peer-reviewed papers can have major    
39:21    
genrewide biases. So again you know in some fields you can    
39:27    
have uh different standards for publication than not    
39:33    
depending on the sort of the state of the art of different statistical tests and methodologies.    
39:41    
The third is that commonly used tests often reject real effects. So with p values like I said we try to distinguish    
39:48    
between things that are the null hypothesis and things that are you know    
39:53    
other types of effects and we can't necess    
39:59    
you know maybe it's not sensitive enough to real effects there are these type one or type two errors that um so we we you    
40:07    
know look for type one errors but there's also type two error and it's hard to kind of overcome those in in a    
40:14    
lot of context. Even if papers avoid these problems, most of them are wrong. That seems like    
40:20    
a statement that is worthy of just kind of making things up.    
40:26    
Um, pointing out that they are wrong is a little bit or no effect on their citation rates. So, we often cite things    
40:33    
that are basically wrong. Of course, that's a subjective statement, but there are a lot of papers that get retracted    
40:39    
that get citations. And sometimes you even collect citations after they're retracted. But I think what is more    
40:47    
likely is that you have situations where a paper becomes a standard in the field    
40:54    
and it's either dated maybe after 20 years or it's been proven to be wrong by    
40:59    
subsequent work, but people still cite those papers. That's a that's a problem, but it's    
41:06    
maybe outside the scope of the original paper that we were talking about here. and maybe it has nothing to do with p    
41:13    
values. So, put that one aside. Um, if they're not wrong, statistical    
41:18    
significance is not the same as actual significance. So, again, there is this distinction    
41:24    
between statistical significance using say like a p value or some other metric    
41:30    
distinguishing between some real effect and some null    
41:35    
hypothesis. Um but of course there are things that are significant in the world that are    
41:42    
detected by p values. Maybe the sample size isn't large enough. Maybe the    
41:48    
phenomena hasn't been characterized the right rate measures things like that.    
41:53    
Uh the next point is important insignificant results might be imperceptibly different from significant    
41:59    
results. And this again is an artifact of the p value and how it detects    
42:05    
sensitivity, how it detects um significant things. And I mean in    
42:12    
science we're always looking for the significant difference between two groups. A lot of times if you do an    
42:17    
experiment, you have two groups. you have a control, you have treatment group or something like that, and there's    
42:23    
supposed to be this difference that is uh sort of free from variation. So, you    
42:30    
should be able to find an effect size that's large enough where the mean of the two groups is    
42:37    
different enough with no overlap in their variance to give you something    
42:42    
that you can say this is an effect. This is the effect of this treatment. This is the effect of this difference between    
42:49    
the groups. Now, sometimes you don't have enough    
42:55    
samples. Sometimes you're not hitting on the right measures. Sometimes it's just a    
43:01    
very small effect and it's hard to pull that effect size out. So, it's a long a    
43:07    
small effect size and it's hard to really distinguish it in an experimental setting. So this is you know all kind of    
43:15    
saying that there are a lot of problems with the p value a lot of things that you can say it doesn't solve which is    
43:22    
maybe not surprising but does that mean that all the results that or in the scient or most of the results in the    
43:28    
scientific literature are wrong I would probably argue against that    
43:34    
even if you find something really really really significant it can fade away over time windowing inexorably this    
43:41    
insignificance Another point is most papers never get cited anyways, which is not actually    
43:47    
true. A lot most papers actually get cited at least once. And then this last    
43:53    
point, but who cares? The end of the world is more likely than we thought. So I think this comes back full circle to    
43:59    
the um the Great Bington Declaration. But anyways, I don't want to get into that. I'll just say that like this is    
44:07    
there's a lot of there are a lot of problems with this kind of approach to meta science where you you know there's    
44:16    
this is it distinguishable from sort of an attack on the scientific enterprise    
44:22    
or is it calling out their errors and trying to earnestly address them?    
44:28    
It's hard to say. And when you write papers like this where it's very provocative, it can blur that line.    
44:37    
While it's easy and important to point out ways in which it doesn't quite work as advertised, it's much harder to say    
44:42    
why it works at all, especially given how unreasonably effective it seems to be. So there's this paper the    
44:49    
unreasonable effectiveness in mathematics which describes why mathematics is sort    
44:55    
of a core tool in the scient or in the scientific and engineering toolbox    
45:00    
because it's an unreasonably effective way to get to answers to approximate things to find kind of an answer for    
45:09    
things that we haven't been able to do. And so it's science the scientific    
45:14    
method is the same way. It's very effective at finding sort of mechanisms or finding evidence for mechanism,    
45:22    
mechanistic thinking. And so it's a good um I think a method that you know has    
45:29    
flaws of course like anything else mathematics has flaws but it works to give you a reasonable answer.    
45:36    
So they site uh XKCD of course as you as you do um and this is summarize    
45:44    
summarizing this reason that the author is interested in uh one reason nicely    
45:50    
summarized by XKCD particularly and I cannot stress this enough the alt text    
45:57    
is here is that scientists are genuinely curious about the answer to a question.    
46:03    
Anyone who's genuinely curious about a question will take these things in and try to do better next time. So, one of    
46:10    
the things about self-correction in science is that it's personal self evaluation or self-revaluation    
46:17    
where you have this uh you know, you learn from your experiment. You do an    
46:23    
experiment. You might find a significant result. You might find things that don't pan out. And then you try to maybe do    
46:30    
another experiment where you reformulate your questions, you reformulate your    
46:36    
experimental design, and you try it again. And you keep doing this in a iterative way until you get um maybe a    
46:44    
very good answer to the question. It's not a one-shot deal where you have to find the perfect answer to a question.    
46:52    
They will also ask searching questions about the criticisms. For instance, are most published research findings really    
46:59    
false? I mean really false. Is it a reasonable question about an unreasonable claim? So you you ask a    
47:06    
question about something that doesn't seem to kind of work doesn't seem to make sense and then if you ask enough    
47:14    
questions or if you try to frame your question in the right way and you really kind of work on that question over time    
47:22    
you can find a way to test that and you can find a way to really verify that    
47:27    
part. So I guess one thing you you see from this uh article is that sometimes    
47:36    
science and like this self-correcting aspect scientific enterprise is about    
47:42    
going and investigating things investigating things that have already been published sort of enforcing and    
47:49    
making sure that like good practice was followed and then the outcome which is    
47:54    
good reliable science. But there's another kind of route to science reform    
48:01    
or science uh meta-cience which is question asking and that kind of backs    
48:06    
us up a couple steps to sort of the formulation of experiments and the formulation of um how to you know how to    
48:15    
execute the scientific method and that is let's think about claims that are    
48:20    
made. Sometimes it's the title of a paper and sometimes it's about um you    
48:27    
know something that people think is true. It's maybe an assumption that we make and then interrogating that    
48:33    
assumption or that provocative thing with a question not just a question    
48:39    
about whether it's true or not but how do we you know kind of make a determinate statement about it. Okay.    
48:46    
And then of course because it's not something that we can always hit on right the first time we have to keep    
48:53    
iterating and kind of improving our question and improving maybe our experimental design or whatever it is    
49:00    
that we're doing our method of investigation and then eventually we get good answers to those questions.    
49:09    
Okay. Um so going back up to these points here uh that I summarized    
49:15    
uh the the author continues such questions fed into the newish field of meta science which having troubles of    
49:23    
its own including the aforemention of buggishness to spawn the field of    
49:28    
critical meta science. I suppose calling it meta meta-cience would be silly but the difference is    
49:34    
perhaps a crucial one which I will come back to later. Some of these studies or the ideas    
49:41    
within them short of any caveats were eventually t taken as signs not that    
49:46    
science was self-reflective and self-correcting but that science was broken or in crisis. So this is where    
49:54    
we're getting into this distinction sort of like where you have a good faith sort    
50:00    
of set of complaints about the way science is done and can lead to    
50:05    
productive outcomes and then this idea that science is broken or in crisis which can lead to    
50:12    
bad outcomes and I think you know you can tell the difference by sort of the real world    
50:20    
implications. So when you say that science is broken or in crisis,    
50:25    
it can be a mode of like kind of self-improvement. Of course, we want to fix things that are broken and we want    
50:31    
to solve a crisis. But that kind of viewpoint can be hijacked by bad actors,    
50:38    
people who want to, you know, science deniers or other types of people who want to attack the scientific enterprise    
50:46    
as a source of authority. And so this is the distinction they're making here.    
50:52    
that there are healthy ways to sort of do this sort of self-reflective and self-correcting or make sure that that    
50:59    
mechanism is robust and and working. In some cases, it doesn't always happen    
51:05    
that way and so that needs to be, you know, addressed, but there's this other view that science is broken or in crisis    
51:12    
and we want to try to avoid. Okay. So, um this is kind of the shift    
51:19    
in some of the meta-cience practice that we've seen in this field. Uh the shift    
51:24    
in emphasis was used at least in part to justify the existence of data thugs and    
51:31    
police and a more direct approach that has given meta science its particular flavor. So there is this aspect in meta    
51:38    
science where instead of kind of thinking about you know just kind of making sure that our process is robust    
51:47    
robust to criticism as well as robust to practice that we constantly see things    
51:52    
as being broken or in crisis. And it gives of course meta-cientist jobs or meta meta scientists jobs but it also    
51:59    
kind of um feeds into this sort of    
52:05    
erosion of authority and so on. And so um this is one of the criticisms of a    
52:12    
lot of the meta science that's the bigname meta science that gets published is that it has this flavor because it's    
52:20    
um this latter aspect of meta science where it's broken or crisis is    
52:26    
provocative and attracts a lot of attention and a lot of debate. Um, that's maybe a    
52:35    
problem in of itself because if you have something that really is controversial, you can bring a lot of attention to it,    
52:42    
but ultimately it's corrosive. Uh, the language is telling. While your    
52:48    
peers might politely disagree with your paper, there is at least a notion of equality, collegiality, give and take.    
52:56    
They are your peers. The relationship however between thug and a scientist is not equal. Nor is a relationship between    
53:04    
watchdog and watched enforcer and enforce. So this idea of being kind of    
53:10    
like an enforcer or there's this term    
53:15    
this this idea of good cop bad cop where the good cop kind of wants to be your    
53:21    
friend and the bad cop wants to kind of force you to tell the truth. In both    
53:28    
cases, they're trying to get to the same goal of sort of interrogating people and getting them to tell the truth, but they    
53:34    
approach it in different ways. And so, this is kind of the same thing here between sort of this normal    
53:41    
collegiality, the sort of normal peer review, and then this thug approach,    
53:48    
which is what the author is kind of obviously against. In the more police    
53:54    
oriented descriptions, we must assume that the relationship is that between police officer and suspect, if not an    
54:00    
actual criminal, and it isn't voluntary at all. However, it's phrased it puts a space    
54:07    
between us and them and linguistically at least keeps the power on one side.    
54:13    
If you internally divide science into a group doing science and a group studying and critiquing the methods used by    
54:19    
scientists, then you have a system that is in some sense unstable.    
54:25    
The binding force and science together is relatively weak and depends on the usual scientific give and take sure we    
54:32    
all cast a critical eye on our peers work but at the same time we can return    
54:38    
the favor and there's an incentive to understand what in their work work is worth building. If we separate those    
54:45    
functions, criticism tends to become an envy itself. Divorced around a positive goal, the    
54:52    
incentive shifts towards seeking out subtler and subtler errors or more trivial and trivial errors until none is    
54:59    
left. So there's this incentive to sort of h be hyperritical of the work and    
55:05    
kind of like salami slice the errors until you basically    
55:11    
you know critique the entire work and say that all is false.    
55:16    
Um, sometimes though this can also lead to complaining strididently about problems long after they cease to be    
55:23    
problematic. So people who will get on their hobby horse about some problem that has been solved uh and and just    
55:30    
kind of paint science the scientific uh practice as emblematic of that thing    
55:37    
that no longer exists. The difficulty is to keep those aspects of meta science a part of ortho science    
55:44    
which is a term they kind of come up with so that they can feed off and exercise exercise one another. The    
55:52    
critique needs to go both ways. Certain correctives have been proposed    
55:57    
to strengthen science by both meta-cientists and regular science.    
56:02    
Um and which is of course you know this idea where we need to have open science    
56:07    
where everything is transparent and we can you know see the data and the code    
56:13    
and connect this with other articles and then of course there's this other branch    
56:19    
of meta science which is methodological reformation and methodological reformation is nice    
56:26    
but of course um this runs into a lot of problems with practice and with    
56:31    
tradition. So both of these ma both of these approaches to meta science requires a    
56:38    
certain amount of incentivization but we want to make sure that incentivization is positive not negative. This kind of    
56:44    
goes on and talks about a little bit about like the trust in science that you know we need to have in order to have a    
56:51    
robust enterprise sort of the authority of science. And so    
56:57    
you know there two camps on this. One is that there is this aspect of science    
57:02    
denial and that there people want to sort of use maybe the inevitable errors    
57:10    
that arise in the scientific enterprise as an excuse to uh criticize science and    
57:17    
say that there are other alternatives that are better and erode the authority of science.    
57:24    
And of course, you know, there are other kind of reasons for, you know, sometimes    
57:29    
this is it leads from actual errors like papers that have been retracted and sometimes    
57:36    
it just kind of builds upon misunderstandings and other things like that.    
57:44    
So, it's it's an interesting article. I think it covers a lot of ground but basically it has this critique of    
57:51    
meta-cience and the two ways to do meta-cience um and how those kind of feed into    
57:58    
larger issues.    
58:03    
So those were uh two selections from this week from the Slack. Uh, you know,    
58:09    
we have things that come across the Slack all the time, so I probably missed some that were interesting, but    
58:15    
thanks to people who posted those.    
58:20    
All right, moving on. Um, want to get into a few articles. Um,    
58:27    
these are two articles that I found from I guess they're AI related articles.    
58:34    
First one here is something that Paul talked about last week. He pointed out this article on daydreaming    
58:42    
and Hopefield networks kind of led from the discussion last week and it was brought up and I just wanted to go over    
58:48    
kind of a quick mention of what this paper was. So this the title here is daydreaming hopefield networks and their    
58:55    
surprising effectiveness on correlated data. These are hopefield networks. This is a physics inspired neural network. As    
59:01    
such, it's so it's it's basically operating like a spin glass model if you're familiar with spin glass models    
59:07    
in physics. So the abstract reads to improve the storage capacity of the hopefield model, we develop a version of    
59:14    
the dreaming algorithm that perpetually reinforces the patterns to be stored. So    
59:19    
this is uh sort of the Heb's rule applied to uh learning in this method.    
59:28    
So we have an streaming algorithm that perpetually reinforces the patterns to    
59:33    
be stored. Of course, we talked about heavy learning which is where you have    
59:39    
this association between two things and that strengthens the connection between    
59:45    
those two things. We perpetually reinforce the patterns to be stored in erase spurious memories. So, it's    
59:53    
important to do two things when learning. You need to be able to reinforce    
59:58    
patterns that occur again and again and then you need to be able to erase    
1:00:04    
spurious memories or spurious patterns. So you don't want to store the spurious    
1:00:10    
patterns but you want to reinforce and store the meaningful patterns. That's basically what's happening.    
1:00:18    
For this reason we call this approach daydreaming. So the idea is that we're dreaming and    
1:00:25    
this goes back to a neuroscience finding which is trying to figure out the    
1:00:30    
function of sleep in organisms. So we sleep and we have different levels of    
1:00:36    
sleep and all that but one of the functions of sleep is of course to    
1:00:42    
regenerate uh you know to to go into a resting state. But another purpose of it    
1:00:50    
specific to the brain is to encode learning. So then encode that day's    
1:00:56    
learning. So you learn things during the day, you experience things during the day and then at night you consolidate    
1:01:03    
those memories. You're replaying those experiences in your head. So you know if    
1:01:10    
you travel uh a certain route uh to work or to school you review that    
1:01:19    
route in your head as you sleep and then that route gets consolidated so that you can retrieve that from long-term memory    
1:01:27    
and eventually you learn your route and it becomes automatic. So, you know,    
1:01:34    
the first day you do this, you might have to look this up on a map and you have the experience of traveling to that    
1:01:40    
place and you might have to do that for a couple days and you're kind of replaying that in    
1:01:47    
your head and you're consolidating that memory until it becomes a stable long-term memory that you can then draw    
1:01:53    
from. They have they proposed this model called daydreaming or heavy or for the    
1:01:59    
hopefield model. Daydreaming is not destructive and it converges astoically    
1:02:04    
to stationary retrieval maps. When trained on random uncorrelated examples,    
1:02:10    
the model shows optimal performance in terms of the size of the basins of attraction stored examples and the    
1:02:17    
quality of reconstruction. So there are two things that are of interest to it. The first is you know when they say    
1:02:24    
stable memory I mean a memory that doesn't carry you is doesn't    
1:02:30    
show a lot of variability. Because if you encode a memory that is basically true on the outlines    
1:02:38    
but isn't stable in how it can be uh retrieved or it's not stable in terms of    
1:02:44    
its details, then it's not necessarily a good um you know it's it's maybe it's or    
1:02:52    
it doesn't really help you too much. So what they're looking at here are the basins of attraction. So when you have a    
1:02:59    
basin of attraction means you have this stable uh thing that where the system    
1:03:05    
gravitates towards. So this tells us something about the stability of that memory. And then of course the quality    
1:03:12    
of reconstruction is another parameter we can use to look at you know how accurate that memory is.    
1:03:20    
We also train the daydreaming algorithm on correlated data obtained via the random features model and argue that it    
1:03:27    
spontaneously exploits the correlations thus increasing even further the storage capacity and the size of the basins of    
1:03:35    
attraction. Moreover, the daydreaming algorithm is also able to stabilize the features    
1:03:41    
hidden in the data. Finally, we test daydreaming on the emnest data set and showed that it still    
1:03:48    
works surprisingly well, producing attractors that are close to unseen examples and class prototypes.    
1:03:58    
Okay. So they they define the hopefield network in terms of its mathematics here    
1:04:04    
um and defining the network itself in terms of neurons that take on discrete    
1:04:09    
values and p discrete patterns or the memory stored in the network and then    
1:04:15    
the retrieval of the memory is successful if the spin dynamics converge to one of the stored patterns.    
1:04:23    
Okay. Um so that's how they define that. Um and so in terms of uh why they call    
1:04:32    
it the daydreaming algorithm since we stress that daydreaming can be iterated indefinitely.    
1:04:38    
Here we review the literature and alternative learning rules arguing that rules that avoided the pitfall of    
1:04:45    
dreaming too much showed other undesirable properties. The most common ones being the addition of non-local    
1:04:51    
terms and the vanishing basins of attraction. So the amount of dreaming that the model does is important. If it    
1:04:58    
does too much dreaming, it can undermine the positive attributes of sort of    
1:05:04    
selective dream that they show. So it's important to have    
1:05:11    
uh you know to let the network explore the uh space in in the room.    
1:05:22    
So I think that's enough for that paper. And this shows the day dreaming learning algorithm uh in terms of the pseudo    
1:05:29    
code. So it's showing that there's this um initialization with the he rule. Then    
1:05:36    
you know you implement this in eics. You have nsteps in each epic. You pick    
1:05:43    
an example at random. You initialize spins at random for for the spin glass    
1:05:48    
model. Um then you run the spin update dynamics. you update the coupling matrix    
1:05:55    
and then you normalize after each epic. So you have this sort of dynamical system that governs the evolution of    
1:06:02    
this network. You uh go through each epic. You define the    
1:06:08    
number of steps and then you normalize after each check it    
1:06:14    
and then this just shows that the daying algorithm has good asmtoic behavior    
1:06:20    
means it converges and this uh shows how this learning    
1:06:28    
process works. So that was followup from last week uh just to talk about the data paper.    
1:06:36    
Um this paper here is from the archive and this is a cognitive science flavored    
1:06:42    
paper. Um and but does talk about AI and kind    
1:06:48    
of this transition between uh the AI that was pre-deing    
1:06:55    
and the AI that we have now which is based on deep learning and thinking about symbols and symbolic    
1:07:02    
representations. So um we talked last week about neuros    
1:07:07    
symbolic models and the daydreaming was actually um sort of in that direction of    
1:07:13    
neuros symbolic learning. Um and there's another paper we talked about by um Josh    
1:07:22    
Jennenbomb that's that's a a good example of neurosyolic learning. Um in    
1:07:28    
this case we're talking about sort of one distinction. Okay. So one    
1:07:34    
distinction between the pre-deep learning era and the modern era is that    
1:07:40    
it's sort of the triumph of data over symbolic learning. In other words, we    
1:07:45    
used to use symbolic learning back when we use chess as the metaphor where we    
1:07:52    
represent things in terms of this table of looking up symbols to represent things. And that was thought to be the    
1:07:59    
future until datadriven AI really kind of produced a lot of good results.    
1:08:06    
And like a lot of things when you point in a certain direction you kind of go in that direction you forget about what's    
1:08:12    
in you know the other back in in the past or what might be uh useful from    
1:08:17    
other directions that you can incorporate. So basically symbols have kind of fallen    
1:08:23    
into disfavor fallen into disrepute.    
1:08:29    
So the title of this paper is whether symbols in the era of advanced neural networks question    
1:08:35    
which means when we you know we're doing deep learning what is the role of symbols if any.    
1:08:44    
So this is uh definitely a you know it's it's from this machine learning    
1:08:50    
community but it's also squarely from the cognitive science community.    
1:08:56    
So the abstract reads some of the strongest evidence that human mind should be thought about in terms of    
1:09:01    
symbolic systems has been the way they combine ideas produce novelty and    
1:09:07    
quickly. So, you know, one of the things about symbolic AI is that it used the    
1:09:13    
human metaphor. In other words, since symbols are important to humans, that symbol should be sort of the model for    
1:09:23    
simulating or making an artificial intelligence. And of course, you can do a lot of    
1:09:29    
things with symbolic systems. Um, but they have their drawbacks. And    
1:09:34    
so, you know, we we still and especially in cognitive science, we want to think    
1:09:39    
about intelligence and about minds as being symbolic systems.    
1:09:46    
We argue that modern neural networks and the artificial intelligence systems built upon them exhibit similar    
1:09:53    
abilities. So, we, you know, don't want to throw out the symbolic baby with the symbolic    
1:10:00    
bathwater, I guess, is the lesson here. uh we have reasons for thinking that    
1:10:06    
intelligent behavior or minds involves symbolic systems and so you know we can    
1:10:11    
learn a lot from training models on data as much data as possible but we have no    
1:10:17    
symbolic basis or anything else. So we can find a lot of patterns    
1:10:22    
but we might not be able to distinguish between spurious patterns and real patterns without the symbolic layer.    
1:10:33    
So this undermines the argument that the cognitive processes and representations used by human minds are symbolic.    
1:10:40    
Although the fact that these neural networks are typically trained on data generated by symbolic systems illustrate    
1:10:47    
that such systems play an important role in characterizing the abstract problems that human minds have to solve.    
1:10:55    
This argument leads us to offer a new agenda for research on the symbolic basis of human thought.    
1:11:04    
So um basically okay so let me go through this argument once more. Um so    
1:11:11    
we basically want to make this analogy between modern neural networks and sort of human minds and those    
1:11:20    
exhibit similar abilities. This actually works against this    
1:11:25    
argument that cognitive processes and representations are symbolic because we    
1:11:31    
use this data driven approach. If we can get maybe you know humanlike results    
1:11:39    
with neural networks that are driven by data then the mind must be similar to    
1:11:44    
that. But of course it undermines a lot of what we've learned from cognitive science which is that human minds are    
1:11:52    
essentially symbolic. And this is of course    
1:11:59    
also undercut by the fact that neural networks are trained on data generated    
1:12:04    
by symbolic systems. So there's this interplay between symbolic systems and    
1:12:09    
non- symbolic systems or this sort of datadriven approach to training models    
1:12:15    
and getting them to behave like human minds or something similar. Um that is    
1:12:21    
an open question. Basically there's this question about whether artificial neural    
1:12:26    
networks can represent symbolic systems such as logic and grammar.    
1:12:32    
And this has gone back uh this argument has gone on for as long as all networks    
1:12:37    
have been around. So there's certain properties of a symbolic systems that we can bring to    
1:12:43    
bear. There also properties of these data-driven systems that um play a role    
1:12:49    
in this debate. So properties of symbolic systems and the two that they    
1:12:55    
highlight in this paper productivity and compositionality    
1:13:00    
have been proposed as central human intelligence. So when we have neural networks that    
1:13:07    
cannot demonstrate these properties, it's a problem for neural networks being    
1:13:12    
sort of this analogy to human minds and human uh pattern recognition or whatnot.    
1:13:21    
Moreover, probabilistic models that operate over logic, grammarss, or programs    
1:13:27    
have highlighted how symbolic systems can be used to characterize the inductive biases that allow people to    
1:13:34    
learn from limited data.    
1:13:40    
In this article, we revisit these questions in light of recent advances in AI.    
1:13:46    
Training larger neural networks with more data using new architectures and training techniques    
1:13:53    
have resulted in improvements in reasoning, learning and using language.    
1:13:58    
So for instance, large language models based on the transformer architecture    
1:14:03    
display impressive productivity in the training technique of metal results in    
1:14:09    
greater compositionality and rapid learning. So it's not that you can't do these things with you can't achieve    
1:14:16    
these sort of symbolic properties with neural networks. It's just that there    
1:14:21    
you know certain methods that can do this to an extent. Uh but we still have    
1:14:26    
this sort of argument. Maybe it's a little bit artificial, but it's definitely, you    
1:14:33    
know, something that cognitive science can maybe address. We argue that these advances undermine    
1:14:40    
historical arguments that human minds use symbolic systems in a way neural    
1:14:45    
networks do not. So this is this sort of issue of how    
1:14:52    
artificial systems miss what cognitive systems and biological    
1:14:58    
systems produce. It's sometimes hard to pinpoint what that missing stuff is, but    
1:15:05    
it's definitely there. At least qualitatively we can tell. So maybe that's,    
1:15:12    
you know, maybe that's not true, but like you know, there is this intuitive sense that that's the case.    
1:15:18    
And so we can address this gap between artificial systems and the    
1:15:26    
mind in terms of maybe you know focusing on symbolic systems.    
1:15:31    
Neural networks display comparable compositionality, productivity and inductive biases to humans when    
1:15:38    
evaluated against the same empirical standards as humans. Therefore, further progress in understanding the    
1:15:45    
similarities and differences between human cognition and neural networks will    
1:15:50    
require new methods for evaluating such problems. So maybe it's not a matter of    
1:15:56    
neural networks not being able to do these things that symbolic systems do,    
1:16:01    
but rather we need new tests and new ways to understand, you know, that    
1:16:06    
difference. So recent advances also suggest a way to    
1:16:12    
resolve this classic debate by levels of analysis. And we'll get to the figure    
1:16:17    
one um pretty soon, but I wanted to go over this preamble.    
1:16:23    
These demonstrations of compositionality, productivity, and rapid learning arise in neural networks    
1:16:30    
that have been trained on data generated by symbolic systems. Similarly, symbolic systems also feature    
1:16:37    
strongly and human experience both within across lifespans.    
1:16:43    
Uh thus for both humans and machines symbolic systems are useful in characterizing the abstract    
1:16:49    
computational problems that need to be solved. And this is what Mar called the computational level. So the    
1:16:56    
computational level uh that bar proposes and Mar has these three levels involves    
1:17:03    
symbolic systems as well as sort of this computational aspect.    
1:17:09    
The sub symbolic processes and representations that implement these computations in neural networks play a    
1:17:17    
complimentary role at Mars algorithmic level which is a different level and    
1:17:22    
capture other behaviors that defy easy symbolic description.    
1:17:28    
Okay, so they kind of walk through this and um    
1:17:34    
so this last sentence here, evaluating this hypothesis will require a new research agenda with four interrelated    
1:17:40    
threads. The first is designing more diagnostic tasks for probing symbolic    
1:17:46    
representations. So, you know, if we want to sort of get    
1:17:52    
into maybe the potential symbolic representations produced by a neural network or the significance of symbolic    
1:17:59    
representations in human cognition, we need better diagnostic tasks for this.    
1:18:07    
The second is developing a deeper mechanistic understanding of neural networks. So, what are neural networks    
1:18:13    
actually doing? Um, we've talked about some of that with credit assignment with    
1:18:19    
other things that we do to look at what neural networks are producing. We don't want it to be a black box just as much    
1:18:25    
as we don't want the brain to be a black box of the mind.    
1:18:31    
Then the third is training neural networks in a more developmentally plausible way. So this goes back to this    
1:18:37    
developmental aspect and um this is a very popular thing to talk about now.    
1:18:46    
But um we want to be able to figure out because we know that human cognition    
1:18:51    
comes from development. How can we train models in ways that    
1:18:56    
mimic development and ways that mimic the acquisition of symbols in ways that    
1:19:02    
mimic the acquisition of seic language? You know, language isn't just something    
1:19:07    
that, you know, we'll take humans as an example. Something that humans are presented with a list of words, a list    
1:19:14    
of grammar, and then they have to construct it. It's kind of a random. Language is learned in a deeply embodied    
1:19:21    
manner. Language is learned kind of through trial and error. And you know,    
1:19:26    
they're ways that language is acquired through development that are reflected in the way that models are trained.    
1:19:35    
And probably that has something you know we we always make this assumption of course that when humans do something    
1:19:41    
it's for a reason. So this is likely to be important for acquisition.    
1:19:48    
Although you know it may not be necessarily important for acquisition. It may just simply be the way we acquire    
1:19:53    
this. And if we're talking about, you know, our official system, it might be    
1:19:59    
just as easy to throw a list of a very giant list of things up.    
1:20:05    
In any case, uh that's something we need to explore more of. And then finally, creating more explicitly cognitive    
1:20:11    
neural networks that explain human mental processes. And this is taking us back to uh connectionism. sort of like    
1:20:20    
we talked about last time, we had this sort of splitting connectionism between    
1:20:26    
the connectionism that happened before the deep learning revolution and connectionism that's happened since.    
1:20:34    
And so these more cognitive neural networks kind of call back to that pre    
1:20:39    
deep learning connectionism aspect where you know we want to use    
1:20:47    
neural networks maybe more as sort of like in you know an experimental verification test bed instead of as this    
1:20:56    
data driven applied model. In any case they they make these u sort of    
1:21:02    
recommendations for a new research agenda and it's basically bringing cognitive science    
1:21:09    
into AI more explicitly. This is figure one. This talks about the signatures of    
1:21:16    
symbol proc symbol processing in modern neural networks. So we have these uh three things here    
1:21:23    
compositionality, productivity and inductive biases.    
1:21:29    
So uh compositionality which is the first one here refers to the ability to    
1:21:35    
flexibly construct thoughts out of a set of simpler elements.    
1:21:40    
So this has a linguistics relevance to modern linguistics that this is the way    
1:21:46    
we think about ling linguistic acquisition through compositionality.    
1:21:53    
So we learn a bunch of words and we can apply those words to objects    
1:22:00    
but you know we have to compose different words into concepts. So for    
1:22:08    
example if we have a teddy bear we can have we know what a teddy bear looks    
1:22:14    
like. We know what the object looks like and we can attach that word. We also know what a skateboard looks    
1:22:19    
like and we can attach that word. And then we know what time square looks like. We can attach that word.    
1:22:27    
But by themselves that's that's fine. But then when we want to compose something, we have to be able to add    
1:22:34    
together these three words and then add together the objects in a way that    
1:22:42    
results in what we see in D, which is this image of a teddy bear on a skateboard in Time Square.    
1:22:51    
And if we wanted to describe this linguistically, we have to put in intermediate words.    
1:22:58    
So, you know, if we wanted to describe the scene, we'd have to say there's a teddy bear on a skateboard rolling    
1:23:05    
through Time Square. And then, you know, we could another person who hears that    
1:23:11    
could evoke a mental imagery that maybe resembles this image. And so, we But the important thing here    
1:23:18    
is that there's this compositionality. And this is something in artificial models that    
1:23:24    
is you know not automatic. So an artificial model will automatically make    
1:23:30    
this connection. It won't be able to build an image like this in a descriptive manner and link it to the    
1:23:36    
language in this way. So that's that's what compositionality is. And again, you know, there is this    
1:23:45    
um sort of aspect of being able to put together concepts and being able to link    
1:23:52    
it with images. Um that's that's really interesting and it's interesting to    
1:23:59    
cognitive scientists, especially linguists, but also interesting to how    
1:24:04    
machines can generate concepts and other things like that.    
1:24:11    
So the next one is productivity. And so productivity in B refers to the    
1:24:17    
ability to extend observed processes to new examples generating a potentially    
1:24:23    
unboundedly large number of novel thoughts or sentences.    
1:24:28    
So if we again and this is not compositionality but it's another way to sort of generate    
1:24:37    
new things from the original things that have been acquired. So we might have a training    
1:24:43    
data set that includes the terms tropical and Brazil.    
1:24:50    
And we want the model to generate things from these two terms, associate    
1:24:56    
these two terms and generate things that are similar to those two terms.    
1:25:02    
So when we train our data on these two words or training set that includes    
1:25:08    
these two words tropical and Brazil, the model generates words that include    
1:25:14    
nonotropical and Brazilianisms. So it's going to generate a lot of    
1:25:20    
things that are maybe not so relevant, but it'll generate things that are relevant to that association.    
1:25:29    
And so we end up with what we see in E which is this graph which shows engram    
1:25:34    
size versus the proportion of engrams that are novel. And this is of course an    
1:25:39    
evaluation of linguistic data. And it shows the performance between    
1:25:46    
humans in red and the performance of GPT2    
1:25:51    
or a large language model in blue. So we see that there's this sort of correspondence with between humans and    
1:25:59    
GPT2 except at high large engram sizes    
1:26:06    
and points where proportion of engrams that are novel increases.    
1:26:12    
So we have this scurve in both cases but GPT2    
1:26:17    
I guess outperforms humans at this very large in this very large area but    
1:26:24    
underperforms humans in this intermediate area which would represent    
1:26:29    
most um natural. So again this is a distinction between    
1:26:38    
artificial models and human cognition.    
1:26:45    
And then finally we have inductive biases which is this stated by this statement    
1:26:51    
here. And inductive biases refer to the set of assumptions that guide how a learner    
1:26:57    
learns from training. So this is where we have this graph F    
1:27:05    
which is evidence for symbolic inductive bias using networks with a training    
1:27:10    
approach based on metalarning. A neural network can learn symbolic formal languages from small numbers of    
1:27:16    
examples. So we want to be able to we don't want to have to train our model    
1:27:22    
incessantly. We certainly don't do that with humans. One of the benefits of    
1:27:27    
human cognition is that we can have a relatively small number of samples    
1:27:33    
and do a pretty good job of generalizing. We can also learn what symbols mean with    
1:27:40    
variable data. So this is an example here of    
1:27:46    
the difference between a basic network and a metalarning approach. And so this    
1:27:52    
is a graph here in f. This is the number of training examples up to 10,000    
1:27:59    
versus at the Fcore for learning formal languages. And we can see that there's    
1:28:05    
this difference between a basic network and a metal network. Meaning that we    
1:28:10    
have to use metalarning as a strategy to improve performance at low numbers of    
1:28:16    
training examples. And then we get up when we get up to 10,000 the basic network and the metalarn network    
1:28:22    
converge. So when I talk about metalarn networks, I'm referring to things that    
1:28:28    
are cognitive like in nature. So we have the strategy that mimics cognition and    
1:28:33    
gives us this ability to sort of do meddling.    
1:28:39    
So uh again for like large numbers of training examples, uh basic neural    
1:28:46    
networks don't do as well as this sort of cognitive strategy.    
1:28:53    
So, I'm not going to go through the rest of the paper. I think that's um you know, I just wanted to set up this    
1:29:00    
argument and kind of make you aware of this paper and kind of what people are thinking about in terms of cognitive    
1:29:06    
science and how to apply that to modern AI.    
1:29:12    
Looks like Jesse's here and Morgan's uh settled in in this location.    
1:29:20    
Um, I don't know if you wanted to make any comments or if you wanted to do any kind of updates or what?    
1:29:27    
Um, well, uh, you know, I got a lot to catch up on.    
1:29:34    
So, uh, I wanted to first say, um, yeah,    
1:29:39    
what is it? The all research findings are false. Yeah. now was like the original Well, I    
1:29:47    
don't know if it's the original clickbait. Yeah. But but uh but damn close, right?    
1:29:54    
Yeah. Yeah. Like Yeah. I love the Well, we didn't    
1:29:59    
really mean that. Um um    
1:30:06    
Yeah. But sorry, your your point though with    
1:30:11    
that uh I'm I'm just trying to remember some of    
1:30:17    
the the comments that you had around it. Um    
1:30:28    
in the uh what what was the context of that uh    
1:30:33    
that paper? So the context was that um there's this aspect of meta science that    
1:30:42    
is sort of I mean it's kind of grown to this harm this sort of malignant force    
1:30:48    
and yeah so like there is this argument on social media this is missing context    
1:30:53    
but that um people feel like there's this sort of authoritarian nature to    
1:31:00    
meta science where people are trying to enforce things and They view    
1:31:07    
practice of science itself as inherently flawed. Whereas, you know, maybe the better way to do it is to say, well, you    
1:31:14    
know, if we have better checks, say through peer review or if we have better sort of internal practice and    
1:31:19    
incentivizing people to do that, then that's a better approach. Yeah. Yeah. Well, as well as the    
1:31:25    
problem, you know, certainly some of the thoughts that I had when when you're covering that, you know, especially    
1:31:31    
around the problem of of citations that continue getting citations. Yeah.    
1:31:38    
They retracted, you know, and and in a sense it reflects    
1:31:44    
the de decentralized nature of of science, right? in that um there isn't    
1:31:51    
actually some some board deciding what we all right    
1:31:57    
think right and so there is that    
1:32:04    
yeah so not not everybody gets the memo right    
1:32:09    
uh but that's not it's not 100% a bad thing it uh it just    
1:32:17    
yeah And uh certainly there's been it's it's really    
1:32:23    
helpful to cover um what's her name? Is it Elizabeth Bick?    
1:32:30    
Yeah. Yeah. Is the woman Yeah. So the the the woman who started retraction watch or    
1:32:38    
uh well I think she's does the thing where she looks at different biological    
1:32:43    
papers and looks at the images to make sure they're not I mean that's that's how she started you    
1:32:48    
know and she she quite rightfully says like like I was doing you know bare    
1:32:56    
minimum checking right you know like like I just you know is it    
1:33:02    
the same image but flipped, right? You know, like like uh you know, partially just to shame the    
1:33:10    
journals in terms of like you could be doing this too. Yeah. Um    
1:33:17    
uh Yeah. And and you know how much this is    
1:33:23    
reflective of of kind of pay to pay to publish and and the the    
1:33:32    
the incentives being wrong in in the journals in    
1:33:38    
the the academic institutions. Um you know demanding papers    
1:33:46    
uh regardless of again you know quality    
1:33:51    
or impact or things like that. But you know again you know    
1:33:58    
there there are metrics but again their metrics that that become start to    
1:34:04    
be games, right? Um and uh    
1:34:13    
which which again I think is is something that you see a lot with the    
1:34:18    
with large language models. Oh yeah. Uh anyway, but uh big big problem that    
1:34:27    
um that is only going to be worse as we have more algorithmic ways of producing    
1:34:34    
content. Yeah. Yeah. So, and and then sorry I had to I    
1:34:42    
had to drop off from from 8 to 8:30 because uh we're starting connection    
1:34:48    
which is a program. It's a kind of    
1:34:56    
four-week boot camp for neuro imaging training in under underserved    
1:35:03    
underresourced locations. So it's predominantly in Africa or at least the    
1:35:09    
the two physical sites are in Nigeria and Kenya.    
1:35:15    
Uh so be looking at some of the issues around uh uh getting getting things    
1:35:22    
running on cloud too and and neuroesk running on compute services like IBM    
1:35:30    
cloud just to uh but you know covering    
1:35:35    
covering neuro imaging I'm on the mic microructural team    
1:35:40    
uh for that and uh Uh    
1:35:46    
it was a good good workshop of 3D printing.    
1:35:52    
Um we're moving forward here on that. I'm    
1:35:59    
trying to trying to think of updates. A lot of a lot of lab infrastructure.    
1:36:05    
Yeah. Getting getting old biotech equipment and trying to figure out how    
1:36:10    
how to get software to work it    
1:36:16    
and and how industry is yeah has locked down some of these    
1:36:23    
devices. So thinking about thinking about what what the next devices    
1:36:28    
we're going to be looking at in terms of you know the 3D bio printers are are    
1:36:35    
very expensive commercially you can do some remarkable things converting consumer consumer printers    
1:36:43    
uh I don't know whether looking at the open flexure microscope    
1:36:51    
and you know I think microscopy is one of those you know absolutely key areas    
1:36:58    
where again I don't know    
1:37:03    
if we can approach something that's more like a that can that can come close to kind of    
1:37:11    
confocal microscopy Yeah. Uh with at a at a    
1:37:18    
like an order of magnitude less kind of I'm sure somebody would have done that.    
1:37:24    
Yeah. There's enough need. So, but I'm looking forward to learning what the what the    
1:37:31    
problem is like what what's the crucial the crucial component that is    
1:37:38    
that is makes it so hard. Um and um    
1:37:45    
yeah, other than that um next next week is getting getting kids back into    
1:37:52    
school. Oh yeah, it's always a challenge.    
1:37:57    
Uh Jesse, how are you doing? I'm okay. How are you? Good.    
1:38:03    
I not sure what to comment on at this point and I know I missed a whole bunch    
1:38:08    
earlier as well. Um, I will loosely promote an event I guess    
1:38:16    
that I hope to be attending at next week at this time. Uh, I don't know if it was mentioned    
1:38:23    
earlier, but I think Morgan will be there at the lab summit. Um, let's see here in MIT Media Lab    
1:38:32    
assist. assisted by the augmentation lab proper but also some echolopto    
1:38:38    
stuff there from echolopto does stuff lab um but it should be a very    
1:38:45    
interesting event in terms of bringing a lot of people there's like artists and technology and startups and whatnot too    
1:38:54    
I'm still I'm I'm still sorting out some of my    
1:39:03    
a lot of a lot of stuff here that what    
1:39:09    
I'm this is a side comment the event great I'm looking forward to it side comment and and just sort of food    
1:39:15    
thought that I'm dealing with at large is it seems very much easier and this maybe    
1:39:23    
even ties to the meta science discussion I kind of came out with it seemed very    
1:39:28    
much easier to get people excited to do hackathons about um technologies are events like very    
1:39:34    
discreet very discreet build a tool build a product and I'm    
1:39:42    
quite curious because I think I want to start I uh I want to make an event at some    
1:39:50    
point maybe maybe even be over 18 months out but maybe 12 months from now would    
1:39:57    
be awesome but I'd like to make an event that was that really centered some of the stuff    
1:40:04    
that we've talked about too. Maybe maybe not necessarily in in theory as much as in practice, but    
1:40:11    
around making a conference that's synthetic um in it in its outcomes around    
1:40:18    
incentivizing people to do things that aren't just discreet discreet um    
1:40:26    
I don't know innovations but but something a bit more coordinated or or wider ranging and I know that's much    
1:40:33    
harder to do like understand there's reasons why that's not quite as appealing or maybe seen as tenable, but    
1:40:40    
what I'd really like to do is make a serious effort of not, you know, we've    
1:40:45    
talked about like every trans like doing science differently um but also sort of I want that to be    
1:40:53    
connected to larger questions um or larger problem spaces    
1:41:00    
too that I don't want it just to do science. I I imagine    
1:41:07    
I don't know if any of you all remember the old Envision conference series which is held at Frank for a while. I happen    
1:41:12    
to find those t-shirts from that event again and it's unrelated to my want to make a um    
1:41:21    
an eventually. But that that event was really wonderful at the time because it was the first    
1:41:28    
event I'd really been exposed to was open to undergraduate folks, open to younger people, early career people    
1:41:35    
that was accessible and somewhat local and and funded enough to make things,    
1:41:40    
you know, appealing for people. um but put a lot of it was hopeful about    
1:41:48    
the future but it was it covered it really put a lot of the cards on the table in an undifferiated way and say    
1:41:54    
okay let's let's bring all these voices into the room uh from like that's where    
1:42:00    
learn about Rhode for example she's she's a critical progressive voice in the space of future studies and race and    
1:42:09    
identity and all these other things without like Joanna Bryson was at the    
1:42:14    
same conference. Um, Emil Torres, Bill or No, Emil Torres was at the    
1:42:20    
conference. Logan Thrasher Collins was at the conference. Like it was just a great what it attracted and brought    
1:42:26    
together was fantastic. and also like myself from that a lot. Um,    
1:42:36    
and it's inspiring because of the breadth of    
1:42:42    
it and the scope and I think okay, you know, I've been that was seven, eight    
1:42:48    
years ago for some of those things and now, you know, the world's a bit different. And I think I think in the    
1:42:54    
middle of the 2010s, you would have a particular um I don't know. I want to say optimism but    
1:43:02    
but the ch what you're asking people to seriously think about the future and doing things different way I think is    
1:43:10    
just a different it's certainly different flavor now uh given how the world has changed since then. So, I    
1:43:16    
don't know. I'm I'm I'm my my open my open thoughts for today are along the    
1:43:23    
lines of if if a conference was to be made or some kind of an event uh was to    
1:43:30    
be made that incorporated a lot of the things that we we've talked about here.    
1:43:36    
Um and obviously I think maybe even a centerpiece for what you want to do is is things that    
1:43:41    
are related to sort of frontier map. Um and the concepts of like you know how do you identify these trajectories and then    
1:43:48    
also the practical versions of how do you lead how do you lead people or or or    
1:43:54    
foster um groups doing research groups    
1:43:59    
trying to do the investigative work. declare a project management set that was talking about professional talking    
1:44:05    
about sort of a more a more I don't want to say you know realistic I don't think    
1:44:12    
that's really a fair word but this balance between    
1:44:19    
you know it it's much more fun it's much more attractive I think to just be sort of a    
1:44:27    
sort of blue skies hackathon let's make cool products and technology You know, like I get that. Like that's    
1:44:33    
that's you you're not not to present these things as shady uh used car salesman    
1:44:42    
vibes by any means, but you're being able to sell. All right, let's come here. A great 24hour period. We're going    
1:44:49    
to focus this to be likeminded people working away. You walk away and it's    
1:44:54    
great. And we're done. We can go viral because of our coverage of the event.    
1:45:00    
you have your new thing and now you can pitch it like great that's all fine but I would love to make something    
1:45:08    
that's even like I attended of this for example I attended the um    
1:45:15    
public a workshop summit work summit this week I mentioned it yesterday I could actually was trying to go to the    
1:45:21    
workshops uh but I I don't know if I got    
1:45:26    
weight listed even though I applied earlier or whatever ever. Um, so I was disappointed to go with the workshops,    
1:45:32    
but the first day was just, you know, three or four keynotes. It was very, it was very nice. It's good stuff. Um, but    
1:45:42    
you know, one, I want to make events just like that. Um, and I think some of    
1:45:48    
the things that we talked about would fit well there. Things I'm doing will fit well there. I think we could all    
1:45:54    
have, you know, um, we could do a disc, we could do, we could do a    
1:46:00    
We easily could do some kind of a, you know, project management, professional    
1:46:05    
development for open source or alternative    
1:46:11    
AI education, whatever. We could do the exact same thing. We could have a two    
1:46:17    
one to three hour keynote day and then a one to two hour workshop day.    
1:46:24    
We do that next week. I'm not saying that I can't do it next week, but because I wanted I'm I'm not using these    
1:46:31    
things as negative examples as like, oh, these are bad, but more I want I'm I'm    
1:46:38    
really starting to think and I'll probably bring this up slowly over time. I want to make a different a different    
1:46:45    
type of event a like further out. And particularly I    
1:46:50    
do want to do something around this time next year because I know uh    
1:46:57    
I anticipate the chaos of year. So I'd like to have something in in the    
1:47:03    
works for that in particular. Um ideally that that can be sustainable enough for    
1:47:10    
that period. But um I don't know. I I    
1:47:17    
I' I've recently shifted from think, oh, this is this is an event. This like what a what a weird set of    
1:47:24    
things to put together to now it's like I think I'm taking it more seriously and and and I'm curious, you know,    
1:47:32    
even even understanding the sort of trajectory that initially I don't think I'm going to be able to do    
1:47:38    
one event that's just totally going to incorporate all the changes that I'd want to see. I don't think it has    
1:47:47    
uh the clout or pull or means to pull it off. But    
1:47:53    
uh sort of like in the Quinton Tarantino tradition of making the same film    
1:47:59    
every time you do it because you want to refine the product so much, which I never understood, by the way. Kind of    
1:48:04    
educated me. Now I kind of get it more like I get I get it why even though    
1:48:10    
it was sort of anyway um it and I could    
1:48:16    
see how this could be made a bit more peace meal. Um so that's that's my    
1:48:23    
that's my contribution for today. It's all uh big future wonderings and    
1:48:29    
thoughts and planning but um I I am    
1:48:35    
I am tightening up some joke and making another organization to do do    
1:48:42    
uh some very different things. Uh but in the future    
1:48:49    
I'm starting to put out videos to see people who want to do some of the stuff that I've been mentioning.    
1:48:55    
There's there's enough to get started with so    
1:49:02    
Okay, that sounds great. Yeah. So, yeah, I you know, I I've    
1:49:09    
thought about hackathons in my career and like I always like we talked about them in this group and I've talked about    
1:49:15    
them in other contexts and uh there's definitely an art of getting together a successful hackathon.    
1:49:22    
You know, you have to have the right mix of people. You have to have the right topic. you have to think about it not in    
1:49:30    
terms of kind of just letting people work on their own but also not you know    
1:49:36    
kind of uh micromanaging everything. So it's it's really kind of you know you    
1:49:43    
want people to to be creative that's the whole point of a hackathon but you also    
1:49:48    
don't want to just leave them to their own devices because that never really works. It always has this sort of    
1:49:54    
intermediate, you know, there's this intermediate recipe to a successful hackathon. Some of that, of course, is    
1:50:01    
technological and some of that is conceptual, right? So, it's it's always kind of hard    
1:50:08    
to pull off and hard to get the right mix. Yeah. I    
1:50:17    
watch me say this and then go make it. Have fun. I don't I really don't want to make a typical hackathon.    
1:50:23    
Yeah. Like and and and it's tough because what I what I think    
1:50:30    
when you say hackathon um the to to continue to just double back and    
1:50:36    
contradict myself with you. I think it's great because the expectations are so clear as when I    
1:50:43    
think I know exactly what to expect. I know what it is. I know I know what the    
1:50:48    
thing is. I get you have you have you know you have a very clear structure and idea    
1:50:53    
about what's going on. And I think that's great. Um, and when you have a summit or    
1:51:01    
whatever you want to call two-day conference, one day conference, you know, and all the stuff with with    
1:51:06    
Nick too, like um, like I think I think I think comparatively or or Nick is an    
1:51:14    
example, Nick, which is New York's celebration of computing. Shout out to them. I think Nickwick has been uh    
1:51:20    
fantastic at meeting its goal, its    
1:51:26    
target audience, its needs, and even see like dealing with funding and choices. I    
1:51:31    
really I I really is is has been so um great to be a part of and see um    
1:51:40    
how their mission and what they the event they made to do it uh works. And I    
1:51:45    
think it's I think it's very it's sustainable. It's not too much of a risk. Well, it's a risk, but it's not    
1:51:52    
too much of a they're staying in their lane the right amount and and and moving forward the    
1:51:59    
right amount. And okay, that's that's cool to see. Um and so it's like using    
1:52:04    
using you have Nickwick, you have hackathon models, you have there's sort of this,    
1:52:11    
you know, here in Boston there's this this I think I think it's similar to    
1:52:18    
Boston or New York or you know the Bay Area and so on    
1:52:25    
that I'm much less familiar with the West Coast but but there sort of    
1:52:31    
the the frequency and opportunity of certain events is is just very different    
1:52:36    
like like and that was a big reason why I came here from Albert was because it would just be so much    
1:52:44    
It was like you'd have to drive so far just just to    
1:52:50    
get some regular regularly happening things. And now now if you're in the    
1:52:55    
space you know to do it um it's it's very different the dynamics what the    
1:53:01    
environment holds in person. That's you know that's even for inerson stuff. where where I'm going with this I guess    
1:53:06    
is um it's going to be an interesting thing and I appreciate I appreciate    
1:53:12    
being like talking about it here with you all just just as you know but just to say that it's sort of this this this    
1:53:19    
choice to be made about when and where do you want to push things forward or    
1:53:24    
more alignment with with the mission vision that you want to have is you know it'd be much eas    
1:53:34    
just to get to get the community up because that's the thing I don't maybe to broaden by this point like I don't    
1:53:40    
think I could just pull off what I want to do yet without a lot of I'd have to really work to build up a    
1:53:46    
certain community of it. Um but at the same time    
1:53:52    
certain things are definitely tenable right now to do. Um so it's going to be    
1:53:58    
some strategic choices about you know what what can be done shorter term and how seriously and how ambitious    
1:54:06    
do I want longer term fuller versions of what I want to see happen uh uh emerge    
1:54:12    
you know so I don't know I'll leave again I'll leave it at that    
1:54:18    
but appreciate the discussion and I mentioned this a bit in the slack but um    
1:54:26    
more about this ahead. Yeah. And and specifically the more tenable version of things like I said, oh discussion series, disc special series,    
1:54:32    
whatever. But yeah, like I don't know. I don't know what you all will be up for. Maybe this is some of the in the most    
1:54:38    
immediate sense next week um when Morgan's in town and we're all here we    
1:54:43    
can have maybe a maybe a very brief um I don't know    
1:54:50    
all uh you know discussion about about some potential potential things to do on    
1:54:57    
these fronts in like basically the rest of this year because there'll be opportunities to do things this year.    
1:55:02    
Yeah. I think I need to I think I personally see an area where it's like    
1:55:07    
stepping up into someone who's hosting and running events might be an avenue that I go down a bit    
1:55:15    
more even like virtual simple online events. That's all we move on.    
1:55:20    
Okay. Yeah. No, I like that. And I don't know I don't remember if I've ever    
1:55:25    
presented on the I have a unit in my project management course where I talk about hackathons    
1:55:31    
in this larger category of public meetings and athons and things like that. So you can have like hackathons,    
1:55:38    
docathons, ideathons, you know, whatever. And then they build upon this model, larger model of public    
1:55:45    
meetings where you have, you know, you have discussion groups, you have meetings, just ways to organize a    
1:55:52    
project, organize a community, and that's kind of, you know, exploring that    
1:55:58    
sort of larger space of options. So like the hackathon is typically kind of focused on certain expectations, right?    
1:56:07    
You expect to produce something useful at the end or sometimes it's experiential and then like you have but    
1:56:15    
that's a public meeting. It's a type of public meeting where you want to bring people together. You have an agenda.    
1:56:21    
Maybe you want to do some accomplish something. And so I think thinking broadly about    
1:56:27    
that category of hackathon with all the baggage that it has and tech and all    
1:56:33    
that. It's I think it's interesting for what you want to do because it's like rethinking I guess what you want to do    
1:56:39    
is rethink like the conference or the mini conference or    
1:56:46    
whatever. And so I think thinking about in terms of okay, what is a hackathon    
1:56:51    
trying to do? What is a mini conference trying to do? What do I want to do? and    
1:56:56    
how do we get all that out into the into a really good event?    
1:57:01    
Um, I think that's that's the way to go. Um, yeah, and the    
1:57:06    
Yeah, exactly. And it's I I think it's it's a little bit of    
1:57:14    
Yeah, it's the mix between the the broader bigger ambitions and    
1:57:20    
sort of begging some of these breadcrumbs to to lead to lead there. Uh for sure.    
1:57:26    
So another thing um a very brief brief    
1:57:34    
shout out to the data and direction uh crew. I don't think they've ever really been able to make it to this meeting. Um    
1:57:42    
it's mostly been distributed. Everybody's kind of doing their own stuff, but I'm very heartened by what    
1:57:47    
they're doing. Um this is a super brief update. We have someone looking someone who is basically    
1:57:54    
learning NLP for the first time. Uh a computer engineering background but    
1:57:59    
learning NLP and learning how to basically just do some really simple uh    
1:58:04    
NLP to to sort of break down ethics policies and understand what's in them.    
1:58:10    
Uh which is a nice a very good starting point for things. Um I have someone looking at    
1:58:16    
um AI inequality in education and and the    
1:58:23    
pressure for different uh school like K through 12 schools uh to adopt    
1:58:29    
technology that they can't even administer or don't understand is one extreme case and how certain um    
1:58:37    
different different like socioeconomic status uh schools like being AI or    
1:58:44    
screen and free is presented more as this luxury you know this oh you don't have to you have time to live whereas    
1:58:51    
you know that that's just one angle but there's this this massive disparity along you know oh save save save money    
1:58:58    
by having more AI and customized turing and manage manage these 500 Chromebooks    
1:59:03    
and and you're trying to make a person an IT an IT administrator and a teacher    
1:59:09    
and so just the disparities that are happening there um no less the actual implications on on the GTP learning all    
1:59:16    
the content interesting    
1:59:22    
um and then a couple other things going on as well. Um I never put I never sent    
1:59:28    
that one medium thing to medium because one of our entrance was at the fact    
1:59:33    
conference and I just sent that to medium but it was she was cool that she was an event    
1:59:42    
one in Greece this year. Okay. Um so yeah it's been it's been really cool to see what what they're doing. Um    
1:59:51    
and I think if anything it's been very heartening to see    
1:59:57    
to go back to the conference thing momentarily seeing people seeing seeing the process of going through basically    
2:00:04    
very specific call for involvement for this project. Um it won't it won't be a    
2:00:10    
huge project. it won't be a huge um the more you know the more tailored the    
2:00:16    
focus for what I really want it to be the less uh widely appealing it will be that's    
2:00:21    
the nature of things so I'm I'm figuring that out but it is heartening to see for a small scale image like data    
2:00:28    
interaction right now um it's it's very heartening to see what    
2:00:34    
people are doing it so shout out to the data interaction cohort so far    
2:00:40    
that's Great. Thank you. Yeah, thank you for the update and it'd be great if some of them could attend some of our    
2:00:46    
meetings. Um I'd like to get like kind of to know a little bit more of what    
2:00:51    
they're doing. Um and definitely push that post to the medium because it would be great to see um some updates on what    
2:01:00    
they're doing. It sounds like you're really kind of hitting uh some pretty    
2:01:05    
good activities at this group. did the I don't think I'll do this. It It was one    
2:01:11    
of those things where I don't think I'll structure it the same way again. Uh but    
2:01:16    
I'm fortunate that the people that it worked out for has has done it's basically three totally different.    
2:01:22    
Um like it's not everybody's it's not we're working on diva worm or sustainability. It was it's basically    
2:01:29    
customized and a mix between like mentor and advising and this thing. Uh, but I'm    
2:01:35    
okay with that. Like for for this term, for this cohort, for this group of people, I'm okay with that. Um, but at    
2:01:43    
the same Oh, I should say this too. I forgot. But not only not only the um I'm    
2:01:49    
I haven't gotten feedback from this yet entirely, but the the education piece um    
2:01:55    
right now it's sort of just a series of you could say blog posts, but what I    
2:02:00    
actually considering doing with it if the person wants to go there is doing a more formal like white paper report on    
2:02:07    
this space because the person is very talented uh    
2:02:12    
academically knows how to write. Like they they're fine with writing, but they specifically    
2:02:18    
wanted to make some outputs for everyday folks. They're very science communication that's not as accessible.    
2:02:25    
But I'm like, geez, we're doing all we're finding citations. We're doing the stuff that they can do the writings. Why    
2:02:31    
don't we just it would almost be like double dipping already because we're doing we're doing the rigorous part of    
2:02:37    
it. So, so that's that's that's something I would um    
2:02:43    
that just came up this week and I kind of I'll I'll ask you more about that offline on Slack. Uh your opinions on    
2:02:48    
that. Uh but I would like them to BS be here or at least have some things that    
2:02:53    
are um you know more inter interactive and get    
2:03:00    
your your feedback and the lab's feedback on too. So absolutely. Okay.    
2:03:05    
Yeah, that's worth mentioning also that I'm this fall for fall term, I'm going    
2:03:10    
to be doing the Illinois model builder again. I did this last fall and I'm    
2:03:16    
going to do it this fall. And this is the sort of experiential course like you    
2:03:22    
have where the small cohort and they're all going to be working on projects and we have these topical lectures every    
2:03:29    
week. And so um and I want to apply this to like different schools. So like this    
2:03:35    
is Illinois model builder. I'd like to have other schools where I do model builder. It's a little bit different in    
2:03:42    
each case. But is is there a way that I could    
2:03:48    
like I I guess the course website or just a way that I can convey to somebody else who doesn't know at all like what    
2:03:55    
model builder is. Yeah, I'm going to be putting well I am putting up a website right now that's going to kind of cover I used to have it    
2:04:01    
like kind of in the private uh you know    
2:04:07    
content distribution system for the university but now I'm going to put it on a website. So, I'm getting that    
2:04:12    
website ready and I'll put it up. Uh, it's gonna be, you know, I'll put the public facing link when I have it done.    
2:04:20    
Okay. Okay. Yeah. Um, let's follow up on that later on, too. Yeah. So, yeah, that's great. Uh, so    
2:04:27    
yeah, thanks for the update, Jesse. Great. So, let me uh I wanted to mention one more thing before we go. This is the    
2:04:34    
last. I'm not going to get into this, but there was one more thing I wanted to talk about, which is this article in    
2:04:40    
science. This is by Melanie Mitchell. This is a sort of an opinion piece, expert voices    
2:04:48    
thing, and it says why AI chatbots lie to us. And so it's it's kind of talk    
2:04:54    
going over uh why AI chatbots make stuff up and    
2:05:00    
fabricate things and how you know they're misaligned behaviors that they    
2:05:07    
exhibit. And I'm not going to get into that this week, but I just wanted to mention it as a as a thing that exists    
2:05:13    
in the world. And we might get into this more next week, but I think that's very relevant to a lot of things we've been    
2:05:20    
talking about with AI models and of course um you know some of the critiques    
2:05:27    
of them. So okay. Um so that's and that's the last    
2:05:32    
thing I want to talk about. So yeah, I don't think we have anything else. We have anything else we want to say before    
2:05:38    
we go or anything to mention before we go? Um, you know, I might try to flesh out    
2:05:45    
some more things for next week's both the Google Summer probably say here. Uh, well, I mean, next next Saturday would    
2:05:52    
be the the summit. So, maybe we can try to do some kind of a check in or live from Lab Summit. Uh, it's orthogonal lab    
2:06:01    
Saturday morning, you know. Yeah, that would be good. I I definitely could do that. Um, I I'll try to figure    
2:06:08    
out the timing of the event. I don't quite know yet. We can do that. Um, and then    
2:06:15    
Friday, I'm going to try I'm going to aim to fit present. I have I have the    
2:06:21    
presentation um for the technical presentation thing. So maybe I can try to do that prior    
2:06:26    
something else Friday. I feel like I feel like I'm uh do some some to deliver    
2:06:32    
some things there. So that's my aim for next week. Okay, that sounds great.    
2:06:39    
All right, see you all. All right, thank you for attending. See you next week.    
2:06:44    
Take care. Bye. See you next week. Take care.    
    
