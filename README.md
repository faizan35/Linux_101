# Linux_101

```sh
git clone https://github.com/faizan35/Linux_101.git
```

---

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

- **[6.1. Basics](./06-Networking/6.1-Basics.md)**: IP addressing, subnetting, and CIDR notation
- **Network Configuration**: `ifconfig`, `ip`, `nmcli`, `netplan`
- **DNS**: `dig`, `nslookup`
- **Troubleshooting**: `ping`, `traceroute`, `netstat`, `ss`, `tcpdump`
- **Services**: SSH (`ssh`, `sshd_config`), FTP, HTTP/HTTPS

### **7. System Administration**

- **Package Management**: `apt`, `yum`, `dnf`, `snap`
- **Processes**: `ps`, `top`, `htop`, `kill`, `nice`, `renice`
- **System Monitoring**: `vmstat`, `iostat`, `dstat`, `glances`
- **Logging**: `syslog`, `journalctl`, configuring log rotation
- **Systemd**: Managing services with `systemctl`, creating and managing units

### **8. Security**

- **File and Network Security**: `iptables`, `ufw`, `firewalld`
- **SELinux**: Basic concepts and commands (`getenforce`, `setenforce`, `semanage`)
- **AppArmor**: Basics and usage
- **User Security**: `sudo`, managing sudoers, and least privilege principle
- **Encryption**: GPG, SSL/TLS basics

### **9. Virtualization and Containers**

- **Virtualization**: KVM, QEMU basics
- **Containers**: Docker, basic commands, and concepts (images, containers, volumes, networks)
- **Orchestration**: Introduction to Kubernetes, basic kubectl commands

### **10. Automation and Configuration Management**

- **Introduction to Automation**: Understanding the need for automation in DevOps
- **Configuration Management Tools**: Ansible, basic playbooks, and modules
- **Scripting for Automation**: Using shell scripts, Python scripts for routine tasks

### **11. DevOps Tools and Practices**

- **Version Control**: Git basics, branching, merging
- **CI/CD Pipelines**: Jenkins, GitLab CI/CD, basic pipeline creation
- **Infrastructure as Code (IaC)**: Introduction to Terraform, creating and managing infrastructure

### **12. Advanced Topics**

- **Performance Tuning**: Kernel tuning parameters, optimizing system performance
- **High Availability and Load Balancing**: Concepts, tools (HAProxy, Keepalived)
- **Backup and Recovery**: Strategies, tools (rsync, tar, etc.)
- **Monitoring and Alerting**: Prometheus, Grafana basics

### **13. Practical Projects**

- **Project 1**: Set up a LAMP stack (Linux, Apache, MySQL, PHP) with automation scripts
- **Project 2**: Configure a secure SSH server with custom login messages and key-based authentication
- **Project 3**: Create a CI/CD pipeline using Jenkins and deploy a sample application
- **Project 4**: Deploy and manage a Dockerized application with Kubernetes

### **Resources and Further Learning**

- **Books**: "The Linux Command Line" by William Shotts, "Linux Bible" by Christopher Negus
- **Online Courses**: Coursera, Udemy, edX for Linux and DevOps-related courses
- **Documentation**: Official documentation for Linux distributions, Docker, Kubernetes, Ansible, etc.

This syllabus should provide a structured path for mastering Linux as a DevOps engineer, ensuring a solid foundation and the ability to handle complex tasks and projects.
