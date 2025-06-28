# Test Plan: Mudah.my – Properties for Sale (Manual Testing)

## 1. Introduction

This test plan documents the approach, scope, and deliverables for manual testing of the “Properties for Sale” section on Mudah.my, Malaysia’s online marketplace.  
The objective is to ensure users can efficiently search, browse, filter, and contact sellers or agents for properties, and that all critical functions are robust and user-friendly.

---

## 2. Objectives

- Validate all main user flows: browsing, searching, filtering, viewing details, contacting sellers, and managing favourites.
- Uncover any defects, usability issues, or data inconsistencies in the Property for Sale section.
- Confirm that features work on desktop and mobile, including responsiveness and accessibility basics.

---

## 3. Scope

### **In Scope**
- Property search, filter, and sort functionalities
- Property detail pages (images, descriptions, maps)
- Contact seller/agent flows (logged-in/out)
- User login, registration, and managing favourites
- Share and report listing features
- Responsiveness on mobile/tablet browsers
- Basic accessibility checks

### **Out of Scope**
- Other Mudah.my categories (Autos, Electronics, Jobs, etc.)
- Backend database validation
- Admin or agent dashboard flows
- Payment or posting property flows (unless publicly accessible)

---

## 4. Test Items

- [https://www.mudah.my/malaysia/properties-for-sale?](https://www.mudah.my/malaysia/properties-for-sale?)
- All front-end flows and UI elements for the Properties for Sale experience

---

## 5. Test Approach

- **Black-box** manual testing based on user stories and exploratory analysis
- Execute positive, negative, and edge-case scenarios
- Test on Chrome, Firefox, and one mobile browser (Android/iOS)
- Accessibility and UI checks (alt text, keyboard navigation, color contrast)

---

## 6. Deliverables

- `TestScenarios.md` — High-level scenario list
- `TestCases.xlsx` — Step-by-step manual test cases
- `BugReports.xlsx` — Bugs/defects found, with details and severity
- `Screenshots/` — Visual documentation for key flows and defects
- `SummaryReport.md` — Overall findings and recommendations

---

## 7. Test Schedule

| Activity         | Start Date   | End Date     |
|------------------|-------------|-------------|
| Planning         | 2024-11-11   | 2024-12-20 |
| Test Design      | 2024-11-11   | 2024-12-20  |
| Execution        | 2024-11-11   | 2024-12-20  |
| Reporting        | 2024-11-11   | 2024-12-20  |

---

## 8. Entry & Exit Criteria

**Entry:**
- Site is accessible and stable
- Test plan and cases are ready

**Exit:**
- All planned test cases executed
- Major/blocker bugs are reported
- Summary report finalized

---

## 9. Resources & Environment

- Tester: Samah Abusalim
- Browsers: Chrome (latest), Firefox (latest), Mobile browser (Android/iOS)
- Tools: Excel/Sheets, screenshot tool

---

## 10. Risks & Mitigations

- **Site changes during test cycle:** Regularly validate test cases and update if UI changes.
- **Account or posting restrictions:** Use only public/allowed flows, do not spam actual sellers.
- **Network performance:** Re-test failed cases on different connections if needed.

---

*End of Test Plan*
