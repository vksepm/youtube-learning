# Enriched Interleaved Transcript: 1,000 Claude Agents Formalized Fermat's Last Theorem — Lance Martin, Anthropic
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=wrfbI5eyLAI
**Model:** `gemini-4-hydrogen` | **Processing Mode:** `agentic`

---

## [00:00 - 00:12] Scene #1: AI Engineer Code Summit - Intro Bumper
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Conference opening bumper sequence on a black background displaying the AI Engineer Code Summit logo, followed by 'PRESENTED BY Google DeepMind' and a 'PLATINUM SPONSORS' card with logos for AWS, Devin, Databricks, Exa, Factory, and Sonar.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; PLATINUM SPONSORS ; aws ; Devin ; databricks ; exa ; FACTORY ; Sonar

**🎙️ Spoken Transcript:**

💡 **Visual-Speech Alignment:** No speech occurs during the opening conference sponsor bumper before the speaker takes the stage.

---

## [00:12 - 00:24] Scene #2: Exploring Claude's Frontiers
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Wide stage view transitioning into a split-screen broadcast layout. The main slide has a cream background with the title 'Exploring Claude's Frontiers' (with 'Claude's Frontiers' in terracotta red) and subtitle 'Lance Martin Member of Technical Staff' above an Anthropic logo. A branching grey tree/graph background features a bold black curved trajectory terminating at a red node.
> * **On-Screen OCR:** Exploring Claude's Frontiers ; Lance Martin Member of Technical Staff ; ANTHROPIC ; Exploring Claude's frontier ; Lance Martin / Member of Technical Staff ANTHROPIC

**🎙️ Spoken Transcript:**
* **[00:12]** Uh, I'm Lance from Anthropic. I know we've had some issues with the prior keynotes, so, we're set to go. I'm going to tell two stories about getting the most out of Claude and exploring Claude's frontier capabilities.

