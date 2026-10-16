## Question 1
Answer: I am faiqashahzad026. My home folder is /home/faiqashahzad026.
Commands: whoami, pwd

## Question 2
Answer: The server's name is ubuntu, and it runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has 1.6Gi of RAM, and 2.4G of disk space is available.
Commands: free -h, df -h /

## Question 4
Answer: Users that can log in with /bin/bash can be found by searching /etc/passwd.
Commands: grep "bash" /etc/passwd

## Question 5
Answer: There are active processes running on the server.
Commands: ps aux | wc -l

## Question 6
Answer: Lab5user creation and deletion times are recorded in the security log.
Commands: sudo grep lab5user /var/log/auth.log
