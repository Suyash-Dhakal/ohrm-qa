# Bug Report Template - OrangeHRM Testing

## Bug Report Format

### Bug ID: BUG-[MODULE]-[NUMBER]
**Example:** BUG-LOGIN-001, BUG-PIM-003, BUG-ADMIN-002

---

## **Bug Title:** [Brief, descriptive title of the issue]

### **Bug Details**

| Field | Information |
|-------|-------------|
| **Bug ID** | BUG-XXX-### |
| **Module** | [Login/PIM/Admin/Dashboard/Leave] |
| **Reported By** | [Your Name] |
| **Date Reported** | [DD/MM/YYYY] |
| **Environment** | [Browser version, OS] |
| **Severity** | [Critical/High/Medium/Low] |
| **Priority** | [P0/P1/P2/P3] |
| **Status** | [Open/In Progress/Resolved/Closed] |

---

### **Bug Description**
[Clear, concise description of what the bug is]

### **Steps to Reproduce**
1. [First step]
2. [Second step]
3. [Third step]
4. [Continue as needed...]

### **Expected Result**
[What should happen according to requirements]

### **Actual Result**
[What actually happened - the bug behavior]

### **Test Data Used**
[Specific data used during testing that caused the bug]

### **Screenshots/Evidence**
- Screenshot 1: [Description]
- Screenshot 2: [Description]
- Video: [If applicable]

### **Workaround** (If any)
[Alternative way to achieve the desired result]

### **Additional Notes**
[Any other relevant information, browser console errors, etc.]

---

## **Severity and Priority Guidelines**

### **Severity Levels:**
- **Critical:** System crash, complete feature failure, security breach
- **High:** Major functionality broken, significant user impact
- **Medium:** Feature partially working, moderate user impact  
- **Low:** Minor issues, cosmetic problems, minimal user impact

### **Priority Levels:**
- **P0:** Fix immediately (blocks testing/release)
- **P1:** Fix in current sprint/release
- **P2:** Fix in next release
- **P3:** Fix when time permits

---

## **Sample Bug Reports**

### **Bug Report Example 1:**

## **Bug Title:** Login fails with correct credentials after password reset

### **Bug Details**

| Field | Information |
|-------|-------------|
| **Bug ID** | BUG-LOGIN-001 |
| **Module** | Login |
| **Reported By** | [Your Name] |
| **Date Reported** | 25/07/2025 |
| **Environment** | Chrome 115, Windows 11 |
| **Severity** | High |
| **Priority** | P1 |
| **Status** | Open |

### **Bug Description**
User cannot login with correct credentials after using the password reset functionality.

### **Steps to Reproduce**
1. Navigate to OrangeHRM login page
2. Click on "Forgot your password?" link
3. Enter valid email address
4. Complete password reset process
5. Return to login page
6. Enter username and new password
7. Click Login button

### **Expected Result**
User should be successfully logged into the system with new password.

### **Actual Result**
Login fails with error message "Invalid credentials" despite using correct username and new password.

### **Test Data Used**
- Username: Admin
- Email: admin@orangehrm.com
- New Password: NewPass123!

### **Screenshots/Evidence**
- Screenshot 1: Password reset confirmation screen
- Screenshot 2: Login error message with new credentials

### **Additional Notes**
Issue appears to be related to password reset token not being properly cleared from the system.

---

### **Bug Report Example 2:**

## **Bug Title:** Employee search returns no results for partial name matches

### **Bug Details**

| Field | Information |
|-------|-------------|
| **Bug ID** | BUG-PIM-002 |
| **Module** | PIM |
| **Reported By** | [Your Name] |
| **Date Reported** | 25/07/2025 |
| **Environment** | Firefox 115, Windows 11 |
| **Severity** | Medium |
| **Priority** | P2 |
| **Status** | Open |

### **Bug Description**
Employee search function does not return results when searching with partial employee names.

### **Steps to Reproduce**
1. Login to OrangeHRM system
2. Navigate to PIM > Employee List
3. Enter partial employee name in search field (e.g., "John" for "John Doe")
4. Click Search button

### **Expected Result**
System should return all employees whose names contain the search term "John".

### **Actual Result**
Search returns "No Records Found" message despite having employees with names containing "John".

### **Test Data Used**
- Search term: "John"
- Existing employees: John Doe, John Smith, Johnny Williams

### **Screenshots/Evidence**
- Screenshot 1: Search interface with partial name
- Screenshot 2: "No Records Found" result

### **Workaround**
Enter complete employee name to find specific employee.

### **Additional Notes**
Full name search works correctly. Issue only occurs with partial name searches.

---

## **Bug Tracking Guidelines**

### **Before Reporting a Bug:**
1. Reproduce the issue at least twice
2. Check if it's a known limitation
3. Verify test data and environment
4. Clear browser cache and try again

### **Bug Report Quality Checklist:**
- [ ] Clear, descriptive title
- [ ] Detailed steps to reproduce
- [ ] Expected vs actual results documented
- [ ] Screenshots attached
- [ ] Environment details provided
- [ ] Severity and priority assigned correctly
- [ ] Test data specified

### **Bug Status Workflow:**
1. **Open** - Newly reported bug
2. **In Progress** - Bug being investigated/fixed
3. **Resolved** - Fix implemented, awaiting verification
4. **Closed** - Bug verified as fixed
5. **Rejected** - Not a valid bug (working as intended)

---

**Template Version:** 1.0  
**Created By:** [Your Name]  
**Date:** July 25, 2025