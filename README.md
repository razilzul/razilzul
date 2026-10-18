## Hi, I'm Rz 👋

Full-stack engineer in Singapore. 18+ years shipping software in three chapters: a decade of award-winning games, then 8 years building the software layer for hospital robotics at Singapore's national centre for healthcare robotics, and now AI-native product development on the side of that. Most of my career is employer or client IP, so this profile can only show the newest chapter as code. The rest is below, in words.

### Chapter 1: games (2008 to 2018)

Unity3D, mostly. A military training simulation that won the Serious Games Showcase & Challenge 2013, ahead of entries from the FBI and the US Army. Word games that reached the worldwide top 10 in their category. The official Gardens by the Bay app. AR/VR work. Along the way I taught an AI & Agent Systems diploma module and worked with the Singapore-MIT GAMBIT Game Lab. Degree: BSc (Hons) Games Programming, First Class Honours, Middlesex University.

### Chapter 2: healthcare robotics (2018 to now)

I work at CHART, the Centre for Healthcare Assistive and Robotics Technology at Changi General Hospital. It is Singapore's centre of excellence for healthcare robotics and automation. I lead the UI engineering team and I'm the most senior engineer in the wider group.

The work, at the level I can talk about publicly:

- Architecture and UI direction for the RMF 2.0 robotics dashboard that nurses, porters and support staff use to work with robot fleets. Built on [Open-RMF](https://www.open-rmf.org/), the open-source multi-fleet orchestration framework running in multiple Singapore hospitals.
- Assisted the development of Dynamic Events for Open-RMF, co-developed with Intrinsic (Alphabet's robotics company), and initiated what it led to: VETO, a visual task orchestrator for real ward workflows, driving Dynamic Events from Node-RED flows. That work is public: my team [presented it at ROSCon 2025](https://vimeo.com/1136163298), the Dynamic Events design ran [in the open with Open-RMF's lead](https://discourse.openrobotics.org/t/dynamic-event-632/44547), and the RMF Node-RED nodes are [published for anyone to use](https://flows.nodered.org/node/@chart-sg/node-red-rmf).
- Co-authored and co-presented Singapore's healthcare robotics middleware story at ROSCon 2022: [From Lab to Ward, RMF Implementation in Healthcare & Beyond](https://vimeo.com/767149623) ([slides](http://download.ros.org/downloads/roscon/2022/From%20Lab%20to%20Ward%20-%20RMF%20Implementation%20in%20Healthcare%20_%20Beyond.pdf)).
- Helped deploy a ward robot across 6+ hospital sites during COVID, when it mattered most.
- Go-to demo lead: ministers, hospital CEOs, overseas delegations.

None of that can be public code. It is hospital infrastructure and employer IP, which is exactly how it should be. That is why the repos on this profile skew recent: GitHub is the one surface where I can only show self-owned work.

### Chapter 3: AI-native (2025 to now)

Outside work I build personal learning projects with my 10-year-old son, from my own and my family's needs. They are a self-funded learning investment, built on evenings and weekends, and what I learn feeds back into my day job.

| Product | What it is | Receipts |
|---|---|---|
| **[HalalSnap](https://halalsnap.org)** | AI halal scanner. Snap any product, get a grounded verdict with per-ingredient reasoning | Both app stores · 1,500+ users · 6,000+ scans · 30 languages (incl. RTL) · [featured in Berita Harian](https://www.beritaharian.sg/singapura/jurutera-perisian-hasilkan-halalsnap-permudah-semakan-status-halal-guna-ai) |
| **[Kakis](https://kakis.app)** | Pickup futsal for Singapore: find a game, tap in, split the court cost | Empty repo to live in production in 1 day (React/TS/Supabase/Vercel) |
| **[Kancil](https://getkancil.app)** | Gamified Bahasa Melayu learning for primary schoolers, MOE-syllabus aligned | First commit to both app stores in 10 days · live on both app stores since Sep 2026 · [Berita Harian front page, 17 Oct 2026](https://www.beritaharian.sg/mata-mata/3060249/anak-10-tahun-jadi-bos-bantu-bapa-bangun-aplikasi-belajar-bahasa-melayu) · [try it in the browser](https://kancil.expo.app) |

*(The product repos are private. I'm happy to walk through any part of them, architecture to eval suites.)*

### How I build

AI agents write most of my code. What makes it production-grade is the system around them:

- **Spec-driven**: every feature starts as a written spec; decisions get locked so future sessions can't relitigate them
- **Eval harnesses**: golden test sets with trap cases, LLM-as-judge scoring, accuracy as a non-regression gate. I switched my production model on eval evidence and cut median scan time by about 40% at equal or better quality. The pattern is public code: [llm-eval-harness](https://github.com/razilzul/llm-eval-harness)
- **Gates everywhere**: typecheck blocks deploys, staging first, production gated behind a human, "verified by LLM" then "verified by me" on the board
- **Device-level proof**: Maestro drives a real phone every release, screenshot proof or it didn't happen
- **Model routing**: match the model to the task's ambiguity, not its size

This isn't just how I work alone. I led my team's adoption of AI-assisted development and built a Responsible AI Development workshop around the same discipline. The workshop deck is public, built as slides-as-code: [responsible-ai-workshop](https://github.com/razilzul/responsible-ai-workshop)

### Elsewhere

- 💼 [LinkedIn](https://www.linkedin.com/in/razil-zul-8363185)
- 📫 razil.zul@gmail.com
