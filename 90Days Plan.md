# Optum 90-Day Detailed  Plan – AWS-to-AWS Cloud Migration

> **Disclaimer:** This is a very **generic plan**. Once I get access to the environments and meet with stakeholders, I will refine and update this plan accordingly.

---

## 1. Objectives
- Complete all **organizational onboarding formalities** and **mandatory trainings**.  
- Gain full **access to AWS environments**, tools, and internal systems.  
- Understand **current AWS infrastructure**, workloads, and migration goals.  
- Align with stakeholders across Cloud, Security, and Application teams.  
- Design and implement a **phased AWS-to-AWS migration plan**.  
- Deliver measurable progress — including initial migrations, automation setup, and compliance adherence — within the first 90 days.

---

## 2. Key Deliverables by 90 Days
- Approved AWS account and tool access  
- Completed compliance and AWS security trainings  
- Current and target state AWS architecture documentation  
- Migration strategy and execution roadmap   
- 90-day progress report and next-phase recommendations  

---

## 3. 90-Day Timeline Overview

| Phase | Duration | Focus |
|--------|-----------|--------|
| **Phase 1: Onboard & Discover** | Days 1–30 | Training, access setup,stakeholders Meetings, AWS environment analysis |
| **Phase 2: Plan & Design** | Days 31–60 | AWS migration strategy  |
| **Phase 3: Execute & Optimize** | Days 61–90 | Initial AWS migrations, performance tuning, and review |

---

## 4. Detailed 90-Day Plan

### **Phase 1 (Days 1–30): Onboarding, Access & Discovery**

#### Week 1: Organizational Onboarding
- Complete **HR induction, IT orientation, and compliance training**.  
- Attend **AWS Security, Optum Cloud Governance, and Data Privacy** sessions.  
- Set up official tools: **Outlook, Teams, Jira, Confluence**.  
- Meet **reporting manager**, **Cloud PMO**, and **project stakeholders**.  
- Review Optum’s **AWS account hierarchy, policies, and tagging standards**.

#### Week 2: Access Requests & Environment Familiarization
- Raise access requests for:
  - AWS Console and CLI access (Production, Non-Prod accounts)  
  - AWS SSO and IAM permissions  
  - GitLab / ServiceNow / Confluence / Jira  
  - CloudWatch Dashboards and Cost Explorer  
  - VPN & internal AWS resources  
- Review **current AWS account structure**, VPC setup, and networking topology.  
- Meet **AWS Security and Networking teams** for access validation.  

#### Week 3: Technical Deep Dive
- Review **As-Is AWS architecture**, including EC2, RDS, S3, Lambda, and EKS resources.  
- Understand **inter-region and cross-account dependencies**.  
- Evaluate **data transfer mechanisms** (AWS DataSync, S3 Replication, Snowball, etc.).  
- Identify automation tools in use (Terraform, CloudFormation).  
- Document existing challenges, cost insights, and improvement opportunities.

#### Week 4: Stakeholder Alignment
- Conduct discussions with:
  - AWS Cloud Architects  
  - Security, Networking, and Compliance teams  
  - Application Owners & Product teams  
- Define **communication cadence** (daily stand-ups, weekly syncs).  
- Submit a **30-day summary report** covering findings, risks, and recommendations.  

**Deliverables (Phase 1):**
- Completed onboarding checklist  
- AWS access approvals  
- As-Is architecture documentation  
- Stakeholder engagement plan  

---

### **Phase 2 (Days 31–60): Planning, Design & POC**

#### Week 5–6: Strategy and Framework Definition
- Define **To-Be AWS architecture** with modernization goals.  
- Identify **migration type** (Lift-and-Shift, Replatform, or Refactor).  
- Define **target services** such as:
  - EC2 (with new instance families)  
  - S3 (cross-region replication or storage class optimization)  
  - RDS/Aurora (cross-account migration)  
  - EKS / ECS clusters for container workloads  
- Define automation stack:
  - **Terraform / CloudFormation** for provisioning  
  - **AWS Step Functions / Lambda / Airflow** for orchestration  
  - **AWS DataSync / DMS / Snowball** for data movement  
- Prepare **migration playbooks and cutover strategy**.

#### Week 7: Security, Compliance & Risk Planning
- Work with Security to ensure:
  - IAM role alignment and least-privilege policies  
  - Encryption (KMS) and logging (CloudTrail) in place  
  - VPC security, GuardDuty, and Config enabled  
  - Backup and DR plans tested (AWS Backup, Multi-AZ setup)  
- Document **risk and mitigation strategy**.

#### Week 8: Proof of Concept (POC)
- Identify 1–2 workloads (e.g., non-critical EC2 apps or RDS databases) for pilot migration.  
- Execute migration using AWS DMS / DataSync or re-deploy via Terraform.  
- Validate infrastructure, application performance, and rollback plan.  
- Record metrics — latency, cost impact, and stability.  

**Deliverables (Phase 2):**
- Target-state AWS architecture  
- Migration and automation strategy  
- POC completion report  
- Risk & mitigation documentation  
- Stakeholder-approved migration roadmap  

---

### **Phase 3 (Days 61–90): Execution, Optimization & Transition**

#### Week 9–10: Controlled Migration
- Migrate initial workloads using approved AWS migration tools.  
- Validate DNS updates, IAM roles, and inter-region data access.  
- Test latency, throughput, and data integrity.  
- Collaborate with QA and Application teams for smoke testing.  

#### Week 11: Monitoring & Optimization
- Implement **CloudWatch dashboards** and **Cost Explorer reports**.  
- Use **AWS Trusted Advisor** and **Compute Optimizer** for performance tuning.  
- Identify **cost-saving opportunities** (e.g., Reserved Instances, S3 lifecycle policies).  
- Create **Standard Operating Procedures (SOPs)** for migration operations.  

#### Week 12: Review, Closure & Handover
- Conduct **90-day performance review** and prepare final documentation.  
- Present migration outcomes to leadership with metrics and lessons learned.  
- Define **next-phase roadmap** (scaling to critical workloads).  
- Conduct **knowledge-sharing sessions** with extended Clou
