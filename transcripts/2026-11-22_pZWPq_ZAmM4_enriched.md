# Enriched Interleaved Transcript: What it takes to set intelligence free — Fabian Hedin, CTO, Lovable
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=pZWPq_ZAmM4
**Model:** `gemini-3.6-flash` | **Processing Mode:** `agentic`

---

## [00:00 - 00:12] Scene #1: AI Engineer Code Summit Intro
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Introductory title screens displaying event branding and platinum sponsor logos.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; PLATINUM SPONSORS ; aws ; Devin ; databricks ; exa ; FACTORY ; Sonar

**🎙️ Spoken Transcript:**

💡 **Visual-Speech Alignment:** Intro bumper and sponsor slides shown before speaker walks onto stage.

---

## [00:13 - 00:41] Scene #2: Speaker Stage Intro
> **[SCREEN INTERPRETATION | Type: `SPEAKER_ONLY`]**
> * **Visual Summary:** Fabian Hedin walks onto the stage at AI Engineer Code Summit.
> * **On-Screen OCR:** AI Engineer Code Summit ; Google DeepMind ; What it takes to set intelligence free

**🎙️ Spoken Transcript:**
* **[00:13]** Welcome everyone. I'm glad to be here. I'm Fabian, co-founder and CTO of Lovable.
* **[00:20]** And we spent the last few years or so building a platform to let anyone create software and then operate that and deploy that software.
* **[00:30]** And the topic of today is what it takes to set intelligence free. And really for us this takes us back to when we started three years ago.

💡 **Visual-Speech Alignment:** Fabian introduces himself and states the primary focus of the presentation.

---

## [00:42 - 00:44] Scene #3: What it takes to set intelligence free
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Title slide with gradient background featuring talk title, speaker name, and company.
> * **On-Screen OCR:** Fabian Hedin - AI Engineer Code Summit ; What it takes to set intelligence free ; Fabian Hedin / CTO ; Lovable

**🎙️ Spoken Transcript:**
* **[00:40]** And I have to say I have a bit of a complicated relationship with agents.

💡 **Visual-Speech Alignment:** Presentation title slide with speaker title and affiliation.

---

## [00:45 - 00:49] Scene #4: I have a complicated relationship with agents.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Minimal slide with simple text stating speaker's relationship with AI agents.
> * **On-Screen OCR:** I have a complicated relationship with agents.

**🎙️ Spoken Transcript:**
* **[00:45]** and I'll tell you why.

💡 **Visual-Speech Alignment:** Speaker opens historical reflection on building agent systems.

---

## [00:50 - 01:11] Scene #5: Lovable almost failed because we bet on them in 2023.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide describing how early reliance on agent architecture nearly led to company failure in 2023.
> * **On-Screen OCR:** Lovable almost failed because we bet on them in 2023. ; We thought they were the future

**🎙️ Spoken Transcript:**
* **[00:50]** We almost failed as a company because we thought back in 2023 that hey, these agents are the future. So let's build for the now.
* **[01:00]** I think that we kind of turned out to be true that they were the future but we're definitely wrong on the the now piece in 23.

💡 **Visual-Speech Alignment:** Speaker points out that betting on agents in 2023 was premature.

---

## [01:12 - 01:19] Scene #6: But at the time, the intelligence was not there.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide explaining model capability limitations in 2023.
> * **On-Screen OCR:** But at the time, the intelligence was not there.

**🎙️ Spoken Transcript:**
* **[01:10]** So this was back in kind of GPT-4 days. Um and at that time, the intelligence was simply not there to have more of these kind of complex agentic systems.

💡 **Visual-Speech Alignment:** Speaker aligns model limitations in GPT-4 era with the failure of multi-agent patterns.

---

## [01:20 - 01:29] Scene #7: Now it is.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Vibrant gradient slide declaring that LLM intelligence has reached the required threshold.
> * **On-Screen OCR:** Now it is.

**🎙️ Spoken Transcript:**
* **[01:20]** Um but now this, right? Now, the intelligence is actually at a place where you can really build out more complicated systems around them.

💡 **Visual-Speech Alignment:** Speaker highlights that present-day models enable robust agentic architectures.

---

## [01:30 - 01:41] Scene #8: How we got here
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Timeline diagram showing four stages of Lovable's architecture evolution from Spring 2023 to present.
> * **On-Screen OCR:** How we got here ; Spring 2023 - GPT Engineer - Prompt -> response, one LLM chain ; Jan 2024 - First agent framework - Async tasks + subagents ; Late 2024 - Back to a chain - One-shot edits in XML ; Now - Agents for real - Tools -> feedback -> next step
> * **Structured Reconstruction:**
>   flowchart LR
>       A["Spring 2023<br/>GPT Engineer<br/>Prompt -> response, one LLM chain"] --> B["Jan 2024<br/>First agent framework<br/>Async tasks + subagents"]
>       B --> C["Late 2024<br/>Back to a chain<br/>One-shot edits in XML"]
>       C --> D["Now<br/>Agents for real<br/>Tools -> feedback -> next step"]

