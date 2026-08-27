<div align="center">

# Aneesh Patne

### Backend and applied AI engineer building reliable data, retrieval, and automation systems

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=flat-square&logo=safari&logoColor=58a6ff)](https://aneeshpatne.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=58a6ff)](https://www.linkedin.com/in/aneeshpatne/)
[![Email](https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=ea4335)](mailto:aneeshpatne12@gmail.com)

**Fresher · Open to backend and applied AI roles · Willing to work in Mumbai or Bengaluru · Open to remote roles**

</div>

I am an early-career engineer who likes taking systems beyond the demo stage. I build and operate software that collects real-world data, survives unreliable dependencies, and turns that data into something useful—from breaking-news alerts and searchable camera footage to developer tools used by others.

My strongest work is in backend systems, data pipelines, retrieval, and applied AI. I care about explicit state, measurable behavior, safe failure recovery, and documenting what a system can and cannot do.

## Featured work

### [Nova](https://github.com/aneeshpatne/Nova) — A personal breaking-news desk

Nova monitors public news sources throughout the day, reads and deduplicates new articles, and alerts me to important developments—typically within **15 minutes**—through Discord, a network siren, and a Kindle display.

It has operated continuously since June 2026, extracting **6,643 articles** from **21,182 visited pages across 666 sources**—about **99 articles per day**—and delivering **550 breaking-news alerts** as of August 2026. Failed channels can be retried independently, duplicate ingestion is guarded at the database boundary, and browser failures do not discard already completed work.

`TypeScript` · `Bun` · `BullMQ` · `Redis` · `gRPC` · `PostgreSQL` · `pgvector`

**[Source code](https://github.com/aneeshpatne/Nova)** · **[Case study](https://aneeshpatne.com/projects/nova)**

### [WeeklyGrant](https://github.com/aneeshpatne/weeklygrant) — A privacy-first Codex usage estimator

WeeklyGrant is an npm CLI and interactive terminal app that estimates what a weekly Codex grant would cost at API rates. It reads local session logs without uploading their contents and provides both a human-friendly interface and redacted JSON output for automation.

The package reached **1,500+ npm downloads in its first weeks**. It ships with automated tests, CI, dependency audits, release history, and security documentation.

`TypeScript` · `Node.js` · `React Ink` · `Worker Threads` · `CI`

**[Source code](https://github.com/aneeshpatne/weeklygrant)** · **[Case study](https://aneeshpatne.com/projects/weeklygrant)** · **[npm](https://www.npmjs.com/package/weeklygrant)**

### [CCTV](https://github.com/aneeshpatne/CCTV) — Searchable, self-hosted video monitoring

CCTV turns an ESP32-CAM feed into a live health view, searchable recordings, motion events, trimmed clips, and scheduled Discord reports. The current deployment retains roughly **500 hours of footage** and **5,760 indexed motion events**.

I moved the latency-sensitive capture path from Python to Swift while retaining Python as an automatic fallback. In a documented Apple M4 rollout canary, the native path reduced median capture-process CPU by **65.6%** and representative segment size by **69.3%**. The repository includes **128 tests** across Python and Swift and documents the benchmark limitations.

`Swift` · `Python` · `VideoToolbox` · `Vision` · `FastAPI` · `SQLite` · `gRPC`

**[Source code](https://github.com/aneeshpatne/CCTV)** · **[Case study](https://aneeshpatne.com/projects/cctv)**

## Selected additional work

| Project | What I built | Links |
| --- | --- | --- |
| **Nilo** | A desktop workspace for running coding agents against real repositories, with approval gates, inspectable patches, isolated Git worktrees, resumable event history, SSH execution, and 148 automated tests. | [Source](https://github.com/aneeshpatne/Nilo) · [Case study](https://aneeshpatne.com/projects/nilo) |
| **Midas** | An Indian-equity research desk that investigates a company, sector, or event; preserves the supporting evidence; challenges its first conclusion; and produces a structured decision brief that a person can review instead of asking them to trust one opaque answer. | [Source](https://github.com/aneeshpatne/Midas) · [Case study](https://aneeshpatne.com/projects/midas) |
| **HealthMaxxing** | A SwiftUI and Bun/Fastify monorepo that captures Bluetooth smart-scale readings, tracks body composition over time, and creates asynchronous insight reports. Its live dataset contains 185 measurements and 736 generated reports. | [Source](https://github.com/aneeshpatne/healthmaxxing) · [Case study](https://aneeshpatne.com/projects/forma-ios) |
| **Atlas** | A Go control plane that schedules browser, text, weather, and sensor views across repurposed Kindle dashboards, with lifecycle supervision and health monitoring. | Source private · [Case study](https://aneeshpatne.com/projects/atlas) |
| **Suraksha** | A multi-tenant authentication service with token rotation, OTP flows, asynchronous messaging, and schema migrations. | [Source](https://github.com/aneeshpatne/suraksha) · [Case study](https://aneeshpatne.com/projects/suraksha) |
| **Mausam 3.0** | A Mumbai weather pipeline that captures radar and forecast evidence, skips unchanged inputs, and feeds downstream analysis and alerts. | [Source](https://github.com/aneeshpatne/mausam3.0) · [Case study](https://aneeshpatne.com/projects/mausam-3) |

## Core technologies

- **Languages:** TypeScript, Python, Go, Swift, Kotlin
- **Backend and data:** Bun, FastAPI, PostgreSQL, Redis, BullMQ, SQLite
- **Retrieval and applied AI:** pgvector, OpenSearch, embeddings, tool-using workflows
- **Interfaces and operations:** gRPC, Protocol Buffers, REST, Docker, Linux, CI

I am looking for a team where I can grow through production backend or applied AI work while bringing the ownership and systems thinking demonstrated here. If that sounds relevant, reach me through [email](mailto:aneeshpatne12@gmail.com) or [LinkedIn](https://www.linkedin.com/in/aneeshpatne/).
