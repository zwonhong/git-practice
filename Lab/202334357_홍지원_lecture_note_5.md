# Lecture 5 Note 202334357 홍지원

## Shell Command
- " > "
- " >> "
- " < "
- " | "
- echo
- " \ "
- history
- Linux permissions
- Superuser
- Text editors
- Shell script

#### " > "
Redirect output to create and save the output in a file.

#### " >> "
Append output to an extising file. if the file doesn't exist, creates and writes a new file.

#### " < "
Redirect input from a file.

#### " | " (pipelines)
" | "previous command's output = " | " after command's input. 

#### $ echo
Expand its meanings.
```sh
$ echo (comments) : Print comments 
$ echo * : List all file names in the current directory
$ echo ~ : Print the path to the user's home directory.
```

#### " \ "
Egnore line change in multiple lines when entered commands are so long.

#### history
Show previous command history or save it to a text file.

#### Linux permissions
Owner-group-other's read/write/execute permissions.
```sh
777(rwxrwxrwx) : Everyone can read, write, execute.
755(rwxr-xr-x) : Owner can do everything, and all others may read and execute.
700(rwx------) : Only owner can read, write, execute.
666(rw-rw-rw-) : Everyone can read and write.
644(rw-r--r--) : Owner can read and write, others can only read.
600(rw-------) : Owner can read and write, other have no rights.
```
Q: How can i express permission expressions(rwxrwxrwx) to number permission expression(777)?
A: Express alphabet to 1, ' - ' to 0, and change that binary number to decimal number.
(rwx------ => 111 000 000 => 7 0 0)

#### Superuser
Super administrator.
By using "sudo" before commands, you can use superuser's privileges.

#### Text editors
It has 2 options, CHI-based and GUI-based.
```sh
vi, vim
Emacs
nano
gedit
kwrite
```

#### Shell script
You can automate tasks and write programs using commands and control structures in shell.