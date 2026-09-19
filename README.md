# Muhammad Maaz Korejo

<div align="center">

### **AI Developer & Backend Systems Engineer**

[![Live Portfolio](https://img.shields.io/badge/Live%20Portfolio-maaz--korejo.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://maaz-korejo.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-maaz-korejo)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Maazkorejo)
[![PyPI](https://img.shields.io/badge/PyPI-Packages-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/user/Maazkorejo)
[![Email](https://img.shields.io/badge/Email-maazkorejo00%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maazkorejo00@gmail.com)

<p align="center">
  <b>Building Production-Grade AI Systems End-to-End:</b><br/>
  LLM Orchestration & Evaluation · Intelligent Document Processing (IDP) · Agentic Tooling · High-Throughput Backends
</p>

```
📍 Hyderabad, Pakistan | 🎓 BS Information Technology (University of Sindh, 2024–2027)
📜 12 Anthropic Credentials | 📜 33 Accredited Certifications | 🧪 100% Pytest Coverage Discipline
```

---

</div>

## 📌 About Me

I am an **AI Developer & Backend Engineer** who builds reliable, cost-efficient, production-hardened AI software. My focus is engineering real systems under practical constraints:
- **Intelligent Document Processing (IDP):** Architecting multi-tier hybrid extraction pipelines (heuristic checks, local CPU parsers, cloud OCR fallbacks) that reduce API costs by 80–90%.
- **Deterministic Offline Evaluation:** Building lightweight evaluation frameworks (`llm-eval-kit`) that measure factual grounding, question relevance, refusal detection, and response completeness without costly LLM-as-a-judge calls.
- **Agentic Architectures & Tooling:** Designing adaptive reflection checkpoint systems (Self-RAG), desktop/web operating assistants (Alfred), and developer CLI tooling (`ctx-bridge` on PyPI).

---

## ⚡ Key Highlights & Engineering Metrics

| Metric | Achievement | Impact / Details |
|:---|:---|:---|
| **80–90%** | Cloud OCR Cost Cut | Designed 3-tier hybrid routing pipeline (*LiteParse -> Docling CPU -> Mistral/Chandra fallback*) |
| **3.3x** | Batch Extraction Speedup | Implemented distributed Ray parallel actors for multi-page PDF processing |
| **292+ hrs** | Verified Engineering Track | Completed Back-End AI Engineering track & accepted capstone at FlyRank.ai |
| **0 API Calls** | Deterministic Offline Eval | Designed embedding-based evaluation (*Grounding, Relevance, Refusal, Completeness*) |
| **100%** | Test Coverage Discipline | Maintained 100% unit and integration test coverage across CLI tools and microservices |
| **12** | Anthropic Verified Credentials | MCP, MCP Advanced, Claude API, Claude Vertex AI, Agent Skills, Subagents, Claude Code |
| **33** | Total Verified Certifications | Anthropic, Google, Linux Foundation, IBM, HP LIFE, Forage, UniAthena, PITP |

---

## 💼 Work Experience & Fellowships

### 1. Back-End AI Engineering Intern — **[FlyRank.ai](https://flyrank.ai)**
*Casper, WY · Remote | Jul 2026 – Sep 2026* &nbsp; `Completed Track`
- Completed **292+ documented hours** across API contracts, Task design & structured prompting, Retrieval & Grounding (RAG), and Evaluation & operations.
- Culminated program with accepted capstone project **"Your 10x Solution"**, reviewed and approved by lead track mentors and executive leadership.
- Engineered 5 end-to-end production assignments: custom web scrapers, JWT/auth session protection, multi-container Docker application stacks, PostgreSQL database integrations, and CRUD REST APIs.
- Attended 29 live technical masterclasses and finished 55 industry learning resources alongside completing 12 Anthropic Academy certifications.
- **Verified Credentials:** Official Certificate of Completion (`FR-D11-FA8DB-52256`), Recommendation Letter from CEO Alen Malkoc, and Final Internship Evaluation Report from Director Arijana Ibrović.

### 2. AI Developer Intern — **Nebulark (IDP SaaS)**
*Jul 2026 – Present* &nbsp; `Active Role`
- Conducted a comprehensive **14-tool benchmark** across OCR, layout parsing, and table extraction engines (*Docling, Mistral-OCR-4, Chandra-OCR, DocLayout-YOLO, Reducto, LandingAI DPT-3, PaddleOCR, LiteParse*).
- Architected a **3-tier cost-optimized hybrid extraction pipeline** (*0.5s LiteParse heuristic pre-check -> local Docling on CPU -> Mistral-OCR-4 / Chandra-OCR cloud fallback*), slashing cloud API costs by **80–90%**.
- Implemented **Ray parallel actor processing** achieving a **3.3x speedup** for batch PDF document extraction; fine-tuned **DocLayout-YOLO** (9 document layout classes) using Label-Studio annotations.
- Conducted OpenMAIC provider-registry architectural review and enforced PostgreSQL Row-Level Security (RLS) policies for multi-tenant isolation.

### 3. Research / Implementation Engineer — **[INFERENCE Lab Fellowship](https://github.com/Inference-LAB)**
*Cohort 01 | Jul 2026 – Present* &nbsp; `Cohort 01 Fellow`
- Selected from **130+ applicants** for Cohort 01 to build `llm-eval-kit`, an open-source, pip-installable Python library for offline, deterministic LLM evaluation.
- Designed and implemented 4 core evaluation modules (*Factual Grounding, Relevance, Refusal Detection, Completeness*) with **zero external LLM-as-judge API calls** using local sentence-transformers (`all-MiniLM-L6-v2`).
- Engineered thread-safe singleton embedding model loader and numeric-mismatch verification layer to eliminate false-positive semantic matches in quantitative evaluations.

### 4. Cloud Computing Intern — **PITP–MUET, Jamshoro**
*Govt of Sindh | Mar 2026 – May 2026*
- Delivered a capstone Flask + PostgreSQL + Railway web platform with automated CI/CD under a government-backed technical training program.
- Reduced lab environment setup time by **~30%** via automated VM configuration and onboarding scripts.

### 5. Certified Graphic Designer Intern — **PITP–MUET**
*Govt of Sindh | Jan 2025 – Mar 2025*
- Produced 10+ branded visual assets for institutional print and digital communications under an accredited government design program.
- Earned official Certified Graphic Designer Certificate of Completion.

---

## 🚀 Flagship Projects & Open-Source Tools

### 📦 [CTX-Bridge](https://github.com/Maazkorejo/CTX-Bridge) — *Open-Source AI Context Handoff CLI*
[![PyPI version](https://img.shields.io/pypi/v/ctx-bridge?color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/ctx-bridge)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
- **Tech:** `Python` · `Typer CLI` · `Rich` · `pytest` · `PyPI` · `Git`
- **Install:** `pip install ctx-bridge`
- Packages codebase context with zero friction for LLM handoffs (Claude, Cursor, ChatGPT).
- Features automated language detection, intelligent `.gitignore` filtering, live token counter, and automated secret redaction (API keys, env tokens).
- Includes template presets for Claude Code subagents, Cursor rules, and architecture specs with clean Rich terminal UI and 100% test coverage.

### 🔬 [llm-eval-kit](https://github.com/Inference-LAB/llm-eval-kit) — *Offline LLM Evaluation Library*
[![PyPI version](https://img.shields.io/pypi/v/llm-eval-kit?color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/llm-eval-kit)
- **Tech:** `Python` · `sentence-transformers` · `PyTorch` · `NumPy` · `pytest` · `Scikit-learn`
- **Install:** `pip install llm-eval-kit`
- Lightweight Python library for offline, deterministic LLM evaluation without external judge API costs or latency.
- Implements 4 core evaluation metrics: *Factual Grounding*, *Question Relevance*, *Refusal Detection*, and *Response Completeness* using local `all-MiniLM-L6-v2` embeddings.
- Thread-safe singleton model cache and strict numeric-mismatch verification to prevent false-positive quantitative matches.

### 🧠 [Self-Reflective RAG Engine](https://github.com/Maazkorejo/self-rag-engine) — *Adaptive Retrieval on LLaMA 3.3 70B*
- **Tech:** `Python` · `Groq API` · `LLaMA 3.3 70B` · `LangGraph` · `ChromaDB / pgvector` · `Docker` · `pytest`
- Implemented Self-RAG architecture (*Asai et al.*) over Groq LLaMA 3.3 70B with 4 automated reflection checkpoints (`Retrieve`, `IsRel`, `IsSup`, `IsUse`).
- Dynamic query rewriting and web search fallback triggered whenever local vector retrieval fails relevance thresholds.
- Containerized with Docker and tested with 100% unit & integration test coverage (46 pytest test cases).

### 🎙️ [Alfred — Personal AI Operating Assistant](https://github.com/Maazkorejo/Alfred-Personal-Assistant)
[![Live Demo](https://img.shields.io/badge/Demo-Live-brightgreen)](https://alfred-personal-assistant.vercel.app)
- **Tech:** `Flask` · `Flask-SocketIO` · `LangGraph` · `Mistral AI` · `PostgreSQL (pgvector)` · `React 18` · `Piper TTS` · `Railway` · `Vercel`
- Agentic operating assistant equipped with 14 custom tools (email, calendar, filesystem, shell, web search).
- Real-time streaming WebSocket trace panel exposing step-by-step tool invocation logs and agent reasoning traces.
- Offline local speech synthesis using Piper TTS and a lightweight FFT spectral clap-to-wake detector for hands-free local activation.

### ⚽ [AI Pundit Rankings](https://github.com/Maazkorejo/football-pundit) — *FIFA World Cup 2026 Prediction Platform*
[![Live Demo](https://img.shields.io/badge/Demo-Live-brightgreen)](https://football-pundit.vercel.app)
- **Tech:** `Flask` · `React 18` · `Supabase` · `PostgreSQL` · `Mistral AI` · `APScheduler` · `Railway` · `Vercel`
- Social prediction platform with a 6-module REST API and 5-table relational schema.
- Automated AI-scoring background worker (APScheduler + Mistral AI) that grades predictions against live match feeds and generates real-time community roasts.

### 🛡️ [Network Intrusion Detection System](https://github.com/Maazkorejo/NIDS-Machine-Learning)
- **Tech:** `Python` · `XGBoost` · `Random Forest` · `Scikit-learn` · `SHAP` · `Pandas`
- End-to-end machine learning pipeline classifying 14 network attack categories (*DDoS, Port Scan, Botnet, Brute Force*) on the CICIDS-2017 dataset.
- Achieved **~99% classification accuracy** with near-zero false positives.
- Interpreted feature importance using SHAP explainability values; packaged for one-command execution.

---

## 🛠️ Master Tech Stack & Capabilities

```
┌──────────────────────────────────────────────────────────────────────────┐
│                             MASTER TECH STACK                            │
├──────────────────────────────────────────────────────────────────────────┤
│ LAYER 01: AI & LLM ENGINEERING                                           │
│  • Model Context Protocol (MCP)    • Claude Code (Subagents & Skills)    │
│  • Claude / Anthropic API          • Retrieval & Grounding (RAG)         │
│  • DSPy Prompt Optimization        • LangGraph Agent Workflows           │
│  • Mistral AI & Groq LLaMA 3.3 70B • sentence-transformers               │
│  • llm-eval-kit (Offline Eval)     • Vector Memory (pgvector / Supabase) │
├──────────────────────────────────────────────────────────────────────────┤
│ LAYER 02: DOCUMENT INTELLIGENCE & OCR                                    │
│  • Intelligent Document Processing • Docling & LiteParse                 │
│  • Mistral-OCR-4 & Chandra-OCR     • DocLayout-YOLO (9 classes)          │
│  • Ray Parallel Processing (3.3x)  • Label-Studio & MinerU               │
│  • Agentic Document Workflows      • n8n Automation                      │
├──────────────────────────────────────────────────────────────────────────┤
│ LAYER 03: MACHINE LEARNING & DATA SCIENCE                                │
│  • Scikit-learn                    • XGBoost & Random Forest             │
│  • SHAP Explainability             • Pandas & NumPy                      │
│  • Feature Engineering             • Model Benchmarking & Evaluation     │
├──────────────────────────────────────────────────────────────────────────┤
│ LAYER 04: BACKEND & CLOUD INFRASTRUCTURE                                 │
│  • Python (Flask)                  • REST APIs & API Contracts           │
│  • Swagger / OpenAPI               • Docker & Containerization           │
│  • PostgreSQL (RLS Multi-Tenancy)  • Supabase & pgvector                 │
│  • Auth (JWT / Login & Protect)    • Webhooks & Caching                  │
│  • Background Jobs & Workflows     • The Twelve-Factor App               │
│  • Railway Deployment              • Git / GitHub & CI/CD Pipelines      │
├──────────────────────────────────────────────────────────────────────────┤
│ LAYER 05: FRONTEND, TESTING & TOOLING                                    │
│  • pytest (100% Test Coverage)     • Typer CLI & Rich Terminal           │
│  • Web Scraping (HTML to Clean)    • Node.js & JavaScript                │
│  • React 18 & Vite                 • Tailwind CSS & shadcn/ui            │
│  • HTML5 & CSS3                    • Framer Motion & Responsive Design   │
└──────────────────────────────────────────────────────────────────────────┘
```

---

## 📜 Verified Certifications (33 Total)

<details>
<summary><b>🟧 Anthropic (12 Verified Credentials) — Expand to view</b></summary>

1. **Model Context Protocol (MCP):** Architecture, Transports, Stdio/SSE Servers & Clients
2. **Model Context Protocol: Advanced Topics**
3. **Building with the Claude API**
4. **Claude with Google Cloud's Vertex AI**
5. **Introduction to Agent Skills**
6. **Introduction to Subagents**
7. **Claude Code in Action**
8. **Claude Code 101**
9. **Claude Platform 101**
10. **AI Fluency: Framework & Foundations**
11. **Claude 101**
12. **AI Fluency for Students**

</details>

<details>
<summary><b>🟦 Google & The Linux Foundation — Expand to view</b></summary>

1. **Google AI Essentials Specialization** (5-Course Specialization · Google / Coursera)
2. **AI Fundamentals** (Google · Coursera)
3. **AI for Research and Insights** (Google · Coursera)
4. **Inclusive Open Source Community Orientation (LFC102)** (The Linux Foundation)

</details>

<details>
<summary><b>🏢 Industry Programs, Honors & Fellowships — Expand to view</b></summary>

1. **Backend AI Engineering Internship — Certificate of Completion** (FlyRank.ai · `ID: FR-D11-FA8DB-52256`)
2. **Official Recommendation Letter** (Alen Malkoc, CEO · FlyRank.ai · `FR-D10-4A2D2-7F7FF`)
3. **Final Internship Report & Evaluation** (Arijana Ibrović, Director · FlyRank.ai · `FR-D8-2C53C-C9AA4`)
4. **INFERENCE Lab Fellowship — Cohort 01 Fellow** (INFERENCE Lab)
5. **Top Participant — HEC / NAVTTC ACT AI SkillBridge** (Government of Pakistan)
6. **McKinsey Forward Program** (McKinsey.org)
7. **Certified Graphic Designer** (PITP–MUET · Govt of Sindh)

</details>

<details>
<summary><b>🛡️ Cybersecurity & Professional Simulations — Expand to view</b></summary>

1. **Cybersecurity Job Simulation** (Mastercard · Forage)
2. **Cyber Security Operations Job Simulation** (Datacom · Forage)
3. **Your Future in Cybersecurity: The Job Landscape** (IBM SkillsBuild)
4. **Getting Started with Cybersecurity** (IBM SkillsBuild)
5. **Protecting a Device with Malwarebytes** (IBM SkillsBuild)
6. **Cybersecurity and Data** (IBM SkillsBuild)
7. **Introduction to Cyber Security** (Simplilearn SkillUp)
8. **AI for Beginners** (HP LIFE · HP Foundation)

</details>

<details>
<summary><b>🐍 Python Specialization (UniAthena · CIQ) — Expand to view</b></summary>

1. **Python for Data Science & Machine Learning**
2. **Data Structure in Python**
3. **OOPs Concept in Python**
4. **Functions in Python**
5. **Modules, Packages & Files in Python**
6. **Data Types & Statements in Python**
7. **Basics of Python Programming**

</details>

---

## 🎓 Education

- **Bachelor of Science in Information Technology (BS IT)**  
  *University of Sindh, Jamshoro* | Feb 2024 – Dec 2027 (6th Semester)  
  *Relevant Coursework:* AI & Machine Learning, Advanced DBMS, Cybersecurity, Cloud Computing, Computer Networks, Data Structures & Algorithms.

---

## 📬 Connect With Me

- 🌐 **Website:** [maaz-korejo.vercel.app](https://maaz-korejo.vercel.app)
- 💼 **LinkedIn:** [linkedin.com/in/muhammad-maaz-korejo](https://linkedin.com/in/muhammad-maaz-korejo)
- 🐙 **GitHub:** [github.com/Maazkorejo](https://github.com/Maazkorejo)
- 📦 **PyPI:** [pypi.org/user/Maazkorejo](https://pypi.org/user/Maazkorejo)
- 📧 **Email:** [maazkorejo00@gmail.com](mailto:maazkorejo00@gmail.com)
- 📱 **WhatsApp:** +92 345 661 8618

---

<div align="center">
  <sub>Engineered with discipline. © 2026 Muhammad Maaz Korejo.</sub>
</div>
