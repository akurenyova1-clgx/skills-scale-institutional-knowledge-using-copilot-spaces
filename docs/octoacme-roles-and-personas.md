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

## UX/UI Designer

### Role Summary
UX/UI Designers create intuitive, accessible interfaces and experiences. They translate product requirements into visual designs and interactive prototypes, ensuring the end product is usable and meets both user needs and accessibility standards.

### Responsibilities
- Design user interfaces and interaction flows
- Create wireframes, mockups, and interactive prototypes
- Conduct and synthesize usability testing
- Ensure designs meet accessibility standards (e.g., WCAG)
- Coordinate design reviews with stakeholders

### Goals
- Deliver clear, accessible, and user-validated designs
- Reduce rework by aligning designs with requirements early
- Maintain a consistent design language across the product

### Typical Communication / Interactions
- Works with **Product Managers** to translate requirements and success metrics into design solutions
- Collaborates with **Developers** to clarify design intent and support implementation
- Partners with **QA Lead** on usability testing and acceptance of UI acceptance criteria
- Presents design reviews to **Project Managers** and stakeholders at planning milestones

---

## QA Lead

### Role Summary
The QA Lead owns the overall quality strategy for a project. They coordinate test planning, manage test execution, champion test automation, and act as the primary escalation point for quality and defect-resolution decisions.

### Responsibilities
- Define and maintain the project's QA strategy and test plan
- Manage test case creation, test execution, and bug triage
- Champion and oversee test automation efforts
- Report test status and quality metrics to project leadership
- Review and validate acceptance criteria and Definition of Done

### Goals
- Ensure releases meet agreed quality standards before deployment
- Minimize defect escape rate to production
- Improve testing efficiency through automation

### Typical Communication / Interactions
- Collaborates closely with **Developers** for defect resolution and testability input during design and code reviews
- Reports test status and quality metrics to **Project Managers** for status tracking and risk decisions
- Reviews acceptance criteria and Definition of Done with **Product Managers**
- Coordinates with **DevOps Engineer** on test environment provisioning and CI pipeline integration
- Partners with **UX/UI Designer** on usability testing coverage

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain and optimize the delivery infrastructure that enables the team to build, test, and release software reliably. They own CI/CD pipelines, infrastructure as code, deployment automation, and reliability monitoring.

### Responsibilities
- Build, maintain, and optimize CI/CD pipelines
- Manage infrastructure as code and environment provisioning
- Automate deployment and rollback procedures
- Monitor system reliability and act on alerting signals
- Enforce security and compliance controls in the delivery pipeline

### Goals
- Enable fast, reliable, and repeatable software delivery
- Minimize deployment risk through automation and observability
- Ensure environment parity between development, staging, and production

### Typical Communication / Interactions
- Works with **Developers** on build failures, branching strategies, and release packaging
- Partners with **QA Lead** on test environment provisioning and pipeline-integrated test execution
- Informs **Project Managers** of deployment readiness, pipeline health, and infrastructure risks
- Coordinates with **Security Champion** to integrate security scanning and compliance gates into the pipeline

---

## Security Champion

### Role Summary
The Security Champion advocates for secure-by-design development practices throughout the project lifecycle. They lead threat modeling, ensure adherence to security standards, and serve as the first line of escalation for security concerns.

### Responsibilities
- Advocate for and educate the team on secure development practices
- Conduct or facilitate threat modeling sessions
- Review designs and code changes for security risks
- Ensure compliance with relevant security standards and regulations
- Support incident response and root-cause analysis for security events

### Goals
- Embed security early to reduce cost of remediation
- Minimize the attack surface of delivered features
- Build security awareness and capability across the delivery team

### Typical Communication / Interactions
- Educates and advises **Developers** on secure coding practices and vulnerability remediation
- Reviews feature designs and release plans with **Product Managers** and **DevOps Engineers** to surface security considerations
- Escalates unresolved security risks to **Project Managers** for risk register tracking and leadership decisions
- Collaborates with **DevOps Engineer** on security scanning gates in CI/CD pipelines

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They gather, clarify, and document requirements, model business processes, and ensure traceability from business need to delivered solution.

### Responsibilities
- Gather and clarify requirements through stakeholder interviews and workshops
- Model and document business processes and user journeys
- Maintain requirements traceability from business need to acceptance criteria
- Facilitate prioritization discussions and trade-off analysis
- Validate that delivered functionality meets business intent

### Goals
- Ensure requirements are complete, unambiguous, and actionable before development begins
- Reduce late-stage rework by surfacing misalignments early
- Maintain clear traceability between business goals and delivered features

### Typical Communication / Interactions
- Works closely with **Product Managers** to translate business goals into well-defined features and acceptance criteria
- Coordinates with **Developers** on technical feasibility and to clarify requirements during implementation
- Supports **QA Lead** in validating that test cases and acceptance criteria correctly reflect business logic
- Facilitates stakeholder workshops and requirements reviews coordinated with **Project Managers**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

