# Git Commands

---

## `git init`

$ git init

**Description**: Initializes a new Git repository in the current folder.

---

## `git clone`

$ git clone <repo-url>

**Description**: Clones a repository from a remote server like GitHub.

---

## `git add`

$ git add <filename>
$ git add .

**Description**: Adds changes to the staging area.

---

## `git commit`

$ git commit -m "your message"


**Description**: Saves staged changes with a message.

---

## `git push`

$ git push origin main

**Description**: Pushes committed changes to a remote repository.

---

## `git pull`

$ git pull origin main

**Description**: Fetches and merges changes from a remote repository.

---

## `git status`

$ git status

**Description**: Shows the current state of the working directory.

---

## `git branch`

$ git branch
$ git branch <branchname>

**Description**: Lists, creates, or deletes branches.

---

## `git checkout`

$ git checkout <branchname>

**Description**: Switches between branches or restores files.

---

## `git merge`

$ git merge <branchname>

**Description**: Combines one branch into another.

---

## `git reset`

$ git reset <file>
$ git reset --hard HEAD~1

**Description**: Unstages or reverts commits.

---

## `git log`

$ git log

**Description**: Shows commit history.

---

## `git config`

$ git config --global user.name "Your Name"
$ git config --global user.email "you@example.com"

**Description**: Sets configuration for user details, editor, etc.

---

## `git revert`

$ git revert <commit-hash>

**Description**: Reverses a specific commit by creating a new commit.
