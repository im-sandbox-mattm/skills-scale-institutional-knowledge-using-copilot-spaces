# OctoAcme Roles and Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It provides comprehensive guidance on role descriptions, responsibilities, interactions, onboarding, and handoff scenarios to ensure clear accountability and effective collaboration across the project lifecycle.

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

## Release Manager

### Role Summary
Release Manager oversees deployment schedules, release coordination, and ensures readiness through compliance checklist completion. They serve as the single point of accountability for successful releases.

### Responsibilities
- Coordinate deployment schedules and release windows
- Manage release communications and stakeholder notifications
- Ensure completion of pre-release checklists and compliance requirements
- Coordinate release activities across teams
- Monitor deployment progress and post-release stability
- Maintain release documentation and runbooks

### Goals
- Deliver smooth, predictable releases with minimal disruption
- Ensure all release readiness criteria are met
- Minimize deployment-related incidents and rollbacks
- Maintain clear communication throughout the release process

### Typical Communication
- Release planning meetings with Project Manager and QA Lead
- Go/no-go meetings with stakeholders
- Release status updates and post-deployment reports
- Coordination with Tech Lead on deployment strategies

---

## Business Analyst

### Role Summary
Business Analyst gathers requirements, clarifies scope, and facilitates communication between business stakeholders and technical teams. They translate business needs into actionable requirements.

### Responsibilities
- Gather and document business requirements
- Clarify scope and acceptance criteria with stakeholders
- Facilitate communication between business and tech teams
- Analyze process workflows and identify improvement opportunities
- Create user stories and functional specifications
- Validate that solutions meet business needs

### Goals
- Ensure clear understanding of business requirements
- Bridge communication gaps between stakeholders and developers
- Reduce rework through accurate requirements gathering
- Maximize alignment between technical solutions and business objectives

### Typical Communication
- Requirements workshops with stakeholders
- Alignment sessions with Product Owner and Project Manager
- User story refinement with development team
- Business process documentation and diagrams

---

## Communications Lead

### Role Summary
Communications Lead manages status updates, stakeholder reporting, and maintains project visibility through dashboards and regular communications. They ensure all stakeholders are informed and aligned.

### Responsibilities
- Manage project status updates and reports
- Maintain project dashboards and visibility tools
- Coordinate stakeholder communications
- Prepare executive briefings and presentations
- Ensure consistent messaging across communication channels
- Track and respond to stakeholder questions and feedback

### Goals
- Maintain transparency and stakeholder alignment
- Ensure timely and accurate information sharing
- Reduce miscommunication and information gaps
- Build stakeholder confidence through clear communication

### Typical Communication
- Weekly status reports with Project Manager
- Stakeholder briefings and updates
- Dashboard reviews with Scrum Master
- Cross-team coordination meetings

---

## QA Lead

### Role Summary
QA Lead defines test strategy, manages QA resources, and ensures quality gates are followed throughout the development lifecycle. They are accountable for quality standards and validation.

### Responsibilities
- Define and maintain test strategy and quality standards
- Manage QA resources and testing schedules
- Review test outcomes and quality metrics
- Ensure quality gates are followed before releases
- Coordinate with developers on testability and test automation
- Report on quality status and risk areas

### Goals
- Maintain high product quality and reliability
- Catch defects early in the development cycle
- Ensure comprehensive test coverage
- Support rapid, confident releases

### Typical Communication
- Test planning sessions with Tech Lead and developers
- Quality reviews with Release Manager
- Defect triage meetings
- Test automation strategy discussions

---

## Change Coordinator

### Role Summary
Change Coordinator oversees the change control process, ensures proper approvals, and communicates planned changes to affected parties. They maintain process integrity and minimize change-related risks.

### Responsibilities
- Oversee change control process and governance
- Ensure all changes receive proper approvals
- Communicate planned changes to stakeholders
- Track change requests and their status
- Coordinate change advisory board (CAB) meetings
- Monitor change success rates and post-implementation reviews

### Goals
- Minimize disruption from changes
- Ensure compliance with change management policies
- Reduce change-related incidents
- Maintain audit trail of all changes

### Typical Communication
- Change advisory board meetings
- Change approval coordination with Project Manager
- Technical change reviews with Tech Lead
- Post-implementation reviews and assessments

---

## Role Interactions and Responsibilities Summary

The following table summarizes key responsibilities and primary interactions for all roles:

| Role | Main Responsibilities | Primary Interactions |
|------|----------------------|---------------------|
| Developer | Implement features, write tests, code reviews | Product Manager, QA Lead, Tech Lead |
| Product Manager | Define vision, prioritize backlog, measure outcomes | Business Analyst, Project Manager, Developers |
| Project Manager | Coordinate delivery, manage risks, facilitate meetings | Release Manager, Communications Lead, Change Coordinator |
| Release Manager | Release planning, deployment coordination, compliance | QA Lead, Project Manager, Tech Lead |
| Business Analyst | Requirements gathering, scope clarification, stakeholder bridge | Product Manager, Project Manager, Developers |
| Communications Lead | Status updates, stakeholder reporting, dashboard maintenance | Project Manager, Scrum Master, stakeholders |
| QA Lead | Test strategy, quality gating, outcome validation | Release Manager, Tech Lead, Developers |
| Change Coordinator | Change management, approvals, process coordination | Project Manager, Tech Lead, Release Manager |

---

## Onboarding Checklists

