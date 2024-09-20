# Command Line Survival Guide for GIT and Linux

## Top 10 Linux Commands

1. mkdir - Creates a new directory
EX: mkdir myFolder -  creates a directory named myFolder

2. cd - Changes the current directory
EX: cd /home/user/Downloads - Navigates to the Downloads directory

3. ls - Lists the directory contents
EX: ls - Lists all the files and directories in the current directory

4. pwd - Displays the current working directory
EX: pwd - Shows the full path of the current directory, e.g. /home/user/myFolder

5. rm - Removes files or directories
EX: rm file.txt - Deletes file.txt

6. chmod - Changes file or directory permissions
EX: chmod 755 prog.c - Gives the owner full permissions (read, write, exdcute), and others only the read and execute permissions for prog.c

7. cp - Copies files or directories
EX: cp file.txt backup.txt - Copies the contents of file.txt to backup.txt

8. mv - Moves or renames files or directories
EX: mv file.txt /path/to/new/location - moves file.txt to new location

9. touch - Creates an empty file or updates the timestamp of an existing file
EX: touch newFile.txt - Creates an empty file called newFile.txt. If the file already exists, it updates its timestamp

10. cat - Displays the content of a file or concatenates multiple files
EX: cat file1.txt file2.txt > combined.txt - Combines the contents of file1.txt and file2.txt into combined.txt

## Top 10 GIT Commands

1. git init - Initializes a new Git repository in the current directory
EX: git init - Initializes a Git repository in the current directory, creating a .git folder

2. git clone - Copies a repository from a remote server to your local machine
EX: git clone https://github.com/user/repo.git - Clones a remote repository located at the URL to your local machine

3. git add - Stages changes to be commited
EX: git add file.txt - Stages file.txt for the next commit

4. git status - Shows the status of your working directory, including staged, unstaged, and untracked files
EX: git status - Shows modified, added, or deleted files

5. git commit - Commits the staged changes with a descriptive message
EX: git commit -m 'Initial Commit' - Commits the changes staged by git add with the message "Initial Commit"

6. git push - Pushes the committed changes to a remote repository
EX: git push origin main - Pushes the committed changes from the main branch to the remote repository origin

7. git pull - Fetches and merges changes from a remote repository into your local branch
EX: git pull origin main - Pulls and merges updates from the main branch

8. git branch - Lists, creates, or deletes branches
EX: git branch tree-branch - Creates a new branch called tree-branch

9. git checkout - Switches to another branch or restores working files
EX: git checkout tree-branch - Switches to tree-branch

10. git merge - Merges changes from one branch into the current branch
EX: git merge tree-branch - Merges tree-branch into the current branch
