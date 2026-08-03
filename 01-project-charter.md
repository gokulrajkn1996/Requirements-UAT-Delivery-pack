# Project Charter

## Business Problem

Employees submit service requests through shared email inboxes. Requests may be incomplete, duplicated or assigned manually. Employees cannot reliably view progress, and managers lack consistent data on volume, backlog, ageing and service performance.

## Project Objective

Implement a centralized portal that enables employees to submit complete requests, routes work to the appropriate team, supports status tracking and produces consistent operational reporting.

## In Scope

- Authenticated employee access
- Request submission and validation
- Request categories and priorities
- Assignment to resolver groups
- Status, comments and activity history
- Employee notifications
- Search and filtering
- Service-level and backlog reporting

## Out of Scope

- Public or customer-facing access
- Automated password reset
- Procurement approval workflow
- Integration with payroll
- Mobile-native application
- AI-based request classification

## Stakeholders

| Stakeholder | Responsibility / Need |
|---|---|
| Employees | Submit requests and view progress |
| Service Desk Agents | Review, assign, update and resolve requests |
| Resolver Groups | Complete specialized work |
| Service Desk Manager | Monitor backlog, ageing and service performance |
| Information Security | Confirm access and data-handling controls |
| IT Application Team | Build, test, deploy and support the solution |

## Assumptions

- Employees authenticate using an existing corporate identity.
- Request categories and resolver groups are approved before configuration.
- Email notifications are available.
- Business users are available for requirements validation and UAT.

## Constraints

- Initial release must use the organization's existing technology stack.
- Sensitive information must not be included in email notifications.
- The first release must be delivered within the agreed project window.

## Success Criteria

- Required request information is captured consistently.
- Employees can view the current status without contacting the Service Desk.
- Every request has an owner, status and activity history.
- Managers can report on volume, backlog, ageing and resolution performance.
- Must-have requirements pass UAT with no critical defects open.
