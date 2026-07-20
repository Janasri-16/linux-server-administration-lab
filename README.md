## Linux Server Setup Automation

A hands-on Linux Administration project that automates the initial configuration of an Ubuntu server using Bash scripting. This project simulates the common tasks a Linux Administrator performs when provisioning a new server, reducing manual effort and ensuring a consistent setup.

---

## Project Overview

Provisioning a Linux server involves several repetitive administrative tasks such as updating packages, installing essential tools, configuring secure remote access, and enabling firewall protection.

This project automates those tasks with a single Bash script, making server initialization faster, more reliable, and repeatable.

---

## Objectives

* Perform initial Ubuntu server configuration
* Automate repetitive administration tasks
* Install essential Linux utilities
* Configure OpenSSH for remote access
* Enable and configure the UFW firewall
* Verify server readiness after setup

---

## 🛠️ Technologies Used

* Ubuntu Linux (WSL)
* Bash Scripting
* APT Package Manager
* OpenSSH
* UFW Firewall

---

##  Features

* Updates package repositories
*  Upgrades installed packages
*  Removes unused packages
*  Installs essential Linux administration tools
*  Installs OpenSSH Server
*  Configures the UFW firewall
*  Displays system information after setup

---

##  Project Structure

```text
linux-server-setup/
│
├── README.md
├── server_setup.sh
└── screenshots/
```

---

## Essential Packages Installed

* Git
* Curl
* Wget
* Vim
* Tree
* Htop
* Net-tools
* OpenSSH Server
* UFW

---

##  How to Run

Clone the repository:

```bash
git clone <repository-url>
```

Move into the project directory:

```bash
cd linux-server-setup
```

Give execution permission:

```bash
chmod +x server_setup.sh
```

Run the automation script:

```bash
./server_setup.sh
```

---

## Screenshots

Include screenshots for:

* Ubuntu Version
* System Update
* Package Installation
* SSH Installation
* Firewall Configuration
* Script Execution
* System Information

---

## Skills Demonstrated

* Linux System Administration
* Bash Scripting
* Package Management
* SSH Configuration
* Firewall Configuration
* Linux Command Line
* System Verification
* Server Provisioning

---

## Future Enhancements

* Automate user creation
* Generate setup logs
* Add system health checks
* Deploy the same script on an AWS EC2 Ubuntu instance

---

## Key Learning Outcomes

Through this project, I learned how to:

* Configure a Linux server from scratch
* Automate server provisioning using Bash
* Manage software packages with APT
* Configure secure remote access with SSH
* Protect a server using UFW
* Validate server configuration using Linux system commands

---



