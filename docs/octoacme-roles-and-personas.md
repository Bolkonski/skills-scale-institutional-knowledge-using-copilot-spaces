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

## Assigning cross-functional roles

At initiation, the Project Manager and Product Manager validate the required roles with stakeholders and record named owners, decision rights, and handoffs in the Project Charter. These personas describe responsibilities, not mandatory new positions: one person may cover several roles on smaller projects, but each responsibility must have an explicit owner. Revisit assignments during planning and when scope or risks change.

QA/Testing continues to validate quality and acceptance criteria; Stakeholders provide inputs and approvals. The additional roles below complement those responsibilities and the existing Developers, Product Managers, and Project Managers rather than replacing them. The Product Manager retains backlog priority and product outcome ownership, and the Project Manager retains delivery coordination and status reporting.

Record cross-functional risks, owners, and mitigations in the risk register and decisions in the decision log. Use the existing escalation path: Team-level -> Project Manager -> Product Lead -> Sponsor. For security incidents, follow the security incident runbook and notify Security on-call.

---

## Project Sponsor / Executive Sponsor

### Role Summary
The Sponsor owns business sponsorship and strategic alignment, secures resources, and resolves decisions beyond the delivery team's authority.

### Responsibilities
- Confirm the business case, success measures, and organizational commitment
- Secure funding and resolve cross-team resource conflicts
- Review major scope, budget, and timeline trade-offs at decision gates

### Lifecycle Contributions
- Initiation: endorse the Project Charter and confirm strategic alignment
- Planning: confirm resource commitments and sponsor-level decision gates
- Execution: resolve escalated business risks and dependencies
- Release: confirm business readiness and any sponsor-level approvals agreed in the charter
- Retrospective: review outcomes and sponsor organizational improvement actions

### Decision Rights and Escalation
- Decide funding and strategic trade-offs within delegated authority; escalate beyond that authority to the accountable executive
- Resolve sponsor-level escalations without taking over backlog prioritization, technical design, or QA validation

### Key Artifacts
- Business case, endorsed Project Charter, funding decisions, and decision log entries

### Interactions with Existing Roles
- Partner with the Project Manager on escalations and with the Product Manager on value and major trade-offs
- Align Stakeholders on commitments; use Developers' and QA/Testing's evidence when evaluating delivery risks and readiness

---

## Delivery / Engineering Lead

### Role Summary
The Delivery / Engineering Lead coordinates technical execution and keeps implementation aligned with agreed scope and quality expectations.

### Responsibilities
- Support estimation, sequencing, and technical dependency management
- Coordinate design reviews and implementation across Developers
- Identify technical risks and propose feasible delivery options

### Lifecycle Contributions
- Initiation: assess technical feasibility and identify dependencies
- Planning: develop estimates, technical milestones, and testability expectations
- Execution: coordinate technical work, reviews, and blocker resolution
- Release: provide technical readiness evidence and support deployment and rollback planning
- Retrospective: identify engineering improvements and own agreed technical follow-ups

### Decision Rights and Escalation
- Decide technical sequencing and implementation approaches within agreed scope and engineering standards
- Bring scope or schedule trade-offs to the Project Manager and Product Manager; escalate unresolved dependencies through the Project Manager
- Do not change product priorities or waive QA, security, or operational release requirements

### Key Artifacts
- Technical design decisions, estimates, dependency map, and technical readiness evidence

### Interactions with Existing Roles
- Work with Developers on implementation and QA/Testing on quality and testability
- Give the Project Manager delivery risks and the Product Manager feasible scope options; explain technical constraints to Stakeholders

---

## UX / Design Lead

### Role Summary
The UX / Design Lead owns user experience direction, research inputs, and usability validation.

### Responsibilities
- Research user needs and translate findings into workflows and designs
- Define accessible, usable interactions and clarify design acceptance criteria
- Validate proposed and implemented experiences with users

### Lifecycle Contributions
- Initiation: identify users, research needs, and usability risks
- Planning: prepare designs, prototypes, and usability acceptance criteria
- Execution: clarify designs and validate implementation with Developers and QA/Testing
- Release: review the delivered experience and report unresolved usability or accessibility issues
- Retrospective: evaluate user feedback and propose design process improvements

### Decision Rights and Escalation
- Decide design direction within agreed product outcomes and design standards
- Negotiate feasibility and priority trade-offs with Developers and the Product Manager; escalate unresolved delivery impacts through the Project Manager
- Do not independently expand scope or replace QA acceptance validation

### Key Artifacts
- Research findings, user journeys, prototypes, design specifications, and usability validation results

### Interactions with Existing Roles
- Partner with the Product Manager on outcomes and Stakeholders on user needs
- Give Developers implementable designs and QA/Testing testable criteria; coordinate design dependencies and risks with the Project Manager

---

## Business Analyst

### Role Summary
The Business Analyst translates stakeholder needs into detailed requirements, workflows, and acceptance criteria.

### Responsibilities
- Elicit requirements and clarify business rules and workflow dependencies
- Maintain traceability between needs, backlog items, and acceptance criteria
- Resolve requirement ambiguity and support business validation

### Lifecycle Contributions
- Initiation: map stakeholder needs, current workflows, and business constraints
- Planning: refine requirements and acceptance criteria with the Product Manager and QA/Testing
- Execution: answer requirement questions and assess proposed changes
- Release: support stakeholder validation and confirm requirement coverage
- Retrospective: identify missed requirements and improve discovery and handoffs

### Decision Rights and Escalation
- Clarify and document agreed requirements; recommend changes without independently approving scope or priority
- Refer conflicting business needs to the Product Manager and delivery impacts to the Project Manager
- Obtain approvals from accountable Stakeholders rather than substituting for them

