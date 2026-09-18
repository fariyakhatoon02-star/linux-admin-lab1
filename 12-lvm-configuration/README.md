Practical 12: LVM (Logical Volume Management)

Aim

To understand and configure Logical Volume Management (LVM) in Red Hat Linux.

Commands Used

fdisk -l

pvcreate /dev/sdb1

vgcreate vgdata /dev/sdb1

lvcreate -L 1G -n lvdata vgdata

mkfs.ext4 /dev/vgdata/lvdata

mkdir /lvmdata

mount /dev/vgdata/lvdata /lvmdata

df -h

Procedure

1. Check available disks using "fdisk -l".
2. Create a Physical Volume using "pvcreate".
3. Create a Volume Group named "vgdata".
4. Create a Logical Volume named "lvdata".
5. Format the logical volume with the ext4 filesystem.
6. Create a mount point and mount the logical volume.
7. Verify the mounted volume using "df -h".

Output

- Physical Volume created successfully.
- Volume Group "vgdata" created.
- Logical Volume "lvdata" created and mounted.
- Storage verified using "df -h".

Conclusion

Successfully configured Logical Volume Management (LVM) in Red Hat Linux using VMware Workstation.
