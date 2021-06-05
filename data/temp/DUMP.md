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

https://github.com/zaproxy/zap-extensions
https://github.com/bugcrowd/HUNT


https://blog.nvisium.com/p263
https://blog.nvisium.com/p255
https://github.com/VerSprite/flask-json-pickle

JWT: https://jwt.io/


https://www.unix-ninja.com/p/A_cheat-sheet_for_password_crackers
https://github.com/s0md3v/Bolt/blob/master/db/hashes.json



MS strings: Sysinternals
https://shattered.io/static/shattered.pdf
https://www.garykessler.net/library/file_sigs.html
https://hybrid-analysis.com/
https://any.run/
https://regexr.com/
https://www.geeksforgeeks.org/awk-command-unixlinux-examples/
http://osr5doc.xinuos.com/en/OSUserG/_The_printf_statement.html
https://www.tutorialspoint.com/awk/awk_workflow.htm
https://www.geeksforgeeks.org/sed-command-in-linux-unix-with-examples/
https://www.gnu.org/software/sed/manual/sed.html
https://www.tecmint.com/linux-sed-command-tips-tricks/

https://www.hackingarticles.in/exploiting-wildcard-for-privilege-escalation/

https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/ 
https://www.hackingarticles.in/linux-privilege-escalation-using-suid-binaries/


JWT
https://github.com/Sjord/jwtdemo/
https://github.com/DiogoMRSilva/websitesVulnerableToSSTI
https://github.com/lmammino/jwt-cracker
https://authlab.digi.ninja/JWT_Cracking

XXE
https://github.com/jbarone/xxelab


windows event viewer
https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/manage/component-updates/command-line-process-auditing#try-this-explore-command-line-process-auditing
https://docs.splunk.com/Documentation/UBA/5.0.4/GetDataIn/AddPowerShell
https://www.fireeye.com/blog/threat-research/2016/02/greater_visibilityt.html
https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_logging_windows?view=powershell-7.1
https://apps.nsa.gov/iaarchive/library/reports/spotting-the-adversary-with-windows-event-log-monitoring.cfm

sysmon
https://github.com/SwiftOnSecurity/sysmon-config
https://github.com/ion-storm/sysmon-config/blob/develop/sysmonconfig-export.xml


https://sushant747.gitbooks.io/total-oscp-guide/content/spawning_shells.html
https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys
https://lauraliparulo.altervista.org/most-common-linux-file-extensions/
https://devblogs.microsoft.com/scripting/use-powershell-to-parse-saved-event-logs-for-errors/

lock picking
https://www.lockpickworld.com/pages/lockpicking-guides-types-of-locks-and-how-to-pick-them
https://unitedlocksmith.net/blog/how-to-pick-locks-the-definitive-guide-to-lock-picking
https://www.art-of-lockpicking.com/how-to-pick-a-lock-guide/
https://www.art-of-lockpicking.com/single-pin-picking-skills/
https://www.art-of-lockpicking.com/security-pins/
http://lockwiki.com/index.php/Security_pin
http://theamazingking.com/lock-spp.php


https://neverendingsecurity.wordpress.com/2015/04/13/linux-tar-commands-cheatsheet/
http://irtfweb.ifa.hawaii.edu/~lockhart/gpg/
https://neverendingsecurity.wordpress.com/2015/04/13/ss-socket-statistics-commands-cheatsheet/
https://linux.die.net/man/8/netstat
https://www.rekha.com/netstat-cheat-sheet-for-newbies.html
https://gist.github.com/adriacidre/307d2f9f5179fc748f22edac5af3d218
https://stackoverflow.com/questions/43537851/difference-between-systemctl-and-service-command#:~:text=service%20operates%20on%20the%20files,file%20in%20%2Fetc%2Finit.
https://www.geeksforgeeks.org/comm-command-in-linux-with-examples/
https://www.geeksforgeeks.org/diff-command-linux-examples/
https://www.networkworld.com/article/3279724/comparing-files-and-directories-with-diff-and-comm.html#:~:text=The%20diff%20command%20would%20make,both%20commands%20is%20the%20same.&text=The%20comm%20command%20can%20provide,it%20can%20compare%20two%20files.
https://www.tecmint.com/linux-more-command-and-less-command-examples/#:~:text=Learn%20Linux%20%27less%27%20Command,using%20page%20up%2Fdown%20keys.
https://ostechnix.com/the-difference-between-more-less-and-most-commands/
https://airman604.medium.com/9-ways-to-backdoor-a-linux-box-f5f83bae5a3c


https://hpbn.co/http1x/
https://www.w3.org/TR/uri-clarification/
http://www.tcpipguide.com/free/t_HTTPOverviewHistoryVersionsandStandards.htm
http://httpd.apache.org/docs/2.2/ssl/ssl_intro.html
https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html
