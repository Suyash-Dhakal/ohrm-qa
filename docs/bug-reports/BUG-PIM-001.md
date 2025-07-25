## **Bug Title:** Employee Name Validation Failure - Invalid Input Accepted Without Error

### **Bug Details**

| Field | Information |
|-------|-------------|
| **Bug ID** | BUG-PIM-001 |
| **Module** | PIM |
| **Reported By** | Suyash |
| **Date Reported** | 15/07/2025 |
| **Environment** | Safari 18.5, macOS 15.5 |
| **Severity** | Medium |
| **Priority** | P2 |
| **Status** | Open |

---

### **Bug Description**
The employee name validation is not functioning correctly. When editing an employee record, the system accepts invalid input containing numbers and special characters without displaying any validation errors or preventing the save operation.

### **Steps to Reproduce**
1. Log in to the system with PIM access privileges
2. Navigate to PIM > Employee List
3. Select an existing employee and click Edit
4. In the name field, enter invalid data: "12345 @$"
5. Click Save changes

### **Expected Result**
The system should display validation errors indicating that the name field contains invalid characters and should reject the input.

### **Actual Result**
The invalid name "12345 @$" was accepted and the employee record was updated successfully without any validation errors or warnings.

### **Test Data Used**
- Invalid name input: "12345 @$"
- Test case reference: TC_PIM_005

### **Screenshots/Evidence**
- Screenshot 1: Updated employee record displaying invalid name