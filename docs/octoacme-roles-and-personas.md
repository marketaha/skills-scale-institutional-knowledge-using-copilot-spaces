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

## Engineering Lead or Technical Lead

### Role Summary
The Engineering Lead (or Technical Lead) guides technical direction, architecture, and estimation for a team or initiative. They balance delivery speed against technical quality and long-term maintainability.

### Responsibilities
- Set technical direction and architecture decisions
- Lead design reviews and technical risk assessments
- Support estimation and technical feasibility input for planning
- Mentor developers and uphold engineering standards
- Escalate significant technical risks or trade-offs early

### Goals
- Ensure technically sound, scalable solutions
- Reduce rework caused by unclear technical direction
- Balance short-term delivery with long-term system health

### Typical Communication
- Architecture and design review sessions
- Technical design docs and RFCs
- Sync with Product Manager on trade-offs and with Developers on implementation approach

### Artifacts / Decisions Owned
- Architecture decisions and design docs
- Technical risk register entries
- Estimation input for planning

### Interaction Guidance
- **Developers:** Provides technical direction, unblocks design questions, and reviews implementation approach; Developers raise technical concerns to the Engineering Lead early.
- **Product Managers:** Partners on trade-offs between scope, quality, and timeline; translates technical constraints into terms the Product Manager can prioritize against.
- **Project Managers:** Supplies technical estimates, flags technical risks/dependencies for the plan, and confirms readiness before milestones.

---

## QA/Test Lead

### Role Summary
The QA/Test Lead defines the test strategy, validates acceptance criteria, and surfaces quality risks so the team ships with confidence.

### Responsibilities
- Define test strategy and coverage expectations
- Validate acceptance criteria are testable and met
- Track and report defects and quality risks
- Coordinate test environments and release readiness sign-off
- Drive root-cause analysis on escaped defects

### Goals
- Reduce production defects and regressions
- Ensure acceptance criteria reflect real user needs
- Provide clear, timely quality signals to the team

### Typical Communication
- Test plan reviews and defect triage meetings
- Quality/readiness reports ahead of release
- Sync with Developers on defect reproduction and fixes

### Artifacts / Decisions Owned
- Test plans and test cases
- Defect reports and quality risk logs
- Release readiness/go-no-go quality input

### Interaction Guidance
- **Developers:** Collaborates on reproducing and verifying fixes; reviews implementation against acceptance criteria.
- **Product Managers:** Confirms acceptance criteria are complete and testable; flags quality risks that affect scope or timing.
- **Project Managers:** Reports quality status and defect trends for status updates; escalates blocking quality issues to the risk register.

---

## UX or Product Designer

### Role Summary
The UX/Product Designer translates user needs into flows, prototypes, and designs, and validates usability before and after build.

### Responsibilities
- Conduct or synthesize user research to inform design
- Produce user flows, wireframes, and prototypes
- Validate usability through testing and feedback
- Ensure designs are technically feasible with Developers
- Maintain design consistency with product standards

### Goals
- Deliver intuitive, accessible user experiences
- Reduce rework from late-discovered usability issues
- Align design intent with acceptance criteria

### Typical Communication
- Design reviews and usability testing readouts
- Collaboration sessions with Product Manager and Developers
- Annotated designs/specs attached to feature work

### Artifacts / Decisions Owned
- Wireframes, prototypes, and design specs
- Usability test findings
- Design acceptance criteria

### Interaction Guidance
- **Developers:** Partners on feasibility of designs and reviews implemented UI against design intent.
- **Product Managers:** Co-creates problem framing and acceptance criteria; aligns design decisions with product goals.
- **Project Managers:** Flags design dependencies and timelines needed for planning; surfaces design risks that could affect schedule.

---

## DevOps/SRE or Release Manager

### Role Summary
The DevOps/SRE or Release Manager owns deployment readiness, operational health, and safe release execution, including rollback planning.

### Responsibilities
- Own CI/CD pipelines, deployment readiness, and environment health
- Define observability, monitoring, and alerting requirements
- Plan and coordinate releases, including rollback procedures
- Identify operational risks and capacity constraints
- Lead post-release verification and incident response coordination

