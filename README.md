### AI systems for regulated contact centers: voice agents, real-time compliance, and LLM evaluation pipelines.
Verifiable output. Deterministic grading. Traceable failure modes.

**Currently:** Taking pilot engagements: compliance audits, eval-harness 
builds, and LLM QA pipeline architecture for collections, direct sales, 
and BPO verticals.

---

### Featured

- **[dental-desk](https://github.com/ree2raz/dental-desk)** — Voice agent prototype for clinic appointment scheduling: FSM (Finite State Machine), real-time STT/TTS, turn-taking, tool calls, multilingual support. Built as a client engagement pitch.
  [Live demo](https://dental-desk.rituraj.info)

- **[auditguard-mcp](https://github.com/ree2raz/auditguard-mcp)** — A compliance-aware MCP server. Seven-step pipeline: RBAC, PII detection, policy enforcement, audit logging. 15-case eval, 100% pass.
  [Live demo](https://auditguard.rituraj.info)
  [Blog post](https://www.rituraj.info/posts/auditguard-mcp-compliance-pipeline/)

- **[LLM Deploy Cost Calculator](https://github.com/ree2raz/llm-cost-calculator)** —
  Production-grade GPU sizing, cost comparison, and break-even analysis for LLM
  deployment. Architecture-aware VRAM (GQA, MLA, MoE), throughput model, replica
  multiplier, pricing tiers. 49 model variants, 38 API plans.
  [Live tool](https://llm-cost.rituraj.info) ·
  [Blog post](https://rituraj.info/posts/on-prem-llm-deployment-cto/)

- **[Inference Bench](https://github.com/ree2raz/inference-bench)** —
  Reproducible vLLM vs SGLang vs llama.cpp benchmark on NVIDIA L4 (via Modal).
  Concurrent-request sweeps, TTFT/TPOT, tail latency (p95/p99), success rate.
  SGLang leads throughput (+10%), vLLM leads TTFT at low concurrency.
  [Results](https://llm-bench.rituraj.info)

- **[Scrutiny](https://github.com/ree2raz/scrutiny)** — FDCPA/Reg F call transcript audit in 60 seconds. 12-rule rubric with verbatim evidence quotes and statutory citations. Dual-path evaluator.
  [Live demo](https://scrutiny.rituraj.info) ·
  [Blog post](https://rituraj.info/posts/scrutiny-fdcpa-call-audit/)

- **[RegTriage-OpenEnv](https://github.com/ree2raz/RegTriage-OpenEnv)** —
  An OpenEnv RL environment where the reward signal is auditor approval.
  12 tasks, severity-weighted F1, auto-fail caps.
  [Live demo](https://huggingface.co/spaces/ree2raz/RegTriage-OpenEnv) ·
  [Blog post](https://rituraj.info/posts/regtriage-rl-environment-compliance-auditing/)


### Production background

Previously shipped LLM features to enterprise production at a 
speech analytics company serving regulated contact centers: automated 
quality scoring, real-time compliance assistant, conversational analytics 
engine. Self-hosted on customer infrastructure. Zero data egress.

### Writing

[rituraj.info](https://rituraj.info): notes on production ML, compliance 
systems, and agent architectures.

### Work with me

Pilot engagements for mid-market collections agencies and direct-sales 
companies: FDCPA/FTC compliance audits, automated QA pipeline builds, 
LLM evaluation harness setup.

- [Book a 20-min call](https://cal.com/ree2raz/quick-chat)
- [ree2raz@proton.me](mailto:ree2raz@proton.me)
