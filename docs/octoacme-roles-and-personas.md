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

## QA / Testing Lead

### Role Summary
QA/Testing Leads own quality assurance, test strategy, and acceptance validation across all phases of the product lifecycle. They collaborate with Product and Development to define testability requirements and measure quality against acceptance criteria.

### Responsibilities
- Define test strategy and QA approach (unit, integration, end-to-end, manual acceptance)
- Create and maintain test plans aligned to acceptance criteria
- Coordinate manual and automated testing across CI/CD pipelines
- Identify quality risks and propose testing mitigations
- Validate that features meet acceptance criteria before handoff to production
- Participate in release readiness reviews and smoke testing

### Goals
- Ensure products meet quality and usability standards before release
- Reduce defect escape and post-release incidents
- Enable fast, confident iteration through automated testing infrastructure

### Typical Communication
- Sprint planning (test approach definition)
- Daily standups (test progress and blockers)
- QA acceptance reviews before release
- Post-incident retrospectives

### Interaction with Existing Roles
- Works closely with **Developers** to understand feature implementation and coordinate testing activities
- Partners with **Product Managers** to clarify acceptance criteria and prioritize quality concerns
- Collaborates with **Project Managers** on test timelines and release readiness gates
- Coordinates with **Technical Leads** on test automation infrastructure and technical testing strategy

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, design oversight, and technical risk mitigation. They work across Product, Development, and Operations to ensure solutions are scalable, maintainable, and aligned to long-term technical strategy.

### Responsibilities
- Define technical approach and architecture for major initiatives
- Lead design reviews and provide guidance on technical trade-offs
- Identify and mitigate technical risks and dependencies
- Mentor developers and guide implementation best practices
- Collaborate with Product on feasibility and effort estimation
- Coordinate with Operations on scalability, performance, and monitoring requirements

### Goals
- Deliver scalable, maintainable solutions that support long-term product growth
- Reduce technical debt and prevent architectural debt accumulation
- Enable teams to make informed technical decisions quickly

### Typical Communication
- Technical design reviews and architecture discussions
- Risk assessment and mitigation planning
- Sprint planning (technical guidance on scope and approach)
- Cross-team coordination on integrations and dependencies

### Interaction with Existing Roles
- Mentors and guides **Developers** on architectural decisions and best practices
- Advises **Product Managers** on technical feasibility and effort implications during planning
- Supports **Project Managers** with technical risk identification and mitigation strategies
- Collaborates with **QA/Testing Leads** on testability and performance requirements
- Partners with **Operations/DevOps Engineers** on scalability and observability needs

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors are business leaders who authorize projects, commit resources, and represent executive-level priorities. They receive escalations on business-impacting issues and make go/no-go decisions at key project gates.

### Responsibilities
- Approve project business case and authorize resource commitment
- Provide executive visibility and alignment on strategic priorities
- Receive escalations for business-impacting risks and blockers
- Make trade-off and go/no-go decisions at project gates
- Support removal of organizational and cross-team blockers
- Validate that delivered outcomes align to business objectives

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment across competing priorities
- Remove organizational barriers to successful delivery

### Typical Communication
- Project approval and resource allocation meetings
- Monthly or milestone-based status updates
- Escalation reviews for business-impacting issues
- Project closeout and retrospective reviews

### Interaction with Existing Roles
- Receives project status and business impact summaries from **Project Managers**
- Aligns strategic priorities and resource decisions with **Product Managers**
- Escalates organizational blockers that impact **Project Managers**, **Developers**, and cross-functional teams
- Participates in project gate reviews to approve progression to next phases
- Validates business outcomes and ROI with **Product Managers** and **Project Managers** at project close

---

## Operations / DevOps Engineer

### Role Summary
Operations and DevOps Engineers own deployment automation, infrastructure provisioning, monitoring, and operational readiness. They work with Development and Product to ensure solutions are production-ready and observable.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Provision and manage infrastructure (staging, production environments)
- Define and implement monitoring, alerting, and observability practices
- Validate deployment readiness and execute production deployments
- Support incident response and post-incident automation improvements
- Plan and test rollback procedures and disaster recovery

### Goals
- Enable safe, fast, and automated deployments to production
- Maintain high system reliability, observability, and incident response capability
- Reduce mean time to recovery (MTTR) for production issues

### Typical Communication
- Release planning (deployment window scheduling and readiness)
- Pre-release verification (smoke testing and infrastructure checks)
- Incident response (deployment decisions, rollback execution)
- Monitoring and observability dashboard reviews

### Interaction with Existing Roles
- Supports **Developers** with CI/CD pipeline setup, deployment tooling, and infrastructure resources
- Works with **Project Managers** on deployment scheduling and release planning
- Collaborates with **Technical Leads** on infrastructure architecture and performance requirements
- Partners with **QA/Testing Leads** on environment provisioning and smoke testing coordination
- Coordinates with **Security/Compliance Officers** on infrastructure security and compliance validation

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that products and processes meet security, privacy, and regulatory standards. They provide security review, threat assessment, and incident response coordination.

### Responsibilities
- Review security architecture and identify vulnerabilities
- Define security scanning and validation requirements in CI/CD
- Conduct threat assessments and security risk modeling
- Coordinate security incident response and triage
- Ensure compliance with regulatory and privacy standards
- Provide security guidance and best practice recommendations

### Goals
- Deliver secure products that protect customer data and privacy
- Reduce security vulnerabilities and incident risk
- Maintain regulatory compliance and stakeholder trust

### Typical Communication
- Security reviews during planning and design phases
- Security incident coordination and escalation
- Risk register reviews (security-related risks)
- Release readiness checks (security scanning results)

### Interaction with Existing Roles
- Advises **Developers** on secure coding practices and security testing requirements
- Collaborates with **Product Managers** on privacy requirements and compliance implications
- Supports **Project Managers** with security risk identification and escalation processes
- Partners with **Technical Leads** on architectural security and threat modeling
- Coordinates with **Operations/DevOps Engineers** on infrastructure security controls and monitoring
- Works with **QA/Testing Leads** on security testing strategy and vulnerability validation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interaction with Existing Roles" sections to understand cross-functional dependencies and handoff points throughout the project lifecycle.
