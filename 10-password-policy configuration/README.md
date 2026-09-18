Practical 10: Password Policy Configuration

Aim

To understand and configure password policy in Red Hat Linux for better system security.

Commands Used

vim /etc/login.defs

passwd fariya

chage -l fariya

chage -M 90 -m 7 -W 7 fariya

Procedure

1. Open the "login.defs" file to view password policy settings.
2. Create or select a user ("fariya").
3. Set password aging using the "chage" command.
4. Verify password policy using "chage -l".

Output

- Password maximum age set to 90 days.
- Minimum age set to 7 days.
- Warning displayed 7 days before password expiry.

Conclusion

Successfully configured and verified password policy in Red Hat Linux using VMware Workstation.
