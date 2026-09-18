Practical 11: ACL (Access Control List) Configuration

Aim

To understand and configure Access Control Lists (ACL) in Red Hat Linux for advanced file permissions.

Commands Used

touch data.txt

getfacl data.txt

setfacl -m u:fariya:rwx data.txt

getfacl data.txt

setfacl -x u:fariya data.txt

Procedure

1. Create a file named "data.txt".
2. Check the current ACL using "getfacl".
3. Give fariya read, write, and execute permissions using "setfacl".
4. Verify the permissions with "getfacl".
5. Remove the ACL entry using "setfacl -x".

Output

- ACL added successfully for user fariya.
- Custom permissions displayed using "getfacl".
- ACL removed successfully.

Conclusion

Successfully configured and managed Access Control Lists (ACL) in Red Hat Linux using VMware Workstation.
