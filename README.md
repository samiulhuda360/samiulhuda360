### Samiul Huda

**AI and automation engineer in Auckland, New Zealand · MSc Data Science**

I build AI systems that companies can trust with real work: retrieval-augmented assistants that cite their
sources and say "I don't know" when they should, multi-agent automation that runs every day on a small
server, and the evaluation harnesses that prove a change made things better.

**Featured**

| Project | What it shows |
|---|---|
| **[catalogue-rag](https://github.com/samiulhuda360/catalogue-rag)** | A product-knowledge assistant over 54 public door hardware catalogues: hybrid BM25 + embedding retrieval, table-aware chunking, cite-or-decline answers, streaming UI. Measured: 20% → **98% correct**, 100% of unanswerable questions declined, ~2 s per answer. Runs on a self-hosted GPU model too. |
| **[Campaign Copilot](https://github.com/samiulhuda360/marketing-campaign-ai-copilot)** | AI marketing copilot: customer response model (ROC-AUC 0.89, calibrated) with SHAP explanations, a tool-calling LLM analyst agent that writes and runs SQL on DuckDB (12/12 on a gold-SQL eval, also with a free open-weight model), a structured-output campaign planner and an MCP server. |
| *hermes-fleet* (publishing soon) | A fleet of LLM agents that run scheduled business tasks (research, SEO monitoring, job search, reporting) with a FastAPI + React command centre, Telegram delivery and self-checks. In daily use. |
| [Poultry disease detection (CNN)](https://github.com/samiulhuda360/Diagnosing-Chicken-Diseases-via-Convolutional-Neural-Networks) | Deep learning image classifier (TensorFlow/Keras) that screens chickens for Coccidiosis and Salmonella: 84.8% accuracy, ROC-AUC up to 0.97. |
| [Visual question answering API](https://github.com/samiulhuda360/visual-question-answering-api) | Ask questions about an image in plain English: ViLT vision-language transformer served with FastAPI, web UI, Docker image tested in CI. |

**What I work with**

- **AI and data:** RAG, LLM agents and tool use, embeddings and vector search (ChromaDB), BM25, evaluation design, prompt engineering, scikit-learn, TensorFlow, pandas
- **Models:** OpenAI-compatible APIs and OpenRouter, open-weight models (Qwen, Llama), self-hosting with vLLM or Ollama
- **Backend:** Python, FastAPI, Flask, Django, SQLite, REST and server-sent events
- **Frontend:** React, TypeScript, Vite, plain JavaScript and Canvas
- **Ops:** Linux servers, Docker, nginx, systemd, cron, GitHub Actions, pytest

**Approach:** measure before and after, keep a human in the loop where mistakes are costly, and prefer a
boring dependable system over a clever fragile one.

📫 Open to AI, automation and data roles in Auckland.
