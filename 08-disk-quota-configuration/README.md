Practical 8: Disk Quota Configuration

Aim

To understand and configure disk quota in Red Hat Linux to limit disk space usage for users.

Commands Used

mount | grep quota

vim /etc/fstab

mount -o remount /

quotacheck -cug /

quotaon /

edquota fariya

quota -u fariya

repquota /

Procedure

1. Enable quota support in the "/etc/fstab" file.
2. Remount the filesystem.
3. Create quota database using "quotacheck".
4. Enable quotas with "quotaon".
5. Set disk quota for user fariya using "edquota".
6. Verify the quota using "quota" and "repquota".

Output

- Quota enabled successfully.
- Disk space limit assigned to user fariya.
- User quota verified using Linux quota commands.

Conclusion

Successfully configured and verified disk quota for a user in Red Hat Linux using VMware Workstation.
