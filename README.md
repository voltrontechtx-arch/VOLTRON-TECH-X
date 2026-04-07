# 🚀 VOLTRON TECH ULTIMATE

**Version:** 10.4 (Falcon Style Edition)  
**Author:** Voltron Tech  
**Platform:** Linux (Ubuntu/Debian)

> A modern, powerful script for managing SSH, VPN, and remote access systems. Built for network professionals and VPS owners.

---

## 📌 Table of Contents

- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Menu Navigation](#-menu-navigation)
- [Protocols Supported](#-protocols-supported)
- [Speed Boosters](#-speed-boosters)
- [Screenshots](#-screenshots)
- [Uninstallation](#-uninstallation)
- [License](#-license)

---

## ✨ Features

### 👤 User Management (Falcon Style)
| Feature | Description |
|---------|-------------|
| Create User | Create new SSH users easily |
| Delete User | Delete single or multiple users at once |
| Edit User | Change password, expiry, limit, bandwidth |
| Lock/Unlock | Lock or unlock user accounts |
| List Users | View all users with their status |
| Bulk Create | Create multiple users at once (1-100) |
| Bandwidth View | Monitor data usage per user |

### 🔌 Protocols & Panels
| Protocol | Port | Status |
|----------|------|--------|
| SSH Direct | 22 | ✅ |
| DNSTT (SlowDNS) | 5300 | ✅ |
| V2Ray (Xray) | 8787 | ✅ |
| BadVPN (UDPGW) | 7300 | ✅ |
| UDP-Custom | 36712 | ✅ |
| SSL Tunnel (HAProxy) | 444 | ✅ |
| VOLTRON Proxy | 8080 | ✅ |
| Nginx Proxy | 80/443 | ✅ |
| ZiVPN | 5667 | ✅ |
| X-UI Panel | - | ✅ |
| DT Proxy | - | ✅ |

### ⚡ Speed Boosters (7 Levels)
| Level | Buffer | Speed |
|-------|--------|-------|
| Standard | 32MB | 10-15 Mbps |
| Medium | 64MB | 15-20 Mbps 🚀 |
| High | 128MB | 20-25 Mbps 🚀🚀 |
| Ultra | 256MB | 25-35 Mbps 🚀🚀🚀 |
| Extreme | 512MB | 35-50 Mbps 💥💥💥 |
| Ultra Plus | 768MB | 40-60 Mbps 🚀🚀🚀🚀 |
| Extreme Plus | 1GB | 60-100 Mbps 💥💥💥💥💥 |

### 🛠️ System Utilities
- **Auto HTML Banner** - Self-generating banner per user (Falcon Style)
- **SSH Banner** - Custom plain text banner
- **Backup & Restore** - Save and restore user data
- **Auto Reboot** - Automatic daily reboot at 00:00
- **Cache Cleaner** - Automatic nightly cache cleanup
- **Traffic Monitor** - Real-time network usage monitoring
- **Connection Forcer** - Control connections per IP

---

## 📋 Requirements

| Requirement | Specification |
|-------------|---------------|
| OS | Ubuntu 20.04/22.04/24.04 or Debian 11/12 |
| RAM | Minimum 1GB (2GB+ recommended) |
| Storage | Minimum 10GB free space |
| Access | Root access required |
| Internet | Stable connection for downloads |

---

## 🚀 Installation

### One-Line Installer

```bash
bash <(curl -sL https://raw.githubusercontent.com/VOLTRON-TECH-X/VOLTRON-TECH-X/refs/heads/main/main.sh)
```

Installation Steps

1. Login as root
   ```bash
   sudo -i
   ```
2. Run the installer
   ```bash
   bash <(curl -sL https://raw.githubusercontent.com/VOLTRON-TECH-X/VOLTRON-TECH-X/refs/heads/main/main.sh)
   ```
3. Script starts automatically - No additional steps required
4. During DNSTT installation - You will choose:
   · Custom domain (your own domain)
   · Auto-generate domain (using deSEC DNS)

---

🎮 Menu Navigation

Main Menu Structure

```
╔═══════════════════════════════════════════════════════════════╗
║           🔥 VOLTRON TECH ULTIMATE v10.4 🔥                    ║
║        SSH • DNSTT • V2RAY • BADVPN • UDP • SSL • ZiVPN        ║
╠═══════════════════════════════════════════════════════════════╣
║  Server IP: xxx.xxx.xxx.xxx                                   ║
║  Location: City, Country                                      ║
║  ISP: Internet Service Provider                               ║
╚═══════════════════════════════════════════════════════════════╝

═══════════════════════════════════════════════════════════════
                    👤 USER MANAGEMENT
═══════════════════════════════════════════════════════════════
  1) Create New User          6) Unlock User
  2) Delete User              7) List Users
  3) Edit User                8) Renew User
  4) Lock User                9) Cleanup Expired
  5) Bulk Create Users       10) 📊 View Bandwidth
                             11) 📱 Generate Client Config
```

Protocol Menu

· Select 12 to enter Protocol & Panel Management
· Then choose the protocol you want to install or manage

---

📸 Screenshots

User List View

```
=========================================================================================
USERNAME          | EXPIRES     | CONNS      | BANDWIDTH       | STATUS
-----------------------------------------------------------------------------------------
john              | 2026-04-23  | 1 / 2      | 1.2/10GB        | 🟢 Active
jane              | 2026-05-01  | 0 / 1      | Unlimited       | 🟢 Active
trial_abc12       | 2026-04-10  | 0 / 1      | 0.5/5GB         | 🗓️ Expired
=========================================================================================
```

Auto HTML Banner Sample

```
===============================

WELCOME TO VOLTRON TECH

===============================

🇿🇦 SOUTH AFRICA SERVER 🇿🇦

📱 HALOTEL UNLIMITED

      ✨ ACCOUNT STATUS ✨      

👤 Username   : john
📅 Expiration : 2026-04-23 (30d 0h left)
📊 Bandwidth  : 1.2/10 GB used | 8.8 GB left
🔌 Sessions   : 1/2

===============================
```

---

🔧 Protocols Installation Guide

DNSTT (SlowDNS)

1. In Protocol Menu, select 4
2. Select 1 Install DNSTT
3. Choose domain (auto or custom)
4. Choose speed booster level (1-7)
5. Wait for installation to complete

V2Ray

1. In Protocol Menu, select 6
2. Select 1 Install V2RAY
3. V2Ray will be installed on port 1080 (localhost)

X-UI Panel

1. In Protocol Menu, select 10
2. Select 1 Install
3. Follow the X-UI script instructions

---

🗑️ Uninstallation

⚠️ WARNING: This will delete the script and all user data!

1. In Main Menu, select 99
2. Type YES to confirm
3. Wait for uninstallation to complete

```bash
# After uninstallation, the script will delete itself
# The 'menu' command will no longer work
```

---

❓ Troubleshooting

Issue: Banner not showing on HTTP Custom

Solution:

1. Go to Auto HTML Banner Menu (Option 17)
2. Verify banner is ENABLED
3. Check if limiter service is running:
   ```bash
   systemctl status voltrontech-limiter
   ```

Issue: Bandwidth not showing actual usage

Solution:

· Wait 15-30 seconds for limiter to update data
· Limiter runs every 15 seconds

Issue: Connection count is incorrect

Solution:

· Verify user is connected via SSH tunnel
· Connection count only counts SSH sessions

---

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

⭐ Show Your Support

If this script helped you, don't forget to give it a star on GitHub!

https://img.shields.io/github/stars/VOLTRON-TECH-X/VOLTRON-TECH-X.svg?style=social

---

Made with 🔥 by Voltron Tech
