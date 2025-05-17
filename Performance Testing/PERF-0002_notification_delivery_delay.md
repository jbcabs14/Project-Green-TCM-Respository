## Test Case ID: PERF-0002_notification_delivery_delay
### Title: Notification Delivery Delay
**Summary**: Verify functionality works as expected.

**Preconditions**: Relevant precondition setup is completed.

**Scenario 1**

| # | Step                                  | Expected Behavior                                  |
|---|---------------------------------------|----------------------------------------------------|
| 1 | Trigger an event-based notification   | Backend sends the message                          |
| 2 | Monitor delivery time on device       | Message appears within 5–10 seconds                |
| 3 | Analyze multiple cases                | Delivery is consistent across network types        |


**Post-conditions**:
- Feature performs the expected action.
