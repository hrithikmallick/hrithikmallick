# Hi, I'm Hrithik Mallick 👋

**GenAI Engineer** specializing in LLM & RAG Systems, Text-to-SQL, and Python-based GenAI pipelines.

📍 Kolkata, India
📧 hrithikmallick2000@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/hrithikmallick) · [GitHub](https://github.com/hrithikmallick)

---

## 🚀 About Me

I'm a Gen AI Engineer with 2.5+ years of experience building production-grade GenAI systems for enterprise ERP platforms. My focus areas include RAG pipelines, LLM-based query routing, and rule-assisted Text-to-SQL using **Python, LangChain, OpenAI API, and pgvector**. I've delivered a conversational AI Business Analyst spanning 5+ ERP modules, powered by a two-LLM pipeline for query polishing and result validation.

---

## 💼 Work Experience

### GenAI / Applied AI Engineer — ViTWO-6 Livo Technologies Pvt. Ltd.
*Dec 2023 – May 2026 · Kolkata*

**RAG Architecture & Retrieval**
- Architected a production RAG-based AI Business Analyst over enterprise ERP data (Sales, Procurement, Finance, Inventory, Production), enabling conversational querying across 5+ modules without manual SQL.
- Built a two-LLM pipeline: one LLM polishes and classifies user queries (RAG vs. SQL routing), while a second validates and reformats the final answer against business terminology, improving response quality.
- Implemented domain-aware semantic chunking with tenant-ID isolation, separating metadata from business-data columns to reduce hallucinations on structured tabular ERP data.

**Text-to-SQL & Prompt Engineering**
- Built a context-aware Text-to-SQL engine with rule-assisted generation — schema-bound hard rules + LLM prompt templates convert natural-language questions into SQL across complex multi-table ERP schemas.
- Applied schema-aware prompt templates, few-shot prompting, and chain-of-thought (CoT) reasoning to improve accuracy on multi-join, aggregation-heavy queries.

**Data Engineering & Backend**
- Built ERP data ingestion pipelines: ERP DB → cron → AWS S3 (Parquet) → PySpark batch processing → OpenAI embeddings → pgvector, scoped per tenant ID.
- Developed backend ERP services in Java and Spring Boot — REST APIs, CI/CD pipelines, and AWS EC2 deployments across Sales, Finance, Inventory, and Procurement modules.

---

## 🛠️ Projects

### 🔹 ERP AI Business Analyst — RAG Application (Production · ViTWO.AI)
`Python` `LangChain` `OpenAI` `pgvector` `PySpark` `AWS S3` `FastAPI` `GPT-4`

- Full-stack RAG pipeline: S3 + PySpark ingestion → OpenAI embeddings → pgvector hybrid retrieval → LangChain orchestration → GPT-4 response with rule-assisted Text-to-SQL fallback.
- Replaced manual SQL reporting across 5+ ERP modules, enabling conversational querying and reducing analyst turnaround time.

### 🔹 Big Data Analytics Engine (Personal · Multi-Tenant Spark Lakehouse)
`Python` `FastAPI` `Apache Spark` `Delta Lake` `Docker Compose` `PostgreSQL` `Papermill` `Hive Metastore`

- Multi-tenant analytics platform with split-runtime Docker Compose.
- Medallion Architecture (Bronze → Silver → Gold) with dynamic per-tenant storage path isolation on a shared Spark cluster.

---

## 🧰 Technical Skills

**Languages:** Python · SQL (window functions, joins, aggregations, CTEs) · Java

**GenAI & LLM:** LangChain · LangGraph · OpenAI API (GPT-4, embeddings) · RAG Pipelines · Text-to-SQL · Semantic Chunking · Prompt Engineering · Few-shot & CoT · Agentic Workflows

**Vector & Retrieval:** pgvector · Hybrid Retrieval · Vector Indexing · Metadata Filtering · Embedding Pipelines

**Data & Cloud:** Apache Spark · PySpark · Delta Lake · Databricks · AWS (S3 / EC2 / Athena) · Docker · Medallion Architecture

**Backend & DevOps:** FastAPI · Spring Boot · REST APIs · CI/CD · Git · Papermill · Jupyter

**Currently Exploring:** RAGAS · TruLens · LangSmith · Multi-agent Orchestration · Fine-tuning / PEFT

---

## 📜 Certifications

- **AI Agent Fundamentals** — Databricks (Apr 2026)
- **Python for Data Science, AI & Development** — Coursera (IBM) (Jan 2023)

---

## 🎓 Education

**Guru Nanak Institute of Technology** (2021 – 2023)
MCA — Master of Computer Applications · 9.19 DGPA

---

## 📫 Get in Touch

- Email: hrithikmallick2000@gmail.com
- Phone: +91-7980086348
- LinkedIn: [linkedin.com/in/hrithikmallick](https://linkedin.com/in/hrithikmallick)
