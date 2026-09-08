# Basic Linux System & Diagnostic Commands

Here is a list of common commands used for checking system information, networking, and processes on a Linux machine (e.g., Ubuntu).

## System Information
1. cat /proc/cpuinfo - Displays CPU architecture and details. 
2. free -m - Shows free and used memory (RAM) in megabytes.
3. df -h - Displays disk space usage in human-readable format (GB, MB). 
4. cat /etc/os-release - Shows detailed information about the Linux distribution release.
5. uname -r - Prints the exact version of the Linux kernel currently running.

## Networking
6. ip address - Shows IP addresses and network interfaces.
7. ip config - (Note: usually `ifconfig` or `ip a` on Linux, but used to check IP configuration).

## Process Management
8. ps - Displays a snapshot of current running processes for the active shell.
9. ps -ef - Shows a full-format list of all running processes on the system.
10. ps -e - Shows all processes running on the system.
11. htop - An interactive and real-time process viewer (similar to `top`, but more user-friendly).

## Environment & Shell
12. printenv - Prints all environment variables.
13. echo $SHELL - Outputs the path to the current shell being used (e.g., `/bin/bash`).
14. history - Displays the command history for the current user session. 
