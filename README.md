# Stephen Chuang

[繁體中文 →](./README.zh-TW.md)

### Agentic Systems Engineer · AI Agent Reliability

Building **Better Workflows**, an evidence-first QA and delivery control layer for AI engineering agents.

I work on the boundary between probabilistic AI agents and deterministic software delivery.

> AI can propose and reason. Production systems still need evidence, authority, validation, and proof of outcome.

My current focus is making autonomous engineering workflows safer and more reliable through evidence-bound validation, explicit authority and scope, fail-closed execution, stale-state detection, unknown-outcome reconciliation, bounded side effects, task-isolated Git workflows, and deterministic delivery gates.

A prompt can describe intent. It does not prove authority, current state, or successful execution. Better Workflows turns those gaps into explicit, verifiable control points.

13+ years of software engineering — frontend architecture, full-stack systems, CI/CD, production delivery, engineering leadership, and extensive hands-on use of AI coding agents.

## What I'm Building

### 1. Better Workflows

**Evidence-first AI engineering QA + delivery gatekeeper**

[betterworkflows.dev](https://betterworkflows.dev) · [Source](https://github.com/stephen-taipei/better-workflows) *(private during the V5 rewrite — opening at public release)*

Better Workflows governs how AI coding agents move from intent to real repository changes. It separates agent judgment from deterministic validation, binds evidence to the current repository, revision, scope and target, and stops when evidence becomes stale or an external action has an unknown outcome.

**Goal-first · Evidence-driven · Fail-closed · Risk-adaptive**

Current areas of work:

- Agent authority and scope boundaries
- Evidence freshness and provenance
- Deterministic validation
- Risk-adaptive workflow routing
- Provider reconciliation
- Safe Git mutation and task-isolated integration
- Multi-agent engineering workflows
- Autonomous delivery reliability

### 2. Connectors (脈客)

**AI-powered personal CRM, shipped to production**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **Role:** Product direction, architecture, AI-assisted delivery orchestration, Code Review, QA, and iOS/Android release delivery.
- **AI-assisted implementation context:** React, NestJS, tRPC, SwiftUI, and Kotlin Compose.

### 3. [stephen-skills](https://github.com/stephen-taipei/stephen-skills)

Claude Code skills, hooks and commands for AI-native development workflow — the day-to-day agent tooling behind the reliability work above.

## Engineering Track Record

Thirteen years of production engineering is why the reliability work above is grounded in real delivery systems rather than demos: AI agents in my workflows touch Git, CI, deployment, databases, and real repositories.

### [Frontend Engineering Case Studies](https://github.com/stephen-taipei/frontend-engineering-case-studies)

A runnable, sanitized Angular/Nx implementation of config-driven multi-theme architecture with three fictional themes, typed contracts, `core / view / theme` boundaries, facade/service separation, family-completeness tests, on-demand CSS, bilingual decision records, and explicit [evidence boundaries](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.md).

- **[Config-driven multi-theme architecture](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/case-studies/config-driven-multi-theme.md)** — Designed and led a unified Angular/Nx architecture supporting 100+ themes and multiple layouts. A one-way `selector → theme leaf → shared view → core` flow, explicit facade/service ownership, and cross-theme completeness tests turned complex customization into typed configuration; within the migration, a representative complete production theme leaf was reduced to **23 lines**. Rollout scope: 70 purpose-specific modules — 24 facades, 10 data services, 10 theme configs, and 26 shared views.
- **[Measured web performance](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/case-studies/on-demand-theme-css.md)** — Led on-demand loading for 136 theme CSS files, reducing a single theme resource request from approximately **2.4 MB to 17 KB — about 99%**. Separately, improved Lighthouse Performance on key measured pages from **50+ to 90+**, while also improving accessibility, best practices, SEO, and AEO for generative-search experiences.
- **Engineering leadership** — Led a 6-person cross-functional team and handled technical interviews, architecture planning, Code Review, work allocation, and delivery schedules.
- **Product growth** — Helped a client grow its product from 0 to 20,000 members within one year.

## Core Expertise

- **Agentic systems:** AI coding agents, multi-agent workflows, agent orchestration, tool-driven execution
- **Agent reliability:** evidence-bound validation, stale-state detection, reconciliation, fail-closed execution
- **Engineering governance:** policy as code, deterministic validation, bounded automation, safe delivery
- **Software architecture:** system boundaries, explicit ownership, behavior-preserving refactoring
- **Production engineering:** Git, CI/CD, Linux, deployment, observability, databases
- **Frontend architecture:** Angular, TypeScript, Nx, config-driven platforms, web performance, accessibility, SEO/AEO
- **Full-stack background:** Node.js, NestJS, Laravel, PHP, MySQL, PostgreSQL, Redis

## Currently Building

I'm focused on Better Workflows and the reliability layer required for increasingly autonomous AI engineering agents.

Interested in conversations around:

- AI coding agents and agentic SDLC
- AI agent reliability and governance
- Developer infrastructure
- Multi-agent systems
- OSS collaboration

Selective conversations around agentic systems, developer infrastructure and AI engineering reliability are welcome.

Taiwan · Remote

[Website](https://stephen.taipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [Case Studies](https://github.com/stephen-taipei/frontend-engineering-case-studies)
