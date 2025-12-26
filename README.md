<div align="center">

# haaziq ali

**learner • frontend & systems programming • 15 year old**

I build things that solve problems, explore code deeply, and think about how things work.

**Currently:**  C++  
**Reading:** The Death of ivan ilyich by Leo Tolstoy

---

I also do calisthenics, write my thoughts, ideals, and ideas.  
My interests include computers[whole], chess, philosophy, classical literature, and anime.

### what i work with

`Next.js` `Tailwind CSS` `C` `Git` `Arch Linux` `Nvim`

<sub>ps: i love minimalism, improving everyday and a great admirer of stoicism</sub>

</div>

---

## 📁 Repository Structure

```
HAAZIQ-ALI/
├── .git/              # Git version control directory
└── README.md          # This file - personal profile and Git guide
```

---

## ⌨️ Essential Git Keybinds & Commands

### Basic Commands

```bash
# Initialize repository
git init

# Clone repository
git clone <url>

# Check status
git status

# Add files to staging
git add <file>          # Add specific file
git add .               # Add all files

# Commit changes
git commit -m "message"

# Push to remote
git push origin <branch>

# Pull from remote
git pull origin <branch>
```

### Branch Management

```bash
# List branches
git branch              # Local branches
git branch -a           # All branches (local + remote)

# Create new branch
git branch <branch-name>
git checkout -b <branch-name>    # Create and switch

# Switch branches
git checkout <branch-name>
git switch <branch-name>         # Modern alternative

# Delete branch
git branch -d <branch-name>      # Safe delete
git branch -D <branch-name>      # Force delete

# Merge branch
git merge <branch-name>
```

### Viewing History

```bash
# View commit history
git log
git log --oneline              # Compact view
git log --graph --oneline      # Visual graph

# View changes
git diff                       # Unstaged changes
git diff --staged              # Staged changes
git diff <commit1> <commit2>   # Between commits

# Show specific commit
git show <commit-hash>
```

### Undoing Changes

```bash
# Discard changes in working directory
git checkout -- <file>
git restore <file>             # Modern alternative

# Unstage files
git reset HEAD <file>
git restore --staged <file>    # Modern alternative

# Reset to previous commit
git reset --soft HEAD~1        # Keep changes staged
git reset --hard HEAD~1        # Discard all changes

# Revert commit
git revert <commit-hash>
```

### Remote Management

```bash
# View remotes
git remote -v

# Add remote
git remote add <name> <url>

# Remove remote
git remote remove <name>

# Fetch changes
git fetch origin

# Pull with rebase
git pull --rebase origin <branch>
```

### Stashing

```bash
# Save work temporarily
git stash
git stash save "description"

# List stashes
git stash list

# Apply stash
git stash apply
git stash pop              # Apply and remove

# Drop stash
git stash drop
git stash clear            # Clear all stashes
```

### Advanced Commands

```bash
# Interactive rebase
git rebase -i HEAD~<n>

# Cherry-pick commit
git cherry-pick <commit-hash>

# Tag commits
git tag <tag-name>
git tag -a <tag-name> -m "message"

# Clean untracked files
git clean -n               # Dry run
git clean -fd              # Force delete
```

---

## 🔄 Git Workflow

### Feature Branch Workflow

1. **Create feature branch**
   ```bash
   git checkout -b feature/new-feature
   ```

2. **Make changes and commit**
   ```bash
   git add .
   git commit -m "Add new feature"
   ```

3. **Push to remote**
   ```bash
   git push origin feature/new-feature
   ```

4. **Create pull request** (on GitHub/GitLab)

5. **Merge and cleanup**
   ```bash
   git checkout main
   git pull origin main
   git branch -d feature/new-feature
   ```

### Quick Commit Workflow

```bash
# Check what changed
git status

# Stage changes
git add .

# Commit with message
git commit -m "Clear, descriptive message"

# Push to remote
git push
```

---

## 🎯 Git Best Practices

- ✅ Write clear, descriptive commit messages
- ✅ Commit often, push regularly
- ✅ Use branches for new features
- ✅ Keep commits atomic (one logical change per commit)
- ✅ Pull before you push to avoid conflicts
- ✅ Review changes before committing (`git diff`)
- ✅ Use `.gitignore` to exclude unnecessary files

---

## 🛠️ Configuration

### Set up Git identity

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Useful aliases

```bash
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.lg "log --graph --oneline --decorate"
```

---

## 📚 Resources

- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Guides](https://guides.github.com/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
