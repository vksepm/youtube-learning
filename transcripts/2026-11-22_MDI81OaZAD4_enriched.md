# Enriched Interleaved Transcript: How to build an agent that builds the culture — Zach Bruggeman, Ramp
**Channel:** AI Engineer | **YouTube URL:** https://www.youtube.com/watch?v=MDI81OaZAD4
**Model:** `gemini-3.5-flash-lite` | **Processing Mode:** `agentic`

---

## [00:00 - 08:67] Scene #1: No Title
> **[SCREEN INTERPRETATION | Type: `SPEAKER_ONLY`]**
> * **Visual Summary:** Speaker presenting on stage about Ramp's engineering culture and their collaborative coding agent, Inspect.

**🎙️ Spoken Transcript:**
* **[00:13]** My name is Zach and I'm an engineer at Ramp. I'm just really excited to tell you all a bit about how Ramp has evolved as engineering culture this year, through the help of our robotic friend, Inspect.
* **[00:20]** As a quick introduction, Inspect is Ramp's collaborative coding agent. About a year ago, we decided to take a bet on building our own coding agent with every session running remotely and being fully multiplayer.
* **[00:30]** Inspect can work alongside you and your team, whether that be an Inspect itself, Slack, linear, or any other of our integrations.
* **[00:41]** And now it goes far beyond just writing the code with the design primitives, review agents and verification flows that let any builder go from prompt to shipping all on side inspect.
* **[00:50]** Inspect is also connected to all of our integrations company-wide, so everyone's automatically connected to the data and tools that matter most, whether that be telemetry, databases, or any of the other tooling available.
* **[01:00]** Through this, we now see around 75% of all of Ramp's code being being written and shipped by Inspect.
* **[01:10]** When we started sharing Inspect publicly at the start of the year, the technology itself was the more novel part. Spinning up sandboxes in under 5 seconds, wiring up all that internal context, having agents work together in a multiplayer setting.
* **[01:20]** People had a lot of questions about the plumbing. But now with much broader adoption of these concepts, and Inspect itself now being a product on the market, the technology isn't nearly the barrier that it once was.
* **[01:30]** Instead, I want to talk about the other angle. The lessons we've learned around building a culture around Inspect and what you can take away to inspire the people and teams that you work with.
* **[01:40]** Uh I'm not going to talk as much about those technical aspects of Inspect today, but if you are curious about that, you can read our blog posts or take a look at Pragmatic Engineer's deep dive that they did with us a few months ago.
* **[01:50]** You can also follow my boy Dylan Garcia on Twitter. He's on a social media grind, but he's also been posting a ton of really great inspecting sites, uh, since we've launched it. So, shout out to Dylan. Please go give him a follow.
* **[02:11]** One thing about working at Ramp is that it really makes you start thinking about everything through the lens of saving time and money.
* **[02:20]** And although I think it is important to understand the systems that you work with and understand how your tooling works, if you're a multi-hundred or multi-thousand person organization, and everyone has to go through, say, 15 minutes of setup.
* **[02:30]** Once you start multiplying that across an organization, this is days lost for what is very rote work. Then, if you consider how fast the frontier moves here, on best practices and new ways to set up an agent, you realize this setup cost isn't just one time.
* **[02:40]** Not to mention, these advancements won't always spread equally. So, now you have an indeterminant amount of time and effort spent on this maintenance without an equal spread of knowledge, leading to desperate outcomes across an organization.
* **[03:00]** You can perceive this as an advantage on an individual level. When you're trying to win, you need everyone on your A-game. So, this was our first lesson. Build tools that kill information silos.
* **[03:10]** When we found patterns that worked well, or tools that benefited everyone, we could push it to our entire organization immediately. If you want to spend time tweaking your own setup, that's fine.
* **[03:20]** But Inspect is always available as a very solid baseline. And what we've found is that we've never needed to mandate usage of Inspect because it existing as this baseline reduced the need for people to reach for their own setups all the time.
* **[03:40]** Part of what I think makes this powerful as well, is that the reality of this industry is that it's unlikely that you as an individual always know the absolute best way to work with agents across everything.
* **[03:50]** Even if keeping up with this is your full-time job, we all miss things, hold biases and have blind spots. So part of the design of Inspect is that there's just one single Inspect for the whole company.
* **[04:00]** When people figure out better ways to use it or have ideas for what make it better for the work they do, we're able to bring it to the entire company. The best part of this is that for most changes, this is invisible to everyone else.
* **[04:10]** You just keep using Inspect as you normally would and benefit from the improvements that everyone's making over time.
* **[04:21]** What we've found is that we really don't have to run these formal sit-down, here's how you use AI effectively, training sessions for Inspect.
* **[04:30]** With every Inspect session being public within the company by default, it's actually easier to work in public than in private. As such, you default to working in public, and you can learn how to use it by watching how your teammates use it in the channels that you're already in, and your teammates can learn from you.
* **[04:49]** You can literally ask InSpects to go through their recent sessions and tell you about how they work, how they structure prompts, or how they break down gnarly problems.
* **[04:59]** I think this has not just been helpful for the builders at ramp but also for the spect team itself. We frequently see the way that people are using inspect in ways that we didn't originally imagine.
* **[05:09]** This then informs what we should build towards, whether that should be more native primitives for common patterns, or where tools and data are missing. All in all, it creates this self-sustaining loop where we're able to build towards what makes inspect the most successful by seeing what people are already achieving with inspect.
* **[05:20]** This feeds into the second lesson that we've learned. It's all about building trust. I think it's fair to say that adopting agentic driven coding has been a massive trust building exercise for every engineer this year.
* **[05:40]** It's helped that the models have become more competent at writing high quality code, but there's a large part of this that's just learning to trust what an agent builds. So much of building trust in tools comes from learning from other people.
* **[05:50]** After all, that's why most of us are here, right? You wanted to listen to people you respect, or at least I hope you respect, uh, teach you about the things that they learn. But if we limit our corpus of knowledge to just those who find the perverse enjoyment in public speaking, we're still not getting the full picture.
* **[06:10]** This democratization of knowledge sharing is just fascinating to me as a concept. Instead of grouping around a select few leaders, can we build systems that inherently share the knowledge of everyone? This is what Inspect has built towards.
* **[06:20]** Every time someone ships something with Inspect, people can see it right there on the work you've done. The session itself is an easy to share, it's a living artifact of how that change came to be.
* **[06:30]** When a pull request goes up, anyone reviewing it doesn't just see the 400 line diff dropped over the wall and hope for the best. They can see the exact conversation that you had, all the tools that Inspect used, before and after screenshots, or even a video recording of the verification agent clicking through the app in the browser to prove its work holds up.
* **[07:00]** It makes it effortless to share not just what changed, but Why you contrast it? It also just makes it easier to bring people you don't work with all the time into the fold.
* **[07:10]** A a fun moment on this one, it was back in February, one of our engineers, Andrew reported a bug in inspect. So naturally, I reached for inspect and asked him to investigate.
* **[07:20]** What's funny here is that, although inspect had access to DataDog for a while, we'd only just finished instrumenting inspect itself. I mean, inspect was primarily built by front-end-y product engineers.
* **[07:30]** So, tracing was a little bit of a foreign concept for us. But in any case, it was a great time for us to put it to the test for inspect. And then inspect says, the instrumentation was causing the error.
* **[07:40]** Yes, the very instrumentation that was letting us debug this error was actually causing this error. So, Dylan and I were not exactly convinced by the robot here.
* **[07:50]** And Andrew is just like, whatever, I'll use Claude code. And and while we don't have a mandate to use inspect, I mean, personally, these were not the words I wanted to hear. So, nobody here is really trusting anybody.
* **[08:00]** Dylan and I don't trust the robot's explanation. Andrew doesn't trust us to build something that works. And inspect, well, I don't know if inspect trusts anyone, but that's okay, that's okay.
* **[08:20]** But because this is happening together in public, we keep prodding at it. Dylan asks inspect to look through the code of the telemetry library using and see if this was just something that was happening before without visibility.
* **[08:30]** Because surely by now, coding has been solved and there can't be bugs that we introduced. And this time it comes back with something a bit more specific. The hotel library calls fetch, but it never reads or cancels the response body.
* **[08:40]** This was just the cloud flare platform location at the time, albeit happening in a library specifically made for cloud flare workers. But that happens, this library was written pre AGI after all.
* **[08:50]** At this point, we ask inspect to make a patch. It updates the exporter to explicitly cancel the response body. We grumbled in the afraid a bit while it was deploying, but we see after it deployed, there haven't been any errors since.
* **[09:10]** So great. Inspect fixed the bug, which at this point, that's nothing special in itself. But there was a much more important story playing out in this thread.
* **[09:20]** Before inspect, a report like this might have been acknowledged, a ticket filed, and then one of us would have gone away to debug it. Andrew might have received a message later saying it was fixed, but the interesting work would have been done in private.
* **[09:30]** Now though, it's easier to do all of this in public. And as such, Andrew naturally starts becoming engaged. Want to chime in with his thoughts and experiences.
* **[09:40]** And then, in that same thread, this leads to ideas coming up about how inspect could power other work. And none of this required any prodding or pressure to work together, instead it was just like, oh, these guys are doing something cool and we could work on it together.
* **[09:59]** So, in the span of an hour, we go from a skeptical user with a broken user experience to an engaged colleague wanting to build together and in more stable inspect.
* **[10:00]** Once you have a tool that gives everyone the best setup on day one with no information silence and you've built a system of trust that brings innovation together. What happens next? This is the last lesson I want to share.
* **[10:20]** Something that's pained me this year is how much reverence has been built for the lone wolf operator. It's great that we can all do more individually with the help of AI.
* **[10:30]** But this can't be the end game in my opinion. If we don't build outwards, collaborate with other people and continue to share the progress and learnings we make, I think this is all going to collapse in on itself.
* **[10:40]** We'll only consider ourselves as our target audience. And we won't grow through the consideration of others' perspectives and experiences.
* **[10:50]** This is not to say I'm all doom and gloom about this. The fact we're all here, hopefully is a testament to the value of connection. More importantly though, I think we can shape our tools to include enable these connections to flourish even stronger than before.
* **[11:00]** That story I told about Andrew has played out so many times with an amp. It's probably the most inspiring thing about inspect to me, honestly. Sure, it's a coding agent, but remarkably, it's become part of the culture.
* **[11:10]** Everyone at amp knows its face, we dress it up on holidays, we throw in Easter eggs overtime. and we evolve it as ramp itself has evolved. Not all literations have been perfect as any ramp engineer could tell you,
* **[11:30]** but I do think every iteration has been together. Going back to earlier this year, Inspect didn't have nearly the amount of functionality it has today. A great example is its code review agent.
* **[11:40]** Before this, we were using various off-the-shelf code view products frequently rotating between them to find a good fit. At some point though, a couple engineers, Daniel and Pranjal realized that we could probably build it ourselves
* **[11:50]** as Inspect already had automation triggers that fired from a variety of sources, including wanted to pull a request that was open. With just what we built already, they got to work building another beloved agent at Ramp, Review Buddy.
* **[12:00]** And what was so cool about this is that, much like in Spects own origins as a side project, these engineers were working on this, they didn't need to ask for permission to build it.
* **[12:20]** They just challenged themselves to build something better, used inspect to move faster, and quickly built an agent that was better for all of Ramp. This really did force us working on inspect to think about inspect differently.
* **[12:30]** At that point in time, we were pretty okay with inspect, quote unquote, just being a coding agent. But once we saw what others were pushing it to do, it got us thinking about how inspect could become full circle.
* **[12:40]** If this push didn't happen naturally, I think it would have taken the inspect team a lot longer to get there. This is what I mean about thinking bigger together.
* **[12:52]** Especially with the continued improvements in model performance, now is the time to push yourself and the people around you to think bigger.
* **[13:00]** I encourage all of you to take some time in this coming week to ask everyone that you work with, what have we been waiting to do that we haven't done yet. And once you've found those things, try to build them together.
* **[13:10]** There's really not an excuse to not just try anymore. You have access to the same models as everyone else. But you have to start somewhere, and I believe that there is so much potential in unlocking wins not just for yourself, but for the people around you.
* **[13:30]** Inspect itself was born this way, not only as something that I wanted to build and Jason wanted to build, but out of a want to build something for a team that I truly love and truly respect, that would just make their jobs a little more enjoyable.
* **[13:40]** Now, if you'd like to use a coding agent that has embodied all these lessons that we've learned, I'm happy to say that Inspect is now available outside of Ramp.
* **[13:50]** If you go to inspect.com/AIE, we'll prioritize you and your team on the wait list. We're actually moving through this wait list pretty quickly, so expect to hear from us soon.
* **[14:00]** Otherwise, I hope you've enjoyed hearing about our robotic friend Inspect. If these topics interest you, feel free to reach out here or on X. But otherwise, thanks so much for listening.

💡 **Visual-Speech Alignment:** The speaker remains on stage presenting throughout the entire video.

---
