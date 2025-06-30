Description
This project introduces shell redirection, a fundamental concept in Unix-based systems. You’ll learn how to use redirection to handle input and output from commands, manage files, and manipulate streams. It’s essential for automating tasks, scripting, and managing systems efficiently.

Each script file in this project is executable and performs a specific task related to shell I/O redirections.

Project Structure
Each numbered task is implemented as an executable shell script:

0-hello_world
Prints “Hello, World”, followed by a new line to standard output.

Example:

bash
Copy
Edit
$ ./0-hello_world
Hello, World
1-confused_smiley
Displays a confused smiley face: "(Ôo)'.

Example:

bash
Copy
Edit
$ ./1-confused_smiley
"(Ôo)'
2-hellofile
Displays the content of the /etc/passwd file.

Example:

bash
Copy
Edit
$ ./2-hellofile
# Output of /etc/passwd
3-twofiles
Displays the content of /etc/passwd and /etc/hosts.

Example:

bash
Copy
Edit
$ ./3-twofiles
# Output from both files
4-lastlines
Displays the last 10 lines of /etc/passwd.

Example:

bash
Copy
Edit
$ ./4-lastlines
# Last 10 lines
5-firstlines
Displays the first 10 lines of /etc/passwd.

Example:

bash
Copy
Edit
$ ./5-firstlines
# First 10 lines
6-third_line
Displays the third line of the file iacta.

The file iacta must be in the working directory. sed is not allowed.

Example:

bash
Copy
Edit
$ ./6-third_line
# The third line of iacta
7-file
Creates a file named exactly *'"Best School"'*$?*****:) containing the text Best School, followed by a new line.

Example:

bash
Copy
Edit
$ ./7-file
$ cat "*'\"Best School\"'*$?*****:)"
Best School
8-cwd_state
Saves the current directory's content (using ls -la) into the file ls_cwd_content, overwriting it if it exists.

Example:

bash
Copy
Edit
$ ./8-cwd_state
$ cat ls_cwd_content
# Output of ls -la
9-duplicate_last_line
Duplicates the last line of the file iacta.

The file iacta must be in the working directory.

Example:

bash
Copy
Edit
$ ./9-duplicate_last_line
# The last line of iacta is duplicated
10-no_more_js
Deletes all regular .js files (not directories) in the current directory and all subdirectories.

Example:

bash
Copy
Edit
$ ./10-no_more_js
# All .js files are removed
Repository
GitHub repository: system_engineering-devops

Directory: 0x02-shell_redirections

Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/system_engineering-devops.git
cd system_engineering-devops/0x02-shell_redirections
Make all scripts executable:

bash
Copy
Edit
chmod +x *
Run any script:

bash
Copy
Edit
./<script_name>
Author
Tendai
ALX Software Engineering Program