# Git-Commands
Include all the commands required to setup git on Linux
Deleting remote branches

To delete a remote branch, you can’t use the git branch command. 
Instead, use the git push command with --delete flag, followed by
the name of the branch you want to delete. You also need to specify the remote name (origin in this case) after git push.

Deleting local branches:
First, we print out all the branches (local as well as remote), using the git branch command with -a (all) flag.
To delete the local branch, just run the git branch command again, this time with the -d (delete) flag, followed 
by the name of the branch you want to delete (test branch in this case).

