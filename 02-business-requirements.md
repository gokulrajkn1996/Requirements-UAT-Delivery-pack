# Business Requirements

## Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The portal shall authenticate employees using corporate credentials. | Must |
| FR-02 | Employees shall create a request using an approved category and subcategory. | Must |
| FR-03 | The portal shall require a title, description, category and impact. | Must |
| FR-04 | The portal shall assign a unique request number. | Must |
| FR-05 | The portal shall route requests to a resolver group using approved category rules. | Must |
| FR-06 | Authorized agents shall assign a request to an individual resolver. | Must |
| FR-07 | Authorized users shall update request status and add comments. | Must |
| FR-08 | Employees shall view their submitted requests and current status. | Must |
| FR-09 | The portal shall retain user, timestamp and status history. | Must |
| FR-10 | The portal shall notify employees when a request is created, updated or resolved. | Should |
| FR-11 | Employees and agents shall search and filter applicable requests. | Should |
| FR-12 | Managers shall view backlog, ageing, volume and resolution KPIs. | Should |
| FR-13 | Authorized agents shall reopen an eligible resolved request. | Could |
| FR-14 | Employees shall attach approved file types within the size limit. | Could |

## Non-Functional Requirements

| ID | Requirement |
|---|---|
| NFR-01 | Standard portal pages should load within three seconds under normal use. |
| NFR-02 | Users shall only access requests permitted by their role. |
| NFR-03 | Data shall be encrypted in transit. |
| NFR-04 | The portal shall meet applicable corporate accessibility standards. |
| NFR-05 | Request and audit history shall be retained according to policy. |
| NFR-06 | The portal shall support current approved versions of major corporate browsers. |
| NFR-07 | Error messages shall explain the issue without exposing sensitive system details. |

## Reporting Requirements

- Requests created by period and category
- Open backlog by status, priority and resolver group
- Average request age
- Average resolution time
- Requests approaching or exceeding service target
- Reopened requests
- First-contact resolution rate, when applicable

## Data Requirements

- Request number
- Requester and department
- Category and subcategory
- Title and description
- Impact, urgency and calculated priority
- Resolver group and assignee
- Status, dates and activity history
- Resolution summary and closure date
