<div align="center">

# Aneesh Patne

### Backend and applied AI engineer building reliable data, retrieval, and automation systems

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=flat-square&logo=safari&logoColor=58a6ff)](https://aneeshpatne.com)
[![Resume](https://img.shields.io/badge/Resume-0d1117?style=flat-square&logo=readme&logoColor=58a6ff)](https://aneeshpatne.com/resume/Aneesh%20Patne.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=58a6ff)](https://www.linkedin.com/in/aneeshpatne/)
[![Email](https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=ea4335)](mailto:aneeshpatne12@gmail.com)

**Seeking my first full-time backend or applied AI engineering role · Open to Mumbai, Bengaluru, and remote opportunities**

</div>

I build backend systems and applied AI tools for problems I encounter myself from monitoring breaking news to searching camera footage. My projects include continuously running services, a published npm CLI, and a native video pipeline.

## Featured work

_Operating figures below are snapshots verified on August 29, 2026._

### [Nova](https://github.com/aneeshpatne/Nova) — A personal breaking-news desk

Nova monitors public news sources, reads and deduplicates new articles, and sends important developments to Discord, a network siren, and a Kindle display. In a **67-day** operating snapshot, it extracted **6,643 articles** from **21,182 visited URLs** across **666 source hosts**. A parsing-workflow comparison extracted about **20% more articles** with about **78% fewer duplicates**; database constraints also prevent concurrent ingestors from storing the same article twice.

`TypeScript` · `Bun` · `BullMQ` · `Redis` · `gRPC` · `PostgreSQL` · `pgvector`

**[Source code](https://github.com/aneeshpatne/Nova)** · **[Case study](https://aneeshpatne.com/projects/nova)**

### [WeeklyGrant](https://github.com/aneeshpatne/weeklygrant) — A privacy-first Codex usage estimator

WeeklyGrant is an npm CLI and interactive terminal app that estimates what a weekly Codex grant would cost at API rates. It reads local session logs without uploading their contents and provides both a human-friendly interface and redacted JSON output for automation.

The package has recorded **1,000+ npm downloads**. I reduced its runtime dependencies from **2 to 0** while retaining automated tests, CI, dependency audits, release history, and security documentation.

`TypeScript` · `Node.js` · `React Ink` · `Worker Threads` · `CI`

**[Source code](https://github.com/aneeshpatne/weeklygrant)** · **[Case study](https://aneeshpatne.com/projects/weeklygrant)** · **[npm](https://www.npmjs.com/package/weeklygrant)**

### [CCTV](https://github.com/aneeshpatne/CCTV) — Searchable, self-hosted video monitoring

CCTV turns an ESP32-CAM feed into a live health view, searchable recordings, motion events, trimmed clips, and scheduled Discord reports. The current deployment retains roughly **500 hours of footage** and **5,760 indexed motion events**.

I moved the latency-sensitive capture path from Python to Swift while retaining Python as an automatic fallback. In a documented Apple M4 rollout canary, the native path reduced median capture-process CPU by **65.6%** and representative segment size by **69.3%**. The repository includes **128 tests** across Python and Swift and documents the benchmark limitations.

`Swift` · `Python` · `VideoToolbox` · `Vision` · `FastAPI` · `SQLite` · `gRPC`

**[Source code](https://github.com/aneeshpatne/CCTV)** · **[Benchmark](https://github.com/aneeshpatne/CCTV/blob/main/benchmarks/canary-results.md)** · **[Case study](https://aneeshpatne.com/projects/cctv)**

## Selected additional work

| Project           | What I built                                                                                                                                                 | Links                                                                                                             |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| **Nilo**          | A desktop workspace for running coding agents in isolated Git worktrees, with approval gates, inspectable patches, and resumable execution.                  | [Source](https://github.com/aneeshpatne/Nilo) · [Case study](https://aneeshpatne.com/projects/nilo)               |
| **HealthMaxxing** | A body-composition tracker with asynchronous insight reports; a workflow revision reduced mean insight-run token use by **59%** in a development comparison. | [Source](https://github.com/aneeshpatne/healthmaxxing) · [Case study](https://aneeshpatne.com/projects/forma-ios) |
| **Suraksha**      | A multi-tenant authentication service with token rotation, OTP flows, asynchronous messaging, and schema migrations.                                         | [Source](https://github.com/aneeshpatne/suraksha) · [Case study](https://aneeshpatne.com/projects/suraksha)       |
| **Mausam 3.0**    | A Mumbai weather pipeline that delivered **392 reports over 63 days** and skips analysis and notifications when radar imagery is unchanged.                  | [Source](https://github.com/aneeshpatne/mausam3.0) · [Case study](https://aneeshpatne.com/projects/mausam-3)      |

## Core technologies

- **Languages:** TypeScript, Python, Go, Swift, Kotlin
- **Backend and data:** Bun, FastAPI, PostgreSQL, Redis, BullMQ, SQLite
- **Retrieval and applied AI:** pgvector, OpenSearch, embeddings, tool-using workflows
- **Interfaces and operations:** gRPC, Protocol Buffers, REST, Docker, Linux, CI
