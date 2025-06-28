# Summary Report: Tasks Mobile App Manual Testing

## 1. Project Overview

Manual testing was performed on the Tasks mobile app (open-source ToDo list), focusing on core task management, reminders, notifications, UI/UX, and accessibility.  
Testing was conducted using an Android emulator (Pixel 4a, Android 13) and the latest APK from GitHub.

---

## 2. Test Coverage & Results

| Area/Feature         | No. of Test Cases | Pass | Fail | Blocked |
|----------------------|-------------------|------|------|---------|
| Installation & Launch|        3          |  3   |  0   |   0     |
| Task Management      |        6          |  4   |  2   |   0     |
| Search/Filter/Sort   |        3          |  3   |  0   |   0     |
| Notifications        |        2          |  1   |  1   |   0     |
| Navigation & UI      |        4          |  3   |  1   |   0     |
| Validation & Errors  |        3          |  2   |  1   |   0     |
| Accessibility        |        2          |  1   |  1   |   0     |
| **Total**            |      **23**       |**17**|**6** | **0**   |

---

## 3. Key Findings

- **Major flows like task creation, deletion, and searching work as expected.**
- **6 bugs were found** (see Defect Summary), mainly in validation, reminders, UI layout, and accessibility.
- No critical/blocker bugs, but several issues affect user experience and data quality.

---

## 4. Defect Summary

| Bug ID   | Linked Test Case(s) | Summary                                 | Severity | Status | Screenshot/File      | Comments                 |
|----------|---------------------|-----------------------------------------|----------|--------|----------------------|--------------------------|
| BUG-001  | TC-004, TC-019      | Task with empty title can be saved      | Major    | Open   | Screenshots/bug1.png | Data quality issue       |
| BUG-002  | TC-013, TC-014      | Notification not reliably received      | Major    | Open   | Screenshots/bug2.png | Possible emulator issue  |
| BUG-003  | TC-005, TC-006      | Long task title breaks UI layout        | Minor    | Open   | Screenshots/bug3.png | Readability affected     |
| BUG-004  | TC-021              | Duplicate tasks allowed                 | Minor    | Open   | Screenshots/bug4.png | No duplicate check       |
| BUG-005  | TC-025              | Buttons/icons lack accessibility labels | Minor    | Open   | Screenshots/bug5.png | Accessibility issue      |
| BUG-006  | TC-017              | Dark mode text contrast is poor         | Minor    | Open   | Screenshots/bug6.png | UI/UX issue              |

---

## 5. Recommendations

- **Add required field validation** for task title.
- **Improve notification reliability** (test on real device, background execution).
- **Enforce unique task titles or warn on duplicates.**
- **Enhance UI layout handling** for long text.
- **Ensure all icons/buttons have accessibility labels.**
- **Adjust color schemes for better contrast in dark mode.**

---

## 6. Conclusion

The Tasks mobile app demonstrates stable core functionality, but several validation, UI, and accessibility issues impact data quality and user experience.  
Addressing these bugs will make the app more robust, accessible, and user-friendly.

---

**Tested by:** Samah Abusalim  
**Date:** 2024-09-05]
