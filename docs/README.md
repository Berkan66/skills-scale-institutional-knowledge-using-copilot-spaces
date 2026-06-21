# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This README centralizes guidance for running projects using our proven approach, with links to detailed process documents and a high-level overview of our methodology.

## Overview of OctoAcme Project Management

OctoAcme operates on a structured project lifecycle consisting of five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The process prioritizes customer value, iterative delivery, and data-informed decision-making. Every project begins with an initiation phase where teams validate business need, align stakeholders, and create a lightweight Project One-pager that defines the problem statement, measurable success metrics, and initial timeline. Once stakeholders approve the initiative, the planning phase breaks work into shippable increments with clear acceptance criteria, risk assessment, and dependency mapping. This structured approach ensures that projects move forward only when there's sufficient clarity and alignment.

OctoAcme defines clear ownership with four core personas: **Project Managers** coordinate schedules and risks; **Product Managers** define what should be built and prioritize outcomes; **Developers** implement features with quality focus; and **QA/Testing** validates acceptance criteria. The organization maintains a consistent communication rhythm with daily standups (15 minutes), weekly PM and PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Risk escalation follows a three-level path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level involvement for business-impacting issues. This layered approach ensures transparency and enables rapid decision-making.

During execution, teams use GitHub Projects as a central hub with workflow columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintain velocity and burndown metrics to track progress. Quality is embedded throughout with requirements for unit tests, integration tests, end-to-end smoke tests, and security scanning in CI before any PR can be merged. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. Release management is standardized with pre-release checklists covering CI/security validation, smoke testing, and rollback plans. Each release includes documented release notes, migration steps, and known issues, with post-deployment verification and stakeholder announcements to ensure smooth transitions.

OctoAcme emphasizes a retrospective-driven culture where teams hold 45–75 minute retrospectives after each sprint or milestone to capture learnings and convert them into actionable improvements. Each retrospective focuses on what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates. These action items feed back into the project backlog and are reviewed in weekly PM syncs to ensure accountability and measurable impact. This commitment to psychological safety, blameless retrospectives (especially after incidents), and iterative process refinement creates a culture of continuous learning and shared responsibility for success.

## Process Documentation

Navigate to the detailed process documents below for specific guidance on each phase:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise intro to OctoAcme approach, core roles, key artifacts, and high-level lifecycle.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps and templates for validating and authorizing new projects, including the Project One-pager template and initiation checklist.
- **[Project Planning](octoacme-project-planning.md)** — Turning approved initiatives into actionable plans, backlog templates, estimation, Definition of Done, and risk handling.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, team rhythm (standups and demos), PR and CI guidance, quality assurance, and execution checklist.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template.
- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk register format, risk lifecycle, stakeholder communication templates, and escalation paths.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, tracking improvements, and building a continuous improvement culture.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role summaries, responsibilities, and communication patterns for Developers, Product Managers, and Project Managers.

## How to Use This Documentation

- **For new team members:** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach, then dive into specific phases as needed.
- **For project kickoff:** Review the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) documents.
- **For execution:** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risks & Communication](octoacme-risks-and-communication.md) during daily standups and weekly syncs.
- **For releases:** Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) checklist to ensure smooth deployments.
- **For continuous improvement:** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to run effective retrospectives and track action items.

## Updating Process Documentation

To propose changes or additions to these process documents:

1. Review the relevant process doc to understand current guidance
2. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
3. Provide a clear summary, rationale, and suggested content
4. Await stakeholder review and approval before implementing changes

This ensures our process documentation remains aligned, vetted, and reflects team consensus.
