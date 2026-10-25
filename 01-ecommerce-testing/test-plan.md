# Test plan for online store www.saucedemo.com
## Table of contents
1. Introduction
2. Scope of testing
3. Test object
4. Pass criteria
5. Fail criteria
6. Entry criteria
7. Exit criteria
8. List of functionalities to be tested
9. Test environment
10. Defect categories and priorities
11. Test location
12. Test schedule
13. Test reports
14. List of tools
15. Incident management

## 1. Introduction
The purpose of this test plan is to describe in detail how the functionality of the online store available at https://www.saucedemo.com/ will be tested. The plan defines the scope, criteria, environment and organization of the testing, as well as the test cases that will be executed.

## 2. Scope of testing
### Test type
-	**Functional tests** – the store will be verified manually, step by step, by comparing the current result of each test case with the expected result. The tests cover:
-	login and logout, including negative scenarios;
-	product catalogue: product list, sorting, product names, prices and details;
-	shopping cart: adding and removing products, Continue Shopping button;
-	checkout: validation of customer information, Checkout: Overview page, completing the purchase;
-	correct display of product data (images, descriptions, prices) and user interface elements for the different types of test users.

## 3. Test object
The object of testing is the online store available at https://www.saucedemo.com/ with the functionalities listed in section 8: logging in and out, product list and product details, sorting products, adding and removing products from the cart, entering checkout information, the Checkout: Overview page and completing the purchase.

## 4. Pass criteria
-	A test case is passed (Test result: Passed) when the current result is consistent with the expected result.
-	The store is accepted when all test cases have the result Passed.

## 5. Fail criteria
-	A test case is failed (Test result: Failed) when the current result differs from the expected result.
-	The store is not accepted if at least one test case has the result Failed.

## 6. Entry criteria
-	The website https://www.saucedemo.com/ is available.
-	The test environment is prepared as described in section 9.
-	The test accounts listed in section 9 are available, including an active account and a locked-out account.
-	The test cases are prepared and the preconditions of each test case can be met.

## 7. Exit criteria
-	All test cases have been executed.
-	The current result and the test result (Passed / Failed) have been recorded for every test case.
-	All detected defects have been reported.

## 8. List of functionalities to be tested
- **Login:** Valid login and negative scenarios (invalid username/password, empty fields, locked-out user)
- **Logout:** Logging out via the hamburger menu
- **Product catalogue:** Product list, sorting (price, name), product names and prices, product details
- **Shopping cart:** Adding and removing products, Continue Shopping button
- **Checkout – customer information and purchase:** Item total, payment and shipping information, tax
- **Product data and UI consistency (problem_user, error_user, visual_user):** Product images and descriptions, price consistency, placement of UI elements and icons

## 9. Test environment
- **Application under test:**	https://www.saucedemo.com/
- **Operating system:**	Windows 10 Pro, version 19045.6466
- **Web browser:**	Google Chrome 152.0.7977.83 (Official Build, 64-bit)

### Test accounts (password for all users: secret_sauce)
- **Username:** standard_user	**Purpose:** Basic scenarios: login, logout, product catalogue, checkout
- **Username:** locked_out_user **Purpose:** Login of a locked-out user
- **Username:** problem_user **Purpose:** Cart operations, product images and product details
- **Username:** error_user **Purpose:** Product description in product details
- **Username:** visual_user **Purpose:** Price consistency, placement of UI elements, Checkout: Overview page

**Test data for checkout:** 
- **First Name:** Adam 
- **Last Name:** Smith 
- **Zip/Postal Code:** 74200
- **Invalid login data for negative scenarios:**
  - **username** “a”
  - **password** “a”

## 10. Defect categories and priorities
Each test case is assigned one of three priorities. The priority determines the order of test execution and the importance of a failed test case.
- **Priority:**
  - High
  - Medium
  - Low

## 11. Test location
Tests will be performed by the tester on the workstation described in section 9.

## 12. Test schedule
Test cases will be executed in the following order:
1.	Login and logout
2.	Product catalogue
3.	Checkout – customer information and purchase
4.	Shopping cart
5.	Product data and UI consistency
6.	Checkout: Overview

## 13. Test reports
-	The Test_cases file with the current result and the test result recorded for each test case.
-	Summary of test execution (number of test cases passed and failed).
-	Reports on detected defects.

## 14. List of tools
-	**Microsoft Excel** – test case documentation and recording of results.
-	**Google Chrome** – test execution.
- **PicPick** – screenshot capture and image annotation.

## 15. Incident management
A test case with the result Failed indicates a defect. The tester describes the defect (the current result compared with the expected result, the test user and the steps to reproduce) and reports it to the development team. After the defect is fixed, the test case is executed again to confirm the fix.