**🎙️ Spoken Transcript:**
* **[01:30]** And so, I'll give you kind of a quick background story here of our journey in working with intelligence or these LLMs.

💡 **Visual-Speech Alignment:** Speaker references the historical timeline diagram summarizing platform iterations.

---

## [01:42 - 02:09] Scene #9: Spring 2023: GPT Engineer
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Visual of initial product phase (GPT Engineer) with simple single-turn prompt-response execution.
> * **On-Screen OCR:** Spring 2023 ; GPT Engineer ; Prompt -> response, one LLM call
> * **Structured Reconstruction:**
>   Prompt -> response, one LLM call

**🎙️ Spoken Transcript:**
* **[01:42]** And so, back in 2023, we built the first version of our product, we called it GPT Engineer back then.
* **[01:50]** and really the UI was very similar to what it is today, where you kind of have a chat and in this preview. But the AI at that point was quite simple, we just had a prompt and response, one LLM call per user message.

💡 **Visual-Speech Alignment:** Speaker explains the single LLM call pattern used in early GPT Engineer.

---

## [02:10 - 03:09] Scene #10: Jan 2024: First agent framework
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Multi-agent tree structure showing main-agent spawning specialist subagents and sending XML messages.
> * **On-Screen OCR:** Jan 2024 ; First agent framework ; Async tasks + subagents ; <agent-started: main-agent> ; <agent-started: todo-app-agent> ; <agent-started: implementation-agent> ; <write-to-agent> ; A todo app
> * **Structured Reconstruction:**
>   flowchart TD
>       User["User Task: A todo app"] --> Main["<agent-started: main-agent>"]
>       Main --> Sub1["<agent-started: todo-app-agent>"]
>       Sub1 --> Sub2["<agent-started: implementation-agent>"]
>       Sub2 --> Write["<write-to-agent>"]

**🎙️ Spoken Transcript:**
* **[02:10]** And so we thought, let's go out and build this agentic framework. And so we went and we built this very sophisticated, dare I say, beautiful framework for agents to work.
* **[02:30]** We had kind of this one main agent that would talk to the user and that agent would spawn other agents like an implementation agent here in the example.
* **[02:50]** And they would all talk to each other, send messages back and forth and we thought, wow, this is beautiful... and in the end it didn't work at all. It just made the product worse.

💡 **Visual-Speech Alignment:** Speaker points to the multi-agent XML log visual showing spawned agents communicating.

---

## [03:10 - 03:39] Scene #11: Late 2024: Back to a chain
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Slide showing XML-formatted one-shot file edits used during the pivot back to a simpler linear execution model.
> * **On-Screen OCR:** Late 2024 ; Back to a chain ; One-shot edits in XML ; Refactor calculateResult to use a separate mathOperations utility file for the calculation logic.
> * **Structured Reconstruction:**
>   <write_file path="src/components/Calculator.tsx">
>   import { calculateResult } from '../utils/mathOperations';
>   </write_file>
>   
>   <write_file path="src/utils/mathOperations.ts">
>   export function calculateResult(num1: number, num2: number, operation: string): number {
>     return num1 + num2;
>   }
>   </write_file>

**🎙️ Spoken Transcript:**
* **[03:10]** So in late 24 we went back to a much simpler system... where we had like some smaller LLMs doing some knowledge retrieval and then really just one main LLM kind of writing to the user and writing the code in the same message.
* **[03:31]** And this worked great. It was very responsive for users in the UI and it was reliable.

💡 **Visual-Speech Alignment:** Speaker points out the XML block format used to stream multi-file modifications in single turns.

---

## [03:40 - 03:54] Scene #12: We're back
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Gradient slide titled 'We're back' with footnote '(This time agents actually works)'.
> * **On-Screen OCR:** We're back ; (This time agents actually works)

**🎙️ Spoken Transcript:**
* **[03:40]** But now it's time again. We're back. We're so back. Agents this time... they work.
* **[03:50]** and we're running them in production over billions of tokens per minute on these systems that I'm going to talk about.

💡 **Visual-Speech Alignment:** Speaker transitions to discussing production scale agent architecture.

---

