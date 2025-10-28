📊 Project Title

Sales Performance and Profitability Dashboard

📝 Short Description / Purpose

This Power BI dashboard was designed to help the business track sales performance, profitability, and regional trends.
It combines transaction data with client information to provide a complete view of how different products and customer types contribute to revenue and profit.
The dashboard enables stakeholders to identify low-profit regions, high-performing product categories, and make data-driven marketing and pricing decisions.

🧰 Tech Stack

Power BI – Data modeling, visualization, and dashboard design

Excel / CSV Files – Data source and initial data cleaning

Power Query – Data transformation and calculated columns

DAX (Data Analysis Expressions) – Custom measures and KPIs

Conditional Formatting – To highlight key financial insights

💾 Data Source

The dataset includes two main tables:

Transactions Table – Contains fields like Transaction Date, Item Name, Units Sold, Revenue, Discount Amount, and Net Profit.

Clients Table – Includes Client ID, Client Type, and Region.

These tables are connected using Client_ID in a one-to-many relationship, enabling client-level analysis.

✨ Feature Highlights
🔹 Key KPIs

Total Revenue

Total Units Sold

Total Net Profit

Average Discount Amount

Current Month Summary

🔹 Interactive Filters (Slicers)

Date

Client Type

Region

These slicers allow users to dynamically filter and explore specific time periods, customer types, or regional data.

🔹 Visuals

Pie Chart – Revenue by Product Category

Electronics lead with 34.88% of total revenue.

Map Visualization – Revenue by Region

East Region contributes ~16.94K revenue and 7.48K profit, showing strong market presence.

Larger bubbles represent higher revenue.

Bar Chart – Top 5 Best-Selling Items

Monitor – Highest sales

Desk – Second highest sales

Printer – Third highest sales

Detailed Data Table – Transaction-level insights

Columns: Transaction Date, Item Name, Units Sold, Revenue, Discount Amount, Net Profit

Includes conditional formatting to highlight unusually high or low profits or discounts.

📈 Key Insights

The East region leads in total revenue and profit, highlighting a strong sales performance.

Electronics category contributes the most revenue (34.88%).

Discount patterns differ across client types, supporting tailored pricing strategies.

🧩 Data Model Overview

One-to-Many Relationship between Clients (1) and Transactions (Many) using Client_ID.

Enables dynamic filtering by region and client type across all visuals.

🔍 Data Cleaning & Transformation

Converted Transaction_Date to a proper date format for accurate time-based filtering.

Created calculated columns:

Total_Sales = Revenue × Units Sold

Discount_Amount = Revenue × Discount Rate

Removed duplicate Client_IDs and validated relationships.

🧠 Insights & Business Impact

Improved understanding of regional and product-level profitability.

Supported targeted marketing and pricing strategies.

Enabled management to track sales performance in real time.

screenshot
Example: ![dashboard preview](https://github.com/Kritika293/sales-performance-dashboard/blob/main/sales%20performance%20dashboard.png)


Enhance dashboard accessibility with tooltips and drill-through analysis.
https://github.com/Kritika293/sales-performance-dashboard/blob/main/sales%20performance%20dashboard.png
