GRC Eramba Implementation
=========================

Overview
--------

This project presents the design and implementation of a centralized **Governance, Risk and Compliance (GRC)** system using the **Eramba** platform.

The project was completed for **IT8515 – Cybersecurity Compliance and Regulations** at **Bahrain Polytechnic**.

The GRC environment was designed around a fictional **Government Digital Services Authority** that provides online services to citizens and manages sensitive information such as citizen identity data, employee HR records, access logs, government email services, document management systems, and virtual server infrastructure.

> **Individual Work:** Although the academic assessment was submitted in a group-project context, I independently completed the GRC implementation and the work documented in this repository by myself.

Project Objectives
------------------

The main objective of this project was to develop an end-to-end GRC solution using Eramba and demonstrate how governance, risk management, compliance, privacy, security controls, incidents, and improvement activities can be managed within a centralized platform.

### Implementation Covers

*   Business Unit Management
    
*   Asset Management
    
*   Asset Classification
    
*   Risk Assessment
    
*   Risk Scoring
    
*   Risk Appetite
    
*   Risk Treatment
    
*   Security Policy Management
    
*   Internal Controls
    
*   Control Audits
    
*   Control Maintenance
    
*   Compliance Management
    
*   NIST CSF 2.0 Mapping
    
*   Government Digital Services Compliance
    
*   Bahrain Privacy Requirements
    
*   Privacy Management
    
*   Data Processing Activities
    
*   Third-Party Risk Management
    
*   Data Flows
    
*   Security Incident Management
    
*   Incident Lifecycle Management
    
*   Improvement Projects
    
*   Project Tasks
    
*   GRC Dashboards
    
*   Cross-Module Traceability
    

Project Information
-------------------
```text
Item                   Details
Course                 IT8515 – Cybersecurity Compliance and Regulations
Institution            Bahrain Polytechnic
Project Type           GRC Implementation
GRC Platform           Eramba
Sector                 Government / Public Sector
Main Framework         NIST Cybersecurity Framework (CSF) 2.0
Privacy / Compliance   Bahrain Personal Data Protection Requirements
Main Focus             Governance, Risk, Compliance, Privacy and Security
```
Individual Contribution
-----------------------

I completed the implementation documented in this repository **independently and by myself**.

My work covered the complete GRC implementation, including:

*   Creating the organization and business units
    
*   Creating and classifying assets
    
*   Configuring liabilities and classification drivers
    
*   Configuring risk calculation
    
*   Creating the risk appetite matrix
    
*   Creating and evaluating asset risks
    
*   Creating risk treatment activities
    
*   Creating security policies
    
*   Configuring policy reviews and evidence
    
*   Creating internal security controls
    
*   Creating control audits
    
*   Creating control maintenance records
    
*   Importing and configuring NIST CSF 2.0
    
*   Creating compliance packages
    
*   Mapping compliance requirements to controls and policies
    
*   Creating privacy data assets
    
*   Creating processing activities
    
*   Creating data flows
    
*   Creating third-party records
    
*   Creating third-party risks
    
*   Creating security incidents
    
*   Configuring incident lifecycle stages
    
*   Creating improvement projects
    
*   Creating project tasks
    
*   Configuring dashboard evidence
    
*   Connecting records across Eramba modules
    
*   Organizing implementation evidence
    
*   Preparing and documenting the project report
    

This repository represents my individual practical work and hands-on experience with **GRC and Eramba**.

Organization and Sector
-----------------------

The project uses a fictional **Government Digital Services Authority** operating in the **Government / Public Sector**.

The organization provides online services to citizens and manages sensitive information and critical infrastructure.

### Core Assets

1.  **Citizen Records Database**
    
2.  **Employee HR Records System**
    
3.  **Government Email System**
    
4.  **Document Management System**
    
5.  **Virtual Server Infrastructure**
    

### Classification Drivers

*   Confidentiality
    
*   Integrity
    
*   Availability
    
*   Legal / Regulatory
    

### External Vendors

The organization also uses external vendors for:

*   Identity verification
    
*   Cloud-based backups
    
*   Security monitoring analytics
    

GRC Architecture
----------------

The implementation connects multiple GRC functions together:

```text
                            GRC SYSTEM
                                |
          +-------------------+-------------------+                                                           |                   |                   |
          v                   v                   v
      Organization           Assets               Risks                                                       |                    |                   |
          |                    +---------+---------+                                                          |                              |
          |                              v
          |                          Controls    
          |                              |
          |                              v
          |                           Policies
          |                              |
          +------------------------------+
                          |
                          v
                      Compliance
                          |
                 +--------+--------+
                 |                 |
                 v                 v
              Privacy          Incidents
                 |                 |
                 +--------+--------+
                          |
                          v
                Improvement Projects
                          |
                          v
                     Dashboards
```

Asset Management
----------------

Five core assets were created and managed in Eramba:

*   Citizen Records Database
    
*   Employee HR Records System
    
*   Government Email System
    
*   Document Management System
    
*   Virtual Server Infrastructure
    

The assets were associated with:

*   Business units
    
*   Owners
    
*   Review dates
    
*   Potential liabilities
    
*   Asset risks
    
*   Classification drivers
    

Risk Management
---------------

Five asset risks were created:

1.  **Unauthorized Access to Citizen Records**
    
2.  **Ransomware in HR Records System**
    
3.  **Phishing Through Government Email System**
    
4.  **Loss of Official Documents**
    
5.  **Service Outage in Virtual Server Infrastructure**
    

Risk classification was based on:

*   Confidentiality
    
*   Integrity
    
*   Availability
    
*   Legal / Regulatory Impact
    

The risk calculation method was configured as:

> **Single Matrix – Multiplication**

Risks were connected to relevant assets, controls, policies, treatments, and improvement projects.

Risk Appetite and Treatment
---------------------------

An asset-based risk matrix was configured to show risk positions during analysis and treatment.

The project demonstrates how risk treatment can be connected to:

*   Internal controls
    
*   Security policies
    
*   Improvement projects
    
*   Residual risk
    

This provides traceability between identified risks and the activities used to address them.

Security Policies
-----------------

Four security policies were implemented.

### 1\. Identity Governance and Privileged Access Policy

Supports identity governance and privileged access protection.

### 2\. Data Resilience and Recovery Policy

Supports backup, recovery, and resilience requirements.

### 3\. Email Security Policy

Supports email security and phishing protection.

### 4\. Incident Response Policy

Supports security incident response governance.

Policy ownership, publishing, review records, and evidence were also configured.

Internal Controls
-----------------

Four internal controls were implemented.

### 1\. Multi-Factor Authentication Control

Supports identity and access protection.

### 2\. Backup and Recovery Control

Supports data resilience and recovery.

### 3\. Email Filtering and Anti-Phishing Control

Supports protection against phishing and malicious email activity.

### 4\. Incident Reporting and Escalation Control

Supports security incident reporting and escalation.

The controls were connected to relevant risks, policies, and compliance requirements.

Control Audits and Maintenance
------------------------------

Audit records were created for the implemented controls.

The audit records included information such as:

*   Audit methodology
    
*   Success criteria
    
*   Planned dates
    
*   Ownership
    

Maintenance records were also created to demonstrate ongoing control maintenance.

Compliance Management
---------------------

The project uses **NIST Cybersecurity Framework (CSF) 2.0** as the primary cybersecurity framework.

The NIST CSF 2.0 package was imported into Eramba with:

> **134 requirement items**

Additional compliance packages were created for:

*   Government Digital Services
    
*   Bahrain Personal Data Protection Requirements
    

Compliance requirements were mapped to:

*   Internal controls
    
*   Security policies
    
*   Risks
    
*   Risk treatment evidence
    
*   NIST CSF 2.0
    

NIST CSF 2.0
------------

NIST CSF 2.0 was used to provide a structured cybersecurity framework for the organization.

The implementation includes mappings covering areas such as:

*   Governance
    
