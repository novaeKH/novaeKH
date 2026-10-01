# Hi, I'm Ilya

Applied Mathematics student at NUST MISIS, focused on Data Science and Machine Learning.

I build ML projects from data preparation and evaluation to working applications. My current interests are tabular ML, retrieval-augmented generation and language models.

Open to Data Science and Machine Learning internships and junior roles.

## Selected projects

### [Hotel Booking Cancellation](https://github.com/novaeKH/hotel-cancellation-ml)

**Predicting cancellation risk at the time a hotel booking is created.**

- Built a pipeline from data preparation and temporal validation to a FastAPI service and monitoring.
- Investigated why a LightGBM model degraded on later bookings, using distribution analysis and SHAP.
- Compared CatBoost retraining strategies, including rolling windows and recency weighting, and retained full-history retraining after the comparison.
- On the May–August monitoring period, CatBoost v2 achieved **0.685 PR-AUC** and **0.661 precision**. The 0.70 precision target remained unmet; the project documents this limitation and the recall trade-off.

`Python` · `pandas` · `scikit-learn` · `LightGBM` · `CatBoost` · `SHAP` · `FastAPI` · `Docker`

---

### [ML Vault Agent](https://github.com/novaeKH/ml-vault-agent)

**A local RAG assistant for learning Data Science and ML from an Obsidian vault.**

- Combined BM25 and embedding search with reciprocal-rank fusion and an incremental SQLite index.
- Integrated local Ollama models for generation and multilingual embeddings, with a lexical-only search fallback.
- Added tutoring, interview preparation and algorithm practice, with separate retrieval collections for exercises and solutions.
- Built a retrieval evaluation tool reporting Recall@k and MRR, plus a local learning-progress system with inspectable evidence.

The app reads the vault without modifying it. Notes, settings, indexes and learning history stay outside the application repository.

`Python` · `FastAPI` · `Ollama` · `BM25` · `Embeddings` · `SQLite` · `RAG`

---

### [DataPath](https://github.com/novaeKH/DataPath)

**A local learning app that brings DS/ML lessons, interactive explanations and practice into one place.**

A guided learning path connects lessons with SQL and Python exercises, visual ML labs and spaced repetition. Daily sessions help decide what to study next, while Focus and Atlas make it easier to revisit topics and track progress. Learning state is stored on the device.

[Open the web app](https://novaekh.github.io/DataPath/) · [Project overview](https://github.com/novaeKH/DataPath#readme)

<table>
  <tr>
    <td width="50%"><a href="https://raw.githubusercontent.com/novaeKH/DataPath/main/docs/screenshots/phase7-today-desktop.png"><img src="https://raw.githubusercontent.com/novaeKH/DataPath/main/docs/screenshots/phase7-today-desktop.png" alt="DataPath Today: daily learning session and progress" width="100%"></a></td>
    <td width="50%"><a href="https://raw.githubusercontent.com/novaeKH/DataPath/main/docs/screenshots/phase7-focus-or-lesson-dark.png"><img src="https://raw.githubusercontent.com/novaeKH/DataPath/main/docs/screenshots/phase7-focus-or-lesson-dark.png" alt="DataPath Focus: lesson view in dark mode" width="100%"></a></td>
  </tr>
  <tr>
    <td align="center">Daily learning session</td>
    <td align="center">Focused lesson view</td>
  </tr>
</table>

`React` · `TypeScript` · `Python` · `SQLite WASM` · `Pyodide` · `PWA` · `Tauri`

---

### [StoryWeaver](https://github.com/novaeKH/StoryWeaver)

**A 126M-parameter Transformer trained from scratch to generate short stories in English.**

- Implemented a decoder-only model in PyTorch with RoPE, GQA, RMSNorm, SwiGLU and KV cache.
- Prepared TinyStoriesInstruct data, trained a byte-level BPE tokenizer and built a mixed-precision training loop with validation and checkpointing.
- Built a FastAPI interface for guiding a story with a plot idea, required words and narrative features.

The model can lose character roles or long-story coherence. Model weights are not included in the repository.

<p>
  <a href="https://github.com/novaeKH/StoryWeaver">
    <img src="https://raw.githubusercontent.com/novaeKH/StoryWeaver/main/assets/storyweaver_app.png" alt="StoryWeaver interface for controlled short-story generation" width="100%">
  </a>
</p>

`Python` · `PyTorch` · `Transformers` · `Tokenizers` · `FastAPI`
