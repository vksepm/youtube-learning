# Enriched Interleaved Transcript: Build the Workshop Before the Software Factory — Armin Ronacher, Earendil
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=JNexz3Tbiu8
**Model:** `gemini-3.6-flash` | **Processing Mode:** `agentic`

---

## [00:00 - 00:23] Scene #1: The Software Atelier
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Title slide of the talk titled 'The Software Atelier: A year of harnesses, models and machines' presented by Armin Ronacher from Earendel at the AI Engineer Code Summit.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; THE SOFTWARE ATELIER ; The Software Atelier ; A year of harnesses, models and machines ; ARMIN RONACHER | EARENDEL ; EARENDEL, INC. 01 / 16 ; Armin Ronacher / CTO / Earendel
> * **Structured Reconstruction:**
>   # The Software Atelier
>   ## A year of harnesses, models and machines
>   **Author:** Armin Ronacher | Earendel  
>   **Slide:** 01 / 16

**🎙️ Spoken Transcript:**
* **[00:13]** My name is Armin, and I want to share with you a little bit the lessons that we have learned from building software with agents...
* **[00:20]** ...and in particular I want to make a strong case for not so much building the factory as building the atelier or workshop.

💡 **Visual-Speech Alignment:** Armin introduces the title of his talk 'The Software Atelier' and introduces the thesis of focusing on the workshop over the factory.

---

## [00:24 - 01:20] Scene #2: Before the factory, the atelier
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide introducing Section I (The Thesis), contrasting the concept of software factories with the software atelier/workshop and advocating for excellent, high-ambition software.
> * **On-Screen OCR:** THE THESIS ; Before the factory, the atelier ; 01 Everyone is trying to build software factories ; 02 Most of us, me included, have not learned to use these tools well in the workshop ; 03 I care about excellent software that aims higher, not mass-produced slop ; EARENDEL, INC. 02 / 16
> * **Structured Reconstruction:**
>   ### I. THE THESIS
>   ## Before the factory, the atelier
>   
>   1. Everyone is trying to build *software factories*
>   2. Most of us, me included, have not learned to use these tools well in the *workshop*
>   3. I care about *excellent software* that aims higher, not mass-produced slop

**🎙️ Spoken Transcript:**
* **[00:30]** And I want to show some data with this from our own usage, but in particular I want to explain what I mean by building the atelier or the workshop prior to building the software factory.
* **[00:41]** And I think everybody here has been using agents for quite a while, and you have probably noticed that we're sort of on an exponential curve in what we can do with them.
* **[00:50]** But the comparison that I want to give here is that you can be an amazing artist and use the greatest and latest technology from CNC machines to 3D printers, which are just very good power tools, and it can increase the ambition of what you can do with your art.
* **[01:05]** And I think we can also look at software a little bit in that sense, so less about building much more software and just building way more ambitious and high-quality software.

💡 **Visual-Speech Alignment:** Armin elaborates on bullet point 03 regarding building 'excellent software' rather than 'mass-produced slop' by drawing an analogy to artists using CNC machines and 3D printers.

---

## [01:21 - 02:40] Scene #3: The machine got better
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide detailing Section I (Stable Harness), showing how underlying AI models improved significantly over the past year while the core agent harness (Pi) remained unchanged.
> * **On-Screen OCR:** I STABLE HARNESS ; The machine got better ; 01 Most prompting ideas were replaced by better models ; 02 Basic Pi did not change ; 03 Yet I am much more capable today ; EARENDEL, INC. 03 / 16
> * **Structured Reconstruction:**
>   ### I. STABLE HARNESS
>   ## The machine got better
>   
>   1. Most prompting ideas were replaced by *better models*
>   2. Basic Pi did *not change*
>   3. Yet I am *much more capable* today

