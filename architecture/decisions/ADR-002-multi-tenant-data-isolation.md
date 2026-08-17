# ADR-002 — Multi-Tenant Data Isolation

**Status:** Accepted  
**Project:** Detara  
**Decision Type:** Security / Data Architecture

---

## Context

Detara is a multi-tenant SaaS platform.

Multiple automotive businesses use the same application infrastructure while maintaining independent users, customers, vehicles, services and configurations.

This creates a fundamental security requirement:

> Data belonging to one company must never be accessible by another company.

Tenant isolation cannot rely exclusively on frontend filtering.

Even if the user interface only displays data associated with the current company, backend operations must independently enforce ownership.

---

## Decision

Tenant ownership will be treated as a **core architectural concern** throughout Detara.

Business entities that belong to a company must maintain an explicit relationship with that tenant.

A simplified model is:

```text
Authenticated User
        │
        ▼
     Company
        │
        ▼
 Tenant Context
        │
        ▼
 Application Operation
        │
        ▼
 Tenant-Owned Data
