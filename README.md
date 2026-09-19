<div align="center">
# Hi there, I'm Muhammad Maaz 👋
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=7C3AED&center=true&vCenter=true&width=750&lines=AI+Developer+%26+Backend+Engineer;Open-Source+Contributor+to+Microsoft+AutoGen;Building+Agentic+AI+Systems+%2B+Self-RAG;12x+Anthropic+Verified+Credentials;Shipping+Deterministic+LLM+Evaluation+Libraries)](https://git.io/typing-svg)
![Profile Views](https://komarev.com/ghpvc/?username=Maazkorejo&color=7C3AED&style=for-the-badge&label=PROFILE+VIEWS)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-muhammad--maaz--korejo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-maaz-korejo-1677a9267)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-22C55E?style=for-the-badge&logo=railway&logoColor=white)](https://cloud-portfolio-production-f02c.up.railway.app)
[![Email](https://img.shields.io/badge/Email-maazkorejo00@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maazkorejo00@gmail.com)
</div>
<div align="center">
<img src="https://raw.githubusercontent.com/kirinnee/kirinnee/master/pixel-city.gif" width="100%"/>
</div>
---
<table>
<tr>
<td width="60%">
### 🎯 About Me
- 🎓 3rd-year **BS Information Technology** student at **University of Sindh, Jamshoro** (6th semester)
- 🚀 **Open-Source Contributor** to Microsoft's official multi-agent framework: **[Microsoft AutoGen](https://github.com/microsoft/autogen)**
- 📜 Hold **12 Anthropic-verified credentials** across MCP, Claude API, Claude Code, Subagents, and Agent Skills
- 🔬 **Research/Implementation Engineer** at **INFERENCE Lab Fellowship** developing `llm-eval-kit` for offline LLM evaluation
- 💼 Completed **Backend AI Engineering Internship** at **FlyRank.ai** and contributing to Intelligent Document Processing (IDP) SaaS at **Nebulark**
- 🌍 Based in Hyderabad, Pakistan
</td>
<td width="40%">
<img src="https://raw.githubusercontent.com/devSouvik/devSouvik/master/gif3.gif" width="100%"/>
</td>
</tr>
</table>
---
### 🌟 Open-Source Contributions
#### 🤖 [Microsoft AutoGen — PR #8077](https://github.com/microsoft/autogen/pull/8077)
> *Maintainer-Approved Fix in Microsoft's Multi-Agent AI Framework*
- **Diagnosed [Issue #7418](https://github.com/microsoft/autogen/issues/7418):** Discovered that custom LLM inference parameters (`extra_body`, e.g., `enable_thinking` for reasoning models or custom API flags) were accepted at runtime but silently stripped during JSON serialization in `autogen-ext`.
- **Architected Fix & Test Suite:** Added `extra_body` to `CreateArguments` and `CreateArgumentsConfigModel` Pydantic schemas, authored regression test suites for `dump_component()` / `load_component()` serialization roundtrips, and added Azure OpenAI client compatibility.
- **Formal Maintainer Approval:** Officially reviewed and **approved by Microsoft maintainer Esan (@EsanRAHIMI)**.
---
### 🚀 Featured Projects
#### 🌉 [CTX-Bridge — AI Assistant Context Handoff CLI](https://github.com/Maazkorejo/CTX-Bridge)
> *Cognitive memory and context bridge between AI coding tools (Cursor, Claude, Copilot, ChatGPT)*
- **Zero-Loss Context Handoff:** Captures active Git state, working tree diffs, timestamped session notes, and ASCII directory trees into paste-ready prompt handoffs and disk snapshots.
- **Smart Detection & Security Redaction:** Auto-detects 8+ project ecosystems (Python, JS/TS, Rust, Go, Java, C#, Ruby, PHP) and redacts sensitive credentials (`.env*`, `*.pem`, `*.key`, `credentials.json`).
- **Comprehensive Quality:** Built with Click/Typer CLI, rich terminal outputs, and robust `pytest` test suites verifying CLI subcommands and symlink loop protection.
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-Developer_Tools-7C3AED?style=flat-square&logoColor=white)
---
#### 🧠 [Self-Reflective RAG Engine](https://github.com/Maazkorejo/self-rag-engine)
> *Production-Grade Self-Reflective RAG Architecture (Asai et al., ICLR 2024)*
- **Four Reflection Checkpoints:** Dynamically critiques retrieval necessity (`Retrieve`), query relevance (`IsRel`), groundedness/hallucination risk (`IsSup`), and answer utility (`IsUse`) using **Groq LLaMA 3.3 70B**.
- **Dense Vector Search:** Integrated Supabase `pgvector` with local `sentence-transformers` embeddings for sub-second retrieval.
- **100% Test Coverage:** Containerized with Docker, rate-limited via Flask-Limiter with SHA-256 API authentication, Swagger/OpenAPI docs, and **46 pytest test suites at 100% code coverage**.
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_LLaMA_3.3_70B-F55036?style=flat-square&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase_pgvector-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-100%25_Coverage-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
---
#### 🦇 [Alfred — Personal AI Operating Assistant](https://github.com/Maazkorejo/Alfred-Personal-Assistant) — *[Live Demo](https://alfred-personal-assistant.vercel.app)*
> *Autonomous agentic assistant with multi-tool calling & persistent vector memory*
- **Agentic Workflow:** Architected an assistant integrating 14 distinct tools (Email, Calendar, Weather, Browser automation) via a custom two-LLM-call tool-calling pipeline.
- **Real-Time Reasoning & Voice:** Built streaming socket chat with live reasoning traces, voice I/O via Piper TTS, and an FFT-based spectral clap-to-wake detector.
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral_AI-FF7000?style=flat-square&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL+pgvector-316192?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
---
#### 🧪 [llm-eval-kit — Offline LLM Evaluation Library](https://github.com/Inference-LAB/llm-eval-kit) — *[PyPI Package](https://pypi.org/project/llm-eval-kit)*
> *Lightweight, deterministic evaluation library without costly LLM-as-a-judge API calls*
- Built during the **INFERENCE Lab Fellowship (Cohort 01)** to evaluate LLM outputs offline across 4 criteria: **Factual Grounding**, **Question Relevance**, **Refusal Detection**, and **Completeness**.
- Utilizes local `sentence-transformers` (`all-MiniLM-L6-v2`) with thread-safe singleton model caching and strict numeric mismatch verification.
![Python](https://img.shields.io/badge/Python-PyPI_Package-3776AB?style=flat-square&logo=python&logoColor=white)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Pytest](https://img.shields.io/badge/Pytest-Tested-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
---
### 💼 Professional Experience
* **Research/Implementation Engineer** — *INFERENCE Lab Fellowship (Cohort 01)* · *Jul 2026 – Present*  
  Selected among 130+ applicants to design core evaluation modules for `llm-eval-kit`. Authored Section 3 (Technical Approach) of the design document and lead offline embedding experiments.
* **Back-End AI Engineering Intern** — *FlyRank.ai* · *Completed*  
  Delivered 5 core production assignments: high-resilience web scraping pipelines, JWT authentication, multi-container Docker deployments, and PostgreSQL/OpenAPI backends.  
  📜 **[Verify Certificate (FR-D11-FA8DB-52256)](https://internship.flyrank.ai/verify?id=FR-D11-FA8DB-52256)** · 📄 **[CEO Recommendation Letter](https://internship.flyrank.ai/verify?id=FR-D10-4A2D2-7F7FF)** · 📊 **[Director Evaluation Report](https://internship.flyrank.ai/verify?id=FR-D8-2C53C-C9AA4)**
* **AI Developer Intern** — *Nebulark* · *Jul 2026 – Present*  
  Contributing to Intelligent Document Processing (IDP) platform design, OCR pipeline evaluations (Mistral OCR, Docling, PaddleOCR), and provider-registry architectures.
* **Cloud Computing Intern** — *PITP–MUET (Govt of Sindh)* · *Mar – May 2026*  
  Delivered a full-stack Flask + PostgreSQL + Railway platform with CI/CD; reduced lab environment setup time by ~30% through automated VM scripting.
---
### 🛠️ Tech Stack
<table>
<tr>
<td align="center" width="20%"><strong>AI & LLMs</strong></td>
<td>
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-7C3AED?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Microsoft_AutoGen-0078D4?style=flat-square&logo=microsoft&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Mistral_AI-FF7000?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq_LLaMA_3.3-F55036?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white"/>
</td>
</tr>
<tr>
<td align="center"><strong>Backend & Cloud</strong></td>
<td>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white"/>
  <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swagger%2FOpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
</td>
</tr>
<tr>
<td align="center"><strong>Testing & ML</strong></td>
<td>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/SHAP-Explainability-blue?style=flat-square"/>
</td>
</tr>
<tr>
<td align="center"><strong>Frontend</strong></td>
<td>
  <img src="https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript%2FJavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</td>
</tr>
</table>
---
### 📜 Verified Credentials & Honors
| Issuer | Credential |
|---|---|
| 🟠 **Anthropic ×12** | Model Context Protocol (MCP) · Claude API · Claude Code in Action · Introduction to Agent Skills · Introduction to Subagents · AI Fluency: Framework & Foundations · Claude 101 |
| 🏅 **HEC / NAVTTC** | Top Participant — ACT AI SkillBridge (2026) |
| 🔵 **McKinsey.org** | McKinsey Forward (Jun 2026) |
| 🔵 **IBM SkillsBuild** | Cybersecurity Fundamentals · Protecting a Device with Malwarebytes |
| 🔶 **Forage** | Mastercard · Datacom (Job Simulations) |
| 🟣 **Cambridge IQ / UniAthena** | Python Programming (×4) |
---
### 📊 GitHub Stats
<div align="center">
![Maaz's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Maazkorejo&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Maazkorejo&layout=compact&theme=tokyonight&hide_border=true)
[![GitHub Streak](https://streak-stats.demolab.com?user=Maazkorejo&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)
</div>
---
### 🤝 Connect & Collaborate
<div align="center">
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-maaz-korejo-1677a9267)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Maazkorejo)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maazkorejo00@gmail.com)
*Open to AI Engineering roles, backend opportunities, and open-source collaborations.*
⭐ **Star a repo if my work caught your eye!** ⭐
<img src="https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg" width="100%"/>
</div>
