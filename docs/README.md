# OctoAcme Project Management Docs

This README indexes the OctoAcme project management process documents and provides a comprehensive summary of the processes used across OctoAcme projects.

## Quick Summary

OctoAcme follows a structured, lifecycle-driven approach to project management that emphasizes stakeholder alignment, iterative delivery, and continuous improvement. The methodology spans five core phases: **Initiation** (validating business need and securing stakeholder buy-in through a Project One-pager), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (building and testing with daily standups and weekly syncs), **Release** (standardized deployment with pre-release checks and rollback plans), and **Close & Retrospective** (capturing learnings for future iterations). This structured lifecycle ensures projects move through decision gates with confirmed success metrics, available resources, and stakeholder alignment before proceeding.

OctoAcme defines clear **core roles** to ensure accountability and ownership: the **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features while collaborating on design and testability; and **QA/Testing** validates quality against acceptance criteria. This separation of concerns—between delivery coordination (PM), product direction (PdM), implementation (Dev), and quality assurance—creates a balanced decision-making structure where each role brings specialized expertise to project execution.

Communication and risk management are woven throughout OctoAcme's approach. The team maintains a **regular cadence** including daily 15-minute standups (focusing on progress, blockers, and dependencies), weekly delivery syncs with the PM and PdM, and monthly stakeholder updates. Risks are tracked in a continuously monitored **Risk Register** with defined escalation paths (team-level → PM → Product Lead → Sponsor), and blockers are triaged at three levels: team standups, PM escalation to dependent teams, and sponsor-level involvement for business-impacting issues. This multi-layered communication structure ensures visibility without creating bottlenecks.

Quality and delivery consistency are maintained through rigorous **execution practices**: the team uses GitHub Projects with a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done), enforces small PRs (≤400 lines when possible) with automated CI testing and linting before review, requires at least one approval before merging, and conducts unit tests, integration tests, and end-to-end smoke tests for critical flows. Velocity and burndown metrics are tracked, and retrospectives after each sprint or milestone capture learnings and convert them into prioritized action items—reinforcing a culture of iterative improvement where processes are regularly refined based on team feedback and measurable outcomes.

## Documentation Index

- [**Project Management Overview**](octoacme-project-management-overview.md) — Concise intro to approach, core roles, key artifacts, and the high-level lifecycle.
- [**Project Initiation Guide**](octoacme-project-initiation.md) — Steps to validate and authorize work, One-pager template, stakeholder alignment, and initiation checklist.
- [**Project Planning**](octoacme-project-planning.md) — Breaking work into shippable increments, backlog templates, estimating, Definition of Done, and risk management.
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Team rhythm, project board workflows, PR conventions, quality assurance, and blocker escalation.
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklist, and rollback playbook.
- [**Risks & Communication**](octoacme-risks-and-communication.md) — Risk Register format, risk lifecycle, stakeholder communication templates, and escalation paths.
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives, tracking improvements, and building a continuous improvement culture.
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Role definitions for Developers, Product Managers, and Project Managers.

## How to Use This README

- **Entry Point**: This file serves as the main entry point for OctoAcme process documentation. Bookmark or reference it when onboarding new team members.
- **Keep It Updated**: When process docs change or new docs are added, update this README and the links accordingly.
- **Propose Changes**: To suggest updates to process docs, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
- **Feedback**: Process documentation is a living artifact. Share feedback and improvements with your Product Lead or Project Manager.
