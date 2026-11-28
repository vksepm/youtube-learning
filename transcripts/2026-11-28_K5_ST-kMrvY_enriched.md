# Enriched Interleaved Transcript: Stop Paying LLM Prices for Yes-or-No Answers — Chinmay Goyal, Glean
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=K5_ST-kMrvY
**Model:** `gemini-4-hydrogen` | **Processing Mode:** `agentic`

---

## [00:00 - 00:11] Scene #1: AI Engineer Code Summit
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Opening conference bumper sequence on a black background displaying the AI Engineer Code Summit title card, presenter attribution (Google DeepMind), and Platinum Sponsors logo grid.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; PLATINUM SPONSORS ; aws ; Devin ; databricks ; exa ; FACTORY ; Sonar

**🎙️ Spoken Transcript:**

💡 **Visual-Speech Alignment:** Conference intro and sponsor bumper preceding the speaker's entrance.

---

## [00:12 - 00:26] Scene #2: AI Engineer Code Summit Stage (Speaker Introduction)
> **[SCREEN INTERPRETATION | Type: `SPEAKER_ONLY`]**
> * **Visual Summary:** Chinmay Goyal walks onto the AI Engineer Code Summit stage in front of a dark sponsor-branded backdrop and stands behind the podium holding a slide clicker while introducing himself and the talk.
> * **On-Screen OCR:** AI Engineer Code Summit ; PRESENTED BY Google DeepMind ; databricks ; exa ; OVERCUT ; Devin ; Firecrawl ; Sonar ; Vercel ; Parasail ; DATADOG

**🎙️ Spoken Transcript:**
* **[00:13]** Hi everyone. My name is Chinmay and I'm a software engineer at Glean. I work on the product engineering side of Glean Assistant.
* **[00:22]** Today I'm going to give a talk on how Glean uses Jev. The title of the talk is Beyond Generation, fast and structured AI decisions with Jev at Glean.

💡 **Visual-Speech Alignment:** Camera stays on the speaker on stage until he switches to the title slide at 00:27.

---

## [00:27 - 00:31] Scene #3: Beyond Generation: Fast, structured AI decisions with Jev at Glean
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Blue title slide displayed in a browser window within the conference presentation layout (left-hand speaker PIP, event branding, and lower-third banner) showing the talk title, subtitle, and speaker details.
> * **On-Screen OCR:** glean ; AIE Code Summit ; Beyond Generation ; Fast, structured AI decisions with Jev at Glean ; Chinmay Goyal ; Software Engineer, Glean ; © 2026 Glean Technologies, Inc.

**🎙️ Spoken Transcript:**
* **[00:27]** (Completes talk title introduction as the title slide appears and transitions to Slide 2.)

💡 **Visual-Speech Alignment:** Title slide appears right as Chinmay announces the talk title before advancing to the main content.

---

## [00:32 - 01:05] Scene #4: Most AI product steps are bounded decisions, not generation
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Slide 2 presenting five numbered horizontal cards (01 through 05) representing common bounded AI product decisions, each labeled with a yellow primitive badge (CHOICE, NOLI, or NOLI + SCORE), over a blue takeaway banner at the bottom.
> * **On-Screen OCR:** Most AI product steps are bounded decisions, not generation ; 01 Understand the request — Which task is the user asking for? [CHOICE] ; 02 Pick the suggestion — Which next step to show, or none? [CHOICE] ; 03 Check citations — Does this source support this claim? [NOLI] ; 04 Route tool or model — Which expert should handle this turn? [CHOICE] ; 05 Apply a guardrail — Is this risky? How severe? [NOLI + SCORE] ; The output can be listed in advance, yet we often pay full LLM latency and cost to pick it.

**🎙️ Spoken Transcript:**
* **[00:32]** If you look at it, most AI product steps are bounded decisions and not generation problems.
* **[00:38]** So to give a couple of examples, user query intent classification, a ranker picking a suggestion out of N options, checking whether a citation is valid or not, routing to the correct model or expert, so on so forth.
* **[00:56]** Till now, we have been paying the full LLM cost and latency to get an answer to all these bounded problems.

💡 **Visual-Speech Alignment:** Speaker enumerates cards 01 through 04 left-to-right ('query intent classification', 'ranker picking a suggestion', 'checking whether a citation is valid', 'routing to the correct model or expert') and concludes by reading the theme of the bottom blue banner.

---

