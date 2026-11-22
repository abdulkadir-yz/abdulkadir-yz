# Hi, I'm Abdulkadir 👋

**Electrical & Electronics Engineer → Full-Stack Developer (C# / .NET)**
📍 Worms, Germany · 🎓 Software Engineering & AI Bootcamp @ WBS Coding School (2026–2027)

## About

I'm an engineer with ~6 years of IT experience in DevOps, IAM and cybersecurity
(KOBIL GmbH, Mespa Medical, Liberta Software). I know how software is deployed,
secured and operated in production, and now I build it end to end: Fork Club is a
tested, security-scanned app with a running demo.

- **Backend:** C# / ASP.NET Core with EF Core, Identity and JWT
- **Frontend:** React and Next.js; TypeScript with Node.js / Express
- **AI:** Built a FHIR project that uses a locally hosted LLM with a grounding check;
  I use Claude Code in my daily development workflow (see below)

## Currently building

**[Fork Club](https://forkclub.de/)** *(pre-launch · private repo)*
Fresh meals waiting in your gym's fridge. Members plan their meals once a week, a partner
kitchen cooks exactly what was ordered and delivers every morning, and members pick up
their box after training. A demo is running; first pilot planned in Germany.

- **Backend:** .NET 10 · ASP.NET Core Web API · EF Core 10 · Azure SQL · JWT with Microsoft Entra External ID · Azure Blob Storage
- **Frontend:** React 19 · TypeScript · Vite · TanStack Query · Tailwind CSS · MSAL
- **Delivery:** Docker (chiseled images) · Azure Container Apps + Container Apps Jobs (weekly cutoff, nightly closing, migrations) ·
  GitHub Actions with OIDC to Azure (no stored secrets)
- **Quality & security:** xUnit integration tests against real SQL Server · Playwright E2E · Trivy · gitleaks · Dependabot

## How I work with AI

I use **Claude Code** as a pair programmer, not as autocomplete: I own the design,
review every change, and let tests decide when something is done.

- **Plan → test → review:** brainstorm and plan first, TDD while building, code review before merging
- **Verified, not trusted:** xUnit integration and Playwright E2E tests, Claude Security scans, gitleaks / Trivy in CI
- **Grounded in real docs:** MCP servers (Context7, Microsoft Learn), JetBrains Rider, Playwright
- **Custom tooling:** my own Claude Code skills and project memory (e.g. a Fork Club brand kit skill); Remotion for promo videos as code

## Tech Stack

**Backend (main focus)**

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Frontend & JavaScript / TypeScript**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

**Background (from IT / DevOps work)**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

Also used: MongoDB / Mongoose (course work), Python, Flask, PostgreSQL

## Projects

**[FHIR Encounter Summary](https://github.com/abdulkadir-yz/fhir-encounter-summary)**
TypeScript · Express · Docker Compose · HAPI FHIR · Ollama · GitHub Actions
Normalizes the scattered FHIR resources of a hospital encounter into a clean domain model,
generates a German discharge summary (Epikrise) with a locally hosted LLM, and flags
every number in the output as backed or unbacked by the source data.

**[Blog API](https://github.com/abdulkadir-yz/BlogApi)**
ASP.NET Core Minimal API · EF Core (SQLite) · ASP.NET Core Identity · JWT
REST API for users and posts with authentication, DTOs, validation filters and migrations.

**[FoodSharing](https://github.com/abdulkadir-yz/FoodSharing)** *(in progress)*
ASP.NET Core Minimal API · EF Core · Identity · JWT · React
Food sharing platform. Authentication is done; posts, comments, image upload
and the React frontend are in progress.

**[Events Platform](https://github.com/abdulkadir-yz/events-platform)**
React · Vite · React Router · Tailwind CSS
React frontend for an Express API, with auth flow and protected routes.

**[Fake E-Commerce](https://github.com/abdulkadir-yz/fake-e-commerce)**
Next.js (App Router) · React · Tailwind CSS
Product listing, dynamic product pages and a cart persisted with React Context and localStorage.

## Education & Certifications

- B.Sc. Electrical & Electronics Engineering, Honors (CGPA 3.43/4.00)
- Software Engineering & AI Bootcamp, WBS Coding School (in progress)
- AZ-900 Microsoft Azure Fundamentals (in progress, exam planned December 2026)

## Languages

🇹🇷 Turkish (native) · 🇬🇧 English (fluent) · 🇩🇪 German (B2 course completed, improving)

## Open to

Junior full-stack / .NET developer roles and internships in Germany.

## Contact

[Portfolio](https://abdulkadir-yz.github.io/) · [LinkedIn](https://www.linkedin.com/in/abdulkadiryilmaz) · [Email](mailto:abdulkadir.yz99@gmail.com)
