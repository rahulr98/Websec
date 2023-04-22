# SQL injection Attack #

  SQL injection attack is a type of cyber attack where an attacker injects malicious SQL (Structured Query Language) code into a database query through an input field on a website or application. The purpose of this attack is to gain unauthorized access to sensitive information or perform actions that they should not be able to perform.
  
  ## MySQL basics ##

  - *Log in to MySQL:* We will use MySQL database, which is an open-source relational database management system. We can log in using the following command:
 
 ![1](https://user-images.githubusercontent.com/116432525/233779622-2b5cf0e5-44e0-4921-89f6-25f717ab0d31.png)

  - *Create a Database:* Inside MySQL, we can create multiple databases. “SHOW DATABSES” command can be used to list existing databases. We will create a new database called dbtest
  
 ![3](https://user-images.githubusercontent.com/116432525/233779811-99727c50-9394-4c4a-a705-183f480493a0.png)

  - *Create a Table:* A relational database organizes its data using tables. Let us create a table called employee with six attributes (i.e. columns) for the database “dbtest.
 
 ![4](https://user-images.githubusercontent.com/116432525/233779868-1f4fdf6f-bad8-480e-8c48-31d9305c5e6c.png)

  - *Insert a Row:* We can use the INSERT INTO statement to insert a new record into a table.
  
 ![5](https://user-images.githubusercontent.com/116432525/233779921-cc634e09-16c9-49cf-8520-a0004efad3c3.png)

  - *SELECT Statement:* The SELECT statement is the most common operation on databases,It retrieves information from a database.
  
 ![6](https://user-images.githubusercontent.com/116432525/233779988-92469a11-e64f-4c04-ae64-e71c02ad2350.png)

  - *WHERE Clause:* WHERE clause is used to set conditions for several types of SQL statements including SELECT, UPDATE, DELETE etc. • The predicate is a logical expression; multiple predicates can be combined using eywords AND and OR
    
 ![7](https://user-images.githubusercontent.com/116432525/233780073-e127258b-365d-4bab-99e8-00ac8aa06a08.png)
 ![8](https://user-images.githubusercontent.com/116432525/233780078-cc2e4f33-e106-4308-9637-ac031f95291a.png)
 ![9](https://user-images.githubusercontent.com/116432525/233780384-97e3da87-030b-400a-973b-53829fd9f28a.png)
  *This 1=1 predicate looks quite useless in real queries, but it will become useful in SQL Injection attacks*
 
  -  *UPDATE Statement:* We can use the UPDATE Statement to modify an existing record.
 
 ![10](https://user-images.githubusercontent.com/116432525/233780281-173ed33f-86bd-4383-b719-f6aaa9761831.png)

# Interacting with Database in Web Application #
