#0x00. Shell, basics

##man or help:

cd
Description: Change the current directory.
Usage: cd [directory]
Example: cd /home/user/Documents
ls
Description: List directory contents.
Usage: ls [options] [directory]
Example: ls -l /home/user
pwd
Description: Print working directory.
Usage: pwd
Example: pwd
less
Description: View file contents one screen at a time.
Usage: less [file]
Example: less /var/log/syslog
file
Description: Determine file type.
Usage: file [file]
Example: file /bin/bash
ln
Description: Create a link to a file.
Usage: ln [options] target [linkname]
Example: ln -s /usr/local/bin/python3 /usr/bin/python
cp
Description: Copy files and directories.
Usage: cp [options] source destination
Example: cp file1.txt /home/user/Documents
mv
Description: Move or rename files and directories.
Usage: mv [options] source destination
Example: mv oldname.txt newname.txt
rm
Description: Remove files or directories.
Usage: rm [options] file
Example: rm -rf /home/user/oldfiles
mkdir
Description: Create directories.
Usage: mkdir [options] directory
Example: mkdir newfolder
type
Description: Display the type of command.
Usage: type [command]
Example: type ls
which
Description: Locate a command.
Usage: which [command]
Example: which python
help
Description: Display help for a built-in command.
Usage: help [command]
Example: help cd
man
Description: Display the manual for a command.
Usage: man [command]
Example: man ls

Learning Objectives Explained
General
RTFM (Read The Fine Manual)

This phrase suggests consulting the manual or documentation to find answers before asking for help.
Shebang

The #! characters at the beginning of a script file, followed by the path to an interpreter, which tells the system how to execute the file.
Example: #!/bin/bash
The Shell

A shell is a command-line interpreter that provides a user interface for the Unix operating system. It allows users to execute commands and scripts.
Terminal vs Shell

A terminal is a program that opens a window for you to interact with the shell. The shell is the actual command-line interpreter.
Shell Prompt

The shell prompt is the text displayed in the terminal that indicates the shell is ready to accept input.
Example: $ or #
Using History

The history command allows you to view, repeat, and manage previously executed commands.
Basic usage: history
Navigation
Commands: cd, pwd, ls

cd: Change directory.
pwd: Print working directory.
ls: List directory contents.
Navigating the Filesystem

. refers to the current directory.
.. refers to the parent directory.
Working Directory

The current directory you are in. Use pwd to print and cd to change it.
Root Directory

The top-level directory in the filesystem, represented by /.
Home Directory

The personal directory of a user. Navigate to it with cd ~.
Root Directory vs Home Directory of User Root

The root directory (/) is the system's top directory. The root user's home directory is /root.
Hidden Files

Files starting with . are hidden. List them with ls -a.
Command cd -

Switches to the previous directory.
Looking Around
Commands: ls, less, file

ls: List directory contents.
less: View file contents.
file: Determine the file type.
Using Options and Arguments

Commands can take options (like -l for ls) and arguments (like filenames).
ls Long Format

ls -l provides detailed information about files and directories.
A Guided Tour
Command ln

Creates links between files.
ln: Creates hard links.
ln -s: Creates symbolic links (symlinks).
Common Directories

/bin, /etc, /home, /lib, /tmp, /usr, etc.
Symbolic Link vs Hard Link

Symbolic links are shortcuts pointing to files. Hard links are additional names for the same file.
Manipulating Files
Commands: cp, mv, rm, mkdir

cp: Copy files and directories.
mv: Move or rename files and directories.
rm: Remove files or directories.
mkdir: Create directories.
Wildcards

Special characters (*, ?, []) used to match filenames.
Working with Commands
Commands: type, which, help, man

type: Display information about command type.
which: Locate a command.
help: Display help for built-in commands.
man: Display manual pages for commands.
Kinds of Commands

Built-in commands: Part of the shell.
External commands: Separate executable files.
Alias

A shortcut for a command or series of commands.
help vs man

help: For shell built-ins.
man: For external commands and detailed documentation.
Reading Man Pages
Reading a Man Page

Use man [command].
Man Page Sections

1: User commands.
2: System calls.
3: Library functions.
