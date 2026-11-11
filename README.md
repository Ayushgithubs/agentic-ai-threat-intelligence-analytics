# Agentic AI Threat Intelligence: Incident Analytics & Risk Prioritization

> 🚧 **Status: Under development**

## Problem Statement

Companies are rapidly deploying AI agents (coding assistants, MCP tool integrations, customer-support bots), and each one adds new attack surface. Security teams have limited time and budget, so they need to know where to start.

**This project analyzes 395+ documented real-world AI agent incidents (Dec 2024 to Oct 2026) to answer:**
*Which attack types are the most frequent, the most severe, and the most likely to cause confirmed real-world harm, and what should an enterprise secure first?*

## Tech Stack

| Layer | Tools |
|---|---|
| Database | Microsoft SQL Server |
| Data analysis | Python (pandas, SciPy, seaborn, matplotlib) |
| Querying | SQL (CTEs, window functions, views) |
| Visualization | Power BI |
| Version control | Git and GitHub |

## Dataset

*AI Agent Security & Real-World Incidents (2024-26)*, Orca AI Incident Archive (Continuum AI Corp), CC BY 4.0.

## Planned Deliverables

- [ ] Clean PostgreSQL schema and analytical view
- [ ] SQL analysis of attack types, severity, and confirmed harm
- [ ] Statistical tests (chi-square) in Python
- [ ] Risk priority matrix
- [ ] Power BI dashboard
- [ ] One-page recommendation memo

---
*Dataset credit: Continuum AI Corp, Orca AI Incident Archive (CC BY 4.0).*
