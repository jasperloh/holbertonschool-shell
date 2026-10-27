## Description
This project introduces Linux file permissions, user management, and ownership concepts as part of the Holberton School Software Engineering program.
The exercises focus on understanding how Linux manages access to files and directories through users, groups, and permissions.

## Scripts 
0-iam_betty
Switches the current user to the user betty using the su command.


1-who_am_i
Prints the effective username of the current user using the whoami command.

2-groups
Prints all the groups the current user belongs to using the groups command.

3-new_owner
Changes the owner of the file hello to the user betty using the chown command.

4-empty
Creates an empty file named hello using the touch command.

5-execute
Adds execute permission to the owner of the file hello without modifying other permissions.

6-multiple_permissions
Adds execute permission to the owner and group owner, and read permission to other users, without changing existing permissions.

7-everybody
Adds execute permission to the owner, group owner, and other users of the file hello.

8-James_Bond
Sets the permissions of hello to 007, granting all permissions to others and none to the owner or group.

9-John_Doe
Sets the permissions of the file hello to rwxr-x-wx (753).

10-mirror_permissions
Sets the permissions of hello to match those of olleh using chmod --reference.

11-directories_permissions
Adds execute permission to all directories recursively for the owner, group owner, and other users.

12-directory_permissions
Creates a directory named my_dir with permissions 751.

13-change_group
Changes the group owner of the file hello to school using the chgrp command.

14-change_owner_and_group
Recursively changes the owner to vincent and group owner to staff for all files and directories in the current working directory.



