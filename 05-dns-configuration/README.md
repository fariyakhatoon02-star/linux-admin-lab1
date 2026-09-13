Practical 5: DNS Server Configuration

Aim

To configure a DNS server in Red Hat Linux.

Commands

yum install bind bind-utils -y
systemctl start named
systemctl enable named
systemctl status named

Explanation

- "yum install bind bind-utils -y" installs the DNS server.
- "systemctl start named" starts the DNS service.
- "systemctl enable named" enables the DNS service at boot.
- "systemctl status named" checks whether the DNS service is running.

Result

Successfully installed, started, enabled, and verified the DNS server in Red Hat Linux using VMware Workstation.
