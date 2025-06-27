# Test Plan: OrangeHRM Demo Web Application

## 1. Introduction

This document outlines the test plan for manual testing of the [OrangeHRM Live Demo](https://opensource-demo.orangehrmlive.com/) web application.  
The goal is to validate core features such as login, employee management, leave management, admin functionalities, and UI/UX through structured manual testing.

---

## 2. Objectives & Tasks

- Verify main business workflows: login, employee management, leave management, and administration.
- Validate user role permissions and access controls.
- Ensure correct input validation and informative error messages.
- Document and report any defects or usability issues found.

---

## 3. Scope

**In-Scope:**
- User authentication (login/logout)
- Employee management (add, edit, delete employees)
- Leave management (apply, approve, reject leave)
- Admin panel features (navigation, user roles, job titles, pay grades)
- Search, filter, and sort functionalities
- UI/UX and accessibility (navigation, layout, field validation)

**Out of Scope:**
- Integration with external payroll or HRMS systems
- Email/SMS notifications
- Database backend or data migration

---

## 4. Test Items

- OrangeHRM Demo Website: [https://opensource-demo.orangehrmlive.com/](https://opensource-demo.orangehrmlive.com/)

---

## 5. Features to be Tested

- Login/Logout process
- Employee information management
- Leave application and approval
- Admin user management and permissions
- User role access and restrictions
- Search/filter in employee and leave lists
- Error message and input validation
- Responsive UI elements (buttons, forms, tables)
- Navigation and accessibility

---

## 6. Features NOT to be Tested

- Payroll processing
- Third-party integrations (e.g., email, SMS)
- Advanced reporting/analytics modules

---

## 7. Test Approach

- **Manual black-box testing:** Focused on end-user workflows, UI validation, and business logic.
- **Positive and negative testing:** Ensure workflows function as intended and invalid actions are handled gracefully.
- **Role-based testing:** Validate actions for admin and other user roles.
- **Cross-browser testing:** Validate on Chrome and Firefox.

---

## 8. Deliverables

- Test Plan (this document)
- Test Scenarios (`TestScenarios.md`)
- Test Cases (`TestCases.xlsx`)
- Bug Reports (`BugReports.xlsx`)
- Screenshots of issues found
- Summary Report (`SummaryReport.md`)

---

## 9. Testing Schedule

| Activity           | Start Date  | End Date    |
|--------------------|-------------|-------------|
| Test Planning      | 2024-07-02  | 2024-07-03  |
| Test Case Design   | 2024-07-03  | 2024-07-04  |
| Test Execution     | 2024-07-04  | 2024-07-05  |
| Reporting          | 2024-07-05  | 2024-07-06  |

---

## 10. Entry & Exit Criteria

**Entry Criteria:**
- Application is accessible and stable.
- Required test data is available.

**Exit Criteria:**
- All planned test cases have been executed.
- All high and critical severity bugs have been reported.

---

## 11. Resources

- Tester: Samah Abusalim
- Tools: Chrome, Firefox, Excel/Google Sheets, Screenshot tool

---

## 12. Risks & Assumptions

- Demo site may reset data periodically.
- Application remains available during testing.

---

## 13. Approvals

| Name        | Role              | Signature    |
|-------------|-------------------|--------------|
| Samah Abusalim | Test Engineer     | samah     |

---

*End of Test Plan*
