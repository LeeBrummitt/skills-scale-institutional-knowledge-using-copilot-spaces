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

## Additional Operational Personas

The following personas represent critical cross-functional and operational roles that become increasingly important during planning, execution, release, and post-release phases. Engaging these roles early and clearly defining their responsibilities reduces handoff ambiguity, speeds decision-making, and improves project outcomes.

### When to Engage
- **Initiation & Planning**: Security & Compliance Owner, Data / Analytics Owner, UX Researcher
- **Execution**: Technical Lead, UX Researcher, Data / Analytics Owner
- **Release**: Release/Platform Engineer, Security & Compliance Owner, Data / Analytics Owner
- **Post-Release**: Support Liaison, Data / Analytics Owner, Release/Platform Engineer

---

## Technical Lead

### Role Summary
Technical Leads translate product requirements into technical architecture and strategy. They own design decisions, identify technical risks, mentor the development team, and ensure quality standards are maintained throughout implementation.

### Responsibilities
- Translate product requirements into a clear technical approach and architecture
- Own or co-own architecture and design decisions for the feature or system
- Identify and surface technical risks, trade-offs, and dependencies early
- Mentor and guide developers during implementation
- Coordinate technical design reviews and design-for-testability activities
- Ensure non-functional requirements (performance, scalability, maintainability) are addressed
- Contribute to estimation and sprint planning with technical insights

### Goals
- Deliver architecturally sound, maintainable solutions
- Reduce technical debt and rework
- Ensure team has clear technical direction and mentorship
- Build scalable, observable systems

### Typical Communication
- Design review meetings and technical discussions with developers
- Risk escalation to PM on technical trade-offs and scope impact
- Collaboration with QA/Testing on non-functional acceptance criteria
- Technical documentation and decision logs

### Interactions
- **With Developers**: Guides implementation, reviews code, mentors on best practices
- **With PM/PdM**: Discusses trade-offs, scope impact, and timeline implications of technical decisions
- **With QA/Testing**: Defines non-functional requirements and testability strategies
- **With Release Engineer**: Communicates deployment considerations and infrastructure requirements

---

## Release / Platform Engineer

### Role Summary
Release/Platform Engineers design, build, and maintain CI/CD pipelines, deployment automation, and infrastructure consistency. They ensure reliable, repeatable releases with minimal risk and enable rapid feedback loops for the team.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage release processes, versioning, and deployment strategies
- Automate testing, security scanning, and code quality checks in CI
- Document and execute rollback and mitigation plans
- Ensure environment consistency (dev, staging, production)
- Advise teams on deployment windows, risk assessment, and incident response
- Coordinate with SRE/On-call for production deployment and monitoring

### Goals
- Enable fast, safe, repeatable releases
- Minimize deployment failures and rollback scenarios
- Reduce time from commit to production
- Maintain infrastructure reliability and consistency

### Typical Communication
- Release readiness reports and deployment schedules
- CI/CD runbooks and troubleshooting guides
- Coordination with developers on test requirements and artifact management
- Incident and rollback communications with PM and on-call teams

### Interactions
- **With Developers**: Ensures build artifacts are properly created, tests are integrated into CI, and deployment requirements are documented
- **With QA/Testing**: Validates release readiness and post-deploy smoke tests
- **With PM**: Advises on deployment windows, risk mitigation, and timeline feasibility
- **With SRE/On-call**: Coordinates production deployments and incident response

---

## Support / Customer Success Liaison

### Role Summary
Support/Customer Success Liaisons represent the voice of customers and support teams in the project lifecycle. They ensure customer-facing impacts are understood, communicate feature changes to end users, and triage post-release issues to maintain customer satisfaction.

### Responsibilities
- Represent customer-facing concerns and feedback during planning and execution
- Triage and prioritize post-release issues based on customer impact
- Own communication to customers, support teams, and CSMs about feature changes
- Ensure documentation and release notes are clear and customer-centric
- Gather post-release feedback and surface patterns to Product and Engineering
- Collaborate on support runbooks and troubleshooting guides
- Participate in incident response and customer communication during outages

### Goals
- Maximize customer satisfaction and adoption of new features
- Reduce support volume and escalations post-release
- Ensure smooth customer transitions and change management
- Build feedback loops from support back into product

### Typical Communication
- Customer communication templates and release notes
- Post-release feedback summaries
- Support runbooks and FAQ documents
- Escalation and incident response coordination with PM and Engineering

