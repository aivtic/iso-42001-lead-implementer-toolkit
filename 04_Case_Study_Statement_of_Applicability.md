# Case Study 4: Statement of Applicability (SoA) Strategic Implementation
## Mastering ISO 42001 Implementation - Day 2 Practical Guide

---

## Executive Summary

This case study demonstrates how a technology consulting firm successfully developed and implemented a strategic Statement of Applicability (SoA) that served as a critical tool for justifying control selections and demonstrating ISO 42001 compliance. The organization recognized that the SoA is not merely a compliance document but a strategic tool for communicating their AI security approach to stakeholders, regulators, and customers.

**Organization Profile:**
- Industry: Technology Consulting & Services
- Size: 350 employees
- AI Usage: AI-powered consulting solutions, client AI implementations, internal AI tools
- Implementation Timeline: 7 months
- Budget: $180,000

---

## Background and Challenge

### Initial Situation

TechConsult Solutions provides AI consulting services to enterprise clients. As part of their service offering, they needed to demonstrate ISO 42001 compliance to win contracts and build customer confidence. However, they faced significant challenges:

1. **Unclear Scope Definition**: Difficulty determining which controls apply to their specific business model
2. **Stakeholder Confusion**: Different stakeholders had different understandings of what controls were needed
3. **Lack of Justification**: No clear documentation of why specific controls were selected
4. **Compliance Gaps**: Uncertainty about whether all necessary controls were included
5. **Audit Readiness**: Inability to quickly demonstrate compliance to auditors
6. **Customer Confidence**: Difficulty explaining their security approach to clients

### Business Impact

The lack of a strategic SoA resulted in:
- Lost business opportunities due to inability to demonstrate compliance
- Inefficient control implementation (implementing unnecessary controls)
- Audit delays and rework
- Customer concerns about security and compliance
- Regulatory uncertainty
- Wasted resources on non-critical controls

---

## Implementation Approach

### Phase 1: SoA Planning and Preparation (Weeks 1-6)

#### Step 1: Establish SoA Development Team

**Team Composition:**
- Chief Information Security Officer (Sponsor)
- Compliance Manager (Lead)
- Business Unit Heads (3)
- IT Manager
- Risk Manager
- Legal Counsel
- Quality Assurance Lead

**Team Responsibilities:**

| Role | Responsibility |
|------|---|
| CISO | Executive sponsorship, strategic direction |
| Compliance Manager | SoA development and coordination |
| Business Unit Heads | Input on business requirements and risks |
| IT Manager | Technical feasibility assessment |
| Risk Manager | Risk assessment and prioritization |
| Legal Counsel | Regulatory and legal requirements |
| QA Lead | Verification and validation |

#### Step 2: Understand ISO 42001 Requirements

**ISO 42001 Control Categories:**

| Category | Controls | Purpose |
|---|---|---|
| Organizational Controls | A.5 | Risk management, governance |
| People Controls | A.6 | Competence, awareness, training |
| Process Controls | A.7 | AI system lifecycle, incident management |
| Information Controls | A.8 | Data governance, information security |
| Technology Controls | A.9 | Technical security measures |

**Total Controls in ISO 42001:** 23 control objectives with multiple individual controls

#### Step 3: Define SoA Scope

**Scope Definition:**

```
In Scope:
├── AI consulting services
├── AI implementation projects
├── Internal AI tools and systems
├── Client data processing
└── AI model development

Out of Scope:
├── Non-AI consulting services
├── Legacy systems (non-AI)
├── Third-party managed services
└── Client-owned infrastructure
```

**Scope Justification:**

> The SoA covers all systems and processes where artificial intelligence is used or developed, including AI consulting services, AI implementation projects, internal AI tools, and AI model development. This scope ensures comprehensive coverage of AI-specific risks while excluding systems that do not involve AI.

#### Step 4: Conduct Stakeholder Analysis

**Stakeholder Identification:**

