# SOC Home Lab: Security Monitoring with Wazuh

## Project Overview

This project documents the development of a home Security Operations Center (SOC) lab to practice security monitoring, endpoint log collection, alert analysis, and incident investigation.

The lab uses Wazuh as the security monitoring platform, an Ubuntu virtual machine to host the Wazuh components, and a Windows 11 virtual machine as the monitored endpoint.

## Objectives

- Deploy and configure a Wazuh SIEM environment.
- Connect a Windows endpoint to the Wazuh manager.
- Explore Windows security events and endpoint activity.
- Practice identifying suspicious behavior and investigating security alerts.
- Document findings using a structured incident investigation process.

## Lab Environment

| Component | Purpose |
|---|---|
| Oracle VirtualBox | Virtualization platform |
| Ubuntu Linux | Wazuh server environment |
| Wazuh | Security monitoring and SIEM platform |
| Windows 11 | Monitored endpoint |
| Windows Event Viewer | Review of endpoint event logs |

## Architecture

Windows 11 Endpoint → Wazuh Agent → Wazuh Manager → Wazuh Dashboard

The lab uses virtual machines on a private home network. Network details and sensitive configuration information are intentionally excluded from this public repository.

## Implementation Progress

- [x] Create the Windows 11 virtual machine.
- [x] Install and enable Microsoft Defender.
- [x] Deploy the Wazuh server components.
- [x] Install the Wazuh agent on the Windows endpoint.
- [x] Confirm that the agent is active.
- [x] Begin reviewing Windows event logs.
- [ ] Validate collection of the required endpoint events in Wazuh.
- [ ] Conduct and document an end-to-end security investigation.
- [ ] Document detection findings and lessons learned.

## Tools and Technologies

- Wazuh SIEM and endpoint monitoring
- Ubuntu Linux
- Windows 11
- Oracle VirtualBox
- Windows Event Viewer
- PowerShell
- Windows security logging

## Investigations

Investigation reports will document the activity tested, relevant log sources, event timestamps, investigation steps, evidence, findings, and recommended follow-up actions.

## Lessons Learned

This section will document configuration challenges, troubleshooting steps, observations about endpoint telemetry, and improvements made to the lab.

## Disclaimer

This lab is for educational and defensive cybersecurity purposes. Testing is conducted in a controlled environment using virtual machines that I manage. Sensitive credentials, personal information, and private configuration details are excluded from this repository.
