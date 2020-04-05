# Git basics commands

Basic commands to get you started with git locally: branching, merging, making commits and viewing git logs.

## To configure git for the first time

`git config --global user.name "Your Name"`

`git config --global user.name "your-email"`

## To initialize git repository in the directory

`git init`

## Check the status of your repository (see tracked, untracked files, files staged for commit etc.)

`git status`

## To create and move to new branch

`git checkout -b branch_name`

## To delete branch

`git branch -d branch_name`

## To move between already created branches

`git checkout branch_name`

## To see all branches and which branch you are on

`git branch`

## To see diff between committed and modified file(s)

`git diff`

`git diff filename`

## To stage files to commit

`git add filename`

## To create commit

### To open new editor to write commit message

`git commit`

### To write commit message directly to command line

`git commit -m "Commit message here"`

### To commit all files and writing commit message directly to command line. Note with this command you don't need git add filename. But be careful as this command takes all modified files to the commit

`git commit -am "Commit message here"`

## To merge another branch to the branch you're currently on

`git merge branch_name`

## To see git log (history)

### Text view

`git log`

### Visualised view

`git log --graph`

### Visualised view with only commit SHA and commit messages

`git log --graph --oneline --decorate`
