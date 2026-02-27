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