## [03:55 - 05:20] Scene #13: The UI is a chat and a preview
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Wireframe diagram showing split layout: CHAT window on left, PREVIEW canvas on right.
> * **On-Screen OCR:** The UI is a chat and a preview ; CHAT ; PREVIEW ; Type what you want. The app changes in front of you.
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph UI ["lovable.dev"]
>           Chat["CHAT<br/>Human input / intent"]
>           Preview["PREVIEW<br/>Live app outcome"]
>       end
>       Chat --> Preview

**🎙️ Spoken Transcript:**
* **[03:55]** So if you simplify the UI... To the left we have a chat where humans come in and they kind of describe their intent to build or whatever they want to do.
* **[04:15]** And to the right, you have a preview, which is the output or outcomes of what you're building.
* **[04:30]** And I think today we've even seen a lot of tooling meant for developers moving to this type of interface where you're not really looking at the code every day.

💡 **Visual-Speech Alignment:** Speaker describes the core Lovable interface paradigm (Chat input leading directly to live preview).

---

## [05:21 - 05:24] Scene #14: You still care about the code, losers?
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Humorous slide questioning developer fixation on source code.
> * **On-Screen OCR:** You still care about the code, losers?

**🎙️ Spoken Transcript:**
* **[05:20]** I think today we're kind of in this almost a bit in between...

💡 **Visual-Speech Alignment:** Brief playful slide shown before emphasizing user outcomes.

---

## [05:25 - 05:49] Scene #15: What matters is outcomes.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Colorful slide emphasizing outcome orientation over manual code inspection.
> * **On-Screen OCR:** What matters is outcomes.

**🎙️ Spoken Transcript:**
* **[05:25]** But in the end, what matters is actually not the code... what matters is outcomes, right?
* **[05:35]** Well, for our users, the outcomes is creating a business and monetizing and creating value for others.

💡 **Visual-Speech Alignment:** Speaker anchors the product strategy to delivering functional business outcomes.

---

## [05:50 - 07:50] Scene #16: Platform Capabilities: Agent, Cloud, Business
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Three-column grid mapping Lovable platform features across Agent, Cloud, and Business categories.
> * **On-Screen OCR:** Agent ; Full-stack apps ; Build, run and test ; Browser verification ; GitHub + code ownership ; Generate MCP servers ; Connect tools + APIs ; Cloud ; Database + authentication ; Storage + realtime ; Edge functions + jobs ; Hosting + custom domains ; Security scanners ; Backups + logs ; Business ; Payments + subscriptions ; Emails ; SEO + AI search ; Google + Meta ads ; Analytics + conversions ; Growth plans + outreach
> * **Structured Reconstruction:**
>   | Agent | Cloud | Business |
>   | --- | --- | --- |
>   | Full-stack apps | Database + authentication | Payments + subscriptions |
>   | Build, run and test | Storage + realtime | Emails |
>   | Browser verification | Edge functions + jobs | SEO + AI search |
>   | GitHub + code ownership | Hosting + custom domains | Google + Meta ads |
>   | Generate MCP servers | Security scanners | Analytics + conversions |
>   | Connect tools + APIs | Backups + logs | Growth plans + outreach |

**🎙️ Spoken Transcript:**
* **[05:50]** If you look at Lovable, the first thing that you can say about the platform is that we have this agent... specialized at building software.
* **[06:25]** The cloud part of the platform is about giving hosting primitives seamlessly... databases, auth, storage, edge functions.
* **[07:05]** The last piece is around these business capabilities... payments, emails, SEO, Google & Meta ads, analytics.

💡 **Visual-Speech Alignment:** Speaker gestures sequentially across the three feature columns.

---

## [07:51 - 08:14] Scene #17: From 30 minutes to 10+ hours
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Bar graph showing expansion of max agent task execution time from 30 minutes to 10+ hours.
> * **On-Screen OCR:** From 30 minutes to 10+ hours ; Before ; 30 minutes ; Now ; 10+ hours ; 0h ; 2h ; 4h ; 6h ; 8h ; 10h
> * **Structured Reconstruction:**
>   | Mode | Duration |
>   | --- | --- |
>   | Before | 30 minutes |
>   | Now | 10+ hours |

**🎙️ Spoken Transcript:**
* **[07:51]** At some point in Lovable history, we used to limit our agents to work for only 30 minutes because we thought they weren't reliable.
* **[08:05]** But now we've changed this to really be without any sort of bound... you can imagine agents working for 10 hours plus.

💡 **Visual-Speech Alignment:** Speaker points to the horizontal bar expansion showing multi-hour autonomous execution.

---

