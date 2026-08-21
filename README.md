# Food Delivery Business Analysis SQL Project

## Project Overview
**Project Title**: Food Delivery Business Analysis

**Level**: Intermediate

**Database**: Food Delivery Database

![Dashboard](https://github.com/Hatem207/SQL-Food-Delivery-Business/blob/main/zomatoERD.png)

This project is designed to demonstrate SQL skills and techniques typically used by data analysts to explore and analyze food delivery business data. The project involves creating a relational database containing customers, restaurants, orders, delivery persons, and deliveries, then using SQL queries to answer real-world business questions.

The project focuses on customer behavior, restaurant performance, order trends, delivery efficiency, revenue analysis, customer segmentation, and business performance.

## Objectives

1. **Set up a food delivery database**: Create and organize tables for customers, restaurants, orders, delivery persons, and deliveries.

2. **Explore the data**: Analyze customers, restaurants, orders, and delivery information.

3. **Perform business analysis**: Use SQL queries to answer real-world business questions.

4. **Analyze customer behavior**: Identify high-value customers, customer spending, order frequency, and customer lifetime value.

5. **Analyze restaurant performance**: Identify popular restaurants, restaurant revenue, growth, and cancellation rates.

6. **Analyze delivery performance**: Evaluate rider delivery time, earnings, ratings, and efficiency.

## Project Structure

### 1. Database Setup

The project starts by creating five related tables:

* `customers`
* `delivery_persons`
* `restaurants`
* `orders`
* `deliveries`

The database contains information about customers, restaurants, orders, and delivery operations.

### Customers

The `customers` table contains:

* Customer ID
* Name
* Email
* Phone
* Location
* Signup Date
* Premium Status
* Preferred Cuisine
* Total Orders
* Average Rating

### Restaurants

The `restaurants` table contains:

* Restaurant ID
* Restaurant Name
* Cuisine Type
* Location
* Owner Name
* Average Delivery Time
* Contact Number
* Rating
* Total Orders
* Active Status

### Orders

The `orders` table contains:

* Order ID
* Customer ID
* Restaurant ID
* Order Date
* Delivery Time
* Order Status
* Total Amount
* Payment Mode
* Discount Applied
* Feedback Rating

### Delivery Persons

The `delivery_persons` table contains:

* Delivery Person ID
* Name
* Contact Number
* Vehicle Type
* Total Deliveries
* Average Rating
* Location

### Deliveries

The `deliveries` table contains:

* Delivery ID
* Order ID
* Delivery Person ID
* Delivery Status
* Distance
* Delivery Time
* Estimated Time
* Delivery Fee
* Vehicle Type

## 2. Data Analysis

The following SQL queries were developed to answer specific business questions:

1. **Write a SQL query to find how many orders "Krish Basak" made in the last year.**

2. **Write a SQL query to identify the time slots during which the most orders are placed, based on 2-hour intervals.**

3. **Write a SQL query to find the average order value (AOV) per customer who has placed more than 7 orders.**

4. **Write a SQL query to find customers who have spent more than 20,000 in total on food orders.**

5. **Write a SQL query to find orders that were placed but not delivered and return the restaurant name, city, and number of not delivered orders.**

6. **Write a SQL query to rank restaurants by their total revenue from the last year, including their rank within their city.**

7. **Write a SQL query to identify the most popular restaurant in each city based on the number of orders.**

8. **Write a SQL query to find customers who haven't placed an order in 2024 but did place an order in 2023.**

9. **Write a SQL query to calculate and compare the order cancellation rate for each restaurant between the current year and previous year.**

10. **Write a SQL query to determine each rider's average delivery time.**

11. **Write a SQL query to calculate each restaurant's monthly growth ratio based on the number of delivered orders.**

12. **Write a SQL query to segment customers into Gold and Silver groups based on their total spending compared to the average order value.**

13. **Write a SQL query to calculate each rider's total monthly earnings, assuming they earn 8% of the order amount.**

14. **Write a SQL query to calculate the number of 5-star, 4-star, and 3-star ratings each rider receives based on delivery time.**

15. **Write a SQL query to analyze order frequency per day of the week and identify the peak day for each restaurant.**

16. **Write a SQL query to calculate the Customer Lifetime Value (CLV) for each customer.**

17. **Write a SQL query to identify monthly sales trends by comparing each month's total sales with the previous month.**

18. **Write a SQL query to evaluate rider efficiency based on average delivery time and rank the riders accordingly.**

19. **Write a SQL query to track monthly restaurant order trends and identify the months with the highest demand.**

20. **Write a SQL query to rank each city based on total revenue for the year 2023.**

## SQL Concepts Used

Throughout this project, several SQL concepts and techniques were used, including:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `JOIN`
* `LEFT JOIN`
* `COUNT`
* `SUM`
* `AVG`
* `CASE`
* `CTE`
* `RANK()`
* `LAG()`
* `DATE_TRUNC()`
* `EXTRACT()`
* `TO_CHAR()`
* Conditional Aggregation
* Window Functions

## Findings

* **Customer Insights**: The analysis identifies high-value customers, frequent customers, inactive customers, and customer lifetime value.

* **Restaurant Performance**: The analysis identifies the highest-revenue restaurants, most popular restaurants in each city, and restaurant growth trends.

* **Delivery Performance**: Rider analysis helps identify average delivery times, rider efficiency, monthly earnings, and delivery-based ratings.

* **Sales Trends**: Monthly sales analysis helps identify changes in revenue and growth compared with previous months.

* **Customer Segmentation**: Customers are divided into Gold and Silver segments based on their total spending.

* **City Performance**: Revenue analysis identifies the highest-performing cities based on total sales.

## Reports

* **Customer Report**: Customer order frequency, spending, segmentation, and Customer Lifetime Value.

* **Restaurant Report**: Restaurant revenue, popularity, growth, cancellation rates, and monthly order trends.

* **Delivery Report**: Rider delivery time, efficiency, earnings, and ratings.

* **Sales Report**: Monthly sales trends, revenue growth, order frequency, and city performance.

## Conclusion

This project provides a practical introduction to SQL for data analysis using a real-world food delivery scenario.

The analysis covers customer behavior, restaurant performance, delivery operations, sales trends, and revenue generation. By using SQL joins, aggregations, CTEs, window functions, ranking, and date functions, the project demonstrates how SQL can be used to answer business questions and generate useful insights from relational data.

## How to Use

1. **Clone the Repository**: Clone the project repository from GitHub.

2. **Set Up the Database**: Create a PostgreSQL database and run the SQL file to create the required tables.

3. **Load the Data**: Import the customer, restaurant, order, delivery person, and delivery data into the corresponding tables.

4. **Run the Queries**: Execute the SQL queries from Q1 to Q20 to perform the business analysis.

5. **Explore and Modify**: Modify the queries or create additional queries to explore other aspects of the food delivery business.

## Author - Hatem Elhadry

This project is part of my portfolio, showcasing SQL and data analysis skills through a real-world food delivery business case.

GitHub: https://github.com/Hatem207

LinkedIn: https://www.linkedin.com/in/hatem-el-hadary.
