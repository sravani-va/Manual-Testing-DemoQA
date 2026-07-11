# Test Data – DemoQA Text Box Module

**Project:** DemoQA Manual Testing Portfolio

| Field | Details |
|--------|---------|
| Module | Text Box |
| Document | Test Data |
| Prepared By | Sravani Vanam |
| Version | 1.0 |
| Status | Completed |
| Related Documents | Test Cases, Test Execution Report |

---

# 1. Purpose

This document contains the actual test data used during manual testing of the DemoQA Text Box module.

The data was used to validate positive, negative, and special input scenarios.

---

# 2. Test Data Used During Execution

| Test Data ID | Field | Test Value | Test Type | Result |
|--------------|-------|------------|-----------|--------|
| TD-TB-001 | Full Name | John Smith | Valid | Pass |
| TD-TB-002 | Email | john.smith@example.com | Valid | Pass |
| TD-TB-003 | Current Address | 123 Main Street | Valid | Pass |
| TD-TB-004 | Permanent Address | 456 Oak Avenue | Valid | Pass |
| TD-TB-005 | Full Name | John@#$ | Special Characters | Pass |
| TD-TB-006 | Email | qa@test.com | Valid | Pass |
| TD-TB-007 | Current Address | 154 Street Cotlin | Valid | Pass |
| TD-TB-008 | Permanent Address | 456 Avenue park | Valid | Pass |
| TD-TB-009 | Email | abc | Invalid Email | Pass (Validation Displayed) |

---

# 3. Test Data Mapping

| Test Case ID | Test Data Used |
|--------------|----------------|
| TC-TB-001 | TD-TB-001, TD-TB-002, TD-TB-003, TD-TB-004 |
| TC-TB-004 | TD-TB-005, TD-TB-006, TD-TB-007, TD-TB-008 |
| TC-TB-005 | TD-TB-006 |
| TC-TB-006 | TD-TB-009 |
| TC-TB-008 | TD-TB-007 |
| TC-TB-009 | TD-TB-008 |
| TC-TB-010 | TD-TB-001, TD-TB-002, TD-TB-003, TD-TB-004 |

---

# 4. Test Data Summary

| Category | Count |
|----------|------:|
| Valid Test Data | 8 |
| Invalid Test Data | 1 |
| Total Test Data Records | 9 |

---

# 5. Remarks

- Test data was prepared to validate both valid and invalid user inputs.
- Invalid email data was used to verify client-side validation.
- Special character input was tested in the Full Name field and the application accepted the value.
- The same test data can be reused for future regression testing and Selenium automation.

---

# 6. Approval

| Role | Name | Status |
|------|------|--------|
| QA Engineer | Sravani Vanam | Completed |
| Reviewer | Self Review | Approved |