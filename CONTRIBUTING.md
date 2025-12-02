# Contributing Guide

Thank you for your interest in contributing to this project!  
Even though this is primarily a personal and academic project, the repository follows real industry contribution standards to demonstrate professionalism and clean collaborative practices.

---

## 📌 Before You Start

1. Read the `README.md`  
2. Understand the project design in `ARCHITECTURE.md`  
3. Check open issues to avoid duplicated work  
4. Follow the Code of Conduct (`CODE_OF_CONDUCT.md`)

---

## 🔀 Branching Strategy

- `main` → Stable, protected, production-ready
- `dev` → Development branch (optional)
- Feature branches follow the pattern:  
  `feature/<short-description>`  
- Bugfix branches:  
  `bugfix/<short-description>`

Example:

feature/google-oauth
bugfix/redis-timeout

---

## 🧪 Writing Tests

All new features should include tests when applicable.  
Test folder structure mirrors the application folder.

---

## 🧹 Code Style Guidelines

- Follow **PEP8**
- Use **type hints**
- Keep functions small and modular
- Avoid circular dependencies
- Avoid unnecessary complexity
- Write docstrings using Google style

---

## 📤 Pull Requests Requirements

All PRs must:

- Link to an existing Issue  
- Have a clear title and description  
- Contain only relevant changes  
- Include tests for new features (if applicable)  
- Pass static checks (flake8, mypy)  
- Follow the PR template

---

## 🧪 Local Development Setup

You only need:

- Docker & Docker Compose
- Python 3.12

Run:

docker compose up

(Actual commands will be added when implementation begins.)

---

## 🧑‍💻 Contact

If you have questions, open an Issue or reach out via GitHub.

Happy contributing!
