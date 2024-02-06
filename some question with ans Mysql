## A                                            Student Table:
Student_ID 	Stu_Name 	       Subject _ID 	  Stu_Marks 	      Stu_Age
101 		Akhil 		          BCA101  		85     		 20
102 		Balram 		BCA104 		78 		 19
103 		Bheem 		BCA102 		80 		 22
104 		Chetan 		BCA103 		95 	 	 20
105 		Diksha 		BCA104 		99 		 20
106 		Raman 		BCA105 		88 		 19
107 		Sheetal 	          BCA103 		98 		 22
Subject Table:

Subject_ID 	    Subject_Name
BCA101 		C
BCA102 		C++
BCA103 		Principle of Management
BCA104 		Core Java
BCA105 		Math
BCA106 		Android

#### Query 1: Write a query to create the table in Structured Query Language.

Answer
CREATE TABLE student
(
    s_id int,
    s_name varchar(255),
    sub_id varchar(20),
    sub_mar double(4,2),
    age int
)
CREATE TABLE  subject
(
    sub_id int NOT NULL,
    sub_name varchar(255),
    PRIMARY KEY(sub_id)
)
Query 2: Write a query to insert the data into the table.

Answer:
INSERT INTO student
VALUES
(101,'Akhil', 'BCA101',85,20),
(102,'Balram','BCA104',78,19),
(103,'Bheem','BCA102',80,22),
(104,'Chetan','BCA103',95,20),
(105,'Diksha','BCA104',99,20),
(106,'Raman','BCA105',88,19),
(107,'Sheetal','BCA103',98,22)

INSERT INTO subject
VALUES
('BCA101','C'),
('BCA102','C++'),
('BCA103','Principle of Management'),
('BCA104','Core Java'),
('BCA105','Math'),
('BCA106','Android')

Query 3: Write a query to view the specific record of the table by using the WHERE clause.

ANSWER :
SELECT *
FROM student
WHERE s_id=101;

Query 4: Write a query in SQL to find the minimum and maximum number from the integer/student marks column:

ANSWER : 
SELECT MAX(sub_mar),MIN(sub_mar)
FROM student;

Query 5: Write a query to access the first record from the SQL table?

ANSWER :
SELECT *
FROM student LIMIT 1;



Query 6: Write a query to access the last record from the table?

ANSWER:
 SELECT * 
FROM `student`ORDER BY s_id DESC LIMIT 1;

Query 7: Write a query to access the first Nth rows from the table?

ANSWER:
SELECT * 
FROM `student`LIMIT 5;

Query 8: Write a query to access the last Nth rows from the SQL table?

ANSWER:
   SELECT*
FROM student ORDER by s_id DESC LIMIT 3;

Query 9: Write a query to show the record of those students whose name begins with the 'm' character

ANSWER:
SELECT*
FROM student
WHERE s_name LIKE 'm%';

Query 10: Write a query in structured query language to view all student details from the Student table order by Stu_Name Descending.

ANSWER:
SELECT*
FROM student ORDER by s_name DESC;








##B
 
EmployeeID	FirstName	LastName	Department	Salary
1	John	Smith	HR	50000
2	Jane	Doe	IT	60000
3	Bob	Johnson	Finance	55000
4	Mary	Brown	IT	62000
5	Alice	White	Sales	48000
 SQL Questions : 
1.	*Question: Retrieve the first and last names of all employees.
ANSWER:
SELECT first_name,last_name
FROM employee;

2.	*Question: List the employees who work in the IT department. 

ANSWER:
SELECT * 
FROM `employee` 
WHERE dept='IT';

3.	*Question: Calculate the average salary of all employees. 

ANSWER:
SELECT AVG(salary) AS AVARAGE_salary
FROM employee;


4.	*Question: Find the highest salary among all employees. 

ANSWER:
SELECT MAX(salary)
FROM employee;

5.	*Question:* Count the number of employees in each department. 

ANSWER:
SELECT dept,COUNT(*)As num
FROM employee
GROUP BY dept;
6.	*Question:* Retrieve the employees with salaries greater than $55,000 and in the HR or Finance department. 
ANSWER:
SELECT*
FROM employee
WHERE salary>=55000 AND(dept='HR 'OR dept='Finance');

