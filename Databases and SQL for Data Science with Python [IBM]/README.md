# Databases and SQL for Data Science with Python [IBM]

In this course, I developed a solid understanding of SQL, starting with the basics like writing SELECT, INSERT, UPDATE, and DELETE statements. I learned how to filter and organize data, differentiate between DML and DDL, and manage tables. As I progressed, I was introduced to more advanced topics like JOINs, Stored Procedures, and ACID Transactions, which I found challenging but rewarding.<br/>
I had the chance to practice what I learned through hands-on labs, working with real databases and data science tools. By the end of the course, I felt more confident in my ability to use SQL, especially after applying my skills to analyze real-world datasets in the final project.<br/>
  
**Skills gained in this course**: `Python Programming`, `Cloud Databases`, `Relational Database Management System (RDBMS)`, `SQL`.

## Course Content and Notebooks

### Module 1 - Getting started with SQL

Description from Coursera: In this module, you will be introduced to databases. You will learn how to use basic SQL statements like SELECT, INSERT, UPDATE and DELETE. You will also get an understanding of how to refine your query results with the WHERE clause as well as using COUNT, LIMIT and DISTINCT.

### Module 2 - Introduction to Relational Databases and Tables

Description from Coursera: In this module, you’ll learn more about relational database concepts and their importance. This module helps you to understand the process of creating a table in your database on MySQL using the graphical interface and SQL scripts. Further, you will also learn how to alter the entries or delete the entries for any table in the database, or even delete the table itself.

### Module 3 - Intermediate SQL

Description from Coursera: This module helps you learn how to use string patterns and ranges to search data and how to sort and group data in result sets. You will also practice composing nested queries and execute select statements to access data from multiple tables.

### Module 4 - Accessing Databases using python

Description from Coursera: In this module you will learn the basic concepts of using Python to connect to databases. In a Jupyter Notebook, you will create tables, load data, query data using SQL magic and SQLite python library. You will also learn how to analyze data using Python.

#### Notebooks

4.1.Insert_Update_SQLite
- Description: This notebook is a step-by-step guide to creating and working with a SQLite database using Python. It covers the basics of setting up a database, creating tables, inserting data, querying data, and retrieving results into a Pandas dataframe. The notebook also includes a task on updating records and emphasizes the importance of closing database connections to free up resources.<br/>
- Main Topics:
    - SQLite database creation
    - Table creation
    - Data insertion
    - SQL queries
    - Data retrieval
    - Pandas dataframe integration
    - Database connection management
    - SQL update statements

4.2.SQLmagic_SQlite
- Description: This notebook provided a hands-on introduction to using SQL within a JupyterLab environment, specifically leveraging SQL "magic" commands. It guided users through creating and connecting to an SQLite database, executing SQL queries, and manipulating data within the database. The notebook also demonstrated how to integrate SQL queries with Python, convert query results into pandas DataFrames, and visualize data using the seaborn library. Overall, it aimed to enhance SQL skills for simplified database access and analysis.<br/>
- Main Topics: 
    - SQL Magic
    - JupyterLab
    - SQLite
    - SQL Queries
    - Database Management
    - Python Integration
    - DataFrame Conversion
    - Data Visualization
    - ipython-sql Extension

4.3.Analyzing_SQLite
- Description: This lab guided me through analyzing a real-world dataset using SQL and Python. I worked with Chicago’s socioeconomic indicators dataset, learned how to store data in an SQLite database, executed SQL queries, and visualized results using Python.<br/>
- Main Topics
    - SQLite Database**
    - SQL Queries
    - Data Visualization
    - Pandas Integration


### Module 5 - Course Assignment

Description from Coursera: In this module, you will be working with multiple real-world datasets for the city of Chicago. You will be asked questions that will help you understand the data just as you would in the real world. You will be assessed on the correctness of your SQL queries and results.

#### Notebooks

5.1.RealDataPractice-v5_sqlite_Learner
- Description: This notebook provided a hands-on experience in working with a real-world dataset using SQL and Python. Using data from the Chicago Public Schools' 2011-2012 School Report Cards, I learned how to connect to a SQLite database, load data from CSV files into the database, and perform various SQL queries to extract, manipulate, and analyze the data. I practiced retrieving metadata, solving specific problems using SQL queries, and applying built-in SQL functions for data analysis.<br/>
- Main Topics:
    - SQL Database Connection
    - Data Loading (CSV to SQLite)
    - Metadata Retrieval
    - SQL Querying
    - Data Manipulation
    - Data Analysis

5.2.Final_assignment
- Description: This notebook provided guidance on analyzing three datasets related to the city of Chicago: Socioeconomic Indicators, Chicago Public Schools, and Chicago Crime Data. The process involved loading these datasets into an SQLite database and executing various SQL queries to extract insights and address specific questions. The focus was on exploring public safety, education, and socioeconomic factors in Chicago through data loading, SQL query execution, and problem-solving.<br/>
- Main Topics:
    - Data Loading
    - SQLite Database
    - SQL Queries
    - Socioeconomic Analysis
    - Public Safety
    - Education Data
    - Crime Analysis

### Module 6 - Advanced SQL for Data Engineer (Honors)

Description from Coursera: This module covers some advanced SQL techniques that will be useful for Data Engineers. In this module, you will learn how to build more powerful queries with advanced SQL techniques like views, transactions, stored procedures, and joins.