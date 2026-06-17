# Sigma Rule Collection

A cybersecurity detection engineering project focused on developing Sigma rules for common attack techniques and security monitoring use cases.

## Overview

This repository contains Sigma detection rules designed to identify suspicious and malicious activities commonly encountered by Security Operations Center (SOC) analysts.

The project demonstrates practical detection engineering concepts by mapping detections to MITRE ATT&CK techniques and documenting investigation workflows.

## Objectives

* Develop reusable Sigma detection rules
* Map detections to MITRE ATT&CK techniques
* Practice detection engineering methodologies
* Improve SOC investigation capabilities
* Build a cybersecurity portfolio demonstrating blue-team skills

## Current Detection Rules

### Brute Force Detection

Detects excessive authentication failures that may indicate password guessing attacks.

MITRE ATT&CK:

* T1110.001 – Password Guessing

### Privilege Escalation Detection

Detects suspicious account creation and privilege escalation activities.

MITRE ATT&CK:

* T1068 – Exploitation for Privilege Escalation

## Technologies Used

* Sigma Rules
* MITRE ATT&CK Framework
* Detection Engineering
* Threat Hunting
* Log Analysis
* Git
* GitHub

## Learning Outcomes

This project demonstrates:

* Detection Engineering
* Security Monitoring
* Threat Hunting
* ATT&CK Mapping
* SOC Operations
* Incident Investigation
* Security Analytics
  
Sigma-Rule-Collection/
├── rules/
│   ├── brute_force.yml
│   └── privilege_escalation.yml
├── reports/
│   └── sigma_mapping_report.txt
├── screenshots/
└── README.md

## Portfolio Value

This project demonstrates practical skills in:

- Detection Engineering
- Threat Detection
- MITRE ATT&CK Mapping
- Security Monitoring
- Threat Hunting
- SOC Operations
- Incident Investigation

## Future Enhancements

- Sysmon Rules
- Wazuh Rules
- Windows Event Mapping
- ATT&CK Navigator Integration

## Author

Thabo Sakonta

Microsoft Certified Security Operations Analyst (SC-200)
