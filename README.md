# LITA_Class Documentation
My data Analysis journey with Ladies in Tech Africa(The Incubator Hub), on a journey to career Transitioning. I am cureently learning and working on various projects to biuld my expertise. Below you will find a selection go my projects that showcase my learning journey and growing proficiency in data analysis. 

[Skills](#skills)

[Tools used](#tools-used)

[Data Aggregation with Microsoft Excel](#data-aggregation-with-microsoft-excel)

[Data Summarization with Pivot Tables](#data-summarization-with-pivot-tables)

[SQL For data Summarization and Aggregation](#sql-for-data-summarization-and-aggregation)

## Skills
- SQL: Proficient in writing complex queries, data manipulation, and database management.
- Microsoft Excel: Advanced skills in data analysis, pivot tables, VLOOKUP, and data visualization.
- Power BI: Experienced in creating interactive dashboards and reports to visualize data insights.
- Data Visualization: Creating insightful charts and dashboards to communicate findings effectively.
- Data Cleaning: Expertise in cleaning and preparing data for analysis.
- Statistical Analysis: Applying statistical methods to analyze data and draw meaningful conclusions.

## Tools used
- Microsoft Excel for data for data analysis, cleaning and visu-alization[Download Here](https://microsoft.com)
- SQL- Structured query language for Querying of Data[Download Here](https://www.mysql.com)
- Github for Portfolio building [Download Here](https://github.com)
- Power Bi for Data Cleaning and visualization. [Download Here](https://powerbi.microsoft.com/en-us/downloads/)


## Data Aggregation with Microsoft Excel
In the intial phase on Microsoft Excel, we carried out:
1. Data Loading and Inspection
2. Handling missing variables
3. Data formatting and cleaning

- Using basic excel functions, we carried out aggregration with condition. The following functions were used to carry out the Aggregration of Numbers in the tables below: 
SUM, AVERAGE, MAX, MIN, COUNT, LARGE, SMALL, SUMIF, AVERAGEIF, MAXIFS,MINIFS, COUNTIF. These functions were used to extract the values specified in the following tables. 
![Screenshot (120)](https://github.com/user-attachments/assets/bc3b5406-3513-41fa-bf0d-9452dec9e41d)

![Screenshot (119)](https://github.com/user-attachments/assets/cf229853-b44f-44a1-9de5-ef72e2183c8c)

- Using basic excel functions, we carried out data aggregration. The following functions were used to carry out the Extraction of texts anf compostion in the tables below: 
LEFT, RIGHT, MID, SEARCH, FIND, LOWER, UPPER, PROPER, RANDBETWEEN, TRIM, CONCAT, CONCATENATE, TEXT JOIN. These functions were used to extract the values specified in the following tables. 

![Screenshot (124)](https://github.com/user-attachments/assets/1a0788b3-0606-42d6-b3f8-4c6b07a26cd7)

![Screenshot (123)](https://github.com/user-attachments/assets/3d0bb69f-40fb-49dc-bf2d-156b0834b2b2)

![Screenshot (125)](https://github.com/user-attachments/assets/7595e135-38a7-47ca-bb14-e2d9a631d783)

![Screenshot (126)](https://github.com/user-attachments/assets/ff7cf3c3-f5f7-4a00-8e98-1b7988b01b48)

![Screenshot (128)](https://github.com/user-attachments/assets/dfdf3b49-133f-4091-ab24-4e98139449e7)

- Using Excel functions LookUp, we carried out aggregration. The Lookup function is to locate values in the simple salary structure table for for aggregation. The basic LOOKUP functions used to carry out the Extraction and composition of values in the table below include: VLOOKUP, HLOOKUP, INDEX, MATCH, CHOOSE, XLOOKUP, INDEX&MATCH, INDIRECT. These functions were used to extract the values specified in the table. 

![Screenshot (131)](https://github.com/user-attachments/assets/be97c55c-290b-4b44-9f4c-8e6fa5b1c8f6)

- Using excel functions-Condtionals, we filled in missing variables. . The following condtional functions were used to fill in the blank column on the transaction category in the table below: IF, SWITCH, IFS, AND, OR, XOR. This functions were used to extract the values specified in the TABLE

![Screenshot (134)](https://github.com/user-attachments/assets/cf7c1207-ec1b-4037-92f0-28bcb18c5fec)


## Data Summarization with Pivot Tables
- **Revenue by Region**:These columnal chart and Pivot table analyses the contribution of each region to the revenue with North east recording the highest at about 18 billion.

![Screenshot (135)](https://github.com/user-attachments/assets/969b2e64-9760-4ed1-ba7b-808722eaf253)

![Screenshot (145)](https://github.com/user-attachments/assets/28478ac3-b975-4bdd-9e26-84aca47dd046)

- **Region by Unit Sold**: These bar chart and pivot table illustrates the unit sold with the North East amassing the highhest at 208,983.

![Screenshot (136)](https://github.com/user-attachments/assets/010ade6f-9f21-4b0b-bed5-46fdd366cc8a)

![Screenshot (146)](https://github.com/user-attachments/assets/2cf0d379-398e-41ca-8792-1067eaa93871)

- **Top 5 market by Revenue**: this table analyses the top 5 market with Ekiti generating the highest at about 5.6million revenue. 

![Screenshot (138)](https://github.com/user-attachments/assets/bfdcd077-0c35-4895-b72c-d7a5485fc0dc)

- **Bottom 5 market by Unit Sold**: this table shows the bottom 5 market performing less compared to others in terms of unit sold and we can the least is Boki amassing just 2 units.

![Screenshot (139)](https://github.com/user-attachments/assets/8a35f25e-d6ba-4975-ada7-6fb023de7c4a)

- **Revenue By Month**: Thus table shows the monthly sales trend in relation to revenue across the two years with May 2014 and March 2015 having the highhest revenue.

![Screenshot (143)](https://github.com/user-attachments/assets/31f38440-84bd-43de-a3d0-9e294bef3313)

- **Line of Business by Revenue percentage**: This table shows the line of business with the highest performance and we have Service Plan generating 52 billion which is equivalent to 71% of the total revenue generated.

![Screenshot (142)](https://github.com/user-attachments/assets/f33942be-1a06-4dad-9f0d-2765bb68f11d)

## SQL For data Summarization and Aggregation
this is where we include some basic lines of code or queries or even DAX expressions used in the analysis:

```SQL
create database LITA_DB

CREATE TABLE Employee (
staffid varchar (10) not null,
FirstName varchar (255) NOT NULL,
SecondName varchar (255),
Gender varchar (10),
Date_of_Birth date,
HireDate datetime,
primary key (staffid)
)
select * from Employee

insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')

-------to drop table --------

drop table employee

----delete sql command--

delete from employee
where staffid  = 'ab281'

-----truncate sql command-------

truncate table employee


------identity in SQL -----

CREATE TABLE PERSON (
personid int identity (1,1) primary key not null,
personname varchar (255) not null,
age int
)
insert into PERSON (personname, age)
values ('saidu', 45),
('adebanjo', 49),
('olorunda', 33),
('martha', 88),
('sandi', 100),
('jackson', 22),
('okunola', 19),
('esther', 45)

select * from PERSON

------Insert more records into Employee table-------

insert into [dbo].[Employee]
values ( 'AB200', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB405', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB282', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB278', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09'),
( 'AB240', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB299', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB268', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB286', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB270', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09')

select * from [dbo].[Employee]

---- to create second table call SALARY TABLE-------
CREATE TABLE Salary (
salary_id int identity (1,1)not null,
Staffid varchar (255),
firstname varchar (255),
lastname varchar (255),
department nvarchar(max),
salary decimal (10, 3) ---(10: precision, 3:scale)
)

select * from [dbo].[Salary]

-----insert records into Salary table-------------

insert into salary (staffid, FirstName, lastname, Department, Salary)


values ( 'AB401', 'ayan', 'olakun', 'Information Tech.', 45000.45),
( 'AB212', 'okorie', 'mercy','Account',500000.99999),
( 'AB223', 'joshua', 'chukwuemeka', 'Human Resources',100560.9339999),
( 'AB234', 'sanni', 'ibrahim', 'Sales and Marketing',845688.99),
( 'AB254', 'mercy', 'olanipekun', 'Account',8889.999999),
( 'AB249', 'johnson', 'mercy', 'Information Tech.',234000.90909090),
( 'AB298', 'ayomide', 'halleluyah', 'Logistics', 678000.991999),
( 'AB260', 'deborah', 'justin', 'Logistics',900099.00697969),
( 'AB281', 'wale', 'olanipekun', 'Information Tech',873093.2344)

insert into [dbo].[Salary]
values ( 'AB200', 'ayomide', 'halleluyah', 'Human Resources',45699.8585),
( 'AB405', 'deborah', 'justin', 'Account',898349.900222),
( 'AB282', 'wale', 'olanipekun', 'Sales and Marketing',362636.564848),
( 'AB278', 'shukurat', 'lasisi', 'Logistics',100000.464647),
( 'AB240', 'johnson', 'mercy', 'Information Tech',3855590.9890093),
( 'AB299', 'ayomide', 'halleluyah', 'Account', 8585858.9292),
( 'AB268', 'deborah', 'justin', 'Human Resources',76767.93939)

----SUM, COUNT, MAX, MIN, AVERAGE---------------------------------

SELECT SUM(Salary) AS TOTALSALARY FROM Salary

SELECT AVG(Salary) AS AVERAGESALARY FROM Salary

SELECT COUNT(Staffid) AS EmployeeCount FROM EMPLOYEE

SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary

-----update--------

update Salary
set salary = 7056999.9994
where Staffid = 'AB401'


---List operator------------------
--IN
--NOT IN

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME IN ('SANNI', 'DEBORAH', 'MERCY')

SELECT * FROM Salary
WHERE department IN ('ACCOUNT', 'LOGISTICS','HUMAN RESOURCES')

SELECT * FROM Salary
WHERE department NOT IN 
('ACCOUNT', 'LOGISTICS','HUMAN RESOURCES')

----------LOGICAL OPERATORS----------------------
----AND
---OR

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JUSTIN'

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JUSTIN' AND GENDER = 'FEMALE'

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JOHNSON' AND GENDER = 'FEMALE'

----OR

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JUSTIN' OR GENDER = 'FEMALE'

SELECT * FROM  EMPLOYEE
WHERE GENDER = 'MALE' AND DATE_OF_BIRTH <= '1990-01-01'
AND STATE_OF_ORIGIN = 'LAGOS'

SELECT * FROM  EMPLOYEE
WHERE GENDER = 'MALE' AND DATE_OF_BIRTH >= '1990-01-01'
AND STATE_OF_ORIGIN = 'LAGOS'



SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JOHNSON' OR GENDER = 'GIRL,'

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'FEMI' OR GENDER = 'GIRL,'

-------UPDATE--------

SELECT * FROM Salary

UPDATE Salary
SET FIRSTNAME = 'Emeka'
where Staffid = 'AB212'

UPDATE SALARY SET STAFFID = 'AB550' WHERE STAFFID = 'AB254'

---SALARY = 5% (0.05)

UPDATE SALARY
SET SALARY = SALARY +(SALARY * 0.05)
WHERE STAFFID IN ('AB200', 'AB268','AB278')

UPDATE SALARY
SET SALARY = SALARY * 1.05
WHERE STAFFID IN ('AB200', 'AB268','AB278')

UPDATE SALARY
SET SALARY = SALARY * (1 + 0.05)
WHERE STAFFID IN ('AB200', 'AB268','AB278')

SELECT * FROM Salary

--------------JOIN-----------------------

INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL JOIN

SELECT * FROM EMPLOYEE
SELECT * FROM SALARY
SELECT * FROM PAYMENT 

-----JOIN 2 TABLES----------------
 --EMPLOYEE  =  7 COLUMNS ( STAFFID, FIRSTNAME, GENDER, HIREDATE, STATE)
 --SALARY  = 6 COLUMNS (DEPARTMENT, SALARY)

 select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
join Salary
on salary.Staffid = employee.staffid


-------inner join----------------
 select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
join Salary
on salary.Staffid = employee.staffid



-------left join---------------------

 select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
left join Salary
on salary.Staffid = employee.staffid

-------right join---------------
 select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
right join Salary
on salary.Staffid = employee.staffid

-----full join---------------------

 select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
full join Salary
on salary.Staffid = employee.staffid

------join 3 tables-------------------

select employee.staffid,
           employee.firstname, 
		   employee.gender,
		   employee.hiredate,
			employee.state_of_origin,
			Salary.department,
			 Salary.salary,
			 Payment.Account_No,
			 Payment.Bank,
			 Payment.Payment_Method
from employee
inner join Salary
on salary.Staffid = employee.staffid
inner join Payment
on Payment.staffid = salary.Staffid


-------------------
select p.staffid, 
           p.firstname, 
		   p.gender,
			 p.hiredate,
			 p.state_of_origin, 
			 a.department,
			 a.salary
from employee p
join Salary a
on a.Staffid = p.staffid

------union vs union all
create table  LITA_Store_Lekki (
customerID INT not null,
firstname varchar (max),
lastname  varchar (max),
Customer_gender nvarchar(max),
age int,
address varchar (max),
transaction_amount decimal (18, 4)
)

insert into LITA_Store_Lekki(customerID,firstname, lastname, Customer_gender, age, address, transaction_amount)
values ( 100, 'ramesh', 'abdukl', 'male', 24, '8 ahmed road', 2000.00),
   (121,'khilan', 'delhi', 'female',33, '9 delhi stree, okun', 1500.33),
    (111,'malik', 'delhi', 'female',39, '2 agriiv stree, makunn', 1999.33),
	 (110, 'kara', 'ogun', 'male',40, '10 hahroh road, ottawa', 3400.33),
	  (109,'sunkanmi','alade','male', 44, '9 orebiyi street, okun', 37575.00),
	   (108,'orobiyi', 'kekerekun', 'male',24, '88 malele road, ijebu', 6500.33),
	    (115,'igbati', 'bunmi', 'male',29, '90 delhi street, abeokunta', 1000.69),
		 (120,'mummry', 'akinbho','female', 25, '9 babaoluwa quarter, ipaha', 9000.50),
		  (119,'latana', 'jerremy', 'male',33, '9 ifelofudn quarter, ado', 15090.35),
		    (108,'orobiyi', 'kekerekun', 'male',24, '88 malele road, ijebu', 6500.33),
			 (111,'malik', 'delhi', 'female',39, '2 agriiv stree, makunn', 1999.33)
 
select * from LITA_Store_Lekki

create table  LITA_Store_Marina (
customerID INT not null,
firstname varchar (max),
lastname  varchar (max),
Customer_gender nvarchar(max),
age int,
address varchar (max),
transaction_amount decimal (18, 4)
)

insert into LITA_Store_Marina( customerID,firstname, lastname, Customer_gender, age,address, transaction_amount)
values ( 200,'Femk', 'abdukl',  'male',24, '9 old road', 88000.00),
   (201, 'isaiah', 'john','male', 55, '22 alaly stree, okun', 1590.33),
    ( 206,'emma', 'abu','male', 39, '7 ababa street, makunn', 6788.33),
	 (210, 'kara', 'ogun','female' ,40, '10 hahroh road, ottawa', 3400.33),
	  ( 211,'sunkanmi', 'osagie', 'female' ,49, '9 agric butstop street, okun', 89875.00),
	   (209,'oge', 'kunle', 'male',88, '10 iwo street, liverpool', 7860.33),
	    (204, 'igbayin', 'elizabeth', 'female',78, '100 kukuma street, epe', 89100.69),
		 (219,'mummry', 'akinbho','female', 25, '9 babaoluwa quarter, ipaha', 9000.50),
		  (220,'latana', 'jerremy','male', 33, '9 ifelofudn quarter, ado', 15090.35),
		  (216, 'marvelous', 'jerremy', 'female',96, '9 jo grey quarter, igbo', 53590.35),
		   (210, 'kara', 'ogun','female' ,40, '10 hahroh road, ottawa', 3400.33),
	  ( 211,'sunkanmi', 'osagie', 'female' ,49, '9 agric butstop street, okun', 89875.00),
	   ( 206,'emma', 'abu','male', 39, '7 ababa street, makunn', 6788.33)

-------union all------
	select * from LITA_Store_Lekki
	union all
	select * from LITA_Store_Marina

	------union-----------
select  customerID, Customer_gender, transaction_amount
from LITA_Store_Lekki
union 
select customerID, Customer_gender, transaction_amount
from LITA_Store_Marina


select * from LITA_Store_Lekki
union all
select * from LITA_Store_Marina

select 'Lekki Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		   customer_gender as [GENDER],age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
FROM LITA_Store_Lekki
UNION ALL
select 'Marina Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		    customer_gender as [GENDER], age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
from LITA_Store_Marina

-------------------SQL VIEWS--------------------------------
select * from employee

create view vw_Employee_tbl
as
SELECT STAFFID, firstname, gender, hiredate from employee

select * from vw_Employee_tbl

select * from [dbo].[vw_LITA_Store_Transaction_tbl]

select * from [dbo].[vw_LITA_Store_Transaction_tbl2]

create view vw_LITA_Employee_Info 
as
select employee.staffid,
        employee.firstname, 
	employee.secondname,
        employee.gender,
	employee.hiredate,
	employee.state_of_origin,
	Salary.department,
	Salary.salary,
	Payment.Account_No,
	Payment.Bank,
	Payment.Payment_Method
from employee
inner join Salary
on salary.Staffid = employee.staffid
inner join Payment
on Payment.staffid = salary.Staffid

select * from [dbo].[vw_LITA_Employee_Info]

-------SQL CASE WHEN-------------------------
SELECT * FROM EMPLOYEE

ALTER TABLE EMPLOYEE
ADD AGE AS DATEDIFF(YEAR, Date_of_Birth, Hiredate) -
   CASE
       WHEN MONTH(Hiredate) < month(Date_of_birth)
	   OR (MONTH(Hiredate) = month(Date_of_birth)
	   AND DAY(Hiredate) < DAY(Date_of_birth))
	THEN 1
	ELSE 0
END

-------------
ALTER TABLE EMPLOYEE
ADD AGE AS datediff( year, Date_of_Birth, Hiredate)

select * from employee

--60 and above = SeniorExecutive
---40 -59 = Senior Manager
--30 and 39 = Manager
--less than 30 =  Assistant Manager

--------Case When--------
select Staffid, firstname, Gender, state_of_origin, Age,
  CASE
       when Age  >= 60 then 'Senior Executive'
	   when Age between 40 and 59 then 'Senior Manager'
	   when Age between 30 and 39 then 'Manager'
	   when Age <= 29 then 'Assistant Manager'
	 Else 'Unknown'
End as AgeGroup
from [dbo].[Employee]

-----Drop state_of_origin column-------------
ALTER TABLE EMPLOYEE
DROP COLUMN STATE_OF_ORIGIN 

SELECT * FROM EMPLOYEE

---create column stateoforigin----------

ALTER TABLE EMPLOYEE
ADD  StateOfOrigin varchar (255)

select * from employee

update Employee
set StateOfOrigin =
  case 
   when Staffid = 'AB200' THEN 'Delta'
   when Staffid = 'AB212' THEN 'Lagos'
   when Staffid = 'AB223' THEN 'Oyo'
   when Staffid = 'AB234' THEN 'Bauchi'
   when Staffid = 'AB240' THEN 'Port Harcourt'
   when Staffid = 'AB249' THEN 'Lagos'
   when Staffid = 'AB254' THEN 'Edo'
   when Staffid = 'AB260' THEN 'Ekiti'
   when Staffid = 'AB268' THEN 'Delta'
   when Staffid = 'AB270' THEN 'Lagos'
   when Staffid = 'AB278' THEN 'Kano'
   when Staffid = 'AB281' THEN 'kano'
   when Staffid = 'AB282' THEN 'Ekiti'
   when Staffid = 'AB286' THEN 'Lagos'
   when Staffid = 'AB298' THEN 'Delta'
   when Staffid = 'AB299' THEN 'Edo'
   when Staffid = 'AB401' THEN 'Oyo'
   when Staffid = 'AB405' THEN 'Delta'
ELSE 'Unknown'
End
-----------------International Breweries------------------------
SELECT * FROM [dbo].[InternationalBreweries]

---to get total profit----
select sum(profit) as TotalProfit from InternationalBreweries
---to get totalprofit for senegal------
select sum(profit) as TotalProfit from InternationalBreweries
where countries = 'Senegal'
--to get total for Nigeria in 2019---
select sum(profit) as TotalProfit from InternationalBreweries
where countries = 'Nigeria' and YEARs = '2019'
----
select Brands, sum(profit) as TotalProfit 
from InternationalBreweries
where countries = 'Nigeria' and years = '2017'
Group by Brands
order by 2 desc

select Brands, sum(profit) as TotalProfit 
from InternationalBreweries
where countries = 'Nigeria' 
Group by Brands
order by 2 desc


----to get totalprofit for Hero brands-----
select  sum(profit) as TotalProfitHero from InternationalBreweries
where countries = 'Nigeria' and years = '2017' and brands ='Hero'
--Group by Brands
--order by 2 desc

SELECT countries,
      CASE
	     WHEN COUNTRIES IN ('Nigeria', 'Ghana') then 'Anglophone'
		 Else 'Francophone'
End as CountriesGroup,
sum(Profit) as TotalProfit from internationalbreweries
where years in ('2017', '2018', '2019')
Group by Countries
order by 3 desc
```
## Data Visualization with Power bi




