<div align="center">

<h1>Misba Saiyed</h1>

<p><b>AI/ML + Python backend, built one system at a time.</b></p>

<a href="https://github.com/misbahsaiyed20">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=1200&color=2E9EF7&center=true&vCenter=true&width=720&height=40&lines=AI%2FML+%2B+Python+backend+engineering;Building+AI+systems+with+FastAPI+and+Next.js;Integrating+Gemini+into+reliable+backend+workflows;Learning+by+building+real+systems" alt="Typing animation: AI/ML and Python backend engineering" />
</a>

<p>BCA Honours &middot; AI &amp; ML major &middot; Gujarat University &middot; 4th year (2023&ndash;2027)</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Misba_Saiyed-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/misba-saiyed-954882392/)
[![Email](https://img.shields.io/badge/Email-misbasaiyed20@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:misbasaiyed20@gmail.com)
[![Live demo](https://img.shields.io/badge/Live_demo-HydroLens-000000?style=flat-square&logo=vercel&logoColor=white)](https://hydrolens-silk.vercel.app)
![Status](https://img.shields.io/badge/Open_to-AI%2FML_%26_backend_internships-2E9EF7?style=flat-square)

</div>

<br/>

I learn by building, and I like systems that show their evidence and admit their limits. That's why HydroLens ships with a limitations section, and why I care more about what happens *around* a model than about the model call itself.

<p align="center">
  <code>input &rarr; model &rarr; validation &rarr; evidence &rarr; confidence &rarr; human review</code>
</p>

---

## What I build

<table>
<tr>
<td width="25%" valign="top">

**Applied AI**

Gemini vision and extraction wired into real workflows, with schema-validated output.

</td>
<td width="25%" valign="top">

**Backend systems**

FastAPI and Django services, REST APIs, PostgreSQL, SQLAlchemy and Alembic migrations.

</td>
<td width="25%" valign="top">

**LLM applications**

Chunking, embeddings, ChromaDB and RAG over a user's own documents.

</td>
<td width="25%" valign="top">

**Reliability**

Explainable confidence scoring, human verification, audit trails, tests with mocked AI responses.

</td>
</tr>
</table>

---

## Selected work

<table>
<tr>
<td>

### HydroLens
**Water-body photos are noisy evidence. What do several observations support together?**

Citizens submit geo-tagged photos. Gemini vision extracts visible indicators (turbidity, algae, visible waste, colour anomalies). The backend compares them with nearby, recent and historical reports and produces a confidence score, then a reviewer verifies or rejects each observation with an audit trail.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Engineering highlight:** confidence is a deterministic, weighted, explainable score (corroboration, recency, geographic consistency, baseline deviation and more) with a conflict rule so strong disagreement isn't averaged away. It integrates a pretrained multimodal model through an API; I did not train a model. It makes no claims about water quality, diagnosis or outbreaks.

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/misbahsaiyed20/HydroLens)
[![Live demo](https://img.shields.io/badge/Live_demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://hydrolens-silk.vercel.app)

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### MemoryVerse AI
**Certificates, resumes and reports end up scattered. Can they become one searchable record?**

Hackathon build (MemoryVerse AI '26). Uploaded documents are extracted and chunked, Gemini extracts entities and relationships into a PostgreSQL knowledge graph, embeddings go into ChromaDB, and a RAG assistant answers from the user's own documents.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)

**Highlight:** a relational knowledge graph combined with vector retrieval. Cloud deployment and OCR are documented as future work.

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/misbahsaiyed20/memoryverse-ai)

</td>
<td width="50%" valign="top">

### Webpage Summarizer
**Summarize the page you're reading without leaving it.**

A browser extension that sends page content to a Python backend, which calls the Gemini API and returns the summary.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Highlight:** the API key lives on the backend, so the extension never ships a secret.

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/misbahsaiyed20/webpage-summarizer)

</td>
</tr>
</table>

---

## Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,postgres,nextjs,ts,js,react,tailwind,git&perline=10" alt="Python, FastAPI, Django, PostgreSQL, Next.js, TypeScript, JavaScript, React, Tailwind CSS, Git" />
</p>

<p align="center">
  <sub><b>Backend</b> FastAPI &middot; Django &middot; SQLAlchemy &middot; Pydantic &middot; Alembic &nbsp;|&nbsp; <b>AI</b> Gemini API &middot; RAG &middot; embeddings &middot; ChromaDB &nbsp;|&nbsp; <b>Data</b> PostgreSQL &middot; SQLite</sub>
</p>

---

## Now

<table>
<tr>
<td width="33%" valign="top">

**Machine learning fundamentals**

Strengthening the theory behind my AI &amp; ML major, alongside the applied work.

</td>
<td width="33%" valign="top">

**Reliable LLM systems**

Retrieval quality, evaluation, and turning model output into testable backend behaviour.

</td>
<td width="33%" valign="top">

**Shipping habits**

System design, Docker and CI/CD.

</td>
</tr>
</table>

---

## Activity

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com/?user=misbahsaiyed20&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub streak" />
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=misbahsaiyed20&layout=compact&langs_count=6&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/misbahsaiyed20/misbahsaiyed20/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/misbahsaiyed20/misbahsaiyed20/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/misbahsaiyed20/misbahsaiyed20/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</p>

---

## Connect

If you build AI or backend products and take interns, I'd like to hear from you.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Misba_Saiyed-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/misba-saiyed-954882392/)
[![Email](https://img.shields.io/badge/Email-misbasaiyed20@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:misbasaiyed20@gmail.com)
