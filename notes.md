# My notes for Git & GitHub

---

## What is Git?

Git is a version control tool that helps us save our code. It keeps all the changes we make to code or any project files that we have.

---

## What is GitHub?

GitHub is a website. It saves our code online. So we can share it and work with others.

---

## Common Git Stuff

Common Git Stuff
git init
bash
Copy
Edit
$ git init
This command starts Git in our folder. It makes a hidden folder called .git where Git keeps track of changes.

git clone
bash
Copy
Edit
$ git clone <repo-url>
This command downloads a project and its history from a remote repository.

git add
bash
Copy
Edit
$ git add <filename>
$ git add .
Adds changes to the staging area. The . adds all modified files.

git commit
bash
Copy
Edit
$ git commit -m "your message"
Saves the staged changes with a message. This creates a new snapshot in Git history.

git push
bash
Copy
Edit
$ git push origin main
Uploads your local commits to the remote repository (like GitHub).

git pull
bash
Copy
Edit
$ git pull origin main
Downloads and merges the latest changes from the remote repository.

git status
bash
Copy
Edit
$ git status
Shows the status of your working directory — which files are modified, staged, or untracked.

git branch
bash
Copy
Edit
$ git branch
$ git branch <branchname>
Lists existing branches or creates a new one.

git checkout
bash
Copy
Edit
$ git checkout <branchname>
Switches to the specified branch.

git merge
bash
Copy
Edit
$ git merge <branchname>
Merges changes from the specified branch into the current branch.

git reset
bash
Copy
Edit
$ git reset <file>
$ git reset --hard HEAD~1
Unstages or undoes commits. Use with caution, especially --hard.

git log
bash
Copy
Edit
$ git log
Shows the commit history in reverse chronological order.

git config
bash
Copy
Edit
$ git config --global user.name "Your Name"
$ git config --global user.email "you@example.com"
Sets your name and email address for commit authorship.

git revert
bash
Copy
Edit
$ git revert <commit-hash>
