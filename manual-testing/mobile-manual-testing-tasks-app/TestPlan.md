# Test Plan: Tasks Mobile App

## 1. Introduction

This test plan describes the approach and scope for manual testing of the Tasks mobile app (Google ToDo clone), focusing on validating core task management, navigation, notifications, and UI/UX.

## 2. Objectives & Tasks

- Validate app installation, onboarding, and launch
- Test all main features: add/edit/delete tasks, mark complete, notifications
- Validate input fields and error handling
- Identify and document any bugs or usability issues

## 3. Scope

**In-Scope:**
- Installation and launch
- Task creation, editing, completion, deletion
- Task search and filtering
- Reminder/notification functionality
- UI/UX checks (navigation, dark mode, screen rotation)

**Out of Scope:**
- Syncing with external accounts/services
- Paid/premium features (if any)
- Accessibility testing (unless included in your emulator setup)

## 4. Test Items

- Tasks Android App (latest APK)

## 5. Features to be Tested

- Installation & first launch
- Onboarding/tutorial screens
- Task management (add/edit/delete/complete)
- Notifications & reminders
- Search/filter
- UI elements and navigation
- Error handling and input validation

## 6. Features NOT to be Tested

- Third-party integrations (Google, Dropbox, etc.)
- Analytics or advanced settings not present in the app

## 7. Test Approach

- Manual black-box testing on Android Emulator (Pixel 4a, Android 13)
- Positive/negative test cases for all user workflows
- UI testing with screen rotation and dark/light mode

## 8. Deliverables

- Test Plan (this document)
- Test Scenarios (`TestScenarios.md`)
- Detailed Test Cases (`TestCases.xlsx`)
- Bug Reports (`BugReports.xlsx`)
- Screenshots
- Summary Report

## 9. Testing Schedule

| Activity         | Start Date  | End Date    |
|------------------|-------------|-------------|
| Test Planning    | 2024-07-10  | 2024-07-11  |
| Test Case Design | 2024-07-11  | 2024-07-12  |
| Test Execution   | 2024-07-12  | 2024-07-13  |
| Reporting        | 2024-07-13  | 2024-07-14  |

## 10. Entry & Exit Criteria

**Entry:** App APK is available and emulator/device is set up  
**Exit:** All test cases executed and all major bugs reported

## 11. Resources

- Tester: Samah Abusalim
- Device: Android Emulator (Pixel 4a)
- Tools: Emulator, screenshot tool, Excel

## 12. Risks & Assumptions

- App runs without crashes on emulator
- All features accessible in test APK

## 13. Approvals

| Name        | Role        | Signature    |
|-------------|-------------|--------------|
| Samah Abusalim | Test Engineer | samah    |

*End of Test Plan*
