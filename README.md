<div align="center">

<img src="assets/hero.svg" alt="Riya Vaishnav: Software Developer, GenAI and Full-Stack Engineer" width="100%"/>

<a href="https://www.linkedin.com/in/riya-vaishnav-1a799024a"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=FFA630&labelColor=C1440E"/></a>
<a href="mailto:kanhavaishnav2010@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=FFA630&labelColor=C1440E"/></a>
<a href="https://leetcode.com/u/riya_2005"><img src="https://img.shields.io/badge/LeetCode-0D1117?style=for-the-badge&logo=leetcode&logoColor=FFA630&labelColor=C1440E"/></a>

<img src="assets/divider.svg" width="100%"/>

</div>

## 👩‍💻 About

I'm a Computer Science graduate (B.Tech, 2026, CGPA 8.7) from Jaipur. I build software **end to end**: data model → REST API → UI → deployment.

My recent work sits where full-stack meets applied AI: a **vision-LLM radiology assistant** with a doctor-in-the-loop review flow, and an **LLM support agent** with RAG and a measured evaluation harness. I care about grounded outputs, safe failure behavior, and numbers that prove a system works.

```python
class Riya:
    role      = "Software Developer · GenAI & Full-Stack Engineer"
    based_in  = "Jaipur, India"
    strengths = ["DSA", "OOP", "DBMS", "REST APIs", "JWT auth", "LLM evaluation"]
    shipped   = ["Medical AI Assistant", "AppleSupport AI Agent", "SIH 2024 (Top 50/293)"]
    looking_for = "Entry-level SDE / Full-Stack / GenAI Engineer roles"
```

<div align="center"><img src="assets/divider.svg" width="100%"/></div>

## 🧰 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,js,html,css,react,nodejs,fastapi,tailwind&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,git,github,linux,vercel,vscode&theme=dark" />

</div>

