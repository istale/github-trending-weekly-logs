---
date: 2026-07-24
period: 2026-07-18 ~ 2026-07-24
source: https://github.com/trending?since=weekly
total: 20
---

## 本週 Top 20

1. **block/buzz** (Rust) — Block 出品的「蜂巢思維」通訊平台，把多人決策變成可即時協作的群體空間。 (⭐ 8.1K)
2. **koala73/worldmonitor** (TypeScript) — 即時全球情報儀表板，AI 驅動的新聞彙整、地緣政治監控與基礎設施追蹤全整合在一個介面。 (⭐ 72.6K)
3. **shiyu-coder/Kronos** (Python) — 金融市場語言的基礎模型，專門處理 K 線與時間序列。 (⭐ 33.3K)
4. **Pumpkin-MC/Pumpkin** (Rust) — 讓每個人都能自架高效能 Minecraft 伺服器的 Rust 實作。 (⭐ 9.1K)
5. **citrolabs/ego-lite** (JavaScript) — 為人類與 AI agent 平行協作而設計的瀏覽器。 (⭐ 2.1K)
6. **chrislgarry/Apollo-11** (Assembly) — Apollo 11 導航電腦（AGC）指令艙與登月艙的原始 source code，歷史性程式碼保存專案。 (⭐ 71.2K)
7. **diegosouzapw/OmniRoute** (TypeScript) — 免費 MIT AI gateway，單一 endpoint 串接 290+ providers / 500+ models，含 quota-aware auto-fallback 與 token 壓縮。 (⭐ 27.9K)
8. **ComposioHQ/awesome-claude-skills** (Python) — 策展過的 Claude Skills / 資源 / 工具清單，給 Claude AI workflow 客製化用。 (⭐ 69.7K)
9. **earthtojake/text-to-cad** (JavaScript) — 把 AI agent skill 應用到 CAD、機器人與硬體設計領域的集合專案。 (⭐ 10.3K)
10. **agegr/pi-web** (TypeScript) — 給 `pi` coding agent 用的 Web UI 前端。 (⭐ 2.5K)
11. **alibaba/open-code-review** (Go) — 阿里巴巴等級的開源 code review 工具：deterministic pipeline + LLM agent，附帶 fine-tuned ruleset（NPE、thread-safety、XSS、SQL injection）。 (⭐ 12.1K)
12. **ruvnet/RuView** (Rust) — 把消費級 WiFi 訊號變成即時空間情報與生命跡象監測，全程零影像。 (⭐ 85.5K)
13. **likec4/likec4** (TypeScript) — 從 code 直接生出即時同步的軟體架構圖，支援協作與演進。 (⭐ 4.8K)
14. **Automattic/harper** (Rust) — 離線、隱私優先的文法檢查工具，Rust 打造。 (⭐ 12.6K)
15. **jellyfin/jellyfin** (C#) — 自由軟體媒體系統的伺服器後端與 API，Free Software Media System。 (⭐ 54.9K)
16. **tirth8205/code-review-graph** (Python) — 本地優先的程式碼智慧圖，給 MCP 與 CLI 用 — 給 AI coding tools 只餵相關 context，已做 benchmark。 (⭐ 26.1K)
17. **Nutlope/hallmark** (CSS) — 反 AI 廢料的設計 skill，給 Claude Code / Cursor / Codex 用，讓產出不要「AI-slop」。 (⭐ 16.5K)
18. **MoonshotAI/kimi-code** (TypeScript) — Moonshot 出品的 Kimi Code CLI，下一代 agent 的入口。 (⭐ 4.9K)
19. **1jehuang/jcode** (Rust) — 宣稱「最聰明的 code agent harness」，用 Rust 寫的 agent 核心。 (⭐ 11.1K)
20. **HKUDS/DeepTutor** (Python) — 港大數據科學團隊出品，終身個人化家教 Agent（DeepTutor.info）。 (⭐ 29.5K)

> **Note:** Trending 頁上 `sponsors/*` 形式的 promo 已映射回原始 repo；`apps/*`（GitHub App 列表，例如 `apps/copilot-swe-agent`、`apps/copilot-pull-request-reviewer`）屬於平台服務而非專案，已排除以維持 Top 20 為「專案」性質。前 15 為 `https://github.com/trending` 整體排序，後 5 補入 `?since=weekly` 頁獨佔的高動能 repo。

---

## 觀察

- **AI Coding Agent 生態進入「runtime + skill + gateway」三件套成熟期**：MoonshotAI/kimi-code（CLI agent）、diegosouzapw/OmniRoute（multi-provider gateway）、Nutlope/hallmark（設計 skill）、agegr/pi-web（Web UI）、1jehuang/jcode（Rust agent harness）— 同一週同框出現，顯示 agent 不再只是聊天介面，而是 CLI runtime + 標準化 skill + provider routing 三層組合的競賽。
- **Claude Skills / Agent Skills 標準持續擴散**：ComposioHQ/awesome-claude-skills、Nutlope/hallmark、earthtojake/text-to-cad、tirth8205/code-review-graph 都圍繞「給 agent 用」的 skill 與 context layer；上週 google-labs-code/stitch-skills 採納的開放標準這週被更多第三方 repo 響應，標準化正在加速。
- **「AI + 垂直場景」的開源實作持續湧現**：shiyu-coder/Kronos（金融市場基礎模型）、HKUDS/DeepTutor（個人化家教）、koala73/worldmonitor（地緣政治情報）、citrolabs/ego-lite（AI + 人的瀏覽器）、alibaba/open-code-review（企業級 code review）— 都是把模型嵌進特定垂直場景並 open source release，不是 demo，是 fork-and-deploy 的產品。
- **Rust 在高頻 / agent runtime 兩端都站穩**：block/buzz（蜂巢通訊）、Pumpkin-MC/Pumpkin（Minecraft server）、ruvnet/RuView（WiFi 訊號處理）、1jehuang/jcode（agent harness）、Automattic/harper（文法檢查）— 5/20 是 Rust，呼應 Rust 已成為「real-time / 系統級 / AI runtime」的首選語言。
- **TypeScript 仍是 agent UI / dashboard 主流，Python 撐起模型 / 框架層**：TypeScript 7 個（含 kimi-code、OmniRoute、worldmonitor、likec4、pi-web 等），Python 6 個（Kronos、ComposioHQ、DeepTutor、Shubhamsaboo-ish 的 awesome 系、code-review-graph 等）；另見 JavaScript 2、Go 1、C# 1、C++ 0、Assembly 1（chrislgarry/Apollo-11 為歷史性 repo 復活，這週的彩蛋）。
