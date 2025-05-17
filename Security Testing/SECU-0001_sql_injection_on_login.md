## Test Case ID: SECU-0001_sql_injection_on_login
### Title: Attempt SQL Injection on Login
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                                     | Expected Behavior                                           |
|---|------------------------------------------|-------------------------------------------------------------|
| 1 | Open login screen                        | Login form is displayed                                    |
| 2 | Enter `' OR 1=1 --` in email or password | Input accepted                                              |
| 3 | Tap 'Sign In'                            | Authentication fails, error message shown                  |
| 4 | Attempt fails to access main dashboard   | Access is denied; user remains on login screen             |



**Post-conditions**:
- Feature performs the expected action.
