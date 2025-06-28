# Summary Report: Udemy.com Manual Testing

## 1. Overview

Manual testing was conducted on Udemy.com to validate core user workflows, including homepage navigation, course search, filtering, course details, enrollment, account management, wishlist, and video playback.  
Testing was performed on both desktop (Chrome, Firefox) and mobile browsers to simulate real-world scenarios.

---

## 2. Test Coverage & Execution

| Feature Area            | Test Cases | Pass | Fail | Blocked |
|-------------------------|------------|------|------|---------|
| Homepage & Navigation   |     5      |  5   |  0   |    0    |
| Search, Filter, Sort    |     6      |  4   |  2   |    0    |
| Course Details          |     5      |  4   |  1   |    0    |
| Enrollment & Learning   |     5      |  5   |  0   |    0    |
| Wishlist, Rating, Review|     4      |  3   |  1   |    0    |
| User Account            |     5      |  4   |  1   |    0    |
| Mobile & Accessibility  |     3      |  2   |  1   |    0    |
| Support & Error Handling|     3      |  3   |  0   |    0    |
| Edge/Negative Scenarios |     2      |  2   |  0   |    0    |
| **Total**               |   **38**   |**32**| **6**| **0**   |

---

## 3. Key Findings

- **Most primary flows work as intended:** Navigation, search, course enrollment, dashboard, and profile management are reliable on desktop and mobile.
- **6 notable bugs were logged:**  
  - Filtering and wishlist logic not robust for logged-out users.
  - Password reset email issues.
  - Curriculum tab expansion and syllabus visibility for non-logged-in users.
  - Minor UI/UX and accessibility gaps.
- **Performance is generally fast and stable** on major browsers/devices.

---

## 4. Defect Summary

| Bug ID  | Area              | Summary                                 | Severity | Status | 
|---------|-------------------|-----------------------------------------|----------|--------|
| BUG-001 | Search/Filter     | Price filter (Free) not applied         | Major    | Open   |
| BUG-002 | Course Detail     | Curriculum tab doesn’t expand           | Major    | Open   |
| BUG-003 | Wishlist/Session  | No login prompt for wishlist (logged-out)| Major    | Open   | 
| BUG-004 | User Account      | Password reset email not sent           | Major    | Open   |
| BUG-005 | Mobile/UX         | Mobile menu overlaps search box         | Minor    | Open   |
| BUG-006 | Accessibility     | Images missing alt text                 | Minor    | Open   |

---

## 5. Recommendations

- **Fix search/filter and wishlist session logic** for logged-out users.
- **Ensure password reset emails** are always delivered and actionable.
- **Enhance curriculum/preview logic** so syllabus and content visibility match user state.
- **Improve accessibility** by reviewing alt text and UI contrast, especially for icons and mobile menus.
- Retest after fixes and broaden device/browser matrix for further assurance.

---

## 6. Conclusion

Udemy.com is robust and intuitive for most learning workflows, but several core bugs must be addressed for an optimal and secure experience.  
Addressing these issues will increase platform reliability, accessibility, and user trust.

---

**Tested by:** Samah Abusalim  
**Date:** 2024-12-12
