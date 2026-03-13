📊 E-Commerce Performance Analysis (Power BI)
📋 Project Overview
This project provides a deep-dive analysis of e-commerce operations, focusing on sales trends, customer satisfaction, and logistics efficiency. The dashboard transforms raw transactional data into actionable insights for business stakeholders.

🚀 Key Performance Indicators (KPIs)
The dashboard tracks the following critical metrics to evaluate business health:


💰 Total Sales / Revenue: Tracking overall financial growth and high-performing categories.


📦 Order Volume: Monitoring the total number of orders processed over time.


⭐ Customer Satisfaction: Analyzing feedback and ratings to improve service quality.


🚚 Delivery Performance: Measuring shipping efficiency and logistics speed.


⚡ Filter Efficiency: Utilizing dynamic slicers to drill down into specific regions or timeframes.

🏗️ The Data Model (Relationships)
The project uses a Star Schema to connect data efficiently:

Fact Table: Sales_Data (contains all transaction amounts and dates).

Dimension Tables: * Customers (Demographics and IDs).

Products (Categories and Pricing).

Geography (Location data).

Calendar (Date logic for Year-over-Year comparisons).

Relationship: All Dimension tables connect to the Fact table via a One-to-Many (1:*) relationship..
