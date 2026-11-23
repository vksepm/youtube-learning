# Enriched Interleaved Transcript: What Runs Where? Local AI in Production — Ahmad Osman, Osmantic
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=GKSQYbELDzw
**Model:** `gemini-3.6-flash` | **Processing Mode:** `agentic`

---

## [00:00 - 00:20] Scene #1: What Runs Where? Local AI in Production
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Opening title slide for the workshop hosted by Ahmad M. Osman at AI Engineer Code Summit. The slide outlines the primary thesis: local AI has advanced quickly, but placement and optimization across workloads remain the key challenge.
> * **On-Screen OCR:** WORKSHOP ; What Runs Where? Local AI in Production ; Local AI got good faster than it got easy. ; A laptop built a playable game on 37 watts of GPU power. ; The frontier is still 18 index points ahead of open weights. ; Both are true today. What runs where is the work. ; The answer moves every few months. This hour is how to find it for your own workload. ; Ahmad M. Osman - Founder & CEO, Osmantic - @TheAhmadOsman ; ODS / AI Engineer Code Summit - San Francisco - November 10, 2026
> * **Structured Reconstruction:**
>   # What Runs Where? Local AI in Production
>   Local AI got good faster than it got easy.
>   
>   - A laptop built a playable game on 37 watts of GPU power.
>   - The frontier is still 18 index points ahead of open weights.
>   - Both are true today. What runs where is the work.
>   
>   The answer moves every few months. This hour is how to find it for your own workload.
>   
>   Ahmad M. Osman | Founder & CEO, Osmantic | @TheAhmadOsman

**🎙️ Spoken Transcript:**
* **[00:13]** I'm just going to give everyone a second to settle in.

💡 **Visual-Speech Alignment:** The speaker welcomes the audience while introducing the theme of the workshop shown on the title slide.

---

## [00:21 - 00:49] Scene #2: June, on this stage: 'the 90s of Linux'
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide comparing the speaker's June 2026 panel statement ('the 90s of Linux') with his November 2026 stance emphasizing granular optimization per chip, per model, and per workflow.
> * **On-Screen OCR:** WHERE WE ARE ; June, on this stage: 'the 90s of Linux' ; What I said on this conference's stage in June, and where I stand today: ; JUNE 2026 - AIEWF STATE OF THE UNION PANEL ; "We're in the 90s of the Linux operating system... The infrastructure is not there yet." ; NOVEMBER 2026 - MY POSITION TODAY ; - Per chip. ; - Per model. ; - Per workflow. ; Optimization is the future.
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph June_2026 [June 2026: AI World's Fair]
>           A["We're in the 90s of the Linux operating system... The infrastructure is not there yet."]
>       end
>       subgraph Nov_2026 [November 2026: Position Today]
>           B["Per chip"]
>           C["Per model"]
>           D["Per workflow"]
>       end
>       June_2026 --> Nov_2026

**🎙️ Spoken Transcript:**
* **[00:21]** So, I have 170 slides for you. I believe that we're not going to be able to go through all of them. But they will be posted online very soon.
* **[00:30]** yeah, this is basically what runs where and locally in production. And the goal is to go through the history of local AI...
* **[00:40]** you know, probably we're going to go back a bit to 2023. And where we're heading in the future, and of course talking about where we are today.

💡 **Visual-Speech Alignment:** The speaker references his previous panel statement from June 2026 displayed on the left side of the slide.

---

## [00:50 - 01:30] Scene #3: Open-source AI is an infrastructure optimization problem.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide highlighting the core difference between open-source AI (infrastructure optimization problem) and local AI (user experience problem covering setup, responsiveness, reliability, and task fit).
> * **On-Screen OCR:** WHERE WE ARE ; Open-source AI is an infrastructure optimization problem. ; Optimized infrastructure only counts once it reaches the person at the keyboard: ; Local AI is a user experience problem. ; Setup ; Responsiveness ; Reliability ; Fits the task
> * **Structured Reconstruction:**
>   | Category | Definition | Critical Pillars |
>   | :--- | :--- | :--- |
>   | **Open-source AI** | Infrastructure optimization problem | Optimized execution engine reaching the end-user |
>   | **Local AI** | User experience problem | Setup, Responsiveness, Reliability, Fits the task |

**🎙️ Spoken Transcript:**
* **[01:00]** yeah and back then I said that we are basically in the 90s of Linux. Uh and I think we're starting to finally see more and more people invest in the ecosystem and the infrastructure.
* **[01:11]** since then we have been seeing more mega kernels or what people call mega kernels, we've been seeing new inference engines...
* **[01:20]** we're seeing a lot of people trying to optimize basically per model, per chip, per workflow, and that's the way to go.

💡 **Visual-Speech Alignment:** Connects 'optimization problem' and 'user experience problem' text on screen with the spoken explanation of infrastructure vs user experience.

---

## [01:31 - 02:15] Scene #4: A laptop built this game
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Demo slide featuring a video recording of 'Elf of Doom', a playable game generated locally on an ASUS ProArt P16 laptop equipped with an RTX Spark GPU, displaying real-time generation metrics.
> * **On-Screen OCR:** LOCAL TODAY ; A laptop built this game ; Qwen3.8-Flash-Next ; 125B total, 6B active ; Decode 60 tok/s (peak 87) ; Prefill 1,000-1,500 tok/s ; 37 W: 89 of 96 GB in use ; On a laptop. ; Click the video to play - 39 s ; Play it: odsspark.com ; Elf of Doom - ASUS ProArt P16 (RTX Spark), 128 GB - rates as shown on the demo's own panel
> * **Structured Reconstruction:**
>   ### Demo Spec: Elf of Doom Game Generation
>   - **Model**: Qwen3.8-Flash-Next (125B total, 6B active)
>   - **Hardware**: ASUS ProArt P16 (RTX Spark), 128 GB RAM
>   - **Power Usage**: 37 W (89 of 96 GB memory in use)
>   - **Decode Speed**: 60 tok/s (peak 87 tok/s)
>   - **Prefill Speed**: 1,000 - 1,500 tok/s
>   - **Play Link**: odsspark.com

**🎙️ Spoken Transcript:**
* **[01:32]** Open source AI is an optimization problem, local AI is a user experience problem. And both of those things need to be solved in parallel to each other.
* **[01:40]** This is from our recent launch co-launch with Nvidia. We built an optimized inference engine for the RTX Spark...
* **[02:00]** you can play this game on odsspark.com and you can see all the traces. This was built fully locally, no cloud, no Codex...

💡 **Visual-Speech Alignment:** Points to the game video demo and metrics listed on the slide for the RTX Spark laptop demo.

---

## [02:16 - 02:39] Scene #5: People lined up to play it
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Photo slide showing crowds gathered at the Best Buy launch line for the RTX Spark local AI demo.
> * **On-Screen OCR:** LOCAL TODAY ; People lined up to play it ; RTX Spark Official Launch at Best Buy - the ODS demo line ; Play it: odsspark.com ; ODS demo - October 2026
> * **Structured Reconstruction:**
>   ![Best Buy Launch Line](odsspark_bestbuy_launch.png)
>   *RTX Spark Official Launch at Best Buy showing the ODS demo line crowd (October 2026).*

**🎙️ Spoken Transcript:**
* **[02:20]** And this is from the Best Buy launch, official launch for the RTX Spark. We had so many people around us that wanted to play this game...
* **[02:30]** so we're starting to see more of everybody, like everyday persons actually showing up for local AI and interested in what's being done in here.

💡 **Visual-Speech Alignment:** Pointers to the photo showing people lined up at the Best Buy launch event.

---

## [02:40 - 03:00] Scene #6: Which answer came from the desktop?
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Side-by-side blind test comparing token generation explanations from Answer A (desktop local model) and Answer B (GPT-5.5 cloud).
> * **On-Screen OCR:** BLIND TEST ; Which answer came from the desktop? ; Explain how a transformer generates one token. One answer came from a desktop, the other from GPT-5.5. ; Hugging Face's Local AI 201 - Nov 10, 2026
> * **Structured Reconstruction:**
>   ### Blind Test Comparison
>   Prompt: "Explain how a transformer generates one token."
>   
>   - **Answer A**: Autoregressive decoding explanation utilizing token embeddings, positional encoding, residual connections, and softmax prediction.
>   - **Answer B**: Multi-stage transformer explanation breaking down attention matrices, feedforward layers, and vocabulary logit projection.

**🎙️ Spoken Transcript:**
* **[02:42]** Can you tell the difference between these two answers? One of them was a local model and another was GPT 5.5.
* **[02:50]** This is from our video online with Hugging Face, it's Local AI 201.

💡 **Visual-Speech Alignment:** Refers to the side-by-side text boxes marked A and B.

---

## [03:01 - 03:30] Scene #7: A was the desktop. It finished first.
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Benchmark results revealing Answer A (Blackwell Tower local Qwen3.6-27B FP8) beat GPT-5.5 cloud in both latency and total completion time.
> * **On-Screen OCR:** BLIND TEST ; A was the desktop. It finished first. ; Qwen3.6-27B (27B dense, FP8) on one RTX PRO 6000 vs GPT-5.5 (parameters undisclosed). ; A - Blackwell Tower, local: 0.04 s to first token, 51 tok/s decode, 5.0 s total ; B - GPT-5.5, OpenAI cloud: 4.33 s to first token, 34 tok/s decode, 12.2 s total ; One user, one question: the desktop wins. Now give it a real job.
> * **Structured Reconstruction:**
>   | Option | Environment / Model | Time to First Token | Decode Speed | Total Duration |
>   | :--- | :--- | :--- | :--- | :--- |
>   | **A** | Blackwell Tower, local (Qwen3.6-27B FP8) | **0.04 s** | **51 tok/s** | **5.0 s** |
>   | **B** | GPT-5.5, OpenAI cloud | 4.33 s | 34 tok/s | 12.2 s |

**🎙️ Spoken Transcript:**
* **[03:05]** the model that we ran locally was 3.6 27 billion parameter. And it ran at 51 tokens per second for decoding, while GPT 5.5 via OpenAI Cloud was running at 34 tokens per second.
* **[03:20]** And I don't know if you guys are using CLI at this point, but it's pretty slow in comparison to anything local.

💡 **Visual-Speech Alignment:** Connects metrics (0.04s vs 4.33s TTFT, 51 tok/s vs 34 tok/s decode) to Desktop A vs Cloud B.

---

## [03:31 - 04:00] Scene #8: The frontier is ahead, and it can afford to compound
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Chart of Artificial Analysis Intelligence Index v5.01 evaluating closed vs open weight models, questioning benchmark fidelity where Haiku 5.5 scores above DeepSeek V4.1 Flash.
> * **On-Screen OCR:** WHY NOW ; The frontier is ahead, and it can afford to compound ; Artificial Analysis Intelligence Index v5.01, Nov 9 - best configuration of each model: ; Closed weights: Fable 5.2 (64.6), Gemini 4.8 (59.5), Opus 5.5 (57.3), GPT-6 Astra (55.4), Haiku 5.5 (52.2) ; Open weights: Kimi K3.1 Pro (46.5), DeepSeek V4.1 Flash (32.6), GLM-5.3 (31.7) ; 18 points ahead at the top. One rung down, Haiku 5.5 trails the open frontier by ten points.
> * **Structured Reconstruction:**
>   | Category | Model Name | Index Score |
>   | :--- | :--- | :--- |
>   | **Closed Weights** | Fable 5.2 | 64.6 |
>   | Closed Weights | Gemini 4.8 | 59.5 |
>   | Closed Weights | Opus 5.5 | 57.3 |
>   | Closed Weights | GPT-6 Astra | 55.4 |
>   | Closed Weights | Haiku 5.5 | 52.2 |
>   | **Open Weights** | Kimi K3.1 Pro | 46.5 |
>   | Open Weights | DeepSeek V4.1 Flash | 32.6 |
>   | Open Weights | GLM-5.3 | 31.7 |

**🎙️ Spoken Transcript:**
* **[03:35]** This one is an interesting one. Anyone saw the new Artificial analysis index V5?
* **[03:45]** They have that Anthropic Haiku 5.5 is ahead of DeepSeek V4.1 flash.
* **[03:55]** if your evals are showing that Haiku code is beating DeepSeek V4.1 flash, there's a problem there.

💡 **Visual-Speech Alignment:** Pointers to Haiku 5.5 (52.2) vs DeepSeek V4.1 Flash (32.6) on the benchmark chart.

---

## [04:01 - 04:35] Scene #9: Four-minute tasks to twelve-hour tasks in three years
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** METR task length progression table demonstrating model autonomous horizon capabilities doubling roughly every 4 months.
> * **On-Screen OCR:** WHY NOW ; Four-minute tasks to twelve-hour tasks in three years ; METR: task length (in expert-human time) a model completes 50% and 80% of the time: ; GPT-4 (Mar 2023): 4 min (50%), 1 min (80%) ; c3 (Nov 2023): 2.5 min, 4 min ; Opus 4.5 (Nov 2025): 4.9 h, 49 min ; Opus 4.6 (Feb 2026): 12 h, 70 min ; Mythos Preview (Apr 2026): 17 h*, 3.1 h ; Doubling every ~4 months. Longer tasks burn more tokens. Where they run is now a budget question.
> * **Structured Reconstruction:**
>   | Model | Release Date | 50% Horizon | 80% Horizon |
>   | :--- | :--- | :--- | :--- |
>   | GPT-4 | Mar 2023 | 4 min | 1 min |
>   | c3 | Nov 2023 | 2.5 min | 4 min |
>   | Opus 4.5 | Nov 2025 | 4.9 h | 49 min |
>   | Opus 4.6 | Feb 2026 | **12 h** | **70 min** |
>   | Mythos Preview | Apr 2026 | 17 h* | 3.1 h |

**🎙️ Spoken Transcript:**
* **[04:11]** It's showing the progress since March 2023 and how long long horizon tasks are becoming longer in terms of what humans could do that machines could solve right now.
* **[04:25]** We're seeing that basically it's doubling every four months and that rate is not slowing down.

💡 **Visual-Speech Alignment:** Speaker gestures toward the METR task length metrics and the exponential trend line.

---

## [04:36 - 05:08] Scene #10: Agents send most tokens. Caching pays for it.
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Line graph based on OpenRouter data showing agent-generated tokens surpassing human-generated tokens starting in February 2026, driving high context-cache hit rates.
> * **On-Screen OCR:** WHY NOW ; Agents send most tokens. Caching pays for it. ; OpenRouter, October 2026 - tokens per month by how each API key is used (T = trillion): ; Agentic keys (top red line reaching ~680T) ; Mixed keys / Human-paced keys (bottom lines) ; What their providers cache: Cache rate on agentic keys among providers serving >1T of them: ; 13 of 24 above 90% in June ; 3 of 16 above 90% in June ; Median 90% vs human 76% ; Agents resend the same context every turn. Reuse it, hosted or local.
> * **Structured Reconstruction:**
>   | Key Class | Token Volume Trend (Trillions/mo) | Caching Behavior |
>   | :--- | :--- | :--- |
>   | **Agentic Keys** | Exponential growth (surpassed human in Feb 2026, hit ~680T Oct 2026) | Resends same context every turn; median 90% cache rate |
>   | **Human-Paced Keys** | Flat/Slow growth (<100T) | Low context repetition; 76% cache rate |

**🎙️ Spoken Transcript:**
* **[04:40]** This is from Open Router's data, October 2026... the number of tokens are in trillions. And since February, agents are the ones producing tokens more than humans.
* **[04:55]** The last time a human was the one generating more tokens out there was February 2026. And I guess we're never going to get there again.

💡 **Visual-Speech Alignment:** Points to the agentic token curve overtaking human-paced key volume starting February 2026.

---

## [05:09 - 05:52] Scene #11: And yet, open models jumped
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Line chart showing rapid progress in open frontier models on Artificial Analysis Intelligence Index v4.1, jumping from 13 to 51 points between Jan 2025 and June 2026.
> * **On-Screen OCR:** WHY NOW ; And yet, open models jumped ; Best score to date, Artificial Analysis Intelligence Index v4.1 (the scale before v5): ; Open frontier went from 13 to 51 in 17 months. ; In June it matched the closed frontier of March.
> * **Structured Reconstruction:**
>   | Month | Open Frontier Score | Closed Frontier Score |
>   | :--- | :--- | :--- |
>   | Jan 2025 | 13 | ~26 |
>   | Apr 2025 | ~18 | ~31 |
>   | Jul 2025 | ~24 | ~35 |
>   | Oct 2025 | ~31 | ~42 |
>   | Jan 2026 | ~42 | ~48 |
>   | Jun 2026 | **51** | ~56 |

**🎙️ Spoken Transcript:**
* **[05:10]** This is Artificial Analysis Intelligence Index V4.1. And it's showing that the open source models since January 2025 basically have jumped up from 13 points to 51 on the index.
* **[05:25]** And the gap is becoming smaller and smaller.

💡 **Visual-Speech Alignment:** Refers to the parallel upward lines comparing open vs closed models over time.

---

## [05:53 - 06:27] Scene #12: Opus 5.5's level goes open. It's still a specialist.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide featuring tweet posts by @TheAhmadOsman predicting open weights catching up to Opus levels while making a case for 1B-2B small specialist models.
> * **On-Screen OCR:** WHY NOW ; Opus 5.5's level goes open. It's still a specialist. ; Opus 5.5's level should reach open weights around March 2027. It will still have an edge, so test each stage, not the model. ; Posted Sep 23 & Nov 8, 2026 by @TheAhmadOsman
> * **Structured Reconstruction:**
>   > **@TheAhmadOsman (Sep 23 & Nov 8, 2026)**
>   > Opus 5.5's intelligence level is about 6 months out of being available from open-weights labs.
>   > The future is small & specialized models.
>   > Out-of-distribution tasks are the ones that the big flagship models win.

**🎙️ Spoken Transcript:**
* **[06:00]** I have a tweet since March 2025, saying the future is small and specialized models.
* **[06:15]** And I believe that in three years or less, we're going to have a 1 billion parameter model that beats Opus 5.5.

💡 **Visual-Speech Alignment:** Direct reference to the author's tweets shown on screen.

---

## [06:28 - 07:10] Scene #13: Open models carry most tokens, not most dollars
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Dual stacked bar charts illustrating that open-weight models represent 70.3% of token traffic but closed models receive 72.5% of total user spend.
> * **On-Screen OCR:** WHY NOW ; Open models carry most tokens, not most dollars ; OpenRouter paid traffic, week of Oct 19, 2026, one cohort for both charts: ; Share of paid tokens: Closed weights 29.7%, Open weights 70.3% ; Share of paid spend: Closed weights 72.5%, Open weights 27.5% ; The work is moving to open models. The money still funds the frontier.
> * **Structured Reconstruction:**
>   | Metric | Closed Weights | Open Weights |
>   | :--- | :--- | :--- |
>   | **Share of Paid Tokens** | 29.7% | **70.3%** |
>   | **Share of Paid Spend** | **72.5%** | 27.5% |

**🎙️ Spoken Transcript:**
* **[06:30]** This is from OpenRouter... amount of money being spent on models right now, mostly closed weights. However, the number of tokens being consumed out there are mostly open source models.
* **[06:50]** pretty much in terms of tokens, everybody is using DeepSeek V4.1 Flash... but in terms of money spent it's Opus 5.5.

💡 **Visual-Speech Alignment:** Explains the contrast between token volume (70.3% open) and dollar spend (72.5% closed).

---

## [07:11 - 07:58] Scene #14: Routine work doesn't chase the newest model
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Horizontal bar chart comparing adoption of newly released models (<60 days old) for complex agentic engineering tasks vs routine support/classification tasks.
> * **On-Screen OCR:** WHY NOW ; Routine work doesn't chase the newest model ; Sept 2026: share of each task's requests going to models under 60 days old: ; Agentic engineering: File read/write 68%, Shell execution 64%, Debugging 61% ; Routine work: Classification 36%, Summarization 26%, Customer support 26% ; The newest model where the work is hard. Settled models where it's routine.
> * **Structured Reconstruction:**
>   | Category | Task | Share using Newest Models (<60d old) |
>   | :--- | :--- | :--- |
>   | **Agentic Engineering** | File read/write | 68% |
>   | Agentic Engineering | Shell execution | 64% |
>   | Agentic Engineering | Debugging | 61% |
>   | **Routine Work** | Classification | 36% |
>   | Routine Work | Summarization | 26% |
>   | Routine Work | Customer support | 26% |

**🎙️ Spoken Transcript:**
* **[07:15]** What are agents doing right now? And why do we think that there is a need for new chips... you're mostly waiting on an agent to run a shell command or do something, execute something and get the results back.
* **[07:35]** More than you are bottlenecked by tokens per second actually.

💡 **Visual-Speech Alignment:** Connects shell execution and agent tasks on the chart to real-world latency bottlenecks.

---

## [07:59 - 08:45] Scene #15: The open-closed gap depends on the test
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Comparison table showing huge variance in open vs closed performance depending on evaluation benchmark choice (43 point gap on HLE Diamond vs open leading by 2 points on Terminal-Bench 4.0).
> * **On-Screen OCR:** WHY NOW ; The open-closed gap depends on the test ; Best closed vs best open score on each independent test, Nov 2026: ; HLE Diamond: Closed 80.2, Open 37.3 (Gap: 43 points) ; WeirdVML (ML engineering): Closed 42.2, Open 9.9 (Gap: 32 points) ; FrontierCode 2.0: Closed 49.1, Open 28.5 (Gap: 21 points) ; AA Intelligence Index v5: Closed 64.6, Open 46.5 (Gap: 18 points) ; GDP.pdf (documents): Closed 32.6, Open 31.4 (Gap: 1 point) ; Terminal-Bench 4.0: Closed 65.2, Open 67.2 (Open ahead by 2) ; Between 43 points behind and 2 ahead. Which test looks like your job?
> * **Structured Reconstruction:**
>   | Test / Benchmark | Best Closed | Best Open | Gap |
>   | :--- | :--- | :--- | :--- |
>   | HLE Diamond | 80.2 | 37.3 | 43 points closed lead |
>   | WeirdVML (ML engineering) | 42.2 | 9.9 | 32 points closed lead |
>   | FrontierCode 2.0 | 49.1 | 28.5 | 21 points closed lead |
>   | AA Intelligence Index v5 | 64.6 | 46.5 | 18 points closed lead |
>   | GDP.pdf (documents) | 32.6 | 31.4 | 1 point closed lead |
>   | **Terminal-Bench 4.0** | 65.2 | **67.2** | **Open ahead by 2** |

**🎙️ Spoken Transcript:**
* **[08:00]** So that gap between open and closed models, it depends mostly on which benchmark you trust.
* **[08:10]** According to HLE Diamond, the gap is more than 30%. Terminal benchmarks says that open source models are ahead by two points.
* **[08:18]** So we have an eval problem, that's for sure.

💡 **Visual-Speech Alignment:** Pointers to HLE Diamond row (+43 gap) vs Terminal-Bench row (-2 gap, open ahead).

---

## [08:46 - 09:40] Scene #16: Pointed at the bug, small open models found it too
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Security audit experiment table showing small specialized models (3.6B active down to 0.1B active) successfully finding code vulnerabilities when isolated to specific steps.
> * **On-Screen OCR:** WHY NOW ; Pointed at the bug, small open models found it too ; A security vendor reran a frontier model's showcase bugs on small models: ; Step 1: Spot the overflow in one isolated function -> 8 of 8 models; down to 3.6B active at $0.11/M ; Step 2: Reason through a signed-integer overflow -> Split the models; a 5.1B-active one got the full chain ; Step 3: Tell a real bug from a look-alike -> Small open models beat most frontier ones ; Step 4: Recognize the patched code as safe -> Shaky; models kept flagging the fix ; Step 5: Find it unprompted in a whole codebase -> Not tested ; The model was enough for the step. The system around it is the work.
> * **Structured Reconstruction:**
>   | Audit Step | Result / Findings |
>   | :--- | :--- |
>   | **1. Spot overflow in isolated function** | 8 of 8 models succeeded; down to 3.6B active at $0.11/M |
>   | **2. Reason signed-integer overflow** | Split models; 5.1B-active model completed full chain |
>   | **3. Distinguish real bug vs look-alike** | Small open models beat most frontier ones |
>   | **4. Recognize patched code as safe** | Shaky; models repeatedly flagged fix |
>   | **5. Find unprompted in whole codebase** | Not tested |

**🎙️ Spoken Transcript:**
* **[08:48]** This is an interesting research came out in April... from a security vendor, pretty much was able to reproduce the same security gaps being caught by small specialized models.
* **[09:10]** This tells you something about the idea of small models.

💡 **Visual-Speech Alignment:** Explains how small models perform well on focused steps (Steps 1-3) when framed properly.

---

## [09:41 - 10:50] Scene #17: You don't need frontier intelligence at every step
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Core architectural principle slide stating that frontier intelligence is only needed at difficult reasoning steps, while small specialized models can handle the majority of tasks.
> * **On-Screen OCR:** WHY NOW ; You don't need frontier intelligence at every step ; You need it where the step is hard. Most of the rest already runs on something smaller. ; From the index gap, the traffic split and the per-test gaps just shown.
> * **Structured Reconstruction:**
>   # Core Thesis: Specialized Model Architecture
>   - **Frontier Intelligence**: Reserved exclusively for hard reasoning steps.
>   - **Small & Specialized Models**: Handles routine execution, routing, classification, and formatting.

**🎙️ Spoken Transcript:**
* **[09:50]** My name is Ahmad Osman, by the way. Let me introduce myself... CEO and founder of a company called Osmotic.
* **[10:30]** the thesis that I'm building this company around is that you don't need frontier intelligence at every step. A lot of what we're doing could be done with small and specialized models.

💡 **Visual-Speech Alignment:** Speaker aligns his company thesis with the large callout text on the slide.

---

## [10:51 - 12:34] Scene #18: Here's what that pipeline made / Our render ran on three kinds of worker
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Breakdown of a 17-minute video presentation trailer production pipeline distributed across local RTX PRO 6000 GPUs, a MacBook, and human review.
> * **On-Screen OCR:** THE RULE ; Our render ran on three kinds of worker ; One 17-minute video render last week. Where did each step run? ; 2x RTX PRO 6000: Qwen3-VL-8B tags photos, SeedVR2-7B upscales, Audio models clean dialogue (9 minutes) ; MacBook: FFmpeg cuts and mixes, Headless Chrome draws overlays, Final encode (~8 minutes) ; A human: Picks the A/B winners, Checks words and faces, Approves the cut ; Moving the Mac's 8 minutes would save 2-4. Not worth the setup. It stayed.
> * **Structured Reconstruction:**
>   flowchart TD
>       subgraph GPU_Box [2x RTX PRO 6000 - 9 min]
>           A1[Qwen3-VL-8B: Photo Tagging]
>           A2[SeedVR2-7B: Video Upscaling]
>           A3[Audio Models: Dialogue Clean]
>       end
>       subgraph Mac [MacBook - 8 min]
>           B1[FFmpeg: Cuts & Mixes]
>           B2[Chrome: Overlays]
>           B3[Final Video Encode]
>       end
>       subgraph Human [Human Reviewer]
>           C1[Select A/B Winners]
>           C2[Inspect Words & Faces]
>           C3[Approve Final Cut]
>       end
>       GPU_Box --> Mac --> Human

**🎙️ Spoken Transcript:**
* **[11:00]** Anyone saw the trailer that I created for this talk? This one right here. This was created with Claude Opus 5.5 end-to-end...
* **[11:50]** however it wasn't able to build this entire thing without... two RTX Pro 6000s that it used for pretty much tagging photos, upscaling videos, upscaling audio.
* **[12:10]** This took me 6 hours... I bet you that we're going to have a small and specialized model doing this within 3 years.

💡 **Visual-Speech Alignment:** Speaker connects trailer video demo to the 3-worker task allocation table.

---

## [12:35 - 13:50] Scene #19: The cloud is someone else's basement
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** UI screenshot of Portal (code name Cairo), the open-source local agent harness running as a self-hosted cloud server at home.
> * **On-Screen OCR:** THE RULE ; The cloud is someone else's basement ; Portal UI showing system prompt and task execution status ; So Portal, our agent in ODS (code name Cairo), is a cloud: the cloud at home. ; ODS Portal - 'your local ODS server agent' - Oct 18, 2026
> * **Structured Reconstruction:**
>   ### Portal Agent Architecture (Code Name: Cairo)
>   - **Concept**: "The Cloud at Home"
>   - **Function**: Local agent harness executing LLM commands, tool calls, and local inference without relying on external cloud APIs.

**🎙️ Spoken Transcript:**
* **[12:40]** The cloud is pretty much someone else's basement... we created this harness called Portal... code name for this thing is Cairo.
* **[13:15]** Local is basically the machine that you have under your desk or someone's API, it doesn't matter...

💡 **Visual-Speech Alignment:** Speaker highlights the Portal agent interface on screen.

---

## [13:51 - 15:19] Scene #20: My basement, November 2024: fourteen GPUs / The box had 14 GPUs. The run used one.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Photo of Ahmad Osman with his 14x RTX 3090 home setup, alongside a technical breakdown of running DeepSeek R1 (671B Q4) using CPU system RAM offloading.
> * **On-Screen OCR:** WILL IT FIT? ; My basement, November 2024: fourteen GPUs ; 14 x RTX 3090, EPYC 7713, 512 GB of RAM. ; The model I wanted: DeepSeek R1, 671B (37B active) at q4. About 400 GB of weights. ; Where do the weights go? ; February 2025: ~13 GB on GPU, ~390 GB in system RAM; 8.24 tok/s generating. ; Offload makes a giant model runnable, not fast. Inventory is not placement.
> * **Structured Reconstruction:**
>   | Component | Capacity / Allocation | Impact |
>   | :--- | :--- | :--- |
>   | **GPU VRAM** | 13 GB (1x RTX 3090) | Holds attention layers |
>   | **System RAM** | 390 GB (DDR4) | Holds remaining weights |
>   | **Total Model** | DeepSeek R1 671B (37B active, Q4) | 400 GB total weights |
>   | **Performance** | **8.24 tok/s** | Extremely slow due to CPU-GPU interconnect bottleneck |

**🎙️ Spoken Transcript:**
* **[14:20]** This is from my basement. 14 RTX 3090s behind me right there.
* **[14:30]** This thing was barely able to hold the DeepSeek R1 which came out in February 2025.
* **[14:45]** It was giving me like eight tokens per second on my RAM...

💡 **Visual-Speech Alignment:** References the photo of his home lab rig and the memory breakdown table for KTransformers offloading.

---

## [15:20 - 15:45] Scene #21: The tool I actually use runs on a 4B model
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Sequence diagram of a practical desktop screenshot organizer pipeline powered by Gemma 3 4B running locally under 6GB VRAM.
> * **On-Screen OCR:** WILL IT FIT? ; The tool I actually use runs on a 4B model ; My screenshot organizer on a desktop: Gemma 3 4B (48B dense, 4B active), under 6 GB of VRAM. ; Screenshot -> API call -> Model returns -> Code checks -> File renamed ; The reply isn't usable JSON (the file goes to 'uncategorized'). A product buys funny renames first. ; On the big server it ran every few weeks. On the desktop, I actually use it.
> * **Structured Reconstruction:**
>   flowchart LR
>       A[Screenshot] --> B["API Call (Gemma 3 4B)"]
>       B --> C["Model Returns JSON"]
>       C --> D[Code Checks]
>       D --> E[File Renamed]

**🎙️ Spoken Transcript:**
* **[15:25]** Even like with Gemma 3 the four billion parameter model, I was able to build this screenshot organizer at home running on an RTX 4090.
* **[15:35]** The models were already so capable, but nobody wanted to put a little bit of systems engineering behind it.

💡 **Visual-Speech Alignment:** Speaker traces the 5-step diagram showing desktop Gemma 3 4B processing screenshots.

---

## [15:46 - 17:09] Scene #22: QAT: train with the rounding in the loop
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Diagram detailing Quantization-Aware Training (QAT), showing how fake-quantization during gradient passes allows low-precision conversion without accuracy drops.
> * **On-Screen OCR:** WILL IT FIT? ; QAT: train with the rounding in the loop ; Quantization-aware training: High-precision weights -> Fake-quantize each pass -> Gradients adapt the weights -> Convert: real 4-bit file -> Serve on PTQ kernels ; Training: each linear layer rounds 3 weights and activations to target grid... backward pass is unchanged. ; The weights were chosen knowing they would be rounded. The file format didn't change.
> * **Structured Reconstruction:**
>   flowchart LR
>       A[High-precision weights] --> B[Fake-quantize each pass]
>       B --> C[Gradients adapt the weights]
>       C --> D[Convert: real 4-bit file]
>       D --> E[Serve on PTQ kernels]

**🎙️ Spoken Transcript:**
* **[16:30]** quantization aware training, which basically is making the model re-assess itself as it's training so that the most used layers are kept at higher precision...

💡 **Visual-Speech Alignment:** Connects QAT flow steps to rounding weights during gradient updates.

---

## [17:10 - 18:56] Scene #23: Fewer bits fit a smaller box. What do you lose?
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Accuracy breakdown of dynamic quantization recipes on DeepSeek V3.1 and GLM-5.3 across 3-bit, 2-bit, and 1-bit compression levels.
> * **On-Screen OCR:** WILL IT FIT? ; Fewer bits fit a smaller box. What do you lose? ; DeepSeek V3.1 (thinking) 671B: Baseline 76.1%, '3-bit' 75.6%, '1-bit' 57.8% ; GLM-5.3 753B: Full model 94.3%, '3-bit' 88.5%, '2-bit' 78.5%, '1-bit' 21.7% ; Here '3-bit' landed 0.5 points under baseline; '1-bit' lost 18.3 points (24%).
> * **Structured Reconstruction:**
>   ### Quantization Degradation Benchmark
>   | Model | Precision Level | Score / Accuracy | Performance Loss |
>   | :--- | :--- | :--- | :--- |
>   | **DeepSeek V3.1 (671B)** | Baseline | 76.1% | - |
>   | DeepSeek V3.1 | "3-bit" | 75.6% | -0.5 points |
>   | DeepSeek V3.1 | "1-bit" | 57.8% | -18.3 points |
>   | **GLM-5.3 (753B)** | Full Model | 94.3% | - |
>   | GLM-5.3 | "3-bit" | 88.5% | -5.8 points |
>   | GLM-5.3 | "2-bit" | 78.5% | -15.8 points |
>   | GLM-5.3 | "1-bit" | 21.7% | -72.6 points |

**🎙️ Spoken Transcript:**
* **[18:10]** how quantization have evolved, we're seeing that something like GLM 5.3 at four bit is able to recall about 94% of its accuracy, while a year ago DeepSeek 3.1 was only able to do 76.1...

💡 **Visual-Speech Alignment:** Points to the baseline vs 3-bit/1-bit numbers on the slide tables.

---

## [18:57 - 20:29] Scene #24: "Fast" at which part? / The bottleneck moves
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Diagram explaining how prompt length dictates system bottlenecks: Prefill phase is compute-bound, whereas Decode phase is memory-bandwidth bound.
> * **On-Screen OCR:** WILL IT BE FAST? ; "Fast" at which part? ; Two clocks, two measurements. Long prompt: Prefill (large block) vs Decode (small block). Short prompt: Prefill (small block) vs Decode (large block). ; Time to first token: queue + scheduling + prefill. ; Time per output token: decode, stalls included. ; Measure the user's wait and the system's throughput. Under load they move apart.
> * **Structured Reconstruction:**
>   flowchart TD
>       subgraph Long_Prompt [Long Prompt / Short Answer]
>           A1["PREFILL (Compute Bound - High TTFT)"] --> A2["DECODE (Memory Bandwidth Bound)"]
>       end
>       subgraph Short_Prompt [Short Prompt / Long Answer]
>           B1["PREFILL (Fast TTFT)"] --> B2["DECODE (Memory Bandwidth Bound - High Total Time)"]
>       end

**🎙️ Spoken Transcript:**
* **[19:05]** How many of you here know the difference between like decode and prefill? Okay, so prefill as we know it is compute bound. Decode is pretty much memory bandwidth bound.
* **[19:25]** If you have a long prompt... time to first token is going to take more.

💡 **Visual-Speech Alignment:** Refers to the red (prefill) and pink (decode) time bars.

---

## [20:30 - 21:30] Scene #25: Fewer bits: where the speed lands
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Speed comparison table showing how quantization and specialized kernels accelerate decode speeds on mobile and GPU hardware.
> * **On-Screen OCR:** WILL IT BE FAST? ; Fewer bits: where the speed lands ; iPhone (Phi-4-mini): PTQ -> QAT | 3.1 -> 2.2 GB | 14 -> 18 tok/s | XNNPACK + TorchAO ; iPhone (Phi-4-mini): 4-bit -> 2-bit | 1.4 -> 0.7 GB | 17 -> 28 tok/s | TorchAO low-bit kernels ; B200 (Gemma 3 27B): FP16 -> NVFP4 | 1.4 HBM | 1.35x | FP4 tensor cores ; Llama.cpp (Llama 3.1): 16 -> Q4_K_M | 15 -> 4.6 GB | 29 -> 72 tok/s | Unpack, then 16-bit math ; Same run, prefill: 16 -> Q4_K_M | same | 923 -> 822 tok/s | Same math, plus unpack
> * **Structured Reconstruction:**
>   | Platform / Model | Quant Switch | Memory Delta | Speed Delta | Kernel / Method |
>   | :--- | :--- | :--- | :--- | :--- |
>   | iPhone (Phi-4-mini) | PTQ -> QAT | 3.1 GB -> 2.2 GB | 14 -> **18 tok/s** | XNNPACK + TorchAO |
>   | iPhone (Phi-4-mini) | 4-bit -> 2-bit | 1.4 GB -> 0.7 GB | 17 -> **28 tok/s** | TorchAO low-bit |
>   | B200 (Gemma 3 27B) | FP16 -> NVFP4 | 1.4 HBM | **1.35x** | FP4 Tensor Cores |
>   | Llama.cpp (Llama 3.1) | 16 -> Q4_K_M | 15 GB -> 4.6 GB | 29 -> **72 tok/s** | Unpack + 16-bit math |
>   | Same run (Prefill) | 16 -> Q4_K_M | Same | 923 -> 822 tok/s | Same math + unpack overhead |

**🎙️ Spoken Transcript:**
* **[20:40]** right now an iPhone is basically more capable than running intelligence... than a model that used to require a data center three years ago.
* **[21:10]** one and two billion parameter models are going to be the norm.

💡 **Visual-Speech Alignment:** Highlights the iPhone speedup rows (14 to 18 tok/s and 17 to 28 tok/s).

---

## [21:31 - 22:25] Scene #26: Prefill wants compute. Decode wants bandwidth.
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Bar charts comparing 2x DGX Spark against Apple M5 Ultra Studio on DeepSeek V4 Flash, showing DGX Spark winning prefill by 2.4x while M5 Ultra is 6% faster in decode.
> * **On-Screen OCR:** WILL IT FIT / SERVE? ; Prefill wants compute. Decode wants bandwidth. ; DeepSeek V4 Flash (284B total, 13B active): ; Prefill (reading prompt): 2x DGX Spark 1,600 vs M5 Ultra Studio 748 (Sparks 2.4x faster) ; Decode (writing answer): 2x DGX Spark 35.8 vs M5 Ultra Studio 38.1 (Mac 6% faster)
> * **Structured Reconstruction:**
>   | System Hardware | Memory Bandwidth | Prefill Speed (tok/s) | Decode Speed (tok/s) |
>   | :--- | :--- | :--- | :--- |
>   | **2x DGX Spark** | ~273 GB/s per unit | **1,600** (2.4x faster) | 35.8 |
>   | **M5 Ultra Studio** | ~1.2 TB/s | 748 | **38.1** (6% faster) |

**🎙️ Spoken Transcript:**
* **[21:35]** The M5 Ultra is supposed to have something like 1.2 terabytes per second bandwidth... and the DGX Spark has 273 gigabytes per second.
* **[21:45]** For decoding, the Sparks still beat the M5 in prefill by 2.4x while Mac is only 6% faster in decode. Software optimizations matter.

💡 **Visual-Speech Alignment:** Gestures to the red/pink bar charts comparing DGX Spark and M5 Ultra Studio.

---

## [22:26 - 25:40] Scene #27: Same model, four memory systems / The race, live / The burst, live
> **[SCREEN INTERPRETATION | Type: `CODE_DEMO`]**
> * **Visual Summary:** Live video benchmark racing Qwen3.6-27B across four hardware platforms: Blackwell Tower (RTX PRO 6000), M5 MacBook Pro, DGX Spark, and Strix Halo under single and 50 parallel requests.
> * **On-Screen OCR:** WILL IT SERVE? ; Same model, four memory systems ; Blackwell tower (RTX PRO 6000): 96 GB GDDR7, ~1,792 GB/s, FP8 - vLLM ; M5 MacBook Pro (M5 Max): 128 GB unified, ~614 GB/s, Q4_K_M - llama.cpp ; DGX Spark (GB10): 128 GB unified, ~273 GB/s, Q4_K_M - llama.cpp ; Strix Halo (Ryzen AI Max+ 395): 128 GB unified, ~256 GB/s, Q4_K_M - llama.cpp ; Single request speed: Tower 51 tok/s, MacBook 23 tok/s, Strix Halo 13 tok/s, DGX Spark 11 tok/s ; 50 parallel requests (Burst): Blackwell Tower 1,291 tok/s total, others stay at ~23-32 tok/s
> * **Structured Reconstruction:**
>   ### 4-System Hardware Benchmark Race (Qwen3.6-27B)
>   | Hardware Platform | Memory & Bandwidth | Stack | 1 User (tok/s) | 50 Users Parallel (tok/s) |
>   | :--- | :--- | :--- | :--- | :--- |
>   | **Blackwell Tower (RTX PRO 6000)** | 96 GB GDDR7 (~1,792 GB/s) | FP8 - vLLM | **51** | **1,291** |
>   | **M5 MacBook Pro (M5 Max)** | 128 GB Unified (~614 GB/s) | Q4_K_M - llama.cpp | 23 | 31 |
>   | **Strix Halo (Ryzen AI Max+)** | 128 GB Unified (~256 GB/s) | Q4_K_M - llama.cpp | 13 | 30 |
>   | **DGX Spark (GB10)** | 128 GB Unified (~273 GB/s) | Q4_K_M - llama.cpp | 11 | 28 |

**🎙️ Spoken Transcript:**
* **[22:35]** We ran an RTX Pro 6000... M5 MacBook Pro, DGX Spark, and Strix Halo...
* **[23:05]** You can see the GPU beating all of them... 51 tokens per second...
* **[23:45]** 50 requests per machine at once. We're seeing that the RTX Pro 6000 becomes almost 1300 tokens per second while everything else is sequential...

💡 **Visual-Speech Alignment:** Direct alignment with live benchmark animation showing 1291 tok/s throughput on Blackwell Tower vs ~30 tok/s on CPU/Unified platforms under batching.

---

## [25:41 - 27:05] Scene #28: The engine families / Nine questions before you pick an engine
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Classification table of major inference engine families (llama.cpp, MLX, ExLlamaV3, vLLM/SGLang/TRT-LLM, NVIDIA Dynamo) detailing target hardware and supported quantization file formats.
> * **On-Screen OCR:** WILL IT SERVE? ; The engine families ; llama.cpp: Portable: any GPU or CPU, offline | Typical format: GGUF ; MLX / MLX-LM: Apple unified memory, Mac-first workflows | Typical format: MLX ; ExLlamaV3: Consumer CUDA quants on RTX boxes | Typical format: EXL3 ; vLLM / SGLang / TRT-LLM: Production: paged KV, batching | Typical format: FP8, NVFP4, AWQ ; NVIDIA Dynamo: Fleets: disaggregation, routing | Typical format: Engines below it
> * **Structured Reconstruction:**
>   | Engine Family | Best Built For | Typical Formats |
>   | :--- | :--- | :--- |
>   | **llama.cpp** | Portable: any GPU or CPU, offline | GGUF |
>   | **MLX / MLX-LM** | Apple unified memory, Mac-first workflows | MLX |
>   | **ExLlamaV3** | Consumer CUDA quants on RTX boxes | EXL3 |
>   | **vLLM / SGLang / TRT-LLM** | Production: paged KV, batching | FP8, NVFP4, AWQ |
>   | **NVIDIA Dynamo** | Fleets: disaggregation, routing | Engines below it |

**🎙️ Spoken Transcript:**
* **[25:55]** Different engines, different quantizations, different file formats... llama.cpp, vLLM, ExLlama...
* **[26:40]** Pick the hardware, workload shape and serving model first. The engine follows.

💡 **Visual-Speech Alignment:** References the table classifying LLM inference engines.

---

## [27:06 - 28:28] Scene #29: Same open weights, different host, different score
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Comparison table showing GLM-5.3 accuracy variation on GPQA Diamond depending on hosting provider hardware and inference backend (87.9% on DigitalOcean down to 81.5% on Tenstorrent).
> * **On-Screen OCR:** WILL IT SERVE? ; Same open weights, different host, different score ; GLM-5.3 on GPQA Diamond, OpenRouter hosts with 1,700+ graded answers each: ; DigitalOcean: 87.9% GPQA Diamond | 1,914 host score | 28.0K output tokens ; Z.ai (maker): 87.0% | 2,172 | 29.0K ; Wafer: 87.0% | 4,450 | 61.3K ; Morph: 82.9% | 2,733 | 29.0K ; Tenstorrent: 81.5% | 1,723 | 16.9K ; Six points between hosts of one model. Measure the endpoint, not the name.
> * **Structured Reconstruction:**
>   | Host / Provider | GPQA Diamond Score | Graded Answers | Output Tokens per Task |
>   | :--- | :--- | :--- | :--- |
>   | **DigitalOcean** | **87.9%** | 1,914 | 28.0K |
>   | Z.ai (model maker) | 87.0% | 2,172 | 29.0K |
>   | Wafer | 87.0% | 4,450 | 61.3K |
>   | Morph | 82.9% | 2,733 | 29.0K |
>   | **Tenstorrent** | **81.5%** | 1,723 | 16.9K |

**🎙️ Spoken Transcript:**
* **[27:15]** This is from OpenRouter and it's basically showing benchmarks of GLM 5.3 on different hardware.
* **[27:30]** At the bottom we have Tenstorrent down there... chip or model optimization is different from one platform to the next.

💡 **Visual-Speech Alignment:** Connects score variance (87.9% to 81.5%) on the same model to host hardware differences.

---

## [28:29 - 29:26] Scene #30: A 100x faster tokenizer bought 11%
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Mathematical formula slide illustrating Amdahl's Law in LLM serving: a 100x speedup in tokenization (which takes 10% of total time) yields only an 11% end-to-end request speedup.
> * **On-Screen OCR:** WILL IT SERVE? ; A 100x faster tokenizer bought 11% ; Suppose tokenization is 10% of request time: ; Component: Tokenizer 100x faster | Everything else unchanged ; Whole request: 1 + (0.90 + 0.10 / 100) = 1.11x faster ; Profile the request before you buy the headline. ; Actual Inc., 'Introducing tok6,' Oct 6, 2026
> * **Structured Reconstruction:**
>   $$\text{Total Time} = T_{\text{compute}} + T_{\text{tokenizer}}$$
>   $$\text{If } T_{\text{tokenizer}} = 0.10 \times T_{\text{total}}, \text{ then } 100\times \text{ tokenizer speedup} \implies 1 + (0.90 + 0.001) = 0.901 \text{ relative time}$$
>   $$\text{Overall Speedup} = \frac{1}{0.901} \approx 1.11\times \text{ (11\% gain)}$$

**🎙️ Spoken Transcript:**
* **[28:30]** This is a very interesting one... came out just last month from a company called Actual Inc. And they built a Rust tokenizer that was 100 times faster.
* **[28:50]** But that 100 times faster when it came to the whole request, it made it 1.1% faster.

💡 **Visual-Speech Alignment:** Points to the equation formula demonstrating Amdahl's Law in LLM pipelines.

---

## [29:27 - 32:13] Scene #31: DFlash: draft a block in one pass, verify in one / FlashStates: a state exactly where each turn ends
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Diagram detailing FlashData / FlashStates scheduling optimization, showing state preservation exactly at turn boundaries to eliminate KV cache re-computation penalties.
> * **On-Screen OCR:** THREE LEVERS ; Where the state was saved decides what you redo ; vLLM today: A state at each 4,352-token block boundary, never at a turn's end ; FlashStates: A state exactly where each turn ends (prompt blocks, output blocks, state saved, turn ends) ; FlashStates on three hybrid models: GLM-5.3-Flash (3.14x prefix tok/min, -96% p50 TTFT), Nemotron 3 Super (2.27x, -97%), Qwen3.8-Flash-Next (1.54x, -66%) ; The gap between the last saved state and the turn's end is prefill you pay again.
> * **Structured Reconstruction:**
>   flowchart TD
>       subgraph vLLM_Standard [vLLM Standard - Block Boundary]
>           A1[Prompt Blocks] --> A2[Output Blocks] --> A3["Fixed Block Save (4352 tok)"]
>           A3 --> A4["Turn Ends (Unsaved State Re-computed!)"]
>       end
>       subgraph FlashStates [FlashStates Optimization]
>           B1[Prompt Blocks] --> B2[Output Blocks] --> B3["Exact State Saved at Turn End"]
>           B3 --> B4["Zero Re-computation Penalty"]
>       end

**🎙️ Spoken Transcript:**
* **[30:00]** This paper came out November 9th... called Flash Data.
* **[30:30]** What they are doing is basically saving where each turn ends... leading to prefix tokens per minute being almost trebled.
* **[30:50]** On GLM-5.3 Flash it's 3.14x performance gain.

💡 **Visual-Speech Alignment:** Connects diagram comparing vLLM block saves vs FlashStates turn-end saves to performance gains table.

---

## [32:14 - 34:50] Scene #32: The local agent couldn't change a GPU's lights
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Scenario slide describing an offline local agent failure when trying to control RTX 5090 RGB lights, highlighting the necessity of web search tool augmentation.
> * **On-Screen OCR:** THE CATCH ; The local agent couldn't change a GPU's lights ; A new 5090, Qwen 3.5 27B (27.8B dense), Claude Code: 'change my RGB colors.' ; A bigger model? A bigger GPU? More context? A search engine? ; Result: It failed. You get one change. What do you try first? ; Hands up for each one. Then we'll see what actually fixed it. ; Build a $5,000 AI Datacenter at Home - youtube video reference
> * **Structured Reconstruction:**
>   ### Debugging Challenge: Offline Agent Failure
>   - **Setup**: RTX 5090 GPU + Qwen 3.5 27B local model + Claude Code harness
>   - **Task**: "Change my GPU fan RGB lights"
>   - **Initial Result**: **FAILED** (Missing training knowledge for hardware released post-cutoff)
>   - **Fix**: **Provide Search Engine Tool Access** (Agent retrieves dynamic specs & scripts)

**🎙️ Spoken Transcript:**
* **[33:00]** A friend bought a 5090 after Qwen 3.5 27B came out and he tried to change the color of the RGB on the GPU fans... and it wasn't able to do that.
* **[33:30]** I asked him: Did you give it a search engine?... Cloud Code comes with a search engine... so it's able to go look on the internet.
* **[33:50]** I gave him an API key... asked the same thing with a search engine. Surprise, it was able to change the RGB colors.

💡 **Visual-Speech Alignment:** Speaker walks through options A-D on the slide, revealing 'A search engine' as the actual fix.

---

## [34:51 - 36:13] Scene #33: The agent rewrote its own harness
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Architecture slide showing the Exo agent runtime, where the agent modifies its contextual harness code while keeping model weights and run history immutable.
> * **On-Screen OCR:** THE CATCH ; The agent rewrote its own harness ; Exo, a research agent runtime: the agent edits the code around the model, never the weights. ; The agent may edit: The harness (tools, prompts, context rules and memory around model) ; Out of its reach: The run history (append-only), previous versions for rollback ; On held-out work: 35-61% lower model cost on repeated tasks; parallel correctness ; Decisions it kept repeating became code. Novel work still needs fresh reasoning.
> * **Structured Reconstruction:**
>   flowchart LR
>       subgraph Agent_Controlled [Agent Editable Zone]
>           A[Tools & Prompts]
>           B[Context Rules]
>           C[Memory Harness]
>       end
>       subgraph Immutable_Zone [Out of Reach]
>           D[Run History / Append-only]
>           E[Model Weights]
>           F[Guardian Check / Guardrails]
>       end
>       Agent_Controlled --> F --> Immutable_Zone

**🎙️ Spoken Transcript:**
* **[35:15]** XO is a paper about an engine harness that we wrote itself to actually improve its own reuse...
* **[35:35]** decisions it kept repeating became code, saving tokens in the long run.

💡 **Visual-Speech Alignment:** References the diagram illustrating self-modifying agent harnesses.

---

## [36:14 - 37:00] Scene #34: Hard work switches models. Tuned work stays pinned.
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** OpenRouter telemetry chart showing developer behavior: hard coding tasks actively switch models (53%), whereas routine workflows stay pinned to legacy models.
> * **On-Screen OCR:** THE CATCH ; Hard work switches models. Tuned work stays pinned. ; OpenRouter: who switches models each month, and who stays on an older version: ; Accounts changing top model: General coding 53%, Customer support 30%, Summarization 27%, Translation 24% ; Requests still on an older version: Grok 70%, Gemini Flash 60%, GPT Sol 54%, Claude Opus 20% ; Pinning is a decision. Make it with an eval, and know what it costs.
> * **Structured Reconstruction:**
>   | Workload Category | Switching Rate (Top Model) | Pinned Model Distribution |
>   | :--- | :--- | :--- |
>   | **General Coding** | **53%** (High churn) | Grok (70% pinned) |
>   | **Customer Support** | 30% | Gemini Flash (60% pinned) |
>   | **Summarization** | 27% | GPT Sol (54% pinned) |
>   | **Translation** | 24% (Low churn) | Claude Opus (20% pinned) |

**🎙️ Spoken Transcript:**
* **[36:15]** Which accounts changed their models on OpenRouter? We're seeing generic coding does that more about 53%...
* **[36:45]** DeepSeek V4.1 Flash is better than Haiku... people should be fine with switching models as newer models come out.

💡 **Visual-Speech Alignment:** Speaker links switching statistics to developer tendencies to stick to closed models vs testing open releases.

---

## [37:01 - 38:24] Scene #35: A 2B model matched the frontier on Airbnb's job
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Case study from Airbnb showing a fine-tuned 2.3B Gemma4-E2B model running locally on an RTX PRO 6000 matching frontier cloud API quality at 35 ms latency and 1% cost.
> * **On-Screen OCR:** THE MONEY ; A 2B model matched the frontier on Airbnb's job ; A pricing-policy classifier with a 200 ms budget, on 10,000 held-out examples. ; Gemma4-E2B (2.3B dense), fine-tuned: F1 0.563 -> 0.902 | 35 ms median | 85 ms p99 | One RTX PRO 6000 ; Frontier APIs (parameters undisclosed): Similar quality | ~900 ms median | Seconds at p99 ; On this task, fine-tuning met the quality bar inside a 200 ms budget. ; Airbnb Engineering, 'Frontier quality at 1% of the cost,' Nov 2026
> * **Structured Reconstruction:**
>   | Model Setup | F1 Score | Median Latency | p99 Latency | Hardware / Cost |
>   | :--- | :--- | :--- | :--- | :--- |
>   | **Gemma4-E2B (2.3B Fine-tuned)** | **0.902** | **35 ms** | **85 ms** | 1x RTX PRO 6000 (1% cost) |
>   | **Frontier Cloud APIs** | ~0.900 | ~900 ms | >2,000 ms | Cloud API billing (100x cost) |

**🎙️ Spoken Transcript:**
* **[37:05]** Airbnb had an article about how at 1% of the cost, they had the Frontier Intelligence Quality on a 2 billion parameter model.
* **[37:45]** If you have some data traces... you can build synthetic data pipelines and RL to beat frontier labs.

💡 **Visual-Speech Alignment:** Direct callout to the Gemma4-E2B vs Frontier APIs latency and accuracy table.

---

## [38:25 - 39:30] Scene #36: Specialization doesn't require owning the GPU
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide detailing Fireworks Ember-1 (specialized Kimi K3 2.8T) distillation claims and evaluation criteria.
> * **On-Screen OCR:** THE MONEY ; Specialization doesn't require owning the GPU ; Fireworks specialized Kimi K3 (2.8T total, 104B active) and serves it behind an API. ; Their claim: Ember-1, built on Kimi K3, ~40% fewer reasoning tokens, comparable quality on evals ; Your test: Hard-case error rate, Retries and total task cost, Time to an answered answer ; Specialization and placement are separate choices.
> * **Structured Reconstruction:**
>   - **Fireworks Claim (Ember-1 / Kimi K3)**: 40% reduction in reasoning tokens with equal eval accuracy.
>   - **Verification Metrics**: Hard-case error rates, retry costs, total task time.

**🎙️ Spoken Transcript:**
* **[38:30]** There are labs out there like Fireworks that are building specialized models and hosting them...
* **[38:45]** How do we think Opus 5.5 was trained? It's a master-student model...

💡 **Visual-Speech Alignment:** Connects model distillation concepts to Fireworks Ember-1 specification on screen.

---

## [39:31 - 41:20] Scene #37: Utilization sets what a token costs on your GPU / The hosted price you compete with keeps falling
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Economic analysis charts demonstrating how GPU utilization impacts per-token cost ($43.03/M at 1% vs $0.43/M at 10%), alongside hosted API price drops.
> * **On-Screen OCR:** THE MONEY ; Utilization sets what a token costs on your GPU ; Output $/million - $2/GPU-hour assumed - 1,291 tok/s burst rate - illustrative GPU floor ; 1% busy: $43.03 | 10% busy: $0.43 | GPU floor ($0.40) vs Opus 5.5 ($20/M) ; Below $1/M: GPU at 100% busy vs a cheap API | DeepSeek Flash off-peak ($0.60) ; Same GPU. Same model. Utilization moves the cost 100x. ; The hosted price you compete with keeps falling: Closed fell 57% and open 70% in ten months.
> * **Structured Reconstruction:**
>   | Utilization Level | Cost per Million Tokens | Comparative Benchmark |
>   | :--- | :--- | :--- |
>   | **1% Duty Cycle (Idle GPU)** | **$43.03** | Higher than Opus 5.5 ($20/M) |
>   | **10% Duty Cycle** | **$0.43** | Below GPU Floor ($0.40) |
>   | **100% Duty Cycle** | **~$0.04** | 100x cheaper than cloud APIs |

**🎙️ Spoken Transcript:**
* **[39:35]** There's a certain threshold for which below that, you shouldn't buy a GPU, you should be renting...
* **[40:40]** Prices per million tokens keep dropping... closed fell 57% and open 70% in ten months.

💡 **Visual-Speech Alignment:** Gestures to the utilization curve showing cost dropping from $43.03 to $0.43 as utilization rises.

---

## [41:21 - 42:15] Scene #38: Price doesn't track quality
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** LM Arena WebDev pricing vs quality table showing Opus 5.5 max ($8.00/M) beating GPT-6 Astra ($20.00/M), while DeepSeek V4.1 Flash ($0.26/M) delivers 30x cost savings.
> * **On-Screen OCR:** THE MONEY ; Price doesn't track quality ; LM Arena WebDev, human voters, Nov 8 - blended $/per million tokens (3 input : 1 output): ; Opus 5.5 max: WebDev score 1818 (+12) | Blended $8.00 ; Sonnet 5.5 xhigh: WebDev score 1774 (+10) | Blended $4.00 ; GPT-6 Astra max: WebDev score 1787 (+9) | Blended $20.00 ; Kimi K3.1 Pro max (open - 2.8T / 104B active): WebDev score 1688 (+10) | Blended $4.00 ; DeepSeek V4.1 Flash-1017 (open - 748B / 816B): WebDev score 1664 (+7) | Blended $0.26 ; The priciest model isn't the best. The cheapest is 30x cheaper. Price your own job.
> * **Structured Reconstruction:**
>   | Model | WebDev Score | Blended Cost per M Tokens | Price-to-Performance Ratio |
>   | :--- | :--- | :--- | :--- |
>   | **Opus 5.5 max** | **1818** | $8.00 | Top score / Moderate cost |
>   | **GPT-6 Astra max** | 1787 | **$20.00** | High cost / Lower score than Opus |
>   | **Sonnet 5.5 xhigh** | 1774 | $4.00 | Mid cost / Strong performance |
>   | **DeepSeek V4.1 Flash** | 1664 | **$0.26** | **30x cheaper than Opus** |

**🎙️ Spoken Transcript:**
* **[41:30]** Pricing per million token doesn't track intelligence necessarily... Opus 5.5 max at $8 per million token is beating in WebDev...
* **[41:50]** It's way cheaper than something like Astra, but Astra is probably 6 to 10 times bigger in terms of size.

💡 **Visual-Speech Alignment:** Points to Opus 5.5 (1818 score, $8/M) vs GPT-6 Astra (1787 score, $20/M).

---

## [42:16 - 44:20] Scene #39: A GPU costs the same busy or idle / What breaks when you own it
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Financial crossover chart comparing hourly GPU rental vs API token billing, followed by operational risks when owning physical hardware.
> * **On-Screen OCR:** THE MONEY / OWNING IT ; A GPU costs the same busy or idle ; Cloud GPU at $2/hr = $1,460/mo. Breakdown by API output price: ; Claude Opus 5.5 (undisclosed): $1,460 + $20 = 73M tokens | Break-even total: 3% ; DeepSeek V4.1 Flash (748B): $1,460 + $0.60 = 2,433M tokens | Break-even total: 72% ; Qwen3.6-27B (27B dense): None ($2/hr) | Break-even total: 100% ; What breaks when you own it: Startup and drivers, Dependencies, Silent failures (script printed DONE after FFmpeg died). ; Check the artifact, not the status message.
> * **Structured Reconstruction:**
>   ### GPU Crossover Math ($2/hr GPU = $1,460/mo)
>   | Target Model Comparison | API Output Price | Break-even Token Volume | Required Box Utilization |
>   | :--- | :--- | :--- | :--- |
>   | **Claude Opus 5.5** | $20.00 / M | 73M tokens | **3% busy** |
>   | **DeepSeek V4.1 Flash** | $0.60 / M | 2,433M tokens | **72% busy** |
>   | **Qwen3.6-27B Local** | $0.00 (Self-hosted) | 3,393M tokens | **100% busy** |

**🎙️ Spoken Transcript:**
* **[42:20]** APIs bill per token. GPUs bill per hour... under 15-30 requests per minute API is cheaper.
* **[43:30]** There's a lot of maintenance that goes into owning hardware... silent failures, hardware that dies on you...
* **[44:00]** Check the artifact, not the status message.

💡 **Visual-Speech Alignment:** Connects the 3% vs 72% utilization break-even math to hardware maintenance trade-offs.

---

## [44:21 - 45:45] Scene #40: Three forces move the line / Three years of the same capability in less hardware
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Historical timeline table mapping model compression from 2023 to 2026, demonstrating how equivalent intelligence continuously shifts onto smaller hardware footprint.
> * **On-Screen OCR:** THE LINE MOVES ; Three years of the same capability in less hardware ; Newer, more efficient models keep matching or beating bigger predecessors: ; 2023: Llama 2 70B -> Mixtral 12.9B active (Comparable on Mistral's tests) ; 2024: Llama 3.1 405B dense -> Qwen2.5 72B dense (Comparable on Qwen's tests) ; 2025: R1 37B active -> gpt-oss 31B active (GPQA 81.0 vs 80.1) ; 2026 (Jan): Qwen3.5 397B total -> Qwen3.6 27B dense (SWE Verified 76.2 vs 77.2) ; 2026 (Apr): V4 Pro 1.6T total -> V4.1 748B incl. Engram (14/16 ahead, 4 weeks later) ; 2026 (Oct): 375B / 501B MOEs -> Nanbeige4.3 33B (AA v5: 18 vs 20) ; The capability keeps moving onto smaller hardware.
> * **Structured Reconstruction:**
>   | Year | Earlier (Bigger) Model | Later (Smaller) Model | Benchmark / Evidence |
>   | :--- | :--- | :--- | :--- |
>   | **2023** | Llama 2 70B | Mixtral 12.9B active | Equal performance on Mistral suite |
>   | **2024** | Llama 3.1 405B dense | Qwen2.5 72B dense | Equal performance on Qwen suite |
>   | **2025** | R1 37B active | gpt-oss 31B active | GPQA 81.0 vs 80.1 |
>   | **2026 (Jan)**| Qwen3.5 397B total | **Qwen3.6 27B dense** | **SWE Verified 76.2 vs 77.2** |
>   | **2026 (Apr)**| V4 Pro 1.6T total | V4.1 748B + Engram | 14 of 16 tests ahead |
>   | **2026 (Oct)**| 375B/501B MOEs | Nanbeige4.3 33B | AA v5: 18 vs 20 |

**🎙️ Spoken Transcript:**
* **[44:25]** Three forces moving the line: more capable models per parameter... specialist models... better engines.
* **[45:00]** The same machine I had behind me in that picture... in 2023 ran Llama 2 70B. Today each GPU runs Qwen 3.6 27B.

💡 **Visual-Speech Alignment:** Traces the historical progression table from 2023 Llama 2 70B to 2026 small dense models.

---

## [45:46 - 46:45] Scene #41: Same lab, 15x fewer parameters, the same band
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Benchmark comparison table showing Qwen3.6-27B (dense) beating Qwen3.5-397B (MOE) across coding benchmarks (SWE-bench Verified 77.2 vs 76.2).
> * **On-Screen OCR:** THE LINE MOVES ; Same lab, 15x fewer parameters, the same band ; Qwen3.5-397B-A17B (17B active) vs Qwen3.6-27B dense, Qwen's own results: ; SWE-bench Verified: 397B MOE 76.2 vs 27B dense 77.2 ; SWE-bench Pro: 397B MOE 50.9 vs 27B dense 53.5 ; Terminal-Bench 2.0: 397B MOE 52.5 vs 27B dense 59.3 ; LiveCodeBench v6: 397B MOE 83.6 vs 27B dense 83.9 ; MMLU-Pro: 397B MOE 87.8 vs 27B dense 86.2 ; GPQA Diamond: 397B MOE 88.4 vs 27B dense 87.8 ; Ahead on four coding tests, behind on two knowledge tests. 27B active against 17B.
> * **Structured Reconstruction:**
>   | Benchmark Test | Qwen3.5-397B-A17B (MOE, 17B active) | Qwen3.6-27B (Dense, 27B active) | Winner |
>   | :--- | :--- | :--- | :--- |
>   | **SWE-bench Verified** | 76.2 | **77.2** | 27B Dense |
>   | **SWE-bench Pro** | 50.9 | **53.5** | 27B Dense |
>   | **Terminal-Bench 2.0** | 52.5 | **59.3** | 27B Dense |
>   | **LiveCodeBench v6** | 83.6 | **83.9** | 27B Dense |
>   | **MMLU-Pro** | **87.8** | 86.2 | 397B MOE |
>   | **GPQA Diamond** | **88.4** | 87.8 | 397B MOE |

**🎙️ Spoken Transcript:**
* **[45:50]** In March we had the 397 billion MOE come out... and a month later the 3.6 27B dense model was beating the 15 times larger MOE on coding tasks.
* **[46:30]** Intelligence density is increasing rapidly.

💡 **Visual-Speech Alignment:** Points to coding benchmark rows (SWE-bench, Terminal-Bench) where 27B dense beats 397B MOE.

---

## [46:46 - 48:10] Scene #42: DeepSeek's global KV cache shrank 437x
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Timeline table highlighting a 437x compression reduction in DeepSeek KV cache memory footprint from DeepSeek V1 (12.8 GB) down to V4.1 Flash (29 MB).
> * **On-Screen OCR:** THE LINE MOVES ; DeepSeek's global KV cache shrank 437x ; DeepSeek-reported global KV at 32K tokens per user. Weights and workspace are extra. ; DeepSeek V1 (Nov 2023): 12.8 GB (369,120 B/token) ; V3.2 (Dec 2025): 1.6 GB (48,068 B/token) ; V4 Flash (Apr 2026): 115 MB (3,514 B/token) ; V4.1 Flash (Sep 2026): 29 MB (890 B/token) ; Our plain GQA example earlier: 4.3 GB per user at 32K, in decimal units. ; Recompute the full memory budget for each architecture.
> * **Structured Reconstruction:**
>   | Architecture Version | Release Date | KV Cache per User (32K Context) | Bytes / Token | Compression Factor |
>   | :--- | :--- | :--- | :--- | :--- |
>   | **DeepSeek V1** | Nov 2023 | 12.8 GB | 369,120 B | Baseline (1x) |
>   | **DeepSeek V3.2** | Dec 2025 | 1.6 GB | 48,068 B | ~8x reduction |
>   | **DeepSeek V4 Flash** | Apr 2026 | 115 MB | 3,514 B | ~111x reduction |
>   | **DeepSeek V4.1 Flash**| Sep 2026 | **29 MB** | **890 B** | **437x reduction** |

**🎙️ Spoken Transcript:**
* **[46:55]** DeepSeek V4.1 Flash... made us go down from 13 gigabytes for 400,000 tokens to 29 megabytes in terms of memory.
* **[47:30]** Pretty much trunked that KV cache by 437 times.

💡 **Visual-Speech Alignment:** Connects the 12.8 GB -> 29 MB timeline nodes on screen to the 437x compression ratio.

---

## [48:11 - 50:30] Scene #43: The infrastructure I asked for in June is arriving / A megakernel: one launch, an interpreter per SM
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Architectural diagram of Megakernel inference optimization running on RTX Spark at 72 tok/s decode, showing persistent single-launch execution per Streaming Multiprocessor.
> * **On-Screen OCR:** THE LINE MOVES ; The infrastructure I asked for in June is arriving ; Software changes only. The silicon under each result stayed the same: ; Measured elsewhere: dSpark +60-85% speed per user, DistServe 7.4x more requests in SLO ; Ours: ODS on RTX Spark - Qwen3.8 Flash Next (125B, 6B active, NVFP4) - 72 tok/s decode on our own engine ; A megakernel: Hazy Research's Llama-3.2-1B (1.2B dense), May 2025: ; 78% of H100 bandwidth at batch one, against about 50% for vLLM and SGLang.
> * **Structured Reconstruction:**
>   flowchart TD
>       subgraph Megakernel_Design [Megakernel - Interpreter per SM]
>           A[One Forward Pass = One Persistent Kernel] --> B[Global Counters Replace Barriers]
>           B --> C[Prefetch Across Boundary / Shared Memory Paged]
>       end
>       subgraph Performance_Impact [Performance Gain]
>           D["78% H100 Bandwidth at Batch 1 vs 50% in vLLM/SGLang"]
>       end
>       Megakernel_Design --> Performance_Impact

**🎙️ Spoken Transcript:**
* **[49:40]** We got a Windows machine with the RTX Spark running Qwen 3.8 Flash Next... at decode speed 72 tokens per second.
* **[50:10]** Megakernel: part of the optimization... 78% of H100 bandwidth at batch one.

💡 **Visual-Speech Alignment:** Speaker connects dSpark and ODS megakernel optimizations to hardware throughput gains.

---

## [50:31 - 51:54] Scene #44: In January I put a date on local capability
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide showing the speaker's original prediction tweet from Jan 16, 2026 regarding Opus 4.5 level quality running locally on a single RTX PRO 6000 before year-end.
> * **On-Screen OCR:** WHAT'S NEXT ; In January I put a date on local capability ; @TheAhmadOsman tweet (Jan 16, 2026): 'Prediction: We will have Claude Code + Opus 4.5 quality (not nerfed) models running locally at home on a single RTX PRO 6000 before the end of the year.' ; A capability, a card and a deadline: specific enough to check.
> * **Structured Reconstruction:**
>   > **@TheAhmadOsman (Jan 16, 2026)**
>   > **Prediction**: We will have Claude Code + Opus 4.5 quality (not nerfed) models running locally at home on a single RTX PRO 6000 before the end of the year.

**🎙️ Spoken Transcript:**
* **[50:45]** In January, I said that by the end of the year we're going to have Opus 4.5 running on an RTX Pro 6000.
* **[50:55]** By April we had that in Qwen 3.6 27B. We already surpassed Opus 4.5 level locally a long time ago.

💡 **Visual-Speech Alignment:** Direct reference to the author's January 2026 prediction tweet displayed on screen.

---

## [51:55 - 53:39] Scene #45: Engrams + decision models + in-weights edits
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Architectural diagram outlining the three-pillar recipe for local continual learning: Engram memory, Decision models, and In-weights programming.
> * **On-Screen OCR:** WHAT'S NEXT ; Engrams + decision models + in-weights edits ; Three research pieces. One bet: a small local model that keeps learning your job. ; Engram memory: Write a fact into memory embeddings. The backbone stays frozen. ; Decision models: Return a decision, not prose. Thresholds you can test. ; In-weights edits: A big model edits a small model's weights. The loop fix you saw: a repair, not a new skill. ; Engrams + Decision Models + In-weights programming == Continual Learning ; Tweet on Nov 4, 2026 by @TheAhmadOsman
> * **Structured Reconstruction:**
>   flowchart LR
>       A[Engram Memory: Fact into Embeddings] --> D[Continual Learning Engine]
>       B[Decision Models: Testable Thresholds] --> D
>       C[In-weights Edits: Weight Repairs] --> D
>       D --> E[Small Local Model Adapts Without Full Retraining]

**🎙️ Spoken Transcript:**
* **[52:25]** Engrams, decision models and weight edits. These are the last three big things that came out in this space for me.
* **[52:40]** Anagrams allows you to have an equivalent of a map on your SSD or in memory... decision models add another layer... plus in-weight edits.
* **[53:05]** Engrams + Decision Models + In-weight programming equal Continual Learning.

💡 **Visual-Speech Alignment:** Explains the three pillars (Engrams, Decision models, In-weight edits) leading to the red summary formula at the bottom of the slide.

---

## [53:40 - 54:53] Scene #46: Which loop are we talking about? / If it learns, every lesson is a release
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** System diagram categorizing AI execution loops (Inside model, Around model, Across experiments) and illustrating continuous learning release management (Log -> Curate -> Adapt -> Gate -> Promote).
> * **On-Screen OCR:** WHAT'S NEXT ; Which loop are we talking about? ; Inside the model: A model trained to run its own layers again (more depth, same weights). ; Around the model: Tools, retries, planning, more agents (same model, more calls). ; Across experiments: Change code or weights, evaluate, keep or reject (the compiler agents did this to an engine). ; All three spend compute. Only the third keeps what it learned. ; If it learns, every lesson is a release: Log -> Curate -> Adapt -> Gate -> Promote
> * **Structured Reconstruction:**
>   flowchart LR
>       A[Log: Outcomes Graded] --> B[Curate: Label & Dedupe]
>       B --> C[Adapt: Shallowest Fix First]
>       C --> D["Gate: Hold-out + Regression"]
>       D --> E[Promote: Versioned & Reversible]

**🎙️ Spoken Transcript:**
* **[54:05]** We have loops inside models, loops around models, loops across experiments.
* **[54:35]** If it learns, every lesson is a release: Log, Curate, Adapt, Gate, Promote. Give it a version, a gate and a way back.

💡 **Visual-Speech Alignment:** Connects the 3 loop definitions to the release pipeline lifecycle diagram.

---

## [54:54 - 56:08] Scene #47: So... should you buy a GPU? / Go deeper
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Final presentation slide providing GPU purchasing advice, resource links (thelocalaibook.com), author contact details, and conference closing screen.
> * **On-Screen OCR:** YOUR TURN / THANK YOU ; So... should you buy a GPU? Yes. For a job it can do today. ; Go deeper: The recording, the math, the book, and the primary sources behind today's numbers. ; The Local Book: thelocalaibook.com ; @TheAhmadOsman - find me after, bring your workload. ; AI Engineer Code Summit - https://ai.engineer
> * **Structured Reconstruction:**
>   # Conclusion & Resources
>   - **Verdict**: Should you buy a GPU? **Yes, for a job it can do today.**
>   - **Book**: [thelocalaibook.com](https://thelocalaibook.com)
>   - **Speaker**: Ahmad Osman (@TheAhmadOsman)
>   - **Conference**: AI Engineer Code Summit

**🎙️ Spoken Transcript:**
* **[55:25]** Should you buy a GPU?... Good question. You tell me.
* **[55:35]** By the way, there's a book coming out that will include a lot of this stuff: localaibook.com.
* **[55:45]** I have 9 seconds left. Thank you so much.

💡 **Visual-Speech Alignment:** Final callouts to the QR/link for the book and social handle on the concluding slide.

---