### Interactions
- **With PM/PdM**: Surface customer feedback, discuss feature priority, validate acceptance criteria
- **With Developers/QA**: Collaborate on reproducing customer-reported bugs and prioritizing fixes
- **With Release Engineer**: Coordinates customer communication timing with deployments
- **With Support teams**: Gathers feedback, disseminates release information, triages issues

---

## Data / Analytics Owner

### Role Summary
Data/Analytics Owners define success metrics, ensure proper instrumentation, and provide data-driven insights to measure impact and inform decisions. They are critical to understanding whether a feature achieves its intended outcomes.

### Responsibilities
- Define measurable success metrics aligned with project goals (from Project One-pager)
- Ensure instrumentation is in place to collect relevant data
- Validate data quality and completeness
- Create dashboards and reports for monitoring key signals
- Conduct post-release analysis and communicate impact findings
- Identify data gaps and recommend additional instrumentation
- Support A/B testing and experimentation strategies
- Advise on monitoring and alerting for key metrics

### Goals
- Enable data-driven decision making
- Demonstrate measurable impact of features and improvements
- Identify and address data quality issues early
- Support continuous improvement through metrics and feedback

### Typical Communication
- Metric definitions and instrumentation requirements (during planning)
- Dashboard reviews and weekly/post-release analytics summaries
- Data quality reports and gap analysis
- Recommendations for optimization based on usage patterns

### Interactions
- **With PdM**: Collaborates on metric definitions and success criteria
- **With Developers**: Ensures instrumentation is implemented correctly and efficiently
- **With PM**: Provides regular reporting on progress toward success metrics
- **With Support/CSM**: Shares usage and adoption insights to inform customer conversations

---

## Security & Compliance Owner

### Role Summary
Security & Compliance Owners identify security and regulatory requirements, conduct threat modeling, and ensure appropriate security controls and scans are applied throughout the project lifecycle.

### Responsibilities
- Identify security and compliance requirements based on scope and data sensitivity
- Conduct or coordinate threat modeling and security design reviews
- Ensure security scanning (SAST, DAST, dependency checks) is integrated into CI
- Review code changes and architecture for security vulnerabilities
- Ensure compliance with relevant standards (SOC 2, GDPR, HIPAA, etc. as applicable)
- Document security controls and risk mitigation strategies
- Communicate security risks and remediation plans clearly to stakeholders
- Participate in incident response for security-related incidents

### Goals
- Prevent security vulnerabilities and data breaches
- Maintain compliance with regulatory and organizational standards
- Build security into the feature from the start (shift-left)
- Enable rapid security incident response

### Typical Communication
- Threat model summaries and security review findings
- Security scanning results and remediation guidance
- Risk assessments and compliance documentation
- Security incident escalations and root cause analysis reports

### Interactions
- **With Developers**: Reviews code and provides guidance on secure coding practices
- **With Release Engineer**: Ensures security scanning is automated in CI and monitored in production
- **With PM**: Communicates security risks, trade-offs, and timeline impact
- **With Technical Lead**: Collaborates on secure architecture and design decisions

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers own the user research, design validation, and accessibility aspects of the project. They ensure features are usable, discoverable, and accessible to all users.

### Responsibilities
- Conduct user research to validate problem statements and design approaches
- Create prototypes and mockups to test design concepts with users
- Define acceptance criteria related to usability and user experience
- Ensure accessibility standards (WCAG) are met in implementation
- Review implementation for design fidelity and user experience quality
- Create or review design documentation and handoff artifacts
- Participate in post-release user feedback collection and analysis
- Recommend UX improvements based on usage data and feedback

### Goals
- Deliver features that are intuitive and valuable to users
- Ensure accessibility for all user segments
- Reduce support volume from user confusion or poor UX
- Build evidence-based design decisions

### Typical Communication
- Research findings and user insights (during initiation and planning)
- Design specifications and prototypes
- Accessibility compliance reports
- Post-release UX feedback summaries and improvement recommendations

### Interactions
- **With PdM**: Collaborates on acceptance criteria related to user experience and accessibility
- **With Developers**: Ensures implementation matches design intent and provides guidance on component behavior
- **With QA/Testing**: Validates usability and accessibility during testing
- **With Support/CSM**: Gathers user feedback and identifies common UX issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning a project, identify which personas should be engaged and at what phase.
- Use persona interaction patterns to design more effective communication and handoff points.
