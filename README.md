# Eric San

**Security-Focused Full-Stack Engineer** · Singapore

📫 [ericsssan@gmail.com](mailto:ericsssan@gmail.com) · 🌐 [Web CV](https://ericsssan.github.io) · 💻 [github.com/ericsssan](https://github.com/ericsssan)

---

Full-stack engineer with 10 years of remote experience building web applications that are **secure by design**. I work the whole stack — product features in Next.js, React, Django, and Laravel — and own the cryptography and architecture that protect the data behind them. I also go a layer deeper than most, building the kinds of systems applications usually just depend on: **TLS/QUIC transport, type checkers, and static analyzers**.

## 🧰 Technical Skills

| | |
|---|---|
| **Security** | End-to-end encryption (E2EE), cryptographic primitives, penetration-testing remediation, secure development practices |
| **Languages** | TypeScript / JavaScript, Python, PHP, Rust, Zig, Go, SQL |
| **Frontend** | React, Next.js, Vue.js, Tailwind CSS, Flutter |
| **Backend** | Django, Django REST Framework, Laravel, Node.js |
| **AI / LLM** | Retrieval-augmented generation (RAG), hybrid search, embeddings, reranking, Gemini |
| **Cloud & Infra** | Azure (AKS), Google Cloud, AWS, Supabase, Kubernetes, Docker, Terraform, Nginx |
| **Data & Queues** | PostgreSQL, pgvector, MySQL, Redis, Celery |
| **Testing** | Playwright, Vitest, Jest, pytest, PestPHP |
| **Observability** | New Relic, Datadog, Sentry |

## 💼 Experience

**Altern8 Technologies Pte Ltd** · Jun 2016 – Present · Remote
*Full-Stack Engineer → Team Lead → Senior Full-Stack Engineer (current)*

- Built secure, encryption-first features for products handling sensitive user data.
- Hardened applications against issues surfaced in independent security audits, closing authentication and session-handling gaps.
- Led delivery across 5+ client products in healthcare, sales, and assessment, owning architecture, code quality, and CI/CD.
- Tuned database and query performance with caching, pre-computation, and indexing across data-heavy products.
- Delivered applications end to end — from APIs, data models, and access control to modernizing legacy systems onto maintainable frameworks.

## 🚀 Selected Projects

- **AssetPass** (2025–Present) — A digital-legacy platform where data is encrypted on the client and never readable by the server. I designed and built the encryption and secure-authentication layers. *Next.js on Kubernetes.*
- **Jarvis AI** (2026) — A RAG platform that turns a fund manager's document archive into a queryable research partner. I built the Go microservices backend: REST + WebSocket streaming chat over a hybrid retrieval pipeline (vector + full-text search, reciprocal-rank fusion, Gemini reranking), event-driven workers over PGMQ queues, and email/web ingestion crawlers feeding a Python/Docling extraction service. Hardened it end to end — JWT and Google-OAuth auth, AES-256-GCM encryption of stored credentials, and a defense-in-depth HTTP layer (CSP, security headers, rate limiting). *Go, Python, Supabase (Postgres + pgvector), Gemini, GCP, Terraform.*
- **Competitor Price Monitoring** (2024) — Real-time scraping and analysis pipeline with scheduled jobs, anti-scraping measures, and alerting. *Django, React, PostgreSQL, Celery, Redis, Docker.*
- **Asentaa SaaS Platform** (2023) — Transformed a legacy onsite candidate-assessment system into a scalable multi-tenant SaaS platform; improved scoring algorithm and migrated legacy data. *Laravel, React, Tailwind CSS.*
- **KeyForCare Analytics** (2022) — Real-time analytics dashboard; caching and pre-calculation strategies reduced report generation time by an average of 70%.

## 🔬 Open Source

**Security & correctness**
- [san](https://github.com/ericsssan/san) — deep static analyzer for `unsafe` Rust; rustc MIR driver, dataflow + typestate analysis, 132 checkers.
- [zbc](https://github.com/ericsssan/zbc) — infers Zig lifetime, ownership, and cleanup bugs with no annotations.
- [ez-checker](https://github.com/ericsssan/ez-checker) — TypeScript type checker; full inference and control-flow narrowing.

**Cryptography & networking**
- [zquic](https://github.com/ericsssan/zquic) — Sans-I/O QUIC library (RFC 9000/9001/9002), TLS 1.3 handshake, 0-RTT, zero dependencies.
- [zhttp3](https://github.com/ericsssan/zhttp3) — HTTP/3 framing, QPACK header compression, and a server layer built on zquic.

**Performance**
- [ic-fuzzer](https://github.com/ericsssan/ic-fuzzer) — diagnoses and fixes V8 JIT megamorphic deoptimizations in Node/TypeScript.
- [es-parser](https://github.com/ericsssan/es-parser) — JS/TS/JSX parser; SIMD lexer, struct-of-arrays AST; 3,966/3,966 test262.

## 🎓 Education

- **B.Eng. Computer Engineering** — National University of Singapore
- **Diploma in Electrical & Electronics Engineering** — Singapore Polytechnic

---

*Open to new roles — security-focused full-stack, secure systems, or performance engineering.*
