# Contributing Guidelines

Thank you for being interested in contributing to Hacktoberfest! We're excited to have you here. Please take a moment to read these guidelines to ensure your contribution is smooth and meaningful.

## Code of Conduct

By participating in this project, you agree to abide by our [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Please read it before contributing.

## What Can You Contribute?

- **Profiles:** Share your GitHub profile and introduction
- **Code/Algorithms:** Add helpful algorithms or code snippets
- **Documentation:** Improve guides, READMEs, and learning materials
- **Fixes:** Bug fixes and improvements to existing code
- **Learning Resources:** Share tutorial links and educational content

## Before You Start

1. **Follow [@bhaveshpatil093](https://github.com/bhaveshpatil093)** on GitHub ⭐
2. Fork the repository
3. Create a new branch for your changes
4. Read this entire document

## Submission Guidelines

### Profile Contributions

**Image Requirements:**
- Format: PNG or JPG
- Size: Minimum 544x544 pixels (square)
- Location: `contributors/images/YOUR-USERNAME.png`
- File name must match your GitHub username

**Profile Format:**
- Location: `contributors/profiles/YOUR-USERNAME.md`
- Follow the template provided in README.md
- Keep it professional but friendly

### Code Contributions

**File Naming:**
- Use descriptive names: `fibonacci_algorithm.py` (not `code.py`)
- Use lowercase with underscores
- Location: `Add Code Here/[LANGUAGE]/FILENAME.ext`

**Code Quality:**
- Include comments explaining logic
- Add docstrings for functions
- Test your code
- Follow language conventions
- Keep functions focused and reusable

**Example Structure:**

```python
# fibonacci_algorithm.py
"""
Calculate Fibonacci number at position n using dynamic programming.
Time Complexity: O(n)
Space Complexity: O(n)
"""

def fibonacci(n):
    """Return the nth Fibonacci number."""
    if n <= 1:
        return n
    # Implementation here
```

### Documentation Improvements

- Use clear, simple language
- Add examples where applicable
- Fix typos and broken links
- Improve organization and readability
- Update outdated information

## Commit Message Guidelines

Use clear, descriptive commit messages:

```
feat: add fibonacci algorithm in Python
fix: correct typo in README
docs: improve contributing guidelines
refactor: simplify sorting algorithm
```

**Format:**

```
[type]: [description]

[optional body]
```

**Types:** `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

## Pull Request Process

### 1. Create a Descriptive PR Title

**Bad:** "Update files"  
**Good:** "feat: add quick sort algorithm in JavaScript"

### 2. Include a Description

```
## Description
Added a quick sort algorithm implementation with time complexity analysis.

## Type of Change
- [x] New feature
- [ ] Bug fix
- [ ] Documentation update

## Testing
Tested with arrays of different sizes and verified correctness.
```

### 3. Link Related Issues

If your PR fixes an issue, include `Fixes #123`

### 4. Be Responsive

- Respond to review comments promptly
- Make requested changes
- Ask for clarification if needed

## What We're Looking For

### ✅ Good Contributions

- Original code or meaningful improvements
- Clear documentation
- Helpful additions to the community
- Respectful and constructive communication

### ❌ We Won't Accept

- Duplicate submissions
- Low-effort changes (single character changes without purpose)
- Offensive or inappropriate content
- Code that violates open-source practices
- Spam or irrelevant contributions

## After Your PR is Merged

- Celebrate! 🎉
- Share your achievement on social media
- Tag us @bhaveshpatil093 and use #Hacktoberfest
- Come back and contribute more!

## Need Help?

- Check [Documentation/GETTING_STARTED.md](Documentation/GETTING_STARTED.md)
- Review existing PRs for examples
- Open an issue with your question
- Join our Discord community
- Contact [@bhaveshpatil093](https://github.com/bhaveshpatil093)

## Important Reminders

⭐ **FOLLOW [@bhaveshpatil093](https://github.com/bhaveshpatil093)** - This helps us review your PR faster!

---

Thank you for contributing! Your participation helps build a stronger open-source community. 💪
