<div align="center">

# Misba Saiyed

**I build software around AI models, with Python and backend engineering at the core.**

BCA Honours · AI & ML major · Gujarat University (2023–2027)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Misba_Saiyed-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/misba-saiyed-954882392/)
[![Email](https://img.shields.io/badge/Email-misbasaiyed20@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:misbasaiyed20@gmail.com)
[![HydroLens demo](https://img.shields.io/badge/Live_demo-HydroLens-000000?style=flat-square&logo=vercel&logoColor=white)](https://hydrolens-silk.vercel.app)

</div>

---

## What I build

Calling a model is the easy part. I'm more interested in the system around it: validating what it returns, combining it with other evidence, storing it properly, and keeping a human in the loop where it matters.

| | |
|---|---|
| **Backend APIs** | FastAPI services on PostgreSQL, with SQLAlchemy models and Alembic migrations |
| **LLM & multimodal integration** | Gemini for image analysis and entity extraction, with schema-validated output |
| **Retrieval** | Document chunking, embeddings, ChromaDB vector search, RAG |
| **Reliability** | Explainable confidence scoring, human verification, audit trails, tests with mocked AI responses |

I'm early in my career. My projects are personal and academic builds, and each README states what is implemented and what is not.

---

## Featured projects

### 1 · HydroLens
*A single photo is noisy evidence. What do several observations support together?*

Citizens submit geo-tagged photos of water bodies. Gemini vision extracts visible indicators (turbidity, algae, visible waste, colour anomalies). The backend then compares them with nearby, recent and historical reports and produces a confidence score. A reviewer verifies or rejects each observation, and every decision is logged.

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `Next.js` `TypeScript` `Gemini API`

[Repository](https://github.com/misbahsaiyed20/HydroLens) · [Live demo](https://hydrolens-silk.vercel.app)

**Engineering highlight:** confidence is a deterministic, weighted and explainable score (corroboration, recency, geographic consistency, baseline deviation and more), with a conflict rule so strong disagreement is never averaged away. It uses a pretrained model through an API and makes no claims about water quality, medical diagnosis or outbreaks.

---

### 2 · MemoryVerse AI
*Certificates, resumes and project reports are scattered. Can they become one searchable record?*

Built for the MemoryVerse AI '26 Hackathon. Uploaded documents go through text extraction and chunking, Gemini extracts entities and relationships into a PostgreSQL knowledge graph, and chunk embeddings go into ChromaDB. A RAG assistant answers questions from the user's own documents.

`Python` `FastAPI` `PostgreSQL` `ChromaDB` `Gemini API` `Next.js` `TypeScript` `Firebase Auth`

[Repository](https://github.com/misbahsaiyed20/memoryverse-ai)

**Engineering highlight:** combines a relational knowledge graph with vector retrieval, so questions can be answered from both structure and semantic similarity.

---

### 3 · Webpage Summarizer
*Summarize the page you are reading without leaving it.*

A browser extension that sends page content to a Python backend, which calls the Gemini API and returns a summary.

`JavaScript` `Python` `Gemini API`

[Repository](https://github.com/misbahsaiyed20/webpage-summarizer)

**Engineering highlight:** the API key stays on the backend, so the extension never ships a secret.

---

## Stack

| | |
|---|---|
| **Languages** | Python · TypeScript · JavaScript |
| **Backend** | FastAPI · Django · SQLAlchemy · Pydantic · Alembic |
| **AI** | Gemini API · RAG · embeddings · ChromaDB |
| **Data** | PostgreSQL · SQLite |
| **Frontend** | Next.js · React · Tailwind CSS |
| **Workflow** | Git · pytest · Docker |

---

## Current focus

- Strengthening machine learning fundamentals alongside my coursework
- Turning LLM capabilities into reliable, testable backend systems
- RAG: retrieval quality and evaluation, not just getting it to run
- System design, Docker and CI/CD

---

## Contact

Looking for AI/ML and backend internship opportunities.
[LinkedIn](https://www.linkedin.com/in/misba-saiyed-954882392/) · [Email](mailto:misbasaiyed20@gmail.com)
