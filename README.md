# Linux Cheatsheet

Linux notes I am writing while studying for a career in cybersecurity.

## Navigation

- `pwd` - shows the folder you are currently in ("print working directory")
- `ls` - lists the files and folders in the current folder
- `ls -a` - lists hidden files too (the ones starting with `.`)
- `ls -l` - lists files with details: permissions, owner, size and date
- `cd <folder>` - moves into a folder ("change directory")
- `cd ..` - goes up one level, to the parent folder
- `cd ~` - goes back to your home folder

## Files

- `mkdir <folder>` - creates a new folder
- `touch <file>` - creates a new empty file
- `cat <file>` - shows the content of the file
- `file <file>` - shows the type of the file
- `rm <file>` - permanently removes the file
- `rm -r <folder>` - permanently removes a folder and everything inside it

## Terminal

- `ssh <user>@<server> -p <port>` - connects to a remote computer / server in an encrypted way
- `exit` - closes the connection
- `man <command>` - opens the manual of a command, press q to exit
- `Ctrl + C` - stops the running command
- `reset` - cleans up the terminal
- `Ctrl + Shift + C` - copy in the terminal
- `Ctrl + Shift + V` - paste in the terminal

## Search and filter

- `find <where> <options>` - searches for files starting from a folder, using the clues you give it
- `grep <word> <file>` - shows only the lines that contain the word: the "highlighter"
- `sort <file>` - sorts the lines in alphabetical order
- `uniq -u` - keeps only the lines that appear once; works only on adjacent lines, so use it after `sort`
- `strings <file>` - extracts only the readable text from a binary file
- `wc -l` - counts the lines
- `<command> | <command>` - the pipe: sends the output of the first command to the second one
- `<command> 2>/dev/null` - hides error messages (`2` = error channel, `/dev/null` = trash)