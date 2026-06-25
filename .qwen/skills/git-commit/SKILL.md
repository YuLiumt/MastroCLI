---
name: git-commit
description: Generate concise git commit messages based on code changes
---

# Git Commit Message Generator

## Instructions

When invoked, follow these steps:

1. Run `git status` to see what files have changed
2. Run `git diff HEAD` (or `git diff` for unstaged changes) to review the actual code changes
3. Run `git log -n 5 --oneline` to understand the project's commit message style
4. Analyze the changes and generate an appropriate commit message

## Commit Message Format

Use conventional commits format:

```
<type>: <description>
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `refactor`: Code refactoring
- `deps`: Dependency changes
- `chore`: Maintenance tasks

### Guidelines
- Keep the message concise and direct (under 50 characters for the subject)
- Use imperative mood ("add" not "added")
- No period at the end
