<div align="center">
  <a href="https://danieldeshmukh.netlify.app/">
    <img src="assets/banner-image.png" alt="Daniel Deshmukh | AI Engineer" width="100%" />
  </a>
</div>

<br/>

<div align="center">
  <a href="https://user-badge.committers.top/india_private/danieldeshmukh">
    <img src="https://user-badge.committers.top/india_private/danieldeshmukh.svg" alt="committers.top badge" />
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=danieldeshmukh&label=Profile%20views&color=6366f1&style=flat-square" alt="profile views" />
  &nbsp;
  <img src="https://img.shields.io/badge/Open%20to%20Work-AI%20Engineer-6366f1?style=flat-square" />
</div>

<br/>

<h1 align="center">Daniel Deshmukh</h1>

<p align="center">
  <strong>I build systems that reason — autonomous agents, RAG pipelines, and production AI.</strong><br/>
  <sub>Mumbai · CS Graduate, Mumbai University · Targeting Germany & Abu Dhabi</sub>
</p>

<p align="center">
  <sub><b>Currently:</b> Fine-tuning Mistral 7B on Indian statutory law (THEMIS) · Targeting AI Engineer roles in Germany & Abu Dhabi</sub>
</p>

<br/>

---

## What I'm Building

<details open>
<summary><b>autobot-swarm</b> &nbsp;·&nbsp; <a href="https://github.com/DanielDeshmukh/autobots">GitHub</a> &nbsp;·&nbsp; <img src="https://img.shields.io/pypi/v/autobot-swarm?color=6366f1&label=PyPI&style=flat-square" /> &nbsp;·&nbsp; <img src="https://img.shields.io/github/stars/DanielDeshmukh/autobots?style=flat-square&color=6366f1&label=stars" /></summary>

<br/>

Multi-agent CLI for NVIDIA NIM orchestration, published on PyPI.

| Detail | Value |
|---|---|
| Tests | 465+ passing |
| Models discovered | 120 live from NVIDIA catalog |
| Skill files | 17 integrated |
| Version | v0.1.9 → v0.2.0 in progress |

```bash
pip install autobot-swarm
autobot-swarm --help
```

</details>

---

<details>
<summary><b>THEMIS</b> &nbsp;·&nbsp; <a href="https://github.com/DanielDeshmukh/themis">GitHub</a> &nbsp;·&nbsp; LoRA Fine-tune · Mistral 7B on Indian Statutory Law &nbsp;·&nbsp; <img src="https://img.shields.io/github/stars/DanielDeshmukh/themis?style=flat-square&color=6366f1&label=stars" /></summary>

<br/>

LoRA/QLoRA fine-tune of Mistral 7B Instruct v0.3 on Indian statutory law — hands-on fine-tuning beyond API wrapping.

| Detail | Value |
|---|---|
| Base model | Mistral 7B Instruct v0.3 |
| Method | LoRA · QLoRA |
| Domain | Indian statutory law (IPC, BNS 2023, CrPC) |
| Training | Kaggle T4 GPU · batch size 1 · seq len 1024 |
| Status | Training in progress |

</details>

---

<details>
<summary><b>AETHER</b> &nbsp;·&nbsp; <a href="https://github.com/DanielDeshmukh/aether">GitHub</a> &nbsp;·&nbsp; Autonomous Pentest Platform &nbsp;·&nbsp; <img src="https://img.shields.io/github/stars/DanielDeshmukh/aether?style=flat-square&color=6366f1&label=stars" /></summary>

<br/>

LangGraph-powered agentic reasoning loop for autonomous security audits, with browser-native recon via Playwright.

| Detail | Value |
|---|---|
| Stack | LangGraph · Playwright · Gemini · Claude |
| Architecture | Multi-step agentic loop: recon → vulnerability scan → exploit → report |
| Recon | Browser automation via Playwright for live target interaction |
| Output | Structured audit report with findings and severity classification |

</details>

---

<details>
<summary><b>HECTOR</b> &nbsp;·&nbsp; <a href="https://github.com/DanielDeshmukh/Hector">GitHub</a> &nbsp;·&nbsp; Indian Legal RAG Engine &nbsp;·&nbsp; <img src="https://img.shields.io/github/stars/DanielDeshmukh/Hector?style=flat-square&color=6366f1&label=stars" /></summary>

<br/>

Chain-of-Verification RAG over Indian statutory law, with IPC to BNS 2023 mapping built in.

| Detail | Value |
|---|---|
| Stack | FastAPI · Next.js · LangGraph · Qdrant |
| Protocol | Chain-of-Verification (CoVe) |
| Coverage | IPC → BNS 2023 full mapping |
| Use case | Legal decision support & document retrieval |

</details>

---

<details>
<summary><b>Ella</b> &nbsp;·&nbsp; <a href="https://github.com/DanielDeshmukh/ella">GitHub</a> &nbsp;·&nbsp; Medical Triage RAG Engine &nbsp;·&nbsp; <img src="https://img.shields.io/github/stars/DanielDeshmukh/ella?style=flat-square&color=6366f1&label=stars" /></summary>

<br/>

