# Users, Groups and File Permissions

## Introduction

Linux is a multi-user operating system. It allows multiple users to work on the same system while controlling access to files and resources.

## Users

A user is an account that can log in to and use a Linux system.

The whoami command shows the current user.

Command: whoami

Example output: ashu

## Groups

A group is a collection of users. Groups make it easier to manage permissions for multiple users.

Users can belong to one or more groups.

## File Permissions

Linux uses permissions to control who can access a file or directory.

There are three basic permissions:

- Read (r): Allows a user to view a file.
- Write (w): Allows a user to modify a file.
- Execute (x): Allows a user to execute a file or access a directory.

## Permission Categories

Permissions are assigned to three categories:

- Owner: The user who owns the file.
- Group: Users belonging to the file's group.
- Others: All other users.

## Checking Permissions

The ls -l command displays file permissions.

Command: ls -l

A typical permission structure looks like:

-rw-r--r--

This represents permissions for the owner, group and others.

## chmod

The chmod command is used to change file permissions.

Example:

chmod 644 filename

This gives the owner read and write permissions, while the group and others get read permission.

## Importance of Permissions

File permissions help protect sensitive information and prevent unauthorized modification or access.

## Learning Outcome

I learned the basic concepts of Linux users, groups and file permissions. I also understood how permissions help secure files and control access to Linux resources.