## [08:15 - 08:50] Scene #18: What does it take to run an agent for 10+ hours?
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Diagram laying out the 3 primary sub-systems: Agent runtime, Computer, and Verification.
> * **On-Screen OCR:** What does it take to run an agent for 10+ hours? ; Pick up and plan its work ; Read the history ; Call the model ; Run a tool ; Write the result ; Agent runtime ; A place to do its work ; Files ; Running app ; Local database ; Memory ; Computer ; A place to check its work ; Verification
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph Component1 ["01. Agent runtime"]
>           A1["Pick up and plan work"] --> A2["Read history"]
>           A2 --> A3["Call model"]
>           A3 --> A4["Run tool"]
>           A4 --> A5["Write result"]
>       end
>   
>       subgraph Component2 ["02. Computer"]
>           C1["Saved State:<br/>Files | Running app | Local db | Memory"]
>       end
>   
>       subgraph Component3 ["03. Verification"]
>           V1["A place to check its work"]
>       end
>   
>       Component1 --> Component2 --> Component3

**🎙️ Spoken Transcript:**
* **[08:15]** And so I'll go into some of the things that we've done in our architecture to enable this. The first piece is really around the agent runtime itself...
* **[08:30]** The second piece is the computer, where each of these agents are actually doing their work...
* **[08:40]** The last piece then is the verification itself, where if you want an agent to work for a long amount of time, you need feedback loops.

💡 **Visual-Speech Alignment:** Speaker introduces the core agenda of technical architecture sections.

---

## [08:51 - 10:04] Scene #19: The agent runtime: Always-on
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Agent Control Plane (ACP) architecture diagram showing Inbox queue aggregating external triggers into Task History trajectory.
> * **On-Screen OCR:** The agent runtime: Always-on ; Agent control plane (ACP) - Starts agents, and wakes one up when its inbox gets a message ; Inbox ; You ; Other agents ; Scheduled wake-ups ; Task history (trajectory) ; Request ; Tool call ; Result ; What's the status? ; Anyone can drop a message in the inbox. The agent copies it into its history between steps.
> * **Structured Reconstruction:**
>   flowchart TD
>       You["You (Human)"] --> Inbox
>       Other["Other agents"] --> Inbox
>       Sched["Scheduled wake-ups"] --> Inbox
>   
>       subgraph ACP ["Agent Control Plane (ACP)"]
>           Inbox["Inbox: 'What's the status?'"]
>       end
>   
>       Inbox --> Trajectory["Task history (trajectory)<br/>[Request] -> [Tool call] -> [Result] -> [What's the status?] -> [Tool call]"]

**🎙️ Spoken Transcript:**
* **[08:51]** And so, if we start by looking at the agent runtime itself... you have three different sources that can interact with an agent: yourself, other agents, or a schedule.
* **[09:20]** For each agent we have a separate inbox where any of these sources send in messages.
* **[09:45]** The agent then can copy that itself into its own what we call a trajectory, basically its task history.

💡 **Visual-Speech Alignment:** Speaker points to the inbox node receiving async messages and copying them into task history.

---

## [10:05 - 11:14] Scene #20: Fork the task history at any step
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Tree graph showing history branching capability ('Rewrite it in Rust' fork extending off 'Read file' node).
> * **On-Screen OCR:** Fork the task history at any step ; Main ; Improve performance ; Start ; Read file ; Fork ; Rewrite it in Rust ; Edit file ; Test: ok ; Done ; Each event points to the one before it. A fork points to the same parent and copies nothing.
> * **Structured Reconstruction:**
>   flowchart LR
>       Main1["Improve performance"] --> Main2["Start"] --> Main3["Read file"]
>       Main3 --> Fork1["Rewrite it in Rust"]
>       Fork1 --> Fork2["Edit file"]
>       Fork2 --> Fork3["Test: ok"]
>       Fork3 --> Fork4["Done"]

**🎙️ Spoken Transcript:**
* **[10:05]** And we designed this trajectory with really Git as inspiration. It's an append-only log where each event points towards a parent...
* **[10:40]** Because of this, you get a nice capability just like in Git where you can fork things, right?
* **[11:00]** Unlike Git, we cannot merge agent trajectories, but we can kind of spawn them out.

💡 **Visual-Speech Alignment:** Speaker gestures along the blue forked branch on screen.

---

## [11:15 - 12:25] Scene #21: We build every prompt from the task history
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Diagram showing how raw Task History is dynamically transformed into model-tailored LLM prompts with compaction.
> * **On-Screen OCR:** We build every prompt from the task history ; Task history - every event, in order ; Add discount codes ; Read checkout.ts ; Edit discount.ts ; Expired code accepted ; Fix the expiry check ; Build the prompt at every step ; What the model sees: Prompt for this step ; Instructions: System instructions | Selected knowledge ; Earlier steps, summarized ; Recent steps, in full: Edit discount.ts | Expired code accepted | Fix the expiry check
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph History ["Task History (All Events)"]
>           H1["Add discount codes"]
>           H2["Read checkout.ts"]
>           H3["Edit discount.ts"]
>           H4["Expired code accepted"]
>           H5["Fix the expiry check"]
>       end
>   
>       History --> Builder["Build Prompt Render Engine"]
>   
>       subgraph Prompt ["Rendered Prompt for Model"]
>           P1["System Instructions & Knowledge"]
>           P2["Summarized Earlier Steps"]
>           P3["Recent Steps (Full Detail)"]
>       end
>   
>       Builder --> Prompt

