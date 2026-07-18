<div align="center">

<!-- Header -->
<h1>
  Hey <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30" /> I'm Sven
</h1>

<!-- Typing animation -->
<a href="https://github.com/AlsoTheZv3n">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=1F6FEB&center=true&vCenter=true&width=760&lines=AI+%26+ML+Engineer+%7C+Full-Stack;Transformers+from+scratch+in+C%2B%2B%2FCUDA;RAG+%26+agents+that+cite+their+sources;17+merged+PRs+in+upstream+open+source" alt="Typing SVG" />
</a>

<br/><br/>

<!-- Contact -->
<a href="mailto:sweidenmann@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
</a>
<a href="https://www.kaggle.com/svenweidenmann">
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</a>
<!-- TODO: paste your LinkedIn URL here and uncomment
<a href="https://www.linkedin.com/in/YOUR-HANDLE">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
-->

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=AlsoTheZv3n&style=for-the-badge&color=1f6feb&label=PROFILE+VIEWS)

</div>

---

## 🧑‍💻 About Me

- 🔬 I build AI systems **down to the kernel** — a modern decoder-only transformer written from scratch in C++/CUDA, no PyTorch, no framework
- 🧬 Currently building **evidence-grounded tooling for oncology research** on ChEMBL, ClinicalTrials.gov, Open Targets and PubMed
- 🌍 **17 merged pull requests** in upstream open source — Dify, Webbrain, WorldWideView — with open PRs at Scanpy, Excalidraw and Infisical
- 🏗️ Backend depth: **Java 21 / Spring Boot**, **FastAPI**, PostgreSQL + pgvector, Row-Level Security, multi-tenancy
- 🇨🇭 Based in Aargau, Switzerland — open to **AI / ML Engineer** and **Full-Stack** roles

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [🧠 Modern LLM from Scratch](https://github.com/AlsoTheZv3n/modern-llm-v1)

A decoder-only transformer in **raw C++/CUDA** — no PyTorch, no abstractions. RoPE, RMSNorm, SwiGLU, GQA, QK-Norm, BF16 mixed precision, gradient checkpointing, and a hand-written **Flash-Attention forward *and* backward** pass. Trained on FineWeb-Edu, monitored by a C# WPF live-loss GUI.

`C++` `CUDA` `Transformers` `Systems ML`

</td>
<td width="50%" valign="top">

### [🧬 H2H — Sourced Cancer Drug Evidence](https://github.com/AlsoTheZv3n/h2h-research-v2)

One sourced brief per oncology drug — structure, binding, mechanism and clinical status — joined across **ChEMBL, ClinicalTrials.gov, Open Targets and PubMed**. Every fact carries its source and retrieval date; gaps are shown honestly instead of hallucinated.

`FastAPI` `PostgreSQL` `Redis` `React 19` `TypeScript`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [📐 Predictive Coding from Scratch](https://github.com/AlsoTheZv3n/PCN-self-improvement-research)

A biologically plausible backprop alternative with **purely local learning rules**, plus a fused **CUDA settling kernel** verified to ~1e-6. Fair PC-vs-BP study with multi-seed confidence intervals — thesis PDF and reproducible figures in the repo.

`PyTorch` `CUDA` `Research` `Statistics`

</td>
<td width="50%" valign="top">

### [🕸️ NEXO Ontology Engine](https://github.com/AlsoTheZv3n/ontology-next)

Multi-tenant ontology platform: typed objects, entity resolution, lineage, semantic search over pgvector, LLM agent tools, CDC with DLQ, and a GDPR audit/erasure layer. **Flyway V1–V31**, Row-Level Security, AES-256-GCM, Testcontainers.

`Java 21` `Spring Boot` `GraphQL` `pgvector` `RLS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🎙️ Local Voice IT Agent](https://github.com/AlsoTheZv3n/Voice-LLM-v1)

A fully **offline** voice support agent — no cloud API. Microphone → faster-whisper → Qwen2.5-7B (4-bit, tool calling) → Piper TTS → browser, over a FastAPI WebSocket, with pgvector + HNSW retrieval behind it.

`FastAPI` `Qwen2.5` `Whisper` `pgvector`

</td>
<td width="50%" valign="top">

### [🛡️ SecureSync](https://github.com/AlsoTheZv3n/securesync)

Multi-tenant **security-audit platform** for MSPs: orchestrates OpenVAS, OWASP ZAP, Nuclei and Wazuh, de-duplicates findings through DefectDojo, enriches with **EPSS** and **HIBP**, and ships white-labelled PDF reports on a per-tenant schedule.

`Python` `Multi-tenant` `Security` `RBAC`

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

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### Frameworks
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white)

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
![MSSQL](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Automation & Integration
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Rewst](https://img.shields.io/badge/Rewst-6366F1?style=for-the-badge)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![Microsoft Graph](https://img.shields.io/badge/MS_Graph-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

</div>

---

## 🎓 Certifications

<div align="center">

![AI-103](https://img.shields.io/badge/AI--103-Azure_AI_Apps_%26_Agents_Developer_Associate-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AI-900](https://img.shields.io/badge/AI--900-Azure_AI_Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AZ-900](https://img.shields.io/badge/AZ--900-Azure_Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://streak-stats.demolab.com?user=AlsoTheZv3n&theme=github-dark-blue&hide_border=true&background=0d1117&ring=1f6feb&fire=1f6feb&currStreakLabel=1f6feb" alt="GitHub Streak" />

<br/><br/>

<a href="https://github.com/AlsoTheZv3n">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AlsoTheZv3n&theme=github-compact&hide_border=true&bg_color=0D1117&color=C9D1D9&line=1F6FEB&point=1F6FEB&area=true&area_color=1F6FEB" alt="Activity Graph" width="98%" />
</a>

</div>

---

<div align="center">

*Always up for a conversation about AI systems, low-level ML, or open-source collaboration.*

<br/>

<a href="mailto:sweidenmann@gmail.com">sweidenmann@gmail.com</a> · <a href="https://www.kaggle.com/svenweidenmann">Kaggle</a>

<br/><br/>

<sub>⭐ From [AlsoTheZv3n](https://github.com/AlsoTheZv3n)</sub>

</div>
