# SOC-Wazuh-SIEM-lab

##Overview
A home lab simulating real world attack and detection scenarios using Wazuh SIEM. The goal is to practice SOC skills by attacking Windows 10 VM from Kali while detecting threats in real time using Wazuh.

##Architecture
-192.168.56.101 - Wazuh (SIEM)
-192.168.56.102 - Kali (attacker)
-192.168.56.103 - Windows (victim)
Network: VirtualBox Host-Only + NAT

##Tools
-Wazuh 4.14.5 - SIEM
-Windows 10 - monitored endpoint / victim
-Kali Linux - attacker

##Lab status
-Wazuh SIEM deployed
-Windows-victim agent connected
-Kali Linux attacker machine configured

<img width="1876" height="957" alt="wazuh-dashboard" src="https://github.com/user-attachments/assets/2c540386-52f8-48eb-a6e3-754666c5807b" />

