# Product Sales Analysis using Tableau
## Problem Statement:
The company is experiencing fluctuating revenue and sales performance across different markets and product lines. While overall revenue and sales quantity are presented, there's a lack of clarity on the underlying factors driving these fluctuations. Specifically, it's unclear:
1. Which markets are contributing most significantly to revenue and sales and why? 
2. What are the key drivers of revenue growth or decline over the years?
3. Which products are performing well and which are lagging?
4. What are the key customer segments and their contribution to revenue? While the "Top 5 Customers" are shown, understanding broader customer segments is missing.
This lack of clarity hinders the company's ability to make informed decisions regarding resource allocation, marketing strategies, and product development to optimize revenue and sales.
## Objective:
1.	Identify the key factors contributing to revenue and sales performance across different markets and product lines. This includes determining which markets and products are performing strongly and weakly.
2.	Understand the trends and patterns in revenue and sales over the years (2017-2020) and identify the potential drivers of these trends.
3.	Determine the contribution of different customer segments to revenue.
4.	Provide actionable insights and recommendations to improve revenue and sales performance by focusing on high-performing areas and addressing underperforming ones.
## Step Followed
Process:
1. Data Acquisition and Storage:
	1.1 Data Source Identification: Identify and document the source(s) of the data, including the format and structure.
	1.2 Data Extraction: Extract the raw data from the identified source(s).
	1.3 Data Ingestion and Storage: Ingest the extracted data into a relational database management system (RDBMS), specifically MySQL, for structured storage and efficient querying.
2. Data Integration and Transformation (ETL):
	2.1 Database Connection Establishment: Establish a secure and reliable connection between MySQL and Tableau for data access.
	2.2 Data Extraction (from MySQL to Tableau): Extract the required tables and fields from the MySQL database into Tableau.
	2.3 Data Cleansing and Preprocessing: Perform data cleansing operations within Tableau, including handling missing values, correcting inconsistencies, and standardizing formats.
	2.4 Data Transformation: Transform the data as needed to facilitate analysis and visualization, such as creating calculated fields, aggregating data, and pivoting tables.
3. Data Visualization and Analysis:
	3.1 Objective-Driven Visualization Design: Develop individual visualizations (charts, graphs, tables) within Tableau based on the specific objectives of the analysis. Each sheet will focus on a distinct aspect of the data (e.g., revenue by market, sales quantity by product).
	3.2 Interactive Dashboard Creation: Combine the individual visualizations into an interactive dashboard, providing a comprehensive overview of the data.
	3.3 Dynamic Filtering and Parameterization: Implement interactive filters and parameters (e.g., year and month selection) within the dashboard to enable dynamic exploration of the data.
	3.4 Insight Generation and Interpretation: Analyze the visualizations to identify trends, patterns, and anomalies, and derive actionable insights related to revenue, sales, customer behavior, and product performance.
## Dashboard
<img width="801" alt="Dashboard Image" src="https://github.com/user-attachments/assets/c2d90edd-b5a6-41b1-829b-e7d70e275b9d" />
## Conclusion:
The analysis of the sales and revenue dashboard reveals significant disparities in performance across different markets, products, and customer segments. ``Delhi NCR emerges as the dominant market, significantly outpacing others in both revenue and sales quantity``, suggesting a strong customer base or effective market penetration in this region. ``Product performance is concentrated, with a few key products (Prod318, Prod218) contributing substantially to overall sales``. While the top five customers contribute a notable portion of the revenue, the overall customer distribution and potential for diversification warrant further investigation. ``Revenue trends over the years (2017-2020) exhibit fluctuations, indicating a need for a deeper understanding of the underlying factors``. The decline in revenue observed in 2020, particularly, requires further scrutiny to identify potential causes (e.g., market changes, economic factors, internal issues).
## Recommendations:
1.	Market-Specific Strategies:
-- Invest in Delhi NCR: Capitalize on the strong performance in Delhi NCR by further investing in marketing, sales, and distribution efforts in this region.
-- Analyze Underperforming Markets: Conduct a thorough analysis of underperforming markets like Bengaluru, Surat, and Lucknow to identify the root causes of low performance (e.g., competition, lack of awareness, logistical challenges). Develop targeted strategies to address these issues.
-- Explore Market Expansion: Investigate the potential for expanding into new markets based on market research and demand analysis.
2.	Product Portfolio Optimization:
-- Focus on Top Performers: Continue to invest in and promote top-performing products (Prod318, Prod218) to maximize their contribution to sales.
-- Analyze Underperforming Products: Analyze the performance of other products and identify opportunities for improvement (e.g., product enhancements, pricing adjustments, targeted marketing campaigns).
-- Product Diversification: Explore opportunities for product diversification to reduce reliance on a few key products and cater to a wider customer base.
3.	Customer Relationship Management:
-- Customer Segmentation: Conduct a detailed customer segmentation analysis to understand the needs and preferences of different customer groups.
-- Customer Retention Strategies: Develop targeted customer retention strategies to build loyalty and increase repeat purchases.
-- Expand Customer Base: Implement strategies to expand the customer base and reduce reliance on a few key customers.
4.	Revenue Growth and Stability:
-- Year-Over-Year Analysis: Conduct a detailed year-over-year analysis to identify the factors driving revenue fluctuations.
-- Develop Revenue Forecasting Models: Develop revenue forecasting models to predict future revenue and identify potential risks and opportunities.
-- Implement Proactive Measures: Implement proactive measures to mitigate risks and capitalize on opportunities to ensure consistent revenue growth.
5.	Data-Driven Decision Making:
-- Enhance Data Collection and Analysis: Improve data collection and analysis processes to gain deeper insights into customer behavior, market trends, and product performance.
-- Regular Dashboard Review: Regularly review the dashboard and track key performance indicators (KPIs) to monitor progress and identify areas for improvement.
-- Foster a Data-Driven Culture: Foster a data-driven culture within the organization to promote the use of data in decision-making.

