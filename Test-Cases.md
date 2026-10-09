# Login Test Cases

## TC-001 – Valid Login

**Test Objective:** Verify that a user can log in with valid credentials.

**Precondition:** User has a valid account.

**Test Steps:**
1. Open the login page.
2. Enter a valid username.
3. Enter a valid password.
4. Click the Login button.

**Expected Result:**
The user should be successfully logged in and redirected to the homepage.

## TC-002 – Invalid Password

**Test Objective:** Verify that a user cannot log in with an incorrect password.

**Precondition:** User has a valid account.

**Test Steps:**

1. Open the login page.
2. Enter a valid username.
3. Enter an incorrect password.
4. Click the Login button.

**Expected Result:**
The user should not be logged in. An appropriate error message should be displayed.

## TC-003 – Invalid Email Format

**Test Objective:** Verify that the login form handles an incorrectly formatted email address.

**Precondition:** The login page is open.

**Test Steps:**

1. Enter an invalid email address, for example `user@`.
2. Enter any password.
3. Click the Login button.

**Expected Result:**
The application should reject the invalid email address and display an appropriate validation message.


