

###Amanda Thomson

###Assgmt07 – Functions

###12/5/2020

###IT FDN 130 A Au 20 | RRoot

###https://amthomson206.github.io/DBFoundations-Module07/

# **SQL Functions: Scalar, Inline and Multi-Statement**

## Introduction
There are various types of functions within SQL and understanding the variances is essential when it comes to work within big data.  Functions enable the user to perform calculations, modify data views, and partition data to best suit the need of the data consumer.   User defined functions (UDF’s) are a function that accepts, modifies and returns values based off sets of parameters of the data.  

## Use of a SQL User Defined Fuction

When working within SQL, the user would take advantage of using SQL User Defined Functions (UDF’s) when there is a need to construct a view of data within the constructs of established parameters.  Instances of such could be the need to do calculations of set data within a specific table(s) or database, to focus on smaller set of the data (if within a large data set) to enable better bug/issue handling, and to allow for easier reuse of code.   

## Difference in Scalar, Inline, and Multi-Statement Functions
There are a few different types of UDF’s within SQL, including Scalar, Inline, and Multi-Statement functions.  Each servers a specific purpose.  Scalar functions are an easy way to define a constant value but are limited to return only one value.  These can be used as a defined value for a column within a table.   Inline functions is one that returns table data types and also accepts parameters.  Unlike Scalar, Inline functions have the ability to return multiple lines of data.  They have the functionality to allow for joins between tables to create a parameterized view of the data between those tables.    The most complex of the User Defined Functions is the Multi-Statement function (MSTVF).  This function will return the results of multiple statements allowing for the user to establish a more precise view of the data, aggregating at a more granular level to a table.     

## Summary
As explained in the above, functions can be simplistic in nature, as a scalar function, or complex through multi-layered aggregation using MSTVF’s. Though at any level they are essential to understand for users who are required to parse out and analyze data within large datasets.  
