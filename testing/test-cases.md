# Test Cases

| Test Case ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-01 | Add a valid task | Task should be added successfully | Task was added successfully | Pass |
| TC-02 | Submit an empty task | Empty task should not be added | Empty task was not added | Pass |
| TC-03 | Add multiple tasks | Multiple tasks should be displayed correctly | Multiple tasks were displayed correctly | Pass |
| TC-04 | Select different task priorities | Selected priority should be displayed with the task | Selected priority was displayed correctly | Pass |
| TC-05 | Add a task with time | Selected time should be displayed with the task | Task time was displayed correctly | Pass |
| TC-06 | Mark a pending task as completed | Task status should change to completed | Task was marked as completed successfully | Pass |
| TC-07 | Mark a completed task as pending | Task status should change back to pending | Task status changed back to pending successfully | Pass |
| TC-08 | Delete a task | Selected task should be removed | Selected task was deleted successfully | Pass |
| TC-09 | Filter tasks by All | All tasks should be displayed | All tasks were displayed correctly | Pass |
| TC-10 | Filter tasks by Pending | Only pending tasks should be displayed | Only pending tasks were displayed | Pass |
| TC-11 | Filter tasks by Done | Only completed tasks should be displayed | Only completed tasks were displayed | Pass |
| TC-12 | Refresh the page after adding tasks | Stored tasks should remain available | Tasks remained available after refreshing the page | Pass |
| TC-13 | Complete multiple tasks | Statistics should update according to completed tasks | Completed and pending statistics were updated correctly | Pass |
| TC-14 | Delete a task after filtering | Selected task should be removed correctly | Selected task was removed successfully | Pass |
| TC-15 | Enter special characters in task title | Task title should be displayed safely | Special characters were displayed safely | Pass |
