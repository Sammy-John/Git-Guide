# Git Basics Cheatsheet
A quick reference for essential Git commands.

## 📂 Repository Management
- `git init`: Initialize a new Git repository.
- `git clone <url>`: Clone a repository from a remote source.
- `git status`: Check the status of your working directory.

## 📥 Staging and Committing
- `git add <file>`: Stage a file for commit.
- `git add .`: Stage all changes in the current directory.
- `git commit -m "message"`: Commit staged changes with a message.

## 🌲 Branching and Merging
- `git branch`: List all branches.
- `git branch <branch-name>`: Create a new branch.
- `git checkout <branch-name>`: Switch to a branch.
- `git merge <branch-name>`: Merge a branch into the current branch.

## 🔄 Synchronizing with Remote
- `git pull`: Fetch and merge changes from the remote repository.
- `git push`: Push local commits to the remote repository.

---

## 🛠️ Advanced Git Commands

### Reset and Revert
- `git reset --soft HEAD~1`: Undo the last commit but keep changes staged.
- `git reset --hard HEAD~1`: Completely undo the last commit and discard changes.
- `git revert <commit-hash>`: Create a new commit that reverses a specific commit.

### Stashing Changes
- `git stash`: Save changes without committing them.
- `git stash pop`: Apply the last stashed changes and remove them from the stash.
- `git stash list`: Show all stashed changes.

### Rebasing
- `git rebase <branch-name>`: Reapply commits from one branch onto another.
- `git rebase -i HEAD~<n>`: Interactive rebase to squash or edit commits.

### Tagging
- `git tag <tag-name>`: Create a lightweight tag for a specific commit.
- `git tag -a <tag-name> -m "message"`: Create an annotated tag with metadata.
- `git push origin <tag-name>`: Push a tag to the remote repository.

