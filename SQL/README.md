# Data_Analytics_Projects

## Overview
This GitHub repository serves as a portfolio showcasing my expertise in data analysis through various projects. It encompasses comprehensive analyses performed using SQL and Microsoft Excel, demonstrating my ability to transform raw data into actionable insights for informed decision-making.

## Project By:
Devang Kumawat
Data Analyst [cite: 3, 4, 48]

## SQL Data Analysis Projects

### Project 1: Pizza Sales Analysis

#### Problem Statement
This project dives into pizza sales data to unlock key insights. [cite: 8] The primary goal is to convert raw sales numbers into actionable intelligence that propels informed choices and drives business. [cite: 12] This analysis is critical for understanding customer preferences, revenue streams, and overall business performance within the fast-food and broader food industry. [cite: 6, 7]

#### Data Sources
The pizza sales analysis utilized the following datasets: [cite: 20]
* `ORDERS` [cite: 21]
* `ORDERS_DETAILS` [cite: 22]
* `PIZZAS` [cite: 23]
* `PIZZA_TYPES` [cite: 24]

#### Tools & Technologies
* **Software:** MySQL Workbench [cite: 19]
* **Language:** SQL
* **Skills Demonstrated:** This project involved complex SQL queries, utilizing multiple joins, aggregations, subqueries, and window functions to extract detailed sales data. [cite: 15]

#### Key Analysis and Insights
* **Total Orders:** Retrieved the total number of orders placed (21,350 orders). [cite: 25]
* **Total Revenue:** Calculated the total revenue generated from pizza sales ($817,860.05). [cite: 26]
* **Highest Price Pizza:** Identified 'The Greek Pizza' as the highest-priced pizza at $35.95. [cite: 27]
* **Most Common Pizza Size:** Determined that 'L' (Large) is the most commonly ordered pizza size (18,526 units). [cite: 28]
* **Top 5 Best-Selling Pizzas:** Identified the top 5 most ordered pizza types by quantity, with 'The Classic Deluxe Pizza' being the highest (2453 units). [cite: 29]
* **Pizza Category Quantity:** Joined necessary tables to find the total quantity of each pizza category ordered, with 'Classic' being the highest (14,888 units). [cite: 30]
* **Hourly Order Distribution:** Determined the distribution of orders by hour, showing peak ordering times (e.g., 12 PM with 2520 orders, 1 PM with 2455 orders, 6 PM with 2399 orders, and 5 PM with 2336 orders). [cite: 31]
* **Category-Wise Pizza Distribution:** Found the category-wise distribution of pizzas, with 'Supreme' and 'Veggie' having the most pizza names (9 each). [cite: 32]
* **Average Pizzas Per Day:** Calculated the average number of pizzas ordered per day (approximately 138.47). [cite: 33]
* **Top 3 Pizzas by Revenue:** Grouped orders to find the top 3 pizzas based on revenue: 'The Thai Chicken Pizza' ($43,434), 'The Barbecue Chicken Pizza' ($42,768), and 'The California Chicken Pizza' ($41,410). [cite: 34]
* **Revenue Contribution by Category:** Calculated the percentage contribution of each pizza type to total revenue, with 'Classic' contributing the highest (approx. 26.91%). [cite: 35]
* **Cumulative Revenue Over Time:** Analyzed the cumulative revenue generated over time, showing a steady increase. [cite: 36]
* **Top 3 Pizzas by Revenue per Category:** Determined the top 3 most ordered pizza types based on revenue for each pizza category. [cite: 37, 38]

#### Conclusion
The Pizza Sales Analysis project provided valuable insights into sales performance and product demand through efficient SQL-based data exploration and analysis. [cite: 40] This analysis helps in understanding customer preferences, enabling better inventory management and more effective marketing strategies. [cite: 42] The project demonstrated the importance of SQL in extracting and transforming data to generate meaningful business insights. [cite: 43]

---

### Project 2: Superstore Sales Analysis

#### Objective
The objective of this project is to demonstrate proficiency in SQL by performing a comprehensive analysis on a sales dataset to extract actionable insights. [cite: 49, 54]

