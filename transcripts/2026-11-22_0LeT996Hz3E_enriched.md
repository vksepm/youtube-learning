# Enriched Interleaved Transcript: Engineer Your Coding Agents Like Any Other System — Zach Lloyd, Warp
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=0LeT996Hz3E
**Model:** `gemini-3.6-flash` | **Processing Mode:** `agentic`

---

## [00:00 - 00:25] Scene #1: AI Engineer Code Summit
> **[SCREEN INTERPRETATION | Type: `SPEAKER_ONLY`]**
> * **Visual Summary:** Event introduction screens for AI Engineer Code Summit presented by Google DeepMind, followed by speaker Zach Lloyd standing on stage.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; PLATINUM SPONSORS: aws, Devin, databricks, exa, FACTORY, Sonar

**🎙️ Spoken Transcript:**
* **[00:13]** All right. Hi everyone. I'm excited to be here and today I'm going to chat about the evolution of software factoring. Software engineering and how it's becoming factory engineering, so excited to do this.

💡 **Visual-Speech Alignment:** Speaker introduces himself and the central topic of the presentation on the main stage.

---

## [00:25 - 01:07] Scene #2: Zach Lloyd
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Introductory slide introducing Zach Lloyd with bullet points detailing his experience at Google Docs, 20 years in engineering, and founding Warp.
> * **On-Screen OCR:** Zach Lloyd ; Principal engineer at Google, lead on GDocs ; 20 years of engineering ; Founder of Warp ; Software Engineering Is Becoming Factory Engineering ; Zach Lloyd | Founder & CEO | warp

**🎙️ Spoken Transcript:**
* **[00:25]** First, a little bit about me. I've been an engineer for a long time. I was a principal engineer at Google. I used to lead engineering on the Google Docs suite, helped scale that product to hundreds of millions of users.
* **[00:38]** I'm currently the founder and CEO of Warp. Warp builds a platform for companies to build their own internal software factories. I'm going to show a little bit of that today.
* **[00:50]** Warp is also well known for our open source Agentic terminal, has about 65,000 GitHub stars. It's used by almost a million developers. Our mission has always been helping developers ship better software more quickly and it's cool to evolve what we're doing as the world changes around us.

💡 **Visual-Speech Alignment:** Spoken background directly matches the bullet points listed under Zach Lloyd's name.

---

## [01:07 - 01:43] Scene #3: Interactive prompting
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide showing a photograph of a multi-monitor developer desk setup representing local multi-threaded interactive prompting.
> * **On-Screen OCR:** Interactive prompting ; Software Engineering Is Becoming Factory Engineering

**🎙️ Spoken Transcript:**
* **[01:07]** This is where I think we're still mostly at. Most developers that I talk to, most platform teams, they're working with individuals who are running their own coding agents locally. Maybe they're running multiple of them at a time. It could be through their terminal, it could be through an agentic development environment.
* **[01:30]** Just show of hands quickly, actually, how many people in here are mostly working in this fashion, local multi threading? Okay, so still most people but actually not everyone.

💡 **Visual-Speech Alignment:** The desk photo visually illustrates the 'local multi threading' and interactive prompting approach discussed.

---

## [01:43 - 03:03] Scene #4: Software factories are coming.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide listing three key arguments for why the industry is shifting towards cloud software factories.
> * **On-Screen OCR:** Software factories are coming. ; 1 Automation increases throughput ; 2 Centralization for measuring and improving quality and cost ; 3 Security and governance in the cloud

**🎙️ Spoken Transcript:**
* **[01:43]** I think that this is going to change and it's starting to change already. The reasons are there's a few of them.
* **[01:54]** So one is like, if you are doing local interactive prompting as your main way of working with coding agents, you're kind of limited by human throughput really. Like you cannot automate if every agent needs to be interactively prompted.
* **[02:10]** There's a second reason too that I hear a lot from platform teams, and from engineering leaders. This mechanism of like everyone choosing their own local setup, their own models, their own skills. It makes it very hard to actually make sure that you're using these agents efficiently from like a cost perspective and a productivity perspective.
* **[02:31]** And then finally, there's like a big security problem and governance problem when everyone is setting up and running their own local agents.

