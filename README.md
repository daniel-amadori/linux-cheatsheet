# Linux Cheatsheet

Linux notes I am writing while studying for a career in cybersecurity.

## Search and filter

- `find <where> <options>` - searches for files starting from a folder, using the clues you give it
- `grep <word> <file>` - shows only the lines that contain the word: the "highlighter"
- `sort <file>` - sorts the lines in alphabetical order

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