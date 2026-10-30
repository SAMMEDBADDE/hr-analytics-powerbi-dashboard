# 📊 HR Analytics & Workforce Insights Dashboard

An end-to-end HR Analytics project built using **Power BI**, analyzing workforce demographics, diversity metrics, hiring trends, and employee distribution across a dataset of **22,000+ employee records**.

---

## 📌 Project Overview

HR Analytics enables organizations to develop data-driven strategies for talent acquisition, retention, diversity and inclusion, and workforce planning. This dashboard provides actionable insights into headcount, location splits (HQ vs. Remote), employee age profiles, racial diversity, gender distribution, and department-level allocations.

### 🎯 Key Objectives & Requirements
* **KPI Metrics:** Track total headcount, HQ vs. Remote percentage split, and average employee age.
* **Hiring Trends:** Line chart visualizing the hiring rate over time by year.
* **Gender Diversity:** Donut chart showcasing gender distribution across the organization.
* **Demographics & Allocations:** Bar charts depicting active employees by **State**, **Department**, and **Race/Ethnicity**.
* **Actionable Recommendations:** Provide strategic recommendations for HR and business leaders.

---

## 🛠️ Data Architecture & Tech Stack

* **Business Intelligence / Data Visualization:** Power BI (Desktop)
* **Database / Connectivity:** MySQL Database (`project_hr_analytics`)
* **Languages & Querying:** DAX (Data Analysis Expressions), Power Query (M)
* **Design & Theme:** Custom Corporate Layout with Fluent UI design standards

---

## 🔑 Key Metrics & Insights

| Metric | Value |
| :--- | :--- |
| **Total Active Employees** | ~19,000 (from 22.2k total records) |
| **HQ vs. Remote Split** | **75.02%** HQ vs. **24.98%** Remote |
| **Average Workforce Age** | **42.03 Years** |
| **Top Department** | Engineering (~5.8k employees), followed by Accounting (~2.9k) |
| **Top Location** | Ohio (~15.6k active employees) |

### 💡 Notable Findings:
1. **Location Concentration:** The vast majority of the workforce is concentrated in **Ohio**, presenting both operational stability and potential geographical risk.
2. **Department Breakdown:** Technical and financial operations dominate headcount, with **Engineering** and **Accounting** representing the largest workforce segments.
3. **Gender Ratio:** Gender representation is relatively balanced (~51% Male, ~46% Female, ~3% Non-Conforming).
4. **Flexible Work Culture:** Nearly **25%** of the workforce operates remotely, demonstrating a mature remote-work infrastructure.

---

## 📁 Repository Structure

```text
├── Submissions/
│   ├── HR_Analytics_Report.pbix           # Power BI Dashboard File
│   ├── HR_Analytics_Workforce_Report.docx  # Detailed HR Analysis Report
│   └── HR-Analytics-Workforce-Report.pptx  # Executive Presentation Deck
├── assets/                                # Screenshots for README & Documentation
│   ├── dashboard_overview.png
│   └── demographics_breakdown.png
├── HR.csv                                 # Local Data Export / Backup
└── README.md                              # Project Documentation
