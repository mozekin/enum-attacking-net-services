# enum-attacking-net-services


``Locate end enum open smb shares:``

``nmap -T4 -v -oA shares --script smb-enum-shares --script-args smbuser=username,smbpass=password -p445 192.168.1.0/24``
