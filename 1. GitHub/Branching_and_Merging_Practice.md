# Branching and Merging Practice

## What is a Branch?

A branch allows you to work on changes without affecting the main version of your project.
It helps keep new features or experiments separate until they are ready.

---

## What I Practiced

### Creating a New Branch

git checkout -b feature-branch

This command creates a new branch and switches to it.

---

### Making Changes on the Branch

- Edited files
- Added changes
- Committed updates using:

git add .
git commit -m "Added changes in feature branch"

---

### Switching Back to Main

git checkout main

This switches back to the main branch.

---

### Merging the Branch

git merge feature-branch

This merges the changes from the feature branch into the main branch.

---

## Why Branching Is Important

Branching allows safe experimentation and structured workflows.
It prevents breaking the main project while developing new features.

It is especially useful when collaborating with teams or managing multiple updates.