#### Dataset Details
The Superstore sales dataset comprises over 9,500 rows [cite: 52] and includes attributes such as:
* Ship Mode [cite: 69]
* Segment [cite: 69]
* Country [cite: 69]
* City [cite: 69]
* State [cite: 69]
* Postal Code [cite: 71]
* Region [cite: 70]
* Category [cite: 70]
* Sub-Category [cite: 70]
* Sales [cite: 70]
* Quantity [cite: 70]
* Discount [cite: 70]
* Profit [cite: 70]

#### Tools & Technologies
* **Database:** MySQL Workbench [cite: 57]
* **Language:** SQL [cite: 58]
* **Skills Demonstrated:**
    * Data filtering, grouping, joining tables [cite: 60]
    * Advanced query techniques (CTEs, subqueries) [cite: 61]
    * Pivot Table [cite: 62]
    * Aggregation [cite: 63]
    * Operators [cite: 64]
    * Nested queries [cite: 65]
    * Window Functions [cite: 66]

#### Key Challenges
* **MySQL Limitations:** Handled the lack of `EXCEPT` and `INTERSECT` operators by using workarounds like `NOT IN` and `JOIN` clauses. [cite: 74, 75]
* **Data Volume:** Focused on efficient filtering and grouping for performance due to the large dataset size. [cite: 76, 77]
* **Insights Extraction:** Balanced granular and high-level insights to provide comprehensive analysis. [cite: 78, 79]

#### Key SQL Queries & Insights
* **Data Filtering (`WHERE` clause):**
    * Retrieved all records where the ship mode is "Standard Class." [cite: 87, 88]
    * Identified loss-making transactions (profit < 0). [cite: 89]
* **Ordering (`ORDER BY` clause):** Sorted data first by region in ascending order and then by profit in descending order. [cite: 90, 91]
* **Joins:**
    * Performed `INNER JOIN` between sales data and a hypothetical `region_details` table to get region descriptions. [cite: 93]
    * Used `LEFT OUTER JOIN` and `RIGHT OUTER JOIN` to display regions along with matching region descriptions. [cite: 95]
* **Aggregation:** Calculated overall total sales ($2,297,200.86), average profit ($28.66), and maximum discount (0.8) for all transactions. [cite: 97]
* **Grouping and Aggregation (`GROUP BY`):**
    * Grouped data by region to find total sales and profit for each region (e.g., South: $391,721.91 sales, $46,749.43 profit; West: $725,457.82 sales, $108,418.45 profit). [cite: 99]
    * Calculated the average discount and total quantity sold for each segment (e.g., Consumer: 0.158 average discount, 19,521 quantity). [cite: 100]
* **Having Clause:** Identified sub-categories where the average profit was less than 0 (e.g., Bookcases, Tables, Supplies). [cite: 102]
* **Subqueries:**
    * Extracted transactions with sales greater than the overall average sales. [cite: 104]
    * Identified regions where the total profit exceeded the total profit in the "Central" region (South, West, East). [cite: 106]
* **Common Table Expressions (CTEs):** Used a CTE to find the top 5 most profitable sub-categories (Copiers, Phones, Accessories, Paper, Binders). [cite: 108]
* **Nested Queries:** Identified cities where the highest sales were greater than the average sales across all regions (e.g., New York City, Jacksonville, Lafayette, Seattle). [cite: 110]
* **Window Functions:** Ranked products by their profit within each category. [cite: 112]
* **Pivot Table:** Created a pivot table showing total sales for each category across regions. [cite: 114]

## Excel Data Analysis Projects

### Project 1: BlinkIT Grocery Data Analysis

#### Objective
This project focuses on analyzing grocery store data to identify key trends, operational efficiencies, and customer purchasing patterns. The aim is to provide data-driven insights that can optimize inventory, improve sales strategies, and enhance overall business performance for BlinkIT Grocery.

#### Data Sources
The analysis for this project utilized data likely exported from the BlinkIT Grocery system:
* `Devang Project-BlinkIT Grocery Data.xlsx - BlinkIT Grocery Data.csv`
* `Devang Project-BlinkIT Grocery Data.xlsx - Sheets Design.csv` (Potentially related to dashboard or report layouts)

