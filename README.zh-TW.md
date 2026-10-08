# Stephen Chuang

[English](./README.md) · [繁體中文](./README.zh-TW.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [ไทย](./README.th.md)

### AI-Native Systems Builder · Agentic Systems Engineer

我擅長把模糊問題轉化成具體系統、工作流與可落地的 production outcome。

目前正在打造 **Better Workflows**，一個以 evidence-first 為核心的 AI engineering reliability 與 delivery control layer。

我目前專注於 probabilistic AI agents 與 deterministic software delivery 之間的邊界。

> AI 可以提出方案與推理。Production system 仍然需要 evidence、authority、validation 與 outcome proof。

具 13+ 年 software engineering 經驗，涵蓋 architecture、full-stack systems、CI/CD、production delivery、engineering leadership 與 AI-native development。

## 目前正在打造

### Agentic Infrastructure

這組工具以 evidence、authority、validation 為核心，管控 AI coding agents 從意圖到真實 repo 變更的過程。

1. **Better Workflows**

   **Evidence-first AI engineering reliability + delivery gatekeeper**

   [betterworkflows.dev](https://betterworkflows.dev) · [Source](https://github.com/stephen-taipei/better-workflows) · [發布版本](https://github.com/stephen-taipei/better-workflows/releases/tag/V5.0.rc1)

   V5.0 RC1 — 可免費安裝（AGPL-3.0-only）。支援 Codex、Gemini CLI、Qwen Code；Claude Code 規劃於 V5.1。

   ```bash
   codex plugin marketplace add stephen-taipei/better-workflows
   codex plugin add better-workflows@better-workflows
   ```

   **Goal-first · Evidence-driven · Fail-closed · Risk-adaptive**

2. **[Deckhand](https://github.com/stephen-taipei/deckhand)**: Claude Code 的多 AI 工具列，提供 usage gauges、模型切換、parallel sub agents，以及來自 Codex／Cursor／agy 的唯讀 second opinion。

3. **[Stephen Skills](https://github.com/stephen-taipei/stephen-skills)**: 可重用的 Agent Skills；以同一份 `SKILL.md` 為來源，Claude Code 和 Codex CLI 都能原生安裝。

### Production Product

**Connectors (脈客) · Private repository**

**AI-powered personal CRM，已上線 production**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **角色：** Product direction、architecture、AI-assisted delivery orchestration、Code Review、QA，以及 iOS/Android release delivery
- **AI-assisted implementation context：** React、NestJS、tRPC、SwiftUI、Kotlin Compose

## Engineering Track Record

13 年 production engineering 經驗，讓上述 reliability work 建立在真實交付系統，而非單純 Demo。我的 AI agent workflow 會實際操作 Git、CI、deployment、database 與真實 repositories。

### [Frontend Engineering Case Studies](https://github.com/stephen-taipei/frontend-engineering-case-studies)

前端工程背景中的部分 production architecture 成果：

- 設計並主導 Angular/Nx architecture，支援 100+ themes，將具代表性的 production theme leaf 降至 **23 行**
- 將單一 theme CSS request 約從 **2.4 MB 降至 17 KB**，約 99%，並將實測 Lighthouse Performance 由 **50+ 提升至 90+**
- 帶領 6 人 cross-functional engineering team

各成果的 scope、baseline 與明確 [未宣稱事項](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.md) 已獨立列出。

## Core Expertise

- **Systems building：** 將模糊問題轉成 explicit models、boundaries、workflows 與 executable systems
- **Agentic systems：** AI coding agents、multi-agent workflows、agent orchestration、tool-driven execution
- **Agent reliability：** evidence-bound validation、stale-state detection、reconciliation、fail-closed execution
- **Engineering governance：** policy as code、deterministic validation、bounded automation、safe delivery
- **Software architecture：** system boundaries、explicit ownership、behavior-preserving refactoring
- **Production engineering：** Git、CI/CD、Linux、deployment、observability、databases
- **Engineering foundation：** Node.js、NestJS、Angular、TypeScript、Nx、Laravel、PostgreSQL、MySQL、Redis

## Connect

歡迎針對 agentic systems、AI agent reliability、developer infrastructure 與 OSS collaboration 進行交流。

Taiwan · Remote

[Website](https://stephen.taipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [Case Studies](https://github.com/stephen-taipei/frontend-engineering-case-studies)
