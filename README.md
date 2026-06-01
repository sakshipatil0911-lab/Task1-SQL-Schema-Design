# Task1-SQL-Schema-Design

## Task Name
Database Setup and Schema Design

## Objective
To learn how to create databases, tables, primary keys, foreign keys, and define relationships between tables.

## Domain Chosen
E-Commerce Management System

## Tables Created

### Customers
Stores customer information.

### Products
Stores product details and inventory information.

### Orders
Stores order information placed by customers.

### Order_Items
Stores products associated with each order and quantity purchased.

## Relationships

1. One Customer can place many Orders (1:M)
2. One Order can contain many Products
3. One Product can appear in many Orders
4. Order_Items acts as a junction table between Orders and Products

## Concepts Used

- DDL (Data Definition Language)
- Primary Key
- Foreign Key
- Auto Increment
- Normalization
- ER Diagram

## Tools Used

- MySQL Workbench
- GitHub

## Deliverables

- schema.sql
- ER_Diagram.png
- README.md
