Library Management Database
Description
This project is a SQL-based database schema for a Library Management System. It manages library operations such as tracking books, authors, members, and book loans. The database supports:

Storing author and book details, including many-to-many relationships between books and authors.
Managing member information and their loan history.
Tracking book availability and loan statuses with constraints to ensure data integrity.
Calculating fines for overdue loans.

The schema is designed for use in a relational database management system (RDBMS) like MySQL or MariaDB.
How to Run/Setup the Project
Follow these steps to set up and import the SQL schema:

Prerequisites:

Install a RDBMS such as MySQL or MariaDB.
Ensure you have a SQL client (e.g., MySQL Workbench, phpMyAdmin, or the MySQL command-line tool).


Import the SQL File:

Download the week 8 assignment.sql file from this repository.
Open your SQL client and connect to your RDBMS.
Create a new database (optional, as the SQL file includes a CREATE DATABASE statement):CREATE DATABASE library_management;


Import the SQL file:
In MySQL Workbench: Go to Server > Data Import and select the SQL file.
Via command line:mysql -u your_username -p library_management < week_8_assignment.sql

Replace your_username with your MySQL username and enter your password when prompted.




Verify Setup:

Check that the following tables are created: Authors, Members, Books, Book_Authors, and Loans.
Run a simple query to confirm:SHOW TABLES;




Usage:

Insert sample data into the tables (e.g., authors, books, members).
Use SQL queries to manage loans, check book availability, or calculate fines.



Entity-Relationship Diagram (ERD)
[Insert ERD screenshot or link here]
Note: To visualize the database schema, you can generate an ERD using tools like MySQL Workbench, DBeaver, or online platforms like dbdiagram.io. Export the ERD as an image and upload it to this repository, then update this section with the image or a link to it.
