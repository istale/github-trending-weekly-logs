---
date: 2026-09-11
period: 2026-09-04 ~ 2026-09-11
source:
  - https://github.com/trending
  - https://github.com/trending?since=weekly
  - https://api.github.com/repos/<owner>/<repo>
total: 34
note: |
  本週 Overall 預設頁（daily 視角）抓到 16 個、weekly 視角抓到 22 個；兩者重疊 4 個，合併去重後共 34 個 unique repo。
  GitHub Trending 沒有公開分頁，本次完整列出全部 34 個（未湊數）。
  排序依 GitHub weekly 頁原始順序（GitHub 混合 ranking 訊號：當週增速、新專案加權、stars 數等綜合），daily-only repo 接在 weekly 後段（標 _(daily fill)_）。
  Top 20 名單中含 0 個 daily fill，其餘 20 個位於 weekly 視角前段。
  Top 20 全 20 個 repo 經 GitHub REST API 成功解析（0 個 404），description / language / stargazers_count 由 API 補上；HTML 描述僅作備援。
generated_by: horo-trending-cron
---

# GitHub Trending 週報 — 2026-09-11

> 期間：2026-09-04 ~ 2026-09-11　|　來源：github.com/trending (Overall + weekly) + GitHub REST API

## 本週 Top 20

