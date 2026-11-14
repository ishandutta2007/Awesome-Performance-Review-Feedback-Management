# Awesome-Performance-Review-Feedback-Management

# Awesome Performance Review & Feedback Management

> A curated list of top Performance Review and Feedback Management platforms — both SaaS/Hosted commercial HR suites and open-source alternatives for running reviews, collecting continuous feedback, and tracking employee growth.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Lattice](#lattice)
  - [Culture Amp](#culture-amp)
  - [15Five](#15five)
  - [Leapsome](#leapsome)
  - [Betterworks](#betterworks)
- [Open-Source Software](#-open-source-software)
  - [Horilla HRMS](#horilla-hrms)
  - [Check-Ins](#check-ins)
  - [Caliber](#caliber)
  - [PIX 360](#pix-360)
  - [EPMS](#epms)
  - [MintHCM](#minthcm)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Performance Review and Feedback Management platforms. These are not open-source but are included as reference points for feature comparison.

### Lattice
**Type:** Performance management with reviews, goals, and 1:1s
Lattice is one of the most widely adopted performance management platforms, covering performance reviews, 360 feedback, goal/OKR tracking, 1:1 meeting management, and engagement surveys. It is known for its clean interface and strong manager-enablement features. Pricing is per-seat with tiered plans.

### Culture Amp
**Type:** Employee experience with engagement and performance
Culture Amp specializes in employee engagement surveys and performance reviews, with a strong focus on people analytics and benchmarking. It is positioned for organizations wanting data-driven insights into employee experience alongside review workflows.

### 15Five
**Type:** Continuous performance management with weekly check-ins
15Five is built around weekly check-ins, OKRs, and continuous feedback rather than annual review cycles. It is positioned for managers wanting ongoing visibility into team sentiment and progress, with review features layered on top of the check-in cadence.

### Leapsome
**Type:** Performance and engagement with reviews and goals
Leapsome combines performance reviews, 360 feedback, goals/OKRs, and engagement surveys in a single platform. It is positioned as an all-in-one people enablement platform for mid-market organizations.

### Betterworks
**Type:** OKR and performance management
Betterworks focuses on OKR tracking and performance management, helping organizations align goals across teams and connect them to review cycles. It is positioned for enterprises wanting structured goal alignment alongside performance conversations.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Performance Review and Feedback Management tools. The open-source ecosystem is **fragmented** — most projects are either broad HR suites with performance modules, manager-focused tools, or early-stage review applications.

### Horilla HRMS
**Stack:** Python / Django / PostgreSQL | **License:** LGPL-2.1
Horilla is a comprehensive open-source HR management suite with a dedicated **Performance Management** module covering goal setting, reviews, and continuous feedback . Key features include:
- **Performance Management**: goal setting, reviews, and continuous feedback 
- **Employee Management** with LDAP integration 
- **Recruitment**, onboarding/offboarding, attendance, leave, payroll, and asset management 
- **Helpdesk and project management** modules 
- **REST API** with token-based authentication, and integrations with LDAP, Google Meet, Google Drive, and WhatsApp 

Deploys via Docker (`docker pull horilla/horilla-hr:2.4.0`) with a documented Compose file, or from source with Python 3.12–3.14 . Security features include permission-based access control, optional two-factor login, brute-force protection, and audit trails . The project is actively developed with a stable 2.0 branch and a dev/v2.0 integration branch .
**Best for:** Organizations wanting a comprehensive open-source HR suite where performance reviews are one module within a broader employee lifecycle platform, accepting the broader Django/PostgreSQL deployment.

### Check-Ins
**Stack:** Micronaut / React / Google Cloud or on-prem | **License:** Open Source
Check-Ins is a team engagement platform from Object Computing with **Performance Reviews and Reporting**, **Feedback Management**, and **Pulse Surveys** . Key features include:
- **Performance Reviews and Reporting**: evaluate team performance as frequently as desired 
- **Feedback Management**: give employees access to feedback for skill growth 
- **Pulse Surveys**: find out how the team is feeling about work 
- **Mentor Program Management**: support and manage employee touchpoints with a dedicated mentor 
- **Public Kudos**: celebrate wins publicly, with Slack integration 
- **Employee Profiles**: manage skills, certifications, and organizations 

Built with Micronaut and React, deployable on-premises or on Google Cloud Platform, with Google SSO integration .
**Best for:** Teams wanting a focused engagement and performance platform with mentor program support and public recognition, accepting the Micronaut/React stack.

### Caliber
**Stack:** Web application | **License:** Open Source
Caliber is a lightweight web platform for **engineering managers** to run day-to-day management work in one place, with a strong focus on **performance conversations** . Key features include:
- **People & Teams**: manage team members with seniority, roles, and start dates, with attention signals per person (overdue tasks, no recent 1:1, ageing follow-ups) 
- **Log evidence per person** for performance conversations 
- **Meetings**: structured templates for 1:1s, Team Sync, Retro, Planning, Review, Standup, with action item extraction 
- **Tasks & Follow-ups**: Kanban and backlog views, tracking commitments made to team members 
- **Career Framework & Goals**: track career goals, gap analysis, focus distributions, achievements, and profile notes 
- **Weekly Review & Summary**: structured checklist with optional AI-assisted summary generation 

It is explicitly designed around how management work actually happens—ad-hoc meetings, regular 1:1s, ongoing feedback, and small actions that need follow-through .
**Best for:** Engineering managers wanting a lightweight tool focused on 1:1s, evidence logging, and career conversations rather than formal HR review cycles.

### PIX 360
**Stack:** Ruby | **License:** AGPL-3.0
PIX 360 is a French application for managing **360-degree evaluations** in an organization . Features include:
- **Google SSO** to restrict access to organization members 
- **Email-based evaluation request** sending 
- **Notification** when a new evaluation is received 
- **Storage of received and given evaluations** 
- **End-to-end encrypted evaluations** 

The project has 6 stars and 7 open issues, with last activity approximately 7 months ago . It is a **focused 360 review tool** rather than a full performance management suite.
**Best for:** Organizations wanting a self-hosted, privacy-focused 360 evaluation tool, accepting a smaller community and narrower scope.

### EPMS
**Stack:** React / Node.js / MongoDB | **License:** MIT
EPMS (Employee Performance Management System) is a modern full-stack application with **Performance Reviews**, **KPI Tracking**, **Goal Management**, **Performance Reports**, and **Employee Evaluation** . Key features include:
- **Role-Based Access Control** with JWT authentication 
- **Dashboard & Analytics**: real-time dashboard, employee statistics, performance charts, activity monitoring 
- **Reports**: employee and department reports with PDF and Excel export 
- **Notifications**: performance review reminders and system notifications 

Built with React, Vite, Tailwind CSS, Node.js, Express, and MongoDB Atlas . **Important:** The project was last committed in June 2026 and has limited community adoption—evaluate maturity before production use.
**Best for:** Developers wanting a modern, full-stack reference implementation of a performance management system, accepting early-stage maturity.

### MintHCM
**Stack:** PHP / (Check repository) | **License:** Open Source
MintHCM is an open-source Human Capital Management platform built in PHP, positioned as an AI-ready HCM with **MCP/A2A-native** interfaces for connecting AI agents to HR functions including **performance reviews** . Key characteristics:
- **Full data ownership**: all employee and payroll data stay on the organization's infrastructure 
- **AI-ready integration**: MCP-compatible API lets AI assistants interact with real HR tools without vendor lock-in 
- **Production readiness signals**: 360 stars, 74 forks, recent commits as of September 2026, and a health score of 77/100 

It covers HR processes broadly, with performance reviews as one function among payroll, onboarding, leave management, and offboarding .
**Best for:** Organizations wanting an open-source HCM with AI agent integration and data sovereignty, accepting a PHP stack and broader HCM scope.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Review Cycles | 360 Feedback | Continuous Feedback | Self-Hosted | Best For |
|----------|---------|-------|---------------|--------------|---------------------|-------------|----------|
| **Lattice** | Proprietary | Cloud | ✅ | ✅ | ✅ | ❌ | Full performance management |
| **Culture Amp** | Proprietary | Cloud | ✅ | ✅ | (Engagement) | ❌ | Engagement + performance |
| **15Five** | Proprietary | Cloud | ✅ | (Check-ins) | ✅ | ❌ | Continuous check-ins |
| **Horilla** | LGPL-2.1 | Django/Postgres | ✅ | (Check) | ✅ | ✅ | Full HR suite + performance |
| **Check-Ins** | Open Source | Micronaut/React | ✅ | (Check) | ✅ | ✅ | Engagement + mentor program |
| **Caliber** | Open Source | Web | (1:1 focused) | ❌ | ✅ | ✅ | Engineering manager 1:1s |
| **PIX 360** | AGPL-3.0 | Ruby | (360 only) | ✅ E2EE | ❌ | ✅ | Privacy-focused 360 reviews |
| **EPMS** | MIT | React/Node/Mongo | ✅ | (Check) | (Check) | ✅ | Full-stack reference implementation |
| **MintHCM** | Open Source | PHP | ✅ | (Check) | (Check) | ✅ | AI-ready HCM + performance |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Performance Review or Feedback Management tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between **full HR suites with performance modules** (Horilla, MintHCM) that cover the entire employee lifecycle, **focused engagement platforms** (Check-Ins) that combine reviews with pulse surveys and recognition, **manager-centric tools** (Caliber) built around 1:1s and evidence logging, and **specialized review tools** (PIX 360 for encrypted 360 evaluations). **Horilla** is the most comprehensive open-source option with active development and Docker deployment , while **Caliber** uniquely addresses the day-to-day reality of management conversations rather than formal review cycles . For organizations wanting AI-agent integration into HR workflows, **MintHCM** offers an MCP-native approach .

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
