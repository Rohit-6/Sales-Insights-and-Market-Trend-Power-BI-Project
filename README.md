
# Sales Insights and Market Trend Analysis - Power BI Project
## 🔎 Overview

This project involves the creation of an interactive Power BI dashboard to analyze and visualize sales performance and market trends for an online retail store. The primary objective is to provide senior management with insights into business performance, key strengths, and opportunities for growth.
The dataset used in this project is composed of sales transactions, market information, customer data, and product details. The dashboard is designed to simplify complex data into meaningful insights, aiding in decision-making processes such as revenue optimization and market expansion.






## 🔑Key features of Dashboard

1.Revenue and Sales Overview:
  -Total revenue and sales quantity are highlighted as KPIs for a quick snapshot of performance.

2.Market Insights:  
  -Total sales and revenue by markets are visualized using bar charts to showcase the performance of different geographical regions.

3.Revenue Trends:
  -A time-series line chart highlights the revenue trends over the years, providing insights into seasonal and long-term performance.

4.Top Customers and Products:
  -Pie and donut charts display revenue contribution by the top 5 customers.
  -A bar chart provides insights into the top 5 performing products, segmented by increase or decrease in sales.

5.Customer Revenue Breakdown:
  -A detailed pie chart depicts the revenue contribution of various customer types, emphasizing customer diversity and revenue distribution.

6.Filters for Interactive Analysis:
  -Yearly filters enable users to drill down into specific periods for more granular insights.
## 🛠 Tools and Technologies used
- *Power BI*: For data visualization and dashboard creation.
 - *Data Modeling*: Efficient relationships between tables for seamless interaction.
 - *DAX (Data Analysis Expressions)*: To create calculated measures and KPIs.
 - *SQL/Excel*: Data preprocessing and cleaning before importing into Power BI.


## 📊Data Model
The data model used in Power BI integrates multiple tables, including:
- Sales Transactions: Contains information about sales amounts, order dates, product codes, and market codes.
- Sales Markets: Provides market names and zones.
- Sales Products: Contains product details such as codes and types.
- Sales Customers: Includes customer names, codes, and types.
- Sales Date: A date dimension table for time-based analysis.
- Base Measures: Stores calculated metrics for the dashboard.

Relationships: The tables are linked using key fields such as customer_code, market_code, product_code, and date. The data model ensures efficient querying and visualization.


## 📈Insights and Outcomes
1.Market Performance:
  - Delhi NCR is the top-performing market, generating the highest revenue.
  - Mumbai and Ahmedabad follow as key contributors.
2.Customer Contribution:
  - "Electricalsara Stores" and "Electricalytical" are the top revenue-generating customers.
3.Product Performance:
  - Product code "Prod040" contributes significantly to overall sales.
4.Revenue Trends:
  - Revenue has seasonal fluctuations, with peaks in mid-2018 and early 2019.


## ❓How to Use This Repository

Clone the repository:

```bash
  https://github.com/Rohit-6/sales-insights-powerbi.git
```
Open the Power BI file:
  - Download and open the .pbix file using Power BI Desktop.
Explore the Dashboard:
  - Interact with various filters and visuals to gain insights.

