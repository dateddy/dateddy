<div align="center">

# Vũ Thành Đạt

**AI Engineer · Vietnamese NLP · RAG and multimodal systems**

Final-year AI/CS student at Ton Duc Thang University · Ho Chi Minh City, Vietnam

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vu-dat-76467b40b/)
[![Email](https://img.shields.io/badge/datvu107@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:datvu107@gmail.com)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/datvu107-dateddy)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/dateddy)
![Open to work](https://img.shields.io/badge/Open%20to-AI%20Engineer%20roles-2EA44F?style=flat-square)

</div>

---

### About

- Final-year AI/CS student at **Ton Duc Thang University (TDTU)**, graduating early 2027
- Member of the **NLP-KD Lab** — Vietnamese NLP, trustworthy RAG, multimodal misinformation detection
- I care about systems that are measured, reproducible, and deployed: every number backed by a script, every project with tests or a live demo
- Looking for **AI Engineer** roles — LLM applications, retrieval pipelines, applied NLP

---

### Featured projects

#### [ViMed-RAG](https://github.com/dateddy/vimed-rag) — trustworthy Vietnamese medical QA &nbsp; [![Demo](https://img.shields.io/badge/Live%20demo-HF%20Spaces-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/datvu107-dateddy/vimed)

Corrective RAG with source citations and **calibrated abstention** for cardiology and diabetes questions — the system declines when its evidence is too weak instead of answering confidently.

- **Faithfulness 0.747 vs 0.481** for an LLM-only baseline (RAGAS, paired sign test, p = 0.0042)
- **2.4× cheaper** per 1,000 queries than LLM-only
- Policy gate, LOOCV-calibrated reranker thresholds, single-rewrite loop with a guard against verdict flipping
- Plain-Python orchestration with dependency injection — **590 tests** run in ~3.5 s with no GPU or API key

`bge-m3` `bge-reranker-v2-m3` `Qdrant` `Gemini 2.5 Flash` `RAGAS` `Streamlit` `Docker`

#### [TMD — Tri-Modal Detection](https://github.com/dateddy/mm_detect) — misinformation in Vietnamese Facebook ads

Deep learning system that jointly encodes ad **text**, **image**, and **advertiser behavior** to flag misleading ads.

- PhoBERT + ViT-B/16 + behavioral-metadata MLP, fused with dual bidirectional cross-attention and input-conditioned gating
- InfoNCE contrastive auxiliary loss and modality dropout for robustness to missing inputs
- Page-level data splits to prevent leakage; full ablation suite over modalities, fusion, features, and fine-tuning strategy
- Written up as an IEEE-format paper

`PyTorch` `Transformers` `PhoBERT` `ViT` `timm` `scikit-learn`

#### [HoldNote](https://github.com/dateddy/holdnote) — hand-journal web app for poker players

Consumer PWA: log a hand in under 30 seconds, get an AI review, and track recurring mistakes across sessions.

- TypeScript monorepo: Next.js app plus a pure, fully tested game-logic package
- Supabase backend with row-level-security tests; Vitest, ESLint, and Prettier in CI
- Building toward a public launch for users in Vietnam and Asia

`Next.js` `TypeScript` `Tailwind` `Supabase` `Vitest` `pnpm`

---

### Tech stack

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**ML / DL** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![QLoRA](https://img.shields.io/badge/QLoRA%20%2F%20PEFT-555555?style=flat-square)

**LLM / RAG** &nbsp;
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-555555?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-555555?style=flat-square)

**Apps / Infra** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<div align="center">

**Let's talk** — [datvu107@gmail.com](mailto:datvu107@gmail.com) · [LinkedIn](https://www.linkedin.com/in/vu-dat-76467b40b/)

</div>
