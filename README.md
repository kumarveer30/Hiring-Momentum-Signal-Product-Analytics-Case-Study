# Hiring Momentum Signal – Product Analytics Case Study

## Overview
This project explores how **job posting data can be used as an early signal of startup growth**. By analyzing hiring patterns across Indian FinTech companies, the project identifies signals that may indicate **product expansion, infrastructure scaling, or geographic market entry**.

The project was developed as part of a **Product Management assignment using JobsPikr-style job intelligence data**, demonstrating how hiring intelligence can be transformed into a decision-support tool for venture capital investors.

---

## Problem Statement
Venture capital firms often discover startup opportunities **after funding announcements or product launches**, when valuations are already high and competition for deals increases.

However, companies typically **hire talent months before these public events**. By analyzing hiring patterns across roles, locations, and hiring velocity, investors can identify startups entering rapid growth phases earlier.

---

## Dataset
The prototype dataset includes:

- **130 job postings**
- **20 Indian FinTech companies**
- Time window: **Dec 2025 – Jan 2026**

Data fields include:

- Company name
- Job title
- Job category
- Skills
- Location
- Job description

The dataset structure mirrors the format of **JobsPikr job intelligence data**.

---

## Methodology

### 1. Hiring Velocity Analysis
Measures the change in job postings between months.

| Hiring Spike | Signal |
|---------------|--------|
| > 2× | Rapid scaling |
| 1.2× – 2× | Moderate growth |
| < 1.2× | Stable hiring |

---

### 2. Strategic Role Analysis
Not all hiring signals growth. Roles were weighted based on their strategic importance.

| Role Category | Weight |
|---------------|--------|
| AI / ML Engineering | 95 |
| Data Science | 90 |
| Product Management | 85 |
| Engineering Leadership | 80 |
| Risk & Compliance | 75 |
| Sales / GTM | 60 |
| Operations / Support | 40 |

Technical and product hiring is treated as **stronger indicators of strategic expansion**.

---

### 3. Hiring Momentum Score (HMS)

The final metric combines:

- Hiring velocity
- Strategic role composition

Formula concept:
