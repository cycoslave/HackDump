https://hackersonlineclub.com/command-injection-cheatsheet/


OSCP journey blog (Rana from HBT Ott)
https://ranakhalil101.medium.com/my-oscp-journey-a-review-fa779b4339d9

https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS

https://github.com/telekom-security/tpotce

dissassembler 
https://onlinedisassembler.com/odaweb/

https://packetlife.net/media/library/23/common-ports.pdf
https://web.mit.edu/rhel-doc/4/RH-DOCS/rhel-sg-en-4/ch-ports.html
https://nullsec.us/top-1-000-tcp-and-udp-ports-nmap-default/

find social media accounts
https://github.com/sherlock-project/sherlock


http://www.xss-payloads.com/
https://www.exploit-db.com/
https://gchq.github.io/CyberChef/


https://portswigger.net/web-security
https://www.offensive-security.com/metasploit-unleashed/meterpreter-basics/
https://hashcat.net/wiki/doku.php?id=example_hashes
https://owasp.org/www-community/attacks/SQL_Injection
https://github.com/SecureAuthCorp/impacket

General:

https://github.com/swisskyrepo/PayloadsAllTheThings (A bunch of tools and payloads for every stage of pentesting)


Linux:

https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/ (a bit old but still worth looking at)

https://github.com/rebootuser/LinEnum (One of the most popular priv esc scripts)

https://github.com/diego-treitos/linux-smart-enumeration/blob/master/lse.sh (Another popular script)

https://github.com/mzet-/linux-exploit-suggester (A Script that's dedicated to searching for kernel exploits)


https://gtfobins.github.io (I can not overstate the usefulness of this for priv esc, if a common binary has special permissions, you can use this site to see how to get root perms with it.)


Windows:


https://www.fuzzysecurity.com/tutorials/16.html  (Dictates some very useful commands and methods to enumerate the host and gain intel)


https://github.com/PowerShellEmpire/PowerTools/tree/master/PowerUp (A bit old but still an incredibly useful script)


https://github.com/411Hall/JAWS (A general enumeration script)

https://gtfobins.github.io/gtfobins/systemctl/

https://en.wikipedia.org/wiki/Alice_and_Bob

https://github.com/Ganapati/RsaCtfTool
https://github.com/ius/rsatool

https://www.openwall.com/john/doc/RULES.shtml
https://muirlandoracle.co.uk/2020/01/29/rsa-encryption/
https://robertheaton.com/2014/03/27/how-does-https-actually-work/

https://github.com/rebootuser/LinEnum/blob/master/LinEnum.sh
https://gtfobins.github.io/
    https://github.com/netbiosX/Checklists/blob/master/Linux-Privilege-Escalation.md
    https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md
    https://sushant747.gitbooks.io/total-oscp-guide/privilege_escalation_-_linux.html
    https://payatu.com/guide-linux-privilege-escalation


https://github.com/diego-treitos/linux-smart-enumeration
https://github.com/rebootuser/LinEnum
https://github.com/linted/linuxprivchecker
https://github.com/AlessandroZ/ReRoot
http://pentestmonkey.net/tools/audit/unix-privesc-check

common backup location
~, /, /tmp, /var/backups

shell escape sequences - https://gtfobins.github.io/

find suid/sgid files
find / -type f -a \( -perm -u+s -o -perm -g+s \) -exec ls -l {} \; 2> /dev/null

create root bash with suid
cp /bin/bash /tmp/rootbash; chmod +s /tmp/root/bash

privesc cheatcheat
https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/


https://github.com/PowerShellMafia/PowerSploit/blob/master/Privesc/PowerUp.ps1

hydra reference - https://en.kali.tools/?p=220

https://docs.python.org/3/tutorial/inputoutput.html
https://www.tutorialsteacher.com/python/python-read-write-file


Desktop eManuel: https://www.zaproxy.org/docs/desktop/ui/
OWASP ZAP Forums: https://groups.google.com/forum/#!forum/zaproxy-users 
ZAP in Ten: https://www.alldaydevops.com/zap-in-ten

