# Hi, I'm Dheeraja 👋

**Data Engineer** building production-style data platforms — from streaming ingestion to orchestrated ML and agentic AI systems.

I care about pipelines that fail loudly, honest evaluation over flattering metrics, and documenting the real debugging journey, not just the polished result.

---

## 🚀 Featured Projects

### 🇮🇳 [India Development Study](https://github.com/Pattem-DE/India-development-study)
An end-to-end data platform tracing India's economic and digital transformation (2015-2025) across 3 stages:

- **Stage 1 — Data Engineering:** Multi-source ingestion (World Bank, NPCI, Climate TRACE) → dbt (staging/intermediate/marts, 6 models, 16 tests) → Airflow orchestration via Docker Compose
- **Stage 2 — Machine Learning:** 3 validated models — UPI volume forecasting (Prophet, 3.17% MAPE), GDP-emissions decoupling analysis, and data-driven development-era clustering (K-Means, silhouette-validated)
- **Stage 3 — Agentic RAG:** A local-first AI system answering questions about India's policy documents (Union Budget speeches, NITI Aayog reports) using Ollama + pgvector, with automatic cloud fallback (Groq + Supabase) for public deployment

**🔗 [Live interactive dashboard](https://india-development-study.streamlit.app)** — try the RAG assistant yourself

`Python` `dbt` `Airflow` `Docker` `DuckDB` `Prophet` `scikit-learn` `LangChain` `Ollama` `pgvector` `Streamlit`

---

### 📊 [StockPlus — Real-Time Stock Analytics](https://github.com/Pattem-DE/Stockplus-Realtime-Analytics)
A real-time stock market analytics platform built solo, covering the full streaming-to-BI stack:

- **Streaming:** Kafka ingestion from Finnhub API → MinIO object storage
- **Orchestration:** Airflow DAGs for ingestion and warehouse loading
- **Warehouse:** Snowflake with a Medallion architecture (Bronze → Silver → Gold)
- **BI:** PowerBI dashboards + a web frontend for interactive exploration

`Python` `Kafka` `MinIO` `Airflow` `Snowflake` `dbt` `PowerBI`

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| Languages | Python · SQL |
| Orchestration | Apache Airflow |
| Transformation | dbt |
| Storage / Warehousing | Snowflake · DuckDB · PostgreSQL · pgvector |
| Streaming | Apache Kafka · MinIO |
| ML / AI | scikit-learn · Prophet · LangChain · Ollama |
| BI / Visualization | Streamlit · PowerBI |
| DevOps | Docker · Docker Compose · Git |

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Pattem-DE&show_icons=true&theme=default&hide_border=true)

---

## 📬 Let's Connect

Open to Data Engineering roles. Feel free to explore the repos above — both include detailed READMEs documenting not just what was built, but the real engineering problems solved along the way.
