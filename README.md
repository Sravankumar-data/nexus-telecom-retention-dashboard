# Nexus Telecom — Business Case Study & Retention Report

**Author:** Banothu Sravan Kumar  
**Cohort:** Jan–Dec 2025 (1,600 Customers • 17,574 Monthly Bills)  
**Currency:** INR (₹)

## Overview
An end-to-end customer billing, revenue, and churn analysis for **Nexus Telecom** across January–December 2025, covering four regions (**North, East, South, West**) and four subscription plans (**Basic, Plus, Premium, Family**).

## Key Highlights (2025)
- **Gross Charges:** ₹16,017,804.22
- **Total Discounts:** ₹475,088.19 (~2.97% discount rate)
- **Total Net Revenue:** ₹15,542,716.03 (₹1.55 Cr)
- **Starting Cohort:** 1,600 active customers (17,574 monthly bills generated)
- **Churned Customers:** 330 customers (**20.62%** annual cohort churn rate), leaving 1,309 billed in December and 1,270 entering 2026
- **Full-Year / Monthly ARPU:** ₹884.42/mo overall (₹9,714/yr); ₹890.66 in December

## Key Insights
1. **Revenue & Subscriber Trend:** Active customers and monthly revenue held steady early in 2025 before declining from March onward, with monthly revenue moving from a February peak of ₹1,410,596.80 to ₹1,165,869.64 in December (-17.35%).
2. **Plan Revenue vs. Churn:** **Plus** (₹4,897,242.30 | 31.51% share | 18.63% churn) and **Premium** (₹4,478,379.80 | 28.81% share | 19.02% churn) drive over 60% of net revenue, while **Basic** has the highest churn at **24.73%** (115 of 465).
3. **Contract Risk:** **Month-to-Month** plans account for **69.7%** of all cancellations (230 of 330 exits; **28.82%** churn rate), with **South Month-to-Month** hitting a **33.3%** churn hotspot.
4. **Early-Tenure Drop-Off:** Customers with 0–6 months tenure at the start of the year churned at **36.19%** (76 of 210), roughly double the rate of longer-tenured cohorts.
5. **Ticket & Churn Metrics Context:** Support ticket volume is ~0.50 tickets per active month across stayed and churned users; `[Revenue in Churn Month]` (₹283,679.24) reflects final-bill collections rather than lost recurring future revenue.

## DAX Measures Included
- `Total Customers`, `Active Subscribers`, `December Subscribers`
- `Gross Charges`, `Total Discounts`, `Discount Rate %`, `Total Revenue`, `Revenue in Churn Month`
- `ARPU`, `December ARPU`
- `Churned Customers`, `Cohort Churn Rate %`, `Churn Events`
- `Support Tickets`, `Late Payments`, `Data Usage GB`

## Files in This Repository
- [Telecom_Dashboard.pbix](./Telecom_Dashboard.pbix) — Interactive Power BI report
- [Telecom_Case_Study.pdf](./Telecom_Project_Case_Study.pdf) — Full written case study, DAX reference, tables, and retention recommendations
- [Customers.csv](./Customers.csv) — Customer cohort dataset (1,600 customers across regions, plans, contracts, and tenure)
- [Monthly_Billing.csv](./Monthly_Billing.csv) — Monthly billing records dataset (17,574 bills across Jan–Dec 2025)
