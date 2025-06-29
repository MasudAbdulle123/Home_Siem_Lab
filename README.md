# 🛡️ Home SIEM Lab with Wazuh

A hands-on cybersecurity project simulating real-world attack techniques in a virtualized lab environment, with threat detection using the open-source Wazuh SIEM platform. This lab was built to demonstrate skills in log analysis, endpoint monitoring, and incident detection.

---

## 🧠 Project Overview

For this Project I set up a wazuh server on a VM to montior a windows 10 endpoint running on physical hardware. I then simulated malicious activity on the endpoint in order to generate logs which where collected and analysed by Wazuh in real time. The idea was to learn about SIEM tools 'hands on' whilst also learing about security monitoring and threat detection.



---

## 🧰 Tools & Technologies

- **Wazuh SIEM** (Manager, Indexer, Dashboard)
- **VirtualBox** (Ubuntu Server VM)
- **Windows 10 endpoint** (physical desktop)
- **Wazuh Agent** for Windows
- **PowerShell** (for executing simulated attacks)

---

## 🧪 Simulated Attack Techniques

| Technique | Description |
|----------|-------------|
| Brute-force login attempts | Repeated failed login attempts at lock screen | 
| Unauthorized user creation | Created new local account via command line | 
| PowerShell misuse | Obfuscated command execution | 
| Log tampering | Cleared Windows Security event log |

---

## 🖼️ Screenshots

> All screenshots are located in the `screenshots/` folder.

- `agent-active.png` — Windows machine registered and active in Wazuh
- `failed-logins-alert.png` — Alert triggered by repeated failed logins
- `user-creation-alert.png` — New user account detected
- `powershell-command-alert.png` — Suspicious PowerShell execution
- `log-clearing-alert.png` — Security log tampering alert
- `dashboard-overview.png` — Wazuh dashboard overview

---

## 🔍 Key Learning Outcomes

- Gained hands-on experience deploying and configuring a functional SIEM
- Demonstrated knowledge of endpoint log monitoring and agent deployment
- Simulated real-world attack behaviors
- Analyzed security alerts and logs to understand threat detection workflows
- Learned to document and communicate technical processes clearly
