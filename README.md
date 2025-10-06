# :jigsaw: Risk & Reporting Automation Dashboard 
**Organization:** Wells Fargo 
**Role:** Associate Operations Processor (2023–2024) 
**Domain:** Risk & Compliance Analytics | Process Automation 
---
## :blue_book: Overview 
This project focuses on building an internal **risk monitoring and reporting automation** framework using **RIDS** (Wells Fargo’s internal reporting tool) and **Excel-VBA scripting**. 
The goal was to reduce manual data handling errors, accelerate fraud detection, and improve operational visibility across financial risk functions.
---
## :dart: Objectives 
Streamline and automate monthly and weekly **risk reporting workflows**. 
Improve accuracy and timeliness of **fraud detection metrics**. 
Reduce manual effort by introducing **ETL-style automation** through Excel-VBA. 
Deliver interactive dashboards for leadership decision-making.
---
## :gear: Tech Stack & Tools 
| Category | Tools / Skills |
|-----------|----------------|
| Data Source | RIDS internal tool, CSV data exports |
| Transformation | Excel, VBA Macros, Data Validation, Pivot Tables |
| Visualization | Excel Dynamic Dashboards, Conditional Formatting |
| Reporting | Automated PDFs, Summary Dashboards |
| Concepts | ETL Workflow (Extract–Transform–Load), Risk Scoring, KPI Tracking |
---
## :arrows_counterclockwise: ETL Workflow Breakdown 
**1. Extract** 
Pulled operational and transactional data from RIDS into Excel via CSV exports. 
Scheduled extraction based on daily and weekly cut-offs for accuracy.
**2. Transform** 
Cleaned data (removed duplicates, normalized values, categorized risk levels). 
Applied formulas and VBA scripts to derive **fraud flags**, **resolution times**, and **trend indicators**.
**3. Load** 
Automated dashboard updates using macro buttons and dynamic pivot refresh. 
Exported summarized results into shareable Excel & PDF reports.
---
## :bar_chart: Key Performance Metrics 
| Metric | Description |
|--------|--------------|
| **Risk Alerts** | Number of high-risk or flagged accounts per week |
| **Resolution Time** | Average hours taken to resolve escalated cases |
| **Data Accuracy Rate** | % reduction in reporting errors after automation |
| **Fraud Detection Speed** | Improvement in identifying potential fraud patterns |
---
## :rocket: Results & Impact 
:white_check_mark: **Reduced reporting errors by 15%** through process automation. 
:zap: **Cut dashboard preparation time from 3 hours to 30 minutes.** 
:mag: Enabled **20% faster fraud detection** by improving data refresh cadence. 
:chart_with_upwards_trend: Delivered consistent weekly & monthly dashboards for senior risk leadership. 
:recycle: Templates were **standardized and replicated** across other operational units.
---
## :file_folder: Folder Structure 
```plaintext
wells-fargo-risk-dashboard/
│
├── data-sample/                   # anonymized mock data samples
│   └── transactions_sample.csv
│
├── vba-scripts/
│   └── dashboard_refresh.vba      # macro for data automation
│
├── reports/
│   ├── monthly_risk_summary.pdf
│   └── weekly_dashboard.xlsx
│
├── visuals/
│   ├── dashboard_snapshot.png
│   └── trend_chart_example.png
│
└── README.md                      # this file






