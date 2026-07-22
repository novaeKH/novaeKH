# Hi, I'm Ilya 👋

Applied Mathematics student at NUST MISIS, focused on Data Science and Machine Learning.

I build end-to-end ML projects — from data validation and leakage-safe evaluation to modeling, interpretation and deployment. My current focus is tabular ML, NLP and practical ML systems.

I am looking for a Data Science or Machine Learning internship or junior position.

## Skills & Tools

### Machine Learning & Data

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="28" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" height="28" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" height="28" alt="NumPy">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" height="28" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black" height="28" alt="CatBoost">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" height="28" alt="PyTorch">
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" height="28" alt="Transformers">
</p>

### Engineering

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" height="28" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" height="28" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" height="28" alt="Redis">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" height="28" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" height="28" alt="Git">
</p>

## Featured Projects

### [ROGII — Wellbore Geology Prediction](https://github.com/novaeKH/rogii-wellbore-prediction)

Regression project for predicting TVT along hidden segments of horizontal well trajectories.

- Designed leakage-safe validation by complete wells, with a separate spatial guardrail for geographic shift.
- Engineered 32 fold-safe spatial features by reconstructing six geological surfaces with IDW interpolation.
- Combined four CatBoost regressors with distance-aware fallback and boundary correction.
- Improved Public Leaderboard RMSE from **13.608** to **11.670** — a **14.2%** reduction.

`Python` `Pandas` `CatBoost` `Feature Engineering` `Group CV` `Spatial Validation`

---

### [Bank Marketing Prioritization](https://github.com/novaeKH/bank-marketing-prioritization)

Binary classification and ranking project for prioritizing clients under a 10% outbound-call budget.

- Removed post-call data leakage and used temporal folds to evaluate performance on future campaigns.
- Compared linear and tree-based models, selecting Logistic Regression for its stability across time.
- Achieved **AP 0.530**, **ROC-AUC 0.745** and **Lift@10% 1.91** on the final period.
- Explained the ranking with permutation importance and model coefficients.

`Python` `Pandas` `Scikit-learn` `Temporal Validation` `Ranking Metrics` `Model Interpretation`

---

### [Banking Intent Classifier](https://github.com/novaeKH/banking-intent-classifier)

Multiclass NLP project for routing customer requests across 77 banking intents.

- Built a shared leakage-safe evaluation pipeline with fixed splits and macro F1.
- Compared TF-IDF with Logistic Regression, a custom Transformer Encoder implemented in PyTorch and fine-tuned DistilBERT.
- DistilBERT reached **0.882 validation macro F1** and **0.886 official test macro F1**; TF-IDF remained a strong baseline at **0.861**.

`Python` `Scikit-learn` `PyTorch` `NLP` `Transformers` `DistilBERT`

---

### [StoryWeaver — 126M Story Generation Model](https://github.com/novaeKH/StoryWeaver)

GPT-style language model trained from scratch for controllable short-story generation.

- Implemented a 126M-parameter decoder-only Transformer in PyTorch with RoPE, GQA, RMSNorm, SwiGLU and KV cache.
- Built the byte-level BPE tokenizer, data pipeline and mixed-precision training loop with gradient accumulation, validation and checkpointing.
- Added a FastAPI web application for steering generation with a summary, required words, story opening and narrative features.

<p align="center">
  <a href="https://github.com/novaeKH/StoryWeaver">
    <img src="https://raw.githubusercontent.com/novaeKH/StoryWeaver/main/assets/storyweaver_app.png" alt="StoryWeaver story generation interface" width="85%">
  </a>
</p>

`Python` `PyTorch` `Transformer` `Tokenizers` `FastAPI` `Generative NLP`

---

### [Takt AI Control Center](https://github.com/novaeKH/takt-ai-control-center)

AI Observability, FinOps and Governance platform for operating AI products and agents.

- Built an AI registry and telemetry pipeline for agent runs, LLM calls, tool calls and business outcomes.
- Implemented token-cost accounting, budgets, ROI and waste metrics, policy violations, audit history and role-based access.
- Exposed a REST ingestion API and Python SDK, with FastAPI, PostgreSQL, Redis and React services packaged through Docker Compose.

<p align="center">
  <a href="https://github.com/novaeKH/takt-ai-control-center">
    <img src="./assets/takt-overview.png" alt="Takt AI Control Center dashboard" width="85%">
  </a>
</p>

`FastAPI` `PostgreSQL` `Redis` `React` `Docker Compose` `REST API`
