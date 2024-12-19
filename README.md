# Database and DBMS
A database is an organized collection of structured/unstructured data, typically stored electronically in a computer system.

A database management system (DBMS) is a collection of programs that allow you to create, manage, and operate a database. It serves as an interface between the database and its end users or programs, allowing users to retrieve, update, and manage how the information is organized and optimized.

# SQL
Structured Query Language

It is a programming language for storing and processing information in a database.

SQL Vs Programming language 
SQL is optimized to work with a databases. It is very fast in performing operations like retrieving, inserting, updating, and deleting data.

A general-purpose programming language like Python. It can be used for a wide range of tasks, including web development, data analysis, artificial intelligence, automation, and more. It is not optimised to work with databases.
SQL is much simpler to understand. Generally python is used to execute SQL code.


# Databases and Tables

A DBMS can have many databases. for e.g. marketplace, payments
A database can have many tables for e.g. marketplace can have tables like orders, customer etc.

Table is the one that actually contains data. We run most of the SQL queries on the tables.

Querying Data:
Syntax:
SELECT [COLUMN NAMES]

FROM [TABLE]



Filtering Data:
Syntax:

SELECT [COLUMN NAMES]

FROM [TABLE]

WHERE [CONDITIONS]

Null Values
NULL is like Nan in python which means no value provided for the column. We can not use = operator to match null values. It's an exception where we need to use "IS NULL" or "IS NOT NULL" with column


Grouping and Aggregating Data:
Syntax:

SELECT [COLUMN NAMES]

FROM [TABLE]

WHERE [CONDITIONS]

GROUP BY [COLUMN NAMES]

HAVING [AGGREGATE COLUMN CONDITIONS]

Views:
In SQL, a view is a virtual table that does not store the actual data itself but represents a stored query that can be executed whenever the view is referenced in a query.

Joins:
Joins are used to query data from multiple tables

<img width="632" alt="download" src="https://github.com/user-attachments/assets/eb1ecdab-5a49-4177-a55d-ce5468186901" />

