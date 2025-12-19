# Linux User & Service Basics (Azure VM)

(Windows / Linux / Core Technical Support)

## Project Overview
This project demonstrates foundational Linux system administration skills performed in a cloud environment. The lab focuses on connecting to a Linux virtual machine from a Windows-based system, managing user accounts, and verifying system services using standard Linux commands.

This type of task is commonly performed by help desk technicians, system administrators, and cloud support engineers.

---

## Key Skills Demonstrated
- Linux user account management
- SSH connectivity and remote administration
- Basic Linux permissions and privilege escalation
- Service management using systemd
- Cross-platform support (Windows to Linux)
- Cloud virtual machine administration

---

## Environments & Technologies Used
- Microsoft Azure (Virtual Machines)
- Windows Virtual Machine (administrative workstation)
- Linux Virtual Machine (Ubuntu)
- PuTTY (SSH client)
- Secure Shell (SSH)

---

## Operating Systems Used
- Windows 10 / Windows Server
- Ubuntu Linux (20.04 / 22.04 LTS)

---

## Project Tasks Performed
- Created and connected to Azure virtual machines
- Installed PuTTY on a Windows VM
- Connected securely to a Linux VM using SSH
- Verified the logged-in Linux user
- Created a new Linux user account
- Verified user creation via system files
- Checked and validated the SSH service status

---

## Lab Workflow

### 1. Windows VM Setup
A Windows virtual machine was created in Azure to act as an administrative workstation. Remote Desktop Protocol (RDP) was used to connect to the system.
<img width="975" height="504" alt="image" src="https://github.com/user-attachments/assets/2c540400-093f-43d0-baa7-5652b43a29ca" />

📸 Screenshot: Windows VM overview

---

### 2. PuTTY Installation
PuTTY was installed on the Windows VM to enable SSH access to the Linux virtual machine.
<img width="975" height="789" alt="image" src="https://github.com/user-attachments/assets/98c7daef-27b2-464f-b115-40c2c741b4d6" />
<img width="975" height="830" alt="image" src="https://github.com/user-attachments/assets/fa1b5521-db0c-4a9b-9830-38a4afa0851a" />

📸 Screenshot: PuTTY installed on Windows VM

---

### 3. Linux VM Deployment
A Linux virtual machine (Ubuntu) was deployed in Azure with SSH (port 22) enabled for remote access.
<img width="975" height="517" alt="image" src="https://github.com/user-attachments/assets/93b15848-0472-4e30-9098-f5eee86eba4f" />

📸 Screenshot: Linux VM overview with public IP

---

### 4. SSH Connection to Linux VM
PuTTY was used to establish an SSH connection from the Windows VM to the Linux VM.
<img width="975" height="706" alt="image" src="https://github.com/user-attachments/assets/f9d206b8-552b-4ac0-aaeb-10c3ffbc4b02" />

📸 Screenshot: Successful SSH connection

---

### 5. Verify Logged-In User
whoami
Confirmed the current Linux user session.
<img width="975" height="485" alt="image" src="https://github.com/user-attachments/assets/db40abef-439e-413a-a66c-a26a82525d13" />

<img width="975" height="725" alt="image" src="https://github.com/user-attachments/assets/195a92a1-a834-49cd-ae3e-434425959d8a" />

📸 Screenshot: whoami output

### 6. Create a New Linux User
bash
sudo adduser supportuser

A new user account was created to demonstrate user management.
<img width="975" height="637" alt="image" src="https://github.com/user-attachments/assets/267b18fd-fe8d-47dc-910d-f0f8ac0eb32e" />

📸 Screenshot: User creation process

### 7. Verify User Creation
bash
cat /etc/passwd | grep supportuser
Verified that the user exists in the system.
<img width="975" height="592" alt="image" src="https://github.com/user-attachments/assets/5df41e13-d2bc-44c6-a50a-9c232dfefbee" />

📸 Screenshot: User verification output

### 8. Check SSH Service Status
bash
sudo systemctl status ssh
Confirmed that the SSH service is active, running, and enabled.
<img width="975" height="527" alt="image" src="https://github.com/user-attachments/assets/76ccdef7-42b2-4c1e-a3a0-be2b00de78fa" />

📸 Screenshot: SSH service status