**🎙️ Spoken Transcript:**
* **[01:20]** And you might know that Earendel is working on the Pi coding agent, so we have obviously a little bit of a horse in the race here of how we're looking at this.
* **[01:30]** Um, but I think what is probably quite interesting is that the Pi coding agent has not really changed in a year on the core harness, it still has the same tools today as it did in December last year.
* **[01:40]** And I think this is interesting because it has become much more powerful, purely as an effect of the models getting better.
* **[02:07]** And you might have remembered throughout the last year and a half that there were a lot of ideas of how you can prompt the machines better or do some interesting tricks with the harness, very few of them are still necessary.
* **[02:20]** For me a good example here is that I was in love with Pi Auto Research... But if you use a present day state of the art model, you actually discover that the entire plugin is no longer necessary.

💡 **Visual-Speech Alignment:** Armin references the points on the slide explaining that the Pi harness stayed identical while model capability gains eliminated the need for complex prompt tricks or custom research plugins.

---

## [02:41 - 03:09] Scene #4: I step in less with every model
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide displaying two horizontal bar charts measuring user intervention metrics (Corrections per 100 Prompts and ESC Aborts per 100 Prompts) across model generations (GPT-5.3 Codex, GPT-5.5, GPT-5.6, Opus 5.5).
> * **On-Screen OCR:** I STABLE HARNESS ; I step in less with every model ; CORRECTIONS PER 100 PROMPTS ; GPT-5.3 Codex: 8.8 ; GPT-5.5: 7.2 ; GPT-5.6: 5.3 ; Opus 5.5: 2.9 ; ESC ABORTS PER 100 PROMPTS ; GPT-5.3 Codex: 13.1 ; GPT-5.5: 12.0 ; GPT-5.6: 10.4 ; Opus 5.5: 7.2 ; N=3,153 SESSIONS OUTSIDE TASK ENGINE. MARCH 14 TO NOVEMBER 2026. CORRECTIONS: REWORK/PROMPTS; ABORTS: ESC/ABORT ; EARENDEL, INC. 04 / 16
> * **Structured Reconstruction:**
>   | Model | Corrections per 100 Prompts | ESC Aborts per 100 Prompts |
>   |---|---|---|
>   | GPT-5.3 Codex | 8.8 | 13.1 |
>   | GPT-5.5 | 7.2 | 12.0 |
>   | GPT-5.6 | 5.3 | 10.4 |
>   | Opus 5.5 | 2.9 | 7.2 |

**🎙️ Spoken Transcript:**
* **[02:41]** Um and I just want to show this from a couple of graphs from basically my Pi sessions where I filtered them out to have nothing but the default set.
* **[02:50]** And the total amount of corrections, and I used Chef to analyze this, the total amount of corrections that I had to do got down and down and down with every single model that got better and better.
* **[03:00]** So I'm pushing back a lot less against the agent with the latest model than I did in December last year, and the same thing with how often I'm aborting it.

💡 **Visual-Speech Alignment:** Armin discusses the two bar charts shown on screen, highlighting the downward trend in both manual corrections (left chart) and escape aborts (right chart) as models progressed from GPT-5.3 Codex down to Opus 5.5.

---

## [03:10 - 03:46] Scene #5: How far one prompt carries, by model
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide showing two horizontal bar charts displaying agent autonomy metrics (90th percentile runtime in minutes per prompt and tool calls per prompt) across model releases.
> * **On-Screen OCR:** I STABLE HARNESS ; How far one prompt carries, by model ; MINUTES OF AGENT WORK PER PROMPT ; Opus 4.6: 2.4 min ; GPT-5.3 Codex: 2.4 min ; GPT-5.5: 5.0 min ; GPT-5.6: 5.5 min ; Opus 5.5: 14 min ; TOOL CALLS PER PROMPT ; Opus 4.6: 19 ; GPT-5.3 Codex: 19 ; GPT-5.5: 37 ; GPT-5.6: 54 ; Opus 5.5: 64 ; 90TH PERCENTILE PER PROMPT, GROUPED BY THE MODEL THAT MADE MOST CALLS IN THE RUN. N=3,153 SESSIONS IN DECEMBER 2026. RUN = FROM 1ST PROMPT TO THE LAST EVENT BEFORE NEXT PROMPT. ; EARENDEL, INC. 05 / 16
> * **Structured Reconstruction:**
>   | Model | Minutes of Agent Work per Prompt (P90) | Tool Calls per Prompt (P90) |
>   |---|---|---|
>   | Opus 4.6 | 2.4 min | 19 |
>   | GPT-5.3 Codex | 2.4 min | 19 |
>   | GPT-5.5 | 5.0 min | 37 |
>   | GPT-5.6 | 5.5 min | 54 |
>   | Opus 5.5 | 14 min | 64 |

**🎙️ Spoken Transcript:**
* **[03:10]** Um and I think this to me was the most interesting way in which I sort of analyzed my sessions, which is the 90th percentile of how long an agent was running in response to a task that I gave it.
* **[03:25]** Uh with Opus 4.6 in December last year was about two and a half minutes. And now with the latest models they are on the 90th percentile running for 14 minutes and more.
* **[03:36]** And that does actually change something about how you want to work with a harness.

💡 **Visual-Speech Alignment:** Armin points directly to the metric showing runtime increase from 2.4 minutes (Opus 4.6) to 14 minutes (Opus 5.5) on the left chart and corresponding tool calls per prompt on the right chart.

---

## [03:47 - 04:36] Scene #6: Tool use by model, same harness
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide showing stacked horizontal bar charts illustrating the proportion of tool choices (read, ast, edit, write, bash variants) made by different AI models under identical harness settings.
> * **On-Screen OCR:** I STABLE HARNESS ; Tool use by model, same harness ; read tool ; ast tool ; edit tool ; write tool ; bash: sed, cat, grep, rg ; bash: python, node ; bash: git ; bash: other ; GPT-5.3 Codex: 28% read, 16% ast, 20% edit, 15% write, 3% sed/cat/grep, 4% python/node, 14% git, 15% other ; GPT-5.5: 34% read, 22% ast, 23% edit, 12% write, 1% sed/cat/grep, 3% python/node, 15% git, 15% other ; GPT-5.6: 30% read, 20% ast, 15% edit, 12% write, 1% sed/cat/grep, 5% python/node, 18% git, 15% other ; Opus 5.5: 28% read, 15% ast, 6% edit, 4% write, 1% sed/cat/grep, 5% python/node, 41% git, 20% other ; * Codemode was not yet in Pi before the Opus 5.5 sessions ; EARENDEL, INC. 06 / 16
> * **Structured Reconstruction:**
>   | Model | Read Tool | AST Tool | Edit Tool | Write Tool | Bash: sed/cat/grep/rg | Bash: python/node | Bash: git | Bash: other |
>   |---|---|---|---|---|---|---|---|---|
>   | GPT-5.3 Codex | 28% | 16% | 20% | 15% | 3% | 4% | 14% | 15% |
>   | GPT-5.5 | 34% | 22% | 23% | 12% | 1% | 3% | 15% | 15% |
>   | GPT-5.6 | 30% | 20% | 15% | 12% | 1% | 5% | 18% | 15% |
>   | Opus 5.5 | 28% | 15% | 6% | 4% | 1% | 5% | 41% | 20% |

**🎙️ Spoken Transcript:**
* **[03:47]** you will probably notice that the present day agents are much more likely to use bash than any of the other tools that are being provided.
* **[04:08]** What's missing here is Astra and Sonnet, they actually look very similar to Opus for my testing, I just didn't have enough data in my test set to show this nicely.
* **[04:19]** You will notice that there's a little purple thing here. I want to talk about this in the end, which is sort of code mode is sort of slowly creeping up.

💡 **Visual-Speech Alignment:** Armin highlights the huge red bar ('bash: git' at 41%) for Opus 5.5, illustrating emergent tool preference shifts towards bash execution.

---

