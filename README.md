# 🛡️ Wazuh HomeLab – Security Monitoring Project

This project showcases my hands-on work in setting up and exploring a Wazuh-based SIEM/XDR HomeLab. It includes threat detection, file monitoring, Docker visibility, and attack simulation using Kali Linux. Built using VirtualBox with a Wazuh server and multiple agents.

---

## ✅ What I Did

### 🔐 Threat Detection & Monitoring
- Detected brute-force attacks:
  - 🚫 Failed login attempts
  - ✅ Successful logins after failed attempts
- Detected creation of new user accounts
- Detected execution of suspicious or malicious shell commands
- Detected anomalous outbound/inbound network traffic

### 📂 File Integrity Monitoring (FIM)
- Detected file additions in sensitive directories
- Detected unauthorized modifications to monitored files

### 🐛 Malware & Binary Analysis
- Detected suspicious binaries placed or executed on the system

### 💉 Exploitation & Attack Simulation
- Detected:
  - SQL Injection attempts
  - Shellshock attack via simulated payloads
  - Unauthorized process creation

### 🔄 IDS Integration
- Integrated **Suricata IDS** with Wazuh
- Detected anomalies from Suricata alerts

### 🐳 Cloud/Container Visibility
- Enabled and monitored Docker container events

### 🛡️ Vulnerability Detection
- Enabled automatic scanning of vulnerabilities on the Ubuntu system using Wazuh's vulnerability detector module

---

## ⚙️ Tools & Technologies Used
- **Wazuh** (Server + Agent)
- **Ubuntu** (Monitored endpoint)
- **Kali Linux** (Attack simulation)
- **Suricata** (IDS integration)
- **Docker** (Container event monitoring)
- **VirtualBox** (Lab virtualization)


