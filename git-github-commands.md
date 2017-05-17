# Git & GitHub Commands

### Clone a repository
````
$ git clone <pathToRepository>
````
### Check Git status
````
$ git status
````
### Add all files to staging area
````
$ git add --all
````
### Commit files to repository
````
$ git commit -m 'write a commit message'
````
### Create a new branch
Make sure all files are committed first!
````
$ git branch <branchName>
````
### See all branches
````
$ git branch -av
````
### Checkout / switch to a branch
````
$ git checkout <branchName>
````
### Create and checkout a branch
````
$ got checkout -b <branchName>
````
### Merge branches
- Checkout the branch you want to merge into
- Use the below command with the name of the branch you want to merge into the current branch
````
$ git merge <branchName>
````
