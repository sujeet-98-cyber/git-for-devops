Git Setup
git config --global user.name "Your Name": Set your Git username.
git config --global user.email "your.email@example.com": Set your Git email.
git config --global color.ui auto: Enable automatic command line coloring for Git.
2. Starting a New Repository
git init: Create a new local Git repository.
git clone <url>: Clone a remote repository to your local machine.
3. Adding Repository to GitHub
git remote add origin <url>: Link your local repository to a remote GitHub repository.
git push -u origin master: Push the local repository’s master branch to GitHub for the first time and set up tracking.
4. Basic Snapshotting
git add <file>: Add a file to the staging area.
git add .: Add all changes in the current directory to the staging area.
git commit -m "Commit message": Commit changes with a message.
git commit -a -m "Commit message": Skip the staging area and commit all changes directly.
5. Branching and Merging
git branch: List all branches in your repository.
git branch <branch-name>: Create a new branch.
git checkout <branch-name>: Switch to a specific branch.
git checkout -b <branch-name>: Create a new branch and switch to it.
git merge <branch-name>: Merge a branch into the current branch.
6. Inspecting and Comparing
git status: Show the working tree status.
git log: View the commit history.
git log --oneline: View a condensed commit history.
git diff: Show changes between working directory and index.
git diff <commit1> <commit2>: Show changes between two commits.
7. Stashing and Cleaning
git stash: Save changes temporarily.
git stash pop: Reapply the stashed changes and remove the stash.
git stash apply: Reapply the stashed changes without removing the stash.
git clean -f: Remove untracked files from the working directory.
8. Remote Repositories
git remote add origin <url>: Add a remote repository (such as GitHub).
git remote -v: List all remotes.
git push origin <branch-name>: Push the current branch to the remote repository.
git pull: Fetch and merge changes from the remote repository.
git fetch: Download changes from a remote repository without merging.
9. Undoing Changes
git reset --hard <commit>: Reset the working directory and index to a specific commit.
git reset <file>: Unstage a file from the index (staging area).
git revert <commit>: Create a new commit that undoes the changes from a specific commit.
git checkout <file>: Discard changes in a working directory.
10. Tagging
git tag <tag-name>: Create a tag.
git tag -a <tag-name> -m "Message": Create an annotated tag with a message.
git show <tag-name>: View the details of a specific tag.
git push origin <tag-name>: Push a tag to a remote repository.
11. Collaborating
git pull origin <branch>: Fetch and merge changes from the remote branch.
git push origin <branch>: Push local commits to a remote branch.
git rebase <branch>: Reapply commits on top of another base tip.
12. Viewing Repository Information
git show: Show various types of objects.
git reflog: Show the history of changes to the local repository.
git blame <file>: Show what revision and author last modified each line of a file.
13. Deleting Branches and Tags
git branch -d <branch-name>: Delete a local branch.
git branch -D <branch-name>: Force delete a local branch.
git tag -d <tag-name>: Delete a tag locally.
git push origin --delete <branch-name>: Delete a remote branch.
