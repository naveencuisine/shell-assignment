# Shell Scripting Task - File Operations and Directory Management

## Task Overview

This repository contains shell scripts and commands to complete the following tasks:

- Create a directory named `my_folder` and navigate into it.
- Create a file `my_file.txt` with some sample text.
- Create another file `another_file.txt` with some sample text.
- Concatenate the content of `another_file.txt` to `my_file.txt`.
- Display the updated content of `my_file.txt`.
- List all files and directories in the current directory.
- Create 20 files with `.txt` extensions.
- Rename the first 5 `.txt` files to `.yml` extension.
- Print the latest created top 5 files among all files in the directory.

---

## Tech Stack

- Shell scripting
- Compatible with: AWS CLI shell, Git Bash, Windows Subsystem for Linux (WSL), VirtualBox Linux environments

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/naveencuisine/shell-assignment.git
   cd shell-assignment
==========

mkdir my_folder
cd my_folder

echo "This is my_file" > my_file.txt
echo "This is another file content" > another_file.txt

cat another_file.txt >> my_file.txt
cat my_file.txt

ls -l

# Create 20 text files
for i in {1..20}; do
  echo "File number $i" > file$i.txt
done

# Rename first 5 .txt files to .yml
for i in {1..5}; do
  mv file$i.txt file$i.yml
done

# List latest 5 created files
ls -lt | head -n 5
==============

---

Would you like me to generate a shell script file (`task.sh`) to go along with this README?

Thank you for reviewing my worK
