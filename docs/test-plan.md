# Test Plan - OrangeHRM Manual Testing Project

## 1. Project Overview
**Project Name:** Manual QA Testing of OrangeHRM System  
**Application Under Test:** OrangeHRM Open Source HRMS   
**Test Environment:** https://opensource-demo.orangehrmlive.com  
**Testing Type:** Manual Functional Testing  
**Tester:** Suyash Dhakal  
**Date:** July 15, 2025  

## 2. Objectives
- Validate core HR functionalities of OrangeHRM system
- Identify critical bugs and usability issues
- Ensure system meets basic user requirements
- Document test coverage for key business processes

## 3. Scope of Testing

### 3.1 In Scope Modules:
- **Login/Authentication System**
- **PIM (Personal Information Management)**
- **Admin Module (User Management)**
- **UI/UX**

### 3.2 Testing Types Covered:
- Functional Testing
- UI/UX Testing
- Negative Testing
- Boundary Value Testing
- Data Validation Testing

### 3.3 Out of Scope:
- Performance Testing
- Security Testing (beyond basic authentication)
- Mobile Application Testing
- Integration with Third-party Systems
- Database Testing

## 4. Test Environment

**System Requirements:**
- Browser: Chrome 115+, Firefox 115+, Safari 18.5
- Operating System: Windows 10/11, macOS
- Internet Connection: Stable broadband

**Test Data:**
- Valid user credentials: Admin/admin123
- Sample employee data for PIM testing
- Various input combinations for negative testing

## 5. Entry and Exit Criteria

### 5.1 Entry Criteria:
- Test environment is accessible and stable
- Test cases are prepared and reviewed
- Test data is ready
- Browser compatibility confirmed

### 5.2 Exit Criteria:
- All planned test cases are executed
- Critical and high-priority bugs are documented
- Test execution report is prepared
- 80% of test cases have passed status

## 6. Test Deliverables

- Test Scenarios Document
- Test Cases (spreadsheet format)
- Bug Reports with Screenshots
- Test Execution Summary
- Project README with findings

## 7. Risk Assessment

| Risk | Impact | Probability | Mitigation |
|------|---------|-------------|------------|
| Demo site unavailable | High | Low | Use backup demo URL |
| Browser compatibility issues | Medium | Medium | Test on multiple browsers |
| Time constraints | High | High | Focus on critical modules first |
| Data reset during testing | Medium | Medium | Document test data states |

## 8. Test Schedule

| Activity | Duration | Timeline |
|----------|----------|----------|
| Test Planning & Setup | 1 hour | 9:00-10:00 AM |
| Test Case Creation | 2 hours | 10:00-12:00 PM |
| Test Execution | 4 hours | 1:00-5:00 PM |
| Bug Reporting | 1 hour | 5:00-6:00 PM |
| Documentation | 1 hour | 6:00-7:00 PM |

## 9. Test Approach

### 9.1 Testing Methodology:
- **Black Box Testing** - Focus on functionality without code knowledge
- **Exploratory Testing** - Ad-hoc testing to discover unexpected issues
- **Requirement-based Testing** - Validate against expected HR workflows

### 9.2 Test Case Design Techniques:
- Equivalence Partitioning
- Boundary Value Analysis
- Error Guessing
- Use Case Testing

## 10. Defect Management

**Bug Severity Levels:**
- **Critical:** System crash, login failure
- **High:** Core functionality broken  
- **Medium:** Feature works with minor issues
- **Low:** Cosmetic/UI issues

**Bug Priority Levels:**
- **P0:** Fix immediately
- **P1:** Fix in current release  
- **P2:** Fix in next release
- **P3:** Fix when time permits

## 11. Success Criteria

- Zero critical bugs in core login functionality
- All major HR workflows (Add Employee, User Management) working
- Comprehensive test coverage documentation
- Professional project presentation

## 12. Tools Used

- **Test Case Management:** Google Sheets
- **Bug Tracking:** Manual documentation (Markdown)
- **Screenshot Tool:** Snipping Tool/Screenshot utilities
- **Browser:** Safari

---

**Prepared by:** Suyash Dhakal  
**Date:** July 15, 2025  
**Version:** 1.0