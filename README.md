<h1 align="center">Hi, I'm Andrey Movshovich 👋</h1>
<h3 align="center">Fachinformatiker AE in Training — AI Automation & Agentic Workflows</h3>

<p align="center">
  Building AI-driven automation with n8n, LLM agents and voice interfaces during my internship at Flexcon IT.<br/>
  Background in C#/.NET and web development, now focused on practical AI integration, APIs and data pipelines.
</p>

<p align="center">
  <a href="https://github.com/sanmovar/Ticket-System">Featured Project</a> •
  <a href="mailto:andrey.movshovich@gmail.com">Email</a> •
  <a href="https://www.linkedin.com/in/andrey-movshovich/">LinkedIn</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sanmovar&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

---

## 👨‍💻 About Me

- 🎓 In training as **Fachinformatiker für Anwendungsentwicklung** (Umschulung)
- 🏢 On a 6-month **Praktikum at Flexcon IT** (since September 2026), focused on AI automation
- 🤖 Building workflows with **n8n**, LLM integrations and **ElevenLabs** voice agents
- 🔌 Connecting systems via REST APIs, webhooks and **Odoo** (ERP/CRM)
- 💻 Background in **C#**, **ASP.NET**, **JavaScript**, **TypeScript**
- 📚 Also exploring: **Lovable**, **Crawl4AI**, PowerShell automation

---

## 🛠️ Tech Stack

### AI & Automation
<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge" alt="ElevenLabs" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="Odoo" />
  <img src="https://img.shields.io/badge/Lovable-E63983?style=for-the-badge" alt="Lovable" />
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/ASP.NET-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET" />
  <img src="https://img.shields.io/badge/Entity%20Framework-68217A?style=for-the-badge&logo=.net&logoColor=white" alt="Entity Framework" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

### Frontend
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

### Tools & Platforms
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
</p>

---

## 📜 Certificates

- **n8n N8N101** — n8n fundamentals
- **n8n N8N102** — *Integrations: APIs & Connected Workflows* (October 2026)
- **n8n N8N103** — in progress

---

## 💼 Internship Projects — Flexcon IT

### Phone AI Agent for internal callers
Voice login via name and personal PIN (ElevenLabs + n8n), PINs stored only as hashes, lockout after three failed attempts, forced PIN change on first login. The agent works against our ERP/CRM (Odoo): creating and querying tickets, capturing contacts and leads, drafting quotes. Hardened with prompt-injection guardrails, per-call limits and a request-validating router. Logs auto-delete after 90 days; monitoring alerts on errors and slow responses, security tests documented.

### Automated Lead Research Pipeline
An n8n pipeline sourcing companies from open data (OpenStreetMap, Wikidata) and purchased datasets, crawling their websites, scoring each company against fixed criteria with an LLM, and finding contacts via web search. Every claim is checked against its source page or discarded. Result: several thousand vetted leads exported to Excel for sales outreach.

### Pipeline Monitoring
A dedicated workflow checks crawler health, the LLM interface, error rate and stuck jobs every 30 minutes, emailing on problems — the pipeline itself also verifies the crawler is reachable before each run.

### Data Provider Comparison
Evaluated data vendors on price, data quality and legal compliance as a decision brief for management.

### Live Sports Results (Lovable)
A web app built with Lovable showing all of today's games and live scores across football, basketball, tennis and ice hockey on one page — no league or sport selection needed upfront.

---

## 📌 Earlier Project

### Ticket System
A web-based ticket management system built with **ASP.NET Core MVC**.

**Key features**
- User authentication and role-based access
- CRUD functionality for tickets and projects
- Entity Framework Core for data access
- Structured admin and user workflows
- Clean and modern UI for practical internal processes

**Tech used**
- C#
- ASP.NET Core MVC
- Entity Framework Core
- SQL Server / PostgreSQL
- HTML, CSS, JavaScript

🔗 Repository: [sanmovar/Ticket-System](https://github.com/sanmovar/Ticket-System)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sanmovar&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanmovar&layout=compact&theme=transparent&hide_border=true" height="165" alt="Top languages" />
</p>

---

## 🎯 Current Focus

- Growing hands-on expertise in **AI workflow automation** (n8n, LLM agents, voice interfaces)
- Completing the **Fachinformatiker AE** retraining with a practical focus on API integration and data pipelines
- Working toward the **n8n N8N103** certification
- Keeping **.NET / ASP.NET** fundamentals sharp alongside the AI-automation work

---

## 📫 Contact

- Location: Germany
- Languages: German, Russian, English
- Currently: Praktikum at **Flexcon IT** (AI Automation) — open to discussing opportunities after the Umschulung
