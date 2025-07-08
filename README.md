# Pizza-Sales-Analysis-with-POWER BI

# **Introduction**

This project focuses on analyzing a years 2023 pizza sales data using POWER BI. We'll explore various aspects of the dataset, including order quantities, revenue, pizza types, and more. The goal is to gain insights that can inform business decisions related to pizza sales.

# **Dataset** Project Overview:

This POWERBI project revolves around a database PIZZA_PROJECTS dashboard designed to manage and analyze data for a pizza store. The database consists of four primary tables:

order_details, pizzas, order_year 2023 and pizza_types.

Each table plays a crucial role in storing different facets of the business operations, from individual orders to the types of pizzas offered. Below is a detailed description of each table and its columns:

1. order_details_year 2023:
— order_details_id: A unique identifier for each entry in the order details.
— order_id: References the ID from the orders table, linking the order detail to a specific order.
— pizza_id: References the ID from the pizzas table, identifying which pizza was ordered.
— quantity: The number of pizzas ordered of the specified type.

2. pizzas:
— pizza_id: A unique identifier for each type of pizza available.
— pizza_type_id: Links to the pizza_types table, specifying the type of pizza.
— pizza_size: The size of the pizza (e.g., small, medium, large).
— price: The cost of the pizza.

3. order_year 2023:
— order_id: A unique identifier for each order placed.
— order_date: The date on which the order was placed.
— order_time: The time at which the order was placed.

4. pizza_type:
— pizza_type_id: A unique identifier for each type of pizza.
— category: Categorizes the pizza (e.g., Vegetarian, Non-Vegetarian).
— ingredients: Lists the ingredients used in the pizza.

# **Basic Questions**

1. Which pizza types contributed the most revenue each year 2023?
2. Top 5 best-selling pizza sizes by quantity and revenue in the year?
3. Monthly revenue trend across years—any seasonal patterns?
4. Which day of the week has highest orders and revenue?
5. Which pizzas have highest avg quantity per order?
6. Rank pizza types within each category by total revenue per year.
7. Rank pizza types by total quantity sold per year.
8. Which sizes dominate within each pizza type (e.g. XL for Meat Lovers)?
9. Top 10 highest-revenue orders and pizzas involved?
10. Average price per pizza (adjusted by quantity) per order?

# **Recommendations:**
**Staffing and Inventory Management**: Increase resources during peak order times (lunch and dinner hours) to ensure smooth operations.

**Menu Optimization**: Focus on promoting and potentially expanding the menu options for Classic and Supreme pizzas, as they generate the most revenue.

**Marketing**: Consider targeted promotions for less popular pizza sizes (e.g., XL, XXL) to increase their sales, or evaluate if these sizes should be continued.

**Customer Preferences**: Maintain a balance of both vegetarian and meat-based pizza offerings, as they appeal to a wide audience.
