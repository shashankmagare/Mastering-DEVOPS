## File System Navigation
15 `pwd` - Prints the working directory (shows your exact current location in the file system).
16 `ls` - Lists files and directories in your current location.
17 `cd <directory>` - Changes the current directory (e.g., `cd /` for root, `cd ..` to move up one level, or `cd /home/user` for an absolute path).

## File & Directory Management
18 `mkdir <directory>` - Creates a new folder (e.g., `mkdir azu`).
19 `rmdir <directory>` - Removes an empty folder (e.g., `rmdir shsh`).
20 `touch <file>` - Creates a new, empty file (e.g., `touch hello.txt`).
21 `cp <source> <destination>` - Copies a file to a new location (e.g., `cp bye.txt azu`).
22 `cd ~` - The tilde (`~`) is a shortcut that quickly returns you to your home directory (e.g., `/home/shashank`), no matter where you are in the system.
23 `cp -r <source_dir> <destination_dir>` - The `-r` flag stands for "recursive." It allows you to copy an entire directory and all the files inside it (e.g., `cp -r aws cloud`).
24 `mv <source> <destination>` - Moves a file or directory to a new location. It is also the command used to **rename** files/folders (e.g., `mv azu cloud`).
25 `rm <file>` - Removes/deletes a file permanently (e.g., `rm hello.txt`). *Note: Unlike `rmdir` which only deletes empty folders, `rm` deletes files. Use with caution!*

## Text Editing & Searching
26 `vim <file>` - Opens a file in the Vim text editor. (Pro tip: `vim -o file1 file2` opens multiple files in a split screen).
27 `grep <search-term> <file>` - Searches for a specific word or pattern inside a file (e.g., `grep file hello.txt`).

## System Manuals (Help)
28 `man <command>` - Opens the built-in manual page for any command to show how it works (e.g., `man vim` or `man ls`). Press `q` to quit the manual.

