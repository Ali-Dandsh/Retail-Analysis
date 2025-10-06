# Retail Analysis Dashboard using Power BI

## Project Overview

This project is a comprehensive retail analysis dashboard built with Power BI. The goal is to provide insights into sales, customer behavior, and product performance. The dashboard allows users to dynamically filter data and explore trends across different categories, segments, and time periods.

---

## Dashboard Screenshots

Here's a look at the different pages of the dashboard:

**1. Home Page** - A summary of the most important Key Performance Indicators (KPIs).

**2. Orders Overview** - A deep dive into order trends, shipping modes, and sales vs. profit over time.

**3. Products Overview** - Analysis of product performance, sales by category, and top-selling items.

**4. Customers Overview** - Insights into customer segments, geographic distribution, and top customers by sales.

---

## Data Model

The project follows a star schema, which is a best practice for Power BI data modeling. This optimizes performance and simplifies DAX calculations by connecting a central fact table (`FactOrder`) to multiple dimension tables (`DimProduct`, `DimCustomer`, `DimLocation`, `DimDate`).

---

## Key Features & Insights

* **KPIs:** The dashboard tracks key metrics such as Total Sales ($2.30M), Total Profit ($286K), Number of Customers (793), and Total Quantity Sold (38K).
* **Time Series Analysis:** Users can analyze sales and order trends over time by year, quarter, and month.
* **Geographical Analysis:** Interactive maps showcase sales performance across different states and regions.
* **Customer Segmentation:** The dashboard breaks down performance by customer segments (Consumer, Corporate, Home Office).
* **Product Performance:** Identifies top-selling products, categories, and sub-categories to inform inventory and marketing decisions.

## Tools Used

* **Microsoft Power BI:** Used for data modeling, creating DAX measures, and designing the interactive dashboard.
* **Power Query:** Used for data cleaning, transformation, and preparation (ETL processes).