## [01:06 - 02:03] Scene #5: Jev fills the gap between general LLMs and fine-tuned classifiers
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 4 displaying a four-column comparison matrix contrasting General-purpose LLM, Open zero-shot classifier, Fine-tuned classifier, and Jev (highlighted in solid blue on the right), with 'WHY USE IT' and 'TRADEOFF' rows for each.
> * **On-Screen OCR:** Jev fills the gap between general LLMs and fine-tuned classifiers ; General-purpose LLM | WHY USE IT: Zero-shot, flexible, can explain itself, can reason | TRADEOFF: Autoregressive latency and cost for a small decision ; Open zero-shot classifier | WHY USE IT: Cheap, local, and controllable | TRADEOFF: Variable quality, you own model selection and serving ; Fine-tuned classifier | WHY USE IT: Best for a stable, high-volume task with good labels | TRADEOFF: Data collection, training drift, rigid taxonomy ; Jev | WHY USE IT: Zero-shot flexibility behind a clean, hosted API | TRADEOFF: No generated text
> * **Structured Reconstruction:**
>   | Approach | Why Use It | Tradeoff |
>   | --- | --- | --- |
>   | General-purpose LLM | Zero-shot, flexible, can explain itself, can reason | Autoregressive latency and cost for a small decision |
>   | Open zero-shot classifier | Cheap, local, and controllable | Variable quality, you own model selection and serving |
>   | Fine-tuned classifier | Best for a stable, high-volume task with good labels | Data collection, training drift, rigid taxonomy |
>   | Jev | Zero-shot flexibility behind a clean, hosted API | No generated text |

**🎙️ Spoken Transcript:**
* **[01:06]** Jev at Glean fills the gap between general LLMs and fine-tuned classifiers.
* **[01:13]** Classification itself isn't a new problem, like people have been trying to solve it since forever. We can have multiple ways to solve it. Some of the things that we have tried out include using a general purpose LLM, using an open model something like Leya, fine-tuning that open model, or using Jev.
* **[01:33]** Now all these approaches and all these different ways have their pros and cons. With a general purpose LLM, we incur a lot of cost and latency, while with something like Jev we get no generated text output.
* **[01:49]** Another advantage that we have been seeing with Jev is that as the taxonomy of the decision space changes, we don't have to fine-tune these models again and again. We can just change our prompt a bit and make it work out of the box.

💡 **Visual-Speech Alignment:** Speaker walks across all four columns ('general purpose LLM', 'open model something like Leya', 'fine-tuning that open model', 'Jev'), referencing the Column 1 tradeoff ('cost and latency'), Column 4 tradeoff ('no generated text output'), and Column 3's 'rigid taxonomy' vs Jev's 'Zero-shot flexibility'.

---

## [02:04 - 02:19] Scene #6: What we tested at Glean
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Dark blue section-divider slide (Slide 5) listing the five bounded decision tasks evaluated against existing baselines in five rounded pill boxes.
> * **On-Screen OCR:** What we tested at Glean ; Five bounded decisions, each measured against an existing baseline ; Query classification ; Model routing ; Suggestion ranking ; Citation judging ; Guardrails

**🎙️ Spoken Transcript:**
* **[02:04]** Now I'll walk you through how we have used Jev at Glean to solve these classification problem statements. I'll go into some of these problems in great detail.

💡 **Visual-Speech Alignment:** Section overview slide introducing the five problem statements covered in subsequent slides.

---

## [02:20 - 03:16] Scene #7: We evaluate in stages before anything reaches users
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Slide 6 illustrating Glean's five-stage evaluation and rollout pipeline arranged left-to-right above an arrow labeled 'Closer to users', with stage 05 highlighted in blue.
> * **On-Screen OCR:** We evaluate in stages before anything reaches users ; 01 Agreement with production — Query classification: auxiliary LLM pipeline labels ; 02 Golden-set replay — Routing: 751 labeled entries; precision and recall per route ; 03 Repeatability runs — Citations: 3 identical runs; verdict changes across 28 paragraphs ; 04 Adjudicate disagreements — Routing: 59 Jev vs OpenAI splits hand-labeled to find failure patterns ; 05 Live experiment with arms — Suggestions: 10% -> 50% of internal chat sessions; latency and quality by arm ; Closer to users
> * **Structured Reconstruction:**
>   flowchart LR
>       S1["01 Agreement with production<br/>Query classification: auxiliary LLM pipeline labels"] --> S2["02 Golden-set replay<br/>Routing: 751 labeled entries"]
>       S2 --> S3["03 Repeatability runs<br/>Citations: 3 identical runs / 28 paragraphs"]
>       S3 --> S4["04 Adjudicate disagreements<br/>Routing: 59 Jev vs OpenAI splits"]
>       S4 --> S5["05 Live experiment with arms<br/>Suggestions: 10% to 50% internal chat sessions"]

