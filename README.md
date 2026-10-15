\# 🛡️ Wazuh SIEM Home Lab



\*\*Hands-on Security Information and Event Management (SIEM) | Endpoint Monitoring | Threat Detection\*\*



A cybersecurity home-lab portfolio documenting Wazuh SIEM setup, Windows endpoint monitoring, security-event analysis, detection troubleshooting, and practical blue-team learning.



> \*\*Project status:\*\* Lab documentation and practical investigation notes. Individual detections and integrations will be marked verified only when supported by actual test results.



\## 📌 Overview



This repository documents my hands-on learning in security monitoring and incident detection using Wazuh and Windows endpoints.



The objective is to understand how security events are collected, analyzed, and investigated in a SIEM environment, while developing practical troubleshooting and blue-team skills.



\## 🎯 Objectives



\- Understand SIEM architecture and security-event collection.

\- Learn Wazuh manager, dashboard, and endpoint-agent concepts.

\- Explore Windows endpoint monitoring and security logs.

\- Investigate alerts and understand detection rules.

\- Troubleshoot agent connectivity and missing security events.

\- Document controlled security testing and lessons learned.



\## 🏗️ Architecture



```mermaid

flowchart TD

&#x20;   A\["Windows Endpoint"] --> B\["Wazuh Agent"]

&#x20;   B --> C\["Wazuh Manager"]

&#x20;   C --> D\["Detection Rules and Analysis"]

&#x20;   D --> E\["Wazuh Dashboard"]

&#x20;   E --> F\["Alert Investigation"]

&#x20;   G\["Authorized Lab Activity"] --> A

```



\*This diagram illustrates the intended monitoring workflow. It does not, by itself, confirm that every component is currently connected or operational.\*



\## 🧰 Technology Stack



| Technology | Purpose |

|---|---|

| Wazuh | Security monitoring and event analysis |

| Windows | Endpoint monitoring and log generation |

| Kali Linux | Controlled lab testing, where configured |

| Virtual machines | Isolated lab environment |

| Networking tools | Connectivity and troubleshooting |

| Git and GitHub | Version control and documentation |



\## 🔬 Planned Lab Modules



\### 1. Wazuh Deployment and Configuration

\- Document the lab architecture and installation process.

\- Record manager and dashboard configuration.

\- Document setup issues and their resolutions.



\### 2. Windows Endpoint Monitoring

\- Document Wazuh agent installation and enrollment.

\- Verify endpoint connectivity.

\- Investigate Windows event collection.

\- Record evidence of successful event ingestion.



\### 3. Alert Investigation

\- Examine generated security alerts.

\- Record rule IDs, severity, timestamps, and event descriptions.

\- Explain the meaning of findings and possible false positives.

\- Document investigation steps and conclusions.



\### 4. Detection and Troubleshooting

\- Investigate missing events and agent connectivity issues.

\- Document rule and configuration troubleshooting.

\- Record expected versus observed results.

\- Verify changes through repeatable tests.



\### 5. Controlled Attack-and-Detection Exercises

\- Generate benign test activity in an isolated, authorized lab.

\- Observe whether relevant events are collected.

\- Record whether a corresponding alert is generated.

\- Document limitations and detection gaps.



\## 📁 Repository Structure



```text

wazuh-siem-home-lab/

├── README.md

├── docs/

│   ├── architecture.md

│   ├── setup-guide.md

│   ├── windows-agent.md

│   ├── alert-investigations.md

│   └── troubleshooting.md

├── labs/

│   ├── windows-monitoring/

│   └── detection-testing/

└── screenshots/

&#x20;   └── README.md

```



Additional files will be added as the corresponding labs are completed and verified.



\## 📊 Lab Evidence



Planned evidence includes:



\- Wazuh dashboard screenshots with sensitive details removed.

\- Agent status and connectivity checks.

\- Sanitized alert examples.

\- Test procedures and observed results.

\- Troubleshooting notes.



Only genuine screenshots and results from the lab will be included.



\## 📚 Key Learning Outcomes



This project is intended to develop practical understanding of:



\- SIEM architecture and log ingestion.

\- Endpoint monitoring and event analysis.

\- Alert triage and detection-rule interpretation.

\- Basic incident-investigation workflows.

\- Security troubleshooting and technical documentation.



\## 🔐 Responsible Use



All testing must take place on systems I own or have explicit authorization to assess.



This repository must not contain passwords, API keys, private certificates, real customer data, confidential company logs, or unredacted incident evidence.



Security testing will be restricted to isolated and authorized environments.



\## 🚀 Future Improvements



\- Add verified installation and configuration instructions.

\- Include sanitized alert-investigation case studies.

\- Document Windows event collection and detection testing.

\- Add architecture and workflow diagrams.

\- Include reproducible troubleshooting examples.



\## 👨‍💻 About



This repository is part of my cybersecurity learning portfolio, focused on SIEM operations, endpoint monitoring, threat detection, and blue-team investigation.



\*\*Note:\*\* This is a learning and documentation project, not a claim of production-grade security monitoring or comprehensive threat detection.



