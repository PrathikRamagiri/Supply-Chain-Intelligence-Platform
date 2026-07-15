# 📦 Supply Chain Intelligence Platform

### End-to-End Business Intelligence Solution using Power BI

An enterprise-style **Supply Chain Intelligence Platform** developed in **Power BI** to analyze business performance, monitor supply chain operations, and support strategic decision-making. This project follows a complete Business Intelligence workflow, including **ETL, dimensional data modeling, DAX, interactive dashboards, and executive insights**.

---

## 📖 Project Overview

Modern organizations require real-time visibility into supply chain operations to improve profitability, optimize logistics, and enhance customer satisfaction. This project transforms raw transactional data into meaningful business insights through an interactive Power BI dashboard.

The dashboard enables business users to monitor revenue, profitability, shipping performance, product performance, and customer trends using KPI-driven visualizations.

---

## 🎯 Business Problem

Organizations often face challenges such as:

- High percentage of late deliveries
- Limited visibility into operational performance
- Difficulty identifying profitable products and categories
- Lack of centralized business reporting
- Inefficient decision-making due to fragmented data

The objective of this project is to build a centralized Business Intelligence solution that provides actionable insights for supply chain and business operations.

---

# 🚀 Business Objectives

- Monitor overall business performance using KPIs
- Analyze product and category profitability
- Evaluate shipping and delivery performance
- Identify operational bottlenecks
- Understand customer purchasing behavior
- Support executive decision-making through interactive dashboards

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning & ETL |
| DAX | Business Calculations |
| Star Schema | Data Modeling |
| Bing Maps | Geographic Visualization |

---

# 📂 Dataset

**Dataset:** DataCo Smart Supply Chain Dataset

The dataset contains transactional information related to:

- Orders
- Customers
- Products
- Categories
- Shipping
- Sales
- Profit
- Delivery Status

This dataset simulates real-world supply chain operations.

---

# 🔄 ETL Process

Data transformation was performed using **Power Query**.

### Steps Performed

- Imported raw dataset
- Removed duplicate records
- Corrected data types
- Created dimension tables
- Built a Star Schema
- Generated surrogate keys
- Established table relationships
- Optimized data model for reporting

---

# ⭐ Data Model

The project follows a professional **Star Schema** design.

```
                 Dim_Date
                     │
                     │
Dim_Product ─── Fact_Orders ─── Dim_Customer
                     │
                     │
               Dim_Shipping
```

The dimensional model improves report performance, scalability, and maintainability.

---

# 📊 Key Performance Indicators

- 💰 Total Revenue
- 📈 Total Profit
- 📊 Profit Margin %
- 📦 Total Orders
- 👥 Total Customers
- 💳 Average Order Value
- 🚚 Late Delivery Rate
- ⭐ Supply Chain Score
- ⏱ Average Shipping Days
- 📅 Average Delivery Delay

---

# 📑 Dashboard Pages

## 1️⃣ Executive Overview

Provides a high-level overview of business performance through executive KPIs and interactive visualizations.

### Includes

- Revenue
- Profit
- Profit Margin
- Orders
- Customers
- Average Order Value
- Revenue Trend
- Revenue by Category
- Delivery Performance
- Geographic Analysis

---

## 2️⃣ Supply Chain & Delivery Performance

Focuses on logistics and shipping efficiency.

### Includes

- Total Shipments
- Late Deliveries
- Late Delivery %
- Average Shipping Days
- Average Delivery Delay
- Shipping Mode Performance
- Delivery Trend
- Delay Distribution

---

## 3️⃣ Product & Inventory Intelligence

Analyzes product performance and profitability.

### Includes

- Product Revenue
- Product Profit
- Product Ranking
- Category Profitability
- Top Performing Products
- Product Performance Matrix

---

## 4️⃣ Customer Intelligence

Provides insights into customer purchasing behavior and regional performance.

### Includes

- Customer Distribution
- Revenue by Customer
- Customer Segmentation
- Geographic Revenue Analysis
- Top Customers

---

## 5️⃣ Executive Insights

Summarizes the most important business findings and strategic recommendations.

Provides decision-makers with actionable insights instead of raw data.

---

# 📈 Business Insights

- More than **54%** of shipments experienced late deliveries, highlighting opportunities to improve logistics performance.
- A small number of product categories generate a significant share of total revenue.
- Product profitability varies considerably across categories, indicating opportunities for product portfolio optimization.
- Customer purchasing patterns reveal high-value customer segments that contribute disproportionately to revenue.
- Revenue trends provide visibility into seasonal demand and business performance.

---

# 💡 Business Recommendations

- Improve shipping processes to reduce late deliveries.
- Focus inventory planning on high-performing products.
- Prioritize high-margin product categories.
- Monitor logistics KPIs continuously to improve operational efficiency.
- Strengthen customer engagement strategies for high-value customer segments.
- Use KPI-driven dashboards to support faster executive decision-making.

---

# 📌 Skills Demonstrated

- Business Intelligence
- Power BI
- Power Query (ETL)
- DAX
- Data Modeling
- Star Schema Design
- KPI Development
- Dashboard Design
- Data Visualization
- Executive Reporting
- Business Storytelling

---

# 📁 Repository Structure

```
Supply-Chain-Intelligence-Platform
│
├── Dataset
│   └── DataCoSupplyChainDataset.csv
│
├── Power BI
│   └── Supply Chain Intelligence Platform.pbix
│
└── README.md
```

---

# 🎓 Learning Outcomes

This project demonstrates the complete Business Intelligence lifecycle:

- Understanding business requirements
- Data cleaning and transformation
- Dimensional modeling
- DAX calculations
- Interactive dashboard development
- Business insight generation
- Executive-level reporting

---

# 👨‍💻 Author

**Prathik Ramagiri**

Master's Student – Artificial Intelligence for Smart Sensors and Actuators  
Technische Hochschule Deggendorf

📧 LinkedIn: *(Add your LinkedIn profile)*

---

# ⭐ If you found this project useful, consider giving it a star!
