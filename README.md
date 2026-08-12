Hi, I'm [Aditya](https://adityaps.work).

AI engineer working on **LLM fine-tuning, quantization, on-device inference, and agent systems** — and a Rust compiler contributor. I graduated from **NIT Trichy** in 2026, shipped production Rust + TypeScript/React as an AI developer on the 5-engineer founding team at [Runitup](https://runitup.ai), and I like building things that hold up in production, not just demos.

More about [me](https://adityaps.notion.site/Aditya-Pratap-Singh-2861e9d33abd80588760fac2a22af86b) · Reach me at [adipras1407@gmail.com](mailto:adipras1407@gmail.com)

## Currently Building

- **[AgentReplay](https://agentreplay.adityaps.work)** — turns production AI-agent failures into verified pull requests. Ingests OpenTelemetry / LangSmith / Langfuse traces, auto-triages errors, loops, and unsafe operations, then reproduces failures in sealed Firecracker microVM sandboxes (zero production-credential exposure) and ships only regression-tested fixes. Supports LangGraph, OpenAI SDK, and CrewAI. *In private beta.*

- **[Veredic](https://github.com/Aditya-PS-05/veredic)** — a security framework that applies formal verification to AI-agent protocols, combining runtime monitoring with static analysis to catch and prevent vulnerabilities in real time with minimal overhead.

## Open Source

Merged PRs in tooling used by millions of developers — full list on [Notion](https://adityaps.notion.site/OSS-Rust-Contributions):

- **[rust-lang/rust](https://github.com/rust-lang/rust)** — fixed an ICE (compiler crash) in import suggestions, plus regression tests covering two further ICE classes.
- **[rust-lang/rust-analyzer](https://github.com/rust-lang/rust-analyzer)** — 4 merged PRs: configurable `dyn` inlay hints and three assist/diagnostic correctness fixes.
- **[astral-sh/uv](https://github.com/astral-sh/uv)** — extended pip compatibility (remaining file extensions, `--emit-index-url` de-duplication).

## Selected Projects

- **[Sunny](https://sunny.adityaps.work)** — a private, on-device skin tracker. Fine-tuned a multimodal LLM (SmolVLM-500M, LoRA/PEFT) on 2,292 clinical images, cut the footprint 93% (5.86 GB to 412 MB) via GGUF quantization, and ran it fully offline on Android with `llama.cpp` — photos never leave the phone. 100% output-schema and safety compliance via grammar-constrained decoding (GBNF).

- **[Codesm](https://github.com/Aditya-PS-05/codesm)** — a multi-agent LLM coding system running up to 10 specialized subagents (coder, researcher, reviewer, planner, finder) across four model providers, with MCP client + LSP integration and a custom evaluation harness. Live at [codesm.adityaps.work](https://codesm.adityaps.work).

- **[tryaudex](https://github.com/Aditya-PS-05/tryaudex)** — scoped, short-lived cloud credentials for AI agents. Wrap any command with temporary IAM permissions that auto-revoke on exit (AWS STS, GCP, Azure, Vault), HMAC-chained audit log, MCP integration, zero secrets on disk. Live at [tryaudex.adityaps.work](https://tryaudex.adityaps.work).

- **[Glintly](https://github.com/Aditya-PS-05/Glintly)** — describe an app in plain English and watch an AI agent build it in real time. Live at [glintly.adityaps.work](https://glintly.adityaps.work).

- **[Piq](https://github.com/Aditya-PS-05/piq)** — a local-first bucket-list app for Android. Dump things you want to try, shake your phone, do the thing. Flutter + SQLite, zero accounts, zero cloud. Live at [piq.adityaps.work](https://piq.adityaps.work).

- **[Visirs](https://github.com/Aditya-PS-05/visirs)** — a Rust library to visually group images and videos.

## Tech

**Languages:** Rust · Python · TypeScript · Go · SQL
**AI/ML:** PyTorch · LLM fine-tuning (LoRA, HF Transformers/PEFT) · GGUF quantization · llama.cpp · on-device inference · grammar-constrained decoding · agent orchestration · MCP · Weights & Biases
**Systems & Web:** Axum · PostgreSQL · Next.js/React · Docker · Firecracker · AWS/GCP/Azure · CI/CD

## Elsewhere

[Website](https://adityaps.work) · [Twitter/X](https://x.com/0xAditya_pratap) · [LinkedIn](https://linkedin.com/in/aditya-pratap-singh-952a8820a) · [Discord](https://discord.gg/adipras_1407)
