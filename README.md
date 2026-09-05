# High-Risk-AI-Risk-Data-Governance-Programme

<img width="1100" height="480" alt="banner (6)" src="https://github.com/user-attachments/assets/53082f1f-2cee-4092-9fe5-bedbd1618ead" />

EU AI Act Articles 8–10 governance programme for an AI recruitment screening system — impact assessment, an 8-entry risk register, data governance, bias testing (pass, 50K-applicant holdout), and continuous monitoring.
**EU AI Act Articles 8, 9, and 10** risk-management and data-governance programme for a high-risk AI recruitment screening system — from system context and impact assessment through risk register, data governance, bias testing, and continuous monitoring.

## About this repository

This repository contains a single-file portfolio programme covering:

- A full system context assessment (intended purpose, users, affected applicants, human oversight model)
- An eight-dimension AI impact assessment (fairness, privacy, employment opportunity, transparency, accessibility, security, human autonomy, contestability)
- An 8-entry AI risk register with likelihood × impact scoring, existing controls, and residual risk
- A data governance assessment (sources, lineage, labeling, representativeness, retention, access controls)
- A bias testing programme with acceptance thresholds and example pass results across four demographic/segment groups
- A continuous monitoring programme (daily/weekly/monthly/quarterly cadences) and monitoring workflow
- A compliance control matrix mapping controls to EU AI Act articles, an evidence package index, and a proposed GitHub repository structure

**Scenario:** The programme governs the **Meridian Talent Intelligence Platform (MTIP)**, a high-risk AI recruitment screening system built for the fictional **Meridian Digital Services**. MTIP ranks and prioritizes job applicants for recruiters based on CVs, employment history, certifications, skills assessments, and interview results — but does not itself hire, reject, or make employment offers; final decisions remain with human recruiters and hiring managers.

## Frameworks referenced

- Regulation (EU) 2024/1689 (EU AI Act) — Article 8 (compliance with high-risk requirements), Article 9 (risk management system), Article 10 (data and data governance)
- NIST AI Risk Management Framework — MAP, MEASURE, MANAGE
- ISO/IEC 42001, ISO 31000, ISO/IEC 27001
- Privacy-by-Design principles

> **Disclaimer:** This is a fictional portfolio project using synthetic data. It demonstrates a risk-management and data-governance methodology, not legal advice or a formal EU AI Act compliance determination. Real deployment of a recruitment-screening system would require qualified legal, HR, employment-law, and data-protection review.

---

# High-Risk AI Risk & Data Governance Programme

## AI Recruitment Screening System Governance Framework

*Portfolio Project | AI Governance, Risk Management & Responsible AI*

## Overview

This project develops a complete Risk Management and Data Governance Programme for a high-risk AI recruitment screening system. The programme is designed around a realistic business scenario in which an organization uses artificial intelligence to rank and prioritize job applicants based on CVs, employment history, skills assessments, and interview information.

The project demonstrates how organizations can establish governance controls for high-risk AI systems by implementing:

- AI impact assessments
- Risk management processes
- Data governance controls
- Bias testing procedures

## Project Overview

| Field | Detail |
|---|---|
| **Project Title** | High-Risk AI Risk and Data Governance Programme for AI-Based Recruitment Screening |
| **Organization** | Meridian Digital Services (Fictional Enterprise) |
| **System Name** | Meridian Talent Intelligence Platform (MTIP) |
| **System Type** | High-Risk AI Recruitment Screening System |
| **Purpose** | Assist recruitment teams by ranking and prioritizing job applicants for further review. |

**Primary Framework Alignment:**

- EU AI Act Article 8 (Compliance with High-Risk AI Requirements)
- EU AI Act Article 9 (Risk Management System)
- EU AI Act Article 10 (Data and Data Governance)
- NIST AI RMF (MAP, MEASURE, MANAGE)
- ISO/IEC 42001
- ISO 31000
- ISO/IEC 27001
- Privacy-by-Design Principles

## Executive Summary

Meridian Digital Services intends to deploy an AI recruitment screening platform that evaluates CVs, employment history, professional certifications, skills assessments, and structured interview results. The system provides applicant ranking recommendations to recruiters.

The organization must demonstrate that:

- Risks are identified and managed.
- Human oversight exists.
- Data quality is suitable.
- Bias is actively monitored.
- Privacy is protected.
- Decisions remain contestable.
- Governance controls are documented and tested.

This project establishes a complete risk management and data governance programme covering the system lifecycle.

## Section 1 — System Context Assessment

### AI System Profile

| Field | Detail |
|---|---|
| System Name | Meridian Talent Intelligence Platform (MTIP) |
| System Classification | High-Risk AI System |
| Business Owner | Head of Recruitment Services |
| Technical Owner | Director of Data Science |
| Governance Owner | AI Governance Committee |
| Assessment Owner | Responsible AI Manager |

### Intended Purpose

