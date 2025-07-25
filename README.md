﻿# Getting Started with Git and GitHub

This guide will help you set up a Git repository locally and push it to GitHub using basic Git commands.

## 🔧 Prerequisites

- [Git](https://git-scm.com/downloads) installed on your computer
- A [GitHub account](https://github.com/)
- Internet connection

---

## 🧱 Step-by-Step Setup

### 1. Create a Repository on GitHub

1. Go to [github.com](https://github.com)
2. Click on the **+** icon (top-right) and select **"New repository"**
3. Enter a repository name (e.g., `my-project`)
4. Choose visibility: **Public** or **Private**
5. Click **Create repository**

---

### 2. Initialize Git Locally

In your terminal (Command Prompt, PowerShell, or Bash):

```bash
cd path/to/your/project-folder
git init
git add .
git add index.html
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin master
git push -u origin main
| Command                   | Description                                |
| ------------------------- | ------------------------------------------ |
| `git status`              | Check the status of your working directory |
| `git add <file>`          | Stage a file for commit                    |
| `git commit -m "message"` | Commit changes with a message              |
| `git log`                 | View commit history                        |
| `git push`                | Push changes to GitHub                     |
| `git pull`                | Pull changes from GitHub                   |
| `git clone <repo-url>`    | Clone an existing repository               |



