# Software Engineering Portfolio

A collection of architecture case studies, technical decisions and engineering practices based on software products and systems I have designed and developed.

Most of my professional and product development work happens in **private repositories**, as many of these projects are commercial software products.

This repository exists to publicly document the **engineering practices, architecture decisions, technologies and challenges** behind those systems without exposing proprietary source code, business-sensitive information or customer data.

---

## Case Studies

### 🚗 Detara — Automotive Services Management SaaS

**Detara** is a SaaS platform designed to help automotive detailing and vehicle care businesses manage their operations.

The platform is being developed as a **multi-tenant modular monolith using .NET**, with explicit module boundaries, tenant isolation and a modern Blazor frontend.

#### Main technologies

`C#` · `.NET 10` · `ASP.NET Core` · `Blazor WebAssembly` · `MudBlazor` · `Entity Framework Core` · `SQL Server` · `Docker` · `JWT`

#### Engineering topics

* Modular architecture
* Multi-tenancy
* Authentication & authorization
* Domain boundaries
* Module and data ownership
* Responsive frontend architecture
* Containerized development environment
* SaaS product evolution

[View Detara Case Study →](case-studies/detara/README.md)

---

## Software Architecture

Beyond individual projects, this portfolio also documents the architectural principles and engineering practices that influence how I design and evolve software systems.

Topics include:

* Modular Monoliths
* Domain and module boundaries
* CQRS
* Multi-tenant architecture
* Authentication and authorization
* Messaging and asynchronous processing
* External integrations
* Background processing
* Caching
* Observability
* Infrastructure
* CI/CD
* Architectural trade-offs

The goal is not to promote a specific pattern or architecture, but to document **how technical decisions are evaluated according to product requirements, complexity and long-term maintainability**.

[Explore Software Architecture →](architecture/README.md)

### Architecture Decisions

Important architectural decisions are documented using lightweight Architecture Decision Records (ADRs).

- [ADR-001 — Modular Monolith Architecture](architecture/decisions/ADR-001-modular-monolith.md)
- [ADR-002 — Multi-Tenant Data Isolation](architecture/decisions/ADR-002-multi-tenant-data-isolation.md)
- [ADR-003 — Permission-Based Authorization](architecture/decisions/ADR-003-permission-based-authorization.md)

---

## What This Portfolio Focuses On

Rather than publishing isolated code samples, this portfolio focuses on how software is **designed, structured and evolved**.

The main areas documented here include:

### Architecture

How systems are divided into responsibilities, modules and application boundaries.

### Backend Engineering

APIs, application flows, domain rules, persistence, integrations and asynchronous processing.

### Frontend Engineering

Modern web interfaces, responsive layouts, component-based development and integration with backend services.

### Data

Data modeling, Entity Framework Core, relational databases, tenant ownership and persistence decisions.

### Security

Authentication, authorization, permissions and tenant isolation.

### Integrations

Communication with external APIs, payment providers and other systems while considering reliability, failures and consistency.

### Infrastructure

Docker, development environments, deployment practices and cloud infrastructure.

### Engineering Decisions

The reasoning, benefits, limitations and trade-offs behind technical choices.

---

## Engineering Philosophy

I believe software architecture should support the product rather than become an objective by itself.

My approach favors:

* Clear responsibilities
* Explicit boundaries
* Maintainable code
* Pragmatic abstractions
* Controlled dependencies
* Incremental architecture evolution
* Reliable integrations
* Production observability
* Reproducible environments

I try to avoid introducing architectural complexity without a concrete technical or business reason.

A solution should be sophisticated enough to solve the problem correctly, but simple enough to remain understandable and maintainable.

---

## Technologies

My main development ecosystem includes:

### Backend

`C#`
`.NET`
`ASP.NET Core`
`Entity Framework Core`

### Frontend

`Blazor WebAssembly`
`MudBlazor`
`HTML`
`CSS`

### Data

`SQL Server`
`PostgreSQL`
`Redis`

### Messaging & Background Processing

`RabbitMQ`
`MassTransit`
`Hangfire`

### Infrastructure

`Docker`
`Docker Compose`
`Azure`
`CI/CD`

### Architecture & Engineering

`Modular Monolith`
`Clean Architecture`
`CQRS`
`REST APIs`
`Multi-Tenancy`
`Permission-Based Authorization`
`Event-Driven Concepts`
`Observability`

---

## Commercial Software

Some systems presented in this repository are active commercial products.

For this reason:

* Proprietary source code remains private
* Credentials and secrets are never published
* Customer data is never exposed
* Internal infrastructure details may be omitted
* Sensitive business rules are not documented
* Architecture may be simplified when appropriate

The objective is to demonstrate **engineering reasoning and technical experience without compromising commercial intellectual property or security**.

---

## Repository Structure

```text
software-engineering-portfolio/
│
├── README.md
│
├── architecture/
│   └── README.md
│
└── case-studies/
    └── detara/
        ├── README.md
        └── assets/
```

As the portfolio evolves, additional case studies and architecture documentation may be introduced.

---

## Current Case Studies

| Project                                 | Type              | Main Topics                                                  | Status                |
| --------------------------------------- | ----------------- | ------------------------------------------------------------ | --------------------- |
| [Detara](case-studies/detara/README.md) | Multi-Tenant SaaS | Modular Monolith, Blazor, .NET, Multi-Tenancy, Authorization | 🟢 Active Development |

---

## Future Portfolio Evolution

This repository will evolve together with my software engineering experience.

Future additions may include:

* Additional architecture case studies
* Integration architecture
* Financial system engineering
* Messaging and asynchronous workflows
* Reference implementations
* Public technical projects
* Architecture diagrams
* Engineering decision records

The focus will remain on **quality and technical relevance rather than quantity of repositories or examples**.

---

## About Me

I'm **Gustavo Steilein Navroski**, a Full-Stack .NET Developer from Brazil 🇧🇷.

I work across backend and frontend development, primarily using the .NET ecosystem to build web applications, APIs, integrations and commercial software products.

My main interests include:

* Software architecture
* Modern .NET
* SaaS architecture
* Distributed systems
* System integrations
* Cloud environments
* Observability
* Performance and scalability

---

## Connect

You can find more about my work and experience here:

**GitHub:** [github.com/gsteilein](https://github.com/gsteilein)
**LinkedIn:** [Gustavo Steilein Navroski](https://www.linkedin.com/in/gustavo-steilein-29b483244/)
**Email:** [gustavosteilein@gmail.com](mailto:gustavosteilein@gmail.com)

---

> **Good architecture is not about using the greatest number of patterns.
> It is about making the right trade-offs for the system being built.**
