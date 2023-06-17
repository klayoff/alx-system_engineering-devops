# Shell Basics

This repository contains shell scripts that perform various tasks. Each script is designed to be executed in the Bash shell and is two lines long. The scripts are tested on Ubuntu 20.04 LTS.

## Scripts Description

- `0-current_working_directory`: Prints the absolute path name of the current working directory.
- `1-listit`: Displays the contents list of the current directory.
- `2-bring_me_home`: Changes the working directory to the user's home directory.
- `3-listfiles`: Displays the current directory contents in a long format.
- `4-listmorefiles`: Displays the current directory contents, including hidden files, in a long format.
- `5-listfilesdigitonly`: Displays the current directory contents in a long format with user and group IDs displayed numerically, including hidden files.
- `6-firstdirectory`: Creates a directory named "my_first_directory" in the /tmp/ directory.
- `7-movethatfile`: Moves the file "betty" from /tmp/ to /tmp/my_first_directory.
- `8-firstdelete`: Deletes the file "betty" from /tmp/my_first_directory.
- `9-firstdirdeletion`: Deletes the directory "my_first_directory" from the /tmp directory.
- `10-back`: Changes the working directory to the previous one.
- `11-lists`: Lists all files in the current directory, parent directory, and /boot directory in a long format.
- `12-file_type`: Prints the type of the file named "iamafile" located in the /tmp directory.
- `13-symbolic_link`: Creates a symbolic link named "__ls__" to /bin/ls in the current working directory.
- `14-copy_html`: Copies all HTML files from the current working directory to the parent of the working directory, only if they don't exist or are newer.

## Author
klayoff

## Requirements

- All scripts should be exactly two lines long.
- All files should end with a new line.
- The first line of all files should be exactly "#!/bin/bash".
- All scripts must be executable using the `chmod` command.
- Scripts should not use backticks, &&, ||, or ;.
- Scripts will be tested on Ubuntu 20.04 LTS.

## Usage

1. Clone the repository:

```bash
$ git clone https://github.com/your-username/alx-system_engineering-devops.git

