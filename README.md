# DePaul University Student Application Data — End-to-End Analytics Project

## Project Overview

This repository documents a complete end-to-end data analytics project completed during a 4-week Data Analytics Internship with Excelerate.

The dataset contains 7,543 student application records from DePaul University, spanning May 2023 to June 2025. It captures student demographics, academic program preferences, application processing details, and outreach campaign activity.
---

## Tools Used

- Google Sheets & MS Excel - Exploratory Data Analysis and visualisations
- Google Sheets — Data cleaning and Documentation
- Power BI Desktop — Interactive dashboard
- Claude AI (Anthropic) — Guided analysis and report structuring
---

## Repository Structure

| Folder | Contents |
|--------|----------|
| Week1-EDA | Data Exploration Report, Data Dictionary, EDA Visualisations |
| Week2-DataCleaning | Data Cleaning Report, Cleaning Log, Before/After Charts, Cleaned Dataset |
| Week3-Dashboard | Dashboard Report, Power BI Dashboard Screenshots |
| Week4-FinalPresentation | Final 12-Slide Presentation |
---

## Week 1 — Data Exploration & EDA

**Dataset:** 7,543 rows, 80 columns, 0 duplicate rows

**Key Findings:**
- India accounts for 61.2% of all applicants (4,617 of 7,543)
- Business Analytics MS (1,080) and Computer Science MS (1,055) are the top two programs
- Jarvis College of Computing received 50.8% of all first-choice college selections
- 38 out of 80 columns were completely empty
- 42.3% of applicants (3,194 students) were never contacted through any outreach campaign
- Admissions grew 176.3% from 2023 (1,377) to 2024 (3,805)
---

## Week 2 — Data Cleaning Report

**17 documented cleaning steps across 6 sections**

**Key Improvements:**
- Columns reduced from 80 to 33 — 47 removed
- 38 completely empty columns deleted
- 3 Unix timestamp columns converted to readable dates
- Country names standardised using PROPER() function
- Application_Source formatting unified
- Intake column split into Program and Intake_Term
- 3,194 blank Outcome_1 cells labelled as "Not Contacted"
- Overall data quality score improved from 2.4/5 to 4.6/5
---

## Week 3 — Interactive Power BI Dashboard

**Two-page interactive dashboard built in Power BI Desktop**

**Page 1 — Applicant Overview:**
6 KPI cards, 5 cross-page synced slicers, and 6 charts covering top countries, top programs, college preferences, intake terms, application sources, and admissions growth by year outreach coverage.

**Page 2 — Admissions & Outreach Performance:**
4 charts covering outreach coverage, outreach outcome breakdown, top countries by recruitment channel, and top programs by intake term.
---

## Week 4 — Final Presentation

12-slide PowerPoint presentation covering the complete project journey — dataset overview, EDA findings, cleaning process, dashboard insights and actionable recommendations
---

## Key Insights

1. **Geographic Concentration Risk** — India's 61.2% share creates a single-market dependency that poses a strategic recruitment risk

2. **Technology Programs Drive Demand** — 7 of the top 10 programs are technology or data-focused, with Jarvis College of Computing dominating first-choice selections

3. **176% Admissions Growth in 2024** — A dramatic year-over-year increase that warrants deeper investigation into the driving factors

4. **42.3% Outreach Gap** — Nearly half the applicant pool was never contacted, and every contacted student received exactly one attempt with no recorded follow-up
---

## Actionable Recommendations

- Diversify recruitment beyond India into Ghana, Nigeria, and Pakistan
- Expand Study Group partnerships in underrepresented markets
- Implement multi-touch outreach protocol — minimum two contact attempts
- Automate transcript reminder system to resolve the biggest bottleneck
- Scale counselor resources ahead of Fall intake peaks
---

## Author

**Enimabasi Ukpong**
Data Analytics Intern — Excelerate
www.linkedin.com/in/enimabasi-ukpong
https://x.com/enimabasi
