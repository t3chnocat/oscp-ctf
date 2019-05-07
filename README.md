## oscp-ctf 

oscp-ctf is a small collection of basic Bash scripts that make life easier and save time whether you are in the OSCP labs, HackThebox or playing around with CTFs.

### tun
Spits out the IP address of tun0, the default interface used by OpenVPN.

### rock
Uses [John The Ripper](https://github.com/magnumripper/JohnTheRipper) to crack a given password/hash file using rockyou.txt

### php-rs
Edits Pentestmonkey's PHP reverse shell with your IP/port and copies it to the current path with a filename of your choice.

### http
Uses Python's SimpleHTTPServer to easily start a HTTP server with a port and location of your choice. Shows the IP address for convenience.

### ftpscript
Outputs a one liner to paste into a Windows host to create and run a ftp script to download a given file.

### smb-menu 
Uses [impacket's](https://github.com/SecureAuthCorp/impacket) smbserver.py to start a SMB server with a name and location of your choice. 

### smb
Same functionality as smb-menu without a menu.

php-rs, rock, smb and smb-menu have user variables so check those before running.

More information and screenshots can be found at this [blog post](https://www.t3chnocat.com/oscp-ctf-scripts/)



