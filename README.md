A series of offensive security projects I undertook to better understand penetration testing and red-teaming tactics.
These projects include:
1) OSINT gathering. Tools used: WhoIS, NSLookup, DIG, MXToolbox, Recon-ng, The Harvester, Maltego, Shodan, Spiderfoot.
2) Active Information Gathering targeting Windows 7 and Metasploitable 2 systems. Tools used: NMAP, Netcat, OpenVAS, Bash scripting.
3) Static Code Analysis. Tools used: Bandit, Pylint, Pyflakes, Wapiti.
4) Network Binary Exploitation and System exploitation targeting Windows 7 and Metasploitable 2 systems. The objective was to gain unauthorized access to these systems, or deny service to users.
   Exploits conducted:
     Metasploitable 2: Exploit through FTP (Open Port 21), and also through a brute force password attack to gain entry.
     Windows 7: Established Reverse TCP connection, and also conducted a DoS attack on Windows 7.
     NOTE: these exploits were conducted on virtual environments using VMWare.
6) Post-Exploitation Techniques: After gaining unauthorized access, how do attackers maintain a presence in systems? This exploration also covers Windows 7 and Metasploitable 2?
     Techniques and attacks covered:
     On Metasploitable 2: SSH Key persistence (gaining access to confidential private key to bypass passwords), System enumeration (enum_system), to gather system information and intelligence.
     On Windows 7: Screen capturing/Spyware using VNC (Virtual Network Computing), Keystroke monitoring to scan and gather keystrokes.
   This exploration also covers gathering access to hash values using the Linux hashdump module, and cracking hashes with John the Ripper.
7) Cloud Security: AWS Cloud Security challenges: flaws.cloud, flaws2.cloud. This was done as part of a CTF-exercise
