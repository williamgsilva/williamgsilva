<h1 align="center">Hi, my name is William!</h1>

<p align="center">
  <b>DevOps / SRE:</b> Automation, IaC, Python, Orchestration, CI/CD
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/william-gon%C3%A7alves-a315961ba/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:williamgs95@hotmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=maildotru&logoColor=white" alt="E-mail"></a>
</p>

<p align="center">
  🇺🇸 English · 🇧🇷 <a href="README.pt-BR.md">Português</a>
</p>

<p align="center">
  🔨 <b>Latest project:</b> <a href="https://github.com/williamgsilva/active-directory-api">active-directory-api</a>: one place for every internal app to authenticate against Active Directory
</p>

---

## 🚀 About me

I'm an infrastructure engineer focused on maintaining critical, scalable environments, observability, and automation.

Day to day, I:

- 💻 Provision and maintain **critical, scalable environments**
- ⚙️ Automate server provisioning and configuration with **Ansible**
- 🐍 Develop **internal Python tools** for infrastructure operations (CLIs, APIs, and automation)
- 🐳 Package and run applications in **Docker** and orchestrate services with **Rancher and Docker Swarm**
- 🔁 Build and maintain **CI/CD pipelines** (GitLab CI / GitHub Actions)
- 🍃 Handle **backup, restore, and database administration** routines (MongoDB, SQL)
- ☕ Support **Java / Spring Boot** applications in production (gateways and microservices)

What I enjoy most is spotting the same problem being solved over and over and turning it into a tool,
whether that's a CLI, an API or a pipeline, with the decisions behind it written down so the next person
doesn't have to rediscover them.

> 💡 I believe good infrastructure never stands still and is never good enough to stop improving.

## 📌 Featured projects

### 🔐 [active-directory-api](https://github.com/williamgsilva/active-directory-api)

Every new internal application was re-implementing its own login against Active Directory: same LDAP
code, same bugs, one more place holding a service-account password. I built a small API to be **the only
thing that talks to AD**. Apps send the credentials and get back a signed JWT they can validate on their own.

- Login by username **or email**, RS256 JWTs with a public JWKS endpoint
- Per-application rules: access level, required groups, which groups go into the token
- Zero-downtime signing-key rotation, apps and keys in PostgreSQL, changes applied without restarts
- Fixes I made on purpose: LDAP injection, empty-password binds, a connection shared across users
- 49 automated tests in CI, Docker Swarm deploy with rolling updates

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LDAP](https://img.shields.io/badge/LDAP%20%2F%20Active%20Directory-0078D4?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Swarm-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 🧱 [project-template](https://github.com/williamgsilva/project-template)

The starting point I use for new projects, so every repository begins with the same foundations instead
of copying them by hand: a standardized structure, `make` as the single interface, CI, security scanning
(secrets, dependencies, IaC), ADRs to record decisions, and instructions for AI assistants.

![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=gnu&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?style=flat-square&logo=precommit&logoColor=black)

<!-- Add new projects here as they are published -->

## 🛠️ Stack

**Infra & DevOps**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=flat-square&logo=rancher&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Languages & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Redmine](https://img.shields.io/badge/Redmine-B32024?style=flat-square&logo=redmine&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

**AI enthusiast**

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

## 📈 Learning roadmap

I track my progress publicly, and each item becomes a repository with a hands-on lab.

- [x] Linux, Bash, and networking
- [x] Docker and Docker Compose
- [x] Ansible for server configuration
- [x] CI/CD with GitLab CI
- [x] Infrastructure automation with Python
- [x] Observability: Prometheus, Grafana and Loki
- [x] Centralized authentication: Active Directory, LDAP and JWT
- [ ] SSO with Keycloak / OpenID Connect
- [ ] Kubernetes (CKA)
- [ ] Terraform / Infrastructure as Code
- [ ] Cloud (AWS)
- [ ] GitOps with Argo CD

## 📊 Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=williamgsilva&show_icons=true&hide_border=true&count_private=true&theme=transparent" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=williamgsilva&layout=compact&hide_border=true&theme=transparent" alt="Top languages" />
</p>

---

<p align="center">
  <i>Open to opportunities in DevOps, SRE, and Cloud. Let's talk!</i>
</p>
