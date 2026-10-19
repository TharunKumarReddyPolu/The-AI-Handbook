# 🔬 AI Benchmarks & Leaderboards

> Track and compare AI model performance. These platforms help you evaluate which models are best for your specific use case.

---

## 🔑 Key Concepts

- **Elo Rating** — A ranking system (like chess) based on head-to-head human preference votes
- **SWE-bench** — Tests an AI's ability to autonomously fix real-world GitHub issues
- **MMLU** — Massive Multitask Language Understanding — now considered a baseline, not a differentiator
- **GPQA** — Graduate-level science questions designed to challenge even PhD experts

---

## 📊 Leaderboards & Benchmarks

| Resource | Description |
|---|---|
| **[LMSYS Chatbot Arena](https://lmarena.ai/)** | Human-preference Elo rankings via blind pairwise comparisons |
| **[Artificial Analysis](https://artificialanalysis.ai/)** | Composite intelligence index with speed and cost metrics |
| **[Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard)** | Hugging Face's open model benchmark tracker |
| **[SWE-bench](https://www.swebench.com/)** | Real-world coding benchmark for agentic AI |
| **[GPQA Diamond](https://github.com/idavidrein/gpqa)** | Graduate-level science reasoning benchmark |
| **[ARC-AGI](https://arcprize.org/)** | Fluid intelligence and novel reasoning test |
| **[LiveBench](https://livebench.ai/)** | Contamination-free benchmark with monthly updated questions and objective ground-truth scoring ([GitHub](https://github.com/LiveBench/LiveBench)) |
| **[LiveCodeBench](https://livecodebench.github.io/)** | Continuously updated coding benchmark built from fresh competitive programming problems ([GitHub](https://github.com/LiveCodeBench/LiveCodeBench)) |
| **[Humanity's Last Exam (HLE)](https://lastexam.ai/)** | 2,500+ frontier academic questions authored by domain experts across math, science, and humanities ([GitHub](https://github.com/centerforaisafety/hle)) |
| **[FrontierMath](https://epoch.ai/frontiermath)** | Epoch AI's benchmark of exceptionally hard, unpublished research-level mathematics problems |
| **[SimpleBench](https://simple-bench.com/)** | Everyday human spatio-temporal and trick-question reasoning benchmark where LLMs still stumble ([GitHub](https://github.com/simple-bench/SimpleBench)) |
| **[OSWorld](https://os-world.github.io/)** | Multimodal benchmark evaluating computer-use agents on real desktop tasks across Ubuntu, Windows, and macOS ([GitHub](https://github.com/xlang-ai/OSWorld)) |
| **[WebArena](https://webarena.dev/)** | Realistic, self-hostable web environment for benchmarking autonomous browser agents ([GitHub](https://github.com/web-arena-x/webarena)) |
| **[GAIA Benchmark](https://huggingface.co/spaces/gaia-benchmark/leaderboard)** | Evaluates General AI Assistants on real-world questions requiring multi-step reasoning, web browsing, and tool use |
| **[τ-bench (Tau-bench)](https://taubench.com/)** | Sierra Research's benchmark testing agents in dynamic multi-turn conversations with users and policy-constrained APIs ([GitHub](https://github.com/sierra-research/tau2-bench)) |
| **[Terminal-Bench](https://www.tbench.ai/leaderboard)** | Evaluates AI coding and ops agents on complex tasks inside real Linux terminal environments ([GitHub](https://github.com/harbor-framework/terminal-bench)) |
| **[Berkeley Function-Calling Leaderboard (BFCL)](https://gorilla.cs.berkeley.edu/leaderboard.html)** | Comprehensive evaluation of how accurately LLMs invoke tools, APIs, and multi-turn functions |
| **[BigCodeBench](https://bigcode-bench.github.io/)** | Next-generation code generation benchmark testing complex instructions and diverse library calls ([GitHub](https://github.com/bigcode-project/bigcodebench)) |
| **[Scale SEAL Leaderboards](https://labs.scale.com/leaderboard)** | Expert-curated private evaluations across coding (`SWE-Bench Pro`), math, multilinguality, and tool use |
| **[BrowseComp](https://openai.com/index/browsecomp/)** | OpenAI's benchmark measuring how effectively browsing agents locate hard-to-find information on the web |
| **[GDPval](https://openai.com/index/gdpval/)** | OpenAI's benchmark for evaluating AI models on real-world, economically valuable tasks |
| **[Perplexity Model Council](https://www.perplexity.ai/hub/blog/introducing-model-council)** | Multiple AI models debate and cross-examine each other to reach an answer |

---

## 💡 Pro Tips

- **Chatbot Arena** is the gold standard for overall model quality — it uses blind human votes, so it's hard to game
- **SWE-bench**, **LiveCodeBench**, and **Terminal-Bench** are what you should check when choosing a coding or terminal agent
- **OSWorld**, **WebArena**, and **τ-bench** separate real action-taking agents from models that only chat well
- **LiveBench** and **Scale SEAL** resist training-data contamination by rotating or keeping evaluation sets private
- **Artificial Analysis** is the best for comparing price-to-performance and token-speed ratios across API providers

---

## 🎯 When to Use What

| What You're Evaluating | Best Benchmark / Leaderboard |
|---|---|
| Overall chat & human preference | LMSYS Chatbot Arena, Scale SEAL |
| API speed, latency & cost per token | Artificial Analysis |
| Autonomous software engineering & CLI agents | SWE-bench, LiveCodeBench, Terminal-Bench, BigCodeBench |
| Computer-use, browser & tool-calling agents | OSWorld, WebArena, τ-bench, BFCL, GAIA |
| Contamination-free & PhD-level reasoning | LiveBench, Humanity's Last Exam, FrontierMath, ARC-AGI |
| Real-world economic & web research tasks | GDPval, BrowseComp |

---

[← Back to Handbook](../README.md)
