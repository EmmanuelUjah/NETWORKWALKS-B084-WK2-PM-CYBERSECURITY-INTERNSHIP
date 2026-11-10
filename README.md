# NETWORKWALKS-B084-WK2-PM-CYBERSECURITY-INTERNSHIP
Week two task
#  Author
Emmanuel Ujah

Cybersecurity Intern B084

ID: NW-084-000

LinkedIn : https://www.linkedin.com/in/emmanuel-ujah-597701203/

 # 🔐FOOTPRINTING & RECONNAISSANCE ATTACKS WITH MULTIPLE KALI TOOLS, AND NETWORK SCANNING WITH ZENMAP

# 📌 Project Overview:
In this lab I will footprint the live website of networkwalks.com using six built-in Kali Linux tools: **whois, whatweb, nslookup, curl, wafw00f and dnsrecon**. Each tool reveals a different piece of the target, and together they build a full profile of it. The information you gather here is the foundation for everything that follows. In the next projects/tasks you will use these same findings to plan your scanning and your attacks, because you cannot attack what you have not first understood. Record every output carefully, as you will need it for your final report.

Network Scanning with Zenmap (the graphical version of Nmap) is used to identify active devices, open ports, running services, operating systems, and potential vulnerabilities within a network.

Overall Purpose: To map the target environment, identify attack surfaces, assess security risks, and support vulnerability assessments, penetration testing, and security monitoring. These techniques help organizations find and fix weaknesses before attackers can exploit them.
# 🎯 Objectives:
The main objectives of this project are to:

1.Run whoisto find the domain registration details.
2.Run whatwebto fingerprint the web technologies.
3.Run nslookupto resolve the domain to its IP address.
4.Run curl -I to read the HTTP response headers.
5.Run wafw00f to detect a Web Application Firewall.
6.Run dnsreconto enumerate all DNS records.
7.Download & install Zenmap from official website on my Windows PC
8.Find the local IP address & LAN subnet
9.Find the list of live hosts/PC’s in IP subnet
10.How many hosts are live in the subnet?
11.What are the IP addresses of the live hosts
12.What are the MAC addresses of the live hosts?

# Purpose of the Lab
This lab is designed to help me understand and practice the information-gathering and network-discovery techniques used in cybersecurity to identify assets, assess risks, and strengthen an organization's security posture.

# Problems Encountered & Solutions
1. After manually configuring the IPv4 settings, Internet connectivity still failed along the line.
Solution: I used the following command on the kali CLI 
"sudo nmcli connection modify "Wired connection 1" ipv4.dad-timeout 0"
2. I was having problems understanding the 6 kali Linux tools  and how it works.
   Solution: I was able to follow a tutorial video @ https://www.youtube.com/watch?v=YB2qykxmCVg and https://www.youtube.com/watch?v=2WbOpiJ6yt8 this gave me an overview of each tool, how it is used and what it stands for. and also helped me understand how zenmap is used for scaning network.


# Knowledge and Skills Gained
1. Information Gathering (Footprinting)
2. Reconnaissance Techniques
3. DNS Enumeration Querying DNS records using tools such as nslookup and dnsrecon.
4. Using tools such as Whois, theHarvester, and WhatWeb for Collecting information from public sources Identifying technologies and exposed information.
5. Network Discovery
6. Port Scanning and Service Enumeration
7. Vulnerability Identification
8. Zenmap/Nmap Proficiency
9. Cyber Threat Awareness
10. Penetration Testing Fundamentals
11. Seeking authorization before performing a penetration test.

# Tools Used 
Kali Linux 
1. whois
2. whatweb
3. nslookup
4. curl -I
5. wafw00f
6. dnsrecon
7. The Havester
8. Zen-map
