# Andrew R. Goad

## Senior Analytics & Applied Data Science Leader

**Enterprise Decision Systems | Consumer Credit & Risk Analytics | Data Governance & Model Validation**

> **No Cold Handoffs:** Logic, controls, validation, evidence, and interpretation travel together.

Senior analytics and applied data science leader with **16+ years of experience** across Wells Fargo, the Office of the Comptroller of the Currency, and the U.S. Census Bureau.

I build and validate governed decision systems that connect:

- business and regulatory requirements
- source-data lineage and fitness
- analytical methodology
- decision and treatment logic
- implementation controls
- independent validation
- monitoring and exception evidence
- executive interpretation

At Wells Fargo, I was promoted from Vice President to Executive Director while serving as principal analytical architect for Consumer Auto programs exceeding **$1B in exposure and customer impact**. My work included seven years of CPI analytical-system ownership, leadership across **15+ additional remediations**, enterprise credit-furnishing governance, and advisory or peer-review support for **10+ additional credit-reporting matters**.

At the OCC, I supported 16 economists and examination teams with longitudinal consumer-credit data, survival and logistic modeling, CECL and life-of-loan PD analysis, credit benchmarking, and published research support.

This portfolio demonstrates how those professional disciplines translate into proactive credit strategy, model and decision validation, forensic data engineering, remediation testing, and executive-ready analytical evidence.