**🎙️ Spoken Transcript:**
* **[11:15]** Then what we've done is to make sure that we have this append-only log, and from that we can actually build a prompt that we would feed into the actual LLM.
* **[11:45]** When you build a prompt... if you have a long history, you probably want to do some sort of compaction and summarize part of that history.
* **[12:10]** By separating the prompt from the actual task history, we're able to render prompts for any type of model or task.

💡 **Visual-Speech Alignment:** Speaker contrasts the complete persistent task log with the context-compacted rendered prompt.

---

## [12:26 - 13:04] Scene #22: Replay a run, event by event
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Live UI recording of slider stepping through 156 historical events to inspect intermediate thoughts and UI states.
> * **On-Screen OCR:** Replay a run, event by event ; Documentation feature overview ; Can you research our docs, and give an overview of the different features... 156 events ; Thought for 3s ; Analyzing documentation categories in links.txt ; Categorizing all documentation pages by section and topic ; Extracting detailed feature list and integration topics ; Testing doc parser script
> * **Structured Reconstruction:**
>   Event History Replay Slider [==================|   ] Event 78 / 156
>   Thought for 3s:
>   - Analyzing documentation categories in links.txt
>   - Categorizing all documentation pages by section and topic
>   - Extracting detailed feature list and integration topics
>   - Testing doc parser script

**🎙️ Spoken Transcript:**
* **[12:26]** So to show this event history in progress, we have this debug tool here. Here it's just a recording of me dragging this slider in our UI...
* **[12:40]** and you have 156 events here and each of those is an event in this event history.

💡 **Visual-Speech Alignment:** Speaker points to the interactive trajectory debug slider operating across 156 events.

---

## [13:05 - 13:34] Scene #23: The task history lives outside the process
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Architectural separation diagram showing stateless agent execution processes disconnected from persistent history stores.
> * **On-Screen OCR:** The task history lives outside the process ; Process running the agent: Can come and go ; Read the history ; Call the model ; Run a tool ; Write the result ; Task history - kept outside: Every event, in order ; A run can stop between steps. Another process picks it up from the record.
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph Process ["Process running agent (Stateless)"]
>           P1["Read history"] --> P2["Call model"] --> P3["Run tool"] --> P4["Write result"]
>       end
>   
>       subgraph Storage ["Task History (Persistent Store)"]
>           S1["Every event, in order"]
>       end
>   
>       Process <--> Storage

**🎙️ Spoken Transcript:**
* **[13:05]** The process that is running these agents, they're separate from the actual task history. And so the process is almost entirely stateless...
* **[13:20]** between each turn, it will actually just persist into the task history and so you can have a process come and go.

💡 **Visual-Speech Alignment:** Speaker highlights process statelessness enabling execution handing off between worker nodes.

---

## [13:35 - 14:36] Scene #24: 700+ deploys a day. Agents keep working.
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Timeline diagram showing a 10-hour agent run seamlessly handing off across Process A, B, C, D, E during deployments.
> * **On-Screen OCR:** 700+ deploys a day. Agents keep working. ; Task history - one run, hours of work ; Process running the agent: Process A -> Process B -> Process C -> Process D -> Process E ; 0h -> 10h ; deploy ; The process changes. The task keeps going.
> * **Structured Reconstruction:**
>   flowchart LR
>       Task["Task History (10h Run)"]
>       PA["Process A"] -- deploy --> PB["Process B"]
>       PB -- deploy --> PC["Process C"]
>       PC -- deploy --> PD["Process D"]
>       PD -- deploy --> PE["Process E"]
>       
>       PA -. executes .-> Task
>       PB -. executes .-> Task
>       PC -. executes .-> Task
>       PD -. executes .-> Task
>       PE -. executes .-> Task

**🎙️ Spoken Transcript:**
* **[13:35]** And then the question is, why do we care about this? Well, at Lovable, we deploy to this system 700 times per day. So that's about once every 2 minutes.
* **[13:50]** And you can imagine if you have an agent working for 10 hours... you want to not disrupt that agent when it's working.
* **[14:10]** We can actually make sure that we have one agent working on one task but we can have different processes taking up and actually doing the compute.

