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

![image alt](https://github.com/GTRR3530/COLDBOX/blob/47df675b1503df74e29fe794693f6244328d55f9/Screenshot%20(8).png)
