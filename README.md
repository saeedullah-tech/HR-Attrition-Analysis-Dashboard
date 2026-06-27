# HR Attrition Analysis Dashboard (Power BI)

A two-page Power BI dashboard analyzing employee attrition across departments, roles, demographics, and compensation bands — built to identify the key drivers of turnover and flag the employee segments at highest risk.

## Overview

This dashboard breaks down attrition data for an organization to answer one core business question: **why are employees leaving, and who is most likely to leave next?** It moves from a detailed exploration view (Page 1) to an executive summary view (Page 2) that surfaces the headline findings for decision-makers.

## Pages

### Page 1 — Attrition Breakdown
A detailed, filterable view of attrition across multiple dimensions:
- **Attrition by Education Field** — Life Sciences (38%) and Medical (27%) account for the majority of attrition
- **Attrition by Age Group** — the 26–35 age band has the highest attrition count (116 employees)
- **Attrition by Job Role & Performance Rating** — cross-tab of role vs. rating (Excellent/Fair/Good/Poor), with Laboratory Technician (62) and Sales Executive (57) as the top roles by attrition
- **Attrition by Salary Band** — employees earning up to 5K account for 163 of total attrition cases, far outweighing every other band
- **Attrition by Tenure (Time in Company)** — a histogram showing where in an employee's tenure attrition is concentrated
- **Attrition by Gender** — 64.13% male vs. 35.87% female
- KPI cards for total employees, attrition count, average monthly income, average hourly rate, average age, environment satisfaction, and average tenure
- Interactive slicers for **Department**, **Gender**, and **Job Level**

### Page 2 — Executive Summary
A condensed, decision-ready view highlighting the top findings:
- **Top driver:** salary — the under-5K band accounts for 69% of attrition
- **Critical window:** years 0–2 of tenure is the highest-risk period
- **Highest-risk roles:** Laboratory Technician and Sales Executive
- **Gender skew:** 64.13% of attrition is male
- **Job level concentration:** 60.34% of attrition occurs at entry level
- **Age concentration:** the 26–35 band is the highest-attrition age group
- **Attrition Rate by Job Role and Gender** — a normalized rate chart (not raw counts) broken out by education field and gender, showing where attrition rate spikes well above 100% relative to headcount in that segment

## Key Insights

| Finding | Detail |
|---|---|
| Compensation is the #1 driver | Employees earning under 5K SAR/month make up the large majority of attrition |
| Early tenure is the danger zone | Most attrition happens within the first two years on the job |
| Entry-level roles are most exposed | 60%+ of all attrition sits at the entry level |
| Lab Techs & Sales Execs leave most | These two roles consistently top the attrition count across breakdowns |
| Attrition rate ≠ attrition count | The rate chart on Page 2 shows some smaller segments (by gender/education field) have disproportionately high attrition *rates* even though their raw counts are low |

## Tools & Techniques
- **Power BI Desktop** — report build, DAX measures, interactive slicers
- **Data Modeling** — KPI cards, cross-tab matrix, normalized rate calculations
- **DAX** — aggregations (Sum/Average of Attrition Count, Monthly Income, Hourly Rate, Tenure, Environment Satisfaction) and rate-based measures (Attrition Rate by Job Role and Gender)
- **Data Visualization** — donut charts, bar charts, histograms, KPI cards, cross-tab table, slicers

## Business Value
This dashboard gives HR and management a clear, evidence-based view of where attrition risk is concentrated — by pay band, tenure, role, and demographic — so retention efforts (pay review, onboarding support, role-specific interventions) can be targeted at the segments driving the most turnover, rather than applied broadly.

## File
- `HR_Attrition.pbix` — Power BI report file (2 pages)

---
*Built as part of a personal data analytics portfolio project.*
