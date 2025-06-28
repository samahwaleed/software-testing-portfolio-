# Summary Report: SauceDemo Manual Testing

## 1. Project Overview

Manual testing was performed on the SauceDemo e-commerce web application. The main objectives were to validate essential user workflows (login, catalog, cart, checkout, order completion), test negative and edge cases, and assess basic UI/UX. All tests were executed on [https://www.saucedemo.com/](https://www.saucedemo.com/).

---

## 2. Test Coverage & Results

| Area/Feature           | Test Case IDs       | No. of Cases | Pass | Fail | Blocked |
|------------------------|--------------------|--------------|------|------|---------|
| Login/Logout           | TC-001–TC-004      | 4            | 4    | 0    | 0       |
| Product Catalog        | TC-005–TC-007      | 3            | 2    | 1    | 0       |
| Shopping Cart          | TC-008–TC-013      | 6            | 6    | 0    | 0       |
| Checkout Process       | TC-014–TC-017      | 4            | 4    | 0    | 0       |
| Order Completion       | TC-018–TC-020      | 3            | 3    | 0    | 0       |
| Negative/Edge Cases    | TC-021–TC-023      | 3            | 3    | 0    | 0       |
| UI/UX & General        | TC-024–TC-026      | 3            | 2    | 1    | 0       |
| **Total**              | **TC-001–TC-026**  | **26**       | **24**| **2**| **0**   |

---

## 3. Key Findings

- **24 out of 26 test cases passed** without issues.
- **2 failures** were observed, corresponding to minor usability issues.
- 2 enhancement opportunities and 1 informational feature were also recorded.

---

## 4. Defect Summary

| Bug ID   | Linked Test Case(s) | Summary                                          | Severity       | Status | Comments / Notes                   |
|----------|---------------------|--------------------------------------------------|----------------|--------|------------------------------------|
| BUG-001  | TC-021              | Locked out user can't login                       | Info           | Open   | Feature; checked for clarity of message |
| BUG-002  | TC-001              | No password show/hide toggle                     | Minor          | Open   | Usability enhancement              |
| BUG-003  | TC-007              | Product images/titles not always clickable       | Minor          | Open   | Not standard e-commerce behavior   |
| BUG-004  | TC-025              | Error messages don't auto-close                  | Enhancement    | Open   | UX improvement possible            |

---

## 5. Recommendations

- **Enhance login UX:** Add a show/hide password option for usability.
- **Improve product browsing:** Ensure product images/titles are consistently clickable to view details.
- **Refine error handling:** Allow error messages to auto-dismiss or close on user interaction for a smoother experience.
- **Review locked user message:** Ensure lockout reasons are clearly explained for real-world scenarios.

---

## 6. Conclusion

All main business flows for standard users work as intended. The few minor issues and enhancement suggestions do not block core functionality but would improve user experience and bring the application in line with modern e-commerce expectations.

---

**Tested by:** Samah Abusalim  
**Date:** 10/10/2024
