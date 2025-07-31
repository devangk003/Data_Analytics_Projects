# SQL Data Analysis Projects

## Overview
This repository showcases my proficiency in SQL for comprehensive data analysis, designed to extract actionable insights from various datasets. It includes two distinct projects: a Pizza Sales Analysis and a Superstore Sales Analysis.

## Project By:
Devang Kumawat
[cite_start]Data Analyst [cite: 3, 4, 48]

## Pizza Sales Analysis Project

### Problem Statement
[cite_start]This project dives into pizza sales data to unlock key insights. [cite: 8] [cite_start]The primary goal is to convert raw sales numbers into actionable intelligence that propels informed choices and drives business. [cite: 12] [cite_start]This analysis is critical for understanding customer preferences, revenue streams, and overall business performance within the fast-food and broader food industry. [cite: 6, 7]

### Data Sources
[cite_start]The pizza sales analysis utilized the following datasets: [cite: 20]
* [cite_start]`ORDERS` [cite: 21]
* [cite_start]`ORDERS_DETAILS` [cite: 22]
* [cite_start]`PIZZAS` [cite: 23]
* [cite_start]`PIZZA_TYPES` [cite: 24]

### Tools & Technologies
* [cite_start]**Software:** MySQL Workbench [cite: 19]
* **Language:** SQL
* [cite_start]**Skills Demonstrated:** This project involved complex SQL queries, utilizing multiple joins, aggregations, subqueries, and window functions to extract detailed sales data. [cite: 15]

### Key Analysis and Insights
* [cite_start]**Total Orders:** Retrieved the total number of orders placed (21,350 orders). [cite: 25]
* [cite_start]**Total Revenue:** Calculated the total revenue generated from pizza sales ($817,860.05). [cite: 26]
* [cite_start]**Highest Price Pizza:** Identified 'The Greek Pizza' as the highest-priced pizza at $35.95. [cite: 27]
* [cite_start]**Most Common Pizza Size:** Determined that 'L' (Large) is the most commonly ordered pizza size (18,526 units). [cite: 28]
* [cite_start]**Top 5 Best-Selling Pizzas:** Identified the top 5 most ordered pizza types by quantity, with 'The Classic Deluxe Pizza' being the highest (2453 units). [cite: 29]
* [cite_start]**Pizza Category Quantity:** Joined necessary tables to find the total quantity of each pizza category ordered, with 'Classic' being the highest (14,888 units). [cite: 30]
* [cite_start]**Hourly Order Distribution:** Determined the distribution of orders by hour, showing peak ordering times (e.g., 12 PM with 2520 orders, 1 PM with 2455 orders, 6 PM with 2399 orders, and 5 PM with 2336 orders). [cite: 31]
* [cite_start]**Category-Wise Pizza Distribution:** Found the category-wise distribution of pizzas, with 'Supreme' and 'Veggie' having the most pizza names (9 each). [cite: 32]
* [cite_start]**Average Pizzas Per Day:** Calculated the average number of pizzas ordered per day (approximately 138.47). [cite: 33]
* [cite_start]**Top 3 Pizzas by Revenue:** Grouped orders to find the top 3 pizzas based on revenue: 'The Thai Chicken Pizza' ($43,434), 'The Barbecue Chicken Pizza' ($42,768), and 'The California Chicken Pizza' ($41,410). [cite: 34]
* [cite_start]**Revenue Contribution by Category:** Calculated the percentage contribution of each pizza type to total revenue, with 'Classic' contributing the highest (approx. 26.91%). [cite: 35]
* [cite_start]**Cumulative Revenue Over Time:** Analyzed the cumulative revenue generated over time, showing a steady increase. [cite: 36]
* [cite_start]**Top 3 Pizzas by Revenue per Category:** Determined the top 3 most ordered pizza types based on revenue for each pizza category. [cite: 37, 38]

### Conclusion
[cite_start]The Pizza Sales Analysis project provided valuable insights into sales performance and product demand through efficient SQL-based data exploration and analysis. [cite: 40] [cite_start]This analysis helps in understanding customer preferences, enabling better inventory management and more effective marketing strategies. [cite: 42] [cite_start]The project demonstrated the importance of SQL in extracting and transforming data to generate meaningful business insights. [cite: 43]

---

## Superstore Sales Project

### Objective
[cite_start]The objective of this project is to demonstrate proficiency in SQL by performing a comprehensive analysis on a sales dataset to extract actionable insights. [cite: 49, 54]

