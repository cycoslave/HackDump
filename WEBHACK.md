# How to start
How do you start probing a web application?

## Data gathering
- mkdir boxname (or something relevant to the network/system you are attacking)
- might want to create a text file with important information

## On a LAN
- netdiscover -i eth0 -r 10.0.0.0/24 > ./boxname/lan.txt

## Recon
- nmap -A -T4 -n -p- 10.0.0.176 > ./boxname/nmap.txt
- enable the burp suite proxy, turn intercept off
- visit the website, get familiar with it if you are not
- right click and review source code to see if anything is interresting
- nikto -h http://10.0.0.176 > ./boxname/nikto.txt
- review nikto report
- check locations in robot.txt
- wafw00f http://10.0.0.176 > ./boxname/app_firewall.txt
- enumerate directories (dirb, dirbuster, autorecon, burp suite, gobuster)
    dirb http://10.0.0.176 > dirscan.txt
    dirb http://10.0.0.176 /usr/share/dirb/wordlists/big.txt > dirscan_long.txt
    dirbuster -l /usr/share/wordlists/dirbuster/<pick one of the files>
- try to enumerate users and maybe brute force passwords, but that takes time

## Wordpress
- wpscan --help (shows all the example needed)
  not a bad idea to start by enumerating users
- try to brute force password if possible 
