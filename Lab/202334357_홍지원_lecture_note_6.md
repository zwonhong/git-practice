# Lecture 6 Note 202334357 홍지원

## GIT Commands
- $ git --version
- $ git config
- $ git init
- $ git status
- $ git add file_name
- $ git rm --cached
- $ git commit -m "commit message"
- $ git branch -m name newname

#### $ git --version
Check the downloaded git's version.

#### $ git config
```sh
$ git config --global user.name "your name"
$ git config --global user.email your_email_address
$ git config --global init.defaultBranch main
-> set up the name of repository
$ git config --list
$ git config --list --show-origin
$ git config user.name
-> check the repository
```
#### $ git init
Initialize a repository in an existing directory.

#### $ git status
Check the present repository status.

#### $ git add file_name
Adding a new file.

If you use command "$ git add .", you can add all changes in the current directory to the Git staging area.

#### $ git rm --cached
Remove a file only from the Git staging area.

Ignoring a file
```sh
*.a : ignore all .a file
!lib.a : ignore all .a file except lib file
/TODO : ignore only /TODO file in the current directory
build/ : ignore all build/ file in any directory
doc/*.txt : ignore doc/notes.txt
doc/**/*.pdf : ignore all .pdf file in doc/directory, any subdirectory
```
#### $ git commit -m "commit message"
Used to finalize and commit changes to a Git repository with a commit message.

#### $ git branch -m name newname
Change branch name 'name' to 'newname'

#### tip
You can use "nano file_name" in order to open and edit "file_name" in nano editor.
