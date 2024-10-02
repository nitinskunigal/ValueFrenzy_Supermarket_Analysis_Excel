**Project Overview**  
This project presents a comprehensive data analysis for ValueFrenzy, a large supermarket chain operating across the USA, Mexico, and Canada. The analysis focuses on sales data from 2021-2023, addressing key performance indicators (KPIs) such as Total Revenue, Gross Profit, Quantity Sold, Total Transactions, and Average Transaction Value (ATV).

**Motivation**  
In the highly competitive FMCG industry, it is crucial to maintain strong profit margins while responding to shifting customer behaviors. This project aims to provide actionable insights that can help ValueFrenzy identify gaps and capitalize on opportunities to improve overall profitability and customer satisfaction.

**Key KPIs**
Total Revenue - Total revenue generated by ValueFrenzy across all regions and product categories.
Gross Profit - Profit after deducting COGS (Cost of Goods Sold) from total revenue.
Quantity Sold - Total units sold across all regions.
Total Transactions - Number of customer transactions.
Average Transaction Value (ATV) - Average amount spent per transaction.

**Insights and Recommendations**

Insight 1:
Declining Revenue and Gross Profit:  
•	Insight: ValueFrenzy’s revenue dropped from $13.8M in 2021 to $9.7M in 2022 and 2023, alongside a decline in gross profit from $8.2M to $5.8M.  
•	Root Cause: Reduced high-tier product sales, especially in the USA, due to economic constraints and lower ATV after Q4 2021.

![ValueFrenzy_Insight 1](https://github.com/user-attachments/assets/a8990e20-1417-4340-90db-34e3f75c1e55)
 
Recommendation 1:
Address Declining Revenue and Gross Profit:  
•	Focus on targeted promotions and pricing strategies for high-tier products, especially electronics and furniture, to revive sales in the USA.  
•	Introduce flexible financing or installment plans to encourage purchases of higher-value items.  

Insight 2:
Stable Quantity Sold but Shifting Product Mix:  
•	Insight: 15.7M units sold, with groceries making up 60% of sales. High-tier product sales declined significantly.  
•	Root Cause: Economic pressures led customers to prioritize essential goods like groceries, reducing demand for high-tier items.

![ValueFrenzy_Insight 2](https://github.com/user-attachments/assets/ab8291ee-8778-457a-9bfa-7bfaba42f712)
 
Recommendation 2:
Optimize Product Mix and Encourage High-Tier Sales:  
•	Shift marketing focus toward medium- and high-tier products in regions like Mexico and Canada, where potential for growth remains.
•	Launch product bundles and cross-selling initiatives to increase spending on higher-margin categories.

Insight 3:
High Transaction Volume but Lower Average Transaction Value:  
•	Insight: Transaction volume remained steady, but ATV dropped from $75+ in 2021 to $53+ in 2022-2023.  
•	Root Cause: Fewer high-value transactions and more frequent low-cost purchases caused the sharp drop in ATV.

![ValueFrenzy_Insight 3](https://github.com/user-attachments/assets/cbd3a45d-191a-4090-b9ba-bd3783b8c706)
 
Recommendation 3:
Boost Average Transaction Value (ATV):  
•	Implement loyalty programs and personalized discounts to increase the ATV, particularly for frequent customers.
•	Encourage customers to add higher-value products to their carts through targeted upselling at checkout.

Insight 4:
Regional Disparities in Performance:  
•	Insight: USA saw the largest revenue drop, while Mexico and Canada showed better stability.  
•	Root Cause: Economic challenges in the USA drove the steep decline in high-tier sales, while Mexico and Canada were less affected.

Recommendation 4:
Improve Regional Performance with Tailored Strategies:  
•	Develop region-specific marketing campaigns to address the unique needs of each market (USA, Mexico, and Canada).
•	Invest in localized market research to better understand customer behavior and adapt product offerings accordingly.

Insight 5:
Impact of Macroeconomic Conditions on Purchasing Patterns:  
•	Insight: A significant drop in ATV, especially in the USA, indicated a shift toward lower-cost, essential goods.  
•	Root Cause: Inflation and changing consumer behavior led to fewer purchases of high-value products like electronics.

Recommendation 5:
Adapt to Macroeconomic Conditions:  
•	Leverage ValueFrenzy’s private label brands to provide customers with affordable, high-quality alternatives.
•	Enhance operational efficiency to mitigate rising costs and pass savings on to consumers through competitive pricing.

For a more detailed look at the insights and recommendations, please refer to the Project Report (Insert Hyperlink).

**Data Model**

The data model was created using Power Pivot to establish relationships between the fact table (sales data) and dimension tables (products, regions, and time). This data model is the backbone of the analysis and enabled complex calculations and dynamic insights.

![ValueFrenzy Data Model](https://github.com/user-attachments/assets/f95401f3-dde9-4cc9-a792-837262b9d0c0)
 
The fact and dimension tables are related in the following ways:
•	Fact Table (Sales): Includes sales transaction data segmented by region, product category, and time.
•	Dimension Tables: 
o	Products: Categorizes products into low-tier (groceries), medium-tier (household goods), and high-tier (electronics).
o	Regions: Lists USA, Mexico, and Canada.
o	Time: Segments data by year, month, and quarter for trend analysis.

**Tools and Technologies Used**
•	Excel only: 
o	Power Query: To clean (handling missing data, duplicates, etc.) and transform (Unpivoting Columns, Custom Columns etc.) the raw sales data.
o	Power Pivot: Employed to establish relationships between data tables & lookup tables and performed detailed analysis DAX calculated Columns and Measures within power pivot. 
o	Excel Dashboards: Created multi-page dashboards to visualize KPIs, interact with the data through slicers and analyze trends.

**How to Use This Project**
1.	Download the Excel Dashboard from this repository. The dashboard can be used to explore the KPIs and trends across different markets.
2.	As the dashboard is fully interactive, use slicers to explore data by different regions, product tiers, and time period. It’s a multi-page dashboard (3 pages) and you’ll find three big buttons for three pages.
3.	Review the detailed Project Report and Presentation Slides for further insights.

**Future Work / Next Steps**
While this project provides valuable insights, there are several ways it can be expanded:
•	Scaling Up: Integrate more advanced data tools like Power BI for enhanced visualizations and interactivity, especially for larger datasets.
•	Deeper Analysis: Further segment the data by product categories, customer demographics, and geographic micro-markets to gain more granular insights.
•	Predictive Analytics: Use machine learning models to forecast future sales trends, customer behavior, and revenue potential.

**Conclusion**
This data analysis project provides a clear understanding of the factors affecting ValueFrenzy’s performance from 2021-2023. The insights drawn from this analysis can help guide strategic decisions to improve revenue, optimize product offerings, and tailor marketing efforts based on regional trends.
Explore the project, interact with the dashboard, and read through the detailed findings to see how data-driven insights can shape business strategy in the FMCG sector.

Project Files  
•	[Project Report (PDF)] (Insert hyperlink)
•	[Presentation Slides (PPT)] (Insert hyperlink)
•	[Excel Dashboard] (Insert hyperlink)