[LinkedIn Profile](https://www.linkedin.com/in/andrewrgoad)

---

## Portfolio Mission

This GitHub portfolio is a public proof layer for governed analytics and decision-system architecture.

The repositories are not isolated notebooks or dashboard demonstrations. Each project pairs code with some combination of:

- business and analytical requirements
- parameter and strategy controls
- synthetic or demonstration data
- QA and validation evidence
- reconciliation and exception outputs
- run registries and archive tables
- executive summaries
- technical runbooks

The repository organization reflects the same professional documentation and version-control discipline I used at Wells Fargo.

---

## Enterprise Decision-System Lifecycle

```text
Data Fitness and Integrity
→ Reconciliation and Signal Detection
→ Model or Strategy Development
→ Scenario and Challenger Testing
→ Decision or Treatment Execution
→ Financial and Customer-Impact Quantification
→ Monitoring, Validation, and Executive Evidence
```

The recurring design pattern is:

```text
Governed Inputs
→ Transparent Logic
→ Configurable Parameters
→ Account-Level Outcomes
→ Validation Evidence
→ Executive Interpretation
→ Reproducible Handoff
```

---

## Repository Map

### 1. [credit_decisioning_strategy](https://github.com/andrew-goad/credit_decisioning_strategy)

**Enterprise Credit Decisioning Strategy Simulator — PostgreSQL**

Governed simulator for deterministic synthetic applications, estimated PD, LGD, Expected Loss, affordability, exposure, counteroffer, review, approval, and decline logic.

Demonstrates:

- synthetic application and risk generation
- configurable credit-policy strategies
- baseline and challenger comparison
- matched-population analysis
- counteroffer feasibility and governance
- reason-code traceability
- strategy-frontier analysis
- archive-backed evidence
- post-campaign validation

---

### 2. [forensic-data-integrity](https://github.com/andrew-goad/forensic-data-integrity)

**Forensic Data Integrity Gatekeeper — Python**

Pre-model diagnostic engine that evaluates raw dataset health before analytical or decision-system use.

Detects and summarizes:

- hidden and disguised nulls
- dominant-value concentration
- zero-variance fields
- formatting defects
- inconsistent data types
- anomalous distributions
- data-quality severity and prioritization

Produces audit ledgers, executive scorecards, and validation-ready handoff evidence.

---

### 3. [enterprise-reconciliation-reporting](https://github.com/andrew-goad/enterprise-reconciliation-reporting)

**Enterprise Reconciliation Reporting — SAS**

Metadata-driven A/B validation framework for large-scale dataset comparison.

Supports:

- schema-drift diagnostics
- key-only and value-level differences
- absolute and relative numeric tolerances
- date, time, and datetime tolerances
- character normalization
- duplicate-key testing
- severity-ranked exceptions
- run metadata and UAT assertions
- controlled CSV evidence exports

Designed to reduce false positives while preserving reproducible, reviewable evidence.

---

### 4. [metro2-remediation-sandbox](https://github.com/andrew-goad/metro2-remediation-sandbox)

**Metro 2 Remediation Sandbox — PostgreSQL**

Synthetic longitudinal credit-reporting environment for controlled remediation design and testing without PII.

Includes:

- five-million-account baseline portfolio
- month-level performance truth tables
- financial and credit-impact windows
- cure and manual-review logic
- treatment assignment
- delta-based remediated fields
- before-and-after validation
- customer-impact and population evidence

Demonstrates governed remediation testing, temporal state management, and explainable credit-reporting outcomes.

---

### 5. [insurance-coverage-reconciliation](https://github.com/andrew-goad/insurance-coverage-reconciliation)

**Insurance Coverage Reconciliation — SAS**

Metadata-driven interval-reconciliation engine for comparing proof-of-coverage evidence with lender-placed CPI policy windows.

Demonstrates:

- overlapping-interval consolidation
- date and coverage validation
- configurable lapse thresholds
- policy-adjustment factors
- parameter governance
- transparent customer-impact logic
- account-level audit evidence

---

### 6. [financial-tvm-optimization](https://github.com/andrew-goad/financial-tvm-optimization)

**Treasury-Indexed Remediation Liability Engine — SAS**

Memory-efficient financial recalculation engine using one-year Constant Maturity Treasury rates and custom SAS functions.

Technical features include:

- PROC FCMP
- in-memory two-dimensional arrays
- chunked account processing
- annual compounding
- final remainder-interest calculations
- account-level recalculation evidence
- executive liability summaries

Demonstrates scalable financial-redress calculation while controlling processing and memory demands.

---

### 7. [survival-retention-engine](https://github.com/andrew-goad/survival-retention-engine)

**Survival Retention and Scenario Engine — Python**

End-to-end time-to-event modeling and scenario-analysis framework.

Combines:

- K-Means personas
- Kaplan-Meier curves
- Cox proportional hazards
- customer and segment risk analysis
- high-risk scenario simulation
- time-to-event runway
- automated PPTX and PDF reporting
- technical and executive model evidence

Demonstrates survival modeling, scenario-based risk reduction, segmentation, and interpretable analytical reporting.

---

## Featured Build: Enterprise Credit Decisioning Strategy Simulator

[View the repository](https://github.com/andrew-goad/credit_decisioning_strategy)

A two-module PostgreSQL decisioning environment demonstrating how synthetic risk generation, policy controls, strategy testing, account-level outcomes, and executive evidence can operate together without exposing PII or proprietary credit policy.

### Module 1 — Synthetic Application and Risk Engine

Generates deterministic synthetic application populations with:

- product type
- score band
- borrower profile
- requested exposure
- APR proxy
- monthly payment
- payment-to-income ratio
- estimated-PD proxy
- LGD
- Expected Loss

**Campaign scope:**

- 19 governed scenarios
- 50,000 applications per scenario
- 950,000 archived scenario rows
- product-by-score risk surfaces
- configurable scenario levers
- Expected-Loss impact decomposition

### Module 2 — Credit Policy and Decision Strategy Engine

Consumes Module 1 outputs and applies configurable policy and treatment controls to simulate:

- approvals
- counteroffers
- manual reviews
- declines
- approved exposure
- approved Expected Loss
- affordability and exposure constraints
- selective and aggressive counteroffer paths
- baseline and challenger comparisons
- strategy-frontier trade-offs

**Campaign scope:**

- 39 governed strategy runs
- 50,000 applicants per run
- 1.95 million archived decisions
- 20 matched comparison groups
- seven scenario families
- baseline-relative challenger analysis
- reason-code and path evidence

### Why the Project Matters

The simulator demonstrates:

- governed credit-strategy architecture
- pre-production decision testing
- configurable policy and product controls
- account-level reason codes
- matched-population comparison
- Expected Loss and affordability trade-offs
- archive-backed evidence
- challenger-strategy assessment
- counteroffer governance
- executive decision support

It is not a dashboard-only demonstration. The repository includes relational implementation, synthetic samples, strategy controls, QA outputs, archived campaign evidence, validation artifacts, and executive reporting.

---

## Professional Foundation

### Wells Fargo — Enterprise Decision Systems and Consumer Auto

Promoted from **Vice President – Lead Analytics Consultant** to **Executive Director – Senior Lead Analytics Consultant** while serving as principal analytical architect for regulated Consumer Auto programs.

Selected experience includes:

- Led analytical workstreams across **15+ remediations** under the Remediation Target Operating Model.
- Served as furnishing SME, peer reviewer, and mentor on **10+ additional credit-reporting remediations**.
- Owned analytical methodology, population logic, SAS/SQL code, outputs, run procedures, and validation evidence from issue intake through execution readiness.
- Authored and presented executive Decision Forum analyses covering risks, facts, options, customer implications, controls, and recommendations.
- Designed and operated Direct and Indirect Auto CPI recalculation systems from **2018–2025**, including proof-of-insurance QA, financial redress, time-value-of-money relief, prior-payment netting, decision-path flags, and recurring production controls.
- Independent Audit found **100% alignment** between retained proof-of-insurance evidence and third-party vendor data.
- Led CPI credit-reporting redress for approximately **850,000 accounts** through approximately **200 external mass-maintenance submissions**, with corresponding internal system-of-record updates.
- Designed an account- and impact-month-specific re-furnishing strategy that preserved favorable reporting and saved approximately **$60,000 per submission**.
- Consolidated **500+ multi-line-of-business submissions** representing more than **100 million account-month furnishing actions**.
- Established account-month SQL controls aligning remediation history with recurring furnishing data to prevent favorable-state overwrites.
- Led UAT and a **20-million-record historical correction**, reconciling inputs, rules, outputs, and exceptions.
- Built reusable execution Standard Data Format, Teradata archival, tax-reporting, and implementation-support processes.

### Office of the Comptroller of the Currency — Credit-Risk Modeling and Research

Supported **16 economists and examination teams** with model-ready data, analytical methods, validation logic, and decision evidence.

Selected experience includes:

- Developed and tested Cox proportional hazards and discrete-time survival/logistic frameworks for delinquency, default, and prepayment.
- Constructed and validated longitudinal bureau panels spanning **875,516 loans** and **2,363,261 loan-year observations**.
- Supported borrower, loan, macroeconomic, term-age, prime/subprime, lifetime-risk, and pricing analysis.
- Led review of third-party PD vendor contracts and evaluated data fitness for CECL and life-of-loan PD analysis.
- Built syndicated-credit entity-resolution and fuzzy-matching logic for cross-bank internal risk-rating comparisons.
- Developed obligor-level sequencing logic for first, second, and subsequent delinquency/default events across products.
- Built ArcGIS branch-distance measures for loss-mitigation analysis.
- Developed a Python market-data collector polling stock quotes at one-second intervals for review against macroeconomic events.
- Built a 10,000+ document conversion and SAS ingestion pipeline for fair-housing analysis.
- Provided technical direction and mentoring to junior analysts and interns.

The authors of both the peer-reviewed and OCC long-term auto-loan studies publicly acknowledged me for **“excellent research support.”**

### U.S. Census Bureau — Federal Statistical Production and Validation

Modernized national survey systems supporting the Annual Capital Expenditures Survey and Annual Retail Trade Survey.

Selected experience includes:

- Architected a SAS-orchestrated pipeline refreshing Access tables and JavaScript/HTML dashboards.
- Led a six-analyst nightly production operation and served as escalation point for processing and data-quality issues.
- Designed analyst views prioritizing major year-over-year discrepancies and high-impact nonrespondents.
- Automated executive-ready industry narratives, completion summaries, and management reporting.
- Built SAS-to-Excel/VBA validation workbooks for analyst-controlled, on-demand review.
- Developed editing, imputation, outlier, disclosure-avoidance, benchmarking, and documentation controls.

---

## Technical Toolkit

### Professional Engineering and Analytics

- SAS Enterprise Guide
- SAS macro programming
- PROC SQL and PROC FCMP
- SQL and Teradata
- Python
- Git/GitHub
- Tableau
- ArcGIS
- Excel/VBA
- Microsoft Access
- JavaScript/HTML
- PuTTY batch processing
- SharePoint
- Jira
- PowerPoint
- high-volume ETL
- metadata-driven processing
- controlled data delivery

### Portfolio Platforms and Libraries

- PostgreSQL
- pandas
- NumPy
- scikit-learn
- lifelines
- matplotlib
- openpyxl
- python-pptx
- ReportLab
- relational data modeling
- archive and evidence tables

### Modeling and Decision Science

- Cox proportional hazards
- Kaplan-Meier analysis
- discrete-time survival and hazard models
- binary and multinomial logistic regression
- ordinary least squares
- K-Means clustering
- probability of default
- loss given default
- Expected Loss
- CECL and life-of-loan PD
- scenario and sensitivity analysis
- policy-rule simulation
- champion/challenger comparison
- strategy-frontier analysis

### Validation and Governance

- independent recalculation
- benchmark and challenger analysis
- matched-population comparison
- source-to-target reconciliation
- data-quality and lineage review
- UAT and acceptance testing
- reasonableness and sensitivity testing
- monitoring and exception management
- documentation standards
- effective challenge
- executive decision evidence

### Domain Experience

- consumer credit risk
- auto finance
- credit-bureau and Metro 2 furnishing
- FCRA
- CECL
- PD, LGD, and Expected Loss
- CPI
- SCRA
- loss mitigation
- syndicated credit
- federal bank supervision
- remediation and customer-impact analytics

---

## Education and Professional Development

- **Bachelor of Arts in Economics, Minor in Mathematics** — Virginia Tech, 2005–2009
- **SAS Base Programming Certification** — 2009
- **SAS Advanced Programming Professional Certification** — 2009
- **Lean Six Sigma Yellow Belt** — Office of the Comptroller of the Currency, 2016
- **Associate Citation in Project Management** — George Washington University, 2013

---

## Portfolio Philosophy

### No Cold Handoffs

A system is not complete when the code runs or the output is produced.

A system is complete when the relevant stakeholders can understand:

- what question was being answered
- which data were used
- how the logic operated
- which assumptions and parameters mattered
- how the output was tested
- which controls were applied
- what exceptions remain
- how the result should influence a decision

That philosophy appears throughout the portfolio:

```text
Data integrity before modeling
Validation before reliance
Strategy testing before implementation
Reason codes before unexplained outcomes
Reconciliation before closure
Documentation before handoff
```

The objective is not complexity for its own sake. It is analytical work that is transparent, reproducible, governable, and useful.

---

## Data and Confidentiality Boundary

All public repositories use synthetic, anonymized, or demonstration data.

These projects do not expose:

- customer or personally identifiable information
- employer-owned code
- production credit policy
- proprietary remediation rules
- confidential model inputs
- regulated operational pipelines
- internal systems or restricted documentation

The repositories are designed to demonstrate transferable methodology, architecture, validation discipline, documentation quality, and executive communication in a public setting.

---
