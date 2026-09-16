# Stephen Chuang

[English →](./README.md)

### Agentic Systems Engineer · AI Agent Reliability

正在打造 **Better Workflows**：一套給 AI 工程 Agent 使用的 evidence-first QA 與交付控制層。

我的工作落在機率性 AI Agent 與確定性軟體交付的交界。

> AI 能提出方案、也能推理。但 production 系統依然需要證據、授權、驗證，以及確實執行完成的證明。

目前的重心是讓自主化的工程工作流程更安全、更可靠，做法包括：evidence-bound validation、明確的 authority 與 scope、fail-closed execution、stale-state detection、unknown-outcome reconciliation、bounded side effects、task-isolated Git workflows，以及 deterministic delivery gates。

Prompt 能描述意圖，但它無法證明授權、當下狀態，或執行確實成功。Better Workflows 把這些落差轉為明確、可重複驗證的控制點。

13 年以上軟體工程經驗 —— 前端架構、全端系統、CI/CD、production 交付、工程領導，以及大量第一線使用 AI coding agents 的實務。

## 正在打造

### 1. Better Workflows

**Evidence-first AI engineering QA + delivery gatekeeper**

[betterworkflows.dev](https://betterworkflows.dev) · [原始碼](https://github.com/stephen-taipei/better-workflows) *(V5 改版期間暫時設為 private，正式發布後公開)*

Better Workflows 治理 AI coding agents 從意圖走到真實 repository 變更的整段路徑。它把 Agent 判斷與 deterministic validation 分開，將證據綁定到當下的 repository、revision、scope 與 target；一旦證據過期，或外部動作結果不明，工作流程就會停下來，而不是假裝任務已完成。

**Goal-first · Evidence-driven · Fail-closed · Risk-adaptive**

目前的工作範圍：

- Agent authority 與 scope 邊界
- 證據的 freshness 與 provenance
- Deterministic validation
- Risk-adaptive 工作流程路由
- Provider reconciliation
- 具安全邊界的 Git mutation 與 task-isolated 整合
- 多 Agent 工程工作流程
- 自主化交付的可靠性

### 2. Connectors（脈客）

**AI 個人 CRM，已實際上線**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **負責範圍：** 產品方向、架構、AI 輔助交付編排、Code Review、QA，以及 iOS／Android 發布。
- **AI 輔助實作技術背景：** React、NestJS、tRPC、SwiftUI、Kotlin Compose。

### 3. [stephen-skills](https://github.com/stephen-taipei/stephen-skills)

供 AI-native 開發工作流程使用的 Claude Code skills、hooks 與 commands —— 支撐上述可靠性工作的日常 Agent 工具。

## 工程實績

十三年 production 工程經驗，正是上述可靠性工作能立基於真實交付系統而非 demo 的原因：在我的工作流程中，AI Agent 實際會動到 Git、CI、deployment、資料庫與真實 repository。

### [前端工程案例](https://github.com/stephen-taipei/frontend-engineering-case-studies)

可執行且去識別化的 Angular／Nx 多主題架構實作，包含三個虛構主題、typed contracts、`core / view / theme` 邊界、facade／service 分層、family-completeness tests、CSS 依需求載入、雙語決策文件，以及明確的[證據邊界](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.zh-TW.md)。

- **[Config 驅動的多主題架構](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/case-studies/config-driven-multi-theme.zh-TW.md)** — 為支援 100+ 主題與多版型的 Angular／Nx 平台制定並主導統一架構。透過單向 `selector → theme leaf → shared view → core` 依賴、明確的 facade／service ownership 與跨主題 completeness tests，將複雜客製化邏輯收斂為 typed config；在此次 migration 中，一個具代表性的完整 production 主題 leaf 精簡至 **23 行**。Rollout scope 涵蓋 70 個職責明確的模組：24 facades、10 data services、10 theme configs、26 shared views。
- **[Web 效能實測](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/case-studies/on-demand-theme-css.zh-TW.md)** — 主導將 136 份主題 CSS 改為依需求載入，使單次主題資源由約 **2.4 MB 降至 17 KB，約降低 99%**。在另一項關鍵頁面品質優化中，將 Lighthouse Performance 實測由 **50+ 提升至 90+**，並同步改善無障礙、最佳實務、SEO 與生成式搜尋情境下的 AEO。
- **工程領導** — 帶領 6 人跨職能團隊，負責技術面試、架構規劃、Code Review、工作分配與交付時程。
- **產品成長** — 協助客戶產品於一年內將會員數由 0 成長至 20,000。

## 核心專長

- **Agentic systems：** AI coding agents、多 Agent 工作流程、Agent orchestration、tool-driven execution
- **Agent reliability：** evidence-bound validation、stale-state detection、reconciliation、fail-closed execution
- **工程治理：** Policy as Code、確定性驗證、具邊界的自動化、安全交付
- **軟體架構：** 系統邊界、明確職責歸屬、行為保持重構
- **Production 工程：** Git、CI/CD、Linux、部署、可觀測性、資料庫
- **前端架構：** Angular、TypeScript、Nx、Config 驅動平台、Web 效能、無障礙、SEO／AEO
- **全端背景：** Node.js、NestJS、Laravel、PHP、MySQL、PostgreSQL、Redis

## 目前投入

我正全力投入 Better Workflows，以及自主化程度日益提高的 AI 工程 Agent 所需要的可靠性層。

有興趣交流的主題：

- AI coding agents 與 agentic SDLC
- AI agent reliability 與治理
- Developer infrastructure
- 多 Agent 系統
- OSS 協作

若與 agentic systems、developer infrastructure 或 AI 工程可靠性相關，歡迎來信洽談。

台灣 · Remote

[個人網站](https://stephen.taipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [前端工程案例](https://github.com/stephen-taipei/frontend-engineering-case-studies)
