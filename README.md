# Hi, I'm Siva Kumar Raju 👋

### AI Engineer · Multi-Agent Systems · Open-Source Contributor to Cognizant AI Lab

[

![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)

](https://linkedin.com/in/siva-kumar-raju-359157229)
[

![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

](mailto:rajusivakumar453@gmail.com)
[

![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

](https://github.com/Sivakumarraj)

---

## 🚀 About Me

I'm an **AI Engineer** building multi-agent systems in Python — LLM agents, deterministic tooling, and production-oriented automation.

- 🤝 **Open-source contributor to [Cognizant AI Lab's Neuro SAN Studio](https://github.com/cognizant-ai-lab/neuro-san-studio)** — two PRs merged to main, reviewed by their AVP of Neuro AI
- 🧠 Core design principle across all my work: **LLMs handle language, deterministic Python owns anything requiring exactness**
- ☁️ **Google Cloud Certified Professional Cloud Architect**
- 🎓 B.E. in ECE — The Oxford College of Engineering, Bangalore (2025)
- 📍 Bangalore, India · Open to Remote
- 📫 **rajusivakumar453@gmail.com**

---

## 🤝 Open-Source Contributions

### [cognizant-ai-lab/neuro-san-studio](https://github.com/cognizant-ai-lab/neuro-san-studio) · 850+ ⭐

Cognizant AI Lab's open-source multi-agent orchestration framework — the library behind the Cognizant Neuro AI Multi-Agent Accelerator.

| PR | Contribution | Status |
|---|---|---|
| [#1134](https://github.com/cognizant-ai-lab/neuro-san-studio/pull/1134) | Community Projects entry | ✅ Merged |
| [#1297](https://github.com/cognizant-ai-lab/neuro-san-studio/pull/1297) | Legacy Business-Rule Extractor added to Community Projects | ✅ Merged |

Worked within framework conventions: HOCON-declared agent networks, `manifest.hocon` registration, the `CodedTool` interface implementing `async_invoke()`, and AAOSA delegation.

---

## 🔥 Featured Projects

### 🏛️ [Neuro SAN Legacy Analyzer](https://github.com/Sivakumarraj/neuro-san-legacy-analyzer)
> **Listed in the official Neuro SAN Studio Community Projects** ([PR #1297](https://github.com/cognizant-ai-lab/neuro-san-studio/pull/1297)). A 6-agent Neuro SAN network that extracts business rules from legacy **COBOL, Java and PL/SQL** source and emits a modernization-ready specification.
>
> The CodedTool/LLM split is deliberate per agent: parsing COBOL paragraphs and tracing `CALL`/`IMPORT` edges are exact pattern matches, so they run as deterministic tools that cannot hallucinate. Business-rule interpretation, migration-risk assessment and spec generation need judgment, so they are LLM agents. **84 unit tests** cover the deterministic tools.

`Python` `Neuro SAN` `CodedTool` `async_invoke` `HOCON` `pytest` `COBOL` `Java` `PL/SQL` `Legacy Modernization`

---

### 🏢 [Antigravity Service Desk](https://github.com/Sivakumarraj/antigravity-service-desk)
> A **4-agent Neuro SAN network** converting raw, unstructured IT support email into schema-valid ServiceNow incident payloads, orchestrated by a front-man agent.
>
> A deterministic **PII-scrubbing CodedTool** runs *before* any LLM call, so personal data never enters a model context — a security boundary, not a post-processing step. **Pydantic v2** guardrails reject out-of-range LLM classifications at the schema edge rather than emitting malformed tickets.

`Python` `Neuro SAN` `Pydantic v2` `ServiceNow` `Multi-Agent` `PII Scrubbing` `HOCON` `ITSM` `Gemini`

---

### 💰 [Autonomous S2P Invoice Matcher](https://github.com/Sivakumarraj/autonomous-s2p-invoice-matcher)
> A **neuro-symbolic** 3-way invoice matcher (Purchase Order vs Goods Receipt vs Invoice) for Source-to-Pay pipelines.
>
> **Gemini 2.5 Flash** handles unstructured document intake into typed Pydantic schemas, while a **pure Python rule engine** executes all tolerance arithmetic — the LLM never performs financial computation. Includes an immutable SQLite audit trail with automated reconciliation reporting.

`Python` `Gemini 2.5 Flash` `Pydantic` `SQLite` `Neuro-Symbolic AI` `Rule Engine` `Source-to-Pay`

---

## 🛠️ Tech Stack

**AI / Agentic AI**



![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)




![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=chainlink&logoColor=white)




![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)




![Gemini](https://img.shields.io/badge/Gemini_2.5_Flash-4285F4?style=flat-square&logo=google&logoColor=white)




![Pydantic](https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square&logo=pydantic&logoColor=white)



**Backend & APIs**



![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)




![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white)




![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)



**Frontend**



![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)




![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)




![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)




![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)



**Databases & Cloud**



![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logo=database&logoColor=white)




![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)




![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)




![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)




![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)




![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)



---

## 📜 Certifications

| Certification | Issuer |
|---|---|
| 🏆 Professional Cloud Architect | Google Cloud |
| 🤖 Fundamental AI Concepts | Microsoft |
| 📊 Fundamentals of Machine Learning | Microsoft |
| 💻 Full Stack Developer | GeeksforGeeks |

---

## 📊 GitHub Stats



![Stats](https://github-readme-stats.vercel.app/api?username=Sivakumarraj&show_icons=true&theme=tokyonight&hide_border=true)




![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Sivakumarraj&layout=compact&theme=tokyonight&hide_border=true)



---

## 🤝 Let's Connect

> *"LLMs handle language. Deterministic code owns anything that has to be exact."*

⭐ Star my repos if you find the work interesting. Always open to collaborations, feedback, and AI engineering opportunities.

[

![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)

](https://linkedin.com/in/siva-kumar-raju-359157229)