## 🔧 **Git & GitHub Course Outline (Point-Based)**

### ✅ **1. Introduction to Git and GitHub**
- What is Git? What is GitHub?
- Version control basics
- Local vs remote repositories

---

### ✅ **2. Setting Up Git**
- Install Git (Windows/Mac/Linux)
- Configure Git:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
  ```

---

### ✅ **3. Git Basics (Local Git)**
- Create a repository:
  ```bash
  git init
  ```
- Check repo status:
  ```bash
  git status
  ```
- Track files:
  ```bash
  git add <filename>
  git add .  # Add all
  ```
- Commit changes:
  ```bash
  git commit -m "Message"
  ```

---

### ✅ **4. Viewing History**
- Log of commits:
  ```bash
  git log
  git log --oneline
  ```
- Differences between versions:
  ```bash
  git diff
  ```

---

### ✅ **5. Branching**
- Create branch:
  ```bash
  git branch <branch-name>
  ```
- Switch branch:
  ```bash
  git checkout <branch-name>
  ```
- Create and switch:
  ```bash
  git checkout -b <branch-name>
  ```
- Merge branches:
  ```bash
  git merge <branch-name>
  ```

---

### ✅ **6. Undoing Changes**
- Unstage file:
  ```bash
  git reset <file>
  ```
- Undo last commit (keep changes):
  ```bash
  git reset --soft HEAD~1
  ```
- Discard all local changes:
  ```bash
  git checkout -- .
  ```

---

### ✅ **7. Working with GitHub (Remote Repos)**
- Create GitHub account
- Create a repository on GitHub

---

### ✅ **8. Connecting Local to Remote**
- Add remote:
  ```bash
  git remote add origin https://github.com/username/repo.git
  ```
- Push code:
  ```bash
  git push -u origin main
  ```

---

### ✅ **9. Cloning and Pulling**
- Clone repo:
  ```bash
  git clone https://github.com/username/repo.git
  ```
- Pull latest changes:
  ```bash
  git pull
  ```

---

### ✅ **10. Collaborating on GitHub**
- Fork a repository
- Create a pull request
- Review and merge pull requests
- Resolve merge conflicts

---

### ✅ **11. Advanced Git**
- Stashing changes:
  ```bash
  git stash
  git stash pop
  ```
- Tagging releases:
  ```bash
  git tag v1.0
  git push origin v1.0
  ```
- Git aliases and custom configs

---

### ✅ **12. GitHub Features**
- GitHub Issues
- GitHub Actions (CI/CD)
- GitHub Pages (Host static sites)
- Contribution graph

---

### ✅ **13. Best Practices**
- Write clear commit messages
- Use `.gitignore` to exclude files
- Keep branches focused
- Regularly pull and merge

---

### ✅ **14. Git GUIs and Tools**
- GitHub Desktop
- VS Code Git Integration
- Sourcetree

---

### ✅ **15. Final Project**
- Create a repository
- Clone, branch, commit, push, and make a pull request
- Collaborate with a peer or fork and contribute to an open-source project

---

