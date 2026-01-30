# Accounting & Financial Management Analysis (Power BI)

## 📌 Project Overview
This project presents a **financial performance analysis** for a sample accounting & financial services firm (similar to CA / finance BPO organizations). The objective is to analyze **revenue, expenditure, profitability, and financial risk** using Power BI and provide clear, management‑level insights.

The project is designed as a **realistic junior data analyst portfolio project**, focusing on clarity, correct financial logic, and business interpretation rather than complex modeling.

---

## 🎯 Business Objectives
The management wanted to understand:
- Overall **financial performance** of the company
- Trends in **revenue and expenditure**
- **Profitability and efficiency** over time
- **Net income stability**
- **Financial risk** using debt metrics

---

## 🗂️ Dataset Information
- **Dataset Type:** Accounting & Financial Management (sample / synthetic data)
- **Source:** Kaggle (public dataset)
- **Records:** ~1000 transactions
- **Time Period:** Multiple years (filtered using Year slicer)

### Key Columns Used
- Date
- Revenue
- Expenditure
- Gross Profit
- Net Income
- Profit Margin
- Debt‑to‑Equity Ratio
- Transaction Amount
- Account Type

---

## 🛠️ Tools & Technologies
- **Power BI** – Data cleaning, modeling, DAX, and dashboard creation
- **Power Query** – Data cleaning and transformation
- **Excel** – Initial data validation

---

## 🧹 Data Cleaning & Preparation
The following steps were performed in Power Query:
- Removed currency symbols and commas from numeric fields
- Corrected data types (Decimal, Whole Number, Date, Text)
- Handled duplicates
- Verified missing values (none found)
- Created Year filtering logic for analysis

All columns were validated to ensure **100% error‑free data** before analysis.

---

## 📊 KPIs & Measures

The following KPIs and measures were created using **DAX** in Power BI.

### 1️⃣ Total Revenue
```
Total Revenue = SUM('Table'[Revenue])
```

### 2️⃣ Total Expenditure
```
Total Expenditure = SUM('Table'[Expenditure])
```

### 3️⃣ Gross Profit
```
Gross Profit = SUM('Table'[Gross Profit])
```

### 4️⃣ Net Income
```
Net Income = SUM('Table'[Net Income])
```

### 5️⃣ Profit Margin % (Weighted)
```
Profit Margin % = 
DIVIDE(
    SUM('Table'[Net Income]),
    SUM('Table'[Revenue])
)
```

### 6️⃣ Average Debt-to-Equity Ratio
```
Avg Debt-to-Equity = AVERAGE('Table'[Debt-to-Equity Ratio])
```

> ⚠️ **Note:** Profit Margin and Debt-to-Equity are ratio metrics, so they are calculated using weighted or average logic instead of SUM. This reflects correct financial reporting practices.

---

## 🔗 Interactive Dashboard

👉 **View Power BI Dashboard:**  
<p align="left">
  <a href="https://github.com/kalpana-da/Finance-Accounting-Data-Analytics/blob/main/acoounting_data_dashboard.pdf" target="_blank">
    <img src="https://img.shields.io/badge/View-Dashboard-blue?style=for-the-badge">
  </a>
</p>

---

## 📈 Dashboard Structure
The Power BI dashboard is structured into three clear sections:

### 1️⃣ KPI Overview
- Total Revenue
- Total Expenditure
- Gross Profit
- Net Income
- Profit Margin %

### 2️⃣ Performance Trends
- Revenue vs Expenditure (Monthly Trend)
- Net Income Trend by Month

### 3️⃣ Efficiency & Risk Analysis
- Profit Margin % by Month
- Average Debt‑to‑Equity Ratio by Month

A **Year slicer** is provided to allow dynamic analysis across years.

---

## 🧠 Key Business Insights
- Revenue consistently exceeds expenditure, indicating healthy operations.
- Seasonal dip observed during October–November, impacting revenue and net income.
- Expenditure remains controlled but peaks mid‑year, requiring monitoring.
- Profit margins are strongest during mid‑year and year‑end, showing improved efficiency.
- Debt‑to‑Equity ratio rises gradually mid‑year and stabilizes toward year‑end, indicating manageable financial risk.

---

## 📌 Conclusion
The analysis shows that the company maintains **stable profitability, controlled expenses, and acceptable debt levels**. Opportunities exist to:
- Improve performance during seasonal downturns
- Monitor mid‑year expense increases
- Maintain optimal leverage ratios

This project demonstrates the ability to:
- Clean and model financial data
- Build professional Power BI dashboards
- Translate data into meaningful business insights

---

## 👤 Author
**Kalpana**  
 Data Analyst | Finance Analytics | Power BI
<p align="left">
  <a href="https://www.linkedin.com/in/skalpana/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-View%20Profile-blue?style=for-the-badge&logo=linkedin">
  </a>
</p>

---

## 📎 Files Included
- Power BI (.pbix) dashboard file
- Dataset (CSV)
- README.md

---