## [04:37 - 06:10] Scene #7: The human did not
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide starting Section II (What the Factory Scales), arguing that human attention remains the static bottleneck while software creation scales exponentially, placing strain on external systems.
> * **On-Screen OCR:** II WHAT THE FACTORY SCALES ; The human did not ; 01 Human attention is limited, and we do not have more humans ; 02 Starting got fast, finishing and maintaining did not ; 03 We tax systems that were never taxed: GitHub, npm, random third-party websites, ... ; EARENDEL, INC. 07 / 16
> * **Structured Reconstruction:**
>   ### II. WHAT THE FACTORY SCALES
>   ## The human did not
>   
>   1. Human *attention* is limited, and we do not have *more humans*
>   2. Starting got fast, *finishing* and *maintaining* did not
>   3. We tax systems that were never taxed: *GitHub*, *npm*, random *third-party websites*, ...

**🎙️ Spoken Transcript:**
* **[04:37]** What has not changed in the last year... is that we are still humans, we're still limited by our fundamental capabilities.
* **[04:58]** human attention is for me at least, the limiting factor and I'm noticing this, largely in how coding agents are deployed in teams...
* **[05:15]** And starting new projects is getting incredibly easy with these agents... But maintaining them has not really gotten easier.
* **[05:30]** but we're also increasingly taxing a lot of external systems that actually in many ways are not supposed to be part of this revolution.
* **[05:38]** GitHub has a lot more commits being pushed up there... But I know quite a few people who have well-established old websites on the internet that found a new life for agents.

💡 **Visual-Speech Alignment:** Armin aligns his verbal commentary with bullet point 01 (human attention), bullet point 02 (starting vs maintaining), and bullet point 03 (external systems like GitHub/npm/websites).

---

## [06:11 - 06:46] Scene #8: Agent-hours per day and my prompts per day
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide with a combined line and bar chart contrasting flat user prompt volume per day against exponentially rising active agent-hours per day from March to November.
> * **On-Screen OCR:** II WHAT THE FACTORY SCALES ; Agent-hours per day and my prompts per day ; MY PROMPTS PER DAY (Line chart): Mar: 126, Apr: 160, May: 111, Jun: 137, Jul: 117, Aug: 182, Sep: 136, Oct: 159 ; AGENT-HOURS PER DAY (PARALLEL AGENTS COUNTED SEPARATELY) (Bar chart): Mar: 6.0, Apr: 5.6, May: 4.8, Jun: 5.2, Jul: 6.1, Aug: 8.4, Sep: 9.3, Oct: 14.4, Nov 1 to 8: 43.7 h ; N=3,153 SESSIONS. HOURS = MINUTES WITH ACTIVITY PER SESSION, GAPS UNDER 2 MINS FOLDED. SUMMED ACROSS PARALLEL SESSIONS. PER ACTIVE DAY. ; EARENDEL, INC. 08 / 16
> * **Structured Reconstruction:**
>   | Month | My Prompts per Day | Agent-Hours per Day |
>   |---|---|---|
>   | Mar | 126 | 6.0 h |
>   | Apr | 160 | 5.6 h |
>   | May | 111 | 4.8 h |
>   | Jun | 137 | 5.2 h |
>   | Jul | 117 | 6.1 h |
>   | Aug | 182 | 8.4 h |
>   | Sep | 136 | 9.3 h |
>   | Oct | 159 | 14.4 h |
>   | Nov 1 to 8 | - | 43.7 h |

**🎙️ Spoken Transcript:**
* **[06:11]** the number of prompts that I'm actively pushing over the year is sort of flat... alternating between 120, 190, something like this, prompts that I'm pushing per day.
* **[06:30]** you can see that the time that the agent was active for my use went from like less than my working day to many times my working day.
* **[06:41]** And this November is not even over, right? So you can see that this is taking an exponential curve up.

💡 **Visual-Speech Alignment:** Armin contrasts the top blue line (prompts per day hovering around 120-180) with the red callout bar at the bottom right showing active agent hours jumping to 43.7 hours/day in November.

---