7.	*Question:* List the employees with names containing "a" in their first name. 

ANSWER:
SELECT*
FROM employee
WHERE first_name LIKE '%a%';

8.	*Question:* Calculate the total salary expenditure for the company. 

ANSWER:
SELECT SUM(salary)
FROM employee;

9.	*Question:* Find the employee with the lowest salary. 

ANSWER:
SELECT *
FROM employee ORDER BY salary ASC LIMIT 1;

10.	*Question:* Update the salary of Bob Johnson to $56000

ANSWER:
UPDATE employee
SET salary=56000
WHERE first_name = 'Bob' AND last_name = 'Johnson';






##C 
 
Q-1. Write an SQL query to fetch “FIRST_NAME” from the Worker table using the alias name <WORKER_NAME>. 
ANSWER:
SELECT FIRST_NAME
FROM Worker;

Q-2. Write an SQL query to fetch “FIRST_NAME” from the Worker table in upper case. 
ANSWER :
SELECT UPPER(FIRST_NAME) AS UPPER_FIRST_NAME
FROM Worker;

Q-3. Write an SQL query to fetch unique values of DEPARTMENT from the Worker table. 
	ANSWER :
SELECT DISTINCT DEPARTMENT
FROM Worker;

Q-4. Write an SQL query to print all Worker details from the Worker table order by FIRST_NAME Ascending. 

ANSWER :
SELECT *
FROM Worker
ORDER BY FIRST_NAME ASC;

Q-5. Write an SQL query to print all Worker details from the Worker table order by FIRST_NAME Ascending and DEPARTMENT Descending. 

ANSWER:
SELECT *
FROM Worker
ORDER BY FIRST_NAME ASC, DEPARTMENT DESC;

Q-6. Write an SQL query to print details for Workers with the first names “Vipul” and “Satish” from the Worker table. 


ANSWER:
SELECT *
FROM Worker
WHERE FIRST_NAME IN ('Vipul', 'Satish');

Q-7. Write an SQL query to print details of workers excluding first names, “Vipul” and “Satish” from the Worker table. 

ANSWER:
SELECT *
FROM Worker
WHERE FIRST_NAME IN ('Vipul', 'Satish');

Q-8. Write an SQL query to print details of the Workers whose FIRST_NAME contains ‘a’. 

ANSWER: 
SELECT *
FROM Worker
WHERE FIRST_NAME LIKE '%a%';

Q-9. Write an SQL query to print details of the Workers whose SALARY lies between 100000 and 500000
ANSWER:
SELECT *
FROM Worker
WHERE SALARY BETWEEN 100000 AND 500000;

Q-10. Write an SQL query to fetch the no. of workers for each department in descending order. 

ANSWER:
SELECT DEPARTMENT, COUNT(*) AS NumberOfWorkers
FROM Worker
GROUP BY DEPARTMENT
ORDER BY NumberOfWorkers DESC;

##D
QUESTION 1. How do you select all columns from a table named "employees"?  

Answer:	 	
SELECT *
 FROM employees;

QUESTION 2. What is the SQL command to retrieve unique values from a column named 
"city" in a table named "customers"? 
Answer:	 	
SELECT DISTINCT city
FROM customers;

QUESTION 3. How do you count the number of records in a table named "orders"?  
Answer:	 	
SELECT COUNT(*)
FROM orders;


QUESTION 4. What is the SQL command to retrieve all orders placed by a specific customer with the ID 123?  
Answer:	 	
SELECT * 
FROM orders
WHERE customer_id = 123;

QUESTION 5. How do you retrieve the first 10 records from a table named "products"?  
Answer:	 	
SELECT * 
FROM products LIMIT 10;

QUESTION 6. What is the SQL command to update the "price" column of a product with ID 456 to $20.99?  
Answer:	 	
UPDATE products 
SET price = 20.99
WHERE product_id =456;

QUESTION 7. How can you delete all records from a table named "employees" where the "department" is "HR"?  
Answer:	 	
DELETE 
FROM employees 
WHERE department = 'HR';

QUESTION 8. What is the SQL command to retrieve the average salary of all employees in the "salary" column of a table named "employees"?  

