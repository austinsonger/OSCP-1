# OSCP
OSCP Preperation Guide and References.

## Goal:
* List of resources, tools, and tactics in order to prepare for the OSCP exam.
* Always accepting more links/stuff. Feel free to make a pull request. 


__*I am just beggining to prepare for the OSCP exam, so I plan for this repository to grow over time and I will contribute reguraly*__ 

## OSCP Topics
*Main topics to help guide to developing a study plan*
|**Topics**|
|:---------|
|Passive Info Gathering||
|Active Info Gathering||
|Vuln Scanning||
|Web Application Attacks||
|Buffer Overflows Overview||
|Windows Buffer Overflows||
|Linux Buffer Overflows||
|Client-Side Attacks||
|Locating Public Exploits||
|Fixing Exploits||
|File Transfers||
|Anti-Virus Evasion||
|Privilege Escalation||
|Password Attacks||
|Port Redirection and Tunneling||
|AD-Attacks||
|Metaploit||
|Powershell||


## OSCP Overview
### Information:
The exam consists of several target machines that must be compromised. Some of the machines will require multiple exploitation steps, resulting first in low-level local access, and then in root or administrative privilege escalation. Other machines will be fully exploitable remotely. Specific instructions for each target will be located in your Exam Control Panel, which will only become available to you once your exam begins.

### Exam Restrictions:
You cannot use any of the following:
* Spoofing (IP, ARP, DNS, NBNS, etc)
* Commercial tools or services (Metasploit Pro, Burp Pro, etc.)
* Automatic exploitation tools (e.g. db_autopwn, browser_autopwn, SQLmap, SQLninja etc.)
* Mass vulnerability scanners (e.g. Nessus, NeXpose, OpenVAS, Canvas, Core Impact, SAINT, etc.)
* Features in other tools that utilize either forbidden or restricted exam limitations
* Any tools that provide similar functions as those listed above
* **You are ultimately responsible for knowing what features or external utilities any chosen tool is using. The primary objective of the OSCP exam is to evaluate your skills in identifying and exploiting vulnerabilities, not in automating the process.**
* **You may however, use tools such as nmap (and scripting engine), Nikto, BurpFree, DirBuster, etc.** 

### Metasploit Restrictions:
The usage of Metasploit and the Meterpreter payload are restricted during the exam. You may only use Metasploit modules ( Auxiliary, Exploit, and Post ) or the Meterpreter payload against one single target machine of your choice.

However, you may use the following against all of the target machines:
* multi handler (aka exploit/multi/handler)
* msfvenom
* pattern_create.rb
* pattern_offset.rb

## Resources
```bash
#Official Documentation
https://help.offensive-security.com/hc/en-us/articles/360040165632
https://www.offensive-security.com/documentation/penetration-testing-with-kali.pdf
```
