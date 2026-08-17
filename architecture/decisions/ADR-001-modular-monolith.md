# ADR-001 — Modular Monolith Architecture

**Status:** Accepted  
**Project:** Detara  
**Decision Type:** Architecture

---

## Context

Detara is a commercial SaaS product designed for automotive detailing and vehicle care businesses.

The application is expected to grow through multiple business capabilities, including:

- Platform and identity
- Customers and vehicles
- Service catalog
- Scheduling
- Service operations
- Financial management
- Additional operational modules

At the current stage of the product, development speed, maintainability and architectural clarity are more important than independent deployment of individual business capabilities.

Introducing microservices at this stage would add distributed-system complexity without providing a proportional business or technical benefit.

---

## Decision

Detara will use a **modular monolith architecture**.

The backend remains a single deployable application while business capabilities are organized into explicit modules with clearly defined ownership and boundaries.

Current modules include:

```text
Detara
│
├── Platform / Identity
├── Customers
└── Catalog
