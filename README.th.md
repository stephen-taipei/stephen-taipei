# Stephen Chuang

[English](./README.md) · [繁體中文](./README.zh-TW.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [ไทย](./README.th.md)

### AI-Native Systems Builder · Agentic Systems Engineer

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

   [betterworkflows.dev](https://betterworkflows.dev) · [ซอร์สโค้ด](https://github.com/stephen-taipei/better-workflows) · [npm](https://www.npmjs.com/package/@better-workflows/core)

   V6 Core 6.0.0-alpha.2 — ติดตั้งฟรี (Apache-2.0) รองรับ Claude Code ก่อน ส่วน Codex, Gemini CLI และ Qwen Code อยู่ในแผน V5 ตรึงไว้ที่ RC1 (AGPL-3.0-only)

   ```bash
   npm install -g @better-workflows/core@alpha
   claude plugin marketplace add stephen-taipei/better-workflows
   claude plugin install better-workflows-core@better-workflows --scope local
   bw init
   ```

   **เป้าหมายมาก่อน · ขับเคลื่อนด้วยหลักฐาน · หยุดเมื่อไม่แน่ชัด · ปรับตามความเสี่ยง**

2. **[Deckhand](https://github.com/stephen-taipei/deckhand)**: แถบเครื่องมือหลาย AI สำหรับ Claude Code พร้อม usage gauges, การสลับโมเดล, parallel sub agents และ second opinion แบบอ่านอย่างเดียวจาก Codex／Cursor／agy

3. **[Intent Galaxy](https://github.com/stephen-taipei/intent-galaxy)**: ขยายเป้าหมายที่คลุมเครือหนึ่งข้อให้เป็นแผนที่กาแล็กซี: เริ่มจากกระจายความคิดเพื่อมองเห็นจุดบอด แล้วใช้แป้นพิมพ์รวบให้เป็นสเปกความตั้งใจที่แน่นอน [npm](https://www.npmjs.com/package/@stephen.taipei/intent-galaxy)

**โอเพนซอร์สอื่น ๆ:** **[Adorable Git Graph](https://github.com/stephen-taipei/adorable-git-graph)**: ประวัติ git ของคุณในรูปการ์ตูนที่เลื่อนดูได้: แต่ละ commit เป็นลูกบอลที่มีสีหน้า และแต่ละ branch เป็นท่อที่ไหลต่อกัน [เดโม](https://stephen-taipei.github.io/adorable-git-graph/) · [npm](https://www.npmjs.com/package/@stephen.taipei/adorable-git-graph)

[โปรเจกต์โอเพนซอร์สทั้งหมด →](https://stephen.taipei/th/open-source)

### ผลิตภัณฑ์ที่เปิดใช้งานแล้ว

**Connectors (脈客) · รีโพสิทอรีส่วนตัว**

**CRM ส่วนบุคคลขับเคลื่อนด้วย AI เปิดใช้งานจริงแล้ว**

[ctrs.app](https://ctrs.app) · [App Store](https://apps.apple.com/tw/app/%E8%84%88%E5%AE%A2-connectors-ai-crm/id6758259873)

- **บทบาท:** Product direction, architecture, AI-assisted delivery orchestration, Code Review, QA และ iOS release delivery
- **สถานะ:** ใช้งานได้แล้วบน iOS และเว็บ · Android กำลังพัฒนา
- **เทคโนโลยีที่พัฒนาร่วมกับ AI:** React, NestJS, tRPC, SwiftUI และ Kotlin Compose

## ผลงานด้านวิศวกรรม

ประสบการณ์ production engineering 13 ปีทำให้ reliability work ข้างต้นตั้งอยู่บนระบบส่งมอบจริง ไม่ใช่เพียง demo Workflow ของ AI agents ที่ผมใช้ทำงานกับ Git, CI, deployment, database และ repository จริง

### [กรณีศึกษาวิศวกรรม Frontend](https://github.com/stephen-taipei/frontend-engineering-case-studies)

ผลงาน production architecture จากพื้นฐาน frontend engineering:

- ออกแบบและนำ Angular/Nx architecture ที่รองรับ 100+ themes และลด representative production theme leaf เหลือ **23 บรรทัด**
- ลด theme CSS request หนึ่งชุดจากประมาณ **2.4 MB เหลือ 17 KB** หรือประมาณ 99% และเพิ่ม measured Lighthouse Performance จาก **50+ เป็น 90+**
- นำทีมวิศวกร frontend 3–4 คนโดยตรง ประสานงานกับวิศวกรสนับสนุนหลายคนที่ไม่ได้ขึ้นตรงกับผม และจัดเทคทอล์กภายในเป็นครั้งคราว

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

[เว็บไซต์](https://stephen.taipei) · [บทความ](https://stephen.taipei/th/articles) · [LinkedIn](https://www.linkedin.com/in/stephentaipei) · [Better Workflows](https://betterworkflows.dev) · [Connectors](https://ctrs.app) · [กรณีศึกษา](https://github.com/stephen-taipei/frontend-engineering-case-studies)
