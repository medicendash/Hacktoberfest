# Git Workflow Guide 🔄

## Complete Workflow from Start to Finish

### Step 1: Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 2: Fork & Clone

```bash
# Fork on GitHub first, then:
git clone https://github.com/YOUR-USERNAME/Hacktoberfest.git
cd Hacktoberfest
git remote add upstream https://github.com/bhaveshpatil093/Hacktoberfest.git
```

### Step 3: Create a Branch

```bash
git checkout -b contribution/add-profile
```

**Branch naming:**
- `contribution/add-profile`
- `feature/add-algorithm`
- `docs/improve-readme`
- `fix/typo`

### Step 4: Make Changes

Edit, add, or create files in your branch.

### Step 5: Commit Changes

```bash
git add .
git commit -m "feat: add my profile"
```

**Commit types:**
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation
- `refactor:` Code refactor

### Step 6: Push to Your Fork

```bash
git push origin contribution/add-profile
```

### Step 7: Create Pull Request

Go to GitHub and click "Compare & pull request"

## Essential Commands

```bash
# Check current status
git status

# See all branches
git branch -a

# Switch to a branch
git checkout branch-name

# Create and switch to new branch
git checkout -b new-branch-name

# View commit history
git log --oneline

# Update branch from upstream
git fetch upstream
git rebase upstream/main

# Discard local changes
git checkout -- filename

# Undo last commit (keep changes)
git reset --soft HEAD~1

# View changes
git diff

# Stash changes temporarily
git stash
git stash pop
```

## Common Git Scenarios

### Update Your Branch with Latest Changes

```bash
git fetch upstream
git rebase upstream/main
git push origin contribution/your-branch
```

### Fix Last Commit Message

```bash
git commit --amend -m "New message"
git push origin contribution/your-branch --force
```

### Squash Multiple Commits

```bash
git rebase -i HEAD~3
```

Then mark commits as `squash` and save.

### Merge Main Into Your Branch

```bash
git fetch upstream
git merge upstream/main
git push origin contribution/your-branch
```

### Revert to Previous Commit

```bash
git log --oneline
git revert commit-hash
git push origin contribution/your-branch
```

## Branch Management

```bash
# Create branch
git branch branch-name

# List local branches
git branch

# List all branches
git branch -a

# Delete local branch
git branch -d branch-name

# Delete remote branch
git push origin --delete branch-name

# Rename branch
git branch -m old-name new-name
```

## Useful Git Tips

```bash
# See what's in a commit
git show commit-hash

# Compare branches
git diff branch1 branch2

# Find which commits touched a file
git log -- filename

# Search commit messages
git log --grep="search term"

# Pretty log view
git log --oneline --graph --all --decorate
```

**Need help?** Check `GETTING_STARTED.md` or `FAQ.md`
