---
date: 2026-08-07
period: 2026-08-01 ~ 2026-08-07
source:
  - https://github.com/trending
  - https://github.com/trending?since=weekly
  - https://api.github.com/repos/<owner>/<repo>
total: 16
note: |
  本週 GitHub Trending Overall 首頁實際列出 13 個 repo，`?since=weekly` 視角再多 3 個；兩個視角去重後共 16 個 unique repo。
  GitHub Trending 頁面沒有公開分頁（grep 不到 `?page=` 或 next-page 連結），因此本週無法湊齊 20 條；以下為實際抓取到的全部 16 條。
generated_by: horo-trending-cron
---

# GitHub Trending 週報 — 2026-08-07

## 本週 Top 16

1. **[TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)** — TypeScript — ⭐ 17,084 — 團隊級 AI Agent 記憶中心，把對話、文件、程式碼蒸餾成四種可重用 memory asset。
2. **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)** — JavaScript — ⭐ 83,349 — 給 AI coding agent 用的 production-grade 工程 skills 套件。
3. **[cloudflare/computer](https://github.com/cloudflare/computer)** — TypeScript — ⭐ 5,159 — 讓 agent 拿到一台可操控的雲端電腦（瀏覽器、shell、檔案系統）。
4. **[huangruiteng/loopx](https://github.com/huangruiteng/loopx)** — Python — ⭐ 3,181 — 給長跑 AI agent team 用的輕量 loop state kernel，跨 Codex / Claude Code 等 agent runtime。
5. **[google/guava](https://github.com/google/guava)** — Java — ⭐ 51,694 — Google 的 Java 核心工具函式庫（經典老牌被重新翻紅）。
6. **[TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook)** — Roff — ⭐ 77,559 — 收集所有中國小初高到大學的 PDF 教材。
7. **[Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** — Python — ⭐ 186,163 — 最早期的自主 AI agent 框架，願景是讓每個人都能使用與構建 AI。
8. **[esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix)** — Go — ⭐ 32,746 — DeepSeek-native 的 terminal AI coding agent，圍繞 prefix-cache 穩定性設計（可常駐）。
9. **[firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector)** — Rust — ⭐ 12,831 — 高速 PDF 檢測／分類／文字抽取函式庫，能智慧分辨掃描檔與文字型 PDF。
10. **[zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)** — PowerShell — ⭐ 20,227 — 逆向工程／授權滲透／安全研究的 skill router pack，AI 路由 + 按需工具鏈 bootstrap。
11. **[microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners)** — Jupyter Notebook — ⭐ 62,946 — 微軟官方 12 週 24 堂的 AI 入門教材。
12. **[block/buzz](https://github.com/block/buzz)** — Rust — ⭐ 24,581 — 開源 hive-mind 通訊平台（多人共享式協作空間）。
13. **[different-ai/openwork](https://github.com/different-ai/openwork)** — TypeScript — ⭐ 21,363 — 開源版的 Claude Cowork，底層用 opencode 驅動。
14. **[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)** — Python — ⭐ 17,931 — 給 coding agent 的 skill：阻止它把答案埋在冗長輸出裡，ADHD 友善呈現。
15. **[DataExpert-io/data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook)** — Jupyter Notebook — ⭐ 43,313 — 資料工程師學習資源總匯（書、工具、平台、教學）。
16. **[embabel/embabel-agent](https://github.com/embabel/embabel-agent)** — Kotlin — ⭐ 4,004 — JVM 生態的 agent framework，發音 Em-BAY-bel。

## 觀察

- **AI agent 仍是絕對主軸，但重心從「agent 框架本體」漂向「agent skill / memory / peripheral」**：本週 16 個 repo 中至少有 10 個與 AI coding agent 直接相關，但只有 `cloudflare/computer`、`embabel/embabel-agent`、`esengine/DeepSeek-Reasonix`、`loopx` 算是「agent runtime / 框架」，其餘 `TencentDB-Agent-Memory`、`agent-skills`、`ayghri/i-have-adhd`、`mattpocock/skills`、`obra/superpowers` 全是「餵給 agent 的 skill / memory pack」。可見市場從「誰能跑 agent」轉進「誰能讓 agent 跑得更好、記得更準、回答得更體貼」。
- **TypeScript 與 Python 仍佔半數江山，Rust 在 infra 類悄悄抬頭**：TypeScript 4 個（`TencentDB-Agent-Memory`、`cloudflare/computer`、`openwork`、`obra`），Python 5 個（`loopx`、`AutoGPT`、`ayghri/i-have-adhd`、`virgiliojr94`、教材類），Rust 2 個（`pdf-inspector`、`buzz`）—— 兩個 Rust 專案都是「高效能 + 偏系統層」（PDF 解析、P2P 通訊），呼應本週觀察到的「agent 需要更快、更省、更可常駐」的硬需求。
- **「agent 用的瀏覽器 / 桌面 / 雲端電腦」繼續被驗證為高需求面**：`cloudflare/computer` 衝上 daily +2,800 stars/day 排行第一，`citrolabs/ego-lite`（上週）與 `different-ai/openwork`（本週仍 +2,939 stars/week）反覆出現，說明「給 agent 開一台完整可操控電腦」的抽象正在變成 standard interface。
- **教材 / awesome-list 類仍在榜，目標受眾從工程師擴到一般大眾**：`microsoft/AI-For-Beginners` 24 課制、`DataExpert-io/data-engineer-handbook`、`TapXWorld/ChinaTextbook`、`zhaoxuya520/reverse-skill` —— 學習入口仍是非英語／中文圈的強拉力來源，學習型 repo 與 agent infra 並行不悖。
- **經典老牌被翻紅**：本週 `google/guava`（Java 核心庫）罕見上榜 +13 stars/day，旁觀 `microsoft/PowerToys`、`dotnet/aspnetcore`（上週）也都在 daily trending 出現，提示 Trending 演算法對「高品質、有長期 commit 歷史」的 mature repo 仍會定期打撈，不是只看新專案。
