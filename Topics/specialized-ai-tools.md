# 🔧 Specialized AI Tools

> Domain-specific AI applications and developer infrastructure — from real-time voice frameworks and code sandboxes to LLM observability, data analysis, and job search.

---

## 🔑 Key Concepts

- **Real-Time Voice & Multimodal Pipelines** — Low-latency WebRTC frameworks (like LiveKit Agents and Pipecat) that stream audio between STT, LLMs, and TTS with sub-500ms turn-taking
- **LLM Observability & Evals** — Tracing every prompt, tool call, latency spike, and token cost in production while running automated regression tests (`evals`) on outputs
- **Code Sandboxes** — Isolated microVMs that let AI agents safely execute untrusted Python/JS code, shell commands, and headless browsers

---

## 🛠️ Domain-Specific Tools & Platforms

| Tool | Description |
|---|---|
| **[Project Astra](https://deepmind.google/models/project-astra/)** | Google DeepMind's real-time multimodal AI assistant |
| **[Apify](https://apify.com/)** | The Swiss Army knife of web scraping and browser automation actors |
| **[Julius.ai](https://julius.ai/)** | AI data analyst — upload CSVs/spreadsheets, run Python analysis, and generate charts |
| **[Happenstance.ai](https://happenstance.ai/)** | Deep AI search engine to find people across your network |
| **[Career-Ops](https://github.com/santifer/career-ops)** | Open-source AI-powered job search system |
| **[AI Job Search](https://github.com/MadsLorentzen/ai-job-search)** | Open-source AI-driven job search workflow ([Repo](https://github.com/MadsLorentzen/ai-job-search)) |
| **[Karpathy Jobs Board](https://karpathy.ai/jobs/)** | Curated AI/ML jobs board by Andrej Karpathy |
| **[Burnermail.io](https://burnermail.io/)** | Disposable email addresses for privacy |
| **[GDPval](https://openai.com/index/gdpval/)** | OpenAI's benchmark for evaluating AI models on real-world, economically valuable tasks |

---

## 🎙️ Real-Time Voice & Speech AI Infrastructure

| Tool | Description |
|---|---|
| **[LiveKit Agents](https://github.com/livekit/agents)** | Open-source framework for building real-time, low-latency voice and multimodal AI agents over WebRTC |
| **[Pipecat](https://github.com/pipecat-ai/pipecat)** | Open-source Python framework for real-time voice and multimodal conversational agents |
| **[OpenAI Whisper](https://github.com/openai/whisper)** | Industry-standard open-source multilingual speech recognition and transcription model |
| **[faster-whisper](https://github.com/SYSTRAN/faster-whisper)** | CTranslate2 reimplementation of Whisper — up to 4x faster transcription with lower memory use |
| **[Kokoro-82M](https://github.com/hexgrad/kokoro)** | Ultra-fast, lightweight (82M parameter) open-weight text-to-speech model with natural prosody |
| **[Ultravox](https://github.com/fixie-ai/ultravox)** | Open multimodal speech LLM that understands audio natively without a separate ASR stage |

---

## 🔍 LLM Observability, Evals & Code Sandboxes

| Tool | Description |
|---|---|
| **[Langfuse](https://github.com/langfuse/langfuse)** | Open-source LLM engineering platform for tracing, prompt management, datasets, and evaluations |
| **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** | Open-source OpenTelemetry-based AI observability, tracing, and evaluation platform |
| **[Promptfoo](https://github.com/promptfoo/promptfoo)** | CLI and library for testing, evaluating, and red-teaming prompts, agents, and RAG pipelines |
| **[DeepEval](https://github.com/confident-ai/deepeval)** | Pytest-style open-source evaluation framework for unit-testing LLM outputs, RAG, and agents |
| **[Ragas](https://github.com/vibrantlabsai/ragas)** | Reference-free evaluation toolkit purpose-built for measuring RAG pipeline accuracy |
| **[Opik](https://github.com/comet-ml/opik)** | Open-source platform by Comet for debugging, evaluating, and monitoring LLM apps and agents |
| **[Vercel Sandbox](https://vercel.com/docs/sandbox)** | Ephemeral Linux microVMs for safely executing untrusted agent-generated code ([GitHub](https://github.com/vercel/sandbox)) |
| **[Together Code Sandbox](https://docs.together.ai/docs/together-code-sandbox)** | Fast snapshot-based isolated environments for running AI agent code ([GitHub](https://github.com/togethercomputer/together-sandbox)) |

---

## 💡 Pro Tips

- **LiveKit Agents** and **Pipecat** are the backbone of modern voice AI — pair them with **faster-whisper** and **Kokoro-82M** (or ElevenLabs) for sub-second conversational latency
- Never ship an AI agent to production without tracing and evals: **Langfuse** + **Promptfoo** (or **DeepEval**) catch prompt regressions before users do
- **Apify** can scrape virtually any website — combine it with AI models for automated data extraction pipelines
- **Julius.ai** is the fastest way to analyze data without writing code — just upload a CSV and ask questions

---

## 🎯 When to Use What

| Need | Best Tool |
|---|---|
| Build real-time voice agents | LiveKit Agents, Pipecat |
| Fast open-source STT / TTS | faster-whisper, OpenAI Whisper, Kokoro-82M |
| Trace & monitor LLM calls in production | Langfuse, Arize Phoenix, Opik |
| Unit-test & red-team prompts / RAG | Promptfoo, DeepEval, Ragas |
| Run untrusted agent-generated code | Vercel Sandbox, Together Code Sandbox |
| No-code data analysis | Julius.ai |
| AI-powered job search | Career-Ops, AI Job Search, Karpathy Jobs Board |

---

[← Back to Handbook](../README.md)
