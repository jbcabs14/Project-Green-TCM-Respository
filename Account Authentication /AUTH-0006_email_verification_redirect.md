## Test Case ID: AUTH-0006_email_verification_redirect
### Title: Redirect to Email Verification
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                                               | Expected Behavior                             |
| - | -------------------------------------------------- | --------------------------------------------- |
| 1 | Complete sign-up with a new valid account.         | App prompts email verification.               |
| 2 | Redirect to "Verify Your Email" screen.            | Success message and retry instructions shown. |
| 3 | User closes and reopens the app without verifying. | App redirects back to "Verify Your Email".    |
| 4 | After email is verified manually, relaunch app.    | User is now redirected to Main Dashboard.     |



**Post-conditions**:
- Feature performs the expected action.
