The client faced several challenges:

Understanding the total number of orders placed.
Calculating the total revenue generated from pizza sales.
Identifying the highest-priced pizza.
Determining the most common pizza size ordered.
Listing the top 5 most ordered pizza types along with their quantities.
Finding the total quantity of each pizza category ordered.
Analyzing the distribution of orders by hour of the day.
Determining the category-wise distribution of pizzas.
Calculating the average number of pizzas ordered per day.
Identifying the top 3 most ordered pizza types based on revenue.
Calculating the percentage contribution of each pizza type to total revenue.
Analyzing cumulative revenue generated over time.
Identifying the top 3 most ordered pizza types based on revenue for each pizza category.

How We Solved the Problem:

To address these challenges, I performed the following steps:

> Data Retrieval:
   Retrieved the total number of orders placed using SQL aggregate functions.
   Calculated total revenue by summing up the sales amounts from the relevant tables.

> Data Analysis:
   Identified the highest-priced pizza by sorting the pizza prices in descending order.
   Determined the most common pizza size using SQL grouping and counting functions.
   Listed the top 5 most ordered pizza types by joining the orders and pizzas tables, then using aggregate 
   functions to count the quantities.

> Advanced Analysis:
  Joined necessary tables to find the total quantity of each pizza category ordered.
  Analyzed the distribution of orders by hour of the day using SQL time functions.
  Determined the category-wise distribution of pizzas by grouping data based on categories.
  Grouped orders by date to calculate the average number of pizzas ordered per day.
  Identified the top 3 most ordered pizza types based on revenue by summing sales amounts and sorting 
  them.

> Revenue Analysis:
   Calculated the percentage contribution of each pizza type to total revenue using ratio functions.
   Analyzed cumulative revenue over time to understand sales trends.
   Identified the top 3 most ordered pizza types based on revenue for each category by filtering and sorting 
   data.
