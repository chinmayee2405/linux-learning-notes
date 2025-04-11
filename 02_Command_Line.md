# Linux Journey – Command Line

## Common Commands

This section covers foundational Linux commands and concepts using the bash shell. These tools help users navigate the file system, manage files, and understand the shell environment.

1. The Shell
A shell interprets typed commands and sends them to the OS.
Bash (Bourne Again SHell) is the default shell on most distros.
Prompt format: username@hostname:current_directory$

bash
$ echo "Hello, World!"
2. pwd – Print Working Directory
Displays your current directory.

bash
$ pwd
3. cd – Change Directory
Moves between directories using:

Absolute paths: /home/user

Relative paths: .., ~/, -

bash
$ cd /home/user/Pictures
4. ls – List Directory Contents
Lists files/folders.
Useful flags:

-a: Show hidden files

-l: Long listing

-la: Combine both

bash
$ ls -la
5. touch – Create Empty Files
bash
$ touch newfile.txt
6. file – Identify File Type
bash
$ file image.jpg
7. cat – View File Contents
View or combine files.

bash
$ cat file1.txt file2.txt
8. less – View Large Files
Scrollable viewer:

q: quit

g: top

G: bottom

/search: search

bash
$ less longfile.txt
9. history – View Command History
Shows previous commands.

Shortcuts:

Ctrl + R: Reverse search

clear: Clear terminal

bash
$ history
10. cp – Copy Files/Directories
Flags:

-r: Recursive

-i: Prompt before overwrite

bash
$ cp -r folder/ /destination/
11. mv – Move/Rename
Also used to rename files.
Flags:

-i: Prompt

-b: Backup

bash
$ mv oldname.txt newname.txt
12. mkdir – Make Directory
-p: Create nested structure

bash
$ mkdir -p books/fiction/magic
13. rm – Remove Files/Directories
Flags:

-i: Confirm

-r: Recursive

-f: Force

bash
$ rm -rf unwanted_folder/
14. find – Search for Files
bash
$ find /home -name file.txt
15. help – Bash Built-in Help
bash
$ help echo
16. man – Manual Pages
Full documentation for commands.

bashs
$ man ls
17. whatis – Quick Command Summary
bash
$ whatis cat
18. alias – Command Shortcuts
bash
$ alias ll='ls -la'
To make it permanent, add it to ~/.bashrc.

19. exit – Close the Shell
bash
$ exit