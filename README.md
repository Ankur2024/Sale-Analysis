# 📊 Sales Analytics Dashboard (Customer & Product Insights)

## 🚀 Project Overview

This project delivers an **end-to-end analytics solution** built using SQL and Power BI. It focuses on analyzing **customer behavior** and **product performance** through structured reporting and interactive dashboards.

The goal is to transform raw transactional data into **actionable business insights**.

---

## 📌 Key Features

### 👤 Customer Analytics

* Customer segmentation (VIP, Regular, New)
* Age group distribution
* Customer lifetime (lifespan)
* Recency analysis (last purchase behavior)
* Key KPIs:

  * Total Orders
  * Total Sales
  * Average Order Value (AOV)
  * Average Monthly Spend

### 📦 Product Analytics

* Product segmentation (High, Mid, Low performers)
* Category & subcategory performance
* Product lifespan tracking
* Sales recency insights
* Key KPIs:

  * Total Revenue
  * Total Quantity Sold
  * Average Selling Price
  * Average Monthly Revenue

---

## 🧱 Data Model

The project uses two main reporting views:

### 🔹 `gold.report_customers`

* Aggregated customer-level metrics
* Customer segmentation & age grouping
* KPIs like AOV, recency, monthly spend

### 🔹 `gold.report_products`

* Aggregated product-level metrics
* Product segmentation by revenue
* KPIs like AOR, recency, monthly revenue

---

## 📊 Dashboard Preview
<img width="1167" height="659" alt="Screenshot 2026-04-14 221306" src="https://github.com/user-attachments/assets/ffd05304-8485-4a2a-b90d-ee0c03c711fc" />


---

## 📈 Insights Generated

* Identified high-value **VIP customers driving majority of revenue**
* Discovered **top-performing product categories**
* Highlighted **inactive customers** using recency metrics
* Detected **low-performing products** for optimization
* Analyzed **customer demographics for targeted marketing**

---

## 🛠️ Tools & Technologies

* **SQL (PostgreSQL)** → Data transformation & reporting views
* **Power BI** → Dashboard & data visualization
* **DAX** → KPI calculations

---

## 📂 Project Structure

```
├── sql/
│   ├── report_customers.sql
│   └── report_products.sql
│
├── dashboard/
│   └── sales_dashboard.pbix
│
└── README.md
```

---

## 🎯 Business Value

This dashboard helps stakeholders:

* Make **data-driven decisions**
* Improve **customer retention**
* Optimize **product strategy**
* Track **business performance in real time**

