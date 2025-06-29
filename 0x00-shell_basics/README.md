0x00. Shell, Basics
📅 Week 10: June 2 – June 16, 2025
Weight: 1280
Contributes 12.5% to final grade

📘 Project Overview
This project introduces the fundamental concepts of the Linux shell and file system navigation. It is designed for beginners in software engineering to help them become familiar with:

Navigating directories

Viewing and manipulating file contents

Creating and running basic shell scripts

Understanding file permissions and hidden files

By completing these tasks, you'll build a solid foundation for working in a Unix-based development environment.

🛠️ Technologies & Tools
Ubuntu 20.04 LTS

Bash 5.1+

Git and GitHub

Shell scripts (written in bash)

📂 Project Structure
Repository: system_engineering-devops
Directory: 0x00-shell_basics

Each task is represented by an executable shell script placed inside the 0x00-shell_basics folder. All files begin with the required shebang line:

bash
Copy
Edit
#!/bin/bash
🚀 Getting Started
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/system_engineering-devops.git
cd system_engineering-devops/0x00-shell_basics
Make scripts executable (if needed):

bash
Copy
Edit
chmod +x <script_name>
Run a script:

bash
Copy
Edit
./0-current_working_directory
📋 Tasks Summary
Task	Filename	Description
0	0-current_working_directory	Prints the absolute path of the current directory
1	1-listit	Lists the contents of the current directory
2	2-bring_me_home	Changes the working directory to the user’s home
3	3-listfiles	Displays current directory contents in long format
4	4-listmorefiles	Lists contents including hidden files, in long format

Note: Each script was tested and designed to be run from the command line on Ubuntu-based systems.

📌 Submission Instructions
Repository must be named: system_engineering-devops

Inside the repo, create the directory: 0x00-shell_basics

Ensure all scripts are named exactly as specified per task

Push to GitHub before the project deadline

Scripts must have execution permissions (chmod +x)

All scripts must start with:

bash
Copy
Edit
#!/bin/bash
✅ Example Usage
bash
Copy
Edit
$ chmod +x ./0-current_working_directory
$ ./0-current_working_directory
/home/username/system_engineering-devops/0x00-shell_basics

✍️ Author
Tendai

GitHub Profile
Part of the ALX Software Engineering Program