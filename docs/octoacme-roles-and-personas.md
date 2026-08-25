# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **With Technical Lead**: Receives technical guidance, participates in design reviews
- **With Product Managers**: Clarifies requirements and acceptance criteria
- **With Project Managers**: Reports progress and blockers
- **With QA/Testing**: Coordinates on test approach and quality handoff
- **With Release Engineer**: Collaborates on deployment readiness

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **With Project Managers**: Aligns on priorities and timelines
- **With Developers**: Discusses requirements and technical constraints
- **With Technical Lead**: Collaborates on technical trade-offs
- **With Executive Sponsor**: Receives business context and strategic guidance

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **With Product Managers**: Coordinates priorities and scope changes
- **With Developers**: Tracks progress and identifies blockers
- **With Technical Lead**: Escalates technical risks and dependency issues
- **With Executive Sponsor**: Escalates business-impacting blockers
- **With Release Engineer**: Coordinates deployment schedules

---

## Cross-functional & Specialized Roles

### Technical Lead / Architect

#### Role Summary
The Technical Lead provides architectural direction, ensures technical quality standards, and makes or approves critical technical decisions that affect project scope, schedule, or quality. This role is essential for complex projects where technical decisions have broad impact.

#### Responsibilities
- Define or approve technical architecture and design patterns
- Conduct technical design reviews before implementation
- Identify technical risks and propose mitigation strategies
- Ensure code quality standards and test coverage expectations
- Mentor developers and promote technical best practices
- Work with Product Managers to translate technical constraints into scope discussions
- Advise on technology choices, scalability, and maintainability

#### Goals
- Maintain high technical standards and code quality
- Reduce technical debt and architectural risk
- Enable team growth through mentorship and knowledge sharing
- Ensure solutions are scalable and maintainable long-term

#### Typical Communication
- Technical design reviews and architecture discussions
- 1-on-1 mentoring sessions with developers
- Risk registers and technical trade-off documents
- Code review comments and design feedback

#### Key Interactions
- **With Developers**: Sets technical standards, reviews complex designs, guides implementation approaches
- **With Project Managers**: Flags technical risks early, provides estimates and complexity assessments
- **With Product Managers**: Translates technical constraints into product trade-offs
- **With QA/Testing**: Collaborates on test strategy and quality acceptance criteria
- **With Security Engineer**: Coordinates on secure architecture and design patterns

---

### Design/UX Lead

#### Role Summary
The Design/UX Lead ensures that project outcomes meet user needs, align with design systems, and deliver excellent user experience. They collaborate with product and development teams to validate design decisions and usability.

#### Responsibilities
- Conduct user research and define user needs and personas
- Create wireframes, prototypes, and design specifications
- Validate design decisions through usability testing
- Ensure alignment with design systems and brand standards
- Review acceptance criteria for usability and accessibility requirements
- Collaborate with developers on implementation of design specifications

#### Goals
- Deliver intuitive, accessible user experiences
- Ensure consistency with design systems
- Minimize rework through early validation
- Balance user needs with technical constraints

#### Typical Communication
- Design review sessions and feedback discussions
- User research findings and testing reports
- Design specifications and component documentation
- Sprint planning to align on design-related requirements

#### Key Interactions
- **With Product Managers**: Collaborates on requirements and user needs
- **With Developers**: Ensures accurate implementation of design specifications
- **With QA/Testing**: Validates usability and accessibility criteria
- **With Project Managers**: Communicates design dependencies and timeline impacts

---

### Release / Operations Engineer

#### Role Summary
The Release Engineer owns deployment processes, infrastructure coordination, and production readiness. They ensure smooth, low-risk transitions from development to production and maintain operational excellence.

#### Responsibilities
- Design and maintain deployment pipelines and automation
- Coordinate and execute production deployments
- Maintain runbooks and rollback procedures
- Monitor post-deployment health and troubleshoot issues
- Collaborate with infrastructure and security on environment setup
- Provide deployment readiness checklists and pre-release validation
- Track deployment metrics and optimize release processes

#### Goals
- Enable fast, reliable deployments with minimal risk
- Reduce time-to-production while maintaining quality
- Maintain high system availability and incident response readiness
- Automate repetitive deployment tasks

