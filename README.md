# [Application Software Lab](./README.md)

 ## Lab 1

 1. Create a table student with attributes sno,name marks and dept
 2. Add a new attribute age
 3. Change the datatype size of dept
 4. Delete the attribute marks from the table
 5. Change the name of the student table to students
 6. Delete all values from the table
 7. Delete the entire table

 <b>SOLUTION</b> : [SQL FILE](./Lab1/Lab1.sql)

<br>

 ## Lab 2

 1. Create a table Employee with following specifications. Code character (4), name character (10), designation character(30), dob date, salary numeric.
 2. Insert 2 tuples into the table
 3. Select all details from the table. 
 4. Change the salary of employee code is e1.
 5. Delete a tuple from the table employee

 <b>SOLUTION</b> : [SQL FILE](./Lab2/Lab2.sql) <br>
 <b>WITH O/P</b> : [SQL FILE](./Lab2/Output.sql)


<br>

## Lab 3

1.	Create table employdetails with empid references to the empid in employee table
2.	Display the details of employee table where empid in employdetails table
3.	Display the details of employee table where empid not in employdetails table

<b>SOLUTION</b> : [SQL FILE](./Lab3/Lab3.sql) <br>
<b>WITH O/P</b> : [SQL FILE](./Lab3/Output.sql) <br>

## Lab 4

Create and insert values for the following tables department and instructor(with constarints)
1.	<b>Department table</b>  
     Code(primary key), 
     Title, 
     Dept_name(unique), 
     Dept_id, 
     Salary(check –salary>2000)
2.	<b>Instructor table</b>  
     Name(not null), 
     Code, 
     Id(default)
     
<b>SOLUTION</b> : [SQL FILE](./Lab4/Lab4.sql) <br>
<b>WITH O/P</b> : [SQL FILE](./Lab4/Output.sql)

## Lab 5

1.	Create a table class. Fields are name and id
2.	Insert values into the table
3.	Display the table
4.	Apply commit, save point and rollback commands

<b>SOLUTION</b> : [SQL FILE](./Lab5/Lab5.sql) <br>
<b>WITH O/P</b> : [SQL FILE](./Lab5/output.sql) <br>

## Lab 6

<b>Creation of Views and Assertions</b>
1. Create a table store. Fields are order no, code, item, quantity, price, discount, mrp
2. Insert values into the table
3. Display the table
4. Create a view with item_name and quantity for the above table
5. Write a query to check whether any changes made to present table is reflected in view.
6. Write a query to delete a view

<b>SOLUTION</b> : [SQL FILE](./Lab6/Lab6.sql) <br>
<b>WITH O/P</b> : [SQL FILE](./Lab6/output.sql) <br>
