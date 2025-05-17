## Test Case ID: PROF-0003_edit_profile_invalid_data
### Title: Edit Profile with Invalid Data
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                                 | Expected Behavior                            |
|---|--------------------------------------|----------------------------------------------|
| 1 | Go to profile page                   | Profile is displayed                         |
| 2 | Tap 'Edit Profile'                   | Fields become editable                       |
| 3 | Enter invalid values (e.g., symbols in name or empty email) | Validation errors shown        |
| 4 | Tap 'Save Changes'                   | Save is blocked; error messages remain       |
| 5 | Correct input and retry              | Profile saves only after valid correction    |



**Post-conditions**:
- Feature performs the expected action.
