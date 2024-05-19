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
- **2.4. Permissions**: `chmod`, `chown`, `chgrp`, understanding file permissions
- **2.5. Compression and Archiving**: `tar`, `gzip`, `gunzip`, `zip`, `unzip`

### **3. Shell Scripting**

- **Basics**: Writing simple scripts, variables, control structures (if, case, loops)
- **Advanced**: Functions, error handling, and script debugging
- **Useful Commands**: `cron`, `at`, `sleep`, `nohup`

### **4. Linux File System**

- **Structure**: Understanding `/`, `/home`, `/var`, `/etc`, `/usr`, and other directories
- **Mounting and Unmounting**: `mount`, `umount`, `fstab`
- **Disk Management**: `df`, `du`, `fdisk`, `mkfs`, `fsck`, `parted`
- **File Systems**: ext4, xfs, btrfs

### **5. User and Group Management**

- **Users**: `useradd`, `userdel`, `usermod`
- **Groups**: `groupadd`, `groupdel`, `groupmod`
- **Password Management**: `passwd`, `chage`

### **6. Networking**

- **Basics**: IP addressing, subnetting, and CIDR notation
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
