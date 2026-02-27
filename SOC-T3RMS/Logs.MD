# Logs
Logs are recorded records of events, activities, or transactions that occur within a system, application, network, or device.

In cybersecurity, logs capture details such as:
1.User logins and logouts
2.Commands executed
3.System errors
4.Network connections
5.Security events

Logs are used for monitoring, troubleshooting, auditing, and incident investigation.

## Types of logs

### Linux
---

## 1️⃣ System Logs

* `/var/log/syslog` (Debian/Ubuntu)
* `/var/log/messages` (RHEL/CentOS)
* `/var/log/dmesg`
* `/var/log/boot.log`

---

## 2️⃣ Authentication & Access Logs

* `/var/log/auth.log` (Debian/Ubuntu)
* `/var/log/secure` (RHEL/CentOS)
* `/var/log/faillog`
* `/var/log/lastlog`
* `/var/log/wtmp`
* `/var/log/btmp`

---

## 3️⃣ Sudo Logs

* `/var/log/auth.log`
* `/var/log/secure`

---

## 4️⃣ Audit Logs

* `/var/log/audit/audit.log`

---

## 5️⃣ Kernel Logs

* `/var/log/kern.log`
* `journalctl -k`

---

## 6️⃣ Firewall Logs

* `/var/log/ufw.log`
* `/var/log/firewalld`
* `/var/log/syslog`
* `/var/log/messages`

---

## 7️⃣ Network Logs

* `/var/log/syslog`
* `/var/log/messages`
* `journalctl -u NetworkManager`

---

## 8️⃣ Web Server Logs

* `/var/log/apache2/access.log`
* `/var/log/apache2/error.log`
* `/var/log/nginx/access.log`
* `/var/log/nginx/error.log`

---

## 9️⃣ Database Logs

* `/var/log/mysql/`
* `/var/log/mariadb/`
* `/var/log/postgresql/`

---

## 🔟 Mail Server Logs

* `/var/log/mail.log`
* `/var/log/maillog`

---

## 1️⃣1️⃣ Cron & Scheduled Jobs

* `/var/log/cron`
* `/var/log/syslog`

---

## 1️⃣2️⃣ Application Logs

* `/var/log/<application_name>/`

---

## 1️⃣3️⃣ Package Management Logs

* `/var/log/dpkg.log`
* `/var/log/yum.log`
* `/var/log/apt/history.log`

---

## 1️⃣4️⃣ SELinux Logs (RHEL-based)

* `/var/log/audit/audit.log`

---

## 1️⃣5️⃣ Systemd Journal Logs

* `/var/log/journal/`
* `journalctl`

---

## 1️⃣6️⃣ IDS/IPS Logs (if installed)

* `/var/log/snort/`
* `/var/log/suricata/`

---

## 1️⃣7️⃣ Fail2Ban Logs

* `/var/log/fail2ban.log`

### Windows
---

## 1️⃣ Security Logs

**Path:**
`C:\Windows\System32\winevt\Logs\Security.evtx`

Contains: Logon events, privilege use, account changes, policy changes.

---

## 2️⃣ System Logs

**Path:**
`C:\Windows\System32\winevt\Logs\System.evtx`

Contains: Driver loads, service starts/stops, system failures.

---

## 3️⃣ Application Logs

**Path:**
`C:\Windows\System32\winevt\Logs\Application.evtx`

Contains: Application errors, crashes, warnings.

---

## 4️⃣ Setup Logs

**Path:**
`C:\Windows\System32\winevt\Logs\Setup.evtx`

Contains: Windows installation and update events.

---

## 5️⃣ Windows Defender Logs

**Path:**
`C:\ProgramData\Microsoft\Windows Defender\Support\`
Event Log:
`Microsoft-Windows-Windows Defender%4Operational.evtx`

---

## 6️⃣ PowerShell Logs

**Path:**
`C:\Windows\System32\winevt\Logs\Microsoft-Windows-PowerShell%4Operational.evtx`

---

## 7️⃣ Sysmon Logs (if installed)

**Path:**
`C:\Windows\System32\winevt\Logs\Microsoft-Windows-Sysmon%4Operational.evtx`

---

## 8️⃣ Task Scheduler Logs

**Path:**
`C:\Windows\System32\winevt\Logs\Microsoft-Windows-TaskScheduler%4Operational.evtx`

---

## 9️⃣ Firewall Logs

Default Location:
`C:\Windows\System32\LogFiles\Firewall\pfirewall.log`

---

## 🔟 RDP Logs

Security Event Log (Logon Type 10)
Path:
`C:\Windows\System32\winevt\Logs\Security.evtx`

---

## 1️⃣1️⃣ DNS Server Logs (if enabled)

`C:\Windows\System32\dns\`

---

## 1️⃣2️⃣ IIS Web Server Logs

`C:\inetpub\logs\LogFiles\`

---

## 1️⃣3️⃣ Active Directory Logs (Domain Controller)

`C:\Windows\NTDS\`
Event logs inside:
`Security.evtx`

---

## 1️⃣4️⃣ Group Policy Logs

`C:\Windows\System32\winevt\Logs\Microsoft-Windows-GroupPolicy%4Operational.evtx`

---

## 1️⃣5️⃣ BitLocker Logs

`Microsoft-Windows-BitLocker%4Management.evtx`

---

## 1️⃣6️⃣ Windows Update Logs

Generated via:
`Get-WindowsUpdateLog`

Raw logs stored in:
`C:\Windows\SoftwareDistribution\ReportingEvents.log`

---

## 1️⃣7️⃣ SMB / File Share Logs

Security Event Log (Object Access events)
`Security.evtx`

---

## 1️⃣8️⃣ Print Service Logs

`Microsoft-Windows-PrintService%4Operational.evtx`

