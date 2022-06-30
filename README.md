## Cheatsheet containing a list of useful commands when working within CLI / terminal. 
### GIT Commands for viewing branches and creating one if need be: 
`git status` 
* see **current** working branch 
`git branch 
* to see **local** branches 
`git branch -r`
* to see **remote** branches 
`git branch -a`
* to see **all local and remote** branches 
`git checkout -b my_branch_name`
* create a **new** branch 
`git checkout my_branch_name` 
* **switch to a branch** in **local** repo 
`git pull` <br />
`git checkout --track origin/my_branch_name`
* **switch to a branch** that came from a **remote** repo 


### GIT Commands for modifying a branch: 
`git push -u origin my_branch_name`
* push to a branch if your local branch **does not exist on the remote**
`git push`
* push to a branch if your local branch **already exists on the remote
`git merge my_branch_name 
* merge a brach after checking which is your working branch & switching to the right branch 
