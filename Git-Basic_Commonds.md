# Git Commands with Explanations

## Basic Git Setup

### 1. Initialize a Git repository  
`git init`  
Use: Creates a new Git repository in your project folder. This is the first step before using Git.  

### 2. Check the status of files  
`git status`  
Use: Shows the current state of your working directory, including untracked, modified, or staged files.  

## Staging and Committing Changes

### 3. Add all files to the staging area  
`git add .`  
Use: Stages all changed, new, or deleted files for the next commit.  

### 4. Add a specific file to the staging area  
`git add <filename>`  
Use: Stages only a specific file for the next commit.  

## Undoing Changes

### 5. Reset to a previous commit  
`git reset <commit-hash>`  
Use: Moves the branch pointer back to a previous commit, undoing newer commits.  

### 6. Restore a specific file  
`git restore <filename>`  
Use: Discards changes in the working directory and restores the file from the last commit.  

## Connecting to a Remote Repository

### 7. Link local repo to a remote GitHub repository  
`git remote add origin <remote-repo-url>`  
Use: Connects your system folder to a GitHub repository.  

### 8. Verify the remote repository URL  
`git remote -v`  
Use: Shows the remote repository URLs for fetch and push operations.  

## Managing Branches

### 9. Check the current branch  
`git branch`  
Use: Lists all branches and highlights the currently active branch.  

### 10. List all branches (local + remote)  
`git branch -a`  
Use: Displays all branches, including remote branches stored in GitHub.  

## Pushing Changes to GitHub

### 11. Push local branch and set upstream  
`git push -u origin <branchname>`  
Use: Pushes the branch to GitHub and sets it as the default upstream branch, so you can just use `git push` next time.  

### 12. Push changes without setting upstream  
`git push origin <branchname>`  
Use: Pushes changes to GitHub, but you have to specify the branch every time.  

## Summary

These commands help you:  
- Initialize and check repo status.  
- Stage and commit changes.  
- Undo mistakes.  
- Connect to GitHub and manage branches.  
- Push changes to GitHub.  

Now your Git workflow is properly structured! 🚀
