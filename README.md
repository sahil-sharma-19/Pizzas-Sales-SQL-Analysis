# Pizzas-Sales-SQL-Analysis
This project delivers an in-depth analysis of pizza restaurant sales using SQL queries. Leveraging a real-world sales dataset, the analysis uncovers key business insights—including total and average sales, top-performing pizza types, sales patterns by size and category, revenue contributions, and ordering trends by time of day. The repository contains all necessary SQL scripts, query results, and a summary of findings, providing actionable information for optimizing menu offerings and improving sales strategy.
## Key Technologies Used
SQL (Structured Query Language): For querying, aggregating, and analyzing the dataset.

 MySQL is the DBMS used for the queries.
 
## Data Source Information
The dataset contains pizza sales transactions from a restaurant, including order details, pizza types, prices, sizes, categories, timestamps, and quantities sold.

Source: [Public dataset, Kaggle]

## Features and Highlights
Retrieves overall order and sales statistics (order count, total revenue)

Identifies top/bottom pizzas by sales, revenue, and order quantity

Analyzes pizza sales by category (Chicken, Veggie, Supreme, Classic, etc.)

Tracks sales trends over time (hourly, daily, monthly distributions)

Highlights best-selling pizza sizes and types

Calculates each pizza’s share of total revenue and overall performance

Provides actionable insights for menu optimization and sales strategy.
## Insights
1. Retrieve the total number of orders placed.

Answer:
A total of 21350 orders were placed during the analyzed period.

2. Calculate the total revenue generated from pizza sales.
   
Answer:
The total revenue generated from pizza sales is $817,860.

3. Identify the highest-priced pizza.
   
Answer:
The highest-priced pizza is The Greek Pizza at $35.95.

4. Identify the most common pizza size ordered.
   
Answer:
The most commonly ordered pizza size is Large i.e. 18526 orders.

5. List the top 5 most ordered pizza types along with their quantities.
    
Answer:
The top 5 most ordered pizza types by quantity are:

The Classic Deluxe Pizza – 2453 orders

The Barbecue Chicken Pizza – 2432 orders

The Hawaaiian Pizza – 2422 orders

The Pepperoni Pizza - 2418 orders

The Thai Chicken Pizza - 2371 orders

6. Join the necessary tables to find the total quantity of each pizza category ordered.
   
Answer:
Order quantities by pizza category:

Chicken – 11050 pizzas

Classic – 14888 pizzas

Supreme – 11987 pizzas

Veggie – 11649 pizzas

7. Determine the distribution of orders by hour of the day.
   
Answer:
Orders peak between 12 PM and 1 PM, with the highest activity at 6 PM.

8. Join relevant tables to find the category-wise distribution of pizzas.
    
Answer:
The menu’s pizza types per category are:

Chicken – 6 types

Classic – 8 types

Veggie – 9 types

Supreme – 9 types

9. Group the orders by date and calculate the average number of pizzas ordered per day.
    
Answer:
On average, 138 pizzas are ordered per day.

10. Determine the top 3 most ordered pizza types based on revenue.
    
Answer:
Top 3 pizzas by revenue:

Chicken-The Thai Chicken Pizza-$43434.25

Chicken-The Barbecue Chicken Pizza-$42768

Chicken-The California Chicken Pizza-$41409.5

Classic-The Classic Deluxe Pizza-$38180.5

Classic-The Hawaiian Pizza-$32273.25

Classic-The Pepperoni Pizza-$30161.75

Supreme-The Spicy Italian Pizza-$34831.25

Supreme-The Italian Supreme Pizza-$33476.75

Supreme-The Sicilian Pizza-$30940.5

Veggie-The Four Cheese Pizza-$32265.7

Veggie-The Mexicana Pizza-$26780.75

Veggie-The Five Cheese Pizza-$26066.5

