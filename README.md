# Richie Garafola

**Data engineer and financial analytics developer.** I build dependable data products for finance
and operations: pipelines that validate their inputs, reconciliations that explain every
difference, and reports that can be reproduced from source.

New York · open to remote roles · [LinkedIn](https://linkedin.com/in/richiegarafola)

## What I build

- **Reconciliation and validation.** Exact-decimal matching, quarantined bad records instead of
  guesses, and exception queues whose review history never alters the original findings.
- **Pipelines with data quality built in.** Typed ingestion, ordered and testable transformation
  steps, per-step audit logs, and explicit quality checks.
- **Reporting people can trust.** Versioned SQL reporting views, Power BI semantic models with
  documented DAX measures and Power Query, and Excel outputs traceable to source rows.
- **Automation that runs unattended.** CLI-first tools with automated tests and CI.

## Featured projects

| Project | What it does | Built with |
|---|---|---|
| [**ReconcileKit**](https://github.com/RichieGarafola/ReconcileKit) | Reconciles an invoice register against a payment ledger in exact integer cents. Quarantines invalid and duplicate rows, ties totals out through a reconciliation bridge checked on every run, keeps an append-only review trail, and publishes versioned read-only SQL views and a Power BI report. | Python · DuckDB SQL · Parquet · Power BI (DAX, Power Query, PBIP) · Streamlit · pytest · GitHub Actions |
| [**DeltaAnalysis**](https://github.com/RichieGarafola/DeltaAnalysis) | Compares two versions of a CSV or Excel dataset in both directions: records found in only one source, field-level differences with numeric and date tolerances, and duplicate identifiers. Produces an Excel report traceable to source rows. | Python · pandas · Streamlit · pytest |
| [**etl-pipeline-builder**](https://github.com/RichieGarafola/etl-pipeline-builder) | Runs raw CSV data through named, ordered transformation steps written as pure functions, and produces clean output with a per-step audit trail. | Python · pandas · Streamlit · pytest |
| [**budget-variance-analyzer**](https://github.com/RichieGarafola/budget-variance-analyzer) | Compares budget and actuals by department, category, and month. Classifies variances against configurable thresholds and projects year-end spend from the year-to-date run rate. | Python · pandas · Streamlit · pytest |
| [**docutil**](https://github.com/RichieGarafola/docutil) | A command-line tool for repeatable DOCX ↔ Markdown conversion and batch document processing, designed for scripts and CI. | Python · CLI · GitHub Actions |

## How I work

- Money is exact: no floating-point currency and no silent rounding.
- Automated findings and human decisions are stored separately, and history is appended rather than overwritten.
- Outputs are deterministic and covered by tests that run in CI on every change.
- Every reported number can be traced back to the source record it came from.

## Technical skills

- **Data engineering:** Python, pandas, SQL (DuckDB), Parquet, ETL design, data validation and data quality
- **Analytics and BI:** Power BI (DAX, Power Query, PBIP projects), Excel reporting automation, Streamlit
- **Engineering practice:** pytest, GitHub Actions, Git, command-line tool design, Docker

## Education and certifications

- B.S. Computer Science — Capella University (2026)
- Arizona State University FinTech Bootcamp
- CompTIA Project+
