# Test Scenarios: SauceDemo E-Commerce Website

This document lists the high-level test scenarios identified for manual testing of the SauceDemo web application.  
Each scenario can be broken down into detailed test cases in the `TestCases.xlsx` file.

---

## 1. User Authentication

- TS-1: Verify user can log in with valid credentials
- TS-2: Verify login fails with invalid credentials
- TS-3: Verify error message displays for blank username/password
- TS-4: Verify user can log out successfully

---

## 2. Product Catalog

- TS-5: Verify all products are displayed on the Products page
- TS-6: Verify product details (name, price, image) are displayed correctly
- TS-7: Verify user can view product details (if applicable)

---

## 3. Shopping Cart

- TS-8: Verify user can add a product to the cart from the product list
- TS-9: Verify user can add multiple products to the cart
- TS-10: Verify user can view cart contents
- TS-11: Verify user can remove a product from the cart
- TS-12: Verify cart displays correct product quantities and prices
- TS-13: Verify cart icon shows correct number of items

---

## 4. Checkout Process

- TS-14: Verify user can initiate checkout from the cart
- TS-15: Verify user must enter required information (first name, last name, postal code) to continue checkout
- TS-16: Verify error message for missing or invalid checkout information
- TS-17: Verify user can complete the purchase and receive confirmation

---

## 5. Order Completion

- TS-18: Verify order confirmation page displays after successful checkout
- TS-19: Verify cart is emptied after order completion
- TS-20: Verify user can navigate back to the Products page after order

---

## 6. Negative & Edge Case Testing

- TS-21: Verify login fails with locked-out user (using `locked_out_user` credentials)
- TS-22: Verify application handles browser refresh and back navigation gracefully during checkout
- TS-23: Verify application maintains cart state on browser refresh

---

## 7. UI/UX & General

- TS-24: Verify all buttons and links are functional
- TS-25: Verify error messages are clear and consistent
- TS-26: Verify application layout is responsive in Chrome and Firefox

---

*End of Test Scenarios*
