# Microsoft-CyberSecurity-Engage-2022
Here I have made four scripts which i have learnt from the webinar conducted in Cybersecurity engage program.

## Ddos
This Script demonstrate the basic of Distributed Denial of Service attack on the server which is the target.This type of attack takes advantage of the specific capacity limits that apply to any network resources – such as the infrastructure that enables a company’s website. The DDoS attack will send multiple requests to the attacked web resource – with the aim of exceeding the website’s capacity to handle multiple requests… and prevent the website from functioning correctly. Here is a brief explanations as to how ddos is carried out-
~~~
DDoS attacks are carried out with networks of Internet-connected machines.

These networks consist of computers and other devices (such as IoT devices)which have been infected with malware,
allowing them to be controlled remotely by an attacker. These individual devices are referred to as bots (or zombies), 
and a group of bots is called a botnet.

Once a botnet has been established,
the attacker is able to direct an attack by sending remote instructions to each bot.

When a victim’s server or network is targeted by the botnet,
each bot sends requests to the target’s IP address, potentially causing the server or network to become overwhelmed,
resulting in a denial-of-service to normal traffic.

Because each bot is a legitimate Internet device, separating the attack traffic from normal traffic can be difficult.

~~~
## Hunterr
Reconnaissance or Information Gathering is the initial step or the starting step of the Ethical Hacking or Penetration Testing process. Knowing about the target is very important while performing penetration testing. The information about the target collected serves as the milestone while penetrating the target.
The Hunterr tool gather the following information-
~~~ 
1. Subdomain Enumeration
2. DNS Scanning"
3. robots.txt checker
4. Nameserver Scanning
5. whoislookup scan
6. Directory Enumeration
~~~
## Ransomware
Ransomware is a type of malware that encrypts a victim’s data until a payment is made to the attacker. If the payment is made, the victim receives a decryption key to restore access to their files. If the ransom payment is not made, the threat actor publishes the data on data leak sites (DLS) or blocks access to the files in perpetuity.
~~~
Step 1. Infection: Ransomware operators often using phishing emails and social engineering techniques to infect their victim’s computer. In most cases, the victim ends up clicking a malicious link in the email, introducing the ransomware variant on their device.
Step 2. Encryption: After a device or system has been infected, ransomware then searches for and encrypts valuable files. Depending on the variant, the malicious software may find opportunities to spread to other devices and systems across the organization.
Step 3. Ransom Demand: Once the data has been encrypted, a decryption key is required to unlock the files. In order to get the decryption key, the victim must follow the instructions left on a ransom note that outline how to pay the attacker – usually in Bitcoin.
~~~
## Reconn
I have made an automate recon tool that is made using bash script. Here I have used 3 tools Which help me to gather the following information
~~~
1. Nmap - ports ,protocols on that port, state of port, services provided by it.
2. Gobuster - to scan all the possible directories present in the web-site.
3. WhatWeb - To gather the information regarding the web server.
~~~