### Goals
- Ensure safe, repeatable, low-risk releases
- Minimize downtime and operational incidents
- Improve system observability and recovery time

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Incident and post-incident reports
- Coordination with Developers and QA on deployment steps

### Artifacts / Decisions Owned
- Release/deployment plans and rollback plans
- Operational risk assessments
- Monitoring/alerting configuration and runbooks

### Interaction Guidance
- **Developers:** Aligns on deployment requirements, observability hooks, and incident response ownership.
- **Product Managers:** Confirms release timing supports product goals and communicates operational constraints affecting scope.
- **Project Managers:** Coordinates release schedule into the project plan and reports operational risks/status for the risk register.

---

## Security/Privacy Representative

### Role Summary
The Security/Privacy Representative identifies and reviews security and privacy requirements, risks, and controls throughout delivery.

### Responsibilities
- Identify security and privacy requirements early in planning
- Review designs and code changes for security/privacy risk
- Track and prioritize remediation of vulnerabilities
- Advise on compliance and data handling requirements
- Participate in incident response for security-related issues

### Goals
- Reduce security and privacy risk exposure
- Ensure compliance with relevant policies and regulations
- Build security/privacy considerations into delivery by default

### Typical Communication
- Security/privacy design reviews
- Risk and vulnerability reports
- Sync with Developers, QA, and Release Management before release

### Artifacts / Decisions Owned
- Security/privacy risk assessments
- Approved controls and remediation plans
- Release security sign-off

### Interaction Guidance
- **Developers:** Reviews code and architecture for security/privacy risk; advises on secure implementation patterns.
- **Product Managers:** Advises on privacy/compliance implications of product decisions and required disclosures.
- **Project Managers:** Flags security/privacy risks for the risk register and confirms sign-off is complete before release milestones.

---

## Data/Analytics Partner

### Role Summary
The Data/Analytics Partner defines instrumentation and measurement approaches and validates whether success metrics are being achieved.

### Responsibilities
- Define instrumentation and data collection requirements
- Validate success metrics and reporting accuracy
- Analyze outcome data and surface insights
- Support experiment design and result interpretation
- Ensure data quality and metric definitions are consistent

### Goals
- Provide reliable, actionable data on outcomes
- Ensure success metrics are measurable from the start
- Reduce ambiguity in interpreting results

### Typical Communication
- Metrics/reporting reviews with Product Manager and stakeholders
- Instrumentation requirements shared with Developers
- Outcome readouts after release

### Artifacts / Decisions Owned
- Instrumentation/tracking plans
- Metrics dashboards and outcome reports
- Data quality validation results

### Interaction Guidance
- **Developers:** Specifies instrumentation/tracking needs to be implemented and validates data is captured correctly.
- **Product Managers:** Partners on defining success metrics and reports outcome signals that inform prioritization.
- **Project Managers:** Provides data-driven status on outcome metrics for stakeholder reporting and retrospectives.

---

## Customer Support or Operations Representative

### Role Summary
The Customer Support/Operations Representative brings frontline customer-impact insight, prepares support readiness, and feeds incidents and feedback into planning.

### Responsibilities
- Prepare support documentation and readiness ahead of release
- Surface customer feedback, issues, and incident trends
- Represent customer impact in planning and prioritization discussions
- Triage and escalate customer-reported issues appropriately
- Contribute customer perspective to retrospectives

### Goals
- Ensure smooth customer experience through and after release
- Reduce time-to-resolution for customer-impacting issues
- Ensure customer feedback informs future planning

### Typical Communication
- Support readiness reviews before release
- Incident/feedback summaries shared with Product and Engineering
- Participation in retrospectives

### Artifacts / Decisions Owned
- Support runbooks/FAQs
- Customer feedback and incident summaries
- Support readiness sign-off

### Interaction Guidance
- **Developers:** Reports reproducible customer-impacting defects and validates fixes address real-world usage.
- **Product Managers:** Feeds customer feedback and pain points into backlog prioritization.
- **Project Managers:** Flags customer-impact risks for planning and ensures support readiness is tracked as a release dependency.

