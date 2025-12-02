# Google Calendar Sync – Open-Source Backend & Infrastructure

This project is a complete open-source system designed to integrate and synchronize Google Calendar events across a small team environment. It serves as a practical study and a portfolio-ready demonstration of backend engineering, systems architecture, DevOps practices, and secure software development.  

The backend is primarily built in Python and follows clean architecture principles, security best practices, dependency isolation, and scalable infrastructure planning using only free and open-source tools.

---

## 🚀 Project Goals

- Provide a secure backend to integrate with Google Calendar (OAuth2 + API)
- Create a modular and maintainable Python application
- Demonstrate real-world infrastructure using only free resources
- Serve as a portfolio project targeted at international recruiters
- Follow industry standards: OWASP, Clean Code, DevSecOps, GitHub workflows

---

## 🛠️ Tech Stack

- **Python 3.12**
- **FastAPI** (backend API)
- **PostgreSQL** (database)
- **Redis** (caching & rate limiting)
- **Docker Compose** (local infra)
- **Nginx** (reverse proxy)
- **Keycloak (optional)** (for IAM)
- **GitHub Actions** (CI/CD)
- **Google Cloud APIs** (Calendar API)

---

## 📚 Core Features (Planned)

- Google OAuth2 authentication & token management  
- Event synchronization engine (pull & push)
- Rate-limited background workers
- User & calendar mapping system
- Audit logs & API monitoring
- Modular service architecture
- Local infrastructure with Docker

---

## 🧱 Project Structure Overview

See full details in `ARCHITECTURE.md`

/project-root
 ├── src/
 │   ├── api/                    # Routes, controllers, REST endpoints
 │   ├── core/                   # Settings, config, security, logging
 │   ├── modules/                # Business logic (calendar, users, sync)
 │   ├── workers/                # Background workers / async jobs
 │   ├── infra/                  # Database, redis, external clients
 │   └── utils/                  # Shared helpers and utilities
 │
 ├── tests/                      # Automated test suite
 ├── docs/                       # Additional documentation (diagrams, notes)
 │
 ├── .github/
 │   ├── ISSUE_TEMPLATE/
 │   │   ├── bug_report.md
 │   │   ├── feature_request.md
 │   │   └── documentation_request.md
 │   └── PULL_REQUEST_TEMPLATE.md
 │
 ├── README.md
 ├── CONTRIBUTING.md
 ├── CODE_OF_CONDUCT.md
 ├── ARCHITECTURE.md            
 ├── BRANCH_PROTECTION.md        
 ├── CODEOWNERS
 └── LICENSE

---

## 🧰 How to Contribute

See: `CONTRIBUTING.md`

---

## 🔒 Code of Conduct

See: `CODE_OF_CONDUCT.md`

---

## 👤 Maintainer

**Murillo Gabriel**  
Contact: *murillogyn2023@gmail.com*

---

## 📄 License

This project is licensed under the MIT License.