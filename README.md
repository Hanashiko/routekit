# routekit

**routekit** is a powerful, colorful, and user-friendly command-line utility for visualizing and managing Linux routing tables, rules, and network interfaces. It provides human-readable output with enhanced formatting, ideal for both sysadmins and power users.

![License](https://img.shields.io/github/license/hanashiko/routekit)
![AUR](https://img.shields.io/aur/version/routekit?color=blue)
![Platform](https://img.shields.io/badge/platform-Linux-green)
![Python](https://img.shields.io/badge/python-3.6%2B-blue)

## Features

- View routing tables (including custom ones).
- how advanced routing rules.
- Get detailed route resolution to a specific destination.
- Add and ➖ remove routes (requires root).
- List available network interfaces and IP addresses.
- Terminal colorized output for readability.
- Packaged as a full CLI tool.
- Available on the AUR: [`routekit`](https://aur.archlinux.org/packages/routekit)

---

## Installation

### From AUR (Recommended for Arch Linux users)

```bash
yay -S routekit
```

### Manual Installation

Clone the repository and install manually:
```bash
git clone https://github.com/hanashiko/routekit.git
cd routekit
sudo install -Dm755 routekit /usr/local/bin/routekit
```