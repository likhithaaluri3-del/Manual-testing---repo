# Login Page - Test Cases

## 1. Objective
To verify that the login page works correctly with valid and invalid credentials.

## 2. Test Environment
- Application: Demo login application
- Testing Type: Functional Testing
- Test Level: UI Testing

## 3. Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | Enter valid username and password, then click Login | Valid credentials | User should log in successfully | Not Executed |
| TC_LOGIN_002 | Login with invalid username | Enter an invalid username and a valid password, then click Login | Invalid username | An appropriate error message should be displayed | Not Executed |
| TC_LOGIN_003 | Login with invalid password | Enter a valid username and an invalid password, then click Login | Invalid password | An appropriate error message should be displayed | Not Executed |
| TC_LOGIN_004 | Login with empty fields | Leave username and password empty, then click Login | Blank fields | Required-field validation should be displayed | Not Executed |
| TC_LOGIN_005 | Login with empty password | Enter a valid username and leave the password empty | Blank password | Password validation should be displayed | Not Executed |
| TC_LOGIN_006 | Password masking | Enter a password in the password field | Sample password | Password characters should be masked | Not Executed |

## 4. Notes
- These are sample test cases for practice.
- Actual results and execution status should be updated after testing a real application.
- Expected behavior may vary depending on the application's requirements.
