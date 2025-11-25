## Meeting Recording

[YouTube link](https://youtu.be/BAqgg3DI-tU)

## Mastodon thread

[link](https://neuromatch.social/@OREL/115517510697165299)

## Feature Videos

[Kingdom of Mind and the History of AGI](https://youtu.be/9N-662Hx43c)

[Baby Dragon Hatchlings and a Post-Transformer Model](https://youtu.be/j3XNpeRVj88)


## NOTES
AlphaEvolve paper: arXiv:2506.13131  (see November 22 meeting).

SF Startup culture -- how can we get ImageNet dataset from action? Embodiment training, self-supervised probabilities.

Big Action Data problem: embodiment sense and physical manipulation.

* Deep Mathematics approach -- hybrid systems to solve math problems.

* bring symbolic logic in LEAN4-type implementations.


Paul Middlebrooks: Brain-inspired Complexity.

* reading group based on Kraukauer's complexity papers.

Blog Post:

* early AI: symbolic vs. probabilistic AI.


Superintelligence (so powerful it could kill you) vs. smarter machine (track reasoning model, how many steps can you change before model collapses?)

*  "Mistake making" and "continual learning": shaped by order of successes and failures. Who is the better estimator?

* what is the right way to train a system to respond to accidental death?


How can an AI system probabilistically manage a problem?

* we can imagine things that are not possible, putting numbers on things -- we (humans) are bad at this.

* Foresight meeting -- will AI replace a neurosurgeon? Negotiate movement as a soft bodied embodiment problem.


Post-transformer architecture -- outside concern, more amenable to AI alignment solutions.

* what does transformer architecture represent? LLMs using hybrid models.

* is the Baby Dragon Hatchling paper brain-inspired, or something else? Developed by a logistics company (operations research).


NeuroAI --> Zador position paper, David Pfau (http://www.davidpfau.com/). Theorize on how the brain is organized? Or creating applictions?

* posit an architecture with consequences (models that stay competitive).

* continual learning ~ autonomous.


Curating papers, architectures. Hinton's capsules (when everything was GANs).

* utilizing symmetries in some fashion. Max Welling's group.

* intelligence problems that are sequences -- related problems improve in a theoretical manner. More than a sequence predictor (limitations).

* MAMBA -- post-tranformer architecture.


What are the metrics that provide confirmation of "bedrock algorithm" status?

* important dimensions -- how did transforer model become first-pass at providing an attention mechanism?


Human Flourishing floor of SF Tower. Computational Philosophy Salon --> Adam Safron.

* Flourishing Intelligence. Ruben Laukonnen.


School of Moral Ambition (Harvard).

* sequences -- tokens with probabilities --> DNA/RNA.

* sequence prediction with structure, thermodynamics, connections, underpinnings.

* Transformer --> 1) structural (complex tokens). 2) sequence prediction (what is a higher level of organization than a token).

* tokens have a Fourier output.


What is the NeuroAI program? Not optimizing metrics (getting small performance gains).

* Biological Underpinnings of Continual Learning (https://www.nature.com/articles/s42256-022-00452-0).


Jesse's updates and advances:

1) Plot Twisters -- grant to do a part of a game. Pattern Language (pedagogy/teaching/learning).

2) Adam Safron -- consciousness JClub.

3) ekkolapto --> Computational Philosophy club.

4) future center and curriculum design. Develop education for certain new fields.

5) princeton Envision -- Jesse will be a speaker @ event (now an AI tech, policy focus). jesse as Envision historian.


Data x Direction 2025 is wrapping up -- what is the follow-up?


