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

---

## Inputs Module

### TC-INP-001 - Enter numeric vaule
**Precondition:** User is on the Input page

**Steps:** 
1. Enter a numeric vaule (e.g., 10) into the input field

**Expected Result:**
The vaule is accepted and displayed in the input field

---

### TC-INP-002 _ Enter non-numeric charecters
***Predecition:** User is on the Inputs page

**Steps:** 
1. Enter non-numeric characters (e.g, abc) into the input fieled

**Expectted Result:**
System shoud prevent non-numeric input or show a validation message

**Obseration ( if no vailidation exists):**
Input accepts non-numeric characters without feedback

---

### TC-ICP003 _ Enter a very large number (edge case)
**Precondition:** User is on the Input page

**Steps:** 
1. Enter a very large number (e.g., 12345699) into the Inpud field

**Expected Result:**
System should handle large values properly (accept with limits or show validation

**Observation ( if no limits exist):**
No limits or validation feedback are provided


---

## Dropdown Module

### TC-DROP-001 - Select a valid option
**Precondition:** user is on the Dropdown page

**Steps:** 
1. Click on the dropdown list
2. Select ''Option 1'' 

**Expected Result:** 
Selected option is displayed as the current vaule

### TC-DROP-002 – Select an option but receive no feedback
**Precondition:** User is on the Dropdown page  

**Steps:**
1. Click on the dropdown list  
2. Select “Option 1”  
   

**Expected Result:**  
System should provide feedback or trigger a next action after selection  


**Observation (current behavior):**  
No feedback or action is triggered after selection  



**Expected Result:** Validation error is di
ssplayed and login is not allowed

### TC-DROP-002 - Don't change the default selected option
**Precondition:** User is on the dropdown page

**Steps:**
1.Observe the default selected option
2. Don't select any other option

**Expected Result:**
System should clearly handle or communicate the default state 

**Observation ( current behavior):**
Default state provides no feedback or guidance to the user



