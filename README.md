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

**Formula concept: HMS = 0.5 × Hiring Velocity Score + 0.5 × Strategic Focus Score**

Scores above **65 indicate strong growth signals**.

---

## Key Insights

The analysis identified **five companies showing >2× hiring spikes**, indicating strong growth momentum.

| Company | Spike Ratio | HMS Score |
|--------|-------------|-----------|
| Cred | 2.67 | 93 |
| Jupiter | 3.00 | 93 |
| Navi | 2.00 | 92 |
| Pine Labs | 3.00 | 92 |
| Razorpay | 2.25 | 93 |

These companies showed concentrated hiring in **AI engineering, product roles, and compliance teams**, suggesting:

- AI-driven credit products
- Regulatory market expansion
- Platform infrastructure scaling

---

## Product Concept: Investor Signal Layer

Based on the analysis, the project proposes a product feature called **Investor Signal Layer**.

The platform would transform raw hiring data into **investment intelligence for venture capital firms**.

Key features include:

- Hiring momentum alerts
- Company expansion insights
- Sector hiring heatmaps
- Portfolio monitoring for VC firms
- Historical trend validation

This enables investors to identify high-growth startups **3–6 months before funding announcements**.

---

## Tools Used

- **Microsoft Excel** – Data analysis and scoring model
- **Manual role classification** – Strategic hiring signals
- **Product analysis frameworks** – ICP, GTM strategy, and competitive analysis

---

## Repository Contents

dataset & hms_model.xlsx
assignment_submission.pdf
assignment_instruction.pdf

---

## Potential Improvements

Future enhancements could include:

- Backtesting hiring spikes against historical funding rounds
- Expanding the dataset to multiple industries
- Automating job data ingestion from job boards
- Applying statistical validation models

---

## Author

**Viresh Kumar**  
MBA – Business Analytics  
UPES (University of Petroleum and Energy Studies)
