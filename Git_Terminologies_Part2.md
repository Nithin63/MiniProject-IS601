# Git Terminologies

## *Cloning a repository*

When you create a repository on GitHub, it exists as a remote repository.
 You can clone your repository to create a local copy on your computer and 
 sync between the two locations.
 
 About cloning a repository
 You can **clone** a repository from GitHub to your local computer to
  make it easier to fix merge conflicts, add or remove files, and push
   larger commits. When you clone a repository, you copy the repository f
   rom GitHub to your local machine.
 
 Cloning a repository pulls down a full copy of all the repository data that
  GitHub has at that point in time, including all versions of every file 
  and folder for the project. You can push your changes to the remote 
  repository on GitHub, or 
 pull other people's changes from GitHub
 
##### Steps:
 1. On GitHub, navigate to the main page of the repository.
 
 2. Above the list of files, click  Code.
 
 3. To clone the repository using HTTPS, under "Clone with HTTPS", click .
  To clone the repository using an SSH key, including a certificate issued
   by your organization's SSH certificate authority, click Use SSH,
    then click . To clone a repository using GitHub CLI, click Use GitHub
     CLI, then click .
     
 ![Git Clone](https://docs.github.com/assets/images/help/repository/https-url-clone-cli.png)
 
4. create your local clone.
   
   $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
   
   
   
## *Fork a repo*

A **fork** is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting 
the original project.

Most commonly, forks are used to either propose changes to someone else's project or to use someone else's
 project as a starting point for your own idea.
 
 *Fork an example repository*
 
 Forking a repository is a simple **two-step process**. We've created a repository for you to practice with.
 
 On GitHub, navigate to the Nithinreddy127/MiniProject-IS601 repository.
 In the top-right corner of the page, click Fork.
 
 ![fork](https://docs.github.com/assets/images/help/repository/fork_button.jpg)
 
 **Keep your fork synced**
   You might fork a project to propose changes to the upstream, 
 or original, repository. In this case, it's good practice to 
 regularly sync your fork with the upstream repository. 
 
 
 ## *Branch*
 Branches are just pointers to commits. 
 
 When you create a branch, all Git needs to do is create
  a new pointer, it doesn’t change the repository in any other way.
   If you start with a repository that looks like this:
   ![image](https://wac-cdn.atlassian.com/dam/jcr:b0e2f237-9337-4385-be22-43f623e133d0/03.svg?cdnVersion=1252)
 
 Then, you create a branch using the following command:
 
 git branch crazy-experiment
 
 The repository history remains unchanged.
  All you get is a new pointer to the current commit:
 
 ![image1](https://wac-cdn.atlassian.com/dam/jcr:b0e2f237-9337-4385-be22-43f623e133d0/03.svg?cdnVersion=1252)
  
  ## *Master Branch*
  
  Master branch is the main working branch created when you pushed 
  your file for the first time into GIT repository.
   Develop or any other branch is typically created by Admin
    to restrict developers to make any changes in master branch.
     As doing this without proper review and testing will break the
      working of application.
 
   
