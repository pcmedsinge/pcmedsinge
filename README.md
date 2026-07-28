---

<h1 align="center">Hi, I'm Parag Medsinge 👋</h1>
<h3 align="center">Healthcare AI Leader · Technical & Delivery Leadership</h3>
<h4 align="center">Working at the intersection of Healthcare & AI — Agentic Clinical AI, Interoperability (FHIR · openEHR · MCP), Clinical NLP & Medical Imaging</h4>

<p align="center">
  <i>Healthcare AI leader and techno-functional product-development leader. Long career leading
  product development in healthcare IT, now working full-time and independently across
  <b>agentic clinical AI, interoperability (FHIR · openEHR · MCP), clinical NLP, and medical
  imaging AI</b> — building open-source reference implementations.<br/>
  I work in <b>AI-native, plan-mode-first workflows</b>, and I read, write, and review
  code throughout the build (now AI-augmented).</i>
</p>

<p align="center">
  <sub>
    🩺 Healthcare IT — long career &nbsp;·&nbsp;
    👥 Led teams of 30+ engineers across multiple geographies &nbsp;·&nbsp;
    🔌 FHIR (R4/R5, Da Vinci) · openEHR · MCP &nbsp;·&nbsp;
    🤖 LangGraph · LangChain · MONAI · MedGemma &nbsp;·&nbsp;
    🧠 AI-augmented builder (Copilot · Claude Code)
  </sub>
</p>

<p align="center">
  <a href="https://github.com/pcmedsinge"><img src="https://img.shields.io/github/followers/pcmedsinge?label=Follow&style=social" alt="GitHub followers"/></a>
  <img src="https://komarev.com/ghpvc/?username=pcmedsinge&color=blue&style=flat" alt="Profile views"/>
</p>

---

## 🩺 What I Do

I work at the intersection of **healthcare standards** and **applied AI** — designing systems, writing the specifications, and getting them into a working state end-to-end:

- 🧭 **Solutions Architecture for Clinical AI** — system design and reference implementations spanning data, agents, evals, and clinical-workflow fit
- 🔌 **Healthcare Interoperability** — **FHIR R4/R5** (with emphasis on the **payer side** — Da Vinci PAS, CRD, DTR, PDex, Plan-Net, Drug Formulary, BCDA), **openEHR** (CKM, EHRbase, AQL), **SMART-on-FHIR**, HL7
- 🤖 **Agentic Clinical AI** — multi-agent workflows on **LangGraph / LangChain**, **MCP** servers and clients for clinical data and policy reasoning, RAG over clinical and payer-policy corpora
- 🩻 **Radiology AI** — early-stage detection of lung disease and breast cancer; DICOM, MONAI, MedGemma, Orthanc PACS, OHIF *(current independent engagement, under NDA)*
- 👥 **Techno-functional leadership** — long career leading product development on **Sunrise Clinical Manager, Sunrise Surgery, and adjacent products** at Altera Digital Health (formerly Allscripts) with teams of **30+ engineers across multiple geographies**
- 🧠 **AI-native, plan-mode-first workflows** — daily driver of **GitHub Copilot** and **Claude Code** for plan-mode thinking, spec-driven builds, architecture review, and code review. I read, write, and review code throughout the build (now AI-augmented).

---

## � How I Lead

For most of my career I led product development on **Sunrise Clinical Manager, Sunrise Surgery, and adjacent products** at Altera Digital Health (formerly Allscripts) — teams of **30+ engineers across multiple geographies**, shipping into live clinical environments.

- **Delivery philosophy** — spec-first and AI-orchestrated, the same way the repos on this profile are built. Plan-mode before code, ADRs for non-trivial decisions, eval and review gates per slice.
- **Code-review and mentoring** — I stay close to the code through reviews and architecture conversations, and back engineers when their judgment is sound. The goal is teams that can decide without me in the room.
- **Hiring** — I optimise for judgment, domain curiosity, and figure-it-out ability over framework counts. Same bar I hold myself to.

Since March 2025, I have been working **full-time and independently**, including a current **fractional engineering-leadership engagement on a Radiology AI venture** focused on early-stage detection of lung disease and breast cancer (under NDA).

> *Open to Healthcare AI leadership roles — AI Technical Leader, AI Delivery / Program Leader, Solutions Architect, or Fractional / Advisory — where deep healthcare-IT domain expertise meets applied AI.*

---

## 🚀 Featured Projects

