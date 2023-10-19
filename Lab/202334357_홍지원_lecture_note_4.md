# Lecture 4 Note 202334357 홍지원

## Shell Command
- pwd
- cd
- ls
- clear
- cp
- mv
- rm
- mkdir
- wildcard
- help commands
- exit

#### $ pwd
Shows current directory sequentially.

#### $ cd (directory name)
Change directory. 
tips: Autocompletion - cd + (directory's first alphabet) + Tab key.

#### $ ls
Lists all subdirectories of the directory. 
```sh
$ ls /bin: Lists the files of /bin directory.
$ ls -l: Lists the files of working directory in long format*.
$ ls -1 /etc /bin: Lists the files in /bin or /etc directory.
$ ls -la: Lists all files in the parent of the working directory in long format.
```
long format* : Way to display a detailed list of files and directories. 
Typically used with the "ls" command, it displays various information about files and directories.
tips: Past Command - pressing "up arrow" makes me reload the directory roaded just before.

#### $ clear
Clear all text of the terminal.


#### $ cp
Copies directories.
```sh
$ cp file1 file2: Silently overwritten with the contents of file1.
$ cp -i file1 file2: same as upper one but use -i option.
$ cp file1 dir1: Copies the contents of file1 inside of directory1.
$ cp -R dir1 dir2: Create a directory name dir1 within dir2 (If dir2 does not exist, created)
```

#### $ mv
Move of rename the directory. 
```sh
$ mv file1 file2: Renames file1 to file2. (If file2 exists, replaced with the contents of file1)
$ mv -i file1 file2: Same as the above, but use -i option to prompt before overwriting.
$ mv file1 file2 dir1: Moves file1 and file2 into directory dir1. (If dir1 does not exist, error)
$ mv dir1 dir2: Renames directory dir1 to dir2. (If dir2 existx, dir is moved within dir2)
```

#### $ rm
Delete the directory permanently.

#### $ mkdir
Make a new directory.

#### wildcard
```sh
* : all filenames.
(first alphabet)* : all filenames begin with that alphabet.
(first alphabet)*.txt : all filenames begin with that alphabet and end with .txt.
Data??? : any filenames begin with Data + followed 3 more characters..
```

#### $ help command
```sh
$ help (Shell Command): provides brief assistance for shell commands.
$ man (Shell Commands): provides detailed manual pages for shell commands.
```

#### $ exit
Exit the terminal.