The AI system assists recruiters by prioritizing and ranking job applicants based on predefined job requirements. The AI system does not make hiring decisions. Final hiring decisions remain the responsibility of authorized recruiters and hiring managers.

### Users

**Primary Users:** Recruiters · Hiring Managers · Talent Acquisition Team

**Secondary Users:** HR Leadership · Internal Audit · Compliance Team · AI Governance Team

### Affected Applicants

All job applicants processed through Meridian's recruitment process. Potential affected groups include:

- Recent graduates
- Experienced professionals
- Intern applicants
- International applicants
- Applicants from underrepresented groups

### Decision Influence

| Aspect | Detail |
|---|---|
| AI Recommendation | Candidate priority score |
| Human Decision | Final decision remains human-controlled |

The AI system cannot hire, reject, or offer employment without human review.

### Expected Benefits

**Operational Benefits:** Faster screening · Consistent applicant prioritization · Reduced recruiter workload

**Business Benefits:** Improved efficiency · Reduced time-to-hire · Increased scalability

### Geographic Scope

Approved Regions: Qatar · United Kingdom · European Union

### Reasonably Foreseeable Misuse

1. Recruiters automatically trust rankings.
2. Using recommendations as hiring decisions.
3. Using AI scores outside intended hiring process.
4. Exporting candidate data without authorization.
5. Manipulating training data.

### Human Oversight Model

```
Applicant Submitted
      ↓
AI Ranking Generated
      ↓
Recruiter Review
      ↓
Override Allowed
      ↓
Hiring Manager Decision
      ↓
Final Outcome
```

Mandatory controls: ✓ Human review · ✓ Override capability · ✓ Escalation path · ✓ Appeal process

## Section 2 — AI Impact Assessment

| Impact Area | Risk | Impact Rating | Mitigation |
|---|---|---|---|
| **Fairness** | Historical hiring patterns may influence future outcomes, causing disproportionate disadvantage. | High | Fairness testing; human review; bias monitoring |
| **Privacy** | Unauthorized access to applicant information. | High | Access controls; encryption; data minimization |
| **Employment Opportunity** | Incorrect ranking could affect opportunities. | Critical | Human review; contestability; periodic validation |
| **Transparency** | Applicants may not understand outcomes. | High | Transparency notice; explainability reports |
| **Accessibility** | System disadvantages certain users. | Medium | Accessibility testing; alternative processes |
| **Security** | Unauthorized access. | High | ISO 27001 controls; logging; monitoring |
| **Human Autonomy** | Automation bias. | High | Mandatory review; training; override requirement |
| **Contestability** | Applicant cannot challenge outcomes. | High | Reconsideration process; appeal pathway; human review board |

## Section 3 — AI Risk Register

**Risk Classification Matrix:** Likelihood (1–5) × Impact (1–5) = Risk Score.

| ID | Risk | Likelihood | Impact | Inherent Risk | Residual Risk | Treatment | Owner |
|---|---|---|---|---|---|---|---|
| R-001 | Historical Hiring Bias | 4 | 5 | 20 | 10 | Annual retraining review (existing controls: bias testing, independent review; evidence: bias reports; review: quarterly) | Responsible AI Manager |
| R-002 | Underrepresentation | 4 | 4 | 16 | 8 | Balanced datasets | — |
| R-003 | Proxy Discrimination | 3 | 5 | 15 | 9 | Feature reviews | — |
| R-004 | Inaccurate Ranking | 4 | 5 | 20 | 10 | Performance validation | — |
| R-005 | Unauthorized Access | 3 | 5 | 15 | 5 | Encryption and RBAC | — |
| R-006 | Model Drift | 4 | 4 | 16 | 8 | Drift monitoring | — |
| R-007 | Automation Bias | 4 | 5 | 20 | 10 | Mandatory recruiter review | — |
| R-008 | Lack of Contestability | 3 | 5 | 15 | 6 | Appeal process | — |

## Section 4 — Data Governance Assessment

### Data Sources

1. Candidate CV Submissions
2. Application Forms
3. Skills Assessments
4. Interview Results

### Legal Basis

Authorized recruitment processing. Applicable privacy and employment requirements reviewed.

### Data Ownership

| Role | Owner |
|---|---|
| Business Owner | Head of Recruitment |
| Data Steward | HR Data Governance Lead |

### Collection Method

Direct collection from applicants. No data scraping.

### Data Lineage

```
Application Submission
      ↓
   HR Platform
      ↓
Data Validation
      ↓
Feature Engineering
      ↓
Training Dataset
      ↓
 Model Training
      ↓
 Ranking System
      ↓
Recruiter Review
```

### Preparation & Labeling

**Labels:** Hired · Interviewed · Rejected. Independent label review conducted.

### Representativeness

**Assessment Areas:** Gender balance · Geographic coverage · Education diversity · Experience diversity

**Representativeness Score:** 88%

### Missing Data Review