| Stakeholder | Interest | Influence | Engagement |
|---|---|---|---|
| Executive Leadership | Compliance, Risk, Cost | High | Monthly reviews |
| Business Unit Heads | Operational impact | High | Weekly meetings |
| IT Team | Technical feasibility | Medium | Weekly meetings |
| Compliance Team | Regulatory requirements | High | Daily coordination |
| Customers | Security assurance | High | Quarterly briefings |
| Auditors | Compliance verification | High | Quarterly reviews |
| Regulators | Compliance demonstration | High | Annual submissions |

**Stakeholder Engagement Plan:**

1. **Executive Leadership**: Monthly steering committee meetings
2. **Business Unit Heads**: Weekly working group meetings
3. **IT Team**: Weekly technical meetings
4. **Compliance Team**: Daily coordination
5. **Customers**: Quarterly security briefings
6. **Auditors**: Quarterly compliance reviews
7. **Regulators**: Annual compliance submissions

### Phase 2: Risk Assessment and Control Identification (Weeks 7-14)

#### Step 1: Conduct Risk Assessment

**Risk Assessment Process:**

```
1. Identify Risk Sources
   ├── AI-specific risks
   ├── Data risks
   ├── Operational risks
   └── Compliance risks

2. Assess Risk Likelihood and Impact
   ├── Likelihood: Low, Medium, High
   ├── Impact: Low, Medium, High, Critical
   └── Risk Score: Likelihood × Impact

3. Prioritize Risks
   ├── Critical risks (High/Critical)
   ├── High risks (High/High, Medium/Critical)
   ├── Medium risks (Medium/High, Low/Critical)
   └── Low risks (others)

4. Identify Control Needs
   ├── Map controls to risks
   ├── Assess control effectiveness
   └── Identify gaps
```

**Risk Assessment Results:**

| Risk ID | Risk Description | Category | Likelihood | Impact | Risk Score | Priority |
|---|---|---|---|---|---|---|
| R-001 | Model bias in consulting recommendations | AI | High | Critical | 20 | Critical |
| R-002 | Data breach of client data | Data | Medium | Critical | 15 | Critical |
| R-003 | Inadequate model validation | Operational | High | High | 12 | High |
| R-004 | Lack of transparency in AI decisions | Compliance | High | High | 12 | High |
| R-005 | Insufficient access controls | Security | Medium | High | 10 | High |
| R-006 | Inadequate incident response | Operational | Medium | High | 10 | High |
| R-007 | Insufficient staff training | People | Medium | Medium | 8 | Medium |
| R-008 | Inadequate documentation | Governance | Low | Medium | 6 | Medium |

#### Step 2: Map Risks to Controls

**Risk-to-Control Mapping:**

| Risk | Control Objective | Specific Control | Justification |
|---|---|---|---|
| R-001: Model bias | A.5.1 Risk Assessment | Bias assessment in model development | Identify bias risks early |
| | A.7.2 AI System Validation | Fairness testing in validation | Detect bias before deployment |
| | A.9.2 AI System Monitoring | Fairness monitoring in production | Detect bias in deployed models |
| R-002: Data breach | A.8.1 Data Classification | Classify client data | Understand protection needs |
| | A.8.2 Data Governance | Implement data governance | Control data usage |
| | A.9.1 Access Control | Restrict data access | Prevent unauthorized access |
| | A.9.3 Encryption | Encrypt sensitive data | Protect data in transit/at rest |

**Control Coverage Matrix:**

| Control | Critical Risks | High Risks | Medium Risks | Coverage |
|---|---|---|---|---|
| A.5.1 Risk Assessment | 2 | 2 | 1 | 5 risks |
| A.5.2 Risk Treatment | 2 | 2 | 1 | 5 risks |
| A.6.1 Competence | 0 | 1 | 2 | 3 risks |
| A.7.1 AI System Development | 1 | 2 | 1 | 4 risks |
| A.7.2 AI System Validation | 1 | 2 | 1 | 4 risks |
| A.8.1 Data Classification | 1 | 1 | 0 | 2 risks |
| A.8.2 Data Governance | 1 | 1 | 0 | 2 risks |
| A.9.1 Access Control | 1 | 1 | 0 | 2 risks |
| A.9.2 AI System Monitoring | 1 | 1 | 1 | 3 risks |
| A.9.3 Encryption | 1 | 0 | 0 | 1 risk |

