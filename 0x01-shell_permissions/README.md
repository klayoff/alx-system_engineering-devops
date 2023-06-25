# Shell Permissions - Script Readme

This repository contains shell scripts that demonstrate various permissions operations in a Unix-like environment.

## General Requirements

- Allowed editors: vi, vim, emacs
- Tested on Ubuntu 20.04 LTS
- All scripts are exactly two lines long (`$ wc -l file` should print 2)
- All files end with a new line
- The first line of all files is `#!/bin/bash`
- A README.md file is provided at the root of the project folder, describing each script's purpose
- Backticks (\`), `&&`, `||`, and `;` are not allowed
- All files must be executable

## Tasks

### Task 0: My name is Betty

Create a script that switches the current user to the user `betty`.

- Script file: [0-iam_betty](./0x01-shell_permissions/0-iam_betty)

### Task 1: Who am I

Write a script that prints the effective username of the current user.

- Script file: [1-who_am_i](./0x01-shell_permissions/1-who_am_i)

### Task 2: Groups

Write a script that prints all the groups the current user is part of.

- Script file: [2-groups](./0x01-shell_permissions/2-groups)

### Task 3: New owner

Write a script that changes the owner of the file `hello` to the user `betty`.

- Script file: [3-new_owner](./0x01-shell_permissions/3-new_owner)

### Task 4: Empty!

Write a script that creates an empty file called `hello`.

- Script file: [4-empty](./0x01-shell_permissions/4-empty)

### Task 5: Execute

Write a script that adds execute permission to the owner of the file `hello`.

- Script file: [5-execute](./0x01-shell_permissions/5-execute)

### Task 6: Multiple permissions

Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

- Script file: [6-multiple_permissions](./0x01-shell_permissions/6-multiple_permissions)

### Task 7: Everybody!

Write a script that adds execution permission to the owner, the group owner, and the other users, to the file `hello`.

- Script file: [7-everybody](./0x01-shell_permissions/7-everybody)

### Task 8: James Bond

Write a script that sets the permission to the file `hello` as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions

- Script file: [8-James_Bond](./0x01-shell_permissions/8-James_Bond)

### Task 9: John Doe

Write a script that sets the mode of the file `hello` to this:
- `-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`

- Script file: [9-John_Doe](./0x01-shell_permissions/9-John_Doe)

### Task 10: Look in the mirror

Write a script that sets the mode of the file `hello` the same as `olleh`'s mode.

- Script file: [10-mirror_permissions](./0x01-shell_permissions/10-mirror_permissions)

### Task 11: Directories

Create a script that adds execute permission to all subdirectories of the current directory for the owner, the.

### AUTHOR

anas klayoff
