# Shell Permissions

In this section, you will learn how to control who can see or change your files.

## The Concept

Every file on a Linux system belongs to an **Owner** and a **Group**. There are rules (permissions) for three categories of users:
1. **User (u)**: The owner of the file.
2. **Group (g)**: Users who are in the file's group.
3. **Others (o)**: Everyone else.

## What are the permissions?

- **Read (r)**: You can open and look at the file.
- **Write (w)**: You can modify or delete the file.
- **Execute (x)**: You can run the file as a program.

## Commands you will use

- `chmod`: **Ch**ange **Mod**e. This command changes the permissions (e.g., making a file executable).
- `chown`: **Ch**ange **Own**er. Changes who owns the file.
- `chgrp`: **Ch**ange **Gr**ou**p**. Changes the group of the file.
- `su`: Switch User. Log in as someone else (like the administrator).
