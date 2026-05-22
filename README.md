# Linux Commands for MLOps

This repository contains basic Linux commands that I learned while exploring MLOps and Linux fundamentals.

Linux is very important in MLOps, DevOps, Cloud Computing, and Machine Learning deployment because most servers run on Linux systems.

---

# Basic Linux Commands

## List files and directories

```bash
ls
```

---

## Update machine packages

```bash
sudo apt update
sudo apt-get update -y
sudo apt-get upgrade
```

---

## Change directory

```bash
cd dir_name
```

---

## Create a new directory

```bash
mkdir test
```

---

## Remove a directory

```bash
rmdir test
```

---

## Print current working directory

```bash
pwd
```

---

## Open and edit file using Vim

```bash
vim file.txt
```

Save and close file:

```bash
:wq
```

---

## Copy files

```bash
cp example.txt backup/
```

---

## Move or rename files

```bash
mv example.txt backup/
```

---

## Remove files

```bash
rm example.txt
```

---

## Create empty file

```bash
touch file.txt
```

---

## Display file content

```bash
cat file.txt
```

---

## Display command manual

```bash
man ls
```

---

## View system processes

```bash
htop
top
ps aux
```

---

## View file permissions

```bash
ls -lart
```

---

## Change file permissions

```bash
chmod 700 file.txt
```

---

## Change file ownership

```bash
chown new_owner file.txt
```

---

## Compress and extract files

```bash
tar cf archive.tar file1 file2
gzip file.txt
gunzip file.txt.gz
```

---

## SSH remote server connection

```bash
ssh username@server_address
```

---

## Securely copy files

```bash
scp myfile.txt user@remotehost:/home/user/
```

---

## Check internet connection

```bash
ping 8.8.8.8
```

---

## Network commands

```bash
ifconfig
netstat
route
```

---

## Kill process

```bash
kill PID
```

---

## Manage services

```bash
systemctl start nginx
systemctl status nginx
systemctl stop nginx
```

---

## User management

```bash
useradd username
passwd username
userdel username
```

---

## Switch user

```bash
su username
```

---

## Current logged-in user

```bash
whoami
```

---

## System information

```bash
uname -a
```

---

## Command history

```bash
history
```

---

## Display date and time

```bash
date
```

---

## Disk usage

```bash
df
du
```

---

## Display text

```bash
echo "Hello Linux"
```

---

## Locate command path

```bash
which python
```

---

## Display first and last lines of file

```bash
head file.txt
tail file.txt
```

---

# Learning Journey

Currently learning:

- Linux
- MLOps
- DevOps
- Docker
- Git & GitHub
- Cloud Computing

More updates will be added soon 🚀
