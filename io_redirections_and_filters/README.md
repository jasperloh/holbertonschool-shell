## Description
This project is part of the Holberton School Software Engineering program. It introduces Linux shell input/output (I/O) redirections, filters, and commands used to manipulate text and files.
The exercises focus on understanding how to display, redirect, and process information using Bash commands.

## Scripts
0-hello_world
Prints "Hello, World" followed by a newline to standard output.

1-confused_smiley
Displays the confused smiley "(Ôo)' followed by a newline.

2-hellofile
Displays the contents of the /etc/passwd file using the cat command.

3-twofiles
Displays the contents of /etc/passwd and /etc/hosts using the cat command.

4-lastlines
Displays the last 10 lines of the /etc/passwd file using the tail command.

5-firstlines
Displays the first 10 lines of the /etc/passwd file using the head command.

6-third_line
Displays the third line of the file iacta using head and tail without sed.

7-file
Creates a file with a name containing special characters and writes "Best School" followed by a newline.

8-cwd_state
Writes the output of ls -la into ls_cwd_content, creating the file if necessary or overwriting its existing contents.

9-duplicate_last_line
Duplicates the last line of the file iacta by appending it to the same file.

10-no_more_js
Recursively deletes all regular files with a .js extension from the current directory and its subdirectories.

11-directories
Counts all directories and subdirectories, including hidden directories, while excluding the current and parent directories.

12-newest_files
Displays the 10 newest entries in the current directory, sorted by modification time from newest to oldest, with one entry per line.

13-unique
Reads words from standard input, prints only those appearing exactly once, and sorts them alphabetically.

14-findthatword
Displays all lines containing the pattern "root" from /etc/passwd using grep.

15-countthatword
Counts the number of lines containing the pattern "bin" in /etc/passwd using grep -c.

16-whatsnext
Displays lines containing "root" and the 3 lines following each match in /etc/passwd.

17-hidethisword
Displays all lines in /etc/passwd that do not contain the pattern "bin" using grep -v.

18-letteronly
Displays all lines from /etc/ssh/sshd_config that begin with an uppercase or lowercase letter.

19-AZ
Replaces all occurrences of A with Z and c with e from standard input using the tr command.

20-hiago
Removes all occurrences of lowercase c and uppercase C from standard input using tr -d.

21-reverse
Reverses the characters of each line received from standard input using the rev command.

22-users_and_homes
Displays all usernames and their home directories from /etc/passwd, sorted alphabetically by username.