💡 **Visual-Speech Alignment:** Points 1, 2, and 3 on screen correspond directly to the speaker's discussion of human throughput limits, cost centralization, and cloud governance.

---

## [03:03 - 03:37] Scene #5: What a software factory is not:
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide featuring four boxes marked with red crosses indicating common misconceptions about software factories.
> * **On-Screen OCR:** What a software factory is not: ; A loose set of automations ; A collection of AI teammates ; A shared skills and mcp setup ; A personal agent swarm

**🎙️ Spoken Transcript:**
* **[03:03]** I'm going to define what I think of as a software factory, but I'll start by saying what I think a software factory is not.
* **[03:14]** I think it's not just a loose set of automations. I don't think of a software factory as a collection of AI teammates. I don't think it's a shared set of skills and MCPs, and I also don't think software factories are personal agent swarms. I think these are all useful primitives, but they're not the end state that we should be shooting for.

💡 **Visual-Speech Alignment:** The four crossed-out cards on screen align item-by-item with the speaker's enumeration.

---

## [03:37 - 03:55] Scene #6: What is a software factory?
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide displaying Zach's formal definition of a software factory highlighted in yellow background text.
> * **On-Screen OCR:** What is a software factory? ; A code-defined, closed-loop system for continuously measuring and improving cloud coding agents.

**🎙️ Spoken Transcript:**
* **[03:37]** And so, to me, the way that I define software factory is very specific. I define it as a code-defined closed loop system for continuously measuring and improving cloud coding agents.

💡 **Visual-Speech Alignment:** Speaker reads the verbatim highlighted definition shown on the slide.

---

## [03:55 - 04:35] Scene #7: Factories as code:
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Slide explaining 'Factories as code' on the left alongside a YAML code configuration snippet defining a factory on the right.
> * **On-Screen OCR:** Factories as code: ; The way a factory engineer defines and improves a factory. ; factory: eng-factory-slim ; automations: ; auto-server-version ; description: Automated software development factory for warp-server
> * **Structured Reconstruction:**
>   factory: eng-factory-slim
>   description: Automated software development factory for warp-server
>   
>   automations:
>     - auto-server-version:
>         name: server-version
>         description: Automated software development factory for warp-server
>         repo: warp-server
>         models:
>           - gpt-4o
>         skills:
>           - web-search

**🎙️ Spoken Transcript:**
* **[03:55]** I believe the first thing you need to do is fully encode it in a declarative language. So you need to say, okay, these are all of the coding agents that I want to run, these are how they're triggered. When work comes into this factory, this is the workflow from triage to spec, whatever your workflow is.
* **[04:24]** You need to specify what MCPs are available, where your agents run. Really, as much as you can in a Terraform style declarative set of code files that define your factory.

💡 **Visual-Speech Alignment:** Speaker points out specifying agents, triggers, and MCPs in a Terraform-like declarative code format while showing YAML snippet.

---

## [04:35 - 05:15] Scene #8: A cloud software factory
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Circular workflow diagram representing the continuous SDLC loop around 'A cloud software factory', incorporating human review gates.
> * **On-Screen OCR:** New product idea or bug reported ; Triage ; Spec ; Reviewing the spec ; Implement ; Reviewing the code ; Verify ; Ship ; Reviewing the product ; Monitor ; A cloud software factory
> * **Structured Reconstruction:**
>   flowchart TD
>       Idea[New product idea or bug reported] --> Triage
>       Triage --> Spec
>       Spec -->|Reviewing the spec| Implement
>       Implement -->|Reviewing the code| Verify
>       Verify --> Ship
>       Ship -->|Reviewing the product| Monitor
>       Monitor --> Idea

