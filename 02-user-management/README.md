Practical 2: User and Group Management

Aim

To understand and manage users and groups in Red Hat Linux.

Commands

useradd fariya
passwd fariya
groupadd linuxadmin
usermod -aG linuxadmin fariya
id fariya
groups fariya

Explanation

- "useradd" creates a new user.
- "passwd" sets the user's password.
- "groupadd" creates a new group.
- "usermod -aG" adds a user to a group.
- "id" displays the user's ID and groups.
- "groups" shows the groups a user belongs to.

Result

Successfully created a user, created a group, added the user to the group, and verified the user's group membership in Red Hat Linux using VMware Workstation.
