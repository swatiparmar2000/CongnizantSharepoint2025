# My notes for Git & GitHub

## What is Git?

Git is a version control tool that helps us save our code. It keeps all the changes we make to code or any project files that we have. 

## What is GitHub?

GitHub is a website. It saves our code online. So we can share it and work with others.

---

## Common Git Stuff

### `git init`

```bash
$ git init
```

This command starts git in our folder. It makes a hidden folder `.git` where git keeps track of changes.

### `git clone`

```bash
$ git clone <url>
```

We use this to download code from GitHub. We give it a URL. It brings the code to our computer.

### `git add`

```bash
$ git add <file>
```

After we change or create files, we use this command to tell git to track those files. Like saying "hey git, look at this file."

### `git commit`

```bash
$ git commit -m "your message"
```

This command saves the changes. We write a small message with it to say what we changed.

### `git push`

```bash
$ git push
```

This sends our changes to GitHub. Now others can see our changes online.

### `git pull`

```bash
$ git pull
```

If someone else made changes and pushed them, we use pull to get those new changes to our computer.

---

## Branches

### `git branch`

```bash
$ git branch
$ git branch new-branch-name
```

We use this to see what branch we are on. We can also make a new branch like above.

### `git checkout`

```bash
$ git checkout new-branch-name
```

We use this to move to a branch.

### `git merge`

```bash
$ git checkout main
$ git merge new-branch-name
```

This command mixes one branch into another. It takes changes from `new-branch-name` and puts them into `main`.

---

## Reverting Stuff (Like Ctrl + Z)

### `git reset`

```bash
$ git reset --hard <commit-id>
```

This can take back changes. It goes back to a past commit.

> **Personal note:** When I reset and try to push to GitHub, it does not work normal. I have to use:

```bash
$ git push --force
```

### `git revert`

```bash
$ git revert <commit-id>
```

This command makes a new commit that cancels an old one. It is safer than reset.

---

## GitHub Forking

Forking is when we copy someone else's repo from GitHub to our own GitHub. This lets us work on it without changing the original one.