## [06:47 - 07:56] Scene #9: Projects started and projects I keep working on
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide showing a line chart tracking cumulative projects started (reaching 141) against a flat bar chart of projects actively maintained (>5 days/month, staying around 10-12).
> * **On-Screen OCR:** II WHAT THE FACTORY SCALES ; Projects started and projects I keep working on ; PROJECTS STARTED, CUMULATIVE (Line): Mar: 24, Apr: 47, May: 61, Jun: 69, Jul: 84, Aug: 101, Sep: 118, Oct: 141 ; PROJECTS I WORKED ON FOR 5+ DAYS THAT MONTH (Bar): Mar: 12, Apr: 9, May: 6, Jun: 9, Jul: 11, Aug: 11, Sep: 10, Oct: 11 ; EARENDEL, INC. 09 / 16
> * **Structured Reconstruction:**
>   | Month | Projects Started (Cumulative) | Projects Worked on for 5+ Days That Month |
>   |---|---|---|
>   | Mar | 24 | 12 |
>   | Apr | 47 | 9 |
>   | May | 61 | 6 |
>   | Jun | 69 | 9 |
>   | Jul | 84 | 11 |
>   | Aug | 101 | 11 |
>   | Sep | 118 | 10 |
>   | Oct | 141 | 11 |

**🎙️ Spoken Transcript:**
* **[06:47]** this here is the number of projects, this is Git repositories that I've created over the last year and this is cumulatively going up so I have 141 different projects that I started.
* **[06:58]** But the number of projects I'm committing on a regular cadence to... is pretty much flat between 10, 15, something like this.
* **[07:20]** I had this discussion with a friend of mine... he said 'Well actually I have an open source project that is now fully automated... But actually he also turned it off because eventually he didn't care about the project as much anymore...'

💡 **Visual-Speech Alignment:** Armin references the brown line showing 141 cumulative projects started versus the dark bars at the bottom indicating only 10-11 maintained projects per month.

---

## [07:57 - 11:11] Scene #10: What the workshop needs
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide introducing Section III (The Atelier), detailing essential practices for human-AI interaction in the software workshop.
> * **On-Screen OCR:** III THE ATELIER ; What the workshop needs ; 01 Being able to say "not like this" ; 02 True skill vs. agent skill ; 03 Moderating speed by one's understanding ; EARENDEL, INC. 10 / 16
> * **Structured Reconstruction:**
>   ### III. THE ATELIER
>   ## What the workshop needs
>   
>   1. Being able to say *"not like this"*
>   2. *True skill* vs. *agent skill*
>   3. Moderating speed by *one's understanding*

**🎙️ Spoken Transcript:**
* **[08:10]** the three most important things to matter is on the one hand, to really know when to push back against what an agent is doing, telling it that this is the wrong way of doing it.
* **[08:48]** It's very easy to basically create the Simpson car of all the features in a software... but actually having something that intrinsically fits together... still requires us to work with it as it's working.
* **[09:12]** And I like to call this like true skill versus agent skill. There is clearly a difference between someone who is an experienced software engineer working with an agent and someone who is not...
* **[10:07]** so there is a lot of value in still understanding what you're doing. That also means that you kind of have to moderate the speed in which you're doing things...
* **[10:36]** I started basically prompting the agent that before it's going towards the verification... to start producing me a really nice short executive summary and a nice type-set HTML page...

💡 **Visual-Speech Alignment:** Armin discusses points 01 (pushing back 'not like this'), 02 (true skill vs agent skill with an anecdote about his son), and 03 (moderating speed via HTML/executive summaries).

---

## [11:12 - 13:30] Scene #11: Resist the temptation
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide warning against uncontrolled code growth ('Wildwuchs'), arguing for adherence to open protocols, standards, and human collaboration despite friction.
> * **On-Screen OCR:** III THE ATELIER ; Resist the temptation ; 01 Sometimes building your own is bad for the ecosystem ; 02 "Wildwuchs" harms interoperability ; 03 Open protocols, specifications and file formats are useful ; 04 But collaboration is human slow! ; EARENDEL, INC. 11 / 16
> * **Structured Reconstruction:**
>   ### III. THE ATELIER
>   ## Resist the temptation
>   
>   1. Sometimes building your own is *bad for the ecosystem*
>   2. *"Wildwuchs"* harms interoperability
>   3. *Open* protocols, specifications and file formats are useful
>   4. But collaboration is *human slow!*

