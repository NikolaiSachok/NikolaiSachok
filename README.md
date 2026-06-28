# Hi, I'm Nikolai 👋

**AI engineer building and operating production LLM systems** — multi-agent orchestration, RAG, evaluation, and guardrails. Two decades of engineering and operations behind it: physicist by training, then founder, CEO and COO, now building AI systems hands-on.

I started out writing C++ simulations for CERN's LHC experiments, spent ~20 years building and leading software teams (500+ apps shipped, 10M+ downloads), and in 2025 rebuilt my delivery operation around AI. Today I run an LLM-orchestrated pipeline solo — design, code, and release — shipping about 20 production apps a week for roughly $6 each in model APIs. Most of the work is the verification and eval that keeps quality up at that volume.

### What I work on
- **Agentic systems** — multi-agent orchestration, task-conditioned model routing, agent memory & state, MCP tooling
- **RAG & retrieval** — hybrid (dense + BM25) retrieval, cross-encoder re-ranking, Qdrant / HNSW, eval-first design
- **Evaluation & guardrails** — LLM-as-judge, severity-tiered rubrics, prompt-injection & PII defenses
- **AI-assisted SDLC** — directing coding agents to a real engineering standard: tests, CI, reproducible builds

### Selected public work
- **[Strata-RAG](https://github.com/NikolaiSachok/Strata-RAG)** — an eval-first, study-grade RAG engine over heterogeneous, multi-format corpora. Qdrant + HNSW, hybrid retrieval with RRF, cross-encoder re-ranking, a metadata sidecar for aggregation queries, and an eval harness (Recall@K / nDCG / MRR + LLM-judge faithfulness) — plus a query router and an agentic chatbot that returns auditable tool-call trajectories.
- **[strata-insurance-corpus](https://github.com/NikolaiSachok/strata-insurance-corpus)** — a reproducible, synthetic, multi-format insurance document corpus (born-digital and scanned PDFs, Word, spreadsheets, photos) with a golden evaluation set by construction. Built to benchmark document-RAG on enterprise-shaped data.
- **[DC-plugins](https://github.com/NikolaiSachok/DC-plugins)** — native macOS plugins for Double Commander (Objective-C, universal binaries, headless tests, CI). A small native tool taken end-to-end to a published standard.

### How I build
I build heavily with AI agents — my work is the architecture, the evaluation, and the debugging, and directing agents to a production standard. The throughline: *verification, not generation, is the bottleneck.* Eval gates, layered automated review, and human attention on the decisions that carry risk — whether the artifact is an app, a retrieval pipeline, or a PR.

### Reach me
[LinkedIn](https://linkedin.com/in/nikolai-sachok/)
