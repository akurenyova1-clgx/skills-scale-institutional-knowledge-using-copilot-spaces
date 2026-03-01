# OctoAcme — Cross-Functional Handoffs Checklist

## Purpose
Clarify ownership and handoff points among all roles across each phase of the project lifecycle to reduce ambiguity, prevent dropped tasks, and promote consistent execution.

## Roles Referenced
- **PM** — Project Manager
- **PdM** — Product Manager
- **BA** — Business Analyst
- **Design** — UX/UI Designer
- **Dev** — Developers
- **QA** — QA Lead
- **DevOps** — DevOps Engineer
- **Security** — Security Champion

---

## Phase 1 — Initiation

| Checklist Item | Owner | Collaborators |
|---|---|---|
| [ ] Project charter / one-pager drafted | PM | PdM, BA |
| [ ] Key stakeholders identified and mapped | PM | PdM, BA |
| [ ] Initial requirements discovery sessions scheduled | BA | PdM, PM |
| [ ] Roles assigned and communicated to team | PM | All |
| [ ] High-level timeline and milestones proposed | PM | PdM |
| [ ] Initial risk register created | PM | Security, DevOps |

---

## Phase 2 — Planning

| Checklist Item | Owner | Collaborators |
|---|---|---|
| [ ] Detailed requirements documented and reviewed | BA | PdM, Dev |
| [ ] Backlog created with acceptance criteria | PdM | BA, QA |
| [ ] Definition of Done (DoD) documented and agreed | PdM | QA, Dev |
| [ ] Test strategy and test plan drafted | QA | Dev, BA, PdM |
| [ ] Deployment strategy and environments defined | DevOps | Dev, QA, PM |
| [ ] Threat modeling session held | Security | Dev, DevOps, PdM |
| [ ] Design brief and wireframes reviewed | Design | PdM, Dev, BA |
| [ ] Release plan and milestones confirmed | PM | PdM, DevOps |
| [ ] Dependencies and cross-team integrations mapped | PM | Dev, DevOps |

---

## Phase 3 — Execution

| Checklist Item | Cadence | Owner | Collaborators |
|---|---|---|---|
| [ ] Sprint planning session held | Per sprint | PM | PdM, Dev, QA |
| [ ] Daily standup (or async equivalent) | Daily | PM | Dev, QA, Design |
| [ ] Design handoff to development completed | Per feature | Design | Dev |
| [ ] Code reviewed and merged | Per PR | Dev | Dev (peer), QA |
| [ ] Security review for high-risk changes | Per feature | Security | Dev, DevOps |
| [ ] Test environments up-to-date | Ongoing | DevOps | QA |
| [ ] Defects triaged and assigned | Weekly | QA | Dev, PM |
| [ ] Risks and blockers reviewed | Weekly | PM | All |
| [ ] Stakeholder status update sent | Weekly | PM | PdM |

---

## Phase 4 — Release

| Checklist Item | Owner | Collaborators |
|---|---|---|
| [ ] All acceptance criteria met and verified | QA | Dev, PdM |
| [ ] CI pipeline passing (build, tests, scans) | DevOps | Dev, QA, Security |
| [ ] Security scans completed with no blocking findings | Security | DevOps |
| [ ] Release notes drafted and reviewed | PdM | PM, BA |
| [ ] Rollback / mitigation plan documented | DevOps | PM |
| [ ] Deployment window scheduled and communicated | PM | DevOps, Stakeholders |
| [ ] Staging deployment completed and smoke tests passed | DevOps | QA |
| [ ] Production deployment executed | DevOps | Dev |
| [ ] Post-deploy verification completed | QA | DevOps, Dev |
| [ ] Release announcement sent to stakeholders | PM | PdM |
| [ ] Support team briefed on changes | PM | PdM, DevOps |

---

## Phase 5 — Close & Retrospective

| Checklist Item | Owner | Collaborators |
|---|---|---|
| [ ] Retrospective held | PM | All |
| [ ] Action items captured and assigned | PM | All |
| [ ] Lessons learned documented | PM | All |
| [ ] Requirements traceability review completed | BA | QA, PdM |
| [ ] Security findings and remediations documented | Security | DevOps, PM |
| [ ] Process and tooling improvements identified | DevOps, QA | PM |

---

## Notes
- This checklist is a starting point; adapt scope and owners to your team's size and context.
- Link checklist items to project board tasks or issues for full traceability.
- See related docs: [Roles & Personas](octoacme-roles-and-personas.md), [Project Planning](octoacme-project-planning.md), [Release & Deployment Guide](octoacme-release-and-deployment.md).
