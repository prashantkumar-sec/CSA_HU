# CSA HU — Cloud Security Alliance, Haridwar University

> Official web portal for the Cloud Security Alliance at Haridwar University.

---

## 📌 Project Overview

This repository contains the source code for the CSA HU club website — a full-featured portal with:
- Club landing page & events
- Member dashboard
- Blog & resources
- Contact & registration forms

---

## 👥 Team

| S.No | Name | Domain | Role |
|------|------|--------|------|
| 1 | Ujjwal Singhal | Frontend | Developer |
| 2 | Vansh Bansal | Frontend | Developer |
| 3 | Omansh Chauhan | Backend | Sub-Coordinator (Architecture & Deployment) |
| 4 | Vansh Pratap | Backend | Developer |
| 5 | Khushi | Database | Coordinator (Architecture & Deployment) |
| 6 | Biswajit Goswami | Database | Developer |
| 7 | Piyush Kumar | AI/ML | Developer |
| 8 | Arpit Rathi | AI/ML | Technical Project Sub-Coordinator |
| 9 | Rimjhim Bhattacharya | AI/ML | Developer |
| 10 | Prashant Kumar | Cybersecurity | Technical Project Coordinator |
| 11 | Varun Kansal | Cybersecurity | Developer |

---

## 🌿 Branch Strategy

```
main          ← Production (Vercel live site) — only Prashant & Omansh merge here
dev           ← Integration branch — all domain branches merge here first
frontend      ← Ujjwal Singhal, Vansh Bansal
backend       ← Omansh Chauhan, Vansh Pratap
database      ← Khushi, Biswajit Goswami
ai-ml         ← Piyush Kumar, Arpit Rathi, Rimjhim Bhattacharya
cybersecurity ← Prashant Kumar, Varun Kansal
```

**Workflow:**
1. Each member works on their **domain branch**
2. Open a **Pull Request** → `domain branch` → `dev`
3. Prashant / Omansh review & merge into `dev`
4. After testing, `dev` → `main` (triggers Vercel deploy)

---

## 🚀 Getting Started (Local Setup)

```bash
# Clone the repo
git clone https://github.com/prashantkumar-sec/CSA_HU.git
cd CSA_HU

# Switch to your domain branch
git checkout frontend   # or backend, database, ai-ml, cybersecurity

# Install dependencies
npm install

# Start dev server
npm run dev
```

---

## 📖 Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before making any commits.

---

## 🌐 Live Site

Hosted on Vercel → **[csa-hu.vercel.app](#)** *(link will be updated after first deploy)*

---

*Made with ❤️ by the CSA HU Tech Team*