**🎙️ Spoken Transcript:**
* **[04:35]** The second part of it is a continuous closed loop of improvement. And that closed loop can look something like this. This is the typical one. This is just really the SDLC, where you have ideas that come in from people... and then your agents do some amount of work.
* **[05:05]** The important piece here is really this closed loop concept, where the more that your agents run, the more efficient you can make this loop.

💡 **Visual-Speech Alignment:** The speaker references the continuous circular flow of triage, spec, implementation, verification, and monitoring depicted in the diagram.

---

## [05:15 - 05:42] Scene #9: Measurement > Vibes
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Scatter plot chart mapping model correctness against average cost, highlighting 'gpt-5.6-sol (high)' as the Benchmark Winner.
> * **On-Screen OCR:** Measurement > Vibes ; Benchmark Results ; gpt-5.6-sol (high): Average cost $8.13, Correctness 96%, Benchmark Winner ; gpt-5.6-sol (med) ; gpt-5.3-flash ; gemini 3.7 flash ; grok 4.0 (high) ; claude opus 5 (high)
> * **Structured Reconstruction:**
>   | Model | Average Cost | Correctness | Status |
>   | --- | --- | --- | --- |
>   | gpt-5.6-sol (high) | $8.13 | 96% | Benchmark Winner |
>   | gpt-5.6-sol (med) | Medium | ~90% | Evaluated |
>   | grok 4.0 (high) | High | ~85% | Evaluated |
>   | claude opus 5 (high) | ~$13.00 | ~78% | Evaluated |
>   | gpt-5.3-flash | Low | ~75% | Evaluated |
>   | gemini 3.7 flash | Low | ~68% | Evaluated |

**🎙️ Spoken Transcript:**
* **[05:15]** The third really key aspect, if you're building a software factory, is that everything needs to be measurable. If you're just going on vibes in terms of how you deploy coding agents, you can't be confident that you're actually getting the best, highest quality outputs, at the best cost.

💡 **Visual-Speech Alignment:** The 'Measurement > Vibes' header and chart contrast empirical benchmark metrics against subjective feelings.

---

## [05:42 - 06:35] Scene #10: Prompt your agents. Manage your agents. Engineer your agents.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Blue slide presenting three evolution stages of working with agents, emphasizing 'Engineer your agents.' in bold white.
> * **On-Screen OCR:** Prompt your agents. ; Manage your agents. ; Engineer your agents.

**🎙️ Spoken Transcript:**
* **[05:42]** And so, if there's one thing that I'm hoping people walk away from this talk with, it's the idea that the way to work with coding agents and the way to think about them is that there's a really cool fundamental new engineering problem, which is How do you take this magic new primitive that we all have... and how do you engineer a system around them to use them most effectively?
* **[06:15]** When you think of coding agents as a new engineering primitive, then you naturally start to build a certain way of using them. That's the mindset.

💡 **Visual-Speech Alignment:** The speaker emphasizes 'Engineer your agents' as the key thesis takeaway.

---

## [06:35 - 06:41] Scene #11: The factory engineering mindset:
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide detailing two foundational principles of the factory engineering mindset.
> * **On-Screen OCR:** The factory engineering mindset: ; 1 Measure everything yourself based on your own data ; 2 Continually improve

**🎙️ Spoken Transcript:**
* **[06:35]** That's the mindset. So yeah, just to unpack that a bit, so there's continual measurement and continual learning.

💡 **Visual-Speech Alignment:** Bullet points 1 and 2 summarize measurement and continuous improvement.

---

## [06:41 - 07:27] Scene #12: The factory engineer toolbelt:
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide listing core tool categories available to factory engineers.
> * **On-Screen OCR:** The factory engineer toolbelt: ; Blueprints ; Automations ; Evals ; Self-improvement ; Benchmarks ; A/B tests

