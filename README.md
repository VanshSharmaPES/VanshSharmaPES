<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Vansh%20Sharma&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Full-Stack%20Engineer%20%7C%20AI%2FML%20%7C%20PESU%20%2728&descAlignY=55&descSize=16" />
</div>

<div align="center">
  <a href="https://linkedin.com/in/vansh-sharma-pesu">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:vansh@vansharma.tech">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" />
  </a>
  <a href="https://vansharma.tech/">
    <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?logo=vercel&logoColor=white" />
  </a>
  <a href="https://instagram.com/v_.s_.2006">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white" />
  </a>
</div>

---

## Hey, I'm Vansh 👋

**B.Tech CSE (AI/ML) @ PES University, Bengaluru** • **Product Intern @ PESU Research Foundation**

I build full-stack systems where the ML layer has to actually earn its place — not just exist. My focus: **medical AI that works in the real world** (handwritten prescriptions, multilingual patients, safety-critical validation).

---

## 🚀 Featured Projects

### 🏥 **Sanjeevani** — Prescription OCR + Multilingual TTS for Rural Healthcare
> **The problem**: 250M+ low-literacy Indians can't read handwritten prescriptions. A misread dosage (5mg vs 50mg) can be fatal.
>
> **The solution**: Mobile-first AI that scans → extracts structured meds/dosage/frequency → validates safety → reads aloud in the patient's native language.

| Metric | Current | Target | Status |
|--------|---------|--------|--------|
| **Medicine Name F1** | 0.697 | ≥0.85 | ✅ Strong |
| **Frequency F1** | 0.236 → **0.600** | ≥0.50 | 🔧 P0 fix deployed |
| **Dosage F1** | 0.364 → **0.516** | ≥0.45 | 🔧 P1 fix deployed |
| **Duration F1** | 0.489 | ≥0.55 | 📋 P2 planned |
| **End-to-End Latency** | 30–40s | ≤15s | ⚡ Caching + concurrency |
| **Languages** | 22 scheduled Indian languages | — | ✅ Edge TTS neural voices |
| **Safety Layer** | Deterministic drug-interaction checker + exact-match substitution engine | — | ✅ Zero-AI-hallucination |

**Architecture Highlights**
- **Two-stage LLM pipeline**: Llama-4-Maverick-17B-128E (NVIDIA NIM) for vision OCR → Llama-3.3-70B-Versatile (Groq LPU) for medical reasoning
- **Multi-provider routing** with API key rotation + exponential backoff
- **MD5-based caching layer** for prescription deduplication
- **250K+ Indian medicine fuzzy match** (SQLite + OpenFDA fallback)
- **Confidence-scored fallback** to deterministic rule engine (`medicine_matcher.py`)
- **Dynamic few-shot retrieval** from 512 annotated prescriptions (sentence-transformers)
- **Frequency normalization engine**: `1-0-1`/`BD`/`1?1` → `twice daily` (+0.36 F1 jump)
- **Dosage parser**: ranges (`500-750mg`), fractions (`1/2 tab`), text numbers (`two tablets`)

