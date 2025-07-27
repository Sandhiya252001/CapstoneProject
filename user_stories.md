# User Stories

**Title:**
_As a [Admin], I want [to log into the portal with my username and password], so that [I can securely manage the platform]._

**Acceptance Criteria:**
1. [Login form validates credentials]
2. [Successful login grants access to admin dashboard]
3. [Invalid credentials return appropriate error messages]

**Priority:** [High]
**Story Points:** [3]
**Notes:**
- [Consider implementing multi-factor authentication for enhanced security]
  
**Title:**
_As a [Admin], I want [ to log out of the portal], so that [unauthorized users cannot access the system]._

**Acceptance Criteria:**
1. [Logout option is available from all pages]
2. [Session ends and user is redirected to login screen]
3. [No access to previous pages without reauthentication]

**Priority:** [High]
**Story Points:** [2]
**Notes:**
- [Support automatic logout after a set period of inactivity]

**Title:**
_As a [Admin], I want [to delete a doctor’s profile from the portal], so that [ I can remove inactive or incorrect records]._

**Acceptance Criteria:**
1. [Admin can search and select the doctor to delete]
2. [System prompts for confirmation before deletion]
3. [Doctor profile is removed and related data cleaned up]

**Priority:** [Medium]
**Story Points:** [2]
**Notes:**
- [Soft-delete mechanism recommended for audit purposes]

**Title:**
_As a [Admin], I want [to run a stored procedure in MySQL CLI to view the number of appointments per month], so that [I can monitor usage statistics]._

**Acceptance Criteria:**
1. [Stored procedure is accessible via MySQL CLI]
2. [Procedure returns accurate monthly counts]
3. [Output is easy to read and export]

**Priority:** [Medium]
**Story Points:** [4]
**Notes:**
- [Procedure should handle months with no appointments gracefully]


  **Title:**
_As a [Doctor], I want [to log into the portal], so that [I can manage my appointments]._

**Acceptance Criteria:**
1. [Login form accepts valid credentials]
2. [Successful login grants access to appointment dashboard]
3. [Error message is shown for invalid login attempts]

**Priority:** [High]
**Story Points:** [2]
**Notes:**
- [Consider two-factor authentication for added security]
  

**Title:**
_As a [Doctor], I want [to log out of the portal], so that [I can protect my data]._

**Acceptance Criteria:**
1. [Logout button is accessible from all pages]
2. [Session ends immediately upon log]
3. [User is redirected to homepage or login page]

**Priority:** [Medium]
**Story Points:** [1]
**Notes:**
- [Enable auto logout on inactivity]


**Title:**
_As a [Doctor], I want [to view my appointment calendar], so that [I can stay organized]._

**Acceptance Criteria:**
1. [Calendar displays all upcoming appointments]
2. [Time, patient name, and duration are clearly shown]
3. [Navigation between days/weeks/months is seamless]

**Priority:** [High]
**Story Points:** [3]
**Notes:**
- [Include daily, weekly, and monthly views]

**Title:**
_As a [Doctor], I want [to mark my unavailability], so that [patients can only book available slots]._

**Acceptance Criteria:**
1. [Option to set unavailable dates and times]
2. [Bookings are disabled for marked slots]
3. [Patients receive real-time feedback on availability]

**Priority:** [High]
**Story Points:** [3]
**Notes:**
- [Allow recurring unavailability (e.g. every weekend)]

**Title:**
_As a [Doctor], I want [to update my profile with specialization and contact information], so that [patients have up-to-date details]._

**Acceptance Criteria:**
1. [Editable form for profile information]
2. [Changes are saved and reflected instantly]
3. [Validation for phone number and email formats]

**Priority:** [Medium]
**Story Points:** [2]
**Notes:**
- [Profile updates should be audit-logged]

**Title:**
_As a [Docotor], I want [to view the patient details for my upcoming appointments], so that [I can be prepared]._

**Acceptance Criteria:**
1. [Patient name, reason for visit, and past notes are visible]
2. [Accessible directly from the appointment calendar]
3. [Information is protected and restricted to scheduled doctors]

**Priority:** [High]
**Story Points:** [3]
**Notes:**
- [Ensure compliance with data privacy regulations]

**Title:**
_As a [Patient], I want [to view a list of doctors without logging in], so that [I can explore my options before registering]._

**Acceptance Criteria:**
1. [Doctor list is accessible from the homepage]
2. [Doctor profiles display key information (name, specialty, availability)]
3. [No login prompt appears while browsing]

**Priority:** [High]
**Story Points:** [2]
**Notes:**
- [Include filters for specialization and location]
  

**Title:**
_As a [Patient], I want [to sign up using my email and password], so that [I can book appointments through the portal]._

**Acceptance Criteria:**
1. [Signup form accepts valid email and password]
2. [Email verification or OTP is sent to confirm identity]
3. [Account is created and user is redirected to dashboard]

**Priority:** [High]
**Story Points:** [3]
**Notes:**
- [Validate password strength during registration]


**Title:**
_As a [Patient], I want [to log into the portal], so that [I can manage my bookings]._

**Acceptance Criteria:**
1. [1.Login form accepts registered credentials]
2. [Successful login redirects to dashboard]
3. [Invalid attempts show helpful error messages]

**Priority:** [High]
**Story Points:** [2]
**Notes:**
- [Include ‘Forgot Password’ option for recovery]

**Title:**
_As a [Patient], I want [to log out of the portal], so that [I can secure my account]._

**Acceptance Criteria:**
1. [Logout is available on all screens]
2. [Session terminates upon logout]
3. [User is redirected to the homepage or login screen]

**Priority:** [Medium]
**Story Points:** [1]
**Notes:**
- [Implement automatic logout after a period of inactivityto run a stored procedure in MySQL CLI to view the number of appointments per month]

**Title:**
_As a [Patient], I want [to book an hour-long appointment with a doctor after logging in], so that [I can consult with them.]._

**Acceptance Criteria:**
1. [Appointment booking form allows selection of time slot]
2. [Appointment is confirmed and added to patient’s schedule]
3. [Confirmation notification is sent]

**Priority:** [High]
**Story Points:** [4]
**Notes:**
- [Avoid double-booking and display doctor’s availability clearly]

**Title:**
_As a [Patient], I want [to view my upcoming appointments], so that [I can prepare accordingly]._

**Acceptance Criteria:**
1. [List of scheduled appointments is visible on the dashboard]
2. [Appointment details (doctor, date, time) are displayed clearly]
3. [Option to cancel or reschedule is provided]

**Priority:** [Medium]
**Story Points:** [3]
**Notes:**
- [Highlight appointments occurring within the next 24 hours]

  
