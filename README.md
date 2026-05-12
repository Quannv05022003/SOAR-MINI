SOAR Lab – Wazuh + Shuffle + TheHive

Overview

This project demonstrates a basic SOAR (Security Orchestration, Automation, and Response) workflow using open-source tools.

The lab integrates Wazuh, Shuffle, and TheHive to automate security alert handling and incident response processes.

Objectives

Automate security alert workflows,
Integrate SIEM alerts with SOAR automation,
Generate incidents automatically,
Improve response efficiency,
Practice basic incident response operations.

Technologies Used

Wazuh,
Shuffle,
TheHive,
VirusTotal,
Ubuntu Server,
Kali Linux.


Features

Automated alert processing,
Wazuh alert integration,
VirusTotal enrichment,
Automatic incident creation in TheHive,
Telegram notification,
Basic active response automation.

Attack Scenarios

Mimikatz Detection,
SSH Brute Force Attack.

Workflow

1. Wazuh detects suspicious activity
2. Alert is sent to Shuffle
3. Shuffle enriches data using VirusTotal
4. Incident is created in TheHive
5. Notification is sent to SOC analyst
6. Active response can be triggered automatically

Lab Environment

Ubuntu Server (Wazuh + TheHive + Shuffle),
Windows Victim Machine,
Ubuntu Victim Machine,
Kali Linux Attacker.

Author

Nguyen Viet Quan.
