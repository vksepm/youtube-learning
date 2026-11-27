# Enriched Interleaved Transcript: How 21 People Built a $100M+ Agent Company — Quinn Slack, Amp
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=Xyb1Bn_L2U4
**Model:** `gemini-4-hydrogen` | **Processing Mode:** `agentic`

---

## [00:00 - 00:12] Scene #1: AI Engineer Code Summit
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Opening title sequence on black background displaying the 'AI Engineer Code Summit' logo, followed by 'PRESENTED BY Google DeepMind' and a 'PLATINUM SPONSORS' grid showing logos for aws, Devin, databricks, exa, FACTORY, and Sonar.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; PLATINUM SPONSORS ; aws ; Devin ; databricks ; exa ; FACTORY ; Sonar
> * **Structured Reconstruction:**
>   Opening Title Sequence:
>   1. AI Engineer Code Summit
>   2. PRESENTED BY Google DeepMind
>   3. PLATINUM SPONSORS: aws, Devin, databricks, exa, FACTORY, Sonar

**🎙️ Spoken Transcript:**

💡 **Visual-Speech Alignment:** Silent conference intro sequence preceding the speaker's entrance.

---

## [00:13 - 01:43] Scene #2: Agents Change Everything
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Initially shown in wide stage view (00:13-00:15) before transitioning to a picture-in-picture layout with Quinn Slack speaking on the left and the slide filling the right. The slide displays two top-level bullets above two side-by-side black cards: on the left, an oscilloscope waveform graphic with 'Everything will change' across the center; on the right, an early terminal/agent session log. Across the bottom is a milestone timeline spanning Jan 2025 to Today (21 co-founders).
> * **On-Screen OCR:** Agents Change Everything ; How software is built, sold, and distributed ; How teams are organized to build it ; Everything will change ; Jan 2025: Amp starts ; Sep 2025: Spin-out decided ; Nov 2025: On our own ; May 2026: Spin-off done ; Today: 21 co-founders ; A Company Built Around the Agent ; Quinn Slack / CEO amp
> * **Structured Reconstruction:**
>   Agents Change Everything
>   - How software is built, sold, and distributed
>   - How teams are organized to build it
>   
>   Timeline:
>   Jan 2025 (Amp starts) -> Sep 2025 (Spin-out decided) -> Nov 2025 (On our own) -> May 2026 (Spin-off done) -> Today (21 co-founders)

**🎙️ Spoken Transcript:**
* **[00:13]** All right. Uh, there was a moment in January of 2025 when I was just coding.
* **[00:20]** And I wanted to see what if you just make an agent? This was before Claude Code. And it was like the dumbest stuff ever. It was like, change this background color. But it just blew my mind when I saw an agent
* **[00:30]** actually work for the first time. It ran commands. It looked at itself. It gave itself its own feedback loops. That blew my mind. And I had this sense, I think
* **[00:40]** that everyone has when they first see an agent, that everything is going to change after that. Everything is going to change about how you build software. I think we've all felt that. Everything
* **[00:50]** is going to change about how you form companies to work on software. And how you sell software. How you distribute software, all other work is going to change. And it was just
* **[01:00]** an absolutely crazy, crazy moment. Um, I was actually at the Frankfurt Airport with Thorsten Ball on our team. Um, he wrote that compiler book, anyone, who knows Thorsten
* **[01:10]** on our team? Yeah, he's a cool guy. Um, we were just like minds-blown at the Frankfurt Airport and we knew that everything was going to change. We didn't know where this was all going to go, but we just wanted
* **[01:20]** to go, we just wanted to go run at it. So inside of Sourcegraph, which was a 200-person enterprise software company, I was the CEO.
* **[01:30]** And we made code search, we decided to just start building this, to tune out everything else, and just start building this thing, not go to sales calls, not go to like exec
* **[01:40]** meetings, none of that stuff, just tune out all the distractions.

💡 **Visual-Speech Alignment:** The speaker's recollection of building a primitive agent in January 2025 ('change this background color') and realizing 'everything is going to change' aligns directly with the 'Jan 2025 Amp starts' timeline marker, the 'Everything will change' waveform graphic, and the right-hand terminal screenshot.

---

## [01:44 - 02:31] Scene #3: I was the CEO. I could change anything.
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Dark-background animated organizational chart starting with a headshot of Quinn Slack labeled 'CEO (Sourcegraph · ~200 people)' at the top, branching to 'Engineering · 75', 'Sales & Marketing · 75', and three smaller department blocks. Over the first 12 seconds of the slide, green dots populate a separate circular node on the far right labeled 'Amp · 1' (01:44), 'Amp · 6' (01:48), 'Amp · 17' (01:52), and finally 'Amp · 20' (01:56).
> * **On-Screen OCR:** I was the CEO. I could change anything. ; CEO ; Sourcegraph · ~200 people ; Engineering · 75 ; Sales & Marketing · 75 ; Amp · 1 ; Amp · 6 ; Amp · 17 ; Amp · 20
> * **Structured Reconstruction:**
>   flowchart TD
>       CEO["CEO (Sourcegraph ~200 people)"] --> Eng["Engineering (75)"]
>       CEO --> Sales["Sales & Marketing (75)"]
>       CEO --> Other["Other Departments (~30)"]
>       CEO --> Amp(("Amp (1 -> 6 -> 17 -> 20)"))

**🎙️ Spoken Transcript:**
* **[01:44]** And I was in this position that I think a lot of people say, you know, wow, you know, I'm a software developer in a company
* **[01:50]** and I want to change, I want my company to be more AI-forward and I can't. Um, you know, I was the CEO, and in theory I could change anything, I could change teams, I could say you don't need to get pull requests,
* **[02:00]** code review. Uh you don't need to you know do any of the other processes we used to do. And yet it was very hard what we did. As we ended up taking 20 people uh from the
* **[02:10]** company and inside of Sourcegraph still we made a little team, the Amp team. And uh that's what we tried. So for those of you who are trying to push back against your company
* **[02:20]** to try to make it more agent friendly, I have a lot of sympathy for you and I hope that you can take away some things from here. Um, I know how hard it is and also, have some empathy for your CEO
* **[02:30]** too, it's hard for them too. This is a really hard kind of change and transformation.

💡 **Visual-Speech Alignment:** The speaker points to his role as CEO of the ~200-person Sourcegraph org while the animation visually pulls 20 people out of the traditional org chart into the green 'Amp · 20' circle.

---

## [02:32 - 03:15] Scene #4: Enterprise-ready vs. frontier
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Comparison slide with a dark center panel containing two columns—'Enterprise-ready' (marked with red X icons) and 'Frontier' (marked with green checkmarks)—and an overlaid callout fragment on the left showing 'Predictable costs' and 'Make the lawyers and security team happy'.
> * **On-Screen OCR:** Enterprise-ready vs. frontier ; Enterprise-ready ; Customize and user model choice ; Self-hosted, single-tenant ; Build for every dev, even in the enterprise ; Predictable costs ; Make the lawyers and security team happy ; Frontier ; Run the best model, no admin nerfing ; Multi-region cloud/site ; Build for and amplify the devs who get it ; Maximum impact, consumption pricing ; Make the customer CEO and devs happy
> * **Structured Reconstruction:**
>   | Enterprise-ready (X) | Frontier (✓) |
>   | --- | --- |
>   | Customize and user model choice | Run the best model, no admin nerfing |
>   | Self-hosted, single-tenant | Multi-region cloud/site |
>   | Build for every dev, even in the enterprise | Build for and amplify the devs who get it |
>   | Predictable costs | Maximum impact, consumption pricing |
>   | Make the lawyers and security team happy | Make the customer CEO and devs happy |

