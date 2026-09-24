# GitHub Beginner Guide

## NEXORA Student Chapter – VIIT

Welcome to the **NEXORA GitHub Beginner Guide**! If you are a first-year student or new to version control, this guide will teach you the fundamentals of Git and GitHub from scratch.

---

## 1. Core Concepts Explained from Zero

### What is Git?
**Git** is a free and open-source **Distributed Version Control System (VCS)**. Imagine it as a superpowered "undo" system for your code. It records changes made to files over time, allowing you to recall specific versions later, experiment safely, and collaborate without overwriting anyone else's code.

### What is GitHub?
**GitHub** is a cloud platform that hosts Git repositories online. It provides a visual web interface, collaboration tools, issue tracking, code review capabilities, and team management features on top of Git.

### Key Terms You Need to Know

| Term | Definition |
| :--- | :--- |
| **Repository (Repo)** | A project folder that contains all project files and their complete revision history tracked by Git. |
| **Clone** | Downloading a complete copy of a remote GitHub repository to your local computer. |
| **Commit** | A saved snapshot of changes in your project history, accompanied by a descriptive message. |
| **Branch** | An independent line of development. You create a branch to work on a feature without affecting the main codebase. |
| **Push** | Uploading your local commits from your computer to the remote GitHub repository. |
| **Pull** | Fetching and downloading updates from GitHub into your local working copy. |
| **Pull Request (PR)** | A request asking project maintainers to review and merge your branch's changes into the main branch. |
| **Issue** | A tracking ticket used to report bugs, request new features, or assign tasks. |
| **Fork** | Creating your own personal copy of someone else's GitHub repository under your account. |
| **Code Review** | When technical members or peers examine your Pull Request code to offer suggestions and ensure quality. |
| **Merge** | Combining changes from one branch (e.g., feature branch) into another branch (e.g., `main`). |

---

## 2. Essential Command Line Quickstart

Here are the basic commands you will use during development:

### Step 1: Configure Git (First Time Only)
Set your name and email so your commits are attributed to your GitHub profile:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 2: Clone a Repository
Download a repository to your machine:
```bash
git clone https://github.com/NEXORA-VIIT-ORG/repository-name.git
cd repository-name
```

### Step 3: Create and Switch to a Branch
Always create a branch before writing code:
```bash
git checkout -b feature/my-first-feature
```

### Step 4: Check Status and Stage Changes
See which files were modified and prepare them for committing:
```bash
# Check modified files
git status

# Stage specific files (or use 'git add .' to stage all changes)
git add path/to/file.js
```

### Step 5: Save a Commit
Create a snapshot of your staged changes:
```bash
git commit -m "feat(ui): add welcome banner component"
```

### Step 6: Keep Your Branch Updated (Pull Latest Changes)
Fetch and combine updates from the remote `main` branch:
```bash
git checkout main
git pull origin main
git checkout feature/my-first-feature
git merge main
```

### Step 7: Push Your Branch to GitHub
Upload your branch to GitHub so you can open a Pull Request:
```bash
git push -u origin feature/my-first-feature
```

---

## 3. Opening Your First Pull Request on GitHub

1. Go to the repository page on GitHub (`https://github.com/NEXORA-VIIT-ORG/<repo-name>`).
2. You will see a banner saying **"Compare & pull request"** for your pushed branch. Click it!
3. Fill out the **Pull Request Template**:
   - Give it a clear title.
   - Describe what changed and link the related Issue number.
   - Check off the verification checklist.
4. Click **Create Pull Request**.
5. Tag a `@NEXORA-VIIT-ORG/technical-team` member if you need assistance!

---

## 4. Helpful Tips for Beginners

- **Commit Small & Often**: It's much easier to review small commits than one giant commit with 50 changed files.
- **Never Work Directly on `main`**: Always create a feature or fix branch.
- **Don't Be Afraid to Ask**: Every experienced developer was once a beginner. Ask questions in PR comments or chapter meetings!
