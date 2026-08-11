<div align="center">

![](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Vansh%20Sharma&fontSize=42&fontColor=fff&animation=twinkle&fontAlignY=32&desc=Full-Stack%20Engineer%20%7C%20AI%2FML%20%2728&descAlignY=55&descSize=16)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/vansh-sharma-pesu) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:vansh@vansharma.tech) [![Portfolio](https://img.shields.io/badge/Portfolio-000000.svg?logo=vercel&logoColor=white)](https://vansharma.tech/) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://instagram.com/v_.s_.2006)

</div>

---

## Hey, I'm Vansh

**B.Tech CSE (AI/ML) @ PES University, Bengaluru** &nbsp;•&nbsp; **Product Intern @ PESU Research Foundation**

I build full-stack systems where the ML layer has to earn its place, not just exist. Current focus areas: medical AI that holds up under real-world conditions (handwritten prescriptions, multilingual patients, safety-critical validation) and developer tooling that makes code review genuinely intelligent instead of just automated.

---

## Experience

**PESU Research Foundation (PESURF)** — Product Intern | Jun 2026 – Aug 2026 | Bengaluru

- Fine-tuned Qwen 2.5-VL 32B on an 865-prescription dataset (700/85/85 train/test/val split) to replace third-party OCR APIs, reaching 95% exact-match accuracy on medicine name, dosage, and frequency on the held-out test set
- Extended Sanjeevani, originally a team project built for Kalpana 6.0, into the internship's core deliverable: a multi-provider LLM pipeline (Groq, NVIDIA NIM) with fuzzy matching over a 2.5L+ medicine dataset and multilingual TTS across 22 Indian languages

**AIESEC in Bengaluru** — Senior Manager, Outgoing Global Talent | Aug 2025 – Jul 2026 | Bengaluru

- Promoted to Senior Manager within 6 months; led all teams in the Outgoing Global Talent department alongside the Local Committee Vice President
- Drove 20 candidate registrations on the Recruitment Organizing Committee; tracked national people-management metrics for AIESEC in India and ran member feedback cycles against them

---

## Featured Projects

**Codex Reviewer** — Repository-Aware Automated PR Review
Deployed GitHub App plus a convention-profiling CLI, live in production.
- Deployed GitHub App parses PR diffs via tree-sitter AST extraction (JavaScript, TypeScript, Python), posts findings as inline review comments
- CLI profiles a repository's own coding conventions and flags only newly introduced deviations, validating generated fixes in an isolated copy before surfacing them
- BullMQ/Redis queue decouples webhook response from analysis; Zod-validated output with a Llama 3.3 70B (Groq) to GPT-4o-mini fallback chain; containerized with Docker Compose
- [Repo](https://github.com/VanshSharmaPES/codex-reviewer) · [Live Demo](https://codexreviewer.vercel.app/)

**ClearTriage** — Explainable AI Hospital Triage System
- Random Forest ESI classifier with SHAP-based explainability, surfacing a real-time "Why?" rationale for every nurse-facing prediction
- 50-case Human vs. AI clinical audit; load-tested via Apache JMeter at 1,000 concurrent users with 0% errors and +82ms AI overhead
- Stack: Next.js, Express, MongoDB, FastAPI, SHAP
- [Repo](https://github.com/VanshSharmaPES/ClearTriage)

**Reliable Group Notification System** — Computer Networks Coursework Project
- Reliable multicast protocol over UDP in C: ACK-based delivery, timeout-driven retransmission, custom packet framing with sequence numbers
- Benchmarked delivery reliability and throughput against a best-effort UDP baseline under simulated packet loss (Linux tc netem)
- [Repo](https://github.com/VanshSharmaPES/Reliable-Group-Notification-System)

**Portfolio Website**
- Editorial dark-mode design, 97/100 Lighthouse score, CI/CD on Vercel
- Stack: React, Tailwind, Vite
- [Live](https://vansharma.tech)

---

## Tech Stack

**Languages**
![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)

**Frameworks & Libraries**
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)

**Data & Infrastructure**
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ![BullMQ](https://img.shields.io/badge/BullMQ-000000?logo=bullmq&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

**AI / ML**
![Groq](https://img.shields.io/badge/Groq-F55036?logo=groq&logoColor=white) ![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?logo=nvidia&logoColor=white) ![tree-sitter](https://img.shields.io/badge/tree--sitter-000000?logo=github&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05033?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) ![Apache JMeter](https://img.shields.io/badge/Apache_JMeter-D22128?logo=apachejmeter&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode&logoColor=white)

---

## GitHub Stats

<div align="center">

![](https://github-readme-stats.herokuapp.com/api?username=VanshSharmaPES&theme=tokyonight&hide_border=true&show_icons=true&count_private=true)

![](https://github-readme-activity-graph.vercel.app/graph?username=VanshSharmaPES&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph)

</div>

---

## Education

**PES University, Bengaluru** — B.Tech CSE (AI/ML) | Sep 2024 – May 2028 (Expected)

---

## Certifications

- **Supervised Machine Learning: Regression and Classification** — DeepLearning.AI & Stanford Online (Coursera)
- **Practical Web Security and Ethical Hacking** — PESU IO
- **Building with Azure Custom Vision** — Microsoft Learn Student Ambassadors, PESU

---

## Achievements

- 7th Place — Kalpana 6.0, Hack for Humanity (IEEE PESUECC Chapter), among 35 competing teams

---

## Let's Connect

- **Open to:** SWE / SDE / ML Engineer internships (Summer 2026) and full-time roles (2028)
- **Ask me about:** medical AI, LLM pipelines, multilingual TTS, explainable ML, AST-based code analysis, reliable UDP protocols
- **Reach me:** [Email](mailto:vansh@vansharma.tech) · [LinkedIn](https://linkedin.com/in/vansh-sharma-pesu)

---

<div align="center">

![](https://camo.githubusercontent.com/2436d81233f5792fd0f264fd57041b0e01e7d27b18bdbb0f61303e4af59e6c9e/68747470733a2f2f63617073756c652d72656e6465722e76657263656c2e6170702f6170693f747970653d776176696e6726636f6c6f723d6772616469656e7426637573746f6d436f6c6f724c6973743d362c31312c3230266865696768743d3130302673656374696f6e3d666f6f746572)

</div>