*   Asset Management
    
*   Identity and Access
    
*   Detection
    
*   Response
    
*   Recovery
    

The mappings demonstrate how cybersecurity framework requirements can be connected to practical organizational controls and policies.

Privacy Management
------------------

Three privacy-related data assets were implemented:

1.  **Citizen Records Database**
    
2.  **Employee HR Records System**
    
3.  **Citizen Service Access Logs**
    

Privacy processing activities were configured with information related to:

*   Data owners
    
*   DPO roles
    
*   Processor roles
    
*   Controller representatives
    
*   Supervisory authority
    
*   Compliance drivers
    
*   GDPR analysis
    

Data Flows
----------

Three data flows were created.

### Citizen Identity Verification Data Flow

Represents identity-related processing involving the identity verification provider.

### Secure Cloud Backup Data Flow

Represents the flow of information to the cloud backup provider.

### Citizen Access Log Monitoring Data Flow

Represents the use of service-access logs for security monitoring.

The data flows were connected to relevant business units, third parties, risks, controls, and policies.

Third-Party Risk
----------------

Third-party risk management was included as part of the GRC implementation.

The project includes:

*   National Identity Verification Gateway
    
*   Secure Cloud Backup Provider
    
*   Security Monitoring Analytics Provider
    

Third-party risks were connected to:

*   Assets
    
*   Controls
    
*   Policies
    
*   Risk treatment
    
*   Reviews
    

This demonstrates how third-party relationships can be incorporated into an organization's GRC process.

Incident Management
-------------------

Four security incidents were created:

1.  **Suspicious Citizen Account Access**
    
2.  **Ransomware Alert on HR Records**
    
3.  **Phishing Email Reported**
    
4.  **Virtual Server Service Outage**
    

Each incident was linked to relevant:

*   Asset risks
    
*   Internal controls
    
*   Affected assets
    
*   Owners
    
*   Status
    
*   Dates
    

Incident Lifecycle
------------------

The implemented incident lifecycle was:
```
Identification        
      |        
      v  
  Containment        
      |        
      v  
  Investigation        
      |        
      v  
    Recovery        
      |        
      v  
    Closure
```

The lifecycle demonstrates structured incident handling within the GRC platform.

Improvement Projects
--------------------

Three improvement projects were created as risk treatment activities.

### Citizen Access Control Improvement Project

Focused on reducing unauthorized access risks associated with citizen information.

### HR Ransomware Recovery Improvement Project

Focused on improving ransomware recovery and data resilience.

### Email Phishing Protection Improvement Project

Focused on reducing phishing-related security risks.

Each project included an associated task with:

*   Owner
    
*   Deadline
    
*   Order
    
*   Completion information
    

Dashboard and Reporting
-----------------------

The Eramba implementation includes dashboard evidence covering:

*   Asset-based risk matrix
    
*   Current compliance status
    

The dashboards provide visibility into risk positions, treatment activities, and compliance status.

Cross-Module Integration
------------------------

One of the main aspects of the project is the integration between different GRC modules.

The implementation demonstrates relationships such as:

```
Asset
  |
  v
Risk
  |
  +----> Internal Control
  |
  +----> Policy
  |
  +----> Compliance Requirement
  |
  +----> Treatment Project
  |
  +----> Incident   
```
### Privacy-Related Integration

```
  Data Asset
      |
      v
Processing Activity
      |
      +----> Data Flow
      |
      +----> Third Party
      |
      +----> Risk
      |
      +----> Control
      |
      +----> Policy   `
