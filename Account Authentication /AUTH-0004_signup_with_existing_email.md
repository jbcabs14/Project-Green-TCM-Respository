## Test Case ID: AUTH-0004_signup_with_existing_email
### Title: Sign Up with Existing Email
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                                              | Expected Behavior                                       |
| - | ------------------------------------------------- | ------------------------------------------------------- |
| 1 | Go to the Sign-Up screen.                         | Sign-Up form appears.                                   |
| 2 | Enter an email that already exists in the system. | Email input is accepted.                                |
| 3 | Fill in other valid fields and submit.            | Attempt to create account is initiated.                 |
| 4 | Tap the "Create My Account" button.               | Error message like **“Email already in use”** is shown. |
| 5 | Stay on the Sign-Up screen.                       | User is not redirected. Form remains visible.           |



**Post-conditions**:
- Feature performs the expected action.
