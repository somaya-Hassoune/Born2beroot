# Born2beroot
# Born2BeRoot – System Administration Project

## Introduction

Born2BeRoot is a system administration project from the 42/1337 curriculum.

The goal is to set up a secure virtual machine running a Linux operating system and to understand how a system works, how to secure it, and how to manage it properly.

---

## What is the purpose of this project?

This project helps you learn:

- How to install and configure a Linux system
- How to manage users and permissions
- How to secure a server
- How SSH works
- How to configure a firewall
- How to apply security rules

---

## Virtual Machine Setup

You will use:

- A virtual machine (VM)
- Debian (Linux OS)
- VirtualBox

The VM simulates a real server environment.

---

## Users and Groups

### What are users?

- A user is an account on the system
- Each user has permissions and access rights

### What are groups?

- A group is a collection of users
- Used to manage permissions easily

Example:
- A user in the `sudo` group can execute administrative commands

---

## SSH (Secure Shell)

SSH allows you to connect to your VM remotely.

### Important rules:

- Password login must be disabled
- Only SSH key authentication is allowed
- SSH runs on a specific port (not the default 22 in some cases)

Why?
- To improve security
- To prevent unauthorized access

---

## Firewall (UFW)

The firewall controls incoming and outgoing network traffic.

### Rules to follow:

- Only necessary ports are open
- All other connections are blocked
- UFW is used to manage firewall rules

This helps protect your system from attacks

---

## Password Policy

You must enforce strong password rules:

- Minimum length
- Complexity (uppercase, lowercase, numbers, symbols)
- Password expiration

This prevents weak passwords and improves security

---

## sudo Configuration

`s​udo` allows users to execute commands as root.

### Security rules:

- Only authorized users can use sudo
- All sudo actions are logged
- Strong configuration must be applied

---

## Signature File

The `signature.txt` file contains a unique hash of your virtual machine.

👉 It ensures:
- The VM has not been modified
- The system integrity is maintained

---

## Important Security Notes

- ❌ Never share passwords
- ❌ Never share SSH private keys
- ❌ Never expose sensitive system files
- ✔️ Only share explanations and configurations

---

## What You Will Learn

- Linux system administration
- Server configuration
- System security
- User and permission management
- Networking basics
- Virtualization concepts

---

## Tips for Success

- Understand each command you use
- Don’t copy blindly
- Test your configuration step by step
- Use documentation and man pages
- Think like a system administrator

---

##  Author

Somaya-Hassoune – 1337 Student