#### Typical Communication
- Deployment coordination and release notes
- Post-deployment monitoring and incident response
- Runbook documentation and process improvements
- Pre-release readiness meetings with stakeholders

#### Key Interactions
- **With Developers**: Reviews code for deployment-related considerations, coordinates release timing
- **With Product Managers**: Communicates deployment windows and release readiness
- **With QA/Testing**: Ensures smoke tests are executable in production, validates rollback procedures
- **With Project Managers**: Provides deployment status and escalates blockers
- **With Security Engineer**: Coordinates on security scanning gates and deployment approvals

---

### Security Engineer

#### Role Summary
The Security Engineer ensures that projects meet security standards, conducts threat analysis, and manages security compliance throughout the project lifecycle. They partner with teams to embed security early and reduce vulnerability risk.

#### Responsibilities
- Conduct security threat analysis during planning phase
- Review code and architecture for security vulnerabilities
- Configure and monitor security scanning in CI/CD pipelines
- Manage secrets, access control, and compliance requirements
- Coordinate security incident response and post-mortem analysis
- Advise on secure coding practices and dependency management
- Validate security acceptance criteria and compliance requirements

#### Goals
- Prevent security vulnerabilities and breaches
- Ensure compliance with security standards and regulations
- Embed security practices across the team
- Respond quickly to security incidents with minimal impact

#### Typical Communication
- Security reviews and threat analysis reports
- Vulnerability scanning results and remediation guidance
- Incident response coordination and post-mortems
- Security training and best practice documentation

#### Key Interactions
- **With Developers**: Reviews code for vulnerabilities, advises on secure implementation
- **With Product Managers**: Collaborates on security requirements and compliance trade-offs
- **With Technical Lead**: Ensures secure architecture and design patterns
- **With Release Engineers**: Ensures security scanning gates are enforced in deployment pipelines
- **With Project Managers**: Escalates security blockers and compliance risks

---

### Scrum Master / Agile Coach

#### Role Summary
The Scrum Master facilitates agile ceremonies, removes blockers to team efficiency, and coaches the team on process adherence and continuous improvement. This role is essential for maintaining team velocity and health.

#### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and help resolve team blockers and impediments
- Coach team on agile practices and ceremonies
- Track team velocity and burndown metrics
- Facilitate communication and conflict resolution
- Support process improvements and experimentation
- Ensure retrospective action items are tracked and completed

#### Goals
- Maximize team velocity and productivity
- Maintain team morale and psychological safety
- Enable continuous process improvement
- Remove organizational obstacles to team effectiveness

#### Typical Communication
- Daily standups and sprint ceremonies
- 1-on-1 coaching sessions with team members
- Blocker and action item tracking
- Retrospective summaries and improvement recommendations

#### Key Interactions
- **With Project Managers**: Escalates blockers and process impediments
- **With All Team Members**: Facilitates ceremonies, removes obstacles, coaches on process
- **With Product Managers**: Ensures product backlog is well-refined and prioritized

---

### Executive Sponsor

#### Role Summary
The Executive Sponsor provides business context, approves major milestones, and serves as the highest level of escalation authority for business-impacting decisions. They ensure organizational alignment and remove strategic blockers.

#### Responsibilities
- Define business objectives and success metrics
- Approve or reject project proposals and major scope changes
- Remove organizational blockers (e.g., resource allocation, cross-team dependencies)
- Participate in project kickoff and major milestone reviews
- Serve as escalation point for business-level risks and trade-offs
- Communicate project outcomes to broader organization
- Align project with organizational strategy and priorities

#### Goals
- Ensure projects deliver business value
- Minimize business risk and maximize ROI
- Enable cross-functional collaboration and alignment
- Communicate project value to stakeholders

#### Typical Communication
- Project kickoff and milestone reviews
- Escalation calls for business-impacting decisions
- Executive status updates and business outcome reports
- Strategic planning and alignment meetings

#### Key Interactions
- **With Project Managers**: Receives escalations, approves milestone changes
- **With Product Managers**: Aligns on business priorities and trade-offs
- **With Stakeholders**: Communicates business value and project status

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- Tailor engagement based on project complexity: simpler projects may combine roles, while larger initiatives require dedicated specialists
- Use the "Key Interactions" sections to understand communication patterns and dependencies
