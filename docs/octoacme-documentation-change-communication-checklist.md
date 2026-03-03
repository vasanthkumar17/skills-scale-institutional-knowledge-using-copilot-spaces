# OctoAcme Documentation & Change Communication Checklist

## Purpose
Provide a reusable checklist to ensure that documentation and stakeholder communications are complete and accurate before and after each release. Copy this checklist into your project repo and update it per release.

## Roles Referenced
| Abbreviation | Role |
|---|---|
| TW | Technical Writer |
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developers |
| QA | QA Engineer |

See [Roles and Personas](octoacme-roles-and-personas.md) for full descriptions and [RACI Ownership Map](octoacme-raci-ownership-map.md) for lifecycle activity ownership.

---

## Release Notes (Owner: Technical Writer, Reviewed by: PdM, QA)
- [ ] Release name / version confirmed with PM and PdM
- [ ] Summary of changes drafted (new features, improvements, deprecations)
- [ ] Fixed defects listed with issue references
- [ ] Known issues and workarounds documented
- [ ] Migration or upgrade steps included (if applicable)
- [ ] Release notes reviewed by PdM for accuracy and tone
- [ ] Release notes reviewed by QA to confirm fixed defects are accurate

## User Documentation (Owner: Technical Writer, Reviewed by: Dev, PdM)
- [ ] User-facing docs updated for new or changed features
- [ ] Outdated content removed or marked as deprecated
- [ ] Code samples or screenshots updated (if applicable)
- [ ] Docs reviewed by a Developer for technical accuracy
- [ ] Docs reviewed by PdM for alignment with product intent

## Internal / Process Documentation (Owner: Technical Writer / PM)
- [ ] Internal runbooks or process docs updated to reflect changes
- [ ] New role responsibilities or workflow changes captured
- [ ] Retrospective action items that affect process docs addressed

## Stakeholder Announcement (Owner: PM, Supported by: PdM, TW)
- [ ] Stakeholder announcement drafted using the template below
- [ ] Key changes clearly summarized in non-technical language
- [ ] Links to release notes and updated docs included
- [ ] Announcement reviewed by PdM before sending
- [ ] Distribution list confirmed (internal teams, customers, support)
- [ ] Announcement sent or scheduled for release day

### Stakeholder Announcement Template
```
Subject: [Release name/version] is now available — [one-line summary]

Hi [audience],

We are pleased to announce the release of [release name/version].

**What's new:**
- [Key change 1]
- [Key change 2]

**What's improved:**
- [Improvement 1]

**Action needed (if any):**
- [Migration step or required action]

**Resources:**
- Release notes: [link]
- Updated documentation: [link]
- Support: [contact or channel]

Thank you,
[Team name]
```

---

## Post-Release Documentation Health Check (Owner: Technical Writer)
- [ ] All published docs reflect the released state
- [ ] No broken links in updated documents
- [ ] Documentation feedback channel monitored for issues

---

## Related Documents
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Quality & Release Readiness Checklist](octoacme-quality-release-readiness-checklist.md)
- [RACI Ownership Map](octoacme-raci-ownership-map.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
