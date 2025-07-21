# TryHackMe-Progress
My daily TryHackMe room progress, notes and findings. 

## ^1st ROOM -Offensing security Intro- [21 jun 2025] 
_STATUS_: COMPLETED

### COMMANDS / CONCEPTS LEARNED**
- Offensive Security (ethical hacking for the analyzation of weak points and resolution) [RED TEAM]
- What is VM (Virtual Machine)
- ```
  dirb https://target.com
 (for research hidden pages (URL) in the directory with brute-force)
>*Notes*: I didn't know what the cyber security was, but this guide open a world for me. Im very interessed.

## ^2nd ROOM-Defensive Security Intro- [21 jun 2025]
_STATUS_: COMPLETED

### COMMANDS / CONCEPTS LEARNED**
- Defensive Security (Preventing and Detecting intrusion, when they occur and responding properly) [BLUE TEAM]
  
- [**SOC**] (Security Operation Center)
  Team of cybersecurity professionals that monitors the network and its systems to detect harmful cybersecurity events. *Vulnerabilities*, *Policy Violations*, *Unauthorized Activity*, *Network Intrusion* are the main point where a SOC Analyst give more attention.
- **Threat Intelligence**
  Gathers information to help the company better prepare against potential adversaries. Every Target (Company) have different Threat (Banks, Telecomunications, Archives, etc.). Intelligence needs data. Data has to be collected, processed, and analyzed. Data is            collected  from local sources such as network logs and public sources such as forums. 

- [**DFIR**] (Digital Forensics and Incident Response)
  Investigate crimes and establish facts. The focus of digital forensics shifts to analyzing evidence of an attack and its perpetrators and other areas such as intellectual property theft, cyber espionage, and possession of unauthorized content. This focused on different areas:
+ **_File System_**: Analyzing a digital forensics image (low-level copy) of a system’s storage reveals much information, such as installed programs, created files, partially overwritten files, and deleted files.
+ **_System memory_**: If the attacker runs their malicious program in memory without saving it to the disk, taking a forensic image (low-level copy) of the system memory is the best way to analyze its contents and learn about the attack.
+ **_System logs_**: Each client and server computer maintains different log files about what is happening. Log files provide plenty of information about what happened on a system. Even if the attacker tries to clear their traces, some traces will remain.
+ **_Network logs_**: Logs of the network packets that have traversed a network would help answer more questions about whether an attack is occurring and what it entails.
  
>*Notes*: [Low-level copy] is the copy of the hidden files in the sistem whitout damage the original, useful when a machine or system is damaged. While the [High-level copy] is the copy of the visible superficials files in the sistem.

The four major phases of the incident response process are:

- **_Preparation_**
- **_Detection and Analysis_**
- **_Containment, Eradication, and Recovery_**
- **_Post-Incident Activity_**: After a successful recovery, a report is produced, and the lesson learned is shared to prevent similar future incidents.

- [**Malware Analysis**]
  Malware stands for 'malicious software'. _Software_ refers to programs, documents, and files you can **save on a disk or send over the network**. Malware includes many types, such as:
  
- A _virus_ is a piece of code (part of a program) that attaches itself to a program. It is designed to spread from one computer to another and works by altering, overwriting, and deleting files once it infects a computer. The result ranges from the computer becoming   slow to unusable.
- _Trojan Horse_ is a program that shows one desirable function but hides a malicious function underneath. For example, a victim might download a video player from a shady website that gives the attacker complete control over their system.
- _Ransomware_ is a malicious program that encrypts the user’s files. Encryption makes the files unreadable without knowing the encryption password. The attacker offers the user the encryption password if the user is willing to pay a “ransom.”

