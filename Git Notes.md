 Git Notes — 10 Essential Commands

## 1. git init
Initializes a new Git repository in your project folder.

git init


## 2. git add
Stages files for commit. Use `git add .` to stage all changes.

git add README.md
git add .


## 3. git commit
Creates a snapshot of your staged changes with a message.

git commit -m “Add README”


## 4. git status
Shows which files are staged, unstaged, or untracked.

git status


## 5. git push
Uploads your commits to GitHub.

git push -u origin main


## 6. git pull
Downloads and merges changes from GitHub into your local branch.

git pull origin main


## 7. git fetch
Downloads changes from GitHub without merging them yet.

git fetch origin


## 8. git log
Shows your commit history.

git log
git log --oneline


## 9. git branch
Lists, creates, or deletes branches.

git branch
git branch -M main
git branch feature-branch


## 10. git diff
Shows differences between your current changes and the last commit.

git diff
git diff HEAD

## 11. git checkout
Helps in creating and switching between repo's

## 12 git reset
git reset undoes commits or unstages files. git reset HEAD~1 undoes your last commit but keeps the changes. git reset --hard HEAD~1 undoes and deletes the changes completely.