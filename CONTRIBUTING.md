````md id="onb1x7"
# 🌊 SolvAqua Developer Onboarding Guide

Welcome to the SolvAqua development team 👋  
This guide will help you set up your environment and understand how we work together as a team.

---

## 🚀 1. Project Overview

SolvAqua is a Progressive Web App (PWA) + USSD system that helps communities report and track water-related issues in real time.

You will be working on:

- Backend APIs (Node.js / Express)
- Frontend PWA (React / Next.js)
- Admin Dashboard
- USSD integration

---

## 🧰 2. First-Time Setup

### Step 1: Clone the repository

```bash id="stp1"
git clone https://github.com/your-org/solvaqua.git
cd solvaqua
```
````

---

### Step 2: Install dependencies

```bash id="stp2"
npm install
```

(Or follow setup instructions inside `/client`, `/server`, or `/dashboard` depending on structure)

---

### Step 3: Create your feature branch

Never work on `main`.

```bash id="stp3"
git checkout -b feature/your-feature-name
```

Examples:

- feature/login-system
- feature/report-issue-api
- feature/ussd-flow

---

## 🔄 3. Daily Workflow

### Before you start coding:

```bash id="wf1"
git pull origin main
```

### After making changes:

```bash id="wf2"
git add .
git commit -m "Describe what you changed"
git push origin feature/your-feature-name
```

---

## 🔁 4. Pull Request Process

When your feature is ready:

1. Push your branch
2. Go to GitHub
3. Open a Pull Request (PR)
4. Request a review from a teammate
5. Wait for approval
6. Merge into `main`

---

## 🚫 5. Important Rules

### ❌ Never:

- Push directly to `main`
- Commit broken or unfinished code
- Upload `.env` or `node_modules/`
- Mix multiple features in one branch

### ✔️ Always:

- Work in a feature branch
- Write clear commit messages
- Pull latest changes before starting work
- Ask for review before merging

---

## ✍️ 6. Commit Message Guidelines

Good examples:

```bash id="cm1"
git commit -m "Added user authentication system"
git commit -m "Fixed issue reporting validation bug"
git commit -m "Implemented USSD step 1 flow"
```

Bad examples:

```bash id="cm2"
git commit -m "update"
git commit -m "fix"
```

---

## 🌿 7. Branch Naming Rules

Use this format:

```text id="bn1"
feature/<feature-name>
fix/<bug-name>
```

Examples:

- feature/auth-system
- feature/issue-tracking
- fix/login-error

---

## 👀 8. Code Review Rules

Before merging:

- At least 1 teammate must review your PR
- Code must not break existing features
- Ensure naming is clear and consistent

---

## 🔐 9. Protected Files

Do NOT push:

```text id="pf1"
node_modules/
.env
vendor/
dist/
```

These are ignored automatically via `.gitignore`.

---

## 🔔 10. Staying Updated

- Watch the repository on GitHub
- Enable notifications (PRs, issues, comments)
- Respond to review feedback quickly

---

## 🎯 11. Team Goal

Our goal is to:

- Build clean, reliable software
- Work collaboratively across countries
- Keep code organized and maintainable
- Ship features consistently without breaking production

---

## 🤝 Welcome to the Team

If anything is unclear:

- ask questions early
- don’t assume
- communicate often

We build better together 🚀

```

```
