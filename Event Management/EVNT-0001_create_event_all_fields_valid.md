## Test Case ID: EVNT-0001_create_event_all_fields_valid
### Title: Create Event with All Valid Fields
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                            | Expected Behavior                                |
|---|---------------------------------|--------------------------------------------------|
| 1 | Tap the Pencil icon at the bottom right to create event| 'Create Event' form opens                        |
| 2 | Fill in title, description, time, date, location | Inputs are accepted and validated         |
| 3 | (Optional) Tick 'Flag as hazardous' | Checkbox is marked                         |
| 4 | Tap image field and select photo| Image preview is shown below                    |
| 5 | Tap 'Post'                      | Event is created, success message appears        |
| 6 | Redirect to event list or detail | Event is visible in feed                        |



**Post-conditions**:
- Feature performs the expected action.
