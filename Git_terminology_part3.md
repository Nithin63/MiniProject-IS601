# Git Terminology

## Remote :
The **Remote** command helps us to manage connection to remote repositories.
It allows us to show which remotes are currently connected and can aslo add new connection or can remove the existing one.
It has some important ***options*** to use with the remote command.

### The important options as follows:
* ### add
 
 The syntax is : add \<shortname> <url\>
 
 It creates a new connection to remote repository. The ***shortname*** we provide can later be used instead of the URL when referencing the remote.
 A typical default shortname is **origin:** this is used for the remote which your local repository was cloned from. 
 
 #### eg.
 ##### $ git remote add production https://test@github.com/test/example.git

* ### remove

The syntax is : remove \<name\>

This command will Disconnects the remote from the local repository. 
This will have no effect on the actual remote repository (i.e. the repository itself is not removed / deleted / etc.).

#### eg.
##### $ git remote remove origin

* ### show

The syntax is : show <remote-name> command
 
This command can be used to get more details about a particular remote.
#### eg.
##### $ git remote show origin
