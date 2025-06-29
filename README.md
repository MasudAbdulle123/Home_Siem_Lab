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


# Windows machine registered and active in Wazuh
![active_agent](https://github.com/user-attachments/assets/28b4877f-2d95-4b3c-9344-cbde824eb45e)


# Alert triggered by repeated failed logins
![Login_Failure](https://github.com/user-attachments/assets/ddf2e90c-54c3-46fa-a8b2-8b234bdd8e71)


# New user account detected
![Users_added](https://github.com/user-attachments/assets/9d99e5a2-db32-4e27-bb46-c2f3039feca0)


#  Wazuh dashboard overview
![Dashboard_Overview](https://github.com/user-attachments/assets/242e9075-77c3-422a-951a-1a413a8be79a)


Coming soon - Video Demo
---

## 🔍 Key Learning Outcomes

- Gained hands-on experience deploying and configuring a functional SIEM
- Demonstrated knowledge of endpoint log monitoring and agent deployment
- Simulated real-world attack behaviors
- Analyzed security alerts and logs to understand threat detection workflows
- Learned to document and communicate technical processes clearly
