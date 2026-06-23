# Stroke Risk Prediction & Analysis  
### *Predict. Prevent. Protect.*

- **Author:** Niranjan  
- **Date:** 17 May 2025

---

## 📌 Project Background

This project aims to support healthcare providers in **identifying individuals at high risk of strokes** using patient data. By analyzing medical and lifestyle indicators (like age, glucose, BMI, smoking habits), we generate **data-driven insights** to support early intervention strategies and enhance healthcare decisions.

This project uses **Python** for data preprocessing and analysis, and **Power BI** for interactive business reporting and visualization.

---

## 🎯 Project Objectives

- **Predict High-Risk Patients** based on clinical and behavioral patterns.
- **Identify Key Risk Factors** contributing to strokes.
- **Visualize Stroke Risk Across Demographics** (e.g., age groups, gender, lifestyle).
- **Support Healthcare Decisions** using interactive Power BI dashboards.

---

## 🧾 Data Overview

The dataset contains **43,400 records** with fields including:

- **Demographics:** `gender`, `age`, `ever_married`, `Residence_type`, `work_type`
- **Medical History:** `hypertension`, `heart_disease`, `avg_glucose_level`, `bmi`
- **Lifestyle:** `smoking_status`
- **Target Variable:** `stroke`

### Engineered Columns:

- `age_group`, `glucose_category`, `bmi_category`
- `log_glucose`, `health_risk`, `lifestyle_risk`
- `residence_smoking_combo`, `married_age_group`

---

## 🧹 Data Cleaning & Feature Engineering Highlights

- Converted numeric risk indicators (`hypertension`, `heart_disease`, `stroke`) to categorical (`Yes/No`)
- Handled skewness and outliers in `avg_glucose_level` and `bmi` using **capping and log transformation**
- Categorized age, BMI, and glucose into **clinical ranges**
- Created composite features like `lifestyle_risk`, `health_risk`, and `residence_smoking_combo`

---

## 📊 Exploratory Data Analysis (Key Findings)

### 1. Stroke Risk by Age Group:
- **Elderly (60+ yrs)** have highest stroke rate (~8.8%)
- Risk increases significantly after **middle-age**

### 2. BMI Categories:
- **Overweight and Obese I-II** groups show the highest stroke rates
- Underweight and severely thin groups have very low stroke incidence

### 3. Residence Type:
- Stroke risk is slightly higher in **urban** areas

### 4. Lifestyle Risk:
- **High-risk lifestyle** (smoking + unhealthy habits) → stroke rate ~2.67%
- Moderate and low-risk groups have lower rates

### 5. Work Type:
- **Self-employed** have stroke rate of ~3.7%, highest among all work groups

### 6. Smoking + Residence Combo:
- Highest risk: **Urban - Formerly Smoked** (3.17%)
- Never smoked groups show the **lowest stroke rates**

---

## 📈 Tools Used

- **Python (Jupyter Notebook)** – Data Cleaning, EDA, Feature Engineering
- **Pandas, NumPy, Seaborn, Matplotlib** – Analysis and visualization
- **Power BI** – Business dashboarding and reporting

---

## 📊 Dashboard Insights

The Power BI dashboard includes:

- Stroke distribution by **demographics and regions**
- **Age group**, **BMI**, **glucose** and **smoking impact**
- Lifestyle and health risk segmentation
- Dynamic filters to explore **interactive risk patterns**

---

## 🧠 Recommendations

- Focus preventive care on **elderly and self-employed individuals**
- Target **smokers (especially former)** with awareness and medical screening
- Monitor and manage **glucose and BMI** levels in at-risk groups
- Use **composite risk indicators** (like lifestyle score) for better prioritization

---

## ❗ Assumptions & Caveats

- Medical standards used to define BMI and glucose categories
- Missing values imputed logically (median for BMI, mode for categorical)
- Some features (like `id`, `avg_glucose_capped`) were dropped post-analysis
- No geographic/location data was available, limiting regional analysis depth

---

## 📬 Contact

For queries or collaborations:  
📧 [niranjan991100@gmail.com](mailto:niranjan991100@gmail.com)  
🔗 [LinkedIn - Niranjan](https://www.linkedin.com/in/niranjan-k-a83517229/)
