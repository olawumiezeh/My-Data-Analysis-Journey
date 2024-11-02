# My-Data-Analysis-Journey

This is where I document my practices and projects  while learning with Incubator Hub (LITA) which started on 19th of August 2024

[INTRODUCTION TO DATA ANALYSIS](#introduction-to-data-analysis)

[TOOLS USED](#tools-used)

[EXCEL CLASS](#excel-class)

[Power BI Class](#power-bi-class)

[PowerBI Assignment ](#powerbi-assignment)

[EXCEL FUNCTIONS 1 AND PRACTICES](#excel-functions-1-and-practices)

[EXCEL FUNCTIONS 2 And Practices](#excel-functions-2-and-practices)

## INTRODUCTION TO DATA ANALYSIS
Terminologies used in Data Analysis and Definitions 
---
### Terminologies used in Data Analysis and Definitions 
  Purpose of Data Analysis
- To help business owners to understand what is working, what is not working and what should be focused on.
- To make more money and to reduce cost. 
- To help companies to make decision, prediction and recommendation using data.
#### Data Set- Collection of different data points
#### Data Points- Individualized data category e.g in a class we have participants, gender,location,academic level, profession which are called data point
#### Operational Systems- Any system that an organisation uses to manage their business which can also be use to manage data.E.G Laptop ued by supermarket to record sales & profits. Youtube, used by organisations to train people etc.
#### Analytical Systems- What is use to analyse data i.e Analytical toos like Power Bi, microsoft Excel, Tableau etc.
#### Data Storage
Data can be stored either on premises or on cloud
1. On Premises- Data stored within the organistion on a centralise server or within the organisation internet. Such can not be accessed outside.
2. On Cloud- Data stored in the data warehouse centres. You buy a big space in the data centres to store your data. Examples of data centres are Microsoft, Google, Amazon etc.
### Data Structure
Structured data, Semi structured dat, Unstructured data
1. Structured Data- Data in a table format
2. Semi structured Data- Data that is not in a table format but in JSON form or XML format
3. Unstructured Data- Data that comes in files i.e raw data
### ETL- A term used to transform data into a structure that can be use to analyse. It means Extract, Transform, Load
ETL is everything you do up to the point of analysis.
1. Extract- You are connecting to the data source to extract data ( data source or satbse can be either on premises or on cloud)
2. Transform- After extracting the data, you then transform to the structure that you need for analysis.
3. Load- Move your clean data which is analysis ready to your analysis tool which can be Power Bi or Excel.
ETL Tools for microsoft is Power Query, it works with Excel and Power Bi
### Data Analysis Life Cycle
1. Ingest Data- This means to get your data from your data source into th etool for data transformation.
2. Transformation- This is whe you change ddata to how you want it and make it analysis ready.
3. Modelling- You bring dat from dierent sources, relate them together so as to build a single drepot.
4. Visualisation- Turning dta into visuls, charts and graphs
5. Analysis- Using stistical tools to analyse your data. Stastical tools like mean,mode nd media
6. Presentation- Present your findings
## TOOLS USED
- Microsoft Excel for;
  1. Data Cleaning
  2. Analysis
  3. Visualization
- SQL: Sequeled Query Language for querying of data
- GitHub: For portfolio building
- Power BI (Business Intelligence) for;
  1. Data entry
  2. Data Cleaning
  3. Data Summarization and Visualization  
 
### EXCEL CLASS
Data Cleaning and Preparations
This is the initial phase of data entry. We perform actions like;
 1. Data Entry
 2. Formatting
 3. Data Validation
#### EXCEL FUNCTIONS 1 AND PRACTICES
- Aggregate Functions
  1. SUM: To add numbers in a column
  2. AVERAGE: To get average number in a column
  3. COUNT: To count a column with numbers
  4. COUNTA: To count a column mix with both numbers and text
  5. MAX: To get highest number in a column
  6. MIN: To get lowest number in a column 
  7. LARGE: To get highet number in a column with a criteria e.g 2nd highest number, 3rd highet number etc
  8. SMALL: To get lowest number in a column with a criteria e.g 2nd lowest number, 3rd lowest number etc 
- Aggregations with conditions
  1. SUMIF: To add numbers where there is conditions in a column
  2. MAXIF: To get highest number with a condition in a column e.g highest salary in a specified location,
  3. MINIF: To get lowest number with a condition in a columne.g lowest salary in a particular city 
  4. AVERAGEIF: To get average number with a condition in a column e.g average salary in Kano from a column containing different states
  5. COUNTIF: To count a column with a condition
#### EXCEL FUNCTION 1 PRACTICE
![Aggregate Functions](https://github.com/user-attachments/assets/f38039dd-df65-43e6-bd91-785c16e226d7)

![Aggregate Conditionals](https://github.com/user-attachments/assets/8b427dba-b112-4573-93a0-0a6914088237)

#### EXCEL FUNCTIONS 2 And Practices
Here, we perform task like
  1. Numbers Extraction
  2. Text Extraction
  3. Text Cleaning
     
 ##### Numbers Extraction. I made use of;
- LEFT Function : To extract from left side of the original text
- MID Function: To extract from middle part of the original text
- RIGHT Function: To extract from right part of the original text
##### Numbers Extraction Practice
![Numbers Extraction](https://github.com/user-attachments/assets/fd295677-b857-4a44-bff3-ab27a7a6cd6b)
##### Excel Text Extraction 1. Here, I made use of;
- TRIM Function: To eliminate unnecessary space in a text
- PROPER Function: To capitalize first letter in a word
- UPPER Function: To capitalie all letters in a word
- LOWER Function: To male all letters to be in lower case
- RandBetween Function: To generate random numbers
- $ Function: To join two text
- Control A- Open Functional Argument Box
- Functions to join letters- concatenate, concate, textjoin
##### Text Extraction Using Excel
![TEXT CLEANING 1](https://github.com/user-attachments/assets/4de4f23f-7b72-4e66-b1ca-4be9800ab139)

##### Text Extraction 2. Here I combined two different functions to extract text
LEN Function- to select the whole text
FIND Function- To search in a text i.e to search for a space
CONCATENATE- To join words together
LEFT Function
Right Function
##### Text extraction 2 practice
![TEXT CLEANING 2](https://github.com/user-attachments/assets/78d4dbab-3975-49f4-baf7-639c73da23e2)
##### Text Extraction 3. Here, I made use of & FUNCTION to join two words together with a space in between
![TEXT CLEANING 3](https://github.com/user-attachments/assets/ebc59854-45e0-45a0-84ad-3a74f28e7d0b)
##### Text Extraction 4. Here, I made use of this FUNCTION =MID(B6,FIND(".",B6)+1, FIND("@",B6)-1 -  FIND(".",B6)) and then autofill the remaining rows
![TEXT CLEANING 4](https://github.com/user-attachments/assets/7b00bb8e-5f77-42e6-a476-164d75721790)

#### EXCEL FUNCTION 3. LOOKUPS
- LOOKUP means that you are getting an information from another workbook or worksheet into the workbook you are working on
- VLOOKUP ( Lookupvalue, table array, column indexnumber, range lookup)
- Lookupvalue- what is common in the two tables
- TableARRAY- Where you are getting the data from
- ColumnIndexNumber- Position of the column you want to get from the table
- RangeLookup- What kind of lookup you want to do
- Types of RangeLookup
   1. Exact Match- Exact text you want it to find
   2. Approximate Match- Text that is closer to what you want it to find  
#### PIVOT TABLE For Data Visualiation and Reporting
### Power BI Class
#### Data Cleaning
- To clean a data we were taught to first: 
 1. Get Data from the source that its been stored
 2. Transform Data
 3. Check the Column Quality, Column Profile and Column Distribution
 4. Check the data type if it is correct
 5. Check the consistency of the columns
- Functions used
  1. Remove columns, Remove rows, Promoted header,Change data type

#### Text Extraction using PowerBI
We used different functions to achieve this, functions like:
lowercase, UPPERCASE, Trim, Capitalize Each Word, Merge column

![POWER BI TEXT EXTRACTION 1](https://github.com/user-attachments/assets/933d59ab-7fea-4c8d-800d-e144fa7cd07d)
##### PowerBI Assignment 

We were given an uncleaned table containing empty rows and columns with Column Names, Column First name, Column Surname,
###### Task: to get email address using the first name column.

![POWER BI TEXT EXTRACTION 2](https://github.com/user-attachments/assets/fa2440af-c064-41fb-97ad-03acf9a7c673)
##### PowerBI Class Project

We worked on a real time data which is a HR data of a company that contains columns like; Attrition, Number of employee and their Age, Department, Gender, Education Field,Job role, Marital status etc. This data gave an insight to the staff strenght of the company, The number of people that have left the company and those remaining

We performed visualisation on the data using Power BI and we are able to come up with visuals relating different columns together.

###### Task
- To understand the attrition rate
- To know the number of people that have left the company
- To know the reason for people leaving the company
- To know the department in the company that has the highest attrition
- To have the understanding of the age group that has the highest attrition
- To have an understanding of the gender that has the gighest attrition
- Generally, we were able to visualise the total number of people remainining in the company
- To have an understanding of employee's job satisfaction and how it relates to attrition
Here is a picture of the visualisation below

![HR Data](https://github.com/user-attachments/assets/306fdcd5-df8d-4966-be91-3449e8329b3e)

- Deductions from the visualization
  
1. *Total Number of Employee is 1470. Out of the 1470, 237 people left the organisation.Leaving the total number of 1233 as the current employees in the company*

2. *Attrition Rate is 16%*

3. *Most people that left are from R&D DEPARTMENT*

*Employee who had the job role as Laboratory Technician has the highest number of attrition. 20 of them expressed that they are **very dissatisfied** with their job role, 8 of them expressed that they are **dissatisfied** with their job role, 21 expressed that they are **satisfied** with their jobrole and 13 of them expressed that they are **very satisfied** *



|Heading 1|Heading 2| Heading 3| Heading 4|
|---------|---------|----------|----------|
|Table 2|Table 2|Table 3|Table 4|













