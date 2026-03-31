# Bright-Coffee-Shop-Sales-Analysis
Using historical transactional data from Bright Coffee Shop to uncover actionable business insights for a newly appointed CEO Using SQL and Microsoft Excel, to get key metrics to support strategic decision-making.

📊 Overview & Aim
This analysis provides a comprehensive review of transactional data from January to June 2023
.As the Junior Data Analyst, the mission is to assist the new CEO in growing company revenue and improving product performance by extracting actionable insights from historical data

🔍 Methodology (The "How")
To ensure data integrity, the following technical steps were taken based on the project plan:
Data Ingestion: Raw CSV data was loaded into Databricks for high-performance SQL processing
.
ETL Pipeline:
Corrected unit_price formatting (converting commas to decimals)
.
Computed total_amount as unit_price * transaction_qty
.
Created "Logic Buckets" for Time (30-minute/3-hour intervals), Spend (Low to Very High), and Day Classification (Weekend vs. Weekday)
.
Analysis: Processed data was exported to Google Sheets/Excel to build pivot tables and visual dashboards
.

--------------------------------------------------------------------------------
- Key Insights (Data-Backed)
- Robust Growth Trend: Your analysis confirms a strong upward trajectory in monthly revenue, nearly doubling from January to June
.
- Morning Dominance: Using the time_buckets column
, the data reveals the "Morning" period is the primary revenue driver, peaking during the 06:00–11:59 window
.
- Product Leadership: Pivot tables showing Revenue per Product Category
 identify Coffee and Tea as the dominant leaders, accounting for more than 60% of total revenue.
- Underperforming Products: Detailed analysis of product_detail
 identifies Loose Tea, Flavors, and Packaged Chocolate as the lowest performers, contributing minimally to monthly totals
.
- Store Performance: Analysis of store_location
 shows Hell's Kitchen as the top-performing branch (~33.8% of revenue), followed closely by Astoria and Lower Manhattan
.
-Spend Segment: The spend_bucket column
 confirms that the "Budget" and "Low Spend" segments drive the highest transaction volume, accounting for the vast majority of customer traffic
.

--------------------------------------------------------------------------------
🎯 Strategic Recommendations
Based on these insights, the following strategies are proposed to the CEO
:
Capitalize on Core Strengths: Launch targeted marketing campaigns during peak Morning hours and prioritize stock for top-tier Coffee and Tea products
.
Strategic Bundling: Create "Combo Deals" that pair high-volume items (Coffee) with slower-moving products (Packaged Chocolate) to increase the average transaction value
.
Optimize Underperformers: Systematically address low-revenue items like Loose Tea through "Happy Hour" promotions or consider phasing them out if performance does not improve
.
Enhance Experience: Invest in staff training for upselling and explore a mobile ordering app to handle the high-volume morning rush more efficiently
.
Future Automation: Implement automated daily sales reporting and track performance across new locations to ensure data-driven scaling
.
