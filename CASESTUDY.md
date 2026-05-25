# UnblockMe: Case Study

**Live product:** https://unblock-me.lovable.app
**Built by:** Clayton Black
**Type:** AI-powered writing tool
**Stack:** Lovable, browser localStorage, AI API relay
**Status:** MVP, live

---

> *"Until it exists, writing has not really begun."*
> — John McPhee

---

## The problem

For as long as I can remember, I have had ideas for stories. As a kid it was characters and worlds. Later, scenes that would replay in my head, vivid and intrusive, with no story attached to them. The problem was never a shortage of ideas. It was not knowing what to do with them.

Looking for help, I found the tools available tend to go one of two ways. Either they offer a blank canvas with no structure or guidance, leaving you exactly where you started. Or they write for you, generating prose, drafting scenes, producing copy on demand. Neither addresses the real problem. A blank canvas is paralysing when you do not know where to begin. And AI-generated prose removes the very thing that made you want to write in the first place.

For writers who have not yet started, the major hurdles are often structure, doubt, and the specific paralysis that comes from simultaneously loving an idea and having no idea how to begin. And once you do start, a new problem arrives: you hate what you have written. Perfectionism sets in. You edit instead of progress. The gap between the story in your head and the words on the page feels insurmountable.

"Just start writing" is not useful advice when you do not know what you are starting.

---

## The insight

Writer's block takes many forms. The paralysis of not knowing where to begin. The loss of confidence that creeps in midway through a draft. The scene that will not connect to the next one. The quiet, persistent doubt about whether the story is worth telling at all. These are different problems, and they do not all have the same solution.

What they share is that none of them are solved by someone else doing the writing. The major barriers are rarely about lacking ideas. They are about not knowing how to move forward with the ones you have. A thinking partner that asks good questions, reflects back what it hears, and proposes a structure, without ever touching the prose, is more useful than a tool that writes for you.

---

## What I built

UnblockMe is a focused AI tool for writers who are stuck, at any stage of the process. It does three things:

**Plan a story.** The writer dumps everything they have: characters, scenes, fragments, images, tone, whatever exists. UnblockMe analyses the material, proposes a story structure mapped to act beats, and identifies gaps. It does not write the story. It finds the shape of what the writer already has.

**Polish a scene.** For writers who are mid-work and stuck on a specific moment. They describe where they are and where they need to get to, and UnblockMe offers craft prompts to help them move forward. No prose generated.

**Refine a beat.** Within a story plan, any individual beat (the inciting incident, the crisis, the climax) can be interrogated and refined through writer's notes. The writer steers; the tool responds.

The core product promise: **get unstuck without handing over the writing.**

---

> *"The first draft is you just telling yourself the story."*
> — Terry Pratchett

## Key product decisions

**Knowing when to stop**

The temptation when building with AI tools is that everything feels possible and nothing feels finished. The feature list expanded fast. Character development tools. Setting cards. Beat expansion into full scene synopses. Series connectors for trilogies. Research dumps. Dialect references. Each one was a real problem worth solving. Each one also felt, in the moment, like an obvious next step.

I cut all of them. Not because they were bad ideas, but because they were solving adjacent problems rather than the core one. Every feature I added risked turning UnblockMe into something writers would spend time inside instead of moving through. The trap with productivity tools, especially creative ones, is that they become a more sophisticated form of procrastination. A perfectly organised story system feels productive. It is not the same as a story. The job of UnblockMe is to get out of the writer's way, not to become another thing they have to manage.

**Privacy by architecture**

UnblockMe stores nothing on a server. All user data lives in the user's own browser. The only backend is a thin relay function that calls the AI without exposing the API key. It does not log, store, or process anything beyond that single exchange.

This was partly a practical decision for an MVP, but it became something more considered. Writers are often protective of their ideas in a way that is hard to explain to people who are not writers. An unfinished story is fragile. The knowledge that nothing you type leaves your own device is a genuine product value for that kind of user, not a footnote in a privacy policy. The trade-off is that work does not persist across devices or browsers, which we make transparent with a first-use notice.

**What comes next: why this story, and why now**

The most important unbuilt feature is not a writing tool. It is a question.

In theatre, dramaturgs routinely ask playwrights: "Why do you need to tell this story, and why now?" Understanding a writer's motivation, what draws them to the material and what they are trying to say, serves two purposes. It helps them get clear before they start, so they have a firm point of reference when doubt and block arrive. And it becomes useful context for the tool: themes to surface, dimensions to explore, a filter for what the story actually needs to be.

That question is the next thing I want to build into UnblockMe.

---

## What surprised me

How easy it was to over-build, and how good it felt while I was doing it.

Building with AI tools removes almost all the friction from shipping features. That sounds like a good thing, and in many ways it is. But friction has always done quiet work in product development. It forces a conversation about whether something is worth building before you build it. When that friction disappears, so does that conversation.

When you can add a feature in twenty minutes, the measure of progress shifts. Shipping feels like succeeding. But shipping is not the same as solving. A product that does twelve things adequately is not better than one that does three things well, and the user almost always pays the price for the confusion.

The discipline of stopping, of looking at a good idea and saying "not this product, not now", turned out to be harder than any technical decision I made.

---

## What I would measure if this went further

- Session completion rate (did users reach a story map or craft prompts, or drop off at the input stage?)
- Return rate (did they come back with the same story?)
- Export usage (a proxy for whether they found the output worth keeping)
- Time to first "Unblock Me" click (are users over-thinking the setup?)

---

## Reflections

This was my first AI-powered product built without an engineering team. The build tool was Lovable; the thinking was product management.

The most valuable skill was not technical. It was knowing when to stop. The hardest part was not building features. It was resisting the ones that did not belong.

UnblockMe is a small, focused tool. That is a product decision, not a limitation.

---

*Built May 2026. Clayton Black is a Product Manager at Lunio, currently developing AI product skills alongside his day job.*
