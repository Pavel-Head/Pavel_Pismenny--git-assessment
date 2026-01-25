
# Student Git & GitHub Assessment Repository

[![License](https://img.shields.io/github/license/Pavel-Head/Pavel_Pismenny--git-assessment)](./License)
![size](https://img.shields.io/github/repo-size/Pavel-Head/Pavel_Pismenny--git-assessment)
![commit](https://img.shields.io/github/last-commit/Pavel-Head/Pavel_Pismenny--git-assessment)
![version](https://img.shields.io/badge/https%3A%2F%2Fgithub.com%2FPavel-Head%2FPavel_Pismenny--git-assessment%2Freleases?style=flat&label=v1.0.1&labelColor=rgba)

## 📌 About This Repository

This is a **student repository** created for educational purposes as part of learning **Git and GitHub workflows**.

The main goal is to demonstrate **core Git skills** and collaboration practices:
- Merging
- Rebasing
- Squashing
- Fixup commits
- Rerouting history (interactive rebase)
- Working with long-living branches

The repository uses a simple **“Hello World”** example in JavaScript to keep the focus on Git processes.

---

## 🌳 Branching Strategy

This repository follows a GitFlow-inspired model:

- **`main`** — *trust branch*, always stable and production-ready; base for CI/CD.
- **`dev`** — persistent development branch; features and fixes are integrated here first.
- **`release/*`** — cut from `dev`, used for release preparation; merged back to `main`.
- **`feature/*`** — for new features; branch off `dev`.
- **`bug/*`** — for non-critical bug fixes; branch off `dev`.
- **`hotfix/*`** — urgent fixes; branch off `main`, merged back into `main` and `dev`.

---

## 🧪 Tech

- **Language:** JavaScript
- **Example:** Hello World
- **Purpose:** Educational (Git & GitHub practice)

---

## ⚙️ Setup & Installation

See [**setup.md**](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/edit/main/docs/setup.md) for full instructions:
- clone the repository
- change directory
- install JS dependencies
- run the example

---

## 🤝 Contributing

Contributions are welcome for learning purposes.  
Please read [**CONTRIBUTING.md**](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/blob/main/CONTRIBUTING.md) before starting.

- Issues: use templates under [**.github/ISSUE_TEMPLATE/**](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/tree/main/.github/ISSUE_TEMPLATE)  
  - Bug reports → `bug_report.md`  
  - Feature requests → `feature_request.md`
- Pull Requests: use [**pull_request_template.md**](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/blob/main/.github/PULL_REQUEST_TEMPLATE.md)

---

## 🐞 Issues

Open an issue using one of the templates:
- **Bug report:** [bug_report.md](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/blob/main/.github/ISSUE_TEMPLATE/bug_report.md)  
- **Feature request:** [feature_request.md](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/blob/main/.github/ISSUE_TEMPLATE/feature_request.md)
- **Custom propose:** [custom.md](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/blob/main/.github/ISSUE_TEMPLATE/custom.md)

---

## 📜 License

Licensed under the [**MIT License**](https://github.com/Pavel-Head/Pavel_Pismenny--git-assessment/blob/main/LICENSE)

---

## ✅ Disclaimer

This repository is **not intended for production use**—it is created solely for **educational and assessment purposes**.
