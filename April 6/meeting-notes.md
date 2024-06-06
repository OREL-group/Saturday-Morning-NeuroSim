## Meeting Recording

[YouTube link](https://youtu.be/ZuT4iMcxig0)

## Mastodon thread

[link](https://neuromatch.social/@OREL/112227064824231087)

## NOTES
More direct path —> conversation with Avery. Synthetic data, Plot Twisters.

MESA — setting up, sugar and spice trader models. Clean coding, good practice.

Ajad Ismail: active matter, systems biology.

Paola DiMaio: model cards for ML, natural language for machine models. ML for model cards, LLMS (use natural language interface).

* queries rely upon data structures.

Moonshot: intelligence definition — path to AGI, Neural MMO. Moonshot: need to have “a moon”, “way to get there” defined, otherwise not useful.

* developing an interactive XR prototype for C. elegans connectome exploration.

* VR fully immersive environment.

_C. elegans_ —model organism — used to investigate disease, gene function.

* blender, Unity modeling:

* blender —> Unity —> Paraview —> SDKs —> A-Frame —> ABM-U.


ABM-U (Unity: https://github.com/cheliotk/unity_abm_framework

* components: 1) interactive 3-D model, 2) deployment on a widely-available XR platform, 3) open-source application.


SMN — #braitenberg-vehicles. ROS — Robotics Developer Masterclass.

* learning structured world models from and for physical interactions.

Michigan Mars rover team. DARPA challenge (robotics club). From grand challenge to undergrad project.

* multi-agents: ABMs, Deep RL, game theory, emergent complexity.

* can LLMs reason and plan? LLMS as agents.


Agent Zero: each agent has an interior model (cognitive,  intelligent).

* SFI course — ABMs. Interesting confluence towards ABMs.

* area of computer simulation with a theoretical impact — why the toy models? Synthetic data — cannot collect data easily.

* AI curves: Mass General. Future of AI in medicine. Clinical AI — rehab medicine.

* priorities, not theory. 

* incentives for investing in AI. Return on investment (ROI).

* generative AI —> visualize development of diseases.


Dan Elton — Microsoft New England — future forecasting.

Mind First foundation. Psychohistory. Control over Ai technology.

* frontier mapping attempts. Destination spaces (trajectory approach).

* interpretational tools, long-term vision. Forced, voluntary tasks — brain activation differences.

* cell types question — Allen Institute Atlas (Voytek group, cell types given activity).

* naturalistic behavior,, given the state of the organism.


Open-source LLMs. BrainGPT — using LLM, foundation model, Neuroscience data.

* discovery of papers, the “literature”.


MESA: Python framework for ABMs.

* Padraig — OpenBrain —> runs in the browser. NeuroFedora.

* micro-tension: collecting data, developmental modeling (generative aspects). ICDL conference.

* data ethics, model things that are hard to collect.

* useful simulations — how to create, how to inform collective, emergent phenomena. 


Synthetic Data: fMRI useful for testing segmentation tools.

* Bzdok — diversity-first model of Psychiatric Neuroimaging.

* Cellular Potts Models (Glazier) —> Spatial-omics. 

* morpheus group (Dresden) — computational epidemiology. Reduced-order model — PDE discussion. Few things you are actually measuring.

* https://en.wikipedia.org/wiki/Model_order_reduction


Visualizable table (3k x 1k of cell type information data).

* we have the data, not the synthesis.

* need a superhuman aspect of organization (data located in multiple silos).

* what drove responses in a structural way? Snapshots don’t get at dynamism. EMBL, bio models.


paola
paola says:
Hay, just checking out what is going here, thanks for invite 
9:22

Jes (OREL)
Jes (OREL) says:
Hello and welcome. If you want to introduce yourself here in the chat now you can  - and then via audio if you'd like to shortly 
Jes (OREL) says:
multiagent? 
9:24

paola
paola says:
Thanks Jes, I recently joined, and have been following AI and intelligent systems space for quite some time 
paola says:
do ont have much b/w for audio but I could try later 
9:25

Jes (OREL)
Jes (OREL) says:
oh I remember you joining the slack a little bit ago now. welcome aboard . 
9:27

paola
paola says:
not sure you folks are but this looks INTELLIGENT SYSTEM 
9:27

Ajad Ismail
Ajad Ismail says:
Hello, I am ready for the presentation so please let me know when to start 
9:28

paola
paola says:
sorry I got disconnected 
paola says:
missed out on some talk 
9:31

Jes (OREL)
Jes (OREL) says:
👍 
9:36