**🎙️ Spoken Transcript:**
* **[02:22]** Before we go into these individual problems, I want to touch upon how we evaluate these changes. Like we have a huge customer base having millions of users so we don't want any of the change that we make to regress our product.
* **[02:34]** We have a multiphase rollout approach to any change that we are making. This includes having a golden eval set for almost every possible thing, like any place where we have generative AI, any place where we have any form of intelligence involved, we have a golden eval set for that space.
* **[02:53]** We soak all of these changes for a significant amount of time for our internal use case, like we have around 1,500 people at Glean right now. We soak all of these changes within our Glean instance for like a couple of weeks, we get active feedback, we have a very active feedback loop from our internal users, we work upon that and then we go for an A/B testing with our customers.

💡 **Visual-Speech Alignment:** Speaker maps Glean's rollout safeguards directly to the staged pipeline: golden eval sets correspond to stage 02 ('Golden-set replay'), and internal soaking across 1,500 employees corresponds to stage 05 ('Live experiment with arms: 10% -> 50% of internal chat sessions').

---

## [03:17 - 04:35] Scene #8: Query classification: 90% of fine-tuned quality, zero training
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 7 featuring a vertical bar chart comparing agreement with production LLM labels across Base Leya (35.9%), Jev zero-shot (66.8%, highlighted in blue), and Fine-tuned Leya (74.5%), paired with three metric callouts and a bottom-right recommendation box.
> * **On-Screen OCR:** Query classification: ; 90% of fine-tuned quality, zero training ; Agreement with production LLM labels (broad task) ; Base Leya: 35.9% ; Jev zero-shot: 66.8% ; Fine-tuned Leya: 74.5% ; 90% of fine-tuned Leya's agreement (66.8% vs 74.5%) with no labeled examples or training run ; 1.9x the agreement of base Leya, the off-the-shelf open alternative (66.8% vs 35.9%) ; 0 retrains when the taxonomy changes: edit the label options in the request ; Reach for Jev when the task is new or the labels keep changing; fine-tune once they're stable.
> * **Structured Reconstruction:**
>   | Model | Agreement with Production LLM Labels | Comparison vs Jev | Training / Retraining |
>   | --- | --- | --- | --- |
>   | Base Leya | 35.9% | Jev is 1.9x higher | Zero-shot |
>   | Jev zero-shot | 66.8% | Baseline reference | 0 retrains (no labeled examples) |
>   | Fine-tuned Leya | 74.5% | Jev achieves 90% of this score | Requires labeled examples and training run |

**🎙️ Spoken Transcript:**
* **[03:17]** The first problem that we tried out with a decision model was query classification. Query classification is when we want to know the nature of user queries. This helps us realize what kind of jobs are people using Glean for—for example, if people are using more for sales-like queries, we focus more on that; if people are using more for engineering-type use cases, we focus more on that.
* **[03:45]** We tried out three different approaches over here, and this is data from our test bed. We used an open source Leya model, then we tried out Jev, and then we fine-tuned the Leya model on our own compute resources.
* **[04:00]** Jev is the best no-training option in our opinion. It nearly doubles the output quality of a base Leya model and is able to perform at a 90% quality in comparison to a fine-tuned Leya.
* **[04:15]** With Jev, we don't have to go through the very tedious process of data collection, data cleaning, incurring the cost for compute, training the model, fine-tuning the model again and again as the taxonomy changes. And at the same time, we don't have to worry about hosting the model or incurring the inference cost.

💡 **Visual-Speech Alignment:** 'nearly doubles the output quality of a base Leya model' refers to the 1.9x metric (66.8% vs 35.9%); '90% quality in comparison to a fine-tuned Leya' refers to the 90% callout (66.8% vs 74.5%); and avoiding retraining as taxonomy changes matches the '0 retrains' callout.

---

