Practical 6: NFS Server Configuration

Aim

To understand and configure Network File System (NFS) in Red Hat Linux using VMware Workstation and share a directory between a server and a client.

Commands Used

yum install nfs-utils -y
mkdir /nfs-share
chmod 777 /nfs-share

vi /etc/exports

/nfs-share *(rw,sync,no_root_squash)

exportfs -rav
systemctl start nfs-server
systemctl enable nfs-server
systemctl status nfs-server

mount <server-ip>:/nfs-share /mnt
df -h

Explanation

- "yum install nfs-utils -y" — Installs the NFS package.
- "mkdir /nfs-share" — Creates a shared directory.
- "chmod 777 /nfs-share" — Gives read, write, and execute permissions.
- "vi /etc/exports" — Opens the NFS configuration file.
- "exportfs -rav" — Applies the export configuration.
- "systemctl start nfs-server" — Starts the NFS service.
- "systemctl enable nfs-server" — Enables NFS service at boot.
- "systemctl status nfs-server" — Checks whether the service is running.
- "mount <server-ip>:/nfs-share /mnt" — Mounts the shared directory on the client.
- "df -h" — Verifies the mounted file system.

Expected Output

The NFS service should be active, and the shared directory should be successfully mounted on the client system.

Conclusion

Successfully configured an NFS server in Red Hat Linux using VMware Workstation and shared a directory between the server and client.
