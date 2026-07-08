<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:5b21b6,100:8b5cf6&height=220&section=header&text=Rayhan%20Vora&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%2F%20Full%20Stack%20Engineer%20%7C%20Building%20Production-Grade%20GenAI%20Systems&descAlignY=58&descSize=18)

<a href="https://github.com/rehanvhora778">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=600&lines=AI+%2F+ML+Engineer;RAG+%26+LLM+Systems+Builder;Full+Stack+Developer;Turning+Ideas+Into+Shipped+Products" alt="Typing SVG" />
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-1a1a2e?style=for-the-badge&logo=github&logoColor=A78BFA)](https://github.com/rehanvhora778)

![Profile Views](https://komarev.com/ghpvc/?username=rehanvhora778&color=8b5cf6&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/rehanvhora778?style=flat-square&color=6d28d9&label=Followers)
![Stars](https://img.shields.io/github/stars/rehanvhora778?style=flat-square&color=7c3aed&label=Stars)

</div>

---

### About Me

I build full-stack AI systems end to end — from RAG pipelines and LLM agents to the React dashboards that sit on top of them. My recent work spans retrieval-augmented chatbots, an AI email copilot with real Gmail integration, a YouTube-transcript RAG assistant with quiz generation, and a transfer-learning medical imaging classifier. I care about shipping things that behave like real products: authentication, real data instead of mocks, human-in-the-loop safety on anything that sends or acts on a user's behalf, and clean API design.

**Open to:** internships and junior/mid roles in AI engineering, full-stack development, and applied ML.

---

### Tech Stack

**Languages**
![Python](https://skillicons.dev/icons?i=python) ![JavaScript](https://skillicons.dev/icons?i=js) ![TypeScript](https://skillicons.dev/icons?i=ts)

**Frontend**
![React](https://skillicons.dev/icons?i=react) ![Vite](https://skillicons.dev/icons?i=vite) ![Tailwind](https://skillicons.dev/icons?i=tailwind)

**Backend & Databases**
![Flask](https://skillicons.dev/icons?i=flask) ![Django](https://skillicons.dev/icons?i=django) ![FastAPI](https://skillicons.dev/icons?i=fastapi) ![MongoDB](https://skillicons.dev/icons?i=mongodb) ![Postgres](https://skillicons.dev/icons?i=postgres)

**AI / ML & Tooling**
![PyTorch](https://skillicons.dev/icons?i=pytorch) ![Git](https://skillicons.dev/icons?i=git) ![VSCode](https://skillicons.dev/icons?i=vscode)

---

### AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| Retrieval-Augmented Generation | Applied | LangChain chunking, FAISS vector stores, semantic retrieval grounded in source documents |
| LLM Integration | Applied | Groq (Llama 3.3, Whisper), Google Gemini, Mistral AI — text generation, embeddings, and audio transcription |
| Computer Vision | Applied | Transfer learning with ResNet18 for medical image classification |
| Agentic Workflows | Applied | Multi-step, streamed (NDJSON) agent execution with tool routing and human-in-the-loop review |
| Vector Search | Applied | FAISS indexing, Sentence-Transformers and Gemini embeddings |

---

### Featured Projects

<details>
<summary><b>🎬 yt-chat-ai — Chat with any YouTube video using GenAI</b></summary>
<br>

A full-stack RAG application that pulls a video's transcript (with an audio-transcription fallback for videos without captions), builds a FAISS vector index, and lets users ask questions, get summaries, and auto-generate quizzes from the content — in English or Hindi.

| | |
|---|---|
| **Stack** | React, Flask, LangChain, Groq, Gemini, FAISS, MongoDB Atlas |
| **Core Feature** | RAG pipeline with timestamped chunk retrieval |
| **Auth** | JWT-based registration and login |
| **Extras** | PDF/DOCX export, analytics dashboard, 5 selectable UI themes |
| **Repository** | [rehanvhora778/yt-chat-ai](https://github.com/rehanvhora778/yt-chat-ai) |

</details>

<details>
<summary><b>🤖 RAG-CHATBOT — Document-grounded AI chatbot</b></summary>
<br>

Upload PDFs, DOCX, or TXT files and chat with an AI that answers strictly from your documents, with inline citations back to the source.

| | |
|---|---|
| **Stack** | Django REST Framework, MongoDB, FAISS, Sentence-Transformers, Groq (Llama 3.3 70B), React + Vite |
| **Core Feature** | Per-user document indexing with citation-backed answers |
| **Repository** | [rehanvhora778/RAG-CHATBOT](https://github.com/rehanvhora778/RAG-CHATBOT) |

</details>

<details>
<summary><b>📬 Automated-Email-Ai — AI email copilot for Gmail</b></summary>
<br>

An AI assistant that connects to Gmail via OAuth, drafts and rewrites emails across 13 tones, runs 15 one-click writing/analysis tools, and executes natural-language agent commands — while never auto-sending without human review.

| | |
|---|---|
| **Stack** | React, TypeScript, FastAPI, Mistral AI, Gmail API, Supabase (Postgres + RLS) |
| **Core Feature** | Streamed multi-step agent mode with human-in-the-loop send approval |
| **Security** | Row-level security in Supabase, least-privilege service-role usage |
| **Repository** | [rehanvhora778/Automated-Email-Ai](https://github.com/rehanvhora778/Automated-Email-Ai) |

</details>

<details>
<summary><b>🫁 pneumonia-detection-main — Chest X-ray classifier</b></summary>
<br>

A deep-learning web app that classifies chest X-rays as Normal or Pneumonia, tuned to prioritize recall given the cost of false negatives in a medical context.

| | |
|---|---|
| **Stack** | Python, PyTorch (ResNet18 transfer learning), Streamlit |
| **Core Feature** | End-to-end pipeline — preprocessing, training, evaluation, deployment |
| **Repository** | [rehanvhora778/pneumonia-detection-main](https://github.com/rehanvhora778/pneumonia-detection-main) |

</details>

<details>
<summary><b>📄 bibtex-extraction — Automated bibliography generation</b></summary>
<br>

A Python tool that scans a folder of PDFs and generates a clean BibTeX bibliography (title, author, year, DOI) without manual entry or external APIs.

| | |
|---|---|
| **Stack** | Python |
| **Repository** | [rehanvhora778/bibtex-extraction](https://github.com/rehanvhora778/bibtex-extraction) |

</details>

---

### GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rehanvhora778&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=8b5cf6&text_color=c9d1d9" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=rehanvhora778&theme=tokyonight&hide_border=true&background=0d1117&ring=8b5cf6&fire=a78bfa&currStreakLabel=a78bfa" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rehanvhora778&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9" width="49%" />

</div>

### GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=rehanvhora778&theme=algolia&no-frame=true&column=4&margin-w=8&margin-h=8" />

</div>

### Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rehanvhora778&theme=react-dark&hide_border=true&bg_color=0d1117&color=a78bfa&line=8b5cf6&point=ffffff" width="100%" />

</div>

### Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/rehanvhora778/rehanvhora778/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

---

### Current Focus

```yaml
learning:
  - Advanced agentic AI workflows and tool-calling patterns
  - Vector database optimization at scale
building:
  - Production-quality full-stack AI applications
  - Cleaner API and system design practices
exploring:
  - Multi-agent orchestration
  - Model evaluation and observability
open_to:
  - AI/ML engineering internships and roles
  - Full-stack engineering opportunities
```

---

### Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/-Email-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/-GitHub-1a1a2e?style=for-the-badge&logo=github&logoColor=A78BFA)](https://github.com/rehanvhora778)
[![Portfolio](https://img.shields.io/badge/-Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](#)

</div>

---

<div align="center">

*Building systems that think, retrieve, and respond — one commit at a time.*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,100:1a1a2e&height=120&section=footer)

</div>
