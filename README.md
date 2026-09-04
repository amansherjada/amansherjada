# Aman Khan

**AI Engineer — agents, RAG, and production automation**

Abu Dhabi, UAE · Available immediately

[![Portfolio](https://img.shields.io/badge/theamankhan.com-000000?style=flat-square&logo=safari&logoColor=white)](https://theamankhan.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amanskhan)
[![Kaggle](https://img.shields.io/badge/Kaggle_Expert-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/amansherjadakhan)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/amansherjada)
[![Email](https://img.shields.io/badge/amanskhan55@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:amanskhan55@gmail.com)

---

## Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,typescript,javascript,nodejs,fastapi,react,nextjs,vite&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=docker,gcp,aws,cloudflare,mongodb,postgres,redis,sqlite&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,git,github,tailwind,streamlit,linux,vscode&theme=dark" />
</p>

---

## GitHub stats

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=amansherjada&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=amansherjada&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />
</p>

<p align="left">
  <img src="https://streak-stats.demolab.com?user=amansherjada&theme=github-dark-blue&hide_border=true" />
</p>

---

## What I actually do

I build AI systems that run in daily production — not demos, not proof-of-concepts that never ship.

For two years I was the sole AI architect across a three-company group (American Hairline, Alchemane, Ydigital). I sat with sales, HR, marketing, and operations — understood exactly what they needed — then designed, built, and maintained the systems they relied on every single day.

The repos here are sanitized snapshots of that production work. Architecture is intact. Credentials and customer PII are not.

---

## Numbers that mean something

| Result | System |
|---|---|
| **55% lower** LLM API cost, **95%** coverage maintained | CRM Call Audit |
| **100%** of sales calls reviewed automatically | CRM Call Audit |
| **300% more** content output | n8n + GenAI workflows |
| **107 employees** on face-biometric payroll | Hazri Box |
| **37 training videos** indexed into a live RAG system | Sales LMS |
| **11 quality parameters** scored per call, 3 sales teams | CRM Call Audit |

---

## Production systems

> These are sanitized public snapshots. Live credentials, customer PII, and private keys are not included.

### [HireOS](https://github.com/amansherjada/hireos) — AI Recruitment Platform
End-to-end hiring, zero manual steps between application and scored result.  
CV parse → GPT-4o personalised questions → WhatsApp test delivery → real-time anti-cheat (tab-switch tracking) → auto-grading → HR dashboard with DISC personality profiling and role-fit analysis.  
`React` `Vite` `Google Apps Script` `OpenRouter` `WhatsApp`

### [CRM Call Audit](https://github.com/amansherjada/crm-call-audit) — Sales Call QA Pipeline
Every sales call, audited automatically across 11 quality parameters for 3 teams. Eliminated manual review entirely. Model routing (smart escalation between smaller and larger models) cut API costs 55% while keeping 95% high-priority coverage.  
`FastAPI` `Whisper` `GPT-4o` `Python`

### [AHL Sales LMS](https://github.com/amansherjada/ahl-sales-lms) — RAG Training Platform with Voice Roleplay
Full-stack learning management system with RAG over 37 video transcripts, voice AI roleplay, and real-time scoring. Live in daily production across two sales teams.  
`React` `Node.js` `MongoDB` `Pinecone` `AssemblyAI` `LangChain`

### [Hazri Box](https://github.com/amansherjada/hazri-box) — Attendance & Payroll PWA
Installable PWA for 107 employees — face biometric + GPS geofenced punches, automated payroll calculation, late/OT rules, and WhatsApp leave approvals. Solved a silent firmware disconnection issue by building a custom pull-based LAN bridge with a watchdog process.  
`React` `Vite` `FastAPI` `Google Sheets`

### [Marketing Attribution](https://github.com/amansherjada/marketing-attribution) — Real-Time Funnel Tracking
Full Meta Ads → WhatsApp → booking funnel tracked in real time via Gallabox webhooks and MongoDB Change Streams. UTM tracking across ads, website, and YouTube to calculate campaign ROI.  
`GCP Cloud Run` `Firestore` `MongoDB` `Webhooks`

### [Career Automation](https://github.com/amansherjada/career-automation) — Human-in-the-Loop Career OS
Production-grade AI career operating system for a UAE job search. Automates research, scoring, deduplication, contact verification, and draft preparation — while keeping every irreversible action (sending email, submitting applications) under human control. MCP server on Cloudflare Workers, Google Sheets as an auditable database, Grok Automations for daily orchestration.  
`Cloudflare Workers` `TypeScript` `MCP` `OAuth 2.0 + PKCE` `Google Apps Script` `Grok`

### [AI Hair Salon](https://github.com/amansherjada/ai-hair-salon) — Multimodal Hairstyle Recommendation
Browser-based multimodal AI app. Image upload → Gemini Pro identity-preserving hairstyle generation → AI analysis report.  
`HTML/CSS/JS` `Google Gemini`

---

## Stack

| Layer | Tools |
|---|---|
| **AI / Agents** | LangChain · RAG · Prompt + Tool Calling · OpenAI (GPT-4o, Whisper) · AssemblyAI · Gemini · n8n · CrewAI · MCP |
| **Backend** | Python · FastAPI · Node.js · REST APIs · Webhooks · Google Apps Script |
| **Frontend** | TypeScript · React · Next.js 15 · Vite · Streamlit · Payload CMS 3 · Tailwind CSS |
| **Data** | PostgreSQL · MongoDB · Firestore · Redis · SQLite · Pinecone · AstraDB |
| **Cloud / Ops** | Docker · GCP · Cloudflare Workers · AWS · OCI · GitHub Actions |
| **Daily build tools** | Claude Code · Cursor · ChatGPT |
| **In progress** | Microsoft AI-103 Azure AI Apps & Agents Developer Associate (Azure AI Foundry training completed, exam target Sep 2026) |

---

## Notable standalone projects

**J.A.R.V.I.S. — AI Recruitment Pipeline**  
n8n multi-agent LinkedIn search pipeline (SerpAPI) that scrapes, scores, and stores candidate profiles into a Google Sheet ATS. GPT-powered sourcing engine with conversation memory and negotiation-strategy generation.  
`Google Apps Script` `n8n` `OpenRouter` `SerpAPI`

**RAG PDF Query System**  
Document QA with sub-second semantic search across 100+ page PDFs using LangChain and AstraDB vector embeddings. Source citations in UI.  
`Python` `LangChain` `AstraDB` `Streamlit`

**Llama-3.2-1B Fine-Tuning with QLoRA**  
Fine-tuned Meta Llama-3.2-1B using QLoRA (4-bit quantization), FP16 mixed-precision, and AdamW 8-bit on a consumer GPU. Published reference notebook on [Kaggle](https://www.kaggle.com/amansherjadakhan) and [Hugging Face](https://huggingface.co/amansherjada).  
`PyTorch` `LoRA` `HuggingFace` `Kaggle`

---

## Experience

**AI Developer → AI Team Lead**  
American Hairline · Alchemane Hair Extensions · Ydigital · *Feb 2025 – Aug 2026 · Mumbai*

Sole AI architect and team lead (3–4 people). Responsible for the end-to-end design, development, and deployment of all AI and automation systems across three group companies. Built everything above, plus an internal task management portal (Next.js + Cloudflare Workers D1), CEO-level MIS dashboards, and a full website rebuild of americanhairline.com (Next.js 15, Payload CMS 3, PostgreSQL, Redis, Docker).

**AI & Automation Executive**  
AYA Facility Management · *Mar 2024 – Oct 2024 · Mumbai*

Google Apps Script workflow automation, an AI-powered customer support chatbot, and the company website.

---

## Education & Certifications

**B.E. Computer Science** · Savitribai Phule Pune University · 2020–2024

- Kaggle Notebook Expert — Top 1,300 of 60,000+ contributors (Top 2%)
- Microsoft AI-103: Azure AI Apps & Agents Developer Associate — *In progress, target Sep 2026*
- Microsoft Azure AI Foundry Virtual Training Day — *Completed Aug 2026*
- Oracle Cloud Infrastructure AI Foundations Professional
- Supervised Machine Learning & Advanced Learning Algorithms — DeepLearning.AI (Coursera)
- EF SET English Certificate — 74/100 (C2 Proficient)

---

## Contact

Based in **Abu Dhabi**, available to start immediately.

- Email: [amanskhan55@gmail.com](mailto:amanskhan55@gmail.com)
- Portfolio: [theamankhan.com](https://theamankhan.com)
- LinkedIn: [linkedin.com/in/amanskhan](https://www.linkedin.com/in/amanskhan)
- GitHub: [github.com/amansherjada](https://github.com/amansherjada)
