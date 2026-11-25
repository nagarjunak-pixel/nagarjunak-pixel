# Nagarjuna Reddy Kamireddy

*(Published on LinkedIn & GitHub as **Nagarjuna Kamireddy** · **Nagarjuna K** · **Nagarjun Reddy Kamireddi**)*

**Lead AI Architect | AI Solutions Architect | GenAI Lead — Agentic AI & RAG · Available Immediately**  
*22 years in enterprise data, SAP BW / BPC / HANA, and production AI/ML systems*

- **Email:** `writetonagarjuna@gmail.com`
- **LinkedIn:** [linkedin.com/in/nagarjuna-kamireddy](https://www.linkedin.com/in/nagarjuna-kamireddy/)
- **GitHub:** [github.com/nagarjunak-pixel](https://github.com/nagarjunak-pixel)
- **Portfolio & Case Studies:** [nagarjunak-pixel.github.io](https://nagarjunak-pixel.github.io/) · [Executive Resume](https://nagarjunak-pixel.github.io/resume.html) · [15 Flagship Systems](https://nagarjunak-pixel.github.io/projects.html) · [Field Guides & Monographs](https://nagarjunak-pixel.github.io/handbooks.html) · [`llms.txt`](https://nagarjunak-pixel.github.io/llms.txt)

---

### Selected Open-Source Systems (15 Flagship Repositories)

| Repository | Architecture & Engineering Scope | Verification & Runtime Stack |
|---|---|---|
| **[`enterprise-erp-odata-mcp-server`](https://github.com/nagarjunak-pixel/enterprise-erp-odata-mcp-server)** | SAP S/4HANA & OData v4 Clean-Core JSON-RPC 2.0 MCP server enforcing EDM schema allowlists (`MM/SD/FI/MM-IM`), `$filter` sanitization, row-level `BUKRS` authorization, IBAN/Tax-ID masking, human-approved write gates, and hash-chained audit logs. | Python 3.13 · C++20 · FastAPI · MCP · React 18 (`98.05%` branch cov, `Apache-2.0`) |
| **[`enterprise-helpdesk-rag-guardrails`](https://github.com/nagarjunak-pixel/enterprise-helpdesk-rag-guardrails)** | Enterprise help-desk hybrid retrieval and guardrail system combining RBAC document filtering, Okapi BM25 + dense cosine + RRF fusion, deterministic low-confidence abstention, PII redaction, and citation-overlap checks. | Python 3.13 · C++20 · FastAPI · MCP · React 18 (`25/25` acceptance suite, `Apache-2.0`) |
| **[`aegis-runtime`](https://github.com/nagarjunak-pixel/aegis-runtime)** | Deterministic policy and audit runtime for AI-agent tool execution with a custom capability DSL, segregation-of-duties checks, PII tokenization vault, compensating sagas, and an Ed25519 Merkle audit ledger. | Python · FastAPI · Ed25519 Merkle Ledger · Pytest CI (`Apache-2.0`) |
| **[`prism-gate`](https://github.com/nagarjunak-pixel/prism-gate)** | OpenAI-compatible multi-tenant LLM routing gateway implementing TCP-Vegas adaptive concurrency limits, per-tenant token budgets, latency/cost model cascades, and PSI/JSD prompt-drift detection. | Python · FastAPI · Asyncio · Pytest CI (`Apache-2.0`) |
| **[`vecta`](https://github.com/nagarjunak-pixel/vecta)** | Hybrid vector and lexical search engine implementing filtered HNSW with tombstone compaction, 24x IVF-PQ asymmetric distance computation, 1-bit RaBitQ quantization, and BM25+RRF fusion. | Python · C++20 SIMD Kernels · Hypothesis Parity (`0.999` Recall@10, `Apache-2.0`) |
| **[`syntara`](https://github.com/nagarjunak-pixel/syntara)** | Grammar-constrained structured decoding engine compiling JSON Schema and regular expressions into minimal byte DFAs with a prefix-sharing token vocabulary index and byte-level Earley CFG constraints. | Python · C++20 · Hypothesis Parity (`20/20` schema-valid decoding, `Apache-2.0`) |
| **[`governed-member-services-agent`](https://github.com/nagarjunak-pixel/governed-member-services-agent)** | Multi-tenant regulated member-services agent with a deterministic tool gateway, policy enforcement, grounded citation checks, human escalation routing, and an offline evaluation gate. | Python · LangGraph · FastAPI · 40-Case Eval Harness (`Apache-2.0`) |
| **[`calibra`](https://github.com/nagarjunak-pixel/calibra)** | Statistical LLM evaluation library providing paired bootstrap and exact McNemar tests, Bradley-Terry leaderboards with confidence intervals, 2PL IRT anchor scoring, temperature scaling, and MinHash-LSH contamination checks. | Python · C++20 · `mypy --strict` (`99.6%` test cov, `Apache-2.0`) |
| **[`verispec-sdd`](https://github.com/nagarjunak-pixel/verispec-sdd)** | Executable `SPEC.md` state-machine compiler verifying reachability, deadlocks, and Tarjan SCC livelocks before code generation, paired with Hypothesis and Vitest property-test synthesis. | Python 3.13 · C++20 · FastAPI · MCP · React 18 (`98.01%` branch cov, `MIT`) |
| **[`skillbench`](https://github.com/nagarjunak-pixel/skillbench)** | Static information-flow taint analyzer and multi-pattern scanner inspecting agent `SKILL.md` archives, OOXML/ZIP attachments, `.pyc` constants, and `.mcp.json` tool definitions prior to execution. | Python 3.13 · C++20 Aho-Corasick · FastAPI · MCP (`97.97%` branch cov, `Apache-2.0`) |
| **[`weavegraph`](https://github.com/nagarjunak-pixel/weavegraph)** | Dependency-aware `git worktree` scheduler using Tarjan SCC condensation, min-cut multi-agent task partitioning, and 3-way AST semantic merge verification to prevent cross-branch contract breakage. | Python 3.13 · C++20 CSR Graph · FastAPI · MCP · React 18 (`MIT`) |
| **[`tracegit`](https://github.com/nagarjunak-pixel/tracegit)** | Content-addressed version control for agent execution traces built on a SQLite/SHA-256 Merkle DAG with C++20 sequence-alignment trace diffing, regression bisection, and loop detection. | Python · C++20 · SQLite · CLI & MCP (`Apache-2.0`) |
| **[`company-os`](https://github.com/nagarjunak-pixel/company-os)** | Config-driven (`company.json`) multi-agent operations runtime coordinating 7 role-scoped agents across deterministic offline simulation and live OpenRouter modes with a Kanban board and KPI tracker. | Python · Flask · REST API · Pytest Suite |
| **[`llm-knowledge-base`](https://github.com/nagarjunak-pixel/llm-knowledge-base)** | Document ingestion, compiled Markdown wiki builder, lexical/semantic search, and cited Q&A workspace for engineering teams. | Python · FastAPI · SQLite · Pytest Suite |
| **[`enterprise-ai-field-guides`](https://github.com/nagarjunak-pixel/enterprise-ai-field-guides)** | Open-access practitioner reference library containing 13 technical field guides and monographs across Production Hybrid/GraphRAG, SAP S/4HANA Clean-Core MCP, Agent Evaluation (`255` CI checks), Supply-Chain Security, AI Gateways, and Forward-Deployed Engineering. | PDF Reference Library · [Browse on Web](https://nagarjunak-pixel.github.io/handbooks.html) |

---

### Enterprise Experience Summary (22 Years)

- **John Deere — AI Architect & Technical Lead (official title: Senior Data Scientist, `01/2023 – 10/2026`):** Owned architecture from discovery to production and led a **12+ member AI/ML engineering team across 23+ AI initiatives**, delivering **750K+ automated requests and 42K+ hours saved (`~25%` faster cycle time) in FY26**. Architected **StoneAge** (LangGraph + OpenSearch hybrid RAG + 6-agent Neo4j GraphRAG copilot routing across GPT-5, Claude, GPT-4o, and Gemini), improved a production GenAI workflow from **`~30%` to `~70%` accuracy** via multimodal validation gates, built **AIFlow** (`255` automated CI checks), and served on the **AI Governance Council** (NIST AI RMF / EU AI Act).
- **Persistent Systems, Vertiv & Soham Global (`2016 – 2022`):** Production machine learning, MLOps pipelines, AWS Athena lakehouse SQL pushdown, computer vision, NLP, and leakage-safe forecasting.
- **Enterprise SAP BW / BPC / HANA Consulting (`2004 – 2016` — India, Malaysia, Singapore, UK, US):** **GlaxoSmithKline (GSK UK)** in-database SAP HANA PAL/APL/R predictive pipelines; **PETRONAS Energy Trading & Deloitte** (`48 hours → 12 minutes` SAP HANA trading risk runtime reduction); **DHL, Symantec & Lenovo**; **4× SAP Certified**, **AWS Certified Solutions Architect – Professional**, **NVIDIA-Certified Professional: Agentic AI**, and Founder of **Surya HANA Academy (`~1,000` professionals trained)**.

---

### Technical Articles & Reference Guides

- [Enterprise AI Field Guides & Architecture Monographs (`handbooks.html`)](https://nagarjunak-pixel.github.io/handbooks.html)
- [Engineering Articles & Production Case Studies (`articles.html`)](https://nagarjunak-pixel.github.io/articles.html)
- [Autonomous SAP & Enterprise AI Newsletter (LinkedIn)](https://www.linkedin.com/newsletters/autonomous-sap-enterprise-ai-7528104436112441348/)

---

### Contact

- **Email:** `writetonagarjuna@gmail.com`
- **LinkedIn:** [https://www.linkedin.com/in/nagarjuna-kamireddy/](https://www.linkedin.com/in/nagarjuna-kamireddy/)
- **GitHub:** [https://github.com/nagarjunak-pixel](https://github.com/nagarjunak-pixel)
