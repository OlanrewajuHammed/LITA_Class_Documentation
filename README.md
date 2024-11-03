# LITA_Class_Portfolio

## Project Title: Comprehensive Data Analysis

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Excel](#excel)
----
- [Foundation of Data](#foundation-of-data)
- [Introduction into Microsoft Excel](#introduction-into-microsoft-excel)
- [Basic Excel Function](#basic-excel-function)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Report and Dashboard](#report-and-dashboard)
- [Summary](#summary)

[SQL](#sql)
----
- [Introduction to SQL](#introduction-to-sql)
- [Basic SQL Queries](#basic-sql-queries)
- [Exploratory Data Analysis](#exploratory-data-analysis)

[Power BI](#power-bi)
----
- [Introduction into Power BI](#introduction-into-power-bi)
- [Component of Power BI](#component-of-power-bi)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Report and Dashboard](#report-and-dashboard)
- [Summary](#summary)

[Capstone Project](#capstone-project)
---
- [Excel](#excel)
- [SQL](#sql)
- [Power BI](#power-bi)

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
- Capstone dataset which include 

### Tools used
The tools used include 
1. Microsoft Excel: [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel?ocid=ORSEARCH_Bing&msockid=31ccbb7207cd643010e1ae7e060d65f3)
   - Used for Data cleaning, analysis, and basic visualization.
3. SQL Server: [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads?msockid=31ccbb7207cd643010e1ae7e060d65f3)
   - Used for Database management and querying.
5. Power BI:[Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads)
   - Used for data visualization and dashboard creation.

#### Excel
Here our facilitator was able to take us through microsoft excel where we were able to navigate data
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
The aim of this phase was to perform data manipulation tasks in other to answer questions on different aggregate using different code. Functions were used based used at differinclude;
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
This repository showcases various aspect completed during my Excel class, highlighting my proficiency in Excel skills and techniques. I began with learning foundational data literacy (Foundation of Data), which laid the groundwork for my understanding of data analysis and manipulation. The main source of data used in these projects was provided by the facilitator during the course of learning. This journey culminates in developing advanced dashboards for data visualization.

### SQL
Here our facilitator was able to take us through proper basic sql commands and queries. Navigating different Rational Database Management system (SQL server and Postgress) to ensure optimum use of oppotunity for diverse students and different organization preference 
#### Content
1. Introduction to SQL
2. Basic SQL Queries
3. Exploratory Data Analysis

### Introduction to SQL
This section encompass the exposure to the theoretical aspect of sql ranging from:
1. Explanation of SQL and its rules. Some of which are
  - Not being case sensitive, Statement depending on text line
2. What database in sql means and how it store data
3. Basic SQL commands and their types
  - Data definition Language (e.g create), Data Manipulation Language (e.g insert), Data Control Language (e.g grant), Data Transaction Language (e.g commit) and Data Query Language (create)
4. Several basic function which include
  - Craeting database, creating table and different data command
  - SQL Data types - SQL keys - SQL Clause - SQL Operators - SQL Join - SQL Aggregate - SQL Views

### Basic SQL Queries
This phase include utilizing several commands to bring insightful conclusions from data and also taing *primary key* into consideration. The process include:
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

3. Inserting values into table created
```
insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09')
```

4. Creating auto-numbering command
```
CREATE TABLE Salary (
salary_id int identity (1,1)not null,
```

5. Creating queries for agreegate using functions like
   - sum, min,max, average count
```
SELECT SUM(Salary) AS TOTALSALARY FROM Salary
```

6. Logical operations
```