**AI / ML:** 
![LLM Apps](https://img.shields.io/badge/LLM%20Applications-0D1117?style=flat-square&labelColor=C1440E)
![RAG](https://img.shields.io/badge/RAG-0D1117?style=flat-square&labelColor=C1440E)
![Agents](https://img.shields.io/badge/Agent%20Workflows-0D1117?style=flat-square&labelColor=C1440E)
![Prompting](https://img.shields.io/badge/Prompt%20%26%20Few--Shot-0D1117?style=flat-square&labelColor=C1440E)
![Gemini](https://img.shields.io/badge/Gemini%20Vision%20API-0D1117?style=flat-square&labelColor=C1440E)
![Embeddings](https://img.shields.io/badge/Embeddings%20%26%20Semantic%20Search-0D1117?style=flat-square&labelColor=C1440E)
![Eval](https://img.shields.io/badge/LLM%20Evaluation%20%7C%20LLM--as--a--Judge-0D1117?style=flat-square&labelColor=C1440E)
![HITL](https://img.shields.io/badge/Human--in--the--Loop-0D1117?style=flat-square&labelColor=C1440E)
![pandas](https://img.shields.io/badge/pandas-0D1117?style=flat-square&labelColor=C1440E)

**Engineering:** 
![REST](https://img.shields.io/badge/REST%20API%20Design-0D1117?style=flat-square&labelColor=C1440E)
![JWT](https://img.shields.io/badge/JWT%20Auth%20%2B%20RBAC-0D1117?style=flat-square&labelColor=C1440E)
![Schema](https://img.shields.io/badge/Schema%20Design%20%7C%20SQLAlchemy-0D1117?style=flat-square&labelColor=C1440E)
![Deploy](https://img.shields.io/badge/Render%20%C2%B7%20Vercel-0D1117?style=flat-square&labelColor=C1440E)

<div align="center"><img src="assets/divider.svg" width="100%"/></div>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🩻 Medical AI Assistant
**AI-powered radiology report generator**

A **vision LLM (Gemini)** drafts findings and an impression from an uploaded scan; a **doctor reviews, edits and approves** the final report. The AI never produces the final report.

- FastAPI + SQLAlchemy + PostgreSQL REST API
- **JWT (bcrypt) + role-based access**: only doctors finalize or delete
- Non-medical images are **flagged, not reported as "normal"**
- DRAFT/FINAL PDF export (ReportLab, Pillow)
- React + Tailwind UI; deployed on **Render + Vercel**

`React` `FastAPI` `PostgreSQL` `Gemini Vision` `JWT` `Tailwind`

[![Code](https://img.shields.io/badge/Source%20Code-0D1117?style=for-the-badge&logo=github&logoColor=FFA630&labelColor=C1440E)](https://github.com/Riya2005-vaishnav/medical-ai-assistant)
<!-- TODO: [![Live Demo](https://img.shields.io/badge/Live%20Demo-0D1117?style=for-the-badge&labelColor=FFA630)](YOUR_VERCEL_URL) -->

</td>
<td width="50%" valign="top">

### 🍎 AppleSupport AI Agent
**LLM-powered support triage and reply drafting**

Classifies messages into **7 intents** (discovered by clustering real customer messages), **retrieves similar past resolutions (RAG)**, drafts a grounded reply, and decides **auto-handle vs. escalate**, biased toward escalating when uncertain.

- Local embedding index (sentence-transformers), no API quota needed
- **206-row golden set**, plus keyword and majority-class baselines
- **LLM-as-a-judge** harness audited against human labels (75% agreement)
- Documented failure modes and a 15-entry decision log

`Python` `Gemini` `RAG` `sentence-transformers` `pandas`

[![Code](https://img.shields.io/badge/Source%20Code-0D1117?style=for-the-badge&logo=github&logoColor=FFA630&labelColor=C1440E)](https://github.com/Riya2005-vaishnav/Apple-Support-AI-Agent)

</td>
</tr>
</table>

<div align="center">

| 📊 AppleSupport AI Agent: golden-set results | Majority baseline | Keyword baseline | **Agent** |
|---|:---:|:---:|:---:|
| Intent accuracy | 30% | 50% | **84%** |
| Escalation accuracy | 60% | 72% | **94%** |

</div>

<table>
<tr>
<td width="50%" valign="top">

### 💊 Drug Inventory & Supply Chain Tracker
**Smart India Hackathon 2024: Top 50 of 293 teams**

Designed the relational MySQL schema and queries linking district hospitals to warehouses, **reducing stockouts by 25%**. Delivered a deployable full-stack system with a team.

`Python` `Java` `MySQL` `React.js`

</td>
<td width="50%" valign="top">

### ✈️ Travel Planner Web App
**Itinerary and budget management**

Node.js backend and React frontend for trip planning and budgets, with persistent storage in **MongoDB Atlas**.

`React.js` `Node.js` `MongoDB Atlas`

</td>
</tr>
</table>

<div align="center"><img src="assets/divider.svg" width="100%"/></div>

## 🧊 3D Contribution Graph

<div align="center">

<!-- Generated daily by .github/workflows/3d-contrib.yml. Appears after the first workflow run. -->
<img src="profile-3d-contrib/profile-night-view.svg" alt="3D contribution graph" width="100%"/>

</div>

## 📈 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Riya2005-vaishnav&show_icons=true&hide_border=true&bg_color=0D1117&title_color=FFA630&icon_color=C1440E&text_color=C9D1D9"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Riya2005-vaishnav&layout=compact&hide_border=true&bg_color=0D1117&title_color=FFA630&text_color=C9D1D9"/>
<br>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Riya2005-vaishnav&hide_border=true&background=0D1117&stroke=FFA630&ring=FFA630&fire=C1440E&currStreakLabel=FFA630&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=C9D1D9"/>

</div>

## 🏆 Achievements

- 🥇 **Smart India Hackathon 2024**: Top 50 of 293 teams (Certificate of Consolation)
- 📜 **IBM SkillBuild**: Python 101 for Data Science (Jul 2025)
- 📜 **NPTEL**: Soft Skills (2024)

<div align="center">

<img src="assets/footer.svg" width="100%"/>

</div>
