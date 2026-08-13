# Infrastructure Report

## 1. Cloud Server Investigation

The Linux cloud environment was investigated using basic Linux commands. The investigation focused on the operating system, kernel, CPU, RAM, disk, mounted file systems, hostname, and IP address.

## 2. System Information

### Commands Used

```bash
cat /etc/os-release
uname -r
lscpu | grep "Model name"
nproc
free -h
df -h
findmnt
hostname
hostname -I
