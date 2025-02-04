![image](https://github.com/user-attachments/assets/95bf40b6-44c8-4387-bd63-0b2d31e6328c)

KALI LINUX most used commands examples:

- gobuster dir -u https://example.com -w /wordlists/Discovery/Web-Content/common.txt  #gobuster
- dirbuster -h # just print: gobuster
- ffuf -w path/to/dictionary.txt -u http://server_url/indexFUZZ
- wfuzz -c -Z -w rockyou.txt http://FUZZ.site.com
- BurpSuite - > intruder -> sniper or pitchwork
- ncrack -U user.txt -P pass.txt 192.168.166.234:21 -v
- ncrack -U user.txt -P pass.txt 192.168.166.234:23 -v
- ncrack -U user.txt -P pass.txt 192.168.166.234:22 -v
- sudo medusa -U user.txt -P pass.txt -h 192.168.166.234 -M ssh
- sudo medusa -U user.txt -P pass.txt -h 192.168.166.234 -M ftp
- hydra -L user.txt -P pass.txt ftp://192.168.166.234:21
- crowbar -b rdp -s 192.168.2.0/24 -U ~/Desktop/userlist -C ~/Desktop/passlist -d
- python3 web–brutator.py --target standardform --url https://site.com/wp-login.php -u admin -P pass.txt -s -t 40 -v
- wpscan --url http://192.168.1.100/wordpress/ -U users.txt -P /usr/share/wordlists/rockyou.txt
- instashell #PASSWORDS wordlist
- patator ftp_login host=10.10.0.50 user=FILE0 password=FILE1 0=usernames.txt 1=passwords.txt

TOP Scan
- nmap -sC -sV -T4 "IP"
- nmap -sX "IP"
  
Another crawlers
- python photon.py -u "http://example.com"

OSINT
- sherlock
Leaked DB
- curl https://api.proxynova.com/comb?query=jrubin&start=0&limit=15 | jq
