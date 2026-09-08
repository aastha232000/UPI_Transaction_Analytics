# UPI Transaction Performance & Fraud Analytics 🚀

## Objective
The primary goal of this end-to-end capstone project is to analyze UPI transaction data to identify patterns in payment failures and fraud. From data extraction to final visualization, this project provides actionable business insights to improve digital payment security and user experience.

## Tools & Technologies Used

* **Microsoft Excel:** Initial data validation, cleaning, and preliminary data profiling (`Data_Quality_Log.xlsx`).
* **SQL:** Database design, data extraction, and relational schema management to structure raw transaction logs (`DDL_Script.sql`).
* **Python (Pandas, SciPy, Statsmodels):** Exploratory Data Analysis (EDA) and Hypothesis Testing (T-test, ANOVA, Chi-Square, Correlation) to validate assumptions (`CapStone_.ipynb`).
* **Power BI:** Building an interactive, dynamic Business Intelligence dashboard (`Capstone_Dashboard.pbix`).
* **MySQL Workbench:** Entity-Relationship modeling (`ER_Diagram.mwb`).

## Key Data-Driven Insights

1. **High Fraud in the West Region:** The West region exhibits the highest fraud rate at **2.09%**, followed closely by South (2.03%).
2. **Feature Phone Vulnerability:** Users on basic feature phones face the highest risk, with a fraud rate of **2.15%** — higher than Android, iOS, and Tablet users.
3. **Targeted Shopping Scams:** The 'Electronics' (**2.24%**) and 'Apparel' (**2.22%**) merchant categories show the highest fraud rates, indicating targeted high-value scams.

## Strategic Recommendations

* **Strengthen Security for Feature Phones:** Implement extra layers of security like automated voice confirmation (IVR) for non-smartphone users.
* **Stricter Merchant Verification:** Enforce stricter KYC and onboarding checks for high-risk categories like Electronics and Apparel, especially in the West region.

## Dashboard Overview

**Executive Dashboard**
KPI cards for Total Transactions, Avg. Transaction Amount, Failure Rate, Fraud Rate, and Top Device, alongside a monthly transaction trend line, transaction-type donut chart, and region/device/merchant comparisons. Filters: Region, Device Type, Merchant Type, Status, Time Period.

**Fraud & Operations Analyst Dashboard**
KPI cards for Total Alerts, Open Alerts, Fraud Rate, Avg. Resolution Time, and Alerts Resolved %, with a fraud alert trend line, root-cause breakdown, resolution-time analysis, and a rooted vs. non-rooted device fraud comparison table.

**Alert Details**
A drill-through page for investigating individual fraud alerts in depth.

---
**Author:** Aastha Maurya · Data Analytics with GenAI — Capstone Project
