# Test Scenarios: Udemy.com (Manual Testing)

This document outlines high-level test scenarios for comprehensive manual testing of Udemy.com.

---

## 1. Homepage & Navigation

- **TS-001:** Udemy homepage loads with banners, featured, and popular courses.
- **TS-002:** Navigation to main categories (Development, Business, IT, etc.) from the menu.
- **TS-003:** Navigation to subcategories (e.g., Python under Development).
- **TS-004:** Click Udemy logo from any page returns to homepage.
- **TS-005:** Page not found (404) scenario for invalid course URLs.

---

## 2. Search, Filter & Sort

- **TS-006:** Search for courses by keyword (e.g., “Python”, “Excel”).
- **TS-007:** Filter search results by price (Free/Paid).
- **TS-008:** Filter by rating, level, language, or features (subtitles, quizzes, etc.).
- **TS-009:** Sort results by Most Popular, Newest, Highest Rated.
- **TS-010:** Combined filters (e.g., Free + Beginner + English).

---

## 3. Course Listing & Detail

- **TS-011:** Course cards display basic info: title, instructor, price, rating.
- **TS-012:** Open course detail page; all sections load (overview, syllabus, instructor, reviews).
- **TS-013:** Course preview video is playable.
- **TS-014:** Curriculum tab displays all lectures/modules.
- **TS-015:** Reviews and ratings load and are paginated/scrollable.

---

## 4. Enrollment & Learning

- **TS-016:** Enroll in a free course as a new user.
- **TS-017:** Add paid course to cart and begin checkout flow (test up to payment page only).
- **TS-018:** Confirmation after enrolling; course appears in My Learning.
- **TS-019:** Open My Learning dashboard; see all enrolled courses.
- **TS-020:** Open a purchased course; play videos, mark lectures complete, download resources.

---

## 5. Wishlist, Rating & Review

- **TS-021:** Add/remove courses to/from wishlist (logged in/out).
- **TS-022:** Rate and review a course after enrollment.
- **TS-023:** View and manage wishlist.
- **TS-024:** Attempt wishlist actions as logged out user (should prompt login).

---

## 6. User Account

- **TS-025:** Register a new user account with valid email and password.
- **TS-026:** Login and logout with valid credentials.
- **TS-027:** Forgot password flow; reset password successfully.
- **TS-028:** Edit profile info (name, photo, bio).
- **TS-029:** Check session persistence after refresh and logout.

---

## 7. Accessibility & Responsiveness

- **TS-030:** Responsive design: homepage, search, and detail pages render on mobile and tablet.
- **TS-031:** All images and icons have alt text or labels.
- **TS-032:** Site is navigable via keyboard (TAB, ENTER, arrow keys).
- **TS-033:** Color contrast and font size meet accessibility guidelines.

---

## 8. Support & Error Handling

- **TS-034:** Access Help Center; search for and view FAQs.
- **TS-035:** Contact Udemy support via form (test up to submission).
- **TS-036:** Error messages for invalid actions (e.g., wrong login, invalid coupon, failed search).
- **TS-037:** Friendly 404 for invalid or broken course/category links.

---

## 9. Edge & Negative Scenarios

- **TS-038:** Search returns no results (edge keyword).
- **TS-039:** Enroll with missing or invalid user info.
- **TS-040:** Attempt paid checkout with incomplete info (no address, invalid card).
- **TS-041:** Attempt to access course detail as logged out (test what is visible).
- **TS-042:** Attempt to enroll in same course twice.

---

*End of Test Scenarios*
