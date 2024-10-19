## Setup & Configuration:

- `git config --global user.name "Your Name"`  
  Set your Git username.
- `git config --global user.email "you@example.com"`  
  Set your Git email.
- `git config --list`  
  View your Git configuration.

## Starting a Repository:

- `git init`  
  Initialize a new Git repository.
- `git clone <repo_url>`  
  Clone an existing repository.

## Basic Operations:

- `git status`  
  Show the current status of the working directory and staging area.
- `git add <file>`  
  Stage a file for the next commit.
- `git add .`  
  Stage all modified and new files for the next commit.
- `git commit -m "Your message"`  
  Commit staged changes with a message.
- `git commit -a -m "Your message"`  
  Commit all modified tracked files with a message (skips `git add`).

## Branching:

- `git branch`  
  List all branches.
- `git branch <branch_name>`  
  Create a new branch.
- `git checkout <branch_name>`  
  Switch to a different branch.
- `git checkout -b <branch_name>`  
  Create a new branch and switch to it.
- `git merge <branch_name>`  
  Merge the specified branch into the current branch.

## Viewing History:

- `git log`  
  View commit history.
- `git log --oneline`  
  View commit history in one line per commit.
- `git diff`  
  Show changes between commits, branches, or working directory.

## Undoing Changes:

- `git reset <file>`  
  Unstage a file (remove from staging area).
- `git checkout -- <file>`  
  Discard changes in a working directory file.
- `git reset --hard`  
  Reset the working directory and staging area to the last commit.
- `git revert <commit_hash>`  
  Create a new commit that undoes the specified commit.

## Remote Repositories:

- `git remote add origin <url>`  
  Add a remote repository.
- `git push origin <branch_name>`  
  Push changes to a remote repository.
- `git pull`  
  Fetch and merge changes from a remote repository.
- `git fetch`  
  Fetch changes from a remote repository without merging.

## Stashing Changes:

- `git stash`  
  Save changes in a temporary area and clean the working directory.
- `git stash pop`  
  Apply stashed changes and remove them from the stash list.
- `git stash list`  
  List all stashed changes.
