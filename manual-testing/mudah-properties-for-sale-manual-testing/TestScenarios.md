# Test Scenarios: Mudah.my – Properties for Sale

This document lists all high-level test scenarios for the Properties for Sale section on Mudah.my.  
Each scenario will be mapped to one or more detailed test cases in TestCases.xlsx.

---

## 1. Page Load & Navigation

- **TS-001:** Properties for Sale page loads with listings and filters visible
- **TS-002:** Navigation to “Properties for Sale” from homepage and category menus
- **TS-003:** Pagination or infinite scroll works to load more listings

---

## 2. Search & Filter

- **TS-004:** Search properties by location (e.g., Kuala Lumpur, Johor)
- **TS-005:** Filter by price range (min and max)
- **TS-006:** Filter by property type (e.g., Condo, House, Land, Commercial)
- **TS-007:** Filter by number of bedrooms/bathrooms
- **TS-008:** Apply multiple filters simultaneously (e.g., location + price + type)
- **TS-009:** Remove or reset all filters
- **TS-010:** Zero-result searches handled gracefully

---

## 3. Sorting

- **TS-011:** Sort by Price (Low to High, High to Low)
- **TS-012:** Sort by Newest and Oldest listings

---

## 4. Listing Details

- **TS-013:** Open property detail page from listing
- **TS-014:** Images/photo gallery navigates properly (carousel, zoom)
- **TS-015:** Listing info (price, location, size, type, agent info, amenities) is complete and accurate
- **TS-016:** Map is present and pin matches property location
- **TS-017:** Share button opens available share options (WhatsApp, Facebook, etc.)
- **TS-018:** Report Ad button works, submits feedback/reason

---

## 5. Contact Flows

- **TS-019:** “Contact Agent/Seller” options (call, WhatsApp, email, form) appear and work for visible listings
- **TS-020:** Attempting to contact while logged out prompts login/signup
- **TS-021:** As logged-in user, successfully send message/contact to agent

---

## 6. Favourites & User Account

- **TS-022:** Favouriting a listing as logged-out prompts login
- **TS-023:** User registration and login
- **TS-024:** Favourite/unfavourite listing as logged-in user
- **TS-025:** View/manage list of favourite properties (add/remove)
- **TS-026:** Logout and verify access to account-specific features is revoked

---

## 7. Mobile & Responsiveness

- **TS-027:** Properties for Sale page displays correctly on mobile devices
- **TS-028:** Images and buttons are visible and accessible on mobile/tablet
- **TS-029:** Filters and sort menus function on mobile browsers

---

## 8. Accessibility & Usability

- **TS-030:** Images have descriptive alt text or labels
- **TS-031:** Site is navigable via keyboard (TAB/ENTER for links, buttons)
- **TS-032:** Color contrast and font size meet readability guidelines

---

## 9. Performance & Edge Cases

- **TS-033:** Properties for Sale page and details load within 3 seconds
- **TS-034:** Edge: Impossible filter ranges (min price > max price) are handled
- **TS-035:** Edge: No listings for nonsensical search shows friendly message
- **TS-036:** Page is stable under rapid filter changes or refresh

---

## 10. Security

- **TS-037:** Cannot contact seller or favourite without being logged in (for flows that require it)
- **TS-038:** Session persists after reload and is cleared after logout
- **TS-039:** URL manipulation does not expose unauthorised data or break the site

---

*End of Test Scenarios*
