# Getting Started with Hacktoberfest 🚀

## Prerequisites

- GitHub account
- Git installed on your computer
- A text editor

## Quick Setup (5 minutes)

### 1. Fork the Repository

Visit [github.com/bhaveshpatil093/Hacktoberfest](https://github.com/bhaveshpatil093/Hacktoberfest) and click **Fork**

### 2. Clone Your Fork
```bash
git clone https://github.com/YOUR-USERNAME/Hacktoberfest.git
cd Hacktoberfest
git remote add upstream https://github.com/bhaveshpatil093/Hacktoberfest.git
```

### 3. Create a Branch

```bash
git checkout -b contribution/your-name
```

### 4. Make Your Contribution

**Add Profile:**
- Image: `contributors/images/YOUR-USERNAME.png` (544x544px)
- Profile: `contributors/profiles/YOUR-USERNAME.md`

```markdown
# Your Name

- **GitHub:** [@yourUsername](https://github.com/yourUsername)
- **Location:** City, Country
- **Interests:** Python, Web Development, Open Source
- **About:** Brief bio about yourself
```

**Add Code:**
- Create file in: `Add Code Here/[LANGUAGE]/filename.ext`

**Improve Docs:**
- Edit files in: `Documentation/`

### 5. Commit and Push

```bash
git add .
git commit -m "feat: add my profile"
git push origin contribution/your-name
```

### 6. Create Pull Request

1. Go to your fork on GitHub
2. Click "Compare & pull request"
3. Add a title and description
4. Click "Create pull request"

## Common Commands

```bash
# Check status
git status

# See your branches
git branch -a

# Switch branch
git checkout branch-name

# Update from upstream
git fetch upstream
git rebase upstream/main

# View commit history
git log --oneline
```

## Troubleshooting

| Issue | Solution |
|-------|----------|
| "fatal: destination path already exists" | Use different folder: `rm -rf Hacktoberfest` |
| "Permission denied (publickey)" | Use HTTPS instead of SSH |
| "upstream is not configured" | Run: `git remote add upstream https://github.com/bhaveshpatil093/Hacktoberfest.git` |
| "Changes not showing up" | Push changes: `git push origin branch-name` |

## Next Steps

1. ⭐ **Follow [@bhaveshpatil093](https://github.com/bhaveshpatil093)**
2. Read [CONTRIBUTING.md](../CONTRIBUTING.md)
3. Join [Discord community](https://discord.gg/hacktoberfest)
4. Make your first contribution!

---

Happy Contributing! 🎉
