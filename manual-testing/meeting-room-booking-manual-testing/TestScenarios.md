# Test Scenarios: Skedda Meeting Room Booking System

This document outlines all high-level and detailed test scenarios for manual testing of Skedda's meeting room booking system.  
Each scenario is mapped to one or more test cases in the TestCases.xlsx file.

---

## 1. Authentication & User Management

- **TS-001:** Register a new user with valid details
- **TS-002:** Register a user with already registered email
- **TS-003:** Register with invalid or missing fields (e.g., invalid email, blank password)
- **TS-004:** Activate account via email (if required)
- **TS-005:** Login with valid credentials
- **TS-006:** Login with invalid password or email
- **TS-007:** Attempt login with blank credentials
- **TS-008:** Reset password via “Forgot Password” flow
- **TS-009:** Change password from user profile
- **TS-010:** Update profile information (name, phone, etc.)
- **TS-011:** Log out from the application

---

## 2. Room & Resource Discovery

- **TS-012:** Browse available rooms/resources by calendar view
- **TS-013:** Search for rooms by name, type, or capacity
- **TS-014:** Filter rooms/resources by attributes (location, size, equipment, etc.)
- **TS-015:** View detailed room information (photos, description, equipment)

---

## 3. Booking Management (Happy Path)

- **TS-016:** Create a new booking for an available slot
- **TS-017:** Create a recurring booking (daily/weekly/monthly, if available)
- **TS-018:** Edit/modify a booking (date, time, room, attendees)
- **TS-019:** Cancel a booking (before it starts)
- **TS-020:** View all upcoming and past bookings
- **TS-021:** Book a room/resource for maximum allowed duration
- **TS-022:** Book a room/resource for minimum allowed duration

---

## 4. Booking Management (Negative, Edge, and Exploratory)

- **TS-023:** Attempt to double-book an already reserved slot (time conflict)
- **TS-024:** Attempt to book a room/resource in the past
- **TS-025:** Book a room/resource for more than maximum allowed duration
- **TS-026:** Book a room/resource for less than minimum allowed duration
- **TS-027:** Book a room/resource with missing mandatory fields (e.g., blank purpose/description)
- **TS-028:** Attempt to book a disabled/unavailable room/resource
- **TS-029:** Attempt to edit/cancel a booking after its start time
- **TS-030:** Attempt to create overlapping recurring bookings
- **TS-031:** Attempt to book with invalid attendee emails
- **TS-032:** Attempt to book on a holiday or outside business hours (if configured)

---

## 5. Approval & Notification Workflows

- **TS-033:** Book a room/resource that requires admin approval
- **TS-034:** Admin approves a pending booking request
- **TS-035:** Admin rejects a pending booking request
- **TS-036:** User receives notification (in-app/email) for new, approved, or rejected bookings
- **TS-037:** Admin receives notification for new booking requests
- **TS-038:** User receives cancellation notification
- **TS-039:** Notification/confirmation sent to all attendees

---

## 6. Search, Filter, and Calendar View

- **TS-040:** Search bookings by room, user, or date range
- **TS-041:** Filter bookings by status (upcoming, past, canceled, pending approval)
- **TS-042:** Switch between calendar (day, week, month) and list views
- **TS-043:** Print or export bookings (PDF, CSV) if supported
- **TS-044:** Check public vs. private visibility of bookings (if feature is present)

---

## 7. User Roles, Permissions & Admin Features

- **TS-045:** Regular user books a room/resource
- **TS-046:** Regular user attempts admin-only actions (should be denied)
- **TS-047:** Admin manages rooms/resources (add/edit/delete)
- **TS-048:** Admin views/manages all users and bookings
- **TS-049:** Admin sets or changes booking policies (duration, approval, business hours, etc.)
- **TS-050:** Admin impersonates user (if allowed)
- **TS-051:** Check correct access for restricted user roles (e.g., read-only, approver, admin)

---

## 8. UI/UX, Mobile Responsiveness & Accessibility

- **TS-052:** Verify UI on Chrome, Firefox, and one mobile browser
- **TS-053:** Validate mobile responsiveness (resize window, rotate device)
- **TS-054:** Check calendar and booking UI for usability (intuitive, clear labels)
- **TS-055:** Accessibility: Tab navigation, keyboard shortcuts, screen reader compatibility
- **TS-056:** Color contrast and font size (WCAG guidelines)
- **TS-057:** Language and localization (if multi-language support is present)
- **TS-058:** Error message clarity and helpfulness

---

## 9. Notifications, Emails & Integrations

- **TS-059:** In-app notification for bookings and cancellations
- **TS-060:** Email notifications for booking actions (book, cancel, edit, approval/rejection)
- **TS-061:** Calendar integration (Google/Outlook, if available)
- **TS-062:** Reminder/alert for upcoming bookings

---

## 10. Security & Session Management

- **TS-063:** Session timeout and auto-logout after inactivity
- **TS-064:** Login from two devices/browsers simultaneously (session handling)
- **TS-065:** Direct URL access to unauthorized pages (access control)
- **TS-066:** Password reset and account lockout after failed attempts

---

## 11. Data Integrity, Edge Cases, and Exploratory Testing

- **TS-067:** Bookings persist after page refresh or re-login
- **TS-068:** Bookings do not get duplicated on slow/fast repeated clicks
- **TS-069:** Mass cancelation of bookings (admin)
- **TS-070:** Try browser “Back” and “Refresh” during booking flow
- **TS-071:** Attempt XSS/HTML injection in booking description (field validation)

---

*End of Test Scenarios*
