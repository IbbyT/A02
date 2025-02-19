# A02
# Git, WebStorm, and GitHub Tutorial

## Introduction

This guide provides a step-by-step tutorial on using Git with WebStorm and GitHub. 

## Prerequisites

- Install [Git](https://git-scm.com/downloads)
- Install [WebStorm](https://www.jetbrains.com/webstorm/download/)
- Create a [GitHub](https://github.com/) account

## Step 1: Setting Up Git

1. Open the terminal (Command Prompt, Git Bash, or Terminal).
2. Configure your Git user:
   ```bash
   git config --global user.name "Name"
   git config --global user.email "email@example.com"
3. Verify the configuration:
   ```bash
   git config --list

## Step 2: Creating a New Repository
1. Go to GitHub, log in, and create a new repository.
2. Copy the repository URL.
3. Initialize Git
   ```bash
   git init
4. Connect the repository to GitHub: bash Copy Edit
   ```bash
   git remote add origin https://github.com/username/repository.git

## Step 3: Pushing to GitHub
1. Commit changes:
   ```bash
   git commit -m "Initial commit"
2. Push to GitHub: bash Copy Edit
   ```bash
   git push -u origin main
## References:
- Git Documentation
- https://www.datacamp.com/tutorial/git-push-pull
- https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

## Glossary

- **Branch**: A separate version of a project where you can make changes without affecting the main code.
- **Clone**: A copy of a repository that you save on your computer.
- **Commit**: A saved change in a repository that keeps track of updates.
- **Fetch**: A command that gets new changes from a remote repository, but doesn’t apply them yet.
- **GIT**: A system that helps track and manage changes in code.
- **Github**: A website where people store and collaborate on Git projects.
- **Merge**: A problem that happens when Git doesn’t know how to combine changes from different branches.
- **Merge Conflict**: A situation that arises when two branches have conflicting changes that Git cannot automatically resolve during a merge.
- **Push**: Sending your saved commits to a remote repository on GitHub.
- **Pull**: Getting the latest changes from a remote repository and updating your local copy.
- **Remote**: A version of a repository stored online, usually on GitHub.
- **Repository**: A place where all the files and history of a project are stored.
