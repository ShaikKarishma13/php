# php

🔹 Overview of the Project

This project is a Student Management System developed using PHP, MySQL, HTML, CSS, and XAMPP.
It performs CRUD operations:

Create – Add student

Read – View student records

Update – Edit student

Delete – Remove student
XAMPP is a free local server package used to run PHP applications.

Components:

X – Cross-platform

A – Apache (Web Server)

M – MySQL (Database)

P – PHP (Server-side language)

Apache runs PHP files, and MySQL stores data.

🔹 Apache Server

Apache is a web server

It handles HTTP requests from the browser

Executes PHP files and sends HTML output to the browser

🔹 PHP (Hypertext Preprocessor)

PHP is a server-side scripting language.

Why PHP is used:

Handles form data

Connects with databases

Performs CRUD operations

Generates dynamic web pages

PHP code runs on the server, not in the browser.


🔹 MySQL Database

MySQL is a relational database management system (RDBMS).

Used for:

Storing student details

Managing structured data using tables

Executing SQL queries

Example table:

students(id, name, email, phone, course)

🔹 phpMyAdmin

A web-based interface to manage MySQL

Used to:

Create databases

Create tables

Run SQL queries

View stored records

SQL operations used:

CREATE – Create database/table

INSERT – Add student

SELECT – Fetch records

UPDATE – Modify data

DELETE – Remove data


🔹 Database Connection (db.php)

Establishes connection between PHP and MySQL

Uses mysqli extension

Ensures reusable and secure connection

Included in all PHP files using include


🔹 HTML (HyperText Markup Language)

HTML is used to:

Create page structure

Display forms, tables, buttons

Show student records in tabular format


🔹 CSS (Cascading Style Sheets)

CSS is used for:

Page layout

Colors, fonts, spacing

Improving UI and readability

File used: style.css


🔹 Forms

HTML forms are used to:

Collect user input

Send data to PHP using POST or GET methods


🔹 Conclusion

This project demonstrates how PHP interacts with MySQL to build a dynamic web application.
Using XAMPP, the system performs complete CRUD operations with proper database connectivity, form handling, and UI design.

