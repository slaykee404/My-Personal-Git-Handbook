


**git config --global user.name "Firstname Lastname"**

This name will show who made the changes in the project.

**git config --global user.email "valid-email@example.com"**

This email will be linked to every change you make.
Use the same email as your GitHub account.

**git config --global color.ui auto**

This adds colors to Git commands.
It makes Git easier to read and understand.

**git init**

This command creates a new Git repository.
It tells Git to start tracking files in the folder.

**git clone [url]**

This command copies a project from GitHub to your computer.
It downloads the full repository using the given link.

**git status**

Shows which files are changed, staged, or not tracked.

**git add [file]**

Adds the file to the staging area.
This means the file is ready to be committed.

**git reset [file]**

Removes the file from staging.
Your changes are not deleted.

**git diff**
Shows changes that are made but not added to staging.

**git diff --staged**

Shows changes that are staged but not yet committed.

**git commit -m “[ message]”**

Saves the staged changes as a new version of the project.

**git branch**

Shows all branches.
The * symbol shows the current branch.

**git branch [branch-name]**

Creates a new branch from the current point.

**git checkout**

Moves to another branch.
Your files change to match that branch.

**git merge [branch]**

Adds changes from the given branch into the current branch.

**git log**

Shows all commits made in the current branch.

**git remote add [alias] [url]**
Connects your project to a GitHub repository.
The alias is usually called origin.

**git fetch [alias]**

Downloads updates from GitHub.
It does not change your files.

**git merge [alias]/[branch]**

Updates your current branch using changes from GitHub.

**git push [alias] [branch]**
Sends your local commits to the GitHub repository.

**git pull**

Downloads and applies changes from GitHub to your project.