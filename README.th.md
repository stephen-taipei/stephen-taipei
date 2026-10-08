# Stephen Chuang

[English](./README.md) · [繁體中文](./README.zh-TW.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [ไทย](./README.th.md)

### Agentic Infrastructure Engineer · AI-Native Systems Builder

ผมเปลี่ยนปัญหาที่กำกวมให้กลายเป็นระบบที่ชัดเจน workflow ที่ใช้งานได้ และ production outcome ที่ตรวจสอบได้

ปัจจุบันกำลังพัฒนา **Better Workflows** ซึ่งเป็น evidence-first reliability และ delivery control layer สำหรับ AI engineering agents

จุดสนใจหลักของผมคือ boundary ระหว่าง probabilistic AI agents กับ deterministic software delivery

> AI สามารถเสนอแนวทางและให้เหตุผลได้ แต่ production system ยังต้องการ evidence, authority, validation และ outcome proof

มีประสบการณ์ software engineering มากกว่า 13 ปี ครอบคลุม architecture, full-stack systems, CI/CD, production delivery, engineering leadership และ AI-native development

## สิ่งที่กำลังสร้าง

### โครงสร้างพื้นฐาน Agentic

เครื่องมือกลุ่มนี้ควบคุม AI coding agents ตั้งแต่เจตนาไปจนถึงการเปลี่ยนแปลงจริงใน repo โดยมี evidence, authority และ validation เป็นแกนหลัก

1. **[Better Workflows](https://betterworkflows.dev)** (ผลงานหลัก)

   **ชั้นควบคุมความน่าเชื่อถือและการส่งมอบงาน AI engineering แบบ evidence-first**

   [betterworkflows.dev](https://betterworkflows.dev) · [ซอร์สโค้ด](https://github.com/stephen-taipei/better-workflows) · [รุ่นที่เผยแพร่](https://github.com/stephen-taipei/better-workflows/releases/tag/V5.0.rc1)

   V5.0 RC1 — ติดตั้งฟรี (AGPL-3.0-only) รองรับ Codex, Gemini CLI และ Qwen Code; วางแผนรองรับ Claude Code ใน V5.1

   ```bash
   codex plugin marketplace add stephen-taipei/better-workflows
   codex plugin add better-workflows@better-workflows
   ```

   **เป้าหมายมาก่อน · ขับเคลื่อนด้วยหลักฐาน · หยุดเมื่อไม่แน่ชัด · ปรับตามความเสี่ยง**

2. **[Deckhand](https://github.com/stephen-taipei/deckhand)**: แถบเครื่องมือหลาย AI สำหรับ Claude Code พร้อม usage gauges, การสลับโมเดล, parallel sub agents และ second opinion แบบอ่านอย่างเดียวจาก Codex／Cursor／agy

3. **[Stephen Skills](https://github.com/stephen-taipei/stephen-skills)**: Agent Skills ที่ใช้ซ้ำได้ โดยใช้ `SKILL.md` แหล่งเดียวและติดตั้งแบบ native ได้ทั้งใน Claude Code และ Codex CLI

### ผลิตภัณฑ์ที่เปิดใช้งานแล้ว

**Connectors (脈客) · รีโพสิทอรีส่วนตัว**

**CRM ส่วนบุคคลขับเคลื่อนด้วย AI เปิดใช้งานจริงแล้ว**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **บทบาท:** Product direction, architecture, AI-assisted delivery orchestration, Code Review, QA และ iOS/Android release delivery
- **เทคโนโลยีที่พัฒนาร่วมกับ AI:** React, NestJS, tRPC, SwiftUI และ Kotlin Compose

## ผลงานด้านวิศวกรรม

ประสบการณ์ production engineering 13 ปีทำให้ reliability work ข้างต้นตั้งอยู่บนระบบส่งมอบจริง ไม่ใช่เพียง demo Workflow ของ AI agents ที่ผมใช้ทำงานกับ Git, CI, deployment, database และ repository จริง

### [กรณีศึกษาวิศวกรรม Frontend](https://github.com/stephen-taipei/frontend-engineering-case-studies)

ผลงาน production architecture จากพื้นฐาน frontend engineering:

- ออกแบบและนำ Angular/Nx architecture ที่รองรับ 100+ themes และลด representative production theme leaf เหลือ **23 บรรทัด**
- ลด theme CSS request หนึ่งชุดจากประมาณ **2.4 MB เหลือ 17 KB** หรือประมาณ 99% และเพิ่ม measured Lighthouse Performance จาก **50+ เป็น 90+**
- นำ cross-functional engineering team จำนวน 6 คน

Scope, baseline และสิ่งที่ [ไม่ได้อ้าง](https://github.com/stephen-taipei/frontend-engineering-case-studies/blob/main/docs/evidence-boundaries.md) ถูกแยกไว้ชัดเจนสำหรับแต่ละผลลัพธ์

## ความเชี่ยวชาญหลัก

- **การสร้างระบบ:** เปลี่ยนปัญหากำกวมให้เป็น explicit models, boundaries, workflows และ executable systems
- **ระบบ Agentic:** AI coding agents, multi-agent workflows, agent orchestration, tool-driven execution
- **ความน่าเชื่อถือของ Agent:** evidence-bound validation, stale-state detection, reconciliation, fail-closed execution
- **ธรรมาภิบาลทางวิศวกรรม:** policy as code, deterministic validation, bounded automation, safe delivery
- **สถาปัตยกรรมซอฟต์แวร์:** system boundaries, explicit ownership, behavior-preserving refactoring
- **วิศวกรรม Production:** Git, CI/CD, Linux, deployment, observability, databases
- **พื้นฐานทางวิศวกรรม:** Node.js, NestJS, Angular, TypeScript, Nx, Laravel, PostgreSQL, MySQL, Redis

## ติดต่อ

ยินดีพูดคุยเรื่อง agentic systems, AI agent reliability, developer infrastructure และ OSS collaboration

ไต้หวัน · ทำงานระยะไกล

[เว็บไซต์](https://stephen.taipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [กรณีศึกษา](https://github.com/stephen-taipei/frontend-engineering-case-studies)
