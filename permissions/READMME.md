# Holberton Shell - Permissions

This repository contains a set of scripts related to **file permissions** in Linux/Unix systems. The purpose of these scripts is to manage file permissions, change file owners, and handle user groups.

## Overview

In Linux systems, file permissions are very important because they determine who can access, read, or modify files. Permissions are given to users based on three categories:

- **Owner**: The person who owns the file.
- **Group**: A group of users who share the same permissions.
- **Others**: All other users on the system.

## The Tasks:

### 0. My name is Betty
This script switches the current user to the **betty** user.

### 1. Who am I
This script displays the current user's name using the `whoami` command.

### 2. Groups
This script shows the groups the current user belongs to, using the `groups` command.

### 3. New owner
This script changes the owner of a file using the `chown` command, making someone else the owner of the file.

### 4. Empty!
This script removes all permissions from a file, using `chmod`, making it inaccessible to everyone.

### 5. Execute
This script adds **execute** permission to a file, so it can be run as a program or script.

### 6. Multiple permissions
This script adds multiple permissions (read, write, execute) to a file at once.

### 7. Everybody!
This script adds all permissions (read, write, execute) for everyone: the owner, the group, and others.

### 8. James Bond
This script grants the **owner** of the file permission to read and execute it, but others can't access it.

### 9. John Doe
This script creates a file, and then changes the file’s owner to "john" and the group to "doe".

### 10. Look in the mirror
This script sets the permissions of a file to be the same as the permissions of another file.

### 11. Directories
This script changes the permissions of a directory to make it accessible to the owner and the group.

### 12. More directories
This script recursively changes permissions of a directory and its contents.

### 13. Change group
This script changes the group ownership of a file using the `chgrp` command.

### 14. Owner and group
This script changes both the owner and group of a file at the same time.

### 15. Symbolic links
This script creates a symbolic link (symlink) to a file or directory.

### 16. If only
This script ensures that a file is only accessible to its owner, with no permissions for others.
