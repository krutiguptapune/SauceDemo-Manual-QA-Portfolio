
# SauceDemo Manual QA Testing Portfolio

## Project Overview

This project demonstrates manual software testing of [SauceDemo](https://www.saucedemo.com/), a demo e-commerce web application.

The objective is to evaluate application functionality, design and execute test cases, identify unexpected behaviour, document issues, and maintain professional QA documentation.

## Application Under Test

| Detail | Description |
|---|---|
| Application | SauceDemo |
| Website | https://www.saucedemo.com/ |
| Domain | E-commerce |
| Testing Type | Manual Testing |
| Test Environment | Windows / Google Chrome |
| Project Status | In Progress |

## Project Objectives

- Understand application functionality and requirements.
- Design positive, negative and boundary test cases.
- Execute test cases and compare actual results with expected results.
- Maintain a Requirements Traceability Matrix (RTM).
- Identify and document application issues.
- Perform exploratory testing.
- Manage issues using Jira.
- Maintain testing evidence and project documentation.

## Tools Used

| Tool | Purpose |
|---|---|
| Google Sheets / Microsoft Excel | Test case design, execution tracking and RTM |
| Jira | Defect tracking and issue management |
| ShareX | Screenshot and screen recording evidence |
| Markdown | QA documentation |
| Git | Version control |
| GitHub | Portfolio management |
| Google Chrome | Application testing |

## Testing Scope

The project covers the following application modules:

- User Login and Authentication
- Product Listing
- Product Sorting
- Product Details
- Shopping Cart Operations
- Checkout Information
- Checkout Validation
- Order Completion
- User Interface
- Session Management
- Browser Navigation

## Project Deliverables

| Deliverable | Description |
|---|---|
| Test Strategy | Defines testing scope, approach, risks and entry/exit criteria |
| Requirements Document | Functional requirements and acceptance criteria |
| Test Cases | 110 test cases covering major application functionality |
| Execution Summary | Tracks Pass, Fail, Blocked and Not Run statuses |
| Requirements Traceability Matrix | Maps requirements to related test cases |
| Defect Log | Central record of documented application issues |
| Known Issues Report | Documents intentionally seeded application behaviours |
| Exploratory Testing Report | Records observations from exploratory testing |
| Defect Evidence | Screenshots and recordings supporting observations |
| Jira Integration | Tracks documented issues through a Kanban board |

## Test Case Coverage

The test suite contains 110 designed test cases covering:

- Login and authentication scenarios
- Product listing and sorting
- Product details
- Cart operations and persistence
- Checkout and validation
- Order completion
- UI consistency
- User account behaviour
- Session management
- Browser navigation

Test execution results are maintained separately in the execution spreadsheet.

## Defect Management and Jira Integration

A dedicated Jira project was created.

- **Project Name:** SauceDemo QA Testing
- **Project Key:** SDQA
- **Board Type:** Kanban

The Kanban workflow includes:

1. Backlog
2. Selected for Development
3. In Progress
4. Retest
5. Done

Jira is used to document issues with:

- Issue summaries and descriptions
- Preconditions and reproduction steps
- Expected and actual results
- Priority and labels
- Screenshot and recording attachments
- Related test case references

Three known, intentionally seeded SauceDemo behaviours have been documented for testing practice.

## Known Application Behaviours

| Issue ID | Description | Affected Account |
|---|---|---|
| KNOWN-001 | Incorrect product images | problem_user |
| KNOWN-002 | Visual layout inconsistencies | visual_user |
| KNOWN-003 | Noticeable application delays | performance_glitch_user |

**Note:** These behaviours are intentionally seeded in SauceDemo. They are documented as known application behaviours and are not represented as independently discovered defects.

## Exploratory Testing

Exploratory testing was performed across different user accounts and application modules.

Activities included:

- Exploring different user account behaviours.
- Testing product and cart functionality.
- Verifying checkout navigation.
- Observing application response behaviour.
- Comparing UI behaviour across accounts.
- Recording unexpected observations.

## Repository Structure

```text
SauceDemo-Manual-QA-Portfolio/
│
├── 01-Test-Strategy/
│   └── Test-Strategy.md
│
├── 02-Requirements/
│   └── Requirements.md
│
├── 03-Test-Cases/
│
├── 04-Traceability-Matrix/
│
├── 05-Defect-Reports/
│   ├── Defect-Report-Template.md
│   ├── Known-Issues.md
│   └── Defect-Evidence/
│
├── 06-Exploratory-Testing/
│   └── Exploratory-Testing-Report.md
│
├── .gitignore
└── README.md
```

The test case spreadsheet, execution summary, traceability matrix and Jira project are maintained separately.

## Current Project Status

| Activity | Status |
|---|---|
| Test Strategy | Completed |
| Requirements Documentation | Completed |
| Test Case Design | Completed |
| Execution Summary Setup | Completed |
| Requirements Traceability Matrix | Created |
| Defect Documentation | In Progress |
| Jira Integration | Completed |
| Exploratory Testing Documentation | Completed |
| Test Execution Verification | In Progress |
| Final Portfolio Review | Pending |

## Learning Outcomes

Through this project, I am developing practical experience in:

- Manual Software Testing
- Test Case Design
- Test Execution
- Functional and Exploratory Testing
- Defect Reporting
- Severity and Priority Classification
- Requirements Traceability
- Jira Issue Management
- Test Evidence Documentation
- Git and GitHub

## Author

**Kruti Gupta**

Manual QA Testing Portfolio Project

GitHub: [SauceDemo Manual QA Portfolio](https://github.com/krutiguptapune/SauceDemo-Manual-QA-Portfolio)