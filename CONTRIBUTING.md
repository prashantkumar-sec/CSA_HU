# Contributing to CSA HU Website

Welcome to the CSA HU project! Please read this guide carefully before making any commits.

---

## 🌿 Which Branch Do I Work On?

| Your Name | Your Branch |
|-----------|-------------|
| Ujjwal Singhal | `frontend` |
| Vansh Bansal | `frontend` |
| Omansh Chauhan | `backend` |
| Vansh Pratap | `backend` |
| Khushi | `database` |
| Biswajit Goswami | `database` |
| Piyush Kumar | `ai-ml` |
| Arpit Rathi | `ai-ml` |
| Rimjhim Bhattacharya | `ai-ml` |
| Prashant Kumar | `cybersecurity` |
| Varun Kansal | `cybersecurity` |

> ⚠️ **Never commit directly to `main` or `dev`.** Only the coordinator can merge into those.

---

## 🔁 Step-by-Step Workflow

### 1. Clone the repo (first time only)
```bash
git clone https://github.com/prashantkumar-sec/CSA_HU.git
cd CSA_HU
```

### 2. Switch to your domain branch
```bash
# Replace 'frontend' with your domain branch
git checkout frontend
```

### 3. Pull latest changes before starting work
```bash
git pull origin frontend
```

### 4. Make your changes, then stage and commit
```bash
git add .
git commit -m "feat(frontend): add hero section component"
```

### 5. Push your branch to GitHub
```bash
git push origin frontend
```

### 6. Open a Pull Request
- Go to the repo on GitHub
- Click **"Compare & pull request"**
- Set **base** = `dev`, **compare** = your branch
- Write a clear description of what you changed
- Tag **Prashant Kumar** or **Arpit Rathi** as reviewers

---

## ✍️ Commit Message Format

Use this format for every commit:

```
<type>(<domain>): <short description>

Examples:
feat(frontend): add navbar component
fix(backend): resolve API timeout issue
docs(ai-ml): update model readme
style(database): fix schema formatting
refactor(cybersecurity): simplify auth middleware
```

**Types:**
| Type | When to use |
|------|-------------|
| `feat` | New feature or component |
| `fix` | Bug fix |
| `docs` | Documentation changes |
| `style` | Formatting, no logic change |
| `refactor` | Code restructure |
| `chore` | Configs, dependencies |

---

## 📁 Folder Ownership

| Domain Branch | Folders You Own |
|---------------|-----------------|
| `frontend` | `src/components/`, `src/pages/`, `src/styles/` |
| `backend` | `src/api/`, `src/services/`, `src/data/events.js` |
| `database` | `src/data/team.js`, `src/db/`, `schema/` |
| `ai-ml` | `src/ai/`, `src/data/blog.js`, `notebooks/` |
| `cybersecurity` | `src/auth/`, `docs/security/` |

> Avoid editing files outside your domain folder without discussing it first.

---

## 🚫 Rules

1. ❌ Do NOT commit directly to `main` or `dev`
2. ❌ Do NOT commit `.env` files or secrets
3. ❌ Do NOT commit `node_modules/`
4. ✅ Always pull before you start working
5. ✅ Always create a Pull Request for review
6. ✅ Write clear commit messages

---

## 🆘 Need Help?

Ping **Prashant Kumar** (Project Coordinator) or **Arpit Rathi** (Sub-Coordinator) on WhatsApp/group.