**🎙️ Spoken Transcript:**
* **[11:24]** I'm a huge believer in using few dependencies and writing more code yourself... But in German we have this word called Wildwuchs, which basically means uncontrolled growth.
* **[11:47]** You might have seen a blog post that was going around recently about a tar archive that has been crafted in a way that different tar implementations read it in different ways.
* **[12:00]** We for us to work together, we really want to have standards, we want to have common specifications, we want to have common file formats.
* **[12:50]** And this really comes down to this part that collaboration between humans is as hard as it has ever been. And this is slowing us in a way down...

💡 **Visual-Speech Alignment:** Armin speaks directly to the points on Slide 11, explicitly defining 'Wildwuchs' (bullet 02) and discussing human collaboration bottlenecks (bullet 04).

---

## [13:31 - 15:01] Scene #12: Spend the power on excellence
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide outlining key focus areas for high-quality software engineering: formal verification, high performance/efficiency, and memory safety (e.g. Rust).
> * **On-Screen OCR:** III THE ATELIER ; Spend the power on excellence ; 01 More software that is verified ; 02 More software that is faster ; 03 More software in memory-safe languages ; EARENDEL, INC. 12 / 16
> * **Structured Reconstruction:**
>   ### III. THE ATELIER
>   ## Spend the power on excellence
>   
>   1. More software that is *verified*
>   2. More software that is *faster*
>   3. More software in *memory-safe languages*

**🎙️ Spoken Transcript:**
* **[13:32]** so I want to make a very strong argument for building software that strives towards excellence.
* **[13:40]** We have I think seen a pretty big explosion recently of verified software.
* **[14:01]** I'm very happy with seeing so many people wanting to build fundamentally faster and more memory efficient software.
* **[14:35]** I really like Rust, I like that there is now a trend towards building memory safe software.

💡 **Visual-Speech Alignment:** Armin goes through bullet points 01, 02, and 03 sequentially, emphasizing verified software, performance, and memory safety.

---

## [15:02 - 16:51] Scene #13: Durability: suspend and come back
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide introducing Section IV (Where the Harness Can Evolve), focusing on durable execution workflows that persist state, handle human delays, and intelligently schedule compute/inference.
> * **On-Screen OCR:** IV WHERE THE HARNESS CAN EVOLVE ; Durability: suspend and come back ; 01 Runs now outlive the process and the attention of the human ; 02 Humans answer in hours, so waiting has to be durable ; 03 Intelligently schedule inference and compute ; EARENDEL, INC. 13 / 16
> * **Structured Reconstruction:**
>   ### IV. WHERE THE HARNESS CAN EVOLVE
>   ## Durability: suspend and come back
>   
>   1. Runs now outlive the *process* and the *attention* of the human
>   2. Humans answer in *hours*, so waiting has to be *durable*
>   3. Intelligently *schedule* inference and compute

**🎙️ Spoken Transcript:**
* **[15:02]** On the last part, I want to talk a little bit about maybe there is something where harness can evolve.
* **[15:49]** Because we're pretty big believers on this concept of durable agents or durable workflows where they orchestrate themselves in a way where you can start it, stop it, suspend it, bring it back.
* **[16:20]** For instance, if you pay raw token cost, you get a pretty significant discount for flexible scheduling. But that means that maybe for minutes no token is coming... so then you want to suspend your agent...

💡 **Visual-Speech Alignment:** Armin connects his discussion of long-running workflows and flexible inference pricing discounts to the three bullet points on durable execution.

---

