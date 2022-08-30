# dump-of-tools

<br><br>

## I will keep updating this list as time progresses feel free to contribute it will help me and you :) 

<br><br>

## Following tools are primarly used for penetration testing purpose

<br><br>

### Anonymity tools
Name | Description
---- | ----
[Tor](https://www.torproject.org/download/) | The-Onion-Routing client
[proxychains](https://github.com/haad/proxychains) | proxychains is tool to establish a chain of proxies

<br><br>

### Bruteforcing tools
Name | Description
---- | ----
[Hydra](https://github.com/vanhauser-thc/thc-hydra) | Hydra is powerfull credential bruteforcing tool
[medusa](https://github.com/jmk-foofus/medusa) | Medusa is credential bruteforcing tool

<br><br>

### Clearing tracks
Name | Description
---- | ----
[Shred](https://en.wikipedia.org/wiki/Shred_(Unix)) | Shred is tool to completely wipe data from storage device to avoid leaving tracks

<br><br>

### Cryptography and Steganography tools
Name | Description
---- | ----
[JohTheRipper](https://www.openwall.com/john/) | An Open source Password Cracking tool
[HashCat](https://hashcat.net/hashcat/) | hashcat is password cracking tool which works on GPU instead of CPU
[Hash-Identifier](https://github.com/blackploit/hash-identifier) | hash-identifier is a CLI to identify type of hash algorithm
[unshadow](https://www.cyberciti.biz/faq/unix-linux-password-cracking-john-the-ripper/) | combine passwd+shadow to bruteforce them
[steghide](http://steghide.sourceforge.net/) | powerfull steganography tool
[stegseek](https://github.com/RickdeJager/stegseek) | insanely fast steghide password cracking 
[base64](https://www.base64decode.org/) | it is CLI and online tool to encode/decode base64
[fcrackzip](https://www.kali.org/tools/fcrackzip/) | crack password protected zip files

<br><br>

### Enumeration - Network and Host Scanning 
Name | Description
---- | ----
[NMAP](https://nmap.org/download) | NMAP The OG tool for scanning network and host
[masscan](https://github.com/robertdavidgraham/masscan) | masscan is port scanning tool which includes a command to search whole internet
[httprobe](https://github.com/tomnomnom/httprobe) | check whether host is alive or down 
[Nessus](https://www.tenable.com/products/nessus) | Nessus is powerall network scanning tool
[netdiscover](https://github.com/netdiscover-scanner/netdiscover) | An active/passive arp enumeration tool

<br><br>

### Enumeration - Sub directory listing
Name | Description
---- | ----
[dirbuster](https://sourceforge.net/projects/dirbuster/files/DirBuster%20Source/1.0-RC1/) | A java application to brute force subdirectories
[dirb](https://www.kali.org/tools/dirb/) | sub directory finder which uses OSINT to find sub directories
[ffuf](https://github.com/ffuf/ffuf) | A fast web fuzzer written in golang
[gobuster](https://github.com/OJ/gobuster) | sub directory - web fuzzer written in go

<br><br>

### Enumeration - NFS
Name | Description
---- | ----
[showmount](https://resources.infosecinstitute.com/topic/exploiting-nfs-share/) | showmount is utility which can be used to list available shares on nfs
[mount](https://resources.infosecinstitute.com/topic/exploiting-nfs-share/) | mount is a inbuilt utility which can be used to mount nfs
[NFSpy](https://github.com/bonsaiviking/NfSpy) | NfSpy is a Python library for automating the falsification of NFS credentials when mounting an NFS share

<br><br>

### Enumeration - Website Fingerprinting tools
Name | Description
---- | ----
[Wappalyzer](https://www.wappalyzer.com/) | wappalyzer awsome tool and can be added as extension to quickly fingerprint website 
[Built With](https://builtwith.com/) | Gives Detailed fingerprint of website
[WhatWeb](https://github.com/urbanadventurer/WhatWeb) | CLI tool for fingerprinting websites 

<br><br>

### Enumeration - DNS records and Domain Enumeration
Name | Description
---- | ----
[whois](https://www.whois.com/) | comes in kali linux by default. usefull for performing whois lookup on domain
[nslookup](https://www.nslookup.io/) | DNS record lookup tool. Comes with kali linux.
[dnsrecon](https://github.com/darkoperator/dnsrecon) | DNS enumeration script written in python. Comes with kali linux

<br><br>

### Enumeration - Subdomains 
Name | Description 
---- | ----
[sublister](https://github.com/aboul3la/Sublist3r) | Sublist3r is a python tool designed to enumerate subdomains of websites using OSINT.
[Bluto](https://github.com/samyoyo/Bluto) | Bluto is DNS recon tool and subdomain finder

<br><br>

### Enumeration - Certificates, IOT, Servers Search Engines
Name | Description
---- | ----
[shodan](https://www.shodan.io/) | An extremely powerfull IOT searchengine
[crt.sh](https://crt.sh/) | certificate search engine for domains
[censys](https://search.censys.io/) | Censys helps organizations, individuals, and researchers find and monitor every server on the Internet

<br><br>

### Enumeration - Samba
Name | Description
---- | ----
[smbmap](https://github.com/ShawnDEvans/smbmap) | Handy tool for enumerating samba service

<br><br>

### OSINT - Overall OSINT gathering
Name | Description
---- | ----
[theHarvester](https://github.com/laramies/theHarvester) | The tool gathers names, emails, IPs, subdomains, and URLs 
[OWASP Amass](https://github.com/OWASP/Amass) | OSINT network attack surface mapping
[Sherlock](https://github.com/sherlock-project/sherlock) | Hunt down social media with sherlock

<br><br>

### OSINT - Data Breaches
Name | Description 
---- | ----
[HaveIBeenPwned](https://haveibeenpwned.com/) | check for credential for data breaches
[Breach-parse](https://github.com/hmaverickadams/breach-parse) | A tool for locally checking for breached data

<br><br>

### OSINT - EMail gathering
Name | Descritpion
---- | ----
[hunter.io](https://hunter.io/) | A professional email finder tool

<br><br>


### Overall Web Penetration testing
Name | Description
---- | ----
[Burpsuite](https://portswigger.net/burp/communitydownload) | An Overwall web penetration testing tool
[OWASP Zap](https://owasp.org/www-project-zap/) | Free Proxy tool to penetrate web applications

<br><br>

### Overall Allrounder tool
Name | Description
---- | ----
[MetaSploit](https://www.metasploit.com/) | A advanced penetration testing framework
[NSE](https://nmap.org/book/man-nse.html) | NSE is extremely powerfull scripting engine for nmap capable of more than scanning

<br><br>

### Payload generator tool
Name | Description
---- | ----
[MSFVenom](https://github.com/rapid7/metasploit-framework/wiki/How-to-use-msfvenom) | A standalone metasploit payload generator

<br><br>

### Privilege Escallation and OS exploit and Enumeration tools
Name | Description
---- | ----
[PEASS-ng](https://github.com/carlospolop/PEASS-ng) | PEASS-ng is an advance priv-escalation tool for Win,Mac,Linux
[LinEnum.sh](https://github.com/rebootuser/LinEnum/blob/master/LinEnum.sh) | Linux Enumeration tool
[linuxprivchecker.py](https://github.com/sleventyeleven/linuxprivchecker/blob/master/linuxprivchecker.py) | linux privilege checker python script
[sherlock](https://github.com/rasta-mouse/Sherlock) | power shell script to check privlege escalation in windows
[Windows-Exploit-Suggester](https://github.com/AonCyberLabs/Windows-Exploit-Suggester) | find exploits in windows
[pspy](https://github.com/DominicBreuker/pspy) | Monitor linux processes without root permissions 

<br><br>

### Reverse Shell \ Bind Shell
Name | Description
---- | ----
[PentestMonkey](https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet) | reverse shell cheatsheet from pentest monkey
[PHP revershell](https://github.com/pentestmonkey/php-reverse-shell) | PHP reverseshell script from pentest monkey
[netcat](https://sourceforge.net/projects/nc110/) | in pentesting used to open and listen to port to spawn shell 

<br><br>


### Services - transfer files (malwares), clients softwares of services
Name | Description
---- | ----
[SMBClient](https://www.samba.org/samba/docs/current/man-html/smbclient.1.html) | SmbClient is client tool for SMB service
[FTP](https://www.computerhope.com/issues/ch001246.htm) | FTP is CLI tool for ftp client
[http.server](https://docs.python.org/3/library/http.server.html) | python3 module to host web server to allow transport of file
[certutil](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/certutil) | Windows tool equivalent to wget
[OpenSSH](https://www.openssh.com/) | OpenSSH is SSH created by OpenBSD team
[OpenVPN](https://openvpn.net/) | Free GNU licensed VPN 
[OpenSSL](https://www.openssl.org/) | Free SSL/TLS toolkit
[SCP](https://www.ssh.com/academy/ssh/scp) | Transfer files securly via ssh
[curl](https://curl.se/download.html) | curl is used to download data from url
[wget](https://www.gnu.org/software/wget/?) | wget is tool to download files from internet


<br><br>

### Vulnerability scanning tools
Name | Description
---- | ----
[Nkto](https://www.cirt.net/Nikto2) | Nikto is powerfull web vulnerability scanning tool
[Vulscan NSE](https://github.com/scipag/vulscan) | Vulscan is powerfull NSE script for vulnerability scanning
[searchsploit](https://github.com/offensive-security/exploitdb) | searchsploit is CLI exploit searching tool

<br><br>

### Winodws - Windows services, Actve Directory, etc.
Name | Description
---- | ----
[Evil-Winrm](https://github.com/Hackplayers/evil-winrm) | Penetration testing tool for exploiting Windows Remote Management (WinRM)
[Get-LAPSPasswords.ps1](https://github.com/kfosaaen/Get-LAPSPasswords.git) | Powershell script to get LAPS passwords 

<br><br>


## General purpose tools - Non Penetration testing tools

<br><br>

### Virtualization 
Name | Description
---- | ----
[Virtual Box](https://www.virtualbox.org/) | Free Open Source VM Manager from Oracle
[OVFToll](https://developer.vmware.com/web/tool/4.4.0/ovf) | create vmx to ovf and vmx to ova for importing vmware machine into virtualbox

<br><br>

### Report Writing - Note Keeping 
Name | Description
---- | ----
[CherryTree](https://www.giuspen.net/cherrytree/) | A hierarchical tree structure type note keeping tool with advanced features 
[FlameShot](https://flameshot.org/) | An advanced software for taking screenshots

<br><br>

### Package Manager
Name | Description
---- | ----
[Nala](https://gitlab.com/volian/nala) | Nala is a frontend for apt it is not replacement of it, it just insanely improves it functionality.

<br><br>
