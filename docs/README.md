# OctoAcme Project Management Process Documentation

Welcome — this folder contains OctoAcme's standardized project management processes, guidance, and checklists. Use this README as the central entry point to find the right process document for your situation, from initiating a new project through planning, execution, release, and continuous improvement.

## Quick Start
New to OctoAcme projects? Start here:
1. Read [Project Management Overview](./octoacme-project-management-overview.md) for core principles and roles
2. Follow [Project Initiation](./octoacme-project-initiation.md) when starting a new project
3. Use [Project Planning](./octoacme-project-planning.md) to create your delivery plan
4. During delivery, follow [Execution & Tracking](./octoacme-execution-and-tracking.md)
5. For releases and deployments, see [Release & Deployment](./octoacme-release-and-deployment.md)

## Project Management Processes — Brief Overview
OctoAcme runs projects with a clear staged workflow that moves work from initiation through planning, execution, release, and retrospective. Initiation requires a short Project One-pager that captures problem, objective, success metrics, stakeholders, timeline, and risks; teams move into planning once success criteria, stakeholder alignment, and resource availability are confirmed. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan.

Execution emphasizes frequent communication and small, testable increments. Teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a pull request workflow that favors small PRs, links issues and acceptance criteria, runs CI and linting before review, and requires approvals per team policy. Daily standups, weekly delivery syncs, and sprint demos keep stakeholders aligned and surface blockers.

Ownership and roles are explicit: Product Managers define outcomes and prioritize the backlog, Project Managers coordinate delivery and communication, Developers implement and test, and QA validates acceptance and quality. Key artifacts include the Project One-pager, roadmap, backlog items with acceptance criteria, a risk register, and release notes — each stored in this docs/ folder or the project repo as the single source of truth.

Quality is enforced by a mix of automated and manual controls. CI must run unit, integration, and security scans; smoke and end-to-end checks are used for critical flows and must pass before release. Releases follow a pre-release checklist (acceptance criteria met, passing CI, release notes, rollback plan), with post-deploy verification and manual QA as needed. Retrospectives produce action items that feed back into the backlog for continuous improvement.

## Complete Documentation (files and purpose)
| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, principles, roles, and lifecycle |
| [Project Initiation](./octoacme-project-initiation.md) | Initial validation, stakeholder alignment, and go/no-go decision |
| [Project Planning](./octoacme-project-planning.md) | Breaking work into shippable increments and creating the delivery plan |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution, standups, quality standards, and blocker escalation |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk registers, stakeholder communication, and escalation paths |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, deployment checklist, and rollback procedures |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Learning capture and process improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Definitions of key project roles and responsibilities |

## Project lifecycle at a glance
1. Initiation → Define the business need and get stakeholder alignment  
2. Planning → Break down work and create delivery plan  
3. Execution → Build, test, and track progress  
4. Release → Deploy and verify  
5. Retrospective → Capture learnings and improve

## Core principles
- Customer-first: Prioritize customer value and usability  
- Iterative delivery: Deliver small, testable increments  
- Clear ownership: Each project has a named PM and Product Lead  
- Data-informed: Measure impact and iterate based on evidence  
- Psychological safety: Encourage feedback and learning

## Which doc to use when (quick guide)
- Starting a new idea: Project Initiation  
- Turning an approved idea into work: Project Planning  
- During implementation: Execution & Tracking and Roles & Personas  
- Before a production rollout: Release & Deployment  
- After a sprint or release: Retrospective & Continuous Improvement  
- When managing risks or stakeholder comms: Risk Management & Communication

## Acceptance criteria for this README
- Content aligns with existing process docs  
- Improves discoverability and clarity of the docs/ folder  
- Provides a concise entry point for new team members
