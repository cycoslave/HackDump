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


AWS S3 Bucket
https://docs.aws.amazon.com/cli/latest/reference/configure/
https://docs.aws.amazon.com/general/latest/gr/root-vs-iam.html
https://docs.aws.amazon.com/cli/latest/userguide/cli-services-dynamodb.html

enum nfs share -> https://ethicalhackingguru.com/how-to-enumerate-and-exploit-nfs-shares/

thispersondoesnotexist.com
to create fake profiles for osint

ahmia.fi - dark web search

https://www.tracelabs.org/initiatives/search-party - ctf for missing ppl

OWASP cheatsheet -0 https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Input_Validation_Cheat_Sheet.md

blog - https://brutelogic.com.br/blog/xss101/

bounty hunting - https://knoxss.me/

JS Beautifier - https://beautifier.io/

https://github.com/blaCCkHatHacEEkr/PENTESTING-BIBLE
http://wuvel.net/cheat-sheet/



## Resources
### Virtual machine images
* [VulnHub](https://www.vulnhub.com/)


https://github.com/phlmox/public-reports/blob/main/hackerone-one-million-reports

https://bugbountyhunter.com/

https://www.securecodewarrior.com/
https://thexssrat.podia.com/dashboard

https://github.com/KaliHash/Practical_Ethical_Hacking_Mindmap


https://www.kitploit.com/2021/07/gitdump-pentesting-tool-that-dumps.html

https://sploitus.com/

https://cyberpolygon.com/materials/security-of-json-web-tokens-jwt/
https://book.hacktricks.xyz/pentesting-web/hacking-jwt-json-web-tokens
https://www.nccgroup.com/ae/about-us/newsroom-and-events/blogs/2019/january/jwt-attack-walk-through/

#OSINT tools:
whois http://whoxy.com
company http://opencorporates.com
person http://truepeoplesearch.com
twitter http://tweetbeaver.com
exif data http://exif.regex.info/exif.cgi
archive http://archive.org
mind map http://xmind.net
translator http://babelfish.com

firewall tutorial
https://www.youtube.com/playlist?list=PL8PnAf11sThUyzc2FUvcvOk1ksfWvkKsJ

webapp pentesting
https://www.youtube.com/playlist?list=PL8PnAf11sThVqeqptNmF9vSZ9tRvaeQtX

https://www.fuzzysecurity.com/
https://adsecurity.org/
https://book.hacktricks.xyz/
https://medium.com/the-innovation/best-youtube-channels-to-learn-cybersecurity-in-2020-b1c445923acf
https://www.hackingarticles.in/
https://agdcservices.com/blog/resources-for-learning-malware-analysis/
https://start.me/p/q6mw4Q/forensics
https://soc-class.com/pres/
https://soc-class.com/res/
https://freetraining.dfirdiva.com/
https://linkshare.olafhartong.nl/
https://www.youtube.com/c/SpinTheHack
https://www.stokfredrik.com/bugbountytraining
https://www.youtube.com/c/HackerSploit
https://www.levelupinfosec.com/freestuff
https://wakelet.com/wake/ZoDim7iESNHwLFr4DJeOC
https://cacr.uwaterloo.ca/hac/
https://vx-underground.org/
https://www.youtube.com/c/CyberBruhArmy
https://www.hoppersroppers.org/
https://frsecure.com/cissp-mentor-program/
https://whoami.securitybreached.org/2019/06/03/guide-getting-started-in-bug-bounty-hunting/
https://www.youtube.com/c/CyberBlackHole

https://replit.com/
https://github.com/obheda12/GitDorker
https://github.com/projectdiscovery/interactsh
https://github.com/six2dez/reconftw
https://github.com/Edu4rdSHL/unimap
https://portswigger.net/web-security/cross-site-scripting
https://github.com/yogisec/VulnerableSAMLApp
https://github.com/Sjord/jwtdemo
https://github.com/david3107/graphql-security-labs
https://github.com/koenbuyens/Vulnerable-OAuth-2.0-Applications
https://github.com/Audi-1/sqli-labs


https://xsshunter.com/features
https://www.0hak.com/
https://nmap.org/book/osdetect.html
https://lcamtuf.coredump.cx/p0f3/
https://www.crunchbase.com/
https://dnsdumpster.com/
https://drive.google.com/file/d/15nzQK_FprTAbfwrFBAlhCsXJo-CWrOww/view
https://infosecwriteups.com/idor-on-api-endpoints-e08c740e87a2

https://www.blackhillsinfosec.com/

useragentstring.com

https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting-ebook-dp-B005LVQA9S/dp/B005LVQA9S/ref=mt_other?_encoding=UTF8&me=&qid=
https://owasp.org/www-community/attacks/xss/
https://www.amazon.com/Google-Hacking-Penetration-Testers-Johnny/dp/1597491764/ref=sr_1_1?ie=UTF8&qid=1302083660&sr=8-1
https://developers.google.com/custom-search/docs/xml_results
https://www.exploit-db.com/google-hacking-database
https://www.valuelabs.com/
https://blog.0xffff.info/2021/06/23/winning-the-race-signals-symlinks-and-toc-tou/
https://insomniasec.com/blog/airtag-hacking
https://github.com/scythe-io/community-threats/tree/master/CompoundActions/T1003.002%20-%20OS%20Credential%20Dumping%20-%20SAM
https://www.romainthomas.fr/post/21-07-pokemongo-anti-frida-jailbreak-bypass/
https://medium.com/appsflyer/nginx-may-be-protecting-your-applications-from-traversal-attacks-without-you-even-knowing-b08f882fd43d
https://blog.0xffff.info/2021/07/24/a-guide-to-non-conventional-waf-ids-evasion-techniques/
https://securib.ee/newsletter/

https://www.youtube.com/watch?v=mjrGOuFc1Kw
https://www.youtube.com/watch?v=hZ0xSRswN8M
https://www.youtube.com/watch?v=5vYhTik8_yU
https://www.youtube.com/watch?v=XkCfySN7US0

https://info.varonis.com/en/thank-you/intro-to-ransomware-with-troy-hunt-free-video-course?submissionGuid=b717c86b-6e3d-44e6-be6a-8c0487f64a7e

https://www.w3schools.com/sql/sql_intro.asp
https://howsecureismypassword.net/
https://www.keepassx.org/
https://keepass.info/
http://web.archive.org/web/20150715001201/http:/www.offensivecomputing.net/?q=taxonomy/term/1
https://www.amazon.com/Hacking-Exposed-Malware-amp-Rootkits/dp/0071823077/ref=sr_1_3?s=books&ie=UTF8&qid=1423220013&sr=1-3
https://wiki.skullsecurity.org/index.php/Main_Page
https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html
https://ss64.com/nt/if.html
https://ss64.com/nt/for.html
https://ss64.com/nt/else.html
https://ss64.com/nt/
https://blog.brainasoft.com/all-internal-commands-of-cmd/
https://tldp.org/LDP/abs/html/comparison-ops.html

https://pimeyes.com/en
https://www.amazon.com/Violent-Python-Cookbook-Penetration-Engineers/dp/1597499579/ref=sr_1_10?ie=UTF8&qid=1361544887&sr=8-10&keywords=python+programming
https://docs.python.org/3/library/index.html
https://docs.python.org/3/tutorial/index.html
https://nostarch.com/black-hat-python2E
https://docs.python.org/3/library/http.client.html
https://docs.python.org/3/library/platform.html
https://docs.python.org/3.3/library/os.html
https://docs.python.org/3/library/socket.html

https://book.hacktricks.xyz/pentesting-web/hacking-jwt-json-web-tokens#new-public-key-inside-the-header
https://nvd.nist.gov/vuln/detail/CVE-2018-0114
https://github.com/Frichetten/CVE-2019-5736-PoC
https://blog.dragonsector.pl/2019/02/cve-2019-5736-escape-from-docker-and.html
https://book.hacktricks.xyz/linux-unix/privilege-escalation/docker-breakout#runc-exploit-cve-2019-5736
https://gist.github.com/ygotthilf/baa58da5c3dd1f69fae9
https://kurtikleiton.medium.com/json-web-token-exploitation-for-red-team-580eea1fe46a
https://medium.com/swlh/hacking-json-web-tokens-jwts-9122efe91e4a
https://www.monkey.org/~dugsong/dsniff/
https://wiki.owasp.org/index.php/Testing_Checklist

https://www.graplsecurity.com/post/kernel-pwning-with-ebpf-a-love-storyhttps://www.graplsecurity.com/post/kernel-pwning-with-ebpf-a-love-story
https://dolosgroup.io/blog/2021/7/9/from-stolen-laptop-to-inside-the-company-network
https://haxolot.com/posts/2021/moodle_pre_auth_shibboleth_rce_part1/
https://malwareunicorn.org/workshops/peinjection.html#0
https://blog.sonarsource.com/zimbra-webmail-compromise-via-email
https://blog.includesecurity.com/2021/07/customizing-semgrep-rules-for-flask-django/

https://book.hacktricks.xyz/pentesting-web/file-upload
https://pentest.ws/