Answer:	 	
SELECT AVG(salary) 
FROM employees;

QUESTION 9. How do you retrieve the names of customers whose names start with the letter "A"?  
Answer:	 	
SELECT name
FROM customers 
WHERE name LIKE 'A%';

QUESTION 10. What is the SQL command to join two tables "orders" and "customers" on the "customer_id" column? 

Answer:	 	
SELECT * 
FROM orders INNER JOIN customers
ON orders.customer_id = customers.customer_id;








##E
Employee_num	Employee_name	Department	Salary
1	Amit	CSE	680000
2	Rishi	CSE	550000
3	Prianka	CSE	430000

1.	Write a query to create the table in Structured Query Language.
ANSWER :
CREATE TABLE Employee (
    Employee_num INT PRIMARY KEY,
    Employee_name VARCHAR(255),
    Department VARCHAR(255),
    Salary INT
);
2.	Write a query to insert data into the table.
ANSWER :
INSERT INTO Employee (Employee_num, Employee_name, Department, Salary)
VALUES  (1, 'Amit', 'CSE', 680000),
    (2, 'Rishi', 'CSE', 550000),
    (3, 'Prianka', 'CSE', 430000);
3.	Write a query to view the specific record of the table by using the WHERE       clause?
ANSWER: 
SELECT *
FROM Employee
WHERE Employee_num = 2;

4.	Write a query that access the first the second record from the SQL table?
ANSWER:
SELECT *
FROM Employee
LIMIT 2;

5.	Write a query to find second highest Salary of Employee?
ANSWER :
SELECT MAX(Salary) AS SecondHighestSalary
FROM Employee
WHERE Salary < (SELECT MAX(Salary) FROM Employee);



6.	Write a query how to find monthly salary of Employee if annual salary is given?
ANSWER:
SELECT Employee_num, Employee_name, Salary / 12 AS MonthlySalary
FROM Employee;
ANSWER:

7.	 Write an SQL query to find the maximum, minimum, and average salary of the employees.
ANSWER:
SELECT
    MAX(Salary) AS MaxSalary,
    MIN(Salary) AS MinSalary,
    AVG(Salary) AS AvgSalary
FROM Employee;

8.	SQL query to find the employee id whose salary lies in the range of 600000 and 690000.
ANSWER:
SELECT Employee_num
FROM Employee
WHERE Salary >= 600000 AND Salary <= 690000;

9.	. Write an SQL query to fetch common records between two tables.
ANSWER :
SELECT *
FROM Table1
INNER JOIN Table2
ON Table1.CommonColumn = Table2.CommonColumn;
10.	Write an SQL query to fetch records that are present in one table but not in another table.
   ANSWER :
SELECT Table1.*
FROM Table1
LEFT JOIN Table2
ON Table1.CommonColumn = Table2.CommonColumn
WHERE Table2.CommonColumn IS NULL;

##F
StudentID	FirstName	LastName	Age	GPA	Major
10001	John	Doe	20	3.75	Computer Science
10002	Jane	Smith	21	3.90	Mathematics
10003	Alice	Johnson	22	3.60	Physics
10004	Bob	Wilson	19	3.45	Chemistry
10005	Emily	Brown	20	3.85	Biology
10006	Sarah	Lee	21	3.70	Computer Science
10007	David	Anderson	22	3.55	Mathematics

Question 1. How do you retrieve all records from the 'Student' table?
ANSWER:
 SELECT * 
FROM Student;
Question 2. What SQL statement would you use to filter students who are older than 20?
ANSWER :
SELECT *
FROM Student
WHERE Age > 20;
Question 3. How do you retrieve students whose first name starts with 'A'?
ANSWER :
SELECT *
FROM Student
WHERE FirstName LIKE 'A%';
Question 4. What SQL statement would you use to update the GPA of a student with 'StudentID' 10002?
ANSWER :
UPDATE Student
SET GPA = 4.0
WHERE StudentID = 10002;
Question 5. How do you delete a student with 'StudentID' 10005 from the 'Student' table?

ANSWER :
DELETE 
FROM Student
WHERE StudentID = 10005;

Question 6. What is the purpose of an index, and how can you create an index on the 'Major' column?
ANSWER:
CREATE INDEX idx_Major ON Student (Major);