| Metric | Value |
|---|---|
| Missing Data Rate | 3.4% |
| Treatment | Imputation; record validation |

### Known Limitations

- Historical recruitment practices
- Labour market changes
- Small applicant segments

### Retention Period

Applicant records retained according to approved retention schedule.

### Access Controls

✓ RBAC · ✓ MFA · ✓ Audit logging · ✓ Encryption · ✓ Data classification

## Section 5 — Bias Testing Programme

### Groups Assessed

Experience level · Geographic region · Education categories · Application source

### Test Dataset

Independent holdout dataset. Size: 50,000 applicants.

### Metrics Used

Selection Rate Difference · Equal Opportunity Difference · False Positive Rate Difference · Precision Difference · Balanced Accuracy

### Acceptance Thresholds and Example Results

| Metric | Threshold | Example Result |
|---|---|---|
| Selection Rate Difference | ≤ 10% | 6% |
| TPR Difference (Equal Opportunity) | ≤ 5% | 3% |
| FPR Difference | ≤ 5% | 2% |
| Precision Difference | ≤ 5% | 4% |

**Status:** Pass

### Limitations

- Labor market changes
- Historical hiring patterns
- Limited representation in some groups

### Corrective Actions

Oversampling · Reweighting · Additional testing · Human review

## Section 6 — Continuous Monitoring Programme

| Cadence | Monitored Items |
|---|---|
| **Daily** | Security events; access events; system availability |
| **Weekly** | Selection rate differences; error rates; human overrides; complaints |
| **Monthly** | Data drift; feature drift; model drift; bias metrics |
| **Quarterly (Governance Review)** | Risk register review; bias review; residual risk review; compliance review |

### Monitoring Workflow

```
Production Monitoring
      ↓
 Threshold Breach
      ↓
   Investigation
      ↓
Root Cause Analysis
      ↓
Corrective Action
      ↓
    Validation
      ↓
Governance Approval
```

## Compliance Control Matrix

| Control | Article | Evidence |
|---|---|---|
| Risk Management Framework | Article 9 | Risk Assessment |
| Risk Register | Article 9 | Risk Register |
| Data Governance Framework | Article 10 | Data Governance Assessment |
| Data Quality Monitoring | Article 10 | Data Quality Reports |
| Bias Testing | Article 10 | Bias Reports |
| Human Oversight | Article 8 | Oversight Procedure |
| Monitoring Programme | Article 9 | Monitoring Reports |
| Residual Risk Review | Article 9 | Acceptance Records |

## Evidence Package

The portfolio repository should include:

1. AI Impact Assessment
2. AI Risk Register
3. Risk Treatment Plan
4. Data Source Register
5. Data Lineage Diagram
6. AI Data Sheet
7. Data Quality Assessment
8. Bias Testing Report
9. Human Oversight Procedure
10. Dataset Approval Record
11. Control Testing Evidence
12. Monitoring Reports
13. Residual Risk Acceptance Form
14. Compliance Control Matrix
15. Governance Decision Record

## Proposed Repository Structure

```
High-Risk-AI-Risk-Data-Governance-Programme/
│
├── README.md
├── Executive-Governance-Report.pdf
│
├── assessments/
│   ├── AI-Impact-Assessment.docx
│   ├── Data-Governance-Assessment.docx
│   ├── Data-Quality-Assessment.xlsx
│   └── Bias-Testing-Report.docx
│
├── registers/
│   ├── AI-Risk-Register.xlsx
│   ├── Risk-Treatment-Plan.xlsx
│   ├── Data-Lineage-Register.xlsx
│   └── Data-Source-Register.xlsx
│
├── controls/
│   ├── Human-Oversight-Procedure.docx
│   ├── Compliance-Control-Matrix.xlsx
│   └── Residual-Risk-Acceptance.docx
│
├── monitoring/
│   ├── Monitoring-Plan.docx
│   ├── Monthly-Monitoring-Report.xlsx
│   └── Dashboard.pbix
│
└── evidence/
    ├── Risk-Workshop-Notes.docx
    ├── Bias-Test-Results.xlsx
    ├── Dataset-Approval.docx
    └── Control-Test-Evidence.docx
```

## Portfolio Description

Developed a comprehensive High-Risk AI Risk and Data Governance Programme for an AI recruitment screening system, including AI impact assessments, risk management, data governance, bias testing, human oversight, compliance controls, residual-risk governance, and continuous monitoring aligned with EU AI Act Articles 8–10, NIST AI RMF, ISO/IEC 42001, ISO 31000, and ISO/IEC 27001.

## Resume Bullet

Designed and implemented a high-risk AI governance programme for an AI recruitment screening platform, producing risk registers, AI impact assessments, data governance controls, bias testing frameworks, human oversight procedures, compliance matrices, residual-risk reviews, and continuous monitoring processes aligned with EU AI Act Articles 8–10 and international governance standards.
