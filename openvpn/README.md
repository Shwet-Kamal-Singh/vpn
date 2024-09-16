# OpenVPN Server Installation

OpenVPN is a powerful tool that creates secure connections between devices over the internet. This guide will help you set up your own OpenVPN server on a compatible Linux system.

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
curl -O https://github.com/Shwet-Kamal-Singh/vpn/blob/main/openvpn/openvpn_script.sh
```
```bash
chmod 744 openvpn_script.sh
```
```bash
bash openvpn_script.sh
```

Follow the on-screen instructions to complete the installation.

## Post-Installation

- Client configuration files (.ovpn) will be in your home directory.
- Download these files to connect using your preferred OpenVPN client.
- To create a new account, rerun the script and follow the prompts.
- Options include adding or removing a client, or uninstalling OpenVPN.

## Features

- Fully functional OpenVPN server installation and configuration
- Seamless iptables rules and forwarding management
- Clean removal option for OpenVPN, including configuration and iptables rules
- Customizable encryption settings with enhanced defaults
- Utilizes OpenVPN 2.4 features, including encryption improvements
- Supports various DNS resolvers for clients
- Option for self-hosted resolver with Unbound
- TCP and UDP protocol support
- NATed IPv6 support
- Compression disabled by default to prevent VORACLE
- Runs in unprivileged mode as nobody/nogroup
- Blocks DNS leaks on Windows 10
- Randomized server certificate name
- Option to protect clients with password using private key encryption

## Additional Notes

- For detailed configuration options, refer to the [official OpenVPN documentation](https://openvpn.net/community-resources/).
- Follow security best practices when setting up your VPN server.
- Regularly update your OpenVPN installation for the latest features and security patches.

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
