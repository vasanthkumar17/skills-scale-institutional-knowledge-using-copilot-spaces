# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions
- **Product Manager (PdM):** Reviews feature specs and acceptance criteria; surfaces technical constraints and trade-offs early in planning.
- **Project Manager (PM):** Communicates progress, flags blockers, and participates in standups and sprint reviews.
- **QA Engineer:** Collaborates on testability, shares implementation context, and verifies fixes together.
- **UX Designer:** Reviews design specs for feasibility during handoff; raises technical constraints that may affect user experience. See also: [Design Handoff Checklist](octoacme-design-handoff-checklist.md).
- **Technical Writer:** Provides technical accuracy reviews for user-facing and process documentation.
- **Business Analyst:** Clarifies ambiguous requirements and edge cases during implementation.

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions
- **Project Manager (PM):** Aligns weekly on scope, schedule, and priorities; escalates trade-offs and decisions that affect delivery commitments.
- **Developers:** Defines and reviews acceptance criteria; gathers input on technical feasibility and effort estimates.
- **UX Designer:** Partners to validate user flows, review research findings, and align designs with product vision.
- **QA Engineer:** Reviews acceptance criteria together to ensure testability; reviews quality status before release go/no-go.
- **Technical Writer:** Aligns on user-facing documentation scope and release notes for each release.
- **Business Analyst:** Collaborates to translate business goals into well-defined, prioritized requirements.

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions
- **Product Manager (PdM):** Aligns weekly on priorities and scope; surfaces schedule and resource constraints that affect roadmap decisions.
- **Developers:** Removes blockers, tracks progress, and ensures the team has clear priorities and timelines.
- **QA Engineer:** Tracks test timelines and quality status; incorporates go/no-go input into release decisions.
- **Technical Writer:** Tracks documentation milestones and ensures doc readiness is part of the release checklist.
- **UX Designer:** Coordinates design milestones and flags scope changes arising from design work.
- **Business Analyst:** Manages requirement change impact on scope and schedule.

---

## UX Designer

### Role Summary
UX Designers create and refine user experiences that are intuitive, accessible, and aligned with product goals. They advocate for user needs throughout the project lifecycle and translate research insights into actionable designs.

### Responsibilities
- Create wireframes, prototypes, and design assets
- Conduct user research and usability testing
- Define user flows and interaction patterns
- Maintain design systems and component libraries
- Review implementations for design fidelity

### Goals
- Deliver user experiences that are intuitive and accessible
- Reduce usability issues before they reach production
- Ensure consistency across product surfaces

### Typical Communication
- Design reviews and prototype walkthroughs with Product Manager and Developers
- Usability test findings and recommendations
- Design handoff notes and annotations

### Interactions
- **Product Manager (PdM):** Collaborates to define user flows, validate requirements against user needs, and align designs with product vision and success metrics.
- **Developers:** Reviews designs for technical feasibility; provides annotated specs and assets during handoff; clarifies interaction details during implementation. See also: [Design Handoff Checklist](octoacme-design-handoff-checklist.md).
- **Business Analyst:** Works together to ensure user flows are grounded in validated requirements and that edge cases from business rules are reflected in designs.
- **QA Engineer:** Aligns on acceptance criteria for UX, including accessibility and visual regression, to ensure implementations meet design intent.
- **Project Manager (PM):** Coordinates design milestones and flags any scope changes that arise from usability testing.

---

## QA Engineer

### Role Summary
QA Engineers validate software quality by defining test strategies, writing test cases, and executing manual and automated tests. They own the test plan and release sign-off gate on behalf of quality.

### Responsibilities
- Write and maintain test cases derived from acceptance criteria
- Build and run automated test suites (unit, integration, end-to-end)
- Execute exploratory and regression tests before releases
- Report, triage, and verify defects
- Participate in Definition of Done reviews

### Goals
- Prevent quality issues from reaching production
- Increase test coverage and automation ratio
- Shorten feedback loops between development and quality validation

### Typical Communication
- Test plan documents and test result summaries
- Defect reports with reproducible steps
- Go/no-go sign-off at release gates

### Interactions
- **Developers:** Collaborates to understand implementation details, shares early test environments, and verifies fixes together. Reviews PRs for testability and acceptance criteria coverage.
- **Product Manager (PdM):** Aligns on acceptance criteria and success metrics to ensure tests validate real user value, not just functional correctness.
- **Project Manager (PM):** Coordinates test timelines, communicates quality status for release readiness, and escalates blockers. See also: [Quality & Release Readiness Checklist](octoacme-quality-release-readiness-checklist.md).
- **Business Analyst:** Reviews requirements and edge cases to ensure test coverage spans all business scenarios.
- **Technical Writer:** Coordinates to ensure release notes accurately describe resolved defects and known issues.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation that helps end users, operators, and internal teams understand and use OctoAcme products and processes effectively.

### Responsibilities
- Write and update user guides, process docs, API references, and release notes
- Collaborate with Developers and PMs to capture workflows and changes
- Review upcoming releases to identify documentation needs
- Maintain documentation accuracy across sprints and releases

### Goals
- Ensure documentation is accurate, discoverable, and up to date
- Reduce support burden by enabling self-service through clear docs
- Align documentation cadence with release cadence

### Typical Communication
- Documentation drafts for review by subject-matter experts (SMEs)
- Change requests and doc review comments in PRs
- Release notes coordinated with PM and QA

### Interactions
- **Developers:** Partners to capture technical details, review accuracy of API and process docs, and receive early heads-up on changes that require documentation updates.
- **Product Manager (PdM):** Aligns on documentation scope for each release; collaborates on user-facing release notes and stakeholder announcements.
- **QA Engineer:** Coordinates to ensure release notes correctly reflect fixed defects, known issues, and test coverage notes.
- **Project Manager (PM):** Tracks documentation milestones alongside project schedule; flags doc debt that could affect release readiness. See also: [Documentation & Change Communication Checklist](octoacme-documentation-change-communication-checklist.md).
- **Business Analyst:** Reviews process documentation to confirm business rules and requirements are accurately described.

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and the delivery team by gathering, clarifying, and documenting requirements. They ensure the team understands the "why" behind requests and that acceptance criteria are unambiguous.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Analyze existing business workflows and identify improvement opportunities
- Define and review acceptance criteria with PdM, QA, and Developers
- Maintain requirement traceability through the project lifecycle
- Facilitate requirement walkthroughs and sign-offs with stakeholders

### Goals
- Ensure requirements are clear, testable, and aligned with business goals
- Reduce rework caused by ambiguous or missing requirements
- Improve stakeholder confidence through transparent requirement tracking

### Typical Communication
- Requirements documents and user story definitions
- Acceptance criteria written in collaboration with PdM and QA
- Stakeholder sign-off summaries and change impact assessments

### Interactions
- **Product Manager (PdM):** Works closely to translate business goals and customer insights into prioritized, well-defined requirements; helps maintain backlog quality.
- **Developers:** Partners to ensure requirements are technically feasible and unambiguous; clarifies edge cases discovered during implementation.
- **QA Engineer:** Collaborates on acceptance criteria and edge cases to ensure requirements are testable and that test coverage is comprehensive.
- **Technical Writer:** Reviews requirements and process documentation together to ensure internal docs accurately reflect agreed-upon business rules and workflows.
- **Project Manager (PM):** Flags requirement changes that affect scope, schedule, or resources; supports impact analysis for change requests.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [RACI Ownership Map](octoacme-raci-ownership-map.md) for a cross-functional view of who owns each lifecycle activity.