**🎙️ Spoken Transcript:**
* **[02:32]** But we knew that there are some things that were going to change. And this all seems kind of obvious now, but back in
* **[02:40]** 2025, early 2025, with this idea of enterprise ready, you do this thing and then you can build a sales team and go sell it. We knew that that was just going to totally die off. You had to be
* **[02:50]** on the frontier. If you had, you know, a taste of success and then you started doing all the enterprise checklist bullshit to make the median enterprise buyer happy, your
* **[03:00]** product was going to go obsolete in like three months. And the whole game had to change. Nothing mattered other than making it so that the people at these other companies loved
* **[03:10]** your product and the CEO, the budget was infinite and all bets were off. So we knew that. We didn't quite know uh all the challenges we'd run into.

💡 **Visual-Speech Alignment:** The spoken critique of the 'enterprise checklist bullshit to make the median enterprise buyer happy' corresponds to the red-X 'Enterprise-ready' list, while 'making it so that the people at these other companies loved your product and the CEO' aligns with the bottom green checkmark: 'Make the customer CEO and devs happy'.

---

## [03:16 - 04:03] Scene #5: "How is this better?"
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide displaying three X (Twitter) post screenshots questioning how Amp or Orbs differ from Codex, Claude Code, or Conductor.
> * **On-Screen OCR:** "How is this better?" ; No intellectually honest way to answer that ; Georgios Konstantopoulos (@gakonst): Is Amp better than Codex and Claude Code? (6:05 PM · Dec 5, 2025 · 30.2K Views) ; Gustavo Barbieri (@gsbarbieri): Advantages over plain codex? Just took a look, seems to cover the same things, similar UX (9:36 AM · Aug 11, 2026 · 131 Views) ; Matt Attanasio (@mattymaddog_89): Why are orbs better then conductor remote workspaces? I can use my own subscription in conductor. Tell me why I should switch? (1:35 AM · Oct 10, 2026 · 934 Views)
> * **Structured Reconstruction:**
>   "How is this better?" — No intellectually honest way to answer that
>   - @gakonst (Dec 5, 2025): Is Amp better than Codex and Claude Code?
>   - @gsbarbieri (Aug 11, 2026): Advantages over plain codex? Just took a look, seems to cover the same things, similar UX
>   - @mattymaddog_89 (Oct 10, 2026): Why are orbs better then conductor remote workspaces? I can use my own subscription in conductor. Tell me why I should switch?

**🎙️ Spoken Transcript:**
* **[03:16]** Um, also, you know, in this world where agents can build a product or build a feature, how do you even think about differentiation? I mean to this day there's people who say, well why is Amp better? Why
* **[03:30]** is, you know, Claude Code better than Codex or whatever. And so many people are begging to have the answer in the form of, well, it's these three features, you know, uh Amp has Orbs which are really
* **[03:40]** good cloud agents and we have multiplayer. But the crazy thing is, you all know that if we can do that and we prove it, then any of our competitors could as well. So, you know, why even play
* **[03:50]** that game? Like what does it even mean to build and sell software, why would you go and hire a sales team, why would you go and do anything in the traditional way if you don't even know what it's going to look like in a month?
* **[04:00]** And if you don't even know how to describe differentiation, there's no sustainable differentiation.

💡 **Visual-Speech Alignment:** The speaker cites the exact questions shown in the three tweets—comparing Amp to Claude Code/Codex and asking why Orbs are better—to illustrate why feature-list differentiation fails when agents replicate features rapidly.

---

## [04:04 - 04:31] Scene #6: Then they used it
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide showing four follow-up X (Twitter) posts from developers and skeptics praising Amp after actually trying it, including two posts from Georgios Konstantopoulos, one from Tailwind creator Adam Wathan, and one from Matt Attanasio.
> * **On-Screen OCR:** Then they used it ; Georgios Konstantopoulos (@gakonst): ... @_AmpCode is by far for me and the rest of Tempo eng team the best agent we've used. ... (1:19 PM · Jan 22, 2026 · 25K Views) ; Georgios Konstantopoulos (@gakonst): It's really hard to understand how ahead of the curve @AmpCode was in January (4:52 AM · Sep 2, 2026 · 13.2K Views) ; Adam Wathan (@adamwathan): Building software in anything other than @AmpCode orbs feels like eating broken glass in comparison. But it's frustratingly one of those "you can't understand why it's better until you use it" tools, a lot like Tailwind was. Use it, and be ruined. (6:09 PM · Oct 9, 2026 · 216K Views) ; Matt Attanasio (@mattymaddog_89): Ok after using @AmpCode for the last couple of days I can say it's awesome, I get it now ... (7:29 PM · Nov 6, 2026 · 156 Views)
> * **Structured Reconstruction:**
>   Then they used it:
>   - @gakonst (Jan 22, 2026): @_AmpCode is by far for me and the rest of Tempo eng team the best agent we've used.
>   - @gakonst (Sep 2, 2026): It's really hard to understand how ahead of the curve @AmpCode was in January
>   - @adamwathan (Oct 9, 2026): Building software in anything other than @AmpCode orbs feels like eating broken glass in comparison... "you can't understand why it's better until you use it"...
>   - @mattymaddog_89 (Nov 6, 2026): Ok after using @AmpCode for the last couple of days I can say it's awesome, I get it now ...

**🎙️ Spoken Transcript:**
* **[04:04]** Um, for Amp, you know, people end up loving it. Um, but you can even see like, um, you know, Adam Wathan, who's the uh Tailwind guy, he
* **[04:10]** loves Amp, but he's like, you know, it's one of those things where you can't understand it. Uh, you you know, it's you can't understand why it's good until you use it. Can you imagine
* **[04:20]** having a whole product management team, a design team, an engineering team that's so disconnected from the actual customers, a whole company apparatus, if that's the best way that you can market
* **[04:30]** a product, it's really tough.

💡 **Visual-Speech Alignment:** The speaker directly paraphrases Adam Wathan's tweet on the top right ('you can't understand why it's better until you use it').

---

## [04:32 - 06:03] Scene #7: Old-fashioned companies vs. companies of the future
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Two-column dark comparison slide contrasting 11 practices of an 'OLD-FASHIONED COMPANY' (muted gray text on left) against a 'COMPANY OF THE FUTURE' (bright white/green text with green arrow icons on right).
> * **On-Screen OCR:** Old-fashioned companies vs. companies of the future ; OLD-FASHIONED COMPANY ; Mandatory PRs and human code review ; Departments, executives, PMs ; Roadmaps, quarterly goals, themes ; Sprint planning and points for bugs ; RFCs, PRDs, design docs ; Many standing meetings ; Hiring as the fix ; Support, accounting, and CRM SaaS ; The local dev environment ; Gossip channels ; Token budgets ; COMPANY OF THE FUTURE ; Push to main, agent proof, feature flags ; One team, everyone does everything ; Weekly discussions. Do what gives you energy. ; Fix it now ; The news post ; One meeting a week ; Reprioritize, skin in the game grows you ; Softer-than-software mini apps running in Amp boxes ; Orbs ; Call it out in the open ; No token limits
> * **Structured Reconstruction:**
>   | OLD-FASHIONED COMPANY | COMPANY OF THE FUTURE |
>   | --- | --- |
>   | Mandatory PRs and human code review | Push to main, agent proof, feature flags |
>   | Departments, executives, PMs | One team, everyone does everything |
>   | Roadmaps, quarterly goals, themes | Weekly discussions. Do what gives you energy. |
>   | Sprint planning and points for bugs | Fix it now |
>   | RFCs, PRDs, design docs | The news post |
>   | Many standing meetings | One meeting a week |
>   | Hiring as the fix | Reprioritize, skin in the game grows you |
>   | Support, accounting, and CRM SaaS | Softer-than-software mini apps running in Amp boxes |
>   | The local dev environment | Orbs |
>   | Gossip channels | Call it out in the open |
>   | Token budgets | No token limits |

