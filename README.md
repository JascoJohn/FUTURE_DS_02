FUTURE_DS_02 - Customer Retention & Churn Analysis


📌 Project Overview


An end-to-end data analysis project focusing on **Telco customer subscription data**. This project identifies key churn patterns, calculates retention trends, and quantifies revenue at risk using **Python** for robust data processing and **Power BI** for dynamic dashboard visualization.


🛠️ Tools Used
1.  🐍 **Python (pandas)** — Data cleaning, transformation, and feature engineering
2.  📓 **Jupyter Notebook (VS Code)** — Interactive environment for exploratory data analysis (EDA)
3.  📊 **Power BI Desktop** — Advanced data modeling and interactive dashboard design


📊 Dashboard Features
1.  **6 Executive KPI Cards:** Total Customers, Churn Rate, Total Churned, MRR at Risk, CLV, and Avg Tenure.
2.  **Churn Driver Analysis:** Bar charts mapping churn rates by contract type, payment method, internet service, and tenure group.
3.  **Tenure Trends:** Line chart visualizing customer churn behavior over time.
4.  **Cohort Churn Heatmap:** Matrix visual analyzing churn by contract type and tenure.
5.  **Revenue Leakage Insights:** Donut charts illustrating Monthly Revenue at Risk broken down by contract, internet service, and tenure.
6.  **Retention Benchmarks:** Detailed bar charts and matrix visuals mapping overall retention rates.
7.  **Interactive Slicers:** Global filtering by **Contract Type** for deep-dive exploration.


💡 Key Insights
1. **The Baseline:** The overall churn rate sits at **26.5%** — representing a loss of **1,869 out of 7,043** customers.
2. **Contract Vulnerability:** Month-to-month customers churn at a staggering **42.7%**, compared to a tiny **2.8%** for those on two-year contracts.
3. **Payment Friction:** Customers using electronic checks churn at **45.3%** — nearly **3x higher** than those on automatic payment methods.
4. **The Critical Window:** The first year is the deadliest; **47.7% of new customers churn within their first 12 months**.
5. **High-Value Exposure:** Fiber optic customers generate the highest revenue, yet they account for **$118,979** of the total **$139,130 monthly revenue at risk**.
6. **The Bottom Line:** While the average Customer Lifetime Value (CLV) is **$2,096**, the business is currently losing over **$1.6 million annually** to churn.


✅ Recommendations
1. **Lock In Short-Term Users:** Incentivize month-to-month customers to switch to annual contracts within their **first 90 days**.
2. **Automate Billing:** Offer small bill discounts or perks for switching to automatic payment methods to mitigate high electronic check churn.
3. **Overhaul Onboarding:** Invest heavily in the new customer onboarding experience, focusing intensely on user engagement during the **critical first 12 months**.
4. **Re-evaluate Premium Pricing:** Review the fiber optic pricing and value proposition to reduce churn in this high-revenue segment.
5. **Hyper-Targeted Campaigns:** Launch immediate retention campaigns specifically targeting the highest risk profile: **New + Month-to-Month + Electronic Check + Fiber Optic** users.


📁 Files Included
* churn_analysis.ipynb — Python notebook with full data cleaning and analysis
* WA_Fn-UseC_-Telco-Customer-Churn.csv — Original dataset (Kaggle Telco Churn)
* customers_clean.csv — Cleaned dataset exported from Python
* cohort_retention.csv — Cohort retention table
* cohort_heatmap.csv — Retention heatmap data
* churn_heatmap.csv — Churn heatmap data
* revenue_by_segment.csv — Revenue at risk by internet service
* revenue_all_segments.csv — Revenue at risk across all segments
* FUTURE_DS_02_CHURN_ANALYSIS.pbix — Power BI Dashboard file


👤 Author:
Jasco John Intern - Data Science & Analytics Track Future Interns Program Task 1 | FUTURE_DS_02 Date: June 2026