#### Step 3: Determine Control Applicability

**Applicability Decision Framework:**

```
Is the control relevant to our scope?
├── YES: Is the risk significant?
│   ├── YES: Is the control cost-effective?
│   │   ├── YES: APPLICABLE
│   │   └── NO: ALTERNATIVE CONTROL
│   └── NO: NOT APPLICABLE (Document justification)
└── NO: NOT APPLICABLE (Document scope exclusion)
```

**Applicability Assessment:**

| Control | Applicable | Justification | Implementation |
|---|---|---|---|
| A.5.1 Risk Assessment | Yes | Critical for identifying AI risks | Implemented |
| A.5.2 Risk Treatment | Yes | Essential for risk mitigation | Implemented |
| A.5.3 Risk Evaluation | Yes | Required for risk prioritization | Implemented |
| A.6.1 Competence | Yes | Necessary for staff capability | Implemented |
| A.6.2 Awareness | Yes | Critical for compliance culture | Implemented |
| A.6.3 Training | Yes | Required for staff capability | Implemented |
| A.7.1 AI System Development | Yes | Core to our business | Implemented |
| A.7.2 AI System Validation | Yes | Essential for model quality | Implemented |
| A.7.3 AI System Deployment | Yes | Required for safe deployment | Implemented |
| A.7.4 AI System Monitoring | Yes | Critical for ongoing safety | Implemented |
| A.7.5 Incident Management | Yes | Required for incident response | Implemented |
| A.8.1 Data Classification | Yes | Essential for data protection | Implemented |
| A.8.2 Data Governance | Yes | Required for data quality | Implemented |
| A.8.3 Data Quality | Yes | Critical for model fairness | Implemented |
| A.9.1 Access Control | Yes | Required for data security | Implemented |
| A.9.2 Cryptography | Yes | Essential for data protection | Implemented |
| A.9.3 AI System Monitoring | Yes | Critical for security monitoring | Implemented |

**Applicability Summary:**
- Total controls in ISO 42001: 23
- Applicable controls: 23 (100%)
- Not applicable controls: 0 (0%)
- Justification: All controls are relevant to our AI consulting business

### Phase 3: SoA Development (Weeks 15-22)

#### Step 1: Create Detailed SoA Document

**SoA Structure:**

```
Statement of Applicability
├── Introduction
│   ├── Purpose
│   ├── Scope
│   └── Approval
├── Organization Overview
│   ├── Business description
│   ├── AI systems
│   └── Regulatory environment
├── Risk Assessment Summary
│   ├── Risk assessment methodology
│   ├── Key risks identified
│   └── Risk prioritization
├── Control Selection Justification
│   ├── For each control:
│   │   ├── Control description
│   │   ├── Applicability justification
│   │   ├── Risk addressed
│   │   ├── Implementation status
│   │   └── Evidence
│   └── Control coverage matrix
├── Implementation Status
│   ├── Implemented controls
│   ├── Controls in progress
│   └── Planned controls
└── Approval and Sign-off
```

**SoA Content Example:**

**Control A.5.1: Risk Assessment**

**Control Description:**
> The organization shall establish and maintain a process for identifying, analyzing, and evaluating risks related to AI systems. The risk assessment process shall consider the likelihood and impact of risks, and shall be conducted on a regular basis and when significant changes occur.

**Applicability Justification:**
> This control is applicable because TechConsult Solutions develops and implements AI systems for clients, and inadequate risk assessment could lead to unidentified AI-specific risks. The organization must systematically identify risks related to model bias, data quality, model drift, and other AI-specific concerns.

**Risks Addressed:**
- R-001: Model bias in consulting recommendations
- R-003: Inadequate model validation
- R-004: Lack of transparency in AI decisions

**Implementation Status:** Implemented

