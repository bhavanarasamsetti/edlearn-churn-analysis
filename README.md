# 📊 EdLearn Customer Analytics Dashboard  
### Power BI | Excel | Data Cleaning | Data Modeling  

This project analyzes the customer behavior, revenue patterns, churn trends, and product usage of **EdLearn**, an online learning platform.  
The dashboard provides actionable insights that help understand user engagement, retention, and revenue drivers.

---

## 🚀 Project Overview

The goal of this project is to build a complete data analytics workflow using:

- **SQL** (- Wrote SQL queries to validate churn calculations, revenue totals, and customer counts using joins and aggregations)
- **Excel** (data cleaning, column creation, pivot checks)
- **Power BI** (interactive dashboards & business insights)
- **DAX** (basic calculations)
- **Data Modeling** (connecting 11 data sources)

This is a beginner → intermediate project designed to demonstrate real-world business analysis skills.

---

## 🗂 Data Sources (11 CSV Files)

The dashboard uses the following datasets:

- `payments.csv`
- `revenue_by_month.csv`
- `customers.csv`
- `customer_segments.csv`
- `customer_revenue.csv`
- `usage.csv`
- `support.csv`
- `subscriptions.csv`
- `surveys.csv`
- `churn_by_month.csv`
- `cohort_ltv.csv`  *(optional: not used in final dashboard)*

---

## 🧼 Data Preparation

### In Excel:
- Standardized **date formats**
- Cleaned **customer age groups**
- Created **Month–Year columns**
- Verified **revenue totals**
- Prepared data for Power BI using `.xlsx`

### In Power BI:
- Loaded **all 11 cleaned datasets**
- Built a proper **star schema**
- Defined relationships (1:M)
- Disabled all wrong auto-detected connections

---

## 📈 Power BI Visuals & Dashboards

The project contains a **4-page interactive dashboard**:

---

### 🟦 **Page 1 — Revenue & Churn Overview**

**Charts:**
- Monthly Revenue Trend  
- Monthly Customer Churn Trend  

**Insights:**
- Revenue peak around mid-2024  
- Churn decreases sharply after 2024

---

### 🟩 **Page 2 — Customer Segments & Acquisition**

**Charts:**
- Age Group Distribution  
- Gender Distribution  
- Acquisition Channel Breakdown  

**Insights:**
- Largest segment: **13–15 age group**
- Gender is balanced  
- Organic + Google Ads drive major acquisition

---

### 🟧 **Page 3 — High-Value Customers**

**Charts:**
- Top 20 Revenue-Generating Customers  

**Insights:**
- Strong Pareto pattern (20% of customers → majority of revenue)

---

### 🟪 **Page 4 — Usage & Support Analytics**

**Charts:**
- Monthly Product Usage Trend  
- Monthly Support Tickets Trend  
- Subscription Type Breakdown  

**Insights:**
- Product usage peaks around May/June  
- Support tickets drop after mid-2024  
- Most customers are on **monthly plans**

---

## 💡 Key Business Insights

- Total revenue: **₹9.3M+**
- Revenue shows strong growth until mid-2024, then a decline  
- Churn improved significantly in 2025  
- User base dominated by **school-age learners (13–15)**  
- Organic search contributes **35% of new users**  
- Heavy dependence on a few high-value customers  
- Monthly plan is most popular → potential for yearly upgrade strategy

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **Microsoft Excel**
- **DAX (Basic Calculations)**
- **Data Modeling**
- **Visualization Best Practices**

---

## 📂 Project Structure
edlearn-churn-analysis/
├── data/
│   ├── payments.csv
│   ├── revenue_by_month.csv
│   ├── customers.csv
│   ├── customer_segments.csv
│   ├── customer_revenue.csv
│   ├── churn_by_month.csv
│   ├── usage.csv
│   ├── support.csv
│   ├── surveys.csv
│   ├── subscriptions.csv
│   └── cohort_ltv.csv
│
├── powerbi/
│   ├── edlearn_dashboard.pbix
│   └── dashboard_report.pdf
│
└── README.md
 Final Note

This project was created as part of my analytics learning journey.
It showcases beginner → intermediate skills in:

Data cleaning

Data modeling

DAX

Visualization

Business storytelling
