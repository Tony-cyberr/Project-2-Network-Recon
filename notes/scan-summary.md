# Scan Summary

## Target
- IP address: 192.168.64.2
- Host status: Online
- Target system: Ubuntu-SOC-Lab VM

## Host Discovery Results
Nmap host discovery identified two live hosts on the lab network:
- 192.168.64.1: likely UTM gateway/router
- 192.168.64.2: Ubuntu-SOC-Lab target VM

## Basic Port Scan Results
The basic Nmap port scan found one open TCP port:
- 22/tcp open ssh

## Service Version Detection
Nmap identified the SSH service as:
- OpenSSH 10.2p1 Ubuntu 2ubuntu3.2
- Protocol: SSH protocol 2.0
- OS information: Ubuntu Linux

## Initial Assessment
The target VM has a minimal exposed attack surface. Only SSH is open, which is expected because the VM is administered remotely through SSH.

## Security Notes
SSH is a legitimate remote administration service, but it should still be secured using strong passwords or SSH keys, limited access, and regular patching.