**Implementation Details:**
- Established AI Risk Assessment Team
- Developed AI Risk Assessment Framework
- Conducted initial risk assessment identifying 8 critical risks
- Established quarterly risk assessment schedule
- Created risk register with 45 identified risks

**Evidence:**
- Risk Assessment Policy (Document REF-001)
- Risk Register (Document REF-002)
- Risk Assessment Reports (Monthly)
- Risk Assessment Team Meeting Minutes

**Monitoring and Review:**
- Quarterly risk assessment reviews
- Annual risk assessment update
- Incident-triggered risk reassessment

---

#### Step 2: Create Control Implementation Evidence

**Evidence Collection:**

For each control, collect evidence demonstrating implementation:

| Control | Evidence Type | Evidence Examples | Status |
|---|---|---|---|
| A.5.1 Risk Assessment | Documentation | Risk policy, Risk register | ✓ Complete |
| | Process | Risk assessment procedure | ✓ Complete |
| | Records | Risk assessment reports | ✓ Complete |
| | Training | Risk assessment training | ✓ Complete |
| A.5.2 Risk Treatment | Documentation | Risk treatment policy | ✓ Complete |
| | Process | Risk treatment procedure | ✓ Complete |
| | Records | Risk treatment plans | ✓ Complete |
| | Monitoring | Risk treatment tracking | ✓ Complete |

**Evidence Documentation:**

```
Control A.5.1: Risk Assessment
├── Policy Documents
│   ├── AI Risk Management Policy (REF-001)
│   └── Risk Assessment Procedure (REF-002)
├── Process Documentation
│   ├── Risk Assessment Methodology
│   └── Risk Assessment Checklist
├── Records
│   ├── Risk Register (Current)
│   ├── Risk Assessment Reports (Monthly)
│   └── Risk Assessment Meeting Minutes
├── Training Records
│   ├── Risk Assessment Training (All staff)
│   └── Training Attendance Records
└── Audit Evidence
    ├── Internal Audit Reports
    └── Management Review Minutes
```

#### Step 3: Create Control Implementation Roadmap

**Implementation Timeline:**

| Phase | Timeline | Controls | Status |
|---|---|---|---|
| Phase 1: Foundation | Months 1-2 | A.5 (Risk Management) | Completed |
| Phase 2: People | Months 2-3 | A.6 (People) | Completed |
| Phase 3: Process | Months 3-5 | A.7 (Process) | Completed |
| Phase 4: Information | Months 4-6 | A.8 (Information) | Completed |
| Phase 5: Technology | Months 5-7 | A.9 (Technology) | Completed |

**Implementation Status Summary:**

| Status | Count | Percentage |
|---|---|---|
| Implemented | 23 | 100% |
| In Progress | 0 | 0% |
| Planned | 0 | 0% |
| Not Applicable | 0 | 0% |

#### Step 4: Create Compliance Mapping

**Regulatory Compliance Mapping:**

| Regulation | Requirement | Related Controls | Status |
|---|---|---|---|
| GDPR | Data Protection | A.8, A.9 | ✓ Compliant |
| GDPR | Data Subject Rights | A.8.2 | ✓ Compliant |
| GDPR | Data Breach Notification | A.7.5 | ✓ Compliant |
| CCPA | Consumer Privacy | A.8, A.9 | ✓ Compliant |
| EU AI Act | High-Risk AI | A.5, A.7 | ✓ Compliant |
| SOC 2 | Security Controls | A.9 | ✓ Compliant |
| ISO 27001 | Information Security | A.8, A.9 | ✓ Compliant |

### Phase 4: SoA Review and Approval (Weeks 23-28)

#### Step 1: Internal Review

**Review Process:**

```
SoA Draft
    ↓
Technical Review (IT/Security)
    ↓
Business Review (Business Units)
    ↓
Compliance Review (Legal/Compliance)
    ↓
Management Review
    ↓
Executive Approval
```

**Review Checklist:**

