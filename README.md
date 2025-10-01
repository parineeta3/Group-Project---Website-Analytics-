📊 Website Analytics & Conversion Rate Optimization

📌 Project Overview

This project simulates the role of a Web Analytics Consulting Team hired by ClickWave, an e-commerce company facing high traffic but low conversions. The objective is to analyze user behavior, funnel performance, and revenue generation using session-level data and recommend strategies to improve conversions.

🗂️ Datasets Used

Events – user interactions with items (e.g., add_to_cart, purchase).

user_id, ga_session_id, country, device, type, item_id, date

Users – lifetime value and metadata of users.

id, ltv, date

Items – product details and pricing.

id, name, brand, variant, category, price_in_usd

Sessions – session-level details.

ga_session_id, user_id, country, device, session_start, session_end, events_count, add_to_cart_count, begin_checkout_count, purchase_count, converted, session_duration_seconds, session_revenue

🛠️ Tools & Technologies

SQL (MySQL / BigQuery) → Data cleaning, segmentation, funnel queries.

Python (Pandas, Matplotlib, Seaborn) → EDA, funnel analysis, visualizations.

Power BI → Interactive dashboards for funnels, drop-offs, and revenue.

Excel → Data preprocessing, validation, and pivot summaries.

🔎 Methodology

Data Collection – Imported raw data into SQL databases.

Data Cleaning – Removed duplicates, handled missing values, standardized formats.

Analysis – Used SQL, Python, and Excel for funnel, segmentation, and revenue analysis.

Visualization – Built interactive Power BI dashboards and Python visualizations.

Insights & Recommendations – Derived actionable strategies for UX and marketing improvements.

📈 Key Insights

Funnel Analysis: Major user drop-offs occur between Add-to-Cart → Checkout, signaling checkout friction.

Device Performance: Desktop users convert better, while mobile has higher traffic but higher bounce rates.

Revenue Analysis: Top 10 items drive the majority of revenue, useful for inventory & promotions.

User Segmentation: High-value users (higher LTV) have longer sessions and purchase more frequently.

Traffic Sources: Social and referral traffic show engagement but low purchase intent.

📊 Dashboards & Visuals

Funnel Chart (Power BI, Python) → Highlights user drop-offs across stages.

Top Items by Revenue (Python, Power BI) → Identifies top-performing products.

Conversion Rate by Device (Python, Power BI) → Device-level performance insights.

Excel Pivot Summaries → Verified funnel and session stats.

📌 Deliverables

SQL Queries (/sql/queries.sql)

Python Notebooks (/python/analysis.ipynb)

Power BI Dashboard (/powerbi/dashboard.pbix)

Excel Summary File (/excel/analysis.xlsx)

Final Report (/report/final_report.pdf)

👥 Team Roles

SQL Analyst – Database design, segmentation queries.

Power BI Developer – Dashboards & funnel visualization.

Excel Analyst – Data preprocessing, pivot analysis.

Python Analyst – Funnel stats, drop-off analysis, revenue insights.

Report Manager – Compiled insights, prepared final documentation.

📚 Learning Outcomes

Hands-on experience with website traffic analytics.

Building and interpreting conversion funnels.

User segmentation using SQL & Python.

Designing BI dashboards for decision-making.

Crafting data-backed UX and marketing recommendations.

🚀 How to Run the Project

Clone this repository.

Import datasets into SQL or your analytics tool of choice.

Run SQL scripts for segmentation and funnel queries.

Open Python notebooks for exploratory analysis and visualization.

Load the Power BI dashboard file to explore interactive insights.

Refer to the Final Report for summarized findings and recommendations.

✨ This project demonstrates real-world problem solving in digital analytics, combining technical tools with business strategy.
