## Hi, I'm Rz 👋

Full-stack engineer in Singapore, 18+ years shipping software — games, AR/VR, healthcare robotics, and now AI-native product development. By day I build the software layer for robotics and automation in healthcare. Outside work, I ship consumer AI products solo, end to end.

### What I've shipped solo (2025–2026)

| Product | What it is | Receipts |
|---|---|---|
| **[HalalSnap](https://halalsnap.org)** | AI halal scanner — snap any product, get a grounded verdict with per-ingredient reasoning | Both app stores · 1,300+ users · 30 languages (incl. RTL) · featured in Berita Harian |
| **[Kakis](https://kakis.app)** | Pickup futsal for Singapore: find a game, tap in, split the court cost | Empty repo → live in production in 1 day (React/TS/Supabase/Vercel) |
| **[Kancil](https://getkancil.app)** | Gamified Bahasa Melayu learning for primary schoolers, MOE-syllabus aligned | First commit → submitted to both app stores in 10 days |

*(Product repos are private — they're real businesses with real users — but I'm happy to walk through any part of any of them, architecture to eval suites.)*

### How I build

AI agents write most of my code. What makes it production-grade is the system around them:

- **Spec-driven**: every feature starts as a written spec; decisions get locked so future sessions can't relitigate them
- **Eval harnesses**: golden test sets, LLM-as-judge scoring — I switched my production model on eval evidence and halved scan time
- **Gates everywhere**: typecheck blocks deploys, staging first, production gated behind a human, "verified by LLM" then "verified by me" on the board
- **Device-level proof**: Maestro drives a real phone every release, screenshot proof or it didn't happen
- **Model routing**: match the model to the task's ambiguity, not its size

### Elsewhere

- 🎤 ROSCon 2022 speaker (healthcare robotics middleware)
- 🏆 Past life: award-winning serious games, top-10 worldwide word games, the official Gardens by the Bay app
- 💼 [LinkedIn](https://www.linkedin.com/in/razil-zul-8363185)
- 📫 razil.zul@gmail.com
