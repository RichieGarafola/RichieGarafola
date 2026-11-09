# Richie Garafola

**Data engineer and financial analytics developer.** I build dependable data products for finance
and operations: pipelines that validate their inputs, reconciliations that explain every
difference, and reports that can be reproduced from source.

New York · open to remote roles · [LinkedIn](https://www.linkedin.com/in/richiegarafola)

## Featured work

### [ReconcileKit](https://github.com/RichieGarafola/ReconcileKit) — invoice-to-payment reconciliation
Reconciles an invoice register against a payment ledger in exact integer cents. Invalid and
duplicate rows are quarantined instead of guessed at. Totals tie out through a reconciliation
bridge whose arithmetic is checked on every run. Reviewer decisions go to an append-only audit
trail. Results are published as versioned, read-only SQL views and a Power BI report (PBIP).

Python · DuckDB SQL · Parquet · Power BI (DAX, Power Query) · Streamlit · **284 tests in CI**

<a href="https://github.com/RichieGarafola/ReconcileKit/tree/main/powerbi"><img src="https://raw.githubusercontent.com/RichieGarafola/ReconcileKit/main/powerbi/screenshots/1-reconciliation-overview.png" alt="ReconcileKit Power BI report: reconciliation overview page (synthetic demo data)" width="640"></a>

### [DeltaAnalysis](https://github.com/RichieGarafola/DeltaAnalysis) — dataset comparison · [**Live app**](https://deltaanalysis.streamlit.app)
Compares two versions of a CSV or Excel dataset in both directions. It finds records present in
only one file, field-level differences (with configurable numeric tolerances and date-aware
comparison), and duplicate or missing keys. Results export to an 11-sheet Excel report that is
traceable to source rows.

Python · pandas · openpyxl · Streamlit · **253 tests in CI** · v1.2.1

### More projects

| Project | What it does | Tests in CI |
|---|---|---|
| [etl-pipeline-builder](https://github.com/RichieGarafola/etl-pipeline-builder) | Runs raw CSV data through named, ordered transformation steps written as pure functions, with a per-step audit trail of row counts and timing | 69 |
| [budget-variance-analyzer](https://github.com/RichieGarafola/budget-variance-analyzer) | Compares budget and actuals by department, category, and month; classifies each line item with fixed variance thresholds and projects year-end spend from the year-to-date run rate | 72 |
| [financial-kpi-dashboard](https://github.com/RichieGarafola/financial-kpi-dashboard) | Computes 17 financial KPIs (profitability, liquidity, leverage, growth) from monthly P&L and balance-sheet data, with period-over-period changes | 44 |
| [docutil](https://github.com/RichieGarafola/docutil) | Command-line tool for repeatable DOCX ↔ Markdown conversion and batch document processing, designed for scripts and CI | — |

The sample datasets in the first five projects are synthetic or generated from a fixed random
seed, as documented in each repository.

## How I work

- Money is exact: no floating-point currency and no silent rounding.
- Automated findings and human decisions are stored separately, and history is appended rather than overwritten.
- Outputs are deterministic and covered by tests that run in CI on every change.
- I design reporting outputs to be traceable to their source records.

## Technical skills

- **Data engineering:** Python, pandas, SQL (DuckDB), Parquet, ETL design, data validation and data quality
- **Analytics and BI:** Power BI (DAX, Power Query, PBIP projects), Excel reporting automation (openpyxl), Streamlit
- **Engineering practice:** pytest, GitHub Actions, Git, command-line tool design, Docker

## Education and certifications

- B.S. Computer Science — Capella University (2026)
- Arizona State University FinTech Bootcamp
- CompTIA Project+
