# Hi, I'm Nagarjuna Kamireddy 👋

**Lead AI Architect** — I turn messy enterprise processes into production AI, and stay with it until people actually use it.

- Most recently technical lead and AI architect for a 12+ member AI/ML team at John Deere: 23+ initiatives, 750K+ automated requests and 42K+ hours saved in FY26
- 20+ years in enterprise data and AI — from SAP BW / HANA consulting across the UK, Malaysia, Singapore, India and the US to agentic AI
- Based in Dubai · open to Principal / Lead AI Architect, Head of AI, Frontier Systems & Forward Deployed roles

### What I work on
Sub-Byte Quantization (GPTQ/AWQ/SpinQuant/FP8) · RLVR Post-Training (GRPO/DAPO, PRMs, DoRA) · 2D Parallelism (Ring-Attention, Megatron TP) · Speculative C++20 Kernels · Mechanistic Interpretability (SAEs) · Formal Verification (CDCL/SMT) · Agentic ERP Sagas · Operations Research · LLM Gateways

### Featured projects — 6-Crown Frontier & Enterprise AI Reference Architecture Suite
- **[quant-forge](https://github.com/nagarjunak-pixel/quant-forge)** — Sub-Byte LLM Quantization, Second-Order Cholesky `GPTQ`/`AWQ`, `SpinQuant` Walsh-Hadamard & Native `C++20` `INT4` Engine: `2 weights/byte` fused register GEMM (`6.40x` byte compression, `7.2e-7` `|Δ|`), Cholesky $H^{-1}$ `GPTQ` (`25.49x` lower MSE / `+14.1 dB` SQNR vs RTN), `FWHT` incoherence (`7.49x` outlier crest reduction), OCP `FP8 E4M3/E5M2`, `H100`/`M3 Max` Roofline autotuner, and live `qwen3.5:4b` `Q4_K_M` audit (`78.7 tok/s`, `2.72x` footprint reduction).
- **[veritas-rl](https://github.com/nagarjunak-pixel/veritas-rl)** — Frontier RLVR Post-Training, `DoRA`, `2D Parallelism` & Step-Level `PRM` Engine: critic-free `GRPO`/`DAPO` with native `C++20` advantages & Schulman $k_3$ KL (`6.25% → 50.00%` `Pass@1`, `8.0x` lift), ICML '24 Oral `DoRA` (`563x` lower MSE than LoRA, `0.00000000` merge `|Δ|`), causal Online-Softmax `Ring-Attention` + `Megatron` 2D TP autograd parity (`< 1.5e-6`), and live `qwen3.5:4b` Step-Level PRM scaling (`62.5% → 100.0%` Olympiad `Best-of-6`).
- **[axiom-zero](https://github.com/nagarjunak-pixel/axiom-zero)** — Verified Frontier Transformer Runtime, Mechanistic `Top-K` Sparse Autoencoder Steering & `1-UIP` CDCL Proof Engine: from-scratch PyTorch `RoPE + GQA + SwiGLU` Transformer + CoW Paged KV, native `C++20` lossless speculative kernel (`4.00x` fewer target passes, `TV = 0.014`), unit-norm `Top-K` SAE (`R² = 0.9855`, `0% → 99.9%` causal steering), independent `RUP` proof checker, and live `qwen3.5:4b` CEGIS repair (`10% → 90%` verified lift, `0.0%` unsafe leakage).
- **[aegis-runtime](https://github.com/nagarjunak-pixel/aegis-runtime)** — Deterministic Zero-Trust Control Plane & Transactional Saga Engine for Enterprise AI Agents: custom `.aegis` AST policy compiler (29 µs median), Biba/Bell-LaPadula taint lattices, AES-256-GCM PII vault, orchestrated SAP/ERP compensating rollbacks, and RFC-6962 Merkle + Ed25519 audit ledger.
- **[chronos-mesh](https://github.com/nagarjunak-pixel/chronos-mesh)** — Neuro-Symbolic Multi-Echelon Supply-Chain Digital Twin & Exact Branch-and-Bound MILP Optimizer: 4-tier diamond BOM contagion (Simchi-Levi TTR vs TTS), Two-Phase Simplex + Bland's rule multi-sourcing across Cost/SLA/Scope-3 Carbon Pareto frontiers, and Monte Carlo `CVaR95` tail-risk engine (-81.4% tail loss).
- **[prism-gate](https://github.com/nagarjunak-pixel/prism-gate)** — High-Throughput OpenAI-Compatible Multi-Tenant LLM Gateway, Speculative Cascade Router & Drift Plane: TCP-Vegas/Gradient2 adaptive concurrency (~4,660 req/s, 67 µs median overhead), dual token-bucket priority shedding, inline atomic claim-faithfulness judge, and `PSI` + base-2 Jensen-Shannon drift detection (-57% FinOps spend).

### Additional projects
- **[company-os](https://github.com/nagarjunak-pixel/company-os)** — CompanyOS — run ANY company with a team of AI agents. Config-driven (company.json), 7 role-agents, SIM + LIVE modes, kanban dashboard, KPI engine.
- **[llm-knowledge-base](https://github.com/nagarjunak-pixel/llm-knowledge-base)** — LLM knowledge base: ingest sources, compile a markdown wiki, search, and ask questions (FastAPI + SQLite).
- **[surya-shiksha](https://github.com/nagarjunak-pixel/surya-shiksha)** — SURYA SHIKSHA - AI-Powered Agentic Learning Operating System for Children
- **[langgraph-localai-tv](https://github.com/nagarjunak-pixel/langgraph-localai-tv)** — LangGraph 3-stage news pipeline: headlines → video → bulletin. Human approval gates, checkpoint persistence, error recovery.

### Connect
[LinkedIn](https://linkedin.com/in/nagarjuna-kamireddy) · sendemailtonagarjuna@gmail.com
