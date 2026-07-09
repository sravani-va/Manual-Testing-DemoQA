# Test Scenarios – DemoQA Text Box Module

**Project:** DemoQA Manual Testing Portfolio

| Field             | Details        |
| ----------------- | -------------- |
| Module            | Text Box       |
| Document          | Test Scenarios |
| Prepared By       | Sravani Vanam  |
| Version           | 1.0            |
| Status            | Draft          |
| Related Documents | SRS, Test Plan |

---

# 1. Purpose

This document defines the high-level test scenarios for the **DemoQA Text Box** module. These scenarios are derived from the Software Requirements Specification (SRS) and provide the basis for creating detailed test cases.

---

# 2. Scope

The following functionality is covered:

* Full Name
* Email
* Current Address
* Permanent Address
* Submit Button
* Displayed Output

---

# 3. Test Scenarios

---

## TS-TB-001 — Verify Text Box page loads successfully

| Field          | Detail     |
| -------------- | ---------- |
| Requirement ID | FR-TB-001  |
| Priority       | High       |
| Test Type      | Functional |

**Scenario Description**

Verify that the Text Box page loads successfully and all input fields and controls are displayed correctly.

---

## TS-TB-002 — Verify successful submission with valid data

| Field          | Detail    |
| -------------- | --------- |
| Requirement ID | FR-TB-005 |
| Priority       | High      |
| Test Type      | Positive  |

**Scenario Description**

Verify that a user can successfully submit valid information using all input fields.

---

## TS-TB-003 — Verify Email field validation

| Field          | Detail     |
| -------------- | ---------- |
| Requirement ID | FR-TB-002  |
| Priority       | High       |
| Test Type      | Validation |

**Scenario Description**

Verify that the Email field accepts valid email addresses and appropriately handles invalid email formats.

---

## TS-TB-004 — Verify mandatory field behaviour

| Field          | Detail               |
| -------------- | -------------------- |
| Requirement ID | FR-TB-001, FR-TB-002 |
| Priority       | High                 |
| Test Type      | Negative             |

**Scenario Description**

Verify the application's behaviour when mandatory fields are left empty before submitting the form.

---

## TS-TB-005 — Verify Full Name input validation

| Field          | Detail           |
| -------------- | ---------------- |
| Requirement ID | FR-TB-001        |
| Priority       | Medium           |
| Test Type      | Input Validation |

**Scenario Description**

Verify how the Full Name field handles alphabetic characters, numbers, special characters and whitespace.

---

## TS-TB-006 — Verify boundary conditions for Full Name

| Field          | Detail                  |
| -------------- | ----------------------- |
| Requirement ID | FR-TB-001               |
| Priority       | Medium                  |
| Test Type      | Boundary Value Analysis |

**Scenario Description**

Verify the application's behaviour when minimum, maximum and excessive input lengths are entered into the Full Name field.

---

## TS-TB-007 — Verify submitted data is displayed correctly

| Field          | Detail     |
| -------------- | ---------- |
| Requirement ID | FR-TB-005  |
| Priority       | High       |
| Test Type      | Functional |

**Scenario Description**

Verify that all submitted information is displayed accurately after a successful form submission.

---

# 4. Scenario Summary

| Metric          | Value |
| --------------- | ----: |
| Total Scenarios |     7 |
| High Priority   |     5 |
| Medium Priority |     2 |
| Low Priority    |     0 |

---

# 5. Remarks

* Each scenario maps to one or more functional requirements.
* Detailed execution steps are documented in the **Test Cases** document.
* Requirement coverage will be verified through the **Requirement Traceability Matrix (RTM)**.
