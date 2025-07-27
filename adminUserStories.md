1.Title: As an admin, I want to log into the portal with my username and password, so that I can securely manage the platform.

Acceptance Criteria:

Login form accepts valid credentials

User is authenticated and granted appropriate permissions

Invalid login attempts show an error message

Priority: High Story Points: 3 Notes:

Consider multi-factor authentication as a future enhancement




2.Title: As an admin, I want to log out of the portal, so that system access is protected when I’m away.

Acceptance Criteria:

Logout button is accessible from all admin screens

Session terminates upon logout

User is redirected to login page

Priority: High Story Points: 2 Notes:

Auto logout after inactivity can be added later



3.Title: As an admin, I want to add doctors to the portal, so that they can be visible and active on the platform.

Acceptance Criteria:

Form allows entry of doctor details

Doctor is saved to the database

Confirmation is shown after successful creation

Priority: High Story Points: 3 Notes:

Check for duplicate profiles before saving



4.Title: As an admin, I want to delete a doctor's profile from the portal, so that outdated or incorrect records are removed.

Acceptance Criteria:

Admin can locate doctor profile

Delete option is available

Profile is permanently removed with confirmation

Priority: Medium Story Points: 2 Notes:

Consider soft-delete for data recovery




5.Title: As an admin, I want to run a stored procedure in MySQL CLI to get monthly appointment statistics, so that I can track system usage.

Acceptance Criteria:

Stored procedure exists in the database

Procedure returns number of appointments per month

Output is logged or displayed clearly

Priority: Medium Story Points: 4 Notes:

Ensure procedure is optimized and handles edge cases (e.g. months with zero appointments)
