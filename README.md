# Mark Sunner

Former CTO ([MessageLabs](https://en.wikipedia.org/wiki/MessageLabs), acquired by Symantec 2008). Now retired, happy tinkering and building local AI infrastructure on NVIDIA DGX Spark hardware. 

I work with AI agents daily and much of what you see here is built collaboratively. I provide the hardware, the direction, and the domain experience; the agents handle the heavy engineering. It's a genuine partnership and I'm not shy about it.

---

## DGX Spark Infrastructure

Running 122B–198B parameter models on single and dual NVIDIA DGX Spark systems. Real benchmarks, real hardware, no cloud.

→ **[dgx-spark](https://github.com/marksunner/dgx-spark)** — Start here. Navigational guide to all DGX Spark work, organised by inference engine.

### Inference engines

- **[Atlas](https://github.com/marksunner/atlas)** *(contributions merged)* — Step 3.7 Flash support for the pure Rust inference engine. [PR #136](https://github.com/Avarok-Cybersecurity/atlas/pull/136) (merged): NVFP4 support, Blackwell kernels, expert parallelism. [Issue #184](https://github.com/Avarok-Cybersecurity/atlas/issues/184#issuecomment-4885603221): extended findings — FP8 quality fix, 13 bug fixes, 70K context validation. [Test artifacts](https://github.com/marksunner/dgx-spark-step37-flash-atlas).
- **vLLM** — [Step 3.7 Flash dual-Spark](https://github.com/marksunner/dgx-spark-step37-dual) (NVFP4, RoCE RDMA, 262K context, 18.5 tok/s) · [DeepSeek V4 benchmark](https://github.com/marksunner/dgx-spark-vllm-tp-benchmark)
- **llama.cpp** — [Step 3.7 Flash single-Spark](https://github.com/marksunner/dgx-spark-step37-flash) (27 tok/s, 128K context) · [Qwen 122B agent stack](https://github.com/marksunner/dgx-spark-single-stack) (47 tok/s)

---

## Other interests

- **[decoherence-paper](https://github.com/marksunner/decoherence-paper)** — Speculative physics: quantum decoherence and the emergence of classical reality. Worldbuilding for a hard SF novel, not a contribution to physics.
- **[storytelling-psychology](https://github.com/marksunner/storytelling-psychology)** — Communication frameworks grounded in cognitive psychology. Built from years of helping technical teams make complex ideas land.
- **[helix](https://github.com/marksunner/helix)** — A non-linear cognition interface for voice AI, designed for dyslexic thinking. Currently paused while pursuing infrastructure work.
