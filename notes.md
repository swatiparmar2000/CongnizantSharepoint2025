# Git Commands 
---

### `git init`

```bash
$ git init
Description: Initializes a new Git repository in the current folder.

git clone
bash
Copy
Edit
$ git clone <repo-url>
Description: Clones a repository from a remote server like GitHub.

git add
bash
Copy
Edit
$ git add <filename>
$ git add .
Description: Adds changes to the staging area.

git commit
bash
Copy
Edit
$ git commit -m "your message"
Description: Saves staged changes with a message.

git push
bash
Copy
Edit
$ git push origin main
Description: Pushes committed changes to a remote repository.

git pull
bash
Copy
Edit
$ git pull origin main
Description: Fetches and merges changes from a remote repository.

git status
bash
Copy
Edit
$ git status
Description: Shows the current state of the working directory.

git branch
bash
Copy
Edit
$ git branch
$ git branch <branchname>
Description: Lists, creates, or deletes branches.

git checkout
bash
Copy
Edit
$ git checkout <branchname>
Description: Switches between branches or restores files.

git merge
bash
Copy
Edit
$ git merge <branchname>
Description: Combines one branch into another.

git reset
bash
Copy
Edit
$ git reset <file>
$ git reset --hard HEAD~1
Description: Unstages or reverts commits.

git log
bash
Copy
Edit
$ git log
Description: Shows commit history.

git config
bash
Copy
Edit
$ git config --global user.name "Your Name"
$ git config --global user.email "you@example.com"
Description: Sets configuration for user details, editor, etc.

git revert
bash
Copy
Edit
$ git revert <commit-hash>
Description: Reverses a specific commit by creating a new commit.
