\# Wazuh SIEM Lab — Practical Work and Troubleshooting



\## 1. Lab Overview



This document records my practical cybersecurity learning involving Wazuh SIEM, Windows endpoint monitoring, and controlled lab activity using VirtualBox.



\*\*Focus areas\*\*

\- SIEM deployment and dashboard access

\- Windows endpoint agent monitoring

\- Security logs, detection rules, and alerts

\- Network connectivity and troubleshooting

\- Kali Linux attacker → Windows endpoint → Wazuh monitoring architecture



\## 2. Lab Architecture



```mermaid

flowchart TD

&#x20;   A\["Kali Linux — Lab Testing"] --> B\["Windows — Lab Endpoint"]

&#x20;   B --> C\["Wazuh Agent"]

&#x20;   C --> D\["Wazuh Manager"]

&#x20;   D --> E\["Wazuh Dashboard"]

&#x20;   E --> F\["Security Event Investigation"]

```



This represents the intended lab design. Successful event delivery and detection must be verified using actual lab evidence.



\## 3. Work Performed



\### Wazuh Environment

\- Worked with the Wazuh OVA in VirtualBox.

\- Explored the Wazuh manager and dashboard environment.

\- Troubleshot dashboard access and virtual-network connectivity.



\### Windows Endpoint Monitoring

\- Worked with Windows agent configuration and connectivity.

\- Explored Windows log collection, detection rules, and alerts.

\- Investigated issues involving missing logs or alerts.



\### Controlled Network Security Lab

\- Worked on a Kali Linux-to-Windows lab design.

\- Explored how endpoint monitoring can support investigation of security-related activity.

\- Focused on understanding the relationship between test activity, collected events, and SIEM alerts.



\## 4. Troubleshooting Areas



| Area | Investigation focus |

|---|---|

| Dashboard access | Connectivity and access to the Wazuh interface |

| Virtual networking | Communication between virtual machines |

| Agent connectivity | Whether the Windows agent can communicate with the manager |

| Missing logs | Event collection and configuration |

| Missing alerts | Rules, event visibility, and detection conditions |



These are areas I worked on investigating. A specific fix should be recorded only when supported by a verified result.



\## 5. Evidence to Add



For each completed test, record:



1\. Objective

2\. Lab configuration

3\. Commands or configuration changes

4\. Expected result

5\. Actual result

6\. Screenshot or log evidence, with sensitive information removed

7\. Troubleshooting performed

8\. Lessons learned



\## 6. Current Limitations



This document records practical work and troubleshooting areas, but does not claim that every configuration issue was resolved or every test generated a successful alert.



Verified commands, screenshots, alert IDs, and test results will be added as evidence becomes available.



\## 7. Responsible Use



All security testing must be performed on systems I own or have explicit permission to assess.



No credentials, private keys, company-confidential information, or unredacted security logs should be committed to this repository.



