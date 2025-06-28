# routekit

**RouteKit** is a visual and user-friendly CLI utility for managing and inspecting Linux routing tables and rules. It wraps the powerful `ip route`, `ip rule`, and `ip link` commands into a colorful and structured interface, making it easier to understand and work with complex routing configurations.

## Features

- Display routing tables with color-coded, readable output
- Inspect advanced routing rules
- Show detailed `ip route get` path to any destination
- List network interfaces with state and IP addresses
- Add or delete routes from the system
- Minimal dependencies: just Python and `iproute2`

---

## 🧰 Requirements

- Python 3.6+
- Linux system with `iproute2` installed
- Root privileges for `add` and `del` route operations

---

## Installation

### Option 1: Clone & Run

```bash
git clone https://github.com/youruser/routekit.git
cd routekit
chmod +x routekit
sudo ./routekit show
```

### Option 2: AUR (for Arch Linux users)

```bash
yay -S routekit
```

---

## Usage

