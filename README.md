Bike Rental System – DBMS Project

Overview

This project implements a Bike Rental System using MySQL. The database stores customer, bike, rental, and payment information and uses SQL queries to retrieve and analyze rental data.

Database Structure

The database contains 4 tables:

Customers – stores customer ID, name, and phone number.

Bikes – stores bike ID, model, type, daily rent, and availability status.

Rentals – stores rental details and connects customers with bikes.

Payments – stores payment details linked to rentals.

Project Details

Database: MySQL

Tables: 4

Sample records: 31

SQL queries: 20

Main SQL concepts: JOIN, GROUP BY, aggregate functions, subqueries, filtering, transactions

SQL Queries

The project includes 20 queries covering:

Available bikes

Ongoing rentals

Total number of bikes

Customer, bike, and rental-date details

Revenue by bike

Amount spent by each customer

Rental count by bike

Most rented bike

Bikes never rented

Customers who never rented

Bikes priced above average

Rentals without recorded payment

Customer with maximum spending

Rentals with payment above average

Rentals lasting more than 2 days

Longest-running current rental

UPDATE with ROLLBACK

UPDATE with COMMIT

Current user grants

Current user information

How to Run

Open MySQL Workbench or another MySQL client.

Open bike_rental_system.sql.

Run the script from top to bottom.

The database project1 and its 4 tables will be created.

The sample data will be inserted.

Run the queries individually to view their results.

Files

bike_rental_system.sql – table creation, sample data, and 20 SQL queries.

README.md – project description and usage instructions.

Note

Queries 19 and 20 are kept as they appear in the original project document.