Question 7. Write an SQL query to find the student id whose age lies in the range of 20 and 21.
ANSWER :
SELECT StudentID
FROM Student
WHERE Age >= 20 AND Age <= 21;
Question 8. Write an SQL query to fetch the last five records from a table
ANSWER:
SELECT *
FROM Student
ORDER BY StudentID DESC
LIMIT 5;

Question 9. Retrieve the student(s) with the highest GPA
ANSWER:
SELECT *
FROM Student
WHERE GPA = (SELECT MAX(GPA) FROM Student);
Question 10. How would you insert a new student record into the 'Student' table?

ANSWER:
INSERT INTO Student (StudentID, FirstName, LastName, Age, GPA, Major)
VALUES (10008, 'Michael', 'Williams', 22, 3.80, 'History');








##G
 
1.Write a query to get the EmpFname from the EmployeeInfo table in the upper case using the alias name as EmpName.
ANSWER :
SELECT UPPER(EmpFname) AS EmpName
FROM EmployeeInfo;

2.Write a query to get the number of employees working in the department ‘HR’.
ANSWER :
SELECT COUNT(*) AS NumberOfEmployeesInHR
FROM EmployeeInfo
WHERE Department = 'HR';

3.What query will you write to fetch the current date?
ANSWER:
SELECT CURRENT_DATE;
4.Write a query to fetch only the place name(string before brackets) from the Address column of the EmployeeInfo table.
ANSWER:
SELECT Address,
 SUBSTRING(Address, 1, CHARINDEX('[', Address) - 1) AS PlaceName
FROM EmployeeInfo;

5.Write a query to create a new table whose data and structure are copied from another table.
ANSWER :
CREATE TABLE DUB AS 
SELECT* FROM employee;

6.Write a query to display the names of employees that begin with ‘S’.
ANSWER:
SELECT EmployeeName
FROM EmployeeInfo
WHERE EmployeeName LIKE 'S%';

7.Create a query to obtain display employees having salaries equal to or greater than 150000.
ANSWER:
SELECT EmployeeName, Salary
FROM EmployeeInfo
WHERE Salary >= 150000;



8.Write a query to fetch the year using a date.
ANSWER:
SELECT YEAR(DateColumn) AS Year
FROM YourTable;

9.Write a query to find duplicate records from a table.
ANSWER:
SELECT first_name,COUNT(*)
FROM employee
GROUP BY first_name
HAVING COUNT(*)>1;

10.Create a query to fetch the list of employees of the same department.
ANSWER:
SELECT*
FROM employee
GROUP BY dept;

##H
Empid	EmpName	Department	ContactNo	EmailId	EmpHeadId
101	Isha	E-101	1234567890	isha@gmail.com	105
102	Priya	E-104	1234567890	priya@yahoo.com	103
103	Neha	E-101	1234567890	neha@gmail.com	101
104	Rahul	E-102	1234567890	rahul@yahoo.com	105
105	Abhishek	E-101	1234567890	abhishek@gmail.com	102


Queries:-
1.	Select the detail of the employee whose name start with P.
ANSWER:
SELECT *
FROM EmployeeInfo
WHERE EmpName LIKE 'P%';

2.	Select the detail of employee whose emailId is in gmail.
ANSWER:
SELECT *
FROM EmployeeInfo
WHERE EmailId LIKE '%@gmail.com';

3.	Select the details of the employee who work either for department E-104 or E-102.
ANSWER:
SELECT *
FROM EmployeeInfo
WHERE Department IN ('E-104', 'E-102');

4.	What is the department name for DeptID E-102?
ANSWER:
SELECT DepartmentName
FROM DepartmentInfo
WHERE DepartmentID = 'E-102';



5.	List name of all employees whose name ends with a.
ANSWER:
SELECT EmpName
FROM EmployeeInfo
WHERE EmpName LIKE '%a';

