# My Lab Setup - Phase 0

## Date
January 12, 2026.

## Objective
Setting up my first virtualization environment to learn cybersecurity hands-on. This lab is where I'll practice Linux, networking, and security tools as I work toward becoming a Cloud Security Engineer.

## Host System Specifications
|Component|Specification|
|---------|-------------|
|RAM|16GB|
|Storage|512GB SSD|
|Processor|4 cores, 8 logical processors|
| Operating System|Windows 11|

## Software Versions
|Software|Version|
|--------|-------|
|VirtualBox|7.2.4|
|VirtualBox Extension Pack|7.2.4|
|Ubuntu|24.04.3 LTS Desktop|

## Virtual Machine Configuration
**VM Name:** CloudSec-Ubuntu
|Resource|Allocation|
|RAM|4GB (4096MB)|
|vCPU|2 cores|
|Storage|25GB virtual hard drive|
|Network Mode|NAT (shares host internet)|

## Setup Process
1. Downloaded and installed VirtualBox
2. Installed Microsoft Visual C++ 2019 Redistributable (prerequisite)
3. Installed VirtualBox Extension Pack
4. Downloaded Ubuntu 24.04.3 LTS ISO from official source
5. Created new VM with professional naming convention
6. Allocated resources (RAM, CPU, storage)
7. Installed Ubuntu on the VM
8. Created user account with strong password
9. Completed initial Ubuntu setup and updates

## Challenges & Solutions
### Challenge 1: VirtualBox Installation Failed
**Problem:** Initial VirtualBox installation failed  
**Solution:** Installed Microsoft Visual C++ 2019 Redistributable package first, then restarted the installation process

### Challenge 2: Ubuntu Installation Error
**Problem:** Ubuntu installation failed with error message during first attempt  
**Solution:** Restarted the VM and ran the installer again - successful on second attempt

### Challenge 3: "Erase Disk" Warning Confusion
**Problem:** Worried the "erase disk" option would delete Windows  
**Solution:** Learned that this only affects the virtual disk (25GB virtual hard drive), not the physical laptop drive - Windows remains completely safe

## Key Learnings
- Virtual machines are isolated from the host computer; safe environment for experimentation
- Always verify download sources (important security practice)
- Installation errors are normal. Troubleshooting is part of the learning process
- VM snapshots act as restore points for experimentation
- Right Ctrl key releases mouse cursor from VM window
- Healthy security mindset: being cautious about warnings and verifying information

## Backup & Recovery
**Snapshot Taken:** Fresh Ubuntu Install
**Purpose:** Clean baseline state for future restoration if configuration breaks

## Screenshots
