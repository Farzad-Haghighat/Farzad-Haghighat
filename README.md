# Hey, I'm Farzad 👋

Full-stack engineer and hands-on technical PM. I build AI-native systems end to end: multi-agent orchestration, model-agnostic pipelines, and the full-stack product around them. Two companies co-founded and 10+ years shipping to real users, so I weigh engineering calls by what they do for the product: revenue, cost, retention. Happiest deep in the hard part: integration sprawl, identity resolution, cost and reliability under load.

---

## 🎮 GameScrobbler · Co-Founder & CTO · [gamescrobbler.com](https://gamescrobbler.com)

Unified gaming data platform (think Last.fm for games), tracking play across every major service.

- 🔌 **9 platform integrations** (Steam, Xbox, PlayStation, Nintendo, Epic, Google Play, Playnite, Overwolf, Discord), each with its own auth path (OAuth, NPSSO, friend codes, per-install tokens), every client an isolated package to keep third-party API churn out of the core.
- 🧩 **Cross-provider game identity**: the same title resolves to different IDs across stores (editions, bundles, regional SKUs). Store literal IDs, roll variants up at read time, keep per-store provenance intact.
- 🏗 **8-app monorepo** (pnpm/Turborepo): Next.js 16 frontend, Express API, Cloudflare Worker cron, Discord bots, a ChatGPT MCP app, behind shared typed packages.
- 🚀 ~10K users on **zero paid acquisition** by building where players already were: a community-adopted Playnite extension past **12k+ downloads**.

`Next.js 16` · `Express` · `PostgreSQL/Prisma` · `Redis/BullMQ` · `Cloudflare Workers` · `embeddings`

🔗 **Open source:** [game-scrobbler/gs-playnite](https://github.com/game-scrobbler/gs-playnite), the Playnite plugin (C#, GPL-3.0) with a public REST API and MCP server.

[![gs-playnite](https://github-readme-stats.vercel.app/api/pin/?username=game-scrobbler&repo=gs-playnite&theme=default)](https://github.com/game-scrobbler/gs-playnite)

---

## 🤖 Bupple · Technical PM & Senior Engineer · *(Jun 2025 - May 2026)* · [bupple.io](https://bupple.io)

AI-native content platform. Built the agentic and media-generation systems end to end.

- 🧠 **Prism**: model-agnostic media generation. Models, schemas, and pricing pulled live from fal.ai and cached, so any of **1,000+ models** (Veo, Sora, Kling, Luma) ships with zero code changes.
- 🤝 **Multi-agent orchestration on Mastra**: a brand-aware supervisor delegating to specialized subagents, with native tool-approval (suspend/resume) wired across backend and frontend.
- 🛠 **LLMOps**: versioned prompt registry, per-call token and cost accounting, plan-tier capability gating signed into service-to-service JWTs.
- 💸 **Cost + reliability**: cut a vision step ~12x (gpt-4o to gpt-5.4-nano) after a quality eval, and fixed a circuit-breaker fallback that had been silently 404-ing on every call.

`Next.js 16` · `NestJS` · `Mastra` · `MongoDB` · `Redis/BullMQ` · `AWS Lambda` · `OpenAI / FAL / Gemini`

---

## 🧰 Muncher · indie studio · [muncherhq.com](https://muncherhq.com) · [@MuncherHQ](https://github.com/MuncherHQ)

Privacy-first utility apps.

- **FileMuncher**: 40+ file tools (PDF, image, video) running **100% client-side**, zero uploads, with in-browser AI background removal via Transformers.js.
- **BetaMuncher**: native **Android (Kotlin)** for discovering open Google Play betas, open-core with a paid Pro tier.

---

## 🧪 etkinbul · [etkinbul.com](https://etkinbul.com)

Event aggregation platform. LLM extraction agents (Gemini + Playwright) over ~79 sources every 6 hours on a Hetzner VPS, served through a multilingual Next.js frontend with PostgreSQL full-text search.

---

## 🛠 Stack

```text
Languages   TypeScript · Python · Kotlin
Frontend    Next.js · React
Backend     Node · NestJS · Express
Data        PostgreSQL · Prisma · MongoDB · Redis
Infra       Cloudflare Workers · Vercel · AWS
AI          Mastra · MCP · LLMOps · embeddings · OpenAI / FAL / Gemini
Workflow    pnpm/Turborepo monorepos · conventional commits · AI-assisted dev (Claude Code, Taskmaster)
```

Earlier: the data infrastructure, anomaly-detection systems, and experimentation platforms behind **5X revenue** at RIWI and **4X funnel conversion** at ROM; co-founded EasyPaz (Iran's first meal-kit service, **$300K seed** from Sarava).

---

## 💬 Connect

Open to full-stack engineering and technical roles in agentic AI, AI infrastructure, and AI-native SaaS.

[![LinkedIn](https://img.shields.io/badge/-farzad--haghighat-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/farzad-haghighat/)
