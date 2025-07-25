# Test Scenarios - OrangeHRM Manual Testing

## 1. Login Module Test Scenarios

### TS_LOGIN_001: Valid Login Functionality
**Objective:** Verify users can successfully login with valid credentials  
**Priority:** P0 (Critical)  
**Test Data:** Username: Admin, Password: admin123

### TS_LOGIN_002: Invalid Login Attempts  
**Objective:** Verify system handles invalid login attempts correctly  
**Priority:** P1 (High)  
**Test Data:** Various invalid username/password combinations

### TS_LOGIN_003: Password Field Security
**Objective:** Verify password field masks input and security measures  
**Priority:** P1 (High)  
**Test Data:** Any password input

### TS_LOGIN_004: Login Form Validation
**Objective:** Verify form validation for empty/special character inputs  
**Priority:** P2 (Medium)  
**Test Data:** Empty fields, special characters, SQL injection attempts

---

## 2. PIM (Personal Information Management) Module Test Scenarios

### TS_PIM_001: Add New Employee
**Objective:** Verify new employee can be successfully added to system  
**Priority:** P0 (Critical)  
**Test Data:** Employee details (Name, ID, contact info)

### TS_PIM_002: Search Employee Functionality
**Objective:** Verify employee search works with various search criteria  
**Priority:** P1 (High)  
**Test Data:** Employee names, IDs, job titles

### TS_PIM_003: Edit Employee Information
**Objective:** Verify existing employee information can be updated  
**Priority:** P1 (High)  
**Test Data:** Modified employee details

### TS_PIM_004: Delete Employee Record
**Objective:** Verify employee records can be deleted with proper confirmation  
**Priority:** P1 (High)  
**Test Data:** Existing employee records

### TS_PIM_005: Employee Personal Details Validation
**Objective:** Verify personal details form validation (phone, email, etc.)  
**Priority:** P2 (Medium)  
**Test Data:** Invalid email formats, phone numbers

---

## 3. Admin Module Test Scenarios

### TS_ADMIN_001: User Management - Add User
**Objective:** Verify new system users can be created  
**Priority:** P0 (Critical)  
**Test Data:** User details with different roles

### TS_ADMIN_002: User Management - Search Users
**Objective:** Verify user search functionality works correctly  
**Priority:** P1 (High)  
**Test Data:** Various search criteria (username, role, status)

### TS_ADMIN_003: User Role Assignment
**Objective:** Verify different user roles can be assigned correctly  
**Priority:** P1 (High)  
**Test Data:** Admin, ESS

### TS_ADMIN_004: User Status Management
**Objective:** Verify user accounts can be enabled/disabled  
**Priority:** P1 (High)  
**Test Data:** Active/inactive user accounts

---

## 4. UI/UX Test Scenarios

### TS_UI_001: Responsive Design Testing
**Objective:** Verify application works on different screen resolutions  
**Priority:** P2 (Medium)  
**Test Data:** Various screen sizes

### TS_UI_002: Browser Compatibility
**Objective:** Verify application works across different browsers  
**Priority:** P2 (Medium)  
**Test Data:** Chrome, Firefox, Edge browsers

### TS_UI_003: Error Message Display
**Objective:** Verify appropriate error messages are displayed  
**Priority:** P2 (Medium)  
**Test Data:** Invalid inputs causing errors

---

**Total Scenarios:** 16  
**Estimated Execution Time:** 5-7 hours  
**Priority Distribution:**
- P0 (Critical): 3 scenarios
- P1 (High): 8 scenarios  
- P2 (Medium): 5 scenarios
- P3 (Low): 0 scenarios

**Prepared by:** Suyash Dhakal  
**Date:** July 15, 2025  
**Version:** 1.0