## [16:52 - 18:16] Scene #14: Codemode: expressiveness in the tool call
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide explaining 'Codemode'—allowing agents to run programmatically composed scripts (e.g. JavaScript/Bash) harness-side to execute loops and concurrency without context window bloat.
> * **On-Screen OCR:** IV WHERE THE HARNESS CAN EVOLVE ; Codemode: expressiveness in the tool call ; 01 Bash composes programs, not the harness's own tools ; 02 Loops and concurrency without going through the context ; 03 Runs on the harness side, state lives in the transcript ; EARENDEL, INC. 14 / 16
> * **Structured Reconstruction:**
>   ### IV. WHERE THE HARNESS CAN EVOLVE
>   ## Codemode: expressiveness in the tool call
>   
>   1. Bash composes *programs*, not the harness's own tools
>   2. Loops and concurrency *without going through the context*
>   3. Runs on the *harness side*, state lives in the *transcript*

**🎙️ Spoken Transcript:**
* **[16:50]** And the second thing is you probably know that when Pi came out, there was a pretty big motivation to say like Bash is everything that you have to run...
* **[17:25]** instead of having thousands of tools being put into the context, what if we just give the agent in addition to JavaScript, in addition to Bash, JavaScript to run?
* **[17:55]** you can have the harness orchestrate very large invocations of tool calls without having to go through the inefficient context.

💡 **Visual-Speech Alignment:** Armin explains the mechanism behind Codemode (bullet points 01-03), describing tool call orchestration in code to keep context lean.

---

## [18:17 - 19:21] Scene #15: Classifier models (Jev, Chef, ...)
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide detailing the use of fast, cheap specialized classifier/decision models (like Chef/Jev) invoked directly within codemode scripts for high-throughput task evaluations.
> * **On-Screen OCR:** IV WHERE THE HARNESS CAN EVOLVE ; Classifier models (Jev, Chef, ...) ; 01 Crunch through large numbers of squishy human tasks ; 02 Ask questions, get choices and scores back, not prose ; 03 Called from codemode and loops, not through the context ; EARENDEL, INC. 15 / 16
> * **Structured Reconstruction:**
>   ### IV. WHERE THE HARNESS CAN EVOLVE
>   ## Classifier models (Jev, Chef, ...)
>   
>   1. Crunch through large numbers of *squishy human tasks*
>   2. Ask questions, get *choices and scores* back, not prose
>   3. Called from *codemode* and loops, not through the context

**🎙️ Spoken Transcript:**
* **[18:17]** it also allows you to use classifier models. And I think this is the other big part that really changed how I was looking at how far I can push certain technology.
* **[18:42]** when you have code mode, what the harness can do is it can create a little workflow that can have decision points along the way... crunch through 3,000 incoming customer support requests...
* **[19:10]** And then you can crunch through thousands of issues in no time in your coding agent, where previously that would have taken you hours.

💡 **Visual-Speech Alignment:** Armin illustrates bullet point 01 ('squishy human tasks') and bullet point 03 (called from loops) using an example of processing 3,000 support requests with Chef.

---

## [19:22 - 19:55] Scene #16: We can build anything, but should we?
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Concluding slide featuring the summary quote 'We can build anything, but should we?', followed by the event closing logo card.
> * **On-Screen OCR:** THE SOFTWARE ATELIER ; We can build anything, but should we? ; EARENDEL, INC. 16 / 16 ; AI Engineer Code Summit ; HTTPS://AI.ENGINEER
> * **Structured Reconstruction:**
>   # We can build anything, but should we?
>   
>   *EARENDEL, INC. | 16 / 16*

**🎙️ Spoken Transcript:**
* **[19:20]** so with this, I just want to leave this idea: Now that we can build anything, maybe we should not.
* **[19:28]** but we should really I think push towards much more enjoyable and in many ways much more ambitious software than we have been doing before. Thank you.

💡 **Visual-Speech Alignment:** Armin reads the closing statement shown on the final slide before the presentation transitions to the AI Engineer summit end title card.

---
