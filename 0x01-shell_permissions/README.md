# 0x01. Shell, Permissions

## 📅 Week 11: June 16 – June 23, 2025  
**Weight**: 1280  
**Grade Contribution**: 12.5%

---

## 📘 Project Overview

This project focuses on understanding and managing **file permissions** in Linux, a fundamental skill for maintaining system security and ensuring proper access control. Through various hands-on scripting tasks, you’ll explore:

- User and group ownership of files
- Permission modes for read, write, and execute
- Changing file and directory permissions
- Switching users and managing file access

You will gain the ability to control who can view or modify files and directories, a key competency in both development and system administration roles.

---

## 🛠️ Technologies Used

- Ubuntu 20.04 LTS
- Bash 5.x+
- Git and GitHub

---

## 🧩 Repository Structure

- **Repository:** `system_engineering-devops`
- **Directory:** `0x01-shell_permissions`
- **File Format:** All scripts are executable files starting with the line:
  ```bash
  #!/bin/bash
To make each script executable:

bash
Copy
Edit
chmod +x <filename>
🚀 Getting Started
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/system_engineering-devops.git
cd system_engineering-devops/0x01-shell_permissions
Make a script executable:

bash
Copy
Edit
chmod +x 0-iam_betty
Run a script:

bash
Copy
Edit
./0-iam_betty
📝 Task Summary
Task #	File	Description
0	0-iam_betty	Switches current user to betty (must be exactly 8 characters + newline)
1	1-who_am_i	Prints the effective username of the current user
2	2-groups	Displays all groups the current user belongs to
3	3-new_owner	Changes the owner of the file hello to betty
4	4-empty	Creates an empty file named hello
5	5-execute	Adds execute permission to the owner of the file hello
6	8-James_Bond	Sets hello permissions to --- --- rwx
7	9-John_Doe	Sets hello permissions to rwx r-x -wx
8	11-directories_permissions	Adds execute permission to all subdirectories of current directory
9	12-directory_permissions	Creates my_dir with 751 permissions
10	13-change_group	Changes the group owner of the file hello to school

Note: Script numbers may not be sequential to match task numbers from the project platform.

📌 Submission Guidelines
All files should be created under:

GitHub Repo: system_engineering-devops

Directory: 0x01-shell_permissions

Each task must have:

A script file with the exact required filename

Executable permission (chmod +x)

A shebang #!/bin/bash as the first line

You can use the GitHub web UI or the command line to push your files.

✅ Example Test
bash
Copy
Edit
julien@ubuntu:/tmp/h$ tail -1 0-iam_betty | wc -c
9
✍️ Author
Tendai
GitHub Profile
ALX Software Engineering Program – Week 11

