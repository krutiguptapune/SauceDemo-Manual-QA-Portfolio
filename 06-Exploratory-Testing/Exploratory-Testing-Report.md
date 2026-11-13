
# SauceDemo Exploratory Testing Report

## 1. Overview

- **Application:** SauceDemo
- **Testing Type:** Exploratory Testing
- **Test Environment:** Windows / Google Chrome
- **Date:** 13 November 2026
- **Tester:** QA Tester

## 2. Testing Objectives

- Explore application functionality beyond predefined test cases.
- Identify unexpected application behaviour.
- Evaluate different user account experiences.
- Observe navigation, cart operations and checkout behaviour.

## 3. Areas Explored

| Area | Activities |
|---|---|
| Login | Tested different user accounts |
| Products | Explored product listings and images |
| Sorting | Tested different sorting options |
| Shopping Cart | Added and removed products |
| Checkout | Completed the checkout process |
| Navigation | Tested application navigation and browser controls |
| User Accounts | Compared behaviour across different accounts |

## 4. Exploratory Testing Observations

| ID | Observation | Affected Account | Result |
|---|---|---|---|
| EXP-001 | Incorrect product images displayed | problem_user | Known issue documented |
| EXP-002 | Visual layout inconsistencies observed | visual_user | Known issue documented |
| EXP-003 | Noticeable application delays | performance_glitch_user | Known issue documented |
| EXP-004 | Some cart actions behaved unexpectedly during earlier exploration | error_user | Further verification required |
| EXP-005 | Standard user completed checkout successfully | standard_user | Successful |
| EXP-006 | Cart contents remained after logout and login with the same account | standard_user | Observed |

## 5. Known Limitations

- SauceDemo is a demonstration application.
- Some user accounts contain intentionally seeded behaviours.
- No formal load or stress testing was performed.
- No backend or database testing was performed.

## 6. Conclusion

Exploratory testing helped evaluate the application beyond predefined test cases. Different user accounts were explored, application behaviour was observed, and known issues were documented for reference.

Further testing may identify additional issues.
