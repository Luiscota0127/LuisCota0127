# Hi, I'm Luis 👋

**Senior Fullstack .NET Developer** — I build distributed systems on .NET and modern web applications on TypeScript.

Currently working with event-driven architecture, service orchestration, and real-time web apps.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luiscota2701/)

---

## 🛠 Tech Stack

**Backend & Architecture**
![.NET](https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

**Messaging & Infrastructure**
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Frontend**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

## 🚀 Featured Work

### Platform — Distributed Task & Document Platform
A production-style microservices system built on .NET Aspire, where services are wired together through an orchestrator instead of hardcoded configuration.

**Highlights**
- Event-driven backbone with **Apache Kafka** for domain events and **RabbitMQ** for background work queues
- **YARP** API gateway fronting multiple services, with JWT protection and service discovery
- **ML.NET** multiclass classifier that consumes task events and republishes recommendations
- **Keycloak** for OIDC authentication, with a Blazor WebAssembly Kanban UI protected by login
- Real-time **SignalR** notifications pushing updates to the board
- Document pipeline with pluggable LLM analysis, OpenTelemetry, and health checks throughout
- **5 test projects** covering unit, integration, and end-to-end system tests

**Stack:** C# · .NET Aspire · Kafka · RabbitMQ · PostgreSQL · Redis · Keycloak · YARP · ML.NET · SignalR

### AspireApp — Fullstack Reference App
A clean, well-tested starting point for shipping .NET services: an orchestrated AppHost, a REST API with JWT + refresh tokens, and a Blazor Server frontend wired through service discovery.

**Highlights**
- Aspire orchestrator wiring Redis, API, and web frontend with health checks and startup ordering
- Authentication with **ASP.NET Core Identity**, JWT access tokens and refresh token rotation
- Blazor Server frontend using Aspire service discovery and Redis output caching
- A standalone WPF point-of-sale client alongside the web app
- Two test suites — NUnit host tests and xUnit integration tests via `WebApplicationFactory`

**Stack:** C# · .NET Aspire · Blazor · EF Core · SQLite · Redis · Docker

### Notas del Día — Shared to-do PWA
A progressive web app that replaces Notion for daily notes. Free text is the source of truth; tasks are parsed from it in the browser rather than stored as structured rows.

**Highlights**
- Custom ~200-line parser over `contenteditable`, deliberately avoiding heavy WYSIWYG editors
- **Next.js 16** with Supabase SSR auth and real-time sync between two devices
- Offline-capable PWA with Tailwind CSS 4 and a test-covered parser
- Locked visual design system replicating a Notion-like reading experience

**Stack:** TypeScript · Next.js 16 · React 19 · Supabase · Tailwind CSS 4 · Vitest

### desayunos-web — Offline-First Order Management
*Private project — happy to walk through the architecture.*

An Angular business app for a delivery operation, designed to keep working when the network does not.

**Highlights**
- **Angular 22** standalone components with an offline-first data layer
- **Dexie** (IndexedDB) for local storage with background sync to Supabase
- Real-time order updates via `postgres_changes` subscriptions
- Role-based access mapping users to *Repartidor* or *Vendedor*

**Stack:** TypeScript · Angular 22 · Supabase · Dexie

---

## 📚 Currently Learning

- Frontend architecture and interview fundamentals
- Applied ML with ML.NET inside event-driven systems
- Deeper Kafka, RabbitMQ, and message-delivery-pattern practice

---

## 📫 Let's Connect

Open to interesting conversations about distributed systems, .NET, or TypeScript.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luiscota2701/)
