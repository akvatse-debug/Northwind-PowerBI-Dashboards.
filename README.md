# 📊 Northwind Sales Data — Power BI Dashboard

## Project Overview
An end-to-end business intelligence dashboard built on the classic **Northwind Sales dataset**, analyzing revenue performance, product profitability, customer behavior, and churn risk. The project goes beyond visualization — it delivers structured business insights and actionable recommendations directly within the report.

**Dataset:** Northwind (orders, products, customers, employees, categories, shippers)  
**Tool:** Microsoft Power BI Desktop  
**Pages:** 4 (Executive Overview | Product Performance | Churn Analysis | Insights & Recommendations)

---

## Dashboard Pages

### 1. 🏢 Executive Overview
A high-level summary for leadership with KPI cards, trend lines, and geographic breakdown.
- Total Revenue: **1.27M** | YoY Growth: **179.31%**
- Total Orders: **830** | Total Customers: **91**
- Revenue trend line with target benchmark
- Revenue breakdown by Category, Top 5 Products, Employees, Shippers
- Revenue by Country (Map visual)
- Customer health snapshot: Active customers, Churn rate, Repeat customer rate

### 2. 📦 Product Performance Analysis
Deep dive into product-level profitability and positioning.
- 77 products analyzed across revenue, quantity, discount, and YoY growth
- Product contribution % ranking
- Revenue by Price Flag (High / Medium / Low)
- Active vs Discontinued product revenue comparison
- Volume vs Value scatter plot for product positioning
- Detailed product table with Revenue, YoY%, Contribution%, Quantity, Discount

### 3. 👥 Customer Churn Analysis
Retention and churn metrics tracked over time.
- Active Customers: **73** | Churned: **18** | Churn Rate: **19.78%**
- Retention Rate: **80.22%** | Repeat Customer Rate: **96.70%**
- Monthly churn rate trend (peaked ~20% in Apr–May, stabilized at 3–5% post-June)
- Churn revenue lost by Product, Country, and Category

### 4. 💡 Insights & Recommendations
A dedicated insights page summarizing findings and prescriptive actions — built entirely within Power BI.

**Key Insights:**
- Revenue highly concentrated in top-performing products → dependency risk
- Majority of churn concentrated in Q2 → seasonal retention failure
- High-priced products drive largest revenue share; low/medium underperform
- Discontinued products still contributing ~185K → delayed phase-out impact

**Recommendations:**
- Launch targeted retention campaigns before Q2
- Promote mid-tier products to reduce revenue concentration risk
- Apply Pareto 80/20 rule to focus on high-value customers
- Set up monthly churn monitoring alerts

---

## Data Model & DAX Highlights

**Tables:** orders, order_details, products, customers, employees, categories, shippers, Date table

**Measure Groups Built:**
| Group | Key Measures |
|---|---|
| Category Analysis | Revenue by category, Category YoY%, Category contribution% |
| Churn Analysis | Churn rate, Churned customers, Active customer revenue, Cohort retention |
| Orders Analysis | Total orders, Avg order per customer, Order YoY% |
| Product Analysis | Product contribution%, Revenue by price flag, Active vs discontinued revenue |
| Growth Measures | Monthly Revenue growth, Monthly Quantity growth, Customer YoY% |

**DAX Concepts Used:** CALCULATE, FILTER, DATEADD, DIVIDE, IF, SWITCH, SUMX, COUNTROWS, DISTINCTCOUNT, time intelligence functions

---

## Tools & Features Used
- **Power Query** — Data transformation and cleaning
- **Data Modeling** — Star schema with relationships across 8 tables
- **DAX** — 30+ custom measures across 5 measure tables
- **Visualizations** — KPI cards, line charts, bar charts, scatter plot, map, donut chart, matrix table
- **Slicers** — Year, Month, Country, Product, Category filters on all pages

---

## Certification
Built as part of the **Microsoft Power BI Desktop for Business Intelligence** course by **Maven Analytics** on Udemy (Feb 2026).

---

## Author
**Akash Kumar Vatse**  
📧 ak.vatse@gmail.com  
📍 Lucknow, Uttar Pradesh