**🎙️ Spoken Transcript:**
* **[06:41]** But there's also a new set of tools... In the new world of factory engineering, there's a new set of tools that everyone should be trying to master. And so those are things like, evals, it's can you set up self-improvement loops that work. Can you write benchmarks? Can you A/B test your factory?

💡 **Visual-Speech Alignment:** Speaker explicitly lists the tools shown horizontally across the slide (Evals, self-improvement, benchmarks, A/B tests).

---

## [07:27 - 08:06] Scene #13: Product engineering and factory engineering.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide contrasting Product engineering ('Building the product') with Factory engineering ('Improving the factory that builds the product').
> * **On-Screen OCR:** Product engineering and factory engineering. ; Product engineering = Building the product ; Factory engineering = Improving the factory that builds the product

**🎙️ Spoken Transcript:**
* **[07:27]** Now, that doesn't mean that that's the only kind of engineering you're going to be doing. You're still going to be doing product engineering, meaning, you as an engineer should still feel responsible for does the product you ship actually solve a real user problem.
* **[07:55]** But the best engineers... is going to need to learn this new tool set of how do you improve the system, not just build the product.

💡 **Visual-Speech Alignment:** Distinction between building the product vs. improving the system/factory aligns directly with the definitions on screen.

---

## [08:06 - 10:38] Scene #14: THE FACTORIES STACK
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Detailed 7-layer architecture pyramid diagram covering layer 00 (Factories-as-code) up to layer 06 (Access).
> * **On-Screen OCR:** THE FACTORIES STACK ; 06 ACCESS: IDE / CLI, Warp Terminal, Warp Mobile, Web, Slack / Linear / Jira / GH, Open API ; 05 ORCHESTRATION: Workflow DAG, Triggers, Human-in-the-loop, Multi-agent, Task Broker ; 04 IMPROVEMENT: Online Evals, Scorer Dashboard, Benchmarking, Self-Improvement ; 03 INFERENCE: Multi-model (OpenAI, Anthropic, Gemini, DeepSeek), Bring Your Own Model, Custom Router ; 02 COMPUTE: Sandboxing (Docker, MicroVM, K8s, E2B), Agent Runner, Compute Size ; 01 DATA & CONTEXT: Runs + Transcripts, Agent Artifacts, MCPs / Internal Knowledge, Access Control ; 00 FACTORIES-AS-CODE: Declarative Config, Agent Definitions, Automation Definitions, Launch Config, Repo Config
> * **Structured Reconstruction:**
>   flowchart TD
>       L6["06 ACCESS: IDE/CLI, Warp Terminal, Slack/Linear/Jira, Open API"]
>       L5["05 ORCHESTRATION: Workflow DAG, Triggers, Human-in-the-loop, Multi-agent"]
>       L4["04 IMPROVEMENT: Online Evals, Scorer Dashboard, Benchmarking, Self-Improvement"]
>       L3["03 INFERENCE: Multi-model, Bring Your Own Model, Custom Router"]
>       L2["02 COMPUTE: Sandboxing, Agent Runner, Compute Size"]
>       L1["01 DATA & CONTEXT: Runs + Transcripts, Agent Artifacts, MCPs, Access Control"]
>       L0["00 FACTORIES-AS-CODE: Declarative Config, Agent Definitions, Automation Definitions"]
>       L6 --> L5 --> L4 --> L3 --> L2 --> L1 --> L0

**🎙️ Spoken Transcript:**
* **[08:06]** And so what does that look like? If you think from first principles about how do you engineer an agentic system. I think you come up with something like this, doesn't have to be exactly this, but it's kind of an infrastructure stack that you're going to want to use...
* **[08:25]** At the bottom of this is what I call factories as code... Above that is a layer of data and context... On top of that is the compute layer... Above that is the inference layer... On top of that, you need an orchestration layer... And then finally, your factory should be all API and MCP first...

💡 **Visual-Speech Alignment:** Speaker walks through each layer of the pyramid from bottom (00 Factories-as-code) to top (06 Access).