#### Tools & Technologies
* **Software:** Microsoft Excel
* **Key Excel Features/Functions:** Data Cleaning & Validation (e.g., removing duplicates, handling inconsistencies), Formulas (e.g., `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, `VLOOKUP`, `INDEX MATCH`), PivotTables & PivotCharts for aggregated analysis and dynamic reporting, Conditional Formatting for visual insights, Data Sorting and Filtering, Chart Creation (e.g., Bar Charts, Line Charts, Pie Charts for trend and distribution analysis), and Dashboard Design for interactive data exploration.

#### Key Analysis (Examples)
* **Sales Performance Analysis:** Breakdown of sales by product category, time period (daily, weekly, monthly), and payment method to identify top-performing areas and trends.
* **Customer Behavior:** Analysis of customer purchasing habits, average transaction value, and frequency of visits to understand customer segments.
* **Product Performance:** Identification of best-selling and slowest-moving grocery items, allowing for optimized stocking and promotional strategies.
* **Profitability Analysis:** Evaluation of gross profit margins across different product lines or categories.
* **Operational Insights:** Examination of order volumes during different hours or days to inform staffing and delivery schedules.

#### Conclusion and Recommendations (Examples)
This project aims to provide a clear overview of BlinkIT Grocery's operational and sales data. Insights gained can lead to:
* Optimized inventory management based on product demand.
* Targeted marketing campaigns for specific customer segments or product categories.
* Improved operational efficiency by understanding peak periods.

---

### Project 2: Sales Analysis Project (FNP, Customers, Orders, Product)

#### Objective
This comprehensive sales analysis project aims to provide a holistic view of sales performance by integrating data from various operational areas: customers, orders, and products. The goal is to uncover relationships between these data points to drive strategic decision-making in sales, marketing, and product development.

#### Data Sources
This project integrates multiple datasets for a complete sales overview:
* `Devang- Sales Analysis Project.xlsx - FNP.csv` (Could represent sales data for a specific entity or region, e.g., "Flowers N Petals")
* `Devang- Sales Analysis Project.xlsx - Customers.csv` (Customer demographic and possibly behavioral data)
* `Devang- Sales Analysis Project.xlsx - Orders.csv` (Transaction-level order details)
* `Devang- Sales Analysis Project.xlsx - Product.csv` (Product catalog information)
* `Devang- Sales Analysis Project.xlsx - Sheet1.csv` (Likely the main working sheet or output summary)

#### Tools & Technologies
* **Software:** Microsoft Excel
* **Key Excel Features/Functions:** Advanced Data Linking & Integration (using `VLOOKUP`, `INDEX MATCH`, `XLOOKUP` for combining data from different sheets/tables), Power Query for data extraction, transformation, and loading (ETL) if complex data shaping was required, Complex Formulas for calculating KPIs like Average Order Value, Customer Lifetime Value, Sales Growth, Interactive Dashboards with Slicers and Timelines for dynamic filtering and reporting, What-If Analysis (e.g., Data Tables, Goal Seek) for scenario planning, and Data Visualization (various chart types to represent sales trends, customer distribution, product mix).

#### Key Analysis (Examples)
* **Overall Sales Trends:** Analysis of total sales revenue and quantity sold over time (monthly, quarterly, yearly).
* **Product Performance by Category:** Identifying top-selling product categories, individual products, and their contribution to overall revenue and profit.
* **Customer Segmentation:** Grouping customers based on their purchasing behavior (e.g., high-value, frequent buyers, new customers) to tailor marketing efforts.
* **Order Analysis:** Understanding average order size, popular order combinations, and fulfillment times.
* **Geographic Sales Performance:** Breaking down sales by region, state, or city to identify strong and weak markets.
* **Profitability Analysis:** Detailed breakdown of profit margins per product, order, or customer segment.

#### Conclusion and Recommendations (Examples)
This project provides a comprehensive analytical framework for understanding sales performance from multiple dimensions. The insights derived can inform:
* Strategic pricing adjustments and promotional strategies.
* Targeted customer retention and acquisition campaigns.
* Optimized product assortment and inventory planning.
* Identification of new market opportunities or areas for expansion.

---
