## College Database Design ##

This repository contains the ER diagram and SQL implementation of a College Database System, created as part of a DBMS assignment/project.


## Project Overview ##

The objective of this project is to design a structured college database using:

Entity Relationship (ER) modeling

Relational database tables

Proper use of primary and foreign keys


The database efficiently represents departments, students, faculty members, courses, and enrollments.


## Entities Included ##

Department – Stores department details

Student – Stores student information

Faculty – Stores faculty information

Course – Stores course details

Enrollment – Handles the many-to-many relationship between students and courses



## Relationships ##

One department can have multiple students, faculty members, and courses

One faculty member can teach multiple courses

A student can enroll in multiple courses

A course can have multiple students

The many-to-many relationship between Student and Course is resolved using the Enrollment table

## ER Diagram ##

The ER diagram visually represents the entities, their attributes, and the relationships between them.

 `File: ER_Diagram.png`



## SQL Implementation ##

The SQL file includes CREATE TABLE statements for all entities with:

Proper primary keys

Foreign key constraints

Normalized table structure





---

## Tools Used ##

draw.io (diagrams.net) – For creating the ER diagram

Oracle SQL / MySQL – For writing and executing SQL queries

GitHub – For version control and project submission





## Repository Structure ##

college-database-design
 ├── ER_Diagram.png
 ├── college_database.sql
 └── README.md


## Conclusion ##

This project demonstrates a clear understanding of database design concepts, ER modeling, and SQL-based relational schema implementation.



 Created for academic purposes (DBMS Project)
