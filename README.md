# Customer Behavior Dashboard

Power BI dashboard analyzing customer shopping behavior using SQL and data visualization.

---

## 📊 Dashboard Preview

![Dashboard](images/dashboard_preview.png)

---

## 📌 Project Overview

This project analyzes customer shopping behavior to identify patterns in purchasing habits, customer demographics, and product category performance.

The dashboard provides insights into:

- Customer subscription behavior
- Revenue by product category
- Sales distribution
- Customer age group purchasing trends
- Average purchase amount
- Average review ratings

---

## 🛠 Tools & Technologies

- **Power BI** – Data visualization and dashboard creation
- **SQL (MySQL)** – Data querying and database management
- **Excel / CSV** – Dataset storage
- **GitHub** – Project version control

---

## 📂 Project Structure

customer-behavior-dashboard
│
├── data
│ └── customer_shopping_behavior.csv
│
├── sql
│ └── database_setup.sql
│
├── powerbi
│ └── customer_behavior_dashboard.pbix
│
├── images
│ └── dashboard_preview.png
│
└── README.md

---

## 📈 Key Dashboard Metrics

| Metric | Value |
|------|------|
| Total Customers | 3,900 |
| Average Review Rating | 3.75 |
| Average Purchase Amount | $59.76 |

---

## 📊 Dashboard Insights

### 1️⃣ Category Performance
- Clothing generates the highest revenue.
- Accessories follow as the second highest category.

### 2️⃣ Customer Age Groups
- Young adults generate the most revenue.
- Middle-aged customers contribute significantly to sales.

### 3️⃣ Subscription Behavior
- 73% of customers are non-subscribers.
- 27% have active subscriptions.

---

## 🗄 Database Setup

Run the SQL script to create the database:

```sql
create database startersql;
use startersql;

sql/database_setup.sql