Clinical-grade RAG with a Hard-RAG protocol providing hallucination guardrails for medical queries.

| Detail | Value |
|---|---|
| Stack | LangGraph · FastAPI · Qdrant |
| Protocol | Hard-RAG (citation-locked retrieval) |
| Use case | Patient triage & clinical decision support |

</details>

---

<details>
<summary><b>babujichaay.com</b> &nbsp;·&nbsp; <a href="https://babujichaay.com">Live</a> &nbsp;·&nbsp; Production POS System</summary>

<br/>

Café POS running in production since July 2024, with real users and real transactions.

| Detail | Value |
|---|---|
| Stack | React · Node.js · Supabase · Capacitor |
| Platform | Web + Android APK |
| Status | Live since July 2024 |

</details>

<br/>

---

## Stack

<table>
  <tr>
    <td align="center" width="140"><b>AI & Agents</b></td>
    <td>
      <img src="https://img.shields.io/badge/LangGraph-1c1c1c?style=flat-square&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/LangChain-1c1c1c?style=flat-square&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white" />
      <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" />
      <img src="https://img.shields.io/badge/NVIDIA%20NIM-76B900?style=flat-square&logo=nvidia&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,python&theme=dark" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind&theme=dark" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Data & Storage</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=postgres,supabase&theme=dark" />
      <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
      <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>DevOps</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=docker,git,netlify,postman&theme=dark" />
    </td>
  </tr>
</table>

<br/>

---

## GitHub Activity

<div>
  <img src="https://streak-stats.demolab.com/?user=DanielDeshmukh&theme=tokyonight&border_radius=8" alt="GitHub Streak" height="165"/>
</div>
<br/>
<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api/?username=DanielDeshmukh&show_icons=true&theme=tokyonight&hide=contribs&border_radius=8" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DanielDeshmukh&layout=compact&theme=tokyonight&border_radius=8&count_private=true" alt="Top languages" />
</p>

<br/>

### Repositories by stars

All public repositories, ranked by stars collected.

| Repository | Stars | Description |
|---|---|---|
| [awesome-nvidia-nim](https://github.com/DanielDeshmukh/awesome-nvidia-nim) | 6 | Curated list of resources for building with NVIDIA NIM inference microservices |
| [github-profile-score](https://github.com/DanielDeshmukh/github-profile-score) | 3 | Embeddable job-readiness scorer for GitHub profiles |
| [autobot-swarm](https://github.com/DanielDeshmukh/autobots) | 3 | Decentralized multi-agent swarm powered by NVIDIA NIM, published on PyPI |
| [themis](https://github.com/DanielDeshmukh/themis) | 2 | Domain-specific LLM fine-tuned on Indian statutory law |
| [aether](https://github.com/DanielDeshmukh/aether) | 1 | Autonomous pentest platform with agentic reasoning loop |
| [Hector](https://github.com/DanielDeshmukh/Hector) | 1 | Hard-RAG legal intelligence system for Indian law, IPC to BNS mapping |
| [proteus](https://github.com/DanielDeshmukh/proteus) | 1 | JD-aware application toolkit with a five-agent NVIDIA NIM pipeline |
| [sportz-websockets](https://github.com/DanielDeshmukh/sportz-websockets) | 1 | Express + Postgres live match commentary via WebSocket |
| [Portfolio](https://github.com/DanielDeshmukh/Portfolio) | 0 | Full-stack developer portfolio |
| [ella](https://github.com/DanielDeshmukh/ella) | 0 | RAG-based agentic core for medical telephony and patient triage |
| [TradeX](https://github.com/DanielDeshmukh/TradeX) | 0 | AI-powered trading platform for new investors |
| [BabujiChaay-website](https://github.com/DanielDeshmukh/BabujiChaay-website) | 0 | Production café website |
| [Babuji-Chaay](https://github.com/DanielDeshmukh/Babuji-Chaay) | 0 | POS and inventory management system for cafés |
| [Interior-Designs-Template](https://github.com/DanielDeshmukh/Interior-Designs-Template) | 0 | Portfolio site template for interior designers |

<br/>

---

## Certifications

<details>
<summary>View 13+ certifications across AI, ML, and CS fundamentals</summary>

<br/>

| Certification | Issuer |
|---|---|
| Claude with Anthropic API · Claude Code 101 · Claude Code in Action | Anthropic Academy |
| Introduction to MCP · MCP Advanced Topics | Anthropic Academy |
| Introduction to Agent Skills · Introduction to Sub Agents | Anthropic Academy |
| CS50 AI with Python · CS50 Databases with SQL | Harvard |
| JavaScript Algorithms & Data Structures · Front End Libraries · Responsive Web Design | freeCodeCamp |
| Samsung Innovation (GitHub Copilot Workshop) | Samsung |

</details>

<br/>

---

## Connect

<div align="center">
  <a href="https://linkedin.com/in/daniel-deshmukh-7b08602b2">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:deshmukhdaniel2005@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://danieldeshmukh.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-6366f1?style=for-the-badge&logo=netlify&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://pypi.org/user/danieldeshmukh">
    <img src="https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white" />
  </a>
</div>
