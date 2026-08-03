# User Acceptance Testing Plan

## Purpose

Validate that the Employee Service Request Portal supports approved business processes and is ready for business use.

## UAT Scope

- Authentication and role access
- Request submission and validation
- Routing and assignment
- Status transitions and comments
- Employee request visibility
- Notifications
- Search, filters and dashboards
- Audit and history requirements

## Roles

| Role | Responsibility |
|---|---|
| Business Sponsor | Approves UAT outcome and business readiness |
| Business Analyst | Coordinates scenarios, traceability and triage |
| Business Testers | Execute scenarios and record evidence |
| QA Lead | Confirms environment and supports defect reproduction |
| Development Team | Investigates and fixes accepted defects |
| Project Manager | Tracks schedule, risks and readiness |

## Entry Criteria

- Requirements and acceptance criteria are approved.
- System and integration testing are complete.
- UAT environment and test accounts are available.
- Test data is prepared.
- Critical system-test defects are closed.
- UAT scenarios are reviewed with business testers.

## Test Data

- Standard employee
- Service Desk Agent
- Resolver in two different groups
- Service Desk Manager
- Active and inactive categories
- New, assigned, on-hold, resolved and closed requests

## Execution Approach

1. Conduct tester orientation.
2. Execute Must-priority scenarios first.
3. Record Pass, Fail, Blocked or Not Run.
4. Attach evidence for each result.
5. Log failed outcomes as defects with clear reproduction steps.
6. Hold daily triage during active execution.
7. Retest fixes and complete targeted regression.

## Exit Criteria

- All Must-priority scenarios are executed.
- No Severity 1 or Severity 2 defects remain open.
- Accepted lower-severity defects have owners and target dates.
- RTM is updated with final results.
- Business Sponsor signs off on UAT and readiness.

## UAT Sign-Off

The sign-off summary should include scope executed, pass rate, outstanding defects, accepted risks, known workarounds and final recommendation.