## [04:36 - 05:39] Scene #9: Routing to the right expert: More precise and 8.1x faster
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 8 presenting a grouped bar chart of precision by route across 751 golden entries comparing an LLM router (grey) against Jev (blue) for Expert 1, Expert 2, Expert 3, and No expert, plus an 8.1x median speedup callout, recall note, and tradeoff note on the right.
> * **On-Screen OCR:** Routing to the right expert: ; More precise and 8.1x faster ; Precision by route, prompt-based LLM router vs Jev (751 golden entries) ; Expert 1 (n=34): LLM router 70%, Jev 87% ; Expert 2 (n=42): LLM router 47%, Jev 86% ; Expert 3 (n=7): LLM router 13%, Jev 83% ; No expert (n=668): LLM router 96%, Jev 98% ; 8.1x median call speedup on requests routed to an expert ; Recall held or rose on every route (Expert 2: 38.7% -> 61.9%). ; Tradeoff: Jev adds a blocking call when no transfer is needed. The LLM router doesn't.
> * **Structured Reconstruction:**
>   | Route | Golden Entries | LLM Router Precision | Jev Precision |
>   | --- | --- | --- | --- |
>   | Expert 1 | n=34 | 70% | 87% |
>   | Expert 2 | n=42 | 47% | 86% |
>   | Expert 3 | n=7 | 13% | 83% |
>   | No expert | n=668 | 96% | 98% |

**🎙️ Spoken Transcript:**
* **[04:36]** The next problem we went to is expert routing. This is a pretty common problem statement in the industry right now. Like, hey, when the user query comes in, what expert do we route it to? How do we ensure that the response to the user is of the best possible quality?
* **[04:53]** The way we have been solving this is Glean receives the user query and then decides what's the best expert to answer the query. Till now we have been using a general purpose LLM to route to the correct expert.
* **[05:05]** We set up a testbed with N experts, and in our experiments found a significantly high precision when using Jev, and that too at an almost 8x reduction in latency.
* **[05:19]** We had to change our implementation or infrastructure significantly to integrate Jev into this specific stage of our product. But the reduction in latency justifies that inherent complexity in the system. We at Glean have been trying to build systems in the simplest possible manners. This is one of the rare pieces where we believe complexity is worth it.

💡 **Visual-Speech Alignment:** 'significantly high precision' points to the grouped bar chart showing Jev beating the LLM router on every route (87% vs 70%, 86% vs 47%, 83% vs 13%, 98% vs 96%); 'almost 8x reduction in latency' corresponds to the 8.1x speedup callout; and the infrastructure complexity remark matches the bottom-right Tradeoff note about Jev adding a blocking call when no transfer is needed.

---

## [05:40 - 08:51] Scene #10: Picking the suggestion: one Choice call made the ranker 7x faster
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 9 displaying a grouped bar chart of production latency in seconds (LLM ranker vs Jev ranker) for Ranker p50, Ranker p95, and Engine p50 on the left, paired with three production impact metrics on the right and a blue Choice-call summary box.
> * **On-Screen OCR:** Picking the suggestion: one Choice call made the ranker 7x faster ; After each answer, a ranker picks at most one follow-up (query, artifact, or skill), or none ; Latency in production, LLM ranker vs Jev ranker (seconds) ; Ranker p50: LLM ranker 4.67 s, Jev ranker 0.67 s ; Ranker p95: LLM ranker 6.92 s, Jev ranker 3.25 s ; Engine p50: LLM ranker 6.66 s, Jev ranker 3.76 s ; 10.2% -> 0.8% suggestion-engine timeouts ; 83% -> 91% of turns surfaced a suggestion ; 10 -> 0 invalid ranker decisions ; The options were already fixed: the candidates plus "none" became one Choice question.
> * **Structured Reconstruction:**
>   | Metric | LLM Ranker | Jev Ranker | Change |
>   | --- | --- | --- | --- |
>   | Ranker p50 latency | 4.67 s | 0.67 s | 7x faster |
>   | Ranker p95 latency | 6.92 s | 3.25 s | 2.1x faster |
>   | Engine p50 latency | 6.66 s | 3.76 s | 1.8x faster |
>   | Suggestion-engine timeouts | 10.2% | 0.8% | -9.4 pp |
>   | Turns surfacing a suggestion | 83% | 91% | +8 pp |
>   | Invalid ranker decisions | 10 | 0 | Eliminated |

