# Secure Connection Hub: OpenVPN and WireGuard VPN Setup

This hub provides a central location to manage secure Virtual Private Network (VPN) connections using OpenVPN and WireGuard protocols. Ideal for security professionals and enthusiasts, it offers streamlined installation scripts and detailed guidance for rapid deployment and testing.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Compatibility](#compatibility)
- [Installation Steps](#installation-steps)
  - [OpenVPN Installation](#openvpn-installation)
  - [WireGuard Installation](#wireguard-installation)
- [Connecting to the Server](#connecting-to-the-server)
  - [OpenVPN Connection](#openvpn-connection)
  - [WireGuard Connection](#wireguard-connection)
- [Additional Notes](#additional-notes)
- [License](#license)
- [Contributing](#contributing)

## Prerequisites

- A supported Linux distribution (see [Compatibility](#compatibility) section)
- Root or sudo privileges
- Basic knowledge of command line interface
- Reliable VPN service provider credentials

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

### OpenVPN Installation
```bash
curl -O https://raw.githubusercontent.com/Shwet-Kamal-Singh/vpn/main/openvpn/openvpn_script.sh
```
```bash
chmod +x openvpn_script.sh
```
```bash
sudo ./openvpn_script.sh
```

### WireGuard Installation
```bash
curl -O https://raw.githubusercontent.com/Shwet-Kamal-Singh/vpn/main/wireguard_vpn/wireguard_script.sh
```
```bash
chmod +x wireguard_script.sh
```
```bash
sudo ./wireguard_script.sh
```


## Connecting to the Server

### OpenVPN Connection

- **Windows**: Use [OpenVPN GUI](https://openvpn.net/index.php/open-source/downloads.html). Install the app, copy the .ovpn file to `C:\Program Files\OpenVPN\config`, launch GUI, right-click the system tray icon, and select "Connect".

- **macOS**: Use [Tunnelblick](https://tunnelblick.net/downloads.html). Install Tunnelblick, double-click the .ovpn file to import, click the Tunnelblick menu bar icon and select "Connect".

- **Android**: Use [OpenVPN Connect for Android](https://play.google.com/store/apps/details?id=net.openvpn.openvpn&hl=en). Install the app, import the profile, and tap "Connect".

- **iOS**: Use [OpenVPN Connect for iOS](https://itunes.apple.com/us/app/openvpn-connect/id590379981?mt=8). Install the app, download the profile in Safari, select "Open in OpenVPN", install the profile, and tap "Connect".

### WireGuard Connection

- **Windows**: Use [WireGuard for Windows](https://www.wireguard.com/install/). Install the app, import the configuration file, and click "Activate".

- **macOS**: Use [WireGuard for macOS](https://www.wireguard.com/install/). Install the app, import the configuration file, and toggle the connection on.

- **Android**: Use [WireGuard for Android](https://play.google.com/store/apps/details?id=com.wireguard.android). Install the app, import the configuration file, and tap the toggle to connect.

- **iOS**: Use [WireGuard for iOS](https://apps.apple.com/us/app/wireguard/id1441195209). Install the app, import the configuration file, and tap the toggle to connect.

## Additional Notes

- Regularly update your VPN client and server for the latest security features and bug fixes.
- Follow security best practices when handling VPN credentials and configuration files.
- For more detailed configuration options, refer to the official [OpenVPN](https://openvpn.net/community-resources/) and [WireGuard](https://www.wireguard.com/quickstart/) documentation.

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
