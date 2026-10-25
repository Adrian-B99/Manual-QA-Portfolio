# BUG-04
## Summary:
Product images are not displayed correctly.
## Related Test Case:
TC-28
## Environment:
Win 10 Pro 19045.6466 + Chrome 152.0.7977.83 (Official Build) (64-bitowa)
## Preconditions:
The user is logged in as problem_user.
## Test Data:
- Username: problem_user
- Password: secret_sauce
## Steps to Reproduce:
1. Open https://www.saucedemo.com/ 
2. Enter the correct username and password 
3. Click the "Login" button
## Actual Result:
The same incorrect image is displayed for every product.
## Expected Result:
Each product should have the correct image displayed.
## Priority:
Medium
## Attachments:
![BUG-04](../screenshots/BUG-04.png)
