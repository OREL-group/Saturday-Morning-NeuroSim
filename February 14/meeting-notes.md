## Meeting Recording

[YouTube link](https://youtu.be/yCxus3Efsk4)

## Mastodon thread

[link](https://neuromatch.social/@OREL/116078223452010240)

## Feature Videos

[Self-organizing Developmental Programs for Sculpting Connectomes](https://youtu.be/gmMp6N3Q2rM)

## NOTES
Agents are good @ building, less @ design.

using agents, what would students want from a website? What adds value?

optogenetics with Dishbrain.

kernel flow, kernel flux. Wearable Squid.

Controlling femtofluctuations.

Data x Direction, future center.


Ekkolapto —> Elan is doing some things.

 Plot Twisters —> May 2024, Oxford —> then hiatus.

DigiNest — digital storytelling.

Avery —> LLM projects, what can you do with these?


GUide to LLMs —> be a reasonable consumer of information.

huge stockpile of discussions.

meetings with Jen. Training, education, consulting, firms.


“Firm of the Brain” for open-source post (or paper).

challenge of LLMs to open-source.

Claude Bots/Open Claude/Open Claw

how do we drive this work forward?

* Jesse does not have a strong take on this.

automate tedium, but need physical media.


Morgan — running models on a laptop. New Year’s Resolutions: immerse yourself and be a user working with a reality that you run up against.

OpenClaw — fork and get started.

Agentic programming. LLMs are like shooting fish in a barrel.

“Shoot fish in a barrel”, “Swimming in a fish bowl”. What is the difference between these two?


Ladyada —> use of OpenClaw. Agentic coding —> where agents share context.

Markdown files for the humans ‘sol.md’ —> tells us how files will be used by the agent.

Bradley Voytek —> LinkedIn —> agentic coding.


Connect to LLM service online. Run service on a Raspberry Pi (via telegram).

living dangerously —> create an OpenClaw that runs the tower.

not enough to ‘ship’ in software.

seem to be hard limits to AI —> business reality.


App developer vs. C++ programming.

OS project, template (agent-based).

“Ask a Cyberneticist” YouTube feeds through Hough and Griffiths.

* presentations, working on both blog post and summaries (guide for AI in the classroom).

## TRANSCRIPT
0:01     
Hello. Hi. How are you? Hi. How are you?     
0:09     
Good. Welcome.     
0:15     
All right. So, um we're doing all right. Yes. All right.     
0:21     
Things are going well. We're doing uh a lot of uh different discussions in the     
0:26     
group. What are our plans for this summer? Probably uh Gox and maybe some other     
0:33     
things. Um our projects are basically the same as     
0:38     
last year, I think. Yeah, I think uh yeah, so we have our     
0:46     
GOC projects and then if anyone wants to do any other projects, you know, they're welcome to do it. Yeah, if you'd like to     
0:53     
continue Sustain Hub, that would be fine. Um, we'll probably have other people interested in open source     
1:00     
sustainability. So, we should look into that and see, you know, what we can do with that.     
1:09     
Um, yeah. And we'll, like I um, yeah, so     
1:14     
we'll continue with our open source our open source meetings in May and we'll     
1:20     
continue those through the summer as well. So, that'll be     
1:25     
um I think a good thing. Maybe we'll try to um you know, maybe work more hands-on     
1:33     
during part of the meetings. I'm not really sure how we'll do it, but Okay.     
1:42     
All right. Yeah. So, welcome. Um and so this week we did uh D.VARM     
1:49     
and that was uh two people presented there on some things. We talked about we     
1:54     
have one person who's doing uh ODEs on a conneto and so you know by extension     
2:01     
temporal networks. Yeah. And then I covered um another paper. So that was     
2:08     
uh really interesting stuff. had a little issue with the audio on the recording, but you know, I'll try to fix     
2:13     
that for next time, of course. Okay, so um that's great. Um     
2:19     
so VD, uh yeah, you had to catch a train, but thanks for uh checking in.     
2:25     
It's always nice to see you and looking forward to the summer.     
2:32     
I haven't been able to make time. Yeah.     
2:40     
Yeah. That's good. And then Morgan, um I don't know, you've     
2:48     
been busy through the last several weeks with different things you've been doing over the week. So,     
2:58     
yeah. Excuse me. Yeah. lots of lots of um event planning     
3:05     
and other yeah and software development you know     
3:12     
so not so much working on the microructural     
3:18     
MRI modeling but um uh but still using still     
3:26     
using agents to construct uh in this case the the new Neuroch website.     
3:34     
So, yeah. Yeah. that we we've finally have a new board     
3:41     
at Neurotech X and um uh so it's it's time to update     
3:50     
the website, make it much more um     
3:57     
make it more functional as a as a resource     
4:02     
than than just a a landing page, you know, at least That's that's the hope.     
4:14     
So a agents are good at constructing through building things. Um     
4:20     
but uh design aesthetic is still something that is uh challenging.     
4:35     
So I shouldn't ask it to design anything. Is that what you're trying? Well, it's like, you know, so so again     
4:44     
it's it's uses um it uses language prompts, right? So     
4:52     
the question is, can you describe what you want?     
4:59     
Yeah. Um and yeah, so I I think it's it's good it's     
5:06     
good to find um examples, you know, like so if you don't have the words um you     
5:14     
know the old a picture is worth a thousand words     
5:19     
um uh that that helps you know but um     
5:28     
but It is also interesting where you see it's like um using Sure sure     
5:37     
using agents uh I see now like a lot of website features     
5:46     
I see is like oh that's why all these websites look like     
5:51     
the they've got the same you know the same aesthetic right it's that that yeah     
5:58     
this is this is something that agents put together. Yeah. And I and I think it is still one of the     
6:04     
like most widely used um when when people say they're using     
6:12     
these to put together software, what they mean is they mean websites, right?     
6:17     
You know, they mean front end stuff. So, um     
6:24     
yeah. Yeah. Um but uh you're right. So still still     
6:32     
trying to think though in terms of just what     
6:39     
yeah what would students want from a website like what um     
6:46     
you know what what services andor resources can we make available that     
6:52     
would actually be um that would add value.     
6:59     
Yeah. Yeah.     
7:08     
But yeah, the um uh I mean it's it's     
7:14     
unfortunate that the the students um the Berkeley students lost their kind of lab     
7:20     
access. Um, but I'm very happy that they're going to make the um the     
7:30     
BART rides uh you know they go they'll go under the tunnel under the bay to     
7:36     
come over and and use our lab. So     
7:42     
the the Wetware team is going to move over to the over to Biopunk to continue the dish     
7:49     
brain kind of work. Um, but they would really like, you know, like if they can     
7:55     
get Dish Brain working again, um, then we'll probably do some some     
8:02     
like they'll probably do some like optogenetics with that. Um, as a, you     
8:10     
know, kind of as a platform, but but this is this is, you know, like     
8:17     
that that would be um that no no better use of the tissue     
8:24     
culture uh at Biopunk than to get them get them     
8:30     
running again. So that that would be awesome and it it'd be really nice. You know I     
8:36     
what I really wanted to have was um you know a couple active neurotchnology     
8:46     
conference. So the the students the students in California are like six of     
8:52     
the five of the UC's plus USC um all collaborate to run a student     
8:58     
conference and uh this year it is hosted by     
9:04     
Berkeley. So I I'm I I am also excited because     
9:09     
it's like it would be really nice for the students to be showing off projects that they're doing at the conference,     
9:16     
you know, just because like like what I'm trying what I want them to show     
9:25     
um show the other the other UC's is like     
9:30     
you can do more than just like an EEG project. Yeah. you know, like like like that.     
9:37     
That to me would be um another big uh     
9:47     
you know, a change in the right direction. Yeah,     
9:52     
that's good. Yeah, sounds like you're making some progress. How did they lose their lab space at     
9:59     
Berkeley? Uh, you know, I think I think the the issue that they have and this is this     
10:05     
is, you know, this is my u     
10:12     
like my concern for trying to do neurobiotech     
10:17     
projects as opposed to neuroch, right? Is that like you know wet lab access at     
10:23     
universities is not some is not a shared facility.     
10:28     
Right. Right. It it it's it's like every wet lab is a     
10:35     
PI's lab. Okay. You know, and so it it's like the big issue is,     
10:43     
you know, who's giving you space? Yeah. And like like what what PI do you know     
10:49     
who's like I've got too much wet laps? Yes. you know, like you know, um,     
10:58     
you know, every every wet lab I know is like got way too many grad students like     
11:06     
working on top of each other, you know. So it's like if you if you think about     
11:14     
that I mean you know like UCSF maybe is like kind of worst case because it's you     
11:22     
know like those kind of like big city labs you know like where     
11:28     
you know square footage is expensive right um uh but     
11:35     
anyway the po point being that um     
11:41     
I think it was one of these things where it was just like you know like sure they     
11:46     
they had a spot for a semester but you know then the PI was just like     
11:53     
hey I you know or the the you know they got new students in they got new grad     
11:59     
students in right and you know they needed the space or they needed the incubator or they     
12:06     
needed the whatever Right. And um and     
12:11     
that's the problem is that like you know you do I mean this this is what I had     
12:19     
been trying to do was just to like make sure we had everything that's in the the     
12:25     
UI uh mind in vitro     
12:30     
projects like like everything described there that's like we would have you know     
12:36     
something dedicated for the students to to to use in our space,     
12:43     
right? And and and then that's that's like now     
12:49     
you can operate freely, you know. Um uh you know but the the problem being     
12:57     
that like if it is you know a 30 minutes train ride away then that makes it     
13:05     
really hard for you to have kind of a around the clock you know e even if     
13:13     
you've got a big student team um that can can do shifts you know what     
13:20     
kind of like around the clock monitoring can you do right and you know that will be effective.     
13:27     
So anyway um yeah so they'll they'll come by come by     
13:33     
and see it. So, I'm hosting at the tower a UC Davis, UC Santa Cruz, UC Berkeley     
13:41     
um uh student mixer or you know like uh     
13:49     
yeah and you know the the Berkeley team will come     
13:54     
up and actually see the the space and you know we can we can try and figure     
13:59     
out the the the logistics for it. So, I'm I'm you know, this is this is this     
14:07     
is exactly what I wanted to buy a plug for. So, this is pretty exciting. Yeah.     
14:14     
Yeah. Yeah. Yeah. I I think I still would like it if     
14:20     
we were actually working on the micro electro array. Um, but a and you know,     
14:27     
like I don't think at this point we're talking about actually using the the the     
14:33     
bio printer. Yeah. Um, but I I'm very tempted to reach out     
14:39     
to Pittsburgh and and and Yeah, actually that's what I should do. I should reach     
14:45     
out to Pittsburgh and both check on the the team that um uh     
14:54     
that taught us the bioprinter conversion, you know, because it's like because that     
15:00     
particular was going to start um neuron neuronal culture um because I'm really     
15:08     
really interested in like have they worked on um the bioreactor itself,     
15:16     
right? So like like you know I think I think these these kids have a they have     
15:23     
a goal of keeping the neurons alive for a month, right? Which is short. Which is     
15:29     
short. I mean it's long but it's short, you know. Um     
15:37     
the the media the media um     
15:42     
uh uh exchange is the is the usual point of failure, right? is     
15:49     
like like while you're doing that is usually when you've you've opened up the     
15:54     
system to contamination and that's that's where they've they've     
16:00     
lost their cultures, right? Um,     
16:06     
so I I'm I'm sure that that Pittsburgh group that that's that, you know, the     
16:13     
bio-engineering group that taught us the conversion, I'm sure build their own     
16:18     
bioreactors for, you know, because they do for every other tissue type, right? So they do for liver cells, kid, you     
16:25     
know, like whatever. Um, anyway, I'm sure there's something to learn there as     
16:31     
well as like it would be really interesting to see if Tracy Cuz Group I     
16:38     
don't know how you say in Chinese like CUi like     
16:44     
Sue. Yeah, I don't know. um uh     
16:51     
her her group I I spoke with one of their postocs and and was um     
16:58     
you know he he who who was just gushing about the 3D 3D neuronal culture because     
17:04     
he was just like like you you know you absolutely will see     
17:11     
remarkable differences to from 2D and in in all the     
17:17     
right directions, all all the all the metrics that you'd care about. It's it's positive.     
17:26     
So, I should I should um I should ask him if there's something that these     
17:31     
these students could do with that because, you know, because his point was     
17:37     
like nobody's doing 3D culture like like you know, so u if if they could do that,     
17:46     
they would all they would like, you know, and keep it alive.     
17:51     
um they would almost guaranteed like have some sort of report from it, you     
17:57     
know, like maybe not a full paper in the sense of, you know, um I don't know if     
18:03     
they've got the time and the, you know, the bandwidth to to to finish that off     
18:09     
without, you know, having students, grad students help them or something like that. But, um that that would be pretty     
18:17     
cool. And um and we've got some great we got some great people at Biopunk right     
18:24     
now who can um who can definitely mentor them on the cell culture techniques and     
18:30     
and other things. Um that's just really exciting. Anyway,     
18:36     
um Jess, I I I went to um Ida's uh um     
18:45     
um Oh, yeah. start up. This is the Yeah. Launch     
18:50     
launch party. Launch party of uh here I've got my merch.     
18:57     
So deve nice.     
19:05     
I I went to a lunch party and I got more than just a t-shirts. I also got a bag um and uh and a lovely     
19:16     
meal. Um but it it was um and and I got     
19:21     
to meet um so it was cool because like she had her     
19:27     
whole engineering team. Uh so by the Bradley, this is um so     
19:33     
they're making a a desktop device. Okay. That looks like um     
19:42     
it looks a little like a Google uh Google Home speaker,     
19:48     
you know, like um and uh but but what this does     
19:55     
is um if you you place it in the center of the room, right? If you've got a     
20:03     
recording device in the room, okay, then this device is setting up an ultrasonic     
20:12     
um uh beam mostly around your recording device.     
20:21     
So that even if you've if you've got you've pressed record,     
20:27     
you know that the microphone will only will pick up like,     
20:33     
you know, will like be totally garbled.     
20:43     
So and and she had some demo units. Um     
20:49     
what a very what a very product for 2026.     
20:55     
Yeah. Yeah. I mean, you know, it was it was not Unfortunately, the the demo     
21:02     
didn't go exactly. I mean, it was funny because it's like like she's built some, you know, she's a physicist. She's she's     
21:10     
built this very sophisticated device. Um but the biggest problem that they had     
21:15     
was just getting uh her Apple laptop to play recordings that they had made.     
21:22     
Like like like it wasn't the part of the demo that failed wasn't the wasn't the     
21:29     
demo but was actually just the presentation. Um,     
21:36     
you know, it was more of a keynote failure than than um     
21:42     
but but the cool thing being that I met the the engineer that really helped um     
21:51     
uh make the initial version. And um and     
21:59     
it's it's super super cool because it's like he he's talking about this in terms     
22:04     
of, you know, how they did the the phased array and things like that. Um,     
22:10     
and then I was just like, "Oh, well, my my only experience is with focused ultrasound, um, you know, transcranial     
22:17     
focused ultrasounds." And he was just like, "No way." And and so like he'd been working as as     
22:25     
uh he he'd been doing brain imaging and and device development for like 10 years     
22:32     
like and he worked he he he started with Ed Bdon you know so he'd been doing     
22:39     
focused ultrasound with Ed Bdon um which is super cool and he had some     
22:44     
interesting stories about their their mouse work um and I didn't even You     
22:50     
know, and this is one of those things where it's just like, you know, of course Ed Bdon's done this, but like I     
22:55     
don't remember it. It's just like, you know, um um but uh but then he     
23:04     
worked at Colonel. So that's the that's the the the the company that I actually     
23:11     
had at the tower for JPM Healthcare. and um     
23:18     
uh and he he had been working on the kernel uh flux. So so when kernel     
23:27     
started they made two systems. So one was the near infrared which they call the kernel flow. The other was called     
23:33     
the Colonel Flux. And the Colonel Flux was a was an optically pumped     
23:40     
magnetometer system. And um like like super cool     
23:46     
nextG stuff like at the time for sure. Um because     
23:54     
you know these OPMs like like yes they allow you to collect     
24:01     
data without having um super cooled, you know, squids.     
24:06     
Um which which saves you like, you know,     
24:12     
instead of having like literally a ton hanging over your     
24:17     
subject, right? Um, you can have something that looks like     
24:24     
more like a like a     
24:29     
a very thin helmet. Um but but you still need this like special     
24:38     
um special kind of metal room, you know, you still need like this this super     
24:45     
shielding because you know phento Tesla fluctuations are are so so hard to uh to     
24:57     
get in any kind of noisefree way. Um,     
25:02     
so you you really can't have any interference. Um, anyway, that that was     
25:08     
that was super fascinating. And then um and then he he totally worked at Nudge.     
25:15     
Um, and so Nudge is the Nudge is the big or the Nudge is like the super     
25:23     
well-funded if if the super wellunded billionaire backed     
25:31     
um group that is doing focused ultrasound     
25:36     
and yeah is where where I was is also a scientific     
25:43     
so that was kind of fun but But I I liked it in terms of just like he's, you     
25:49     
know, when he's not building brain, you know, cool brain devices. Um     
25:57     
u he he's building, you know,     
26:03     
nextgen satellite parts, right? You know, because     
26:10     
so what do you what do you work on? He's like, "Well, I like to work on um um tip of the spear kind of stuff, you know,     
26:17     
and you know, satellites, you know, basically spacecraft is one of those things, you know, like Yeah.     
26:26     
tip of the spear being cutting edge. Cutting edge." Yeah. Cutting edge. Yeah. I mean, tip of the     
26:32     
Yeah. Yeah. I I didn't know whether that meant that he was also working on     
26:38     
military applications like Tip of the spear usually means tip of the spear.     
26:43     
Right. Right. Right. Yeah. Yeah. But like who who's the main     
26:50     
who's the main consumer of this? Well, who's who uses more satellites     
26:55     
than anybody, right? Yeah. Yeah. So, yeah. Like kind of the same thing.     
27:03     
And I met Addie there. Okay. Of course, you know. Um, so, uh,     
27:12     
although that was that was also kind of funny because he was a little a little bit a part of the demo. Um,     
27:18     
and and yeah, and he introduced me to a few     
27:23     
people that are going to come by the tower. So, I still haven't seen him though like like for as long as he's I     
27:30     
think he's been in San Francisco since um     
27:35     
I think the 28th of January, something like that. I know he had something to do in New     
27:40     
York, so I don't know how long. He he he was in New York for the weekend, I think. Um     
27:48     
or, you know, six sixth to the 8th or something like that. But yeah. Yeah.     
27:54     
Anyway, that was um that was last last night's     
28:00     
um the Devalance launch party. Oh, wow. Okay, that sounds great.     
28:05     
Yeah, yeah, yeah. Um they should have done it at the tower.     
28:12     
Yeah, yeah, yeah.     
28:17     
So, Jesse, hello. Oh, yeah. Okay, my mic's here. Hi. Um,     
28:28     
boy. Uh, I feel like I haven't been here     
28:33     
like and usually I've been able I've been coming at the end. It's been a very busy very busy busy busy busy time in a     
28:40     
in a mostly good way. Um, yeah. Um     
28:47     
things things are going it's it's one of those situations where it's     
28:54     
like geez there's a whole lot I could say what is actually good to say right now um     
29:01     
you know on the dr side of things um date and direction is is going     
29:09     
uh letting things wind down on well I guess we're coming to a stopping point     
29:15     
on on sort of the first cohort of things. Um, which many of those students     
29:20     
are in like the UC system, so they're they're in the middle of like winter term. Um, whereas things over here on     
29:28     
the east coast are just getting started. So, I'm kind of I'm playing letting them     
29:33     
kind of finish at a natural pace there. Uh, there's the future centers um in     
29:39     
development is still going on its path. Uh there's a I feel like there's so much     
29:45     
I want to do with coition futures, but I really don't have the time to do it right now. Like embodied intelligence um     
29:51     
is soon. The the conference is soon and there's a lot things that I that I even     
29:56     
could could present there and I don't know if I I might be able to do something small.     
30:02     
Um but there's a lot of you know fun stuff in that space and sort of the you     
30:07     
know echolapto adjacent space. I haven't there hasn't really been a lot of I guess I guess in Echalopto space Elon's     
30:16     
talking more about his stuff and getting some more things for his LLM ideas. I     
30:21     
haven't I haven't really seen all of that yet, but that's cool. Uh I I there's been any like     
30:27     
I don't know. I'm sure there's going to be stuff happening in San Francisco with with Addie and that that crew, but I don't I haven't really heard a lot of     
30:33     
like specific plans about things. Um but sure things will happen there. Uh     
30:42     
um plot twist is actually in a really interesting space. Um because they just     
30:49     
finished I don't even know how much we talked about this recently but they just finished one of their play testing demos for the small houses court which is this     
30:57     
um well it's just a play testing demo. finished the the fellowship from Medic     
31:02     
and they they presented their their their I guess product. I don't know how to really call     
31:09     
it. It's not really it's not not anything for sale. It's sort of a component a publicly I guess you call it     
31:16     
it's sort of a publicly available demo of one of the components of the game world     
31:22     
that that we're building out. Um and that's that's good. And there's a going     
31:28     
to be really interesting time. um most of which you know I can only say so much     
31:34     
here but um there's a lot of plot twist is is     
31:41     
I don't know on a on a personal level two years ago in 2024     
31:49     
May so year and a half whatever uh we were at Oxford that's when I went     
31:55     
to Oxford last and then London and all that stuff and there There was a bit of a hiatus     
32:01     
after that, but it's very interesting now where the momentum has kind of shifted a     
32:07     
little bit back in the in in in the doing. There's different different parts that are that are functioning right now.     
32:13     
So, it's really interesting to see where that's going to go. Um, and there's sort of this very interesting overlap     
32:19     
between, for example, um, Digi Nest, which is this digital narratives, um,     
32:25     
emerging story technology kind of group, uh, which Avery is in that. Um, Molly     
32:32     
has, uh, been consistent part of that. Um,     
32:37     
nothing super cool to say in terms of showing off stuff, but we have been     
32:43     
pretty good at maintaining the momentum. uh which is quite nice uh and and very     
32:49     
much you know I always think of Bradley about about the momentum in progress situation     
32:56     
and we have been hold on a second uh     
33:02     
yeah the things we're working on there Avery wants us to prototype some of the ideas they've had about     
33:10     
you know sort of interesting Ella that functionally speaking The projects revolve a little bit around LM which     
33:18     
sounds kind of like obvious and and trit in a way but Avery is kind of looking to     
33:24     
make various incarnations of     
33:33     
some of their theories and also just just sort of in a in a tool exploring     
33:38     
what certain tools can do relative to things they want to see created. So he's not he's not beholden to using you know     
33:46     
flaw or GTP or some rapper or some version of it necessarily to do XYZ but there's some exploration happening     
33:52     
there. Uh Molly mentioned something about kind of a     
33:58     
users's guide u to to LMS or sort of a things things a a common or average user     
34:05     
should be aware of as that's happening. Um, and so we're looking to that someone     
34:10     
and looking at some like the research like less and we actually met yesterday     
34:16     
and talked a little bit about like the environmental impact or just you know how do we how do we try um how do we try     
34:24     
to understand the data that's available on these different fronts and the projections like that's that in and of     
34:29     
itself trying to be like a reasonable consumer of information about some of the things is a challenge uh because of     
34:37     
the competing camps and then you know all the the different interests of the play which is I I particularly     
34:45     
think about that. Um but yeah so that that's going well. Um, and also I have I     
34:51     
feel like I have so much um I haven't posted a lot of things. Uh, but but     
34:59     
there there there's a a huge stockpile of discussions from Digest from     
35:08     
uh a few other things from the modernizing mental health um pod I don't     
35:13     
call it podcast. I like I like discussion series because I'm not I'm not trying to release full length episodes for any of these things but     
35:20     
we've had having some consistent meetings with Jen about that in terms of you know um     
35:27     
both some of the practices too a lot of it a lot of the JoePro angle and many of these things for the discussions are     
35:34     
what's the domain space and then what's sort of the problem what are the problems in both the pedagogy and applications of the spaces that are     
35:42     
common that that that extend and beyond that specific domain space. So we're like a lot there is about training and     
35:49     
education and and preparing and then yes even things like how are contemporary     
35:54     
social workers or people in those professions um being taught about     
36:00     
technology and AI like and what are their implementation best practices? What are the you know when when classic     
36:07     
example like oh I have I have an AI boyfriend or girlfriend you know and that person comes to therapy how do you     
36:13     
deal with that like what do you what are you supposed to know in a clinical side so that those are those are broad broad     
36:20     
things and those are you know those discussions are happening um     
36:29     
that's that's sort of the the nonprofit side of things. Um I am also I     
36:38     
have uh officially launched Bridge which is this uh     
36:45     
forprofit entity that that will do different things but is basically around     
36:51     
you know technology and change and consulting and advising people what to     
36:57     
do and some executive coaching and some like some some conventional consulting     
37:03     
things and some modern or next generation things that are a little bit more um finding the sweet spot between a     
37:12     
lot of older conventions and bigger firms and things that I think are increasingly relevant and and     
37:19     
it it stems from my experiences but also just um there's there's a lot of demand like     
37:27     
I you know I I know this isn't the main focus of what we talk about here but     
37:32     
there's been there's been so much demand or just so many jobs and so many things.     
37:38     
People are people people are just so uh many many groups both uh     
37:45     
in in in research and in nonprofit sections and and obviously profit space is just like wow we need someone to tell     
37:50     
us what to do about AI. We need we need someone to uh speak with clarity and     
37:58     
confidence about you know what we're doing and     
38:04     
uh that's that's been it's been a further realization of okay well there's     
38:09     
things here now. So that's in development and um we're expanding a lot     
38:14     
of our network for people on the roster and people that want to either do things with us or     
38:20     
um accepting accepting certain clients for that too.     
38:27     
So that's that's a lot of work has been there and it's also been a lot of interesting it's a very interesting time     
38:34     
more relevant things would be a lot of the advances we're seeing in I mean even even as simple as like I don't know how     
38:41     
much we've talked about here the last week or two about like all the cloud bots and open cloud and that kind of     
38:47     
stuff which I'm is you know a very peculiar space on many ways but how are     
38:54     
people using all these new tools for not not LM based but even just all the     
39:00     
technology available and like the the broad theme here of like doing research differently and what are we doing with     
39:07     
these various various things that are before us. Um sorry but yeah that's     
39:14     
that's been a big you know that's launching anything like that is is a lot. Um there's we're kind of still in     
39:20     
an initial stage of some things, but also like it's happening like that's that's rolling and live in the world and     
39:27     
and that's exciting and it's it's uh yeah, it it's really interesting. It's     
39:33     
always it's kind of on a on a personalish note it's very interesting to be like okay now I have sort of a     
39:42     
very particular state um a very particular vantage point of     
39:50     
in terms of trying to do sort of nonprofit type research and development in like the Joe     
39:57     
or like what we've done here that's sort of like you know paracademic about certain things you have that whole     
40:03     
process and agenda and approach to things. And then you're dealing with the other side of the coin of the the     
40:09     
industry and the for-profit side of things that are like, oh, like what are people doing to be functional there and     
40:17     
where is where are sources of actual knowledge and insight on how the technologies are being made and where they're going because that's huge on all     
40:24     
the different fronts. So, um that's pretty much like the broad     
40:29     
updates. I will be in New Jersey um basically next week. It's already here     
40:35     
and doing some like traveling in New York, New Jersey soon. Um for some     
40:42     
events and things of that nature. Uh yeah, that's that's my super super duper broad update. Um a lot of things     
40:49     
and I'm happy to talk about any, you know, specific parts if there's questions or or a lot of what I talked     
40:56     
about dovtails into other things too. So I'm happy to shift conversation to those things.     
41:10     
You have a slide projector screen in there,     
41:16     
but I heard you lifting it up something. I mean, it does it does sound like     
41:21     
it. You're right. I I kind of wish I kind of like as as a total like fun side     
41:27     
comment. Um it's been so interesting talking to people like setting setting     
41:32     
up like some like finance stuff and a lot of like the really the stuff that nobody wants to talk like some of the     
41:39     
most boring grunt work whether it's it's forprofit or nonprofit like just the the really tedious stuff. And in the process     
41:46     
of that, the last week or two in particular, it's been so interesting to     
41:51     
have like these side conversations about the role of physical media. Like somebody was like, "Oh, here's one of my     
41:57     
last business cards. They're not letting me they're not letting me use physical media anymore. They have I want you to     
42:02     
scan my QR code on my my sign." And and and just little things like that. It was like I I think     
42:09     
when I when I had I had to um what was it? I think I had to change     
42:15     
like some minute address or detail or something and I had I felt like I had to     
42:20     
click 40 I had to click 40 different buttons and 40 different like mouse clicks just to to get to the thing to do     
42:27     
the thing. And it's like, man, like I I I've heard about like the PE that people     
42:32     
like, oh, my VHS tapes or my DVDs or my CDs, like the physical media movement.     
42:38     
And it really hit me this this last week or two of like sometimes you just don't you don't want to stream or subscribe or     
42:45     
monitor like like that. I I do and because there's been a lot of talk about     
42:51     
that too at a higher level of like are people gonna what's the limit like there's been push back against AI in the     
42:57     
syn there's been push back against AI this way and that way and there's like certain certain groups etc like oh well     
43:03     
AI is super great and we don't care about it here because blah blah blah blah and it's I don't think there's sort of a a one-sizefits all but there's     
43:10     
definitely a lot of um I'm I'm feeling the appeal of just not     
43:16     
just unplugging but not the the the permanent the permanent     
43:22     
cloud over the head of like a subscription or like managing multiple login and the data risk and the privacy     
43:28     
risk and is is some corporation going to buy my data and use it to do things I     
43:33     
don't like like that that seems to really be a force that we don't that's a wild     
43:40     
card. Yeah. Like how much that plays out I think will be very interesting. And I do like     
43:45     
I'm not I'm not I'm not trying to like pitch anything here, but I like unfortunately     
43:52     
I think that's going to affect like all the domain spaces that we're dealing with whether it's for profit or not. So     
44:01     
I don't know that's I'm happy to pass the mic to someone else after all that randomness. So     
44:09     
well I just had another comment too. you talked about like you know we've been having these discussions about uh open     
44:16     
cloud and and all these other things and Morgan's been talking about how people have been using it for     
44:23     
different things. We talked about bolt book last week and so what are your what are your thoughts on that? Um     
44:31     
you just mentioned it. I thought you may have some more things to say about that.     
44:36     
I mean, excuse me. Punching is a bite. Um,     
44:45     
I'm curious. I should probably I would love to hear any kind of a quick recap from what you you you folks have said     
44:52     
recently because I'm sure you've anybody like used     
44:58     
well, it feels like there's different iterations of I don't even know what to call certain parts of it right now because there's I know the mold box and     
45:04     
there's like open claw. I know there's like open claw as a thing and there's like the rent a human site you know like     
45:10     
these sort of derivative things where like oh you know we we we need people to do     
45:16     
all this stuff. I don't my I don't have any strong takes other than     
45:23     
like the obvious generic sort of caution of     
45:32     
like it's a fascinating time and like honestly it's it's a one like it's an     
45:37     
amazing time to be starting up new things and like the ease of going from     
45:44     
an idea to a company to a product to all this stuff is     
45:51     
unbelievable. Like I've I've done it again or like you know I'm doing this version of PL.     
45:57     
It feels so different but like     
46:05     
like you you you hear stories and you think of use cases and it's like well you know     
46:11     
you got to be you got to be careful. So I'll leave it at that. Well, I I will     
46:17     
say that this is sort of, you know, a measured statement, but I'm curious,     
46:22     
what have you guys been really thinking about that? I know I missed some bits and apologize, but where's the     
46:28     
conversation going on? Well, I'll let Morgan go first on that and then I'll give my thoughts.     
46:34     
Yeah. So, you know, my So, I'm I'm running it     
46:42     
on um running it on this laptop here     
46:47     
somewhere. Um, and you know, and I've I've     
46:55     
uh I I feel confident enough to to run     
47:00     
it um dangerously     
47:06     
um on on a system that I control physically.     
47:12     
I also like to live dangerously as well. Yeah. But but at the same time, right,     
47:19     
like like you know, it it's     
47:26     
part of following it is just to,     
47:32     
you know, my New Year's resolution of I'm going to     
47:37     
um I'm going to track agentic coding,     
47:44     
right? And And by track, I mean like I'm gonna jump in both feet, you know, try     
47:53     
to immerse myself in what's going on and try to be a user, you know.     
48:01     
Yeah. Um and and I've I've actually applied for a fellowship with uh with a     
48:08     
program here in um uh San Francisco     
48:14     
which is is run by somebody that I know got a lot of respect for     
48:20     
um and you know is is somebody who's definitely     
48:28     
is definitely coming at this as a kind of an experience experience product designer and product manager.     
48:35     
And what I mean by that is is that like this is somebody who's working with companies to actually build products,     
48:43     
right? And so they they run a hardware studio.     
48:48     
Um so it's I mean we're not     
48:54     
you know like this tower has got a lot of it's got a lot of app people. It's     
49:00     
got a lot of website people. Yeah. It's got a you know it's got a lot of crypto web three people, right?     
49:06     
Yeah. Um I     
49:12     
big big difference. Oh yeah. When when you're talking about     
49:17     
a a group that is much more like, you know, working with lab automation     
49:24     
for biotech or battery design or, you know, like     
49:34     
an exoskeleton for um to help people walk, which is cool. And     
49:42     
this wasn't even it's not even for people. This is actually like an augmentative device. So, this is just     
49:49     
like like you want to climb up that mountain like put put these put these pants on, you know. Um uh     
49:59     
so, you know, because there's something there's something very     
50:07     
um     
50:13     
There's a reality that you run up against. There's a very particular discipline     
50:19     
that will destroy you. Right. Right. If you if you know so so     
50:26     
it's funny. It's funny you mentioned rent to human because because event there was um there I met a guy     
50:36     
whose whose bank um row our ho     
50:43     
yeah he was up here one time. Yeah. So so so he's doing compliance     
50:52     
on the rent to human. Oh my god. Right. That's     
50:58     
and and he he's just like he's like you're you're just some guys on a couch     
51:07     
like like like I can't open a bank account for you. like like you're not even an American     
51:16     
like like um     
51:21     
but but his his the the real point was that like it was     
51:27     
more it was more something that I mean like the compliance guy himself was just     
51:35     
like this this this is a company based off of a tweet that went viral, you     
51:42     
know, like Well, yes. Yeah.     
51:47     
And and so, um, anyway, the the just coming back to     
51:53     
the, you know, what can you do? What what is open claw, right?     
52:01     
And and you know what you're what you're also seeing is that like     
52:06     
this is such a basic idea, right? Where     
52:13     
it's it's an LLM um with     
52:19     
with existing artifacts, right? So it's it's it's actually a small enough     
52:26     
project where you can you can get started with it andor fork     
52:33     
it, you know, right? like um and so it's it's it's very it's very     
52:43     
close to the the way in which     
52:49     
people are already doing agentic programming,     
52:55     
excuse me, where you're making markdown files.     
53:02     
Yeah. to give to give the LLM, you know, memory, persistence,     
53:09     
um skills, and um you know, any anything else     
53:18     
where so that you don't have to keep repeating     
53:23     
yourself or you don't have to keep using a very large prompt that     
53:30     
includes all the factors. because you know LLMs are like a are     
53:36     
like a um you know fish in a bowl and just seeing you know     
53:44     
and and so this it's like it's like it's kind     
53:49     
it's super basic, right? Um, and yeah,     
53:55     
I think yeah, I I think I think a lot of my take to kind of play off of that and and and I guess what I said before is is     
54:02     
just like it's it is I     
54:11     
this is probably just how I naturally am. you all know this and now that I'm     
54:17     
like I'm legitimately I've legitimately wearing different hats and speaking from different perspectives and it's like I     
54:22     
think what am I what would I tell a high school student who's going into     
54:29     
you know college right now and congratulations to um someone in like the JPro community     
54:36     
who who've done that I won't I won't mention who but if they see this they'll know who it is and and that they were     
54:41     
just accepted like conditionally to some great schools in in the UK. But like     
54:47     
what what do you tell to that person about your career or what you study, you     
54:53     
know, and what do you what do you tell somebody who's um you know in starting up their own wants     
55:00     
to be a founder has an idea they want? Oh, I have an idea. I have an idea. Maybe it was based off a tweet, maybe     
55:06     
not. What do you tell the people who you know the eboard of of the company that's     
55:11     
who should we how should we be more AI native you know like do they know what that means do they want to do you know     
55:17     
all that kind of stuff it's like it's such a weird it is such a weird time right now where     
55:25     
I I find I find this I find the open claw and it's a relatives to be an     
55:33     
embodiment of the moment like I think I think a lot of things that I I think about doing and try to offer people is     
55:40     
is a a framing or like a vantage point or a set of references because I feel like     
55:48     
like people have to understand what is creating the situation both like     
55:53     
economically and also like in terms of regulations like what could change and     
55:59     
why is there so much push back and and what people want there's a lot you know there's a lot of heavy contention right     
56:05     
now about what what kind of any kind of regulation both from like the creation     
56:10     
of things but down to like economics down to like what what what kind of     
56:16     
funding or oversight is necessary blah blah blah blah blah and it's just like look a lot of a lot of stuff has hap     
56:22     
like this is this may be and it may not be but it may be     
56:27     
an un unprecedent like a forever will never be the same again in terms of     
56:33     
the wild west nature of some of what's happening right now. Maybe it will be uh maybe maybe it'll be the new norm. But     
56:40     
in some ways like like the this the rapidity of ideas, the complete lack of     
56:46     
you know uh like like like you know look like you mentioned the seeking compliance and banking accounts stuff     
56:52     
like that. And it's like, yeah, um, and you can you can still     
56:58     
you can rush stuff and get money right now in very particular ways, but like     
57:04     
what does that mean in terms of quality or longevity or sustainability of of the market or of whatever? Like, it's such     
57:10     
it's such a weird time. So, it's it's like this weird mix of like go for it, find out, dive in, be aware of it, and     
57:17     
and and there's a lot of t there's a lot of tension like that's that's there's a lot of It's so weird because I think one of the     
57:25     
weirdest things about all this to zoom out again and from a different angle is AI is affecting workforces. Like I've     
57:32     
known I've known another batch of people who were just presented with redundancies about about stuff and     
57:37     
giving very bogus reasons for like oh we offshore blah blah blah blah blah and it's like no you guys want to try to     
57:43     
lean on AI and push people out and that's fine but it's like there's this     
57:48     
massive deference to AI but we don't we don't know some things yet about like     
57:55     
it's kind of just a well we're all going to find out together so let's look let's let's make sure we're all in the same boat And     
58:02     
you know what do you do with that? I feel like I feel like a lot of ways it comes down to what do you want to like     
58:08     
what not not what the the line but to go back to your point about like the physical engineering hardware people. I     
58:15     
think there's a very there's a very interesting take between what do you want to do and what can you do and how     
58:23     
for a lot of like the apps and website only folks the line there the the rationalization     
58:31     
for how to sort that out is can be very different and I think there's sort of a     
58:39     
um increasingly in certain spaces it's not it's not even about what can you do,     
58:46     
it's what do you want? I wouldn't even say the should word, but like what do you what do you want to see in the world     
58:51     
right now? And it's weird to kind of, you know, when you're talking to people with different backgrounds or takes on     
58:58     
that, that's a that's a challenging space. Like, how do you find consensus about that? And on like a really a     
59:04     
really particular kind of weird level, it's it's sort of well, who are you going to partner with and who what are     
59:11     
you going to it feels like this very particular I don't want to use I don't I don't mean as inherently negative as     
59:18     
colonization um perhaps was um in in in in certain     
59:23     
regards but very much a sense of okay like you have your your fund your broad     
59:29     
funders of things and you have people kind of let's get our East India company or our ship and go somewhere and do     
59:35     
something and hopefully it's not I'm not trying to have like nefarious implications here but a lot of it's like     
59:42     
where like who's going where and what are they doing and what are they     
59:47     
colonizing if you will in in the service of other things. So, I don't know that that was probably a lot     
59:55     
not really what we wanted to talk about in some ways, but I feel like that like it's hard for me to talk about the space     
1:00:00     
technically without understanding what's affording that in a non-technical sense.     
1:00:08     
So, anyway, um I I I'll put ask you a     
1:00:13     
very specific question about it. Like I I've wondered if I should just put it on a laptop and let it go and do certain     
1:00:22     
things. I've seen some interesting use cases, but like do you think would you recommend like a dedicated     
1:00:29     
old laptop or like put it like when you say you I you may not be able     
1:00:35     
to say everything, but like when you say live dangerously and let it do things on a laptop, like how does that play out?     
1:00:41     
Oh, I I I mean Yeah. So, so in this     
1:00:47     
case, um,     
1:00:52     
so, so part of it is that you're running it,     
1:00:58     
um, without some of the guard rails like like again like like     
1:01:05     
one of the reasons why I brought up um, uh, last week, I think I brought up that     
1:01:13     
um, Lady Ada was basically using open claw in her videos, right?     
1:01:22     
Like like a and and she was running, you     
1:01:27     
know, the way in which her and um Circuit Python guy Scott, I forget. Um     
1:01:36     
he does a show on Fridays. Uh he does a weekly YouTube as well. um     
1:01:43     
like they were both using it and     
1:01:49     
it's it's again it's it's like I think I think using aentic coding     
1:01:58     
first like like using cloud code the way     
1:02:03     
the way the cloud code developer uses it is like actually     
1:02:08     
creators independent. Yeah. What's that? I was jokingly saying the way its creators intended it for it to     
1:02:14     
be used. Well, you know that it's it's like like it was it was actually one of his posts     
1:02:19     
that went viral where he was showing people how he was using it,     
1:02:25     
right? where he was using it like on a on a Apple laptop with, you know, iTerm     
1:02:32     
2, you know, with five tabs and like the agents sharing context and like like he     
1:02:40     
was he was he had a very particular way he was running it, right?     
1:02:47     
In a in a very particular multi- aent way in which he was running it.     
1:02:52     
and uh you my my experience you know so so one     
1:03:00     
it's good to do that and it's good to see like like the the necessity of the     
1:03:07     
kind of intermediary markdown files yes that that you're sharing and passing     
1:03:13     
because as soon as you do that then like setting up openclaw is just like like they'll call they'll have some     
1:03:21     
of these these markdown down files be called like like soul.md     
1:03:26     
right you know you know and but this is this is this is purely for the humans right     
1:03:32     
right I mean in the sense that like like you know yeah I mean it it's these these     
1:03:41     
are just to give us useful guides for for how that particular artifact is     
1:03:47     
going to be used by the LM but at the same time in terms of kind of like the     
1:03:54     
additional software. There's no additional software, right? Like it's an LLM that that um     
1:04:02     
that you're you're kind of like hooking up to     
1:04:11     
two resources, right? So, so like one I might you know     
1:04:18     
so so so Bradley Voytech who leads um cognitive science at UCSD right     
1:04:24     
like like he posted on his LinkedIn     
1:04:29     
um he posted like hey I was hearing all the the buzz about agentic coding so     
1:04:36     
like I spent a day vibe coding uh a I     
1:04:41     
forget what he called it like talk something for the cont. Yeah.     
1:04:46     
Yeah. Yeah. Yeah. Yeah. And and you know, but it's funny because it's     
1:04:52     
just like so I installed I installed he and he he said he like that took like four hours, five hours or something like     
1:04:58     
that. And um but here's the thing, right? like I I I installed OpenClaw,     
1:05:06     
right, which again is not an install or like you know it's running a oneline uh     
1:05:13     
JavaScript thing, right? Or you know it's like installing a node package, right? And and and     
1:05:22     
now and then you connect it to your your LLM service, right? Was it like who are     
1:05:29     
you paying? Um and and then it's it's online.     
1:05:36     
So the first thing I did was said like hey you know start start uh start     
1:05:42     
hooking yourself you know start signing up for RSS feeds like like you know like     
1:05:49     
go grab those tables of contents like they're all available right? So, so um     
1:05:57     
you know I could basically I could tell I could tell Open Claw to like make this     
1:06:03     
service, right? And and you know     
1:06:11     
that's that's the that's the kind of like the only difference is that like people are potentially     
1:06:18     
right like like now I don't have to um now I don't have to run my LLM on a on     
1:06:26     
an app directly from the service. I can I can run it on a Raspberry Pi, but that     
1:06:37     
that Raspberry Pi has access to a Telegram account,     
1:06:44     
right? So So I can I can now send, you know, I can now say to my Raspberry Pi     
1:06:53     
um via Telegram, right? like go check out Bradley Voytech projects like grab     
1:07:03     
the OPML of of the the RSS     
1:07:09     
um feeds, you know, and and create create the you     
1:07:15     
know provide provide the same service to me now uh on a daily basis. Send me     
1:07:23     
articles via Telegram. Right. right? Of the of the you know the articles that     
1:07:31     
best fit my Google Scholar profile something like that. Right.     
1:07:36     
And like and as like my my previous job and I was was basically     
1:07:42     
very interested in essentially edge computing for very specific health like health tech     
1:07:49     
applications and now it's like even I'm thinking about open like cloud and like all these things I'm really I haven't looked into     
1:07:56     
this but I'm really curious about things like HIPPA compliant data and and there's there's this this movement in     
1:08:01     
that direction of like okay now now edge edge computing or like edge LLM access     
1:08:06     
and like that's going to be that's a huge you know um     
1:08:12     
both offering products and services but also like this a disruption potentially     
1:08:17     
for a lot of things. So yeah, I'm that's I'm glad that you mentioned that     
1:08:22     
specifically because I that that's a different an interesting     
1:08:28     
way to think about a lot of you know problems and then also uh     
1:08:35     
but you also see how like like it's barely new, right? like like you know um so so you     
1:08:46     
know living dangerously um I gave it a I gave it an email     
1:08:53     
address and I gave it I mean so you can't you can't hook it up to your Gmail     
1:09:01     
but if you have a Google Workspace right so if you have a business or nonprofit     
1:09:09     
Google Workspace um you can hook it up and so     
1:09:16     
so I'm I've given it uh a full role at the at the org,     
1:09:24     
but again it's it's um you would really need you'd really need to do some extra     
1:09:31     
work to get it to to to actually be, you know, doing something, right? So, it's     
1:09:38     
like we we've definitely got a team, you know, the the AI group on the floor above us are like absolutely trying to     
1:09:47     
get a make a open claw that like runs the tower,     
1:09:52     
you know. Yeah. Uh um I'm all for it, you know. Um but     
1:09:59     
but that's that's kind of like you'll see that like you know what they kind of     
1:10:05     
mean by that is that it it behaves like a telegram bot.     
1:10:11     
Right. Right. you know, and and you know, I I think I think the interesting the interesting thing that that maybe     
1:10:19     
speaks to kind of like an actual business case, right? Because like again, the point of all these things is,     
1:10:28     
you know, if if LLMs actually become     
1:10:34     
good scientific software developers, right? I think it's still important to     
1:10:40     
say that doesn't mean that they have a business case, right? And yes, like like that that's not how Open AI     
1:10:49     
and Anthropic are actually going to pay back their their debt, you know. Um and     
1:10:57     
and you know like like I think it's it's important you know I cut my teeth post     
1:11:05     
college being thrown in the deep end of of     
1:11:10     
regulated software development right so a software engineering manager for a medical device company and     
1:11:17     
um where you know you don't it's not enough     
1:11:24     
to ship right? like like you know privacy and     
1:11:30     
safety and and um kind of code provenence     
1:11:37     
um are all actually you know     
1:11:42     
regulated uh um regulated developments you know     
1:11:48     
um and that's really hard to see how you     
1:11:54     
how you square that circle in terms of agentic development, right? Because     
1:12:01     
Yeah. I and that's kind of why I mentioned the we can we can segue other things. I'm     
1:12:07     
sure but I'll close by saying I think that's that's that's exact this conversation is     
1:12:14     
exactly what I feel about like the I don't I think I'll Yeah, this is sort of     
1:12:20     
a nice sort of zooming out comment I guess. I think my biggest     
1:12:29     
Uh essentially it's     
1:12:34     
the nature of the the nature of the the problem space or opportunity space is     
1:12:40     
very interesting in its differences in the     
1:12:46     
vantage points that people have. And I do think like one people can be sold.     
1:12:51     
People can sell out. People can be sold. People could take it down the river on a lot of things right now with the promises and whatever. Like that's yes I     
1:12:58     
acknowledge that. Beyond that um     
1:13:03     
what people see the domain like the problem space and and the opportunity space what people see is really     
1:13:10     
different based on what they know and who they're talking to. And I     
1:13:17     
I I had a conversation basically yesterday about how you know like like in ter this this is sort of a broader     
1:13:24     
zeitgeist moment of like you know um environmentalism at a at a is is still     
1:13:29     
an issue in the world perhaps or differently but but it's not a politically relevant issue or like as     
1:13:37     
opposed to like technology and jobs and other things other thing many other things going on in the United States right but it's sort of like a lot of     
1:13:46     
people who have strong opinions and and done things in that the environmental space are sort of their approach on what     
1:13:51     
AI means now and is is it using technology like their interests have     
1:13:56     
kind of been transferred into this other technical space to varying degrees of fidelity or     
1:14:03     
like accurate mapping of those feelings or those opinions and those takes and I feel like right now you know we're in     
1:14:10     
this space where um it It's it's like what what     
1:14:18     
it's it's very it feels very like buyer beware or or like like it it's a great it's a great place to explore stuff and     
1:14:25     
yet also there are there are hard limits that are coming up too not just the     
1:14:31     
physical engineering limits but also like you said like I I quoted this I think very well said but like that's not     
1:14:36     
how anthropic and open AAI are going to pay back their debts like people need to understand     
1:14:42     
there is a business reality that comes out too. And there's a there's a reason why things are being made available and     
1:14:48     
the reason why the data that's being collected is is a trade-off for certain things and all this other stuff. So,     
1:14:54     
yeah, I'll I'll I'll leave it at that. Um I I'm sure I have more things to say,     
1:15:00     
too. like I I don't I'm I'm I'm claw I'm open claw agnostic at the time but at     
1:15:07     
the same time given many things that I'm doing right now like I I need to know     
1:15:13     
you know certain I need to know some things about it because people are asking so     
1:15:18     
yeah yeah yeah so I mean sorry just one last thing you know is like it is     
1:15:29     
it is kind like a maker project that     
1:15:34     
um that is following very closely     
1:15:40     
what all these closed software groups are doing     
1:15:46     
right I mean in the sense that like you you've currently got a million     
1:15:52     
developers who are all you know writing     
1:15:57     
agents you I mean writing agent apps, right?     
1:16:03     
Yeah. Which are doing exactly this, right? It's just like like you're you're you're     
1:16:11     
either giving them you're giving them sources of of data. You're you're maybe     
1:16:17     
fine-tuning the agent, you know, conditioning that agent.     
1:16:22     
You're again giving the agent certain like context and and and other kind of     
1:16:28     
um guidelines to to you know drive their     
1:16:34     
personality and responsiveness and directions and things like that. You     
1:16:40     
know again like there's this scaffolding and and and then you're giving it     
1:16:46     
outputs. You're giving it a way to to communicate, right? I mean, you know,     
1:16:53     
again, with the the real world, right? Yeah. Yeah. I mean, in the sense of Yeah. And and     
1:17:01     
it uh so that that's that's what I mean by like like it's a kind of perfect you     
1:17:08     
know it's it's um you you you see this again like coming     
1:17:15     
from software development where people learn you know it's not that you     
1:17:23     
are excuse me it's not that you are a C++ programmer right like if you're an     
1:17:28     
app developer, right? I mean, again, I'm I'm so old I'm going to date myself with     
1:17:34     
this, but like um you know, in the old Mac OS classic days, right? If you were     
1:17:40     
a Mac app developer, right? Then you used MetroWorks code     
1:17:45     
warrior and and you know you were actually a     
1:17:51     
code warrior like like you had a a C++ framework that you used to develop with     
1:17:58     
and and that yeah um you know similarly you know if     
1:18:07     
you were a Windows developer which I was um you you would you'd be you kind of     
1:18:13     
conditioned on that. And like so this is just the the this is like you know we're     
1:18:19     
seeing a a nice open source project that's giving you the the the um the     
1:18:26     
prototypic template for for an agentbased app right     
1:18:35     
you know so it's kind of nice it's it's also you know but it's like it's also um     
1:18:41     
um yeah it's it's lacking a lot of professionalism and and a lot of um uh     
1:18:49     
uh Yeah. Yeah. Anyway, I I I don't know if software engineers are going away     
1:18:55     
anytime soon. No, if you care. Um and and the other thing is that Yeah.     
1:19:02     
Like like there's no economic story here, right? Where it's just like like you know none of these app     
1:19:10     
so we all have access to the world's text, you know, trained LLM, right? But     
1:19:18     
that just means that like now the app store is a thousand times more     
1:19:25     
competitive, right? Like so you're you're kind of like even less likely to     
1:19:32     
get traction for your app. like how your app will get any kind of visibility     
1:19:38     
is now um uh exactly much much worse, you know. Um anyway,     
1:19:46     
yeah. Yeah, I'm sure Bradley's got some actual interesting science to talk about.     
1:20:03     
Um I I'll just say in a in a moment your     
1:20:09     
what you concluded on is exactly what I'm seeing a lot of um people     
1:20:18     
wanting to not deal with or pretend isn't the case. And then also like are     
1:20:25     
depending on where they are like and how vested how vested they are in like being sober about it like if they don't have     
1:20:32     
anything to lose they're like yeah you know like the the hype the hype appeal is there and and then if they're like     
1:20:39     
well I'm established here is this actually going to do anything you know very classic differences that way but I     
1:20:45     
do think I do really think like     
1:20:50     
Um like I think it really like I don't in     
1:20:56     
in like the consulting management stuff like McKenzie and many groups like that the big big big enterprise level like     
1:21:02     
yeah there's there are hits coming there but I and I again this is self- serving to what I'm doing so like full     
1:21:08     
disclosure like I'm I'm probably biased in in presenting it this way but I think     
1:21:15     
I think right now like the strategy the actual business plan the decision- the     
1:21:20     
operational structure like that's what's going to differentiate certain things because some of the barrier to entry is     
1:21:28     
incred like like it's inc it's it's kind of seductingly appealing to think what     
1:21:34     
you can do and this could be great like I do if if it's handled the right way and who knows like I don't I I don't     
1:21:41     
know I I do think there's even in the sense of sort of     
1:21:47     
I don't want to say I really don't want to use the word free market here. But like the ability to create certain     
1:21:52     
competing uh pro like processes will be it'll be     
1:21:59     
really interesting to see where the line emerge in terms of creating alternatives or competitives to apps or     
1:22:06     
like that basically do the same thing versus centering different I I think I     
1:22:12     
think I think there is this is quite idealistic to say I think there is sort of a I don't want to say market or     
1:22:19     
economy, but like almost like a a economic trajectory of some sort. That's     
1:22:26     
it's kind of like it's sort of adjacent to um     
1:22:32     
like I know some people in the space of oh we're really centering human     
1:22:37     
genuine human non AI made content um or not not kind of products like     
1:22:44     
singing songs articles clothing whatever     
1:22:50     
and and stuff like that and it's like well what's going to different when when     
1:22:55     
when when the ability to create your app and your website and and your like you     
1:23:01     
know copy is so easy what's going to really differentiate. Yeah. So that was a good conversation. Um     
1:23:09     
it's a lot of I mean I don't really have a lot I think you covered a lot of what I was going to kind of bring up.     
1:23:16     
um you know I've been using um LLMs to do a lot of summary in the lab     
1:23:23     
sort of housekeeping uh going through the things that we've been doing you know in the last several     
1:23:29     
years and kind of summarizing those and looking for insights.     
1:23:34     
Um I I've been playing around a lot with uh the notebook LM where I create a     
1:23:40     
notebook, train it on like local material and then you know do queries or     
1:23:45     
generate media. Uh they have like their summaries and we've been doing summaries     
1:23:51     
of both the Saturday morning meetings and the uh naval war meetings which are     
1:23:57     
interesting because it's like it I do I kind of do it in six-month intervals. So, it's like this bundle of content     
1:24:04     
that's so big that it would be hard to really kind of extract a lot of the     
1:24:09     
themes unless you had like some automation to do it. And so, that was     
1:24:15     
kind of the idea there. And it's been, you know, interesting to see what it comes up with.     
1:24:20     
Uh they also have this feature which is slides which is interesting too because it draws like little figures and some of     
1:24:28     
them are ridiculous but some of them actually are interesting. Um and so you     
1:24:34     
have to kind of separate all that out. See what it does that's like really interesting. See what it does that's     
1:24:40     
really ridiculous. And uh you know that that's it's that's it's useful because we can get a little     
1:24:47     
bit better handle on what we've been doing. Um, so yeah, so there and there's stuff I     
1:24:54     
I've put them up on the YouTube channel so you can check out some of the summaries. Um, and so yeah, that's that.     
1:25:02     
And then I've been using it also for some uh coding and some kind of     
1:25:07     
summarizing uh like some of the research ideas we've had. So, for example, and I think I     
1:25:14     
mentioned several weeks ago, I've been creating these Ask a Cyberneticist chat bots. So, I created one for Ashb     
1:25:24     
and I've been playing around with that. I have like um some of the some of Ashby's papers, some of his     
1:25:30     
correspondences which I found through the library and library at UI has um a lot of     
1:25:39     
correspondences from the biological um     
1:25:44     
biological lab that was here. It was run by Ivon Forester and he you know they have like the correspondences from Ashb     
1:25:51     
because he was at the um biological systems lab and and von Forester and so     
1:25:59     
forth. So you you know you train them on the correspondences actually with ash view of his notebooks and they were     
1:26:05     
transcribed um by someone. It was like a humanities project where they transcribed a bunch     
1:26:12     
of his notebooks and using those transcriptions, you know, you can kind of ask questions about what Ashb would     
1:26:18     
do, what would Ashb do in this situation or what does Ashby think about this and     
1:26:24     
then it would give you like this structured answer which is, you know, um     
1:26:30     
quite quite intriguing. Um and then of course uh also trained it on a little     
1:26:35     
bit of um makulla's work as well. I haven't created a makulla bot but that's     
1:26:41     
maybe next. Uh and then also I did a B ran Granville who developed a lot of uh     
1:26:50     
he did a lot of things in like um management in business but he's also the     
1:26:57     
person who talked about black boxes and gray boxes and white boxes as being     
1:27:02     
these observable systems. And so you know that was interesting because I was asking it about um the observer in     
1:27:10     
cybernetics. I I I'd particularly like this. I don't I don't know if these are like publicly     
1:27:16     
available or what not, but I I'm interested in I'm using some of those black, white,     
1:27:21     
gray boxes for other things. Yeah. So, that's cool. Yeah.     
1:27:26     
Yeah. I'm not sure how when, you know, when if I make those public, but um I'm     
1:27:34     
probably going to give a demo here in in in a few weeks on this. Um we're maybe     
1:27:40     
just put it on the YouTube channel and going to walk through it. I I'm still kind of working uh I didn't have a plan     
1:27:46     
going in. I didn't I mean, I kind of knew what I wanted to do, but I just kind of like     
1:27:53     
kind of working from behind, if you know what I mean. like you just you say, "Oh, this would be good." And then you you     
1:27:58     
keep working on it. That's I think a lot of the thing about like working with chat bots and working with training a     
1:28:06     
model is that you uh you'd like to think that you have it all planned out, but     
1:28:11     
really it's just kind of exploration. It's like, "Oh, here's this data set. We'll put this in. We'll query it and     
1:28:16     
see what happens. We'll build on the query." And then, you know, it's uh     
1:28:22     
so it's hard to say when it's like ready for people to I guess it's ready for     
1:28:28     
people to use now, but I don't know how useful it is.     
1:28:33     
I don't have any standards for it. That's that's that's the case on many     
1:28:41     
fronts. Yeah. But I mean, you know, I'd like to have it like be re like sound research,     
1:28:46     
not just kind of but yeah, I mean, you know, the idea would be to have like an ask a     
1:28:52     
cyberneticist maybe for Ashb maybe for Von Forester for Grandville and would     
1:28:58     
have like the different skins or different flavors. So you could or you know you'd have     
1:29:04     
because you could ask a question like how would uh Granville interpret     
1:29:10     
feedback differently than Ashby and it would have like the two different perspectives in there or you know just     
1:29:17     
query diff the two different models or two different um     
1:29:22     
rag training uh embeddings and then say uh you know     
1:29:28     
you could just compare the answers I and and it cites everything like when     
1:29:34     
you work with notebook element it cites things the footnotes are basically where it's pulling it from in the thing that     
1:29:40     
you're training it from which is kind of useful but it's also kind of redundant     
1:29:47     
it like cites things over and over sometimes which is like papers do that     
1:29:52     
but uh you know you get this the problem is too sometimes you get this sort of     
1:29:58     
self-reerential loop where it's like going back to the same source materials or something. Um,     
1:30:06     
but that's again, you know, um, if you do a literature search,     
1:30:11     
feed I can feed it YouTube videos. Yeah. Well, notebook LM. Yes, you can     
1:30:16     
feed YouTube links and it'll extract things from the videos.     
1:30:22     
That's interesting. I you know because um you know John Griffith the the     
1:30:27     
professor at Toronto is also the board member. Um he and I did you know     
1:30:33     
YouTubetubes through the pandemic right? Um so we did you know threehour hack     
1:30:40     
nights every every week. Um and like definitely definitely more     
1:30:47     
than a year of that. Um,     
1:30:52     
it it would be kind of it would be it would be a fun synthesis project.     
1:31:00     
Yeah. You know, synopsis plus, you know, I I     
1:31:06     
I've actually really liked, you know, going through it just to pull out um     
1:31:13     
just to make a calendar, right? because it's like like every week we'd be     
1:31:18     
covering like what are the conferences this week, what are the the workshops,     
1:31:23     
what are the you know things like that and um um     
1:31:29     
yeah anyway that that would be that would be an interesting I'm I'm thinking you know so I've got a new I've got a     
1:31:35     
new tech website and you know and I'm trying to     
1:31:44     
yeah trying I think again like what are what are services like like having a proper calendar like is one of those     
1:31:50     
things like you know always be checking in to see what's what's going on.     
1:31:57     
Yeah. So definitely yeah we're going to have to follow up on some of this. Um     
1:32:04     
yeah and like you know it's like you have to kind of work your way through it. I don't know. I'm not an expert by     
1:32:10     
any means at this, but I'm trying to get like a methodology worked out so that     
1:32:16     
you know it's again like this is how you do produce something that's sound and we     
1:32:22     
can compare across uh different work sessions and instances and things like that. Um     
1:32:30     
yeah, so that's good. Um what do we move on? Um I saw that Sara was here. I don't     
1:32:37     
know if she wanted to say anything, but I guess she hasn't come back. So,     
1:32:42     
well, thank you, Jesse, for that. That was good. Um, and then sounds like there's a lot of interesting stuff going     
1:32:48     
on with uh Joe and and uh other things going on.     
1:32:55     
Yeah, we should do more um more detailed overview of that or maybe, you know, I     
1:33:01     
don't know what the data and direction. I'm interested to know kind of what are     
1:33:06     
you doing that this year again or what's the I think I'm going to     
1:33:14     
wait until summer to advert like there's there's residual things happening. I don't think I'm going to in put plant     
1:33:21     
any new seeds until summer. Like I think there's a really wonderful overlap with like Google Summer code stuff.     
1:33:27     
Yeah. So, I think when that picks up, I think that'll be the next natural like     
1:33:32     
re refilling the I don't know, planting new seeds, whatever you want to call it, because there's there's stuff that's     
1:33:38     
just winding down and um a couple a couple interns are um     
1:33:46     
we're kind of like just wrapping up what they've been doing. So, between that and I'm obviously     
1:33:53     
uh my my my center of focus has shifted onto other things right now. So,     
1:34:01     
um, and no, this is there's a lot of stuff going on. It's just the real the real reality is like it's so it's so     
1:34:09     
interesting because I was I was incredibly in the doldrums especially like October of of last year and now     
1:34:16     
it's just every everything's firing. So, um, data and direction, there is more I     
1:34:23     
would would be interested in doing with this like like there's there's projects that I want to release, but they won't     
1:34:30     
really be released until I think maybe April at the earliest, more like May, I     
1:34:35     
think. Um, and I would like to basically get another round of um Oops. Did I lose     
1:34:41     
everybody? I think I might have I think I might have lost my connection.     
1:34:48     
I can hear you. It's fine. Okay. Everybody froze and then Oh, okay. Um uh um but yeah, that's that's     
1:34:57     
it. Was there another question about that? I'm sorry. Oh, yeah. So, did from last year, did     
1:35:02     
you produce any artifacts or things you can like look at or Yeah. Um there are a couple     
1:35:09     
presentations and then also um we're working on the     
1:35:14     
um both the the two interns are wrapping up     
1:35:20     
essentially uh one one will be like a not as     
1:35:25     
detailed as like the Google summar code like like VI had an excellent you know     
1:35:31     
um like final blog post like there'll be a version of that which will be a little     
1:35:36     
bit simpler and and and someone's kind of their first time with NLP type stuff and and whatnot. And then also um     
1:35:45     
essentially an article series or a guide who are finding essentially a a guide.     
1:35:52     
One of our interns was working on a kind of a guide for parents on how to     
1:35:57     
deal with AI in the classroom and their children. So that's that's we're putting     
1:36:02     
the finishing touches on like the public version of that. So those will be those will be out um in the next few weeks.     
1:36:09     
Yeah. Well, I look forward to it. Yeah. And it's it's actually really interesting because the ladder will be     
1:36:16     
part of what I'm talking about at a an education panel um in in a few weeks. I     
1:36:22     
was asked to be part of that. And then it's kind of similar to the LM guide     
1:36:27     
that Molly and other folks in Digest are doing too because it it it's sort of you     
1:36:34     
know some of this some of this is you know uh undergraduate     
1:36:41     
research and and and level of of just getting those things off the ground. and some of it will be a lot more digest     
1:36:48     
stuff will be a little bit more um coming from people with certain experience in the fields and and and     
1:36:54     
different different applications. So I'm looking forward to that and it's kind of it's kind of keeping keeping everything     
1:37:01     
running down the tracks right now. But uh it'll be good. So yeah, um I'll do     
1:37:06     
I'll do a more broad like I don't know f first first this first     
1:37:12     
year basically first year of data and direction. We we'll do something for that specifically to show what we're actually up to.     
1:37:18     
Yeah, that would be good, you know, to showcase everything. Make sure that everyone knows sort of the value there,     
1:37:24     
you know, when they they want to join, oh yeah, this is this is something you can get at the end and it's uh     
1:37:32     
definitely worth your time. I mean, not that it wouldn't be worth their time, but it gives them one more thing to kind     
1:37:37     
of make that decision. Oh, yeah. Absolutely.     
1:37:42     
Okay. Yeah. Great. Thank you, Jesse. All right. So, this is a paper from last     
1:37:50     
year's Gecko conference. Um, this is from Risto and uh he he's     
1:37:59     
been at the University of Texas for years kind of working on AI models and     
1:38:04     
evolutionary programming and things like that and     
1:38:09     
Jame Warner who's at cognizant technology solutions and they work     
1:38:15     
together in this paper on self-organizing models of brain wiring developmental programs for involving     
1:38:21     
intelligence. So, you know, we've been interested in this developmental AI thing. Uh we've been interested in how u     
1:38:30     
neural networks can be evolved or developed and they're going to be talking about this this in this     
1:38:36     
conference paper. So, let's go over the abstract. Um     
1:38:46     
so, it looks like Risto is also at Cognizant AI Labs. Um so the abstract is     
1:38:53     
in developing brains axonal projections follow chemical gradients checked by     
1:38:58     
local interaction. So this is a mamalian brains where you get um uh the     
1:39:04     
development of a conto um through axon guidance and through neurogenesis and we     
1:39:10     
end up with a brain. So you know it's it doesn't just come it just doesn't come out into existence out of sort of you     
1:39:19     
know uh simple cell differentiation. There's a lot of chemical signaling.     
1:39:25     
There's a lot of sort of building the connections. And so that's what they're trying to do here is they're trying to     
1:39:31     
mimic this process. This paper asks whether such a process can be inferred from its outcome. For     
1:39:38     
instance, given observed mouse brain connectivity, one can recover the developmental program that produced it.     
1:39:45     
And that's a question because, you know, we don't know if we can actually recover that developmental program uh just     
1:39:53     
simply by looking at the connectivity. Um you know, there there isn't necessarily, especially if you're     
1:39:59     
talking about mammals, a simple developmental program that will give you that answer. Now in C elegance it's     
1:40:07     
worth noting that maybe that answer is more certain because     
1:40:13     
se elegance has the deterministic mode of development. So when you get neurons that emerge at a certain time or     
1:40:20     
neuronal cells they will become those neurons and then they'll wire up in a     
1:40:26     
way that's sort of stereotypic of you know the the the small conneto that     
1:40:32     
we're dealing with. And then as you know if you've been attending your D.VAR meetings the real variation is in the     
1:40:39     
synaptic connectivity not necessarily the gap junction connectivity and the     
1:40:45     
synapses actually are quite plastic during laral development and then going     
1:40:50     
into adulthood. And so, you know, that's not and part of that even you can     
1:40:56     
predict maybe from looking at um sort of     
1:41:01     
the the quote unquote program, but some of that of course is driven by     
1:41:06     
environment. In mouse brains, a lot of that is driven by not only environment,     
1:41:12     
but by interactions. So if two cells are in in sort of close proximity, they have     
1:41:19     
these chemical interactions that um you know where they sort of have a fate that     
1:41:26     
is similar. And so, you know, there are all sorts of experiments in developmental biology     
1:41:33     
where they take a stem cell and they put it into a niche of say like a heart     
1:41:39     
muscle cell and they can transform that cell into a heart muscle cell as well.     
1:41:44     
So, if you put a stem cell or you put a very potent cell of some type into a     
1:41:50     
certain tissue, it will assimilate into that tissue. And similar things happen     
1:41:56     
in in the mamalian brain in development. But there are all these sort of qualifiers with respect to neural     
1:42:03     
precursor cells and you know the position in the brain and things like     
1:42:08     
that and you know how it's connecting with its neighbors. So if it doesn't connect the cell dies if it connects it     
1:42:16     
can uh maintain an identity. So this idea of developmental programs     
1:42:22     
is really interesting. It's not really some people would argue against the idea of a developmental program, but even     
1:42:28     
when you have a developmental program, all that means is that there's some regularity there. And um you know, it     
1:42:36     
some of it is not really a program. Some of it's these interactions. So, you know, but as as if we're     
1:42:44     
simulating this, we want to know what the program is because we're going to actually build a program to, you know,     
1:42:51     
reproduce the system. So that's why we're interested in this idea. Um, if     
1:42:57     
such developmental programs can be recovered, they not only explain how biological connectivity arises, but they     
1:43:06     
offer a biologically grounded search space for artificial intelligence in     
1:43:11     
which architectures emerge through the evolution of genetic encodings that produce plausible layering diagrams. So     
1:43:18     
this is the key another key thing here which is Um you know basically the     
1:43:26     
advantage of having a digital analog of development     
1:43:31     
is that you can have this search space where you can look for different     
1:43:36     
possibilities that produce a certain behavior. So you     
1:43:42     
want to be able to produce wiring diagrams that do things that produce behaviors.     
1:43:49     
And we can use like something like a genetic encoding to encode sort of the     
1:43:54     
basic components or the primitives or sometimes like innate behaviors and then     
1:44:02     
build upon those to build more complex behaviors or learn behaviors or whatever. We have a bunch of     
1:44:09     
possibilities because you know we're dealing with this interacting system of a of a neural network. So we have all     
1:44:15     
these possibilities for you know architectures that produce     
1:44:21     
certain behaviors. Of course multiple architectures might produce the same behavior. Um so that's something that we     
1:44:28     
want to uh keep in mind. But then we also want to see all the plausible diagrams because it sometimes if you're     
1:44:36     
dealing with something like C elegance you might have a very uh specific type     
1:44:42     
of circuit like for example the movement circuit C elegance that's a specific     
1:44:48     
circuit that's you know doesn't vary from worm to worm it's very mechanistic     
1:44:54     
in terms of how it operates and you can even do things like use pharmacological blockers to uh shut down cells in that     
1:45:03     
circuit and you can modify the behavior quite stereotypically. Um so you know if you want to have if     
1:45:10     
you want to target a neuron that's involved in reversal behaviors or reversal movements you can shut that     
1:45:16     
neuron down and then the worm will no longer move backwards or no longer will reverse. you know anything about worm     
1:45:23     
movements, you know it moves towards say like a food source and then it backs up again and it could do these backing up     
1:45:29     
move maneuvers and you could actually plausibly shut down one of those     
1:45:34     
neurons. You could do this with uh optogenetics too and shut down that neuron and it would change the behavior.     
1:45:42     
And so, you know, this is kind of the what's interesting about this. Well, actually, what's interesting about it     
1:45:48     
from a biological standpoint, but also from an AI standpoint or an artificial     
1:45:54     
standpoint because artificially we're going to be producing, you know, emergent behaviors. And emerging     
1:46:01     
behaviors have, you know, that it's hard to kind of     
1:46:07     
uh reverse engineer an emerging behavior because emerging behaviors are explicitly about um you know,     
1:46:13     
interactions producing a certain outcome and then those outcomes being slightly different over all the instances of that     
1:46:21     
emergent behavior. And so but but still with with our um search space and our um     
1:46:29     
evolutionary algorithm that we're going to use here, we can s sort through that space, find all the plausible     
1:46:35     
configurations and then look and then evaluate them as sort of their own thing     
1:46:41     
and then see what they do. So it it narrows our possibility space and it     
1:46:47     
helps us understand how these things come to be. So in this paper a framework is proposed     
1:46:53     
that uses the biological conneto itself as a beacon to guide this search     
1:46:59     
referred to as the conneto generating AI generating algorithm. And so that's     
1:47:04     
awkward, but the acronym is not. And I guess there is a rule that like where if     
1:47:10     
you have an awkward um acronym, your phrase is good, but if your phrase is     
1:47:17     
awkward, you have a good uh acronym. And that's, you know, that is science right     
1:47:23     
there. So that that's what we're going to have. We have this conga platform implemented as a neuroscellular automa.     
1:47:30     
So they're using these neural cellular automatas which are these uh of course we've talked about this in divorm     
1:47:36     
they're cellular automas but they use a neural network underneath and they sort of run uh they're good for pattern     
1:47:44     
formation pattern generation and in this case they're using it for to find these     
1:47:49     
configurations. So implemented as a neural cellular automa a model was trained to reproduce     
1:47:56     
exxon tracing data mouse conneto and its internal representations were compared     
1:48:02     
to gene expression patterns measured at the same spatial coordinates. So they're     
1:48:07     
comparing gene expression across different parts of a a conneto with uh     
1:48:16     
these sort of uh models of the mouse connect axon tracing data on the mouse     
1:48:22     
connector. So they're looking at sort of how gene genes are expressed, if they're     
1:48:28     
influencing axon tra or axon formation, axon guidance using an axon tracing data     
1:48:35     
set and a gene expression data set to match those two things.     
1:48:40     
The result demonstrates how the brain of an intelligent organism may self assemble through an indirect encoding of     
1:48:48     
connectivity. The model L performed a static linear baseline but only when when constrained     
1:48:54     
in size suggesting that compact developmental programs better align with     
1:48:59     
biological mechanisms. So that's really interesting. Um this is     
1:49:05     
seems a little bit like I was under the impression that Gecko is mainly like an     
1:49:11     
applied uh conference. This isn't necessarily so applied. So it's it's it's really nice to see.     
1:49:19     
So this work investigated with their NCAs can serve as explanatory developmental models for real biological     
1:49:25     
data specifically the wiring architecture of the mouse brain. And so     
1:49:30     
this provides a powerful framework for simulating systems which structure emerges through localized iterative     
1:49:37     
processes originally applied to the synthetic pattern formation tasks such as emoji     
1:49:43     
regeneration. NCAA was were simultaneously proposed as models of morphagenesis and it's in 28 I     
1:49:50     
believe that is um this paper uh Ian distill     
1:49:56     
journal which is uh from uh this group including Mike Leven and Tori Randazo.     
1:50:04     
So they've they've actually done a well you know Michael Leven's work and Troy Reddazo     
1:50:09     
they've worked on some other things having to do with neural cellular automa. Uh so that's that's where     
1:50:16     
they're kind of basing this on. If you want to go back to that paper um that is     
1:50:21     
where they kind of produce um a pattern of a lizard with a neural cellular     
1:50:28     
automa. They kind of evolve a lizard phenotype. That's an interesting paper.     
1:50:34     
Um and so um to produce the connectivity data, the     
1:50:41     
NCAA is extended with a dotproduct decoder to convert its voxal level state vectors into a connectivity estimator.     
1:50:50     
This decoding mechanism reflects homophilic wiring rules where connectivity is determined by the     
1:50:56     
similarity between genetic expression signatures at both source and target     
1:51:02     
states. The central question of this work is whether an NCA when trained to reproduce     
1:51:09     
the voxal level connectivity of the mouse also captures features of the biological     
1:51:14     
developmental process that gives rise to that connectivity. So we want to maybe reproduce     
1:51:24     
the conneto. So if we train it on a set of data, we should be able to reproduce     
1:51:29     
that that connectivity between cells or between voxels. We also want to capture     
1:51:35     
the underlying gene expression or the biological developmental process. So uh     
1:51:41     
when we talk about a a developmental program, what we're usually talking about is a gene expression program.     
1:51:47     
We're talking about genes that are in some module where it the expression of those genes produce     
1:51:55     
say like some sort of patterning. So we might have a module that when expressed     
1:52:02     
in different spatial regions of the embryo will produce a concentration of a     
1:52:08     
certain morphagen which is some biochemical that is typical of that region and it     
1:52:15     
produces a distribution of that and then those distributions overlap and places     
1:52:22     
where where they overlap there's usually a boundary formed and that boundary formation is maybe something like     
1:52:28     
striping or some delineation of a pattern.     
1:52:34     
So we might have a gene regulatory network that produces certain colors of     
1:52:39     
pigment and depending on the region of the the embryo, you know, it could be pink, it     
1:52:46     
could be blue, it could be white or gray or whatever. And so you know cells in     
1:52:53     
each of those regions will uh express that variant of the gene regulatory     
1:52:59     
network. Those different colors will then kind of you'll have this distribution of cells     
1:53:05     
expressing these colors and then there will be a boundary because at some point those u you know the expression of those     
1:53:13     
things lead to the production of mRNAs and proteins. The proteins then um will     
1:53:19     
kind of be distributed in the in the space but also interfere with each other     
1:53:24     
at the boundaries. So then you get this sharp boundary formation and you get something where you have a multicolored     
1:53:32     
embryo with boundaries throughout. That's how you know you get pattern formation. And the same holds true for     
1:53:39     
something like a conto where gene expression is informing connectivity.     
1:53:44     
It's informing what you know it's basically a a gene expression     
1:53:50     
u module is in each cell and it's uh sending out these chemical signals and     
1:53:56     
if you have so cells with similar chemical signals they tend to layer together and if you apply this in     
1:54:04     
parallel you get a connecto that's the idea.     
1:54:09     
So if we modify that gene expression uh program if we modify that module how     
1:54:15     
it's expressed the different constituent genes inside if we rewire that uh     
1:54:22     
circuit then we can get different outcomes we can diff get different outputs and the wiring pattern will be     
1:54:28     
different that's the idea and so um the central question of this work is whether an NCA     
1:54:36     
will when trying to reproduce the voxal level connectivity of the mouse brain also captures features of the biological     
1:54:43     
development process. The NCAA's internal state variables treated as a candidate     
1:54:49     
mechanism for generating connectivity are compared to aligned insight to     
1:54:54     
hybridization gene expression data using a gene score metric that quantifies how     
1:54:59     
much of the transcripttoic variation is explained by the learned representations.     
1:55:05     
So we have this sort of um you know the fit of the data. So we'll have learned     
1:55:13     
representations and then we can compare that to transcripttoic variation. Basically what is this program producing     
1:55:20     
in terms of mRNA transcripts and measuring that at that level we can     
1:55:25     
maybe see parallels between that and our NCA output.     
1:55:32     
So high scores indicate that the model has not merely fit the data that has inferred a biologically meaningful     
1:55:38     
generative process. So if we see a a relationship a positive relationship a     
1:55:45     
high score between transcripttoic variation and what the NCA is producing     
1:55:51     
in other words if the NCA is basically aligned with     
1:55:58     
uh transcrytoic um signals across this array. then we've uncovered     
1:56:06     
maybe something that represents this generative process. We've not     
1:56:12     
necessarily discovered the exact mechanism, but we've discovered how this basically works. So that's the idea. And     
1:56:20     
you could argue that that's not a very sound methodology, but that's really all we have at this     
1:56:25     
point. It's it's basically double inference. You're inferring that like the     
1:56:30     
transcripttoic variation that you see that you measure is indicative of the activity of these gene uh gene     
1:56:37     
regulatory networks which isn't a given necessarily because transcripttons can be highly variable depending on context     
1:56:45     
depending on conditional um stimula things like that. And the     
1:56:52     
output of a neur of a of a cellular automa you know while it produces     
1:56:58     
patterns is sort of this very general type of process. It's a generative     
1:57:04     
process, but just because it's it's similar to something else doesn't mean     
1:57:09     
that it's actually modeling that thing. It's just coinciding with that thing.     
1:57:14     
So, we could, you know, write a whole paper on, you know, generative processes and emergence and how, you know,     
1:57:21     
depending on the system that you're working with, you know, it might correlate with that. But is it like     
1:57:27     
representing maybe just like a general a generalized um uh emergent process, a     
1:57:35     
generalized um generative process or is it modeling the very you know the the     
1:57:40     
specific system? It could be a biological system or a social system. Is it modeling that or is it modeling this     
1:57:47     
general process of like interaction and outcomes like that?     
1:57:54     
Okay. So um they want to benchmark the developmental model. They've established     
1:58:00     
that developmental models capture biologically grounded link between genetics and fogyny. This work proposes     
1:58:08     
that the same link can support the evolution of intelligent architectures by enabling direct comparisons between     
1:58:15     
model connectivity and biological data. So this is their conga framework. And     
1:58:20     
then when a model solves a task while also exhibiting strong correspondence to brain connectivity, it suggests     
1:58:27     
convergence on principles that underly biological intelligence. So this paper     
1:58:33     
will proceed in two parts. The first presents a developmental modeling approach to brain connectivity and     
1:58:39     
evaluates its correspondence with gene expression. The second proposes Conga is     
1:58:45     
a framework for using developmental models and biological data     
1:58:52     
to guide the evolution of artificial neural architectures. Together, these contributions     
1:58:58     
demonstrate how developmental and evolutionary principles can be integrated to form the design of     
1:59:04     
brain-like AI systems. Okay.     
1:59:09     
So this work sits at the intersection of developmental biology and neuro evolution.     
1:59:15     
So that's kind of where they're sitting. Um now they want to link gene expression     
1:59:21     
to connectivity. So what they're doing is um they're     
1:59:26     
using a specific method for this. So they're not just throwing data at at the model. Um they review some work from C     
1:59:35     
elegance. So um early studies in C elegant show that a neuron's gene     
1:59:40     
expression profile could predict its synaptic partners. The conneto model proposed that wiring     
1:59:47     
motifs such as bike leaks emerge from gene gene compat compatibility rules.     
1:59:53     
Identifying these network level patterns is computational identifying these network level patterns     
2:00:00     
computationally and using them to infer genes involved in circuit formation. The model was     
2:00:07     
later extended to incorporate physical constraints of biological noise. So this is where they looked at mouse retina     
2:00:14     
data as well and they found that this uh works in both systems.     
2:00:21     
Another approach based on bilinear factorization treated gene expression profiles as input to a recommener system     
2:00:28     
for predicting pair wise connection strength. Collectively, these models supported the idea that genetic     
2:00:34     
signatures can include wiring rules and highlighted candidate genes likely to     
2:00:39     
influence circuit assembly in mammals. Limited neuron level resolution has led     
2:00:45     
researchers to focus on region level data when relating gene expression and connectivity. And this is uh true     
2:00:52     
because we just don't have single cell data that can allow us to do this. So we     
2:00:58     
usually use something like a voxil structure. So we'll take a voxil from like a neuroiming study or we'll take a     
2:01:05     
voxil um of data which you know is like a a bunch of things inside of it a lot     
2:01:11     
of neurons a lot of um other types of uh supporting cells and a lot of con uh     
2:01:19     
synaptic connections. And we'll use that as the unit of analysis which you know     
2:01:24     
is kind of a you know it allows you to see connectivity but not single cell     
2:01:30     
connectivity like you might see in C elephants. Early studies found that brain regions     
2:01:36     
of similar gene expression profiles were more likely to be connected and that classifiers trained on gene expression     
2:01:42     
could predict anatomical anatomical connectivity in both mice and rats.     
2:01:49     
And so then there's some later work leveraging the Allen brain atlas that     
2:01:54     
demonstrates a voxal level connectivity could be predicted with high accuracy from local gene expression. The most     
2:02:02     
predictive genes were involved in synaptic function and neural development.     
2:02:07     
Other studies identify transcrytoic features of distinguished network hubs in both mouse and human brains,     
2:02:14     
suggesting potential conversation of wire or suggesting potential     
2:02:19     
conservation of wiring principles across species. So this is where you know we were     
2:02:27     
looking at they were looking at different genes that predicted connectivity. Of course, the most     
2:02:33     
predictive genes were synaptic function function neural development. So that means that you know it's not sort of     
2:02:39     
this artifact where it's, you know, it's it's pretty much related to, you know,     
2:02:44     
it's verifiable that this is a a real signal.     
2:02:49     
While most prior studies use supervised learning to predict connectivity from gene expression, this paper adopts a     
2:02:55     
latent variable formulation. So rather than learning a direct mapping of gene expression and connectivity,     
2:03:02     
this model infers voxal level latent variables or what they call barcodes from the connectivity matrix which are     
2:03:10     
then compared to observed gene expression patterns. So you go from connectivity to this intermediary called     
2:03:16     
of barcodes and then to gene expression. This approach enables testing of     
2:03:22     
competing hypotheses about how connectivity may be genetically encoded.     
2:03:28     
Unlike supervised models which are constrained to define connectivity only in terms of the genetic expression     
2:03:36     
already observed uh latent variable models can uncover spatial codes denovo     
2:03:42     
when coding when such codes align with gene expression they offer compelling candidate explanations for neural layer.     
2:03:51     
So they kind of go over their methods here which is this barcoding. Uh they     
2:03:57     
have some data sets. Uh they use transcrytoic and connetoic data sets from the Allen Institute for Brain     
2:04:04     
Science which offers extensive whole brain measurements. All data are aligned     
2:04:09     
to a common coordinate system allowing latent representations derived from connectivity to be directly compared     
2:04:16     
with voxal level gene expression. So that's what we're doing. So they have this Allen mouse brain atlas data set.     
2:04:24     
Um they're looking at mRNA transcript levels for over 20,000 genes     
2:04:29     
and then they're using expression energy values. Um and they're they have this     
2:04:35     
matrix that assigns each voxal with a highdimensional gene expression vector representing local transcriptional     
2:04:42     
activity. So they have a map of their barcodes here.     
2:04:47     
They have the barcodes, the decoder, the estimate of connectivity, they have a     
2:04:53     
loss function, and then they compare that with brain connectivity. And they try to get this estimate and brain     
2:05:00     
connectivity kind of match together using this loss function. And then they have this. So this is part of a decoder     
2:05:06     
where they have the barcode, they have the source and target. you try to predict the target from the source and     
2:05:12     
that gives you a connectivity matrix or or like a matrix of connectivity.     
2:05:19     
That's our static model right here. Then there's a developmental model     
2:05:26     
which is where we use a seed. We use our neural cellular automa.     
2:05:32     
We then uh evolve this seed um over times. We have T1. We get a result, we     
2:05:39     
feed it back into the NCA. We keep doing this over and over. And then at T100, we     
2:05:45     
get our barcodes. Then we have this decoder which then gives us an estimate at connectivity.     
2:05:52     
And inside the neural cellular automa, which is this green box here, we have a     
2:05:57     
set of inputs which is this four-dimensional space. We get then     
2:06:03     
convolution of that space. we get perception update module and a state     
2:06:09     
update. Okay, so that's kind of how they do that. Um,     
2:06:16     
all right. So this is the gene score comparisons just showing for their     
2:06:21     
different instantiations of this model. They have the static model, the developmental model, the full random     
2:06:28     
model and then the preserved degree model. So the developmental model is has a higher mean gene score overall and     
2:06:36     
then the static model is second. So just showing how this is an SVDbased model.     
2:06:43     
So this is just kind of showing what what comes out of that.     
2:06:48     
They use these randomization baselines here. So they should be expected to be near zero. Um the full random baseline     
2:06:56     
is where it fully shuffles the connectivity matrix destroying all spatial and topological structure while     
2:07:03     
preserving the global distribution of connection points. Then two is degree preservation or degree preserve which     
2:07:10     
rewires the edges to preserve the in and out degree of each ofoxal controlling for effects driven by connection density     
2:07:17     
alone. So they want to really make sure that the underlying gene expression is     
2:07:23     
driving that connectivity. They want to get rid of all artifacts in the connectivity matrix where it might, you     
2:07:30     
know, be based on proximity or some spatial structure, topological structure     
2:07:35     
that's already sort of baked into these interactions.     
2:07:40     
So this is you know this this allows us to get away from potential confounds such as connection density and so forth.     
2:07:50     
So the results are here we have um the representation size and hidden units. So     
2:07:57     
this is a trade-off between model complexity and biological alignment. So as the internal hidden size of the     
2:08:04     
developmental model increases and that inter in hidden sizes in the hidden units     
2:08:11     
uh gene scores decline. So if you look at the upper plot your hidden units your     
2:08:17     
gene score declines and your internal hidden size increases.     
2:08:24     
So this is where the gene score declines. This is where the model I guess um     
2:08:31     
increases or the hidden internal hidden size of the developmental model increases. So you have 200 hidden units     
2:08:37     
here, 100 hidden units here. So the hidden units are increasing and then the gene score is high and low hidden unit     
2:08:45     
sizes but levels off or higher hidden unit sizes.     
2:08:52     
Uh so that's here in this um this first plot.     
2:08:57     
Um but connectivity reconstruction improves uh as you do this. So you know your     
2:09:04     
representation size gets smaller in this in this graph here.     
2:09:10     
Simpler developmental models yield representations of more closely match gene expression and that's here. So in     
2:09:17     
this case we use our gene square. In this case we use graph prediction are squared and we get our hidden units. Um     
2:09:24     
we get level a positive leveling off with the graph prediction are squared     
2:09:30     
and the representation size grows accordingly.     
2:09:35     
So the representations more closely matched gene expression that suggests     
2:09:40     
that the underlying biological process is governed by limited representational complexity.     
2:09:46     
So that as the number of latent variables per voxil in the static model increases the gene score peak at low     
2:09:53     
levels of complexity but the connectivity reconstruction continues to improve. So at the top in this um graph     
2:10:03     
on the upper right um this represents gene scores peaking at a low level of complexity and that     
2:10:09     
just represents where gene scores are relative to the complexity.     
2:10:15     
But in the lower right hand corner here, this figure um the connectivity     
2:10:21     
reconstruction continues to improve regardless. So we're actually measuring two things     
2:10:27     
here. We're measuring the gene score and how faithful it is to the representation     
2:10:32     
and then the complexity of the representation itself.     
2:10:37     
As the static model grows in size, it overfits to the connectivity and its latent variables lose their relevance to     
2:10:44     
gene expression. Okay. So that's um that's some of their     
2:10:50     
results. Then the discussion is that developmental programs can serve as biological models.     
2:10:57     
So you know basically that's their their outcome. His work demonstrates that NCA     
2:11:05     
can learn such developmental programs directly from data, but several limitations constrain the scope of these     
2:11:11     
conclusions. So while developmental models better align gene expression, it     
2:11:16     
should not yet be interpreted as recovering the specific biological program that gives rise to connectivity.     
2:11:22     
As I said before, we can see very similar things, but it doesn't necessarily tell us how that program     
2:11:28     
works or if there even is a program in the first place. Further comparisons are     
2:11:34     
needed to disentangle the contributions of different structural constraints to the observed genetic associations and     
2:11:41     
important direction for future work. Further, the genetic and contoic data are sourced from a snapshot in time.     
2:11:49     
biological systems many transcription factors are transient disappearing once their developmental role is complete. So     
2:11:56     
this is interesting because you know transcription factors are not um static     
2:12:02     
things like I said they sometimes vary by context and a lot of times there's     
2:12:08     
stuff that is transiently functional or transiently expressed. So if we're     
2:12:14     
measuring uh mRNA as a measure of transcription, there are a lot of mRNAs     
2:12:20     
that show up and sometimes they're very ubiquitous, but they don't necessarily have a function or they don't function     
2:12:26     
the same way other mRNAs with a known function. So sometimes mRNAs are very um     
2:12:32     
specific have a specific target you know um they do things that are     
2:12:39     
that really can be predicted by say like phenotypic function or quai phenotypic     
2:12:44     
function like with this NCA but sometimes they're just expressed and they're expressed everywhere and they're     
2:12:51     
just expressed because they are u I'm thinking of housekeeping genes where the expression of housekeeping genes exist     
2:12:58     
just sort of is like something in the background, something that's maybe maintaining the cell instead of like     
2:13:03     
doing something functional. So that's kind of where this this     
2:13:09     
there's a problem here with thinking u you know that this relationship is one     
2:13:15     
to one or that you can really kind of um you know that there there are a lot     
2:13:22     
of like shortcomings to thinking about sort of this mapping between the     
2:13:29     
computational model and the biology but also that these uh biological systems     
2:13:34     
these gene regulatory networks constitute a program in the same way that we have a computer program for     
2:13:39     
example. Um so further the genetic and conneto     
2:13:45     
data are sourced from a snapshot in time. So usually we sample these systems     
2:13:50     
from one snapshot in time. We take conneto from like one mouse one period     
2:13:57     
of of development or life history. The same thing even more so with gene     
2:14:02     
expression data. And so you know it's hard to like uh really give     
2:14:08     
you know infer dynamic states from these kinds of data.     
2:14:14     
In biological systems many transcription factors are transient of course we talked about that. Um moreover the     
2:14:21     
connectivity is decoded from the barcodes all at once rather than in sequential growth cone processes as we     
2:14:27     
see in biology. So they're referring to here is that if you look at an axon finding, there's a growth cone that     
2:14:34     
forms in front of the axon and it sort of uh decodes the information of the     
2:14:40     
envir of the molecular environment in the developing brain and it tells the     
2:14:48     
axon kind of where to find its partner or where to find its affinity. So it does these sort of chemotaxic behaviors     
2:14:56     
to find partners to wire up to. So once that's that happens and you establish a     
2:15:02     
connection between two neurons and you get the results that you see in the data that we have and then reproduce in the     
2:15:10     
NCA. So this is where you know this is all to say that um we have this separate     
2:15:18     
process in biology. we're not modeling and so you know we can't rely on the     
2:15:23     
barcoding methodology uh too literally. You have to think of it as a very loose analogy.     
2:15:30     
Additional limitations include the use of oxalized data of course and the lack of distinction between synaptic and     
2:15:36     
non-synaptic connections. So of course synaptic connections and non-synaptic connections or defining your conneto     
2:15:43     
that way can be be very it can result in a very different conneto and very different wiring behaviors.     
2:15:51     
Um so yeah we can resolve some of these issues but they're still outstanding. And so thinking about high resolution     
2:15:58     
microscopy as maybe a solution to finding synaps level contos, we can go     
2:16:03     
to small model organisms such as Drosophila where we can use this sort of     
2:16:09     
method to find you know relatively large for small     
2:16:15     
organisms. Um we could find relatively large connetos and analyze those. So you     
2:16:22     
know in the microns project they've been extending the methods that have been uh     
2:16:28     
working this out in in Rosophila uh to mamalian tissues and trying to res     
2:16:35     
reconstruct cubic millimeters of mouse cortex and you know in different regions     
2:16:42     
of the uh neoortex and trying to build conneto really     
2:16:48     
informative connetos from There also axon tracing methods and the     
2:16:54     
Allen data set provides some axon tracing methods and you can also use other methods such as map seek and seek     
2:17:00     
which are these nextgen sequencing platforms to match up to those kinds of data sets.     
2:17:08     
So this is a nice diagram here from biology to AI conneto generating AI     
2:17:13     
generating algorithms which is this uh method that they they propose. Um so they have this these     
2:17:23     
three paradigms for building AGI. So the cognitive approach which is at     
2:17:29     
the top constructs intelligence systems by assembling cognitive modules which     
2:17:34     
you see here as sort of these puzzle pieces that lock together that suffers from a limited understanding of the     
2:17:41     
brain's modular functional architecture. So at the right on the left you have this puzzle. The puzzle pieces are put     
2:17:47     
together. This is a nice model of brickage and cognition where you have these different components that fit     
2:17:53     
together. And it's tempting to say those are cognitive modules that each part of the of the brain does something and that     
2:18:01     
they all kind of work maybe together but they all kind of work separately as well. And that's that's cognition. But     
2:18:08     
we don't really understand the contents of those modules, how they develop or even if they are modules in the first     
2:18:14     
place. they may have connections to other functions to other modules that we don't understand.     
2:18:20     
So that's one approach and they kind of you know there are all sorts of debates about you know cognitive modularity and     
2:18:27     
things and so they kind of want to move away from that. Um the middle uh     
2:18:32     
approach is the emergent approach. So instead of assuming the sort of bricklage or function     
2:18:38     
uh you assume that there's this emerging process where we might use something of     
2:18:44     
reinforcement learning and task environments to produce intelligent behavior. So this is a video game     
2:18:50     
joystick and this is a robot. Robot plays the video game. It's better at it. Learns the policies and optimizes that     
2:18:57     
to get you know cognition basically or AGI.     
2:19:03     
The problem with the emerging approach of course is we don't have a complete understanding of the relevant ecological     
2:19:09     
pressures and so without that understanding such task design is     
2:19:14     
difficult. So this is where we have no idea what the inputs should actually     
2:19:19     
look like. So the robot doesn't achieve AGI not because it doesn't have the architecture to do so but because it     
2:19:25     
doesn't understand its ecological constraints in its environment and how to act them.     
2:19:32     
Then finally the connetoic approach at the bottom grounds the architectural search and real brain wiring data which     
2:19:39     
is here this conneto using the conneto to shape the design of the task     
2:19:44     
environment which is this joystick and then the developmental program     
2:19:49     
generates architectures which are on the right that are trained at the task and then that maps back to the real brain     
2:19:58     
wiring data and that's how we have these kind of ag GI models from conneto. So     
2:20:05     
it's approaching it by saying we can take like a biological conneto. We can     
2:20:10     
train it in different ways and we can produce this cognitive architecture that     
2:20:15     
then goes back to the conneto to see what the dynamic behavior of the conneto is and we keep shaping it appropriately.     
2:20:24     
So they actually in the cognitive approaches they mentioned that cognitive architectures like actar and soore and     
2:20:31     
open cog hyperon are sort of in this category where we make assumptions about     
2:20:38     
the architecture through sort of these modules and then we fit them together but we don't necessarily look underneath     
2:20:45     
the hood to see what's driving the behav sort of the the formation of the function of these modules. it's just     
2:20:51     
kind of behavior based. Um, so this is something that, you know, cognitive approaches are, you know, they     
2:20:58     
do interesting things, but they're not really necessarily um they don't rely on     
2:21:05     
a principal taxonomy of mental functions. Emerging approaches are what they refer     
2:21:11     
to as things like GPT4 or um AI uh gas, which are genetic     
2:21:18     
algorithms. Um, and so this is where intelligent systems can be evolved jointly by jointly optimizing     
2:21:25     
architectures, learning rules, and training environments in an open-ended loop.     
2:21:31     
So this the systems shift the design burden from the agent to the world. But in doing so, they assume the environment     
2:21:37     
itself is rich enough to produce general intelligence, an assumption that may not hold without strong inductive biases.     
2:21:45     
That's an important point. We don't think too much about the world in ter when we talk about agentive programming     
2:21:52     
or agentive modeling but that's that's kind of the assumption that's where at rest the power of these models rest     
2:21:59     
ultimately is in the world. Um then the connetoic approach of course is this     
2:22:05     
approach where these biological connetos to train a model and then produce but     
2:22:12     
they also rely on the environment as this intermediary to shape what that     
2:22:17     
cognitive model will look like. And so this forms the basis of the proposed conga framework which incorporates     
2:22:24     
biological structure as an explicit constraint on the evolutionary process.     
2:22:30     
So that's all we have. This is the conclusion and you know that I think     
2:22:36     
they kind of have made their case for using um the NCAs as as sort of a the     
2:22:46     
basis for their computational model that links you know where they have the conneto and then they try to match that     
2:22:52     
to the NCA which is their uh their cognitive model and then they have     
2:22:57     
feedback between them. So that's that's I thought that was a really interesting     
2:23:02     
paper and we had talked about like kind of the state-of-the-art at Gecko. So um     
2:23:08     
I think Morgan you're muted so if you want to Yeah. No, I mean it's it's it's a super     
2:23:13     
interesting Yeah, it's like very very creative um     
2:23:22     
linking of of you know some some concepts. But uh yeah, it's still     
2:23:29     
definitely still one of those those ones where it's like I feel like I need to     
2:23:35     
play with it computationally to Yeah. to really get my head around it.     
2:23:40     
Yeah. You know, Yeah. Um and Yeah. But you know, the the     
2:23:48     
um so I I'll set it as a as a project where it's just like okay, you know,     
2:23:54     
these these tools should give me the ability to to     
2:24:01     
actually set that up and and play with it, you know, right?     
2:24:06     
Yeah. Like like regardless of whether those guys actually give me code or not, right?     
2:24:14     
Yeah. I I Yeah, for sure. For sure. But but very     
2:24:21     
very interesting. You're right. I think that's all for today. I've come across that PI before.     
2:24:28     
Oh yeah. Yeah. I I I I forget why or like like it's definitely come up before.     
2:24:34     
Oh. Yeah. Yeah. He's been working on this for a while. Stuff     
2:24:40     
like neuroeolution and and other types of approaches like that. So Okay. That's of course a subset of     
2:24:46     
evolutionary programming where they're trying to use neural networks to guide     
2:24:51     
sort of or using evolutionary algorithms and and neural networks to guide search and     
2:24:58     
things like that. Yeah. I I think it it came you know when my wife was doing you know her her     
2:25:06     
masters with with Richard Watson. Oh yeah. And you know and it was very Yeah. like     
2:25:14     
like so deep dives with like Jeff Cloon and     
2:25:20     
um you know Ken Stanley those those kinds of um     
2:25:28     
those kinds of researchers you know like but you do see that at Gecko.     
2:25:35     
Yeah. Yeah. Cool. All right. All right. Thanks for the     
2:25:42     
conversations and I see Jesse had to leave, but thanks Jesse for the updates.     
2:25:47     
And uh talk to you next week. Yeah. Take care. Take care. Bye. Bye.
