# Git Commands

---

## `git init`

$ git init

yaml
Copy
Edit
**Description**: Initializes a new Git repository in the current folder.

---

## `git clone`

$ git clone <repo-url>

yaml
Copy
Edit
**Description**: Clones a repository from a remote server like GitHub.

---

## `git add`

$ git add <filename>
$ git add .

yaml
Copy
Edit
**Description**: Adds changes to the staging area.

---

## `git commit`

$ git commit -m "your message"

yaml
Copy
Edit
**Description**: Saves staged changes with a message.

---

## `git push`

$ git push origin main

yaml
Copy
Edit
**Description**: Pushes committed changes to a remote repository.

---

## `git pull`

$ git pull origin main

yaml
Copy
Edit
**Description**: Fetches and merges changes from a remote repository.

---

## `git status`

$ git status

yaml
Copy
Edit
**Description**: Shows the current state of the working directory.

---

## `git branch`

$ git branch
$ git branch <branchname>

yaml
Copy
Edit
**Description**: Lists, creates, or deletes branches.

---

## `git checkout`

$ git checkout <branchname>

yaml
Copy
Edit
**Description**: Switches between branches or restores files.

---

## `git merge`

$ git merge <branchname>

yaml
Copy
Edit
**Description**: Combines one branch into another.

---

## `git reset`

$ git reset <file>
$ git reset --hard HEAD~1

yaml
Copy
Edit
**Description**: Unstages or reverts commits.

---

## `git log`

$ git log

yaml
Copy
Edit
**Description**: Shows commit history.

---

## `git config`

$ git config --global user.name "Your Name"
$ git config --global user.email "you@example.com"

yaml
Copy
Edit
**Description**: Sets configuration for user details, editor, etc.

---

## `git revert`

$ git revert <commit-hash>

pgsql
Copy
Edit
**Description**: Reverses a specific commit by creating a new commit.
