## Meeting Recording

[YouTube link](https://www.youtube.com/watch?v=XTVToHyOVVI)

## Mastodon thread

[link](https://neuromatch.social/@OREL/113058118459204208)

## NOTES
Shubham Soni: RL tools in repo (GSoC).

* MESA (RL project). Rl library by this weekend, next Saturdy review.

* RL or no RL (randomness). Policy and rewards are effected.


Lukas -- started working on coding part of project, Jupyter notebook (.ipynb) file should be on Github soon.

* BlastP for 25 proteins, finished primary data collection (JSON files).

* Studentship: 1) develop Jupyter notebook and JSON format, Blast; 2) what to do with it, post video presentation
to YouTube, Github.


Comparative Genomics and Functional Study of Lipid Metabolic Genes in C. elegans.

1) assigned to a metabolic pathway.

2) suggest that C. elegans could be a lipid metabolic model.


Orthologous: from same common ancestor, homologous with speciation.

Paralogous: separated due to a gene duplication event.


RNAi: interference gene silencing. cheaper than CRISPR, TALENs, available primers.

* two ways to manipulate genes: 1) knockout (remove gene), 2) knockdown (decrease gene expression).

* fatty acids, lipids, homeostasis.

* obtained genes from KEGG database, WormBase, human orthologs. 

* Ensembl --> BioMart. ClueGo --> functional annotations. Huge lipid families IDed.


How many genes? Have they been manipulated in pathways?

* some could not be mapped to a particular pathway (no specific biological function).

* 471 genes --> 16 lipid metabolic pathways.

* conflicting results from KEGG, annotations.


Venny --> program for making Venn diagrams. Substrate from another metabolic pathway.

* conservation genomics. 581 orthologs in C. elegans (Human). 70% are conserved across mouse, Drosophila, C. elegans, and Humans.

* Table 3 -- summary of phenotypes --> lipid droplet size as assay (mutations).

* sams-1 --> increased lipid droplet size (with RNAi) --> growth rate is affected.

* 471 --> lipid genes --> 4% affect phenotypes.


Jesse update: JoPro updates, mental health working group, admin, research coordinator level.

* SUNY Albany is developing a new mentorship program.

* opportunities across colleges -- Data Science; Society, Ethics, and Tech. No longer need a generic posting.

* more detailed -- Complex Systems lab. dBV --> book review on BVs. Is a great overview.

* GSoC -- nice set of contributions. Convos with Avery -- Meta-brains; dBVs; CGSs.

* simulation-based work (Representational Brains and Phenotypes). 


Paola's model cards. Granting organization, Future of Life institute.

* experience of working with a grant office. Offer to do here: JoPro --> modeled after the MIT Media Lab.

* post, publication, groups preview. Responsive Environments group.


Make a front page for the lab: PR aspect to works.

* "Centering AI in Medicine" -- SUNY Downstate, Neuromodulation.

* SORA did not solve world models -- video generation as world models.

* NetPyNe: lead developer extension of NEURON, MetaCell.

* text-based game. Hand-coded, hierarchical strategy.


World Model -- model the world -- easy exchange.

* between training and world. Better memory, better plans for the future. Papers from the RfP on world models.

* strining actions together, concepts as sequences.

* Levin -- task planning.

