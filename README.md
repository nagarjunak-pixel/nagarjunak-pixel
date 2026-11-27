# Nagarjuna Reddy Kamireddy

*(Published across resumes, LinkedIn & GitHub as **Nagarjuna Kamireddy** · **Nagarjuna K**)*

**Lead AI Architect | AI Solutions Architect | GenAI Lead — Agentic AI & RAG · Available Immediately**  
*22 years in enterprise data and AI: a decade of production ML and GenAI (John Deere, Persistent Systems, Vertiv), built on a decade embedded at client sites as an SAP BW / BPC / HANA consultant across India, Malaysia, Singapore, the UK, and the US.*

- **Email:** `writetonagarjuna@gmail.com`
- **LinkedIn:** [linkedin.com/in/nagarjuna-kamireddy](https://www.linkedin.com/in/nagarjuna-kamireddy/)
- **GitHub:** [github.com/nagarjunak-pixel](https://github.com/nagarjunak-pixel)
- **Portfolio & Case Studies:** [nagarjunak-pixel.github.io](https://nagarjunak-pixel.github.io/) · [Executive Resume](https://nagarjunak-pixel.github.io/resume.html) · [Open-Source Systems](https://nagarjunak-pixel.github.io/projects.html) · [Field Guides & Monographs](https://nagarjunak-pixel.github.io/handbooks.html)

---

### Selected Open-Source Systems (`10/10` CV Selected Projects + Systems Suite)

| Repository | Architecture & Engineering Scope | Verification & Runtime Stack |
|---|---|---|
| **[`enterprise-erp-odata-mcp-server`](https://github.com/nagarjunak-pixel/enterprise-erp-odata-mcp-server)** | MCP server enabling AI agents to query ERP systems over OData v4 APIs (`MM/SD/FI/MM-IM`) with EDM schema validation, `$filter` sanitization, row-level `BUKRS` authorization, PII masking, and tool-calling guardrails. | Python 3.13 · C++20 · FastAPI · MCP · React 18 (`98.05%` branch cov, `Apache-2.0`) |
| **[`enterprise-helpdesk-rag-guardrails`](https://github.com/nagarjunak-pixel/enterprise-helpdesk-rag-guardrails)** | RAG help-desk assistant combining RBAC filtering, hybrid BM25 + dense retrieval, similarity thresholds, code-enforced refusal when retrieval confidence is low, PII redaction, and automated acceptance tests. | Python 3.13 · C++20 · FastAPI · MCP · React 18 (`25/25` acceptance suite, `Apache-2.0`) |
| **[`aegis-runtime`](https://github.com/nagarjunak-pixel/aegis-runtime)** | Policy and audit layer for AI-agent tool calls with a deny-by-default capability DSL, segregation-of-duties checks, saga rollback, compaction attribution, and an Ed25519 signed tamper-evident audit log. | Python · FastAPI · Ed25519 Merkle Ledger · Pytest CI (`96.74%` cov, `Apache-2.0`) |
| **[`prism-gate`](https://github.com/nagarjunak-pixel/prism-gate)** | OpenAI-compatible multi-tenant LLM gateway implementing TCP-Vegas adaptive concurrency, per-tenant rate limits, cost-aware model cascade, and PSI/JSD prompt-drift detection. | Python · FastAPI · Asyncio · Pytest CI (`Apache-2.0`) |
| **[`vecta`](https://github.com/nagarjunak-pixel/vecta)** | From-scratch vector search engine implementing filtered HNSW with tombstone compaction, IVF-PQ asymmetric distance computation, 1-bit RaBitQ quantization, and hybrid BM25 + dense retrieval (`0.999` recall@10). | Python · C++20 SIMD Kernels · Hypothesis Parity (`Apache-2.0`) |
| **[`syntara`](https://github.com/nagarjunak-pixel/syntara)** | Grammar-constrained decoding engine compiling JSON Schema and regular expressions into minimal byte DFAs and token vocabulary masks so LLM output is valid by construction (`20/20` schema-valid). | Python · C++20 · Hypothesis Parity (`Apache-2.0`) |
| **[`company-os`](https://github.com/nagarjunak-pixel/company-os)** | Config-driven multi-agent operations runtime where 7 executive AI agents plan, assign, and track a company's work from one config file — Kanban board, live logs, and KPI engine. | Python · REST API · Pytest Suite (`Apache-2.0`) |
| **[`adaptive-ai-tutor`](https://github.com/nagarjunak-pixel/adaptive-ai-tutor)** | Agentic learning platform coordinating 12 GPT-4o agents across prerequisite DAG curriculum planning, Socratic tutoring, rubric assessment, Bayesian Knowledge Tracing, and SM-2 spaced repetition. | Next.js 14 · TypeScript · PostgreSQL · Prisma · Vitest (`97.88%` cov, `Apache-2.0`) |
| **[`llm-knowledge-base`](https://github.com/nagarjunak-pixel/llm-knowledge-base)** | Turns raw sources into an LLM-maintained Markdown wiki with incremental entity compilation, SQLite FTS5 full-text search, and citation-grounded Q&A. | Python · FastAPI · SQLite FTS5 · Pytest Suite |
| **[`langgraph-newsroom`](https://github.com/nagarjunak-pixel/langgraph-newsroom)** | Deterministic 3-stage news production pipeline with human-in-the-loop approval gates (`interrupt_before`), SQLite checkpoint persistence, citation/numeric grounding verification, and bounded error recovery. | Python · LangGraph · SQLite · FastAPI · Typer (`98.78%` cov, `Apache-2.0`) |
| **[`governed-member-services-agent`](https://github.com/nagarjunak-pixel/governed-member-services-agent)** | Multi-tenant regulated member-services agent with a deterministic tool gateway, policy enforcement, grounded citation checks, human escalation routing, and an offline evaluation gate. | Python · LangGraph · FastAPI · 40-Case Eval Harness (`Apache-2.0`) |
| **[`verispec-sdd`](https://github.com/nagarjunak-pixel/verispec-sdd)** | Executable `SPEC.md` state-machine compiler verifying reachability, deadlocks, and Tarjan SCC livelocks before code generation, paired with Hypothesis and Vitest property-test synthesis. | Python 3.13 · C++20 · FastAPI · MCP · React 18 (`98.01%` branch cov, `MIT`) |
| **[`skillbench`](https://github.com/nagarjunak-pixel/skillbench)** | Static information-flow taint analyzer and multi-pattern scanner inspecting agent `SKILL.md` archives, OOXML/ZIP attachments, `.pyc` constants, and `.mcp.json` tool definitions prior to execution. | Python 3.13 · C++20 Aho-Corasick · FastAPI · MCP (`97.97%` branch cov, `Apache-2.0`) |
| **[`weavegraph`](https://github.com/nagarjunak-pixel/weavegraph)** | Dependency-aware `git worktree` scheduler using Tarjan SCC condensation, min-cut multi-agent task partitioning, and 3-way AST semantic merge verification to prevent cross-branch contract breakage. | Python 3.13 · C++20 CSR Graph · FastAPI · MCP · React 18 (`MIT`) |
| **[`tracegit`](https://github.com/nagarjunak-pixel/tracegit)** | Content-addressed version control for agent execution traces built on a SQLite/SHA-256 Merkle DAG with C++20 sequence-alignment trace diffing, regression bisection, and loop detection. | Python · C++20 · SQLite · CLI & MCP (`Apache-2.0`) |
| **[`calibra`](https://github.com/nagarjunak-pixel/calibra)** | Statistical LLM evaluation library providing paired bootstrap and exact McNemar tests, Bradley-Terry leaderboards with confidence intervals, 2PL IRT anchor scoring, temperature scaling, and MinHash-LSH contamination checks. | Python · C++20 · `mypy --strict` (`99.6%` test cov, `Apache-2.0`) |
| **[`enterprise-ai-field-guides`](https://github.com/nagarjunak-pixel/enterprise-ai-field-guides)** | Open-access practitioner reference library containing 15 technical field guides and monographs across Production Hybrid/GraphRAG, SAP S/4HANA Clean-Core MCP, Agent Evaluation (`255` CI checks), Supply-Chain Security, AI Gateways, and Forward-Deployed Engineering. | PDF Reference Library · [Browse on Web](https://nagarjunak-pixel.github.io/handbooks.html) |

---

### Experience & Credentials (22 Years)

- **Canonical Name & Published Variants:** Nagarjuna Reddy Kamireddy (`Nagarjuna Kamireddy` · `Nagarjuna K`)
- **Total Experience:** **22 years** (`2004 – 2026`)
- **Chronological Employment History (`MM/YYYY – MM/YYYY`):**
  1. **John Deere** (Pune, India) — **AI Architect & Technical Lead (official title: Senior Data Scientist)** · **`01/2023 – 10/2026`** — Owned architecture, self-service AWS platform (Terraform, GitHub Actions), and delivery for a **12+ member team across 23+ AI initiatives** (**750K+ automated requests**, **42K+ hours saved** in FY26); built **StoneAge** engineering copilot, **6-agent Neo4j GraphRAG**, and **AIFlow** (`255` CI quality checks); sat on the **AI Governance Council** (NIST AI RMF / EU AI Act).
  2. **Persistent Systems** (Pune, India) — **Engineering Lead — Machine Learning** · **`01/2021 – 01/2023`** — Delivered client ML projects, MLOps, and secure database integrations across PIAM access recommendation, iDataCleanse identity deduplication, face recognition, VMS recommendation, VectorFlow POD, and Vertina NLP.
  3. **Vertiv** (Hyderabad, India) — **Data Scientist** · **`03/2020 – 01/2021`** — Production ML/DL models for compliance analytics and Customer 360 with AWS Athena query pushdown and Tableau dashboards.
  4. **Soham Global** (India) — **Software Engineer — Machine Learning** · **`03/2016 – 02/2020`** — Leakage-safe time-based forecasting, market-basket analysis, recommendation, and inventory tracking for finance and e-commerce clients.
  5. **GlaxoSmithKline (GSK)** (Brentford, United Kingdom) — **HANA Lead Consultant — Data Platform & Predictive Analytics** · **`02/2014 – 02/2016`** — In-database ML (PAL, APL, R) for forecasting and churn scoring; reduced MRP and financial consolidation batch runs from hours to minutes.
  6. **Earlier Enterprise Data & SAP Consulting (`2004 – 2014`):** **GSK India & HCL Axon UK** (`2012 – 2014`, HANA Consultant) · **PETRONAS Energy Trading & Deloitte, Kuala Lumpur** (`2011 – 2012`, HANA / BPC Architect — cut data load from `48 hours` to `12 minutes`) · **DHL, Symantec & Khaga, Malaysia · Singapore** (`2008 – 2011`, BPC / BusinessObjects Consultant) · **Lenovo, SEAL InfoTech & High Industries, Chennai · United States** (`2004 – 2008`, BW / BI Consultant).
- **Certifications:** **AWS Certified Solutions Architect – Professional (SAP-C02)** · **NVIDIA-Certified Professional: Agentic AI (NCP-AAI)**
- **Training:** Anthropic — Advanced Prompt Engineering, MCP (Advanced) · OpenAI — Agents & Workflows
- **Education:** **M.Sc. (Integrated) Applied Science, IT — Periyar University · `1999 – 2004` · First Class**

---

### Contact

- **Email:** `writetonagarjuna@gmail.com`
- **LinkedIn:** [https://www.linkedin.com/in/nagarjuna-kamireddy/](https://www.linkedin.com/in/nagarjuna-kamireddy/)
- **GitHub:** [https://github.com/nagarjunak-pixel](https://github.com/nagarjunak-pixel)
- **Canonical Website:** [https://nagarjunak-pixel.github.io/](https://nagarjunak-pixel.github.io/)
