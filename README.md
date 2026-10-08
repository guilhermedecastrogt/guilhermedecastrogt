<div align="center">

# Guilherme de Castro

### Full-Stack Software Engineer · AI Systems · Cloud & DevOps

Building production-minded software across **TypeScript, Node.js, .NET, AI, PostgreSQL, Docker, Terraform and cloud infrastructure**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilhermedecastro-/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-111827?style=flat&logo=vercel&logoColor=white)](https://guilherme-de-castro.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=flat&logo=github&logoColor=white)](https://github.com/guilhermedecastrogt)

</div>

---

## About

I'm a **Full-Stack Software Engineer** focused on building reliable applications and the infrastructure around them.

My work sits at the intersection of:

- **Product engineering** — turning business requirements into complete, maintainable systems
- **Backend engineering** — APIs, domain logic, integrations, data modeling and authentication
- **AI engineering** — practical AI systems where models are isolated from critical business logic
- **Cloud & DevOps** — Docker, CI/CD, Terraform, Linux and infrastructure automation
- **Software architecture** — modular systems, clean boundaries, observability and production ownership

I enjoy going beyond writing application code: designing the architecture, automating deployment, operating the system and understanding the trade-offs behind each decision.

Currently based in **Dublin, Ireland** and open to opportunities across the Irish and European technology market.

---

## What I Build

```text
                    ┌──────────────────────────────┐
                    │        Product / UX          │
                    │   Next.js · React · Web UI   │
                    └──────────────┬───────────────┘
                                   │
                    ┌──────────────▼───────────────┐
                    │        Application Layer     │
                    │ Node.js · NestJS · .NET APIs │
                    └──────────────┬───────────────┘
                                   │
              ┌────────────────────┼────────────────────┐
              │                    │                    │
      ┌───────▼────────┐   ┌───────▼────────┐   ┌───────▼────────┐
      │ Data & Domain  │   │ AI & Integrations│   │ Infrastructure │
      │ PostgreSQL     │   │ OpenAI · WhatsApp│   │ Docker         │
      │ MySQL · Redis  │   │ REST · Webhooks │   │ Terraform      │
      └────────────────┘   └─────────────────┘   │ Oracle Cloud   │
                                                  │ GitHub Actions │
                                                  └────────────────┘
```

---

## Featured Projects

### AI Personal CFO

**A self-hosted personal finance platform with a deterministic finance engine and an AI advisor delivered through WhatsApp.**

[Repository](https://github.com/guilhermedecastrogt/ai-personal-cfo)

**Architecture**

`WhatsApp → Kapso → Caddy → Next.js → NestJS → PostgreSQL`

**Highlights**

- Multi-household and multi-member financial model
- Deterministic finance engine — the LLM never performs financial calculations
- AI transaction extraction from text and receipt images
- Runtime and domain validation before persistence
- WhatsApp identity resolution
- Budget, goals, insights and proactive notifications
- Next.js dashboard
- NestJS API with Drizzle ORM and Zod
- OpenAI isolated behind an internal provider interface
- Docker Compose production stack
- Terraform-managed Oracle Cloud infrastructure
- GitHub Actions CI/CD
- Architecture documentation and ADRs

**Stack:** `TypeScript` `Node.js` `NestJS` `Next.js` `PostgreSQL` `Drizzle` `Zod` `OpenAI` `WhatsApp` `Docker` `Terraform` `Oracle Cloud` `GitHub Actions`

---

### Pterodactyl on Oracle Cloud

**Infrastructure-as-code for deploying a complete Pterodactyl game-server platform on Oracle Cloud Always Free.**

[Repository](https://github.com/guilhermedecastrogt/pterodactyl-oracle-terraform)

**Highlights**

- Terraform-provisioned Oracle Cloud ARM infrastructure
- VCN, subnet, routing and security rules
- Ubuntu ARM VM provisioning
- Cloud-init first-boot automation
- Docker-based Pterodactyl stack
- Caddy reverse proxy and automatic HTTPS
- MariaDB, Redis and Wings
- Terraform-generated credentials
- Budget alert as a cost-safety mechanism
- GitHub Actions validation
- Designed around Oracle Cloud Always Free constraints

**Stack:** `Terraform` `Oracle Cloud` `ARM64` `Ubuntu` `Docker` `Cloud-init` `Caddy` `Pterodactyl` `GitHub Actions`

---

### Banco Inter Open Banking API

**A .NET 8 Web API integrating Banco Inter's banking API using production-oriented architecture and security practices.**

[Repository](https://github.com/guilhermedecastrogt/inter-bank-api-dotnet)

**Highlights**

- Clean layered architecture
- Domain / Application / Infrastructure separation
- OAuth 2.0 Client Credentials flow
- Mutual TLS authentication
- Repository pattern
- Dependency injection
- Balance and statement endpoints
- Docker support
- Swagger/OpenAPI development workflow

**Stack:** `.NET 8` `C#` `ASP.NET Core` `Docker` `OAuth 2.0` `mTLS`

---

### WhatsApp Bulk Sender

**Python automation for sending WhatsApp messages from structured contact data.**

[Repository](https://github.com/guilhermedecastrogt/whatsapp-bulk-sender)

**Stack:** `Python` `Selenium` `WhatsApp Web` `Automation`

---

### Artistique Casting API

**A .NET Web API integration layer for casting-management workflows.**

[Repository](https://github.com/guilhermedecastrogt/ArtistiqueCastingAPI)

**Stack:** `.NET` `C#` `ASP.NET Core` `REST API`

---

## Technical Stack

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)

### Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

### AI & Integrations

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-005571?style=flat)

### Cloud & DevOps

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat&logo=oracle&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)

---

## Engineering Principles

### Deterministic systems over AI guesswork

For systems involving money or other critical business logic, I prefer **deterministic code as the source of truth** and AI as an interface, extraction layer or advisor.

### Architecture with boundaries

I care about keeping domain logic independent from infrastructure, external providers and framework details whenever the problem benefits from it.

### Infrastructure is part of the product

A project is not finished when it works locally. I care about reproducible environments, automated deployment, observability, backups and operational safety.

### Build for the real constraint

Whether the constraint is an ARM free tier, an external API, authentication requirements or a production database, I prefer architectures that explicitly account for the environment they actually run in.

---

## Professional Experience

**Software Engineering — Full Stack / Backend / DevOps**

Experience across:

- TypeScript / Node.js / Next.js
- .NET / C# / ASP.NET Core
- REST API design and third-party integrations
- SQL data modeling
- Docker and Linux deployments
- CI/CD automation
- Authentication and authorization
- Observability and production troubleshooting
- Cloud infrastructure and Infrastructure as Code

---

## Beyond the Code

I like projects where software meets a real-world problem.

Some of my recent work explores:

- AI-powered personal finance
- WhatsApp-based interfaces
- Cloud infrastructure on constrained budgets
- Open Banking integrations
- Automation
- Self-hosted systems
- Developer tooling and architecture

The common thread is simple:

> **Build something useful, understand the system end-to-end, and make the engineering deliberate.**

---

## Let's Connect

I'm currently based in **Dublin, Ireland**.

If you're hiring for **Full-Stack, Backend, Node.js/TypeScript, .NET, AI Engineering or Cloud/DevOps** roles, I'd be happy to connect.

- **LinkedIn:** https://www.linkedin.com/in/guilhermedecastro-/
- **Portfolio:** https://guilherme-de-castro.vercel.app/
- **GitHub:** https://github.com/guilhermedecastrogt

---

<div align="center">

### Thanks for visiting.

*Building systems, not just features.*

</div>
