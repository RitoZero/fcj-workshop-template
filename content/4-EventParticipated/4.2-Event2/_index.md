---
title: "Event 2"
date: 2026-07-11
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Event Report: “SLA, Monitoring, Automated Security with AWS Security Agent & AWS Certification Pathways”

### Event Objectives

- Understand the significance of SLAs (Service Level Agreements) and how to design a comprehensive monitoring strategy ranging from infrastructure to end-user experience.
- Explore advanced automated security solutions using **AWS Security Agent** powered by Amazon Bedrock across the entire software development lifecycle.
- Provide a clear overview and structural breakdown of the core knowledge domains for the foundational **AWS Cloud Practitioner** certification exam.

### List of Speakers

- Industry experts and guest speakers from the tech community sharing insights on systems management, cloud security, and AWS certification roadmaps.

### Key Highlights

#### 1. SLA and Monitoring — From SLA to Monitoring What Really Matters

- **SLA (Service Level Agreement)**: A formal commitment defining service expectations between a provider and a customer, establishing clear expectations, accountability, performance measurement, and risk management.
- **The Role of Monitoring**: Embedded within risk management to detect issues early before impacting SLAs. The standard workflow includes: Risk Identification → Signal Collection (metrics, logs, alarms) → Reaction (SNS notifications, SOPs, system recovery) → Improvement (post-incident evaluation and tuning to prevent recurrence).
- **The Monitoring Pyramid Model**:
  - **Customer Experience (Pyramid Peak)**: Actual end-user experience.
  - **Business**: Successful login rates, order volumes, revenue.
  - **Application**: Latency, error rates, request volumes.
  - **Infrastructure**: CPU, memory, disk, and network resource states.
  - **Cloud Provider (Pyramid Base)**: Core service statuses for EC2, RDS, ALB, S3.
- **Practical Takeaways**:
  - *Healthy infrastructure ≠ Happy users*: A passing health check does not guarantee a smooth user experience; infrastructure alone does not tell the whole story.
  - Cloud providers are responsible for cloud infrastructure, but we remain fully responsible for the end-user experience.

#### 2. Securing Your Web Apps With AWS Security Agent

- **Bottlenecks in Traditional Testing**: Traditional manual pentesting takes weeks, incurs high costs ($5,000–$20,000), and heavily relies on the pentester's expertise.
- **The Frontier Agent (AWS Security Agent)**:
  - Powered by Amazon Bedrock, capable of self-planning and executing complex security tasks without human intervention.
  - Validates vulnerabilities through active exploitation: analyzing architecture documents against standards (PCI DSS, NIST CSF, AWS Well-Architected), auto-scanning PRs for exposed secrets/API keys, and simulating multi-step attacks.
- **Full Lifecycle Protection**: Spans Design Review, Code Security, and Active Penetration Testing, with direct integration into GitHub/GitLab Pull Requests providing Auto-PR Fixes.
- **Limitations to Consider**: Disrupted by complex authentication mechanisms (MFA, Biometrics, mTLS), struggles with business logic flaws lacking deep context, and execution time increases with application complexity.

#### 3. Inside The Exam — AWS Cloud Practitioner

- **Certification Nature**: A foundational certification focusing on cloud mindset and the high-level overview of AWS Cloud, requiring no deep coding or advanced configuration skills.
- **Four Knowledge Domains**:
  - **Domain 1**: Cloud Concepts (24%).
  - **Domain 2**: Security and Compliance (30%).
  - **Domain 3**: Cloud Technology and Services (34%).
  - **Domain 4**: Billing, Pricing, and Support (12%).

### What Was Learned

#### Monitoring & Operational Management Mindset

- Understood the direct correlation between SLAs and system risk management strategies.
- Mastered the Monitoring Pyramid framework to prioritize tracking from actual user experiences down to cloud infrastructure layers.

#### Cybersecurity & AI-Driven Security Mindset

- Explored comprehensive automated security models (Full Lifecycle) by integrating intelligent assistants like AWS Security Agent into CI/CD pipelines.
- Recognized the boundaries of automated tools to seamlessly combine them with human expertise in complex scenarios.

### Application to Work

- **Implementing Multi-Layer Monitoring**: Configure alerts and metric tracking aligned with the Monitoring Pyramid model to optimize user experience.
- **Integrating Automated Security Checks**: Adopt automated vulnerability scanning tools directly into daily software development workflows.
- **Enhancing Cloud Foundations**: Direct study and review efforts toward the core knowledge domains outlined in the AWS Cloud Practitioner certification blueprint.

### Event Experience

#### Expert Perspectives
- Listened to in-depth insights on establishing Service Level Agreements (SLAs) and practical monitoring practices in enterprise environments.
- Updated on the latest trends in applying AI to cybersecurity and vulnerability testing.

#### Core Takeaways
- Monitoring must go beyond infrastructure tracking by centering on the end-user experience.
- Cybersecurity needs to be automated early in the software design and development phases (Shift-Left Security).

#### Event Photos
* Add your event photos here

> Overall, the event equipped me with invaluable knowledge regarding advanced monitoring techniques, AI-driven automated security, and a clear roadmap for conquering professional certifications on the AWS platform.
>
> ![event](../../images/4-EventParticipated/event2.jpg)