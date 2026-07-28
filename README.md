# Hi, I'm Mayan Pathak
Software Engineer — CS 2026 grad focused on Rust backend systems, distributed infrastructure, Solana development, and AI tooling. Also a seasoned MERN stack developer.

---

## All Projects

### Rust
- [memolite](https://github.com/mayanpathak/memolite) — Local, embedded memory engine for AI agents: SQLite-backed durable storage with transactional memory+embedding writes, an in-process vector index (cosine similarity) rebuilt from SQLite on every restart, confidence-weighted ranking (similarity × importance × recency × reinforcement), non-destructive updates via `superseded_by`, bounded streaming ingestion, and background compression/maintenance
- [crypto-exchange](https://github.com/mayanpathak/crypto-exchange) — Multi-crate workspace: Axum REST API, in-memory price-time priority matching engine, Warp WebSocket server, Diesel/PostgreSQL persistence, Redis pub/sub message bus with per-request correlation channels
- [Promptoanime](https://github.com/mayanpathak/Prompttoanimation) — Async distributed rendering backend: Axum API server + Tokio worker binary, Redis LPUSH/BRPOP job queue, Gemini API code generation, Docker-sandboxed Manim rendering, MongoDB job state machine
- [VecLite](https://github.com/mayanpathak/veclite) — Self-hosted, single-node vector database server built from scratch: custom IVF-style indexing with K-means clustering, gRPC API via tonic/prost, RwLock-based concurrent storage and index, atomic snapshot persistence, black-box end-to-end test suite
- [WarpBench](https://github.com/mayanpathak/WrapBench) — Distributed async HTTP load-testing CLI: zero-copy lifetime-annotated YAML parsing, thousands of concurrent virtual users via Tokio, lock-free Arc/Atomic metrics, mpsc aggregator, broadcast shutdown, spawn_blocking percentile reports
- [Live Attendance System](https://github.com/mayanpathak/WebSocket-Based-Live-Attendance-System) — Real-time attendance tracking backend: Axum + WebSockets, JWT auth with custom FromRequestParts extractor, tokio::sync::Mutex shared session state, mpsc-per-client broadcast pattern, MongoDB persistence

### MERN / Full Stack
- [Sellify](https://github.com/mayanpathak/sellify) — Shopify for digital products: no-code checkout page builder, Stripe integration, Redis queues, webhook automations, Zapier and Google Sheets connectors
- [CodeCollab](https://github.com/mayanpathak/newcodecollab) — Real-time collaborative code editor: multi-user live editing, AI code help, syntax highlighting
- AI Website Builder — Generates complete websites from natural language prompts; live code editing, zip export for deployment
- Anime Recommender — AI-powered mood-based anime recommendation engine with adaptive personalisation

---

## Featured Projects

| Project | What it does | Tech | Link |
|---|---|---|---|
| **memolite** | Local memory engine for AI agents — durable SQLite storage, in-process vector recall, confidence/ranking model, non-destructive updates, streaming ingestion, and background compression | Rust, SQLite, Tokio, fastembed (ONNX) | [Repository](https://github.com/mayanpathak/memolite) |
| **crypto-exchange** | Production-grade event-driven cryptocurrency exchange — matching engine, Redis message bus, WebSocket feeds, async PostgreSQL persistence | Rust, Axum, Redis, Diesel, PostgreSQL, Warp | [Repository](https://github.com/mayanpathak/crypto-exchange) |
| **Promptoanime** | Distributed prompt-to-animation platform — natural language → Manim video via AI code generation, Docker sandboxing, and async job queue | Rust, Axum, Tokio, Redis, MongoDB, Gemini API, Docker | [Repository](https://github.com/mayanpathak/Prompttoanimation) |
| **VecLite** | From-scratch vector database server — custom IVF-style indexing, K-means clustering, gRPC API, atomic snapshot persistence | Rust, tonic, gRPC, Protocol Buffers, Tokio | [Repository](https://github.com/mayanpathak/veclite) |
| **Sellify** | No-code checkout page SaaS — Stripe-branded checkout builder, webhook automations, Redis queues, Zapier and Google Sheets integrations | Next.js, Node.js, Redis, Stripe | [Repository](https://github.com/mayanpathak/sellify) |
| **CodeCollab** | Real-time collaborative code editor with multi-user editing, AI code assistance, and syntax highlighting | React, Node.js, WebSockets | [Repository](https://github.com/mayanpathak/newcodecollab) |

---

## Tech Stack
**Rust** · Axum · Tokio · Diesel · Warp · Redis · PostgreSQL · MongoDB · Docker · tonic / gRPC  
**TypeScript / JavaScript** · React · Next.js · Node.js · Express  
**Other** · JWT · WebSockets · Stripe · Gemini API · Solana

---

## Contact
- **GitHub** — [github.com/mayanpathak](https://github.com/mayanpathak)
- **Email** — pathakmayan339@gmail.com
