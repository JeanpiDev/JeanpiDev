<!-- ────────────────────────────────────────────────────────────────
     Perfil de GitHub de Jean Pierre Ramírez  ·  github.com/JeanpiDev
     Este archivo es el README del repo especial JeanpiDev/JeanpiDev.
     Marca "Editorial Terminal": espresso + crema + ámbar (#e6a94c).
     Mantener coherente con el portafolio (jeanpi-ramirez.vercel.app).
──────────────────────────────────────────────────────────────── -->

<!-- HEADER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:d98b2b,100:e6a94c&fontColor=0d0b0a&text=Jean%20Pierre%20Ram%C3%ADrez&desc=Software%20Engineer%20%C2%B7%20AI-driven%20web%20development&fontSize=42&fontAlignY=40&descSize=17&descAlignY=62&animation=fadeIn" alt="Jean Pierre Ramírez — Software Engineer" />

<!-- INTRO / TERMINAL -->
```bash
visitor@jean:~$ whoami
```

**Software Engineer** 🇨🇴 — I build modern web applications and integrate **AI that solves real problems**.

- 💻 Backend with **Python / FastAPI** (SQLAlchemy, gRPC) and **NestJS**, plus a solid frontend (Angular · Next.js · React).
- 🤖 What sets me apart: I ship **AI in production** — multi-provider LLMs with fallback (Claude, OpenAI, DeepSeek), RAG and prompt-injection defense.
- 🎯 Open to **full-time remote** opportunities (LatAm / US).
- 🎮 Off the keyboard: video games, Rubik's cubes and reading.

<br>

<!-- ASSISTANT — el diferenciador, al frente del embudo -->
## 🤖 Talk to my portfolio

My site has an **AI assistant (Claude)** grounded in my profile: ask it anything about my experience,
stack or projects and it answers in real time. It includes a one-click **recruiter mode** that generates
a ready-to-share pitch.

**→ [Try it live](https://jeanpi-ramirez.vercel.app/en/) · [Versión en español](https://jeanpi-ramirez.vercel.app/es/)**

<br>

<!-- FEATURED PROJECTS -->
## 🚀 Featured projects

**🎧 Contact Center AI Analyzer** &nbsp;·&nbsp; <sub><i>professional work / private</i></sub>

Platform that analyzes contact center interactions (audio, video and documents) and automatically
generates Word reports with **Claude** (using prompt caching). Real-time job queue over WebSockets,
cached automated transcription, admin panel with RBAC and usage metrics, and security hardening
(nonce-based CSP, rate limiting, audit log).

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

<br>

**🚗 Vehicle loan platform** &nbsp;·&nbsp; <sub><i>professional work / private</i></sub>

Production system for loan applications: public application form, role-based panel, loan simulator
validated with amortization tests, a **gRPC** microservice for a ~13,500-vehicle catalog,
**AI financial analysis** (multi-provider with fallback, live progress over SSE and cost tracking),
e-signature with webhooks and PDF generation with jsreport.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)
![JavaScript](https://img.shields.io/badge/Web_Components-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

<br>

**🔒 [local-ai-gateway](https://github.com/JeanpiDev/local-ai-gateway)**

Self-hosted local AI (Ollama + Open WebUI) behind an OpenAI-compatible API gateway: per-user API keys,
**layered prompt-injection defense** (heuristics, llm-guard, Prompt Guard 2 and an output guard) and
concurrency control that returns `429` under load — so sensitive data never leaves the server.

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

<br>

**🧱 [Clean Architecture inventory + RAG agent](https://github.com/JeanpiDev/clean-architecture-inventory-rag)**

Full-stack app for companies, products and inventory built with **Clean Architecture** (pure domain packaged
with Poetry), FastAPI microservices for PDF/email and AI, a **RAG agent** with pgvector + LangChain + Claude,
JWT roles, Argon2 and a hash-chain audit log. Lighthouse 99/98/96/100 and a passing SonarQube Quality Gate.

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

<br>

**🎙️ [sonix-transcription-bot](https://github.com/JeanpiDev/sonix-transcription-bot)**

Selenium + FastAPI bot that bulk-uploads audio/video to Sonix.ai, polls transcription status and
downloads the results, with content-hash caching.

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

<br>

<!-- SKILLS — mismo orden que el portafolio -->
## 🛠️ Stack & Skills

**Frontend**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)

**AI & Productivity**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Tools & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

<br>

<!-- STATS — recoloreadas a la marca (ámbar sobre espresso) -->
## 📊 GitHub Stats

<table>
  <tr>
    <td width="50%">
      <img width="100%" src="https://github-readme-stats.vercel.app/api?username=JeanpiDev&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0b0a&title_color=e6a94c&icon_color=e6a94c&text_color=f2ece2" alt="GitHub stats" />
    </td>
    <td width="50%">
      <img width="100%" src="https://streak-stats.demolab.com/?user=JeanpiDev&hide_border=true&background=0d0b0a&stroke=e6a94c&ring=e6a94c&fire=e6a94c&currStreakLabel=e6a94c&sideLabels=f2ece2&currStreakNum=f2ece2&sideNums=f2ece2&dates=a89d8e" alt="GitHub streak" />
    </td>
  </tr>
</table>

<br>

<!-- CONTACT -->
## 📬 Contact

<p align="center">
  <a href="https://jeanpi-ramirez.vercel.app/en/"><img src="https://img.shields.io/badge/Portfolio-e6a94c?style=for-the-badge&logo=astro&logoColor=0d0b0a" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/dev-jeanpi/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:devjeanpi@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
