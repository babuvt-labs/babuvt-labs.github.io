# SonarQube on Azure VM with GitHub Actions Integration

This guide outlines how to install SonarQube on an Azure Virtual Machine (VM) and configure it for automated code analysis using GitHub Actions.

## 1. Provision and Prepare Azure VM

- Create an Azure VM (Ubuntu is recommended for Docker-based install)
- Ensure the VM has at least 4 GB RAM
- Open port 9000 in the VM's Network Security Group to allow access to the SonarQube web interface
- SSH into your VM using its public IP

## 2. Install SonarQube Using Docker Compose

Update your system and install Docker and Docker Compose:

