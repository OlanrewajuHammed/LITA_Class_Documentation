![Screenshot (170)](https://github.com/user-attachments/assets/2eb6ce8e-4677-4685-85c5-79adf4e134a8)![Screenshot (137)](https://github.com/user-attachments/assets/a5133edf-4bbb-4d5f-af3c-1f3ebe1cd1c5)# LITA_Class_Portfolio

## Project Title: Comprehensive Data Analysis Journey 

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
- [Summary](#summary)


[Power BI](#power-bi)
- [Introduction into Power BI](#introduction-into-power-bi)
- [Data Transformation](#data-transformation)
- [Report and Dashboard](#report-and-dashboard) 
- [Exploratory Data Analysis](#exploratory-data-analysis)
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
1. **Microsoft Excel**: [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel?ocid=ORSEARCH_Bing&msockid=31ccbb7207cd643010e1ae7e060d65f3)
   - Used for Data cleaning, analysis, and basic visualization.
3. **SQL Server**: [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads?msockid=31ccbb7207cd643010e1ae7e060d65f3)
   - Used for Database management and querying.
5. **Power BI**:[Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads)
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
 1. **Data Literacy**: which encompasses
- Data Generation, Data storage, Data Stucture, Statistic, Data Driven Decision Making
2. **Data Analysis Life Cycle**: which include  
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

2. conditional funtions; to specify answer if a particular condition is met
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


## Power BI
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
   - VIsualualization pane: component are
     - bar chat, histogram, map, table etc.
4. Principles of data visualization: enumerating steps to proper decision making

### Data Transformation 
Actions perform in this phase include importing of data from different sources and building visualization to show compelling result
1. Generating real life dataset from class and importing data from different sources

|Heading 1|Heading 2|Heading 3|Heading 4|Heading 5|Heading 6|
|---------|---------|---------|---------|---------|---------|
|Name|Gender|marital status|level of education|Email address|hiredate|

![Screenshot (5)](https://github.com/user-attachments/assets/afa9c0eb-5fa4-4c8e-9d70-33c68f9bec9f)


3. Data transformation: where data cleaning is carried out. Actions include
   - Transposing data, removing specific column and rows, promoting header, correcting datatype etc..

![Screenshot (17)](https://github.com/user-attachments/assets/a0cf3035-3aa4-4014-8633-86cf8f0014c0)

4. Sorting data by delimeter: used for
   - splitting a column into columns
   - sorting data in ascending or descending order

![Screenshot (22)](https://github.com/user-attachments/assets/f45fec47-09f2-4362-b851-27d55f9985d2)

5. Checking for Data consistency previewing 
   - column quality, column distribution, column profile

![Screenshot (27)](https://github.com/user-attachments/assets/4e685d2e-152e-44e0-839f-4eb50aaeb37a)

6. Appending and merging colunm of similar dataset
   - Append add data to row
   - merging add to column

![Screenshot (40)](https://github.com/user-attachments/assets/0afa010d-03d2-49b3-a19f-1fb8041bc9b4)

7. Chaging text case and merging columns using
   - Upper,proper and lower function
   - concatenate to merge 

![Screenshot (123)](https://github.com/user-attachments/assets/ac105ebb-8970-4697-9e51-7f30af13f854)

### Report and Dashboard 
This phase require creating some calculated and conditional column to enable proper visualization 
1. **Creating *measure* (Analytic Expression)**: to create a single desired value from entire table.
![Screenshot (170)](https://github.com/user-attachments/assets/45f0c56f-c64e-4f05-a2a5-94b6d36ac1fb)

2. **Creating conditional column**: representing unique row name by number, numbers by text
```
If Region = South West --> 1
Else if Region = South East --> 2
Else if Region = South South --> 3
Else if Region = North Central --> 4
Else if Region = North East --> 5
Else
6
```

![Screenshot (133)](https://github.com/user-attachments/assets/a1a145c7-a7dc-443a-9058-f672fbe35d39)

3.  **Visualization**: This part consist of building visuals and formating (beautifying and modifying) visuals view for efficient presentation of findings. Visuals are presented on
- card: use to display aggregate from created measure
![Screenshot (135)](https://github.com/user-attachments/assets/c9368a59-d12b-492d-9e07-d1ced15160b5)
![Screenshot (140)](https://github.com/user-attachments/assets/059dd112-c2de-4136-ad2b-1b2ffbb5e11f)

- bar chart: to check particular dimension against period or value
- doughnut: check ratio of entity by other entity (Legend)
- map: to visualize real life location of desired entity
![Screenshot (145)](https://github.com/user-attachments/assets/f508a8e7-e640-4432-9151-c8454696decd)

- Q & A: To know count by yes or no true or false
![Screenshot (153)](https://github.com/user-attachments/assets/6bcb0e21-6984-4e7b-b4b2-9b22b226617c)

- slicer: using particular entity to look around data
![Screenshot (175)](https://github.com/user-attachments/assets/4812fef8-81f1-4a42-adfd-7e538cc71b95)

- matrix: showing entities of calculated column and other desired columns
![Screenshot (183)](https://github.com/user-attachments/assets/4ddf7548-4da1-43e8-838f-1e8261c24bfb)

### Exploratory Data Analysis
In this EDA we were able to visualiza proper adequate finding to answer questions and show trends 
1. Attrition count by Department
2. Product distribution by region using the map
3. Njmber of current employees by gender
4. Job role by job satisfactory level

![Screenshot (182)](https://github.com/user-attachments/assets/c68c7f22-f21f-45c0-aa81-642688e40525)

### Summary
In this repository, I document my journey of mastering Power BI, a powerful tool for data visualization and business analytics. Throughout this course, I have learned to navigate the Power BI interface, transform and clean data using the Power Query Editor, and create a variety of visualizations. I have also developed skills in building interactive dashboards that consolidate data insights and facilitate informed decision-making. This repository serves as a comprehensive guide, showcasing my progress and the practical applications of Power BI in data analysis.


## [Capstone Project]
---
### Introduction
This repository documents my work on a capstone project designed to assess my skills in data analysis using Excel, SQL, and Power BI. The project involved working with two datasets: sales data and customer data. The objective was to demonstrate my knowledge and skills acquired during classes, as well as to showcase my ability to apply these skills to real-world data. Additionally, this project allowed me to document my learning journey beyond the classroom, highlighting my ability to clean, analyze, and visualize data effectively.

### Excel
#### Data Cleaning
1. **Remove Duplicates**: The first step was to remove duplicates from both datasets to ensure data integrity. This was done using the "Remove Duplicates" feature in Excel.

![Screenshot (229)](https://github.com/user-attachments/assets/3c8f322b-128b-4fcf-87bc-aeff412bd5aa)
![Screenshot (237)](https://github.com/user-attachments/assets/3d5e162e-f561-43e6-9a77-7655080ab2b4)


2. **Generate Revenue Column**: For the sales data, I generated a revenue column by multiplying the Quantity column by the Unit Sold column.
```
=F28*G2
```
![Screenshot (231)](https://github.com/user-attachments/assets/fba6696f-7d9a-4d67-90e0-4b17838438fc)

3. **Validate Columns**: I validated the columns to ensure data consistency and accuracy. This involved checking for any inconsistencies or errors in the data.

![Screenshot (232)](https://github.com/user-attachments/assets/8f1c6346-9150-4aaa-9de8-078ad37d0d69)

4. **Create Drop-Down Lists**: To standardize data entries, I created drop-down lists for certain columns, such as Product and Region.

![Screenshot (236)](https://github.com/user-attachments/assets/6467bf44-df60-48f2-9bb8-03a13c9a7335)

#### Aggregations
1. **Aggregate Functions**: I performed various aggregations for both data using functions like
 - `SUM` to calculate overall revenue
 - `AVERAGE` to calculate average revenue
 - `MAX` to calculate maximum revenue
 - `MIN` to calculate minimum revenue and
 - `COUNT` to calculate count customers 
```
=SUM('Customer Data'!H2:H33788)
```
```
= =SUM('Sales Data'!J2:J9922)
```
![Screenshot (241)](https://github.com/user-attachments/assets/e4b37fa6-0b90-4193-acd2-642c896c3081)

![Screenshot (226)](https://github.com/user-attachments/assets/1065bbce-2245-4042-bec3-9ef6ba252e25)

2. **Conditional Columns**: I calculated conditional columns using functions to analyze the impact of region and product on revenue.
- **Sales data**
   - `SUMIF`for overall revenue and product sold by product and region 
   - `AVERAGEIF` for average revenue product and region
   - `COUNTIF`count of product by region
   - `IFS`to create sales Category
```
=AVERAGEIF ('Customer Data'!D2:D33788,'Customer Data'!D2,'Customer Data'!H2:H33788)
```
![Screenshot (220)](https://github.com/user-attachments/assets/0e978906-2a5c-459a-9383-bcc5819ba70e)

- **Customers data**
 - `SUMIF`for overall revenue by subscription type and region 
   - `AVERAGEIF` for average revenue product and region
   - `COUNTIF`count of product by region
![Screenshot (233)](https://github.com/user-attachments/assets/1f8e5dbc-bd36-4f19-b3ba-c4f990bedda5)

#### Pivot Tables
1. **Sales Data**: Created pivot tables for
- revenue by product, Rank of revenue by product
- Regional performance,
- Product sale by region
- Highest quantity sold by region,
- monthly sales trends for different years and region,
- monthly sales trends for different years and product

![Screenshot (221)](https://github.com/user-attachments/assets/b5d080ec-763f-4303-9a4e-f079c610f287)

![Screenshot (222)](https://github.com/user-attachments/assets/671905b0-7809-41f2-9980-0eb8a380fba4)

![Screenshot (223)](https://github.com/user-attachments/assets/686d5dd3-0738-4cbf-8028-825254d5c992)

3. **Customer Data**: Created pivot tables for 
- revenue by region,
- revenue by subscription type
- count of customers by region and subscription type,
- trend of subscription per region by year
- revenue by cancellation per subscription type
- revenue by region and subscription type
- top 10  revenue by customers name and subscription type
- highest revenue by customer name per region
- Monthly sale trend by region

![Screenshot (227)](https://github.com/user-attachments/assets/f370b741-8742-4ec5-ba53-65ad11af50d0)

![Screenshot (228)](https://github.com/user-attachments/assets/0081fee5-4a88-4224-b9fb-9f3a1e6bb881)

![Screenshot (240)](https://github.com/user-attachments/assets/9b44897e-7150-46e1-8b39-717e46621846)
19d34463c96)


### SQL
I Imported the capstone data with duplicate and perform the following actions:

#### Data Cleaning
**Correct Data Types**: Ensured that all columns had the correct data types.
**Handle Null Values**: Wrote queries to handle null values appropriately.

#### Database Creation
1. **Create Databases**: I created a databases for the sales and customer datasets uing the followin query
```
create database Capstone_project
```

2. **Import Data**: Imported the capstone datasets from Excel into SQL.

![Screenshot (185)](https://github.com/user-attachments/assets/5707972a-1cec-4ef1-812e-5025db1ed50f)

3. **Create table**: I created tables for the sales and customer datasets uing the followin query
```
select * from [dbo].[Sales_Data]
```
![Screenshot (186)](https://github.com/user-attachments/assets/cb736c26-bd04-4076-ae89-71ea24dfcdd7)

```
SELECT * FROM [dbo].[Customers Data]
```
![Screenshot (193)](https://github.com/user-attachments/assets/8783f306-b486-426c-8f2f-5f5605af62d1)

4. **Created a revenue column for sales data using
```
Alter table [dbo].[Sales_Data]
add Revenue int  
update[dbo].[Sales_Data] 
set revenue = (quantity * unitprice)
```
![Screenshot (187)](https://github.com/user-attachments/assets/fe3a3ee2-37b0-4cc0-ad90-039eb3becf48)

5. Calculated total revenue generated for accuracy
![Screenshot (188)](https://github.com/user-attachments/assets/75c94090-4d1a-49ce-958c-cd67215e00fb)

#### Exploratory Data Analysis (EDA)
1. **Sales Data**:
- I Wrote queries to extract key insights based on the following questions:
  - Retrieve the total sales for each product category.
```
SELECT product, sum (revenue) as Total_sales_by_product
from[dbo].[Sales_Data]
group by Product
```
![Screenshot (189)](https://github.com/user-attachments/assets/860c8fda-d88c-44ea-b457-d9388f6fe8e7)


  - Find the number of sales transactions in each region.
```
SELECT Region, sum (quantity) as Number_of_Sales_Transactions 
from[dbo].[Sales_Data]
group by Region
```
![Screenshot (190)](https://github.com/user-attachments/assets/d9774041-3131-400c-8ae6-27020a226f8d)

  - Identify the highest-selling product by total sales
```
SELECT product, sum (Revenue) as Total_sales 
from[dbo].[Sales_Data]
group by Product
order by Total_sales desc
```
![Screenshot (191)](https://github.com/user-attachments/assets/ec879833-c715-4259-ab71-1d0881530380)


  - Calculate total revenue per product.
```
SELECT product, sum (revenue) as Total_revenue_by_product
from[dbo].[Sales_Data]
group by Product
```

**To calculate the next question i modified table by creating conditions**
```
ALTER TABLE [dbo].[Sales_Data]
ADD OrderMonth_ nvarchar(50) 

UPDATE [dbo].[Sales_Data]
SET OrderMonth_ = DATENAME (MONTH, OrderDate) 
 
ALTER TABLE [dbo].[Sales_Data]
ADD OrderYear int 

UPDATE  [dbo].[Sales_Data]
SET OrderYear = Year(OrderDate)
```
![Screenshot (192)](https://github.com/user-attachments/assets/f589b36b-ccb4-45a3-94cf-a3fe5d1da2a3)

  - Calculate monthly sales totals for the current year.
```
select ORDERMONTH_, SUM (Quantity) as Montly_sales_For_current_Year 
FROM[dbo].[Sales_Data]
WHERE ORDERYEAR = 2024
GROUP BY ORDERMONTH_
```
![Screenshot (248)](https://github.com/user-attachments/assets/08715830-9c81-4e29-bde5-9752582536ad)

  - Find the top 5 customers by total purchase amount.
```
SELECT top 5 Customer_Id,SUM (QUANTITY) AS TOP_5_BY_QUANTITY_PURCHASED
FROM [dbo].[Sales_Data]
GROUP BY Customer_Id
ORDER BY TOP_5_BY_QUANTITY_PURCHASED DESC
```
![Screenshot (247)](https://github.com/user-attachments/assets/21cf9465-f5a2-4c3d-b85c-f8d3745ea174)

  - Calculate the percentage of total sales contributed by each region.
```
SELECT Region, SUM(Revenue)/SUM(Quantity)*0.1 AS Percentage_of_Total_Sales 
FROM  [dbo].[Sales_Data]
GROUP BY Region 
ORDER BY Percentage_of_Total_Sales 
```
![Screenshot (249)](https://github.com/user-attachments/assets/760282b8-d14a-4eff-9e8f-85aa334e0d49)

  - Identify products with no sales in the last quarter. This reveal that there is no region with no sales in the last 3 quarter
```
SELECT Product, sum (Quantity) as No_Sales_in_Last_Quarter
FROM [dbo].[Sales_Data]
where OrderDate >= '2024-06-01'
group by Product
having sum (Quantity) = 0
```
![Screenshot (251)](https://github.com/user-attachments/assets/d045f268-d253-49ea-bc0c-95aad3829ebc)

2. **Customer Data**:
- Wrote queries to extract key insights based on the following questions:
  - Retrieve the total number of customers from each region.
```
SELECT REGION, COUNT (CUSTOMERID) AS NUMBER_OF_CUSTOMERS_BY_REGION
FROM [dbo].[Customers Data]
GROUP BY REGION
```
![Screenshot (195)](https://github.com/user-attachments/assets/6d476774-0d34-4d91-989f-5d79f5884eac)

  - Find the most popular subscription type by the number of customers.
```
SELECT SUBSCRIPTION_TYPE, COUNT (CUSTOMERID) AS NUMBERS_OF_CUSTOMERS
FROM [dbo].[Customers Data]
GROUP BY SUBSCRIPTION_TYPE
```
![Screenshot (196)](https://github.com/user-attachments/assets/26f289b4-3870-4f6c-9c86-1d459217db25)

  - Identify customers who canceled their subscription within 6 months.
```
select Customer_Name,Canceled, Subscription_Start
from [dbo].[Customers Data]
WHERE month (Subscription_Start) <= 6 and canceled = 'true'
```
![Screenshot (197)](https://github.com/user-attachments/assets/a7097b50-1dbb-408f-8ffb-b8b123ffde9a)

 - Calculate the average subscription duration for all customers.
```
SELECT Count(CustomerID) As All_Customers,
select AVG(DATEDIFF(DAY,subscriptionstart,SubscriptionEnd)) AS Average_Subscription_Duration 
FROM  [dbo].[Sales_Data]
WHERE SubscriptionEnd not null
```

  - Find customers with subscriptions longer than 12 months.
```
select Customer_Name,Subscription_Type, Subscription_Start, Subscription_End
from [dbo].[Customers Data]
WHERE DATEDIFF (month,Subscription_Start,Subscription_End) >= 12
```
![Screenshot (198)](https://github.com/user-attachments/assets/017926c2-2753-4782-ad31-cb4e0884a242)

  - Calculate total revenue by subscription type.
```
SELECT Subscription_Type, SUM (REVENUE) AS TOTAL_REVENUE
FROM [dbo].[Customers Data]
GROUP BY Subscription_Type
```
![Screenshot (200)](https://github.com/user-attachments/assets/c384112b-6645-49b5-b0bc-befb78802346)

  - Find the top 3 regions by subscription cancellations.
```
SELECT TOP 3 REGION, CANCELED
FROM [dbo].[Customers Data]
WHERE Canceled = 'TRUE'
```
![Screenshot (201)](https://github.com/user-attachments/assets/6826cd36-58a0-44cf-9c24-83150bec534f)

  - Find the total number of active and canceled subscriptions.
```
SELECT CANCELED FROM [Customers Data]
COUNT
 (CASE WHEN STATUS = 'TRUE' THEN 1 ELSE 0 END) AS CANCELED_SUBSCRIPTION,
 COUNT (CASE WHEN STATUS = 'FALSE' THEN 1 ELSE 0 END) AS ACTIVE_SUBSCRIPTION
GROUP BY SUBSCRIPTION_TYPE
```

#### Visualization Preparation
1. **Export Data**: I exported cleaned and aggregated data for visualization in Power BI.

### Power BI
#### Data Import and Transformation
1. **Import Data**: Imported data from Excel into Power BI.
2. **Transform Data**: to checked for column consistency, including column quality, distribution, and profile.

#### Measure Creation
1. **Sales Data**:
   - Created measures like total revenue and count of customers.
2. **Customer Data**:
   - Created a conditional column (cancellation count) for canceled subscriptions based on true or false values.
   - Created several measures such as cancellation rate and total number of customers.

#### Dashboard Creation
1. **Sales Data**:
   - Built a Power BI dashboard that visualizes the insights found in Excel and SQL.
   - Included a sales overview, top-performing products, and regional breakdowns.
2. **Customer Data**:
   - Built a dashboard that visualizes key customer segments, cancellations, and subscription trends.
   - Included slicers for interactive analysis.

### Conclusion
This repository showcases my ability to clean, analyze, and visualize data using Excel, SQL, and Power BI. It includes detailed steps for each tool, highlighting my proficiency in data cleaning, exploratory data analysis, and creating compelling visualizations and dashboards. The project demonstrates my comprehensive understanding of data analysis techniques and my ability to apply them to real-world datasets.
