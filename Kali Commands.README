### 1. File and Directory Management
| Command | Description |
|---------|-------------|
| `pwd` | Prints the current working directory. |
| `ls` | Lists files and directories in the current directory. |
| `cd <directory>` | Changes the current directory to the specified one. |
| `mkdir <name>` | Creates a new directory. |
| `rmdir <directory>` | Removes an empty directory. |
| `rm <file>` | Removes a file. Use `-r` for recursive delete (for directories). |
| `cp <source> <destination>` | Copies a file or directory to a new location. Use `-r` for directories. |
| `mv <source> <destination>` | Moves or renames a file or directory. |
| `touch <file>` | Creates a new empty file. |

### 2. File Viewing and Editing
| Command | Description |
|---------|-------------|
| `cat <file>` | Displays the contents of a file. |
| `tac <file>` | Displays file content in reverse. |
| `nl <file>` | Displays file content with line numbers. |
| `more <file>` | Views file content one screen at a time. |
| `less <file>` | Similar to `more` but with backward navigation. |
| `head <file>` | Shows the first 10 lines of a file. |
| `tail <file>` | Shows the last 10 lines of a file. Use `-f` to monitor file updates. |
| `nano <file>` | Opens the file in the nano text editor. |
| `vi <file>` | Opens the file in the vi text editor. |

### 3. Permissions and Ownership
| Command | Description |
|---------|-------------|
| `chmod <permissions> <file>` | Changes the permissions of a file. |
| `chown <user>:<group> <file>` | Changes the owner and group of a file. |

### 4. User Management and Privileges
| Command | Description |
|---------|-------------|
| `sudo <command>` | Runs a command as a superuser (root privileges). |
| `su` | Switches to the root user. |
| `whoami` | Displays the current logged-in user. |
| `id` | Displays user ID and group ID. |

### 5. Package Management (APT and DPKG)
| Command | Description |
|---------|-------------|
| `apt update` | Updates the package list from repositories. |
| `apt upgrade` | Upgrades all installed packages to the latest versions. |
| `apt install <package>` | Installs the specified package. |
| `apt remove <package>` | Removes the specified package. |
| `apt purge <package>` | Removes a package and its config files. |
| `apt autoremove` | Removes unnecessary packages. |
| `apt search <package>` | Searches for a package. |
| `dpkg -i <package.deb>` | Installs a .deb package. |
| `dpkg -r <package>` | Removes a package installed via dpkg. |
| `dpkg -l` | Lists installed packages. |
| `dpkg -s <package>` | Displays information about a package. |

### 6. Terminal and Shell
| Command | Description |
|---------|-------------|
| `clear` | Clears the terminal screen. |
| `history` | Shows a list of previously run commands. |
| `alias <name>=<command>` | Creates a shortcut for a command. |
| `unalias <name>` | Removes an alias. |
| `man <command>` | Opens the manual page for a command. |

### 7. Networking and Connectivity
| Command | Description |
|---------|-------------|
| `ifconfig` | Displays network configuration (deprecated; use `ip a`). |
| `ip a` | Shows IP addresses and network interfaces. |
| `ping <host>` | Sends ICMP echo requests to test connectivity. |
| `netstat -tuln` | Displays active listening ports and their states. |
| `ss -tuln` | Modern alternative to netstat. |
| `nmap <host>` | Scans the host for open ports and services. |
| `ssh <user>@<host>` | Connects to a remote host via SSH. |
| `scp <file> <user>@<host>:<path>` | Securely copies files to a remote server. |
| `rsync -av <source> <destination>` | Synchronizes files and directories. |

### 8. Process and System Monitoring
| Command | Description |
|---------|-------------|
| `top` | Displays active processes and system resource usage. |
| `htop` | Interactive process viewer (requires installation). |
| `ps aux` | Shows all running processes. |
| `kill <PID>` | Terminates a process with the specified Process ID. |
| `killall <name>` | Kills all processes by name. |
| `xkill` | Click on a window to kill it (GUI). |
| `uptime` | Shows how long the system has been running. |
| `uname -a` | Shows detailed system information. |
| `hostname` | Displays or sets the system hostname. |

### 9. Search Utilities
| Command | Description |
|---------|-------------|
| `locate <file>` | Searches for the location of a file. |
| `updatedb` | Updates the database used by `locate`. |
| `find <dir> -name <file>` | Searches for a file in a directory hierarchy. |
| `grep <pattern> <file>` | Searches for a pattern in a file. |
| `egrep <pattern> <file>` | Extended grep. |
| `fgrep <string> <file>` | Searches for a fixed string. |

### 10. Compression and Archiving
| Command | Description |
|---------|-------------|
| `tar -xvf <file>.tar` | Extracts a tar archive. Use `-czvf` to create one. |
| `zip <file>.zip <files>` | Compresses files into a .zip archive. |
| `unzip <file>.zip` | Extracts files from a .zip archive. |
| `gzip <file>` | Compresses a file. |
| `gunzip <file.gz>` | Decompresses a .gz file. |

### 11. Internet and Downloads
| Command | Description |
|---------|-------------|
| `wget <url>` | Downloads files from the internet. |
| `curl <url>` | Transfers data from or to a server using URL. |

### 12. Service Management
| Command | Description |
|---------|-------------|
| `service <service> start/stop/restart` | Manages system services. |
| `systemctl <action> <service>` | Controls systemd services (start, stop, restart, enable). |
| `journalctl` | Views system logs managed by systemd. |

### 13. Scheduling Tasks
| Command | Description |
|---------|-------------|
| `crontab -e` | Edits the current user's cron jobs. |
| `crontab -l` | Lists the current user's cron jobs. |
| `at <time>` | Schedules a task at a specific time. |

### 14. Disk and Storage Management
| Command | Description |
|---------|-------------|
| `mount <device> <dir>` | Mounts a filesystem. |
| `umount <dir>` | Unmounts a mounted filesystem. |
| `df -h` | Displays disk space usage. |
| `du -sh <dir>` | Displays directory size. |
| `lsblk` | Lists block devices. |
| `blkid` | Shows block device UUIDs and labels. |
| `fdisk -l` | Lists partitions on all devices. |
| `parted` | CLI tool to manage disk partitions. |

### 15. System Control
| Command | Description |
|---------|-------------|
| `exit` | Logs out from the current shell session. |
| `reboot` | Reboots the system. |
| `shutdown now` | Shuts down the system immediately. |

### 16. Date, Time, and Miscellaneous
| Command | Description |
|---------|-------------|
| `date` | Displays the current date and time. |
| `cal` | Displays a calendar. |
| `bc` | Command line calculator. |
| `echo <text>` | Displays a line of text. |
| `env` | Displays environment variables. |
| `export VAR=value` | Sets an environment variable. |
| `printenv` | Prints environment variables. |
| `read <var>` | Reads input into a variable. |
| `sleep <seconds>` | Pauses for specified time. |
| `watch <command>` | Repeats a command at intervals. |
