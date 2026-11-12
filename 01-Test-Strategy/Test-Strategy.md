
# Test Strategy Document

## 1. Project Overview

**Project Name:** SauceDemo Manual QA Testing Portfolio

**Application:** SauceDemo

**Website:** https://www.saucedemo.com/

**Testing Type:** Manual Functional Testing

**Domain:** E-commerce

### Project Description

This project focuses on manually testing SauceDemo, a demo e-commerce web application.

The objective is to verify application functionality, identify defects, execute test scenarios, and maintain professional QA documentation.

The testing covers login, product browsing, sorting, shopping cart operations, and the complete checkout process.

---

## 2. Scope of Testing

### 2.1 In-Scope

The following features will be tested:

- Login and authentication
- Product listing and product details
- Product sorting
- Add to Cart and Remove from Cart
- Shopping cart functionality
- Checkout information form
- Checkout overview and price calculations
- Order completion
- Logout functionality
- Cart persistence after logout and login
- Browser navigation
- Input validation and error messages
- UI consistency across different test accounts

### 2.2 Out-of-Scope

The following areas will not be tested:

- Actual payment gateway integration
- Real financial transactions
- Backend database testing
- Source code testing
- Security penetration testing
- Formal performance load and stress testing
- Mobile application testing

---

## 3. Testing Approach

The project will follow a manual testing approach using the following techniques:

- **Functional Testing:** Verify that application features work as expected.
- **Positive Testing:** Verify functionality using valid inputs.
- **Negative Testing:** Check application behaviour with invalid or missing inputs.
- **Boundary Value Testing:** Test input values at their limits.
- **Exploratory Testing:** Explore the application without predefined test cases to identify unexpected behaviour.
- **UI Testing:** Verify the appearance and consistency of interface elements.
- **Regression Testing:** Recheck existing functionality after changes or fixes.

---

## 4. Testing Environment and Tools

### 4.1 Environment

- Operating System: Windows 11
- Browser: Google Chrome
- Application: SauceDemo
- Testing Type: Manual Testing

### 4.2 Tools

| Tool | Purpose |
|---|---|
| Google Sheets / Excel | Test case management and traceability matrix |
| Jira | Defect tracking |
| GitHub | Version control and portfolio hosting |
| ShareX | Screenshot and screen recording |
| Chrome DevTools | Browser inspection and debugging |
| Visual Studio Code | Documentation editing |
| Markdown | Project documentation |

---

## 5. Entry and Exit Criteria

### 5.1 Entry Criteria

Testing can begin when:

- The application is accessible.
- The testing environment is ready.
- Valid test credentials are available.
- Requirements are documented.
- Test cases are prepared.

### 5.2 Exit Criteria

Testing can be considered complete when:

- All planned test cases have been executed or their blocked status documented.
- Test results are recorded.
- Identified defects are documented.
- Requirements Traceability Matrix is updated.
- Exploratory testing sessions are completed and documented.
- Major unresolved defects and testing limitations are reported.

---

## 6. Risks and Mitigation

| Risk | Impact | Mitigation |
|---|---|---|
| Application downtime | Testing interruption | Retry when application becomes available |
| Unstable internet | Slow or failed page loading | Verify network connectivity |
| Different test account behaviours | Unexpected results | Document account-specific behaviour |
| Application updates | Test cases may become outdated | Review test cases periodically |
| Missing test coverage | Defects may remain undetected | Maintain a Traceability Matrix |

---

## 7. Defect Management

Identified defects will be documented and tracked using Jira and GitHub Issues.

Each defect report will contain:

- Defect ID and title
- Environment
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Screenshot or video evidence

### Severity Classification

- **Critical:** Application or major functionality is completely blocked.
- **High:** Important functionality is seriously affected.
- **Medium:** Functionality is partially affected.
- **Low:** Minor issue with limited impact.

### Priority Classification

- **High:** Requires immediate attention.
- **Medium:** Should be fixed soon.
- **Low:** Can be addressed later.

Only reproducible defects will be reported. Intentional behaviours of predefined test accounts will be documented separately.

---

## 8. Test Data

The following test accounts will be used:

| Username | Testing Purpose |
|---|---|
| standard_user | Normal application behaviour |
| locked_out_user | Login restriction testing |
| problem_user | UI and functional issue testing |
| performance_glitch_user | Slow response behaviour |
| error_user | Error behaviour testing |
| visual_user | Visual layout testing |

**Password:** secret_sauce

Additional test data will include:

- Valid and invalid login credentials
- Blank and valid checkout information
- Different product selections
- Multiple cart combinations
- Special characters and boundary input values

---

## 9. Project Limitations

- SauceDemo is a public demonstration application.
- Some test accounts intentionally contain predefined issues.
- Actual payment processing cannot be verified.
- Backend and database operations are outside the testing scope.
- Application availability and behaviour may change.
- Performance observations are limited to manual checks and do not represent formal load testing.

---

## 10. Project Deliverables

The project will produce the following QA deliverables:

1. Test Strategy Document
2. Requirements Document with user stories and acceptance criteria
3. Manual Test Cases
4. Requirements Traceability Matrix
5. Defect Reports with supporting evidence
6. Exploratory Testing Session Reports
7. Test Execution Summary

All project documentation and supporting evidence will be maintained in the GitHub repository.

---

**Document Status:** In Progress

**Testing Type:** Manual Testing

**Application Under Test:** SauceDemo
