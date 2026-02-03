# Linux & HPC: A Quick Guided Tour
## IBDC – Workshop Manual

---

## Why this workshop?

With the rapid evolution of biological research and high-throughput technologies,
biologists increasingly need computing skills to manage, analyse, and interpret
large datasets.

Although many tools provide graphical interfaces, command-line tools are often:
- Faster
- Reproducible
- Essential for HPC systems

---

# 🐧 LINUX

---

## Introduction to Linux

Linux is a family of free and open-source operating systems based on the Linux kernel.
The Linux kernel manages communication between software and hardware.

A complete Linux system combines the kernel with software packages and utilities,
together called Linux distributions.

Examples:
Ubuntu, Debian, Fedora, CentOS, RHEL

---

## Brief History of Linux

Linux was created in 1991 by Linus Torvalds while studying at the University of Helsinki.
It was inspired by UNIX (Minix) and developed as an open, community-driven system.

---

## Importance of Linux

- Free and open-source
- Stable and secure
- Highly customizable
- Widely used in servers and HPC
- Strong global community support

Most bioinformatics tools run on Linux.

---

## Architecture of Linux

Linux follows a layered architecture:

1. Kernel – manages CPU, memory, and devices  
2. System Libraries – interface between applications and kernel  
3. Shell – command-line interface  
4. Hardware – CPU, RAM, storage, I/O  
5. System Utilities – system management tools  

---

## The Terminal

The terminal is a text-based interface used to interact with Linux.

- Terminal: input/output window
- Shell: command interpreter
- CLI: typed command interface

To run a command, type it and press Enter.

---

## Linux File Hierarchy Structure

Linux follows the Filesystem Hierarchy Standard (FHS).

- Root directory: /
- User home directories: /home/username
- Root user home: /root

Common directories:

| Directory | Purpose |
|--------|--------|
| /bin | Essential commands |
| /etc | Configuration files |
| /home | User files |
| /usr | Applications |
| /var | Logs |
| /tmp | Temporary files |

---

## The Linux Shell

When the shell opens, you see a prompt:

```text
username@hostname:~$