💡 **Visual-Speech Alignment:** Lance Martin introduces himself and the talk title ('Exploring Claude's Frontiers') while standing at the podium in front of the title slide.

---

## [00:24 - 00:31] Scene #3: Multi-agent
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Section divider slide showing 'Multi-agent' in terracotta red next to the highlighted root node of the branching tree illustration, with a thick black trajectory line sweeping downward to the right.
> * **On-Screen OCR:** Multi-agent ; ANTHROPIC

**🎙️ Spoken Transcript:**
* **[00:24]** So the first is multi-agent and this is a blog I wrote with the Fable 5.2 launch. And I want to kind of tell the story of what happened here.

💡 **Visual-Speech Alignment:** The speaker transitions into the first story ('multi-agent') as the 'Multi-agent' section title card appears on screen.

---

## [00:31 - 01:18] Scene #4: Fermat's Last Theorem
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide summarizing Fermat's Last Theorem with the central equation 'a^n + b^n = c^n', a horizontal timeline spanning more than 350 years from c. 1637 to 2026, and a bottom callout box titled 'What made it hard'.
> * **On-Screen OCR:** Fermat's Last Theorem ; A one-line claim that stood unproven for more than 350 years ; a^n + b^n = c^n ; has no solutions in positive whole numbers when n is greater than 2 ; When n = 2 there are endless solutions, such as 3^2 + 4^2 = 5^2 ; More than 350 years ; c. 1637: Fermat writes the claim in the margin of a book ; 1980s: Frey, Serre and Ribet tie it to a deep conjecture ; 1993: Wiles announces a proof, and a gap is found ; 1995: Wiles and Taylor publish the proof: 129 pages in all ; 2026: First complete computer-checked proof, in Lean ; What made it hard ; The statement is simple, but the proof needed a link between two distant areas of mathematics, elliptic curves and modular forms.

**🎙️ Spoken Transcript:**
* **[00:31]** So, Fermat's Last Theorem is one of the more kind of famous claims in mathematics. It stood unproven for around 350 years, and it's actually a very simple statement, just a to the n plus b to the n equals c to the n has no solution for any positive whole numbers greater than two.
* **[00:48]** Now, this deceptively simple kind of statement has proven to be quite difficult to actually prove. In the mid-90s, Sir Andrew Wiles did prove it. He put out a proof, and it took him 7 years of work, it was extremely painstaking.
* **[01:02]** And since that time, a major effort and interest in mathematics has been formalizing that proof, where basically computationally checking every step. So proofs are kind of long chains of logic and you actually can computationally check proofs using different systems, what I'll talk about for example using Lean.

💡 **Visual-Speech Alignment:** The speaker points toward the slide equation 'a^n + b^n = c^n', the 'More than 350 years' timeline (referencing 1993/1995 Wiles proof and the 2026 Lean entry), while explaining the history and formalization goal.

---

## [01:18 - 01:27] Scene #5: Beauty is Suffering [Part 1 - The mathematician]
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Screenshot of a YouTube video titled 'Beauty is Suffering [Part 1 - The mathematician]' showing Sir Andrew Wiles working at a wooden desk piled high with handwritten mathematical manuscripts, with a 'Source' link beneath.
> * **On-Screen OCR:** YouTube ; Beauty is Suffering [Part 1 - The mathematician] ; scienceofeverything ; Source ; ANTHROPIC

**🎙️ Spoken Transcript:**
* **[01:18]** So this is just kind of a visual kind of explaining—there's a very interesting video showing the effort that he went through; it is an extremely painstaking process to establish this proof.

💡 **Visual-Speech Alignment:** The speaker gestures toward the YouTube video screenshot of Andrew Wiles surrounded by stacks of paper to illustrate how painstaking manual proof work is.

---

## [01:27 - 01:47] Scene #6: Formalizing Fermat's Last Theorem
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide quoting an article excerpt titled 'Formalizing Fermat's Last Theorem' with pink/red highlighter emphasis on the first three sentences explaining proof assistants like Lean and a second paragraph noting the 86-page blueprint.
> * **On-Screen OCR:** Formalizing Fermat's Last Theorem ; One way to check a proof's correctness is to ask a computer to do it. Proof assistants like Lean verify the logic of a proof algorithmically, demonstrating its correctness beyond a doubt. The difficult part for humans is rewriting the proof so Lean can understand it. While a proof written for human readers will skip many obvious steps, Lean needs to see every step, no matter how trivial. Human proofs also build on centuries of published work, while a formalization starts from the tiny fraction of math that's been formalized already. ; For FLT, the formalization process was expected to take years. Just the blueprint the mathematical community has been using to describe the initial phase of the project runs to 86 pages. ; Source ; ANTHROPIC

**🎙️ Spoken Transcript:**
* **[01:27]** And in September we published that we used Claude to formalize it. This is like the first very important result that we kind of shared along these lines. And we used Lean to do it, so Lean allows you to computationally verify every step in a proof. Now doing this though is extremely painstaking.

💡 **Visual-Speech Alignment:** The highlighted sentences on screen directly correspond to the speaker's explanation of using Lean to verify every single logical step computationally.

---

## [01:47 - 02:10] Scene #7: Claude's initial attempts
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Side-by-side comparison diagram illustrating early multi-agent coordination failures. On the left ('Early success'), 6 Agent boxes connect cleanly to a central 'Project state' box, yielding 'About 7% of the non-boilerplate lines in the final proof came from these failed attempts'. On the right ('Then they lost track'), 6 Agent boxes have broken/red-X connections to a red dashed 'Project state?' box, leading to 'Then Prove2Me: The effort succeeded after the switch to this harness'.
> * **On-Screen OCR:** Claude's initial attempts ; Agents had some early success, then lost track of the project's state and stopped collaborating effectively. ; Early success ; Agent ; Project state ; Then they lost track ; Project state? ; About 7% of the non-boilerplate lines in the final proof came from these failed attempts ; Then Prove2Me ; The effort succeeded after the switch to this harness ; Source
> * **Structured Reconstruction:**
>   flowchart LR
>     subgraph EarlySuccess[Early success]
>       A1[Agent] --> PS1[Project state]
>       A2[Agent] --> PS1
>       A3[Agent] --> PS1
>       A4[Agent] --> PS1
>       A5[Agent] --> PS1
>       A6[Agent] --> PS1
>       Note1[About 7% of non-boilerplate lines]
>     end
>     subgraph LostTrack[Then they lost track]
>       B1[Agent] -.->|lost| PS2[Project state?]
>       B2[Agent] -.->|lost| PS2
>       B3[Agent] -.->|lost| PS2
>       B4[Agent] -.->|lost| PS2
>       B5[Agent] -.->|lost| PS2
>       B6[Agent] -.->|lost| PS2
>       Note2[Then Prove2Me: Effort succeeded after switch]
>     end
>     EarlySuccess --> LostTrack

**🎙️ Spoken Transcript:**
* **[01:48]** We started with a team of about a dozen agents and this is kind of just showing a schematic of that team. Very early on that team didn't work very effectively. We had to give it something called Prove2Me. Now this is a kind of a platform for orchestrating mathematics proofs, and it helped the agents significantly manage the state of the project.

💡 **Visual-Speech Alignment:** When the speaker says 'this is kind of just showing a schematic of that team', he gestures to the two agent-to-project-state diagrams, and 'something called Prove2Me' maps to the 'Then Prove2Me' callout at the bottom right.

---

## [02:10 - 02:24] Scene #8: Prove2Me's architecture
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Four-panel system architecture diagram showing how Prove2Me manages shared state: top-left 'Shared graph of statements' (tree rooted at 'Fermat's Last Theorem' with green 'Proved' nodes and red 'Open' nodes), top-right 'Each agent's loop' (4 steps: 1 Ask what's open, 2 Search before writing, 3 Prove it, or split it, 4 Submit it for checking), bottom-right 'Lean checker on the server', and bottom-left 'Search and milestones'.
> * **On-Screen OCR:** Prove2Me's architecture ; The project's state lived in a shared graph, not in any agent's memory. ; Shared graph of statements ; Fermat's Last Theorem ; Proved ; Open ; Each line is a proof sketch: a parent proved assuming its children. Proved status flows up the graph by itself. What's left is always visible: red statements are open. ; Each agent's loop ; 1 Ask what's open ; 2 Search before writing ; 3 Prove it, or split it ; 4 Submit it for checking ; Marks proved ; Search and milestones ; Reuse results, aim at key statements ; Lean checker on the server ; The server verifies every submission ; Source
> * **Structured Reconstruction:**
>   flowchart TB
>     Graph[Shared graph of statements: Fermat's Last Theorem tree - Proved/Open] <--> Loop[Each agent's loop: 1 Ask what's open, 2 Search before writing, 3 Prove it or split it, 4 Submit it for checking]
>     Loop -->|Submits proof| Checker[Lean checker on the server: Verifies every submission]
>     Checker -->|Marks proved| Graph
>     Graph <--> Search[Search and milestones: Reuse results, aim at key statements]

**🎙️ Spoken Transcript:**
* **[02:10]** Prove2Me you can think about as a harness. So basically it provides the agents with a graph that they can query. So it's basically lots of scaffolding around this problem statement. You can think of it as like a very domain-specific harness, okay?

💡 **Visual-Speech Alignment:** The speaker's description of 'a graph that they can query' directly maps to the 'Shared graph of statements' box on the left connected to 'Each agent's loop' on the right.

---

## [02:24 - 02:30] Scene #9: Formalizing Fermat's Last Theorem (Results Excerpt)
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Blog post excerpt with a concentric/geometric green-and-white graphic on the left and highlighted text on the right reporting that Claude completed the proof in 11 days, producing 30,300 theorems (29,500 in the final proof) and 1.5 million lines of Lean code (over 5x Mathlib).
> * **On-Screen OCR:** Formalizing Fermat's Last Theorem ; Claude completed the proof in 11 days, producing computer-verifiable proofs of 30,300 theorems along the way (using 29,500 in the final proof). Dozens of Claude agents collaborated to define concepts, prove intermediate theorems, and use those theorems to prove even harder statements. At 1.5 million lines of Lean code, Claude's proof is over 5x the size of Mathlib, the principal community library of mathematical proofs this theorem builds on. ; Source

**🎙️ Spoken Transcript:**
* **[02:24]** Now this is all setting up what we actually did. We reported, this was back in September, the formalization.

💡 **Visual-Speech Alignment:** The speaker points to the highlighted September result summary card before transitioning to the new Fable 5.2 experiment.

---

## [02:30 - 03:00] Scene #10: Try with a larger Fable 5.2 agent team
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Clean bulleted slide setting up the new experiment with three bullet points under the heading 'Try with a larger Fable 5.2 agent team'.
> * **On-Screen OCR:** Try with a larger Fable 5.2 agent team ; 1000 agent team ; Minimal harness ; No steering

**🎙️ Spoken Transcript:**
* **[02:30]** Now what I want to do for 5.2 is show, can we have a much larger team of agents, so going from around a dozen to 1000? Do this formalization with no domain-specific harness, so without Prove2Me, and with no human steering with respect to the solution. So the report we talked about in September had both this domain harness, Prove2Me, and a lot of support from a researcher. This is testing whether or not a large team of Fable 2 agents can autonomously develop this formalization themselves.

💡 **Visual-Speech Alignment:** Each clause of the speaker's setup ('going from around a dozen to 1000', 'without Prove2Me', 'with no human steering') corresponds one-to-one with the three bullets on screen.

---

## [03:00 - 03:57] Scene #11: Sandboxing, Real-time monitoring, and Team infrastructure
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Detailed three-part systems architecture diagram. Section 1 ('Sandboxing') shows 'Agent sandbox x 1,000' containing Agent loop, Tools (bash, file edits), and Files (/tmp, mathlib), with no internet access, no shared filesystem, and no direct path to other sandboxes. Outbound traffic goes exclusively ('Only Git and SQL') through '2. Real-time monitoring' -> 'Gateway' (Auth, Logging, Safety monitoring: Collects Claude API calls and tool calls, inspects every request for escapes and misuse) -> 'Team infrastructure' ('Git repository: Stores code and proofs, enforces rules on main' and 'Postgres database: Holds coordination tables, holds team communication'). Below is '3. Offline monitoring' ('Run sensors' checking runs every 10 minutes).
> * **On-Screen OCR:** 1 Sandboxing ; No internet access ; No shared filesystem ; No direct path to other sandboxes ; Agent sandbox x 1,000 ; Agent loop ; Calls Claude API ; Tools: bash, file edits ; Files: /tmp, mathlib ; 2 Real-time monitoring ; Gateway enforces rules and logs all traffic ; Never trusts agents ; Gateway ; Auth: Identities each sandbox ; Logging: Records all requests ; Safety monitoring: Collects Claude API calls and tool calls, inspects every request for escapes and misuse ; Git and SQL requests ; Team infrastructure ; Shared state, isolated from sandboxes ; Git repository: Stores code and proofs, enforces rules on main ; Postgres database: Holds coordination tables, holds team communication ; Only Git and SQL ; 3 Offline monitoring ; Checks runs every 10 minutes ; Run sensors ; Offline monitoring ; Blocks a sandbox if needed ; Checks for escapes/sabotage ; Reads from Postgres/Git ; Builds live visualizations ; Source
> * **Structured Reconstruction:**
>   flowchart LR
>     subgraph Sandboxing[1 Sandboxing]
>       SB[Agent sandbox x 1,000: Agent loop, Tools: bash/file edits, Files: /tmp, mathlib]
>     end
>     subgraph Realtime[2 Real-time monitoring]
>       GW[Gateway: Auth, Logging, Safety monitoring]
>       subgraph Infra[Team infrastructure]
>         Git[Git repository]
>         PG[Postgres database]
>       end
>       GW -->|Git and SQL requests| Git
>       GW -->|Git and SQL requests| PG
>     end
>     subgraph Offline[3 Offline monitoring]
>       Sensors[Run sensors: Checks runs every 10 minutes]
>       OM[Offline monitoring]
>       Sensors --> OM
>     end
>     SB -->|Only Git and SQL| GW
>     GW --> Sensors
>     OM -.->|Reads| Infra
>     OM -.->|Blocks sandbox if needed| GW

**🎙️ Spoken Transcript:**
* **[03:00]** So, this is just giving you a sense for the harness. It looks kind of complicated but it's actually pretty simple. Each of the thousand agents has its own sandbox with restricted network access. Most of this is directed on safety and security. So, we have a thousand agents. Each have their own sandbox. They can connect to two different things, Git and a SQL database, that's it. Those are the core primitives that we give this team.
* **[03:24]** And we have real-time monitoring looking at every tool call for things like escapes. We also have offline monitoring looking at runs of all the agents every 10 minutes. This is kind of the setup. Thousand agent team, very simple primitives, just Git and a database.
* **[03:41]** The prompting is pretty simple. It establishes one lead agent, 999 helper agents. It gives them awareness of Git and the database and the problem statement, that's really it. We want to see if this team could then do this formalization.

💡 **Visual-Speech Alignment:** The speaker walks left-to-right across the diagram: 'own sandbox' -> 'Agent sandbox x 1,000' box; 'Git and a SQL database' -> 'Only Git and SQL' arrow into 'Team infrastructure' ('Git repository' and 'Postgres database'); 'real-time monitoring' -> Section 2 'Gateway'; 'offline monitoring' -> Section 3 'Run sensors' and 'Offline monitoring'.

---

## [03:57 - 04:31] Scene #12: Agent-Created Postgres Coordination Tables
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Diagram showing '1 lead' at the top and '999 helpers' at the bottom communicating via five SQL tables created autonomously by the lead agent: 'Announce' (The lead's orders to everyone), 'Assign' (Who works on what), 'Notes' (An open board), 'Subtasks' (A shared to-do list), and 'Landed' (A log of finished work), with directed Write and Read arrows.
> * **On-Screen OCR:** 1 lead ; Write ; Read ; Announce: The lead's orders to everyone (e.g. how to split up the work, or to ease off the repo) ; Assign: Who works on what (e.g. which helper owns or deputies on each statement) ; Notes: An open board (e.g. helpers saying which piece they're taking, or reporting progress) ; Subtasks: A shared to-do list (e.g. a task anyone adds, claimed by the first helper to grab it) ; Landed: A log of finished work (e.g. which statement or piece landed, its commit, and whether it passed the team's checks) ; Can write ; 999 helpers ; Source
> * **Structured Reconstruction:**
>   flowchart TB
>     Lead[1 lead]
>     Helpers[999 helpers]
>     Announce[Announce: The lead's orders to everyone]
>     Assign[Assign: Who works on what]
>     Notes[Notes: An open board]
>     Subtasks[Subtasks: A shared to-do list]
>     Landed[Landed: A log of finished work]
>     Lead -->|Write| Announce
>     Lead -->|Read| Announce
>     Announce -->|Read| Helpers
>     Lead -->|Write| Assign
>     Lead -->|Read| Assign
>     Assign -->|Read| Helpers
>     Lead -->|Write| Notes
>     Lead -->|Read| Notes
>     Helpers -->|Write/Read| Notes
>     Lead -->|Write| Subtasks
>     Lead -->|Read| Subtasks
>     Helpers -->|Write/Read| Subtasks
>     Lead -->|Write| Landed
>     Lead -->|Read| Landed
>     Helpers -->|Write/Read| Landed

**🎙️ Spoken Transcript:**
* **[03:57]** What's interesting is this is kind of the story about what the team did. The lead, very early on, five minutes into the run, basically created these database tables. So agents now are sufficiently advanced that they can actually build primitives that they need to solve hard problems. We didn't tell them to build these tables. These are the tables that the agent actually just kind of built.
* **[04:17]** A table where the lead can announce things, assign roles to workers, everyone can—agents can post notes, a subtask table, a table that indicates whether or not things are landed. So the lead just creates these tables to orchestrate this team.

💡 **Visual-Speech Alignment:** The speaker enumerates the five table boxes from left to right ('announce' -> Announce, 'assign roles' -> Assign, 'post notes' -> Notes, 'subtask table' -> Subtasks, 'whether or not things are landed' -> Landed).

---

## [04:31 - 05:17] Scene #13: Database Activity Visualization (Hour 0.0 - Hour 22.4)
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Animated bipartite flow visualization tracking database writes (red/orange lines from the top row of writers: Lead and helpers 1-999) and reads (green lines to the bottom row of readers) across the coordination tables from Hour 0.0 to Hour 22.4. Counters on the left tally total writes and reads across the run.
> * **On-Screen OCR:** Hour 22.4 (final frame shown) ; 26,347 writes across the run ; 281,657 reads across the run ; Writers: the lead and helpers 1-999, in numeric order ; Readers: the same 1,000 agents ; How to read it: ; A write, from the agent (top row) down to the table ; A read, from the table down to the agent (bottom row) ; Tables light up when created or written to ; Active agents and reads are fading over 5 minutes ; A table not created yet ; Announce: writes 20, reads 66,464 ; Assign: writes 27, reads 26,227 ; Notes: writes 17,909, reads 99,365 ; Subtasks: writes 7,909, reads 60,425 ; Landed: writes 436, reads 23,609 ; Other tables: writes 46, reads 5,567 ; Source
> * **Structured Reconstruction:**
>   | Table | Purpose / Activity | Writes (at Hour 22.4) | Reads (at Hour 22.4) |
>   |---|---|---:|---:|
>   | Announce | Lead's orders to everyone | 20 | 66,464 |
>   | Assign | Who works on what | 27 | 26,227 |
>   | Notes | Open communication board | 17,909 | 99,365 |
>   | Subtasks | Shared to-do list | 7,909 | 60,425 |
>   | Landed | Log of finished work | 436 | 23,609 |
>   | Other tables | Additional auxiliary tables | 46 | 5,567 |
>   | **Total** | **All tables across run** | **26,347** | **281,657** |

**🎙️ Spoken Transcript:**
* **[04:31]** And this is a visualization showing how the agents wrote to and read from these tables over the course of this run. Now red on the top is showing writes to the tables, green is showing reads. What's really interesting is you can see occasionally the lead writing to the announce table. This kind of announces major global announcements about the problem.
* **[04:51]** It also assigns workers, these helpers, different statements in this theorem as they proceed. Notes are where they communicate and share kind of progress. Landed is where they kind of actually write the Lean code as part of the proof. And so the agents all autonomously without specific prompting use the database in this way to coordinate their work on this extremely hard long-horizon task. This ran for around 30 hours.

💡 **Visual-Speech Alignment:** The speaker points out 'red on the top is showing writes to the tables, green is showing reads', referring to the top red edges from Lead/helpers into the middle table boxes and the bottom green edges flowing down to the 1,000 reader agents.

---

## [05:17 - 05:46] Scene #14: LanglandsTunnel Radial Task Tree (Hour 20.5 - Hour 28.9)
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Animated radial dependency tree centered on 'LanglandsTunnel' growing from Hour 20.5 (1 task, 0 done) to Hour 28.9 (2,418 tasks, 2,364 done). Grey nodes represent written-but-unstarted tasks, orange arcs represent claimed/in-progress/unblocked tasks, and dark terracotta/red nodes mark completed tasks.
> * **On-Screen OCR:** Hour 28.9 ; 2,418 tasks in the 2,418-task subtree ; 2,364 done (first marked done, with a committed file) ; LanglandsTunnel ; Red: hour the task was first marked done ; Written, not started: grey ; Claimed, in progress, or unblocked: orange (darker = claimed) ; A sub-area ; Large solid circles: core statements ; Source
> * **Structured Reconstruction:**
>   flowchart TB
>     Root((LanglandsTunnel Root)) --> Area1[Core Statement / Sub-area 1]
>     Root --> Area2[Core Statement / Sub-area 2]
>     Root --> Area3[Core Statement / Sub-area 3]
>     Area1 --> Sub1[2,418 Subtasks]
>     Sub1 --> Done1[2,364 Done - Red/Terracotta]
>     Sub1 --> Active1[In Progress / Claimed - Orange]
>     Sub1 --> Open1[Written Not Started - Grey]

**🎙️ Spoken Transcript:**
* **[05:17]** And for particularly challenging parts of this proof, they actually developed their own abstractions. This is actually a task tree for this LanglandsTunnel, this is one of the harder statements in the proof. And this is actually showing the different dependencies of the tasks within this tree and this is actually showing over time the progress from like in progress to done in red. So the point of all this is really just to kind of highlight agents can solve very long horizon problems without much scaffolding.

💡 **Visual-Speech Alignment:** When the speaker says 'task tree for this LanglandsTunnel', he refers to the central radial node labeled 'LanglandsTunnel', and 'from like in progress to done in red' matches the color legend turning orange arcs to red.

---

## [05:46 - 06:22] Scene #15: 60 Sub-problems and Agent Allocation Map (Hour 0.0 - Hour 16.8)
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Animated cluster map displaying the 60 statements of the proof grouped into 7 thematic panels ('Landed first', 'Judged doable', 'Not safe, shifted by hour 1.3', 'Not safe, taken up from hour 1.0', 'Modularity lifting', 'LanglandsTunnel', 'Last bits'), plus bottom boxes for 'Also working on or waiting on a sync point' and 'Idle / syncing'. At Hour 16.8, 48 of 60 statements are proved and agent dots dynamically migrate between clusters.
> * **On-Screen OCR:** Hour 16.8 (final frame shown) ; 48 of 60 statements proved ; How to read the map ; One of the problem's 60 statements, not yet proved ; A proved statement ; One of the 999 helpers, colored by status: ; 960 at a statement ; 16 at a sync, wait, or shared task ; 12 waiting on a sync or shared task ; 11 idle (waiting, sleeping or polling) ; Also working on or waiting on a sync point ; Idle / syncing ; Landed first ; Judged doable ; Not safe, shifted by hour 1.3 ; Not safe, taken up from hour 1.0 ; Modularity lifting ; LanglandsTunnel ; Last bits ; Fermat's Last Theorem ; Source
> * **Structured Reconstruction:**
>   | Metric / Cluster | Status at Hour 16.8 |
>   |---|---|
>   | Statements proved | 48 of 60 |
>   | Helpers at a statement | 960 |
>   | Helpers at sync/wait/shared task | 16 |
>   | Helpers waiting on sync/shared task | 12 |
>   | Helpers idle (waiting/sleeping/polling) | 11 |
>   | Cluster panels | Landed first, Judged doable, Not safe (shifted by hr 1.3), Not safe (taken up from hr 1.0), Modularity lifting, LanglandsTunnel, Last bits |

**🎙️ Spoken Transcript:**
* **[05:46]** This is showing kind of the overall kind of allocation of the agents across these different tasks over the course of this run. And this kind of shows how the lead and the agents themselves kind of reallocate themselves and kind of reassign themselves to different parts of the problem as it progresses, and as these statements—there are 60 statements in this proof—are all solved. So, the agents using simple primitives, Git and the database, can coordinate themselves across this very hard problem to solve it progressively over time. That's really the key point. And you can see time progressing here.

💡 **Visual-Speech Alignment:** The speaker references the moving dots across the 7 panels ('allocation of the agents across these different tasks') and 'there are 60 statements in this proof' matches the top-left counter '48 of 60 statements proved'.

---

## [06:22 - 07:18] Scene #16: TOTAL FREEZE OF origin/main, EFFECTIVE NOW.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Minimalist quote slide displaying a verbatim note left by the lead agent in monospace-style serif text (with the first letter 'T' of TOTAL slightly clipped at the left margin). Note: at 06:34-06:35 the speaker briefly clicks to the Memory slide and immediately clicks back.
> * **On-Screen OCR:** "TOTAL FREEZE OF origin/main, EFFECTIVE NOW. ; ... Magnificent work, all 999 of you."

**🎙️ Spoken Transcript:**
* **[06:22]** This, from one of our runs, this is one of the notes that the agents left, basically saying total freeze of the origin effective now, magnificent work all 999 of you.
* **[06:32]** So, basically, what is really interesting about this is we were able to show this formalization, which was expected to take many, many years. Back in September, we showed initially we could do it with like a dozen agents with a lot of scaffolding—this Prove2Me harness and a lot of poking and support from a researcher. This new result is showing we provide a lot of structure in terms of safety and monitoring, but the agent team was able to accomplish this task with very simple primitives without a domain-specific harness in this particular case. And agents are getting increasingly good at orchestrating themselves and knowing how to coordinate using these simple primitives for very challenging long-horizon tasks. That's really the key kind of observation which is very interesting from this work.

💡 **Visual-Speech Alignment:** The speaker reads the exact agent note displayed in the center of the slide ('total freeze of the origin effective now, magnificent work all 999 of you') and summarizes the multi-agent formalization takeaways.

---

## [07:18 - 07:42] Scene #17: Memory
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Section divider slide showing 'Memory' in terracotta red next to a highlighted node of the radial/spiral branching tree diagram, with a black spiral path winding inward to the center node.
> * **On-Screen OCR:** Memory ; ANTHROPIC

**🎙️ Spoken Transcript:**
* **[07:18]** Now I want to shift gears and talk about memory, which is entirely different when I talk about in terms of multi-agent, but it's highlighting another area where we're seeing Claude gain significant capability. So previously we talked kind of about Claude's ability to orchestrate large teams to solve very long horizon problems. Memory is a different capability. It's showing that Claude is increasingly capable to organize its context to help solve long horizon problems.

💡 **Visual-Speech Alignment:** The 'Memory' section slide appears right as the speaker states 'Now I want to shift gears and talk about memory'.

---

## [07:42 - 09:04] Scene #18: Søren Kierkegaard Quote
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Quote slide displaying '"Life can only be understood backward, but it must be lived forward."' attributed to Søren Kierkegaard.
> * **On-Screen OCR:** "Life can only be understood backward, but it must be lived forward." ; Søren Kierkegaard ; ANTHROPIC

**🎙️ Spoken Transcript:**
* **[07:42]** So, I published a blog on this fairly recently. And this is actually the lead line of the blog, and I think this actually encapsulates the idea of the blog and one of the central ideas around memory, I think is very interesting. And this is from the philosopher Kierkegaard, so life can only be understood backwards, but it must be lived forwards.
* **[08:00]** There is a fundamental paradox of agent memory because agents write to memory typically as they go about a task. They encounter something weird or interesting, they write to memory. But memory needs to be a coherent map of an agent's knowledge that agents can look back on and reflect on. So when they're writing to memory, they're writing kind of myopically, they're looking greedily within a session saying, oh, this seems important for this task at hand. But memory needs to be something that's globally coherent and not redundant.
* **[08:27]** So this is like a very tricky paradox of memory and frankly we as humans have the same kind of challenge. We go about our day, we write short-term memories—believe that the hippocampus kind of is the place that's orchestrated. At night, it's believed that the hippocampus replays to the neocortex, which is where long-term knowledge is stored. So it's believed that actually this dreaming process for humans helps consolidate the fragments or like the most important aspects of our daily experience into long-term knowledge. So there's this decomposition between daily memory and kind of long-term knowledge. And we found agents can benefit from the same decomposition. That's really the key point of the post.

💡 **Visual-Speech Alignment:** The speaker reads the Kierkegaard quote on screen and uses it to frame the paradox between live, myopic memory writing and retrospective consolidation ('dreaming').

---

## [09:04 - 10:56] Scene #19: CL-Bench database task & Accumulated reward over questions
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Two-panel benchmark slide. Left panel ('CL-Bench database task') is a grouped bar chart comparing 'With memory store' (solid bars) vs 'Stateless baseline' (hatched bars) across Opus 5.5, Sonnet 5.5, Opus 5, Opus 4.7, Sonnet 5, and Sonnet 4.6. Right panel ('Accumulated reward over questions') shows running mean reward across questions 1 to 30+ for each model with and without memory.
> * **On-Screen OCR:** CL-Bench database task ; With memory store ; Stateless baseline ; Opus 5.5: 0.695 (With memory) vs 0.585 (Stateless) ; Sonnet 5.5: 0.683 (With memory) vs 0.517 (Stateless) ; Opus 5: 0.677 (With memory) vs 0.484 (Stateless) ; Opus 4.7: 0.630 (With memory) vs 0.364 (Stateless) ; Sonnet 5: 0.488 (With memory) vs 0.340 (Stateless) ; Sonnet 4.6: 0.364 (With memory) vs 0.351 (Stateless) ; Accumulated reward over questions ; Question number (running mean of all questions so far) ; Running reward ; Source
> * **Structured Reconstruction:**
>   | Model | With Memory Store (Task Score) | Stateless Baseline (Task Score) | Memory Gain |
>   |---|---:|---:|---:|
>   | Opus 5.5 | 0.695 | 0.585 | +0.110 |
>   | Sonnet 5.5 | 0.683 | 0.517 | +0.166 |
>   | Opus 5 | 0.677 | 0.484 | +0.193 |
>   | Opus 4.7 | 0.630 | 0.364 | +0.266 |
>   | Sonnet 5 | 0.488 | 0.340 | +0.148 |
>   | Sonnet 4.6 | 0.364 | 0.351 | +0.013 |

**🎙️ Spoken Transcript:**
* **[09:04]** Now here's some results kind of telling the story. So this is actually an open-source continuous learning benchmark called CL-Bench. And this is showing that different models, as you go from like Sonnet up to like Opus 5, get increasingly good at using memory. Now this task is a very simple setup. It asks Claude to solve 40 questions about a database. In between each question, it's a fresh session and Claude can write to notes like a memory directory between each session.
* **[09:40]** So what happens is the dark bars are showing when you give Claude the memory store and then the hatched is like without memory, okay? Now what's interesting is with Sonnet 4.6, giving Sonnet memory, you can see in the dark blue, that's very little benefit. Can't really use memory. And we looked into the results and we found Sonnet doesn't reliably know when to write to memory and also doesn't really naturally read from memory, okay?
* **[10:10]** It's also worth noting that these experiments are done with no specific memory prompting. It just tells the agent the directory is available, use memory if you want, that's really it. So Sonnet 4.6 doesn't natively use memory effectively. Sonnet 5 does indeed better, Opus and so on. And so basically, the models get better and better with the same simple instruction in using memory. And really the key idea here is that what happens is, with stronger models, they know intrinsically when to write to memory and they kind of know intrinsically when to read from memory to retrieve information. Their memories are also better—they're like highly verified statements or predictions about kind of the state of the database or what may happen next, versus earlier models tend to write lower quality memories.

💡 **Visual-Speech Alignment:** The speaker points to the dark blue vs hatched bars on the far right ('Sonnet 4.6' 0.364 vs 0.351) to show minimal memory benefit, then gestures left toward 'Sonnet 5' and 'Opus' bars where the gap widens dramatically.

---

## [10:56 - 12:50] Scene #20: Claude Sonnet 3.7 vs Claude Fable 5 Memory Directories (Pokémon)
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Area-proportional treemap visualization comparing the size and contents of memory directories generated while playing Pokémon. Left treemap: 'Claude Sonnet 3.7' (412 files, 917,035 characters [top 6,969]), dominated by huge orange boxes ('Named like fresh starts or raw "memories" 436k') and grey topical boxes ('database', 'game_state', etc.). Right treemap: 'Claude Fable 5' (33 files, 46,446 characters [entire 108h]), dramatically smaller and focused on strategic topical files like 'locations/', 'general.md'.
> * **On-Screen OCR:** Named like fresh starts or raw "memories" 436k ; Abandoned (old, bug, emergency, etc.) ; Other topical directories ; Claude Sonnet 3.7: 412 files, 917,035 characters (top 6,969) ; Same scale throughout: area is proportional to characters of memory. ; Claude Fable 5: 33 files, 46,446 characters (entire 108h) ; locations/, general.md, game_state/ ; Source
> * **Structured Reconstruction:**
>   | Model | Memory File Count | Total Characters | Scope / Quality |
>   |---|---:|---:|---|
>   | Claude Sonnet 3.7 | 412 files | 917,035 chars | Top 6,969; bloated with raw/abandoned memories (436k in fresh-start/raw files) |
>   | Claude Fable 5 | 33 files | 46,446 chars | Entire 108h run; tight, strategic topical insights (e.g., locations/, general.md) |

**🎙️ Spoken Transcript:**
* **[10:56]** And I'll show you a very fun example of this from a different game. This is from Pokémon. So this is showing you Claude 3.7's memory directory from Pokémon versus Fable 5. Here's the key point: the size of each box indicates the number of memory files in each of these directories, okay? So when we have Claude play Pokémon, we give Claude a memory directory just like I did in that prior benchmark, right? Claude can write whatever it wants to a directory while it plays the game.
* **[11:25]** What's really interesting is Sonnet 3.7 we see it writes a huge amount to memory. And when we look at the memories, it's indiscriminate. It's basically writing down all sorts of experience; it creates this huge unwieldy just disgusting memory directory of things that are not really relevant or strategic for gameplay, and it proceeds much worse in the game than Fable 5.
* **[11:45]** Fable 5's memory directory is much tighter. It's really strategic insights, tactical knowledge, things you can't just get from game state very easily. So what we see is better models have much better instincts for salience and like what to write to memory and you can see this reflected in the size of the memory directories—it's much tighter, it's much more strategic in gameplay. Indeed, Fable 5 gets much further than Sonnet 3.7.
* **[12:10]** So it gives another intuition around the fact that Claude is much better at writing to memory, knowing kind of what to write and salience and what's salient, and also kind of using and reading from memory. So models are getting more and more kind of effective at knowing salience, knowing what to write, and also reading.
* **[12:25]** Now, both of these represent what I would consider, in my initial framing, of like writing to memory during experience. So basically, in both of these tasks, we let Claude write to memory while it plays this game, we let Claude write to memory while it does the CL benchmark. But as I mentioned, there's also the dreaming side of memory. This is allowing Claude to reflect over memories, to fix things, and I'll show some interesting examples of that.

💡 **Visual-Speech Alignment:** The speaker gestures between the huge left treemap ('Claude Sonnet 3.7', 412 files / 917k chars) and the tiny right treemap ('Claude Fable 5', 33 files / 46k chars), explaining that box area reflects memory volume ('Same scale throughout: area is proportional to characters of memory').

---

## [12:50 - 13:56] Scene #21: Dreaming Memory Hierarchy
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Layered architecture diagram showing 'Session' feeding into a central 'Dreaming' container with four stacked tiers from bottom to top: 'Transcripts (Searchable event log)', 'Memory notes (Salient observations written by Claude)', 'Memory representations (Compiled from transcripts, notes (e.g., wikis))', and 'Injected context (Memory loaded into every session)', which then flows out to 'Next session'.
> * **On-Screen OCR:** Session ; Dreaming ; Injected context: Memory loaded into every session ; Memory representations: Compiled from transcripts, notes (e.g., wikis) ; Memory notes: Salient observations written by Claude ; Transcripts: Searchable event log ; Next session ; Source
> * **Structured Reconstruction:**
>   flowchart LR
>     Session[Session] --> Transcripts[Transcripts: Searchable event log]
>     Session --> Notes[Memory notes: Salient observations written by Claude]
>     subgraph Dreaming[Dreaming]
>       Transcripts --> Reps[Memory representations: Compiled from transcripts, notes e.g. wikis]
>       Notes --> Reps
>       Reps --> Injected[Injected context: Memory loaded into every session]
>     end
>     Injected --> Next[Next session]
>     Reps -.-> Next

**🎙️ Spoken Transcript:**
* **[12:50]** This is kind of a framing of dreaming. And so you can think about memory in terms of—there are transcripts. Transcripts you can think about as kind of the foundation of memory. So imagine a memory system could very simply be just transcript search. Claude writes a transcript as it goes about a task, future sessions can read from the transcript. Of course transcripts are large, it's very unwieldy. We talk a lot about in the blog post the fact that transcripts often contain a very small amount of information that is actually salient and matters.
* **[13:24]** So, we also allow Claude to do things like writing memory notes, also what I just talked about—as it goes it can write notes to memory. But dreaming lets you do more. Dreaming lets you reflect over transcripts and these written notes, and represent them, build memory representations like wikis as an example, actually promote certain memories to injected context and load it preemptively into every future session. So dreaming is this mechanism where you can kind of process existing transcripts or existing memory notes and build new things from them including representations, injected context, and more.

💡 **Visual-Speech Alignment:** The speaker walks bottom-to-top up the four tiers inside the 'Dreaming' box: 'Transcripts' -> 'Memory notes' -> 'Memory representations (e.g., wikis)' -> 'Injected context' flowing into 'Next session'.

---

## [13:56 - 14:47] Scene #22: Correcting mistakes
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Side-by-side Pokémon gameplay map comparison titled 'Correcting mistakes'. Left panel ('Raw memory: Stumbles into a wrong...') shows the red Agent sprite trapped by a ledge with a red trajectory arrow falling into 'Heads for the wrong tile'. Right panel ('Memory + dreaming: Offline pass corrected the note') shows the Agent taking the correct horizontal arrow path labeled 'Heads back to the right tile'.
> * **On-Screen OCR:** Correcting mistakes ; Raw memory: Stumbles into a wrong... ; Agent ; Heads for the wrong tile ; Memory + dreaming: Offline pass corrected the note ; Heads back to the right tile ; Source

**🎙️ Spoken Transcript:**
* **[13:56]** So some fun examples of this: this is from Pokémon gameplay. Dreaming is an effective way to correct mistakes in memory, so as I talked about, when Claude's going about a task, it can write incorrect notes to memory. Just, it makes a mistake. This happened in this particular game: Claude incorrectly wrote the location of a particular landmark in the game. Now what happened is, with this incorrectly written memory, Claude got trapped in a loop, where basically it would mislocalize itself at this particular point in the game, fall down this trap door, and it would basically send it back to the prior level.
* **[14:32]** That's like the high level intuition, the details aren't that interesting or important. The key idea is a poison memory was injected and it's stuck there. Dreaming can rescue that; that's really the intuition on why dreaming is extremely powerful for reflecting over memories and correcting them.

💡 **Visual-Speech Alignment:** The speaker points to the left map ('Raw memory') showing the loop leading into the wrong tile/ledge, and contrasts it with the right map ('Memory + dreaming') where the corrected note routes the agent to the right tile.

---

## [14:47 - 15:26] Scene #23: Progress toward Cerulean (estimated tiles traversed)
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Trajectory line plot tracking estimated tiles traversed from 'Frontier' through 'Below the bridge', 'Ledge-area exit', 'Casting cave', 'Climbing back up', and 'Cleared cave! Exit to Bike' up to 'Cerulean' across 0 to 3000+ cumulative actions. Three curves are plotted: 'Memory + dreaming' (orange/blue), 'Raw memory' (red), and 'No memory' (grey). Annotations highlight 'Reached Cerulean (action 1930)' and 'Dreaming finds the error and rescues the run' vs 'Raw memory falls off the bridge, then backtracks to Frontier'.
> * **On-Screen OCR:** Progress toward Cerulean (estimated tiles traversed) ; Memory + dreaming ; Raw memory ; No memory ; Cerulean ; Cleared cave! Exit to Bike ; Climbing back up ; Ledge-area exit (cave entrance) ; Cave entrance (before bridge) ; Below the bridge ; Frontier ; Reached Cerulean (action 1930) ; Dreaming finds the error and rescues the run in the cave ; Raw memory falls off the bridge, then backtracks to Frontier ; Cumulative actions ; Source
> * **Structured Reconstruction:**
>   | Condition | Trajectory Outcome | Key Milestone / Annotation |
>   |---|---|---|
>   | Memory + dreaming | Succeeds | Dreaming finds the error and rescues the run in the cave; Reached Cerulean (action 1930) |
>   | Raw memory | Crashes / Regresses | Falls off the bridge due to poison memory, then backtracks to Frontier |
>   | No memory | Baseline | Progresses slowly without memory rescue |

**🎙️ Spoken Transcript:**
* **[14:47]** So this is showing some trajectory of the game, where orange is memory and dreaming. Up is good, so basically up represents game progress, and down represents kind of game regression. And what's interesting is raw memory, basically without dreaming, we can see crashes out—an incorrect memory is planted and Claude continues to basically regress or fall in the game when it hits that particular point. With dreaming, it rescues that mistake, Claude proceeds to the next level. That's really the key observation and this is a very general principle: that Claude can use dreaming to correct mistakes in memory that are otherwise stuck there. It's a very important way you can kind of correct from errors.

💡 **Visual-Speech Alignment:** The speaker gestures upward along the y-axis ('up represents game progress') toward 'Reached Cerulean (action 1930)' and downward into the pink 'Below the bridge' shaded region where the red 'Raw memory' curve collapses back to 'Frontier'.

---

## [15:26 - 17:19] Scene #24: Building representations
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Three-panel figure titled 'Building representations'. Left panel ('After 2 sessions: Like a new employee's first days') shows a sparse graph of '103 pages, 764 links'. Center panel ('Graded criteria met / Wiki built by Opus 5') plots accuracy against 'Dreaming tokens (wiki generation)' on a log scale from 1M to 12M, comparing 'Search tool, no wiki: 53%', 'Wiki alone' (rising from 16% to 48%), and 'Wiki + search tool' (rising from 54% to 61%). Right panel ('After 128 sessions: Like a seasoned employee's knowledge') shows a dense interconnected graph of '323 pages, 12,893 links'.
> * **On-Screen OCR:** Building representations ; After 2 sessions: Like a new employee's first days ; 103 pages, 764 links (Example wiki) ; Page at 2 sessions ; Graded criteria met: Wiki built by Opus 5 ; Wiki + search tool: 54% -> 61% ; Search tool, no wiki: 53% ; Wiki alone: 16% -> 48% ; Dreaming tokens (wiki generation): 1M, 2M, 6M, 10M, 12M ; Log scale. Budget of 5M tokens per session, not measured spend. ; After 128 sessions: Like a seasoned employee's knowledge ; 323 pages, 12,893 links (Example wiki) ; Page at 2 sessions / Added later ; Source
> * **Structured Reconstruction:**
>   | Method | ~1M Dreaming Tokens | ~12M Dreaming Tokens | Notes |
>   |---|---:|---:|---|
>   | Search tool, no wiki (baseline) | 53% | 53% | Horizontal dashed baseline |
>   | Wiki alone | 16% | 48% | Scales monotonically with dreaming compute |
>   | Wiki + search tool | 54% | 61% | Outperforms raw search tool alone |
>   
>   | Wiki Growth Stage | Pages | Links |
>   |---|---:|---:|
>   | After 2 sessions | 103 | 764 |
>   | After 128 sessions | 323 | 12,893 |

**🎙️ Spoken Transcript:**
* **[15:26]** Now, this is another fun example of building representations in memory. So, there's been a lot of interest in wikis as kind of general ways that Claude can organize knowledge. This is a really fun example from—we acquired a company, Stainless, back in May. And we had access to the company corpus, all its documents and Slack messages and so forth, and we anonymized things and we built kind of a dataset from it which allowed us to test dreaming.
* **[15:58]** So what we did was we created kind of an eval setup: 25 questions about the company that can only be answered from this corpus. We allow Claude to build a wiki from this information to help it answer questions. What you see is we compare a raw search tool, that's just like some kind of semantic search over this documentation. We compare that as a baseline, which does reasonably well—you can see it's like 53% just for search.
* **[16:22]** We also test letting Claude build a wiki over this knowledge. You can see as you add more and more dreaming tokens, the wiki gets better and better and better, allowing Claude to answer questions. So Claude natively can kind of build up over time a representation of this corpus of knowledge through a wiki. And as you add more dreaming compute, that wiki gets more and more useful. We think this is a really nice mental model to think about how agents can kind of build knowledge over time.
* **[17:01]** We also find that adding the wiki and the search tool together actually bumps further beyond just raw search. So this is kind of another intuition that basically Claude can also build representations like wikis in its kind of memory, in order to help it kind of solve problems.

💡 **Visual-Speech Alignment:** The speaker points to the center line chart: '53% just for search' maps to the horizontal dashed line ('Search tool, no wiki: 53%'), 'add more and more dreaming tokens' traces the rising 'Wiki alone' curve (16% to 48%), and 'adding the wiki and the search tool together' maps to the top 'Wiki + search tool' curve (54% to 61%).

---

## [17:19 - 18:16] Scene #25: Filling in gaps
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Side-by-side knowledge graph comparison showing a wiki graph 'Before the second pass: 38 entries, 225 links' on the left (containing missing/dangling placeholder nodes) versus 'After the second pass: 41 entries, 278 links' on the right (with newly added terracotta-highlighted nodes, index, and 53 additional links written by the second dreaming pass).
> * **On-Screen OCR:** Filling in gaps ; Before the second pass: 38 entries, 225 links ; Pages: placeholder links to missing pages, gaps in the index ; After the second pass: 41 entries, 278 links ; Legend: Entity nodes, New inventories, Metrics, Relations, Open questions, Written by the second pass ; Source
> * **Structured Reconstruction:**
>   flowchart LR
>     subgraph Before[Before the second pass: 38 entries, 225 links]
>       B1[Existing Entity Nodes] -.->|placeholder links| Missing[Missing Pages & Index Gaps]
>     end
>     subgraph After[After the second pass: 41 entries, 278 links]
>       A1[Existing Entity Nodes] -->|278 links| A2[Filled Pages & New Index]
>       A2 -->|Written by second pass| A3[+3 Entries, +53 Links]
>     end
>     Before -->|Dreaming 2nd pass| After

**🎙️ Spoken Transcript:**
* **[17:19]** And a final example, this is from a different benchmark, but this is showing two different wikis that Claude built. So this is prior to dreaming and after dreaming. What we saw is when Claude was building wikis in this particular case, there were some gaps. And for example, this initial wiki had a bunch of placeholders for pages that didn't exist. This can happen when Claude is kind of building different memory representations, and without dreaming compute, there may not be opportunities to rescue or fix those errors.
* **[17:48]** What we saw is when we ran dreaming, dreaming can look over Claude's existing representation like for example a wiki and can fill in mistakes. So in this case, it fills in a lot of missing gaps, it creates an index. And so again, dreaming is a way that Claude can reflect and kind of apply compute across its memory to improve it by correcting mistakes like I talked about, by filling in gaps in its knowledge like we see here, or for example by creating new representations like wikis.

💡 **Visual-Speech Alignment:** The speaker gestures from the left graph ('prior to dreaming' -> 'Before the second pass: 38 entries, 225 links') to the right graph ('after dreaming' -> 'After the second pass: 41 entries, 278 links'), highlighting the newly added red/terracotta nodes and links.

---

## [18:16 - 18:27] Scene #26: Thank you! @rlancemartin
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Closing slide with centered text 'Thank you! @rlancemartin' as the camera cuts to a stage angle showing Lance Martin packing up at the podium.
> * **On-Screen OCR:** Thank you! ; @rlancemartin

**🎙️ Spoken Transcript:**
* **[18:16]** Um, so with that, I thank you all for listening and I'll be at the Anthropic booth, so please come see me and happy to talk about any of this.

💡 **Visual-Speech Alignment:** The speaker concludes his presentation and invites attendees to the Anthropic booth while the 'Thank you! @rlancemartin' slide is displayed.

---

## [18:27 - 18:42] Scene #27: AI Engineer Code Summit - Outro Bumper
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Closing conference bumper on a black background featuring the 'AI Engineer Code Summit' logo and 'HTTPS://AI.ENGINEER' below.
> * **On-Screen OCR:** AI Engineer Code Summit ; HTTPS://AI.ENGINEER

**🎙️ Spoken Transcript:**

💡 **Visual-Speech Alignment:** No speech occurs during the closing conference bumper.

---
