# Executive Summary
The goal of this lab is to understand relational databases and how they work as well as the concepts behind them and how they're used. 

# Data, Information and Knowledge 
## Relational Data

* What is the difference between data, information and knowledge? 
    * Data is raw information with no context. Information is when the data is given context and meaning. Knowledge is when you understand the information. 

* If you were creating a database for a small company and two tables you identify are customers and orders explain the following:
(be sure to use the example in the chapter as a guide - customers and orders would be like clubs and events) 
a) What would be the primary key in the customers and orders table? 
   * The primary key of the customer table would be CustomerID. The primary key of the order table would be OrderID.
    
b) How would the customers and orders table be related? 
   * It would be a one-to-many relationship with the customer table being the "one". 
    
c) What would be the foreign key in the orders table? 
   * The foreign keys in the orders table are CustomerID and EmployerID.
    
d) The orders table would likely have a date field.  Explain why it is important to properly define the data type of a field. 
   * This is important if you intend to use it to do any type of calculations, it is also important for formatting. 
 
## Big Data

* Briefly describe the four "Vs" of big data 
   * Volume: the scale of the data, how much of it there is. 
   * Velocity: the speed of data streaming, how fast data can be transported. 
   * Variety: Different types of data formats, this is necessary because the technical details of data cannot always be predicted. 
   * Veracity: the trustworthiness of the data, how accurate is it. 
* What types of technology have driven the increased need for big data? 
   * Web services that operate on a large scale and have a large number of users/customers. Social networks/forums especially. 
 
# Structured Query Language (SQL)
* Explain RDBMS and how it relates to SQL and the purpose of SQL 
   * RDBMS stands for relational database management system. It is a fundamental part of modern SQL because that's how it defines which databases are related to each other and in what way. 
* Pick two related tables from the diagram provided in the "module - SQL" and explain the relationship between them
a) which is the primary key?
b) which is the foreign key?
* Using W3Schools, try out a 
a) select statement 
a) where clause 
and upload screenshots of the results.
* Explain how SQL injections are a security threat and what can be done to reduce the issue. 
  
# Conclusion
Include what you have learnt from this lab
