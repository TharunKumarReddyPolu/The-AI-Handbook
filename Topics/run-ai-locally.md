# 🏃 Run AI Locally

> Run AI models on your own hardware — no cloud, no API keys, full privacy. The local-first AI movement is thriving.

---

## 🔑 Key Concepts

- **Local Inference** — Running AI models on your own hardware instead of cloud APIs
- **VRAM** — GPU memory (the most critical factor for local AI performance)
- **Quantization** — Reducing model precision (e.g., 16-bit → 4-bit) to fit large models on consumer GPUs
- **OpenAI-Compatible API** — Most local tools expose an API that matches OpenAI's format, so you can swap cloud for local seamlessly

---

## 🛠️ Tools & Platforms

| Tool | Platform | Description |
|---|---|---|
| **[LM Studio](https://lmstudio.ai/)** | Windows, Mac, Linux | GUI for downloading and running local AI models |
| **[LocallyAI](https://locallyai.app/)** | Apple devices | Run open-source AI models on Mac, iPhone, iPad |
| **[Google AI Edge Gallery](https://github.com/google-ai-edge/gallery)** | Android | Run Google's open-source models for free on your phone |
| **[Ollama](https://ollama.com/)** | Windows, Mac, Linux | The standard for running LLMs locally — one-command setup |
| **[GPT4All](https://gpt4all.io/)** | Windows, Mac, Linux | Desktop-friendly local AI — optimized for CPU inference |
| **[Jan](https://jan.ai/)** | Windows, Mac, Linux | Privacy-first, offline ChatGPT alternative |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | Web (self-hosted) | ChatGPT-like interface for local models (pairs with Ollama) |
| **[LocalAI](https://localai.io/)** | Windows, Mac, Linux | Self-hosted drop-in OpenAI API replacement |

---

## 💡 Pro Tips

- **Start with Ollama** — it's one command to install and run any model (`ollama run llama3`)
- **Pair Ollama + Open WebUI** for a private, self-hosted ChatGPT experience
- **LM Studio** is the best GUI option — it checks hardware compatibility before downloading models
- **GPT4All** works great on CPU-only machines (no GPU required)
- **Jan** is the most polished offline ChatGPT alternative for daily use

---

## 🎯 Hardware Recommendations

| Hardware | What You Can Run |
|---|---|
| 8GB RAM (CPU only) | Small models (1-3B parameters) |
| 16GB RAM (CPU only) | Medium models (7B quantized) |
| RTX 3060 (12GB VRAM) | 7B-13B models comfortably |
| RTX 4090 / M-series Mac (24GB+) | 32B+ models, full-speed inference |

---

[← Back to Handbook](../README.md)
