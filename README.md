# Maven-Pizza-Sales
The Maven Pizza Dataset is a fictional dataset used for data analysis challenges on Maven Analytics. It contains annual sales data for a pizza restaurant, including details about orders, pizza types, sizes, prices, and ingredients.

##Data Set use
https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/order_details.csv
https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/orders.csv
https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/pizza_types.csv
https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/pizzas.csv

##Dataset Overview
- Orders Table – Contains timestamps for each order placed.
- Order Details Table – Tracks the pizzas ordered, including type, size, and quantity.
- Pizza Types Table – Lists different pizza varieties, their categories, and ingredients.
- Pizzas Table – Provides pricing details based on size and type.

## Step By Step Breakdown
-CSV file upload and ETL process in query
-Data Modelling with the tables
-Set up DAX Measures for appropiate insights
-Data Visualization on canvas

##Creating Landing Page
DAX Used
Total Order = COUNT(orders[order_id])
Total Revenue = SUM(order_details[Total Price])

![Alt text](relative/path/to/image.jpg?raw=true "Landing_Page.png")


