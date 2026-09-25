# Andrew R. Goad

**Senior Analytics & Applied Data Science Leader · Decision Systems · Consumer Credit · AI-Enabled Delivery**

**I build analytical products that turn complex data into decisions people can understand, test and carry into the next operational step.**

My 16+ years span Wells Fargo, the Office of the Comptroller of the Currency and the U.S. Census Bureau. At Wells Fargo, I advanced to Senior Lead Analytics Consultant at the Executive Director level, advising leaders on remediation strategy and challenging proposed directions when I identified risk. This independent portfolio makes my current AI-assisted work in credit strategy, analytical engineering, statistical modeling and business-facing decision intelligence available to inspect.

> **No Cold Handoffs:** the logic, evidence, interpretation and ownership travel together.

[LinkedIn][linkedin] · [Leadership case study](#leadership-method) · [Featured products](#featured-work) · [Domain tools](#domain-tools) · [Professional foundation](#professional-foundation)

**Explore Power BI:** [Merchant decisions and account journeys](#msbf-power-bi) · [Version validation and application-level change](#cds-power-bi)

<a name="leadership-method"></a>
## Human-in-the-Loop Analytical Leadership

**A case study in directing cross-functional, task-specific AI workstreams.**

Using Merchant Sales-Based Financing as the case, I coordinated specialized reporting, remediation/build and separate review conversations while retaining responsibility for business decisions. The report shows the original interactions, the questions that redirected the work, and the evidence used to verify the results.

**[Read the full case study · 35 pages][hitl-report] · [Browse the LinkedIn carousel · 13 pages][hitl-carousel]**

[![Agree on direction. Delegate the work. Retain judgment. Original human instruction authorizing substantial AI-assisted execution after context and strategy were established, with key decisions reserved for human judgment.][hitl-mandate-image]][hitl-report]

*Original instruction from the case study: context supplied, execution delegated, judgment retained. [Open the instruction at full resolution][hitl-mandate].*

- **Prepare the work for substantial execution.** Bring requirements and evidence across workstreams, agree on direction, and define when consequential decisions must return for human judgment.
- **Keep questioning after acceptance.** Challenge an accepted rule, investigate behavior that does not make business sense, and propose a mechanism the evidence can test.
- **Verify the change and teach the method.** Reconcile both the intended correction and the facts that should remain unchanged, obtain separate challenge, and make the reasoning usable by another person.

*Independent, synthetic, non-production case. The conversations were human-coordinated and did not communicate autonomously. Separate AI-assisted project review is not external professional assurance.*

<details>
<summary><strong>Take the method into your next analytical problem</strong></summary>

**Frame → Trace → Challenge → Test → Reconcile → Review → Return → Teach**

[![Eight reusable analytical leadership questions: frame the business concern, trace source evidence, challenge the rule, test explanations, reconcile changes and unchanged facts, seek review, return to reporting, and teach the reasoning.][hitl-method-image]][hitl-method]

*Stay accountable across the loop, including after an acceptance milestone. [Open the method at full resolution][hitl-method] · [See the verification and reconciliation example][hitl-reconcile].*

</details>

**Do not stop at the output. Challenge the reasoning. Teach the method.**

---

<a name="featured-work"></a>
## Featured analytical products

*Independent, synthetic, non-production demonstrations. Screenshots open in the browser; the linked Power BI files open in Power BI Desktop—not as hosted live dashboards.*

<a name="msbf"></a>
### Merchant Sales-Based Financing (MSBF) · Merchant Credit Intelligence

**What financing can a merchant support, why, and what happens after funding?**  
PostgreSQL · Python · Power BI

I designed and published a sales-based merchant-financing product demonstration connecting acquisition, sales and settlement, liquidity, obligations and cash-flow capacity to product economics, financing terms and the funded-account lifecycle. Strong sales alone do not establish capacity; finding supportable terms does not automatically confer approval.

<a name="msbf-power-bi"></a>
#### Power BI: explain the decision—and follow the account

**P03 Application Journey** joins merchant backstory, operating evidence, risk/economics and decision narratives to remittance, monitoring and servicing for funded paths. The narratives preserve source-engine rationale; Power BI explains the decision rather than making it.

[![MSBF P03: synthetic merchant 738 in Baseline, with operating evidence, financing rationale and the funded account's performance, monitoring and servicing.][msbf-p03-image]][msbf-p03]

*Original P03 view, merchant 738 / Baseline. Risk/loss fields are **Current Portfolio — synthetic estimated-PD proxy, LGD, EAD/exposure, and comparative Expected Loss**—not calibrated lending risk or realized profit. Activity after the 23 July 2026 source cutoff is synthetic-forward through 22 November 2026. [Open full resolution][msbf-p03].*

The four-page application connects **cohort context → performance over time → individual merchant explanation → servicing and attention**. Industry, acquisition-source, scenario and date controls let a reviewer move from the portfolio to the account behind it.

I challenged premature decline logic and redesigned constrained-counteroffer search. On the same **750 synthetic merchants across two scenarios**, reportable structures expanded from **557 to 6,519**, while evidence requirements, hard-policy stops and distinct review/authorization outcomes remained in place. [Inspect the version comparison][msbf-changes].

Narrative QA covers all **1,500 application-scenario paths**. The funded demonstration follows **130 scenario paths for 120 days**, keeping recommendations, permissions, synthetic servicing and reconciliation distinct.

**See the distinction under Recession Energy:** [merchant 738 versus merchant 098][msbf-cases]. Merchant 738 lacks required evidence, while merchant 098 receives an authorized counteroffer after a feasible structure is found. The 738 image above shows its separate Baseline outcome. Different terms can repair a financing structure; they cannot replace required evidence.

**[View the merchant example][msbf-p03] · [Explore MSBF][msbf] · [Power BI file (.pbix)][msbf-pbix] / [Reading guide][msbf-bi-guide]**

*Power BI Desktop: inspect a separate viewing copy without refreshing or saving over the accepted PBIX; follow the [Current Use Guide][msbf-current-use].*

<details>
<summary><strong>Also inspect the executive cohort command center</strong></summary>

P01 connects funding sources, decision categories, industry economics and account-attention signals. This original view is **Baseline only**, not the combined two-scenario population.

[![MSBF P01 Baseline: executive cohort command center with funding sources, decision outcomes, endpoint status and active alerts.][msbf-p01-image]][msbf-p01]

*Risk/loss context: **Current Portfolio — synthetic estimated-PD proxy, LGD, EAD/exposure, and comparative Expected Loss**. This is synthetic-forward account evidence, not a live book or actual financial performance. [Full-resolution command center][msbf-p01] · [Cohort report][msbf-cohort].*

</details>

<details>
<summary><strong>Architecture, proof posters and technical/use guidance</strong></summary>

[Executive brief][msbf-brief] · [Architecture][msbf-architecture] · [Module documentation][msbf-modules] · [Published v2.1.0][msbf-release]

**Learn the mechanism:** [How the Governed Decision Engine Works][msbf-poster-decision] explains evidence, structure search and final authority. [What Happens After the Decision][msbf-poster-after] follows monitoring, permissions, servicing and reconciliation. Both open at full resolution; the [masterclass][msbf-learn] adds worked cases.

**Using the report:** the [Current Use Guide][msbf-current-use] governs viewing and reproducibility. The accepted PBIX retains its historical `v2.1.0-rc2.pbix` filename. A generalized new-campaign runner is not provided.

</details>

---

<a name="cds"></a>
### Enterprise Credit Decisioning Strategy Simulator

**How do policy choices—and changes to the analytical foundation—alter a credit decision?**  
PostgreSQL · SAS reconciliation · Power BI

I built a configurable consumer-credit strategy environment with adjustable population size, product/score mix, selected product bounds, policy thresholds and counteroffer settings. I executed **39 runs of 50,000 synthetic applications each: 1.95 million decision evaluations**, not 1.95 million unique borrowers. Source-consistent comparisons within appropriate scenario groups expose access, affordability, exposure and review/decline tradeoffs.

The synthetic foundation also evolved through four Module 1 workstreams: **mortgage realism, risk-proxy dispersion, scenario design and revolving-payment sensitivity**. For example, revolving-payment estimates were revised so that APR changes affect payment burden—making the synthetic foundation more useful for strategy testing.

<a name="cds-power-bi"></a>
#### Power BI: what changed, for whom, and why?

This two-page report is **Module 1 v1.0 → v2.0 release/version validation**, not a dashboard of the separate Module 2 strategy campaign.

The **Executive Summary** establishes the full matched population, affected applications and field-level differences. The **Application Release Impact Explorer** lets a reviewer select an application, inspect before/after values and read an automated DAX narrative connecting the changes to documented Module 1 workstream themes.

[![CDS Application Release Impact Explorer: matched application lookup, version-one/version-two values, changes and an automated workstream-linked Analyst Interpretation.][cds-explorer-image]][cds-explorer]

*Original application-level release evidence. `ESTIMATED_PD` and `EXPECTED_LOSS_AMOUNT` belong to the **Current Portfolio — synthetic estimated-PD proxy, LGD, EAD/exposure, and comparative Expected Loss** framework. Rounded display values do not replace precise reconciliation values; workstream associations are not exclusive causal attribution. [Open full resolution][cds-explorer].*

The report reconciles **50,000 matched applications**, distinguishing **21,326 affected applications** from **58,382 application-variable differences**. I used ERR/SAS reconciliation in this version-analysis workflow, connecting the data comparison to both executive and application-level understanding.

**[Power BI file (.pbix)][cds-pbix] · [Executive validation report preview][cds-executive] · [Application change explorer][cds-explorer]**

<details>
<summary><strong>View the executive release-validation summary</strong></summary>

[![CDS Module 1 executive release-validation summary: 50,000 matched applications, 21,326 affected, 58,382 variable-change records and seven changed functional variables.][cds-executive-image]][cds-executive]

*These are synthetic version-comparison counts, not a campaign approval rate. Risk/loss fields use the **Current Portfolio — synthetic estimated-PD proxy, LGD, EAD/exposure, and comparative Expected Loss** formulation. [Full-resolution summary][cds-executive].*

</details>

[Explore CDS][cds] · [Campaign run evidence][cds-campaign] · [Module 1 workstreams][cds-workstreams] · [Validation summary][cds-validation] · [System architecture][cds-architecture]

---

<a name="ssf"></a>
### Survival Strategy Framework

**When does customer-attrition risk emerge, and how do configured scenarios change the same cohort's predicted survival?**  
Python · pandas · scikit-learn · lifelines

I directed development and executed a configurable time-to-event workflow for **synthetic customer-retention analysis**. Descriptive K-Means personas remain separate from regularized Cox proportional-hazards modeling. Input contracts, cross-validation, out-of-fold calibration, proportional-hazards review and risk stratification connect the fitted model to scenario analysis and stakeholder reports.

[![SSF: predicted survival curves for identical target IDs under baseline, no-change control, improvement assumptions and service-friction stress.][ssf-scenarios-image]][ssf-scenarios]

*Same target IDs; different configured assumptions. These curves show modeled sensitivity—not measured retention improvement or causal treatment effects. Retained validation posture: **PASS_WITH_REVIEW**, with documented proportional-hazards sensitivity and calibration limitations. Late-horizon support is limited: the [retained calibration evidence][ssf-calibration] has no records remaining at risk at the 24-month endpoint. [Open full resolution][ssf-scenarios].*

The demonstration uses **7,500 synthetic records** and compares **six scenarios on the same 1,875-record target cohort**. Changing a base feature also rebuilds its interactions and squared terms before rescoring. Neutral and adverse controls keep the comparison from becoming a showcase of favorable outcomes alone.

[Explore SSF][ssf] · [Python implementation][ssf-source] · [Executive deck][ssf-executive] · [Technical evidence][ssf-technical] · [Validation and review posture][ssf-validation]

---

<a name="domain-tools"></a>
## Furnishing and remediation strategy

### Metro 2 Credit-Reporting & Remediation Sandbox

**How should a proposed reporting correction interact with the underlying account-performance history?**

With adjustable population size and account-profile mix, this PostgreSQL testbed lets users explore credit-reporting remediation on synthetic histories before live implementation. It links account-month history and Payment History Profiles to Account Status, Payment Rating, DOFD, Date of Account Information and Date Closed, then exposes simulated before/after changes and eligible unresolved cases for manual follow-up.

The domain distinction matters: **reporting cleanup is not evidence of behavioral cure**. Recovery, cure, deletion and review remain different questions. This is a methodology sandbox—not a production furnishing or ongoing monitoring service.

[Explore the sandbox][metro2] · [Reporting-population generator][metro2-generator] · [Impact, cure and treatment logic][metro2-treatment]

## Data tools and financial-remediation methods

Focused prototypes address analytical prerequisites and specialized calculation problems. They complement the featured products without implying one integrated eight-project platform.

**[Forensic Data Integrity][fdi] · Python**  
Which selected column-level data-fitness issues deserve investigation? Inspect hidden-null screening, scoring assumptions and hypothetical cleanup—not a claim that data have been repaired. [Diagnostic source][fdi-source].

**[Enterprise Reconciliation Reporting][err] · SAS**  
What changed between datasets? Compare key coverage, schema/type/format and within-key values, with configurable tolerance and normalization logic. [Analyst guide][err-guide] · [Source][err-source].

**[Insurance Coverage Reconciliation][icr] · SAS**  
How should customer proof and configurable short-gap treatment affect coverage adjustment? Make the date-window methodology inspectable; an adjustment factor is not payment authority. [Coverage logic][icr-source].

**[Financial TVM Optimization][tvm] · SAS**  
How does time affect financial redress? Explore Treasury-linked daily accrual and periodic capitalization from supplied impact amounts and dates—not realized payments or a performance benchmark. [Calculation source][tvm-source].

**Reuse, not eight isolated stories.** I used ERR in CDS's release-analysis workflow and adapted CDS counteroffer concepts into MSBF. That is reuse of a tool and transfer of a method—not a claim of identical source versions or one common production pipeline.

---

<a name="professional-foundation"></a>
## Professional foundation

My employment record supplies the institutional context; the independent projects above supply inspectable work samples.

**Wells Fargo · Consumer Auto:** advanced to Senior Lead Analytics Consultant at the Executive Director level. Led analytics for Collateral Protection Insurance (CPI) customer remediation and other Consumer Auto remediation workstreams, representing more than $1B in exposure and customer impact. Designed and owned proof-of-insurance intake/QA and Direct and Indirect Auto recalculation tools, leading seven years of recurring analytical production and regulatory-response support. Advised Decision Forums through recommendations and effective challenge, and delivered credit-reporting corrections, furnishing controls and validated SAS feeds supporting management and review dashboards.

**Office of the Comptroller of the Currency:** supported 16 Credit Risk Analysis Division economists in credit-risk research and bank examination/stress-testing work, including DFAST. Engineered longitudinal bureau data and pricing inputs for economist-led Auto research; developed and tested CECL/lifetime-PD approaches; independently recalculated and validated evidence. Delivered Tableau views and explanations to support investigation and review. Research contributions were acknowledged in the *Journal of Credit Risk* and an OCC working paper. Research support is distinct from final model, publication or supervisory ownership.

**U.S. Census Bureau:** built dashboards for the Annual Capital Expenditures Survey (ACES) and analytical workbooks for the Annual Retail Trade Survey (ARTS), helping analysts investigate material discrepancies and company-level drivers. Led day-to-day ACES production for a six-analyst nightly workflow; ARTS workbooks supported on-demand analysis. These products connected analyst investigation with management visibility into industry performance and production progress.

The recurring thread is practical: **make the data usable, challenge the method, explain the result and preserve the next person's ability to act on it.**

## How I work

**Build:** SAS · SQL/Teradata · Python; PostgreSQL and Power BI/Power Query/DAX in the public portfolio.  
**Challenge:** source and output reconciliation · benchmark/challenger comparisons · sensitivity analysis · model diagnostics.  
**Deliver:** requirements and code · usable analytical views · executive interpretation · documented operating handoffs.

I use AI to accelerate implementation, testing, documentation and iteration while retaining responsibility for requirements, analytical judgment, validation and final acceptance. I publish business requirements, validation evidence and AI conversation records alongside the code so reviewers can examine and challenge the development process—not just the finished product. **TRUTH made visible.** Project-specific sources distinguish implemented capability, demonstrated runs, review qualifications and future work. Synthetic examples do not establish employer deployment, commercial adoption or realized customer outcomes.

**Let's connect about senior analytics, credit strategy, decision systems and analytical-product work.** [LinkedIn][linkedin] · [All repositories][github]

<!-- Direct proof artifacts are pinned to the reviewed source editions; project links open the repository front doors. -->

[msbf]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator
[cds]: https://github.com/andrew-goad/credit_decisioning_strategy
[ssf]: https://github.com/andrew-goad/survival-strategy-framework
[err]: https://github.com/andrew-goad/enterprise-reconciliation-reporting
[tvm]: https://github.com/andrew-goad/financial-tvm-optimization
[icr]: https://github.com/andrew-goad/insurance-coverage-reconciliation
[metro2]: https://github.com/andrew-goad/metro2-remediation-sandbox
[fdi]: https://github.com/andrew-goad/forensic-data-integrity
[linkedin]: https://www.linkedin.com/in/andrewrgoad
[github]: https://github.com/andrew-goad?tab=repositories
[msbf-p03]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/power_bi/m2_v2_1/assets/power_bi/core/p03_application_journey_738_baseline.png
[msbf-p03-image]: https://raw.githubusercontent.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/power_bi/m2_v2_1/assets/power_bi/core/p03_application_journey_738_baseline.png
[msbf-p01]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/power_bi/m2_v2_1/assets/power_bi/core/p01_command_center_baseline.png
[msbf-p01-image]: https://raw.githubusercontent.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/power_bi/m2_v2_1/assets/power_bi/core/p01_command_center_baseline.png
[cds-explorer]: https://github.com/andrew-goad/credit_decisioning_strategy/blob/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_1_Synthetic_Application_%26_Risk_Modeling_Engine/v2.0/tests/module1_v1_v2_release_impact_explorer.png
[cds-explorer-image]: https://raw.githubusercontent.com/andrew-goad/credit_decisioning_strategy/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_1_Synthetic_Application_%26_Risk_Modeling_Engine/v2.0/tests/module1_v1_v2_release_impact_explorer.png
[cds-executive]: https://github.com/andrew-goad/credit_decisioning_strategy/blob/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_1_Synthetic_Application_%26_Risk_Modeling_Engine/v2.0/tests/module1_v1_v2_release_validation_executive_summary.png
[cds-executive-image]: https://raw.githubusercontent.com/andrew-goad/credit_decisioning_strategy/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_1_Synthetic_Application_%26_Risk_Modeling_Engine/v2.0/tests/module1_v1_v2_release_validation_executive_summary.png
[ssf-scenarios]: https://github.com/andrew-goad/survival-strategy-framework/blob/620991e428942b0cc09faaafc111670ad35deca2/outputs/baseline_vs_scenario_survival.png
[ssf-scenarios-image]: https://raw.githubusercontent.com/andrew-goad/survival-strategy-framework/620991e428942b0cc09faaafc111670ad35deca2/outputs/baseline_vs_scenario_survival.png
[msbf-pbix]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/power_bi/m2_v2_1/release/MSBF_Merchant_Credit_Intelligence_M2_v2.1.0-rc2.pbix
[msbf-bi-guide]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/guide/ANALYTICS.md
[msbf-cases]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/guide/EXPLAINABILITY.md
[msbf-brief]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/portfolio_visuals/MSBF_VISUAL_PUBLIC_R1/assets/pitch/From_First_Advance_to_Intelligent_Portfolio.pdf
[msbf-architecture]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/portfolio_visuals/MSBF_VISUAL_PUBLIC_R1/assets/architecture/png/Enterprise_Merchant_Sales_Based_Financing_Platform_v2_1.png
[msbf-modules]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/README.md
[msbf-current-use]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/guide/CURRENT_USE.md
[msbf-changes]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/release_change_control/module_2_g3_v2_1/reports/02_DETAILED_CHANGE_LOG_AND_DATA_RECONCILIATION_REPORT.md
[msbf-cohort]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/portfolio_visuals/MSBF_VISUAL_PUBLIC_R1/assets/cohort/MSBF_Merchant_Credit_Intelligence_Initial_750_Cohort_Overview_R3_PATCH1_20260908_REVIEW.pdf
[msbf-learn]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/guide/LEARNING.md
[msbf-poster-decision]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/portfolio_visuals/MSBF_VISUAL_PUBLIC_R1/assets/posters/MSBF_MCI_How_the_Governed_Decision_Engine_Works_v2_1_COPYFIX_R1.png
[msbf-poster-after]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/blob/fd9f67b6d1d7fc848d315bcb696487b82c9a8046/docs/portfolio_visuals/MSBF_VISUAL_PUBLIC_R1/assets/posters/MSBF_MCI_What_Happens_After_the_Decision_v2_1_COPYFIX_R1.png
[cds-pbix]: https://github.com/andrew-goad/credit_decisioning_strategy/blob/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_1_Synthetic_Application_%26_Risk_Modeling_Engine/v2.0/tests/Module1_V1_V2_Release_Validation.pbix
[cds-workstreams]: https://github.com/andrew-goad/credit_decisioning_strategy/blob/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_1_Synthetic_Application_%26_Risk_Modeling_Engine/v2.0/docs/Enterprise_Credit_Decisioning_Simulator_Module1_Synthetic_Application_Risk_Engine_BRD_v2.0.pdf
[cds-validation]: https://github.com/andrew-goad/credit_decisioning_strategy/blob/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_1_Synthetic_Application_%26_Risk_Modeling_Engine/v2.0/tests/Enterprise_Credit_Decisioning_Simulator_Module1_Validation_Summary_v2.0.pdf
[cds-campaign]: https://github.com/andrew-goad/credit_decisioning_strategy/blob/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_2_Credit_Policy_Strategy_%26_Decision_Outcome_Simulation_Engine/v1.0/outputs/module2_credit_policy_strategy_decision_outcome_simulation_engine_v1.0_OUTPUT_strategy_run_campaign_registry.csv
[cds-architecture]: https://github.com/andrew-goad/credit_decisioning_strategy/blob/1361046fa7f4e61dfa4cfc6105577e50f53af083/Module_2_Credit_Policy_Strategy_%26_Decision_Outcome_Simulation_Engine/v1.0/docs/Enterprise%20Credit%20Decisioning%20Strategy%20Module%202%20Architecture.png
[ssf-technical]: https://github.com/andrew-goad/survival-strategy-framework/blob/620991e428942b0cc09faaafc111670ad35deca2/outputs/Technical_Model_Evidence.pdf
[ssf-validation]: https://github.com/andrew-goad/survival-strategy-framework/blob/620991e428942b0cc09faaafc111670ad35deca2/tests/Survival_Strategy_Framework_Validation_Summary.pdf
[ssf-calibration]: https://github.com/andrew-goad/survival-strategy-framework/blob/620991e428942b0cc09faaafc111670ad35deca2/outputs/calibration_metrics.csv
[ssf-source]: https://github.com/andrew-goad/survival-strategy-framework/blob/620991e428942b0cc09faaafc111670ad35deca2/src/survival_strategy_framework.py
[ssf-executive]: https://github.com/andrew-goad/survival-strategy-framework/blob/620991e428942b0cc09faaafc111670ad35deca2/outputs/Survival_Strategy_Deck.pptx
[metro2-generator]: https://github.com/andrew-goad/metro2-remediation-sandbox/blob/1201adcc0b3a74a0f81e8f456a9e3d901f0aaca7/src/module_01_metro2_synthetic_portfolio_generator.sql
[metro2-treatment]: https://github.com/andrew-goad/metro2-remediation-sandbox/blob/1201adcc0b3a74a0f81e8f456a9e3d901f0aaca7/src/module_02_metro2_remediation_engine.sql
[fdi-source]: https://github.com/andrew-goad/forensic-data-integrity/blob/6654869c244e74eaaad9794e3130c6151b9882a2/src/forensic_diagnostic_engine.py
[err-guide]: https://github.com/andrew-goad/enterprise-reconciliation-reporting/blob/a6f8c2dfeefe24b0489094b5e619fc48fdf7b272/docs/reconciliation_learning_aid.sas
[err-source]: https://github.com/andrew-goad/enterprise-reconciliation-reporting/blob/a6f8c2dfeefe24b0489094b5e619fc48fdf7b272/src/enterprise_reconciliation_diagnostic.sas
[icr-source]: https://github.com/andrew-goad/insurance-coverage-reconciliation/blob/9fd3b4dd83aeb9466600656d7b7b1ae5257fba79/src/policy_coverage_reconciliation.sas
[tvm-source]: https://github.com/andrew-goad/financial-tvm-optimization/blob/81cc82ef88e022830c5ec862c5dcb582380b3ce2/src/high_scale_tvm_engine.sas
[msbf-release]: https://github.com/andrew-goad/merchant-sales-based-financing-strategy-simulator/releases/tag/module-2-g3-v2.1.0

[hitl-report]: https://github.com/andrew-goad/andrew-goad/blob/03cbea711f1b3d06ce1b77599286eb700dedb313/Human_in_the_Loop_Analytical_Leadership/Human_in_the_Loop_Analytical_Leadership.pdf
[hitl-carousel]: https://github.com/andrew-goad/andrew-goad/blob/03cbea711f1b3d06ce1b77599286eb700dedb313/Human_in_the_Loop_Analytical_Leadership/Human_in_the_Loop_Analytical_Leadership_LinkedIn_Carousel.pdf
[hitl-mandate]: https://github.com/andrew-goad/andrew-goad/blob/03cbea711f1b3d06ce1b77599286eb700dedb313/Human_in_the_Loop_Analytical_Leadership/HITL_Page_02_Operating_Mandate.png
[hitl-mandate-image]: https://raw.githubusercontent.com/andrew-goad/andrew-goad/03cbea711f1b3d06ce1b77599286eb700dedb313/Human_in_the_Loop_Analytical_Leadership/HITL_Page_02_Operating_Mandate.png
[hitl-method]: https://github.com/andrew-goad/andrew-goad/blob/03cbea711f1b3d06ce1b77599286eb700dedb313/Human_in_the_Loop_Analytical_Leadership/HITL_Page_33_Reusable_Method.png
[hitl-method-image]: https://raw.githubusercontent.com/andrew-goad/andrew-goad/03cbea711f1b3d06ce1b77599286eb700dedb313/Human_in_the_Loop_Analytical_Leadership/HITL_Page_33_Reusable_Method.png
[hitl-reconcile]: https://github.com/andrew-goad/andrew-goad/blob/03cbea711f1b3d06ce1b77599286eb700dedb313/Human_in_the_Loop_Analytical_Leadership/HITL_Page_28_Verify_and_Reconcile.png
