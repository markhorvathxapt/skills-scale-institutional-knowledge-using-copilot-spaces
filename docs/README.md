# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This README serves as the central index and entry point for all process documents, helping new and existing team members quickly find the guidance they need.

## Overview

OctoAcme operates a structured, customer-focused project management approach built on iterative delivery and clear ownership. The organization employs a defined lifecycle spanning **initiation → planning → execution → release → retrospective** phases, with each stage producing specific deliverables. Key roles include the **Project Manager** (who coordinates schedules, risks, and communications), **Product Manager** (who defines outcomes and prioritizes work), **Developers** (who implement and collaborate on design), and **QA teams** (who validate quality). This role-based structure ensures accountability and clear communication lines, supported by artifacts like Project One-pagers, backlogs with acceptance criteria, Risk Registers, and release notes that serve as single sources of truth throughout each project's lifecycle.

Communication across OctoAcme emphasizes transparency and regular cadence: weekly syncs between Project and Product Managers, twice-weekly standups for delivery teams, and monthly stakeholder updates ensure alignment and early escalation of risks and blockers. The organization uses GitHub Projects as its primary tracking tool, employing a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done) and enforcing practices such as small pull requests (≤400 lines), automated CI/CD testing, and linting before merging. Risk management is proactive, with a documented Risk Register reviewed weekly and escalation paths defined from team-level through Product Lead to Sponsor level for business-impacting issues.

Quality assurance is embedded throughout OctoAcme's delivery process, combining automated testing (unit, integration, end-to-end smoke tests, and security scanning) with structured peer review before any merge. OctoAcme closes each project cycle with retrospectives—held after sprints, releases, or incidents—where teams capture learnings, prioritize 2–3 top action items, and measure the impact of continuous improvements, fostering a culture of psychological safety and evidence-based iteration.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's PM approach, tools, and principles |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a new project: goals, stakeholders, and one-pager creation |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, sprint planning, estimation, and acceptance criteria |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflow, standups, GitHub Projects board management |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk Register process, escalation paths, and communication cadences |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment steps, and go/no-go criteria |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action item tracking, and improvement measurement |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions of all project roles, responsibilities, and RACI guidelines |

---

## Project Lifecycle Summary

```
Initiation → Planning → Execution → Release → Retrospective
```

| Phase | Key Activities | Key Artifacts |
|---|---|---|
| **Initiation** | Define goals, identify stakeholders, create one-pager | Project One-pager |
| **Planning** | Build backlog, define acceptance criteria, estimate effort | Backlog, Sprint Plan |
| **Execution** | Daily standups, PR reviews, CI/CD, board updates | GitHub Projects board, PRs |
| **Release** | Go/no-go review, deployment, release notes | Release Notes, Deploy Log |
| **Retrospective** | Capture learnings, prioritize action items, track improvement | Retro Notes, Action Items |

---

## Quick Reference: When to Use Each Document

- **Starting a new project?** → [Project Initiation](octoacme-project-initiation.md)
- **Setting up sprints and backlog?** → [Project Planning](octoacme-project-planning.md)
- **Managing day-to-day delivery?** → [Execution and Tracking](octoacme-execution-and-tracking.md)
- **Tracking or escalating a risk?** → [Risks and Communication](octoacme-risks-and-communication.md)
- **Preparing for a release?** → [Release and Deployment](octoacme-release-and-deployment.md)
- **Running a retrospective?** → [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- **Clarifying team roles?** → [Roles and Personas](octoacme-roles-and-personas.md)
- **Getting a high-level picture?** → [Project Management Overview](octoacme-project-management-overview.md)
