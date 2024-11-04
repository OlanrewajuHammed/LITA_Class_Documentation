# LITA_Class_Portfolio

## Project Title: Comprehensive Data Analysis

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Excel](#excel)
- [Foundation of Data](#foundation-of-data)
- [Introduction into Microsoft Excel](#introduction-into-microsoft-excel)
- [Basic Excel Function](#basic-excel-function)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Report and Dashboard](#report-and-dashboard)
- [Summary](#summary)

[SQL](#sql)
- [Introduction to SQL](#introduction-to-sql)
- [Basic SQL Queries](#basic-sql-queries)
- [Exploratory Data Analysis](#exploratory-data-analysis)

[Power BI](#power-bi)
- [Introduction into Power BI](#introduction-into-power-bi)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Report and Dashboard](#report-and-dashboard)
- [Summary](#summary)

[Capstone Project](#capstone-project)

### Project Overview
---
Welcome to my Data Analysis class portfolio, this repository is a collection of my work, demonstrating the growth of my skills from basic data literacy to the creation of data visualizations. Each project includes analyses, visualizations, and documentation of the techniques used. My knowledge span from foundational data literacy, which laid the groundwork for my understanding of data analysis and manipulation and major tools used were **Microsoft-Excel**, **SQL Server** and **Power BI**.
##### Skill demonstrated
  1. Foundational Data Literacy
  2. Data Cleaning and Transformation
  3. Data Visualization and Creating Dashboard
Explore the projects to see how I applied various functions and features to uncover insights and create compelling visual representations of data.

### Data Sources
The data used in these projects were sourced from a variety of locations including:
- Sample datasets provided by course instructors
- Publicly available datasets from online repositories
- Synthetic data generated during tthe classes for learning purposes
- A Capstone dataset for my final project

### Tools used
The tools used include 
1. Microsoft Excel: [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel?ocid=ORSEARCH_Bing&msockid=31ccbb7207cd643010e1ae7e060d65f3)
   - Used for Data cleaning, analysis, and basic visualization.
3. SQL Server: [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads?msockid=31ccbb7207cd643010e1ae7e060d65f3)
   - Used for Database management and querying.
5. Power BI:[Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads)
   - Used for data visualization and dashboard creation.

## Excel
---
Here our facilitator took us through microsoft excel where we navigate the following context
##### Content
- Foundation of Data
- Introduction into Microsoft Excel
- Basic Excel Functions
- Report and Dashboard in Excel

### Foundation of Data
This phase serve as an insight to enhance our excel journey, we were introduced to the following:
 1. Data Literacy: which encompasses
- Data Generation, Data storage, Data Stucture, Statistic, Data Driven Decision Making
2. Data Analysis Life Cycle: which include  
- Ingestion, Transformation, Modeling, Visualization, Analysis, Presentation
  
### Introduction into Microsoft Excel
At this stage we were able to,
1. Navigating Excel interphase
2. Perform data loading and inspection to understand data structure
3. Handling missing variables
4. Perform data cleaning and formatting: which include removing duplicates, data validation, building a drop-down list

![Screenshot (61)](https://github.com/user-attachments/assets/ce26346a-157c-4c39-bd4c-e3da70c4914a)

![Screenshot (65)](https://github.com/user-attachments/assets/58df7fd2-12c0-44d5-9cec-e6a306a26646)

### Basic Excel Function
#### Data Analysis
The aim of this phase was to perform data manipulation tasks in other to answer questions on different aggregate using different code. Functions were used based used at include;
1. overall aggregate;
 - Sum, Average, Max, Min, Count, CountA, Large, Small
```
=SUM(D8:D27)
```
![Screenshot (73)](https://github.com/user-attachments/assets/dfc5faaa-04de-4a15-b62a-83018e5ee73f)

2. conditional funtions; to specify answe if a particular condition is met
   - Sumif(s), Averageif(s), Maxifs, Maxa , Minifs, Countif(s), If(s) 
```
=COUNTIF(C8:C27,C19)
```
![Screenshot (78)](https://github.com/user-attachments/assets/345b2987-005a-4657-b7ad-13e487a51323)

3. Data extraction and joining;
   - Extaction function: Left, Mid, Right,
   - Join function: Concatenate
```
=LEFT(B6,FIND(" ",B6))
```
```
=CONCATENATE(B16&" "&C16)
```

4. Text Cleaning for removing excess spaces and writing in specified cases 
   - Trim
   - Lower,  Upper, Proper
```
=UPPER(B7)
```
![Screenshot (88)](https://github.com/user-attachments/assets/d30ba982-f985-4619-8561-d7e01b3903ea)

4. Data retrieval;
   - Vlookup, Match, Xlookup, Index
```
=VLOOKUP(Database!$E21,'Simple Salary Structure'!$B$8:$I$16,2,FALSE)
```
![Screenshot (108)](https://github.com/user-attachments/assets/9cb80d96-6a5d-4ead-a36b-eb7eb9d8428a)

### Exploratory Data Analysis
When delving into the analysis phase of Exploratory Data Analysis(EDA), we adopt a structured method to comprehend and extract insights from the data to address questions like:
1. Overall sales trend 
2. Top selling product by specific region or market
3. Monthly sales pattern
4. Percentage of revenue generated from specific product by region

### Report and Dashboard
This aspect summarizes our data, enabling us to to communicate the results of data analysis in a structured format using the pivot table, and display key performance indicators and metrics in a dynamic, interactive format using charts, graphs.

![Screenshot (146)](https://github.com/user-attachments/assets/92ab1b63-a998-4cc7-be25-26e4ae432ef9) 
![Screenshot (130)](https://github.com/user-attachments/assets/e1ba4f14-85ef-4172-8e5d-05b1f16cc17a)

### Summary
This repository showcases various aspect completed during my Excel class, highlighting my proficiency in Excel skills and techniques. Learning from foundational data literacy (Foundation of Data), which laid the groundwork for my understanding of data analysis and manipulation. The main source of data used in these projects was provided by the facilitator during the course of learning. This journey culminates in developing advanced dashboards for data visualization.

## SQL
---
Here our facilitator was able to take us through proper basic sql commands and queries by navigating different Rational Database Management system (SQL server and Postgress) to ensure optimum use of oppotunity for diverse students and different organizations preference. Data sources include synthetic data generated during the classes for learning purposes and Sample datasets provided by course instructors
#### Content
1. Introduction to SQL
2. Basic SQL Queries
3. Exploratory Data Analysis

### Introduction to SQL
This section encompass the exposure to the theoretical aspect of sql ranging from:
1. Explanation of SQL and its rules. Some of which are
  - Not being case sensitive, Statement depending on text line
2. What database in sql means and how it store data
3. Importind and exporting of data
3. Basic SQL commands and their types
  - Data definition Language (e.g create), Data Manipulation Language (e.g insert), Data Control Language (e.g grant), Data Transaction Language (e.g commit) and Data Query Language (create)
4. Several basic function which include
  - Craeting database, creating table and different data command
  - SQL Data types - SQL keys - SQL Clause - SQL Operators - SQL Join - SQL Aggregate
5. Craeting SQL Views: a vitual table created based on result of queries. It serves as security to restrict exposure of certain data

![Screenshot (155)](https://github.com/user-attachments/assets/c23373fd-affd-4eaf-8c9f-5d2231e44e40)

### Basic SQL Queries
This phase include utilizing several commands to bring insightful conclusions from data and also taing *primary key* into consideration. Some of the process include:
1. Create database: This serve as the house where tables are stored 
```
Create database LITA_DB
```

2. CREATE TABLE: Similar to excel table where data are store and ensuring appropriate data type
```
CREATE TABLE Employee (
staffid varchar (10) not null, FirstName varchar (255) NOT NULL, SecondName varchar (255), Gender varchar (10), Date_of_Birth date, HireDate datetime,
primary key (staffid)
)
```

|Heading 1|Heading 2|Heading 3|Heading 4|Heading 5|Heading 6|
|---------|---------|---------|---------|---------|---------|
|staffid|firstname|secondname|gender|Date_of_Birth|hiredate|

3. Inserting values into table created and importing data from different sources (following column arragement)

|staffid|firstname|secondname|gender|Date_of_Birth|hiredate|
|---------|---------|---------|---------|---------|---------|
|AB401|ayan|olakun|female|1992-08-22|2018-02-09|
```
insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09')
```
![Screenshot (156)](https://github.com/user-attachments/assets/4d97134e-898f-4acc-b226-97c2eefed38c)

4. Creating auto-numbering command
```
CREATE TABLE Salary (
salary_id int identity (1,1)not null,
)
```

![Screenshot (160)](https://github.com/user-attachments/assets/59e796e5-9c7f-48a5-9163-fb806a9a3848)

5. Creating queries for agreegate using functions like
   - sum, min,max, average count
```
SELECT SUM(Salary) AS TOTALSALARY FROM Salary
```

![Screenshot (161)](https://github.com/user-attachments/assets/f5606cf4-6dce-4b52-9e54-4b1f480f7c5c)

6. Get specific results based on conditions
```
UPDATE SALARY
SET department = 'Information Tech.'
where Staffid = 'AB234'
```
```
select count(staffid) as StaffPerSate, state_of_origin 
from Employee
GROUP BY State_of_Origin
HAVING COUNT(staffid) >=3
```

![Screenshot (164)](https://github.com/user-attachments/assets/3d5b2af2-b63d-4299-aff5-91a4c0e4a3e4)

7. Joining  different tables
```
select employee.staffid, employee.firstname, employee.gender,
			 Salary.salary
from employee
join Salary
on salary.Staffid = employee.staffid
```

![Screenshot (166)](https://github.com/user-attachments/assets/bc228d39-c3f8-4c42-aaba-45040fb517e2)

8. Combining results from different tables using
  - UNION to remove duplicate  result
  - UNION ALL to return all results
```
select * from LITA_Store_Lekki
	union all
	select * from LITA_Store_Marina
```

![Screenshot (168)](https://github.com/user-attachments/assets/b1f565e7-b431-475c-856f-71536bdaed91)

9. Altering of table which enable modifying existing atttribues or creatin a new one based on specified conditiond
```
ADD AGE AS DATEDIFF(YEAR, Date_of_Birth, Hiredate) -
   CASE
       WHEN MONTH(Hiredate) < month(Date_of_birth)
	   OR (MONTH(Hiredate) = month(Date_of_birth)
	   AND DAY(Hiredate) < DAY(Date_of_birth))
	THEN 1
	ELSE 0
END
```

![Screenshot (169)](https://github.com/user-attachments/assets/9e86e9a0-69e0-403b-a921-b95cf6f46238)

### Exploratory Data Analysis
In the Exploratory Data Analysis(EDA), extract insights from the data to address questions like:
1. Overall sales trend 
2. Top selling product in assending of descending order
3. Join 2 or more tables together based on desire results and positions
4. Combine the result of two or more select queries

### Summary
The basics of SQL include creating and managing tables, inserting data, and querying data using SELECT statements. Learning how to filter data and perform basic aggregations helps in retrieving and summarizing information from databases. Data sources include synthetic data generated during the classes for learning purposes and Sample datasets provided by course instructors

### Power BI
---
A data visualization and business intelligence tool. Here our facilitator introduced us to the Power BI tool including proper navigation. Data sources used are synthetic data generated during the classes for learning purposes, Sample datasets provided by course instructors which include  (HR data, Columnar data, International Breweries dataset, Loan data) and data imported from Power BI supported data sources

### Introduction into Power BI
This phase expantiate the what the tool entails and its working system which include 
1. Explanation of the tool as a multiple software connectors with the ability to connect to several supported data sources at a time . Data sources include
   - Excel, SQL server, Online services etc.
2. introduction to the its different component which includes
   - Power BI Desktop where all visualization ate done
   - Power BI Mobile Application
   - Power BI Gateway
   - Power BI service used to publish report
3. Elaboration on the  interface including
   - The repot view, data view, model view and DAX query view 
   - VIsualualization pan: component are
     - bar chat, histogram, map, table etc.
4. Principles of data visualization: enumerating steps to proper decision making

### Visialization and creating Dashboard 
Actions perform in this phase include importing of data from different sources and building visualization to show compelling result
1. Importing and transformation of data:


- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Report and Dashboard](#report-and-dashboard)
- [Summary](#summary)


## [Capstone Project]
---

- [Excel](#excel)
- [SQL](#sql)
- [Power BI](#power-bi)
