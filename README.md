# Microsoft Defender XDR Attack Scenarios
Advanced Microsoft Defender XDR Detection Engineering project with KQL hunting queries, attack scenarios, MITRE ATT&amp;CK mapping and SOC investigation playbooks.
---

## Overview

This repository provides advanced attack scenarios for Microsoft Defender XDR.

Each scenario includes:

- Attack Overview
- Detection Logic
- KQL Hunting Queries
- MITRE ATT&CK Mapping
- Investigation Guide
- False Positives
- Detection Tuning
- References

The objective is to help SOC analysts, Detection Engineers and Blue Teams detect, investigate and understand real-world attack techniques.

---

## Repository Structure

```
📂 scenarios/
📂 kql/
📂 playbooks/
📂 docs/
📂 templates/
📂 tools/
📂 images/
```

---

## Attack Scenarios

| ID | Scenario | Status |
|----|----------|--------|
| SCN-001 | Password Spraying | 🚧 |
| SCN-002 | Adversary-in-the-Middle (AiTM) | 🚧 |
| SCN-003 | Device Code Phishing | 🚧 |
| SCN-004 | Active Directory Enumeration | 🚧 |
| SCN-005 | Kerberoasting | 🚧 |
| SCN-006 | DCSync | 🚧 |
| SCN-007 | Pass-the-Hash | 🚧 |
| SCN-008 | Shadow Credentials | 🚧 |
| SCN-009 | AD CS ESC1 | 🚧 |
| SCN-010 | Ransomware Detection | 🚧 |

---

## Detection Coverage

- Microsoft Defender XDR
- Microsoft Defender for Endpoint
- Microsoft Defender for Identity
- Microsoft Defender for Office 365
- Microsoft Defender for Cloud Apps
- Microsoft Sentinel

---

## MITRE ATT&CK

Coverage is mapped to the MITRE ATT&CK framework.

Examples include:

- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Defense Evasion
- Credential Access
- Discovery
- Lateral Movement
- Collection
- Exfiltration
- Impact

---

## Contributing

Contributions are welcome.

Please open an Issue before submitting a Pull Request.

---

## License

MIT License