## TRANSCRIPT    
0:03     
hello good morning morning so how are you this     
0:10     
morning just Bree coffee oh     
0:16     
yeah so yeah we didn't have our Friday meeting yesterday at a conflict and um     
0:24     
we had Diva on this week which was good um talking a lot about     
0:30     
graph neural network stuff and talking about you know connectivity Mah presented um on a paper     
0:39     
that he was interested in so we had a lot of discussions about that     
0:45     
so right so as you know gck is completed uh the normal time period for gso is     
0:53     
completed and Sara bostal was uh the student in the Orel lab uh we have two     
1:00     
students in Evo worm who aren't finished with their projects they got a 3-week extension so we'll be talking about     
1:07     
their projects later uh but then we also had chuom Sony who was working     
1:13     
on uh like a reinforcement learning model of Open Source sustainability that wasn't funded by gach that wasn't     
1:21     
accepted by gck but he never the less worked on it and pushed the materials to     
1:27     
our reu so there's s Ro     
1:33     
hello Lucas hello Hi how are you fine I want you guys all right this is actually     
1:41     
Sara's last blog post this so this is uh her gso 24 report um from Concepts to     
1:50     
completion so this is really kind of going over the final framework LL m o c     
1:57     
uh that's large language models for Source sustainability it's actually based on     
2:03     
the Llama open source uh large language models uh talking about how those were     
2:10     
used to generate agents and using agent-based modeling to generate contributors that um address tasks that     
2:18     
were also addressed or were also generated through a larger language model so this kind of goes through a lot     
2:27     
of the work that she did kind of from this diagram that she presented in early meetings here uh to some of the     
2:34     
implementation components so like the environment environment variables agents     
2:41     
agent variables which were the internal States um then there's the framework capabilities so she integrated Auto C     
2:49     
Grover into the uh framework which is something that generates uh code so part     
2:56     
of it was to generate tasks but it had to also generate code and so the code     
3:02     
was in response to the issues that were created so this was just a lot of generative um kind of basically     
3:09     
generating an open source Community maybe a small open source community and then uh seeing how well it worked given     
3:17     
certain conditions so that's why she was integrating auto code Rover integrating     
3:24     
this automated pull request life cycle with a contributor agent and a maintainer agent so that contributor     
3:30     
would generate some solution to an issue the maintainer would check the code to     
3:35     
make sure it was consistent with the issue and uh then we had these multi-m     
3:42     
decision multi-agent decision-making algorithms so there were two algorithms that kind of governed how the     
3:48     
contributors um operated one was the authoritarian algorithm or the     
3:53     
benevolent dictator model where the maintainer manages allgates tasks and     
3:59     
then contributors are rated and assigned based on what the maintainer says and     
4:04     
the decentralized algorithm which is the meritocratic model uh had distributed decision-making amongst contributors not     
4:12     
maintainers and the contributors bid on tasks based on their suitability and experience so once the agent uh that     
4:20     
represented contributors had a profile they could then bid on tasks they had a     
4:25     
certain amount of experience and then you know that was done the maintainer of     
4:30     
course is also automated and uh in the case of the authoritarian regime would     
4:37     
actually do the allocation of tests so that would impact how sustainable or you     
4:43     
know what the open source Community would look like uh then there are metrics and     
4:48     
Trends visualization so she had a number of things here uh you know she had this     
4:55     
popup where you when you run the simulation you set a number of parameters of the number of contributors number of     
5:01     
maintainers and number of issues those are the the initial conditions of the     
5:07     
simulation then you set the decision-making algorithm uh and you select an issues     
5:14     
path so you can select certain issues you can hand code the issues if you'd like or you can generate them um and     
5:21     
then you know put them in this file that you can import import into the simulation and then this so this is for     
5:28     
the calculator project that S created for this uh this as a demo of this and     
5:35     
then starting the simulation so runs a simulation and you get these results     
5:40     
based on the initial uh inputs there are also some metrics that are used in the     
5:48     
simulation we can plot those out so all of this is uh present in our open source     
5:54     
meetings uh from this year so we had open source meetings from um     
6:00     
from May to this month so uh we had our last meeting uh last week we didn't     
6:06     
weren't able to have one this week so uh that's thank you to everyone who participated in our open source meetings     
6:14     
um they were you know weekly Affairs that were very I think very useful for students working in open source projects     
6:21     
people like Morgan who have experience in open source and Jesse of course working on his uh project manager M uh     
6:31     
you know issues and then myself who was leading the whole thing and I talked     
6:36     
about a number of topics in open source so I think that was very useful this fall we're going to do     
6:43     
something related to modeling and data science at that time so it's going to be a different thing so I feel like uh you     
6:51     
know that was a successful season of uh open source and um looking forward to doing     
6:57     
it next year the other thing I wanted to highlight was this was shom shon's uh uh     
7:05     
repository so this is uh shoom and been contributing a lot to the open source     
7:12     
sustainability or a lot to the gck uh repository in this directory open source     
7:18     
sustainability using our so if you go up to the gck repository we have uh this is     
7:25     
of course Sara's work here and this is shubham's work be going into this directory you'll see that he has the P     
7:33     
file set up and the read me which actually doesn't have anything in right now but I guess he's going to add those     
7:40     
in a little bit later um so this is uh you know this is so he's issued a number     
7:46     
of poll requests this week which is why I wanted to highlight in the meeting um     
7:52     
yeah these these uh so there were some updated files here um and so yeah this     
7:59     
is a good work as well I think he still needs to do a little bit more but I'm not sure it's fine there he is um but     
8:06     
yeah congratulations to shom for also doing a great job on um working on the     
8:12     
reinforcement learning model that he was working on the site so it looks like shom's here and so is     
8:20     
Jesse so shom     
8:26     
hello hey everyone hi AUD yeah you're audible     
8:32     
yeah uh just give me a second I have some network issues here um but uh uh     
8:39     
regarding the updates I don't have any visual updates I have pushed a lot of code into the repository um uh so that     
8:47     
is mostly the previous work and I have added some RL logic into it so what I     
8:52     
was trying earlier was uh I will um you know use pettings to create a custom     
8:58     
environment but uh um doing implementing that would require a lot of you know uh     
9:03     
it would require a lot of maintaining variables uh that was not really worth it but uh so what I did was I reached     
9:10     
out to the developers at Misa and uh they have actually completed the     
9:15     
reinforcement learning project that they were supposed to do last year so um I reached out to them and they     
9:22     
have done some work in the in implementing reinforcement learning into some Misa models of Their Own using uh R     
9:31     
RL Library there's another RL reinforcement learning library called RL Library so I've been trying to implement     
9:39     
uh the reinforcement learning part with the help of uh whatever work they have done using it as a reference and uh     
9:45     
probably by this weekend or uh at most by next Saturday I'll be done with the     
9:51     
entire uh thing and then I can have a I I can you know display two different models one with reinforcement learning     
9:58     
and one without so we can compare the results between both of them by next week mostly all     
10:04     
right and so yeah you were talking about that in the open source meeting so the nonl model is just doing things at     
10:11     
random right yeah non model is doing things at random and uh when we     
10:17     
Implement RL it will you know have a reward system so it will take its actions based on the policy and the     
10:24     
rewards right that sounds good and     
10:30     
maybe at most a week and then yeah yeah a week it' be fine     
10:36     
um so we had talked about also Sara building a lot of this these automation     
10:42     
tools have you looked at any of those for this project or uh not yet I was just hoping I'll     
10:49     
finish this RL part first and if anything uh if you guys have any suggestions for the auto so we can do     
10:56     
that as well well that sounds good thank you thank you also I have pushed the entire     
11:04     
code whatever the updates are there until now so if you guys want toie it once     
11:09     
Che yeah yeah I saw that yeah there's there you made a number of full requests     
11:14     
this last week so good yeah thank you thank you so much yeah thank     
11:22     
you so I don't know if Jesse or Lucas wanted to give an update um     
11:29     
does Lucas want to give an update yeah I can give an update so um     
11:35     
yeah basically what I did was that I uh started working on the coding part of     
11:42     
the Jupiter uh notebook I uh developed a pipeline and I started doing um I     
11:50     
started running the blast searches using the pipeline so right as of right now     
11:56     
I've uh ran all of the blast searches uh which is like a blast PE uh protein     
12:03     
blast and uh I've run it for uh around     
12:09     
25 proteins now so I I use the ncbi accession IDS from the paper and also s     
12:19     
uh around five more proteins that are uh involved in Seance     
12:24     
developmental uh like Seance development and stuff like that so um what I did as     
12:30     
of now is that I uh finished the primary data collection so     
12:36     
right now if you look at uh the GitHub page I have the Jupiter notebook there     
12:42     
and all of the uh Json files that we needed uh for primary data um so yeah um     
12:51     
and I'm also looking to uh use the primary data to so like basically the     
12:58     
open form studentship had two goals the first goal was to uh develop the Jupiter     
13:05     
notebook and Pipeline and collect the data collect the primary data and the second goal was uh to uh use the primary     
13:13     
data to uh achieve a secondary goal which um we're still thinking about what     
13:20     
we can do with the primary data so um yeah so as of now this primary goal is     
13:27     
achieved however uh we're still thinking about what we have to do with this uh with these Json files and what we can do     
13:35     
with the blast search results so that's my update on the open warm project all     
13:40     
right project yeah we talked and I know we've been talking about what to do with     
13:46     
them and I'm like canot uh kg about that but I I'm really trying to figure out     
13:52     
what to do I mean I'm I'm still kind of working that through in my head how we want to implement that but so I guess     
13:59     
the next step would be to like to do a presentation on this um on this project     
14:07     
like just kind of going through the notebook and the Json files and then I know that um that porg wanted to see you     
14:15     
know um what had been done and everything and so we'll try to schedule that in where you can present on that     
14:22     
and I'd like to see it first just by myself so i' give you feedback and then I can either share the video with or we     
14:29     
can do another presentation porg but I wanted to get like a good you know     
14:34     
presentation you know I don't know if you want to do demo or slides or what but you know to sort of summarize     
14:41     
everything and sort of lay it out there for people you know for what what's there and I think that's valuable     
14:48     
because you know it's kind of hard to you know hard to say first of all it's     
14:54     
hard to say what we can use it for if we don't know exactly all the you know functionality of tools and so forth but     
15:01     
also because it does summarize everything that was done and you know with you know if you look at the GitHub     
15:07     
repo you might not you know actually get what's going on um so yeah I would like     
15:13     
to see that oh yeah yeah what what I can do like uh I was thinking about this     
15:20     
actually um what I was initially thinking was to uh like when the project     
15:25     
is all done I can uh like just record a video just uh by myself or with you     
15:34     
together to go over everything that I've done and then this uh I can also present     
15:40     
it in a meeting too but like um we can save this video we can either uh post it     
15:46     
on the YouTube channel and post it on the slack Channel too for others to access it I can also put it on the     
15:53     
GitHub page as well just in case people want to see how it works and stuff like that but yeah I can do both I can uh uh     
16:01     
record a video to go over everything and also I can present uh what I've done     
16:06     
live to just in case uh they wanted to see how it works and stuff like that yeah that would be good um yeah so yeah     
16:14     
let me know um you could just kind do a video on your own and you could send it to me and look it over and see you know     
16:22     
make sure it's got everything in add so yeah or you know we could do this kind     
16:27     
of we could do this is part of D.A wor even or or this meeting um not just let     
16:33     
me know we'll do in the next few weeks I don't want to um make you do it like     
16:39     
right now I mean you know I'm sure you're starting your semester so yeah     
16:45     
this this is good um and I was looking over the the GitHub repository and of     
16:50     
course yeah I I don't know if are the uh Jupiter notebooks up there yet or uh     
16:57     
yeah it is uh so like uh I haven't worked a lot with uh GitHub pages but uh     
17:02     
yeah I think it's uh it's like I was     
17:07     
thinking about like I don't know how this happens but um the GitHub uh the     
17:16     
Jupiter notebook is uh in between the zip files so uh people cannot really uh     
17:22     
see it at first but it's called ow studentship with the ipy andb uh     
17:30     
um it's called oldw student ship. op. iynb which is the uh thing for Jupiter     
17:38     
notebooks um so yeah that's on the GitHub right now with the zip files um     
17:44     
but yeah yeah so this is the fork of uh     
17:50     
Lucas's uh open room student ship project on dorm uh so we have this ZIP file which     
17:57     
contains uh Json files for each protein and then     
18:02     
this is The Notebook I don't know if you can render The Notebook oh uh this one apparently it's not updated for some     
18:08     
reason like I have a different version which is uh the more updated one maybe I have to uh oh yeah this is the one I     
18:16     
don't know why it's like the forking had a problem or something I don't know oh I just need to update the fork but I     
18:21     
haven't done that yet but oh okay yeah but this is yeah so this is just these are the proteins here and these zip     
18:29     
files so the zip files I think have like the Json files like two Json files per     
18:34     
protein or something and then this is the notebook and yeah so this is good um     
18:41     
and so yeah we can go over I guess you can go over maybe you know what's in the repository go to the notebook and then     
18:49     
um you know kind of while maybe walk through the notebook and then maybe walk through a single zip file to show the     
18:55     
Json format and like how that is structured and also you know kind of     
19:01     
what you know what that gives us in the notebook so like it's it's pulling in a Json file there's this API that's you     
19:10     
know maybe even talk about a little bit about the API that you're you know the source of the data that you're getting     
19:15     
so it's coming from somewhere it's coming from a database and you have you know the databas is assembled from     
19:22     
different people's primary data that they've collected and uploaded there and they have it in this format and you're     
19:28     
taking it down down and putting it in Json format and then bringing it into the notebook and so that I think would     
19:34     
give people a good appreciation for what was involving project yeah yeah great all right thank     
19:43     
you um so I don't I don't know Lucas you said you also wanted to present on a     
19:49     
paper today uh yeah I'm ready to present that if you uh uh I     
19:55     
actually uploaded the PDF file of the paper on the slack channel it's on in     
20:02     
the general Channel okay um yeah so can     
20:07     
you guys see the shared screen now yes yeah okay so um yeah the paper that I     
20:14     
chose to present is uh called the comparative genomics and functional study of uh lipid metalate genes and C     
20:22     
Elegance um so basically what this paper mainly does is that it goes over like um     
20:30     
they've collected 471 lipid metabolic genes in uh cigance and what they what they do they     
20:39     
they're basically they're basically trying to achieve two goals by publishing this     
20:44     
study uh the first goal is to uh develop a uh network of uh metabolic     
20:52     
pathways to um metabolic pathways using the 471 lipid genes and they're the     
20:59     
first to do it so basically um these authors used the 471 lipid metabolic     
21:04     
genes and assigned each one of them to a metabolic     
21:11     
pathway and they actually integrated each of the 16 uh Pathways into a     
21:18     
network uh which they go over later but yeah so basically the first uh goal was     
21:24     
to uh develop this network and the second goal um which actually is on a     
21:29     
deeper level is to um basically um they uh their second goal     
21:38     
is basically to suggest that uh celegans could be used as a model to study lipid     
21:45     
metabolic diseases or even other diseases uh human diseases so um yeah so     
21:52     
basically the first page goes over the abstract background and it's basically a summary     
21:59     
however what I wanted to go uh what what I wanted to mention is a couple of terms     
22:05     
that uh not a lot of people might know about maybe they know but I just want to go over them uh the first one is     
22:12     
orthologue uh so basically a orthologous gene or     
22:19     
orthologous genes are genes that have uh that um     
22:26     
basically are from the same common ancestor but they've been separated due     
22:31     
to a speciation event and um there's also another uh so basically they're     
22:38     
homologous but they've been separated due to a speciation event     
22:44     
there's also something called paralog which is not mentioned in this paper but um     
22:50     
basically a paralog or paralus Gene is a gene that or genes that uh have the same     
22:58     
common ancestor but they've been separated due to a gene duplication event which is also mentioned in a lot     
23:04     
of genomics papers however this paper mainly focused on uh     
23:09     
orthol and um there's another thing that has been mentioned in the first page     
23:14     
which is really important um so basically in the results section on the     
23:21     
first page they talk about um RNA I or     
23:26     
RNA Med mediated uh interference or RNA     
23:32     
basically um RNA well basically to look at rni we also need to mention uh     
23:40     
something called gene silencing so basically the idea of gene silencing is     
23:46     
that uh a lot of uh researchers try to either turn off a     
23:54     
gene expression or decrease the amount of gene expression to understand the     
24:00     
phenotype or a biological function of a certain Gene so basically there are two     
24:06     
uh types of gene silencing there's something called Gene knockout uh which basically uh is uh     
24:16     
Gene Knockouts completely turn off a gene expression so um there are     
24:24     
different uh Technologies used for Gene Knockouts like Talons or crisper and     
24:32     
they basically turn off the gene expression completely to understand the phenotype but in this case they use RNA     
24:40     
which uses the concept of Gene knockdowns Gene knockdowns basically     
24:45     
decrease the amount of gene expression so um they do not completely turn off     
24:51     
the G gene expression but they decrease uh the amount of gene expression and uh     
24:57     
RNA basically is a technology used to uh do uh Gene knockdowns and basically     
25:06     
based on my understanding they used RNA because um first of all it's uh I talked     
25:12     
to a couple of researchers about it and apparently uh RNA is uh a little bit     
25:18     
cheaper to use than crisper or Talent so that's one of the reasons they use uh     
25:24     
the gene knockdown method the other reason behind uh them using RNA technology was that they     
25:32     
um it's as they said um there about more     
25:38     
than 85% of the primers were available so um they didn't need to start     
25:44     
developing their own uh library for uh gene silencing they just H uh they uh     
25:51     
like um the primers for different leap uh for the a uh import uh like a significant     
26:00     
amount of lipid genes was already available so they basically used the already developed libraries to start     
26:08     
doing Gene uh uh gene silencing so that's another reason why they use the     
26:13     
RNA uh technology which I thought is uh kind of important to uh     
26:18     
mention uh because a lot of people don't know about it so yeah basically the     
26:24     
first page basically goes over the background um there's a lot of stuff     
26:29     
related to biochemistry mentioned in the paper too um like um fatty acids what     
26:37     
they are um lipids what they are and what they do and why they're important     
26:43     
and um basically yeah to give you a summary this page the first page     
26:49     
basically um goes over the entire paper just summarizes what they're doing and     
26:58     
yeah so that's the first paper uh sorry the first page of the paper um     
27:06     
and the next page page two basically um tells you a lot about how     
27:12     
these researchers uh obtain the 471 lipid genes so uh as you can see on     
27:19     
figure one um they obtained 168 lipid genes from a     
27:27     
database called keg uh I think it's pronounced keg if I'm not mistaken um     
27:34     
this the this database basically this database um is     
27:41     
also another database for Gathering like jeans but the unique thing that cake     
27:47     
does is that when you search for jeans on cake it gives you the it basically     
27:54     
gives you the uh uh Pathways that genes are involved in so     
28:02     
um that's a useful thing for these authors because at the end of the day they're trying to develop metabolic     
28:09     
pathways so they might have needed the genes uh they might have needed this     
28:14     
additional data so that's what another reason why they use Kake so um they use     
28:19     
168 genes from the G Kake database they used 147 human orthologue genes um     
28:27     
basically I think the main database for Gathering the 147 human orthol was uh um     
28:36     
I think it's also another tool named uh biomart um so biomart is     
28:44     
a tool used it's used in a lot of for a lot of things it has a lot of useful tools but     
28:51     
if you go on the BART website one one thing that they mostly use it for is     
28:57     
finding human Orthodox so um yeah basically the 14 the majority of these     
29:03     
human Orthodox uh were gathered from the biomart uh to and also 56 of these 471     
29:13     
genes were gathered from the literature well it says literature however yeah     
29:19     
they didn't gather all 156 from the literature and the published papers um     
29:24     
so as you can see on the on the bottom of the uh like uh in the description of     
29:32     
the figure it says that 156 genes um manually picked from uh wb.org and     
29:41     
published literature uh so yeah basically uh they picked the 156 jeans     
29:46     
from uh war.org which I think um which is also related which like is     
29:55     
an organization that has done a lot of uh research on sea Elegance too I think their their main goal is to uh develop     
30:04     
and contribute to the Sea Elegance community so um that's one thing and also um yeah so U figure one basically     
30:12     
mentions how they got the 471 lipid metab genes and     
30:19     
uh it also     
30:25     
um yeah so it also mention uh uh basically on the oh     
30:39     
here it basically mentions that U the 471 lipid genes and silans were not only     
30:46     
involved in distinct lipid metabolic processes but also play multiple roles     
30:51     
in uh response to oxidative stress aging and Longevity as well as other     
30:57     
biological process es that are also um kind of important when uh researchers     
31:04     
are studying human diseases um so yeah and um at the the     
31:13     
last paragraph basically goes over um um basically looks at the 471 lipid genes     
31:20     
and mentions the big lipid families that they got this lipid genes from so um     
31:28     
basically the main uh lipid family was     
31:33     
uh well one of the main ones uh was uh lipas the other the other one was     
31:41     
phospholipase and there's also a family called the p450 or     
31:47     
cyp um which is also another huge uh lipid family um so yeah basically page two     
31:55     
also goes over uh their results and mainly the lipid     
32:00     
genes um yeah um page well     
32:08     
um page uh three uh U you can look at the table one which basically um they're     
32:17     
uh summarizing the lipid metabolic Gene FES in cell leans and the other column     
32:25     
like um there's uh the genes that enzymes related to them and also the     
32:30     
number in database so basically um they they found the number of genes and uh     
32:37     
they look at how many genes there are in total and how many of them have been mapped in Pathways     
32:44     
um that's also kind of important for them because uh they were uh trying to     
32:52     
uh they were trying to uh develop that metabolic pathway so uh they're trying     
32:57     
to uh but basically summarize how many have been found and how many have been uh     
33:05     
mapped in pathway um the paper also mentions that some of them are uh well     
33:12     
basically the paper mentions that some genes were found like basically out of     
33:18     
all the 47 more lipid genes some of them could be uh could be specified to a     
33:25     
certain metabolic pathway but but some of them couldn't because for example the     
33:31     
cyp gene from the satome p450 family um     
33:36     
it's the paper basically mentions that these type of uh these genes from this     
33:42     
family um do not have a specific biological function um specific     
33:48     
biological function um for them so like um there's not a biological function     
33:55     
that has been assigned to some of those genes so they couldn't really specify uh     
34:01     
or assign those genes to a metabolic pathway um yeah and the rest of this     
34:08     
page basically goes over the lipid metabolic pathways uh one of the more     
34:14     
important things that they mentioned in this page was um the fact that like um     
34:21     
was the fact that um some of the genes such as uh like some genes had to be     
34:29     
well basically they mentioned the exceptions in uh the assignment of genes     
34:35     
to Pathways so uh like they mentioned the cyp33 E2 Gene that um basically     
34:43     
initially they found uh basically initially the cake database     
34:49     
gave them a different result than what the actual function of the gene was so     
34:55     
they had to reassign the gene into a different uh pathway and they go over     
35:00     
other genes too and mention um uh well some of them they mentioned that they     
35:06     
had to reassign uh because of uh confusions uh and uh different uh     
35:14     
database results and some of them they couldn't even assign to     
35:19     
the lipid metabolic pathway so basically that's the uh third page and the fourth     
35:27     
page um which I mean I'm a little bit disappointed because U I guess they     
35:34     
could have uh kind of um well it's a great figure it's a     
35:39     
great Network they've assigned all of these metabolic pathways but um it's     
35:45     
really hard to look at them you know it's uh I had to even I tried to yeah you have to you     
35:53     
have to zoom a lot basically if you've printed this paper you can't read it you can so um I guess what they could have     
36:01     
done was that they could have added the figure to appendix or uh did something     
36:07     
better in terms of representation of the network because uh it's really hard to read yeah that's the figure two is     
36:16     
basically the network of these 16 lipid metabolic pathways um so if you can if     
36:23     
you look at uh here it mentions that um the blue ones     
36:31     
uh basically like if you look at     
36:37     
um um let's say lolic acid metabolism um here if you look at this     
36:45     
pathway basically the blue ones like um     
36:50     
it's really H hard to read the gene I think it's like um w07     
36:56     
A8 two or something like that these genes are the genes that um the blue     
37:01     
ones are the ones that have been gathered from the Kake database um the orange ones are human orthologues and     
37:08     
the red ones are the ones from uh the literature and um the green dash line     
37:16     
which is really interesting um is basically representing the link to     
37:21     
different Pathways so there might be a certain product in a metabolism pathway     
37:29     
that is a substrate for another um like metabolic pathways so um what they     
37:37     
basically did is that um they connected the substrate and the product from     
37:42     
different metabolis metabolic pathways using the freeing dash line uh so yeah     
37:49     
basically um that's figure two and the other thing that this um     
37:57     
this page goes over is um the uh uh the     
38:02     
biomart which is uh I think it's right there um um the biomark so basically uh they     
38:10     
mentioned that um the they um used BART to find um     
38:17     
orthologs in human mouse rat and dropa so     
38:24     
basically um they use the 471 genes to find     
38:30     
581 human Orthodox uh 46 uh 585 uh um Mouse     
38:38     
orthol uh 563 rat orthol and 428     
38:44     
drop um orthol um and they also um well     
38:50     
basically this um this information um is the starting point to     
38:56     
look at the conservative genomics part of this uh or conservation uh sorry     
39:03     
conservation genomics part of the uh the paper so     
39:10     
basically um if you look at this um this paragraph they actually um     
39:19     
mentioned that over 70% of the uh celegans lipid genes have Orthodox and     
39:25     
humans and uh they mention that about 72.2% of human lipid genes are conserved     
39:32     
in celegans which um is a relatively High uh     
39:38     
um con uh relatively high percentage of uh conservation therefore that that     
39:45     
paragraph also U well basically highlights the importance of studying     
39:51     
seans studying seans been looking at uh uh lipogen or lipid metabolic diseases     
39:58     
because of this High conservation um High conservation     
40:04     
percentage um and this this paragraph basically um the conservation of     
40:12     
seans uh lipid metabolic Gene section basically um goes well basically they     
40:20     
look at a database called omim uh I think omim is uh     
40:28     
online melan inheritance and man database basically um it's a database     
40:34     
used to look at uh disease genes um     
40:39     
mainly human disease genes so um there was     
40:47     
19,994 MIM IDs basically MIM IDs were um the genes that they could F they could     
40:55     
find on the database and they     
41:00     
uh basically this section uh if you look at this section it's on page five     
41:07     
basically U they mentioned that out of all of those 19,000 or like close to 20,000 genes they uh found     
41:15     
15,181 genes that could be considered human disease genes um and     
41:22     
basically um they found out the they found out that all out of all of those     
41:28     
15,000 genes uh 1,264 of these um may be considered     
41:34     
metabolic disease genes um so basically     
41:39     
they uh found the um they use the omim database to find the amount of genes     
41:48     
that could be considered metabolic disease genes and uh they use keywords such as     
41:55     
uh obesity data uh diabetes metabolic disease and other U     
42:01     
major obesity related diseases basically um they use these keyboards to find the     
42:07     
12 164 genes and they um they uh one of the     
42:14     
most important things that they found out was that out of all of those     
42:21     
uh out of all those genes about 346 orus genes are conserved in all five     
42:30     
organisms so it means that um there were 346 genes that they found in this uh     
42:36     
database in this online database and 346 of them were conservant all five     
42:43     
organisms in C Elegance uh Mouse Seance Mouse R drop and uh um in humans so um     
42:55     
that's also an important number because um it also mentions that they um well basically due     
43:03     
to this um High conservation uh it mentions why they're using these um well basically it um it's     
43:13     
a number but basically it's a high number of conserved genes um which later     
43:20     
on is used in figure three to uh explain some uh conservation uh result     
43:28     
conservation genetics results and the most important part in this page in my     
43:34     
opinion is uh this paragraph where they mentioned that in humans uh 97 of the 581 lipid genes are     
43:43     
overlapped with metabolic disease genes uh that means that um they were like if     
43:50     
you remember the 581 lipid genes are the human orthologs that they found using     
43:57     
the 471 lipid metabolic genes in uh lipid lipid genes in seans so this the 581 is     
44:06     
basically the human Orthodox they found that 97 of those 581 are overlapped with metabolic     
44:14     
disease genes that means that all of out of all of those uh human     
44:19     
orls um 97 of them could be uh human metabolic genes and they say similarly     
44:27     
94 of the 471 uh lipid genes and celegans U are orthog human metabolic     
44:36     
genes and um they later on mentioned that crucially all 94 of those celan     
44:44     
genes uh overlap with the 97 overlap with uh the 97 human     
44:52     
metabolic disease genes um which also another uh basic basically they are     
44:58     
proving the point that uh seant are important uh models in studying uh uh     
45:05     
human diseases because of this High overlap of uh a high overlap of genes     
45:12     
and high conservation High conserv genes and yeah basically     
45:19     
um the other um yeah basically um they go over the results and numbers which um     
45:27     
um I just summarize the most important information there um but the other thing     
45:32     
to look at um is figure three figure three is basically um using U it's     
45:40     
really interesting uh they used a program uh called Veni to develop these     
45:49     
ven diagrams at first it looks uh kind of terrifying but um it's basically if     
45:56     
you look at like figure 3A um figure 3A is basically um looking     
46:03     
at basically human Dash Cel is uh um     
46:10     
basically there are five uh like yeah it could be like five uh kind of circles     
46:19     
and it's a van diagram say they look at commonalities they look at uh uh     
46:25     
sometimes like in the Sometimes some of the genes are not conserved like U 44 of the human and Cal     
46:34     
are just not conserved so they don't have any commonalities uh similar um to the human     
46:41     
SL Doopa uh you can also look that uh we can also see that the 44 of those ones     
46:48     
also uh don't overlap with any of them but the most important thing to look at     
46:54     
is uh the 5,081 5,085 genes um which is an important     
47:02     
number because um it's basically represents the amount of genes that are     
47:07     
conserved in all five um in all five organisms uh which is a high number     
47:14     
basically um this 585 if you look at look at it you can see that it's common     
47:22     
in all of the circles therefore it represents the conserved gen in all five     
47:28     
organism um basically 3B also has figure 3B also has a similar concept except     
47:36     
that they're in this case they're looking at the well F 3A looks at the uh     
47:42     
lipid genes in general um but uh figure 3B looks at the metabolic uh disease     
47:51     
genes um figure 3 C D and E are uh very     
47:56     
straight straight forward um you can see the 97 U like in figure 3C you can uh     
48:04     
see the 97 uh genes uh that are basically common     
48:11     
in human metabolic gen metabolic diseases and human lipids um three uh similar uh 3D also     
48:21     
represents uh the 94 genes um and and figure 3 again um basic     
48:30     
V diagrams but there also well the 3A and 3B Vin diagrams are a     
48:37     
little bit confusing but um uh CD and E are useful V diagrams in my opinion and     
48:45     
yeah basically the other section of this page looks at um the RNA or the gene     
48:55     
silencing method that they use um as they mentioned     
49:04     
um um the out of all the 471 lipid metabolic genes only a small     
49:12     
number have been bioch biochemically and functionally characterized that's why     
49:18     
they needed to use the gene silencing method to look at the     
49:25     
biochemical uh biochemical IAL details and functions of the other genes um so     
49:31     
basically um the next page basically looks at how     
49:39     
they did the gene silencing using RNA and the results uh though the me the     
49:46     
most important the most important part um in this page is Table Three basically Table     
49:54     
Three is a summarization of um uh these long paragraphs uh that are on     
50:02     
p u on page six so if you look at uh Table Three um there's sequence name     
50:09     
there's Gene name and there's LDS well basically LDS is a lipid     
50:16     
droplet size um and uh there's a column named     
50:22     
other phenotype phenotypes and the pathway and the key references     
50:28     
um basically they looked at these genes um they used RNA and um well if I     
50:37     
go um oh I can yeah I can well I can     
50:42     
explain the r lipid droplet size um better here so basically if you look     
50:49     
at figure four on page seven of the paper uh you can see that they've um     
50:56     
well first of all they used a uh they     
51:01     
used a method called NY um n blue I think not sure I think it was n blue if     
51:09     
I'm sorry NY red um so basically um NY     
51:15     
red is uh a is a Dy used to um well it's     
51:23     
mainly used for visual representation of uh uh different lipids and um it's     
51:31     
basically a Dye but uh I think most people have heard about Nile blue     
51:37     
basically Nile blue is um is uh well basically Nile red is a substitute of NY     
51:46     
blue basically they uh boil Nile blue with h2so4 or sulfuric acid to get n red     
51:53     
and then they use n red for uh um basically as a diet for lipid uh lipid     
52:01     
drop for basically the visual representation of lipids so as you can     
52:06     
see there's a control here um I think I can zoom in on that um there's a control     
52:13     
they use a uh lipid droplet as a control and then um they     
52:20     
uh use the RNA on different genes such as the sams1 Gene the     
52:27     
lp1 Gene and um they looked at that lipid droplet and they uh they reported     
52:38     
the lipid droplet size on table three so basically if you you can look at like um     
52:47     
like let's says1 Gene uh it had increased lipid droplet size therefore     
52:53     
it affects the growth rate and and so they could look at um they could mention     
53:00     
growth rate as a phenotype um and they also mention lean and     
53:05     
steroid um the atgl gene increased lipid     
53:11     
droplet um some of them in in an interesting part was uh that some of     
53:19     
them had decreased the lipid droplet size such as lpin1 Gene     
53:27     
um but the most important uh part uh well the most     
53:32     
important um phenotype and the most mentioned one was growth rate if you     
53:38     
look at U these genes you can see that growth rate um was mentioned in most of     
53:45     
the uh Gene phenotypes I think the paper later on mentions that out of the 21     
53:50     
genes that they looked at uh using Nile red uh 19 of them     
53:57     
um affected phen affected growth rate phenotype um so basically regardless of     
54:04     
the uh regardless of lipid droplet increasing or decreasing um um these     
54:10     
genes had an effect on growth rate some uh had positive effect on growth rate     
54:15     
some had negative effect um so yeah basically that's a summarization of     
54:23     
table three and then uh as we mentioned figure four um basically um looks at an     
54:32     
activation of uh 10 lipid genes by RNA and uh looks at fat storage they     
54:39     
have a control there so they can uh look at what happened to the lipid droplets     
54:44     
in uh different genes and yeah this part     
54:50     
uh is the discussion section the discussion section mainly goes over um     
54:58     
um mainly goes over um the uh like     
55:04     
basically um is again a summary of what they've done     
55:09     
um they uh basically I have gone through most of uh the discussion section there     
55:16     
but um um basically the other thing that I wanted to talk about is uh figure five     
55:24     
on page eight which um um um I think a lot of people who uh are     
55:30     
part of the seans community have seen uh uh this type of uh pictures it's     
55:38     
basically um um that's the control one is an empty     
55:46     
vector and um they use um they basically use a control to look at um     
55:53     
the um they basically look at uh the     
56:00     
development um of C elegance and how those genes affect the development of     
56:07     
cgant and U Yeah so basically uh this this part of     
56:14     
the paper also um well basically     
56:19     
um also mentions U well there are two important parts that I wanted toight     
56:25     
highlight um one of them is this part for um they     
56:32     
basically mentioned that um seans and humans share High     
56:37     
conservation in terms of lipid genes and their roles in metabolic diseases     
56:43     
suggesting that cigance is likely a useful and insightful model for uh um     
56:48     
for use not only in research on the fundamental uh biology of lipid     
56:54     
metabolism but also expl exploring the mechanisms of human metabolic diseases     
57:00     
so yeah they basically again mention the importance of celegans as a model     
57:08     
and on the other paragraph U they mentioned that among the 471 liquor     
57:14     
genes um nearly 40% genes were reported to affect     
57:20     
phenotypes example as an example they use fat content D life     
57:26     
root size Etc um I also wanted to uh well um I also wanted to um explain what     
57:35     
D is so basically if you look at um the     
57:40     
uh developmental stage in C Elegance um it starts uh well     
57:48     
basically there are two like basically there are two versions of Sean's life     
57:55     
cycle there's one version where uh you assume that     
58:01     
cgans the the organism U is in uh a good environment basically a good environment     
58:08     
is um described as having enough food so basically if cens is in an environment     
58:16     
where it has access to eoli which is its main food um they'll start as L1 go to     
58:23     
L2 L3 L4 and than the adulthood stage so     
58:28     
basically that's um the seans life cycle on an assumption that Seance is in good     
58:34     
environment however if um Seance start in a bad environment um basically the     
58:42     
bad environment would be the lack of food um basically they start as L1 but     
58:48     
they go to a stage called l2d and then a stage called d a d St AG     
58:56     
is basically like a hibernation state where um cigance is in that state until     
59:04     
they um until um like they're put in a good     
59:10     
environment if they're put in a good environment they go to The L4 stage and     
59:16     
then the adulthood stage however if they're not if their environment doesn't change they I think they stay in that     
59:23     
Dow stage um also another thing that I wanted to mention about the Dow stage is     
59:30     
that um um basically it can only happen before um before um L2 so um before     
59:41     
puberty they can enter the Dow stage however after um puberty or after the L2     
59:49     
stage if you change their environment from a good environment to a relatively     
59:54     
harsh environment um they you basically might destroy them     
1:00:00     
um but yeah that that's basically the d stage which they mentioned which is also     
1:00:06     
an important Concept in seans developmental stages uh so yeah that's     
1:00:12     
page eight of the paper and um page nine um again basically there's a lot of info     
1:00:20     
here but um B basically um these     
1:00:25     
paragraphs look at the um the genes and they look at the     
1:00:33     
omim um database results um they've also     
1:00:38     
um mentioned the Nile red staining uh     
1:00:43     
method and basically that's all about lipids and what they've done and um as a     
1:00:52     
conclusion they uh conclude uh two things again um the fact that they've     
1:00:58     
created four uh they've created a database of 471 SE against lipid genes     
1:01:04     
they found the human orthologs um they found that over 70% of     
1:01:10     
seans lipid genes have human orthologues um and they also mentioned that out of     
1:01:17     
uh all of those genes they use 21 lipid genes um to     
1:01:24     
study um on more depth using the RNA method so um and the reason why um it's     
1:01:32     
it's really interesting the reason why they used 21 but basically out of the     
1:01:37     
471 they had uh I think access to about 356 primers so they basically uh tried     
1:01:47     
using RNA on 356 uh lipid genes which is a little bit     
1:01:53     
time consuming but out of those 356 they found 21 lipid and they studied it in     
1:02:01     
more depth the reason why they chose 21 was that um those 21 were the main ones     
1:02:08     
that had a significant effect on fat storage or development or reproduction     
1:02:14     
the rest of them either did not have a significant um either did not have a     
1:02:22     
significant effect on the phenotype so they couldn't study it or um um it was     
1:02:29     
uh basically um or the primer was basically not available     
1:02:36     
in the library um yeah and the last part basically is     
1:02:41     
the method section the method section again um goes through the construction     
1:02:46     
of uh the database and uh how they found the 471     
1:02:52     
genes and they also um well the next page also mentions um The     
1:03:02     
annotation of lipid metabol genes uh how they annotated it     
1:03:08     
um they basically used a lot of important tools that um I think a lot of     
1:03:14     
people um can also use and it's really important um to go over all of the tools     
1:03:21     
one of the tools that they use is Veni which is uh used for V diagram     
1:03:26     
another tool that they used is uh um the biomart which they use for ortholog     
1:03:34     
orthologous genes and finding orthologous genes um they use the omim database     
1:03:40     
which is also a great tool um they use K database basically um um I found that     
1:03:47     
this paper also um gives you a lot of uh insights on different tools and how to     
1:03:53     
use them and what their importance are well basically they didn't go over it in     
1:03:58     
depth but um they basically name all of the tools they used and I think it's     
1:04:04     
useful for other researchers as well um yeah at the end they go over um uh the     
1:04:12     
growth condition and RNA um basically they mentioned that     
1:04:18     
um the standard protocols were used to maintain the cigan N2 strain at 20° C     
1:04:27     
with uh EO and um yeah um they also go     
1:04:34     
over the um they basically go over the details of     
1:04:40     
um the protocols and uh the N red staining um n red     
1:04:48     
staining U methods um there's also a growth growth     
1:04:54     
rate and St analysis where uh they uh give     
1:05:01     
references to the growth rate analysis um you can look at the references     
1:05:07     
section for that one and they also mentioned that all images were captured using um identical settings and exposure     
1:05:15     
times uh one of which clearly late fewer eggs were recorded as having a eggling     
1:05:21     
effect and those with no eggs will record as steroid so that that was basically um that was uh basically the     
1:05:32     
paper all right that's that's great um thanks for the presentation I know that     
1:05:37     
was a lot of stuff maybe people didn't really understand everything that was going on I think Lucas kind of laid out     
1:05:44     
a lot of the take-home messages in that paper so you know they're doing like     
1:05:50     
genetics um they're getting data out of a database to look at what's that they consider to be     
1:05:57     
conserved uh then they do annotation so they know the function they fit them into these     
1:06:02     
metabolic uh Pathways then they do these assays which are you know the the the     
1:06:10     
lipid metabolism phenotypes they do the RNA which basically knocks down the     
1:06:15     
expression of a gene and then they make comparisons between seans and     
1:06:20     
humans so the you know the reason why we use seans as a model organism for     
1:06:27     
medicine is because it's easy to work with you get a good generation time you     
1:06:34     
get you get to do things like look at sterility you get to do things like look at lipid metabolism in a very simple way     
1:06:41     
you just take a uh microscopy image and you look at the droplet size lipid     
1:06:47     
droplet size and you can assess from like the wild type or the the control if     
1:06:53     
it's larger or smaller and but as you mentioned there are a lot of cases where you can't definitively     
1:07:00     
say um and you know we have these defined mutants and SE allans so for     
1:07:05     
there's a whole database of defined mutants where people have taken genes and knock them out and then they can     
1:07:11     
characterize the phenotype very easily well not for all of them but for most of them and we know we can map that to the     
1:07:18     
genome so we know kind of when we knock out a certain Gene and there are a number of uh     
1:07:24     
defined newants that for like metabolism where you have uh if you knock out that     
1:07:30     
Gene and this is through uh you know not RNA but a more um a more complete     
1:07:38     
knockout process um that you know you have this strong effect the strong     
1:07:44     
phenotypic effect and so um yeah so you can use theine mutants you can use RNA     
1:07:51     
which is cheaper and allows you to do that in context so you can look at the metabolic pathways and that's all you     
1:07:58     
know very easily manipulable in a lab so finding the connection between seans biology the manipulations that you can     
1:08:05     
do in seant biology and then the human disease Pathways and human disease phenotypes is very     
1:08:12     
useful so you know we have different medical models for seans like in Aging     
1:08:19     
in um metabolism of course in uh some     
1:08:24     
other disorders um you know there you'll see seans used     
1:08:29     
quite a bit in human medicine studies and you'll wonder why we're doing this     
1:08:35     
it seems like it's a very distant uh distantly related animal and the answer     
1:08:40     
is this because we have these uh we have these orthologues we have these you know     
1:08:46     
these highly conserved areas with respect to function that are not only concerned with humans but with mouse     
1:08:54     
where we do a lot of other bi biomedical research and using mouse and rat as analoges for humans because they also     
1:09:00     
have very similar you know they have you know conserved genes they have     
1:09:06     
similar physiology and so you know we don't want to do these experiments on humans we can't slice them up and do all     
1:09:13     
these things but we can do it with these other organisms so very good Lucas thank you     
1:09:19     
for that presentation I know that was something he presented in a journal club and now     
1:09:24     
he wanted to presed here so I think it's a great great overview of     
1:09:32     
it yeah and if anyone has a has questions uh I I can also kind of answer     
1:09:38     
to the best of my ability if you guys have any questions but yeah that was that was basically the P so yeah that's     
1:09:46     
that's great now uh I don't know if Jesse is available right now I don't think we had any real meetings     
1:09:53     
um this week in the conv itional sense um I have had I've did a little     
1:10:01     
jopro related stuff um at a at a broader     
1:10:08     
level um no no major updates but the a few things     
1:10:15     
with the mental health working group um J still working on a bunch of stuff there which I     
1:10:23     
appreciate and I guess the biggest the biggest real     
1:10:28     
news of this week is more like an administrative research coordination level I met with     
1:10:37     
um my old's     
1:10:42     
department or I guess the college within the     
1:10:47     
university and it was really good I was actually really really impressed by them     
1:10:53     
and where they've gone I haven't really been in touch the last year or two or so     
1:10:58     
and said things have changed and everything else but um people have kind of left in come and gone and all that     
1:11:05     
the department itself and what they're doing for like experiential learning and Outreach and creating opportunities for     
1:11:11     
students is very um     
1:11:17     
um promising like they've taken they've addressed actual concerns I had as a     
1:11:23     
student and I had in the past so kudos to them kudos to CC at the Aly     
1:11:31     
for um stepping into some things and and making happen basically we just it was     
1:11:37     
just really a catch-up call but like um they we have opportunity to do some     
1:11:43     
internships kind of things we even they even have like a particular opportunity where um well I don't know a modification of     
1:11:52     
opportunities where they realize a lot of things don't start at like     
1:11:58     
August September 1st so they have um like midweek they have it so you can     
1:12:04     
start certain things in the middle of like the semester for example to     
1:12:10     
create more flexibility for organizations and students to start internships or learning you know     
1:12:17     
experiential learning opportunities and so on um and things like that I think are quite like that's a huge barrier to     
1:12:25     
reducing friction for uh many students and I I I respect that so functionally     
1:12:33     
what do this been for us um I'll be talking with them again soon and not you know different colleges and or different     
1:12:41     
departments and well I guess colleges and and other things like that will have some different opportunities     
1:12:47     
but um there's a lot we can do in terms of society ethics Tech uh some things in     
1:12:55     
data science in general I I might do some data ethics things there     
1:13:01     
some uh those spaces and then Bradley also mentioned about model builder um as     
1:13:09     
as an internship and and I think we've talked about I think we even have a description somewhere in the past but     
1:13:17     
there's the the college will have um they look quite promising in terms of     
1:13:23     
their ability to have some Niche things that aren't just informatics doing     
1:13:29     
student doing informatics internship or whatever like like very clearcut like they they are open to doing some like     
1:13:36     
interdisciplinary or adjacent related things as well which is which is     
1:13:42     
promising uh but then also um understanding that     
1:13:49     
there's there is opportunity to do it with the main campus Center for other things that maybe more like     
1:13:55     
predominantly like psychology related or cognitive science related we can do through the main campus um like like     
1:14:02     
Research Center um but it was good to meet with these folks and and I'm happy     
1:14:08     
to um I don't know if we want to talk any more about this now but I think it would be good to talk about the model     
1:14:14     
build thing that Bradley specifically mentioned and some other ideas and opportunities we have there in the     
1:14:19     
future but but the summary is that it was a really I was I was legitimately impressed and     
1:14:25     
um I think there'd be some nice opportunities ahead so look     
1:14:31     
good yeah I know you mentioned that in the slack and I kind of thought well that would be a good opportunity to do     
1:14:37     
the model builder as a as a piece like an internship piece also yeah I think     
1:14:44     
Society ethics Tech you know that's been something that has Darner some interest in the New York celebration women in     
1:14:51     
Computing so that's unnatural or obvious thing to do uh data science stuff that's     
1:14:58     
what they do there as well you have some expertise in it now and uh so yeah we     
1:15:03     
can do that um you'd have to kind of figure out how to you know uh kind of would I guess     
1:15:11     
with data science or something like that we'd have to figure out what people want to do specifically it's not easy to kind     
1:15:18     
of just say here are some things um why don't we work on them uh     
1:15:25     
whatever you know kind of uh you get you get a certain amount of uh expertise out of that but if you had a specific     
1:15:32     
project we could tie it to uh then you know that makes it a lot easier and we don't have like although     
1:15:39     
we have some stuff we could do in the group but it I think it's better if we     
1:15:45     
try to find like something that we can put together like you know if they want to work on something in a platform kind     
1:15:51     
of work out a model I'll have some data available that they can mine or something that would be good instead of     
1:15:58     
just kind of saying go for find your own thing and go for it and you know spend half the term kind of figuring out what     
1:16:04     
people want to do yes I agree with that very much um     
1:16:10     
and I do think I think I wrote this somewhere but it's an important Point     
1:16:15     
what's interesting previously my work with what the former version of these     
1:16:21     
groups at You me we were very limited any what we     
1:16:26     
could we basically had to have one extremely generic     
1:16:32     
hosting now with the way things are currently we actually can do much more     
1:16:39     
especially for like data Science eics Tech data science ml like like like the     
1:16:45     
groups that I mentioned will have opportunity to do much more individualized postings and especially     
1:16:50     
For What Bradley said for data science thing I think that that makes a lot of sense but I think we could even do     
1:16:55     
there's like a complex systems lab um at at the at the at the in the college um     
1:17:03     
there's a few others that are like particularly relevant to what we can do     
1:17:08     
to what to what we do in the lab as it is and so I'm going to be investigating what those are and either offering like     
1:17:16     
a partnership or some kind of like a a not partnership but like maybe some kind of a joint thing or     
1:17:25     
like at least seeing what kind of research opportunities are already being offered and making ours you know fit     
1:17:33     
that mold a bit um but we have the opportunity to be a     
1:17:38     
lot more specific which I think will be nice to do I suspect for the other     
1:17:46     
Main Campus Center will have like one I think they'll be a little more generalized but in this in this college     
1:17:52     
we'll have the chance to do more detailed things which could be quite exciting um but yeah I'll know more     
1:18:00     
about that over the next week so okay yeah that would be great     
1:18:05     
um I've been actually working on the um cards that we mentioned I think it was     
1:18:11     
last week or the week before and updating those and just looking at them I was like oh these are really out of     
1:18:17     
date yeah so obviously I needed but I I've actually generated some for some     
1:18:23     
sort of encapsulating just projects but kind of like themes in the lab so I've been working on that I'm not ready to     
1:18:30     
share it yet I'll be working on it more maybe this weekend but uh we'll we'll go over those soon and that those will be I     
1:18:38     
don't know if that's necessarily the best kind of description but I'm kind of working out some     
1:18:44     
descriptions so that we can if we don't want to use those cards we can move that to some other     
1:18:50     
medium you know kind of just give people a taste of different things that we do we want to     
1:18:56     
do I I think one thing that I'm particularly interested in doing is     
1:19:03     
consolidating especially I think I think the book review that you that you've done uh I think will be a great leading     
1:19:13     
to the developmental bright vehicle project I don't know whatever we want to     
1:19:19     
call that all of that stuff like that that's not even necessarily some of going to pitch although we we could some     
1:19:28     
some point but like I think that's a coherent project thing that we can do I I need to update go summer code stuff     
1:19:35     
we've had a lot of you know nice contributions and and and and discussions and all this stuff happening     
1:19:40     
for that but like I need to update that page I've had to move things around in the Jero website a lot and that was sort     
1:19:45     
of where the ban archive was but I I'll that will be     
1:19:52     
uh updated too but I think that the great Vehicles is a really cool space     
1:19:58     
between that and also this sort of um um some conversation with Avery who who     
1:20:06     
is not often at these meetings but uh we we talk frequently and um there's     
1:20:13     
there's a definite overlap between some of what Avery's trying to do and essentially like I think they're could     
1:20:18     
even be like um one of the things I wanted to do and and never really fully did I think I     
1:20:25     
forgot what I called it before but basically     
1:20:32     
like I'm I'm I apologize because all the terms that come to my mind are terms from everywhere else and not in the lab     
1:20:39     
so they're going to sound really out of place but almost like a center or a     
1:20:44     
group or something something focused on simulation it's basically     
1:20:50     
representational brains and phenotypes let me just call it that like representational brains and pH types was     
1:20:56     
the sort of banner that I originally came in underneath it was about developmental bra Vehicles it was about     
1:21:03     
even what was it called like contextual geometric structures and stuff like that that old school it came up in a     
1:21:08     
discussion this week about some Aver and some other TOS too it's like all the stuff from that era that I think is you     
1:21:15     
know maybe it's Dev now or whatever it is but like this this this sort     
1:21:20     
of the the metab brains developmental brain Vehicles some things in the CGS     
1:21:27     
category um like something there that's about simulating these things and like     
1:21:33     
creating like what can we take away from you know I don't want to say the unique     
1:21:39     
the uniqueness of this lab in that we don't you know we're not doing uh like wet lab stuff but access     
1:21:45     
to certain like computational simulations and we can do that way and and and like having something about that     
1:21:52     
specifically I think it's something that I may try to focus on     
1:21:57     
but it requires some other things to develop more but yeah yeah yeah like     
1:22:03     
all that stuff is on my mind yes let's let's please revisit the I mean I I like the idea of having this     
1:22:11     
overarching uh approach to the representational brains and phenotypes that's that's still a thing by the way     
1:22:17     
that's like overarching because we have a website for that and that's where things get updated for all those so it's just like     
1:22:25     
you know you have this right now you have this sort of large collection of     
1:22:30     
work on you know modeling you know agentive modeling and uh you know other     
1:22:37     
cognitive science type things that we're doing which always tie into that usually and then you know that so that's all     
1:22:43     
kind of in that area now I you know it's just kind of there as like a name on on     
1:22:49     
a bunch of things but yeah it would be nice if we could like stake out some     
1:22:54     
sort of you know saying why we put all these things together in the same     
1:23:00     
pot do do you think this is more this is kind of a side question but I do like I know a lot     
1:23:08     
of talk has been about like you said agented modeling agent based models some of this stuff I feel     
1:23:15     
like that's maybe a good term but also like I think that's I think do you do     
1:23:22     
you have comment or agree or disagree that agented modeling or make like     
1:23:27     
saying like that would be more of a subterm rather than the whole thing like I still think the best like overall Banner is probably the original     
1:23:35     
representational brain spenot types thing right yeah yeah okay but it's just I'm just saying what what's in there     
1:23:42     
like yeah exactly okay um that's what I thought I'm I'm     
1:23:48     
thinking about how to like you know all this like weird administrative discusting like presenting stuff which     
1:23:54     
is always awkward and like inherently incomplete so that can be a whole discussion to have um later is enough to     
1:24:02     
happen now but I I think that's um there's stuff to do there and I will try     
1:24:08     
to be uh put that into the pipeline of stuff that's like happening um adjacent     
1:24:16     
to the nship adjacent to reaching out here adjacent to the stuff I'm doing     
1:24:21     
with UCSD which is a little bit um they're time they're like you know three or four or five weeks behind what we're     
1:24:28     
doing here so it's it's a uh yeah um anything I have like one     
1:24:35     
other slight update but anything else you want to say about about all that stuff not right     
1:24:41     
now um my other slight update is I'm making slow progress on a number of     
1:24:47     
things that come well in my life and one of them in the lab like Howa     
1:24:54     
PA was like interested in this uh finding an organization to do     
1:25:00     
some of that Grant like I think it was her model cards idea or like something about the NSF grant for certain kind of     
1:25:06     
learning or something um I think I think I'm not I'm     
1:25:12     
not uh I'm not the best person to speak on where that is I understand some I think     
1:25:18     
there's still looking for a grant an organization basically to to to manage that so between between that and the I     
1:25:27     
think it's the what is it called the future of Life Institute has the grant     
1:25:33     
as particularly interested in about like AI power or whatever concentration I     
1:25:38     
think I'm going to try I think I'm gonna I don't I I'm I don't know if the time is going to work out for stuff but I     
1:25:47     
have at least taking it a little bit seriously and sort of reaching out     
1:25:53     
about who who to do what and I I finally found the right people at UCSD who would     
1:25:59     
tell me like they're they're they're sponsored research office basically and     
1:26:04     
and like their Grant I need I'm I'm I will be getting     
1:26:09     
some familiarity at least talking that office in CLI having them show me the ropes about what is it like to get that     
1:26:16     
kind of a grant from an external group and use it in this way as whatever which     
1:26:22     
I would love to win the Grant and have a a wonderful experience with that that might help this lab and or joepro or     
1:26:28     
other products or whatever on varing ways it wouldn't be gigantic but it'll be something you know an experience but     
1:26:35     
I think the experience of working with the grant office will be beneficial to a     
1:26:41     
lot of things I or we are trying to do later on too so that is in motion I     
1:26:47     
don't it's kind of been a bumpy ride because they're they're on breaks but     
1:26:52     
the deadline's ahead of time and then y Al is in a different way and I'm trying to sort out all this other     
1:26:59     
stuff so things are in motion it's exciting it's weird uh but that's you     
1:27:05     
know that's the nature of of it well that's great thank you Jesse for the update so this is the uh     
1:27:12     
representational brains and phenotype website yeah you can see the     
1:27:17     
representational dbrain phenotypes weebly.com it links from the     
1:27:23     
orthogonal lab um sites if you go back to orthoga lab     
1:27:28     
it's under um neuroi so we have people collaboration you go to neuro AI we have     
1:27:36     
this representational brains of phenotypes we go to that and we this is an image I made from like a brainbow     
1:27:42     
image of neurons and some agents on top of them but you know the the idea here     
1:27:48     
is that we're kind of pooling all the work that we're doing on these uh computational models     
1:27:55     
uh embodiment agentive models even stuff that's bio inspired to kind of bring     
1:28:01     
that together into one place and so this is uh we have a couple of categories     
1:28:07     
here cultural computational modeling which actually something we were doing um you know we were doing uh the     
1:28:14     
contextual geometric structures but we also uh did a uh I did a number of     
1:28:20     
papers before that uh with her cas G Carney on some things in machine     
1:28:27     
learning and kind of working on cultural things in machine learning so there are a lot of variations to this we have     
1:28:34     
talks papers preprints uh gck Stuff Etc uh so we have     
1:28:43     
that then we have growth in form which is you know kind of things having to do     
1:28:48     
with uh this is more dorm related but computational models of um Rel to of     
1:28:55     
organismal growth and form but also with respect to incorporating those into     
1:29:00     
embodied agents this is kind of one of these things that's kind of very loose     
1:29:06     
and you know it's uh so the super performance paper presented at be AI is     
1:29:11     
in here but we have some other things as well critical period stuff kind of falls into this category so this is um you     
1:29:18     
know this is all just kind of work so you know we have like these categories     
1:29:23     
and and each category is a work in progress and so as we kind of go through that the Motions on writing papers you     
1:29:32     
know coming up with ideas that kind of fit into these areas so you know there is no real synthesis here it's just kind     
1:29:40     
of all these different areas um stuck together sometimes it feels like there is no organization but     
1:29:47     
they're related because you can relate them it's not that they've they're fully synthesized and realized     
1:29:54     
so then there's the phasic IIA which is uh this phasic which is physical     
1:30:00     
intelligence augmentation systems and complexity uh and intelligence     
1:30:05     
augmentation so this is an area that we haven't talked about a lot but I have a map of it on the orthogonal lab if you     
1:30:13     
look at the carousel on the main website there's a uh sort of a map of what that     
1:30:20     
is and how those things relate to one another so this is you know you know um     
1:30:25     
some talks this is from neurom match uh talk that I did on human assisted Ai and     
1:30:32     
some other blog posts some Publications so that's an area and then finally     
1:30:38     
cybernetics and complexity which is the work that we've done on the agents and agent based     
1:30:44     
models and embodied agents so things like gonan information intelligence     
1:30:50     
offloading and developmental agents um uh metab brain models um developmental     
1:30:58     
brain vehicles um embodied continual learning     
1:31:03     
and even some things on cybernetics and the embryo and then of course the stuff on     
1:31:10     
good regulator theorem as well kind of fits into this uh so that kind of overlaps with what we're talking about     
1:31:15     
with uh cybernetics and so those all kind of fit together a question is how do they fit     
1:31:22     
together um and how do they you know we've talked a little I mean in some of     
1:31:28     
the papers we've talked a little bit about something called developmental neuro simulation that's like one thing that's     
1:31:35     
kind of youits maybe sa the stuff on briber vehicles but there's more synthesis to do there and so you know     
1:31:43     
that that's what we're striving towards but that's like kind of one of uh well one of the big areas of the lab the way     
1:31:50     
I have the website set up I have like the orthogonal lab site and then I have these we have these projects some of     
1:31:56     
them are administered by Jesse some are by me and we have like these different     
1:32:01     
websites so that's why it's a little bit when you go to look for papers if they're on different websites but     
1:32:07     
there's a reason for that and so we have all these sort of websites with     
1:32:12     
different sort of themes and you know then we have within that theme we have things that need to be synthesized and     
1:32:20     
so that's an overview of representational brains and phenotypes what one of the things that     
1:32:29     
I have been building up doing for other     
1:32:34     
things and I would offer to do here     
1:32:39     
is like um what I'm turning joepro into like the     
1:32:45     
main joepro website is essentially modeled after the MIT media lab and I     
1:32:51     
can either show my screen or just talk about I don't really care share your screen I think but um because I think I     
1:32:58     
think I think what I might do is propose something here let me see if I     
1:33:06     
can make this easier um so this is the media lab um     
1:33:15     
there it's actually a very interesting website i' I've spent a lot of time diagnosing and dissecting it so what's     
1:33:23     
cool about this is that the media lab itself the front page of it is just a bunch of these like updates and posts if     
1:33:28     
you look on the bottom left I think you can I don't know if it's going to show on the screen share but you can see like     
1:33:34     
the URL preview is like post or publication or like groups and they have     
1:33:43     
basically just put everything as one of these tabs here then you have the the menu like research about right whatever     
1:33:51     
but like let's let's do um this one might work so here's a post     
1:33:58     
about something that's sort of like a news article but then they have topics and people and projects and then groups     
1:34:04     
like this is the responsive environment groups they have their cool little MIT logo whatever and in the group you see     
1:34:10     
people and all this other stuff but it's also yeah it's great there's a group     
1:34:17     
website and this will take you to like the equivalent of the representation     
1:34:23     
brains and know types page right and I'm realizing like what what I might suggest     
1:34:29     
doing um is essentially joepro is acting     
1:34:34     
a lot like what the main like what this page is or like as a     
1:34:40     
place to house stuff it's not necessarily A oh this is kind of an     
1:34:45     
awkward website I suppose well no it's fine a really cool website excuse me um     
1:34:50     
it's a very cool modern website and I didn't think was um     
1:34:57     
but it essentially the the the media lab stuff is sort of almost uh a     
1:35:05     
a um landing page for many many many     
1:35:11     
different labs and projects like if you go here it's it's it's well spelled out     
1:35:17     
in terms of like this is a nice way they talk about it here it     
1:35:22     
loads um uh which is taking a very long time for this space     
1:35:27     
load but like yeah blah blah blah dozens of research     
1:35:33     
groups initiative centers working on hundreds of projects so they break it down through projects and initiatives and all this stuff and I feel like what     
1:35:42     
I can try to do if it's of use is make a little bit more of a front page for     
1:35:48     
these different one to Children the things in the lab but the uh like the     
1:35:53     
phasix project or I don't know if that's really a project or not but like the phasix thing The     
1:36:00     
phasix Entity yeah um and and and essentially give it more like kind of a     
1:36:07     
front page not that it would not that maybe more like landing page because I don't I want I really like the idea of     
1:36:14     
having the separate like this this site is the is the actual page where the updates are     
1:36:20     
the news are but having something essentially stop sharing my screen but like     
1:36:27     
essentially what what I tried to do with that GitHub page a while ago that was sort of a an attempt at organizing     
1:36:34     
things a bit more I think it may be easier to do now in a different format     
1:36:39     
so I don't know if what I'm saying makes a lot of sense but like I think there are ways to do that that might     
1:36:46     
be help some of the organization but then also keep funnel people to the right stuff in terms of seeing like     
1:36:53     
phasix work stuff like that yeah well I think yeah there is sort of a a public relations aspect to     
1:37:01     
the main media lab page of this okay here are the new things that we're we're working on here are the ongoing projects     
1:37:08     
I mean they have more press releases there but also you can just basically     
1:37:13     
you know highlight things like we had the timeline which was very um hard to     
1:37:19     
read or hard to get anything out of it's just like okay at this time we did this it would be nice to have and it might be     
1:37:25     
a little bit of work of course but to have like a you know say this why it's     
1:37:32     
you know we did this thing why it's important yes yeah have some resources connected yeah I think what I'm what I'm     
1:37:39     
working on with the Joo website right now is basically I've been made some custom I basically I've attempted to     
1:37:48     
emulate some of how the media lab does they have a nice way of breaking down people projects in the working groups     
1:37:56     
and I think that could be a nice way to separate out like if you go to the working group or a project it will give     
1:38:03     
a little description about it and I think that would be that's something I might try to work on I guess and uh on     
1:38:11     
if I do make progress on it I'll I'll let you know but it will I think I think     
1:38:16     
that would be a direction that I could see it being a good way to go yeah yeah     
1:38:21     
I think so that would be a good idea yeah yeah it would be you know something it would take a bit of time to maintain     
1:38:27     
but would be good yeah and I what what like I know this is a really deep in the weed and nobody car about this but but     
1:38:33     
Me Maybe Bradley right now well like what I've realized is there's a there's a much easier way in the way I've at Le     
1:38:41     
done it in the past where like if you funnel stuff in the right way it won't     
1:38:47     
require the maintenance and and like all the GitHub stuff that I tried to do before were just kind of nice but like     
1:38:54     
very not Evergreen enough so I think there's some there's some things that I found that I think are going to work     
1:39:00     
well so I will I'll try to like report on that over the next few weeks or so um     
1:39:07     
particularly as we develop the other things and the interships in the model building and everything else too so yeah     
1:39:13     
yeah yeah be great step away from that yeah so that's great uh thank you Jesse     
1:39:18     
for the update and for those uh all that great work in terms of getting laying out the sort of mentorship stuff and     
1:39:26     
everything else uh is see Trevor Trevor has joined us welcome     
1:39:32     
Trevor Morgan I don't know if you want to give an update before we move on to other     
1:39:39     
things yes sorry for being late today fine spaced     
1:39:47     
it I was just gonna um say     
1:39:53     
sort of relating to Jesse U     
1:39:59     
um talking talking with Sunni people that um I think the the link that you     
1:40:06     
posted about um was it centering AI medicine     
1:40:13     
or AI um something like that anyway they     
1:40:19     
were partnering with uh Sunni downstate [Music]     
1:40:24     
and uh in terms of neuro attack there's two two really interesting groups at Sun     
1:40:30     
downstate um one is um mayam bix's Group     
1:40:36     
which is focused on um neurom modulation so kind of one of the one of the lead     
1:40:43     
groups in in tdcs um so electrical stimulation but     
1:40:49     
but really does follow lots of those um organizes the neurotic group or the     
1:40:55     
neurotic conference that just happened and um you know is is a huge     
1:41:02     
draw um I believe at neurotic dog and     
1:41:08     
um um yeah so so it's really really good group on that front and then um the     
1:41:16     
other group and I'm blanking on his name except that I know know that     
1:41:23     
it's it's very Spanish it's like Salvador somebody and I'm blanking on it     
1:41:30     
but it's the net Pine um py n.org     
1:41:37     
[Music] um developer or lead and um so that's a     
1:41:43     
that' be like a computational neuroscience um group and they work in     
1:41:50     
addition to you know it's kind of an extension of neuron the the the software     
1:41:57     
package and project um which is a really bad name for Google searching um     
1:42:05     
[Music] but together with     
1:42:11     
um sorry I'm forgetting the um metacell um metel does their     
1:42:21     
um like gooey front you know and Mel does doeses that kind     
1:42:28     
of software contract work for a lot of open source project right yeah yeah just     
1:42:34     
just wanted to mention those two just when I saw Sunni down state I is like oh     
1:42:39     
well at least on that neurotech front I don't know if that that helps um maybe kind of refine some some     
1:42:49     
project ideas or things like that but definitely like that the those would be two really great     
1:42:57     
resources from sun down state that would be um I I would you know highly suggest     
1:43:02     
to to link up with if there students interested um I think they they referred     
1:43:08     
to it as like links to City down state for translational and clinical research     
1:43:15     
yeah that's great yeah thanks for that update um all right so uh in one of the     
1:43:22     
I don't remember what channel it was uh I think it was Morgan who posted this     
1:43:29     
paper here or it could have been something it ran across on social media as well anyways this is a paper that     
1:43:36     
came out this week on the archive it uses Doom so we we all saw it yeah yeah     
1:43:43     
so this is uh you know so this is a diffusion model via video games as World     
1:43:48     
models so this has World models in it diffusion models and which we will talk     
1:43:54     
about more in the coming meetings because I've been uh you know our upcoming paper on um the aate regulator     
1:44:02     
theorem talks about diffusion models a lot and there's a lot of really good interesting work on diffusion models     
1:44:08     
coming out plus I've been doing a deep dive on anti- diffusion models and it'll     
1:44:13     
be interesting to talk about more in the coming weeks but anyways this is an upand cominging area of machine learning     
1:44:20     
what they're doing here is they're using video games basically uh where they're     
1:44:25     
looking at uh doom and they're building these World models which are these     
1:44:31     
models uh you know where you build representations of as much of the world as you can and provide it to the model     
1:44:39     
so that's what they're doing uh they have a site game j. github.io that's I guess their open source repository for     
1:44:45     
this so this is a place where you you know you can kind of actually get the code to implement this any case what     
1:44:53     
they're so let's go through the abstract and read this is I think from Google especially Deep Mind and um so let's go     
1:45:01     
through the abstract and see what they're doing so they are using Doom here uh and these are screenshots from     
1:45:07     
Doom and they kind of have this uh World model of Doom I guess and they're able     
1:45:13     
to get like these representations so the AI can look and you know navigate the     
1:45:19     
space so it's a nice way to like kind of encapsulate a world World model because you have a finite world in the game you     
1:45:26     
have these different scenes you have these different moves that you can make and I think we talked about this with     
1:45:32     
respect to um like maybe some of the sequential models that we've talked about or some of the large language     
1:45:38     
modeling that we've talked about where they're representing like spatial cognition is like the sequence of events     
1:45:44     
that you do so it very much relates to some of those papers as well okay so the abstract reads we     
1:45:52     
present game and gen the first game engine powered entirely by a neural model that enables real-time interaction     
1:45:59     
with a complex environment over long trajectories at high quality so this is this game and gen model uh it's a neurom     
1:46:07     
model that enables real-time interaction this complex environment is this game here that they're playing there're     
1:46:13     
showing different screenshots of this firstperson shooter and you're going through the game it's again a human     
1:46:20     
player playing Doom a 20 frame per second this is what's being uh the model     
1:46:25     
is being trained on and you have this you know these long trajectories of action     
1:46:32     
sequences game and gen can interactively simulate the classic game Doom that over     
1:46:37     
20 frames per second on a single TPU so this is game and gen being able to simulate game playay in Doom like maybe     
1:46:45     
like a human would play and you know it doesn't take maybe like a human would plane it     
1:46:51     
doesn't lag and Andy to make decisions it can just you know the the action can     
1:46:56     
flow like a human player with play uh next frame prediction achieves a     
1:47:02     
PN psnr of 29.4 this is a metric that they talk about in the paper comparable     
1:47:08     
to lossi jpic compression so this is something that is not um you know out of     
1:47:13     
the realm of like you know it's not computationally expensive necessary uh human Raiders are only     
1:47:20     
slightly better than random chance at distinguishing short clips of the game from clips of the simulation so this is     
1:47:26     
where you know you ask humans can you distinguish these game the game play     
1:47:32     
basically that the simulation is doing and the game play that the human is doing if I were to show you clips of the     
1:47:38     
games would you know that a human was playing it or the AI basically they do this rating they find that it's just a     
1:47:45     
little bit more likely that you would detect an AI sequence from a a human PL     
1:47:51     
sequence so that's pretty good uh game and gen is trained in two phases the first is that an RL agent learns to play     
1:47:58     
the game and the training sessions are reported so there's reinforcement learning agent that plays the game the     
1:48:04     
training sessions are recorded and then the human Raider uh you know judges whether that was an AI or whether that     
1:48:10     
was like a human uh you can also get this world mod extract this world model     
1:48:16     
uh and and you know examples of the RL agent plane so that's the first stage of     
1:48:23     
training is that the RL agent learns to play this game and the training sessions are recorded then a diffusion model is     
1:48:29     
used independently of the RL agent to produce the next frame and this is conditioned on the sequence of past     
1:48:35     
frames and actions so we take that recording we basically condition the diffusion model to you know give it     
1:48:43     
information about that world and then train it to produce the next frame so there's there are two stages there's an     
1:48:49     
RL agent training stage and then there's the diffusion model that's predicting the next stage and the thing about     
1:48:57     
diffusion models is that diffusion models are basically trying to uh     
1:49:02     
recover images or recover things that it's been trained on and tries to     
1:49:08     
predict what that looks like so for example a classic diffusion model example is where you have like a set of     
1:49:14     
pictures and you might noise them with different types of Gyan noise and if you     
1:49:19     
keep noising with Gyan noise the images become become indistinguishable from the background ones so what you want the     
1:49:26     
algorithm to do is you want it to get like basically the the uh plain images     
1:49:32     
and then train the model on Progressive or Progressive noising of these models     
1:49:38     
of these images and so if you have if the model has all that information a diffusion model can basically predict     
1:49:45     
how the noise sort of obscures the image and then it can recover the original     
1:49:51     
image so a diffusion model is basically uh you know working from sort of this     
1:49:56     
noise as the mask and then you know it it can recover an image from the mask     
1:50:02     
another way to think about that is that the model hasn't seen certain things in the world but it's seen other things so     
1:50:09     
it sees these images of the game and then it can you know given like discrete     
1:50:14     
images that are separated uh in terms of action and gameplay it can given the     
1:50:20     
full range of states of gameplay it can recover what the next stage should be because it's basically recovering that     
1:50:27     
from noise the noise being the inability to observe those intermediate     
1:50:33     
States so that's what they're using they're using this AR oil agent this diffusion model OKAY conditioning     
1:50:40     
augmentations enable stable autor regressive generation over long trajectories so they can generate these     
1:50:47     
uh gameplay trajectories and using this type of approach so so they talk about     
1:50:54     
computer games and how uh you know it's centered around the following game Loop     
1:50:59     
you gather user inputs so there's a user that does something the game state is updated so if you move left the game     
1:51:07     
like the the scene will rotate left and you'll go down that path so the user gives the input to rotate left the game     
1:51:15     
State shifts to the left and then continues in that direction and then all of that action has to be rendered to the     
1:51:22     
screen so this these images are rendered by the game engine and but this all has to be     
1:51:28     
seamless it can't just have a lot of wag in it it can't have a lot of noise it has to be seamless and for the     
1:51:35     
experience to be good this game Loop running at a high frame rate creates the illusion of an interactive virtual world     
1:51:41     
for the player such game Loops are classically run on standard computers and while there have been many amazing     
1:51:48     
attempts at running games on bespoke Hardware such as Doom uh being run on kitchen appliances such     
1:51:55     
as a toaster and a microwave a treadmill a camera and iPod I guess that didn't     
1:52:01     
mean is that Doom is like you can play this game on devices that have a really     
1:52:06     
low amount of memory um was I was watching a video     
1:52:12     
this week actually on Doom uh someone trying to take doom and make it into a nonan game or something like that is     
1:52:18     
interesting stuff but basically Doom is um you know there's this ability to take     
1:52:25     
doom and running on on different types of devices uh and you can also play Doom     
1:52:31     
within the game of Minecraft so I'm not really sure like uh this so this is from     
1:52:36     
our Reddit post here it runs Doom so there are a lot of things that run Doom that aren't like U you know the best     
1:52:43     
hardware you can think of it's just kind of like hard random Hardware like my microwave can run Doom my camera can run     
1:52:50     
Doom my iPod can run Doom things you would think that could run Doom okay but in all these cases the hardware is still     
1:52:56     
emulating the manually written game software as is so you can run Doom as is in a lot of different contexts and so     
1:53:03     
this is their point here so what that means is it's easy to break down the game it's easy to build a world model     
1:53:10     
because there's basically a world being represented here but it doesn't you know it apparently doesn't require like a lot     
1:53:17     
of computational overhead to simulate it so that's it okay so uh furthermore     
1:53:25     
while vastly different game engines exist the game State updates and rendering logic in all our composed of     
1:53:31     
sets of manual rules programmed or configured by hand okay so in recent years generative     
1:53:37     
models have made significant progress in producing images and videos conditioned in multimodal inputs such as texture     
1:53:44     
images at the Forefront of this wave the fusion models become the de facto standard media so this is where you know     
1:53:52     
uh gen diffusion models are a sort of a generative model that's sort of the main     
1:53:58     
the new uh sort of uh uh model dour basically so it it actually turns out     
1:54:05     
the diffusion models because they're based on physics and and a lot of the diffusion models in physics and a lot of     
1:54:11     
the things we're doing in in like computational simulation they actually make for very uh diverse versatile     
1:54:19     
models so you know we can use diffusion models in number of ways um that you     
1:54:25     
know actually enable a whole new set of uh you know this is why I talked about     
1:54:31     
it in the ever regulator theorem paper because it opens up a lot of avenues     
1:54:36     
between say like machine learning and say physics or uh theoretical computer     
1:54:43     
science uh at a glance simulating interactive worlds of video games May see may seem similar to video generation     
1:54:51     
so uh platforms like Sora stable diffusion Deli are all doing image     
1:54:56     
generation they're all doing these generative models images and video and     
1:55:01     
so you know we think about the way that these models work with video generation     
1:55:06     
they need to be very large to get like good videos and video generation but and     
1:55:13     
so we might think that we need this for video games as well but we actually don't need that because as it turns out     
1:55:19     
we have uh this actually we don't need as much computational power for video     
1:55:25     
video game generation or this interactive World simulation so in that sense it's a lot more compact than video     
1:55:32     
generation so um interactive World simulation is more than just very fast     
1:55:38     
video generation the requirement to condition on a stream of input actions that is only available throughout the     
1:55:44     
generation breaks some assumptions on existing diffusion model architectures notably it requires generating frames     
1:55:51     
autor regressively which tends to be unstable and leads to sampling Divergence so this is where you     
1:55:58     
know uh we need actually different requirements from video generation so to     
1:56:03     
condition on a stream of input actions we can only uh we have to it sort of     
1:56:08     
breaks some assumptions of diffusion model architectures that currently exist so a lot of the diffusion architectures     
1:56:14     
that we use for Sora and stable diffusion and Del can't really be used here because they do break some of these     
1:56:20     
assumptions so it requires generating frames autor regressively which tends to be unstable and this is another point in     
1:56:27     
the ever good regulator theorem uh analogy to uh diffusion models is that     
1:56:33     
you're you know to make predictions in Time series which is what you're doing here you need to have some sort of Auto     
1:56:41     
regressive model in any case I'm getting too far into the weeds of something we're not looking at directly so I'm not     
1:56:47     
going to spend time on that but they do talk about world models here several     
1:56:53     
important works and they talk about hmid Huber from 2018 Kim from 2020 and Bruce     
1:56:59     
from 2024 uh they where they talk about uh     
1:57:04     
generating World models from video games so in especially in Han Schmid Huber they're simulating an interactive car     
1:57:11     
racing game and a video game uh environment uh with their their sort of     
1:57:16     
training a model on that game and then they're reproducing the game um in different ways     
1:57:23     
so you know a lot of this work on world models is focused on interactive video     
1:57:28     
games nevertheless most of these approaches are limited in respect to the complexity of the simulated games     
1:57:34     
simulation speed stability over long time periods and visual quality so we     
1:57:40     
might ask can a neural model running in real time simulate a complex game high     
1:57:46     
quality and so in this work they demonstrate the answer is yes so back here I made a statement that seemed like     
1:57:52     
it was contradictory which is that you know interactive world uh interactive video games uh and video generation are     
1:58:00     
similar but interactive World simulation requires something else something more apparently because it's not just uh very     
1:58:09     
fast video generation you need this autor regressive component and so down here you know that that may suggest that     
1:58:15     
we need a uh even better model than the standard diffusion model but another way     
1:58:21     
to do this is to actually pick a game that's very Compact and so that's what     
1:58:26     
we're doing doing with doom and so they show that a complex video game the     
1:58:31     
iconic game Doom can be run on an Neal Network they're using a Model A version     
1:58:37     
of the stable diffusion 1.4 model uh which is from Rach 2022 they're do     
1:58:44     
running this model in real time they're achieving a visual quality comparable to that of the original game well not an     
1:58:51     
exact simulation the neurom model is able to perform complex game State updates such as telling health and ammo     
1:58:59     
attacking enemies damaging objects opening doors and persist uh throughout the game State     
1:59:05     
over long trajectory so you can do all these things these interactions with the game the game can be rendered uh based     
1:59:11     
on those decisions and uh uh things that are going on in the game and then these     
1:59:17     
can persist over long trajectories so that's what they're doing with this gameing gen platform     
1:59:23     
and so game and gen itself answers one of the important questions on the road towards a new paradigm for game engines     
1:59:29     
one more games are automatically generated similarly images and video are generated by neurom models uh key     
1:59:36     
questions are remain such as how these neural game engines would be trained and how games would be effectively created     
1:59:42     
in the first place including how to vest leverage human inputs we are nevertheless extremely excited for the     
1:59:48     
possibilities of this new paradigm so this is kind of showing Doom in terms of     
1:59:54     
what they're doing so in a world model this is the basically a world model of the game so what they're doing is     
1:59:59     
they're using a methodology similar to h m Huber they're building this world     
2:00:04     
model of the game and they're they're recovering the the different uh components of the game through this     
2:00:11     
world model the second one is this game Gan so they're using a a generative     
2:00:16     
adversarial Network to model the game and which is called game Gan and they're actually able to reconstruct the game a     
2:00:23     
little bit better but it's still blurry if you look at the hanm Huber paper on world models they recover components of     
2:00:30     
the game but it's blurry and it's because you know it's it's kind of picking up on some of the features but     
2:00:36     
it's not doing it the way they're doing it here which is on the right and that's actually recovering the game fully and     
2:00:42     
of course you pick a game that's you know uh you know that's that's amenable to this but you also build the way uh     
2:00:50     
use the methods that they're using here so this is uh their their and they can     
2:00:55     
show this clear Improvement in Doom over the other methods so they give their methods here     
2:01:02     
uh they have this generative model training basically uh they have the frames and the actions the frames are in     
2:01:08     
blue the actions are in yellow this goes to previous actions uh so the current actions go to     
2:01:15     
the previous actions they have this um reinforcement learning agent that uh     
2:01:22     
observes the game environment observes things are rewarded in the game environment and then takes a     
2:01:27     
corresponding action and then during the training of the RL agent the episodes are stored as these frames and actions     
2:01:35     
the actions then go towards these they they're compared with the previous actions and the current action so you     
2:01:42     
have the previous actions the store of those and the current action a n minus one and then that leads us to build an     
2:01:49     
action in betting and this is now part part of the generative model and training the generative this action embedding then     
2:01:56     
tells basically the game all the possible actions that can be taken in the game so you go through this RL agent     
2:02:03     
the filter of this RL agent these it throughout the training of the RL agent you get these episodes that are stored     
2:02:09     
you get these frames and actions the actions are stored into this action embedding and then the frames themselves     
2:02:15     
are encoded to latence which allow you to predict the next frame from the     
2:02:20     
current action and the available frames so you have previous frames the next     
2:02:26     
frame that's encoded to weight that's then goes into this denoising network and the denoising network remember it's     
2:02:33     
this uh uh diffusion model so you're recovering um a signal from noise you're     
2:02:40     
pulling the signal out of a bunch of noise the noise being everything in the action embedding and the weight and     
2:02:47     
you're pulling out the current um frame that's predicted with some diffusion     
2:02:52     
loss that goes back to the weight and is kind of improved upon as the model is     
2:02:58     
trained so that's how gameing gen works it uses the reinforcement learning agent     
2:03:04     
the uh the the diffusion model and it puts those together in a way that is     
2:03:10     
improves upon the world model and a generative adversarial Network and even     
2:03:15     
like a standard diffusion model okay so that's all I think for     
2:03:21     
that uh paper um there's a lot more technical detail I'm not going to get into but I think that's a good kind of     
2:03:27     
overview of things and so I see Trevor has his hand raised and Morgan has his hand raised so let's I was pointing out     
2:03:34     
Trevor okay um I was just curious the actions     
2:03:39     
were were the actions predefined in that paper or did they like do Discovery and like I'm curious how combinations of     
2:03:45     
actions were happened and all that well way in in an interactive video game the actions are just what the agent will     
2:03:51     
take so like in a if a human plays a game you know the human will like shoot     
2:03:57     
at a Target or they'll be rewarded with points if they pick the right target uh     
2:04:02     
so those things are those can be learned by the RL agent or in the human case it can be learned but you know there's this     
2:04:10     
uh sort of directed towards things that make sense you know like you you     
2:04:16     
maximize your reward in the game environment you navigate towards different parts of the game world and     
2:04:23     
all those things are stored in the action latens so the actions are actually generated by playing the game     
2:04:29     
itself could be the ARL agent playing the game could be human playing and those seem to match well that's what the     
2:04:36     
paper said and so that's where you're learning your actions they're not just generated at random although it would be     
2:04:41     
interesting if they did do a randomization to see what that would look like interesting so I'm assuming there's     
2:04:50     
still some like base level actions like you kind of at the beginning of the paper you like you know go left go right     
2:04:58     
type of thing right and then it just builds up into this late thing okay yeah yeah the also     
2:05:06     
the thing is is that you're building up on your previous actions so if you go left you're going to have a certain part     
2:05:11     
of the world that you're exploring if you go right there's another part of the world you're exploring if you play it multiple times you can explore the world     
2:05:18     
more and more so you get a better handle of the world if you you've ever played a video game you know where you have to     
2:05:25     
play like I don't know for three or four months to really learn it that's that's     
2:05:30     
what's going on is you're learning these different strategies by exploring the game World exploring different things     
2:05:36     
that you do and then kind of getting a a sense in your head of how to play and     
2:05:41     
then eventually you win because you or you get really good because you know that environment intimately and you can     
2:05:48     
navigate it uh pretty easily and then choose the actions that are the best in     
2:05:54     
that situation yeah it makes sense I guess one of the things I'm just uh that first     
2:06:00     
comes to mind is um a few years ago at some nips um     
2:06:06     
contests they were kind of there there's like a text based game i' have to look it up I can't remember meta really loves     
2:06:13     
this thing and um and like the winning uh solution was like a     
2:06:19     
handed hierarchical strategy and I'd just be curious how the     
2:06:26     
like a world model like this would hold up to something like that because it it seems like there's this interplay     
2:06:32     
between this world model being dependent on how it was trained and so um yeah     
2:06:38     
just just just curiosity yeah yeah well there's this whole problem of what world models are     
2:06:46     
and so the whole idea of a world model is that you can train us a you can train a model but it can only do things on     
2:06:53     
what it sees so like if it it's seen something before it can like classify it     
2:06:58     
if it hasn't seen something before it either has to generalize from the existing data or you're out of love it     
2:07:06     
doesn't you know misclassifies things and so people come up with the world model as a way to sort of say okay uh we     
2:07:13     
can just build a representation of the world so instead of training it on like letters and numbers we can do that but     
2:07:20     
we can also provide the cont context of the entire language and that' be a world model of a language or something like     
2:07:26     
that and then the game it would be like I can just simply train it on playing the game which would be you know just it     
2:07:33     
would know what it sees until you you know you'd have to provide it with every possible scenario again and again um to     
2:07:42     
get to get you know but you can also just build a world model which doesn't require explicit game sequences but just     
2:07:50     
requires like every scene in the game to be there and you know so you have this     
2:07:56     
model of the world and so if you train the model it has that information but it can put it     
2:08:02     
in a context which is the entire world and so that's what people and this is an area that's not you know been fully     
2:08:09     
explored it's kind of like you know people have introduced papers on it but it's it's one of these things that     
2:08:15     
people haven't really refined as much as like some of the training uh you know like training an RL     
2:08:22     
model we know how to do that a lot of people have written a lot of papers on this but World models aren't that well     
2:08:28     
studied like we've had a handful of papers on them so relatively speaking so     
2:08:34     
it's it's a it's an interesting approach and it's definitely one that overcomes     
2:08:39     
that problem of generalization in other words I you know if I generalize and taking you know the     
2:08:46     
model is basically taking a leap of faith in the sense that it doesn't know if it's the right answer answer it's     
2:08:52     
just kind of saying this is similar to this thing so that's the answer and it may be right and it may be wrong error     
2:08:57     
rate may be very high so that's bad and World model at least the model can     
2:09:02     
compare it to Something in the world models oh yeah that's a feature that should be in the world and so would be     
2:09:09     
you know better suited for     
2:09:15     
it yeah just you know this is somewhat just uh you know my arm share uh     
2:09:21     
ignorance here but it seems like um for something like this if you're trying to like model the the real world     
2:09:29     
you would want some sort of easy way to uh exchange between the world model and     
2:09:36     
the simulator so um like whether like was encoding objects that you could then     
2:09:42     
throw in a simulator because there seems to be like this dependence on um simulation to teach the world model and     
2:09:49     
so yeah I don't know much about this world but I don't know if there are approaches that     
2:09:56     
enable that type of thing yeah so let me go to the paper I want to show something     
2:10:03     
here so they talked about world models up here somewhere     
2:10:09     
um oh yeah H Schmid hoer 2018 Kim 2020 and Bruce 24 so if we go to those     
2:10:18     
citations um the first one yeah so Bruce is let's see if they     
2:10:26     
have it here how do they have this organized um this is H Schmid Huber you're not     
2:10:34     
sharing your screen oh thank you share my screen     
2:10:42     
again all right so the first one is hm hu this is World models this is uh     
2:10:48     
archive paper but they don't they don't mention it here uh but that that's the one I think the     
2:10:53     
first one that was based on the racing video game um and then I said what Kim     
2:11:00     
and what was the other one here so this is the Kim Paper I believe     
2:11:08     
it says uh learning to simulate Dynamic environments with game Gan so this is the game Gan paper where they use a     
2:11:15     
generative adversarial Network this is at the it e conference on computer vision and pattern recognition     
2:11:22     
cbpr so what was the other one did you remember can you say Bruce Bruce yeah     
2:11:29     
see if I can find that maybe I don't know how they have it     
2:11:34     
organized I think it's here it is Jake Bruce Michael Dennis Ashley     
2:11:40     
Genie Genie yes Jeff cloon is on this did see a whole bunch of people Genie     
2:11:47     
generative interactive environment so this is from 2021 this is also an archiv     
2:11:52     
paper and you know again they're using these generative uh models there's this     
2:11:58     
difference between like maybe video generation and interactive environments video generation just needs to like put     
2:12:05     
together a sequence of things the interactive environment needs to take inputs from the player and put it you     
2:12:13     
know use it to guide these worlds so the player determines how the world is     
2:12:19     
explored what the sequence should look like and that's an auto regressive     
2:12:24     
process and yeah so there are a lot of interesting statistical properties here     
2:12:30     
you know that that differ between the two um and yeah they have a lot of     
2:12:35     
interesting stuff in this um paper they do this autor regressive     
2:12:42     
evaluation um and context length noise     
2:12:47     
augmentation so it's pretty cool um yeah any other comments or questions     
2:12:54     
about this paper well it's um as as usual I'm just     
2:13:01     
upset I I didn't do more background on it before you know because it's it would     
2:13:07     
be good to you know one put it like you said put it in context of the not     
2:13:14     
necessarily H maneuver but but the um the the     
2:13:22     
specifically some of the world model papers that are in the RFP oh yeah that     
2:13:30     
like saffron's RFB right like like some of his links are really interesting     
2:13:36     
because again they're they're all kind of focused or certainly like the the     
2:13:43     
progression of papers um is is focused on kind of having     
2:13:52     
more and more foresight I mean like like being     
2:13:57     
able to kind of you know have a have a better memory and and kind of make     
2:14:05     
better plans in the future right you know right and and and so you     
2:14:11     
see at least again in some of the staff papers but like specifically some of     
2:14:16     
those references sorry Trevor uh um have them off the 10 my     
2:14:23     
time but um yeah just just you know because again     
2:14:31     
like it's so much of this you know kind     
2:14:36     
of like subtle and only comes out from the specific evaluations that you're     
2:14:42     
making you know or you know like the the metric you're tracking things like that     
2:14:47     
like like at least for me to get a intuitive idea of of what what these     
2:14:54     
design choices are are getting you yeah you know um     
2:15:00     
um anyway that's that's yeah again that's more just there a long way way of     
2:15:07     
me saying like I wish i' done more background I think the use of Doom is     
2:15:12     
really interesting here because it's like Doom is like something you can program onto some like very trivial     
2:15:19     
thing piece of hardware and then means that it's you know something that has a structure that's unique to this problem     
2:15:25     
I guess or can show this problem very easily it's kind of like the celegans of like computational models that use well     
2:15:33     
I mean certainly the the the video the like video generation versus you know     
2:15:39     
video generate like yeah video generation as World models yeah like     
2:15:45     
like you know like like that was an interesting thing remember when um     
2:15:51     
I can't even remember you know it tells you tells you how much hype there is in this area I can't even remember the 3D     
2:16:00     
video generation tool like from open AI or somebody you     
2:16:07     
know like remember that they you make oh Sora yeah yeah with Will Smith eating spaghetti yeah yeah you know and and     
2:16:16     
it's a yeah like like whether that meant that     
2:16:22     
that world models were solved or something like that you know like you had world like like like again like it's     
2:16:29     
it's not it's not yeah yeah they didn't really solve it yeah it's definitely     
2:16:37     
there's definitely more yeah you know as well as it just being um the     
2:16:43     
[Music] vocabul more specific you know in terms     
2:16:49     
of of what RL people are going for with these with these World models you know yeah um and     
2:16:58     
and especially with a you know it's about it's kind     
2:17:04     
of and you know I I wasn't sure if if Trevor was thinking about this but you     
2:17:09     
know again like stringing actions together is the kind of thing where you     
2:17:15     
know you start to look for like like tool use right right like like tool use     
2:17:20     
for require memory and and and     
2:17:29     
um yeah like being able kind of concepts are     
2:17:38     
representations you know potentially yeah yeah I think there's something     
2:17:43     
about like like the sequ sequential     
2:17:48     
representations because it seems like that's a people are kind of really interested in right now and how those     
2:17:54     
can be handled and how you can extract those and learn and there are a lot of statistical properties of sequential you     
2:18:01     
know sequences that are different than like just kind of putting in independently distributed data and you     
2:18:07     
know I don't know what the connection is there um but yeah something worth     
2:18:14     
thinking yeah Lon seems to really be emphasizing this he talks about task     
2:18:20     
planning and all that I guess that's what a lot of the labs are focusing on these days yeah yeah yeah all     
2:18:28     
right I mean yeah the ones that aren't focused on the     
2:18:33     
language models yeah all right that sounds good well     
2:18:40     
let's let's call it a day um thanks for attending um and Trevor yeah you might     
2:18:46     
find um Lucas's talk that he gave earlier in the meeting interest you'll see it on the recording is on lipid     
2:18:54     
metabolism genes and proteins and celegans and they were doing a lot of interesting work with that     
2:19:02     
so check out the the um new build a cell seminar oh yeah okay     
2:19:10     
they have a new one yeah yeah it's a good cytoplasm and um and and it's it's     
2:19:16     
somebody from um ski University Utah k h     
2:19:22     
yeah I wonder who it is I'll see if I know yeah yeah yeah it's good stuff yeah     
2:19:27     
all right yeah thanks thanks so much see take take care bye
