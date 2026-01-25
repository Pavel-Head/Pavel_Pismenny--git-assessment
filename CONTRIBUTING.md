---

### `CONTRIBUTING.md` (в корне репозитория)

```markdown
# Contributing Guidelines

Thank you for your interest in contributing! This repository is for **educational purposes** and aims to practice clean Git workflows and collaboration.

## 📋 Ground Rules

- Be respectful and constructive.
- Keep commits **small**, **focused**, and **well-described**.
- Prefer **English** in commit messages and discussions.

## 🌳 Branching Model

Follow the GitFlow-inspired model:

- `main` — stable, production-like branch
- `dev` — integration branch for ongoing development
- `feature/*` — new features (from `dev`)
- `bug/*` — non-critical bug fixes (from `dev`)
- `release/*` — release prep (from `dev`)
- `hotfix/*` — urgent fixes (from `main`, then merge back to `main` and `dev`)

## ✅ Commit Message Style

- Use imperative mood (e.g., `Add`, `Fix`, `Update`).
- Keep the subject under ~72 chars.
- Use **squash** or **fixup** during PR review to keep history clean.
