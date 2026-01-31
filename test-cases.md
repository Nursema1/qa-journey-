# Test Cases

## Login Module

### TC-LOGIN-001 – Successful login with valid credentials
**Precondition:** User is on the login page  
**Steps:**
1. Enter valid username
2. Enter valid password
3. Click Login button  
**Expected Result:** User is successfully logged in and secure area is displayed

---

### TC-LOGIN-002 – Login attempt with invalid password
**Precondition:** User is on the login page  
**Steps:**
1. Enter valid username
2. Enter invalid password
3. Click Login button  
**Expected Result:** Error message is displayed and user remains on login page

---

### TC-LOGIN-003 – Login with empty username and password fields
**Precondition:** User is on the login page  
**Steps:**
1. Leave username field empty
2. Leave password field empty
3. Click Login button  
**Expected Result:** Validation error is displayed and login is not allowed

