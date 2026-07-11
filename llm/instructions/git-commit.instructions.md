---
applyTo: "*"
description: "Conventional commit style for commit messages"
---

# Commit Message Instructions

Write commit messages using the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

Types: `feat`, `fix`, `chore`, `docs`, `style`, `refactor`, `perf`, `test`, `ci`

Rules:
- First line ≤ 72 characters, no period
- Use imperative mood ("Add feature" not "Added feature")
- Body explains *why* and *what*, not *how*
- Reference issues/PRs in the footer
- Scope is optional but encouraged (e.g., `feat(api):`, `fix(auth):`)
- Breaking changes get a `!` after type/scope and `BREAKING CHANGE:` in footer
