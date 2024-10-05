# Sales-Rep-Performance
![](linkedin-sales-solutions-nISqmehpBQk-unsplash.jpg)

## Introduction

This project aims to provide a comprehensive Tableau dashboard for monitoring sales representatives' performance. The dashboard will track key performance indicators (KPIs) such as monthly revenue, revenue quotas, and gross margin percentage. It also aims to visualize the YTD (Year-to-Date) Revenue by Customer, comparing the previous year versus the current year, as well as the YTD Gross Margin % by Customer. The central idea is to give sales reps and leadership an easy-to-use tool for visualizing and analyzing performance trends.

## Problem Statement

Sales teams, especially those operating at scale, often face the challenge of aligning their efforts with strategic objectives like hitting revenue targets and maintaining profitability. Without real-time, accurate performance metrics, both sales representatives and leadership can become disconnected from the business's true state. The absence of such metrics, or reliance on inaccurate ones, can lead to several downsides:

1. Lack of Real-Time Insights.
2. Inability to Track Progress Against Quotas.
3. Misalignment Between Efforts and Results.
4. Lack of Granular Customer Insights.
5. Inconsistent or Poor Goal Setting.
6. Inability to Identify Top Performers and Areas for Improvement.
7. Low Morale and Motivation.

The ultimate goal is to create a dashboard that provides real-time insights:

1. Sales reps view personalized dashboards, seeing only their own performance data.
2. Leadership sees aggregated team data, comparing revenue and margins across reps and customers.

## Skills Demonstrated

**SQL:** Used for querying and transforming raw sales data, including filtering out unnecessary columns, cleaning up missing values, and joining tables to create a structured dataset.

**Tableau:** Utilized to create a dynamic dashboard with interactive visuals. These visuals helped to track KPIs like YTD revenue by customer, gross margin %, and monthly performance trends.

**Excel:** Used to open and explore the dataset for the first time. Initial exploratory analysis was done in Excel to better understand the structure and key aspects of the data before cleaning and transformation in SQL.

**Data Analysis:** Conducted in-depth analysis of key performance indicators (KPIs) such as YTD revenue, gross margin %, and monthly sales trends. This included analyzing performance against quotas and identifying trends to support sales strategy decisions.

## Soft Skills Demonstrated

**Attention to Detail:** Ensured accuracy at every stage of the process, from data cleaning in SQL to carefully designing the Tableau dashboard. Paid close attention to how each metric would be visualized and interpreted.

**Problem-Solving:** I addressed missing or inaccurate data during the cleaning and transformation phases, ensuring the final analysis was based on reliable data. Additionally, I tackled the challenge of creating clear, actionable insights from complex data.

**Critical Thinking:** Applied analytical thinking to determine which KPIs and metrics would be most helpful in tracking sales performance, revenue trends, and sales rep performance. I thought critically about how each visual could provide value to both sales reps and leadership.

**Communication:** Communicated findings through well-structured visuals that are easy to interpret for technical and non-technical stakeholders. The dashboard was designed to tell a straightforward story with the data, aiding decision-makers in their day-to-day operations.

**Time Management:** Efficiently managed the entire data pipeline—from exploration to cleaning, transformation, analysis, and final dashboard creation—within project deadlines.

**Adaptability:** Utilized multiple tools (Excel, SQL, Python, and Tableau) to adapt to the different stages of the data analysis process, ensuring the project ran smoothly from start to finish.

## Data Sourcing

The dataset used in this project was sourced from Kaggle and contains historical sales information, including columns such as:

Sales Value: I treated the total sales for each transaction as the revenue.
Cost: The cost associated with the product sold.
Date, Customer Industry, Sales Channel, Brand, and Sales Rep.

## Data Transformation

The raw data required extensive preprocessing and transformation to ensure consistency and correctness before analysis. SQL was primarily used for data cleaning and transformation, with additional calculated fields created in Tableau for specific metrics. The transformation process involved the following steps:

**Removing Null or Duplicate Entries:** To maintain the integrity of the analysis, SQL queries were used to eliminate rows with missing or duplicate data.

**Data Structuring:** Sales data was segregated by Sales Rep and Customer to enable a more granular analysis. This helped focus the dashboard on individual performance and overall customer revenue trends.

**Gross Margin %:** A calculated field in Tableau to track gross margin as a percentage of total revenue. This key metric helped visualize profitability trends.
Profit: A calculated field to visualize the total profit generated by each sales rep and customer segment.

**YTD Gross Margin %:** Created in Tableau to compare year-to-date gross margin performance across customers and periods. This allowed leadership to track progress against the previous year.

Data was further aggregated to create high-level KPIs, such as Total Revenue and Total Gross Margin.
Segregated by Region and Sales Channel to allow multi-dimensional insights into sales performance across different segments.

## Analysis and Visualization

Using Tableau, the following visualizations were created:

### Monthly Revenue vs. Minimum Expectation Quota:
![](Revenue vs Minimum Expectation Quota.jpg)

This visualization displays Monthly Revenue against the Minimum Expected Quota (set at $250) for all sales reps over a year. It effectively shows how revenue fluctuates month by month and highlights when sales exceed or fall below the set quota. The green line representing the $250 expectation is consistently lower than actual revenue across all months for all sales reps, indicating the sales team consistently surpassed this target.

Overall, revenue remained above the minimum expectation throughout the year, demonstrating solid sales performance.

### Revenue vs. Target Quota
![](Revenue vs Target Quota.jpg)

This second graph showcases a Revenue vs. Target Quota chart for a single sales rep, where the target quota is set at $500. The performance comparison across the months is insightful for understanding trends within the sales data.

Multiple sales reps must catch up to the quota, which suggests issues like seasonal variability, differences in customer demand, or potential internal factors like reps' engagement or resources. This data can propel a strategy revaluation and prompt a deeper dive into identifying common months of underperformance. It may help in understanding whether external factors impact sales or if adjustments in sales strategy and training could improve outcomes.

