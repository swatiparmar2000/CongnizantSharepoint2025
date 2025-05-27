# My notes for Git & GitHub

---

## What is Git?

Git is a version control tool that helps us save our code. It keeps all the changes we make to code or any project files that we have.

---

## What is GitHub?

GitHub is a website. It saves our code online. So we can share it and work with others.

---

## Common Git Stuff

### 1. `git init`

- **Description**: Initializes a new Git repository in the current folder.  
- **Usage**: `git init`  
- **Purpose**: Starts tracking version control.

---

### 2. `git clone`

- **Description**: Clones a repository from a remote server like GitHub.  
- **Usage**: `git clone <repo-url>`  
- **Purpose**: Makes a local copy of an existing remote repository.

---

### 3. `git add`

- **Description**: Adds changes to the staging area.  
- **Usage**:  
  - `git add <filename>`  
  - `git add .`  
- **Purpose**: Prepares files to be committed.

---

### 4. `git commit`

- **Description**: Saves staged changes with a message.  
- **Usage**: `git commit -m "your message"`  
- **Purpose**: Creates a version snapshot of the staged files.

---

### 5. `git push`

- **Description**: Pushes committed changes to a remote repository.  
- **Usage**: `git push origin main`  
- **Purpose**: Syncs local commits with remote repository.

---

### 6. `git pull`

- **Description**: Fetches and merges changes from a remote repository.  
- **Usage**: `git pull origin main`  
- **Purpose**: Updates your local branch with remote changes.

---

### 7. `git status`

- **Description**: Shows the current state of the working directory.  
- **Usage**: `git status`  
- **Purpose**: Helps see which files are staged, modified, or untracked.

---

### 8. `git branch`

- **Description**: Lists, creates, or deletes branches.  
- **Usage**:  
  - `git branch`  
  - `git branch <branchname>`  
- **Purpose**: Helps organize features/fixes.

---

### 9. `git checkout`

- **Description**: Switches between branches or restores files.  
- **Usage**: `git checkout <branchname>`  
- **Purpose**: Move between branches.

---

### 10. `git merge`

- **Description**: Combines one branch into another.  
- **Usage**: `git merge <branchname>`  
- **Purpose**: Integrates changes from one branch into the current branch.

---

### 11. `git reset`

- **Description**: Unstages or reverts commits.  
- **Usage**:  
  - `git reset <file>`  
  - `git reset --hard HEAD~1`  
- **Purpose**: Used to undo changes.

---

### 12. `git log`

- **Description**: Shows commit history.  
- **Usage**: `git log`  
- **Purpose**: Tracks the changes made over time.

---

### 13. `git config`

- **Description**: Sets configuration for user details, editor, etc.  
- **Usage**:  
  - `git config --global user.name "Your Name"`  
  - `git config --global user.email "you@example.com"`  
- **Purpose**: Ensures correct authorship on commits.

---

### 14. `git revert`

- **Description**: Reverses a specific commit by creating a new commit.  
- **Usage**: `git revert <commit-hash>`  
- **Purpose**: Safely undoes a commit without altering commit history.

---

