# PostgreSQL Data Integration Project
PostgresSQL project for WGU. 


## Project Description/Purpose

The purpose of this project is to create a data integration pipeline using PostgreSQL to help a hypothetical company determine the highest grossing postal code per quarter. By analyzing the revenue data, the company can make informed decisions about where to launch new stores.

## Database Schema Design

The database consists of two tables:

* sales_detailed2: contains detailed information about each rental transaction, including rental id, postal code, district, rental date, and sales amount.
* sales_summary2: summarizes the rental transactions by postal code and quarter, including the total number of rentals and total sales amount.

## PostgreSQL Code

The PostgreSQL code used in this project consists of six parts: creating the tables, extracting data and inserting it into the tables, creating a function to summarize the data, creating a trigger to refresh the summary table automatically, creating a procedure to refresh the detailed table, and executing the procedure to refresh the detailed and summary tables.
