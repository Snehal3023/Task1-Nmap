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
Common Services with IP Address
<br>
telnet 192.168.1.1  23
<br>
http 192.168.1.11  80
<br>
https 192.168.1.3  443
<br>
rtsp 192.168.1.64   554
<br>
http-alt 192.168.1.64
<br>
pop3pw 192.168.1.12   106
<br>
resvc 192.168.1.12   691
<br>
ansyslmd 192.168.1.12   1055
<br>
pn-requester 192.168.1.12  2717
<br>
iss-realsec 192.168.1.12  2998
<br>
iscsi  192.168.1.12 3260
<br>
vrml-multi-use 192.168.1.12 4279
<br>
afs3-bos 192.168.1.12 7007
<br>
doceri-ctl  192.168.1.12  7019
<br>
trivnet1  192.168.1.12 8200
<br>
ff-sm  192.168.1.15  1091
<br>
klogin  192.168.1.17  547
<br>
unknown  192.168.1.12   19801


Risk with open port
http:-  Web vulnerabilities 
<br>
http-alt :- Exposed admin panels
<br>
https :- misconfigured SSL/TLS settings, expired or self-signed certificates
<br>
rtsp:- unencrypted video streams and credentials
<br>
telnet :- transmits all data, including passwords, in plaintext
