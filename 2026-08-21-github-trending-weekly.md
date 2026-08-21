---
date: 2026-08-21
period: weekly
period_start: 2026-08-14
period_end: 2026-08-21
source: GitHub Trending (since=weekly primary + since=daily fill)
total: 20
notes: GitHub trending HTML rendered 18 weekly repos; Top 20 filled with 2 strongest daily-only repos by GitHub's daily ranking. Ranking order preserved as displayed by GitHub. Star counts taken directly from GitHub trending page display values.
---

# GitHub Trending Weekly - 2026-08-21

**Captured**: 2026-08-21 18:00 Asia/Taipei  
**Window**: 2026-08-14 ~ 2026-08-21 (past 7 days)  
**Source**: [GitHub Trending](https://github.com/trending) Overall (weekly primary + daily fill)

## This Week's Top 20

1. **[cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)** - 38 editorial diagram types for Claude Code, Codex, and Pi. Self-contained HTML + SVG. No shadows. No Mermaid slop.
   - Lang: `HTML` | Trending stars: 11,325 stars this week

2. **[modular/modular](https://github.com/modular/modular)** - The Modular Platform (includes MAX & Mojo)
   - Lang: `Mojo` | Trending stars: 744 stars this week

3. **[volcengine/OpenViking](https://github.com/volcengine/OpenViking)** - Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills.
   - Lang: `Python` | Trending stars: 2,444 stars this week

4. **[basecamp/omarchy](https://github.com/basecamp/omarchy)** - Beautiful, Modern & Opinionated Linux
   - Lang: `Shell` | Trending stars: 2,395 stars this week

5. **[AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)** - ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HID++. No account, no telemetry.
   - Lang: `Rust` | Trending stars: 2,674 stars this week

6. **[cactus-compute/needle](https://github.com/cactus-compute/needle)** - 14MB foundation model for tiny devices; phones, wearables, smart home, and robots.
   - Lang: `Python` | Trending stars: 3,409 stars this week

7. **[semantica-agi/semantica](https://github.com/semantica-agi/semantica)** - Graph-Native Infrastructure for Context and Accountable AI Systems
   - Lang: `Python` | Trending stars: 3,674 stars this week

8. **[NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard)** - Switchyard lets LLM applications route traffic across models and providers while preserving native OpenAI and Anthropic API compatibility - enabling flexible model selection, benchmarking, and cost/performance optimization.
   - Lang: `Rust` | Trending stars: 932 stars this week

9. **[akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)** - Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors
   - Lang: `Rust` | Trending stars: 1,952 stars this week

10. **[harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)** - 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.
   - Lang: `Python` | Trending stars: 9,712 stars this week

11. **[public-apis/public-apis](https://github.com/public-apis/public-apis)** - A collective list of free APIs
   - Lang: `Python` | Trending stars: 11,259 stars this week

12. **[megadose/holehe](https://github.com/megadose/holehe)** - holehe allows you to check if the mail is used on different sites like twitter, instagram and will retrieve information on sites with the forgotten password function.
   - Lang: `Python` | Trending stars: 1,632 stars this week

13. **[lightningpixel/modly](https://github.com/lightningpixel/modly)** - Desktop app to generate 3D models from images or prompt using local AI — runs entirely on your GPU
   - Lang: `TypeScript` | Trending stars: 1,855 stars this week

14. **[macro-inc/macro](https://github.com/macro-inc/macro)** - Macro is a unified workspace for teams: email, chat, docs, tasks, agents, calls, and CRM — @-linked together with shared AI memory.
   - Lang: `Rust` | Trending stars: 1,456 stars this week

15. **[unslothai/unsloth](https://github.com/unslothai/unsloth)** - Local UI to run and train LLMs and diffusion models, including Qwen3.8, Kimi K3, MiniMax-H3, Gemma 4, DeepSeek-V4, FLUX and more.
   - Lang: `Python` | Trending stars: 3,300 stars this week

16. **[jundot/omlx](https://github.com/jundot/omlx)** - LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu bar
   - Lang: `Python` | Trending stars: 1,388 stars this week

17. **[AlexsJones/llmfit](https://github.com/AlexsJones/llmfit)** - Hundreds of models & providers. One command to find what runs on your hardware.
   - Lang: `Rust` | Trending stars: 1,842 stars this week

18. **[CodebuffAI/freebuff](https://github.com/CodebuffAI/freebuff)** - The free coding agent
   - Lang: `TypeScript` | Trending stars: 1,133 stars this week

19. **[mattpocock/skills](https://github.com/mattpocock/skills)** _(daily fill)_ - Skills for Real Engineers. Straight from my .agents directory.
   - Lang: `Shell` | Trending stars: 2,192 stars today

20. **[obra/superpowers](https://github.com/obra/superpowers)** _(daily fill)_ - An agentic skills framework & software development methodology that works.
   - Lang: `Shell` | Trending stars: 727 stars today

## Observations

- **AI agents and skills dominate the chart** (7/20): skills catalogs (3) - cathrynlavery/diagram-design, mattpocock/skills, obra/superpowers; coding agents (1) - CodebuffAI/freebuff; agent infra (3) - volcengine/OpenViking, semantica-agi/semantica, akitaonrails/ai-memory. Every cluster is either a Claude Code plugin / skill catalog, a coding agent harness, or context-database support for agents.
- **Local / on-device AI is its own coherent branch** (4/20): cactus-compute/needle, unslothai/unsloth, jundot/omlx, AlexsJones/llmfit. Different layers (foundation model, runtime, hardware matcher, local UI) - same bet: 'runs locally' is becoming a real category, not just a tagline.
- **AI infra + safety add up to a third pole** (2/20): infra - modular/modular, NVIDIA-NeMo/Switchyard (modular/modular's MAX/Mojo platform, NVIDIA-NeMo/Switchyard model routing); safety/red team does not crack Top 20 this week (Tencent/AI-Infra-Guard is on daily-only outside the cut).
- **Language split: Rust + Python + TypeScript + Shell dominate**. Rust 5, Python 8, TypeScript 2, Shell 3, Mojo 1, HTML 1. Rust clusters in AI infra and hardware; Python in AI stacks; TypeScript in plugin/UI surfaces; Shell in skills catalogs (markdown-heavy).
- **Anomalies worth a sanity check**: cathrynlavery/diagram-design (11,325 stars this week) and public-apis/public-apis (11,259 stars this week) both display weekly counts well above typical for niche / long-running repos. Could be a GitHub display quirk or genuine viral moment - flagging for next week's check.

---

_Generated by cron job at Friday 18:00 Asia/Taipei._