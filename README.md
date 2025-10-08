# Optum 90-Day Detailed Manager Plan – Cloud-to-Cloud Migration

## Executive Summary
This document outlines a comprehensive 90-day onboarding and execution plan for the role of **Manager – Cloud Migration** at **Optum**.  
The plan includes onboarding activities, access management, mandatory trainings, stakeholder alignment, and structured delivery of the Cloud-to-Cloud Migration project.  
The focus is to establish a solid foundation for managing end-to-end migration initiatives, ensuring security, scalability, and business continuity.

---

## 1. Objectives
- Complete all organizational onboarding formalities and mandatory trainings.
- Gain full access to required tools, systems, and environments.
- Understand existing cloud infrastructure and migration strategy.
- Align with stakeholders and build a capable cross-functional team.
- Design, plan, and begin execution of Cloud-to-Cloud migration in a phased, secure manner.
- Deliver measurable outcomes within the first 90 days.

---

## 2. Key Deliverables by 90 Days
- Approved access to all necessary tools and cloud environments.
- Completed compliance and security trainings.
- Current and target state architecture documentation.
- Migration strategy and execution plan.
- Proof of Concept (POC) for initial workloads.
- Progress report and roadmap for next phase.

---

## 3. 90-Day Timeline Overview

| Phase | Duration | Focus |
|--------|-----------|--------|
| **Phase 1: Onboard & Discover** | Days 1–30 | Training, access setup, environment study |
| **Phase 2: Plan & Design** | Days 31–60 | Migration strategy and POC development |
| **Phase 3: Execute & Optimize** | Days 61–90 | Execute initial migration, optimize, and review |

---

## 4. Detailed 90-Day Plan

### **Phase 1 (Days 1–30): Onboarding, Access, and Discovery**

#### Week 1: Organizational Onboarding
- Complete **mandatory HR induction and IT orientation**.
- Attend **security awareness, compliance, and code of conduct** trainings.
- Complete **mandatory Optum Cloud Security and Data Privacy training**.
- Set up official email, communication tools (Teams, Outlook), and collaboration platforms (Jira, Confluence).
- Meet the **reporting manager and project stakeholders**.
- Review organizational hierarchy, policies, and team structures.

#### Week 2: Access Requests & Environment Familiarization
- Raise access requests for:
  - GCP / AWS / Azure environments (as applicable)
  - GitLab / GitHub repositories
  - ServiceNow or internal ticketing systems
  - Cloud Monitoring / Logging dashboards
  - VPN and internal cloud resources
- Meet with **IT Security** to ensure proper access control configuration.
- Review the **current project documentation** and migration history.
- Join **Optum Cloud Engineering CoP (Community of Practice)** sessions.

#### Week 3: Technical Deep Dive
- Review the **As-Is architecture** for source and target cloud systems.
- Understand data flow, network setup, storage classes, and integration dependencies.
- Identify key applications, databases, and data pipelines planned for migration.
- Document challenges, constraints, and any existing automation tools.

#### Week 4: Stakeholder Alignment
- Conduct one-on-one sessions with:
  - Cloud Architects
  - Security and Compliance leads
  - Data Engineering teams
  - Product and Business stakeholders
- Define communication cadence (weekly syncs, dashboards, reports).
- Prepare an **initial 30-day summary report** highlighting observations, risks, and recommendations.

**Deliverables (Phase 1):**
- Completed onboarding checklist  
- Access approvals  
- As-Is infrastructure report  
- Stakeholder alignment plan  

---

### **Phase 2 (Days 31–60): Planning, Design & POC Development**

#### Week 5–6: Strategy and Framework Definition
- Define **To-Be (future) architecture** for cloud-to-cloud integration.
- Identify **target services** (e.g., GCP BigQuery, AWS Redshift, Azure Synapse).
- Plan **migration strategy** — data transfer, synchronization, cutover approach.
- Define **tooling and automation** approach:
  - Terraform for provisioning
  - Cloud Composer / Airflow for orchestration
  - Dataflow / Dataproc for data movement
- Conduct feasibility assessment for **real-time vs batch data migration**.

