# Richie Garafola

### Data Engineering · Financial Analytics · Business Intelligence · Automation

**I build data systems that make complex information reliable, traceable, and actionable.**

I turn fragmented operational and financial data into validated pipelines, explainable reconciliations, and decision-ready reporting. My work spans federal financial reporting, business intelligence, workflow automation, and software development—with a focus on data integrity, reproducibility, and practical outcomes.

**Based in New York · Open to fully remote opportunities**  
[LinkedIn](https://www.linkedin.com/in/richiegarafola) · [Featured projects](#featured-projects) · [Technical toolkit](#technical-toolkit)

---

## Featured projects

### [DeltaAnalysis](https://github.com/RichieGarafola/DeltaAnalysis) — Know what changed. See exactly where.

**[Try the live application](https://deltaanalysis.streamlit.app) · [Source code](https://github.com/RichieGarafola/DeltaAnalysis)**

A comparison tool for auditing changes between CSV and Excel datasets. It helps answer three practical questions: **What's new, what's missing, and what changed?**

- Compares two snapshots in both directions, including added and removed records.
- Pinpoints field-level changes with configurable numeric tolerances and date-aware comparison.
- Flags duplicate and missing keys instead of silently treating them as reliable matches.
- Exports an **11-sheet Excel report** with findings traceable to source rows.

**Stack:** Python · pandas · openpyxl · Streamlit  
**Quality:** 253 tests in CI · v1.2.1

### [ReconcileKit](https://github.com/RichieGarafola/ReconcileKit) — Reconcile the numbers. Preserve the evidence.

An invoice-to-payment reconciliation system designed around exact arithmetic, exception handling, and a reviewable audit trail.

- Reconciles financial records in **integer cents**, without floating-point currency drift.
- Quarantines invalid and duplicate rows rather than guessing how to process them.
- Checks reconciliation-bridge arithmetic on every run.
- Records reviewer decisions in an append-only audit trail.
- Publishes versioned, read-only SQL views and a **Power BI report (PBIP)**.

**Stack:** Python · DuckDB SQL · Parquet · Power BI (DAX, Power Query) · Streamlit  
**Quality:** 284 tests in CI

[![ReconcileKit Power BI reconciliation overview, using synthetic demonstration data](https://raw.githubusercontent.com/RichieGarafola/ReconcileKit/main/powerbi/screenshots/1-reconciliation-overview.png)](https://github.com/RichieGarafola/ReconcileKit/tree/main/powerbi)

*ReconcileKit Power BI reconciliation overview — synthetic demonstration data.*

---

## More projects

| Project | Problem it tackles | Tests in CI |
| --- | --- | ---: |
| [ETL Pipeline Builder](https://github.com/RichieGarafola/etl-pipeline-builder) | Repeatable CSV transformations with per-step row-count and execution-time auditing | 69 |
| [Budget Variance Analyzer](https://github.com/RichieGarafola/budget-variance-analyzer) | Budget-versus-actual analysis, variance classification, and year-end projections | 72 |
| [Financial KPI Dashboard](https://github.com/RichieGarafola/financial-kpi-dashboard) | 17 financial KPIs across profitability, liquidity, leverage, and growth | 44 |
| [docutil](https://github.com/RichieGarafola/docutil) | Scriptable DOCX ↔ Markdown conversion and batch document processing | — |

*Demonstration datasets in the first five projects are synthetic or fixed-seed generated, as documented in their repositories. Public examples do not contain employer or client records.*

## Technical toolkit

| Area | Tools and methods |
| --- | --- |
| **Data engineering** | Python, pandas, SQL, DuckDB, PostgreSQL, Parquet, ETL pipelines, validation and data quality |
| **Analytics & BI** | Power BI, DAX, Power Query, PBIP, Excel, financial and operational reporting |
| **Automation & applications** | Streamlit, Power Automate, REST API integrations, openpyxl |
| **Engineering & delivery** | pytest, GitHub Actions, Git, Docker, reproducible workflows |

## How I engineer for trust

> A useful data product should make it possible to explain **where a result came from, how it was calculated, and why it can be trusted**.

- **Traceability:** Link reported results and exceptions back to original records.
- **Data integrity:** Surface invalid inputs, duplicate keys, and mismatches—not silent assumptions.
- **Reproducibility:** Produce consistent outputs from the same inputs.
- **Accountability:** Separate automated findings from human review decisions.
- **Testing:** Use continuous integration to catch regressions before they reach users.

## Background

- **B.S., Computer Science** — Capella University (2026)
- **FinTech Bootcamp** — Arizona State University
- **CompTIA Project+**
- Experience in federal financial reporting, financial analytics, business intelligence, and reporting automation.

## Let's connect

I'm interested in **fully remote data engineering, analytics engineering, business intelligence, and automation** opportunities—especially work that depends on trustworthy data and explainable reporting.

**[Connect on LinkedIn](https://www.linkedin.com/in/richiegarafola)**