**🎙️ Spoken Transcript:**
* **[05:44]** Next, I'll walk you through the ranker problem statement that I talked about. When we receive a user query, we also want to generate the best follow up suggestions for the user. This helps us in getting discoverability for our product and ensuring that the user has the best possible experience. We also want to recommend or say preempt what the next user query might be.
* **[06:11]** Internally we call this system Q, like Q as in the literal Q. The way this works, we have like 10 or 15 different sources that are generating suggestions independently of each other. These suggestions are generated by natural language LLMs, and it's like a proper natural language query. Once these suggestions are in, we have a ranking step. So the ranker takes in all these suggestions, takes in the first user query, takes in the output that Glean gave, and then all these suggestions in that context. The ranker is then asked to decide: hey, you have these suggestions, what do you think is the best one?
* **[06:54]** A pretty interesting bottleneck that we had over here is we want the response to be snappy. We cannot have a state where we give the textual response to the user and then wait 5 seconds for generating the follow up suggestion. That's why we have time limits on these suggestions. So right now this step had a time limit of 1.5 to 2 seconds.
* **[07:13]** Jev no doubt gave us a better quality and far better latency than what we had with the general purpose LLM. But two things stood out over there. First, we were able to give a suggestion within our time bounds in 99.2% cases. With the general purpose LLM, this was almost 90%. So this ensures that we have user engagement in far more user queries now.
* **[07:45]** The second thing is at Glean whenever we use these LLMs, we have guardrails in the sense that LLM might not be good at generating a response or might be making some specific kind of mistakes, so we have checks and balances for all those possible mistakes that we see. With a general purpose LLM, we were able to generate a valid suggestion in almost 90% of the cases—we still had some places where LLM was either generating a response in a different language or the output did not meet certain other criteria that we had written programmatically. With Jev, we found zero cases to be there when the output was invalid.
* **[08:35]** Now a natural question is like, hey, but you would have used a different prompt. Yes, the prompt was somewhat different, but we try to mimic the prompt in the two cases to the largest extent possible so that we don't have a divergence. Again, we at Glean want to keep the system as simple as possible.

💡 **Visual-Speech Alignment:** 99.2% within time bounds (vs ~90% for the LLM) corresponds directly to the '10.2% -> 0.8% suggestion-engine timeouts' metric; 'zero cases... when the output was invalid' maps to '10 -> 0 invalid ranker decisions'; and the 1.5–2s latency budget explains why the 4.67 s -> 0.67 s Ranker p50 reduction raised surfaced suggestions from 83% to 91%.

---

## [08:52 - 09:43] Scene #11: Confidence scores let the system decide when not to decide
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 10 illustrating probability-based abstention across two suggestion-ranking examples (Turn A: nothing shown; Turn B: query shown) with horizontal confidence bar charts against a dashed red 0.50 cutoff line, plus three numbered configuration notes on the right.
> * **On-Screen OCR:** Confidence scores let the system decide when not to decide ; Turn A: nothing shown — skill 0.49, query 0.30, artifact 0.16, none 0.05 — Top pick 0.49 is below the 0.50 cutoff, so the system abstains ; Turn B: query shown — query 0.67, artifact 0.29, none 0.04 — Top pick 0.67 clears the cutoff, so the suggestion is shown ; 1. Abstaining is a first-class outcome, logged separately from failures ; 2. The cutoff is a config flag tuned per surface (0.40 by default in the production experiment) ; 3. Same pattern for routing: transfer only on a confident pick, otherwise keep the default model
> * **Structured Reconstruction:**
>   | Turn | Option | Confidence Score | 0.50 Cutoff Check | Outcome |
>   | --- | --- | --- | --- | --- |
>   | Turn A | skill | 0.49 | Below 0.50 | System abstains (nothing shown) |
>   | Turn A | query | 0.30 | Below 0.50 | - |
>   | Turn A | artifact | 0.16 | Below 0.50 | - |
>   | Turn A | none | 0.05 | Below 0.50 | - |
>   | Turn B | query | 0.67 | Clears 0.50 | Suggestion shown |
>   | Turn B | artifact | 0.29 | Below 0.50 | - |
>   | Turn B | none | 0.04 | Below 0.50 | - |

**🎙️ Spoken Transcript:**
* **[08:55]** Another benefit we see with using a decision model is how we can control the thresholds. Because in this ranker problem statement we are getting specific probabilities of each output. We are not restricted to a binary yes or no response. We get like hey, these were the five options and these are the probabilities of these five options.
* **[09:15]** With this we are able to fine-tune the thresholds based on the deployment. We have put in self-learning systems which, based on the customer deployment and the nature of usage that the specific customer has, fine-tunes the thresholds by itself. This ensures that the experience in each and every customer out there is the best possible based on how they use Glean, not a general purpose solution that fits all.

💡 **Visual-Speech Alignment:** 'specific probabilities of each output' maps to the confidence scores shown in Turn A (0.49, 0.30, 0.16, 0.05) and Turn B (0.67, 0.29, 0.04), while threshold tuning per customer deployment connects to the dashed cutoff line and bullet 2 ('config flag tuned per surface').

---

