## Question 1
Answer: I am student. My home folder is /home/student.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu-lab01 and it runs Ubuntu 24.04.3 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has 1.9Gi of RAM and 4.0G of free disk space.
Commands: free -h, df -h /

## Question 4
Answer: root and student can log in with bash.
Commands: grep bash /etc/passwd

## Question 5
Answer: 220 processes are running.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at (time) and deleted at (time).
Commands: sudo grep lab5user /var/log/auth.log
