# iMeazure
Data acquisition software first developed by Kirill Bolotin at Cornell, now widely used at Columbia University and further afield.

## Useful git commands:

* `git init` Initializes a Git repository in the current folder
* `git clone <url> <directory name>`
* `git status` Lists changes, including "staged" changes
* `git add <file>` Stages a file
* `git mv <file>` Rename a file
* `git rm` Remove a file. Use **git rm -r <foldername>** to recursively remove all files and folders within
* `git commit -m "did stuff"` Save your changes. Use **'-a'** option on **'git commit'**, which auto removes deleted files with the commit. E.g. **git commit -am "Delete stuff"**
* `git push origin master` Push your latest commit to the origin (github)
* `git pull origin master` Get the latest changes from github
* `git stash` Hide your changes for a moment, resets the working directory
* `git stash pop` Get your changes back
* `git remote add <name> <url>` Add a new remote repository
* `rm -rf <git directory>` Delete a git working directory without complaints
* `git log` View all recent changes. Use **git log --summary** to see more information for each commit. You can see where new files were added for the first time or where files were deleted. It's a good overview of what's going on in the project.
* `git diff HEAD` Look at what is different from our last commit. The HEAD is a pointer that holds your position within all your different commits. By default **HEAD** points to your most recent commit
* `git reset <file>` Unstage files
* `git checkout <file>` Change the file back to how it was at the last commit
* `git branch` List current branches
* `git branch <branchname>` Create a new branch to make seperate commits from the master branch
* `git checkout <branchname>` Switch to a different branch
* `git merge <branchname>` Merge a branch with the current (eg. **master**) branch
* `git branch -d <branchname>` Delete a branch