💡 **Visual-Speech Alignment:** Speaker tracks how ongoing long-duration agent tasks persist across back-to-back production deployments.

---

## [14:37 - 14:55] Scene #25: 02. Computer
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Section slide introducing topic 02: Computer (A place to do its work).
> * **On-Screen OCR:** 02. Computer ; A place to do its work ; Saved: Files | Running app | Local database | Memory

**🎙️ Spoken Transcript:**
* **[14:37]** The second piece of this platform is the computer, so this is where the work is actually happening.

💡 **Visual-Speech Alignment:** Transition slide opening the sandbox execution architecture.

---

## [14:56 - 15:44] Scene #26: New computers start from a golden checkpoint
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Diagram showing base Golden Checkpoint launching new project VMs in 230 milliseconds.
> * **On-Screen OCR:** New computers start from a golden checkpoint ; A VM resumes in 230 ms ; Golden checkpoint - Prepared once ; OS + system services ; Common tools installed ; Dev server ready to start ; New computer - Project A: Checkpoint + project code + dependencies ; New computer - Project B: Checkpoint + project code + dependencies ; New computer - Project C: Checkpoint + project code + dependencies ; We run around 1M sandboxes a day. Reusing setup matters at that scale.
> * **Structured Reconstruction:**
>   flowchart LR
>       Golden["Golden Checkpoint (Prepared once)<br/>- OS + system services<br/>- Common tools installed<br/>- Dev server ready to start"]
>       
>       Golden -- "Resumes in 230ms" --> ProjA["Project A VM<br/>[Checkpoint] + project code + dependencies"]
>       Golden -- "Resumes in 230ms" --> ProjB["Project B VM<br/>[Checkpoint] + project code + dependencies"]
>       Golden -- "Resumes in 230ms" --> ProjC["Project C VM<br/>[Checkpoint] + project code + dependencies"]

**🎙️ Spoken Transcript:**
* **[14:56]** And we've landed in the system that we've worked really hard now to develop, which is checkpointing a computer...
* **[15:10]** We have this common what we call a golden checkpoint which contains the OS and system services... and dev server ready to start.
* **[15:25]** And all of that you copy over in about 230 milliseconds. We run around 1M sandboxes a day.

💡 **Visual-Speech Alignment:** Speaker points to the 230ms cold start measurement visual.

---

## [15:45 - 16:15] Scene #27: We save the running computer, then resume it
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** State preservation sequence diagram showing active state saved into snapshot and resumed in place.
> * **On-Screen OCR:** We save the running computer, then resume it ; Agent turn: Running (Edited files, Installed packages, App + processes running) ; end of turn ; Snapshot: Saved (Files, Memory, Running processes) ; next visit ; Resumed: Running again (Same files, Same packages, App already running) ; Saved at the end of every agent turn. Resumed in place.
> * **Structured Reconstruction:**
>   flowchart LR
>       Run1["Running<br/>- Edited files<br/>- Installed packages<br/>- App running"] -->|"end of turn"| Save["Saved Snapshot<br/>- Files<br/>- Memory<br/>- Running processes"]
>       Save -->|"next visit"| Run2["Resumed Running<br/>- Same files<br/>- Same packages<br/>- App already running"]

**🎙️ Spoken Transcript:**
* **[15:45]** And so each time the agent is running and it finishes a turn, we will actually save a checkpoint of that computer.
* **[15:55]** And from that, we're able to again very quickly subsecond spin that computer up whenever you need it.

💡 **Visual-Speech Alignment:** Speaker points out snapshot saving of RAM and disk state at the conclusion of each agent turn.

---

## [16:16 - 16:51] Scene #28: Try different approaches from one snapshot
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Forking sandbox model diagram branching a single saved state into parallel Draft A and Draft B computers.
> * **On-Screen OCR:** Try different approaches from one snapshot ; Latest snapshot: One saved computer (Files, Running app, Local database, Memory) ; Draft A: Reschedule inside the app (same start + its own changes) ; Draft B: Reschedule by email (same start + its own changes) ; Two approaches, tried side by side. This is how Drafts work.
> * **Structured Reconstruction:**
>   flowchart LR
>       Snap["Latest Snapshot<br/>- Files<br/>- Running app<br/>- Local db<br/>- Memory"]
>       Snap --> DraftA["Draft A<br/>Reschedule inside the app<br/>(same start + its own changes)"]
>       Snap --> DraftB["Draft B<br/>Reschedule by email<br/>(same start + its own changes)"]

**🎙️ Spoken Transcript:**
* **[16:16]** The other thing we can do thanks to this checkpointing is that just like the trajectory itself... we can also fork the computer.
* **[16:30]** We have a feature in Lovable that is called drafts where you kind of work in different environments...

