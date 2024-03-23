# OpenVPN Server Installation

OpenVPN is a powerful tool that creates secure connections between devices over the internet. This guide will help you set up your own OpenVPN server on a compatible Linux system.

This script enables you to set up your own secure VPN server effortlessly in just a few seconds.

### Before You Begin


- Ensure your server has a public IP address.
- This guide is compatible with Debian, Ubuntu, CentOS, Amazon Linux 2, Fedora, Oracle Linux, Arch Linux, Rocky Linux, and AlmaLinux.


### Installation Steps

#### Update your system
```bash
sudo apt update && sudo apt upgrade -y
```

#### Download and run the installation script
```bash
curl -O https://github.com/Shwet-Kamal-Singh/vpn/blob/main/openvpn/openvpn_script.sh
```
```bash
chmod 744 openvpn_script.sh
```
```bash
bash openvpn_script.sh
```

#### Follow the on-screen instructions

Upon completion, you'll find .ovpn files in your home directory. These are client configuration files. Download them from your server and connect using your preferred OpenVPN client.

#### Post-Installation

To create a new account, simply rerun the script and follow the prompts. Options include adding or removing a client, or uninstalling OpenVPN.

#### Features:

- Installs and configures a fully functional OpenVPN server.
- Manages iptables rules and forwarding seamlessly.
- Offers clean removal of OpenVPN, including configuration and iptables rules.
- Customizable encryption settings with enhanced defaults.
- Utilizes OpenVPN 2.4 features, including encryption improvements.
- Supports a variety of DNS resolvers for clients.
- Choice of using a self-hosted resolver with Unbound.
- Supports TCP and UDP protocols.
- NATed IPv6 support.
- Compression disabled by default to prevent VORACLE.
- Runs in unprivileged mode as nobody/nogroup.
- Blocks DNS leaks on Windows 10.
- Provides a randomized server certificate name.
- Option to protect clients with a password using private key encryption.


#### Compatibility:

The script is compatible with the following Linux distributions:

|                    | Support  |
| ------------------ | -------  |
| AlmaLinux 8        | ✅      |
| Amazon Linux 2     | ✅ 🤖   |
| Arch Linux         | ✅      |
| CentOS 7           | ✅ 🤖   |
| CentOS Stream >= 8 | ✅ 🤖   |
| Debian >= 10       | ✅ 🤖   |
| Fedora >= 35       | ✅ 🤖   |
| Oracle Linux 8     | ✅      |
| Rocky Linux 8      | ✅      |
| Ubuntu >= 18.04    | ✅ 🤖  |


#### Additional Notes
- Refer to the official OpenVPN documentation: (https://openvpn.net/community-resources/) for more detailed configuration and customization options.
- Consider security best practices when setting up your VPN server.
