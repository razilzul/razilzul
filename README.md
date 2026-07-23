## Hi, I'm Rz 👋

Full-stack engineer in Singapore. 18+ years shipping software in three chapters: a decade of award-winning games, then 8 years building the software layer for hospital robotics at Singapore's national centre for healthcare robotics, and now AI-native product development on the side of that. Most of my career is employer or client IP, so this profile can only show the newest chapter as code. The rest is below, in words.

### Chapter 1: games (2008 to 2018)

Unity3D, mostly. A military training simulation that won the Serious Games Showcase & Challenge 2013, ahead of entries from the FBI and the US Army. Word games that reached the worldwide top 10 in their category. The official Gardens by the Bay app. AR/VR work. Along the way I taught an AI & Agent Systems diploma module and worked with the Singapore-MIT GAMBIT Game Lab. Degree: BSc (Hons) Games Programming, First Class Honours, Middlesex University.

### Chapter 2: healthcare robotics (2018 to now)

I work at CHART, the Centre for Healthcare Assistive and Robotics Technology at Changi General Hospital. It is Singapore's centre of excellence for healthcare robotics and automation. I lead the UI engineering team and I'm the most senior engineer in the wider group.

The work, at the level I can talk about publicly:

- Architecture and UI direction for the RMF 2.0 robotics dashboard that nurses, porters and support staff use to work with robot fleets. Built on [Open-RMF](https://www.open-rmf.org/), the open-source multi-fleet orchestration framework running in multiple Singapore hospitals.
- Initiated a task-orchestration layer above RMF for real ward workflows, beyond my team's scope, and collaborated with Intrinsic (Alphabet's robotics company) on it.
- Co-authored and co-presented RoMi-H, Singapore's healthcare robotics middleware, at ROSCon 2022.
- Helped deploy a ward robot across 6+ hospital sites during COVID, when it mattered most.
- Go-to demo lead: ministers, hospital CEOs, overseas delegations.

None of that can be public code. It is hospital infrastructure and employer IP, which is exactly how it should be. That is why the repos on this profile skew recent: GitHub is the one surface where I can only show self-owned work.

### Chapter 3: AI-native (2025 to now)

Outside work I ship consumer AI products solo, end to end.

| Product | What it is | Receipts |
|---|---|---|
| **[HalalSnap](https://halalsnap.org)** | AI halal scanner. Snap any product, get a grounded verdict with per-ingredient reasoning | Both app stores · 1,300+ users · 30 languages (incl. RTL) · featured in Berita Harian |
| **[Kakis](https://kakis.app)** | Pickup futsal for Singapore: find a game, tap in, split the court cost | Empty repo to live in production in 1 day (React/TS/Supabase/Vercel) |
| **[Kancil](https://getkancil.app)** | Gamified Bahasa Melayu learning for primary schoolers, MOE-syllabus aligned | First commit to both app stores in 10 days |

*(Product repos are private. They are real businesses with real users. I'm happy to walk through any part of any of them, architecture to eval suites.)*

### How I build

AI agents write most of my code. What makes it production-grade is the system around them:

- **Spec-driven**: every feature starts as a written spec; decisions get locked so future sessions can't relitigate them
- **Eval harnesses**: golden test sets with trap cases, LLM-as-judge scoring, accuracy as a non-regression gate. I switched my production model on eval evidence and halved scan time. The pattern is public code: [llm-eval-harness](https://github.com/razilzul/llm-eval-harness)
- **Gates everywhere**: typecheck blocks deploys, staging first, production gated behind a human, "verified by LLM" then "verified by me" on the board
- **Device-level proof**: Maestro drives a real phone every release, screenshot proof or it didn't happen
- **Model routing**: match the model to the task's ambiguity, not its size

This isn't just how I work alone. I led my team's adoption of AI-assisted development and built a Responsible AI Development workshop around the same discipline. The workshop deck is public, built as slides-as-code: [responsible-ai-workshop](https://github.com/razilzul/responsible-ai-workshop)

### Elsewhere

- 💼 [LinkedIn](https://www.linkedin.com/in/razil-zul-8363185)
- 📫 razil.zul@gmail.com
