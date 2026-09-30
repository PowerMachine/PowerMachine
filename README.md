# Sungmok (Sam) Kim

I build AI systems that connect research models to real decisions. My work focuses on industrial condition monitoring, latency-aware LLM orchestration, multimodal reasoning, and safety-constrained autonomy.

Graduate researcher at Seoul National University · Seoul, South Korea  
[LinkedIn](https://www.linkedin.com/in/sungmok-kim/)

## Research and engineering

| Area | What I am building |
| --- | --- |
| **PHM + LLM orchestration** | Event-triggered decision support for equipment anomalies, with latency budgets, evidence checks, and comparisons of always-on, gated, and staged inference. |
| **Safe UGV autonomy** | A ROS-based runtime that verifies action candidates before execution, with operator approval, dry-run previews, and command safety checks. |
| **Feedback-driven code revision** | A simulation prototype that proposes behavioral patches, tests them, and promotes only verified changes with rollback support. |
| **Multimodal industrial AI** | Local VLM workflows for industrial drawings and visual question answering. |

## Selected code

| Project | What the repository shows |
| --- | --- |
| [Foundation Model Lab](https://github.com/PowerMachine/foundation-model-lab) · [Evidence site](https://powermachine.github.io/foundation-model-lab/) | Integrated research monorepo connecting multimodal post-training, agent evaluation, distributed correctness, and inference systems through one evidence contract. |
| [Feedback-Driven Code Revision](https://github.com/PowerMachine/feedback-driven-code-revision) | LLM-proposed behavioral patches, deterministic verification, promotion/rollback, and a candid 60-run study including fallback and regression cases. |
| [Domain-Aware VLM QA](https://github.com/PowerMachine/domain-aware-vlm-qa) | Local Qwen3-VL analysis with OCR, retrieval, protected-identifier handling, domain prompts, and conservative safety boundaries. |
| [Verified UGV Autonomy](https://github.com/PowerMachine/verified-ugv-autonomy) | Verification-first robot command path, dry-run controls, simulation, and 74 passing tests. |
| [Multi-Agent Autonomy Runtime](https://github.com/PowerMachine/multi-agent-autonomy) | Local-first agent coordination, model routing, safe defaults, and 8 passing tests. |

## Earlier explorations

| Project | Focus |
| --- | --- |
| [Paper Reviewer — Spring 2025 team project](https://github.com/PowerMachine/spring-2025-paper-reviewer) | PDF ingestion, retrieval, and LLM-assisted review drafts; published as Team 18 work. |
| [PDF Document Reading & Translation](https://github.com/PowerMachine/pdf-document-reading-translator) | Testing document extraction, OCR, reading order, and translated PDF reconstruction. |
| [STT Latency Benchmark](https://github.com/PowerMachine/stt-latency-benchmark) | Comparing speech-to-text processing time for a real-time interpreter prototype. |
| [Selected SNU Coursework](https://github.com/PowerMachine/snu-coursework) | Semester-by-semester code samples in control, reinforcement learning, CUDA, and C++; a curated learning history. |

These are research or prototype code samples, not production systems. Other work will be released only when data, permissions, and reproducibility are ready.

## Working principles

I care about measurable outcomes, reproducible experiments, and clear boundaries between AI recommendations and actions in the physical world.

## Publication boundary

Public repositories are reviewed snapshots. Model weights, private datasets, credentials, field logs, and assets without clear redistribution rights are excluded or kept private. Each repository documents what its evidence supports and what it does not.