💡 **Visual-Speech Alignment:** Speaker demonstrates how sandbox snapshot forking underlies the 'Drafts' user feature.

---

## [16:52 - 17:20] Scene #29: Drafts share memory until they change it
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Memory grid diagram displaying Copy-on-Write (COW) page allocation across parallel drafts.
> * **On-Screen OCR:** Drafts share memory until they change it ; Shared snapshot memory ; copied on write ; Shared, unchanged ; Original page, left as it was ; Draft A: Reads the shared pages, Keeps its own copies of pages it changed ; Draft B: Reads the shared pages, Keeps its own copies of pages it changed ; Drafts share every page they haven't changed. A page is copied only when a draft writes to it.
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph Memory ["Shared Snapshot Memory Grid"]
>           S["Shared pages (Unchanged)"]
>           W1["Copied on write page (Draft A)"]
>           W2["Copied on write page (Draft B)"]
>       end
>   
>       Memory --> DraftA["Draft A<br/>Reads shared pages, keeps written page copies"]
>       Memory --> DraftB["Draft B<br/>Reads shared pages, keeps written page copies"]

**🎙️ Spoken Transcript:**
* **[16:52]** And so we've had to do some optimizations to make this feasible to actually run. One of these optimizations is copy-on-write on the RAM itself.
* **[17:05]** as soon as you start writing in a process to RAM, we will kind of copy that page over and only then will you start having to allocate new memory.

💡 **Visual-Speech Alignment:** Speaker points to orange copy-on-write blocks in the RAM allocation visual.

---

## [17:21 - 18:04] Scene #30: Load only the memory needed to resume
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Grid visual depicting streaming memory page restoration during VM resume.
> * **On-Screen OCR:** Load only the memory needed to resume ; A Lovable computer: dev server + database ; Hundreds of MB ; So a computer streams in only the memory it needs to keep running.
> * **Structured Reconstruction:**
>   flowchart TD
>       Grid["Memory Page Grid (Hundreds of MB)"] --> OnDemand["On-Demand Memory Streaming"]
>       OnDemand --> Boot["Fast VM Boot (Loads active pages first)"]

**🎙️ Spoken Transcript:**
* **[17:21]** And there's another optimization here also, which is that each of these sandboxes require a few hundreds of megabytes of memory.
* **[17:40]** thanks to being able to stream the memory, we can actually boot up the machine before all of the memory is actually ready on it.

💡 **Visual-Speech Alignment:** Speaker references the on-demand RAM page streaming graphic.

---

## [18:05 - 18:34] Scene #31: Meet OJ: Vite, rewritten in Rust
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Benchmark slide presenting OJ (Rust-based Vite server) metrics showing 2x faster cold start and 14s to 3s preview time decrease.
> * **On-Screen OCR:** Meet OJ: Vite, rewritten in Rust ; 2x faster cold starts ; 14s -> 3s to get a ready preview ; Every preview runs a real dev server. OJ is one Rust binary that runs your app the way Vite does, with no Node.js underneath. ; Open source: github.com/lovable-dev/oj
> * **Structured Reconstruction:**
>   | Metric | Node + Vite | OJ (Rust Vite) |
>   | --- | --- | --- |
>   | Cold Start Speed | Baseline | 2x faster |
>   | Time to Ready Preview | 14s | 3s |
>   | Runtime Dependency | Node.js | Single Rust Binary |

**🎙️ Spoken Transcript:**
* **[18:05]** And then we started asking ourselves, how can we make this even more efficient and even faster for our users?
* **[18:15]** we took Vite and we forked it and we rewrote it in Rust. And that made our cold starts two times faster and we went from getting this preview from 14 seconds to 3 seconds.

💡 **Visual-Speech Alignment:** Speaker points to the 14s -> 3s speedup metric and open-source GitHub URL.

---

## [18:35 - 19:15] Scene #32: OJ uses less memory, so more previews fit
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Density comparison graphic demonstrating 6.5x memory reduction when replacing Node+Vite with OJ.
> * **On-Screen OCR:** OJ uses less memory, so more previews fit ; 6.5x less dev-server memory than Node + Vite ; Measured before the app loads. ; Node + Vite (4 blocks) ; OJ (25 blocks) ; More previews fit on the same machine.
> * **Structured Reconstruction:**
>   | Parameter | Node + Vite | OJ |
>   | --- | --- | --- |
>   | Dev-server Memory | Baseline (1x) | 6.5x less |
>   | Density per Machine | 4 previews | 25 previews |

**🎙️ Spoken Transcript:**
* **[18:35]** The main thing that we made faster here is that Vite uses Node JS and we're able to drop that dependency... so that made the memory footprint be 6.5 times less.
* **[18:55]** we're able to run this extremely efficiently so that we can run lots and lots of agents in parallel.

