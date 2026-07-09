# Test Execution Report – DemoQA Text Box Module

**Project:** DemoQA Manual Testing Portfolio

| Field             | Details                            |
| ----------------- | ---------------------------------- |
| Module            | Text Box                           |
| Document          | Test Execution Report              |
| Prepared By       | Sravani Vanam                      |
| Version           | 1.0                                |
| Execution Cycle   | Cycle 1                            |
| Test Environment  | Windows 11, Google Chrome (Latest) |
| Execution Date    | 10 July 2026                       |
| Related Documents | Test Cases, RTM, Bug Reports       |

---

# 1. Purpose

The purpose of this document is to record the execution results of all planned test cases for the DemoQA Text Box module.

The report provides execution status, defect references, execution comments, and overall execution metrics.

---

# 2. Test Environment

| Item                   | Value                                 |
| ---------------------- | ------------------------------------- |
| Operating System       | Windows 11                            |
| Browser                | Google Chrome (Latest Stable Version) |
| Application Under Test | DemoQA – Text Box Module              |
| Test Type              | Manual Functional Testing             |

---

# 3. Test Execution Results

| Execution ID | Test Case ID | Requirement ID       | Status | Defect ID  | Executed By   | Execution Date | Comments                                       |
| ------------ | ------------ | -------------------- | ------ | ---------- | ------------- | -------------- | ---------------------------------------------- |
| EX-TB-001    | TC-TB-001    | FR-TB-005            | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Form submitted successfully.                   |
| EX-TB-002    | TC-TB-002    | FR-TB-001            | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Alphabetic input accepted correctly.           |
| EX-TB-003    | TC-TB-003    | FR-TB-001            | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Spaces handled correctly.                      |
| EX-TB-004    | TC-TB-004    | FR-TB-001            | Fail   | BUG-TB-002 | Sravani Vanam | 10-Jul-2026    | Special characters accepted unexpectedly.      |
| EX-TB-005    | TC-TB-005    | FR-TB-002            | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Valid email accepted successfully.             |
| EX-TB-006    | TC-TB-006    | FR-TB-002            | Fail   | BUG-TB-001 | Sravani Vanam | 10-Jul-2026    | Invalid email accepted.                        |
| EX-TB-007    | TC-TB-007    | FR-TB-001, FR-TB-002 | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Mandatory field validation worked as expected. |
| EX-TB-008    | TC-TB-008    | FR-TB-003            | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Current Address accepted correctly.            |
| EX-TB-009    | TC-TB-009    | FR-TB-004            | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Permanent Address accepted correctly.          |
| EX-TB-010    | TC-TB-010    | FR-TB-005            | Pass   | N/A        | Sravani Vanam | 10-Jul-2026    | Submitted information displayed correctly.     |

---

# 4. Execution Metrics

| Metric           | Value |
| ---------------- | ----: |
| Total Test Cases |    10 |
| Executed         |    10 |
| Passed           |     8 |
| Failed           |     2 |
| Blocked          |     0 |
| Not Executed     |     0 |
| Execution Rate   |  100% |
| Pass Rate        |   80% |
| Fail Rate        |   20% |

---

# 5. Defect Summary

| Defect ID  | Related Test Case | Severity | Priority | Status |
| ---------- | ----------------- | -------- | -------- | ------ |
| BUG-TB-001 | TC-TB-006         | Medium   | High     | Open   |
| BUG-TB-002 | TC-TB-004         | Low      | Medium   | Open   |

---

# 6. Execution Observations

* All planned test cases were executed successfully.
* Two defects were identified during execution.
* No test cases were blocked or skipped.
* Requirement coverage remained at 100%.
* Failed test cases have been linked to the corresponding defect reports.

---

# 7. Recommendation

The Text Box module is functionally stable for the majority of tested scenarios.

However, the identified defects should be reviewed and resolved before the module is considered ready for production deployment.

---

# 8. Approval

| Role        | Name          | Status    |
| ----------- | ------------- | --------- |
| QA Engineer | Sravani Vanam | Completed |
| Reviewer    | Self Review   | Approved  |
