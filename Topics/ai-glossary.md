# 🧠 AI Glossary

> Quick-reference definitions for terms you'll encounter in the AI world. Bookmark this page for whenever you need a refresher.

---

## 📖 Core Terms

| Term | Definition |
|---|---|
| **LLM** | Large Language Model — AI trained on massive text data (e.g., GPT-4, Gemini, Claude) |
| **Prompt Engineering** | The practice of crafting inputs to get better outputs from AI models |
| **RAG** | Retrieval-Augmented Generation — combining AI with a knowledge base to ground answers in real data |
| **MCP** | Model Context Protocol — an open standard for connecting AI models to external tools and data |
| **Fine-tuning** | Adapting a pre-trained model on a specific dataset to improve performance for a particular task |
| **Token** | The basic unit of text that an LLM processes — roughly ¾ of a word in English |
| **Context Window** | The maximum amount of text an LLM can process in a single conversation |
| **Inference** | The process of running a trained AI model to generate predictions or outputs |
| **Embedding** | A numerical representation of text that captures semantic meaning, used for search and similarity |
| **Open Source Model** | An AI model whose weights and code are publicly available (e.g., Llama, Mistral, Gemma) |

---

## 🤖 Agents & Systems

| Term | Definition |
|---|---|
| **AI Agent** | An AI system that can autonomously plan, reason, and take actions to achieve a goal |
| **Multi-Agent System** | Multiple AI agents working together, each with specialized roles, to solve complex problems |
| **Agentic AI** | AI systems designed to act autonomously — plan, execute, and adapt without constant human input |
| **Agentic RAG** | Next-gen RAG where AI agents dynamically plan retrieval, validate evidence, and iterate on results |
| **GraphRAG** | Retrieval-Augmented Generation that builds a knowledge graph of entities and relationships alongside vector search for deeper multi-hop reasoning |
| **Context Engineering** | The discipline of dynamically selecting, compressing, and structuring instructions, memory, retrieved evidence, and tool definitions so an LLM gets the exact context it needs |
| **Computer Use / GUI Agents** | Multimodal agents that observe screenshots and operate graphical interfaces via mouse clicks and keystrokes like a human user |
| **Tool Calling / Function Calling** | An LLM's structured output request asking the host application to execute a specific function or API with typed arguments |
| **Deep Research** | An autonomous multi-step agent workflow that iteratively searches, reads dozens of sources, cross-checks claims, and synthesizes a long-form cited report |
| **A2A (Agent2Agent Protocol)** | Open interoperability standard enabling AI agents built on different frameworks or vendors to discover capabilities and delegate tasks to each other |
| **Vibe Coding** | Coined by Andrej Karpathy — building software primarily through natural-language prompts and rapid iteration with coding agents |

---

## 🧪 Training & Alignment

| Term | Definition |
|---|---|
| **RLHF** | Reinforcement Learning from Human Feedback — aligning models with human preferences via reward signals |
| **DPO** | Direct Preference Optimization — efficient alternative to RLHF for model alignment |
| **AI Distillation** | The process of training a smaller model to replicate the performance of a larger model |
| **Synthetic Data** | AI-generated training data used to augment or replace real-world datasets |
| **Quantization** | Reducing model precision (e.g., 16-bit → 4-bit) to run large models on consumer hardware |

---

## 🧠 Reasoning & Prompting

| Term | Definition |
|---|---|
| **Chain of Thought (CoT)** | Prompting technique where AI breaks problems into explicit intermediate reasoning steps |
| **Reasoning Model** | AI models that "think" before responding via extended internal chain of thought (e.g., o3, DeepSeek-R1) |
| **Zero-shot / Few-shot** | Prompting an AI with zero or a few examples to guide its response format |
| **Mixture of Experts (MoE)** | Architecture that activates only relevant "expert" sub-networks per query for efficiency |
| **Test-Time Compute (Inference-Time Scaling)** | Allocating extra compute while generating an answer — searching, verifying, and refining candidate reasoning paths — to boost accuracy without retraining weights |
| **Structured Outputs** | Enforcing a strict JSON Schema or grammar during token decoding so model responses are guaranteed to match your application's data types |
| **Speculative Decoding** | Inference optimization where a fast draft model proposes multiple tokens ahead and the target model verifies them in parallel in a single forward pass |
| **KV Cache & Prompt Caching** | Storing attention Key/Value tensors from prior tokens (or shared system-prompt prefixes across API calls) to slash time-to-first-token and inference cost |

---

## ⚠️ Safety & Risks

| Term | Definition |
|---|---|
| **Hallucination** | When an AI model generates plausible-sounding but factually incorrect information |
| **Sycophancy** | The tendency of AI models to agree with whatever the user says, even when incorrect |
| **Guardrails** | Safety mechanisms that filter, redact, or block harmful AI inputs and outputs |
| **Prompt Injection** | Attack technique that manipulates AI behavior by embedding hidden instructions in input |

---

## 📝 Other Terms

| Term | Definition |
|---|---|
| **Guesstimate** | An estimate arrived at by a combination of guesswork and calculation |
| **Observed Exposure** | Anthropic's measure of how much human work AI is actually displacing in the labor market — see [Anthropic's research](https://www.anthropic.com/research/labor-market-impacts) |
| **Dyson Sphere** | A hypothetical megastructure enclosing a star to capture its energy — a popular metaphor for civilization-scale energy/compute ambition in AI scaling discussions ([Wikipedia](https://en.wikipedia.org/wiki/Dyson_sphere)) |
| **Project Panama** | OpenJDK initiative connecting the JVM directly to native C/C++ libraries and off-heap memory (Foreign Function & Memory API) — enabling high-performance Java bindings to native ML/CUDA runtimes ([Wikipedia](https://en.wikipedia.org/wiki/Project_Panama)) |
| **HBM** | High Bandwidth Memory — stacked DRAM that gives AI accelerators (GPUs/TPUs) the memory bandwidth large models demand; a key bottleneck in AI hardware scaling ([Wikipedia](https://en.wikipedia.org/wiki/High_Bandwidth_Memory)) |

---

[← Back to Handbook](../README.md)
