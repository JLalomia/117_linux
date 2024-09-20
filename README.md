# Command Line Survival Guide for GIT and Linux

## Top 10 Linux Commands

| Command  | Description             | Example             |	
|---------------------------|-----------------|-------------|	
| mkdir    | Creates a new directory | mkdir myFolder -  creates a directory named myFolder |	
| cd       | Changes the current directory | cd /home/user/Downloads - Navigates to the Downloads directory |	
| ls       | Lists the directory contents | ls - Lists all the files and directories in the current directory |		
| pwd      | Displays the current working directory | pwd - Shows the full path of the current directory, e.g. /home/user/myFolder |	
| rm       | Removes files or directories | rm file.txt - Deletes file.txt |	
| chmod    | Changes file or directory permissions | chmod 755 prog.c - Gives the owner full permissions (read, write, exdcute), and others only the read and execute permissions for prog.c |	
| cp       | Copies files or directories | cp file.txt backup.txt - Copies the contents of file.txt to backup.txt |	
| mv       | Moves or renames files or directories | mv file.txt /path/to/new/location - moves file.txt to new location |	
| touch    | Creates an empty file or updates the timestamp of an existing file | touch newFile.txt - Creates an empty file called newFile.txt. If the file already exists, it updates its timestamp |	
| cat      | Displays the content of a file or concatenates multiple files | cat file1.txt file2.txt > combined.txt - Combines the contents of file1.txt and file2.txt into combined.txt |	

## Top 10 GIT Commands

| Command  | Description             | Example             |
|---------------------------|-----------------|-------------|
| git init | Initializes a new Git repository in the current directory | git init - Initializes a Git repository in the current directory, creating a .git folder |	
| git clone | Copies a repository from a remote server to your local machine | git clone https://github.com/user/repo.git - Clones a remote repository located at the URL to your local machine |	
| git add | Stages changes to be commited | git add file.txt - Stages file.txt for the next commit |	
| git status | Shows the status of your working directory, including staged, unstaged, and untracked files | git status - Shows modified, added, or deleted files |	
| git commit | Commits the staged changes with a descriptive message | git commit -m 'Initial Commit' - Commits the changes staged by git add with the message "Initial Commit" |	
| git push | Pushes the committed changes to a remote repository | git push origin main - Pushes the committed changes from the main branch to the remote repository origin |	
| git pull | Fetches and merges changes from a remote repository into your local branch | git pull origin main - Pulls and merges updates from the main branch |	
| git branch | Lists, creates, or deletes branches | git branch tree-branch - Creates a new branch called tree-branch |		
| git checkout | Switches to another branch or restores working files| git checkout tree-branch - Switches to tree-branch |	
| git merge | Merges changes from one branch into the current branch | git merge tree-branch - Merges tree-branch into the current branch |	
