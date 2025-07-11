# ubuntu-vm-setup

This project guides you through the step-by-step process of installing **Ubuntu 24.04 LTS** on **Oracle VirtualBox** using a **Windows 11** host system. It's ideal for users who want to set up a Linux environment for testing or developement

---

## Project Overview

- Set up VirtualBox on Windows 11
- Download the Ubuntu 24.04 LTS ISO
- Create a virtual machine (VM)
- Configure system settings (RAM, disk, etc.)
- Install and boot into Ubuntu
- Finalize VM setup for everyday use

---

## Prerequisites

- Windows 11 PC with internet access
- Oracle VirtualBox 
- Ubuntu 24.04 LTS ISO

---

## Installation Steps

### Step 1: Download and Install VirtualBox
1. Visit [virtualbox.org](https://www.virtualbox.org/) and download VirtualBox for Windows
2. Install VirtualBox using default settings

### Step 2: Download Ubuntu 24.04 LTS ISO
- Get the ISO from the [Ubuntu official site](https://ubuntu.com/download/desktop)

### Step 3: Create a Virtual Machine in VirtualBox
<img width="953" height="500" alt="Screenshot 2025-07-07 205430" src="https://github.com/user-attachments/assets/d9ef1829-b27e-4974-aaf2-8732d7576510" />


- Choose:
  - **Name**: Any name for your virtual
  - **ISO Image**: Choose the Ubuntu 24.04 LTS ISO file you downloaded
  - **Type**: Linux
  - **Version**: Ubuntu (64-bit)
 
<img width="713" height="398" alt="Screenshot 2025-07-07 205510" src="https://github.com/user-attachments/assets/02b146df-681a-482e-acc9-bda11119d86b" />


### Step 4: Allocate Memory (RAM) and Proccessors
- Recommended: **2048 MB (2 GB)** or more and 4 CPus or more

<img width="706" height="400" alt="Screenshot 2025-07-07 205751" src="https://github.com/user-attachments/assets/1ec70611-b227-4920-ba8e-38746a1cd3e8" />

### Step 5: Create Virtual Hard Disk
- Allocate **at least 25 GB** of space
- Remember this is **Dynamically allocated** it won't use all the space you chose

<img width="710" height="401" alt="Screenshot 2025-07-07 205952" src="https://github.com/user-attachments/assets/d1c6de56-a287-4231-a559-d7dfae079d98" />

### Step 6: Summary of selections
<img width="705" height="402" alt="Screenshot 2025-07-07 210020" src="https://github.com/user-attachments/assets/88fc98cb-6199-48be-bb08-35f8e10c8ab0" />

### Step 7: Install Ubuntu
1. Start the VM and select "Install Ubuntu"
2. Follow the on-screen instructions

<img width="1281" height="872" alt="Screenshot 2025-07-07 214134" src="https://github.com/user-attachments/assets/72eca885-66d4-479f-abdb-f91276558005" />

<img width="957" height="675" alt="Screenshot 2025-07-07 215440" src="https://github.com/user-attachments/assets/ecea207b-81ee-4bbf-9875-45203119357b" />

<img width="1279" height="865" alt="Screenshot 2025-07-07 215552" src="https://github.com/user-attachments/assets/5009fcb7-3c45-4f78-8a91-1f2db2e547a2" />

<img width="1279" height="865" alt="Screenshot 2025-07-07 215552" src="https://github.com/user-attachments/assets/ca16340d-b75d-4fda-8939-8718b0b83bcd" />

Choose credentials
<img width="955" height="670" alt="Screenshot 2025-07-10 224849" src="https://github.com/user-attachments/assets/2b5cd359-1404-4ced-8fd8-33244a273fe0" />

Complete installation and reboot

Log in
<img width="1271" height="870" alt="Screenshot 2025-07-07 221309" src="https://github.com/user-attachments/assets/cdfacf7a-c900-4e4f-a20b-f99fec76e5dd" />

Now Ubuntu is installed on your host os
<img width="1275" height="882" alt="Screenshot 2025-07-07 222458" src="https://github.com/user-attachments/assets/03747697-cb28-4399-82fc-62b28c8837cb" />

---

## 🔧 Optional 
- Enable **Shared Clipboard** and **Drag & Drop** between host and guest.

<img width="958" height="499" alt="Screenshot 2025-07-07 214728" src="https://github.com/user-attachments/assets/e91d2134-db99-48b5-b2db-f25c9d6bab23" />

## Author
**Jhalil Danilo Roman Soria**  
