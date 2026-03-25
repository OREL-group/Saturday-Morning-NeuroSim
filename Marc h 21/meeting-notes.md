## Meeting Recording

[YouTube link](https://youtu.be/AaNdIgQ-50g)

## Mastodon thread

[link](https://neuromatch.social/@OREL/116279917169078327)

## Feature Videos

[Kavya Zala on "Conversations Spaces"](https://youtu.be/_GLTJQY9YMU)

[Vidhi Rohira on Improving SARSA](https://youtu.be/f2SRrtMP0Gc)

[Akshat Choudhury on Motivation in Open-source Communities](https://youtu.be/iX4RM37zoeo)

[Discussing Models of Scientific Dysfunction in the Tenderloin](https://youtu.be/_gRyCVURU1c)

## NOTES
Gastown simulation — similar to SustainHub.

formulate coders, designers, roles, and activities.

what if tokens (and compute) were free?


Ising, Spin Glass model.


Karpathy —> iterate on benchmarks if you have good metrics.

diffusion (microstructural) benchmarks.

ALF (evolution of embodiment) —> Bongard, iterated embodiment.


Vidhi — SustainHub. Maintainers, Contributors, Innovators, Knowledge Curators.

multi-armed bandit, SARSA.

Thompson Sampling is a means to make multi-armed bandit more contextual.

new metrics in the project: harmony, resilience, and reassignment.

2025 vs. 2026 —> updates to repo. Towards intelligent adaptive system.

contextual text allocation (bandits) —> Thompson Sampling.


State-aware rather than history-only.

* SARSA (lambda), Q(s,a) —> eligibility trace, sustained action pair (long-term effects).
 
evaluate burnout, convergence (edge cases — agents remain unclassified), efficiency.

centralized systems —> in terms of agent metrics. 


Sarrah — collaboration, size of tasks, # of agents. 

Riya — World grounding event (ingest, ground, chunk), sourcing, agentic RAG (currently have parametric knowledge only).

* PyQT5 — Slack, Github, conversations are separate.

ChromaDB —> Ollama. Modular, multi-agent RAG.


Need collective discussion information and historical knowledge.

Gao, 2003; Ehtesham, 2025. Issue-level shared retrieval. Contributor personalization, maintainer selection. 

Authoritarian vs. decentralized. Planner, retrieval, filter, synthesis (four configurable models).

Modular RAG — each agent’s context, shaped by prior agents.

what constitutes a RAG database?

Issues —> 5-10 comments vs. threads.


PRs are part of discussion, but not the whole thing.

issues vs. style of discussions.

Chroma db will be local, other dbs such as pinecone work well with Ollama.

Add conversation space to system —> motivation system. Calculator issue motivation is primarily predictive.

intrinsic, extrinsic (enjoyment, ownership, learning).

agent actions —> more than reviewing code, submit PRs. 

reviewing code, open Github issue, mentioning another contributor.

Cheng and Guo, 2019, “Activity-Based Analysis of Open Source Software Contributors: Roles and Dynamics”. Supporting vs. active participants.

allrounders, coordinators, core devs, intense code contributors (Activity Space).

Active Classrooms: expands into an open system. 

roles are not acribed, form from interactions.

What is the initial state?

flat Github discussions structure. 

no role-based simulation of actions.

Turn Order: Softmax (additive model with burstiness) —> P(i,t)

motivation, action, network. Motivation/Discussion using RAGs.

profile scraper and personality configuration.

inactive people —> lose expertise. Nonnecke and Preeco, 2000. 90-9-1 rule (lurkers, control, super users).

RAG — gives model a memory, previous action.

data disentanglement (convo_ids).

DISCO —> intertopic distance map. 

personal enrichment. Park et.al (2023). Use Sims to model conversations.

Sim is already computationally expensive.

Frequency, breadth. Types of agent and stratification.

cross-coupling —> interaction are not background noise.

memory vs. RAG (not sufficient) —> LyfeAgents, CogSci.

Stanford GenAgent paper.

emergent vs. replay RAG —> only retrieve conversation information.

focused Ultrasound @ the Tower. Temporal windows, symptom modulation.

diffusion in Python —> DiPy —> development release. Coverage of AI in medical imaging.

Geoff Hinton (radiologists are all still there). Can you design a sequence that runs faster? AI-assisted coding (Morgan’s project, refactor with Jax).

## TRANSCRIPT
0:00   
Hello guys.   
0:06   
Hello. How are you? Good.   
0:12   
So, looks like Ashot is here and Vit's here and Morgan's here. Welcome.   
0:18   
So, this week we had a DVORM meeting. Um, and we talked about a lot of G-S   
0:23   
things. Remember that the G-SK deadline is uh coming up on the 31st. So the 31st   
0:31   
is I believe next week. And so we're going to be pushing that deadline this   
0:38   
week. So if everyone is uh working on their proposals, please make sure to   
0:45   
send those into the GOC portal. make sure that you have, you know, everything   
0:51   
ready to go and then, you know, we'll make our selections and I think they'll   
0:57   
be announced sometime uh before the beginning of May. I'm not really sure what the timeline is this   
1:02   
year for them. So, our D.VARM meeting this week, um we had a lot of it was a   
1:08   
hour and 40 minutes, so we had a lot of people presenting for GOC. Um, so we had Susan and Shreas and   
1:16   
Morgan to begin the meeting and uh it looks like we talked about   
1:22   
this figure here. This was from a talk that Susan gave um you know she does a   
1:28   
lot of things on tensgrity structures and other things and she's interested in   
1:33   
tissue modeling specifically different types of computational methods you would use for tissue modeling and for building   
1:41   
uh simulations of biological cells and populations of biological cells. So you   
1:48   
know there are these different types of discrete models, there are continuous models, there are mixes of discrete and   
1:55   
continuous models, there are heristic models, physical models and then design aids which include finite element   
2:02   
analysis and evolutionary algorithms. So that was just something I wanted to   
2:08   
talk about and then uh Susan had some things to say about that and then Shreas   
2:14   
gave his presentation on the uh his work that he's proposing um in terms of   
2:20   
interpolating the conneto. So he's thinking about the sea elegance conto   
2:26   
which is a fairly small conneto and it has is well characterized and he has   
2:31   
that data set and he's interested in integrating the lineage. So he's looking at these uh uh uh graph neural networks   
2:40   
that are time dependent. Um and and so you know he's looking at that and one of   
2:46   
the ways he wants to do that is to look at how the conneto is shaped in development looking at the different   
2:52   
time points and then using methods to both project that into a higher uh   
2:58   
dimensional space and to uh well to plot the the network over time and then to   
3:06   
also look at the dynamical systems type of behavior that you see in this uh   
3:13   
conneto. So a lot of interesting um stuff here. He's he's talking about uh   
3:19   
talks about why lineage matters for matters for neural developmental modeling. And so what he's doing is he's   
3:26   
taking the data he's projecting it into this um hyperbolic space which is a   
3:32   
special kind of mathematical space that's different from uklidian space. It allows for curvatures to be represented.   
3:39   
and then using the lineage tree um information to build these uh time   
3:45   
dependent structures. So he goes through his math and and his   
3:51   
uh so he's uh using hyperraphs to encode these things. Uh he's technically   
3:57   
collective motion. So he actually developed this method that's very similar to um a lrangeian coherent   
4:03   
structure and that you have these uh these you know the cells are represented on this uh hyperbolic space and it kind   
4:11   
of looks like um particles floating in a pool of water or something or on a on   
4:18   
the surface of a sphere. So it's kind of interesting. We talked I kind of drew that out on my board and then we talked   
4:25   
about it. Um and then he has some graphs here. So he's reporting some data for   
4:30   
developmental stage talking about lineage direction as a collective force.   
4:35   
So this is where he gets into his ordinary differential equations that he's using on a hyperraph   
4:41   
and then you know talking about a little bit about synaptogenesis   
4:46   
in the uh conneto in the developmental conneto. So this is uh   
4:53   
all that there and then so that was Shreas's presentation. Uh we had some discussion after that and   
5:00   
then I wanted to I ended up talking about Morgan's work. So Morgan last week   
5:06   
in this meeting presented on his work um uh for you know doing neuro simulation   
5:12   
and he built a stack in claude to do that and one of the things one of the repos that he has is this organoid   
5:20   
benchmark of course so natural this is something we talked about in divorm this is the organoid benchmark we just went   
5:27   
through what's here and sort of the pipeline and talking about that a little bit and he's adding things in from the   
5:34   
for meetings. So people who are applying to G-SK, he's kind of taking that and putting it into the model. It's really   
5:40   
interesting work and he's got some nice data sets um to mine for this this   
5:47   
activity. So that was uh Morgan and then uh then   
5:53   
Susan presented her work on actually I did talk about someone else's repo here   
5:59   
um Hardik Singh who did neurokconne growth simulation. So we talked a little bit about that. Uh and then Susan gave   
6:07   
her talk on modeling simple epithelium tissue using tensegrity structure. So she's interested in this these super   
6:14   
stable structures called tensegrity structures and applying it to biolog groups of biological cells that form   
6:21   
tissues or form other types of structures. And so this is kind of going through   
6:27   
some of the work that she's doing. A lot of uh mechanical engineering, a lot of physics. This is the stress strain   
6:34   
curve. So you have this response curve of the tissue. So when the tissue is under stress and strain or it's under   
6:41   
sort sort of um perturbation, you have this relationship between stress and   
6:46   
strain that has this sort of nonlinear curve. And so you know we that's kind of   
6:52   
what we're interested in. And with uh with respect to tensities, the stress   
6:58   
strain curve is more robust than it otherwise would be. uh we have these trijunctions which are important how the   
7:05   
cells are are organized um in terms of you know how they meet together. So   
7:12   
cells don't exist kind of in a vacuum or they don't exist sort of independently.   
7:17   
They're in this matrix uh in contact with other cells and then anchor to a   
7:22   
substrate. And so this is kind of describing those anchor points um and and how they kind of form this meta   
7:29   
geometry for the tissue. and the tensities we think would be in those   
7:34   
structures. So she's going through some of the computational modeling. She's modeling   
7:40   
this what they call a T3 tense segrity um and and just kind of the simulations   
7:45   
there, the boundary conditions, some sample graphs and tension and   
7:51   
compression. So some displacement versus force graphs and then you know some validation on   
7:58   
long tissue data and uh this hexagon   
8:03   
three cell model which is where three cells come together and just you know different types of toy models like that.   
8:11   
Then we had our G-S students or GOC aspirants um give talks. So we had this talk by   
8:19   
Udkar Hiyagi he was doing some threedimensional modeling and building a biohysical model really interesting   
8:26   
stuff uh that he was presenting uh we so he had a bunch of things   
8:32   
related to biopysics that he was modeling here um and he was using this   
8:39   
package Cindy as well as GNN's to do some of this then we also had I think   
8:46   
Baron yes Baron or Ashu who actually um who did this   
8:52   
uh work on looking at temporal developmental graphs, building a   
8:58   
simulation engine for embryoenesis, uh building it into a developmental graph neural network, looking at the   
9:05   
emerging conneto and then hyperraph neural networks. Um and and so this is kind of going   
9:12   
through this building this in network X and PyTorch Geometric and those sorts of things. And then this   
9:20   
is some of her visualizations which are interesting. This is the conneto uh   
9:25   
graph here. This is a temporal graph of the conneto and you know this is plotting it out in three dimensions. So   
9:31   
you can explore it and look at the structure and then we of course have statistics that we use to summarize   
9:38   
these networks as well. And so this is u she brought up this uh   
9:45   
C302 paper that that openworm published uh several years ago. And here you know   
9:52   
this is the C302 platform which is well established in openworm. And it   
9:57   
basically is this uh relationship between uh um like a conneto that you   
10:04   
might get. you have um uh neuroinformatic data that where the cells are labeled and then you plug it   
10:11   
into the simulation platform. Um you use neuron and you use other Python scripts   
10:17   
to analyze it. So fitting that into C302 might be really interesting as well.   
10:24   
Okay, so that's all we have on the um on the D.VAR meeting and so yeah, that's   
10:29   
good. And uh we've been working on G-Soft applications. Now, when we get to about the 1st of May, we're going to   
10:35   
start up our open-source meetings for the year. So, our open source meetings are usually an hour long, maybe an hour   
10:43   
and 10 minutes long. And it is um yeah, and it is on Fridays   
10:51   
right around noon Eastern time in North America. So, I don't know what that is   
10:56   
in India. Um but we'll we'll kind of figure out who wants to attend.   
11:01   
Everyone's free to attend. If you're accepted to GSOC, of course, you have to attend. But if you weren't if you worked   
11:07   
with our group and you weren't accepted to GOC, you can still attend the open source meetings. And you know, we do   
11:14   
actually go well beyond GSOC. So the idea of the open source meetings is to present G-S projects, but also to talk   
11:21   
about topics in open source. And then if we're doing open source projects independently of GSOC, we can talk about   
11:27   
those and present on those and everything else. I usually do a topic in open source every meeting. So we, you   
11:34   
know, maybe just spend 15 minutes on that. And so it's it's a nice de uh uh   
11:40   
professional development opportunity. So I'll be in touch more about that as   
11:45   
we get closer to the time. Usually between May and October, May and September, we usually run these open   
11:51   
source meetings in in the lab. And it's I think it's very useful to people. We also have them on our YouTube channel   
11:57   
from past years so you can check out what we've were talking about last year for example and and get a sense of what   
12:04   
we're doing. Okay. So um I guess uh we want to present today I know we have a   
12:09   
number of people wanting to present their projects. Uh so who wants to go first?   
12:14   
I'm audible right? Uh so hi um I'm Vidi for those of you who don't know I have   
12:20   
contributed to GSOC like I've contributed to oral as a part of the Google summary of code already and I was   
12:26   
a part of oral like I've been a part of oral since one year now and I did the   
12:31   
sustainab project the opensource community sustainability project last year like the GSO 2026 project uh I'm   
12:39   
presenting today uh as the part of the extension of this project like the part   
12:44   
of the project which I would be doing in 2026. So before I actually talk about what my proposal for 2026 is since it's   
12:51   
a continuation of the previous project, I would like to talk a bit about uh that project as well because some people over   
12:57   
here don't really know what that project was but yeah like Bradley Morgan Sal   
13:02   
because you all are my mentors. So right so I named the open source community sustainability uh project a sustain hub   
13:10   
and uh it was mentored by Bradley Jesse Sara Mahul and Morgan so thanks a lot to   
13:16   
my mentors and uh yeah just to let you all know I am Vidi I'm a third year B   
13:23   
tech student pursuing computer engineering at VJTI and yeah so talking about the project so   
13:30   
basically we know that opensource communities for example GitHub is a big example of open source communities and   
13:36   
we have gitlab and other examples as well. So we see that there's some uneven workload distribution. There's some   
13:42   
contributor burnouts there are dropouts that are knowledge related queries and whatn not and then it's hard to maintain   
13:48   
the long-term sustainability. So the main problem statement is that how do we keep an open source community sustain   
13:54   
community stable and efficient. So for that we have this project and uh I   
13:59   
propose sustain hub for that. So the overview of the project is that it is an agent based simulation of the open   
14:05   
source community and it models the real contributors and tasks. So we use I have   
14:10   
used reinforcement learning for task allocation and decision making and uh I   
14:16   
used like the goal was to have balanced workload and high engagement.   
14:22   
Uh right. So continuing with it, I categorized the whole thing into like four agents and the four agents were   
14:29   
maintainers for assigning the tasks. Contributors for fixing the bugs, innovators for building features and   
14:35   
knowledge curators for documentation. So there can be more but I briefly categorized the contributors into these   
14:41   
two like these three categories. Four other because uh previously when this project had been done there were only   
14:48   
two types of uh agents like the maintainer and the contributor. But I classified the contributor into three   
14:54   
different classifications as well and the maintainer remains the same. So uh since I use reinforcement learning and   
15:01   
we know that reinforcement learning involves math and majorly reinforcement learning means that there's an agent   
15:06   
which acts in an environment and based on how it has performed an action in an environment it gets a reward and the   
15:12   
reward can be positive or negative and based on the reward it takes the further actions. So like as I mentioned earlier   
15:19   
like contributor supposed to do the bugs innovators do the features knowledge creators do the docs. So I want so what   
15:25   
I did was that uh so that the contributor does bugs it gets a higher reward for that like it gets plus three   
15:30   
for that minus one for failure and zero if it skips the tasks and similarly for   
15:36   
innovator knowledge curator and for the other ones if the contributor is doing a feature task it gets a plus one and   
15:42   
minus one for failure. So this was like the basic uh maths that I used in the simulation and we are talking more about   
15:50   
the reinforcement learning part. So there were basically two uh main   
15:55   
algorithms that I used multi-armed bandit bandits which was more on the math math side which was exploration and   
16:02   
exploitation and s of the state action reward state action where the agent learns behavior over time. So this is a   
16:10   
this is the picture of how multiam bandits works. So this is the maintainer and the arms are nothing but the tasks   
16:15   
and a b cde e f are the contributors. So this is just to show how it works but uh   
16:21   
this was done mathematically in the project. So moving on this was the equation I don't want to get into like I   
16:28   
don't want to get much into a technical part of the project but uh yeah talking about what I had used this was the   
16:34   
thomson sampling in multiam bandits where theta was dependent on the successes and failures. Every time a   
16:41   
contributor did a task, we used to either calculate its success or failure. Success means it has done the task and   
16:46   
failure if it hasn't done the task. So this is the ma basic math behind it and uh yeah I don't to get very technical   
16:52   
but then when I talk about the future scope of this project I have a comparison that's why uh a math brief.   
16:59   
Then we had the SASa working state action reward state action. So this is the basic equation of SASA where Q is   
17:06   
the Q value of like the particular state and action which get gets gets updated based on the current state and the   
17:13   
action Q value plus the learning rate plus reward and oh yeah gamma is the discount factor with the next state   
17:20   
minus the Q value of the current state. So this is the equation that we use for SASA in general and this is the equation   
17:27   
that I used for calculating the Q values for each of the contributors in my GSO   
17:32   
2025 project and these were the outputs. So step one basically I was running it   
17:38   
for a lot of steps and after every step I was showing these outputs of the   
17:43   
contributors and how they have performed. So the maintainer would assign tasks using multiarm bandit. So   
17:50   
these three steps talk about that and then next three talk about the uh results of the assigned tasks that   
17:57   
whether they were performed or whether they were not and then using the success rate like the success rate formula that   
18:02   
we have we calculated the success rate for each of the tasks. So how many are assigned and how many are done and then   
18:09   
based on that the success rate. So like that for every step I used to show. So   
18:14   
yeah and then the Q values were stored in the JSON tables like this. So there were three types of task like bug,   
18:21   
features and docs. And based on whether it has done the task or skipped the task I uh use the Q values used to be updated   
18:29   
after each and every step and each and every simulation that I had like every single time you have to run the   
18:34   
simulation. So like we can see over here do task for docs is negative that means it has not done the task and for bug it   
18:42   
is it is very high 0.79 that's why uh mostly it has been classified this   
18:47   
contributor has been classified as a contributor not a knowledge curator and yeah like this was a lot about what I   
18:53   
did last year so my mentors know but about the other people right so this was   
18:59   
again one of the graphs that I had used to show how the uh outputs are like   
19:05   
After a lot of steps of running it, we can see that contributor one has done an   
19:10   
has done the bug task around 89.7 times. And then similarly for the three tasks   
19:15   
and all the 10 agents over here this image shows 10 but then when I done the   
19:20   
project I had like the final uh simulation which was created could   
19:25   
actually have more agents involved but anyways right so the project also   
19:30   
involved some metrics. The metrics were harmony index for calculating the workload balance, resonance quotient for   
19:37   
handling the dropouts and reassignment overhead for calculating the efficiency. So the major reason for these metrics   
19:43   
was for that so that we can check how well the IL simulation is and the metrics would give us some output and   
19:49   
with the output we would figure out whether the project is doing well or not and if it's not doing well then how can we improve it and how much improvement   
19:56   
does it need. So the metrics were just to show the outputs and how much we can improve. So a bit more about the   
20:02   
metrics. The harmony index was around 0.8. The resonance question was between   
20:08   
1 to 5. Harmony index the range was 0 to 1 but a good harmony index was around   
20:13   
0.8 and above. Resence question had a range of 1 to 5 and it improved the task   
20:18   
distribution stability and I had built a GUI which is a graphical user interface   
20:23   
and a visualization dashboard. So this is how the metrics would look and this is just a graph of the metrics on the   
20:30   
visualization dashboard which is it shows the range like how I   
20:35   
said around 0.8 rate. It's a good range for harmony index. The reassignment overhead has a big range and so yeah and   
20:43   
the so the resonance question has a bigger range but reassignment overhead is constantly one that means each and   
20:49   
every task is being reassigned if it is not done. So why I chose what I chose in   
20:55   
2025, the different agents so that we can have a better real world simulation and we can differentiate between the   
21:02   
different types of contributors based on their skills, goals and behaviors and to enable richer interaction dynamics. Why   
21:08   
the multi-owned bandits? Because it was uh used to balance between exploration and exploitation and it was just simple   
21:13   
math so it would help us achieve what we wanted. Why SASA? Because the name itself suggest state action reward state   
21:20   
action so that we can have uh so that we can learn some of the ongoing interactions and adapt the strategies to   
21:26   
continue over time and the combination of multiarm brands plus salsa because   
21:31   
multiarm brands is quick adaptive and salsa defines the behavior through experience based learning and the   
21:37   
metrics just help us understand better as I spoke about it before. So this is just about a few results of my project   
21:44   
from last year and this was the simulation where the blue   
21:49   
circles are nothing but the contributors and the yellow uh yellow squares are the   
21:55   
tasks of the contributor such as the task that means the was just a stimulation that I wanted to show apart   
22:01   
from the math and the outputs which were there in the GUI and yeah so I   
22:06   
documented everything into a paper which is available on GitHub right now in the same repository as where I did the   
22:13   
project. So if any of you all want to go through it, you all can go through this paper and get a better understanding of   
22:18   
the project with the details and the math which is used and I used to update the readme. So I updated the readme to   
22:25   
talk about how we can run the project and basically what the project was along with a blog page. So the blog page had a   
22:32   
weekly explanation of what I did in each week. So you can go through that as well. So now talking about my vision for   
22:39   
2026. So since it's since it is a continuation of the project, I would like to make the project smarter, more   
22:45   
realistic and like a resource level system. So it is a simulation but from a simulation I want to go to an   
22:51   
intelligent adaptive system in a simulation itself because we can't achieve a lot of real world right now   
22:58   
cuz it requires a lot of hardware. But I would want to improve this simulation. So the key improvements that I proposed   
23:04   
this year are contextual task allocation, salsa, lambra for long-term learning, new sustainability metrics and   
23:11   
some comparative analysis of the models. So the first improvement is contextual bandits. So instead of just using   
23:18   
multiarm bandits, we can use contemp contextual Thompson sampling. So it uses workload skill match burnout and the   
23:24   
benefit is that there is better task agent manage uh task agent matching. So   
23:31   
basically this is the formula over here that theta is the probability of some theta with some context and what 80 is   
23:38   
over here that it's the maximum of this value. So this is the older one that I   
23:44   
had used in 2025 where the theta depends only on theta a which is the history and   
23:50   
the theta new depends like the theta for like the contextual the contextual   
23:55   
bandits will actually have theta as well as xt and xt is nothing but some context   
24:01   
which is given to the thing. So it is not only on the bas of history but also   
24:06   
some context. So along with history we can add some context about which contributor can do which task well. So   
24:13   
the first few steps will obviously use just map but then after that we can have this as a middle middle step will   
24:18   
directly start with this so that there's some context involved and we can get a better understanding. So task allocation   
24:25   
becomes state aware instead of history only and these two other papers which I had referred to uh to which motivated me   
24:32   
to use contextual Thompson sampling. And the second improvement is SASA Lamra. So   
24:37   
it adds me memory which is the eligibility traces and it learns long-term effects and captures burnout   
24:43   
accumulation with delayed rewards. So this is the SASa 2025 working which I   
24:49   
spoke about a while ago where this is the equation the standard equation for SASA. But if we see SASA lambda this is   
24:57   
the equation where we have an extra e term involved. So this delta is the same as this uh thing that is in the squared   
25:04   
brackets after the learning rate alpha. So we have alpha delta and this is the e which is the eligibility trace which   
25:10   
tracks how recently and frequently a state action pair was visited. So the state action pair visited in our case is   
25:17   
nothing but a contributor and a task which has done. So over here like we   
25:22   
kept on updating this but then rather than updating this we can make the use of the history that we get from this.   
25:28   
For example contributor one does bugs more. So it can do more of the bugs by using this thing and   
25:35   
for that we have this sa lambra which will help us. So we have the eligibility   
25:42   
trace for that which will help us perform better and yeah this is just a   
25:47   
bit more theoretical that it captures more long-term effects and updates multiple past actions not only the latest one and it's faster and more   
25:54   
efficient. So that is about SASA lambla. Now about the metrics because my   
26:00   
previous project also had some metrics like the harmony index resonance quotient and the the reassignment   
26:06   
overhead. There are three more which is the burnout risk score, skill utilization efficiency and common health   
26:13   
score. So these are just some metrics which would probably help like which will help me in the project more and   
26:19   
understand how well the new SASA Lambra and the contextual map is in the project   
26:25   
and we shift from performance to sustainability evaluation and the experiments and validation. But   
26:33   
before I talk about this, why are these improvements there like especially improvement one and two? Because uh last   
26:39   
year when I was doing the project, if there was something a result that I was getting after running the simulation for around seven eight times, we can use   
26:46   
these two neuro techniques also Amra and the contextual map and we can get the   
26:51   
same results in the first few the running of the first few simulations itself. So if we get something in the   
26:57   
seventh simulation, we can get the result in the third or fourth simulation itself. That's the aim and yeah so   
27:04   
talking about the experiments and the validation so then so the current model is multiams with s plus sasa but once I   
27:11   
improve the multiarms bandits we will have the contextual uh thompson sampling with sasa then we can compare map with   
27:18   
the new sasa and then we can compare both the new tech like we can add the new techniques contextual this thing and   
27:25   
sasa and we can compare everything so we will know which of the four models is better is the previous project better or   
27:32   
are the the two the two new improvements better or a combination of these and then we can obviously evaluate the   
27:38   
conversions burnout and efficiency. Well, thank you. That was great.   
27:43   
Okay. Uh did we have any questions or comments? Uh so yeah, that looks great.   
27:48   
So you're just proposing to add things on and and those things are going to   
27:54   
improve the performance or or kind of add some depth to the performance. Yeah. Sorry, I just included more of the   
28:00   
technical part of it like the new alos that I would be doing probably and I   
28:05   
didn't like but obviously it goes along that I would continue with the blog post every week and improve the simulation   
28:12   
that I had last year. So yeah about that. Yeah. So could you pull up your slides   
28:18   
again? I wanted to see that last slide where you were talking about the things you want to evaluate this year.   
28:24   
Uh yeah, that one. So you're evaluating burnout, convergence and efficiency.   
28:31   
So what is convergence? Uh convergence tells us like earlier like if you remember last year when I   
28:37   
did the project the uh earlier the agents were unclassified. So they used   
28:44   
to remain unclassified until and unless like for the number of times I used to keep running the simulation again and again. So there used to be some edge   
28:51   
cases where the agents were still remaining unclassified. So they can get classified sooner and like the correct   
28:58   
classification whether it's a knowledge curator or an innovator or something. So we can have the convergence of the   
29:04   
correct like the correct labeling or the correct classification as well as them being assigned the correct tasks earlier   
29:11   
as earlier as possible. So that's why convergence. Okay. Yeah. And then then burnout we   
29:17   
know what that is. Efficiency we know what that is. I mean, uh, burnout, you you have like equations   
29:23   
in mind for this or you have ways that you have in mind to to measure them, right?   
29:29   
I Okay. Um, Morgan, did you have a question?   
29:35   
Um, well, excuse me. Sorry. I'm I am driving. Um, but uh but I am handsree.   
29:43   
um the but to ju just a kind of   
29:48   
philosophical question or a kind of um architecture question. So this is this is a centralized system.   
29:55   
Yeah. Like like there's there's and what you're comparing are kind of different   
30:01   
centralized systems in terms of the um in terms of their   
30:09   
their metrics. Um, in terms of of the agents,   
30:16   
um, how much how much autonomy do the agents have in their tasks that they they they're totally assigned, right?   
30:24   
Yeah, they're totally assigned and then they have the the main autonomy that they have is in the beginning where all   
30:30   
of them are unclassified. So they don't know what they are going to be assigned and based on their actions they will be   
30:35   
given some classification and the next autonomy that they get is whether they will do the task or not. So they can   
30:41   
skip task or if they do it and if there's a success or failure. So that was that's the part of autonomy in the   
30:47   
agents. Gotcha. Gotcha. Because after they have been classified there's a very less chance that they   
30:53   
would actually want to do some other kind of task because there's a particular task that they are good at.   
30:59   
That's why they have been classified as a particular agent. So they have autonomy to our project.   
31:06   
Okay. Okay. Yeah. Now just just making sure I I understood and um uh you know   
31:14   
like like it's been very interesting to read your your paper and um to learn   
31:20   
about the uh learn about the methods you're applying. So yeah, thank you.   
31:27   
Welcome. Thanks. Yeah, Morgan. Thank you. Uh,   
31:34   
hi. Hi. Hi. I'm traveling so the network might be a bit dodgy. Uh, so I was able to go   
31:42   
like for your presentation somewhat. Um, I go through it more in   
31:48   
detail later. But uh one of the questions I had was have you given any thought to some kind of collaboration as   
31:56   
a as a feature for this between agents? Uh not yet. I was completely relying on   
32:03   
a particular agent doing one task. But I think yeah we can have this as a part of   
32:08   
it that if a task is big then we can have some metrics for the size of the task and depending on the size of the   
32:14   
task we can involve a few number of agents. So I'll have to look into it and if it has been implemented before and   
32:20   
since it's how will the match work over there. So I'll look into that and I'll get back   
32:25   
to you on it. Yeah. Okay.   
32:31   
All right. Yeah. Thank you. Uh yeah. Any other questions? So yeah, I   
32:37   
enjoyed this project last year and you know we're doing so this is for people who don't know this is sort of our   
32:42   
reinforcement learning part of the uh project. So we have the large language   
32:48   
models part of the project and people have been uh you know putting in pull   
32:54   
requests for that and then we have the reinforcement learning and there's a lot to do in the reinforcement learning area   
33:00   
as well like you know this is like um pulling all the threads together but we   
33:06   
do have other uh reinforcement learning code other types of things that we're doing   
33:13   
there. We also want to kind of make links to active inference and I I'm   
33:18   
particularly interested in this link to active inference because and not only is it uh sort of uh you know we we've done   
33:27   
this before but there I I see people more and more making ties between reinforcement learning and active   
33:32   
inference and it's it's really I think for agents it's at least something to   
33:39   
consider uh using in in terms of the model. I don't suggest that VD use it in this   
33:46   
case. I think she's got a good uh set of things that she's wants to explore in this proposal. But just to throw that   
33:53   
out there uh when we're doing a lot of this work. Uh now that being said, the   
34:00   
large language models and the reinforcement learning kind of remain separate up to this point. So I don't know how much sense it makes to kind of   
34:07   
integrate those um in different ways. But definitely I think uh you know   
34:13   
that's something that is maybe a next step although I think for now we would   
34:18   
work on separate tracks at least for this summer. Um so that's that's uh that but thank you   
34:26   
VD for presenting on that. Okay. Uh we have other people want to   
34:32   
present. So uh hi everyone my name is Ria and I'm   
34:37   
a recent graduate in computer science engineering and I have been contributing to this uh environment in this uh   
34:44   
repository and I'm this is my proposal uh presentation regarding my proposal.   
34:50   
Okay. So uh I proposed adding a conversation   
34:56   
space to LM OC. So these were some of the issues uh which were addressed and   
35:03   
uh according to these these keeping in mind I have created my uh architecture   
35:08   
on how I want to proceed this uh this was my adding a conversation space to len that's my proposal so these were the   
35:17   
issues that I kept in mind and the comments on this but for creating my proposal   
35:22   
the real world data ingestion and researchbacked uh rag and real world   
35:28   
community sustainability and engagement metrics and front- end integration. So my proposed solution is divided into   
35:35   
three layers. First layers is world grounding where I would be ingesting real world archives from Slack, IRC and   
35:43   
Discord. The second layer is event sourcing. This is the part where the conversation space   
35:49   
is there along with engagement metrics. And the third part is the uh agentic   
35:55   
rag. Uh so the first uh going to the first   
36:00   
layer. So this is divided into four parts. So so the first part uh I'll be   
36:07   
ingesting and parsing data slack and discord. So to get us uh to make it a   
36:14   
and then I would move to uh creating it into a common message schema   
36:21   
and then I would be uh moving on to chunking. Chunking because not every   
36:26   
message would make uh like the context won't be that much. So chunking them   
36:32   
based on threading and time would make the semantic retrieval during the   
36:38   
simulation and then I would be converting it into vectors using the embedding model nomic. So the key   
36:45   
architectures of this layer are uh like the I have done the research regarding   
36:50   
it and I've evaluated and compared with other uh like methods present out there   
36:56   
and all the details I have uh like linked in my proposal document.   
37:02   
So these are the things that I'm proposing right now. So the database I'm going with Chroma database because the   
37:08   
latency is uh 20 milliseconds which is negligible compared to Olama's 2 to 5   
37:15   
seconds inference and the embedding model that I have proposing here is Nomic Nomic embed model because it's the   
37:22   
only open-source model to outperform text embedding ADAP on MTB MTB retrieval   
37:29   
and runs via Olama and the thread chunking is the same way that I've uh   
37:34   
like discussed just now. So going on to the layer two is the event sourcing here   
37:41   
is the where the conversation space is there. This is also divided into three parts. The first part is ingestion. So   
37:48   
this is the part where the layer one orchestrates or it starts the pipeline starts and the second the retrieval is   
37:55   
the one which is being used by the rack. Here are the queries from the chrom with   
38:01   
role aware and simulation aware filters and the matrix are the opensource health   
38:07   
uh community matrix and sustainability score   
38:13   
and going onto the layer three that's agentic rag. So why am I proposing rag   
38:19   
here is because right now the knowledge that the agents have is parametric knowledge. they don't have real uh like   
38:26   
opensource archives and open source history which makes the response generic   
38:32   
and so and so it bridges the gap between the layer one which is the normalized or   
38:39   
schematic data and the agentic behavior but at the same time I'm not going with   
38:44   
standard rag because standard drag will lead to single agent and single pass which will lead to each contributor   
38:50   
retrieving independently and not aware of the prior agents discussion that have   
38:56   
taken place and cannot differentiate retrieval by contributor role versus   
39:02   
maintainer role. So I propose uh modular multi- aent track. So the uh so in my   
39:10   
proposal I have researched regarding it and the evaluation and uh everything is   
39:16   
uh linked to that. So just a brief idea that why modular. So here it's divided   
39:22   
into four the rag is divided into four discrete models. Each of the discrete   
39:27   
model is independent and easily replaceable without touching the agent code and it's multi- aent because they   
39:34   
have a shared context pool plus discussion coverage signal is used which means each agent's retrieval is shared   
39:41   
by prior agents discussion and role aware because planner differentiate contribute queries contributor queries   
39:49   
from maintainer queries. So there three uh layer 3's overview. So   
39:56   
there are three phases involved. The first phase is issue level shared retrieval which runs only once in the   
40:04   
starting. The planner creates a query and the retrieval happens and the filter   
40:11   
share context pool is stored in conversation space available to all contributors. So this data which has   
40:17   
been retrieved is available to all the contributors. Phase two is contributor personalized.   
40:24   
So here uh at every contributor's turn planner will give role based plus the   
40:30   
discussion based query which will be personalized to particular contributor   
40:36   
the retrieval will take place and the filter part will penalize already covered angles so that every time   
40:42   
there's a new uh angle we are discovering to the problem and the synthesis will order it or construct it   
40:48   
properly before giving the query to the ammo and the phase three is the mentor maintaining Maintainer selection. So   
40:55   
after discussion if the algorithm is authoritarian maintainer retrieves real   
41:00   
contributor patterns for this discovery tier to calibrate contributor agent   
41:05   
ratings. If if the algorithm is decentralized contributors retrieve real   
41:11   
community approaches to similar issues to ground their self bid.   
41:17   
So as I said the rag is divided into four configurable modules. The first   
41:24   
module being planner. So that decides the query type the metadata filtering and the recency window like how recent   
41:30   
should be the data which is being retrieved for the agent role. And the retrieval is more of a semantic   
41:36   
retrieval of the metadata. And the filter is relevance where we have the   
41:41   
score uh we have a relevant score. So which is b which is backed up by a   
41:47   
research paper which penalizes angles that have already already been discussed and so and the synthesis is basically   
41:54   
construction of all the queries and blocks. So and time stamps so before   
41:59   
giving it to the ama and this is the important part multi-   
42:05   
aent coordination. So there are three points in where the modules are shared across agents not running independently.   
42:14   
First is shared context pool. So issue level retrieval runs once. So all the   
42:19   
contributors draw from the same base context pool rather than each time running redundant queries. Discussion   
42:26   
coverage signal growing discussion history is fed back to the filter module. Chunks covering angles already   
42:34   
discussed are penalized. The discussion shapes its own retrieval. And the third part is collective track record which is   
42:41   
used by the synthesis module runs once per contributor being evaluated in   
42:46   
authoritarian mode. Difficulty match contributor pattern query to calibrate   
42:52   
maintainer ratings and in a decentralized similar issues query to ground each contributor self bid.   
43:01   
So this is the timeline and this is the front end integration that I have to I   
43:07   
have been proposing which includes matrix dashboard, slack like discussion view, sustainability   
43:13   
score and conversation space panel. Yeah. Hello. Hi. Am I audible?   
43:19   
Yeah. Yeah. Yeah. Uh yeah. So a few questions. Firstly uh I saw that   
43:25   
whenever you me mention uh about the agents talking uh you were only talking   
43:32   
about it from an issue perspective like you were like currently how it happens   
43:38   
in the author authoritarian and decentralized models. So the conversation that happens   
43:44   
currently you're trying to replace it with rack right?   
43:50   
Yeah, but the uh I mean the whole idea of conversation space was to simulate   
43:57   
all the conversation that would happen in an open source community and that was the reason we are pulling in archives   
44:03   
from Slack and Discord. on Slack and Discord people don't usually talk that much about the GitHub issues that   
44:10   
conversation is done on the GitHub PR comment section and that will stay like   
44:15   
that's already implemented and that will stay right but what you're trying to enhance is the conversation that would   
44:22   
happen otherwise the whole community that would talk about everything about   
44:28   
how they want to progress about new contributors coming in and about everything that happens in an open   
44:35   
source community. So I feel like you should focus on that not try to it's okay if you want to   
44:42   
enhance the way the authoritarian or the decentralized model also works. So that would be a different thing but that   
44:48   
would not be the solution to the issue of conversation space. The issue of   
44:54   
conversation space relates not at all to GitHub. Okay. But the transition will still   
45:01   
happen but will be assisted with that in I I'm say yeah I understand that's what   
45:08   
you're proposing right? Yeah I'm saying that the issues I mean the the the comments that are left on issues   
45:15   
even if there is say 50 to 100 issues in some repo and each issue will have maybe   
45:22   
like five to 10 comments that still does not justify a whole rag database. What justifies a rag database is a   
45:29   
conversation where everything from hi a new person has joined to everything that   
45:36   
anybody can talk about like you take our community for example you go through all the channels on our slack and there's so   
45:44   
much context there it's people sharing papers people sharing what they did this week all of that some of that takes   
45:51   
growth into it it's people talking about GOC for example or any other such programs that may happen regularly in an   
45:58   
open source community. There's also uh in when you start studying about open source community uh there's a lot of uh   
46:06   
talk about how people are incentivized to contribute because there is no   
46:11   
incentive or there's no monetary incentive. So there is this talk about how to get new contributors in, how to   
46:19   
keep the contributors who are there, how to keep them integrated and attached   
46:25   
with the community, how to build community and that is where the people talking to each other face comes in,   
46:31   
right? It's not the PR uh the comments on PR like that is a part of it but   
46:37   
that's not the whole thing. So you you should you should focus on that because on flat people don't talk   
46:45   
about PRs right usually or discord or any other is   
46:51   
so that would be the first thing secondly you said you have looked into taking in discord and slack architects   
46:58   
so how have you looked into them what software what licensing uh have you thought about all of that   
47:06   
yes yes I have uh I the archives are available But uh I'll have to look into it more.   
47:13   
But yeah, so by archives do you mean some specific data sets or any any Slack channel, any   
47:21   
Slack workspace, any discord channel? Uh yeah, I mean I have to look into it   
47:27   
more but there are modules for passing. So I was thinking of using them. Yeah,   
47:33   
is one thing but also how would you get the data because this   
47:39   
I yeah so yeah that's one thing and then   
47:44   
also the front end integration part you skimmed through I think quite quickly but one doubt I had was if you can just   
47:52   
go back on that slide which okay one second the front identification   
47:59   
identification basically my doubt is that how would you so all this when you say that you know   
48:05   
quirma is called and all these agents are talking to each other are they   
48:11   
talking in a multi- aent format or are they talking with like English like   
48:18   
spoken language do we have when they're talking to each other do we have enough conversation to relate to front end   
48:26   
yes they are talking in spoken English language okay Okay. Okay. Okay. Great. Great. So   
48:33   
I think one other thing you can look into is how they would talk not just about the issues. Issues is a very small   
48:39   
part. We already have methods for that. The authoritarian and decentralized model. All you can do is plug those   
48:45   
existing modules into the into your conversation space. So maybe you could   
48:50   
decide you could have a separate conversation space for chat and you   
48:56   
could have a separate conversation space like chat would be equivalent to whatever the organization uses slack   
49:01   
discord whatever and you could have a separate conversation space for the GitHub related code related review   
49:07   
related things where who has to solve this issue what is the maintainers   
49:13   
review on it and everything so that will the agents participate will   
49:19   
be participating in chat and we'll be like yes different simulation   
49:24   
no team agents that's it it will influence each other the same way in an actual open source community if people   
49:31   
are talking more they there you you will find data on all of this and you need to   
49:37   
research about it but uh as far as I know there would be some uh patterns   
49:42   
like people who are more active in the community would you know also contribute more and maybe they would be the senior   
49:49   
people maybe they don't have that many lines of code but they're more active because they are reviewing more and they   
49:56   
are talking more and they're sharing knowledge there's knowledge transfer and all of that so there'll be pattern and   
50:02   
those that is what we can simulate right so there'll be metrics and that is what we can simulate   
50:08   
and another thing is you should also look into metrics for all of this okay and a small technical doubt you   
50:15   
said at the beginning that you are Uh you are preferring chroma as its   
50:21   
inference is faster than so you talking about as a database. No,   
50:27   
no, no, no, no. Like is in local   
50:32   
the chroma database will be local and then running it   
50:40   
right but I'm not understanding why did you compare it with no uh I compared with other databases   
50:48   
like pine cone uh and others. Okay. Okay. Okay. Yeah, I thought in because in your slide I'm pretty sure it   
50:54   
said that Olama's incidence is about some seconds and this is something else.   
51:01   
So that line I was confused about. So basically it goes together. It's like   
51:06   
the uh it's more but as it is less it will be able to you know collab do it   
51:14   
with together basically. Yeah but I Okay, maybe you can just DM   
51:20   
me about this. I'm still not um I still have some questions. Yeah. Yeah. If anybody else has some questions, please   
51:26   
go ahead. Yeah. So, the llama, you're just running it on a llama. You're training it with the database.   
51:33   
Okay. Yeah. Yeah. This rag idea is pretty interesting. I mean, we've been   
51:38   
playing with them a little bit. um you know where you can customize it with specific data sets and you can see you   
51:46   
know if you can kind of get really specific   
51:51   
um you know uh prompts and things like that and and see if you can get really niche kinds of answers out of the uh   
52:00   
large language model. Um, yeah. So, I mean, and another thing, and I don't want to confuse this too much, but like   
52:06   
Sara was talking about how our discussions sometimes are different in terms of the   
52:14   
the different media we're using. So, if we're on GitHub, we're maybe doing having issues around specific issue or   
52:20   
discussions around specific issues. If we're in Slack, we're having different types of discussions. It's just of   
52:26   
quality. Sometimes, of course, they overlap. Um so this is going to be like   
52:32   
totally dependent on the team style. Uh some teams will just kind of do everything in GitHub. They'll have long   
52:38   
discussions there. Sometimes they'll have different discussions types of discussions in Slack. And so it's and   
52:45   
then of course you do have that difference in this like authoritarian versus decentralized.   
52:52   
Uh a lot of times though that you know that may show up in the discussions but it may also be like there's this style   
52:59   
of management that is it might show up in the discussions it might not and it's   
53:06   
hard to say you know it's hard to make that distinction. So I mean some of this is going to be um you know harder to   
53:15   
because it's it varies so much by team and but so we can model it and it we   
53:22   
have to be very explicit what we're modeling. So if we decide we're going to model um maybe an authoritarian style of   
53:30   
issuing um you know just creating issues, we might have one person that   
53:35   
creates all the issues and then like everyone has to sort of follow those to the letter versus a team that just kind   
53:42   
of creates their own issues and there's a lot of discussion about the structure and form of the issue and all of that.   
53:49   
So those are like both possible but we want to like we don't want to muddy the   
53:55   
waters too much. We want to just have like one methodology for doing this. Um   
54:01   
and so that that's kind of important to keep in mind is like we don't want to when we do experiments we want to keep   
54:08   
as many things constant as possible and then we can like kind of deal with the details later. Um, so that's just, you   
54:15   
know, really kind of thinking about how you would kind of get started and structure things and you have to make   
54:22   
decisions sometimes about how you're how you're defining a conversation. Uh,   
54:29   
because sometimes, you know, conversations are very this is not an easy problem. Um I know the using large   
54:35   
language models makes this look easy where you can parse discussions and and get uh simulate things but really you   
54:42   
know discussions are going to be very different based on power relations right who's who's   
54:49   
talking to who it could be just kind of the style that a lot of people just kind of do things in GitHub some teams will   
54:56   
be more formal and have like things in Slack and they'll just stick to certain things in Slack and certain things in   
55:01   
GitHub Um and you know sometimes it's just they're using um in person. So   
55:08   
sometimes their modality is like in-person meetings. So they don't talk about a lot of things there. They'll   
55:14   
talk about some things in Slack, maybe some uh things in GitHub uh related to   
55:19   
the issues, but most of it is like synchronous communication. So that's   
55:24   
another problem is that if you took a data set and we don't have good access   
55:29   
to like different teams because they usually are private but if we had a data set um from like you know if we had data   
55:37   
from 10 different teams that data would be very widely variable in terms of how the discussion would flow right um   
55:44   
because every team is its own kind of style. So, we have to kind of think about normalizing this um and making   
55:51   
sure that we don't kind of bite off more than we can chew on this.   
55:59   
Yeah. Well, yeah. No, I think it's great work. And, you know, I like this idea of using a rag and um and I think at this   
56:06   
point, you know, it's like kind of be just seeing if you can get it implemented and say this is how it could   
56:13   
work. this is how we can you know uh kind of tailor it to discussions because   
56:19   
their unique challenges there and that sort of thing.   
56:24   
All right. Thank you. Thank you. So we had V and Ria and did we have   
56:30   
anyone else who okay Ashot wants to to present?   
56:36   
So uh I wasn't able to make a dedicated PPT. So I'd like to present my proposal   
56:42   
form and uh I'd just like to start a bit on where my thinking started. So we are   
56:51   
basically talking about adding a conversation space to enhance the   
56:57   
simulation that uh some communities use Slack to   
57:02   
talk. So the talking in Slack is obviously bound to uh change the GitHub   
57:10   
uh PRs and issues etc. So I have thinking I have been thinking of   
57:16   
reworking the motivation system we have in the project. So the current motivation here I'll show uh the current   
57:24   
motivation is a bit like this. If someone's PRs get accepted then his or   
57:31   
her motivation rises. If they get rejected then it falls down. So this is   
57:37   
a very good starting point but I believe it will become more complex and it will   
57:43   
need to be updated whenever we add the conversation space.   
57:48   
So I have looked through some research papers on motivation and in o in open source communities   
57:57   
motivation is the primary predictor of contributor productivity and retention.   
58:03   
So motivation is basically the central thing for this project. And one more   
58:09   
research uh quantified the uh prediction of individual motivators.   
58:17   
And here it divides basically into two types of motivations. First is intrinsic   
58:24   
motivation. uh we we've also studied it as internal motivation and external motivation such   
58:32   
as money or community. So this is the uh table from this paper and as we can see   
58:39   
the internal motivators, enjoyment, ownership, learning things which are   
58:46   
limited to oneself internally. They are much more better at   
58:52   
predicting the motivation and these should be focused in an open source to   
58:59   
help increase its sustainability and uh external motivators are rated a bit   
59:05   
below at prediction of a motivator. So now this one was a bit surprising to   
59:11   
me as well. payment doesn't cause as much motivation as enjoyment or ownership most likely due to burnouts or   
59:19   
some other things. So firstly I would like to uh rework this motivation system and I   
59:27   
will use these as weights to update a motivation whenever we when an action   
59:33   
takes place. Now second is I want to talk about the agent actions.   
59:39   
Now actions of an agent. Right now they are just submitting PRs and   
59:46   
reviewing the code. So I'd like to expand the action set of one agent. So   
59:52   
they can join a project. They can talk in conversation space. They can comment   
59:58   
on a GitHub issue or a PR for a better structured decision discussion. They can   
1:00:05   
submit the PR. Now this is currently implemented. I don't think this would need much more work. The core members   
1:00:11   
can assign issues. Uh reviewing code whenever available. Opening a GitHub issue. Right now   
1:00:18   
everything starts at the beginning and the contributors don't open the issue.   
1:00:25   
It open it is basically opened by the system. So I'd like to implement the   
1:00:31   
capability for an agent to open the issue as well. leaving the project. I'll talk about the leaving and joining part   
1:00:38   
later. And mentioning another contributor now I think this is very   
1:00:43   
central part to emulating a real discussion. We use ad signs to mention   
1:00:49   
other contributors such as someone has started talking so we would mention them and continue the   
1:00:57   
conversation that way. So these are the actions one agent can have. I'll refer   
1:01:03   
to them as actions from now on. Now this is my favorite part. Uh I think Vidi   
1:01:10   
also touched on this on her presentation roles in an OSS project. So   
1:01:17   
I've gone through this paper by Chang and Go and they have analyzed 20 thou   
1:01:23   
more than 20,000 unique contributors in 29 GitHub projects. Now uh I'd like to   
1:01:29   
make this diagram a bit bigger. So uh this is basically them clustering   
1:01:36   
the overall contributors into two major groups. So there is basically two groups   
1:01:43   
supporting participants which are the silent majority. They provide much less   
1:01:48   
value to the project compared to the active participants which are the   
1:01:54   
minority but they do most of the work. So I think in the current implementation   
1:01:59   
of the project we can uh we can use analogy that supporting participants are   
1:02:05   
the contributors and active participants are the maintainers. So this is the first thing and now these   
1:02:13   
are the major groups. These groups are divided into minor groups as well. Uh   
1:02:20   
yeah so here are the minor groups which are the active contributors can be divided into. Now these are based on the   
1:02:27   
actions they take. So intense code contributors, coordinators, code   
1:02:34   
developers and all rounders. These are the four major groups and they all perform different actions.   
1:02:41   
So uh here are the actions they perform. So all rounders are the middle part.   
1:02:48   
They perform everything at an around equal level respect to each other.   
1:02:55   
coordinators they focus on issue reporting and knowledge sharing and issue coordination. Core developers   
1:03:01   
focus on progress control the most and they they don't report issue as much.   
1:03:09   
Now this is the my favorite group intense code contributors. They are the ones focused on code   
1:03:16   
contribution. As you can see the part actually goes out of the diagram. So   
1:03:22   
they are very focused on the code contribution part. So we can model the   
1:03:27   
maintainers based on these roles. We can assign them one role and then model it. For example,   
1:03:34   
if we assign one maintainer agent to be co-developer then he would not issue   
1:03:40   
then he would not report many issues but he will focus on pro progress control and knowledge sharing. So this way we   
1:03:47   
can actually test how the opensource project will develop under one type of   
1:03:55   
maintainer and similarly the contributors can also   
1:04:00   
be assigned into six different roles. Now uh I think only one group stands out   
1:04:07   
here the most. Those are the rare contributors. These are the majority and   
1:04:13   
they pro provide the least value. As we can see they have almost everywhere they   
1:04:18   
have the lowest distance from the center and we have some specialized   
1:04:24   
supporting contributors with some engage in issues some engage in fixing those   
1:04:29   
issues and there are progress based also. So we can basically   
1:04:36   
model these roles into our project. So we can test how better uh how which   
1:04:44   
leadership is best for an opensource sustain to be sustainable and what type   
1:04:49   
of contributors supporters are best. Now one more thing I'd like to uh say here   
1:04:57   
is the changes in role. Now we know that one person who is uh core de core   
1:05:05   
developer will get burnt out and he may move to a smaller role or there is   
1:05:11   
someone who is highly motivated and highly skilled so he can move into a upper role to be a maintainer of the   
1:05:19   
project. So we can use this graph to model a marov state type of diagram that   
1:05:28   
if someone is a rare contributor that means he rarely contributes then he is   
1:05:33   
most likely to leave the project that is being absent. Now I'd like to point out   
1:05:39   
the rare contributors. These are the types. These are the most uh   
1:05:50   
they like if someone is absent then he's most likely to become a rare contributor   
1:05:56   
and if someone is a rare contributor here then he's most likely to be absent.   
1:06:02   
So this shows that uh the current simulation basically keeps them in a box. So I'd like to model also to this   
1:06:10   
to be more dynamic. We would like to give one agent the freedom to leave or   
1:06:15   
to join a project. So I have talked about this later. Now I'm skimming this through a bit. But here's the diagram I   
1:06:23   
have made. The current model is like this. We are   
1:06:28   
essentially keeping them in a box. They can't leave or they can't join. So I'd like to propose an active classroom type   
1:06:36   
of approach. We have the watchers who are looking at the project but they are not contributing and they're outside the   
1:06:43   
room. On the doorway there are rare contributors. Those who contribute the   
1:06:48   
least they have the tendency to leave and they have the tendency to join the   
1:06:54   
more active roles. supporters can become the the all four roles can uh transmit   
1:07:02   
to trans can convert to another role based on this uh diagram I have shown   
1:07:09   
here. So any feedback on this approach?   
1:07:15   
Yes. Yes, you are. Oh yeah. Okay. So this is uh yeah you're you're   
1:07:20   
audible. Did you want to is are you done with your presentation or   
1:07:29   
pretty much. No, no, I'm I'm at a checkpoint. Uh I'm like halfway through my presentation to   
1:07:35   
just get feedback. Just checking. Okay. Yeah. Go ahead. Yeah.   
1:07:41   
So, I'd like to get any feedback on this new proposed architecture. Instead of   
1:07:48   
keeping them in a box, we are keeping them in a classroom.   
1:07:55   
Yeah, I think that's great. So, you know, this is something that um I think   
1:08:01   
I'd like to talk say now that like there is this opportunity to combine the large   
1:08:09   
language model and act or and the reinforcement learning part. So, I like the idea of having the motivations.   
1:08:17   
So, you know, one of the things we're building on is ultimately with reinforcement learning are motivations.   
1:08:22   
So reinforcement learning is about policies but to get those policies people have to be motivated by something   
1:08:30   
you know internally and externally and then this this you know this idea that we want to have the box or the   
1:08:36   
active classroom instead of this box is key because you know we want to have   
1:08:42   
like um uh community that changes   
1:08:48   
yeah I I agree as well like that's exactly the kind of way we want to move forward like make it more realistic and   
1:08:56   
also another thing would be if the initial uh the initial kind of contributors we   
1:09:03   
have for this right if to understand how we always keep an initial state of the   
1:09:09   
repository and then we try to simulate from that point onwards so even we would   
1:09:15   
like I would like if the initial state was also modeled in this way so you   
1:09:21   
could go through maybe the existing GitHub, the existing conversation and   
1:09:26   
you know again this would be a very good use case for RNG and you could understand what are the type of   
1:09:34   
contributors now what roles do they already have how many active contributors are there how many   
1:09:40   
supporting contributors are there and then every simulation could show that you know if your opensource communities   
1:09:46   
at this stage this is where it could lead to yes and also So having different things that   
1:09:53   
could influence this. Yeah. Yeah. Sorry. So about the initial state uh I I had   
1:10:00   
this idea uh for this graph that under we are able to uh program what type of   
1:10:07   
contributors currently they are uh acting as. So we can test like what   
1:10:13   
happens under an allrounder leadership what happens under an intense   
1:10:18   
contributor. So I was thinking that uh initial state would be choosable by us   
1:10:24   
uh user uh users in the front end. Yeah. Yeah. That could also be that   
1:10:30   
would be a very good starting point if we could do it somehow to you know automatically get it from the current   
1:10:37   
state of the community using methods like passing and that would be like an add-on feature. So of course the first   
1:10:44   
step and the first testing way would be you know done by the user so the user   
1:10:49   
can simulate. So that's fine. Yes. Yes. Yeah. So uh   
1:10:54   
it's important to remember too that like the roles I know in this paper they talk about roles but that's because they've   
1:11:01   
kind of defined those in the paper. So roles are not in in typical open source communities roles aren't ascribed   
1:11:08   
necessarily. I mean sometimes they are you can be a maintainer. I can hire you as a maintainer,   
1:11:13   
but most of the time the roles are going to be like informal or they're going to be like kind of grow out of the   
1:11:19   
interactions. So a lot of times people just maintain stuff because they that's what they do   
1:11:25   
and it's like they may do other things as well and everyone might kind of share   
1:11:31   
in the workload and do other things but you know we I guess if you go back to   
1:11:36   
the reinforcement learning stuff that we were doing um last week I talked about the different types of issues and I   
1:11:43   
talked about uh Himanchu's project himu actually is also interested in this idea   
1:11:49   
of um you know uh different roles and and you know having maintainers and being   
1:11:57   
regular contributors and if you vary the number of maintainers versus the number of contributors then that changes the   
1:12:04   
dynamics of the you know they're using he's reasoning a reinforcement learning algorithm but it changes the whole   
1:12:10   
nature of the the community. So if you have more maintainers versus fewer maintainers, what happens? And that's   
1:12:17   
like important because you know and and it's not that you're ascribing that role. It's that more people take   
1:12:23   
responsibility for maintaining the software because they maybe have a motivation to do so. That maybe it needs   
1:12:30   
to be done, but also maybe they want just better software. You know, I mean, you might have a monetary uh incentive.   
1:12:38   
You might just say, I want better. I don't want this to be a messy project or you know you might have the reverse   
1:12:44   
motivation that like people don't feel like it matters so much and they end up   
1:12:50   
running into a bunch of problems because no one wants to maintain anything. So that's that's you know those are all   
1:12:56   
things that we could do here or to think about and you know I don't know if   
1:13:01   
you've if you're familiar with Hamanchu's work but I can point this is from several years ago I can point you   
1:13:08   
to the repository there. Okay. Yeah. Yeah. So uh regarding the roles part uh   
1:13:16   
I think this just represents the average. So uh in the project we would   
1:13:22   
obviously have to introduce some variance and standard deviation. So it actually mimics a real person.   
1:13:30   
So I think that would need to be tested multiple times and we'll eventually get   
1:13:35   
to a a realistic value and yeah we would need to introduce some variance. Each   
1:13:42   
contributor has a different graph but it is closer to one of the six standard   
1:13:47   
graphs. So I think that is one way we can make the real world. Okay, moving   
1:13:54   
onwards. So uh the current lambs capabilities and   
1:14:00   
limitations. So the motivation update algorithm I have talked about this   
1:14:06   
briefly but it is I believe it is based on three signals bit selection, PR merge   
1:14:13   
success and code quality score. These are what uh influence the current   
1:14:18   
motivation in the project. So I think this is a bit simplistic uh approach. We   
1:14:25   
can obviously make it better to have a bit more realistic such as ideology,   
1:14:30   
money incentive etc. No conversation space emulation. I think this has been   
1:14:36   
touched on before the before this presentation that this can't mimic a   
1:14:42   
real opensource development environment. So we have to introduce one GitHub   
1:14:48   
discussion structure. Now the current uh the current project has this one panel   
1:14:57   
and all most of the discussion occurs here. so that we we are basically jumbling   
1:15:04   
everything in one place. So I was thinking updating the front end a bit   
1:15:10   
like the current GitHub we have you have pull request and we have discussions   
1:15:15   
going on to in different pull requests like this. So that can be used instead   
1:15:22   
of this. So that won't require much work. I think we would just need to   
1:15:27   
tinker a bit with the front end and have the agents talk into the separate   
1:15:35   
things. No personality configuration. Right now the personality of an agent is   
1:15:41   
written statically. So it is basically just one string which we can modify to   
1:15:47   
change the agent's behavior. So we can just add a bit to the front end which   
1:15:52   
which allows the user to use some pre-built or a custom personality that   
1:15:59   
we can use. No role based simulation of actions. Right now they work on bidding for the   
1:16:07   
contribution part. They are chosen based on motivation and skill level. So I   
1:16:13   
think we can add a bit of autonomy there. And for the conversation part, I   
1:16:19   
think they just talk in a for loop. So that's not how a real conversation   
1:16:25   
works. We can we have to give them individual autonomy what they want to do   
1:16:30   
based on their personality and their whatever role we give them. And I've   
1:16:37   
talked about this before the current model and my proposed new model. And   
1:16:43   
here are some of the references. I found two similar projects. Now I think this   
1:16:49   
project has a very good starting point. Now I couldn't find any research paper   
1:16:55   
for emulating a slack like behavior but I am able to find some GitHub projects.   
1:17:00   
So I was thinking some implementing something like this when wherever there's an event then they start   
1:17:08   
there's some randomness and basically we use this architecture   
1:17:14   
to emulate the current whatever message we want our   
1:17:19   
agent to send whatever conversation we want them to have. So for see uh this   
1:17:25   
decides how the conversation will go. So to emulate different channels we can   
1:17:30   
have a different prompt. For example, we have I think in select we have a random   
1:17:35   
channel. So there we talk about random things. I think someone made a   
1:17:42   
Valentine's Day project. So that was pretty fun to go through. So we can have   
1:17:47   
uh different channels based on this seed variable. We can have one string   
1:17:54   
describing only serious talks, one string describing only informal talks   
1:17:59   
such as that. So through that we can al use these references to have a better   
1:18:06   
understanding for what we want to implement. So now proposed implementation I have   
1:18:12   
for uh conversation space is this. The agent   
1:18:19   
the agent will uh uh I think I should go about one more   
1:18:27   
thing here uh that is turn order. turn order in one time step. We can only have   
1:18:32   
limited actions and this will be decided through an agent through this   
1:18:38   
mathematical formula. I have found this through an paper. Now   
1:18:44   
I'm working on this part so I'll talk about this later. But whenever an agent's turn comes up, we will have   
1:18:51   
basically two different LLM calls. One will decide what action it wants to   
1:18:56   
take. Does it want to open an issue? Does it want to make make a comment?   
1:19:01   
Does it want to talk informally to the Slack channel? Then we have rag part.   
1:19:07   
Now this rag part will retrieve the context and then we will execute our action. So the division of uh labor to   
1:19:16   
two different AI calls will allow us to have a better result here. We don't dump   
1:19:23   
all the decision burden onto one. This will allow us to have a better   
1:19:29   
uh this allow us to have a better performance and emulation. Now about the rag part, I'm thinking that the current   
1:19:38   
messages and the long-term messages which are relevant will be emulated   
1:19:43   
here. There will be a Slack message memory. This will have all of the   
1:19:48   
informal messages, all of the channels, all the threads that was recently talked into the GitHub   
1:19:55   
comments. If the agent wants to go into the GitHub part, make a new issue, start   
1:20:00   
a new PR, we can have a PR or issue if it want to review some previous issue or   
1:20:08   
PR that has been published. And then the main part here is motivation events. We   
1:20:14   
will decide how the motivation will be affected through some mathematical   
1:20:19   
formula or we can also ask some uh pre-trained sentiment analysis models   
1:20:27   
and this will make up the rag retriever part. So after getting all this   
1:20:33   
information then the action will be executed and then the it will go onward to the next agent and the process will   
1:20:40   
continue and one final thing now I'm thinking the project is get the presentation is   
1:20:47   
getting a bit longer so I'll like to end it right here now this is my f my   
1:20:53   
favorite part of the project uh GitHub profile scraper and personality configuration so we have talked that uh   
1:21:01   
GitHub users tend to have very vast different personalities.   
1:21:06   
So to emulate that, why not we use the current GitHub profiles we have over the   
1:21:12   
internet. So this will obviously be anonymized. We don't want it to get   
1:21:18   
misused. So all the GitHub users will be hashed in the storage and scraping will   
1:21:26   
be rate limited like one user data per minute or something like that so that it   
1:21:32   
won't be misused. So now the uh here's my web scraper architecture I'm thinking   
1:21:38   
of. We have the web scraper algorithm. It will get the data in a JSON format   
1:21:44   
and it will sanitize it through uh various means. It will hash it so   
1:21:50   
it's not traceable and we'll use an LLM to generate a personality text.   
1:21:57   
This personality will help us emulate that person's behavior into our agent   
1:22:03   
contributor. So these are the three main things that the web scraper will tend to   
1:22:10   
analyze. First is the way of talking. How uh how politely that person talks   
1:22:17   
and then we have action taken on an average. So this will   
1:22:23   
help us identify maintainers and contributors.   
1:22:28   
We can model it through that. And finally the role part I talked about we can predicted through commit issue and   
1:22:35   
review and PR split. A person who is opening more issues is obviously focused   
1:22:40   
on issues. So he is one of these issue uh sorry engaged issue reporter or an   
1:22:48   
occasional issue reporter. So through getting these data I think I've seen   
1:22:54   
this multiple times in a GitHub uh profile readme that there's one graph   
1:23:01   
similar to uh similar to this one which shows this exam diagram which shows how   
1:23:07   
much this person is contributing as related to how much this person is   
1:23:13   
opening issues. So through that we can map out one of the personality and then we can obviously add some variance to   
1:23:20   
emulate the real part. So that will do for my presentation. Now any feedback on   
1:23:28   
the next part I've talked about. Yeah. So I think uh yeah I think this   
1:23:36   
part is you go back to that equation you showed. I wanted to see something real quick.   
1:23:41   
Yeah. Yeah. That one. So that's the the turn order formula. So that's a softmax   
1:23:46   
function that's kind of like with burst it's additive with burstiness.   
1:23:52   
Yes. Okay. So could you go through that a little bit?   
1:23:59   
Yeah. So uh I I haven't actually worked on this. I ran out of time but I like to   
1:24:06   
give the gist of it. So we have the probability of an agent uh of an agent   
1:24:14   
taking an action and this probability will be uh calculated on first of all   
1:24:20   
basis of the motivation. So the motivation is again a central part to   
1:24:25   
this project and we'll talk about the action weights we will use. So that is   
1:24:31   
will be based on the rules. Now we will have to add some variance again to make   
1:24:37   
that more uh make it more realistic. Then there's bust. So we tend to see   
1:24:45   
that the agent will do multiple functions at once. We see that in a   
1:24:53   
conversation there's multiple times multiple messages to convey one overall   
1:25:00   
message used. So this bust will try to emulate how much how frequently there   
1:25:08   
will be chunks to messages and actions and the network part the network part   
1:25:16   
will use uh the page rank. Now this page rank wasn't clear to me. So it's one   
1:25:24   
it's in this docs. I'm working on this. I'll I'll talk to about talk it about a   
1:25:30   
bit later. I think I've ran out of time. I was reading through so many papers.   
1:25:35   
Yeah. So I think the page rank algorithm is used as kind of like a way to go through   
1:25:41   
like order like rank your your members of your network and then go through the order. I mean they use it for very large   
1:25:47   
networks when they're doing search engine work but you can use on smaller networks as far as I know like   
1:25:53   
yeah so we can divide one time step into multiple contributor actions. So we can   
1:26:00   
use this to predict which uh which agent is most likely to perform and we can   
1:26:07   
obviously add some randomness to it to add more realist realness   
1:26:14   
and what any thoughts around this part web scraper to get the personality.   
1:26:21   
Yeah. Um, yeah. So, you know, I've been talking about act I've been trying to sell people an active inference and   
1:26:28   
that's this is maybe active inference or there's there's some thing here that is   
1:26:34   
where it's relevant, right? I think that'd be good. Uh, but but I like this kind of focus on thinking   
1:26:40   
about um, you know, motivations and then like how to model that better. And um   
1:26:48   
and then the part about the web scraper that's maybe a reach goal because we have   
1:26:53   
you know that when once we get the data scraped um then we have to kind of figure out   
1:26:59   
how it fits into the models. So it's not I know it seems like we should be doing that first   
1:27:04   
but given the challenges I think I outlined before   
1:27:10   
you know we maybe don't want to open that can of worms.   
1:27:16   
Okay. So, should I omit this part and replace it with um you could put it as a reach goal? You   
1:27:22   
could say this is something I'd like to do in the future. I think it's worth mentioning u or getting it out in print, but yeah, I   
1:27:28   
would I would focus on the the motivations part and then Yeah.   
1:27:33   
Yeah. Yeah. In my timeline, I think this is also placed a bit below.   
1:27:39   
Yeah. So, here. Yeah. So the GitHub file scraper is bit below in the priority   
1:27:47   
and for my stretch goals I'd like to also talk about this. So the Python packaging this will make it more   
1:27:54   
accessible but this will be obviously a very hard task. So I'm putting it a bit   
1:27:59   
below and one more thing I wanted to see through is uh core member missing an   
1:28:04   
action study. What will happen if a core member goes suddenly inactive? So how   
1:28:10   
can we see that without an active person there's a gap of knowledge there's a gap   
1:28:15   
of skill how can the community of less motivated and less experienced members   
1:28:22   
will try to recover I forgot about mentioning this part so this study also   
1:28:27   
seems relevant to the pro aim of project and yeah so I'll okay I'll move the   
1:28:35   
GitHub script a bit below so it will and it will be one of the stretch goals where I think it will be   
1:28:42   
possible. Yeah. So a lot of this stuff I I teach in my project management course is very   
1:28:48   
relevant to like the the core question there which is like how do you keep teams running and active and you know   
1:28:57   
you lose a lot sometimes when you lose people you lose institutional knowledge. So you can put it in documentation,   
1:29:04   
you can distribute it or you can keep it in everyone's heads and then you lose in   
1:29:09   
lose um expertise but you also can't avoid that sometimes and that you   
1:29:15   
know that is a thing. It's it's so it's there's a motivation there. There's some alternate artifact sometimes there are   
1:29:23   
different ways you can organize a team to prevent that or sometimes exacerbate that. So yeah, it's   
1:29:30   
this is all interesting, but um I would yeah, I would just kind of really focus   
1:29:35   
on the Yeah, now the rag part. Uh so Ria also is is thinking about rags.   
1:29:41   
So I am interested in this, but I don't know, you know, I I would like for you   
1:29:47   
guys to maybe talk about this a little bit. Um   
1:29:52   
and like what what is it that you know um what is it we can get out of this rag?   
1:29:59   
approach like what is the thing because and I mean maybe probably include um uh   
1:30:05   
Sara in that as well because like what is the thing that you're trying to actually do here? Um I'm uh I mean you   
1:30:12   
know it'd be nice to have that kind of personalization or specific kind of   
1:30:17   
training but like what can you actually do there without with with being useful?   
1:30:22   
You know what I mean? Yeah. Yeah. So uh I'd like to give the gist of it.   
1:30:27   
the uh when we call large language models they basically answer without   
1:30:35   
memory. So through rag we are basically giving them uh previous memory that this   
1:30:42   
things have occurred this are your motivations your personality and then we   
1:30:48   
are giving the AI to do the action. So rag basically emulates the memory of an   
1:30:55   
agent here. Okay. Uh well it does it do that in a   
1:31:01   
way that's the same as if I like had some non-Marovian process where I just   
1:31:07   
you know had like a list of specific things that was going on in the simulation versus like   
1:31:13   
knowledge about the world that it could draw from. I mean they're different forms of memory. It's interesting though   
1:31:20   
because the rag allows you to have some context, right? Like Yeah. But   
1:31:26   
yeah, yeah, rag gives us a bit of independence on how we want the uh LLM to process the   
1:31:35   
data. Okay. Yeah. So, okay. Yeah. Uh but yeah, I heard the most of   
1:31:42   
the I mean I heard the presentation and it's good uh just the few things he talked about but yeah I think it's uh   
1:31:49   
quite good. Did you share your timeline at all in the timeline   
1:31:56   
finalized but yeah it yeah I mean no no it's fine I think yeah   
1:32:02   
that's like the next thing you because you you proposed a lot of things and they're all good. Uh but yeah the   
1:32:09   
schedule once you finalize so make sure it's uh you know achievable as well.   
1:32:16   
Yeah. Yeah. Yeah. And maybe you can go into the three 360 3 hours. So you can go longer   
1:32:21   
than 12 weeks too if you wish. Like that's always an option if you feel like that will be better for you.   
1:32:29   
So you can do it as as you know as you're confident about.   
1:32:35   
Okay. Yeah. Uh I would have delved deeper to   
1:32:41   
my um timeline but I just wanted to say that uh I'll have basically June and   
1:32:48   
July uh for entirely free. I'm basically idle during that time. So I don't think   
1:32:56   
time will be an issue. It will be okay. Yeah. Okay. There must be university holidays. Okay.   
1:33:02   
Yeah. Okay. Yeah. That's perfectly good. Okay. So I'll as soon as I finalize this   
1:33:08   
I'll send to you for the review. Sure. Yeah sure.   
1:33:14   
You can send it to me in the doc format only. Can maybe make a group with Bradley and   
1:33:20   
okay and me and just send the doc file for if anybody has any comments.   
1:33:27   
Okay. Thanks a lot for the presentation. I took a lot of time I think.   
1:33:33   
No worries the presentation. Good presentation by all the presenters today.   
1:33:38   
Well, that's great. Thank you. Yeah, thank you Ashan and thank you um Sara for your comments. That was good.   
1:33:46   
All right. Um uh Zavia, would you like to present?   
1:33:53   
Yes, sure. Okay. Okay. So, I'm Kavia Zada, a second year undergraduate from VGTI.   
1:34:00   
So, this is a high level overview of what I'm trying to do. uh I'll first inject uh inest a slack corpus. So   
1:34:08   
basically uh we cannot uh uh ingest live data like from discord or slack because   
1:34:15   
it requires some admin permissions and using third party tools has some legal   
1:34:20   
implications which I don't want to do. So I'll use some data sets for it. uh   
1:34:26   
then I'll extract behavioral personas from the extracted uh data set so that   
1:34:32   
we are giving an identity to the agent and it is also grounded to reality.   
1:34:38   
Uh then we'll initialize the agents and the agents can post messages and we can   
1:34:45   
have evolving states like motivation, experience, knowledge base. So talking about the data set uh these are some of   
1:34:53   
the data sets I went through. This is first one is the chhatty data set uh which is basically a slack data set and   
1:35:00   
its advantage is that it's already disentangled. So uh the threads are   
1:35:05   
already disang disentangled in it as you can see the conversation ids. So you do   
1:35:11   
not have to manage different threads here because normally what happens that although they are threads but people do   
1:35:18   
communicate in some other other threads and context uh does become entangled   
1:35:24   
here. Uh second is the discord data set. So this is again discord conversation data sets. um it is not dis disentangled   
1:35:33   
and will require external tools like KD uh which again introduces dependencies   
1:35:40   
and environment issues. Uh but its advantage is that it has interoptic   
1:35:45   
distance map and uh 30 serian terms. Basically what are the most common terms   
1:35:51   
or topics that have been discussed here. Uh then third data set is the gter   
1:35:57   
common one uh which is not a slack or discord data set. It's uh from gter. So   
1:36:04   
again it's not disentangled but it has advantages that what is the purpose of each conversation and what are the   
1:36:10   
categories are already defined in it. Um and since disentanglement is a   
1:36:19   
specific requirement that we will need for persona enrichment, I think we   
1:36:24   
should move forward with the strategy data set.   
1:36:30   
Okay. So moving to persona enrichment. Um actually we have already initialized   
1:36:36   
some personas in the code code space while initializing the agents like the role description the experience the   
1:36:42   
motivation uh so what I'm trying to do is I'm trying to uh enrich them basically add   
1:36:49   
some extra personas that are required for chatting so I'll extract archetypes   
1:36:54   
like questioner lurker helper or connector then sentiments whether the   
1:37:00   
conversation is positive neutral negative uh how much has the user engaged and how   
1:37:07   
widely it engages across people. uh and this is the personal ideas   
1:37:12   
derived from this paper uh that is generative agents simula which is uh   
1:37:18   
basically Stanford paper they are simulating your daily life through agents and um in that they have   
1:37:27   
basically it's they have used the sims the game type of simulation the sims and   
1:37:34   
they are uh evolving state so basically uh each agent has some behior behavior   
1:37:40   
some memory and as and when they are interacting they are gaining some experiences and they are updating   
1:37:45   
themselves. So how are we extracting? Uh we'll first   
1:37:50   
group the text according to the users and uh then we'll extract this persona   
1:37:56   
by passing it through LMS. I know it sounds that we are using simply an LLM for this but uh there are these papers   
1:38:04   
that justify it uh that language large language models can actually infer the   
1:38:10   
big five rates although they have used GPT models and here we are using llama.   
1:38:15   
So I know that the accuracy will be a little less but the thing is the current   
1:38:22   
architecture is already computationally expensive. So running the whole um   
1:38:28   
simulation takes up a lot of time. So I want to keep it as uh minimal or as   
1:38:35   
efficient as possible. Another approach which I thought can be used is the paid one uh which is a zeros u uh zero uh   
1:38:46   
zeroot extraction frame framework. So basically the original pair extracts   
1:38:51   
triplet. So uh basically the subject uh the object and the conversation part   
1:39:00   
but u we will have to modify it to extract the habits goals and characteristics.   
1:39:06   
So paid is actually research based and uh it has shown high precision but in   
1:39:12   
our case we would have to modify it and also it uh requires external scripts and   
1:39:17   
dependencies uh which uh might not be great. So I thought of using just the   
1:39:24   
LLM for extracting the archetypes and sentiments. Um moving to this frequency and breadth   
1:39:32   
they can be directly computed using Python.   
1:39:38   
Uh moving on to stratified sampling. So basically I'm thinking we can have three types of agents. Conversation space only   
1:39:45   
agents the overlapping agents which take part both in the code space as well as in the conversation space. And third is   
1:39:52   
the code space only. Basically this is derived from real oss communities because uh normally there are some   
1:39:59   
people who just contribute on GitHub. There are people who take part in conversations only and there are people   
1:40:04   
who take part in both. Uh so basically uh this stratified sampling is needed   
1:40:12   
because there is this 991 rule in   
1:40:17   
social activities and uh this paper OSS 1991 confirms this uh what the priest   
1:40:25   
paper is talking but they have validated that although it's not 1991 exactly but   
1:40:33   
it's more or less similar like 87 five and two. So   
1:40:41   
the 90% of the users are basically the lurkers who just u come and uh chat very   
1:40:47   
limitedly and 9% of the people who actually contribute a little 1% are the   
1:40:52   
super users. So but in our s uh in our simulation if   
1:40:57   
we keep uh this kind of a ratio uh our simulation will be pretty dead because   
1:41:03   
most of the people would be lurkers and uh they would not communicate much. So in our simulation I think we should   
1:41:11   
change the ratio a bit and keep five lurkers. Um okay so how would be how would the   
1:41:19   
overlapping agents you know map to the personas and   
1:41:24   
to the original users of the data set. So this is how we can map. So   
1:41:31   
the existing code space traits can be matched with the com compatible purpose   
1:41:36   
archetypes like helper or connector. And these are some of the groundings from which I have inferred though they have   
1:41:42   
not directly mentioned it. Uh but we can infer from these papers.   
1:41:48   
Uh also there are papers like promise and hicks uh which uh show that oss   
1:41:54   
communities do require sentiments. Uh and um the Hicks paper shows that   
1:42:02   
there are uh different types of arch archetypes like helper, connector, question all helper who uh helps   
1:42:10   
continuously like helps most of the time like whenever a question is raised a person who helps connector who basically   
1:42:17   
is spread across multiple threads and uh uh provides recommendations. There's a   
1:42:23   
questioner who ask questions and of course there are workers who observe and   
1:42:30   
uh send messages very of less often.   
1:42:37   
So I'm also thinking of evolving the agent states again this is derived from the interactive similar paper where   
1:42:44   
people uh update the states using the memory and the type of interaction they   
1:42:50   
have. So we can have updating um motivations through experiences like   
1:42:58   
if a person is replying politely our motivation increases or by conversing   
1:43:03   
more we gain much more experience.   
1:43:09   
So again this cross compling is what proves that we also need conversation   
1:43:16   
space only agents because they are not background noise they actually help in the updating the code space one or the   
1:43:23   
overlapping ones because they update their motivation by conversing if they are being acknowledged if they are being   
1:43:29   
heard. Now thinking about the memory management   
1:43:35   
uh I'm thinking of an architecture where we have short-term and long-term memory   
1:43:40   
and if it is not found in these type uh in these memories then only we move to   
1:43:46   
rack because rack is actually computationally expensive making LLM calls driving   
1:43:52   
constack doing embeddings every time. So it's actually computationally expensive.   
1:43:58   
So again this architecture is derived from the life agents uh paper and also   
1:44:03   
cognitive science like how we think progressively first we look into the short-term memory then we gain some   
1:44:10   
long-term memory if not found in the short-term memory and then we search across websites or previous contexts.   
1:44:18   
So uh again other memory architecture which I have seen is the similar one   
1:44:24   
because it has short-term memory memory stream where all past events are stored. Uh it   
1:44:31   
summarizes the events into long-term memory and they also have ragged but the method they have used in the similar one   
1:44:38   
is actually expensive as mentioned in the life agents. I've also   
1:44:43   
uh take a screenshot from that paper and mentioned it here that the computation cost was $2,000 when it was done uh just   
1:44:50   
run for two game days. So again uh uh where should we apply   
1:44:58   
rag? Uh this was the question. So I was thinking uh should we also retrive how   
1:45:04   
was a similar situation handled from the data set I'm using like the real slack conversations. But if I do that then it   
1:45:11   
will be a replay and not emergence since we want to study the emerging behaviors. I think that's not the right way. So   
1:45:18   
basically what I'm doing is making uh initializing personas that that means   
1:45:23   
I'm giving it some identity but the paper like composter shows that um there   
1:45:29   
are persona drifts. So basically after a certain amount of conversation the LLM   
1:45:34   
forgets who he is. So we'll need to reinject some examples uh so that he   
1:45:40   
gains knowledge of his archetype sentiment. So we will do few short prompting for   
1:45:46   
this. And this was the paper that I used to get the architecture. And also we   
1:45:53   
just can't keep uh simple personality as I mentioned it. Uh so yeah so rack   
1:46:00   
should only be used to retract the conversation info and not from the data set. So uh rag I'm just saying that rack   
1:46:08   
should be used to get info about the current conversation that is happening in the simulation and not from the data   
1:46:14   
set. Okay. So moving on to the rag requirements. I think the vector DB   
1:46:21   
should be chromadb since the simulation is actually incrementing. So the data is   
1:46:27   
actually generating in every uh time step and so if we apply just f it   
1:46:35   
actually does re-mbbedding of the whole simulation again and again. So it's again very slow.   
1:46:42   
Next uh and chromads uh doesn't do this. So basically you can have incremental   
1:46:49   
embeddings without redoing the whole uh embeddings that has already happened.   
1:46:54   
And this is the benchmark for selecting uh the embedding model. Basically, we   
1:46:59   
can't use the amma embeddings because it takes a lot of time. As you can see the corpus speed and uh basically corpus   
1:47:07   
speed is the time that it takes for the whole uh document   
1:47:14   
to be converted into the embedding and STS score is the sim semantic similarity   
1:47:19   
score. So how much it is correct the real semantics. So I'm thinking we can   
1:47:25   
use this model as it is comparatively faster. Oh that's great.   
1:47:31   
Yeah I think you got a lot there. Thank you for presenting. Um yeah so sorry you   
1:47:37   
want sorry you wanted to say something. Yeah. Yeah. One basic question but so   
1:47:43   
you head like like the heading for your presentation was conversation space. So   
1:47:49   
uh are you is this your presentation? Is this what your proposal will be or   
1:47:54   
are you currently just telling us your plan for conversation space and you plan to add more uh late?   
1:48:03   
Yes. So I plan to add more later. So as I mentioned I haven't done a research about the metric part and the new   
1:48:11   
algorithm part. So I just mentioned that uh the heading is conversation space   
1:48:16   
because that is what we were discussing in today's session. Okay. Okay. Okay. And then um like a few   
1:48:23   
questions. So firstly you so yeah I mean when you   
1:48:28   
presented the data set again I was going to tell you this which you clarified yourself that we won't be doing rag on   
1:48:35   
the data set. So the data set has so there's two separate things you're targeting here. One is the persona   
1:48:42   
creation on the basis of the data set. So it would be similar to how Akshhat said that maybe you should you know take   
1:48:48   
real GitHub personalities and so instead of that you're proposing we do that from the Slack data set   
1:48:55   
and and and then the separate part is actual conversation space between the   
1:49:03   
current agents. Yes. Yes. So there will be three types of agents. One is just the people who   
1:49:09   
chat, people just the people who contribute and both. So the main part is   
1:49:16   
how will we connect the code space agents with the actual slack datab slack   
1:49:22   
users. So for doing that I have showed the mapping using archetype archetypes   
1:49:27   
which I've also mentioned some papers around right but I understand the archetypes   
1:49:34   
part but then how would you actually do it that was my exact question like so you get the data set and you work on   
1:49:41   
creating the personas and the personas are now created so every time you have an agent they can have some random   
1:49:47   
persona I'm assuming out of the ones that are created. No, no. Uh, actually the code space   
1:49:53   
already generates a role description, right? Right. It also creates experience, right? And   
1:50:00   
motivation. So I'm going to use that experience and motivation   
1:50:05   
to link it to the archetype. So basically there's an overlap of archetypes also   
1:50:11   
which help to map both of them. So I'm using the experience and motivation from   
1:50:17   
the code space agents to map them to the real stack users and giving them an   
1:50:22   
identity. So also I'm giving the extra   
1:50:27   
archite extra persona so that they can chat.   
1:50:33   
Okay. So you're saying that you would first ingest all the real world Slack data   
1:50:38   
then try to identify certain archetypes within that then try to identify similar   
1:50:44   
archetypes within our existing code space agents then map them the way they   
1:50:49   
best match and then you would attach a persona to it.   
1:50:56   
Yes. Basically I'm mapping them on the basis of the persona. So the final agent   
1:51:01   
that we'll create will have the personas required for conversing as well as uh for the code space that is for the   
1:51:08   
overlapping part and for code space agents we do not need these personas as   
1:51:13   
they already have so we'll keep them as it is no changes required and for conversation space only agents whatever   
1:51:20   
the archetypes we have extracted they are enough for conversing so   
1:51:25   
the point of the data set is to understand what different types of personas exist   
1:51:32   
and but then how are you connecting that to actual real world Slack data? I'm still   
1:51:38   
a bit lost. So the data set actually contains the real Slack conversation. So I'm   
1:51:45   
extracting sentiments from those conversation like how this user is   
1:51:51   
right but that's not so that data set is old right it's it's made so what about   
1:51:59   
um a new when you make when you say the yellow slack data you're saying for every simulation we'll be having that   
1:52:05   
data set only it won't change from simulation to simulation basically it the data set actually has   
1:52:13   
three oss communities. One is the python dev uh another is closure and third one   
1:52:19   
is elm. So basically we can we will have to use these data sets only   
1:52:25   
because uh if we try to inest word data there are third party tools but there   
1:52:31   
are some legal implications that licensing issues. Yeah. Okay. Okay. Yeah. Okay. Just wanted to confirm. So   
1:52:37   
okay. So then maybe it'll be one of these three and then so then why you   
1:52:43   
trying to make personas and not so it's different each simulation is that why   
1:52:49   
instead of just taking the users as they are from the data set   
1:52:55   
basically I'm extracting personas to basically this is what research papers   
1:53:01   
have done like this the generator similar one the camel one where came T   
1:53:06   
camel One also is actually a simulation of the how people respond on social   
1:53:12   
media, how they react to posts. Uh so there also they have done the persona   
1:53:19   
extraction part or actually they have most of them have actually created the persona themselves like we have done in   
1:53:25   
the port space like we gave the agent an identity. So basically I'm trying to give the agent an identity of who he is.   
1:53:32   
So we can have individuals or individual identities of Egyptians.   
1:53:38   
Okay. Okay. Yeah. Okay.   
1:53:44   
So yeah, I think you're burying the lead with your title project title then.   
1:53:50   
Yeah. Yeah. Sorry for the title because this is actually   
1:53:57   
Yeah. No, no, it's okay. Yeah, I think that's out.   
1:54:04   
Yeah, I think you've hit a lot of points here. And then, you know, you're also talking about rags. So, I would get together. I mean, you know, I I know   
1:54:10   
that you're all competing for G-Soft, but I would get together and talk about how to do rags and how this would be   
1:54:18   
best done because I think it's like, you know, we don't want to have like four different rags floating around and   
1:54:25   
and people saying this is the way it should be done because it's this is a nice feature to   
1:54:30   
have. you know, you can train a model, get some context, and then I think Zavia   
1:54:36   
mentioned that, you know, you have this, like we talked about this before, you have this difference between the   
1:54:42   
previous experience within the simulation and then there's this context that you can draw from and you can use   
1:54:48   
that to inform the model. So if I for well like the one that we the rag that   
1:54:54   
we built for the cyberneticists that I keep talking about you know if we write a paper on if we have a reading   
1:55:01   
group we're thinking about uh what uh say uh Norbert Weiner had to say about   
1:55:08   
something and we read you know we've read one book we maybe read a couple other papers but if we train a rag on   
1:55:15   
his work we can then go back and say you know what you know what would Norbert Weiner say about this concept and then   
1:55:23   
it would give us some output and we could look at that and say okay well this is what we've kind of come up with in our reading group and it might add   
1:55:30   
something um it gives context and we can use that as another piece of   
1:55:36   
information to sort of you know so it's like history but it's also like history   
1:55:42   
from a wider lens than like that one experience of the simulation or the runs that you give it that it has experience   
1:55:49   
with. So I think that's but you know we have to kind of figure out how to implement that correctly and how that   
1:55:55   
would best serve the model. Actually the current architecture is   
1:56:02   
already very heavy. So yeah I know that's a bit of a problem because   
1:56:07   
running the whole simulation takes a lot of time and laptop just start spinning   
1:56:13   
and producing noise. Yeah, it is. It is a problem. And this I think is something important to remember   
1:56:18   
is that like um we have to make sure that it's memory efficient, right? We   
1:56:24   
don't want to add everything. I don't want to add the kitchen sink and then have the whole thing not be able to   
1:56:30   
run because we have too much in there. Yes. So, exact uh that is why I was   
1:56:36   
looking at the architecture from the research papers but actually those are very heavy. So we cannot actually   
1:56:43   
implement them in our simulation. So that is what we will have to make some   
1:56:48   
tweaks and remove some heavy parts from it. Yeah. Well, that's that's again like   
1:56:53   
that's uh strategizing, right? Okay.   
1:56:59   
All right. So I think everyone did a good job here this this week. Uh I wanted to give people a chance to go   
1:57:04   
through their projects. So I think everyone did well. Um, and you know, uh,   
1:57:10   
hopefully we can get our, so our project deadline is next Tuesday, 31st.   
1:57:16   
I say this because it's very important that you meet the deadline exactly. Figure out what time they want. Like I   
1:57:22   
think it's I can't I don't think it's anywhere on Earth at the end of the day. I think it's like a specific time UTC.   
1:57:29   
So make sure you have that right. And then um again you know your your project   
1:57:35   
proposal is the outline of what you want to do. Make that very clear but then   
1:57:40   
also you have the schedule go through week by week and say this is what I'm going to do. But also if we have reach   
1:57:47   
goals, if we have ways that we can get around bottlenecks, point those out because sometimes we hit things that we   
1:57:54   
can't solve right away and we need to kind of we don't want to waste time sitting on something for a week when we   
1:58:00   
could be doing something else and then come back to that later. So prioritization is also important.   
1:58:08   
Okay. Um so I don't know, Morgan, I know you've been waiting patiently.   
1:58:14   
Uh I hope you've enjoyed the presentations and so why don't you give an update on what you've been up to?   
1:58:19   
Yeah, I I certainly wasn't uh waiting pat or like uh   
1:58:26   
I just turned my camera on. That's all. Yeah. Um uh yeah, thanks everyone for your   
1:58:33   
presentations. Um I am trying to understand this area myself. It's not my   
1:58:40   
um it's not my thing. Um but uh but I find these simulations really   
1:58:47   
interesting and u as as I presented last   
1:58:52   
week uh I'm trying to use some some large scale LLM simulations for for a   
1:59:01   
variety of purposes and you know I'm just kind of using using sustain hub and   
1:59:07   
um uh the the open source sustainability project is some uh   
1:59:16   
drawing inspiration from it. Yeah. Um so just uh not sure what to cover this week   
1:59:24   
in particular. Um we did uh we we talked about uh focused ultrasound   
1:59:31   
um at the tower. We had the chief scientist of a tune neuro   
1:59:37   
speaking. Um, so this is a focused ultrasound company that uses the the   
1:59:45   
we've got some small um thin parts of your skull right here that   
1:59:52   
focus ultrasounds can use to um uh they call them temporal windows to uh allow   
2:00:01   
for neurom modulation of of brain areas. his his particular group is doing some   
2:00:07   
really interesting uh work with UCSF not only on depression and chronic pain   
2:00:15   
which of course are are typical targets because of the large   
2:00:20   
size of of need um uh but my research   
2:00:26   
area is in psychosis and in particular schizophrenia and he's   
2:00:33   
together again with a someone in group UCSF doing really interesting work in   
2:00:39   
terms of symptom symptom modulation in schizophrenia with focused ultrasound   
2:00:47   
which is fascinating. This week was the diffusion in Python   
2:00:55   
workshop. So this is a a week of online discussion around uh deep they I I heard   
2:01:05   
people say deep. Um, uh, yeah. Do you   
2:01:11   
have thoughts on this, Bradley, about how to how to say,   
2:01:16   
you know, ni py? Uh, not di or no, I mean, dpi sounds   
2:01:24   
like you're trying to unpython it, which maybe is better. I don't know. Well, so like like it's confusing,   
2:01:31   
right? I mean, uh, yeah, this is this is the problem.   
2:01:37   
If you if you don't work with uh people who are, you know, if you're if you're   
2:01:42   
always just using chat to talk to people in other countries, um you don't hear them saying it out loud. Uh I think I   
2:01:49   
think I feel like that the the Python people want to say me because of um   
2:01:56   
Montipython and the Holy Grail. Oh yeah. Is that why they say it like that?   
2:02:02   
Why the pie or what do they what do you mean? Well, because they were saying DPI and I'm like it's DI like   
2:02:10   
Oh, yeah. Oh, yeah. I don't know. Yeah. Well, it's like NIPI is the it's   
2:02:18   
the neur imaging in Python is NIPI. Yeah. NIPI.org.   
2:02:24   
Um, but I think I think the NIPI people actually like if I met them in real   
2:02:29   
life, I think they would say Nepi. Yeah. Yeah.   
2:02:35   
Um but the the the interesting thing about it I mean it was it was you know   
2:02:42   
um they used the workshop as an opportunity to kind of talk about their development release.   
2:02:49   
So you get you get to see kind of new features and and and things like that.   
2:02:55   
The important thing for what I hope would be a a weekly segment is uh the   
2:03:03   
uh coverage of AI in medical imaging. Okay.   
2:03:09   
And uh you know this is a particularly   
2:03:14   
um this is a I think an interesting topic   
2:03:20   
also because if if if you remember although this seems like this was can   
2:03:25   
this already be like 10 plus years eight years ago. Um Jeff Jeff hit said um AI   
2:03:33   
is going to replace all of radiologists you know like like   
2:03:39   
We won't need radiologists anymore because of AI. Am I right, Bradley? I mean, was that   
2:03:45   
like Yeah, that was the idea that the radiologist had be replaced.   
2:03:50   
But wasn't that like 2015? Yeah, it was a long time ago. Like a crazy long time ago.   
2:04:00   
So, if you check your hospitals, your your your neuroraiologists are fine.   
2:04:05   
Yes. Yes. They're all there still. Well, maybe not all.   
2:04:11   
No, they're still there. It's still still, you know, uh still a functional discipline. Um still being taught in   
2:04:19   
medical schools. Um but it's interesting, right? Because   
2:04:25   
at the same time, um we are seeing a lot of you know   
2:04:32   
there's there's a lot of progress in models. There's a lot of progress in segmentation.   
2:04:37   
um segment anything is is is a really useful tool and and you know I follow   
2:04:44   
some groups that that work with it. Um   
2:04:50   
uh so people were covering you know people were talking about um how how it's used   
2:04:59   
in both you know acquisition from the MRI. So, can you can you design a sequence   
2:05:06   
that kind of like runs faster? Um, so that you don't have to have the person   
2:05:12   
in the scanner for as as long um or again in some way make the the scan   
2:05:20   
itself more amendable to kind of deep learning approach.   
2:05:25   
And um but I I gotta say, you know, I think it   
2:05:31   
was really um somewhat somewhat lacking as a session. Um and   
2:05:38   
and I I think we should talk about why. Um this will be part of a of a um   
2:05:48   
like an opinion piece that they're going to put out after. Um but I did so so my   
2:05:57   
con I didn't speak until the end where I talked about talked about um agentic   
2:06:04   
coding um or like a AI assisted coding and so I   
2:06:11   
did I did submit my um diffusion microructural imaging in Python project   
2:06:19   
which is like my refactor of uh of an old project that was you know numpy   
2:06:27   
based um and and that I've refactored with Jax and that I've been using um not   
2:06:37   
only coding agents to uh to parallelize the code um but also   
2:06:45   
to extend it in in new ways that in particular like I like I presented last   
2:06:51   
We use this Jax ecosystem and specifically something I call the the   
2:06:56   
Ker stack which is just a a a set of libraries that are are   
2:07:04   
designed for neural differential equations in in machine learning. So   
2:07:10   
pins and and related approaches. um uh did so   
2:07:17   
I would just say for those interested in those kinds of approaches um uh the talk   
2:07:24   
that I I dropped in um the data sigh channel   
2:07:30   
um it it doesn't come with a um a thumbnail but is is the um American   
2:07:40   
Mathematical Society talk uh And unfortunately to make it even   
2:07:46   
worse, he's the second speaker. So So you first have to go through a   
2:07:52   
conversation about um I mean an interesting one about biomimetic robots   
2:07:57   
um swimming robots. Um but um George   
2:08:06   
Takanas, I'm not even coming close to getting his name right. Yeah. But um he's he's the   
2:08:13   
head of crunch lab at Brown is been a pioneer in pins um has you know is he or   
2:08:22   
his students like have developed most of the pietorch tools that people use for these these   
2:08:29   
approaches and um and he has the f the first time   
2:08:36   
where I've seen somebody like him uh uh actually talking about agentic AI for   
2:08:46   
uh um computational science, right? And and I think I think that's really   
2:08:52   
interesting that he's um I mean in addition to talking about   
2:08:59   
what what he's calling second generation pins and and um second order   
2:09:06   
optimization for for them and and you know some some dramatic results in terms   
2:09:13   
of improvement um which which I have got to follow up on. Um but he's also taking a very um if   
2:09:24   
you remember Bradley the the gas town simulation. Oh yeah.   
2:09:29   
Um yeah. So so this is like like you know again it kind of reminds me of   
2:09:36   
sustain hub in terms of um or you know the the open source   
2:09:42   
sustainability like you've got a community of developers that you're that you're using. I mean, um, a community of   
2:09:50   
coding agents and and that's what Gas Town is all about. Um, and so yeah, he   
2:10:00   
has he he lays out this this kind of Gas Town approach to   
2:10:06   
uh formulating a computational model. So   
2:10:11   
it's it's he's not trying to do an AI scientist, but he is but he does have   
2:10:16   
like like certain certain agents that are the actual coders, certain agents   
2:10:21   
that are kind of like the designers. Um I mean it it's funny because it looks   
2:10:27   
like it kind of looks like an academic lab. Yeah. where he's got like like the PI   
2:10:34   
and and maybe some some other senior people are are coming up with ideas and   
2:10:40   
then there's like post talks that   
2:10:46   
sorry I'm not sure what that says about his particular vision. Yeah. Oh well,   
2:10:53   
but I'm trying not to read too much into it, but but I think it's it is um   
2:11:00   
it's I'm I'm interested in that particular approach. Uh   
2:11:06   
uh well, h how to make things more autonomous. Yeah.   
2:11:11   
And I mean and you know, again, sorry, I don't know if you can hear this really   
2:11:17   
loud siren. Um, sorry. I'm in downtown San Francisco. Yeah,   
2:11:24   
we get the full Yeah. sounds in the city. Um, but you   
2:11:31   
know, again, like like what I'm trying to do is as I presented at the   
2:11:36   
conference or the workshop, um, you know, I'm I'm trying to see this in   
2:11:42   
action and see, you know, what what it's capable of doing. you know, if if if   
2:11:49   
Yeah. So, um and and you know, making the the other   
2:11:56   
video that I posted was and Andrew uh Andre Karpathy talking about his own,   
2:12:03   
you know, auto research project, which is is, you know, again, it's it's a   
2:12:09   
super simple idea um that is is something that you know you   
2:12:18   
you it would be your first approach to doing the kind of thing that that um   
2:12:25   
that Crunch Lab is doing in terms of of uh giving a set giving an agent a kind   
2:12:33   
of task to iterate on and not not need the human to be in the loop. So Carpathy   
2:12:40   
talks a lot about trying to remove the human. Um it's not the not that um that   
2:12:47   
the human's unimportant but that you know the humans the the bottleneck in a   
2:12:53   
lot of the the work if if you know tokens are free and you know to some   
2:12:59   
degree compute is free I know those are not true but anyway I just I but I think   
2:13:06   
it's really interesting you know I think it's really interesting to hear in talking about it   
2:13:12   
Um, I've got uh, yeah, some some I mean   
2:13:18   
I I've I've trying to make everything um, runnable here just on a DGX Spark,   
2:13:25   
but it allows us to to go um to to use cloud compute if things are   
2:13:33   
uh, if it seems worth it, but really trying to get as much out   
2:13:38   
from the the GPU as possible and and uh, Like Bradley said, you know, I'm trying   
2:13:44   
to use things like the organoid benchmark as   
2:13:49   
as something to iterate on. So Karpathy talks a lot about in his auto research   
2:13:55   
is that you know this is really good if you've got good metrics, right? So if   
2:14:00   
the agent can be trying new things as long as there's good you know there's real tests to see if these are if this   
2:14:07   
is an improvement in the right direction. Um so I'm I'm you know in addition to   
2:14:15   
the organoid benchmark I'm using some some diffusion benchmarks to to   
2:14:20   
microructural MRI benchmarks and um and most recently is the um real time fMRI   
2:14:28   
benchmark that uh from the lion's eye project. Um   
2:14:35   
yeah, so if if you're uh if anybody's interested, please do check out my   
2:14:41   
GitHub. Um I've been dropping Oh well, so the the new repos that that again   
2:14:49   
Claude has generated. Um uh all of the training materials in   
2:14:56   
terms of the kind of educational materials for learning about these projects is in the spinning up in uh I   
2:15:04   
say ALF um uh it's supposed to be active inference framework you know but u uh I   
2:15:12   
think ALF sounds better and uh one of the new repos you'll see there is EVO   
2:15:20   
embodied which is um my attempt to rewrite Josh   
2:15:25   
Bombgard's evolutionary com robotics course uh with with a new software stack   
2:15:32   
right that again is Jaxbased is is Mujoko   
2:15:38   
um a rewrite of Mujoko that's Jax and uh   
2:15:46   
but but still keeps a lot of Bongard's um kind of   
2:15:53   
having the body itself be part of the evolution you know so it's it's not just   
2:16:01   
um uh evol evolutionary computation it's it's an embodiment that is also being um   
2:16:09   
iterated and um and selected yeah um I think that's that's it I've got one   
2:16:19   
um coming to talk about uh well you know   
2:16:24   
something something trying to go um I don't know if this repo is public   
2:16:31   
or private currently but but I'm I'm trying to do um   
2:16:38   
you know trying to think about larger simulations that um that kind of drop the LLM.   
2:16:45   
Yeah. Um and in terms of um   
2:16:51   
very large simulations and potentially ones that you'd actually be interested   
2:16:57   
in using quantum computing, but these these are really just large uh   
2:17:04   
icing models and spinny glass models. Okay. Um but but as as you see I'm   
2:17:12   
trying to connect the um um it's it's   
2:17:18   
interesting that the math behind these is actually similar for um large scale   
2:17:24   
social social interaction models. So if you're interested in learning about that   
2:17:32   
um again check the material support I'll make the material uh public but it is um   
2:17:41   
uh you can see this in yeah   
2:17:46   
disordered magnet systems. Yeah. And you know it's it's it's an   
2:17:51   
interesting intersection of actually like material science modeling and um   
2:17:58   
large scale multi- multi- aent simulations. Yeah. Yeah. Obviously you lose a lot of you   
2:18:05   
know these are you're going to lose a lot of the theory of mind kind of Oh yeah.   
2:18:11   
Well this is kind of like mid 90s Santa Fe Institute where they were like put this is this is Yeah. But but actually   
2:18:18   
this is like current um uh   
2:18:24   
oh yeah this is current current work. Um so you   
2:18:29   
know um Aram Nabi from from   
2:18:36   
um Carnegie Melon who just spoke at Santa Fe Institute. He also spoke at at   
2:18:41   
foresight and was talking about trying to do these kinds of simulations. The   
2:18:48   
these are kind of simulations that you can also prove um uh analytic you know   
2:18:54   
you can prove some things about analytically. Yeah. Right. Um which is the kind of stuff   
2:19:01   
that he's done in terms of finding lower bounds to to certain um certain   
2:19:06   
properties of the system. Um uh but again just would be it's an interesting   
2:19:15   
connection to um to these kind of multi- aent system models.   
2:19:20   
Yeah. I mean now that we have much better compute than they had when they   
2:19:26   
started doing spin glass models. I mean, you know, they're largely theoretical when they introduced them like the we we   
2:19:32   
talked about this in deep where like it was a product of kind of thinking about   
2:19:38   
um you know magnetic spins and then putting that into a network and then or   
2:19:44   
an agent based kind of uh paradigm and then people started using it for different types of biological and social   
2:19:50   
systems and making that analogy but then getting the compute right and and   
2:19:55   
getting insights out of it is a different issue. So that's why people are working on it, I guess, still. And   
2:20:01   
yeah, I think it's great. Yeah, it it's it's um so please check   
2:20:08   
out the the the um the educational material because it's like I'm really um   
2:20:15   
trying to find the the right kind of um   
2:20:20   
um scaffolding for this in terms of how to how to approach it. But this will be   
2:20:27   
something where um you know again if if quantum compute becomes available I I'm   
2:20:34   
going to try and submit a grant for just getting some some compute access   
2:20:39   
right for you know limited compute access via NASA um oh okay   
2:20:44   
for for some some quantum simulations. Oh wow. Um and yeah but I I think it's it's   
2:20:53   
still something Yeah, that you can connect to social simulations.   
2:21:00   
Yeah. Yeah. Look, sounds good. Sounds good. Um   
2:21:05   
glad to hear you're doing um all the things apparently.   
2:21:11   
Yeah. All right. Uh well, thanks for attending. Thanks to everyone who presented today and   
2:21:18   
uh let's keep uh working on our applications. And we have a lot of things in the um and I didn't even talk   
2:21:25   
about it, but we have a lot of things in the um GitHub repository that are sort   
2:21:31   
of I'm not really sure of what needs to be pushed and where we're pushing them. I think we're pushing everything to dev   
2:21:38   
now, but I think and I think that's good for like you know the the application   
2:21:43   
periods. Yeah. Uh application period of GSC. Um but   
2:21:48   
there's still some things that are open. So, I want to know I I'd like to know more about like what the status is, what   
2:21:54   
what can be pushed uh and and so forth. But I'm glad everyone's been at least,   
2:22:00   
you know, engaging and uh getting things out there and and really in being   
2:22:06   
interested in that repository. So, thank you. Uh, all right. See you   
2:22:13   
next week.
