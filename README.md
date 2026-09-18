# Corporate Talent Optimization & Attrition Analytics
**Tools Used:** Microsoft Excel (Advanced Formulas, Power Query, Dynamic Dashboards)

## 💡 1. The Business Problem
The organization tracks 1,000 corporate staff members across 8 major departments. While baseline attendance is high (~90%), total human capital costs are climbing due to employee turnover. 

The objective of this analysis is to isolate systemic turnover risk and identify if attrition is a department-wide compensation issue or if it correlates directly to specific team managers.

## 🔍 2. Data Engineering & Cleaning
*   **Data Validation:** Audited the `Gender` and `Full Name` strings to ensure variable alignment.
*   **Normalization:** Ensured `Hire Date` values were correctly formatted into standardized YYYY-MM-DD format.
*   **Attrition Feature Engineering:** Segmented the workforce into `Active` vs `Resigned` blocks using the `Status` dimension to isolate churn metrics.

## 📊 3. Executive Dashboard & Insights

### [Insert Your Dashboard Screenshot or GIF Here]

*   **🚨 Attrition by Manager:** Team members managed by **Jamie Arnold** and **Daniel Wagner** show an alarming pattern of resigning compared to other leadership paths.
*   **💰 Specialization Tiers vs. Compensation Weights:** IT carries the highest monthly salary floor at **₱72,441.15**, followed closely by Finance at **₱70,923.28**. However, they maintain the lowest total headcount, proving the company pays a distinct premium for technical specialization.
*   **⏱ Training Hours & Performance ROI:** Departments with the highest collective training investment hours (HR with 5,255 hours and Customer Support with 4,823 hours) directly match the highest volume of top-tier performance rankings.

## 🚀 4. Strategic Recommendations
1. **Launch a Leadership Intervention Program:** Prioritize an immediate HR leadership audit for teams under high-attrition managers to determine if turnover is caused by bad management or workload issues.
2. **Rebalance the Marketing Compensation Floor:** Adjust the base pay framework for the Marketing department closer to the company median to prevent low compensation from triggering a mass wave of future resignations.
3. **Scale the Customer Support Training Model:** Take the onboarding and training modules used by Customer Support and scale them company-wide, as their high training hours show a direct mathematical correlation to achieving peak performance ratings.
