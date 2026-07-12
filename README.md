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

I build full-stack systems where the ML layer has to actually earn its place — not just exist. My focus: **medical AI that works in the real world** (handwritten prescriptions, multilingual patients, safety-critical validation) and **developer tools that make code reviews intelligent**.

---

## 💼 Experience

### **PESU Research Foundation (PESURF)** — *Product Intern* | Jun 2026 – Present | Bengaluru
- Built **Sanjeevani AI** — a two-stage pipeline (Llama-4-Scout OCR → Llama-3.3-70B analysis) with multi-provider routing (Groq, NVIDIA NIM), rotating API keys, and MD5-based result caching
- Implemented fuzzy matching over a **2.5L+ medicine dataset** with SQLite caching, OpenFDA fallback, and LLM auto-caching
- Delivered **multilingual TTS output across 22 Indian languages** using Microsoft Edge Neural Voices
- Tech: Python, Next.js, Flask, Groq API, NVIDIA NIM, MongoDB, SQLite, OpenCV, Edge TTS

### **AIESEC in Bengaluru** — *Senior Manager, Outgoing Corporate Exchanges* | Aug 2025 – Present
- Progressed from Junior Manager (Aug 2025) to Senior Manager, driving corporate exchange partnerships and talent pipeline for outgoing programs
- Served on the Organizing Committee for Recruitments (Nov 2025 – Feb 2026); currently part of the People Management Support Team (Apr 2026 – Present)

---

## 🚀 Featured Projects

### 🏥 **Sanjeevani** — Prescription OCR + Multilingual TTS for Rural Healthcare
> Reads handwritten prescriptions → extracts structured meds/dosage/frequency → validates safety → reads aloud in the patient's native language.

