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

**FANSPEED-CONTROL-THINKPAD-CLI** a no-nonsense CLI tool for controlling and monitoring ThinkPad fan speed on Linux systems.  
Perfect for power users, sysadmins, and anyone who wants more control, perfrmance or silence from their beloved ThinkPad!

---

## ✨ Features

- 🌡️ **Monitor Fan Speed**: View real-time fan RPM and temperature sensors.
- ⚡ **Control Fan Modes**: Set manual, automatic, or custom fan speed profiles.
- 🖥️ **ThinkPad Specific**: Optimized for Lenovo ThinkPad models on Linux.
- 🛠️ **Easy CLI Usage**: No GUI, no bloat—just pure terminal power.
- 🔒 **Open Source (GPLv3)**: Fork, hack, and contribute freely!

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
sudo ./custom-FANSPEED-CONTROL-THINKPAD
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

## 📖 Usage

```bash
./custom-FANSPEED-CONTROL-THINKPAD
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
