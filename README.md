# Mark Sunner

Former CTO ([MessageLabs](https://en.wikipedia.org/wiki/MessageLabs), acquired by Symantec 2008). Now retired, happy tinkering and building local AI infrastructure on NVIDIA DGX Spark hardware. 

I work with AI agents daily and much of what you see here is built collaboratively. I provide the hardware, the direction, and the domain experience; the agents handle the heavy engineering. It's a genuine partnership and I'm not shy about it.

---

## DGX Spark Infrastructure

Running 122B–671B parameter models on single, dual and cluster NVIDIA DGX Spark systems. Real benchmarks, real hardware, no cloud.

→ **[dgx-spark](https://github.com/marksunner/dgx-spark)** — Start here. Navigational guide to all DGX Spark work, organised by inference engine and model.
→ **[dgx-spark-glm52](https://github.com/marksunner/dgx-spark-glm52)** ✨ — Cluster deployment guides written from real experience: **GLM 5.2 on 4× Sparks** (the complete journey from unboxing to first inference) · **What Is Fabric?** (building a lossless RoCE fabric with the MikroTik CRS812, from first principles)

### Inference engines

- **vLLM** — **[GLM 5.2 on 4× Sparks](https://github.com/marksunner/dgx-spark-glm52)** ✨ (671B MoE, all 256 experts, 200K context, ~26 tok/s) · [Step 3.7 Flash dual-Spark](https://github.com/marksunner/dgx-spark-step37-dual) (198B MoE, RoCE RDMA, 262K context, 18.5 tok/s) · [DeepSeek V4 benchmark](https://github.com/marksunner/dgx-spark-vllm-tp-benchmark)
- **[Atlas](https://github.com/marksunner/atlas)** *(contributions merged)* — Step 3.7 Flash support for the pure Rust inference engine. [PR #136](https://github.com/Avarok-Cybersecurity/atlas/pull/136) (merged): NVFP4 support, Blackwell kernels, expert parallelism. [Issue #184](https://github.com/Avarok-Cybersecurity/atlas/issues/184#issuecomment-4885603221): extended findings — FP8 quality fix, 13 bug fixes, 70K context validation. [Test artifacts](https://github.com/marksunner/dgx-spark-step37-flash-atlas).
- **llama.cpp** — [Step 3.7 Flash single-Spark](https://github.com/marksunner/dgx-spark-step37-flash) (27 tok/s, 128K context) · [Qwen 122B agent stack](https://github.com/marksunner/dgx-spark-single-stack) (47 tok/s)

---

## Tools

- **[barrel-index](https://github.com/marksunner/barrel-index)** — **[The Barrel Index](https://marksunner.github.io/barrel-index/)**: Pricing benchmarking for machine intelligence. A single HTML file that shows what every major AI producer charges per million tokens, pulled live from the market and racked like a commodity board. No build step, no dependencies, no API key.

---

## Other interests

- **[decoherence-paper](https://github.com/marksunner/decoherence-paper)** — Speculative physics: quantum decoherence and the emergence of classical reality. Worldbuilding for a hard SF novel, not a contribution to physics.
- **[storytelling-psychology](https://github.com/marksunner/storytelling-psychology)** — Communication frameworks grounded in cognitive psychology. Built from years of helping technical teams make complex ideas land.
- **[helix](https://github.com/marksunner/helix)** — A non-linear cognition interface for voice AI, designed for dyslexic thinking. Currently paused while pursuing infrastructure work.
