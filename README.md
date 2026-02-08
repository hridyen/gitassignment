# Git Assignment – Complete Workflow Demonstration

This repository demonstrates a complete Git workflow performed on Ubuntu Linux as part of an academic assignment.

The purpose of this assignment is to understand how Git works internally while handling real-world scenarios such as branching, merge conflicts, stash, cherry-pick, and squash.

---

## 🔧 Tools & Environment
- Operating System: Ubuntu (VirtualBox)
- Version Control System: Git
- Remote Repository: GitHub

---

## 📌 Concepts Covered

### 1. Repository Initialization
- Created a local Git repository using `git init`
- Performed the first commit to establish the main branch

### 2. Feature Branch Workflow
- Created multiple feature branches (`feature-login`, `feature-a`, `feature-b`, etc.)
- Ensured the `main` branch remained clean
- Merged feature branches back into `main`

### 3. Merge Conflict Handling
- Intentionally created merge conflicts by modifying the same file in different branches
- Manually resolved conflicts by editing conflict markers
- Committed the resolved changes

### 4. Git Stash
- Used `git stash` to temporarily save uncommitted changes
- Verified stash entries using `git stash list`
- Restored changes using `git stash pop`

### 5. Cherry-Pick
- Applied a specific commit from a feature branch to the `main` branch
- Demonstrated selective commit integration without merging the entire branch

### 6. Squash (Interactive Rebase)
- Created multiple temporary commits
- Used `git rebase -i` to squash commits into a single clean commit
- Maintained a readable and professional commit history

---

## 📊 Final Verification
The complete workflow can be verified using:
```bash
git log --oneline --graph --all

