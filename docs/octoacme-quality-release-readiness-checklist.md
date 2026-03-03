# OctoAcme Quality & Release Readiness Checklist

## Purpose
Provide a reusable checklist to confirm that quality gates and release prerequisites are met before deploying to production. Copy this checklist into your project repo and update it per release.

## Roles Referenced
| Abbreviation | Role |
|---|---|
| Dev | Developers |
| QA | QA Engineer |
| PM | Project Manager |
| PdM | Product Manager |

See [Roles and Personas](octoacme-roles-and-personas.md) for full descriptions and [RACI Ownership Map](octoacme-raci-ownership-map.md) for lifecycle activity ownership.

---

## Test Planning (Owner: QA, Consulted: Dev, PdM)
- [ ] Test plan created and reviewed by QA and PdM
- [ ] Acceptance criteria confirmed as testable with PdM and BA
- [ ] Test environments provisioned and validated
- [ ] Test data prepared and anonymized as required

## Development Readiness (Owner: Dev, Consulted: QA)
- [ ] All planned features implemented and PRs merged
- [ ] Unit and integration tests written and passing
- [ ] Code review completed (no unresolved review comments)
- [ ] CI pipeline green (build, lint, security scan)
- [ ] No known blockers or critical open defects

## Quality Validation (Owner: QA)
- [ ] Regression test suite executed and passing
- [ ] Exploratory testing completed for new features
- [ ] Accessibility checks completed (if applicable)
- [ ] Performance / load tests run for affected areas (if applicable)
- [ ] Security / dependency vulnerability scan reviewed

## Smoke Tests (Owner: QA, Supported: Dev)
- [ ] Smoke test cases documented and up to date
- [ ] Smoke tests executed against staging environment
- [ ] All smoke tests passing

## Release Readiness Gate (Owner: PM, Consulted: QA, PdM, Dev)
- [ ] All acceptance criteria verified as met
- [ ] Open defects triaged; P0/P1 issues resolved or risk accepted by PdM
- [ ] Rollback / mitigation plan documented
- [ ] Deployment window confirmed (if needed)
- [ ] On-call / incident response coverage confirmed

## Documentation & Communication (Owner: Technical Writer / PM)
- [ ] Release notes drafted and reviewed
- [ ] User-facing documentation updated
- [ ] Stakeholder announcement drafted

See [Documentation & Change Communication Checklist](octoacme-documentation-change-communication-checklist.md) for the full documentation checklist.

## Go / No-Go Decision (Owner: PM, Accountable: PdM)
- [ ] QA sign-off received
- [ ] PM and PdM alignment confirmed
- [ ] Go/no-go decision documented and communicated to the team

---

## Related Documents
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [RACI Ownership Map](octoacme-raci-ownership-map.md)
- [Documentation & Change Communication Checklist](octoacme-documentation-change-communication-checklist.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
