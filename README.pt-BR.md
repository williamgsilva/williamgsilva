<h1 align="center">Olá, meu nome é William!</h1>

<p align="center">
  <b>DevOps / SRE:</b> Automações, IaC, Python, orquestração, CI/CD
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/william-gon%C3%A7alves-a315961ba/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:williamgs95@hotmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=maildotru&logoColor=white" alt="E-mail"></a>
</p>

<p align="center">
  🇺🇸 <a href="README.md">English</a> · 🇧🇷 Português
</p>

<p align="center">
  🔨 <b>Projeto mais recente:</b> <a href="https://github.com/williamgsilva/active-directory-api">active-directory-api</a> — um só lugar para todas as aplicações internas autenticarem no Active Directory
</p>

---

## 🚀 Sobre mim

Sou engenheiro de infraestrutura com foco em sustentação de ambientes críticos e escaláveis, observabilidade e automações.

No dia a dia eu:

- 💻 Provisiono e mantenho **ambientes críticos e escaláveis**
- ⚙️ Automatizo provisionamento e configuração de servidores com **Ansible**
- 🐍 Desenvolvo **ferramentas internas em Python** para operação de infraestrutura (CLIs, APIs e automações)
- 🐳 Empacoto e opero aplicações em **Docker** e orquestro serviços com **Rancher e Docker Swarm**
- 🔁 Construo e mantenho **pipelines de CI/CD** (GitLab CI / GitHub Actions)
- 🍃 Cuido de rotinas de **backup, restore e gestão de bancos** (MongoDB, SQL)
- ☕ Dou suporte a aplicações **Java / Spring Boot** em produção (gateways e microsserviços)

O que mais gosto é perceber um problema sendo resolvido de novo e de novo e transformá-lo em ferramenta —
uma CLI, uma API, um pipeline — com as decisões por trás documentadas, para a próxima pessoa não precisar
redescobri-las.

> 💡 Acredito que boa infraestrutura é aquela que não para no tempo e nunca se considera boa o suficiente para deixar de melhorar.

## 📌 Projetos em destaque

### 🔐 [active-directory-api](https://github.com/williamgsilva/active-directory-api)

Cada nova aplicação interna reimplementava o próprio login no Active Directory: o mesmo código LDAP, os
mesmos bugs e mais um lugar guardando senha de conta de serviço. Criei uma API pequena para ser **a única
coisa que fala com o AD** — as aplicações mandam as credenciais e recebem um JWT assinado, que elas mesmas
conseguem validar.

- Login por usuário **ou e-mail**, JWT RS256 com endpoint JWKS público
- Regras por aplicação: nível de acesso, grupos obrigatórios e quais grupos vão no token
- Troca da chave de assinatura sem derrubar ninguém; aplicações e chaves no PostgreSQL, mudanças sem restart
- Correções feitas de propósito: LDAP injection, bind com senha vazia, conexão compartilhada entre usuários
- 49 testes automatizados na CI e deploy em Docker Swarm com rolling update

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LDAP](https://img.shields.io/badge/LDAP%20%2F%20Active%20Directory-0078D4?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Swarm-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 🧱 [project-template](https://github.com/williamgsilva/project-template)

O ponto de partida que uso em novos projetos, para todo repositório nascer com a mesma base em vez de
copiá-la à mão: estrutura padronizada, `make` como interface única, CI, varredura de segurança (segredos,
dependências, IaC), ADRs para registrar decisões e instruções para assistentes de IA.

![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=gnu&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?style=flat-square&logo=precommit&logoColor=black)

<!-- Adicione novos projetos aqui conforme publicar -->

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

**Linguagens & Dados**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Ferramentas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Redmine](https://img.shields.io/badge/Redmine-B32024?style=flat-square&logo=redmine&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

**Entusiasta de IA**

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

## 📈 Roadmap de estudos

Acompanho meu progresso publicamente — cada item vira um repositório com laboratório prático.

- [x] Linux, Bash e redes
- [x] Docker e Docker Compose
- [x] Ansible para configuração de servidores
- [x] CI/CD com GitLab CI
- [x] Automação de infraestrutura com Python
- [x] Observabilidade: Prometheus, Grafana e Loki
- [x] Autenticação centralizada: Active Directory, LDAP e JWT
- [ ] SSO com Keycloak / OpenID Connect
- [ ] Kubernetes (CKA)
- [ ] Terraform / Infraestrutura como Código
- [ ] Cloud (AWS)
- [ ] GitOps com Argo CD

## 📊 Estatísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=williamgsilva&show_icons=true&hide_border=true&count_private=true&theme=transparent" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=williamgsilva&layout=compact&hide_border=true&theme=transparent" alt="Top languages" />
</p>

---

<p align="center">
  <i>Aberto a oportunidades em DevOps, SRE e Cloud. Vamos conversar!</i>
</p>
