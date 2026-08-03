# UAT Test Scenarios

## Access and Security

| ID | Scenario | Expected Result |
|---|---|---|
| UAT-01 | Sign in with a valid employee account. | User reaches the portal with the correct role. |
| UAT-02 | Attempt to view another employee's restricted request. | Access is denied without exposing request information. |

## Request Submission

| ID | Scenario | Expected Result |
|---|---|---|
| UAT-03 | Submit a complete request using an active category. | Unique request is created and routed correctly. |
| UAT-04 | Submit without a mandatory description. | Submission is blocked and description is identified as required. |
| UAT-05 | Submit requests for different categories. | Each request reaches the resolver group defined by its category. |

## Assignment and Processing

| ID | Scenario | Expected Result |
|---|---|---|
| UAT-06 | Agent assigns a resolver from the correct group. | Assignee is updated and history is recorded. |
| UAT-07 | Attempt to assign a user outside the selected group. | Invalid assignee cannot be selected or saved. |
| UAT-08 | Move a request from Assigned to In Progress. | Valid transition saves with user and timestamp. |
| UAT-09 | Place a request On Hold without a reason. | Update is blocked until a reason is entered. |
| UAT-10 | Resolve a request without a resolution summary. | Update is blocked until summary is entered. |
| UAT-11 | Add an internal comment. | Comment is visible to authorized agents but not the employee. |

## Employee Experience

| ID | Scenario | Expected Result |
|---|---|---|
| UAT-12 | Employee opens My Requests. | Only permitted requests appear with current statuses. |
| UAT-13 | Employee opens a request containing internal comments. | Internal comments are not displayed. |
| UAT-14 | Review request activity history. | Authorized viewer sees ordered status, assignment and comment activity. |
| UAT-15 | Create and resolve a request. | Correct notifications are generated without sensitive internal content. |
| UAT-16 | Filter My Requests by status and date. | Results match all selected criteria. |

## Reporting and Errors

| ID | Scenario | Expected Result |
|---|---|---|
| UAT-17 | Filter manager dashboard by resolver group. | KPIs and visuals show only the selected group. |
| UAT-18 | Reconcile backlog and ageing values to source requests. | Dashboard results match approved calculations. |
| UAT-19 | Trigger a controlled application error. | User receives a clear message without sensitive system details. |

## Result Values

- **Pass:** Actual result matches expected result.
- **Fail:** Actual result does not match expected result.
- **Blocked:** Scenario cannot run because of a dependency or defect.
- **Not Run:** Execution has not started.
