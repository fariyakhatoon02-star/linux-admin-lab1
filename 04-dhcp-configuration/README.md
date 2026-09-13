Practical 4: DHCP Server Configuration

Aim

To configure a DHCP server in Red Hat Linux.

Commands

yum install dhcp -y
systemctl start dhcpd
systemctl enable dhcpd
systemctl status dhcpd

Explanation

- "yum install dhcp -y" installs the DHCP server.
- "systemctl start dhcpd" starts the DHCP service.
- "systemctl enable dhcpd" enables the DHCP service at boot.
- "systemctl status dhcpd" checks whether the DHCP service is running.

Result

Successfully installed, started, enabled, and verified the DHCP server in Red Hat Linux using VMware Workstation.
