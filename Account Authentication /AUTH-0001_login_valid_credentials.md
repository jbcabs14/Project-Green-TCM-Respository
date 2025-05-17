## Test Case ID: AUTH-0001_login_valid_credentials
### Title: Successful Login with Valid Credentials
**Summary**: Verify that user can log in using valid credentials.

**Preconditions**: User must already be registered and email verified.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|--------------------|
| 1 | Launch the application. | Verify that the login screen is displayed. |
| 2 | Enter valid email (e.g. user@example.com). | Verify that the email field is populated. |
| 3 | Enter valid password. | Verify that the password field is populated. |
| 4 | Tap the 'Sign In' button. | Verify that the user is redirected to the Main Dashboard. |


**Post-conditions**:
- User is redirected to the dashboard and session is active.
