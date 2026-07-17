---
date: 2026-07-17
period: 2026-07-11 ~ 2026-07-17
source: https://github.com/trending?since=weekly
total: 20
---

## 本週 Top 20

1. **google-labs-code/stitch-skills** (TypeScript) — Google Labs 出品的 Agent Skills library，與 Stitch MCP server 搭配使用，遵循 Agent Skills 開放標準，相容 Antigravity、Gemini CLI、Claude Code、Cursor。 (⭐ 7.6K)
2. **wonderwhy-er/DesktopCommanderMCP** (TypeScript) — 給 Claude 的 MCP server，提供 terminal 控制、檔案搜尋與 diff 編輯能力。 (⭐ 8.4K)
3. **abseil/abseil-cpp** (C++) — Google 維護的 C++ 通用函式庫集合（Abseil Common Libraries），本週被新一波 C++ 開發者關注。 (⭐ 18.0K)
4. **Nutlope/hallmark** (CSS) — 反 AI 廢料設計的 skill，給 Claude Code、Cursor、Codex 用，讓產出不要「AI-slop」。 (⭐ 11.5K)
5. **HKUDS/Vibe-Trading** (Python) — 「Vibe-Trading」個人化交易 Agent，HKU Data Science 團隊出品。 (⭐ 24.5K)
6. **chriskohlhoff/asio** (C++) — Asio C++ 異步網路與並行庫，獨立於 Boost 的現代版本。 (⭐ 6.1K)
7. **stablyai/orca** (TypeScript) — Agent Development Environment，用一個 UI 同時管理多個平行 coding agent，可用自己的訂閱跑任何 coding agent。 (⭐ 20.9K)
8. **oven-sh/bun** (Rust) — 超快 JavaScript runtime + bundler + test runner + 套件管理器，本週突破 94K stars。 (⭐ 94.8K)
9. **OpenCut-app/OpenCut** (TypeScript) — 開源 CapCut 替代品，影片剪輯。 (⭐ 74.5K)
10. **MadsLorentzen/ai-job-search** (TypeScript) — 跑在自己機器上的求職 AI 框架：評估職缺、改 CV、寫 cover letter、準備面試，全在 Claude Code 裡完成。 (⭐ 23.3K)
11. **iOfficeAI/OfficeCLI** (C#) — 第一個為 AI agent 設計的 Office 套件，可讀、編、自動化 Word/Excel/PPT；單一二進位、不需裝 Office。 (⭐ 18.6K)
12. **Shubhamsaboo/awesome-llm-apps** (Python) — 100+ 可直接跑的 AI Agent 與 RAG app 集合。 (⭐ 123.3K)
13. **openai/codex-plugin-cc** (JavaScript) — 從 Claude Code 內呼叫 OpenAI Codex 來 review code 或委派任務。 (⭐ 29.0K)
14. **diegosouzapw/OmniRoute** (TypeScript) — 免費 AI gateway，單一 endpoint 串接 231+ providers（含 50+ 免費 Claude/GPT/Gemini）；RTK+Caveman token 壓縮節省 15-95%。 (⭐ 18.2K)
15. **davila7/claude-code-templates** (Python) — Claude Code 的 CLI 配置與監控工具。 (⭐ 29.6K)
16. **pbakaus/impeccable** (JavaScript) — 讓 AI harness 在設計任務上更出色的「設計語言」。 (⭐ 47.5K)
17. **kangarooking/cangjie-skill** (Python) — 把書、長影片、Podcast 等高價值內容蒸餾成可執行的 Agent Skills（中文）。 (⭐ 3.4K)
18. **ogulcancelik/herdr** (Rust) — terminal 裡跑的 agent multiplexer，把任務路由到多個 AI agent。 (⭐ 17.4K)
19. **HKUDS/DeepTutor** (Python) — 終身個人化家教 Agent，HKU Data Science 出品。 (⭐ 27.1K)
20. **jrouwe/JoltPhysics** (C++) — 多核心友好的剛體物理與碰撞偵測庫，給遊戲與 VR 用；Horizon Forbidden West 與 Death Stranding 2 都用它。 (⭐ 11.0K)

> **Note:** Trending 頁上 `sponsors/*` 形式的 promo 已映射回原始 repo（owner 同名）；`actions/checkout`（第 19 順位的 GitHub Action 庫）被排除以維持 Top 20 為「專案」性質。

---

## 觀察

- **AI Agent Skills 生態成形**：本週 20 個 repo 中至少有 6 個直接與「給 AI coding agent 的 skill / template / MCP server」相關 — google-labs-code/stitch-skills、Nutlope/hallmark、pbakaus/impeccable、kangarooking/cangjie-skill、mattpocock/skills（上週延燒）、davila7/claude-code-templates。「Agent Skills open standard」這次被 Google Labs 正式採用，說明這條標準線正在被各家 coding agent 接受。
- **Claude Code 與 Codex 互補成明確主題**：wonderwhy-er/DesktopCommanderMCP、openai/codex-plugin-cc、davila7/claude-code-templates、diegosouzapw/OmniRoute、ogulcancelik/herdr 都圍繞 Claude Code / Codex / Cursor / Cline 的擴展與互通 — 「哪個 coding agent 最好」已經不是問題，「怎麼把它們組合起來」才是。
- **本地化 Agent 框架從概念走向實作**：HKUDS/Vibe-Trading（交易）、MadsLorentzen/ai-job-search（求職）、iOfficeAI/OfficeCLI（Office 自動化）、HKUDS/DeepTutor（家教）— 都不是聊天機器人，而是把 agent 嵌進特定垂直場景並開源 release，使用者 fork 後自部署。
- **Rust 在 AI infra 與 runtime 兩端都站穩**：oven-sh/bun（94.8K）、ogulancelik/herdr、openinterpreter/openinterpreter（上週延燒）— Rust 不再只是「系統語言」，而是 AI agent runtime / 高頻 I/O 工具的事實首選。
- **長青 C++ 基礎庫意外進榜**：abseil/abseil-cpp 與 chriskohlhoff/asio 同週進 Top 10，jrouwe/JoltPhysics 也在榜上，可能是 C++ 社群近期的 release 活動或文件更新觸發；與 AI 主題並存說明 Trending 並未完全被 AI 壟斷。
