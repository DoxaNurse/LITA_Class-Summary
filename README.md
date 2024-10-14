# LITA_Projects
My data Analysis journey with Ladies in Tech Africa(The Incubator Hub), on a journey to career Transitioning. I am cureently learning and working on various projects to biuld my expertise. Below you will find a selection go my projects that showcase my learning journey and growing proficiency in data analysis. 

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


## Data Cleaning and Preparation
In the intial phase, we carried out:
1. Data Loading and Inspection
2. Handling missing variables
3. Data formatting and cleaning

## Exploratory Data Analysis
Exploratory Data Analysis involved answering questions about the data such as: 
- what is the overall sales trend?
- what product are top sellers?
- what are the products on peak sales?

## Data Analysis
this is where we include some basic lines of code or queries or even DAX expressions used in the analysis:

```SQL
SELECT * FROM TABLE !
WHERE CONDTION= TRUE

CREATE DATABASE LITA

UPDATE Salary
SET FIRSTNAME = 'Emeka'
where Staffid = 'AB212'

select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
join Salary
on salary.Staffid = employee.staffid

select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
right join Salary
on salary.Staffid = employee.staffid

create view vw_Employee_tbl
as
SELECT STAFFID, firstname, gender, hiredate from employee

ALTER TABLE EMPLOYEE
ADD AGE AS DATEDIFF(YEAR, Date_of_Birth, Hiredate) -
   CASE
       WHEN MONTH(Hiredate) < month(Date_of_birth)
	   OR (MONTH(Hiredate) = month(Date_of_birth)
	   AND DAY(Hiredate) < DAY(Date_of_birth))
	THEN 1
	ELSE 0
END

```
## Data Visualization


ALTER TABLE EMPLOYEE
ADD AGE AS datediff( year, Date_of_Birth, Hiredate)