### Dataset Details
[cite_start]The Superstore sales dataset comprises over 9,500 rows [cite: 52] and includes attributes such as:
* [cite_start]Ship Mode [cite: 69]
* [cite_start]Segment [cite: 69]
* [cite_start]Country [cite: 69]
* [cite_start]City [cite: 69]
* [cite_start]State [cite: 69]
* [cite_start]Postal Code [cite: 71]
* [cite_start]Region [cite: 70]
* [cite_start]Category [cite: 70]
* [cite_start]Sub-Category [cite: 70]
* [cite_start]Sales [cite: 70]
* [cite_start]Quantity [cite: 70]
* [cite_start]Discount [cite: 70]
* [cite_start]Profit [cite: 70]

### Tools & Technologies
* [cite_start]**Database:** MySQL Workbench [cite: 57]
* [cite_start]**Language:** SQL [cite: 58]
* **Skills Demonstrated:**
    * [cite_start]Data filtering, grouping, joining tables [cite: 60]
    * [cite_start]Advanced query techniques (CTEs, subqueries) [cite: 61]
    * [cite_start]Pivot Table [cite: 62]
    * [cite_start]Aggregation [cite: 63]
    * [cite_start]Operators [cite: 64]
    * [cite_start]Nested queries [cite: 65]
    * [cite_start]Window Functions [cite: 66]

### Key Challenges
* [cite_start]**MySQL Limitations:** Handled the lack of `EXCEPT` and `INTERSECT` operators by using workarounds like `NOT IN` and `JOIN` clauses. [cite: 74, 75]
* [cite_start]**Data Volume:** Focused on efficient filtering and grouping for performance due to the large dataset size. [cite: 76, 77]
* [cite_start]**Insights Extraction:** Balanced granular and high-level insights to provide comprehensive analysis. [cite: 78, 79]

### Key SQL Queries & Insights
* **Data Filtering (`WHERE` clause):**
    * [cite_start]Retrieved all records where the ship mode is "Standard Class." [cite: 87, 88]
    * [cite_start]Identified loss-making transactions (profit < 0). [cite: 89]
* [cite_start]**Ordering (`ORDER BY` clause):** Sorted data first by region in ascending order and then by profit in descending order. [cite: 90, 91]
* **Joins:**
    * [cite_start]Performed `INNER JOIN` between sales data and a hypothetical `region_details` table to get region descriptions. [cite: 93]
    * [cite_start]Used `LEFT OUTER JOIN` and `RIGHT OUTER JOIN` to display regions along with matching region descriptions. [cite: 95]
* [cite_start]**Aggregation:** Calculated total sales ($2,297,200.86), average profit ($28.66), and maximum discount (0.8) for all transactions. [cite: 97]
* **Grouping and Aggregation (`GROUP BY`):**
    * [cite_start]Grouped data by region to find total sales and profit for each region (e.g., South: $391,721.91 sales, $46,749.43 profit; West: $725,457.82 sales, $108,418.45 profit). [cite: 99]
    * [cite_start]Calculated the average discount and total quantity sold for each segment (e.g., Consumer: 0.158 average discount, 19,521 quantity). [cite: 100]
* [cite_start]**Having Clause:** Identified sub-categories where the average profit was less than 0 (e.g., Bookcases, Tables, Supplies). [cite: 102]
* **Subqueries:**
    * [cite_start]Extracted transactions with sales greater than the overall average sales. [cite: 104]
    * [cite_start]Identified regions where the total profit exceeded the total profit in the "Central" region (South, West, East). [cite: 106]
* [cite_start]**Common Table Expressions (CTEs):** Used a CTE to find the top 5 most profitable sub-categories (Copiers, Phones, Accessories, Paper, Binders). [cite: 108]
* [cite_start]**Nested Queries:** Identified cities where the highest sales were greater than the average sales across all regions (e.g., New York City, Jacksonville, Lafayette, Seattle). [cite: 110]
* [cite_start]**Window Functions:** Ranked products by their profit within each category. [cite: 112]
* [cite_start]**Pivot Table:** Created a pivot table showing total sales for each category across regions. [cite: 114]

## How to View the Project
1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/](https://github.com/)[Your_Username]/[Your_Repo_Name].git
    ```
2.  Navigate to the respective project directory (e.g., `Pizza_Sales_Analysis` or `Superstore_Sales_Analysis`).
3.  The SQL queries are typically found within `.sql` files or can be directly run in MySQL Workbench against the corresponding datasets (which would need to be imported if not already set up).

---