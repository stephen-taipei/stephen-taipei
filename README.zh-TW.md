# Stephen Chuang

[English](./README.md) · [繁體中文](./README.zh-TW.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [ไทย](./README.th.md)

### AI-Native Systems Builder · Agentic Systems Engineer

我擅長把模糊問題轉化成具體系統、工作流與能實際上線的 production outcome。

目前正在開發 **Better Workflows**，一個以 evidence-first 為核心的 AI engineering reliability 與 delivery control layer。

我目前專注於 probabilistic AI agents 與 deterministic software delivery 之間的邊界。

> AI 可以提出方案與推理。Production system 仍然需要 evidence、authority、validation 與 outcome proof。

具 13+ 年 software engineering 經驗，涵蓋 architecture、full-stack systems、CI/CD、production delivery、engineering leadership 與 AI-native development。

## 目前在做的事

### Agentic 基礎設施

這組工具以 evidence、authority、validation 為核心，管控 AI coding agents 從意圖到真實 repo 變更的過程。

1. **[Better Workflows](https://betterworkflows.dev)** （主力）

   **以 evidence 為先的 AI 工程可靠性與交付守門層**

   [betterworkflows.dev](https://betterworkflows.dev) · [原始碼](https://github.com/stephen-taipei/better-workflows) · [npm](https://www.npmjs.com/package/@better-workflows/core)

   V6 Core 6.0.0-alpha.2 — 可免費安裝（Apache-2.0）。先支援 Claude Code；Codex、Gemini CLI、Qwen Code 規劃中。V5 已定格在 RC1（AGPL-3.0-only）。

   ```bash
   npm install -g @better-workflows/core@alpha
   claude plugin marketplace add stephen-taipei/better-workflows
   claude plugin install better-workflows-core@better-workflows --scope local
   bw init
   ```

   **目標優先 · 證據驅動 · 失效即阻擋 · 風險自適應**

2. **[Deckhand](https://github.com/stephen-taipei/deckhand)**: Claude Code 的多 AI 工具列，提供 usage gauges、模型切換、parallel sub agents，以及來自 Codex／Cursor／agy 的唯讀 second opinion。

3. **[Intent Galaxy](https://github.com/stephen-taipei/intent-galaxy)**: 把一句模糊目標展開成星系圖：先發散看見盲區，再用鍵盤收斂成確定性的意圖規格。[npm](https://www.npmjs.com/package/@stephen.taipei/intent-galaxy)

**其他開源專案：** **[Adorable Git Graph](https://github.com/stephen-taipei/adorable-git-graph)**: 把 git 歷史畫成可以捲動的卡通：每個 commit 是一顆有表情的小球，每條 branch 是流動的管線。[Demo](https://stephen-taipei.github.io/adorable-git-graph/) · [npm](https://www.npmjs.com/package/@stephen.taipei/adorable-git-graph)

[所有開源專案 →](https://stephen.taipei/open-source)

### 已上線產品

**Connectors (脈客) · 私有儲存庫**

**AI 驅動的個人 CRM，已正式上線**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **角色：** Product direction、architecture、AI-assisted delivery orchestration、Code Review、QA，以及 iOS release delivery
- **狀態：** iOS 與網頁版已上線 · Android 開發中
- **AI 輔助實作技術：** React、NestJS、tRPC、SwiftUI、Kotlin Compose

## 工程實績

13 年 production engineering 經驗，讓上述 reliability work 建立在真實交付系統，而非單純 Demo。我的 AI agent workflow 會實際操作 Git、CI、deployment、database 與真實 repositories。

### [前端工程案例研究](https://github.com/stephen-taipei/frontend-engineering-case-studies)

前端工程背景中的部分 production architecture 成果：

- 設計並主導 Angular/Nx architecture，支援 100+ themes，將具代表性的 production theme leaf 降至 **23 行**
- 將單一 theme CSS request 約從 **2.4 MB 降至 17 KB**，約 99%，並將實測 Lighthouse Performance 由 **50+ 提升至 90+**
- 直接帶領 3–4 位前端工程師，並協調多位非直屬的支援工程師；不定期主辦內部技術分享會。

各成果的 scope、baseline 與明確 [未宣稱事項](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.md) 已獨立列出。

## 核心專長

- **系統建構：** 將模糊問題轉成 explicit models、boundaries、workflows 與 executable systems
- **Agentic 系統：** AI coding agents、multi-agent workflows、agent orchestration、tool-driven execution
- **Agent 可靠性：** evidence-bound validation、stale-state detection、reconciliation、fail-closed execution
- **工程治理：** policy as code、deterministic validation、bounded automation、safe delivery
- **軟體架構：** system boundaries、explicit ownership、behavior-preserving refactoring
- **生產環境工程：** Git、CI/CD、Linux、deployment、observability、databases
- **工程基礎：** Node.js、NestJS、Angular、TypeScript、Nx、Laravel、PostgreSQL、MySQL、Redis

## 聯繫

歡迎針對 agentic systems、AI agent reliability、developer infrastructure 與 OSS collaboration 進行交流。

台灣 · 遠端

[個人網站](https://stephen.taipei) · [文章](https://stephen.taipei/articles) · [LinkedIn](https://www.linkedin.com/in/stephentaipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [案例研究](https://github.com/stephen-taipei/frontend-engineering-case-studies)