```
This integration allows GRC information to be managed and traced across multiple areas of the organization.

Key Risk Areas
--------------

### Unauthorized Access

Addressed through:

*   Multi-Factor Authentication Control
    
*   Identity Governance and Privileged Access Policy
    
*   Access-control improvement activities
    

### Ransomware

Addressed through:

*   Backup and Recovery Control
    
*   Data Resilience and Recovery Policy
    
*   HR Ransomware Recovery Improvement Project
    

### Phishing

Addressed through:

*   Email Filtering and Anti-Phishing Control
    
*   Email Security Policy
    
*   Email Phishing Protection Improvement Project
    

### Service Outage

Addressed through:

*   Incident Reporting and Escalation Control
    
*   Incident Response Policy
    
*   Risk treatment activities
    

Project Evidence
----------------

The project includes extensive Eramba implementation evidence covering:

*   Business units
    
*   Asset inventory
    
*   Classification drivers
    
*   Risk calculation
    
*   Risk matrix
    
*   Asset risk register
    
*   Risk treatment
    
*   Security policies
    
*   Policy reviews
    
*   Internal controls
    
*   Control audits
    
*   Control maintenance
    
*   NIST CSF 2.0
    
*   Government compliance
    
*   Bahrain privacy compliance
    
*   Data processing activities
    
*   Privacy role mapping
    
*   Data flows
    
*   Third-party risks
    
*   Third-party reviews
    
*   Security incidents
    
*   Incident lifecycle stages
    
*   Improvement projects
    
*   Project tasks
    
*   Compliance dashboards
    
*   Cross-module relationships
    

The final report contains evidence for **34 figures** covering the implemented GRC areas.

Implementation Summary
----------------------

RequirementImplementedBusiness Units3Core Assets5Asset Risks5Security Policies4Internal Controls4NIST CSF 2.0 Requirements134Privacy Data Assets3Data Flows3Third Parties3Security Incidents4Improvement Projects3Evidence Figures34

Skills Demonstrated
-------------------

This project demonstrates practical experience in:

*   Governance, Risk and Compliance (GRC)
    
*   Risk Assessment
    
*   Risk Treatment
    
*   Asset Management
    
*   Security Policy Management
    
*   Internal Controls
    
*   Control Auditing
    
*   Compliance Mapping
    
*   NIST CSF 2.0
    
*   Privacy Governance
    
*   Data Protection
    
*   Third-Party Risk Management
    
*   Incident Management
    
*   GRC Reporting
    
*   Eramba
    
*   Cross-Module GRC Integration
    

Tools and Technologies
----------------------

### GRC Platform

**Eramba**

Used for:

*   Governance
    
*   Asset Management
    
*   Risk Management
    
*   Policy Management
    
*   Control Management
    
*   Compliance Management
    
*   Privacy Management
    
*   Incident Management
    
*   Project Management
    
*   Dashboard Reporting
    

### Frameworks and Regulations

*   NIST Cybersecurity Framework (CSF) 2.0
    
*   Bahrain Personal Data Protection Requirements
    
*   Government Digital Services Cybersecurity Compliance Requirements
    

Repository Structure
--------------------

```
GRC-Eramba-Implementation/
│
├── README.md
│
└── report/
    └── IT8515-GRC-Eramba-Project-Report.docx   `
```
Project Report
--------------
The complete project report is available below:

📄 **[Download the IT8515 GRC Project Report](./GRC-Eramba-Project-Report.docx)**

**IT8515 GRC Project Report**

Conclusion
----------

This project demonstrates an end-to-end **GRC implementation using Eramba** for a government digital services environment.

The implementation connects:

```
   Governance
        |
        +-- Assets
        |
        +-- Risks
        |
        +-- Policies
        |
        +-- Controls
        |
        +-- Compliance
        |
        +-- Privacy
        |
        +-- Third Parties
        |
        +-- Incidents
        |
        +-- Risk Treatment
        |
        +-- Improvement Projects
        |
        +-- Dashboards
```

The project provided practical hands-on experience in building and integrating GRC processes within a centralized platform.

Individual Project Statement
----------------------------

I completed the implementation documented in this repository **independently and by myself**.

I personally worked through the GRC configuration, asset management, risk management, policy and control management, compliance mapping, privacy management, third-party risk, incident management, risk treatment, dashboard evidence, and project documentation.

Academic Context
----------------

**IT8515 – Cybersecurity Compliance and Regulations**

**Bahrain Polytechnic**

**GRC Platform:** Eramba