## TRASNCRIPT
0:00   
Hello, Morgan. Good morning. Morning. How are you? Oh,   
0:08   
just uh just getting started here. Yeah, pre coffee. All right.   
0:16   
Uh so, welcome to the meeting. Um some interesting things for today. Uh   
0:24   
so la in the last week we had one meeting we had the uh diva worm meeting   
0:32   
and I think Morgan was there too. We covered some papers um   
0:39   
on trying to remember what the first paper was but the second paper was on   
0:45   
these uh uh wasps nest and how they're selforganized.   
0:52   
and a mathematical model to describe that. So, it was pretty good um stuff   
0:58   
that we t covered. I remember having to go through a lot of species names that I   
1:03   
wasn't familiar with. So, oh, I know what the paper was. It was the cellular   
1:09   
uh it was like a cellular zoo type paper where they characterized a bunch of um   
1:15   
single cell organisms and they were looking at the structure   
1:20   
of the single cell organisms and how they moved and you know describing that   
1:26   
movement in terms of how it's produced. So, it was a pretty good paper.   
1:32   
Um, and yeah, so check that out on our YouTube channel for D.VARM if you're   
1:38   
interested. Um, this week I also completed the videos for the active symposium. So,   
1:47   
that's next week. That's Wednesday through Friday. And you can either   
1:52   
register at the website. I I think I brought that link up last week where you can just catch   
1:59   
their live stream on YouTube which is um at their active inference channel on   
2:06   
YouTube. So in some laboratory news as I said before this is these are the   
2:13   
new videos that we have up for um our   
2:19   
for the uh active inference uh symposium. It's not showing the other   
2:25   
one, but this is the screenshot. So, we have the neurosimulation of spatial intelligence,   
2:30   
interdisciplinary underpinnings, and that's a nice overview of spatial   
2:36   
cognition and the different ways it's produced. Going over some of the details of   
2:43   
ecological psychology and spatial cognition, which is a different   
2:48   
view than the typical grid cell, place cell view.   
2:54   
and then talking about things like path integration and other types of mechanisms for   
3:00   
spatial intelligence, spatial intelligence and single cells etc etc.   
3:06   
So and then it talks a little bit more about how we might produce spatial cognition agents   
3:14   
and you know it's it's a nice talk. Um, and then I have this other one on   
3:20   
open-source sustainability. Kind of an overview of the project. Um, as we talked about last week, uh, Sara did an   
3:28   
overview of the project at the, uh, GOC mentor summit. So, I'm going to do an   
3:35   
hourlong version at the ACTM symposium.   
3:40   
So, those are available on our YouTube channel and then they'll also be featured in the symposium.   
3:48   
And then another piece of news, uh, Ankit Grover, this is from LinkedIn, he's starting a new position as student   
3:54   
researcher for machine learning for adversarial threat detection at Google. So, it looks like he's   
4:01   
coming along in his career. Yeah.   
4:09   
Did you want to say something, Morgan? No, I was just saying that's that's awesome. Oh,   
4:15   
okay. Yeah, I mean, you know, great great job. Yeah.   
4:23   
All right. So, that's laboratory news. Um, actually, I wanted to pull this up. This   
4:28   
is uh Josh Bongard, the talk I think that um I think it was Morgan who posted   
4:34   
this in the Slack. This is Echolapto um and they're introducing Josh Bongard   
4:41   
here. So this is just one of his computational granular metam materials talks called the tip in the iceberg why   
4:49   
embodiment matters. So you you can check that out on that YouTube channel   
4:59   
and then a few other things from following him from last time. This is uh   
5:05   
Kelsey High Tower. I think this is from um blue sky and he says kubernetes is a   
5:15   
sum of all shell scripts and practices system administrators cobble together   
5:20   
over time and presented as a single system behind a declarative set of APIs.   
5:26   
Now, we were talking last week about shell scripts and how shell scripting is   
5:32   
designed to sort of cut through some of that complexity. And this is kind of talking about   
5:38   
Kubernetes and how it's sort of the way it's built, the way kind of you have to access it is   
5:46   
sort of adding complexity to this. I cover this in my graduate uh level   
5:53   
project management course where you get all these different things that are going on in your project or in a like   
6:00   
maybe in an IT environment and you know you try to make things easier and a lot   
6:06   
of times in doing so you make things harder. So, Kubernetes is kind of, you know,   
6:12   
trying to make things easier for people um for cloud services and that, but it   
6:17   
actually ends up being pretty pretty hard to, you know, pretty complex.   
6:25   
So, that was kind of interesting. Um, and then this is another interesting thing I think also from Blue Sky. This   
6:31   
is complexity cat. Um, and this is an interesting   
6:37   
biblometric kind of I don't know if anyone's followed up on this, but it's looking at   
6:45   
the number of publications for autopoesis and the number of publications for M   
6:51   
comma R systems. So MR systems were something that was proposed by Robert   
6:57   
Rosen way back like in the 1950s and they're these uh systems that   
7:04   
describe um you know physiologies interested in systems physiology   
7:10   
and interested in these different types of uh complimentary systems or systems of   
7:17   
mapping. Um he did a lot of things with relational biology. So they're, you know, different sets that are related   
7:24   
together and they form this system and it's, you know, it's kind of one of   
7:30   
those areas. It's kind of a niche area. Um, and I I this was this is from data   
7:36   
from the Web of Science. So I'm not sure exactly how they got these search results, but they basically are so the   
7:43   
the number of publications for autopoesis goes up over time. Of course, autopoesis   
7:49   
is something that was developed by Matarana and Varela in the 70s.   
7:55   
And you can see that starts at 1990 and it goes up, you know, from about 5 to   
8:02   
about 20 until about maybe 2004 and then it starts to go up in in 2011.   
8:11   
It goes up to like 45 and this ends at like 2011 or something   
8:16   
like that. So this is um you know there's there's probably more to be said   
8:22   
here but I don't have the methodology so I couldn't reproduce it but it's   
8:28   
interesting uh MR systems of course this line is flat until we get to like 2004   
8:34   
2003 and then you get these publications. So I was interested in this graph um and   
8:41   
I looked into the MR systems uh references and I found that you know   
8:47   
MR systems kind of were proposed in the 50s. Uh there are a couple of publications   
8:54   
in the 50s and 60s and then the last one is like 1971   
8:59   
and then there isn't a publication from 1971 until 2003. So there's this huge gap in   
9:07   
the practice of you know talking about these kind of systems and then after   
9:12   
2003 you get this growth in people using that model or that type of methodology   
9:19   
for looking at relational systems and so there have been a number of publications   
9:25   
since then uh I think the one in 2003 was actually autopolesis and MR systems   
9:32   
so that you know kind of combined the two and in MR systems have been used in   
9:37   
different biological settings. Uh and the papers themselves range from   
9:43   
methodology papers and putting you know that type of methodology into code to   
9:48   
applying them to biological systems. So it's really kind of an interesting um   
9:56   
mix of things going on there in that literature. Um definitely the you know   
10:01   
MR systems are pretty interesting but I just thought that was interesting be you know given our discussions about   
10:08   
cybernetics and autooesis and the systems biology. Okay. Uh so let me uh   
10:16   
start off with an article here. You know we've been following this reading group. It's from Paul Middlebrooks.   
10:21   
Yeah. Yeah. Uh Paul Middlebrooks. Uh I think he calls it   
10:28   
brain inspired complexity complexity reading group.   
10:34   
Okay. Yeah, that sounds about right. Yeah. So that's brain inspired complexity reading group.   
10:40   
Yeah. And they've been doing all these classic papers and we've been following along and uh one of So the latest paper   
10:48   
I think is coming up. Yeah, it's Minsky. The the um   
10:56   
uh it's David Crackour's um   
11:04   
like like complexity papers. Okay. Yeah. You know, like like that's the that's   
11:11   
the reading list. Yeah. Is is comes from Crackour's um   
11:18   
compilation, right? So that's that's Hence the name.   
11:24   
Yeah. Yeah. Yeah. Um and so yeah, the next paper is on minsky paper from like the 60s.   
11:32   
So this is uh this is one of the participants in the reading group, Darren L. And he has this blog uh and he   
11:41   
posted this blog post. I wanted to go over it a little bit just to see what his point of view is because he seems   
11:47   
like he brings up some interesting comments in the reading group. So,   
11:54   
okay. So, this is uh kingdom of mind path to   
11:59   
AGI ends in a cornfield. Um and so, um he starts off in 1956,   
12:07   
the pioneers of artificial intelligence declared machines would be able to use language, form abstract concepts, solve   
12:15   
the kinds of problems reserved for humans. And they thought then and they   
12:20   
thought significant progress could be made in two months by 10 handpicked experts.   
12:26   
That's that was off base. Uh two of these handpicked experts, John McCarthy   
12:31   
and Morgan Marvin Minsky went on to initiate an artificial intelligence lab at MIT. They were among the first but   
12:39   
not the last scientists to grossly underestimate the effort involved and to provide a hilarious prediction set of   
12:46   
predictions of sentient machines just around the corner. So yeah, the first of   
12:52   
course goi or the first attempted AI were sort of thinking in terms of expert   
12:57   
systems like if you could capture the expertise and you know just kind of regurgitate it   
13:03   
would work pretty well you know so um that was I mean they weren't wrong about   
13:10   
expertise you do need expertise in intelligence or in artificial intelligence but the way that they   
13:16   
approached it wasn't particularly fruitful. And so then they started their labs and   
13:22   
started to do research on symbolic AI and things like that.   
13:28   
By 195758 the seeds for the greatest division in AI had already been sewn. So this is   
13:34   
symbolic AI is exemplified by new and Simon's general problem solver which was   
13:40   
in 1957 and probabilistic AI is exemplified by   
13:45   
papers perceptrons 1958 later marketed as artificial neural networks. By the   
13:52   
1980s the symbolic AI movement had stalled and after a very late start   
13:57   
probabilistic AI had also stalled. over a half century later neither approach   
14:02   
has even produ provided definitions of for their highest goals uh intelligence and consciousness. So   
14:10   
this is kind of um you know these are the two kind of components of goi as it   
14:17   
kind of came to be known and this was kind of at the end of the 50s when symbolic AI and probabilistic AI were   
14:25   
kind of formed and so um and so basically there there was a lack   
14:31   
of definitions here where it's hard to know kind of what exactly they're trying   
14:37   
to accomplish if they're overlappinging domains or if they're separate domains.   
14:42   
So he says by the end of the article I will tackle defining both. So he starts with the Turing test which   
14:49   
is that one of the earliest most notable predictions about the eventual humanlike abilities of machines comes from Alan   
14:57   
Turing in 1950. So this is the quote here. I believe that at the end of the century the   
15:04   
general educated opinion will have altered so much that one will be able to speak a machine's thinking without   
15:11   
expecting to be contradicted. So this is uh you know Turing made some   
15:16   
predictions about the year 2001 and these predictions were comparatively   
15:21   
modest. The term AI had not yet been coined and now it conjecture is merely   
15:27   
about machines thinking 50 years in the future. This is a far cry from predicting a   
15:33   
conscious malevolent artificial super intelligence or ASI. And we'll get to   
15:38   
that prediction soon enough. Uh Turing's benchmark of course was the   
15:45   
imitation game. In this parlor type game, a man and woman would be segregated from an interrogator who   
15:51   
submits written questions to them. The goal of the woman is to be perceived as a woman. The goal of the man is to   
15:57   
submit answers to the interrogator such that he would be fooled into thinking the man was a woman. Uh so Turing's   
16:05   
imitation game is can a man trick another man into thinking he is a woman?   
16:10   
Um and then the language in the paper is unambiguously gender specific. So um   
16:16   
Turing then proposes that the role of the trickster can be taken by a machine which attempts to imitate the man if the   
16:24   
machine can fool the interrogator 30% of the time. The point about thinking would be considered proven.   
16:31   
And so u this was in 2001 a chatbot named Eugene Gman supposedly beat the   
16:38   
touring test by pretending to be a 13-year-old boy from Ukraine. there were mitigating factors to influence this   
16:45   
positive result but the year 2001 is notable and then by 2025   
16:52   
uh GPT 4.5 was being identified as human   
16:57   
73% of the time which is more often than actual human counterparts in randomized   
17:04   
control tests. So, uh, Eliza was invented in 1966, was   
17:10   
included in the contest and scored 23%. Worse than the humans, but Eliza   
17:16   
outperformed GPT40's 21% score. So, Elisa, which is a was at   
17:24   
the time, which is this year, um, uh, almost a 50-year-old chatbot, was able   
17:31   
to do better than, uh, GPT40. So it's interesting that you know   
17:39   
we have this older model that's actually doing pretty well on that. I think it's   
17:44   
important to note again that Turring is proposing a test of thinking and not intelligence or consciousness.   
17:51   
The test is a purely language-based performance. It's also an imitation game   
17:56   
and winning may not mean what some might want it to mean. Over text fooling   
18:02   
another man that you are a woman does not make you a woman. Over text fooling human intelligence does not make the   
18:09   
computer intelligent. Then 2001 a bolder prediction. So   
18:14   
Stanley Kubri the director of 2001 a space odyssey was fanatic about   
18:20   
scientific accuracy for his 1968 film and hired many consultants. One of these   
18:26   
was Marvin Minsky from the MIT AI lab. You might expect Hell 9000, a sentient   
18:32   
AI that becomes paranoid and murders the crew, was Minsk's contribution. It   
18:38   
wasn't. Instead, Kubric asked, "By 2001, you expect that computers will be able   
18:44   
to speak coherently." To this, Minsky replied, "By that time, their voices will be very good and   
18:49   
nicely articulated, but I doubt they'll understand what they are saying." This   
18:55   
turned out to be precient and redemptive of the exuberance characteristic of a   
19:00   
decade before, but it didn't deter Kubri's vision for Hal. Um, what Minsky did contribute to the   
19:08   
final movie was inspiration for the design of the EVA pod. This is uh the   
19:14   
EVA pod here. Uh, right here we see the foundational split in AI and Marvin   
19:20   
Minsky is central to it. Uh, so this is about the AI winter. Uh,   
19:29   
the first AI winter, I believe. I'm sorry, Dave. I I'm afraid I can't fund that. So, in the 1960s, Marvin began   
19:36   
designing and programming the Minsky robotic arm to build things of blocks, a   
19:42   
skilled with which most children are adept. These challenges colored Minsky's work for the next 60 years. By 1986, he   
19:50   
wrote Society of Mind, which extensively uses World of Blocks as an illustrative.   
19:55   
By 2011, he conducted a 26-hour MIT graduate course surveying the state of   
20:01   
artificial intelligence. Robotics examples are still front and center. And in the concluding lecture,   
20:07   
he challenges the grad students to think about how to make machines smarter.   
20:13   
As a former president of the American Association for Artificial Intelligence,   
20:18   
it's telling that Professor Minsky asks about smarter machines like the EVA pod   
20:25   
uh and not about emergent super intelligence like HAL 9000. So, he's   
20:30   
kind of more on the in the camp of sort of smarter machines rather than super intelligence.   
20:37   
During the lectures, Minsky expresses disdain and frustration with probabilistic approaches to AI.   
20:43   
He also warns his students against using neuroscience as a guide to design. That's interesting. When asked about the   
20:50   
lack of progress in AI, he says it stalled in the 80s because all the funding has gone into artificial neural   
20:56   
networks, leaving only 12 people worldwide to do the required work of deciphering common sense reasoning. So   
21:04   
way he has states that this the uh the AI winter one of the AI winters was   
21:10   
because you know there was this funding imperative for things that were not what he   
21:17   
considered to be AI. Uh then there's more of X paradox. Um   
21:23   
and so there's a quote from society of mind. In attempting to make our robot work, we found that many everyday   
21:29   
problems were much more complicated than the sorts of problems, puzzles, and games adults consider hard. It was this   
21:37   
body of experience more than anything we learned about psychology that led us to many ideas about societies of mind.   
21:45   
Uh so that's the quote from society of mind. So, aside from monetary challenges, one of the biggest   
21:52   
impediments to advancing artificial intelligence is labeled Moravec's paradox. It's named for Hans Moravec,   
21:59   
who wrote a 40page essay on the subject in 1976. A phrase capturing the essence of the   
22:05   
paradox was popularized by Steven Pinker. The main lesson of 35 years of AI research is that the hard problems   
22:13   
are easy and the easy problems are hard. Moravec's raw power and intelligence   
22:18   
essay asserts that the division between the easy things and the hard things is   
22:23   
based on the timeline of evolution. Things that are hard for a computer are essential to living organisms and so   
22:31   
natural selection has had millions of years to work out solutions. These solutions are instinctual and seem seem   
22:38   
free or easy. The seemingly hard things are recent man-made problems and don't   
22:44   
have biologically prepared solutions. So they seem hard by comparison but really   
22:49   
are not. So catching a ball is easy for a child, a monkey or a dog, but playing   
22:56   
chess is not. Uh the easy task is handled by highly evolved sensory and motor portions of the brain. The hard   
23:04   
task requires reasoning and awareness. Like Minsky, Moravec believes that   
23:09   
creating a path to intelligent machines is an engineering problem and can be solved by incremental improvements and   
23:16   
occasional insights into subpros. These subpros in the parliament of society of mind are called agents. And   
23:24   
Minsky writes, you can build a mind from many of these little parts. When we join these agents and societies in certain   
23:32   
very special ways, this leads to true intelligence. Okay. So that and then the quote from   
23:38   
Marvin Minsky again, it's mainly when our other systems start to fail that we engage the special agencies involved   
23:45   
with what we call consciousness. So this is uh that's kind of you know an   
23:51   
interesting take on it given some of the recent uh discussions on this. So then   
23:58   
he talks about the origins of consciousness and the breakdown of the bicamal mind. Above is the title of a   
24:04   
1976 popular science book by Julian James. I add breakdown to the question   
24:10   
of consciousness as the pinnacle achievement of an intelligent mind. And so a quote from Julian James that there   
24:18   
can be no progress in the science of consciousness until careful distinctions have been made between what is   
24:24   
introspectable and all hosts of other neural abilities we have come to call cognition. Consciousness is not the same   
24:30   
as cognition and should be sharply distinguished from it. Jean's position is that human consciousness is unique, a   
24:38   
byproduct of language and has manifested only in the last few thousand years.   
24:43   
That's fun, but I'm not buying into it. What is more interesting though is James than necessarily posits an older   
24:50   
non-concious human mentality prevalent for the vast portion of history   
24:55   
um which we will revisit shortly. And then um I guess he has another post   
25:03   
here where he provides a working definition of intelligence plus revealing how consciousness is actually   
25:09   
an illusion. I don't know if Morgan had any comments or questions about that. I mean it's it's um some interesting   
25:17   
backstory about um you know Minsk's work with Cooper.   
25:23   
Yeah. Yeah. I mean uh interesting things um   
25:31   
and um yeah it's good to know that the the   
25:39   
complaint about um funding allocation is is a perennial one. Yeah,   
25:47   
I I I don't know if I mentioned this, but um   
25:57   
I'm trying to think who who posted this, but um   
26:03   
some some neuro imaging researcher posted this thing from um like seventh   
26:08   
or eighth century Syria or um Iraq where the astronomers were   
26:17   
complaining uh about their their teaching requirements. Oh yeah. Saying that they they they couldn't do   
26:24   
they couldn't do research because of of their burdensome teaching requirements. Right. Right.   
26:30   
Um yeah. Yeah. Anyway, uh yeah, but uh yeah, still still, you know, still   
26:39   
amazing what they what they did and um you know, some of some of their   
26:46   
some of their guesses about about the future weren't um weren't half wrong,   
26:52   
right? you know, um it's it's nice to know that they thought   
26:58   
or that he he predicted that they would speak but they wouldn't understand their speech,   
27:04   
right? I you know feel like that's that's sort   
27:10   
of sort of even 2025. Yeah.   
27:15   
Well, especially 2025, right? Like we have machines that are speaking and   
27:21   
like people are like well is that a real person or is that should I listen to that thing that speech or should I like   
27:27   
just ignore it safely? Yeah. Yeah.   
27:33   
So yeah he brings up the well the two distinctions of symbolic versus probabilistic. It's nice to know that   
27:40   
that distinction is was uh deeply embedded in goi that you had these   
27:45   
models these symbolic models of course that were trying to achieve different things from the probabilistic models you   
27:53   
know probabilistic models are of course what are sort of predominant today but   
27:59   
the symbolic models you know you think well maybe we've learned how to do this better with probabilistic models but it   
28:07   
seems like the symbolic models are doing something else and it you know we don't   
28:13   
we didn't necessarily get the same developmental trajectory of those types of models.   
28:18   
So you know um yeah that's and then this idea of super intelligence versus smarter   
28:25   
machines. So if something is super intelligent it's like how and then a smarter machine   
28:32   
is um you know something else. So, I don't   
28:38   
know. I I've not followed the super intelligence debate or the super intelligence literature, but I I'm   
28:45   
curious about that distinction as well. Yeah. I mean, you know, it's one of   
28:52   
these things. Is isn't that is that Bolstrom's term? I mean,   
28:58   
yeah, I think so. I've heard people throwing it. Yeah. you know, and   
29:09   
the Yeah. So, I I mean, my my fear with it is that it's too caught up in the   
29:15   
kind of AI dumerism. Yeah. Which, you know, I I forget who   
29:22   
was talking about this. Um maybe this was Emily um Emily Bender.   
29:33   
But you know that that AI dumerism is this is a weird   
29:40   
sort of um   
29:45   
is kind of like this um   
29:50   
it's that it's related to something that Corey Doctor talks about which is that   
29:57   
these companies want us to think that they're capable of   
30:03   
superhero like abilities, you know, and and and that   
30:10   
like like it's it's actually part of the same   
30:16   
marketing effort. Well, no, no. Um, I'm trying to trying to think of the kind of   
30:21   
like most um cynical way of seeing it where it's like it's actually a part of   
30:27   
the same um sales pitch   
30:33   
that like like you know that that we're working on something that so powerful it   
30:41   
could kill you. you know, like um   
30:47   
sorry, it just makes me think of um the movie Scrooged um with Bill Murray where   
30:54   
he's got the he he wants the he wants the the ad for the um the upcoming   
31:03   
Christmas Christmas Carol um preview to be so scary that it's that it kills   
31:10   
people, you know, like like this is th you know that this is   
31:16   
this is um you know he's like I want you to be I want you to be afraid not to   
31:22   
watch it you know like and and um anyway but the point the   
31:29   
point being that like you know that that back to this kind of like they've got a trillion dollar   
31:35   
reason for for misleading you. Um and   
31:41   
you you know whereas like the more interesting thing that um   
31:47   
I think somebody was talking about was just again   
31:52   
something that Gary Marcus brought up at the h this was like a couple years ago   
31:58   
where he did a conference together with or like a workshop together with Emily   
32:04   
Mender where they just invited linguists to   
32:09   
talk about the interesting ways in which the language models failed.   
32:16   
I don't know if you remember that meeting. I'm trying to think what the what they called it, but but somebody   
32:22   
somebody talking about um recently this this week, you know, like because of   
32:29   
course, you know, um like still a hundred papers will come across my feed   
32:35   
somehow in terms of of you know, a AGI or something like that,   
32:42   
reasoning models, right? and and they were just talking about how I think,   
32:48   
you know, how interesting it is to actually track reasoning models in terms   
32:55   
of how many um   
33:01   
how many kind of linked uh   
33:07   
not thoughts, but what do you what would you call the um how many steps can you pain before you   
33:15   
get a a real collapse in the model performance   
33:20   
and and finding that that model collapse was   
33:25   
is always like um super steep.   
33:32   
So, so I it it it's it's it's   
33:37   
there's something something strangely catastrophic   
33:42   
about about kind of like the last step.   
33:48   
Um, which which again just points to this like I mean I I I don't know if   
33:53   
these are you know silly character like these seem like much more interesting   
33:59   
points to be playing with in in the   
34:05   
um evaluation and discussion whereas like super intelligence gets   
34:14   
so easy to fall into this kind of like I can imagine ine this. Oh yeah. Okay.   
34:20   
Okay. Um it was from the foresight meeting this   
34:26   
week. So So the foresight meeting was um   
34:33   
a neurosurgeon speaking about will AI ever replace a   
34:39   
neurosurgeon. So   
34:44   
perhaps not surprisingly, he was he was on the uh no or no no time soon.   
34:52   
But it was really interesting discussion of what both what is involved in neurosurgery   
35:00   
and and how um certainly for AI that it's it's a   
35:09   
it's a strange it's a difficult marriage of both um   
35:16   
AI ethics in terms of um so he he is   
35:22   
giving you a scenario where there's a piece of tumor that's left on a um on a   
35:28   
blood vein or blood blood vessel. So he's talking about   
35:35   
the the the scenarios that you have in terms of wait, you know, if you if you leave   
35:42   
any of the tumor, obviously you could be right back doing doing what is a dangerous surgery every time you do the   
35:48   
surgery, even with things kind of out of your control in terms of infection, in terms   
35:54   
of of complications, right? um together with   
36:01   
this this you know kind of minuscule amount of tissue that's left on a on a   
36:08   
blood vessel and the the the difficulty of the actual   
36:16   
physical removal as being an incredibly delicate   
36:21   
um uh soft body complex problem   
36:28   
where you're you both how you remove the tumor piece as well as like how to   
36:36   
negotiate with its connection to the the vein itself   
36:43   
being a remarkably difficult soft body embodiment understanding problem.   
36:51   
But but that's something that embodied agents understand   
36:59   
much better than we currently know how to um   
37:05   
teach robots. And   
37:12   
you know he his his point when when people were were saying like well isn't   
37:18   
it possible with you know if I do this and I have this data set and this data set and he's like well I think what   
37:24   
you're what you're doing is you're you're making an argument based on can I imagine that you know and and he's like   
37:33   
I can imagine that.   
37:38   
Um uh and you know like it it almost comes   
37:45   
back to a similar kind of human problem where it's just like um we we have this   
37:51   
ability to imagine things that actually aren't possible and and you know so now our our problem   
37:59   
is distinguishing those and and trying trying to quantify those   
38:08   
which seemed to me to be an actually interesting way to to to talk about kind of AI dumerism, which is that that we   
38:16   
have this ability to imagine it. Um um but but very, you know, like like   
38:27   
putting putting numbers on these things um is is   
38:34   
something that we're actually really bad at. Um   
38:40   
and he had some it it was a wonderful like like you know   
38:48   
it was really nice because it was like someone whose talk   
38:55   
suggested that it was going to be a kind of technical um   
39:04   
a technical discussion. Um but it was actually a remarkably   
39:10   
human. uh he he he actually brought an incredible   
39:16   
amount of humanity to the problem a a and said it as a very difficult like   
39:23   
it wasn't kind of like he wasn't setting a kind of trolley problem ethical   
39:28   
dilemma but um   
39:35   
but was was in fact really giving you um a great   
39:42   
understanding of how how difficult it would be to truly quantify so that uh an   
39:51   
AI system would be able to probabilistically manage the problem.   
40:01   
And you know like like again like it it it wasn't that he   
40:08   
felt that this wouldn't be you know some sometime possible in the   
40:16   
future. Um but but I think he was he was giving   
40:22   
great grounds for like why this is not possible in the short term   
40:28   
as well as talking about you know critical mistakes that he made   
40:35   
as a doctor and and you know sharing those with us   
40:42   
and sharing the   
40:48   
um after you make one of those mistakes, how does that color   
40:55   
your next crisis? So they talked about kind of like how   
41:04   
your continual learning is shaped by your   
41:10   
um potentially by you know the the the order of your   
41:17   
um successes and failures in a in a in an interesting like you know he he   
41:24   
talking a little bit about you know judges being more likely to to give guilty   
41:30   
verdicts when they're hungry. Problem, too. you know. Anyway,   
41:38   
it um it it was uh I I'll see if they've   
41:44   
if they've got a link to that um later because uh um   
41:51   
yeah, you know, obvious obviously part of what he's talking about is the   
41:59   
is the um the big action data set problem. where   
42:06   
it's just like like this is this is something new that is needed to to really kind of give systems of intuitive   
42:15   
sense of embodiment and physical manipulation.   
42:21   
But but I I think he got I think he touched on something   
42:27   
um uh uh something actually more human than just   
42:34   
this dilemma of he he he he wasn't trying to frame it as a you know would   
42:39   
you want an AI to kill you or would you want a doctor to kill you?   
42:46   
Excuse me. It was um   
42:54   
it was really about how to what is the right way to to train the system   
43:05   
to respond to these um to to   
43:14   
yeah to to these say say um   
43:20   
to to killing a patient like like what what what would be the right way to to   
43:27   
have the system respond? Right? So should it be less likely to   
43:34   
engage in that task or more likely and and on what basis would you properly   
43:41   
make that? I'll try and find it.   
43:49   
Yeah. So that's really interesting stuff. Um, yeah, I'd be interested in the big action data set problem as well.   
43:58   
Well, the, you know, I mean, this is this is what is driving um   
44:06   
this is the the new thing in Silicon Valley.   
44:12   
Oh, really? Okay. Is is is you know and and so so you see you know this is like   
44:20   
I've got people front or not it's not Frontier to Tower sharing this um you know people in these   
44:29   
kind of um startup founder groups sharing sharing links to   
44:36   
you know all sorts of of kind of like very specific mechanical Turk uh um   
44:45   
operations where they're paying people in countries where you can pay trained people,   
44:55   
you know, at scale to basically be folding clothes with GoPros on, you   
45:02   
know. Oh, yeah. Right. To get the data. Yeah. Visual data. a   
45:07   
and and you know like like again I'm I it's it's it's   
45:13   
interesting to kind of embed yourself in San Francisco startup culture where   
45:22   
um you know so so this is this is what big   
45:28   
companies like physical intelligence are are trying to do and and and that's how   
45:33   
they're trying to do it right like like how can we how can we get the the   
45:39   
imageet like data set that allows us to to to train this right   
45:45   
but somebody talking um yesterday it's a neurocher saying like um oh yeah you know all   
45:53   
these um all these big hedge funds and you know Chinese banks   
46:00   
looking for nerotic investment are are interested in EG again um because um   
46:07   
somebody's paid for kind of like a 100,000 hours of EEG data from or you   
46:15   
know like like um they're they're getting again like new   
46:22   
types of data at scale where they're literally paying for them,   
46:28   
you know, um and trying trying to solve the problem by by   
46:35   
collecting the data, you know, e even though none of these are actually at like all extent text level that that the   
46:44   
at large language models have have benefited from. But um but yeah, but this this is the   
46:51   
big data um I mean sorry big action okay push that's that's going on right now.   
46:58   
Oh, okay. So this is something that they're just kind of trying to get uh training   
47:04   
data basically for embodiment or for action. Yeah. But but but with this, you know,   
47:11   
but using these AI valuations that they have where it's just like, hey, you   
47:17   
know, like you can actually raise, you know, a billion dollars. Um and and   
47:26   
be spending that to just essentially buy data and compute, you know, uh um with   
47:34   
this this uh hypothesized, you know, insight that   
47:41   
will come from the um you know, just self-supervised learning on on enough   
47:48   
data. Yeah. Yeah.   
47:54   
And it's not. Yeah. And this is of course a distinction between probabilistic and symbolic   
48:00   
uh training. We're putting all our eggs in probabilistic   
48:06   
actually extracting probabilities from images. Yeah. Well,   
48:13   
you know, so so yeah, how do you how you bring that into the real world is is   
48:18   
interesting. But I think I think you know it's always good to follow the um   
48:28   
the deep deep mathematics if you will in terms of um like deep minds latest paper   
48:36   
on its um its approaches to extending mathematics   
48:41   
right because it's like like there you have a combination of of   
48:49   
I It's it's it's hybrid systems to solve math problems, right?   
48:55   
So So certainly one of the outputs is like one of the outputs you're going to get   
49:02   
is a um a formal lean implementation,   
49:08   
right? Like lean for the the the package. um   
49:14   
you you'll get a a a theorem prover output,   
49:20   
right? So so to to some extent that that is the new this is this is one way in   
49:26   
which you bring symbolic logic into   
49:31   
um into these systems. And even even if um   
49:38   
they're using a combination of of other kinds of techniques to to   
49:45   
actually generate that lean program. Um so it like I I haven't um dug into it.   
49:54   
It was just like yesterday that they had the paper but but they're like they're using alpha evolve. They're using alpha,   
50:01   
you know, like they're using multiple alphas in terms of techniques to to um extend   
50:10   
new mathematics and or sol solving excellent problems and and extending   
50:17   
mathematical fields. Well, it's interesting stuff. Yeah. Um   
50:23   
glad to see that like um all the new things kind of emerging   
50:30   
right now. Um yeah. Yeah. Yeah.   
50:35   
Okay. Why don't we move on to we had a couple things in the Slack. This is one of the things I think this was something   
50:42   
Morgan posted on from the archive on uh this idea of the dragon hatchling. the   
50:50   
missing link between the transformer and models of the brain.   
50:55   
And so, you know, a couple weeks ago, we talked about this sort of link uh   
51:00   
between like these machine learning models and models of the brain and some   
51:07   
of these things and this got posted. Um, so the dragon hatchling is kind of a   
51:13   
provocative title. Um, but what do they mean by that?   
51:18   
So, uh, let's see. This is from, um, these people are from Pathway, which I   
51:23   
guess is a startup in Palo Alto. Um, I'm not familiar with it, but you know,   
51:30   
that's kind of where they're coming from is from a sort of maybe a tech startup   
51:35   
standpoint. Um so the relationship between computing systems and the brain has served as   
51:42   
motivation for pioneering theoreticians such as John vonoyman and Alan Turring.   
51:49   
Uniform scale-free biological networks such as the brain have powerful   
51:55   
properties including generalizing over time which is the main barrier for   
52:00   
machine learning on the path to universal reasoning models. I'm wondering why they're using uniform and   
52:06   
scale free as descriptors of the brain. Maybe we get to that later, but we'll   
52:11   
see. Uh, we introduced the dragon hatchling or BDH. Um, I guess maybe brain dragon   
52:19   
hatchling. I don't know why they put the B in there, but a new large language model architecture based on a scale-free   
52:26   
biologically inspired network of n locally interacting neuron particles. So   
52:33   
this is a a network model. It's scale-free. Um we have these particle systems that   
52:40   
are locally interacting. BDH couples strong theoretical foundations and inherently interpability   
52:48   
or inherent interpability without sacrificing transformer-like performance.   
52:54   
BDH is a practical performance state-of-the-art attentionbased statesbased sequence learning architecture. So this is a state space   
53:02   
sequence learning is the key here. In addition to being a graph model, BDH   
53:08   
admits a GPU friendly formulation. It exhibits transformer-l like scaling   
53:13   
laws. So we find empirically that BDH rivals GPT2 architecture transformer   
53:19   
performance on language and translation tasks at the same number of parameters   
53:25   
10 billion 10 million to 1 billion for the same training data. So 10 to the 6th   
53:31   
or or 10 the 7th to 10 to the 9th parameters EDH provides theoretical foundations for   
53:38   
understanding model behavior in the limit of large size and reasoning time.   
53:43   
Our results formalized as a chain of reductions of expressiveness in the framework of computational complexity   
53:49   
theory and distributed computing and combined with findings on the BD on   
53:54   
the BDH model show a macro to micro correspondence of function between the   
54:00   
general attention mechanisms in state-of-the-art language models and   
54:05   
attention mechanisms observed in the brain. So they're actually able to get this sort of correspondence of function   
54:12   
between the two. I don't exactly know how they determine that but these attention mechanisms formally converge   
54:19   
as close form local graph dynamics at neurons and synapses the equations of   
54:24   
reasoning. So they basically build and this is something that um   
54:31   
people this this is kind of an emerging theme in the literature where you're   
54:36   
using these closed and open graphs. So like you know you'll have a graph where   
54:42   
it's connected and um that's a closed graph and then an open graph is where   
54:49   
you need to insert a node to get a certain relationship. So you know you   
54:54   
can use closed form graphs to describe things. You can also use open uh open   
55:01   
form graphs to describe things. And you know it's basically if you have the the   
55:07   
graph itself is the representation that you have or the data that you have. If you can describe what you need with the   
55:14   
data that you have that's great. It's a closed form graph. if you need additional data or if you you know if   
55:21   
the graph needs to add a node to get that kind of description then that's an open formed graph. Um   
55:29   
so I kind of go over that in this spatial intelligence talk towards the end and looking at the um the work of   
55:38   
saffron at all on um you know they're doing some things with with open   
55:44   
formagraphs and you know kind of go through that a little bit. So that's that's kind of an   
55:51   
interesting theme to follow up on. Um, so it's interesting. They call neurons   
55:58   
and synapses the equations of reasoning, or at least these graph representations of neurons and synapses, the equations   
56:05   
of reasoning. They put it in quotes because that's always good. Um, BDH can   
56:10   
be represented as a brain model. It contains n neurons organized as excitatory circuits and an inhibitory   
56:18   
circuit with integrating fire thresholding of input signals at neurons. working memory of BDH during inference   
56:24   
entirely relies on synaptic plasticity with heavy and learning using spiking   
56:31   
neurons at potentiation scales of minutes for the brain up to hundreds of   
56:36   
tokens. We confirm empirically that specific individual synapses strengthen   
56:41   
connection whenever BDH hears or reasons about a specific concept while   
56:47   
processing language inputs. The neuron interaction network of BDH is a graph of   
56:52   
high modularity with heavy tail degree distribution. Uh the BDH model is biologically   
56:58   
plausible explaining one possible mechanism which human neurons could be used to achieve speech.   
57:05   
Uh then BDH is designed for interpability. Activation vectors of BDH are sparse and   
57:11   
positive. We demonstrate monossemantically in BDH and language tasks including representation of comp   
57:18   
concept abstractions which happens even for small models below 100 u uh below   
57:25   
the 100 million parameter scale. Interperability of state which goes beyond interpability of neurons and   
57:32   
model parameters is an inherent feature of this architecture. So we believe BDH opens the door to a   
57:39   
new theory of thermodynamic limit behavior for language and reasoning models with the ultimate goal of   
57:45   
probably approximate correct or pack-like bounds for generalization of reasoning over time. So they have a   
57:52   
technical blog entry and a GitHub repository for this and this is um this   
58:00   
is their company pathway. So you know the abstract kind of reads a   
58:07   
little bit like uh marketing materials but also has some very nice things in it   
58:13   
um these promising things. So this is the you know they have a table of contents the introduction   
58:21   
uh and then BDH a language model architecture given by local distributed graph dynamics. Uh this is exciting to   
58:28   
me because they're actually using um some elements of network theory here   
58:34   
to describe some of the things that are going on in this. So you know we're talking about different graph formalisms   
58:41   
first of all and you know we're using these graph-based language models. We're also   
58:48   
defining uh this approach BDH as a local edge reweing process. These are the what   
58:54   
they call the equations of reasoning. interpretation of attention as a microinductive bias of reasoning.   
59:02   
Interpretation of BDH as an oscillator network toy model and then expressing BDH using brain models. And then so   
59:10   
that's kind of maybe the heart of the paper that I'm interested in personally. Um there's also BDHGPU   
59:17   
a tensor friendly version of the BDH architecture. So they they about implementing it on a GPU.   
59:24   
Um actually they have the state space system definition here the local   
59:30   
interacting particle system and then preserving parameter and state size.   
59:36   
Then they have some uh section on scaling laws. Uh the emergence of modularity and scale   
59:43   
free structure u linear attention sparse positive attention and monossemanticity.   
59:50   
uh then playing with the hatchling where they're doing model merging and training   
59:55   
without back propagation through time. So yeah then let me go down and see if   
1:00:01   
they have some figures. So yeah this just shows like tensorbased models where   
1:00:07   
you have centralized computing versus local graph models or distributed computing on graphs. So this shows the   
1:00:14   
attention mechanism, local dynamics and this feed forward network. Um so the   
1:00:21   
tensorbased models which is indicative of centralized computing you have the transformer and then this BDHGPU. So   
1:00:30   
they compare those two for the tensorbased model. So this BDHGPU is   
1:00:36   
actually a different type of model than the BDH that they talk about. Um so in a   
1:00:44   
transformer you have general attention a general attention mechanism uh the attention mechanism for the   
1:00:51   
transformer is a KV cache for the BDHGPU it's a state matrix in neuron dimensions   
1:00:58   
uh then the local dynamics for the transformer is a linear algebra for BDHGPU it's a local meanfield dynamics   
1:01:07   
then the feed forward network for the transformer are these M MLPS keys   
1:01:12   
and then you have these so these weight matrices and then BDHGPU you have this   
1:01:19   
emergent network defined by decoder encoder matrices   
1:01:25   
and then these neuron dimensions. So they kind of use I don't know if they're   
1:01:30   
using um reservoir networks or what they're using for this but we'll maybe   
1:01:36   
get to that later. uh the local graph models on the other and then okay so that's the tensorbased   
1:01:42   
models there's this general attention mechanism that they're trying to approximate here and then local graph   
1:01:49   
models uh uh we have the attention mechanism local dynamics and the feed forward   
1:01:56   
network so local graph models are distributing computing on graphs so we talked a little bit about how they're   
1:02:02   
using sort of uh complex networks instead of neural networks   
1:02:08   
for this or at least the way they're describing it is more in the complex networks domain. So BDH um for the   
1:02:16   
attention mechanism is synaptic state plasticity and there's a parameter for that. Um and then um   
1:02:26   
synaptic state plasticity is also the case for brain models. The local dynamics consist of local graph dynamics   
1:02:34   
plus edgery waiting for the BDH and then brain models we have spiking graph   
1:02:40   
dynamics plus heavy and learning. Then the feed forward network for the   
1:02:45   
BDH or neuron interaction graphs and so that these graphs here defined by X Y   
1:02:53   
and S. And then for the brain models, the feed forward network consists of   
1:02:58   
neuron interaction graphs which are unspecified. So these are gen general overview of   
1:03:04   
these architectures. Um the inference dynamics of BDH and BDHGPU   
1:03:10   
act as a natural bridge between transformers and models of the brain. The two main inference mechanisms of a   
1:03:17   
reasoning architecture attention and the feed forward network are defined at a macro level through tensor operations   
1:03:24   
for the transformer and at the micro level neuron interactions through local graph dynamics for brain models. The new   
1:03:32   
BDHGPU architecture is naturally defined both at the level of vectors and a   
1:03:38   
particle dynamics of neurons and synapses acting as the bridge between the two approaches.   
1:03:44   
Okay, so this is the physical system representation of BDH as a physical graph toy model. So this just shows   
1:03:52   
these different uh graph parameters gx, gy and gs. You see them here. Uh I   
1:04:00   
guess they're connections between these different states. you have x and y is   
1:04:06   
the activation vectors and then you have uh synaptic state of model. So uh the   
1:04:14   
graph parameters of the model. Uh so you have first of all you have state equations and then you have the   
1:04:20   
oscillator network toy model. The state equation the state equation   
1:04:25   
for our graph parameters of the model. In the oscillator toy network model the   
1:04:30   
uh correspondence are wires prods and elastic connections. So that's what they have here. These elastic connections,   
1:04:37   
wires and prods. Um, and then the synaptic state of model   
1:04:43   
corresponds to the displacement of elastic connections in the oscillator network toy model. So this is the toy   
1:04:49   
model. And I think what they're trying to do here is diagram out these different components. Um, and you know,   
1:04:57   
it's kind of like they're taking things from their state equations and kind of   
1:05:03   
translating it to this sort of graphical model. So uh you have these elastic connections   
1:05:10   
then you have the displacement of elastic connections then activation vectors the state equations the   
1:05:16   
correspondence of that and the toy network oscillator network toy model are   
1:05:21   
pulses at nodes and state correction. So that's what they're kind of describing here.   
1:05:33   
Okay. So they have a lot of equations in here. I'm not going to go through um   
1:05:42   
and this is neuron neuron communication using graphs. Uh so this is the   
1:05:48   
correspondence between graph H which is here with M edges uh which is on the left and neuron   
1:05:56   
neuron interaction graph G which is corresponds to H squ. So basically uh   
1:06:04   
this just shows uh how you can express linear signal   
1:06:10   
propagation on a broad class of graphs using two steps of linear dynamics on a   
1:06:15   
sparse circuit. So I'm interested in this toy model. And the toy model of course is usually, you know, we'll use a   
1:06:23   
toy model in physics to demonstrate a principle that's kind of hard to understand. And you build this small   
1:06:30   
model that isn't necessarily useful for large amounts of data, but nevertheless, it communicates this idea. So um   
1:06:40   
I want to go over the definition of the toy model because I think it's interesting. So we will consider the toy   
1:06:45   
model of an n particle system shown in the figure that I showed in figure two   
1:06:50   
is an illustration of the general form of dynamics of the states base equation of bd.   
1:06:57   
All right. So the first thing is we draw n particles in a circle. We see that here we have the five particles   
1:07:03   
and then the particles are connected each other by the state elements represented as these elastic connectors   
1:07:09   
these wiggly lines. uh the topology of the pair wise connections is given by the graph GS.   
1:07:17   
So that's the the black lines between the states and in may in general be   
1:07:23   
dense. The signal displays dynamics of state P through or or F through tension   
1:07:30   
of of on connectors which evolves at a slower time scale and a more puls-like   
1:07:35   
activation dynamics XY on nodes appearing and vanishing regularly at a   
1:07:40   
rapid time scale. So that's kind of what they're doing here. So they basically have these elastic connections between   
1:07:47   
the nodes. then they have this uh tension that you know introduces these   
1:07:53   
pulses and that's kind of how they're imagining their network. The slower   
1:07:59   
state dynamics represent in the first order oscillation or relaxation of the   
1:08:04   
system of elastic connectors. Once an elastic connector between particles I and J has had its end points displaced   
1:08:11   
through states X and Y respectively, a tension appears on this connector which   
1:08:17   
causes its displacement and then you know between the particles.   
1:08:22   
So there's this displacement between the particles when you get this sort of tension in the system. So it's like kind   
1:08:28   
of combining a physical system with the actions of   
1:08:33   
uh like an a spiking neural network or something where there's some sort of   
1:08:39   
synapse or connection between the two neurons. So it's interesting and you   
1:08:44   
know we've talked in divorm we talk a lot about tensity models and this is   
1:08:50   
almost kind of giving me the same kind of idea about how those models work. We have a number of nodes in the in the   
1:08:57   
model which are um mechanical points of articulation.   
1:09:03   
And then we have these uh strings that can induce tension or   
1:09:10   
you know some other physical uh constraint and they behave in a way that   
1:09:18   
you know introduces superstability to the system. so that the uh the physical   
1:09:23   
forces balance out. That seems kind of like what they're trying to do here in a way. They're trying to build this   
1:09:30   
physical system that represents kind of the you know what you might see in a neural system. And I know there are a   
1:09:38   
lot of like analogies being made here, but uh I think they're they think they're on to something because there   
1:09:44   
are a lot of these sort of thermodynamic approaches that people are starting to pick up now in the field. And so um but   
1:09:52   
it's interesting how they're trying to kind of find the right mix of things. Um   
1:09:59   
so the faster dynamic back to this definition of a toy model. The faster   
1:10:04   
dynamics represent the node dynamics of particles over time. Pulse displacements   
1:10:09   
XI happen at nodes as a result of either previous behavior of the system or   
1:10:14   
perturbation by an external forcing field. Okay. So this this field may would be a language input or it could be   
1:10:22   
some other type of thing that you're trying to analyze uh like uh data for   
1:10:27   
classification or something like that. A node I with displacement X I may due to   
1:10:33   
the exaggerated action of tensional elastic connectors adjacent to it activate a system of prods gy adjacent   
1:10:41   
to it perturbing nodes it hits in this way. If another node J is prodded sufficiently hard, it may cause it to   
1:10:48   
activate a perturbation YJ. Perturbation YJ of a node J will in   
1:10:54   
the next step propagate action to those other nodes I prime which are connected to J by a system of wires. Yeah, this is   
1:11:02   
definitely sounding like tensgrity. I have to pull this up or at least think   
1:11:07   
about this in in that context because there you know in tenseity models you   
1:11:12   
have single nodes that interact with other nodes but you have both these   
1:11:17   
direct connections and these indirect connections or at least indirect effects that you see. So node I is connected to   
1:11:25   
node J and then node K is also connected to node I and node J. And when you   
1:11:31   
perturb I or when you perturb a connection with I, it perturbs a   
1:11:36   
connection with J and K and then that propagates back to I. So you get this   
1:11:41   
feedback as well. So you get the this mass set of effects from a single   
1:11:48   
propagation and that's largely due to the connection being they're all being connected in a network.   
1:11:54   
If the aggregated pull of wires on a node I prime is sufficiently strong, this modifies its pulse displacement Xi   
1:12:01   
prime. The pulse activation uh Y J prime   
1:12:07   
of some node J prime directly following the pulse activation of X I prime of node Xi prime results in an increase in   
1:12:14   
the tension of the connector J. adding to the value of the tension all pulse   
1:12:20   
activations y subside and the pulse propagate consequently altering the slow state. So this is kind of describing how   
1:12:29   
you know these relations happen in the network using a very simple set of interactions that we can unpack.   
1:12:37   
So I like that you know that aspect of it. Um I'm not quite sure about if I can   
1:12:44   
answer my question about the type of methodology they use for   
1:12:50   
network. I don't think they use any sort of reservoir network here but it would be interesting to use that to grow the   
1:12:57   
the graph. Um they do use edgery waiting. So they use a closed graph with edgery waiting. I think that's what   
1:13:04   
they're doing here. um they also have uh this sort of uh   
1:13:10   
anchoring definition. So for anchoring in the literature of dynamical systems,   
1:13:16   
we note that already systems following an interaction kernel with a strongly constrain K in the form K inclusions of   
1:13:23   
a VI J exhibit powerful nonlinearities which is what we talked about before in the toy model example. with such a   
1:13:30   
restriction on K. Equation three which is up here. This equation which looks   
1:13:37   
like a replicator equation describes the class of evolutionary systems following the equation of replicator equations of   
1:13:44   
replicator dynamics and this was from Hoffbara and sigund also equivalently   
1:13:50   
known as non-normalized form of the fundamental locker predator prey dynamics. So that this is a replicator   
1:13:58   
equation here um which describes sort of you know uh where things replicate based   
1:14:05   
on their fitness and if one class of replicator is dependent on the other   
1:14:11   
class replicator they self sort of regulate their their uh reproduction and   
1:14:17   
their ability to replicate. uh replicator dynamics can naturally be   
1:14:23   
represented as graph systems whose parameters are defined on edges on the graph who but whose state is updated on   
1:14:30   
nodes on the graph. So the parameters or edges the states are nodes. By contrast,   
1:14:36   
when defining dynamics for reasoning in the current work, we will also need to capture more powerful class of   
1:14:42   
graphbased systems where crucially state is larger than the number of neuron   
1:14:47   
nodes appearing on neuron edges or synapses. Okay, so I think that's all for this   
1:14:53   
paper. I I don't know if people had any comments on it, general comments. I think you know getting too any more   
1:15:00   
deeply into the methods is not going to be useful for understanding it. But they're they're bringing together a   
1:15:07   
lot of things here um that are not like typical um large language model or   
1:15:14   
machine learning uh methodologies. Yeah, good paper. Yeah.   
1:15:19   
Yeah. So, so really appreciate you going through it. Um,   
1:15:25   
it it was I don't want to say given to me as a   
1:15:31   
task, but it was I it was put forward at the tower   
1:15:40   
um by someone who I should say is is not a   
1:15:47   
machine learning researcher, but she was she was kind of putting it   
1:15:52   
forward is like something for both the AI group and the the neuro group to   
1:16:01   
look at as an interesting   
1:16:07   
um post you know as an example of a post   
1:16:15   
transformer architecture right you know now uh I'm gonna I'm going to   
1:16:23   
leave aside some of the editorializing that I think that she added that I don't   
1:16:31   
think is um is you know I don't think I get from the   
1:16:37   
paper. Um excuse me sorry awful thing went   
1:16:43   
through. Um but it like   
1:16:49   
you know there was just also some weird things about the paper too, right? Yeah. It didn't seem like it was   
1:16:56   
implementable. Where's just like   
1:17:04   
you know so so you know background on the company it's like it's a logistics   
1:17:11   
company right so as you know like anything I can find   
1:17:18   
in terms of this company andor the the um the researcher involved   
1:17:24   
who who definitely has technical background to be able to propose things,   
1:17:30   
right? You know, but like, you know, again, it's it's it's something where,   
1:17:38   
you know, they're they're really coming out of kind of like operations research. Yeah.   
1:17:45   
and um which which does have a you know   
1:17:53   
certainly has a a long and um you know storied legacy.   
1:18:02   
Um uh so you know but then there's things   
1:18:08   
where it's just like I don't know whether I I need to concede to them just   
1:18:13   
some poetic license in the sense that like you know it's hard to stand out in   
1:18:20   
the fire hose or you know   
1:18:25   
just massive tsunami of of papers.   
1:18:31   
Yeah. Um, in terms of baby dragon hatchling, like   
1:18:38   
I don't know where that comes from. Yeah, I don't either, you know. Oh, it's baby is baby. I thought it was   
1:18:44   
brain, but it's baby dragon hatchling. Okay. You know, and and um and I think it's   
1:18:52   
supposed to to recognize that um this idea has has has hatched. Oh,   
1:19:00   
like like what you're what you're looking at is the is the hatchling. I   
1:19:05   
mean the baby. Oh, okay. Hatchling now. Um I I assume that means that there was   
1:19:12   
a previous paper. Well, probably more theoretical. Yeah. I mean this is theoretical. Yeah. But   
1:19:20   
Right. Yeah. Um but then it comes down to this kind of you know like like   
1:19:28   
what does the what does the transformer architecture   
1:19:33   
represent right? Um in in   
1:19:40   
the fact that like um   
1:19:47   
all all the big language models are using much more hybrid systems now or   
1:19:54   
like like they're using transformers, yes, but they're using plenty of other,   
1:20:00   
you know, if if you ask somebody to characterize any of those models like   
1:20:06   
that is just one of one of several things that they you would use to characterize them, you know.   
1:20:12   
Yeah. And and and I I think this somewhat points to the fact that that wasn't that   
1:20:17   
wasn't the goal of this paper. Right. Right. Like like is this is this a post   
1:20:24   
transformer architecture or is it literally just a a brain inspired   
1:20:34   
architecture that should be absolutely you know like like it's put up against   
1:20:40   
Transformer but not as like uh um   
1:20:46   
necessarily as like this is post transformer as being just like this is   
1:20:51   
different. Yeah. like, you know, and and kind of   
1:20:56   
set to to have um you know, it it's trying to   
1:21:02   
optimize different different things and and so so again, I I appreciate this   
1:21:09   
discussion because it's just like like she's she would like us to do   
1:21:15   
a more general meeting on post transformer architectures. Okay.   
1:21:22   
And my my question is, you know, like   
1:21:28   
obviously, you know, we we follow a bunch of neuroi,   
1:21:36   
you know, projects and and workshops and and researchers. Um   
1:21:45   
but you know a and this kind of goes back to this that that um remember that   
1:21:52   
big kind of position paper on neuroi that um like Tony Tony Zeder I think is   
1:21:59   
either like first author or last author on. Yeah. Yeah. I remember. Yeah. you know, was like a couple years   
1:22:06   
ago and then like David um   
1:22:12   
B like PF P I mean sorry P F A U like   
1:22:21   
I think I think he's like a deep mind guy was you know kind of slagging off on   
1:22:28   
on Twitter even saying that like you know This is the these are these are   
1:22:39   
I forget he he he had some he had harsh words because he was just like you know   
1:22:44   
like we're we're inventing the future you know and and you know the future is ML   
1:22:53   
you know like like the the the tenuous brain metaphor is   
1:22:59   
not actually important. Um   
1:23:04   
and and it it should be you know it's going to come from the math and you know   
1:23:11   
it's it's um it's optimization and like if you're interested in neuroi like   
1:23:19   
you're you're really doing something else like like it's um it's again not   
1:23:26   
clear if you're actually theorizing about you know how the brain is   
1:23:32   
organized. Mhm. you know, like are are you is is   
1:23:37   
neuroi a practical subd discipline of ML or is   
1:23:42   
it actually a subd discipline of brain science where you're you're actually   
1:23:51   
making a you know   
1:23:57   
you're po positing a a kind of theoretical model or not it's not   
1:24:03   
theoretical um you're positing an architecture and and kind of seeing the computational   
1:24:10   
consequences of that in the sense of playing, you know, making toy models,   
1:24:16   
having it work on data and kind of seeing like, oh, let's let's let's see the interesting things that let's let's   
1:24:23   
see the interesting features that this this approach has.   
1:24:31   
But it's it's not it's not as a it's not meant to be a competitor   
1:24:39   
to like production   
1:24:45   
production ML pipelines. Does that make sense? Yeah. Yeah. It's like you you have the   
1:24:52   
theoretical models of the brain. Then you have kind of maybe a way to think about in terms of an architecture which   
1:24:58   
might be more applied but you don't want to go up against like super performing models of that that might be used in   
1:25:05   
industry that the they're really two different   
1:25:12   
programs. Yeah. Yeah. They're not the same type of aim,   
1:25:17   
right? Yeah. You know, it's like it's like Yeah. and and um   
1:25:25   
anyway, it's like this is um you know, so again, thank you for covering this   
1:25:31   
paper and self selfishly I I posted it because I was just like I was kind of   
1:25:37   
like what would you do with this? Yeah.   
1:25:42   
Well, I was fascinated by the title. It makes maybe more sense now, maybe even less sense when you said baby. And that   
1:25:48   
and that seemed to be and that's you know like like again like I I think they   
1:25:54   
absolutely know that that's that's you know they they knew what they were   
1:26:00   
getting with that title. Yeah. Attention. Yeah. Which is what they were trying to model.   
1:26:06   
Yeah. and and um so   
1:26:12   
you know it's like it's it it seemed to me also being like   
1:26:20   
again like if I was trying to pitch in Silicon Valley   
1:26:26   
that this this could be an important uh you know I like always impressed with   
1:26:31   
people who are good at you know selling a narrative and Um,   
1:26:37   
yeah. So, um, sorry, I'm cleaning cleaning my   
1:26:43   
my dogs here. Um, but, uh, um, yeah. So, thanks for   
1:26:51   
covering it. It does it did seem to be kind of like an eclectic mix of things.   
1:26:57   
Yeah, it was definitely purchasing. Um, yeah. Now I like the network part like   
1:27:05   
you know kind of be getting away from like the neural network and getting into the complex network stuff where you're   
1:27:11   
thinking about like graphs. So you know you have the graph like it's kind of a conduit to graph neural networks but   
1:27:18   
they don't talk about graph neural networks. It's kind of like going to something like   
1:27:23   
uh like a growing graph where you're adding nodes in, you're connecting them up and then you know they're eventually   
1:27:29   
forming this this sort of architecture which could be scale-free. It could be   
1:27:35   
you know what we call small world. It could be random. The graph properties   
1:27:40   
can vary based on like maybe learning or you know maybe some physical   
1:27:46   
constraints. And then of course you have um thermodynamic constraints because you   
1:27:53   
have these you know elastic they they model like synaptic learning is elastic connections which is interesting right   
1:28:00   
like it's you have this uh analogy between elasticity and like synaptic   
1:28:08   
um encoding or synaptic learn you know adaptation which also though you know when I I just   
1:28:14   
mentioned about um insegrity structures which are you know something that we're   
1:28:21   
talking about in divor biological superstability you have the same kind of architecture or a similar   
1:28:28   
architecture where you have this network of nodes and there are these physical   
1:28:33   
things like struts or other types of physical um structures that are   
1:28:39   
biological in this case and then you have elasticity which are the connections between the nodes you have   
1:28:46   
the elast elasticity between the nodes. And so that's usually a physical medium   
1:28:51   
and in tense in this case it's an analogy of synaptic learning. But in a   
1:28:57   
you know in a in a biologic physical biological network it could be you know adaptation of some type where you have   
1:29:05   
um you know the adaptive mechanism that is where the body or the biological   
1:29:12   
system experiences something and it gets encoded in the configurations it can   
1:29:17   
take on. So there are a lot of relationships with like thermodynamics and physics, a lot of relationships with   
1:29:25   
uh biology and and other types of structures, a lot of relationships with learning in the brain. It's very   
1:29:32   
broadreaching and I could see a lot of ways to apply these. I I would would certainly appreciate any   
1:29:40   
thoughts you have. you know, if you were curating papers or or   
1:29:45   
kind of architecture that you'd want to put as   
1:29:51   
post transformer uh you know, I mean, you know, like like   
1:29:58   
the first thing I always think of is like, well, there's there's two things. So,   
1:30:03   
one I think of this old um I remember back in 2016,   
1:30:10   
you know, it's like it's not that long ago, but I'm talking about it like it's the   
1:30:15   
dark ages, you know. Um uh uh the   
1:30:22   
Do you remember capsules? Remember Hinton's capsules? No. Okay. So, so I think this is like um   
1:30:32   
you you remember when everything was gans, you know. Oh, okay. Take care of you. Um   
1:30:42   
uh uh you know, everything was gans and um   
1:30:48   
I I forget it was like a year plus. It's like of um Goodfellow's paper   
1:30:56   
and Maybe maybe even I have the timeline   
1:31:02   
wrong on this, but like the point being that Hinton um   
1:31:08   
put forward this new architecture that was the post whatever whatever   
1:31:14   
was the um the architecture of the day, right? Um, and   
1:31:22   
what it had is actually something that I think of as very Maxwelling in the sense   
1:31:27   
that like it was um Oh, okay. Yes. I I   
1:31:32   
will get that I'll get that done today. Vy. Yeah. Sorry, she's just asking something   
1:31:39   
in chat. Yeah. Yeah. Yeah. Yeah. I I I I got the link for sure.   
1:31:45   
Okay. And um the um uh   
1:31:53   
so I mean I just mention it because like like I remember I mean we've still got   
1:31:58   
this discussion on on our Neurochx Slack where it's just somebody's asking like   
1:32:04   
what do you think of this architecture and and I was just like yeah it's cool   
1:32:09   
you know like again it reminds me now of kind of Maxwelling where it's just like it's utilizing symmetry ries   
1:32:17   
um it's it's utilizing symmetries in some   
1:32:24   
fashion like I can't even remember exactly now um but but it's very very   
1:32:30   
much in the the Maxwelling tradition which le leads Maxwelling's   
1:32:37   
group to kind of clifford algebra approaches   
1:32:44   
um of of   
1:32:51   
you know it's like like current architectures but with Clifford algebra extensions right which which again   
1:32:58   
speaks to this kind of like geometric algebra understanding or exploitation   
1:33:07   
right but but they totally didn't take you know like like nobody used these   
1:33:12   
like you know like this this did not did not take over, right? Like like   
1:33:19   
everybody kept on using whatever it was. What did we use before anyway? Like like   
1:33:26   
they just kept using what whatever was the backdrop approach at the time, right?   
1:33:32   
And um just um   
1:33:38   
uh so the the other the other approach being Mamba, right? So, so Mamba is like is   
1:33:48   
supposed to be a post transformer architecture that um or well   
1:33:57   
it's supposed to improve on um   
1:34:03   
to transform architecture in in some theoretical way and and I assume you   
1:34:11   
know to to get the paper published that they had to come up with a few examples where it was it was actually better, you   
1:34:19   
know. But but the qu question I have though is like uh what would those metrics be   
1:34:27   
uh in terms of like improving upon a transformer architecture? You definitely   
1:34:33   
I mean you know like like would it be you know like like it could be in so   
1:34:38   
many different directions, right? And and and I think it's it says something that we don't actually know   
1:34:44   
which of those dimensions that's that's like kind of valuable to explain like to   
1:34:49   
be better on, right, in terms of becoming this this   
1:34:56   
bedrock algorithm that that allows for,   
1:35:02   
you know, that again like allows for a much   
1:35:08   
greater   
1:35:13   
you know additional complexity after the fact. I mean you know in the sense that like like again these large   
1:35:20   
language models have a um h have have a bunch of additional   
1:35:28   
um training features and and architectures to them in terms of mixtures of experts and and things like   
1:35:35   
that. So, so like like some somehow that   
1:35:42   
Yeah. So, again, this is this is more my own or you know, perhaps a   
1:35:50   
a defect of my own self-taught um education, you know, it's like   
1:35:55   
self-taught trading, right? Um and that like like I can't fully understand what the   
1:36:03   
dis um you know like like what are the   
1:36:08   
important dimensions on which that those those that that valuation would be um   
1:36:15   
held to you know as well as like   
1:36:22   
yeah or or is there even like a greater kind of misunderstanding of my own in   
1:36:28   
terms of what are the um   
1:36:35   
you know like like h how the how the transform model itself became this like   
1:36:41   
f first first pass that that other things can build on   
1:36:51   
and and you know is there there's   
1:36:58   
something in yeah it's like Like   
1:37:06   
I have a few questions actually maybe that'll help. Um so I mean why do we   
1:37:11   
want to have a post transformer architecture? Is it because we want to do better or is it because it's maybe we   
1:37:18   
want broader performance which sort of goes back to   
1:37:24   
the capsule thing where it's just like like I kind of felt like like Hen was putting out this capsule thing because   
1:37:30   
it was supposed to be like like it was kind of a way to grab to to to take the   
1:37:38   
spotlight right like like I I I super cynical, but   
1:37:45   
but you know at the same time like like again like there's a cheap there's huge   
1:37:51   
money at stake in these things like this isn't an academic we're not talking about astrophysics here we're talking   
1:37:58   
about like you know what has potentially created the largest economic bubble   
1:38:04   
of mankind's history right like so we're talking about a lot of money um   
1:38:11   
And you know, I I I I don't want to I don't   
1:38:17   
want to fall down that in terms of like like I I I think   
1:38:24   
like I will say that the the woman who proposed the baby dragon hatchling paper, I think was definitely coming at   
1:38:32   
this as as an outsider wondering like are there architectures that   
1:38:40   
would be more more amendable to   
1:38:46   
um solutions to an AI alignment.   
1:38:53   
Okay. To AI alignment issues, right? So, so,   
1:38:59   
um, you know, which which was maybe a misunderstanding of kind of like the   
1:39:06   
brain inspired part. Um but but again   
1:39:11   
it's like how um yeah anyway I think she she she was   
1:39:18   
definitely sort of thinking of that in the sense that like how do we get away from an architecture that's just a   
1:39:26   
sequence predictor you know and and that that like that   
1:39:33   
there's certain limitations to a sequence predictor. Um   
1:39:41   
or like like everything just being a like trying to do sequence predicting better and and again um   
1:39:50   
uh I think the blaze blaze arcus um   
1:39:58   
um how do I keep forgetting his last name? Arcus Aas or something like that. Yes.   
1:40:07   
You know, like as someone who's def who definitely cares about this is like pointing out   
1:40:15   
that um you know there there are intelligence problems that are good   
1:40:20   
sequence prediction problems and then there are intelligence problems that are absolutely not. Sorry, got   
1:40:29   
some uh some people leaving here. Yeah. All right. Um yeah you know and   
1:40:36   
this is interesting because this gets addressed in this cybernetics paper that we've been working on. Um if you dig   
1:40:43   
into it a bit um we have the you know kind of talking   
1:40:49   
about different models not focusing in any one model but how uh models of the   
1:40:54   
group regulator can help us understand some of what the structure what's going   
1:41:00   
on in in artificial learning systems. So one of the things of course with large language models is that it's a sequence   
1:41:06   
predictor, a sequence learner. It's spitting out these tokens that are putting things in a sequence and they   
1:41:11   
have to make sense. Um and so but the thing is is that you can use a good regulator model to approximate that.   
1:41:19   
There's a thermodynamics to like sequence sequence production. There's   
1:41:25   
also a link with um like uh DNA and RNA   
1:41:31   
and proteins because there are groups that have been using large language models to predict DNA sequences to   
1:41:37   
predict protein sequences with pretty good we we covered a couple of those models in DVOM where they do pretty well   
1:41:45   
in predicting sequences which is different from human natural language   
1:41:50   
because it's like you know it's just trying to predict like a functional sequence.   
1:41:55   
there isn't the same sort of um I mean people argue that there's grammar and that there's stuff like that in in DNA   
1:42:03   
sequences for example but you know the structure is different than a natural language but it can still do that and so   
1:42:10   
at the core of a large language model is this sequence production basically and   
1:42:16   
then you can use a good regulator model or something like that to like you know   
1:42:21   
produce sort of the thermodynamic conditions of that I guess that's kind of the argument.   
1:42:27   
Um, yeah. I mean, this is I'm just gonna say Blaze.   
1:42:34   
I'm going to use his first name. Not that I'm on a personal have a personal relationship. Uh   
1:42:40   
Bla Blaz's point is it's certainly like that where he's just like like there's a   
1:42:47   
um you know a sequence prediction works but if if the beginning of your if the   
1:42:54   
beginning of the sentence is you know is something tright like it's a you know   
1:43:02   
like yeah that where where   
1:43:07   
probabilistic ally you can you can guess what that word is that's great but if if   
1:43:13   
the same sentence is actually the beginning of a mathematical proof like that like the next the next thing that   
1:43:20   
you need to predict is is is actually um   
1:43:25   
unlikely um but but absolutely can be um   
1:43:33   
constrained by certain bounds or you know like like can be given a can be given a say a symbolic   
1:43:41   
representation. Um I I just wanted to say to to that point and again coming coming back to   
1:43:49   
this you know like like these are these are difficult topics because   
1:43:56   
these are certainly tied to current economics um was was a a wonderful video I saw of   
1:44:05   
um um I'm trying to think the CEO of Nvidia   
1:44:11   
um and It's like like Wong, like Hua N.   
1:44:16   
Yeah. Anyway, uh um so he he's showing off the new Blackwell   
1:44:24   
architecture DGX box. Yeah. Right. So this is like this is like a   
1:44:29   
$200,000 box he's talking about. I think he's he's next to kind of like the head of AI   
1:44:38   
for Germany. Not not like like a university Germany,   
1:44:44   
just the government. Yeah. like, you know, and they're like like we're gonna buy, you know, a hundred,000 of these   
1:44:51   
boxes. And um and he was he was talking he's like this this box um uh you know   
1:45:02   
outputs tokens and those tokens are money you know like like like it wasn't   
1:45:12   
it wasn't like you know it was it was just a pure you know these these these   
1:45:18   
tokens this is a money printing machine. They're food pellets. [Laughter]   
1:45:26   
And I was just like, well, you know, there there it is. There you can't you can't get a, you know, a clearer pitch,   
1:45:34   
right? Um uh um so   
1:45:41   
you know like like again like what is post transformer architecture, right? like like is it um so it comes back to   
1:45:51   
this like is post transformer architecture   
1:45:57   
just a specialized architecture where it's just like like it's set up for for   
1:46:02   
math problems that doesn't seem like what a post transformer architecture is. It's like like some somehow   
1:46:09   
fundamentally like like like what what the model's outputting   
1:46:16   
is is much more powerful, right? like like like it'll be something and you   
1:46:23   
know this is kind of a a stupid metaphor but like it'll be something like instead   
1:46:29   
of outputting tokens it'll be outputting complex tokens   
1:46:34   
you know like like to follow the the kind of mathematic you know like like   
1:46:39   
these aren't numbers these are complex numbers yeah you know and like like like it   
1:46:47   
it'll open up this new this new dimension like that'll be the post transformer architecture where it it   
1:46:56   
still somehow has the sequence prediction but it has something else you know like it's it's   
1:47:02   
some somehow you get another you know   
1:47:08   
you get another layer of um   
1:47:15   
whatever it is that we need. Yeah. Yeah. Yeah. Well, it's like like like again it gets it gets to something   
1:47:21   
fundamental about like what this token is, right? Because it's like like the token itself is is um   
1:47:32   
yeah it's we need a higher level of organization for tokens. Like a token is just kind of an atomized thing and then   
1:47:38   
you're putting them together. I mean, you know, the the complex number   
1:47:44   
idea is is is sort of, you know, I mean, like like the token is   
1:47:51   
kind of like a forier, you know, a forier output, you know what I mean? Yeah. Okay.   
1:47:56   
Like like you know, you you are getting um   
1:48:02   
you are getting this magical transformation of the of the data that you you've given it, right? like like   
1:48:09   
and so and then like in this in this space you know the data looks you know   
1:48:16   
and has this this interpretation um   
1:48:22   
yeah anyway so I I thank you for covering that paper you g me a lot more   
1:48:27   
to talk about in terms of trying to do um   
1:48:33   
an event around this I mean Oh yeah so it it's Um   
1:48:39   
uh a and you know like like again it comes   
1:48:44   
back to this question of what is the neuroi program and and is it   
1:48:53   
uh yeah I is it is it actually relevant at   
1:49:00   
all to you know should should should neurai remain a a brain science   
1:49:06   
discipline. Yeah. than than pretending to be a   
1:49:15   
um an ML discipline. Yeah. Well, I think like in terms of benchmarks, of course, probably not   
1:49:21   
going to be there or, you know, I mean, if if it does happen happens to do   
1:49:27   
better performance-wise than existing AI models, so much the better. But I don't   
1:49:33   
think like you know we should pursue this in the sort of with the goal of   
1:49:39   
optimizing uh performance on some benchmark. I mean that's just not what you're going to get   
1:49:45   
at least not at this point. So it's really about building to me in my mind   
1:49:51   
it's building models of the brain or building models that are brain inspired and it's just basically playing around   
1:49:56   
with what the brain does. What are mechanisms? We know we know that there are certain mechanisms in the brain that   
1:50:03   
produce maybe behavior or some sort of output that is you know based on   
1:50:08   
learning or some sort of intelligent behavior and then you know seeing what you can do with that. Um the application   
1:50:15   
domain is maybe open. We don't really care so much about that and it's not so   
1:50:21   
much remaining in neuroscience but it's not putting it up against like uh state-of-the-art AI. So you know what   
1:50:28   
the artificial life community is doing is very similar to what I think is probably the goal for neuroi at least in   
1:50:35   
the short term which is to build interesting models get interesting results see what they can do and um you   
1:50:43   
know if you can put them you know build per performance benchmarks and get some   
1:50:48   
good performance on them then that's great but that's not the that shouldn't be the goal of the you know to because   
1:50:56   
what happens of course in state of the art AI is you're always trying to optimize the benchmarks. That's the   
1:51:01   
whole goal. And then you're getting these small improvements and you're like, well, this is great. This is better. This is a better model because   
1:51:07   
it gives us uh just a little bit better performance. But then, you know, it's like, well, okay, but like,   
1:51:15   
you know, what is that? I could build like a model that's has bears no   
1:51:21   
relationship to the brain. In fact, it's just kind of like maybe a brute force model or random model and I can produce   
1:51:28   
a certain level of performance, you know, uh what does that tell me? What's interesting about that? I mean, I guess   
1:51:35   
it gives you good performance, but beyond that, it's not much. So I would I would definitely think you know at least   
1:51:41   
in the short term neuroi is about kind of brain modeling and seeing what you   
1:51:47   
can do but I would you know it's you don't want to get caught in that trap either of trying to optimize metrics and   
1:51:53   
things like that. Yeah I mean you know like like for sure   
1:51:59   
for sure right and like and like we think of these the you know like a   
1:52:06   
benchmark Yeah, like like again we're so limited   
1:52:14   
in our attention, right, that we can actually come up with a lot of benchmarks and yet it still be very   
1:52:23   
limited in terms of of the the space in which um we actually operate, you know,   
1:52:32   
and and so so maybe just finish off with   
1:52:37   
a with a last reference to that um biological underpinnings of lifelong   
1:52:43   
learning perspective paper that that has the you   
1:52:49   
know 30 plus co-authors. Um   
1:52:54   
but the the wonderful matrix that it has in terms of you know these are the   
1:53:01   
problems that we see in continual learning and   
1:53:09   
these are the the mechanisms the puditive mechanisms   
1:53:15   
uh that that biology has found   
1:53:20   
that that um c can perhaps deal with some of those   
1:53:27   
these continual learning problems, right? Yeah. because because um   
1:53:33   
again um e e even in this short time you know   
1:53:39   
I forget how much the um   
1:53:45   
large language models don't try to you know they they are in no way shape   
1:53:51   
or form any even attempt at solving continual learning problems.   
1:53:57   
Yeah. Right. they are they are a a very fixed model. Um   
1:54:05   
so um you know any yeah that's uh interesting stuff.   
1:54:13   
Yeah, we we'll we'll try to come back to this sort of post transformer model thing too because I think that's an   
1:54:19   
interesting question even you know I mean because you you reason we use transformers is exactly why because they   
1:54:25   
perform well or that they provide a compact representation I mean   
1:54:31   
those are great and interesting but like you could you know and especially like thinking about like language models you   
1:54:38   
know what do what do we want what could we put in there maybe it's not the greatest performing model, but what   
1:54:44   
would give the most interesting results? So, we could substitute in a bunch of different types of models,   
1:54:50   
you know, maybe things that are model attention, maybe they're more computational models, things like that.   
1:54:58   
as as I mean and potentially and I and I think this gets to the root of of her   
1:55:04   
actual original request which comes from a a uh   
1:55:11   
so she leads the human flourishing floor. Okay. Okay. And I think   
1:55:21   
you know like like I don't even it's not even I think I know that the only   
1:55:28   
question I'm asked uh by basically every person who who comes to the tower is   
1:55:35   
like I get all the other floors what's the human flourishing you know and and   
1:55:42   
but I I I mention it because it's relevant went to the other foresight meeting. Was it   
1:55:49   
foresight? No, no, sorry. It was um computational philosophy salon.   
1:55:55   
Okay. This week that had Adam Saffron and um and I   
1:56:01   
forget the um uh   
1:56:07   
I forget the other guy's name. Um I think it was a Finnish name.   
1:56:14   
Yeah, it was like it wasn't Reuben, but it was like it's it struck me as Finnish or Baltic.   
1:56:23   
Anyway, uh I won't claim to be uh that that knowledgeable, but he's moving to   
1:56:29   
Oxford and um his his group at Oxford is going to be called Flourishing   
1:56:36   
Intelligence. Okay. And um and yeah, thanks Jess. Um   
1:56:45   
so so it see it it seemed relevant to the um yeah luben la yeah yeah lacan   
1:56:56   
and um um the   
1:57:06   
you know again the the biological underpinnings of lifelong learning is really about autonomous systems.   
1:57:13   
you know, systems like like um   
1:57:18   
that that are potentially sustainable, right? So, and and I'm I'm using that in   
1:57:26   
a very broad sense where it's just like like they're both they're both   
1:57:32   
autonomous and able to update themselves,   
1:57:39   
you know, like like you you can you can release and they will continue, you   
1:57:44   
know, learning and adapting and and um uh staying staying u competitive.   
1:57:53   
right but but can do so with resource   
1:57:59   
constraints etc like um uh it it's this combination of   
1:58:06   
of his work as as a um practitioner of   
1:58:13   
of meditation um but definitely relates to you know   
1:58:19   
something that I've seen Adam Saffron speak to multiple times when he comes to the foresight institute and talking   
1:58:26   
about you know compassionate artificial intelligence it's like like somewhat   
1:58:32   
speaking to this alignment issue and somewhat speaking to how to you know   
1:58:38   
like like what role   
1:58:44   
would AI ever have in our happiness andor uh um Yeah. Yeah. and and un   
1:58:54   
unfortunately. Oh, yeah. Yeah. Yeah. Yeah. So, so Jess   
1:59:00   
is is saying, you know, has has Adam spoken about this? He he absolutely had   
1:59:06   
like like I don't think I mean I think you can find a talk of Adams on this in   
1:59:14   
terms of covering this. He he he has since I think since he joined   
1:59:22   
Leven's lab, I think he's done a couple   
1:59:28   
uh a couple of his own meetings where he's talking specifically about this. He   
1:59:35   
he's definitely spoken at foresight foresight vision weekend.   
1:59:42   
So, so yeah, it I think it falls under existential hope like like as you know,   
1:59:49   
you know, I I I mistook it. So, in my head I was just like, oh, this was a foresight event and I was like, no, no,   
1:59:54   
that's actually it was a computational philosophy. Um   
2:00:00   
you know so so um but I but I know he's done he he's done   
2:00:07   
specifically his own meetings on this and um   
2:00:14   
it yeah anyway like like I I was only asking because   
2:00:20   
I I know the foresight institute is a is a   
2:00:26   
concern about many things that I am, but I didn't. It's sort of like ven diagrams   
2:00:32   
not connecting and then you're like, oh, like I didn't know Adam and Foresight   
2:00:37   
were doing that together because I know Adam's been doing a bunch of stuff and I know foresight's done a lot of things   
2:00:42   
and I didn't know there was like any, you know, like   
2:00:49   
how that would work. But I'm glad it I wouldn't say though. I   
2:00:56   
mean, I shouldn't say that. This was Adam pitching. I see. Yeah. So, so this is Adam like   
2:01:04   
coming to um I mean the last time I heard him   
2:01:10   
speak directly to this I think was actually the Neurotech whole brain   
2:01:16   
emulation AI safety um workshop   
2:01:23   
and um and and it was a pitch like like I I do   
2:01:29   
think it's somewhat aligned with with their existential hope program. Um,   
2:01:34   
yeah, that's what I would but but I don't believe I don't believe he's like a fellow of that for instance   
2:01:41   
or like I could be wrong. I could be wrong. Um but it it's definitely it's   
2:01:48   
definitely it relates to is   
2:01:54   
you know like academically I think he was an effective   
2:01:59   
you know an effective neuroscience yeah right I was surprised like you were   
2:02:06   
surprised that Adam like wasn't a foresight I was surprised because the meeting itself for me I was like okay   
2:02:12   
Carl first snack for That's how I was told about it. And then it's so and it's Reuben who's like   
2:02:19   
talking like very, you know. Oh, yeah. Right, right, right. No, I agree.   
2:02:24   
And Adam's there. I didn't know Adam's gonna be there at all. I'm like, oh, yeah. Yeah. So, yeah, it   
2:02:31   
surprised. I was I was expecting more active inference.   
2:02:36   
Um, and and I don't know if they came around to that because I I Yeah, I just   
2:02:42   
had too much stuff going on at the same time. Like unfortunately, we had a memorial service at the tower for for   
2:02:50   
somebody who passed. Um so um I I was not uh on for the whole   
2:03:00   
time but um but they seem to be doing a deep dive in   
2:03:06   
meditation and and issues of you know consciousness   
2:03:12   
sessation and things like that that um   
2:03:17   
uh are are difficult But   
2:03:22   
again, I I felt we're kind of like easier to understand with with differing   
2:03:30   
anesthetics, you know. Uh I mean, if if I was going to study them   
2:03:38   
experimentally. Um, I I think I would be interested more   
2:03:44   
in using different anesthetics um and getting at some of the,   
2:03:52   
you know, time perception and and other other issues that that they were talking   
2:03:59   
about. Um,   
2:04:05   
yeah, I I I didn't catch all of it. Um, I I'm   
2:04:10   
sure there's a whole bunch of things I'd say, but I imagine you want to get going. I'm sorry for coming in. So, like   
2:04:15   
Well, it's okay. Uh, we have like 10 minutes left. Would you like to give an update or would you like to discuss some   
2:04:21   
things? What did I'm I didn't know like at the meeting that I I'm just I'm curious what happened earlier today in   
2:04:28   
in the meeting because I don't want to repeat anything. I don't know if you guys talked about what Morgan just said or other stuff so I don't want to rehash   
2:04:35   
it but well we talked about this baby dragon hatchlings paper that was in the Slack.   
2:04:41   
I also did a you humored me. Yeah. Well, we also did a blog post on   
2:04:47   
um uh like AI, the underpinnings of AI and   
2:04:52   
this whole um complexity reading group that um Paul Middles is running.   
2:04:58   
Uh so you talked a little bit in that space and then I I gave some updates   
2:05:04   
uh for the lab. So yeah, I mean I don't know if you okay but had any general updates though you wanted to talk about.   
2:05:10   
Oh I mean I have a whole ton of things to say. Oh my god, I'm like remembering   
2:05:17   
stuff continuously. I don't know where to begin with some things. One, um   
2:05:24   
I will I will I'll I'll try to map it out very quickly. One, I have plot twisters related updates. I have   
2:05:30   
Princeton and Vision related updates. I have Jo Future Center up updates. And I   
2:05:36   
have updates around I mean we I was at the this the salon that Morgan was at   
2:05:44   
which which I'll start with there and just say really really interesting. I'm so glad I I was able to go to it. I I   
2:05:51   
zero% I thought Adam when I when I showed up in Zoom and I saw Adam in Zoom like oh   
2:05:56   
that's cool. Adam's here is a participant. I haven't been in any space with him in a while. I came in an hour   
2:06:03   
late, but he was a co he was like a co- co- speaker. Um, so it was very   
2:06:09   
interesting to see him and what he's up to. I I know he's doing like a small like consciousness journal club reading   
2:06:15   
group thing, but I've been invited to and I've never I've never been able to go because I always spend the time doing other things.   
2:06:20   
That that was I've had like no   
2:06:25   
I he didn't disappear or anything, but to me he disappeared. So I I've seen him or interact with him in a long time but   
2:06:32   
it's like we're on the same path of a lot you know still um or he's on and   
2:06:38   
similar things you know blah blah so that was very cool um but also unexpected the thing the thing about the   
2:06:45   
computational philosophy club and a lot of echolapto related things Brad they you don't know is like a lot of times   
2:06:51   
they came they come up like one or two days noticed. Yeah, like like this wasn't planned like two   
2:06:57   
weeks ago. It didn't exist. So, it's kind of like this randomized opportunity   
2:07:04   
thing. Uh, which is cool. Um, but I would have loved to been like, oh, let's have all   
2:07:09   
the condition futures folks come to this event, you know, or or like last week or whatever. There's also like a funny one   
2:07:15   
next time. It's cool. Um, so that was that was fun. Um, let's see. Uh, plot   
2:07:22   
twisters. Um, the wheels are slowly turning. Platus is   
2:07:27   
plat is demoing. They got a grant or we I suppose I   
2:07:33   
should say got a grant to do a very specific part of the game like about   
2:07:38   
through Medicov. Um, and it's about um   
2:07:43   
it's called Small Town Holes Court and and people are working on it. I'm not part of that group. It's very It's kind   
2:07:49   
of a little secretive, but they're demoing it or they're having like a user testing thing happening   
2:07:56   
starting now, I guess, like certain like the next few Fridays are doing something. So, I   
2:08:02   
will try to post that in in the chat because it'd be good to have people to give feedback or whatever. Um, and I   
2:08:08   
don't have a lot more to say that because I have no idea I have no idea what what it is in uh yet, but but   
2:08:14   
that's happening on on one side. on the other side in working with um another part of plot stuff that I do know about   
2:08:21   
has been um um   
2:08:29   
uh we're looking at a certain part of plot twist which I'm   
2:08:34   
not at liberty to discuss fully and its relation to things like um emotion   
2:08:41   
regulation like theory and research around it but also there's a side thing   
2:08:47   
that I've kind of been really focused on about pedagogy, teaching, curriculum, education,   
2:08:53   
and it's led me down this pathway of um let's see   
2:09:00   
uh looking at at classical works even like critical classical works like pedagogy of the oppressed which is like   
2:09:06   
one whole lineage of thought and ideas and more contemporary um I've looked   
2:09:12   
actually at like pattern language um and the concept of a pattern language by I   
2:09:17   
think Alexander in that book and stuff like that and then how to apply that to teaching. And so my latest p like the   
2:09:25   
the latest turn of this path which I would have actually spent a lot more time on here if I had more time to learn today and maybe next time is how people   
2:09:35   
are using it to map curriculum spaces. Um, and for those who don't know, a   
2:09:42   
pattern language is sort of attempting to demarcate in particular domains   
2:09:49   
recurring patterns of how something materializes. It's based ar from   
2:09:55   
architecture, but I'm super fascinated to apply it to other sort of a front like pattern matching pattern pattern   
2:10:02   
language plus uh frontier map as you can tell or like we've talked a lot about curriculum design epistemological   
2:10:09   
directories. So kind of like what's going on there and looking at some papers about like actual educators,   
2:10:15   
curriculum designers teaching teaching teachers pedagogy that that that's really interesting to me. U so lots   
2:10:21   
going on there. Uh the future center stuff is kind of related to that. Um   
2:10:27   
and and more yeah I mean directly related to like curriculum design like I'm really thinking about how if I could   
2:10:36   
do we've kind of Brad and I have talked informally about like oh designing my own PhD stuff right now. Um some of that   
2:10:42   
would essentially be um like how to develop certain new fields   
2:10:50   
but then how to do the training like as well like how are you   
2:10:56   
like very both implementation and theory of how to do new stuff in that sense. So   
2:11:02   
the future center is a little more concrete than that. Um, but suffice to   
2:11:08   
say, it's about thinking about curriculum design, thinking about different projects around that, and I'm I'm really trying to to talk to people   
2:11:14   
in that space to kind of get a better grasp of things. And I should probably do a more broad bit in the future center in general. Um,   
2:11:22   
I've been kind of MIA from a lot of like intense work the last two weeks. I've been processing some things. I don't   
2:11:28   
know the weather, blah blah blah, but this week was kind of coming out week. And I'll conclude on a very fun thing.   
2:11:35   
Um uh what's what's that like Mark Twain   
2:11:40   
saying like rumors of my death were widely um you know overblown or   
2:11:45   
whatever. Um, Princeton Envision is alive and well.   
2:11:51   
And to my surprise, um, I reached out to them months ago and   
2:11:57   
heard nothing. And then I just got a random thing like 10 days ago from one   
2:12:02   
of the co-chairs and we've talked this week. We talked Monday.   
2:12:09   
So, I will very likely be a speaker at the event this year, which is in Feb or next year in February   
2:12:15   
uh 2026. And   
2:12:21   
I don't quite yet know what it will be. It's a little bit different than events in the past. It's actually taken a step   
2:12:27   
more in the direction in the in the direction of data and direction or society ethics technology. like they've   
2:12:33   
shifted to AI tech policy ethics um or kind of we robot feel even uh but I but   
2:12:40   
I don't quite know like it'll be you know I I I've kind of pitched a little   
2:12:45   
bit of the idea of presenting on some current topics but also like Princeton and vision historian because I'm such a   
2:12:52   
fan of the three three events I went to as we all know here probably um and kind   
2:12:58   
of just doing this crossgenerational like a lot of I the major theme for me of late is sort of this   
2:13:04   
crossgenerational we're massively intergenerationally   
2:13:09   
unprepared for the moment we're in. So how do we foster crossgenerational   
2:13:16   
let's try to help young people understand what is happening in the world um to to be comical about it but   
2:13:22   
in a very serious way like I'm very happy to provide like they didn't have a lot of contact with the like Luca or   
2:13:30   
Sonia Joseph who were all Princeton and Vision folks no less um   
2:13:36   
uh Phil formerly Phil now Emil P Torres uh um and and Logan Thrasher Collins   
2:13:44   
like we were all envision folks who all of were there and and so like there's I   
2:13:49   
think they don't even know the depth to some of the legacy that they have um at least from an event space but like what   
2:13:56   
does that mean for for people you know for for kids for people trying to understand and do meaningful things   
2:14:01   
which is like something I'm extremely focused on lately is like holy crap like we we need to like   
2:14:08   
recognize the degree as educators or guides or or mentors that that's   
2:14:13   
happening. And so I'm looking forward to that. I'm in talk with them about what to do. I have I have ideas and all this   
2:14:19   
other stuff. But um finally, I'll say um   
2:14:24   
we're kind of wrapping up things with data and direction too and and this first summer cohort that's involved in   
2:14:31   
spring cohort. And I'm just I'm just very excited with them and and some of the folks have I stay with their   
2:14:37   
projects the whole time. And we're talking about when we're talking about grad school, you know, like like kind of   
2:14:42   
like mentoring, like not mentoring, but like advising, but some folks are are   
2:14:48   
having really interesting discussions about like what do they want to what do they want to do? Like I'm surrounded   
2:14:54   
less so about this the topics, but like I'm really surrounded by people trying to sort out what to do and and like   
2:15:00   
their careers and and and what to study and and how do they do that? And that's that's a related theme to the Nickwick   
2:15:07   
panel that I'll I'll be doing stuff with later too. So, it's just a big nexus around that. I know it's super abridged   
2:15:14   
and brief and I'll leave it there, but I'm just just a lot a lot is happening and I   
2:15:21   
I've kind of been like Rip Van Winkled asleep for for two weeks and and now   
2:15:26   
it's like, oh yeah, like like there's so much happening. So, I'm just trying to, you know, c catch the moving tide again.   
2:15:34   
um now that I'm more functional. So, any any questions or comments before we go? I know I know we're late, but um I   
2:15:41   
appreciate this meeting and and what we're doing here, too.   
2:15:49   
Oh, thank you. Um yeah, so yeah, it's a great update.   
2:15:54   
Thank you, Jesse. Um yeah, a lot of things going on. Congratulations on the Princeton Envision. uh you know getting   
2:16:02   
moving to the next step on that and becoming a historian of the meetings and that um that's always a good sign that   
2:16:09   
you've been kind of recognized in that space. Yeah. Um also thank you for that. And   
2:16:17   
one other thing um uh for anyone in the it's limited right   
2:16:24   
now. It's a p It's basically a pilot program, but I do encourage folks if   
2:16:29   
you're a little tied to anyone in Harvard, it's basically Harvard undergraduates, Harvard juniors, the   
2:16:35   
school for moral ambition. And there have been like some big policy some big buses at at Harvard, Princeton um and   
2:16:42   
Stanford I guess now I just saw today um har the school for moral ambition is doing these pilot programs um to get   
2:16:50   
juniors and underassman juniors to think to basically think about impact with their career. her.   
