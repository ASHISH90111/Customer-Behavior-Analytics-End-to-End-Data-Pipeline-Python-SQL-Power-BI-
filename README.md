# ✅ 🔥 Customer Behavior Analytics: End-to-End Data Pipeline (Python + SQL + Power BI)

## 📄 Project Overview

An end-to-end data analytics project that explores customer shopping behavior using **Python**, **SQL**, and **Power BI** to generate actionable business insights.

This project analyzes **3,900 customer transactions** to understand purchasing behavior, customer segmentation, and revenue trends.

### 🎯 Main Business Goal
Leverage customer data to improve sales, engagement, and marketing strategies

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python (Pandas, NumPy)** | Data Cleaning & Feature Engineering |
| **SQL (PostgreSQL)** | Business Analysis & Querying |
| **Power BI** | Interactive Dashboard & Visualization |

---

## 📁 Dataset Details

| Attribute | Value |
|-----------|-------|
| 📌 Rows | 3,900 |
| 📌 Columns | 18 |
| **Key Features** | Customer Demographics (Age, Gender), Purchase Details (Category, Amount), Behavior Data (Frequency, Discounts, Reviews) |
| ⚠️ Missing Values | Handled using median imputation (category-wise) |

---

## 🧹 Data Processing (Python)

- Loaded dataset using `pandas`
- Handled missing values in `review_rating`
- Standardized column names (`snake_case`)
- **Feature Engineering:**
  - `age_group` segmentation
  - `purchase_frequency_days` mapping
- Removed redundant column (`promo_code_used`)

---

## 🗄️ Database Integration

- Data exported to **PostgreSQL** / **MySQL** / **SQL Server**
- Used **SQLAlchemy** + **psycopg2** for pipeline

---

## 🔍 SQL Business Analysis

Key business questions answered:

- ✅ Revenue comparison → Male vs Female
- ✅ High-value discount users
- ✅ Top-rated products
- ✅ Shipping type impact
- ✅ Subscriber vs Non-subscriber spending
- ✅ Discount-driven products
- ✅ Customer segmentation (New / Returning / Loyal)
- ✅ Top products per category
- ✅ Repeat buyers vs subscription
- ✅ Revenue by age group

---

## 📈 Power BI Dashboard

### Key Metrics
| Metric | Value |
|--------|-------|
| 👥 Customers | 3.9K |
| ⭐ Avg Rating | 3.75 |
| 💰 Avg Purchase | $59.76 |

### Visual Insights
- Revenue by Category
- Sales by Age Group
- Subscription Distribution
- Category-wise Sales

### 🎛 Filters Used
- Gender
- Subscription Status
- Category
- Shipping Type

---

## 📊 Key Insights

| Insight |
|---------|
| 🧍‍♂️ Male customers generate higher revenue |
| 🛍️ Clothing is the top-performing category |
| 🚚 Express shipping → higher average spend |
| 🔁 Loyal customers dominate dataset |
| 🎯 Young Adults contribute highest revenue |

> *Insights validated from SQL results*

---

## 💡 Business Recommendations

1. Increase subscription benefits
2. Target loyal customers with rewards
3. Optimize discount strategy
4. Focus on high-performing categories
5. Use age-based targeted marketing

---

## 🏗 Project Structure
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── data_cleaning.ipynb
├── sql/
│   └── business_queries.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
├── README.md

---

## 🧠 What I Learned

- Real-world data cleaning & feature engineering
- Writing analytical SQL queries
- Building business dashboards
- Translating data → insights → decisions

---

## ⭐ Future Improvements

- [ ] Add ML model (customer segmentation / prediction)
- [ ] Deploy dashboard (Power BI Service)
- [ ] Automate ETL pipeline

---

## 📫 Connect

Feel free to reach out for collaboration or feedback!

---

⭐ **If you found this project useful, give it a star!** ⭐
