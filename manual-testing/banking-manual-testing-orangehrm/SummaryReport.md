# Summary Report: OrangeHRM Demo Manual Testing

## 1. Project Overview

Manual testing was performed on the OrangeHRM demo web application ([https://opensource-demo.orangehrmlive.com/](https://opensource-demo.orangehrmlive.com/)).  
The aim was to validate core HR workflows (login, employee management, leave management, admin, and UI/UX) and document any functional or data integrity issues.

---

## 2. Test Coverage & Results

| Area/Feature           | No. of Test Cases | Pass | Fail | Blocked |
|------------------------|-------------------|------|------|---------|
| Login/Logout           |      4            |  4   |  0   |   0     |
| Employee Management    |      6            |  5   |  1   |   0     |
| Leave Management       |      6            |  3   |  1   |   2     |
| Admin Features         |      6            |  6   |  0   |   0     |
| Search/Filter/Sort     |      3            |  3   |  0   |   0     |
| Validation & Error Msg |      3            |  2   |  1   |   0     |
| UI/UX & Accessibility  |      2            |  2   |  0   |   0     |
| **Total**              |    **30**         | **25**|**3** | **2**   |

---

## 3. Key Findings

- **Most core HR functionalities are working as expected.**
- **3 bugs and 2 blocked scenarios were identified:**
    - **BUG-001:** No validation on employee first name—special characters allowed without error (data integrity issue).
    - **BUG-002:** Approve/Reject buttons not available for leave requests (cannot test leave approval).
    - **BUG-003:** Leave balance does not update after applying for leave (feature not testable).
    - 2 scenarios blocked due to demo limitations (unable to approve/reject leave and verify balance updates).
- All bugs and demo limitations have been documented in BugReports.xlsx.

---

## 4. Defect Summary

| Bug ID   | Linked Test Case(s) | Summary                                  | Severity | Status | Screenshot/File      | Comments                  |
|----------|---------------------|------------------------------------------|----------|--------|----------------------|---------------------------|
| BUG-001  | TC-025              | No validation on employee first name     | Major    | Open   | Screenshots/bug1.png | Data integrity issue      |
| BUG-002  | TC-011, TC-012      | Approve/Reject not available for leave   | Blocker  | Open   | Screenshots/bug2.png | Demo limitation           |
| BUG-003  | TC-013              | Leave balance does not update            | Major    | Open   | Screenshots/bug3.png | Feature not testable      |

---

## 5. Recommendations

- **Implement input validation:** Employee name fields should block special characters and show a clear error message.
- **Review leave workflow in demo:** Enable leave approval/rejection for more complete testability.
- **Ensure dynamic leave balances:** Leave balances should update after requests, approvals, or rejections.
- Consider enhancing demo documentation to clarify current limitations for testers.

---

## 6. Conclusion

The OrangeHRM demo site demonstrates stable core HR functionality for login, admin, and data management.  
However, some critical workflows (such as leave approval and balance updates) could not be fully tested due to demo environment limitations.  
Addressing input validation and enabling full leave workflows would further improve data quality and demo reliability.

---

**Tested by:** Samah Abusalim  
**Date:** 2024-07-07
