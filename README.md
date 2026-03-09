#  Cerber Ransomware Attack — Detection & Defence Analysis

##  Overview
This project investigates a real-world Cerber ransomware attack 
on Wayne Enterprises using Splunk and the Lockheed Martin 
Cyber Kill Chain framework.

##  Objectives
- Identify the infection vector
- Reconstruct the full attack timeline
- Propose detection and defence strategies

##  Tools Used
- Splunk (SIEM Investigation)
- Sysmon & Windows Event Logs
- Suricata IDS
- DNS Stream Analysis
- Lockheed Martin Cyber Kill Chain

##  Attack Stages Investigated
1. Victim Identification — Host: we8105desk / IP: 192.168.250.100
2. USB Infection Vector — Device: MIRANDA_PRI
3. Malicious File Execution — Miranda_Tate_unveiled.dotm
4. C2 Communication — solidaritedeproximite.org
5. Cryptor Payload Download — mhtr.jpg
6. Process Chain Mapping — 121214.tmp
7. Local File Encryption — .txt files counted
8. Server File Encryption — .pdf files on we9041srv
9. Ransom Redirection — Payment portal domain identified

##  Key Findings
- Single USB device caused full network compromise
- Cerber disguised cryptor as innocent .jpg image
- Attack reached shared file server within minutes
- All 9 Kill Chain stages successfully reconstructed

##  Defence Recommendations
- USB device control via Group Policy
- Disable macros in Microsoft Office
- Network segmentation & least privilege
- DNS filtering with threat intelligence
- Regular offline backups (3-2-1 rule)
- EDR deployment on all endpoints

##  Files
-  Full Analysis Report (DOCX)
-  Presentation Slides (PPTX)

##  Certification
Blue Team Junior Analyst (BTJA) — Security Blue Team — Jan 2026
Cybersecurity Bootcamp — Ironhack — Mar 2026
