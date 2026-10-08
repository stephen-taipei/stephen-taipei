# Stephen Chuang

[English](./README.md) · [繁體中文](./README.zh-TW.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [ไทย](./README.th.md)

### Agentic Infrastructure Engineer · AI-Native Systems Builder

모호한 문제를 구체적인 시스템, workflow, production outcome으로 바꾸는 일을 합니다.

현재 **Better Workflows**를 만들고 있습니다. AI engineering agents를 위한 evidence-first reliability 및 delivery control layer입니다.

현재 주된 관심사는 probabilistic AI agents와 deterministic software delivery 사이의 경계입니다.

> AI는 제안하고 추론할 수 있습니다. Production system에는 여전히 evidence, authority, validation, outcome proof가 필요합니다.

13+년의 software engineering 경험을 보유하고 있으며 architecture, full-stack systems, CI/CD, production delivery, engineering leadership, AI-native development를 다뤄왔습니다.

## 현재 만들고 있는 것

### Agentic 인프라

이 도구 모음은 evidence, authority, validation을 중심으로 AI coding agents가 의도에서 실제 repo 변경으로 나아가는 과정을 관리합니다.

1. **[Better Workflows](https://betterworkflows.dev)** (주력)

   **Evidence-first AI 엔지니어링 신뢰성 + 딜리버리 게이트키퍼**

   [betterworkflows.dev](https://betterworkflows.dev) · [소스 코드](https://github.com/stephen-taipei/better-workflows) · [릴리스](https://github.com/stephen-taipei/better-workflows/releases/tag/V5.0.rc1)

   V5.0 RC1 — 무료 설치 가능(AGPL-3.0-only). Codex, Gemini CLI, Qwen Code 지원; Claude Code는 V5.1에서 지원 예정입니다.

   ```bash
   codex plugin marketplace add stephen-taipei/better-workflows
   codex plugin add better-workflows@better-workflows
   ```

   **목표 우선 · 증거 기반 · 실패 시 차단 · 위험 적응형**

2. **[Deckhand](https://github.com/stephen-taipei/deckhand)**: Claude Code용 멀티 AI 도구 모음으로 usage gauges, 모델 전환, parallel sub agents, Codex／Cursor／agy의 읽기 전용 second opinion을 제공합니다.

3. **[Stephen Skills](https://github.com/stephen-taipei/stephen-skills)**: 재사용 가능한 Agent Skills로, 하나의 `SKILL.md` 소스를 Claude Code와 Codex CLI 모두에 네이티브로 설치할 수 있습니다.

### 출시된 제품

**Connectors (脈客) · 비공개 저장소**

**AI 기반 개인 CRM, 프로덕션 출시 완료**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **역할:** Product direction, architecture, AI-assisted delivery orchestration, Code Review, QA, iOS/Android release delivery
- **AI 지원 구현 기술:** React, NestJS, tRPC, SwiftUI, Kotlin Compose

## 엔지니어링 실적

13년의 production engineering 경험 덕분에 위 reliability work는 단순 demo가 아닌 실제 delivery system을 기반으로 합니다. 제 AI agent workflow는 Git, CI, deployment, database, 실제 repositories를 다룹니다.

### [프론트엔드 엔지니어링 사례 연구](https://github.com/stephen-taipei/frontend-engineering-case-studies)

프론트엔드 엔지니어링 배경의 대표적인 production architecture 성과:

- 100+ themes를 지원하는 Angular/Nx architecture를 설계하고 주도해 대표 production theme leaf를 **23줄**로 축소
- 단일 theme CSS request를 약 **2.4 MB에서 17 KB**로 약 99% 줄이고, 측정된 Lighthouse Performance를 **50+에서 90+**로 개선
- 6인 cross-functional engineering team 리드

각 결과의 scope, baseline, 명시적 [주장하지 않는 사항](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.md)을 분리해 기록했습니다.

## 핵심 전문 분야

- **시스템 구축:** 모호한 문제를 explicit models, boundaries, workflows, executable systems로 변환
- **Agentic 시스템:** AI coding agents, multi-agent workflows, agent orchestration, tool-driven execution
- **Agent 신뢰성:** evidence-bound validation, stale-state detection, reconciliation, fail-closed execution
- **엔지니어링 거버넌스:** policy as code, deterministic validation, bounded automation, safe delivery
- **소프트웨어 아키텍처:** system boundaries, explicit ownership, behavior-preserving refactoring
- **프로덕션 엔지니어링:** Git, CI/CD, Linux, deployment, observability, databases
- **엔지니어링 기반:** Node.js, NestJS, Angular, TypeScript, Nx, Laravel, PostgreSQL, MySQL, Redis

## 연락

Agentic systems, AI agent reliability, developer infrastructure, OSS collaboration 관련 대화를 환영합니다.

대만 · 원격

[웹사이트](https://stephen.taipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [사례 연구](https://github.com/stephen-taipei/frontend-engineering-case-studies)
