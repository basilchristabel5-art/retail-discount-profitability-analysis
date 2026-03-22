# retail-discount-profitability-analysis

Retail Sales Performance Analysis: Discount Impact on Profitability
This project analyzes retail sales data to understand how discount levels influence revenue, cost, and overall profitability. Using Power BI, interactive dashboards were developed to explore trends across product categories, regions, and discount bands. The goal is to identify discount thresholds where profit begins to decline and support better pricing and business decision‑making.

📂 Project Overview

This analysis answers key business questions:

How do discounts affect revenue and profit?

Which product categories drive the most profit?

How does performance vary across regions?

What discount levels pose a risk to profitability?

What trends exist across time, categories, and customer orders?

The project includes a full dashboard, insights summary, and recommendations.

🧹 Data Overview & Preparation
Dataset includes:

Sales, cost, profit

Product category

Region

Discount

Order date

Order ID

Quantity

Key preparation steps:

Rounded unit_cost to two decimal places for financial accuracy

Checked for duplicates across all columns (none found)

Validated data types and cleaned inconsistencies

Created six core DAX measures:

Total Revenue

Total Cost

Total Profit

Total Quantity

Profit Margin %

Number of Orders

🔍 Key Insights

💰 Profitability;
The business maintains a 25% profit margin, indicating strong cost control and healthy revenue generation.

💻 Category Performance; 
Technology is the top profit driver and should be prioritized for investment and marketing.

Furniture shows weaker profitability and may require margin review.

🌍 Regional Insights;
Revenue varies significantly by region, suggesting opportunities to improve underperforming markets.

📅 Trend Analysis;
Revenue fluctuates over time, indicating possible seasonality or inconsistent demand.

🏷️ Discount Impact

Profit declines sharply as discounts increase.

Discounts above 20% significantly reduce profitability.

The 21–30% discount band generates minimal profit and should be closely monitored.

📊 Dashboard Features
The Power BI dashboard includes:

Executive KPI summary

Revenue, cost, and profit trends

Category performance

Regional revenue map

Discount‑band profitability analysis

Time‑series sales trends

Top‑performing products and regions

💡 Recommendations

Investigate the 21–30% discount band, as it produces minimal profit.

Avoid discounting above 20%, as profitability declines sharply.

Prioritize the Technology category for expansion and marketing.

Review Furniture margins to identify cost or pricing issues.

Analyze underperforming regions to replicate strategies from high‑performing ones.

Use forecasting models to anticipate demand and optimize pricing.

🧭 Limitations & Next Steps

The analysis focuses on historical data only.

No customer demographics or competitor data included.

Regional differences are shown but not explained.

Aggregated data may hide deeper transactional patterns.

Next steps:

Conduct customer segmentation

Investigate regional performance drivers

Build forecasting models

Perform deeper discount‑band analysis

Expand cost analysis for margin optimization

🛠️ Tools & Technologies
Power BI

DAX

Data modeling

Data cleaning and transformation

Interactive dashboard design

📁 Repository Structure
Code            
├── pbix/                     # Power BI file
├── visuals/                  # Dashboard screenshots
├── documentation/            # Project report or notes
└── README.md                 # Project documentation

📬 Contact

Feel free to reach out if you'd like to discuss this project or collaborate on analytics work.
