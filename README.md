📘 Project Overview
This mini project demonstrates Linux Identity and Access Management (IAM) and System Hardening techniques on Ubuntu.
It focuses on managing users, groups, and file permissions securely — while identifying and fixing misconfigurations in a vulnerable system.

🎯 Objective
Build a secure IAM model (Users, Groups, Permissions)
Detect and fix 3 misconfigurations in a vulnerable VM
Generate a remediation report and checklist
🧰 Tools & Environment
Ubuntu Server VM (for IAM & Hardening)
Kali/Attacker VM (for testing)
sudo access for configuration
Tools: useradd, chmod, acl, auditd, visudo
🧩 Tasks
🧠 Task 1 — Policy + User & Group Configuration
Create roles: Admin, Developer, Auditor
Add users & groups using useradd and groupadd
Apply least privilege principle in /etc/sudoers
Use POSIX permissions + ACLs for folder control
Enable auditd to track /etc/sudoers and /etc/passwd changes
🔍 Task 2 — Vulnerability Analysis & Remediation
Analyze vulnerable VM and find 3 issues:
World-writable /etc/cron.d
Sudo with NOPASSWD
Weak file permissions on /etc/shadow
Fix each issue, record evidence (before/after)
Create a Remediation Checklist and a Policy Document
📚 Skills & Learning
Linux user & group management
File permissions & ACLs
Sudo security configuration
Auditing & logging with auditd
Detecting and fixing vulnerabilities
📸 Screenshots
Screenshot 2025-11-06 012217 Screenshot 2025-11-06 012847 Screenshot 2025-11-06 012857 Screenshot 2025-11-06 012935 Screenshot 2025-11-06 013006 Screenshot 2025-11-06 012951 Screenshot 2025-11-06 013016 Screenshot 2025-11-06 013043 Screenshot 2025-11-06 013034 Screenshot 2025-11-06 013057
