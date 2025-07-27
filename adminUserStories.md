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
_As a [Admin], I want [I want to add doctors to the portal], so that [they can be listed and available for patient appointments]._

**Acceptance Criteria:**
1. [Form to input doctor information is functional]
2. [Doctor profile is saved and displayed correctly]
3. [Confirmation or error message is shown after submission]

**Priority:** [High]
**Story Points:** [3]
**Notes:**
- [Ensure unique identification for each doctor]


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

