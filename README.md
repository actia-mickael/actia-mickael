# Bonjour, je suis Mickael Moisan 👋

## AI Architect / Data Scientist | Partenaire des PME bretonnes et un peu plus

🎯 **Consultant indépendant** — Ex-Directeur Technique de l'industrie manufacturière,
spécialisé en Intelligence Artificielle, Data Science et applications web métier
adaptées aux PME et TPE.

📍 Bretagne, France | 🏢 [ACT-IA](https://www.act-ia.fr)

---

### 💼 Expertise

- **27 ans d'expérience industrielle** (ex-Directeur Technique)
- Architecture IA & Data Engineering (formation Jedha)
- Applications web métier full-stack, de la conception au déploiement
- Machine Learning & Deep Learning
- RAG, agents LLM & Fine-tuning
- MLOps (MLflow, Docker, suivi d'expériences)
- Big Data (PySpark, Databricks)
- Déploiement sur mesure, compatible avec votre environnement IT

---

### 🏗️ Architecture de référence

Mon socle éprouvé pour les applications métier : **full-stack async, containerisé,
testé, portable** — pensé pour tourner aussi bien sur un serveur PME que dans le cloud.

```
┌─────────────────┐     ┌──────────────────┐     ┌─────────────────┐
│  React 18 + Vite│────▶│  FastAPI (async) │────▶│  PostgreSQL 16  │
│  TypeScript     │ HTTP│  SQLAlchemy 2.0  │ SQL │  + pgvector     │
│  Tailwind CSS   │◀────│  Pydantic v2     │◀────│  (embeddings)   │
└─────────────────┘     └──────────────────┘     └─────────────────┘
        │                        │                         │
        └────────────────────────┴─────────────────────────┘
                    Docker Compose · Alembic · pytest
                    Couche IA : SDK Anthropic · RAG · LangGraph
```

- **Backend** : Python 3.12, FastAPI + Uvicorn, SQLAlchemy 2.0 async, Alembic
  (migrations), Pydantic v2, `structlog`, packaging `uv` / `pyproject.toml`
- **Frontend** : React 18/19, Vite, TypeScript strict, Tailwind, Zustand, Axios
- **Data** : PostgreSQL 16 / pgvector, JSONB, migrations versionnées
- **Qualité** : `ruff`, `pytest` + `pytest-asyncio`, isolation par transaction
- **Déploiement** : Docker Compose multi-services, multi-stage `base → dev → prod`

---

### 🚀 Projets phares

- **Veille stratégique IA** *(client)* — SaaS de veille automatisée : RAG sur
  `pgvector` + `sentence-transformers`, synthèse LLM (Claude Haiku/Sonnet),
  recherche web (Tavily), génération de rapports PDF. Stack FastAPI + React/TS.
- **Optimisation logistique 3D** *(client)* — Moteur de bin-packing pour
  containers : heuristiques géométriques (`trimesh`, `numba`, OR-Tools CP-SAT),
  visualisation temps réel Three.js / react-three-fiber.
- **Aide à la décision boursière** *(perso)* — Système décisionnel hybride
  quant + LLM (aucune exécution de trade). Cœur prédictif : **4 modèles
  LightGBM calibrés** (prix, géométrie de bougie, fondamentaux SEC
  point-in-time) empilés par un **méta-modèle de stacking**, évalués en
  **walk-forward purgé** (embargo, holdout gelé, anti-fuite). Couche
  qualitative : **débat multi-agents haussier/baissier arbitré par un juge**
  (LLM en mode *thinking* via SDK Anthropic), orchestré par un graphe
  **LangGraph** à escalade conditionnelle, avec ancrage anti-hallucination
  (chaque argument doit citer sa source). Un module de **fusion** combine
  signaux quantitatifs et qualitatifs (détection concordance / divergence) et
  un **score d'opportunité** pondère modèle, sentiment, potentiel analystes et
  smart money. Le tout adossé à une **gestion du risque déterministe**
  (dimensionnement ATR, stop-loss et trailing Chandelier, surveillance en
  alerte), un **journal de signaux à boucle fermée** (mesure a posteriori,
  intervalles de Wilson), backtest anti-look-ahead, paper trading, surveillance
  intraday temps réel (WebSocket) et clustering de co-mouvement HRP.
  Environnement de recherche MLflow + Optuna + JupyterLab.
- **Prédiction de ventes ML** *(perso)* — Pipeline gradient boosting
  (XGBoost / LightGBM / CatBoost), app Gradio déployée sur HuggingFace Spaces.

---

### 🤖 Spécialiste Claude Code

J'utilise **Claude Code** au quotidien comme partenaire d'ingénierie : mise en
place de workspaces structurés (charte de stack, contextes hiérarchiques
`CLAUDE.md`), orchestration multi-agents, skills et slash commands sur mesure,
automatisation du workflow Git/PR. J'accompagne les équipes qui veulent intégrer
un assistant de code IA dans leur flux de développement.

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_SDK-191919?style=flat&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)

---

### 🛠️ Stack technique

**Langages & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white)

**IA / Data Science**

![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat&logo=xgboost&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat&logo=lightning&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FBBF24?style=flat&logo=v&logoColor=black)

**MLOps / Big Data**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2E4B9B?style=flat&logo=optuna&logoColor=white)
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)

**Infra & Data**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

---

### 📫 Me contacter

- 💼 [LinkedIn](https://www.linkedin.com/in/mickael-moisan-42605774/)
- 🌐 [act-ia.fr](https://www.act-ia.fr)
- 📧 mickael.moisan@act-ia.fr
