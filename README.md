Linux Short Notes

This repository contains concise and practical notes on Linux. It's designed to help users quickly understand and reference essential Linux commands, file systems, and administrative tasks.

📖 Table of Contents
1. Introduction
2. Linux Basics (Essential Commands)
3. File Management
4. User and Permission Management
5. Process Management
6. Networking
7. System Monitoring and Logs
8. Package Management
9. Shell Scripting
10. Additional Resources
11. Contributing

🛠 Introduction

Linux is a powerful and flexible open-source operating system widely used in servers, development, and everyday computing. Its command-line interface (CLI) offers extensive control for managing files, processes, networks, and users.

---

🐧 Linux Basics
File System Hierarchy:
   `/`: Root directory.
   `/home`: User files.
   `/etc`: Configuration files.
   `/var`: Variable data like logs.
   `/tmp`: Temporary files.
Essential Commands:
   `pwd`: Print current directory.
   `ls`: List directory contents.
   `cd`: Change directory.
   `man`: Display the manual for a command.

📂 File Management
 Basic Commands:
   `touch`: Create an empty file.
   `cat`: View file content.
   `cp`: Copy files or directories.
   `mv`: Move or rename files.
   `rm`: Remove files or directories.
 Viewing Files:**
   `less`, `more`: Paginate through files.
   `head`, `tail`: View the beginning or end of a file.
 Finding Files:
   `find`: Search for files in directories.
   `locate`: Quickly find files using a pre-built database.
   `grep`: Search for text within files.

 👤 User and Permission Management
 User Commands:
   `whoami`: Display current user.
   `id`: Show user ID and group information.
   `adduser`, `deluser`: Add or delete a user.
 File Permissions:
   `chmod`: Change file permissions.
   `chown`: Change file ownership.
   `umask`: Set default file permissions.

 🖥 Process Management
 Monitoring Processes:
   `ps`: List running processes.
   `top`/`htop`: Interactive process monitoring.
   `uptime`: Check system uptime and load.
 Managing Processes:
   `kill`: Terminate a process by PID.
   `jobs`: List background jobs.
   `fg`, `bg`: Move jobs between foreground and background.
   `nice`, `renice`: Adjust process priority.

🌐 Networking
 Network Configuration:
   `ifconfig`/`ip addr`: View or configure network interfaces.
   `ping`: Test network connectivity.
   `hostname`: Display or set the system's hostname.
 File Transfers:
   `scp`: Securely copy files between systems.
   `rsync`: Efficient file synchronization.
 Network Monitoring:
   `netstat`/`ss`: View network connections and listening ports.
   `traceroute`: Trace the path to a network host.
   
📊 System Monitoring and Logs
 Monitoring Tools:
   `df`: Display disk space usage.
   `du`: Check directory size.
   `free`: View memory usage.
   `vmstat`: Monitor CPU and memory usage.
 Log Files:
   `/var/log`: Directory containing system logs.
   `dmesg`: View kernel logs.
   `journalctl`: Query and display logs from `systemd`.

📦 Package Management
Debian-based Systems (e.g., Ubuntu):
   `apt update`: Update package list.
   `apt install <package>`: Install a package.
   `apt remove <package>`: Remove a package.
 Red Hat-based Systems (e.g., CentOS):
   `yum update`: Update packages.
   `yum install <package>`: Install a package.
   `yum remove <package>`: Remove a package.

📜 Shell Scripting
 Basics:
   Scripts are text files with commands executed in sequence.
   Start a script with `#!/bin/bash` to specify the shell.
 Running Scripts:
   `bash script.sh`: Run the script using Bash.
   `chmod +x script.sh && ./script.sh`: Make the script executable and run it.
 Common Scripting Constructs:
   Variables: `VAR="value"`
   Loops: `for`, `while`
   Conditions: `if [ condition ]; then ... fi`
   Functions: `function_name() { commands }`

📚 Additional Resources
- [Linux Documentation Project](https://www.tldp.org/)
- [Linux Command Cheat Sheet](https://linuxize.com/post/linux-command-cheat-sheet/)

🤝 Contributing
Contributions are welcome! If you’d like to add new topics or improve existing ones, feel free to open a pull request or create an issue.

