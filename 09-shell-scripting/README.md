Practical 9: Shell Scripting

Aim

To understand and create a basic shell script in Red Hat Linux.

Script

#!/bin/bash

echo "Welcome to Linux Administration Lab"
echo "User: $(whoami)"
echo "Current Date: $(date)"
echo "Current Directory: $(pwd)"

Commands Used

vi script.sh
chmod +x script.sh
./script.sh

Procedure

1. Create a shell script using "vi".
2. Write the script and save it.
3. Give execute permission using "chmod +x".
4. Run the script using "./script.sh".

Output

- Displays a welcome message.
- Shows current user name.
- Shows current date and current working directory.

Conclusion

Successfully created and executed a basic shell script in Red Hat Linux using VMware Workstation.
