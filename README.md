# E-Commerce_Sales_Analysis
# 🛒 E-Commerce Sales Analysis Dashboard | Power BI

## 📌 Project Overview

The **E-Commerce Sales Analysis Dashboard** is an interactive business intelligence project built using Microsoft Power BI to analyze sales performance, profitability, product categories, customer locations, and payment methods.

The objective of this project is to transform raw sales data into meaningful business insights through data modeling, KPI analysis, and interactive visualizations, helping stakeholders understand performance and make data-driven decisions.

## 🎯 Business Objectives

* Analyze overall sales and profit performance.
* Track sales quantity and average order value.
* Identify profitable and loss-making product subcategories.
* Understand sales distribution across payment methods.
* Explore sales performance across states and cities.
* Analyze quarterly and monthly trends to support business decisions.

## 🛠️ Tools & Technologies

* **Microsoft Power BI Desktop** — Dashboard development and visualization
* **Power Query** — Data inspection, cleaning, and transformation
* **DAX (Data Analysis Expressions)** — Measures and KPI calculations
* **CSV datasets** — Source data for orders and sales details

## 📂 Dataset Description

The project uses two CSV files:

### 1. `Orders.csv`

Contains order-level information, including:

* Order ID
* Order date
* Customer name
* State
* City

### 2. `Details.csv`

Contains sales transaction details, including:

* Order ID
* Amount
* Profit
* Quantity
* Category
* Sub-category
* Payment mode

The two datasets are connected using **Order ID** to enable combined analysis of sales and order information.

## 📊 Key Performance Indicators (KPIs)

The dashboard tracks key metrics such as:

* **Total Sales** — Total sales amount recorded in the dataset.
* **Total Profit** — Total profit generated across transactions.
* **Total Quantity** — Total units sold.
* **Average Order Value (AOV)** — Total sales divided by the number of distinct orders.
* **Profit Margin** — Total profit divided by total sales, expressed as a percentage.

## 📈 Dashboard Features

* Interactive KPI cards for monitoring overall performance.
* Profit analysis by subcategory.
* Quantity analysis by product category.
* Sales and profit analysis by payment method.
* Geographic analysis by state and city.
* Date and quarter filtering for exploring different reporting periods.
* Interactive visuals that allow users to investigate performance across business dimensions.

## 🔍 Key Insights

The following findings were calculated from the complete source datasets:

* **Total sales:** ₹437,771
* **Total profit:** ₹36,963
* **Total quantity sold:** 5,615
* **Distinct orders:** 500
* **Average order value:** ₹875.54
* **Overall profit margin:** 8.44%

Additional observations:

* Clothing generated the highest total profit among the three main product categories.
* Printers was the highest-profit subcategory in the dataset.
* Electronic Games and some other subcategories recorded negative profit, highlighting areas for further investigation.
* Cash on Delivery (COD) accounted for the largest sales amount among the payment methods.

*Note: These figures represent calculations from the complete CSV datasets. Dashboard values may differ when filters are applied.*

## 💡 Business Recommendations

Based on the analysis, a business could:

1. Investigate loss-making subcategories to understand pricing, costs, discounts, or operational issues.
2. Review high-performing categories to identify opportunities for growth.
3. Monitor monthly sales and profit trends to understand changes in performance.
4. Evaluate payment-method trends to improve customer convenience and payment operations.
5. Use state- and city-level analysis to identify regional opportunities.

These recommendations should be validated against additional business context before making operational decisions.

## 🧠 Skills Demonstrated

* Data analysis and data validation
* Data cleaning and transformation
* Data modeling and table relationships
* DAX measure creation
* KPI development
* Interactive dashboard design
* Business insight generation
* Data storytelling and visualization

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. If prompted, update the source paths for `Orders.csv` and `Details.csv`.
4. Refresh the data.
5. Clear the report filters to view the full dataset.
6. Use the slicers and visuals to explore sales performance.

## 📁 Repository Structure

```text
E-Commerce-Sales-Dashboard/
│
├── E commerce Sales Dashboard.pbix
├── Orders.csv
├── Details.csv
└── README.md
```

## 👨‍💻 Project Purpose

This project demonstrates practical application of business intelligence concepts to an e-commerce sales dataset, combining data modeling, KPI analysis, and interactive reporting to support business decision-making.

---

**Built with:** Microsoft Power BI | Power Query | DAX

**Project Category:** Data Analytics / Business Intelligence
