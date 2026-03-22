# 👨‍💻 Sagar Paudel | Lead AI / ML Engineer

## 🚀 About Me
* I build production-grade AI systems that combine Machine Learning, Generative AI, and scalable infrastructure to solve high-impact, real-world problems.
* With 8+ years of experience, my work has evolved from classical ML systems to end-to-end Agentic AI architectures, where LLMs are orchestrated with tools, memory, and workflows to automate complex decision-making.
* Currently, I work as a Lead Data Scientist, designing systems that power credit risk, fraud detection, and financial intelligence at scale, supporting 5M+ predictions per month across an NPR 9B+ lending portfolio.
* I am also actively developing **SystemX**, a Linux server management software, and **MLfy**, an Auto ML platform to streamline machine learning workflows.

---

## 🏗️ What I Work On

### 🤖 Agentic AI Systems (LLM + Tools + Orchestration)
**Designing multi-step reasoning systems using:**
* LangChain, LangGraph, CrewAI, Google ADK, MCP

**Building RAG pipelines:**
* Hybrid retrieval (BM25 + dense embeddings)
* Vector stores (FAISS, Chroma, Elasticsearch)
* Re-ranking strategies for improved grounding

**Implementing:**
* Tool calling agents (APIs, DBs, credit bureau parsing)
* Memory (short-term + long-term + semantic retrieval)
* Structured outputs (Pydantic, JSON schema validation)

**Use cases:**
* Automated credit report analysis
* Risk summarization agents
* Decision-support systems

### 🧠 Machine Learning Systems (Production)
**End-to-end ML lifecycle:**
* Feature engineering → model training → evaluation → deployment → monitoring

**Models:**
* Gradient Boosting: XGBoost, LightGBM, CatBoost
* Statistical: GLM, survival models, Bayesian models (PyMC)
* Deep Learning: LSTM, Transformers (NLP tasks)

**Core applications:**
* Credit risk modeling (PD, LGD proxies)
* Fraud & anomaly detection (PyOD, isolation forests)
* Recommendation systems
* Time series forecasting (Prophet, LSTM)

**Metrics:**
* AUC, KS, Gini, Precision-Recall, calibration

### ⚙️ MLOps & ML Infrastructure
**Pipeline orchestration & tracking:**
* Airflow, Kubeflow Pipelines
* MLflow, Git, DVC

**Deployment & Scaling:**
* FastAPI, Flask (REST APIs) for batch + real-time inference systems
* Docker, Kubernetes

**Monitoring & CI/CD:**
* Data drift, concept drift, performance monitoring
* Automated training + deployment workflows

### 💾 Data Engineering & Real-Time Systems
* **Distributed processing:** Spark, PySpark, Hadoop ecosystem
* **Streaming:** Kafka, Flink
* **Storage & querying:** PostgreSQL, MySQL, ClickHouse, Cassandra
* **Data lake:** S3, MinIO, Iceberg
* **ETL/ELT:** dbt, Airflow pipelines
* **Event-driven architectures:** Real-time fraud detection pipelines

---

## 🏛️ Example System Architecture

```mermaid
flowchart TD
    A["User / API Request"] --> B["API Layer (FastAPI)"]
    B --> C["Orchestrator (LangGraph / CrewAI)"]
    C --> D["LLM (OpenAI / Google GenAI)"]
    C --> E["Tools Layer"]
    E --> F["Vector DB (FAISS / Chroma)"]
    E --> G["Feature Store (Feast)"]
    E --> H["External APIs / Credit Bureau"]
    C --> I["Memory Layer"]
    I --> F
    D --> J["Structured Output"]
    J --> K["Decision Engine"]
    K --> L["Database / Downstream System"]
```

---

## 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | Python, SQL, R |
| **ML & Stats** | scikit-learn, XGBoost, LightGBM, CatBoost, Statsmodels, PyMC, Lifelines, SHAP, LIME |
| **Deep Learning & GenAI** | PyTorch, TensorFlow, Transformers, LangChain, LangGraph, CrewAI, Google GenAI, MCP |
| **Data & Infra** | Spark, Kafka, Flink, Airflow, Kubeflow, MLflow, Docker, Kubernetes, AWS (S3, SageMaker), MinIO |

---

## 📂 What You’ll Find on My GitHub
* End-to-end ML system design (not just notebooks)
* Agentic AI workflows with real-world use cases
* Scalable RAG pipelines with evaluation
* Production-ready FastAPI services
* Clean, modular, and reproducible code

---

## 💡 Philosophy
> *"If it’s not in production, it’s a prototype."*

* Focus on scalability, reliability, and measurable impact
* Prefer simple, explainable systems over unnecessary complexity
* Treat data + models + infra as one system

---

## 📫 Let’s Connect
If you're working on **Agentic AI**, **RAG systems**, or **Scalable ML infrastructure**, I’m always open to collaborating or exchanging ideas. Let's connect!
