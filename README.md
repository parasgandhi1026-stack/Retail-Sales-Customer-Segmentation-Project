# Customer Order & Revenue Analysis System

This project is a comprehensive retail sales data analytics system built using SQL with a focus on analyzing customer orders, product sales, and revenue patterns. It includes detailed queries to explore customer purchase behavior, calculate profits, identify late shipments, and segment customers based on their spending habits.

## Features

- Customer Purchase Insights
- Profit Calculation per Order Line
- Order Aging Analysis
- Late Shipment Analysis
- Customer Segmentation (Low, Medium, High spenders)
- Return Gap Analysis using LAG()
- Relational data model with Customers, Orders, Products, Order Details

## Database Schema

- Customers (Customer_id, Customer_name, Gender, City, Join_date)
- Products (Product_id, Product_name, Category, Unit_price)
- Orders (Order_id, Customer_id, Order_date, Ship_date, Order_Status)
- Order_Details (Detail_id, Order_id, Product_id, Quantity, Price, Discount)

## Usage

1. Create tables using the provided SQL scripts.
2. Insert sample data.
3. Run SQL queries for analysis.
4. Customize queries as per your requirements.

---

Feel free to contribute and suggest improvements.
