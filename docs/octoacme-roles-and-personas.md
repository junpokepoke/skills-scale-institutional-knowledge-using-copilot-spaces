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

### Interaction with Other Roles
- **With Technical Lead**: Receive architectural guidance and design reviews
- **With QA/Testing Lead**: Collaborate on test strategy and acceptance criteria validation
- **With Product Managers**: Clarify requirements and acceptance criteria
- **With Project Managers**: Report progress and identify blockers

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

### Interaction with Other Roles
- **With Product Lead**: Align on strategic priorities and product direction
- **With Project Managers**: Coordinate delivery timelines and resource allocation
- **With Technical Lead**: Validate feasibility and discuss technical trade-offs
- **With Developers**: Define requirements and acceptance criteria

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

### Interaction with Other Roles
- **With Product Managers**: Coordinate priorities and timeline alignment
- **With Technical Lead**: Monitor technical risks and dependencies
- **With Release/DevOps Engineer**: Plan deployment windows and rollback strategies
- **With Sponsor**: Escalate business-impacting issues and resource needs

---

## Technical Lead

### Role Summary
Technical Leads own the system architecture and technical strategy for projects. They ensure designs are scalable, maintainable, and aligned with organizational standards. They collaborate with Product Managers to validate feasibility and with Developers to guide implementation.

### Responsibilities
- Design system architecture and technical approach
- Review and validate technical design documents and PRs
- Identify technical risks and propose mitigations
- Mentor developers and support capability building
- Participate in capacity planning and estimation
- Ensure alignment with architectural standards and security requirements

### Goals
- Deliver technically sound solutions that scale with business needs
- Reduce technical debt while maintaining velocity
- Build a culture of code quality and continuous learning

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Weekly planning and risk discussions with PM and Project Manager
- Post-release retrospectives on technical learnings

### Interaction with Other Roles
- **With Developers**: Provide architectural guidance, review designs, unblock technical challenges
- **With Product Managers**: Validate feasibility, identify technical trade-offs, estimate effort
- **With Project Managers**: Flag technical risks, support dependency mapping, participate in planning
- **With QA/Testing Lead**: Ensure test strategy aligns with architecture, support test planning

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and test planning for projects. They ensure features meet acceptance criteria and quality standards before release. They collaborate with Developers and Technical Leads to define test approaches and validate solutions.

### Responsibilities
- Develop comprehensive test plans and quality strategies
- Validate acceptance criteria and Definition of Done
- Coordinate manual and automated testing efforts
- Identify quality risks and propose mitigation approaches
- Oversee end-to-end, integration, and performance testing
- Participate in release readiness assessments

### Goals
- Ensure high product quality and user satisfaction
- Reduce defects reaching production
- Establish measurable quality metrics and standards

### Typical Communication
- Test plan reviews and quality discussions
- QA status updates in weekly syncs
- Test case walkthroughs and validation sessions
- Release readiness reports

### Interaction with Other Roles
- **With Developers**: Collaborate on test coverage and acceptance criteria validation
- **With Technical Lead**: Align test strategy with architecture and performance requirements
- **With Product Managers**: Clarify acceptance criteria and feature requirements
- **With Project Managers**: Report quality status and escalate blockers

---

## Product Lead

### Role Summary
Product Leads coordinate product strategy across multiple initiatives and provide strategic guidance to Product Managers and Project Managers. They ensure alignment between customer needs, business objectives, and technical capabilities.

### Responsibilities
- Define overall product strategy and vision
- Align priorities across multiple projects and teams
- Provide mentorship and guidance to Product Managers
- Communicate product direction to stakeholders
- Monitor product metrics and business impact
- Make strategic trade-offs between features and capabilities

### Goals
- Maximize product-market fit and business impact
- Ensure consistent product strategy across initiatives
- Build a high-performing product organization

### Typical Communication
- Monthly strategic reviews with leadership
- Weekly alignment with Product Managers and Project Managers
- Quarterly roadmap and strategy updates
- Cross-team collaboration sessions

### Interaction with Other Roles
- **With Product Managers**: Provide strategic direction and mentorship
- **With Project Managers**: Ensure project alignment with product strategy
- **With Sponsor**: Report on product performance and strategic progress
- **With Technical Lead**: Discuss technical feasibility of strategic initiatives

---

## Release/DevOps Engineer

### Role Summary
Release/DevOps Engineers manage deployment pipelines, infrastructure, and release orchestration. They ensure reliable, repeatable deployments and maintain system observability and stability.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Coordinate release scheduling and deployment windows
- Manage rollback and incident response procedures
- Monitor system performance and health metrics
- Ensure security and compliance in deployment processes
- Support environment setup and configuration management

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment risk and downtime
- Maintain high system availability and performance

### Typical Communication
- Release planning and deployment scheduling
- Infrastructure and pipeline status reports
- Post-deployment verification and monitoring
- Incident response coordination

### Interaction with Other Roles
- **With Project Managers**: Coordinate release timing and deployment windows
- **With Developers**: Support CI/CD pipeline integration and troubleshooting
- **With Technical Lead**: Ensure infrastructure aligns with architectural requirements
- **With Security/Compliance Officer**: Implement security controls in deployment processes

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors are executive-level stakeholders who provide business context, funding, and strategic alignment for projects. They remove blockers, secure resources, and ensure projects align with organizational priorities.

### Responsibilities
- Provide business context and strategic alignment
- Secure funding and resources for projects
- Remove organizational blockers and obstacles
- Receive status updates and escalations
- Make business-level trade-off decisions
- Communicate project outcomes to leadership

### Goals
- Ensure projects deliver business value
- Maintain alignment with organizational strategy
- Enable teams to execute efficiently

### Typical Communication
- Monthly executive status updates
- Ad-hoc escalation for business-impacting decisions
- Resource allocation and planning meetings
- Post-release business impact reviews

### Interaction with Other Roles
- **With Project Managers**: Receive escalations and provide guidance on resource constraints
- **With Product Lead**: Align on strategic priorities and business objectives
- **With Technical Lead**: Make decisions on technical trade-offs with business impact
- **With Security/Compliance Officer**: Address compliance and risk management concerns

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet security, privacy, and regulatory requirements. They provide guidance on secure design practices and ensure compliance throughout the project lifecycle.

### Responsibilities
- Review designs for security and compliance implications
- Conduct security assessments and threat modeling
- Ensure data privacy and regulatory compliance
- Coordinate security testing and vulnerability management
- Develop and maintain security policies and standards
- Participate in incident response and post-incident reviews

### Goals
- Protect organizational and customer data
- Ensure compliance with regulatory requirements
- Build security awareness across the organization

### Typical Communication
- Security design reviews and threat modeling sessions
- Compliance audit and assessment reports
- Security incident notifications and response coordination
- Policy and standard updates

### Interaction with Other Roles
- **With Technical Lead**: Review architecture for security implications
- **With Developers**: Provide secure coding guidance and training
- **With Release/DevOps Engineer**: Ensure secure deployment practices
- **With Project Managers**: Flag security and compliance risks
- **With Sponsor**: Escalate critical security or compliance issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
