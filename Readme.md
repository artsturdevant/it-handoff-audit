**IT Evaluation Framework**
=============================
***For both IT professionals entering new roles, and those saints among us that provide good documentation on their way out.***

*Developed By: Art Sturdevant*

##General IT:##
Is there a strategic IT plan in place?

 - Does it include a short-term plan 1-5 years?
 - Does it include a long-term plan 5+ years?
 - When was it created?
 - When was it last updated?
 - Does it list each company individually?

How are changes to the IT landscape handled?
Is there a scheduled downtime window?

How are incidents handled? (Viruses, security breaches, employee termination, etc)

- Is there a formal process? 
- Is there a documented procedure in place for events like network outages, server outages, etc?

What is the annual budget (or previous 12 months expenditures in IT)

- What percent is spent on:
- New Hardware
- New Software (Office 2013, Antivirus, etc)
- Software licenses (MSSQL, Virus Subscription)
- Software Updates (LIMS, etc)
- Outsourced IT
- Hardware maintenance, replacement parts, upgrades

How long does it take to get a computer on a user’s desk from request to login?

- How does a user initiate this process?

Do/Can Employees bring their own equipment?

- Phones or Tablets?
- Personal Computers?

Are there any formal requirements for people that choose to use their own devices?

- Hard drive encryption?
- Geolocation service for lost or stolen devices (Prey for example)
- Remote wiping for phones and tablets
- How many traveling devices are there
How do users communicate issues or request service?
- Is there a formal ticketing system in place to document work orders?
- What is the average time to resolve a work order?

How are long term projects tracked?

Is there a code repository in place for scripts, applications, and websites?

Is there a list of approved computers and printers users may order?

What is used for inventory management? What happens when an asset is lost or stolen?

Please list third-parties that interact with our IT systems:

- Clients (in a general sense)
- Outsourced IT
- Business Partners

##Servers##
How many servers are in use?

Physical Hardware & age of machines

Virtual Software & version of host operating system

How do we manage DNS?

What operating systems are installed on the servers?     

Who installed the servers?

Do any servers require redundant power?

How many servers are over 3 years old?

What is the replacement policy for server and network hardware?

How long would it take to rebuild mission critical systems in the case of a fire or natural disaster?

When was the last time the backup dataset was tested?

Is there any alerting if a backup fails?

Does each server have a disaster recovery plan?

What are the most mission critical servers?
(list here)

What is the password policy for servers?
     - Where are the passwords to critical systems stored?
     - Is there a procedure in place to make sure that passwords are kept up-to-date?
     - Is Active Directory in place?
     - Is the Administrator/root password different on client than it is on servers?

Who is hosting Website/Designing Websites?
- What is the monthly costs
- Can I review the terms and agreement?
- Is there any analytics data available for website usage?

##Backup:##
What software is in use for backups?

Is the software up to date?

Is the 3-2-1 rule in place and followed?

Who is responsible for the backup sets?

How do servers or files make it into the backup set?

How quickly are your backup sets growing?

How much storage is available for backups onsite?

How much storage is available for backups offsite?

Are backups being performed regularly?

When were the backups last tested?

Are the backups encrypted in any way?

Who has the key?

What happens if they get hit by a bus at the exact time you need to restore from a backup?

##Infrastructure:##
How many clients/ client computers are managed?

Who is our ISP?

- Do we have redundant connections?
- Do we have a static IP address or multiple addresses?
- Do they provide any kind of uptime agreement?
- How often does the internet go out/down?
- Last time the internet was out, how long before it was restored?
- Was there any explanation of the problem?

How are systems monitored for issues?

- Is there any sort of monitoring system in place for servers, computers, or printers?
- If a system goes down at 3am, who is responsible for fixing it?

Is there a VPN for employees to use to work remotely?

- What software is in use?
- How often is it utilized?
- What protocol is in place (PPTP, IPSEC, etc)
- What is the security measure? (Passwords, Shared Secret, Certificates, etc)

How is security handled on the network?

- Do internal sites require https?
- How is the wireless secured (WEP, WPA, WPA2, etc)
- Is the public wifi separated from the internal wireless?
- Does everyone use the same wireless password or is it tied to their network account?
- Are the different companies on separate network segments?
- Are there any VLANs in place?

What is the internal wired network speed?

What is the internal wireless speed? What versions of 802.11 are available?
(a, b, g, n)

Who manages the licenses for:

- Windows Servers
- VMware
- Antivirus Subscriptions
- Windows Desktop Subscriptions
- MSSQL
- Office
- Windows Server CALs
	- Other: (list)

Is there an accurate inventory of software in use?

Is group policy in use? If so, what is it managing?

Is there any sort of configuration management in place for managing OS installation, updates, or software installations?

What services can users access from outside the internal network (from home for example)? - Email, Internal websites, their desktop?

Is there software in place for desktop sharing?

- What is the software?
- What protocol is in use?

What is the firewall installed on the network?

- Does it get updates? If so, when was the last update?
- Is it vendor supported or internally managed?

Is there a separate network segment or secured environment for testing infrastructure changes?
