# Test Cases – DemoQA Text Box Module

**Project:** DemoQA Manual Testing Portfolio

| Field             | Details                        |
| ----------------- | ------------------------------ |
| Module            | Text Box                       |
| Document          | Test Cases                     |
| Prepared By       | Sravani Vanam                  |
| Version           | 1.0                            |
| Status            | Draft                          |
| Related Documents | SRS, Test Plan, Test Scenarios |

---

# 1. Purpose

This document contains the detailed manual test cases for the DemoQA Text Box module. Each test case is derived from the approved Test Scenarios and Functional Requirements to ensure complete functional coverage.

---

# 2. Test Cases

---

## TC-TB-001 — Verify successful form submission with valid data

| Field          | Detail                |
| -------------- | --------------------- |
| Requirement ID | FR-TB-005             |
| Scenario ID    | TS-TB-002             |
| Priority       | High                  |
| Test Type      | Positive / Functional |

### Preconditions

* User is on the DemoQA Text Box page.
* Browser is open.

### Test Data

| Field             | Value                                                   |
| ----------------- | ------------------------------------------------------- |
| Full Name         | John Smith                                              |
| Email             | [john.smith@example.com](mailto:john.smith@example.com) |
| Current Address   | 123 Main Street                                         |
| Permanent Address | 456 Oak Avenue                                          |

### Test Steps

1. Enter a valid Full Name.
2. Enter a valid Email address.
3. Enter the Current Address.
4. Enter the Permanent Address.
5. Click **Submit**.

### Expected Result

* Form is submitted successfully.
* Entered information is displayed below the form.
* Displayed values match the entered values.

---

## TC-TB-002 — Verify Full Name accepts alphabetic characters

| Field          | Detail    |
| -------------- | --------- |
| Requirement ID | FR-TB-001 |
| Scenario ID    | TS-TB-005 |
| Priority       | High      |
| Test Type      | Positive  |

### Preconditions

* User is on the Text Box page.

### Test Data

| Field     | Value         |
| --------- | ------------- |
| Full Name | Sravani Vanam |

### Test Steps

1. Enter alphabetic characters in the Full Name field.
2. Complete the remaining fields with valid data.
3. Click **Submit**.

### Expected Result

* Full Name is accepted.
* Form submits successfully.

---

## TC-TB-003 — Verify Full Name accepts spaces

| Field          | Detail    |
| -------------- | --------- |
| Requirement ID | FR-TB-001 |
| Scenario ID    | TS-TB-005 |
| Priority       | Medium    |
| Test Type      | Positive  |

### Test Data

| Field     | Value      |
| --------- | ---------- |
| Full Name | John Smith |

### Test Steps

1. Enter a Full Name containing spaces.
2. Complete the remaining fields.
3. Click **Submit**.

### Expected Result

* Name containing spaces is accepted.
* Form submits successfully.

---

## TC-TB-004 — Verify Full Name with special characters

| Field          | Detail                |
| -------------- | --------------------- |
| Requirement ID | FR-TB-001             |
| Scenario ID    | TS-TB-005             |
| Priority       | Medium                |
| Test Type      | Negative / Validation |

### Test Data

| Field     | Value   |
| --------- | ------- |
| Full Name | John@#$ |

### Test Steps

1. Enter special characters in the Full Name field.
2. Complete remaining fields.
3. Click **Submit**.

### Expected Result

Record the application's behaviour. If special characters are not allowed by the requirements, the application should reject the input or display a validation message.

---

## TC-TB-005 — Verify valid Email address

| Field          | Detail    |
| -------------- | --------- |
| Requirement ID | FR-TB-002 |
| Scenario ID    | TS-TB-003 |
| Priority       | High      |
| Test Type      | Positive  |

### Test Data

| Field | Value                             |
| ----- | --------------------------------- |
| Email | [qa@test.com](mailto:qa@test.com) |

### Test Steps

1. Enter valid information in all fields.
2. Enter **[qa@test.com](mailto:qa@test.com)** as the Email.
3. Click **Submit**.

### Expected Result

* Email is accepted.
* Form submits successfully.

---

## TC-TB-006 — Verify invalid Email address

| Field          | Detail    |
| -------------- | --------- |
| Requirement ID | FR-TB-002 |
| Scenario ID    | TS-TB-003 |
| Priority       | High      |
| Test Type      | Negative  |

### Test Data

| Field | Value |
| ----- | ----- |
| Email | abc   |

### Test Steps

1. Enter valid values in all fields except Email.
2. Enter **abc** as the Email.
3. Click **Submit**.

### Expected Result

The application should reject the invalid email or display an appropriate validation message. If it accepts the value, a defect should be logged.

---

## TC-TB-007 — Verify submission with empty mandatory fields

| Field          | Detail               |
| -------------- | -------------------- |
| Requirement ID | FR-TB-001, FR-TB-002 |
| Scenario ID    | TS-TB-004            |
| Priority       | High                 |
| Test Type      | Negative             |

### Test Steps

1. Leave the Full Name and Email fields empty.
2. Click **Submit**.

### Expected Result

The application should prevent submission or clearly indicate which mandatory fields require input.

---

## TC-TB-008 — Verify Current Address accepts valid input

| Field          | Detail    |
| -------------- | --------- |
| Requirement ID | FR-TB-003 |
| Scenario ID    | TS-TB-002 |
| Priority       | Medium    |
| Test Type      | Positive  |

### Test Data

| Field           | Value           |
| --------------- | --------------- |
| Current Address | 123 Main Street |

### Test Steps

1. Enter a valid Current Address.
2. Complete all other required fields.
3. Click **Submit**.

### Expected Result

Current Address is accepted and displayed correctly after submission.

---

## TC-TB-009 — Verify Permanent Address accepts valid input

| Field          | Detail    |
| -------------- | --------- |
| Requirement ID | FR-TB-004 |
| Scenario ID    | TS-TB-002 |
| Priority       | Medium    |
| Test Type      | Positive  |

### Test Data

| Field             | Value          |
| ----------------- | -------------- |
| Permanent Address | 456 Oak Avenue |

### Test Steps

1. Enter a valid Permanent Address.
2. Complete all remaining fields.
3. Click **Submit**.

### Expected Result

Permanent Address is accepted and displayed correctly.

---

## TC-TB-010 — Verify submitted information is displayed correctly

| Field          | Detail     |
| -------------- | ---------- |
| Requirement ID | FR-TB-005  |
| Scenario ID    | TS-TB-007  |
| Priority       | High       |
| Test Type      | Functional |

### Preconditions

A successful form submission has been completed.

### Test Steps

1. Submit the form with valid information.
2. Review the displayed output.

### Expected Result

* Full Name matches the entered value.
* Email matches the entered value.
* Current Address matches the entered value.
* Permanent Address matches the entered value.
* No data is missing or incorrectly displayed.

---

# 3. Test Case Summary

| Metric                | Value |
| --------------------- | ----: |
| Total Test Cases      |    10 |
| Positive Test Cases   |     6 |
| Negative Test Cases   |     2 |
| Validation Test Cases |     1 |
| Functional Test Cases |     1 |

---

# 4. Remarks

* All test cases are traceable to one or more functional requirements.
* Test execution results will be documented separately in the **Test Execution Report**.
* Any failed test case will result in a defect being logged in the **Bug Report** document.
