# Mark Sunner

Former CTO ([MessageLabs](https://en.wikipedia.org/wiki/MessageLabs), acquired by Symantec 2008). Now building AI infrastructure on NVIDIA DGX Spark hardware — running large language models locally, benchmarking inference engines, and contributing upstream where it helps.

I work with AI agents daily and have done since early 2026. Much of what you see here is built collaboratively — I provide the hardware, the direction, and the domain experience; the agents handle the heavy engineering. It's a genuine partnership and I'm not shy about saying so.

---

## DGX Spark Infrastructure

Running 122B–198B parameter models on single and dual NVIDIA DGX Spark systems. Real benchmarks, real hardware, no cloud.

- **[dgx-spark-step37-flash](https://github.com/marksunner/dgx-spark-step37-flash)** — Step 3.7 Flash (198B MoE) on a single DGX Spark. 27 tok/s, 128K context, agent-ready.
- **[dgx-spark-single-stack](https://github.com/marksunner/dgx-spark-single-stack)** — Complete AI agent on one Spark: Qwen 122B + Hermes + Honcho. GPU inference and CPU agent framework sharing unified memory without competing.
- **[dgx-spark-vllm-tp-benchmark](https://github.com/marksunner/dgx-spark-vllm-tp-benchmark)** — DeepSeek V4 Flash dual-Spark benchmark via vLLM tensor parallelism over NCCL/RoCE.
- **[dgx-spark-ds4-benchmark](https://github.com/marksunner/dgx-spark-ds4-benchmark)** — DeepSeek V4 Flash distributed inference on dual Sparks using ds4 (DwarfStar).

### Open source contributions

- **[Atlas inference engine](https://github.com/Avarok-Cybersecurity/atlas/pull/119)** — Added Step 3.7 Flash NVFP4 support: kernel target, config parser, weight loader, and expert parallelism preprocessing for the pure Rust inference engine.

---

## Other interests

- **[decoherence-paper](https://github.com/marksunner/decoherence-paper)** — Speculative physics: quantum decoherence and the emergence of classical reality. Worldbuilding for a hard SF novel, not a contribution to physics.
- **[storytelling-psychology](https://github.com/marksunner/storytelling-psychology)** — Communication frameworks grounded in cognitive psychology. Built from years of helping technical teams make complex ideas land.
- **[helix](https://github.com/marksunner/helix)** — A non-linear cognition interface for voice AI, designed for dyslexic thinking. Currently paused while pursuing infrastructure work.
