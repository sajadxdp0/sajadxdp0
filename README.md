# Sajad

**Software Engineer · Backend Operations & AI Products**

I build the services that sit underneath AI features: ingestion workers, retrieval layers, auth and access control, event delivery, and the interfaces on top of them. Most of my time goes into the unglamorous parts—making a queue recover cleanly from a crashed worker, keeping vector indexes isolated per tenant, or writing a deterministic fallback so a product still works when an LLM API is down.

**Core** · Python, FastAPI, PostgreSQL, Redis, Celery, SQLAlchemy, Pydantic, Docker
**AI & retrieval** · embeddings, FAISS, LangChain, OpenAI, retrieval caching, SSE streaming
**ML fundamentals** · scikit-learn, TF-IDF, model evaluation, pandas
**Product & web** · TypeScript, Next.js, React, Express, Tailwind CSS
**Operations** · GitHub Actions, Alembic, Prometheus metrics, structured logging, JWT/RBAC

## Selected work

- **[Lexora](https://github.com/sajadxdp0/lexora-ai)** — Document Q&A backend with cited sources. Validated uploads, Celery ingestion, per-user FAISS vector isolation, Redis retrieval cache, and answers streamed over SSE. Includes a deterministic retrieval-recall probe.
- **[HookFlow](https://github.com/sajadxdp0/hookflow)** — Persist-first webhook delivery. Events commit before any dispatch attempt, workers claim rows with expiring leases, payloads are HMAC-signed, and failed deliveries land in a replayable dead-letter queue.
- **[EsenceLab](https://github.com/sajadxdp0/esencelab)** — Multi-service hiring platform across a Next.js frontend, an Express API with RBAC, and a FastAPI resume parser and job matcher with deterministic scoring and an optional LLM assist.
- **[neuDB](https://github.com/sajadxdp0/neudb)** — Zero-dependency embedded database in pure Python. One human-readable JSON file per table, crash-atomic writes, and brute-force text and cosine search.

## Foundations

- **[spam-classifier](https://github.com/sajadxdp0/spam-classifier)** — End-to-end SMS spam baseline with a leakage-aware split. Three models compared by 5-fold CV, selected by F1, then evaluated once on 1,032 held-out messages (**0.937 F1**, 0.952 precision, 0.922 recall), with a one-message CLI.
- **[dsa-practice](https://github.com/sajadxdp0/dsa-practice)** — 40 Python solutions across 12 patterns. Every problem has its source link, a short approach note, time and space complexity, and a test that runs in CI.

## Links

[Portfolio](https://sajadxdp0.github.io/) · [LinkedIn](https://linkedin.com/in/abdullasajad) · [abdullasajad01@gmail.com](mailto:abdullasajad01@gmail.com)
