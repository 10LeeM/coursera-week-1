# coursera-week-1
Initializing the folder as a Git repository
git init

Checking your Git repository status
Type the following at the prompt to check your Git repository's status:
git status

Adding files to the staging area

To add files to the staging area of your Git repository, type:
git add .

Commiting to the Git repository

To commit the current staging area to your Git repository, type:
git comit -m "commit message"

Checking the log of Git commits

To check the log of the commits to your Git repository, type
git log oneline

The git checkout command operates upon three distinct entities: files, commits, and branches. In addition to the definition of "checkout" the phrase "checking out" is commonly used to imply the act of executing the git checkout command.
Checking out branches is similar to checking out old commits and files in that the working directory is updated to match the selected branch/revision
git checkout

 Resetting the Git repository
To discard the effect of the previous operation and restore a file e.g  index.html to its state at the end of a commit, type:
git reset HEAD <indes.html>
Then type the following at the prompt:
git checkout -- <index.html>

You can also use git reset to reset the staging area to the last commit without disturbing the working directory.
