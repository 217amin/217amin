# Hi, I'm Amin Lasri

**AI Engineer — Search, NLP, RAG**

I build retrieval systems that work in production: hybrid search pipelines, re-ranking systems, and RAG architectures evaluated with real metrics.

Background: 8 years as an economics teacher. I bring the same discipline to ML that I brought to the classroom — precise reasoning, clear communication, and an obsession with understanding *why* something works, not just *that* it works.

---

## Featured Projects

### [amazon-esci-search](https://github.com/217amin/amazon-esci-search) — Two-Stage E-commerce Search Engine
Production-style hybrid retrieval on the Amazon ESCI dataset. Matryoshka fine-tuning compresses embeddings to 64 dims while recovering recall from 0.43 → 0.81. Hybrid pipeline (BGE + SPLADE + BM25 + RRF) + Cross-Encoder reranking achieves **nDCG@20 = 0.54** on consumer hardware.

`dense retrieval` `SPLADE` `BM25` `Matryoshka` `FAISS` `MNRL` `MLflow`

---

### [aegis-rag](https://github.com/217amin/aegis-rag) — Production RAG with Safe Abstention
Retrieval-first RAG for policy-heavy PDF corpora. Hybrid BM25 + dense retrieval + RRF + reranking. **Recall@5 = 0.85, nDCG@5 = 0.80.** Includes profile-based A/B testing, RAGAS evaluation, failure mode analysis, and a confidence-gated abstention mechanism.

`RAG` `hybrid retrieval` `LangChain` `RAGAS` `cross-encoder` `Chroma` `abstention`

---

### [House-Price-Prediction](https://github.com/217amin/House-Price-Prediction) — End-to-End ML Pipeline
Regression, classification, and unsupervised market segmentation on 80+ feature real-estate data. Tuned CatBoost/XGBoost: **R² = 0.92**. UMAP + HDBSCAN for non-linear property clustering.

`scikit-learn` `XGBoost` `CatBoost` `UMAP` `HDBSCAN`

---

## Skills

| Area | Tools |
|---|---|
| Information Retrieval | BM25, SPLADE, FAISS, dense bi-encoders, cross-encoders, RRF |
| NLP / Embeddings | sentence-transformers, Matryoshka, MNRL, BGE, E5 |
| RAG Systems | LangChain, Chroma, RAGAS, semantic chunking, abstention |
| ML Engineering | scikit-learn, XGBoost, LightGBM, CatBoost, UMAP, HDBSCAN |
| Experiment Tracking | MLflow, DagsHub |
| Languages | Python, SQL |

---

## Currently Working On

- Live demo for amazon-esci-search (Streamlit + Hugging Face Spaces)
- EdTech NLP project combining domain expertise with retrieval

---

📍 Ottawa, Canada &nbsp;|&nbsp; [aminanalyst.com](http://aminanalyst.com) &nbsp;|&nbsp; [LinkedIn](https://linkedin.com/in/amin-lasri)
