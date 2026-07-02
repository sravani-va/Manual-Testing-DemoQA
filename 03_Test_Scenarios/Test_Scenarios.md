# Test Scenarios — DemoQA Text Box Module

**Application Under Test (AUT):** https://demoqa.com/text-box

| Field       | Details            |
| ----------- | ------------------ |
| Module      | Text Box           |
| Prepared By | Sravani Vanam      |
| Test Level  | Functional Testing |
| Version     | 1.0                |

---

# Purpose

This document defines the high-level test scenarios for the DemoQA Text Box module.

The scenarios are designed to ensure that the functionality, validation, and user interactions of the Text Box feature meet the specified requirements.

---

# Test Scenarios

## TS-TB-001 — Verify the Text Box page loads successfully

| Field       | Detail     |
| ----------- | ---------- |
| Requirement | FR-001     |
| Priority    | High       |
| Test Type   | Functional |

**Scenario Description**

Verify that the Text Box page loads successfully and all input fields and controls are displayed correctly.

---

## TS-TB-002 — Verify successful submission with valid data

| Field       | Detail   |
| ----------- | -------- |
| Requirement | FR-005   |
| Priority    | High     |
| Test Type   | Positive |

**Scenario Description**

Verify that a user can submit valid information and that the entered data is displayed correctly after submission.

---

## TS-TB-003 — Verify Email field validation

| Field       | Detail   |
| ----------- | -------- |
| Requirement | FR-002   |
| Priority    | High     |
| Test Type   | Negative |

**Scenario Description**

Verify that the Email field validates incorrect email formats and accepts valid email addresses.

---

## TS-TB-004 — Verify mandatory field behaviour

| Field       | Detail         |
| ----------- | -------------- |
| Requirement | FR-001, FR-002 |
| Priority    | High           |
| Test Type   | Validation     |

**Scenario Description**

Verify the application's behaviour when mandatory fields are left empty before submitting the form.

---

## TS-TB-005 — Verify special character handling

| Field       | Detail           |
| ----------- | ---------------- |
| Requirement | FR-001           |
| Priority    | Medium           |
| Test Type   | Input Validation |

**Scenario Description**

Verify how the application handles special characters entered in the Full Name field.

---

## TS-TB-006 — Verify maximum input length

| Field       | Detail                  |
| ----------- | ----------------------- |
| Requirement | FR-001                  |
| Priority    | Medium                  |
| Test Type   | Boundary Value Analysis |

**Scenario Description**

Verify that the Full Name field handles input at its maximum supported length correctly.

---

# Scenario Summary

| Total Scenarios | High | Medium | Low |
| --------------- | ---: | -----: | --: |
| 6               |    4 |      2 |   0 |
