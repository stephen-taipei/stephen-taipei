# Stephen Chuang

[English](./README.md) · [繁體中文](./README.zh-TW.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [ไทย](./README.th.md)

### Agentic Infrastructure Engineer · AI-Native Systems Builder

我擅长把模糊问题转化为具体系统、工作流和可落地的 production outcome。

目前正在构建 **Better Workflows**，一个以 evidence-first 为核心的 AI engineering reliability 与 delivery control layer。

我目前关注 probabilistic AI agents 与 deterministic software delivery 之间的边界。

> AI 可以提出方案和推理。Production system 仍然需要 evidence、authority、validation 和 outcome proof。

拥有 13+ 年 software engineering 经验，涵盖 architecture、full-stack systems、CI/CD、production delivery、engineering leadership 与 AI-native development。

## 当前项目

### Agentic 基础设施

这组工具以 evidence、authority、validation 为核心，管控 AI coding agents 从意图到真实 repo 变更的过程。

1. **[Better Workflows](https://betterworkflows.dev)** （主力）

   **以 evidence 为先的 AI 工程可靠性与交付守门层**

   [betterworkflows.dev](https://betterworkflows.dev) · [源代码](https://github.com/stephen-taipei/better-workflows) · [发布版本](https://github.com/stephen-taipei/better-workflows/releases/tag/V5.0.rc1)

   V5.0 RC1 — 可免费安装（AGPL-3.0-only）。支持 Codex、Gemini CLI、Qwen Code；Claude Code 计划于 V5.1。

   ```bash
   codex plugin marketplace add stephen-taipei/better-workflows
   codex plugin add better-workflows@better-workflows
   ```

   **目标优先 · 证据驱动 · 失效即阻断 · 风险自适应**

2. **[Deckhand](https://github.com/stephen-taipei/deckhand)**: Claude Code 的多 AI 工具栏，提供 usage gauges、模型切换、parallel sub agents，以及来自 Codex／Cursor／agy 的只读 second opinion。

3. **[Stephen Skills](https://github.com/stephen-taipei/stephen-skills)**: 可复用的 Agent Skills；以同一份 `SKILL.md` 为来源，Claude Code 和 Codex CLI 都能原生安装。

### 已上线产品

**Connectors (脈客) · 私有仓库**

**AI 驱动的个人 CRM，已正式上线**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **角色：** Product direction、architecture、AI-assisted delivery orchestration、Code Review、QA，以及 iOS/Android release delivery
- **AI 辅助实现技术：** React、NestJS、tRPC、SwiftUI、Kotlin Compose

## 工程实绩

13 年 production engineering 经验，让上述 reliability work 建立在真实交付系统上。我的 AI agent workflow 会实际接触 Git、CI、deployment、database 和真实 repositories。

### [前端工程案例研究](https://github.com/stephen-taipei/frontend-engineering-case-studies)

前端工程背景中的部分 production architecture 成果：

- 设计并主导 Angular/Nx architecture，支持 100+ themes，将一个具有代表性的 production theme leaf 降到 **23 行**
- 将单一 theme CSS request 约从 **2.4 MB 降到 17 KB**，约 99%，并将实测 Lighthouse Performance 从 **50+ 提升到 90+**
- 带领 6 人 cross-functional engineering team

各成果的 scope、baseline 和明确 [未声明事项](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.md) 已独立列出。

## 核心专长

- **系统构建：** 将模糊问题转成 explicit models、boundaries、workflows 与 executable systems
- **Agentic 系统：** AI coding agents、multi-agent workflows、agent orchestration、tool-driven execution
- **Agent 可靠性：** evidence-bound validation、stale-state detection、reconciliation、fail-closed execution
- **工程治理：** policy as code、deterministic validation、bounded automation、safe delivery
- **软件架构：** system boundaries、explicit ownership、behavior-preserving refactoring
- **生产环境工程：** Git、CI/CD、Linux、deployment、observability、databases
- **工程基础：** Node.js、NestJS、Angular、TypeScript、Nx、Laravel、PostgreSQL、MySQL、Redis

## 联系

欢迎就 agentic systems、AI agent reliability、developer infrastructure 和 OSS collaboration 进行交流。

台湾 · 远程

[个人网站](https://stephen.taipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [案例研究](https://github.com/stephen-taipei/frontend-engineering-case-studies)
