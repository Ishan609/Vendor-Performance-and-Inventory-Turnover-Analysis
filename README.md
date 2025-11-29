# Vendor-Performance-and-Inventory-Turnover-Analysis
A complete end-to-end data analytics project focused on understanding vendor profitability, inventory movement, pricing inefficiencies, bulk purchasing advantages, and supply-chain risk. This project combines Python, SQL, ETL automation, and statistical analysis to derive actionable business insights.

#🎯 Business Problem

Retail businesses often depend on a few high-performing vendors while simultaneously carrying slow-moving inventory that locks up capital. This project explores:

-Which vendors deliver consistent value
-Which inventory is draining cash flow
-How pricing strategy impacts sales
-Whether bulk purchases actually reduce cost
-Whether vendor margin differences are statistically significant

# 🔍 Project Overview

An analytical deep dive into vendor performance, inventory turnover, bulk purchase cost savings, and profit margin patterns, supported by advanced SQL, Python analytics, and hypothesis testing.

The study examines 200+ brands and multiple vendor streams to uncover critical patterns influencing profitability.

# 🛠 Tech Stack

Programming: Python (Pandas, NumPy, SciPy)
Database: MS SQL Server
ETL: SQLAlchemy, pyodbc
Visualization: Power BI / Matplotlib
Other Tools: Excel, Jupyter Notebook

# 🧹 1. Data Cleaning & Preprocessing (Python)

-Standardized types and fixed inconsistencies
-Cleaned missing values across pricing & quantity fields
-Normalized cost and margin structures
-Applied business validation rules
-Prepared structured datasets for SQL analysis

# 🔄 2. Automated ETL Pipeline

A reusable ETL pipeline was built to:
-Load cleaned data from Python into MS SQL Server
-Maintain consistency across multiple relational tables
-Support quick refresh for new sales & purchase transactions
-Tech: SQLAlchemy + pyodbc

# 📊 3. SQL-Based Vendor & Inventory Analysis

Major findings from SQL aggregations, joins, and window functions:

# ✅ Vendor Contribution

-Top 10 vendors contribute 65.69% of total purchases → high dependency risk
-Remaining vendors account for only ~34%

# ✅ High-Margin but Low-Sales Brands

-198 brands with low sales but high profit margins
-Ideal candidates for promotions & price optimization

# ✅ Inventory Turnover

-$2.71M in slow-moving or unsold inventory
-Significant capital blockage and storage cost strain

# 💰 4. Bulk Purchasing Cost Analysis

-Vendors purchasing in bulk enjoy 72% lower unit costs
-Larger orders → higher profitability
-Strong optimization potential through negotiated tiered pricing

# 📉 5. Profit Margin Statistical Analysis

Using SciPy:

-Top Vendors Mean Margin: 31.17%
-Low Performing Vendors Mean Margin: 41.55%
-95% Confidence Intervals calculated

Hypothesis Test Result:
Null hypothesis rejected → vendor groups differ significantly

This confirms the need for differentiated pricing and discounting strategies.

# 📦 6. Inventory Turnover Insights

-Identified brands/vendors with very low turnover
-Highlighted categories responsible for majority of dead stock
-Suggested stock correction, clearance strategies, and purchasing adjustments

# 📈 Business Recommendations
•	Re-evaluate pricing for low-sales, highly margins brands to boost sales volume without sacrificing profitability.
•	Diversify vendor partnership to reduce dependency on few suppliers and mitigate supply chain risks.
•	Leverage bulk purchasing advantages to maintain competitive pricing while optimizing inventory management.
•	Optimize slow-moving inventory by adjusting purchase quantities, launching clearance sales, or revising storage strategies.
•	Enhance marketing and distribution strategies for low performing vendors to drive higher sales volumes without compromising profit margins.
•	By implementing these recommendations, the company can achieve sustainable, profitability, mitigate risks and enhance overall operational efficiency.


# 📉 Quantified Impact

-Potential recovery of $2.71M in locked inventory capital
-15–25% profit improvement through pricing corrections
-72% cost savings via optimized bulk purchasing
-65% lower risk exposure by vendor diversification
