# Zomato-Data-Analysis

## Project Overview

- **Goal**: Analyze Zomato's delivery data to derive actionable insights for optimizing delivery operations, enhancing customer satisfaction, and improving restaurant partnerships.
- **Objective**: Identify key trends, customer behavior patterns, and restaurant performance metrics to support data-driven decision-making.
- **Approach**: Perform exploratory data analysis (EDA) to calculate KPIs, generate metrics, and create insightful visualizations.

## Problem Statement

- The dataset contains records of food orders, customer demographics, and restaurant information. The company aims to leverage this data to understand delivery performance, customer preferences, and restaurant popularity.
- Insights from this analysis will inform strategies for improving delivery efficiency, targeting specific customer segments, optimizing marketing campaigns, and refining restaurant collaborations.

## Dataset Overview

### Orders
- `Order_ID`: Unique identifier for each order.
- `Restaurant_ID`: Identifier for the restaurant fulfilling the order.
- `Order_Date`: Date when the order was placed.
- `Expected_Delivery_Time`: Expected time (in minutes) for order delivery.
- `Actual_Delivery_Time`: Actual time (in minutes) taken to deliver the order.
- `Total_Amount`: Total monetary value of the order.
- `Order_Status`: Status of the order (e.g., completed, cancelled).
- `Payment_Method`: Method used for payment (e.g., cash, credit card, UPI).
- `Dish_Name`: Name of the dish ordered.
- `Customer_ID`: Identifier for the customer who placed the order.

### Customers
- `Customer_ID`: Unique identifier for each customer.
- `Customer_Location`: Location of the customer.
- `Customer_Age_Group`: Age group category of the customer (e.g., 18-25, 26-35).
- `Customer_Rating`: Average rating given by the customer.
- `Customer_Name`: Name of the customer.

### Restaurants
- `Restaurant_ID`: Unique identifier for each restaurant.
- `Name`: Name of the restaurant.
- `Location`: Location of the restaurant.
- `Cuisine_Types`: Types of cuisine offered by the restaurant (e.g., Italian, Chinese).
- `Avg_Cost_for_Two`: Average cost for two people at the restaurant.
- `Ratings`: Average rating of the restaurant.
- `Reviews_Count`: Number of reviews the restaurant has received.
- `Operational_Hours`: Hours during which the restaurant operates.

## Key Performance Indicators (KPIs)

1. **Total Revenue Generated & Number of Orders Placed**
2. **Average Value Per Order [AOV]**
3. **Average Delivery Time**
4. **Cancellation Rate**
5. **Number of Orders by Hour**
6. **Numbers of Orders by Days of the Week**
7. **Numbers of Orders by Month**
8. **Revenue Generated Over Months**
9. **Top 10 Dishes as per Reveue Contribution**
10. **Top 10 Dishes as per Number of Orders**
11. **Top 5 Dishes as per Location**
12. **Top 5 Cuisines as per Location**
13. **Top 10 Cuisines as per Revenue Contribution & Number of Orders**
14. **Top 10 Locations as per Number of Orders & Revenue Contribution**
15. **Number of Orders & Revenue Contribution by Age Group**
16. **Number of Orders by Age Group and Location**
17. **Average Customer Rating**
18. **Top 3 Cuisines as per Customer Age Group**
19. **Top 5 Restaurants for each Location based on Number of Orders & Revenue Contribution**
20. **Top 5 Restaurants for each Location based on Number of Reviews & Average Rating**