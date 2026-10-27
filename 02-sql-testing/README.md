# SQL Testing Project – E-commerce Database
## Project Overview

This project focuses on testing an database using SQL queries. The goal was to verify data accuracy, identify data integrity issues, and validate relationships between database tables.

This is an independent portfolio project created for learning purposes to demonstrate my practical SQL testing skills as an aspiring Junior QA Tester.

## Database Environment
- **Database:** MariaDB 10.4.32
- **Local Environment:** XAMPP 3.3.0
- **Database Management Tool:** phpMyAdmin
- **Database Name:** qa_sql_portfolio
- **Database Type:** E-commerce test database

## Database Structure
The project includes the following tables:
- customers – customer information
- products – product details, prices, stock levels, and categories
- categories – product categories
- orders – customer orders, dates, statuses, and total amounts
- payments – payment details, dates, and payment statuses

## Scope of Testing
The following areas were covered during testing:
- Verifying record counts
- Filtering data using WHERE
- Sorting results using ORDER BY
- Using aggregate functions such as COUNT(), SUM(), AVG(), MIN(), and MAX()
- Grouping data using GROUP BY and HAVING
- Retrieving unique values using DISTINCT
- Joining tables using INNER JOIN and LEFT JOIN
- Filtering records by date ranges
- Checking data integrity and identifying invalid values
- Identifying duplicate customer email addresses
- Checking for missing payment dates

## Tools and Technologies
- **SQL** – writing and executing queries
- **MariaDB** – relational database management system
- **phpMyAdmin** – database administration and query execution
- **XAMPP** – local development environment
- **Microsoft Excel** – test case documentation and test execution results
- **GitHub** – project documentation and portfolio

## Test Documentation
The project includes an markdown (.md) file containing test cases and execution results.
Each test case includes:
- Test Case ID
- Test Environment
- Test Title and Description
- Preconditions
- SQL Query
- Priority
- Test Steps
- Actual Results
- Expected Results
- Test Result

## Test Execution Summary
- Total test cases: 19
- Passed: 15
- Failed: 4
- Not Run: 0
- Bugs reported: 4

The failed test cases identified potential data quality and integrity issues in the test database.

## Key Findings
The testing process identified the following issues:
- Products with negative stock quantities
- A product with a negative price
- Duplicate customer email addresses
- A payment record with a missing payment date

The issues were documented as test execution findings. No database corrections were performed as part of this project.

## Project Structure
```text
02-sql-testing/
├── bug-reports/
├── screenshots/
├── README.md
└── test-cases-and-execution.xlsx
```

## Learning Outcomes
Through this project, I practised:
- Writing SQL queries to retrieve and validate data
- Using filtering, sorting, and aggregate functions
- Joining related database tables
- Grouping records and checking conditions using HAVING
- Identifying data quality and integrity issues
- Comparing actual and expected results
- Documenting test cases and execution results

## Disclaimer
This project was created for educational and portfolio purposes using a local test database. The data is used for practising SQL queries and database testing and does not represent a production system.
