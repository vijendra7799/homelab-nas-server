# 🖥️ DIY Homelab NAS Server

> A self-hosted Home Lab NAS built by repurposing a Dell desktop into a virtualization and storage server using **Proxmox VE**.

---

## 📖 Overview

This project demonstrates the design and deployment of a **DIY Home NAS (Network Attached Storage)** and virtualization server using an old Dell desktop computer.

The server is configured with **Proxmox Virtual Environment (VE)** to host virtual machines while providing centralized storage for backups, development projects, and future self-hosted services.

The objective of this project was to build a **cost-effective**, **energy-efficient**, and **upgradeable** homelab server capable of running multiple workloads simultaneously.

---

# ✨ Features

- 💾 Centralized File Storage
- 🖥️ Proxmox Virtual Environment
- 📦 Virtual Machine Hosting
- 💽 Multiple SATA Storage Drives
- ⚡ SSD Boot Drive
- 🌐 Web-based Management Dashboard
- 📊 Storage Benchmarking
- 🔧 Modular & Upgradeable Hardware
- 🏠 Self-hosted Home Lab Platform

---

# 📸 Project Gallery

## 🖥️ NAS Hardware

<img width="4032" height="2268" alt="Inside Nas" src="https://github.com/user-attachments/assets/1692d9cb-5c7f-4094-9e94-d874a3f0604d" />

Internal hardware layout of the NAS showing the motherboard, CPU, storage drives, SATA connections, and power distribution.

---

## 💽 Storage Drives

<img width="2268" height="4032" alt="HDD" src="https://github.com/user-attachments/assets/6c0c2289-b106-4baf-a4b3-9852d741ce93" />


Dual SATA storage drives installed inside the Dell chassis.

---

## 🌐 Proxmox VE Dashboard

<img width="4032" height="2268" alt="proxmox" src="https://github.com/user-attachments/assets/b5b4a889-8c40-44a3-9038-93e3c50a1054" />


Web-based Proxmox dashboard used for virtualization and server management.

---

## 📈 Virtual Machine Monitoring

<img width="4032" height="2268" alt="Dashboard" src="https://github.com/user-attachments/assets/d1e2cedd-de58-4fd3-8d6d-491ba7a4e556" />


Real-time monitoring of CPU, memory, storage, and network usage.

---

## 🚀 SSD Benchmark

<img width="601" height="372" alt="Benchmark" src="https://github.com/user-attachments/assets/b3e2ec14-42fe-443d-9a85-7526e67c0dc3" />


Storage benchmarking performed to evaluate SSD performance before deployment.

---

# 🛠️ Hardware Specifications

| Component | Details |
|-----------|----------|
| System | Dell Desktop |
| Hypervisor | Proxmox VE 9 |
| Storage | Multiple SATA HDD/SSD |
| Boot Drive | SSD |
| Network | Gigabit Ethernet |
| Virtualization | KVM |

---

# 💻 Software Stack

- Proxmox VE
- Linux
- KVM Virtualization
- Web Management Interface

---

# 🏗️ System Architecture

```text
                    Router
                       │
                 Gigabit Ethernet
                       │
               Dell NAS Server
                       │
        ┌──────────────┴──────────────┐
        │                             │
   SSD Boot Drive             SATA Storage
        │                             │
        └──────────────┬──────────────┘
                       │
                  Proxmox VE
                       │
        ┌──────────────┴──────────────┐
        │                             │
     Ubuntu VM                  Future Virtual Machines
```

---

# ⚙️ Installation Workflow

1. Assemble Dell desktop hardware.
2. Install SSD and storage drives.
3. Connect SATA power and data cables.
4. Install Proxmox VE.
5. Configure networking.
6. Create Ubuntu virtual machine.
7. Verify storage performance.
8. Access the Proxmox web dashboard.

---

# 📊 Current Capabilities

- ✅ Virtual Machine Hosting
- ✅ Centralized Storage
- ✅ Remote Web Dashboard
- ✅ SSD Performance Benchmarking
- ✅ Multi-drive Storage Configuration

---

# 🚀 Planned Upgrades

- RAID Configuration
- Docker Containers
- Jellyfin Media Server
- Nextcloud
- Home Assistant
- Tailscale VPN
- Automatic Backups
- UPS Support
- Monitoring Dashboard (Grafana + Prometheus)

---

# 🎯 Skills Demonstrated

- Linux Administration
- Proxmox VE
- KVM Virtualization
- Computer Hardware Assembly
- Storage Configuration
- SATA Drive Installation
- Network Configuration
- Self-hosting
- Performance Benchmarking
- System Troubleshooting

---

# 👨‍💻 Author

**Sabavath Vijendra**

Mechanical Engineering Undergraduate

**Indian Institute of Technology Indore**

---

## ⭐ Support

If you found this project interesting, consider giving it a ⭐ on GitHub.
