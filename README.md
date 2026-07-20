# Public Health M&E Portfolio: Maternal & Child Nutrition Initiative

## 📌 Project Overview
This repository documents a comprehensive, end-to-end Monitoring and Evaluation (M&E) framework designed for a 12-month maternal and child health intervention across 10 rural villages. The project targets acute malnutrition in children under 5 and aims to improve antenatal care (ANC) and facility-based delivery compliance among pregnant women.

### Core M&E Competencies Demonstrated:
* **Day 1:** Logic Model & Results Framework Design 
* **Day 2:** Strategic Indicator Design *(In Progress)*

---

## 📂 Day 1: Results Framework / Logic Model
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

## 📂 Day 2: Strategic Indicator Framework

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
