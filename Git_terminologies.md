# Git Terminologies

## 1. Repository
A Git repository is the .git/ folder inside a project. 
This repository tracks all changes made to files in your project,
 building a history over time. Meaning, if you delete the .git/ folder, 
 then you delete your project’s history.
 
 Now, Let's see how we create a git repository
 
$ cd C:/Users/user/my_project

$ git init

$ git add *.c

$ git add LICENSE

![Create Repsoitory](https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot_2-1.png?width=1007&height=627&name=Git_101_Screenshot_2-1.png)


## 5. Commit
A commit is a record of what files you have changed 
since the last time you made a commit. Essentially, 
you make changes to your repo (for example, adding a 
file or modifying one) and then tell git to put those 
files into a commit.

Commits make up the essence of your project and allow 
you to go back to the state of a project at any point.

So, how do you tell git which files to put into a commit? 
When we make changes to our repo, 
git notices that a file has changed but won't do anything 
with it (like adding it in a commit).

To add a file to a commit, you first need to add it to 
the staging environment. To do this, you can use the 
**git add <filename> ** command 

Once we've used the git add command to add all the files 
we want to the staging environment, we can then tell git 
to package them into a commit using the git commit command as shown below. 

 git commit -m "This is my first commit!"
 

 
 
    
 
 
 
 
 



