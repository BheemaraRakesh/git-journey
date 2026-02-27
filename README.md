# Git Commands Reference

This file contains a list of important Git commands for everyday use.

## Configuration

- `git config --global user.name "Your Name"` - set username
- `git config --global user.email "you@example.com"` - set email

## Repository Setup

- `git init` - initialize a new Git repository
- `git clone <repository_url>` - clone an existing repository

## Basic Workflow

- `git status` - show the working tree status
- `git add <file>` - stage changes for commit
- `git add .` - stage all changes
- `git commit -m "message"` - commit staged changes with a message
- `git log` - view commit history

## Branching

- `git branch` - list branches
- `git branch <name>` - create a new branch
- `git checkout <branch>` - switch to a branch
- `git checkout -b <branch>` - create and switch to a new branch
- `git merge <branch>` - merge a branch into the current branch

## Remote Repositories

- `git remote -v` - list remote connections
- `git remote add origin <url>` - add a remote repository
- `git push` - push changes to remote
- `git push -u origin <branch>` - push and set upstream
- `git pull` - fetch from and merge with remote

## Stashing

- `git stash` - stash changes
- `git stash pop` - apply stashed changes and remove from stash

## Undoing Changes

- `git checkout -- <file>` - discard changes in working directory
- `git reset HEAD <file>` - unstage a file
- `git revert <commit>` - create a new commit that undoes a commit
- `git reset --hard <commit>` - reset to a specific commit, discarding changes

## Tags

- `git tag` - list tags
- `git tag <name>` - create a new tag
- `git push origin <tag>` - push a tag to remote

Feel free to add more commands as needed.