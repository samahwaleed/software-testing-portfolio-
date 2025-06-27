# Test Scenarios: OrangeHRM Demo Web Application

This document lists the high-level test scenarios for manual testing of the OrangeHRM demo web application.  
Each scenario will be mapped to detailed test cases in the `TestCases.xlsx` file.

---

## 1. User Authentication

- TS-01: Verify login with valid credentials
- TS-02: Verify login fails with invalid credentials
- TS-03: Verify appropriate error messages for blank username/password
- TS-04: Verify successful logout

---

## 2. Employee Management

- TS-05: Add a new employee successfully
- TS-06: Edit existing employee details
- TS-07: Delete an employee record
- TS-08: Upload employee profile photo
- TS-09: Search for employees by name/ID
- TS-10: View employee details

---

## 3. Leave Management

- TS-11: Apply for leave as an employee
- TS-12: Approve leave as admin/manager
- TS-13: Reject leave request as admin/manager
- TS-14: Verify leave balances are updated after approval/rejection
- TS-15: Search/filter leave records

---

## 4. Admin Features

- TS-16: Add new user role (e.g., ESS, Admin)
- TS-17: Edit user role permissions
- TS-18: Delete a user role
- TS-19: Assign role to a user
- TS-20: Add and update job titles
- TS-21: Add and update pay grades

---

## 5. Search, Filter & Sort

- TS-22: Search employee list by keyword
- TS-23: Filter leave records by date/status
- TS-24: Sort employee and leave lists by column

---

## 6. Input Validation & Error Messages

- TS-25: Validate required fields on forms (employee, leave, user)
- TS-26: Verify error messages for invalid data entries
- TS-27: Check max length/min length validation for text fields

---

## 7. UI/UX and Accessibility

- TS-28: Verify all buttons, menus, and navigation links are functional
- TS-29: Check for responsive design in Chrome and Firefox
- TS-30: Verify that form fields are labeled and accessible
- TS-31: Check for proper alignment and layout across pages

---

*End of Test Scenarios*
