# 🛒 E-Commerce Sales & Customer Analytics Dashboard

## 📊 Project Overview

This project is an **E-Commerce Data Analysis and Business Intelligence dashboard** developed using **Microsoft Power BI**.

The objective of this project is to analyze e-commerce sales, customers, products, orders, payments, and customer retention patterns and transform the data into meaningful business insights through interactive dashboards.

The dashboard provides a comprehensive view of business performance and helps identify **sales trends, high-performing products, valuable customers, customer segments, payment patterns, order status, cancellation trends, and retention behavior**.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall e-commerce sales performance.
- Identify monthly and yearly revenue trends.
- Analyze sales performance by product and category.
- Identify top-performing and low-performing products.
- Analyze customer segments and customer value.
- Identify top customers based on revenue.
- Analyze repeat customer behavior.
- Analyze orders and payment methods.
- Identify cancellation patterns.
- Analyze pending and completed orders.
- Understand product stock status.
- Analyze revenue across different cities.
- Provide an interactive dashboard for business decision-making.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Power BI** | Data visualization and dashboard development |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures, calculated metrics and business analysis |
| **Data Modeling** | Creating relationships between tables |
| **Excel / CSV** | Data source and data preparation |

---

## 🗂️ Data Model

The Power BI data model contains the following major tables:

- **Customers** – Customer information and customer attributes.
- **Orders** – Order-level information and order status.
- **Order Items** – Individual items associated with orders.
- **Products** – Product, category, price and inventory information.
- **Dim_Date** – Date dimension used for time-based analysis.

The tables are connected using relationships to create an integrated analytical model.

---

## 📑 Dashboard Pages

The Power BI report contains the following pages:

### 1. 📌 Executive Summary

Provides a high-level overview of the overall business performance.

Key analysis includes:

- Overall revenue performance
- Sales trends
- Revenue by category
- Revenue by city
- Top products
- Key business KPIs

---

### 2. 📈 Sales Performance

Focuses on detailed sales performance analysis.

Key visualizations include:

- Monthly Revenue Trend
- Revenue by Category
- Top 10 Products by Revenue
- Revenue by City
- Sales performance trends

This page helps understand how revenue changes over time and which products, categories and locations contribute most to sales.

---

### 3. 👥 Customer Analytics

Provides insights into customer acquisition and customer behavior.

Key analysis includes:

- New Customers by Month
- Customer Segments
- Top 10 Customers by Revenue
- Customer contribution to overall revenue

This helps identify valuable customers and understand the customer base.

---

### 4. 🏷️ Product & Category

Analyzes product and category performance.

Key visualizations include:

- Revenue by Category
- Price vs Units Sold
- Top 5 Products by Revenue
- Bottom 5 Products by Revenue
- Stock Status by Category

This page helps identify products that generate high revenue as well as products that may require further attention.

---

### 5. 📦 Orders & Payment

Provides an overview of order and payment behavior.

Key analysis includes:

- Revenue Trend
- Order Status Mix
- Revenue by Payment Method
- Cancellation Rate by Payment Method
- Cancelled Value % by Category
- Pending Orders
- Pending Orders Detail

This page helps understand order fulfillment, payment preferences and cancellation behavior.

---

### 6. 🔄 Customer Value & Retention

Focuses on customer value and retention-related metrics.

Key analysis includes:

- Revenue by Customer Segment
- Repeat Rate by City
- Customer retention behavior
- Customer value analysis

This helps identify locations and customer segments with stronger repeat-purchase behavior.

---

### 7. 👤 Customer Detail

An interactive **drill-through page** that provides detailed information for an individual customer.

Users can navigate from customer-level visualizations to a detailed customer view for deeper analysis.

---

## 📊 Key Business Questions

This dashboard is designed to answer questions such as:

1. What is the overall revenue performance?
2. How does revenue change over time?
3. Which categories generate the most revenue?
4. Which products are the top revenue contributors?
5. Which products have relatively low revenue?
6. Which cities generate the highest revenue?
7. Who are the highest-value customers?
8. How many new customers are acquired each month?
9. Which customer segments generate the most revenue?
10. What is the repeat customer rate across cities?
11. Which payment methods generate the most revenue?
12. Which payment methods have higher cancellation rates?
13. Which categories have the highest cancelled order value?
14. How many orders are currently pending?
15. What is the stock status across different categories?

