sudo nmap 192.168.43.75 -sV
[sudo] password for kali: 
Starting Nmap 7.99 ( https://nmap.org ) at 2026-06-19 12:33 -0400
Nmap scan report for 192.168.43.75
Host is up (0.0028s latency).
Not shown: 977 closed tcp ports (reset)
PORT     STATE SERVICE       VERSION
21/tcp   open  ftp           vsftpd 2.3.4
22/tcp   open  ssh           OpenSSH 4.7p1 Debian 8ubuntu1 (protocol 2.0)
23/tcp   open  telnet        Linux telnetd
25/tcp   open  smtp          Postfix smtpd
53/tcp   open  domain?
80/tcp   open  http?
111/tcp  open  rpcbind?
139/tcp  open  netbios-ssn?
445/tcp  open  microsoft-ds?
512/tcp  open  exec?
513/tcp  open  login?
514/tcp  open  shell?
1099/tcp open  rmiregistry?
1524/tcp open  bindshell     Metasploitable root shell
2049/tcp open  nfs?
2121/tcp open  ftp           ProFTPD 1.3.1
3306/tcp open  mysql         MySQL 5.0.51a-3ubuntu5
5432/tcp open  postgresql?
5900/tcp open  vnc           VNC (protocol 3.3)
6000/tcp open  X11?
6667/tcp open  irc           UnrealIRCd
8009/tcp open  ajp13?
8180/tcp open  unknown
1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at https://nmap.org/cgi-bin/submit.cgi?new-service :
SF-Port514-TCP:V=7.99%I=7%D=6/19%Time=6A356F44%P=x86_64-pc-linux-gnu%r(NUL
SF:L,2B,"\x01Couldn't\x20get\x20address\x20for\x20your\x20host\x20\(kali\)
SF:\n")%r(RTSPRequest,2B,"\x01Couldn't\x20get\x20address\x20for\x20your\x2
SF:0host\x20\(kali\)\n");
MAC Address: 00:0C:29:C8:CE:6F (VMware)
Service Info: Hosts:  metasploitable.localdomain, irc.Metasploitable.LAN; OSs: Unix, Linux; CPE: cpe:/o:linux:linux_kernel

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 39.04 seconds
