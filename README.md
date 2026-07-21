# Public Health M&E Portfolio: Maternal & Child Nutrition Initiative

## 📌 Project Overview
This repository documents a comprehensive, end-to-end Monitoring, Evaluation, Accountability, and Learning (MEAL) framework designed for a 12-month maternal and child health intervention across 10 rural villages. The project addresses acute child malnutrition and works to improve antenatal care (ANC) and facility-based delivery compliance among pregnant women.

### 🗺️ Project Execution Roadmap
* [x] **Step 1:** Needs Assessment, Root Cause Diagnosis & Validation Matrix
* [x] **Step 2:** Stakeholder Analysis & Information Needs Mapping
* [x] **Step 3:** Results Framework & Theory of Change (Logic Model)
* [x] **Step 4:** Strategic Indicator Framework & Math Formulas
* [ ] **Step 5:** KoboToolbox Mobile Survey Tool & Form Schema *(Next Step)*
* [ ] **Step 6:** Dataset Simulation, SQL/Excel Cleaning & Power BI Dashboard

---
## DAY 1
## 🔍 Step 1: Needs Assessment & Diagnostic Problem Analysis

### 1. Baseline Context
A baseline assessment across 10 target rural communities revealed critical public health challenges:
* **High Malnutrition Rates:** Severe Acute Malnutrition (SAM) among children under 5 stands at **18%**, exceeding local emergency thresholds.
* **Low Healthcare Utilization:** Only **35%** of pregnant women complete the recommended 4+ Antenatal Care (ANC) visits.
* **Infant Feeding Gaps:** Only **22%** of infants are exclusively breastfed (0–6 months), and only **15%** of children (6–23 months) reach Minimum Dietary Diversity (MDD).

---

### 2. Root Cause Analysis (Issue Tree Breakdown)
To avoid treating surface-level symptoms, a **Diagnostic Issue Tree** was applied using a **Demand vs. Supply** framework to isolate root drivers:

```text
                                                ┌─► Demand: Low nutritional literacy regarding local food groups
                                ┌─► Sub-issue: ─┤
                                │   Poor Diets  └─► Supply: Limited household access to diversified crops
                                │
Why is child malnutrition ──────┤
high across target villages?    │               ┌─► Demand: Delayed recognition of early physical wasting signs
                                └─► Sub-issue: ─┤
                                    Late        └─► Supply: Lack of functional MUAC screening tools & trained CHVs
                                    Detection
```
### 3. Driver Hypothesis Validation Matrix
Prior to project design, each potential root driver was validated using multi-source triangulation (quantitative data, qualitative interviews, and field audits):

| Driver Hypothesis | Validation Source / Method | Findings & Status |
| :--- | :--- | :--- |
| **Late Malnutrition Detection:** Delayed due to missing screening tools at village level. | **Facility & Volunteer Audit:** Inspected all 20 Community Health Volunteer (CHV) kits across villages. | **Validated:** 80% (16/20) of CHV kits lacked functional MUAC screening tapes. |
| **Low ANC Completion:** Women avoid clinic visits due to high consultation fees. | **Key Informant Interviews & Clinic Registers:** Interviewed 50 mothers & reviewed clinic price schedules. | **Revised:** ANC services were free, but indirect transit costs and 4+ hour clinic wait times were the true barriers. |
| **Low Infant Dietary Diversity:** Mothers lack awareness of nutritional combination of local crops. | **Household Dietary Recall Survey (Primary Data):** Assessed 24-hour food group recall among mothers. | **Validated:** 85% of toddlers relied strictly on mono-crop carbohydrates due to knowledge gaps. |

---
## Day 2
## Step 2: Stakeholder Analysis & Information Needs Mapping

To ensure M&E outputs directly serve operational, clinical, and strategic decision-making, reporting requirements were mapped to specific stakeholder roles prior to indicator design:

### 1. Stakeholder Information Needs Matrix

