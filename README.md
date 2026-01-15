#COMMANDS

nmap -p -sV <IP>


gobuster dir -u http://<IP> -w wordlist.txt
dirb http://<IP>

nikto -h http://<IP>

sqlmap -u "<URL>" --dbs

hydra -l user -P passwords.txt <IP> ssh

nc -lvnp <port>
nc <IP> <port>

whoami
id
uname -a

sudo -l
find / -perm -4000 2>/dev/null
