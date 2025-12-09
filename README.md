# 📊 PowerBI-Healthcare-Insights

An interactive and visually clean **Power BI dashboard** designed to analyze key healthcare metrics such as patient demographics, medical conditions, billing trends, doctor and hospital performance, and insurance contribution patterns.

This project is designed with a **corporate-style minimal UI**, ensuring clarity, usability, and meaningful insights for healthcare decision-making.
---

## ⭐ Project Overview

This dashboard transforms raw healthcare data into an easy-to-understand visual story.  
It helps stakeholders analyze:

- Most common medical conditions  
- Revenue distribution across insurance providers  
- Doctor and hospital performance  
- Gender distribution  
- Age vs Billing patterns  
- Monthly billing trends  
- Patient count by condition  
- Admission type behavior
---

## 📸 Dashboard Preview
![Healthcare Dashboard](C:\Users\Bhumika Gajbhiye\OneDrive\Pictures\Screenshots\dashboard_full.png)
---

## 📌 Key Features

### 📍 **1. KPI Overview**
Includes the most important aggregated metrics:
- Most common medical condition - Arthritis
- Total patients - 56K
- Average billing amount - 25.54K (in $)    
- Total billing amount - 1.42bn
- Average patient age - 51.54
- Average billing per condition - 236.24M (in $)
  
### 📍 **2. Demographics**
- Gender split of patients  
- Age vs Billing Scatter Analysis  
- Admission type by gender  

### 📍 **3. Medical Condition Insights**
- Patient count by condition  
- Billing by condition across insurance providers  

### 📍 **4. Financial & Operational Insights**
- Monthly billing trend (line chart)  
- Total billing by insurance provider  
- Doctor-wise billing contribution (Top 10)  
- Hospital billing performance (Top 10 Treemap)  

---
## 🧠 General Insights

Below are the key analytical insights derived from the dashboard.  

---

## 🧍‍♂️🧍‍♀️ 1. Gender Distribution Insights
- The gender ratio is nearly balanced, Female - 49.96% & Male - 50.04%, suggesting no strong demographic skew.
- Both Male and Female patients contribute almost equally to the total patient count.
- Minor variations exist, but neither gender dominates the patient population.

---

## ❤️‍🩹 2. Medical Condition Insights
- Conditions such as **Arthritis, Diabetes, Hypertension, Obesity and Cancer** have the highest patient counts.
- These chronic conditions dominate the majority of cases in the dataset.
- Less frequent conditions indicate lower occurrence or case severity.

---

## 📈 3. Billing Trend Insights (Monthly)
- Monthly billing remains relatively stable with minor upward and downward variations.
- A small spike/dip appears in the final month, possibly seasonal or operational.
- No extreme fluctuations, indicating consistent billing activity.

---

## 👥 4. Age vs Billing Insights
- Billing amounts show mild positive variation with increasing age groups.
- Significant spread in the scatter plot indicates varied billing across similar ages.
- No single age group overwhelmingly dominates the billing contribution.

---

## 🏥 5. Hospital Performance Insights
- A few hospitals (e.g., **Johnson PLC, Smith Ltd, LLC Smith, Group Smith**) contribute the highest billing.
- Clear performance hierarchy is visible, with top hospitals dominating revenue.
- Other hospitals show moderate but steady contributions.

---

## 🩺 6. Doctor Performance Insights
- The top doctors generate a significantly higher share of the total billing.
- A classic long-tail distribution is present — top 3–5 doctors dominate revenue.
- Indicates specialist-driven financial contribution.

---

## 💳 7. Insurance Provider Insights
- Major providers like **Cigna, Medicare, Blue Cross, United Healthcare, and Aetna** contribute similarly to overall billing.
- No single insurance provider shows extreme dominance.
- Billing distribution across providers is balanced.

---

## 🚑 8. Admission Type Insights
- Admission types (Elective, Emergency, Urgent) vary slightly between genders.
- No large imbalance, but subtle gender-specific patterns exist.
- Useful for understanding patient behavior and admission trends.
---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard creation, visuals, DAX |
| **Power Query** | Data cleaning and transformations |
| **Excel** | Base dataset source |
| **DAX** | Calculated measures and KPIs |
---

## 📂 Project Structure

```text
PowerBI-Healthcare-Insights/
│── README.md  
│── dashboard.pbix  
│── images/  
│   ├── dashboard_preview.gif  
│   └── dashboard_full.png  
│── data/   (optional)
```
---

## 🧹 Data Preparation Summary

Data was cleaned and transformed using **Power Query**:

- Removed duplicates and null rows  
- Standardized column names  
- Converted data types (Age → Whole Number, Billing → Decimal)  
- Created new calculated fields (billing metrics, categories)  
- Built relationships between tables  
- Ensured modeling consistency for visuals
---

## ▶️ How to Use the Dashboard

1. Download the `.pbix` file  
2. Open using **Power BI Desktop**  
3. Load or refresh the data source  
4. Interact with charts, filters, and visuals  
5. Review insights from KPIs and charts  
---

## 🚀 Future Enhancements

- Add forecasting using Power BI analytics pane  
- Create drill-through pages for Doctor/Hospital details  
- Add a mobile layout view  
- Connect to a SQL database for live data updates  
- Add patient segmentation / clustering  
---

## 👩‍💻 About the Author

**Bhumika Gajbhiye**  
Master’s in Statistics  
Skills: Power BI, Python, R, SQL, Excel, Data Analytics  
Passionate about building clean, insight-driven dashboards.
---

# ⭐ If you find this project helpful, consider giving it a star!



