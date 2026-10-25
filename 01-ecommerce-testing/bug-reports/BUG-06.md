# BUG-06
## Summary:
The prices on the products page and the product details page are different.
## Related Test Case:
TC-31
## Environment:
Win 10 Pro 19045.6466 + Chrome 152.0.7977.83 (Official Build) (64-bitowa)
## Preconditions:
The user is logged in as visual_user.
## Test Data:
- Username: visual_user
- Password: secret_sauce
## Steps to Reproduce:
1. Open https://www.saucedemo.com/ 
2. Enter the correct username and password 
3. Click the "Login" button
4. Click on a product name
## Actual Result:
The prices on the products page and the product details page are different.
## Expected Result:
The prices on the Products page and the Product Details page should be the same.
## Priority: 
High
## Attachments:
![BUG-06-1](../screenshots/BUG-06-1.png)

![BUG-06-2](../screenshots/BUG-06-2.png)
