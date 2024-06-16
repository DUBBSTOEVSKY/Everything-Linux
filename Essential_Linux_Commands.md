# Essential Linux Commands

This file contains a list of essential Linux commands that I've found useful in my Linux journey. Feel free to use this as a reference.

## Navigation

- `pwd`: Print the current working directory
- `ls`: List directory contents
  - `ls -l`: List detailed directory contents
  - `ls -a`: List all files, including hidden files
- `cd`: Change directory
  - `cd ~`: Change to the home directory
  - `cd ..`: Change to the parent directory
- `mkdir`: Create a new directory
- `rmdir`: Remove a directory (must be empty)

## File Management

- `touch`: Create an empty file or update the timestamp of an existing file
- `cp`: Copy files and directories
- `mv`: Move or rename files and directories
- `rm`: Remove files and directories
  - `rm -r`: Remove directories recursively
  - `rm -f`: Force removal without confirmation

## File Permissions

- `chmod`: Change file permissions
- `chown`: Change file owner and group
- `chgrp`: Change group ownership of files

## Text Processing

- `cat`: Display the contents of a file
- `less` or `more`: View file contents one page at a time
- `grep`: Search for a pattern in files
- `sed`: Stream editor for filtering and transforming text

## System Information

- `uname`: Display system information
  - `uname -a`: Display all system information
- `df`: Display disk space usage
- `du`: Display disk usage of files and directories

## Process Management

- `ps`: Display information about processes
  - `ps aux`: Display all processes
- `kill`: Terminate processes
  - `kill -9`: Forcefully terminate a process

## Package Management (apt package manager)

- `apt-get`: Command-line tool for handling packages
  - `apt-get update`: Update the list of available packages
  - `apt-get upgrade`: Upgrade all installed packages
  - `apt-get install`: Install new packages
  - `apt-get remove`: Remove packages
  - `apt-get autoremove`: Remove unused dependencies

## Networking

- `ifconfig` or `ip addr`: Display network interface information
- `ping`: Send ICMP echo requests to a network host
- `netstat`: Display network connections, routing tables, and interface statistics
- `ssh`: Securely connect to a remote system
- `scp`: Securely copy files between systems

## Miscellaneous

- `history`: Display command history
- `man`: Display manual pages for commands
- `tar`: Archive files
- `zip`/`unzip`: Compress and decompress files