| Review Area | Reviewer | Checklist Items | Status |
|---|---|---|---|
| Technical | IT Manager | All controls technically feasible | ✓ Pass |
| | | Implementation realistic | ✓ Pass |
| | | Evidence available | ✓ Pass |
| Business | Business Heads | Scope appropriate | ✓ Pass |
| | | Controls address business risks | ✓ Pass |
| | | Implementation cost-effective | ✓ Pass |
| Compliance | Legal/Compliance | All regulations addressed | ✓ Pass |
| | | Justifications sound | ✓ Pass |
| | | Documentation complete | ✓ Pass |
| Management | CISO | Overall adequacy | ✓ Pass |
| | | Risk coverage | ✓ Pass |
| | | Resource requirements | ✓ Pass |

**Review Results:**
- Technical Review: APPROVED
- Business Review: APPROVED
- Compliance Review: APPROVED
- Management Review: APPROVED

#### Step 2: Stakeholder Communication

**Communication Plan:**

| Stakeholder | Message | Format | Frequency |
|---|---|---|---|
| Executive Leadership | SoA approved, compliance achieved | Executive summary | Annual |
| Business Units | Controls implemented, compliance status | Detailed briefing | Quarterly |
| Customers | Security controls in place, compliance verified | Security brief | On request |
| Auditors | SoA available, evidence ready | Full SoA document | Annual |
| Regulators | Compliance demonstrated, controls implemented | Compliance report | Annual |

**Communication Materials:**

1. **Executive Summary** (2 pages)
   - SoA overview
   - Compliance status
   - Key achievements

2. **Detailed SoA** (50+ pages)
   - Full control descriptions
   - Implementation details
   - Evidence references

3. **Customer Security Brief** (5 pages)
   - Overview of controls
   - Data protection measures
   - Compliance certifications

4. **Audit Readiness Package** (100+ pages)
   - Complete SoA
   - All supporting evidence
   - Implementation records

#### Step 3: Formal Approval

**Approval Sign-off:**

```
Statement of Applicability
Version 1.0
Date: November 15, 2025

Approved by:

Chief Information Security Officer: _________________ Date: _______
Chief Executive Officer: _________________ Date: _______
Board of Directors: _________________ Date: _______

This Statement of Applicability is approved and will be implemented
effective immediately. This document will be reviewed and updated
annually or when significant changes occur.
```

### Phase 5: Implementation and Maintenance (Weeks 29-36)

#### Step 1: Implement SoA-Based Controls

**Implementation Approach:**

```
For Each Control:
├── Assign Responsibility
├── Define Implementation Procedure
├── Set Implementation Timeline
├── Allocate Resources
├── Implement Control
├── Collect Evidence
├── Verify Implementation
└── Document Results
```

**Implementation Tracking:**

| Control | Owner | Start Date | Target Date | Status | Evidence |
|---|---|---|---|---|---|
| A.5.1 | Risk Manager | 2025-06-01 | 2025-07-15 | ✓ Complete | Risk register |
| A.5.2 | Risk Manager | 2025-06-15 | 2025-08-01 | ✓ Complete | Risk treatment plan |
| A.6.1 | HR Manager | 2025-07-01 | 2025-08-15 | ✓ Complete | Training records |
| A.7.1 | IT Manager | 2025-07-15 | 2025-09-01 | ✓ Complete | Development standards |
| A.8.1 | Data Manager | 2025-08-01 | 2025-09-15 | ✓ Complete | Data classification |
| A.9.1 | Security Manager | 2025-08-15 | 2025-10-01 | ✓ Complete | Access control policy |

#### Step 2: Maintain and Update SoA

**SoA Maintenance Process:**

```
Quarterly Review
├── Check for changes in:
│   ├── Business scope
│   ├── Regulatory environment
│   ├── Risk profile
│   └── Control effectiveness
├── Update SoA if needed
└── Communicate changes

Annual Update
├── Comprehensive review
├── Risk reassessment
├── Control effectiveness evaluation
├── Update SoA
└── Executive approval
```

**Change Management:**

| Change Type | Trigger | Process | Approval |
|---|---|---|---|
| Minor updates | Documentation corrections | Update SoA | Compliance Manager |
| Control changes | New risks identified | Risk assessment, update SoA | CISO |
| Scope changes | Business expansion | Scope review, risk assessment | Executive Committee |
| Regulatory changes | New regulations | Compliance assessment, update SoA | Legal/Compliance |