### Key Artifacts
- Requirements, workflow maps, business rules, traceability records, and acceptance criteria

### Interactions with Existing Roles
- Elicit inputs from Stakeholders and refine them with the Product Manager
- Help Developers and QA/Testing interpret requirements; inform the Project Manager of dependencies and unresolved approvals

---

## Technical Writer / Documentation Owner

### Role Summary
The Technical Writer / Documentation Owner coordinates accurate user-facing and operational documentation and release information.

### Responsibilities
- Maintain documentation plans, user guides, and release notes
- Coordinate technical reviews and keep documentation aligned with delivered behavior
- Prepare documentation handoffs for Operations and customer-facing teams

### Lifecycle Contributions
- Initiation: identify audiences and documentation needs
- Planning: include documentation deliverables, reviewers, and dependencies in the release plan
- Execution: draft and validate content alongside implementation
- Release: finalize reviewed documentation, release notes, migration steps, and known issues before release
- Retrospective: use documentation feedback to address gaps and improve maintenance

### Decision Rights and Escalation
- Own documentation structure, clarity, and publication readiness within agreed standards
- Require subject-matter review for technical accuracy; do not own product scope or operational procedures on behalf of their accountable owners
- Raise missing reviews or release-critical documentation gaps to the Project Manager

### Key Artifacts
- Documentation plan, user guides, reviewed operational documentation, and release notes

### Interactions with Existing Roles
- Validate behavior with Developers and QA/Testing and messaging with the Product Manager
- Coordinate milestones with the Project Manager and documentation needs with Stakeholders, Operations, and Customer Support / Customer Success

---

## Operations / Site Reliability Representative

### Role Summary
The Operations / Site Reliability Representative owns operational readiness requirements and coordinates reliable deployment and support handoffs.

### Responsibilities
- Define monitoring, alerting, deployment, on-call, and rollback requirements
- Validate support readiness and operational risk mitigations
- Coordinate operational incident response and follow-up within the incident runbook

### Lifecycle Contributions
- Initiation: identify service ownership, reliability needs, and operational constraints
- Planning: define readiness criteria, monitoring, deployment windows, and rollback plans
- Execution: work with Developers and QA/Testing to validate observability and recovery
- Release: review operational readiness, coordinate deployment, and verify service health; trigger incident response and rollback when required
- Retrospective: contribute incident findings and own agreed reliability improvements

### Decision Rights and Escalation
- Determine operational readiness within agreed release criteria and exercise incident authority defined by the runbook
- Do not waive unmet acceptance criteria, passing CI and security scans, or other pre-release requirements
- Escalate readiness gaps through the Project Manager; route incidents to on-call and security incidents to Security on-call

### Key Artifacts
- Operational readiness checklist, monitoring and alert definitions, deployment and rollback plans, and incident follow-ups

### Interactions with Existing Roles
- Partner with Developers on deployability and QA/Testing on smoke tests and recovery validation
- Coordinate release dependencies with the Project Manager, service-impact trade-offs with the Product Manager, and readiness communications with Stakeholders and Security

---

## Security / Privacy Partner

### Role Summary
The Security / Privacy Partner reviews security, privacy, and compliance considerations and guides risk controls throughout delivery.

### Responsibilities
- Identify threats, sensitive data flows, and applicable security and privacy requirements
- Review controls and validate mitigations within delegated authority
- Support risk escalation and security incident response through established channels

### Lifecycle Contributions
- Initiation: identify data sensitivity, obligations, and high-level security risks
- Planning: define threat assessments, controls, and security acceptance criteria
- Execution: review implementation and findings with Developers and QA/Testing
- Release: provide security readiness evidence, verify required controls and scans, and flag unresolved risks
- Retrospective: review security findings and incidents and recommend preventive improvements

### Decision Rights and Escalation
- Approve controls and mitigations only within delegated security or privacy authority
- Escalate residual-risk acceptance to the designated accountable authority through the Project Manager; do not unilaterally waive compliance obligations or release requirements
- For security incidents, follow the security incident runbook and notify Security on-call

### Key Artifacts
- Threat assessments, data-flow reviews, control requirements, security findings, and documented mitigation or risk-acceptance decisions

### Interactions with Existing Roles
- Align requirements with the Product Manager and accountable Stakeholders
- Work with Developers, QA/Testing, and Operations on controls and verification; keep the Project Manager informed of risks and approval dependencies

---

## Customer Support / Customer Success Representative

### Role Summary
The Customer Support / Customer Success Representative contributes customer-impact insights, support readiness, and post-release adoption signals.

### Responsibilities
- Surface recurring customer problems and support or adoption needs
- Prepare support enablement and coordinate customer communications
- Gather post-release feedback and route issues to accountable teams

### Lifecycle Contributions
- Initiation: contribute customer pain points and affected audience insights
- Planning: identify support, training, communication, and adoption requirements
- Execution: review customer-facing workflows and prepare support materials with the Documentation Owner
- Release: confirm support readiness and coordinate approved customer communications and handoffs
- Retrospective: share support trends, adoption feedback, and improvement proposals

### Decision Rights and Escalation
- Own support enablement and customer communication readiness within agreed messaging and service commitments
- Recommend product changes without committing scope, priorities, or delivery dates on behalf of the team
- Escalate readiness gaps through the Project Manager, product feedback to the Product Manager, and service incidents to Operations through the incident process

### Key Artifacts
- Customer-impact summary, support readiness checklist, enablement materials, communication plan, and post-release feedback

### Interactions with Existing Roles
- Give the Product Manager customer evidence and the Project Manager readiness and communication risks
- Work with Developers and QA/Testing to reproduce customer issues; align Stakeholders, the Documentation Owner, and Operations on release information and support handoffs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

