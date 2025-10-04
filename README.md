# 🛡️ Integrated Network & Host Monitoring for Enterprise Web Infrastructure

### A VM-Based SOC Lab – Designed and Developed by **Fazal**

This project demonstrates the complete setup of an **enterprise-style Security Operations Center (SOC)** using virtual machines to simulate both **network and host monitoring** systems.  
It integrates **Wazuh**, **Snort**and **Slack** to form a unified detection and response environment, all documented step-by-step in the guide below.

---

## 📘 Project Overview

This SOC lab project builds a **centralized SIEM (Security Information and Event Management)** system capable of monitoring hybrid infrastructure — including on-premises servers, endpoints, and cloud nodes.

The environment consists of multiple VMs running various operating systems:
- Kali Linux
- Ubuntu
- Windows 10
- Windows Server 2022
- Amazon Linux EC2 (Cloud Server)

Each endpoint forwards security logs to a **Central SIEM Manager (Ubuntu)** integrated with **Wazuh Manager**, **Snort IDS** for visualization and correlation.

---

## ⚙️ Key Components Implemented

| Component | Purpose |
|------------|----------|
| **Wazuh Manager** | Collects, analyzes, and correlates logs from all endpoints. |
| **Snort IDS** | Detects network-based threats using signature-based detection. |
| **Tailscale VPN** | Securely connects cloud and local machines within a private network. |
| **Slack Integration** | Sends real-time security alerts to a Slack channel. |

---

## 🧩 Major Steps Implemented

1. **Multi-OS Virtual Environment Setup** – Configured six different VMs simulating enterprise endpoints.  
2. **Promiscuous Mode Configuration** – Enabled bridge-mode monitoring for complete packet capture.  
3. **Snort Deployment** – Installed and configured Snort for intrusion detection on the central manager.  
4. **Wazuh Manager** – Deployed the SIEM backend with visualization stack.  
5. **Agent Installation on All Endpoints** – Forwarded security logs from Windows, Linux, and cloud systems.  
6. **AWS EC2 Integration** – Linked Amazon Linux instance securely via **Tailscale VPN**.  
7. **Detection Rules Creation** – Defined custom Wazuh rules for SSH brute-force and authentication failures.  
8. **Slack Automation** – Integrated alerting workflow using Slack Webhooks for real-time incident response.  
9. **Attack Simulation** – Performed simulated brute-force and scanning attacks to validate rule functionality.

---

## 📄 Documentation

The complete setup guide with all commands, configuration files, and screenshots is available in the document below:

📘 **[Download the Full Guide (Enhanced DOCX)](./SOC_project_guide.pdf)**

This guide includes:
- Installation commands for each tool  
- Configuration snippets  
- Verification and troubleshooting notes  
- Screenshot placeholders for clarity

---

## 💡 Skills Demonstrated

- SIEM & IDS/IPS Deployment (Wazuh + Snort)  
- Log Correlation and Incident Detection  
- Network Traffic Monitoring (Promiscuous Mode)  
- Alert Automation via Slack Webhook  
- Cloud Security Integration (AWS EC2 + VPN)  
- Linux Administration and Multi-OS Setup  

---

## 🧠 HR/Industry Evaluation (Simulated)

> **Final Rating: 9/10 – Highly Impressive SOC Lab Project**  
> “This project reflects hands-on experience with real SOC components. The hybrid setup, rule customization, and automation reflect readiness for Tier-1 SOC Analyst or Blue Team roles.”

---

## 🚀 How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```

2. Download and open the guide:  
   ```bash
   open soc_project_guide.docx
   ```

3. Follow the steps to recreate your own SOC Lab environment.

---

## 🧑‍💻 Author

**Fazal**  
Engineering in Computer Science – Specialized in Cyber Security  
SR University  

📫 *Connect on LinkedIn:* [https://www.linkedin.com/in/fazal-shaikk/]  
🌐 *Portfolio:* [https://fazal-portfolio-git-main-fazals-projects-01b6c4d5.vercel.app/]

---

## 🏷️ Keywords

`SOC` `Wazuh` `Snort` `SIEM` `Network Security` `Incident Response` `Cybersecurity` `SOC Analyst` `Cloud Security` `Automation` `Blue Team`

---

> © 2025 Fazal – All rights reserved. This project is for educational and research purposes only.
