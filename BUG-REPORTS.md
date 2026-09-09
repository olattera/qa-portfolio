DemoQA Bug Reports

The following reports are portfolio examples based on publicly documented testing observations and reference material. They should not be presented as defects personally discovered during execution unless independently verified.

⸻

BUG-001: Invalid email value is accepted by Text Box form

ID: BUG-001

Module: Elements / Text Box

Severity: Medium

Priority: Medium

Status: Open

Preconditions

Text Box page is open.

Steps to Reproduce

1. Enter a valid name.
2. Enter an incorrectly formatted email address.
3. Fill the remaining fields.
4. Click Submit.

Expected Result

The invalid email should be rejected and the user should receive validation feedback.

Actual Result

The form may accept the entered value without displaying an appropriate validation message.

Environment

Google Chrome

Notes

This report requires verification against the current version of DemoQA before being described as a confirmed defect.

⸻

BUG-002: Search result state is unclear when no records match

ID: BUG-002

Module: Elements / Web Tables

Severity: Low

Priority: Low

Status: Open

Preconditions

Web Tables page is open.

Steps to Reproduce

1. Enter a value that does not exist in the table.
2. Observe the table.

Expected Result

The interface should clearly indicate that no matching records were found.

Actual Result

The resulting empty state can be unclear to the user.

Environment

Google Chrome

Notes

This is primarily a usability observation and should be verified before being classified as a product defect.
