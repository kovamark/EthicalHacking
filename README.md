CS-381 Ethical Hacking Final Project
---

by Connor McCarty, Mark Kovach, and Philipp Pedron


---

This repository documents a multi-faceted security assessment designed to simulate a real-world penetration test, covering the entire engagement lifecycle from initial reconnaissance to final defensive recommendations. The project demonstrates a wide array of offensive and defensive cybersecurity techniques across various domains.
Project Phases & Key Activities:
1. Reconnaissance and Information Gathering (Task 1):
Conducted extensive Open-Source Intelligence (OSINT) gathering using tools like theHarvester, Recon-ng, and Maltego.
Successfully mapped target domains, discovered subdomains and infrastructure, and identified potential entry points for further investigation.
2. Network Scanning and Enumeration (Task 2):
Performed active network scanning and service enumeration with Nmap to identify live hosts, open ports, and running service versions on target systems.
3. Vulnerability Assessment (Task 3):
Executed automated vulnerability scans to pinpoint specific weaknesses, including outdated software, misconfigurations, and known backdoors in services like FTP, IRC, and Samba.
4. Exploitation and System Hacking (Task 4):
Leveraged the Metasploit Framework to successfully exploit identified vulnerabilities, gaining root-level access and demonstrating methods for establishing persistence on compromised hosts.
5. Specialized Security Audits (Tasks 5, 7, 9, 10):
Wireless Security: Assessed Wi-Fi network vulnerabilities using the Aircrack-ng suite.
Malware Analysis: Performed static analysis on a Petya ransomware sample using Ghidra.
Cryptography: Evaluated SSL/TLS configurations for cryptographic weaknesses with SSLyze.
Cloud & IoT Security: Audited simulated Cloud (AWS via LocalStack) and IoT environments for common misconfigurations and security flaws.
6. Traffic Analysis & Social Engineering (Tasks 6 & 8):
Conducted network traffic sniffing with Wireshark to capture and analyze unencrypted communications.
Executed a simulated phishing campaign using the Social-Engineer Toolkit (SET) to assess organizational susceptibility to social engineering attacks.
7. Defensive Strategies (Task 11):
Developed custom Intrusion Detection System (IDS) rules using Snort to detect malicious network activity.
Designed a comprehensive network segmentation plan to mitigate risks and enhance the overall security posture of the environment.