---

## [10:38 - 11:34] Scene #15: factory.yml — eng-factory-slim
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Live repository code viewer on GitHub displaying `factory.yml` configuration defining agents, triggers, and lifecycle operations.
> * **On-Screen OCR:** Let's take a look at the tools -> ; GitHub - warp-agent-staging / eng-factory-slim / factory.yml ; factory: eng-factory-slim ; description: Automated software development operations with a facilitator foreman and autonomous lifecycle workers. ; owners: - zacklloyd@warp.dev ; triggers: - github-prs ; agents: warp-server, warp-docs, warp-web, warp-ios, warp-android
> * **Structured Reconstruction:**
>   factory: eng-factory-slim
>   description: Automated software development operations with a facilitator foreman and autonomous lifecycle workers.
>   
>   owners:
>     - zacklloyd@warp.dev
>   
>   triggers:
>     - github-prs
>   
>   agents:
>     - name: warp-server
>     - name: warp-docs
>     - name: warp-web
>     - name: warp-ios
>     - name: warp-android

**🎙️ Spoken Transcript:**
* **[10:38]** I'm going to give a quick demo of what some of these tools look like in the context of warp factories.
* **[10:55]** So, let me start here, so at the foundation, I mentioned earlier, this factory is in code. And so, I'm going to show some code... You basically want a declarative way of saying, this is my factory.

💡 **Visual-Speech Alignment:** Demonstrates the code implementation of the bottom stack layer (Factories-as-code).

---

## [11:34 - 12:33] Scene #16: Runs — eng-factory-slim
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Warp platform UI showing live team agent runs, real-time activity feeds, task duration, models used, and generated artifacts.
> * **On-Screen OCR:** platform.staging.warp.dev ; Runs ; Inventory GitHub Repository Capabilities — Maggie Web — 5m ago ; Implement Opus 5.5 High Plan — Maggie Web — 11m ago ; Artifacts: GitHub migration push step, GitHub name step, GitHub push step, GitHub success screen ; Metadata: Model gpt-4-0125-preview, Autopilot slack-mention
> * **Structured Reconstruction:**
>   Run: Implement Opus 5.5 High Plan
>   Assignee: Maggie Web
>   Status: Delivered (Completed in 14m 25s)
>   Model: gpt-4-0125-preview
>   Autopilot: slack-mention
>   Artifacts:
>     - GitHub migration push step
>     - GitHub name step (step 2 of 3) with purple banner
>     - GitHub push step
>     - GitHub success screen

**🎙️ Spoken Transcript:**
* **[11:34]** The second thing, moving up a layer is the idea that everything that you do in the factory should be tracked across your entire team.
* **[11:55]** This is a sort of Google Docs style live view of what every coding agent on Warp's team across all of our engineers are doing at all times.
* **[12:08]** And so I could click in and I could see, Maggie is implementing Opus 55 on the high plan. She's doing it from Slack. It has this artifact, I could look in and see the actual conversation here.

💡 **Visual-Speech Alignment:** Speaker points to Maggie's run item on screen and inspects metadata and generated artifacts.

---

## [12:33 - 13:24] Scene #17: Dashboard — Productivity & Spending
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Analytics dashboard displaying productivity metrics (human interactions, cycle time, PR counts) and spending analytics.
> * **On-Screen OCR:** eng-factory-slim — Dashboard ; Productivity | Spending | Scorers ; Human interactions per PR: 19.4 ; Median cycle time: Kickoff -> Merge 5.7h, Kickoff -> PR 20m ; Pull requests: 342 (341 merged) ; Total runs: 1,188 ; Cost per PR: $10.68 ; Most expensive PRs: $4,697.41 total spend
> * **Structured Reconstruction:**
>   | Metric | Value |
>   | --- | --- |
>   | Human interactions per PR | 19.4 |
>   | Median Kickoff -> Merge | 5.7h |
>   | Median Kickoff -> PR | 20m |
>   | Total Pull Requests | 342 |
>   | Total Runs | 1,188 |
>   | Average Cost per PR | $10.68 |

