# Git Branching Workflow Project

## Project Overview

This project demonstrates a basic Git branching workflow used by development teams. It shows how developers can create feature branches, work independently, and merge their work back into the main branch.

## Tools Used

* Git
* Git Bash
* GitHub

## Project Steps

### 1. Initialize Git Repository

```
git init
```

### 2. Create a File

```
touch login.txt
```

### 3. Add and Commit the File

```
git add .
git commit -m "first commit"
```

### 4. Create a Feature Branch

```
git branch feature-login
```

### 5. Switch to the Feature Branch

```
git checkout feature-login
```

### 6. Work on the Feature

Add content inside `login.txt`.

### 7. Switch Back to Main Branch

```
git checkout main
```

### 8. Merge the Feature Branch

```
git merge feature-login
```

## Project Structure

```
git-branch-project/
│
├── login.txt
└── README.md
```

## What I Learned

* How Git branches work
* How to create feature branches
* How to merge branches
* Basic Git workflow used in DevOps teams

## Author

Dada Oluwaferanmi E

GitHub: https://github.com/feranzeey