paola
paola says:
ah 
paola says:
what does SMN stand for 
paola says:
since you are up for talks, here a very short talk I am presenging virtually on Monday, you can watch it in your own time, not sure if related to this group's mission tho. 
https://www.awesomescreenshot.com/video/26488353?key=e15c71a8579d68a83853fcc5dba557cc
 
9:44

Adama
Adama says:
Hi everyone! 
9:46

paola
paola says:
Hello Adama 
9:46

Sarrah Bastawala
Sarrah Bastawala says:
Hello everyone, apologies for joining late 
9:48

paola
paola says:
Hello Sarrah 
9:49

Adama
Adama says:
Should I present my project for the next time ? 
Adama says:
👏 
Adama says:
👏 
9:50

me says:
browser.openworm.org
 
9:52

Jes (OREL)
Jes (OREL) says:
Looks good and good luck for this summer! 
9:53

Ajad Ismail
Ajad Ismail says:
thank you 😃 
9:53

paola
paola says:
ah, then my talk may be relevant here, I have low b/w 
paola says:
Thank you Ajad 
paola says:
Thanks Bradley,  just over 5 minuts 
paola says:
thanks, now I understand how we fit  in 
paola says:
starting to figure 
10:00

Himanshu
Himanshu says:
https://github.com/eugeneyan/open-llms
 
10:01

Sarrah Bastawala
Sarrah Bastawala says:
Looks helpful @Himanshu 
10:02

paola
paola says:
nice, also we need to figure if they run from the browser 
10:02

Jes (OREL)
Jes (OREL) says:
https://braingpt.org/
 
10:03

paola
paola says:
brain GPT!!! 
10:04

Himanshu
Himanshu says:
BrainGPT: Large language models surpass human experts in
 predicting neuroscience results
https://arxiv.org/abs/2403.03230
 
10:04

Morgan Hough
Morgan Hough says:
https://youtu.be/sDt4-Q_jz7g?si=UXp5K6fxSkfXhmJX
 
10:07

paola
paola says:
This is so leading edge stuff, thanks 
10:10

Jes (OREL)
Jes (OREL) says:
👍 
Jes (OREL) says:
👍 
10:23

paola
paola says:
can I suggest we paste the intersting  links in the slack, otherwise the pointers to valuable resources may be lost when the chat closes 
10:24

Morgan Hough
Morgan Hough says:
Yes good idea 
10:24

Jes (OREL)
Jes (OREL) says:
yes, that's usually what we do. Feel free to share links in slack 
10:24

paola
paola says:
Thank you Bradley!! 
paola says:
yes 
paola says:
great to know thatnks 
paola says:
what is Mesa @Jes? 
paola says:
thank ou, gotcha 
10:30

Jes (OREL)
Jes (OREL) says:
👍 
Jes (OREL) says:
Should we have time this week, I may talk about: AI Cures 2024, "future of humanity" AI Futures event, Anthropic & future job postings <> data ethics . We may not have time for this directly, and I want to write a bit more about all of these things and present more formally on them ahead . 
10:37

paola
paola says:
Thank you MOrgan, nice to meet you at the intersection! just looking you people p, lets talk 
10:37

Ajad Ismail
Ajad Ismail says:
👍 
10:39

paola
paola says:
👍  Jes (not sure how to give thumbs up directly under yr msg) 
paola says:
@morgan yes it is important imho to keep in mind that we are trying to answer urgent questions, absolutely, get to the gist and do not get lost in the complexity 
10:41

Jes (OREL)
Jes (OREL) says:
👍 
10:45

paola
paola says:
yup 
paola says:
because human life is relatively short and finite, people do ont tent to have long term vision 
11:02

Ajad Ismail
Ajad Ismail says:
I have to leave unfortunately, have a great day everyone 👋 
11:03

Sarrah Bastawala
Sarrah Bastawala says:
Will have to leave, great meet, will definitely look more into the agent-based model with data paper looks interesting! 
11:04

Adama
Adama says:
Can you show again the title of the article ? 
Adama says:
Thank you ! 
11:08

paola
paola says:
👍 
paola says:
Thanks Bradlley, so what do we learn from the high density molecular data, about the diversity of the types of molecules? 
paola says:
@morgan so important understanding the chemistry of consciousness, if we could get into that 
paola says:
aw @brad I understand, thank you 
paola says:
yes, well, they call responsive a state of being conscious vs being unconscious (unresponsive) to the point about anestetized /asleep specimen, 
11:18
P
paola
paola says:
so sorry I fell out 
11:27

Adama
Adama says:
Thank you for this session, I have to go now but see you next week probably!  😃 
11:27
P
paola
paola says:
thank you bye 
