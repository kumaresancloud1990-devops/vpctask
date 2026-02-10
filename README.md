Git Repository Setup and Version Control Operations
📌 Objective

This project demonstrates how to:

Create a new local project directory

Add script files

Initialize a Git repository

Create and connect to a remote GitHub repository

Push local code to GitHub

Perform Git operations such as merge, rebase, and stash

🚀 Steps Performed
1. Create a New Directory

A new project directory was created and populated with script files.

mkdir project-folder
cd project-folder

2. Initialize Git Repository

The local directory was converted into a Git repository.

git init

3. Add Files and Commit

All files were staged and committed.

git add .
git commit -m "Initial commit"

4. Create and Link GitHub Repository

An empty GitHub repository was created and linked to the local repository.

git remote add origin git@github.com:kumaresancloud1990-devops/vpctask.git

5. Push Code to GitHub

The code was pushed to the remote repository.

git push -u origin main

🔧 Git Operations Demonstrated
✅ Merge

Used to combine changes from different branches.

git merge branch-name

✅ Rebase

Reapplies commits on top of another base branch.

git rebase branch-name

✅ Stash

Temporarily saves uncommitted changes.

git stash
git stash pop
