# CODETECH-Task-4
# Name: Prajapati Udit Mukesh
# Company: CODTECH IT SOLUTIONS
# Id: CT12EHC
# Domain: SQL
# Duration: DECEMBER 17th, 2024 to FEBRUARY 17th, 2025.
# Mentor: Muzammil Ahmed

# Overview
The project involves creating and managing a database for a movie rental system. The database tracks movies, customers, rentals, and returns. It ensures data integrity through the use of primary and foreign keys, allowing for efficient rental operations, stock updates, and late fee calculations. The project includes handling complex queries and transactions for real-world scenarios.

# Key Activities
Database Design:
Created normalized tables (Movies, Customer, Rentals, and Returns) to store data efficiently.
Established relationships between tables using foreign keys.
Data Population:
Added sample records to Customer and Movies tables to facilitate testing.
Ensured foreign key constraints are respected during data insertion.
Transaction Handling:
Implemented SQL transactions to manage operations like rentals and returns securely.
Calculated late fees dynamically based on rental due dates.
Error Resolution:
Debugged issues related to foreign key constraints and data integrity.

# Technology Used
Database Management System: MySQL
Programming Language: SQL for querying and updates
Tools: MySQL Workbench for database design and query execution
Transaction Handling: ACID-compliant SQL commands for consistent operations

# Key Insights
Data Integrity:
Foreign key constraints ensure relational integrity between tables.
Error handling during rentals prevents stock from being decremented incorrectly.
Scalability:
The database design can easily scale to include additional features like user reviews or promotional discounts.
Efficiency:
Query optimization, such as using indices on frequently accessed columns, improves performance.
Transactions ensure atomicity, consistency, and durability of operations.
Real-World Application:
The system handles common edge cases, such as late returns and unavailable stock, making it practical for real-world scenarios.
