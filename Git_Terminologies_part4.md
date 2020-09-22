# Git Terminologies

## Checkout

The git checkout command lets you navigate between the branches created by git branch. 
Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch. 
Think of it as a way to select which line of development you’re working on.

The git checkout command may occasionally be confused with git clone. 
The difference between the two commands is that clone works to fetch code from a remote repository,
alternatively checkout works to switch between versions of code already on the local system.

#### Checkout Syntax:

- ###### To create a new branch: *git checkout -b*

- ###### Navigate to existing branch: *git checkout existing-branch*

## Status

The git status command displays the state of the working directory and the staging area. 
It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git. 
Status output does not show you any information regarding the committed project history.

#### Status Syntax:

- ###### **List which files are staged, unstaged, and untracked.** :  ***git status***
