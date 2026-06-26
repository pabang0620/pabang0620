# Hi, I'm Wonho Lee 👋

**Full-Stack Developer** based in South Korea

I build web applications end-to-end — from planning and design to deployment and ops. Spent 2.5 years as a one-man dev team inside an ad-tech startup, shipping over 10 internal tools while running infrastructure that handles **1.5M monthly visitors**. Now leading business projects at a mid-sized enterprise.

📧 lwh970924@gmail.com · [Nekolab](https://kingkle.co.kr)

---

## What I Do

- **Full Ownership** — Planning, design, development, deployment, and ops. I own the whole cycle.
- **AI-Augmented Development** — Using Claude Code as a daily dev tool, not just a toy.
- **DX & Automation** — I turn manual workflows (Excel, repetitive ops) into actual platforms people use every day.
- **Business Project Leading** — Writing proposals, leading cross-functional projects, bridging business and tech.

---

## Tech Stack

**Frontend:** React, Next.js, TypeScript, Tailwind CSS
**Backend:** Node.js, Express, Python, FastAPI
**Database:** PostgreSQL, MySQL, MongoDB
**Cloud & DevOps:** AWS (EC2, RDS, CloudFront, CloudWatch), Docker, Linux
**Automation:** Playwright, n8n, BeautifulSoup
**AI:** Claude API, Gemini API

---

## Work Experience

### Mid-sized Enterprise — Business Project Lead
*May 2026 - Present*

Leading business projects end-to-end — writing proposals, coordinating with stakeholders, and bridging business requirements with technical execution.

### Ad-tech Startup — Lead Developer
*Dec 2023 - May 2026*

Solo in-house developer. Built and operated 10+ internal tools from scratch while managing infrastructure single-handedly.

- **Landing Page Web Builder** — No-code builder so marketers can self-publish pages without engineering help
- **Landing Page Ops** — Built and operated pages serving **1.5M+ monthly visitors**; zero-downtime deployment via Docker
- **Lead Management Platform (CRM)** — Internal CRM for the call team handling 6,000+ leads/month
- **Ad Performance Dashboard** — Real-time ROAS and cross-platform ad analytics
- **DX Transformation** — Replaced company-wide Excel workflows with a unified platform used by all 30 employees daily
- **AWS Observability** — CloudWatch + Slack alerts; cut incident diagnosis time from hours to under 5 minutes

### Nekolab — Freelance Developer (Solo)
*2023 - Present · [kingkle.co.kr](https://kingkle.co.kr)*

Running my own freelance operation. Services: custom web apps, data crawling, automation/RPA, dashboards, and AI integration.

| Client | Project | Stack |
|--------|---------|-------|
| EdTech startup | Online coding education platform features (FE) | React |
| Smart farm startup | Real-time sensor monitoring dashboard | React, ECharts |
| B2B data firm | Webtoon platform + contest submission system | Node.js, React |
| Individual | SAT English exam platform (authoring, grading, management) | Full-stack |
| Individual | Vehicle log system (mileage, tax calc, ranking) | Full-stack |

---

## Side Projects

### [skill-fog](https://github.com/pabang0620/skill-fog) · [npm](https://www.npmjs.com/package/skill-fog)

Claude Code usage pattern detector — auto-generates skills, commands, and agents from repeated requests.

- Hooks into Claude Code sessions silently via Stop + SessionStart hooks
- Detects patterns across sessions (threshold: 3x / 2 sessions)
- Auto-proposes tools at next session start — nothing to remember
- Optional evaluator agent pass to improve generated skill quality
- Pure bash, no runtime required — `npm install -g skill-fog`

### [SNS Auto Poster](https://github.com/pabang0620/sns-auto-poster)

Automated social media posting with AI-generated content.

- Zero-cost self-hosted solution using Gemini API
- Multi-platform support (Threads, Instagram)
- Built with Python, Playwright, n8n

### Tech Blog (AI-Automated Daily Posts)

Running a technical blog where posts are auto-generated and published daily via an AI pipeline.
