# Bug Reports – DemoQA Text Box Module

**Project:** DemoQA Manual Testing Portfolio

| Field             | Details         |
| ----------------- | --------------- |
| Module            | Text Box        |
| Document          | Bug Reports     |
| Prepared By       | Sravani Vanam   |
| Version           | 1.0             |
| Status            | Open            |
| Related Documents | Test Cases, RTM |

---

# 1. Purpose

This document records the defects identified during manual testing of the DemoQA Text Box module.

Each defect includes sufficient information for developers to reproduce the issue, understand its impact, and implement a fix.

---

# Bug Report 1

## BUG-TB-001 — Invalid Email Address Validation

| Field               | Detail                             |
| ------------------- | ---------------------------------- |
| Defect ID           | BUG-TB-001                         |
| Module              | Text Box                           |
| Related Requirement | FR-TB-002                          |
| Related Scenario    | TS-TB-003                          |
| Related Test Case   | TC-TB-006                          |
| Severity            | Medium                             |
| Priority            | High                               |
| Status              | Open                               |
| Environment         | Windows 11, Google Chrome (Latest) |
| Reported By         | Sravani Vanam                      |

### Description

The application allows an invalid email address to be submitted without displaying a validation message.

### Preconditions

* User is on the DemoQA Text Box page.
* Browser is open.

### Steps to Reproduce

1. Navigate to the Text Box page.
2. Enter a valid Full Name.
3. Enter **abc** in the Email field.
4. Enter valid Current Address and Permanent Address.
5. Click **Submit**.

### Expected Result

The application should reject the invalid email address and display an appropriate validation message.

### Actual Result

The form accepts the invalid email address and displays the submitted information.

### Business Impact

Invalid email addresses may be stored, leading to poor data quality and failed customer communications.

### Recommendation

Implement client-side and server-side email format validation before allowing form submission.

---

# Bug Report 2

## BUG-TB-002 — Full Name Field Accepts Unsupported Special Characters

| Field               | Detail                             |
| ------------------- | ---------------------------------- |
| Defect ID           | BUG-TB-002                         |
| Module              | Text Box                           |
| Related Requirement | FR-TB-001                          |
| Related Scenario    | TS-TB-005                          |
| Related Test Case   | TC-TB-004                          |
| Severity            | Low                                |
| Priority            | Medium                             |
| Status              | Open                               |
| Environment         | Windows 11, Google Chrome (Latest) |
| Reported By         | Sravani Vanam                      |

### Description

The Full Name field accepts special characters without validation.

### Preconditions

* User is on the DemoQA Text Box page.

### Steps to Reproduce

1. Navigate to the Text Box page.
2. Enter **John@#$** in the Full Name field.
3. Enter valid values in the remaining fields.
4. Click **Submit**.

### Expected Result

The application should either reject unsupported special characters or validate the input according to the business rules.

### Actual Result

The application accepts the value and displays it after submission.

### Business Impact

Acceptance of invalid name formats may reduce data quality and create inconsistent customer records.

### Recommendation

Define and implement input validation rules for the Full Name field.

---

# 2. Defect Summary

| Defect ID  | Related Test Case | Title                                                  | Severity | Priority | Status |
| ---------- | ----------------- | ------------------------------------------------------ | -------- | -------- | ------ |
| BUG-TB-002 | TC-TB-004         | Full Name Field Accepts Unsupported Special Characters | Low      | Medium   | Open   |

---

# 3. Remarks

* Each defect is traceable to a functional requirement, test scenario, and test case.
* Defect severity indicates the impact on the application.
* Defect priority indicates the urgency of fixing the issue.
* Defects should be re-tested after fixes are implemented and their status updated accordingly.
