# Cybersecurity Journey – My TryHackMe Progress
My daily TryHackMe room progress, notes and findings. 

## 1.ROOM - Offensing Security Intro - [21 july 2025] 
_STATUS_: COMPLETED

### CONCEPTS LEARNED
- Offensive Security (ethical hacking for the analyzation of weak points and resolution) [RED TEAM]
- What is VM (Virtual Machine, software that emulates a physical computer within a host computer.)

### COMMANDS
- ```
  dirb https://target.com
 (List hidden directories (URL) by brute-forcing common paths using a predefined wordlist.)
 
>*Notes:* I didn't know what the cyber security was, but this guide open a world for me. Im very interested.


------------------------------------------------------------------------------------------------------------------

## 2.ROOM - Defensive Security Intro - [21 july 2025]
_STATUS_: COMPLETED

### CONCEPTS LEARNED
- Defensive Security (Preventing and Detecting intrusion, when they occur and responding properly) [BLUE TEAM]
  
  #### [SOC] (Security Operation Center)
  Team of cybersecurity professionals that monitors the network and its systems to detect harmful cybersecurity events. *Vulnerabilities*, *Policy Violations*, *Unauthorized Activity*, *Network Intrusion* are the main point where a SOC Analyst give more attention.
- **Threat Intelligence**
  Gathers information to help the company better prepare against potential adversaries. Every Target (Company) have different Threat (Banks, Telecomunications, Archives, etc.). Intelligence needs data. Data has to be collected, processed, and analyzed. Data is            collected  from local sources such as network logs and public sources such as forums. 

  #### [DFIR] (Digital Forensics and Incident Response)
  Investigate crimes and establish facts. The analysis evidence of an attack and its perpetrators and other areas such as intellectual property theft, cyber espionage, and possession of unauthorized content. This focused on different areas:
  
**_File System_**

**_System memory_**

**_System logs_**

**_Network logs_**
  
>*Notes*: [Low-level copy] is the copy of the hidden files in the sistem whitout damage the original, useful when a machine or system is damaged. While the [High-level copy] is the copy of the visible files in the system.

The four major phases of the incident response process are:

1. **_Preparation_**
2. **_Detection and Analysis_**
3. **_Containment, Eradication, and Recovery_**
4. **_Post-Incident Activity_**

- #### Malware Analysis
  Malware stands for 'malicious software'. _Software_ refers to programs, documents, and files you can **save on a disk or send over the network**. Malware includes many types, such as:
  
. A _virus_ is a piece of code (part of a program) that attaches itself to a program. It is designed to spread from one computer to another and works by altering, overwriting, and deleting files once it infects a computer. The result ranges from the computer becoming     slow to unusable.

. _Trojan Horse_ is a program that shows one desirable function but hides a malicious function underneath. For example, a victim might download a video player from a shady website that gives the attacker complete control over their system.

. _Ransomware_ is a malicious program that encrypts the user’s files. Encryption makes the files unreadable without knowing the encryption password. The attacker offers the user the encryption password if the user is willing to pay a “ransom.”

