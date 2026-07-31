---
date: 2026-07-31
period: 2026-07-24 ~ 2026-07-31
source:
  - https://github.com/trending
  - https://github.com/trending?since=weekly
  - https://api.github.com/repos/<owner>/<repo>
total: 20
generated_by: horo-trending-cron
---

# GitHub Trending 週報 — 2026-07-31

## 本週 Top 20

1. **[huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)** — ⭐ 9,490 — Build local voice agents with open-source models.
2. **[microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners)** — ⭐ 54,770 — 12 Weeks, 24 Lessons, AI for All!
3. **[paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading)** — ⭐ 11,417 — Curated list of awesome libraries, packages, strategies, books, blogs, tutorials, papers for systematic trading.
4. **[different-ai/openwork](https://github.com/different-ai/openwork)** — ⭐ 19,070 — The open-source alternative to Claude Cowork (powered by opencode).
5. **[WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys)** — ⭐ 10,518 — Socket-based TS/JavaScript API for WhatsApp Web.
6. **[pascalorg/editor](https://github.com/pascalorg/editor)** — ⭐ 20,333 — Create and share 3D architectural projects.
7. **[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)** — ⭐ 55,816 — AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web — then synthesizes a grounded summary.
8. **[dotnet/aspnetcore](https://github.com/dotnet/aspnetcore)** — ⭐ 38,331 — ASP.NET Core, a cross-platform .NET framework for building modern cloud-based web applications.
9. **[microsoft/PowerToys](https://github.com/microsoft/PowerToys)** — ⭐ 137,287 — Microsoft PowerToys: a collection of utilities that supercharge productivity on Windows.
10. **[ansible/ansible](https://github.com/ansible/ansible)** — ⭐ 69,984 — Ansible: a radically simple IT automation platform that makes your applications and systems easier to deploy.
11. **[ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)** — ⭐ 48,232 — Chrome DevTools for coding agents (MCP server).
12. **[jenkinsci/jenkins](https://github.com/jenkinsci/jenkins)** — ⭐ 26,366 — Jenkins automation server.
13. **[agavra/tuicr](https://github.com/agavra/tuicr)** — ⭐ 1,995 — A code review TUI with vim keybindings.
14. **[affaan-m/ECC](https://github.com/affaan-m/ECC)** — ⭐ 236,457 — The agent harness performance optimization system: skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.
15. **[block/buzz](https://github.com/block/buzz)** — ⭐ 18,868 — A hive mind communication platform.
16. **[citrolabs/ego-lite](https://github.com/citrolabs/ego-lite)** — ⭐ 6,801 — The fastest browser for AI agents to run browser automation, built for sharing your agent.
17. **[koala73/worldmonitor](https://github.com/koala73/worldmonitor)** — ⭐ 77,216 — Real-time global intelligence dashboard: AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface.
18. **[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)** — ⭐ 14,470 — A skill to stop your coding agent from burying the answer; ADHD-friendly output.
19. **[alibaba/open-code-review](https://github.com/alibaba/open-code-review)** — ⭐ 16,821 — Open-source & free — battle-tested at Alibaba's scale; hybrid architecture code review.
20. **[mattpocock/skills](https://github.com/mattpocock/skills)** — ⭐ 197,090 — Skills for Real Engineers, straight from my .agents directory.

## 觀察

- **AI agent 工具仍是主旋律**：本週 20 個 repo 中，至少 9 個與 AI agent / coding agent 直接相關 —— `huggingface/speech-to-speech`（本地語音代理）、`different-ai/openwork`（Claude Cowork 開源替代）、`mvanhorn/last30days-skill`、`ChromeDevTools/chrome-devtools-mcp`（coding agent 用的 MCP）、`agavra/tuicr`（給 agent / dev 用的 code review TUI）、`affaan-m/ECC`（agent harness 性能優化）、`citrolabs/ego-lite`（給 AI agent 用的瀏覽器）、`ayghri/i-have-adhd`（coding agent 行為 skill）、`mattpocock/skills`（agent skills 集合）。其餘觀察類與 infra 類 repo 也大量與「給 agent 跑」有關 —— agent 生態已從 prompt hack 進到 harness / TUI / browser / skill pack 的工程化深水區。
- **語言分佈明顯偏向 TypeScript 與 Python**：TypeScript 約 6 個（`different-ai/openwork`、`pascalorg/editor`、`ChromeDevTools/chrome-devtools-mcp`、`koala73/worldmonitor`、`moeru-ai/airi` 進 weekly-only 沒入榜），Python 約 5 個（`huggingface/speech-to-speech`、`paperswithbacktest/awesome-systematic-trading`、`mvanhorn/last30days-skill`、`ansible/ansible`、`ayghri/i-have-adhd`），Rust 3 個（`agavra/tuicr`、`block/buzz`、`tokio-rs/topcoat`），JavaScript 2 個，Java / C# / C / Go / Shell 各 1 個。TypeScript + Python 合計過半，呼應 agent 生態以腳本化 + 前端 dashboard 為主軸。
- **瀏覽器自動化 + MCP 化**：兩條平行趨勢 —— 一邊是 `citrolabs/ego-lite` 為 AI agent 量身打造的瀏覽器、配合 `ChromeDevTools/chrome-devtools-mcp` 走 MCP 標準；另一邊 `pascalorg/editor` 把 3D 編輯器放到瀏覽器。本週明顯的「AI agent 第一公民」基建潮 —— 把通用工具改造為 agent 友善介面（MCP server、TUI、skill pack、specialized browser）。
- **「Skill 化」是 agent 工程的下一個抽象層**：`ayghri/i-have-adhd`、`mvanhorn/last30days-skill`、`mattpocock/skills` 三個 repo 都在做「可掛載的 agent skill / 行為包」，顯示 community 正在把 prompt + tool config 收斂成可分享的 skill 單位（與 Hermes 的 skill 概念同源）。`affaan-m/ECC` 進一步把「harness performance optimization」做成系統 —— agent 從「會呼叫工具」演進到「有持久化記憶、行為準則、安全策略」。
- **巨型老牌專案靠 AI 熱度二次衝榜**：`microsoft/PowerToys`（137K ⭐）、`ansible/ansible`（70K ⭐）、`dotnet/aspnetcore`（38K ⭐）、`jenkinsci/jenkins`（26K ⭐）都是 5~10 年以上的老專案，本週卻進入 trending，顯示「AI-assisted sysadmin / dev tooling」正在讓傳統 IT 自動化框架重新被翻出來用 —— 不只是新創 AI 工具，老牌 infra 也在被 AI 工作流重新包裝使用。
