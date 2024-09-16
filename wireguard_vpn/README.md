# WireGuard VPN Server Installation

WireGuard® is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Compatibility](#compatibility)
- [Installation Steps](#installation-steps)
  - [Update System](#update-system)
  - [Download and Run Installation Script](#download-and-run-installation-script)
- [Post-Installation](#post-installation)
- [Features](#features)
- [Additional Notes](#additional-notes)
- [License](#license)
- [Contributing](#contributing)

## Prerequisites

- A server with a public IP address
- Root or sudo privileges
- Basic knowledge of command line interface

## Compatibility

| Distribution       | Support |
|--------------------|---------|
| AlmaLinux 8        | ✅      |
| Amazon Linux 2     | ✅ 🤖   |
| Arch Linux         | ✅      |
| CentOS 7           | ✅ 🤖   |
| CentOS Stream >= 8 | ✅ 🤖   |
| Debian >= 10       | ✅ 🤖   |
| Fedora >= 35       | ✅ 🤖   |
| Oracle Linux 8     | ✅      |
| Rocky Linux 8      | ✅      |
| Ubuntu >= 18.04    | ✅ 🤖   |

## Installation Steps

### Update System
```bash
sudo apt update && sudo apt upgrade -y
```

### Download and Run Installation Script
```bash
curl -O https://github.com/Shwet-Kamal-Singh/vpn/blob/main/wireguard_vpn/wireguard_script.sh
```
```bash
chmod 744 wireguard_script.sh
```
```bash
bash wireguard_script.sh
```

Follow the on-screen instructions to complete the installation.

## Post-Installation

- Client configuration files (.conf) will be in your home directory.
- Download these files to connect using your preferred WireGuard client.
- To create a new account, rerun the script and follow the prompts.
- Options include adding or removing a client, or uninstalling WireGuard.

## Features

- **Speed**: Exceptional performance due to modern, streamlined codebase.
- **Simplicity**: Easy setup and user-friendly configuration.
- **Security**: Utilizes cutting-edge cryptography protocols.
- **Open-Source**: Transparent and community-scrutinized.
- **Cross-Platform**: Runs on Windows, macOS, Linux, Android, and iOS.
- **Lightweight**: Small code footprint, resource-efficient.
- **Modern Design**: Built with modern principles, avoiding legacy issues.
- **Future-Proof**: Adaptable to latest cryptography advancements.
- **Active Development**: Constant improvements and new features.
- **Privacy-Focused**: Does not collect or store sensitive data.

## Additional Notes

- For detailed configuration options, refer to the [official WireGuard documentation](https://www.wireguard.com/).
- Follow security best practices when setting up your VPN server.
- Regularly update your WireGuard installation for the latest features and security patches.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Shwet-Kamal-Singh/vpn/blob/main/LICENSE) file for details.

![Original Creator](https://img.shields.io/badge/Original%20Creator-Shwet%20Kamal%20Singh-blue)

![License](https://img.shields.io/badge/License-MIT-green)

## Contributing

Contributions to improve this script are welcome. Please fork the repository, create a new branch for your feature or bug fix, make your changes, and submit a pull request with a clear description of your modifications.

## Contact

For any inquiries or permissions, please contact:
- Email: shwetkamalsingh55@gmail.com
- LinkedIn: https://www.linkedin.com/in/shwet-kamal-singh/
- GitHub: https://github.com/Shwet-Kamal-Singh