## [09:44 - 12:29] Scene #12: Checking citations: ~12x faster and far more repeatable
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 11 (labeled 9 on slide footer) comparing Jev against GPT-5.4 Luna judges (no reasoning and high reasoning) on Time and Cost in a table on the left, paired with a blue callout card on the right highlighting verdict consistency across 3 identical runs on 28 paragraphs.
> * **On-Screen OCR:** Checking citations: ~12x faster and far more repeatable ; Judge | Time | Cost ; Jev | 6.6 s | $0.014 ; Luna, no reasoning | 81.3–85.5 s | $0.030–0.047 ; Luna, high reasoning | 227.4–259.7 s | $0.047–0.060 ; GPT-5.4 Luna judges, 3 runs each on identical input. These are judge scores, not accuracy. ; 1 of 28 paragraphs where Jev changed its verdict across 3 identical runs ; Luna changed 7 of 28 with no reasoning, and 5 of 28 with high, which also roughly tripled its time. ; Same 1,448-word production response
> * **Structured Reconstruction:**
>   | Judge | Time | Cost | Verdict Changes Across 3 Runs (28 Paragraphs) |
>   | --- | --- | --- | --- |
>   | Jev | 6.6 s | $0.014 | 1 of 28 |
>   | Luna, no reasoning | 81.3–85.5 s | $0.030–0.047 | 7 of 28 |
>   | Luna, high reasoning | 227.4–259.7 s | $0.047–0.060 | 5 of 28 |

**🎙️ Spoken Transcript:**
* **[09:45]** Okay, this is an interesting one. Now moving on from how we have been making the experience of our end users better, we also tried using Jev in some other parts of our development pipeline. One of them was how we use LLM as judges. Like all of us have been using LLM as judges for quite some time now. There is an input, there is an output, and we use an LLM to judge how the quality of the output is. Now naturally, whenever we use LLM as a judge, we repeat the experiment multiple times to account for the variability in the response.
* **[10:25]** At Glean, we used Jev for a very specific part of our evaluation pipeline. Glean responses, like any other AI product out there, have citations. This is how people trust that Glean's answer was correct and it is grounded in the correct document. Now we hold these citations to a very high bar, and we have a specific part in our evaluation pipeline where we check whether the cited document really supports the claim made in the answer or not. This again seems to be a pretty simple yes or no question: whether the claim is supported or not.
* **[11:02]** With Jev, no doubt we had a far better latency and cost like visible in the slide over here. The interesting thing we noticed over here is how consistent and reproducible Jev results were in comparison to something like say Luna. In the 28 or 30 use cases that we had, only one run had a difference in response. Apart from that, everything was consistent.
* **[11:28]** What this ensures are two things for us as engineers or developers at Glean: we are not only improving the quality of our product in a linear fashion anymore. Any improvement of this extent in the development pipeline leads to an exponential increase in how we can improve the product. So if I as a developer am able to ship things like 5x faster—like this is a significant reduction in latency if I run this experiment across thousands and thousands of entries, this saves a lot of time. And again, I don't have to run the same input-output pair multiple times, because the results from Jev are quite consistent. So if I'm able to increase my own productivity by like 5x or 6x, I can ship 6x the features to our customers, and this happens across like 500 or 300 engineers at Glean. So the impact of a good decision model is no longer linear, it is exponential on how we can improve the product.

💡 **Visual-Speech Alignment:** 'far better latency and cost like visible in the slide over here' references the Jev row (6.6 s, $0.014) vs Luna rows (81.3–259.7 s, $0.030–0.060); 'only one run had a difference in response' across '28 or 30 use cases' points to the right-hand blue card ('1 of 28 paragraphs where Jev changed its verdict across 3 identical runs' vs 7 of 28 and 5 of 28 for Luna).

---

## [12:30 - 14:23] Scene #13: Guardrails: Jev tripled first-pass recall at about the same precision
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 13 presenting a horizontal bar chart of first-pass recall on internal guardrail datasets comparing the previous first-pass classifier (grey) to Jev (blue) across six prompt/response categories, plus four summary KPI blocks on the right.
> * **On-Screen OCR:** Guardrails: Jev tripled first-pass recall at about the same precision ; Every prompt, tool output, and response paths a fast first-pass check: an LLM makes the final call on what it flags ; First-pass recall on internal guardrail datasets ; Injection: prompt — Previous 19%, Jev 99% ; Injection: retrieved — Previous 4%, Jev 92% ; Harmful: prompt — Previous 81%, Jev 92% ; Harmful: response — Previous 6%, Jev 82% ; Malicious code: prompt — Previous 29%, Jev 87% ; Malicious code: response — Previous 22%, Jev 87% ; 31.5% -> 90.2% overall recall; precision 92.7% -> 90.8% ; 2-3x more violations caught on our internal deployment, with no rise in false positives ; 137 ms p50 across 22.8M production calls (p99 347 ms); run in parallel with the LLM ; $4,000 -> $2,100 per month on our internal deployment: 8 GPU pods vs ~50B Jev tokens
> * **Structured Reconstruction:**
>   | Guardrail Dataset | Previous First-Pass Classifier Recall | Jev Recall |
>   | --- | --- | --- |
>   | Injection: prompt | 19% | 99% |
>   | Injection: retrieved | 4% | 92% |
>   | Harmful: prompt | 81% | 92% |
>   | Harmful: response | 6% | 82% |
>   | Malicious code: prompt | 29% | 87% |
>   | Malicious code: response | 22% | 87% |
>   | Overall (Recall / Precision) | 31.5% / 92.7% | 90.2% / 90.8% |

