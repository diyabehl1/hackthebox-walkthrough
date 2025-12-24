# <div align="center">[Meow](https://app.hackthebox.com/machines/Meow?tab=play_machine) Walkthrough By -Diya  </div>
<div align="center"><img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/1d3fc0d6-13af-4d74-a65d-782822e3b282" /></div>

### First Step is connect to vpn

##### TASK 1
#### What does the acronym VM stand for?
#### ```  VIRTUAL MACHINE ```


##### TASK 2
#### What tool do we use to interact with the operating system in order to issue commands via the command line, such as the one to start our VPN connection? It's also known as a console or shell.
#### ```  TERMINAL ```

##### TASK 3
#### What service do we use to form our VPN connection into HTB labs?
#### ```  openvpn ```

##### TASK 4
#### What tool do we use to test our connection to the target with an ICMP echo request?
#### ```  ping  ```

##### TASK 5
#### What is the name of the most common tool for finding open ports on a target?
#### ```  nmap ```

##### TASK 6
#### What service do we identify on port 23/tcp during our scans?
#### ```  Here we will start Enumerating
```
┌──(kali㉿kali)-[~]
└─$ nmap -sV -sC 10.129.36.234                             
Starting Nmap 7.95 ( https://nmap.org ) at 2025-12-24 12:17 IST
Nmap scan report for 10.129.36.234
Host is up (0.50s latency).
Not shown: 999 closed tcp ports (reset)
PORT   STATE SERVICE VERSION
23/tcp open  telnet  Linux telnetd
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 26.93 seconds


```
