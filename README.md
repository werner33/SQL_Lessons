# SQL Lesson

### SQL Course Overview
  
  SQL and other query languages are used to interact with databases. As long as you work with software, you can be sure that a database - and probably more than one - is not far away. Some of you likely work with SQL on a daily basis where others might only write queries occasionally. In this class, we will review some of the basic aspects of SQL, but since you have already learned SQL basics, we will move on to some of the more advanced concepts quickly. 
  
  If you would like to review basic SQL, you can always return to the Core curriculum in [Module 4](https://github.com/joinpursuit/Pursuit-Core-Web/blob/master/full_stack_express/README.md).
  
  Through out this two part class, we will lean heavily on [W3's Sql lessons and live database](https://www.w3schools.com/sql/default.asp). 
  

### Basic Review of SQL

Let's quickly review one of the bedrocks of any web application CRUD: CREATE, READ, UPDATE and DELETE. Almost everything we do in a web application is one of thesefour types of actions. Now, just as a quick reminder, let's see how CRUD maps to the HTTP methods and the SQL commands: 

|  CRUD  | HTTP  | SQL          |
|------- |-------|--------------|
| CREATE | POST  | INSERT INTO  |
| READ   | GET   | SELECT       |
| UPDATE | PUT   | UPDATE       |
| DELETE | DELETE| DELETE FROM      |

And to review SQL syntax quickly, our query is usually composed by starting with one of these key words. For example: 

`SELECT name, age, height FROM users` or 'INSERT INTO users SET score=100 WHERE age > 14'

We won't spend too much time reviewing these more simple queries, but you can practice with each of them here: 

(SELECT)[https://www.w3schools.com/sql/sql_select.asp]
(UPDATE)[https://www.w3schools.com/sql/sql_update.asp]
(INSERT INTO)[https://www.w3schools.com/sql/sql_insert.asp]
(DELETE)[https://www.w3schools.com/sql/sql_delete.asp]


