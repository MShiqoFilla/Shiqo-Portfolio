# Data Engineering Portfolio

Greetings! Here I want to share some of my personal works related to data engineering. I have some skills in operating technologies like Python programming language, Relational databases (Postgresql, SQL Server etc), and workflow orchestrator like Apache Airflow. I hope this page is able to showcase my ability in this topic and records my essential self development throughout the learning processes.

### Books Database Normalization in SQL Server and Postgresql

This project attempts to normalize the table of books data from bukabuku.com that has been stored in the previous project. Normalization means that the "one big table" is broken down to several tables that has relationship with each others to make the data less redundant and more effective. The work is done in DBeaver as database tools with Postgresql RDBMS and SSMS for SQL Server.
- Technologies: *Postgresql (DBeaver), SQL Server (SSMS)*.
- Final Results: Database with normalized form.
- Link: [Books Database Normalization in SQL Server and Postgresql](https://github.com/MShiqoFilla/Books-Database-Normalization)

### Bukabuku.com Books Data ETL Pipeline

It's a web scrapping project to get the data of the books that are listed in an online bookstore bukabuku.com. Some of the data includes the title, author, language, pages, price of the book, etc. I built a simple pipeline with Airflow to automate the works from extracting data from the website, transform it, and store it to local postgresql database.
- Technologies: *Python (beautifulsoup, pandas), Apache Airflow, Docker, Postgresql*.
- Final Results: Database and csv file containing books data from bukabuku.com. 
- Presentation link: [Bukabuku.com Books Data ETL Pipeline](https://drive.google.com/file/d/1Y-yXB__JivMiGWQOvGIpF4E1W7Vhe8ig)

### JKT48 Members Data Web Scrapping

This is a project to extract general data of JKT48 (a girlgroup from Jakarta) members that available in jkt48.com. The object is to get some of their data that is openly available from the website and store it in personal database. 
- Technologies: *Python (beautifulsoup, pandas, pymysql), MySQL database*.
- Final Results: Database containing the JKT48 members data. 
- Presentation link: [JKT48 Members Data Web Scrapping](https://drive.google.com/file/d/1R-C8PRNPZ8gCjppUQBFRJEY4KKkim-8D)

### Exploratory Data Analysis using MySQL

This is some SQL queries documentation about some exploratory data analysis that I record for intern vacancy test at Schoters Ruangguru. 
- Technologies: *MySQL*
- Link: [Exploratory Data Analysis using MySQL](https://github.com/MShiqoFilla/Exploratory-Data-Analysis-using-MySQL/blob/main/Exploratory%20Data%20Analysis%20Menggunakan%20MySQL.sql)

### Simple CRUD Project with Python and MySql

Here is the project to create a simple Create, Remove, Update, Delete (CRUD) system with Python programming language.  The system will input and saves the data of students and store them in MysQL database.
- Technologies: *Python (pymsysql), MySQL*
- Link: [Simple CRUD Project with Python and MySql](https://github.com/MShiqoFilla/CRUD-Project/)



