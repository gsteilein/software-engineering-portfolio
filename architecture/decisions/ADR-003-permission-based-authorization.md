# ADR-003 — Permission-Based Authorization

**Status:** Accepted  
**Project:** Detara  
**Decision Type:** Security / Authorization

---

## Context

Different employees inside the same company may require different levels of access to Detara.

A simple role-based model such as:

```text
Administrator
Manager
Employee
