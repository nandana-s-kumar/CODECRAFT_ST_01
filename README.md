# CODECRAFT_ST_01
Manual test cases for Calculator application
---
## Test case 1
**Test Case ID:** TC_ADD_001
**Description:** Verify addition of two positive integers

**Preconditions:**
-Calculator application is opened
-Display shows 0
**Test Steps:**
1. Click Number 2
2. Click +
3. Click Number 3
4. Click =

**Expected Result:**
-The Result in Display Should be 5

---
## Test Case 2
**Test Case ID:** TC_ADD_002
**Description:** Verify addition of two negative numbers

**Preconditions:**
-Calculator application is opened
-Display shows 0

**Test Steps:**
1. Click Number -2
2. Click +
3. Click Number -3
4. Click =

**Expected Result:**
-The result in display should be -5

---

## Test case 3

**Test Case ID:** TC_ADD_003  

**Description:** Verify addition of decimal numbers  

**Preconditions:**  
- Calculator application is opened  
- Display shows 0  

**Test Steps:**  
1. Click Number 2  
2. Click .  
3. Click Number 5  
4. Click +  
5. Click Number 1  
6. Click .  
7. Click Number 5  
8. Click =  

**Expected Result:**  
- The result in display should be 4.0  

---

## Test case 4

**Test Case ID:** TC_ADD_004  
**Description:** Verify addition follows BODMAS when combined with multiplication

**Preconditions:**
- Calculator application is opened
- Display shows 0


**Test Steps:**
1. Click (
2. Click Number 2
3. Click +
4. Click Number 3
5. Click )
6. Click +
7. Click Number 4
8. Click =

**Expected Result:**
- The result in display should be 9  
  (Because (2 + 3) + 4 = 9)


   
