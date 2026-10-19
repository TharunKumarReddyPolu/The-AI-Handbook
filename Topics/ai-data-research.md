# 📊 AI Data & Research

> Essential platforms for AI research, datasets, vector databases, and LLM fine-tuning. Whether you're training models, building RAG pipelines, or exploring papers.

---

## 🔑 Key Concepts

- **Vector Database** — Specialized storage that indexes high-dimensional embeddings for fast semantic similarity search and hybrid (keyword + vector) retrieval
- **LoRA / QLoRA (Parameter-Efficient Fine-Tuning)** — Adapting large models on custom datasets by training small adapter layers rather than updating billions of base weights
- **Document Ingestion** — Parsing messy PDFs, tables, and Office files into clean Markdown or JSON chunks so RAG pipelines retrieve accurate context

---

## 🛠️ Research, Datasets & Document Ingestion

| Resource | Description |
|---|---|
| **[Hugging Face](https://huggingface.co/)** | The GitHub of AI — open-weight models, datasets, and interactive Spaces |
| **[Papers with Code](https://paperswithcode.com/)** | ML papers linked directly to code implementations and SOTA leaderboards |
| **[Kaggle](https://www.kaggle.com/)** | Data science competitions, datasets, and free GPU notebooks |
| **[arXiv AI](https://arxiv.org/list/cs.AI/recent)** | Latest AI research paper preprints |
| **[Semantic Scholar](https://www.semanticscholar.org/)** | AI-powered academic paper search engine and citation graph |
| **[Consensus](https://consensus.app/)** | AI academic search engine that synthesizes findings directly from peer-reviewed papers |
| **[Exa](https://exa.ai/)** | Neural web search engine and API built specifically for AI agents and RAG pipelines |
| **[Stanford STORM](https://storm.genie.stanford.edu/)** | Open-source research system that synthesizes web sources into full Wikipedia-style cited articles ([GitHub](https://github.com/stanford-oval/storm)) |
| **[Docling](https://github.com/docling-project/docling)** | IBM's open-source toolkit for parsing complex PDFs, tables, and Office docs into clean Markdown/JSON |
| **[MarkItDown](https://github.com/microsoft/markitdown)** | Microsoft's lightweight Python tool for converting PDFs, Office files, images, and audio into LLM-ready Markdown |

---

## 🗄️ Vector Databases & Retrieval Engines

| Tool | Description |
|---|---|
| **[Qdrant](https://github.com/qdrant/qdrant)** | High-performance Rust vector database and similarity search engine with rich filtering |
| **[Chroma](https://github.com/chroma-core/chroma)** | Developer-friendly open-source embedding and vector database built for LLM apps |
| **[Pinecone](https://www.pinecone.io/)** | Fully managed serverless vector database for production RAG at scale |
| **[FAISS](https://github.com/facebookresearch/faiss)** | Meta's foundational C++/Python library for ultra-fast dense vector similarity search and clustering |
| **[Vespa](https://vespa.ai/)** | Open-source big-data serving engine combining vector search, full-text search, and structured ranking ([GitHub](https://github.com/vespa-engine/vespa)) |

---

## 🧪 Fine-Tuning & Post-Training Frameworks

| Tool | Description |
|---|---|
| **[Hugging Face PEFT](https://github.com/huggingface/peft)** | State-of-the-art parameter-efficient fine-tuning (LoRA, QLoRA, AdaLoRA) integrated with Transformers |
| **[LitGPT](https://github.com/Lightning-AI/litgpt)** | Lightning AI's hackable implementation for pretraining, fine-tuning, and deploying 20+ LLM families |
| **[OpenRLHF](https://github.com/openrlhf/openrlhf)** | Scalable open-source RLHF and post-training framework built on Ray and vLLM |
| **[verl](https://github.com/verl-project/verl)** | Production-ready LLM reinforcement learning library supporting PPO and GRPO post-training |
| **[DeepSpeed](https://www.deepspeed.ai/)** | Microsoft's distributed training and inference optimization library ([GitHub](https://github.com/deepspeedai/DeepSpeed)) |

---

## 💡 Pro Tips

- **Hugging Face** is where the AI community shares everything — models, datasets, demos, and Spaces
- **Docling** and **MarkItDown** solve the hardest part of RAG: turning messy real-world PDFs and Office docs into clean Markdown before chunking
- Start with **Chroma** (local prototyping) or **Qdrant** / **Pinecone** (production scale) when building semantic search
- **PEFT + LitGPT** let you fine-tune 7B–70B models on a single GPU using QLoRA

---

## 🎯 When to Use What

| Need | Best Tool |
|---|---|
| Academic literature review | Consensus, Semantic Scholar, arXiv AI |
| Deep automated web research reports | Stanford STORM, Exa |
| Converting PDFs/Office docs for LLMs | Docling, MarkItDown |
| Vector search & RAG storage | Qdrant, Chroma, Pinecone |
| Fine-tuning & RL post-training | Hugging Face PEFT, LitGPT, verl, OpenRLHF |

---

[← Back to Handbook](../README.md)
