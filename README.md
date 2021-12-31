## Keeping-Git-Branches-Clean

## Deleting Local Branches
First the local branches must be individually deleted using the following command
> git branch -d branch-name-here
## Deleting remote branches
Finally the following command will automatically clean the equivilant of the local branches deleted previously 
> git remote prune origin
