# Linux 101

Creating a comprehensive Linux learning syllabus for a DevOps engineer involves covering foundational topics, system administration, networking, security, and automation. Here's a structured syllabus to follow:

### **1. Introduction to Linux**

- **[1.1. Overview of Linux](./01-Introduction-to-Linux/1.1-Overview-of-Linux.md)**: History, distributions.
- **[1.2. Distributions different from `Ubuntu`](./01-Introduction-to-Linux/1.2-Distributions-different-from-Ubuntu.md)**: Package Manager, etc
- **Installation**: Installing Linux (e.g., Ubuntu, CentOS) on physical/virtual machines.

### **2. Basic Linux Commands**

- **[2.1. File System Navigation](./02-Basic-Linux-Commands/2.1-File-System-Navigation.md)**: `ls`, `cd`, `pwd`, `find`, `locate`
- **[2.2. File Operations](./02-Basic-Linux-Commands/2.2-File-Operations.md)**: `cp`, `mv`, `rm`, `mkdir`, `rmdir`, `touch`
- **[2.3. Text Manipulation](./02-Basic-Linux-Commands/2.3-Text-Manipulation.md)**: `cat`, `less`, `more`, `head`, `tail`, `grep`, `sed`, `awk`
- **[2.4. Permissions](./02-Basic-Linux-Commands/2.4-Permissions.md)**: `chmod`, `chown`, `chgrp`, `umask`, understanding file permissions
- **[2.5. Compression and Archiving](./02-Basic-Linux-Commands/2.5-Compression-and-Archiving.md)**: `tar`, `gzip`, `gunzip`, `zip`, `unzip`
- **[2.6. Piping and Redirection](./02-Basic-Linux-Commands/2.6-Piping-and-Redirection.md)**: `|` (pipe), `>` (redirect output), `>>` (append output), `tee`

### **3. Shell Scripting**

- **[3.1. Basics](./03-Shell-Scripting/3.1-Basics.md)**: Writing simple scripts, variables, control structures (if, case, loops)
- **3.2. Advanced**: Functions, error handling, and script debugging
- **3.3. Useful Commands**: `cron`, `at`, `sleep`, `nohup`

### **4. Linux File System**

- **[4.1. Structure](./04-Linux-File-System/4.1-Structure.md)**: Understanding `/`, `/home`, `/var`, `/etc`, `/usr`, and other directories
- **[4.2. Mounting and Unmounting](./04-Linux-File-System/4.2-Mounting-and-Unmounting.md)**: `mount`, `umount`, `fstab`
- **[4.3. Disk Management](./04-Linux-File-System/4.3-Disk-Management.md)**: `df`, `du`, `fdisk`, `mkfs`, `fsck`, `parted`
- **[4.4. File Systems](./04-Linux-File-System/4.4-File-Systems.md)**: ext4, xfs, btrfs
- **[4.5. Soft and Hard Links](./04-Linux-File-System/4.5-Soft-and-Hard-Links.md)**: Understanding soft links (`ln -s`) and hard links (`ln`)

### **5. User and Group Management**

- **[5.1. Users](./05-User-Group-Management/5.1-Users.md)**: `useradd`, `userdel`, `usermod`
- **[5.2. Groups](./05-User-Group-Management/5.2-Groups.md)**: `groupadd`, `groupdel`, `groupmod`
- **[5.3. Password Management](./05-User-Group-Management/5.3-Password-Management.md)**: `passwd`, `chage`

### **6. Networking**

- **[6.1. Network Configuration](./06-Networking/6.1-Network-Configuration.md)**: `ifconfig`, `ip`, `nmcli`, `netplan`
- **[6.2. DNS](./06-Networking/6.2-DNS.md)**: `dig`, `nslookup`
- **[6.3. Troubleshooting](./06-Networking/6.3-Troubleshooting.md)**: `ping`, `traceroute`, `netstat`, `ss`, `tcpdump`
- **[6.4. `SSH`, `SCP`](./06-Networking/6.4-SSH-SCP.md)**

### **7. System Administration**

- **[7.1. Package Management](./07-System-Administration/7.1-Package-Management.md)**: `apt`, `yum`, `dnf`, `snap`
- **[7.2. Processes](./07-System-Administration/7.2-Processes.md)**: `ps`, `top`, `htop`, `kill`, `nice`, `renice`
- **[7.3. System Monitoring](./07-System-Administration/7.3-System-Monitoring.md)**: `vmstat`, `iostat`, `dstat`, `glances`
- **[7.4. Logging](./07-System-Administration/7.4-Logging.md)**: `syslog`, `journalctl`, configuring log rotation
- **[7.5. Systemd](./07-System-Administration/7.5-Systemd.md)**: Managing services with `systemctl`, creating and managing units

### **8. Security**

- **[8.1. File and Network Security](./08-Security/8.1-File-Network-Security.md)**: `iptables`, `ufw`, `firewalld`
- **SELinux**: Basic concepts and commands (`getenforce`, `setenforce`, `semanage`)
- **AppArmor**: Basics and usage
- **User Security**: `sudo`, managing sudoers, and least privilege principle
- **Encryption**: GPG, SSL/TLS basics

---
