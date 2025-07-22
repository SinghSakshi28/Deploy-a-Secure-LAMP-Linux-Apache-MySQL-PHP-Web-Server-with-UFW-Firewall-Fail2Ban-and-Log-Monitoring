# 🚀 Deploy a Secure LAMP (Linux, Apache, MySQL, PHP) Web Server with UFW Firewall, Fail2Ban, and Log Monitoring


This project provides a step-by-step guide to set up a secure LAMP stack on Ubuntu Server with basic monitoring, log auditing, and security hardening using UFW and Fail2Ban.

---

## 📌 What You Will Learn

| Skill          | Description                                                 |
|----------------|-------------------------------------------------------------|
| Linux Basics   | SSH, directory management, user & permission handling       |
| Web Hosting    | Install & configure Apache, MySQL, PHP                      |
| Security       | Set up UFW, Fail2Ban, and disable root login                |
| Monitoring     | Use logwatch, grep, awk, and cron jobs                      |
| Hardening      | Change SSH port, basic system hardening                     |

---

## 🛠️ Tools & Technologies

- **Operating System:** Ubuntu Server (VMware/VirtualBox or Cloud)
- **Web Stack:** Apache, MySQL, PHP (LAMP)
- **Security Tools:** UFW Firewall, Fail2Ban
- **Monitoring Tools:** Logwatch, cron jobs, bash scripting, htop/top

---

## 🧩 Step-by-Step Deployment Guide

### 🔧 Part 1: Setup LAMP Stack

1. **Install Ubuntu Server** on VMware or any virtual environment.
2. **Update packages:**
   ```bash
   sudo apt update && sudo apt upgrade -y
