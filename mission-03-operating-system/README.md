# mission 3 - understand the operating system

## 1. task / objective
check operating system details, observe processes, understand paths and file permissions, and explain os roles

## 2. work completed
ran system commands, filled system exploration table, answered process questions, checked file permissions, and completed os responsibilities table

## 3. commands / tools used
uname -a, whoami, df -h, ps, ls -l

## 4. my understanding

### task 3.1 - explore your operating system

| information explored | what it tells you | your observation (privacy-safe) |
| :--- | :--- | :--- |
| operating system / system details | shows os type and kernel | darwin kernel [redacted] |
| current account identity | shows logged in user | [redacted] |
| available and used storage | shows total and free disk space | size 460gi used [redacted]gi free [redacted]gi |
| system activity snapshot | shows active processes and memory use | list of running processes and cpu usage |

### task 3.2 - understand processes
- what is a process: a program that is currently running in memory
- what does the pid column represent: unique process id number assigned by os to identify each process
- two examples of processes: python3 and zsh

### task 3.3 - understand paths and permissions
- absolute path gives full location from root folder like /Users/[redacted]/digital-detective-8039
- relative path gives location from current folder like mission-01-computer-basics/README.md
- permission letters: r means read, w means write, x means execute
in practice folder, file permissions were rw-r--r-- so owner can read and write the file

| permission | meaning | example |
| :--- | :--- | :--- |
| r - read | lets you read file content | opening text file |
| w - write | lets you edit or modify file | saving changes to file |
| x - execute | lets you run file as a program | running a script |

### task 3.4 - explain operating-system responsibilities

| os responsibility | your explanation | example |
| :--- | :--- | :--- |
| process management | controls running programs and allocates cpu time | running browser and terminal at same time |
| memory management | allocates ram to apps and frees it when closed | giving ram memory to python |
| device management | manages hardware components with drivers | sending print job to printer |
| file management | organizes files and folders on storage drive | saving files into folders |
| user interface / shell | provides ways for user to control computer | terminal cli and graphical desktop |
| security and permissions | protects files and checks user access rights | asking user password before system changes |

## 5. difficulties faced
no major difficulties

## 6. how i resolved them
not applicable

## 7. evidence / files
system inspection notes and permission details in this readme

## 8. commit details
commit message: document operating system and file management
