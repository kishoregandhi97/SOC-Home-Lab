# SOC Home Lab Project

## Overview
Built a complete Security Operations Center (SOC) home lab 
using VirtualBox, Kali Linux, and Wazuh SIEM v4.14.3.

## Tools Used
- Oracle VirtualBox 7.2.2
- Wazuh SIEM v4.14.3
- Kali Linux (Attacker)
- Windows 11 Home (Victim)
- Nmap 7.98
- Hydra (Brute Force)

## Lab Architecture
- Attacker: Kali Linux (192.168.56.x)
- Victim:   Windows 11 (192.168.56.10)
- Monitor:  Wazuh SIEM (192.168.56.3)
- Network:  Isolated Host-Only (192.168.56.0/24)

## Key Achievements
- Detected 635+ security events in 24 hours
- Mapped attacks to MITRE ATT&CK framework
- Detected brute force, privilege escalation, persistence
- Performed CIS Benchmark compliance assessment
- Identified 32 vulnerabilities across monitored systems
- Documented findings in professional incident report

## MITRE ATT&CK Tactics Detected
- Privilege Escalation (20 events)
- Persistence (18 events)
- Defense Evasion (12 events)
- Impact (10 events)
- Credential Access (2 events)

## Vulnerability Assessment
- Critical: 0
- High: 11
- Medium: 20
- Low: 1

## CIS Compliance
- Policy: CIS Windows 11 Enterprise Benchmark v3.0.0
- Score: 26% (baseline)
- Passed: 123 controls
- Failed: 350 controls

## Documentation
Full project documentation available in the repository.

## Author
Kishore Gandi - Cybersecurity Enthusiast
