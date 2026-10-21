# Stephen Chuang

[English](./README.md) · [繁體中文](./README.zh-TW.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [ไทย](./README.th.md)

### AI-Native Systems Builder · Agentic Systems Engineer

曖昧な課題を、具体的なシステム、ワークフロー、production outcome に変えることを得意としています。

現在は **Better Workflows** を開発しています。これは AI engineering agents のための evidence-first reliability と delivery control layer です。

現在の主なテーマは probabilistic AI agents と deterministic software delivery の境界です。

> AI は提案し推論できます。Production system には依然として evidence、authority、validation、outcome proof が必要です。

Software engineering の経験は 13+ 年で、architecture、full-stack systems、CI/CD、production delivery、engineering leadership、AI-native development を含みます。

## 現在取り組んでいること

### Agentic インフラストラクチャ

このツール群は evidence、authority、validation を核に、AI coding agents が意図から実際の repo 変更へ進む過程を管理します。

1. **[Better Workflows](https://betterworkflows.dev)** （主力）

   **Evidence-first な AI エンジニアリングの信頼性とデリバリーのゲートキーパー**

   [betterworkflows.dev](https://betterworkflows.dev) · [ソースコード](https://github.com/stephen-taipei/better-workflows) · [npm](https://www.npmjs.com/package/@better-workflows/core)

   V6 Core 6.0.0-alpha.2 — 無料でインストール可能（Apache-2.0）。まず Claude Code に対応し、Codex、Gemini CLI、Qwen Code は対応予定です。V5 は RC1 で凍結されています（AGPL-3.0-only）。

   ```bash
   npm install -g @better-workflows/core@alpha
   claude plugin marketplace add stephen-taipei/better-workflows
   claude plugin install better-workflows-core@better-workflows --scope local
   bw init
   ```

   **目標優先 · エビデンス駆動 · フェイルクローズ · リスク適応型**

2. **[Deckhand](https://github.com/stephen-taipei/deckhand)**: Claude Code 向けのマルチ AI ツールバーで、usage gauges、モデル切り替え、parallel sub agents、Codex／Cursor／agy からの読み取り専用 second opinion を提供します。

3. **[Intent Galaxy](https://github.com/stephen-taipei/intent-galaxy)**: あいまいな目標をひとつ、銀河マップに展開します。まず発散して死角を見つけ、次にキーボード操作で収束させ、確定的な意図仕様にまとめます。[npm](https://www.npmjs.com/package/@stephen.taipei/intent-galaxy)

**その他のオープンソース：** **[Adorable Git Graph](https://github.com/stephen-taipei/adorable-git-graph)**: git の履歴をスクロールできるマンガ風の絵にします。commit は表情のある小さな球、branch は流れるパイプです。[デモ](https://stephen-taipei.github.io/adorable-git-graph/) · [npm](https://www.npmjs.com/package/@stephen.taipei/adorable-git-graph)

[オープンソース一覧 →](https://stephen.taipei/ja/open-source)

### 提供中のプロダクト

**Connectors (脈客) · 非公開リポジトリ**

**AI 搭載のパーソナル CRM、本番リリース済み**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **役割:** Product direction、architecture、AI-assisted delivery orchestration、Code Review、QA、iOS release delivery
- **状況：** iOS と Web で公開中 · Android は開発中
- **AI 支援による実装技術:** React、NestJS、tRPC、SwiftUI、Kotlin Compose

## エンジニアリング実績

13 年の production engineering 経験により、reliability work はデモだけではなく実際の delivery system を前提としています。私の AI agent workflow は Git、CI、deployment、database、実 repository を扱います。

### [フロントエンドエンジニアリング事例](https://github.com/stephen-taipei/frontend-engineering-case-studies)

フロントエンドエンジニアリングでの代表的な production architecture 実績:

- 100+ themes を支える Angular/Nx architecture を設計・主導し、代表的な production theme leaf を **23 行**まで削減
- 単一 theme CSS request を約 **2.4 MB から 17 KB** へ約 99% 削減し、実測 Lighthouse Performance を **50+ から 90+** へ改善
- フロントエンドエンジニア3–4名を直接率い、直属ではない複数のサポートエンジニアとの連携を調整。社内技術共有会を不定期に主催。

各成果の scope、baseline、明示的な [主張しない事項](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.md) を分離して記載しています。

## コア専門領域

- **システム構築:** 曖昧な課題を explicit models、boundaries、workflows、executable systems へ変換
- **Agentic システム:** AI coding agents、multi-agent workflows、agent orchestration、tool-driven execution
- **Agent 信頼性:** evidence-bound validation、stale-state detection、reconciliation、fail-closed execution
- **エンジニアリングガバナンス:** policy as code、deterministic validation、bounded automation、safe delivery
- **ソフトウェアアーキテクチャ:** system boundaries、explicit ownership、behavior-preserving refactoring
- **本番環境エンジニアリング:** Git、CI/CD、Linux、deployment、observability、databases
- **エンジニアリング基盤:** Node.js、NestJS、Angular、TypeScript、Nx、Laravel、PostgreSQL、MySQL、Redis

## 連絡先

Agentic systems、AI agent reliability、developer infrastructure、OSS collaboration に関する対話を歓迎します。

台湾 · リモート

[ウェブサイト](https://stephen.taipei) · [記事](https://stephen.taipei/ja/articles) · [LinkedIn](https://www.linkedin.com/in/stephentaipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [事例研究](https://github.com/stephen-taipei/frontend-engineering-case-studies)