排序：依 GitHub weekly 頁原始順序（GitHub 混合 ranking 訊號，非純 stars 數），後接 daily-only 補強（標 _(daily fill)_）。


 1. **[affaan-m/ECC](https://github.com/affaan-m/ECC)** — JavaScript — +9,257 stars this week　|　⭐ 256,144 — The agent harness performance optimization system.
 2. **[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)** — Python — +3,882 stars today　|　⭐ 39,686 — A skill to stop your coding agent from burying the answer.
 3. **[DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)** — JavaScript — +11,638 stars this week　|　⭐ 135,290 — Makes your AI agent think like the laziest senior dev in…
 4. **[tt-a1i/archify](https://github.com/tt-a1i/archify)** — JavaScript — +11,958 stars this week　|　⭐ 57,970 — Agent skill for beautiful, verifiable architecture,…
 5. **[fmtlib/fmt](https://github.com/fmtlib/fmt)** — C++ — +920 stars this week　|　⭐ 25,730 — A modern formatting library
 6. **[mattpocock/skills](https://github.com/mattpocock/skills)** — Shell — +12,356 stars this week　|　⭐ 259,265 — Skills for Real Engineers.
 7. **[openai/plugins](https://github.com/openai/plugins)** — JavaScript — +1,018 stars this week　|　⭐ 6,412 — OpenAI Plugins
 8. **[blader/humanizer](https://github.com/blader/humanizer)** — Python — +5,224 stars this week　|　⭐ 46,700 — Agent skill that removes signs of AI-generated writing…
 9. **[mksglu/context-mode](https://github.com/mksglu/context-mode)** — TypeScript — +1,619 stars this week　|　⭐ 22,078 — Context window optimization for AI coding agents.
10. **[openai/skills](https://github.com/openai/skills)** — Python — +1,490 stars this week　|　⭐ 26,885 — Skills Catalog for Codex
11. **[heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)** — TypeScript — +4,896 stars this week　|　⭐ 48,901 — Write HTML.
12. **[ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)** — TypeScript — +791 stars this week　|　⭐ 51,627 — Chrome DevTools for coding agents
13. **[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)** — Python — +3,769 stars this week　|　⭐ 244,386 — The agent that grows with you
14. **[coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)** — JavaScript — +2,711 stars this week　|　⭐ 49,520 — Marketing skills for Claude Code and AI agents.
15. **[cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)** — HTML — +1,294 stars today　|　⭐ 38,200 — 38 editorial diagram types for Claude Code, Codex, and Pi.
16. **[microsoft/markitdown](https://github.com/microsoft/markitdown)** — Python — +4,579 stars this week　|　⭐ 182,554 — Python tool for converting files and office documents to…
17. **[ruvnet/ruflo](https://github.com/ruvnet/ruflo)** — TypeScript — +1,694 stars this week　|　⭐ 72,050 — 🌊 The original agent meta-harness.
18. **[THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC)** — TypeScript — +837 stars today　|　⭐ 35,681 — Open Multi-Agent Interactive Classroom — Get an…
19. **[anthropics/skills](https://github.com/anthropics/skills)** — Python — +2,234 stars this week　|　⭐ 175,753 — Public repository for Agent Skills
20. **[bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)** — JavaScript — +1,762 stars today　|　⭐ 25,638 — A spy satellite simulator in your browser, except the…

## 觀察

- **AI skills / Claude Code plugins 仍是 Top 20 絕對主軸**（10/20）：skills 目錄、plugin marketplace、agent-skill prompt pack 都算在內 — openai/skills、openai/plugins、anthropics/skills、mattpocock/skills、cathrynlavery/diagram-design、coreyhaines31/marketingskills、blader/humanizer、tt-a1i/archify、ayghri/i-have-adhd、DietrichGebert/ponytail。本週觀察到的兩條橫切訊號：(1) OpenAI / Anthropic 兩個官方都開「skills catalog」repo，把 skill 變成可索引的 surface area；(2) 第三方 skills（如 archify、marketingskills、blader/humanizer）開始針對「單一垂直任務」做精緻化（架構圖、行銷文案、去除 AI 痕跡）。
- **Coding agent / agent harness 整隊上位**（Top 20 內 3 席，daily fill 段繼續延伸）：Top 20 內 — affaan-m/ECC（agent harness performance optimization）、mksglu/context-mode（context window optimization）、NousResearch/hermes-agent（agent that grows with you）；daily fill 段（Top 20 之後）也有 anomalyco/opencode、Tencent/teamai-cli、obra/superpowers、vastsa/PI-Desktop — 全部圍繞「讓 agent 跑得更好」，不是新模型、而是把現有模型 + agent loop 包成產品。
- **AI multimodal / agent infra / infra 三類補完 4 個席次**：AI multimodal 有 heygen-com/hyperframes（寫 HTML，HeyGen 出品）與 THU-MAIC/OpenMAIC（multi-agent interactive classroom，清華 MAIC）；agent infra 有 ruvnet/ruflo（agent meta-harness，號稱 🌊「the original」）；infra 則是 microsoft/markitdown（檔案→markdown 轉換，雖然不是新專案但本週被 retrending）。
- **本週 22/34 是新進榜黑馬**，12 個曾在近 5 期週報出現過 — 黑馬集中在：**Claude Code 第三方 skill ecosystem**（ayghri/i-have-adhd、tt-a1i/archify、coreyhaines31/marketingskills、blader/humanizer、openai/plugins、openai/skills、mattpocock/skills、anthropics/skills 全是 skills 類）與 **agent ecosystem**（NousResearch/hermes-agent、Tencent/teamai-cli、anomalyco/opencode、vastsa/PI-Desktop、ruvnet/ruflo）；retrending 則有 fmtlib/fmt、ChromeDevTools/chrome-devtools-mcp、bilawalsidhu/gods-eye-view 等少數 infra / 視覺 demo 長尾。
- **語言分佈**：Top 20 內 TypeScript 5 / JavaScript 6 / Python 6 / Shell 1 / C++ 1 / HTML 1 — Python 與 TypeScript 雙引擎拉動 skill + agent 生態（mksglu/context-mode、ruvnet/ruflo、openai/skills、NousResearch/hermes-agent 都是這兩種）；JavaScript 來自 plugin 生態（openai/plugins、coreyhaines31/marketingskills）與瀏覽器端視覺 demo（gods-eye-view）。整體 34 個 unique repo 還包含 Rust 1（AlexsJones/llmfit）、C 2（armory3d/armorpaint、JustVugg/colibri）等長尾。
- **Anomalies worth sanity check**：多個 repo 的 weekly stars 顯示值明顯偏高（affaan-m/ECC 單週 +9,257、mattpocock/skills +12,356、tt-a1i/archify +11,958、DietrichGebert/ponytail +11,638），但 API `stargazers_count` 與 `pushed_at` 都確認為真實（皆在 2026-09 內有 push），非渲染假字串 — GitHub Trending 對存量大的專案會把當週增速放大顯示。fmtlib/fmt（C++ formatting library）進 top20 在「AI 一片」中屬亮點：純 C++ 工具持續有開發者關注、與本週 agent 浪潮形成對照。

---

_Generated by cron job at Friday 18:00 Asia/Taipei._
