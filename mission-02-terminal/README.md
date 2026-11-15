# mission 2 - become comfortable with the terminal

## 1. task / objective
practice basic terminal commands, do file operations, understand flags and pipes, and learn about package managers

## 2. work completed
ran terminal commands and filled operations table, created terminal-practice folder with files, tested flags and pipe, and checked homebrew

## 3. commands / tools used
pwd, ls, ls -l, ls -lah, cd, mkdir, touch, cp, mv, cat, echo, head, brew

## 4. my understanding

### task 2.1 - explore basic terminal operations

| operation / command name | what it does | what i observed |
| :--- | :--- | :--- |
| current-directory display (pwd) | shows full path of current folder | showed full directory path |
| directory listing (ls) | lists files and folders | showed names of items in folder |
| detailed listing (ls -l) | shows file details with permissions and size | showed details in columns |
| change directory (cd ..) | moves to parent folder | location changed to one folder up |
| create directory (mkdir test) | makes a new folder | created new folder |
| create empty file (touch test.txt) | makes an empty file | created empty text file |
| copy file (cp test.txt copy.txt) | makes a duplicate of a file | created copy file with same content |
| move / rename file (mv copy.txt new.txt) | renames or moves a file | renamed copy.txt to new.txt |
| display file contents (cat test.txt) | prints file contents to terminal | displayed text inside file |

### task 2.2 - practise file changes safely
practiced file changes in terminal-practice folder
created notes.txt, added first line with echo >, added second line with echo >>, verified with cat, copied to notes_backup.txt, renamed to notes_renamed.txt

questions:
- difference between replacing and adding: replacing with > deletes old content and writes new text, adding with >> appends text to the end without deleting anything
- difference between copying and moving: copying creates a duplicate while keeping original file, moving changes location or name and does not keep original
- what current-directory display provides: gives exact full path of current folder so you know where you are
- why directory listing is useful: lets you see what files and folders exist before running commands on them

### task 2.3 - understand flags and pipes
flags change how a command works
ls only shows names of files
ls -lah shows permissions, hidden files starting with dot, and human-readable sizes like k or m

pipes:
ran ls -l | head -n 5
the pipe symbol | takes output from left command and passes it as input to right command
left side ls -l lists all file details, right side head -n 5 takes that list and displays only first 5 lines

### task 2.4 - understand package managers
checked brew --version and saw homebrew 7.0.9
package managers help install, update, and remove software easily from terminal
they handle download and setup automatically so you do not have to install programs manually from websites

## 5. difficulties faced
no major difficulties

## 6. how i resolved them
not applicable

## 7. evidence / files
terminal-practice folder containing notes.txt and notes_renamed.txt

## 8. commit details
commit message: complete terminal and file management mission
