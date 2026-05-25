# UnblockMe

**A focused AI tool for writers who have not started yet.**

🔗 [Try it live](https://unblock-me.lovable.app) · [Read the full case study](./CASESTUDY.md)

---

## What it does

UnblockMe helps writers get unstuck at any stage of the process, without writing a single word for them.

Writer's block takes many forms. It is the paralysis of not knowing where to begin. The loss of confidence midway through. The scene that will not connect to the next one. The creeping doubt about whether the story is worth telling at all. UnblockMe does not try to solve all of these with a single feature. Instead it offers focused tools for the specific kind of stuck you are in, and steps aside so the writing can happen.

**Three modes:**

- **Plan a story** — dump everything you have (characters, scenes, fragments, tone) and get back a proposed story structure mapped to act beats
- **Polish a scene** — describe where you are and where you need to get to, and receive craft prompts to move forward
- **Refine a beat** — interrogate any individual beat in your story plan and push it further with writer's notes

The core promise: **get unstuck without handing over the writing.**

---

## Key product decisions

**No prose generation.** Every feature was designed to stimulate the writer, not replace them. UnblockMe asks questions, proposes structures, and surfaces prompts. It does not draft scenes or generate copy.

**Privacy by architecture.** Nothing the user types leaves their device. All data is stored in the browser via localStorage. The only backend is a relay function that calls the AI without exposing the API key. No database, no accounts, no server-side storage.

**Deliberately limited scope.** Many features were considered and cut: character cards, setting maps, beat expansion, series connectors, research storage. Each was a real problem worth solving elsewhere. Keeping UnblockMe focused was an active product decision, not a limitation of the build.

---

## Built with

- [Lovable](https://lovable.dev) — AI-powered app builder
- Browser localStorage for data persistence
- AI API via a thin server relay function

---

## Status

Live MVP. Actively developed.

Next planned feature: a guided prompt asking writers "why do you need to tell this story, and why now?" — a question borrowed from theatre dramaturgy that surfaces motivation before the writing begins.

---

## About

Built by [Clayton Black](https://www.linkedin.com/in/claytonblack) — Product Manager at Lunio, currently developing AI product skills alongside the day job.

For the full product thinking behind this project, read the [case study](./CASESTUDY.md).
