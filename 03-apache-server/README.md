Practical 3: Apache Web Server Configuration

Aim

To install and configure the Apache web server in Red Hat Linux.

Commands

yum install httpd -y
systemctl start httpd
systemctl enable httpd
systemctl status httpd

Explanation

- "yum install httpd -y" installs Apache.
- "systemctl start httpd" starts the Apache service.
- "systemctl enable httpd" starts Apache automatically after reboot.
- "systemctl status httpd" checks whether Apache is running.

Result

Successfully installed, started, enabled, and verified the Apache web server in Red Hat Linux using VMware Workstation.