> Sorted by relevance, not date. See pinned repos below or my [full repository list](https://github.com/pcmedsinge?tab=repositories).

### 🤖 Agentic Clinical AI & MCP
| Project | Stack | What it does |
|---|---|---|
| **Prior-Auth Co-pilot** 🚧 *(flagship, in build)* | LangGraph · MCP · FHIR Da Vinci PAS/CRD/DTR | Agentic, FHIR-native Prior-Authorization co-pilot targeting the **CMS-0057 Jan 2027** mandate. Assembles clinical evidence, reasons over payer policy, drafts the PAS bundle, and explains the decision with citations. *Public roadmap coming Week 2.* |
| [fhir-mcp-suite](https://github.com/pcmedsinge/fhir-mcp-suite) ⭐ | Python · MCP | A suite of Model Context Protocol servers for FHIR — letting LLM agents query clinical data safely |
| [fhir-mapping-agent](https://github.com/pcmedsinge/fhir-mapping-agent) ⭐ | Python · LangChain | LLM agent for mapping arbitrary clinical data into FHIR resources |
| [bodhi_app](https://github.com/pcmedsinge/bodhi_app) ⭐ | FastAPI · React · Neo4j | **ClinIQ · BODHI** — clinical knowledge-graph app on the *Bharat Ontology for Disease & Healthcare Informatics* (Eka Care) |
| [openEHR_TrialSafety_TrialMatch](https://github.com/pcmedsinge/openEHR_TrialSafety_TrialMatch) | Python · GPT-4o · AQL | Agentic trial-safety screening and trial-matching over openEHR data with AQL |
| **Clinical LLM Quality Harness** 🚧 *(flagship #2, in build)* | Python · LangGraph · Evals | Eval & observability framework for clinical AI — three tracks: ambient-scribe note quality (hallucination, SOAP adherence, FHIR write-back), prior-auth reasoning quality, and clinical Q&A grounding. |

### 🏥 Healthcare Interoperability — FHIR & openEHR
| Project | Stack | What it does |
|---|---|---|
| [fhir-dqm-engine](https://github.com/pcmedsinge/fhir-dqm-engine) ⭐ 🆕 | TypeScript · NestJS | **Pramana** — FHIR-native CQL quality measure engine: runs HEDIS/CMS eCQMs against FHIR R4 data, produces a standards-compliant FHIR MeasureReport. **69.8% BP control rate** measured on a 279-patient synthetic cohort. AI care-gap layer in progress. |
| [FHIRPayerProvider_RCM_Knowledge](https://github.com/pcmedsinge/FHIRPayerProvider_RCM_Knowledge) | Docs · FHIR | Payer-side FHIR & RCM knowledge base — Da Vinci IGs, policy patterns, integration notes |
| [openEHR-trialcapture](https://github.com/pcmedsinge/openEHR-trialcapture) ⭐ | TypeScript · openEHR | Clinical trial data capture using openEHR archetypes |
| [healthcare-graphql-api](https://github.com/pcmedsinge/healthcare-graphql-api) ⭐ | .NET 8 · HotChocolate | Healthcare GraphQL API with JWT auth, caching, rate limiting, Docker |
| [python-healthcare-api-microservices](https://github.com/pcmedsinge/python-healthcare-api-microservices) ⭐ | Python | Healthcare API in a microservices pattern |
| [TEFCA-Knowledge](https://github.com/pcmedsinge/TEFCA-Knowledge) | Docs | A practitioner's hub for TEFCA + FHIR + Clinical AI |

### 🩻 Radiology & Medical Imaging AI
| Project | Stack | What it does |
|---|---|---|
| [pneumonia-monai](https://github.com/pcmedsinge/pneumonia-monai) 🚧 | Python · MONAI · DICOM | Pneumonia detection on chest images using MONAI |
| [RAdImageProcessing](https://github.com/pcmedsinge/RAdImageProcessing) 🚧 | Python · DICOM | Radiology image processing pipeline |

> Browse all repos by topic: [`#fhir`](https://github.com/pcmedsinge?tab=repositories) · [`#agentic-ai`](https://github.com/pcmedsinge?tab=repositories) · [`#mcp`](https://github.com/pcmedsinge?tab=repositories) · [`#langgraph`](https://github.com/pcmedsinge?tab=repositories) · [`#healthcare`](https://github.com/pcmedsinge?tab=repositories) · [`#openehr`](https://github.com/pcmedsinge?tab=repositories) · [`#clinical-ai`](https://github.com/pcmedsinge?tab=repositories)

---

## 🛠️ Tech I Use

**Languages**
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Backend & Cloud**
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Healthcare Standards**
![FHIR](https://img.shields.io/badge/FHIR-E60012?style=flat)
![openEHR](https://img.shields.io/badge/openEHR-007ACC?style=flat)
![HL7](https://img.shields.io/badge/HL7-005A9C?style=flat)
![DICOM](https://img.shields.io/badge/DICOM-4B0082?style=flat)
![SMART_on_FHIR](https://img.shields.io/badge/SMART--on--FHIR-FF6B35?style=flat)
![TEFCA](https://img.shields.io/badge/TEFCA-2E8B57?style=flat)
![CQL](https://img.shields.io/badge/CQL-8B0000?style=flat)
![HEDIS](https://img.shields.io/badge/HEDIS-2E4057?style=flat)

**AI / ML**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![MCP](https://img.shields.io/badge/MCP-purple?style=flat)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)
![MONAI](https://img.shields.io/badge/MONAI-00A0A0?style=flat)

**AI-Augmented Workflow** *(daily drivers)*
![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat&logo=githubcopilot&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Code-D97706?style=flat&logo=anthropic&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=flat&logo=openai&logoColor=white)
![Plan Mode](https://img.shields.io/badge/Plan--Mode%20Workflows-blueviolet?style=flat)

---

## � How I Build & Lead in 2026

My working assumption is that **plan-mode, spec-driven, AI-orchestrated workflows are now the senior norm** — not a quirk. Every repo on this profile is built this way, and this is how I expect the teams I lead to ship.

1. **Plan-mode first** — talk through the problem, constraints, and trade-offs with Claude Code or Copilot agent before writing a line of code. The plan is the artefact.
2. **Specification-driven** — design doc, sequence diagram, FHIR resource map, agent graph, or eval plan produced *with* the AI, then reviewed critically against domain context.
3. **Build in small slices** — each slice reviewed for correctness, security (OWASP), and clinical safety. AI as reviewer; judgment stays with me.
4. **Evals and documentation as first-class outputs** — every repo ships with a real README, measurable behaviour, and a clear status (WIP / Stable / Reference).

**As a leader**, my job is to set up the *quality gates* a team ships against — the spec rituals, eval bars, ADR cadence, and code-review standards — not to be the fastest typist in the room.

**For hiring conversations**: I'm strongest in **architecture rounds, system-design discussions, and walking through any of the repos on this profile**. If your loop is built around live algorithm whiteboarding, we're probably not the right fit — and that's a useful filter for both of us.

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pcmedsinge&show_icons=true&theme=default&hide_border=true&count_private=false" height="170" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pcmedsinge&layout=compact&theme=default&hide_border=true&langs_count=8" height="170" alt="Top Languages"/>
</p>

---

## 🔭 Currently Working On

- 🧭 **Prior-Auth Co-pilot** *(flagship #1, in build)* — agentic, FHIR-native PA co-pilot for the **CMS-0057 Jan 2027** mandate. Da Vinci PAS / CRD / DTR + policy reasoning + audit trail. Public roadmap and weekly slices in progress.
- 🧪 **Clinical LLM Quality Harness** *(flagship #2, in build)* — eval & observability framework across three tracks: ambient-scribe note quality, prior-auth reasoning quality, and clinical Q&A grounding.
- 🩻 **Radiology AI** *(NDA, ongoing)* — fractional engineering leadership on early-stage detection of lung disease and breast cancer; DICOM, MONAI, MedGemma, Orthanc PACS, OHIF.
- 🏗️ **`fhir-dqm-engine` (Pramana)** — care-gap API + AI layer on top of the CQL quality-measure engine; 69.8% BP control rate measured on a 279-patient synthetic cohort.
- 🛠️ **`fhir-mcp-suite`** — extending MCP server coverage for more FHIR resources; feeds the Prior-Auth flagship.

---

## 🤝 Let's Connect

- 💼 LinkedIn: <https://linkedin.com/in/paragmedsinge>
- 📧 Email: <paragmedsinge@yahoo.com>
- 🌍 Based in: Pune, Maharashtra, India · open to remote / hybrid worldwide
- 💬 *Open to Healthcare AI leadership roles — AI Technical Leader, AI Delivery / Program Leader, Solutions Architect, or Fractional / Advisory — where deep healthcare-IT domain expertise meets applied AI.*

---

<sub>⚡ <b>Note:</b> The repos on this profile are reference implementations and working prototypes built around real interoperability and clinical-AI problems — not tutorials. Each is clearly labelled WIP / Stable / Reference.</sub>
