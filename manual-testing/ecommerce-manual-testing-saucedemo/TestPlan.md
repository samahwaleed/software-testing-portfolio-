# Test Plan: SauceDemo E-Commerce Website

## 1. Introduction

This test plan describes the approach and scope for manual testing of the [SauceDemo](https://www.saucedemo.com/) e-commerce web application.  
The objective is to verify the main business flows—login, product selection, cart management, and checkout and ensure the application is robust against common bugs.

---

## 2. Objectives & Tasks

- Validate core functionalities (login, logout, shopping cart, checkout)
- Ensure correct display of product data and prices
- Verify user input validation and error messages
- Identify and document any defects or UI issues

---

## 3. Scope

**In-Scope:**
- User authentication (login/logout)
- Browsing products
- Adding/removing products to/from cart
- Cart review and item quantity management
- Checkout process (address, payment)
- Order completion and confirmation

**Out of Scope:**
- Admin or backend functionalities
- Third-party integrations

---

## 4. Test Items

- SauceDemo Website: [https://www.saucedemo.com/](https://www.saucedemo.com/)

---

## 5. Features to be Tested

- Login/Logout
- Product catalog and product details page
- Add to cart, remove from cart
- Shopping cart review
- Checkout workflow (address, payment, finish)
- Error message validation (invalid login, incomplete form)
- UI elements (buttons, links, navigation)

---

## 6. Features NOT to be Tested

- Database backend
- Email confirmations
- Payment gateway integration (as this is a demo app)

---

## 7. Test Approach

- **Manual black-box testing**: Focus on user workflows, input validation, and end-to-end scenarios.
- **Positive and negative testing**: Ensure the app works as expected and handles invalid actions gracefully.
- **Cross-browser testing**: Run tests in Chrome and Firefox.

---

## 8. Deliverables

- Test Plan (this document)
- Test Scenarios (`TestScenarios.md`)
- Detailed Test Cases (`TestCases.xlsx`)
- Bug Reports (`BugReports.xlsx`)
- Screenshots of defects
- Summary Report (`SummaryReport.md`)

---

## 9. Testing Schedule

| Activity           | Start Date  | End Date    |
|--------------------|-------------|-------------|
| Test Planning      | 2024-07-01  | 2024-07-02  |
| Test Case Design   | 2024-07-02  | 2024-07-03  |
| Test Execution     | 2024-07-03  | 2024-07-04  |
| Reporting          | 2024-07-04  | 2024-07-05  |

---

## 10. Entry & Exit Criteria

**Entry:**
- Application is accessible and stable
- Test data is ready

**Exit:**
- All planned test cases executed
- All critical bugs reported

---

## 11. Resources

- Test Engineer: Samah Abusalim
- Tools: Web browser, Excel, Markdown, Screenshot tool

---

## 12. Risks & Assumptions

- The demo site remains available and functional during testing.
- No access to backend or live data.

---

## 13. Approvals

| Name        | Role              | Signature    |
|-------------|-------------------|--------------|
| Samah Abusalim | Test Engineer  | samah     |

---

*End of Test Plan*
