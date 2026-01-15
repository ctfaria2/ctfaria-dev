# Commit Skill

Use conventional commit format for all commits in this repository.

## Format

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

## Types

- **feat**: New feature
- **fix**: Bug fix
- **docs**: Documentation changes
- **style**: Code style changes (formatting, no logic change)
- **refactor**: Code refactoring (no feature or fix)
- **test**: Adding or updating tests
- **chore**: Maintenance tasks, dependencies, config

## Rules

1. Use lowercase for type and description
2. No period at end of description
3. Keep description under 72 characters
4. Use imperative mood ("add" not "added" or "adds")
5. Scope is optional but useful for larger projects

## Examples

```
feat: add dark mode toggle
fix: correct typo in about page
docs: add license file
chore: update hugo version in ci
feat(blog): add reading time to posts
```
