<div align="center">

<!-- Header -->
<h1>
  Hey <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30" /> I'm Sven
</h1>

<!-- Typing animation -->
<a href="https://github.com/AlsoTheZv3n">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=1F6FEB&center=true&vCenter=true&width=760&lines=Software+Engineer+%7C+AI+%26+Full-Stack;Java+25+%E2%80%A2+Spring+Boot+%E2%80%A2+FastAPI+%E2%80%A2+React;Self-healing+automation+%26+AI+agents;17+merged+PRs+in+upstream+open+source;Microsoft+Certified%3A+AI-103+%E2%80%A2+AI-300+%E2%80%A2+DP-600" alt="Typing SVG" />
</a>

<br/><br/>

<!-- Contact -->
<a href="https://www.linkedin.com/in/sven-weidenmann-260a16235/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:sweidenmann@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
</a>
<a href="https://huggingface.co/Zv3n">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
</a>
<a href="https://www.kaggle.com/svenweidenmann">
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=AlsoTheZv3n&style=for-the-badge&color=1f6feb&label=PROFILE+VIEWS)

</div>

---

## 🧑‍💻 About Me

- 💼 **Freelance Software Engineer** — building automation and web platforms for Swiss SMEs, from a full operations platform for a taxi company (admin, driver and customer portals, live map, Swiss QR-bill, Stripe incl. TWINT) to AI-assisted workflows for a bakery & café
- 🤖 Previously at **BeSync AG**, Zurich — first as Automation Engineer, then Frontend & AI Developer: AI agents with **self-healing components** that detect and mitigate issues on their own, a cross-department KPI dashboard, and a SaaS that unifies several systems into one customer view
- 🏗️ Backend depth: **Java 25 / Spring Boot**, **FastAPI**, PostgreSQL + pgvector, Row-Level Security, multi-tenancy
- 🧬 Side projects in **ML & health tech** — local LLM fine-tuning, MLOps, and evidence-grounded tooling for oncology research
- 🌍 **17 merged pull requests** in upstream open source — Dify, Webbrain, WorldWideView — with open PRs at Scanpy, Excalidraw and Infisical
- 🇨🇭 Based in Aargau, Switzerland — open to **AI Engineering** and **Full-Stack** roles as well as freelance projects

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [💳 Receivables & Payment Matching for Swiss SMEs](https://github.com/AlsoTheZv3n/Debitoren--und-Zahlungsabgleich-f-r-Schweizer-KMU)

Issues **Swiss QR-bills**, matches incoming payments from **camt.054** files automatically and runs a multi-level dunning process — multi-tenant from day one. Modular Spring Modulith backend, Keycloak auth, an API contract checked in CI, and Playwright E2E tests against the full Compose stack.

`Java 25` `Spring Boot 4` `React 19` `PostgreSQL 18` `Keycloak`

</td>
<td width="50%" valign="top">

### [🏺 Kintsugi — Web Data That Repairs Itself](https://github.com/AlsoTheZv3n/Kintsugi)

Scraper → cleaning → versioned store → API. When a source changes its layout, the extractor is repaired automatically — value anchors, then a DOM diff, then an LLM that only sees the changed subtree and may only edit a schema-validated config. A fix ships only after it passes a gate against known-good pages; otherwise a human gets an incident with the evidence attached.

`Python` `FastAPI` `Playwright` `PostgreSQL` `LLM`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🎓 EduSovereign — Intelligent Tutoring System](https://github.com/AlsoTheZv3n/school-learn-agent)

A privacy-first tutoring system for schools, built for minors: a LangGraph teaching agent that explains and quizzes, an inspectable **Bayesian Knowledge Tracing** model per student, and a teacher view to verify and override. Isolation via Row-Level Security, PII anonymised before any LLM call, CH/EU data residency.

`FastAPI` `LangGraph` `pgvector` `React` `TypeScript`

</td>
<td width="50%" valign="top">

### [🩺 Clinical Dialogue Summarizer](https://github.com/AlsoTheZv3n/llm-training-medical-fine-tuning)

QLoRA fine-tune of **Qwen2.5-3B-Instruct** that turns doctor–patient dialogues into structured complaint summaries for the physician, served through Ollama's OpenAI-compatible API. The whole pipeline — data, training, serving, eval — runs on a single consumer GPU, so patient dialogues never leave the machine.

`PyTorch` `QLoRA` `Hugging Face` `Ollama`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🧾 TaxFlow — AI-Assisted Swiss Tax Return](https://github.com/AlsoTheZv3n/TaxFlow)

Prototype for the tax return of the canton of Aargau: uploaded documents run through a hybrid OCR pipeline — PdfPig → Tesseract → **Claude Vision** — and the extracted values land directly in a faithful replica of the official form. A rule-based advisor suggests optimisations.

`C#` `ASP.NET Core` `Claude Vision` `OCR`

</td>
<td width="50%" valign="top">

### [📈 Source-Verified Valuation Models](https://github.com/AlsoTheZv3n/finance-models-v1)

Valuation models and research theses for twelve listed companies. Every figure is read at runtime from the official filing and checked twice — not a single actual value is typed by hand. Shared mechanics are separated from per-company judgement, and each workbook and PDF is rebuilt from scripts.

`Python` `XBRL` `Valuation` `Reproducible Research`

</td>
</tr>
</table>
---

## 🌍 Open Source Contributions

Fixes and features shipped into projects I don't own:

| Project | Contribution | |
|---|---|---|
| **[Dify](https://github.com/langgenius/dify/pulls?q=is%3Apr+author%3AAlsoTheZv3n+is%3Amerged)** <br/> ![](https://img.shields.io/github/stars/langgenius/dify?style=flat-square&label=%E2%98%85&color=1f6feb) | Type-safety pass across the MCP, plugin, agent-runtime and moderation layers; `TypedDict` migration for credential verification | **11 merged** |
| **[Webbrain](https://github.com/webbrain-one/webbrain/pulls?q=is%3Apr+author%3AAlsoTheZv3n)** <br/> ![](https://img.shields.io/github/stars/webbrain-one/webbrain?style=flat-square&label=%E2%98%85&color=1f6feb) | `/export-with-traces` command; site adapter for Galaxus | **2 merged** |
| **[WorldWideView](https://github.com/silvertakana/worldwideview/pulls?q=is%3Apr+author%3AAlsoTheZv3n)** <br/> ![](https://img.shields.io/github/stars/silvertakana/worldwideview?style=flat-square&label=%E2%98%85&color=1f6feb) | Three Cesium hot-path performance wins; ESLint baseline + CI lint job; dependency audit; architecture docs | **4 merged** |
| **[Scanpy](https://github.com/scverse/scanpy/pull/4218)** (scverse) <br/> ![](https://img.shields.io/github/stars/scverse/scanpy?style=flat-square&label=%E2%98%85&color=1f6feb) | `min_cells` parameter for `dotplot` | open |
| **[Excalidraw](https://github.com/excalidraw/excalidraw/pull/11645)** <br/> ![](https://img.shields.io/github/stars/excalidraw/excalidraw?style=flat-square&label=%E2%98%85&color=1f6feb) | Preserve text-editor focus on window blur (Alt+Tab) | open |
| **[Infisical](https://github.com/Infisical/infisical/pulls?q=is%3Apr+author%3AAlsoTheZv3n)** <br/> ![](https://img.shields.io/github/stars/Infisical/infisical?style=flat-square&label=%E2%98%85&color=1f6feb) | PKI certificate-renewal response, distinct member counts, dotted secret references, project search filter, UI fix | 5 open |
| **[Agno](https://github.com/agno-agi/agno/pull/7339)** <br/> ![](https://img.shields.io/github/stars/agno-agi/agno?style=flat-square&label=%E2%98%85&color=1f6feb) | `N8nTools` toolkit — n8n workflow automation for multi-agent systems | open |

---

## 🛠️ Tech Stack

<div align="center">

### Languages — Proficient
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java_25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Languages — Intermediate
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-39457E?style=for-the-badge&logo=perl&logoColor=white)

### Frameworks
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white)
![Mojolicious](https://img.shields.io/badge/Mojolicious-CC0000?style=for-the-badge&logoColor=white)

### AI & Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

### Data
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MSSQL](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)

### Automation & Integration
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Rewst](https://img.shields.io/badge/Rewst-6366F1?style=for-the-badge)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![Microsoft Graph](https://img.shields.io/badge/MS_Graph-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

</div>

---

## 🎓 Certifications

<div align="center">

### Microsoft Certified — Associate
![AI-103](https://img.shields.io/badge/AI--103-Azure_AI_Apps_%26_Agents_Developer-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AI-300](https://img.shields.io/badge/AI--300-Machine_Learning_Operations_Engineer-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![DP-600](https://img.shields.io/badge/DP--600-Fabric_Analytics_Engineer-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

### Microsoft Certified — Fundamentals
![AI-900](https://img.shields.io/badge/AI--900-Azure_AI_Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AZ-900](https://img.shields.io/badge/AZ--900-Azure_Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

### NinjaOne
![NinjaOne Automation Specialist](https://img.shields.io/badge/NinjaOne-Certified_Automation_Specialist-1F2937?style=for-the-badge)
![NinjaOne Technician](https://img.shields.io/badge/NinjaOne-Certified_Technician_%28MSP%29-1F2937?style=for-the-badge)

</div>
---

## 📊 GitHub Analytics

<div align="center">

<img src="https://streak-stats.demolab.com?user=AlsoTheZv3n&theme=github-dark-blue&hide_border=true&background=0d1117&ring=1f6feb&fire=1f6feb&currStreakLabel=1f6feb" alt="GitHub Streak" />

<br/><br/>

<a href="https://github.com/AlsoTheZv3n">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AlsoTheZv3n/AlsoTheZv3n/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AlsoTheZv3n/AlsoTheZv3n/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/AlsoTheZv3n/AlsoTheZv3n/output/github-contribution-grid-snake-dark.svg" alt="Contribution graph" width="98%" />
  </picture>
</a>

</div>

---

<div align="center">

*Always up for a conversation about AI systems, automation, or open-source collaboration.*

<br/>

<a href="mailto:sweidenmann@gmail.com">sweidenmann@gmail.com</a> · <a href="https://www.linkedin.com/in/sven-weidenmann-260a16235/">LinkedIn</a> · <a href="https://huggingface.co/Zv3n">Hugging Face</a> · <a href="https://www.kaggle.com/svenweidenmann">Kaggle</a>

<br/><br/>

<sub>⭐ From [AlsoTheZv3n](https://github.com/AlsoTheZv3n)</sub>

</div>