**🎙️ Spoken Transcript:**
* **[12:33]** Now moving on from product and LLMs as judges, this is a pretty important part of how we use our customer data. Like security is something that all our customers expect from us. So, for example, we have checks and balances on all the inputs and outputs coming from a tool, all the inputs and outputs from an LLM.
* **[12:58]** Till now, we at Glean have like a multiphase approach—there are two phases to this. The first one is like a recall-heavy phase and the second one is the final heavy-loaded LLM. All these calls are made in parallel to the actual tool input-output calls. Till now we used to host a virtual classifier using T4 GPUs across all our customers. So Glean is a single-tenant solution, like we don't use or share resources across customers, every customer gets its own deployment, gets its own instance, and gets all the resources. So assuming we have 1,000 customers out there, we had to maintain virtual classifiers across all these 1,000 customers, which becomes a pretty difficult problem statement in itself which takes up a lot of time from Glean engineers.
* **[13:46]** So looking at the results over here, the overall recall of the first phase where we used to have a virtual classifier—we replaced that with Jev—went from 31.5% to 90.2%. At the same time, we are seeing a significant reduction in cost. Now this cost is only the resource cost mentioned over here, but we are also saving cost on the engineering resources over here. We don't have to invest like two or three engineers who are full time maintaining those virtual classifiers or those T4 GPUs across customers. The improvement or the savings that we have are far more than 50%.

💡 **Visual-Speech Alignment:** 'overall recall of the first phase... went from 31.5% to 90.2%' directly cites the top-right metric; 'calls are made in parallel' matches the 137 ms p50 note ('run in parallel with the LLM'); and 'only the resource cost mentioned over here' points to '$4,000 -> $2,100 per month on our internal deployment: 8 GPU pods vs ~50B Jev tokens'.

---

## [14:24 - 14:43] Scene #14: One decision model, used across product, evals, and security
> **[SCREEN INTERPRETATION | Type: `BENCHMARK_TABLE`]**
> * **Visual Summary:** Slide 14 summarizing all five evaluated Jev use cases grouped into three areas (Product experience, Evals and analytics, Security) with Quality vs baseline, Speed / cost, and color-coded Verdict badges (Shines or Mixed).
> * **On-Screen OCR:** One decision model, used across product, evals, and security ; Area | Decision | Quality vs baseline | Speed / cost | Verdict ; Product experience | Model routing | Higher precision on every route | 8.1x faster (median) | Shines ; Product experience | Suggestion ranking | More suggestions surfaced, fewer timeouts | 7x faster ranker p50 | Shines ; Evals and analytics | Citation judging | Most repeatable verdicts (1/28 vs 5–7/28) | ~12x faster, 2–4x cheaper | Shines ; Evals and analytics | Query classification | 66.8% vs 74.5% fine-tuned | No training; best while labels change | Mixed ; Security | Guardrails (first pass) | Catches 90% of unsafe content, ~91% precision | 137 ms p50, about half the cost | Shines
> * **Structured Reconstruction:**
>   | Area | Decision | Quality vs Baseline | Speed / Cost | Verdict |
>   | --- | --- | --- | --- | --- |
>   | Product experience | Model routing | Higher precision on every route | 8.1x faster (median) | Shines |
>   | Product experience | Suggestion ranking | More suggestions surfaced, fewer timeouts | 7x faster ranker p50 | Shines |
>   | Evals and analytics | Citation judging | Most repeatable verdicts (1/28 vs 5–7/28) | ~12x faster, 2–4x cheaper | Shines |
>   | Evals and analytics | Query classification | 66.8% vs 74.5% fine-tuned | No training; best while labels change | Mixed |
>   | Security | Guardrails (first pass) | Catches 90% of unsafe content, ~91% precision | 137 ms p50, about half the cost | Shines |

