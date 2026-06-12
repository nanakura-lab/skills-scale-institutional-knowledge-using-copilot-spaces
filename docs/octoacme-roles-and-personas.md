# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Project Roles

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

#### Cross-functional Collaboration
- **With DevOps Engineers**: Discuss deployment requirements, automation policies, and infrastructure dependencies
- **With UX Designers**: Clarify technical feasibility of design concepts, implement UI/UX specifications
- **With Data Analysts**: Define data collection requirements and performance metrics
- **With Security Teams**: Incorporate security requirements into implementation, participate in security reviews

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

#### Cross-functional Collaboration
- **With UX Designers**: Define user requirements, validate design decisions, prioritize features based on user impact
- **With Data Analysts**: Establish KPIs, interpret metrics, inform prioritization decisions
- **With Security Teams**: Understand security constraints, incorporate compliance requirements into roadmap

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

#### Cross-functional Collaboration
- **With DevOps Engineers**: Align on deployment schedules, resolve infrastructure-related delays
- **With Security Teams**: Incorporate security review cycles into timelines, manage compliance-related risks
- **With Data Analysts**: Track project metrics, measure delivery impact

---

## Extended Roles (Supporting Project Success)

### UX Designers

#### Role Summary
UX Designers create intuitive, user-centered experiences by conducting research, designing interfaces, and validating solutions with users. They bridge user needs with technical implementation.

#### Responsibilities
- Conduct user research and create personas/journey maps
- Design wireframes, prototypes, and high-fidelity mockups
- Lead usability testing and gather user feedback
- Collaborate on design systems and component specifications
- Advocate for user needs in trade-off discussions
- Document design decisions and maintain design documentation

#### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support adoption
- Establish consistent design patterns across products

#### Typical Communication
- Design critiques and feedback sessions
- Prototype reviews with stakeholders
- Design specifications and component libraries
- Usability test findings and recommendations

#### Cross-functional Collaboration
- **With Product Managers**: Translate user needs into product requirements, prioritize features based on user impact
- **With Developers**: Ensure technical feasibility of designs, provide detailed implementation specs, support accessibility standards
- **With Data Analysts**: Understand user behavior patterns, validate design impact through metrics

---

### Data Analysts

#### Role Summary
Data Analysts measure project success, inform decision-making through insights, and establish performance baselines. They provide data-driven perspective to prioritization and optimization efforts.

#### Responsibilities
- Define success metrics and KPIs aligned with project goals
- Analyze product/project data to measure outcomes
- Create dashboards and reports for stakeholders
- Identify trends, anomalies, and optimization opportunities
- Support A/B testing and experimentation
- Document analytical methodologies and findings

#### Goals
- Enable data-driven decision-making across teams
- Provide actionable insights on product performance
- Establish measurement frameworks for continuous improvement

#### Typical Communication
- Weekly/bi-weekly metric reviews
- Dashboard updates and KPI tracking
- Analysis reports and recommendations
- Experimentation design and results review

#### Cross-functional Collaboration
- **With Product Managers**: Define metrics that matter, translate insights into prioritization decisions
- **With Developers**: Understand data collection implementation, resolve data quality issues, measure technical performance
- **With Project Managers**: Track project-level metrics, measure delivery impact, support business case validation

---

### DevOps Engineers

#### Role Summary
DevOps Engineers bridge development and operations by building, maintaining, and optimizing CI/CD pipelines, infrastructure, and deployment processes. They ensure reliable, scalable, and observable systems.

#### Responsibilities
- Design and implement CI/CD pipelines
- Manage infrastructure, environments (dev/staging/prod), and deployment automation
- Monitor application performance, availability, and security
- Respond to incidents and drive reliability improvements
- Document deployment procedures and runbooks
- Collaborate on performance optimization and cost efficiency

#### Goals
- Enable fast, safe, reliable deployments
- Minimize downtime and reduce mean time to recovery (MTTR)
- Maintain infrastructure cost efficiency and security

#### Typical Communication
- Deployment coordination and release schedules
- Infrastructure and performance reviews
- Incident reports and post-mortems
- CI/CD pipeline status and optimization updates

#### Cross-functional Collaboration
- **With Developers**: Define deployment standards, provide deployment automation, troubleshoot environment issues
- **With Project Managers**: Align deployment schedules with release timelines, communicate infrastructure constraints
- **With Security Teams**: Implement security scanning in pipelines, manage infrastructure security, participate in security reviews

---

### Security Teams

#### Role Summary
Security Teams protect the organization by defining security requirements, assessing risks, conducting security reviews, and ensuring compliance. They are integrated throughout the project lifecycle.

#### Responsibilities
- Define security requirements and compliance standards
- Conduct threat modeling and risk assessments
- Perform security code reviews and penetration testing
- Configure security scanning in CI/CD pipelines
- Investigate and remediate security vulnerabilities
- Provide security training and guidance to teams
- Manage incident response and post-incident reviews

#### Goals
- Prevent security breaches and protect customer data
- Maintain compliance with regulatory requirements
- Foster a security-first development culture
- Reduce security-related incidents and their impact

#### Typical Communication
- Security requirement definitions and guidelines
- Threat models and risk assessments
- Security review findings and remediation tracking
- Incident alerts and response coordination
- Security training and awareness updates

#### Cross-functional Collaboration
- **With Developers**: Review security design decisions, conduct code reviews, provide secure coding guidance
- **With Project Managers**: Incorporate security review cycles into project timelines, escalate critical vulnerabilities
- **With DevOps Engineers**: Integrate security scanning into CI/CD, manage infrastructure security controls, coordinate incident response

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The cross-functional collaboration sections clarify how each role interacts with others, improving coordination and reducing silos.
- When creating project documentation, reference relevant personas to ensure all stakeholders understand their responsibilities and expected interactions.

---

## Persona Interaction Matrix

| Role | Primary Stakeholders | Key Touchpoints | Communication Frequency |
|------|---------------------|-----------------|--------------------------|
| **Developer** | Product Manager, UX Designer, DevOps, Security | Code reviews, design specs, deployment, security reviews | Daily standups, per-PR |
| **Product Manager** | Developers, UX Designer, Data Analyst, Stakeholders | Backlog prioritization, metrics review, roadmap | Weekly sync, sprint planning |
| **Project Manager** | All roles | Status tracking, risk management, scheduling | Weekly status, escalations as needed |
| **UX Designer** | Product Manager, Developers, Data Analyst | Design reviews, prototype feedback, usability testing | 2-3x weekly design reviews |
| **Data Analyst** | Product Manager, Developers, Project Manager | Metrics definition, dashboard reviews, analysis | Weekly/bi-weekly metric reviews |
| **DevOps Engineer** | Developers, Project Manager, Security | CI/CD updates, deployment coordination, infrastructure | Daily (as needed), release cycles |
| **Security Team** | Developers, Project Manager, DevOps | Security requirements, code/design reviews, incident response | Per-sprint planning, ongoing reviews |
