# REST API Testing Project – Restful Booker

## Project Overview

This project focuses on manual REST API testing using Postman. The goal was to verify API functionality, validate response status codes and response bodies, test authentication, and identify potential issues with API behavior.

This is an independent portfolio project created for learning purposes to demonstrate my practical API testing skills as an aspiring Junior QA Tester.

## Application Under Test
- **API:** Restful Booker Demo API
- **Base URL:** https://restful-booker.herokuapp.com
- **Testing Tool:** Postman 12.33.1
- **Operating System:** Windows 10 Pro
- **Testing Type:** Manual API Testing
- **Project Status:** Test execution completed

## Scope of Testing
The following areas were covered during testing:
- Authentication and token generation
- Handling valid, invalid, and empty credentials
- Retrieving booking IDs
- Retrieving booking details by ID
- Filtering bookings by first name and last name
- Searching with non-existing names
- Testing invalid date formats
- Creating new bookings
- Handling requests with empty payloads
- Updating existing bookings
- Partially updating booking details
- Verifying authorization requirements
- Deleting bookings
- Handling requests without a valid authorization token

## Testing Types
- Functional Testing
- Positive Testing
- Negative Testing
- Authentication and Authorization Testing
- Response Validation
- CRUD Operations Testing

## Tools and Technologies
- **Postman** – sending HTTP requests and inspecting API responses
- **REST API** – testing API endpoints and HTTP methods
- **JSON** – working with request and response bodies
- **Microsoft Excel** – test case documentation and test execution results
- **GitHub** – project documentation and portfolio

## Test Documentation
The project includes an markdown (.md) file containing test cases and execution results.
Each test case includes:
- Test Case ID
- Test Environment
- Test Title and Description
- Preconditions
- Test Data
- Priority
- Test Steps
- Actual Results
- Expected Results
- Test Result

## API Methods Covered
- **GET** - Retrieve booking IDs and booking details
- **POST** - Generate authentication tokens and create bookings
- **PUT** - Update existing bookings
- **PATCH** - Partially update booking details
- **DELETE** - Delete bookings

## Test Execution Summary
- Total test cases: 16
- Passed: 15
- Failed: 1
- Not Run: 0
- Bugs reported: 1

The test results reflect the execution recorded in the markdown (.md) test documentation.

## Key Findings
One test case failed during execution:
- **TC-07 – Get bookings by first and last name:** The API returned HTTP 200, but the expected booking IDs for the combined first-name and last-name filter were not displayed.

This result indicates a discrepancy between the expected and actual behavior. Further investigation would be needed to determine whether the cause is related to the test data, request parameters, or API behavior.

The remaining test cases passed according to their documented expected results.

## Project Structure
```text
03-api-testing/
├── bug-reports/
├── screenshots/
├── README.md
└── test_cases-and-execution.xlsx
```

## Learning Outcomes

Through this project, I practised:
- Sending HTTP requests using Postman
- Working with GET, POST, PUT, PATCH, and DELETE methods
- Testing authentication and authorization
- Validating HTTP status codes and response bodies
- Working with JSON request and response data
- Testing positive and negative scenarios
- Filtering API resources using query parameters
- Documenting test cases and execution results
- Comparing actual and expected API behavior

## Disclaimer
This project was created for educational and portfolio purposes using a publicly available demo API. The tests were performed independently and were not part of a commercial testing project.
