# Test Plan — DemoQA Practice Form

**Project:** Manual Testing Portfolio
**Application Under Test (AUT):** DemoQA Practice Form
**Application URL:** https://demoqa.com/automation-practice-form

| Field            | Details           |
| ---------------- | ----------------- |
| Document Version | 1.0               |
| Prepared By      | Sravani Vanam     |
| Review Status    | Draft             |
| Testing Type     | Manual Testing    |
| Project Type     | Portfolio Project |

---

# 1. Purpose

This Test Plan defines the testing strategy, scope, objectives, resources, schedule, and deliverables for the manual testing of the DemoQA Practice Form module.

The objective is to ensure that the Practice Form functions correctly, validates user inputs, handles invalid data appropriately, and provides a smooth user experience before release.

---

# 2. Objectives

The objectives of this testing activity are to:

* Verify all mandatory fields function correctly.
* Validate user input according to business rules.
* Verify successful form submission.
* Validate field-level error handling.
* Execute positive and negative test scenarios.
* Apply industry-standard test design techniques.
* Produce complete QA documentation suitable for portfolio presentation.

---

# 3. Scope

## In Scope

The following functionality will be tested:

* First Name
* Last Name
* Email
* Gender
* Mobile Number
* Date of Birth
* Subjects
* Hobbies
* Picture Upload
* Current Address
* State
* City
* Submit Button
* Confirmation Modal

---

## Out of Scope

The following items are excluded from this testing cycle:

* Performance Testing
* Load Testing
* Security Testing
* Accessibility Testing
* Cross-browser compatibility testing
* Mobile device testing
* API testing
* Database validation

---

# 4. Test Strategy

Testing will be performed manually using functional testing techniques.

The following design techniques will be applied:

* Functional Testing
* Positive Testing
* Negative Testing
* Equivalence Partitioning
* Boundary Value Analysis
* Input Validation Testing
* UI Validation Testing

---

# 5. Test Environment

| Item                | Details                               |
| ------------------- | ------------------------------------- |
| Operating System    | Windows 11                            |
| Browser             | Google Chrome (Latest Stable Version) |
| Internet Connection | Required                              |
| Test Environment    | DemoQA Public Website                 |

---

# 6. Entry Criteria

Testing will begin when all of the following conditions are met:

* Practice Form page is accessible.
* Requirements have been reviewed.
* Test Plan has been prepared.
* Test Scenarios have been completed.
* Test Cases have been reviewed.

---

# 7. Exit Criteria

Testing will be considered complete when:

* All planned test cases have been executed.
* High-priority defects have been reported.
* Test execution results have been documented.
* Test Summary Report has been completed.

---

# 8. Test Deliverables

The following deliverables will be produced during the testing lifecycle:

* Software Requirements Specification (SRS)
* Test Plan
* Test Scenarios
* Test Cases
* Requirement Traceability Matrix (RTM)
* Test Execution Report
* Defect Reports
* Test Summary Report
* Screenshots

---

# 9. Test Design Techniques

| Technique                | Purpose                                              |
| ------------------------ | ---------------------------------------------------- |
| Equivalence Partitioning | Validate representative input values                 |
| Boundary Value Analysis  | Verify minimum and maximum accepted values           |
| Positive Testing         | Confirm expected behaviour using valid inputs        |
| Negative Testing         | Verify system response to invalid inputs             |
| UI Validation            | Ensure controls and messages are displayed correctly |

---

# 10. Risks

| Risk                            | Impact | Mitigation                              |
| ------------------------------- | ------ | --------------------------------------- |
| DemoQA website unavailable      | High   | Resume testing when available           |
| Changes to DemoQA functionality | Medium | Review and update affected test cases   |
| Browser updates                 | Low    | Verify browser version before execution |

---

# 11. Assumptions

* DemoQA remains publicly accessible.
* Test environment remains stable throughout execution.
* No authentication is required to access the Practice Form.
* Internet connectivity is available during testing.

---

# 12. Roles and Responsibilities

| Role              | Responsibility                                                                                             |
| ----------------- | ---------------------------------------------------------------------------------------------------------- |
| QA Engineer       | Review requirements, design test scenarios, create test cases, execute tests, log defects, prepare reports |
| Application Owner | Maintain the DemoQA application (simulated for portfolio purposes)                                         |

---

# 13. Defect Management

Any defects identified during testing will be documented with:

* Defect ID
* Title
* Description
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Status
* Screenshot (if applicable)

---

# 14. Test Completion Criteria

Testing will be considered successful when:

* All planned test cases have been executed.
* Critical and High severity defects have been documented.
* Test Summary Report has been prepared.
* All project artifacts have been committed to GitHub.

---

# 15. Approval

| Role               | Name          | Status   |
| ------------------ | ------------- | -------- |
| QA Engineer        | Sravani Vanam | Approved |
| Portfolio Reviewer | Self Review   | Approved |

---

# Revision History

| Version | Date      | Description       | Author        |
| ------- | --------- | ----------------- | ------------- |
| 1.0     | July 2026 | Initial Test Plan | Sravani Vanam |
