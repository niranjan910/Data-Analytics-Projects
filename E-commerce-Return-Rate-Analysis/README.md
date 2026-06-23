
# E-commerce Return Rate Analysis

**Author:** Niranjan  
**Date:** 3 May 2025

---

# Project Background

This project focuses on analyzing **product performance metrics** within an e-commerce environment. As a Data Analyst, my goal was to explore factors affecting product sales, returns, delivery times, and overall customer satisfaction to uncover actionable business insights that can optimize pricing, inventory, and logistics strategies.

The study covers key product aspects such as price, discount rates, ratings, stock availability, and return behavior. The results aim to support better **pricing strategies**, **inventory planning**, and **customer experience improvements**.

---

# Dataset Description

This **synthetic yet realistic dataset** contains **2,000 product records**, designed to mimic a real-world e-commerce platform. It is suitable for **intermediate-level data analysis and machine learning** tasks and includes:

- Natural randomness,
- Missing values (~5% per column),
- Varying distributions (normal, skewed, categorical).

The dataset allows for hands-on practice in **data cleaning**, **exploratory data analysis (EDA)**, and **business-focused reporting**.

---

# Data Structure & Initial Checks

| Column Name           | Description                                                               |
|-----------------------|---------------------------------------------------------------------------|
| Product_Price         | Listed price of the product in USD (5 to 1000).                           |
| Discount_Rate         | Discount applied (0.0 to 0.8).                                            |
| Product_Rating        | Customer rating (1 to 5 scale).                                           |
| Number_of_Reviews     | Number of reviews (0 to 5000, highly skewed).                              |
| Stock_Availability    | Whether the product is in stock (`Yes`/`No`).                              |
| Days_to_Deliver       | Days to deliver the product (1 to 30).                                     |
| Return_Rate           | Fraction of items returned (0.0 to 0.9).                                   |
| Category_ID           | Product category (1 to 10, integer labels).                                |

---

# Executive Summary

### Key Highlights

- **Product Pricing:** Majority of products are priced between \$20 and \$500, with occasional high-end outliers.
- **Discounting Patterns:** Discount rates typically cluster between 10% and 40%, with very few deep-discounted items.
- **Product Ratings:** Ratings are slightly **left-skewed** (skew = -0.43), indicating generally **high customer satisfaction**.
- **Stock & Delivery:** Most products are in stock; delivery times are **symmetrically distributed** with an average of ~5–10 days.
- **Return Trends:** Return rates vary but cluster around 20%–40%, helping identify potential product or logistics issues.

---

# Data Cleaning Steps

- ✔️ Handled missing values (mean/median imputation based on skewness).
- ✔️ Verified and **confirmed no duplicate rows**.
- ✔️ Standardized data types (e.g., categorical vs. numerical).
- ✔️ Reviewed distribution and outliers for all columns.

---

# Next Steps

- **Univariate Analysis:** Understand distributions and detect anomalies per column.
- **Bivariate Analysis:** Explore relationships between key metrics (e.g., price vs. rating, discount vs. return rate).
- **Multivariate Analysis:** Analyze combined effects (e.g., pricing + discount + stock on returns).
- **Visualizations:** Create intuitive charts for clear storytelling.

---

# Assumptions & Caveats

- This dataset is **synthetic** but designed to reflect real-world e-commerce behavior.
- Missing values (~5% per column) were filled based on distribution characteristics.
- Category_ID is **treated as categorical** even though it's numeric.

---

## 📬 Contact

For queries or collaborations:  
- **Email:** niranjan991100@gmail.com  
- **LinkedIn:** [Niranjan's Profile](https://www.linkedin.com/in/niranjan-a83517229/)
- **Portfolio**: [Portfolio](https://niranjan910.github.io/NiranjanDataAnalystPortfolio.github.io/)
