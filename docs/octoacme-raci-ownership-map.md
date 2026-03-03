# OctoAcme RACI Ownership Map

## Purpose
Provide a lightweight cross-functional ownership reference for key project lifecycle activities. Use this map to clarify accountability and avoid gaps or duplication of effort across roles.

## RACI Key
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome, final decision-maker |
| **C** | Consulted — provides input before/during |
| **I** | Informed — kept up to date on outcomes |

## Roles
| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developers |
| QA | QA Engineer |
| UX | UX Designer |
| BA | Business Analyst |
| TW | Technical Writer |

---

## Initiation

| Activity | PM | PdM | Dev | QA | UX | BA | TW |
|---|---|---|---|---|---|---|---|
| Define problem statement | C | A/R | I | I | C | R | I |
| Identify stakeholders & champions | A/R | C | I | I | I | C | I |
| Draft project one-pager | R | A | I | I | I | C | I |
| Define success metrics | C | A/R | I | I | C | C | I |
| Go/no-go decision | A | C | I | I | I | I | I |

---

## Planning

| Activity | PM | PdM | Dev | QA | UX | BA | TW |
|---|---|---|---|---|---|---|---|
| Define scope and milestones | A/R | C | C | C | C | C | I |
| Write and review requirements | C | A | C | C | C | R | I |
| Establish acceptance criteria | C | A | C | R | C | R | I |
| Create test strategy & test plan | I | C | C | A/R | I | C | I |
| Define UX flows and wireframes | I | C | C | I | A/R | C | I |
| Identify risks and dependencies | A/R | C | C | C | C | C | I |
| Estimate effort | C | I | A/R | C | C | I | I |
| Create documentation plan | I | C | I | I | I | I | A/R |

---

## Execution

| Activity | PM | PdM | Dev | QA | UX | BA | TW |
|---|---|---|---|---|---|---|---|
| Implement features | I | I | A/R | I | I | I | I |
| Design review & iteration | I | C | C | I | A/R | I | I |
| Write and run automated tests | I | I | C | A/R | I | I | I |
| Exploratory / manual testing | I | I | I | A/R | I | I | I |
| Defect triage and resolution | C | I | R | A | I | I | I |
| Track progress and blockers | A/R | C | C | C | C | C | C |
| Update process documentation | I | I | C | I | I | I | A/R |

---

## Release

| Activity | PM | PdM | Dev | QA | UX | BA | TW |
|---|---|---|---|---|---|---|---|
| Release go/no-go decision | A | C | C | R | I | I | I |
| Smoke tests after deploy | I | I | C | A/R | I | I | I |
| Release notes | C | C | C | C | I | I | A/R |
| Stakeholder announcement | R | A | I | I | I | I | C |
| Deploy to production | C | I | A/R | I | I | I | I |
| Post-deploy verification | C | I | R | A/R | I | I | I |

See also: [Quality & Release Readiness Checklist](octoacme-quality-release-readiness-checklist.md) · [Documentation & Change Communication Checklist](octoacme-documentation-change-communication-checklist.md)

---

## Retrospective & Continuous Improvement

| Activity | PM | PdM | Dev | QA | UX | BA | TW |
|---|---|---|---|---|---|---|---|
| Facilitate retrospective | A/R | C | C | C | C | C | C |
| Capture action items | R | C | C | C | C | C | C |
| Update process documentation | R | C | C | C | C | C | A/R |
| Track action item completion | A/R | I | I | I | I | I | I |

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Quality & Release Readiness Checklist](octoacme-quality-release-readiness-checklist.md)
- [Documentation & Change Communication Checklist](octoacme-documentation-change-communication-checklist.md)
- [Design Handoff Checklist](octoacme-design-handoff-checklist.md)
