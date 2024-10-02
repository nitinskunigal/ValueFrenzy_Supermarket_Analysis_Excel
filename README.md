# **Section 1: Project Overview**  
This project is an in-depth analysis of sales data from ValueFrenzy, a fictional supermarket chain operating in the FMCG sector across the USA, Mexico, and Canada. The goal was to analyze key performance indicators (KPIs) such as Total Revenue, Gross Profit, Quantity Sold, Total Transactions, and Average Transaction Value (ATV) to uncover insights and provide recommendations for business growth. The analysis focused on historical sales data from 2021-2023, segmented by three major regions (USA, Mexico, Canada) and product tiers (low-tier like groceries, medium-tier like household goods, and high-tier like electronics). 

The objective of this project is to assist ValueFrenzy in understanding sales trends from 2021-2023, identify the root causes of declining revenue and profitability, and provide actionable insights and recommendations to improve operational efficiency and market competitiveness across its three regions: USA, Mexico, and Canada.

# **Section 2: Motivation**  
In the highly competitive FMCG industry, it is crucial to maintain strong profit margins while responding to shifting customer behaviors. This project aims to provide actionable insights that can help ValueFrenzy identify gaps and capitalize on opportunities to improve overall profitability and customer satisfaction.

# **Section 3: Data Sources**
The dataset used for this analysis was provided in CSV format, eliminating the need to use SQL for data retrieval. The data was imported directly into Power Query for cleaning, transformation, and modeling.

# **Section 4: Data Model**

The data model was created using Power Pivot to establish relationships between the fact table (sales data) and dimension tables (products, regions, and time periods). This data model is the backbone of the analysis and enables complex calculations and dynamic insights. It allows for slicing and dicing data in multiple dimensions for deeper analysis and visualization within the dashboard. The relationships are structured as follows:

