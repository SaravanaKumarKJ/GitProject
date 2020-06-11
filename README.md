## Branching commands

git branch
- This command will list all the available branches. Also, it indicates the current active branch with a astreik symbol (*) at the front of the branch name.

git branch {branch name}
- This command will create a branch locally from master or the current active branch.

git checkout {branch name}
- This command switches the current active branch to the new branch.

git push -u origin {branch name}
- This command will push the changes from local {branch name} to the remote repository. This will also create a remote branch with the same {branch name}

## Merge strategies

git merge {branch name}
- This command will merge the contents of {branch name} to the current active branch.