**🎙️ Spoken Transcript:**
* **[04:32]** So we knew that we just had to change everything, and we rethought so many things, because kind of unintentionally, we were
* **[04:40]** under some weird constraints. We decided to spin out Amp. So for those of you who have been at a company, at like a small, uh, you know, you're on a small team in a company and you're trying to do things different,
* **[04:50]** you're trying to be the startup within a startup, you probably have these fantasies of let's just go off and start a new company. Well, we actually did that. We, you know, did the right thing by investors and employees and everyone has
* **[05:00]** ownership in both, but we actually spun out and for a year until last Friday, we couldn't hire anyone. We couldn't grant options. The legal spin-off process was a huge pain. And we were forced to make do with the 21 people that we brought
* **[05:10]** over. We didn't have time in this crazy competitive environment to do, you know, we couldn't move as slowly in order to do um, you know, mandatory pull requests. We couldn't have meetings. We couldn't have our time be sucked up by enterprises that would need to take, you know,
* **[05:20]** many months to sign on something. And so we were forced into this radically different way of working. And we also had this environment where every single person on the team has a huge stake in the company. And
* **[05:30]** that skin in the game that you get when AI makes it so that you can operate with way less people, skin in the game, it's like this spiritual thing for the soul of great people. It makes them better at everything they do. It makes them grow faster, and
* **[05:40]** so this is what we have seen. This, I think, when you've seen a company that operates like this without any of that bullshit, it's
* **[05:55]** obvious how companies like this are going to crush everyone else and how every company in the future is going to look a lot more like that.

💡 **Visual-Speech Alignment:** While discussing the spin-out constraints, Quinn highlights items directly from the table: abandoning 'Mandatory PRs', eliminating 'Many standing meetings', and how 'skin in the game grows you' replaces 'Hiring as the fix'.

---

## [06:04 - 06:15] Scene #8: So we spun Amp out
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide detailing the spin-out of Amp Frontier Corporation. On the left are two overlapping screenshots: a dark header graphic for 'Amp Frontier Corporation' and a #amp chat message from Quinn Slack dated Friday, November 14th, 2025. On the right are two bullets, with the five-stage company timeline anchored at the bottom.
> * **On-Screen OCR:** So we spun Amp out ; An accident of history: it took 8 months ; We couldn't hire. We invented how we work. ; Amp Frontier Corporation ; #amp · amp ; Friday, November 14th, 2025 ; Quinn Slack: BTW, when I am sharing this news with customers, I say that this will also let Amp keep building for people who want to live on the frontier, who want to use Amp the way everyone will be using a coding agent 1 year from now—not be watered down by needing to be palatable for every single dev at every single enterprise. ; Jan 2025: Amp starts ; Sep 2025: Spin-out decided ; Nov 2025: On our own ; May 2026: Spin-off done ; Today: 21 co-founders
> * **Structured Reconstruction:**
>   So we spun Amp out
>   - An accident of history: it took 8 months
>   - We couldn't hire. We invented how we work.
>   
>   Announcement (Nov 14, 2025): Amp Frontier Corporation spun out to keep building for people on the frontier rather than being watered down for every enterprise dev.

**🎙️ Spoken Transcript:**
* **[06:04]** So, yeah, we spun Amp out and we had to figure out a lot of new
* **[06:10]** ways of working with these constraints that we had no idea that we were going to be under. And we couldn't hire as I said.

💡 **Visual-Speech Alignment:** The speaker transitions directly into explaining the 8-month spin-out and hiring freeze shown on the slide.

---

## [06:16 - 06:47] Scene #9: We didn't hire our way here
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Data slide featuring a log-scale line chart on the left titled 'Employees, 2026 (log scale)' spanning Jan through Oct 2026, showing Amp remaining flat at 21 (green line) while multiple competitors ('The other guys', dark red lines) grow from hundreds into the thousands. Four key metrics and takeaways are listed on the right.
> * **On-Screen OCR:** We didn't hire our way here ; Employees, 2026 (log scale) ; 10,000 / 1,000 / 100 / 10 / 1 ; Jan Feb Mar Apr May Jun Jul Aug Sep Oct ; Amp: 21 ; The other guys ; More than $100M ARR, very fast ; Built to be profitable ; 1/10 to 1/30 the headcount ; When hiring isn't an option, you work differently
> * **Structured Reconstruction:**
>   | Metric / Entity | 2026 Trend (Jan–Oct) | Scale |
>   | --- | --- | --- |
>   | Amp | Flat at 21 employees | 1/10 to 1/30 the headcount |
>   | The other guys | Steep growth from ~200–1,000+ up to ~2,000–5,000+ | Log scale (1 to 10,000) |
>   | Amp Revenue | >$100M ARR, very fast | Built to be profitable |

**🎙️ Spoken Transcript:**
* **[06:16]** So, as a result, while our—this is a log chart by the way—while, you know, all the other big competitors in the space were growing and building old-fashioned companies in order to go and exploit this amazing technology of AI,
* **[06:30]** we had to stay at 21 people. But that was awesome because it was a forcing function for us to work differently and to figure out how can you do so much more with an agent where we couldn't hire people. There's actually
* **[06:40]** one guy who was like, I don't care that I can't get options for like eight months and I'm going to come join, and Hamish is pretty awesome.

💡 **Visual-Speech Alignment:** Quinn explicitly points out 'this is a log chart by the way' while contrasting the flat green 'Amp: 21' line against the rising red lines for 'The other guys'.

---

## [06:48 - 06:59] Scene #10: Old Way -> New Way
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Section divider slide featuring a textured metallic orb with radiating tick lines on the left and large dark typography 'Old Way -> New Way' with subtitle 'Agents reshaped how we build' on the right.
> * **On-Screen OCR:** Old Way -> New Way ; Agents reshaped how we build
> * **Structured Reconstruction:**
>   Section: Old Way -> New Way
>   Subtitle: Agents reshaped how we build

**🎙️ Spoken Transcript:**
* **[06:48]** So I want to talk about the ways in which we built Amp, which is our agent product, around the way that these constraints forced us to work and how we grew up around the agent here.

💡 **Visual-Speech Alignment:** Transition slide introducing concrete examples of how agents reshaped Amp's engineering and operational workflows.

---

## [07:00 - 07:15] Scene #11: The thread is where the work happens
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Screenshot of a real multiplayer Amp thread ('Spaces v1', 13,186 messages) where team members Lewis and Hitesh discuss accidentally sending prompts into each other's threads, the Amp agent summarizes their messages without interrupting, and Brent asks if the tab can show an indicator of the thread requester.
> * **On-Screen OCR:** The thread is where the work happens ; EXAMPLE FROM A REAL THREAD ; Spaces v1 ; ampcode.com/threads/T-1c7641ba-570b-444f-85fe-b8bb4be14483 · project-quick · 13,186 messages ; Lewis: @here I accidentally sent some prompts into @Hitesh's threads today - I think navigating into a space and it opens on the last thread you had open is sometimes convenient but often confusing ; Hitesh: @Lewis I did the same thing to @Tim's thread ampcode.com/threads/T-042706ed... 10 mins after you accidentally sent to my thread ; Agent: Lewis and Hitesh are telling the team, with @here and to each other, that they each sent prompts into someone else's thread by mistake. Lewis thinks a Space reopening on the last thread you had open is often confusing. They didn't ask Amp anything, so I started no work and didn't post or react ... ; Brent: Could we possibly show some sort of indication of thread requester in the tab? Maybe as a badge on the orb icon? Not sure
> * **Structured Reconstruction:**
>   Thread: Spaces v1 (project-quick, 13,186 messages)
>   Lewis -> @here: accidentally sent prompts into @Hitesh's threads today...
>   Hitesh -> @Lewis: did the same thing to @Tim's thread...
>   [Amp Agent]: Summarizes conversation passively; takes no action since not asked.
>   Brent -> Amp: Could we possibly show some sort of indication of thread requester in the tab? Maybe as a badge on the orb icon?

**🎙️ Spoken Transcript:**
* **[07:00]** We got rid of all of the other tools. We got rid of all of the other things you got to check, obviously not Jira, no task tracking, we don't have a support system. Everything we do in the
* **[07:10]** agent. In Amp they're called threads. We even communicate in the agent.

💡 **Visual-Speech Alignment:** The speaker explains that team communication happens directly inside Amp threads while displaying a real multiplayer thread where Lewis, Hitesh, and Brent talk to each other and the agent listens in.