🔗 **Repo**: [VanshSharmaPES/Sanjeevani](https://github.com/VanshSharmaPES/Sanjeevani)  
📋 **Tech Wiki**: [Research Gaps](https://github.com/VanshSharmaPES/Sanjeevani/wiki/Research-Gaps) • [Evaluation Report](https://github.com/VanshSharmaPES/Sanjeevani/wiki/Evaluation-Report) • [Improvement Roadmap](https://github.com/VanshSharmaPES/Sanjeevani/wiki/Roadmap) • [Model Strategy](https://github.com/VanshSharmaPES/Sanjeevani/wiki/Model-Prioritization)

---

### 🏥 **ClearTriage** — Explainable Hospital Triage
> Random Forest + SHAP explanations. **0% error vs human triage** on 50-case clinical audit. **619 req/s** sustained (JMeter, 100 concurrent users).

- **Stack**: Next.js, FastAPI, MongoDB, scikit-learn, SHAP
- **Key insight**: The model wasn't the hard part — making nurses *trust* it under pressure was. SHAP force plots in plain English did that.
- 🔗 [Repo](https://github.com/VanshSharmaPES/ClearTriage) • [Demo](https://cleartriage.vercel.app)

---

### 📚 **NovaLearn** — Full-Featured LMS
> Role-based access (instructors/students), JWT auth, course management, progress tracking.
- **Stack**: MERN, JWT, React Query
- 🔗 [Repo](https://github.com/VanshSharmaPES/NovaLearn)

---

### 🌐 **Portfolio Website**
> Editorial dark-mode aesthetic. **97/100 Lighthouse**. CI/CD on Vercel.
- **Stack**: React, Tailwind, Vite
- 🔗 [Live](https://vansharma.tech) • [Repo](https://github.com/VanshSharmaPES/Portfolio-App-Full-Stack)

---

### ⚡ **Hospital Queue Management System**
> **500+ concurrent users • 16ms latency • 0% packet loss** (JMeter validated)
- **Stack**: MERN, Apache JMeter
- 🔗 [Repo](https://github.com/VanshSharmaPES/Hospital-Queue-Management)

---

### 🧩 **AlgoForge** — Gamified DSA Platform
> Problem tagging, solution ratings, timed challenges, leaderboards. Built for campus coding competitions.
- **Stack**: React, Node.js, Express, MongoDB
- 🔗 [Repo](https://github.com/VanshSharmaPES/AlgoForge)

---

## 🧠 Currently Leveling Up (5th Semester Focus)

| Area | What I'm Doing |
|------|----------------|
| **LLM Optimization** | LoRA fine-tuning Llama-4-Maverick on 512 Rx dataset • Self-consistency decoding (N=5) • Confidence-threshold routing (0.85) |
| **MLOps for Medical AI** | Offline simulation (512 Rx) vs live pilot (15 Rx) evaluation pipeline • Latency profiling • Cache warming strategies |
| **Production AI Infra** | NVIDIA NIMs deployment • Groq LPU inference • Multi-provider failover • Rate-limit handling |
| **Coursework** | ML (PyTorch), DBMS (Redis/Neo4j/Kafka), SE (Docker/Jenkins/SonarQube), Prompt Engineering, Active Learning |

---

## 🛠️ Tech Stack

**AI/ML & LLMs**  
`Llama-4-Maverick-17B` `Llama-3.3-70B` `Groq API` `NVIDIA NIM` `PyTorch` `scikit-learn` `SHAP` `OpenCV` `Hugging Face` `LangChain` `sentence-transformers` `Edge TTS`

**Full-Stack**  
`React` `Next.js` `Node.js` `Express` `FastAPI` `Flask` `Tailwind CSS` `TypeScript` `JavaScript (ES6+)` `Python` `C`

**Data & Infra**  
`MongoDB` `SQLite` `Supabase` `Redis` `Neo4j` `Kafka` `Docker` `Gunicorn` `Vercel` `Render` `n8n` `Apache JMeter`

**Tools**  
`Git` `GitHub` `VS Code` `Jira` `OpenProject` `SonarQube` `pytest` `Figma`

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=VanshSharmaPES&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VanshSharmaPES&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=VanshSharmaPES&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VanshSharmaPES&theme=tokyo-night&hide_border=true&area=true" />
</div>

---

## 🎓 Leadership & Community

- **AIESEC in Bengaluru** — Senior Manager, Outgoing Corporate Exchanges; People Management Support Team (building a Productivity & Dropout Prediction Dashboard to turn member feedback into retention signals)
- **Microsoft Learn Student Ambassadors (MLSA), PESU** — Logistics Member
- **WEAL-ECC, PES University** — Former Logistics & Operations Member, Health-Tech Club

---

## 📫 Let's Connect

- 💼 **Open to**: SDE / ML Engineer internships (Summer 2026) & full-time (2028)
- 💬 **Ask me about**: Medical AI, LLM pipelines, multilingual TTS, explainable ML, DSA platforms
- 📧 **Reach me**: `vansh@vansharma.tech` or [LinkedIn](https://linkedin.com/in/vansh-sharma-pesu)

---

> *“You're not behind. You're overleveraged. Build the proof. Ship it. Then come back.”* — *Note to self, June 2026*

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />
</div>