#### Week 7: Security, Compliance & Risk Planning
- Collaborate with Security and Compliance teams to:
  - Review IAM policies and encryption standards.
  - Define backup and disaster recovery strategy.
  - Identify regulatory frameworks (HIPAA, GDPR) applicable to the data.
- Prepare **risk and mitigation plan** for migration.

#### Week 8: Proof of Concept (POC)
- Select 1–2 non-critical workloads for pilot migration.
- Execute the POC end-to-end:
  - Setup environment
  - Data migration
  - Validation and rollback
- Capture results, performance metrics, and lessons learned.

**Deliverables (Phase 2):**
- Target-state architecture documentation  
- Detailed migration strategy and POC results  
- Risk assessment and mitigation plan  
- Migration roadmap (approved by stakeholders)  

---

### **Phase 3 (Days 61–90): Execution, Optimization & Transition**

#### Week 9–10: Controlled Migration
- Begin phased migration of selected workloads.
- Use **migration automation tools** and validate data integrity.
- Monitor latency, throughput, and performance metrics.
- Validate application behavior in the target cloud environment.
- Conduct smoke and functional testing with QA teams.

#### Week 11: Monitoring & Optimization
- Implement **Cloud Monitoring dashboards** using Prometheus and Grafana.
- Track resource utilization, cost, and performance.
- Identify and optimize any performance bottlenecks.
- Initiate documentation for Standard Operating Procedures (SOPs).

#### Week 12: Review, Closure & Handover
- Conduct **90-day performance review** of migration activities.
- Prepare a comprehensive **status report and executive presentation**.
- Define **next-phase goals** and backlog items for upcoming quarters.
- Conduct **knowledge-sharing session** with extended teams.

**Deliverables (Phase 3):**
- Executed initial migrations  
- Performance monitoring dashboards  
- Optimization & feedback report  
- 90-Day completion report and future roadmap  

---

## 5. Tools & Platforms Required
- **Cloud:** GCP, AWS, Azure  
- **Automation:** Terraform, Ansible  
- **Data Transfer:** Cloud Data Transfer, Velostrata, Storage Transfer Service  
- **Monitoring:** Prometheus, Cloud Monitoring, Grafana  
- **Collaboration:** Jira, Confluence, Teams, GitLab  
- **Compliance:** Cloud KMS, VPC Service Controls, IAM  

---

## 6. KPIs & Success Metrics
| KPI | Goal | Target by Day 90 |
|------|------|----------------|
| Access Setup Completion | All required system access | 100% |
| Mandatory Trainings | Security, Compliance, Cloud | 100% |
| Architecture Documentation | As-Is and To-Be completed | 100% |
| POC Success Rate | Migration validation passed | 95% |
| Stakeholder Satisfaction | Positive feedback | ≥90% |
| Cost Optimization | Identified savings | 10–15% |

---

## 7. Risks & Mitigation
| Risk | Impact | Mitigation |
|------|---------|------------|
| Delayed access approvals | High | Raise requests early, track via ticketing |
| Unclear migration scope | Medium | Conduct discovery workshops |
| Data loss during migration | High | Implement rollback and backup plans |
| Skill gaps in team | Medium | Conduct targeted upskilling |
| Cost overruns | Medium | Monitor spend via billing dashboards |

---

## 8. Communication & Reporting Plan
| Frequency | Type | Audience |
|------------|------|-----------|
| Daily | Stand-up with core team | Project members |
| Weekly | Status update | Program stakeholders |
| Bi-Weekly | Migration committee review | Leadership |
| Monthly | Risk and cost summary | Senior Management |
| End of 90 Days | Final presentation | Executive Team |

---

## 9. Conclusion
The first 90 days as a Cloud Migration Manager at Optum will focus on establishing governance, securing system access, completing compliance requirements, and setting the foundation for a smooth and scalable Cloud-to-Cloud migration.  
By Day 90, the project will be ready for large-scale migration with proven frameworks, validated tools, and a well-aligned team.

---

**Prepared by:**  
**Chiranjeevi G**  
*Manager – Cloud Migration*  
*Optum*

