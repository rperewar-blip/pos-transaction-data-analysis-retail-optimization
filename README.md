Project Overview

This project analyzes over 500,000 retail Point of Sale (POS) transactions to extract actionable business insights that improve decision-making, operational efficiency, and profitability.

The objective is to transform raw transaction data into strategic business recommendations using customer segmentation, time-series analysis, and operational analytics.

🎯 Business Problem

Retail businesses generate large volumes of transaction data daily. However, without proper analysis, important patterns remain hidden, leading to:

Inefficient inventory management

Poor staffing decisions

Missed revenue opportunities

Lack of customer targeting strategy

This project demonstrates how POS data analytics can solve these challenges.

📂 Dataset Description

The dataset contains:

500,000+ transaction records

3,164 unique customers

Transaction-level data including:

Invoice number

Product ID and description

Quantity

Unit price

Customer ID

Country

Transaction timestamp

🧮 Engineered Features:

Revenue = Quantity × Unit Price

Hour of transaction

Month and Year

🧹 Data Cleaning Process

To ensure data quality:

Removed transactions where Quantity ≤ 0

Removed transactions where UnitPrice ≤ 0

Converted InvoiceDate to datetime format

Removed duplicates and invalid records

Created derived revenue and time-based features

📈 Methodology

The following analytical techniques were applied:

1️⃣ Time-Series Analysis

Monthly revenue trend identification

Seasonal pattern detection

2️⃣ Customer Segmentation

Customers classified into:

High Value

Medium Value

Low Value
Based on total revenue contribution.

3️⃣ Product Performance Analysis

Ranking products by total revenue

4️⃣ Country-Wise Revenue Analysis

Identifying geographic revenue concentration

5️⃣ Hourly Sales Analysis

Identifying peak business hours

Operational optimization insights

🔥 Key Insights
📅 Monthly Revenue Trends

Highest Revenue Month: July (~$99,618)

Lowest Revenue Month: December (~$17,329)

Clear seasonal demand pattern identified.

👥 Customer Segmentation

8 High-Value Customers (0.25%) generate 57% of total revenue.

Revenue is highly concentrated among a small customer group.

Confirms Pareto Principle (80/20 rule concept).

⏰ Hourly Sales Pattern

Peak sales hours: 10 AM – 3 PM

Highest revenue hour: 12 PM

Supports workforce scheduling optimization.

🌍 Geographic Revenue Concentration

United Kingdom generates highest revenue (~$9M+).

Strong market concentration in select countries.

🧠 Business Action Plans
📦 Inventory Strategy

Increase inventory by 30–40% before peak months.

Reduce purchases during low-demand periods.

👥 Customer Strategy

Dedicated management for high-value customers.

Personalized campaigns for medium-value customers.

Automated promotions for low-value customers.

🏪 Operational Strategy

Increase staffing during peak hours.

Schedule maintenance during low-traffic periods.

💼 Business Impact

This project demonstrates how retail businesses can:

Improve profitability

Optimize staffing and operations

Enhance customer retention

Make data-driven strategic decisions

🛠 Tools Used

Microsoft Excel (Pivot Tables, Charts)

Data Cleaning & Feature Engineering

Business Analytics Techniques

Statistical & Trend Analysis

📌 Project Outcome

This research proves that POS transaction data can be transformed into actionable intelligence that improves operational efficiency and strategic planning in retail businesses.

👨‍💻 Author

Rishabh Perewar
Master’s Student – Business Analytics
Saint Peter’s University
