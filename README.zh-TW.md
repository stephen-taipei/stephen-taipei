# Stephen Chuang

[English →](./README.md)

### Agentic Systems Engineer · AI Agent Reliability

正在打造 **Better Workflows**：一套給 AI 工程 Agent 使用的 evidence-first QA 與交付控制層。

我的工作落在機率性 AI Agent 與確定性軟體交付的交界。

> AI 能提出方案、也能推理。但 production 系統依然需要證據、授權、驗證，以及確實執行完成的證明。

13 年以上軟體工程經驗，橫跨架構、全端系統、CI/CD、production 交付、工程領導，以及 AI-native 開發。

## 正在打造

### 1. Better Workflows

**Evidence-first AI engineering QA + delivery gatekeeper**

[betterworkflows.dev](https://betterworkflows.dev) · [原始碼](https://github.com/stephen-taipei/better-workflows) *(V5 改版期間暫時設為 private，正式發布後公開)*

Better Workflows 治理 AI coding agents 從意圖走到真實 repository 變更的整段路徑。它把 Agent 判斷與 deterministic validation 分開，將證據綁定到當下的 repository、revision、scope 與 target；一旦證據過期，或外部動作結果不明，工作流程就會停下來，而不是假裝任務已完成。

Prompt 能描述意圖，但它無法證明授權、當下狀態，或執行確實成功。Better Workflows 把這些落差轉為明確、可重複驗證的控制點。

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

## 工程實績

十三年 production 工程經驗，正是上述可靠性工作能立基於真實交付系統而非 demo 的原因：在我的工作流程中，AI Agent 實際會動到 Git、CI、deployment、資料庫與真實 repository。

### [前端工程案例](https://github.com/stephen-taipei/frontend-engineering-case-studies)

前端工程背景中具代表性的 production 架構工作：

- 設計並主導支援 100+ 主題的 Angular／Nx 架構，將一個具代表性的 production 主題 leaf 精簡至 **23 行**。
- 將單次主題 CSS 請求由約 **2.4 MB 降至 17 KB**（約 99%），並將實測 Lighthouse Performance 由 **50+ 提升至 90+**。
- 帶領 6 人跨職能工程團隊。

## 核心專長

- **Agentic systems：** AI coding agents、多 Agent 工作流程、Agent orchestration、tool-driven execution
- **Agent reliability：** evidence-bound validation、stale-state detection、reconciliation、fail-closed execution
- **工程治理：** Policy as Code、確定性驗證、具邊界的自動化、安全交付
- **軟體架構：** 系統邊界、明確職責歸屬、行為保持重構
- **Production 工程：** Git、CI/CD、Linux、部署、可觀測性、資料庫
- **工程基礎：** Node.js、NestJS、Angular、TypeScript、Nx、Laravel、PostgreSQL、MySQL、Redis

## 聯絡

關於 agentic systems、AI agent reliability、developer infrastructure 與 OSS 協作的選擇性洽談，歡迎來信。

台灣 · Remote

[個人網站](https://stephen.taipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [前端工程案例](https://github.com/stephen-taipei/frontend-engineering-case-studies)
