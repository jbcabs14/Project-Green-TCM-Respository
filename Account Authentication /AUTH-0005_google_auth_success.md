## Test Case ID: AUTH-0005_google_auth_success
### Title: Google Sign-In Success
**Summary**: Verify that Google Sign-In works correctly.

**Preconditions**: Google account is signed in on the device.

**Scenario 1**

| # | Step | Expected Behavior |
|---|------|--------------------|
| 1 | Launch the application. | Verify that login options are displayed. |
| 2 | Tap on 'Sign in with Google'. | Verify that Google account selector appears. |
| 3 | Choose a valid account. | Verify that the user is logged in. |
| 4 | Wait for redirection. | Verify that the user is taken to the Main Dashboard. |


**Post-conditions**:
- User is authenticated via Google and redirected successfully.
