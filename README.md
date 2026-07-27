<div align="center">

# Hi 👋, I'm Hochan Son

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=24&duration=3000&pause=800&center=true&vCenter=true&width=700&color=58A6FF&lines=Database+Architect;SRE+%26+DevOps+Engineer;ML+%2F+GenAI+Practitioner;Research-to-Production+Gap+Filler)](https://github.com/ohsono)

**Database Architect · SRE & DevOps Engineer · ML/GenAI Practitioner** — Los Angeles, CA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hochanson)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ohsono)

</div>

---

I build data infrastructure, ML pipelines, and distributed systems. My background spans Adtech, entertainment, and enterprise — from MySpace and Hallmark Labs to Branch.io and ADP, with graduate work at UCLA Trustworthy AI Lab.

## 🔬 Research Focus

I work the gap between GenAI/LLM research and the systems that have to run it in production. Concretely: agentic, intent-conditioned tooling for generative-model selection (Synthony), the training/evaluation infrastructure that supports it at scale (table-synthesizers), and the database, SRE, and DevOps foundation that makes either one reliable. My thesis direction extends this into applying LLM-driven reasoning — RAG and Chain-of-Agents (COA) orchestration — to systems-engineering decisions, treating "which model," "which architecture," and "which infra tradeoff" as the same class of problem: a research-to-production gap that needs both ML judgment and engineering rigor to close.

## 🚀 Selected Projects

**[Synthony](https://github.com/UCLA-Trustworthy-AI-Lab/Synthony)** — *Stress-aware, intent-conditioned agent for generative model selection* ([ICLR 2026 DeLTA](https://arxiv.org/abs/2604.00293), accepted poster)
- Built an agent that recommends the best-fit tabular generative model (GAN / VAE / Diffusion / DP-based / Bayesian / Normalizing Flow) for a given dataset by profiling its "stress" characteristics — privacy sensitivity, class imbalance, cardinality, sample size — instead of defaulting to one architecture.
- Implemented rule-based, LLM-based, and hybrid ranking strategies with explainable tie-breaking and benchmark-driven comparison.

**[table-synthesizers](https://github.com/UCLA-Trustworthy-AI-Lab/table-synthesizers)** — *Synthetic tabular data generation library & evaluation pipeline*
- Unified 16 synthesizer architectures (CTGAN, TVAE, TabDDPM, AutoDiff, TabSyn, AIM, PATECTGAN, DPCART, Bayesian Network, ARF, NFlow, GREAT, and more) behind a single factory interface with per-model production configs.
- Built the end-to-end training → generation → evaluation loop, integrating with alfred-analytica for fidelity and machine-learning-efficacy scoring against real data.
- Deployed distributed training on NCSA DeltaAI (SLURM, H100 GPU nodes) with reproducible experiment tracking and versioned experiment outputs.

**COA-PKV** — *Chain-of-Agents with memory-budgeted context reduction for edge multi-hop reasoning* (paper under rebuttal)
- A Chain-of-Agents (COA) framework that reduces context / KV-cache footprint against an on-device memory budget, enabling multi-hop reasoning on resource-constrained NVIDIA edge-to-desktop hardware (Jetson Orin Nano, DGX Spark).

## 🎯 Areas of Focus

- Synthetic data generation (using Transformer, VAE, Diffusion models) & privacy-preserving ML
- Agentic GenAI systems: LLM-driven reasoning, RAG, and Chain-of-Agents (COA) orchestration
- Legacy Data Ops to SRE & DevOps to scale in the Cloud Native Infra
- Large-scale data/ML pipelines (MLFlow, Kafka, LMDB, distributed training)
- Local LLM inference & serving (CUDA, MLX, RDMA, vLLM, Ollama)
- Large-scale Database engineering (RDBMS, NoSQL, and Distributed SQL)
- CI/CD & containerized for ML workflows (Docker, Kubernetes, GitHub Actions)

## 🛠️ Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge&logoColor=white)
![MLX](https://img.shields.io/badge/MLX-000000?style=for-the-badge&logo=apple&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-6E56CF?style=for-the-badge&logoColor=white)
![Diffusion](https://img.shields.io/badge/Diffusion-FF6F61?style=for-the-badge&logoColor=white)
![VAE](https://img.shields.io/badge/VAE-9B59B6?style=for-the-badge&logoColor=white)

**Data & Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white)
![etcd](https://img.shields.io/badge/etcd-419EDA?style=for-the-badge&logo=etcd&logoColor=white)
![Aerospike](https://img.shields.io/badge/Aerospike-ED1C24?style=for-the-badge&logoColor=white)
![FoundationDB](https://img.shields.io/badge/FoundationDB-4B0082?style=for-the-badge&logoColor=white)
![LMDB](https://img.shields.io/badge/LMDB-1E90FF?style=for-the-badge&logoColor=white)
![memcached](https://img.shields.io/badge/memcached-0F7377?style=for-the-badge&logoColor=white)
![ProxySQL](https://img.shields.io/badge/ProxySQL-2E8B57?style=for-the-badge&logoColor=white)

**Infra & CI/CD**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white)

## 📊 GitHub Stats

<div align="center">

![Profile Details](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ohsono&theme=tokyonight)

![Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ohsono&theme=tokyonight)
![Most Used Languages](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ohsono&theme=tokyonight)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ohsono&hide_border=true&theme=tokyonight)

</div>

## 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ohsono/ohsono/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ohsono/ohsono/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/ohsono/ohsono/output/github-snake.svg" />
</picture>

</div>

## 🎓 Education

- **UCLA** — Master of Applied Statistics Data Science (MASDS) — *Outstanding Master's Award, 2025–26*
- **University At Buffalo** — B.S. Computer Science & Engineering

## 📄 Publication

**SYNTHONY: A Stress-Aware, Intent-Conditioned Agent for Deep Tabular Generative Models Selection**
**Hochan Son** (first author), Xiaofeng Lin, Jason Ni, Guang Cheng — ICLR 2026 DeLTA (accepted, poster)
[arXiv:2604.00293](https://arxiv.org/abs/2604.00293)
