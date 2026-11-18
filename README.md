# Nagarjuna Reddy Kamireddy 👋
*(Published on LinkedIn & GitHub as **Nagarjuna Kamireddy** · **Nagarjuna K** · **Nagarjun Reddy Kamireddi**)*

**Lead AI Architect &nbsp;|&nbsp; Production Agentic AI, Hybrid RAG & LLM Evals (750K+ Workflows/Yr) &nbsp;|&nbsp; Ex-John Deere, GSK, Deloitte &nbsp;|&nbsp; AWS SA Pro & NVIDIA Agentic AI Certified**

- 🔗 **Official LinkedIn Profile:** **[https://www.linkedin.com/in/nagarjuna-kamireddy/](https://www.linkedin.com/in/nagarjuna-kamireddy/)** *(UAE: [ae.linkedin.com/in/nagarjuna-kamireddy](https://ae.linkedin.com/in/nagarjuna-kamireddy))*
- 📰 **Daily LinkedIn Newsletter:** **[Autonomous SAP & Enterprise AI](https://www.linkedin.com/newsletters/autonomous-sap-enterprise-ai-7528104436112441348/)** *(SAP S/4HANA, SAP-RPT-1, Joule Studio, Clean Core BTP & Agentic AI)*
- 🌐 **Canonical Architecture Hub (72+ Live Pages):** **[https://nagarjunak-pixel.github.io/](https://nagarjunak-pixel.github.io/)** · [LinkedIn Open-Web Hub](https://nagarjunak-pixel.github.io/linkedin-profile.html) · [Complete 50-Repo GitHub Atlas](https://nagarjunak-pixel.github.io/github-projects-atlas.html)
- 🤖 **LLM Grounding & SFT Dataset:** [`llms.txt`](https://nagarjunak-pixel.github.io/llms.txt) · [`llms-full.txt`](https://nagarjunak-pixel.github.io/llms-full.txt) · [68-Q&A Knowledge Base](https://nagarjunak-pixel.github.io/ai-architect-faq.html) · [`llm-training-dataset.jsonl`](https://nagarjunak-pixel.github.io/llm-training-dataset.jsonl)
- 📄 **Executive Resumes (PDF):** [Global AI Architect CV](https://nagarjunak-pixel.github.io/assets/cv/Nagarjuna-Reddy-Kamireddy-CV-Global.pdf) · [UAE / KSA / Gulf CV](https://nagarjunak-pixel.github.io/assets/cv/Nagarjuna-Reddy-Kamireddy-CV-Gulf-UAE.pdf) · [Corporate AI Trainer CV](https://nagarjunak-pixel.github.io/assets/cv/Nagarjuna-Reddy-Kamireddy-CV-Corporate-AI-Trainer.pdf)

---

### Flagship Projects
1. **[helios-consensus](https://github.com/nagarjunak-pixel/helios-consensus)** — Library-style Raft consensus in Python (`~7.2K` LOC Python + `705` LOC C++20 + `~1.8K` LOC tests): `PreVote`, `CheckQuorum`, chunked snapshots, Ongaro §6 Joint Consensus (`C_{old,new}`), `ReadIndex`, crash-safe segmented binary WAL, `asyncio` TCP server/client & Multi-Raft range splits. Verified across `20/20` Jepsen fault-injection seeds (`8,639` ops, Wing–Gong–Lowe linearizability) and `7/7` protocol/WAL mutant kills.
2. **[tokendiet](https://github.com/nagarjunak-pixel/tokendiet)** — Context compressor for AI coding agents: order-preserving knapsack pruning of tool logs (C++20 kernel + Python fallback), Python AST skeletons, cross-turn read dedup; CLI + MCP server. On 6 self-built tasks with a local `qwen3.5:4b`: `6,487 → 1,930` prompt tokens (`70.25%` fewer), required answer content kept in `6/6`.
3. **[slopguard](https://github.com/nagarjunak-pixel/slopguard)** — Rule-based checker for common AI-generated-code mistakes (stub bodies, unresolved imports, swallowed exceptions, tautological tests, dead UI handlers): Python AST + regex TS/JSX rules, C++20 prescreen, Claude Code `PostToolUse` hook & MCP server. `~0.03–0.28 ms` per small file in the demo; 6-task local repair audit `0/6 → 6/6` passing its own rules.

---

### Executive Impact (22+ Years Global Enterprise Data, SAP HANA & Production AI)
- **John Deere (AI Architecture & Technical Lead, 2023–2026):** Led a **12+ member AI/ML team across 23+ production initiatives** — **750K+ automated requests & 42K+ hours saved (~25% faster cycle time) in FY26**. Built **StoneAge** (LangGraph + OpenSearch hybrid RAG + Neo4j copilot routing across GPT-5/Claude/GPT-4o/Gemini), rescued a failing **~30%-accurate GenAI product to ~70% accuracy** via GPT-4o Vision + rule gates, built **AIFlow** (255 CI quality checks), and served on the **AI Governance Council** (NIST AI RMF / EU AI Act).
- **Persistent Systems, Vertiv & Soham Global (2016–2023):** Production ML, MLOps, AWS Athena lakehouse pushdown, computer vision, NLP, and leakage-safe forecasting.
- **Global SAP HANA / BW / BPC Consulting (2004–2016 — UK, Malaysia, Singapore, US, India):** **GlaxoSmithKline (GSK UK)** in-database HANA PAL/APL/R ML; **PETRONAS Energy Trading & Deloitte** (`48 hours → 12 minutes` HANA speedup); **DHL, Symantec & Lenovo**; **4× SAP Certified** + Founder of **Surya HANA Academy (~1,000 trained)** & **Suryagentic Institute (280+ live AI sessions in 2026)**.

---

### LinkedIn Pulse Monographs & 15 Architecture Deep-Dives & 2 Scholarly Whitepapers
- **[The 4 SAP MCP Layers Every BTP & Enterprise AI Architect Must Know in 2026 (LinkedIn Pulse)](https://www.linkedin.com/pulse/4-sap-mcp-layers-every-btp-enterprise-ai-architect-must-kamireddy-llh1f)**
- **[Meet SAP-RPT-1: Why SAP Built a Table-Native Foundation Model Instead of Text LLMs (LinkedIn Pulse)](https://www.linkedin.com/pulse/meet-sap-rpt-1-why-sap-built-table-native-foundation-model-kamireddy-tdulf)**
- **[Masterbook Ch. 01 of 50: Claude Code & The 5-Land Enterprise AI Architecture (LinkedIn Pulse)](https://www.linkedin.com/pulse/nagarjun-reddy-kamireddi-masterbook-chapter-01-50-claude-kamireddy-skfpe)**
- **[All 14 Deep Systems & Enterprise AI Articles on nagarjunak-pixel.github.io →](https://nagarjunak-pixel.github.io/articles.html)**

---

### Systems & ML Reference Implementations (Python with small `C++20` helpers)
1. **[weavegraph](https://github.com/nagarjunak-pixel/weavegraph)** — Code-graph scheduler for parallel agent worktrees: C++20 CSR graph, Tarjan SCC, min-cut task partitioning & 3-way AST merge check + MCP.
2. **[vecta](https://github.com/nagarjunak-pixel/vecta)** — Vector search engine: HNSW (`0.999` recall, tombstones), IVF-PQ, RaBitQ-style 1-bit codes & hybrid BM25+RRF, with C++20 kernels.
3. **[slopguard](https://github.com/nagarjunak-pixel/slopguard)** — Heuristic checker for AI-generated code: Python AST + regex TS/JSX rules, C++20 prescreen, Claude Code `PostToolUse` hook & MCP server.
4. **[tokendiet](https://github.com/nagarjunak-pixel/tokendiet)** — Context compressor for coding agents: order-preserving knapsack log pruning (`70.25%` fewer prompt tokens on 6 self-built tasks, `6/6` answers kept), AST skeletons & cross-turn dedup.
5. **[syntara](https://github.com/nagarjunak-pixel/syntara)** — Grammar-constrained structured decoding: JSON Schema/regex → minimal byte DFA (`141.7x` C++20 prefix-sharing index, `20/20` schema-valid) & byte-level Earley CFG.
6. **[tracegit](https://github.com/nagarjunak-pixel/tracegit)** — Git-like local history for AI agent traces: SQLite/SHA-256 Merkle store, C++20 edit-distance diff/bisect, loop detection, CI gate & MCP server (prototype).
7. **[aether-compiler](https://github.com/nagarjunak-pixel/aether-compiler)** — Educational tensor-graph compiler: SSA IR with CSE/fusion/DCE passes, C++20 static arena planner (`432 → 120 MiB`, `3.60x` on a 2-layer example) & analytic H100 tile cost model.
8. **[nexus-verity](https://github.com/nagarjunak-pixel/nexus-verity)** — Educational causal-inference toolkit: PC discovery (`SHD=0` on a synthetic DAG), cross-fitted double ML (`919x` smaller bias than the naive estimate on synthetic data), split conformal & C++ doubly-robust OPE.
9. **[helios-consensus](https://github.com/nagarjunak-pixel/helios-consensus)** — Library-style Raft (`PreVote`, Joint Consensus, `ReadIndex`), segmented binary `CRC32C` WAL, `asyncio` TCP + Multi-Raft sharding, Jepsen fault-injection harness & C++20 Wing–Gong–Lowe linearizability solver (`20/20` seeds safe, `7/7` mutants killed).
10. **[privora-graph](https://github.com/nagarjunak-pixel/privora-graph)** — Privacy & robustness reference implementation: DP-SGD with RDP accounting, bi-temporal PageRank retrieval, Multi-Krum/geometric-median aggregation.
11. **[quant-forge](https://github.com/nagarjunak-pixel/quant-forge)** — LLM weight-quantization reference implementation: GPTQ, AWQ, Walsh-Hadamard rotation, simulated FP8 & a small C++20 packed-INT4 GEMM.
12. **[veritas-rl](https://github.com/nagarjunak-pixel/veritas-rl)** — RL post-training sandbox: GRPO/DAPO on toy math tasks (`6.25% → 50.00%` Pass@1), DoRA vs LoRA on a `128×128` toy (`563x` lower MSE), single-process ring-attention/TP simulation & step-level PRM reranking.
13. **[axiom-zero](https://github.com/nagarjunak-pixel/axiom-zero)** — Educational small GQA transformer: speculative decoding with a C++ helper (`4.00x` fewer target passes), Top-K SAE steering (`R²=0.9855`) & CDCL SAT solver with RUP checks.
14. **[aegis-runtime](https://github.com/nagarjunak-pixel/aegis-runtime)** — Policy and audit layer for AI-agent tool calls: custom policy DSL, taint tracking, PII vault, saga compensation & hash-chained Merkle/Ed25519 audit log.
15. **[prism-gate](https://github.com/nagarjunak-pixel/prism-gate)** — OpenAI-compatible LLM gateway prototype (`~4,660 req/s` gateway overhead against simulated upstreams): TCP-Vegas adaptive concurrency, heuristic cascade routing & PSI/JSD drift checks.
16. **[chronos-mesh](https://github.com/nagarjunak-pixel/chronos-mesh)** — Educational supply-chain rerouting model: pure-Python simplex + branch-and-bound MILP, BOM safety stock & Monte Carlo `CVaR95`.

---

### Complete Public Repository Index ([Interactive Atlas →](https://nagarjunak-pixel.github.io/github-projects-atlas.html))

| Repository | Stack | Architectural Scope |
|---|---|---|
| [`nagarjunak-pixel`](https://github.com/nagarjunak-pixel/nagarjunak-pixel) | Multi-Lang | Nagarjuna Reddy Kamireddy (Nagarjuna Kamireddy / Nagarjuna K) — Lead AI Architect, Agentic AI, GraphRAG, LLM Evaluation & SAP HANA |
| [`nagarjunak-pixel.github.io`](https://github.com/nagarjunak-pixel/nagarjunak-pixel.github.io) | HTML | Nagarjuna Reddy Kamireddy (Nagarjuna Kamireddy / Nagarjuna K) — Official Lead AI Architect, Agentic AI & SAP Portfolio, Case Studies & llms.txt Hub |
| [`weavegraph`](https://github.com/nagarjunak-pixel/weavegraph) | Python | Code-graph worktree scheduler, min-cut multi-agent task partitioner & 3-way AST merge check (C++20 + Python + MCP + React) |
| **[calibra](https://github.com/nagarjunak-pixel/calibra)** ([v1.0.0](https://github.com/nagarjunak-pixel/calibra/releases/tag/v1.0.0)) | `C++20` · Python · `mypy --strict` (`0` errors) · `99.6%` coverage (`>100` tests) | Rigorous eval: bootstrap/McNemar tests, Bradley–Terry leaderboards, 2PL IRT anchor benchmarking, ECE temperature scaling, and MinHash-LSH contamination detection. Bit-exact C++20 kernels. | — |
| [`vecta`](https://github.com/nagarjunak-pixel/vecta) | Python | Vector search engine: HNSW (heuristic neighbour selection, filtered & tombstone search) at 0.999 recall@10 touching 1.4% of vectors, IVF-PQ ADC + rerank (24x compression), RaBitQ-style 1-bit codes, BM25+RRF hybrid & bit-exact native C++20 kernels |
| [`slopguard`](https://github.com/nagarjunak-pixel/slopguard) | Python | Heuristic checker for AI-generated code — Python AST + regex TS/JSX rules for stubs, unresolved imports, empty tests; C++20 prescreen, Claude Code hook, MCP |
| [`tokendiet`](https://github.com/nagarjunak-pixel/tokendiet) | Python | Context compressor for AI coding agents — knapsack log pruning (C++20 kernel, Python fallback), AST skeletons, cross-turn read dedup. CLI + MCP server |
| [`nrk-enterprise-ai-masterbook`](https://github.com/nagarjunak-pixel/nrk-enterprise-ai-masterbook) | Multi-Lang | Nagarjuna Reddy Kamireddy™ — The 7,200-Page Enterprise AI, Claude Code & SAP RAG Masterbook Series (50 Daily Chapters) |
| [`syntara`](https://github.com/nagarjunak-pixel/syntara) | Python | Grammar-constrained structured decoding: JSON Schema/regex -> minimal byte DFA (Thompson/Rabin-Scott/Moore), C++20 prefix-sharing token index (112-142x, bit-exact vs Python), byte-level Earley CFG constraints & closed-set choice scoring |
| [`tracegit`](https://github.com/nagarjunak-pixel/tracegit) | Python | Git-like local history for AI agent traces — SQLite/SHA-256 Merkle store, C++20 edit-distance diff/bisect, loop detection, CI gate, MCP server. Prototype |
| [`nexus-verity`](https://github.com/nagarjunak-pixel/nexus-verity) | Python | Causal inference in Python — PC discovery, d-separation, cross-fitted double ML, split conformal, C++ doubly-robust OPE. Educational reference implementation |
| [`aether-compiler`](https://github.com/nagarjunak-pixel/aether-compiler) | Python | Small tensor-graph compiler: SSA IR with CSE/fusion/DCE passes, C++20 static arena planner, analytic H100 tile cost model. Educational reference implementation |
| [`privora-graph`](https://github.com/nagarjunak-pixel/privora-graph) | Python | Privacy & robustness toolkit — DP-SGD with RDP accounting, bi-temporal PageRank retrieval, Multi-Krum/geometric-median aggregation. Reference implementation |
| [`helios-consensus`](https://github.com/nagarjunak-pixel/helios-consensus) | Python | Library-style Raft consensus with segmented binary WAL, asyncio TCP, Multi-Raft range splits, Jepsen fault injection, Wing–Gong–Lowe linearizability & C++20 kernels |
| [`venkatesh-llm`](https://github.com/nagarjunak-pixel/venkatesh-llm) | HTML | Micro-LLM From Scratch (1.03M Parameters) — End-to-end BPE tokenizer, causal Transformer pretraining, checkpointing & Ollama Q&A engineering lab. |
| [`surya-agentic-academy-digest`](https://github.com/nagarjunak-pixel/surya-agentic-academy-digest) | HTML | Automated Agentic AI Research & Engineering Digest — Daily LLM paper & technical talk synthesis into 5 runnable project blueprints per edition. |
| [`langgraph-localai-tv`](https://github.com/nagarjunak-pixel/langgraph-localai-tv) | Python | LangGraph 3-stage news pipeline: headlines → video → bulletin. Human approval gates, checkpoint persistence, error recovery. |
| [`self-improving-agents`](https://github.com/nagarjunak-pixel/self-improving-agents) | Python | 🧠 Self-Improving Multi-Agent System — A teaching framework for advanced agentic AI: ReAct loop, Reflexion, multi-agent orchestration, adversarial reasoning, and agent-as-a-judge. With web UI + Netlify deployment. |
| [`operdai-dashboard`](https://github.com/nagarjunak-pixel/operdai-dashboard) | JavaScript | Enterprise Multi-Tenant White-Label AI Lead-Agent Analytics Console — React + TypeScript telemetry, conversion funnels & partner branding portal. |
| [`loop-engineering-trading`](https://github.com/nagarjunak-pixel/loop-engineering-trading) | JavaScript | Browser 'Minara' quant desk: research, strategy, execution, and review loops with backtesting and paper trading. |
| [`llm-knowledge-base`](https://github.com/nagarjunak-pixel/llm-knowledge-base) | Python | LLM knowledge base: ingest sources, compile a markdown wiki, search, and ask questions (FastAPI + SQLite). |
| [`firecrawl-nexus-rss`](https://github.com/nagarjunak-pixel/firecrawl-nexus-rss) | Python | Firecrawl-powered news aggregator: scrapes AP/TG constituency news into clean markdown and structured JSON. |
| [`deerflow-research-agent`](https://github.com/nagarjunak-pixel/deerflow-research-agent) | Python | DeerFlow-inspired research agent with sub-agents (Planner, Searcher, Analyzer), persistent memory, and session resume. |
| [`crewai-telugu-newsroom`](https://github.com/nagarjunak-pixel/crewai-telugu-newsroom) | Python | CrewAI multi-agent Telugu newsroom: Researcher → Script Writer → Fact-Checker. Sequential pipeline for automated news production. |
| [`codexforge-tdd-mvp-v2`](https://github.com/nagarjunak-pixel/codexforge-tdd-mvp-v2) | Python | Self-correcting TDD sandbox: RED→GREEN loop with Docker isolation, VS Code extension, and LLM-powered code repair |
| [`apsrtc-statistics-dashboard`](https://github.com/nagarjunak-pixel/apsrtc-statistics-dashboard) | JavaScript | React dashboard for APSRTC operations: fleet, tickets, financials, route heatmap, EV tracker, and a what-if simulator. |
| [`agentic-ai-dashboard`](https://github.com/nagarjunak-pixel/agentic-ai-dashboard) | JavaScript | Interactive Visual Guide to Agentic AI Architecture — Tokenizer Inspector, RAG Playground, ReAct Loop, Reflexion & LLM Evaluation Suite. |
| [`agentic-academy`](https://github.com/nagarjunak-pixel/agentic-academy) | Python | Python teaching framework for agentic engineering: agents, a harness, loops, memory, and a local-model demo. |
| [`agentforge`](https://github.com/nagarjunak-pixel/agentforge) | JavaScript | AgentForge — Interactive React Workbench for Designing, Simulating & Debugging Multi-Agent Graphs, Eval Sandboxes & Swarm Telemetry. |
| [`agent-framework-lab`](https://github.com/nagarjunak-pixel/agent-framework-lab) | Python | Hands-on Microsoft Agent Framework 1.0 lab — multi-agent workflows on local Ollama (no API keys) |
| [`pytorch-interactive-demo`](https://github.com/nagarjunak-pixel/pytorch-interactive-demo) | JavaScript | Interactive PyTorch Deep-Learning Visualizer — Vector Embeddings, Cosine RAG Retrieval & Autograd Training Loop Dynamics. |
| [`attention-head-walkthrough`](https://github.com/nagarjunak-pixel/attention-head-walkthrough) | HTML | Interactive Step-by-Step Transformer Self-Attention Head Simulation (Q/K/V Projections, Causal Masking & Softmax Attention Weights). |
| [`ai-calc`](https://github.com/nagarjunak-pixel/ai-calc) | JavaScript | Qwen AI Calculator — plain-English math in the browser, solved locally with Ollama. |
| [`company-os`](https://github.com/nagarjunak-pixel/company-os) | Python | CompanyOS — config-driven team of AI agents for simulated company workflows (company.json, 7 role-agents, SIM + LIVE modes, kanban dashboard, KPI engine). |
| [`rag-chat-docs`](https://github.com/nagarjunak-pixel/rag-chat-docs) | Python | RAG Chat with Documents — 7-Module From-Scratch Retrieval-Augmented Generation System (Chunking, Hybrid Search, CLI & FastAPI Web UI). |
| [`spring-boot-mcp`](https://github.com/nagarjunak-pixel/spring-boot-mcp) | TypeScript | MCP server that lets an LLM inspect a Java Spring Boot app via Actuator, REST APIs, and logs. |
| [`localaitv-mcp-server`](https://github.com/nagarjunak-pixel/localaitv-mcp-server) | Python | Python MCP server for LocalAI TV admin access to Postgres, AWS (ECS, S3, SQS, CloudWatch), and the public API. |
| [`antigravity-sdk`](https://github.com/nagarjunak-pixel/antigravity-sdk) | Python | Example agents for Google's Antigravity SDK: chat, custom tools, MCP, streaming, multimodal, and hooks. |
| [`ai-workforce`](https://github.com/nagarjunak-pixel/ai-workforce) | Python | Local multi-agent workforce with a FastAPI dashboard: CEO → research → architect → coding → QA → docs → deploy → marketing, on Ollama. |
| [`smart-marketing-assistant`](https://github.com/nagarjunak-pixel/smart-marketing-assistant) | Python | CrewAI + LangChain marketing crew on local Ollama that drafts a content strategy, plus a daemon that can post AI news to X. |
| [`agentic-systems-v3.1`](https://github.com/nagarjunak-pixel/agentic-systems-v3.1) | Python | Enterprise Agentic Systems v3.1 — consolidated monorepo (Phases 0-7) |
| [`surya-shiksha`](https://github.com/nagarjunak-pixel/surya-shiksha) | TypeScript | Surya Shiksha — Multi-Agent Adaptive Learning Operating System (12 Specialized AI Agents, Next.js, TypeScript, PostgreSQL & Prisma). |
| [`quant-forge`](https://github.com/nagarjunak-pixel/quant-forge) | Python | LLM weight-quantization reference implementation — GPTQ, AWQ, Walsh-Hadamard rotation, simulated FP8, and a small C++20 packed-INT4 GEMM. Educational. |
| [`veritas-rl`](https://github.com/nagarjunak-pixel/veritas-rl) | Python | RL post-training sandbox — GRPO/DAPO on toy math tasks, DoRA, single-process ring-attention/TP simulation, step-level PRM reranking. Reference implementation |
| [`axiom-zero`](https://github.com/nagarjunak-pixel/axiom-zero) | Python | Small GQA transformer with speculative decoding (C++ helper), Top-K SAE steering, and a CDCL SAT solver with RUP checks — educational reference implementation |
| [`chronos-mesh`](https://github.com/nagarjunak-pixel/chronos-mesh) | Python | Supply-chain rerouting toy model — pure-Python simplex + branch-and-bound MILP, BOM safety stock, Monte Carlo CVaR95. Educational reference implementation |
| [`prism-gate`](https://github.com/nagarjunak-pixel/prism-gate) | Python | OpenAI-compatible LLM gateway prototype — TCP-Vegas adaptive concurrency, heuristic cascade routing, PSI/JSD drift checks. Reference implementation |
| [`aegis-runtime`](https://github.com/nagarjunak-pixel/aegis-runtime) | Python | Policy and audit layer for AI-agent tool calls — custom policy DSL, saga compensation, hash-chained Merkle/Ed25519 audit log. Reference implementation |
| [`02-autogpt-autonomous-agent`](https://github.com/nagarjunak-pixel/02-autogpt-autonomous-agent) | Python | Forward-Deployed Engineering (FDE) Autonomous Agent Lab — Zero-dependency ReAct think-act-observe execution loop & enterprise FDE curriculum. |
| [`nagarjuna-kamireddy-ai-architect-dataset`](https://github.com/nagarjunak-pixel/nagarjuna-kamireddy-ai-architect-dataset) | JSONL | Open ChatML/SFT Fine-Tuning & RAG Grounding Dataset for Nagarjuna Reddy Kamireddy |

---

### Direct Contact
- **LinkedIn:** [https://www.linkedin.com/in/nagarjuna-kamireddy/](https://www.linkedin.com/in/nagarjuna-kamireddy/)
- **Portfolio:** [https://nagarjunak-pixel.github.io/](https://nagarjunak-pixel.github.io/)
- **Email:** `gmailtonagarjuna@gmail.com` · `writetonagarjuna@gmail.com` · `sendemailtonagarjuna@gmail.com`
- **Phone / WhatsApp:** `+971 50 742 4361` (Dubai, UAE) · `+91 93913 47406` (India)