---

## Executive Sponsor or Business Owner

### Role Summary
The Executive Sponsor/Business Owner confirms strategic priority, secures resources, and resolves business-level escalations that the team cannot resolve on its own.

### Responsibilities
- Confirm strategic alignment and priority of initiatives
- Secure budget, staffing, and organizational resources
- Resolve cross-functional or business-level escalations
- Make final decisions on scope/priority trade-offs when needed
- Champion the initiative with other stakeholders and leadership

### Goals
- Ensure initiatives remain aligned with business strategy
- Unblock resourcing and organizational obstacles quickly
- Provide timely decisions on escalated issues

### Typical Communication
- Periodic executive briefings and milestone reviews
- Escalation conversations as needed
- Sign-off at key decision points (e.g., initiation, major scope changes)

### Artifacts / Decisions Owned
- Business case and strategic approval
- Escalation resolutions and resourcing decisions
- Go/no-go decisions at major milestones

### Interaction Guidance
- **Developers:** Rarely interacts directly; provides context on business priority when technical trade-offs need executive input.
- **Product Managers:** Confirms strategic priority and provides decision support on scope, budget, or timeline trade-offs.
- **Project Managers:** Escalation point for risks/blockers beyond the Project Manager's authority; approves major plan changes.

---

## Multiple Roles on Smaller Teams
On smaller teams, one person may hold multiple personas (for example, a Developer acting as Engineering Lead, or a Project Manager also serving as Release Manager). Regardless of how roles are combined:
- Accountability for each role's responsibilities and decisions must remain explicit, even when consolidated.
- Handoffs between roles should still be documented (e.g., in status updates, decision logs, or readiness checklists) so it's clear which "hat" a decision was made under.
- Teams should periodically confirm role coverage to ensure no responsibility is silently dropped when roles are combined.

## Role Participation Across the Project Lifecycle
The table below maps when each persona is typically most active. "Lead" indicates primary ownership for that phase; "Support" indicates active participation without primary ownership.

| Persona | Initiation | Planning | Execution | Release | Retrospective |
|---|---|---|---|---|---|
| Developers | Support | Support | Lead | Support | Support |
| Product Managers | Lead | Lead | Support | Support | Support |
| Project Managers | Support | Lead | Lead | Lead | Lead |
| Engineering/Technical Lead | Support | Lead | Lead | Support | Support |
| QA/Test Lead | — | Support | Lead | Lead | Support |
| UX/Product Designer | Support | Lead | Support | — | Support |
| DevOps/SRE or Release Manager | — | Support | Support | Lead | Support |
| Security/Privacy Representative | Support | Support | Support | Lead | Support |
| Data/Analytics Partner | Support | Support | — | Support | Lead |
| Customer Support/Operations Representative | — | Support | — | Support | Support |
| Executive Sponsor/Business Owner | Lead | Support | — | Support | — |

### Role-Specific Handoffs and Escalation Paths
- **Design → Development:** UX/Product Designer hands off validated designs to Developers and the Engineering Lead; feasibility concerns escalate back to the Product Manager.
- **Development → QA:** Developers hand off completed work to the QA/Test Lead for validation; unresolved defects escalate to the Engineering Lead and Project Manager.
- **QA/Security → Release:** QA/Test Lead and Security/Privacy Representative provide sign-off to the DevOps/SRE or Release Manager before release; unresolved risks escalate to the Project Manager and, if needed, the Executive Sponsor.
- **Release → Support:** DevOps/SRE or Release Manager hands off release notes and known issues to the Customer Support/Operations Representative; post-release incidents escalate back to Developers and the Release Manager.
- **Outcome Measurement → Planning:** Data/Analytics Partner reports outcomes to the Product Manager, informing the next planning cycle; significant misses escalate to the Executive Sponsor for prioritization decisions.
- **Business-Level Blockers:** Any persona can escalate resourcing, priority, or cross-functional conflicts through the Project Manager to the Executive Sponsor/Business Owner when resolution is beyond the team's authority.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

