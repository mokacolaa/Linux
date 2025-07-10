# Linux Basics

## File System Hierarchy

- `/home`: User directories where personal files are stored  
- `/etc`: System-wide configuration files  
- `/var`: Variable data files like logs and databases  
- `/usr`: User programs and libraries (read-only system files)  
- `/bin` and `/sbin`: Essential binaries and system binaries  
- Understanding **absolute paths** (starting with `/`) vs **relative paths** (relative to current directory)

## Basic Commands

- `ls` — list directory contents  
  - Common flags: `-l` (long format), `-a` (show hidden files)  
- `cd` — change directory  
  - `cd ~` or just `cd` returns to home directory  
  - `cd ..` moves up one directory  
- `pwd` — print working directory (shows current location)  
- `cat` — display file contents  
- `echo` — print text or variables to terminal  
- `touch` — create empty files or update timestamps  
- `mv` — move or rename files/directories  
- `rm` — remove files (`-r` for directories)  
- `mkdir` — create directories  
- `head` / `tail` — show beginning or end of files  
- `grep` — search text patterns within files  
- `find` — search for files and directories by name or criteria

## Understanding Command Options and Flags

- Most commands support flags to modify behavior  
- Flags typically start with `-` or `--` (e.g., `ls -l`, `rm -rf`)  
- Use `man <command>` to read detailed documentation  

## Permissions

- File permissions control read (r), write (w), and execute (x) access for:  
  - User (owner)  
  - Group  
  - Others  
- `ls -l` shows permissions and ownership details  
- `chmod` — change permissions  
  - Symbolic (e.g., `chmod u+x file`) or numeric (e.g., `chmod 755 file`) modes  
- `chown` — change file owner and group  

## Users and Groups

- Understanding users and groups for access control  
- Switching users with `su` or `sudo` for administrative tasks  

## Working with Processes

- `ps` — list running processes  
- `top` — real-time process monitoring  
- `kill` — terminate processes by PID  

## Input and Output Redirection

- Redirect output to files: `>` (overwrite), `>>` (append)  
- Redirect input from files: `<`  
- Pipe output between commands: `|`  

## Environment Variables and Shell Configuration

- Viewing variables: `echo $VARIABLE`    
- Persistent configuration via `.bashrc`, `.zshrc`  

## Text Editing and Navigation

- Basic file editing with `nano` and `vim`  
- Moving through files and saving changes  

## Networking Basics

- `ssh` — securely connect to remote servers  
- `scp` — copy files over SSH  
- Checking network configuration with `ifconfig` or `ip`  

