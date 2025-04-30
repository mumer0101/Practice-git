# Git Commands Cheat Sheet  
---

### Git Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "your@example.com"
git config --list
```

---

### Repository Setup
```bash
git init
git clone <repo-url>
```

---

### Basic Workflow
```bash
git status
git add <file>
git add .
git commit -m "message"
git log
```

---

### Branching
```bash
git branch
git branch <new-branch>
git checkout <branch>
git checkout -b <branch>
git merge <branch>
git branch -d <branch>
```

---

### Remote Repositories
```bash
git remote -v
git remote add origin <url>
git push -u origin <branch>
git push
git pull
git fetch
```

---

### Undoing Changes
```bash
git reset <file>
git reset --hard
git revert <commit>
git checkout -- <file>
git commit --amend
```

---

### Viewing & Comparing
```bash
git diff
git diff --staged
git show <commit>
git log --oneline --graph
```

---

### Tags
```bash
git tag
git tag <name>
git tag -a <name> -m "msg"
git push origin <tag>
```

---

### Stashing
```bash
git stash
git stash list
git stash apply
git stash drop
```

---

### Remote Authentication
```bash
git remote set-url origin git@github.com:user/repo.git
git remote set-url origin https://<token>@github.com/user/repo.git
```

---

### Git Aliases (Optional)
```bash
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.cm commit
```
