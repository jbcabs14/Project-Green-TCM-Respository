## Test Case ID: SECU-0002_authentication_bypass_attempt
### Title: Authentication Bypass Attempt
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                                      | Expected Behavior                                            |
|---|-------------------------------------------|--------------------------------------------------------------|
| 1 | Attempt direct URL navigation to dashboard | Unauthorized users are redirected to login                  |
| 2 | Bypass localStorage/Token manually         | App detects invalid session                                 |
| 3 | Check local state and UI post-attempt      | User is not allowed to access protected routes              |


**Post-conditions**:
- Feature performs the expected action.