**🎙️ Spoken Transcript:**
* **[12:33]** That brings me to the third thing moving up the stack here is once you have all of this information... You get the ability very easily... to understand how these coding agents are working.
* **[12:55]** You can think of that in terms of like traditional output metrics, like your Dora metrics... cycle time... how many human interactions per PR... cost...

💡 **Visual-Speech Alignment:** Speaker points out exact numbers on dashboard: 19.4 human interactions per PR, cycle times, and cost per PR.

---

## [13:24 - 14:58] Scene #18: Scorers — Redundant Tests & Online Evals
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Scorer evaluation overview detailing automated test quality metrics, zooming into 'Redundant Tests' pass rates and execution history.
> * **On-Screen OCR:** Dashboard -> Scorers ; Stage Transition Compliance: 71% pass ; Self-improvement Quality: 69% pass ; Redundant Tests: 82% pass, All-time answer cost: $43.54 ; Scorer prompt: Whether the worker's final delivered test diff included redundant, low-signal, or trivial tests ; Recent runs: Pass/Fail scores (1.0 vs 0.4 - 'Some surplus tests')
> * **Structured Reconstruction:**
>   | Scorer Name | Pass Rate | Score Metric |
>   | --- | --- | --- |
>   | Stage Transition Compliance | 71% | 69 passed, 28 failed |
>   | Self-improvement Quality | 69% | 29 passed, 13 failed |
>   | Redundant Tests | 82% | Score history ~0.8 |
>   | Human Feedback | 70% | 284 passed, 122 failed |

**🎙️ Spoken Transcript:**
* **[13:24]** And then, there's this next layer of data, which is also really important that I mentioned earlier, which is the ability to set up online Evals that run across all your coding agent sessions.
* **[13:55]** So, it's like we have an eval score here that we use that is looking for redundant tests... one common failure mode of coding agents is that sometimes they will write tests that are unnecessary.

💡 **Visual-Speech Alignment:** Speaker navigates into the Redundant Tests scorer tab to demonstrate online evaluation capabilities.

---

## [14:58 - 15:54] Scene #19: Self-improvement Inbox & GitHub PR #1328
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Self-improvement inbox view listing automated bug fix proposals, opening GitHub PR #1328 showing diff additions to `SKILL.md`.
> * **On-Screen OCR:** Self-improvement ; Approval 1 / 43 (2%) ; Inbox item: Check GitHub capabilities before declaring publication blocked ; GitHub PR #1328: Check GitHub capabilities before declaring publication blocked ; Diff file: eng-factory/skills/github/SKILL.md (+18 lines) ; Before reporting on access tracker: Check GitHub capabilities before declaring publication blocked
> * **Structured Reconstruction:**
>   PR #1328: Check GitHub capabilities before declaring publication blocked
>   Branch: self-improvement-auto-fix
>   File changed: eng-factory/skills/github/SKILL.md
>   
>   + ### Before reporting on access tracker
>   + All transports, open-PR visibility, PR creation, and PR metadata write access have different permissions. An empty response from a GitHub API check does not imply total lack of access...

**🎙️ Spoken Transcript:**
* **[14:58]** Once you have that in place, You can do something that we call self-improvement which is rather than having humans look at the outputs of these scorers you have agents look at the output.
* **[15:30]** So this is like the awesome thing about having your factory defined as code and being able to use coding agents is that you can then have the coding agents diagnose problems with how they're working internally and suggest fixes to them.

