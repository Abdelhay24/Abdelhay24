<h1 align="center">Hi 👋, I'm Abdelhay</h1>

<p align="center">
  <b>Full-Stack Software Engineer</b> · Django + Angular · I build systems that run real businesses
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Roles-2ea44f?style=for-the-badge" alt="Open to remote" />
  <img src="https://img.shields.io/badge/Timezone-GMT%20(UTC%2B0)-0a66c2?style=for-the-badge" alt="GMT" />
  <a href="https://www.linkedin.com/in/abd-lhay-127a72396/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:medabdlhay8@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## 🚀 About me

- 🏭 **Software Engineer at Kenz Mining SA.** I build and run the internal platforms a mining company uses every day: performance dashboards, executive reporting, and biometric meal ticketing.
- 🔁 **I own projects end to end.** I gather requirements with non-technical stakeholders, then handle design, backend, frontend, Docker deployment and support in production.
- 🔐 **Pursuing a Master's in Cybersecurity**, so security is part of how I design systems from the start.
- 🥈 **2nd place at Mauritania's largest AI hackathon.**
- 🌍 Arabic · French · English

---

## 🏗️ Featured work — all in production

### 📊 Kenz Management — Performance & Executive Dashboard Platform
`Django` `DRF` `Angular` `PostgreSQL` `Redis` `Docker`

The platform Kenz Mining SA uses to track production performance and executive decisions. It started as my internship project and grew into a system the company uses every day.

- **Executive Decision Tracking (EDT)** dashboard that turns management decisions into tracked, accountable actions
- **Automated PDF reports** (ReportLab + Matplotlib) written for executives with no technical background
- **Responsive UI with no CSS framework**, built on a custom four-breakpoint SCSS mixin system
- Containerized deployment with Docker, and caching with Redis

### 🍽️ Kenz Restaurant Ticketing — Biometric Meal Tickets
`ZKBio Time REST API` `ZKTeco terminals` `Print agent` `Job queue`

An employee scans a fingerprint or face at a ZKTeco terminal, and a meal ticket prints at the counter within seconds. Management sees exactly how many dishes were served per meal, per day, and to whom.

- Integrated with an existing **ZKBio Time** deployment: **3 terminals, ~600 enrolled employees, 200k+ attendance logs**
- **No duplicate or missed scans:** cursor-based polling every 5s, a deliberate overlap window, and a database unique constraint. Scan to ticket takes **3–8 seconds**.
- **Survives printer and network outages:** a pull-based print agent works through a job queue (`QUEUED → SENT → PRINTED / FAILED`)
- A **low-latency push proxy** (target under 1s) is built and ready. It fails closed and never fakes a success to the terminal.
- Design rule: the component on the unreliable network edge always starts the connection, and the server only answers.

### ♟️ [Hassaniya Chess](https://hassaniyachess.tech/) — Mauritania's Chess Community Platform
`Django` `Angular`

A platform for Mauritanian chess players, with **player profiles, ratings and tournaments** in one place.
🔗 **Live:** [hassaniyachess.tech](https://hassaniyachess.tech/)

### 🛰️ AI Hackathon — 🥈 2nd Place
`Python` `Machine Learning` `Satellite data`

Land-suitability analysis from satellite imagery at Mauritania's largest AI hackathon.

### 🧾 Odoo 19 Enterprise — ERP for real businesses
- **Restaurant & beach business (Deyina Beach SARL):** I connected point of sale to stock, so every dish sold deducts its ingredients automatically through Kit Bills of Materials. I also imported 70 inventory products and 25 bar recipes, fixed VAT (16%) and MRU currency rounding, and built a ReportLab audit report that proves each POS sale matches its stock movement.
- **HR system** built on Odoo.
- **Analytic accounting** architecture (analytic plans, accounts, distribution models), plus POS customization with Studio.

<sub>*Also worked with: AWLYG TECH · MIZAB OR*</sub>

---

## 🛠️ Tech stack

| | |
|---|---|
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white) |
| **Frontend** | ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **ERP** | ![Odoo](https://img.shields.io/badge/Odoo%2019-714B67?style=flat-square&logo=odoo&logoColor=white) |
| **Security** | ![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white) Secure development · Network analysis · Web vulnerabilities (SQLi, brute force) |
| **Also used** | Flask · Spring Boot · React · Flutter · PHP · MySQL · MongoDB · scikit-learn · OR-Tools |

---

## 📈 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Abdelhay24&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abdelhay24&layout=compact&hide_border=true" alt="Top languages" />
</p>

---

## 🎯 Beyond code

- ♟️ **Founding Nouackchott gambit Chess Club** in Nouakchott to grow chess locally
- 🤖 **Going deeper on AI engineering:** RAG, embeddings and agents

---

<p align="center">
  <b>Looking for a full-stack engineer who ships to production and owns it afterwards?</b><br/>
  📫 <a href="mailto:medabdlhay8@gmail.com">medabdlhay8@gmail.com</a> · <a href="https://www.linkedin.com/in/abd-lhay-127a72396/">LinkedIn</a>
</p>

<p align="center"><i>Code, learn, share — and make an impact.</i></p>
