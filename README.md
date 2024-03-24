## Welcome to Your Secure Connection Hub!

This hub provides a central location to manage secure Virtual Private Network (VPN) connections for multiple providers. 

## Prerequisites

Before you begin, ensure that you meet the following prerequisites:

### Operating System

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

Please note that while other distributions may work, they have not been explicitly tested or verified for compatibility.

### Administrative Privileges

You will need administrative privileges on your system to install and configure the VPN software.

### Command Line Interface Knowledge

Basic knowledge of the command line interface is required to execute installation and configuration commands.



## Understanding VPNs:

A VPN encrypts your internet traffic, protecting data flowing between your device and the internet. It provides enhanced privacy by masking your IP address and location.

## Choose the VPN protocol that best suits your needs:

- OpenVPN: Offers strong security and wide compatibility with various devices and platforms.
- WireGuard: A newer, simpler protocol known for its speed and ease of use.

## Getting Started:
Before diving in, ensure you have a reliable VPN service provider with credentials for each protocol you intend to use.

## Navigating This Directory

To quickly access the configuration files and installation guides for each VPN protocol, you can use the following direct links:

- **[OpenVPN Configuration](https://github.com/Shwet-Kamal-Singh/vpn/tree/main/openvpn)**: Detailed instructions and configuration files for setting up OpenVPN.
- **[WireGuard Configuration](https://github.com/Shwet-Kamal-Singh/vpn/tree/main/wireguard_vpn)**: Explore the setup guide and configuration files for WireGuard VPN.

Simply click on the respective links to navigate directly to the folders.

## Connecting to the Server

Once the profile is downloaded, you need to configure a client:

* **Windows**: Use [OpenVPN GUI](https://openvpn.net/index.php/open-source/downloads.html). After installing the app, copy the .ovpn to the **C:\Program Files\OpenVPN\config** folder. Launch the GUI from your Start menu, then right-click the icon in the System Tray, and click **Connect**. Disconnect by right-clicking and selecting **Disconnect**.

* **MacOS** (OS X): Use [Tunnelblick](https://tunnelblick.net/downloads.html). Download and install Tunnelblick. After downloading, double-click on the downloaded .ovpn file and import the configuration either for yourself or all users. Once imported, click the Tunnelblick icon on the menu bar and click **Connect**. Disconnect by clicking the Tunnelblick icon and selecting **Disconnect**.

* **Android**: Use [OpenVPN Connect for Android](https://play.google.com/store/apps/details?id=net.openvpn.openvpn&hl=en). Download and install the app. Next, go to the admin site and create and/or download a profile. In the app, select Import from the menu, then select **Import**, then select **Import Profile from SD card**. Find the profile in your **Downloads** folder and import the profile. Once downloaded, click **Connect**. To disconnect, open the app again and select **Disconnect**.

* **iOS**: Use [OpenVPN Connect for iOS](https://itunes.apple.com/us/app/openvpn-connect/id590379981?mt=8). Install the app, then browse to the admin site in Safari. Create and/or download a profile. After the profile is downloaded, select **Open in OpenVPN**. Install the profile, then select **Connect** to connect to the VPN. To disconnect, open the app again and select **Disconnect**.

That's it! Your VPN is up and running.
