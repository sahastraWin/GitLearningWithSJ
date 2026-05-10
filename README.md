# 🚀 GitLearningWithSJ

> **"Git is not memorization. It is understanding the graph."**

A comprehensive, hands-on laboratory dedicated to mastering version control, branching strategies, and the underlying architecture of Git. This repository serves as a visual and technical roadmap for professional-grade Git proficiency.

---

## 🛠️ Commands Mastered
I have moved beyond basic commits to understanding history manipulation and repository maintenance:

| Category | Commands |
| :--- | :--- |
| **Setup & Config** | `git init`, `git config` |
| **Snapshots** | `git add`, `git commit`, `git .gitignore` |
| **Navigation** | `git log`, `git switch`, `git branch` |
| **History Control** | `git restore`, `git commit --amend` |
| **Integration** | `git merge --no-ff`, `git rebase` |

---

## 🌿 Branching Strategy
This project follows a professional naming convention (Feature/Bugfix/Release) to simulate a real-world development environment:

* ✨ `feature/navbar` - Navigation component implementation.
* ✨ `feature/hero` - Hero section design and logic.
* ✨ `feature/contact` - Contact form integration.
* 🐛 `bugfix/typo` - Correction of documentation and string literals.
* 🔥 `hotfix/crash` - Critical patch for runtime stability.
* 📦 `release/v1.0` - Production-ready stable build.

---

## 📊 Visualization: The Power of the Graph
To view the complete evolutionary history of this project with a visual DAG (Directed Acyclic Graph), run the following command in your terminal:

```bash
git log --oneline --graph --all --decorate
