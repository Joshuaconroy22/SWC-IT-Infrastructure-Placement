 # SWC-IT-Infrastructure-Placement

# Introduction 

Welcome to the documentation repository for my 12-week Work-Based Learning placement as an IT Technician at a large Further & Higher Education Institution in the UK. 

During this placement, I was integrated into the central IT Support team, operating across a large-scale, multi-campus educational estate. The role encompassed maintaining Windows 11 endpoints, Active Directory environments, network switch handshakes, specialized AV equipment, and automated print fleets. 

This repository serves as a portfolio of my hands-on technical work, detailing enterprise network troubleshooting, endpoint incident response, hardware component repairs, and asset management audits executed during the placement.

----------------------------------------------------------------------------------------------------------------------------

Featured Major Project: Campus-Wide Laptop Battery & Infrastructure Audit

> Scope: Multi-campus fleet | 80+ endpoints | Mobile Charging Infrastructure
> Role:  Technician for Audit & Remediation

Problem Statement
Degraded laptop batteries and misconfigured charging trolleys were causing frequent mid-class device failures across multiple academic departments, leading to heavy daily support ticket volume and disrupted learning environments.

Execution & Technical Methodology
Comprehensive Health Audit: Systematically documented cycle counts, battery capacity vs. design capacity, and physical degradation across mobile trolleys (including rooms OT81 and OF62).
Infrastructure Remediation: Identified a critical systemic fault where Power Distribution Unit (PDU) timers were misconfigured. Recalibrated PDUs to safe 2-hour cycles to prevent overcharging, severe battery swelling, and thermal degradation.
Asset Tracking System: Solved a persistent operational bottleneck where devices were mixed across three separate trolleys by designing and implementing a standardized labeling and attribution system for senior management approval.

Impact & Outcomes
* Cost Prevention: Extended asset lifecycle for 80+ endpoints, preventing premature battery replacements.
* Ticket Reduction: Reduced daily emergency support tickets related to dead classroom laptops.
* Process Improvement: Established a standardized reporting template adopted by the team for ongoing preventative maintenance.

Additional Technical Achievements

* Fleet Network Remediation: Executed CLI commands (`gpupdate /force`) across 300+ laptops (19 trolleys) to restore Domain Controller authentication following switch firmware updates.
* Hardware & Security Interventions: Performed Dell motherboard replacements, managing TPM security triggers and BitLocker recovery key retrieval via Active Directory.
