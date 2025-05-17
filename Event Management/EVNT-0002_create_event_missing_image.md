## Test Case ID: EVNT-0002_create_event_missing_image
### Title: Create Event without Image
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                             | Expected Behavior                          |
|---|----------------------------------|--------------------------------------------|
| 1 | Open Create Event form           | Form loads properly                        |
| 2 | Fill all fields **except image** | Other inputs are accepted                  |
| 3 | Tap 'Post'                       | Error shown: “Image is required”           |
| 4 | Remain on form                   | User prompted to add an image              |



**Post-conditions**:
- Feature performs the expected action.
