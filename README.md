# FANSPEED-CONTROL-THINKPAD-CLI 🚀🌬️

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![Linux](https://img.shields.io/badge/OS-Linux-darkgreen?logo=linux)](https://www.kernel.org/)
[![Made with Bash](https://img.shields.io/badge/made%20with-Bash-4EAA25?logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI/pulls)
[![Issues](https://img.shields.io/github/issues/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI?logo=github)](https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI/issues)
[![Stars](https://img.shields.io/github/stars/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI?style=social)](https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI)](https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI/commits/main)
[![Code Sparkle](https://img.shields.io/badge/code-sparkles-FFD700?style=flat)](https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI)

---

## 💡 Overview

**FANSPEED-CONTROL-THINKPAD-CLI** is a lightweight, no-nonsense CLI tool for **controlling and monitoring ThinkPad fan speed on Linux systems**.  
Unlike raw commands or manual thinkfan setups, this project focuses on **ease of use**: no typing, no config file tinkering — just arrow keys and enter.  
Perfect for power users, sysadmins, and anyone who wants quick control, performance, or silence from their beloved ThinkPad!

---

## ✨ Features

- 🌡️ **Monitor Fan Speed**: View real-time fan RPM and temperature sensors.
- ⚡ **Control Fan Modes**: Set manual, automatic, or custom fan speed profiles.
- 🖥️ **ThinkPad Specific**: Optimized for Lenovo ThinkPad models on Linux.
- 🛠️ **Easy CLI Usage**: No GUI, no bloat—just pure terminal power.
- 🔒 **Open Source (GPLv3)**: Fork, hack, and contribute freely!

---

## 🤔 Why not just use thinkfan or echo commands?

Yes, you *can* configure **thinkfan** manually or echo values into `/proc/acpi/ibm/fan` — but that requires:  

- 📚 Knowing the right backend commands & syntax  
- 📝 Manually editing config files  
- ⌨️ Typing commands every time you want a change  

**FANSPEED-CONTROL-THINKPAD-CLI** automates all of that into a simple, menu-driven CLI:  

- ✅ No need to memorize commands  
- ✅ No manual config tinkering  
- ✅ Just navigate with arrow keys & press enter  

It’s about **convenience + accessibility**. Power users still get full control, but anyone can now tweak fan behavior instantly without diving into configs or documentation.  

---

## Tested Linux Distributions

This tool has been tested and verified to work on the following Linux distributions:

- **Debian**
- **Ubuntu**
- **Linux Mint**

> **Note:** The tool is primarily tested on Debian and Debian derivatives. It is expected to work correctly on any Linux distribution that uses the **APT package manager**, including other Debian-based distros.

If you encounter issues on other APT-based distributions, please report them!

---

## 🚀 Quickstart

```bash
# Clone the repo
git clone https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI.git
cd FANSPEED-CONTROL-THINKPAD-CLI

# Make the script executable
chmod +x custom-FANSPEED-CONTROL-THINKPAD

# Run with sudo (required for hardware control)
sudo ./custom-FANSPEED-CONTROL-THINKPAD
