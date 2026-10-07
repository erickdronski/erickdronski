<h1 align="center">Hey, I'm Erick Dronski 👋</h1>

<p align="center">
  <strong>Value engineer and agentic AI enablement. I build open-source tooling for AI coding agents, plus native iOS and data products — from App Store releases to live market systems.</strong>
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

Small, standalone tools. All MIT, all zero-dependency, all with CI, tagged
releases, and test suites — 1,055 tests across the five — and each one checked
against a real workstation, not only against fixtures.

| Repo | What it does | Release |
| --- | --- | --- |
| **[agentsmith](https://github.com/erickdronski/agentsmith)** | Mines your repo's *actual* conventions into `AGENTS.md` — and `CLAUDE.md`, Cursor rules, and Copilot instructions — with evidence for every rule, then catches drift in CI. No LLM, no network. | v0.2.1 · 216 tests |
| **[burnrate](https://github.com/erickdronski/burnrate)** | What Claude Code and Codex sessions actually cost, from local logs, plus a hook that caps spend mid-session. Prices cache reads per model and counts each response once — on a real machine, flat cache pricing overstated Claude spend by 50%, and naive counting doubled Codex tokens. | v0.2.0 · 204 tests |
| **[tripwire](https://github.com/erickdronski/tripwire)** | Offline audit of every skill, MCP server, hook, and permission across Claude Code, Claude Desktop, Cursor, and Codex. On a real workstation, v0.1 raised 32 high-severity findings that were all false; v0.2 raises one, and it is real. | v0.2.0 · 196 tests |
| **[contexttest](https://github.com/erickdronski/contexttest)** | A/B testing for instruction files: same task, same commit, two rule sets, paired statistics. Ablates sections, pools repeated runs, compares agents — and checks that the agent actually received the instructions. | v0.3.1 · 113 tests |
| **[gtm-skills](https://github.com/erickdronski/gtm-skills)** | Nine go-to-market skills for agents — business cases, MEDDPICC deal qualification, pipeline forecasts, pricing, market sizing — on a tested arithmetic engine with an assumption ledger. | v0.2.0 · 326 tests |
| **[contexttest-findings](https://github.com/erickdronski/contexttest-findings)** | Pre-registered experiments on instruction-file rules across Claude Code and Codex. A rule carrying a convention the code lacks moved success from 1/10 to 10/10; a popular scope rule did almost nothing. Includes a published correction of its own first result. | 70 live trials |

A theme runs through all of them: **be honest about what you don't know.** The
business cases grade their own evidence, the convention miner refuses to assert
a rule from four files, the cost tool names models it can't price instead of
costing them at zero, the security scanner treats a false positive as the
failure mode that matters — and when the findings repo discovered its first
result was invalid, it published the retraction next to the data.

### Shipping ledger

| Product | State | Built with | Proof |
| --- | --- | --- | --- |
| **Nalee** — honest product-toxin scoring backed by a 2.4M+ product library | Live on the App Store | Expo · Supabase | [App Store](https://apps.apple.com/us/app/nalee/id6785313667) · [Site](https://nalee.app) |
| **Lore** — geospatial place stories hiding in the streets around you | Live on the App Store | Swift · Supabase | [App Store](https://apps.apple.com/us/app/lore-ar-city-history-guide/id6788171860) · [Source](https://github.com/erickdronski/lore-ios) |
| **Goals** — a cinematic goal-discovery and execution command center for turning intention into daily progress | iOS / TestFlight lane + live web | SwiftUI · TypeScript · Supabase | [Live](https://goals-phi-seven.vercel.app) · Private source |
| **Tapt** — beer discovery, Passport collecting, and a live beer market | Native iOS release lane | Swift · Supabase | [Source](https://github.com/erickdronski/tapt) · [Site](https://taptbeer.com) |
| **Mend** — a private app that helps couples connect, grow, and stay in sync | TestFlight | Expo · TypeScript · Supabase | [Source](https://github.com/erickdronski/mend-app) |
| **Precision Algorithms** — a published prediction-market models desk | Live web product | Data · Web | [Live](https://precisionalgorithms.com) |
| **SqueezeRadar** — short-squeeze signals with live price overlays | Live web product | Next.js · Market data | [Live](https://short-squeeze-radar.vercel.app) · Private source |
| **Penny Catcher** — volume and flow radar for quiet, low-priced tickers | Live web product | Next.js · Market data | [Live](https://penny-catcher.vercel.app) · Private source |

### Engineering proof

[agentsmith CI](https://github.com/erickdronski/agentsmith/blob/main/.github/workflows/ci.yml) (Python 3.9–3.13 on Linux, macOS, Windows + self-audit) · [tripwire CI](https://github.com/erickdronski/tripwire/blob/main/.github/workflows/ci.yml) (plants live attacks, Claude Code and Codex, every run) · [contexttest CI](https://github.com/erickdronski/contexttest/blob/main/.github/workflows/ci.yml) (Node 20/22/24 + GitHub Action end to end) · [Lore CI and TestFlight](https://github.com/erickdronski/lore-ios/blob/main/.github/workflows/ios-testflight.yml) · [Tapt release automation](https://github.com/erickdronski/tapt/tree/main/.github/workflows) · [Merged pull requests](https://github.com/search?q=author%3Aerickdronski+is%3Apr+is%3Amerged&type=pullrequests)

### Work

Value engineering and agentic AI enablement — helping teams adopt coding agents
and AI workflows, and measure what they actually return. Previously at Ivanti,
where I built the [Capability & Maturity Assessment](https://www.ivanti.com/resources/capabilities)
framework.

### Working stack

- **Native:** Swift, SwiftUI, Expo, React Native
- **Web:** TypeScript, Next.js, React, Tailwind CSS, Node.js
- **Data and delivery:** Supabase, Python, GitHub Actions, Vercel
- **Agent tooling:** Claude Code and Codex skills, plugins, and hooks; MCP; agent evaluation; static analysis; dependency-free Python CLIs

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
  <a href="https://apps.apple.com/us/app/lore-ar-city-history-guide/id6788171860">
    <img alt="Lore — live on the App Store" src="https://img.shields.io/badge/Lore-Live_on_the_App_Store-34C759?style=for-the-badge&logo=apple&logoColor=white" />
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
