# Pewlett-Hackard-Analysis

##  Overview
The purpose of this analysis is to determine the number of Pewlett Hackard employees who will be retiring in the near future, grouped by title, and which of those employees will be eligible for a mentorship program the company is considering implementing to keep a certain number of retiring employees working on a part-time basis to train and lend their expertise to the new hires who will be taking their place.

##  Summary
* There are 72458 employees who will be retiring in the near future.
* Of those 1549 are eligible to participate in the mentorship program.
* The two titles with the largest amount of turnover will be Senior Staff and Senior Engineers.
* ![image](https://user-images.githubusercontent.com/116078337/209249897-917bfeca-f082-44d0-8033-8331b25ab9dc.png)


##  Results

In this analysis using PostgreSQL, the number of retiring employees by title and the employees eligible for the mentorship program were distilled by combining 6 csv files with different aspects of employee data. 
Two additional queries that would give further insight:
* 1.  A query to determine the number of retiring employees in each department.
* 2.  A query that keeps the same birthdate but expands the years of the hiring date to include employees who are of retirement age but who may not have been with the company their entire career.
