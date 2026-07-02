# Test Cases – DemoQA Text Box Module

---

## Test Case ID: TC-001

**Requirement ID:** FR-001, FR-005

**Title:**
Verify successful submission with valid data.

**Priority:**
High

**Preconditions:**

- User is on the Text Box page.
- Browser is open.

**Test Data:**

| Field | Value |
|-------|-------|
| Full Name | John Smith |
| Email | john.smith@example.com |
| Current Address | 123 Main Street |
| Permanent Address | 456 Oak Avenue |

**Test Steps:**

1. Enter "John Smith" in the Full Name field.
2. Enter "john.smith@example.com" in the Email field.
3. Enter "123 Main Street" in the Current Address field.
4. Enter "456 Oak Avenue" in the Permanent Address field.
5. Click the **Submit** button.

**Expected Result:**

- The form is submitted successfully.
- The entered information is displayed below the form.
- The displayed data matches the entered values.

---

## Test Case ID: TC-002

**Requirement ID:** FR-002

**Title:**
Verify that the Email field accepts a valid email address.

**Priority:**
High

**Preconditions:**

- User is on the Text Box page.

**Test Data:**

| Field | Value |
|-------|-------|
| Email | qa@test.com |

**Test Steps:**

1. Enter valid data in all required fields.
2. Enter **qa@test.com** in the Email field.
3. Click **Submit**.

**Expected Result:**

- The email is accepted.
- The form is submitted successfully.
- Submitted information is displayed.