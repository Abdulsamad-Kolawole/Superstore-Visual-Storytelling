# Superstore Sales Performance Dashboard

## Project Overview

This project analyzes the Superstore dataset using Power BI to transform transactional sales data into meaningful business insights through interactive dashboards and data visualization.

The project demonstrates the use of data modeling, DAX measures, and visual storytelling to support data-driven decision-making.

---

## Business Objective

The objective of this project is to:

- Analyze sales performance across different regions, states, customer segments, and product categories.
- Identify key business trends and profitability drivers.
- Build an interactive dashboard that enables users to explore the data through filters and visualizations.

---

## Dataset

The project uses the Superstore dataset, which contains information on:

- Orders
- Customers
- Products
- Geography
- Sales
- Profit
- Quantity
- Discounts
- Order Dates

The dataset was cleaned before visualization.

---

## Data Modeling

A Star Schema data model was implemented.

### Fact Table

- Orders

### Dimension Tables

- Customers
- Products
- Geography

One-to-many relationships were created between the dimension tables and the Orders table to improve data organization and reporting performance.

<img width="1742" height="932" alt="Superstore Model View" src="https://github.com/user-attachments/assets/4537b5e4-c0d4-470e-bc9b-86b3e434af10" />


---

## DAX Measures

The following measures were created:

- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Profit Margin

---

## Dashboard Preview

<img width="1806" height="1081" alt="Superstore Dashboard" src="https://github.com/user-attachments/assets/29c10507-969a-47d6-bf38-933f8994d433" />


---

## Dashboard Features

The dashboard includes:

- KPI Cards
  - Total Sales
  - Total Profit
  - Total Orders
  - Profit Margin

- Sales by Region
- Profit by Category
- Sales by State
- Sales by Customer Segment
- Sales Trend by Year

Interactive slicers allow users to filter the report by:

- Category
- Customer Segment
- Year

---

## Key Insights

- The West region generated the highest sales.
- Technology was the most profitable product category.
- The Consumer segment contributed the highest sales.
- California recorded the highest sales among all states.
- Sales showed a steady upward trend from 2015 to 2017.
- Overall profit margin was approximately 12.47%.

---

## Business Recommendations

- Continue investing in Technology products due to their high profitability.
- Develop strategies to improve profitability within the Furniture category.
- Replicate successful sales practices from the West region in lower-performing regions.
- Continue targeting the Consumer segment through marketing and customer retention initiatives.

---

## Tools Used

- Power BI
- DAX
- Power Query

---

## Files Included

- Superstore Sales Dashboard.pbix
- Superstore Dataset.csv
- README.md
- Dashboard Screenshot
- Data Model Screenshot

---

## Author

**Abdulsamad Kolawole**
