# Eric San

**Security-Focused Full-Stack Engineer** · Singapore Citizen

📫 [ericsssan@gmail.com](mailto:ericsssan@gmail.com) · 🌐 [Web CV](https://ericsssan.github.io) · 💻 [github.com/ericsssan](https://github.com/ericsssan) · 💼 [LinkedIn](https://www.linkedin.com/in/ericsssan)

---

Full-stack engineer with 10 years of remote experience delivering **secure-by-design** web applications for client companies across Europe. I work the whole stack — product features and AI/RAG systems across Next.js, React, Django, Laravel, and Go — and own the cryptography and architecture that protect the data behind them. I also build the layers most engineers just consume: **TLS/QUIC transport, type checkers, and static analyzers**.

## 🧰 Technical Skills

| | |
|---|---|
| **Security** | End-to-end encryption (E2EE), cryptographic primitives, penetration-testing remediation, secure development practices |
| **Languages** | TypeScript / JavaScript, Python, PHP, Rust, Zig, Go, SQL |
| **Frontend** | React, React Native (Expo), Next.js, Vue.js, Tailwind CSS, Flutter |
| **Backend** | Django, Django REST Framework, Laravel, Node.js |
| **AI / LLM** | Retrieval-augmented generation (RAG), hybrid search, embeddings, reranking, Gemini |
| **Cloud & Infra** | Azure (AKS), Google Cloud, AWS, Supabase, Kubernetes, Docker, Terraform, Nginx |
| **Data & Queues** | PostgreSQL, pgvector, MySQL, Redis, Celery |
| **Testing** | Playwright, Vitest, Jest, pytest, PestPHP |
| **Observability** | New Relic, Datadog, Sentry |

## 💼 Experience

**Altern8 Technologies Pte Ltd** · Jun 2016 – Present · Remote
*Full-Stack Engineer → Team Lead → Senior Full-Stack Engineer (current)*
*Delivering full-stack products for client companies across Europe.*

- Built secure, encryption-first features for products handling sensitive user data.
- Hardened applications against issues surfaced in independent security audits, closing authentication and session-handling gaps.
- Led delivery across 5+ client products in healthcare, sales, and assessment, owning architecture, code quality, and CI/CD.
- Tuned database and query performance with caching, pre-computation, and indexing across data-heavy products.
- Modernized legacy client applications onto maintainable frameworks.

## 🚀 Selected Projects

- **Jarvis AI** — A production RAG platform that turns a fund's research archive into a conversational assistant. I build it across the stack: a Go + Python microservices backend — hybrid retrieval (semantic + keyword search, reranked), automated document ingestion, encryption and hardened auth — and a React Native mobile client. *Go, Python, React Native, Supabase/pgvector, Gemini, GCP.*
- **[AssetPass](https://assetpass.com)** — A digital-legacy platform where data is encrypted on the client and never readable by the server. I designed and built the encryption and secure-authentication layers. *Next.js on Kubernetes.*
- **[SalesGoal](https://www.salesgoal.com)** — A sales-management platform for pipeline tracking, performance analytics, and revenue forecasting. I built full-stack features across a Laravel backend and a React/TypeScript front end — drag-and-drop pipeline boards and interactive forecasting dashboards. *Laravel, React, TypeScript, visx, Playwright.*
- **[Asentaa SaaS Platform](https://www.asentaa.com)** — A multi-tenant candidate-assessment SaaS platform; I rebuilt it from a legacy on-site tool, reworking the scoring engine and migrating existing data. *Laravel, React, Tailwind CSS.*
- **[KeyForCare Analytics](https://www.keyforcare.se)** — I automated the report generation and distribution pipeline, cutting generation time ~70% through caching and pre-computation. *Vanilla PHP, Laravel, MySQL, Redis.*
- **Competitor Price Monitoring** — A real-time price-monitoring pipeline; I built the scheduled crawlers, anti-scraping handling, and alerting. *Django, React, PostgreSQL, Celery, Redis, Docker.*

## 🔬 Open Source

**A TypeScript toolchain in Zig**
- [ez](https://github.com/ericsssan/ez) — high-performance JS/TS parser + linter with a zero-copy ESLint plugin runner: run any ESLint plugin (core, `n`, `es-x`, `import`) against the Zig AST without reimplementing a single rule. SIMD lexer, struct-of-arrays AST.
- [ez-checker](https://github.com/ericsssan/ez-checker) — a from-scratch reimplementation of the TypeScript type checker (the type-system core of `tsc`) in Zig: full inference, control-flow narrowing, conditional/mapped/utility types. ~83% TypeScript-corpus conformance.
- [es-parser](https://github.com/ericsssan/es-parser) — the fast, standalone JS/TS/JSX parser the toolchain is built on; SIMD lexer, struct-of-arrays AST; 3,966/3,966 test262.

**Security & static analysis**
- [san](https://github.com/ericsssan/san) — deep static analyzer for `unsafe` Rust; rustc MIR driver, dataflow + typestate analysis, 132 checkers.
- [zbc](https://github.com/ericsssan/zbc) — infers Zig lifetime, ownership, and cleanup bugs with no annotations.

**Cryptography & networking**
- [zquic](https://github.com/ericsssan/zquic) — Sans-I/O QUIC library (RFC 9000/9001/9002), TLS 1.3 handshake, 0-RTT, zero dependencies.
- [zhttp3](https://github.com/ericsssan/zhttp3) — HTTP/3 framing, QPACK header compression, and a server layer built on zquic.

**Performance**
- [ic-fuzzer](https://github.com/ericsssan/ic-fuzzer) — diagnoses and fixes V8 JIT megamorphic deoptimizations in Node/TypeScript.

## 🎓 Education

- **B.Eng. Computer Engineering** — National University of Singapore
- **Diploma in Electrical & Electronics Engineering** — Singapore Polytechnic

---

*Open to new roles — security-focused full-stack, secure systems, or performance engineering.*
