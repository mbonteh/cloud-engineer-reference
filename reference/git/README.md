
# Module 0: Git - Learn foundamentals of Git, GitHub, and Version Control

Working Directory <-add-> Staging Area <-commit-> Local (Git) Repository <-push-> Remote (GitHub/CodeCommit) Repository

## Local Repository

```sh
# Initialize a local repository
git init

# Add or remove files to/from the staging area
git add <file/folder>
git rm <file/folder>

# View commit history
git log

# Check current status
git status

# See differences in a file
git diff <file>

# Roll back changes from repository to working directory
git checkout <file>

# Create and manage branches
git branch <branch-name>
git checkout <branch-name>

# Add a remote repository
git remote add origin <url>

# Push commits to a remote repository
git push -u <remote-name> <branch-name>

# Clone a remote repository locally
git clone <repository-url>

# Merge branches
git merge <branch-name>

# Rebase changes onto a branch
git rebase <base-branch>





