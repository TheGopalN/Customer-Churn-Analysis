# 📊 Customer Churn Analysis & Retention Dashboard

![Dashboard Preview](dashboard/dashboard_overview.png)

**Tools:** Python | Power BI | Excel  
**Dataset:** 7,032 telecom customers | 33 features  
**Status:** ✅ Completed

---

## 🎯 Project Objective
Analyze customer churn patterns in a telecom dataset to identify 
key churn drivers and build an interactive 3-page Power BI dashboard 
to support data-driven retention strategies.

---

## 📁 Repository Structure
```
📦 Customer-Churn-Analysis
 ┣ 📂 data
 ┃ ┣ 📄 Telco_customer_churn.xlsx        ← Raw dataset (7,043 rows, 33 columns)
 ┃ ┗ 📄 telecom_churn_cleaned.csv        ← Cleaned dataset after preprocessing
 ┣ 📂 notebook
 ┃ ┗ 📓 Churn_Analysis.ipynb             ← Data cleaning & EDA
 ┣ 📂 dashboard
 ┃ ┣ 🖼️ dashboard_overview.png           ← Power BI Page 1
 ┃ ┣ 🖼️ dashboard_churn_drivers.png      ← Power BI Page 2
 ┃ ┗ 🖼️ dashboard_customer_profile.png  ← Power BI Page 3
 ┗ 📄 README.md
```

---

## 🔍 Key Findings
- 📌 Overall churn rate: **26.58%** — 1,869 out of 7,032 customers churned
- 📌 **Month-to-month** contracts churn at **43%** — highest risk contract type
- 📌 **Fiber optic** customers churn at **42%** — highest risk internet service
- 📌 **Electronic check** payment users churn at **45%** — highest risk payment method
- 📌 Customers in **first 12 months** churn at **48%** — most critical retention window
- 📌 **Senior citizens** churn at **63.8%** — 2.4x the overall average
- 📌 Customers **without tech support** churn at **42%** vs only **15%** with support
- 📌 Highest risk segment: Month-to-month + Fiber optic + Electronic check = **60.37% churn**
- 📌 Total revenue lost to churn: **$139,130/month**

---

## 📊 Dashboard Preview

### Page 1 — Overview KPIs
![Overview](dashboard/dashboard_overview.png)

### Page 2 — Churn Drivers
![Churn Drivers](dashboard/dashboard_churn_drivers.png)

### Page 3 — Customer Profile
![Customer Profile](dashboard/dashboard_customer_profile.png)

---

## 💡 Business Recommendations
1. **Promote annual/two-year contracts** — offer discounts to convert month-to-month customers
2. **Focus on first 12 months** — implement strong onboarding and early engagement program
3. **Bundle tech support** — customers with tech support churn 3x less
4. **Senior citizen retention program** — dedicated support and simplified pricing plans
5. **Incentivize automatic payments** — electronic check users churn at nearly 3x the rate of automatic payment users

---

## 🛠️ Technical Skills Used
| Skill | Usage |
|-------|-------|
| Python (Pandas, NumPy) | Data cleaning, feature engineering |
| Power BI & DAX | Interactive dashboard, 15+ measures |
| Excel | Data validation and analysis |
| SQL | Data querying concepts applied |

---

## 👤 Author
**Gopal Kumar** — Data Analyst  
📍 Hyderabad, India  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/gopal-kumar1/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/TheGopalN)
