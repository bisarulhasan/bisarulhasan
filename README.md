<!-- Profile README: github.com/bisarulhasan -->
<h1 align="center">Bisar Ul Hasan</h1>

<p align="center">
  <strong>Agentic AI · AI Engineer · LLM Ops</strong>
  <br>
  <sub>6+ years across the AI and data stack</sub>
</p>

<p align="center">
  <a href="https://www.bisarhasan.com">Website</a> ·
  <a href="https://www.linkedin.com/in/bisarhasan">LinkedIn</a> ·
  <a href="mailto:bisar1000@gmail.com">Email</a>
</p>

---

I started as a founding engineer at a 3-person speech-AI startup that scaled to 52 people, where I led the dataset and TTS-training pipelines. Today I design and ship LLM-powered RAG and multi-agent systems. Most of my work lives in private and company repos, so Noor below is the public, fully documented reference for how I build.

- **Now:** building context-aware automation and GenAI applications, and driving AI adoption inside a school.
- **Focus:** RAG pipelines · agentic workflows · tool use / MCP · LLM evaluation and observability.

## Featured project

### [Noor — Production-Grade RAG Assistant](https://github.com/bisarulhasan/teaching-assistant-bot) &nbsp;·&nbsp; [Live demo →](https://wgs-noor.vercel.app)

A teaching assistant that answers students strictly from their own textbooks, so every answer is grounded and citable.

- **Hybrid retrieval** — BM25 + dense vectors fused with Reciprocal Rank Fusion, then **Cohere cross-encoder reranking**.
- **Two-stage citation enforcement** — declines to answer when the context doesn't support a grounded response.
- **Per-student scoping** — filters the corpus by year / subject / course.
- **Evaluation-gated CI** — RAGAS + a deterministic golden-set harness run on every merge via GitHub Actions.

> `RAGAS faithfulness 0.94 · context precision 0.98 · answer relevancy 0.85`
>
> Next.js · FastAPI · Qdrant · FastEmbed · Cohere · OpenRouter · RAGAS · GitHub Actions

## Selected work

Production and client work in private and company repos, described at a high level.

- **PlotKhata** — multi-tenant housing-society management SaaS, shipped live. Shared-schema multi-tenancy with row-level security, an immutable audit log, segregation of duties, and a buyer portal. Postgres on Neon, Next.js on Vercel.
- **Model-alignment pipelines** — two pipelines built with supervised fine-tuning and Direct Preference Optimization (DPO) to align model outputs to preferred responses.

## Research &amp; academic projects

- **State-of-the-Art TTS &amp; Voice-Cloning Attack Detection** — a literature review of modern text-to-speech and voice-cloning technologies and the automated methods for detecting synthetic-speech (deepfake) attacks: MOS / vMOS quality assessment, higher-order spectral analysis, and vocal-tract reconstruction. Macquarie University, COMP 8851. **[Read the report (PDF) →](https://github.com/bisarulhasan/bisarulhasan/blob/main/research/tts-voice-cloning-attack-detection.pdf)**
- **[Bayesian Logistic Regression &amp; Multivariate Analysis — Diabetes Prediction](https://www.linkedin.com/in/bisarhasan/details/projects/)** — modelled diabetes risk using Bayesian logistic regression and multivariate statistical analysis.
- **[Knowledge Graphs to Analyse a Twitter Dataset](https://www.linkedin.com/in/bisarhasan/details/projects/)** — built knowledge graphs over a large Twitter dataset using big-data technologies.

## Tech I work with

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**GenAI &amp; Agentic** — RAG · Agentic Workflows · Tool Use / Function Calling · MCP · Structured Outputs · LLM Fine-Tuning · Preference Alignment (DPO) · LLM Evaluation · Prompt &amp; Context Engineering

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Retrieval &amp; Backend**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Deployment &amp; MLOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<p align="center">
  <a href="https://www.bisarhasan.com"><img src="https://img.shields.io/badge/Website-bisarhasan.com-111?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/bisarhasan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/bisarulhasan"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white"></a>
  <a href="mailto:bisar1000@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
</p>
