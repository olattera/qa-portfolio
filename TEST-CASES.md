DemoQA Test Cases

Elements / Text Box

TC-TB-001: Submit form with valid data

Priority: High

Preconditions: Text Box page is open.

Steps:

1. Enter a valid full name.
2. Enter a valid email.
3. Enter a current address.
4. Enter a permanent address.
5. Click Submit.

Expected Result:

The submitted information is displayed in the output section.

⸻

TC-TB-002: Submit form with empty fields

Priority: Medium

Steps:

1. Open Text Box.
2. Leave all fields empty.
3. Click Submit.

Expected Result:

The application does not create a valid completed submission.

⸻

TC-TB-003: Enter invalid email

Priority: High

Steps:

1. Enter a valid name.
2. Enter an incorrectly formatted email address.
3. Fill the remaining required information.
4. Click Submit.

Expected Result:

The email field is identified as invalid and the invalid value is not accepted as a valid email.

⸻

Elements / Check Box

TC-CB-001: Select a checkbox

Priority: High

Steps:

1. Open Check Box.
2. Expand the required tree node.
3. Select one checkbox.

Expected Result:

The selected checkbox becomes checked and the corresponding selection is displayed.

⸻

TC-CB-002: Select parent checkbox

Priority: Medium

Steps:

1. Expand the checkbox tree.
2. Select a parent checkbox.

Expected Result:

The corresponding child options are selected according to the application’s checkbox logic.

⸻

TC-CB-003: Unselect a checkbox

Priority: Medium

Steps:

1. Select a checkbox.
2. Select it again.

Expected Result:

The checkbox returns to the unselected state and the selection output is updated.

⸻

Elements / Radio Button

TC-RB-001: Select a valid radio button

Priority: High

Steps:

1. Open Radio Button.
2. Select Yes.

Expected Result:

The selected option is displayed in the result area.

⸻

TC-RB-002: Select another radio button

Priority: Medium

Steps:

1. Select Yes.
2. Select Impressive.

Expected Result:

Only the latest selected option remains active.

⸻

TC-RB-003: Verify disabled option

Priority: Low

Steps:

1. Open Radio Button.
2. Locate the disabled option.
3. Attempt to select it.

Expected Result:

The disabled option cannot be selected.

⸻

Elements / Web Tables

TC-WT-001: Add a new record

Priority: High

Steps:

1. Open Web Tables.
2. Click Add.
3. Enter valid information into all required fields.
4. Submit the form.

Expected Result:

A new record appears in the table.

⸻

TC-WT-002: Add record with empty required field

Priority: High

Steps:

1. Click Add.
2. Leave one required field empty.
3. Fill the remaining fields.
4. Submit.

Expected Result:

The record is not created and validation is displayed.

⸻

TC-WT-003: Edit an existing record

Priority: High

Steps:

1. Select an existing record.
2. Click Edit.
3. Change one or more values.
4. Save the changes.

Expected Result:

The record contains the updated information.

⸻

TC-WT-004: Delete an existing record

Priority: High

Steps:

1. Select an existing record.
2. Click Delete.

Expected Result:

The selected record is removed from the table.

⸻

TC-WT-005: Search for a record

Priority: Medium

Steps:

1. Enter an existing value in the search field.
2. Observe the table.

Expected Result:

The table displays matching records.

⸻

TC-WT-006: Search with a value that does not exist

Priority: Low

Steps:

1. Enter a value that does not exist.
2. Observe the table.

Expected Result:

No matching records are displayed.

⸻

Forms / Practice Form

TC-PF-001: Submit form with valid information

Priority: Critical

Steps:

1. Open Practice Form.
2. Enter valid first name.
3. Enter valid last name.
4. Enter valid email.
5. Select gender.
6. Enter mobile number.
7. Select date of birth.
8. Enter subjects.
9. Select hobbies.
10. Enter address.
11. Select state and city.
12. Submit.

Expected Result:

The form is submitted successfully and the submitted information is displayed.

⸻

TC-PF-002: Submit form without first name

Priority: High

Steps:

1. Open Practice Form.
2. Leave First Name empty.
3. Fill the remaining required fields.
4. Submit.

Expected Result:

The form is not submitted and the required field is highlighted.

⸻

TC-PF-003: Submit form without last name

Priority: High

Steps:

1. Leave Last Name empty.
2. Fill the remaining required information.
3. Submit.

Expected Result:

The form is not submitted successfully.

⸻

TC-PF-004: Enter invalid mobile number

Priority: High

Steps:

1. Enter an invalid mobile number.
2. Fill the remaining required fields.
3. Submit.

Expected Result:

The invalid mobile number is rejected by validation.

⸻

TC-PF-005: Submit form without selecting gender

Priority: High

Steps:

1. Fill the required text fields.
2. Do not select gender.
3. Submit.

Expected Result:

The form is not submitted successfully because gender is required.

⸻

Alerts

TC-AL-001: Open simple alert

Priority: Medium

Steps:

1. Open Alerts.
2. Click the button that opens a simple alert.
3. Confirm the alert.

Expected Result:

An alert dialog appears and can be closed successfully.

⸻

TC-AL-002: Open confirmation alert

Priority: Medium

Steps:

1. Open the confirmation alert.
2. Select OK.

Expected Result:

The corresponding confirmation result is displayed.

⸻

TC-AL-003: Cancel confirmation alert

Priority: Medium

Steps:

1. Open the confirmation alert.
2. Select Cancel.

Expected Result:

The corresponding cancellation result is displayed.

⸻

Browser Windows

TC-BW-001: Open a new browser window

Priority: Medium

Steps:

1. Open Browser Windows.
2. Click the button that opens a new window.
3. Switch to the new window.

Expected Result:

A new browser window opens and displays the expected content.

⸻

TC-BW-002: Open a new browser tab

Priority: Medium

Steps:

1. Open Browser Windows.
2. Click the button that opens a new tab.
3. Switch to the new tab.

Expected Result:

A new browser tab opens and displays the expected content.

⸻

CHECKLIST.md

DemoQA Testing Checklist

Text Box

* Full name accepts valid input
* Email accepts valid format
* Invalid email is rejected
* Address fields accept text
* Submit button works
* Submitted information is displayed

Check Box

* Checkbox can be selected
* Checkbox can be unselected
* Parent checkbox works
* Child selections are displayed
* Selected state is visually clear

Radio Button

* Available option can be selected
* Only one radio option can be active
* Result is displayed
* Disabled option cannot be selected

Web Tables

* Add button works
* Required fields are validated
* New record appears in table
* Existing record can be edited
* Edited data is displayed
* Existing record can be deleted
* Search returns matching records
* Search with no results behaves correctly

Practice Form

* First Name is required
* Last Name is required
* Email validation works
* Gender selection works
* Mobile number validation works
* Date picker works
* Subjects can be entered
* Hobbies can be selected
* Address accepts text
* State and city can be selected
* Successful submission displays entered data

Alerts

* Simple alert opens
* Alert can be confirmed
* Confirmation alert works
* Cancel action works
* Result is displayed correctly

Browser Windows

* New tab opens
* New window opens
* New content is displayed
* User can return to the original page
