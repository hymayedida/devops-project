# 🚀 DevOps Git Project

This project demonstrates Git best practices in a DevOps environment. It includes repository setup, branching strategies, pull request workflows, tagging, and task documentation — all managed through Git and GitHub.

---
## 📁 Project Structure
devops-project/
├── src/ # Application source code
├── scripts/ # Deployment or automation scripts
├── docs/ # Documentation files (e.g., TASKS.md)
├── tags/ # (Optional) Release notes or changelogs
├── .gitignore # Git ignore rules
└── README.md # Project overview


---

## 🧠 Git Workflow

### 🔸 Branching Strategy
- `main` – Stable production-ready code
- `dev` – Development integration branch
- `feature/*` – Feature-specific development branches (e.g., `feature/setup-structure`)

### 🔸 Workflow Summary
1. Developers create a `feature/*` branch from `dev`
2. Work is committed to the feature branch
3. Pull Request (PR) is created to merge into `dev`
4. After review, `dev` is merged into `main` upon release
5. Tags are added for versioning (e.g., `v1.0.0`)

---

## ✅ Git Best Practices Followed

| Practice             | Description                                |
|----------------------|--------------------------------------------|
| 🪄 Commit History     | Clear, concise, and atomic commits         |
| 🌿 Branching Model    | Follows `main`/`dev`/`feature/*` strategy  |
| 🔀 Pull Requests      | Code merged via PRs (not direct pushes)    |
| 🏷️ Tagging           | Release versions with annotated tags       |
| 📂 Clean Repo         | `.gitignore` for excluding unnecessary files |
| 📝 Markdown Docs      | Tasks tracked in `docs/TASKS.md`           |

---

## 📄 Documentation

All tasks and workflows are documented in:

📄 [`docs/TASKS.md`](docs/TASKS.md)

This file contains:
- Task checklists
- Feature descriptions
- Steps followed in the project

---

## 🏷️ Release Tags

Tags are used to mark stable points in the project (e.g., `v1.0.0`, `v1.1.0`). You can list them using:

```bash
git tag