The following checklists provide role-specific onboarding guidance. For a comprehensive onboarding template with 30-60-90 day goals and tracking, see [OctoAcme Role Onboarding Template](octoacme-role-onboarding-template.md).

### Release Manager Onboarding
- [ ] Review release and deployment guide
- [ ] Understand deployment pipeline and infrastructure
- [ ] Access release management tools and dashboards
- [ ] Review past release retrospectives and lessons learned
- [ ] Meet with QA Lead to understand quality gates
- [ ] Shadow at least one release cycle
- [ ] Review rollback procedures and incident playbooks
- [ ] Establish communication channels with key stakeholders

### Business Analyst Onboarding
- [ ] Review product roadmap and current backlog
- [ ] Understand business domains and stakeholder landscape
- [ ] Access requirements management tools
- [ ] Review user story templates and acceptance criteria standards
- [ ] Meet with Product Manager to align on prioritization
- [ ] Shadow requirements gathering sessions
- [ ] Review existing business process documentation
- [ ] Establish communication channels with key business stakeholders

### Communications Lead Onboarding
- [ ] Review project management overview and communication cadence
- [ ] Access project dashboards and reporting tools
- [ ] Review past status reports and stakeholder updates
- [ ] Meet with Project Manager to understand current priorities
- [ ] Identify all stakeholder groups and their information needs
- [ ] Review communication templates and standards
- [ ] Establish distribution lists and communication channels
- [ ] Create communication calendar and schedule

### QA Lead Onboarding
- [ ] Review test strategy and quality standards
- [ ] Access test management and automation tools
- [ ] Review current test coverage and quality metrics
- [ ] Meet with Tech Lead to understand architecture and testability
- [ ] Review quality gates and definition of done
- [ ] Shadow test planning and execution sessions
- [ ] Review defect tracking process and tools
- [ ] Establish communication with development team

### Change Coordinator Onboarding
- [ ] Review change management policy and procedures
- [ ] Access change management tools and systems
- [ ] Review change request templates and approval workflows
- [ ] Meet with Project Manager to understand current change pipeline
- [ ] Review past change advisory board meetings
- [ ] Understand escalation paths and approval authorities
- [ ] Review change categorization and risk assessment criteria
- [ ] Establish communication with key approvers and stakeholders

---

## Role Handoff and Escalation Scenarios

### Scenario 1: Requirements to Development Handoff
**Context:** A new feature has been approved and needs to move from requirements to implementation.

**Flow:**
1. **Business Analyst** finalizes requirements and acceptance criteria
2. **Business Analyst** → **Product Manager**: Reviews and validates business value
3. **Product Manager** → **Project Manager**: Confirms resource availability and timeline
4. **Project Manager** → **Developers**: Assigns work and sets expectations
5. **QA Lead** is notified to prepare test strategy

**Escalation Path:** If requirements are unclear or incomplete, Developer escalates to Business Analyst, who may escalate to Product Manager for prioritization decisions.

---

### Scenario 2: Pre-Release Quality Gate
**Context:** A release is scheduled but quality concerns have been raised.

**Flow:**
1. **QA Lead** identifies quality concerns during final testing
2. **QA Lead** → **Release Manager**: Reports findings and recommends go/no-go
3. **Release Manager** → **Project Manager**: Evaluates impact on schedule
4. **Project Manager** → **Product Manager**: Assesses business impact of delay
5. **Release Manager** makes final go/no-go decision based on inputs

**Escalation Path:** If unable to reach consensus, escalate to executive sponsor with input from all stakeholders.

---

### Scenario 3: Change Request Approval
**Context:** A significant change is requested during active development.

**Flow:**
1. Requester submits change request to **Change Coordinator**
2. **Change Coordinator** → **Project Manager**: Evaluates schedule and resource impact
3. **Change Coordinator** → **Tech Lead**: Assesses technical feasibility and risk
4. **Change Coordinator** convenes change advisory board (CAB)
5. **Change Coordinator** → Requester: Communicates decision and next steps

**Escalation Path:** If change is high-impact or controversial, escalate to Product Manager and executive sponsor for final decision.

---

### Scenario 4: Deployment Issue During Release
**Context:** An issue is discovered during production deployment.

**Flow:**
1. **Release Manager** identifies deployment issue
2. **Release Manager** → **Tech Lead**: Assesses severity and impact
3. **Tech Lead** → **Developers**: Triages and determines fix approach
4. **Release Manager** → **Communications Lead**: Prepares stakeholder notification
5. **Release Manager** decides: rollback, fix forward, or pause
6. **QA Lead** validates fix or rollback before proceeding

**Escalation Path:** If issue is critical or customer-impacting, Release Manager escalates to incident response process and notifies executive sponsor immediately.

---

### Scenario 5: Stakeholder Communication Breakdown
**Context:** Stakeholders report being uninformed about project status.

**Flow:**
1. Stakeholder raises concern to **Communications Lead**
2. **Communications Lead** → **Project Manager**: Reviews communication gaps
3. **Project Manager** → **Communications Lead**: Adjusts communication plan
4. **Communications Lead** implements remediation (more frequent updates, different channels, etc.)
5. **Communications Lead** → Stakeholders: Confirms improved communication plan

**Escalation Path:** If communication gaps persist or involve executive stakeholders, escalate to Product Manager and consider broader process improvements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The interaction table and scenarios help clarify responsibilities and handoff points across the project lifecycle.
- Onboarding checklists ensure new team members can quickly understand their role and get up to speed.

