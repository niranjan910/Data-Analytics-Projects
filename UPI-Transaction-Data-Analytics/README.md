# UPI Transaction Data Analytics

**Author:** Niranjan  
**Date:** 31 May 2025

---

## 📌 Project Background

This project analyzes UPI (Unified Payments Interface) transaction data to uncover user behavior patterns across cities, age groups, genders, time periods, and banking platforms.  
As a Data Analyst, the objective was to generate actionable insights that help banks and digital platforms optimize services and improve customer experience.

The project delivers insights and recommendations in the following key areas:

- 📍 City-Wise UPI Behavior  
- 🕒 Time-Based Transaction Patterns  
- 👥 User Segment Analysis (Age & Gender)  
- 🏦 Bank Performance Metrics  
- 💼 Balance vs Transaction Behavior  

Artifacts:
- Python Notebook: `UPI_EDA_Analysis.ipynb`  
- Power BI Dashboard: `UPI_Dashboard.pbix`  

---

## 🧾 Dataset & Features

The dataset includes the following cleaned and feature-engineered columns:

- **Date**, **Time**, **Year**, **Month**, **Day**, **Weekday**, **Week**, **Hour**, **Time_Period**
- **Transaction** – UPI transaction amount (₹000s)
- **Balance** – Post-transaction balance (₹000s)
- **Age**, **Age_Groups**
- **Gender**, **City**
- **Sent_From_Bank**, **Bank_Received**
- **Customer_ID** – Unique identifier

Initial cleaning steps:

- Converted `Date` and `Time` into datetime format  
- Extracted temporal features  
- Dropped null values in `Time`  
- Standardized key categorical columns  

---

## 📊 Exploratory Data Analysis

### ✅ Univariate Analysis
- Distribution plots for: `Transaction`, `Balance`, `Age`
- Count plots for: `Gender`, `City`, `Age_Groups`, `Bank_Received`

### ✅ Bivariate Analysis
- Box plots: `Transaction` vs `Age_Groups`, `Gender`, `City`
- Bar plots: `Transaction` vs `Weekday`, `Time_Period`
- GroupBy/Crosstab: Bank performance, city-wise metrics

### ✅ Time Series Analysis
- Daily, hourly, and monthly trend lines
- Peak transaction hours identified

---

## 🔍 Key Insights

- Evening hours (6–10 PM) record the highest UPI transaction volume  
- Users aged 18–30 dominate transaction activity  
- Top cities: Delhi, Mumbai, Bangalore  
- HDFC and ICICI outperform in total UPI throughput  
- Males transact slightly more than females on average  

---

## 📈 Dashboard Highlights (Power BI)

- 🔢 KPI Cards: Total, Average, Number of Transactions, Active Users  
- 📊 Tables: City Summary, Age Group Insights, Bank Performance  
- 📅 Visuals: Transactions by Weekday and Time Period  
- 🎯 Conditional formatting used for high/low indicators  

---

## ✅ Recommendations

- Scale server capacity during evening hours  
- Promote usage in less active cities/time slots via campaigns  
- Launch personalized offers for young adult users  
- Monitor inter-bank delays for operational improvement  
- Introduce balance-based financial nudges or alerts  

---

## ⚠️ Assumptions

- Transaction & Balance values are in ₹000  
- Null times dropped to ensure valid time-based analysis  
- No failed or pending transactions included  
- Gender, city, and bank names standardized manually  

---

## 📬 Contact

- **Email:** niranjan991100@gmail.com  
- **LinkedIn:** [Niranjan's Profile](https://www.linkedin.com/in/niranjan-a83517229/)
- **Portfolio**: [Portfolio](https://niranjan910.github.io/NiranjanDataAnalystPortfolio.github.io/)

---

