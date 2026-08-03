# User Stories and Acceptance Criteria

## US-01 — Submit a Request

**As an** employee, **I want** to submit a service request **so that** I can receive help from the correct team.

### Acceptance Criteria

- Title, description, category and impact are mandatory.
- The employee can select only active categories.
- Successful submission generates a unique request number.
- The request is routed to the resolver group defined for the category.
- The employee sees a confirmation and receives a notification.

## US-02 — View My Requests

**As an** employee, **I want** to view my requests **so that** I can understand their current status.

### Acceptance Criteria

- The employee sees only requests they submitted or are permitted to view.
- The list displays request number, title, status, priority and last update.
- The employee can filter by status and date.
- Selecting a request displays its permitted history and comments.

## US-03 — Assign a Request

**As a** Service Desk Agent, **I want** to assign a request **so that** responsibility is clear.

### Acceptance Criteria

- Only authorized agents can change resolver group or assignee.
- Assignee choices are limited to members of the selected resolver group.
- The assignment change records user and timestamp.
- The new assignee is notified.

## US-04 — Update Status

**As a** resolver, **I want** to update request status **so that** progress is visible.

### Acceptance Criteria

- Only valid status transitions are available.
- A reason is required when placing a request on hold.
- Resolution summary is required before status becomes `Resolved`.
- Every transition is recorded in history.

## US-05 — Add a Comment

**As an** employee or resolver, **I want** to add an appropriate comment **so that** information is shared within the request.

### Acceptance Criteria

- A blank comment cannot be submitted.
- The comment records author and timestamp.
- Internal comments are not visible to employees.
- Employee-visible comments trigger a notification when applicable.

## US-06 — Monitor Backlog

**As a** Service Desk Manager, **I want** a backlog dashboard **so that** I can identify ageing and service risks.

### Acceptance Criteria

- Dashboard KPIs use approved definitions.
- Results can be filtered by period, category, priority and resolver group.
- Ageing is calculated from creation to closure or the current date.
- Requests exceeding the service target are clearly identified.
