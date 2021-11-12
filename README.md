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

[SELECT](https://www.w3schools.com/sql/sql_select.asp) 
[UPDATE](https://www.w3schools.com/sql/sql_update.asp)
[INSERT INTO](https://www.w3schools.com/sql/sql_insert.asp) 
[DELETE](https://www.w3schools.com/sql/sql_delete.asp)

### Getting Specific with Selectors

SQL is a powerful language with all kinds of syntax to help us tailor our queries. Let's look at a couple you may not be familiar with:

[LIKE](https://www.w3schools.com/sql/sql_like.asp) - LIKE is used to match text patterns in a particular column. It is somewhat similar to a regular expression in Javascript and other programing languages. Keep in mind that the text you are looking to match is case-insensitive.

Challenge: Write a query that returns any customers where the contactName has an a in the second and fifth position. 

[BETWEEN](https://www.w3schools.com/sql/sql_between.asp) - BETWEEN is used to search for a value, usually a number, that lies in a bounded range. The query would look something like this :

`SELECT * FROM users WHERE accountTotal BETWEEN 1000 AND 9999;`

Challenge: On the order details table, write a query that returns all orders where the quantity is between 17 and 20.  

### Grouping

When we want to see certain records collapsed into a single row, for example, when we would like to see the number of users in a certain country, we can use `GROUP BY`, passing a column. All records that have that column in common will be grouped together. 

[GROUP BY](https://www.w3schools.com/sql/sql_groupby.asp)

Challenge: On the W3 orderDetail table, write a query that gets the number of products in each order. 


### Fun SQL Resources 

[W3 SQL](https://www.w3schools.com/sql/default.asp) - This is a real treasure as a reference. 

[SQL Murder Mystery](https://mystery.knightlab.com/) -  a great free game with lots of practice in more complex SQL queries. 

[SQL ZOO](https://sqlzoo.net/wiki/SQL_Tutorial) - lots of practice starting with very easy SQL to much more advanced. 

[SQL Police Department](https://sqlpd.com/) - This game only has a few levels for free and can feel a bit elementary, but fun none-the-less.


