## My SQL ( Sturctured query language )
> **Advantage**  
<br />

--> High speed and Fast query processing     
--> Open source   
--> Allows multiple views    
--> Efficient and portable  

<br />  

> **Disadvantage**    
<br />

--> High operation cost ( _commercial websites, for example_ )  
--> High maintenance  

### What is SQL SYNTAX ?    
--> The rules and guidelines to follow while coding mysql commands.  
--> Case insensitive syntax, both cases can be used to write any keyword.  
--> RDBMS ( Relational Database Management System )  
<br />  

## SQL Datatypes  

* NUMERIC- `INT`  `BIT`  `FLOAT`  `BOOLEAN`
* STRING DATA- `CHAR`  `VARCHAR`  `TEXT`  
* DATETIME- `DATE`  `DATETIME`  `TIMESTAMP`  

## SQL COMMANDS  

DATA DEFINITION LANGUAGE ( DDL )   
* CREATE  
* ALTER
* DROP
* TRUNCATE    

<br />

> SQL CREATE STATEMENT  

_SYNTAX_ :   
```
Create table table_name (
"column1" "data type", 
"column2" "data type",
"column_3" "data type");
```

for example-  
`
Create Table Employee(
EMP_ID int,
Name varchar,
Address Varchar);
`  

<br />

> SQL ALTER STATEMENT  

_SYNTAX_ :  
```
ALTER table table_name
ADD (
"column_name1" "data type",
"column_name2" "data type",
"column_name3" "data type");
```  
  
for example-  
`ALTER TABLE Employee ` 
`ADD (DOB Date); `




