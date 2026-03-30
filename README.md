# Linux Server Setup & Automation

Overview
This project demonstrates the setup and configuration of a secure Linux server using Ubuntu. It includes system administration tasks, security hardening, and automation using Bash scripting.

The goal of this project is to simulate real-world server management and demonstrate practical skills in Linux administration and cybersecurity fundamentals.

Features

- User and group management
- Sudo privilege configuration
- SSH server installation and secure configuration
- Apache web server setup and verification
- Firewall configuration using UFW
- Intrusion prevention using Fail2Ban
- Backup automation using Bash scripting
- Task scheduling using cron jobs

Technologies Used

- Ubuntu Server
- Bash Scripting
- Apache2
- UFW (Uncomplicated Firewall)
- Fail2Ban
- OpenSSH

Automation Script

A Bash script was created to automate backups of the `/home` directory.

Script:
bash
#!/bin/bash
DATE=$(date +%F)
tar -czf /home/montahe/backup_$DATE.tar.gz /home

Security Measures Implemented
Disabled root SSH login
Configured firewall rules using UFW
Enabled Fail2Ban to prevent brute-force attacks
Applied proper user privilege management

Screenshots: 
Apache server running
UFW status
Fail2Ban status

What I Learned
Practical Linux server setup and management
System security best practices
Bash scripting for automation
Troubleshooting permission and configuration issues
Using Git and GitHub for project version control