**🎙️ Spoken Transcript:**
* **[14:24]** This slide concludes all the results I have talked about till now. Jev at Glean has been able to influence the product experience of the users, has been able to impact how we as developers have been working at Glean. And most importantly, it also has a very good positive impact on the security that we provide to our customers.

💡 **Visual-Speech Alignment:** Speaker summarizes the three Areas on the left column of the summary table: 'Product experience', 'Evals and analytics' (developer workflow), and 'Security'.

---

## [14:44 - 15:27] Scene #15: A simple rule for when to reach for a decision model
> **[SCREEN INTERPRETATION | Type: `ARCHITECTURE_DIAGRAM`]**
> * **Visual Summary:** Slide 15 presenting a three-row decision framework with blue question cards on the left branching into white/blue recommendation boxes on the right for choosing between generative models, Jev, fine-tuned classifiers, or a hybrid pattern.
> * **On-Screen OCR:** A simple rule for when to reach for a decision model ; Can the output be listed in advance? -> No -> keep a generative model (queries, explanations, tool arguments) | Yes -> benchmark Jev ; Are labels stable and volume high? -> Yes -> also benchmark a fine-tuned classifier | No -> Jev's zero-shot flexibility pays off ; Do you also need dynamic text? -> Go hybrid: Jev picks the tool, the LLM writes the arguments
> * **Structured Reconstruction:**
>   flowchart TD
>       Q1["Can the output be listed in advance?"] -->|No| A1["Keep a generative model<br/>(queries, explanations, tool arguments)"]
>       Q1 -->|Yes| A2["Benchmark Jev"]
>       A2 --> Q2["Are labels stable and volume high?"]
>       Q2 -->|Yes| A3["Also benchmark a fine-tuned classifier"]
>       Q2 -->|No| A4["Jev's zero-shot flexibility pays off"]
>       Q3["Do you also need dynamic text?"] --> A5["Go hybrid: Jev picks the tool, the LLM writes the arguments"]

**🎙️ Spoken Transcript:**
* **[14:44]** In conclusion, a simple rule that we have been using at Glean is: can the output be listed in advance? If no, then it's a freeform generative text problem statement—go back to something that can generate freeform text. If yes, then use Jev.
* **[15:02]** Are labels stable and volume high? If this is the case where the labels are stable, which is rarely the case anymore, you can also fine-tune a model. But if the labels change, which in my opinion is quite frequent these days, then again use something like Jev.
* **[15:18]** Obviously, if you need dynamic text, feel free to try out more hybrid approaches like Jev along with freeform text LLMs.

💡 **Visual-Speech Alignment:** Speaker reads sequentially down the three blue question blocks ('Can the output be listed in advance?', 'Are labels stable and volume high?', 'Do you also need dynamic text?') and explains each outcome box on the right.

---

## [15:28 - 15:47] Scene #16: Generate when you must. Decide when you can.
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Closing blue slide showing the tagline 'Generate when you must. Decide when you can.', speaker contact email, blog URL, and colleague acknowledgments; transitions at 15:32 to wide auditorium shots of the stage and screens as Chinmay concludes.
> * **On-Screen OCR:** glean ; Generate when you must. ; Decide when you can. ; Thank you ; Chinmay Goyal · chinmay.goyal@glean.com ; Read more: glean.com/blog/jev-zero-shot-classifier ; Thanks to Deepak Verma, Eddie Zhou, Chau Tran, Aviral Singh, Matt Zhai, Manav Agrawal, and Sarika Mohapatra ; © 2026 Glean Technologies, Inc.

**🎙️ Spoken Transcript:**
* **[15:31]** This ends my presentation. So thank you everyone for listening. I have added a link to the blog post, where we have posted the exact same results in great detail. Feel free to catch me on the outside if you have more questions. Thank you.

💡 **Visual-Speech Alignment:** Speaker points viewers to the blog URL ('glean.com/blog/jev-zero-shot-classifier') displayed on the closing slide.

---

## [15:48 - 16:04] Scene #17: AI Engineer Code Summit
> **[SCREEN INTERPRETATION | Type: `SLIDE`]**
> * **Visual Summary:** Closing conference bumper card on a black background displaying the AI Engineer Code Summit logo and website URL.
> * **On-Screen OCR:** AI Engineer Code Summit ; HTTPS://AI.ENGINEER

**🎙️ Spoken Transcript:**
* **[16:01]** This is the test of the recording system.

💡 **Visual-Speech Alignment:** Post-presentation conference outro bumper with an incidental recording-system test message in the final seconds.

---
