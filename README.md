# Git Commands Cheat Sheet

## Basic Commands

- **git init:** Initialize a new Git repository.
- **git status:** Check the status of your repository.
- **git add .:** Add all changes to the staging area.
- **git commit -m "message":** Commit changes with a descriptive message.
- **git diff:** View changes made to files since the last commit.
- **git branch:** List all branches in the repository.
- **git log:** Show a log of all commits.
- **git checkout <file>:** Undo changes to a file before committing.
- **git checkout <commit_hash>:** Move to a specific commit in the project's history.
- **git checkout <branch_name>:** Switch between branches.
- **git branch <new_branch_name> <commit_hash>:** Create a new branch from a specific commit.
- **git reflog:** View the full history of actions in the repository.
- **git reset --hard:** Reset the current branch to a specific commit or delete/reset commits.

## Advanced Commands

- **git tag <tag_name>:** Create a tag with a descriptive name for a specific commit.
- **git switch <branch_name>:** Switch to a different branch.
- **git merge <branch_name>:** Merge changes from one branch into the current branch.
- **git stash:** Temporarily save changes without committing them.
- **git stash list:** View a list of all stashed changes.
- **git stash pop:** Apply the most recent stash and remove it from the stash list.
- **git stash drop:** Remove the most recent stash from the stash list.
- **git pull origin <branch_name>:** Fetch changes from a remote repository and merge them into the current branch.
- **git push origin <branch_name>:** Push changes from a local branch to a remote repository.

## Additional Commands

- **git clone <repository_url>:** Clone a repository from a remote server to your local machine.
