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

**FANSPEED-CONTROL-THINKPAD-CLI** is a blazing-fast 🏎️, no-nonsense CLI tool for controlling and monitoring ThinkPad fan speed on Linux systems.  
Perfect for power users, sysadmins, and anyone who wants more control or silence from their beloved ThinkPad!

---

## ✨ Features

- 🌡️ **Monitor Fan Speed**: View real-time fan RPM and temperature sensors.
- ⚡ **Control Fan Modes**: Set manual, automatic, or custom fan speed profiles.
- 🖥️ **ThinkPad Specific**: Optimized for Lenovo ThinkPad models on Linux.
- 🛠️ **Easy CLI Usage**: No GUI, no bloat—just pure terminal power.
- 🏁 **Boot-Time Fan Level**: Start your ThinkPad with a pre-set fan speed (like a server!) for instant cooling, noise, or performance.
- 🔒 **Open Source (GPLv3)**: Fork, hack, and contribute freely!

---

## 🚀 Quickstart

```bash
# Clone the repo
git clone https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI.git
cd FANSPEED-CONTROL-THINKPAD-CLI

# Make the script executable
chmod +x fanspeed.sh

# Run with sudo (required for hardware control)
sudo ./fanspeed.sh status
sudo ./fanspeed.sh set 3500    # Set fan speed to 3500 RPM
```

---

## 📦 Dependencies

This tool relies on a few Linux dependencies to interact with ThinkPad hardware:

- **thinkfan** (for fan control backend)
- **acpi** or **lm-sensors** (for temperature readings)
- **bash** (for scripting)
- **systemd** (for boot-time configuration, optional)
- **root privileges** (required for direct hardware access)

Install with:
```bash
sudo apt install thinkfan lm-sensors acpi bash
```

---

## ⚡ Boot-Time Fan Control

Want your ThinkPad to behave like a server, starting with fans at a specified RPM?  
**FANSPEED-CONTROL-THINKPAD-CLI** provides a feature to set your desired fan speed at boot.  
You can enable this by adding a systemd service or placing the CLI command in your boot scripts.

**Example systemd service:**
```ini
[Unit]
Description=Set ThinkPad Fan Speed at Boot

[Service]
Type=oneshot
ExecStart=/usr/local/bin/fanspeed.sh set 3500

[Install]
WantedBy=multi-user.target
```
Enable with:
```bash
sudo systemctl enable fanspeed-at-boot.service
```

---

## 📖 Usage

```bash
./fanspeed.sh status        # Show current fan speed and temperatures
./fanspeed.sh set <rpm>     # Set fan speed manually
./fanspeed.sh auto          # Enable automatic fan control
./fanspeed.sh boot <rpm>    # Configure boot-time fan speed
./fanspeed.sh help          # Show all commands
```

---

## 🛡️ License

This project is licensed under the [GNU GPL v3](LICENSE).

---

## 🌟 Contributing

Pull requests, issues, and ideas are **welcome**!  
Check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 💬 Support & Community

- [Open Issues](https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI/issues)
- [Discussions](https://github.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI/discussions)
- [Linux ThinkPad Community](https://reddit.com/r/thinkpad)

---

## 🧑‍💻 Authors & Credits

- [LINUX-OASIS](https://github.com/LINUX-OASIS) — Maintainer & Lead Developer

---

## 🌈 Tech Flair

> ✨ Bash scripting | 🖥️ Linux hardware | 🚥 Fan control | 💻 ThinkPad hacking | 🎉 Open source

---

## 📸 Screenshots

![Terminal Demo](https://raw.githubusercontent.com/LINUX-OASIS/FANSPEED-CONTROL-THINKPAD-CLI/main/docs/demo.png)

---

## ⭐️ If you like this project, give it a star!
