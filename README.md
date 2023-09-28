# F2_DBMS


# EXP NO 1: DATA DEFINITION LANGUAGE COMMANDS IN RDBMS


# AIM:

To create a student database and execute DDL queries using SQL.



# DDL (Data Definition Language)

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database

schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of

database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database

structures but not data. These commands are normally not used by a general user, who should be accessing the

database via an application



# List of DDL commands:


CREATE: This command is used to create the database or its objects (like table, index, function, views, store


procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to


alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces


allocated for the records are removed. RENAME: This is used to rename an object existing in the database.



# Query:


1) Create a table student with the following fieds rollno,name,age,address,phoneno.


SQL QUERY: 


create table student(rollno numeric(4), name varchar(50), age numeric(2), address varchar(10), phoneno numeric(10));


OUTPUT:


<img width="613" alt="image" src="https://github.com/AlluguriSrikrishnateja/F2_DBMS/assets/118343892/29fcdd94-e003-492c-9f3e-eee9fd45d026">



2) Change the above student table by adding another attribute department.


SQL QUERY:




alter table student add department varchar(10);



OUTPUT:


<img width="623" alt="image" src="https://github.com/AlluguriSrikrishnateja/F2_DBMS/assets/118343892/06af2051-da64-49cd-ad2c-495aeab4cbed">




3) Drop the student table


SQL QUERY:


   drop table student;


           
OUTPUT:

<img width="295" alt="image" src="https://github.com/AlluguriSrikrishnateja/F2_DBMS/assets/118343892/43100b74-7a5d-4ae4-9eb2-efe05e2aaa0a">





4) Delete the student table using truncate keyword

SQL QUERY:


  truncate table mystudent;


  

OUTPUT:


<img width="286" alt="image" src="https://github.com/AlluguriSrikrishnateja/F2_DBMS/assets/118343892/eed2ba30-2769-44cf-9fa5-b264aed25cd5">



5) Rename the student table to mystudent

SQL QUERY:

  rename student to mystudent;

OUTPUT:


<img width="383" alt="image" src="https://github.com/AlluguriSrikrishnateja/F2_DBMS/assets/118343892/8b5b3f3a-add8-489e-ba3d-3ff163c195c6">


# RESULT: 

Creating a student table and executing the DDL queries using SQL was successfully executed.






