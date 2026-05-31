# Project RxSpeed
## Prescription Fulfillment Optimization — CMedicare Plus Company

> A complete business analysis portfolio project demonstrating end-to-end BA delivery: from data analysis through requirements engineering, Agile execution, and interactive Tableau dashboards.

**Disclaimer:** This is a fictional portfolio project. CMedicare Plus Company, all individuals named, financial figures, and operational data are synthetically generated for demonstration purposes only.

---

## The Business Problem

CMedicare Plus, a 247-store retail pharmacy chain operating across 12 US states, experienced a 59% increase in average prescription wait times over 24 months (from 19.2 to 30.6 minutes), driving customer attrition and an estimated $88M in annual lost revenue.

This project delivers a data-driven analytics solution that empowers pharmacy leadership and store managers to identify bottlenecks and improve fulfillment efficiency.

---

## Key Findings (From Baseline Analysis)

- Wait times doubled over 24 months, now averaging 30.6 minutes (target: 15 minutes)
- 70% of prescriptions exceed the 15-minute target
- Midwest stores run 30% slower than Southeast stores (24.8 vs 19.0 min)
- Peak-hour bottlenecks at 11am-1pm and 5pm-7pm (up to 34 min)
- Customer satisfaction collapses from 9.5 (under 10 min wait) to 3.4 (over 30 min)
- $88M revenue at risk annually, with $35M conservatively recoverable

---

## Solution

A two-tier Tableau dashboard:

- **Executive Overview** — KPI scorecard, state map, and wait-time trend for leadership
- **Operational Detail** — Heatmap, store ranking, regional comparison, and satisfaction correlation for managers

Both dashboards feature interactive filtering, role-based views, and a HIPAA-compliant data layer.

---

## Repository Structure

- **01_Initiation/** — Charter, Business Case, Stakeholder Register, RACI, KPI Framework
- **02_Requirements/** — As-Is and To-Be Process Flows, BRD, FRD, Requirements Traceability
- **03_Agile_Artifacts/** — Product Backlog, Sprint Plans, Ceremonies
- **04_Design_and_Dashboard/** — Data Dictionary, Wireframes
- **05_UAT_and_Closure/** — UAT Plan, Closure Report, Lessons Learned
- **data/** — Synthetic datasets (CSV)
- **notebooks/** — Python notebooks for data generation and baseline analysis
- **outputs/** — Generated charts and analytical outputs
- **Project_Journal.md** — Session-by-session work log

---

## Methodology

This project follows a hybrid SDLC + Agile approach across six phases:

| Phase | Focus |
|-------|-------|
| 1. Initiation | Charter, Business Case, Stakeholder Analysis, KPI Framework |
| 2. Requirements | Process flows, BRD, FRD, Traceability Matrix |
| 3. Agile Execution | Product Backlog, Sprint Plans, Ceremonies |
| 4. Design and Build | Data Dictionary, Wireframes, Tableau Dashboards |
| 5. UAT and Closure | Test Plan, Closure Report, Lessons Learned |
| 6. Portfolio Publishing | This repository |

---

## Data Foundation

A star-schema synthetic dataset, designed to mirror real pharmacy operations:

| Dataset | Type | Rows |
|---------|------|------|
| stores.csv | Dimension | 247 |
| staff.csv | Dimension | ~2,500 |
| prescriptions.csv | Fact (transactional) | 500,000 |
| customer_satisfaction.csv | Fact (linked) | 50,000 |
| daily_store_metrics.csv | Aggregate (derived) | ~150,000 |

The data is engineered to include realistic temporal patterns (peak hours, seasonality), regional performance variance, drug complexity factors, and a deliberate wait-time decline trajectory — providing an evidence base for every downstream artifact.

---

## Tools Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn) — Data generation and baseline analysis
- **Tableau Public** — Dashboard development
- **Markdown** — Documentation
- **VS Code** — Development environment
- **Git / GitHub** — Version control and portfolio hosting

---

## Skills Demonstrated

- Requirements engineering with full traceability (Finding to Objective to BR to FR to Test Case)
- Quantitative baseline analysis to validate business problems
- Star-schema data modeling and simulation
- Agile and Scrum delivery (user stories, sprints, ceremonies, retrospectives)
- Stakeholder analysis (RACI, Power/Interest Grid)
- KPI framework design across strategic, operational, process, and leading-indicator tiers
- Interactive dashboard design with role-based views and cross-source data blending
- UAT planning with test cases tied directly to functional requirements
- Intellectual honesty about analytical limits (proven vs hypothesized findings)

---

## Author

Cizen Bhatta
Business Analyst (Portfolio Project)
cijanbhatta@gmail.com
https://www.linkedin.com/in/cizen/