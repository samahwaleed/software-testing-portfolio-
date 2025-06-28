# Test Plan: Udemy.com (Manual Testing)

## 1. Introduction

This document outlines the approach, scope, and deliverables for manual testing of Udemy.com, a major global online learning platform.  
The objective is to validate that users can discover, enroll in, and engage with courses, and that all critical workflows, UI elements, and user account features function reliably across devices.

---

## 2. Objectives

- Verify main user flows: homepage, course discovery, search, filtering, course detail, enrollment, account, and learning dashboard.
- Identify and document defects, usability issues, and gaps in responsiveness or accessibility.
- Validate the experience on desktop and mobile, for both logged-in and logged-out users.

---

## 3. Scope

### **In Scope**
- Homepage, featured, and recommended course displays
- Course search, filtering, sorting, and category navigation
- Course detail pages (content, instructor, reviews, preview)
- Enrollment flows (free and paid test flows)
- Wishlist, rating, and review features
- User account management (register, login, password reset, My Learning)
- Responsive layout and accessibility basics (alt text, keyboard nav)
- Session persistence, logout, error handling

### **Out of Scope**
- Actual paid purchases (no real transactions)
- Instructor course creation or admin features
- Backend database or API validation

---

## 4. Test Items

- [https://www.udemy.com/](https://www.udemy.com/)
- All public and user-facing features covered in the TestScenarios.md

---

## 5. Test Approach

- **Black-box manual testing** guided by user stories, feature exploration, and exploratory analysis.
- Execution of positive, negative, and edge-case scenarios.
- Testing on Chrome, Firefox, and at least one mobile browser (Android/iOS).
- Accessibility and usability checks (alt attributes, keyboard navigation, color contrast).

---

## 6. Deliverables

- `TestScenarios.md` — Scenario and feature coverage
- `TestCases.xlsx` — Detailed step-by-step test cases
- `BugReports.xlsx` — Defects/bugs with steps, severity, and screenshots
- `Screenshots/` — Visual documentation for coverage and issues
- `SummaryReport.md` — Test coverage, bugs, and recommendations

---

## 7. Test Schedule

| Activity         | Start Date   | End Date     |
|------------------|-------------|-------------|
| Planning         | YYYY-MM-DD   | YYYY-MM-DD  |
| Test Design      | YYYY-MM-DD   | YYYY-MM-DD  |
| Execution        | YYYY-MM-DD   | YYYY-MM-DD  |
| Reporting        | YYYY-MM-DD   | YYYY-MM-DD  |

---

## 8. Entry & Exit Criteria

**Entry:**
- Udemy.com is accessible and stable.
- Test plan and test cases are reviewed and ready.

**Exit:**
- All planned test cases executed.
- All major/critical bugs documented and reported.
- Summary report completed.

---

## 9. Resources & Environment

- Tester: Samah Abusalim
- Browsers: Chrome (latest), Firefox (latest), Mobile browser (Android/iOS)
- Tools: Excel/Sheets, screenshot tool, accessibility checker

---

## 10. Risks & Mitigations

- **Platform changes during test:** Monitor and update cases if UI/features shift.
- **Account lockout or limitations:** Use only test accounts, avoid spamming flows.
- **Network variability:** Retest failed cases on a different connection/device.

---

*End of Test Plan*
