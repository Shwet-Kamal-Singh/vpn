
# WireGuard Server Installation

WireGuard® is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN. WireGuard is designed as a general purpose VPN for running on embedded interfaces and super computers alike, fit for many different circumstances. Initially released for the Linux kernel, it is now cross-platform (Windows, macOS, BSD, iOS, Android) and widely deployable. It is currently under heavy development, but already it might be regarded as the most secure, easiest to use, and simplest VPN solution in the industry.

This script enables you to set up your own secure VPN server effortlessly in just a few seconds.


### Why is WireGuard special?

- Fast and Easy: It's quicker and more user-friendly than other VPN options.
- Strong Security: Uses the latest technology to keep your data safe and sound.
- Works on many devices: You can use it on your phone, computer, or even fancy robots!

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
curl -O https://github.com/Shwet-Kamal-Singh/vpn/blob/main/wireguard_vpn/wireguard_script.sh

```
```bash
chmod 744 wireguard_script.sh
```
```bash
bash wireguard_script.sh
```

#### Follow the on-screen instructions

Upon completion, you'll find .conf files in your home directory. These are client configuration files. Download them from your server and connect using your preferred WireGuard client.

#### Post-Installation

To create a new account, simply rerun the script and follow the prompts. Options include adding or removing a client, or uninstalling WireGuard.

#### Features:

- Speed: WireGuard boasts exceptional speeds due to its modern and streamlined codebase. This makes it ideal for tasks like streaming and gaming.
- Simplicity: Setting up and using WireGuard is significantly easier compared to other VPN solutions. Its configuration is minimal and user-friendly.
- Security: WireGuard utilizes cutting-edge cryptography protocols, ensuring robust protection for your online activity.
- Open-Source: WireGuard's open-source nature allows for transparency and community scrutiny, fostering trust in its security.
- Cross-Platform: WireGuard runs seamlessly on various operating systems, including Windows, macOS, Linux, Android, and iOS.
- Lightweight: WireGuard has a small code footprint, making it resource-efficient and suitable for even low-powered devices.
- Modern Design: Built from the ground up with modern principles, WireGuard avoids the complexities and compatibility issues of older VPN protocols.
- Future-Proof: WireGuard's design is adaptable and incorporates the latest advancements in cryptography, ensuring its continued effectiveness.
- Active Development: The WireGuard community is constantly working on improvements and new features, keeping the software at the forefront of VPN technology.
- Privacy-Focused: WireGuard prioritizes user privacy and does not collect or store any sensitive data.


#### Compatibility:

The script is compatible with the following Linux distributions:

|                    | Support  |
| ------------------ | -------  |
| AlmaLinux 8        | ✅      |
| Amazon Linux 2     | ✅ 🤖     |
| Arch Linux         | ✅      |
| CentOS 7           | ✅ 🤖   |
| CentOS Stream >= 8 | ✅ 🤖   |
| Debian >= 10       | ✅ 🤖   |
| Fedora >= 35       | ✅ 🤖   |
| Oracle Linux 8     | ✅      |
| Rocky Linux 8      | ✅      |
| Ubuntu >= 18.04    | ✅ 🤖   |


#### Additional Notes
- Refer to the official WireGuard documentation: (https://www.wireguard.com/) for more detailed configuration and customization options.
- Consider security best practices when setting up your VPN server.

