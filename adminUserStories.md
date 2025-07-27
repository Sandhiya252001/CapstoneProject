Title: As an admin, I want to log into the portal with my username and password, so that I can securely manage the platform.

Acceptance Criteria:

Login form validates credentials

Successful login grants access to admin dashboard

Invalid credentials return appropriate error messages

Priority: High Story Points: 3 Notes:

Consider implementing multi-factor authentication for enhanced security

Title: As an admin, I want to log out of the portal, so that unauthorized users cannot access the system.

Acceptance Criteria:

Logout option is available from all pages

Session ends and user is redirected to login screen

No access to previous pages without reauthentication

Priority: High Story Points: 2 Notes:

Support automatic logout after a set period of inactivity

Title: As an admin, I want to add doctors to the portal, so that they can be listed and available for patient appointments.

Acceptance Criteria:

Form to input doctor information is functional

Doctor profile is saved and displayed correctly

Confirmation or error message is shown after submission

Priority: High Story Points: 3 Notes:

Ensure unique identification for each doctor

Title: As an admin, I want to delete a doctor’s profile from the portal, so that I can remove inactive or incorrect records.

Acceptance Criteria:

Admin can search and select the doctor to delete

System prompts for confirmation before deletion

Doctor profile is removed and related data cleaned up

Priority: Medium Story Points: 2 Notes:

Soft-delete mechanism recommended for audit purposes

Title: As an admin, I want to run a stored procedure in MySQL CLI to view the number of appointments per month, so that I can monitor usage statistics.

Acceptance Criteria:

Stored procedure is accessible via MySQL CLI

Procedure returns accurate monthly counts

Output is easy to read and export

Priority: Medium Story Points: 4 Notes:

Procedure should handle months with no appointments gracefully
