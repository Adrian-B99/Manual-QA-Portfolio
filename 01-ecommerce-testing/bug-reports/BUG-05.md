# BUG-05
## Summary:
The product description is not displayed on the product details page.
## Related Test Case:
TC-30
## Environment:
Win 10 Pro 19045.6466 + Chrome 152.0.7977.83 (Official Build) (64-bitowa)
## Preconditions:
The user is logged in as error_user.
## Test Data:
- Username: error_user
- Password: secret_sauce
## Steps to Reproduce:
1. Open https://www.saucedemo.com/ 
2. Enter the correct username and password 
3. Click the "Login" button
4. Click on a product name
## Actual Result:
After clicking on a product, the product description is missing.
## Expected Result:
After clicking on a product, the product description should be displayed.
## Priority:
Medium
## Attachments:
![BUG-05](../screenshots/BUG-05.png)
