## openvpn-install
VPN-in-a-Box is an OpenVPN installer for Debian 8 , Ubuntu 14.04/16.04, and CentOS 7.  It is built upon the work of [Nyr's OpenVPN scripts](https://github.com/Nyr/openvpn-install).

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be simple and secure.

### Installation
Run the script and follow the assistant:

`wget https://git.io/vSAjf -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

### Note about .ovpn distribution
Typically, you want to distribute the .ovpn client files in a secure manner (such as using SFTP to download them from your server.  However, I've included a QR code generator that provides an HTTP link to the .ovpn file for easy installation on mobile devices.  Note that this is not securely transmitted and is optionally there if you prefer the ease of access.
