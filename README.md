## Git Learning Repository

Welcome to the Git Learning Repository! This repository is designed to help you learn and practice Git, a powerful version control system used for tracking changes in your projects.

## Git Cheat Sheet

### Basic Commands

* **git init**: Initialize a new Git repository in the current directory.

   ```sh
   git init
   ```

* **git clone <repository_url>**: Clone a repository from a remote URL to your local machine.

   ```sh
   git clone [https://github.com/username/repo.git](https://github.com/username/repo.git)
   ```

* **git status**: Show the working directory status.

   ```sh
   git status
   ```

* **git add <file>**: Add file contents to the index (staging area).

   ```sh
   git add filename
   ```

* **git commit -m "message"**: Record changes to the repository with a message.

   ```sh
   git commit -m "Initial commit"
   ```

* **git push**: Update remote refs along with associated objects.

   ```sh
   git push origin main
   ```

* **git pull**: Fetch from and integrate with another repository or a local branch.

   ```sh
   git pull origin main
   ```

## Branching and Merging

* **git branch**: List, create, or delete branches.

   ```sh
   git branch
   git branch new-branch
   ```

* **git checkout <branch>**: Switch to a specified branch and update the working directory.

   ```sh
   git checkout main
   ```

* **git merge <branch>**: Join two or more development histories together.

   ```sh
   git merge new-branch
   ```

* **git branch -d <branch>**: Delete a specified branch.

   ```sh
   git branch -d new-branch
   ```

## Undoing Changes

* **git reset <file>**: Unstage a file.

   ```sh
   git reset filename
   ```

* **git revert <commit>**: Create a new commit that undoes changes from a previous commit.

   ```sh
   git revert <commit>
   ```

## Viewing History

* **git log**: Show the commit logs.

   ```sh
   git log
   ```

* **git diff**: Show changes between commits, commit and working tree, etc.

   ```sh
   git diff
   ```

* **git show <commit>**: Show various types of objects.

   ```sh
   git show <commit>
   ```

## Stashing

* **git stash**: Stash the changes in a dirty working directory away.

   ```sh
   git stash
   ```

* **git stash pop**: Apply the stashed changes and remove them from the stash list.

   ```sh
   git stash pop
   ```

## Remote Repositories

* **git remote**: Manage set of tracked repositories.

   ```sh
   git remote -v
   ```

* **git fetch**: Download objects and refs from another repository.

   ```sh
   git fetch origin
   ```

## Configuration

* **git config --global user.name "Your Name"**: Set the name for your commits.

   ```sh
   git config --global user.name "Your Name"
   ```

* **git config --global user.email "you@example.com"**: Set the email for your commits.

   ```sh
   git config --global user.email "you@example.com"
   ```