EmployeeInfo Table:
EmpID	EmpFname	EmpLname	Department	Project	Address	DOB	Gender
1	Sanjay	Mehra	HR	P1	Hyderabad(HYD)	01/12/1976	M
2	Ananya	Mishra	Admin	P2	Delhi(DEL)	02/05/1968	F
3	Rohan	Diwan	Account	P3	Mumbai(BOM)	01/01/1980	M
4	Sonia	Kulkarni	HR	P1	Hyderabad(HYD)	02/05/1992	F
5	Ankit	Kapoor	Admin	P2	Delhi(DEL)	03/07/1994	M
EmployeePosition Table:
EmpID	EmpPosition	DateOfJoining	Salary
1	Manager	01/05/2022	500000
2	Executive	02/05/2022	75000
3	Manager	01/05/2022	90000
2	Lead	02/05/2022	85000
1	Executive	01/05/2022	300000

6. Write a query to find the Nth highest salary from the table without using TOP/limit keyword.


 7.Write a query to retrieve duplicate records from a table.
ANSWER:
SELECT EmployeeName, COUNT(*) AS Count
FROM Employee
GROUP BY EmployeeName
HAVING COUNT(*) > 1;

 8.Write a query to display the first and the last record from    the EmployeeInfo table.
ANSWER:
SELECT *
FROM EmployeeInfo
ORDER BY EmpID
LIMIT 1
UNION ALL
SELECT *
FROM EmployeeInfo
ORDER BY EmpID DESC
LIMIT 1;
 9. Write a query to retrieve two minimum and maximum salaries from the EmployeePosition table.
ANSWER:
SELECT MIN(Salary),MAX(salary)
FROM EmployeePosition;

 10.Write a query to calculate the even and odd records from a table.

##I
CREATE DATABASE student_inquery;
SHOW DATABASES;
USE student_inquery;

CREATE TABLE student (
	Student_id INT(8) NOT NULL PRIMARY KEY,
	First_name CHAR(25),
	Last_name CHAR(25),
	Money INT(15),
    Money_source char(15),
    Monthley_expenses int(8),
	Department CHAR(25)
);

INSERT INTO  student
	(Student_id, First_name, Last_name,Money, Money_source, Monthley_expenses,Department) VALUES
		(2002040, 'Shabuj', 'Mia',8000, 'Tution',7500, 'CSE'),
		(2004067, 'Sorna', 'Boikontho', 5000, 'Home',4500, 'DVM'),
		(2002022, 'Ronok', 'Hasan', 300000, 'Freelancing',11000 ,'CSE'),
		(1902089, 'Amitabh', 'Reza', 500000, 'Freelancing',12350, 'ECE'),
		(1804089, 'Fazle', 'Rabbi', 11500, 'Tution',6700, 'Agri'),
		(1706044, 'Shanti', 'Rehman',70000, 'Home',6000, 'Act'),
		(2107023, 'Rahman', 'Pair', 45000, 'Remote Job',16000, 'Engin.'),
		(2205066, 'Geetika', 'Roy', 4500, 'Tution',4500, 'Math');

 



Q(1): What is SQL Query ? Why it is needed ? write it’s application.
Answer:

SQL (Structured Query Language) is a domain-specific language used for managing and manipulating relational database systems. It is a standard language for interacting with databases and is used to perform a wide range of tasks related to database management and data retrieval. SQL queries are used to communicate with a database to retrieve, insert, update, and delete data.

Q(2): Write a SQL query to print First_name and Last_name from table into a single column Full_name.A space char should separate them.
ANSWER:
SELECT CONCAT(First_name, ' ', Last_name) AS Full_name
FROM student;

Q(3): Write a SQL query to find those student money is greater than 10000 and expenses is greater than 10000.
ANSWER;
SELECT *
FROM student
WHERE Money > 10000 AND Monthley_expenses > 10000;

Q(4): Write a SQL query to find those student expenses is smaller than 70000.
ANSWER:
SELECT *
FROM student
WHERE Monthley_expenses < 70000;

Q(5): Write a SQL query to find unique money source.
ANSWER:
SELECT DISTINCT Money_source
FROM student;

Q(6): Write a SQL query to find highest money in freelancing.
ANSWER:
SELECT MAX(Money) AS HighestFreelancingIncome
FROM student
WHERE Money_source = 'Freelancing';
Q(7): Write a SQL query to find highest money in different job. Like (Home 7000, Freelancing 50000)
ANSWER:
SELECT Money_source, MAX(Money) AS HighestIncome
FROM student
GROUP BY Money_source;

