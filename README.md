# enum-attacking-net-services


Locate and enum open smb shares:

``nmap -T4 -v -oA shares --script smb-enum-shares --script-args smbuser=username,smbpass=password -p445 192.168.1.0/24``

Scan for vulnerable SMB servers:

``nmap -v -p 445 --script=smb-check-vulns 
--script-args=unsafe=1 192.168.1.0/24``

todo: add metasploit/bash automated scanners