---

## [07:16 - 07:27] Scene #12: The thread is where the work happens
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Continuation of the 'Spaces v1' thread showing the agent picking up Brent's suggestion, starting 'Requester on Space thread tabs', building a prototype displaying the thread owner's avatar on the tab icon for threads that aren't yours, and rendering a live UI preview of the browser/tab bar ('Auth cleanup', 'Fix login redirect loop', 'Add new limit to login endpoint · Hitesh Soghom's thread').
> * **On-Screen OCR:** The thread is where the work happens ; EXAMPLE FROM A REAL THREAD ; Brent: Could we possibly show some sort of indication of thread requester in the tab? Maybe as a badge on the orb icon? Not sure ; Create thread: Requester on Space thread tabs ; I've started Requester on Space thread tabs. I'll try a few ways to show whose thread a tab is, such as their avatar on the tab icon, and only when it isn't yours. ; Showing whose thread a tab is in a Space is built and ready to review in the thread, not shipped. It only appears on threads that aren't yours ... ; Auth cleanup ; Fix login redirect loop ; Add new limit to login en... ; Add note limit to login endpoint · Hitesh Soghom's thread
> * **Structured Reconstruction:**
>   Brent: Could we possibly show some sort of indication of thread requester in the tab?
>   -> Agent spawns sub-thread: 'Requester on Space thread tabs'
>   -> Implements avatar badge on Space thread tab icons (only for threads that aren't yours)
>   -> UI Tabs preview: [Auth cleanup] [Fix login redirect loop] [Add new limit to login en... (Tooltip: Add note limit to login endpoint · Hitesh Soghom's thread)]

**🎙️ Spoken Transcript:**
* **[07:16]** You can say, um, you know, I made a—something's bad in the product, let's do it, the agent can listen to everything and then
* **[07:20]** go fix it. If you're in like a local agent that runs on your laptop, you can't bring someone else in if you realize you're in over your head. Really valuable.

💡 **Visual-Speech Alignment:** Demonstrates the agent listening to a casual bug/UX complaint in a shared thread and immediately building a feature ('Requester on Space thread tabs') ready for review.

---

## [07:28 - 07:41] Scene #13: No code review. Push to main.
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide displaying a green bar chart titled 'Production deploys per day' showing roughly 130 deploys daily and a ~10-minute median time from push to production. Right-hand bullets include the quote '"The code review process is what creates the risk."' (Note: at 07:33-07:35, the presenter briefly advances to the next slide before clicking back to finish introducing this slide.)
> * **On-Screen OCR:** No code review. Push to main. ; Production deploys per day ; ~130 deploys a day ; ~10 min median, push to production ; "The code review process is what creates the risk."
> * **Structured Reconstruction:**
>   | Deployment Metric | Value |
>   | --- | --- |
>   | Production deploys per day | ~130 deploys a day |
>   | Median time from push to production | ~10 min |
>   | Code review policy | No code review; push to main |

**🎙️ Spoken Transcript:**
* **[07:28]** We push way too often, um, and I want to show, you know, how we actually reduce the risk here, because you might say—let me, let me start that again. You might say, well if you're pushing constantly,
* **[07:40]** then how do you not take down the site all the time?

💡 **Visual-Speech Alignment:** The speaker addresses the apparent contradiction of ~130 daily pushes to main without code review, pausing briefly at 07:33 to rewind a premature slide click and re-frame the risk argument.

---

## [07:42 - 08:37] Scene #14: In the time one change waits for review...
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Animated timeline diagram contrasting 'Old way: pull request + human review' against 'New way: push to main, agent proves it works'. On the top track, one large change moves through 'Write' -> 'Waiting for review' -> 'Fix' -> 'Waiting again' -> 'Merge' (total: '1 change merged'). Simultaneously on the bottom track, 14 small incremental green steps ship sequentially: '+ logging', 'refactor', '+ tests', 'ship', 'edge case', '+ metrics', 'ship', 'shadow', '+ tests', 'UI fix', 'ship', 'revert', '+ logging', 'ship' (total: '14 changes shipped'). At 08:25-08:37, Quinn tosses Amp hats into the audience.
> * **On-Screen OCR:** In the time one change waits for review... ; ...the agent ships a dozen small ones, each with proof. ; Old way: pull request + human review ; Write ; Waiting for review ; Fix ; Waiting again ; Merge ; 1 change merged ; New way: push to main, agent proves it works ; + logging ; refactor ; + tests ; ship ; edge case ; + metrics ; shadow ; UI fix ; revert ; 14 changes shipped
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph OldWay["Old way: pull request + human review (1 change merged)"]
>           W[Write] --> WR[Waiting for review] --> F[Fix] --> WA[Waiting again] --> M[Merge]
>       end
>       subgraph NewWay["New way: push to main, agent proves it works (14 changes shipped)"]
>           L1[+ logging] --> R1[refactor] --> T1[+ tests] --> S1[ship] --> EC[edge case] --> MT[+ metrics] --> S2[ship] --> SH[shadow] --> T2[+ tests] --> UI[UI fix] --> S3[ship] --> RV[revert] --> L2[+ logging] --> S4[ship]
>       end

**🎙️ Spoken Transcript:**
* **[07:42]** And the difference is when you can push and you can do it any time of day, just by yourself, you can chunk up your
* **[07:50]** work into way smaller pieces. Before you're going and doing a big change, you can go and say let me add the logging to make sure that my understanding and the agent's understanding of the system is correct. Let me push a little change,
* **[08:00]** a little change, you know, and then the agent can monitor it for an hour and then push the next change. You can run a whole shadow system side-by-side with the old system to see does it compute the exact same results in every single case.
* **[08:11]** And that way of working actually reduces the risk because by the time, you know, you finish the old way of doing it and the pace that things have to move these days and what your customers
* **[08:20]** expect, you've probably forgotten what you're building and it just totally sucks. Um, let me give out some more hats. Who wants some more hats? All right.
* **[08:30]** There we go. I'm sorry. The one guy who's on his laptop, that's a lesson, right? There we go. All right.

💡 **Visual-Speech Alignment:** Each example Quinn mentions—adding logging first ('+ logging'), pushing small increments ('ship'), and running a shadow system ('shadow')—matches the labeled green blocks animating along the 'New way' track.

---

## [08:38 - 08:56] Scene #15: "Give me irrefutable proof"
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Screenshot of a real thread titled 'Left panel git status misaligned toolbar space' showing Quinn instructing the agent to record loading videos and verify frame-by-frame that the icon does not shift position. The agent reports 'Verified frame by frame' with exact pixel coordinates across 56 and 59 frames at 10 fps.
> * **On-Screen OCR:** "Give me irrefutable proof" ; EXAMPLE FROM A REAL THREAD ; Left panel git status misaligned toolbar space ; Quinn: record videos of it loading and ensure frame-by-frame that the icon (pulsing or not) does not change position ; Verified frame by frame ; I found and fixed a second source of movement. The loading state reserved 40px for text, while the empty state reserved only 20px. Both states now reserve the same height. ; I extracted every recorded frame at 10 frames per second and matched the 32px icon across a seven-pixel search area: ; Desktop recording: the icon stayed at (433, 281) in all 56 frames. ; Right panel width, clean state: the icon stayed at (223, 281) in all 59 frames. ; Right panel width, commits ahead state: the icon stayed at (785, 266) in all 59 frames. ; No movement was detected, including the exact frame where loading ended.
> * **Structured Reconstruction:**
>   Prompt (Quinn): record videos of it loading and ensure frame-by-frame that the icon (pulsing or not) does not change position
>   
>   Agent Output (Verified frame by frame):
>   - Fixed reserved height mismatch (40px loading vs 20px empty).
>   - Extracted frames at 10 fps; matched 32px icon across 7px search area:
>     * Desktop recording: icon stayed at (433, 281) in all 56 frames.
>     * Right panel width, clean state: icon stayed at (223, 281) in all 59 frames.
>     * Right panel width, commits ahead state: icon stayed at (785, 266) in all 59 frames.
>   - No movement detected, including exact frame where loading ended.

**🎙️ Spoken Transcript:**
* **[08:38]** Um, another thing is making it so the agent's able to irrefutably prove what uh, the, you know, the thing it's building is correct. Um, there's a lot of ways they can do this.
* **[08:50]** Turns out they're really good at proving these things. So if you're trying to remove like uh jitter in the UI, make sure that when you load it's like nice and crisp,

💡 **Visual-Speech Alignment:** The speaker describes eliminating UI load jitter by asking the agent for irrefutable proof, matching the thread prompt and pixel-coordinate verification output.

---

## [08:57 - 09:05] Scene #16: "Give me irrefutable proof"
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Scrolled view of the same verification thread displaying a visual proof grid titled 'Icon position in all 56 frames: (433, 281). Movement: 0 px.' with 8 cropped frame snapshots (frames 0, 14, 22, 30, 38, 41 - last loading, 42 - first loaded, and 56 - loaded) overlaid with alignment crosshairs.
> * **On-Screen OCR:** "Give me irrefutable proof" ; EXAMPLE FROM A REAL THREAD ; Icon position in all 56 frames: (433, 281). Movement: 0 px. ; frame 0 - loading ; frame 14 - loading ; frame 22 - loading ; frame 30 - loading ; frame 38 - loading ; frame 41 - last loading ; frame 42 - first loaded ; frame 56 - loaded
> * **Structured Reconstruction:**
>   Icon position in all 56 frames: (433, 281). Movement: 0 px.
>   [frame 0 - loading] [frame 14 - loading] [frame 22 - loading] [frame 30 - loading]
>   [frame 38 - loading] [frame 41 - last loading] [frame 42 - first loaded] [frame 56 - loaded]

**🎙️ Spoken Transcript:**
* **[08:57]** you can ask the agent to do something that no human would ever have the patience to do, which is to take every single frame and compare them visually, and that's what I did here.

💡 **Visual-Speech Alignment:** Quinn says 'take every single frame and compare them visually, and that's what I did here' right as the slide advances to the frame-by-frame crosshair comparison grid.

---

## [09:06 - 09:20] Scene #17: Don't iterate. Ask for nine versions.
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Thread screenshot ('Voice waveform lock stability and variants') showing Quinn prompting the agent to fix fractional rounding in the voice waveform and generate a bunch of animated wave examples in Storybook. At 09:06-09:18 it shows the agent running 31 commands (`rg`, `cat`); at 09:19-09:20 it briefly shows the agent listing 5 waveform options and Quinn selecting 'orb field' and instructing the agent to remove all other variants.
> * **On-Screen OCR:** Don't iterate. Ask for nine versions. ; EXAMPLE FROM A REAL THREAD ; Voice waveform lock stability and variants ; Quinn: Make it so the waveform looks a little bit cooler. There's some weird issues where certain ticks in the waveform have different widths. That might be fractional rounding. So fix that. It also might be cool to show some actual waves instead of just ticks. Show me a bunch of examples in a storybook and show them animated with some fake data and I'll tell you what I think looks good. ; Ran 31 commands, edited 4 files, looked at 4 images, loaded 2 skills, 1 other tool call ; Waveform options are ready ; 1. Trailing bars 2. Centered bars 3. Envelope 4. Ribbon 5. Oscilloscope ; Quinn: Use the orb field and remove all the other ones that you tried. Remove the current one and clean up the storybook as well. ; Orb Field is now the only waveform.
> * **Structured Reconstruction:**
>   Prompt: Fix fractional rounding in waveform ticks and build animated wave examples in Storybook.
>   Agent actions: Ran 31 commands (rg, cat), edited 4 files, looked at 4 images.
>   Follow-up Prompt: Use the orb field and remove all the other ones that you tried. Remove the current one and clean up the storybook as well.
>   Result: Orb Field is now the only waveform.

**🎙️ Spoken Transcript:**
* **[09:06]** You can ask the agent to go make a ton of different versions of something. You can never ask a human to like, you know, if you ask a designer, go make nine iterations or nine styles of this, they're going to get really annoyed.
* **[09:16]** I know, because I've worked with designers and I know they don't like that. But for the agent,

💡 **Visual-Speech Alignment:** Illustrates asking the agent to generate multiple design iterations in a Storybook simultaneously instead of iterating one-by-one.

---

## [09:21 - 09:37] Scene #18: Don't iterate. Ask for nine versions.
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Storybook grid displaying 6 interactive animated waveform components generated by the agent: 'Centered Bars', 'Envelope', 'Oscilloscope', 'Bar Ribbon', 'DNA', and 'Orb Field' (highlighted in green with a 'Selected' badge).
> * **On-Screen OCR:** Don't iterate. Ask for nine versions. ; EXAMPLE FROM A REAL THREAD ; Centered Bars: Uniform bars centered with consistent margin. ; Envelope: A smooth line following the signal's upper edge. ; Oscilloscope: A linear waveform steered by audio level. ; Bar Ribbon: A soft organic ribbon, exaggerated bars. ; DNA: Two mirrored rails over dense lines. ; Orb Field (Selected): A multi-dot cascade with a right-edge glow.
> * **Structured Reconstruction:**
>   Storybook Variants:
>   - Centered Bars: Uniform bars centered with consistent margin.
>   - Envelope: A smooth line following the signal's upper edge.
>   - Oscilloscope: A linear waveform steered by audio level.
>   - Bar Ribbon: A soft organic ribbon, exaggerated bars.
>   - DNA: Two mirrored rails over dense lines.
>   - Orb Field [Selected]: A multi-dot cascade with a right-edge glow.

**🎙️ Spoken Transcript:**
* **[09:21]** yeah, you know, you can have it make a ton of different things. This is the waveform for dictation in Amp. And this is one of the solutions to people who say, I don't like waiting on my agent.
* **[09:29]** You know, they're asking for one thing at a time and then they say, make this little change. You shouldn't do that. Go have it make a ton of things at once and you're going to get a lot more done.

💡 **Visual-Speech Alignment:** Quinn identifies the visual Storybook grid as 'the waveform for dictation in Amp' and uses it as an example of parallelizing creative exploration instead of waiting on sequential small tweaks.

---

## [09:38 - 09:54] Scene #19: Ship it, then follow up with everyone affected
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Overview slide showing a dark 5-step horizontal pipeline diagram on the left—(1) Bug reports come in, (2) The agent investigates, (3) A human approves each email, (4) Find everyone affected, (5) Fixed, emailed, credited—paired with four summary bullets on the right.
> * **On-Screen OCR:** Ship it, then follow up with everyone affected ; 1 Bug reports come in ; 2 The agent investigates ; 3 A human approves each email ; 4 Find everyone affected ; 5 Fixed, emailed, credited ; Bugs handled on masse, not one at a time ; Fix -> find everyone affected -> email + credits ; Every email is reviewed by a human ; ~$390K in free credits given back since August
> * **Structured Reconstruction:**
>   flowchart LR
>       S1["1. Bug reports come in"] --> S2["2. The agent investigates"] --> S3["3. A human approves each email"] --> S4["4. Find everyone affected"] --> S5["5. Fixed, emailed, credited"]

**🎙️ Spoken Transcript:**
* **[09:38]** We have this magical system where if you report a bug in Amp—has anyone here reported a bug in Amp? All right, cool. I apologize for the bug, but we have a system that is a full loop where when you report a bug,

💡 **Visual-Speech Alignment:** Introduces the 5-step end-to-end bug resolution and customer credit loop before stepping through each stage in detail.

---

## [09:55 - 10:06] Scene #20: 1 Bug reports come in / 2 The agent investigates
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Interactive walkthrough zooming into Steps 1 and 2 of the bug-fix pipeline. At 09:55-09:58, Step 1 ('4 users, 4 platforms, one cause') displays a submitted bug report: 'In the Android app, opening the Orbs tab in Project Settings shows a 500 error'. At 09:59-10:06, Step 2 ('The agent investigates') highlights the agent's root-cause analysis identifying a Svelte `each_key_duplicate` error in the snapshot list on the Orb page and pushing fix commit `84b84b3` to `main`.
> * **On-Screen OCR:** 1 Bug reports come in (4 users, 4 platforms, one cause) ; In the Android app, opening the Orbs tab in Project Settings shows a 500 error ; 2 The agent investigates ; Root cause: That commit made templates part of the key for shared project snapshots... Two rows with the same key make Svelte throw each_key_duplicate, and SvelteKit shows that as a 500 page. ; Pushed commit 84b84b3 to main, which is linked to all four bug reports. I'm waiting on its CI and production deploy before sending the emails.
> * **Structured Reconstruction:**
>   Step 1: Bug report received -> 'In the Android app, opening the Orbs tab in Project Settings shows a 500 error'
>   Step 2: Agent investigates -> Reproduces locally, identifies Svelte `each_key_duplicate` client error, commits fix `84b84b3` to `main` linked to 4 bug reports.

**🎙️ Spoken Transcript:**
* **[09:55]** we will fix it, of course, you know, Android app. We'll fix it, obviously with the agent. I think everyone does that now, mostly everyone. A lot of times still the engineers are different from the support team, which is kind of crazy.

💡 **Visual-Speech Alignment:** Quinn references the 'Android app' directly from the Step 1 bug report title and transitions into the agent fixing it in Step 2.

---

## [10:07 - 10:20] Scene #21: 3 A human approves each email
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Step 3 of the bug-fix walkthrough ('A human approves each email · plugin dialog: review, edit, send') displaying an interactive 'Send Email?' modal pre-filled with recipient, 'Free credits: $10.00 per recipient', subject line, and draft apology body referencing the Android app bug report, with 'Cancel' and 'Send 1 Email' buttons.
> * **On-Screen OCR:** 3 A human approves each email ; plugin dialog: review, edit, send ; Send Email? ; Free credits: $10.00 per recipient ; Subject: Re: Your Amp bug report "In the Android app, opening..." ; Body: Hi [user A], Fixed! The Orbs tab in Project Settings loads again in the Android app and everywhere else... ; Cancel ; Send 1 Email
> * **Structured Reconstruction:**
>   Step 3: Human-in-the-Loop Email Approval
>   Modal: Send Email?
>   Free credits: $10.00 per recipient
>   Subject: Re: Your Amp bug report "In the Android app, opening..."
>   Actions: [Cancel] [Send 1 Email]

**🎙️ Spoken Transcript:**
* **[10:07]** Um, we'll send an email to the person thanking them, we give them free credits, which is, oh, it's kind of nice. I think it sucks—I think it sucks when there's a bug in a product and the company doesn't apologize. I just think that's like morally wrong.

💡 **Visual-Speech Alignment:** Aligns the 'Send Email?' approval dialog and '$10.00 per recipient' free credits field with the speaker's explanation of thanking users and giving credits.

---

## [10:21 - 11:14] Scene #22: 4 Find everyone affected / 5 Fixed, emailed, credited
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Steps 4 and 5 of the bug-fix walkthrough. At 10:21-10:51, Step 4 ('Find everyone affected · same issue in 3 other users' logs') shows the agent querying other threads and Sentry logs for `each_key_duplicate` to identify everyone who hit the browser-side 500 error. At 10:52-11:14, Step 5 ('Fixed, emailed, credited · 4 emails, 4 $10 credits, 4 reports closed') confirms production deploy (`9c70178b`), closure of all 4 reports, and 4 personalized emails/credits sent (including one localized in Chinese).
> * **On-Screen OCR:** 4 Find everyone affected ; same issue in 3 other users' logs ; Investigate 500 on Project Settings > Orbs (customer A) ; A related web report shows a Sentry `each_key_duplicate` error in its browser log, which Sentry/tab surfaces as a 500. ; 5 Fixed, emailed, credited ; 4 emails, 4 $10 credits, 4 reports closed ; The fix is live on production (9c70178b, including 84b84b3), and I'm now sending the four replies, each granting $10, with a confirmation dialog for every send. ; Shipped: 84b84b3 is on main. ; Emailed, credited and resolved: each email came from you with me CC'd, said the fix is live, apologized and mentioned the $10.
> * **Structured Reconstruction:**
>   Step 4: Find everyone affected
>   - Agent queries Sentry client logs & other bug threads for `each_key_duplicate`.
>   - Finds 3 additional affected users.
>   
>   Step 5: Fixed, emailed, credited
>   - Fix live in production (9c70178b / 84b84b3).
>   - 4 emails sent (one in Chinese), 4 x $10 credits granted, 4 bug reports closed.

**🎙️ Spoken Transcript:**
* **[10:21]** And then what we'll do is we'll go through the logs, and this is something that no human would ever do by themselves, we'll see everyone else who was affected by that issue. Because where there's smoke, there's
* **[10:30]** fire. So, you find the 17 other people that hit that same obscure error. They remember it probably, and you proactively tell them. How many times have you gotten an email from some product that says, hey, I know that
* **[10:40]** you saw an error yesterday and that was really annoying, I'm really sorry about that. Here's $10, we fixed it. And by the way, that—it's a self-perpetuating cycle where then people who get that know that you care and they're going to send
* **[10:50]** more feedback in the future. And then you ship those all out and then, you know, boom. And that's the cycle, that—people talk about vibe-coded products
* **[11:00]** as being junk; Amp is basically 100% built with AI. And people say it's very high quality. And this is one of the things you can do differently with an agent. But there's no
* **[11:10]** way in hell you can do this if you had to go through a PM or go to the team that owns this bug and the designers each time.

💡 **Visual-Speech Alignment:** Step 4 visually demonstrates the agent searching Sentry logs to uncover other affected users ('where there's smoke, there's fire'), and Step 5 shows all 4 affected users receiving the $10 apology email once shipped.

---

## [11:15 - 11:55] Scene #23: How do you do RTO if everyone's dictating?
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide featuring a dark bar chart on the left titled 'Dictations per day, last 3 weeks', showing daily dictation counts around 300-440 before a trip ('To Sydney'), dropping sharply to ~25-70 during the period labeled 'In Australia', and rebounding to ~250-350 after 'Fly home'. Three bullet points appear on the right.
> * **On-Screen OCR:** How do you do RTO if everyone's dictating? ; Dictations per day, last 3 weeks ; To Sydney / In Australia / Fly home ; Avg per day: 358 before | 44 in Australia | 310 after ; 69% of my messages are dictated ; Dictated messages run 2x as long ; In Australia, in rooms with people: 358 -> 44 a day
> * **Structured Reconstruction:**
>   | Period | Avg Dictations / Day | Notes |
>   | --- | --- | --- |
>   | Before trip | 358 | Peak ~438/day |
>   | In Australia (in rooms with people) | 44 | Sharp drop during in-person coworking |
>   | After ('Fly home') | 310 | 69% of speaker's messages are dictated; 2x length |

**🎙️ Spoken Transcript:**
* **[11:15]** Um, dictation. Who dictates to their agents?
* **[11:20]** Yeah. Wow, that's—that's pretty good. That's a lot more than I thought. It is the fastest way to get bits of information from your brain to the agent.
* **[11:30]** And uh I think that there's probably something around it uh ushering in the return of remote work. Because I was just in an office today with um the
* **[11:40]** other co-founder dictating and it was uh very annoying. Dictation, if you're not doing it yet, you got to do it. Just overcome the embarrassment, uh,
* **[11:50]** you know, uh, channel Nathan Fielder and uh tell yourself that you can withstand any amount of awkwardness as you talk.

💡 **Visual-Speech Alignment:** The bar chart dip during 'In Australia' (358 -> 44 dictations/day) illustrates Quinn's joke that voice dictation to agents is awkward in shared offices and might bring back remote work.

---

## [11:56 - 14:23] Scene #24: Custom tools our agent can use
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Slide titled 'Custom tools our agent can use' with subtitle 'Plugins and MCP servers, hooked up to every thread.' Below is a 3x4 grid of 12 dark cards detailing the internal tools wired directly into every Amp thread: CRM, Bug reports, Amp admin, Hiring, Gmail & Calendar, Slack, Grafana, Buildkite, App Store & Play, GitHub & Linear, Offer cards, and CustomInk.
> * **On-Screen OCR:** Custom tools our agent can use ; Plugins and MCP servers, hooked up to every thread. ; CRM: Accounts, contacts, deals, emails, meetings, automations ; Bug reports: Search, cluster, resolve, email users with credits ; Amp admin: Credits, subscriptions, feature flags, notices ; Hiring: Positions, candidates, notes ; Gmail & Calendar: Read, search, draft, schedule ; Slack: Read channels, post, reply ; Grafana: Production metrics, dashboards, alerts, profiles ; Buildkite: CI builds, jobs, logs, test runs ; App Store & Play: TestFlight, feedback, crashes, reviews ; GitHub & Linear: Subscribe to CI, commits, issues ; Offer cards: Print and assign QR gift cards ; CustomInk: Design and order team merch
> * **Structured Reconstruction:**
>   flowchart TB
>       Agent["Amp Thread (Plugins & MCP Servers)"]
>       Agent --> CRM["CRM: Accounts, contacts, deals, emails, meetings, automations"]
>       Agent --> Bugs["Bug reports: Search, cluster, resolve, email users with credits"]
>       Agent --> Admin["Amp admin: Credits, subscriptions, feature flags, notices"]
>       Agent --> Hiring["Hiring: Positions, candidates, notes"]
>       Agent --> Gmail["Gmail & Calendar: Read, search, draft, schedule"]
>       Agent --> Slack["Slack: Read channels, post, reply"]
>       Agent --> Grafana["Grafana: Production metrics, dashboards, alerts, profiles"]
>       Agent --> Buildkite["Buildkite: CI builds, jobs, logs, test runs"]
>       Agent --> Stores["App Store & Play: TestFlight, feedback, crashes, reviews"]
>       Agent --> GitHub["GitHub & Linear: Subscribe to CI, commits, issues"]
>       Agent --> Offer["Offer cards: Print and assign QR gift cards"]
>       Agent --> Merch["CustomInk: Design and order team merch"]

**🎙️ Spoken Transcript:**
* **[11:56]** We've hooked up our agent to a lot of different tools.
* **[12:00]** I think a lot of companies have gotten here, you know, to this point. We've been doing this in production for a long time and what we've found is, the more that we start using these tools where just the
* **[12:10]** agent is using it directly, we don't even need the software product on the other end. And it's a very small number of products that we think actually have sticking power for us. So, you know, we've built some new things in Amp,
* **[12:20]** for example, a CRM. And a year ago, you heard people talking about, oh, no one's going to vibe code Salesforce from scratch. And yeah, that's totally true. Why would you want
* **[12:30]** to? Have you ever used it? Would you be proud if you vibe coded that and that came out the other end? And also, you've used like 2% of the features of Salesforce. So actually, you know, people ridiculed this idea, but actually,
* **[12:40]** would you code the 2% subset of Salesforce features? And then another 2% that integrate with the rest of your stack in the most perfect way because the agent is so good at that?
* **[13:00]** And that, you know, 4% of Salesforce total, that's like the easy shit. And you know what you want out of that better than Salesforce. And you certainly don't want to spend your time talking to some Salesforce product manager and hearing
* **[13:10]** from them, I'm going to advocate with my PM and my executive team to get that on our Q4 roadmap, all that bullshit. So, compared to that, it's actually getting
* **[13:20]** easier and easier to just build the tools that you want from scratch. And this goes back to some of the existential kind of dread but also kind of mind-blowing
* **[13:30]** feeling that we felt when we first tried an agent. This is what we kind of thought would happen. That it would change everything about the software
* **[13:40]** industry. If Salesforce, which is like the King Cobra of SaaS—they had the most reliable customers, most reliable renewals, all that, they like invented the category—
* **[13:50]** if we're starting to see, you know, why would we use them? Well, everything is starting to fall and all of SaaS starts to break down if you can no longer assume that
* **[14:00]** you can pay a salesperson 100k for closing a deal and that deal's going to last for 10 years and it's going to, you know, get bigger by a little bit. No, all of that is called into question now. So if you're at a software company and that is how you ultimately make money,
* **[14:12]** and you're trying to ring the bell, you're trying to raise the alarm here, uh absolutely raise it and get out of the cage that you are in.

💡 **Visual-Speech Alignment:** Quinn singles out the top-left 'CRM' card on the grid to explain why building a custom 4% subset of Salesforce directly inside the agent eliminates traditional SaaS dependency.

---

## [14:24 - 14:39] Scene #25: A New Kind of Company
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Section divider slide showing the textured metallic orb on the left and large bold dark text 'A New Kind of Company' on the right.
> * **On-Screen OCR:** A New Kind of Company
> * **Structured Reconstruction:**
>   Section: A New Kind of Company

**🎙️ Spoken Transcript:**
* **[14:24]** Because uh in my opinion, once you have seen how the new kind of companies that are two orders of magnitude smaller, where everyone can do everything
* **[14:31]** and where everyone has skin in the game, then you know, you don't want anything else. And so this is what we call this new kind of company

💡 **Visual-Speech Alignment:** Visual section header introducing the organizational principles of the 21-person spun-out company.

---

## [14:40 - 14:47] Scene #26: Departments -> 21 co-founders
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Animated transition slide showing the old Sourcegraph ~200-person departmental tree fading out while the flat green circle on the right populates from 'Amp · 9' to 21 green dots ('21 co-founders').
> * **On-Screen OCR:** Departments -> 21 co-founders ; Sourcegraph: ~200 people in departments ; CEO ; Engineering · 75 ; Sales & Marketing · 75 ; Amp · 9
> * **Structured Reconstruction:**
>   flowchart LR
>       Old["Sourcegraph (~200 people in departments: Eng 75, Sales & Mktg 75, etc.)"] -->|"Replaced by"| New(("Amp: 21 co-founders (flat team)"))

**🎙️ Spoken Transcript:**
* **[14:40]** where, you know, we take that old org chart and now we just got 21 people on Amp.

💡 **Visual-Speech Alignment:** Synchronized with the speaker saying 'we take that old org chart and now we just got 21 people on Amp' as the Sourcegraph tree dissolves into the Amp circle.

---

## [14:48 - 15:39] Scene #27: PMs -> everyone talks to customers
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide pairing two Slack message screenshots on the left with bullet points on the right. The top Slack screenshot ('Re: Amp Budget', Nov 6, 2026) shows Brady Jeong confirming payment receipt, adding credits, and announcing 'The 100k USD Sales Order is now fully executed.' The bottom screenshot ('# shared-channel', Nov 12, 2026) shows Alex Kemper candidly telling a customer they shouldn't waste people's time getting 'bogged down into cross-functional requirement BS', followed by the customer agreeing.
> * **On-Screen OCR:** PMs -> everyone talks to customers ; You're the ambassador to your customers ; You own everything ; Re: Amp Budget ; Brady Jeong (Nov 6, 2026): @here ... confirming payment receipt and rest of the credits have been added. Thanks! The 100k USD Sales Order is now fully executed. ; # shared-channel (Slack Connect with a customer) ; Alex Kemper (Thursday, November 12th, 2026): That's the exact right details here. There are a ton of requirements and cross-functional stakeholders here and I don't want to waste peoples time. I'm imagining a scenario where we demo a few things, it looks good, but then we get bogged down into cross-functional requirement BS and the whole initiative goes nowhere.
> * **Structured Reconstruction:**
>   PMs -> everyone talks to customers
>   - You're the ambassador to your customers
>   - You own everything
>   
>   Examples:
>   1. Brady Jeong (former SDR) executing a $100k USD Sales Order + implementing ACH wire transfer.
>   2. Alex Kemper candidly advising a customer in a Slack Connect channel not to waste time on cross-functional BS.

**🎙️ Spoken Transcript:**
* **[14:48]** We have no PMs, everyone talks to customers. Brady is this guy who was an SDR at Sourcegraph, really smart guy, I love the guy. And one day he's like, I'm going to make a wire—ACH wire transfer thing so customers
* **[15:00]** can pay us, you know, if it's too big for credit card, and he's like two years out of college and he's just doing that. And nobody knows on the other end. It's like that old New Yorker cartoon: on the internet, nobody knows you're a dog. You know, nobody knows that he's an SDR, they're all kind of, you know, devs and doing everything.
* **[15:14]** But you can. And you also get people that are really real with customers, and I think sometimes customers need real talk. So Alex Kemper on our team,
* **[15:22]** you know, just today, he was like, hey, you know, to a customer who wanted our stuff: that sounds like we're just going to get bogged down in a bunch of BS and I don't think that's a good use of anyone's time.
* **[15:31]** If you can get to a place where you have people that feel empowered to say that and to truly say the best thing for the customer, that's great. You're not going to get that out of a salesperson who is commissioned.

💡 **Visual-Speech Alignment:** Quinn's stories about Brady Jeong and Alex Kemper map directly to the two Slack screenshots displayed on the left half of the slide.

---

## [15:40 - 16:11] Scene #28: Roadmaps -> one meeting a week
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide displaying a 7-day weekly calendar ('Mon' through 'Sun') on the left: Monday contains a bright green block labeled 'What do we ship this week?' followed by 'follow your energy', while Tuesday through Sunday (including Saturday and Sunday) contain only 'follow your energy'. Below the calendar is a muted line reading 'no quarterly goals · no roadmaps · no PRDs'. Two bullets are on the right.
> * **On-Screen OCR:** Roadmaps -> one meeting a week ; Mon / Tue / Wed / Thu / Fri / Sat / Sun ; What do we ship this week? ; follow your energy ; no quarterly goals · no roadmaps · no PRDs ; Monday: what do we ship this week? ; Feature flags and real usage decide what ships
> * **Structured Reconstruction:**
>   Weekly Schedule:
>   - Mon: [What do we ship this week?] + follow your energy
>   - Tue–Sun: follow your energy
>   Rules: no quarterly goals · no roadmaps · no PRDs
>   Policy: Feature flags and real usage decide what ships

**🎙️ Spoken Transcript:**
* **[15:40]** We have—this is some people's favorite part—we have one meeting per week, and then everything else, the guidance is follow your energy.
* **[15:49]** Um, you couldn't run most companies like that, but if everyone at the company has a massive stake in the company, you know, take 100% divided by 21, you know, and all that,
* **[15:59]** you can actually trust people. Because again, when people have skin in the game, it makes them better at everything they do. It's like an incentive to make them think whole-company, to make them do more, to make them work harder, and that's why I included Saturday and Sunday as well on this.

💡 **Visual-Speech Alignment:** Quinn explicitly points to including 'Saturday and Sunday as well on this' on the 7-day 'follow your energy' calendar.

---

## [16:12 - 16:47] Scene #29: Opposite release cycles
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide displaying a dark green bar chart titled 'Amp, every week since February 2025' plotting weekly shipping activity: 22,538 total code pushes (green bars) alongside 219 news posts (bright green/white markers). Three bullets on the right contrast Enterprise vs. Amp release cadences.
> * **On-Screen OCR:** Opposite release cycles ; Amp, every week since February 2025 ; 22,538 code pushes ; 219 news posts ; Enterprise: stable, predictable releases ; Amp: changes every day ; Hard to talk about both at once
> * **Structured Reconstruction:**
>   | Metric (Feb 2025 – Present, Weekly) | Total Count |
>   | --- | --- |
>   | Code pushes | 22,538 |
>   | News posts | 219 |
>   | Release model | Enterprise (stable/predictable) vs. Amp (changes every day) |

**🎙️ Spoken Transcript:**
* **[16:12]** And we are shipping just, you know, so much more. I think that, you know, Amp for many people is a product that they love. We also have a great business and we're serving as proof that this new kind of company that is profitable, that's more than $100 million
* **[16:30]** ARR, that is doing so on a dollar-in dollar-out, you know, basis, that's 40 to 50 times more efficient than old-fashioned companies here—that that can work.
* **[16:40]** And so if this is appealing to you, if you want to push your company in this direction, if you want to go start a company like this, then reach out, I am happy to help.

💡 **Visual-Speech Alignment:** The steady upward growth of weekly code pushes (22,538) and news posts (219) visually backs up the speaker's claim of shipping far more with 40-50x capital efficiency.

---

## [16:48 - 17:27] Scene #30: Get Out of the Cage
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Closing section slide featuring the metallic orb with radiating lines on the left and bold text 'Get Out of the Cage' on the right.
> * **On-Screen OCR:** Get Out of the Cage
> * **Structured Reconstruction:**
>   Closing Call to Action: Get Out of the Cage

**🎙️ Spoken Transcript:**
* **[16:48]** And my guidance is just get out of the cage. I've heard from so many people who say I hate that there's a gossip channel with the people in my company. We're all talking about the change, you know what—the
* **[17:00]** longer that you are in the gossip channel, the longer that you are at a company getting paid a lot of money and you're really smart and you're not doing shit about it, you're starting to become part of the problem. And the longer that you let yourself be
* **[17:10]** just a developer when agents have completely changed the game, you're really hurting yourself. So, if this is, you know, the one thing you take away, just get out
* **[17:20]** of that cage, let agents really shape how you work and get to a company that's willing to be shaped by the agents.

💡 **Visual-Speech Alignment:** Direct alignment between the slide title 'Get Out of the Cage' and the speaker's closing exhortation.

---

## [17:28 - 17:31] Scene #31: Thanks!
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Brief thank-you slide displaying 'Thanks!' and '@sqs · ampcode.com' on a light background.
> * **On-Screen OCR:** Thanks! ; @sqs · ampcode.com
> * **Structured Reconstruction:**
>   Thanks!
>   @sqs · ampcode.com

**🎙️ Spoken Transcript:**
* **[17:28]** Thank you and um

💡 **Visual-Speech Alignment:** Speaker thanks the audience as the 'Thanks!' slide appears.

---

## [17:32 - 17:43] Scene #32: 1 month of Amp Megawatt, on us
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Promotional QR code slide (initially picture-in-picture at 17:32, then switching to wide stage view at 17:36 as audience members hold up phones to scan) offering '1 month of Amp Megawatt, on us' at `ampcode.com/code/AMP-AIE-5F`.
> * **On-Screen OCR:** 1 month of Amp Megawatt, on us ; ampcode.com/code/AMP-AIE-5F
> * **Structured Reconstruction:**
>   Promo Offer: 1 month of Amp Megawatt, on us
>   URL: ampcode.com/code/AMP-AIE-5F (with QR code)

**🎙️ Spoken Transcript:**
* **[17:32]** if you want to try Amp, you can get up there, you can uh copy that. I got more hats, so find me afterwards and I'll probably be getting dinner at Chipotle or something, so come find me if you
* **[17:40]** want to uh chat about all this stuff. All right, thank you all.

💡 **Visual-Speech Alignment:** Quinn gestures toward the QR code ('you can get up there, you can copy that') while concluding his talk.

---

## [17:44 - 18:00] Scene #33: AI Engineer Code Summit
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Closing conference bumper on black background displaying the 'AI Engineer Code Summit' logo and 'HTTPS://AI.ENGINEER' below.
> * **On-Screen OCR:** AI Engineer Code Summit ; HTTPS://AI.ENGINEER
> * **Structured Reconstruction:**
>   Closing Title Card:
>   AI Engineer Code Summit
>   HTTPS://AI.ENGINEER

**🎙️ Spoken Transcript:**
* **[17:58]** They are not in the house.

💡 **Visual-Speech Alignment:** Closing conference end-card with brief background/off-mic remark near the end.

---
