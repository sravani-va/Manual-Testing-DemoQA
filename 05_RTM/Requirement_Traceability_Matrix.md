# Requirement Traceability Matrix (RTM) – DemoQA Text Box Module

**Project:** DemoQA Manual Testing Portfolio

| Field             | Details                                    |
| ----------------- | ------------------------------------------ |
| Module            | Text Box                                   |
| Document          | Requirement Traceability Matrix (RTM)      |
| Prepared By       | Sravani Vanam                              |
| Version           | 1.0                                        |
| Status            | Draft                                      |
| Related Documents | SRS, Test Plan, Test Scenarios, Test Cases |

---

# 1. Purpose

The Requirement Traceability Matrix (RTM) ensures that every functional requirement has been mapped to one or more test scenarios and detailed test cases.

The RTM provides complete traceability from business requirements through to testing activities and helps identify any missing or uncovered requirements.

---

# 2. Requirement Traceability Matrix

| Requirement ID | Functional Requirement                                                           | Test Scenario ID(s)                        | Test Case ID(s)                                       | Coverage Status |
| -------------- | -------------------------------------------------------------------------------- | ------------------------------------------ | ----------------------------------------------------- | --------------- |
| **FR-TB-001**  | The system shall allow the user to enter a Full Name.                            | TS-TB-001, TS-TB-004, TS-TB-005, TS-TB-006 | TC-TB-001, TC-TB-002, TC-TB-003, TC-TB-004, TC-TB-007 | Covered         |
| **FR-TB-002**  | The system shall allow the user to enter a valid Email address.                  | TS-TB-003, TS-TB-004                       | TC-TB-001, TC-TB-005, TC-TB-006, TC-TB-007            | Covered         |
| **FR-TB-003**  | The system shall allow the user to enter the Current Address.                    | TS-TB-002                                  | TC-TB-001, TC-TB-008                                  | Covered         |
| **FR-TB-004**  | The system shall allow the user to enter the Permanent Address.                  | TS-TB-002                                  | TC-TB-001, TC-TB-009                                  | Covered         |
| **FR-TB-005**  | The system shall display submitted information after clicking the Submit button. | TS-TB-002, TS-TB-007                       | TC-TB-001, TC-TB-010                                  | Covered         |

---

# 3. Coverage Summary

| Metric                        | Value |
| ----------------------------- | ----: |
| Total Functional Requirements |     5 |
| Total Test Scenarios          |     7 |
| Total Test Cases              |    10 |
| Requirements Covered          |     5 |
| Requirements Not Covered      |     0 |
| Coverage Percentage           |  100% |

---

# 4. Traceability Flow

The following traceability has been established for this module:

```text
Requirements (SRS)
        ↓
Test Scenarios
        ↓
Test Cases
        ↓
Test Execution
        ↓
Defects (if any)
        ↓
Test Summary Report
```

This ensures that every requirement is verified through planned testing activities and can be traced throughout the Software Testing Life Cycle (STLC).

---

# 5. Remarks

* Every functional requirement has been mapped to one or more test scenarios.
* Every test scenario is supported by one or more detailed test cases.
* No functional requirements remain untested.
* The RTM will be updated if new requirements or test cases are added during future testing cycles.

---

# 6. Approval

| Role        | Name          | Status   |
| ----------- | ------------- | -------- |
| QA Engineer | Sravani Vanam | Approved |
| Reviewer    | Self Review   | Approved |