![ValueFrenzy Data Model](https://github.com/user-attachments/assets/f95401f3-dde9-4cc9-a792-837262b9d0c0)
 
## ***Fact Table (Sales):***
Includes consolidated sales transaction data (2021-2023) segmented by region, product category, and time.
## ***Dimension Tables:***
### *Products:* 
Categorizes products into low-tier (groceries), medium-tier (household goods), and high-tier (electronics).
### *Regions:* 
Includes USA, Mexico, and Canada.
### *Time:* 
Segments data by year, month, and quarter for trend analysis.

For the complete details about the Dashboard, Data Model, Detailed Analysis (Pivot Tables and DAX Measures), please refer to [Excel Dashboard](https://github.com/nitinskunigal/ValueFrenzy_Supermarket_Analysis_Excel/blob/main/ValueFrenzy%20Dashboard%20-%20NK.xlsx).

# **Section 5: Key KPIs**

## **Total Revenue**
Total revenue generated by ValueFrenzy across all regions and product categories.

## **Gross Profit**
Profit after deducting COGS (Cost of Goods Sold) from total revenue.

## **Quantity Sold**
Total units sold across all regions.

## **Total Transactions**
Number of customer transactions.

## **Average Transaction Value (ATV)**
Average amount spent per transaction.

# **Section 6: Insights and Recommendations**

## **Insight 1:**

### *Declining Revenue and Gross Profit:*
1.	**Insight**: ValueFrenzy’s revenue dropped from $13.8M in 2021 to $9.7M in 2022 and 2023, alongside a decline in gross profit from $8.2M to $5.8M.  
2.	**Root Cause**: Reduced high-tier product sales, especially in the USA, due to economic constraints and lower ATV after Q4 2021.


![ValueFrenzy_Insight 1](https://github.com/user-attachments/assets/fceec189-4fba-4312-b983-42a0285d4e50)
 
## **Recommendation 1:**

### ***Address Declining Revenue and Gross Profit:***
1.	Focus on targeted promotions and pricing strategies for high-tier products, especially electronics and furniture, to revive sales in the USA.  
2.	Introduce flexible financing or installment plans to encourage purchases of higher-value items.  

## **Insight 2:**

### *Stable Quantity Sold but Shifting Product Mix:*
1.	**Insight**: 15.7M units sold, with groceries making up 60% of sales. High-tier product sales declined significantly.  
2.	**Root Cause**: Economic pressures led customers to prioritize essential goods like groceries, reducing demand for high-tier items.

![ValueFrenzy_Insight 2](https://github.com/user-attachments/assets/ab8291ee-8778-457a-9bfa-7bfaba42f712)
 
## **Recommendation 2:**

### *Optimize Product Mix and Encourage High-Tier Sales:*  
1.	Shift marketing focus toward medium- and high-tier products in regions like Mexico and Canada, where potential for growth remains.
2.	Launch product bundles and cross-selling initiatives to increase spending on higher-margin categories.

## **Insight 3:**

### *High Transaction Volume but Lower Average Transaction Value:*
1.	**Insight**: Transaction volume remained steady, but ATV dropped from $75+ in 2021 to $53+ in 2022-2023.  
2.	**Root Cause**: Fewer high-value transactions and more frequent low-cost purchases caused the sharp drop in ATV.

![ValueFrenzy_Insight 3](https://github.com/user-attachments/assets/cbd3a45d-191a-4090-b9ba-bd3783b8c706)
 
## **Recommendation 3:**

### *Boost Average Transaction Value (ATV):*
1.	Implement loyalty programs and personalized discounts to increase the ATV, particularly for frequent customers.
2.	Encourage customers to add higher-value products to their carts through targeted upselling at checkout.

## **Insight 4:**

### *Regional Disparities in Performance:*
1.	**Insight**: USA saw the largest revenue drop, while Mexico and Canada showed better stability.  
2.	**Root Cause**: Economic challenges in the USA drove the steep decline in high-tier sales, while Mexico and Canada were less affected.

## **Recommendation 4:**

### *Improve Regional Performance with Tailored Strategies:*
1.	Develop region-specific marketing campaigns to address the unique needs of each market (USA, Mexico, and Canada).
2.	Invest in localized market research to better understand customer behavior and adapt product offerings accordingly.

## **Insight 5:**

### *Impact of Macroeconomic Conditions on Purchasing Patterns:*
1.	**Insight**: A significant drop in ATV, especially in the USA, indicated a shift toward lower-cost, essential goods.  
2.	**Root Cause**: Inflation and changing consumer behavior led to fewer purchases of high-value products like electronics.

## **Recommendation 5:**

### *Adapt to Macroeconomic Conditions:*
1.	Leverage ValueFrenzy’s private label brands to provide customers with affordable, high-quality alternatives.
2.	Enhance operational efficiency to mitigate rising costs and pass savings on to consumers through competitive pricing.

For a more detailed look at the insights and recommendations, please refer to the [Project Report](https://github.com/nitinskunigal/ValueFrenzy_Supermarket_Analysis_Excel/blob/main/ValueFrenzy_Data%20Analysis%20Project%20Report_NK.pdf) and the [Presentation Slides](https://github.com/nitinskunigal/ValueFrenzy_Supermarket_Analysis_Excel/blob/main/ValueFrenzy_Data%20Analysis%20Project_NK.pptx).

# **Section 7: Rationale Behind Choosing EXCEL as My Go-To Tool**
For this project, I chose to leverage Excel as my primary data analysis tool. Excel has several powerful features that make it a perfect fit for end-to-end data analysis, including:
1.	**Data Processing and Transformation in Power Query**: Excel’s Power Query allows for efficient data import, cleaning, and transformation, providing robust capabilities to handle even complex and large datasets.

2.	**Data Modeling and DAX in Power Pivot**: With Power Pivot, I was able to create a comprehensive data model, define relationships between fact and dimension tables, and execute calculations via DAX (Data Analysis Expressions), mimicking many of the features typically associated with advanced tools like Power BI.

3.	**Visualization and Dashboarding**: Excel’s charting and pivot table functionalities allowed me to create dynamic, interactive dashboards with slicers and drill-down options. The final dashboard is easy to interact with, aligning with the project's goal of simplicity and accessibility for a wide audience.

By focusing solely on Excel, I was able to unlock its full potential, demonstrating how it can be utilized not only for simple spreadsheets but also for advanced data modeling, in-depth analysis, and professional visual reporting.

# **Section 8: How to Use This Project**
1.	Download the Excel Dashboard from this repository. The dashboard can be used to explore the KPIs and trends across different markets.
	
2.	As the dashboard is fully interactive, use slicers to explore data by different regions, product tiers, and time period. It’s a multi-page dashboard (3 pages) and you’ll find three big buttons for three pages.
	
3.	Review the detailed Project Report and Presentation Slides for further insights.

# **Section 9: Future Work / Next Steps**
While this project provides valuable insights, there are several ways it can be expanded:

1.	Scaling Up: Integrate more advanced data tools like Power BI for enhanced visualizations and interactivity, especially for larger datasets.

2.	Deeper Analysis: Further segment the data by product categories, customer demographics, and geographic micro-markets to gain more granular insights.

3.	Predictive Analytics: Use machine learning models to forecast future sales trends, customer behavior, and revenue potential.

# **Section 10: Lessons Learned**
Working on the ValueFrenzy data analysis project has been an invaluable experience, offering insights from various perspectives—technical, analytical, and strategic:

## ***1. Data Preparation and Cleaning:***
One of the key lessons was the importance of robust data cleaning and transformation. Handling messy, incomplete, and unstructured data required a deep dive into Power Query, which helped automate much of the cleaning process. I gained valuable experience in understanding the nuances of data quality issues and how to resolve them effectively.

## ***2. Working with Real-World Business Data:***
I learned how real-world datasets often don’t conform to neat, predefined structures. The data required not only cleaning but also thoughtful segmentation, such as breaking down information by product tiers and regions. Understanding the business logic behind the data was critical in making the right transformations and interpreting the results correctly.

## ***3. Defining Key Metrics and KPIs:***
Identifying the right KPIs—Total Revenue, Gross Profit, Quantity Sold, Total Transactions, and Average Transaction Value—taught me the importance of aligning analytical goals with business objectives. These KPIs formed the backbone of the analysis, and I learned how essential it is to communicate their impact clearly to stakeholders.
## ***4. Data Modeling and DAX Measures in Power Pivot:***
Setting up relationships between fact and dimension tables was a key learning area. Understanding how to structure data models for efficient querying and analysis helped me enhance my skills in Power Pivot and reinforced the importance of having well-defined data relationships. Using different DAX measures further solidified my understanding of how to slice and dice data from different perspectives yet connecting the dots between all the 5 KPIs, which wouldn't have been possible with normal pivot tables.
## ***5. Dashboard Design and Presentation:***
Crafting a dashboard that is both insightful and user-friendly was a rewarding challenge. I learned the importance of balancing aesthetics and functionality, ensuring that key insights were easily accessible while maintaining a clean and professional design. This project helped me hone my skills in visual storytelling and presenting complex insights in a simplified, impactful way.
## ***6. Stakeholder Collaboration and Feedback:***
Frequent iterations and feedback loops with hypothetical stakeholders like Sarah (COO) gave me an understanding of the dynamic nature of data analytics projects. I learned how to adjust my analysis and recommendations based on feedback and how to present findings that resonate with a C-level audience.
## ***7. Time Management and Agile Approach:***
Managing the project timeline taught me to work in sprints and deliver results iteratively. Each phase of the project, from data collection to final presentation, required effective time management and prioritization of tasks. This experience highlighted the need for flexibility and adaptability in the face of evolving requirements.

Overall, this project was a comprehensive learning experience, covering everything from technical data handling to strategic business analysis and communication. It has prepared me well for future data analysis projects where technical skills, business understanding, and stakeholder engagement all converge.

# **Section 11: Conclusion**
This project provides a clear understanding of the factors affecting ValueFrenzy’s performance from 2021-2023. The data analysis provides actionable insights that can drive significant improvements in ValueFrenzy's revenue and profitability. By addressing key gaps in high-tier product sales and focusing on region-specific strategies, the company can enhance its market presence and operational efficiency across the USA, Mexico, and Canada.

# **Section 12: View/ Download Project Files**

•	[Project Report (PDF)](https://github.com/nitinskunigal/ValueFrenzy_Supermarket_Analysis_Excel/blob/main/ValueFrenzy_Data%20Analysis%20Project%20Report_NK.pdf)

•	[Presentation Slides (PPT)](https://github.com/nitinskunigal/ValueFrenzy_Supermarket_Analysis_Excel/blob/main/ValueFrenzy_Data%20Analysis%20Project_NK.pptx)

•	[Excel Dashboard](https://github.com/nitinskunigal/ValueFrenzy_Supermarket_Analysis_Excel/blob/main/ValueFrenzy%20Dashboard%20-%20NK.xlsx)

•	[Video Presentation](https://share.vidyard.com/watch/i11Buozsgp1U7zwZLSKkQJ?)
