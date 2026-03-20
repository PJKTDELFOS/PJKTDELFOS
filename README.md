# Hi, I'm Albert Pimentel França 👋

### Data Engineer & Python Developer · Rio de Janeiro, Brazil 🇧🇷

I build production data pipelines that solve real business problems. My background is unusual: 12 years as a government procurement specialist managing over **R$104M in public contracts** — and since April 2024, I've been turning that domain expertise into software.

The result is systems that non-developers couldn't build (because they don't know the code) and developers couldn't build well (because they don't know the domain).

---

## 🚀 What I'm Building

### [Appa Licitações](https://github.com/PJKTDELFOS/appa-licitacoes-showcase) — Production ETL Pipeline
A data pipeline that ingests **4,000–5,000 government procurement records daily** from Brazil's PNCP API, deduplicates via SHA-256 hashing, runs keyword matching with PostgreSQL regex operators, and delivers analysis-ready Excel reports to paying clients — automatically, every day.

```
PNCP API → Extract → Deduplicate → Transform → PostgreSQL → Deliver
              ↑                                      ↑
         Retry logic                          GIN index + pg_trgm
         Rate-limit aware                    Full-text search (PT)
         Graceful degradation                JSONB lifecycle mgmt
```

**Stack:** Python · PostgreSQL · Pandas · Django · psycopg2 · Resend API · Ubuntu VPS

---

## 🛠️ Tech Stack

**Data & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)

**Infrastructure & Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)

**Currently Learning**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## 📊 Core Competencies

```python
profile = {
    "domain_expertise": [
        "Government procurement (B2G) — 12 years",
        "Public contract management — R$104M+ managed",
        "Compliance & regulatory data (LGPD)",
    ],
    "data_engineering": [
        "ETL pipeline design & implementation",
        "API data collection at scale (4-5k records/day)",
        "PostgreSQL optimization (GIN, pg_trgm, JSONB)",
        "Idempotent ingestion patterns (SHA-256 dedup)",
        "Data quality validation (CNPJ/CPF checksum)",
        "Lead enrichment pipelines (BrasilAPI + CNPJ.ws)",
    ],
    "development": [
        "Django 5.2 (production systems)",
        "REST API consumption & error handling",
        "Role-based access control (RBAC)",
        "Secure secrets management",
        "Audit logging & observability",
    ],
    "currently_building": "Power BI dashboards on top of my procurement data",
}
```

---

## 📁 Featured Projects

| Project | Description | Stack |
|---|---|---|
| [Appa Showcase](https://github.com/PJKTDELFOS/appa-licitacoes-showcase) | Production ETL — 5k gov records/day | Python · PostgreSQL · Django |
| [posvendapamela](https://github.com/PJKTDELFOS/posvendapamela) | After-sales management system — GCP deploy | Django · PostgreSQL · LGPD |
| [Yosef](https://github.com/PJKTDELFOS/Yosef) | ERP system for small business | Django · Python · Multi-module |

---

## 🌍 What I'm Looking For

I'm open to remote opportunities in **Data Engineering** and **Data Analysis** — primarily in **Brazil** and **Portugal** 🇵🇹, and open to other European markets.

What I bring that most candidates don't: I understand the *business* behind the data. Twelve years operating in a highly regulated, document-heavy domain means I know what makes data trustworthy, auditable, and actionable — not just how to move it from A to B.

📩 **Let's connect:** [LinkedIn](https://www.linkedin.com/in/albert-pimentel-0a47a5338/) · albert.franca1992@gmail.com

---

## 📈 GitHub Stats

![Albert's GitHub stats](https://github-readme-stats.vercel.app/api?username=PJKTDELFOS&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PJKTDELFOS&layout=compact&hide_border=true&theme=default)

---

<div align="center">
  <i>"I didn't learn to code and then look for problems to solve.<br>
  I had a problem that needed solving — and learned to code to solve it."</i>
</div>
