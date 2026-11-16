# Nagarjuna Reddy Kamireddy 👋
*(Also published as **Nagarjuna Kamireddy** · **Nagarjuna K** · **Nagarjun Reddy Kamireddi**)*

**Lead AI Architect &nbsp;|&nbsp; AI Solutions Architect &nbsp;|&nbsp; GenAI Lead (Agentic AI & RAG) &nbsp;|&nbsp; Corporate AI Trainer**

🌐 **Official Portfolio & Architecture Hub:** **[https://nagarjunak-pixel.github.io/](https://nagarjunak-pixel.github.io/)**  
📄 **Downloadable Resumes (PDF):** [Global AI Architect CV](https://nagarjunak-pixel.github.io/assets/cv/Nagarjuna-Reddy-Kamireddy-CV-Global.pdf) · [Gulf / UAE / KSA CV](https://nagarjunak-pixel.github.io/assets/cv/Nagarjuna-Reddy-Kamireddy-CV-Gulf-UAE.pdf) · [Corporate AI Trainer CV](https://nagarjunak-pixel.github.io/assets/cv/Nagarjuna-Reddy-Kamireddy-CV-Corporate-AI-Trainer.pdf) · [Full Web CV](https://nagarjunak-pixel.github.io/resume.html)  
🤖 **Machine-Readable AI / Recruiter Index:** [`llms.txt`](https://nagarjunak-pixel.github.io/llms.txt) · [`llms-full.txt`](https://nagarjunak-pixel.github.io/llms-full.txt) · [`person.json`](https://nagarjunak-pixel.github.io/person.json)

---

### Executive Snapshot
- **Production Scale:** Most recently AI Architect & Technical Lead for a **12+ member AI/ML team across 23+ initiatives at John Deere** — delivering **750K+ automated requests, 42K+ hours saved, and ~25% faster workflow cycle time in FY26**.
- **20+ Years Global Enterprise Data & AI:** 10 years of production ML & Agentic AI (John Deere, Persistent Systems, Vertiv, Soham Global) built on 12 years embedded at client sites as an **SAP BW / BPC / HANA Lead Consultant** across the **UK, Malaysia, Singapore, the US, and India** (GlaxoSmithKline UK, PETRONAS Energy Trading & Deloitte, DHL, Symantec, Lenovo).
- **Certifications:** **AWS Certified Solutions Architect – Professional (`SAP-C02`)** · **NVIDIA-Certified Professional: Agentic AI (`NCP-AAI`)** · **4× SAP Certified** (`SAP HANA`, `SAP BW 7.4`, `SAP Simple Finance`, `SAP BPC`).
- **Corporate AI Training:** Founder of **Surya HANA Academy** (~1,000 professionals trained) & **Suryagentic Institute** (**280+ live AI sessions in 2026**, **570+ online teaching hours**, plus **300+ corporate employees** upskilled at John Deere).
- **Location & Availability:** Currently in **Dubai, UAE** · Available immediately for **Principal / Lead AI Architect, Head of AI, Enterprise SAP + GenAI Architect, Forward Deployed Architect, and Corporate AI Trainer** mandates (UAE/KSA/GCC employer sponsorship, global relocation, or remote) — see [10-Mandate Role-Fit Matrix](https://nagarjunak-pixel.github.io/roles.html).

### What I Work On
RLVR Post-Training (GRPO/DAPO, PRMs, DoRA) · 2D Parallelism (Ring-Attention, Megatron TP) · Speculative C++20 Kernels · Mechanistic Interpretability (SAEs) · Formal Verification (CDCL/SMT) · Agentic AI (LangGraph, CrewAI, MCP) · Hybrid & Neo4j GraphRAG · LLM Evaluation & CI Regression Gates · AI Governance (NIST AI RMF / EU AI Act) · SAP HANA / BTP Integration · LLM Gateways & Drift

---

### Production Architecture Articles & Field Notes
- **[How We Rescued a ~30%-Accurate Enterprise GenAI Product to ~70% Using Multimodal Vision Agents & Rule Gates](https://nagarjunak-pixel.github.io/articles/rescuing-enterprise-genai-30-to-70-percent-accuracy.html)**
- **[AIFlow: Why Production Enterprise AI Needs 255 CI Quality Gates & Zero-Latency Drift Telemetry](https://nagarjunak-pixel.github.io/articles/aiflow-255-llm-evaluation-ci-regression-gates.html)**
- **[Designing StoneAge: Multi-Model Routing (GPT-5, GPT-4o, Gemini) & Why Search-Plus-Rules Beats Fine-Tuning](https://nagarjunak-pixel.github.io/articles/stoneage-copilot-search-plus-rules-over-fine-tuning.html)**
- **[From 48-Hour Batch Loads to 12-Minute SAP HANA Pushdown & 6-Agent Neo4j GraphRAG](https://nagarjunak-pixel.github.io/articles/from-sap-hana-pushdown-to-neo4j-graphrag.html)**
- **[Inside an Enterprise AI Governance Council: Scale, Fix, or Retire Under NIST AI RMF & the EU AI Act](https://nagarjunak-pixel.github.io/articles/enterprise-ai-governance-nist-rmf-eu-ai-act.html)**
- **[20-Year Comparative Architectural Analysis: SAP BI, HANA, Cloud MLOps & Agentic AI (2006–2026)](https://nagarjunak-pixel.github.io/articles/enterprise-transformation-casebook-2006-2026.html)**
- **[50-Chapter Enterprise AI, Claude Code & SAP RAG Masterbook Series](https://nagarjunak-pixel.github.io/nrk-enterprise-ai-masterbook/)**

---

### Featured Projects — Frontier & Enterprise AI Reference Architecture Suite
- **[veritas-rl](https://github.com/nagarjunak-pixel/veritas-rl)** — Frontier RLVR Post-Training, `DoRA`, `2D Parallelism` & Step-Level `PRM` Engine: critic-free `GRPO`/`DAPO` with native `C++20` advantages & Schulman $k_3$ KL (`6.25% → 50.00%` `Pass@1`, `8.0x` lift), ICML '24 Oral `DoRA` (`563x` lower MSE than LoRA, `0.00000000` merge `|Δ|`), causal Online-Softmax `Ring-Attention` + `Megatron` 2D TP autograd parity (`< 1.5e-6`), and live `qwen3.5:4b` Step-Level PRM scaling (`62.5% → 100.0%` Olympiad `Best-of-6`).
- **[axiom-zero](https://github.com/nagarjunak-pixel/axiom-zero)** — Verified Frontier Transformer Runtime, Mechanistic `Top-K` Sparse Autoencoder Steering & `1-UIP` CDCL Proof Engine: from-scratch PyTorch `RoPE + GQA + SwiGLU` Transformer + CoW Paged KV, native `C++20` lossless speculative kernel (`4.00x` fewer target passes, `TV = 0.014`), unit-norm `Top-K` SAE (`R² = 0.9855`, `0% → 99.9%` causal steering), independent `RUP` proof checker, and live `qwen3.5:4b` CEGIS repair (`10% → 90%` verified lift, `0.0%` unsafe leakage).
- **[aegis-runtime](https://github.com/nagarjunak-pixel/aegis-runtime)** — Deterministic Zero-Trust Control Plane & Transactional Saga Engine for Enterprise AI Agents: custom `.aegis` AST policy compiler (29 µs median), Biba/Bell-LaPadula taint lattices, AES-256-GCM PII vault, orchestrated SAP/ERP compensating rollbacks, and RFC-6962 Merkle + Ed25519 audit ledger.
- **[chronos-mesh](https://github.com/nagarjunak-pixel/chronos-mesh)** — Neuro-Symbolic Multi-Echelon Supply-Chain Digital Twin & Exact Branch-and-Bound MILP Optimizer: 4-tier diamond BOM contagion (Simchi-Levi TTR vs TTS), Two-Phase Simplex + Bland's rule multi-sourcing across Cost/SLA/Scope-3 Carbon Pareto frontiers, and Monte Carlo `CVaR95` tail-risk engine (-81.4% tail loss).
- **[prism-gate](https://github.com/nagarjunak-pixel/prism-gate)** — High-Throughput OpenAI-Compatible Multi-Tenant LLM Gateway, Speculative Cascade Router & Drift Plane: TCP-Vegas/Gradient2 adaptive concurrency (~4,660 req/s, 67 µs median overhead), dual token-bucket priority shedding, inline atomic claim-faithfulness judge, and `PSI` + base-2 Jensen-Shannon drift detection (-57% FinOps spend).

### Multi-Agent & RAG Applications ([Browse All 38 Public Repos →](https://nagarjunak-pixel.github.io/projects.html))
- **[company-os](https://github.com/nagarjunak-pixel/company-os)** — Config-driven autonomous company runtime (`company.json`), 7 executive AI agents, SIM + LIVE modes, Kanban dashboard, KPI engine.
- **[llm-knowledge-base](https://github.com/nagarjunak-pixel/llm-knowledge-base)** — LLM knowledge base: ingest sources, compile a Markdown wiki, search with SQLite FTS5, and ask grounded questions (FastAPI + SQLite).
- **[surya-shiksha](https://github.com/nagarjunak-pixel/surya-shiksha)** — AI-powered agentic learning operating system with 12 specialized agents for curriculum, tutoring, and assessment.
- **[langgraph-localai-tv](https://github.com/nagarjunak-pixel/langgraph-localai-tv)** — LangGraph 3-stage news pipeline with human approval gates, checkpoint persistence, and error recovery.

### Direct Contact
- **Website:** [nagarjunak-pixel.github.io](https://nagarjunak-pixel.github.io/)
- **LinkedIn:** [linkedin.com/in/nagarjuna-kamireddy](https://www.linkedin.com/in/nagarjuna-kamireddy)
- **Email:** `gmailtonagarjuna@gmail.com` · `sendemailtonagarjuna@gmail.com`
- **Phone / WhatsApp:** `+971 50 742 4361` (Dubai, UAE) · `+91 93913 47406` (India)
