# Linux Basics

This document contains my notes and practice on Linux fundamentals as part of my transition toward a Sysadmin / Server Engineering role.

## What is Linux
Linux is an open-source operating system kernel commonly used on servers due to its stability, security, and flexibility. 
Most hosting and cloud environments are based on Linux distributions.

## Linux Distributions
A Linux distribution is a complete operating system built around the Linux kernel.
Some common distributions used in servers include:
- Ubuntu Server
- Debian
- CentOS / Rocky Linux
- AlmaLinux

## Basic Command Line Usage
Some basic commands I practice regularly:

- `ls` – list files and directories
- `cd` – navigate between directories
- `pwd` – show current directory
- `cp`, `mv`, `rm` – manage files
- `mkdir`, `rmdir` – create and remove directories
- `cat`, `less`, `head`, `tail` – view file contents

## Users and Permissions
Linux is a multi-user system where access is controlled through users, groups, and permissions.

- Read (`r`), write (`w`), and execute (`x`) permissions
- Permission levels: owner, group, others
- Using `chmod` to modify permissions
- Using `chown` to change file ownership

I’m currently practicing permission management to better understand numeric and symbolic modes.

## Processes and Services
Basic process and service management includes:

- `ps`, `top` – view running processes
- `kill` – terminate processes
- `systemctl` – manage services
  - start, stop, restart, enable, status

## Networking Basics
Basic networking concepts I’m studying:

- IP addresses and ports
- Checking network configuration with `ip a`
- Testing connectivity with `ping` and `curl`

## Logs and Troubleshooting
Logs are essential hooking points for troubleshooting.

- System logs commonly located in `/var/log`
- Using `journalctl` to inspect service logs

## Next Steps
Topics I plan to study and practice next:
- File system structure and disk usage
- Package management (`apt`, `dnf`)
- Shell scripting basics
- Web server configuration basics
