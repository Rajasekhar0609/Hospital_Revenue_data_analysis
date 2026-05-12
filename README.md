# 🏥 Hospital Operations & Patient Risk Intelligence Dashboard

## 📌 Project Overview

This project is an end-to-end Healthcare Analytics and Business Intelligence solution developed using **Power BI, SQL, Python, DAX, and Power Query**.

The dashboard is designed to help hospital leadership monitor:

- Patient admissions
- Readmission risk
- Treatment cost
- Mortality rate
- Bed occupancy
- Department performance
- Insurance distribution
- Branch-level operational efficiency

The project simulates a real-world healthcare analytics engagement using messy relational datasets with data quality issues, duplicate records, missing values, and operational KPIs.

---

# 🚀 Project Objectives

The primary goal of this project is to identify:

✅ High-risk patient segments  
✅ Readmission trends and operational bottlenecks  
✅ High-cost treatments and departments  
✅ Hospital branch performance  
✅ Insurance and payment distribution  
✅ Resource utilization and occupancy trends  

---

# 📊 Dashboard Features

## Executive Overview Dashboard

### KPI Cards
- Total Patients
- Total Admissions
- Readmission Rate
- Avg Treatment Cost
- Avg Length of Stay
- Mortality Rate
- Bed Occupancy %

### Visualizations
- Admissions Trend (Monthly)
- Readmission Rate by Department
- Top Diseases by Admissions
- Revenue by Hospital Branch
- Admissions by Age Group & Gender
- Insurance Type Distribution
- Branch Performance Summary Table

---

# 🛠 Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Power BI | Dashboard Development |
| SQL | Data Analysis & Querying |
| Python | Data Cleaning & EDA |
| Power Query | Data Transformation |
| DAX | KPI & Measure Calculations |
| Excel/CSV | Raw Data Sources |

---

# 🗂 Dataset Information

The project includes multiple relational healthcare datasets:

| Dataset | Description |
|---|---|
| patients_raw | Patient demographics |
| admissions_raw | Hospital admissions |
| billing_claims_raw | Billing and insurance claims |
| treatments_raw | Treatment records |
| pharmacy_orders_raw | Medication orders |
| lab_results_raw | Lab test results |
| followups_raw | Post-discharge follow-ups |
| hospitals | Hospital master data |
| doctors | Doctor master data |
| departments | Department master data |

---

# 📈 Key KPIs

## Readmission Rate

```DAX
Readmission Rate =
DIVIDE(
    [Readmission Count],
    [Total Admissions],
    0
)
