# 🧰 Git Commands Cheat Sheet

A handy reference for working with Git — version control essentials.

---

## 🔧 SETUP

Configure user information used across all local repositories:

```bash
git config --global user.name "Your Name"
```
Sets your name for commits.

```bash
git config --global user.email "your.email@example.com"
```
Sets your email for commits.

---

## 🗂️ REPOSITORY SETUP

Initialize or clone repositories:

```bash
git init
```
Initialize a new Git repository in the current directory.

```bash
git clone [url]
```
Clone an existing repository from a remote server.

---

## 📦 STAGING & SNAPSHOTS

Track, stage, and commit changes:

```bash
git status
```
List the changed files and their status.

```bash
git add [file]
```
Stage a file for the next commit.

```bash
git reset [file]
```
Unstage a file, keeping the changes in your working directory.

```bash
git diff
```
Show changes between working directory and staging area.

```bash
git commit -m "Your descriptive message"
```
Commit staged changes with a message.

---

## 🌿 BRANCHING & MERGING

Work in isolated branches and merge changes:

```bash
git branch
```
List all branches. A `*` marks the current one.

```bash
git branch [branch-name]
```
Create a new branch.

```bash
git checkout [branch-name]
```
Switch to another branch.

```bash
git merge [branch-name]
```
Merge a branch into the current branch.

```bash
git log
```
View commit history of the current branch.

---

## 🔄 SHARE & UPDATE

Work with remote repositories:

```bash
git remote add [alias] [url]
```
Add a new remote with an alias.

```bash
git fetch [alias]
```
Fetch branches and history from a remote.

```bash
git merge [alias]/[branch]
```
Merge a specific remote branch into your local branch.

```bash
git pull
```
Fetch and merge from the tracking remote branch.

---
> 📘 **Tip:** Use `git help [command]` to get help for any Git command.
## 🙌 Contributing

Feel free to fork the repo, add examples, improve formatting, or add new features. Pull requests are welcome!


