Practical 7: RAID Configuration

Aim

To understand and configure RAID in Red Hat Linux using VMware Workstation for disk management and data protection.

Commands Used

lsblk
fdisk -l
mdadm --create /dev/md0 --level=1 --raid-devices=2 /dev/sdb /dev/sdc
mkfs.ext4 /dev/md0
mkdir /raid-data
mount /dev/md0 /raid-data
df -h
cat /proc/mdstat

Explanation

- "lsblk" — Displays available disks and partitions.
- "fdisk -l" — Lists disk partition details.
- "mdadm --create" — Creates a RAID 1 array.
- "mkfs.ext4" — Creates an ext4 filesystem on the RAID device.
- "mkdir /raid-data" — Creates a mount point.
- "mount" — Mounts the RAID device.
- "df -h" — Verifies the mounted filesystem.
- "cat /proc/mdstat" — Checks RAID status.

Expected Output

The RAID array should be created successfully and mounted at "/raid-data".

Conclusion

Successfully configured RAID 1 in Red Hat Linux using VMware Workstation and verified the RAID status.
