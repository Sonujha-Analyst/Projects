# Blinkit Analysis-Dashboard

### Dashboard Overview:
![Image](https://github.com/user-attachments/assets/31fb9ca9-3763-4750-8b51-bf1cbf8cfe83)

## Problem Statement

This dashboard provides an in-depth analysis of Blinkit's operations, helping stakeholders understand key metrics such as order volume, customer satisfaction, delivery efficiency, and product trends. The dashboard aims to highlight areas for improvement, optimize delivery times, and enhance customer experience through data-driven insights.

## Key insights include:

1. Identification of peak order times and trends.

2. Customer satisfaction ratings and feedback.

3. Average order processing and delivery time.

4. Sales performance across different product categories.



### Steps followed 

- Step 1 : Requirement Gathering: Understanding business needs and defining project objectives.
- Step 2 : Data Walkthrough: Reviewing data sources and formats.
- Step 3 : Data Connection: Connecting Power BI to required datasets, datasets are excel file.
- Step 4 : Data Cleaning/Quality Check: Handling missing values, duplicates, and inconsistencies.
- Step 5 : Data Modelling: Establishing relationships between tables for efficient analysis.
- Step 6 : Data Processing: Transforming and aggregating data for meaningful insights.
- Step 7 : DAX Calculations: Creating calculated columns, measures, and KPIs using DAX.
First measure was created to find total sales of each & every product.

Following DAX expression was written for the same,

![Image](https://github.com/user-attachments/assets/5a2f5f66-0079-447e-a0c3-947fba5dd5cb)

Second measure was created to find number of of items i.e, total count of different items sold.

Following DAX expression was written for the same,

![Image](https://github.com/user-attachments/assets/5956e0ce-5e9b-4e0f-801b-699372940a37)

Third measure was created to find average sales i.e, average revenue per sales.

Following DAX expression was written for the same,

![Image](https://github.com/user-attachments/assets/2724b466-4927-4014-ba17-c2b30776255f)

Fourth measure was created to find average rating given by customers.

Following DAX expression was written for the same,

![Image](https://github.com/user-attachments/assets/e93b10b0-3668-42aa-8e6b-e30ecde48e07)


Fifth measure was created a Metrix  which helps in determining how the other KPI's affets by a single change in one component.

Following DAX expression was written for the same,

![Image](https://github.com/user-attachments/assets/f598a1a8-953a-43a0-8641-7429af0ddb0a)


- Step 8 : Dashboard Lay Outing: Designing a structured and visually appealing layout.
- Step 9 : Charts Development and Formatting: Selecting appropriate charts and ensuring readability.
- Step 10 : Dashboard/Report Development: Integrating visual elements into an interactive dashboard.
# KPI’s Requirements:

1.	Total Sales: The overall revenue generated from all items sold.
2.	Average Sales: The average revenue per sale.
3.	Number of Items: Total count of different items sold.
4.	Average Rating: The average customer rating for items sold.

# Chart’s Requirements:

1.	Total Sales by Fat Content:
Objective: Analyse the impact of fat content on total sales.
Additional KPI Metrices: Assess how other KPI’s (Average sales, No. of Items, Average Rating) vary with fat Content.
Chart Type: Donut Chart.

2.	Total Sales by Item Type:
Objective: Identify the performance of different item types in terms of total sales.
Additional KPI Metrices: Assess how other KPI’s (Average sales, No. of Items, Average Rating) vary with fat Content.
Chart Type: Bar Chart.

3.	Fat Content by Outlet for Total Sales:
Objective: Compare total sales across different outlets segmented by fat content.
Additional KPI Metrices: Assess how other KPI’s (Average sales, No. of Items, Average Rating) vary with fat Content.
Chart Type: Stacked Column Chart.

4.	Total Sales by Outlet Establishment: 
Objective: Evaluate how the age or type of outlet establishments influences total sales.
Chart Type: Line Chart.

5.	Sales by Outlet Size: 
Objective: Analyse the correlation between outlet size and total sales.
Chart Type: Donut/ Pie Chart.

6.	Sales by Outlet Location: 
Objective: Assess the geographic distribution of sales across different locations.
Chart Type: Funnel Map.

7.	All Metrices by Outlet Type: 
Objective: Provide a comprehensive view of all key metrics (Total Sales, Number of Items, Average Rating) broken down by different outlet types.
Chart Type: Matrix Card.


- Step 11 : Insights Generation: Analyzing key trends and providing actionable recommendations.
 

### Insights
1. Blinkit Sales Analysis in Tier 1 area and growth during the years, and here is the results shown below:
![Image](https://github.com/user-attachments/assets/abac196d-ca80-4869-801d-6e5c4e179e01)

2. Blinkit Sales Analysis in Tier 2 area and growth during the years, and here is the results shown below:
![Image](https://github.com/user-attachments/assets/80a32158-df7c-49a5-9371-9a9d10986938)

3. Blinkit Sales Analysis in Tier 3 area and growth during the years, and here is the results shown below:
![Image](https://github.com/user-attachments/assets/bfe20ead-6927-48e8-bb74-f85fabf2b717)

4. Blinkit Sales Analysis on behalf of outlet size and growth during the years in high size store, and here is the results shown below:
![Image](https://github.com/user-attachments/assets/71d27047-e0bd-42f8-a494-707da330a18b)

5. Blinkit Sales Analysis on behalf of outlet size and growth during the years in medium size store, and here is the results shown below:
![Image](https://github.com/user-attachments/assets/f174c956-6f6f-4f39-94ab-d6dd5e0bd97f)

6. Blinkit Sales Analysis on behalf of outlet size and growth during the years in small size store, and here is the results shown below:
![Image](https://github.com/user-attachments/assets/11dfeacf-66a5-4336-8e4b-09f6adaf189a)

### Recommendations
1. Expand in Tier 3 Locations – Increase medium-sized outlets based on high sales growth and conduct market research to optimize product selection.

2. Enhance Product Availability – Improve visibility of low-performing categories like breakfast items and seafood to boost sales.

3. Improve Customer Satisfaction – Focus on faster delivery, better order fulfillment, and targeted promotions. Implement a feedback loop to address concerns.

4. Leverage Promotions & Marketing – Introduce discounts, loyalty programs, and targeted marketing for high-margin products.

5. Optimize Grocery Stores – Improve pricing, product variety, and delivery services to boost performance.

# Conclusion

The analysis of Blinkit's sales data indicates a spontaneous growth in Tier 3 locations, particularly in medium-sized outlets. With total sales of $299.37K, these outlets are performing well due to a high number of items sold (2128) and an average sales value of $141 per transaction. The average rating of 3.9 suggests customer satisfaction is moderately high but leaves room for improvement.

The highest-selling product categories include fruits & vegetables ($44K), snack foods ($40K), and household items ($37K), indicating a strong demand for daily essentials in these locations. Furthermore, the "Regular" fat content category dominates sales ($204.73K), suggesting a consumer preference for standard products over low-fat alternatives.

Additionally, Supermarket Type 3 stores have performed well with nearly $131.48K in sales and 928 items sold, while grocery stores lag behind with $37.18K in sales.

![Image](https://github.com/user-attachments/assets/b2d10528-005d-4fca-8bdf-16e717ad35ed)


# Blinkit Analysis-Dashboard

A brief description of what this project does and who it's for.