💡 **Visual-Speech Alignment:** Speaker points out the visual contrast between 4 large Node blocks and 25 compact OJ blocks.

---

## [19:16 - 19:29] Scene #33: 03. Verification
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Section transition slide introducing topic 03: Verification.
> * **On-Screen OCR:** 03. Verification ; A place to check its work

**🎙️ Spoken Transcript:**
* **[19:16]** the last piece now is about verification, and of course this kind of computer and dev server is a big piece of being able to verify what an agent is doing.

💡 **Visual-Speech Alignment:** Transition slide opening verification feedback loops.

---

## [19:30 - 21:09] Scene #34: Two loops: fix it now, improve it later
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Comprehensive comparative table detailing Inner Loop checks (turn-time fixes) vs Outer Loop checks (horizon business metrics).
> * **On-Screen OCR:** Two loops: fix it now, improve it later ; Inner loop - during the turn ; The agent sees it and fixes it right away ; Build, lint + type errors - Automatic ; Runtime errors - Automatic + tools ; Browser + visual checks - Tools ; Judges in the turn - Automatic ; Domain scanners - Tools ; Backend logs + usage - Tools ; Guardrails + notifications - Automatic ; User-triggered fixes - User ; Outer loop - between turns ; The horizon between turns is long ; Product metrics: ; Production signals - Automatic ; Visitor behaviour - Automatic ; What users tell you - Explicit ; Automatic A/B tests - Automatic ; Business metrics: ; e.g. payments / signups / conversions ; Transactions -> conversions - Automatic ; Feedbacks fed back - Next turn ; Production outcomes reach the agent only as next-turn findings, never as a training signal.
> * **Structured Reconstruction:**
>   | Inner Loop (During turn) | Type | Outer Loop (Between turns) | Type |
>   | --- | --- | --- | --- |
>   | Build, lint + type errors | Automatic | Production signals | Automatic |
>   | Runtime errors | Automatic + tools | Visitor behaviour | Automatic |
>   | Browser + visual checks | Tools | What users tell you | Explicit |
>   | Judges in the turn | Automatic | Automatic A/B tests | Automatic |
>   | Domain scanners | Tools | Transactions -> conversions | Automatic |
>   | Backend logs + usage | Tools | Feedbacks fed back | Next turn |
>   | Guardrails + notifications | Automatic | | |
>   | User-triggered fixes | User | | |

**🎙️ Spoken Transcript:**
* **[19:30]** If you look at verification, you can think of these feedback loops... this inner loop and this outer loop.
* **[19:45]** This inner loop is during the turn of the agent: build, lint errors, type errors, runtime errors, headless browser.
* **[20:15]** Then you also have this outer loop between each turn... product metrics, visitor behavior, AB tests, business metrics.

💡 **Visual-Speech Alignment:** Speaker walks down both columns comparing real-time inner turn checks against production outer loop feedback signals.

---

## [21:10 - 22:05] Scene #35: The foundations for agents to take on more ambitious goals
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Graph visual showing networked multi-agent system orchestrating across connected computers and verification nodes.
> * **On-Screen OCR:** The foundations for agents to take on more ambitious goals ; FIG 1. - A HUNDRED AGENTS, ONE GOAL ; COMPUTER ; AGENT ; MESSAGE ; VERIFIED ; MOST CONNECTED COMPUTER
> * **Structured Reconstruction:**
>   flowchart TD
>       subgraph Swarm ["A Hundred Agents, One Goal"]
>           C1["MOST CONNECTED COMPUTER"]
>           A1["Agent 1"] <--> C1
>           A2["Agent 2"] <--> C1
>           A3["Agent 3"] <--> C1
>           A4["Agent 4"] <--> C2["Computer 2"]
>           C1 <--> C2
>       end

**🎙️ Spoken Transcript:**
* **[21:10]** and so this agentic system that we're building is running billions of tokens per minute and these computers we can spawn up with each agent...
* **[21:35]** And now we're kind of back to this quite beautiful setup where you have agents talking to agents and they're orchestrating. And this time it's actually working.

💡 **Visual-Speech Alignment:** Speaker points to the multi-agent network topology graph representing scaled autonomous agent interaction.

---

## [22:06 - 22:25] Scene #36: AI Engineer Code Summit Outro
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Closing graphic with summit branding and web URL.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; HTTPS://AI.ENGINEER

**🎙️ Spoken Transcript:**
* **[21:50]** And so if you're curious to try this out, you can head to lovable.dev... thank you so much, it's been a pleasure.

💡 **Visual-Speech Alignment:** Final outro banner shown as speaker concludes talk.

---