💡 **Visual-Speech Alignment:** Shows an agent-generated GitHub PR (#1328) proposing a skill configuration patch based on automated scorer feedback.

---

## [15:54 - 17:15] Scene #20: Benchmarks — WarpBench 0.1
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Benchmark evaluation suite 'WarpBench 0.1' showing test runs and scatter plot graph of Correctness vs Average Cost on real tasks.
> * **On-Screen OCR:** Benchmarks -> WarpBench 0.1 ; Synthesized, self-contained implementation agent tasks distilled from real Warp factory runs. ; Scatter plot: Correctness vs Average cost ; gpt-5.6-sol (med): Correctness ~93.8%, Avg cost $4.23 ; gpt-5.3-flash: Correctness ~86.2% ; gemini 3.7 flash: Correctness ~77.1% ; claude opus 5 (high): Correctness ~84.5%, Avg cost ~$15.20
> * **Structured Reconstruction:**
>   | Model | Correctness | Average Cost |
>   | --- | --- | --- |
>   | gpt-5.6-sol (med) | 93.8% | $4.23 |
>   | gpt-5.3-flash | 86.2% | $1.85 |
>   | gemini 3.7 flash | 77.1% | $1.10 |
>   | claude opus 5 (high) | 84.5% | $15.20 |

**🎙️ Spoken Transcript:**
* **[15:54]** The final tool that I'm going to point out that I mentioned earlier is the ability to create and run benchmarks. This is also essential...
* **[16:05]** The only way to answer those questions for real is to test on your own data. And so you should have in place some mechanism where you can basically create a benchmark set out of your real data...
* **[16:45]** This is something that looks like what you might get when a new model drops, like in Sweetbench or Terminal Bench. It's showing the trade-offs of different models here in terms of cost and quality...

💡 **Visual-Speech Alignment:** Speaker demonstrates running WarpBench 0.1 on actual production tasks to compare model cost vs. correctness.

---

## [17:15 - 17:36] Scene #21: Factory proof points:
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide showing empirical results achieved by Warp: 40% more PRs merged, 70% lower PR review rate, and 67% lower cost per merged PR.
> * **On-Screen OCR:** Factory proof points: ; 40% MORE PRS MERGED (Merged PR volume increased from 1,692 to 2,362 across the seven weeks before and after comparison) ; 70% LOWER OBSERVED PR REVIEW RATE (Declined from 0.80% to 0.24% across matched four-week periods) ; 67% LOWER FACTORY COST PER MERGED PR (Average cost per merged PR fell from approximately $55 to $18 between September and October 2025) ; How we improved our own factory:
> * **Structured Reconstruction:**
>   | Metric | Result | Context |
>   | --- | --- | --- |
>   | Merged PRs | +40% | Increased from 1,692 to 2,362 |
>   | PR Review Rate | -70% | Declined from 0.80% to 0.24% |
>   | Factory Cost / PR | -67% | Fell from ~$55 to ~$18 |

**🎙️ Spoken Transcript:**
* **[17:15]** And just to return to this big concept like this has worked well for us. We've managed to use these tools to drastically improve our throughput and lower our cost. We are just constantly doing this because this cost really matters to us...

💡 **Visual-Speech Alignment:** Spoken points highlight the 40% throughput increase and cost reduction metrics visible on the slide.

---

## [17:36 - 18:30] Scene #22: Engineer your agents.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Concluding slides reinforcing the core message 'Engineer your agents.', followed by closing thoughts and a final QR code slide.
> * **On-Screen OCR:** Engineer your agents. ; How I feel about being an engineer today. ; TRY WARP FACTORIES TODAY

**🎙️ Spoken Transcript:**
* **[17:36]** Engineer your agents. It's a new engineering primitive we're all engineers. Think about how you can get the most out of them and build the system for that.
* **[17:51]** I think this is very exciting. I know there's a lot of angst around what it means to be an engineer right now... but I'm still using all the engineering skills that I spent my whole career learning...
* **[18:08]** If you're interested in more factories, you can check it out here. Thank you all for coming to the talk.

💡 **Visual-Speech Alignment:** Speaker delivers concluding remarks while showing final call-to-action slides and QR code.

---
