Cybersecurity Lab Setup

📌 Project Overview

This project focuses on building a controlled virtual cybersecurity laboratory using VirtualBox and Kali Linux.

The lab provides an isolated environment for practicing cybersecurity concepts, network analysis, reconnaissance, vulnerability assessment, and security-tool usage in a safe and repeatable manner.

A private NAT Network is configured to allow additional virtual machines to be connected in the future for authorized security testing and hands-on cybersecurity exercises.

🎯 Objectives

The main objectives of Week 1 were to:

Install and configure Oracle VirtualBox.

Install and configure Kali Linux as a virtual machine.

Create a private NAT Network for the lab environment.

Configure network connectivity within Kali Linux.

Verify the assigned IP address and network configuration.

Test gateway and Internet connectivity.

Verify DNS resolution.

Create a clean VM snapshot for recovery.

Document the complete laboratory setup.

Prepare the environment for future cybersecurity projects.

🛡️ Lab Purpose

The laboratory is designed as a controlled learning environment for practicing cybersecurity concepts and authorized security testing.

Future exercises may include:

🔎 Network reconnaissance

🌐 Network and port scanning

🛡️ Vulnerability assessment

📡 Packet analysis

🌍 Web security testing

🧪 Security-tool experimentation

💻 Practice with intentionally vulnerable systems

⚠️ Ethical & Legal Notice:
All security testing performed in this laboratory must be limited to systems that are owned by the learner or for which explicit authorization has been provided. Cybersecurity tools and techniques should never be used against unauthorized systems.


Lab Architecture


<img width="1919" height="997" alt="image" src="https://github.com/user-attachments/assets/0fad236f-78b8-42ff-a51b-a513ab28168f" />

Additional target machines can be added to the same virtual network in future projects.


🖥️ Lab Environment

Component	Configuration

Host Operating System	Windows 11

Processor	Intel Core i3 / i5

RAM	16 GB

Storage	512 GB SSD

Virtualization Platform	Oracle VirtualBox

Guest Operating System	Kali Linux 2026.2

Network Type	NAT Network

Network CIDR	10.0.0.0/24

Kali Linux IP	10.0.0.2/24

Gateway	10.0.0.1

DNS Server	8.8.8.8


🌐 Network Configuration

The Kali Linux virtual machine is connected to a dedicated NAT Network using the 10.0.0.0/24 private address range.

The basic network configuration is:

Network     : 10.0.0.0/24
Gateway     : 10.0.0.1
Kali VM     : 10.0.0.2/24
DNS         : 8.8.8.8

This configuration provides a controlled virtual networking environment while allowing the lab to be expanded with additional virtual machines in future exercises.

:

🧰 Tools & Resources

The following tools and resources were used to build the virtual cybersecurity laboratory:

Tool / Resource	Purpose

7-Zip	Extracting and managing compressed files
Oracle VirtualBox	Creating and managing virtual machines
Kali Linux	Cybersecurity learning and testing environment
NAT Network	Providing isolated virtual network connectivity
Linux Networking Tools	Configuring and troubleshooting network connectivity
VirtualBox Snapshots	Creating recovery points for the VM

🔗 Official Resources

7-Zip: 7-Zip Downloads
Oracle VirtualBox: VirtualBox Downloads
Kali Linux: Kali Linux Downloads


🛡️ Lab Setup Workflow

The Week 1 laboratory setup was completed through six main stages:

1️⃣ Install 7-Zip

Install 7-Zip to extract and manage the Kali Linux files required for the virtual machine setup.

2️⃣ Install Oracle VirtualBox

Install Oracle VirtualBox as the virtualization platform used to create and manage the Kali Linux virtual machine.

3️⃣ Configure the NAT Network

Create and configure a private NAT Network using the 10.0.0.0/24 address range.

4️⃣ Download & Import Kali Linux

Download the Kali Linux virtual machine image and import it into VirtualBox.

5️⃣ Configure Kali Linux Networking

Configure and verify the Kali Linux network settings, including the IPv4 address, gateway, and DNS configuration.

6️⃣ Create a VM Snapshot

Create a clean snapshot after completing the initial configuration so the laboratory can be restored to a known working state when required.

📌 Week 1 Setup Flow
7-Zip
   ↓
VirtualBox Installation
   ↓
NAT Network Configuration
   ↓
Kali Linux Import
   ↓
IPv4 & Network Configuration
   ↓
Connectivity Verification
   ↓
Clean VM Snapshot


🛡️ Phase 01 — Lab Setup


1️⃣ 7-Zip Installation
What I Did

Installed 7-Zip to extract and manage the compressed virtual machine files required for the cybersecurity laboratory.

Why

Kali Linux virtual machine files are commonly distributed in compressed formats. 7-Zip was used to extract these files and prepare them for import into Oracle VirtualBox.

Result

✅ 7-Zip was successfully installed and verified.

✅ Required virtual machine files were extracted successfully.

✅ The Kali Linux VM files were prepared for the next stage of the laboratory setup.
