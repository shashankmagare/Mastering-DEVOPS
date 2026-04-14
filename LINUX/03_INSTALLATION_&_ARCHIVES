## Privilege Escalation
`sudo su` - Switches you to the root user (Superuser) shell, granting you full administrative privileges for all subsequent commands without having to type `sudo` every time.

## Downloading & Package Management
29 `wget <url>` - Downloads files directly from the internet to your current directory (e.g., downloading `.deb` files or GPG keys).
30 `sudo apt update` - Refreshes your system's local list of available packages and updates from the configured repositories. Always run this before installing new software!
31 `sudo apt install <package>` - Installs a software package from the official repositories (e.g., `sudo apt install zip java terraform`).
32 `sudo apt remove <package> -y` - Uninstalls a software package. The `-y` flag automatically answers "yes" to any confirmation prompts.
33 `sudo dpkg -i <file.deb>` - Manually installs a downloaded Debian package file (`.deb`), rather than downloading it through `apt`.

## Archiving & Compression (Zip & Tar)
34 `zip -r <archive.zip> <folder_or_file>` - Compresses files or folders into a `.zip` file. The `-r` flag ensures it recursively includes everything inside a folder.
35 `unzip <archive.zip> -d <destination>` - Extracts a `.zip` file. The `-d` flag lets you specify exactly which directory to extract the contents into (e.g., `unzip myfile.zip -d /tmp`).
36 `tar -cf <archive.tar> <file>` - Creates (`-c`) a new tar archive file (`-f`) bundling files together without compressing them. 
37 `tar -xf <archive.tar>` - Extracts (`-x`) the contents of a tar archive file (`-f`).

## Advanced Command Execution (Chaining & Piping)
38 `rm -f <file>` - The `-f` (force) flag forcefully removes a file without asking for confirmation, even if it is read-only.
39 `command1 && command2` - The `&&` operator chains commands together. The second command will only run if the first command succeeds (e.g., `sudo apt update && sudo apt install terraform`).
40 `|` (The Pipe Operator) - Takes the output of the command on the left and passes it as the input to the command on the right. (You used this to download the HashiCorp GPG key with `wget -O -` and pass it to `gpg --dearmor`).
