# Usefull-git-Commands
A list of useful git commands.

### Git commands

This is a list of useful git commands.

#### Add repos and files and push new code to github
`git clone <link>` - brings in files from github repository onto your machine

`git status` - shows what files are not tracked by github

`git add <file>` - adds on local machine onto github. use '.' instead of file to add all untracked files. Remember to save files first. If file has already been created you can skip this and go use `git commit -am "description (?)".

`git reset <file/commit hash>` removes file/s that had been previously added. Can use `git reset` to remove all added files.

`git reset HEAD~<n>` - reverse commits n commits back.

`git reset --hard <file/commit hash>` - completely removes all file changes from that commit.

`git commit -m "Name" -m "Description"` - commits all file changes. Second -m is optional.

`git push` - pushes code to live remote repository that was added in git add and git commit commands.

`git init` - Initializes new repository into git. Do this when creating a new directory.

`git remote add origin <link>` - connects to remote repository.

`git remote -v` - lists all remote repositories that are connected to.

`git push -u origin master` - use this to do the first git push for a newly connected to repository. Afterwords can use regular `git push` command.

`git log` - prints a log of all previous gits. Press 'ENTER' to show more commits. Press 'q' to exit the logs.

#### Work with git branches
`git branch` - shows the existing branches of a github repo and which one is currently selected.

`git checkout -b <feature name>-<description/numeration>` - creates new branch in repository.

`git checkout <branchname>` - will switch the branch being used.

`git push -u origin <branchname>` - will push the branches changes to the repository. After single use for the new branch, use the normal `git push` function.

`git diff <branchname to compare to>` - shows the difference between the branch that is currently open and the selected branch. Press 'ENTER' to continue reading differences. Press 'q' to exit.

`git merge <branchname>` - merges the named branch with the branch that is currently open.

`git pull` - pulls code that was added to the github. Do this after the merge.

`git branch -d <branchname>` - deletes the specified branch.

### Other useful commands
`cd ../<filename>` - changes the directory in the terminal.
