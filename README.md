# 🔐 Cybersecurity Lab Setup: Kali Linux on a Virtual Machine

**A hands-on build of an isolated virtual lab for ethical hacking and penetration-testing practice.**

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-000000?style=flat-square&logo=kalilinux&logoColor=white)
![Virtualization](https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square)
![Networking](https://img.shields.io/badge/Skill-Networking-404040?style=flat-square)

---

## 📌 Project Overview

In this project I built a virtual cybersecurity lab on my own computer. The lab runs **Kali Linux** inside a **virtual machine (VM)**, so I can practice security tools safely, without touching my main operating system.

I set up the VM's network, gave Kali a working IP configuration, checked that the connection works, allocated resources (RAM and storage), and saved a **snapshot** as a clean starting point.

---

## 🎯 Objectives

- Install virtual machine software on my computer
- Configure the virtual network settings
- Download and extract Kali Linux
- Add Kali Linux to the virtual machine
- Configure the IP settings of the Kali VM
- Test that the network connection works
- Set the VM's hardware specs (RAM, storage, processors)
- Take a snapshot of the finished machine

---

## ⚙️ Lab Configuration

| Component | Configuration |
|---|---|
| Host OS | {{your Windows/Linux version}} |
| Virtualization software | {{VirtualBox / VMware, with version}} |
| Guest OS | Kali Linux {{version}} |
| VM RAM | {{e.g. 2048 MB}} |
| VM Storage | {{e.g. 80 GB}} |
| VM Processors | {{e.g. 2 CPUs}} |
| Network mode | {{NAT / NAT Network / Bridged}} |
| Kali IP address | {{your IP}} |
| Gateway | {{your gateway}} |
| DNS | {{your DNS}} |

---

## 🪜 Setup Procedure

### Step 1. Install the virtual machine software

I downloaded and installed the virtualization software that runs the lab.

![Step 1](screenshots/1-vm-software-installed.png)

### Step 2. Configure the network settings

Before adding Kali, I configured the virtual network so the VM can connect properly.

![Step 2](screenshots/2-network-settings.png)

### Step 3. Download and extract Kali Linux

I downloaded Kali Linux from the official website and extracted the files.

![Step 3](screenshots/3-kali-downloaded-extracted.png)

### Step 4. Add Kali Linux to the virtual machine

I imported the extracted Kali machine into the virtualization software.

![Step 4](screenshots/4-kali-added.png)

### Step 5. Configure the IP settings

I set up the IP configuration of the Kali VM (IP address, subnet mask, gateway and DNS).

![Step 5](screenshots/5-ip-configuration.png)

### Step 6. Test the network connection

I checked that the VM is connected and the network is working, using ping.

![Step 6](screenshots/6-network-test.png)

### Step 7. Set the VM specs

I decided how many resources the VM gets: RAM, storage and processors.

![Step 7](screenshots/7-vm-specs.png)

### Step 8. Take a snapshot

After everything was working, I took a snapshot. This is my clean baseline: if I break something later, I can restore the machine in one click.

![Step 8](screenshots/8-snapshot.png)

---

## 🔎 Verification

| Test | Command | Expected result |
|---|---|---|
| Check IP address | `ip a` | Correct IP shown |
| Test connectivity | `ping <gateway or 8.8.8.8>` | Successful replies |
| Snapshot | Restore snapshot | Clean machine restored |

---

## 💡 What I Learned

- How to create and configure a virtual machine from scratch
- How virtual network settings affect a VM's connection
- How to check IP configuration and test connectivity
- Why a clean snapshot is useful before experimenting
- Why documenting each step matters in cybersecurity work

---

## 🚀 Next Steps

- Add a vulnerable target machine to the lab
- Practice network scanning and reconnaissance in the isolated environment
- Explore more tools that come with Kali Linux

---

## 🔐 Ethical Use

This lab is for **education only**. Only test systems that you own or have clear permission to test.

---

## 🔗 Tools & Resources

- **Kali Linux:** https://www.kali.org/get-kali/
- {{Virtualization software download link}}

---

## 👤 Author

**Armaghan Arshad**
Cybersecurity student, University of Haripur

LinkedIn: https://www.linkedin.com/in/armaghan-arshad-b3345828b
