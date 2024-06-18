# Basic Web Pentesting
- I managed to complete the room in Try Hack Me platform i.e., Basic Web Pentesting. Click here to access it [tryhackme.com](https://tryhackme.com/r/room/basicpentestingjt)
- In this room I learnt the concepts like Service Enumeration, Linux Enumeration, Brute Forcing and Hash Cracking.
  
## Service Enumeration
- In Service Enumeration, I need to find the services and versions in the given machine.
- I used nmap to scan the machine and managed to find few open ports.
  ```bash
  nmap -sV -vv <ip_address>
  ```
- After scanning we got the following result:
  1. Port no: 22/tcp    State: Open    Service: ssh    Version: OpenSSH 7.2P2
  2. Port no: 80/tcp    State: Open    Service: http    Version: Apache httpd 2.4.18
  3. Port no: 139/tcp   State: Open    Service: netbios-ssn    Version: Samba smbd 3.X -4.X
  4. Port no: 445/tcp   State: Open    Service: netbios-ssn    Version: Samba smbd 3.X - 4.X
  5. Port no: 8009/tcp  State: Open    Service: ajp13    Version: Apache Jserv (Protocol v1.3)
  6. Port no: 8080/tcp  State: Open    Service: http     Version: Apache Tomcat 9.0.7


  ### Linux Enumeration
  - In linux enumeration, I found the hidden directory and username for the given machine
  - To find the hidden directory i used the tool namely gobuster which is already discussed in Day-02
  - To find the username i used enum4linux
 
  ### Brute Forcing
  - After successfully identifying the username I used hydra to brute force the username and successfully found the password.
  - 
