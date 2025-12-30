# GitHub Repository Setup Guide

## Prerequisites

1. Install Git: https://git-scm.com/download/win
2. Create a GitHub account: https://github.com
3. Create a new repository on GitHub (empty, no README)

## Setup Steps

### 1. Open Terminal/PowerShell in this directory
```
cd "C:\Users\cytron\December Newsletter"
```

### 2. Initialize Git Repository
```bash
git init
```

### 3. Add All Files
```bash
git add .
```

### 4. Create Initial Commit
```bash
git commit -m "Initial commit: Year-end newsletter email template"
```

### 5. Add GitHub Remote
Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name:
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

### 6. Rename Default Branch to Main (if needed)
```bash
git branch -M main
```

### 7. Push to GitHub
```bash
git push -u origin main
```

## Alternative: Using GitHub Desktop

1. Install GitHub Desktop: https://desktop.github.com
2. Open GitHub Desktop
3. Click "File" → "Add Local Repository"
4. Select this folder: `C:\Users\cytron\December Newsletter`
5. Click "Publish repository" in GitHub Desktop
6. Follow the prompts to create the repository on GitHub

## Quick Commands Reference

```bash
# Check status
git status

# Add changes
git add .

# Commit changes
git commit -m "Your commit message"

# Push to GitHub
git push

# Pull latest changes
git pull
```

## Files Included

- `year-end-email.html` - Main email template
- `README.md` - Project documentation
- `.gitignore` - Git ignore rules
- `GITHUB_SETUP.md` - This setup guide

