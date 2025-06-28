# Test Scenarios: Tasks Mobile App

This document lists the high-level test scenarios identified for manual testing of the Tasks Android mobile app.  
Each scenario will be mapped to detailed test cases in the `TestCases.xlsx` file.

---

## 1. Installation & Launch

- TS-01: Install the APK on the emulator/device
- TS-02: Launch the app and verify splash screen/logo
- TS-03: Verify onboarding/tutorial is displayed on first launch

---

## 2. Task Management

- TS-04: Add a new task with required fields only
- TS-05: Add a new task with all fields (title, due date, notes, priority)
- TS-06: Edit an existing task
- TS-07: Delete a task from the list
- TS-08: Mark a task as complete/incomplete
- TS-09: Add, edit, and delete task notes/subtasks

---

## 3. Search & Filter

- TS-10: Search for tasks by title or note content
- TS-11: Filter tasks by status (completed, pending)
- TS-12: Filter/sort tasks by due date, priority, or list

---

## 4. Notifications & Reminders

- TS-13: Set a reminder for a task and receive a notification
- TS-14: Tap a notification to open the corresponding task in the app

---

## 5. Navigation & UI

- TS-15: Navigate between lists (e.g., Personal, Work)
- TS-16: Open the side menu and access all available options (Settings, About, etc.)
- TS-17: Switch between light and dark mode (if available)
- TS-18: Rotate device (portrait/landscape) and check layout responsiveness

---

## 6. Input Validation & Error Handling

- TS-19: Attempt to save a task without a required field (e.g., title)
- TS-20: Check for proper error messages for invalid input or long text
- TS-21: Attempt to add duplicate tasks (same title and date)

---

## 7. App Data Persistence

- TS-22: Close and relaunch the app—verify all tasks and settings are saved
- TS-23: Delete the app and reinstall—verify app resets to default state

---

## 8. Accessibility & Usability

- TS-24: Check app with TalkBack (screen reader)
- TS-25: Verify all buttons and icons have accessible labels
- TS-26: Confirm color contrast and tap target sizes are adequate

---

*End of Test Scenarios*
