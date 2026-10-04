<div align="center">

# 👋 Hi, I'm Aditya Sharma

### Backend Engineer · AI/ML Engineer · Systems & Software Developer

Building scalable backend systems, intelligent applications, and production-oriented software.

<br>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_USERNAME)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

</div>

---

## 🚀 About

I design and build **backend systems, APIs, data-driven applications, and machine learning solutions** with a focus on performance, scalability, security, and clean architecture.

My technical interests span:

- ⚙️ Backend Engineering & API Architecture
- 🏗️ Scalable & Distributed Systems
- 🤖 Machine Learning & Deep Learning
- 🗄️ Database Engineering
- ☁️ Cloud Infrastructure & DevOps
- 🔐 Authentication & Application Security
- 🧠 Data Structures & Algorithms

---

## 🛠️ Technology Stack

### Languages

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" width="48"/>
</p>

`Python` · `Java` · `JavaScript` · `SQL`

---

### Backend & APIs

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="48"/>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlalchemy/sqlalchemy-original.svg" width="48"/>
</p>

`FastAPI` ·  `PostgreSQL` · `SQLAlchemy`

---

### AI / Machine Learning

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="48"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" height="48" alt="scikit-learn"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/keras/keras-original.svg" width="48"/>
</p>

`NumPy` · `Pandas` · `Scikit-Learn` · `TensorFlow` · `Keras`

---

### Cloud, DevOps & Engineering

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="48"/>
<img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white" height="48" alt="Oracle Cloud"/>
</p>

`Docker` · `Linux` · `Git` · `GitHub` · `Oracle Cloud`

---

### Development & API Tools

<p>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" width="48"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/streamlit/streamlit-original.svg" width="48"/>

</p>

`Postman` · `Streamlit` 

---

## 🧠 InsightRAG: Document Q&A with LLMs *(AI Engineer)*

A retrieval-augmented generation system that answers questions over private documents, with cited sources and evaluation built in.

**Architecture**

```text
User Query
  │
  ▼
FastAPI Gateway
  │
  ├── Query Rewriting
  ├── Hybrid Retrieval (BM25 + Vector Search)
  ├── Reranker
  └── LLM Generation + Citations
  │
  ▼
Vector DB (FAISS / pgvector)  ◄──  Ingestion Pipeline
                                   (Parse → Chunk → Embed)
```

**Highlights**
- Hybrid retrieval with reranking to improve answer relevance
- Evaluation harness for retrieval recall and answer faithfulness
- Streaming responses, caching, and request tracing

**Stack:** `Python` `FastAPI` `LangChain/LlamaIndex` `pgvector` `Docker`

---

## Satelite: End-to-End ML Pipeline *(AI/ML)*

A production-style ML workflow covering training, tracking, deployment, and monitoring.

**Architecture**

```text
Raw Data
  │
  ▼
Feature Pipeline (Pandas / scikit-learn)
  │
  ▼
Training + Hyperparameter Tuning (XGBoost / PyTorch)
  │
  ▼
Experiment Tracking (MLflow)
  │
  ▼
Model Registry ──► FastAPI Inference Service ──► Drift Monitoring
```

**Highlights**
- Reproducible pipelines with versioned data and models
- Cross-validation, calibration, and error analysis
- Containerized inference API with health checks

**Stack:** `Python` `scikit-learn` `PyTorch` `MLflow` `Docker` `GitHub Actions`

---



**Highlights**
- Redis caching for low-latency redirects
- Token-bucket rate limiting per user and IP
- Async workers for analytics so redirects stay fast
- Load-tested with Locust, with documented results

**Stack:** `FastAPI` `PostgreSQL` `Redis`  `Docker` `pytest`