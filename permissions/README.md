# alu-shell

Welcome to the **alu-shell** repository! This repository contains a series of shell scripts focused on user and group permissions, file manipulation, and directory management in a Linux environment.

## Recent Updates

- **[0-iam_betty]**: Created a script that switches the current user to the user **betty**.
- **[1-who_am_i]**: Implemented a script that prints the effective username of the current user.
- **[2-groups]**: Developed a script that lists all groups the current user is part of.
- **[3-new_owner]**: Created a script to change the owner of the file **hello** to the user **betty**.
- **[4-empty]**: Wrote a script to create an empty file called **hello**.
- **[5-execute]**: Added execute permission for the owner of the file **hello**.
- **[6-multiple_permissions]**: Created a script to add execute permission to the owner and group owner and read permission to others for the file **hello**.
- **[7-everybody]**: Developed a script that adds execution permission to all users for the file **hello**.
- **[8-James_Bond]**: Set the permissions of **hello** so the owner and group have no permissions, while others have all permissions.
- **[9-John_Doe]**: Set the mode of **hello** to `-rwxr-x-wx`.
- **[10-mirror_permissions]**: Created a script that mirrors the permissions of the file **olleh** to **hello**.
- **[11-directories_permissions]**: Added execute permission to all subdirectories of the current directory.
- **[12-directory_permissions]**: Created a directory called **my_dir** with permissions set to **751**.
- **[13-change_group]**: Implemented a script to change the group owner of **hello** to **school**.

## Personal Work

This repository serves as a practical exercise in understanding user and group permissions, file manipulation, and script automation in a Linux environment. Each script is designed to address specific requirements related to file ownership and permission management.

## Getting Started

To get started with the scripts in this repository, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/alu-shell.git
   cd alu-shell/permissions

