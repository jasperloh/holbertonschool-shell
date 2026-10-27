Description
This project introduces fundamental Linux shell commands and Bash scripting concepts.
The exercises focus on navigating the filesystem, understanding directories, and executing basic shell commands.

Scripts
0-current_working_directory
Prints the absolute path of the current working directory.

1-listit
Displays the contents of the current working directory using the ls command.

2-bring_me_home
Changes the working directory to the user's home directory without using shell variables.

3-listfiles
Displays the contents of the current directory in long format using ls -l.

4-listmorefiles
Displays all files and directories, including hidden files, in long format using ls -la.

5-listfilesdigitonly
Displays directory contents in long format, including hidden files, with numerical user and group IDs.

6-firstdirectory
Creates a directory named my_first_directory inside /tmp using the mkdir command.

7-movethatfile
Moves the file betty from /tmp to /tmp/my_first_directory.

8-firstdelete
Deletes the file betty from /tmp/my_first_directory using the rm command.

9-firstdirdeletion
Deletes the empty directory my_first_directory from /tmp using the rmdir command.

10-back
Changes the working directory to the previous working directory using cd -.

11-lists
Lists all files, including hidden files, in the current directory, parent directory, and /boot directory in long format.

12-file_type
Prints the type of the file /tmp/iamafile using the file command.

13-symbolic_link
Creates a symbolic link named __ls__ pointing to /bin/ls in the current working directory.

14-copy_html
Copies HTML files from the current directory to its parent directory only when the destination file does not exist or the source file is newer.

15-lets_move
Moves all files beginning with an uppercase letter from the current working directory to /tmp/u.

16-clean_emacs
Deletes files in the current working directory whose names end with ~.

17-tree
Creates the nested directories welcome/, welcome/to/, and welcome/to/school/ using mkdir -p.
