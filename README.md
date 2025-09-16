# Git & GitHub Notes

## 📌 Contents
- Importance of Git
- Git Use Cases
- Version Control System
- What is Git?
- Why Git?
- What is GitHub?
- Difference Between Git & GitHub
- Git Setup (Local + GitHub + VS Code)
- Git Workflow (add, commit, push, pull)
- Git Branching & Merge
- Git Commands

---

## 🔹 What is Version Control?
Version control is a system that tracks changes to files over time, allowing developers to:
- Revert to previous versions  
- Collaborate efficiently  
- Manage different code versions  

It prevents **data loss** and ensures **smooth teamwork** in software development.

---

## 🔹 What is Git?
Git is a **distributed version control system** that tracks changes in code, allowing multiple developers to collaborate efficiently.

### ✅ Use Cases of Git
- Software Development  
- Project Management  
- Tracking Versions  

---

## 🔹 What is GitHub?
GitHub is a **cloud-based platform** that hosts Git repositories, enabling developers to collaborate, manage code, and track changes efficiently.

---

## 🔹 Difference Between Git & GitHub
- **Git** → Works locally to track changes in files and folders. Helps organize code with branches.  
- **GitHub** → A cloud platform that hosts the local repo online. Anyone with repo access can contribute changes.  

---

## 🔹 Git Workflow
```
Local Files → Staging Area → Committed Changes → GitHub Repo
```

### Common Commands
```bash
# Add files to staging area
git add --all        # or git add .

# Commit changes locally
git commit -m "message"

# Push changes to GitHub
git push origin branchName

# Pull latest changes from GitHub
git pull origin branchName
```

---

## 🔹 Git Branches & Commands

```bash
# List all local branches
git branch

# Create a new branch
git branch <branch-name>

# Switch to a branch
git checkout <branch-name>
git switch <branch-name>

# Create + Switch to new branch
git checkout -b <branch-name>
git switch -c <branch-name>

# Merge a branch
git merge <branch-name>

# Delete local branch
git branch -d <branch-name>   # only if fully merged
git branch -D <branch-name>   # force delete

# Delete remote branch
git push origin --delete <branch-name>

# Rename a branch
git branch -m <old-name> <new-name>

# List remote branches
git branch -r
```

---

✍️ Notes prepared by *Tech Jashwanth*