- **Two-stage LLM pipeline**: Llama-4-Scout (NVIDIA NIM) for vision OCR → Llama-3.3-70B-Versatile (Groq LPU) for medical reasoning
- **Multi-provider routing** with API key rotation + exponential backoff
- **MD5 caching layer** for prescription deduplication
- **250K+ Indian medicine fuzzy match** (SQLite + OpenFDA fallback)
- **Confidence-scored fallback** to deterministic rule engine (`medicine_matcher.py`)
- **22 scheduled Indian languages** via Edge TTS neural voices
- 🔗 [Repo](https://github.com/VanshSharmaPES/Sanjeevani)

---

### 🏥 **ClearTriage** — Explainable AI Hospital Triage System
> Random Forest ESI classifier + SHAP explanations. **0% error vs human triage** on 50-case clinical audit. **619 req/s** sustained (JMeter, 100 concurrent users).

- Real-time "Why?" tooltips for every nurse-facing prediction via SHAP force plots
- Stack: Next.js, Express, MongoDB, FastAPI, SHAP, scikit-learn
- 🔗 [Repo](https://github.com/VanshSharmaPES/ClearTriage) • [Demo](https://cleartriage.vercel.app)

---

### 🤖 **AI Bug Detector** — Automated AI-Powered PR Reviewer
> GitHub App that parses PR diffs into AST via **tree-sitter** across 5 languages (C, C++, Python, JavaScript, TypeScript) to detect memory leaks, race conditions, null dereferences, and injection vulnerabilities.

- **Async review pipeline**: BullMQ + Redis so webhook responses return immediately while LLM analysis runs in background
- **Strict JSON schema validation (Zod)** before posting inline PR comments
- Deployed on Vercel
- Stack: Next.js, Groq (Llama-3.3-70B), tree-sitter, BullMQ, Redis, Zod
- 🔗 [Repo](https://github.com/VanshSharmaPES/AI-Bug-Detector)

---

### 📚 **NovaLearn** — Full-Featured LMS
> Role-based access (instructors/students), JWT auth, course management, progress tracking.
- Stack: MERN, JWT, React Query
- 🔗 [Repo](https://github.com/VanshSharmaPES/NovaLearn)

---

### 🌐 **Portfolio Website**
> Editorial dark-mode aesthetic. **97/100 Lighthouse**. CI/CD on Vercel.
- Stack: React, Tailwind, Vite
- 🔗 [Live](https://vansharma.tech) • [Repo](https://github.com/VanshSharmaPES/Portfolio-App-Full-Stack)

---

### ⚡ **Hospital Queue Management System**
> **500+ concurrent users • 16ms latency • 0% packet loss** (JMeter validated)
- Stack: MERN, Apache JMeter
- 🔗 [Repo](https://github.com/VanshSharmaPES/Hospital-Queue-Management)

---

### 🌐 **Reliable Group Notification System** — Computer Networks Coursework
> Reliable multicast protocol over UDP: ACK-based delivery, timeout/retransmission logic, custom packet framing with sequence numbers. Benchmarked against best-effort UDP under simulated packet loss (Linux `tc netem`).
- Stack: C, UDP Sockets, Linux tc netem
- 🔗 [Repo](https://github.com/VanshSharmaPES/Reliable-Group-Notification)

---

## 🧠 Currently Leveling Up (5th Semester Focus)

| Area | What I'm Doing |
|------|----------------|
| **LLM Optimization** | LoRA fine-tuning Llama-4-Maverick on 512 Rx dataset • Self-consistency decoding (N=5) • Confidence-threshold routing (0.85) |
| **MLOps for Medical AI** | Offline simulation (512 Rx) vs live pilot evaluation pipeline • Latency profiling • Cache warming strategies |
| **Production AI Infra** | NVIDIA NIMs deployment • Groq LPU inference • Multi-provider failover • Rate-limit handling |
| **Coursework** | ML (PyTorch), DBMS (Redis/Neo4j/Kafka), SE (Docker/Jenkins/SonarQube), Prompt Engineering, Active Learning |

---

## 🛠️ Tech Stack

**AI/ML & LLMs**  
`Llama-4-Scout` `Llama-3.3-70B` `Groq API` `NVIDIA NIM` `PyTorch` `scikit-learn` `SHAP` `OpenCV` `Hugging Face` `LangChain` `sentence-transformers` `Edge TTS` `tree-sitter`

**Full-Stack**  
`React` `Next.js` `Node.js` `Express` `FastAPI` `Flask` `Tailwind CSS` `TypeScript` `JavaScript (ES6+)` `Python` `C` `C++`

**Data & Infra**  
`MongoDB` `SQLite` `Supabase` `Redis` `Neo4j` `Kafka` `Docker` `Gunicorn` `Vercel` `Render` `n8n` `Apache JMeter` `BullMQ`

**Tools**  
`Git` `GitHub` `VS Code` `Jira` `OpenProject` `SonarQube` `pytest` `Zod` `Figma`

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

## 🎓 Education

**PES University, Bengaluru** — *B.Tech CSE (AI/ML)* | Sep 2024 – Present

**Cambridge International School, Amritsar** — *High School Diploma (Sciences & Mathematics)* | 2022 – 2024

---

## 📜 Certifications

- **Supervised Machine Learning: Regression and Classification** — DeepLearning.AI & Stanford Online (Coursera)
- **Building with Azure Custom Vision** — Microsoft Learn Student Ambassadors, PESU
- **Practical Web Security and Ethical Hacking** — PESU IO
- **C Programming Certification** — Udemy
- **Python Basics Certification** — HackerRank

---

## 🎓 Leadership & Community

- **AIESEC in Bengaluru** — Senior Manager, Outgoing Corporate Exchanges; People Management Support Team (building a Productivity & Dropout Prediction Dashboard to turn member feedback into retention signals)
- **Microsoft Learn Student Ambassadors (MLSA), PESU** — Logistics Member
- **WEAL-ECC, PES University** — Former Logistics & Operations Member, Health-Tech Club

---

## 📫 Let's Connect

- 💼 **Open to**: SDE / ML Engineer internships (Summer 2026) & full-time (2028)
- 💬 **Ask me about**: Medical AI, LLM pipelines, multilingual TTS, explainable ML, AST-based code analysis, reliable UDP protocols
- 📧 **Reach me**: `vansh@vansharma.tech` or [LinkedIn](https://linkedin.com/in/vansh-sharma-pesu)

---

> *“You're not behind. You're overleveraged. Build the proof. Ship it. Then come back.”* — *Note to self, June 2026*

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />
</div>