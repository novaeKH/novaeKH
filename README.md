# Hi, I'm Ilya 👋

Applied Mathematics student at NUST MISIS, focused on Data Science and Machine Learning.

I build ML projects from data validation and leakage-safe evaluation to modeling and interpretation. My current focus is tabular ML, NLP and practical ML systems.

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

Regression project for predicting TVT along hidden segments of well trajectories.

- Built leakage-safe validation by complete wells and separate spatial clusters.
- Reconstructed six train-only geological surfaces with fold-safe IDW interpolation, expanding the feature set from 80 to 112.
- Combined four CatBoost regressors with a distance guard and boundary anchor correction.
- Improved Public Leaderboard RMSE from **13.608** to **11.670** — a **14.2%** reduction.

`Python` `Pandas` `Scikit-learn` `CatBoost` `Feature Engineering` `Group CV`

---

### [Bank Marketing Prioritization](https://github.com/novaeKH/bank-marketing-prioritization)

Binary classification project for prioritizing clients within a limited outbound-call budget.

- Used the full UCI Bank Marketing dataset with 41,188 observations.
- Removed post-call data leakage and validated models with a temporal split.
- Selected the top 10% of clients instead of relying on a fixed classification threshold.
- Achieved **AP 0.530**, **ROC-AUC 0.745** and **Lift@10% 1.91** on the final period.
- Interpreted predictions with permutation importance and Logistic Regression coefficients.

`Python` `Pandas` `Scikit-learn` `Binary Classification` `Model Interpretation`

---

### [Banking Intent Classifier](https://github.com/novaeKH/banking-intent-classifier)

Multiclass NLP project for classifying customer requests into 77 banking intents.

- Compared TF-IDF with Logistic Regression, a custom Transformer Encoder and fine-tuned DistilBERT.
- DistilBERT achieved the best validation macro F1 of **0.882**.
- TF-IDF remained a strong and efficient baseline with macro F1 of **0.861**.

`Python` `Scikit-learn` `PyTorch` `Transformers` `DistilBERT`

---

### [Takt AI Control Center](https://github.com/novaeKH/takt-ai-control-center)

AI Observability, FinOps and Governance platform for monitoring AI products and agents.

- Tracks token usage, cost, quality and operational status of AI systems.
- Provides centralized monitoring, policy controls and audit history.

<p align="center">
  <a href="https://github.com/novaeKH/takt-ai-control-center">
    <img src="./assets/takt-overview.png" alt="Takt AI Control Center dashboard" width="85%">
  </a>
</p>

`FastAPI` `PostgreSQL` `Redis` `Docker`
