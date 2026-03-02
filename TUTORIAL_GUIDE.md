# GitHub Skills Tutorial Guide

## Introduction to GitHub

This repository contains a GitHub Skills interactive tutorial designed to teach you the basics of working with GitHub. The tutorial guides you through creating branches, making commits, opening pull requests, and merging changes.

## Current Status

The tutorial has been initialized and is ready for you to complete! You can track your progress in the Exercise issue (typically Issue #2) in your repository's Issues tab.

## How to Complete the Tutorial

### Step 1: Create a Branch

1. Navigate to your repository (the one you copied from the GitHub Skills template)
2. Click on the **Code** tab (if not already there)
3. Click on the branch dropdown that says "main"
4. In the search box, type: `my-first-branch`
5. Click "Create branch: my-first-branch from main"

Once you create the branch, the GitHub Actions workflow will automatically detect it and post the next step in the Exercise issue (check your repository's Issues tab).

### Step 2: Commit a File

1. Make sure you're on the `my-first-branch` branch (check the branch dropdown)
2. Click "Add file" → "Create new file"
3. Name the file: `PROFILE.md`
4. Add the following content:
   ```
   Welcome to my GitHub profile!
   ```
5. Scroll down and in the commit message box, type: `Add PROFILE.md`
6. Make sure "Commit directly to the my-first-branch branch" is selected
7. Click "Commit new file"

The workflow will detect your commit and provide the next instructions.

### Step 3: Open a Pull Request

1. After committing, you should see a yellow banner with "Compare & pull request" - click it
   - If you don't see it, go to the "Pull requests" tab and click "New pull request"
2. Make sure:
   - **base:** is `main`
   - **compare:** is `my-first-branch`
3. Title your pull request: `Add my first file`
4. Add a description of what you did (e.g., "Created a new branch, added a PROFILE.md file")
5. Click "Create pull request"

### Step 4: Merge Your Pull Request

1. On your pull request page, wait for any checks to complete
2. Click the green "Merge pull request" button
3. Click "Confirm merge"
4. Click "Delete branch" to clean up

## What You'll Learn

- **Repositories**: Projects containing files and folders that track versions
- **Branches**: Parallel versions of your repository for safe experimentation  
- **Commits**: Sets of changes to files and folders in your project
- **Pull Requests**: Proposals to merge changes from one branch to another
- **Merging**: Combining changes from a pull request into the main branch

## Tips

- Take your time - this is a self-paced tutorial
- Read the explanations in Issue #2 - they provide valuable context
- Don't worry if you make mistakes - that's part of learning!
- The workflows will guide you with feedback after each step

## Resources

- [GitHub Docs](https://docs.github.com)
- [GitHub Skills](https://skills.github.com)
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)

---

Happy learning! 🎉
