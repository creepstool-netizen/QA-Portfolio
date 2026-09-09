# Test Cases

## Authorization

| ID | Test Case | Expected Result | Status |
|---|---|---|---|
| TC-001 | Login with valid credentials | User successfully logged in | PASS |
| TC-002 | Login with incorrect password | Error message is displayed | PASS |
| TC-003 | Login with empty email | Validation message is displayed | PASS |
| TC-004 | Login with empty password | Validation message is displayed | PASS |
| TC-005 | Login with invalid email format | Validation message is displayed | PASS |

## Registration

| ID | Test Case | Expected Result | Status |
|---|---|---|---|
| TC-006 | Registration with valid data | Account is created | PASS |
| TC-007 | Registration with existing email | Error message is displayed | PASS |
| TC-008 | Registration with empty required fields | Validation messages are displayed | PASS |

TC-001 Login with valid credentials

Preconditions:
User is registered.

Steps:
1. Open login page.
2. Enter valid email.
3. Enter valid password.
4. Click "Login".

Expected Result:
User successfully logs in and is redirected to the main page.
