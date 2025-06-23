<# Task1-Nmap
This is my Nmap work
<br>
Official website : - https://nmap.org/download#windows
<br>
Stable version:-  nmap-7.97-setup.exe
<br>
Run .exe file
<br>
![Alt text][installation](https://github.com/user-attachments/assets/ba07088c-f6ab-4294-a74a-6587c3a84460)
<br>
 nmap -sS 192.168.1.0/24
<br>
 sS Stand for SYN Scan
<br>
Nmap done: 256 IP addresses (43 hosts up) scanned in 115.86 seconds
<br>
![nmap -sS](https://github.com/user-attachments/assets/c5f4e608-be1b-4e76-a1e9-de7dacfe0a02)
<br>
Common Services
<br>
telnet
<br>
http
<br>
https
<br>
rtsp
<br>
http-alt
<br>
pop3pw
<br>
resvc
<br>
ansyslmd
<br>
pn-requester
<br>
iss-realsec
<br>
iscsi
<br>
vrml-multi-use
<br>
afs3-bos
<br>
doceri-ctl
<br>
trivnet1
<br>
ff-sm
<br>
klogin
<br>
<br>
Risk with open port
<br>
http:-  Web vulnerabilities 
<br>
http-alt :- Exposed admin panels
<br>
https :- misconfigured SSL/TLS settings, expired or self-signed certificates
<br>
rtsp:- unencrypted video streams and credentials
<br>
telnet :- transmits all data, including passwords, in plaintext
