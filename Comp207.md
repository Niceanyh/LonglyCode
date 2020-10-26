# Database Development 

> overview:  
>> - Basic of SQL and the relational model  
>> - Relational DBMS Component  
>> - Beyond Plain Relational DBMS  


* [Week1](#1)
* [Week2](#2)
* [Week3](#3)
* [Week4](#4)



<h2 id="1">Week1</h2>

### Lecture 1  Introduction to SQL  
#### Relational database :
&#8195;• Data is organised in tables(also called relations)  
&#8195;• All element in an attribute are of the same datatype  
&#8195;• Each table has a schema. The schema of Items is Items(name,price,number)  
&#8195;• Columns/attributes are fixed, rows depends on the table can change  
&#8195;• For OO Programmingm, if two rows are the same, we view them as being the same item  


#### SQL :
&#8195;• Relational database are accessed using SQL(Standard Query Language)    
&#8195;• Data Definition Language(DDL):Create/alter/delete databases,tables and their attributes.  
&#8195;• Data Manipulation Language(DML):Add/remove/update and query rows in tables.  
&#8195;• Transact-SQL  

### Lecture 2  SQL DDL(Data DEfinition Language)
#### creat a batabese
&#8195;CREAT DATABASE databasename;(not case-sensitive)  
#### creat a table
&#8195;CREATE TABLE Table_name(  
&#8195;column1 datatype,  
&#8195;column2 datatype,  
&#8195;column3 datatype,  
&#8195;)  
&#8195;// The schema is Table_name(column1,column2,column3)  

#### Datatypes
&#8195;INT – integers  
&#8195;FLOAT – decimal numbers  
&#8195;CHAR(x) – x is an integer, fixed length string  
&#8195;VARCHAR(x) – x is an integer, variable length string  
&#8195;DATE – Format YYYY-MM-DD, e.g. 1990-11-10 would be the 10th of November 1990  
&#8195;DATETIME – for time and dates, Format YYYY-MM-DD HH:MI:SS.  
&#8195;XML – for XML files  
&#8195;BLOB – binary files (e.g. programs)  

#### Unique
&#8195;CREATE TABLE Employees (  
&#8195;birthday DATE,  
&#8195;first_name VARCHAR(100),  
&#8195;family_name VARCHAR(100),  
&#8195;CONSTRAINT UC_Employees UNIQUE(birthday,first_name));  
&#8195;// Unique in a table means that for each value, there is at most one row in the table where the set of attributes take that value.   

#### Primary Key
&#8195;Primary keys must be unique and there can only be 1 primary key per table.   

#### Foreign Key
&#8195;A foreign key is used to link two tables together explicitly.  

#### DROP & Modify
DROP DATABASE CS_Store;  
DROP TABLE Employees;  
&#8195;  
ALTER TABLE Employees ADD email VARCHAR(100);  
&#8195;//Adds an email attribute  
ALTER TABLE Employees MODIFY email VARCHAR(200);  
&#8195;//Changes the email attribute to allow longer emails  
ALTER TABLE Employees DROP COLUMN email;  
&#8195;//Removes the email attribute again  

### Lecture 3  SQL DML(Data Manipulation Language)
#### Insert rows into a table

#### Delete rows from a table

#### Update rows in a table

#### [Query a table](#101)







<h2 id="2">Week2</h2>  

### Lecture 4  SQL Queries -require part 
<h3 id="101">Lecture 4 SQL Queries -require part</h3>  

### Lecture 5  SQL Queries -optional part

### Lecture 6  SQL Queries -Misc
hello,world!  


