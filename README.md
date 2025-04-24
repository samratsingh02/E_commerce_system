# E_commerce_system
This is E- commerce database system which i made with the help of the course provided by the company pixelfactor Solutions from where i learned about basic and Advanced level of SQL and DBMS concept. I became familiar with the real world project which is an direct exposure for the companies work.
This SQL project implements a fully-functional E-Commerce system.
It includes user management, product catalog, order tracking, payment processing, report generation, and
administrative access control.
It is normalized, optimized with indexes, uses triggers and stored procedures, and enforces security best
practices.

In this project i Have used:-

- Users: Stores customer and admin information with role-based differentiation.
- Products: Product catalog with price, stock, and category.
- Orders: Tracks each order with status and total amount.
- Order_Items: Line items within each order, linking products and quantity.
- Payments: Payment details for each order.
- Reports: Admin-generated reports with timestamp
- 
1)Normalized data which help my code abilty faster to fetch the data.
2)Indexing technique on several query fields.
3)Triggers for :-
              a) payment insertion -- which immediately invoke and adds a payment row.
              b)order_item update -- which update the product item when any item is insterted.
              
4)Stored-Procedures :-
              a) GetUserOrderSummary(uid): Returns a summary of orders and payments for a user.
              b) GenerateSalesReport(): Aggregates sales data per product category for reporting. 
              
5)
