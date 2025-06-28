# Summary Report: Mudah.my – Properties for Sale Manual Testing

## 1. Overview

Manual testing was conducted on the “Properties for Sale” section of Mudah.my to validate all core user flows, UI elements, search, filter, detail pages, contact, and user account features.  
Testing was performed on desktop (Chrome/Firefox) and mobile browsers to cover real user scenarios.

---

## 2. Test Coverage & Execution

| Feature Area               | Test Cases | Pass | Fail | Blocked |
|----------------------------|------------|------|------|---------|
| Page Load & Navigation     |     3      |  3   |  0   |    0    |
| Search & Filters           |     6      |  4   |  2   |    0    |
| Sorting                    |     2      |  2   |  0   |    0    |
| Listing Details            |     4      |  3   |  1   |    0    |
| Contact & Favourites       |     6      |  4   |  2   |    0    |
| Account/Login              |     3      |  3   |  0   |    0    |
| Mobile & Responsiveness    |     3      |  3   |  0   |    0    |
| Accessibility & Usability  |     3      |  2   |  1   |    0    |
| Performance & Edge Cases   |     3      |  2   |  1   |    0    |
| Security                   |     3      |  2   |  1   |    0    |
| **Total**                  |   **36**   |**28**| **8**| **0**   |

---

## 3. Key Findings

- **Most primary features work as intended:** navigation, search, account creation, basic filtering, and detail page loading all passed.
- **8 bugs were logged:**  
  - Filtering and favourite logic not robust in edge cases.
  - Some security and usability issues (e.g., favourites/contact without login).
  - Minor accessibility and image alt text gaps.
- **Performance on desktop/mobile is generally good,** though more filters or rapid interactions occasionally cause minor glitches.

---

## 4. Defect Summary

| Bug ID  | Area                    | Summary                                  | Severity | Status | 
|---------|-------------------------|------------------------------------------|----------|--------|
| BUG-001 | Filters                 | Price filter not applied correctly       | Major    | Open   | 
| BUG-002 | Details                 | Image gallery arrows don’t work (mobile) | Minor    | Open   |
| BUG-003 | Contact/Security        | Contact button works when not logged in  | Major    | Open   | 
| BUG-004 | Filters                 | No error for impossible price range      | Minor    | Open   |
| BUG-005 | Favourites              | Unfavourited listings remain visible     | Minor    | Open   |
| BUG-006 | Search                  | Zero-result message not user-friendly    | Minor    | Open   |
| BUG-007 | Accessibility           | Images missing alt text                  | Minor    | Open   |
| BUG-008 | Security/Favourites     | Can favourite without login              | Major    | Open   |

---

## 5. Recommendations

- **Fix filtering and search logic** to always match selected criteria and gracefully handle zero/invalid ranges.
- **Enforce login requirements** for contact and fav
