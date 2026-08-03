# Requirements Traceability Matrix

The RTM confirms that priority requirements are represented in user stories and validated through UAT.

| Requirement | Related Story | Acceptance / Rule | UAT Scenario | Status |
|---|---|---|---|---|
| FR-01 Authenticate employees | — | Authorized access only | UAT-01, UAT-02 | Planned |
| FR-02 Select category | US-01 | Active categories only | UAT-03 | Planned |
| FR-03 Required request fields | US-01 | Mandatory-field validation | UAT-04 | Planned |
| FR-04 Unique request number | US-01 | BR-01 | UAT-03 | Planned |
| FR-05 Route resolver group | US-01 | Category routing rule | UAT-05 | Planned |
| FR-06 Assign resolver | US-03 | Authorized assignment | UAT-06, UAT-07 | Planned |
| FR-07 Update status/comments | US-04, US-05 | BR-04 to BR-07 | UAT-08 to UAT-11 | Planned |
| FR-08 View submitted requests | US-02 | Permitted records only | UAT-12, UAT-13 | Planned |
| FR-09 Retain history | US-03, US-04 | User and timestamp retained | UAT-14 | Planned |
| FR-10 Send notifications | US-01, US-04 | Event-based notification | UAT-15 | Planned |
| FR-11 Search and filter | US-02 | Status and date filters | UAT-16 | Planned |
| FR-12 Manager dashboard | US-06 | Approved KPI definitions | UAT-17, UAT-18 | Planned |
| NFR-02 Role-based access | US-02, US-05 | BR-04, BR-08 | UAT-02, UAT-13 | Planned |
| NFR-07 Safe error messages | — | No sensitive technical details | UAT-19 | Planned |

## Traceability Review

- Every Must-priority functional requirement must have at least one UAT scenario.
- Failed or deferred scenarios must retain links to the related requirement.
- Requirement changes must trigger RTM and test-impact review.
