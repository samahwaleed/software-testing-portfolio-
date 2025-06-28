# Summary Report: Skedda Meeting Room Booking System Manual Testing

## 1. Project Overview

Extensive manual testing was conducted on the Skedda Meeting Room Booking System to validate user registration, authentication, room discovery, booking creation, approval workflows, notifications, permissions, calendar views, UI/UX, accessibility, and security.  
Testing was performed on Chrome, Firefox, and mobile browsers, with all major business flows and negative/edge cases covered.

---

## 2. Test Coverage & Results

| Area/Feature             | Test Cases | Pass | Fail | Blocked |
|--------------------------|------------|------|------|---------|
| Authentication & Users   |     7      |  6   |  1   |    0    |
| Room Discovery           |     3      |  3   |  0   |    0    |
| Booking Management       |     7      |  5   |  2   |    0    |
| Approval & Notification  |     4      |  3   |  1   |    0    |
| Search/Filter/Calendar   |     3      |  3   |  0   |    0    |
| Roles & Permissions      |     4      |  4   |  0   |    0    |
| UI/UX & Accessibility    |     4      |  3   |  1   |    0    |
| Security & Sessions      |     3      |  2   |  1   |    0    |
| Data Integrity/Edge      |     3      |  2   |  1   |    0    |
| **Total**                |   **38**   |**31**| **7**| **0**   |

---

## 3. Key Findings

- **Most core workflows function as intended.**
- **7 major/minor/critical bugs were logged** (see Defect Summary).
- **Security vulnerabilities** found in session handling and XSS validation.
- UI/UX and accessibility issues on mobile and for screen readers.
- Some validation/notification issues may result in data inconsistencies or missed updates.

---

## 4. Defect Summary

| Bug ID   | Linked Test Case(s) | Summary                                | Severity   | Status | Screenshot/File      | Comments             |
|----------|---------------------|----------------------------------------|------------|--------|----------------------|----------------------|
| BUG-001  | TC-013              | Double-booking allowed                 | Major      | Open   | Screenshots/bug1.png | Data integrity       |
| BUG-002  | TC-002              | Duplicate email registration           | Major      | Open   | Screenshots/bug2.png | Should be prevented  |
| BUG-003  | TC-016              | No error on missing booking fields     | Major      | Open   | Screenshots/bug3.png | Validation missing   |
| BUG-004  | TC-030              | Mobile calendar misaligned             | Minor      | Open   | Screenshots/bug4.png | UI/UX on mobile      |
| BUG-005  | TC-018, TC-019      | Approval notifications not sent        | Major      | Open   | Screenshots/bug5.png | Notification flaw    |
| BUG-006  | TC-038              | Booking description allows XSS         | Critical   | Open   | Screenshots/bug6.png | Security vulnerability |
| BUG-007  | TC-031              | Screen reader can’t access all UI      | Minor      | Open   | Screenshots/bug7.png | Accessibility issue  |
| BUG-008  | TC-033              | Session does not timeout               | Major      | Open   | Screenshots/bug8.png | Security/session flaw|
| BUG-009  | TC-037              | Duplicate bookings via rapid click     | Major      | Open   | Screenshots/bug9.png | No debounce on submit|
| BUG-010  | TC-035              | Account not locked after failed logins | Major      | Open   | Screenshots/bug10.png| Lockout missing      |

---

## 5. Recommendations

- **Fix double-booking and duplicate registration** with stricter backend validation.
- **Add robust field validation** for all booking and user forms.
- **Resolve session timeout and account lockout security issues.**
- **Sanitize all user input** to prevent XSS and injection attacks.
- **Enhance mobile calendar UI** and accessibility labels for better usability.
- **Improve notification reliability** for all booking status changes.

---

## 6. Conclusion

The Skedda platform is stable for primary meeting room booking flows, but several high-severity issues were found.  
Addressing these bugs will improve system reliability, security, and user experience—making the platform ready for production and enterprise use.

---

**Tested by:** Samah Abusalim  
**Date:** 2024-12-12