**SoA Version Control:**

| Version | Date | Changes | Approver |
|---|---|---|---|
| 1.0 | 2025-11-15 | Initial SoA | CISO |
| 1.1 | 2026-02-15 | Q1 updates | CISO |
| 1.2 | 2026-05-15 | Q2 updates | CISO |
| 2.0 | 2026-11-15 | Annual review | Executive Committee |

#### Step 3: Use SoA for Audit and Compliance

**Audit Preparation:**

```
Audit Preparation Checklist:
├── SoA current and approved
├── All controls implemented
├── Evidence collected and organized
├── Documentation complete
├── Staff trained on controls
├── Monitoring in place
└── Issues tracked and resolved
```

**Audit Response:**

| Audit Question | SoA Response | Evidence |
|---|---|---|
| What controls do you have? | See SoA, Section 3 | SoA document |
| Why did you select these controls? | See SoA, Section 4 | Control justifications |
| Are controls implemented? | See SoA, Section 5 | Implementation records |
| How do you monitor controls? | See SoA, Section 6 | Monitoring procedures |
| What evidence do you have? | See SoA, Appendix | Evidence package |

---

## Results and Outcomes

### SoA Development Success

| Metric | Target | Achieved |
|---|---|---|
| SoA Completion | 100% | 100% ✓ |
| Control Applicability Assessment | 100% | 100% ✓ |
| Implementation Evidence | 100% | 100% ✓ |
| Stakeholder Approval | 100% | 100% ✓ |
| Documentation Completeness | 95% | 98% ✓ |

### Compliance Achievement

| Compliance Area | Target | Achieved |
|---|---|---|
| Control Implementation | 100% | 100% ✓ |
| Evidence Collection | 100% | 100% ✓ |
| Audit Readiness | 95% | 98% ✓ |
| Regulatory Compliance | 95% | 100% ✓ |
| Customer Confidence | 85% | 92% ✓ |

### Business Impact

| Metric | Before | After | Improvement |
|---|---|---|---|
| Audit Time | 40 hours | 8 hours | 80% reduction |
| Compliance Violations | 5/year | 0 | 100% reduction |
| Customer Confidence | 65% | 92% | +27% |
| Contract Win Rate | 60% | 85% | +25% |
| Regulatory Fines | $50K/year | $0 | 100% reduction |

### Financial Impact

| Item | Value |
|------|-------|
| SoA Development Cost | $180,000 |
| Avoided Compliance Fines | $200,000 |
| Increased Contract Value | $500,000 (annual) |
| Audit Cost Reduction | $100,000 (annual) |
| Operational Efficiency Gains | $150,000 (annual) |
| **Net Benefit (Year 1)** | **$770,000** |

---

## Key Lessons Learned

### 1. SoA is a Strategic Document

**Lesson:** The SoA is not just a compliance checklist but a strategic document that communicates your security approach to all stakeholders.

**Application:** Invest time in developing a comprehensive SoA that clearly justifies your control selections and demonstrates your commitment to security.

### 2. Applicability Assessment is Critical

**Lesson:** Blindly implementing all controls in a standard is inefficient. Careful applicability assessment ensures you implement only necessary controls.

**Application:** Conduct thorough risk assessment and carefully assess control applicability. Document your justifications clearly.

### 3. Evidence Collection is Essential

**Lesson:** Without evidence, you cannot demonstrate compliance. Evidence collection must be systematic and ongoing.

**Application:** Establish processes for collecting and organizing evidence as controls are implemented, not after the fact.

### 4. Stakeholder Engagement is Key

**Lesson:** SoA development requires input from multiple stakeholders. Lack of engagement leads to incomplete or ineffective SoA.

**Application:** Engage business units, IT, compliance, and legal early and often. Communicate regularly about progress and decisions.

### 5. SoA is a Living Document

**Lesson:** The SoA must be updated regularly as business, risks, and regulations change. A static SoA becomes outdated quickly.

