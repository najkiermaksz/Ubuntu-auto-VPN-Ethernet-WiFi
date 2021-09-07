# Ubuntu-auto-VPN-Ethernet-WiFi
Set up VPN that automatically connects on startup

1. Set up Ethernet / WiFi connection
2. Get your VPN credentials (username, pwd), e.g. https://my.surfshark.com/vpn/manual-setup/main
3. Download your VPN location config file (e.g. de-ber.prod.surfshark.comsurfshark_openvpn_tcp.ovpn)
4. Go to Settings - Network
5. Click + on the VPN option
6. Import from file...
7. Select file, apply
8. Go to VPN settings, Identity tab
9. Click on the small user icon in the password tab
10. Select store password for all users
11. Open terminal
12. nm-connection-editor
13. Open connection settings
14. Click on the General tab
15. Select "Automatically connect to VPN"
