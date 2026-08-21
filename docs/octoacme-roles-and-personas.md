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

---

## QA / Testing

### Role Summary
QA and Testing professionals validate that software meets acceptance criteria, quality standards, and non-functional requirements before release. They act as a quality gate across the delivery lifecycle.

### Responsibilities
- Design and execute test plans, test cases, and regression suites
- Report defects and track them through resolution
- Validate bug fixes and confirm acceptance criteria are met
- Collaborate with Developers on testability and edge cases
- Contribute to release readiness criteria

### Goals
- Prevent defects from reaching production
- Increase confidence in release quality
- Improve test coverage and reduce manual testing over time

### Typical Communication
- Sprint reviews and bug triage sessions
- Defect reports and test result summaries
- Coordination with Developers and PM on release blockers

### Interactions with Existing Roles
- **Developers**: Coordinates on bug fixes, edge cases, and test environment setup
- **Product Managers**: Validates features against acceptance criteria and reported user issues
- **Project Managers**: Flags release blockers and quality risks
- **Stakeholders**: Provides quality status as part of release readiness sign-off

---

## Delivery Lead / Scrum Master

### Role Summary
The Delivery Lead or Scrum Master facilitates agile ceremonies, removes delivery blockers, and helps the team maintain a sustainable delivery cadence. They protect the team from external disruptions and coach on agile practices.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and reviews
- Identify and remove impediments that block team progress
- Track team velocity and flag delivery risks early
- Coach the team on agile and lean delivery practices
- Coordinate cross-team dependencies with Project Managers

### Goals
- Maintain consistent team delivery cadence
- Reduce friction and time spent on blockers
- Continuously improve team process and collaboration

### Typical Communication
- Daily standups and retrospective facilitation
- Impediment logs and blocker escalation to PM
- Sprint metrics and burndown reporting

### Interactions with Existing Roles
- **Project Managers**: Aligns on delivery timelines, risks, and cross-team coordination
- **Developers**: Shields team from unplanned interruptions and clears blockers
- **Product Managers**: Coordinates backlog readiness and sprint goal alignment
- **QA / Testing**: Ensures testing is factored into sprint capacity and definition of done

---

## Business Stakeholder / Sponsor

### Role Summary
Business Stakeholders and Sponsors provide strategic direction, approve priorities, and resolve escalations. They represent the business interest and ensure the project delivers value aligned with organizational goals.

### Responsibilities
- Articulate business goals, success metrics, and strategic priorities
- Approve scope changes and resource commitments
- Participate in milestone reviews and sign-off on deliverables
- Resolve escalated risks or decisions that require executive authority
- Advocate for the project within the organization

### Goals
- Ensure project investment delivers measurable business value
- Minimize surprises through timely review and decision-making
- Maintain alignment between project outputs and business strategy

### Typical Communication
- Milestone and steering committee reviews
- Escalation briefings and decision requests from Project Managers
- Executive status summaries and roadmap presentations

### Interactions with Existing Roles
- **Project Managers**: Primary point of contact for escalation, status, and scope decisions
- **Product Managers**: Aligns on roadmap priorities and business value trade-offs
- **Developers**: Indirect; provides strategic context that shapes roadmap priorities
- **QA / Testing**: Reviews release readiness and approves go/no-go decisions at key milestones

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides technical decisions, ensures architectural alignment, and manages implementation risks. They bridge the gap between product requirements and engineering execution.

### Responsibilities
- Define and maintain technical architecture and design standards
- Review and approve significant technical decisions and designs
- Identify and mitigate technical risks and dependencies
- Mentor Developers on architecture patterns and best practices
- Evaluate technology options and trade-offs for major components

### Goals
- Ensure technical quality, scalability, and maintainability of the system
- Reduce architectural debt and prevent costly rework
- Align technical direction with product and business goals

### Typical Communication
- Architecture decision records (ADRs) and design review sessions
- Technical risk updates in project planning meetings
- Code and design review participation with Developers

### Interactions with Existing Roles
- **Developers**: Guides implementation approach, conducts design reviews, and provides architectural guidance
- **Product Managers**: Translates technical constraints into product trade-off conversations
- **Project Managers**: Provides input on technical risks, dependency timelines, and estimation confidence
- **QA / Testing**: Collaborates on testability, integration test strategy, and non-functional requirements

---

## UX / Product Designer

### Role Summary
UX and Product Designers define user flows, validate usability, and translate product requirements into intuitive, accessible experiences. They ensure the product meets user needs and aligns with design standards.

### Responsibilities
- Conduct user research and synthesize insights into design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define and document user flows and interaction patterns
- Collaborate with Developers on design implementation and feasibility
- Validate usability through testing, reviews, and feedback cycles

### Goals
- Deliver experiences that are usable, accessible, and user-centered
- Reduce rework by validating designs before development begins
- Ensure consistency across product interfaces and interaction patterns

### Typical Communication
- Design reviews with Product Managers and Developers
- Usability testing sessions and research readouts
- Design handoff documentation and annotated specifications

### Interactions with Existing Roles
- **Product Managers**: Collaborates on acceptance criteria, user journeys, and feature prioritization
- **Developers**: Provides design specifications and answers implementation questions during development
- **Project Managers**: Communicates design dependencies and flags when design work may impact delivery timelines
- **QA / Testing**: Reviews implemented UI against design specifications to validate fidelity and usability

---

## Operations / Release Manager

### Role Summary
The Operations or Release Manager coordinates release readiness, deployment activities, and rollback preparedness. They ensure that software changes are delivered to production safely and reliably.

### Responsibilities
- Define and manage release schedules and deployment windows
- Coordinate release readiness checklists across QA, Developers, and PM
- Manage deployment pipelines, environment configuration, and release tooling
- Monitor post-release health and coordinate rollback if needed
- Maintain runbooks, deployment guides, and incident response plans

### Goals
- Deliver releases on schedule with minimal production disruption
- Reduce deployment risk through repeatable, well-documented processes
- Increase release frequency by improving automation and coordination

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Deployment status updates to Project Managers and Stakeholders
- Incident summaries and post-release retrospectives

### Interactions with Existing Roles
- **Developers**: Coordinates deployment packaging, environment readiness, and hotfix procedures
- **QA / Testing**: Validates release readiness criteria and ensures testing sign-off before deployment
- **Project Managers**: Aligns release timing with project milestones and communicates deployment risks
- **Business Stakeholders**: Provides go/no-go status and post-release outcome summaries

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

