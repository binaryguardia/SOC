# 🛡️ Wazuh SIEM Setup & Log Analysis – Blue Team Journey

Welcome to my Blue Team exploration with **Wazuh**, an open-source SIEM and security monitoring platform. This project documents how I set up Wazuh from a `.ova` file and started working with **log analysis**.

---

## 📌 What is Wazuh?

> Wazuh is a free, open-source security monitoring solution that provides intrusion detection, vulnerability detection, log analysis, file integrity monitoring, and more — all integrated into a centralized platform.

---

## ⚙️ Setup Overview

### ✅ Requirements:
- VirtualBox or VMware
- Wazuh `.ova` file (Download from [Wazuh Downloads](https://wazuh.com/downloads/))
- 4 GB RAM minimum (8 GB recommended)
- 2 vCPUs
- Internet access

---

### 🗂️ Step-by-Step Installation

#### 1. Import Wazuh OVA
- Open VirtualBox or VMware.
- File > Import Appliance > Select `wazuh.ova`.
- Set your RAM/CPU allocation.
- Finish import and start the VM.

#### 2. Network Configuration (Optional)
- Use **Bridged Adapter** for local network access.
- Check the IP address inside Wazuh VM with:  
  ```bash
  ip a
  ```

#### 3. Access Wazuh Dashboard
- Open browser and go to:  
  `https://<your-wazuh-ip>`
- Default credentials:  
  - **Username:** `admin`  
  - **Password:** `admin` *(change after first login)*

---

## 🔍 Features Explored

### ✅ Dashboard Walkthrough
- Visual overview of active agents, alerts, rules, and modules.
- Real-time event monitoring.
![image](https://github.com/user-attachments/assets/08a87a1d-b194-4f35-b0c0-a0d27de2add2)

### ✅ Log Analysis (First Steps)
- Monitored logs from the Wazuh server itself.
- Understood different alert levels (0–15).
- Reviewed `auth.log`, `syslog`, and file integrity modules.

---

## 🔐 Wazuh Use Cases (To Explore Next)

- File Integrity Monitoring (FIM)
- Active Response
- Vulnerability Detection
- Agent-based monitoring (Linux & Windows systems)
- Integrating with Elastic Stack or Splunk

---

## 📘 Learnings So Far

- Setting up `.ova` images can be tricky with network & memory issues.
- Wazuh is **feature-rich but lightweight** — great for learning SIEM.
- Even without agents, you can practice log review and alert triage.

---

## 💡 Recommendations

> If you're starting in **blue teaming** or want to learn **SOC-level monitoring**, Wazuh is a must-try. It helps bridge the gap between **theory and real-world** monitoring tasks.

---

## 🚀 Let's Grow Together

I’m currently deepening my knowledge in:
- Rule customization
- Agent integration
- Threat detection logic

If you’re learning Wazuh or working in Blue Team, feel free to connect or contribute ideas!

---

## 📎 Resources

- [Official Wazuh Documentation](https://documentation.wazuh.com/)
- [Wazuh YouTube Tutorials](https://www.youtube.com/@Wazuh)

---

🔧 *Author:* Neeraj Kumar  
📅 *Last Updated:* June 2025  
