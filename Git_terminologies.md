# Git Terminologies

## Repository
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


##  Commit
A **commit** is a record of what files you have changed 
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
 
 ## Push
 **Push** the commit in your branch to your new GitHub repo. 
 This allows other people to see the changes you've made.
  If they're approved by the repository's owner, the changes 
  can then be merged into the primary branch.
 
 To push changes onto a new branch on GitHub, we should
  run git push origin our branch name. GitHub will automatically 
 create the branch for you on the remote repository: 
 
 git push origin yourbranchname
 
 ## Pull
 If we refresh the GitHub page, we'll see note saying a branch
  with our name has just been pushed into the repository. 
  ![Compare and Pull](https://cloud.githubusercontent.com/assets/5241432/9189475/da30eb86-3fb6-11e5-934f-ca596a2cac69.png)
 
 
 
  Create a Pull Request (PR)
 A **pull request** (or PR) is a way to alert a repo's owners 
 that you want to make some **changes** to their code. It allows 
 them to review the code and make sure it looks good before 
 putting your changes on the primary branch.
 
 This is what the PR page looks like before you've submitted it
 
 ![Open a pull request](https://cloud.githubusercontent.com/assets/5241432/9189500/4688c07e-3fb7-11e5-99ed-d75b50ed9e48.png)
    
 And this is what it looks like once you've submitted the PR request:
 
 ![Merge pull request](https://cloud.githubusercontent.com/assets/5241432/9189528/b39a7176-3fb7-11e5-87b1-7fed3e63b6bb.png)
 
 You might see a big green button at the bottom that says 'Merge pull request'. Clicking this means you'll merge your changes
  into the primary branch.
  
  Note that this button won't always be green. In some cases 
  it'll be grey, which means you're faced with a merge conflict. 
  
  This is when there is a change in one file that conflicts with a
   change in another file and git can't figure out which version to 
   use. You'll have to manually go in and tell git which version to 
   use.
 
 
 
 



