# Linux User & Service Basics

*(Linux / System Administration / Core Technical Support)*

## Project Overview

This project demonstrates fundamental Linux system administration tasks commonly performed in entry-level technical support and junior system administrator roles. The lab focuses on managing Linux users, verifying permissions, and controlling system services within a cloud-hosted Linux virtual machine.

These tasks reflect real-world Linux support responsibilities such as onboarding users, managing access, and ensuring system services are running properly.

---

## Key Skills Demonstrated

- Linux user account management  
- Password and group administration  
- File and directory permission awareness  
- Service management using systemd  
- Command-line troubleshooting  
- Linux system verification

---

## Environment & Technologies Used

- **Cloud Platform:** Microsoft Azure (Virtual Machine)  
- **Operating System:** Linux (Ubuntu)  
- **Access Method:** SSH  
- **Service Manager:** systemd  

---

## Tools & Commands Used

- `useradd`
- `passwd`
- `usermod`
- `groups`
- `id`
- `ls -l`
- `systemctl`
- `whoami`
- `hostname`
- `uptime`

---

## Tasks Performed

- Created a new Linux user account  
- Assigned and updated user passwords  
- Verified group membership and permissions  
- Switched users to confirm access  
- Checked file and directory permissions  
- Verified system identity and uptime  
- Started, stopped, and validated a Linux service  
- Confirmed service status using systemctl  

---

## Linux Administration Workflow

1. Connected to the Linux VM using SSH  
2. Verified system identity and current user  
3. Created a new user account  
4. Set and managed user credentials  
5. Validated user group membership  
6. Reviewed file and directory permissions  
7. Managed a system service (start / stop / status)  
8. Confirmed service health and system stability  

---

## Screenshots & Explanations


SSH connection to Azure Linux VM  

System identity verification (`whoami`, `hostname`)  

User account creation  

Password assignment  

Group membership verification  

File and directory permission check  

Service status check using `systemctl`  

Service start and validation  

Each screenshot includes command output to verify successful completion of each administrative task.

---

## Outcome

- Successfully created and managed Linux user accounts  
- Verified permissions and access control  
- Ensured critical services were running properly  
- Demonstrated core Linux administration skills applicable to help desk and junior system administrator roles  

---

## Why This Project Matters

Linux is widely used across enterprise environments, cloud platforms, and server infrastructure. This project demonstrates the ability to confidently manage Linux users and services — a critical skill for technical support, systems administration, and cloud support roles.