| Stakeholder Group | Key Decision They Need to Make | Specific Information Needed (Exact Metrics) | Primary Data Source & Output Format | Reporting Frequency |
| :--- | :--- | :--- | :--- | :--- |
| **Donor / Funder** | Grant renewal, multi-year budget allocation, and regional scaling to adjacent districts. | • **U5 Malnutrition Prevalence (%):** Overall % of children 6–59m classified as SAM/MAM via MUAC.<br>• **ANC4+ Completion Rate (%):** % of pregnant women completing $\ge 4$ clinical ANC visits.<br>• **Cost per Beneficiary Reached:** Expenditure per child successfully screened and treated. | High-Level Executive Summary & Interactive Power BI Strategic Dashboard | Quarterly / Annually |
| **Ministry of Health (MOH)** | Allocation of regional Ready-to-Use Therapeutic Food (RUTF) stocks, clinical supervisor deployment, and DHIS2 integration. | • **Facility vs. Home Delivery Ratio (%):** % of births in accredited facilities vs. TBA/home.<br>• **Severe Acute Cases Referrals (Count):** Monthly volume of SAM cases referred from villages to PHCs.<br>• **Minimum Dietary Diversity Rate (%):** % of toddlers 6–23m reaching $\ge 5/8$ WHO food groups. | Aggregated Facility Ledgers, Monthly Summary Extracts & Standard DHIS2 Formats | Monthly / Quarterly |
| **Project Field Management & CHVs** | Daily route planning, volunteer kit restocking, identifying underperforming villages, and resolving field bottlenecks. | • **Active CHV Screening Coverage (Count):** Monthly screenings performed per CHV (Target: $\ge 50$/month).<br>• **MUAC Stock/Kit Readiness:** Count of operational screening kits and MUAC tapes deployed per village.<br>• **Kitchen Session Attendance (Count):** Number of unique mothers attending bi-weekly cooking demos. | Real-Time KoboToolbox Submissions, Operational Mobile Alerts & Weekly Excel Logbooks | Real-Time / Weekly |
| **Community Leaders & Village Elders** | Maintaining community buy-in, encouraging male involvement, and approving mothers' attendance at nutrition kitchens. | • **Village Screening Totals:** Total children checked in their specific village and progress made.<br>• **Recovered Children Count:** Number of local children successfully rehabilitated from wasting.<br>• **Community Kitchen Schedule:** Dates, locations, and attendance targets for upcoming sessions. | Visual Community Dashboards (Infographics/A3 Printouts) & Monthly Town Hall Briefings | Monthly |
---
## Day 3
## Step 3: Results Framework / Logic Model
<img width="960" height="540" alt="logic model (1)" src="https://github.com/user-attachments/assets/15f41bc1-c0e0-48e2-bbe0-caa2e92ca189" />

The structural logic of this intervention maps out how local capacity building and community-led nutrition hubs systematically drive behavioral shifts and long-term health impacts.

### The Project Logic Chain:

* **IMPACT:**
  * Reduction in under-5 mortality & acute malnutrition rates.

* **OUTCOMES:**
  * Mothers adopt optimal infant feeding and cooking practices at home.
  * Increased utilization of ANC services & facility-based deliveries.

* **OUTPUTS:**
  * 50 CHVs successfully trained and equipped with MUAC screening kits.
  * Bi-weekly nutrition kitchens established across 10 villages.

* **ACTIVITIES:**
  * Run a 3-day training program for 50 local CHVs on MUAC tape.
  * Establish and operate bi-weekly Community Nutrition Kitchens.

### Critical Sustainability Assumption:
* **Husbands approve wives' participation.**


---
## Day 4:
## Strategic Indicator Framework

To measure the success of the logic model, five specific public health indicators have been designed. These metrics strip out arbitrary targets to focus purely on standardized data collection definitions that will feed our database pipeline.

### 1. Maternal Health Utilization Metrics
* **Indicator 1.1:** `Number of pregnant women who completed at least 4 Antenatal Care (ANC) visits during their pregnancy.`
  * *Type:* Count 
  * *Data Source:* Health Facility Registers / CHV Logbooks
* **Indicator 1.2:** `Percentage of live births delivered at a certified health facility.`
  * *Type:* Proportion
  * *Data Source:* Health Facility Delivery Logs
  * *Calculation Matrix:* $$\text{Facility Delivery Rate (\%)} = \left( \frac{\text{Live births at a health facility}}{\text{Total recorded live births}} \right) \times 100$$

### 2. Infant Nutrition & Behavioral Change Metrics
* **Indicator 2.1:** `Percentage of infants aged 0–5 months who are exclusively breastfed.`
  * *Type:* Proportion
  * *Data Source:* Household Surveys (24-hour maternal dietary recall)
* **Indicator 2.2:** `Percentage of children aged 6–23 months who receive a Minimum Dietary Diversity (MDD) using locally available food groups.`
  * *Type:* Proportion (Measures consumption across $\ge 5$ of 8 standard WHO food groups)
  * *Data Source:* Household Surveys (Toddler dietary intake sheets)

### 3. Population Health Impact Metric
* **Indicator 3.1:** `Prevalence of acute malnutrition (wasting) among children aged 6–59 months.`
  * *Type:* Prevalence / Impact Proportion
  * *Data Source:* Community Health Volunteer (CHV) Monthly Screening Ledgers
  * *Calculation Matrix:*
    $$\text{Wasting Prevalence (\%)} = \left( \frac{\text{Children surveyed with a Mid-Upper Arm Circumference (MUAC) } < 125\text{mm}}{\text{Total children screened via MUAC}} \right) \times 100$$

---
