Enterprise SOC Threat Intelligence & Attack Simulation Lab

Overview

This project documents the design, deployment, integration, and validation of a fully operational Security Operations Center (SOC) laboratory environment built from scratch using industry-standard security technologies.

The goal of this project was to create a realistic SOC environment capable of:

- Threat Intelligence Management
- Security Monitoring
- Detection Engineering
- Adversary Emulation
- Endpoint Telemetry Collection
- IOC Enrichment
- Lateral Movement Testing

The lab successfully integrates MISP, Splunk Enterprise, CALDERA, Infection Monkey, Windows Event Logging, and Docker into a single security operations workflow.

---

Technologies Used

Technology| Purpose
Splunk Enterprise| SIEM & Security Analytics
MISP| Threat Intelligence Platform
CALDERA| MITRE ATT&CK Adversary Emulation
Infection Monkey| Lateral Movement & Breach Simulation
Docker| Containerized Deployment
Windows 10| Endpoint Target System
Splunk Universal Forwarder| Log Collection
Kali Linux| Security Operations Platform

---

Lab Architecture

CALDERA / Infection Monkey
            │
            ▼
      Windows 10 Endpoint
            │
            ▼
 Splunk Universal Forwarder
            │
            ▼
     Splunk Enterprise
            │
            ▼
      Detection Rules
            │
            ▼
      MISP Intelligence
            │
            ▼
 Security Investigation

---

Project Objectives

- Deploy and configure MISP Threat Intelligence Platform
- Deploy Splunk Enterprise SIEM
- Configure Windows log collection
- Integrate MISP with Splunk
- Simulate attacks using CALDERA
- Develop custom detection rules
- Validate attack-to-detection workflows
- Test network resilience using Infection Monkey

---

Key Achievements

Threat Intelligence Platform

- Successfully deployed MISP using Docker
- Validated IOC management capabilities
- Tested MISP REST API functionality
- Integrated threat intelligence with Splunk

SIEM Deployment

- Successfully deployed Splunk Enterprise
- Configured centralized log collection
- Ingested Windows Security Event Logs
- Enabled security monitoring and alerting

Detection Engineering

Custom detections developed and validated:

- CALDERA Agent Detection
- Suspicious Process Execution Detection
- User Enumeration Detection
- Suspicious Process Chain Detection

Adversary Emulation

Executed multiple MITRE ATT&CK techniques using CALDERA, including:

- User Discovery
- Process Discovery
- Security Product Discovery
- Group Enumeration
- System Information Discovery

Lateral Movement Testing

- Successfully deployed Infection Monkey
- Tested endpoint discovery
- Evaluated network visibility and resilience

---

End-to-End SOC Validation

The complete attack-to-detection pipeline was successfully demonstrated.

Workflow

1. Attack simulated using CALDERA
2. Windows security events generated
3. Splunk Universal Forwarder collected telemetry
4. Splunk indexed security events
5. Detection rules triggered successfully
6. MISP enriched investigations with IOC data

This validated a realistic SOC workflow from adversary activity through detection and investigation.

---

Screenshots

MISP Deployment

Add MISP screenshots here.

Splunk Monitoring

Add Splunk screenshots here.

CALDERA Operations

Add CALDERA screenshots here.

Detection Engineering

Add detection screenshots here.

Infection Monkey

Add Infection Monkey screenshots here.

---

Technical Challenges

Throughout the project, numerous deployment and integration challenges were encountered and resolved, including:

- Operating system compatibility issues
- PHP dependency conflicts
- Docker deployment troubleshooting
- Threat intelligence integration issues
- Splunk configuration challenges
- Virtual machine networking problems

Resolving these issues provided valuable hands-on experience with enterprise security technologies.

---

Lessons Learned

- Stability is more important than using the newest software releases.
- Docker significantly simplifies complex deployments.
- Effective troubleshooting is a critical cybersecurity skill.
- Threat intelligence enhances investigative capabilities.
- Detection engineering requires continuous testing and validation.
- Documentation is essential for successful security operations.

---

Documentation

The complete project report is available in the repository documentation folder.

/docs/Wilfred_Amimo_SOC_Lab_Report.pdf

---

Author

Wilfred Amimo

SOC Analyst | Threat Intelligence | Detection Engineering | Security Monitoring

Nairobi, Kenya

---

Disclaimer

This project was conducted in a controlled laboratory environment for educational, research, and defensive cybersecurity purposes only.
