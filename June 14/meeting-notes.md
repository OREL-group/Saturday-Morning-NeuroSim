## Meeting Recording

[YouTube link](https://youtu.be/-fg3XRcdE88)

## Mastodon thread

[link](https://neuromatch.social/@OREL/114685499733182113)

## Notes
Reasoning Models (multinational fight) vs. Language Models.

Miles Brundage: Oxford fellow.

* ARC2 is go-to benchmark.

Anthropic circuits —> explainability.

tradeoffs of model capacities are interesting —> planning ahead within a window (token budget, etc).

Audio tokenization: complex forecasting —> time-series reasoning.

https://arxiv.org/pdf/2406.10735v1
https://ravinkumar.com/GenAiGuidebook/audio/audio_tokenization.html

Integrating AI and LLMs into operating systems —> how will Apple do it? Microsoft has Co-Pilot, RedHat is doing this currently. Will be an issue for Fedora.


Lingbuzz —> are models taking over the CogSci literature?

Foundation Model —> language prediction, generative.

ML Street Talk —> LLM arena (benchmark). Benchmarks are gamble, figure out how to iterate on a benchmark.

ARC tries to avoid. Better engineering understanding of token content size.


DeepSeek’s paper was so interesting (hybrid, not a transformer).

is human reasoning the pinnacle of (in evolution) of reasoning?

expertise plays a role in interoceptive taxis.

models open to trivial shortcomings.


A mathematical abstraction of biology —> can you align with biology and behavior?

Connected Papers —> 3 clusters: affective taxis, computational Bayesian modeling, alignment.

how much alignment between agents?

* Rx Infer: Lazy Dynamics: Link ActInf to Tennenbaum, Word to World Models (https://arxiv.org/abs/2403.18829), 2023.


Environments: training zoos. Environmental Complexity: making it more naturalistic.

DeepSeek’s paper was so interesting (hybrid, not a transformer).
is human reasoning the pinnacle of(in evolution) of reasoning?

expertise? Models open  to trivial shortcomings —> thinking (TM).


Loop from animal to world is much richer. Mice don’t just maximize pellets —> does not capture what’s going on.

## TRANSCRIPT 
0:00     
hello good morning morning hello hello     
0:06     
i'm still still walking in to walking into the lab here but Okay     
0:13     
how's everybody doing good good so this week we had a divor     
0:21     
meeting and that was pretty good you can go see the meeting on the     
0:28     
YouTube channel for Divorm then we also had uh open source meeting     
0:34     
yesterday that meeting was um basically updates     
0:40     
for people working on projects a lot of information about the uh DVO     
0:45     
graph repository um there's some interest in the hugging face spaces     
0:52     
which is a nice tool it's sort of a a parallel to GitHub in some ways because     
0:59     
you can store files there store your models uh but also it gives you this new     
1:06     
community of people to spread your model to so this is a machine learning     
1:13     
AI community where people are looking for open source models so we had uh     
1:21     
I was looking at how it's structured and I had forgotten that it was by project     
1:26     
so there's a DVO learn one and I created a one for DVO graph so if you're interested in joining the hugging face     
1:33     
spaces ask for permission granted     
1:38     
um yeah um so yeah I don't know well this     
1:45     
week coming up is the active inference live stream uh than Wednesday     
1:51     
uh around midday in North America it's on the open source um     
1:58     
economics economics of open source and so we talked I think we talked about     
2:04     
that um in last week's open source meeting so that's going to be happening     
2:10     
this week yeah what what kind of speakers I'm not sure who the presenters are for     
2:17     
it but it's that p it's a paper by an external group so they're just kind of     
2:23     
talking about and I imagine it just gets framed in an active inference context uh     
2:30     
people thinking about the problem in that way they do a lot of stuff with like um     
2:37     
yeah they do a lot of stuff with like um I don't know like I don't want to say     
2:42     
cryptocurrency but a similar thing blockchain and they have like a project on that so     
2:49     
it's that might go in that direction or you know something about just pure active influence i'm not really sure     
2:56     
which got you yeah um yeah so and then that's the active     
3:05     
inference institute they have their YouTube channel and you can join in on     
3:11     
that stream they always have streams um like almost every day they seem to     
3:17     
come out so that's um for active inputs     
3:24     
so I guess I should start with this um paper that came out it was from Apple     
3:29     
research it was called the illusion of thinking and it came out I think in the     
3:35     
past two weeks so this is this paper the illusion of thinking     
3:41     
understanding the strengths and limitations of reasoning models via the lens of problem complexity so we've been     
3:48     
talking about uh these chain of thought models and large language models and     
3:54     
also large reasoning models and how those kind of differ from large language models and get you to a place where you     
4:03     
know you have uh more in-depth reasoning as opposed to     
4:08     
like just regurgitating tokens or whatever so we've talked about how     
4:14     
people have used reinforcement learning for that how people are doing other sorts of things and uh in this paper     
4:21     
they're arguing that those types of models also have limitations     
4:27     
which might actually preclude them from being useful for thinking through a problem so that's their and this is a     
4:35     
group of researchers at Apple research they just put Apple on the paper as the affiliation and you know what it is     
4:43     
okay um and I think this was from the archive it's been passed around so I Well maybe     
4:51     
they're publishing it on their research website too but anyways you can imagine     
4:56     
it's pretty it's getting a lot of attention so uh why don't we go through the     
5:02     
abstract um I mean this has direct relevance to a lot of the newer chat GPT     
5:09     
models or the open AI models where you know they have this sort of reasoning     
5:15     
component in them so um the abstract reads recent     
5:22     
generations of frontier language models have introduced larger reasoning models     
5:27     
or LRM that generate detailed thinking processes before providing answers     
5:33     
while these models demonstrate improved performance on reasoning benchmarks their fundamental capabilities scaling     
5:41     
properties and limitations remain insufficiently understood     
5:46     
current evaluations primarily focus on established mathematical coding     
5:52     
benchmarks emphasizing final answer accuracy     
5:57     
however this evaluation paradigm often suffers from data contamination     
6:02     
it does not provide insights into the reasoning traces and structure quality so we talked about this kind of uh I     
6:10     
call them circuit tracing tools but something similar where you're tracing out how the model arrived at an answer     
6:17     
and you can trace it out um neuron by neuron if necessary or unit by unit and     
6:23     
so this gives you this um you know     
6:29     
we have this way of evaluating the answer somewhat although it's not clear     
6:35     
how exactly the thing is being assembled the answer is being assembled we also     
6:40     
have these benchmarks that people lean on to say look we've made great progress     
6:46     
in this area and then the question is of course are these coding benchmarks     
6:52     
useful for a larger application so you know it's kind of if you were to compare     
6:59     
two models you might be able to use a coding benchmark and find sort of better     
7:05     
performing law but if you're comparing it with a cognitive agent or even a     
7:12     
cognitive model that's less it's actually less obvious using a coding     
7:18     
benchmark what the better or if it's if it's     
7:23     
matching the abilities of a cognitive agent     
7:29     
okay in this work we systematically investigate these gaps with the help of controllable puzzle environments that     
7:36     
allow precise manipulation of compositional complexity while maintaining consistent logical structure     
7:44     
so these controllable puzzle environments these are things that you know people use in     
7:51     
or in cognitive science so you'll see some examples of that with     
7:57     
like the Tower of Hanoi for example where you have to you're given this     
8:02     
puzzle where you have to move these rings from uh one rung to another to     
8:08     
another but you have to stack them in order from largest on the bottom to smallest on top     
8:15     
and you have to transfer them according to certain rules so that you end up at the end of the puzzle with satisfying     
8:23     
the conditions of the game so this is where you can test um you know thinking     
8:31     
how you reason out a problem in multiple steps because it takes multiple steps to     
8:36     
get this sort of um answer in in a reasonable amount of time and so you can     
8:42     
count the number of steps it takes to do this and you can examine the process by which     
8:50     
this reasoning unfolds then they talk about compositional     
8:55     
complexity and given our discussion on compositionality that's interesting     
9:01     
because remember compositionality is putting together um an answer or putting together a     
9:09     
complex behavior or you know putting together a sentence in this case or in     
9:15     
the case of like what the linguists think about says compositional complexity is you know you're able to     
9:23     
sort of modify different stages in the reasoning process or constrain it in     
9:28     
certain ways and then get an answer at the end and examine how an answer was arrived at     
9:35     
this setup enables the analysis of not only final answers but also the internal     
9:41     
reasoning traces so remember we're interested in what the model is doing internally not necessarily the output     
9:47     
behavior although the output behavior is important if the output behavior is     
9:52     
matching that cognitive model the reasoning trace is quite different     
9:58     
well that's interesting because you know we don't have the same process going     
10:04     
you know the model could just reproduce the behavior but it could just be like     
10:10     
an imitation or something so we want to know like how it's     
10:15     
arriving at this what is the way it's in which it's reasoned     
10:21     
okay so this offers insights into how large uh reasoning models think in     
10:27     
quotes because we don't know if they actually think or what thinking actually means and hold that thought because     
10:34     
that's something that will come up later through extensive experimentation across     
10:40     
diverse puzzles we show that frontier LRM face a complete accuracy collapse     
10:46     
beyond certain complexities so this is interesting now I guess by     
10:52     
frontier large reasoning models they mean the state-of-the-art models that we see out of um open AI and other uh big     
11:02     
large companies very large models um and so this is interesting because you can     
11:09     
provide it with a very simple puzzle and it's pretty accurate it can like put together an answer but at some point it     
11:16     
does not do that very well or it's very inaccurate so this actually you know kind of feeds     
11:23     
into this idea of you know what how how why and how do     
11:29     
models hallucinate or why and how do models kind of get things wrong how do they go off course     
11:37     
and so this may be a case where if you get to a certain level of complexity and     
11:43     
you know if you're doing things like assembling a a bunch of sentences it may     
11:49     
not reveal itself but if you're trying to do something more complex like understand the reasoning behind say     
11:56     
a passage of text then that may be too complex for the model to deal with     
12:02     
moreover they exhibit a counterintuitive scaling their reasoning effort increases with     
12:08     
the problem complexity up to a point so as the problem complexity increases the     
12:15     
reasoning effort increases so the model puts more effort in reasoning comes up with greater and greater explanations     
12:25     
then declines despite having an adequate token budget so there's this budget of     
12:31     
tokens that it has so it can use those tokens to arrive at these answers it can     
12:38     
devote some of that budget towards uh solving problems     
12:43     
the problem complexity increases so the challenge to the model to spend that     
12:48     
token budget on generating uh you know more elaborate reasoning     
12:56     
increases but then despite having enough token     
13:01     
budget they don't they stop at some point and so it's not a resource     
13:07     
constraint it's something else     
13:12     
by comparing LRM with their standard large language model counterparts and     
13:17     
equivalent inference compute we identify three performance regimes     
13:23     
so they're comparing here these large reasoning models with large language     
13:30     
models okay so they have these two ways of uh sort of building the large     
13:35     
language model we have just the standard vanilla language model and then the reasoning model     
13:44     
uh we identify three per performance regimes low complexity tasks where standard     
13:50     
models surprisingly outperform large reasoning models so this is where you have very low levels of complexity and     
13:57     
you might expect large language models to do well there they tend to outperform     
14:03     
large reasoning models um maybe it's just because that's their     
14:09     
regime and large reasoning models maybe are trying to do too much     
14:14     
and it hurts their performance the second is medium complexity tasks     
14:20     
where additional thinking in large reasoning models demonstrates advantage so this is where we have medium level     
14:27     
complexity where we have to add additional thinking and add additional effort and large     
14:33     
reasoning models take over and then three high complexity tasks     
14:39     
where both models experience complete lapse so this is where we're in this high     
14:45     
complexity domain and both models collapse for reasons     
14:50     
that we're not quite sure of we found that large reasoning models of     
14:56     
limitations and exact computation they fail to use explicit algorithms and     
15:03     
reason inconsistently across puzzles so they don't necessarily generate     
15:09     
algorithms to solve the problem they kind of do this ad hoc     
15:15     
which makes it harder to study and harder to understand why they do this u     
15:22     
you know they don't generate explicit algorithms however so you know this is     
15:27     
of course you could think of generating a specific or an explicit algorithm is kind of like generating a hypothesis or     
15:34     
a formal hypothesis if you present the model with a problem can it reason out     
15:39     
uh several hypotheses to test so the the formality of the methods aren't there     
15:46     
and then they reason inconsistently across puzzles so this is of course linked to this because they're not     
15:52     
generating these formal solutions or these formal candidate solutions and so     
15:57     
the reasoning is inconsistent we also investigate the reasoning traces     
16:03     
in more depth studying the patterns of explored solutions and analyzing the     
16:09     
model's computational behavior shedding light on their strengths limitations and     
16:15     
ultimately raising crucial questions about their true reasoning capabilities     
16:20     
so as you can imagine this is pretty controversial and um it's not clear what this means     
16:28     
but we'll we'll see that there's been a lot of speculation on what it means and     
16:33     
even people who are kind of uh highly critical of it so this is not to     
16:40     
say that you know this is not the be all end all of this debate it's you know kind of dependent on what you're     
16:47     
throwing at the models and how you're testing it so um but let's yeah let's I     
16:54     
want to create a chart here so the first chart is thinking about these levels of     
16:59     
complexity so we have low medium and high     
17:06     
medium and for the sake of argument just say     
17:12     
this is maybe like Well they did say that this was a     
17:19     
positional complexity     
17:27     
and not really sure what they mean by compositional complexity probably have a definition later     
17:34     
and then of course we have our space here where cases     
17:42     
high     
17:55     
And we said that in low LLMs outperform large reasoning models     
18:04     
and then in medium large reasoning models perform large language models     
18:10     
and then in both cases large reasoning models     
18:17     
language models collapse okay so I just wanted to put that on the     
18:24     
table because we'll probably come back to this okay so uh let's get into the paper here     
18:32     
so they talk about large language models having recently evolved to include specialized variants explicitly designed     
18:39     
for reasoning tasks and these are large reasoning models examples include open AIS uh 01 and 03     
18:48     
deepseek R1 which we talked about in depth a couple weeks ago uh claude 3.7 and Gemini thinking so     
18:57     
these are all I guess Gemini thinking is just Gemini um and so you know this introduces this     
19:06     
new artifact characterized by their thinking mechanisms such as long chain     
19:12     
of thought and self-reflection and have demonstrated promising results     
19:17     
across reasoning benchmarks their emergence suggests a potential paradigm shift in how learned language systems     
19:24     
approach complex reasoning and problem solving tasks with some re researchers     
19:29     
proposing them as significant steps towards more general artificial intelligence capabilities     
19:36     
so um despite these claims and performance advancements their fundamental benefits and limitations     
19:43     
remain insufficiently understood so we have some critical questions that persist and I mean persist they they've     
19:50     
been out for like about a year at most so you know um the first is are these     
19:56     
models capable of generalizable reasoning or are they leveraging different forms of pattern matching so     
20:02     
is it that they're going through this reasoning process or are they just simply imitating what they see in the     
20:10     
training data and doing a lot of pattern matching that is impressive but isn't     
20:15     
reason so you want to have that sort of you want to test for the false positive of reason     
20:22     
the second is how do the how do their performance how does their performance     
20:27     
scale with increasing problem complexity so that's what we just drew uh image up     
20:32     
on the board three how do they compare to their non-thinking standard large language     
20:38     
model counterparts when provided with the same inference token     
20:43     
so again we have this budget of tokens um we have these large language models     
20:51     
that have you know we give them the same budget of tokens and the idea is that they're maybe     
20:57     
supposed to be more efficient with their tokens or reach a higher level of reasoning with the same amount of tokens     
21:05     
and so that's what they want to test and they want to see how that compares to standard language     
21:13     
most importantly however what are the inherent limitations ations of current reasoning approaches what improvements     
21:19     
might be necessary to advance towards more robust reasoning capabilities     
21:25     
and so you know one of the things they need to do is come up with a good evaluation paradigm so this figure here     
21:32     
is kind of a summary of what they were doing so this is figure one um so they     
21:38     
want to enable verification of both final answers and intermediate     
21:44     
reasoning traces so they want to be able to an analyze model thinking behavior     
21:50     
so on the upper left hand side of figure one we have we pose to the model we pose     
21:59     
this case of the tower of Koi and so this is the response of the large     
22:05     
language model and it gives a strategy for solving the toworth model and it     
22:12     
gives the number of moves and their composition so you have uh so on the     
22:19     
upper right we see the toweri we said that there are three pegs peg zero peg     
22:24     
one and peg two the idea is that in the initial state these different rings are     
22:30     
on peg one or in peg zero and the largest ring is on the bottom and the     
22:36     
smallest ring is on the top with an intermediate size ring in the middle     
22:41     
the idea is we need to move these rings across from peg zero to peg two     
22:49     
but keep them in the same order so you can't just pick them all up one at a time and move them from peg zero to peg     
22:56     
two because they'd be inverted the largest ring would be on the top and     
23:02     
so you have to use peg one as an intermediary in other words you need to take one or or ring one and you need to     
23:10     
store it on one you need to take ring two and store it on maybe two     
23:16     
you know or maybe one as well take ring three move it over to two take ring uh     
23:22     
two move it back to zero take ring one move it see that's the problem then you     
23:27     
have to move two from zero to two and then uh one from one to two i guess     
23:33     
that's a good solution just eyeball it and so that and they show an example     
23:38     
here of how what the model is producing in terms of an answer maps to the     
23:45     
problem space so you have this initial state this middle state and a target     
23:51     
state and it just generates the sequence of moves that it needs to make to get to     
23:58     
that target state so it composes sort of a final answer from     
24:06     
you know what it's presented with from the puzzle and reasoning trace of course     
24:11     
is apparent here you see the different moves but you actually don't see why it     
24:16     
made those moves it might just be that it saw an example in the psychology     
24:21     
literature and you know it just copied that and gave an answer so is it     
24:27     
actually going through these moves and it can produce an optimal move but it's not like you know     
24:35     
when a a a artificial model plays chess and they     
24:42     
generate strategies and moves and things like that they can beat the human expert we're talking about something where the     
24:49     
model is maybe putting together an answer but it's really mimicking what's in the training set so if this is a     
24:56     
fairly easy problem to solve there might be an example of it in the world somewhere it's just copying     
25:03     
as opposed to say you know coming up with a unique strategy and being able to walk through each implementation of that     
25:10     
strategy and say "Oh this is why this was done." It's unconventional but it's a very interesting move and so     
25:18     
you know this is where it it's not quite clear that the     
25:24     
language models are actually doing the latter so     
25:29     
they're extracting the moves from thoughts for analysis and then they're extracting the final     
25:35     
answer for measuring accuracy so they want to see if the model actually completed the puzzle and then you know     
25:43     
and how many moves and how accurate was it given the number of moves it     
25:48     
committed and then they want to extract all the moves to analyze to see     
25:55     
if those moves are kind of in this in an order that is um sort of a realistic way     
26:01     
of solving it okay yeah uh VD says tower of pheninoi     
26:09     
classic recursion example yes that's that's it's a very simple example of     
26:15     
recursion and then they use this of course in a lot of cognitive science um     
26:21     
experiments to to sometimes in development sometimes in     
26:26     
adults to look at reasoning and study them so you're trying you know it's not an obvious answer you need to make track     
26:33     
multiple things in your head and and you know figure out how to get from point A     
26:39     
to point B so this is the these are the results     
26:44     
here at the bottom uh this is these are graphs show well the first one shows accuracy is a percentage versus     
26:51     
complexity and the way they're measuring complexity is the number of discs so this example shows three discs which you     
26:58     
can do in your head um and you know a large language model probably can do     
27:04     
pretty easily at least generating an answer um and it's not that hard the     
27:09     
complexity isn't that high so you can see in this graph that we have three um     
27:18     
so you have one two three which is in this yellow regime here and in the yellow regime uh cloud 3.7     
27:27     
which is uh sort of the standard LLM which is in red and then the cloud 3.7     
27:33     
with thinking which is the LRM which is in blue they perform about the same task     
27:40     
so there's no difference which is interesting because you know I mean we     
27:46     
can't really say whether it's actually coming up with a sort of a strategy on its own or if it's copying what it sees     
27:52     
in the world but it's a pretty easy thing to do pretty easy thing to generate     
27:58     
then we have this blue regime from three disks to 10 discs so this is where we're adding complexity and we're we're not     
28:05     
adding uh any more rungs we're just or we're or um we're not adding any more     
28:11     
rungs we're just adding more things to move over so you have to uh export a lot     
28:16     
more moves and assemble or compose a much larger answer and so this is where     
28:23     
the thinking model or the LRM exceeds the large language model by     
28:29     
quite a bit you can see that the large reasoning model maintains its accuracy     
28:35     
over 60% until disk 8 whereas the large language model falls off at disk 4 to     
28:43     
below a 40% accuracy and then of course after 10 we have this     
28:48     
third regime which is the pink regime and that is where there's a total collapse of accuracy and for both types     
28:57     
of models you get under 20% so this is interesting they have these     
29:03     
regimes of complexity so you have from 1 to three from 3 to 10 and from 10 to 20     
29:09     
as they tested so if we look at the we create a graph here where we have um     
29:17     
again this this regime I guess it's terms of accuracy     
29:29     
10 three accuracy as a percent     
29:37     
these three regimes so this is where you have     
29:42     
your large reasoning models which have this     
29:48     
preservation in the middle and then the large language models which kind of show     
29:54     
a premature collapse     
30:03     
all right so that's our kind of how we can think of accuracy versus complexity     
30:09     
now the next graph is of course response link so this talks about the token usage     
30:15     
so this is the token budget and so we have complex again these three regimes of complexity going from 1 to three 3 to     
30:23     
10 and then 10 to 20 and so again this is our large language model this is our     
30:28     
large reasoning model and our large reasoning model will use a lot more tokens     
30:35     
and then it'll stop using tokens so this collapse isn't because it's using so many tokens it can't keep up it's     
30:43     
because it just stops doing anything it stops making effort and it holds true     
30:49     
for the large language and the large reasoning and I don't know you know if we go down     
30:55     
to the like discussion they might discuss why that is but um basically there's this huge ramp up in token usage     
31:02     
in this middle regime okay so we go back over to our board you     
31:08     
know we have this graph where now we have token budget I guess um     
31:16     
here 320     
31:26     
and we have our language model here     
31:32     
so a few more tokens here and then it collapses back up     
31:38     
and then our large reasoning model is there's a huge investment in use of tokens here and it collapses back up     
31:47     
and so this is the token budget i'm actually really fascinated by this     
31:52     
because I'm thinking in terms of like I don't know if people are familiar with this old game called core war but this     
32:00     
is a way that um people have looked at how programs of different classes will     
32:08     
use the computational budget available to them so they'll use you know some     
32:14     
agent classes of agent will use different strategies to exploit the number of uh compute cycles in the CPU     
32:22     
and you can have these really interesting games where uh different classes of agent will compete against     
32:28     
one another or form these sort of ecosystems where they all have their own sort of     
32:35     
niche and you know it's not that that's what we're dealing with here but we're     
32:41     
dealing with a finite resource which is this token budget or I guess a semi-finite resource and we're seeing     
32:48     
how they use it in terms of kind of producing a solution or producing a     
32:54     
competency as Michael Leman said in this case we don't get a competency     
33:00     
we get this collapse so we get sort of this you know no competency here but we have     
33:07     
maybe a semicompetency here so it almost looks like you're going to develop some     
33:13     
sort of reasoning here and then you basically lose it at at a certain budget or at a certain level of investment     
33:21     
um then we have complexity and position with thoughts or within thoughts so I'm     
33:26     
not sure what this means but it you know basically looks at correct solutions     
33:32     
versus incorrect solutions so um when we get to uh within this uh low level of     
33:39     
complexity we have more correct solutions and incorrect solutions and     
33:45     
then with uh the second medium regime we get a lot of lot more correct than     
33:51     
incorrect solutions and then that's where they're tracking stop so basically     
33:57     
I don't know if this is counterintuitive uh you get more incorrect solutions     
34:03     
within thoughts here and then more correct solutions in this medium area of     
34:09     
uh complexity and I'm not sure if that has something to do with the token budget but um let's see if they say     
34:17     
anything legend here oh okay uh thinking tends to     
34:24     
find answers early at low complexity and later at high complexity so it's     
34:29     
basically finding answers at a certain point in the chain of thought in failed cases it     
34:36     
often fixates on an early answer wasting the remaining token budget that's     
34:41     
interesting so gets fixated on early wrong answers and spends all of its     
34:48     
token budget or spends a lot of its token budget on exploring that wrong answer and that's you know kind of a     
34:54     
thing with human reasoning where people you know we have this expression cut our losses so if you find something is maybe     
35:02     
and if not a very good answer you stop exploring that answer and you move to a     
35:08     
new potential answer as and in this case what the large language models are doing     
35:13     
or large reasoning models they're fixating on one answer and they're not using that sort of     
35:20     
that sort of principle both cases reveal inefficiencies in the reason process     
35:30     
so that's what we're dealing with here um and so let's see if we have any other     
35:36     
thing okay here these are their key contributions as they see uh we question     
35:42     
the current evaluation paradigms of large reasoning models on established ma math benchmarks we show that the     
35:49     
state-of-the-art in large reasoning models uh still fail to develop generalizable problem solving     
35:55     
capabilities with accuracy ultimately collapsing to zero we find that there     
36:01     
exists a scaling of and large reasoning models reasoning effort with respect to     
36:06     
problem complexity evidenced by the counterintuitive decreasing trend in the     
36:11     
thinking tokens after a complexity point so this is where you know again we     
36:17     
talked about that that decrease with complexity     
36:22     
we question the current evaluation paradigm based on final accuracy and extend our evaluation to intermediate     
36:28     
solutions of thinking traces with the help of deterministic puzzle simulators     
36:35     
uh our analysis reveals that as problem solve complexity increases correct     
36:40     
solutions systematically emerge at later positions and thinking compared to incorrect ones so this is where you know     
36:48     
you have to explore something for a while before you get to the correct solution add what they're     
36:56     
what the language models are doing is kind of not understanding that long term     
37:03     
of reasoning and just kind of thinking oh this is the right answer definitely the right answer and we'll explore that     
37:09     
to its logical conclusion whereas you know maybe humans playing this puzzle     
37:16     
might explore the model that might explore the puzzle and then they oh okay     
37:22     
I get it now come up with this sort of aha moment of     
37:28     
getting the right answer at some point after playing with the program     
37:33     
um and then we uncover surprising limitations in large reasoning models ability to perform exact computation     
37:41     
including their failure to benefit from explicit algorithms and their inconsistent reasoning across puzzle     
37:47     
types so um they kind of also unpack this     
37:54     
whole sort of these trends that we were talking about um     
38:00     
so hers despite these their sophisticated self-reflection mechanisms learn through     
38:07     
reinforcement learning so these are the large reasoning models and we talked about how you basically have this large     
38:12     
language model with this reinforcement learning step on top and the idea is that you know the self-reflection is the     
38:18     
reinforcement learning so you have the generated answers and then you have this     
38:24     
sort of reinforcement that gives you this ability to self-reflect and get rewarded for the     
38:30     
proper sort of self-reflections and so this is you know thought to be uh     
38:37     
sort of a I guess you could call it a stop gap for the lack of reasoning that a mark language model     
38:44     
um but despite the second level or the second layer these models fail to     
38:50     
develop generalizable problem solving capabilities for planning tasks with     
38:55     
performance collapsing to zero beyond a certain complexity threshold     
39:00     
and then of course when you compare large reasoning models and large language models under equivalent     
39:05     
inference compute it just means I guess that they have the same compute power     
39:10     
and the same token budget it reveals three distinct reasoning regimes for     
39:16     
simple lower compositional problems standard large language models demonstrate greater efficiency and     
39:22     
accuracy as problem complexity moderately increases however thinking models gain     
39:28     
an advantage however when problems reach high complexity with longer compositional depth both model types     
39:35     
experience complete performance collapse notably near this collapse point and you     
39:42     
can think of this collapse point as sort of like a phase transition or something like that large reasoning models begin     
39:49     
reducing the reasoning effort measured by inference time tokens as problem     
39:54     
complexity increases despite operating well below generation inference     
40:00     
this suggests a fundamental inference time scale in larger reasoning models reasoning     
40:07     
capabilities relative to the problem complexity so that's interesting it may     
40:12     
be a time scaling limit that we're dealing with so as we move out in terms     
40:19     
of the number of tokens here we actually have a time link so like these are of     
40:25     
course our I'm sorry not number of tokens number of uh moves or number of     
40:32     
discs translating the number of moves this is a time parameter as well as sort     
40:37     
of a complexity point so this is where we're moving forward in time and this is taking longer and     
40:44     
longer as you're adding discs so from three discs to 10 discs to 20 discs and     
40:51     
you know you're adding time into that problem     
40:57     
okay um finally our analysis of intermediate reasoning traces or thoughts reveals complexity dependent     
41:04     
patterns in simpler problems reasoning models often identify correct solutions     
41:10     
early but inefficiently continue exploring alternatives incorrect alternatives and overthinking phenomen     
41:17     
so they're overthinking the problem or they're overthinking     
41:22     
um some of these incorrect alternatives you know it's like don't overthink the     
41:28     
problem it's a very simple answer and so you being very conscientious     
41:35     
develop this very complex hypothesis and you explore it to its extent and you're     
41:43     
continuous you continue to be wrong because you can't rescue the hypothesis     
41:48     
it has like a fatal flaw in this case the u strategy is a fatal     
41:54     
flaw and part of reasoning is identifying when there's a fatal flaw and either fixing that fatal flaw or     
42:01     
moving on to something else so that's what they're talking about overthinking     
42:07     
at moderate complexity correct solutions emerge only after extensive exploration of incorrect paths     
42:15     
so these are of course again they're not like fixing this in at     
42:20     
moderate complexity it's just that they're investing a lot of tokens     
42:25     
in kind of exploring these alternatives alongside the correct     
42:33     
or or correct strategies and they're a able to     
42:38     
maintain a higher level of performance just simply by having a lot of things     
42:45     
that they're doing so they're dumping everything into their token budget here     
42:50     
they're maintaining this remember the accuracy falls in this middle regime but     
42:56     
not as much as in large language models so that reasoning step that reinforcement learning step is doing the     
43:03     
work of keeping the accuracy up okay so they're using tokens to mask its loss of     
43:12     
performance and then in the in you know when you reach a certain level of complexity that     
43:19     
just collapses entirely okay um this indicates large reasoning     
43:26     
models possess limited self-correction capabilities that while valuable reveal     
43:32     
fundamental inefficiencies and scaling limitations okay so we did these points     
43:42     
um they you know they talk about some of the existing benchmarks these math and puzzle environments so     
43:50     
they actually did a number of puzzle environments they did the tower of Hanoi which is this model we talked about they     
43:56     
did checkers jumping which is maybe a more conventional test of strategy     
44:03     
uh river crossing where you have this you have to get things across the river in multiple steps and then blocks world     
44:10     
where you have to move things from one side of the screen to the other in terms     
44:15     
of moving these blocks in a certain order and so this is all kind of like     
44:21     
you know you have these multi-step problems you have to kind of come up with these long chains of strategy fit     
44:29     
together you have to compose a strategy out of these discrete loops that's     
44:34     
basically what we're doing okay so then they talk about what happens inside the thoughts of reasoning     
44:40     
models and so they conducted a fine grain analysis of the reasoning traces     
44:47     
and so they showed their puzzle setup in figure one     
44:52     
and uh they extract and analyze the intermediate solutions explored within     
44:57     
the model within the thoughts of a model with the help of puzzle our     
45:04     
investigation examines patterns and characteristics of these intermediate solutions     
45:09     
their correctness relative to their sequential position in the reasoning process and how these patterns evolve     
45:14     
with increasing problem complexity so they focused on the reasoning traces of cloud 3.7 sonnet thinking across our     
45:22     
puzzle suite for each intermediate solution identified within the traces we     
45:28     
recorded one its relative position within the reasoning trace so this is normalized by total thought length so     
45:35     
basically you have this long reasoning trace that comes out figure out where     
45:41     
things happened in what position its correctness is validated by our     
45:46     
puzzle simulator so is this a correct answer or is this a correct move or is this a optimal move of some type     
45:54     
and then three the complexity of the corresponding problem so how complex is the problem     
46:00     
so that allowed them to characterize the progression and accuracy of the solution throughout the reasoning process     
46:09     
so this uh figure seven here shows kind of this reasoning trace     
46:16     
so we we saw the tools for sort of tracing things through     
46:23     
a neural network um in in a I think two weeks ago maybe     
46:28     
or one week ago this is showing something else this is showing the output behavior and kind of tracing     
46:35     
through this chain of of strategies in assembling in a certain way so this uh     
46:43     
on the left is the tower of Hanoi or the Upper left is the tower of Hanoi     
46:49     
the bottom left is Blox World the upper right is Checker jumping and the lower     
46:57     
right is River Crossing so we're looking at figure 7A we're looking at these four graphs     
47:02     
and then on the right in figure 7B we're looking at the tower of noise specifically and looking at these um     
47:10     
chains of length so from n= 1 to n= 10     
47:16     
and then we're looking at solution accuracy versus position in theory so let's start with the tower of Henoi     
47:23     
we track the incorrect solutions and the correct solutions so as we move along we get um     
47:32     
so the position and thinking I guess goes from zero to one this is normalized     
47:38     
um the correct I guess the correct answer goes down in the position and     
47:44     
then back up and the incorrect position in thinking goes up down and then down     
47:51     
so it becomes like at a lower the incorrect answer is lower in terms of     
47:56     
its position the correct answer is higher in terms of its position for total four so they kind of cross at a     
48:03     
complexity of four four discs in blocks world we're dealing with blocks instead     
48:10     
of discs and in this case the position of thinking doesn't really change that     
48:16     
much with the correct answer coming a little bit later in the position than     
48:21     
the incorrect answer river crossing um I'm not sure what's going on with that     
48:28     
but the uh I guess the incorrect answer is relatively weight the position of     
48:34     
thinking uh and then checker jumping is where again the there's no crossing of the     
48:41     
correct and incorrect answers the correct answer comes later than the incorrect answer it's positional     
48:47     
thinking and so that you know this just shows across these different examples     
48:54     
um and it says that simple problems for okay so let's let's see     
49:02     
uh so if we go to I guess the right is figure 7B so for figure 7B     
49:09     
solution accuracy versus position and thinking is shown for the tower of Hanoi     
49:15     
at different complexity levels simple problems which again is that regime of     
49:21     
one to three units show early accuracy declining over time which is indicative     
49:26     
of overthinking moderate problems which are uh and four     
49:31     
through seven show slight improvement in accuracy with continued reasoning     
49:37     
complex problems and then uh in this case uh more than eight discs or a     
49:44     
complexity of greater than eight or greater or equal than eight exhibit     
49:50     
consistently near zero accuracy indicating complete reasoning fail you     
49:55     
can see here that like we have from n= 1 to n= 10 we have this position in     
50:02     
thinking in terms of tokens and you know we have like these     
50:07     
shallower sort of chains for smaller problem sets and then longer     
50:14     
chains for larger problem sets and you can see that basically as the problem set gets longer     
50:22     
the position and thinking is you know there's a the accuracy is generally low     
50:27     
but it's really low once you get past I don't know a thousand tokens or maybe     
50:34     
well maybe 4,000 tokens so you can see that there's this kind of collapse this     
50:39     
is a kind of a hard graph to interpret but in that case you can see what     
50:44     
happens there so again they they give some open questions about this puzzling behavior     
50:52     
um and you know they kind of talk about some of this and then they they have this conclusion     
50:58     
which is in this paper we systematically examine frontier large reasoning models     
51:04     
through the lens of problem complexity using controllable puzzle environments our findings reveal fundamental     
51:11     
limitations of current models um     
51:16     
and they talk about the overthinking they talk about some of these surprising     
51:22     
results on large reasoning models that lead to several open questions for future work most notably we observe     
51:29     
their limitations in performing the exact computation for example when we provided the solution algorithm for the     
51:36     
Tower of Hanoi to the models their performance on this puzzle did not improve which is interesting because you     
51:42     
would think if you gave them the algorithm that they would just copy the algorithm but that's not actually what     
51:47     
happened the implication here is that there's no use of an algorithm it's just     
51:53     
generating these strategies independent of an algorithm and independent of any     
51:59     
sort of systematic thinking or so it seems um moreover investigating the first     
52:06     
failure move of the models revealed surprising behaviors for instance they could perform up to a 100 correct moves     
52:12     
in the Torah of Hanoi but fail to provide more than five correct moves in the river crossing business so it's not     
52:19     
really dependent on complexity it's just the type of game and so the tower seems     
52:26     
to be better or it seems to be better at toweri than river crossing for whatever     
52:32     
reason we believe our results can pave the way for future investigations in the     
52:38     
reasoning capabilities of the system so again this this result of tower canoy     
52:43     
versus river crossing is important because it's not based on complexity per     
52:48     
se it's based on sort of the structure of the game or the structure of the puzzle     
52:54     
now I wanted to get into a few more things actually Morgan if you wanted to make some comments here     
53:00     
well it's um you know as you know this paper generated a lot of     
53:06     
strong feelings in the uh machine learning community or I should say the     
53:13     
the reasoning models community um     
53:18     
and so it's it's it's interesting to hear i mean thanks for     
53:24     
going over this because um all I really caught was all the     
53:30     
social media around it oh yeah you know um and did they release this was I think     
53:38     
part of um is it was Apple's developer conference oh yeah yeah wwe     
53:44     
yes and and so there's also a lot of um     
53:52     
you know there's a lot of like Apple you know Apple's essentially absent from     
54:00     
kind of AI work right and and how much     
54:05     
is this like um you know when when Apple rolled out you     
54:11     
know it's like like Apple is a is a ruthless multinational like all of them     
54:19     
right and yet like somehow they've managed to have this uh this kind of um     
54:26     
privacy exemption in terms of people's minds you know right and and and you know of     
54:34     
course like this is just how do you how do you undercut your competitors right     
54:40     
so it's just like like like We're gonna cut off Facebook's data flow from our     
54:47     
customers right not not as some you know but but we'll market it as like hey     
54:54     
we're doing you guys all a big favor right it's simultaneously     
55:00     
they start selling that exact same data stream right right you know like like     
55:09     
we're just not giving it to Facebook first yeah um uh so     
55:16     
I mean it is funny right like like a lot of I mean um Miles Brundage     
55:24     
is this one guy um I don't know if I'm getting his last name right anyway he     
55:32     
I don't even know who he works for now like OpenAI or something but but he he     
55:39     
was a fellow at Oxford for some time period and we commiserated about the     
55:44     
lack of burritos there um and uh uh     
55:50     
the anyway like like his comments about this     
55:55     
were like you know it's a good you know it's they're not     
56:02     
saying anything that other people haven't said right but but um for for     
56:07     
some reason he was criticizing their roll out or presentation something like     
56:14     
that and um uh it seemed like that there was     
56:20     
a lot of anyway point being that like you know     
56:26     
it is super interesting um arc arc 2 is still like the go-to     
56:34     
benchmark right yeah and and like and I think 03     
56:41     
um is the you know considered the the frontier     
56:49     
edge in terms of of performance across across arc tasks     
56:55     
something like that right and um yeah so it was it was interesting you     
57:03     
know it was just like like to get past the     
57:08     
the the multinationals fighting yeah yeah it is interesting in terms of just     
57:15     
like what do they add to the story beyond anthropics that like the the what you     
57:23     
presented last time around um or or like was it a couple weeks ago     
57:29     
in terms of like anthropic circuits and Oh yeah yeah yeah like like like again     
57:34     
like Anthropic's entire case and     
57:41     
sorry who do they actually represent are they Amazon     
57:46     
like like like again like I was about to say like Anthropic's you know an independent player but not really yeah     
57:53     
um but they they've certainly tried to emphasize their     
58:01     
explanability right or Yeah yeah um and     
58:08     
so that that was that was interesting and and the     
58:14     
the the the tradeoffs that you're discussing was was     
58:19     
also interesting and and I guess you know it makes me     
58:27     
Yeah it's like like at a certain point it's it's definitely worth diving into     
58:33     
these models a bit more and and um I I     
58:38     
ju just there's some new stuff I I I don't know if I've posted it here but     
58:44     
just in terms of of audio audio tokenization     
58:50     
and which is of course kind of the same thing as saying time series tokenization     
58:56     
yeah yeah and and like you know like again like I still don't I still don't     
59:05     
know if you're looking at reasoning you know um but     
59:14     
but you know again like comp or complex     
59:19     
forecasting right right yeah you know and and and     
59:25     
you know like how does that differ from planning um but like like they do they seem     
59:33     
powerful and they seem to be you know stretched at a point now or you know     
59:40     
developed to a point now where you know there's there's certainly really interesting engineering     
59:47     
going on that that's worth understanding so anyway     
59:53     
more more stuff to study     
59:59     
yeah I think it's interesting Apple kind of like um you know they're they're struggling with Apple intelligence and     
1:00:06     
like they just say "Well look this is why I Well yeah yeah yeah and it's just     
1:00:12     
like like they're still I mean it's it's funny because it's just like they still     
1:00:18     
haven't even gotten Siri to be uh Alexa     
1:00:23     
you know like like they are I I don't know what any Yeah yeah i'm I'm glad     
1:00:35     
that I am not following what the developer roll     
1:00:40     
out was you know what their what their foundation model strate you know     
1:00:47     
foundation model integration with OS strategy is     
1:00:52     
um yeah I I I will say it it's it's I know it's going to be an issue um for     
1:01:01     
Fedora like like you know certainly IBM is trying to push Red Hat to adopt     
1:01:11     
you know like again like this is the this is the buzzword of the decades     
1:01:16     
you know so somehow integrating this is is what OS     
1:01:23     
manufacturers are supposed to be working on and um Yeah     
1:01:31     
yeah well yeah and again yeah I think that the you mentioned that you found the trade-offs interesting i do too i I     
1:01:39     
thought that was that that was something right and and it speaks Yeah again like     
1:01:46     
like there's that that's saying something about your kind of     
1:01:53     
planning ahead window or Yeah yeah you know like like     
1:01:59     
Yeah yeah I mean the work on this reasoning these these reasoning models is is     
1:02:06     
certainly interesting and and um you know but like hopefully more work     
1:02:13     
connecting it like more work like this more work I mean you know again this     
1:02:18     
just strikes me as somewhat Gary Marcusish or Emily Benderish they had mentioned     
1:02:24     
that about the uh Gary Marcus I don't know if he like put up a blog post on this but I     
1:02:30     
is definitely in his wheelhouse i I don't I don't have it up no yeah yeah yeah yeah yeah is he saying something     
1:02:38     
like "Hey this is what I've been saying." Yeah i think it would tend to be like an I told you so so I didn't really want to get into that but Yeah i     
1:02:46     
I didn't feel like reading another humor     
1:02:51     
yes yes um Well still good good yeah um     
1:02:58     
I I wonder I wonder what um you know I like like is this taking over     
1:03:06     
cogsai literature like like you know we've looked at     
1:03:12     
lingbuzz you know ling like the ling archive for linguistics and like you     
1:03:19     
know how much how much these these models have     
1:03:25     
somewhat or at least that one paper dominated     
1:03:31     
um you know is this uh is this also sucking all the oxygen from from Kogai     
1:03:39     
oh I'm sure it probably is to some extent but well I mean sucking the oxygen meaning like everyone's like     
1:03:46     
fascinated by it well like like that that either you know     
1:03:51     
if you're a Coxai researcher if you're not if you're not looking at     
1:03:57     
you know parallels between LLMs and humans right right that you're you know     
1:04:04     
you're pay right oh yeah I'm sure they probably are because this is you know kind of like um     
1:04:12     
you know looking like maybe 20 years ago between robots and humans or something     
1:04:17     
like that although it's not as hype it wasn't as hyped to say so     
1:04:23     
yeah so yeah that'd be interesting to see how Cobbsai is integrating this kind     
1:04:29     
of research because it's definitely like I said this is very Cobbsai oriented like you know you could learn     
1:04:36     
direct barrels between how humans perform on or in development how     
1:04:41     
children perform on toenoid versus adults and see that kind of you know     
1:04:47     
that progression of a of a set of strategies or a way of thinking and I     
1:04:53     
mean I You know but I mean is this is this     
1:04:59     
is this an artifact though that they've trained on our language what do you mean like like     
1:05:07     
you know I mean again it's they're foundation models right so so it it's     
1:05:15     
come first from training on language prediction and certainly you know which     
1:05:23     
suggests a     
1:05:28     
you know not not not necessarily a world model in the sense of like outside but     
1:05:34     
like that you've generated this model about language     
1:05:40     
for for generative model for language yeah and and so     
1:05:47     
yeah anyway yeah yeah the training aspect is interesting because like I     
1:05:52     
said you know you could have like there this is not like an unknown puzzle like     
1:05:58     
people this has been solved in say like in the literature they talk about how people solve it so if you train your     
1:06:05     
model on like like cockai papers there it is there's the answer but would     
1:06:12     
you be able to get independent solutions or really interesting like you     
1:06:18     
know in chess there's always this innovation to kind of figure out strategies and sometimes they look     
1:06:23     
really weird but they're effective and it's like no one knows exactly why or how people came up with this it's just     
1:06:30     
the pressure to win or the pressure to do well and then say okay well let's throw everything we know out and let's     
1:06:36     
try this new strategy you know I don't know if you see that here but like that would be kind of to me a hallmark of     
1:06:42     
like oh yeah this thing maybe really is thinking about     
1:06:48     
Yeah yeah i I I did they did they mention the arc prize or the arc     
1:06:54     
challenge directly i don't I mean you know like you know it is I don't know if     
1:07:01     
you saw this but the I think I put it in data science ML um     
1:07:09     
but it was a machine machine learning street talk about the company's gaming     
1:07:19     
like LLM arena is it is that what it's called or you know it's like it's like     
1:07:26     
an arena benchmark and and     
1:07:31     
you know the that basically like people     
1:07:38     
you know using using metrics starting to gain whatever system that you're trying     
1:07:45     
to judge them by right because billions of dollars are you know there are there     
1:07:51     
is there are prizes at the end of this rainbow right and um uh so I mean I I     
1:07:59     
would say like if if if anything like Apple wasn't harsh enough in that beginning part in terms it's not just     
1:08:06     
data contamination or you know like like Yeah it's not just that you might be     
1:08:12     
training on something that's relevant it's it's that your benchmarks     
1:08:18     
um are gameable in in various ways that that's what the machine learning street     
1:08:24     
talk video is about was like like     
1:08:30     
ways in which people have figured out how you can iterate on the the benchmark itself um     
1:08:39     
the the Yeah but that that that's not re you know     
1:08:45     
again that's not that's definitely not reasoning yeah right yeah um anyway but     
1:08:53     
like and then how much the art goes out of its way to make sure that it's it's     
1:08:59     
it's tests are are not public or Yeah     
1:09:07     
yeah it's like avoid like looking at the test before you take it basically yeah     
1:09:12     
like like like like again like certainly actively trying to be     
1:09:20     
ungameable anyway it's um     
1:09:29     
still still the benchmark to be yeah so     
1:09:34     
as you might well as you mentioned this was of course     
1:09:39     
so yeah as you mentioned this was of of course kind of contentious     
1:09:45     
uh the illusion of thinking and so this title the illusion of thinking     
1:09:50     
was sort of mocked in this response paper the illusion of the illusion of     
1:09:56     
thinking this is a comment on this paper you just saw this was published on the     
1:10:02     
archive like this week I think oh that's funny yeah so this is uh so this paper     
1:10:09     
that we just looked at showj J at all report that large reasoning models exhibit accuracy collapse on planning     
1:10:17     
puzzles beyond certain complexity thresholds we demonstrate that their findings primarily reflect experimental     
1:10:24     
design limitations rather than fundamental reasoning failures so their     
1:10:29     
analysis reveals three critical issues to T tower of Hanoi experiments systematically exceeded model output     
1:10:36     
token limits at reported failure points with models explicitly acknowledging     
1:10:42     
these constraints and their outputs then two the author's automated evaluation frameworks failed to     
1:10:48     
distinguish between reasoning failures practical constraints leading to mclassification of model capabilities     
1:10:56     
and then three their river crossing benchmarks include mathematically impossible instances where n equal to or     
1:11:04     
greater than six due to insufficient vote capacity yet models are scored as     
1:11:09     
failures for not solving these unsolvable problems and so when we control for these experimental artifacts     
1:11:17     
by requesting generating functions instead of exhausted move lists pre preliminary experiments across multiple     
1:11:23     
models indicate high accuracy on Tower of Hanoi instances previously reported     
1:11:29     
as complete failures um these findings highlight the importance of careful experimental design so I don't know what     
1:11:36     
they're doing here in terms of like I guess they're doing uh they're kind of     
1:11:42     
work walking through some of these things that they mention so um the     
1:11:47     
consequences of rigid evaluation physical token limits drive apparent     
1:11:52     
collapse and alternative representations restore performance     
1:11:58     
um and then re-evaluating complexity claims so thinking about how complex the     
1:12:04     
problem actually is and so then future work should design evaluations that     
1:12:10     
distinguish between reasoning capability and output constraints verify puzzle     
1:12:16     
solvability before evaluating model performance three using complexity metrics that     
1:12:22     
reflect computational difficulty not just solution length or consider     
1:12:27     
multiple solution representations to separate algorithmic understanding from execution     
1:12:34     
and so the question isn't whether large reasoning models can reason but whether our evaluations can distinguish     
1:12:40     
reasoning from typing i guess uh this is just kind of thinking     
1:12:46     
about you know yeah that's interesting that that that     
1:12:53     
makes a lot of s now certain again like certain social media posts make more     
1:12:59     
sense than that like like that's okay I see I see what they were getting at when     
1:13:05     
they said like they they pointed out flaws to the     
1:13:10     
authors and uh um     
1:13:17     
yeah okay it it still seems I mean I I still want to have a better     
1:13:25     
engineering understanding of the token context     
1:13:34     
size and and it's its role     
1:13:40     
in these in these um evaluations     
1:13:46     
yeah um I think maybe one of the things they're suggesting too is that you know     
1:13:51     
if you give if you run the model enough times it might generate instances where it actually solves the problem instead     
1:13:57     
of collapsing so it's like if you get into that latter regime you know it might be harder to generate a correct     
1:14:05     
instance but you can solve it it's just that it's less like reliable     
1:14:11     
i think that may be kind of what may be happening there or that it's not     
1:14:18     
um yeah I mean it's it's obviously going to be harder because it's a more you     
1:14:24     
you're they have to do more generate more to get to the answer so it's not     
1:14:30     
going to maybe always get the right answer but it can get the right answer much like in humans when you're faced     
1:14:36     
with a really hard puzzle or you know like if you have maybe a few people in     
1:14:42     
the world that can solve a Rubik's cube when you scramble it up and and you know you say solve this in a minute and how     
1:14:49     
many people can do that not a lot i mean we all have reasoning capabilities but some people can do it very you know they     
1:14:56     
they can become competent in that or are competent in that and a lot of people could never be competent in that for     
1:15:02     
whatever reason it's just not something they're going to be able to do or maybe     
1:15:07     
that they train enough but if they train enough you have to uh really kind of     
1:15:13     
train just at that thing so     
1:15:22     
so definitely a lot of cognitive science here that's interesting and not just     
1:15:27     
like computer science um the not I mean these these are to a     
1:15:35     
certain some extent you know Yeah like like you're saying like these are interesting     
1:15:42     
alternative cog model yeah yeah     
1:15:50     
so I'm not a huge fan of Reddit but like here it is um     
1:15:55     
well you'll see what I mean um this is on our local llama this is apples in     
1:16:01     
research paper limitations of thinking models and so this is kind of goes     
1:16:06     
through this paper and some of the comments um so you know it kind of talks     
1:16:11     
about the brief takeaway of of well for ChromeX anyways a brief takeaway     
1:16:19     
uh a number of points regular models beat thinking models on simple tasks     
1:16:24     
thinking models beat regular models of medium complexity tasks both types of models suffer from high complexity tasks     
1:16:32     
even at short prompt length uh thus no relevant long context degradation impact     
1:16:39     
thinking models allocate more reasoning tokens with increased task complexity yet at some point start reducing them     
1:16:46     
and thus quality result quality suffers models tend to stick to wrong early     
1:16:52     
answers which aligns with the multi-turn research i don't know what that is but there's this multi-turn     
1:16:58     
convers getting lost in multi-turn conversation i guess this is where the     
1:17:04     
model has to take turns in conversation conversation which is a form of     
1:17:10     
improvisation and so that you know I don't know too much about that but I guess that's kind     
1:17:16     
of consistent with that and then problem solving doesn't generalize they can they     
1:17:21     
can be doing okay in some puzzles yet utterly fail in others despite no increase in difficulty     
1:17:28     
and so this this person here Sky Feisty Llama 8 says     
1:17:35     
uh with the problem solving doesn't generalize the AI believer's answer would be to increase generalization     
1:17:41     
until the model can answer anything and everything i think we are starting to see the limitations of a transformer     
1:17:47     
architecture to encode human knowledge it only works for finding similar patterns but isn't capable of     
1:17:54     
intellectual leaps like those aha moments like we said not yet anyway     
1:18:00     
um and then this person uh seasoned curies again this I'm not I don't make     
1:18:07     
up these screen names uh it makes me wonder whether there's value in trying to train models and find     
1:18:15     
and apply known algorithms correctly as a teacher I know that there is variance among the students on their ability to     
1:18:21     
apply step-by-step problem solving effectively so this is something in education that you try to get people to     
1:18:28     
do um even when given directions people find this very hard perhaps there's room     
1:18:33     
for teaching large language models metacognitive strategies we've talked about this like metacognition and uh     
1:18:40     
talked about like you know a lot of the aspects of how you know humans are not     
1:18:46     
always good reasoners we like to think it's a human Yeah it's a human attribute but it's not something that comes easy     
1:18:54     
especially multi-step reasoning yeah yeah i mean this is this is this is     
1:18:59     
again why like like Deep Seek's paper was so interesting right because because     
1:19:06     
you know has it showed you what else they were doing     
1:19:13     
right like like it's not just a transformer right you know I     
1:19:20     
Yeah and just just just how hybrid these these models are getting to to     
1:19:28     
specifically do well on these the on this this kind     
1:19:34     
of like task set right um sorry could you go back to to Reddit     
1:19:41     
just real quick because um you uh you     
1:19:47     
missed uh stuffy was it stuffy stuff     
1:19:54     
9,01 trillion quadrillion     
1:20:00     
i mean you know again this is it's comments like this that make the     
1:20:05     
internet a wonderful place yes     
1:20:15     
you know the comment after alarms and timers     
1:20:22     
don't     
1:20:35     
Yes yes you can't you can't g keep humor um     
1:20:40     
uh uh yeah like     
1:20:47     
here's here's a statement um Reddit made some good points yes     
1:20:57     
that's that's Yeah yeah so I'm not going to go through the whole Reddit post uh     
1:21:02     
thankfully but I think you know this is like gives you some idea of how people are thinking about this and um you know     
1:21:10     
it's it's it's it's social media so take it with a grain of salt and of course     
1:21:15     
there were a lot of social media posts uh one I found interesting this is Carl     
1:21:20     
Bergster on Blue Sky he's the author or one of the authors of the uh book machines which is like kind of     
1:21:27     
how to think about large language models and I I just find you know that interesting um so he did a post on this     
1:21:35     
paper the illusion of thinking um so this is a short thread um and he says     
1:21:42     
"My sense over the past 6 months or so is that chain of thought prompting is used in chat GPT0 or 0.3 improved     
1:21:50     
substantially upon previous systems such as a chat GPT 4.0 at least for certain     
1:21:57     
tasks but how revolutionary is it?" Uh the authors set out to assess     
1:22:03     
systematically the reasoning ability of chain of thought systems in a structured domain and that's why they use logic     
1:22:09     
puzzles that can be solved with recursive algorithms so we talked about the tower of Hanoi where the uh river c     
1:22:17     
riverboat crossing uh problem these findings are interesting for a domain     
1:22:23     
characterized by extremely simple puzzles uh the basic models without coot     
1:22:29     
do as well as or better than the coot models and use a lot less compute     
1:22:34     
however for for medium difficulty puzzles coot dramatically outperforms basic which we showed and talked about     
1:22:42     
but then as you get to difficult puzzles coot fails as well the thing is they're     
1:22:47     
only difficult puzzles if you try to brute force them so this is a part of an algorithm we were talking about that     
1:22:53     
algorithms allow you to find a strategy that's not a brute force strategy so I     
1:22:59     
could just brute force the thing uh you know basically uh try every solution or something like     
1:23:07     
that but the algorithm is actually the thing that you want to see because it says that you're reasoning out sort of     
1:23:14     
this generalizable strategy that should work so like a search algorithm of     
1:23:20     
course doesn't just try to search everything one by one element i mean that's just you know any agent can do     
1:23:27     
that you have to have some strategy where you u you know have a pile of uh     
1:23:33     
tokens and you split it into parts and then you search it for maybe the largest     
1:23:39     
token or the most significant token and you keep doing that recursively until you find a subset and then search that     
1:23:47     
and it you know it's it's a way to sort of cut down on your complexity or make     
1:23:52     
that complexity smaller and but then maintain your accuracy and that's what     
1:23:58     
it's not doing and that may be what's going on in this regime here the pink regime is it's not applying an     
1:24:03     
algorithmic solution so it can't maintain that accuracy it's just trying     
1:24:09     
to brute force everything and as a result gets low accuracy even if it can     
1:24:14     
solve it it's not a you know it's not something that can be applied every time     
1:24:20     
or by every model we talked about this where you know you I I don't know how     
1:24:26     
they're measuring accuracy but basically because you're measuring accuracy you     
1:24:32     
know you're including all the wrong answers with the right answers so if you're just doing a brute force search     
1:24:38     
you're going to have a lot less success than if you did tried to a focused algorithm where you could always find     
1:24:45     
success and have a high accuracy so I mean that's kind of a thinking you     
1:24:50     
know the the kind of thinking here it gets worse straight up give the coot     
1:24:55     
model the algorithm and it can't implement it so if you just give Yeah so they talked about the how if you give     
1:25:03     
the model the algorithm it can't implement it certain people will scream that they prompted it wrong worse um     
1:25:10     
maybe there is a way to prompt it right but even so it's not promising that this ability is at best so prompt dependent     
1:25:17     
um and so that's kind of so what do we what did we learn from all this i think     
1:25:23     
the paper is devastating for the notion these systems have general reasoning cap capacities in the sense of being able to     
1:25:30     
develop and deploy simple algorithms to solve combinatorally different problems     
1:25:35     
or difficult problems to phrase it a different way it is useful though not particularly surprising to known that uh     
1:25:43     
for these recursive problems it doesn't work out a general algorithm apply it i     
1:25:49     
I mean no sort sort of no it is a large language model not a magic or train Russell genie box     
1:25:57     
what we don't learn from this is whether the training sets from these systems are sufficiently rich and chain of thought     
1:26:03     
prompting sufficiently powerful to allow them to for example solve mathematical     
1:26:08     
problems of intermediate difficulty uh where by that I mean one that I could     
1:26:15     
solve as a human but would be a day's work and of course your level of expertise would have to be fairly high     
1:26:22     
to do that proving most mathematical theorems is quite different from implementing a tower of Henoi algorithm     
1:26:28     
to make without error the thousand moves you need to solve a tower with 10 discs and so you know this is again uh more     
1:26:37     
comments about it and uh going through um you know some of the details here um     
1:26:45     
what's interesting about this too is there was another paper that I didn't pull up this is uh that was another play     
1:26:52     
on words this is the illusion of the illusion of thinking and apparently there was another paper was the illusion     
1:26:58     
of human thinking which I don't know what that was about but maybe it was about like you know     
1:27:05     
kind of considering human thought as um you know like we talked about um you     
1:27:14     
know we think about humans as reasoning as as that's one of the hallmarks of being human but maybe humans aren't     
1:27:20     
necessarily great at reasoning and maybe there's a better you If if there were in evolution a better     
1:27:27     
organism that did better reasoning um you know that's humans would not be     
1:27:32     
considered the hallmark of reasoning but uh we are what we have so and large     
1:27:40     
language models are what they have for now so um yeah so I guess that's it I want to     
1:27:50     
No I think I mean that that's um that that gets at right is that you know     
1:27:56     
again it wasn't exactly machine learning     
1:28:02     
street talks point but but again you can imagine that there's a real emphasis on     
1:28:12     
getting an improvement across a set of     
1:28:19     
you know a set of benchmarks or again like some some arena benchmark     
1:28:26     
and you know f focusing on that reporting     
1:28:33     
that you know um u but still leaving the     
1:28:40     
models completely open to you know almost kind of trivial     
1:28:46     
trivial shortcomings you know and and that Um     
1:28:53     
that just completely bely the     
1:28:59     
the the the thought that the performance increase on     
1:29:05     
benchmarks is reflective of more and more thinking you know because that's     
1:29:11     
what it's called thinking you know TM right like like you know you know Um     
1:29:21     
and yeah anyway we we we still need more     
1:29:28     
you know people people calling     
1:29:34     
uh um especially when as what machine learning     
1:29:39     
street talk's talking about which is that like you know again these are trillion dollar companies that have     
1:29:47     
everything every reason to lie right every reason to game right right so this     
1:29:54     
was an interesting paper that came out this week this is actually uh uh Maxwell     
1:30:01     
Ramstead is an active inference um and Ellie Sesh has done some really     
1:30:07     
interesting work on uh the brain and on alistasis and I     
1:30:13     
don't it was involved in active inference but this has a very uh maybe     
1:30:20     
active inference type flavor it's on alignment and interpretability models     
1:30:25     
and they're talking about this effective taxis hypothesis so this is about     
1:30:31     
emotion I guess uh Ellie's work on uh alostasis is largely on you know the     
1:30:38     
effective affective nervous system and so this should be a really interesting     
1:30:43     
paper um this was on the archive published last month um     
1:30:50     
so the abstract reads AI alignment is a     
1:30:55     
field of research that aims to develop methods to ensure that agents always behave in a matter aligned with or     
1:31:03     
consistent with the goals and values of their human operators     
1:31:08     
no matter the level of capability this paper proposes that an effect     
1:31:13     
effective effectiven effectivist approach to the alignment problem reframing the concepts of goals     
1:31:21     
and values in terms of effective taxes and so taxes is like a directional     
1:31:27     
movement towards something or away from something so we have all sorts of taxis     
1:31:33     
in um behavior photoaxis chemotaxis     
1:31:38     
uh thigotaxis I mean you name the stimulus and there's     
1:31:43     
usually a taxis and the idea is that you know if you have say for example photoaxis     
1:31:50     
it's like you have an agent and it's attracted or repulsed by light it's kind of like the vehicles and some of the     
1:31:58     
simple training models that they have for for those where you provide a source     
1:32:04     
of light and then that provides this gradient through which the agent can     
1:32:10     
either move towards or repulse away from and so the idea of taxis is basically     
1:32:17     
where they move towards or away from a resource in this case the resource is a effective     
1:32:23     
so these goals and values are reframed in terms of affective taxes     
1:32:29     
uh and explaining the emergence of affective veilance by appealing to recent work in evolutionary     
1:32:35     
developmental and computational neuroscience we review the state-of-the-art and     
1:32:41     
building on this work propose a computational model affect based on taxis navigation we discuss evidence and     
1:32:49     
attractable model organism that our model reflects the aspects of biological taxis navigation we conclude with the     
1:32:56     
discussion of the role of affective taxes in AI alignment     
1:33:02     
so this talks about artificial agents and how you know we've gotten more and     
1:33:11     
more capabilities uh in them and talking about AI     
1:33:16     
alignment and how that focuses on ensuring that AI agents do behave consistently in a way     
1:33:24     
in this way even if the absence of direct human supervision is the case so     
1:33:29     
we want to have like if we're doing reasoning we want to have it aligned with human uh reasoning or human goals     
1:33:36     
in in in the sense that it's not doing nefarious things or unethical things or     
1:33:42     
whatever conventionally since state-of-the-art agents are trained using reinforcement     
1:33:48     
learning and accordingly optimize a reward utility or cost function over the state trajectories determined by their     
1:33:55     
sequential decisions ai alignment is focused largely in designing agents that share a reward or     
1:34:03     
utility or cost function with their human operators so the idea of modeling     
1:34:08     
this is that the humans and the AI would share like some sort of reward function     
1:34:14     
and this you know goes back to the reasoning models because reasoning models use a reinforcement learning uh     
1:34:21     
framework to achieve reasoning for chain of thought that involves some sort of uh     
1:34:28     
you know policy uh utility or policy role so those policies are based on sort     
1:34:36     
of the same things we find in humans and so we we you know kind of see the     
1:34:42     
results accordingly um and so I I don't have any more to say about that just     
1:34:48     
want to put that out there unfortunately however there are core obstacles that need to be overcome for     
1:34:54     
this approach to get off the ground so this is something that isn't achieved it's just kind of the way people are     
1:34:59     
thinking about this as pointed out in early work on AI alignment     
1:35:05     
and the related philosophy literature while people's actions depend on the     
1:35:11     
convolution of their values and beliefs their values themselves depend solely on     
1:35:16     
the ground truth state of affairs this introduces interpretive ambiguity     
1:35:22     
that potentially prevents explicit alignment so there's this ambiguity and this is     
1:35:28     
interpretive ambiguity that um you know results from sort of     
1:35:36     
people not always expressing their values and beliefs     
1:35:41     
uh consistently uh for example depending on our beliefs     
1:35:46     
we might experience an elevated heart rate as either romantic attraction which     
1:35:52     
is positive rewarding and valued or as an effect of physical exercise which     
1:35:58     
might be negative costly and valuous so you know it depends the sort of the     
1:36:05     
physiological response as different affective value and so you     
1:36:12     
know you think about like for example alostasis you have a state that you sort     
1:36:19     
of attain maybe elevated heart rate and why are why is your heart rate elevated well it     
1:36:26     
could be because you're in love or because you've just been out running five miles or maybe you watched a scary     
1:36:33     
movie you know and that those are all different sort of meanings attached to those or explanations     
1:36:40     
what we really value in the sense necessary for building aligned autonomous agents cannot be estimated     
1:36:47     
sole away from behavior because it depends on a combination of how behavioral outcomes impact our physical     
1:36:53     
reward systems and how those reward systems measure the cognitive cost of updating our beliefs     
1:37:01     
along the way so you know we we make these decisions     
1:37:08     
um and thinking about how you know these reward systems work and     
1:37:15     
that interacts with our beliefs mathematically it is not possible to     
1:37:20     
estimate the reward function of an agent based solely on observed behavior because behavior is the convolution of     
1:37:27     
beliefs and values so this is where we're looking at um you know how those     
1:37:34     
beliefs and values are conditional and how they can change its context without     
1:37:40     
independently knowing about a belief formation mechanism of play it is not possible to estimate the reward function     
1:37:47     
used by agent well we do not presently know what the exact belief formation mechanism that is implemented by the     
1:37:54     
human brain whatever it is however we can be almost certain it is not via the     
1:38:00     
back propagation of errors so this is where you know we have I guess an     
1:38:05     
analogy with the reasoning or the the sort of the strategic work in     
1:38:12     
that we don't even really understand how humans arrive at these things and so you     
1:38:17     
know trying to say well this is how humans do it and because we we do that     
1:38:23     
just solely by observing behavior we can't really understand how humans do things by observing behavior i mean     
1:38:30     
that's the whole premise of like physiological measurement especially like neuro imaging is that if we could     
1:38:36     
just take behavior at face value that's being generated by this box this black     
1:38:43     
box and the black box is totally interpretable which by definition it isn't but let's let's suppose it were     
1:38:51     
then you know we would have our answer but because this is you know our     
1:38:56     
behavior is highly convoluted by what's happening inside a black box you know it's hard to really kind of make that     
1:39:03     
analogy between say the behavior of an agent the behavior of a human and then     
1:39:09     
just you know peering into the black box of the agent say okay if we can just     
1:39:15     
trace out that you know chain of things going on in that black box we can     
1:39:21     
achieve humanlike um behaviors or humanlike competencies     
1:39:27     
and in other words what I'm saying is that we don't understand how it happens in humans so that kind of limits our     
1:39:33     
ability to sort of know what's happen or sort of approximate things in a model     
1:39:41     
in any case um so state-of-the-art approaches and     
1:39:47     
machine learning in some sense has ellighted the problem AI align together     
1:39:52     
so for example behavioral cloning is useful in practice because it does not require reward functions but results in     
1:39:59     
brittle AI systems that generalize poorly outside the training set similarly reinforcement learning from     
1:40:07     
human feedback or RLHF is very well in many applied settings     
1:40:13     
but outsources the evaluation of system outputs and therefore the task of evaluating whether these outputs are     
1:40:19     
aligned with human And those are outsourced to human raiders so that goes     
1:40:25     
outside of an artificial system to this highly subjective approach at rating     
1:40:32     
things ratings may be appropriate to train models that need to be deployed in specific narrowly defined use cases but     
1:40:40     
it does not get us any closer to achieving AIA neither does learning rewards from users     
1:40:47     
by directly querying them about their preferences address the AI alignment problem since we know from experimental     
1:40:54     
psychology itself report is a poor measure of actual performance     
1:41:00     
we suggest that progress can be made here by explicitly considering human evaluative systems and designing     
1:41:06     
artificial agents that conform to the same principles over the past few     
1:41:11     
decades the fields of psychology and neuroscience have fundamentally reconsidered the nature of evaluative     
1:41:17     
processes in the human brain rather than assuming that there exists a separate     
1:41:22     
rational and emotion evaluative system often assumed to correspond to model     
1:41:27     
based in model for neural processes the experimental evidence suggests that affect is the core evaluative process     
1:41:36     
ubiquitous throughout the whole brain activity that we observe in neural imaging     
1:41:47     
uh we have also learned that the sensory motor grounding for affect rests in interosception     
1:41:54     
we come to our decisions and select our actions on the basis of interosceptive beliefs accountable to visensory signals     
1:42:03     
so what they're getting at here is that you know there's this sort of ancient     
1:42:08     
assumption that emotion and cognition separated out     
1:42:14     
so like you know that there's this rational brain and there's this emotional brain and that there's no interaction between and that's kind of     
1:42:21     
fallen by the wayside as we know that like they're interacting systems so a     
1:42:27     
lot of decision making for example is influenced by emotion so if you're in a     
1:42:32     
certain emotional state your decision- making is impacted if you're under stress it's harder to come up with a     
1:42:39     
good solution to a problem if you're um you know blinded by positive or negative     
1:42:46     
emotions it's harder to come up with the best answer to a problem so they're     
1:42:52     
that's what they're getting at with that and you know this is something of course we don't really take into account with     
1:42:59     
machine models machine models don't have that um emotive or a effective component     
1:43:06     
which is maybe interesting enough if you're comparing humans and machines but     
1:43:11     
you also have this aspect of uh kind of thinking about this regulatory system that is involved in a     
1:43:18     
effect so you know with Ellie Sesha's work he's interested in alistasis     
1:43:25     
and uh emotions or a effect and how those states you know complex     
1:43:31     
physiological states are regulated by aphact and so again this is where you     
1:43:37     
have this interaction between the processes that you don't see in machine intelligence and machine decision     
1:43:46     
um okay so let's see     
1:43:53     
here we propose that if we want AI agents to align with us then it ought to follow that AI agents must model both     
1:44:00     
the formation of affective states in humans and the interosceptive facts that     
1:44:05     
ground the states this proposed grounding may provide an inductive bias to overcome then negative     
1:44:11     
identifiability results in alignment approaches such as cooperative infor     
1:44:19     
accordingly this paper proposes an affectivist approach to AI alignment and     
1:44:24     
then they kind of talk about some of these things throughout the paper     
1:44:32     
so they kind of talk about the affective landscape within the affective sciences     
1:44:37     
the affect gradient hypothesis suggests that gradients over a landscape     
1:44:43     
of affective hills and valleys can point the way for all motivated behavior so     
1:44:48     
they use this sort of gradient descent like process or this this sort of     
1:44:55     
landscape model for looking at how um you know how motivated behavior     
1:45:01     
should unfold so the hills and valleys are sort of these a effects of a effect     
1:45:07     
and how they make motivated behavior harder or easier to achieve     
1:45:13     
and so this is a formalization of folk psychology or folk psychological intuition     
1:45:19     
as a brain basis for this hypothesis the dopamineergic midbrain invertebrates has     
1:45:25     
long been studied as a brain basis for reinforcement learning but such reinforcement learning studies tend to     
1:45:31     
assume that reward which is the psychological mathematical construct in reinforcement learning     
1:45:38     
corresponds linearly to reward that we see in in neurobiology so if we're     
1:45:44     
talking about dopamine that there's a sort of one to one correspondence between dopamineergic signaling and this     
1:45:53     
reward be you know uh rewarding behavior and then having it be the psychological     
1:46:00     
mathematical construct so like you know I guess what they're getting at is that     
1:46:05     
you can increase or decrease the reward and it will have an effect on behavior     
1:46:12     
in the same way that at least as it's thought of here that you can increase or     
1:46:18     
decrease dopamineergic signaling to get a certain reward behavior now there are     
1:46:24     
a number of problems with that for one thing we found that dopamineergic signaling is much more complex than like     
1:46:30     
more or less resulting in a certain behavior there are a lot of interactions and quite frankly we don't fully     
1:46:37     
understand the effects of dop do dopamine signaling but secondly that it     
1:46:42     
maps neatly to the construct that you're making of reward so if you have a reinforcement learning model and you     
1:46:49     
have reward for some um output of a large language model and you use that construct and you say you just increase     
1:46:56     
the reward what does that look like in the biological context and how do you align that with human uh re the human     
1:47:05     
response to rewards sometimes it's not obvious what the response for a reward     
1:47:11     
is if it's a weak if it's a weak reward does it have you know a good response     
1:47:19     
curve and things like that while alternative models of     
1:47:24     
dopamineergic midbrain have appeared in the literature reinforcement learning formalizes the expected utility metaphor     
1:47:31     
which lacks interpability because it systematically identifies mathematical functions of distal or sensory states of     
1:47:39     
physical substances so this is kind of an interesting aside but like in the history of behaviorism     
1:47:47     
which is where reinforcement learning originally came from you know they would do a lot of     
1:47:54     
different types of experiments where you would maybe give a monkey or a rat you     
1:48:01     
know some sort of reward like fruit juice and you'd have this training uh     
1:48:08     
typically the sort of training regimen where you know they'd either get the fruit juice reward or not and then that     
1:48:16     
corresponds to this reward that we can quantify and then this all kind of relates to dopamineergic midbrain     
1:48:23     
signaling so the midbrain of course not being the sort of seat of cognition as     
1:48:28     
it were but rather a place where get this clear response you know it's kind     
1:48:35     
of like this is what's happening in the domeic midbrain this is the sort of     
1:48:40     
behavioral paradigm and it's corresponding with some sort of improvement in behavior so I'm awarding     
1:48:48     
it with a treat the organism is responding And we know     
1:48:54     
this sort of uh idealized model system and so this is     
1:49:01     
how this should work and then we take that as inspiration for our artificial     
1:49:07     
model which has all the properties of that kind of reward loop but none of     
1:49:13     
sort of the bi doesn't take any of the biological responsibility which means we don't understand the variation in it we     
1:49:19     
don't really understand where we can fail or we don't really understand the sort of strength of the rules so it's     
1:49:27     
it's kind of an interesting aside um they say here the problem here is not     
1:49:34     
mathematical models of the mind but rather their application of the study of motivated or goal- directed behavior     
1:49:41     
without well- definfined limits so again this is like you know we kind of take     
1:49:48     
reinforcement learning as a artificial intelligence paradigm takes inspiration     
1:49:53     
from these kind of reinforcement learning experiments from behaviorism but they don't really have uh they don't     
1:50:02     
translate the same units they don't translate the same sort of mechanisms     
1:50:08     
any interpretable model of biological systems behavior features well- definfined units     
1:50:13     
or any interpretable model of biological systems behavior that features well- definfined units must account for     
1:50:20     
evolutionary history and natural selection so in neuroscience and the cognitive     
1:50:26     
sciences this project takes the form of phoggenetic refinement and this is uh     
1:50:31     
Paul Cisac's idea of phoggenetic refinement so this is the phoggenetic view of cognition where things are sort     
1:50:39     
of improved or optimized over evolution so if you have like a uh lineage where     
1:50:45     
you have some trait or some state that exists it's refined throughout philogyny     
1:50:53     
it's refined throughout evolution that's refined throughout um     
1:50:59     
you know the evolutionary history of that which was conserved through evolution by political selection     
1:51:06     
pressures preventing deviation will tend to generalize across species providing     
1:51:11     
the historical inductive bias to understand that species specific features emerge by elaboration and     
1:51:19     
acceptation of what came before so this leads us up to thinking about     
1:51:25     
affect and the evolutionary function of veilance and uh the sort of the advantage of     
1:51:34     
veilance evolutionarily is to link an organism's internal physiology with the movement of its body     
1:51:42     
through space via taxis navigation now we're getting into the taxis and how that relates to alignment because we go     
1:51:50     
from like this model very simple model of reinforcement learning which is an experimental model in     
1:51:57     
biology so you know it's it's something that we can elicit a response from that's why we     
1:52:03     
design experiments so it may not relate directly to reward in sort of a naturalistic context     
1:52:12     
but the then the point is that that biological idealized biological model is     
1:52:18     
then used it it's sort of artificialized into this reinforcement learning that we     
1:52:23     
use today for reasoning and we don't really have the same units of measurement we don't we're just kind of     
1:52:29     
using a metaphor and attaching numbers to it but then we have to think more     
1:52:34     
deeply about sort of why something gets rewarded or why something is motivated     
1:52:41     
to an organism and that's where we get into these taxes and these kinds of concepts like veance and things like     
1:52:48     
that and so now we're talking about evolution we're talking about why it's there     
1:52:54     
and what it does and so this is where we'll get into this     
1:52:59     
whole discussion on these sort of um you know     
1:53:06     
things that are well beyond computational reinforcement     
1:53:12     
and so of course it relates to the movement of the body so it's related to um embodiment and other things like that     
1:53:22     
so they point out that while elementary taxis navigation emerged quite early in single cell organisms and was later     
1:53:29     
replicated in multisellular animals the earliest brains to feature taxi navigation or taxis navigation likely     
1:53:36     
evolved in early violarian so this goes pretty deep into fogyny well before we     
1:53:43     
had a midbrain um and so this is where we get this sort of um this behavior     
1:53:51     
that maybe we see in single cell organisms and then we you start to see in organisms with brains and then     
1:53:57     
complex brains and so this is something that is maybe an organizing principle of     
1:54:03     
goal directed behavior is taxis so you get taxes for you know you're moving     
1:54:09     
towards a sort resource or stimulus and it's not dependent on any one neural     
1:54:17     
architecture it's certainly not dependent on dopamine signaling it's dependent on     
1:54:23     
some sort of movement towards a goal and that can be     
1:54:28     
implemented in a number of different ways phoggenetically we propose that once taxis navigation     
1:54:35     
evolved to navigate a biotarian's physical environment the folding of the neural plate into a tube inside the     
1:54:41     
organism reoriented the combined apical and blastoporal nervous systems towards     
1:54:47     
navigating an internal tax landscape this is all described by Paul Seizic in     
1:54:53     
his phoggenetic refinement paper so this is where you have this transformation of     
1:55:01     
single cells and the behavior of those single cells i     
1:55:07     
guess when they're connected it reorients his nervous system and you     
1:55:14     
have what used to be external taxis in single cell organisms now the sort of     
1:55:20     
internal taxis in in complex organisms with a nervous system with specifically     
1:55:27     
a neural tube which would then later become uh a nervous system     
1:55:32     
so it's an interesting concept for these sort of internal taxes or aphact is that     
1:55:38     
it started with like single cell taxes in the environment where you have single     
1:55:43     
cells that are moving towards food sources chemical sources light sources     
1:55:49     
or away from them and then those things get repurposed by this sort of uh     
1:55:55     
multisellularity and then organization into a tissue and organization into a network and then this sort sort of     
1:56:01     
folding and reshaping in development     
1:56:07     
um and so this is this internal taxus     
1:56:13     
landscape prescribed movement through a vector space and viscerosensory physiological indicators     
1:56:20     
through interosceptive space and so this is the heart of the affect     
1:56:25     
taxis hypothesis we further suggest that the associative learning systems we typically consider     
1:56:32     
the brain's reinforcement learning systems evolve later to invigorate or slow down taxis movement by estimating     
1:56:39     
the long run rate this hypothesis could be check neuroanatomically     
1:56:44     
and mammals reward taxis models explain aspects of reward seeking in mice so     
1:56:51     
what he's saying is that you know we have this sort of these internal taxes     
1:56:57     
which are these responses that are not well controlled and then what he's     
1:57:02     
saying is that any sort of reinforcement learning system in the brain really     
1:57:07     
evolve to sort of regulate these toxic movements um and estimate sort of a longer     
1:57:15     
movement rate so instead of like having these internal taxes that are just kind of responsive to immediate stimuli or     
1:57:22     
immediate internal state you need to have a system that can like modulate that but also estimate long longer term     
1:57:29     
networks so if you have um you know a subject and you give it a juice box     
1:57:35     
every time it does something interesting or good then there's a sort of uh     
1:57:41     
immediate sort of maximization of the award and so the reward you know     
1:57:48     
that's not necessarily a good thing you need to have the sort of maybe longer you know rewards for longer term goals     
1:57:54     
or the ability to sort of seek out longer term goals or uh maybe a delayed     
1:58:00     
reward so you know you you have this distinction between always getting an     
1:58:06     
immediate reward and always kind of having the system optimized or poised at that immediate reward versus seeking out     
1:58:13     
longer term rewards and longer term uh equilibrium     
1:58:20     
so um so unfortunately in vertebrates and such as mice and humans associative     
1:58:27     
reinforcement learning also ensures that behavior at any one moment does not reflect the immediate taxis landscape at     
1:58:34     
same moment instead it reflects the predicted long run taxis landscape given     
1:58:41     
present sensory cues so this is uh very much in the spirit of uh predictive     
1:58:46     
processing and so this is where you have this sort of prediction from present     
1:58:52     
sensory cues to this what this long run landscape will look like um and so     
1:59:00     
again I don't know whe that's unfortunately I guess you know we can't what they're saying is we can't make     
1:59:06     
this direct um you know a direct connection between     
1:59:11     
artificial systems and biological systems like humans for in terms of how     
1:59:17     
the board structure works or is structured     
1:59:23     
um to study Texas navigation as such rather and associative learning     
1:59:29     
experimenters would either have to find a way to deactivate unlearned associations while inhibiting their     
1:59:36     
further learning or study a model organism that simply lacks temporal reinforcement learning while nonetheless     
1:59:42     
performing Texas navigation and sharing a common ancestor of vertebrates so     
1:59:47     
they're actually thinking more about the sort of internal taxis and how those     
1:59:53     
things work but I think it has some relevance to the alignment problem too     
2:00:00     
okay so um they kind of work through the math here um     
2:00:07     
and so they define partially observed markoff precision processes which are     
2:00:13     
these environment models that they use so at the level of RL simulation environments frameworks such as the     
2:00:20     
Farama gymnasium could include taxis navigation or optimal foraging problems     
2:00:25     
including potentially by connecting with biohysical models and model organisms     
2:00:31     
forage world which is another package provides an example of such an environment as do deep minds rodent and     
2:00:37     
swimmer environments and these are these model gems that we've talked about many times such an environment model would     
2:00:44     
consist of a partially observable numerical decision process or POM DP as     
2:00:50     
a standard reinforcement okay so um then they kind of work     
2:00:56     
through the POM DP example and then they actually use C elegance as a model     
2:01:02     
organisms affective landscape um and so computational study of a factor     
2:01:10     
remains in its infancy with most studies focusing either on applying theories of emotion theory of mind tasks or on the     
2:01:17     
representation of emotion and AI models rather than on formally modeling theories of how emotional and effective     
2:01:24     
content arises in real brains so we propose a computational model of a     
2:01:30     
simple model organism engaging in whole body behavior to regulate its internal     
2:01:36     
physiology and tie the biologically plausible components of that model to affect     
2:01:42     
so now we have a biotitarian model which is C elegance and uh     
2:01:49     
so taxis behavior in C elegance is driven by a present stimulus not a prediction or belief about possible     
2:01:56     
future stimuli bypassing the need to infer such beliefs or behavior     
2:02:02     
this section will describe what's already known about taxis and sea elegance so it's true that C elegance     
2:02:09     
uses sort of an associative learning paradigm so while C elegance     
2:02:14     
can learn to associate rewarding or punishing cues across sensoring modalities it does not associate them     
2:02:21     
over time so it doesn't have a good long-term memory of uh punishing and rewarding cues at least according to the     
2:02:29     
literature that they're citing um and then     
2:02:34     
so consider building the palm dp model proposed in section three for sea elegance so we take the palm dp model     
2:02:41     
and we apply it to se elegance observations correspond to the signals transuced by taxis related sensory and     
2:02:49     
interosceptive neurons so we have the sensory and interosceptive neurons we     
2:02:55     
have their circuits and we can uh or sort of use that as a model of taxes     
2:03:01     
it's interesting that uh in the Nether meeting this week I talked about a paper where they had explored this concept of     
2:03:10     
sort of supporting circuits in the connetoone that is we know that they're basic circuits for movement that it     
2:03:17     
consists of about six or seven neurons and that you can map these you can     
2:03:22     
simulate these circuits and map them to forward and backward movements and     
2:03:27     
they're very stereotype movements and it's very precise however there is a lot of tuning in those movements a lot of     
2:03:34     
tuning of like you know the speed of the worm and things like that and those come from other neurons in the connectto and     
2:03:41     
other parts of the conneto that feed into that circuit so that circuit is basically operative at the level of     
2:03:47     
giving basic commands but there also these supporting neurons that feed into     
2:03:52     
the circuit that modulate so it's an interesting aside because I think they may be kind of hoping for a     
2:04:00     
really simple model and they may not have as simple of a model as they would like in any case it's far simpler than     
2:04:07     
the dopamineergic midbrain so um     
2:04:13     
there we go um the ladder has been understood and by latter they mean interosceptive neurons in this Texas     
2:04:19     
related aspect uh as reading off the internal state of the organism to     
2:04:25     
provide salience means for different rewards and costs outside the body     
2:04:31     
so we have these uh so actually we have this two-tiered system of we have taxis     
2:04:38     
in the external environment and those are sensed by sensory neurons     
2:04:46     
and then we have interosceptive neurons which sense taxis in the interior     
2:04:52     
and then we can combine those into this sort of model of uh salience weights     
2:05:00     
that characterize different rewards and costs um and and so that's they've worked     
2:05:08     
through their mathematical model here there's a spatial gradient that provides a reference signal for taxis navigation     
2:05:17     
and um kind of going through this whole thing um     
2:05:24     
and so and then they kind of get at like     
2:05:29     
dopamine and serotonin and how those can play a role in these     
2:05:35     
kind of reward reward signals and and things like that     
2:05:43     
okay um reinforcement learning theories of the human brain tend to associate dopamine with prediction error the     
2:05:51     
invigoration of movement and subjective arousal active inference models of     
2:05:56     
vertebrate behavior cast dopamine as a precision parameter measuring confidence     
2:06:01     
and sensory cues about action so this leads to this sort of application of active influence based on what we know     
2:06:08     
about uh dopamine being this reward prediction and mechanism and having this     
2:06:15     
error that needs to be minimized um and then this is sort of the basis for the active influence model which     
2:06:22     
models this u minimizing this prediction     
2:06:27     
this is all based on the human brain or in malian sea elegance activating dopam     
2:06:35     
dopamineergic neurons makes worms slow down into a crawling gate and behave as     
2:06:40     
if exploiting a patch of resources well dopam dopamine also serves as an     
2:06:46     
essential role for controlling the speed or vigor of movement as invertebrates     
2:06:52     
we suggest here that from an evolutionary perspective dopamine controls the gain of perceptive feedback     
2:06:58     
from motor movements to enable an organism to exploit opportunities in its nearby environment so they made this     
2:07:05     
connection between sea elegance and mamalian dopamine uh signaling and it's     
2:07:13     
behavior and unlike some of the other cases in a defect you have this very clear signal     
2:07:21     
from the signal and it's you know phoggenetically conserved I guess is the way to put it     
2:07:28     
um less is known about as a whole about the neural role of serotonin so they have     
2:07:36     
dopamine and then serotonin they're looking at serotonergic activation and c elegance     
2:07:42     
uh serotonin neuronic activation makes ones change their locomatory gate as if leaving patches of resources the sensory     
2:07:50     
endings of these neuroscratory motor neurons located in the ferings release serotonin when it sense food leading to     
2:07:57     
locomotive slowing or angial pumping and eventually eggling behaviors     
2:08:02     
you suggest here that serotonin signals a shift from using the body to exploit environmental rewards spending energy on     
2:08:09     
the internal physiological processes requiring these rewards tempering the     
2:08:14     
Texas landscape to inhibit locomotion so this is all about modeling arousal     
2:08:20     
and then the behavioral output so then they finally get into this discussion of AI alignment     
2:08:27     
discussing these affected taxes and and these other things and kind of linking that to     
2:08:33     
reinforcement learning which would be the link between the two     
2:08:40     
um yeah so I think that's it uh building on recent work in affective science and     
2:08:45     
computational modeling this paper proposes an affective Texas hypothesis     
2:08:51     
of motivated behavior and ties it to interpability and alignment of AI systems     
2:08:59     
so some really interesting references in here um we don't have time to go through them all but um a lot of references with     
2:09:07     
respect to C elegance and dopamineergic signaling     
2:09:13     
and some other things about gradients and yeah I mean just a lot of good stuff     
2:09:20     
ryan Morgan looks like you want to say some things but I mean you know     
2:09:27     
it's a lot of um what you Yeah it's just like hey we've     
2:09:33     
been using a mathematical abstraction of Yeah of what is what is refor you know     
2:09:40     
like again like I always joke um people like uh so are you like a machine     
2:09:47     
learning person or something like that i said "Well I was certainly doing reinforcement learning back in 90s     
2:09:58     
but I but I was doing it with animals." Yeah     
2:10:04     
so um Yes     
2:10:09     
um yeah so I mean I I like it you know i I     
2:10:16     
thought it was interesting sorry my um     
2:10:22     
image is getting cut off there but um um     
2:10:28     
the uh what's it called citation no     
2:10:35     
connected papers so So you go to the archive do connected papers okay and um     
2:10:41     
and you get three distinct clusters you know which I think is is and you     
2:10:50     
look at it and it's a it's a pretty good characterization of of what that you     
2:10:56     
know it's got a it's got a you know it's talking about it's kind of like     
2:11:03     
effective uh uh issues around you know um     
2:11:13     
effective uh taxis um     
2:11:20     
you know another kind of like computational basian modeling and then     
2:11:25     
like C elegance and     
2:11:30     
um anyway it's     
2:11:36     
it's good um you know I think it should coupled with     
2:11:42     
uh this uh this Carne Melon professor who     
2:11:50     
um was the I think the last second last speak like a recent speaker     
2:11:56     
in the the neuro group at foresight     
2:12:03     
talking about how much information     
2:12:11     
anyway that that was kind of like a theoretical paper i mean in terms of like a computer science limits of of how     
2:12:19     
much information needs to be exchanged for for alignment between agents right     
2:12:27     
um this this Yeah I mean interesting bringing trying to bring more     
2:12:36     
biology And biology can only be understood in     
2:12:41     
the the light of evolution right     
2:12:47     
like um and     
2:12:53     
yeah good good stuff um     
2:13:00     
certainly and Ramstead's name comes up a bunch right um I I was you know I know     
2:13:06     
we gotta go but uh I meant to post this but like there's an RX infer let me just     
2:13:13     
see if I can find it right before the before we go um     
2:13:22     
let me see     
2:13:30     
maybe it was from Lazy Dynamics yeah yeah okay um     
2:13:44     
Oh well this is an old paper sorry anyway     
2:13:49     
this is um trying to to computationally link     
2:13:56     
um active inference to um a tenon bomb a 2023 tenon bomb paper     
2:14:05     
about from from words to world models or from word models to world models i don't     
2:14:11     
know if my pronunciation is getting that across okay w to w     
2:14:21     
uh u and not not that this is the same thing but     
2:14:27     
just more more realism i I it's so also interesting like the the the benchmark     
2:14:35     
suite or not the benchmark suite but the the environments that you're using right     
2:14:41     
and and um sorry I didn't get to talk about uh the neuroch summit that was     
2:14:50     
this week okay um uh the the very short uh update on this was there was no     
2:14:57     
neuroch what it it was it was a     
2:15:04     
three four it was a 4hour pitch session oh     
2:15:10     
to protocol labs neuro okay um which was super interesting in that     
2:15:19     
uh there was a series of senior what I     
2:15:24     
would call senior brain initiative researchers pitching     
2:15:31     
um and as as I joked um to someone it was     
2:15:37     
just like like everybody in that room was was already on my Google Scholar     
2:15:43     
alert lists     
2:15:48     
and uh so that was kind of cool yeah um it was     
2:15:54     
just sad that they were all looking for alternative funding because     
2:15:59     
brain initiative in their minds is has been     
2:16:05     
you know is effectively closed uh     
2:16:11     
and but Why I bring it up is that there was a     
2:16:18     
a consistent like like Shaun Escola and and Patrick     
2:16:23     
Minnow were the two judges if you will or Yeah yeah they     
2:16:31     
they they were who you were pitching to and um the uh     
2:16:39     
their consistent kind of followup question across these     
2:16:47     
um these researchers pitches was about the environmental     
2:16:54     
complexity that you could achieve you know so this is like like how how are     
2:17:02     
you making the environment more naturalistic     
2:17:09     
right right i mean it like like I so many neuropixels     
2:17:15     
you know like like neuropixels were present you know like in probably 50% of     
2:17:21     
the if they if the pitch wasn't about     
2:17:27     
starting to use them then the pitch was like because because we've been looking at     
2:17:34     
pieces right like like either doing something new past it or or like some     
2:17:40     
new application of it um but but a real like a pretty common followup was just     
2:17:49     
about how well you um how naturalistic     
2:17:54     
Yeah just that you could make make things and which which against I mean     
2:18:01     
played a bit into this this kind of active inference way of thinking of     
2:18:07     
things where you know that that loop about from the the animal to the world     
2:18:14     
and and you know is is is much richer and and yeah and not necessarily more     
2:18:23     
complex but um     
2:18:28     
needs to be treated with a bit more fidelity right     
2:18:35     
and and you know and which is sort of similar to the you know pe     
2:18:42     
mice don't just maximize pellets or you know     
2:18:47     
like it's not you know you know you you can't just have a a     
2:18:53     
light go on and and a pellet response and feel like you've you've really     
2:19:00     
captured what's going on and     
2:19:05     
I'll I'll follow up or you know like it would be good to cover some more of     
2:19:12     
those those examples of because it really was an interesting like you get     
2:19:18     
to be in the room when a bunch of senior people are kind of pitching for     
2:19:26     
like like it was kind of good that they weren't RO1's yeah you know like like     
2:19:33     
they were small but they weren't trivial kind of cared about open science     
2:19:41     
and kind of cared about     
2:19:49     
what open science open source and and and a little bit like     
2:19:56     
like will will this help other people's research not you know like like can you     
2:20:02     
do something that then like a bunch of people can build on yeah yeah yeah i'm     
2:20:07     
not sure that's exactly open science but like Yeah     
2:20:14     
i'll stop all right all right well yeah thanks for attending and hopefully this     
2:20:22     
meeting was useful i guess it was oh yeah yeah yeah for sure anyway we got we gota gotta start helping with the     
2:20:28     
hackathon here all right so by a punk hackathon all right good luck take care     
2:20:34     
take care bye bye