---

## 📈 Dashboard Features

### Interactive Filtering

The dashboard allows users to interact with the report using filters and slicers to analyze specific portions of the data.

### Drill-Through Analysis

The **Customer Detail** page provides drill-through functionality, allowing users to move from an overall customer analysis to an individual customer's detailed information.

### KPI Analysis

Important business metrics are presented through KPI cards and visualizations to provide a quick understanding of business performance.

### Time-Based Analysis

The `Dim_Date` table enables analysis of sales and customer activity across different time periods.

### Comparative Analysis

The dashboard compares:

- Products
- Categories
- Cities
- Customer segments
- Payment methods
- Order statuses

---

## 🔍 Major Analysis Areas

The project focuses on five major analytical areas:

### Sales Analysis
Understanding revenue trends, category performance, product performance and geographic sales.

### Customer Analysis
Understanding customer acquisition, segmentation and customer contribution to revenue.

### Product Analysis
Identifying high-performing and low-performing products and analyzing product demand.

### Order & Payment Analysis
Understanding order status, pending orders, payment methods and cancellations.

### Customer Retention Analysis
Analyzing repeat purchase behavior and customer value across different segments and cities.

---

## 💡 Business Insights

The dashboard can help businesses:

- Identify high-revenue products and categories.
- Recognize valuable customers.
- Understand customer purchasing behavior.
- Identify cities with strong customer retention.
- Monitor pending and cancelled orders.
- Understand payment preferences.
- Detect categories with high cancellation value.
- Improve inventory and product management.
- Support data-driven sales and marketing decisions.

---

## 🧩 Project Workflow

```text
Raw E-Commerce Data
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
DAX Measures & Calculations
        ↓
Exploratory Analysis
        ↓
Interactive Power BI Dashboard
        ↓
Business Insights
```

---

## 📁 Project Structure

```text
E-Commerce-Analysis/
│
├── README.md
├── E-Commerce_Analysis.pbix
│
├── data/
│   └── ecommerce_data.csv
│
├── screenshots/
│   ├── executive-summary.png
│   ├── sales-performance.png
│   ├── customer-analytics.png
│   ├── product-category.png
│   ├── orders-payment.png
│   └── customer-retention.png
│
└── documentation/
    └── project-report.pdf
```

> **Note:** Update the `data/` and `screenshots/` filenames according to the files you actually upload to GitHub.

---

## 🚀 How to Use the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/E-Commerce-Analysis.git
```

### 2. Open the Power BI File

Open:

```text
E-Commerce_Analysis.pbix
```

using **Microsoft Power BI Desktop**.

### 3. Refresh the Data

If the original dataset is included in the repository, update the data source path if required and refresh the Power BI report.

### 4. Explore the Dashboard

Navigate through the report pages and use the available filters, slicers and drill-through functionality to explore the analysis.

---

## 📌 Project Highlights

- Interactive Power BI dashboard
- Multi-page business intelligence report
- Sales performance analysis
- Customer segmentation
- Product and category analysis
- Order and payment analysis
- Cancellation analysis
- Customer retention analysis
- Geographic sales analysis
- Top and bottom product analysis
- Customer drill-through functionality
- Time-series analysis

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Data Modeling
- Power Query
- DAX
- Data Visualization
- Business Intelligence
- KPI Development
- Customer Analytics
- Sales Analytics
- Dashboard Design
- Business Insight Generation

---

## 📷 Dashboard Preview

Add screenshots of your Power BI dashboard here:

```markdown
![Executive Summary](screenshots/executive-summary.png)

![Sales Performance](screenshots/sales-performance.png)

![Customer Analytics](screenshots/customer-analytics.png)
```

---

## 👨‍💻 Author

**Sairam**

B.Tech Student | Data Analytics & Data Science Enthusiast

### Areas of Interest

- Data Analytics
- Data Science
- Machine Learning
- Generative AI
- Business Intelligence
- Power BI

---

## ⭐ If You Find This Project Useful

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.