Q(8): Write a SQL query to find details for First_name “Ronok” Last_name “Hasan” from the table.
ANSWER:
SELECT *
FROM student
WHERE First_name = 'Ronok' AND Last_name = 'Hasan';
Q(9): Write a SQL query to find even Student_id.
ANSWER:
SELECT *
FROM student
WHERE Student_id % 2 = 0;
Q(10): write a SQL query to find those student whose First_name start with “A” or “S”.
ANSWER:
SELECT *
FROM student
WHERE First_name LIKE 'A%' OR First_name LIKE 'S%';




##J
WORKER_ID	FIRST_NAME	LAST_NAME	SALARY	JOINING_DATE	DEPARTMENT
001	Monika	Arora	100000	2014-02-20 09:00:00	HR
002	Niharika	Verma	80000	2014-06-11 09:00:00	Admin
003	Vishal	Singhal	300000	2014-02-20 09:00:00	HR
004	Amitabh	Singh	500000	2014-02-20 09:00:00	Admin
005	Vivek	Bhati	500000	2014-06-11 09:00:00	Admin
006	Vipul	Diwan	200000	2014-06-11 09:00:00	Account
007	Satish	Kumar	75000	2014-01-20 09:00:00	Account
008	Geetika	Chauhan	90000	2014-04-11 09:00:00	Admin
Sample Table – Worker
Sample Table – Bonus
WORKER_REF_ID	BONUS_DATE	BONUS_AMOUNT
1	2016-02-20 00:00:00	5000
2	2016-06-11 00:00:00	3000
3	2016-02-20 00:00:00	4000
1	2016-02-20 00:00:00	4500
2	2016-06-11 00:00:00	3500
Sample Table – Title
WORKER_REF_ID	WORKER_TITLE	AFFECTED_FROM
1	Manager	2016-02-20 00:00:00
2	Executive	2016-06-11 00:00:00
8	Executive	2016-06-11 00:00:00
5	Manager	2016-06-11 00:00:00
4	Asst. Manager	2016-06-11 00:00:00
7	Executive	2016-06-11 00:00:00
6	Lead	2016-06-11 00:00:00
3	Lead	2016-06-11 00:00:00
1.Write an SQL query to print all Worker details from the Worker table order by FIRST_NAME Ascending and DEPARTMENT Descending.
ANSWER :
SELECT *
FROM Worker
ORDER BY FIRST_NAME ASC, DEPARTMENT DESC;

 2.Write an SQL query to print details of Workers with DEPARTMENT name as “Admin”.
ANSWER:
SELECT *
FROM Worker
WHERE DEPARTMENT = 'Admin';
3. Write an SQL query to print details of workers excluding first names, “Vipul” and “Satish” from the Worker table.
ANSWER:
SELECT *
FROM Worker
WHERE FIRST_NAME NOT IN ('Vipul', 'Satish');
4.Write an SQL query to print details of the Workers whose SALARY lies between 100000 and 500000.
ANSWER:
SELECT *
FROM Worker
WHERE SALARY BETWEEN 100000 AND 500000;
5.Write an SQL query to fetch the no. of workers for each department in descending order.
ANSWER:
SELECT DEPARTMENT, COUNT(*) AS WorkerCount
FROM Worker
GROUP BY DEPARTMENT
ORDER BY WorkerCount DESC;
6.Write an SQL query to fetch duplicate records having matching data in some fields of a table.
ANSWER:
SELECT field1, field2, COUNT(*)
FROM your_table_name
GROUP BY field1, field2
HAVING COUNT(*) > 1;
7.Write an SQL query to show only even rows from a table.
ANSWER:

8. Write an SQL query to fetch intersecting records of two tables.
ANSWER:
SELECT *
FROM table1
INNER JOIN table2
ON table1.common_column = table2.common_column;
9.Write an SQL query to show records from one table that another table does not have.
ANSWER:
SELECT table1.*
FROM table1
LEFT JOIN table2 ON table1.unique_column = table2.unique_column
WHERE table2.unique_column IS NULL;
10.Write an SQL query to show the top n (say 10) records of a table.
ANSWER:
SELECT *
FROM your_table_name
LIMIT 10;
