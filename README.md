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

<a href="images/inside_nas.jpg">
<img src="images/inside_nas.jpg" width="900">
</a>

Internal hardware layout of the NAS showing the motherboard, CPU, storage drives, SATA connections, and power distribution.

---

## 💽 Storage Drives

<a href="images/hdd_mount.jpg">
<img src="images/hdd_mount.jpg" width="700">
</a>

Dual SATA storage drives installed inside the Dell chassis.

---

## 🌐 Proxmox VE Dashboard

<a href="images/proxmox_dashboard.jpg">
<img src="images/proxmox_dashboard.jpg" width="900">
</a>

Web-based Proxmox dashboard used for virtualization and server management.

---

## 📈 Virtual Machine Monitoring

<a href="images/vm_dashboard.jpg">
<img src="images/vm_dashboard.jpg" width="900">
</a>

Real-time monitoring of CPU, memory, storage, and network usage.

---

## 🚀 SSD Benchmark

<a href="images/benchmark.png">
<img src="images/benchmark.png" width="700">
</a>

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
