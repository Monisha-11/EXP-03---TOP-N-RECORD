# EXP 17 - CREATE A SQL PROGRAM TO SHOW THE TOP N RECORDS USING LIMITS.

## AIM:

 To show the n number of given columns by uing the LIMIT method in SQL.
 
## ALGORITHM:

1) Create a sample table in SQL using CREATE TABLE syntax
2) Insert all the values and Titles respectively using INSERT INTO syntax
3) Now check whether all the rows are affected or not by fetching the table
4) After checking, now use SELECT for choosing the column name that we meant to sort and use FROM to choose the table
5) Then use LIMIT syntax to limit the number of columns to be displyed as a result.
6) After compiling and running the program, the results will be displayed.

## PROGRAM:
```java
create table Employee(
  Sno int,
  Department varchar(50),
  No_of_workers int
);
insert into Employee (Sno,Department,No_of_workers)
values (1,'Development',15);
insert into Employee (Sno,Department,No_of_workers)
values (2,'Frontend Dv',10);
insert into Employee (Sno,Department,No_of_workers)
values (3,'Backend DV',7);
insert into Employee (Sno,Department,No_of_workers)
values (4,'Finance MM',8);
insert into Employee (Sno,Department,No_of_workers)
values (5,'Designer',12);
insert into Employee (Sno,Department,No_of_workers)
values (6,'Marketing',25);
insert into Employee (Sno,Department,No_of_workers)
values (7,'Chief heads',4);
insert into Employee (Sno,Department,No_of_workers)
values (8,'Law persuit',3);

select *from Employee
limit 5;
```

## OUTPUT:

<img width="421" alt="image" src="https://github.com/Monisha-11/EXP-03---TOP-N-RECORD/assets/93427240/e7b1cdd8-718b-43f9-b271-e8e21bb3cd86">


## RESULT:

Thus we have successfully obtained the required result using the above-given code.
