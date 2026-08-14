<h1 align="center">Hey, I'm Erick Dronski 👋</h1>

<p align="center">
  <strong>Value Engineer @ Ivanti · I build open-source tooling for AI coding agents, plus native iOS and data products — from App Store releases to live market systems.</strong>
</p>

<p align="center">
  <a href="https://apps.apple.com/us/app/nalee/id6785313667">App Store release</a> ·
  <a href="https://erickdronski.com">Portfolio</a> ·
  <a href="https://github.com/erickdronski?tab=repositories&type=source">Public source</a> ·
  <a href="https://github.com/erickdronski?tab=achievements">GitHub achievements</a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/erickdronski">LinkedIn</a> ·
  <a href="https://x.com/DronskiErick">X/Twitter</a> ·
  <a href="https://www.tiktok.com/@dr0nski">TikTok</a>
</p>

---

### Open source — tooling for AI coding agents

Small, standalone tools. All MIT, all zero-dependency, all with real test suites.

| Repo | What it does |
| --- | --- |
| **[agentsmith](https://github.com/erickdronski/agentsmith)** | Mines your repo's *actual* conventions into an `AGENTS.md`, with evidence for every rule — and detects drift in CI when the file and the repo disagree. No LLM, no network. |
| **[burnrate](https://github.com/erickdronski/burnrate)** | What your coding agent actually cost, read from local session logs, plus a hook that caps spend mid-session. Fixes a ~3× overcount that naive token counters hit. |
| **[tripwire](https://github.com/erickdronski/tripwire)** | Offline audit of the skills, MCP servers, hooks, and permissions installed for your agent. Shows your real capability surface, then flags how it can be turned against you. |
| **[contexttest](https://github.com/erickdronski/contexttest)** | A/B testing for `AGENTS.md`. Runs the same task from the same commit under two instruction sets and reports which one measurably worked. |
| **[gtm-skills](https://github.com/erickdronski/gtm-skills)** | Nine production-grade go-to-market skills for agents — business cases, ICP scoring, pricing, market sizing — on a tested arithmetic engine with an assumption ledger. |

A theme runs through all five: **be honest about what you don't know.** The
business cases grade their own evidence, the convention miner refuses to assert
a rule from four files, the cost tool names models it can't price instead of
costing them at zero, and the security scanner treats a false positive as the
failure mode that matters.

### Shipping ledger

| Product | State | Built with | Proof |
| --- | --- | --- | --- |
| **Nalee** — honest product-toxin scoring backed by a 2.4M+ product library | Live on the App Store | Expo · Supabase | [App Store](https://apps.apple.com/us/app/nalee/id6785313667) · [Site](https://nalee.app) |
| **Goals** — a cinematic goal-discovery and execution command center for turning intention into daily progress | iOS / TestFlight lane + live web | SwiftUI · TypeScript · Supabase | [Live](https://goals-phi-seven.vercel.app) · Private source |
| **Tapt** — beer discovery, Passport collecting, and a live beer market | Native iOS release lane | Swift · Supabase | [Source](https://github.com/erickdronski/tapt) · [Site](https://taptbeer.com) |
| **Mend** — a free, private journey and shared-space app for relationship repair | TestFlight | Expo · TypeScript · Supabase | [Source](https://github.com/erickdronski/mend-app) |
| **Lore** — geospatial place stories hiding in the streets around you | Native iOS / TestFlight lane | Swift · Supabase | [Source](https://github.com/erickdronski/lore-ios) |
| **Precision Algorithms** — a published prediction-market models desk | Live web product | Data · Web | [Live](https://precisionalgorithms.com) |
| **SqueezeRadar** — short-squeeze signals with live price overlays | Live web product | Next.js · Market data | [Live](https://short-squeeze-radar.vercel.app) |
| **Penny Catcher** — volume and flow radar for quiet, low-priced tickers | Live web product | Web · Market data | [Live](https://penny-catcher.vercel.app) |

### Engineering proof

[agentsmith CI](https://github.com/erickdronski/agentsmith/blob/main/.github/workflows/ci.yml) (Python 3.9–3.13 + self-audit) · [tripwire CI](https://github.com/erickdronski/tripwire/blob/main/.github/workflows/ci.yml) (plants a live attack each run) · [Tapt release automation](https://github.com/erickdronski/tapt/tree/main/.github/workflows) · [Lore CI and TestFlight](https://github.com/erickdronski/lore-ios/blob/main/.github/workflows/ios-testflight.yml) · [Merged pull requests](https://github.com/search?q=author%3Aerickdronski+is%3Apr+is%3Amerged&type=pullrequests) · [Achievements](https://github.com/erickdronski?tab=achievements)

### Day job

**Ivanti** · Value engineering and AI adoption strategy for enterprise clients. I built the [Capability & Maturity Assessment](https://www.ivanti.com/resources/capabilities) framework.

### Working stack

- **Native:** Swift, SwiftUI, Expo, React Native
- **Web:** TypeScript, Next.js, React, Tailwind CSS, Node.js
- **Data and delivery:** Supabase, Python, GitHub Actions, Vercel
- **Agent tooling:** Claude Code skills and plugins, MCP, static analysis, dependency-free Python CLIs

### Beyond the build

- MBA, Data Analytics concentration — Rowan University
- First-generation Polish-American, based in New Jersey
- 18K+ LinkedIn followers and 3× Top Voice
- Philly sports across all four, golf whenever possible
- 130 memorized digits of Pi, listed on the [Pi World Ranking List](https://www.pi-world-ranking-list.com/?page=lists&category=pi)

---

<p align="center">
  <a href="https://apps.apple.com/us/app/nalee/id6785313667">
    <img alt="Nalee — live on the App Store" src="https://img.shields.io/badge/Nalee-Live_on_the_App_Store-34C759?style=for-the-badge&logo=apple&logoColor=white" />
  </a>
  <a href="https://github.com/erickdronski?tab=repositories&q=&type=source&language=python">
    <img alt="Open-source agent tooling" src="https://img.shields.io/badge/Open_Source-Agent_Tooling-6b21a8?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://erickdronski.com">
    <img alt="Portfolio — erickdronski.com" src="https://img.shields.io/badge/Portfolio-erickdronski.com-0F1E35?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/erickdronski">
    <img alt="LinkedIn — 18K+ followers" src="https://img.shields.io/badge/LinkedIn-18K+_Followers-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
