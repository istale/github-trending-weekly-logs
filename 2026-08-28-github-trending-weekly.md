---
date: 2026-08-28
period: 2026-08-22 ~ 2026-08-28
source:
  - https://github.com/trending
  - https://github.com/trending?since=weekly
  - https://api.github.com/repos/<owner>/<repo>
total: 32
note: |
  本週 Overall 預設頁抓到 19 個、weekly 視角抓到 19 個；兩者重疊 6 個，合併去重後共 32 個 unique repo。
  GitHub Trending 沒有公開分頁，本次完整列出全部 32 個（未湊數）；下表 Top 20 依「daily 視角優先」（今日星數），
  末位以 weekly 排名最高、但今日未上榜的 anthropics/claude-plugins-community 補滿。
  Top 20 的 20 個 repo 全部經 GitHub REST API 成功解析（0 個 404），description / language / stargazers_count 由 API 補上。
generated_by: horo-trending-cron
---

# GitHub Trending 週報 — 2026-08-28

> 期間：2026-08-22 ~ 2026-08-28　|　來源：github.com/trending (Overall + weekly) + GitHub REST API

## 本週 Top 20

排序：daily 視角優先（依今日星數遞減），末位補一個 weekly 排名最高但今日未上榜者（標 _(weekly fill)_）。

1. **[tt-a1i/archify](https://github.com/tt-a1i/archify)** — JavaScript — +4,561 stars today　|　⭐ 25,530 — Agent skill for beautiful, verifiable architecture, workfl…
2. **[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)** — Python — +720 stars today　|　⭐ 35,793 — Turn any AI agent into an AI Scientist.
3. **[anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)** — Python — +457 stars today　|　⭐ 34,854 — Official, Anthropic-managed directory of high quality Clau…
4. **[bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)** — JavaScript — +1,984 stars today　|　⭐ 10,025 — A spy satellite simulator in your browser, except the data…
5. **[abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)** — TypeScript — +189 stars today　|　⭐ 46,040 — GitNexus: The Zero-Server Code Intelligence Engine - GitNe…
6. **[JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines)** — Go — +574 stars today　|　⭐ 2,448 — Help AI coding agents write modern Go
7. **[calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)** — Python — +1,144 stars today　|　⭐ 52,949 — World's first open-source, agentic video production system.
8. **[abi/screenshot-to-code](https://github.com/abi/screenshot-to-code)** — Python — +309 stars today　|　⭐ 75,305 — Drop in a screenshot and convert it to clean code (HTML/Ta…
9. **[cursor/plugins](https://github.com/cursor/plugins)** — TypeScript — +257 stars today　|　⭐ 5,826 — Cursor plugin specification and official plugins
10. **[freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)** — JavaScript — +1,687 stars today　|　⭐ 23,968 — Prompt as Code | GPT-Image2 工业级提示词引擎与模板库，530+ 个案例逆向工程，20+…
11. **[tailscale/tailcat](https://github.com/tailscale/tailcat)** — Go — +986 stars today　|　⭐ 2,333 — like netcat, but over Tailscale's data plane, without Tail…
12. **[NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra)** — Java — +117 stars today　|　⭐ 73,141 — Ghidra is a software reverse engineering (SRE) framework
13. **[marin-community/marin](https://github.com/marin-community/marin)** — Python — +236 stars today　|　⭐ 2,805 — Open-source framework for the research and development of…
14. **[tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi)** — TypeScript — +405 stars today　|　⭐ 21,320 — 7.4 billion tokens per month.
15. **[ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)** — TypeScript — +61 stars today　|　⭐ 49,872 — Chrome DevTools for coding agents
16. **[rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)** — Python — +703 stars today　|　⭐ 50,456 — Learn it. Build it. Ship it for others.
17. **[DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)** — JavaScript — +1,396 stars today　|　⭐ 114,855 — Makes your AI agent think like the laziest senior dev in t…
18. **[google/googletest](https://github.com/google/googletest)** — C++ — +156 stars today　|　⭐ 39,117 — GoogleTest - Google Testing and Mocking Framework
19. **[livekit/agents](https://github.com/livekit/agents)** — Python — +14 stars today　|　⭐ 13,223 — A framework for building realtime voice AI agents
20. **[anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community)** _(weekly fill)_ — Python — +2,069 stars this week　|　⭐ 2,486 — Community plugin marketplace for Claude Cowork and Claude…

## 觀察

- **AI agent / Claude Code / LLM 生態佔壓倒性多數**（Top 20 中 14/20，前兩席皆為 agent-skill 專案）：skills 目錄與 plugin marketplace — tt-a1i/archify、K-Dense-AI/scientific-agent-skills、anthropics/claude-plugins-official、anthropics/claude-plugins-community、cursor/plugins；coding agent / LLM 工具鏈 — JetBrains/go-modern-guidelines、DietrichGebert/ponytail、ChromeDevTools/chrome-devtools-mcp、livekit/agents、tashfeenahmed/freellmapi、freestylefly/awesome-gpt-image-2、calesthio/OpenMontage、rohitg00/ai-engineering-from-scratch、marin-community/marin。本週主題高度集中在「讓 agent 更強、更多 skill」。
- **「開源 / self-hosted / 免費」是橫切主題**：freestylefly/awesome-gpt-image-2（本機提示詞庫）、tashfeenahmed/freellmapi（免費 LLM 路由）、tailscale/tailcat（脫離 control plane 的本地數據平面）、calesthio/OpenMontage（開源 agentic 影片）。共同押注：「跑在本機、不要餵資料」正從口號變成真實分類。
- **語言分佈**：Python 8、JavaScript 4、TypeScript 4、Go 2、Java 1、C++ 1（API `language` 統計，合計 20）。Python 集中於 agent/skills 與模型訓練；JavaScript / TypeScript 偏 plugin / DevTools / 視覺工具前端；Go 在本週僅 2 個（JetBrains/go-modern-guidelines、tailscale/tailcat），較前幾週少。
- **非 AI 的系統 / 視覺工具也有上榜**（6/20）：NationalSecurityAgency/ghidra（逆向工程）、google/googletest（C++ 測試）、abhigyanpatwari/GitNexus（code intelligence）、abi/screenshot-to-code（截圖轉碼）、bilawalsidhu/gods-eye-view（開源空間情報 3D 地球儀）、tailscale/tailcat（tailnet 網路工具），與上週（純 AI）形成對照。
- **Anomalies worth sanity check**：DietrichGebert/ponytail 顯示 total 114,855 stars（API 確認 stargazers_count=114,855，pushed_at=2026-08-07），單日 +1,396 仍正常但總量偏高，疑為前幾週持續熱度累積；tt-a1i/archify 單日 +4,561（total 25,530，pushed_at=2026-08-28）為本週最陡增額，pushed_at 確認有當週真實活動，非顯示異常。

---

_Generated by cron job at Friday 18:00 Asia/Taipei._
