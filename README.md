# Maven-Pizza-Sales

The Maven Pizza Dataset is a fictional dataset used for data analysis challenges on Maven Analytics. It contains annual sales data for a pizza restaurant, including details about orders, pizza types, sizes, prices, and ingredients.

##DataSet used

-<a href="https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/order_details.csv">OrderDetails</a>

-<a href="https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/orders.csv">Orders</a>

-<a href="https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/pizza_types.csv">PizzaTypes<a/>

-<a href="https://github.com/NaingLinnPhyoe28/Maven-Pizza-Sales/blob/main/pizzas.csv">PizzSales<a/>

## Dataset Overview

- Orders Table – Contains timestamps for each order placed.
- Order Details Table – Tracks the pizzas ordered, including type, size, and quantity.
- Pizza Types Table – Lists different pizza varieties, their categories, and ingredients.
- Pizzas Table – Provides pricing details based on size and type.

## KPI

-Figure out the best order item and least order item.

-Revenue by dayname a week.

-Finding the peak months by sales and determine the traffic periode for sales forcasting.


## Step By Step Breakdown
-CSV file upload and ETL process in query

-Data Modelling with the tables
![Screenshot 2025-05-25 120322](https://github.com/user-attachments/assets/35e2b093-fee5-493f-87d7-e07d465dda1e)

-Set up DAX Measures for appropiate insights

-Data Visualization on canvas


## Creating Landing Page
DAX Used
Total Order = COUNT(orders[order_id])
Total Revenue = SUM(order_details[Total Price])

![Landing_Page](https://github.com/user-attachments/assets/65bfe69d-bd26-497c-a869-e8edc4e81b13)

## Creating Menue List
Pizza Type was changed into Menue List by Table Format 
![Menue_List](https://github.com/user-attachments/assets/4af7a9c2-f66f-48a5-8dfc-05869f8d43f2)

## Order Insights

Peak Month: July stands out as the highest order month with 1935 orders, possibly due to seasonal demand or promotions during this time.
Moderate Months: January, March, May, and August consistently perform well, maintaining order quantities close to or above 1800.
Low Periods: October records the lowest number of orders at 1646, closely followed by September and December. These months could represent a slower business period, possibly due to reduced customer demand.

Dax Used
Total Order = COUNT(orders[order_id])
Filter option is used to determine the most order and least order.

![Order_Insights](https://github.com/user-attachments/assets/0d2c4467-79c8-434d-83e4-2e3a12978030)

## Revenue Insights

Dax Used 
Total Revenue = SUM(order_details[Total Price])

![Revenue_Insights](https://github.com/user-attachments/assets/6b9ead2c-89da-4a22-8152-7ebdb769f456)

## Traffic Hours
Dax Used
Total Order = COUNT(orders[order_id])
Total Revenue = SUM(order_details[Total Price])

![Traffic_Hours_Insights](https://github.com/user-attachments/assets/fcb34c68-ee6b-4acc-bb9e-c82b4597b783)