**Application:** Establish processes for regular SoA review and update. Communicate changes to all stakeholders.

### 6. SoA Drives Implementation

**Lesson:** A well-developed SoA provides clear direction for control implementation. It reduces confusion and ensures consistency.

**Application:** Use the SoA as the primary guide for implementation. Ensure all teams understand their responsibilities based on the SoA.

---

## Practical Toolkit Components Used

### 1. SoA Template
- Comprehensive SoA structure
- Control description format
- Justification template
- Evidence reference format

### 2. Risk Assessment Template
- Risk identification process
- Risk scoring methodology
- Risk prioritization framework
- Risk-to-control mapping

### 3. Control Applicability Matrix
- Applicability assessment framework
- Justification guidance
- Decision documentation
- Approval workflow

### 4. Evidence Collection Checklist
- Evidence types by control
- Documentation requirements
- Record organization
- Audit readiness checklist

### 5. Stakeholder Communication Templates
- Executive summary template
- Control overview template
- Customer security brief template
- Audit readiness package template

---

## Recommendations for Other Organizations

### 1. Start with Risk Assessment

Before developing your SoA, conduct a thorough risk assessment. Your control selections should be driven by your specific risks, not by a generic standard.

### 2. Engage All Stakeholders

SoA development requires input from business units, IT, compliance, legal, and other stakeholders. Engage them early and often.

### 3. Document Your Justifications

For each control, clearly document why you selected it, what risks it addresses, and how it's implemented. This is essential for audit and compliance.

### 4. Collect Evidence Systematically

Don't wait until audit time to collect evidence. Establish processes for collecting and organizing evidence as controls are implemented.

### 5. Use SoA as Implementation Guide

Your SoA should be the primary guide for control implementation. Ensure all teams understand their responsibilities based on the SoA.

### 6. Plan for Regular Updates

Establish processes for regular SoA review and update. Review at least annually and whenever significant changes occur.

### 7. Communicate Widely

Use your SoA to communicate your security approach to customers, regulators, auditors, and other stakeholders. A well-communicated SoA builds confidence.

---

## Conclusion

TechConsult Solutions successfully developed a comprehensive Statement of Applicability that served as a strategic tool for demonstrating ISO 42001 compliance and communicating their security approach to stakeholders. The SoA development process resulted in 100% control implementation, 100% audit readiness, and increased customer confidence.

The key to success was recognizing that the SoA is not just a compliance document but a strategic tool that should drive implementation, guide audits, and communicate security approach to all stakeholders. By following the structured approach outlined in this case study, other organizations can develop effective SoAs that support their compliance objectives and build stakeholder confidence.

---

## Appendix: SoA Template

### Statement of Applicability Template

**Document Information:**
- Organization: [Organization Name]
- Document Title: Statement of Applicability
- Version: [Version Number]
- Date: [Date]
- Approval: [Approver Name and Title]

**1. Introduction**

**1.1 Purpose**
The purpose of this Statement of Applicability (SoA) is to define the scope of the information security management system (ISMS) and to identify which controls from ISO 42001 are applicable to [Organization Name].

**1.2 Scope**
This SoA applies to [describe scope].

**1.3 Applicability**
This SoA is applicable to [describe applicability].

**2. Organization Overview**

**2.1 Business Description**
[Describe organization, business model, and AI systems]

**2.2 Regulatory Environment**
[Describe applicable regulations]

**2.3 Risk Profile**
[Describe risk profile]

**3. Risk Assessment Summary**

**3.1 Risk Assessment Methodology**
[Describe risk assessment methodology]

**3.2 Key Risks Identified**
[List key risks]

**3.3 Risk Prioritization**
[Describe risk prioritization]

**4. Control Selection Justification**

For each control, provide:
- Control description
- Applicability justification
- Risks addressed
- Implementation status
- Evidence

**5. Implementation Status**

[Describe implementation status of each control]

**6. Approval**

[Approval signatures]

---

**Document Version:** 1.0  
**Last Updated:** November 2025  
**Status:** Final
